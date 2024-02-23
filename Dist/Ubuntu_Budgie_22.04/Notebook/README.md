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

Total: 141

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| TUXEDO        | InfinityBook S 15 Gen6      | [c80a1f64fc](https://linux-hardware.org/?probe=c80a1f64fc) | Jan 18, 2024 |
| Toshiba       | Satellite C855D-11X         | [d047649166](https://linux-hardware.org/?probe=d047649166) | Jan 14, 2024 |
| Alurin        | ALU-LPT-N4020-8256-140      | [61fdeffbaf](https://linux-hardware.org/?probe=61fdeffbaf) | Jan 12, 2024 |
| TUXEDO        | Pulse 14 Gen1               | [66efe29bec](https://linux-hardware.org/?probe=66efe29bec) | Jan 11, 2024 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | [0bc6f72a01](https://linux-hardware.org/?probe=0bc6f72a01) | Jan 09, 2024 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | [cce2fde2ac](https://linux-hardware.org/?probe=cce2fde2ac) | Jan 08, 2024 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | [fd3f275cfb](https://linux-hardware.org/?probe=fd3f275cfb) | Jan 07, 2024 |
| Apple         | MacBookPro8,3               | [b1467995b6](https://linux-hardware.org/?probe=b1467995b6) | Jan 06, 2024 |
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
| 5.15.0-27-generic     | 7         | 6.36%   |
| 5.15.0-50-generic     | 5         | 4.55%   |
| 5.15.0-48-generic     | 5         | 4.55%   |
| 6.2.0-39-generic      | 4         | 3.64%   |
| 5.19.0-46-generic     | 4         | 3.64%   |
| 5.15.0-52-generic     | 4         | 3.64%   |
| 5.19.0-41-generic     | 3         | 2.73%   |
| 5.19.0-35-generic     | 3         | 2.73%   |
| 5.15.0-53-generic     | 3         | 2.73%   |
| 5.15.0-40-generic     | 3         | 2.73%   |
| 5.15.0-39-generic     | 3         | 2.73%   |
| 5.15.0-30-generic     | 3         | 2.73%   |
| 6.5.0-14-generic      | 2         | 1.82%   |
| 6.5.0-10013-tuxedo    | 2         | 1.82%   |
| 6.2.0-33-generic      | 2         | 1.82%   |
| 6.2.0-32-generic      | 2         | 1.82%   |
| 6.2.0-26-generic      | 2         | 1.82%   |
| 6.2.0-10007-tuxedo    | 2         | 1.82%   |
| 5.19.0-42-generic     | 2         | 1.82%   |
| 5.19.0-38-generic     | 2         | 1.82%   |
| 5.15.0-67-generic     | 2         | 1.82%   |
| 5.15.0-58-generic     | 2         | 1.82%   |
| 5.15.0-56-generic     | 2         | 1.82%   |
| 5.15.0-47-generic     | 2         | 1.82%   |
| 5.15.0-46-generic     | 2         | 1.82%   |
| 5.15.0-33-generic     | 2         | 1.82%   |
| 5.15.0-25-generic     | 2         | 1.82%   |
| 6.5.0-10008-tuxedo    | 1         | 0.91%   |
| 6.3.1-060301-generic  | 1         | 0.91%   |
| 6.2.0-37-generic      | 1         | 0.91%   |
| 6.2.0-34-generic      | 1         | 0.91%   |
| 6.2.0-10018-tuxedo    | 1         | 0.91%   |
| 6.1.0-060100-generic  | 1         | 0.91%   |
| 5.19.0-45-generic     | 1         | 0.91%   |
| 5.19.0-40-generic     | 1         | 0.91%   |
| 5.19.0-32-generic     | 1         | 0.91%   |
| 5.19.0-051900-generic | 1         | 0.91%   |
| 5.15.0-89-generic     | 1         | 0.91%   |
| 5.15.0-88-lowlatency  | 1         | 0.91%   |
| 5.15.0-88-generic     | 1         | 0.91%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 62        | 61.39%  |
| 5.19.0  | 17        | 16.83%  |
| 6.2.0   | 14        | 13.86%  |
| 6.5.0   | 4         | 3.96%   |
| 5.13.0  | 2         | 1.98%   |
| 6.3.1   | 1         | 0.99%   |
| 6.1.0   | 1         | 0.99%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 62        | 61.39%  |
| 5.19    | 17        | 16.83%  |
| 6.2     | 14        | 13.86%  |
| 6.5     | 4         | 3.96%   |
| 5.13    | 2         | 1.98%   |
| 6.3     | 1         | 0.99%   |
| 6.1     | 1         | 0.99%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 95        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Budgie | 89        | 93.68%  |
| GNOME  | 5         | 5.26%   |
| KDE5   | 1         | 1.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 92        | 96.84%  |
| Wayland | 3         | 3.16%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 69        | 72.63%  |
| Unknown | 15        | 15.79%  |
| GDM3    | 10        | 10.53%  |
| SDDM    | 1         | 1.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 30        | 31.58%  |
| de_DE | 12        | 12.63%  |
| fr_FR | 11        | 11.58%  |
| en_GB | 6         | 6.32%   |
| pt_BR | 5         | 5.26%   |
| en_CA | 4         | 4.21%   |
| it_IT | 3         | 3.16%   |
| ru_RU | 2         | 2.11%   |
| hu_HU | 2         | 2.11%   |
| fr_BE | 2         | 2.11%   |
| en_IE | 2         | 2.11%   |
| pl_PL | 1         | 1.05%   |
| mt_MT | 1         | 1.05%   |
| ja_JP | 1         | 1.05%   |
| eu_ES | 1         | 1.05%   |
| es_PE | 1         | 1.05%   |
| es_MX | 1         | 1.05%   |
| es_ES | 1         | 1.05%   |
| es_EC | 1         | 1.05%   |
| es_CL | 1         | 1.05%   |
| es_AR | 1         | 1.05%   |
| en_SG | 1         | 1.05%   |
| en_IL | 1         | 1.05%   |
| en_AU | 1         | 1.05%   |
| da_DK | 1         | 1.05%   |
| cs_CZ | 1         | 1.05%   |
| C     | 1         | 1.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 54        | 56.84%  |
| EFI  | 41        | 43.16%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 82        | 83.67%  |
| Tmpfs   | 9         | 9.18%   |
| Overlay | 3         | 3.06%   |
| Zfs     | 2         | 2.04%   |
| Xfs     | 1         | 1.02%   |
| Btrfs   | 1         | 1.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 65        | 68.42%  |
| Unknown | 25        | 26.32%  |
| MBR     | 5         | 5.26%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 82        | 86.32%  |
| Yes       | 13        | 13.68%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 67        | 69.79%  |
| Yes       | 29        | 30.21%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 22        | 23.16%  |
| Dell                   | 13        | 13.68%  |
| ASUSTek Computer       | 13        | 13.68%  |
| Hewlett-Packard        | 12        | 12.63%  |
| TUXEDO                 | 10        | 10.53%  |
| Apple                  | 5         | 5.26%   |
| Toshiba                | 3         | 3.16%   |
| MSI                    | 3         | 3.16%   |
| Google                 | 2         | 2.11%   |
| Acer                   | 2         | 2.11%   |
| Timi                   | 1         | 1.05%   |
| Razer                  | 1         | 1.05%   |
| HUAWEI                 | 1         | 1.05%   |
| Digibras               | 1         | 1.05%   |
| COM1                   | 1         | 1.05%   |
| Chuwi                  | 1         | 1.05%   |
| BANGHO                 | 1         | 1.05%   |
| AXIOO                  | 1         | 1.05%   |
| Avell High Performance | 1         | 1.05%   |
| Alurin                 | 1         | 1.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                 | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| TUXEDO Pulse 15 Gen1                                 | 2         | 2.11%   |
| Lenovo G50-45 80E3                                   | 2         | 2.11%   |
| HP EliteBook 840 G3                                  | 2         | 2.11%   |
| TUXEDO Pulse 14 Gen1                                 | 1         | 1.05%   |
| TUXEDO Polaris Intel Gen3 (TGL)                      | 1         | 1.05%   |
| TUXEDO InfinityBook S 15 Gen6                        | 1         | 1.05%   |
| TUXEDO InfinityBook Pro 14 v4                        | 1         | 1.05%   |
| TUXEDO Book XUX7 Gen11                               | 1         | 1.05%   |
| TUXEDO Book XP1511                                   | 1         | 1.05%   |
| TUXEDO Book BA1510                                   | 1         | 1.05%   |
| TUXEDO Aura 15 Gen1                                  | 1         | 1.05%   |
| Toshiba Satellite C855D-11X                          | 1         | 1.05%   |
| Toshiba Satellite A505                               | 1         | 1.05%   |
| Toshiba Satellite A300                               | 1         | 1.05%   |
| Timi TM1604                                          | 1         | 1.05%   |
| Razer Blade 15 Advanced Model (Mid 2021) - RZ09-0409 | 1         | 1.05%   |
| MSI Modern 15 A10M                                   | 1         | 1.05%   |
| MSI GL62 6QF                                         | 1         | 1.05%   |
| MSI Alpha 15 B5EEK                                   | 1         | 1.05%   |
| Lenovo V15 G2 ALC 82KD                               | 1         | 1.05%   |
| Lenovo ThinkPad X260 20F5S0V500                      | 1         | 1.05%   |
| Lenovo ThinkPad X220 4291G75                         | 1         | 1.05%   |
| Lenovo ThinkPad X1 Carbon 5th 20HR002SIV             | 1         | 1.05%   |
| Lenovo ThinkPad T500 2242CTO                         | 1         | 1.05%   |
| Lenovo ThinkPad T480s 20L8SF1X00                     | 1         | 1.05%   |
| Lenovo ThinkPad T480 20L6SDR21A                      | 1         | 1.05%   |
| Lenovo ThinkPad T440 20B7S0F100                      | 1         | 1.05%   |
| Lenovo ThinkPad T14 Gen 3 21AHCTO1WW                 | 1         | 1.05%   |
| Lenovo ThinkPad T14 Gen 2i 20W000Q4GE                | 1         | 1.05%   |
| Lenovo ThinkPad E15 20RD003KHV                       | 1         | 1.05%   |
| Lenovo Legion Y530-15ICH 81FV                        | 1         | 1.05%   |
| Lenovo IdeaPad Z500 20202                            | 1         | 1.05%   |
| Lenovo IdeaPad S145-14IWL 81MU                       | 1         | 1.05%   |
| Lenovo IdeaPad C340-14API 81N6                       | 1         | 1.05%   |
| Lenovo IdeaPad 520-15IKB 81BF                        | 1         | 1.05%   |
| Lenovo IdeaPad 5 15ARE05 81YQ                        | 1         | 1.05%   |
| Lenovo IdeaPad 330-15IKB 81FE                        | 1         | 1.05%   |
| Lenovo IdeaPad 110-15ISK 80UD                        | 1         | 1.05%   |
| Lenovo G500 20236                                    | 1         | 1.05%   |
| HUAWEI HKD-WXX                                       | 1         | 1.05%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 10        | 10.53%  |
| Lenovo IdeaPad      | 7         | 7.37%   |
| Dell Latitude       | 5         | 5.26%   |
| HP EliteBook        | 4         | 4.21%   |
| Dell Inspiron       | 4         | 4.21%   |
| TUXEDO Pulse        | 3         | 3.16%   |
| TUXEDO Book         | 3         | 3.16%   |
| Toshiba Satellite   | 3         | 3.16%   |
| HP ProBook          | 3         | 3.16%   |
| ASUS VivoBook       | 3         | 3.16%   |
| TUXEDO InfinityBook | 2         | 2.11%   |
| Lenovo G50-45       | 2         | 2.11%   |
| HP Pavilion         | 2         | 2.11%   |
| Dell XPS            | 2         | 2.11%   |
| ASUS ZenBook        | 2         | 2.11%   |
| Apple MacBookPro8   | 2         | 2.11%   |
| Acer Aspire         | 2         | 2.11%   |
| TUXEDO Polaris      | 1         | 1.05%   |
| TUXEDO Aura         | 1         | 1.05%   |
| Timi TM1604         | 1         | 1.05%   |
| Razer Blade         | 1         | 1.05%   |
| MSI Modern          | 1         | 1.05%   |
| MSI GL62            | 1         | 1.05%   |
| MSI Alpha           | 1         | 1.05%   |
| Lenovo V15          | 1         | 1.05%   |
| Lenovo Legion       | 1         | 1.05%   |
| Lenovo G500         | 1         | 1.05%   |
| HUAWEI HKD-WXX      | 1         | 1.05%   |
| HP ENVY             | 1         | 1.05%   |
| HP ElitePad         | 1         | 1.05%   |
| HP Bloog            | 1         | 1.05%   |
| Google Rabbid       | 1         | 1.05%   |
| Google Boten        | 1         | 1.05%   |
| Digibras NH4CU03    | 1         | 1.05%   |
| Dell Vostro         | 1         | 1.05%   |
| Dell Precision      | 1         | 1.05%   |
| COM1 NBINF-X5-9G5   | 1         | 1.05%   |
| Chuwi HeroBook      | 1         | 1.05%   |
| BANGHO BES          | 1         | 1.05%   |
| AXIOO Slimbook      | 1         | 1.05%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 17        | 17.89%  |
| 2020 | 15        | 15.79%  |
| 2016 | 9         | 9.47%   |
| 2014 | 8         | 8.42%   |
| 2019 | 6         | 6.32%   |
| 2018 | 6         | 6.32%   |
| 2017 | 5         | 5.26%   |
| 2015 | 5         | 5.26%   |
| 2022 | 4         | 4.21%   |
| 2013 | 4         | 4.21%   |
| 2012 | 4         | 4.21%   |
| 2011 | 4         | 4.21%   |
| 2009 | 3         | 3.16%   |
| 2010 | 2         | 2.11%   |
| 2008 | 2         | 2.11%   |
| 2023 | 1         | 1.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 95        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 87        | 91.58%  |
| Enabled  | 8         | 8.42%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 92        | 96.84%  |
| Yes  | 3         | 3.16%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 32        | 33.33%  |
| 16.01-24.0  | 24        | 25%     |
| 3.01-4.0    | 13        | 13.54%  |
| 8.01-16.0   | 13        | 13.54%  |
| 32.01-64.0  | 9         | 9.38%   |
| 64.01-256.0 | 4         | 4.17%   |
| 1.01-2.0    | 1         | 1.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 35        | 33.98%  |
| 1.01-2.0   | 25        | 24.27%  |
| 4.01-8.0   | 17        | 16.5%   |
| 3.01-4.0   | 14        | 13.59%  |
| 8.01-16.0  | 8         | 7.77%   |
| 24.01-32.0 | 2         | 1.94%   |
| 16.01-24.0 | 2         | 1.94%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 74        | 75.51%  |
| 2      | 22        | 22.45%  |
| 3      | 2         | 2.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 77        | 81.05%  |
| Yes       | 18        | 18.95%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 77.08%  |
| No        | 22        | 22.92%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 93        | 97.89%  |
| No        | 2         | 2.11%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 80        | 84.21%  |
| No        | 15        | 15.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| Germany            | 15        | 15.79%  |
| USA                | 13        | 13.68%  |
| France             | 12        | 12.63%  |
| Brazil             | 5         | 5.26%   |
| Canada             | 4         | 4.21%   |
| UK                 | 3         | 3.16%   |
| Poland             | 3         | 3.16%   |
| Italy              | 3         | 3.16%   |
| Spain              | 2         | 2.11%   |
| Peru               | 2         | 2.11%   |
| Ireland            | 2         | 2.11%   |
| Indonesia          | 2         | 2.11%   |
| Hungary            | 2         | 2.11%   |
| Belgium            | 2         | 2.11%   |
| Austria            | 2         | 2.11%   |
| Sweden             | 1         | 1.05%   |
| Slovenia           | 1         | 1.05%   |
| Singapore          | 1         | 1.05%   |
| Russia             | 1         | 1.05%   |
| Romania            | 1         | 1.05%   |
| Mexico             | 1         | 1.05%   |
| Malta              | 1         | 1.05%   |
| Japan              | 1         | 1.05%   |
| Israel             | 1         | 1.05%   |
| Greece             | 1         | 1.05%   |
| Ghana              | 1         | 1.05%   |
| Ecuador            | 1         | 1.05%   |
| Dominican Republic | 1         | 1.05%   |
| Denmark            | 1         | 1.05%   |
| Czechia            | 1         | 1.05%   |
| Cuba               | 1         | 1.05%   |
| Chile              | 1         | 1.05%   |
| Cabo Verde         | 1         | 1.05%   |
| Bulgaria           | 1         | 1.05%   |
| Belarus            | 1         | 1.05%   |
| Australia          | 1         | 1.05%   |
| Argentina          | 1         | 1.05%   |
| Algeria            | 1         | 1.05%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Berlin                | 3         | 3.06%   |
| Warsaw                | 2         | 2.04%   |
| Vienna                | 2         | 2.04%   |
| Victoria              | 2         | 2.04%   |
| Nuremberg             | 2         | 2.04%   |
| Laval                 | 2         | 2.04%   |
| Frankfurt am Main     | 2         | 2.04%   |
| Dublin                | 2         | 2.04%   |
| Budapest              | 2         | 2.04%   |
| Yogyakarta            | 1         | 1.02%   |
| Wertheim am Main      | 1         | 1.02%   |
| Weisswasser           | 1         | 1.02%   |
| Weilheim              | 1         | 1.02%   |
| Washington            | 1         | 1.02%   |
| Torun                 | 1         | 1.02%   |
| Targu Frumos          | 1         | 1.02%   |
| Tarakan               | 1         | 1.02%   |
| Sunnyvale             | 1         | 1.02%   |
| St Petersburg         | 1         | 1.02%   |
| Sofia                 | 1         | 1.02%   |
| Singapore             | 1         | 1.02%   |
| Siegen                | 1         | 1.02%   |
| Shirakuni             | 1         | 1.02%   |
| Sétif                | 1         | 1.02%   |
| Seelze                | 1         | 1.02%   |
| Sao Paulo             | 1         | 1.02%   |
| Sao Bernardo do Campo | 1         | 1.02%   |
| Santo Domingo Este    | 1         | 1.02%   |
| Santiago              | 1         | 1.02%   |
| Saint-Gilles          | 1         | 1.02%   |
| Rishon LeTsiyyon      | 1         | 1.02%   |
| Renton                | 1         | 1.02%   |
| Recife                | 1         | 1.02%   |
| Queens                | 1         | 1.02%   |
| Quedlinburg           | 1         | 1.02%   |
| Puteaux               | 1         | 1.02%   |
| Puebla City           | 1         | 1.02%   |
| Praia                 | 1         | 1.02%   |
| Postojna              | 1         | 1.02%   |
| Pau                   | 1         | 1.02%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 28        | 35     | 24.14%  |
| Unknown                        | 11        | 11     | 9.48%   |
| Toshiba                        | 9         | 12     | 7.76%   |
| WDC                            | 7         | 8      | 6.03%   |
| Micron Technology              | 7         | 7      | 6.03%   |
| Crucial                        | 7         | 12     | 6.03%   |
| SK hynix                       | 6         | 6      | 5.17%   |
| Seagate                        | 6         | 6      | 5.17%   |
| Kingston                       | 4         | 4      | 3.45%   |
| Intel                          | 3         | 3      | 2.59%   |
| SPCC                           | 2         | 3      | 1.72%   |
| SanDisk                        | 2         | 2      | 1.72%   |
| JMicron Technology             | 2         | 2      | 1.72%   |
| China                          | 2         | 3      | 1.72%   |
| Apple                          | 2         | 2      | 1.72%   |
| A-DATA Technology              | 2         | 3      | 1.72%   |
| YMTC                           | 1         | 1      | 0.86%   |
| VISIPRO                        | 1         | 1      | 0.86%   |
| Union Memory                   | 1         | 1      | 0.86%   |
| TO Exter                       | 1         | 1      | 0.86%   |
| Solid State Storage Technology | 1         | 1      | 0.86%   |
| Silicon Motion                 | 1         | 1      | 0.86%   |
| Realtek Semiconductor          | 1         | 1      | 0.86%   |
| Phison Electronics             | 1         | 1      | 0.86%   |
| OWC                            | 1         | 1      | 0.86%   |
| Netac                          | 1         | 1      | 0.86%   |
| KIOXIA                         | 1         | 1      | 0.86%   |
| HGST                           | 1         | 1      | 0.86%   |
| Hewlett-Packard                | 1         | 1      | 0.86%   |
| Gigabyte Technology            | 1         | 1      | 0.86%   |
| Corsair                        | 1         | 2      | 0.86%   |
| Unknown                        | 1         | 1      | 0.86%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 4         | 3.39%   |
| WDC WD10JPVX-22JC3T0 1TB                          | 2         | 1.69%   |
| Unknown SD64G  64GB                               | 2         | 1.69%   |
| Unknown MMC Card  64GB                            | 2         | 1.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 2         | 1.69%   |
| Samsung SSD 980 PRO 2TB                           | 2         | 1.69%   |
| Samsung SSD 980 500GB                             | 2         | 1.69%   |
| Samsung SSD 860 EVO M.2 500GB                     | 2         | 1.69%   |
| Samsung SSD 860 EVO 500GB                         | 2         | 1.69%   |
| Samsung MZVLQ512HALU-000H1 512GB                  | 2         | 1.69%   |
| Crucial CT240BX500SSD1 240GB                      | 2         | 1.69%   |
| YMTC PC005 1TB                                    | 1         | 0.85%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 1         | 0.85%   |
| WDC WD10JPVX-75JC3T0 1TB                          | 1         | 0.85%   |
| WDC PC SN730 NVMe 256GB                           | 1         | 0.85%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB              | 1         | 0.85%   |
| WDC PC SN530 SDBPTPZ-512G-1002 512GB              | 1         | 0.85%   |
| WDC PC SN520 SDAPNUW-512G-1002 512GB              | 1         | 0.85%   |
| VISIPRO SSD 256GB                                 | 1         | 0.85%   |
| Unknown SL128  128GB                              | 1         | 0.85%   |
| Unknown SA16G  16GB                               | 1         | 0.85%   |
| Unknown NCard  4GB                                | 1         | 0.85%   |
| Unknown MMC128  128GB                             | 1         | 0.85%   |
| Unknown MMC Card  968MB                           | 1         | 0.85%   |
| Unknown MMC Card  32GB                            | 1         | 0.85%   |
| Unknown MMC Card  128GB                           | 1         | 0.85%   |
| Union Memory RTOTJ128VGD2EYX 128GB SSD            | 1         | 0.85%   |
| Toshiba XG6 NVMe SSD Controller 256GB             | 1         | 0.85%   |
| Toshiba TR150 480GB SSD                           | 1         | 0.85%   |
| Toshiba MQ04ABF100 1TB                            | 1         | 0.85%   |
| Toshiba MQ01ABD100 1TB                            | 1         | 0.85%   |
| Toshiba MQ01ABD075 752GB                          | 1         | 0.85%   |
| Toshiba MQ01ABD050 500GB                          | 1         | 0.85%   |
| Toshiba KXG50ZNV512G NVMe 512GB                   | 1         | 0.85%   |
| Toshiba KBG40ZNT256G MEMORY 256GB                 | 1         | 0.85%   |
| Toshiba KBG30ZMT256G 256GB                        | 1         | 0.85%   |
| TO Exter nal USB 3.0 512GB                        | 1         | 0.85%   |
| SPCC Solid State Disk 120GB                       | 1         | 0.85%   |
| SPCC Solid State Disk 1024GB                      | 1         | 0.85%   |
| Solid State Storage NVMe CA6-8D1024 1024GB        | 1         | 0.85%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 35.29%  |
| Toshiba             | 4         | 4      | 23.53%  |
| WDC                 | 3         | 3      | 17.65%  |
| TO Exter            | 1         | 1      | 5.88%   |
| Samsung Electronics | 1         | 1      | 5.88%   |
| JMicron Technology  | 1         | 1      | 5.88%   |
| HGST                | 1         | 1      | 5.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 14     | 21.95%  |
| Crucial             | 7         | 12     | 17.07%  |
| Micron Technology   | 4         | 4      | 9.76%   |
| SPCC                | 2         | 3      | 4.88%   |
| SanDisk             | 2         | 2      | 4.88%   |
| Kingston            | 2         | 2      | 4.88%   |
| China               | 2         | 3      | 4.88%   |
| Apple               | 2         | 2      | 4.88%   |
| WDC                 | 1         | 1      | 2.44%   |
| VISIPRO             | 1         | 1      | 2.44%   |
| Union Memory        | 1         | 1      | 2.44%   |
| Toshiba             | 1         | 1      | 2.44%   |
| SK hynix            | 1         | 1      | 2.44%   |
| OWC                 | 1         | 1      | 2.44%   |
| Netac               | 1         | 1      | 2.44%   |
| Intel               | 1         | 1      | 2.44%   |
| Hewlett-Packard     | 1         | 1      | 2.44%   |
| Gigabyte Technology | 1         | 1      | 2.44%   |
| Corsair             | 1         | 2      | 2.44%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 43        | 50     | 39.09%  |
| SSD     | 38        | 54     | 34.55%  |
| HDD     | 16        | 17     | 14.55%  |
| MMC     | 12        | 14     | 10.91%  |
| Unknown | 1         | 1      | 0.91%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 49        | 68     | 45.79%  |
| NVMe | 43        | 50     | 40.19%  |
| MMC  | 12        | 14     | 11.21%  |
| SAS  | 3         | 4      | 2.8%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 37        | 47     | 64.91%  |
| 0.51-1.0   | 15        | 18     | 26.32%  |
| 1.01-2.0   | 5         | 6      | 8.77%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 31        | 32.63%  |
| 101-250        | 31        | 32.63%  |
| 501-1000       | 13        | 13.68%  |
| 51-100         | 7         | 7.37%   |
| 21-50          | 5         | 5.26%   |
| 1001-2000      | 4         | 4.21%   |
| 1-20           | 2         | 2.11%   |
| More than 3000 | 1         | 1.05%   |
| 2001-3000      | 1         | 1.05%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 27        | 27.55%  |
| 21-50     | 23        | 23.47%  |
| 101-250   | 21        | 21.43%  |
| 51-100    | 12        | 12.24%  |
| 251-500   | 8         | 8.16%   |
| 501-1000  | 4         | 4.08%   |
| 1001-2000 | 3         | 3.06%   |

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
| Detected | 55        | 77     | 55%     |
| Works    | 43        | 57     | 43%     |
| Malfunc  | 2         | 2      | 2%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 59        | 51.75%  |
| Samsung Electronics            | 18        | 15.79%  |
| AMD                            | 11        | 9.65%   |
| SanDisk                        | 4         | 3.51%   |
| Toshiba America Info Systems   | 3         | 2.63%   |
| SK hynix                       | 3         | 2.63%   |
| Micron Technology              | 3         | 2.63%   |
| KIOXIA                         | 2         | 1.75%   |
| Kingston Technology Company    | 2         | 1.75%   |
| ADATA Technology               | 2         | 1.75%   |
| Yangtze Memory Technologies    | 1         | 0.88%   |
| Solid State Storage Technology | 1         | 0.88%   |
| Silicon Motion                 | 1         | 0.88%   |
| Realtek Semiconductor          | 1         | 0.88%   |
| Phison Electronics             | 1         | 0.88%   |
| Nvidia                         | 1         | 0.88%   |
| Marvell Technology Group       | 1         | 0.88%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 11        | 9.24%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 11        | 9.24%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                  | 6         | 5.04%   |
| Intel Volume Management Device NVMe RAID Controller                          | 6         | 5.04%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 5         | 4.2%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 5         | 4.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 5         | 4.2%    |
| Intel Comet Lake SATA AHCI Controller                                        | 4         | 3.36%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 4         | 3.36%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 4         | 3.36%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 3         | 2.52%   |
| Intel Tiger Lake-LP SATA Controller                                          | 3         | 2.52%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                         | 2         | 1.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 2         | 1.68%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                   | 2         | 1.68%   |
| Intel Tiger Lake SATA AHCI Controller                                        | 2         | 1.68%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 2         | 1.68%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 2         | 1.68%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 2         | 1.68%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 2         | 1.68%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 2         | 1.68%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 2         | 1.68%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 2         | 1.68%   |
| Yangtze Memory PC005 NVMe SSD                                                | 1         | 0.84%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                         | 1         | 0.84%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                         | 1         | 0.84%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)          | 1         | 0.84%   |
| Solid State Storage CA6-8D512 NVMe SSD M.2                                   | 1         | 0.84%   |
| SK hynix PC601 NVMe Solid State Drive                                        | 1         | 0.84%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers            | 1         | 0.84%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                        | 1         | 0.84%   |
| SanDisk IX SN530 NVMe SSD (DRAM-less)                                        | 1         | 0.84%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD         | 1         | 0.84%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                  | 1         | 0.84%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                            | 1         | 0.84%   |
| Phison E8 PCIe3 x2 NVMe Controller                                           | 1         | 0.84%   |
| Nvidia MCP79 AHCI Controller                                                 | 1         | 0.84%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                  | 1         | 0.84%   |
| Micron 2400 NVMe SSD (DRAM-less)                                             | 1         | 0.84%   |
| Micron 2300 NVMe SSD [Santana]                                               | 1         | 0.84%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 65        | 55.56%  |
| NVMe | 43        | 36.75%  |
| RAID | 8         | 6.84%   |
| IDE  | 1         | 0.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 79        | 83.16%  |
| AMD    | 16        | 16.84%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 4.21%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 4         | 4.21%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 3.16%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 3.16%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 2         | 2.11%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 2.11%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 2.11%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 2.11%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 2.11%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 2.11%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 2.11%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 2         | 2.11%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 2.11%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 2.11%   |
| Intel Atom CPU Z3795 @ 1.60GHz                | 2         | 2.11%   |
| Intel 11th Gen Core i7-11850H @ 2.50GHz       | 2         | 2.11%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 2.11%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 2.11%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 2.11%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 2.11%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 2.11%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics   | 2         | 2.11%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 1.05%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 1.05%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 1.05%   |
| Intel Core i9-10900K CPU @ 3.70GHz            | 1         | 1.05%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 1.05%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.05%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 1.05%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.05%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 1.05%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1         | 1.05%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 1.05%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 1.05%   |
| Intel Core i7-2760QM CPU @ 2.40GHz            | 1         | 1.05%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.05%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 1.05%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1.05%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.05%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.05%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 23        | 24.21%  |
| Intel Core i7           | 18        | 18.95%  |
| Other                   | 15        | 15.79%  |
| AMD Ryzen 7             | 8         | 8.42%   |
| Intel Core i3           | 6         | 6.32%   |
| Intel Celeron           | 6         | 6.32%   |
| AMD Ryzen 5             | 4         | 4.21%   |
| Intel Atom              | 3         | 3.16%   |
| Intel Pentium Silver    | 2         | 2.11%   |
| Intel Pentium           | 2         | 2.11%   |
| Intel Core 2 Duo        | 2         | 2.11%   |
| AMD A8                  | 2         | 2.11%   |
| Intel Pentium Dual-Core | 1         | 1.05%   |
| Intel Core i9           | 1         | 1.05%   |
| AMD Ryzen 3             | 1         | 1.05%   |
| AMD A6                  | 1         | 1.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 38        | 40%     |
| 2      | 36        | 37.89%  |
| 8      | 13        | 13.68%  |
| 6      | 5         | 5.26%   |
| 10     | 2         | 2.11%   |
| 1      | 1         | 1.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 95        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 73        | 76.84%  |
| 1      | 22        | 23.16%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 95        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 56        | 57.14%  |
| 0x806c1    | 4         | 4.08%   |
| 0x08600106 | 4         | 4.08%   |
| 0x806ec    | 3         | 3.06%   |
| 0x706a8    | 3         | 3.06%   |
| 0x206a7    | 3         | 3.06%   |
| 0x806ea    | 2         | 2.04%   |
| 0x806d1    | 2         | 2.04%   |
| 0x406e3    | 2         | 2.04%   |
| 0x20655    | 2         | 2.04%   |
| 0x08108102 | 2         | 2.04%   |
| 0x906ea    | 1         | 1.02%   |
| 0x806eb    | 1         | 1.02%   |
| 0x806e9    | 1         | 1.02%   |
| 0x506e3    | 1         | 1.02%   |
| 0x506c9    | 1         | 1.02%   |
| 0x40651    | 1         | 1.02%   |
| 0x306d4    | 1         | 1.02%   |
| 0x306c3    | 1         | 1.02%   |
| 0x30678    | 1         | 1.02%   |
| 0x106e5    | 1         | 1.02%   |
| 0x0a50000c | 1         | 1.02%   |
| 0x08608103 | 1         | 1.02%   |
| 0x08600103 | 1         | 1.02%   |
| 0x07030105 | 1         | 1.02%   |
| 0x07030104 | 1         | 1.02%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 18        | 18.95%  |
| Skylake       | 10        | 10.53%  |
| TigerLake     | 9         | 9.47%   |
| Zen 2         | 7         | 7.37%   |
| Unknown       | 7         | 7.37%   |
| SandyBridge   | 5         | 5.26%   |
| Goldmont plus | 5         | 5.26%   |
| Silvermont    | 4         | 4.21%   |
| IvyBridge     | 4         | 4.21%   |
| Haswell       | 4         | 4.21%   |
| Penryn        | 3         | 3.16%   |
| IceLake       | 3         | 3.16%   |
| Broadwell     | 3         | 3.16%   |
| Zen+          | 2         | 2.11%   |
| Zen 3         | 2         | 2.11%   |
| Westmere      | 2         | 2.11%   |
| Puma          | 2         | 2.11%   |
| CometLake     | 2         | 2.11%   |
| Piledriver    | 1         | 1.05%   |
| Nehalem       | 1         | 1.05%   |
| Goldmont      | 1         | 1.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 76        | 65.52%  |
| Nvidia | 21        | 18.1%   |
| AMD    | 19        | 16.38%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 9         | 7.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 8         | 6.72%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]             | 7         | 5.88%   |
| Intel UHD Graphics 620                                                    | 6         | 5.04%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 5         | 4.2%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 4         | 3.36%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 4         | 3.36%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 4         | 3.36%   |
| Intel HD Graphics 620                                                     | 3         | 2.52%   |
| Intel HD Graphics 5500                                                    | 3         | 2.52%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 3         | 2.52%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 3         | 2.52%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 3         | 2.52%   |
| Nvidia GP108M [GeForce MX150]                                             | 2         | 1.68%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 2         | 1.68%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 2         | 1.68%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 1.68%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 2         | 1.68%   |
| Intel HD Graphics 530                                                     | 2         | 1.68%   |
| Intel GeminiLake [UHD Graphics 605]                                       | 2         | 1.68%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 1.68%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 2         | 1.68%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 2         | 1.68%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                       | 2         | 1.68%   |
| AMD Lucienne                                                              | 2         | 1.68%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 1.68%   |
| Nvidia TU117M [GeForce MX450]                                             | 1         | 0.84%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 0.84%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                   | 1         | 0.84%   |
| Nvidia TU104BM [GeForce RTX 2080 SUPER Mobile / Max-Q]                    | 1         | 0.84%   |
| Nvidia GT218M [GeForce 310M]                                              | 1         | 0.84%   |
| Nvidia GP108M [GeForce MX230]                                             | 1         | 0.84%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.84%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 0.84%   |
| Nvidia GM108M [GeForce 840M]                                              | 1         | 0.84%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 0.84%   |
| Nvidia GM107M [GeForce GTX 950M]                                          | 1         | 0.84%   |
| Nvidia GK208M [GeForce GT 740M]                                           | 1         | 0.84%   |
| Nvidia GK208BM [GeForce 920M]                                             | 1         | 0.84%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                        | 1         | 0.84%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 56        | 58.95%  |
| Intel + Nvidia | 16        | 16.84%  |
| 1 x AMD        | 11        | 11.58%  |
| 2 x AMD        | 3         | 3.16%   |
| 1 x Nvidia     | 3         | 3.16%   |
| Intel + AMD    | 3         | 3.16%   |
| AMD + Nvidia   | 2         | 2.11%   |
| Other          | 1         | 1.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 81        | 85.26%  |
| Proprietary | 12        | 12.63%  |
| Unknown     | 2         | 2.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 80        | 84.21%  |
| 0.01-0.5   | 5         | 5.26%   |
| 1.01-2.0   | 4         | 4.21%   |
| 0.51-1.0   | 3         | 3.16%   |
| 7.01-8.0   | 2         | 2.11%   |
| 3.01-4.0   | 1         | 1.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 23        | 20.54%  |
| Chimei Innolux          | 22        | 19.64%  |
| AU Optronics            | 13        | 11.61%  |
| Samsung Electronics     | 11        | 9.82%   |
| LG Display              | 9         | 8.04%   |
| Apple                   | 5         | 4.46%   |
| Sharp                   | 4         | 3.57%   |
| Goldstar                | 4         | 3.57%   |
| Philips                 | 2         | 1.79%   |
| PANDA                   | 2         | 1.79%   |
| Lenovo                  | 2         | 1.79%   |
| Unknown (AAA)           | 1         | 0.89%   |
| TMX                     | 1         | 0.89%   |
| Sony                    | 1         | 0.89%   |
| MStar                   | 1         | 0.89%   |
| LG Philips              | 1         | 0.89%   |
| KDC                     | 1         | 0.89%   |
| JDZ                     | 1         | 0.89%   |
| IBM                     | 1         | 0.89%   |
| HKC                     | 1         | 0.89%   |
| Hewlett-Packard         | 1         | 0.89%   |
| Daewoo                  | 1         | 0.89%   |
| Chi Mei Optoelectronics | 1         | 0.89%   |
| BenQ                    | 1         | 0.89%   |
| AOC                     | 1         | 0.89%   |
| Acer                    | 1         | 0.89%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch         | 2         | 1.79%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch        | 2         | 1.79%   |
| Unknown (AAA) LCDTV AAA3393 1360x768 890x500mm 40.2-inch                | 1         | 0.89%   |
| TMX TL142GDXP02-0 TMX1420 2520x1680 300x200mm 14.2-inch                 | 1         | 0.89%   |
| Sony TV SNYAB03 1920x1080                                               | 1         | 0.89%   |
| Sharp LQ156T1JW03 SHP1529 2560x1440 344x194mm 15.5-inch                 | 1         | 0.89%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                 | 1         | 0.89%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                 | 1         | 0.89%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch                 | 1         | 0.89%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch    | 1         | 0.89%   |
| Samsung Electronics LS24AG30x SAM7178 1920x1080 530x300mm 24.0-inch     | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch    | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch    | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch   | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SDC5844 1920x1080 344x194mm 15.5-inch   | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch   | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SDC414F 3456x2160 288x180mm 13.4-inch   | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1872x1053mm 84.6-inch | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch    | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 1209x680mm 54.6-inch  | 1         | 0.89%   |
| Philips PHL 276B1 PHL0947 2560x1440 597x336mm 27.0-inch                 | 1         | 0.89%   |
| Philips PHL 216V6 PHLC10D 1920x1080 419x262mm 19.5-inch                 | 1         | 0.89%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                 | 1         | 0.89%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                 | 1         | 0.89%   |
| MStar LCD TV MST9000 1360x768                                           | 1         | 0.89%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch           | 1         | 0.89%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch            | 1         | 0.89%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch            | 1         | 0.89%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch            | 1         | 0.89%   |
| LG Display LCD Monitor LGD0542 1920x1080 276x156mm 12.5-inch            | 1         | 0.89%   |
| LG Display LCD Monitor LGD04AF 1366x768 344x194mm 15.5-inch             | 1         | 0.89%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch             | 1         | 0.89%   |
| LG Display LCD Monitor LGD03D6 1366x768 345x194mm 15.6-inch             | 1         | 0.89%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch             | 1         | 0.89%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch             | 1         | 0.89%   |
| Lenovo T22v-20 LEN61FB 1920x1080 476x268mm 21.5-inch                    | 1         | 0.89%   |
| Lenovo LEN D27-20B LEN65F5 1920x1080 598x336mm 27.0-inch                | 1         | 0.89%   |
| KDC LCD Monitor KDC0830 1920x1080 344x193mm 15.5-inch                   | 1         | 0.89%   |
| JDZ LCD Monitor JDZ0203 1920x1080 309x174mm 14.0-inch                   | 1         | 0.89%   |
| IBM LCD Monitor IBM2887 1680x1050 331x207mm 15.4-inch                   | 1         | 0.89%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 47        | 47%     |
| 1366x768 (WXGA)    | 25        | 25%     |
| 1920x1200 (WUXGA)  | 4         | 4%      |
| 1280x800 (WXGA)    | 4         | 4%      |
| 3840x2160 (4K)     | 3         | 3%      |
| 2560x1440 (QHD)    | 3         | 3%      |
| 1600x900 (HD+)     | 3         | 3%      |
| 1680x1050 (WSXGA+) | 2         | 2%      |
| 1440x900 (WXGA+)   | 2         | 2%      |
| 3456x2160          | 1         | 1%      |
| 3440x1440          | 1         | 1%      |
| 2880x1800          | 1         | 1%      |
| 2560x1600          | 1         | 1%      |
| 2560x1080          | 1         | 1%      |
| 2520x1680          | 1         | 1%      |
| 1360x768           | 1         | 1%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 46        | 41.07%  |
| 13      | 21        | 18.75%  |
| 14      | 12        | 10.71%  |
| 17      | 5         | 4.46%   |
| 23      | 4         | 3.57%   |
| 27      | 3         | 2.68%   |
| 12      | 3         | 2.68%   |
| 11      | 3         | 2.68%   |
| 40      | 2         | 1.79%   |
| 34      | 2         | 1.79%   |
| 24      | 2         | 1.79%   |
| 21      | 2         | 1.79%   |
| 84      | 1         | 0.89%   |
| 72      | 1         | 0.89%   |
| 60      | 1         | 0.89%   |
| 31      | 1         | 0.89%   |
| 19      | 1         | 0.89%   |
| 10      | 1         | 0.89%   |
| Unknown | 1         | 0.89%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 68        | 60.71%  |
| 201-300     | 17        | 15.18%  |
| 501-600     | 7         | 6.25%   |
| 351-400     | 6         | 5.36%   |
| 401-500     | 4         | 3.57%   |
| 801-900     | 2         | 1.79%   |
| 701-800     | 2         | 1.79%   |
| 601-700     | 2         | 1.79%   |
| 1501-2000   | 2         | 1.79%   |
| 1001-1500   | 1         | 0.89%   |
| Unknown     | 1         | 0.89%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 79        | 80.61%  |
| 16/10 | 15        | 15.31%  |
| 3/2   | 2         | 2.04%   |
| 21/9  | 2         | 2.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 46        | 41.07%  |
| 81-90          | 27        | 24.11%  |
| 201-250        | 7         | 6.25%   |
| 71-80          | 5         | 4.46%   |
| 121-130        | 4         | 3.57%   |
| More than 1000 | 3         | 2.68%   |
| 61-70          | 3         | 2.68%   |
| 51-60          | 3         | 2.68%   |
| 351-500        | 3         | 2.68%   |
| 301-350        | 3         | 2.68%   |
| 151-200        | 2         | 1.79%   |
| 501-1000       | 2         | 1.79%   |
| 41-50          | 1         | 0.89%   |
| 131-140        | 1         | 0.89%   |
| 91-100         | 1         | 0.89%   |
| Unknown        | 1         | 0.89%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 51        | 45.54%  |
| 101-120       | 28        | 25%     |
| 161-240       | 12        | 10.71%  |
| 51-100        | 12        | 10.71%  |
| More than 240 | 4         | 3.57%   |
| 1-50          | 4         | 3.57%   |
| Unknown       | 1         | 0.89%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 74        | 77.08%  |
| 2     | 20        | 20.83%  |
| 0     | 2         | 2.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 52        | 35.14%  |
| Intel                 | 52        | 35.14%  |
| Qualcomm Atheros      | 15        | 10.14%  |
| Broadcom              | 9         | 6.08%   |
| MediaTek              | 5         | 3.38%   |
| ASIX Electronics      | 3         | 2.03%   |
| Hewlett-Packard       | 2         | 1.35%   |
| Broadcom Limited      | 2         | 1.35%   |
| Xiaomi                | 1         | 0.68%   |
| TP-Link               | 1         | 0.68%   |
| Sierra Wireless       | 1         | 0.68%   |
| Nvidia                | 1         | 0.68%   |
| Lenovo                | 1         | 0.68%   |
| JMicron Technology    | 1         | 0.68%   |
| Huawei Technologies   | 1         | 0.68%   |
| Fibocom               | 1         | 0.68%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 28        | 15.64%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 11        | 6.15%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 4.47%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 4.47%   |
| Intel Wireless 8265 / 8275                                              | 7         | 3.91%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 6         | 3.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 2.79%   |
| Intel Wireless 8260                                                     | 4         | 2.23%   |
| Intel Ethernet Connection (4) I219-LM                                   | 4         | 2.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 2.23%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 2.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 1.68%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 1.68%   |
| Intel Ethernet Connection I219-V                                        | 3         | 1.68%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 3         | 1.68%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 3         | 1.68%   |
| ASIX AX88179 Gigabit Ethernet                                           | 3         | 1.68%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.12%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 2         | 1.12%   |
| Realtek 802.11n WLAN Adapter                                            | 2         | 1.12%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.12%   |
| Intel Wireless 7265                                                     | 2         | 1.12%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 2         | 1.12%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 1.12%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.12%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 1.12%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.56%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1         | 0.56%   |
| Sierra Wireless EM7455                                                  | 1         | 0.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.56%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.56%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.56%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.56%   |
| Realtek RTL8125 2.5GbE Controller                                       | 1         | 0.56%   |
| Realtek Killer E3000 2.5GbE Controller                                  | 1         | 0.56%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 51        | 52.04%  |
| Realtek Semiconductor | 15        | 15.31%  |
| Qualcomm Atheros      | 13        | 13.27%  |
| Broadcom              | 9         | 9.18%   |
| MediaTek              | 5         | 5.1%    |
| TP-Link               | 1         | 1.02%   |
| Sierra Wireless       | 1         | 1.02%   |
| Hewlett-Packard       | 1         | 1.02%   |
| Fibocom               | 1         | 1.02%   |
| Broadcom Limited      | 1         | 1.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                     | 8         | 8.16%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 8.16%   |
| Intel Wireless 8265 / 8275                                              | 7         | 7.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 5.1%    |
| Intel Wireless 8260                                                     | 4         | 4.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 4.08%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 4.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 3.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 3.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 3.06%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 3.06%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 3         | 3.06%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.04%   |
| Realtek 802.11n WLAN Adapter                                            | 2         | 2.04%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 2.04%   |
| Intel Wireless 7265                                                     | 2         | 2.04%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 2         | 2.04%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 2.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 2.04%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 2.04%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1         | 1.02%   |
| Sierra Wireless EM7455                                                  | 1         | 1.02%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 1.02%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.02%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 1.02%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.02%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.02%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 1.02%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 1.02%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 1.02%   |
| MediaTek 802.11 n WLAN                                                  | 1         | 1.02%   |
| Intel Wireless 7260                                                     | 1         | 1.02%   |
| Intel Wireless 3165                                                     | 1         | 1.02%   |
| Intel Wireless 3160                                                     | 1         | 1.02%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 1.02%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 1.02%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 1.02%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 1.02%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 1.02%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 47        | 60.26%  |
| Intel                 | 17        | 21.79%  |
| Broadcom              | 3         | 3.85%   |
| ASIX Electronics      | 3         | 3.85%   |
| Qualcomm Atheros      | 2         | 2.56%   |
| Xiaomi                | 1         | 1.28%   |
| Nvidia                | 1         | 1.28%   |
| Lenovo                | 1         | 1.28%   |
| JMicron Technology    | 1         | 1.28%   |
| Hewlett-Packard       | 1         | 1.28%   |
| Broadcom Limited      | 1         | 1.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 28        | 35%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 11        | 13.75%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 6         | 7.5%    |
| Intel Ethernet Connection (4) I219-LM                                  | 4         | 5%      |
| Intel Ethernet Connection I219-V                                       | 3         | 3.75%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 3.75%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 3.75%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 2.5%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 1.25%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 1.25%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 1         | 1.25%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 1.25%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 1.25%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 1.25%   |
| Lenovo ThinkPad Lan                                                    | 1         | 1.25%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 1.25%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 1.25%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 1.25%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 1.25%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 1.25%   |
| Intel Ethernet Connection (16) I219-LM                                 | 1         | 1.25%   |
| Intel Ethernet Connection (14) I219-LM                                 | 1         | 1.25%   |
| Intel Ethernet Connection (10) I219-V                                  | 1         | 1.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 1         | 1.25%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 1.25%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 1.25%   |
| HP lt4120 Snapdragon X5 LTE                                            | 1         | 1.25%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe               | 1         | 1.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 93        | 55.36%  |
| Ethernet | 74        | 44.05%  |
| Modem    | 1         | 0.6%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 79        | 81.44%  |
| Ethernet | 18        | 18.56%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 66        | 69.47%  |
| 1     | 24        | 25.26%  |
| 0     | 5         | 5.26%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 63        | 64.29%  |
| Yes  | 35        | 35.71%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 44        | 55%     |
| Realtek Semiconductor           | 7         | 8.75%   |
| Qualcomm Atheros Communications | 7         | 8.75%   |
| Broadcom                        | 6         | 7.5%    |
| IMC Networks                    | 5         | 6.25%   |
| Apple                           | 5         | 6.25%   |
| Dell                            | 2         | 2.5%    |
| Smart Modular Technologies      | 1         | 1.25%   |
| Realtek                         | 1         | 1.25%   |
| MediaTek                        | 1         | 1.25%   |
| Foxconn International           | 1         | 1.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 15        | 18.75%  |
| Intel AX201 Bluetooth                              | 14        | 17.5%   |
| Intel AX200 Bluetooth                              | 8         | 10%     |
| Realtek Bluetooth Radio                            | 6         | 7.5%    |
| Qualcomm Atheros  Bluetooth Device                 | 5         | 6.25%   |
| IMC Networks Wireless_Device                       | 3         | 3.75%   |
| Apple Bluetooth Host Controller                    | 3         | 3.75%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 2         | 2.5%    |
| Intel AX210 Bluetooth                              | 2         | 2.5%    |
| Dell DW375 Bluetooth Module                        | 2         | 2.5%    |
| Apple Bluetooth USB Host Controller                | 2         | 2.5%    |
| Smart Modular Bluetooth Device                     | 1         | 1.25%   |
| Realtek RTL8723B Bluetooth                         | 1         | 1.25%   |
| Realtek Bluetooth Radio                            | 1         | 1.25%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0             | 1         | 1.25%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0              | 1         | 1.25%   |
| MediaTek Wireless_Device                           | 1         | 1.25%   |
| Intel Wireless-AC 3168 Bluetooth                   | 1         | 1.25%   |
| Intel Centrino Bluetooth Wireless Transceiver      | 1         | 1.25%   |
| Intel Bluetooth Device                             | 1         | 1.25%   |
| IMC Networks Bluetooth Radio                       | 1         | 1.25%   |
| IMC Networks Atheros AR3012 Bluetooth              | 1         | 1.25%   |
| Foxconn International BCM43142A0 Bluetooth module  | 1         | 1.25%   |
| Broadcom BCM43142A0 Bluetooth Device               | 1         | 1.25%   |
| Broadcom BCM43142A0 Bluetooth 4.0                  | 1         | 1.25%   |
| Broadcom BCM43142 Bluetooth 4.0                    | 1         | 1.25%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR               | 1         | 1.25%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 1.25%   |
| Broadcom BCM2045B (BDC-2.1)                        | 1         | 1.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 75        | 69.44%  |
| AMD                    | 17        | 15.74%  |
| Nvidia                 | 10        | 9.26%   |
| Plantronics            | 1         | 0.93%   |
| Logitech               | 1         | 0.93%   |
| LINE TECH INDUSTRIAL   | 1         | 0.93%   |
| DSEA A/S               | 1         | 0.93%   |
| Arturia                | 1         | 0.93%   |
| AKAI Professional M.I. | 1         | 0.93%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 17        | 12.88%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 13        | 9.85%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 11        | 8.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 9         | 6.82%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 3.79%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 3.79%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 3.03%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 3.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 3.03%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 2.27%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 2.27%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 2.27%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 2.27%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 2.27%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 2.27%   |
| AMD FCH Azalia Controller                                                                         | 3         | 2.27%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 1.52%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.52%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.52%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 1.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.52%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.52%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.52%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.52%   |
| Plantronics Blackwire 3225 Series                                                                 | 1         | 0.76%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.76%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.76%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.76%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.76%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.76%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.76%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.76%   |
| Nvidia Audio device                                                                               | 1         | 0.76%   |
| Logitech PRO X                                                                                    | 1         | 0.76%   |
| LINE TECH INDUSTRIAL YTL HEADSET                                                                  | 1         | 0.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 0.76%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 0.76%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.76%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 24        | 35.29%  |
| SK hynix            | 17        | 25%     |
| Kingston            | 7         | 10.29%  |
| Micron Technology   | 6         | 8.82%   |
| Elpida              | 3         | 4.41%   |
| Unknown (ABCD)      | 2         | 2.94%   |
| Ramaxel Technology  | 2         | 2.94%   |
| Unknown             | 1         | 1.47%   |
| Teikon              | 1         | 1.47%   |
| Magnum Tech         | 1         | 1.47%   |
| fef5                | 1         | 1.47%   |
| ChangXin Memory     | 1         | 1.47%   |
| A-DATA Technology   | 1         | 1.47%   |
| 8945000080AD        | 1         | 1.47%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s              | 4         | 5.56%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 4.17%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 2.78%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 2.78%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 2         | 2.78%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 2.78%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s               | 2         | 2.78%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                         | 1         | 1.39%   |
| Teikon RAM TMT41GS6BFR8A-PBHJ 8GB SODIMM DDR3 1600MT/s              | 1         | 1.39%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                        | 1         | 1.39%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2133MT/s                        | 1         | 1.39%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                       | 1         | 1.39%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 1.39%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 1.39%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB Chip DDR3 1600MT/s                | 1         | 1.39%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 1.39%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s             | 1         | 1.39%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s             | 1         | 1.39%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 1.39%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 1.39%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s              | 1         | 1.39%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8192MB SODIMM LPDDR4 4266MT/s       | 1         | 1.39%   |
| SK hynix RAM H9HCNNN8KUMLHR 1GB 2400MT/s                            | 1         | 1.39%   |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8GB Row Of Chips LPDDR3 1867MT/s    | 1         | 1.39%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                         | 1         | 1.39%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                         | 1         | 1.39%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                        | 1         | 1.39%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 1         | 1.39%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 1.39%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s         | 1         | 1.39%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 1         | 1.39%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 1         | 1.39%   |
| Samsung RAM M471A5143SB1-CRC 4GB SODIMM DDR4 2400MT/s               | 1         | 1.39%   |
| Samsung RAM M471A2G44BM0-CWE 16GB SODIMM DDR4 3200MT/s              | 1         | 1.39%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s              | 1         | 1.39%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 1         | 1.39%   |
| Samsung RAM M471A1K44BM0-CRC 8GB SODIMM DDR4 2400MT/s               | 1         | 1.39%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 1.39%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 1.39%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB LPDDR4 2400MT/s                     | 1         | 1.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 33        | 58.93%  |
| DDR3    | 13        | 23.21%  |
| LPDDR4  | 7         | 12.5%   |
| SDRAM   | 1         | 1.79%   |
| LPDDR3  | 1         | 1.79%   |
| Unknown | 1         | 1.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 49        | 87.5%   |
| Row Of Chips | 4         | 7.14%   |
| Unknown      | 2         | 3.57%   |
| Chip         | 1         | 1.79%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 25        | 43.86%  |
| 4096  | 11        | 19.3%   |
| 16384 | 9         | 15.79%  |
| 32768 | 5         | 8.77%   |
| 2048  | 5         | 8.77%   |
| 1024  | 2         | 3.51%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 17        | 27.87%  |
| 2667  | 11        | 18.03%  |
| 1600  | 10        | 16.39%  |
| 2400  | 8         | 13.11%  |
| 2133  | 3         | 4.92%   |
| 1334  | 2         | 3.28%   |
| 1333  | 2         | 3.28%   |
| 4267  | 1         | 1.64%   |
| 4266  | 1         | 1.64%   |
| 4199  | 1         | 1.64%   |
| 3733  | 1         | 1.64%   |
| 3266  | 1         | 1.64%   |
| 1867  | 1         | 1.64%   |
| 1067  | 1         | 1.64%   |
| 1066  | 1         | 1.64%   |

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
| Chicony Electronics                    | 29        | 34.94%  |
| Realtek Semiconductor                  | 8         | 9.64%   |
| IMC Networks                           | 8         | 9.64%   |
| Microdia                               | 5         | 6.02%   |
| Sunplus Innovation Technology          | 4         | 4.82%   |
| Apple                                  | 4         | 4.82%   |
| Acer                                   | 4         | 4.82%   |
| Syntek                                 | 3         | 3.61%   |
| Quanta                                 | 3         | 3.61%   |
| Luxvisions Innotech Limited            | 3         | 3.61%   |
| Bison Electronics                      | 3         | 3.61%   |
| Unknown (3730304233333731323245)       | 1         | 1.2%    |
| Samsung Electronics                    | 1         | 1.2%    |
| Polycom                                | 1         | 1.2%    |
| Pixart Imaging                         | 1         | 1.2%    |
| Logitech                               | 1         | 1.2%    |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.2%    |
| Alcor Micro                            | 1         | 1.2%    |
| 8SSC21D67422V1SR3AV5KW1                | 1         | 1.2%    |
| Unknown                                | 1         | 1.2%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony HD Webcam                             | 6         | 7.23%   |
| Chicony Integrated Camera                     | 4         | 4.82%   |
| Chicony HP HD Camera                          | 4         | 4.82%   |
| Realtek Integrated_Webcam_HD                  | 3         | 3.61%   |
| Microdia Integrated_Webcam_HD                 | 3         | 3.61%   |
| IMC Networks USB2.0 HD UVC WebCam             | 3         | 3.61%   |
| IMC Networks Integrated Camera                | 3         | 3.61%   |
| Chicony USB2.0 Camera                         | 3         | 3.61%   |
| Apple FaceTime HD Camera                      | 3         | 3.61%   |
| Acer SunplusIT Integrated Camera              | 3         | 3.61%   |
| Syntek Integrated Camera                      | 2         | 2.41%   |
| Realtek USB Camera                            | 2         | 2.41%   |
| Quanta USB2.0 HD UVC WebCam                   | 2         | 2.41%   |
| Luxvisions Innotech Limited HP HD Camera      | 2         | 2.41%   |
| Chicony USB2.0 VGA UVC WebCam                 | 2         | 2.41%   |
| Bison EasyCamera                              | 2         | 2.41%   |
| Unknown (3730304233333731323245) USB Camera   | 1         | 1.2%    |
| Syntek Lenovo EasyCamera                      | 1         | 1.2%    |
| Sunplus Laptop_Integrated_Webcam_FHD          | 1         | 1.2%    |
| Sunplus Integrated_Webcam_HD                  | 1         | 1.2%    |
| Sunplus HD WebCam                             | 1         | 1.2%    |
| Sunplus FHD Camera Microphone                 | 1         | 1.2%    |
| Samsung Galaxy series, misc. (MTP mode)       | 1         | 1.2%    |
| Realtek USB2.0 HD UVC WebCam                  | 1         | 1.2%    |
| Realtek Lenovo EasyCamera                     | 1         | 1.2%    |
| Realtek Integrated Webcam                     | 1         | 1.2%    |
| Quanta HP Wide Vision HD Camera               | 1         | 1.2%    |
| Polycom Poly Studio P5 webcam                 | 1         | 1.2%    |
| Pixart Imaging USB_2.0_Webcam                 | 1         | 1.2%    |
| Microdia Lenovo EasyCamera                    | 1         | 1.2%    |
| Microdia Integrated Webcam HD                 | 1         | 1.2%    |
| Luxvisions Innotech Limited Integrated Camera | 1         | 1.2%    |
| Logitech StreamCam                            | 1         | 1.2%    |
| IMC Networks USB2.0 VGA UVC WebCam            | 1         | 1.2%    |
| IMC Networks Integrated RGB Camera            | 1         | 1.2%    |
| Chicony XiaoMi USB 2.0 Webcam                 | 1         | 1.2%    |
| Chicony USB2.0 UVC WebCam                     | 1         | 1.2%    |
| Chicony USB2.0 0.3M UVC WebCam                | 1         | 1.2%    |
| Chicony USB 2.0 Camera                        | 1         | 1.2%    |
| Chicony Lenovo EasyCamera                     | 1         | 1.2%    |

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
| 0     | 56        | 58.33%  |
| 1     | 29        | 30.21%  |
| 2     | 8         | 8.33%   |
| 3     | 2         | 2.08%   |
| 7     | 1         | 1.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 21        | 40.38%  |
| Net/wireless             | 5         | 9.62%   |
| Graphics card            | 5         | 9.62%   |
| Chipcard                 | 5         | 9.62%   |
| Communication controller | 4         | 7.69%   |
| Camera                   | 4         | 7.69%   |
| Multimedia controller    | 3         | 5.77%   |
| Sound                    | 2         | 3.85%   |
| Card reader              | 2         | 3.85%   |
| Bluetooth                | 1         | 1.92%   |


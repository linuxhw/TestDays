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

Total: 157

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Pavilion dv8                | [24eb3d99a9](https://linux-hardware.org/?probe=24eb3d99a9) | Apr 11, 2024 |
| Chuwi         | X312B                       | [3623330a1c](https://linux-hardware.org/?probe=3623330a1c) | Apr 09, 2024 |
| Chuwi         | X312B                       | [5aa107f741](https://linux-hardware.org/?probe=5aa107f741) | Apr 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [7bb2773966](https://linux-hardware.org/?probe=7bb2773966) | Apr 05, 2024 |
| Lenovo        | G50-45 80E3                 | [297eab2023](https://linux-hardware.org/?probe=297eab2023) | Mar 31, 2024 |
| Google        | Bobba                       | [d69b117fd0](https://linux-hardware.org/?probe=d69b117fd0) | Mar 30, 2024 |
| HP            | Dragonfly 13.5 inch G4 N... | [4b22ed6279](https://linux-hardware.org/?probe=4b22ed6279) | Mar 29, 2024 |
| Packard Be... | EasyNote TM98               | [e6c48ef91f](https://linux-hardware.org/?probe=e6c48ef91f) | Mar 22, 2024 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [d337b27afc](https://linux-hardware.org/?probe=d337b27afc) | Mar 21, 2024 |
| HP            | ProBook 450 G1              | [3bfd1620fe](https://linux-hardware.org/?probe=3bfd1620fe) | Mar 12, 2024 |
| Apple         | MacBookPro6,2               | [a3b8064ddf](https://linux-hardware.org/?probe=a3b8064ddf) | Feb 29, 2024 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [4963c40308](https://linux-hardware.org/?probe=4963c40308) | Feb 27, 2024 |
| Apple         | MacBookPro6,2               | [fd9e5de8cf](https://linux-hardware.org/?probe=fd9e5de8cf) | Feb 22, 2024 |
| Dell          | Vostro 5625                 | [04e53619c6](https://linux-hardware.org/?probe=04e53619c6) | Feb 19, 2024 |
| TUXEDO        | InfinityBook_Pro13_14_v4    | [4264042062](https://linux-hardware.org/?probe=4264042062) | Feb 18, 2024 |
| HP            | 15                          | [ef0b519e9b](https://linux-hardware.org/?probe=ef0b519e9b) | Feb 12, 2024 |
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


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 5.15.0-27-generic    | 7         | 5.65%   |
| 5.15.0-50-generic    | 5         | 4.03%   |
| 5.15.0-48-generic    | 5         | 4.03%   |
| 6.5.0-18-generic     | 4         | 3.23%   |
| 6.2.0-39-generic     | 4         | 3.23%   |
| 5.19.0-46-generic    | 4         | 3.23%   |
| 5.15.0-52-generic    | 4         | 3.23%   |
| 6.5.0-26-generic     | 3         | 2.42%   |
| 6.2.0-26-generic     | 3         | 2.42%   |
| 5.19.0-41-generic    | 3         | 2.42%   |
| 5.19.0-35-generic    | 3         | 2.42%   |
| 5.15.0-53-generic    | 3         | 2.42%   |
| 5.15.0-40-generic    | 3         | 2.42%   |
| 5.15.0-39-generic    | 3         | 2.42%   |
| 5.15.0-30-generic    | 3         | 2.42%   |
| 6.5.0-15-generic     | 2         | 1.61%   |
| 6.5.0-14-generic     | 2         | 1.61%   |
| 6.5.0-10013-tuxedo   | 2         | 1.61%   |
| 6.2.0-33-generic     | 2         | 1.61%   |
| 6.2.0-32-generic     | 2         | 1.61%   |
| 6.2.0-10007-tuxedo   | 2         | 1.61%   |
| 5.19.0-42-generic    | 2         | 1.61%   |
| 5.19.0-38-generic    | 2         | 1.61%   |
| 5.15.0-67-generic    | 2         | 1.61%   |
| 5.15.0-58-generic    | 2         | 1.61%   |
| 5.15.0-56-generic    | 2         | 1.61%   |
| 5.15.0-47-generic    | 2         | 1.61%   |
| 5.15.0-46-generic    | 2         | 1.61%   |
| 5.15.0-33-generic    | 2         | 1.61%   |
| 5.15.0-25-generic    | 2         | 1.61%   |
| 6.5.0-27-generic     | 1         | 0.81%   |
| 6.5.0-25-generic     | 1         | 0.81%   |
| 6.5.0-10008-tuxedo   | 1         | 0.81%   |
| 6.3.1-060301-generic | 1         | 0.81%   |
| 6.2.0-37-generic     | 1         | 0.81%   |
| 6.2.0-34-generic     | 1         | 0.81%   |
| 6.2.0-10018-tuxedo   | 1         | 0.81%   |
| 6.1.0-060100-generic | 1         | 0.81%   |
| 5.19.0-45-generic    | 1         | 0.81%   |
| 5.19.0-40-generic    | 1         | 0.81%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 63        | 55.26%  |
| 5.19.0  | 17        | 14.91%  |
| 6.5.0   | 15        | 13.16%  |
| 6.2.0   | 15        | 13.16%  |
| 5.13.0  | 2         | 1.75%   |
| 6.3.1   | 1         | 0.88%   |
| 6.1.0   | 1         | 0.88%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 63        | 55.26%  |
| 5.19    | 17        | 14.91%  |
| 6.5     | 15        | 13.16%  |
| 6.2     | 15        | 13.16%  |
| 5.13    | 2         | 1.75%   |
| 6.3     | 1         | 0.88%   |
| 6.1     | 1         | 0.88%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 108       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Budgie | 101       | 93.52%  |
| GNOME  | 6         | 5.56%   |
| KDE5   | 1         | 0.93%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 105       | 97.22%  |
| Wayland | 3         | 2.78%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 80        | 73.39%  |
| Unknown | 16        | 14.68%  |
| GDM3    | 12        | 11.01%  |
| SDDM    | 1         | 0.92%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 35        | 32.41%  |
| de_DE | 13        | 12.04%  |
| fr_FR | 11        | 10.19%  |
| en_GB | 6         | 5.56%   |
| pt_BR | 5         | 4.63%   |
| it_IT | 4         | 3.7%    |
| en_CA | 4         | 3.7%    |
| ru_RU | 3         | 2.78%   |
| hu_HU | 2         | 1.85%   |
| fr_BE | 2         | 1.85%   |
| eu_ES | 2         | 1.85%   |
| es_ES | 2         | 1.85%   |
| en_IE | 2         | 1.85%   |
| pl_PL | 1         | 0.93%   |
| mt_MT | 1         | 0.93%   |
| ja_JP | 1         | 0.93%   |
| es_PE | 1         | 0.93%   |
| es_MX | 1         | 0.93%   |
| es_EC | 1         | 0.93%   |
| es_CL | 1         | 0.93%   |
| es_AR | 1         | 0.93%   |
| en_ZA | 1         | 0.93%   |
| en_SG | 1         | 0.93%   |
| en_IN | 1         | 0.93%   |
| en_IL | 1         | 0.93%   |
| en_AU | 1         | 0.93%   |
| da_DK | 1         | 0.93%   |
| cs_CZ | 1         | 0.93%   |
| C     | 1         | 0.93%   |
| bg_BG | 1         | 0.93%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 59        | 54.13%  |
| EFI  | 50        | 45.87%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 89        | 80.18%  |
| Tmpfs   | 13        | 11.71%  |
| Overlay | 4         | 3.6%    |
| Zfs     | 3         | 2.7%    |
| Xfs     | 1         | 0.9%    |
| Btrfs   | 1         | 0.9%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 76        | 70.37%  |
| Unknown | 25        | 23.15%  |
| MBR     | 7         | 6.48%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 94        | 87.04%  |
| Yes       | 14        | 12.96%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 74        | 67.89%  |
| Yes       | 35        | 32.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 22        | 20.37%  |
| Hewlett-Packard        | 16        | 14.81%  |
| ASUSTek Computer       | 16        | 14.81%  |
| Dell                   | 14        | 12.96%  |
| TUXEDO                 | 11        | 10.19%  |
| Apple                  | 6         | 5.56%   |
| Toshiba                | 3         | 2.78%   |
| MSI                    | 3         | 2.78%   |
| Google                 | 3         | 2.78%   |
| Chuwi                  | 2         | 1.85%   |
| Acer                   | 2         | 1.85%   |
| Timi                   | 1         | 0.93%   |
| Razer                  | 1         | 0.93%   |
| Packard Bell           | 1         | 0.93%   |
| HUAWEI                 | 1         | 0.93%   |
| Digibras               | 1         | 0.93%   |
| COM1                   | 1         | 0.93%   |
| BANGHO                 | 1         | 0.93%   |
| AXIOO                  | 1         | 0.93%   |
| Avell High Performance | 1         | 0.93%   |
| Alurin                 | 1         | 0.93%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                 | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| TUXEDO Pulse 15 Gen1                                 | 2         | 1.85%   |
| Lenovo G50-45 80E3                                   | 2         | 1.85%   |
| HP EliteBook 840 G3                                  | 2         | 1.85%   |
| TUXEDO Pulse 14 Gen1                                 | 1         | 0.93%   |
| TUXEDO Polaris Intel Gen3 (TGL)                      | 1         | 0.93%   |
| TUXEDO InfinityBook_Pro13_14_v4                      | 1         | 0.93%   |
| TUXEDO InfinityBook S 15 Gen6                        | 1         | 0.93%   |
| TUXEDO InfinityBook Pro 14 v4                        | 1         | 0.93%   |
| TUXEDO Book XUX7 Gen11                               | 1         | 0.93%   |
| TUXEDO Book XP1511                                   | 1         | 0.93%   |
| TUXEDO Book BA1510                                   | 1         | 0.93%   |
| TUXEDO Aura 15 Gen1                                  | 1         | 0.93%   |
| Toshiba Satellite C855D-11X                          | 1         | 0.93%   |
| Toshiba Satellite A505                               | 1         | 0.93%   |
| Toshiba Satellite A300                               | 1         | 0.93%   |
| Timi TM1604                                          | 1         | 0.93%   |
| Razer Blade 15 Advanced Model (Mid 2021) - RZ09-0409 | 1         | 0.93%   |
| Packard Bell EasyNote TM98                           | 1         | 0.93%   |
| MSI Modern 15 A10M                                   | 1         | 0.93%   |
| MSI GL62 6QF                                         | 1         | 0.93%   |
| MSI Alpha 15 B5EEK                                   | 1         | 0.93%   |
| Lenovo V15 G2 ALC 82KD                               | 1         | 0.93%   |
| Lenovo ThinkPad X260 20F5S0V500                      | 1         | 0.93%   |
| Lenovo ThinkPad X220 4291G75                         | 1         | 0.93%   |
| Lenovo ThinkPad X1 Carbon 5th 20HR002SIV             | 1         | 0.93%   |
| Lenovo ThinkPad T500 2242CTO                         | 1         | 0.93%   |
| Lenovo ThinkPad T480s 20L8SF1X00                     | 1         | 0.93%   |
| Lenovo ThinkPad T480 20L6SDR21A                      | 1         | 0.93%   |
| Lenovo ThinkPad T440 20B7S0F100                      | 1         | 0.93%   |
| Lenovo ThinkPad T14 Gen 3 21AHCTO1WW                 | 1         | 0.93%   |
| Lenovo ThinkPad T14 Gen 2i 20W000Q4GE                | 1         | 0.93%   |
| Lenovo ThinkPad E15 20RD003KHV                       | 1         | 0.93%   |
| Lenovo Legion Y530-15ICH 81FV                        | 1         | 0.93%   |
| Lenovo IdeaPad Z500 20202                            | 1         | 0.93%   |
| Lenovo IdeaPad S145-14IWL 81MU                       | 1         | 0.93%   |
| Lenovo IdeaPad C340-14API 81N6                       | 1         | 0.93%   |
| Lenovo IdeaPad 520-15IKB 81BF                        | 1         | 0.93%   |
| Lenovo IdeaPad 5 15ARE05 81YQ                        | 1         | 0.93%   |
| Lenovo IdeaPad 330-15IKB 81FE                        | 1         | 0.93%   |
| Lenovo IdeaPad 110-15ISK 80UD                        | 1         | 0.93%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 10        | 9.26%   |
| Lenovo IdeaPad        | 7         | 6.48%   |
| Dell Latitude         | 5         | 4.63%   |
| HP ProBook            | 4         | 3.7%    |
| HP EliteBook          | 4         | 3.7%    |
| Dell Inspiron         | 4         | 3.7%    |
| ASUS VivoBook         | 4         | 3.7%    |
| TUXEDO Pulse          | 3         | 2.78%   |
| TUXEDO InfinityBook   | 3         | 2.78%   |
| TUXEDO Book           | 3         | 2.78%   |
| Toshiba Satellite     | 3         | 2.78%   |
| HP Pavilion           | 3         | 2.78%   |
| ASUS ZenBook          | 3         | 2.78%   |
| Lenovo G50-45         | 2         | 1.85%   |
| Dell XPS              | 2         | 1.85%   |
| Dell Vostro           | 2         | 1.85%   |
| Apple MacBookPro8     | 2         | 1.85%   |
| Acer Aspire           | 2         | 1.85%   |
| TUXEDO Polaris        | 1         | 0.93%   |
| TUXEDO Aura           | 1         | 0.93%   |
| Timi TM1604           | 1         | 0.93%   |
| Razer Blade           | 1         | 0.93%   |
| Packard Bell EasyNote | 1         | 0.93%   |
| MSI Modern            | 1         | 0.93%   |
| MSI GL62              | 1         | 0.93%   |
| MSI Alpha             | 1         | 0.93%   |
| Lenovo V15            | 1         | 0.93%   |
| Lenovo Legion         | 1         | 0.93%   |
| Lenovo G500           | 1         | 0.93%   |
| HUAWEI HKD-WXX        | 1         | 0.93%   |
| HP ENVY               | 1         | 0.93%   |
| HP ElitePad           | 1         | 0.93%   |
| HP Dragonfly          | 1         | 0.93%   |
| HP Bloog              | 1         | 0.93%   |
| HP 15                 | 1         | 0.93%   |
| Google Rabbid         | 1         | 0.93%   |
| Google Boten          | 1         | 0.93%   |
| Google Bobba          | 1         | 0.93%   |
| Digibras NH4CU03      | 1         | 0.93%   |
| Dell Precision        | 1         | 0.93%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 19        | 17.59%  |
| 2020 | 18        | 16.67%  |
| 2016 | 9         | 8.33%   |
| 2014 | 8         | 7.41%   |
| 2019 | 6         | 5.56%   |
| 2018 | 6         | 5.56%   |
| 2013 | 6         | 5.56%   |
| 2017 | 5         | 4.63%   |
| 2012 | 5         | 4.63%   |
| 2022 | 4         | 3.7%    |
| 2015 | 4         | 3.7%    |
| 2011 | 4         | 3.7%    |
| 2010 | 4         | 3.7%    |
| 2009 | 4         | 3.7%    |
| 2023 | 3         | 2.78%   |
| 2008 | 2         | 1.85%   |
| 2024 | 1         | 0.93%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 108       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 99        | 91.67%  |
| Enabled  | 9         | 8.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 104       | 96.3%   |
| Yes  | 4         | 3.7%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 35        | 31.82%  |
| 16.01-24.0  | 26        | 23.64%  |
| 3.01-4.0    | 17        | 15.45%  |
| 8.01-16.0   | 17        | 15.45%  |
| 32.01-64.0  | 9         | 8.18%   |
| 64.01-256.0 | 5         | 4.55%   |
| 1.01-2.0    | 1         | 0.91%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 42        | 35.9%   |
| 1.01-2.0   | 28        | 23.93%  |
| 4.01-8.0   | 17        | 14.53%  |
| 3.01-4.0   | 15        | 12.82%  |
| 8.01-16.0  | 11        | 9.4%    |
| 24.01-32.0 | 2         | 1.71%   |
| 16.01-24.0 | 2         | 1.71%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 84        | 75.68%  |
| 2      | 24        | 21.62%  |
| 3      | 3         | 2.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 87        | 80.56%  |
| Yes       | 21        | 19.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 85        | 77.98%  |
| No        | 24        | 22.02%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 106       | 98.15%  |
| No        | 2         | 1.85%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 93        | 86.11%  |
| No        | 15        | 13.89%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| Germany            | 17        | 15.74%  |
| USA                | 14        | 12.96%  |
| France             | 12        | 11.11%  |
| Brazil             | 5         | 4.63%   |
| Spain              | 4         | 3.7%    |
| Italy              | 4         | 3.7%    |
| Canada             | 4         | 3.7%    |
| UK                 | 3         | 2.78%   |
| Poland             | 3         | 2.78%   |
| Russia             | 2         | 1.85%   |
| Peru               | 2         | 1.85%   |
| Ireland            | 2         | 1.85%   |
| Indonesia          | 2         | 1.85%   |
| Hungary            | 2         | 1.85%   |
| Bulgaria           | 2         | 1.85%   |
| Belgium            | 2         | 1.85%   |
| Austria            | 2         | 1.85%   |
| Turkey             | 1         | 0.93%   |
| Sweden             | 1         | 0.93%   |
| South Africa       | 1         | 0.93%   |
| Slovenia           | 1         | 0.93%   |
| Slovakia           | 1         | 0.93%   |
| Singapore          | 1         | 0.93%   |
| Romania            | 1         | 0.93%   |
| Netherlands        | 1         | 0.93%   |
| Mexico             | 1         | 0.93%   |
| Malta              | 1         | 0.93%   |
| Japan              | 1         | 0.93%   |
| Israel             | 1         | 0.93%   |
| India              | 1         | 0.93%   |
| Greece             | 1         | 0.93%   |
| Ghana              | 1         | 0.93%   |
| Ecuador            | 1         | 0.93%   |
| Dominican Republic | 1         | 0.93%   |
| Denmark            | 1         | 0.93%   |
| Czechia            | 1         | 0.93%   |
| Cuba               | 1         | 0.93%   |
| Chile              | 1         | 0.93%   |
| Cabo Verde         | 1         | 0.93%   |
| Belarus            | 1         | 0.93%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Berlin                | 3         | 2.68%   |
| Warsaw                | 2         | 1.79%   |
| Vienna                | 2         | 1.79%   |
| Victoria              | 2         | 1.79%   |
| Nuremberg             | 2         | 1.79%   |
| Laval                 | 2         | 1.79%   |
| Frankfurt am Main     | 2         | 1.79%   |
| Dublin                | 2         | 1.79%   |
| Budapest              | 2         | 1.79%   |
| Yogyakarta            | 1         | 0.89%   |
| Wertheim am Main      | 1         | 0.89%   |
| Weisswasser           | 1         | 0.89%   |
| Weilheim              | 1         | 0.89%   |
| Washington            | 1         | 0.89%   |
| Veliko Tarnovo        | 1         | 0.89%   |
| Torun                 | 1         | 0.89%   |
| Tegueste              | 1         | 0.89%   |
| Targu Frumos          | 1         | 0.89%   |
| Tarakan               | 1         | 0.89%   |
| Sunnyvale             | 1         | 0.89%   |
| St Petersburg         | 1         | 0.89%   |
| Sofia                 | 1         | 0.89%   |
| Singapore             | 1         | 0.89%   |
| Siegen                | 1         | 0.89%   |
| Shirakuni             | 1         | 0.89%   |
| Sétif                | 1         | 0.89%   |
| Seelze                | 1         | 0.89%   |
| Sao Paulo             | 1         | 0.89%   |
| Sao Bernardo do Campo | 1         | 0.89%   |
| Santo Domingo Este    | 1         | 0.89%   |
| Santiago              | 1         | 0.89%   |
| Saint-Gilles          | 1         | 0.89%   |
| Rishon LeTsiyyon      | 1         | 0.89%   |
| Richmond              | 1         | 0.89%   |
| Renton                | 1         | 0.89%   |
| Recife                | 1         | 0.89%   |
| Queens                | 1         | 0.89%   |
| Quedlinburg           | 1         | 0.89%   |
| Puteaux               | 1         | 0.89%   |
| Puebla City           | 1         | 0.89%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 31        | 38     | 23.31%  |
| Unknown                        | 13        | 13     | 9.77%   |
| Toshiba                        | 10        | 13     | 7.52%   |
| WDC                            | 9         | 10     | 6.77%   |
| SK hynix                       | 8         | 8      | 6.02%   |
| Micron Technology              | 7         | 7      | 5.26%   |
| Crucial                        | 7         | 13     | 5.26%   |
| Seagate                        | 6         | 6      | 4.51%   |
| Kingston                       | 5         | 5      | 3.76%   |
| SanDisk                        | 4         | 4      | 3.01%   |
| Intel                          | 4         | 4      | 3.01%   |
| China                          | 3         | 4      | 2.26%   |
| SPCC                           | 2         | 3      | 1.5%    |
| JMicron Technology             | 2         | 2      | 1.5%    |
| Apple                          | 2         | 2      | 1.5%    |
| A-DATA Technology              | 2         | 3      | 1.5%    |
| YMTC                           | 1         | 1      | 0.75%   |
| VISIPRO                        | 1         | 1      | 0.75%   |
| Union Memory                   | 1         | 1      | 0.75%   |
| TO Exter                       | 1         | 1      | 0.75%   |
| Solid State Storage Technology | 1         | 1      | 0.75%   |
| Silicon Motion                 | 1         | 1      | 0.75%   |
| Realtek Semiconductor          | 1         | 1      | 0.75%   |
| Phison Electronics             | 1         | 1      | 0.75%   |
| OWC                            | 1         | 1      | 0.75%   |
| Netac                          | 1         | 1      | 0.75%   |
| NE-1TB                         | 1         | 1      | 0.75%   |
| Kllisre                        | 1         | 1      | 0.75%   |
| KIOXIA                         | 1         | 1      | 0.75%   |
| HGST                           | 1         | 1      | 0.75%   |
| Hewlett-Packard                | 1         | 1      | 0.75%   |
| Gigabyte Technology            | 1         | 1      | 0.75%   |
| Corsair                        | 1         | 2      | 0.75%   |
| Unknown                        | 1         | 1      | 0.75%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 4         | 2.96%   |
| Samsung SSD 860 EVO M.2 500GB                     | 3         | 2.22%   |
| Samsung SSD 860 EVO 500GB                         | 3         | 2.22%   |
| WDC WD10JPVX-22JC3T0 1TB                          | 2         | 1.48%   |
| Unknown SD64G  64GB                               | 2         | 1.48%   |
| Unknown MMC Card  64GB                            | 2         | 1.48%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 2         | 1.48%   |
| Samsung SSD 980 PRO 2TB                           | 2         | 1.48%   |
| Samsung SSD 980 500GB                             | 2         | 1.48%   |
| Samsung MZVLQ512HALU-000H1 512GB                  | 2         | 1.48%   |
| Kingston SA400S37240G 240GB SSD                   | 2         | 1.48%   |
| Crucial CT240BX500SSD1 240GB                      | 2         | 1.48%   |
| YMTC PC005 1TB                                    | 1         | 0.74%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 1         | 0.74%   |
| WDC WD6400BEVT-22A0RT0 640GB                      | 1         | 0.74%   |
| WDC WD10JPVX-75JC3T0 1TB                          | 1         | 0.74%   |
| WDC WD10JPVX-60JC3T0 1TB                          | 1         | 0.74%   |
| WDC PC SN730 NVMe 256GB                           | 1         | 0.74%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB              | 1         | 0.74%   |
| WDC PC SN530 SDBPTPZ-512G-1002 512GB              | 1         | 0.74%   |
| WDC PC SN520 SDAPNUW-512G-1002 512GB              | 1         | 0.74%   |
| VISIPRO SSD 256GB                                 | 1         | 0.74%   |
| Unknown SL128  128GB                              | 1         | 0.74%   |
| Unknown SA16G  16GB                               | 1         | 0.74%   |
| Unknown NVMe SSD Drive 512GB                      | 1         | 0.74%   |
| Unknown NCard  4GB                                | 1         | 0.74%   |
| Unknown MMC128  128GB                             | 1         | 0.74%   |
| Unknown MMC Card  968MB                           | 1         | 0.74%   |
| Unknown MMC Card  32GB                            | 1         | 0.74%   |
| Unknown MMC Card  128GB                           | 1         | 0.74%   |
| Unknown DA4064  64GB                              | 1         | 0.74%   |
| Union Memory RTOTJ128VGD2EYX 128GB SSD            | 1         | 0.74%   |
| Toshiba XG6 NVMe SSD Controller 1024GB            | 1         | 0.74%   |
| Toshiba TR150 480GB SSD                           | 1         | 0.74%   |
| Toshiba MQ04ABF100 1TB                            | 1         | 0.74%   |
| Toshiba MQ01ABD100 1TB                            | 1         | 0.74%   |
| Toshiba MQ01ABD075 752GB                          | 1         | 0.74%   |
| Toshiba MQ01ABD050 500GB                          | 1         | 0.74%   |
| Toshiba MK1059GSM 1TB                             | 1         | 0.74%   |
| Toshiba KXG50ZNV512G NVMe 512GB                   | 1         | 0.74%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 30%     |
| WDC                 | 5         | 5      | 25%     |
| Toshiba             | 5         | 5      | 25%     |
| TO Exter            | 1         | 1      | 5%      |
| Samsung Electronics | 1         | 1      | 5%      |
| JMicron Technology  | 1         | 1      | 5%      |
| HGST                | 1         | 1      | 5%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 17     | 25.53%  |
| Crucial             | 7         | 13     | 14.89%  |
| Micron Technology   | 4         | 4      | 8.51%   |
| SanDisk             | 3         | 3      | 6.38%   |
| Kingston            | 3         | 3      | 6.38%   |
| China               | 3         | 4      | 6.38%   |
| SPCC                | 2         | 3      | 4.26%   |
| Apple               | 2         | 2      | 4.26%   |
| WDC                 | 1         | 1      | 2.13%   |
| VISIPRO             | 1         | 1      | 2.13%   |
| Union Memory        | 1         | 1      | 2.13%   |
| Toshiba             | 1         | 1      | 2.13%   |
| SK hynix            | 1         | 1      | 2.13%   |
| OWC                 | 1         | 1      | 2.13%   |
| Netac               | 1         | 1      | 2.13%   |
| Intel               | 1         | 1      | 2.13%   |
| Hewlett-Packard     | 1         | 1      | 2.13%   |
| Gigabyte Technology | 1         | 1      | 2.13%   |
| Corsair             | 1         | 2      | 2.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 48        | 55     | 37.8%   |
| SSD     | 44        | 61     | 34.65%  |
| HDD     | 19        | 20     | 14.96%  |
| MMC     | 13        | 15     | 10.24%  |
| Unknown | 3         | 3      | 2.36%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 57        | 79     | 46.72%  |
| NVMe | 48        | 55     | 39.34%  |
| MMC  | 13        | 15     | 10.66%  |
| SAS  | 4         | 5      | 3.28%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 43        | 56     | 67.19%  |
| 0.51-1.0   | 16        | 19     | 25%     |
| 1.01-2.0   | 5         | 6      | 7.81%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 34        | 31.48%  |
| 101-250        | 34        | 31.48%  |
| 501-1000       | 15        | 13.89%  |
| 51-100         | 8         | 7.41%   |
| 21-50          | 5         | 4.63%   |
| 1001-2000      | 5         | 4.63%   |
| 1-20           | 5         | 4.63%   |
| More than 3000 | 1         | 0.93%   |
| 2001-3000      | 1         | 0.93%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 33        | 29.73%  |
| 21-50     | 25        | 22.52%  |
| 101-250   | 22        | 19.82%  |
| 51-100    | 12        | 10.81%  |
| 251-500   | 11        | 9.91%   |
| 501-1000  | 5         | 4.5%    |
| 1001-2000 | 3         | 2.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                    | Notebooks | Drives | Percent |
|--------------------------|-----------|--------|---------|
| WDC WD10JPVX-60JC3T0 1TB | 1         | 1      | 33.33%  |
| Toshiba MQ01ABD075 752GB | 1         | 1      | 33.33%  |
| HGST HTS541010A9E680 1TB | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Toshiba | 1         | 1      | 33.33%  |
| HGST    | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Toshiba | 1         | 1      | 33.33%  |
| HGST    | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 100%    |

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
| Detected | 63        | 90     | 55.75%  |
| Works    | 47        | 61     | 41.59%  |
| Malfunc  | 3         | 3      | 2.65%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 69        | 53.49%  |
| Samsung Electronics            | 18        | 13.95%  |
| AMD                            | 12        | 9.3%    |
| SK hynix                       | 5         | 3.88%   |
| SanDisk                        | 5         | 3.88%   |
| Toshiba America Info Systems   | 3         | 2.33%   |
| Micron Technology              | 3         | 2.33%   |
| KIOXIA                         | 2         | 1.55%   |
| Kingston Technology Company    | 2         | 1.55%   |
| ADATA Technology               | 2         | 1.55%   |
| Yangtze Memory Technologies    | 1         | 0.78%   |
| Solidigm                       | 1         | 0.78%   |
| Solid State Storage Technology | 1         | 0.78%   |
| Silicon Motion                 | 1         | 0.78%   |
| Realtek Semiconductor          | 1         | 0.78%   |
| Phison Electronics             | 1         | 0.78%   |
| Nvidia                         | 1         | 0.78%   |
| Marvell Technology Group       | 1         | 0.78%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 12        | 8.89%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 11        | 8.15%   |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 5.19%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 6         | 4.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 3.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 5         | 3.7%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 5         | 3.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 3.7%    |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 2.96%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 2.96%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 4         | 2.96%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 2.22%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 2.22%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 2.22%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 2.22%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 2.22%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.48%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 2         | 1.48%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 2         | 1.48%   |
| Intel SSD 660P Series                                                          | 2         | 1.48%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 1.48%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 1.48%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 1.48%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.48%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.48%   |
| Yangtze Memory PC005 NVMe SSD                                                  | 1         | 0.74%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.74%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.74%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 1         | 0.74%   |
| Solidigm P41 Plus NVMe SSD (DRAM-less) [Echo Harbor]                           | 1         | 0.74%   |
| Solid State Storage CA6-8D512 NVMe SSD M.2                                     | 1         | 0.74%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 1         | 0.74%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.74%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 1         | 0.74%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 1         | 0.74%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1         | 0.74%   |
| SanDisk IX SN530 NVMe SSD (DRAM-less)                                          | 1         | 0.74%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 1         | 0.74%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 1         | 0.74%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                              | 1         | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 74        | 55.64%  |
| NVMe | 48        | 36.09%  |
| RAID | 10        | 7.52%   |
| IDE  | 1         | 0.75%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 91        | 84.26%  |
| AMD    | 17        | 15.74%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 4.63%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 4         | 3.7%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 4         | 3.7%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 2.78%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 2.78%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 2         | 1.85%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.85%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.85%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 2         | 1.85%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 1.85%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.85%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 1.85%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 2         | 1.85%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.85%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.85%   |
| Intel Atom CPU Z3795 @ 1.60GHz                | 2         | 1.85%   |
| Intel 11th Gen Core i7-11850H @ 2.50GHz       | 2         | 1.85%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 1.85%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.85%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 1.85%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 1.85%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.85%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics   | 2         | 1.85%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 0.93%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.93%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.93%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 0.93%   |
| Intel Core i9-10900K CPU @ 3.70GHz            | 1         | 0.93%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.93%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.93%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.93%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.93%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.93%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1         | 0.93%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 0.93%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 0.93%   |
| Intel Core i7-2760QM CPU @ 2.40GHz            | 1         | 0.93%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 0.93%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 0.93%   |
| Intel Core i7 CPU M 640 @ 2.80GHz             | 1         | 0.93%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 25        | 23.15%  |
| Intel Core i7           | 22        | 20.37%  |
| Other                   | 18        | 16.67%  |
| AMD Ryzen 7             | 9         | 8.33%   |
| Intel Celeron           | 8         | 7.41%   |
| Intel Core i3           | 6         | 5.56%   |
| AMD Ryzen 5             | 4         | 3.7%    |
| Intel Pentium           | 3         | 2.78%   |
| Intel Atom              | 3         | 2.78%   |
| Intel Pentium Silver    | 2         | 1.85%   |
| Intel Core 2 Duo        | 2         | 1.85%   |
| AMD A8                  | 2         | 1.85%   |
| Intel Pentium Dual-Core | 1         | 0.93%   |
| Intel Core i9           | 1         | 0.93%   |
| AMD Ryzen 3             | 1         | 0.93%   |
| AMD A6                  | 1         | 0.93%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 44        | 40.74%  |
| 2      | 40        | 37.04%  |
| 8      | 14        | 12.96%  |
| 6      | 5         | 4.63%   |
| 10     | 3         | 2.78%   |
| 12     | 1         | 0.93%   |
| 1      | 1         | 0.93%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 108       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 83        | 76.85%  |
| 1      | 25        | 23.15%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 108       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 67        | 60.36%  |
| 0x806c1    | 4         | 3.6%    |
| 0x08600106 | 4         | 3.6%    |
| 0x806ec    | 3         | 2.7%    |
| 0x706a8    | 3         | 2.7%    |
| 0x206a7    | 3         | 2.7%    |
| 0x806eb    | 2         | 1.8%    |
| 0x806ea    | 2         | 1.8%    |
| 0x806d1    | 2         | 1.8%    |
| 0x406e3    | 2         | 1.8%    |
| 0x20655    | 2         | 1.8%    |
| 0x0a50000c | 2         | 1.8%    |
| 0x08108102 | 2         | 1.8%    |
| 0x906ea    | 1         | 0.9%    |
| 0x806e9    | 1         | 0.9%    |
| 0x506e3    | 1         | 0.9%    |
| 0x506c9    | 1         | 0.9%    |
| 0x40651    | 1         | 0.9%    |
| 0x306d4    | 1         | 0.9%    |
| 0x306c3    | 1         | 0.9%    |
| 0x30678    | 1         | 0.9%    |
| 0x106e5    | 1         | 0.9%    |
| 0x08608103 | 1         | 0.9%    |
| 0x08600103 | 1         | 0.9%    |
| 0x07030105 | 1         | 0.9%    |
| 0x07030104 | 1         | 0.9%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 20        | 18.52%  |
| TigerLake        | 10        | 9.26%   |
| Skylake          | 10        | 9.26%   |
| Zen 2            | 7         | 6.48%   |
| Goldmont plus    | 7         | 6.48%   |
| Unknown          | 7         | 6.48%   |
| Silvermont       | 5         | 4.63%   |
| SandyBridge      | 5         | 4.63%   |
| Haswell          | 5         | 4.63%   |
| Westmere         | 4         | 3.7%    |
| IvyBridge        | 4         | 3.7%    |
| Zen 3            | 3         | 2.78%   |
| Penryn           | 3         | 2.78%   |
| IceLake          | 3         | 2.78%   |
| Broadwell        | 3         | 2.78%   |
| Zen+             | 2         | 1.85%   |
| Puma             | 2         | 1.85%   |
| Nehalem          | 2         | 1.85%   |
| CometLake        | 2         | 1.85%   |
| Alderlake Hybrid | 2         | 1.85%   |
| Piledriver       | 1         | 0.93%   |
| Goldmont         | 1         | 0.93%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 86        | 65.15%  |
| Nvidia | 25        | 18.94%  |
| AMD    | 21        | 15.91%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 10        | 7.41%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 8         | 5.93%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]             | 7         | 5.19%   |
| Intel UHD Graphics 620                                                    | 6         | 4.44%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 5         | 3.7%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 5         | 3.7%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 4         | 2.96%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 4         | 2.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 4         | 2.96%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 4         | 2.96%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 3         | 2.22%   |
| Intel HD Graphics 620                                                     | 3         | 2.22%   |
| Intel HD Graphics 5500                                                    | 3         | 2.22%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 3         | 2.22%   |
| Intel Core Processor Integrated Graphics Controller                       | 3         | 2.22%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 3         | 2.22%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 1.48%   |
| Nvidia GP108M [GeForce MX150]                                             | 2         | 1.48%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 2         | 1.48%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 2         | 1.48%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 2         | 1.48%   |
| Intel HD Graphics 530                                                     | 2         | 1.48%   |
| Intel GeminiLake [UHD Graphics 605]                                       | 2         | 1.48%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 2         | 1.48%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 2         | 1.48%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                       | 2         | 1.48%   |
| AMD Lucienne                                                              | 2         | 1.48%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 1.48%   |
| Nvidia TU117M [GeForce MX450]                                             | 1         | 0.74%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                   | 1         | 0.74%   |
| Nvidia TU104BM [GeForce RTX 2080 SUPER Mobile / Max-Q]                    | 1         | 0.74%   |
| Nvidia GT218M [GeForce 310M]                                              | 1         | 0.74%   |
| Nvidia GT216M [GeForce GT 330M]                                           | 1         | 0.74%   |
| Nvidia GT216M [GeForce GT 230M]                                           | 1         | 0.74%   |
| Nvidia GP108M [GeForce MX230]                                             | 1         | 0.74%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.74%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 0.74%   |
| Nvidia GM108M [GeForce 840M]                                              | 1         | 0.74%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 0.74%   |
| Nvidia GM107M [GeForce GTX 950M]                                          | 1         | 0.74%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 62        | 57.41%  |
| Intel + Nvidia | 19        | 17.59%  |
| 1 x AMD        | 13        | 12.04%  |
| 1 x Nvidia     | 4         | 3.7%    |
| 2 x AMD        | 3         | 2.78%   |
| Intel + AMD    | 3         | 2.78%   |
| Other          | 2         | 1.85%   |
| AMD + Nvidia   | 2         | 1.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 94        | 87.04%  |
| Proprietary | 12        | 11.11%  |
| Unknown     | 2         | 1.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 92        | 84.4%   |
| 0.01-0.5   | 7         | 6.42%   |
| 1.01-2.0   | 4         | 3.67%   |
| 0.51-1.0   | 3         | 2.75%   |
| 7.01-8.0   | 2         | 1.83%   |
| 3.01-4.0   | 1         | 0.92%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 25        | 19.53%  |
| BOE                     | 24        | 18.75%  |
| AU Optronics            | 14        | 10.94%  |
| Samsung Electronics     | 12        | 9.38%   |
| LG Display              | 11        | 8.59%   |
| Apple                   | 6         | 4.69%   |
| Sharp                   | 4         | 3.13%   |
| Goldstar                | 4         | 3.13%   |
| Philips                 | 3         | 2.34%   |
| PANDA                   | 3         | 2.34%   |
| Lenovo                  | 2         | 1.56%   |
| Dell                    | 2         | 1.56%   |
| Chi Mei Optoelectronics | 2         | 1.56%   |
| Acer                    | 2         | 1.56%   |
| Unknown (AAA)           | 1         | 0.78%   |
| TMX                     | 1         | 0.78%   |
| Sony                    | 1         | 0.78%   |
| MStar                   | 1         | 0.78%   |
| LG Philips              | 1         | 0.78%   |
| KDC                     | 1         | 0.78%   |
| JDZ                     | 1         | 0.78%   |
| InfoVision              | 1         | 0.78%   |
| IBM                     | 1         | 0.78%   |
| HKC                     | 1         | 0.78%   |
| Hewlett-Packard         | 1         | 0.78%   |
| Daewoo                  | 1         | 0.78%   |
| BenQ                    | 1         | 0.78%   |
| AOC                     | 1         | 0.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch        | 2         | 1.56%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch       | 2         | 1.56%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch       | 2         | 1.56%   |
| Unknown (AAA) LCDTV AAA3393 1360x768 890x500mm 40.2-inch               | 1         | 0.78%   |
| TMX TL142GDXP02-0 TMX1420 2520x1680 300x200mm 14.2-inch                | 1         | 0.78%   |
| Sony TV SNYAB03 1920x1080                                              | 1         | 0.78%   |
| Sharp LQ156T1JW03 SHP1529 2560x1440 344x194mm 15.5-inch                | 1         | 0.78%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                | 1         | 0.78%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                | 1         | 0.78%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch                | 1         | 0.78%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch   | 1         | 0.78%   |
| Samsung Electronics LS24AG30x SAM7178 1920x1080 530x300mm 24.0-inch    | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch   | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch   | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SDC5844 1920x1080 344x194mm 15.5-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SDC414F 3456x2160 288x180mm 13.4-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch   | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 1209x680mm 54.6-inch | 1         | 0.78%   |
| Philips PHL 276B1 PHL0947 2560x1440 597x336mm 27.0-inch                | 1         | 0.78%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 1         | 0.78%   |
| Philips PHL 216V6 PHLC10D 1920x1080 419x262mm 19.5-inch                | 1         | 0.78%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 1         | 0.78%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                | 1         | 0.78%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                | 1         | 0.78%   |
| MStar LCD TV MST9000 1360x768                                          | 1         | 0.78%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch          | 1         | 0.78%   |
| LG Display LCD Monitor LGD0701 1920x1200 345x215mm 16.0-inch           | 1         | 0.78%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch           | 1         | 0.78%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch           | 1         | 0.78%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch           | 1         | 0.78%   |
| LG Display LCD Monitor LGD0542 1920x1080 276x156mm 12.5-inch           | 1         | 0.78%   |
| LG Display LCD Monitor LGD04AF 1366x768 344x194mm 15.5-inch            | 1         | 0.78%   |
| LG Display LCD Monitor LGD045D 1366x768 345x194mm 15.6-inch            | 1         | 0.78%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch            | 1         | 0.78%   |
| LG Display LCD Monitor LGD03D6 1366x768 345x194mm 15.6-inch            | 1         | 0.78%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch            | 1         | 0.78%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 54        | 47.37%  |
| 1366x768 (WXGA)    | 28        | 24.56%  |
| 1920x1200 (WUXGA)  | 6         | 5.26%   |
| 1280x800 (WXGA)    | 4         | 3.51%   |
| 3840x2160 (4K)     | 3         | 2.63%   |
| 2560x1440 (QHD)    | 3         | 2.63%   |
| 1600x900 (HD+)     | 3         | 2.63%   |
| 1440x900 (WXGA+)   | 3         | 2.63%   |
| 1680x1050 (WSXGA+) | 2         | 1.75%   |
| 3456x2160          | 1         | 0.88%   |
| 3440x1440          | 1         | 0.88%   |
| 2880x1800          | 1         | 0.88%   |
| 2560x1600          | 1         | 0.88%   |
| 2560x1080          | 1         | 0.88%   |
| 2520x1680          | 1         | 0.88%   |
| 1920x1280          | 1         | 0.88%   |
| 1360x768           | 1         | 0.88%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 51        | 39.84%  |
| 13      | 24        | 18.75%  |
| 14      | 12        | 9.38%   |
| 23      | 5         | 3.91%   |
| 17      | 5         | 3.91%   |
| 27      | 4         | 3.13%   |
| 24      | 4         | 3.13%   |
| 11      | 4         | 3.13%   |
| 12      | 3         | 2.34%   |
| 40      | 2         | 1.56%   |
| 34      | 2         | 1.56%   |
| 21      | 2         | 1.56%   |
| 16      | 2         | 1.56%   |
| 84      | 1         | 0.78%   |
| 72      | 1         | 0.78%   |
| 60      | 1         | 0.78%   |
| 31      | 1         | 0.78%   |
| 19      | 1         | 0.78%   |
| 18      | 1         | 0.78%   |
| 10      | 1         | 0.78%   |
| Unknown | 1         | 0.78%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 76        | 59.38%  |
| 201-300     | 20        | 15.63%  |
| 501-600     | 11        | 8.59%   |
| 351-400     | 6         | 4.69%   |
| 401-500     | 5         | 3.91%   |
| 801-900     | 2         | 1.56%   |
| 701-800     | 2         | 1.56%   |
| 601-700     | 2         | 1.56%   |
| 1501-2000   | 2         | 1.56%   |
| 1001-1500   | 1         | 0.78%   |
| Unknown     | 1         | 0.78%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 89        | 78.76%  |
| 16/10 | 19        | 16.81%  |
| 3/2   | 3         | 2.65%   |
| 21/9  | 2         | 1.77%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 51        | 39.84%  |
| 81-90          | 29        | 22.66%  |
| 201-250        | 9         | 7.03%   |
| 71-80          | 6         | 4.69%   |
| 51-60          | 4         | 3.13%   |
| 301-350        | 4         | 3.13%   |
| 121-130        | 4         | 3.13%   |
| More than 1000 | 3         | 2.34%   |
| 61-70          | 3         | 2.34%   |
| 351-500        | 3         | 2.34%   |
| 151-200        | 2         | 1.56%   |
| 111-120        | 2         | 1.56%   |
| 501-1000       | 2         | 1.56%   |
| 41-50          | 1         | 0.78%   |
| 251-300        | 1         | 0.78%   |
| 141-150        | 1         | 0.78%   |
| 131-140        | 1         | 0.78%   |
| 91-100         | 1         | 0.78%   |
| Unknown        | 1         | 0.78%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 57        | 44.53%  |
| 101-120       | 30        | 23.44%  |
| 51-100        | 18        | 14.06%  |
| 161-240       | 14        | 10.94%  |
| More than 240 | 4         | 3.13%   |
| 1-50          | 4         | 3.13%   |
| Unknown       | 1         | 0.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 83        | 76.15%  |
| 2     | 24        | 22.02%  |
| 0     | 2         | 1.83%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 59        | 34.3%   |
| Intel                 | 58        | 33.72%  |
| Qualcomm Atheros      | 16        | 9.3%    |
| Broadcom              | 11        | 6.4%    |
| MediaTek              | 7         | 4.07%   |
| ASIX Electronics      | 4         | 2.33%   |
| Xiaomi                | 2         | 1.16%   |
| Hewlett-Packard       | 2         | 1.16%   |
| DisplayLink           | 2         | 1.16%   |
| Broadcom Limited      | 2         | 1.16%   |
| TP-Link               | 1         | 0.58%   |
| Sierra Wireless       | 1         | 0.58%   |
| Samsung Electronics   | 1         | 0.58%   |
| Ralink                | 1         | 0.58%   |
| Nvidia                | 1         | 0.58%   |
| Lenovo                | 1         | 0.58%   |
| JMicron Technology    | 1         | 0.58%   |
| Huawei Technologies   | 1         | 0.58%   |
| FIBOCOM               | 1         | 0.58%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 33        | 16.1%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 12        | 5.85%   |
| Intel Wi-Fi 6 AX201                                                     | 9         | 4.39%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 3.9%    |
| Intel Wireless 8265 / 8275                                              | 7         | 3.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 6         | 2.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 2.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.95%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 1.95%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 1.95%   |
| Intel Wireless 8260                                                     | 4         | 1.95%   |
| Intel Ethernet Connection (4) I219-LM                                   | 4         | 1.95%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.95%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 1.95%   |
| ASIX AX88179 Gigabit Ethernet                                           | 4         | 1.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.46%   |
| Intel Ethernet Connection I219-V                                        | 3         | 1.46%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 3         | 1.46%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 3         | 1.46%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 2         | 0.98%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.98%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 2         | 0.98%   |
| Realtek 802.11n WLAN Adapter                                            | 2         | 0.98%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.98%   |
| Intel Wireless 7265                                                     | 2         | 0.98%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 2         | 0.98%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 0.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 0.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 0.98%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 0.98%   |
| DisplayLink Dell Universal Dock D6000                                   | 2         | 0.98%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1         | 0.49%   |
| Sierra Wireless EM7455                                                  | 1         | 0.49%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 0.49%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.49%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.49%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.49%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.49%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.49%   |
| Realtek RTL8125 2.5GbE Controller                                       | 1         | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 57        | 51.35%  |
| Realtek Semiconductor | 16        | 14.41%  |
| Qualcomm Atheros      | 14        | 12.61%  |
| Broadcom              | 11        | 9.91%   |
| MediaTek              | 7         | 6.31%   |
| TP-Link               | 1         | 0.9%    |
| Sierra Wireless       | 1         | 0.9%    |
| Ralink                | 1         | 0.9%    |
| Hewlett-Packard       | 1         | 0.9%    |
| FIBOCOM               | 1         | 0.9%    |
| Broadcom Limited      | 1         | 0.9%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                     | 9         | 8.11%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 7.21%   |
| Intel Wireless 8265 / 8275                                              | 7         | 6.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 4.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 3.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 3.6%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 3.6%    |
| Intel Wireless 8260                                                     | 4         | 3.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 3.6%    |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 3.6%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2.7%    |
| Broadcom BCM4331 802.11a/b/g/n                                          | 3         | 2.7%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.8%    |
| Realtek 802.11n WLAN Adapter                                            | 2         | 1.8%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.8%    |
| Intel Wireless 7265                                                     | 2         | 1.8%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 2         | 1.8%    |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 1.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.8%    |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 1.8%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1         | 0.9%    |
| Sierra Wireless EM7455                                                  | 1         | 0.9%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.9%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.9%    |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.9%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.9%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.9%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.9%    |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                       | 1         | 0.9%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 0.9%    |
| MediaTek 802.11 n WLAN                                                  | 1         | 0.9%    |
| Intel Wireless 7260                                                     | 1         | 0.9%    |
| Intel Wireless 3165                                                     | 1         | 0.9%    |
| Intel Wireless 3160                                                     | 1         | 0.9%    |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 0.9%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 1         | 0.9%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 53        | 58.24%  |
| Intel                 | 17        | 18.68%  |
| Broadcom              | 5         | 5.49%   |
| ASIX Electronics      | 4         | 4.4%    |
| Xiaomi                | 2         | 2.2%    |
| Qualcomm Atheros      | 2         | 2.2%    |
| DisplayLink           | 2         | 2.2%    |
| Samsung Electronics   | 1         | 1.1%    |
| Nvidia                | 1         | 1.1%    |
| Lenovo                | 1         | 1.1%    |
| JMicron Technology    | 1         | 1.1%    |
| Hewlett-Packard       | 1         | 1.1%    |
| Broadcom Limited      | 1         | 1.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 33        | 35.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 12        | 12.9%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 6         | 6.45%   |
| Intel Ethernet Connection (4) I219-LM                                  | 4         | 4.3%    |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 4.3%    |
| Intel Ethernet Connection I219-V                                       | 3         | 3.23%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 3.23%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2         | 2.15%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 2.15%   |
| DisplayLink Dell Universal Dock D6000                                  | 2         | 2.15%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 1.08%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 1.08%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 1         | 1.08%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 1.08%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 1.08%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 1.08%   |
| Lenovo ThinkPad Lan                                                    | 1         | 1.08%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 1.08%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 1.08%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 1.08%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 1.08%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 1.08%   |
| Intel Ethernet Connection (16) I219-LM                                 | 1         | 1.08%   |
| Intel Ethernet Connection (14) I219-LM                                 | 1         | 1.08%   |
| Intel Ethernet Connection (10) I219-V                                  | 1         | 1.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 1         | 1.08%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 1.08%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 1.08%   |
| HP lt4120 Snapdragon X5 LTE                                            | 1         | 1.08%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 1         | 1.08%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 1.08%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe               | 1         | 1.08%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 106       | 55.21%  |
| Ethernet | 85        | 44.27%  |
| Modem    | 1         | 0.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 91        | 81.25%  |
| Ethernet | 21        | 18.75%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 74        | 68.52%  |
| 1     | 29        | 26.85%  |
| 0     | 5         | 4.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 73        | 65.77%  |
| Yes  | 38        | 34.23%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 49        | 52.69%  |
| Realtek Semiconductor           | 8         | 8.6%    |
| Qualcomm Atheros Communications | 8         | 8.6%    |
| Broadcom                        | 7         | 7.53%   |
| IMC Networks                    | 6         | 6.45%   |
| Apple                           | 6         | 6.45%   |
| Dell                            | 2         | 2.15%   |
| Smart Modular Technologies      | 1         | 1.08%   |
| Realtek                         | 1         | 1.08%   |
| Ralink                          | 1         | 1.08%   |
| MediaTek                        | 1         | 1.08%   |
| Hewlett-Packard                 | 1         | 1.08%   |
| Foxconn International           | 1         | 1.08%   |
| Foxconn / Hon Hai               | 1         | 1.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                              | 15        | 16.13%  |
| Intel Bluetooth Device                             | 9         | 9.68%   |
| Intel AX200 Bluetooth                              | 8         | 8.6%    |
| Intel Bluetooth wireless interface                 | 6         | 6.45%   |
| Qualcomm Atheros  Bluetooth Device                 | 5         | 5.38%   |
| Realtek Bluetooth Radio                            | 4         | 4.3%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 4         | 4.3%    |
| IMC Networks Wireless_Device                       | 4         | 4.3%    |
| Apple Bluetooth Host Controller                    | 4         | 4.3%    |
| Realtek 802.11ac WLAN Adapter                      | 2         | 2.15%   |
| Intel AX211 Bluetooth                              | 2         | 2.15%   |
| Intel AX210 Bluetooth                              | 2         | 2.15%   |
| Dell DW375 Bluetooth Module                        | 2         | 2.15%   |
| Apple Bluetooth USB Host Controller                | 2         | 2.15%   |
| Smart Modular Bluetooth Device                     | 1         | 1.08%   |
| Realtek RTL8821A Bluetooth                         | 1         | 1.08%   |
| Realtek RTL8723B Bluetooth                         | 1         | 1.08%   |
| Realtek Bluetooth Radio                            | 1         | 1.08%   |
| Ralink RT3290 Bluetooth                            | 1         | 1.08%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0             | 1         | 1.08%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0              | 1         | 1.08%   |
| Qualcomm Atheros AR3012 Bluetooth                  | 1         | 1.08%   |
| MediaTek Wireless_Device                           | 1         | 1.08%   |
| Intel Wireless-AC 9260 Bluetooth Adapter           | 1         | 1.08%   |
| Intel Wireless-AC 3168 Bluetooth                   | 1         | 1.08%   |
| Intel Centrino Bluetooth Wireless Transceiver      | 1         | 1.08%   |
| IMC Networks Bluetooth Radio                       | 1         | 1.08%   |
| IMC Networks Atheros AR3012 Bluetooth              | 1         | 1.08%   |
| HP Broadcom 2070 Bluetooth Combo                   | 1         | 1.08%   |
| Foxconn International BCM43142A0 Bluetooth module  | 1         | 1.08%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth        | 1         | 1.08%   |
| Broadcom HP Portable Bumble Bee                    | 1         | 1.08%   |
| Broadcom BCM43142A0 Bluetooth Device               | 1         | 1.08%   |
| Broadcom BCM43142A0 Bluetooth 4.0                  | 1         | 1.08%   |
| Broadcom BCM43142 Bluetooth 4.0                    | 1         | 1.08%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR               | 1         | 1.08%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 1.08%   |
| Broadcom BCM2045B (BDC-2.1)                        | 1         | 1.08%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 87        | 69.6%   |
| AMD                    | 19        | 15.2%   |
| Nvidia                 | 13        | 10.4%   |
| Plantronics            | 1         | 0.8%    |
| Logitech               | 1         | 0.8%    |
| LINE TECH INDUSTRIAL   | 1         | 0.8%    |
| DSEA A/S               | 1         | 0.8%    |
| Arturia                | 1         | 0.8%    |
| AKAI Professional M.I. | 1         | 0.8%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 17        | 11.26%  |
| AMD Family 17h/19h HD Audio Controller                                     | 14        | 9.27%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 12        | 7.95%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 10        | 6.62%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 7         | 4.64%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 3.97%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 3.31%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 2.65%   |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 2.65%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 2.65%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 2.65%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 1.99%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 1.99%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 1.99%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 1.99%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 1.99%   |
| AMD FCH Azalia Controller                                                  | 3         | 1.99%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 1.32%   |
| Nvidia GT216 HDMI Audio Controller                                         | 2         | 1.32%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 1.32%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 1.32%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 2         | 1.32%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.32%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 1.32%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 1.32%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 1.32%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 1.32%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.32%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 1.32%   |
| Plantronics Plantronics Blackwire 3225 Series                              | 1         | 0.66%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.66%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.66%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.66%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.66%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.66%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.66%   |
| Nvidia Audio device                                                        | 1         | 0.66%   |
| Logitech Logitech G PRO X Gaming Headset                                   | 1         | 0.66%   |
| LINE TECH INDUSTRIAL YTL HEADSET                                           | 1         | 0.66%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 28        | 35.44%  |
| SK hynix            | 20        | 25.32%  |
| Kingston            | 8         | 10.13%  |
| Micron Technology   | 6         | 7.59%   |
| Unknown (ABCD)      | 3         | 3.8%    |
| Elpida              | 3         | 3.8%    |
| Ramaxel Technology  | 2         | 2.53%   |
| Unknown             | 1         | 1.27%   |
| Teikon              | 1         | 1.27%   |
| Magnum Tech         | 1         | 1.27%   |
| ff                  | 1         | 1.27%   |
| fef5                | 1         | 1.27%   |
| ChangXin Memory     | 1         | 1.27%   |
| A-DATA Technology   | 1         | 1.27%   |
| 8945000080AD        | 1         | 1.27%   |
| 4ea5                | 1         | 1.27%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 4         | 4.82%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 3.61%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 3         | 3.61%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 2.41%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 2.41%   |
| Samsung RAM M471A2G44BM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 2.41%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 2.41%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 2.41%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 2         | 2.41%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 1         | 1.2%    |
| Teikon RAM TMT41GS6BFR8A-PBHJ 8GB SODIMM DDR3 1600MT/s           | 1         | 1.2%    |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.2%    |
| SK hynix RAM Module 4GB SODIMM DDR4 2133MT/s                     | 1         | 1.2%    |
| SK hynix RAM Module 2GB Row Of Chips LPDDR5 6400MT/s             | 1         | 1.2%    |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 1         | 1.2%    |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.2%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.2%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB Chip DDR3 1600MT/s             | 1         | 1.2%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.2%    |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.2%    |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.2%    |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.2%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.2%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 1.2%    |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 1         | 1.2%    |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s       | 1         | 1.2%    |
| SK hynix RAM H9HCNNN8KUMLHR-NME 1GB LPDDR4 2400MT/s              | 1         | 1.2%    |
| SK hynix RAM H9HCNNN8KUMLHR 1GB 2400MT/s                         | 1         | 1.2%    |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 1.2%    |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 1         | 1.2%    |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 1.2%    |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 1.2%    |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 1.2%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 1         | 1.2%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.2%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.2%    |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 1.2%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.2%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.2%    |
| Samsung RAM M471A5143SB1-CRC 4GB SODIMM DDR4 2400MT/s            | 1         | 1.2%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 36        | 55.38%  |
| DDR3    | 15        | 23.08%  |
| LPDDR4  | 10        | 15.38%  |
| SDRAM   | 1         | 1.54%   |
| LPDDR5  | 1         | 1.54%   |
| LPDDR3  | 1         | 1.54%   |
| Unknown | 1         | 1.54%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 55        | 84.62%  |
| Row Of Chips | 6         | 9.23%   |
| Unknown      | 3         | 4.62%   |
| Chip         | 1         | 1.54%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 28        | 42.42%  |
| 4096  | 13        | 19.7%   |
| 16384 | 10        | 15.15%  |
| 32768 | 6         | 9.09%   |
| 2048  | 6         | 9.09%   |
| 1024  | 3         | 4.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 19        | 27.14%  |
| 2667  | 12        | 17.14%  |
| 1600  | 12        | 17.14%  |
| 2400  | 10        | 14.29%  |
| 2133  | 3         | 4.29%   |
| 4267  | 2         | 2.86%   |
| 1334  | 2         | 2.86%   |
| 1333  | 2         | 2.86%   |
| 6400  | 1         | 1.43%   |
| 4266  | 1         | 1.43%   |
| 4199  | 1         | 1.43%   |
| 3733  | 1         | 1.43%   |
| 3266  | 1         | 1.43%   |
| 1867  | 1         | 1.43%   |
| 1067  | 1         | 1.43%   |
| 1066  | 1         | 1.43%   |

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
| Chicony Electronics                    | 31        | 32.29%  |
| IMC Networks                           | 9         | 9.38%   |
| Realtek Semiconductor                  | 8         | 8.33%   |
| Bison Electronics                      | 7         | 7.29%   |
| Microdia                               | 6         | 6.25%   |
| Sunplus Innovation Technology          | 5         | 5.21%   |
| Quanta                                 | 5         | 5.21%   |
| Apple                                  | 5         | 5.21%   |
| Luxvisions Innotech Limited            | 4         | 4.17%   |
| Syntek                                 | 3         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.08%   |
| Suyin                                  | 1         | 1.04%   |
| Silicon Motion                         | 1         | 1.04%   |
| ShineTech                              | 1         | 1.04%   |
| Samsung Electronics                    | 1         | 1.04%   |
| Qtech                                  | 1         | 1.04%   |
| Polycom                                | 1         | 1.04%   |
| Pixart Imaging                         | 1         | 1.04%   |
| Logitech                               | 1         | 1.04%   |
| ALi                                    | 1         | 1.04%   |
| Alcor Micro                            | 1         | 1.04%   |
| Unknown                                | 1         | 1.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam        | 4         | 4.17%   |
| Chicony USB2.0 Camera                    | 4         | 4.17%   |
| Chicony Integrated Camera                | 4         | 4.17%   |
| Chicony HP HD Camera                     | 4         | 4.17%   |
| Quanta USB2.0 HD UVC WebCam              | 3         | 3.13%   |
| Microdia Integrated_Webcam_HD            | 3         | 3.13%   |
| IMC Networks Integrated Camera           | 3         | 3.13%   |
| Chicony Integrated IR Camera             | 3         | 3.13%   |
| Chicony HD Webcam                        | 3         | 3.13%   |
| Bison SunplusIT Integrated Camera        | 3         | 3.13%   |
| Apple FaceTime HD Camera                 | 3         | 3.13%   |
| Syntek Integrated Camera                 | 2         | 2.08%   |
| Realtek USB Camera                       | 2         | 2.08%   |
| Realtek Integrated_Webcam_HD             | 2         | 2.08%   |
| Luxvisions Innotech Limited HP HD Camera | 2         | 2.08%   |
| Chicony USB2.0 VGA UVC WebCam            | 2         | 2.08%   |
| Bison EasyCamera                         | 2         | 2.08%   |
| Apple Built-in iSight                    | 2         | 2.08%   |
| Syntek Lenovo EasyCamera                 | 1         | 1.04%   |
| Suyin HP Truevision HD                   | 1         | 1.04%   |
| Sunplus PC Camera                        | 1         | 1.04%   |
| Sunplus Laptop_Integrated_Webcam_FHD     | 1         | 1.04%   |
| Sunplus Integrated_Webcam_HD             | 1         | 1.04%   |
| Sunplus HD WebCam                        | 1         | 1.04%   |
| Sunplus 5Mega Webcam                     | 1         | 1.04%   |
| Silicon Motion 300k Pixel Camera         | 1         | 1.04%   |
| ShineTech USB2.0 HD UVC WebCam           | 1         | 1.04%   |
| Samsung Galaxy series, misc. (MTP mode)  | 1         | 1.04%   |
| Realtek USB2.0 HD UVC WebCam             | 1         | 1.04%   |
| Realtek Lenovo EasyCamera                | 1         | 1.04%   |
| Realtek Integrated Webcam HD             | 1         | 1.04%   |
| Realtek Integrated Webcam                | 1         | 1.04%   |
| Quanta HP Wide Vision HD Camera          | 1         | 1.04%   |
| Quanta HP Webcam                         | 1         | 1.04%   |
| Qtech USB Camera                         | 1         | 1.04%   |
| Polycom Poly Studio P5 webcam            | 1         | 1.04%   |
| Pixart Imaging USB_2.0_Webcam            | 1         | 1.04%   |
| Microdia Lenovo EasyCamera               | 1         | 1.04%   |
| Microdia Integrated_Webcam_FHD           | 1         | 1.04%   |
| Microdia Integrated Webcam HD            | 1         | 1.04%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 9         | 37.5%   |
| Validity Sensors           | 8         | 33.33%  |
| Shenzhen Goodix Technology | 5         | 20.83%  |
| LighTuning Technology      | 1         | 4.17%   |
| Elan Microelectronics      | 1         | 4.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                | 4         | 16.67%  |
| Shenzhen Goodix  Fingerprint Device                       | 3         | 12.5%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 2         | 8.33%   |
| Validity Sensors VFS301 Fingerprint Reader                | 1         | 4.17%   |
| Validity Sensors VFS 5011 fingerprint sensor              | 1         | 4.17%   |
| Validity Sensors Synaptics WBDI                           | 1         | 4.17%   |
| Validity Sensors Swipe Fingerprint Sensor                 | 1         | 4.17%   |
| Synaptics UWP WBDI Device                                 | 1         | 4.17%   |
| Synaptics TouchPad                                        | 1         | 4.17%   |
| Synaptics  WBDI                                           | 1         | 4.17%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 4.17%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 4.17%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 4.17%   |
| Shenzhen Goodix Fingerprint Reader                        | 1         | 4.17%   |
| Shenzhen Goodix FingerPrint                               | 1         | 4.17%   |
| LighTuning ES603 Swipe Fingerprint Sensor                 | 1         | 4.17%   |
| Elan ELAN:Fingerprint                                     | 1         | 4.17%   |
| Unknown                                                   | 1         | 4.17%   |

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
| 0     | 64        | 58.72%  |
| 1     | 33        | 30.28%  |
| 2     | 9         | 8.26%   |
| 3     | 2         | 1.83%   |
| 7     | 1         | 0.92%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 23        | 39.66%  |
| Net/wireless             | 6         | 10.34%  |
| Graphics card            | 6         | 10.34%  |
| Chipcard                 | 5         | 8.62%   |
| Multimedia controller    | 4         | 6.9%    |
| Communication controller | 4         | 6.9%    |
| Camera                   | 4         | 6.9%    |
| Sound                    | 2         | 3.45%   |
| Card reader              | 2         | 3.45%   |
| Bluetooth                | 2         | 3.45%   |


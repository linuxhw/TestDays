Ubuntu Budgie 22.04 - Tested Hardware & Statistics
--------------------------------------------------

A project to collect tested hardware configurations for Ubuntu Budgie 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_Budgie_22.04/Desktop/README.md) and [notebooks](/Dist/Ubuntu_Budgie_22.04/Notebook/README.md).

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

Total: 250

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | A88X-PRO                    | Desktop     | [0e0bc97fa5](https://linux-hardware.org/?probe=0e0bc97fa5) | Dec 17, 2024 |
| ASUSTek       | UX303UA                     | Notebook    | [7151dfd4cb](https://linux-hardware.org/?probe=7151dfd4cb) | Oct 11, 2024 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | Notebook    | [05af8a3249](https://linux-hardware.org/?probe=05af8a3249) | Oct 10, 2024 |
| ASUSTek       | K52Jc                       | Notebook    | [364a24826b](https://linux-hardware.org/?probe=364a24826b) | Sep 29, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1402CBA... | Notebook    | [7e49febc40](https://linux-hardware.org/?probe=7e49febc40) | Sep 27, 2024 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [df83d2c6b4](https://linux-hardware.org/?probe=df83d2c6b4) | Sep 26, 2024 |
| ASUSTek       | UX303UA                     | Notebook    | [8cb4bb7e08](https://linux-hardware.org/?probe=8cb4bb7e08) | Sep 20, 2024 |
| Dell          | XPS 13 9370                 | Notebook    | [f77ada41b7](https://linux-hardware.org/?probe=f77ada41b7) | Sep 08, 2024 |
| Dell          | XPS 15 7590                 | Notebook    | [fc9e70c2da](https://linux-hardware.org/?probe=fc9e70c2da) | Aug 29, 2024 |
| Dell          | XPS 13 9370                 | Notebook    | [b1e23bca9e](https://linux-hardware.org/?probe=b1e23bca9e) | Aug 26, 2024 |
| ASUSTek       | A88X-PRO                    | Desktop     | [6c5b4b865c](https://linux-hardware.org/?probe=6c5b4b865c) | Aug 21, 2024 |
| ASUSTek       | A88X-PRO                    | Desktop     | [0d6421bb24](https://linux-hardware.org/?probe=0d6421bb24) | Aug 21, 2024 |
| ASUSTek       | H81T                        | Desktop     | [db12bb8871](https://linux-hardware.org/?probe=db12bb8871) | Aug 03, 2024 |
| ASUSTek       | X555LAB                     | Notebook    | [d81c85d9d6](https://linux-hardware.org/?probe=d81c85d9d6) | Jun 20, 2024 |
| Lenovo        | G50-45 80E3                 | Notebook    | [55945040da](https://linux-hardware.org/?probe=55945040da) | May 09, 2024 |
| HP            | Pavilion dv8                | Notebook    | [24eb3d99a9](https://linux-hardware.org/?probe=24eb3d99a9) | Apr 11, 2024 |
| Chuwi         | X312B                       | Notebook    | [3623330a1c](https://linux-hardware.org/?probe=3623330a1c) | Apr 09, 2024 |
| Chuwi         | X312B                       | Notebook    | [5aa107f741](https://linux-hardware.org/?probe=5aa107f741) | Apr 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [7bb2773966](https://linux-hardware.org/?probe=7bb2773966) | Apr 05, 2024 |
| Lenovo        | G50-45 80E3                 | Notebook    | [297eab2023](https://linux-hardware.org/?probe=297eab2023) | Mar 31, 2024 |
| Google        | Bobba                       | Notebook    | [d69b117fd0](https://linux-hardware.org/?probe=d69b117fd0) | Mar 30, 2024 |
| Lenovo        | 1059 SDK0T76530 WIN 3556... | Desktop     | [39db39fb8a](https://linux-hardware.org/?probe=39db39fb8a) | Mar 30, 2024 |
| HP            | Dragonfly 13.5 inch G4 N... | Notebook    | [4b22ed6279](https://linux-hardware.org/?probe=4b22ed6279) | Mar 29, 2024 |
| Packard Be... | EasyNote TM98               | Notebook    | [e6c48ef91f](https://linux-hardware.org/?probe=e6c48ef91f) | Mar 22, 2024 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | Notebook    | [d337b27afc](https://linux-hardware.org/?probe=d337b27afc) | Mar 21, 2024 |
| HP            | 8058                        | All in one  | [2a0c07d92f](https://linux-hardware.org/?probe=2a0c07d92f) | Mar 18, 2024 |
| HP            | ProBook 450 G1              | Notebook    | [3bfd1620fe](https://linux-hardware.org/?probe=3bfd1620fe) | Mar 12, 2024 |
| Winnovo       | TaBook                      | Convertible | [e98a415190](https://linux-hardware.org/?probe=e98a415190) | Mar 08, 2024 |
| PCWare        | APM-A320G                   | Desktop     | [15ddb5b3fd](https://linux-hardware.org/?probe=15ddb5b3fd) | Feb 29, 2024 |
| Apple         | MacBookPro6,2               | Notebook    | [a3b8064ddf](https://linux-hardware.org/?probe=a3b8064ddf) | Feb 29, 2024 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [4963c40308](https://linux-hardware.org/?probe=4963c40308) | Feb 27, 2024 |
| Apple         | MacBookPro6,2               | Notebook    | [fd9e5de8cf](https://linux-hardware.org/?probe=fd9e5de8cf) | Feb 22, 2024 |
| Dell          | Vostro 5625                 | Notebook    | [04e53619c6](https://linux-hardware.org/?probe=04e53619c6) | Feb 19, 2024 |
| TUXEDO        | InfinityBook_Pro13_14_v4    | Notebook    | [4264042062](https://linux-hardware.org/?probe=4264042062) | Feb 18, 2024 |
| HP            | 8169                        | Desktop     | [8aadb502eb](https://linux-hardware.org/?probe=8aadb502eb) | Feb 13, 2024 |
| HP            | 15                          | Notebook    | [ef0b519e9b](https://linux-hardware.org/?probe=ef0b519e9b) | Feb 12, 2024 |
| MSI           | B450M GAMING PLUS           | Desktop     | [093c937aa6](https://linux-hardware.org/?probe=093c937aa6) | Feb 07, 2024 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [c80a1f64fc](https://linux-hardware.org/?probe=c80a1f64fc) | Jan 18, 2024 |
| Toshiba       | Satellite C855D-11X         | Notebook    | [d047649166](https://linux-hardware.org/?probe=d047649166) | Jan 14, 2024 |
| Alurin        | ALU-LPT-N4020-8256-140      | Notebook    | [61fdeffbaf](https://linux-hardware.org/?probe=61fdeffbaf) | Jan 12, 2024 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [66efe29bec](https://linux-hardware.org/?probe=66efe29bec) | Jan 11, 2024 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | Notebook    | [0bc6f72a01](https://linux-hardware.org/?probe=0bc6f72a01) | Jan 09, 2024 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [cce2fde2ac](https://linux-hardware.org/?probe=cce2fde2ac) | Jan 08, 2024 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | Notebook    | [fd3f275cfb](https://linux-hardware.org/?probe=fd3f275cfb) | Jan 07, 2024 |
| Apple         | MacBookPro8,3               | Notebook    | [b1467995b6](https://linux-hardware.org/?probe=b1467995b6) | Jan 06, 2024 |
| MSI           | A68HM-E33 V2                | Desktop     | [462cb61dd3](https://linux-hardware.org/?probe=462cb61dd3) | Jan 05, 2024 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [03e7ada99a](https://linux-hardware.org/?probe=03e7ada99a) | Jan 04, 2024 |
| MSI           | B450M PRO-VDH V2            | Desktop     | [7efa5db123](https://linux-hardware.org/?probe=7efa5db123) | Dec 29, 2023 |
| Lenovo        | ThinkPad X220 4291G75       | Notebook    | [1192d8e746](https://linux-hardware.org/?probe=1192d8e746) | Dec 27, 2023 |
| Lenovo        | ThinkPad X220 4291G75       | Notebook    | [3fdb3a1cc7](https://linux-hardware.org/?probe=3fdb3a1cc7) | Dec 27, 2023 |
| Toshiba       | Satellite A300              | Notebook    | [5e373b58ac](https://linux-hardware.org/?probe=5e373b58ac) | Dec 15, 2023 |
| ASUSTek       | E403SA                      | Notebook    | [141030490c](https://linux-hardware.org/?probe=141030490c) | Dec 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [ddfffa5172](https://linux-hardware.org/?probe=ddfffa5172) | Dec 08, 2023 |
| Lenovo        | ThinkPad X260 20F5S0V500    | Notebook    | [a293b54992](https://linux-hardware.org/?probe=a293b54992) | Nov 24, 2023 |
| Toshiba       | STI 010433                  | Desktop     | [c172f735d2](https://linux-hardware.org/?probe=c172f735d2) | Nov 15, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [5efa262121](https://linux-hardware.org/?probe=5efa262121) | Nov 14, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [51f7d5e2dc](https://linux-hardware.org/?probe=51f7d5e2dc) | Nov 09, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [0a23b4526a](https://linux-hardware.org/?probe=0a23b4526a) | Nov 09, 2023 |
| Lenovo        | ThinkPad X260 20F5S0V500    | Notebook    | [143fa66e87](https://linux-hardware.org/?probe=143fa66e87) | Nov 08, 2023 |
| HONOR         | GLO-GXXX                    | Notebook    | [c6d6619fd9](https://linux-hardware.org/?probe=c6d6619fd9) | Nov 06, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [2ac9878b30](https://linux-hardware.org/?probe=2ac9878b30) | Nov 05, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [532db79d07](https://linux-hardware.org/?probe=532db79d07) | Nov 05, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [a816b34b9e](https://linux-hardware.org/?probe=a816b34b9e) | Nov 03, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [e1edc2410b](https://linux-hardware.org/?probe=e1edc2410b) | Nov 03, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [41f9f44ee1](https://linux-hardware.org/?probe=41f9f44ee1) | Oct 20, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [98f1b28357](https://linux-hardware.org/?probe=98f1b28357) | Oct 20, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [b3a6489f94](https://linux-hardware.org/?probe=b3a6489f94) | Oct 20, 2023 |
| HP            | 8054                        | Desktop     | [66ad5550d1](https://linux-hardware.org/?probe=66ad5550d1) | Oct 10, 2023 |
| ASUSTek       | UX303UA                     | Notebook    | [657233bb53](https://linux-hardware.org/?probe=657233bb53) | Oct 02, 2023 |
| COM1          | NBINF-X5-9G5                | Notebook    | [919d36ddd8](https://linux-hardware.org/?probe=919d36ddd8) | Sep 24, 2023 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [9a1d56bda1](https://linux-hardware.org/?probe=9a1d56bda1) | Sep 20, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [01e90212e5](https://linux-hardware.org/?probe=01e90212e5) | Sep 20, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [6588973c54](https://linux-hardware.org/?probe=6588973c54) | Sep 19, 2023 |
| Dell          | Latitude 7280               | Notebook    | [ecca4887d5](https://linux-hardware.org/?probe=ecca4887d5) | Sep 15, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [40c7e7f27b](https://linux-hardware.org/?probe=40c7e7f27b) | Aug 31, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [f09b86405b](https://linux-hardware.org/?probe=f09b86405b) | Aug 26, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [044deb0ad2](https://linux-hardware.org/?probe=044deb0ad2) | Aug 22, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [921d699e5d](https://linux-hardware.org/?probe=921d699e5d) | Aug 19, 2023 |
| ASUSTek       | UX303UA                     | Notebook    | [a34dfca1e3](https://linux-hardware.org/?probe=a34dfca1e3) | Aug 14, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [15fb5d0baf](https://linux-hardware.org/?probe=15fb5d0baf) | Aug 04, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [e97688a8c1](https://linux-hardware.org/?probe=e97688a8c1) | Jul 27, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [7466fce2a2](https://linux-hardware.org/?probe=7466fce2a2) | Jul 18, 2023 |
| Gigabyte      | H410M S2H V3                | Desktop     | [e31d121593](https://linux-hardware.org/?probe=e31d121593) | Jul 15, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [cabc9a2940](https://linux-hardware.org/?probe=cabc9a2940) | Jul 15, 2023 |
| Gigabyte      | H410M S2H V3                | Desktop     | [9c3135decf](https://linux-hardware.org/?probe=9c3135decf) | Jul 10, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [ce4fed4466](https://linux-hardware.org/?probe=ce4fed4466) | Jul 08, 2023 |
| Lenovo        | ThinkPad X260 20F5S0V500    | Notebook    | [760a6712db](https://linux-hardware.org/?probe=760a6712db) | Jul 07, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [95fa9e14bf](https://linux-hardware.org/?probe=95fa9e14bf) | Jul 07, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [aae865deb7](https://linux-hardware.org/?probe=aae865deb7) | Jul 02, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [89db1a9656](https://linux-hardware.org/?probe=89db1a9656) | Jul 02, 2023 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [0e9e13c4b5](https://linux-hardware.org/?probe=0e9e13c4b5) | Jul 02, 2023 |
| BANGHO        | BES G0304                   | Notebook    | [7b9e2a7570](https://linux-hardware.org/?probe=7b9e2a7570) | Jun 30, 2023 |
| HUAWEI        | HKD-WXX                     | Notebook    | [433d7b4f7e](https://linux-hardware.org/?probe=433d7b4f7e) | Jun 24, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [4622902df7](https://linux-hardware.org/?probe=4622902df7) | Jun 17, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [f04b28a0e5](https://linux-hardware.org/?probe=f04b28a0e5) | Jun 10, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [5d75bba35e](https://linux-hardware.org/?probe=5d75bba35e) | Jun 06, 2023 |
| ASUSTek       | UX303UA                     | Notebook    | [41514924ed](https://linux-hardware.org/?probe=41514924ed) | Jun 04, 2023 |
| Gigabyte      | H310M HD2                   | Desktop     | [b28787ecb7](https://linux-hardware.org/?probe=b28787ecb7) | Jun 04, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [d12d9a4fc2](https://linux-hardware.org/?probe=d12d9a4fc2) | May 29, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [9cbdd21a81](https://linux-hardware.org/?probe=9cbdd21a81) | May 28, 2023 |
| Dell          | Latitude 5521               | Notebook    | [b33afe1463](https://linux-hardware.org/?probe=b33afe1463) | May 25, 2023 |
| TUXEDO        | InfinityBook Pro 14 v4      | Notebook    | [51c520b6e6](https://linux-hardware.org/?probe=51c520b6e6) | May 25, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [5a0f8e19ee](https://linux-hardware.org/?probe=5a0f8e19ee) | May 19, 2023 |
| TUXEDO        | InfinityBook Pro 14 v4      | Notebook    | [741d6fe6d2](https://linux-hardware.org/?probe=741d6fe6d2) | May 19, 2023 |
| HP            | Bloog                       | Notebook    | [4673a7630e](https://linux-hardware.org/?probe=4673a7630e) | May 16, 2023 |
| HP            | Bloog                       | Notebook    | [1c91d5ef51](https://linux-hardware.org/?probe=1c91d5ef51) | May 16, 2023 |
| Dell          | Latitude E5420              | Notebook    | [571765685f](https://linux-hardware.org/?probe=571765685f) | May 14, 2023 |
| TUXEDO        | Book XP1511                 | Notebook    | [37a17568a0](https://linux-hardware.org/?probe=37a17568a0) | May 11, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [8a80fd7103](https://linux-hardware.org/?probe=8a80fd7103) | May 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [3198c997b2](https://linux-hardware.org/?probe=3198c997b2) | May 04, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [612ab58d3f](https://linux-hardware.org/?probe=612ab58d3f) | May 02, 2023 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [b3ac75c53e](https://linux-hardware.org/?probe=b3ac75c53e) | Apr 30, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [f87233a295](https://linux-hardware.org/?probe=f87233a295) | Apr 29, 2023 |
| Intel         | H61                         | Desktop     | [b8f0acdf61](https://linux-hardware.org/?probe=b8f0acdf61) | Apr 28, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [090405a4a7](https://linux-hardware.org/?probe=090405a4a7) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [7afa5cded3](https://linux-hardware.org/?probe=7afa5cded3) | Apr 18, 2023 |
| Lenovo        | ThinkPad T480s 20L8SF1X0... | Notebook    | [d567c29052](https://linux-hardware.org/?probe=d567c29052) | Apr 17, 2023 |
| ASUSTek       | UX303UA                     | Notebook    | [6e9b87d6e1](https://linux-hardware.org/?probe=6e9b87d6e1) | Apr 11, 2023 |
| Dell          | Inspiron 3543               | Notebook    | [d714304a67](https://linux-hardware.org/?probe=d714304a67) | Mar 27, 2023 |
| Dell          | Inspiron 3543               | Notebook    | [f733f5b792](https://linux-hardware.org/?probe=f733f5b792) | Mar 27, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [8701ff9985](https://linux-hardware.org/?probe=8701ff9985) | Mar 26, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [03f3f846eb](https://linux-hardware.org/?probe=03f3f846eb) | Mar 24, 2023 |
| Dell          | Latitude 7480               | Notebook    | [0301ad09f6](https://linux-hardware.org/?probe=0301ad09f6) | Mar 23, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [18bf88d413](https://linux-hardware.org/?probe=18bf88d413) | Mar 17, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [d73bb5ec34](https://linux-hardware.org/?probe=d73bb5ec34) | Mar 15, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [a7d30f68b1](https://linux-hardware.org/?probe=a7d30f68b1) | Mar 12, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [d7ed4aaf2c](https://linux-hardware.org/?probe=d7ed4aaf2c) | Mar 11, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [6e97141469](https://linux-hardware.org/?probe=6e97141469) | Mar 10, 2023 |
| ASUSTek       | K52F                        | Notebook    | [8fa6eaf7cf](https://linux-hardware.org/?probe=8fa6eaf7cf) | Mar 10, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [8a70478523](https://linux-hardware.org/?probe=8a70478523) | Mar 06, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [6e08a2dcf9](https://linux-hardware.org/?probe=6e08a2dcf9) | Mar 06, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [e3578290d2](https://linux-hardware.org/?probe=e3578290d2) | Feb 25, 2023 |
| MSI           | X99S SLI PLUS               | Desktop     | [8c6fb84b12](https://linux-hardware.org/?probe=8c6fb84b12) | Feb 09, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [0e931084a7](https://linux-hardware.org/?probe=0e931084a7) | Feb 05, 2023 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [9f812fe2a7](https://linux-hardware.org/?probe=9f812fe2a7) | Feb 02, 2023 |
| Fujitsu       | D3183-A1 S26361-D3183-A1    | Desktop     | [bfb86ee660](https://linux-hardware.org/?probe=bfb86ee660) | Jan 29, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [de3f21b51b](https://linux-hardware.org/?probe=de3f21b51b) | Jan 28, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [329e7b7105](https://linux-hardware.org/?probe=329e7b7105) | Jan 28, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [ee44dc2539](https://linux-hardware.org/?probe=ee44dc2539) | Jan 27, 2023 |
| HP            | ProBook 450 G7              | Notebook    | [1d507a3cdc](https://linux-hardware.org/?probe=1d507a3cdc) | Jan 27, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [831fd897ec](https://linux-hardware.org/?probe=831fd897ec) | Jan 25, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [0c8a9895bd](https://linux-hardware.org/?probe=0c8a9895bd) | Jan 25, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [b3bc8de731](https://linux-hardware.org/?probe=b3bc8de731) | Jan 25, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [7bf2d60c0b](https://linux-hardware.org/?probe=7bf2d60c0b) | Jan 21, 2023 |
| Lenovo        | ThinkStation C20 4263BA7    | Desktop     | [38ff99d952](https://linux-hardware.org/?probe=38ff99d952) | Jan 10, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [a5e1965b89](https://linux-hardware.org/?probe=a5e1965b89) | Jan 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP14... | Convertible | [195eb3e6eb](https://linux-hardware.org/?probe=195eb3e6eb) | Dec 31, 2022 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | Notebook    | [7da34e4f7f](https://linux-hardware.org/?probe=7da34e4f7f) | Dec 14, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [b34265fdbe](https://linux-hardware.org/?probe=b34265fdbe) | Dec 14, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [ea74cd284c](https://linux-hardware.org/?probe=ea74cd284c) | Dec 08, 2022 |
| Fujitsu       | D3348-B2 S26361-D3348-B2    | Desktop     | [4568e83912](https://linux-hardware.org/?probe=4568e83912) | Dec 03, 2022 |
| Fujitsu       | D3348-B2 S26361-D3348-B2    | Desktop     | [2047a872cb](https://linux-hardware.org/?probe=2047a872cb) | Dec 03, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [bdc64a5196](https://linux-hardware.org/?probe=bdc64a5196) | Dec 02, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [615b292682](https://linux-hardware.org/?probe=615b292682) | Dec 01, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [a130766490](https://linux-hardware.org/?probe=a130766490) | Nov 29, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [be7a4a88a1](https://linux-hardware.org/?probe=be7a4a88a1) | Nov 23, 2022 |
| Fujitsu       | D3348-B2 S26361-D3348-B2    | Desktop     | [eabfad66da](https://linux-hardware.org/?probe=eabfad66da) | Nov 22, 2022 |
| Dell          | 0RW199                      | Desktop     | [2a2fa5baf8](https://linux-hardware.org/?probe=2a2fa5baf8) | Nov 20, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [afb716fb12](https://linux-hardware.org/?probe=afb716fb12) | Nov 18, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [0f94a77355](https://linux-hardware.org/?probe=0f94a77355) | Nov 12, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [104082422f](https://linux-hardware.org/?probe=104082422f) | Nov 04, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [2f2963b2fc](https://linux-hardware.org/?probe=2f2963b2fc) | Nov 04, 2022 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [e0a589194b](https://linux-hardware.org/?probe=e0a589194b) | Nov 01, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | Notebook    | [b401e89d9c](https://linux-hardware.org/?probe=b401e89d9c) | Oct 31, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | Notebook    | [4650c9df06](https://linux-hardware.org/?probe=4650c9df06) | Oct 31, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [ed46beadef](https://linux-hardware.org/?probe=ed46beadef) | Oct 30, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [0e8db93a43](https://linux-hardware.org/?probe=0e8db93a43) | Oct 30, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [4055c79756](https://linux-hardware.org/?probe=4055c79756) | Oct 28, 2022 |
| Toshiba       | Satellite A505              | Notebook    | [41dafcbfb9](https://linux-hardware.org/?probe=41dafcbfb9) | Oct 25, 2022 |
| ASUSTek       | X205TA                      | Notebook    | [2da58f110d](https://linux-hardware.org/?probe=2da58f110d) | Oct 24, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [b397c3fd26](https://linux-hardware.org/?probe=b397c3fd26) | Oct 18, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [23c855f88b](https://linux-hardware.org/?probe=23c855f88b) | Oct 17, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [ebe65ec5fa](https://linux-hardware.org/?probe=ebe65ec5fa) | Oct 17, 2022 |
| Dell          | Latitude E5420              | Notebook    | [dcc7463646](https://linux-hardware.org/?probe=dcc7463646) | Oct 16, 2022 |
| Digibras      | NH4CU03                     | Notebook    | [45912a4bae](https://linux-hardware.org/?probe=45912a4bae) | Oct 16, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [3028d439cf](https://linux-hardware.org/?probe=3028d439cf) | Oct 14, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [6def734895](https://linux-hardware.org/?probe=6def734895) | Oct 14, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [f4d09b3dae](https://linux-hardware.org/?probe=f4d09b3dae) | Oct 13, 2022 |
| AXIOO         | Slimbook 13                 | Notebook    | [221b0b500d](https://linux-hardware.org/?probe=221b0b500d) | Oct 09, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [fee12e32e5](https://linux-hardware.org/?probe=fee12e32e5) | Oct 07, 2022 |
| Dell          | Precision 5560              | Notebook    | [168025b691](https://linux-hardware.org/?probe=168025b691) | Oct 03, 2022 |
| Dell          | Latitude E6410              | Notebook    | [98545a1050](https://linux-hardware.org/?probe=98545a1050) | Sep 30, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [55db3c3775](https://linux-hardware.org/?probe=55db3c3775) | Sep 27, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [15d9ea100b](https://linux-hardware.org/?probe=15d9ea100b) | Sep 26, 2022 |
| TUXEDO        | Book BA1510                 | Notebook    | [76a485fe7e](https://linux-hardware.org/?probe=76a485fe7e) | Sep 22, 2022 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | Notebook    | [f185fff0a3](https://linux-hardware.org/?probe=f185fff0a3) | Sep 21, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [5c9688dac8](https://linux-hardware.org/?probe=5c9688dac8) | Sep 19, 2022 |
| Gigabyte      | B75M-D3P                    | Desktop     | [da53115e6b](https://linux-hardware.org/?probe=da53115e6b) | Sep 15, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [1a5358a3c1](https://linux-hardware.org/?probe=1a5358a3c1) | Sep 14, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [fc210ff2c2](https://linux-hardware.org/?probe=fc210ff2c2) | Sep 07, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [19a21d721c](https://linux-hardware.org/?probe=19a21d721c) | Sep 07, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [f42f75038e](https://linux-hardware.org/?probe=f42f75038e) | Sep 03, 2022 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [548332086b](https://linux-hardware.org/?probe=548332086b) | Sep 02, 2022 |
| ASUSTek       | A88X-PRO                    | Desktop     | [922554664a](https://linux-hardware.org/?probe=922554664a) | Aug 25, 2022 |
| Google        | Rabbid                      | Notebook    | [8049c3894c](https://linux-hardware.org/?probe=8049c3894c) | Aug 24, 2022 |
| Intel         | X79M-S                      | Desktop     | [49a7d62fe8](https://linux-hardware.org/?probe=49a7d62fe8) | Aug 18, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [45df8f9be9](https://linux-hardware.org/?probe=45df8f9be9) | Aug 18, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [6974cf32ce](https://linux-hardware.org/?probe=6974cf32ce) | Aug 17, 2022 |
| HP            | 828A                        | Desktop     | [f42b1efd1e](https://linux-hardware.org/?probe=f42b1efd1e) | Aug 17, 2022 |
| TUXEDO        | Book XUX7 Gen11             | Notebook    | [ecf8be45de](https://linux-hardware.org/?probe=ecf8be45de) | Aug 16, 2022 |
| TUXEDO        | Book XUX7 Gen11             | Notebook    | [c5c7e42e91](https://linux-hardware.org/?probe=c5c7e42e91) | Aug 16, 2022 |
| Biostar       | A960D+V3                    | Desktop     | [83f7f840b7](https://linux-hardware.org/?probe=83f7f840b7) | Aug 15, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [a6aba67197](https://linux-hardware.org/?probe=a6aba67197) | Aug 02, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [fae724727b](https://linux-hardware.org/?probe=fae724727b) | Aug 02, 2022 |
| Dell          | Inspiron 3793               | Notebook    | [15f2e25089](https://linux-hardware.org/?probe=15f2e25089) | Jul 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [e82d2e1076](https://linux-hardware.org/?probe=e82d2e1076) | Jul 28, 2022 |
| Intel         | STK1A32SC H95551-301        | Desktop     | [ea91c7805d](https://linux-hardware.org/?probe=ea91c7805d) | Jul 22, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [e34f81fcfa](https://linux-hardware.org/?probe=e34f81fcfa) | Jul 18, 2022 |
| Lenovo        | ThinkPad T500 2242CTO       | Notebook    | [47bddb4e10](https://linux-hardware.org/?probe=47bddb4e10) | Jul 10, 2022 |
| HP            | ENVY 17                     | Notebook    | [2d97952e56](https://linux-hardware.org/?probe=2d97952e56) | Jul 08, 2022 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [b48ce81bfa](https://linux-hardware.org/?probe=b48ce81bfa) | Jun 27, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [9f14a273b0](https://linux-hardware.org/?probe=9f14a273b0) | Jun 26, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [f6faa2d944](https://linux-hardware.org/?probe=f6faa2d944) | Jun 25, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [e478f31175](https://linux-hardware.org/?probe=e478f31175) | Jun 25, 2022 |
| HP            | 212B                        | Desktop     | [a163af0cb5](https://linux-hardware.org/?probe=a163af0cb5) | Jun 21, 2022 |
| MSI           | GL62 6QF                    | Notebook    | [39e2d35166](https://linux-hardware.org/?probe=39e2d35166) | Jun 20, 2022 |
| Timi          | TM1604                      | Notebook    | [2f45cc25b4](https://linux-hardware.org/?probe=2f45cc25b4) | Jun 20, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [261466af7b](https://linux-hardware.org/?probe=261466af7b) | Jun 17, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [da04a03393](https://linux-hardware.org/?probe=da04a03393) | Jun 04, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [ea74ff47bc](https://linux-hardware.org/?probe=ea74ff47bc) | May 27, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [83e0c49ab0](https://linux-hardware.org/?probe=83e0c49ab0) | May 27, 2022 |
| HP            | Pavilion g6                 | Notebook    | [ef71909561](https://linux-hardware.org/?probe=ef71909561) | May 26, 2022 |
| HP            | Pavilion g6                 | Notebook    | [41d1e81397](https://linux-hardware.org/?probe=41d1e81397) | May 26, 2022 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [fc9dd3db05](https://linux-hardware.org/?probe=fc9dd3db05) | May 26, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [7b393b3933](https://linux-hardware.org/?probe=7b393b3933) | May 24, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [9f009d836c](https://linux-hardware.org/?probe=9f009d836c) | May 23, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [206aa9b805](https://linux-hardware.org/?probe=206aa9b805) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [b128814505](https://linux-hardware.org/?probe=b128814505) | May 21, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [9acb45109f](https://linux-hardware.org/?probe=9acb45109f) | May 21, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [5b7383f9cb](https://linux-hardware.org/?probe=5b7383f9cb) | May 15, 2022 |
| Avell High... | B.ON                        | Notebook    | [9069ca4c66](https://linux-hardware.org/?probe=9069ca4c66) | May 13, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [b9437261b7](https://linux-hardware.org/?probe=b9437261b7) | May 10, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [4ab84df25d](https://linux-hardware.org/?probe=4ab84df25d) | May 10, 2022 |
| MSI           | Modern 15 A10M              | Notebook    | [88c226c079](https://linux-hardware.org/?probe=88c226c079) | May 09, 2022 |
| HP            | 1825                        | Desktop     | [fe93966c1c](https://linux-hardware.org/?probe=fe93966c1c) | May 09, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [296dc11e4b](https://linux-hardware.org/?probe=296dc11e4b) | May 08, 2022 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [ca08dea33b](https://linux-hardware.org/?probe=ca08dea33b) | May 07, 2022 |
| Google        | Boten                       | Notebook    | [6204cff7de](https://linux-hardware.org/?probe=6204cff7de) | May 05, 2022 |
| Samsung       | 740U3M                      | Convertible | [4ba9324ca5](https://linux-hardware.org/?probe=4ba9324ca5) | May 04, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [ff291ff9e3](https://linux-hardware.org/?probe=ff291ff9e3) | May 03, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [0c5f20e02c](https://linux-hardware.org/?probe=0c5f20e02c) | May 02, 2022 |
| HP            | 8446                        | All in one  | [b13e626d1a](https://linux-hardware.org/?probe=b13e626d1a) | May 02, 2022 |
| HP            | 8446                        | All in one  | [14d68e146a](https://linux-hardware.org/?probe=14d68e146a) | May 02, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [0d006e41fc](https://linux-hardware.org/?probe=0d006e41fc) | May 01, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [6ace557278](https://linux-hardware.org/?probe=6ace557278) | Apr 29, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [967eac195b](https://linux-hardware.org/?probe=967eac195b) | Apr 23, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [e2cbc23977](https://linux-hardware.org/?probe=e2cbc23977) | Apr 12, 2022 |
| ASUSTek       | T200TAC                     | Notebook    | [20834c0dba](https://linux-hardware.org/?probe=20834c0dba) | Feb 17, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [77a04d958e](https://linux-hardware.org/?probe=77a04d958e) | Jan 27, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [56d0201ca6](https://linux-hardware.org/?probe=56d0201ca6) | Dec 29, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version            | Computers | Percent |
|--------------------|-----------|---------|
| 5.15.0-27-generic  | 11        | 5.45%   |
| 5.15.0-52-generic  | 9         | 4.46%   |
| 5.15.0-50-generic  | 7         | 3.47%   |
| 5.15.0-48-generic  | 6         | 2.97%   |
| 5.15.0-30-generic  | 6         | 2.97%   |
| 6.5.0-18-generic   | 5         | 2.48%   |
| 6.2.0-39-generic   | 5         | 2.48%   |
| 6.2.0-26-generic   | 5         | 2.48%   |
| 5.19.0-46-generic  | 5         | 2.48%   |
| 5.15.0-46-generic  | 5         | 2.48%   |
| 5.15.0-39-generic  | 5         | 2.48%   |
| 5.19.0-35-generic  | 4         | 1.98%   |
| 5.15.0-58-generic  | 4         | 1.98%   |
| 5.15.0-57-generic  | 4         | 1.98%   |
| 5.15.0-56-generic  | 4         | 1.98%   |
| 5.15.0-43-generic  | 4         | 1.98%   |
| 5.15.0-33-generic  | 4         | 1.98%   |
| 5.15.0-25-generic  | 4         | 1.98%   |
| 6.5.0-26-generic   | 3         | 1.49%   |
| 6.5.0-25-generic   | 3         | 1.49%   |
| 6.2.0-33-generic   | 3         | 1.49%   |
| 5.19.0-45-generic  | 3         | 1.49%   |
| 5.19.0-41-generic  | 3         | 1.49%   |
| 5.19.0-40-generic  | 3         | 1.49%   |
| 5.15.0-53-generic  | 3         | 1.49%   |
| 5.15.0-47-generic  | 3         | 1.49%   |
| 5.15.0-40-generic  | 3         | 1.49%   |
| 6.8.0-45-generic   | 2         | 0.99%   |
| 6.8.0-40-generic   | 2         | 0.99%   |
| 6.5.0-15-generic   | 2         | 0.99%   |
| 6.5.0-14-generic   | 2         | 0.99%   |
| 6.5.0-10013-tuxedo | 2         | 0.99%   |
| 6.2.0-37-generic   | 2         | 0.99%   |
| 6.2.0-32-generic   | 2         | 0.99%   |
| 6.2.0-10007-tuxedo | 2         | 0.99%   |
| 5.19.0-42-generic  | 2         | 0.99%   |
| 5.19.0-38-generic  | 2         | 0.99%   |
| 5.15.0-94-generic  | 2         | 0.99%   |
| 5.15.0-73-generic  | 2         | 0.99%   |
| 5.15.0-67-generic  | 2         | 0.99%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 106       | 57.3%   |
| 5.19.0  | 24        | 12.97%  |
| 6.2.0   | 22        | 11.89%  |
| 6.5.0   | 20        | 10.81%  |
| 6.8.0   | 4         | 2.16%   |
| 5.13.0  | 3         | 1.62%   |
| 6.6.0   | 1         | 0.54%   |
| 6.3.1   | 1         | 0.54%   |
| 6.1.0   | 1         | 0.54%   |
| 5.17.2  | 1         | 0.54%   |
| 5.16.2  | 1         | 0.54%   |
| 5.15.92 | 1         | 0.54%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 107       | 57.84%  |
| 5.19    | 24        | 12.97%  |
| 6.2     | 22        | 11.89%  |
| 6.5     | 20        | 10.81%  |
| 6.8     | 4         | 2.16%   |
| 5.13    | 3         | 1.62%   |
| 6.6     | 1         | 0.54%   |
| 6.3     | 1         | 0.54%   |
| 6.1     | 1         | 0.54%   |
| 5.17    | 1         | 0.54%   |
| 5.16    | 1         | 0.54%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 176       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Budgie | 169       | 96.02%  |
| GNOME  | 6         | 3.41%   |
| KDE5   | 1         | 0.57%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 172       | 97.73%  |
| Wayland | 4         | 2.27%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 126       | 71.19%  |
| Unknown | 30        | 16.95%  |
| GDM3    | 18        | 10.17%  |
| SDDM    | 2         | 1.13%   |
| GDM     | 1         | 0.56%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 65        | 36.93%  |
| de_DE | 20        | 11.36%  |
| fr_FR | 14        | 7.95%   |
| pt_BR | 11        | 6.25%   |
| en_GB | 11        | 6.25%   |
| it_IT | 5         | 2.84%   |
| es_ES | 5         | 2.84%   |
| en_CA | 5         | 2.84%   |
| ru_RU | 3         | 1.7%    |
| fr_BE | 3         | 1.7%    |
| en_AU | 3         | 1.7%    |
| pl_PL | 2         | 1.14%   |
| hu_HU | 2         | 1.14%   |
| eu_ES | 2         | 1.14%   |
| es_MX | 2         | 1.14%   |
| es_CL | 2         | 1.14%   |
| es_AR | 2         | 1.14%   |
| en_ZA | 2         | 1.14%   |
| en_SG | 2         | 1.14%   |
| en_IN | 2         | 1.14%   |
| en_IE | 2         | 1.14%   |
| mt_MT | 1         | 0.57%   |
| ja_JP | 1         | 0.57%   |
| es_PE | 1         | 0.57%   |
| es_EC | 1         | 0.57%   |
| en_NZ | 1         | 0.57%   |
| en_IL | 1         | 0.57%   |
| el_GR | 1         | 0.57%   |
| da_DK | 1         | 0.57%   |
| cs_CZ | 1         | 0.57%   |
| C     | 1         | 0.57%   |
| bg_BG | 1         | 0.57%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 101       | 56.74%  |
| EFI  | 77        | 43.26%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 142       | 78.89%  |
| Tmpfs   | 21        | 11.67%  |
| Overlay | 8         | 4.44%   |
| Zfs     | 5         | 2.78%   |
| Btrfs   | 3         | 1.67%   |
| Xfs     | 1         | 0.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 121       | 67.98%  |
| Unknown | 47        | 26.4%   |
| MBR     | 10        | 5.62%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 149       | 84.66%  |
| Yes       | 27        | 15.34%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 114       | 64.41%  |
| Yes       | 63        | 35.59%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 26        | 14.77%  |
| Hewlett-Packard        | 26        | 14.77%  |
| ASUSTek Computer       | 24        | 13.64%  |
| Dell                   | 20        | 11.36%  |
| TUXEDO                 | 11        | 6.25%   |
| MSI                    | 11        | 6.25%   |
| Gigabyte Technology    | 11        | 6.25%   |
| Apple                  | 10        | 5.68%   |
| Intel                  | 4         | 2.27%   |
| Toshiba                | 3         | 1.7%    |
| Google                 | 3         | 1.7%    |
| Fujitsu                | 3         | 1.7%    |
| ASRock                 | 3         | 1.7%    |
| Chuwi                  | 2         | 1.14%   |
| AZW                    | 2         | 1.14%   |
| Acer                   | 2         | 1.14%   |
| Winnovo                | 1         | 0.57%   |
| Timi                   | 1         | 0.57%   |
| Semp Toshiba           | 1         | 0.57%   |
| Samsung Electronics    | 1         | 0.57%   |
| Razer                  | 1         | 0.57%   |
| PCWare                 | 1         | 0.57%   |
| Packard Bell           | 1         | 0.57%   |
| HUAWEI                 | 1         | 0.57%   |
| Digibras               | 1         | 0.57%   |
| COM1                   | 1         | 0.57%   |
| Biostar                | 1         | 0.57%   |
| BANGHO                 | 1         | 0.57%   |
| AXIOO                  | 1         | 0.57%   |
| Avell High Performance | 1         | 0.57%   |
| Alurin                 | 1         | 0.57%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                 | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| TUXEDO Pulse 15 Gen1                                 | 2         | 1.14%   |
| Lenovo G50-45 80E3                                   | 2         | 1.14%   |
| HP EliteBook 840 G3                                  | 2         | 1.14%   |
| AZW SER                                              | 2         | 1.14%   |
| ASUS All Series                                      | 2         | 1.14%   |
| Winnovo TaBook                                       | 1         | 0.57%   |
| TUXEDO Pulse 14 Gen1                                 | 1         | 0.57%   |
| TUXEDO Polaris Intel Gen3 (TGL)                      | 1         | 0.57%   |
| TUXEDO InfinityBook_Pro13_14_v4                      | 1         | 0.57%   |
| TUXEDO InfinityBook S 15 Gen6                        | 1         | 0.57%   |
| TUXEDO InfinityBook Pro 14 v4                        | 1         | 0.57%   |
| TUXEDO Book XUX7 Gen11                               | 1         | 0.57%   |
| TUXEDO Book XP1511                                   | 1         | 0.57%   |
| TUXEDO Book BA1510                                   | 1         | 0.57%   |
| TUXEDO Aura 15 Gen1                                  | 1         | 0.57%   |
| Toshiba Satellite C855D-11X                          | 1         | 0.57%   |
| Toshiba Satellite A505                               | 1         | 0.57%   |
| Toshiba Satellite A300                               | 1         | 0.57%   |
| Timi TM1604                                          | 1         | 0.57%   |
| Semp Toshiba STI                                     | 1         | 0.57%   |
| Samsung 740U3M                                       | 1         | 0.57%   |
| Razer Blade 15 Advanced Model (Mid 2021) - RZ09-0409 | 1         | 0.57%   |
| PCWare APM-A320G                                     | 1         | 0.57%   |
| Packard Bell EasyNote TM98                           | 1         | 0.57%   |
| MSI MS-7C95                                          | 1         | 0.57%   |
| MSI MS-7C51                                          | 1         | 0.57%   |
| MSI MS-7B87                                          | 1         | 0.57%   |
| MSI MS-7B86                                          | 1         | 0.57%   |
| MSI MS-7A38                                          | 1         | 0.57%   |
| MSI MS-7A32                                          | 1         | 0.57%   |
| MSI MS-7885                                          | 1         | 0.57%   |
| MSI MS-7721                                          | 1         | 0.57%   |
| MSI Modern 15 A10M                                   | 1         | 0.57%   |
| MSI GL62 6QF                                         | 1         | 0.57%   |
| MSI Alpha 15 B5EEK                                   | 1         | 0.57%   |
| Lenovo V15 G2 ALC 82KD                               | 1         | 0.57%   |
| Lenovo ThinkStation P360 Ultra 30G1001AUS            | 1         | 0.57%   |
| Lenovo ThinkStation C20 4263BA7                      | 1         | 0.57%   |
| Lenovo ThinkPad X260 20F5S0V500                      | 1         | 0.57%   |
| Lenovo ThinkPad X220 4291G75                         | 1         | 0.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 11        | 6.25%   |
| Lenovo IdeaPad        | 7         | 3.98%   |
| Dell Latitude         | 5         | 2.84%   |
| Dell Inspiron         | 5         | 2.84%   |
| ASUS VivoBook         | 5         | 2.84%   |
| HP ProBook            | 4         | 2.27%   |
| HP Pavilion           | 4         | 2.27%   |
| HP EliteBook          | 4         | 2.27%   |
| Dell XPS              | 4         | 2.27%   |
| TUXEDO Pulse          | 3         | 1.7%    |
| TUXEDO InfinityBook   | 3         | 1.7%    |
| TUXEDO Book           | 3         | 1.7%    |
| Toshiba Satellite     | 3         | 1.7%    |
| ASUS ZenBook          | 3         | 1.7%    |
| Lenovo ThinkStation   | 2         | 1.14%   |
| Lenovo G50-45         | 2         | 1.14%   |
| HP EliteDesk          | 2         | 1.14%   |
| Fujitsu ESPRIMO       | 2         | 1.14%   |
| Dell Vostro           | 2         | 1.14%   |
| Dell Precision        | 2         | 1.14%   |
| Dell OptiPlex         | 2         | 1.14%   |
| AZW SER               | 2         | 1.14%   |
| ASUS ROG              | 2         | 1.14%   |
| ASUS ASUS             | 2         | 1.14%   |
| ASUS All              | 2         | 1.14%   |
| Apple MacBookPro8     | 2         | 1.14%   |
| Acer Aspire           | 2         | 1.14%   |
| Winnovo TaBook        | 1         | 0.57%   |
| TUXEDO Polaris        | 1         | 0.57%   |
| TUXEDO Aura           | 1         | 0.57%   |
| Timi TM1604           | 1         | 0.57%   |
| Semp Toshiba STI      | 1         | 0.57%   |
| Samsung 740U3M        | 1         | 0.57%   |
| Razer Blade           | 1         | 0.57%   |
| PCWare APM-A320G      | 1         | 0.57%   |
| Packard Bell EasyNote | 1         | 0.57%   |
| MSI MS-7C95           | 1         | 0.57%   |
| MSI MS-7C51           | 1         | 0.57%   |
| MSI MS-7B87           | 1         | 0.57%   |
| MSI MS-7B86           | 1         | 0.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 23        | 13.07%  |
| 2020 | 22        | 12.5%   |
| 2014 | 17        | 9.66%   |
| 2018 | 16        | 9.09%   |
| 2016 | 14        | 7.95%   |
| 2019 | 12        | 6.82%   |
| 2022 | 11        | 6.25%   |
| 2010 | 9         | 5.11%   |
| 2017 | 8         | 4.55%   |
| 2013 | 8         | 4.55%   |
| 2012 | 8         | 4.55%   |
| 2011 | 7         | 3.98%   |
| 2015 | 6         | 3.41%   |
| 2023 | 5         | 2.84%   |
| 2009 | 5         | 2.84%   |
| 2008 | 4         | 2.27%   |
| 2024 | 1         | 0.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 113       | 64.2%   |
| Desktop     | 46        | 26.14%  |
| Convertible | 7         | 3.98%   |
| Mini pc     | 5         | 2.84%   |
| All in one  | 4         | 2.27%   |
| Tablet      | 1         | 0.57%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 166       | 94.32%  |
| Enabled  | 10        | 5.68%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 172       | 97.73%  |
| Yes  | 4         | 2.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 50        | 28.09%  |
| 16.01-24.0      | 45        | 25.28%  |
| 8.01-16.0       | 34        | 19.1%   |
| 3.01-4.0        | 20        | 11.24%  |
| 32.01-64.0      | 15        | 8.43%   |
| 64.01-256.0     | 7         | 3.93%   |
| 24.01-32.0      | 4         | 2.25%   |
| 1.01-2.0        | 2         | 1.12%   |
| More than 256.0 | 1         | 0.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 68        | 35.42%  |
| 1.01-2.0   | 48        | 25%     |
| 4.01-8.0   | 33        | 17.19%  |
| 3.01-4.0   | 21        | 10.94%  |
| 8.01-16.0  | 16        | 8.33%   |
| 16.01-24.0 | 4         | 2.08%   |
| 24.01-32.0 | 2         | 1.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 110       | 61.45%  |
| 2      | 47        | 26.26%  |
| 3      | 12        | 6.7%    |
| 4      | 6         | 3.35%   |
| 6      | 2         | 1.12%   |
| 8      | 1         | 0.56%   |
| 7      | 1         | 0.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 132       | 75%     |
| Yes       | 44        | 25%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 144       | 80.9%   |
| No        | 34        | 19.1%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 150       | 85.23%  |
| No        | 26        | 14.77%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 128       | 72.73%  |
| No        | 48        | 27.27%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 32        | 18.18%  |
| Germany      | 23        | 13.07%  |
| France       | 15        | 8.52%   |
| Brazil       | 13        | 7.39%   |
| UK           | 7         | 3.98%   |
| Spain        | 7         | 3.98%   |
| Italy        | 5         | 2.84%   |
| Canada       | 5         | 2.84%   |
| Poland       | 4         | 2.27%   |
| Netherlands  | 3         | 1.7%    |
| Belgium      | 3         | 1.7%    |
| Austria      | 3         | 1.7%    |
| Australia    | 3         | 1.7%    |
| Argentina    | 3         | 1.7%    |
| Switzerland  | 2         | 1.14%   |
| South Africa | 2         | 1.14%   |
| Slovenia     | 2         | 1.14%   |
| Singapore    | 2         | 1.14%   |
| Russia       | 2         | 1.14%   |
| Romania      | 2         | 1.14%   |
| Peru         | 2         | 1.14%   |
| Mexico       | 2         | 1.14%   |
| Ireland      | 2         | 1.14%   |
| Indonesia    | 2         | 1.14%   |
| India        | 2         | 1.14%   |
| Hungary      | 2         | 1.14%   |
| Greece       | 2         | 1.14%   |
| Czechia      | 2         | 1.14%   |
| Chile        | 2         | 1.14%   |
| Bulgaria     | 2         | 1.14%   |
| Turkey       | 1         | 0.57%   |
| Sweden       | 1         | 0.57%   |
| Slovakia     | 1         | 0.57%   |
| Saudi Arabia | 1         | 0.57%   |
| Norway       | 1         | 0.57%   |
| New Zealand  | 1         | 0.57%   |
| Malta        | 1         | 0.57%   |
| Japan        | 1         | 0.57%   |
| Israel       | 1         | 0.57%   |
| Ghana        | 1         | 0.57%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Brasília         | 4         | 2.17%   |
| Berlin            | 4         | 2.17%   |
| Warsaw            | 2         | 1.09%   |
| Vienna            | 2         | 1.09%   |
| Victoria          | 2         | 1.09%   |
| Singapore         | 2         | 1.09%   |
| Nuremberg         | 2         | 1.09%   |
| Milwaukee         | 2         | 1.09%   |
| London            | 2         | 1.09%   |
| Laval             | 2         | 1.09%   |
| Frankfurt am Main | 2         | 1.09%   |
| Dublin            | 2         | 1.09%   |
| Cape Town         | 2         | 1.09%   |
| Budapest          | 2         | 1.09%   |
| Athens            | 2         | 1.09%   |
| Zurich            | 1         | 0.54%   |
| Yogyakarta        | 1         | 0.54%   |
| West Lafayette    | 1         | 0.54%   |
| Wertheim am Main  | 1         | 0.54%   |
| Weisswasser       | 1         | 0.54%   |
| Weilheim          | 1         | 0.54%   |
| Washington        | 1         | 0.54%   |
| Walled Lake       | 1         | 0.54%   |
| Venray            | 1         | 0.54%   |
| Veliko Tarnovo    | 1         | 0.54%   |
| Trondheim         | 1         | 0.54%   |
| Torun             | 1         | 0.54%   |
| Tocantins         | 1         | 0.54%   |
| Tegueste          | 1         | 0.54%   |
| Targu Frumos      | 1         | 0.54%   |
| Tarakan           | 1         | 0.54%   |
| Tann              | 1         | 0.54%   |
| Tampa             | 1         | 0.54%   |
| Sunnyvale         | 1         | 0.54%   |
| Summerfield       | 1         | 0.54%   |
| St Petersburg     | 1         | 0.54%   |
| Sooke             | 1         | 0.54%   |
| Sofia             | 1         | 0.54%   |
| Siegen            | 1         | 0.54%   |
| Shirakuni         | 1         | 0.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 46        | 77     | 17.76%  |
| WDC                            | 25        | 29     | 9.65%   |
| Seagate                        | 25        | 41     | 9.65%   |
| Unknown                        | 18        | 19     | 6.95%   |
| Toshiba                        | 16        | 21     | 6.18%   |
| Crucial                        | 14        | 21     | 5.41%   |
| SanDisk                        | 12        | 13     | 4.63%   |
| Micron Technology              | 12        | 12     | 4.63%   |
| SK hynix                       | 11        | 11     | 4.25%   |
| Kingston                       | 9         | 10     | 3.47%   |
| Intel                          | 7         | 9      | 2.7%    |
| China                          | 6         | 7      | 2.32%   |
| SPCC                           | 4         | 5      | 1.54%   |
| A-DATA Technology              | 4         | 5      | 1.54%   |
| OCZ                            | 3         | 3      | 1.16%   |
| JMicron Technology             | 3         | 3      | 1.16%   |
| Apple                          | 3         | 3      | 1.16%   |
| Transcend                      | 2         | 2      | 0.77%   |
| PNY                            | 2         | 2      | 0.77%   |
| Phison                         | 2         | 2      | 0.77%   |
| Micron/Crucial Technology      | 2         | 2      | 0.77%   |
| HGST                           | 2         | 2      | 0.77%   |
| Zheino                         | 1         | 1      | 0.39%   |
| YMTC                           | 1         | 1      | 0.39%   |
| VISIPRO                        | 1         | 1      | 0.39%   |
| Union Memory                   | 1         | 1      | 0.39%   |
| UMAX                           | 1         | 1      | 0.39%   |
| TO Exter                       | 1         | 1      | 0.39%   |
| Solid State Storage Technology | 1         | 1      | 0.39%   |
| Silicon Motion                 | 1         | 1      | 0.39%   |
| SABRENT                        | 1         | 1      | 0.39%   |
| Realtek Semiconductor          | 1         | 1      | 0.39%   |
| Plextor                        | 1         | 1      | 0.39%   |
| Phison Electronics             | 1         | 1      | 0.39%   |
| Patriot                        | 1         | 1      | 0.39%   |
| OWC                            | 1         | 1      | 0.39%   |
| Netac                          | 1         | 1      | 0.39%   |
| NE-1TB                         | 1         | 1      | 0.39%   |
| Mushkin                        | 1         | 1      | 0.39%   |
| MicroFrom                      | 1         | 1      | 0.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 4         | 1.43%   |
| Kingston SA400S37240G 240GB SSD                     | 4         | 1.43%   |
| Unknown MMC Card  64GB                              | 3         | 1.07%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 3         | 1.07%   |
| Samsung SSD 860 EVO M.2 500GB                       | 3         | 1.07%   |
| Samsung SSD 860 EVO 500GB                           | 3         | 1.07%   |
| Crucial CT480BX500SSD1 480GB                        | 3         | 1.07%   |
| Crucial CT240BX500SSD1 240GB                        | 3         | 1.07%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 2         | 0.71%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 2         | 0.71%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 2         | 0.71%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 2         | 0.71%   |
| Unknown SD64G  64GB                                 | 2         | 0.71%   |
| Unknown SD/MMC/MS PRO 128GB                         | 2         | 0.71%   |
| Unknown MMC Card  128GB                             | 2         | 0.71%   |
| Seagate ST3500418AS 500GB                           | 2         | 0.71%   |
| Seagate ST3500413AS 500GB                           | 2         | 0.71%   |
| Seagate ST1000LM048-2E7172 1TB                      | 2         | 0.71%   |
| Seagate ST1000LM035-1RK172 1TB                      | 2         | 0.71%   |
| Seagate ST1000LM014-1EJ164 1TB                      | 2         | 0.71%   |
| Seagate ST1000DM010-2EP102 1TB                      | 2         | 0.71%   |
| SanDisk SDSSDA120G 120GB                            | 2         | 0.71%   |
| Samsung SSD 980 PRO 2TB                             | 2         | 0.71%   |
| Samsung SSD 980 500GB                               | 2         | 0.71%   |
| Samsung SSD 870 EVO 250GB                           | 2         | 0.71%   |
| Samsung SSD 850 PRO 256GB                           | 2         | 0.71%   |
| Samsung SSD 850 EVO 500GB                           | 2         | 0.71%   |
| Samsung SSD 840 EVO 250GB                           | 2         | 0.71%   |
| Samsung NVMe SSD Drive 256GB                        | 2         | 0.71%   |
| Samsung MZVLQ512HALU-000H1 512GB                    | 2         | 0.71%   |
| JMicron Generic 500GB                               | 2         | 0.71%   |
| Crucial CT1000MX500SSD1 1TB                         | 2         | 0.71%   |
| China SSD 256GB                                     | 2         | 0.71%   |
| Zheino CHN-25SATAC3-120 120GB                       | 1         | 0.36%   |
| YMTC PC005 1TB                                      | 1         | 0.36%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                    | 1         | 0.36%   |
| WDC WDS100T2B0C 1TB                                 | 1         | 0.36%   |
| WDC WD6400BEVT-22A0RT0 640GB                        | 1         | 0.36%   |
| WDC WD40PURZ-85TTDY0 4TB                            | 1         | 0.36%   |
| WDC WD40EZAZ-00SF3B0 4TB                            | 1         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 25        | 40     | 38.46%  |
| WDC                 | 16        | 18     | 24.62%  |
| Toshiba             | 10        | 11     | 15.38%  |
| Samsung Electronics | 3         | 5      | 4.62%   |
| Unknown             | 2         | 2      | 3.08%   |
| JMicron Technology  | 2         | 2      | 3.08%   |
| HGST                | 2         | 2      | 3.08%   |
| TO Exter            | 1         | 1      | 1.54%   |
| SABRENT             | 1         | 1      | 1.54%   |
| Maxtor              | 1         | 1      | 1.54%   |
| ASMT109x            | 1         | 1      | 1.54%   |
| Apple               | 1         | 1      | 1.54%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 20        | 42     | 20.83%  |
| Crucial             | 13        | 20     | 13.54%  |
| SanDisk             | 8         | 8      | 8.33%   |
| WDC                 | 6         | 6      | 6.25%   |
| Kingston            | 6         | 7      | 6.25%   |
| China               | 6         | 7      | 6.25%   |
| Micron Technology   | 5         | 5      | 5.21%   |
| SPCC                | 3         | 4      | 3.13%   |
| SK hynix            | 2         | 2      | 2.08%   |
| PNY                 | 2         | 2      | 2.08%   |
| OCZ                 | 2         | 2      | 2.08%   |
| Apple               | 2         | 2      | 2.08%   |
| A-DATA Technology   | 2         | 2      | 2.08%   |
| Zheino              | 1         | 1      | 1.04%   |
| VISIPRO             | 1         | 1      | 1.04%   |
| Union Memory        | 1         | 1      | 1.04%   |
| UMAX                | 1         | 1      | 1.04%   |
| Transcend           | 1         | 1      | 1.04%   |
| Toshiba             | 1         | 1      | 1.04%   |
| Plextor             | 1         | 1      | 1.04%   |
| Patriot             | 1         | 1      | 1.04%   |
| OWC                 | 1         | 1      | 1.04%   |
| Netac               | 1         | 1      | 1.04%   |
| Mushkin             | 1         | 1      | 1.04%   |
| MicroFrom           | 1         | 1      | 1.04%   |
| LITEON              | 1         | 1      | 1.04%   |
| Intel               | 1         | 1      | 1.04%   |
| Hewlett-Packard     | 1         | 1      | 1.04%   |
| Gigabyte Technology | 1         | 1      | 1.04%   |
| Dogfish             | 1         | 1      | 1.04%   |
| Corsair             | 1         | 2      | 1.04%   |
| 4Life               | 1         | 1      | 1.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 84        | 129    | 36.21%  |
| NVMe    | 76        | 94     | 32.76%  |
| HDD     | 52        | 85     | 22.41%  |
| MMC     | 17        | 20     | 7.33%   |
| Unknown | 3         | 3      | 1.29%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 108       | 205    | 50.94%  |
| NVMe | 76        | 93     | 35.85%  |
| MMC  | 17        | 20     | 8.02%   |
| SAS  | 11        | 13     | 5.19%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 88        | 133    | 60.69%  |
| 0.51-1.0   | 35        | 50     | 24.14%  |
| 1.01-2.0   | 13        | 20     | 8.97%   |
| 3.01-4.0   | 8         | 9      | 5.52%   |
| 4.01-10.0  | 1         | 2      | 0.69%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 54        | 30.51%  |
| 251-500        | 45        | 25.42%  |
| 501-1000       | 25        | 14.12%  |
| 51-100         | 15        | 8.47%   |
| 1001-2000      | 12        | 6.78%   |
| 1-20           | 10        | 5.65%   |
| More than 3000 | 7         | 3.95%   |
| 21-50          | 6         | 3.39%   |
| 2001-3000      | 3         | 1.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 50        | 27.32%  |
| 21-50          | 46        | 25.14%  |
| 101-250        | 29        | 15.85%  |
| 51-100         | 21        | 11.48%  |
| 251-500        | 17        | 9.29%   |
| 501-1000       | 9         | 4.92%   |
| 1001-2000      | 8         | 4.37%   |
| More than 3000 | 2         | 1.09%   |
| 2001-3000      | 1         | 0.55%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-22V0TT0 500GB       | 1         | 1      | 16.67%  |
| WDC WD10JPVX-60JC3T0 1TB           | 1         | 1      | 16.67%  |
| Toshiba MQ01ABD075 752GB           | 1         | 1      | 16.67%  |
| Seagate ST500DM002-1BD142 500GB    | 1         | 1      | 16.67%  |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 16.67%  |
| HGST HTS541010A9E680 1TB           | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 33.33%  |
| Seagate | 2         | 2      | 33.33%  |
| Toshiba | 1         | 1      | 16.67%  |
| HGST    | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 33.33%  |
| Seagate | 2         | 2      | 33.33%  |
| Toshiba | 1         | 1      | 16.67%  |
| HGST    | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 6      | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Apple HDD HTS541010A9E662 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| Apple  | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 106       | 210    | 55.79%  |
| Works    | 77        | 114    | 40.53%  |
| Malfunc  | 6         | 6      | 3.16%   |
| Failed   | 1         | 1      | 0.53%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 108       | 49.09%  |
| AMD                            | 32        | 14.55%  |
| Samsung Electronics            | 26        | 11.82%  |
| SanDisk                        | 8         | 3.64%   |
| SK hynix                       | 7         | 3.18%   |
| Micron Technology              | 7         | 3.18%   |
| Toshiba America Info Systems   | 4         | 1.82%   |
| Kingston Technology Company    | 4         | 1.82%   |
| Phison Electronics             | 3         | 1.36%   |
| Nvidia                         | 3         | 1.36%   |
| Micron/Crucial Technology      | 3         | 1.36%   |
| Marvell Technology Group       | 2         | 0.91%   |
| KIOXIA                         | 2         | 0.91%   |
| ADATA Technology               | 2         | 0.91%   |
| Yangtze Memory Technologies    | 1         | 0.45%   |
| Transcend                      | 1         | 0.45%   |
| Solidigm                       | 1         | 0.45%   |
| Solid State Storage Technology | 1         | 0.45%   |
| Silicon Motion                 | 1         | 0.45%   |
| Seagate Technology             | 1         | 0.45%   |
| Realtek Semiconductor          | 1         | 0.45%   |
| OCZ Technology Group           | 1         | 0.45%   |
| JMicron Technology             | 1         | 0.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 21        | 8.64%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 13        | 5.35%   |
| Intel Volume Management Device NVMe RAID Controller                            | 9         | 3.7%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 7         | 2.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 6         | 2.47%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 2.47%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 2.06%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 5         | 2.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 2.06%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 5         | 2.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 2.06%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 5         | 2.06%   |
| AMD 400 Series Chipset SATA Controller                                         | 5         | 2.06%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 1.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 1.65%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 1.65%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.65%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 1.23%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 1.23%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 1.23%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 1.23%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 3         | 1.23%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 2         | 0.82%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 0.82%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 2         | 0.82%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 2         | 0.82%   |
| Nvidia MCP79 AHCI Controller                                                   | 2         | 0.82%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2         | 0.82%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 2         | 0.82%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 2         | 0.82%   |
| Micron 2300 NVMe SSD [Santana]                                                 | 2         | 0.82%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 2         | 0.82%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 2         | 0.82%   |
| Intel SSD 660P Series                                                          | 2         | 0.82%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]             | 2         | 0.82%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 0.82%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 0.82%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 2         | 0.82%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 2         | 0.82%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 2         | 0.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 125       | 55.07%  |
| NVMe | 76        | 33.48%  |
| RAID | 14        | 6.17%   |
| IDE  | 12        | 5.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 135       | 76.7%   |
| AMD    | 41        | 23.3%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 3.41%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 4         | 2.27%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 4         | 2.27%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 1.7%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.7%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 1.7%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 1.7%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 1.7%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 1.7%    |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 2         | 1.14%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.14%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 2         | 1.14%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 1.14%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.14%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 2         | 1.14%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 1.14%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 2         | 1.14%   |
| Intel Core i5-4590T CPU @ 2.00GHz             | 2         | 1.14%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.14%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.14%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 2         | 1.14%   |
| Intel Celeron N4500 @ 1.10GHz                 | 2         | 1.14%   |
| Intel Atom CPU Z3795 @ 1.60GHz                | 2         | 1.14%   |
| Intel 11th Gen Core i7-11850H @ 2.50GHz       | 2         | 1.14%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 1.14%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.14%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 1.14%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 2         | 1.14%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 1.14%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.14%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 2         | 1.14%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics   | 2         | 1.14%   |
| Intel Xeon CPU X5492 @ 3.40GHz                | 1         | 0.57%   |
| Intel Xeon CPU E5620 @ 2.40GHz                | 1         | 0.57%   |
| Intel Xeon CPU E5-2697A v4 @ 2.60GHz          | 1         | 0.57%   |
| Intel Xeon CPU E5-1620 v4 @ 3.50GHz           | 1         | 0.57%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 0.57%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.57%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 0.57%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 40        | 22.73%  |
| Intel Core i7           | 32        | 18.18%  |
| Other                   | 24        | 13.64%  |
| AMD Ryzen 7             | 12        | 6.82%   |
| AMD Ryzen 5             | 12        | 6.82%   |
| Intel Celeron           | 10        | 5.68%   |
| Intel Core i3           | 8         | 4.55%   |
| Intel Pentium           | 5         | 2.84%   |
| Intel Xeon              | 4         | 2.27%   |
| Intel Atom              | 4         | 2.27%   |
| Intel Core 2 Duo        | 3         | 1.7%    |
| AMD Ryzen 9             | 3         | 1.7%    |
| AMD Ryzen 3             | 3         | 1.7%    |
| Intel Pentium Silver    | 2         | 1.14%   |
| AMD A8                  | 2         | 1.14%   |
| AMD A4                  | 2         | 1.14%   |
| Intel Pentium Dual-Core | 1         | 0.57%   |
| Intel Core i9           | 1         | 0.57%   |
| Intel Core 2 Quad       | 1         | 0.57%   |
| AMD Phenom II X4        | 1         | 0.57%   |
| AMD FX                  | 1         | 0.57%   |
| AMD Athlon X4           | 1         | 0.57%   |
| AMD Athlon II X3        | 1         | 0.57%   |
| AMD Athlon              | 1         | 0.57%   |
| AMD A6                  | 1         | 0.57%   |
| AMD A10                 | 1         | 0.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 71        | 40.34%  |
| 2      | 55        | 31.25%  |
| 8      | 19        | 10.8%   |
| 6      | 16        | 9.09%   |
| 12     | 6         | 3.41%   |
| 10     | 4         | 2.27%   |
| 1      | 3         | 1.7%    |
| 16     | 1         | 0.57%   |
| 3      | 1         | 0.57%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 174       | 98.86%  |
| 2      | 2         | 1.14%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 129       | 73.3%   |
| 1      | 47        | 26.7%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 176       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 109       | 60.22%  |
| 0x806c1    | 5         | 2.76%   |
| 0x806ec    | 4         | 2.21%   |
| 0x306a9    | 4         | 2.21%   |
| 0x08600106 | 4         | 2.21%   |
| 0x706a8    | 3         | 1.66%   |
| 0x506e3    | 3         | 1.66%   |
| 0x206a7    | 3         | 1.66%   |
| 0x0a50000c | 3         | 1.66%   |
| 0x08108102 | 3         | 1.66%   |
| 0x806eb    | 2         | 1.1%    |
| 0x806ea    | 2         | 1.1%    |
| 0x806e9    | 2         | 1.1%    |
| 0x806d1    | 2         | 1.1%    |
| 0x406f1    | 2         | 1.1%    |
| 0x406e3    | 2         | 1.1%    |
| 0x306c3    | 2         | 1.1%    |
| 0x20655    | 2         | 1.1%    |
| 0x106e5    | 2         | 1.1%    |
| 0x08608103 | 2         | 1.1%    |
| 0xa0671    | 1         | 0.55%   |
| 0x906eb    | 1         | 0.55%   |
| 0x906ea    | 1         | 0.55%   |
| 0x906a3    | 1         | 0.55%   |
| 0x506c9    | 1         | 0.55%   |
| 0x406c4    | 1         | 0.55%   |
| 0x40651    | 1         | 0.55%   |
| 0x306d4    | 1         | 0.55%   |
| 0x30678    | 1         | 0.55%   |
| 0x1067a    | 1         | 0.55%   |
| 0x10677    | 1         | 0.55%   |
| 0x0a601206 | 1         | 0.55%   |
| 0x0a201205 | 1         | 0.55%   |
| 0x0a201016 | 1         | 0.55%   |
| 0x08608104 | 1         | 0.55%   |
| 0x08600103 | 1         | 0.55%   |
| 0x08108109 | 1         | 0.55%   |
| 0x07030105 | 1         | 0.55%   |
| 0x07030104 | 1         | 0.55%   |
| 0x06001119 | 1         | 0.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 28        | 15.91%  |
| Skylake          | 14        | 7.95%   |
| TigerLake        | 12        | 6.82%   |
| Unknown          | 12        | 6.82%   |
| Haswell          | 10        | 5.68%   |
| Zen 3            | 9         | 5.11%   |
| Zen+             | 8         | 4.55%   |
| SandyBridge      | 8         | 4.55%   |
| IvyBridge        | 8         | 4.55%   |
| Zen 2            | 7         | 3.98%   |
| Goldmont plus    | 7         | 3.98%   |
| Westmere         | 6         | 3.41%   |
| Silvermont       | 6         | 3.41%   |
| Penryn           | 6         | 3.41%   |
| Broadwell        | 6         | 3.41%   |
| Alderlake Hybrid | 5         | 2.84%   |
| Nehalem          | 4         | 2.27%   |
| Icelake          | 4         | 2.27%   |
| Piledriver       | 3         | 1.7%    |
| CometLake        | 3         | 1.7%    |
| Puma             | 2         | 1.14%   |
| K10              | 2         | 1.14%   |
| Goldmont         | 2         | 1.14%   |
| Zen              | 1         | 0.57%   |
| Steamroller      | 1         | 0.57%   |
| Excavator        | 1         | 0.57%   |
| Bulldozer        | 1         | 0.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 118       | 57.28%  |
| Nvidia | 45        | 21.84%  |
| AMD    | 43        | 20.87%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 5.71%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 3.81%   |
| Intel UHD Graphics 620                                                                   | 7         | 3.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 3.33%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 7         | 3.33%   |
| Intel HD Graphics 530                                                                    | 6         | 2.86%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 2.86%   |
| Intel HD Graphics 620                                                                    | 5         | 2.38%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 2.38%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 2.38%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 2.38%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5         | 2.38%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 4         | 1.9%    |
| Intel HD Graphics 5500                                                                   | 4         | 1.9%    |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.9%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 1.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.9%    |
| AMD Lucienne                                                                             | 4         | 1.9%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 1.43%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.43%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 1.43%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.95%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 0.95%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 2         | 0.95%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 0.95%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 0.95%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.95%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 0.95%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.95%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.95%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900 GRE/7900M]                                  | 2         | 0.95%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 0.95%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 0.95%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2         | 0.95%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.48%   |
| Nvidia TU117GL [T400 4GB / T400E]                                                        | 1         | 0.48%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 0.48%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 1         | 0.48%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 88        | 50%     |
| 1 x AMD        | 34        | 19.32%  |
| 1 x Nvidia     | 21        | 11.93%  |
| Intel + Nvidia | 21        | 11.93%  |
| 2 x AMD        | 3         | 1.7%    |
| Intel + AMD    | 3         | 1.7%    |
| AMD + Nvidia   | 3         | 1.7%    |
| Other          | 2         | 1.14%   |
| 2 x Intel      | 1         | 0.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 150       | 84.75%  |
| Proprietary | 22        | 12.43%  |
| Unknown     | 5         | 2.82%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 137       | 77.4%   |
| 0.01-0.5   | 11        | 6.21%   |
| 1.01-2.0   | 8         | 4.52%   |
| 3.01-4.0   | 7         | 3.95%   |
| 7.01-8.0   | 5         | 2.82%   |
| 0.51-1.0   | 5         | 2.82%   |
| 2.01-3.0   | 2         | 1.13%   |
| 16.01-24.0 | 2         | 1.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 28        | 14.21%  |
| Chimei Innolux          | 28        | 14.21%  |
| BOE                     | 26        | 13.2%   |
| AU Optronics            | 16        | 8.12%   |
| LG Display              | 13        | 6.6%    |
| Apple                   | 9         | 4.57%   |
| Goldstar                | 7         | 3.55%   |
| Philips                 | 6         | 3.05%   |
| Sharp                   | 5         | 2.54%   |
| Hewlett-Packard         | 5         | 2.54%   |
| Dell                    | 5         | 2.54%   |
| AOC                     | 5         | 2.54%   |
| Acer                    | 4         | 2.03%   |
| PANDA                   | 3         | 1.52%   |
| Chi Mei Optoelectronics | 3         | 1.52%   |
| BenQ                    | 3         | 1.52%   |
| Sony                    | 2         | 1.02%   |
| SANYO                   | 2         | 1.02%   |
| Lenovo                  | 2         | 1.02%   |
| HKC                     | 2         | 1.02%   |
| Fujitsu Siemens         | 2         | 1.02%   |
| Ancor Communications    | 2         | 1.02%   |
| Vizio                   | 1         | 0.51%   |
| Vestel Elektronik       | 1         | 0.51%   |
| Unknown (XXX)           | 1         | 0.51%   |
| Unknown (AAA)           | 1         | 0.51%   |
| TMX                     | 1         | 0.51%   |
| RTK                     | 1         | 0.51%   |
| Panasonic               | 1         | 0.51%   |
| ONN                     | 1         | 0.51%   |
| NEC Computers           | 1         | 0.51%   |
| MStar                   | 1         | 0.51%   |
| LG Philips              | 1         | 0.51%   |
| LG Electronics          | 1         | 0.51%   |
| KDC                     | 1         | 0.51%   |
| JDZ                     | 1         | 0.51%   |
| InfoVision              | 1         | 0.51%   |
| IBM                     | 1         | 0.51%   |
| Denver                  | 1         | 0.51%   |
| Daewoo                  | 1         | 0.51%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch    | 2         | 0.98%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch        | 2         | 0.98%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch       | 2         | 0.98%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch       | 2         | 0.98%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch       | 2         | 0.98%   |
| Vizio E320-B2 VIZ0095 1360x768 477x268mm 21.5-inch                     | 1         | 0.49%   |
| Vestel Elektronik 49FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch  | 1         | 0.49%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch          | 1         | 0.49%   |
| Unknown (AAA) LCDTV AAA3393 1360x768 890x500mm 40.2-inch               | 1         | 0.49%   |
| TMX TL142GDXP02-0 TMX1420 2520x1680 300x200mm 14.2-inch                | 1         | 0.49%   |
| Sony TV SNYEE01 1920x1080                                              | 1         | 0.49%   |
| Sony TV SNYAB03 1920x1080                                              | 1         | 0.49%   |
| Sharp LQ156T1JW03 SHP1529 2560x1440 344x194mm 15.5-inch                | 1         | 0.49%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                | 1         | 0.49%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                | 1         | 0.49%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                | 1         | 0.49%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch                | 1         | 0.49%   |
| SANYO LCD-24XH7** SAN0B92 1920x540 531x299mm 24.0-inch                 | 1         | 0.49%   |
| SANYO LCD SAN0A12 1920x540                                             | 1         | 0.49%   |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch      | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM060C 1920x1080 510x290mm 23.1-inch   | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM0346 1680x1050 459x296mm 21.5-inch   | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch   | 1         | 0.49%   |
| Samsung Electronics SMT22A550 SAM07AF 1920x1080 477x268mm 21.5-inch    | 1         | 0.49%   |
| Samsung Electronics SMB2030N SAM0634 1600x900 443x249mm 20.0-inch      | 1         | 0.49%   |
| Samsung Electronics SMB1930N SAM0632 1360x768 410x230mm 18.5-inch      | 1         | 0.49%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch      | 1         | 0.49%   |
| Samsung Electronics S24C450 SAM09CF 1920x1200 518x324mm 24.1-inch      | 1         | 0.49%   |
| Samsung Electronics Odyssey G7 SAM72BF 3840x2160 697x392mm 31.5-inch   | 1         | 0.49%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 630x360mm 28.6-inch      | 1         | 0.49%   |
| Samsung Electronics LS24AG30x SAM7178 1920x1080 527x296mm 23.8-inch    | 1         | 0.49%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch      | 1         | 0.49%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 477x268mm 21.5-inch      | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch   | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch   | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SDC5844 1920x1080 344x194mm 15.5-inch  | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch  | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch  | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SDC414F 3456x2160 288x180mm 13.4-inch  | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1110x620mm 50.1-inch | 1         | 0.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 88        | 47.83%  |
| 1366x768 (WXGA)    | 32        | 17.39%  |
| 3840x2160 (4K)     | 14        | 7.61%   |
| 1920x1200 (WUXGA)  | 10        | 5.43%   |
| 2560x1440 (QHD)    | 8         | 4.35%   |
| 1680x1050 (WSXGA+) | 4         | 2.17%   |
| 1600x900 (HD+)     | 4         | 2.17%   |
| 1280x800 (WXGA)    | 4         | 2.17%   |
| 3440x1440          | 3         | 1.63%   |
| 1920x540           | 3         | 1.63%   |
| 1440x900 (WXGA+)   | 3         | 1.63%   |
| 2560x1080          | 2         | 1.09%   |
| 3456x2160          | 1         | 0.54%   |
| 2880x1800          | 1         | 0.54%   |
| 2736x1824          | 1         | 0.54%   |
| 2560x1600          | 1         | 0.54%   |
| 2520x1680          | 1         | 0.54%   |
| 2240x1400          | 1         | 0.54%   |
| 1920x1280          | 1         | 0.54%   |
| 1360x768           | 1         | 0.54%   |
| 1280x1024 (SXGA)   | 1         | 0.54%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 55        | 27.5%   |
| 13      | 29        | 14.5%   |
| 24      | 16        | 8%      |
| 27      | 14        | 7%      |
| 23      | 13        | 6.5%    |
| 14      | 13        | 6.5%    |
| 21      | 10        | 5%      |
| 34      | 5         | 2.5%    |
| 31      | 5         | 2.5%    |
| 17      | 5         | 2.5%    |
| 12      | 5         | 2.5%    |
| 11      | 4         | 2%      |
| Unknown | 4         | 2%      |
| 40      | 3         | 1.5%    |
| 84      | 2         | 1%      |
| 72      | 2         | 1%      |
| 54      | 2         | 1%      |
| 18      | 2         | 1%      |
| 16      | 2         | 1%      |
| 60      | 1         | 0.5%    |
| 46      | 1         | 0.5%    |
| 33      | 1         | 0.5%    |
| 28      | 1         | 0.5%    |
| 26      | 1         | 0.5%    |
| 22      | 1         | 0.5%    |
| 20      | 1         | 0.5%    |
| 19      | 1         | 0.5%    |
| 10      | 1         | 0.5%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 84        | 42.64%  |
| 501-600     | 39        | 19.8%   |
| 201-300     | 24        | 12.18%  |
| 401-500     | 16        | 8.12%   |
| 601-700     | 7         | 3.55%   |
| 701-800     | 6         | 3.05%   |
| 351-400     | 6         | 3.05%   |
| 1501-2000   | 4         | 2.03%   |
| 1001-1500   | 4         | 2.03%   |
| Unknown     | 4         | 2.03%   |
| 801-900     | 3         | 1.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 140       | 79.1%   |
| 16/10   | 25        | 14.12%  |
| 21/9    | 5         | 2.82%   |
| 3/2     | 4         | 2.26%   |
| Unknown | 2         | 1.13%   |
| 32/9    | 1         | 0.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 55        | 27.92%  |
| 81-90          | 33        | 16.75%  |
| 201-250        | 30        | 15.23%  |
| 301-350        | 14        | 7.11%   |
| 351-500        | 12        | 6.09%   |
| 71-80          | 8         | 4.06%   |
| More than 1000 | 7         | 3.55%   |
| 61-70          | 5         | 2.54%   |
| 251-300        | 5         | 2.54%   |
| 151-200        | 5         | 2.54%   |
| 51-60          | 4         | 2.03%   |
| 121-130        | 4         | 2.03%   |
| 501-1000       | 4         | 2.03%   |
| Unknown        | 4         | 2.03%   |
| 141-150        | 2         | 1.02%   |
| 111-120        | 2         | 1.02%   |
| 41-50          | 1         | 0.51%   |
| 131-140        | 1         | 0.51%   |
| 91-100         | 1         | 0.51%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 62        | 31.63%  |
| 51-100        | 50        | 25.51%  |
| 101-120       | 44        | 22.45%  |
| 161-240       | 18        | 9.18%   |
| More than 240 | 9         | 4.59%   |
| 1-50          | 9         | 4.59%   |
| Unknown       | 4         | 2.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 138       | 77.53%  |
| 2     | 37        | 20.79%  |
| 0     | 3         | 1.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 95        | 35.71%  |
| Realtek Semiconductor | 89        | 33.46%  |
| Qualcomm Atheros      | 21        | 7.89%   |
| Broadcom              | 16        | 6.02%   |
| MediaTek              | 10        | 3.76%   |
| ASIX Electronics      | 5         | 1.88%   |
| Broadcom Limited      | 4         | 1.5%    |
| Nvidia                | 3         | 1.13%   |
| Xiaomi                | 2         | 0.75%   |
| Lenovo                | 2         | 0.75%   |
| JMicron Technology    | 2         | 0.75%   |
| Hewlett-Packard       | 2         | 0.75%   |
| DisplayLink           | 2         | 0.75%   |
| TP-Link               | 1         | 0.38%   |
| T & A Mobile Phones   | 1         | 0.38%   |
| Sierra Wireless       | 1         | 0.38%   |
| Samsung Electronics   | 1         | 0.38%   |
| Raspberry Pi          | 1         | 0.38%   |
| Ralink Technology     | 1         | 0.38%   |
| Ralink                | 1         | 0.38%   |
| Microsoft             | 1         | 0.38%   |
| Microchip Technology  | 1         | 0.38%   |
| Huawei Technologies   | 1         | 0.38%   |
| Fibocom               | 1         | 0.38%   |
| Edimax Technology     | 1         | 0.38%   |
| ASUSTek Computer      | 1         | 0.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 55        | 17.41%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 12        | 3.8%    |
| Intel Wi-Fi 6 AX200                                                     | 12        | 3.8%    |
| Intel Wi-Fi 6 AX201                                                     | 10        | 3.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 8         | 2.53%   |
| Intel Wireless 8265 / 8275                                              | 8         | 2.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.9%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 1.9%    |
| Intel Wireless 8260                                                     | 6         | 1.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 1.58%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 5         | 1.58%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 1.58%   |
| ASIX AX88179 Gigabit Ethernet                                           | 5         | 1.58%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 1.27%   |
| Intel Wireless 7265                                                     | 4         | 1.27%   |
| Intel Ethernet Connection I217-LM                                       | 4         | 1.27%   |
| Intel Ethernet Connection (4) I219-LM                                   | 4         | 1.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 1.27%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 4         | 1.27%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 4         | 1.27%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 1.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.95%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 3         | 0.95%   |
| Realtek RTL8125 2.5GbE Controller                                       | 3         | 0.95%   |
| Intel Ethernet Controller I225-V                                        | 3         | 0.95%   |
| Intel Ethernet Connection I219-V                                        | 3         | 0.95%   |
| Intel Ethernet Connection (2) I219-LM                                   | 3         | 0.95%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 3         | 0.95%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 2         | 0.63%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.63%   |
| Realtek 802.11n WLAN Adapter                                            | 2         | 0.63%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 2         | 0.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 0.63%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.63%   |
| Nvidia MCP79 Ethernet                                                   | 2         | 0.63%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 2         | 0.63%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 2         | 0.63%   |
| Intel Wireless 7260                                                     | 2         | 0.63%   |
| Intel Wireless 3165                                                     | 2         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 80        | 51.28%  |
| Realtek Semiconductor | 24        | 15.38%  |
| Qualcomm Atheros      | 17        | 10.9%   |
| Broadcom              | 14        | 8.97%   |
| MediaTek              | 10        | 6.41%   |
| Broadcom Limited      | 2         | 1.28%   |
| TP-Link               | 1         | 0.64%   |
| Sierra Wireless       | 1         | 0.64%   |
| Ralink Technology     | 1         | 0.64%   |
| Ralink                | 1         | 0.64%   |
| Microsoft             | 1         | 0.64%   |
| Hewlett-Packard       | 1         | 0.64%   |
| Fibocom               | 1         | 0.64%   |
| Edimax Technology     | 1         | 0.64%   |
| ASUSTek Computer      | 1         | 0.64%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 12        | 7.69%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 6.41%   |
| Intel Wireless 8265 / 8275                                              | 8         | 5.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 3.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 3.85%   |
| Intel Wireless 8260                                                     | 6         | 3.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 3.21%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 5         | 3.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 3.21%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 2.56%   |
| Intel Wireless 7265                                                     | 4         | 2.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 2.56%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 4         | 2.56%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 4         | 2.56%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 2.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.92%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.28%   |
| Realtek 802.11n WLAN Adapter                                            | 2         | 1.28%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.28%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 1.28%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.28%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 2         | 1.28%   |
| Intel Wireless 7260                                                     | 2         | 1.28%   |
| Intel Wireless 3165                                                     | 2         | 1.28%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 2         | 1.28%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 1.28%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.28%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.28%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1         | 0.64%   |
| Sierra Wireless EM7455                                                  | 1         | 0.64%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.64%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 1         | 0.64%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 0.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.64%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.64%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.64%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 0.64%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.64%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 0.64%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 79        | 52.32%  |
| Intel                 | 38        | 25.17%  |
| Broadcom              | 9         | 5.96%   |
| ASIX Electronics      | 5         | 3.31%   |
| Qualcomm Atheros      | 4         | 2.65%   |
| Nvidia                | 3         | 1.99%   |
| Xiaomi                | 2         | 1.32%   |
| Lenovo                | 2         | 1.32%   |
| JMicron Technology    | 2         | 1.32%   |
| DisplayLink           | 2         | 1.32%   |
| Broadcom Limited      | 2         | 1.32%   |
| T & A Mobile Phones   | 1         | 0.66%   |
| Samsung Electronics   | 1         | 0.66%   |
| Hewlett-Packard       | 1         | 0.66%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 55        | 35.03%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 12        | 7.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 8         | 5.1%    |
| ASIX AX88179 Gigabit Ethernet                                          | 5         | 3.18%   |
| Intel Ethernet Connection I217-LM                                      | 4         | 2.55%   |
| Intel Ethernet Connection (4) I219-LM                                  | 4         | 2.55%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 3         | 1.91%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 1.91%   |
| Intel Ethernet Controller I225-V                                       | 3         | 1.91%   |
| Intel Ethernet Connection I219-V                                       | 3         | 1.91%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3         | 1.91%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 1.91%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2         | 1.27%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 1.27%   |
| Nvidia MCP79 Ethernet                                                  | 2         | 1.27%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 2         | 1.27%   |
| Intel I211 Gigabit Network Connection                                  | 2         | 1.27%   |
| Intel I210 Gigabit Network Connection                                  | 2         | 1.27%   |
| Intel Ethernet Connection (2) I218-V                                   | 2         | 1.27%   |
| Intel Ethernet Connection (14) I219-V                                  | 2         | 1.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 1.27%   |
| DisplayLink Dell Universal Dock D6000                                  | 2         | 1.27%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 2         | 1.27%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2         | 1.27%   |
| T & A Mobile Phones TCL 30 Z                                           | 1         | 0.64%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.64%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1         | 0.64%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 1         | 0.64%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.64%   |
| Nvidia MCP61 Ethernet                                                  | 1         | 0.64%   |
| Lenovo ThinkPad Lan                                                    | 1         | 0.64%   |
| Lenovo AX88179 Gigabit Ethernet [ThinkPad OneLink GigaLAN]             | 1         | 0.64%   |
| Intel Ethernet Controller I225-LM                                      | 1         | 0.64%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 0.64%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 0.64%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 0.64%   |
| Intel Ethernet Connection (2) I218-LM                                  | 1         | 0.64%   |
| Intel Ethernet Connection (16) I219-V                                  | 1         | 0.64%   |
| Intel Ethernet Connection (16) I219-LM                                 | 1         | 0.64%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 150       | 50.68%  |
| Ethernet | 143       | 48.31%  |
| Modem    | 3         | 1.01%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 118       | 64.48%  |
| Ethernet | 65        | 35.52%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 99        | 56.25%  |
| 1     | 71        | 40.34%  |
| 0     | 5         | 2.84%   |
| 3     | 1         | 0.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 127       | 70.95%  |
| Yes  | 52        | 29.05%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 70        | 54.69%  |
| Apple                           | 10        | 7.81%   |
| Realtek Semiconductor           | 9         | 7.03%   |
| Qualcomm Atheros Communications | 8         | 6.25%   |
| Broadcom                        | 8         | 6.25%   |
| IMC Networks                    | 7         | 5.47%   |
| Foxconn / Hon Hai               | 3         | 2.34%   |
| Cambridge Silicon Radio         | 3         | 2.34%   |
| MediaTek                        | 2         | 1.56%   |
| Dell                            | 2         | 1.56%   |
| Smart Modular Technologies      | 1         | 0.78%   |
| Realtek                         | 1         | 0.78%   |
| Ralink                          | 1         | 0.78%   |
| Lite-On Technology              | 1         | 0.78%   |
| Hewlett-Packard                 | 1         | 0.78%   |
| Foxconn International           | 1         | 0.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 22        | 17.19%  |
| Intel AX201 Bluetooth                               | 17        | 13.28%  |
| Intel AX200 Bluetooth                               | 12        | 9.38%   |
| Realtek Bluetooth Radio                             | 5         | 3.91%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 3.91%   |
| Intel AX210 Bluetooth                               | 5         | 3.91%   |
| IMC Networks Wireless_Device                        | 5         | 3.91%   |
| Apple Bluetooth USB Host Controller                 | 5         | 3.91%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 3.13%   |
| Intel AX211 Bluetooth                               | 4         | 3.13%   |
| Apple Bluetooth Host Controller                     | 4         | 3.13%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 2.34%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 2.34%   |
| MediaTek Wireless_Device                            | 2         | 1.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 1.56%   |
| Dell DW375 Bluetooth Module                         | 2         | 1.56%   |
| Smart Modular Bluetooth Device                      | 1         | 0.78%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.78%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.78%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 0.78%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 0.78%   |
| Realtek Bluetooth Radio                             | 1         | 0.78%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.78%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.78%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.78%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.78%   |
| Lite-On Bluetooth Radio                             | 1         | 0.78%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.78%   |
| IMC Networks Bluetooth Radio                        | 1         | 0.78%   |
| IMC Networks Atheros AR3012 Bluetooth               | 1         | 0.78%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.78%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.78%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth         | 1         | 0.78%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 1         | 0.78%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.78%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 0.78%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 0.78%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 0.78%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.78%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 0.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 128       | 56.39%  |
| AMD                     | 47        | 20.7%   |
| Nvidia                  | 31        | 13.66%  |
| Plantronics             | 3         | 1.32%   |
| Logitech                | 3         | 1.32%   |
| GN Netcom               | 2         | 0.88%   |
| DSEA A/S                | 2         | 0.88%   |
| Texas Instruments       | 1         | 0.44%   |
| Shure                   | 1         | 0.44%   |
| Realtek Semiconductor   | 1         | 0.44%   |
| LINE TECH INDUSTRIAL    | 1         | 0.44%   |
| Lenovo                  | 1         | 0.44%   |
| Creative Technology     | 1         | 0.44%   |
| ClearOne Communications | 1         | 0.44%   |
| ASUSTek Computer        | 1         | 0.44%   |
| Arturia                 | 1         | 0.44%   |
| Apple                   | 1         | 0.44%   |
| AKAI Professional M.I.  | 1         | 0.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 25        | 9.12%   |
| Intel Sunrise Point-LP HD Audio                                            | 21        | 7.66%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 17        | 6.2%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 12        | 4.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 9         | 3.28%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 2.92%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8         | 2.92%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 7         | 2.55%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7         | 2.55%   |
| AMD FCH Azalia Controller                                                  | 7         | 2.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6         | 2.19%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 2.19%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6         | 2.19%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 5         | 1.82%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 1.82%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 1.82%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 1.46%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 1.46%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 1.46%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 4         | 1.46%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.09%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 1.09%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 1.09%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 1.09%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 3         | 1.09%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 1.09%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 1.09%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3         | 1.09%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 0.73%   |
| Nvidia MCP79 High Definition Audio                                         | 2         | 0.73%   |
| Nvidia GT216 HDMI Audio Controller                                         | 2         | 0.73%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.73%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2         | 0.73%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 2         | 0.73%   |
| Intel Jasper Lake HD Audio                                                 | 2         | 0.73%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 0.73%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 2         | 0.73%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 0.73%   |
| AMD Trinity HDMI Audio Controller                                          | 2         | 0.73%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 36        | 29.51%  |
| SK hynix            | 29        | 23.77%  |
| Kingston            | 14        | 11.48%  |
| Crucial             | 10        | 8.2%    |
| Micron Technology   | 9         | 7.38%   |
| Elpida              | 4         | 3.28%   |
| Unknown (ABCD)      | 3         | 2.46%   |
| Ramaxel Technology  | 2         | 1.64%   |
| Corsair             | 2         | 1.64%   |
| A-DATA Technology   | 2         | 1.64%   |
| Unknown             | 1         | 0.82%   |
| Transcend           | 1         | 0.82%   |
| Teikon              | 1         | 0.82%   |
| Nanya Technology    | 1         | 0.82%   |
| Magnum Tech         | 1         | 0.82%   |
| G.Skill             | 1         | 0.82%   |
| ff                  | 1         | 0.82%   |
| fef5                | 1         | 0.82%   |
| ChangXin Memory     | 1         | 0.82%   |
| 8945000080AD        | 1         | 0.82%   |
| 4ea5                | 1         | 0.82%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 4         | 3.08%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 3         | 2.31%   |
| Samsung RAM M471A2G44BM0-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 2.31%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 2.31%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.54%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 1.54%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 2         | 1.54%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 1.54%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.54%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.54%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.54%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s            | 2         | 1.54%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 2         | 1.54%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 1         | 0.77%   |
| Transcend RAM TS256MLK64V3U 2GB DIMM DDR3 1066MT/s               | 1         | 0.77%   |
| Teikon RAM TMT41GS6BFR8A-PBHJ 8GB SODIMM DDR3 1600MT/s           | 1         | 0.77%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.77%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2133MT/s                     | 1         | 0.77%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1067MT/s                     | 1         | 0.77%   |
| SK hynix RAM Module 4GB Row Of Chips LPDDR3 1867MT/s             | 1         | 0.77%   |
| SK hynix RAM Module 2GB Row Of Chips LPDDR5 6400MT/s             | 1         | 0.77%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s                       | 1         | 0.77%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 1         | 0.77%   |
| SK hynix RAM HMT851S6AMR6R-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.77%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.77%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 2667MT/s           | 1         | 0.77%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB Chip DDR3 1600MT/s             | 1         | 0.77%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.77%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.77%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.77%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.77%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.77%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 0.77%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.77%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.77%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.77%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 1         | 0.77%   |
| SK hynix RAM HMA41GR7AFR4N-UH 8GB DIMM DDR4 2400MT/s             | 1         | 0.77%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s       | 1         | 0.77%   |
| SK hynix RAM H9HCNNN8KUMLHR-NME 1GB LPDDR4 2400MT/s              | 1         | 0.77%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 54        | 52.43%  |
| DDR3    | 26        | 25.24%  |
| LPDDR4  | 13        | 12.62%  |
| LPDDR3  | 3         | 2.91%   |
| SDRAM   | 2         | 1.94%   |
| DDR5    | 2         | 1.94%   |
| LPDDR5  | 1         | 0.97%   |
| DRAM    | 1         | 0.97%   |
| Unknown | 1         | 0.97%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 72        | 71.29%  |
| DIMM         | 15        | 14.85%  |
| Row Of Chips | 10        | 9.9%    |
| Unknown      | 3         | 2.97%   |
| Chip         | 1         | 0.99%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 40        | 38.1%   |
| 4096  | 23        | 21.9%   |
| 16384 | 22        | 20.95%  |
| 2048  | 9         | 8.57%   |
| 32768 | 8         | 7.62%   |
| 1024  | 3         | 2.86%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 25        | 22.32%  |
| 1600  | 20        | 17.86%  |
| 2667  | 18        | 16.07%  |
| 2400  | 14        | 12.5%   |
| 2133  | 7         | 6.25%   |
| 1333  | 5         | 4.46%   |
| 4267  | 4         | 3.57%   |
| 1067  | 3         | 2.68%   |
| 1867  | 2         | 1.79%   |
| 1334  | 2         | 1.79%   |
| 1066  | 2         | 1.79%   |
| 6400  | 1         | 0.89%   |
| 6000  | 1         | 0.89%   |
| 4800  | 1         | 0.89%   |
| 4266  | 1         | 0.89%   |
| 4199  | 1         | 0.89%   |
| 3733  | 1         | 0.89%   |
| 3600  | 1         | 0.89%   |
| 3266  | 1         | 0.89%   |
| 3000  | 1         | 0.89%   |
| 2933  | 1         | 0.89%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 40%     |
| Samsung Electronics | 1         | 20%     |
| Dymo-CoStar         | 1         | 20%     |
| Canon               | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Samsung ML-1510 Laser Printer | 1         | 20%     |
| HP LaserJet 1320              | 1         | 20%     |
| HP DeskJet 3700 series        | 1         | 20%     |
| Dymo-CoStar LabelWriter 450   | 1         | 20%     |
| Canon LiDE 400                | 1         | 20%     |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 34        | 27.87%  |
| IMC Networks                           | 11        | 9.02%   |
| Realtek Semiconductor                  | 10        | 8.2%    |
| Microdia                               | 8         | 6.56%   |
| Apple                                  | 8         | 6.56%   |
| Sunplus Innovation Technology          | 7         | 5.74%   |
| Luxvisions Innotech Limited            | 6         | 4.92%   |
| Bison Electronics                      | 6         | 4.92%   |
| Quanta                                 | 5         | 4.1%    |
| Logitech                               | 5         | 4.1%    |
| Syntek                                 | 3         | 2.46%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.46%   |
| Samsung Electronics                    | 2         | 1.64%   |
| WaveRider Communications               | 1         | 0.82%   |
| ValueHD                                | 1         | 0.82%   |
| Unknown                                | 1         | 0.82%   |
| Suyin                                  | 1         | 0.82%   |
| Silicon Motion                         | 1         | 0.82%   |
| ShineTech                              | 1         | 0.82%   |
| Qtech                                  | 1         | 0.82%   |
| Polycom                                | 1         | 0.82%   |
| Pixart Imaging                         | 1         | 0.82%   |
| Generalplus Technology                 | 1         | 0.82%   |
| ALi                                    | 1         | 0.82%   |
| Alcor Micro                            | 1         | 0.82%   |
| Acer                                   | 1         | 0.82%   |
| Unknown                                | 1         | 0.82%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam             | 6         | 4.92%   |
| Realtek Integrated_Webcam_HD                  | 4         | 3.28%   |
| Microdia Integrated_Webcam_HD                 | 4         | 3.28%   |
| Chicony USB2.0 Camera                         | 4         | 3.28%   |
| Chicony Integrated Camera                     | 4         | 3.28%   |
| Chicony HP HD Camera                          | 4         | 3.28%   |
| Quanta USB2.0 HD UVC WebCam                   | 3         | 2.46%   |
| Logitech HD Pro Webcam C920                   | 3         | 2.46%   |
| IMC Networks Integrated Camera                | 3         | 2.46%   |
| Chicony Integrated IR Camera                  | 3         | 2.46%   |
| Chicony HD Webcam                             | 3         | 2.46%   |
| Bison SunplusIT Integrated Camera             | 3         | 2.46%   |
| Apple FaceTime HD Camera                      | 3         | 2.46%   |
| Apple Built-in iSight                         | 3         | 2.46%   |
| Syntek Integrated Camera                      | 2         | 1.64%   |
| Sunplus DICOTA 4K                             | 2         | 1.64%   |
| Samsung Galaxy series, misc. (MTP mode)       | 2         | 1.64%   |
| Luxvisions Innotech Limited Integrated Camera | 2         | 1.64%   |
| Luxvisions Innotech Limited HP HD Camera      | 2         | 1.64%   |
| Chicony USB2.0 VGA UVC WebCam                 | 2         | 1.64%   |
| Chicony USB2.0 0.3M UVC WebCam                | 2         | 1.64%   |
| Bison EasyCamera                              | 2         | 1.64%   |
| WaveRider USB 2.0 Camera                      | 1         | 0.82%   |
| ValueHD Konftel Cam20                         | 1         | 0.82%   |
| Unknown ATIV VGA CAMERA                       | 1         | 0.82%   |
| Syntek Lenovo EasyCamera                      | 1         | 0.82%   |
| Suyin HP Truevision HD                        | 1         | 0.82%   |
| Sunplus USB Camera                            | 1         | 0.82%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 1         | 0.82%   |
| Sunplus Integrated_Webcam_HD                  | 1         | 0.82%   |
| Sunplus Integrated Camera                     | 1         | 0.82%   |
| Sunplus HD WebCam                             | 1         | 0.82%   |
| Silicon Motion 300k Pixel Camera              | 1         | 0.82%   |
| ShineTech USB2.0 HD UVC WebCam                | 1         | 0.82%   |
| Realtek USB2.0 HD UVC WebCam                  | 1         | 0.82%   |
| Realtek USB2.0 camera                         | 1         | 0.82%   |
| Realtek USB Camera                            | 1         | 0.82%   |
| Realtek Lenovo EasyCamera                     | 1         | 0.82%   |
| Realtek Integrated Webcam HD                  | 1         | 0.82%   |
| Realtek Integrated Webcam                     | 1         | 0.82%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 10        | 37.04%  |
| Validity Sensors           | 8         | 29.63%  |
| Shenzhen Goodix Technology | 6         | 22.22%  |
| Elan Microelectronics      | 2         | 7.41%   |
| LighTuning Technology      | 1         | 3.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                | 4         | 14.81%  |
| Shenzhen Goodix  Fingerprint Device                       | 3         | 11.11%  |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 2         | 7.41%   |
| Shenzhen Goodix Fingerprint Reader                        | 2         | 7.41%   |
| Validity Sensors VFS301 Fingerprint Reader                | 1         | 3.7%    |
| Validity Sensors VFS 5011 fingerprint sensor              | 1         | 3.7%    |
| Validity Sensors Synaptics WBDI                           | 1         | 3.7%    |
| Validity Sensors Swipe Fingerprint Sensor                 | 1         | 3.7%    |
| Synaptics WBDI Fingerprint Reader USB 102                 | 1         | 3.7%    |
| Synaptics UWP WBDI Device                                 | 1         | 3.7%    |
| Synaptics TouchPad                                        | 1         | 3.7%    |
| Synaptics  WBDI                                           | 1         | 3.7%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 3.7%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 3.7%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 3.7%    |
| Shenzhen Goodix FingerPrint                               | 1         | 3.7%    |
| LighTuning ES603 Swipe Fingerprint Sensor                 | 1         | 3.7%    |
| Elan ELAN:Fingerprint                                     | 1         | 3.7%    |
| Elan ELAN:ARM-M4                                          | 1         | 3.7%    |
| Unknown                                                   | 1         | 3.7%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 3         | 60%     |
| Broadcom    | 2         | 40%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 3         | 60%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 20%     |
| Broadcom 5880                                  | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 120       | 67.04%  |
| 1     | 42        | 23.46%  |
| 2     | 13        | 7.26%   |
| 3     | 2         | 1.12%   |
| 7     | 1         | 0.56%   |
| 4     | 1         | 0.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 26        | 34.21%  |
| Graphics card            | 10        | 13.16%  |
| Net/wireless             | 9         | 11.84%  |
| Multimedia controller    | 5         | 6.58%   |
| Chipcard                 | 5         | 6.58%   |
| Sound                    | 4         | 5.26%   |
| Communication controller | 4         | 5.26%   |
| Camera                   | 4         | 5.26%   |
| Unassigned class         | 3         | 3.95%   |
| Bluetooth                | 3         | 3.95%   |
| Card reader              | 2         | 2.63%   |
| Net/ethernet             | 1         | 1.32%   |


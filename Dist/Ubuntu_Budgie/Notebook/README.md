Ubuntu Budgie - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu Budgie.

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

Total: 661

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Notebook      | N150CU                      | [348d0cab2d](https://linux-hardware.org/?probe=348d0cab2d) | May 07, 2024 |
| Sony          | SVS13A25PBS                 | [32dc3304ac](https://linux-hardware.org/?probe=32dc3304ac) | May 02, 2024 |
| HP            | Spectre Pro x360 G1         | [39577e6ab0](https://linux-hardware.org/?probe=39577e6ab0) | May 01, 2024 |
| HP            | Pavilion dv8                | [24eb3d99a9](https://linux-hardware.org/?probe=24eb3d99a9) | Apr 11, 2024 |
| Chuwi         | X312B                       | [3623330a1c](https://linux-hardware.org/?probe=3623330a1c) | Apr 09, 2024 |
| Chuwi         | X312B                       | [5aa107f741](https://linux-hardware.org/?probe=5aa107f741) | Apr 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [7bb2773966](https://linux-hardware.org/?probe=7bb2773966) | Apr 05, 2024 |
| Lenovo        | G50-45 80E3                 | [297eab2023](https://linux-hardware.org/?probe=297eab2023) | Mar 31, 2024 |
| Google        | Bobba                       | [d69b117fd0](https://linux-hardware.org/?probe=d69b117fd0) | Mar 30, 2024 |
| HP            | Dragonfly 13.5 inch G4 N... | [4b22ed6279](https://linux-hardware.org/?probe=4b22ed6279) | Mar 29, 2024 |
| Sony          | SVS13A25PBS                 | [6ee5930fa8](https://linux-hardware.org/?probe=6ee5930fa8) | Mar 27, 2024 |
| Packard Be... | EasyNote TM98               | [e6c48ef91f](https://linux-hardware.org/?probe=e6c48ef91f) | Mar 22, 2024 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [d337b27afc](https://linux-hardware.org/?probe=d337b27afc) | Mar 21, 2024 |
| HP            | ProBook 450 G1              | [3bfd1620fe](https://linux-hardware.org/?probe=3bfd1620fe) | Mar 12, 2024 |
| Dell          | Latitude 5480               | [5c3376ae97](https://linux-hardware.org/?probe=5c3376ae97) | Feb 29, 2024 |
| Apple         | MacBookPro6,2               | [a3b8064ddf](https://linux-hardware.org/?probe=a3b8064ddf) | Feb 29, 2024 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [4963c40308](https://linux-hardware.org/?probe=4963c40308) | Feb 27, 2024 |
| Apple         | MacBookPro6,2               | [fd9e5de8cf](https://linux-hardware.org/?probe=fd9e5de8cf) | Feb 22, 2024 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [29aa21542a](https://linux-hardware.org/?probe=29aa21542a) | Feb 22, 2024 |
| Dell          | Vostro 5625                 | [04e53619c6](https://linux-hardware.org/?probe=04e53619c6) | Feb 19, 2024 |
| TUXEDO        | InfinityBook_Pro13_14_v4    | [4264042062](https://linux-hardware.org/?probe=4264042062) | Feb 18, 2024 |
| ASUSTek       | G750JW                      | [1ba5260b50](https://linux-hardware.org/?probe=1ba5260b50) | Feb 13, 2024 |
| HP            | 15                          | [ef0b519e9b](https://linux-hardware.org/?probe=ef0b519e9b) | Feb 12, 2024 |
| TUXEDO        | InfinityBook S 15 Gen6      | [c80a1f64fc](https://linux-hardware.org/?probe=c80a1f64fc) | Jan 18, 2024 |
| Toshiba       | Satellite C855D-11X         | [d047649166](https://linux-hardware.org/?probe=d047649166) | Jan 14, 2024 |
| Alurin        | ALU-LPT-N4020-8256-140      | [61fdeffbaf](https://linux-hardware.org/?probe=61fdeffbaf) | Jan 12, 2024 |
| TUXEDO        | Pulse 14 Gen1               | [66efe29bec](https://linux-hardware.org/?probe=66efe29bec) | Jan 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [d041e87729](https://linux-hardware.org/?probe=d041e87729) | Jan 09, 2024 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | [0bc6f72a01](https://linux-hardware.org/?probe=0bc6f72a01) | Jan 09, 2024 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | [cce2fde2ac](https://linux-hardware.org/?probe=cce2fde2ac) | Jan 08, 2024 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | [fd3f275cfb](https://linux-hardware.org/?probe=fd3f275cfb) | Jan 07, 2024 |
| Apple         | MacBookPro8,3               | [b1467995b6](https://linux-hardware.org/?probe=b1467995b6) | Jan 06, 2024 |
| Lenovo        | ThinkPad X220 4291G75       | [1192d8e746](https://linux-hardware.org/?probe=1192d8e746) | Dec 27, 2023 |
| Lenovo        | ThinkPad X220 4291G75       | [3fdb3a1cc7](https://linux-hardware.org/?probe=3fdb3a1cc7) | Dec 27, 2023 |
| Toshiba       | Satellite A300              | [5e373b58ac](https://linux-hardware.org/?probe=5e373b58ac) | Dec 15, 2023 |
| ASUSTek       | E403SA                      | [141030490c](https://linux-hardware.org/?probe=141030490c) | Dec 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [ddfffa5172](https://linux-hardware.org/?probe=ddfffa5172) | Dec 08, 2023 |
| Sony          | VPCW216AG                   | [fb60613609](https://linux-hardware.org/?probe=fb60613609) | Dec 08, 2023 |
| Unknown       | Unknown                     | [00756344be](https://linux-hardware.org/?probe=00756344be) | Nov 25, 2023 |
| Lenovo        | ThinkPad X260 20F5S0V500    | [a293b54992](https://linux-hardware.org/?probe=a293b54992) | Nov 24, 2023 |
| HP            | ZBook 17 G3                 | [5f26bd4798](https://linux-hardware.org/?probe=5f26bd4798) | Nov 21, 2023 |
| HP            | ZBook 17 G3                 | [ed1bde2ed6](https://linux-hardware.org/?probe=ed1bde2ed6) | Nov 20, 2023 |
| Dell          | Vostro 15 3510              | [9c0b7c2706](https://linux-hardware.org/?probe=9c0b7c2706) | Nov 15, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | [5efa262121](https://linux-hardware.org/?probe=5efa262121) | Nov 14, 2023 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [7736f94150](https://linux-hardware.org/?probe=7736f94150) | Nov 13, 2023 |
| Lenovo        | G50-45 80E3                 | [51f7d5e2dc](https://linux-hardware.org/?probe=51f7d5e2dc) | Nov 09, 2023 |
| Lenovo        | G50-45 80E3                 | [0a23b4526a](https://linux-hardware.org/?probe=0a23b4526a) | Nov 09, 2023 |
| Lenovo        | ThinkPad X260 20F5S0V500    | [143fa66e87](https://linux-hardware.org/?probe=143fa66e87) | Nov 08, 2023 |
| HONOR         | GLO-GXXX                    | [c6d6619fd9](https://linux-hardware.org/?probe=c6d6619fd9) | Nov 06, 2023 |
| Lenovo        | G50-45 80E3                 | [2ac9878b30](https://linux-hardware.org/?probe=2ac9878b30) | Nov 05, 2023 |
| Acer          | Aspire A515-57              | [532db79d07](https://linux-hardware.org/?probe=532db79d07) | Nov 05, 2023 |
| Lenovo        | G50-45 80E3                 | [a816b34b9e](https://linux-hardware.org/?probe=a816b34b9e) | Nov 03, 2023 |
| Dell          | Latitude E5470              | [b1be043dc0](https://linux-hardware.org/?probe=b1be043dc0) | Oct 31, 2023 |
| Sony          | SVS13A25PBS                 | [7cb087bd2d](https://linux-hardware.org/?probe=7cb087bd2d) | Oct 27, 2023 |
| Toshiba       | Satellite C650              | [5236a2eca3](https://linux-hardware.org/?probe=5236a2eca3) | Oct 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [47186b8e71](https://linux-hardware.org/?probe=47186b8e71) | Oct 24, 2023 |
| Lenovo        | G50-45 80E3                 | [41f9f44ee1](https://linux-hardware.org/?probe=41f9f44ee1) | Oct 20, 2023 |
| Lenovo        | G50-45 80E3                 | [98f1b28357](https://linux-hardware.org/?probe=98f1b28357) | Oct 20, 2023 |
| IMUZ          | STORMBOOK14 APOLLO          | [6d8e8178b0](https://linux-hardware.org/?probe=6d8e8178b0) | Oct 19, 2023 |
| Google        | Kled                        | [4d546b71e7](https://linux-hardware.org/?probe=4d546b71e7) | Oct 17, 2023 |
| Gateway       | NV59C                       | [5a0c4e72d6](https://linux-hardware.org/?probe=5a0c4e72d6) | Oct 16, 2023 |
| HP            | EliteBook 840 G2            | [3055b32637](https://linux-hardware.org/?probe=3055b32637) | Oct 15, 2023 |
| HP            | Pavilion dv7                | [feb4113e4e](https://linux-hardware.org/?probe=feb4113e4e) | Oct 15, 2023 |
| HP            | Pavilion dv7                | [6bb631736f](https://linux-hardware.org/?probe=6bb631736f) | Oct 15, 2023 |
| HP            | Laptop 15-fc0xxx            | [c2205d1cf2](https://linux-hardware.org/?probe=c2205d1cf2) | Oct 10, 2023 |
| HP            | EliteBook 840 G2            | [a90e584705](https://linux-hardware.org/?probe=a90e584705) | Oct 04, 2023 |
| ASUSTek       | UX303UA                     | [657233bb53](https://linux-hardware.org/?probe=657233bb53) | Oct 02, 2023 |
| HONOR         | HLYL-WXX9                   | [5a440c873d](https://linux-hardware.org/?probe=5a440c873d) | Oct 01, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [73b5907f17](https://linux-hardware.org/?probe=73b5907f17) | Sep 30, 2023 |
| Apple         | MacBookPro15,2              | [1331a57778](https://linux-hardware.org/?probe=1331a57778) | Sep 27, 2023 |
| COM1          | NBINF-X5-9G5                | [919d36ddd8](https://linux-hardware.org/?probe=919d36ddd8) | Sep 24, 2023 |
| Acer          | Aspire 7530G                | [37d34804dd](https://linux-hardware.org/?probe=37d34804dd) | Sep 22, 2023 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [9a1d56bda1](https://linux-hardware.org/?probe=9a1d56bda1) | Sep 20, 2023 |
| Gateway       | NV59C                       | [0885dc9384](https://linux-hardware.org/?probe=0885dc9384) | Sep 16, 2023 |
| Dell          | Latitude 7280               | [ecca4887d5](https://linux-hardware.org/?probe=ecca4887d5) | Sep 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [312d4a06dc](https://linux-hardware.org/?probe=312d4a06dc) | Sep 05, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [40c7e7f27b](https://linux-hardware.org/?probe=40c7e7f27b) | Aug 31, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [f09b86405b](https://linux-hardware.org/?probe=f09b86405b) | Aug 26, 2023 |
| Lenovo        | G50-45 80E3                 | [044deb0ad2](https://linux-hardware.org/?probe=044deb0ad2) | Aug 22, 2023 |
| ASUSTek       | UX303UA                     | [a34dfca1e3](https://linux-hardware.org/?probe=a34dfca1e3) | Aug 14, 2023 |
| ASUSTek       | X550CC                      | [934ab444f2](https://linux-hardware.org/?probe=934ab444f2) | Aug 07, 2023 |
| ASUSTek       | X550CC                      | [3f8e9bffbd](https://linux-hardware.org/?probe=3f8e9bffbd) | Aug 05, 2023 |
| Dell          | Latitude 7490               | [73efa45f4f](https://linux-hardware.org/?probe=73efa45f4f) | Aug 05, 2023 |
| Dell          | Latitude 7490               | [ce0e015b6e](https://linux-hardware.org/?probe=ce0e015b6e) | Aug 05, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [e97688a8c1](https://linux-hardware.org/?probe=e97688a8c1) | Jul 27, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [7466fce2a2](https://linux-hardware.org/?probe=7466fce2a2) | Jul 18, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [cabc9a2940](https://linux-hardware.org/?probe=cabc9a2940) | Jul 15, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [ce4fed4466](https://linux-hardware.org/?probe=ce4fed4466) | Jul 08, 2023 |
| Lenovo        | ThinkPad X260 20F5S0V500    | [760a6712db](https://linux-hardware.org/?probe=760a6712db) | Jul 07, 2023 |
| HP            | EliteBook 840 G3            | [95fa9e14bf](https://linux-hardware.org/?probe=95fa9e14bf) | Jul 07, 2023 |
| Lenovo        | ThinkPad T550 20CK000GCA    | [3e7598da34](https://linux-hardware.org/?probe=3e7598da34) | Jul 04, 2023 |
| Dell          | Latitude 5420               | [dedd6c842c](https://linux-hardware.org/?probe=dedd6c842c) | Jul 04, 2023 |
| Dell          | Latitude 5420               | [dfe3274d7e](https://linux-hardware.org/?probe=dfe3274d7e) | Jul 03, 2023 |
| Lenovo        | G50-45 80E3                 | [aae865deb7](https://linux-hardware.org/?probe=aae865deb7) | Jul 02, 2023 |
| Lenovo        | G50-45 80E3                 | [89db1a9656](https://linux-hardware.org/?probe=89db1a9656) | Jul 02, 2023 |
| HP            | Pavilion Gaming Notebook    | [0e9e13c4b5](https://linux-hardware.org/?probe=0e9e13c4b5) | Jul 02, 2023 |
| BANGHO        | BES G0304                   | [7b9e2a7570](https://linux-hardware.org/?probe=7b9e2a7570) | Jun 30, 2023 |
| HUAWEI        | HKD-WXX                     | [433d7b4f7e](https://linux-hardware.org/?probe=433d7b4f7e) | Jun 24, 2023 |
| HP            | 250 G6 Notebook PC          | [7cc301b3f7](https://linux-hardware.org/?probe=7cc301b3f7) | Jun 21, 2023 |
| HP            | 250 G6 Notebook PC          | [1ba2e18bc1](https://linux-hardware.org/?probe=1ba2e18bc1) | Jun 21, 2023 |
| Apple         | MacBookPro9,2               | [544b40258b](https://linux-hardware.org/?probe=544b40258b) | Jun 21, 2023 |
| HUAWEI        | MACHD-WXX9                  | [f87fe0fe34](https://linux-hardware.org/?probe=f87fe0fe34) | Jun 08, 2023 |
| ASUSTek       | UX303UA                     | [41514924ed](https://linux-hardware.org/?probe=41514924ed) | Jun 04, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [3903b22ffd](https://linux-hardware.org/?probe=3903b22ffd) | Jun 02, 2023 |
| HP            | Notebook                    | [c246477ea2](https://linux-hardware.org/?probe=c246477ea2) | May 31, 2023 |
| Dell          | XPS 13 9310                 | [d12d9a4fc2](https://linux-hardware.org/?probe=d12d9a4fc2) | May 29, 2023 |
| Unknown       | Unknown                     | [b63a3cbd7b](https://linux-hardware.org/?probe=b63a3cbd7b) | May 25, 2023 |
| Unknown       | Unknown                     | [3db7516231](https://linux-hardware.org/?probe=3db7516231) | May 25, 2023 |
| Dell          | Latitude 5521               | [b33afe1463](https://linux-hardware.org/?probe=b33afe1463) | May 25, 2023 |
| TUXEDO        | InfinityBook Pro 14 v4      | [51c520b6e6](https://linux-hardware.org/?probe=51c520b6e6) | May 25, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | [e484eaf025](https://linux-hardware.org/?probe=e484eaf025) | May 24, 2023 |
| Apple         | MacBookAir6,2               | [5a0f8e19ee](https://linux-hardware.org/?probe=5a0f8e19ee) | May 19, 2023 |
| TUXEDO        | InfinityBook Pro 14 v4      | [741d6fe6d2](https://linux-hardware.org/?probe=741d6fe6d2) | May 19, 2023 |
| HP            | Bloog                       | [4673a7630e](https://linux-hardware.org/?probe=4673a7630e) | May 16, 2023 |
| HP            | Bloog                       | [1c91d5ef51](https://linux-hardware.org/?probe=1c91d5ef51) | May 16, 2023 |
| Dell          | Latitude E5420              | [571765685f](https://linux-hardware.org/?probe=571765685f) | May 14, 2023 |
| TUXEDO        | Book XP1511                 | [37a17568a0](https://linux-hardware.org/?probe=37a17568a0) | May 11, 2023 |
| Unknown       | Unknown                     | [9ed744299a](https://linux-hardware.org/?probe=9ed744299a) | May 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [8a80fd7103](https://linux-hardware.org/?probe=8a80fd7103) | May 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [3198c997b2](https://linux-hardware.org/?probe=3198c997b2) | May 04, 2023 |
| Dell          | Latitude E6420              | [7a26c45568](https://linux-hardware.org/?probe=7a26c45568) | May 04, 2023 |
| HP            | EliteBook 2540p             | [a0b1299baa](https://linux-hardware.org/?probe=a0b1299baa) | May 02, 2023 |
| Acer          | Aspire A317-53              | [612ab58d3f](https://linux-hardware.org/?probe=612ab58d3f) | May 02, 2023 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [8a7ed180c0](https://linux-hardware.org/?probe=8a7ed180c0) | May 02, 2023 |
| Dell          | Latitude E5420              | [df8c9e7f40](https://linux-hardware.org/?probe=df8c9e7f40) | Apr 30, 2023 |
| HP            | EliteBook Folio 1040 G3     | [b3ac75c53e](https://linux-hardware.org/?probe=b3ac75c53e) | Apr 30, 2023 |
| Lenovo        | B50-30 80ES                 | [d84727b8e4](https://linux-hardware.org/?probe=d84727b8e4) | Apr 29, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [b402183807](https://linux-hardware.org/?probe=b402183807) | Apr 24, 2023 |
| Acer          | Swift SF314-42              | [2508f138a4](https://linux-hardware.org/?probe=2508f138a4) | Apr 23, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [090405a4a7](https://linux-hardware.org/?probe=090405a4a7) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [7afa5cded3](https://linux-hardware.org/?probe=7afa5cded3) | Apr 18, 2023 |
| Lenovo        | ThinkPad T480s 20L8SF1X0... | [d567c29052](https://linux-hardware.org/?probe=d567c29052) | Apr 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [19fc60d2a5](https://linux-hardware.org/?probe=19fc60d2a5) | Apr 14, 2023 |
| ASUSTek       | UX303UA                     | [6e9b87d6e1](https://linux-hardware.org/?probe=6e9b87d6e1) | Apr 11, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [683d3101d8](https://linux-hardware.org/?probe=683d3101d8) | Mar 31, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [1c517ff300](https://linux-hardware.org/?probe=1c517ff300) | Mar 27, 2023 |
| Dell          | Inspiron 3543               | [d714304a67](https://linux-hardware.org/?probe=d714304a67) | Mar 27, 2023 |
| Dell          | Inspiron 3543               | [f733f5b792](https://linux-hardware.org/?probe=f733f5b792) | Mar 27, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [8701ff9985](https://linux-hardware.org/?probe=8701ff9985) | Mar 26, 2023 |
| MSI           | Alpha 15 B5EEK              | [03f3f846eb](https://linux-hardware.org/?probe=03f3f846eb) | Mar 24, 2023 |
| HP            | ZBook 15 G4                 | [ebd974c40f](https://linux-hardware.org/?probe=ebd974c40f) | Mar 23, 2023 |
| Dell          | Latitude 7480               | [0301ad09f6](https://linux-hardware.org/?probe=0301ad09f6) | Mar 23, 2023 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [a3339e152a](https://linux-hardware.org/?probe=a3339e152a) | Mar 18, 2023 |
| ASUSTek       | X555LAB                     | [18bf88d413](https://linux-hardware.org/?probe=18bf88d413) | Mar 17, 2023 |
| Apple         | MacBookPro11,3              | [1ade706194](https://linux-hardware.org/?probe=1ade706194) | Mar 17, 2023 |
| Apple         | MacBookPro11,3              | [45537ae306](https://linux-hardware.org/?probe=45537ae306) | Mar 17, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [a7d30f68b1](https://linux-hardware.org/?probe=a7d30f68b1) | Mar 12, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [d7ed4aaf2c](https://linux-hardware.org/?probe=d7ed4aaf2c) | Mar 11, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [6e97141469](https://linux-hardware.org/?probe=6e97141469) | Mar 10, 2023 |
| ASUSTek       | K52F                        | [8fa6eaf7cf](https://linux-hardware.org/?probe=8fa6eaf7cf) | Mar 10, 2023 |
| MSI           | Raider GE76 12UE            | [b78033fddd](https://linux-hardware.org/?probe=b78033fddd) | Mar 08, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [8a70478523](https://linux-hardware.org/?probe=8a70478523) | Mar 06, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [6e08a2dcf9](https://linux-hardware.org/?probe=6e08a2dcf9) | Mar 06, 2023 |
| HP            | ZBook 15 G4                 | [38a0ce48ed](https://linux-hardware.org/?probe=38a0ce48ed) | Mar 04, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [ceb6fb20b2](https://linux-hardware.org/?probe=ceb6fb20b2) | Mar 02, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [b80c1e685f](https://linux-hardware.org/?probe=b80c1e685f) | Feb 26, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [e3578290d2](https://linux-hardware.org/?probe=e3578290d2) | Feb 25, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [6b2160527d](https://linux-hardware.org/?probe=6b2160527d) | Feb 23, 2023 |
| Lenovo        | ThinkPad T440p 20AWS08S0... | [2daf635e15](https://linux-hardware.org/?probe=2daf635e15) | Feb 18, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [12f305c12f](https://linux-hardware.org/?probe=12f305c12f) | Feb 17, 2023 |
| Google        | Boten                       | [5562b4af15](https://linux-hardware.org/?probe=5562b4af15) | Feb 11, 2023 |
| Google        | Boten                       | [d07e5295bb](https://linux-hardware.org/?probe=d07e5295bb) | Feb 11, 2023 |
| HP            | Laptop 14-cm0xxx            | [5dfc3e2280](https://linux-hardware.org/?probe=5dfc3e2280) | Feb 08, 2023 |
| Apple         | MacBookAir7,2               | [b5f0169944](https://linux-hardware.org/?probe=b5f0169944) | Jan 28, 2023 |
| Dell          | Latitude E6420              | [a772965137](https://linux-hardware.org/?probe=a772965137) | Jan 27, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | [ee44dc2539](https://linux-hardware.org/?probe=ee44dc2539) | Jan 27, 2023 |
| HP            | ProBook 450 G7              | [1d507a3cdc](https://linux-hardware.org/?probe=1d507a3cdc) | Jan 27, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | [7bf2d60c0b](https://linux-hardware.org/?probe=7bf2d60c0b) | Jan 21, 2023 |
| Google        | Banjo                       | [30a528ac6b](https://linux-hardware.org/?probe=30a528ac6b) | Jan 14, 2023 |
| Google        | Banjo                       | [66dc97b0de](https://linux-hardware.org/?probe=66dc97b0de) | Jan 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [d83005eb10](https://linux-hardware.org/?probe=d83005eb10) | Jan 03, 2023 |
| TUXEDO        | Polaris (CML/Gen2)          | [a14e00ab97](https://linux-hardware.org/?probe=a14e00ab97) | Dec 29, 2022 |
| TUXEDO        | Polaris (CML/Gen2)          | [00e25b3232](https://linux-hardware.org/?probe=00e25b3232) | Dec 29, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [2d653884d9](https://linux-hardware.org/?probe=2d653884d9) | Dec 29, 2022 |
| Dell          | System XPS L502X            | [db4f93ae82](https://linux-hardware.org/?probe=db4f93ae82) | Dec 22, 2022 |
| MSI           | GL65 Leopard 10SDK          | [2c6e6ec3ec](https://linux-hardware.org/?probe=2c6e6ec3ec) | Dec 21, 2022 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | [7da34e4f7f](https://linux-hardware.org/?probe=7da34e4f7f) | Dec 14, 2022 |
| HP            | ProBook 445 G7              | [b34265fdbe](https://linux-hardware.org/?probe=b34265fdbe) | Dec 14, 2022 |
| Unknown       | Unknown                     | [a6efa9c8ab](https://linux-hardware.org/?probe=a6efa9c8ab) | Dec 12, 2022 |
| Unknown       | Unknown                     | [b9b1bab552](https://linux-hardware.org/?probe=b9b1bab552) | Dec 12, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [ea74cd284c](https://linux-hardware.org/?probe=ea74cd284c) | Dec 08, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [bdc64a5196](https://linux-hardware.org/?probe=bdc64a5196) | Dec 02, 2022 |
| THUNDEROBO... | 911MT                       | [40111c09eb](https://linux-hardware.org/?probe=40111c09eb) | Dec 01, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [615b292682](https://linux-hardware.org/?probe=615b292682) | Dec 01, 2022 |
| THUNDEROBO... | 911MT                       | [cdd03a3498](https://linux-hardware.org/?probe=cdd03a3498) | Dec 01, 2022 |
| THUNDEROBO... | 911MT                       | [2731961e4c](https://linux-hardware.org/?probe=2731961e4c) | Nov 30, 2022 |
| Dell          | Inspiron 5566               | [a130766490](https://linux-hardware.org/?probe=a130766490) | Nov 29, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [be7a4a88a1](https://linux-hardware.org/?probe=be7a4a88a1) | Nov 23, 2022 |
| Sony          | VPCEA45FG                   | [cb719dbd60](https://linux-hardware.org/?probe=cb719dbd60) | Nov 19, 2022 |
| MSI           | GL65 Leopard 10SFKV         | [84668eb3a8](https://linux-hardware.org/?probe=84668eb3a8) | Nov 16, 2022 |
| MSI           | GL65 Leopard 10SFKV         | [316e275c13](https://linux-hardware.org/?probe=316e275c13) | Nov 16, 2022 |
| Thomson       | N17V3C8WH512                | [f13487a2f3](https://linux-hardware.org/?probe=f13487a2f3) | Nov 07, 2022 |
| Thomson       | N17V3C8WH512                | [58d6a21b17](https://linux-hardware.org/?probe=58d6a21b17) | Nov 06, 2022 |
| ASUSTek       | UX303UA                     | [751669286c](https://linux-hardware.org/?probe=751669286c) | Nov 05, 2022 |
| Dell          | XPS 13 9310                 | [104082422f](https://linux-hardware.org/?probe=104082422f) | Nov 04, 2022 |
| Dell          | XPS 13 9310                 | [2f2963b2fc](https://linux-hardware.org/?probe=2f2963b2fc) | Nov 04, 2022 |
| Razer         | Blade 15 Advanced Model ... | [e0a589194b](https://linux-hardware.org/?probe=e0a589194b) | Nov 01, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | [b401e89d9c](https://linux-hardware.org/?probe=b401e89d9c) | Oct 31, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | [4650c9df06](https://linux-hardware.org/?probe=4650c9df06) | Oct 31, 2022 |
| Sony          | VPCEA45FG                   | [26a8adcee2](https://linux-hardware.org/?probe=26a8adcee2) | Oct 31, 2022 |
| Sony          | VPCEA45FG                   | [3448172ca3](https://linux-hardware.org/?probe=3448172ca3) | Oct 29, 2022 |
| TUXEDO        | Aura 15 Gen1                | [4055c79756](https://linux-hardware.org/?probe=4055c79756) | Oct 28, 2022 |
| Toshiba       | Satellite A505              | [41dafcbfb9](https://linux-hardware.org/?probe=41dafcbfb9) | Oct 25, 2022 |
| ASUSTek       | X205TA                      | [2da58f110d](https://linux-hardware.org/?probe=2da58f110d) | Oct 24, 2022 |
| TUXEDO        | Polaris (CML/Gen2)          | [3cb2ce5a02](https://linux-hardware.org/?probe=3cb2ce5a02) | Oct 24, 2022 |
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
| TUXEDO        | InfinityBook Pro 14 v4      | [cc583599ef](https://linux-hardware.org/?probe=cc583599ef) | Aug 28, 2022 |
| Google        | Rabbid                      | [8049c3894c](https://linux-hardware.org/?probe=8049c3894c) | Aug 24, 2022 |
| Lenovo        | G500 20236                  | [45df8f9be9](https://linux-hardware.org/?probe=45df8f9be9) | Aug 18, 2022 |
| Lenovo        | G500 20236                  | [6974cf32ce](https://linux-hardware.org/?probe=6974cf32ce) | Aug 17, 2022 |
| Acer          | TravelMate P653-M           | [1e33abf031](https://linux-hardware.org/?probe=1e33abf031) | Aug 17, 2022 |
| TUXEDO        | Book XUX7 Gen11             | [ecf8be45de](https://linux-hardware.org/?probe=ecf8be45de) | Aug 16, 2022 |
| TUXEDO        | Book XUX7 Gen11             | [c5c7e42e91](https://linux-hardware.org/?probe=c5c7e42e91) | Aug 16, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [5d50a29ca9](https://linux-hardware.org/?probe=5d50a29ca9) | Aug 13, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | [8c6f00600e](https://linux-hardware.org/?probe=8c6f00600e) | Aug 12, 2022 |
| Dell          | Inspiron 3793               | [15f2e25089](https://linux-hardware.org/?probe=15f2e25089) | Jul 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [e82d2e1076](https://linux-hardware.org/?probe=e82d2e1076) | Jul 28, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [2a95697c62](https://linux-hardware.org/?probe=2a95697c62) | Jul 25, 2022 |
| Alienware     | M11xR3                      | [e479dcdefb](https://linux-hardware.org/?probe=e479dcdefb) | Jul 22, 2022 |
| HP            | EliteBook 840 G3            | [e34f81fcfa](https://linux-hardware.org/?probe=e34f81fcfa) | Jul 18, 2022 |
| MSI           | GE75 Raider 10SE            | [d2ed25b6e8](https://linux-hardware.org/?probe=d2ed25b6e8) | Jul 16, 2022 |
| TUXEDO        | InfinityBook_Pro13_14_v4    | [f1dcf09169](https://linux-hardware.org/?probe=f1dcf09169) | Jul 14, 2022 |
| Lenovo        | ThinkPad T500 2242CTO       | [47bddb4e10](https://linux-hardware.org/?probe=47bddb4e10) | Jul 10, 2022 |
| HP            | ENVY 17                     | [2d97952e56](https://linux-hardware.org/?probe=2d97952e56) | Jul 08, 2022 |
| Dell          | Latitude E7450              | [34913911ca](https://linux-hardware.org/?probe=34913911ca) | Jul 05, 2022 |
| Dell          | Latitude E7450              | [60e633e563](https://linux-hardware.org/?probe=60e633e563) | Jul 04, 2022 |
| Positivo      | Q232A                       | [c297e38afb](https://linux-hardware.org/?probe=c297e38afb) | Jun 27, 2022 |
| Positivo      | Q232A                       | [8774fcf3a2](https://linux-hardware.org/?probe=8774fcf3a2) | Jun 27, 2022 |
| Acer          | Aspire E5-573G              | [9f14a273b0](https://linux-hardware.org/?probe=9f14a273b0) | Jun 26, 2022 |
| Lenovo        | ThinkPad T400 6475AT3       | [55fd247328](https://linux-hardware.org/?probe=55fd247328) | Jun 26, 2022 |
| HP            | ElitePad 1000 G2            | [e478f31175](https://linux-hardware.org/?probe=e478f31175) | Jun 25, 2022 |
| MSI           | GL62 6QF                    | [39e2d35166](https://linux-hardware.org/?probe=39e2d35166) | Jun 20, 2022 |
| Timi          | TM1604                      | [2f45cc25b4](https://linux-hardware.org/?probe=2f45cc25b4) | Jun 20, 2022 |
| HP            | Pavilion dv7                | [add98928e5](https://linux-hardware.org/?probe=add98928e5) | Jun 18, 2022 |
| HP            | Pavilion dv7                | [bfecf091a6](https://linux-hardware.org/?probe=bfecf091a6) | Jun 18, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [d4ad64d715](https://linux-hardware.org/?probe=d4ad64d715) | Jun 15, 2022 |
| ASUSTek       | X555LAB                     | [8e47a3c188](https://linux-hardware.org/?probe=8e47a3c188) | Jun 10, 2022 |
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
| Lenovo        | IdeaPad 330-15IKB 81DE      | [4f2714e3fe](https://linux-hardware.org/?probe=4f2714e3fe) | May 04, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [ff291ff9e3](https://linux-hardware.org/?probe=ff291ff9e3) | May 03, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [0c5f20e02c](https://linux-hardware.org/?probe=0c5f20e02c) | May 02, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [0d006e41fc](https://linux-hardware.org/?probe=0d006e41fc) | May 01, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [6ace557278](https://linux-hardware.org/?probe=6ace557278) | Apr 29, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [ef265ae548](https://linux-hardware.org/?probe=ef265ae548) | Apr 29, 2022 |
| Sony          | SVS13A25PBS                 | [c1be74b619](https://linux-hardware.org/?probe=c1be74b619) | Apr 25, 2022 |
| Acer          | Swift SF315-52              | [089d81a936](https://linux-hardware.org/?probe=089d81a936) | Apr 23, 2022 |
| Apple         | MacBookPro9,2               | [967eac195b](https://linux-hardware.org/?probe=967eac195b) | Apr 23, 2022 |
| Dell          | XPS 13 9305                 | [51daefb9d3](https://linux-hardware.org/?probe=51daefb9d3) | Apr 22, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [3b76e2f5ab](https://linux-hardware.org/?probe=3b76e2f5ab) | Apr 21, 2022 |
| Lenovo        | ThinkPad T430s 2356H83      | [714396bc62](https://linux-hardware.org/?probe=714396bc62) | Apr 20, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [70547d6581](https://linux-hardware.org/?probe=70547d6581) | Apr 19, 2022 |
| TUXEDO        | Stellaris Intel Gen3 (TG... | [c1a5e02fa5](https://linux-hardware.org/?probe=c1a5e02fa5) | Apr 17, 2022 |
| Acer          | Swift SF114-34              | [ca66ed7272](https://linux-hardware.org/?probe=ca66ed7272) | Apr 14, 2022 |
| Dell          | Inspiron 5570               | [a75a1551fa](https://linux-hardware.org/?probe=a75a1551fa) | Apr 09, 2022 |
| Alienware     | m15                         | [0cd462faaa](https://linux-hardware.org/?probe=0cd462faaa) | Apr 07, 2022 |
| Lenovo        | ThinkPad E490 20N9001MBR    | [1b041100a3](https://linux-hardware.org/?probe=1b041100a3) | Apr 07, 2022 |
| TUXEDO        | Aura 15 Gen1                | [cda73dafa0](https://linux-hardware.org/?probe=cda73dafa0) | Apr 04, 2022 |
| TUXEDO        | InfinityBook S 14 v5        | [6a5061e741](https://linux-hardware.org/?probe=6a5061e741) | Apr 03, 2022 |
| Dell          | Inspiron 14 5401            | [995691e022](https://linux-hardware.org/?probe=995691e022) | Apr 01, 2022 |
| TUXEDO        | InfinityBook S 14 Gen6      | [847b8f0788](https://linux-hardware.org/?probe=847b8f0788) | Apr 01, 2022 |
| Packard Be... | ENLE11BZ                    | [4fb836698c](https://linux-hardware.org/?probe=4fb836698c) | Mar 26, 2022 |
| ASUSTek       | G752VY                      | [2b82008ffc](https://linux-hardware.org/?probe=2b82008ffc) | Mar 23, 2022 |
| Apple         | MacBookPro15,1              | [0fe3cba205](https://linux-hardware.org/?probe=0fe3cba205) | Mar 23, 2022 |
| ASUSTek       | G752VY                      | [ffc0cdf0bd](https://linux-hardware.org/?probe=ffc0cdf0bd) | Mar 22, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [63ea3e99c5](https://linux-hardware.org/?probe=63ea3e99c5) | Mar 14, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [08525a320d](https://linux-hardware.org/?probe=08525a320d) | Mar 13, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | [b61991cef4](https://linux-hardware.org/?probe=b61991cef4) | Mar 13, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [22452f39c2](https://linux-hardware.org/?probe=22452f39c2) | Mar 11, 2022 |
| HP            | ZBook 15u G6                | [42921aebfd](https://linux-hardware.org/?probe=42921aebfd) | Mar 10, 2022 |
| MSI           | Vector GP66 12UGS           | [be60e729e2](https://linux-hardware.org/?probe=be60e729e2) | Mar 06, 2022 |
| HP            | Pavilion dm4                | [4786fbfbdd](https://linux-hardware.org/?probe=4786fbfbdd) | Mar 04, 2022 |
| HP            | Pavilion dm4                | [8adb026a31](https://linux-hardware.org/?probe=8adb026a31) | Mar 04, 2022 |
| Google        | Rammus                      | [a326a69db9](https://linux-hardware.org/?probe=a326a69db9) | Mar 02, 2022 |
| Google        | Rammus                      | [b395780983](https://linux-hardware.org/?probe=b395780983) | Mar 02, 2022 |
| Apple         | MacBookAir7,2               | [34da56b567](https://linux-hardware.org/?probe=34da56b567) | Mar 01, 2022 |
| ASUSTek       | UX303UA                     | [0ed28fa881](https://linux-hardware.org/?probe=0ed28fa881) | Feb 23, 2022 |
| HP            | Compaq Presario C700        | [52cff70be5](https://linux-hardware.org/?probe=52cff70be5) | Feb 21, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | [e58eb70913](https://linux-hardware.org/?probe=e58eb70913) | Feb 19, 2022 |
| ASUSTek       | T200TAC                     | [20834c0dba](https://linux-hardware.org/?probe=20834c0dba) | Feb 17, 2022 |
| TUXEDO        | Aura 15 Gen1                | [536a1e49b0](https://linux-hardware.org/?probe=536a1e49b0) | Feb 17, 2022 |
| Samsung       | 305V4A/305V5A               | [07233a144c](https://linux-hardware.org/?probe=07233a144c) | Feb 09, 2022 |
| Lenovo        | G500 20236                  | [2dd47c0a4b](https://linux-hardware.org/?probe=2dd47c0a4b) | Feb 08, 2022 |
| Viglen        | VUB1                        | [13f512e2d1](https://linux-hardware.org/?probe=13f512e2d1) | Feb 08, 2022 |
| Apple         | MacBookPro4,1               | [87e9ca3a01](https://linux-hardware.org/?probe=87e9ca3a01) | Feb 07, 2022 |
| Razer         | Blade Stealth               | [de6e279575](https://linux-hardware.org/?probe=de6e279575) | Feb 07, 2022 |
| Razer         | Blade Stealth               | [c85996c28c](https://linux-hardware.org/?probe=c85996c28c) | Feb 07, 2022 |
| HP            | ProBook 440 G5              | [5f6a923aa2](https://linux-hardware.org/?probe=5f6a923aa2) | Feb 05, 2022 |
| HP            | ProBook 440 G5              | [6ff30e8299](https://linux-hardware.org/?probe=6ff30e8299) | Feb 05, 2022 |
| Apple         | MacBookPro11,5              | [46ba4fcc12](https://linux-hardware.org/?probe=46ba4fcc12) | Feb 04, 2022 |
| Acer          | Aspire 8940G                | [686119ea77](https://linux-hardware.org/?probe=686119ea77) | Feb 03, 2022 |
| HP            | Laptop 15s-fq1xxx           | [81f3f014e7](https://linux-hardware.org/?probe=81f3f014e7) | Feb 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [f9e76db452](https://linux-hardware.org/?probe=f9e76db452) | Jan 31, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [74533ff76f](https://linux-hardware.org/?probe=74533ff76f) | Jan 28, 2022 |
| Lenovo        | V145-15AST 81MT             | [07192f2b7d](https://linux-hardware.org/?probe=07192f2b7d) | Jan 27, 2022 |
| Lenovo        | G50-45 80E3                 | [f7fafa6976](https://linux-hardware.org/?probe=f7fafa6976) | Jan 26, 2022 |
| TUXEDO        | Book XP1511                 | [9a62ad3fe4](https://linux-hardware.org/?probe=9a62ad3fe4) | Jan 25, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [909aca1407](https://linux-hardware.org/?probe=909aca1407) | Jan 22, 2022 |
| Dell          | Latitude 5510               | [ab7eee3de9](https://linux-hardware.org/?probe=ab7eee3de9) | Jan 21, 2022 |
| Lenovo        | G50-45 80E3                 | [e45b9230c9](https://linux-hardware.org/?probe=e45b9230c9) | Jan 19, 2022 |
| HP            | EliteBook 8570w             | [edc7be1068](https://linux-hardware.org/?probe=edc7be1068) | Jan 18, 2022 |
| Lenovo        | G50-45 80E3                 | [98ff0f7580](https://linux-hardware.org/?probe=98ff0f7580) | Jan 17, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [585aa2aa39](https://linux-hardware.org/?probe=585aa2aa39) | Jan 16, 2022 |
| HP            | EliteBook 8570w             | [e324ae4a05](https://linux-hardware.org/?probe=e324ae4a05) | Jan 16, 2022 |
| Viglen        | VUB1                        | [d16d7f30b3](https://linux-hardware.org/?probe=d16d7f30b3) | Jan 16, 2022 |
| HP            | EliteBook 8570w             | [dd6c66b4dc](https://linux-hardware.org/?probe=dd6c66b4dc) | Jan 15, 2022 |
| Lenovo        | V145-15AST 81MT             | [03a777b7b1](https://linux-hardware.org/?probe=03a777b7b1) | Jan 13, 2022 |
| Lenovo        | V145-15AST 81MT             | [43ea5ed123](https://linux-hardware.org/?probe=43ea5ed123) | Jan 12, 2022 |
| EVOO          | EV-C-116-7                  | [3fe03ac079](https://linux-hardware.org/?probe=3fe03ac079) | Jan 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [e55162d481](https://linux-hardware.org/?probe=e55162d481) | Jan 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [ee6ede67e9](https://linux-hardware.org/?probe=ee6ede67e9) | Jan 02, 2022 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | [a76fb98d8d](https://linux-hardware.org/?probe=a76fb98d8d) | Jan 01, 2022 |
| Apple         | MacBookPro8,1               | [56d0201ca6](https://linux-hardware.org/?probe=56d0201ca6) | Dec 29, 2021 |
| TUXEDO        | Unknown                     | [339ee3ca1c](https://linux-hardware.org/?probe=339ee3ca1c) | Dec 28, 2021 |
| Lenovo        | V310-15ISK 80SY             | [16855d1282](https://linux-hardware.org/?probe=16855d1282) | Dec 27, 2021 |
| TUXEDO        | Unknown                     | [14323d7f2a](https://linux-hardware.org/?probe=14323d7f2a) | Dec 27, 2021 |
| Acer          | Swift SF314-52              | [67fb871b2f](https://linux-hardware.org/?probe=67fb871b2f) | Dec 24, 2021 |
| TUXEDO        | Aura 15 Gen1                | [c860a1c3c5](https://linux-hardware.org/?probe=c860a1c3c5) | Dec 22, 2021 |
| HP            | Pavilion tx1000             | [a3639ffcd5](https://linux-hardware.org/?probe=a3639ffcd5) | Dec 21, 2021 |
| HP            | Pavilion dm1                | [5e63d24312](https://linux-hardware.org/?probe=5e63d24312) | Dec 17, 2021 |
| GPU Compan... | GWTN156-11                  | [f586c51674](https://linux-hardware.org/?probe=f586c51674) | Dec 17, 2021 |
| Acer          | E3-112M-C6BV                | [81a7f64292](https://linux-hardware.org/?probe=81a7f64292) | Dec 15, 2021 |
| HP            | Pavilion tx1000             | [e568b07f70](https://linux-hardware.org/?probe=e568b07f70) | Dec 14, 2021 |
| TUXEDO        | Polaris 15 AMD Gen1         | [49234a5c74](https://linux-hardware.org/?probe=49234a5c74) | Dec 10, 2021 |
| TUXEDO        | Polaris 15 AMD Gen1         | [7cf830d39e](https://linux-hardware.org/?probe=7cf830d39e) | Dec 10, 2021 |
| Lenovo        | ThinkPad W530 244743G       | [4aff204627](https://linux-hardware.org/?probe=4aff204627) | Dec 10, 2021 |
| Toshiba       | Satellite S55-C             | [b6c63776b5](https://linux-hardware.org/?probe=b6c63776b5) | Dec 10, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | [b2d2913170](https://linux-hardware.org/?probe=b2d2913170) | Dec 07, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | [429851405d](https://linux-hardware.org/?probe=429851405d) | Dec 07, 2021 |
| Toshiba       | Satellite S55-C             | [9721dbfb66](https://linux-hardware.org/?probe=9721dbfb66) | Dec 07, 2021 |
| Toshiba       | Satellite S55-C             | [0e41e47583](https://linux-hardware.org/?probe=0e41e47583) | Dec 05, 2021 |
| Sony          | VPCEA47FX                   | [088fab187c](https://linux-hardware.org/?probe=088fab187c) | Dec 03, 2021 |
| Sony          | VPCEA47FX                   | [2f6f3b14de](https://linux-hardware.org/?probe=2f6f3b14de) | Dec 03, 2021 |
| Sony          | VPCEJ1L1E                   | [a48a00bdbc](https://linux-hardware.org/?probe=a48a00bdbc) | Dec 02, 2021 |
| TUXEDO        | P95_HP                      | [859d674cfe](https://linux-hardware.org/?probe=859d674cfe) | Dec 02, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [cd9d182e6e](https://linux-hardware.org/?probe=cd9d182e6e) | Nov 22, 2021 |
| Dell          | Vostro 1700                 | [86f23cb2f4](https://linux-hardware.org/?probe=86f23cb2f4) | Nov 22, 2021 |
| Dell          | Vostro 1700                 | [2aee39d91c](https://linux-hardware.org/?probe=2aee39d91c) | Nov 21, 2021 |
| Acer          | Swift SF114-32              | [008cd729a5](https://linux-hardware.org/?probe=008cd729a5) | Nov 14, 2021 |
| TUXEDO        | Unknown                     | [cb21aae05f](https://linux-hardware.org/?probe=cb21aae05f) | Nov 07, 2021 |
| Unknown       | Unknown                     | [ed14b60c7a](https://linux-hardware.org/?probe=ed14b60c7a) | Nov 05, 2021 |
| Dell          | Inspiron 5515               | [35d04dc3b9](https://linux-hardware.org/?probe=35d04dc3b9) | Nov 01, 2021 |
| Apple         | MacBookPro9,2               | [ef04c3c27a](https://linux-hardware.org/?probe=ef04c3c27a) | Oct 31, 2021 |
| TUXEDO        | Book XP15 / XP17 Gen12      | [4a518a759f](https://linux-hardware.org/?probe=4a518a759f) | Oct 25, 2021 |
| Apple         | MacBookPro8,2               | [571936bc0d](https://linux-hardware.org/?probe=571936bc0d) | Oct 23, 2021 |
| Acer          | Aspire 4752                 | [c4e21818b1](https://linux-hardware.org/?probe=c4e21818b1) | Oct 20, 2021 |
| Lenovo        | G570 4334                   | [7a9034f398](https://linux-hardware.org/?probe=7a9034f398) | Oct 12, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [1bea81fd91](https://linux-hardware.org/?probe=1bea81fd91) | Oct 10, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [d5ea22ef16](https://linux-hardware.org/?probe=d5ea22ef16) | Oct 09, 2021 |
| TUXEDO        | InfinityBook S 15 Gen6      | [b665ef94e7](https://linux-hardware.org/?probe=b665ef94e7) | Oct 01, 2021 |
| ASUSTek       | X302LJ                      | [281beb5fe7](https://linux-hardware.org/?probe=281beb5fe7) | Sep 23, 2021 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [9710e6ad6f](https://linux-hardware.org/?probe=9710e6ad6f) | Sep 19, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [b640e5da6d](https://linux-hardware.org/?probe=b640e5da6d) | Sep 17, 2021 |
| Dell          | Inspiron 5570               | [3ea6af2159](https://linux-hardware.org/?probe=3ea6af2159) | Sep 09, 2021 |
| Dell          | Inspiron 5570               | [981856c740](https://linux-hardware.org/?probe=981856c740) | Sep 09, 2021 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [4b6f0833eb](https://linux-hardware.org/?probe=4b6f0833eb) | Sep 02, 2021 |
| ASUSTek       | UX410UQK                    | [d2804fad00](https://linux-hardware.org/?probe=d2804fad00) | Sep 01, 2021 |
| ASUSTek       | UX410UQK                    | [819b70e8cb](https://linux-hardware.org/?probe=819b70e8cb) | Sep 01, 2021 |
| HP            | ZBook Studio G3             | [d0b29312b8](https://linux-hardware.org/?probe=d0b29312b8) | Aug 31, 2021 |
| HP            | x360 310 G2 PC              | [429d94dd0f](https://linux-hardware.org/?probe=429d94dd0f) | Aug 31, 2021 |
| Fujitsu       | LIFEBOOK U9311A             | [7d5eeb6448](https://linux-hardware.org/?probe=7d5eeb6448) | Aug 30, 2021 |
| Dell          | XPS 15 9560                 | [55f224e5c3](https://linux-hardware.org/?probe=55f224e5c3) | Aug 26, 2021 |
| TUXEDO        | InfinityBook S 15 Gen6      | [aabe23e7a8](https://linux-hardware.org/?probe=aabe23e7a8) | Aug 20, 2021 |
| Google        | Peppy                       | [b0be7ddeac](https://linux-hardware.org/?probe=b0be7ddeac) | Aug 18, 2021 |
| TUXEDO        | Book XP1511                 | [3312e66e9f](https://linux-hardware.org/?probe=3312e66e9f) | Aug 15, 2021 |
| Unknown       | Unknown                     | [8ffbb927af](https://linux-hardware.org/?probe=8ffbb927af) | Aug 13, 2021 |
| Lenovo        | ThinkPad E490 20N8S07A00    | [bd4a6e1eaf](https://linux-hardware.org/?probe=bd4a6e1eaf) | Aug 05, 2021 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [9452fd6e14](https://linux-hardware.org/?probe=9452fd6e14) | Aug 02, 2021 |
| TUXEDO        | Book_XA1510                 | [bc0cfb6203](https://linux-hardware.org/?probe=bc0cfb6203) | Jul 29, 2021 |
| TUXEDO        | P95_HR                      | [60f8b3ac61](https://linux-hardware.org/?probe=60f8b3ac61) | Jul 26, 2021 |
| PC Special... | OctaneVI 15                 | [05e8f69907](https://linux-hardware.org/?probe=05e8f69907) | Jul 26, 2021 |
| Fujitsu       | LIFEBOOK E756               | [6afad8262f](https://linux-hardware.org/?probe=6afad8262f) | Jul 26, 2021 |
| TUXEDO        | Unknown                     | [b2586cfeba](https://linux-hardware.org/?probe=b2586cfeba) | Jul 05, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [19f235e9dd](https://linux-hardware.org/?probe=19f235e9dd) | Jul 04, 2021 |
| Lenovo        | Y50-70 20378                | [cd4215f3d2](https://linux-hardware.org/?probe=cd4215f3d2) | Jul 03, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [bbda9475cc](https://linux-hardware.org/?probe=bbda9475cc) | Jul 02, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [d2d1c6e65e](https://linux-hardware.org/?probe=d2d1c6e65e) | Jun 28, 2021 |
| Lenovo        | ThinkPad T490 20RY0005US    | [5e91d6296d](https://linux-hardware.org/?probe=5e91d6296d) | Jun 27, 2021 |
| Lenovo        | ThinkPad T490 20RY0005US    | [4e3ee76cd4](https://linux-hardware.org/?probe=4e3ee76cd4) | Jun 27, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [f8795e30bf](https://linux-hardware.org/?probe=f8795e30bf) | Jun 24, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [143827e2e8](https://linux-hardware.org/?probe=143827e2e8) | Jun 16, 2021 |
| HP            | Notebook                    | [43b2a0f397](https://linux-hardware.org/?probe=43b2a0f397) | Jun 16, 2021 |
| BANGHO        | MAX G5 i1                   | [ca05e3a059](https://linux-hardware.org/?probe=ca05e3a059) | Jun 15, 2021 |
| Acer          | TravelMate P446-M           | [0c47a21c07](https://linux-hardware.org/?probe=0c47a21c07) | Jun 14, 2021 |
| Toshiba       | Satellite P300              | [f19856109a](https://linux-hardware.org/?probe=f19856109a) | Jun 09, 2021 |
| Acer          | Aspire A515-44              | [0f80210c56](https://linux-hardware.org/?probe=0f80210c56) | Jun 02, 2021 |
| Acer          | Aspire A515-44              | [8f5cb26311](https://linux-hardware.org/?probe=8f5cb26311) | Jun 02, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [b7f26cced7](https://linux-hardware.org/?probe=b7f26cced7) | Jun 01, 2021 |
| AWOW          | AK41                        | [ca1ba6ce75](https://linux-hardware.org/?probe=ca1ba6ce75) | May 27, 2021 |
| Dell          | Latitude E6410              | [124fdcdccb](https://linux-hardware.org/?probe=124fdcdccb) | May 25, 2021 |
| Dell          | Latitude E6410              | [5715f12aee](https://linux-hardware.org/?probe=5715f12aee) | May 24, 2021 |
| Toshiba       | Satellite P300              | [34d9279028](https://linux-hardware.org/?probe=34d9279028) | May 24, 2021 |
| TUXEDO        | Unknown                     | [d39c5e1f70](https://linux-hardware.org/?probe=d39c5e1f70) | May 23, 2021 |
| ASUSTek       | K45DR                       | [583824ad87](https://linux-hardware.org/?probe=583824ad87) | May 21, 2021 |
| Acer          | Aspire A515-51G             | [ad8fffaf05](https://linux-hardware.org/?probe=ad8fffaf05) | May 20, 2021 |
| ASUSTek       | N53SM                       | [fb4667be90](https://linux-hardware.org/?probe=fb4667be90) | May 19, 2021 |
| Dell          | Latitude E6540              | [6399cecb6f](https://linux-hardware.org/?probe=6399cecb6f) | May 19, 2021 |
| HP            | EliteBook 850 G1            | [5533f32102](https://linux-hardware.org/?probe=5533f32102) | May 18, 2021 |
| Toshiba       | Satellite P300              | [62ac427393](https://linux-hardware.org/?probe=62ac427393) | May 16, 2021 |
| TUXEDO        | Aura 15 Gen1                | [7aa1f41d1e](https://linux-hardware.org/?probe=7aa1f41d1e) | May 12, 2021 |
| Dell          | Latitude 5480               | [e6d8aca46a](https://linux-hardware.org/?probe=e6d8aca46a) | May 11, 2021 |
| Packard Be... | EasyNote TM98               | [2bb98626e9](https://linux-hardware.org/?probe=2bb98626e9) | May 03, 2021 |
| Dell          | Latitude D531               | [096370a055](https://linux-hardware.org/?probe=096370a055) | Apr 29, 2021 |
| Dell          | XPS 15 9500                 | [fbba77b949](https://linux-hardware.org/?probe=fbba77b949) | Apr 28, 2021 |
| Dell          | XPS 15 9500                 | [aba1faeb69](https://linux-hardware.org/?probe=aba1faeb69) | Apr 28, 2021 |
| Dell          | Vostro 5460                 | [cf32099d64](https://linux-hardware.org/?probe=cf32099d64) | Apr 27, 2021 |
| HUAWEI        | KLVL-WXX9                   | [d7318b3c30](https://linux-hardware.org/?probe=d7318b3c30) | Apr 26, 2021 |
| HUAWEI        | KLVL-WXX9                   | [ceee3d709c](https://linux-hardware.org/?probe=ceee3d709c) | Apr 26, 2021 |
| HP            | Pavilion g6                 | [e22e43c0b5](https://linux-hardware.org/?probe=e22e43c0b5) | Apr 22, 2021 |
| TUXEDO        | Polaris 17 AMD Gen1         | [0d25287be0](https://linux-hardware.org/?probe=0d25287be0) | Apr 16, 2021 |
| TUXEDO        | Polaris 17 AMD Gen1         | [a74abd0b52](https://linux-hardware.org/?probe=a74abd0b52) | Apr 16, 2021 |
| Sony          | SVS13A25PBS                 | [c693fe6603](https://linux-hardware.org/?probe=c693fe6603) | Apr 14, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [09dc9d1375](https://linux-hardware.org/?probe=09dc9d1375) | Apr 14, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [3c414d527a](https://linux-hardware.org/?probe=3c414d527a) | Apr 05, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [383e2af37d](https://linux-hardware.org/?probe=383e2af37d) | Apr 05, 2021 |
| MSI           | CX62 6QL                    | [fc3756c451](https://linux-hardware.org/?probe=fc3756c451) | Apr 05, 2021 |
| MSI           | CX62 6QL                    | [41b87e1036](https://linux-hardware.org/?probe=41b87e1036) | Apr 05, 2021 |
| Acer          | Aspire E1-431               | [0a6108eb22](https://linux-hardware.org/?probe=0a6108eb22) | Apr 04, 2021 |
| TUXEDO        | Aura 15 Gen1                | [7fbbadb983](https://linux-hardware.org/?probe=7fbbadb983) | Mar 27, 2021 |
| HP            | ProBook 640 G2              | [39e97c482d](https://linux-hardware.org/?probe=39e97c482d) | Mar 24, 2021 |
| Lenovo        | ThinkPad P43s 20RHS00100    | [835766dc3a](https://linux-hardware.org/?probe=835766dc3a) | Mar 21, 2021 |
| Lenovo        | ThinkPad P43s 20RHS00100    | [fb954b806d](https://linux-hardware.org/?probe=fb954b806d) | Mar 21, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | [153e336d81](https://linux-hardware.org/?probe=153e336d81) | Mar 21, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | [fa3b417784](https://linux-hardware.org/?probe=fa3b417784) | Mar 21, 2021 |
| Unknown       | Unknown                     | [282adc38a9](https://linux-hardware.org/?probe=282adc38a9) | Mar 20, 2021 |
| Unknown       | Unknown                     | [c368ac7bac](https://linux-hardware.org/?probe=c368ac7bac) | Mar 20, 2021 |
| Apple         | MacBookPro11,1              | [17a2a64f30](https://linux-hardware.org/?probe=17a2a64f30) | Mar 10, 2021 |
| HP            | ENVY 15                     | [5c1bfc1459](https://linux-hardware.org/?probe=5c1bfc1459) | Mar 05, 2021 |
| Timi          | TM1701                      | [a47b371c00](https://linux-hardware.org/?probe=a47b371c00) | Mar 03, 2021 |
| TUXEDO        | Polaris 15 AMD Gen1         | [12212ad362](https://linux-hardware.org/?probe=12212ad362) | Feb 27, 2021 |
| Dell          | Latitude 5590               | [95fa6d8570](https://linux-hardware.org/?probe=95fa6d8570) | Feb 26, 2021 |
| Dell          | Latitude 7490               | [c72d91886b](https://linux-hardware.org/?probe=c72d91886b) | Feb 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [290d20ab8b](https://linux-hardware.org/?probe=290d20ab8b) | Feb 23, 2021 |
| HP            | ENVY 15 x360 PC             | [1a67eafe01](https://linux-hardware.org/?probe=1a67eafe01) | Feb 22, 2021 |
| Dell          | Latitude E4300              | [ba125a9cb8](https://linux-hardware.org/?probe=ba125a9cb8) | Feb 22, 2021 |
| Lenovo        | ThinkPad P1 20MES01400      | [640ff77fea](https://linux-hardware.org/?probe=640ff77fea) | Feb 11, 2021 |
| Fujitsu       | LIFEBOOK A555               | [2028548034](https://linux-hardware.org/?probe=2028548034) | Feb 07, 2021 |
| Dell          | XPS 13 7390                 | [db6b98f685](https://linux-hardware.org/?probe=db6b98f685) | Feb 05, 2021 |
| HP            | ZBook Studio G3             | [6f207e9b7f](https://linux-hardware.org/?probe=6f207e9b7f) | Feb 04, 2021 |
| Dell          | Latitude 5580               | [b9ac308476](https://linux-hardware.org/?probe=b9ac308476) | Feb 04, 2021 |
| Dell          | XPS 13 7390                 | [771cb653c6](https://linux-hardware.org/?probe=771cb653c6) | Feb 03, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [c94818db0e](https://linux-hardware.org/?probe=c94818db0e) | Feb 03, 2021 |
| ASUSTek       | ROG Zephyrus GX550LXS_GX... | [748cc10c8c](https://linux-hardware.org/?probe=748cc10c8c) | Feb 03, 2021 |
| ASUSTek       | X551CA                      | [1857586e3a](https://linux-hardware.org/?probe=1857586e3a) | Feb 03, 2021 |
| Positivo      | C14CR21TV                   | [2133a41335](https://linux-hardware.org/?probe=2133a41335) | Feb 02, 2021 |
| MSI           | Prestige 14 A10SC           | [4af6bad702](https://linux-hardware.org/?probe=4af6bad702) | Jan 31, 2021 |
| HUAWEI        | KLVC-WXX9                   | [f519b82ae5](https://linux-hardware.org/?probe=f519b82ae5) | Jan 26, 2021 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [47517be667](https://linux-hardware.org/?probe=47517be667) | Jan 23, 2021 |
| Lenovo        | G40-30 80FY                 | [2ade08670a](https://linux-hardware.org/?probe=2ade08670a) | Jan 22, 2021 |
| HP            | Laptop 15-da0xxx            | [3d5f8c3cd2](https://linux-hardware.org/?probe=3d5f8c3cd2) | Jan 21, 2021 |
| MSI           | GP73 Leopard 8RE            | [c554fa2a9d](https://linux-hardware.org/?probe=c554fa2a9d) | Jan 17, 2021 |
| Dell          | XPS L322X                   | [e65c21cdd5](https://linux-hardware.org/?probe=e65c21cdd5) | Jan 16, 2021 |
| ASUSTek       | N53SM                       | [41bf2f638a](https://linux-hardware.org/?probe=41bf2f638a) | Jan 13, 2021 |
| MSI           | GE70 2PC\2PE                | [805e6fac6b](https://linux-hardware.org/?probe=805e6fac6b) | Jan 08, 2021 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [92c9f3e6c5](https://linux-hardware.org/?probe=92c9f3e6c5) | Jan 07, 2021 |
| Acer          | TravelMate P446-M           | [a0706cf84a](https://linux-hardware.org/?probe=a0706cf84a) | Jan 06, 2021 |
| Acer          | TravelMate P446-M           | [dd100bc162](https://linux-hardware.org/?probe=dd100bc162) | Jan 04, 2021 |
| Acer          | Aspire V3-771               | [450e8c59cc](https://linux-hardware.org/?probe=450e8c59cc) | Jan 02, 2021 |
| Acer          | Aspire V3-771               | [4122ea4b04](https://linux-hardware.org/?probe=4122ea4b04) | Jan 02, 2021 |
| Acer          | TravelMate P446-M           | [d040cbadcc](https://linux-hardware.org/?probe=d040cbadcc) | Jan 02, 2021 |
| Toshiba       | Satellite P750              | [3d7045dbbf](https://linux-hardware.org/?probe=3d7045dbbf) | Dec 28, 2020 |
| HP            | Pavilion 17                 | [b07af847e2](https://linux-hardware.org/?probe=b07af847e2) | Dec 26, 2020 |
| HP            | Stream Laptop 14-cb1xxx     | [4f8b9f90d8](https://linux-hardware.org/?probe=4f8b9f90d8) | Dec 21, 2020 |
| TUXEDO        | Aura 15 Gen1                | [c85ead3218](https://linux-hardware.org/?probe=c85ead3218) | Dec 19, 2020 |
| Unknown       | Unknown                     | [e81e3d85d6](https://linux-hardware.org/?probe=e81e3d85d6) | Dec 15, 2020 |
| Dell          | XPS 13 9380                 | [1eae71a2dd](https://linux-hardware.org/?probe=1eae71a2dd) | Dec 14, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | [ff0cd7f2bc](https://linux-hardware.org/?probe=ff0cd7f2bc) | Dec 13, 2020 |
| ASUSTek       | F9E                         | [0070b5eda7](https://linux-hardware.org/?probe=0070b5eda7) | Dec 12, 2020 |
| HP            | EliteBook 850 G1            | [671d151ab9](https://linux-hardware.org/?probe=671d151ab9) | Dec 12, 2020 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [a603cda0d7](https://linux-hardware.org/?probe=a603cda0d7) | Dec 12, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [c04e40195e](https://linux-hardware.org/?probe=c04e40195e) | Dec 11, 2020 |
| Fujitsu       | LIFEBOOK E756               | [ccb7d3edd7](https://linux-hardware.org/?probe=ccb7d3edd7) | Dec 10, 2020 |
| HP            | Pavilion dv1000 (EW999LA... | [6675bde630](https://linux-hardware.org/?probe=6675bde630) | Dec 07, 2020 |
| Lenovo        | ThinkPad T480 20L50011US    | [d47823099d](https://linux-hardware.org/?probe=d47823099d) | Dec 02, 2020 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [465bfd7567](https://linux-hardware.org/?probe=465bfd7567) | Nov 28, 2020 |
| Acer          | Aspire E1-532               | [c4db9a001e](https://linux-hardware.org/?probe=c4db9a001e) | Nov 25, 2020 |
| ASUSTek       | FX503VD                     | [f391747dd0](https://linux-hardware.org/?probe=f391747dd0) | Nov 24, 2020 |
| Packard Be... | EasyNote LE69KB             | [0afa851fa7](https://linux-hardware.org/?probe=0afa851fa7) | Nov 22, 2020 |
| HP            | Laptop 17-ak0xx             | [81d47c5bbd](https://linux-hardware.org/?probe=81d47c5bbd) | Nov 14, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [7e8af2342a](https://linux-hardware.org/?probe=7e8af2342a) | Nov 12, 2020 |
| ASUSTek       | K52De                       | [d95e3b8198](https://linux-hardware.org/?probe=d95e3b8198) | Nov 12, 2020 |
| ASUSTek       | K52De                       | [9aec230d46](https://linux-hardware.org/?probe=9aec230d46) | Nov 12, 2020 |
| HP            | Laptop 17-ak0xx             | [bb3de0e33d](https://linux-hardware.org/?probe=bb3de0e33d) | Nov 08, 2020 |
| Sony          | SVS13A25PBS                 | [ec54069f90](https://linux-hardware.org/?probe=ec54069f90) | Nov 06, 2020 |
| TUXEDO        | Unknown                     | [ccab34bcd7](https://linux-hardware.org/?probe=ccab34bcd7) | Nov 03, 2020 |
| Lenovo        | IdeaPad S100 20109          | [8f26323f1e](https://linux-hardware.org/?probe=8f26323f1e) | Nov 02, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | [f403df4c45](https://linux-hardware.org/?probe=f403df4c45) | Nov 01, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | [2e03e273f1](https://linux-hardware.org/?probe=2e03e273f1) | Oct 31, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | [4a619e003e](https://linux-hardware.org/?probe=4a619e003e) | Oct 31, 2020 |
| Fujitsu       | LIFEBOOK E756               | [7e515b01ea](https://linux-hardware.org/?probe=7e515b01ea) | Oct 30, 2020 |
| Acer          | Aspire SW3-016              | [be195992d0](https://linux-hardware.org/?probe=be195992d0) | Oct 30, 2020 |
| Dell          | Latitude E6540              | [45ad219146](https://linux-hardware.org/?probe=45ad219146) | Oct 29, 2020 |
| HP            | ZBook 14                    | [b282051085](https://linux-hardware.org/?probe=b282051085) | Oct 27, 2020 |
| HP            | Elite x2 1012 G1            | [7a593747a4](https://linux-hardware.org/?probe=7a593747a4) | Oct 26, 2020 |
| HP            | Elite x2 1012 G1            | [82ff46fe7f](https://linux-hardware.org/?probe=82ff46fe7f) | Oct 26, 2020 |
| Dell          | Latitude 5400               | [9594ef7488](https://linux-hardware.org/?probe=9594ef7488) | Oct 20, 2020 |
| Dell          | Latitude 5400               | [d016f37257](https://linux-hardware.org/?probe=d016f37257) | Oct 20, 2020 |
| HP            | Laptop 14-dk0xxx            | [2f2b699bf6](https://linux-hardware.org/?probe=2f2b699bf6) | Oct 11, 2020 |
| Lenovo        | ThinkPad P43s 20RH0013US    | [e540cc2901](https://linux-hardware.org/?probe=e540cc2901) | Oct 09, 2020 |
| Lenovo        | 20SL                        | [bda45231ce](https://linux-hardware.org/?probe=bda45231ce) | Oct 07, 2020 |
| Apple         | MacBookPro8,1               | [3f17f3c6e8](https://linux-hardware.org/?probe=3f17f3c6e8) | Oct 06, 2020 |
| TUXEDO        | P7xxTM1                     | [1c64a38e1e](https://linux-hardware.org/?probe=1c64a38e1e) | Oct 05, 2020 |
| MSI           | Modern 14 A10RB             | [67d9e1d5e4](https://linux-hardware.org/?probe=67d9e1d5e4) | Sep 30, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [2ebce35736](https://linux-hardware.org/?probe=2ebce35736) | Sep 29, 2020 |
| ASUSTek       | UX430UQ                     | [c201929d1a](https://linux-hardware.org/?probe=c201929d1a) | Sep 27, 2020 |
| Dell          | Latitude 5400               | [763c1287a5](https://linux-hardware.org/?probe=763c1287a5) | Sep 23, 2020 |
| HP            | ProBook 4730s               | [4363da5d51](https://linux-hardware.org/?probe=4363da5d51) | Sep 19, 2020 |
| Dell          | Inspiron 7560               | [4a1a3140a7](https://linux-hardware.org/?probe=4a1a3140a7) | Sep 15, 2020 |
| Fujitsu       | LIFEBOOK A512               | [0ce417fed7](https://linux-hardware.org/?probe=0ce417fed7) | Sep 08, 2020 |
| HP            | Pavilion g6                 | [522ff3c9c7](https://linux-hardware.org/?probe=522ff3c9c7) | Sep 03, 2020 |
| Dell          | G7 7588                     | [d6cd49b568](https://linux-hardware.org/?probe=d6cd49b568) | Sep 02, 2020 |
| Dell          | Inspiron 11-3168            | [bf9ae88e59](https://linux-hardware.org/?probe=bf9ae88e59) | Aug 20, 2020 |
| Dell          | Inspiron 11-3168            | [c168661ada](https://linux-hardware.org/?probe=c168661ada) | Aug 20, 2020 |
| ASUSTek       | U47A                        | [39d5bde56a](https://linux-hardware.org/?probe=39d5bde56a) | Aug 19, 2020 |
| Sony          | VPCEK20AL                   | [2147eeff89](https://linux-hardware.org/?probe=2147eeff89) | Aug 16, 2020 |
| MSI           | Prestige 15 A10SC           | [4cea086204](https://linux-hardware.org/?probe=4cea086204) | Aug 16, 2020 |
| Dell          | Inspiron 11-3168            | [d24b0f8f6a](https://linux-hardware.org/?probe=d24b0f8f6a) | Aug 16, 2020 |
| Dell          | Inspiron 11-3168            | [6bdfa3f1ad](https://linux-hardware.org/?probe=6bdfa3f1ad) | Aug 16, 2020 |
| ASUSTek       | U47A                        | [55022416f8](https://linux-hardware.org/?probe=55022416f8) | Aug 14, 2020 |
| ASUSTek       | U47A                        | [1c4676a5d6](https://linux-hardware.org/?probe=1c4676a5d6) | Aug 13, 2020 |
| Standard      | MT40II                      | [974f5398ca](https://linux-hardware.org/?probe=974f5398ca) | Aug 06, 2020 |
| Lenovo        | ThinkPad T430s 23539WU      | [3ff86ae696](https://linux-hardware.org/?probe=3ff86ae696) | Aug 03, 2020 |
| Samsung       | 340XAA/350XAA/550XAA        | [5caeef5a4f](https://linux-hardware.org/?probe=5caeef5a4f) | Aug 03, 2020 |
| Apple         | MacBook3,1                  | [7da122d44a](https://linux-hardware.org/?probe=7da122d44a) | Jul 29, 2020 |
| HUAWEI        | MACH-WX9                    | [999f65d55e](https://linux-hardware.org/?probe=999f65d55e) | Jul 28, 2020 |
| Samsung       | 340XAA/350XAA/550XAA        | [6a0fabe139](https://linux-hardware.org/?probe=6a0fabe139) | Jul 28, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [ccd785c473](https://linux-hardware.org/?probe=ccd785c473) | Jul 27, 2020 |
| Samsung       | 530U3C/530U4C/532U3C        | [4f80b590f5](https://linux-hardware.org/?probe=4f80b590f5) | Jul 25, 2020 |
| HP            | Pavilion 14                 | [3243fbe29b](https://linux-hardware.org/?probe=3243fbe29b) | Jul 25, 2020 |
| HP            | Pavilion dv6                | [24b46efa49](https://linux-hardware.org/?probe=24b46efa49) | Jul 25, 2020 |
| HP            | EliteBook 2560p             | [dd251c0a0c](https://linux-hardware.org/?probe=dd251c0a0c) | Jul 25, 2020 |
| Dell          | Latitude E6320              | [d9ac43486e](https://linux-hardware.org/?probe=d9ac43486e) | Jul 25, 2020 |
| Dell          | G3 3579                     | [b129bccbcf](https://linux-hardware.org/?probe=b129bccbcf) | Jul 24, 2020 |
| Dell          | G7 7588                     | [cb6c4a378b](https://linux-hardware.org/?probe=cb6c4a378b) | Jul 24, 2020 |
| Dell          | Inspiron 5437               | [bae63d5905](https://linux-hardware.org/?probe=bae63d5905) | Jul 24, 2020 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [a4ff18fb01](https://linux-hardware.org/?probe=a4ff18fb01) | Jul 24, 2020 |
| Acer          | Aspire A315-41              | [689b63d743](https://linux-hardware.org/?probe=689b63d743) | Jul 24, 2020 |
| ASUSTek       | K53E                        | [965c0a5e03](https://linux-hardware.org/?probe=965c0a5e03) | Jul 20, 2020 |
| MSI           | GL62M 7RD                   | [ddfb055569](https://linux-hardware.org/?probe=ddfb055569) | Jul 18, 2020 |
| MSI           | GP72 7RE                    | [66efd09dbc](https://linux-hardware.org/?probe=66efd09dbc) | Jul 12, 2020 |
| ASUSTek       | X510UAR                     | [a8f39d2061](https://linux-hardware.org/?probe=a8f39d2061) | Jul 08, 2020 |
| HP            | EliteBook 840 G6            | [1a175eee47](https://linux-hardware.org/?probe=1a175eee47) | Jul 07, 2020 |
| Dell          | Inspiron 3537               | [803b8c9adc](https://linux-hardware.org/?probe=803b8c9adc) | Jul 06, 2020 |
| Dell          | Inspiron 3537               | [38640e68c7](https://linux-hardware.org/?probe=38640e68c7) | Jul 06, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [e2f2937842](https://linux-hardware.org/?probe=e2f2937842) | Jul 05, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [e6480fdb93](https://linux-hardware.org/?probe=e6480fdb93) | Jul 04, 2020 |
| Dell          | XPS L401X                   | [291b1c0a01](https://linux-hardware.org/?probe=291b1c0a01) | Jul 03, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [c67e3d5b3d](https://linux-hardware.org/?probe=c67e3d5b3d) | Jul 02, 2020 |
| TUXEDO        | Unknown                     | [dd10caa4c9](https://linux-hardware.org/?probe=dd10caa4c9) | Jun 26, 2020 |
| Dell          | Latitude E6220              | [2177469041](https://linux-hardware.org/?probe=2177469041) | Jun 25, 2020 |
| HP            | Laptop 15-dw0xxx            | [a9c582ba02](https://linux-hardware.org/?probe=a9c582ba02) | Jun 19, 2020 |
| Acer          | Aspire R3-131T              | [b51cceda3f](https://linux-hardware.org/?probe=b51cceda3f) | Jun 17, 2020 |
| Acer          | Aspire R3-131T              | [52d48f4c11](https://linux-hardware.org/?probe=52d48f4c11) | Jun 17, 2020 |
| TUXEDO        | InfinityBook Pro 15 v4      | [7d351b71dc](https://linux-hardware.org/?probe=7d351b71dc) | Jun 17, 2020 |
| HP            | ENVY 17                     | [8ee27ae156](https://linux-hardware.org/?probe=8ee27ae156) | Jun 16, 2020 |
| Dell          | Inspiron 7590               | [1e4d9a97b8](https://linux-hardware.org/?probe=1e4d9a97b8) | Jun 15, 2020 |
| Sony          | VPCCW25FL                   | [2e9d3ed45b](https://linux-hardware.org/?probe=2e9d3ed45b) | Jun 14, 2020 |
| HP            | ENVY 17                     | [6717ca8025](https://linux-hardware.org/?probe=6717ca8025) | Jun 14, 2020 |
| TUXEDO        | Unknown                     | [7c4e814d03](https://linux-hardware.org/?probe=7c4e814d03) | Jun 13, 2020 |
| TUXEDO        | Unknown                     | [10875bae28](https://linux-hardware.org/?probe=10875bae28) | Jun 13, 2020 |
| Acer          | Aspire V3-572G              | [d780f9b6ef](https://linux-hardware.org/?probe=d780f9b6ef) | Jun 13, 2020 |
| ASUSTek       | X540LA                      | [99651c1c86](https://linux-hardware.org/?probe=99651c1c86) | Jun 12, 2020 |
| HP            | ENVY 17                     | [19571ad1c9](https://linux-hardware.org/?probe=19571ad1c9) | Jun 11, 2020 |
| HP            | ENVY 15                     | [3fa91961e1](https://linux-hardware.org/?probe=3fa91961e1) | Jun 07, 2020 |
| HP            | ENVY 17                     | [16c895ce30](https://linux-hardware.org/?probe=16c895ce30) | Jun 07, 2020 |
| Lenovo        | ThinkPad X230 23257G6       | [95097be9d3](https://linux-hardware.org/?probe=95097be9d3) | Jun 02, 2020 |
| Lenovo        | ThinkPad X230 23257G6       | [d4c8c1735b](https://linux-hardware.org/?probe=d4c8c1735b) | May 31, 2020 |
| HUAWEI        | MACH-WX9                    | [f3ca082840](https://linux-hardware.org/?probe=f3ca082840) | May 31, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [6ad038b762](https://linux-hardware.org/?probe=6ad038b762) | May 30, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [3552bfc82b](https://linux-hardware.org/?probe=3552bfc82b) | May 29, 2020 |
| HP            | ENVY 17                     | [0bb6be8c85](https://linux-hardware.org/?probe=0bb6be8c85) | May 27, 2020 |
| HP            | ENVY 17                     | [4f1caa50f6](https://linux-hardware.org/?probe=4f1caa50f6) | May 27, 2020 |
| Lenovo        | ThinkPad X260 20F5S2HF06    | [fb34ca6c06](https://linux-hardware.org/?probe=fb34ca6c06) | May 26, 2020 |
| Lenovo        | ThinkPad T430 2349P74       | [50dbda3211](https://linux-hardware.org/?probe=50dbda3211) | May 21, 2020 |
| ASUSTek       | S400CA                      | [3e3bb3f13e](https://linux-hardware.org/?probe=3e3bb3f13e) | May 19, 2020 |
| ASUSTek       | X510UNR                     | [23cb30a022](https://linux-hardware.org/?probe=23cb30a022) | May 16, 2020 |
| ASUSTek       | X510UNR                     | [d28985973f](https://linux-hardware.org/?probe=d28985973f) | May 16, 2020 |
| Acer          | Aspire F5-573G              | [7eea93aa65](https://linux-hardware.org/?probe=7eea93aa65) | May 16, 2020 |
| TUXEDO        | Unknown                     | [9eb9f125bf](https://linux-hardware.org/?probe=9eb9f125bf) | May 15, 2020 |
| Dell          | Latitude 5400               | [cfdf75da7b](https://linux-hardware.org/?probe=cfdf75da7b) | May 14, 2020 |
| Acer          | Swift SF315-52              | [39a7bd47d7](https://linux-hardware.org/?probe=39a7bd47d7) | May 12, 2020 |
| Lenovo        | G550 2958                   | [4e4bcc14f1](https://linux-hardware.org/?probe=4e4bcc14f1) | May 11, 2020 |
| Lenovo        | G550 2958                   | [ea8d2d9296](https://linux-hardware.org/?probe=ea8d2d9296) | May 11, 2020 |
| TUXEDO        | Unknown                     | [f06dc42b2a](https://linux-hardware.org/?probe=f06dc42b2a) | May 10, 2020 |
| TUXEDO        | Unknown                     | [3a72ff2108](https://linux-hardware.org/?probe=3a72ff2108) | May 09, 2020 |
| ASUSTek       | S551LN                      | [51bb777f10](https://linux-hardware.org/?probe=51bb777f10) | May 08, 2020 |
| ASUSTek       | S551LN                      | [b81e2e0679](https://linux-hardware.org/?probe=b81e2e0679) | May 08, 2020 |
| Quanta        | QL3 TBD                     | [680a32b94c](https://linux-hardware.org/?probe=680a32b94c) | May 08, 2020 |
| Gigabyte      | GB-BKi7A-7500               | [a4c4bc09fb](https://linux-hardware.org/?probe=a4c4bc09fb) | May 08, 2020 |
| HP            | EliteBook 840 G5            | [5c81f4ef61](https://linux-hardware.org/?probe=5c81f4ef61) | May 07, 2020 |
| ASUSTek       | G55VW                       | [9cb0c68aa1](https://linux-hardware.org/?probe=9cb0c68aa1) | May 07, 2020 |
| HP            | EliteBook 8560w             | [e2fca9899f](https://linux-hardware.org/?probe=e2fca9899f) | May 07, 2020 |
| Acer          | Aspire F5-573G              | [0b67b7c423](https://linux-hardware.org/?probe=0b67b7c423) | May 06, 2020 |
| Dell          | Inspiron 1545               | [ac74330be2](https://linux-hardware.org/?probe=ac74330be2) | May 03, 2020 |
| HP            | Notebook                    | [d666fee133](https://linux-hardware.org/?probe=d666fee133) | May 02, 2020 |
| Lenovo        | ThinkPad W530 2447GW3       | [69f36d1be1](https://linux-hardware.org/?probe=69f36d1be1) | Apr 30, 2020 |
| Lenovo        | ThinkPad X230 2306CTO       | [80111dac4b](https://linux-hardware.org/?probe=80111dac4b) | Apr 24, 2020 |
| Dell          | Latitude 5400               | [7319cff553](https://linux-hardware.org/?probe=7319cff553) | Apr 22, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [cba2c66659](https://linux-hardware.org/?probe=cba2c66659) | Apr 20, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [e2fabad799](https://linux-hardware.org/?probe=e2fabad799) | Apr 13, 2020 |
| Lenovo        | ThinkPad T410 2537H21       | [0140b2344a](https://linux-hardware.org/?probe=0140b2344a) | Apr 08, 2020 |
| HP            | EliteBook 8470p             | [d39e8563ca](https://linux-hardware.org/?probe=d39e8563ca) | Apr 07, 2020 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [f309322c77](https://linux-hardware.org/?probe=f309322c77) | Apr 04, 2020 |
| Dell          | Inspiron 5770               | [5a5984be1c](https://linux-hardware.org/?probe=5a5984be1c) | Mar 29, 2020 |
| Dell          | Inspiron 5770               | [afcbaaf5c5](https://linux-hardware.org/?probe=afcbaaf5c5) | Mar 29, 2020 |
| HP            | Compaq 6720s                | [7a81993a9b](https://linux-hardware.org/?probe=7a81993a9b) | Mar 22, 2020 |
| Lenovo        | ThinkPad P53 20QQS1JE00     | [6692834531](https://linux-hardware.org/?probe=6692834531) | Mar 18, 2020 |
| ASUSTek       | X750JB                      | [6d8e7e2bf9](https://linux-hardware.org/?probe=6d8e7e2bf9) | Mar 15, 2020 |
| Dell          | Latitude 5400               | [3bda0aef33](https://linux-hardware.org/?probe=3bda0aef33) | Mar 14, 2020 |
| HP            | 2000                        | [fa3539bb75](https://linux-hardware.org/?probe=fa3539bb75) | Mar 14, 2020 |
| Standard      | MT40II                      | [f11c251d38](https://linux-hardware.org/?probe=f11c251d38) | Mar 13, 2020 |
| Dell          | Latitude E6420              | [7653562a2f](https://linux-hardware.org/?probe=7653562a2f) | Mar 07, 2020 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [c4b9b4ab26](https://linux-hardware.org/?probe=c4b9b4ab26) | Mar 07, 2020 |
| HP            | ENVY Laptop 13-ah0xxx       | [4b844d95eb](https://linux-hardware.org/?probe=4b844d95eb) | Mar 05, 2020 |
| HP            | ENVY Laptop 13-ah0xxx       | [b88f46d2eb](https://linux-hardware.org/?probe=b88f46d2eb) | Mar 05, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [1dba6c5acf](https://linux-hardware.org/?probe=1dba6c5acf) | Mar 03, 2020 |
| Dell          | XPS 13 9380                 | [5a7b311c84](https://linux-hardware.org/?probe=5a7b311c84) | Mar 02, 2020 |
| ASUSTek       | N751JK                      | [a08a81ed83](https://linux-hardware.org/?probe=a08a81ed83) | Mar 01, 2020 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [435f7d1017](https://linux-hardware.org/?probe=435f7d1017) | Feb 21, 2020 |
| TUXEDO        | Unknown                     | [002a2b6abe](https://linux-hardware.org/?probe=002a2b6abe) | Feb 21, 2020 |
| ASUSTek       | N501VW                      | [9e101537c5](https://linux-hardware.org/?probe=9e101537c5) | Feb 17, 2020 |
| ASUSTek       | N501VW                      | [31a6b6bac8](https://linux-hardware.org/?probe=31a6b6bac8) | Feb 15, 2020 |
| Acer          | Aspire A515-51G             | [ac2755b222](https://linux-hardware.org/?probe=ac2755b222) | Feb 12, 2020 |
| Acer          | Aspire A515-51G             | [317f9ded14](https://linux-hardware.org/?probe=317f9ded14) | Feb 12, 2020 |
| Lenovo        | ThinkPad L380 20M50013UK    | [e5b58a2f40](https://linux-hardware.org/?probe=e5b58a2f40) | Feb 08, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [81d2b1c515](https://linux-hardware.org/?probe=81d2b1c515) | Jan 25, 2020 |
| Unknown       | Unknown                     | [5603e706a3](https://linux-hardware.org/?probe=5603e706a3) | Jan 19, 2020 |
| Lenovo        | Yoga 2 Pro 20266            | [912a2fc0df](https://linux-hardware.org/?probe=912a2fc0df) | Jan 16, 2020 |
| HP            | 2000                        | [adde2680e0](https://linux-hardware.org/?probe=adde2680e0) | Jan 08, 2020 |
| Lenovo        | ThinkPad T530 23943V0       | [fdb43e275c](https://linux-hardware.org/?probe=fdb43e275c) | Jan 05, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [ae8aac83f4](https://linux-hardware.org/?probe=ae8aac83f4) | Jan 05, 2020 |
| TUXEDO        | Unknown                     | [282e4941e2](https://linux-hardware.org/?probe=282e4941e2) | Dec 27, 2019 |
| HP            | Compaq 8460p USAO           | [3eab448396](https://linux-hardware.org/?probe=3eab448396) | Dec 21, 2019 |
| ASUSTek       | N751JK                      | [a6b5f083ca](https://linux-hardware.org/?probe=a6b5f083ca) | Nov 21, 2019 |
| ASUSTek       | N751JK                      | [2c44aa3122](https://linux-hardware.org/?probe=2c44aa3122) | Nov 21, 2019 |
| Dell          | Inspiron 5559               | [6571c933d2](https://linux-hardware.org/?probe=6571c933d2) | Mar 08, 2019 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_Budgie/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu Budgie 20.04 | 171       | 36.85%  |
| Ubuntu Budgie 22.04 | 108       | 23.28%  |
| Ubuntu Budgie 20.10 | 34        | 7.33%   |
| Ubuntu Budgie 21.10 | 33        | 7.11%   |
| Ubuntu Budgie 22.10 | 26        | 5.6%    |
| Ubuntu Budgie 18.04 | 25        | 5.39%   |
| Ubuntu Budgie 21.04 | 21        | 4.53%   |
| Ubuntu Budgie 23.04 | 17        | 3.66%   |
| Ubuntu Budgie 19.10 | 13        | 2.8%    |
| Ubuntu Budgie 23.10 | 11        | 2.37%   |
| Ubuntu Budgie 24.04 | 2         | 0.43%   |
| Ubuntu Budgie 16.04 | 2         | 0.43%   |
| Ubuntu Budgie       | 1         | 0.22%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu Budgie | 446       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 18        | 3.51%   |
| 5.3.0-40-generic  | 10        | 1.95%   |
| 5.4.0-40-generic  | 9         | 1.75%   |
| 5.13.0-22-generic | 9         | 1.75%   |
| 6.2.0-20-generic  | 8         | 1.56%   |
| 5.8.0-41-generic  | 7         | 1.36%   |
| 5.15.0-27-generic | 7         | 1.36%   |
| 5.13.0-28-generic | 7         | 1.36%   |
| 5.4.0-37-generic  | 6         | 1.17%   |
| 5.4.0-29-generic  | 6         | 1.17%   |
| 5.13.0-39-generic | 6         | 1.17%   |
| 6.2.0-26-generic  | 5         | 0.97%   |
| 5.8.0-53-generic  | 5         | 0.97%   |
| 5.8.0-48-generic  | 5         | 0.97%   |
| 5.4.0-52-generic  | 5         | 0.97%   |
| 5.4.0-48-generic  | 5         | 0.97%   |
| 5.4.0-33-generic  | 5         | 0.97%   |
| 5.19.0-46-generic | 5         | 0.97%   |
| 5.19.0-35-generic | 5         | 0.97%   |
| 5.15.0-50-generic | 5         | 0.97%   |
| 5.15.0-48-generic | 5         | 0.97%   |
| 5.13.0-40-generic | 5         | 0.97%   |
| 5.13.0-35-generic | 5         | 0.97%   |
| 5.13.0-30-generic | 5         | 0.97%   |
| 5.13.0-19-generic | 5         | 0.97%   |
| 5.11.0-41-generic | 5         | 0.97%   |
| 6.5.0-9-generic   | 4         | 0.78%   |
| 6.5.0-18-generic  | 4         | 0.78%   |
| 6.5.0-15-generic  | 4         | 0.78%   |
| 6.2.0-39-generic  | 4         | 0.78%   |
| 6.2.0-33-generic  | 4         | 0.78%   |
| 5.8.0-44-generic  | 4         | 0.78%   |
| 5.8.0-33-generic  | 4         | 0.78%   |
| 5.8.0-29-generic  | 4         | 0.78%   |
| 5.4.0-58-generic  | 4         | 0.78%   |
| 5.4.0-31-generic  | 4         | 0.78%   |
| 5.19.0-38-generic | 4         | 0.78%   |
| 5.19.0-26-generic | 4         | 0.78%   |
| 5.15.0-52-generic | 4         | 0.78%   |
| 5.15.0-46-generic | 4         | 0.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 105       | 22.06%  |
| 5.15.0  | 75        | 15.76%  |
| 5.8.0   | 54        | 11.34%  |
| 5.13.0  | 53        | 11.13%  |
| 5.19.0  | 41        | 8.61%   |
| 5.11.0  | 35        | 7.35%   |
| 6.2.0   | 32        | 6.72%   |
| 6.5.0   | 25        | 5.25%   |
| 5.3.0   | 21        | 4.41%   |
| 4.15.0  | 11        | 2.31%   |
| 5.6.0   | 3         | 0.63%   |
| 6.8.0   | 2         | 0.42%   |
| 5.12.0  | 2         | 0.42%   |
| 5.0.0   | 2         | 0.42%   |
| 4.18.0  | 2         | 0.42%   |
| 6.5.5   | 1         | 0.21%   |
| 6.3.1   | 1         | 0.21%   |
| 6.1.0   | 1         | 0.21%   |
| 5.9.0   | 1         | 0.21%   |
| 5.8.11  | 1         | 0.21%   |
| 5.6.7   | 1         | 0.21%   |
| 5.5.0   | 1         | 0.21%   |
| 5.18.8  | 1         | 0.21%   |
| 5.16.14 | 1         | 0.21%   |
| 5.15.11 | 1         | 0.21%   |
| 5.10.11 | 1         | 0.21%   |
| 5.10.0  | 1         | 0.21%   |
| 4.4.0   | 1         | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 105       | 22.06%  |
| 5.15    | 76        | 15.97%  |
| 5.8     | 55        | 11.55%  |
| 5.13    | 53        | 11.13%  |
| 5.19    | 41        | 8.61%   |
| 5.11    | 35        | 7.35%   |
| 6.2     | 32        | 6.72%   |
| 6.5     | 26        | 5.46%   |
| 5.3     | 21        | 4.41%   |
| 4.15    | 11        | 2.31%   |
| 5.6     | 4         | 0.84%   |
| 6.8     | 2         | 0.42%   |
| 5.12    | 2         | 0.42%   |
| 5.10    | 2         | 0.42%   |
| 5.0     | 2         | 0.42%   |
| 4.18    | 2         | 0.42%   |
| 6.3     | 1         | 0.21%   |
| 6.1     | 1         | 0.21%   |
| 5.9     | 1         | 0.21%   |
| 5.5     | 1         | 0.21%   |
| 5.18    | 1         | 0.21%   |
| 5.16    | 1         | 0.21%   |
| 4.4     | 1         | 0.21%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 443       | 99.33%  |
| i686   | 3         | 0.67%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Budgie     | 432       | 96.86%  |
| GNOME      | 10        | 2.24%   |
| KDE5       | 2         | 0.45%   |
| XFCE       | 1         | 0.22%   |
| X-Cinnamon | 1         | 0.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 434       | 96.88%  |
| Wayland | 13        | 2.9%    |
| Tty     | 1         | 0.22%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 199       | 44.12%  |
| Unknown | 146       | 32.37%  |
| TDM     | 58        | 12.86%  |
| GDM     | 26        | 5.76%   |
| GDM3    | 19        | 4.21%   |
| SDDM    | 3         | 0.67%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 155       | 34.6%   |
| de_DE   | 56        | 12.5%   |
| fr_FR   | 32        | 7.14%   |
| en_GB   | 27        | 6.03%   |
| pt_BR   | 25        | 5.58%   |
| it_IT   | 15        | 3.35%   |
| en_CA   | 15        | 3.35%   |
| ru_RU   | 14        | 3.13%   |
| en_IN   | 13        | 2.9%    |
| es_AR   | 8         | 1.79%   |
| es_ES   | 7         | 1.56%   |
| es_MX   | 6         | 1.34%   |
| en_AU   | 6         | 1.34%   |
| C       | 6         | 1.34%   |
| pl_PL   | 4         | 0.89%   |
| hu_HU   | 4         | 0.89%   |
| es_CL   | 4         | 0.89%   |
| pt_PT   | 3         | 0.67%   |
| en_IE   | 3         | 0.67%   |
| de_AT   | 3         | 0.67%   |
| cs_CZ   | 3         | 0.67%   |
| Unknown | 3         | 0.67%   |
| fr_BE   | 2         | 0.45%   |
| fi_FI   | 2         | 0.45%   |
| eu_ES   | 2         | 0.45%   |
| en_ZA   | 2         | 0.45%   |
| en_SG   | 2         | 0.45%   |
| de_CH   | 2         | 0.45%   |
| zh_TW   | 1         | 0.22%   |
| zh_CN   | 1         | 0.22%   |
| uk_UA   | 1         | 0.22%   |
| tr_TR   | 1         | 0.22%   |
| nl_NL   | 1         | 0.22%   |
| nl_BE   | 1         | 0.22%   |
| nb_NO   | 1         | 0.22%   |
| mt_MT   | 1         | 0.22%   |
| lv_LV   | 1         | 0.22%   |
| ko_KR   | 1         | 0.22%   |
| ja_JP   | 1         | 0.22%   |
| id_ID   | 1         | 0.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 256       | 56.14%  |
| BIOS | 200       | 43.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 389       | 86.25%  |
| Tmpfs   | 28        | 6.21%   |
| Zfs     | 14        | 3.1%    |
| Overlay | 11        | 2.44%   |
| Btrfs   | 5         | 1.11%   |
| Xfs     | 3         | 0.67%   |
| Jfs     | 1         | 0.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 231       | 50.77%  |
| Unknown | 187       | 41.1%   |
| MBR     | 37        | 8.13%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 399       | 88.67%  |
| Yes       | 51        | 11.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 306       | 68%     |
| Yes       | 144       | 32%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 84        | 18.83%  |
| Hewlett-Packard        | 72        | 16.14%  |
| Dell                   | 60        | 13.45%  |
| ASUSTek Computer       | 49        | 10.99%  |
| TUXEDO                 | 46        | 10.31%  |
| Acer                   | 24        | 5.38%   |
| Apple                  | 18        | 4.04%   |
| MSI                    | 16        | 3.59%   |
| Toshiba                | 7         | 1.57%   |
| Sony                   | 7         | 1.57%   |
| HUAWEI                 | 7         | 1.57%   |
| Google                 | 7         | 1.57%   |
| Samsung Electronics    | 5         | 1.12%   |
| Unknown                | 5         | 1.12%   |
| Packard Bell           | 4         | 0.9%    |
| Fujitsu                | 3         | 0.67%   |
| Timi                   | 2         | 0.45%   |
| Standard               | 2         | 0.45%   |
| Razer                  | 2         | 0.45%   |
| Positivo               | 2         | 0.45%   |
| Chuwi                  | 2         | 0.45%   |
| BANGHO                 | 2         | 0.45%   |
| Alienware              | 2         | 0.45%   |
| Viglen                 | 1         | 0.22%   |
| THUNDEROBOT            | 1         | 0.22%   |
| Thomson                | 1         | 0.22%   |
| Quanta                 | 1         | 0.22%   |
| PC Specialist          | 1         | 0.22%   |
| Notebook               | 1         | 0.22%   |
| IMUZ                   | 1         | 0.22%   |
| HONOR                  | 1         | 0.22%   |
| GPU Company            | 1         | 0.22%   |
| Gigabyte Technology    | 1         | 0.22%   |
| Gateway                | 1         | 0.22%   |
| EVOO                   | 1         | 0.22%   |
| Digibras               | 1         | 0.22%   |
| COM1                   | 1         | 0.22%   |
| AXIOO                  | 1         | 0.22%   |
| AWOW                   | 1         | 0.22%   |
| Avell High Performance | 1         | 0.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Unknown                                 | 15        | 3.36%   |
| TUXEDO Pulse 15 Gen1                    | 4         | 0.9%    |
| TUXEDO InfinityBook S 15 Gen6           | 3         | 0.67%   |
| TUXEDO Aura 15 Gen1                     | 3         | 0.67%   |
| HP Pavilion g6                          | 3         | 0.67%   |
| HP Notebook                             | 3         | 0.67%   |
| Dell Latitude E6420                     | 3         | 0.67%   |
| TUXEDO Polaris 15 AMD Gen1              | 2         | 0.45%   |
| TUXEDO InfinityBook S 14 Gen6           | 2         | 0.45%   |
| TUXEDO InfinityBook Pro 14 Gen6         | 2         | 0.45%   |
| TUXEDO Book XP1511                      | 2         | 0.45%   |
| Standard MT40II                         | 2         | 0.45%   |
| Packard Bell EasyNote TM98              | 2         | 0.45%   |
| Lenovo ThinkPad E15 20RD003KHV          | 2         | 0.45%   |
| Lenovo ThinkBook 14-IML 20RV            | 2         | 0.45%   |
| Lenovo IdeaPad C340-14API 81N6          | 2         | 0.45%   |
| Lenovo IdeaPad 5 15ARE05 81YQ           | 2         | 0.45%   |
| Lenovo IdeaPad 330S-15ARR 81FB          | 2         | 0.45%   |
| Lenovo IdeaPad 320-15IKB 80XL           | 2         | 0.45%   |
| Lenovo IdeaPad 110-15ISK 80UD           | 2         | 0.45%   |
| Lenovo G500 20236                       | 2         | 0.45%   |
| Lenovo G50-45 80E3                      | 2         | 0.45%   |
| HP ZBook Studio G3                      | 2         | 0.45%   |
| HP ZBook 15 G4                          | 2         | 0.45%   |
| HP Pavilion dv7                         | 2         | 0.45%   |
| HP ENVY 17                              | 2         | 0.45%   |
| HP ENVY 15                              | 2         | 0.45%   |
| HP EliteBook 840 G8 Notebook PC         | 2         | 0.45%   |
| HP EliteBook 840 G3                     | 2         | 0.45%   |
| HP 2000                                 | 2         | 0.45%   |
| Dell XPS 13 9380                        | 2         | 0.45%   |
| Dell Latitude E6540                     | 2         | 0.45%   |
| Dell Latitude E6410                     | 2         | 0.45%   |
| Dell Latitude E5420                     | 2         | 0.45%   |
| Dell Latitude 7490                      | 2         | 0.45%   |
| Dell Latitude 5480                      | 2         | 0.45%   |
| Dell Latitude 5400                      | 2         | 0.45%   |
| Dell Inspiron 5570                      | 2         | 0.45%   |
| ASUS VivoBook_ASUSLaptop X705MAR_X705MA | 2         | 0.45%   |
| ASUS VivoBook_ASUSLaptop X571GT_F571GT  | 2         | 0.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 39        | 8.74%   |
| Dell Latitude         | 28        | 6.28%   |
| Lenovo IdeaPad        | 24        | 5.38%   |
| HP Pavilion           | 15        | 3.36%   |
| Acer Aspire           | 15        | 3.36%   |
| Unknown               | 15        | 3.36%   |
| HP EliteBook          | 14        | 3.14%   |
| Dell Inspiron         | 14        | 3.14%   |
| TUXEDO InfinityBook   | 11        | 2.47%   |
| ASUS VivoBook         | 10        | 2.24%   |
| Dell XPS              | 9         | 2.02%   |
| Toshiba Satellite     | 7         | 1.57%   |
| HP ZBook              | 7         | 1.57%   |
| HP ProBook            | 7         | 1.57%   |
| TUXEDO Polaris        | 6         | 1.35%   |
| TUXEDO Book           | 6         | 1.35%   |
| HP Laptop             | 6         | 1.35%   |
| HP ENVY               | 6         | 1.35%   |
| TUXEDO Pulse          | 5         | 1.12%   |
| Dell Vostro           | 5         | 1.12%   |
| Acer Swift            | 5         | 1.12%   |
| Lenovo ThinkBook      | 4         | 0.9%    |
| ASUS ZenBook          | 4         | 0.9%    |
| ASUS ASUS             | 4         | 0.9%    |
| Apple MacBookPro8     | 4         | 0.9%    |
| TUXEDO Aura           | 3         | 0.67%   |
| Packard Bell EasyNote | 3         | 0.67%   |
| HP Notebook           | 3         | 0.67%   |
| HP Compaq             | 3         | 0.67%   |
| Fujitsu LIFEBOOK      | 3         | 0.67%   |
| ASUS ROG              | 3         | 0.67%   |
| Apple MacBookPro11    | 3         | 0.67%   |
| Acer TravelMate       | 3         | 0.67%   |
| TUXEDO Stellaris      | 2         | 0.45%   |
| TUXEDO P95            | 2         | 0.45%   |
| Standard MT40II       | 2         | 0.45%   |
| Razer Blade           | 2         | 0.45%   |
| MSI Prestige          | 2         | 0.45%   |
| MSI Modern            | 2         | 0.45%   |
| MSI GL65              | 2         | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 57        | 12.78%  |
| 2019 | 53        | 11.88%  |
| 2021 | 45        | 10.09%  |
| 2018 | 43        | 9.64%   |
| 2017 | 32        | 7.17%   |
| 2011 | 30        | 6.73%   |
| 2012 | 27        | 6.05%   |
| 2016 | 26        | 5.83%   |
| 2014 | 25        | 5.61%   |
| 2013 | 25        | 5.61%   |
| 2015 | 19        | 4.26%   |
| 2010 | 18        | 4.04%   |
| 2008 | 15        | 3.36%   |
| 2009 | 10        | 2.24%   |
| 2007 | 8         | 1.79%   |
| 2022 | 7         | 1.57%   |
| 2023 | 5         | 1.12%   |
| 2024 | 1         | 0.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 446       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 402       | 89.93%  |
| Enabled  | 45        | 10.07%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 438       | 98.21%  |
| Yes  | 8         | 1.79%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 134       | 29.71%  |
| 16.01-24.0  | 92        | 20.4%   |
| 8.01-16.0   | 75        | 16.63%  |
| 3.01-4.0    | 73        | 16.19%  |
| 32.01-64.0  | 41        | 9.09%   |
| 64.01-256.0 | 17        | 3.77%   |
| 1.01-2.0    | 11        | 2.44%   |
| 24.01-32.0  | 4         | 0.89%   |
| 2.01-3.0    | 4         | 0.89%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 155       | 32.02%  |
| 1.01-2.0   | 127       | 26.24%  |
| 4.01-8.0   | 89        | 18.39%  |
| 3.01-4.0   | 77        | 15.91%  |
| 8.01-16.0  | 26        | 5.37%   |
| 16.01-24.0 | 4         | 0.83%   |
| 0.51-1.0   | 4         | 0.83%   |
| 24.01-32.0 | 2         | 0.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 332       | 73.45%  |
| 2      | 104       | 23.01%  |
| 3      | 14        | 3.1%    |
| 0      | 2         | 0.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 325       | 72.71%  |
| Yes       | 122       | 27.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 356       | 79.46%  |
| No        | 92        | 20.54%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 441       | 98.66%  |
| No        | 6         | 1.34%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 378       | 84.38%  |
| No        | 70        | 15.63%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| Germany            | 69        | 15.47%  |
| USA                | 58        | 13%     |
| France             | 33        | 7.4%    |
| Brazil             | 29        | 6.5%    |
| Italy              | 18        | 4.04%   |
| UK                 | 17        | 3.81%   |
| India              | 16        | 3.59%   |
| Russia             | 15        | 3.36%   |
| Canada             | 13        | 2.91%   |
| Spain              | 11        | 2.47%   |
| Netherlands        | 11        | 2.47%   |
| Argentina          | 10        | 2.24%   |
| Poland             | 9         | 2.02%   |
| Mexico             | 8         | 1.79%   |
| Austria            | 6         | 1.35%   |
| Australia          | 6         | 1.35%   |
| Ukraine            | 5         | 1.12%   |
| South Africa       | 5         | 1.12%   |
| Hungary            | 5         | 1.12%   |
| Turkey             | 4         | 0.9%    |
| Switzerland        | 4         | 0.9%    |
| Portugal           | 4         | 0.9%    |
| Iran               | 4         | 0.9%    |
| Indonesia          | 4         | 0.9%    |
| Greece             | 4         | 0.9%    |
| Finland            | 4         | 0.9%    |
| Czechia            | 4         | 0.9%    |
| Colombia           | 4         | 0.9%    |
| Chile              | 4         | 0.9%    |
| Belgium            | 4         | 0.9%    |
| Sweden             | 3         | 0.67%   |
| Norway             | 3         | 0.67%   |
| Japan              | 3         | 0.67%   |
| Ireland            | 3         | 0.67%   |
| Dominican Republic | 3         | 0.67%   |
| Slovenia           | 2         | 0.45%   |
| Singapore          | 2         | 0.45%   |
| Peru               | 2         | 0.45%   |
| Malaysia           | 2         | 0.45%   |
| Kenya              | 2         | 0.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Sao Paulo          | 6         | 1.3%    |
| Moscow             | 6         | 1.3%    |
| Berlin             | 6         | 1.3%    |
| Budapest           | 5         | 1.08%   |
| Tehran             | 4         | 0.86%   |
| Ravensburg         | 4         | 0.86%   |
| Athens             | 4         | 0.86%   |
| Warsaw             | 3         | 0.65%   |
| Vienna             | 3         | 0.65%   |
| St Petersburg      | 3         | 0.65%   |
| Santo Domingo Este | 3         | 0.65%   |
| Pune               | 3         | 0.65%   |
| Prague             | 3         | 0.65%   |
| Paris              | 3         | 0.65%   |
| Nuremberg          | 3         | 0.65%   |
| Munich             | 3         | 0.65%   |
| Mumbai             | 3         | 0.65%   |
| Montreal           | 3         | 0.65%   |
| Milan              | 3         | 0.65%   |
| Los Angeles        | 3         | 0.65%   |
| Kyiv               | 3         | 0.65%   |
| Hamburg            | 3         | 0.65%   |
| Frankfurt am Main  | 3         | 0.65%   |
| Dublin             | 3         | 0.65%   |
| Brasília          | 3         | 0.65%   |
| Belo Horizonte     | 3         | 0.65%   |
| Austin             | 3         | 0.65%   |
| Wolfsburg          | 2         | 0.43%   |
| Victoria           | 2         | 0.43%   |
| Vancouver          | 2         | 0.43%   |
| The Hague          | 2         | 0.43%   |
| Sydney             | 2         | 0.43%   |
| Sunnyvale          | 2         | 0.43%   |
| Stuttgart          | 2         | 0.43%   |
| Singapore          | 2         | 0.43%   |
| San Miguel         | 2         | 0.43%   |
| San Francisco      | 2         | 0.43%   |
| Portland           | 2         | 0.43%   |
| Niterói           | 2         | 0.43%   |
| Nairobi            | 2         | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 122       | 160    | 22.02%  |
| WDC                            | 56        | 60     | 10.11%  |
| Seagate                        | 49        | 52     | 8.84%   |
| Toshiba                        | 46        | 57     | 8.3%    |
| Unknown                        | 40        | 47     | 7.22%   |
| SanDisk                        | 32        | 35     | 5.78%   |
| SK hynix                       | 22        | 24     | 3.97%   |
| Kingston                       | 21        | 22     | 3.79%   |
| Intel                          | 19        | 24     | 3.43%   |
| Crucial                        | 19        | 28     | 3.43%   |
| Micron Technology              | 16        | 18     | 2.89%   |
| A-DATA Technology              | 11        | 13     | 1.99%   |
| HGST                           | 10        | 13     | 1.81%   |
| Hitachi                        | 9         | 9      | 1.62%   |
| China                          | 8         | 12     | 1.44%   |
| Apple                          | 8         | 8      | 1.44%   |
| SPCC                           | 7         | 8      | 1.26%   |
| PNY                            | 5         | 10     | 0.9%    |
| KIOXIA                         | 3         | 3      | 0.54%   |
| JMicron Technology             | 3         | 3      | 0.54%   |
| Unknown                        | 3         | 3      | 0.54%   |
| Micron/Crucial Technology      | 2         | 2      | 0.36%   |
| LITEON                         | 2         | 2      | 0.36%   |
| Lenovo                         | 2         | 2      | 0.36%   |
| KingSpec                       | 2         | 2      | 0.36%   |
| Intenso                        | 2         | 3      | 0.36%   |
| Hewlett-Packard                | 2         | 1      | 0.36%   |
| Gigabyte Technology            | 2         | 2      | 0.36%   |
| Corsair                        | 2         | 3      | 0.36%   |
| YMTC                           | 1         | 1      | 0.18%   |
| VISIPRO                        | 1         | 1      | 0.18%   |
| Vaseky                         | 1         | 1      | 0.18%   |
| USB30                          | 1         | 1      | 0.18%   |
| Union Memory                   | 1         | 1      | 0.18%   |
| Transcend                      | 1         | 1      | 0.18%   |
| TO Exter                       | 1         | 1      | 0.18%   |
| Teclast                        | 1         | 2      | 0.18%   |
| SSSTC                          | 1         | 2      | 0.18%   |
| Solid State Storage Technology | 1         | 1      | 0.18%   |
| Silicon Motion                 | 1         | 1      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                            | 7         | 1.22%   |
| Unknown MMC Card  32GB                            | 7         | 1.22%   |
| Toshiba MQ04ABF100 1TB                            | 7         | 1.22%   |
| Toshiba MQ01ABD100 1TB                            | 7         | 1.22%   |
| Seagate ST1000LM035-1RK172 1TB                    | 6         | 1.05%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 6         | 1.05%   |
| Samsung SSD 860 EVO M.2 500GB                     | 6         | 1.05%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 6         | 1.05%   |
| WDC WD10JPVX-22JC3T0 1TB                          | 5         | 0.87%   |
| Seagate ST9500325AS 500GB                         | 5         | 0.87%   |
| Samsung SSD 860 EVO M.2 250GB                     | 5         | 0.87%   |
| Samsung SSD 860 EVO 500GB                         | 5         | 0.87%   |
| Samsung NVMe SSD Drive 1TB                        | 5         | 0.87%   |
| Unknown SD/MMC/MS PRO 128GB                       | 4         | 0.7%    |
| SK hynix NVMe SSD Drive 256GB                     | 4         | 0.7%    |
| SanDisk NVMe SSD Drive 512GB                      | 4         | 0.7%    |
| Samsung SSD 970 EVO Plus 1TB                      | 4         | 0.7%    |
| Samsung NVMe SSD Drive 512GB                      | 4         | 0.7%    |
| Samsung NVMe SSD Drive 500GB                      | 4         | 0.7%    |
| Kingston SA400S37240G 240GB SSD                   | 4         | 0.7%    |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 3         | 0.52%   |
| Unknown SD64G  64GB                               | 3         | 0.52%   |
| Unknown MMC Card  16GB                            | 3         | 0.52%   |
| SPCC Solid State Disk 120GB                       | 3         | 0.52%   |
| SK hynix BC501 NVMe Solid State Drive 512GB       | 3         | 0.52%   |
| Seagate ST500LT012-1DG142 500GB                   | 3         | 0.52%   |
| Seagate ST1000LX015-1U7172 1TB                    | 3         | 0.52%   |
| SanDisk SSD PLUS 480GB                            | 3         | 0.52%   |
| Samsung SSD 980 PRO 1TB                           | 3         | 0.52%   |
| Samsung SSD 980 500GB                             | 3         | 0.52%   |
| Samsung SSD 970 EVO Plus 500GB                    | 3         | 0.52%   |
| Samsung SSD 970 EVO 500GB                         | 3         | 0.52%   |
| Samsung SSD 840 EVO 250GB                         | 3         | 0.52%   |
| Samsung SSD 750 EVO 250GB                         | 3         | 0.52%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB            | 3         | 0.52%   |
| Samsung NVMe SSD Drive 2TB                        | 3         | 0.52%   |
| HGST HTS541010A9E680 1TB                          | 3         | 0.52%   |
| Crucial CT480BX500SSD1 480GB                      | 3         | 0.52%   |
| Crucial CT240BX500SSD1 240GB                      | 3         | 0.52%   |
| China SSD 256GB                                   | 3         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 46        | 49     | 33.58%  |
| Toshiba             | 32        | 36     | 23.36%  |
| WDC                 | 30        | 33     | 21.9%   |
| HGST                | 10        | 13     | 7.3%    |
| Hitachi             | 9         | 9      | 6.57%   |
| Unknown             | 4         | 4      | 2.92%   |
| Samsung Electronics | 2         | 2      | 1.46%   |
| JMicron Technology  | 2         | 2      | 1.46%   |
| TO Exter            | 1         | 1      | 0.73%   |
| Fujitsu             | 1         | 1      | 0.73%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 52        | 70     | 26.26%  |
| SanDisk             | 21        | 21     | 10.61%  |
| Crucial             | 18        | 27     | 9.09%   |
| Kingston            | 17        | 17     | 8.59%   |
| WDC                 | 10        | 10     | 5.05%   |
| Micron Technology   | 8         | 9      | 4.04%   |
| China               | 8         | 12     | 4.04%   |
| SPCC                | 7         | 8      | 3.54%   |
| Intel               | 7         | 7      | 3.54%   |
| A-DATA Technology   | 7         | 8      | 3.54%   |
| Apple               | 6         | 6      | 3.03%   |
| PNY                 | 5         | 10     | 2.53%   |
| Toshiba             | 3         | 3      | 1.52%   |
| SK hynix            | 3         | 3      | 1.52%   |
| Seagate             | 2         | 2      | 1.01%   |
| LITEON              | 2         | 2      | 1.01%   |
| KingSpec            | 2         | 2      | 1.01%   |
| Intenso             | 2         | 3      | 1.01%   |
| Gigabyte Technology | 2         | 2      | 1.01%   |
| VISIPRO             | 1         | 1      | 0.51%   |
| Vaseky              | 1         | 1      | 0.51%   |
| USB30               | 1         | 1      | 0.51%   |
| Unknown             | 1         | 1      | 0.51%   |
| Union Memory        | 1         | 1      | 0.51%   |
| Transcend           | 1         | 1      | 0.51%   |
| Teclast             | 1         | 2      | 0.51%   |
| Patriot             | 1         | 1      | 0.51%   |
| OWC                 | 1         | 1      | 0.51%   |
| Netac               | 1         | 1      | 0.51%   |
| LITEONIT            | 1         | 1      | 0.51%   |
| Hewlett-Packard     | 1         | 1      | 0.51%   |
| FORESEE             | 1         | 1      | 0.51%   |
| Dogfish             | 1         | 1      | 0.51%   |
| Corsair             | 1         | 2      | 0.51%   |
| BIWIN               | 1         | 1      | 0.51%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 183       | 240    | 34.53%  |
| NVMe    | 169       | 213    | 31.89%  |
| HDD     | 131       | 150    | 24.72%  |
| MMC     | 36        | 45     | 6.79%   |
| Unknown | 11        | 11     | 2.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 277       | 379    | 55.07%  |
| NVMe | 169       | 213    | 33.6%   |
| MMC  | 36        | 45     | 7.16%   |
| SAS  | 21        | 22     | 4.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 208       | 260    | 66.45%  |
| 0.51-1.0   | 89        | 110    | 28.43%  |
| 1.01-2.0   | 14        | 18     | 4.47%   |
| 3.01-4.0   | 2         | 2      | 0.64%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 142       | 31.49%  |
| 251-500        | 135       | 29.93%  |
| 501-1000       | 59        | 13.08%  |
| 51-100         | 35        | 7.76%   |
| 1001-2000      | 23        | 5.1%    |
| 21-50          | 22        | 4.88%   |
| 1-20           | 19        | 4.21%   |
| 2001-3000      | 9         | 2%      |
| More than 3000 | 4         | 0.89%   |
| Unknown        | 3         | 0.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 158       | 33.76%  |
| 21-50          | 95        | 20.3%   |
| 101-250        | 87        | 18.59%  |
| 51-100         | 59        | 12.61%  |
| 251-500        | 37        | 7.91%   |
| 501-1000       | 19        | 4.06%   |
| 1001-2000      | 8         | 1.71%   |
| Unknown        | 3         | 0.64%   |
| More than 3000 | 2         | 0.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB               | 2         | 2      | 7.69%   |
| Seagate ST9500325AS 500GB            | 2         | 2      | 7.69%   |
| WDC WD6400BPVT-60HXZT3 640GB         | 1         | 1      | 3.85%   |
| WDC WD5000BPVT-00HXZT1 500GB         | 1         | 1      | 3.85%   |
| WDC WD2500BEKT-75PVMT1 250GB         | 1         | 1      | 3.85%   |
| WDC WD10JPVX-60JC3T0 1TB             | 1         | 1      | 3.85%   |
| Toshiba MQ01ABF050 500GB             | 1         | 1      | 3.85%   |
| Toshiba MQ01ABD075 752GB             | 1         | 1      | 3.85%   |
| Toshiba MQ01ABD050 500GB             | 1         | 1      | 3.85%   |
| Toshiba MK5055GSX 500GB              | 1         | 1      | 3.85%   |
| Toshiba MK3265GSXN 320GB             | 1         | 1      | 3.85%   |
| Toshiba MK2561GSYN 250GB             | 1         | 1      | 3.85%   |
| Seagate ST9750420AS 752GB            | 1         | 1      | 3.85%   |
| Seagate ST9500423AS 500GB            | 1         | 1      | 3.85%   |
| Seagate ST500LX012-1LM162-SSHD 500GB | 1         | 1      | 3.85%   |
| Seagate ST500LT012-1DG142 500GB      | 1         | 1      | 3.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 1         | 1      | 3.85%   |
| PNY SSD2SC120G3LC709B121-460I 120GB  | 1         | 1      | 3.85%   |
| Kingston SNS4151S316G 16GB SSD       | 1         | 1      | 3.85%   |
| HGST HTS725032A7E630 320GB           | 1         | 2      | 3.85%   |
| HGST HTS541075A9E680 752GB           | 1         | 1      | 3.85%   |
| HGST HTS541010A9E680 1TB             | 1         | 1      | 3.85%   |
| Crucial CT500P1SSD8 500GB            | 1         | 1      | 3.85%   |
| China SSD 256GB                      | 1         | 1      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Toshiba  | 8         | 8      | 30.77%  |
| Seagate  | 7         | 7      | 26.92%  |
| WDC      | 4         | 4      | 15.38%  |
| HGST     | 3         | 4      | 11.54%  |
| PNY      | 1         | 1      | 3.85%   |
| Kingston | 1         | 1      | 3.85%   |
| Crucial  | 1         | 1      | 3.85%   |
| China    | 1         | 1      | 3.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 8         | 8      | 36.36%  |
| Seagate | 7         | 7      | 31.82%  |
| WDC     | 4         | 4      | 18.18%  |
| HGST    | 3         | 4      | 13.64%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 22        | 23     | 84.62%  |
| SSD  | 3         | 3      | 11.54%  |
| NVMe | 1         | 1      | 3.85%   |

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
| Detected | 259       | 379    | 55.22%  |
| Works    | 185       | 253    | 39.45%  |
| Malfunc  | 25        | 27     | 5.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 311       | 59.35%  |
| Samsung Electronics            | 75        | 14.31%  |
| AMD                            | 40        | 7.63%   |
| SanDisk                        | 26        | 4.96%   |
| SK hynix                       | 17        | 3.24%   |
| Toshiba America Info Systems   | 10        | 1.91%   |
| Micron Technology              | 9         | 1.72%   |
| KIOXIA                         | 4         | 0.76%   |
| Kingston Technology Company    | 4         | 0.76%   |
| ADATA Technology               | 4         | 0.76%   |
| Phison Electronics             | 3         | 0.57%   |
| Nvidia                         | 3         | 0.57%   |
| Micron/Crucial Technology      | 3         | 0.57%   |
| Solid State Storage Technology | 2         | 0.38%   |
| Silicon Motion                 | 2         | 0.38%   |
| Realtek Semiconductor          | 2         | 0.38%   |
| Lenovo                         | 2         | 0.38%   |
| Apple                          | 2         | 0.38%   |
| Yangtze Memory Technologies    | 1         | 0.19%   |
| Union Memory (Shenzhen)        | 1         | 0.19%   |
| Solidigm                       | 1         | 0.19%   |
| Shenzhen Longsys Electronics   | 1         | 0.19%   |
| Marvell Technology Group       | 1         | 0.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 41        | 7.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 39        | 7.08%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 37        | 6.72%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 32        | 5.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 25        | 4.54%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 20        | 3.63%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 15        | 2.72%   |
| Intel Comet Lake SATA AHCI Controller                                          | 15        | 2.72%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 14        | 2.54%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 13        | 2.36%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 13        | 2.36%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 13        | 2.36%   |
| Intel Volume Management Device NVMe RAID Controller                            | 12        | 2.18%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 12        | 2.18%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 10        | 1.81%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 10        | 1.81%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 10        | 1.81%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 9         | 1.63%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 8         | 1.45%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 8         | 1.45%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 8         | 1.45%   |
| Intel SSD 660P Series                                                          | 7         | 1.27%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 7         | 1.27%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 6         | 1.09%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 6         | 1.09%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 6         | 1.09%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 6         | 1.09%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 6         | 1.09%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 5         | 0.91%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 5         | 0.91%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 5         | 0.91%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 5         | 0.91%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 4         | 0.73%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 4         | 0.73%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 4         | 0.73%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 4         | 0.73%   |
| Intel Tiger Lake-LP SATA Controller                                            | 4         | 0.73%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 4         | 0.73%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 3         | 0.54%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 3         | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 319       | 59.29%  |
| NVMe | 171       | 31.78%  |
| RAID | 34        | 6.32%   |
| IDE  | 14        | 2.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 382       | 85.65%  |
| AMD    | 64        | 14.35%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 17        | 3.81%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 14        | 3.14%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 10        | 2.24%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 10        | 2.24%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 9         | 2.02%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 9         | 2.02%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 7         | 1.57%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 7         | 1.57%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 6         | 1.35%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 6         | 1.35%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 6         | 1.35%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 6         | 1.35%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 1.35%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 6         | 1.35%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 1.12%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 5         | 1.12%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.12%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 1.12%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 1.12%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 1.12%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 4         | 0.9%    |
| Intel Core i7-3520M CPU @ 2.90GHz             | 4         | 0.9%    |
| Intel Core i7-10710U CPU @ 1.10GHz            | 4         | 0.9%    |
| Intel Core i5-8350U CPU @ 1.70GHz             | 4         | 0.9%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 0.9%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 0.9%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 4         | 0.9%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 4         | 0.9%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 4         | 0.9%    |
| AMD Ryzen 5 4600H with Radeon Graphics        | 4         | 0.9%    |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 3         | 0.67%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 3         | 0.67%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 0.67%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 3         | 0.67%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 3         | 0.67%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 3         | 0.67%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 3         | 0.67%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 3         | 0.67%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 3         | 0.67%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 0.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 145       | 32.51%  |
| Intel Core i5                  | 104       | 23.32%  |
| Other                          | 36        | 8.07%   |
| Intel Core i3                  | 27        | 6.05%   |
| Intel Celeron                  | 25        | 5.61%   |
| AMD Ryzen 7                    | 21        | 4.71%   |
| AMD Ryzen 5                    | 17        | 3.81%   |
| Intel Core 2 Duo               | 12        | 2.69%   |
| Intel Pentium                  | 10        | 2.24%   |
| Intel Atom                     | 7         | 1.57%   |
| Intel Pentium Silver           | 5         | 1.12%   |
| AMD Ryzen 9                    | 4         | 0.9%    |
| AMD A8                         | 4         | 0.9%    |
| AMD A6                         | 4         | 0.9%    |
| Intel Pentium Dual-Core        | 3         | 0.67%   |
| AMD Ryzen 3                    | 3         | 0.67%   |
| AMD E                          | 3         | 0.67%   |
| Intel Pentium Dual             | 2         | 0.45%   |
| Intel Genuine                  | 2         | 0.45%   |
| Intel Core i9                  | 2         | 0.45%   |
| AMD Turion 64 X2 Mobile        | 2         | 0.45%   |
| Intel Core m5                  | 1         | 0.22%   |
| Intel Core m3                  | 1         | 0.22%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.22%   |
| AMD Ryzen 7 PRO                | 1         | 0.22%   |
| AMD Quad-Core                  | 1         | 0.22%   |
| AMD E1                         | 1         | 0.22%   |
| AMD Athlon II                  | 1         | 0.22%   |
| AMD A10                        | 1         | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 185       | 41.48%  |
| 2      | 183       | 41.03%  |
| 8      | 35        | 7.85%   |
| 6      | 31        | 6.95%   |
| 1      | 4         | 0.9%    |
| 10     | 3         | 0.67%   |
| 16     | 2         | 0.45%   |
| 14     | 2         | 0.45%   |
| 12     | 1         | 0.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 446       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 346       | 77.58%  |
| 1      | 100       | 22.42%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 445       | 99.78%  |
| 32-bit         | 1         | 0.22%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 168       | 36.36%  |
| 0x206a7    | 25        | 5.41%   |
| 0x806ec    | 23        | 4.98%   |
| 0x306a9    | 19        | 4.11%   |
| 0x806ea    | 15        | 3.25%   |
| 0x906ea    | 14        | 3.03%   |
| 0x806c1    | 14        | 3.03%   |
| 0x806e9    | 11        | 2.38%   |
| 0x406e3    | 11        | 2.38%   |
| 0x40651    | 11        | 2.38%   |
| 0x306c3    | 10        | 2.16%   |
| 0x306d4    | 9         | 1.95%   |
| 0x906e9    | 8         | 1.73%   |
| 0x806eb    | 8         | 1.73%   |
| 0xa0652    | 7         | 1.52%   |
| 0x20655    | 7         | 1.52%   |
| 0x0a50000c | 6         | 1.3%    |
| 0x08600106 | 6         | 1.3%    |
| 0x08600103 | 6         | 1.3%    |
| 0x1067a    | 5         | 1.08%   |
| 0x806d1    | 4         | 0.87%   |
| 0x706a8    | 4         | 0.87%   |
| 0x506e3    | 4         | 0.87%   |
| 0x10676    | 4         | 0.87%   |
| 0x08600104 | 4         | 0.87%   |
| 0x08108109 | 4         | 0.87%   |
| 0xa0660    | 3         | 0.65%   |
| 0x706e5    | 3         | 0.65%   |
| 0x406c3    | 3         | 0.65%   |
| 0x30678    | 3         | 0.65%   |
| 0x08608103 | 3         | 0.65%   |
| 0x0810100b | 3         | 0.65%   |
| 0x05000119 | 3         | 0.65%   |
| 0x906a3    | 2         | 0.43%   |
| 0x706a1    | 2         | 0.43%   |
| 0x6fd      | 2         | 0.43%   |
| 0x506c9    | 2         | 0.43%   |
| 0x40661    | 2         | 0.43%   |
| 0x20652    | 2         | 0.43%   |
| 0x106e5    | 2         | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 114       | 25.56%  |
| SandyBridge      | 32        | 7.17%   |
| IvyBridge        | 30        | 6.73%   |
| Haswell          | 30        | 6.73%   |
| Skylake          | 27        | 6.05%   |
| Zen 2            | 23        | 5.16%   |
| TigerLake        | 23        | 5.16%   |
| Silvermont       | 16        | 3.59%   |
| Broadwell        | 16        | 3.59%   |
| Goldmont plus    | 15        | 3.36%   |
| CometLake        | 15        | 3.36%   |
| Penryn           | 14        | 3.14%   |
| Westmere         | 13        | 2.91%   |
| IceLake          | 11        | 2.47%   |
| Unknown          | 11        | 2.47%   |
| Zen 3            | 7         | 1.57%   |
| Zen+             | 6         | 1.35%   |
| Goldmont         | 6         | 1.35%   |
| Zen              | 4         | 0.9%    |
| Core             | 4         | 0.9%    |
| Alderlake Hybrid | 4         | 0.9%    |
| Puma             | 3         | 0.67%   |
| Nehalem          | 3         | 0.67%   |
| Jaguar           | 3         | 0.67%   |
| Bobcat           | 3         | 0.67%   |
| Piledriver       | 2         | 0.45%   |
| K8 Hammer        | 2         | 0.45%   |
| Excavator        | 2         | 0.45%   |
| Bonnell          | 2         | 0.45%   |
| Tremont          | 1         | 0.22%   |
| P6               | 1         | 0.22%   |
| K8 & K10 hybrid  | 1         | 0.22%   |
| K10 Llano        | 1         | 0.22%   |
| K10              | 1         | 0.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 355       | 62.72%  |
| Nvidia | 125       | 22.08%  |
| AMD    | 86        | 15.19%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 30        | 5.21%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 28        | 4.86%   |
| Intel UHD Graphics 620                                                                   | 25        | 4.34%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 24        | 4.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 23        | 3.99%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 22        | 3.82%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 17        | 2.95%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 16        | 2.78%   |
| Intel HD Graphics 620                                                                    | 16        | 2.78%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 15        | 2.6%    |
| Intel HD Graphics 5500                                                                   | 13        | 2.26%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 13        | 2.26%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 12        | 2.08%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 11        | 1.91%   |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 1.74%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 10        | 1.74%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 9         | 1.56%   |
| Intel HD Graphics 630                                                                    | 9         | 1.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 1.56%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 1.22%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 7         | 1.22%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 1.22%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 6         | 1.04%   |
| Intel HD Graphics 530                                                                    | 6         | 1.04%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 1.04%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 0.87%   |
| Nvidia GP108M [GeForce MX150]                                                            | 5         | 0.87%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 0.87%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 0.87%   |
| Intel HD Graphics 500                                                                    | 5         | 0.87%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 5         | 0.87%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 0.87%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5         | 0.87%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 4         | 0.69%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 4         | 0.69%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.69%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 4         | 0.69%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 4         | 0.69%   |
| Intel Comet Lake UHD Graphics                                                            | 4         | 0.69%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 242       | 54.26%  |
| Intel + Nvidia | 91        | 20.4%   |
| 1 x AMD        | 52        | 11.66%  |
| 1 x Nvidia     | 23        | 5.16%   |
| Intel + AMD    | 19        | 4.26%   |
| AMD + Nvidia   | 10        | 2.24%   |
| 2 x AMD        | 5         | 1.12%   |
| Other          | 2         | 0.45%   |
| 2 x Nvidia     | 1         | 0.22%   |
| 2 x Intel      | 1         | 0.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 363       | 80.85%  |
| Proprietary | 77        | 17.15%  |
| Unknown     | 9         | 2%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 326       | 72.12%  |
| 1.01-2.0   | 39        | 8.63%   |
| 0.01-0.5   | 29        | 6.42%   |
| 3.01-4.0   | 19        | 4.2%    |
| 0.51-1.0   | 19        | 4.2%    |
| 7.01-8.0   | 9         | 1.99%   |
| 5.01-6.0   | 9         | 1.99%   |
| 2.01-3.0   | 1         | 0.22%   |
| 8.01-16.0  | 1         | 0.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 95        | 18.06%  |
| AU Optronics            | 87        | 16.54%  |
| BOE                     | 76        | 14.45%  |
| LG Display              | 60        | 11.41%  |
| Samsung Electronics     | 43        | 8.17%   |
| Dell                    | 18        | 3.42%   |
| Apple                   | 17        | 3.23%   |
| Goldstar                | 15        | 2.85%   |
| Chi Mei Optoelectronics | 13        | 2.47%   |
| Sharp                   | 12        | 2.28%   |
| PANDA                   | 9         | 1.71%   |
| Lenovo                  | 8         | 1.52%   |
| Hewlett-Packard         | 7         | 1.33%   |
| Acer                    | 7         | 1.33%   |
| Philips                 | 6         | 1.14%   |
| BenQ                    | 6         | 1.14%   |
| InfoVision              | 5         | 0.95%   |
| AOC                     | 4         | 0.76%   |
| Ancor Communications    | 4         | 0.76%   |
| LGD                     | 3         | 0.57%   |
| LG Philips              | 3         | 0.57%   |
| Unknown (AAA)           | 2         | 0.38%   |
| Sony                    | 2         | 0.38%   |
| Iiyama                  | 2         | 0.38%   |
| Fujitsu Siemens         | 2         | 0.38%   |
| CSO                     | 2         | 0.38%   |
| ASUSTek Computer        | 2         | 0.38%   |
| Vestel Elektronik       | 1         | 0.19%   |
| UPD                     | 1         | 0.19%   |
| Unknown                 | 1         | 0.19%   |
| TMX                     | 1         | 0.19%   |
| MStar                   | 1         | 0.19%   |
| LaCie                   | 1         | 0.19%   |
| KTC                     | 1         | 0.19%   |
| KDC                     | 1         | 0.19%   |
| JDZ                     | 1         | 0.19%   |
| JDI                     | 1         | 0.19%   |
| InnoLux Display         | 1         | 0.19%   |
| IBM                     | 1         | 0.19%   |
| HKC                     | 1         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 6         | 1.13%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch      | 6         | 1.13%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 5         | 0.94%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 4         | 0.75%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 4         | 0.75%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 4         | 0.75%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                 | 4         | 0.75%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 4         | 0.75%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 3         | 0.56%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 3         | 0.56%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 3         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 3         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 0.56%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 0.56%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 3         | 0.56%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 3         | 0.56%   |
| AU Optronics LCD Monitor AUO623D 1920x1080 309x174mm 14.0-inch        | 3         | 0.56%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 3         | 0.56%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.56%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 3         | 0.56%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch        | 3         | 0.56%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 0.38%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch  | 2         | 0.38%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 2         | 0.38%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch  | 2         | 0.38%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 2         | 0.38%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 2         | 0.38%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.38%   |
| LGD LCD Monitor 1920x1080                                             | 2         | 0.38%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch          | 2         | 0.38%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 2         | 0.38%   |
| LG Display LCD Monitor LGD057E 1920x1080 344x194mm 15.5-inch          | 2         | 0.38%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 2         | 0.38%   |
| LG Display LCD Monitor LGD04AF 1366x768 344x194mm 15.5-inch           | 2         | 0.38%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch          | 2         | 0.38%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 0.38%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch           | 2         | 0.38%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 0.38%   |
| InfoVision LCD Monitor IVO0579 1366x768 310x170mm 13.9-inch           | 2         | 0.38%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2         | 0.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 219       | 44.97%  |
| 1366x768 (WXGA)    | 130       | 26.69%  |
| 1600x900 (HD+)     | 21        | 4.31%   |
| 2560x1440 (QHD)    | 20        | 4.11%   |
| 3840x2160 (4K)     | 16        | 3.29%   |
| 1280x800 (WXGA)    | 15        | 3.08%   |
| 1440x900 (WXGA+)   | 11        | 2.26%   |
| 1920x1200 (WUXGA)  | 10        | 2.05%   |
| 3440x1440          | 6         | 1.23%   |
| 2880x1800          | 5         | 1.03%   |
| 2560x1080          | 4         | 0.82%   |
| 1680x1050 (WSXGA+) | 4         | 0.82%   |
| 3200x1800 (QHD+)   | 3         | 0.62%   |
| 2560x1600          | 3         | 0.62%   |
| 1280x1024 (SXGA)   | 3         | 0.62%   |
| 3000x2000          | 2         | 0.41%   |
| 2256x1504          | 2         | 0.41%   |
| 2160x1440          | 2         | 0.41%   |
| 1920x1280          | 2         | 0.41%   |
| 1360x768           | 2         | 0.41%   |
| 3840x2400          | 1         | 0.21%   |
| 3840x1100          | 1         | 0.21%   |
| 3840x1080          | 1         | 0.21%   |
| 3456x2160          | 1         | 0.21%   |
| 2520x1680          | 1         | 0.21%   |
| 1600x1200          | 1         | 0.21%   |
| 1280x768           | 1         | 0.21%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 197       | 37.1%   |
| 13      | 94        | 17.7%   |
| 14      | 65        | 12.24%  |
| 17      | 34        | 6.4%    |
| 24      | 24        | 4.52%   |
| 27      | 18        | 3.39%   |
| 23      | 16        | 3.01%   |
| 11      | 12        | 2.26%   |
| 34      | 10        | 1.88%   |
| 12      | 9         | 1.69%   |
| 21      | 8         | 1.51%   |
| 19      | 6         | 1.13%   |
| Unknown | 6         | 1.13%   |
| 31      | 5         | 0.94%   |
| 84      | 3         | 0.56%   |
| 40      | 3         | 0.56%   |
| 32      | 3         | 0.56%   |
| 18      | 3         | 0.56%   |
| 16      | 3         | 0.56%   |
| 72      | 2         | 0.38%   |
| 48      | 2         | 0.38%   |
| 22      | 2         | 0.38%   |
| 60      | 1         | 0.19%   |
| 54      | 1         | 0.19%   |
| 44      | 1         | 0.19%   |
| 29      | 1         | 0.19%   |
| 20      | 1         | 0.19%   |
| 10      | 1         | 0.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 309       | 58.63%  |
| 201-300     | 66        | 12.52%  |
| 501-600     | 53        | 10.06%  |
| 351-400     | 42        | 7.97%   |
| 401-500     | 18        | 3.42%   |
| 701-800     | 13        | 2.47%   |
| 601-700     | 7         | 1.33%   |
| Unknown     | 6         | 1.14%   |
| 1501-2000   | 5         | 0.95%   |
| 1001-1500   | 4         | 0.76%   |
| 801-900     | 3         | 0.57%   |
| 901-1000    | 1         | 0.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 380       | 81.37%  |
| 16/10   | 56        | 11.99%  |
| 3/2     | 10        | 2.14%   |
| 21/9    | 10        | 2.14%   |
| Unknown | 5         | 1.07%   |
| 5/4     | 3         | 0.64%   |
| 4/3     | 1         | 0.21%   |
| 32/9    | 1         | 0.21%   |
| 3.40    | 1         | 0.21%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 197       | 37.24%  |
| 81-90          | 128       | 24.2%   |
| 201-250        | 39        | 7.37%   |
| 71-80          | 29        | 5.48%   |
| 121-130        | 27        | 5.1%    |
| 351-500        | 19        | 3.59%   |
| 301-350        | 18        | 3.4%    |
| 51-60          | 13        | 2.46%   |
| 61-70          | 9         | 1.7%    |
| More than 1000 | 8         | 1.51%   |
| 251-300        | 8         | 1.51%   |
| 151-200        | 8         | 1.51%   |
| 131-140        | 7         | 1.32%   |
| Unknown        | 6         | 1.13%   |
| 501-1000       | 5         | 0.95%   |
| 141-150        | 3         | 0.57%   |
| 111-120        | 2         | 0.38%   |
| 91-100         | 2         | 0.38%   |
| 41-50          | 1         | 0.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 210       | 40.46%  |
| 101-120       | 149       | 28.71%  |
| 51-100        | 84        | 16.18%  |
| 161-240       | 41        | 7.9%    |
| More than 240 | 19        | 3.66%   |
| 1-50          | 10        | 1.93%   |
| Unknown       | 6         | 1.16%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 354       | 77.29%  |
| 2     | 85        | 18.56%  |
| 3     | 10        | 2.18%   |
| 0     | 9         | 1.97%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 264       | 36.67%  |
| Realtek Semiconductor                 | 231       | 32.08%  |
| Qualcomm Atheros                      | 91        | 12.64%  |
| Broadcom                              | 40        | 5.56%   |
| Broadcom Limited                      | 16        | 2.22%   |
| MediaTek                              | 10        | 1.39%   |
| Marvell Technology Group              | 7         | 0.97%   |
| Ralink                                | 6         | 0.83%   |
| Hewlett-Packard                       | 5         | 0.69%   |
| DisplayLink                           | 5         | 0.69%   |
| ASIX Electronics                      | 5         | 0.69%   |
| Xiaomi                                | 4         | 0.56%   |
| Lenovo                                | 4         | 0.56%   |
| Sierra Wireless                       | 3         | 0.42%   |
| NetGear                               | 3         | 0.42%   |
| JMicron Technology                    | 3         | 0.42%   |
| Huawei Technologies                   | 3         | 0.42%   |
| TP-Link                               | 2         | 0.28%   |
| Samsung Electronics                   | 2         | 0.28%   |
| Ralink Technology                     | 2         | 0.28%   |
| Nvidia                                | 2         | 0.28%   |
| Qualcomm Atheros Communications       | 1         | 0.14%   |
| Novatek Microelectronics              | 1         | 0.14%   |
| Motorola PCS                          | 1         | 0.14%   |
| Google                                | 1         | 0.14%   |
| FIBOCOM                               | 1         | 0.14%   |
| Ericsson Business Mobile Networks     | 1         | 0.14%   |
| Edimax Technology                     | 1         | 0.14%   |
| Dell                                  | 1         | 0.14%   |
| BUFFALO                               | 1         | 0.14%   |
| ASUSTek Computer                      | 1         | 0.14%   |
| Apple                                 | 1         | 0.14%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 139       | 16.13%  |
| Intel Wi-Fi 6 AX200                                                    | 42        | 4.87%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 35        | 4.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 29        | 3.36%   |
| Intel Wireless 8265 / 8275                                             | 28        | 3.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 19        | 2.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 19        | 2.2%    |
| Intel Wireless 8260                                                    | 15        | 1.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 14        | 1.62%   |
| Intel Wi-Fi 6 AX201                                                    | 14        | 1.62%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 14        | 1.62%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 14        | 1.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 13        | 1.51%   |
| Intel Wireless 7265                                                    | 13        | 1.51%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 12        | 1.39%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 11        | 1.28%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 10        | 1.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 10        | 1.16%   |
| Intel Wireless 7260                                                    | 9         | 1.04%   |
| Intel Ethernet Connection (4) I219-LM                                  | 9         | 1.04%   |
| Broadcom BCM43142 802.11b/g/n                                          | 9         | 1.04%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 8         | 0.93%   |
| Realtek RTL8125 2.5GbE Controller                                      | 7         | 0.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 7         | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 7         | 0.81%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 7         | 0.81%   |
| Intel Wireless 3165                                                    | 6         | 0.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 6         | 0.7%    |
| Intel Comet Lake PCH CNVi WiFi                                         | 6         | 0.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                        | 6         | 0.7%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 6         | 0.7%    |
| Broadcom BCM4331 802.11a/b/g/n                                         | 6         | 0.7%    |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 5         | 0.58%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 5         | 0.58%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 5         | 0.58%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 5         | 0.58%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 0.58%   |
| Intel Ethernet Connection (6) I219-V                                   | 5         | 0.58%   |
| Intel Ethernet Connection (2) I219-LM                                  | 5         | 0.58%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 5         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 252       | 54.55%  |
| Qualcomm Atheros                      | 74        | 16.02%  |
| Realtek Semiconductor                 | 59        | 12.77%  |
| Broadcom                              | 33        | 7.14%   |
| Broadcom Limited                      | 11        | 2.38%   |
| MediaTek                              | 10        | 2.16%   |
| Ralink                                | 6         | 1.3%    |
| Sierra Wireless                       | 3         | 0.65%   |
| NetGear                               | 3         | 0.65%   |
| TP-Link                               | 2         | 0.43%   |
| Ralink Technology                     | 2         | 0.43%   |
| Qualcomm Atheros Communications       | 1         | 0.22%   |
| Hewlett-Packard                       | 1         | 0.22%   |
| FIBOCOM                               | 1         | 0.22%   |
| Edimax Technology                     | 1         | 0.22%   |
| BUFFALO                               | 1         | 0.22%   |
| ASUSTek Computer                      | 1         | 0.22%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 42        | 9.07%   |
| Intel Wireless 8265 / 8275                                           | 28        | 6.05%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 19        | 4.1%    |
| Intel Wireless 8260                                                  | 15        | 3.24%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 14        | 3.02%   |
| Intel Wi-Fi 6 AX201                                                  | 14        | 3.02%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 14        | 3.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 14        | 3.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 13        | 2.81%   |
| Intel Wireless 7265                                                  | 13        | 2.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 12        | 2.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 11        | 2.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 10        | 2.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 10        | 2.16%   |
| Intel Wireless 7260                                                  | 9         | 1.94%   |
| Broadcom BCM43142 802.11b/g/n                                        | 9         | 1.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 8         | 1.73%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 7         | 1.51%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 7         | 1.51%   |
| Intel Wireless 3165                                                  | 6         | 1.3%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 6         | 1.3%    |
| Intel Comet Lake PCH CNVi WiFi                                       | 6         | 1.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                      | 6         | 1.3%    |
| Broadcom BCM4331 802.11a/b/g/n                                       | 6         | 1.3%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 5         | 1.08%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 5         | 1.08%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 5         | 1.08%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 4         | 0.86%   |
| Realtek 802.11n WLAN Adapter                                         | 4         | 0.86%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 4         | 0.86%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 4         | 0.86%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 4         | 0.86%   |
| Intel Gemini Lake PCH CNVi WiFi                                      | 4         | 0.86%   |
| Intel Centrino Wireless-N 2230                                       | 4         | 0.86%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                         | 4         | 0.86%   |
| Intel Centrino Ultimate-N 6300                                       | 4         | 0.86%   |
| Intel Centrino Advanced-N 6200                                       | 4         | 0.86%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 4         | 0.86%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 4         | 0.86%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 4         | 0.86%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 207       | 54.62%  |
| Intel                    | 88        | 23.22%  |
| Qualcomm Atheros         | 26        | 6.86%   |
| Broadcom                 | 17        | 4.49%   |
| Marvell Technology Group | 7         | 1.85%   |
| DisplayLink              | 5         | 1.32%   |
| Broadcom Limited         | 5         | 1.32%   |
| ASIX Electronics         | 5         | 1.32%   |
| Xiaomi                   | 4         | 1.06%   |
| Lenovo                   | 4         | 1.06%   |
| JMicron Technology       | 3         | 0.79%   |
| Samsung Electronics      | 2         | 0.53%   |
| Nvidia                   | 2         | 0.53%   |
| Hewlett-Packard          | 2         | 0.53%   |
| Google                   | 1         | 0.26%   |
| Apple                    | 1         | 0.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 139       | 35.64%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 35        | 8.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 29        | 7.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 19        | 4.87%   |
| Intel Ethernet Connection (4) I219-LM                                          | 9         | 2.31%   |
| Realtek RTL8125 2.5GbE Controller                                              | 7         | 1.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 7         | 1.79%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 6         | 1.54%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 5         | 1.28%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 5         | 1.28%   |
| Intel Ethernet Connection I219-LM                                              | 5         | 1.28%   |
| Intel Ethernet Connection (6) I219-V                                           | 5         | 1.28%   |
| Intel Ethernet Connection (2) I219-LM                                          | 5         | 1.28%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 5         | 1.28%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 4         | 1.03%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 4         | 1.03%   |
| Intel Ethernet Connection I219-V                                               | 4         | 1.03%   |
| Intel Ethernet Connection I218-LM                                              | 4         | 1.03%   |
| Intel Ethernet Connection I217-LM                                              | 4         | 1.03%   |
| Intel 82577LM Gigabit Network Connection                                       | 4         | 1.03%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 4         | 1.03%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 3         | 0.77%   |
| Intel Ethernet Connection (6) I219-LM                                          | 3         | 0.77%   |
| Intel Ethernet Connection (5) I219-LM                                          | 3         | 0.77%   |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 0.77%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 0.77%   |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 0.77%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 0.51%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 2         | 0.51%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 0.51%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.51%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.51%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 2         | 0.51%   |
| Lenovo ThinkPad Lan                                                            | 2         | 0.51%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.51%   |
| Intel Ethernet Connection (13) I219-V                                          | 2         | 0.51%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 0.51%   |
| HP lt4120 Snapdragon X5 LTE                                                    | 2         | 0.51%   |
| DisplayLink Dell Universal Dock D6000                                          | 2         | 0.51%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 440       | 54.66%  |
| Ethernet | 356       | 44.22%  |
| Modem    | 8         | 0.99%   |
| Unknown  | 1         | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 375       | 80.13%  |
| Ethernet | 93        | 19.87%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 327       | 73.15%  |
| 1     | 109       | 24.38%  |
| 0     | 10        | 2.24%   |
| 3     | 1         | 0.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 357       | 78.98%  |
| Yes  | 95        | 21.02%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 205       | 53.81%  |
| Qualcomm Atheros Communications | 33        | 8.66%   |
| Realtek Semiconductor           | 31        | 8.14%   |
| Broadcom                        | 20        | 5.25%   |
| IMC Networks                    | 16        | 4.2%    |
| Apple                           | 16        | 4.2%    |
| Foxconn / Hon Hai               | 14        | 3.67%   |
| Dell                            | 10        | 2.62%   |
| Lite-On Technology              | 9         | 2.36%   |
| Hewlett-Packard                 | 7         | 1.84%   |
| Realtek                         | 5         | 1.31%   |
| Ralink                          | 4         | 1.05%   |
| Cambridge Silicon Radio         | 3         | 0.79%   |
| Toshiba                         | 2         | 0.52%   |
| Foxconn International           | 2         | 0.52%   |
| Smart Modular Technologies      | 1         | 0.26%   |
| MediaTek                        | 1         | 0.26%   |
| Integrated System Solution      | 1         | 0.26%   |
| Belkin Components               | 1         | 0.26%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                                              | 40        | 10.5%   |
| Intel AX200 Bluetooth                                                               | 40        | 10.5%   |
| Intel AX201 Bluetooth                                                               | 35        | 9.19%   |
| Intel Bluetooth wireless interface                                                  | 34        | 8.92%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 23        | 6.04%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 19        | 4.99%   |
| Realtek Bluetooth Radio                                                             | 16        | 4.2%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 14        | 3.67%   |
| Dell DW375 Bluetooth Module                                                         | 9         | 2.36%   |
| Apple Bluetooth Host Controller                                                     | 9         | 2.36%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 6         | 1.57%   |
| Realtek RTL8723B Bluetooth                                                          | 5         | 1.31%   |
| Realtek Bluetooth Radio                                                             | 5         | 1.31%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 5         | 1.31%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 1.31%   |
| IMC Networks Wireless_Device                                                        | 5         | 1.31%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 5         | 1.31%   |
| Apple Bluetooth USB Host Controller                                                 | 5         | 1.31%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 4         | 1.05%   |
| Ralink RT3290 Bluetooth                                                             | 4         | 1.05%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 1.05%   |
| Intel AX210 Bluetooth                                                               | 4         | 1.05%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 1.05%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 4         | 1.05%   |
| Realtek RTL8821A Bluetooth                                                          | 3         | 0.79%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 0.79%   |
| Intel AX211 Bluetooth                                                               | 3         | 0.79%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 3         | 0.79%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 0.79%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 3         | 0.79%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 3         | 0.79%   |
| Realtek 802.11ac WLAN Adapter                                                       | 2         | 0.52%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 0.52%   |
| Lite-On Bluetooth Device                                                            | 2         | 0.52%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 0.52%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 0.52%   |
| IMC Networks Bluetooth Device                                                       | 2         | 0.52%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 0.52%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 2         | 0.52%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 2         | 0.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 374       | 66.79%  |
| AMD                    | 72        | 12.86%  |
| Nvidia                 | 71        | 12.68%  |
| Realtek Semiconductor  | 7         | 1.25%   |
| GN Netcom              | 4         | 0.71%   |
| Logitech               | 3         | 0.54%   |
| Texas Instruments      | 2         | 0.36%   |
| Plantronics            | 2         | 0.36%   |
| Lenovo                 | 2         | 0.36%   |
| Kingston Technology    | 2         | 0.36%   |
| JMTek                  | 2         | 0.36%   |
| DSEA A/S               | 2         | 0.36%   |
| C-Media Electronics    | 2         | 0.36%   |
| Apple                  | 2         | 0.36%   |
| XMOS                   | 1         | 0.18%   |
| Samson Technologies    | 1         | 0.18%   |
| Razer USA              | 1         | 0.18%   |
| No brand               | 1         | 0.18%   |
| LINE TECH INDUSTRIAL   | 1         | 0.18%   |
| Hewlett-Packard        | 1         | 0.18%   |
| GYROCOM C&C            | 1         | 0.18%   |
| Generalplus Technology | 1         | 0.18%   |
| Conexant Systems       | 1         | 0.18%   |
| CMX Systems            | 1         | 0.18%   |
| Cambridge Audio        | 1         | 0.18%   |
| Arturia                | 1         | 0.18%   |
| AKAI Professional M.I. | 1         | 0.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 61        | 9.28%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 45        | 6.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 33        | 5.02%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 29        | 4.41%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 28        | 4.26%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 26        | 3.96%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 23        | 3.5%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 21        | 3.2%    |
| Intel Broadwell-U Audio Controller                                                                | 16        | 2.44%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 16        | 2.44%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 15        | 2.28%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 15        | 2.28%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 15        | 2.28%   |
| Intel Cannon Lake PCH cAVS                                                                        | 15        | 2.28%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 15        | 2.28%   |
| Intel 8 Series HD Audio Controller                                                                | 15        | 2.28%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12        | 1.83%   |
| Intel Comet Lake PCH cAVS                                                                         | 11        | 1.67%   |
| Intel CM238 HD Audio Controller                                                                   | 11        | 1.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 11        | 1.67%   |
| AMD FCH Azalia Controller                                                                         | 11        | 1.67%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 10        | 1.52%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 10        | 1.52%   |
| Realtek Semiconductor USB Audio                                                                   | 7         | 1.07%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 7         | 1.07%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 7         | 1.07%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 1.07%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 1.07%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 6         | 0.91%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 6         | 0.91%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 6         | 0.91%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 0.91%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 0.91%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 0.76%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 0.61%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 0.61%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 4         | 0.61%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 4         | 0.61%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.46%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 107       | 34.19%  |
| SK hynix            | 71        | 22.68%  |
| Micron Technology   | 35        | 11.18%  |
| Kingston            | 24        | 7.67%   |
| Unknown             | 14        | 4.47%   |
| Ramaxel Technology  | 12        | 3.83%   |
| Crucial             | 12        | 3.83%   |
| Unknown (ABCD)      | 6         | 1.92%   |
| Elpida              | 4         | 1.28%   |
| A-DATA Technology   | 4         | 1.28%   |
| Corsair             | 3         | 0.96%   |
| Teikon              | 2         | 0.64%   |
| Smart               | 2         | 0.64%   |
| Unknown             | 2         | 0.64%   |
| Smart Brazil        | 1         | 0.32%   |
| PNY                 | 1         | 0.32%   |
| Patriot             | 1         | 0.32%   |
| Nanya Technology    | 1         | 0.32%   |
| Magnum Tech         | 1         | 0.32%   |
| Lexar               | 1         | 0.32%   |
| Kingmax             | 1         | 0.32%   |
| Goldkey             | 1         | 0.32%   |
| ff                  | 1         | 0.32%   |
| fef5                | 1         | 0.32%   |
| Cors                | 1         | 0.32%   |
| ChangXin Memory     | 1         | 0.32%   |
| ASint Technology    | 1         | 0.32%   |
| 8945000080AD        | 1         | 0.32%   |
| 4ea5                | 1         | 0.32%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 10        | 3.01%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 6         | 1.81%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 6         | 1.81%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 1.81%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 1.81%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 1.81%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 1.81%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.2%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 4         | 1.2%    |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 4         | 1.2%    |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 4         | 1.2%    |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 4         | 1.2%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 4         | 1.2%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.9%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 3         | 0.9%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.9%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 0.9%    |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 3         | 0.9%    |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 3         | 0.9%    |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 3         | 0.9%    |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 3         | 0.9%    |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s           | 3         | 0.9%    |
| Unknown RAM Module 4096MB SODIMM DDR2 667MT/s                    | 2         | 0.6%    |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 0.6%    |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 0.6%    |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 0.6%    |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 2         | 0.6%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.6%    |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.6%    |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 2         | 0.6%    |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.6%    |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 0.6%    |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 2         | 0.6%    |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                      | 2         | 0.6%    |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s         | 2         | 0.6%    |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 0.6%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.6%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.6%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.6%    |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.6%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 139       | 52.26%  |
| DDR3    | 79        | 29.7%   |
| LPDDR4  | 20        | 7.52%   |
| LPDDR3  | 12        | 4.51%   |
| DDR2    | 5         | 1.88%   |
| SDRAM   | 4         | 1.5%    |
| Unknown | 3         | 1.13%   |
| DDR5    | 2         | 0.75%   |
| LPDDR5  | 1         | 0.38%   |
| DDR     | 1         | 0.38%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 231       | 87.5%   |
| Row Of Chips | 27        | 10.23%  |
| Unknown      | 4         | 1.52%   |
| Chip         | 2         | 0.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 104       | 36.75%  |
| 4096  | 83        | 29.33%  |
| 16384 | 46        | 16.25%  |
| 2048  | 25        | 8.83%   |
| 32768 | 19        | 6.71%   |
| 1024  | 6         | 2.12%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 71        | 24.15%  |
| 1600    | 58        | 19.73%  |
| 3200    | 49        | 16.67%  |
| 2400    | 25        | 8.5%    |
| 2133    | 22        | 7.48%   |
| 1333    | 12        | 4.08%   |
| 1334    | 11        | 3.74%   |
| 3266    | 6         | 2.04%   |
| Unknown | 6         | 2.04%   |
| 4267    | 5         | 1.7%    |
| 1067    | 5         | 1.7%    |
| 4199    | 4         | 1.36%   |
| 1867    | 4         | 1.36%   |
| 8400    | 3         | 1.02%   |
| 4266    | 3         | 1.02%   |
| 667     | 3         | 1.02%   |
| 4800    | 2         | 0.68%   |
| 3733    | 2         | 0.68%   |
| 6400    | 1         | 0.34%   |
| 1066    | 1         | 0.34%   |
| 533     | 1         | 0.34%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 40%     |
| Samsung Electronics | 1         | 20%     |
| Canon               | 1         | 20%     |
| Brother Industries  | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Notebooks | Percent |
|------------------------|-----------|---------|
| Samsung M2020 Series   | 1         | 20%     |
| HP LaserJet 1320       | 1         | 20%     |
| HP DeskJet 2130 series | 1         | 20%     |
| Canon LiDE 400         | 1         | 20%     |
| Brother MFC-1810       | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 112       | 27.65%  |
| IMC Networks                           | 40        | 9.88%   |
| Sunplus Innovation Technology          | 33        | 8.15%   |
| Realtek Semiconductor                  | 31        | 7.65%   |
| Microdia                               | 29        | 7.16%   |
| Bison Electronics                      | 29        | 7.16%   |
| Quanta                                 | 17        | 4.2%    |
| Cheng Uei Precision Industry (Foxlink) | 15        | 3.7%    |
| Apple                                  | 13        | 3.21%   |
| Syntek                                 | 12        | 2.96%   |
| Suyin                                  | 12        | 2.96%   |
| Acer                                   | 8         | 1.98%   |
| Silicon Motion                         | 7         | 1.73%   |
| Luxvisions Innotech Limited            | 6         | 1.48%   |
| Lite-On Technology                     | 5         | 1.23%   |
| Samsung Electronics                    | 4         | 0.99%   |
| Logitech                               | 4         | 0.99%   |
| Alcor Micro                            | 4         | 0.99%   |
| Ricoh                                  | 3         | 0.74%   |
| Z-Star Microelectronics                | 2         | 0.49%   |
| Importek                               | 2         | 0.49%   |
| ALi                                    | 2         | 0.49%   |
| Unknown                                | 2         | 0.49%   |
| Y Media                                | 1         | 0.25%   |
| Sonix Technology                       | 1         | 0.25%   |
| ShineTech                              | 1         | 0.25%   |
| Qtech                                  | 1         | 0.25%   |
| Primax Electronics                     | 1         | 0.25%   |
| Polycom                                | 1         | 0.25%   |
| Pixart Imaging                         | 1         | 0.25%   |
| Nokia Mobile Phones                    | 1         | 0.25%   |
| LG Electronics                         | 1         | 0.25%   |
| icSpring                               | 1         | 0.25%   |
| Generalplus Technology                 | 1         | 0.25%   |
| Denron                                 | 1         | 0.25%   |
| Creative Technology                    | 1         | 0.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony USB2.0 Camera                                                      | 18        | 4.44%   |
| Chicony HD Webcam                                                          | 16        | 3.95%   |
| Microdia Integrated_Webcam_HD                                              | 14        | 3.46%   |
| Chicony Integrated Camera                                                  | 14        | 3.46%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 13        | 3.21%   |
| IMC Networks Integrated Camera                                             | 11        | 2.72%   |
| Realtek Integrated_Webcam_HD                                               | 9         | 2.22%   |
| Chicony HP HD Camera                                                       | 9         | 2.22%   |
| Chicony Integrated IR Camera                                               | 7         | 1.73%   |
| Bison BisonCam,NB Pro                                                      | 7         | 1.73%   |
| Syntek Integrated Camera                                                   | 6         | 1.48%   |
| Bison HD Webcam                                                            | 6         | 1.48%   |
| Apple FaceTime HD Camera                                                   | 6         | 1.48%   |
| Sunplus Integrated_Webcam_HD                                               | 5         | 1.23%   |
| Sunplus HD WebCam                                                          | 5         | 1.23%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 4         | 0.99%   |
| IMC Networks VGA UVC WebCam                                                | 4         | 0.99%   |
| Chicony EasyCamera                                                         | 4         | 0.99%   |
| Bison SunplusIT Integrated Camera                                          | 4         | 0.99%   |
| Bison Integrated Camera                                                    | 4         | 0.99%   |
| Bison EasyCamera                                                           | 4         | 0.99%   |
| Acer Integrated Camera                                                     | 4         | 0.99%   |
| Suyin HP Truevision HD                                                     | 3         | 0.74%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 3         | 0.74%   |
| Sunplus Asus Webcam                                                        | 3         | 0.74%   |
| Realtek USB2.0 HD UVC WebCam                                               | 3         | 0.74%   |
| Realtek Lenovo EasyCamera                                                  | 3         | 0.74%   |
| Realtek Integrated Webcam                                                  | 3         | 0.74%   |
| Realtek HD WebCam                                                          | 3         | 0.74%   |
| Quanta USB2.0 HD UVC WebCam                                                | 3         | 0.74%   |
| Quanta HD User Facing                                                      | 3         | 0.74%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 3         | 0.74%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 3         | 0.74%   |
| Chicony Integrated Camera [ThinkPad]                                       | 3         | 0.74%   |
| Chicony Integrated Camera (1280x720@30)                                    | 3         | 0.74%   |
| Chicony HP Truevision HD                                                   | 3         | 0.74%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 3         | 0.74%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 3         | 0.74%   |
| Bison BisonCam, NB Pro                                                     | 3         | 0.74%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 3         | 0.74%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 34        | 34%     |
| Synaptics                  | 34        | 34%     |
| Shenzhen Goodix Technology | 16        | 16%     |
| LighTuning Technology      | 8         | 8%      |
| Elan Microelectronics      | 4         | 4%      |
| AuthenTec                  | 4         | 4%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 12        | 12%     |
| Shenzhen Goodix  Fingerprint Device                                        | 11        | 11%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 8%      |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 5%      |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 4%      |
| Synaptics WBDI Device                                                      | 4         | 4%      |
| Synaptics TouchPad                                                         | 4         | 4%      |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 4%      |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 4         | 4%      |
| Elan ELAN:Fingerprint                                                      | 4         | 4%      |
| Unknown                                                                    | 4         | 4%      |
| Validity Sensors Fingerprint scanner                                       | 3         | 3%      |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 3%      |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 3%      |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 2%      |
| Validity Sensors VFS491                                                    | 2         | 2%      |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 2%      |
| Synaptics UWP WBDI Device                                                  | 2         | 2%      |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 2%      |
| Shenzhen Goodix FingerPrint                                                | 2         | 2%      |
| AuthenTec AES1600                                                          | 2         | 2%      |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 1%      |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 1%      |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1%      |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 1%      |
| Validity Sensors Synaptics WBDI                                            | 1         | 1%      |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1%      |
| Synaptics  WBDI                                                            | 1         | 1%      |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1%      |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 1%      |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 1%      |
| LighTuning Fingerprint Reader                                              | 1         | 1%      |
| AuthenTec AES2810                                                          | 1         | 1%      |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 16        | 51.61%  |
| Alcor Micro           | 7         | 22.58%  |
| Upek                  | 5         | 16.13%  |
| Lenovo                | 2         | 6.45%   |
| Gemalto (was Gemplus) | 1         | 3.23%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 22.58%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 22.58%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 16.13%  |
| Broadcom 5880                                                                | 5         | 16.13%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 6.45%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 6.45%   |
| Broadcom 58200                                                               | 2         | 6.45%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 3.23%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 249       | 54.85%  |
| 1     | 163       | 35.9%   |
| 2     | 34        | 7.49%   |
| 3     | 5         | 1.1%    |
| 7     | 1         | 0.22%   |
| 5     | 1         | 0.22%   |
| 4     | 1         | 0.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 99        | 40.74%  |
| Graphics card            | 37        | 15.23%  |
| Chipcard                 | 30        | 12.35%  |
| Net/wireless             | 19        | 7.82%   |
| Communication controller | 18        | 7.41%   |
| Camera                   | 10        | 4.12%   |
| Multimedia controller    | 9         | 3.7%    |
| Bluetooth                | 6         | 2.47%   |
| Storage                  | 5         | 2.06%   |
| Card reader              | 5         | 2.06%   |
| Sound                    | 4         | 1.65%   |
| Net/ethernet             | 1         | 0.41%   |


Linux in Bangladesh - Tested Hardware & Statistics
--------------------------------------------------

A project to collect tested hardware configurations for Linux in Bangladesh.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Bangladesh/Desktop/README.md) and [notebooks](/Location/Bangladesh/Notebook/README.md).

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

Total: 458

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | B150M-D3V-CF                | Desktop     | [75b228c5fb](https://linux-hardware.org/?probe=75b228c5fb) | Sep 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [128658b9f0](https://linux-hardware.org/?probe=128658b9f0) | Sep 26, 2023 |
| MSI           | PRO H410M-B                 | Desktop     | [dd6815e149](https://linux-hardware.org/?probe=dd6815e149) | Sep 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [c63ae3378d](https://linux-hardware.org/?probe=c63ae3378d) | Sep 22, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [0f189d3c2a](https://linux-hardware.org/?probe=0f189d3c2a) | Sep 21, 2023 |
| Acer          | TravelMate P246-MG          | Notebook    | [197b2c18c7](https://linux-hardware.org/?probe=197b2c18c7) | Sep 21, 2023 |
| Gigabyte      | B250M-HD3-CF                | Desktop     | [f7280def0d](https://linux-hardware.org/?probe=f7280def0d) | Sep 20, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [1e8bb82a4a](https://linux-hardware.org/?probe=1e8bb82a4a) | Sep 16, 2023 |
| Gigabyte      | B250M-HD3-CF                | Desktop     | [8bc40fd9f1](https://linux-hardware.org/?probe=8bc40fd9f1) | Sep 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [699fb7e97e](https://linux-hardware.org/?probe=699fb7e97e) | Sep 07, 2023 |
| ASUSTek       | X580VD                      | Notebook    | [989134a7c5](https://linux-hardware.org/?probe=989134a7c5) | Sep 06, 2023 |
| Gigabyte      | Z690 AORUS ELITE DDR4       | Desktop     | [7e7d27d9f2](https://linux-hardware.org/?probe=7e7d27d9f2) | Sep 03, 2023 |
| win elemen... | MoreFine S500+              | Notebook    | [9675488adc](https://linux-hardware.org/?probe=9675488adc) | Aug 28, 2023 |
| win elemen... | MoreFine S500+              | Notebook    | [29e062fb36](https://linux-hardware.org/?probe=29e062fb36) | Aug 27, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [9c34344e6d](https://linux-hardware.org/?probe=9c34344e6d) | Aug 26, 2023 |
| Biostar       | H410MH                      | Desktop     | [abe98ae584](https://linux-hardware.org/?probe=abe98ae584) | Aug 15, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [2ec62f31c9](https://linux-hardware.org/?probe=2ec62f31c9) | Aug 12, 2023 |
| Gigabyte      | H510M S2H                   | Desktop     | [72eb04ca17](https://linux-hardware.org/?probe=72eb04ca17) | Aug 08, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [a4a6f81455](https://linux-hardware.org/?probe=a4a6f81455) | Aug 05, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [ef010c9d51](https://linux-hardware.org/?probe=ef010c9d51) | Aug 05, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [8aad3290a7](https://linux-hardware.org/?probe=8aad3290a7) | Aug 03, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [3f15239dd2](https://linux-hardware.org/?probe=3f15239dd2) | Jul 16, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [23793e7d9c](https://linux-hardware.org/?probe=23793e7d9c) | Jul 14, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [8974860f56](https://linux-hardware.org/?probe=8974860f56) | Jul 12, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [cc4f862316](https://linux-hardware.org/?probe=cc4f862316) | Jul 11, 2023 |
| HP            | Notebook                    | Notebook    | [9487146a2f](https://linux-hardware.org/?probe=9487146a2f) | Jun 09, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [c64ff76dba](https://linux-hardware.org/?probe=c64ff76dba) | Jun 09, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [a34c3550be](https://linux-hardware.org/?probe=a34c3550be) | Jun 06, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [4808ee44b5](https://linux-hardware.org/?probe=4808ee44b5) | Jun 04, 2023 |
| ASRock        | H470M-HDV                   | Desktop     | [abf4b3f5d2](https://linux-hardware.org/?probe=abf4b3f5d2) | Jun 02, 2023 |
| ASRock        | H470M-HDV                   | Desktop     | [4092d4fe1b](https://linux-hardware.org/?probe=4092d4fe1b) | Jun 02, 2023 |
| ASRock        | H470M-HDV                   | Desktop     | [f73c3032af](https://linux-hardware.org/?probe=f73c3032af) | May 30, 2023 |
| ASRock        | H470M-HDV                   | Desktop     | [12fe930fb2](https://linux-hardware.org/?probe=12fe930fb2) | May 30, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [f8ec1083ad](https://linux-hardware.org/?probe=f8ec1083ad) | May 26, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [eb636c0b30](https://linux-hardware.org/?probe=eb636c0b30) | May 26, 2023 |
| HP            | ProBook 4540s               | Notebook    | [2a2712560e](https://linux-hardware.org/?probe=2a2712560e) | May 17, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [38482c1a10](https://linux-hardware.org/?probe=38482c1a10) | May 15, 2023 |
| Lenovo        | S20-30 20421                | Notebook    | [cc4f992884](https://linux-hardware.org/?probe=cc4f992884) | May 12, 2023 |
| ASRock        | H470M-HDV                   | Desktop     | [36257aa0a2](https://linux-hardware.org/?probe=36257aa0a2) | May 11, 2023 |
| ASUSTek       | X556UQK                     | Notebook    | [12d23bdebb](https://linux-hardware.org/?probe=12d23bdebb) | May 11, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [6fc095ce39](https://linux-hardware.org/?probe=6fc095ce39) | May 04, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [b97932d8f1](https://linux-hardware.org/?probe=b97932d8f1) | May 03, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [c4841e9b59](https://linux-hardware.org/?probe=c4841e9b59) | May 02, 2023 |
| HP            | ProBook 450 G7              | Notebook    | [a1c1008bf1](https://linux-hardware.org/?probe=a1c1008bf1) | Apr 29, 2023 |
| Dell          | Inspiron 15 3520            | Notebook    | [f767bfff00](https://linux-hardware.org/?probe=f767bfff00) | Apr 29, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [ce4700304c](https://linux-hardware.org/?probe=ce4700304c) | Apr 26, 2023 |
| Lenovo        | S20-30 20421                | Notebook    | [b9846b05e7](https://linux-hardware.org/?probe=b9846b05e7) | Apr 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [c27abc2880](https://linux-hardware.org/?probe=c27abc2880) | Apr 17, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [802d7b7c3f](https://linux-hardware.org/?probe=802d7b7c3f) | Apr 07, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [874157891b](https://linux-hardware.org/?probe=874157891b) | Apr 06, 2023 |
| Lenovo        | ThinkPad X220 4290CTO       | Notebook    | [5dd9277838](https://linux-hardware.org/?probe=5dd9277838) | Apr 04, 2023 |
| Lenovo        | ThinkPad T470s 20HGS23V0... | Notebook    | [6af08c4bfe](https://linux-hardware.org/?probe=6af08c4bfe) | Mar 30, 2023 |
| Lenovo        | ThinkPad T470s 20HGS23V0... | Notebook    | [6f0d3fd82b](https://linux-hardware.org/?probe=6f0d3fd82b) | Mar 30, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [b860e76ead](https://linux-hardware.org/?probe=b860e76ead) | Mar 26, 2023 |
| MSI           | Modern 14 B10MW             | Notebook    | [2940ea3b40](https://linux-hardware.org/?probe=2940ea3b40) | Mar 21, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [ec2390af74](https://linux-hardware.org/?probe=ec2390af74) | Mar 21, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [e3e0efa236](https://linux-hardware.org/?probe=e3e0efa236) | Mar 20, 2023 |
| Lenovo        | LEGION5PRO-16ACH6H 82JQ     | Notebook    | [4f3cbedf85](https://linux-hardware.org/?probe=4f3cbedf85) | Mar 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [a0cf486df2](https://linux-hardware.org/?probe=a0cf486df2) | Mar 19, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [7d708fea96](https://linux-hardware.org/?probe=7d708fea96) | Mar 06, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [418b5dd7ff](https://linux-hardware.org/?probe=418b5dd7ff) | Feb 27, 2023 |
| Dell          | Inspiron N4010              | Notebook    | [612418b6e7](https://linux-hardware.org/?probe=612418b6e7) | Feb 25, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [47db699ed6](https://linux-hardware.org/?probe=47db699ed6) | Feb 18, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [c1e5226b6e](https://linux-hardware.org/?probe=c1e5226b6e) | Feb 18, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [6cda8724a4](https://linux-hardware.org/?probe=6cda8724a4) | Feb 14, 2023 |
| Toshiba       | Satellite Pro L510          | Notebook    | [c8dc3a76e5](https://linux-hardware.org/?probe=c8dc3a76e5) | Feb 06, 2023 |
| Acer          | Aspire 4736Z                | Notebook    | [a2ab102eeb](https://linux-hardware.org/?probe=a2ab102eeb) | Feb 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [ddb7f53b34](https://linux-hardware.org/?probe=ddb7f53b34) | Feb 03, 2023 |
| Lenovo        | ThinkPad X230 2324A82       | Notebook    | [2793159580](https://linux-hardware.org/?probe=2793159580) | Feb 03, 2023 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [63143e2bf5](https://linux-hardware.org/?probe=63143e2bf5) | Feb 01, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [d6d4c6c38c](https://linux-hardware.org/?probe=d6d4c6c38c) | Jan 31, 2023 |
| Gigabyte      | B250M-HD3-CF                | Desktop     | [f8630776ca](https://linux-hardware.org/?probe=f8630776ca) | Jan 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [af63cfc79a](https://linux-hardware.org/?probe=af63cfc79a) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [f0d73c960e](https://linux-hardware.org/?probe=f0d73c960e) | Jan 25, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [cf6bdca9c4](https://linux-hardware.org/?probe=cf6bdca9c4) | Jan 23, 2023 |
| Dell          | Vostro 1014                 | Notebook    | [f7ff3312f2](https://linux-hardware.org/?probe=f7ff3312f2) | Jan 21, 2023 |
| Dell          | Vostro 1014                 | Notebook    | [724939f0cf](https://linux-hardware.org/?probe=724939f0cf) | Jan 21, 2023 |
| MSI           | Modern 14 B10MW             | Notebook    | [c3f150a8f4](https://linux-hardware.org/?probe=c3f150a8f4) | Jan 18, 2023 |
| MSI           | Modern 14 B10MW             | Notebook    | [d2ac110bfb](https://linux-hardware.org/?probe=d2ac110bfb) | Jan 18, 2023 |
| MSI           | Modern 14 B10MW             | Notebook    | [ad5c9e7f6a](https://linux-hardware.org/?probe=ad5c9e7f6a) | Jan 18, 2023 |
| HP            | Notebook                    | Notebook    | [fbdf174a63](https://linux-hardware.org/?probe=fbdf174a63) | Jan 16, 2023 |
| Dell          | Latitude 5300               | Notebook    | [8149377926](https://linux-hardware.org/?probe=8149377926) | Jan 15, 2023 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [bddd00febc](https://linux-hardware.org/?probe=bddd00febc) | Jan 15, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [e5773ce5f8](https://linux-hardware.org/?probe=e5773ce5f8) | Jan 11, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [53043b7d75](https://linux-hardware.org/?probe=53043b7d75) | Jan 10, 2023 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | Desktop     | [3566221932](https://linux-hardware.org/?probe=3566221932) | Jan 06, 2023 |
| ASUSTek       | P453UA                      | Notebook    | [0bf89f0f8f](https://linux-hardware.org/?probe=0bf89f0f8f) | Dec 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [3a505870ba](https://linux-hardware.org/?probe=3a505870ba) | Dec 22, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [7c8e3bbb6a](https://linux-hardware.org/?probe=7c8e3bbb6a) | Dec 21, 2022 |
| HP            | 15                          | Notebook    | [cce5eb4078](https://linux-hardware.org/?probe=cce5eb4078) | Dec 19, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [4b44d6e506](https://linux-hardware.org/?probe=4b44d6e506) | Dec 12, 2022 |
| Foxconn       | H55MXV-LE                   | Desktop     | [931837aeec](https://linux-hardware.org/?probe=931837aeec) | Dec 12, 2022 |
| Acer          | Aspire E5-471               | Notebook    | [3e9c2f0201](https://linux-hardware.org/?probe=3e9c2f0201) | Dec 02, 2022 |
| HP            | ProBook 450 G7 HP NOTEBO... | Notebook    | [2fe5c76c3c](https://linux-hardware.org/?probe=2fe5c76c3c) | Dec 02, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [da83c13da3](https://linux-hardware.org/?probe=da83c13da3) | Nov 30, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [459c2ba743](https://linux-hardware.org/?probe=459c2ba743) | Nov 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [9836f71cb7](https://linux-hardware.org/?probe=9836f71cb7) | Nov 24, 2022 |
| Lenovo        | G40-70 20369                | Notebook    | [aafdfb20ff](https://linux-hardware.org/?probe=aafdfb20ff) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [9b9a13f34f](https://linux-hardware.org/?probe=9b9a13f34f) | Nov 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [4efc557c1b](https://linux-hardware.org/?probe=4efc557c1b) | Nov 24, 2022 |
| HP            | 15                          | Notebook    | [ab7c1e3bfd](https://linux-hardware.org/?probe=ab7c1e3bfd) | Nov 21, 2022 |
| Dell          | G7 7700                     | Notebook    | [2440bebe2c](https://linux-hardware.org/?probe=2440bebe2c) | Nov 15, 2022 |
| Acer          | TravelMate P214-53          | Notebook    | [2c342fa72f](https://linux-hardware.org/?probe=2c342fa72f) | Nov 14, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [b5080a1102](https://linux-hardware.org/?probe=b5080a1102) | Nov 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [104fb805bd](https://linux-hardware.org/?probe=104fb805bd) | Nov 09, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [1918990398](https://linux-hardware.org/?probe=1918990398) | Nov 07, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [a26a719002](https://linux-hardware.org/?probe=a26a719002) | Nov 05, 2022 |
| Dell          | Latitude E7240              | Notebook    | [2548bcefe0](https://linux-hardware.org/?probe=2548bcefe0) | Nov 04, 2022 |
| HP            | Compaq 8000 Elite CMT PC    | Desktop     | [fbe835b8ef](https://linux-hardware.org/?probe=fbe835b8ef) | Oct 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [e1a32857ba](https://linux-hardware.org/?probe=e1a32857ba) | Oct 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [9357d641ef](https://linux-hardware.org/?probe=9357d641ef) | Oct 18, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [068a780cce](https://linux-hardware.org/?probe=068a780cce) | Oct 17, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [d4c5e9f853](https://linux-hardware.org/?probe=d4c5e9f853) | Oct 16, 2022 |
| HP            | Compaq 8000 Elite CMT PC    | Desktop     | [5dd9f2cda4](https://linux-hardware.org/?probe=5dd9f2cda4) | Oct 09, 2022 |
| Fujitsu       | LIFEBOOK LH531              | Notebook    | [21a68d8c0e](https://linux-hardware.org/?probe=21a68d8c0e) | Oct 08, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [ee4c1a5f66](https://linux-hardware.org/?probe=ee4c1a5f66) | Oct 03, 2022 |
| Biostar       | G41D3C                      | Desktop     | [97ee103719](https://linux-hardware.org/?probe=97ee103719) | Sep 30, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [8f28254d53](https://linux-hardware.org/?probe=8f28254d53) | Sep 20, 2022 |
| Dell          | Inspiron 14-3467            | Notebook    | [e92b56817a](https://linux-hardware.org/?probe=e92b56817a) | Sep 14, 2022 |
| Biostar       | G41D3C                      | Desktop     | [280212d494](https://linux-hardware.org/?probe=280212d494) | Sep 13, 2022 |
| Biostar       | G41D3C                      | Desktop     | [6d15a54350](https://linux-hardware.org/?probe=6d15a54350) | Sep 13, 2022 |
| Biostar       | G41D3C                      | Desktop     | [09d42cd406](https://linux-hardware.org/?probe=09d42cd406) | Sep 13, 2022 |
| Biostar       | G41D3C                      | Desktop     | [c45809d681](https://linux-hardware.org/?probe=c45809d681) | Sep 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [4fbc7a765f](https://linux-hardware.org/?probe=4fbc7a765f) | Sep 12, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [aa1cd85ea9](https://linux-hardware.org/?probe=aa1cd85ea9) | Sep 09, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d4e798ff22](https://linux-hardware.org/?probe=d4e798ff22) | Sep 07, 2022 |
| Toshiba       | Satellite L645              | Notebook    | [642a6f7602](https://linux-hardware.org/?probe=642a6f7602) | Sep 03, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [5ad5d3809b](https://linux-hardware.org/?probe=5ad5d3809b) | Sep 01, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1d04855f84](https://linux-hardware.org/?probe=1d04855f84) | Aug 29, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [7439a7400d](https://linux-hardware.org/?probe=7439a7400d) | Aug 27, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [262ff7d08a](https://linux-hardware.org/?probe=262ff7d08a) | Aug 27, 2022 |
| HP            | Pavilion x360 m3 Convert... | Convertible | [bde621edc4](https://linux-hardware.org/?probe=bde621edc4) | Aug 17, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [e04617befa](https://linux-hardware.org/?probe=e04617befa) | Aug 17, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [db7b7b3126](https://linux-hardware.org/?probe=db7b7b3126) | Aug 15, 2022 |
| ASUSTek       | GL552VW                     | Notebook    | [ae85f68d58](https://linux-hardware.org/?probe=ae85f68d58) | Aug 15, 2022 |
| Acer          | Aspire M5-581T              | Notebook    | [7efdb0e467](https://linux-hardware.org/?probe=7efdb0e467) | Aug 14, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [97f75c2be0](https://linux-hardware.org/?probe=97f75c2be0) | Aug 13, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [534c1142c2](https://linux-hardware.org/?probe=534c1142c2) | Aug 10, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [0724d34f68](https://linux-hardware.org/?probe=0724d34f68) | Aug 10, 2022 |
| Acer          | TravelMate P214-53          | Notebook    | [41f0d0b264](https://linux-hardware.org/?probe=41f0d0b264) | Aug 02, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [c6643cb779](https://linux-hardware.org/?probe=c6643cb779) | Jul 28, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [2dc0ffa0d1](https://linux-hardware.org/?probe=2dc0ffa0d1) | Jul 26, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [4e33f5e902](https://linux-hardware.org/?probe=4e33f5e902) | Jul 19, 2022 |
| HP            | 14                          | Notebook    | [816a62dde0](https://linux-hardware.org/?probe=816a62dde0) | Jul 07, 2022 |
| Timi          | Mi NoteBook Pro             | Notebook    | [046a18dc14](https://linux-hardware.org/?probe=046a18dc14) | Jul 03, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [9a35c1249b](https://linux-hardware.org/?probe=9a35c1249b) | Jun 30, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [c8f0217b26](https://linux-hardware.org/?probe=c8f0217b26) | Jun 29, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [d3af5b938a](https://linux-hardware.org/?probe=d3af5b938a) | Jun 29, 2022 |
| Gigabyte      | B360M HD3                   | Desktop     | [b35e9f3e5c](https://linux-hardware.org/?probe=b35e9f3e5c) | Jun 28, 2022 |
| ASUSTek       | X507UB                      | Notebook    | [0ba0fc4089](https://linux-hardware.org/?probe=0ba0fc4089) | Jun 28, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [4b202c1285](https://linux-hardware.org/?probe=4b202c1285) | Jun 22, 2022 |
| MSI           | H61M-P31/W8                 | Desktop     | [7b8cc6556b](https://linux-hardware.org/?probe=7b8cc6556b) | Jun 12, 2022 |
| Acer          | Aspire E5-573               | Notebook    | [dce8b618f8](https://linux-hardware.org/?probe=dce8b618f8) | May 22, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [758bdaefe9](https://linux-hardware.org/?probe=758bdaefe9) | May 21, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [99283be07b](https://linux-hardware.org/?probe=99283be07b) | May 20, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [b85af00b16](https://linux-hardware.org/?probe=b85af00b16) | May 18, 2022 |
| Dell          | Latitude 5580               | Notebook    | [18cefe0718](https://linux-hardware.org/?probe=18cefe0718) | May 17, 2022 |
| Dell          | Inspiron 5505               | Notebook    | [c1353ba170](https://linux-hardware.org/?probe=c1353ba170) | May 15, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [f09183023d](https://linux-hardware.org/?probe=f09183023d) | May 10, 2022 |
| HP            | Elite x2 1012 G2            | Tablet      | [71e0ef1fc9](https://linux-hardware.org/?probe=71e0ef1fc9) | May 07, 2022 |
| HP            | 240 G3                      | Notebook    | [7062083e69](https://linux-hardware.org/?probe=7062083e69) | May 06, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3055b0e95f](https://linux-hardware.org/?probe=3055b0e95f) | May 05, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [88f6586c4b](https://linux-hardware.org/?probe=88f6586c4b) | May 02, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [ab11d6ac2f](https://linux-hardware.org/?probe=ab11d6ac2f) | Apr 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [c6577346b8](https://linux-hardware.org/?probe=c6577346b8) | Apr 11, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [6e993bc145](https://linux-hardware.org/?probe=6e993bc145) | Apr 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [73abf1d6fd](https://linux-hardware.org/?probe=73abf1d6fd) | Apr 08, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [19623aa8b6](https://linux-hardware.org/?probe=19623aa8b6) | Apr 07, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [287aa3ba8e](https://linux-hardware.org/?probe=287aa3ba8e) | Apr 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [14a3433a91](https://linux-hardware.org/?probe=14a3433a91) | Apr 03, 2022 |
| HP            | ZHAN 66 Pro A 14 G4 Note... | Notebook    | [8199781e64](https://linux-hardware.org/?probe=8199781e64) | Mar 28, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [33d1544ea1](https://linux-hardware.org/?probe=33d1544ea1) | Mar 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [52ce856be5](https://linux-hardware.org/?probe=52ce856be5) | Mar 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [1dd07eeee0](https://linux-hardware.org/?probe=1dd07eeee0) | Mar 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [321d0c1b4a](https://linux-hardware.org/?probe=321d0c1b4a) | Mar 23, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [5db5bac582](https://linux-hardware.org/?probe=5db5bac582) | Mar 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [cb949f34eb](https://linux-hardware.org/?probe=cb949f34eb) | Mar 20, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [da23c76a90](https://linux-hardware.org/?probe=da23c76a90) | Mar 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [fd9e66788c](https://linux-hardware.org/?probe=fd9e66788c) | Mar 17, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [e141c99bf2](https://linux-hardware.org/?probe=e141c99bf2) | Mar 09, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [87d97b3c00](https://linux-hardware.org/?probe=87d97b3c00) | Mar 05, 2022 |
| MSI           | FM2-A55M-E33                | Desktop     | [d7a873bf3d](https://linux-hardware.org/?probe=d7a873bf3d) | Feb 27, 2022 |
| Acer          | TravelMate P214-53          | Notebook    | [87f30f494f](https://linux-hardware.org/?probe=87f30f494f) | Feb 19, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [62c028a881](https://linux-hardware.org/?probe=62c028a881) | Feb 16, 2022 |
| Biostar       | H55 HD                      | Desktop     | [b0d5843b6e](https://linux-hardware.org/?probe=b0d5843b6e) | Feb 13, 2022 |
| HP            | Compaq 8000 Elite CMT PC    | Desktop     | [42647bc4b3](https://linux-hardware.org/?probe=42647bc4b3) | Feb 12, 2022 |
| HP            | 339A                        | Desktop     | [6f8e63bfb0](https://linux-hardware.org/?probe=6f8e63bfb0) | Feb 11, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [0c13bfa27b](https://linux-hardware.org/?probe=0c13bfa27b) | Feb 10, 2022 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [8e73dc39ab](https://linux-hardware.org/?probe=8e73dc39ab) | Feb 09, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [42e37d6172](https://linux-hardware.org/?probe=42e37d6172) | Feb 07, 2022 |
| Biostar       | H55 HD                      | Desktop     | [e08da3e685](https://linux-hardware.org/?probe=e08da3e685) | Feb 03, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [47c47a0121](https://linux-hardware.org/?probe=47c47a0121) | Feb 02, 2022 |
| HP            | ProBook 440 G6              | Notebook    | [d7431ab69e](https://linux-hardware.org/?probe=d7431ab69e) | Jan 31, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [76d17811e3](https://linux-hardware.org/?probe=76d17811e3) | Jan 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [caca9680a9](https://linux-hardware.org/?probe=caca9680a9) | Jan 25, 2022 |
| Lenovo        | ThinkPad X230 2324A82       | Notebook    | [be92c29259](https://linux-hardware.org/?probe=be92c29259) | Jan 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1e89749691](https://linux-hardware.org/?probe=1e89749691) | Jan 22, 2022 |
| MSI           | FM2-A55M-E33                | Desktop     | [ac35b74090](https://linux-hardware.org/?probe=ac35b74090) | Jan 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | Notebook    | [88f62c8333](https://linux-hardware.org/?probe=88f62c8333) | Jan 15, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [38a7870ece](https://linux-hardware.org/?probe=38a7870ece) | Jan 13, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [2fb0411785](https://linux-hardware.org/?probe=2fb0411785) | Jan 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [0d69dca8f3](https://linux-hardware.org/?probe=0d69dca8f3) | Jan 04, 2022 |
| Gigabyte      | H81M-S                      | Desktop     | [692274162f](https://linux-hardware.org/?probe=692274162f) | Jan 04, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [e6a4a21d5c](https://linux-hardware.org/?probe=e6a4a21d5c) | Jan 02, 2022 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [8e8da56e93](https://linux-hardware.org/?probe=8e8da56e93) | Jan 01, 2022 |
| OEM           | Unknown                     | Desktop     | [6adc4b5659](https://linux-hardware.org/?probe=6adc4b5659) | Jan 01, 2022 |
| MSI           | MAG B550 TORPEDO            | Desktop     | [b674024789](https://linux-hardware.org/?probe=b674024789) | Dec 30, 2021 |
| MSI           | B460M-A PRO                 | Desktop     | [209e15690e](https://linux-hardware.org/?probe=209e15690e) | Dec 29, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [00696e3398](https://linux-hardware.org/?probe=00696e3398) | Dec 28, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [7280895518](https://linux-hardware.org/?probe=7280895518) | Dec 27, 2021 |
| Unknown       | Unknown                     | Desktop     | [56d5bb8659](https://linux-hardware.org/?probe=56d5bb8659) | Dec 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | Notebook    | [d347eea0b2](https://linux-hardware.org/?probe=d347eea0b2) | Dec 19, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [5cf5b44fc8](https://linux-hardware.org/?probe=5cf5b44fc8) | Dec 13, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [6ab6a89db8](https://linux-hardware.org/?probe=6ab6a89db8) | Dec 12, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [3cd505591d](https://linux-hardware.org/?probe=3cd505591d) | Dec 11, 2021 |
| Dell          | Inspiron 5468               | Notebook    | [ff0b877d5a](https://linux-hardware.org/?probe=ff0b877d5a) | Dec 08, 2021 |
| Dell          | Latitude 7480               | Notebook    | [480ad981d9](https://linux-hardware.org/?probe=480ad981d9) | Dec 07, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [42edbb20ce](https://linux-hardware.org/?probe=42edbb20ce) | Dec 04, 2021 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [e155882ffa](https://linux-hardware.org/?probe=e155882ffa) | Dec 02, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [07bcad31f5](https://linux-hardware.org/?probe=07bcad31f5) | Dec 02, 2021 |
| ASUSTek       | UX430UQ                     | Notebook    | [cf0cd5c862](https://linux-hardware.org/?probe=cf0cd5c862) | Dec 01, 2021 |
| ASUSTek       | UX430UQ                     | Notebook    | [5cd208a361](https://linux-hardware.org/?probe=5cd208a361) | Dec 01, 2021 |
| ASUSTek       | P453UJ                      | Notebook    | [056cba6efd](https://linux-hardware.org/?probe=056cba6efd) | Nov 28, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [aa0a0e67b3](https://linux-hardware.org/?probe=aa0a0e67b3) | Nov 26, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [9bffff74e0](https://linux-hardware.org/?probe=9bffff74e0) | Nov 26, 2021 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [09b0e5058d](https://linux-hardware.org/?probe=09b0e5058d) | Nov 23, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [623b2b0ba9](https://linux-hardware.org/?probe=623b2b0ba9) | Nov 19, 2021 |
| HP            | Elite x2 1012 G2            | Tablet      | [47d816d00f](https://linux-hardware.org/?probe=47d816d00f) | Nov 12, 2021 |
| MSI           | 990FXA-GD65                 | Desktop     | [6d2cade66c](https://linux-hardware.org/?probe=6d2cade66c) | Nov 11, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [efd1c194ac](https://linux-hardware.org/?probe=efd1c194ac) | Nov 11, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [0802656d19](https://linux-hardware.org/?probe=0802656d19) | Nov 11, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [312e04d7f9](https://linux-hardware.org/?probe=312e04d7f9) | Nov 09, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f1f7ca30e5](https://linux-hardware.org/?probe=f1f7ca30e5) | Nov 05, 2021 |
| ASUSTek       | X442UAR                     | Notebook    | [0db140fa3d](https://linux-hardware.org/?probe=0db140fa3d) | Nov 03, 2021 |
| OEM           | Intel H81                   | Desktop     | [a4e298caf1](https://linux-hardware.org/?probe=a4e298caf1) | Nov 02, 2021 |
| OEM           | Intel H81                   | Desktop     | [50758cfaf3](https://linux-hardware.org/?probe=50758cfaf3) | Oct 26, 2021 |
| OEM           | Intel H81                   | Desktop     | [e997f638bc](https://linux-hardware.org/?probe=e997f638bc) | Oct 26, 2021 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [356632b328](https://linux-hardware.org/?probe=356632b328) | Oct 19, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [d377aa2b23](https://linux-hardware.org/?probe=d377aa2b23) | Oct 17, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [7447071c00](https://linux-hardware.org/?probe=7447071c00) | Oct 16, 2021 |
| MSI           | Boston                      | Desktop     | [77d385bc09](https://linux-hardware.org/?probe=77d385bc09) | Oct 13, 2021 |
| MSI           | Boston                      | Desktop     | [14528f628a](https://linux-hardware.org/?probe=14528f628a) | Oct 13, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [0bf0387391](https://linux-hardware.org/?probe=0bf0387391) | Oct 07, 2021 |
| Acer          | Aspire V5-471               | Notebook    | [6a5bc4355e](https://linux-hardware.org/?probe=6a5bc4355e) | Oct 05, 2021 |
| Acer          | Aspire V5-471               | Notebook    | [4b9f0ceb64](https://linux-hardware.org/?probe=4b9f0ceb64) | Oct 05, 2021 |
| ASUSTek       | VivoBook S15 X510UF         | Notebook    | [883e0dec71](https://linux-hardware.org/?probe=883e0dec71) | Sep 19, 2021 |
| Dell          | Latitude E7250              | Notebook    | [275b9204f5](https://linux-hardware.org/?probe=275b9204f5) | Sep 13, 2021 |
| Gigabyte      | H81M-S                      | Desktop     | [8109d84e42](https://linux-hardware.org/?probe=8109d84e42) | Sep 12, 2021 |
| Lenovo        | ThinkPad T430s 2356GPU      | Notebook    | [6a9842e166](https://linux-hardware.org/?probe=6a9842e166) | Sep 06, 2021 |
| ASUSTek       | PRIME H370-PLUS             | Desktop     | [752964e357](https://linux-hardware.org/?probe=752964e357) | Sep 05, 2021 |
| ASUSTek       | X456UQ                      | Notebook    | [6ce8e44ad3](https://linux-hardware.org/?probe=6ce8e44ad3) | Sep 02, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [7a654e5473](https://linux-hardware.org/?probe=7a654e5473) | Aug 28, 2021 |
| Acer          | Aspire 4349                 | Notebook    | [527e511232](https://linux-hardware.org/?probe=527e511232) | Aug 27, 2021 |
| Gigabyte      | B250M-Gaming5-CF            | Desktop     | [c34514576a](https://linux-hardware.org/?probe=c34514576a) | Aug 17, 2021 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [460fc8dfd4](https://linux-hardware.org/?probe=460fc8dfd4) | Aug 08, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [48853e253b](https://linux-hardware.org/?probe=48853e253b) | Aug 04, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [c672738a0e](https://linux-hardware.org/?probe=c672738a0e) | Aug 04, 2021 |
| ASUSTek       | VivoBook S15 X530UA         | Notebook    | [c22e4ce5b4](https://linux-hardware.org/?probe=c22e4ce5b4) | Jul 29, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ab8a90e145](https://linux-hardware.org/?probe=ab8a90e145) | Jul 25, 2021 |
| Unknown       | Unknown                     | Notebook    | [1f6b072c8e](https://linux-hardware.org/?probe=1f6b072c8e) | Jul 24, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [dd58ecd9c7](https://linux-hardware.org/?probe=dd58ecd9c7) | Jul 23, 2021 |
| ASUSTek       | X550JK                      | Notebook    | [ebd01f2605](https://linux-hardware.org/?probe=ebd01f2605) | Jul 22, 2021 |
| Unknown       | Unknown                     | Desktop     | [c6dea4c88d](https://linux-hardware.org/?probe=c6dea4c88d) | Jul 19, 2021 |
| Biostar       | TZ68K+                      | Desktop     | [52ef8197ad](https://linux-hardware.org/?probe=52ef8197ad) | Jul 13, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [3b153ae2f9](https://linux-hardware.org/?probe=3b153ae2f9) | Jun 24, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [988fc9a599](https://linux-hardware.org/?probe=988fc9a599) | Jun 24, 2021 |
| HP            | 15                          | Notebook    | [4f6c5d8c89](https://linux-hardware.org/?probe=4f6c5d8c89) | Jun 22, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [406cb898f1](https://linux-hardware.org/?probe=406cb898f1) | Jun 17, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [2a633bc008](https://linux-hardware.org/?probe=2a633bc008) | Jun 14, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [e3bb48a049](https://linux-hardware.org/?probe=e3bb48a049) | Jun 14, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [1927d0abfe](https://linux-hardware.org/?probe=1927d0abfe) | Jun 13, 2021 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [23e735bb8f](https://linux-hardware.org/?probe=23e735bb8f) | Jun 08, 2021 |
| Dell          | 0VHWTR A02                  | Desktop     | [ec7174828a](https://linux-hardware.org/?probe=ec7174828a) | Jun 04, 2021 |
| ASUSTek       | UX310UAK                    | Notebook    | [4a79148721](https://linux-hardware.org/?probe=4a79148721) | Jun 03, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [6b5f1170f9](https://linux-hardware.org/?probe=6b5f1170f9) | Jun 02, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [e2389864db](https://linux-hardware.org/?probe=e2389864db) | Jun 02, 2021 |
| HP            | ENVY TS 14 Sleekbook        | Notebook    | [f52091e51e](https://linux-hardware.org/?probe=f52091e51e) | May 31, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [0226c84811](https://linux-hardware.org/?probe=0226c84811) | May 25, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [b2c4e6f3a5](https://linux-hardware.org/?probe=b2c4e6f3a5) | May 25, 2021 |
| HP            | 15 Notebook PC              | Notebook    | [b34d6d63d9](https://linux-hardware.org/?probe=b34d6d63d9) | May 22, 2021 |
| MSI           | B85M GAMING                 | Desktop     | [4d2529b647](https://linux-hardware.org/?probe=4d2529b647) | May 22, 2021 |
| Lenovo        | ThinkPad T430s 2356GPU      | Notebook    | [8f1510061b](https://linux-hardware.org/?probe=8f1510061b) | May 18, 2021 |
| Lenovo        | ThinkPad T430s 2356GPU      | Notebook    | [e78b76fcf3](https://linux-hardware.org/?probe=e78b76fcf3) | May 18, 2021 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [aba051d387](https://linux-hardware.org/?probe=aba051d387) | May 15, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [fa9f8b7f7e](https://linux-hardware.org/?probe=fa9f8b7f7e) | May 10, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [db1a234412](https://linux-hardware.org/?probe=db1a234412) | May 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [b7e4895fd8](https://linux-hardware.org/?probe=b7e4895fd8) | May 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [1254eab2b7](https://linux-hardware.org/?probe=1254eab2b7) | May 04, 2021 |
| HP            | 15                          | Notebook    | [fd4d562cd2](https://linux-hardware.org/?probe=fd4d562cd2) | May 04, 2021 |
| MSI           | Summit B14 A11MOT           | Notebook    | [9bdd91f198](https://linux-hardware.org/?probe=9bdd91f198) | May 02, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [dbcbb68258](https://linux-hardware.org/?probe=dbcbb68258) | Apr 26, 2021 |
| Unknown       | Unknown                     | Desktop     | [b2600d2372](https://linux-hardware.org/?probe=b2600d2372) | Apr 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [367455807e](https://linux-hardware.org/?probe=367455807e) | Mar 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1de185d0da](https://linux-hardware.org/?probe=1de185d0da) | Mar 22, 2021 |
| Dell          | Latitude E4300              | Notebook    | [2ccfcf6a1b](https://linux-hardware.org/?probe=2ccfcf6a1b) | Mar 22, 2021 |
| HP            | 15                          | Notebook    | [860412bddc](https://linux-hardware.org/?probe=860412bddc) | Mar 20, 2021 |
| HP            | 15                          | Notebook    | [62447250f9](https://linux-hardware.org/?probe=62447250f9) | Mar 17, 2021 |
| ASUSTek       | H110M-CS                    | Desktop     | [ac52c3630c](https://linux-hardware.org/?probe=ac52c3630c) | Mar 12, 2021 |
| Lenovo        | ThinkPad E490 20N9S1XE00    | Notebook    | [4ee1271923](https://linux-hardware.org/?probe=4ee1271923) | Mar 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [6343267ab7](https://linux-hardware.org/?probe=6343267ab7) | Mar 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [47123299d4](https://linux-hardware.org/?probe=47123299d4) | Mar 09, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [a8091a8c28](https://linux-hardware.org/?probe=a8091a8c28) | Mar 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [8f8fe2c911](https://linux-hardware.org/?probe=8f8fe2c911) | Mar 06, 2021 |
| ASUSTek       | X411UNV                     | Notebook    | [009f3bb5e5](https://linux-hardware.org/?probe=009f3bb5e5) | Feb 27, 2021 |
| HP            | 15                          | Notebook    | [e74fa488e9](https://linux-hardware.org/?probe=e74fa488e9) | Feb 27, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [89174dda21](https://linux-hardware.org/?probe=89174dda21) | Feb 27, 2021 |
| ASUSTek       | ZenBook UX461FA_UX461FA     | Convertible | [8efc8caada](https://linux-hardware.org/?probe=8efc8caada) | Feb 27, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [b414109f66](https://linux-hardware.org/?probe=b414109f66) | Feb 07, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [08a1160725](https://linux-hardware.org/?probe=08a1160725) | Feb 07, 2021 |
| HP            | Notebook                    | Notebook    | [df39c8aaf8](https://linux-hardware.org/?probe=df39c8aaf8) | Feb 02, 2021 |
| ASUSTek       | X45C                        | Notebook    | [349beec2d5](https://linux-hardware.org/?probe=349beec2d5) | Jan 27, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [474d61d1a7](https://linux-hardware.org/?probe=474d61d1a7) | Jan 27, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [c9e8f99464](https://linux-hardware.org/?probe=c9e8f99464) | Jan 21, 2021 |
| Lenovo        | ThinkPad T450 20BUS2021M    | Notebook    | [60929bb3d1](https://linux-hardware.org/?probe=60929bb3d1) | Jan 21, 2021 |
| Gigabyte      | B365M HD3                   | Desktop     | [32878b3dae](https://linux-hardware.org/?probe=32878b3dae) | Jan 20, 2021 |
| Gigabyte      | B365M HD3                   | Desktop     | [03b73f8223](https://linux-hardware.org/?probe=03b73f8223) | Jan 20, 2021 |
| HP            | Notebook                    | Notebook    | [d14d8fe5db](https://linux-hardware.org/?probe=d14d8fe5db) | Jan 19, 2021 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [0bfbe639fc](https://linux-hardware.org/?probe=0bfbe639fc) | Jan 18, 2021 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [e053ef39b6](https://linux-hardware.org/?probe=e053ef39b6) | Jan 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [5ee0809420](https://linux-hardware.org/?probe=5ee0809420) | Jan 16, 2021 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [4c2ddc3c14](https://linux-hardware.org/?probe=4c2ddc3c14) | Jan 10, 2021 |
| HP            | 15                          | Notebook    | [1b3597829c](https://linux-hardware.org/?probe=1b3597829c) | Jan 05, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [150aed5937](https://linux-hardware.org/?probe=150aed5937) | Dec 28, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [f3aaccf16d](https://linux-hardware.org/?probe=f3aaccf16d) | Dec 19, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [eff007611b](https://linux-hardware.org/?probe=eff007611b) | Dec 16, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [1eec63b277](https://linux-hardware.org/?probe=1eec63b277) | Dec 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [da59a1c5a8](https://linux-hardware.org/?probe=da59a1c5a8) | Dec 07, 2020 |
| MSI           | GS63 7RD                    | Notebook    | [51929f5d16](https://linux-hardware.org/?probe=51929f5d16) | Dec 05, 2020 |
| Gigabyte      | B85M-HD3                    | Desktop     | [983f59c8ba](https://linux-hardware.org/?probe=983f59c8ba) | Nov 17, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [4d0297d500](https://linux-hardware.org/?probe=4d0297d500) | Nov 15, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [2898db77af](https://linux-hardware.org/?probe=2898db77af) | Nov 14, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [399693b152](https://linux-hardware.org/?probe=399693b152) | Nov 04, 2020 |
| HP            | 15                          | Notebook    | [751dbba280](https://linux-hardware.org/?probe=751dbba280) | Nov 04, 2020 |
| Unknown       | Unknown                     | Desktop     | [49351fb74d](https://linux-hardware.org/?probe=49351fb74d) | Nov 03, 2020 |
| Unknown       | Unknown                     | Desktop     | [a5450c668e](https://linux-hardware.org/?probe=a5450c668e) | Oct 30, 2020 |
| ASRock        | AB350 Pro4                  | Desktop     | [7e48c5dac7](https://linux-hardware.org/?probe=7e48c5dac7) | Oct 30, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [20da8831d7](https://linux-hardware.org/?probe=20da8831d7) | Oct 29, 2020 |
| ASUSTek       | H81M-K                      | Desktop     | [6abbe0be7c](https://linux-hardware.org/?probe=6abbe0be7c) | Oct 29, 2020 |
| Notebook      | DCL C483                    | Notebook    | [ed2bb10c86](https://linux-hardware.org/?probe=ed2bb10c86) | Oct 29, 2020 |
| ASUSTek       | H110M-CS                    | Desktop     | [4bc7a25c4b](https://linux-hardware.org/?probe=4bc7a25c4b) | Oct 29, 2020 |
| ASUSTek       | H81M-K                      | Desktop     | [7a6ee90819](https://linux-hardware.org/?probe=7a6ee90819) | Oct 29, 2020 |
| HP            | ENVY Sleekbook 4            | Notebook    | [b2377a6388](https://linux-hardware.org/?probe=b2377a6388) | Oct 29, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [c85f72911e](https://linux-hardware.org/?probe=c85f72911e) | Oct 29, 2020 |
| Acer          | Aspire E5-576               | Notebook    | [1f7d96b34a](https://linux-hardware.org/?probe=1f7d96b34a) | Oct 27, 2020 |
| ASRock        | B450 Gaming K4              | Desktop     | [76e61701fa](https://linux-hardware.org/?probe=76e61701fa) | Oct 24, 2020 |
| ASUSTek       | P453UA                      | Notebook    | [a376addbeb](https://linux-hardware.org/?probe=a376addbeb) | Oct 21, 2020 |
| Acer          | Aspire E5-575               | Notebook    | [218b3ce742](https://linux-hardware.org/?probe=218b3ce742) | Oct 12, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [da1765fe36](https://linux-hardware.org/?probe=da1765fe36) | Oct 11, 2020 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [a9c53146fc](https://linux-hardware.org/?probe=a9c53146fc) | Oct 10, 2020 |
| Acer          | Aspire A515-51G             | Notebook    | [be8091856c](https://linux-hardware.org/?probe=be8091856c) | Oct 09, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [a6f1865423](https://linux-hardware.org/?probe=a6f1865423) | Oct 07, 2020 |
| ASUSTek       | X510UQ                      | Notebook    | [75933321b6](https://linux-hardware.org/?probe=75933321b6) | Oct 02, 2020 |
| Acer          | Aspire 4752                 | Notebook    | [ae7fe5907d](https://linux-hardware.org/?probe=ae7fe5907d) | Sep 27, 2020 |
| ASUSTek       | X555LF                      | Notebook    | [ed0ef70a05](https://linux-hardware.org/?probe=ed0ef70a05) | Sep 19, 2020 |
| Gigabyte      | GA-E350N                    | Desktop     | [871d27c2e8](https://linux-hardware.org/?probe=871d27c2e8) | Sep 18, 2020 |
| Gigabyte      | GA-E350N                    | Desktop     | [3f442c236c](https://linux-hardware.org/?probe=3f442c236c) | Sep 18, 2020 |
| HP            | ProBook 440 G5              | Notebook    | [d7b1ce1a01](https://linux-hardware.org/?probe=d7b1ce1a01) | Sep 15, 2020 |
| Notebook      | N2x0LU                      | Notebook    | [86354a1c26](https://linux-hardware.org/?probe=86354a1c26) | Sep 14, 2020 |
| ASUSTek       | X510UQ                      | Notebook    | [e289d19d20](https://linux-hardware.org/?probe=e289d19d20) | Sep 14, 2020 |
| ASRock        | Z77 Pro3                    | Desktop     | [8d6db6e2d3](https://linux-hardware.org/?probe=8d6db6e2d3) | Sep 09, 2020 |
| ASUSTek       | X555LF                      | Notebook    | [22629ba9b2](https://linux-hardware.org/?probe=22629ba9b2) | Sep 07, 2020 |
| Lenovo        | ThinkPad E490 20N9S1XE00    | Notebook    | [43ddcf3c95](https://linux-hardware.org/?probe=43ddcf3c95) | Sep 06, 2020 |
| Unknown       | Unknown                     | Phone       | [d4a5776865](https://linux-hardware.org/?probe=d4a5776865) | Sep 02, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [38548d7877](https://linux-hardware.org/?probe=38548d7877) | Sep 01, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [3edf866f94](https://linux-hardware.org/?probe=3edf866f94) | Aug 22, 2020 |
| Acer          | Aspire E5-576               | Notebook    | [3a9beeb9f4](https://linux-hardware.org/?probe=3a9beeb9f4) | Aug 16, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [3c3b21f81b](https://linux-hardware.org/?probe=3c3b21f81b) | Aug 15, 2020 |
| HP            | 14                          | Notebook    | [b7289075c1](https://linux-hardware.org/?probe=b7289075c1) | Aug 08, 2020 |
| SYS           | H310CH5-TI2                 | Desktop     | [fb33742784](https://linux-hardware.org/?probe=fb33742784) | Aug 06, 2020 |
| HP            | EliteBook 850 G2            | Notebook    | [1c81c3c24d](https://linux-hardware.org/?probe=1c81c3c24d) | Jul 30, 2020 |
| Acer          | Aspire E5-473               | Notebook    | [27a9cd08a6](https://linux-hardware.org/?probe=27a9cd08a6) | Jul 26, 2020 |
| Gigabyte      | B250M-HD3-CF                | Desktop     | [f1ef1518c4](https://linux-hardware.org/?probe=f1ef1518c4) | Jul 25, 2020 |
| Gigabyte      | B250M-HD3-CF                | Desktop     | [bf80f266b6](https://linux-hardware.org/?probe=bf80f266b6) | Jul 25, 2020 |
| Acer          | Aspire E5-473               | Notebook    | [9c3656a710](https://linux-hardware.org/?probe=9c3656a710) | Jul 24, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [3c50b289eb](https://linux-hardware.org/?probe=3c50b289eb) | Jul 21, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [e800855127](https://linux-hardware.org/?probe=e800855127) | Jul 21, 2020 |
| Dell          | Latitude E7470              | Notebook    | [74e59971a2](https://linux-hardware.org/?probe=74e59971a2) | Jul 09, 2020 |
| ASUSTek       | X200CA                      | Notebook    | [eb79a1863c](https://linux-hardware.org/?probe=eb79a1863c) | Jul 08, 2020 |
| ASUSTek       | X200CA                      | Notebook    | [374493e07f](https://linux-hardware.org/?probe=374493e07f) | Jul 08, 2020 |
| HP            | EliteBook 2570p             | Notebook    | [04f260c99a](https://linux-hardware.org/?probe=04f260c99a) | Jul 06, 2020 |
| HP            | EliteBook 2570p             | Notebook    | [aa5a987949](https://linux-hardware.org/?probe=aa5a987949) | Jul 06, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [e8be3d4a45](https://linux-hardware.org/?probe=e8be3d4a45) | Jul 02, 2020 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [d59cf3e39f](https://linux-hardware.org/?probe=d59cf3e39f) | Jun 21, 2020 |
| Lenovo        | IdeaPad 310-14ISK 80SL      | Notebook    | [bedb334316](https://linux-hardware.org/?probe=bedb334316) | Jun 11, 2020 |
| Gigabyte      | B75MS                       | Desktop     | [116d7e4473](https://linux-hardware.org/?probe=116d7e4473) | Jun 06, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [0690307575](https://linux-hardware.org/?probe=0690307575) | Jun 06, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [2d68573dcb](https://linux-hardware.org/?probe=2d68573dcb) | Jun 04, 2020 |
| ASRock        | B450 Gaming K4              | Desktop     | [24ebee7f8d](https://linux-hardware.org/?probe=24ebee7f8d) | Jun 03, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [e10a133997](https://linux-hardware.org/?probe=e10a133997) | Jun 02, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [7b57cf3668](https://linux-hardware.org/?probe=7b57cf3668) | May 30, 2020 |
| ASUSTek       | H61M-A                      | Desktop     | [821df8e348](https://linux-hardware.org/?probe=821df8e348) | May 25, 2020 |
| ASUSTek       | H61M-A                      | Desktop     | [6118e39327](https://linux-hardware.org/?probe=6118e39327) | May 25, 2020 |
| HP            | Notebook                    | Notebook    | [024a28eb0b](https://linux-hardware.org/?probe=024a28eb0b) | May 23, 2020 |
| Dell          | Latitude E7450              | Notebook    | [f3e9ca7a40](https://linux-hardware.org/?probe=f3e9ca7a40) | May 21, 2020 |
| Lenovo        | ThinkPad E470 20H1A029SG    | Notebook    | [6afaed7f7f](https://linux-hardware.org/?probe=6afaed7f7f) | May 21, 2020 |
| Dell          | Latitude E7450              | Notebook    | [e6818ffd7d](https://linux-hardware.org/?probe=e6818ffd7d) | May 21, 2020 |
| Notebook      | W9x0LU                      | Notebook    | [c7455fcb18](https://linux-hardware.org/?probe=c7455fcb18) | May 17, 2020 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [5d81beb457](https://linux-hardware.org/?probe=5d81beb457) | May 17, 2020 |
| ASUSTek       | X510UNR                     | Notebook    | [7b1a18ebf9](https://linux-hardware.org/?probe=7b1a18ebf9) | May 09, 2020 |
| ASUSTek       | X556URK                     | Notebook    | [63c6b5a357](https://linux-hardware.org/?probe=63c6b5a357) | May 08, 2020 |
| Foxconn       | 17A0                        | Desktop     | [167cb26122](https://linux-hardware.org/?probe=167cb26122) | May 03, 2020 |
| Notebook      | N750BU                      | Notebook    | [e3f870729f](https://linux-hardware.org/?probe=e3f870729f) | Apr 23, 2020 |
| ASUSTek       | H81M-K                      | Desktop     | [de6fa960ad](https://linux-hardware.org/?probe=de6fa960ad) | Apr 23, 2020 |
| I-Life Dig... | ZED_AIR_PLUS                | Convertible | [b1a911e13e](https://linux-hardware.org/?probe=b1a911e13e) | Mar 27, 2020 |
| MSI           | H61M-P31/W8                 | Desktop     | [26d8323c91](https://linux-hardware.org/?probe=26d8323c91) | Mar 25, 2020 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [baa90e0762](https://linux-hardware.org/?probe=baa90e0762) | Mar 22, 2020 |
| Gigabyte      | X299 AORUS Gaming 3 Pro-... | Desktop     | [34ced022e3](https://linux-hardware.org/?probe=34ced022e3) | Feb 29, 2020 |
| HP            | Mini 210-4000               | Notebook    | [61c0ab33d8](https://linux-hardware.org/?probe=61c0ab33d8) | Feb 28, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [729f8e494d](https://linux-hardware.org/?probe=729f8e494d) | Feb 14, 2020 |
| Dell          | Inspiron 13-5378            | Notebook    | [357823f120](https://linux-hardware.org/?probe=357823f120) | Feb 03, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [e9a4da7f1c](https://linux-hardware.org/?probe=e9a4da7f1c) | Jan 31, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | Notebook    | [4fad937155](https://linux-hardware.org/?probe=4fad937155) | Jan 10, 2020 |
| Lenovo        | ThinkPad L380 20M6S22500    | Notebook    | [15c43def70](https://linux-hardware.org/?probe=15c43def70) | Jan 09, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [9d4e0d1911](https://linux-hardware.org/?probe=9d4e0d1911) | Jan 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [2d0bca85ea](https://linux-hardware.org/?probe=2d0bca85ea) | Dec 29, 2019 |
| Gigabyte      | B85M-D3H                    | Desktop     | [753205d5df](https://linux-hardware.org/?probe=753205d5df) | Dec 27, 2019 |
| HP            | ProBook 450 G4              | Notebook    | [d85b25cd22](https://linux-hardware.org/?probe=d85b25cd22) | Dec 24, 2019 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | Notebook    | [30c00cb837](https://linux-hardware.org/?probe=30c00cb837) | Dec 14, 2019 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | Notebook    | [e004d9f500](https://linux-hardware.org/?probe=e004d9f500) | Dec 14, 2019 |
| ASUSTek       | E202SA                      | Notebook    | [e052cf247b](https://linux-hardware.org/?probe=e052cf247b) | Nov 23, 2019 |
| HP            | ProBook 450 G4              | Notebook    | [44d09b2105](https://linux-hardware.org/?probe=44d09b2105) | Nov 19, 2019 |
| HP            | ProBook 450 G4              | Notebook    | [3fc910f23c](https://linux-hardware.org/?probe=3fc910f23c) | Nov 19, 2019 |
| Acer          | Aspire E5-571G              | Notebook    | [afc9fdb4b3](https://linux-hardware.org/?probe=afc9fdb4b3) | Nov 14, 2019 |
| Acer          | Aspire E5-571G              | Notebook    | [7914862967](https://linux-hardware.org/?probe=7914862967) | Nov 14, 2019 |
| MSI           | PH67A-C43                   | Desktop     | [b472118c5a](https://linux-hardware.org/?probe=b472118c5a) | Oct 29, 2019 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [73a0de63c0](https://linux-hardware.org/?probe=73a0de63c0) | Sep 27, 2019 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [4299e1c036](https://linux-hardware.org/?probe=4299e1c036) | Sep 27, 2019 |
| HP            | ProBook 450 G1              | Notebook    | [671ea53b31](https://linux-hardware.org/?probe=671ea53b31) | Sep 22, 2019 |
| HP            | ProBook 450 G1              | Notebook    | [53b4bf1914](https://linux-hardware.org/?probe=53b4bf1914) | Sep 22, 2019 |
| ASUSTek       | X441UA                      | Notebook    | [6022620aee](https://linux-hardware.org/?probe=6022620aee) | Sep 17, 2019 |
| ASUSTek       | X441UA                      | Notebook    | [d0632368ab](https://linux-hardware.org/?probe=d0632368ab) | Sep 04, 2019 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [ede7f2c199](https://linux-hardware.org/?probe=ede7f2c199) | Aug 30, 2019 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [e3c13fc2d8](https://linux-hardware.org/?probe=e3c13fc2d8) | Aug 20, 2019 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [d0d6cd20b1](https://linux-hardware.org/?probe=d0d6cd20b1) | Jul 26, 2019 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [f9b65f1415](https://linux-hardware.org/?probe=f9b65f1415) | Jul 14, 2019 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [a6f5bc1b0f](https://linux-hardware.org/?probe=a6f5bc1b0f) | Jul 13, 2019 |
| HP            | Notebook                    | Notebook    | [2ce0b2ff35](https://linux-hardware.org/?probe=2ce0b2ff35) | Jul 04, 2019 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [298e510c05](https://linux-hardware.org/?probe=298e510c05) | Jun 22, 2019 |
| Lenovo        | ThinkPad X230 2324F51       | Notebook    | [9291e8f5f3](https://linux-hardware.org/?probe=9291e8f5f3) | Jun 22, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [70fecd4e42](https://linux-hardware.org/?probe=70fecd4e42) | Jun 04, 2019 |
| Acer          | Aspire A515-51              | Notebook    | [ee5c9fcc02](https://linux-hardware.org/?probe=ee5c9fcc02) | Jun 04, 2019 |
| Acer          | Aspire A515-51              | Notebook    | [424ee39d57](https://linux-hardware.org/?probe=424ee39d57) | Jun 04, 2019 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [37a334e523](https://linux-hardware.org/?probe=37a334e523) | Jun 02, 2019 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [cb301afe49](https://linux-hardware.org/?probe=cb301afe49) | Jun 02, 2019 |
| Lenovo        | S10-3                       | Notebook    | [09f132c2fa](https://linux-hardware.org/?probe=09f132c2fa) | May 27, 2019 |
| ASUSTek       | H110M-K                     | Desktop     | [24c1251a9a](https://linux-hardware.org/?probe=24c1251a9a) | May 09, 2019 |
| ASUSTek       | H110M-K                     | Desktop     | [0f42a3ea73](https://linux-hardware.org/?probe=0f42a3ea73) | May 09, 2019 |
| Daffodil C... | DCL S4                      | Notebook    | [291cd2445c](https://linux-hardware.org/?probe=291cd2445c) | May 08, 2019 |
| HP            | ProBook 4540s               | Notebook    | [a8b0fbe3a8](https://linux-hardware.org/?probe=a8b0fbe3a8) | Apr 22, 2019 |
| Foxconn       | G31MV/G31MV-K FAB           | Desktop     | [83303ad448](https://linux-hardware.org/?probe=83303ad448) | Apr 07, 2019 |
| Intel         | Unknown                     | Desktop     | [6abdeb3169](https://linux-hardware.org/?probe=6abdeb3169) | Mar 10, 2019 |
| Intel         | Unknown                     | Desktop     | [d27842b77f](https://linux-hardware.org/?probe=d27842b77f) | Mar 10, 2019 |
| Intel         | Unknown                     | Desktop     | [1c484063a6](https://linux-hardware.org/?probe=1c484063a6) | Mar 09, 2019 |
| ASUSTek       | X510UQ                      | Notebook    | [74e81c78ab](https://linux-hardware.org/?probe=74e81c78ab) | Feb 16, 2019 |
| ASUSTek       | X510UQ                      | Notebook    | [50fc8650ad](https://linux-hardware.org/?probe=50fc8650ad) | Feb 16, 2019 |
| MSI           | P55A-G55                    | Desktop     | [8bc6ce2174](https://linux-hardware.org/?probe=8bc6ce2174) | Dec 08, 2018 |
| MSI           | P55A-G55                    | Desktop     | [24654f4990](https://linux-hardware.org/?probe=24654f4990) | Dec 07, 2018 |
| Gigabyte      | P55-USB3                    | Desktop     | [3cf949c024](https://linux-hardware.org/?probe=3cf949c024) | Jul 21, 2017 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 47        | 14.07%  |
| Ubuntu 22.04                 | 18        | 5.39%   |
| ArcoLinux Rolling            | 12        | 3.59%   |
| Arch                         | 12        | 3.59%   |
| Ubuntu 18.04                 | 11        | 3.29%   |
| Manjaro                      | 11        | 3.29%   |
| Zorin 16                     | 9         | 2.69%   |
| Arch Rolling                 | 9         | 2.69%   |
| Ubuntu 19.10                 | 8         | 2.4%    |
| KDE neon 20.04               | 8         | 2.4%    |
| Pop!_OS 22.04                | 7         | 2.1%    |
| Debian 11                    | 6         | 1.8%    |
| OpenMandriva 4.2             | 5         | 1.5%    |
| Fedora 33                    | 5         | 1.5%    |
| EndeavourOS Rolling          | 5         | 1.5%    |
| Zorin 15                     | 4         | 1.2%    |
| Ubuntu 22.10                 | 4         | 1.2%    |
| Manjaro 20.0.1               | 4         | 1.2%    |
| Linux Mint 20.2              | 4         | 1.2%    |
| Fedora 38                    | 4         | 1.2%    |
| Fedora 37                    | 4         | 1.2%    |
| Ubuntu 19.04                 | 3         | 0.9%    |
| Pop!_OS 21.10                | 3         | 0.9%    |
| Pop!_OS 21.04                | 3         | 0.9%    |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 0.9%    |
| OpenMandriva 4.3             | 3         | 0.9%    |
| Manjaro 20.1.2               | 3         | 0.9%    |
| Linux Mint 21                | 3         | 0.9%    |
| Linux Mint 20.1              | 3         | 0.9%    |
| Linux Mint 20                | 3         | 0.9%    |
| Kubuntu 20.04                | 3         | 0.9%    |
| KDE neon 22.04               | 3         | 0.9%    |
| Ubuntu 21.04                 | 2         | 0.6%    |
| Ubuntu 20.10                 | 2         | 0.6%    |
| Ubuntu 18.10                 | 2         | 0.6%    |
| Pop!_OS 20.10                | 2         | 0.6%    |
| Parrot 5.1                   | 2         | 0.6%    |
| OpenMandriva 4.90            | 2         | 0.6%    |
| MX 21                        | 2         | 0.6%    |
| Manjaro 21.2.6               | 2         | 0.6%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 97        | 31.29%  |
| Manjaro      | 30        | 9.68%   |
| Arch         | 20        | 6.45%   |
| Linux Mint   | 17        | 5.48%   |
| Fedora       | 17        | 5.48%   |
| Pop!_OS      | 14        | 4.52%   |
| Zorin        | 13        | 4.19%   |
| ArcoLinux    | 12        | 3.87%   |
| KDE neon     | 11        | 3.55%   |
| OpenMandriva | 10        | 3.23%   |
| Kubuntu      | 10        | 3.23%   |
| Debian       | 10        | 3.23%   |
| Endless      | 6         | 1.94%   |
| EndeavourOS  | 6         | 1.94%   |
| Parrot       | 5         | 1.61%   |
| Kali         | 5         | 1.61%   |
| openSUSE     | 3         | 0.97%   |
| MX           | 2         | 0.65%   |
| LMDE         | 2         | 0.65%   |
| Deepin       | 2         | 0.65%   |
| CentOS       | 2         | 0.65%   |
| BlackPanther | 2         | 0.65%   |
| Artix        | 2         | 0.65%   |
| Void Linux   | 1         | 0.32%   |
| Ubuntu Unity | 1         | 0.32%   |
| Ubuntu MATE  | 1         | 0.32%   |
| ROSA         | 1         | 0.32%   |
| Pragma       | 1         | 0.32%   |
| Lubuntu      | 1         | 0.32%   |
| Gentoo       | 1         | 0.32%   |
| Garuda Linux | 1         | 0.32%   |
| Elementary   | 1         | 0.32%   |
| Devuan       | 1         | 0.32%   |
| Clear Linux  | 1         | 0.32%   |
| Android      | 1         | 0.32%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 8         | 2.2%    |
| 5.4.0-52-generic         | 6         | 1.65%   |
| 5.10.14-desktop-1omv4002 | 5         | 1.37%   |
| 5.13.0-28-generic        | 4         | 1.1%    |
| 6.2.0-32-generic         | 3         | 0.82%   |
| 5.9.16-1-MANJARO         | 3         | 0.82%   |
| 5.8.0-55-generic         | 3         | 0.82%   |
| 5.8.0-41-generic         | 3         | 0.82%   |
| 5.6.11-1-MANJARO         | 3         | 0.82%   |
| 5.4.0-53-generic         | 3         | 0.82%   |
| 5.4.0-40-generic         | 3         | 0.82%   |
| 5.4.0-29-generic         | 3         | 0.82%   |
| 5.16.7-desktop-1omv4003  | 3         | 0.82%   |
| 5.15.0-57-generic        | 3         | 0.82%   |
| 5.15.0-56-generic        | 3         | 0.82%   |
| 5.15.0-48-generic        | 3         | 0.82%   |
| 5.11.0-37-generic        | 3         | 0.82%   |
| 5.11.0-16-generic        | 3         | 0.82%   |
| 6.2.9-300.fc38.x86_64    | 2         | 0.55%   |
| 6.2.0-33-generic         | 2         | 0.55%   |
| 6.2.0-26-generic         | 2         | 0.55%   |
| 6.1.12-arch1-1           | 2         | 0.55%   |
| 6.0.9-zen1-1-zen         | 2         | 0.55%   |
| 6.0.0-kali6-amd64        | 2         | 0.55%   |
| 5.8.16-2-MANJARO         | 2         | 0.55%   |
| 5.8.0-50-generic         | 2         | 0.55%   |
| 5.8.0-44-generic         | 2         | 0.55%   |
| 5.8.0-38-generic         | 2         | 0.55%   |
| 5.8.0-14-generic         | 2         | 0.55%   |
| 5.7.19-2-MANJARO         | 2         | 0.55%   |
| 5.4.8-arch1-1            | 2         | 0.55%   |
| 5.4.0-90-generic         | 2         | 0.55%   |
| 5.4.0-73-generic         | 2         | 0.55%   |
| 5.4.0-47-generic         | 2         | 0.55%   |
| 5.4.0-26-generic         | 2         | 0.55%   |
| 5.4.0-19-generic         | 2         | 0.55%   |
| 5.3.0-40-generic         | 2         | 0.55%   |
| 5.3.0-24-generic         | 2         | 0.55%   |
| 5.3.0-23-generic         | 2         | 0.55%   |
| 5.3.0-18-generic         | 2         | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 40        | 11.56%  |
| 5.15.0  | 28        | 8.09%   |
| 5.11.0  | 19        | 5.49%   |
| 5.8.0   | 18        | 5.2%    |
| 5.13.0  | 17        | 4.91%   |
| 5.3.0   | 13        | 3.76%   |
| 5.19.0  | 13        | 3.76%   |
| 5.10.0  | 10        | 2.89%   |
| 6.2.0   | 7         | 2.02%   |
| 5.0.0   | 7         | 2.02%   |
| 4.18.0  | 7         | 2.02%   |
| 4.15.0  | 7         | 2.02%   |
| 6.0.0   | 6         | 1.73%   |
| 5.10.14 | 5         | 1.45%   |
| 5.9.16  | 4         | 1.16%   |
| 5.8.16  | 4         | 1.16%   |
| 4.19.0  | 4         | 1.16%   |
| 6.1.8   | 3         | 0.87%   |
| 6.0.12  | 3         | 0.87%   |
| 5.6.11  | 3         | 0.87%   |
| 5.18.12 | 3         | 0.87%   |
| 5.16.7  | 3         | 0.87%   |
| 6.2.9   | 2         | 0.58%   |
| 6.2.7   | 2         | 0.58%   |
| 6.1.12  | 2         | 0.58%   |
| 6.1.0   | 2         | 0.58%   |
| 6.0.9   | 2         | 0.58%   |
| 5.7.19  | 2         | 0.58%   |
| 5.4.8   | 2         | 0.58%   |
| 5.17.0  | 2         | 0.58%   |
| 5.16.15 | 2         | 0.58%   |
| 5.16.11 | 2         | 0.58%   |
| 5.15.7  | 2         | 0.58%   |
| 5.15.5  | 2         | 0.58%   |
| 5.15.13 | 2         | 0.58%   |
| 5.11.6  | 2         | 0.58%   |
| 5.10.52 | 2         | 0.58%   |
| 6.5.2   | 1         | 0.29%   |
| 6.5.0   | 1         | 0.29%   |
| 6.4.9   | 1         | 0.29%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 47        | 13.99%  |
| 5.15    | 45        | 13.39%  |
| 5.8     | 25        | 7.44%   |
| 5.11    | 24        | 7.14%   |
| 5.10    | 23        | 6.85%   |
| 5.13    | 19        | 5.65%   |
| 6.2     | 15        | 4.46%   |
| 5.19    | 15        | 4.46%   |
| 6.0     | 13        | 3.87%   |
| 5.3     | 13        | 3.87%   |
| 5.16    | 13        | 3.87%   |
| 6.1     | 10        | 2.98%   |
| 4.18    | 8         | 2.38%   |
| 5.18    | 7         | 2.08%   |
| 5.0     | 7         | 2.08%   |
| 4.15    | 7         | 2.08%   |
| 5.9     | 5         | 1.49%   |
| 5.7     | 5         | 1.49%   |
| 5.6     | 5         | 1.49%   |
| 5.17    | 5         | 1.49%   |
| 4.19    | 5         | 1.49%   |
| 6.4     | 4         | 1.19%   |
| 6.3     | 3         | 0.89%   |
| 5.14    | 3         | 0.89%   |
| 6.5     | 2         | 0.6%    |
| 5.12    | 2         | 0.6%    |
| 5.1     | 2         | 0.6%    |
| 4.9     | 1         | 0.3%    |
| 4.4     | 1         | 0.3%    |
| 4.13    | 1         | 0.3%    |
| 3.18    | 1         | 0.3%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 288       | 97.63%  |
| i686    | 4         | 1.36%   |
| aarch64 | 3         | 1.02%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 145       | 46.93%  |
| KDE5            | 67        | 21.68%  |
| Unknown         | 30        | 9.71%   |
| XFCE            | 20        | 6.47%   |
| X-Cinnamon      | 17        | 5.5%    |
| MATE            | 6         | 1.94%   |
| awesome         | 5         | 1.62%   |
| KDE             | 4         | 1.29%   |
| i3-with-shmlog  | 2         | 0.65%   |
| Deepin          | 2         | 0.65%   |
| Unity           | 1         | 0.32%   |
| qtile           | 1         | 0.32%   |
| Pantheon        | 1         | 0.32%   |
| openbox         | 1         | 0.32%   |
| LXQt            | 1         | 0.32%   |
| LXDE            | 1         | 0.32%   |
| i3              | 1         | 0.32%   |
| GNOME Flashback | 1         | 0.32%   |
| DWM             | 1         | 0.32%   |
| Cinnamon        | 1         | 0.32%   |
| bspwm           | 1         | 0.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 245       | 78.78%  |
| Wayland | 45        | 14.47%  |
| Unknown | 17        | 5.47%   |
| Tty     | 4         | 1.29%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 150       | 48.08%  |
| SDDM    | 47        | 15.06%  |
| GDM     | 43        | 13.78%  |
| GDM3    | 33        | 10.58%  |
| LightDM | 30        | 9.62%   |
| TDM     | 9         | 2.88%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 248       | 82.67%  |
| Unknown | 30        | 10%     |
| en_GB   | 10        | 3.33%   |
| C       | 7         | 2.33%   |
| en_IE   | 1         | 0.33%   |
| en_EN   | 1         | 0.33%   |
| en_CA   | 1         | 0.33%   |
| en_AG   | 1         | 0.33%   |
| Default | 1         | 0.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 159       | 51.46%  |
| BIOS | 150       | 48.54%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 236       | 77.63%  |
| Btrfs   | 29        | 9.54%   |
| Overlay | 26        | 8.55%   |
| Unknown | 5         | 1.64%   |
| Tmpfs   | 4         | 1.32%   |
| Xfs     | 3         | 0.99%   |
| Zfs     | 1         | 0.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 160       | 51.61%  |
| GPT     | 119       | 38.39%  |
| MBR     | 31        | 10%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 256       | 84.49%  |
| Yes       | 47        | 15.51%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 174       | 57.05%  |
| Yes       | 131       | 42.95%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| ASUSTek Computer            | 64        | 21.69%  |
| Hewlett-Packard             | 50        | 16.95%  |
| MSI                         | 30        | 10.17%  |
| Gigabyte Technology         | 28        | 9.49%   |
| Lenovo                      | 27        | 9.15%   |
| Dell                        | 27        | 9.15%   |
| Acer                        | 20        | 6.78%   |
| Unknown                     | 9         | 3.05%   |
| ASRock                      | 7         | 2.37%   |
| Intel                       | 5         | 1.69%   |
| Notebook                    | 4         | 1.36%   |
| Biostar                     | 4         | 1.36%   |
| Toshiba                     | 3         | 1.02%   |
| OEM                         | 3         | 1.02%   |
| Foxconn                     | 3         | 1.02%   |
| Raspberry Pi Foundation     | 2         | 0.68%   |
| win element                 | 1         | 0.34%   |
| Timi                        | 1         | 0.34%   |
| SYS                         | 1         | 0.34%   |
| Samsung Electronics         | 1         | 0.34%   |
| I-Life Digital Technologies | 1         | 0.34%   |
| HUAWEI                      | 1         | 0.34%   |
| Fujitsu                     | 1         | 0.34%   |
| Daffodil Computers          | 1         | 0.34%   |
| Apple                       | 1         | 0.34%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Unknown                                               | 11        | 3.73%   |
| MSI MS-7C52                                           | 6         | 2.03%   |
| HP ProBook 450 G4                                     | 5         | 1.69%   |
| HP Notebook                                           | 4         | 1.36%   |
| MSI Modern 15 A5M                                     | 3         | 1.02%   |
| Gigabyte B250M-HD3                                    | 3         | 1.02%   |
| ASUS VivoBook_ASUSLaptop X530FN_S530FN                | 3         | 1.02%   |
| ASUS All Series                                       | 3         | 1.02%   |
| OEM Intel H81                                         | 2         | 0.68%   |
| MSI MS-7B89                                           | 2         | 0.68%   |
| MSI MS-7788                                           | 2         | 0.68%   |
| MSI MS-7668                                           | 2         | 0.68%   |
| MSI Modern 14 B10MW                                   | 2         | 0.68%   |
| Intel DG41RQ AAE54511-203                             | 2         | 0.68%   |
| HP ProBook 4540s                                      | 2         | 0.68%   |
| HP ProBook 450 G2                                     | 2         | 0.68%   |
| HP ProBook 440 G8 Notebook PC                         | 2         | 0.68%   |
| HP EliteBook 840 G3                                   | 2         | 0.68%   |
| HP 15                                                 | 2         | 0.68%   |
| HP 14                                                 | 2         | 0.68%   |
| Gigabyte H61M-S2PV                                    | 2         | 0.68%   |
| Dell Inspiron 3442                                    | 2         | 0.68%   |
| ASUS X556UQK                                          | 2         | 0.68%   |
| ASUS X510UQ                                           | 2         | 0.68%   |
| ASUS VivoBook_ASUSLaptop X531FL_S531FL                | 2         | 0.68%   |
| ASUS VivoBook_ASUSLaptop X530FA_S530FA                | 2         | 0.68%   |
| ASUS VivoBook_ASUSLaptop X509JA_X509JA                | 2         | 0.68%   |
| ASUS VivoBook_ASUSLaptop X509DA                       | 2         | 0.68%   |
| ASUS VivoBook 14_ASUS Laptop X407UA                   | 2         | 0.68%   |
| ASUS P453UA                                           | 2         | 0.68%   |
| Acer Nitro AN515-43                                   | 2         | 0.68%   |
| win element MoreFine S500+                            | 1         | 0.34%   |
| Toshiba Satellite Pro L510                            | 1         | 0.34%   |
| Toshiba Satellite L645                                | 1         | 0.34%   |
| Toshiba Satellite C660                                | 1         | 0.34%   |
| Timi Mi NoteBook Pro                                  | 1         | 0.34%   |
| SYS H310CH5-TI2                                       | 1         | 0.34%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.34%   |
| RPi Raspberry Pi 4 Model B Rev 1.5                    | 1         | 0.34%   |
| RPi Raspberry Pi 4 Model B Rev 1.2                    | 1         | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| ASUS VivoBook        | 24        | 8.14%   |
| HP ProBook           | 19        | 6.44%   |
| Acer Aspire          | 15        | 5.08%   |
| Dell Inspiron        | 13        | 4.41%   |
| Lenovo IdeaPad       | 12        | 4.07%   |
| Unknown              | 11        | 3.73%   |
| Lenovo ThinkPad      | 9         | 3.05%   |
| Dell Latitude        | 8         | 2.71%   |
| HP EliteBook         | 7         | 2.37%   |
| MSI MS-7C52          | 6         | 2.03%   |
| MSI Modern           | 5         | 1.69%   |
| HP Notebook          | 4         | 1.36%   |
| ASUS TUF             | 4         | 1.36%   |
| Toshiba Satellite    | 3         | 1.02%   |
| HP Pavilion          | 3         | 1.02%   |
| HP ENVY              | 3         | 1.02%   |
| HP 15                | 3         | 1.02%   |
| Gigabyte B250M-HD3   | 3         | 1.02%   |
| ASUS All             | 3         | 1.02%   |
| Acer Nitro           | 3         | 1.02%   |
| RPi Raspberry        | 2         | 0.68%   |
| OEM Intel            | 2         | 0.68%   |
| MSI MS-7B89          | 2         | 0.68%   |
| MSI MS-7788          | 2         | 0.68%   |
| MSI MS-7668          | 2         | 0.68%   |
| Intel DG41RQ         | 2         | 0.68%   |
| HP Laptop            | 2         | 0.68%   |
| HP Compaq            | 2         | 0.68%   |
| HP 14                | 2         | 0.68%   |
| Gigabyte H61M-S2PV   | 2         | 0.68%   |
| Dell XPS             | 2         | 0.68%   |
| Dell Vostro          | 2         | 0.68%   |
| ASUS ZenBook         | 2         | 0.68%   |
| ASUS X556UQK         | 2         | 0.68%   |
| ASUS X510UQ          | 2         | 0.68%   |
| ASUS P453UA          | 2         | 0.68%   |
| Acer TravelMate      | 2         | 0.68%   |
| win element MoreFine | 1         | 0.34%   |
| Timi Mi              | 1         | 0.34%   |
| SYS H310CH5-TI2      | 1         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2016    | 36        | 12.2%   |
| 2019    | 32        | 10.85%  |
| 2018    | 32        | 10.85%  |
| 2017    | 28        | 9.49%   |
| 2021    | 26        | 8.81%   |
| 2012    | 22        | 7.46%   |
| 2015    | 21        | 7.12%   |
| 2020    | 20        | 6.78%   |
| 2014    | 19        | 6.44%   |
| 2013    | 18        | 6.1%    |
| 2011    | 12        | 4.07%   |
| 2010    | 12        | 4.07%   |
| 2009    | 7         | 2.37%   |
| 2022    | 4         | 1.36%   |
| 2008    | 3         | 1.02%   |
| Unknown | 3         | 1.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 190       | 64.41%  |
| Desktop        | 96        | 32.54%  |
| Convertible    | 4         | 1.36%   |
| System on chip | 2         | 0.68%   |
| Phone          | 1         | 0.34%   |
| Tablet         | 1         | 0.34%   |
| Mini pc        | 1         | 0.34%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 274       | 91.03%  |
| Enabled  | 27        | 8.97%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 295       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 107       | 35.55%  |
| 3.01-4.0    | 72        | 23.92%  |
| 8.01-16.0   | 58        | 19.27%  |
| 16.01-24.0  | 38        | 12.62%  |
| 1.01-2.0    | 14        | 4.65%   |
| 32.01-64.0  | 7         | 2.33%   |
| 2.01-3.0    | 3         | 1%      |
| 64.01-256.0 | 1         | 0.33%   |
| 0.51-1.0    | 1         | 0.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 116       | 34.83%  |
| 2.01-3.0   | 106       | 31.83%  |
| 3.01-4.0   | 52        | 15.62%  |
| 4.01-8.0   | 37        | 11.11%  |
| 0.51-1.0   | 13        | 3.9%    |
| 8.01-16.0  | 4         | 1.2%    |
| 0.01-0.5   | 4         | 1.2%    |
| 16.01-24.0 | 1         | 0.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 184       | 61.13%  |
| 2      | 101       | 33.55%  |
| 3      | 13        | 4.32%   |
| 5      | 1         | 0.33%   |
| 4      | 1         | 0.33%   |
| 0      | 1         | 0.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 211       | 70.81%  |
| Yes       | 87        | 29.19%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 243       | 81.82%  |
| No        | 54        | 18.18%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 228       | 76.25%  |
| No        | 71        | 23.75%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 181       | 60.13%  |
| No        | 120       | 39.87%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country    | Computers | Percent |
|------------|-----------|---------|
| Bangladesh | 295       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Dhaka             | 186       | 59.81%  |
| Chittagong        | 19        | 6.11%   |
| Rajshahi          | 9         | 2.89%   |
| Tongi             | 8         | 2.57%   |
| Jessore           | 8         | 2.57%   |
| Narayanganj       | 6         | 1.93%   |
| Khulna            | 6         | 1.93%   |
| Comilla           | 5         | 1.61%   |
| Mirpur            | 4         | 1.29%   |
| Azimpur           | 4         | 1.29%   |
| Wari              | 3         | 0.96%   |
| Sylhet            | 3         | 0.96%   |
| Pabna             | 3         | 0.96%   |
| Sherpur           | 2         | 0.64%   |
| Savar Upazila     | 2         | 0.64%   |
| Paltan            | 2         | 0.64%   |
| Nilphamari        | 2         | 0.64%   |
| Narail            | 2         | 0.64%   |
| Mymensingh        | 2         | 0.64%   |
| Feni              | 2         | 0.64%   |
| Dinajpur          | 2         | 0.64%   |
| Bogra             | 2         | 0.64%   |
| Uttara            | 1         | 0.32%   |
| Tejgaon           | 1         | 0.32%   |
| Srimangal         | 1         | 0.32%   |
| Sirajganj         | 1         | 0.32%   |
| Senbag            | 1         | 0.32%   |
| Rangpur City      | 1         | 0.32%   |
| Pirganj           | 1         | 0.32%   |
| Patnitala         | 1         | 0.32%   |
| Pabna Sadar       | 1         | 0.32%   |
| NДЃrДЃyanganj | 1         | 0.32%   |
| Natore            | 1         | 0.32%   |
| Narsingdi         | 1         | 0.32%   |
| Nalitabari        | 1         | 0.32%   |
| Nāgarpur         | 1         | 0.32%   |
| LДЃkshДЃm     | 1         | 0.32%   |
| Lalpur            | 1         | 0.32%   |
| Khilgaon          | 1         | 0.32%   |
| Jamalpur          | 1         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 74        | 102    | 18.05%  |
| Seagate                        | 69        | 86     | 16.83%  |
| Toshiba                        | 59        | 73     | 14.39%  |
| Samsung Electronics            | 34        | 49     | 8.29%   |
| Transcend                      | 24        | 25     | 5.85%   |
| Hitachi                        | 15        | 20     | 3.66%   |
| HGST                           | 12        | 12     | 2.93%   |
| SanDisk                        | 10        | 10     | 2.44%   |
| Intel                          | 10        | 12     | 2.44%   |
| A-DATA Technology              | 9         | 10     | 2.2%    |
| Silicon Motion                 | 7         | 17     | 1.71%   |
| Micron Technology              | 7         | 7      | 1.71%   |
| Kingston                       | 7         | 9      | 1.71%   |
| Teutons                        | 6         | 10     | 1.46%   |
| Corsair                        | 5         | 7      | 1.22%   |
| Unknown                        | 4         | 5      | 0.98%   |
| SK hynix                       | 4         | 4      | 0.98%   |
| Hewlett-Packard                | 4         | 4      | 0.98%   |
| Team                           | 3         | 3      | 0.73%   |
| PNY                            | 3         | 3      | 0.73%   |
| Phison Electronics             | 3         | 4      | 0.73%   |
| Phison                         | 3         | 3      | 0.73%   |
| Apacer                         | 3         | 4      | 0.73%   |
| TwinMOS                        | 2         | 2      | 0.49%   |
| Ramsta                         | 2         | 2      | 0.49%   |
| KingSpec                       | 2         | 2      | 0.49%   |
| HS-SSD-E100                    | 2         | 3      | 0.49%   |
| Gigabyte Technology            | 2         | 3      | 0.49%   |
| Crucial                        | 2         | 3      | 0.49%   |
| China                          | 2         | 2      | 0.49%   |
| Unknown                        | 2         | 2      | 0.49%   |
| WDC WDS4                       | 1         | 1      | 0.24%   |
| WALTON                         | 1         | 2      | 0.24%   |
| Solid State Storage Technology | 1         | 1      | 0.24%   |
| Shenzhen Longsys Electronics   | 1         | 1      | 0.24%   |
| Realtek Semiconductor          | 1         | 1      | 0.24%   |
| Realtek                        | 1         | 1      | 0.24%   |
| Patriot                        | 1         | 1      | 0.24%   |
| OCZ                            | 1         | 1      | 0.24%   |
| MAXIO Technology (Hangzhou)    | 1         | 1      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 21        | 4.93%   |
| Toshiba MQ04ABF100 1TB                              | 15        | 3.52%   |
| Toshiba DT01ACA100 1TB                              | 10        | 2.35%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                    | 8         | 1.88%   |
| Seagate ST1000DM010-2EP102 1TB                      | 8         | 1.88%   |
| Toshiba HDWD110 1TB                                 | 7         | 1.64%   |
| Seagate ST500DM002-1BD142 500GB                     | 7         | 1.64%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 6         | 1.41%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 5         | 1.17%   |
| WDC WD10JPVX-60JC3T0 1TB                            | 5         | 1.17%   |
| Toshiba MQ01ABD100 1TB                              | 5         | 1.17%   |
| Seagate ST500LT012-1DG142 500GB                     | 5         | 1.17%   |
| A-DATA SU650 240GB SSD                              | 5         | 1.17%   |
| WDC WD10SPZX-60Z10T0 1TB                            | 4         | 0.94%   |
| Transcend TS256GSSD230S 256GB                       | 4         | 0.94%   |
| SanDisk NVMe SSD Drive 512GB                        | 4         | 0.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 4         | 0.94%   |
| Intel NVMe SSD Drive 512GB                          | 4         | 0.94%   |
| HGST HTS541010A9E680 1TB                            | 4         | 0.94%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 3         | 0.7%    |
| WDC WD5000AAKX-001CA0 500GB                         | 3         | 0.7%    |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 3         | 0.7%    |
| WDC WD10JPVX-60JC3T1 1TB                            | 3         | 0.7%    |
| WDC WD10EZEX-60WN4A0 1TB                            | 3         | 0.7%    |
| Transcend TS128GSSD370S 128GB                       | 3         | 0.7%    |
| Transcend TS120GSSD220S 120GB                       | 3         | 0.7%    |
| Transcend TS120GMTS420S 120GB SSD                   | 3         | 0.7%    |
| Toshiba DT01ACA200 2TB                              | 3         | 0.7%    |
| Silicon Motion SM2262/SM2262EN SSD Controller 500GB | 3         | 0.7%    |
| Seagate ST500LT012-9WS142 500GB                     | 3         | 0.7%    |
| Seagate ST1000LM049-2GH172 1TB                      | 3         | 0.7%    |
| Samsung SSD 860 EVO 500GB                           | 3         | 0.7%    |
| Samsung HD502HJ 500GB                               | 3         | 0.7%    |
| Intel SSD 660P Series 1024GB                        | 3         | 0.7%    |
| HGST HTS545050A7E680 500GB                          | 3         | 0.7%    |
| Corsair Force MP510 240GB                           | 3         | 0.7%    |
| WDC WD40PURX-64N96Y0 4TB                            | 2         | 0.47%   |
| WDC WD10SPZX-24Z10T0 1TB                            | 2         | 0.47%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 2         | 0.47%   |
| WDC WD10EZEX-22MFCA0 1TB                            | 2         | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 69        | 86     | 33.01%  |
| Toshiba             | 52        | 65     | 24.88%  |
| WDC                 | 48        | 64     | 22.97%  |
| Hitachi             | 15        | 20     | 7.18%   |
| Samsung Electronics | 13        | 21     | 6.22%   |
| HGST                | 12        | 12     | 5.74%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 22        | 27     | 18.33%  |
| Transcend           | 21        | 22     | 17.5%   |
| Samsung Electronics | 10        | 13     | 8.33%   |
| A-DATA Technology   | 9         | 10     | 7.5%    |
| Teutons             | 6         | 10     | 5%      |
| Micron Technology   | 6         | 6      | 5%      |
| SanDisk             | 5         | 5      | 4.17%   |
| Hewlett-Packard     | 4         | 4      | 3.33%   |
| Toshiba             | 3         | 4      | 2.5%    |
| PNY                 | 3         | 3      | 2.5%    |
| Apacer              | 3         | 4      | 2.5%    |
| TwinMOS             | 2         | 2      | 1.67%   |
| Team                | 2         | 2      | 1.67%   |
| Ramsta              | 2         | 2      | 1.67%   |
| KingSpec            | 2         | 2      | 1.67%   |
| HS-SSD-E100         | 2         | 2      | 1.67%   |
| Gigabyte Technology | 2         | 3      | 1.67%   |
| Crucial             | 2         | 3      | 1.67%   |
| Corsair             | 2         | 3      | 1.67%   |
| China               | 2         | 2      | 1.67%   |
| WDC WDS4            | 1         | 1      | 0.83%   |
| WALTON              | 1         | 2      | 0.83%   |
| SK hynix            | 1         | 1      | 0.83%   |
| Patriot             | 1         | 1      | 0.83%   |
| OCZ                 | 1         | 1      | 0.83%   |
| Kingston            | 1         | 1      | 0.83%   |
| Intel               | 1         | 1      | 0.83%   |
| GeIL                | 1         | 1      | 0.83%   |
| GAMER               | 1         | 1      | 0.83%   |
| ASMT                | 1         | 1      | 0.83%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 199       | 268    | 50.38%  |
| SSD     | 117       | 140    | 29.62%  |
| NVMe    | 67        | 98     | 16.96%  |
| Unknown | 9         | 9      | 2.28%   |
| MMC     | 3         | 4      | 0.76%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 250       | 413    | 76.92%  |
| NVMe | 67        | 97     | 20.62%  |
| SAS  | 5         | 5      | 1.54%   |
| MMC  | 3         | 4      | 0.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 162       | 224    | 53.29%  |
| 0.51-1.0   | 123       | 159    | 40.46%  |
| 1.01-2.0   | 14        | 16     | 4.61%   |
| 3.01-4.0   | 2         | 3      | 0.66%   |
| 4.01-10.0  | 2         | 2      | 0.66%   |
| 2.01-3.0   | 1         | 4      | 0.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 90        | 28.3%   |
| 251-500        | 68        | 21.38%  |
| 501-1000       | 59        | 18.55%  |
| 1001-2000      | 27        | 8.49%   |
| 51-100         | 27        | 8.49%   |
| 21-50          | 21        | 6.6%    |
| 1-20           | 14        | 4.4%    |
| Unknown        | 7         | 2.2%    |
| More than 3000 | 5         | 1.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 110       | 33.74%  |
| 21-50          | 68        | 20.86%  |
| 51-100         | 53        | 16.26%  |
| 101-250        | 50        | 15.34%  |
| 251-500        | 19        | 5.83%   |
| 501-1000       | 13        | 3.99%   |
| Unknown        | 7         | 2.15%   |
| 1001-2000      | 4         | 1.23%   |
| More than 3000 | 2         | 0.61%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                              | 3         | 5      | 6.98%   |
| Toshiba DT01ACA100 1TB                              | 2         | 2      | 4.65%   |
| Seagate ST500DM002-1BD142 500GB                     | 2         | 2      | 4.65%   |
| HGST HTS545050A7E680 500GB                          | 2         | 2      | 4.65%   |
| HGST HTS541010A9E680 1TB                            | 2         | 2      | 4.65%   |
| WDC WD5000LPCX-22VHAT0 500GB                        | 1         | 1      | 2.33%   |
| WDC WD5000BPVT-22HXZT3 500GB                        | 1         | 1      | 2.33%   |
| WDC WD5000AAKX-001CA0 500GB                         | 1         | 1      | 2.33%   |
| WDC WD10SPZX-24Z10T0 1TB                            | 1         | 1      | 2.33%   |
| WDC WD10JPVX-60JC3T0 1TB                            | 1         | 2      | 2.33%   |
| WDC WD10JPVT-00MS8T0 1TB                            | 1         | 1      | 2.33%   |
| WDC WD10EZEX-60WN4A0 1TB                            | 1         | 1      | 2.33%   |
| WDC WD10EZEX-22MFCA0 1TB                            | 1         | 1      | 2.33%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 1         | 1      | 2.33%   |
| Toshiba MQ01ABD050 500GB                            | 1         | 1      | 2.33%   |
| Toshiba HDWD110 1TB                                 | 1         | 1      | 2.33%   |
| Toshiba DT01ACA200 2TB                              | 1         | 1      | 2.33%   |
| SK hynix HFS256G3AMNB-2200A 256GB SSD               | 1         | 1      | 2.33%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 500GB | 1         | 1      | 2.33%   |
| Seagate ST9500325AS 500GB                           | 1         | 1      | 2.33%   |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 1      | 2.33%   |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 1      | 2.33%   |
| Seagate ST3500418AS 500GB                           | 1         | 1      | 2.33%   |
| Seagate ST320LT012-9WS14C 320GB                     | 1         | 1      | 2.33%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                  | 1         | 1      | 2.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 2.33%   |
| Samsung Electronics HM160HI 160GB                   | 1         | 1      | 2.33%   |
| Samsung Electronics HD161HJ 160GB                   | 1         | 2      | 2.33%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD      | 1         | 1      | 2.33%   |
| Intel SSDSCKKW240H6 240GB                           | 1         | 1      | 2.33%   |
| HS-SSD-E100 SSD 128G                                | 1         | 1      | 2.33%   |
| Hitachi HTS545025B9A300 250GB                       | 1         | 1      | 2.33%   |
| Hitachi HDT725050VLA380 500GB                       | 1         | 1      | 2.33%   |
| Hitachi HDT721032SLA360 320GB                       | 1         | 2      | 2.33%   |
| HGST HTS545050A7E380 500GB                          | 1         | 1      | 2.33%   |
| Hewlett-Packard SSD S600 240GB                      | 1         | 1      | 2.33%   |
| A-DATA Technology SU650 240GB SSD                   | 1         | 2      | 2.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 10     | 20.93%  |
| Seagate             | 9         | 9      | 20.93%  |
| Toshiba             | 8         | 10     | 18.6%   |
| HGST                | 5         | 5      | 11.63%  |
| Hitachi             | 3         | 4      | 6.98%   |
| Samsung Electronics | 2         | 3      | 4.65%   |
| SK hynix            | 1         | 1      | 2.33%   |
| Silicon Motion      | 1         | 1      | 2.33%   |
| Micron Technology   | 1         | 1      | 2.33%   |
| Intel               | 1         | 1      | 2.33%   |
| HS-SSD-E100         | 1         | 1      | 2.33%   |
| Hewlett-Packard     | 1         | 1      | 2.33%   |
| A-DATA Technology   | 1         | 2      | 2.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 10     | 25%     |
| Seagate             | 9         | 9      | 25%     |
| Toshiba             | 8         | 10     | 22.22%  |
| HGST                | 5         | 5      | 13.89%  |
| Hitachi             | 3         | 4      | 8.33%   |
| Samsung Electronics | 2         | 3      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 35        | 41     | 83.33%  |
| SSD  | 6         | 7      | 14.29%  |
| NVMe | 1         | 1      | 2.38%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                  | Computers | Drives | Percent |
|------------------------|-----------|--------|---------|
| Toshiba DT01ACA200 2TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 175       | 290    | 53.52%  |
| Works    | 109       | 179    | 33.33%  |
| Malfunc  | 42        | 49     | 12.84%  |
| Failed   | 1         | 1      | 0.31%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 240       | 69.16%  |
| AMD                            | 38        | 10.95%  |
| Samsung Electronics            | 12        | 3.46%   |
| SanDisk                        | 11        | 3.17%   |
| Phison Electronics             | 9         | 2.59%   |
| Silicon Motion                 | 7         | 2.02%   |
| Kingston Technology Company    | 6         | 1.73%   |
| SK hynix                       | 3         | 0.86%   |
| Shenzhen Longsys Electronics   | 3         | 0.86%   |
| Marvell Technology Group       | 3         | 0.86%   |
| KIOXIA                         | 3         | 0.86%   |
| Transcend                      | 2         | 0.58%   |
| Toshiba America Info Systems   | 2         | 0.58%   |
| ASMedia Technology             | 2         | 0.58%   |
| VIA Technologies               | 1         | 0.29%   |
| Solid State Storage Technology | 1         | 0.29%   |
| Realtek Semiconductor          | 1         | 0.29%   |
| Micron Technology              | 1         | 0.29%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.29%   |
| Biwin Storage Technology       | 1         | 0.29%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 56        | 13.86%  |
| AMD FCH SATA Controller [AHCI mode]                                                     | 30        | 7.43%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 15        | 3.71%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 13        | 3.22%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 12        | 2.97%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 12        | 2.97%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 12        | 2.97%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 11        | 2.72%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 11        | 2.72%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 10        | 2.48%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 10        | 2.48%   |
| AMD 400 Series Chipset SATA Controller                                                  | 10        | 2.48%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 9         | 2.23%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 9         | 2.23%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 8         | 1.98%   |
| Intel SSD 660P Series                                                                   | 7         | 1.73%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6         | 1.49%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 6         | 1.49%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 6         | 1.49%   |
| Phison PS5013 E13 NVMe Controller                                                       | 5         | 1.24%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5         | 1.24%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 5         | 1.24%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 5         | 1.24%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 5         | 1.24%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 4         | 0.99%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 4         | 0.99%   |
| Phison E12 NVMe Controller                                                              | 4         | 0.99%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                           | 4         | 0.99%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 4         | 0.99%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 4         | 0.99%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4         | 0.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4         | 0.99%   |
| AMD FCH SATA Controller D                                                               | 4         | 0.99%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 3         | 0.74%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 3         | 0.74%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3         | 0.74%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                              | 3         | 0.74%   |
| Intel SATA Controller [RAID mode]                                                       | 3         | 0.74%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 3         | 0.74%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3         | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 223       | 63.17%  |
| NVMe | 68        | 19.26%  |
| IDE  | 33        | 9.35%   |
| RAID | 29        | 8.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 249       | 84.41%  |
| AMD    | 43        | 14.58%  |
| ARM    | 3         | 1.02%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 14        | 4.73%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 11        | 3.72%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 9         | 3.04%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 8         | 2.7%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 2.03%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 2.03%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 1.69%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 5         | 1.69%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 1.35%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 4         | 1.35%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 1.35%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 4         | 1.35%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 1.35%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 4         | 1.35%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 1.35%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 4         | 1.35%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 4         | 1.35%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 4         | 1.35%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 4         | 1.35%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 4         | 1.35%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 4         | 1.35%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 4         | 1.35%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 1.01%   |
| Intel Pentium CPU G630 @ 2.70GHz              | 3         | 1.01%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 1.01%   |
| Intel Core i5-7500 CPU @ 3.40GHz              | 3         | 1.01%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.01%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 3         | 1.01%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 3         | 1.01%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 3         | 1.01%   |
| AMD Ryzen 5 3600 6-Core Processor             | 3         | 1.01%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 3         | 1.01%   |
| Intel Xeon CPU X3440 @ 2.53GHz                | 2         | 0.68%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz   | 2         | 0.68%   |
| Intel Pentium CPU G3260 @ 3.30GHz             | 2         | 0.68%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.68%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 2         | 0.68%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 2         | 0.68%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 0.68%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 105       | 35.59%  |
| Intel Core i3           | 59        | 20%     |
| Other                   | 22        | 7.46%   |
| Intel Core i7           | 21        | 7.12%   |
| AMD Ryzen 5             | 21        | 7.12%   |
| Intel Pentium           | 14        | 4.75%   |
| Intel Core 2 Duo        | 9         | 3.05%   |
| Intel Celeron           | 7         | 2.37%   |
| AMD Ryzen 7             | 7         | 2.37%   |
| AMD Ryzen 3             | 7         | 2.37%   |
| Intel Pentium Dual-Core | 5         | 1.69%   |
| Intel Xeon              | 3         | 1.02%   |
| Intel Core 2 Quad       | 2         | 0.68%   |
| Intel Atom              | 2         | 0.68%   |
| AMD Ryzen 9             | 2         | 0.68%   |
| AMD A8                  | 2         | 0.68%   |
| Intel Pentium Gold      | 1         | 0.34%   |
| Intel Celeron Dual-Core | 1         | 0.34%   |
| ARM AArch64             | 1         | 0.34%   |
| AMD FX                  | 1         | 0.34%   |
| AMD E2                  | 1         | 0.34%   |
| AMD E                   | 1         | 0.34%   |
| AMD A4                  | 1         | 0.34%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 162       | 54.73%  |
| 4       | 95        | 32.09%  |
| 6       | 22        | 7.43%   |
| 8       | 10        | 3.38%   |
| 10      | 2         | 0.68%   |
| 1       | 2         | 0.68%   |
| 16      | 1         | 0.34%   |
| 12      | 1         | 0.34%   |
| Unknown | 1         | 0.34%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 294       | 99.66%  |
| Unknown | 1         | 0.34%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 218       | 73.65%  |
| 1       | 77        | 26.01%  |
| Unknown | 1         | 0.34%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 294       | 99.66%  |
| Unknown        | 1         | 0.34%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 93        | 29.81%  |
| 0x806e9    | 24        | 7.69%   |
| 0x806ea    | 15        | 4.81%   |
| 0x306a9    | 15        | 4.81%   |
| 0x206a7    | 13        | 4.17%   |
| 0x406e3    | 12        | 3.85%   |
| 0x40651    | 10        | 3.21%   |
| 0x306d4    | 10        | 3.21%   |
| 0x806c1    | 9         | 2.88%   |
| 0x306c3    | 9         | 2.88%   |
| 0x1067a    | 9         | 2.88%   |
| 0x08108109 | 9         | 2.88%   |
| 0x806ec    | 7         | 2.24%   |
| 0x806eb    | 7         | 2.24%   |
| 0x906e9    | 6         | 1.92%   |
| 0x706e5    | 5         | 1.6%    |
| 0x406c4    | 4         | 1.28%   |
| 0x08701021 | 4         | 1.28%   |
| 0x506e3    | 3         | 0.96%   |
| 0x20655    | 3         | 0.96%   |
| 0x106e5    | 3         | 0.96%   |
| 0x10676    | 3         | 0.96%   |
| 0x0a50000c | 3         | 0.96%   |
| 0x08108102 | 3         | 0.96%   |
| 0xa0652    | 2         | 0.64%   |
| 0x906eb    | 2         | 0.64%   |
| 0x906ea    | 2         | 0.64%   |
| 0x90672    | 2         | 0.64%   |
| 0x6fb      | 2         | 0.64%   |
| 0x20652    | 2         | 0.64%   |
| 0x08608103 | 2         | 0.64%   |
| 0x0810100b | 2         | 0.64%   |
| 0xa0653    | 1         | 0.32%   |
| 0x906a3    | 1         | 0.32%   |
| 0x806d1    | 1         | 0.32%   |
| 0x506c9    | 1         | 0.32%   |
| 0x50654    | 1         | 0.32%   |
| 0x406c3    | 1         | 0.32%   |
| 0x30678    | 1         | 0.32%   |
| 0x30661    | 1         | 0.32%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 81        | 27.36%  |
| Haswell          | 25        | 8.45%   |
| Skylake          | 22        | 7.43%   |
| IvyBridge        | 20        | 6.76%   |
| SandyBridge      | 19        | 6.42%   |
| Zen+             | 15        | 5.07%   |
| TigerLake        | 14        | 4.73%   |
| Penryn           | 14        | 4.73%   |
| Broadwell        | 13        | 4.39%   |
| Zen 3            | 8         | 2.7%    |
| Zen 2            | 8         | 2.7%    |
| CometLake        | 8         | 2.7%    |
| Silvermont       | 7         | 2.36%   |
| IceLake          | 6         | 2.03%   |
| Unknown          | 6         | 2.03%   |
| Westmere         | 5         | 1.69%   |
| Core             | 5         | 1.69%   |
| Alderlake Hybrid | 5         | 1.69%   |
| Zen              | 3         | 1.01%   |
| Nehalem          | 3         | 1.01%   |
| Piledriver       | 2         | 0.68%   |
| Excavator        | 2         | 0.68%   |
| Bonnell          | 2         | 0.68%   |
| Puma             | 1         | 0.34%   |
| Goldmont         | 1         | 0.34%   |
| Bobcat           | 1         | 0.34%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 231       | 65.81%  |
| Nvidia | 69        | 19.66%  |
| AMD    | 51        | 14.53%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                    | 32        | 8.99%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17        | 4.78%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 16        | 4.49%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 15        | 4.21%   |
| Intel UHD Graphics 620                                                                   | 15        | 4.21%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 14        | 3.93%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 13        | 3.65%   |
| Intel HD Graphics 5500                                                                   | 12        | 3.37%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 3.37%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 3.09%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 8         | 2.25%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 8         | 2.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 7         | 1.97%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7         | 1.97%   |
| Intel HD Graphics 630                                                                    | 7         | 1.97%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 6         | 1.69%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 6         | 1.69%   |
| Nvidia GP108M [GeForce MX150]                                                            | 5         | 1.4%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 1.4%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 1.4%    |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 1.4%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 1.4%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 5         | 1.4%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.4%    |
| Nvidia GP108M [GeForce MX250]                                                            | 4         | 1.12%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.12%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 4         | 1.12%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 1.12%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 0.84%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.84%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 0.84%   |
| AMD Lucienne                                                                             | 3         | 0.84%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 3         | 0.84%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.56%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 2         | 0.56%   |
| Nvidia GT215 [GeForce GT 240]                                                            | 2         | 0.56%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 0.56%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.56%   |
| Intel HD Graphics 530                                                                    | 2         | 0.56%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 181       | 60.74%  |
| Intel + Nvidia | 41        | 13.76%  |
| 1 x AMD        | 35        | 11.74%  |
| 1 x Nvidia     | 22        | 7.38%   |
| Intel + AMD    | 6         | 2.01%   |
| AMD + Nvidia   | 6         | 2.01%   |
| 2 x AMD        | 4         | 1.34%   |
| Other          | 3         | 1.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 250       | 81.97%  |
| Proprietary | 43        | 14.1%   |
| Unknown     | 12        | 3.93%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 222       | 73.51%  |
| 1.01-2.0   | 38        | 12.58%  |
| 3.01-4.0   | 17        | 5.63%   |
| 0.01-0.5   | 10        | 3.31%   |
| 0.51-1.0   | 8         | 2.65%   |
| 7.01-8.0   | 5         | 1.66%   |
| 5.01-6.0   | 2         | 0.66%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 52        | 17.33%  |
| AU Optronics            | 47        | 15.67%  |
| Chimei Innolux          | 38        | 12.67%  |
| LG Display              | 34        | 11.33%  |
| Samsung Electronics     | 30        | 10%     |
| Dell                    | 23        | 7.67%   |
| Hewlett-Packard         | 17        | 5.67%   |
| Goldstar                | 16        | 5.33%   |
| ViewSonic               | 5         | 1.67%   |
| PANDA                   | 5         | 1.67%   |
| Philips                 | 3         | 1%      |
| Chi Mei Optoelectronics | 3         | 1%      |
| ASUSTek Computer        | 3         | 1%      |
| Ancor Communications    | 3         | 1%      |
| Sony                    | 2         | 0.67%   |
| MSI                     | 2         | 0.67%   |
| LG Electronics          | 2         | 0.67%   |
| ___                     | 1         | 0.33%   |
| UTV                     | 1         | 0.33%   |
| Unknown                 | 1         | 0.33%   |
| Sharp                   | 1         | 0.33%   |
| QXS                     | 1         | 0.33%   |
| LLL                     | 1         | 0.33%   |
| IDS                     | 1         | 0.33%   |
| HYU                     | 1         | 0.33%   |
| HUYINIUDA               | 1         | 0.33%   |
| HUAWEI                  | 1         | 0.33%   |
| FSR                     | 1         | 0.33%   |
| CND                     | 1         | 0.33%   |
| CHR                     | 1         | 0.33%   |
| Apple                   | 1         | 0.33%   |
| AOC                     | 1         | 0.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 10        | 3.24%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 7         | 2.27%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 6         | 1.94%   |
| Samsung Electronics S19F350 SAM0D46 1366x768 410x230mm 18.5-inch         | 5         | 1.62%   |
| Hewlett-Packard 22fw HPN3541 1920x1080 476x268mm 21.5-inch               | 5         | 1.62%   |
| Dell SE2219H DELF10F 1920x1080 476x268mm 21.5-inch                       | 4         | 1.29%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 4         | 1.29%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 3         | 0.97%   |
| Hewlett-Packard V194 HWP3346 1366x768 410x230mm 18.5-inch                | 3         | 0.97%   |
| Dell S2240L DELD054 1920x1080 476x267mm 21.5-inch                        | 3         | 0.97%   |
| Dell S2218H DELD0B8 1920x1080 476x268mm 21.5-inch                        | 3         | 0.97%   |
| Dell E1916HV DELF06C 1366x768 409x230mm 18.5-inch                        | 3         | 0.97%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                    | 3         | 0.97%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 3         | 0.97%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch           | 3         | 0.97%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 3         | 0.97%   |
| Samsung Electronics SyncMaster SAM0472 1440x900 367x229mm 17.0-inch      | 2         | 0.65%   |
| Samsung Electronics S22R35x SAM103A 1920x1080 476x268mm 21.5-inch        | 2         | 0.65%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch             | 2         | 0.65%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch             | 2         | 0.65%   |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch              | 2         | 0.65%   |
| LG Display LCD Monitor LGD04C0 1366x768 309x174mm 14.0-inch              | 2         | 0.65%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 2         | 0.65%   |
| LG Display LCD Monitor LGD0466 1366x768 309x174mm 14.0-inch              | 2         | 0.65%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch              | 2         | 0.65%   |
| Hewlett-Packard v185w HWP2820 1366x768 410x230mm 18.5-inch               | 2         | 0.65%   |
| Hewlett-Packard 22f HPN3542 1920x1080 476x267mm 21.5-inch                | 2         | 0.65%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch                | 2         | 0.65%   |
| Dell D1918H DEL2005 1366x768 410x230mm 18.5-inch                         | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch         | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 309x174mm 14.0-inch          | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch          | 2         | 0.65%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 2         | 0.65%   |
| BOE LCD Monitor BOE07B4 1366x768 344x194mm 15.5-inch                     | 2         | 0.65%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 2         | 0.65%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 2         | 0.65%   |
| BOE LCD Monitor BOE0698 1366x768 309x173mm 13.9-inch                     | 2         | 0.65%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 124       | 42.91%  |
| 1366x768 (WXGA)   | 121       | 41.87%  |
| 3840x2160 (4K)    | 9         | 3.11%   |
| 1440x900 (WXGA+)  | 7         | 2.42%   |
| 1600x900 (HD+)    | 5         | 1.73%   |
| 1280x1024 (SXGA)  | 4         | 1.38%   |
| 2560x1600         | 2         | 0.69%   |
| 1920x1200 (WUXGA) | 2         | 0.69%   |
| 1280x800 (WXGA)   | 2         | 0.69%   |
| 1024x600          | 2         | 0.69%   |
| Unknown           | 2         | 0.69%   |
| 3840x2400         | 1         | 0.35%   |
| 3440x1440         | 1         | 0.35%   |
| 3360x1080         | 1         | 0.35%   |
| 2736x1824         | 1         | 0.35%   |
| 2726x768          | 1         | 0.35%   |
| 2560x1440 (QHD)   | 1         | 0.35%   |
| 2240x1400         | 1         | 0.35%   |
| 1360x768          | 1         | 0.35%   |
| 1024x768 (XGA)    | 1         | 0.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 93        | 30.9%   |
| 13      | 47        | 15.61%  |
| 21      | 42        | 13.95%  |
| 14      | 37        | 12.29%  |
| 18      | 27        | 8.97%   |
| 23      | 8         | 2.66%   |
| 12      | 7         | 2.33%   |
| Unknown | 7         | 2.33%   |
| 19      | 6         | 1.99%   |
| 17      | 5         | 1.66%   |
| 16      | 5         | 1.66%   |
| 24      | 4         | 1.33%   |
| 11      | 3         | 1%      |
| 72      | 2         | 0.66%   |
| 10      | 2         | 0.66%   |
| 84      | 1         | 0.33%   |
| 39      | 1         | 0.33%   |
| 34      | 1         | 0.33%   |
| 27      | 1         | 0.33%   |
| 26      | 1         | 0.33%   |
| 20      | 1         | 0.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 168       | 56.57%  |
| 401-500     | 77        | 25.93%  |
| 201-300     | 24        | 8.08%   |
| 501-600     | 9         | 3.03%   |
| 351-400     | 7         | 2.36%   |
| Unknown     | 7         | 2.36%   |
| 1501-2000   | 3         | 1.01%   |
| 801-900     | 1         | 0.34%   |
| 701-800     | 1         | 0.34%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 247       | 89.49%  |
| 16/10   | 15        | 5.43%   |
| Unknown | 6         | 2.17%   |
| 4/3     | 4         | 1.45%   |
| 5/4     | 2         | 0.72%   |
| 3/2     | 1         | 0.36%   |
| 21/9    | 1         | 0.36%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 92        | 30.67%  |
| 81-90          | 73        | 24.33%  |
| 201-250        | 39        | 13%     |
| 141-150        | 28        | 9.33%   |
| 151-200        | 19        | 6.33%   |
| 71-80          | 9         | 3%      |
| 61-70          | 7         | 2.33%   |
| Unknown        | 7         | 2.33%   |
| 111-120        | 5         | 1.67%   |
| 131-140        | 4         | 1.33%   |
| More than 1000 | 3         | 1%      |
| 51-60          | 3         | 1%      |
| 251-300        | 3         | 1%      |
| 41-50          | 2         | 0.67%   |
| 91-100         | 2         | 0.67%   |
| 351-500        | 1         | 0.33%   |
| 301-350        | 1         | 0.33%   |
| 121-130        | 1         | 0.33%   |
| 501-1000       | 1         | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 131       | 44.56%  |
| 121-160       | 88        | 29.93%  |
| 51-100        | 56        | 19.05%  |
| 161-240       | 7         | 2.38%   |
| Unknown       | 7         | 2.38%   |
| More than 240 | 3         | 1.02%   |
| 1-50          | 2         | 0.68%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 256       | 85.05%  |
| 2     | 31        | 10.3%   |
| 0     | 12        | 3.99%   |
| 3     | 2         | 0.66%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 210       | 47.95%  |
| Intel                             | 107       | 24.43%  |
| Qualcomm Atheros                  | 56        | 12.79%  |
| Ralink Technology                 | 16        | 3.65%   |
| Xiaomi                            | 10        | 2.28%   |
| TP-Link                           | 8         | 1.83%   |
| MediaTek                          | 7         | 1.6%    |
| Broadcom                          | 7         | 1.6%    |
| Ralink                            | 2         | 0.46%   |
| Qualcomm                          | 2         | 0.46%   |
| HMD Global                        | 2         | 0.46%   |
| D-Link                            | 2         | 0.46%   |
| ASIX Electronics                  | 2         | 0.46%   |
| Sundance Technology Inc / IC Plus | 1         | 0.23%   |
| Samsung Electronics               | 1         | 0.23%   |
| OPPO Electronics                  | 1         | 0.23%   |
| NetGear                           | 1         | 0.23%   |
| Dell                              | 1         | 0.23%   |
| Arduino SA                        | 1         | 0.23%   |
| AboCom Systems                    | 1         | 0.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 143       | 28.77%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 43        | 8.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 23        | 4.63%   |
| Intel Wireless 8265 / 8275                                        | 17        | 3.42%   |
| Ralink MT7601U Wireless Adapter                                   | 14        | 2.82%   |
| Intel Wi-Fi 6 AX201                                               | 13        | 2.62%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 13        | 2.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 12        | 2.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 9         | 1.81%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 8         | 1.61%   |
| Intel Wireless 3165                                               | 8         | 1.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 1.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 7         | 1.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 1.21%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5         | 1.01%   |
| Intel Wireless 8260                                               | 5         | 1.01%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 1.01%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 4         | 0.8%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 4         | 0.8%    |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 0.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 0.8%    |
| Intel Wireless 7265                                               | 4         | 0.8%    |
| Intel Wireless 7260                                               | 4         | 0.8%    |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 0.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 0.8%    |
| Xiaomi MediaTek MT7601U [MI WiFi]                                 | 3         | 0.6%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.6%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 3         | 0.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 0.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 0.6%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 3         | 0.6%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 0.6%    |
| Intel Wireless 3160                                               | 3         | 0.6%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.6%    |
| Intel Ethernet Controller I225-V                                  | 3         | 0.6%    |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.6%    |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 0.6%    |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 94        | 39.66%  |
| Qualcomm Atheros      | 53        | 22.36%  |
| Realtek Semiconductor | 46        | 19.41%  |
| Ralink Technology     | 16        | 6.75%   |
| TP-Link               | 7         | 2.95%   |
| MediaTek              | 6         | 2.53%   |
| Broadcom              | 5         | 2.11%   |
| Xiaomi                | 3         | 1.27%   |
| Ralink                | 2         | 0.84%   |
| D-Link                | 2         | 0.84%   |
| NetGear               | 1         | 0.42%   |
| Dell                  | 1         | 0.42%   |
| AboCom Systems        | 1         | 0.42%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 23        | 9.7%    |
| Intel Wireless 8265 / 8275                                     | 17        | 7.17%   |
| Ralink MT7601U Wireless Adapter                                | 14        | 5.91%   |
| Intel Wi-Fi 6 AX201                                            | 13        | 5.49%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 13        | 5.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 12        | 5.06%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 9         | 3.8%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 8         | 3.38%   |
| Intel Wireless 3165                                            | 8         | 3.38%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 7         | 2.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6         | 2.53%   |
| Intel Wireless 8260                                            | 5         | 2.11%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 4         | 1.69%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 4         | 1.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 1.69%   |
| Intel Wireless 7265                                            | 4         | 1.69%   |
| Intel Wireless 7260                                            | 4         | 1.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 1.69%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                              | 3         | 1.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 1.27%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 3         | 1.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3         | 1.27%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 3         | 1.27%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 3         | 1.27%   |
| Intel Wireless 3160                                            | 3         | 1.27%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 3         | 1.27%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 1.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 1.27%   |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 1.27%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 0.84%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)      | 2         | 0.84%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 0.84%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 0.84%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 0.84%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 0.84%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 0.84%   |
| TP-Link Archer T4U ver.3                                       | 1         | 0.42%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 0.42%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.42%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 1         | 0.42%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 194       | 76.08%  |
| Intel                             | 33        | 12.94%  |
| Xiaomi                            | 7         | 2.75%   |
| Qualcomm Atheros                  | 7         | 2.75%   |
| Broadcom                          | 3         | 1.18%   |
| Qualcomm                          | 2         | 0.78%   |
| HMD Global                        | 2         | 0.78%   |
| ASIX Electronics                  | 2         | 0.78%   |
| TP-Link                           | 1         | 0.39%   |
| Sundance Technology Inc / IC Plus | 1         | 0.39%   |
| Samsung Electronics               | 1         | 0.39%   |
| OPPO Electronics                  | 1         | 0.39%   |
| MediaTek                          | 1         | 0.39%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 143       | 55.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 43        | 16.6%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 3.09%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5         | 1.93%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 1.93%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 1.54%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 1.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 1.16%   |
| Intel Ethernet Controller I225-V                                  | 3         | 1.16%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.16%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.16%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2         | 0.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.77%   |
| Qualcomm Redmi Note 8                                             | 2         | 0.77%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.77%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 0.77%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.77%   |
| HMD Global Android                                                | 2         | 0.77%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 0.77%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.39%   |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet             | 1         | 0.39%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.39%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.39%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.39%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.39%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.39%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.39%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.39%   |
| OPPO 8                                                            | 1         | 0.39%   |
| MediaTek Infinix SMART 6 HD                                       | 1         | 0.39%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.39%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.39%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 1         | 0.39%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 0.39%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.39%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.39%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.39%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 242       | 51.49%  |
| WiFi     | 227       | 48.3%   |
| Modem    | 1         | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 183       | 62.03%  |
| Ethernet | 112       | 37.97%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 149       | 50.51%  |
| 2     | 140       | 47.46%  |
| 0     | 5         | 1.69%   |
| 3     | 1         | 0.34%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 292       | 98.98%  |
| Yes  | 3         | 1.02%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 79        | 43.17%  |
| IMC Networks                    | 26        | 14.21%  |
| Realtek Semiconductor           | 18        | 9.84%   |
| Qualcomm Atheros Communications | 15        | 8.2%    |
| Cambridge Silicon Radio         | 15        | 8.2%    |
| Lite-On Technology              | 11        | 6.01%   |
| Broadcom                        | 7         | 3.83%   |
| Foxconn / Hon Hai               | 4         | 2.19%   |
| MediaTek                        | 2         | 1.09%   |
| Toshiba                         | 1         | 0.55%   |
| Ralink                          | 1         | 0.55%   |
| Hewlett-Packard                 | 1         | 0.55%   |
| Foxconn International           | 1         | 0.55%   |
| Dell                            | 1         | 0.55%   |
| Unknown                         | 1         | 0.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 40        | 21.86%  |
| Intel AX201 Bluetooth                               | 15        | 8.2%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 15        | 8.2%    |
| IMC Networks Bluetooth Device                       | 14        | 7.65%   |
| Realtek Bluetooth Radio                             | 12        | 6.56%   |
| Intel Wireless-AC 3168 Bluetooth                    | 11        | 6.01%   |
| Qualcomm Atheros  Bluetooth Device                  | 9         | 4.92%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 9         | 4.92%   |
| IMC Networks Bluetooth Radio                        | 9         | 4.92%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 7         | 3.83%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 1.64%   |
| Lite-On Bluetooth Device                            | 3         | 1.64%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 1.09%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 1.09%   |
| MediaTek Wireless_Device                            | 2         | 1.09%   |
| Intel AX200 Bluetooth                               | 2         | 1.09%   |
| IMC Networks Wireless_Device                        | 2         | 1.09%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 1.09%   |
| Broadcom HP Portable SoftSailing                    | 2         | 1.09%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.09%   |
| Toshiba Bluetooth Radio                             | 1         | 0.55%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.55%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.55%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.55%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.55%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.55%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.55%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.55%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.55%   |
| Intel AX210 Bluetooth                               | 1         | 0.55%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.55%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.55%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.55%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 1         | 0.55%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.55%   |
| Dell Wireless 360 Bluetooth                         | 1         | 0.55%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 0.55%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.55%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 0.55%   |
| Unknown                                             | 1         | 0.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 248       | 71.88%  |
| AMD                    | 51        | 14.78%  |
| Nvidia                 | 32        | 9.28%   |
| Generalplus Technology | 7         | 2.03%   |
| Logitech               | 2         | 0.58%   |
| C-Media Electronics    | 2         | 0.58%   |
| JMTek                  | 1         | 0.29%   |
| iCreate Technologies   | 1         | 0.29%   |
| Creative Labs          | 1         | 0.29%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 63        | 15.18%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 30        | 7.23%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 20        | 4.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 18        | 4.34%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 15        | 3.61%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 15        | 3.61%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 14        | 3.37%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 13        | 3.13%   |
| Intel Broadwell-U Audio Controller                                                                | 13        | 3.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 13        | 3.13%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 12        | 2.89%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 2.89%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 2.89%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 11        | 2.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 2.17%   |
| Intel 200 Series PCH HD Audio                                                                     | 9         | 2.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 1.93%   |
| Generalplus Technology USB Audio Device                                                           | 7         | 1.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6         | 1.45%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 6         | 1.45%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 1.2%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 1.2%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 1.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 1.2%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 1.2%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 0.96%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 0.96%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4         | 0.96%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.72%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.72%   |
| Intel USB PnP Sound Device                                                                        | 3         | 0.72%   |
| Intel Smart Sound Technology (SST) Audio Controller                                               | 3         | 0.72%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 0.72%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 0.72%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 3         | 0.72%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 0.48%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 2         | 0.48%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.48%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.48%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 42        | 22.46%  |
| SK hynix            | 36        | 19.25%  |
| Micron Technology   | 21        | 11.23%  |
| G.Skill             | 13        | 6.95%   |
| Unknown             | 10        | 5.35%   |
| A-DATA Technology   | 10        | 5.35%   |
| Kingston            | 9         | 4.81%   |
| Transcend           | 7         | 3.74%   |
| Team                | 7         | 3.74%   |
| Corsair             | 7         | 3.74%   |
| Ramaxel Technology  | 4         | 2.14%   |
| Nanya Technology    | 3         | 1.6%    |
| Crucial             | 3         | 1.6%    |
| SemsoTai            | 2         | 1.07%   |
| Unknown (C509)      | 1         | 0.53%   |
| Unknown (768A)      | 1         | 0.53%   |
| TwinMOS             | 1         | 0.53%   |
| Toshiba             | 1         | 0.53%   |
| Ramos Technology    | 1         | 0.53%   |
| Qumo                | 1         | 0.53%   |
| Patriot             | 1         | 0.53%   |
| Hewlett-Packard     | 1         | 0.53%   |
| GeIL                | 1         | 0.53%   |
| Elpida              | 1         | 0.53%   |
| ASint Technology    | 1         | 0.53%   |
| Apacer              | 1         | 0.53%   |
| Unknown             | 1         | 0.53%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s | 6         | 3.09%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s  | 5         | 2.58%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s | 4         | 2.06%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s | 3         | 1.55%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s | 3         | 1.55%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s | 3         | 1.55%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s | 3         | 1.55%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s  | 3         | 1.55%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s  | 3         | 1.55%   |
| Corsair RAM CMK8GX4M1E3200C16 8GB DIMM DDR4 3200MT/s   | 3         | 1.55%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s     | 2         | 1.03%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s  | 2         | 1.03%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s | 2         | 1.03%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s | 2         | 1.03%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s  | 2         | 1.03%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s  | 2         | 1.03%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s  | 2         | 1.03%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s  | 2         | 1.03%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s | 2         | 1.03%   |
| Samsung RAM M471A1K44BM0-CRC 8GB SODIMM DDR4 2400MT/s  | 2         | 1.03%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s  | 2         | 1.03%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s  | 2         | 1.03%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s   | 2         | 1.03%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s   | 2         | 1.03%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s  | 2         | 1.03%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s  | 2         | 1.03%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s | 2         | 1.03%   |
| G.Skill RAM F4-3600C18-16GTZN 16GB DIMM DDR4 3666MT/s  | 2         | 1.03%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s   | 2         | 1.03%   |
| Unknown RAM Module 8GB DIMM DDR4 3200MT/s              | 1         | 0.52%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s         | 1         | 0.52%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s            | 1         | 0.52%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s            | 1         | 0.52%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s         | 1         | 0.52%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                | 1         | 0.52%   |
| Unknown RAM Module 4096MB DIMM 1066MT/s                | 1         | 0.52%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s    | 1         | 0.52%   |
| Unknown RAM Module 2GB DIMM SDRAM 1066MT/s             | 1         | 0.52%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 1         | 0.52%   |
| Unknown RAM Module 2048MB Row Of Chips LPDDR4 4267MT/s | 1         | 0.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 92        | 63.01%  |
| DDR3    | 39        | 26.71%  |
| LPDDR4  | 5         | 3.42%   |
| LPDDR3  | 4         | 2.74%   |
| SDRAM   | 2         | 1.37%   |
| DDR2    | 2         | 1.37%   |
| Unknown | 2         | 1.37%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 100       | 69.93%  |
| DIMM         | 36        | 25.17%  |
| Row Of Chips | 7         | 4.9%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 68        | 41.21%  |
| 4096  | 57        | 34.55%  |
| 16384 | 18        | 10.91%  |
| 2048  | 15        | 9.09%   |
| 32768 | 6         | 3.64%   |
| 1024  | 1         | 0.61%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 36        | 22.36%  |
| 3200  | 31        | 19.25%  |
| 1600  | 27        | 16.77%  |
| 2400  | 16        | 9.94%   |
| 2133  | 11        | 6.83%   |
| 1333  | 8         | 4.97%   |
| 1067  | 4         | 2.48%   |
| 2800  | 3         | 1.86%   |
| 1867  | 3         | 1.86%   |
| 1334  | 3         | 1.86%   |
| 1066  | 3         | 1.86%   |
| 3800  | 2         | 1.24%   |
| 3666  | 2         | 1.24%   |
| 3600  | 2         | 1.24%   |
| 3266  | 2         | 1.24%   |
| 8400  | 1         | 0.62%   |
| 4267  | 1         | 0.62%   |
| 4199  | 1         | 0.62%   |
| 3151  | 1         | 0.62%   |
| 2933  | 1         | 0.62%   |
| 2134  | 1         | 0.62%   |
| 2000  | 1         | 0.62%   |
| 800   | 1         | 0.62%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 66.67%  |
| Pantum      | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Seiko Epson L132 Series | 2         | 66.67%  |
| Pantum PMF22 series     | 1         | 33.33%  |

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
| Chicony Electronics                    | 40        | 21.28%  |
| IMC Networks                           | 36        | 19.15%  |
| Cheng Uei Precision Industry (Foxlink) | 16        | 8.51%   |
| Realtek Semiconductor                  | 13        | 6.91%   |
| Sunplus Innovation Technology          | 11        | 5.85%   |
| Quanta                                 | 11        | 5.85%   |
| Microdia                               | 11        | 5.85%   |
| Bison Electronics                      | 10        | 5.32%   |
| Lite-On Technology                     | 7         | 3.72%   |
| Suyin                                  | 5         | 2.66%   |
| Luxvisions Innotech Limited            | 5         | 2.66%   |
| Z-Star Microelectronics                | 2         | 1.06%   |
| Syntek                                 | 2         | 1.06%   |
| Sonix Technology                       | 2         | 1.06%   |
| Silicon Motion                         | 2         | 1.06%   |
| Primax Electronics                     | 2         | 1.06%   |
| Logitech                               | 2         | 1.06%   |
| ANYKA                                  | 2         | 1.06%   |
| Alcor Micro                            | 2         | 1.06%   |
| Acer                                   | 2         | 1.06%   |
| WCM_USB                                | 1         | 0.53%   |
| SiGma Micro                            | 1         | 0.53%   |
| Jieli Technology                       | 1         | 0.53%   |
| Importek                               | 1         | 0.53%   |
| Apple                                  | 1         | 0.53%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                       | 13        | 6.91%   |
| Chicony USB2.0 VGA UVC WebCam                           | 11        | 5.85%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 10        | 5.32%   |
| Chicony HD WebCam                                       | 6         | 3.19%   |
| Microdia Integrated_Webcam_HD                           | 5         | 2.66%   |
| IMC Networks VGA UVC WebCam                             | 5         | 2.66%   |
| Luxvisions Innotech Limited HP HD Camera                | 4         | 2.13%   |
| Lite-On HP HD Camera                                    | 4         | 2.13%   |
| IMC Networks Integrated Camera                          | 4         | 2.13%   |
| Suyin Integrated_Webcam_HD                              | 3         | 1.6%    |
| Realtek Integrated_Webcam_HD                            | 3         | 1.6%    |
| Quanta HD Webcam                                        | 3         | 1.6%    |
| IMC Networks USB2.0 HD IR UVC WebCam                    | 3         | 1.6%    |
| Chicony EasyCamera                                      | 3         | 1.6%    |
| Cheng Uei Precision Industry (Foxlink) Webcam           | 3         | 1.6%    |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 3         | 1.6%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera     | 3         | 1.6%    |
| Bison Integrated Camera                                 | 3         | 1.6%    |
| Bison HD Webcam                                         | 3         | 1.6%    |
| Z-Star A4 TECH USB2.0 PC Camera J                       | 2         | 1.06%   |
| Suyin HP Truevision HD                                  | 2         | 1.06%   |
| Sunplus Laptop Integrated Webcam HD                     | 2         | 1.06%   |
| Sunplus Integrated_Webcam_HD                            | 2         | 1.06%   |
| Realtek USB2.0 VGA UVC WebCam                           | 2         | 1.06%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 1.06%   |
| Quanta HP HD Camera                                     | 2         | 1.06%   |
| Quanta HD User Facing                                   | 2         | 1.06%   |
| Primax HP HD Webcam [Fixed]                             | 2         | 1.06%   |
| Microdia HP Integrated Webcam                           | 2         | 1.06%   |
| Logitech Webcam C270                                    | 2         | 1.06%   |
| Lite-On Integrated Camera                               | 2         | 1.06%   |
| Chicony USB2.0 Camera                                   | 2         | 1.06%   |
| Chicony Integrated Camera                               | 2         | 1.06%   |
| Chicony HP Truevision HD camera                         | 2         | 1.06%   |
| Chicony HP HD Webcam                                    | 2         | 1.06%   |
| Chicony HP HD Camera                                    | 2         | 1.06%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 2         | 1.06%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam     | 2         | 1.06%   |
| Bison Lenovo EasyCamera                                 | 2         | 1.06%   |
| ANYKA V380 FHD Camera                                   | 2         | 1.06%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 27        | 79.41%  |
| Synaptics                  | 3         | 8.82%   |
| Elan Microelectronics      | 2         | 5.88%   |
| Upek                       | 1         | 2.94%   |
| Shenzhen Goodix Technology | 1         | 2.94%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 14        | 41.18%  |
| Validity Sensors VFS491                                                    | 4         | 11.76%  |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 8.82%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 5.88%   |
| Elan ELAN:Fingerprint                                                      | 2         | 5.88%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 2.94%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.94%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 2.94%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 2.94%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.94%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 2.94%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 2.94%   |
| Synaptics  WBDI                                                            | 1         | 2.94%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 2.94%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 6         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 33.33%  |
| Broadcom 5880                                                                | 2         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 16.67%  |
| Broadcom 58200                                                               | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 221       | 71.52%  |
| 1     | 79        | 25.57%  |
| 2     | 6         | 1.94%   |
| 3     | 2         | 0.65%   |
| 5     | 1         | 0.32%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 34        | 35.05%  |
| Graphics card            | 27        | 27.84%  |
| Net/wireless             | 13        | 13.4%   |
| Chipcard                 | 6         | 6.19%   |
| Camera                   | 6         | 6.19%   |
| Multimedia controller    | 3         | 3.09%   |
| Communication controller | 3         | 3.09%   |
| Bluetooth                | 3         | 3.09%   |
| Sound                    | 1         | 1.03%   |
| Card reader              | 1         | 1.03%   |


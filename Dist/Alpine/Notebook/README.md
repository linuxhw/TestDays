Alpine - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Alpine.

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

Total: 188

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Apple         | MacBookPro12,1              | [face1f6c37](https://linux-hardware.org/?probe=face1f6c37) | Dec 25, 2024 |
| MSI           | Creator 15 A11UE            | [9beee8397d](https://linux-hardware.org/?probe=9beee8397d) | Dec 23, 2024 |
| Dell          | Inspiron 14 Plus 7440       | [b0c9087a18](https://linux-hardware.org/?probe=b0c9087a18) | Dec 08, 2024 |
| Dell          | Inspiron 14 Plus 7440       | [253c2d74fb](https://linux-hardware.org/?probe=253c2d74fb) | Dec 08, 2024 |
| Lenovo        | ThinkPad T400 27658JG       | [0e628ec7f3](https://linux-hardware.org/?probe=0e628ec7f3) | Dec 06, 2024 |
| Lenovo        | ThinkPad T400 27658JG       | [19da4f0a7b](https://linux-hardware.org/?probe=19da4f0a7b) | Dec 06, 2024 |
| HP            | Laptop 14-dk0xxx            | [413b02dc7a](https://linux-hardware.org/?probe=413b02dc7a) | Nov 25, 2024 |
| HP            | Stream Laptop 11-ak0xxx     | [21f300941c](https://linux-hardware.org/?probe=21f300941c) | Nov 20, 2024 |
| Google        | Kefka                       | [bf5cd8a623](https://linux-hardware.org/?probe=bf5cd8a623) | Nov 12, 2024 |
| Google        | Kefka                       | [affed9dd1e](https://linux-hardware.org/?probe=affed9dd1e) | Nov 12, 2024 |
| Sony          | VPCEC3A4E                   | [6a6d904b6a](https://linux-hardware.org/?probe=6a6d904b6a) | Nov 01, 2024 |
| Lenovo        | V15 G3 IAP 82TT             | [bdb953f731](https://linux-hardware.org/?probe=bdb953f731) | Oct 29, 2024 |
| HP            | EliteBook 820 G2            | [648ab7b15f](https://linux-hardware.org/?probe=648ab7b15f) | Oct 29, 2024 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [50274618bd](https://linux-hardware.org/?probe=50274618bd) | Oct 25, 2024 |
| Dell          | XPS 13 7390                 | [4bc8b23ee8](https://linux-hardware.org/?probe=4bc8b23ee8) | Oct 13, 2024 |
| ASUSTek       | F5SL                        | [8b5218d324](https://linux-hardware.org/?probe=8b5218d324) | Oct 12, 2024 |
| Gateway       | MD7811U                     | [7df8e45ea9](https://linux-hardware.org/?probe=7df8e45ea9) | Oct 03, 2024 |
| Gateway       | MD7811U                     | [23ddfbc0e6](https://linux-hardware.org/?probe=23ddfbc0e6) | Oct 03, 2024 |
| HP            | EliteBook 840 G1            | [cb3d0e7a13](https://linux-hardware.org/?probe=cb3d0e7a13) | Sep 06, 2024 |
| Lenovo        | ThinkPad T480 20L6S0WY00    | [c99c4f1732](https://linux-hardware.org/?probe=c99c4f1732) | Aug 25, 2024 |
| Dell          | Inspiron 5547               | [75994d1146](https://linux-hardware.org/?probe=75994d1146) | Aug 18, 2024 |
| Lenovo        | ThinkPad T480 20L6S0WY00    | [2b23906005](https://linux-hardware.org/?probe=2b23906005) | Aug 15, 2024 |
| Samsung       | 100NZC                      | [866404351e](https://linux-hardware.org/?probe=866404351e) | Aug 15, 2024 |
| Acer          | Nitro AN517-51              | [680a0fc9bd](https://linux-hardware.org/?probe=680a0fc9bd) | Aug 05, 2024 |
| Lenovo        | ThinkPad T480 20L6S0WY00    | [41c870c893](https://linux-hardware.org/?probe=41c870c893) | Jul 26, 2024 |
| HP            | ENVY Laptop 13-ad1xx        | [c583344cb5](https://linux-hardware.org/?probe=c583344cb5) | Jul 10, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [1fb3302507](https://linux-hardware.org/?probe=1fb3302507) | Jul 08, 2024 |
| HP            | Laptop 15-bs0xx             | [e7d34a0b87](https://linux-hardware.org/?probe=e7d34a0b87) | Jul 08, 2024 |
| Dell          | Inspiron 1545               | [16a84d453a](https://linux-hardware.org/?probe=16a84d453a) | Jul 05, 2024 |
| Dell          | Inspiron 1545               | [57f7d3d2e8](https://linux-hardware.org/?probe=57f7d3d2e8) | Jul 04, 2024 |
| Dell          | Inspiron 5575               | [7e022ade86](https://linux-hardware.org/?probe=7e022ade86) | Jul 01, 2024 |
| HP            | ProBook 450 G7              | [f45e2bd9fe](https://linux-hardware.org/?probe=f45e2bd9fe) | Jun 26, 2024 |
| Dell          | Inspiron 14 Plus 7440       | [103438691e](https://linux-hardware.org/?probe=103438691e) | Jun 17, 2024 |
| Dell          | Inspiron N5110              | [110790c81a](https://linux-hardware.org/?probe=110790c81a) | Jun 14, 2024 |
| HP            | EliteBook 840 G5            | [8d3c1d6921](https://linux-hardware.org/?probe=8d3c1d6921) | Jun 11, 2024 |
| HP            | EliteBook 2560p             | [08989abc4e](https://linux-hardware.org/?probe=08989abc4e) | Jun 09, 2024 |
| HP            | EliteBook 2560p             | [a8eb359b6e](https://linux-hardware.org/?probe=a8eb359b6e) | Jun 09, 2024 |
| Toshiba       | Satellite M50Dt-A           | [40c29073b1](https://linux-hardware.org/?probe=40c29073b1) | May 31, 2024 |
| Sony          | VPCEC3A4E                   | [7cbeb425cf](https://linux-hardware.org/?probe=7cbeb425cf) | May 31, 2024 |
| Lenovo        | ThinkPad T480 20L6S0WY00    | [c84cce1d60](https://linux-hardware.org/?probe=c84cce1d60) | May 26, 2024 |
| Lenovo        | ThinkPad T480 20L6S0WY00    | [7d2a37b22b](https://linux-hardware.org/?probe=7d2a37b22b) | May 26, 2024 |
| Lenovo        | ThinkPad X61 76754KU        | [1a083b94dc](https://linux-hardware.org/?probe=1a083b94dc) | Apr 27, 2024 |
| HP            | Pavilion dv6500             | [339679d475](https://linux-hardware.org/?probe=339679d475) | Apr 22, 2024 |
| HP            | ENVY Laptop 13-ad1xx        | [73379ea508](https://linux-hardware.org/?probe=73379ea508) | Apr 13, 2024 |
| HP            | Laptop 15-bw0xx             | [823f3c3138](https://linux-hardware.org/?probe=823f3c3138) | Apr 09, 2024 |
| Dell          | Inspiron 14 Plus 7440       | [9b975edbf7](https://linux-hardware.org/?probe=9b975edbf7) | Mar 23, 2024 |
| HP            | Pavilion Notebook           | [2c5499e776](https://linux-hardware.org/?probe=2c5499e776) | Mar 22, 2024 |
| Lenovo        | V15 G3 IAP 82TT             | [fb281cfb94](https://linux-hardware.org/?probe=fb281cfb94) | Mar 18, 2024 |
| Sony          | VPCEC3A4E                   | [38f3380fcf](https://linux-hardware.org/?probe=38f3380fcf) | Mar 11, 2024 |
| Dell          | Inspiron 14 Plus 7440       | [98c56ac1d0](https://linux-hardware.org/?probe=98c56ac1d0) | Mar 10, 2024 |
| SLIMBOOK      | EXECUTIVE-14                | [39d528dadf](https://linux-hardware.org/?probe=39d528dadf) | Mar 01, 2024 |
| SLIMBOOK      | EXECUTIVE-14                | [5fc24348a8](https://linux-hardware.org/?probe=5fc24348a8) | Mar 01, 2024 |
| HP            | Laptop 15-bw0xx             | [39ed74cf97](https://linux-hardware.org/?probe=39ed74cf97) | Feb 24, 2024 |
| HP            | ENVY Laptop 13-ad1xx        | [340e79c73f](https://linux-hardware.org/?probe=340e79c73f) | Feb 22, 2024 |
| Sony          | VPCEC3A4E                   | [e365c35e91](https://linux-hardware.org/?probe=e365c35e91) | Feb 22, 2024 |
| Dell          | Inspiron 14 Plus 7440       | [0ee9f9ca69](https://linux-hardware.org/?probe=0ee9f9ca69) | Feb 18, 2024 |
| Sony          | VPCEC3A4E                   | [cc5290daff](https://linux-hardware.org/?probe=cc5290daff) | Feb 18, 2024 |
| Sony          | VPCEC3A4E                   | [b31170da6a](https://linux-hardware.org/?probe=b31170da6a) | Feb 17, 2024 |
| HP            | ENVY Laptop 13-ad1xx        | [f3d4535f87](https://linux-hardware.org/?probe=f3d4535f87) | Feb 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [6b61926dd2](https://linux-hardware.org/?probe=6b61926dd2) | Feb 09, 2024 |
| Dell          | Inspiron 14 Plus 7440       | [1e2603f833](https://linux-hardware.org/?probe=1e2603f833) | Feb 04, 2024 |
| Apple         | MacBook5,1                  | [d3a48ce5b5](https://linux-hardware.org/?probe=d3a48ce5b5) | Jan 24, 2024 |
| Apple         | MacBook5,1                  | [2fa13d832c](https://linux-hardware.org/?probe=2fa13d832c) | Jan 24, 2024 |
| Dell          | Inspiron 14 Plus 7440       | [876874e8b5](https://linux-hardware.org/?probe=876874e8b5) | Jan 24, 2024 |
| Lenovo        | Y70-70 Touch 80DU           | [fb81d9ccfe](https://linux-hardware.org/?probe=fb81d9ccfe) | Jan 20, 2024 |
| Wortmann      | M660SE                      | [225361b7c3](https://linux-hardware.org/?probe=225361b7c3) | Jan 06, 2024 |
| Dell          | Inspiron 14 Plus 7440       | [6f9241e288](https://linux-hardware.org/?probe=6f9241e288) | Jan 04, 2024 |
| Fujitsu       | LIFEBOOK AH530              | [9d5aa2f8ae](https://linux-hardware.org/?probe=9d5aa2f8ae) | Jan 02, 2024 |
| Fujitsu       | LIFEBOOK AH530              | [db0bed1921](https://linux-hardware.org/?probe=db0bed1921) | Jan 02, 2024 |
| Dell          | Inspiron 14 Plus 7440       | [7528cb1c24](https://linux-hardware.org/?probe=7528cb1c24) | Dec 30, 2023 |
| Dell          | Inspiron 14 Plus 7440       | [f071a372c0](https://linux-hardware.org/?probe=f071a372c0) | Dec 29, 2023 |
| Acer          | Aspire A515-54              | [ea0b7cd870](https://linux-hardware.org/?probe=ea0b7cd870) | Dec 26, 2023 |
| Dell          | Inspiron 14 Plus 7440       | [2432d4f585](https://linux-hardware.org/?probe=2432d4f585) | Dec 22, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | [d33b5845ef](https://linux-hardware.org/?probe=d33b5845ef) | Dec 20, 2023 |
| Dell          | Inspiron 14 Plus 7440       | [4b404f8509](https://linux-hardware.org/?probe=4b404f8509) | Dec 15, 2023 |
| Dell          | Latitude 3420               | [b344d71410](https://linux-hardware.org/?probe=b344d71410) | Dec 13, 2023 |
| HP            | Laptop 17-cp0xxx            | [2199caf331](https://linux-hardware.org/?probe=2199caf331) | Dec 10, 2023 |
| ASUSTek       | 1001PX                      | [74bc5aeded](https://linux-hardware.org/?probe=74bc5aeded) | Nov 22, 2023 |
| ASUSTek       | 1001PX                      | [2069694d95](https://linux-hardware.org/?probe=2069694d95) | Nov 22, 2023 |
| Dell          | Inspiron 14 Plus 7440       | [b312b34d74](https://linux-hardware.org/?probe=b312b34d74) | Nov 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [f576d94ac0](https://linux-hardware.org/?probe=f576d94ac0) | Nov 17, 2023 |
| Dell          | Inspiron 14 Plus 7440       | [f48f05994e](https://linux-hardware.org/?probe=f48f05994e) | Nov 14, 2023 |
| Apple         | MacBookAir5,2               | [60e418e27f](https://linux-hardware.org/?probe=60e418e27f) | Nov 14, 2023 |
| Dell          | Inspiron 14 Plus 7440       | [65a7263504](https://linux-hardware.org/?probe=65a7263504) | Nov 09, 2023 |
| Dell          | Inspiron 14 Plus 7440       | [ccc7d658ea](https://linux-hardware.org/?probe=ccc7d658ea) | Nov 06, 2023 |
| Lenovo        | Flex 2-14 20404             | [0656d1a0a8](https://linux-hardware.org/?probe=0656d1a0a8) | Oct 28, 2023 |
| Dell          | Inspiron 14 Plus 7440       | [e116ef83e9](https://linux-hardware.org/?probe=e116ef83e9) | Oct 27, 2023 |
| Dell          | Inspiron 14 Plus 7440       | [6df3cd6820](https://linux-hardware.org/?probe=6df3cd6820) | Oct 20, 2023 |
| Dell          | Inspiron 14 Plus 7440       | [8356867b4d](https://linux-hardware.org/?probe=8356867b4d) | Oct 04, 2023 |
| Dell          | Inspiron 14 Plus 7440       | [1d2bd102c6](https://linux-hardware.org/?probe=1d2bd102c6) | Sep 28, 2023 |
| Dell          | Inspiron 14 Plus 7440       | [6295f7193c](https://linux-hardware.org/?probe=6295f7193c) | Sep 27, 2023 |
| Dell          | Inspiron 14 Plus 7440       | [793c32918d](https://linux-hardware.org/?probe=793c32918d) | Sep 23, 2023 |
| Unknown       | Unknown                     | [cc13e0926e](https://linux-hardware.org/?probe=cc13e0926e) | Sep 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [416798463e](https://linux-hardware.org/?probe=416798463e) | Sep 16, 2023 |
| LG Electro... | LW25-B7HG                   | [e9998203e6](https://linux-hardware.org/?probe=e9998203e6) | Sep 12, 2023 |
| Dell          | Inspiron 14 Plus 7440       | [d59c2170bb](https://linux-hardware.org/?probe=d59c2170bb) | Sep 08, 2023 |
| Dell          | Inspiron 14 Plus 7440       | [ed1061dbb1](https://linux-hardware.org/?probe=ed1061dbb1) | Sep 07, 2023 |
| Dell          | Inspiron 14 Plus 7440       | [30368099b8](https://linux-hardware.org/?probe=30368099b8) | Sep 06, 2023 |
| Dell          | Inspiron 14 Plus 7440       | [f71590bc2b](https://linux-hardware.org/?probe=f71590bc2b) | Sep 03, 2023 |
| HP            | Presario V2000 (ES307UA#... | [6c727b9e00](https://linux-hardware.org/?probe=6c727b9e00) | Aug 23, 2023 |
| Dell          | Inspiron 14 Plus 7440       | [d81314b86d](https://linux-hardware.org/?probe=d81314b86d) | Aug 12, 2023 |
| Dell          | Inspiron 14 Plus 7440       | [4d26902a65](https://linux-hardware.org/?probe=4d26902a65) | Aug 12, 2023 |
| Dell          | Inspiron 14 Plus 7440       | [d4a16b0b3e](https://linux-hardware.org/?probe=d4a16b0b3e) | Aug 10, 2023 |
| Dell          | Inspiron 14 Plus 7440       | [294dcce02b](https://linux-hardware.org/?probe=294dcce02b) | Aug 04, 2023 |
| Dell          | Latitude 5430 Rugged        | [051aebd1a2](https://linux-hardware.org/?probe=051aebd1a2) | Jul 24, 2023 |
| ASUSTek       | A3AC                        | [1bf0a25c8e](https://linux-hardware.org/?probe=1bf0a25c8e) | Jul 22, 2023 |
| ASUSTek       | A3AC                        | [f7fb9875de](https://linux-hardware.org/?probe=f7fb9875de) | Jul 22, 2023 |
| Toshiba       | Satellite Pro L50-A         | [f1907449fa](https://linux-hardware.org/?probe=f1907449fa) | Jun 24, 2023 |
| Google        | Kefka                       | [c5d9002e23](https://linux-hardware.org/?probe=c5d9002e23) | Jun 23, 2023 |
| Lenovo        | ThinkPad T440p              | [c058d92130](https://linux-hardware.org/?probe=c058d92130) | Jun 05, 2023 |
| Toshiba       | WT8-A                       | [4dc30f1c10](https://linux-hardware.org/?probe=4dc30f1c10) | Jun 04, 2023 |
| MSI           | U200                        | [2fe4d70ea1](https://linux-hardware.org/?probe=2fe4d70ea1) | Jun 02, 2023 |
| Notebook      | NV4XMB,ME,MZ                | [125884d17a](https://linux-hardware.org/?probe=125884d17a) | Apr 05, 2023 |
| Olivetti      | Spring Peak                 | [9678c685d7](https://linux-hardware.org/?probe=9678c685d7) | Mar 31, 2023 |
| Olivetti      | Spring Peak                 | [7878f53f36](https://linux-hardware.org/?probe=7878f53f36) | Mar 31, 2023 |
| Fujitsu       | FMVNP8AE                    | [10efc9f976](https://linux-hardware.org/?probe=10efc9f976) | Mar 21, 2023 |
| Lenovo        | ThinkPad E590 20NB0012RT    | [4c9bfc239a](https://linux-hardware.org/?probe=4c9bfc239a) | Feb 26, 2023 |
| Acer          | Aspire ES1-132              | [386da062e2](https://linux-hardware.org/?probe=386da062e2) | Feb 23, 2023 |
| Lenovo        | V14-ADA 82C6                | [3bd522dc2c](https://linux-hardware.org/?probe=3bd522dc2c) | Feb 13, 2023 |
| Lenovo        | V14-ADA 82C6                | [cfa774a092](https://linux-hardware.org/?probe=cfa774a092) | Feb 13, 2023 |
| Dell          | Inspiron 14 Plus 7440       | [b3d00219b0](https://linux-hardware.org/?probe=b3d00219b0) | Feb 07, 2023 |
| Google        | Leona                       | [59b146e197](https://linux-hardware.org/?probe=59b146e197) | Jan 21, 2023 |
| Dell          | Inspiron 3558               | [9635348d10](https://linux-hardware.org/?probe=9635348d10) | Jan 09, 2023 |
| Lenovo        | ThinkPad X131e 33711Q7      | [3336313cae](https://linux-hardware.org/?probe=3336313cae) | Jan 06, 2023 |
| Lenovo        | ThinkPad X131e 33711Q7      | [7e0f8a38bf](https://linux-hardware.org/?probe=7e0f8a38bf) | Jan 04, 2023 |
| Dell          | Inspiron N5010              | [389475ec30](https://linux-hardware.org/?probe=389475ec30) | Dec 25, 2022 |
| Dell          | Inspiron 5447               | [735ac089ab](https://linux-hardware.org/?probe=735ac089ab) | Oct 17, 2022 |
| HP            | Presario V4000 (EQ608PA#... | [f462d80b2a](https://linux-hardware.org/?probe=f462d80b2a) | Oct 06, 2022 |
| Toshiba       | Satellite M645              | [b342f11704](https://linux-hardware.org/?probe=b342f11704) | Aug 16, 2022 |
| Toshiba       | Satellite M645              | [f64d98a9e1](https://linux-hardware.org/?probe=f64d98a9e1) | Aug 16, 2022 |
| Dell          | Inspiron 3180               | [d4dbaf9ec8](https://linux-hardware.org/?probe=d4dbaf9ec8) | Aug 14, 2022 |
| Fujitsu       | LIFEBOOK P702               | [fdbe6c32cd](https://linux-hardware.org/?probe=fdbe6c32cd) | Aug 06, 2022 |
| Sony          | VGN-UX27GN                  | [ed20bd45a4](https://linux-hardware.org/?probe=ed20bd45a4) | Jun 20, 2022 |
| IBM           | ThinkPad X40 2371LBG        | [e7610b86d4](https://linux-hardware.org/?probe=e7610b86d4) | Jun 20, 2022 |
| HP            | EliteBook 8460p             | [a0a6c37152](https://linux-hardware.org/?probe=a0a6c37152) | Jun 19, 2022 |
| ASUSTek       | X555LAB                     | [e47cf70de1](https://linux-hardware.org/?probe=e47cf70de1) | Jun 17, 2022 |
| HP            | ENVY Sleekbook 6 PC         | [28b7e84c50](https://linux-hardware.org/?probe=28b7e84c50) | May 24, 2022 |
| HP            | ENVY Sleekbook 6 PC         | [5d78835d90](https://linux-hardware.org/?probe=5d78835d90) | May 24, 2022 |
| ASUSTek       | N10Jc                       | [ae20ca4c7c](https://linux-hardware.org/?probe=ae20ca4c7c) | May 05, 2022 |
| ASUSTek       | N10Jc                       | [1f688a5b2d](https://linux-hardware.org/?probe=1f688a5b2d) | May 05, 2022 |
| HP            | ProBook 4310s               | [a37901ae30](https://linux-hardware.org/?probe=a37901ae30) | Apr 26, 2022 |
| Haier         | U144S                       | [9a4827b852](https://linux-hardware.org/?probe=9a4827b852) | Mar 26, 2022 |
| Acer          | Aspire E5-553G              | [930cc740b2](https://linux-hardware.org/?probe=930cc740b2) | Mar 24, 2022 |
| Lenovo        | ThinkPad T420 42364F2       | [d82acaba71](https://linux-hardware.org/?probe=d82acaba71) | Mar 23, 2022 |
| Dell          | XPS 15 7590                 | [df2a40363b](https://linux-hardware.org/?probe=df2a40363b) | Mar 18, 2022 |
| ASUSTek       | ZenBook UX431FA             | [b3cbed05f5](https://linux-hardware.org/?probe=b3cbed05f5) | Mar 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [94cf359935](https://linux-hardware.org/?probe=94cf359935) | Feb 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [822688debe](https://linux-hardware.org/?probe=822688debe) | Feb 16, 2022 |
| ASUSTek       | ZenBook UX431FA             | [519a7a72ab](https://linux-hardware.org/?probe=519a7a72ab) | Jan 24, 2022 |
| HP            | EliteBook 1040 G3 Notebo... | [465c51678d](https://linux-hardware.org/?probe=465c51678d) | Jan 01, 2022 |
| MSI           | GL72M 7REX                  | [6ada534c8b](https://linux-hardware.org/?probe=6ada534c8b) | Dec 13, 2021 |
| Lenovo        | ThinkPad W700 2752RZ2       | [66ea0a02cb](https://linux-hardware.org/?probe=66ea0a02cb) | Nov 25, 2021 |
| Dell          | Inspiron MM061              | [e293d0cf05](https://linux-hardware.org/?probe=e293d0cf05) | Nov 02, 2021 |
| ASUSTek       | X550EA                      | [bbed87466a](https://linux-hardware.org/?probe=bbed87466a) | Oct 05, 2021 |
| HP            | Compaq Mini CQ10-600        | [4603b3336e](https://linux-hardware.org/?probe=4603b3336e) | Oct 01, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [9ff8561f02](https://linux-hardware.org/?probe=9ff8561f02) | Sep 30, 2021 |
| Lenovo        | Yoga 14sARH 2021 82LB       | [9fa77d455d](https://linux-hardware.org/?probe=9fa77d455d) | Sep 30, 2021 |
| Unknown       | Unknown                     | [d3c742bac9](https://linux-hardware.org/?probe=d3c742bac9) | Sep 26, 2021 |
| Pegatron      | Deepcam                     | [5326e6bf39](https://linux-hardware.org/?probe=5326e6bf39) | Jul 18, 2021 |
| Dell          | Inspiron 14 Plus 7440       | [3199a22608](https://linux-hardware.org/?probe=3199a22608) | Jul 15, 2021 |
| HP            | EliteBook 2740p             | [66479cb1dd](https://linux-hardware.org/?probe=66479cb1dd) | Jul 09, 2021 |
| HP            | EliteBook 2740p             | [652fa48f49](https://linux-hardware.org/?probe=652fa48f49) | Jul 08, 2021 |
| ASUSTek       | X200MA                      | [c9edeec38a](https://linux-hardware.org/?probe=c9edeec38a) | Jun 26, 2021 |
| HP            | Laptop 14-dq1xxx            | [f1b8c01b96](https://linux-hardware.org/?probe=f1b8c01b96) | Jun 22, 2021 |
| IBM           | 264070A                     | [c057e54603](https://linux-hardware.org/?probe=c057e54603) | Jun 08, 2021 |
| HP            | Mini 110-3500               | [be40a38710](https://linux-hardware.org/?probe=be40a38710) | Jun 06, 2021 |
| HP            | ENVY Sleekbook 6 PC         | [0a2464e592](https://linux-hardware.org/?probe=0a2464e592) | Jun 06, 2021 |
| Acer          | Aspire ES1-512              | [01ad8fc793](https://linux-hardware.org/?probe=01ad8fc793) | Jan 30, 2021 |
| Acer          | Aspire 5920G                | [7cf5d7b04a](https://linux-hardware.org/?probe=7cf5d7b04a) | Jan 08, 2021 |
| HP            | Compaq Mini CQ10-600        | [fe7ee46763](https://linux-hardware.org/?probe=fe7ee46763) | Jan 08, 2021 |
| Gateway       | MX3631m                     | [15d8283384](https://linux-hardware.org/?probe=15d8283384) | Jan 03, 2021 |
| Dell          | Studio 1747                 | [b4e0e289f6](https://linux-hardware.org/?probe=b4e0e289f6) | Dec 29, 2020 |
| Dell          | Inspiron 3180               | [4b05b65d0e](https://linux-hardware.org/?probe=4b05b65d0e) | Dec 16, 2020 |
| Dell          | Inspiron 3180               | [0bc140f6f6](https://linux-hardware.org/?probe=0bc140f6f6) | Dec 16, 2020 |
| ASUSTek       | E502SA                      | [0a25648158](https://linux-hardware.org/?probe=0a25648158) | Dec 05, 2020 |
| IBM           | 26446AG                     | [f004231106](https://linux-hardware.org/?probe=f004231106) | Nov 15, 2020 |
| IBM           | 26446AG                     | [29affa3577](https://linux-hardware.org/?probe=29affa3577) | Nov 15, 2020 |
| Google        | Samus                       | [efe40a5a38](https://linux-hardware.org/?probe=efe40a5a38) | Oct 13, 2020 |
| Dell          | Inspiron 5566               | [a12b4d304a](https://linux-hardware.org/?probe=a12b4d304a) | Sep 29, 2020 |
| Apple         | MacBook7,1                  | [6445bfa9bd](https://linux-hardware.org/?probe=6445bfa9bd) | Aug 31, 2020 |
| Dell          | Inspiron 14 Plus 7440       | [d05c262e67](https://linux-hardware.org/?probe=d05c262e67) | Aug 06, 2020 |
| Lenovo        | ThinkPad 11e 20ED001HUS     | [364afb4113](https://linux-hardware.org/?probe=364afb4113) | Aug 06, 2020 |
| Acer          | Aspire ES1-111M             | [c99b05cc07](https://linux-hardware.org/?probe=c99b05cc07) | Jul 30, 2020 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | [aa287cffbe](https://linux-hardware.org/?probe=aa287cffbe) | Jun 18, 2020 |
| HP            | ZBook 15 G5                 | [3f3b1f2237](https://linux-hardware.org/?probe=3f3b1f2237) | Apr 05, 2020 |
| Synology      | DS1019+                     | [622ced4019](https://linux-hardware.org/?probe=622ced4019) | Feb 09, 2020 |
| Synology      | DS1019+                     | [c8a69e1c12](https://linux-hardware.org/?probe=c8a69e1c12) | Jan 21, 2020 |
| Synology      | DS1019+                     | [43a8c9674e](https://linux-hardware.org/?probe=43a8c9674e) | Jan 18, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Alpine 3.19.1               | 9         | 7.2%    |
| Alpine 3.21.0_alpha20240606 | 7         | 5.6%    |
| Alpine 3.20.3               | 7         | 5.6%    |
| Alpine 3.16.0               | 6         | 4.8%    |
| Alpine 3.15.0               | 6         | 4.8%    |
| Alpine 3.19.0               | 5         | 4%      |
| Alpine 3.14.0               | 5         | 4%      |
| Alpine 3.12.0               | 5         | 4%      |
| Alpine 3.20.0               | 4         | 3.2%    |
| Alpine 3.18.3               | 4         | 3.2%    |
| Alpine 3.15.0_alpha20210804 | 4         | 3.2%    |
| Alpine 3.21.0_alpha20240923 | 3         | 2.4%    |
| Alpine 3.20.0_alpha20231219 | 3         | 2.4%    |
| Alpine 3.18.0               | 3         | 2.4%    |
| Alpine 3.17.2               | 3         | 2.4%    |
| Alpine 3.17.0               | 3         | 2.4%    |
| Alpine 3.15.4               | 3         | 2.4%    |
| Alpine 3.21.0               | 2         | 1.6%    |
| Alpine 3.20.2               | 2         | 1.6%    |
| Alpine 3.20.0_alpha20240329 | 2         | 1.6%    |
| Alpine 3.19_alpha20230901   | 2         | 1.6%    |
| Alpine 3.18_alpha20230329   | 2         | 1.6%    |
| Alpine 3.18.4               | 2         | 1.6%    |
| Alpine 3.17.1               | 2         | 1.6%    |
| Alpine 3.16.2               | 2         | 1.6%    |
| Alpine 3.14.2               | 2         | 1.6%    |
| Alpine 3.13.5               | 2         | 1.6%    |
| Alpine 3.13.0_alpha20201218 | 2         | 1.6%    |
| Alpine 3.13.0_alpha20200917 | 2         | 1.6%    |
| Alpine 3.11.2               | 2         | 1.6%    |
| Alpine 3.21.0_alpha20240807 | 1         | 0.8%    |
| Alpine 3.20.1               | 1         | 0.8%    |
| Alpine 3.19.0_rc2           | 1         | 0.8%    |
| Alpine 3.18.6               | 1         | 0.8%    |
| Alpine 3.18.5               | 1         | 0.8%    |
| Alpine 3.18.2               | 1         | 0.8%    |
| Alpine 3.17_alpha20220809   | 1         | 0.8%    |
| Alpine 3.17.3               | 1         | 0.8%    |
| Alpine 3.16.1               | 1         | 0.8%    |
| Alpine 3.16.0_alpha20220316 | 1         | 0.8%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Alpine | 114       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 6.6.32-0-lts           | 4         | 2.96%   |
| 6.6.37-0-lts           | 3         | 2.22%   |
| 6.6.61-0-lts           | 2         | 1.48%   |
| 6.6.45-0-lts           | 2         | 1.48%   |
| 6.6.35-0-lts           | 2         | 1.48%   |
| 6.6.22-0-lts           | 2         | 1.48%   |
| 6.6.17-0-lts           | 2         | 1.48%   |
| 6.6.16-0-lts           | 2         | 1.48%   |
| 6.1.62-0-lts           | 2         | 1.48%   |
| 5.4.83-0-lts           | 2         | 1.48%   |
| 5.4.43-1-lts           | 2         | 1.48%   |
| 5.15.86-0-lts          | 2         | 1.48%   |
| 5.15.59-0-lts          | 2         | 1.48%   |
| 5.15.47-0-lts          | 2         | 1.48%   |
| 5.15.41-0-lts          | 2         | 1.48%   |
| 5.15.4-0-lts           | 2         | 1.48%   |
| 6.8.11-300.fc40.x86_64 | 1         | 0.74%   |
| 6.8.0-49-generic       | 1         | 0.74%   |
| 6.6.9-0-lts            | 1         | 0.74%   |
| 6.6.7-0-lts            | 1         | 0.74%   |
| 6.6.60-0-lts           | 1         | 0.74%   |
| 6.6.58-1-lts           | 1         | 0.74%   |
| 6.6.58-0-lts           | 1         | 0.74%   |
| 6.6.56-0-lts           | 1         | 0.74%   |
| 6.6.53-0-lts           | 1         | 0.74%   |
| 6.6.49-0-lts           | 1         | 0.74%   |
| 6.6.44-0-lts           | 1         | 0.74%   |
| 6.6.42-1-lts           | 1         | 0.74%   |
| 6.6.4-0-lts            | 1         | 0.74%   |
| 6.6.36-0-lts           | 1         | 0.74%   |
| 6.6.33-haos            | 1         | 0.74%   |
| 6.6.33-0-lts           | 1         | 0.74%   |
| 6.6.30-0-lts           | 1         | 0.74%   |
| 6.6.28-0-lts           | 1         | 0.74%   |
| 6.6.26-0-lts           | 1         | 0.74%   |
| 6.6.24-0-lts           | 1         | 0.74%   |
| 6.6.21-0-lts           | 1         | 0.74%   |
| 6.6.20-0-lts           | 1         | 0.74%   |
| 6.6.18-0-lts           | 1         | 0.74%   |
| 6.6.12-0-lts           | 1         | 0.74%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.6.32  | 4         | 3.05%   |
| 6.6.37  | 3         | 2.29%   |
| 6.6.61  | 2         | 1.53%   |
| 6.6.58  | 2         | 1.53%   |
| 6.6.45  | 2         | 1.53%   |
| 6.6.35  | 2         | 1.53%   |
| 6.6.33  | 2         | 1.53%   |
| 6.6.22  | 2         | 1.53%   |
| 6.6.17  | 2         | 1.53%   |
| 6.6.16  | 2         | 1.53%   |
| 6.1.62  | 2         | 1.53%   |
| 5.4.83  | 2         | 1.53%   |
| 5.4.43  | 2         | 1.53%   |
| 5.15.86 | 2         | 1.53%   |
| 5.15.59 | 2         | 1.53%   |
| 5.15.47 | 2         | 1.53%   |
| 5.15.41 | 2         | 1.53%   |
| 5.15.4  | 2         | 1.53%   |
| 5.15.0  | 2         | 1.53%   |
| 6.8.11  | 1         | 0.76%   |
| 6.8.0   | 1         | 0.76%   |
| 6.6.9   | 1         | 0.76%   |
| 6.6.7   | 1         | 0.76%   |
| 6.6.60  | 1         | 0.76%   |
| 6.6.56  | 1         | 0.76%   |
| 6.6.53  | 1         | 0.76%   |
| 6.6.49  | 1         | 0.76%   |
| 6.6.44  | 1         | 0.76%   |
| 6.6.42  | 1         | 0.76%   |
| 6.6.4   | 1         | 0.76%   |
| 6.6.36  | 1         | 0.76%   |
| 6.6.30  | 1         | 0.76%   |
| 6.6.28  | 1         | 0.76%   |
| 6.6.26  | 1         | 0.76%   |
| 6.6.24  | 1         | 0.76%   |
| 6.6.21  | 1         | 0.76%   |
| 6.6.20  | 1         | 0.76%   |
| 6.6.18  | 1         | 0.76%   |
| 6.6.12  | 1         | 0.76%   |
| 6.6.1   | 1         | 0.76%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.6     | 37        | 30.08%  |
| 5.15    | 30        | 24.39%  |
| 6.1     | 14        | 11.38%  |
| 5.10    | 11        | 8.94%   |
| 5.4     | 10        | 8.13%   |
| 6.12    | 2         | 1.63%   |
| 6.11    | 2         | 1.63%   |
| 5.17    | 2         | 1.63%   |
| 6.8     | 1         | 0.81%   |
| 6.5     | 1         | 0.81%   |
| 6.4     | 1         | 0.81%   |
| 6.2     | 1         | 0.81%   |
| 5.8     | 1         | 0.81%   |
| 5.7     | 1         | 0.81%   |
| 5.6     | 1         | 0.81%   |
| 5.19    | 1         | 0.81%   |
| 5.16    | 1         | 0.81%   |
| 5.14    | 1         | 0.81%   |
| 5.13    | 1         | 0.81%   |
| 5.12    | 1         | 0.81%   |
| 4.4     | 1         | 0.81%   |
| 3.18    | 1         | 0.81%   |
| 3.10    | 1         | 0.81%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 99        | 86.84%  |
| i686   | 12        | 10.53%  |
| armv7l | 2         | 1.75%   |
| i586   | 1         | 0.88%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Unknown       | 76        | 66.67%  |
| XFCE          | 18        | 15.79%  |
| GNOME         | 6         | 5.26%   |
| KDE6          | 4         | 3.51%   |
| sway          | 3         | 2.63%   |
| KDE5          | 3         | 2.63%   |
| LXQt          | 2         | 1.75%   |
| MATE          | 1         | 0.88%   |
| GNOME Classic | 1         | 0.88%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 53        | 44.92%  |
| Unknown | 51        | 43.22%  |
| Wayland | 14        | 11.86%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 77        | 66.96%  |
| LightDM | 21        | 18.26%  |
| GDM     | 9         | 7.83%   |
| SDDM    | 5         | 4.35%   |
| LXDM    | 2         | 1.74%   |
| XDM     | 1         | 0.87%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| C       | 72        | 61.02%  |
| Unknown | 35        | 29.66%  |
| en_US   | 6         | 5.08%   |
| tr_TR   | 1         | 0.85%   |
| ru_RU   | 1         | 0.85%   |
| pt_BR   | 1         | 0.85%   |
| es_NI   | 1         | 0.85%   |
| en_GB   | 1         | 0.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 68        | 58.62%  |
| EFI  | 48        | 41.38%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 89        | 74.79%  |
| Btrfs   | 14        | 11.76%  |
| Overlay | 7         | 5.88%   |
| Xfs     | 2         | 1.68%   |
| Tmpfs   | 2         | 1.68%   |
| Ext2    | 2         | 1.68%   |
| Unknown | 2         | 1.68%   |
| F2fs    | 1         | 0.84%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 66        | 56.41%  |
| GPT     | 37        | 31.62%  |
| MBR     | 14        | 11.97%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 106       | 91.38%  |
| Yes       | 10        | 8.62%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 108       | 93.91%  |
| Yes       | 7         | 6.09%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 28        | 24.56%  |
| Lenovo              | 18        | 15.79%  |
| Dell                | 16        | 14.04%  |
| ASUSTek Computer    | 12        | 10.53%  |
| Acer                | 7         | 6.14%   |
| Toshiba             | 4         | 3.51%   |
| Google              | 4         | 3.51%   |
| IBM                 | 3         | 2.63%   |
| Fujitsu             | 3         | 2.63%   |
| Apple               | 3         | 2.63%   |
| Sony                | 2         | 1.75%   |
| Gateway             | 2         | 1.75%   |
| Unknown             | 2         | 1.75%   |
| Wortmann AG         | 1         | 0.88%   |
| Synology            | 1         | 0.88%   |
| SLIMBOOK            | 1         | 0.88%   |
| Samsung Electronics | 1         | 0.88%   |
| Pegatron            | 1         | 0.88%   |
| Olivetti            | 1         | 0.88%   |
| Notebook            | 1         | 0.88%   |
| MSI                 | 1         | 0.88%   |
| LG Electronics      | 1         | 0.88%   |
| Haier               | 1         | 0.88%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| HP ENVY Laptop 13-ad1xx                  | 4         | 3.51%   |
| Lenovo V15 G3 IAP 82TT                   | 2         | 1.75%   |
| Google Kefka                             | 2         | 1.75%   |
| Unknown                                  | 2         | 1.75%   |
| Wortmann AG M660SE                       | 1         | 0.88%   |
| Toshiba WT8-A                            | 1         | 0.88%   |
| Toshiba Satellite Pro L50-A              | 1         | 0.88%   |
| Toshiba Satellite M645                   | 1         | 0.88%   |
| Toshiba Satellite M50Dt-A                | 1         | 0.88%   |
| Synology DS1019+                         | 1         | 0.88%   |
| Sony VPCEC3A4E                           | 1         | 0.88%   |
| Sony VGN-UX27GN                          | 1         | 0.88%   |
| SLIMBOOK EXECUTIVE-14                    | 1         | 0.88%   |
| Samsung 100NZC                           | 1         | 0.88%   |
| Pegatron Deepcam                         | 1         | 0.88%   |
| Olivetti Spring Peak                     | 1         | 0.88%   |
| Notebook NV4XMB,ME,MZ                    | 1         | 0.88%   |
| MSI GL72M 7REX                           | 1         | 0.88%   |
| LG LW25-B7HG                             | 1         | 0.88%   |
| Lenovo Yoga 14sARH 2021 82LB             | 1         | 0.88%   |
| Lenovo Y70-70 Touch 80DU                 | 1         | 0.88%   |
| Lenovo V14-ADA 82C6                      | 1         | 0.88%   |
| Lenovo ThinkPad X61 76754KU              | 1         | 0.88%   |
| Lenovo ThinkPad X131e 33711Q7            | 1         | 0.88%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS17D00 | 1         | 0.88%   |
| Lenovo ThinkPad W700 2752RZ2             | 1         | 0.88%   |
| Lenovo ThinkPad T480 20L6S0WY00          | 1         | 0.88%   |
| Lenovo ThinkPad T420 42364F2             | 1         | 0.88%   |
| Lenovo ThinkPad T400 27658JG             | 1         | 0.88%   |
| Lenovo ThinkPad E590 20NB0012RT          | 1         | 0.88%   |
| Lenovo ThinkPad E485 20KUCTO1WW          | 1         | 0.88%   |
| Lenovo ThinkPad 11e 20ED001HUS           | 1         | 0.88%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7         | 1         | 0.88%   |
| Lenovo IdeaPad 320-15AST 80XV            | 1         | 0.88%   |
| Lenovo Flex 2-14 20404                   | 1         | 0.88%   |
| IBM ThinkPad X40 2371LBG                 | 1         | 0.88%   |
| IBM 26446AG                              | 1         | 0.88%   |
| IBM 264070A                              | 1         | 0.88%   |
| HP ZBook 15 G5                           | 1         | 0.88%   |
| HP Stream Laptop 11-ak0xxx               | 1         | 0.88%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 11        | 9.65%   |
| Lenovo ThinkPad       | 10        | 8.77%   |
| HP EliteBook          | 7         | 6.14%   |
| Acer Aspire           | 6         | 5.26%   |
| HP Laptop             | 5         | 4.39%   |
| HP ENVY               | 5         | 4.39%   |
| Toshiba Satellite     | 3         | 2.63%   |
| HP Pavilion           | 3         | 2.63%   |
| ASUS VivoBook         | 3         | 2.63%   |
| Lenovo V15            | 2         | 1.75%   |
| Lenovo IdeaPad        | 2         | 1.75%   |
| HP ProBook            | 2         | 1.75%   |
| HP Presario           | 2         | 1.75%   |
| Google Kefka          | 2         | 1.75%   |
| Fujitsu LIFEBOOK      | 2         | 1.75%   |
| Dell XPS              | 2         | 1.75%   |
| Dell Latitude         | 2         | 1.75%   |
| Unknown               | 2         | 1.75%   |
| Wortmann AG M660SE    | 1         | 0.88%   |
| Toshiba WT8-A         | 1         | 0.88%   |
| Synology DS1019+      | 1         | 0.88%   |
| Sony VPCEC3A4E        | 1         | 0.88%   |
| Sony VGN-UX27GN       | 1         | 0.88%   |
| SLIMBOOK EXECUTIVE-14 | 1         | 0.88%   |
| Samsung 100NZC        | 1         | 0.88%   |
| Pegatron Deepcam      | 1         | 0.88%   |
| Olivetti Spring       | 1         | 0.88%   |
| Notebook NV4XMB       | 1         | 0.88%   |
| MSI GL72M             | 1         | 0.88%   |
| LG LW25-B7HG          | 1         | 0.88%   |
| Lenovo Yoga           | 1         | 0.88%   |
| Lenovo Y70-70         | 1         | 0.88%   |
| Lenovo V14-ADA        | 1         | 0.88%   |
| Lenovo Flex           | 1         | 0.88%   |
| IBM ThinkPad          | 1         | 0.88%   |
| IBM 26446AG           | 1         | 0.88%   |
| IBM 264070A           | 1         | 0.88%   |
| HP ZBook              | 1         | 0.88%   |
| HP Stream             | 1         | 0.88%   |
| HP Mini               | 1         | 0.88%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 14        | 12.28%  |
| 2014    | 10        | 8.77%   |
| 2018    | 9         | 7.89%   |
| 2017    | 9         | 7.89%   |
| 2010    | 8         | 7.02%   |
| 2021    | 7         | 6.14%   |
| 2012    | 7         | 6.14%   |
| 2011    | 6         | 5.26%   |
| 2006    | 6         | 5.26%   |
| 2013    | 5         | 4.39%   |
| 2016    | 4         | 3.51%   |
| 2015    | 4         | 3.51%   |
| 2009    | 4         | 3.51%   |
| 2008    | 4         | 3.51%   |
| 2007    | 4         | 3.51%   |
| 2022    | 3         | 2.63%   |
| Unknown | 3         | 2.63%   |
| 2020    | 2         | 1.75%   |
| 2005    | 2         | 1.75%   |
| 2024    | 1         | 0.88%   |
| 2023    | 1         | 0.88%   |
| 1999    | 1         | 0.88%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 114       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 113       | 98.26%  |
| Enabled  | 2         | 1.74%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 110       | 96.49%  |
| Yes  | 4         | 3.51%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Notebooks | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 38        | 31.93%  |
| 3.01-4.0        | 24        | 20.17%  |
| 16.01-24.0      | 13        | 10.92%  |
| 8.01-16.0       | 13        | 10.92%  |
| 0.51-1.0        | 9         | 7.56%   |
| 1.01-2.0        | 8         | 6.72%   |
| 32.01-64.0      | 5         | 4.2%    |
| 2.01-3.0        | 4         | 3.36%   |
| 64.01-256.0     | 2         | 1.68%   |
| 0.01-0.5        | 2         | 1.68%   |
| More than 256.0 | 1         | 0.84%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 33        | 26.83%  |
| 1.01-2.0  | 31        | 25.2%   |
| 2.01-3.0  | 23        | 18.7%   |
| 0.51-1.0  | 15        | 12.2%   |
| 4.01-8.0  | 9         | 7.32%   |
| 3.01-4.0  | 6         | 4.88%   |
| 8.01-16.0 | 3         | 2.44%   |
| 0         | 2         | 1.63%   |
| Unknown   | 1         | 0.81%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 90        | 76.27%  |
| 2      | 22        | 18.64%  |
| 3      | 2         | 1.69%   |
| 0      | 2         | 1.69%   |
| 7      | 1         | 0.85%   |
| 5      | 1         | 0.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 81        | 70.43%  |
| Yes       | 34        | 29.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 86        | 74.78%  |
| No        | 29        | 25.22%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 106       | 91.38%  |
| No        | 10        | 8.62%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 76        | 64.96%  |
| No        | 41        | 35.04%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 23        | 18.7%   |
| Canada       | 11        | 8.94%   |
| Russia       | 10        | 8.13%   |
| Germany      | 9         | 7.32%   |
| UK           | 7         | 5.69%   |
| Turkey       | 7         | 5.69%   |
| Brazil       | 7         | 5.69%   |
| Italy        | 4         | 3.25%   |
| Spain        | 3         | 2.44%   |
| Slovakia     | 3         | 2.44%   |
| France       | 3         | 2.44%   |
| Australia    | 3         | 2.44%   |
| Switzerland  | 2         | 1.63%   |
| Portugal     | 2         | 1.63%   |
| Netherlands  | 2         | 1.63%   |
| Israel       | 2         | 1.63%   |
| Hungary      | 2         | 1.63%   |
| Venezuela    | 1         | 0.81%   |
| UAE          | 1         | 0.81%   |
| Sweden       | 1         | 0.81%   |
| South Korea  | 1         | 0.81%   |
| South Africa | 1         | 0.81%   |
| Puerto Rico  | 1         | 0.81%   |
| Poland       | 1         | 0.81%   |
| Philippines  | 1         | 0.81%   |
| Norway       | 1         | 0.81%   |
| Nicaragua    | 1         | 0.81%   |
| Mexico       | 1         | 0.81%   |
| Lithuania    | 1         | 0.81%   |
| Kenya        | 1         | 0.81%   |
| Jamaica      | 1         | 0.81%   |
| Iran         | 1         | 0.81%   |
| Guatemala    | 1         | 0.81%   |
| Finland      | 1         | 0.81%   |
| Egypt        | 1         | 0.81%   |
| Czechia      | 1         | 0.81%   |
| Cyprus       | 1         | 0.81%   |
| Colombia     | 1         | 0.81%   |
| China        | 1         | 0.81%   |
| Austria      | 1         | 0.81%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Istanbul         | 7         | 5.47%   |
| Vernon           | 4         | 3.13%   |
| Moscow           | 4         | 3.13%   |
| St Petersburg    | 3         | 2.34%   |
| Springfield      | 3         | 2.34%   |
| Zurich           | 2         | 1.56%   |
| Waukesha         | 2         | 1.56%   |
| Ufa              | 2         | 1.56%   |
| Stratford        | 2         | 1.56%   |
| Sao Paulo        | 2         | 1.56%   |
| Manitowoc        | 2         | 1.56%   |
| Fulham           | 2         | 1.56%   |
| Bratislava       | 2         | 1.56%   |
| Zhangzhou        | 1         | 0.78%   |
| Wimborne Minster | 1         | 0.78%   |
| Vragender        | 1         | 0.78%   |
| Vilnius          | 1         | 0.78%   |
| Vienna           | 1         | 0.78%   |
| Ventura          | 1         | 0.78%   |
| Tymovskoye       | 1         | 0.78%   |
| Turin            | 1         | 0.78%   |
| Traunstein       | 1         | 0.78%   |
| Toulouse         | 1         | 0.78%   |
| Thornhill        | 1         | 0.78%   |
| Tehran           | 1         | 0.78%   |
| Tampa            | 1         | 0.78%   |
| Sydney           | 1         | 0.78%   |
| Stuttgart        | 1         | 0.78%   |
| Stewartstown     | 1         | 0.78%   |
| Stavanger        | 1         | 0.78%   |
| St. Paul         | 1         | 0.78%   |
| Sisteron         | 1         | 0.78%   |
| Semily           | 1         | 0.78%   |
| Seattle          | 1         | 0.78%   |
| San Mateo        | 1         | 0.78%   |
| Saarbrücken     | 1         | 0.78%   |
| Rzeszów         | 1         | 0.78%   |
| Rostock          | 1         | 0.78%   |
| Rome             | 1         | 0.78%   |
| Ramat Gan        | 1         | 0.78%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 19        | 39     | 12.84%  |
| Seagate                     | 15        | 29     | 10.14%  |
| Toshiba                     | 14        | 17     | 9.46%   |
| Unknown                     | 12        | 14     | 8.11%   |
| Hitachi                     | 10        | 10     | 6.76%   |
| WDC                         | 8         | 13     | 5.41%   |
| Sandisk                     | 7         | 7      | 4.73%   |
| Kingston                    | 7         | 11     | 4.73%   |
| HGST                        | 7         | 7      | 4.73%   |
| SK hynix                    | 5         | 5      | 3.38%   |
| Intel                       | 5         | 8      | 3.38%   |
| Micron Technology           | 4         | 5      | 2.7%    |
| Crucial                     | 4         | 4      | 2.7%    |
| SPCC                        | 3         | 3      | 2.03%   |
| Realtek Semiconductor       | 3         | 3      | 2.03%   |
| A-DATA Technology           | 3         | 4      | 2.03%   |
| OCZ                         | 2         | 2      | 1.35%   |
| LITEON                      | 2         | 2      | 1.35%   |
| Fujitsu                     | 2         | 2      | 1.35%   |
| SINTECHI                    | 1         | 1      | 0.68%   |
| Secure                      | 1         | 1      | 0.68%   |
| Netac                       | 1         | 1      | 0.68%   |
| Kingston Technology Company | 1         | 1      | 0.68%   |
| KingSpec                    | 1         | 1      | 0.68%   |
| KC600                       | 1         | 1      | 0.68%   |
| JMicron Technology          | 1         | 1      | 0.68%   |
| Intenso                     | 1         | 1      | 0.68%   |
| INNOVATION IT               | 1         | 1      | 0.68%   |
| IBM                         | 1         | 1      | 0.68%   |
| Emtec                       | 1         | 1      | 0.68%   |
| Dell                        | 1         | 2      | 0.68%   |
| Corsair                     | 1         | 2      | 0.68%   |
| China                       | 1         | 1      | 0.68%   |
| Aura                        | 1         | 1      | 0.68%   |
| AMD                         | 1         | 1      | 0.68%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Toshiba KXG50ZNV256G 256GB                          | 4         | 2.23%   |
| Unknown MMC Card  32GB                              | 3         | 1.68%   |
| Unknown MMC Card  16GB                              | 3         | 1.68%   |
| Seagate ST1000LM035-1RK172 1TB                      | 3         | 1.68%   |
| Unknown SD/MMC/MS PRO 128GB                         | 2         | 1.12%   |
| Unknown MMC Card  64GB                              | 2         | 1.12%   |
| Toshiba MQ01ABD100 1TB                              | 2         | 1.12%   |
| Toshiba MQ01ABD075 752GB                            | 2         | 1.12%   |
| SK hynix BC501 NVMe Solid State Drive 512GB         | 2         | 1.12%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 1.12%   |
| Samsung SSD 970 EVO Plus 250GB                      | 2         | 1.12%   |
| Samsung NVMe SSD Drive 1024GB                       | 2         | 1.12%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 2         | 1.12%   |
| Kingston SV300S37A120G 120GB SSD                    | 2         | 1.12%   |
| Crucial CT500MX500SSD1 500GB                        | 2         | 1.12%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1         | 0.56%   |
| WDC WDS500G2B0A 500GB SSD                           | 1         | 0.56%   |
| WDC WDS250G2B0A 250GB SSD                           | 1         | 0.56%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 0.56%   |
| WDC WD60EFRX-68L 6TB                                | 1         | 0.56%   |
| WDC WD5000BEVT-7 500GB                              | 1         | 0.56%   |
| WDC WD5000BEVT-22ZAT0 500GB                         | 1         | 0.56%   |
| WDC WD10SPZX-80Z10T2 1TB                            | 1         | 0.56%   |
| WDC WD10SPZX-60Z10T1 1TB                            | 1         | 0.56%   |
| WDC WD10JPVX-60J 1TB                                | 1         | 0.56%   |
| WDC WD BLACK SDBPNTY-512G-1106 512GB                | 1         | 0.56%   |
| WDC PC SN520 SDAPNUW-512G-1002 512GB                | 1         | 0.56%   |
| Unknown SD32G  32GB                                 | 1         | 0.56%   |
| Unknown NVMe SSD Drive 1024GB                       | 1         | 0.56%   |
| Unknown MMC Card                                    | 1         | 0.56%   |
| Toshiba NVMe SSD Drive 256GB                        | 1         | 0.56%   |
| Toshiba MQ04ABF1 1TB                                | 1         | 0.56%   |
| Toshiba MQ01ABD1 1TB                                | 1         | 0.56%   |
| Toshiba MK6008GAH 64GB                              | 1         | 0.56%   |
| Toshiba MK4009GAL 40GB                              | 1         | 0.56%   |
| Toshiba MK1637GSX 160GB                             | 1         | 0.56%   |
| Toshiba KXG5AZNV512G 512GB                          | 1         | 0.56%   |
| Toshiba KXG5AZNV256G 256GB                          | 1         | 0.56%   |
| Toshiba DT01ACA1 1TB                                | 1         | 0.56%   |
| SPCC Solid State Disk 256GB                         | 1         | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 29     | 27.78%  |
| Hitachi             | 10        | 10     | 18.52%  |
| Toshiba             | 8         | 10     | 14.81%  |
| HGST                | 7         | 7      | 12.96%  |
| WDC                 | 5         | 6      | 9.26%   |
| Unknown             | 2         | 2      | 3.7%    |
| Samsung Electronics | 2         | 3      | 3.7%    |
| Fujitsu             | 2         | 2      | 3.7%    |
| SINTECHI            | 1         | 1      | 1.85%   |
| JMicron Technology  | 1         | 1      | 1.85%   |
| IBM                 | 1         | 1      | 1.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 16     | 16%     |
| Kingston            | 7         | 9      | 14%     |
| Crucial             | 4         | 4      | 8%      |
| WDC                 | 3         | 4      | 6%      |
| SPCC                | 3         | 3      | 6%      |
| SanDisk             | 3         | 3      | 6%      |
| Intel               | 3         | 4      | 6%      |
| OCZ                 | 2         | 2      | 4%      |
| LITEON              | 2         | 2      | 4%      |
| SK hynix            | 1         | 1      | 2%      |
| Secure              | 1         | 1      | 2%      |
| Netac               | 1         | 1      | 2%      |
| Micron Technology   | 1         | 1      | 2%      |
| KingSpec            | 1         | 1      | 2%      |
| KC600               | 1         | 1      | 2%      |
| Intenso             | 1         | 1      | 2%      |
| INNOVATION IT       | 1         | 1      | 2%      |
| Emtec               | 1         | 1      | 2%      |
| Dell                | 1         | 2      | 2%      |
| Corsair             | 1         | 2      | 2%      |
| China               | 1         | 1      | 2%      |
| Aura                | 1         | 1      | 2%      |
| AMD                 | 1         | 1      | 2%      |
| A-DATA Technology   | 1         | 1      | 2%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 51        | 72     | 39.23%  |
| SSD  | 39        | 64     | 30%     |
| NVMe | 31        | 57     | 23.85%  |
| MMC  | 9         | 10     | 6.92%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 80        | 129    | 63.49%  |
| NVMe | 31        | 57     | 24.6%   |
| MMC  | 9         | 10     | 7.14%   |
| SAS  | 6         | 7      | 4.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 60        | 84     | 66.67%  |
| 0.51-1.0   | 23        | 29     | 25.56%  |
| 1.01-2.0   | 3         | 5      | 3.33%   |
| 4.01-10.0  | 3         | 14     | 3.33%   |
| 3.01-4.0   | 1         | 4      | 1.11%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 36        | 30.77%  |
| 1-20           | 18        | 15.38%  |
| 251-500        | 15        | 12.82%  |
| 501-1000       | 11        | 9.4%    |
| Unknown        | 11        | 9.4%    |
| 21-50          | 9         | 7.69%   |
| More than 3000 | 6         | 5.13%   |
| 1001-2000      | 5         | 4.27%   |
| 51-100         | 5         | 4.27%   |
| 2001-3000      | 1         | 0.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 74        | 63.25%  |
| Unknown   | 11        | 9.4%    |
| 21-50     | 10        | 8.55%   |
| 51-100    | 9         | 7.69%   |
| 101-250   | 4         | 3.42%   |
| 501-1000  | 4         | 3.42%   |
| 251-500   | 2         | 1.71%   |
| 1001-2000 | 2         | 1.71%   |
| 2001-3000 | 1         | 0.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD10SPZX-80Z10T2 1TB                       | 1         | 1      | 5.56%   |
| Toshiba MK4009GAL 40GB                         | 1         | 1      | 5.56%   |
| Secure Net 256GB SSD                           | 1         | 1      | 5.56%   |
| Seagate ST9250315AS 250GB                      | 1         | 1      | 5.56%   |
| Seagate ST320LT007-9ZV14 320GB                 | 1         | 2      | 5.56%   |
| Seagate ST2000LM015-2E81 2TB                   | 1         | 1      | 5.56%   |
| Samsung Electronics HM160HI 160GB              | 1         | 2      | 5.56%   |
| Netac SSD 256GB                                | 1         | 1      | 5.56%   |
| Micron Technology 1100_MTFDDAK256TBN 256GB SSD | 1         | 1      | 5.56%   |
| Hitachi HTS725025A9A364 250GB                  | 1         | 1      | 5.56%   |
| Hitachi HTS723232A7A364 320GB                  | 1         | 1      | 5.56%   |
| Hitachi HTS72101 99GB                          | 1         | 1      | 5.56%   |
| Hitachi HTS542516K9SA00 160GB                  | 1         | 1      | 5.56%   |
| Hitachi HTC426040G9AT00 40GB                   | 1         | 1      | 5.56%   |
| HGST HTS721010A9E630 1TB                       | 1         | 1      | 5.56%   |
| HGST HTS545050A7E380 500GB                     | 1         | 1      | 5.56%   |
| Corsair Force LE SSD 120GB                     | 1         | 2      | 5.56%   |
| A-DATA Technology IM2P33F8ABR1-1TB             | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 5         | 5      | 27.78%  |
| Seagate             | 3         | 4      | 16.67%  |
| HGST                | 2         | 2      | 11.11%  |
| WDC                 | 1         | 1      | 5.56%   |
| Toshiba             | 1         | 1      | 5.56%   |
| Secure              | 1         | 1      | 5.56%   |
| Samsung Electronics | 1         | 2      | 5.56%   |
| Netac               | 1         | 1      | 5.56%   |
| Micron Technology   | 1         | 1      | 5.56%   |
| Corsair             | 1         | 2      | 5.56%   |
| A-DATA Technology   | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 5         | 5      | 38.46%  |
| Seagate             | 3         | 4      | 23.08%  |
| HGST                | 2         | 2      | 15.38%  |
| WDC                 | 1         | 1      | 7.69%   |
| Toshiba             | 1         | 1      | 7.69%   |
| Samsung Electronics | 1         | 2      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 15     | 76.47%  |
| SSD  | 3         | 5      | 17.65%  |
| NVMe | 1         | 1      | 5.88%   |

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
| Works    | 70        | 132    | 55.56%  |
| Detected | 40        | 50     | 31.75%  |
| Malfunc  | 16        | 21     | 12.7%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 77        | 57.89%  |
| AMD                              | 16        | 12.03%  |
| Samsung Electronics              | 9         | 6.77%   |
| Toshiba America Info Systems     | 6         | 4.51%   |
| SanDisk                          | 5         | 3.76%   |
| SK hynix                         | 4         | 3.01%   |
| Realtek Semiconductor            | 3         | 2.26%   |
| Micron Technology                | 3         | 2.26%   |
| ADATA Technology                 | 3         | 2.26%   |
| Nvidia                           | 2         | 1.5%    |
| VIA Technologies                 | 1         | 0.75%   |
| Silicon Integrated Systems [SiS] | 1         | 0.75%   |
| Marvell Technology Group         | 1         | 0.75%   |
| Kingston Technology Company      | 1         | 0.75%   |
| Broadcom / LSI                   | 1         | 0.75%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 15        | 8.98%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 5.39%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 6         | 3.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 2.99%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 2.99%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 5         | 2.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 2.99%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 2.4%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 4         | 2.4%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 2.4%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 2.4%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 3         | 1.8%    |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 1.8%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 1.8%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 1.8%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 1.8%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 3         | 1.8%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 3         | 1.8%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 1.8%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 1.8%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 1.8%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 1.8%    |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 1.2%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 2         | 1.2%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.2%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 1.2%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 2         | 1.2%    |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                              | 2         | 1.2%    |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 1.2%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.2%    |
| Intel Alder Lake-P SATA AHCI Controller                                        | 2         | 1.2%    |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2         | 1.2%    |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 2         | 1.2%    |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 0.6%    |
| VIA VT8237A SATA 2-Port Controller                                             | 1         | 0.6%    |
| SK hynix PC611 NVMe Solid State Drive                                          | 1         | 0.6%    |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                              | 1         | 0.6%    |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 1         | 0.6%    |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 1         | 0.6%    |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 78        | 60%     |
| NVMe | 30        | 23.08%  |
| IDE  | 17        | 13.08%  |
| RAID | 5         | 3.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 94        | 81.74%  |
| AMD    | 19        | 16.52%  |
| ARM    | 2         | 1.74%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 3.2%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 2.4%    |
| Intel Pentium M processor 1.70GHz             | 2         | 1.6%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.6%    |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 1.6%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.6%    |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 1.6%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 1.6%    |
| Intel Atom CPU N455 @ 1.66GHz                 | 2         | 1.6%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.6%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.6%    |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 1.6%    |
| Intel Xeon Gold 6336Y CPU @ 2.40GHz           | 1         | 0.8%    |
| Intel Xeon Gold 5218 CPU @ 2.30GHz            | 1         | 0.8%    |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 1         | 0.8%    |
| Intel Xeon CPU E5-2640 v4 @ 2.40GHz           | 1         | 0.8%    |
| Intel Pentium M processor 1.60GHz             | 1         | 0.8%    |
| Intel Pentium M processor 1.50GHz             | 1         | 0.8%    |
| Intel Pentium III (Coppermine)                | 1         | 0.8%    |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 1         | 0.8%    |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 0.8%    |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.8%    |
| Intel Mobile Pentium MMX                      | 1         | 0.8%    |
| Intel Genuine CPU T2400 @ 1.83GHz             | 1         | 0.8%    |
| Intel Core Ultra 9 185H                       | 1         | 0.8%    |
| Intel Core Solo CPU U1500 @ 1.33GHz           | 1         | 0.8%    |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 1         | 0.8%    |
| Intel Core i9-9980HK CPU @ 2.40GHz            | 1         | 0.8%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 0.8%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.8%    |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 0.8%    |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 0.8%    |
| Intel Core i7-4790 CPU @ 3.60GHz              | 1         | 0.8%    |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 0.8%    |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 0.8%    |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 0.8%    |
| Intel Core i7-10610U CPU @ 1.80GHz            | 1         | 0.8%    |
| Intel Core i7 CPU Q 820 @ 1.73GHz             | 1         | 0.8%    |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 0.8%    |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 0.8%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 25        | 20.49%  |
| Intel Core i7        | 14        | 11.48%  |
| Other                | 10        | 8.2%    |
| Intel Core i3        | 9         | 7.38%   |
| Intel Core 2 Duo     | 9         | 7.38%   |
| Intel Celeron        | 9         | 7.38%   |
| Intel Atom           | 7         | 5.74%   |
| AMD Ryzen 5          | 6         | 4.92%   |
| Intel Pentium M      | 4         | 3.28%   |
| AMD A6               | 3         | 2.46%   |
| Intel Xeon           | 2         | 1.64%   |
| Intel Pentium        | 2         | 1.64%   |
| AMD Ryzen 7          | 2         | 1.64%   |
| AMD Ryzen 3          | 2         | 1.64%   |
| AMD A4               | 2         | 1.64%   |
| Intel Xeon Gold      | 1         | 0.82%   |
| Intel Pentium III    | 1         | 0.82%   |
| Intel Pentium Dual   | 1         | 0.82%   |
| Intel Genuine        | 1         | 0.82%   |
| Intel Core Solo      | 1         | 0.82%   |
| Intel Core m3        | 1         | 0.82%   |
| Intel Core i9        | 1         | 0.82%   |
| Intel Core Duo       | 1         | 0.82%   |
| Intel Core 2         | 1         | 0.82%   |
| Intel Core           | 1         | 0.82%   |
| ARM ARMv7            | 1         | 0.82%   |
| AMD Turion 64 Mobile | 1         | 0.82%   |
| AMD Ryzen 9          | 1         | 0.82%   |
| AMD FX               | 1         | 0.82%   |
| AMD E2               | 1         | 0.82%   |
| AMD A10              | 1         | 0.82%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 58        | 47.93%  |
| 4       | 35        | 28.93%  |
| 1       | 13        | 10.74%  |
| 6       | 4         | 3.31%   |
| 10      | 2         | 1.65%   |
| 8       | 2         | 1.65%   |
| 48      | 1         | 0.83%   |
| 32      | 1         | 0.83%   |
| 16      | 1         | 0.83%   |
| 14      | 1         | 0.83%   |
| 12      | 1         | 0.83%   |
| 3       | 1         | 0.83%   |
| Unknown | 1         | 0.83%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 113       | 98.26%  |
| 2       | 1         | 0.87%   |
| Unknown | 1         | 0.87%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 65        | 56.52%  |
| 1       | 49        | 42.61%  |
| Unknown | 1         | 0.87%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 59        | 50.86%  |
| Unknown        | 54        | 46.55%  |
| 32-bit         | 3         | 2.59%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 78        | 62.9%   |
| 0x306a9    | 3         | 2.42%   |
| 0x30678    | 3         | 2.42%   |
| 0x20655    | 3         | 2.42%   |
| 0x106ca    | 3         | 2.42%   |
| 0x08108109 | 3         | 2.42%   |
| 0x906ea    | 2         | 1.61%   |
| 0x806eb    | 2         | 1.61%   |
| 0x806c1    | 2         | 1.61%   |
| 0x306c3    | 2         | 1.61%   |
| 0x206a7    | 2         | 1.61%   |
| 0x06006704 | 2         | 1.61%   |
| 0xa0671    | 1         | 0.81%   |
| 0xa0652    | 1         | 0.81%   |
| 0x906a3    | 1         | 0.81%   |
| 0x806ec    | 1         | 0.81%   |
| 0x806ea    | 1         | 0.81%   |
| 0x706e5    | 1         | 0.81%   |
| 0x683      | 1         | 0.81%   |
| 0x606a6    | 1         | 0.81%   |
| 0x506c9    | 1         | 0.81%   |
| 0x406c4    | 1         | 0.81%   |
| 0x306d4    | 1         | 0.81%   |
| 0x106e5    | 1         | 0.81%   |
| 0x1067a    | 1         | 0.81%   |
| 0x08701030 | 1         | 0.81%   |
| 0x08608103 | 1         | 0.81%   |
| 0x08108102 | 1         | 0.81%   |
| 0x0810100b | 1         | 0.81%   |
| 0x0700010f | 1         | 0.81%   |
| 0x06006705 | 1         | 0.81%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 20        | 16.26%  |
| P6               | 8         | 6.5%    |
| Silvermont       | 7         | 5.69%   |
| Penryn           | 7         | 5.69%   |
| Haswell          | 7         | 5.69%   |
| Broadwell        | 6         | 4.88%   |
| Unknown          | 6         | 4.88%   |
| Westmere         | 5         | 4.07%   |
| SandyBridge      | 5         | 4.07%   |
| Bonnell          | 5         | 4.07%   |
| Zen+             | 4         | 3.25%   |
| TigerLake        | 4         | 3.25%   |
| Skylake          | 4         | 3.25%   |
| IvyBridge        | 4         | 3.25%   |
| Goldmont         | 4         | 3.25%   |
| Excavator        | 4         | 3.25%   |
| Core             | 4         | 3.25%   |
| Alderlake Hybrid | 3         | 2.44%   |
| Zen 2            | 2         | 1.63%   |
| Zen              | 2         | 1.63%   |
| Jaguar           | 2         | 1.63%   |
| Icelake          | 2         | 1.63%   |
| Goldmont plus    | 2         | 1.63%   |
| Zen 3            | 1         | 0.81%   |
| Puma             | 1         | 0.81%   |
| Piledriver       | 1         | 0.81%   |
| Nehalem          | 1         | 0.81%   |
| K8 Hammer        | 1         | 0.81%   |
| Bobcat           | 1         | 0.81%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 82        | 60.29%  |
| AMD                        | 29        | 21.32%  |
| Nvidia                     | 20        | 14.71%  |
| Neomagic                   | 2         | 1.47%   |
| VIA Technologies           | 1         | 0.74%   |
| Matrox Electronics Systems | 1         | 0.74%   |
| ASPEED Technology          | 1         | 0.74%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 8         | 4.71%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 2.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 2.94%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 2.35%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 2.35%   |
| Intel HD Graphics 5500                                                                   | 4         | 2.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 2.35%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 2.35%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 2.35%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 2.35%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 2.35%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 1.76%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 1.76%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 3         | 1.76%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.76%   |
| Intel HD Graphics 500                                                                    | 3         | 1.76%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.76%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.76%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 1.76%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.76%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 1.18%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.18%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 1.18%   |
| Intel HD Graphics 630                                                                    | 2         | 1.18%   |
| Intel HD Graphics 620                                                                    | 2         | 1.18%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.18%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 1.18%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                                  | 2         | 1.18%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 2         | 1.18%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 1.18%   |
| AMD Lucienne                                                                             | 2         | 1.18%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2         | 1.18%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 1.18%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 0.59%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.59%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.59%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.59%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.59%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 55        | 46.22%  |
| 1 x AMD         | 23        | 19.33%  |
| Intel + Nvidia  | 16        | 13.45%  |
| 2 x Intel       | 8         | 6.72%   |
| Intel + AMD     | 5         | 4.2%    |
| 1 x Nvidia      | 3         | 2.52%   |
| Other           | 2         | 1.68%   |
| 1 x Neomagic    | 2         | 1.68%   |
| 2 x AMD         | 1         | 0.84%   |
| 1 x VIA         | 1         | 0.84%   |
| Nvidia + Matrox | 1         | 0.84%   |
| 1 x ASPEED      | 1         | 0.84%   |
| AMD + Nvidia    | 1         | 0.84%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 106       | 91.38%  |
| Unknown     | 8         | 6.9%    |
| Proprietary | 2         | 1.72%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 96        | 82.76%  |
| 0.01-0.5   | 9         | 7.76%   |
| 1.01-2.0   | 7         | 6.03%   |
| 0.51-1.0   | 2         | 1.72%   |
| 3.01-4.0   | 1         | 0.86%   |
| 2.01-3.0   | 1         | 0.86%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 26        | 21.14%  |
| LG Display              | 21        | 17.07%  |
| BOE                     | 16        | 13.01%  |
| Chimei Innolux          | 10        | 8.13%   |
| Samsung Electronics     | 7         | 5.69%   |
| LG Philips              | 4         | 3.25%   |
| Lenovo                  | 4         | 3.25%   |
| InfoVision              | 3         | 2.44%   |
| Chi Mei Optoelectronics | 3         | 2.44%   |
| Apple                   | 3         | 2.44%   |
| Sharp                   | 2         | 1.63%   |
| HannStar                | 2         | 1.63%   |
| Goldstar                | 2         | 1.63%   |
| CSO                     | 2         | 1.63%   |
| BenQ                    | 2         | 1.63%   |
| Vizio                   | 1         | 0.81%   |
| Sony                    | 1         | 0.81%   |
| Sceptre Tech            | 1         | 0.81%   |
| Quanta Display          | 1         | 0.81%   |
| Philips                 | 1         | 0.81%   |
| PANDA                   | 1         | 0.81%   |
| ONN                     | 1         | 0.81%   |
| KVM                     | 1         | 0.81%   |
| Envision                | 1         | 0.81%   |
| Element                 | 1         | 0.81%   |
| DENON                   | 1         | 0.81%   |
| Dell                    | 1         | 0.81%   |
| CPT                     | 1         | 0.81%   |
| CHD                     | 1         | 0.81%   |
| ASUSTek Computer        | 1         | 0.81%   |
| Acer                    | 1         | 0.81%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0597 1920x1080 294x165mm 13.3-inch          | 4         | 2.8%    |
| BOE LCD Monitor BOE08D5 1920x1080 344x194mm 15.5-inch                 | 3         | 2.1%    |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 1.4%    |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 2         | 1.4%    |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                 | 2         | 1.4%    |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch         | 2         | 1.4%    |
| Vizio D43f-J04 VIZ1044 1920x1080 527x296mm 23.8-inch                  | 1         | 0.7%    |
| Sony LCD Monitor SNY06FA 1600x900 380x210mm 17.1-inch                 | 1         | 0.7%    |
| Sharp LCD Monitor SHP1513 1920x1080 309x174mm 14.0-inch               | 1         | 0.7%    |
| Sharp LCD Monitor SHP14AE 1920x1080 294x165mm 13.3-inch               | 1         | 0.7%    |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 526x296mm 23.8-inch        | 1         | 0.7%    |
| Samsung Electronics SyncMaster SAM0320 1680x1050 474x296mm 22.0-inch  | 1         | 0.7%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC5A42 1366x768 309x174mm 14.0-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC5642 1280x768 305x183mm 14.0-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SDC4147 3840x2160 294x165mm 13.3-inch | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch  | 1         | 0.7%    |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch   | 1         | 0.7%    |
| Quanta Display LCD Monitor QDS0020 1280x768 305x183mm 14.0-inch       | 1         | 0.7%    |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch               | 1         | 0.7%    |
| PANDA LCD Monitor NCP0056 1920x1080 309x174mm 14.0-inch               | 1         | 0.7%    |
| ONN 100002487 ONN0101 1920x1080 517x323mm 24.0-inch                   | 1         | 0.7%    |
| LG Philips LCD Monitor LPLE300 1280x800 331x207mm 15.4-inch           | 1         | 0.7%    |
| LG Philips LCD Monitor LPLE100 1280x800 331x207mm 15.4-inch           | 1         | 0.7%    |
| LG Philips LCD Monitor LPLB600 1280x800 260x160mm 12.0-inch           | 1         | 0.7%    |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch           | 1         | 0.7%    |
| LG Display LP116WH2-TLC1 LGD0232 1366x768 256x144mm 11.6-inch         | 1         | 0.7%    |
| LG Display LCD Monitor LGD7001 1366x768 344x194mm 15.5-inch           | 1         | 0.7%    |
| LG Display LCD Monitor LGD0782 2880x1800 302x189mm 14.0-inch          | 1         | 0.7%    |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 1         | 0.7%    |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 0.7%    |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch          | 1         | 0.7%    |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch           | 1         | 0.7%    |
| LG Display LCD Monitor LGD0446 1920x1080 309x174mm 14.0-inch          | 1         | 0.7%    |
| LG Display LCD Monitor LGD042E 2560x1700 272x181mm 12.9-inch          | 1         | 0.7%    |
| LG Display LCD Monitor LGD03EE 1366x768 277x156mm 12.5-inch           | 1         | 0.7%    |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch           | 1         | 0.7%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 1         | 0.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 39        | 33.05%  |
| 1920x1080 (FHD)    | 34        | 28.81%  |
| 1280x800 (WXGA)    | 9         | 7.63%   |
| 1600x900 (HD+)     | 5         | 4.24%   |
| 3840x2160 (4K)     | 4         | 3.39%   |
| 1024x600           | 4         | 3.39%   |
| 2880x1800          | 3         | 2.54%   |
| 2560x1440 (QHD)    | 3         | 2.54%   |
| 2560x1080          | 2         | 1.69%   |
| 1920x1200 (WUXGA)  | 2         | 1.69%   |
| 1440x900 (WXGA+)   | 2         | 1.69%   |
| 1280x768           | 2         | 1.69%   |
| 1280x1024 (SXGA)   | 2         | 1.69%   |
| 3440x1440          | 1         | 0.85%   |
| 2560x1700          | 1         | 0.85%   |
| 2560x1600          | 1         | 0.85%   |
| 2240x1400          | 1         | 0.85%   |
| 1680x1050 (WSXGA+) | 1         | 0.85%   |
| 1360x768           | 1         | 0.85%   |
| 1024x768 (XGA)     | 1         | 0.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 40        | 32.52%  |
| 13     | 20        | 16.26%  |
| 14     | 16        | 13.01%  |
| 17     | 9         | 7.32%   |
| 11     | 7         | 5.69%   |
| 12     | 6         | 4.88%   |
| 10     | 4         | 3.25%   |
| 31     | 3         | 2.44%   |
| 32     | 2         | 1.63%   |
| 23     | 2         | 1.63%   |
| 21     | 2         | 1.63%   |
| 72     | 1         | 0.81%   |
| 60     | 1         | 0.81%   |
| 40     | 1         | 0.81%   |
| 34     | 1         | 0.81%   |
| 29     | 1         | 0.81%   |
| 27     | 1         | 0.81%   |
| 25     | 1         | 0.81%   |
| 24     | 1         | 0.81%   |
| 22     | 1         | 0.81%   |
| 20     | 1         | 0.81%   |
| 19     | 1         | 0.81%   |
| 16     | 1         | 0.81%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 64        | 55.65%  |
| 201-300     | 28        | 24.35%  |
| 351-400     | 10        | 8.7%    |
| 601-700     | 4         | 3.48%   |
| 701-800     | 2         | 1.74%   |
| 501-600     | 2         | 1.74%   |
| 401-500     | 2         | 1.74%   |
| 801-900     | 1         | 0.87%   |
| 1501-2000   | 1         | 0.87%   |
| 1001-1500   | 1         | 0.87%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 84        | 78.5%   |
| 16/10 | 17        | 15.89%  |
| 5/4   | 2         | 1.87%   |
| 21/9  | 2         | 1.87%   |
| 4/3   | 1         | 0.93%   |
| 3/2   | 1         | 0.93%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 40        | 34.48%  |
| 81-90          | 27        | 23.28%  |
| 71-80          | 10        | 8.62%   |
| 51-60          | 7         | 6.03%   |
| 121-130        | 7         | 6.03%   |
| 61-70          | 5         | 4.31%   |
| 351-500        | 4         | 3.45%   |
| 41-50          | 4         | 3.45%   |
| More than 1000 | 2         | 1.72%   |
| 301-350        | 2         | 1.72%   |
| 201-250        | 2         | 1.72%   |
| 151-200        | 2         | 1.72%   |
| 251-300        | 1         | 0.86%   |
| 141-150        | 1         | 0.86%   |
| 131-140        | 1         | 0.86%   |
| 501-1000       | 1         | 0.86%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 42        | 38.18%  |
| 101-120       | 37        | 33.64%  |
| 51-100        | 15        | 13.64%  |
| 161-240       | 9         | 8.18%   |
| More than 240 | 4         | 3.64%   |
| 1-50          | 3         | 2.73%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 99        | 84.62%  |
| 0     | 9         | 7.69%   |
| 2     | 8         | 6.84%   |
| 3     | 1         | 0.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 65        | 34.39%  |
| Intel                             | 58        | 30.69%  |
| Qualcomm Atheros                  | 26        | 13.76%  |
| Broadcom                          | 13        | 6.88%   |
| Marvell Technology Group          | 6         | 3.17%   |
| Broadcom Limited                  | 3         | 1.59%   |
| LSI                               | 2         | 1.06%   |
| VIA Technologies                  | 1         | 0.53%   |
| TP-Link                           | 1         | 0.53%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.53%   |
| Samsung Electronics               | 1         | 0.53%   |
| Qualcomm Atheros Communications   | 1         | 0.53%   |
| Qualcomm                          | 1         | 0.53%   |
| Nvidia                            | 1         | 0.53%   |
| NetGear                           | 1         | 0.53%   |
| Mellanox Technologies             | 1         | 0.53%   |
| MediaTek                          | 1         | 0.53%   |
| Google                            | 1         | 0.53%   |
| Ericsson Business Mobile Networks | 1         | 0.53%   |
| Dresden Elektronik                | 1         | 0.53%   |
| DisplayLink                       | 1         | 0.53%   |
| ASIX Electronics                  | 1         | 0.53%   |
| AMD                               | 1         | 0.53%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 30        | 12.61%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 17        | 7.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 11        | 4.62%   |
| Intel Wireless 7265                                                    | 8         | 3.36%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 6         | 2.52%   |
| Intel Wireless 8265 / 8275                                             | 5         | 2.1%    |
| Intel Wi-Fi 6 AX200                                                    | 5         | 2.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 4         | 1.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 4         | 1.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 4         | 1.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 4         | 1.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 1.68%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 4         | 1.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3         | 1.26%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 3         | 1.26%   |
| Intel Wireless 3160                                                    | 3         | 1.26%   |
| Intel Wi-Fi 6 AX201                                                    | 3         | 1.26%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 3         | 1.26%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 1.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 3         | 1.26%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 3         | 1.26%   |
| Broadcom BCM43224 802.11a/b/g/n                                        | 3         | 1.26%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 2         | 0.84%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 0.84%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 2         | 0.84%   |
| Intel Ultimate N WiFi Link 5300                                        | 2         | 0.84%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection          | 2         | 0.84%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection               | 2         | 0.84%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2         | 0.84%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 2         | 0.84%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2         | 0.84%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller       | 2         | 0.84%   |
| Intel 82579V Gigabit Network Connection                                | 2         | 0.84%   |
| Broadcom Limited BCM4352 802.11ac Dual Band Wireless Network Adapter   | 2         | 0.84%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1         | 0.42%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                    | 1         | 0.42%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1         | 0.42%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.42%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 1         | 0.42%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 1         | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 53        | 46.9%   |
| Qualcomm Atheros                | 25        | 22.12%  |
| Realtek Semiconductor           | 16        | 14.16%  |
| Broadcom                        | 11        | 9.73%   |
| Broadcom Limited                | 3         | 2.65%   |
| TP-Link                         | 1         | 0.88%   |
| Qualcomm Atheros Communications | 1         | 0.88%   |
| NetGear                         | 1         | 0.88%   |
| MediaTek                        | 1         | 0.88%   |
| Marvell Technology Group        | 1         | 0.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 11        | 8.94%   |
| Intel Wireless 7265                                                            | 8         | 6.5%    |
| Intel Wireless 8265 / 8275                                                     | 5         | 4.07%   |
| Intel Wi-Fi 6 AX200                                                            | 5         | 4.07%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 4         | 3.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 4         | 3.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 4         | 3.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 4         | 3.25%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 4         | 3.25%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 3         | 2.44%   |
| Intel Wireless 3160                                                            | 3         | 2.44%   |
| Intel Wi-Fi 6 AX201                                                            | 3         | 2.44%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 3         | 2.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                              | 3         | 2.44%   |
| Broadcom BCM43224 802.11a/b/g/n                                                | 3         | 2.44%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 2         | 1.63%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                        | 2         | 1.63%   |
| Intel Ultimate N WiFi Link 5300                                                | 2         | 1.63%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 2         | 1.63%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                       | 2         | 1.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 2         | 1.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 2         | 1.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 2         | 1.63%   |
| Intel Alder Lake-P PCH CNVi WiFi                                               | 2         | 1.63%   |
| Broadcom Limited BCM4352 802.11ac Dual Band Wireless Network Adapter           | 2         | 1.63%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                            | 1         | 0.81%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                       | 1         | 0.81%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 1         | 0.81%   |
| Realtek RTL8723DE Wireless Network Adapter                                     | 1         | 0.81%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                     | 1         | 0.81%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 1         | 0.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 1         | 0.81%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 0.81%   |
| Realtek RTL8187 Wireless Adapter                                               | 1         | 0.81%   |
| Qualcomm Atheros AR9271 802.11n                                                | 1         | 0.81%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1         | 0.81%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1         | 0.81%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                          | 1         | 0.81%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 1         | 0.81%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]                          | 1         | 0.81%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 55        | 57.29%  |
| Intel                            | 20        | 20.83%  |
| Marvell Technology Group         | 5         | 5.21%   |
| Broadcom                         | 4         | 4.17%   |
| Qualcomm Atheros                 | 3         | 3.13%   |
| VIA Technologies                 | 1         | 1.04%   |
| Silicon Integrated Systems [SiS] | 1         | 1.04%   |
| Samsung Electronics              | 1         | 1.04%   |
| Qualcomm                         | 1         | 1.04%   |
| Nvidia                           | 1         | 1.04%   |
| Mellanox Technologies            | 1         | 1.04%   |
| LSI                              | 1         | 1.04%   |
| DisplayLink                      | 1         | 1.04%   |
| ASIX Electronics                 | 1         | 1.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 30        | 28.04%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 17        | 15.89%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 6         | 5.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4         | 3.74%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 3         | 2.8%    |
| Intel Ethernet Connection (4) I219-LM                                          | 3         | 2.8%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 1.87%   |
| Intel 82579V Gigabit Network Connection                                        | 2         | 1.87%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 1         | 0.93%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 1         | 0.93%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.93%   |
| Realtek USB 10/100/1G/2.5G LAN                                                 | 1         | 0.93%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.93%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.93%   |
| Realtek Killer E2600 GbE Controller                                            | 1         | 0.93%   |
| Qualcomm POCO F3                                                               | 1         | 0.93%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.93%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.93%   |
| Mellanox MT28908 Family [ConnectX-6]                                           | 1         | 0.93%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.93%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 1         | 0.93%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.93%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.93%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 1         | 0.93%   |
| LSI ET-131x PCI-E Ethernet Controller                                          | 1         | 0.93%   |
| Intel WiMAX Connection 2400m                                                   | 1         | 0.93%   |
| Intel Ethernet Controller 10G X550T                                            | 1         | 0.93%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.93%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.93%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.93%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.93%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 0.93%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 0.93%   |
| Intel Ethernet Connection (2) I218-V                                           | 1         | 0.93%   |
| Intel Ethernet Connection (13) I219-LM                                         | 1         | 0.93%   |
| Intel Alder Lake-P PCH CNVi WiFi                                               | 1         | 0.93%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.93%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 0.93%   |
| Intel 82567LF Gigabit Network Connection                                       | 1         | 0.93%   |
| Intel 82566MM Gigabit Network Connection                                       | 1         | 0.93%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 106       | 53.27%  |
| Ethernet | 85        | 42.71%  |
| Modem    | 8         | 4.02%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 82        | 70.09%  |
| Ethernet | 35        | 29.91%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 77        | 66.38%  |
| 1     | 34        | 29.31%  |
| 0     | 5         | 4.31%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 88        | 76.52%  |
| Yes  | 27        | 23.48%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 34        | 40.48%  |
| Realtek Semiconductor           | 10        | 11.9%   |
| Qualcomm Atheros Communications | 9         | 10.71%  |
| IMC Networks                    | 5         | 5.95%   |
| Broadcom                        | 5         | 5.95%   |
| Foxconn / Hon Hai               | 4         | 4.76%   |
| Apple                           | 4         | 4.76%   |
| Lite-On Technology              | 3         | 3.57%   |
| ASUSTek Computer                | 2         | 2.38%   |
| Toshiba                         | 1         | 1.19%   |
| Marvell Semiconductor           | 1         | 1.19%   |
| Hewlett-Packard                 | 1         | 1.19%   |
| Edimax Technology               | 1         | 1.19%   |
| Dell                            | 1         | 1.19%   |
| Cambridge Silicon Radio         | 1         | 1.19%   |
| Askey Computer                  | 1         | 1.19%   |
| Alps Electric                   | 1         | 1.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 16        | 18.39%  |
| Realtek Bluetooth Radio                                                             | 7         | 8.05%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 6         | 6.9%    |
| Intel AX201 Bluetooth                                                               | 6         | 6.9%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 5         | 5.75%   |
| Intel AX200 Bluetooth                                                               | 4         | 4.6%    |
| Apple Bluetooth Host Controller                                                     | 3         | 3.45%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 2.3%    |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 2.3%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 2.3%    |
| IMC Networks Bluetooth Radio                                                        | 2         | 2.3%    |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth                                     | 2         | 2.3%    |
| Toshiba Bluetooth Device                                                            | 1         | 1.15%   |
| Realtek 802.11ac WLAN Adapter                                                       | 1         | 1.15%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 1.15%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.15%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 1.15%   |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 1         | 1.15%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 1.15%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 1.15%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 1.15%   |
| Intel AX211 Bluetooth                                                               | 1         | 1.15%   |
| Intel AX210 Bluetooth                                                               | 1         | 1.15%   |
| IMC Networks Wireless_Device                                                        | 1         | 1.15%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.15%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 1.15%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 1.15%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 1         | 1.15%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.15%   |
| Edimax Bluetooth Adapter                                                            | 1         | 1.15%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 1.15%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 1.15%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 1.15%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 1.15%   |
| Broadcom BCM20702A0                                                                 | 1         | 1.15%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 1.15%   |
| Broadcom BCM2045 Bluetooth                                                          | 1         | 1.15%   |
| ASUS BT-270 Bluetooth Adapter                                                       | 1         | 1.15%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 1         | 1.15%   |
| Askey Bluetooth Device                                                              | 1         | 1.15%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 87        | 70.16%  |
| AMD                              | 23        | 18.55%  |
| Nvidia                           | 5         | 4.03%   |
| VIA Technologies                 | 1         | 0.81%   |
| Texas Instruments                | 1         | 0.81%   |
| SteelSeries ApS                  | 1         | 0.81%   |
| Silicon Integrated Systems [SiS] | 1         | 0.81%   |
| Sennheiser Communications        | 1         | 0.81%   |
| Realtek Semiconductor            | 1         | 0.81%   |
| Logitech                         | 1         | 0.81%   |
| Focusrite-Novation               | 1         | 0.81%   |
| Cirrus Logic                     | 1         | 0.81%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 13        | 7.1%    |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 10        | 5.46%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 4.37%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 3.83%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 3.28%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 3.28%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 2.73%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 2.73%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 2.73%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 2.73%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 2.19%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 2.19%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 2.19%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 2.19%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 2.19%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 2.19%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 2.19%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 2.19%   |
| AMD FCH Azalia Controller                                                                         | 4         | 2.19%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 2.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.64%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 1.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.64%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 1.64%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.64%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 1.64%   |
| AMD High Definition Audio Controller                                                              | 3         | 1.64%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.09%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.09%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 2         | 1.09%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 2         | 1.09%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.55%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.55%   |
| SteelSeries ApS SteelSeries Arctis 7                                                              | 1         | 0.55%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.55%   |
| Sennheiser Communications Sennheiser USB headset                                                  | 1         | 0.55%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.55%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.55%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.55%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 26        | 22.81%  |
| SK hynix            | 23        | 20.18%  |
| Unknown             | 22        | 19.3%   |
| Micron Technology   | 12        | 10.53%  |
| Crucial             | 8         | 7.02%   |
| Elpida              | 5         | 4.39%   |
| A-DATA Technology   | 4         | 3.51%   |
| Kingston            | 3         | 2.63%   |
| Unknown (ABCD)      | 2         | 1.75%   |
| Smart Brazil        | 1         | 0.88%   |
| Ramaxel Technology  | 1         | 0.88%   |
| Nanya Technology    | 1         | 0.88%   |
| Lexar               | 1         | 0.88%   |
| GOODRAM             | 1         | 0.88%   |
| Gold Key            | 1         | 0.88%   |
| G.Skill             | 1         | 0.88%   |
| Corsair             | 1         | 0.88%   |
| Unknown             | 1         | 0.88%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 4         | 2.96%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 3         | 2.22%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 2.22%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 2         | 1.48%   |
| Unknown RAM Module 1GB SODIMM DRAM                               | 2         | 1.48%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 2         | 1.48%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 2         | 1.48%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 2         | 1.48%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.48%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1333MT/s            | 2         | 1.48%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 2         | 1.48%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.48%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.48%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.48%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s            | 2         | 1.48%   |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 0.74%   |
| Unknown RAM Module 512MB SODIMM DRAM                             | 1         | 0.74%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.74%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.74%   |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 1         | 0.74%   |
| Unknown RAM Module 2GB SODIMM LPDDR4 2133MT/s                    | 1         | 0.74%   |
| Unknown RAM Module 256MB SODIMM DDR                              | 1         | 0.74%   |
| Unknown RAM Module 1GB SODIMM LPDDR4 2400MT/s                    | 1         | 0.74%   |
| Unknown RAM Module 1GB SODIMM DDR3 1066MT/s                      | 1         | 0.74%   |
| Unknown RAM Module 1GB SODIMM DDR3                               | 1         | 0.74%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 0.74%   |
| Unknown RAM Module 16GB SODIMM DDR4 2400MT/s                     | 1         | 0.74%   |
| Unknown RAM Module 128MB DIMM DRAM                               | 1         | 0.74%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s     | 1         | 0.74%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.74%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 0.74%   |
| SK hynix RAM HMT425S2AFR6R-PB 2GB SODIMM DDR3 1333MT/s           | 1         | 0.74%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.74%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.74%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.74%   |
| SK hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1600MT/s        | 1         | 0.74%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.74%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 0.74%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.74%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 0.74%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 32        | 35.16%  |
| DDR4   | 26        | 28.57%  |
| LPDDR3 | 11        | 12.09%  |
| DDR2   | 6         | 6.59%   |
| SDRAM  | 4         | 4.4%    |
| LPDDR4 | 4         | 4.4%    |
| DDR    | 4         | 4.4%    |
| DRAM   | 3         | 3.3%    |
| DDR5   | 1         | 1.1%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 75        | 80.65%  |
| Row Of Chips | 12        | 12.9%   |
| Unknown      | 3         | 3.23%   |
| DIMM         | 2         | 2.15%   |
| RIMM         | 1         | 1.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 38        | 36.89%  |
| 8192  | 22        | 21.36%  |
| 2048  | 14        | 13.59%  |
| 1024  | 11        | 10.68%  |
| 16384 | 10        | 9.71%   |
| 512   | 5         | 4.85%   |
| 32768 | 1         | 0.97%   |
| 256   | 1         | 0.97%   |
| 128   | 1         | 0.97%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 18        | 17.14%  |
| 2667    | 12        | 11.43%  |
| Unknown | 12        | 11.43%  |
| 3200    | 9         | 8.57%   |
| 2400    | 9         | 8.57%   |
| 1867    | 9         | 8.57%   |
| 1334    | 7         | 6.67%   |
| 2133    | 6         | 5.71%   |
| 1067    | 4         | 3.81%   |
| 667     | 4         | 3.81%   |
| 1333    | 3         | 2.86%   |
| 3266    | 2         | 1.9%    |
| 1066    | 2         | 1.9%    |
| 8400    | 1         | 0.95%   |
| 6000    | 1         | 0.95%   |
| 4800    | 1         | 0.95%   |
| 4199    | 1         | 0.95%   |
| 3800    | 1         | 0.95%   |
| 1400    | 1         | 0.95%   |
| 1200    | 1         | 0.95%   |
| 533     | 1         | 0.95%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| HP LaserJet 1020 | 1         | 50%     |
| HP Deskjet 3050A | 1         | 50%     |

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
| Chicony Electronics                    | 23        | 21.7%   |
| Realtek Semiconductor                  | 14        | 13.21%  |
| Microdia                               | 10        | 9.43%   |
| IMC Networks                           | 9         | 8.49%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 8.49%   |
| Quanta                                 | 6         | 5.66%   |
| Bison Electronics                      | 6         | 5.66%   |
| Acer                                   | 4         | 3.77%   |
| Syntek                                 | 3         | 2.83%   |
| Suyin                                  | 3         | 2.83%   |
| Lite-On Technology                     | 3         | 2.83%   |
| Apple                                  | 3         | 2.83%   |
| Sunplus Innovation Technology          | 2         | 1.89%   |
| Silicon Motion                         | 2         | 1.89%   |
| Ricoh                                  | 2         | 1.89%   |
| Lenovo                                 | 2         | 1.89%   |
| Trust                                  | 1         | 0.94%   |
| Samsung Electronics                    | 1         | 0.94%   |
| Luxvisions Innotech Limited            | 1         | 0.94%   |
| Logitech                               | 1         | 0.94%   |
| Alcor Micro                            | 1         | 0.94%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                        | 5         | 4.59%   |
| Microdia Integrated_Webcam_HD                       | 5         | 4.59%   |
| Chicony Integrated Camera                           | 5         | 4.59%   |
| Realtek HP Webcam                                   | 3         | 2.75%   |
| IMC Networks Integrated Camera                      | 3         | 2.75%   |
| Chicony HP Wide Vision HD Camera                    | 3         | 2.75%   |
| Chicony HD Webcam                                   | 3         | 2.75%   |
| Realtek Integrated Webcam                           | 2         | 1.83%   |
| Realtek Acer 640 x 480 laptop camera                | 2         | 1.83%   |
| Quanta HD User Facing                               | 2         | 1.83%   |
| Microdia Laptop_Integrated_Webcam_2M                | 2         | 1.83%   |
| Lite-On TOSHIBA Web Camera - HD                     | 2         | 1.83%   |
| Lenovo Integrated Webcam                            | 2         | 1.83%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 2         | 1.83%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 2         | 1.83%   |
| Chicony 2.0M UVC Webcam / CNF7129                   | 2         | 1.83%   |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 2         | 1.83%   |
| Bison Integrated Camera                             | 2         | 1.83%   |
| Trust QHD Webcam                                    | 1         | 0.92%   |
| Syntek Sonix 1.3MPixel USB 2.0 Camera               | 1         | 0.92%   |
| Syntek Integrated Camera                            | 1         | 0.92%   |
| Syntek EasyCamera                                   | 1         | 0.92%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.92%   |
| Suyin HP TrueVision HD                              | 1         | 0.92%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.92%   |
| Sunplus HP Universal Camera                         | 1         | 0.92%   |
| Sunplus HD WebCam                                   | 1         | 0.92%   |
| Silicon Motion WebCam SC-03FFL11939N                | 1         | 0.92%   |
| Silicon Motion NCM-G102                             | 1         | 0.92%   |
| Samsung Galaxy series, misc. (MTP mode)             | 1         | 0.92%   |
| Ricoh Visual Communication Camera VGP-VCC3 [R5U870] | 1         | 0.92%   |
| Ricoh Pavilion Webcam [R5U870]                      | 1         | 0.92%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 0.92%   |
| Realtek USB Camera                                  | 1         | 0.92%   |
| Realtek Integrated_Webcam_FHD                       | 1         | 0.92%   |
| Quanta USB2.0 HD UVC WebCam                         | 1         | 0.92%   |
| Quanta HP Wide Vision HD Camera                     | 1         | 0.92%   |
| Quanta HP TrueVision HD Camera                      | 1         | 0.92%   |
| Quanta HP HD Camera                                 | 1         | 0.92%   |
| Microdia Webcam                                     | 1         | 0.92%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 28.57%  |
| Synaptics                  | 4         | 28.57%  |
| AuthenTec                  | 3         | 21.43%  |
| STMicroelectronics         | 2         | 14.29%  |
| Shenzhen Goodix Technology | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AuthenTec AES2810                                                          | 3         | 21.43%  |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 14.29%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 14.29%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 14.29%  |
| STMicroelectronics Fingerprint Reader                                      | 2         | 14.29%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 7.14%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 7.14%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 7.14%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 2         | 66.67%  |
| Lenovo      | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 2         | 66.67%  |
| Lenovo Integrated Smart Card Reader | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 64        | 52.03%  |
| 1     | 34        | 27.64%  |
| 2     | 20        | 16.26%  |
| 3     | 3         | 2.44%   |
| 4     | 2         | 1.63%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 23        | 25.84%  |
| Fingerprint reader       | 13        | 14.61%  |
| Modem                    | 8         | 8.99%   |
| Communication controller | 7         | 7.87%   |
| Camera                   | 7         | 7.87%   |
| Bluetooth                | 7         | 7.87%   |
| Net/wireless             | 5         | 5.62%   |
| Card reader              | 5         | 5.62%   |
| Multimedia controller    | 4         | 4.49%   |
| Chipcard                 | 3         | 3.37%   |
| Storage                  | 2         | 2.25%   |
| Unclassified device      | 1         | 1.12%   |
| Unassigned class         | 1         | 1.12%   |
| Sound                    | 1         | 1.12%   |
| Network                  | 1         | 1.12%   |
| Flash memory             | 1         | 1.12%   |


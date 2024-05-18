Alpine - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Alpine.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Alpine/Desktop/README.md) and [notebooks](/Dist/Alpine/Notebook/README.md).

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

Total: 286

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X61 76754KU        | Notebook    | [1a083b94dc](https://linux-hardware.org/?probe=1a083b94dc) | Apr 27, 2024 |
| HP            | Pavilion dv6500             | Notebook    | [339679d475](https://linux-hardware.org/?probe=339679d475) | Apr 22, 2024 |
| Gigabyte      | Z270X-Gaming 8              | Desktop     | [00e056103f](https://linux-hardware.org/?probe=00e056103f) | Apr 22, 2024 |
| ASRock        | B85M-ITX                    | Desktop     | [c868a15a8f](https://linux-hardware.org/?probe=c868a15a8f) | Apr 20, 2024 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [73379ea508](https://linux-hardware.org/?probe=73379ea508) | Apr 13, 2024 |
| Intel         | H81                         | Desktop     | [8b51b58c02](https://linux-hardware.org/?probe=8b51b58c02) | Apr 11, 2024 |
| HP            | 18E7                        | Desktop     | [06187ec68b](https://linux-hardware.org/?probe=06187ec68b) | Apr 09, 2024 |
| HP            | Laptop 15-bw0xx             | Notebook    | [823f3c3138](https://linux-hardware.org/?probe=823f3c3138) | Apr 09, 2024 |
| Dell          | 0CU395                      | Desktop     | [0ba3773be8](https://linux-hardware.org/?probe=0ba3773be8) | Apr 03, 2024 |
| Intel         | H81                         | Desktop     | [c62889d4a5](https://linux-hardware.org/?probe=c62889d4a5) | Apr 02, 2024 |
| Acer          | Nitro AN515-55              | Notebook    | [9b975edbf7](https://linux-hardware.org/?probe=9b975edbf7) | Mar 23, 2024 |
| Inventec      | DQ Class A02                | Desktop     | [6539e1cbe7](https://linux-hardware.org/?probe=6539e1cbe7) | Mar 22, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [2c5499e776](https://linux-hardware.org/?probe=2c5499e776) | Mar 22, 2024 |
| Lenovo        | V15 G3 IAP 82TT             | Notebook    | [fb281cfb94](https://linux-hardware.org/?probe=fb281cfb94) | Mar 18, 2024 |
| MACHINIST     | X99 PR9                     | Desktop     | [481821b9ad](https://linux-hardware.org/?probe=481821b9ad) | Mar 12, 2024 |
| Sony          | VPCEC3A4E                   | Notebook    | [38f3380fcf](https://linux-hardware.org/?probe=38f3380fcf) | Mar 11, 2024 |
| Acer          | Nitro AN515-55              | Notebook    | [98c56ac1d0](https://linux-hardware.org/?probe=98c56ac1d0) | Mar 10, 2024 |
| Intel         | D102GGC2 AAD42789-204       | Desktop     | [0da90b1518](https://linux-hardware.org/?probe=0da90b1518) | Mar 03, 2024 |
| SLIMBOOK      | EXECUTIVE-14                | Notebook    | [39d528dadf](https://linux-hardware.org/?probe=39d528dadf) | Mar 01, 2024 |
| SLIMBOOK      | EXECUTIVE-14                | Notebook    | [5fc24348a8](https://linux-hardware.org/?probe=5fc24348a8) | Mar 01, 2024 |
| HP            | Laptop 15-bw0xx             | Notebook    | [39ed74cf97](https://linux-hardware.org/?probe=39ed74cf97) | Feb 24, 2024 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [340e79c73f](https://linux-hardware.org/?probe=340e79c73f) | Feb 22, 2024 |
| Sony          | VPCEC3A4E                   | Notebook    | [e365c35e91](https://linux-hardware.org/?probe=e365c35e91) | Feb 22, 2024 |
| Unknown       | Unknown                     | Soc         | [17963d5911](https://linux-hardware.org/?probe=17963d5911) | Feb 20, 2024 |
| Acer          | Nitro AN515-55              | Notebook    | [0ee9f9ca69](https://linux-hardware.org/?probe=0ee9f9ca69) | Feb 18, 2024 |
| Sony          | VPCEC3A4E                   | Notebook    | [cc5290daff](https://linux-hardware.org/?probe=cc5290daff) | Feb 18, 2024 |
| Sony          | VPCEC3A4E                   | Notebook    | [b31170da6a](https://linux-hardware.org/?probe=b31170da6a) | Feb 17, 2024 |
| Acer          | TDPS05                      | Desktop     | [9156de5a01](https://linux-hardware.org/?probe=9156de5a01) | Feb 15, 2024 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [f3d4535f87](https://linux-hardware.org/?probe=f3d4535f87) | Feb 13, 2024 |
| AMI           | Intel                       | Desktop     | [15abbc4eb4](https://linux-hardware.org/?probe=15abbc4eb4) | Feb 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [6b61926dd2](https://linux-hardware.org/?probe=6b61926dd2) | Feb 09, 2024 |
| Acer          | Nitro AN515-55              | Notebook    | [1e2603f833](https://linux-hardware.org/?probe=1e2603f833) | Feb 04, 2024 |
| HP            | 158Ch                       | Mini pc     | [2cef0fa0f1](https://linux-hardware.org/?probe=2cef0fa0f1) | Feb 03, 2024 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [dc84848e79](https://linux-hardware.org/?probe=dc84848e79) | Jan 24, 2024 |
| Apple         | MacBook5,1                  | Notebook    | [d3a48ce5b5](https://linux-hardware.org/?probe=d3a48ce5b5) | Jan 24, 2024 |
| Apple         | MacBook5,1                  | Notebook    | [2fa13d832c](https://linux-hardware.org/?probe=2fa13d832c) | Jan 24, 2024 |
| Acer          | Nitro AN515-55              | Notebook    | [876874e8b5](https://linux-hardware.org/?probe=876874e8b5) | Jan 24, 2024 |
| Lenovo        | Y70-70 Touch 80DU           | Notebook    | [fb81d9ccfe](https://linux-hardware.org/?probe=fb81d9ccfe) | Jan 20, 2024 |
| Unknown       | Unknown                     | Desktop     | [413fbae0c9](https://linux-hardware.org/?probe=413fbae0c9) | Jan 17, 2024 |
| Unknown       | Unknown                     | Desktop     | [69d393fc55](https://linux-hardware.org/?probe=69d393fc55) | Jan 17, 2024 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [3f6d4a63ee](https://linux-hardware.org/?probe=3f6d4a63ee) | Jan 09, 2024 |
| HP            | 3397                        | Desktop     | [c33a1d3b01](https://linux-hardware.org/?probe=c33a1d3b01) | Jan 09, 2024 |
| Wortmann      | M660SE                      | Notebook    | [225361b7c3](https://linux-hardware.org/?probe=225361b7c3) | Jan 06, 2024 |
| Acer          | Nitro AN515-55              | Notebook    | [6f9241e288](https://linux-hardware.org/?probe=6f9241e288) | Jan 04, 2024 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [cf4135541d](https://linux-hardware.org/?probe=cf4135541d) | Jan 03, 2024 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [9d5aa2f8ae](https://linux-hardware.org/?probe=9d5aa2f8ae) | Jan 02, 2024 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [db0bed1921](https://linux-hardware.org/?probe=db0bed1921) | Jan 02, 2024 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [018238aa79](https://linux-hardware.org/?probe=018238aa79) | Jan 01, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [cee7f7036e](https://linux-hardware.org/?probe=cee7f7036e) | Dec 31, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [d6121834a4](https://linux-hardware.org/?probe=d6121834a4) | Dec 31, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [7528cb1c24](https://linux-hardware.org/?probe=7528cb1c24) | Dec 30, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [f071a372c0](https://linux-hardware.org/?probe=f071a372c0) | Dec 29, 2023 |
| Acer          | Aspire A515-54              | Notebook    | [ea0b7cd870](https://linux-hardware.org/?probe=ea0b7cd870) | Dec 26, 2023 |
| Acer          | TDPS05                      | Desktop     | [ce9b5d0c48](https://linux-hardware.org/?probe=ce9b5d0c48) | Dec 23, 2023 |
| Acer          | TDPS05                      | Desktop     | [d0260b1327](https://linux-hardware.org/?probe=d0260b1327) | Dec 23, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [2432d4f585](https://linux-hardware.org/?probe=2432d4f585) | Dec 22, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | Notebook    | [d33b5845ef](https://linux-hardware.org/?probe=d33b5845ef) | Dec 20, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [4b404f8509](https://linux-hardware.org/?probe=4b404f8509) | Dec 15, 2023 |
| ZOTAC         | Unknown                     | Desktop     | [a91d567af3](https://linux-hardware.org/?probe=a91d567af3) | Dec 14, 2023 |
| Dell          | Latitude 3420               | Notebook    | [b344d71410](https://linux-hardware.org/?probe=b344d71410) | Dec 13, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [2199caf331](https://linux-hardware.org/?probe=2199caf331) | Dec 10, 2023 |
| Compaq        | 0684h                       | Desktop     | [54c2d84103](https://linux-hardware.org/?probe=54c2d84103) | Dec 02, 2023 |
| Compaq        | 0684h                       | Desktop     | [b2d96b48dc](https://linux-hardware.org/?probe=b2d96b48dc) | Dec 02, 2023 |
| ECS           | M789CG                      | Desktop     | [7c2e2de188](https://linux-hardware.org/?probe=7c2e2de188) | Dec 01, 2023 |
| ASUSTek       | 1001PX                      | Notebook    | [74bc5aeded](https://linux-hardware.org/?probe=74bc5aeded) | Nov 22, 2023 |
| ASUSTek       | 1001PX                      | Notebook    | [2069694d95](https://linux-hardware.org/?probe=2069694d95) | Nov 22, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [b312b34d74](https://linux-hardware.org/?probe=b312b34d74) | Nov 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [f576d94ac0](https://linux-hardware.org/?probe=f576d94ac0) | Nov 17, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [1909f3fbff](https://linux-hardware.org/?probe=1909f3fbff) | Nov 15, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [f48f05994e](https://linux-hardware.org/?probe=f48f05994e) | Nov 14, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [60e418e27f](https://linux-hardware.org/?probe=60e418e27f) | Nov 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [80774e2d18](https://linux-hardware.org/?probe=80774e2d18) | Nov 14, 2023 |
| Unknown       | MT6737 (DT)                 | Soc         | [ed82b4c1c7](https://linux-hardware.org/?probe=ed82b4c1c7) | Nov 12, 2023 |
| ZOTAC         | ZBOX-EN1070/1060,EN1070K... | Mini pc     | [bfd62247aa](https://linux-hardware.org/?probe=bfd62247aa) | Nov 12, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [65a7263504](https://linux-hardware.org/?probe=65a7263504) | Nov 09, 2023 |
| ECS           | M789CG                      | Desktop     | [49edfe005c](https://linux-hardware.org/?probe=49edfe005c) | Nov 07, 2023 |
| Gigabyte      | 945GCM-S2C                  | Desktop     | [c714bf35c2](https://linux-hardware.org/?probe=c714bf35c2) | Nov 06, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [ccc7d658ea](https://linux-hardware.org/?probe=ccc7d658ea) | Nov 06, 2023 |
| ECS           | M789CG                      | Desktop     | [87fe73ee84](https://linux-hardware.org/?probe=87fe73ee84) | Nov 02, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [0656d1a0a8](https://linux-hardware.org/?probe=0656d1a0a8) | Oct 28, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [e116ef83e9](https://linux-hardware.org/?probe=e116ef83e9) | Oct 27, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [6df3cd6820](https://linux-hardware.org/?probe=6df3cd6820) | Oct 20, 2023 |
| ECS           | M789CG                      | Desktop     | [b767549953](https://linux-hardware.org/?probe=b767549953) | Oct 15, 2023 |
| ASRock        | Q1900B-ITX                  | Desktop     | [8625166ef3](https://linux-hardware.org/?probe=8625166ef3) | Oct 14, 2023 |
| ECS           | M789CG                      | Desktop     | [6f446a6f77](https://linux-hardware.org/?probe=6f446a6f77) | Oct 14, 2023 |
| ECS           | M789CG                      | Desktop     | [0a0df79fcd](https://linux-hardware.org/?probe=0a0df79fcd) | Oct 14, 2023 |
| Inventec      | D CLASS A02                 | Desktop     | [9559c016fb](https://linux-hardware.org/?probe=9559c016fb) | Oct 13, 2023 |
| ASRock        | Z790M-ITX WiFi              | Desktop     | [560aec8a01](https://linux-hardware.org/?probe=560aec8a01) | Oct 06, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [8356867b4d](https://linux-hardware.org/?probe=8356867b4d) | Oct 04, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [1d2bd102c6](https://linux-hardware.org/?probe=1d2bd102c6) | Sep 28, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [6295f7193c](https://linux-hardware.org/?probe=6295f7193c) | Sep 27, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [793c32918d](https://linux-hardware.org/?probe=793c32918d) | Sep 23, 2023 |
| ASRock        | H55M-LE                     | Desktop     | [6b7e52fd8c](https://linux-hardware.org/?probe=6b7e52fd8c) | Sep 20, 2023 |
| ASRock        | H55M-LE                     | Desktop     | [ceefe742e2](https://linux-hardware.org/?probe=ceefe742e2) | Sep 20, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [b858f753b2](https://linux-hardware.org/?probe=b858f753b2) | Sep 19, 2023 |
| Dell          | 0RY007                      | Desktop     | [3bcbd1f6c3](https://linux-hardware.org/?probe=3bcbd1f6c3) | Sep 19, 2023 |
| Unknown       | Unknown                     | Notebook    | [cc13e0926e](https://linux-hardware.org/?probe=cc13e0926e) | Sep 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [416798463e](https://linux-hardware.org/?probe=416798463e) | Sep 16, 2023 |
| LG Electro... | LW25-B7HG                   | Notebook    | [e9998203e6](https://linux-hardware.org/?probe=e9998203e6) | Sep 12, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [d59c2170bb](https://linux-hardware.org/?probe=d59c2170bb) | Sep 08, 2023 |
| Unknown       | MT6737 (DT)                 | Soc         | [ca65758798](https://linux-hardware.org/?probe=ca65758798) | Sep 07, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [ed1061dbb1](https://linux-hardware.org/?probe=ed1061dbb1) | Sep 07, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [00e5bebc6a](https://linux-hardware.org/?probe=00e5bebc6a) | Sep 06, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [30368099b8](https://linux-hardware.org/?probe=30368099b8) | Sep 06, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [f71590bc2b](https://linux-hardware.org/?probe=f71590bc2b) | Sep 03, 2023 |
| HP            | Presario V2000 (ES307UA#... | Notebook    | [6c727b9e00](https://linux-hardware.org/?probe=6c727b9e00) | Aug 23, 2023 |
| Dell          | 007MXD A00                  | Mini pc     | [1eab959e9a](https://linux-hardware.org/?probe=1eab959e9a) | Aug 15, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [d81314b86d](https://linux-hardware.org/?probe=d81314b86d) | Aug 12, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [4d26902a65](https://linux-hardware.org/?probe=4d26902a65) | Aug 12, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [d4a16b0b3e](https://linux-hardware.org/?probe=d4a16b0b3e) | Aug 10, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [294dcce02b](https://linux-hardware.org/?probe=294dcce02b) | Aug 04, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [2ea9aa9b27](https://linux-hardware.org/?probe=2ea9aa9b27) | Aug 02, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [3dcdce4c6d](https://linux-hardware.org/?probe=3dcdce4c6d) | Aug 02, 2023 |
| Dell          | Latitude 5430 Rugged        | Notebook    | [051aebd1a2](https://linux-hardware.org/?probe=051aebd1a2) | Jul 24, 2023 |
| ASUSTek       | A3AC                        | Notebook    | [1bf0a25c8e](https://linux-hardware.org/?probe=1bf0a25c8e) | Jul 22, 2023 |
| ASUSTek       | A3AC                        | Notebook    | [f7fb9875de](https://linux-hardware.org/?probe=f7fb9875de) | Jul 22, 2023 |
| ASRock        | 970 Extreme4                | Desktop     | [de055c3a95](https://linux-hardware.org/?probe=de055c3a95) | Jul 17, 2023 |
| ASUSTek       | Z170-E                      | Desktop     | [8be9720ca6](https://linux-hardware.org/?probe=8be9720ca6) | Jun 29, 2023 |
| Toshiba       | Satellite Pro L50-A         | Notebook    | [f1907449fa](https://linux-hardware.org/?probe=f1907449fa) | Jun 24, 2023 |
| Google        | Kefka                       | Notebook    | [c5d9002e23](https://linux-hardware.org/?probe=c5d9002e23) | Jun 23, 2023 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [4dca77df51](https://linux-hardware.org/?probe=4dca77df51) | Jun 21, 2023 |
| Dell          | 007MXD A00                  | Mini pc     | [b303b8ce0d](https://linux-hardware.org/?probe=b303b8ce0d) | Jun 07, 2023 |
| Dell          | 007MXD A00                  | Mini pc     | [8b904db6cf](https://linux-hardware.org/?probe=8b904db6cf) | Jun 06, 2023 |
| Intel         | NUC7i5BNB J31144-310        | Mini pc     | [0ad2309a50](https://linux-hardware.org/?probe=0ad2309a50) | Jun 05, 2023 |
| Lenovo        | ThinkPad T440p              | Notebook    | [c058d92130](https://linux-hardware.org/?probe=c058d92130) | Jun 05, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [374a3fef00](https://linux-hardware.org/?probe=374a3fef00) | Jun 05, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [413d6e5373](https://linux-hardware.org/?probe=413d6e5373) | Jun 05, 2023 |
| Toshiba       | WT8-A                       | Notebook    | [4dc30f1c10](https://linux-hardware.org/?probe=4dc30f1c10) | Jun 04, 2023 |
| MSI           | U200                        | Notebook    | [2fe4d70ea1](https://linux-hardware.org/?probe=2fe4d70ea1) | Jun 02, 2023 |
| HP            | 83E2                        | Desktop     | [0db8dcbc23](https://linux-hardware.org/?probe=0db8dcbc23) | May 28, 2023 |
| MSI           | MAG B460M MORTAR            | Desktop     | [da74cacf64](https://linux-hardware.org/?probe=da74cacf64) | May 18, 2023 |
| Gigabyte      | Z170X-UD5-CF                | Desktop     | [429dc207a6](https://linux-hardware.org/?probe=429dc207a6) | May 15, 2023 |
| Gigabyte      | Z170X-UD5-CF                | Desktop     | [f887e6f037](https://linux-hardware.org/?probe=f887e6f037) | May 15, 2023 |
| UGREEN        | DX4600                      | Desktop     | [cbe70de89c](https://linux-hardware.org/?probe=cbe70de89c) | Apr 19, 2023 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [125884d17a](https://linux-hardware.org/?probe=125884d17a) | Apr 05, 2023 |
| Olivetti      | Spring Peak                 | Notebook    | [9678c685d7](https://linux-hardware.org/?probe=9678c685d7) | Mar 31, 2023 |
| Olivetti      | Spring Peak                 | Notebook    | [7878f53f36](https://linux-hardware.org/?probe=7878f53f36) | Mar 31, 2023 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [8cf7b9cc76](https://linux-hardware.org/?probe=8cf7b9cc76) | Mar 23, 2023 |
| Fujitsu       | FMVNP8AE                    | Notebook    | [10efc9f976](https://linux-hardware.org/?probe=10efc9f976) | Mar 21, 2023 |
| Intel         | D525MW AAE93082-401         | Desktop     | [590309a32b](https://linux-hardware.org/?probe=590309a32b) | Mar 18, 2023 |
| Intel         | D525MW AAE93082-401         | Desktop     | [bc847b4586](https://linux-hardware.org/?probe=bc847b4586) | Mar 09, 2023 |
| Intel         | D525MW AAE93082-401         | Desktop     | [d02959f9ad](https://linux-hardware.org/?probe=d02959f9ad) | Mar 02, 2023 |
| Lenovo        | ThinkPad E590 20NB0012RT    | Notebook    | [4c9bfc239a](https://linux-hardware.org/?probe=4c9bfc239a) | Feb 26, 2023 |
| Acer          | Aspire ES1-132              | Notebook    | [386da062e2](https://linux-hardware.org/?probe=386da062e2) | Feb 23, 2023 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [3bd522dc2c](https://linux-hardware.org/?probe=3bd522dc2c) | Feb 13, 2023 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [cfa774a092](https://linux-hardware.org/?probe=cfa774a092) | Feb 13, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [b3d00219b0](https://linux-hardware.org/?probe=b3d00219b0) | Feb 07, 2023 |
| Google        | Leona                       | Notebook    | [59b146e197](https://linux-hardware.org/?probe=59b146e197) | Jan 21, 2023 |
| ASRock        | X470 Master SLI/ac          | Desktop     | [d8f1121a19](https://linux-hardware.org/?probe=d8f1121a19) | Jan 19, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [68a73ee517](https://linux-hardware.org/?probe=68a73ee517) | Jan 19, 2023 |
| ASRock        | X470 Master SLI/ac          | Desktop     | [6b6a4929de](https://linux-hardware.org/?probe=6b6a4929de) | Jan 16, 2023 |
| ASRock        | X470 Master SLI/ac          | Desktop     | [8775308115](https://linux-hardware.org/?probe=8775308115) | Jan 15, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [473b4d0e6e](https://linux-hardware.org/?probe=473b4d0e6e) | Jan 11, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [747c3d8c1f](https://linux-hardware.org/?probe=747c3d8c1f) | Jan 11, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [9635348d10](https://linux-hardware.org/?probe=9635348d10) | Jan 09, 2023 |
| Lenovo        | ThinkPad X131e 33711Q7      | Notebook    | [3336313cae](https://linux-hardware.org/?probe=3336313cae) | Jan 06, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [053b8697ce](https://linux-hardware.org/?probe=053b8697ce) | Jan 06, 2023 |
| Lenovo        | ThinkPad X131e 33711Q7      | Notebook    | [7e0f8a38bf](https://linux-hardware.org/?probe=7e0f8a38bf) | Jan 04, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [5da7f2d3a9](https://linux-hardware.org/?probe=5da7f2d3a9) | Dec 27, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [389475ec30](https://linux-hardware.org/?probe=389475ec30) | Dec 25, 2022 |
| Dell          | 03V7GF A01                  | Desktop     | [3847c61b81](https://linux-hardware.org/?probe=3847c61b81) | Dec 17, 2022 |
| Dell          | 03V7GF A01                  | Desktop     | [e491b54a3c](https://linux-hardware.org/?probe=e491b54a3c) | Dec 17, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [bbf4464c41](https://linux-hardware.org/?probe=bbf4464c41) | Nov 27, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [ec837e35d6](https://linux-hardware.org/?probe=ec837e35d6) | Nov 22, 2022 |
| Fujitsu       | FujitsuTP7000 -1            | Desktop     | [89198d262f](https://linux-hardware.org/?probe=89198d262f) | Nov 17, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [d7cc344b2f](https://linux-hardware.org/?probe=d7cc344b2f) | Oct 31, 2022 |
| Supermicro    | X10SLL-F                    | Server      | [ab9f37ab3a](https://linux-hardware.org/?probe=ab9f37ab3a) | Oct 27, 2022 |
| Dell          | Inspiron 5447               | Notebook    | [735ac089ab](https://linux-hardware.org/?probe=735ac089ab) | Oct 17, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [9f7158b883](https://linux-hardware.org/?probe=9f7158b883) | Oct 16, 2022 |
| HP            | Presario V4000 (EQ608PA#... | Notebook    | [f462d80b2a](https://linux-hardware.org/?probe=f462d80b2a) | Oct 06, 2022 |
| HP            | 1493                        | Desktop     | [60ebd1d8dd](https://linux-hardware.org/?probe=60ebd1d8dd) | Sep 29, 2022 |
| Gateway       | SX2185                      | Desktop     | [8372be8fe3](https://linux-hardware.org/?probe=8372be8fe3) | Sep 29, 2022 |
| ASRock        | H81M                        | Desktop     | [d59c4705a2](https://linux-hardware.org/?probe=d59c4705a2) | Aug 17, 2022 |
| Toshiba       | Satellite M645              | Notebook    | [b342f11704](https://linux-hardware.org/?probe=b342f11704) | Aug 16, 2022 |
| Toshiba       | Satellite M645              | Notebook    | [f64d98a9e1](https://linux-hardware.org/?probe=f64d98a9e1) | Aug 16, 2022 |
| Dell          | Inspiron 3180               | Notebook    | [d4dbaf9ec8](https://linux-hardware.org/?probe=d4dbaf9ec8) | Aug 14, 2022 |
| Fujitsu       | LIFEBOOK P702               | Notebook    | [fdbe6c32cd](https://linux-hardware.org/?probe=fdbe6c32cd) | Aug 06, 2022 |
| Unknown       | Unknown                     | Soc         | [9ebddaa953](https://linux-hardware.org/?probe=9ebddaa953) | Jul 31, 2022 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [5a3ed0cf62](https://linux-hardware.org/?probe=5a3ed0cf62) | Jul 30, 2022 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [719bbf817c](https://linux-hardware.org/?probe=719bbf817c) | Jul 30, 2022 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [9a4907d88c](https://linux-hardware.org/?probe=9a4907d88c) | Jul 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [d857b93614](https://linux-hardware.org/?probe=d857b93614) | Jul 13, 2022 |
| Sony          | VGN-UX27GN                  | Notebook    | [ed20bd45a4](https://linux-hardware.org/?probe=ed20bd45a4) | Jun 20, 2022 |
| IBM           | ThinkPad X40 2371LBG        | Notebook    | [e7610b86d4](https://linux-hardware.org/?probe=e7610b86d4) | Jun 20, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [a0a6c37152](https://linux-hardware.org/?probe=a0a6c37152) | Jun 19, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [2f6356a177](https://linux-hardware.org/?probe=2f6356a177) | Jun 17, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [e47cf70de1](https://linux-hardware.org/?probe=e47cf70de1) | Jun 17, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [582fd88dbe](https://linux-hardware.org/?probe=582fd88dbe) | Jun 14, 2022 |
| MSI           | Z170A GAMING PRO            | Desktop     | [73b3e29101](https://linux-hardware.org/?probe=73b3e29101) | Jun 14, 2022 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [a7f61e2b9b](https://linux-hardware.org/?probe=a7f61e2b9b) | May 28, 2022 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [e692b2a091](https://linux-hardware.org/?probe=e692b2a091) | May 26, 2022 |
| HP            | ENVY Sleekbook 6 PC         | Notebook    | [28b7e84c50](https://linux-hardware.org/?probe=28b7e84c50) | May 24, 2022 |
| HP            | ENVY Sleekbook 6 PC         | Notebook    | [5d78835d90](https://linux-hardware.org/?probe=5d78835d90) | May 24, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [cab2025064](https://linux-hardware.org/?probe=cab2025064) | May 24, 2022 |
| MSI           | J1900I                      | Desktop     | [86f37a71f5](https://linux-hardware.org/?probe=86f37a71f5) | May 15, 2022 |
| MSI           | J1900I                      | Desktop     | [5a48d83596](https://linux-hardware.org/?probe=5a48d83596) | May 15, 2022 |
| ASUSTek       | N10Jc                       | Notebook    | [ae20ca4c7c](https://linux-hardware.org/?probe=ae20ca4c7c) | May 05, 2022 |
| ASUSTek       | N10Jc                       | Notebook    | [1f688a5b2d](https://linux-hardware.org/?probe=1f688a5b2d) | May 05, 2022 |
| HP            | ProBook 4310s               | Notebook    | [a37901ae30](https://linux-hardware.org/?probe=a37901ae30) | Apr 26, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f0671e360b](https://linux-hardware.org/?probe=f0671e360b) | Apr 25, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [53cba6b4f8](https://linux-hardware.org/?probe=53cba6b4f8) | Apr 14, 2022 |
| Haier         | U144S                       | Notebook    | [9a4827b852](https://linux-hardware.org/?probe=9a4827b852) | Mar 26, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [930cc740b2](https://linux-hardware.org/?probe=930cc740b2) | Mar 24, 2022 |
| Lenovo        | ThinkPad T420 42364F2       | Notebook    | [d82acaba71](https://linux-hardware.org/?probe=d82acaba71) | Mar 23, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [df2a40363b](https://linux-hardware.org/?probe=df2a40363b) | Mar 18, 2022 |
| ASUSTek       | ZenBook UX431FA             | Notebook    | [b3cbed05f5](https://linux-hardware.org/?probe=b3cbed05f5) | Mar 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [94cf359935](https://linux-hardware.org/?probe=94cf359935) | Feb 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [822688debe](https://linux-hardware.org/?probe=822688debe) | Feb 16, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [a72ab8595e](https://linux-hardware.org/?probe=a72ab8595e) | Jan 30, 2022 |
| Gigabyte      | Z490I AORUS ULTRA           | Desktop     | [908edb3724](https://linux-hardware.org/?probe=908edb3724) | Jan 27, 2022 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [6deddd3d32](https://linux-hardware.org/?probe=6deddd3d32) | Jan 25, 2022 |
| ASUSTek       | ZenBook UX431FA             | Notebook    | [519a7a72ab](https://linux-hardware.org/?probe=519a7a72ab) | Jan 24, 2022 |
| HP            | EliteBook 1040 G3 Notebo... | Notebook    | [465c51678d](https://linux-hardware.org/?probe=465c51678d) | Jan 01, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [f483ddc44f](https://linux-hardware.org/?probe=f483ddc44f) | Jan 01, 2022 |
| MSI           | GL72M 7REX                  | Notebook    | [6ada534c8b](https://linux-hardware.org/?probe=6ada534c8b) | Dec 13, 2021 |
| Dell          | 02YRK5 A02                  | Desktop     | [58c2ed388b](https://linux-hardware.org/?probe=58c2ed388b) | Dec 02, 2021 |
| Lenovo        | ThinkPad W700 2752RZ2       | Notebook    | [66ea0a02cb](https://linux-hardware.org/?probe=66ea0a02cb) | Nov 25, 2021 |
| Supermicro    | X10SLL-F                    | Server      | [84ed224f36](https://linux-hardware.org/?probe=84ed224f36) | Nov 24, 2021 |
| HP            | 21B4 A01                    | Desktop     | [98accc83e4](https://linux-hardware.org/?probe=98accc83e4) | Nov 11, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [e293d0cf05](https://linux-hardware.org/?probe=e293d0cf05) | Nov 02, 2021 |
| HP            | Stream 7 Tablet             | Tablet      | [0297d0f732](https://linux-hardware.org/?probe=0297d0f732) | Oct 25, 2021 |
| HP            | Stream 7 Tablet             | Tablet      | [45b1bba577](https://linux-hardware.org/?probe=45b1bba577) | Oct 24, 2021 |
| ASUSTek       | X550EA                      | Notebook    | [bbed87466a](https://linux-hardware.org/?probe=bbed87466a) | Oct 05, 2021 |
| HP            | ProLiant DL360 G6           | Server      | [6f87d9f9b8](https://linux-hardware.org/?probe=6f87d9f9b8) | Oct 01, 2021 |
| HP            | ProLiant DL360 G6           | Server      | [2668fd795b](https://linux-hardware.org/?probe=2668fd795b) | Oct 01, 2021 |
| HP            | Compaq Mini CQ10-600        | Notebook    | [4603b3336e](https://linux-hardware.org/?probe=4603b3336e) | Oct 01, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [9ff8561f02](https://linux-hardware.org/?probe=9ff8561f02) | Sep 30, 2021 |
| Lenovo        | Yoga 14sARH 2021 82LB       | Notebook    | [9fa77d455d](https://linux-hardware.org/?probe=9fa77d455d) | Sep 30, 2021 |
| Unknown       | Unknown                     | Notebook    | [d3c742bac9](https://linux-hardware.org/?probe=d3c742bac9) | Sep 26, 2021 |
| HP            | Stream 7 Tablet             | Tablet      | [254589b0bd](https://linux-hardware.org/?probe=254589b0bd) | Sep 16, 2021 |
| HP            | Stream 7 Tablet             | Tablet      | [f5bdbbea34](https://linux-hardware.org/?probe=f5bdbbea34) | Sep 15, 2021 |
| Dell          | 0T10XW A00                  | Desktop     | [585636f7fe](https://linux-hardware.org/?probe=585636f7fe) | Sep 08, 2021 |
| Shuttle       | FS81                        | Desktop     | [9a98a31681](https://linux-hardware.org/?probe=9a98a31681) | Sep 06, 2021 |
| Pegatron      | Deepcam                     | Notebook    | [5326e6bf39](https://linux-hardware.org/?probe=5326e6bf39) | Jul 18, 2021 |
| Acer          | Nitro AN515-55              | Notebook    | [3199a22608](https://linux-hardware.org/?probe=3199a22608) | Jul 15, 2021 |
| HP            | EliteBook 2740p             | Notebook    | [66479cb1dd](https://linux-hardware.org/?probe=66479cb1dd) | Jul 09, 2021 |
| HP            | EliteBook 2740p             | Notebook    | [652fa48f49](https://linux-hardware.org/?probe=652fa48f49) | Jul 08, 2021 |
| ASUSTek       | X200MA                      | Notebook    | [c9edeec38a](https://linux-hardware.org/?probe=c9edeec38a) | Jun 26, 2021 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [f1b8c01b96](https://linux-hardware.org/?probe=f1b8c01b96) | Jun 22, 2021 |
| IBM           | 264070A                     | Notebook    | [c057e54603](https://linux-hardware.org/?probe=c057e54603) | Jun 08, 2021 |
| HP            | Mini 110-3500               | Notebook    | [be40a38710](https://linux-hardware.org/?probe=be40a38710) | Jun 06, 2021 |
| HP            | ENVY Sleekbook 6 PC         | Notebook    | [0a2464e592](https://linux-hardware.org/?probe=0a2464e592) | Jun 06, 2021 |
| Dell          | 0VRWRC A00                  | Desktop     | [37a6ad6e02](https://linux-hardware.org/?probe=37a6ad6e02) | Apr 09, 2021 |
| Dell          | 0DPRKF A07                  | Server      | [dee1f70644](https://linux-hardware.org/?probe=dee1f70644) | Mar 28, 2021 |
| ASUSTek       | P8H67-V                     | Desktop     | [89edd8b343](https://linux-hardware.org/?probe=89edd8b343) | Mar 17, 2021 |
| F5 Network... | PCA-0377-05                 | Server      | [14c76e0c83](https://linux-hardware.org/?probe=14c76e0c83) | Feb 28, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [0a01176cbe](https://linux-hardware.org/?probe=0a01176cbe) | Feb 23, 2021 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [af637820c2](https://linux-hardware.org/?probe=af637820c2) | Feb 12, 2021 |
| Acer          | Aspire ES1-512              | Notebook    | [01ad8fc793](https://linux-hardware.org/?probe=01ad8fc793) | Jan 30, 2021 |
| Acer          | Aspire 5920G                | Notebook    | [7cf5d7b04a](https://linux-hardware.org/?probe=7cf5d7b04a) | Jan 08, 2021 |
| HP            | Compaq Mini CQ10-600        | Notebook    | [fe7ee46763](https://linux-hardware.org/?probe=fe7ee46763) | Jan 08, 2021 |
| Gateway       | MX3631m                     | Notebook    | [15d8283384](https://linux-hardware.org/?probe=15d8283384) | Jan 03, 2021 |
| Dell          | Studio 1747                 | Notebook    | [b4e0e289f6](https://linux-hardware.org/?probe=b4e0e289f6) | Dec 29, 2020 |
| VIA Techno... | KM266APro-835               | Desktop     | [1334ad3f74](https://linux-hardware.org/?probe=1334ad3f74) | Dec 22, 2020 |
| Dell          | Inspiron 3180               | Notebook    | [4b05b65d0e](https://linux-hardware.org/?probe=4b05b65d0e) | Dec 16, 2020 |
| Dell          | Inspiron 3180               | Notebook    | [0bc140f6f6](https://linux-hardware.org/?probe=0bc140f6f6) | Dec 16, 2020 |
| ASUSTek       | E502SA                      | Notebook    | [0a25648158](https://linux-hardware.org/?probe=0a25648158) | Dec 05, 2020 |
| IBM           | 26446AG                     | Notebook    | [f004231106](https://linux-hardware.org/?probe=f004231106) | Nov 15, 2020 |
| IBM           | 26446AG                     | Notebook    | [29affa3577](https://linux-hardware.org/?probe=29affa3577) | Nov 15, 2020 |
| HP            | 2B0D A01                    | All in one  | [5c13b7bb96](https://linux-hardware.org/?probe=5c13b7bb96) | Nov 03, 2020 |
| Google        | Samus                       | Notebook    | [efe40a5a38](https://linux-hardware.org/?probe=efe40a5a38) | Oct 13, 2020 |
| Fujitsu       | D2779 S26361-D2779-A1       | Desktop     | [07795a357a](https://linux-hardware.org/?probe=07795a357a) | Oct 09, 2020 |
| Dell          | Inspiron 5566               | Notebook    | [a12b4d304a](https://linux-hardware.org/?probe=a12b4d304a) | Sep 29, 2020 |
| Lenovo        | 314C SDK0J40697 WIN 3305... | Mini pc     | [0f66b49a44](https://linux-hardware.org/?probe=0f66b49a44) | Sep 17, 2020 |
| Dell          | 0PU052                      | Desktop     | [9a31999f07](https://linux-hardware.org/?probe=9a31999f07) | Aug 31, 2020 |
| Apple         | MacBook7,1                  | Notebook    | [6445bfa9bd](https://linux-hardware.org/?probe=6445bfa9bd) | Aug 31, 2020 |
| Supermicro    | X10SLL-F                    | Server      | [dfbdbb0676](https://linux-hardware.org/?probe=dfbdbb0676) | Aug 25, 2020 |
| ASUSTek       | TS10                        | Desktop     | [71d7f6e110](https://linux-hardware.org/?probe=71d7f6e110) | Aug 20, 2020 |
| VIA Techno... | KM266APro-835               | Desktop     | [25ec3d44ff](https://linux-hardware.org/?probe=25ec3d44ff) | Aug 16, 2020 |
| Gigabyte      | Z490I AORUS ULTRA           | Desktop     | [58dce1215c](https://linux-hardware.org/?probe=58dce1215c) | Aug 13, 2020 |
| ASUSTek       | PRIME H370M-PLUS            | Desktop     | [0c50242cc5](https://linux-hardware.org/?probe=0c50242cc5) | Aug 09, 2020 |
| Acer          | Nitro AN515-55              | Notebook    | [d05c262e67](https://linux-hardware.org/?probe=d05c262e67) | Aug 06, 2020 |
| ASRock        | J3455M                      | Desktop     | [05f9d5c3b4](https://linux-hardware.org/?probe=05f9d5c3b4) | Aug 06, 2020 |
| Lenovo        | ThinkPad 11e 20ED001HUS     | Notebook    | [364afb4113](https://linux-hardware.org/?probe=364afb4113) | Aug 06, 2020 |
| Acer          | Aspire ES1-111M             | Notebook    | [c99b05cc07](https://linux-hardware.org/?probe=c99b05cc07) | Jul 30, 2020 |
| eMachines     | EL1352G                     | Desktop     | [4513d2931f](https://linux-hardware.org/?probe=4513d2931f) | Jul 03, 2020 |
| eMachines     | EL1352G                     | Desktop     | [4b26717c89](https://linux-hardware.org/?probe=4b26717c89) | Jul 03, 2020 |
| ASRock        | J3455M                      | Desktop     | [3719f96b60](https://linux-hardware.org/?probe=3719f96b60) | Jul 03, 2020 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | Notebook    | [aa287cffbe](https://linux-hardware.org/?probe=aa287cffbe) | Jun 18, 2020 |
| Intel         | Merrifield                  | Tablet      | [d1f5e15d8c](https://linux-hardware.org/?probe=d1f5e15d8c) | May 23, 2020 |
| HP            | ZBook 15 G5                 | Notebook    | [3f3b1f2237](https://linux-hardware.org/?probe=3f3b1f2237) | Apr 05, 2020 |
| Synology      | DS1019+                     | Notebook    | [622ced4019](https://linux-hardware.org/?probe=622ced4019) | Feb 09, 2020 |
| Synology      | DS1019+                     | Notebook    | [c8a69e1c12](https://linux-hardware.org/?probe=c8a69e1c12) | Jan 21, 2020 |
| Synology      | DS1019+                     | Notebook    | [43a8c9674e](https://linux-hardware.org/?probe=43a8c9674e) | Jan 18, 2020 |
| Unknown       | i855GM/E-ITE8712            | Desktop     | [7b9cbd816b](https://linux-hardware.org/?probe=7b9cbd816b) | Dec 27, 2019 |
| ASRock        | D1800B-ITX                  | Desktop     | [f962d4bbf9](https://linux-hardware.org/?probe=f962d4bbf9) | Dec 22, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Alpine 3.19.1               | 12        | 6.06%   |
| Alpine 3.18.0               | 11        | 5.56%   |
| Alpine 3.12.0               | 11        | 5.56%   |
| Alpine 3.15.0               | 10        | 5.05%   |
| Alpine 3.19.0               | 9         | 4.55%   |
| Alpine 3.16.0               | 9         | 4.55%   |
| Alpine 3.15.4               | 9         | 4.55%   |
| Alpine 3.18.3               | 7         | 3.54%   |
| Alpine 3.15.0_alpha20210804 | 7         | 3.54%   |
| Alpine 3.19_alpha20230901   | 6         | 3.03%   |
| Alpine 3.18.4               | 6         | 3.03%   |
| Alpine 3.17_alpha20220809   | 5         | 2.53%   |
| Alpine 3.17.2               | 5         | 2.53%   |
| Alpine 3.14.0               | 5         | 2.53%   |
| Alpine 3.20.0_alpha20231219 | 4         | 2.02%   |
| Alpine 3.18.5               | 4         | 2.02%   |
| Alpine 3.18.2               | 4         | 2.02%   |
| Alpine 3.17.1               | 4         | 2.02%   |
| Alpine 3.17.0               | 4         | 2.02%   |
| Alpine 3.16.1               | 4         | 2.02%   |
| Alpine 3.14.2               | 4         | 2.02%   |
| Alpine 3.13.0_alpha20200917 | 4         | 2.02%   |
| Alpine 3.13.0_alpha20200626 | 4         | 2.02%   |
| Alpine 3.11.2               | 4         | 2.02%   |
| Alpine 3.20.0_alpha20240329 | 3         | 1.52%   |
| Alpine 3.18.6               | 3         | 1.52%   |
| Alpine 3.16.2               | 3         | 1.52%   |
| Alpine 3.13.1               | 3         | 1.52%   |
| Alpine 3.13.0_alpha20201218 | 3         | 1.52%   |
| Alpine 3.18_alpha20230329   | 2         | 1.01%   |
| Alpine 3.16.3               | 2         | 1.01%   |
| Alpine 3.15.6               | 2         | 1.01%   |
| Alpine 3.14.3               | 2         | 1.01%   |
| Alpine 3.13.5               | 2         | 1.01%   |
| Alpine 3.13.2               | 2         | 1.01%   |
| Alpine 3.12.3               | 2         | 1.01%   |
| Alpine 3.8.4                | 1         | 0.51%   |
| Alpine 3.19.0_rc2           | 1         | 0.51%   |
| Alpine 3.17.7               | 1         | 0.51%   |
| Alpine 3.17.4               | 1         | 0.51%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Alpine | 183       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version       | Computers | Percent |
|---------------|-----------|---------|
| 5.4.43-1-lts  | 8         | 3.9%    |
| 6.6.16-0-lts  | 3         | 1.46%   |
| 6.1.57-0-lts  | 3         | 1.46%   |
| 6.1.32-0-lts  | 3         | 1.46%   |
| 5.15.86-0-lts | 3         | 1.46%   |
| 5.15.60-0-lts | 3         | 1.46%   |
| 5.15.16-0-lts | 3         | 1.46%   |
| 5.10.61-0-lts | 3         | 1.46%   |
| 6.6.7-0-lts   | 2         | 0.98%   |
| 6.6.23-0-lts  | 2         | 0.98%   |
| 6.6.17-0-lts  | 2         | 0.98%   |
| 6.6.12-0-lts  | 2         | 0.98%   |
| 6.6.1-0-edge  | 2         | 0.98%   |
| 6.5.11-4-pve  | 2         | 0.98%   |
| 6.1.77-0-lts  | 2         | 0.98%   |
| 6.1.62-0-lts  | 2         | 0.98%   |
| 6.1.55-0-lts  | 2         | 0.98%   |
| 6.1.51-0-lts  | 2         | 0.98%   |
| 6.1.28-2-lts  | 2         | 0.98%   |
| 5.4.84-0-lts  | 2         | 0.98%   |
| 5.4.83-0-lts  | 2         | 0.98%   |
| 5.17.9-0-edge | 2         | 0.98%   |
| 5.15.74-0-lts | 2         | 0.98%   |
| 5.15.59-0-lts | 2         | 0.98%   |
| 5.15.47-0-lts | 2         | 0.98%   |
| 5.15.46-1-lts | 2         | 0.98%   |
| 5.15.41-0-lts | 2         | 0.98%   |
| 5.15.4-0-lts  | 2         | 0.98%   |
| 5.15.12-0-lts | 2         | 0.98%   |
| 5.10.68-0-lts | 2         | 0.98%   |
| 5.10.16-0-lts | 2         | 0.98%   |
| 6.6.9-0-lts   | 1         | 0.49%   |
| 6.6.8-0-lts   | 1         | 0.49%   |
| 6.6.6-0-lts   | 1         | 0.49%   |
| 6.6.4-0-lts   | 1         | 0.49%   |
| 6.6.28-0-lts  | 1         | 0.49%   |
| 6.6.26-0-lts  | 1         | 0.49%   |
| 6.6.25-haos   | 1         | 0.49%   |
| 6.6.24-0-lts  | 1         | 0.49%   |
| 6.6.22-0-lts  | 1         | 0.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.43  | 8         | 3.98%   |
| 6.6.16  | 3         | 1.49%   |
| 6.1.57  | 3         | 1.49%   |
| 6.1.55  | 3         | 1.49%   |
| 6.1.32  | 3         | 1.49%   |
| 5.15.86 | 3         | 1.49%   |
| 5.15.60 | 3         | 1.49%   |
| 5.15.16 | 3         | 1.49%   |
| 5.15.0  | 3         | 1.49%   |
| 5.10.61 | 3         | 1.49%   |
| 6.6.7   | 2         | 1%      |
| 6.6.23  | 2         | 1%      |
| 6.6.17  | 2         | 1%      |
| 6.6.12  | 2         | 1%      |
| 6.6.1   | 2         | 1%      |
| 6.5.11  | 2         | 1%      |
| 6.2.0   | 2         | 1%      |
| 6.1.77  | 2         | 1%      |
| 6.1.64  | 2         | 1%      |
| 6.1.62  | 2         | 1%      |
| 6.1.51  | 2         | 1%      |
| 6.1.34  | 2         | 1%      |
| 6.1.28  | 2         | 1%      |
| 5.4.84  | 2         | 1%      |
| 5.4.83  | 2         | 1%      |
| 5.19.0  | 2         | 1%      |
| 5.17.9  | 2         | 1%      |
| 5.15.74 | 2         | 1%      |
| 5.15.59 | 2         | 1%      |
| 5.15.47 | 2         | 1%      |
| 5.15.46 | 2         | 1%      |
| 5.15.41 | 2         | 1%      |
| 5.15.4  | 2         | 1%      |
| 5.15.12 | 2         | 1%      |
| 5.10.68 | 2         | 1%      |
| 5.10.16 | 2         | 1%      |
| 6.6.9   | 1         | 0.5%    |
| 6.6.8   | 1         | 0.5%    |
| 6.6.6   | 1         | 0.5%    |
| 6.6.4   | 1         | 0.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 52        | 26.8%   |
| 6.1     | 36        | 18.56%  |
| 6.6     | 26        | 13.4%   |
| 5.4     | 23        | 11.86%  |
| 5.10    | 23        | 11.86%  |
| 5.17    | 4         | 2.06%   |
| 6.5     | 3         | 1.55%   |
| 3.10    | 3         | 1.55%   |
| 6.2     | 2         | 1.03%   |
| 5.8     | 2         | 1.03%   |
| 5.19    | 2         | 1.03%   |
| 5.14    | 2         | 1.03%   |
| 4.4     | 2         | 1.03%   |
| 3.18    | 2         | 1.03%   |
| 6.4     | 1         | 0.52%   |
| 6.3     | 1         | 0.52%   |
| 6.0     | 1         | 0.52%   |
| 5.7     | 1         | 0.52%   |
| 5.6     | 1         | 0.52%   |
| 5.18    | 1         | 0.52%   |
| 5.16    | 1         | 0.52%   |
| 5.13    | 1         | 0.52%   |
| 5.12    | 1         | 0.52%   |
| 4.9     | 1         | 0.52%   |
| 4.20    | 1         | 0.52%   |
| 4.14    | 1         | 0.52%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 154       | 84.15%  |
| i686    | 19        | 10.38%  |
| aarch64 | 5         | 2.73%   |
| armv7l  | 3         | 1.64%   |
| i586    | 1         | 0.55%   |
| armv6l  | 1         | 0.55%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 142       | 77.6%   |
| XFCE    | 19        | 10.38%  |
| GNOME   | 9         | 4.92%   |
| KDE5    | 7         | 3.83%   |
| sway    | 2         | 1.09%   |
| LXQt    | 2         | 1.09%   |
| KDE     | 1         | 0.55%   |
| i3      | 1         | 0.55%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 109       | 58.29%  |
| X11     | 63        | 33.69%  |
| Wayland | 14        | 7.49%   |
| Tty     | 1         | 0.53%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 144       | 78.26%  |
| LightDM | 25        | 13.59%  |
| GDM     | 7         | 3.8%    |
| SDDM    | 5         | 2.72%   |
| LXDM    | 2         | 1.09%   |
| XDM     | 1         | 0.54%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| C       | 115       | 61.5%   |
| Unknown | 57        | 30.48%  |
| en_US   | 8         | 4.28%   |
| ru_RU   | 3         | 1.6%    |
| en_GB   | 2         | 1.07%   |
| pt_BR   | 1         | 0.53%   |
| es_NI   | 1         | 0.53%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 116       | 62.7%   |
| EFI  | 69        | 37.3%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 145       | 76.72%  |
| Btrfs   | 16        | 8.47%   |
| Overlay | 11        | 5.82%   |
| Tmpfs   | 6         | 3.17%   |
| Unknown | 4         | 2.12%   |
| F2fs    | 2         | 1.06%   |
| Ext2    | 2         | 1.06%   |
| Zfs     | 1         | 0.53%   |
| Rootfs  | 1         | 0.53%   |
| Fake    | 1         | 0.53%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 119       | 62.96%  |
| GPT     | 51        | 26.98%  |
| MBR     | 19        | 10.05%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 163       | 88.11%  |
| Yes       | 22        | 11.89%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 173       | 93.01%  |
| Yes       | 13        | 6.99%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 29        | 15.85%  |
| Dell                    | 23        | 12.57%  |
| Lenovo                  | 19        | 10.38%  |
| ASUSTek Computer        | 19        | 10.38%  |
| ASRock                  | 9         | 4.92%   |
| Gigabyte Technology     | 8         | 4.37%   |
| Acer                    | 8         | 4.37%   |
| Unknown                 | 8         | 4.37%   |
| Intel                   | 7         | 3.83%   |
| Fujitsu                 | 5         | 2.73%   |
| Apple                   | 5         | 2.73%   |
| Toshiba                 | 3         | 1.64%   |
| Raspberry Pi Foundation | 3         | 1.64%   |
| MSI                     | 3         | 1.64%   |
| IBM                     | 3         | 1.64%   |
| Google                  | 3         | 1.64%   |
| ZOTAC                   | 2         | 1.09%   |
| Sony                    | 2         | 1.09%   |
| Inventec                | 2         | 1.09%   |
| Gateway                 | 2         | 1.09%   |
| AMI                     | 2         | 1.09%   |
| Wortmann AG             | 1         | 0.55%   |
| VIA Technologies        | 1         | 0.55%   |
| UGREEN                  | 1         | 0.55%   |
| Synology                | 1         | 0.55%   |
| Supermicro              | 1         | 0.55%   |
| SLIMBOOK                | 1         | 0.55%   |
| Shuttle                 | 1         | 0.55%   |
| Pegatron                | 1         | 0.55%   |
| Olivetti                | 1         | 0.55%   |
| Notebook                | 1         | 0.55%   |
| MACHINIST               | 1         | 0.55%   |
| LG Electronics          | 1         | 0.55%   |
| Haier                   | 1         | 0.55%   |
| Fanless Mini PC         | 1         | 0.55%   |
| F5 Networks             | 1         | 0.55%   |
| eMachines               | 1         | 0.55%   |
| ECS                     | 1         | 0.55%   |
| Compaq                  | 1         | 0.55%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 9         | 4.92%   |
| HP ENVY Laptop 13-ad1xx                  | 3         | 1.64%   |
| Dell Dell Thin Client Desktop 3030 LT    | 3         | 1.64%   |
| ASUS All Series                          | 3         | 1.64%   |
| RPi Raspberry Pi                         | 2         | 1.09%   |
| Lenovo V15 G3 IAP 82TT                   | 2         | 1.09%   |
| HP ProLiant DL360 G6                     | 2         | 1.09%   |
| Gigabyte Z490I AORUS ULTRA               | 2         | 1.09%   |
| ZOTAC ZBOX-EN1070/1060,EN1070K/1060K     | 1         | 0.55%   |
| Wortmann AG M660SE                       | 1         | 0.55%   |
| VIA KM266APro-835                        | 1         | 0.55%   |
| UGREEN DX4600                            | 1         | 0.55%   |
| Toshiba WT8-A                            | 1         | 0.55%   |
| Toshiba Satellite Pro L50-A              | 1         | 0.55%   |
| Toshiba Satellite M645                   | 1         | 0.55%   |
| Synology DS1019+                         | 1         | 0.55%   |
| Supermicro X10SLL-F                      | 1         | 0.55%   |
| Sony VPCEC3A4E                           | 1         | 0.55%   |
| Sony VGN-UX27GN                          | 1         | 0.55%   |
| SLIMBOOK EXECUTIVE-14                    | 1         | 0.55%   |
| Shuttle DS81D                            | 1         | 0.55%   |
| RPi Raspberry Pi 4 Model B Rev 1.5       | 1         | 0.55%   |
| Pegatron Deepcam                         | 1         | 0.55%   |
| Olivetti Spring Peak                     | 1         | 0.55%   |
| Notebook NV4XMB,ME,MZ                    | 1         | 0.55%   |
| MSI MS-7C82                              | 1         | 0.55%   |
| MSI MS-7877                              | 1         | 0.55%   |
| MSI GL72M 7REX                           | 1         | 0.55%   |
| MACHINIST X99 PR9                        | 1         | 0.55%   |
| LG LW25-B7HG                             | 1         | 0.55%   |
| Lenovo Yoga 14sARH 2021 82LB             | 1         | 0.55%   |
| Lenovo Y70-70 Touch 80DU                 | 1         | 0.55%   |
| Lenovo V14-ADA 82C6                      | 1         | 0.55%   |
| Lenovo ThinkPad X61 76754KU              | 1         | 0.55%   |
| Lenovo ThinkPad X131e 33711Q7            | 1         | 0.55%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS17D00 | 1         | 0.55%   |
| Lenovo ThinkPad W700 2752RZ2             | 1         | 0.55%   |
| Lenovo ThinkPad T420 42364F2             | 1         | 0.55%   |
| Lenovo ThinkPad E590 20NB0012RT          | 1         | 0.55%   |
| Lenovo ThinkPad E485 20KUCTO1WW          | 1         | 0.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Unknown               | 9         | 4.92%   |
| Lenovo ThinkPad       | 8         | 4.37%   |
| Dell Inspiron         | 8         | 4.37%   |
| Dell OptiPlex         | 6         | 3.28%   |
| Acer Aspire           | 6         | 3.28%   |
| HP ENVY               | 4         | 2.19%   |
| RPi Raspberry         | 3         | 1.64%   |
| HP ProLiant           | 3         | 1.64%   |
| HP Pavilion           | 3         | 1.64%   |
| HP Laptop             | 3         | 1.64%   |
| HP EliteBook          | 3         | 1.64%   |
| HP Compaq             | 3         | 1.64%   |
| Dell Dell             | 3         | 1.64%   |
| ASUS All              | 3         | 1.64%   |
| Toshiba Satellite     | 2         | 1.09%   |
| Lenovo V15            | 2         | 1.09%   |
| Lenovo ThinkCentre    | 2         | 1.09%   |
| HP Presario           | 2         | 1.09%   |
| Gigabyte Z490I        | 2         | 1.09%   |
| Fujitsu LIFEBOOK      | 2         | 1.09%   |
| Dell XPS              | 2         | 1.09%   |
| Dell Latitude         | 2         | 1.09%   |
| ASUS VivoBook         | 2         | 1.09%   |
| ASUS PRIME            | 2         | 1.09%   |
| ZOTAC ZBOX-EN1070     | 1         | 0.55%   |
| Wortmann AG M660SE    | 1         | 0.55%   |
| VIA KM266APro-835     | 1         | 0.55%   |
| UGREEN DX4600         | 1         | 0.55%   |
| Toshiba WT8-A         | 1         | 0.55%   |
| Synology DS1019+      | 1         | 0.55%   |
| Supermicro X10SLL-F   | 1         | 0.55%   |
| Sony VPCEC3A4E        | 1         | 0.55%   |
| Sony VGN-UX27GN       | 1         | 0.55%   |
| SLIMBOOK EXECUTIVE-14 | 1         | 0.55%   |
| Shuttle DS81D         | 1         | 0.55%   |
| Pegatron Deepcam      | 1         | 0.55%   |
| Olivetti Spring       | 1         | 0.55%   |
| Notebook NV4XMB       | 1         | 0.55%   |
| MSI MS-7C82           | 1         | 0.55%   |
| MSI MS-7877           | 1         | 0.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2014    | 19        | 10.38%  |
| 2012    | 15        | 8.2%    |
| 2019    | 13        | 7.1%    |
| 2017    | 13        | 7.1%    |
| 2013    | 13        | 7.1%    |
| 2010    | 13        | 7.1%    |
| 2016    | 12        | 6.56%   |
| 2018    | 11        | 6.01%   |
| Unknown | 11        | 6.01%   |
| 2021    | 8         | 4.37%   |
| 2020    | 8         | 4.37%   |
| 2009    | 7         | 3.83%   |
| 2007    | 7         | 3.83%   |
| 2011    | 6         | 3.28%   |
| 2006    | 6         | 3.28%   |
| 2022    | 5         | 2.73%   |
| 2015    | 5         | 2.73%   |
| 2023    | 4         | 2.19%   |
| 2005    | 2         | 1.09%   |
| 2001    | 2         | 1.09%   |
| 2008    | 1         | 0.55%   |
| 2004    | 1         | 0.55%   |
| 1999    | 1         | 0.55%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 90        | 49.18%  |
| Desktop        | 64        | 34.97%  |
| Mini pc        | 12        | 6.56%   |
| System on chip | 6         | 3.28%   |
| Server         | 5         | 2.73%   |
| Tablet         | 3         | 1.64%   |
| All in one     | 2         | 1.09%   |
| Convertible    | 1         | 0.55%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 182       | 98.91%  |
| Enabled  | 2         | 1.09%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 180       | 98.36%  |
| Yes  | 3         | 1.64%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 38        | 19.9%   |
| 3.01-4.0        | 37        | 19.37%  |
| 16.01-24.0      | 29        | 15.18%  |
| 8.01-16.0       | 22        | 11.52%  |
| 1.01-2.0        | 17        | 8.9%    |
| 0.51-1.0        | 16        | 8.38%   |
| 32.01-64.0      | 14        | 7.33%   |
| 64.01-256.0     | 6         | 3.14%   |
| 0.01-0.5        | 6         | 3.14%   |
| 2.01-3.0        | 5         | 2.62%   |
| More than 256.0 | 1         | 0.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 54        | 27.69%  |
| 1.01-2.0  | 43        | 22.05%  |
| 0.51-1.0  | 35        | 17.95%  |
| 2.01-3.0  | 21        | 10.77%  |
| 3.01-4.0  | 16        | 8.21%   |
| 4.01-8.0  | 11        | 5.64%   |
| 0         | 6         | 3.08%   |
| 8.01-16.0 | 5         | 2.56%   |
| Unknown   | 4         | 2.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 123       | 65.08%  |
| 2      | 35        | 18.52%  |
| 3      | 11        | 5.82%   |
| 4      | 8         | 4.23%   |
| 5      | 4         | 2.12%   |
| 0      | 3         | 1.59%   |
| 14     | 2         | 1.06%   |
| 12     | 1         | 0.53%   |
| 10     | 1         | 0.53%   |
| 7      | 1         | 0.53%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 146       | 78.92%  |
| Yes       | 39        | 21.08%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 154       | 84.15%  |
| No        | 29        | 15.85%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 116       | 62.37%  |
| No        | 70        | 37.63%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 101       | 54.59%  |
| Yes       | 84        | 45.41%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 42        | 21.88%  |
| Germany      | 22        | 11.46%  |
| Russia       | 13        | 6.77%   |
| Canada       | 13        | 6.77%   |
| UK           | 10        | 5.21%   |
| Brazil       | 9         | 4.69%   |
| Turkey       | 5         | 2.6%    |
| Sweden       | 5         | 2.6%    |
| Spain        | 5         | 2.6%    |
| France       | 4         | 2.08%   |
| Australia    | 4         | 2.08%   |
| Portugal     | 3         | 1.56%   |
| Poland       | 3         | 1.56%   |
| Norway       | 3         | 1.56%   |
| Italy        | 3         | 1.56%   |
| China        | 3         | 1.56%   |
| Switzerland  | 2         | 1.04%   |
| Slovakia     | 2         | 1.04%   |
| Netherlands  | 2         | 1.04%   |
| Mexico       | 2         | 1.04%   |
| Israel       | 2         | 1.04%   |
| Guatemala    | 2         | 1.04%   |
| Finland      | 2         | 1.04%   |
| Austria      | 2         | 1.04%   |
| Argentina    | 2         | 1.04%   |
| Vietnam      | 1         | 0.52%   |
| Venezuela    | 1         | 0.52%   |
| Uruguay      | 1         | 0.52%   |
| Ukraine      | 1         | 0.52%   |
| UAE          | 1         | 0.52%   |
| Thailand     | 1         | 0.52%   |
| South Korea  | 1         | 0.52%   |
| South Africa | 1         | 0.52%   |
| Romania      | 1         | 0.52%   |
| Puerto Rico  | 1         | 0.52%   |
| Philippines  | 1         | 0.52%   |
| Pakistan     | 1         | 0.52%   |
| Nicaragua    | 1         | 0.52%   |
| Kenya        | 1         | 0.52%   |
| Jamaica      | 1         | 0.52%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Springfield       | 7         | 3.57%   |
| St Petersburg     | 6         | 3.06%   |
| Manitowoc         | 5         | 2.55%   |
| Vernon            | 4         | 2.04%   |
| Traunstein        | 4         | 2.04%   |
| Moscow            | 4         | 2.04%   |
| Istanbul          | 4         | 2.04%   |
| Zurich            | 2         | 1.02%   |
| Sydney            | 2         | 1.02%   |
| Stuttgart         | 2         | 1.02%   |
| Stratford         | 2         | 1.02%   |
| Stillwater        | 2         | 1.02%   |
| Siegsdorf         | 2         | 1.02%   |
| Harrisonburg      | 2         | 1.02%   |
| Guatemala City    | 2         | 1.02%   |
| Gothenburg        | 2         | 1.02%   |
| Fulham            | 2         | 1.02%   |
| Frankfurt am Main | 2         | 1.02%   |
| As                | 2         | 1.02%   |
| Zhangzhou         | 1         | 0.51%   |
| Yakima            | 1         | 0.51%   |
| Waukesha          | 1         | 0.51%   |
| Warsaw            | 1         | 0.51%   |
| Vienna            | 1         | 0.51%   |
| Ventura           | 1         | 0.51%   |
| Vejle             | 1         | 0.51%   |
| Vancouver         | 1         | 0.51%   |
| Tymovskoye        | 1         | 0.51%   |
| Tuusula           | 1         | 0.51%   |
| Turin             | 1         | 0.51%   |
| Topeka            | 1         | 0.51%   |
| Tinh Binh Duong   | 1         | 0.51%   |
| Thornhill         | 1         | 0.51%   |
| Thame             | 1         | 0.51%   |
| Tampa             | 1         | 0.51%   |
| Stockholm         | 1         | 0.51%   |
| Stewartstown      | 1         | 0.51%   |
| Sorgues           | 1         | 0.51%   |
| Somerset          | 1         | 0.51%   |
| Ski               | 1         | 0.51%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 35        | 64     | 13.31%  |
| WDC                         | 31        | 64     | 11.79%  |
| Seagate                     | 25        | 62     | 9.51%   |
| Unknown                     | 23        | 29     | 8.75%   |
| Toshiba                     | 21        | 24     | 7.98%   |
| Hitachi                     | 12        | 12     | 4.56%   |
| Crucial                     | 12        | 21     | 4.56%   |
| Sandisk                     | 10        | 13     | 3.8%    |
| Kingston                    | 10        | 14     | 3.8%    |
| HGST                        | 10        | 10     | 3.8%    |
| A-DATA Technology           | 8         | 11     | 3.04%   |
| SK hynix                    | 7         | 9      | 2.66%   |
| Intel                       | 7         | 11     | 2.66%   |
| SPCC                        | 4         | 4      | 1.52%   |
| Micron Technology           | 4         | 5      | 1.52%   |
| Transcend                   | 2         | 2      | 0.76%   |
| Realtek Semiconductor       | 2         | 2      | 0.76%   |
| LITEON                      | 2         | 2      | 0.76%   |
| Intenso                     | 2         | 2      | 0.76%   |
| Hewlett-Packard             | 2         | 4      | 0.76%   |
| Fujitsu                     | 2         | 2      | 0.76%   |
| Corsair                     | 2         | 3      | 0.76%   |
| Unknown                     | 2         | 2      | 0.76%   |
| STEC                        | 1         | 1      | 0.38%   |
| SINTECHI                    | 1         | 1      | 0.38%   |
| Secure                      | 1         | 1      | 0.38%   |
| PNY                         | 1         | 1      | 0.38%   |
| Plextor                     | 1         | 1      | 0.38%   |
| Phison Electronics          | 1         | 1      | 0.38%   |
| OCZ                         | 1         | 1      | 0.38%   |
| NETAPP                      | 1         | 1      | 0.38%   |
| Netac                       | 1         | 1      | 0.38%   |
| Maxtor                      | 1         | 1      | 0.38%   |
| Lexar                       | 1         | 1      | 0.38%   |
| KIOXIA                      | 1         | 1      | 0.38%   |
| Kingston Technology Company | 1         | 1      | 0.38%   |
| KingSpec                    | 1         | 1      | 0.38%   |
| Kingmax                     | 1         | 1      | 0.38%   |
| KC600                       | 1         | 1      | 0.38%   |
| JMicron Technology          | 1         | 1      | 0.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown MMC Card  16GB                            | 5         | 1.6%    |
| Unknown MMC Card  4GB                             | 4         | 1.28%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 4         | 1.28%   |
| Unknown MMC Card  64GB                            | 3         | 0.96%   |
| Unknown MMC Card  32GB                            | 3         | 0.96%   |
| Unknown MMC Card                                  | 3         | 0.96%   |
| Toshiba KXG50ZNV256G 256GB                        | 3         | 0.96%   |
| SK hynix BC501 NVMe Solid State Drive 512GB       | 3         | 0.96%   |
| Samsung SSD 870 EVO 1TB                           | 3         | 0.96%   |
| Crucial CT500MX500SSD1 500GB                      | 3         | 0.96%   |
| Crucial CT1000MX500SSD1 1TB                       | 3         | 0.96%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 2         | 0.64%   |
| WDC WD3000BLFS-60YBU2 304GB                       | 2         | 0.64%   |
| Unknown SD/MMC/MS PRO 128GB                       | 2         | 0.64%   |
| Toshiba MQ01ABD100 1TB                            | 2         | 0.64%   |
| Toshiba MQ01ABD075 752GB                          | 2         | 0.64%   |
| Seagate ST4000VN008-2DR1 4TB                      | 2         | 0.64%   |
| Seagate ST380815AS 80GB                           | 2         | 0.64%   |
| Samsung SSD 980 PRO 1TB                           | 2         | 0.64%   |
| Samsung SSD 970 EVO Plus 250GB                    | 2         | 0.64%   |
| Samsung SSD 960 EVO 500GB                         | 2         | 0.64%   |
| Samsung SSD 870 QVO 1TB                           | 2         | 0.64%   |
| Samsung SSD 860 1TB                               | 2         | 0.64%   |
| Samsung NVMe SSD Drive 1024GB                     | 2         | 0.64%   |
| Kingston SV300S37A120G 120GB SSD                  | 2         | 0.64%   |
| Kingston SA400S37120G 120GB SSD                   | 2         | 0.64%   |
| Kingston SA400S3 960GB SSD                        | 2         | 0.64%   |
| Intenso SSD 128GB                                 | 2         | 0.64%   |
| HP LOGICAL VOLUME 160GB                           | 2         | 0.64%   |
| Crucial CT120BX500SSD1 120GB                      | 2         | 0.64%   |
| A-DATA SU800 128GB SSD                            | 2         | 0.64%   |
| Unknown                                           | 2         | 0.64%   |
| WDC WDS500G2X0C-00L350 500GB                      | 1         | 0.32%   |
| WDC WDS500G2B0A 500GB SSD                         | 1         | 0.32%   |
| WDC WDS250G2B0B-00YS70 250GB SSD                  | 1         | 0.32%   |
| WDC WDS250G2B0B 250GB SSD                         | 1         | 0.32%   |
| WDC WDS250G2B0A 250GB SSD                         | 1         | 0.32%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 1         | 0.32%   |
| WDC WD80EMAZ-00WJTA0 8TB                          | 1         | 0.32%   |
| WDC WD80EFZZ-68B 8TB                              | 1         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 25        | 53     | 24.04%  |
| Seagate             | 25        | 62     | 24.04%  |
| Toshiba             | 15        | 17     | 14.42%  |
| Hitachi             | 12        | 12     | 11.54%  |
| HGST                | 10        | 10     | 9.62%   |
| Samsung Electronics | 5         | 9      | 4.81%   |
| Unknown             | 2         | 2      | 1.92%   |
| Hewlett-Packard     | 2         | 4      | 1.92%   |
| Fujitsu             | 2         | 2      | 1.92%   |
| SINTECHI            | 1         | 1      | 0.96%   |
| Maxtor              | 1         | 1      | 0.96%   |
| JMicron Technology  | 1         | 1      | 0.96%   |
| IBM                 | 1         | 1      | 0.96%   |
| EDILOCA             | 1         | 1      | 0.96%   |
| ASMT                | 1         | 1      | 0.96%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 27     | 17.58%  |
| Crucial             | 12        | 21     | 13.19%  |
| Kingston            | 10        | 12     | 10.99%  |
| WDC                 | 5         | 7      | 5.49%   |
| Intel               | 5         | 7      | 5.49%   |
| A-DATA Technology   | 5         | 6      | 5.49%   |
| SPCC                | 4         | 4      | 4.4%    |
| SanDisk             | 4         | 5      | 4.4%    |
| Transcend           | 2         | 2      | 2.2%    |
| SK hynix            | 2         | 3      | 2.2%    |
| Micron Technology   | 2         | 2      | 2.2%    |
| LITEON              | 2         | 2      | 2.2%    |
| Intenso             | 2         | 2      | 2.2%    |
| Corsair             | 2         | 3      | 2.2%    |
| Toshiba             | 1         | 1      | 1.1%    |
| Secure              | 1         | 1      | 1.1%    |
| PNY                 | 1         | 1      | 1.1%    |
| Plextor             | 1         | 1      | 1.1%    |
| OCZ                 | 1         | 1      | 1.1%    |
| Netac               | 1         | 1      | 1.1%    |
| Lexar               | 1         | 1      | 1.1%    |
| KingSpec            | 1         | 1      | 1.1%    |
| Kingmax             | 1         | 1      | 1.1%    |
| KC600               | 1         | 1      | 1.1%    |
| INNOVATION IT       | 1         | 1      | 1.1%    |
| Emtec               | 1         | 1      | 1.1%    |
| Dell                | 1         | 2      | 1.1%    |
| China               | 1         | 1      | 1.1%    |
| Aura                | 1         | 1      | 1.1%    |
| Apacer              | 1         | 1      | 1.1%    |
| AMD                 | 1         | 1      | 1.1%    |
| Unknown             | 1         | 1      | 1.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 87        | 177    | 38.67%  |
| SSD     | 73        | 122    | 32.44%  |
| NVMe    | 43        | 74     | 19.11%  |
| MMC     | 21        | 28     | 9.33%   |
| Unknown | 1         | 2      | 0.44%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 132       | 285    | 63.77%  |
| NVMe | 43        | 74     | 20.77%  |
| MMC  | 21        | 28     | 10.14%  |
| SAS  | 11        | 16     | 5.31%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 107       | 178    | 66.05%  |
| 0.51-1.0   | 33        | 49     | 20.37%  |
| 3.01-4.0   | 6         | 20     | 3.7%    |
| 4.01-10.0  | 6         | 24     | 3.7%    |
| 1.01-2.0   | 4         | 8      | 2.47%   |
| 2.01-3.0   | 3         | 7      | 1.85%   |
| 10.01-20.0 | 3         | 13     | 1.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 42        | 22.34%  |
| Unknown        | 34        | 18.09%  |
| 1-20           | 29        | 15.43%  |
| 251-500        | 18        | 9.57%   |
| 501-1000       | 16        | 8.51%   |
| More than 3000 | 13        | 6.91%   |
| 21-50          | 13        | 6.91%   |
| 51-100         | 11        | 5.85%   |
| 1001-2000      | 8         | 4.26%   |
| 2001-3000      | 4         | 2.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 102       | 54.55%  |
| Unknown        | 34        | 18.18%  |
| 21-50          | 13        | 6.95%   |
| 51-100         | 13        | 6.95%   |
| 251-500        | 10        | 5.35%   |
| 501-1000       | 5         | 2.67%   |
| 101-250        | 3         | 1.6%    |
| 1001-2000      | 3         | 1.6%    |
| More than 3000 | 2         | 1.07%   |
| 2001-3000      | 2         | 1.07%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD3000BLFS-60YBU2 304GB                    | 2         | 14     | 6.45%   |
| WDC WD3200AAKX-0 320GB                         | 1         | 1      | 3.23%   |
| WDC WD10SPZX-80Z10T2 1TB                       | 1         | 1      | 3.23%   |
| Toshiba MK4009GAL 40GB                         | 1         | 1      | 3.23%   |
| Toshiba MK3252GS 320GB                         | 1         | 1      | 3.23%   |
| Secure Net 256GB SSD                           | 1         | 1      | 3.23%   |
| Seagate ST9250315AS 250GB                      | 1         | 1      | 3.23%   |
| Seagate ST500LM021-1KJ152 500GB                | 1         | 1      | 3.23%   |
| Seagate ST320LT007-9ZV14 320GB                 | 1         | 2      | 3.23%   |
| Seagate ST2000LM015-2E81 2TB                   | 1         | 1      | 3.23%   |
| SanDisk SDSA6MM 16GB SSD                       | 1         | 1      | 3.23%   |
| Samsung Electronics SSD PM81 128GB             | 1         | 1      | 3.23%   |
| Samsung Electronics SP0411N 40GB               | 1         | 2      | 3.23%   |
| Samsung Electronics HM160HI 160GB              | 1         | 2      | 3.23%   |
| Netac SSD 256GB                                | 1         | 1      | 3.23%   |
| Micron Technology 1100_MTFDDAK256TBN 256GB SSD | 1         | 1      | 3.23%   |
| Maxtor 2B020H1 20GB                            | 1         | 1      | 3.23%   |
| Kingmax SSD 120G                               | 1         | 1      | 3.23%   |
| Hitachi HTS725025A9A364 250GB                  | 1         | 1      | 3.23%   |
| Hitachi HTS723232A7A364 320GB                  | 1         | 1      | 3.23%   |
| Hitachi HTS722080K9A300 80GB                   | 1         | 1      | 3.23%   |
| Hitachi HTS72101 99GB                          | 1         | 1      | 3.23%   |
| Hitachi HTC426040G9AT00 40GB                   | 1         | 1      | 3.23%   |
| HGST HTS725050A7 500GB                         | 1         | 1      | 3.23%   |
| HGST HTS721010A9E630 1TB                       | 1         | 1      | 3.23%   |
| HGST HTS545050A7E380 500GB                     | 1         | 1      | 3.23%   |
| Corsair Force LE SSD 120GB                     | 1         | 2      | 3.23%   |
| A-DATA Technology SU800 128GB SSD              | 1         | 2      | 3.23%   |
| A-DATA Technology IM2P33F8ABR1-1TB             | 1         | 1      | 3.23%   |
| Unknown                                        | 1         | 1      | 3.23%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 5         | 5      | 16.13%  |
| WDC                 | 4         | 16     | 12.9%   |
| Seagate             | 4         | 5      | 12.9%   |
| Samsung Electronics | 3         | 5      | 9.68%   |
| HGST                | 3         | 3      | 9.68%   |
| Toshiba             | 2         | 2      | 6.45%   |
| A-DATA Technology   | 2         | 3      | 6.45%   |
| Secure              | 1         | 1      | 3.23%   |
| SanDisk             | 1         | 1      | 3.23%   |
| Netac               | 1         | 1      | 3.23%   |
| Micron Technology   | 1         | 1      | 3.23%   |
| Maxtor              | 1         | 1      | 3.23%   |
| Kingmax             | 1         | 1      | 3.23%   |
| Corsair             | 1         | 2      | 3.23%   |
| Unknown             | 1         | 1      | 3.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 5         | 5      | 23.81%  |
| WDC                 | 4         | 16     | 19.05%  |
| Seagate             | 4         | 5      | 19.05%  |
| HGST                | 3         | 3      | 14.29%  |
| Toshiba             | 2         | 2      | 9.52%   |
| Samsung Electronics | 2         | 4      | 9.52%   |
| Maxtor              | 1         | 1      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 21        | 36     | 70%     |
| SSD  | 8         | 11     | 26.67%  |
| NVMe | 1         | 1      | 3.33%   |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 108       | 248    | 53.2%   |
| Detected | 67        | 107    | 33%     |
| Malfunc  | 28        | 48     | 13.79%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 120       | 55.81%  |
| AMD                          | 24        | 11.16%  |
| Samsung Electronics          | 18        | 8.37%   |
| SanDisk                      | 8         | 3.72%   |
| VIA Technologies             | 4         | 1.86%   |
| Toshiba America Info Systems | 4         | 1.86%   |
| SK hynix                     | 4         | 1.86%   |
| LSI Logic / Symbios Logic    | 4         | 1.86%   |
| ASMedia Technology           | 4         | 1.86%   |
| ADATA Technology             | 4         | 1.86%   |
| Nvidia                       | 3         | 1.4%    |
| Marvell Technology Group     | 3         | 1.4%    |
| Realtek Semiconductor        | 2         | 0.93%   |
| Micron Technology            | 2         | 0.93%   |
| KIOXIA                       | 2         | 0.93%   |
| Hewlett-Packard              | 2         | 0.93%   |
| Adaptec                      | 2         | 0.93%   |
| Promise Technology           | 1         | 0.47%   |
| Phison Electronics           | 1         | 0.47%   |
| Micron/Crucial Technology    | 1         | 0.47%   |
| Kingston Technology Company  | 1         | 0.47%   |
| Broadcom / LSI               | 1         | 0.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 19        | 7.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 14        | 5.3%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 11        | 4.17%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 8         | 3.03%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 7         | 2.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 2.27%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 5         | 1.89%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 5         | 1.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5         | 1.89%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 4         | 1.52%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 4         | 1.52%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 1.52%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 4         | 1.52%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 1.52%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 1.52%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 1.52%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 4         | 1.52%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 3         | 1.14%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 3         | 1.14%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.14%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 1.14%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 3         | 1.14%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller               | 3         | 1.14%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.14%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3         | 1.14%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 1.14%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 1.14%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 3         | 1.14%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3         | 1.14%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 3         | 1.14%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 1.14%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 1.14%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 1.14%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 2         | 0.76%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                              | 2         | 0.76%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 0.76%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 0.76%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2         | 0.76%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 2         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 119       | 56.13%  |
| NVMe | 42        | 19.81%  |
| IDE  | 32        | 15.09%  |
| RAID | 15        | 7.08%   |
| SAS  | 4         | 1.89%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 146       | 78.92%  |
| AMD          | 27        | 14.59%  |
| ARM          | 8         | 4.32%   |
| CentaurHauls | 2         | 1.08%   |
| iSH          | 1         | 0.54%   |
| Unknown      | 1         | 0.54%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz       | 3         | 1.55%   |
| Intel Celeron CPU N2807 @ 1.58GHz       | 3         | 1.55%   |
| Intel Xeon CPU L5640 @ 2.27GHz          | 2         | 1.04%   |
| Intel Pentium M processor 1.70GHz       | 2         | 1.04%   |
| Intel Pentium III (Coppermine)          | 2         | 1.04%   |
| Intel Core i9-10900 CPU @ 2.80GHz       | 2         | 1.04%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 2         | 1.04%   |
| Intel Core i5-4590T CPU @ 2.00GHz       | 2         | 1.04%   |
| Intel Core i5-4570 CPU @ 3.20GHz        | 2         | 1.04%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 2         | 1.04%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 2         | 1.04%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 2         | 1.04%   |
| Intel Core i3-4150 CPU @ 3.50GHz        | 2         | 1.04%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 2         | 1.04%   |
| Intel Celeron CPU J3455 @ 1.50GHz       | 2         | 1.04%   |
| Intel Celeron CPU J1900 @ 1.99GHz       | 2         | 1.04%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 2         | 1.04%   |
| Intel Atom CPU N455 @ 1.66GHz           | 2         | 1.04%   |
| Intel Atom CPU D525 @ 1.80GHz           | 2         | 1.04%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 1.04%   |
| ARM Processor                           | 2         | 1.04%   |
| ARM BCM2835 Processor                   | 2         | 1.04%   |
| ARM AArch64 Processor rev 4 (aarch64)   | 2         | 1.04%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 2         | 1.04%   |
| AMD FX-8350 Eight-Core Processor        | 2         | 1.04%   |
| iSH Processor                           | 1         | 0.52%   |
| Intel Xeon Gold 6336Y CPU @ 2.40GHz     | 1         | 0.52%   |
| Intel Xeon Gold 5218 CPU @ 2.30GHz      | 1         | 0.52%   |
| Intel Xeon E-2176M CPU @ 2.70GHz        | 1         | 0.52%   |
| Intel Xeon CPU X3430 @ 2.40GHz          | 1         | 0.52%   |
| Intel Xeon CPU L5630 @ 2.13GHz          | 1         | 0.52%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz     | 1         | 0.52%   |
| Intel Xeon CPU E5-2640 v4 @ 2.40GHz     | 1         | 0.52%   |
| Intel Xeon CPU E3-1240L v3 @ 2.00GHz    | 1         | 0.52%   |
| Intel Pentium M processor 1.60GHz       | 1         | 0.52%   |
| Intel Pentium M processor 1.50GHz       | 1         | 0.52%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz  | 1         | 0.52%   |
| Intel Pentium CPU N4200 @ 1.10GHz       | 1         | 0.52%   |
| Intel Pentium CPU N3710 @ 1.60GHz       | 1         | 0.52%   |
| Intel Pentium CPU G3460 @ 3.50GHz       | 1         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                 | Computers | Percent |
|-----------------------|-----------|---------|
| Intel Core i5         | 35        | 18.42%  |
| Other                 | 20        | 10.53%  |
| Intel Core i7         | 20        | 10.53%  |
| Intel Celeron         | 18        | 9.47%   |
| Intel Core i3         | 14        | 7.37%   |
| Intel Atom            | 12        | 6.32%   |
| Intel Xeon            | 8         | 4.21%   |
| Intel Core 2 Duo      | 6         | 3.16%   |
| Intel Pentium         | 5         | 2.63%   |
| AMD Ryzen 7           | 5         | 2.63%   |
| Intel Pentium M       | 4         | 2.11%   |
| AMD Ryzen 5           | 4         | 2.11%   |
| Intel Genuine         | 3         | 1.58%   |
| Intel Core i9         | 3         | 1.58%   |
| Intel Pentium III     | 2         | 1.05%   |
| Intel Core 2          | 2         | 1.05%   |
| ARM BCM               | 2         | 1.05%   |
| ARM AArch64           | 2         | 1.05%   |
| AMD Ryzen 9           | 2         | 1.05%   |
| AMD FX                | 2         | 1.05%   |
| AMD A6                | 2         | 1.05%   |
| AMD A4                | 2         | 1.05%   |
| Intel Xeon Gold       | 1         | 0.53%   |
| Intel Pentium Dual    | 1         | 0.53%   |
| Intel Core Solo       | 1         | 0.53%   |
| Intel Core m3         | 1         | 0.53%   |
| Intel Core Duo        | 1         | 0.53%   |
| Intel Celeron M       | 1         | 0.53%   |
| CentaurHauls VIA Eden | 1         | 0.53%   |
| ARM ARMv7             | 1         | 0.53%   |
| AMD Turion 64 Mobile  | 1         | 0.53%   |
| AMD Sempron           | 1         | 0.53%   |
| AMD Ryzen 3           | 1         | 0.53%   |
| AMD GX                | 1         | 0.53%   |
| AMD G                 | 1         | 0.53%   |
| AMD E2                | 1         | 0.53%   |
| AMD E1                | 1         | 0.53%   |
| AMD A8                | 1         | 0.53%   |
| AMD A10               | 1         | 0.53%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 73        | 38.42%  |
| 4       | 62        | 32.63%  |
| 1       | 19        | 10%     |
| 8       | 7         | 3.68%   |
| 6       | 7         | 3.68%   |
| Unknown | 7         | 3.68%   |
| 12      | 5         | 2.63%   |
| 10      | 4         | 2.11%   |
| 48      | 1         | 0.53%   |
| 32      | 1         | 0.53%   |
| 24      | 1         | 0.53%   |
| 16      | 1         | 0.53%   |
| 14      | 1         | 0.53%   |
| 3       | 1         | 0.53%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 171       | 92.93%  |
| Unknown | 7         | 3.8%    |
| 2       | 4         | 2.17%   |
| 0       | 2         | 1.09%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 89        | 48.63%  |
| 2       | 87        | 47.54%  |
| Unknown | 7         | 3.83%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 98        | 52.69%  |
| 32-bit, 64-bit | 82        | 44.09%  |
| 32-bit         | 5         | 2.69%   |
| 64-bit         | 1         | 0.54%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 115       | 58.38%  |
| 0x306c3    | 8         | 4.06%   |
| 0x306a9    | 5         | 2.54%   |
| 0x30678    | 5         | 2.54%   |
| 0x906ea    | 4         | 2.03%   |
| 0x20655    | 4         | 2.03%   |
| 0x106ca    | 4         | 2.03%   |
| 0x506e3    | 3         | 1.52%   |
| 0x206c2    | 3         | 1.52%   |
| 0x806eb    | 2         | 1.02%   |
| 0x806c1    | 2         | 1.02%   |
| 0x506c9    | 2         | 1.02%   |
| 0x406c4    | 2         | 1.02%   |
| 0x206a7    | 2         | 1.02%   |
| 0x106e5    | 2         | 1.02%   |
| 0x1067a    | 2         | 1.02%   |
| 0x08108109 | 2         | 1.02%   |
| 0x08108102 | 2         | 1.02%   |
| 0x06006704 | 2         | 1.02%   |
| 0xb0671    | 1         | 0.51%   |
| 0xa0671    | 1         | 0.51%   |
| 0xa0655    | 1         | 0.51%   |
| 0xa0652    | 1         | 0.51%   |
| 0x906a3    | 1         | 0.51%   |
| 0x90672    | 1         | 0.51%   |
| 0x806ec    | 1         | 0.51%   |
| 0x806ea    | 1         | 0.51%   |
| 0x706e5    | 1         | 0.51%   |
| 0x6fd      | 1         | 0.51%   |
| 0x6f2      | 1         | 0.51%   |
| 0x6d8      | 1         | 0.51%   |
| 0x68a      | 1         | 0.51%   |
| 0x683      | 1         | 0.51%   |
| 0x606a6    | 1         | 0.51%   |
| 0x306d4    | 1         | 0.51%   |
| 0x0a20120e | 1         | 0.51%   |
| 0x08701030 | 1         | 0.51%   |
| 0x08701021 | 1         | 0.51%   |
| 0x08608103 | 1         | 0.51%   |
| 0x0810100b | 1         | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 19        | 9.95%   |
| Haswell          | 18        | 9.42%   |
| Silvermont       | 17        | 8.9%    |
| Unknown          | 17        | 8.9%    |
| P6               | 10        | 5.24%   |
| Westmere         | 9         | 4.71%   |
| Skylake          | 9         | 4.71%   |
| IvyBridge        | 9         | 4.71%   |
| SandyBridge      | 7         | 3.66%   |
| Penryn           | 6         | 3.14%   |
| Core             | 6         | 3.14%   |
| Broadwell        | 6         | 3.14%   |
| Bonnell          | 6         | 3.14%   |
| Zen+             | 5         | 2.62%   |
| IceLake          | 5         | 2.62%   |
| Goldmont         | 5         | 2.62%   |
| Alderlake Hybrid | 5         | 2.62%   |
| TigerLake        | 4         | 2.09%   |
| Excavator        | 4         | 2.09%   |
| Zen 2            | 3         | 1.57%   |
| Piledriver       | 3         | 1.57%   |
| Jaguar           | 3         | 1.57%   |
| CometLake        | 3         | 1.57%   |
| Zen 3            | 2         | 1.05%   |
| Nehalem          | 2         | 1.05%   |
| Bobcat           | 2         | 1.05%   |
| Zen              | 1         | 0.52%   |
| Puma             | 1         | 0.52%   |
| K8 Hammer        | 1         | 0.52%   |
| K6               | 1         | 0.52%   |
| K10              | 1         | 0.52%   |
| Goldmont plus    | 1         | 0.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 121       | 60.5%   |
| AMD                        | 41        | 20.5%   |
| Nvidia                     | 25        | 12.5%   |
| VIA Technologies           | 4         | 2%      |
| Matrox Electronics Systems | 4         | 2%      |
| Neomagic                   | 2         | 1%      |
| ASPEED Technology          | 2         | 1%      |
| S3 Graphics                | 1         | 0.5%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 12        | 5.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 10        | 4.31%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 3.02%   |
| Intel UHD Graphics 620                                                                   | 5         | 2.16%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 2.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 2.16%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 2.16%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 2.16%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 5         | 2.16%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 1.72%   |
| Intel HD Graphics 500                                                                    | 4         | 1.72%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 1.72%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4         | 1.72%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 1.29%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 1.29%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.29%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 1.29%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 3         | 1.29%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.29%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.29%   |
| AMD ES1000                                                                               | 3         | 1.29%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 2         | 0.86%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 0.86%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.86%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.86%   |
| Intel HD Graphics 630                                                                    | 2         | 0.86%   |
| Intel HD Graphics 620                                                                    | 2         | 0.86%   |
| Intel HD Graphics 530                                                                    | 2         | 0.86%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 0.86%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.86%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.86%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 0.86%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 0.86%   |
| Intel AlderLake-S GT1                                                                    | 2         | 0.86%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 2         | 0.86%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 0.86%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.86%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 2         | 0.86%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 0.86%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 2         | 0.86%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 94        | 49.74%  |
| 1 x AMD         | 33        | 17.46%  |
| Intel + Nvidia  | 14        | 7.41%   |
| Other           | 11        | 5.82%   |
| 2 x Intel       | 9         | 4.76%   |
| 1 x Nvidia      | 8         | 4.23%   |
| Intel + AMD     | 4         | 2.12%   |
| 1 x VIA         | 3         | 1.59%   |
| 1 x Matrox      | 3         | 1.59%   |
| 1 x Neomagic    | 2         | 1.06%   |
| 1 x ASPEED      | 2         | 1.06%   |
| AMD + Nvidia    | 2         | 1.06%   |
| 2 x AMD         | 1         | 0.53%   |
| 1 x S3 Graphics | 1         | 0.53%   |
| Nvidia + Matrox | 1         | 0.53%   |
| AMD + VIA       | 1         | 0.53%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 152       | 81.28%  |
| Unknown     | 31        | 16.58%  |
| Proprietary | 4         | 2.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 154       | 82.8%   |
| 0.01-0.5   | 14        | 7.53%   |
| 1.01-2.0   | 6         | 3.23%   |
| 7.01-8.0   | 4         | 2.15%   |
| 0.51-1.0   | 4         | 2.15%   |
| 3.01-4.0   | 2         | 1.08%   |
| 2.01-3.0   | 1         | 0.54%   |
| 8.01-16.0  | 1         | 0.54%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 17        | 10.83%  |
| AU Optronics            | 16        | 10.19%  |
| BOE                     | 13        | 8.28%   |
| Samsung Electronics     | 11        | 7.01%   |
| Dell                    | 10        | 6.37%   |
| Chimei Innolux          | 10        | 6.37%   |
| Goldstar                | 9         | 5.73%   |
| AOC                     | 6         | 3.82%   |
| BenQ                    | 5         | 3.18%   |
| Hewlett-Packard         | 4         | 2.55%   |
| Apple                   | 4         | 2.55%   |
| LG Philips              | 3         | 1.91%   |
| Lenovo                  | 3         | 1.91%   |
| InfoVision              | 3         | 1.91%   |
| Chi Mei Optoelectronics | 3         | 1.91%   |
| Acer                    | 3         | 1.91%   |
| Vizio                   | 2         | 1.27%   |
| Sony                    | 2         | 1.27%   |
| Sharp                   | 2         | 1.27%   |
| Philips                 | 2         | 1.27%   |
| PANDA                   | 2         | 1.27%   |
| Jean                    | 2         | 1.27%   |
| HannStar                | 2         | 1.27%   |
| CSO                     | 2         | 1.27%   |
| Belinea                 | 2         | 1.27%   |
| ViewSonic               | 1         | 0.64%   |
| SKY                     | 1         | 0.64%   |
| Sceptre Tech            | 1         | 0.64%   |
| Quanta Display          | 1         | 0.64%   |
| ONN                     | 1         | 0.64%   |
| Mi                      | 1         | 0.64%   |
| KVM                     | 1         | 0.64%   |
| Huion                   | 1         | 0.64%   |
| HJW                     | 1         | 0.64%   |
| Envision                | 1         | 0.64%   |
| Elo Touch               | 1         | 0.64%   |
| Element                 | 1         | 0.64%   |
| EDI                     | 1         | 0.64%   |
| DENON                   | 1         | 0.64%   |
| CTC                     | 1         | 0.64%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SE790C SAM0BFE 3440x1440 797x333mm 34.0-inch      | 3         | 1.73%   |
| LG Display LCD Monitor LGD0597 1920x1080 294x165mm 13.3-inch          | 3         | 1.73%   |
| Dell 2009W DEL4041 1680x1050 433x270mm 20.1-inch                      | 3         | 1.73%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 1.16%   |
| Jean JT229x6-4 JEN51C6 1680x1050 474x297mm 22.0-inch                  | 2         | 1.16%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 2         | 1.16%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                 | 2         | 1.16%   |
| BOE LCD Monitor BOE08D5 1920x1080 344x194mm 15.5-inch                 | 2         | 1.16%   |
| Belinea B101555 MAX05DF 1024x768 304x228mm 15.0-inch                  | 2         | 1.16%   |
| Vizio VX42L HDTV10A VIZ0030 1366x768 930x523mm 42.0-inch              | 1         | 0.58%   |
| Vizio D40f-J09 VIZ1044 1920x1080 890x490mm 40.0-inch                  | 1         | 0.58%   |
| ViewSonic VG2030wm VSCA51E 1680x1050 433x270mm 20.1-inch              | 1         | 0.58%   |
| Sony TV *02 SNY9703 1920x1080 1439x809mm 65.0-inch                    | 1         | 0.58%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch  | 1         | 0.58%   |
| SKY TV-monitor SKY0001 1920x1080 890x500mm 40.2-inch                  | 1         | 0.58%   |
| Sharp LCD Monitor SHP1513 1920x1080 309x174mm 14.0-inch               | 1         | 0.58%   |
| Sharp LCD Monitor SHP14AF 1920x1200 288x180mm 13.4-inch               | 1         | 0.58%   |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 530x290mm 23.8-inch        | 1         | 0.58%   |
| Samsung Electronics SyncMaster SAM0320 1680x1050 474x296mm 22.0-inch  | 1         | 0.58%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 1         | 0.58%   |
| Samsung Electronics S27A950D SAM079E 1920x1080 598x336mm 27.0-inch    | 1         | 0.58%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.58%   |
| Samsung Electronics LS24AG30x SAM7179 1920x1080 527x296mm 23.8-inch   | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC5A42 1366x768 309x174mm 14.0-inch  | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC5642 1280x768 305x183mm 14.0-inch  | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch  | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch  | 1         | 0.58%   |
| Quanta Display LCD Monitor QDS0020 1280x768 305x183mm 14.0-inch       | 1         | 0.58%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch               | 1         | 0.58%   |
| Philips PHL 216V6 PHLC10D 1920x1080 419x262mm 19.5-inch               | 1         | 0.58%   |
| PANDA LCD Monitor NCP0056 1920x1080 309x174mm 14.0-inch               | 1         | 0.58%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 0.58%   |
| ONN ONA18HO015 ONN0101 1920x1080 698x393mm 31.5-inch                  | 1         | 0.58%   |
| Mi Monitor XMI2701 2560x1440 597x336mm 27.0-inch                      | 1         | 0.58%   |
| LG Philips LCD Monitor LPLE100 1280x800 331x207mm 15.4-inch           | 1         | 0.58%   |
| LG Philips LCD Monitor LPLB600 1280x800 260x160mm 12.0-inch           | 1         | 0.58%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch           | 1         | 0.58%   |
| LG Display LP116WH2-TLC1 LGD0232 1366x768 256x144mm 11.6-inch         | 1         | 0.58%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 1         | 0.58%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 45        | 30.61%  |
| 1366x768 (WXGA)    | 32        | 21.77%  |
| 1280x800 (WXGA)    | 8         | 5.44%   |
| 3840x2160 (4K)     | 7         | 4.76%   |
| 1680x1050 (WSXGA+) | 7         | 4.76%   |
| 2560x1440 (QHD)    | 6         | 4.08%   |
| 1280x1024 (SXGA)   | 6         | 4.08%   |
| 1600x900 (HD+)     | 5         | 3.4%    |
| 1024x768 (XGA)     | 5         | 3.4%    |
| 3440x1440          | 4         | 2.72%   |
| 1920x1200 (WUXGA)  | 4         | 2.72%   |
| 1024x600           | 4         | 2.72%   |
| 1440x900 (WXGA+)   | 3         | 2.04%   |
| 2880x1800          | 2         | 1.36%   |
| 2560x1080          | 2         | 1.36%   |
| 1360x768           | 2         | 1.36%   |
| 1280x768           | 2         | 1.36%   |
| 2560x1700          | 1         | 0.68%   |
| 1400x1050          | 1         | 0.68%   |
| 1280x960           | 1         | 0.68%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 35        | 22.44%  |
| 13     | 15        | 9.62%   |
| 14     | 14        | 8.97%   |
| 17     | 12        | 7.69%   |
| 23     | 10        | 6.41%   |
| 27     | 9         | 5.77%   |
| 24     | 7         | 4.49%   |
| 21     | 5         | 3.21%   |
| 20     | 5         | 3.21%   |
| 19     | 5         | 3.21%   |
| 11     | 5         | 3.21%   |
| 34     | 4         | 2.56%   |
| 31     | 4         | 2.56%   |
| 18     | 4         | 2.56%   |
| 12     | 4         | 2.56%   |
| 10     | 4         | 2.56%   |
| 22     | 3         | 1.92%   |
| 40     | 2         | 1.28%   |
| 32     | 2         | 1.28%   |
| 72     | 1         | 0.64%   |
| 65     | 1         | 0.64%   |
| 60     | 1         | 0.64%   |
| 42     | 1         | 0.64%   |
| 29     | 1         | 0.64%   |
| 25     | 1         | 0.64%   |
| 16     | 1         | 0.64%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 59        | 40.14%  |
| 501-600     | 23        | 15.65%  |
| 201-300     | 21        | 14.29%  |
| 401-500     | 17        | 11.56%  |
| 351-400     | 11        | 7.48%   |
| 701-800     | 5         | 3.4%    |
| 601-700     | 5         | 3.4%    |
| 801-900     | 2         | 1.36%   |
| 1001-1500   | 2         | 1.36%   |
| 1501-2000   | 1         | 0.68%   |
| 901-1000    | 1         | 0.68%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 94        | 68.61%  |
| 16/10 | 25        | 18.25%  |
| 5/4   | 6         | 4.38%   |
| 4/3   | 5         | 3.65%   |
| 21/9  | 5         | 3.65%   |
| 6/5   | 1         | 0.73%   |
| 3/2   | 1         | 0.73%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 34        | 22.82%  |
| 81-90          | 21        | 14.09%  |
| 201-250        | 18        | 12.08%  |
| 151-200        | 12        | 8.05%   |
| 301-350        | 10        | 6.71%   |
| 71-80          | 9         | 6.04%   |
| 351-500        | 8         | 5.37%   |
| 141-150        | 7         | 4.7%    |
| 121-130        | 6         | 4.03%   |
| 51-60          | 5         | 3.36%   |
| 41-50          | 4         | 2.68%   |
| More than 1000 | 3         | 2.01%   |
| 61-70          | 3         | 2.01%   |
| 251-300        | 3         | 2.01%   |
| 501-1000       | 3         | 2.01%   |
| 131-140        | 2         | 1.34%   |
| 111-120        | 1         | 0.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 48        | 34.53%  |
| 101-120       | 39        | 28.06%  |
| 121-160       | 33        | 23.74%  |
| 1-50          | 8         | 5.76%   |
| 161-240       | 8         | 5.76%   |
| More than 240 | 3         | 2.16%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 124       | 65.96%  |
| 0     | 50        | 26.6%   |
| 2     | 12        | 6.38%   |
| 4     | 1         | 0.53%   |
| 3     | 1         | 0.53%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 93        | 34.44%  |
| Intel                           | 82        | 30.37%  |
| Qualcomm Atheros                | 27        | 10%     |
| Broadcom                        | 24        | 8.89%   |
| Marvell Technology Group        | 4         | 1.48%   |
| Broadcom Limited                | 4         | 1.48%   |
| Xiaomi                          | 3         | 1.11%   |
| VIA Technologies                | 3         | 1.11%   |
| Qualcomm Atheros Communications | 3         | 1.11%   |
| TP-Link                         | 2         | 0.74%   |
| Qualcomm                        | 2         | 0.74%   |
| Nvidia                          | 2         | 0.74%   |
| Microchip Technology            | 2         | 0.74%   |
| Mellanox Technologies           | 2         | 0.74%   |
| MediaTek                        | 2         | 0.74%   |
| LSI                             | 2         | 0.74%   |
| ASIX Electronics                | 2         | 0.74%   |
| T & A Mobile Phones             | 1         | 0.37%   |
| Sigma Designs                   | 1         | 0.37%   |
| Ralink Technology               | 1         | 0.37%   |
| NetGear                         | 1         | 0.37%   |
| Google                          | 1         | 0.37%   |
| Dresden Elektronik              | 1         | 0.37%   |
| DisplayLink                     | 1         | 0.37%   |
| D-Link System                   | 1         | 0.37%   |
| D-Link                          | 1         | 0.37%   |
| Belkin Components               | 1         | 0.37%   |
| AMD                             | 1         | 0.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 58        | 17.01%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 13        | 3.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 11        | 3.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 9         | 2.64%   |
| Intel Wireless 7265                                                    | 6         | 1.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6         | 1.76%   |
| Intel Ethernet Controller I225-V                                       | 5         | 1.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 4         | 1.17%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 4         | 1.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 4         | 1.17%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 4         | 1.17%   |
| Intel Wireless 8265 / 8275                                             | 4         | 1.17%   |
| Intel Wi-Fi 6 AX200                                                    | 4         | 1.17%   |
| Intel I210 Gigabit Network Connection                                  | 4         | 1.17%   |
| Intel Ethernet Connection (2) I219-V                                   | 4         | 1.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 4         | 1.17%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 3         | 0.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 3         | 0.88%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 0.88%   |
| Qualcomm Atheros AR9271 802.11n                                        | 3         | 0.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 3         | 0.88%   |
| Intel Wireless 3160                                                    | 3         | 0.88%   |
| Intel Wi-Fi 6 AX201                                                    | 3         | 0.88%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 3         | 0.88%   |
| Intel I211 Gigabit Network Connection                                  | 3         | 0.88%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 0.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 3         | 0.88%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 3         | 0.88%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 3         | 0.88%   |
| Broadcom BCM43224 802.11a/b/g/n                                        | 3         | 0.88%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 2         | 0.59%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 2         | 0.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 2         | 0.59%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                          | 2         | 0.59%   |
| Intel Wireless 8260                                                    | 2         | 0.59%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 2         | 0.59%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection          | 2         | 0.59%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection               | 2         | 0.59%   |
| Intel Ethernet Connection (7) I219-V                                   | 2         | 0.59%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 54        | 42.86%  |
| Qualcomm Atheros                | 23        | 18.25%  |
| Realtek Semiconductor           | 18        | 14.29%  |
| Broadcom                        | 16        | 12.7%   |
| Qualcomm Atheros Communications | 3         | 2.38%   |
| Broadcom Limited                | 3         | 2.38%   |
| TP-Link                         | 2         | 1.59%   |
| MediaTek                        | 2         | 1.59%   |
| Ralink Technology               | 1         | 0.79%   |
| NetGear                         | 1         | 0.79%   |
| Marvell Technology Group        | 1         | 0.79%   |
| D-Link                          | 1         | 0.79%   |
| Belkin Components               | 1         | 0.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 9         | 6.57%   |
| Intel Wireless 7265                                                  | 6         | 4.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 4         | 2.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 4         | 2.92%   |
| Intel Wireless 8265 / 8275                                           | 4         | 2.92%   |
| Intel Wi-Fi 6 AX200                                                  | 4         | 2.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 4         | 2.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 3         | 2.19%   |
| Qualcomm Atheros AR9271 802.11n                                      | 3         | 2.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 3         | 2.19%   |
| Intel Wireless 3160                                                  | 3         | 2.19%   |
| Intel Wi-Fi 6 AX201                                                  | 3         | 2.19%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 3         | 2.19%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 3         | 2.19%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 3         | 2.19%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 3         | 2.19%   |
| Broadcom BCM43224 802.11a/b/g/n                                      | 3         | 2.19%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 2         | 1.46%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 2         | 1.46%   |
| Intel Wireless 8260                                                  | 2         | 1.46%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 2         | 1.46%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection        | 2         | 1.46%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection             | 2         | 1.46%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 2         | 1.46%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 2         | 1.46%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 2         | 1.46%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 2         | 1.46%   |
| Broadcom Limited BCM4352 802.11ac Dual Band Wireless Network Adapter | 2         | 1.46%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 2         | 1.46%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                  | 1         | 0.73%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 1         | 0.73%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 1         | 0.73%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 1         | 0.73%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1         | 0.73%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 1         | 0.73%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                           | 1         | 0.73%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 1         | 0.73%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                               | 1         | 0.73%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 1         | 0.73%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1         | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 85        | 48.02%  |
| Intel                    | 48        | 27.12%  |
| Broadcom                 | 13        | 7.34%   |
| Qualcomm Atheros         | 7         | 3.95%   |
| Xiaomi                   | 3         | 1.69%   |
| VIA Technologies         | 3         | 1.69%   |
| Marvell Technology Group | 3         | 1.69%   |
| Qualcomm                 | 2         | 1.13%   |
| Nvidia                   | 2         | 1.13%   |
| Microchip Technology     | 2         | 1.13%   |
| Mellanox Technologies    | 2         | 1.13%   |
| ASIX Electronics         | 2         | 1.13%   |
| T & A Mobile Phones      | 1         | 0.56%   |
| LSI                      | 1         | 0.56%   |
| DisplayLink              | 1         | 0.56%   |
| D-Link System            | 1         | 0.56%   |
| Broadcom Limited         | 1         | 0.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 58        | 29.9%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 13        | 6.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 11        | 5.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 6         | 3.09%   |
| Intel Ethernet Controller I225-V                                               | 5         | 2.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 4         | 2.06%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 4         | 2.06%   |
| Intel I210 Gigabit Network Connection                                          | 4         | 2.06%   |
| Intel Ethernet Connection (2) I219-V                                           | 4         | 2.06%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 3         | 1.55%   |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 1.55%   |
| Intel I211 Gigabit Network Connection                                          | 3         | 1.55%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 1.55%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 2         | 1.03%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                                  | 2         | 1.03%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 1.03%   |
| Intel Ethernet Connection (7) I219-LM                                          | 2         | 1.03%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 1.03%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 1.03%   |
| Intel Ethernet Connection (17) I219-LM                                         | 2         | 1.03%   |
| Intel 82579V Gigabit Network Connection                                        | 2         | 1.03%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                 | 2         | 1.03%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 2         | 1.03%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 1.03%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 1.03%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.52%   |
| T & A Mobile Phones TCL 20E                                                    | 1         | 0.52%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.52%   |
| Realtek Killer E2600 GbE Controller                                            | 1         | 0.52%   |
| Qualcomm SAMSUNG_Android                                                       | 1         | 0.52%   |
| Qualcomm Nokia G42 5G                                                          | 1         | 0.52%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.52%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.52%   |
| Nvidia MCP61 Ethernet                                                          | 1         | 0.52%   |
| Mellanox MT28908 Family [ConnectX-6]                                           | 1         | 0.52%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                          | 1         | 0.52%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.52%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 1         | 0.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 153       | 54.84%  |
| WiFi     | 116       | 41.58%  |
| Modem    | 8         | 2.87%   |
| Unknown  | 2         | 0.72%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 100       | 59.17%  |
| WiFi     | 69        | 40.83%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 90        | 48.65%  |
| 1     | 68        | 36.76%  |
| 0     | 16        | 8.65%   |
| 3     | 5         | 2.7%    |
| 4     | 4         | 2.16%   |
| 5     | 2         | 1.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 144       | 77.42%  |
| Yes  | 42        | 22.58%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 36        | 38.3%   |
| Realtek Semiconductor           | 9         | 9.57%   |
| Qualcomm Atheros Communications | 6         | 6.38%   |
| IMC Networks                    | 6         | 6.38%   |
| Apple                           | 6         | 6.38%   |
| Cambridge Silicon Radio         | 5         | 5.32%   |
| Broadcom                        | 5         | 5.32%   |
| Foxconn / Hon Hai               | 4         | 4.26%   |
| Lite-On Technology              | 3         | 3.19%   |
| ASUSTek Computer                | 3         | 3.19%   |
| Actions                         | 2         | 2.13%   |
| Toshiba                         | 1         | 1.06%   |
| MediaTek                        | 1         | 1.06%   |
| Marvell Semiconductor           | 1         | 1.06%   |
| Hewlett-Packard                 | 1         | 1.06%   |
| Edimax Technology               | 1         | 1.06%   |
| Dell                            | 1         | 1.06%   |
| Askey Computer                  | 1         | 1.06%   |
| Alps Electric                   | 1         | 1.06%   |
| Unknown                         | 1         | 1.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 8         | 8.33%   |
| Intel AX201 Bluetooth                                                               | 8         | 8.33%   |
| Realtek Bluetooth Radio                                                             | 6         | 6.25%   |
| Intel Bluetooth Device                                                              | 6         | 6.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 6         | 6.25%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 5         | 5.21%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 5         | 5.21%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 3.13%   |
| Intel AX200 Bluetooth                                                               | 3         | 3.13%   |
| Apple Bluetooth Host Controller                                                     | 3         | 3.13%   |
| Realtek 802.11ac WLAN Adapter                                                       | 2         | 2.08%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 2.08%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 2.08%   |
| IMC Networks Bluetooth Device                                                       | 2         | 2.08%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth                                     | 2         | 2.08%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 2.08%   |
| Actions general adapter                                                             | 2         | 2.08%   |
| Toshiba Bluetooth Device                                                            | 1         | 1.04%   |
| Realtek Bluetooth 5.3 Radio                                                         | 1         | 1.04%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 1.04%   |
| MediaTek Wireless_Device                                                            | 1         | 1.04%   |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 1         | 1.04%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 1.04%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 1.04%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 1.04%   |
| Intel AX211 Bluetooth                                                               | 1         | 1.04%   |
| Intel AX210 Bluetooth                                                               | 1         | 1.04%   |
| IMC Networks Wireless_Device                                                        | 1         | 1.04%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 1.04%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 1.04%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 1         | 1.04%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.04%   |
| Edimax Edimax Bluetooth Adapter                                                     | 1         | 1.04%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 1.04%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 1.04%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 1.04%   |
| Broadcom BCM20702A0                                                                 | 1         | 1.04%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 1.04%   |
| Broadcom BCM2045 Bluetooth                                                          | 1         | 1.04%   |
| ASUS BT-270 Bluetooth Adapter                                                       | 1         | 1.04%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 126       | 63.64%  |
| AMD                                  | 37        | 18.69%  |
| Nvidia                               | 11        | 5.56%   |
| VIA Technologies                     | 4         | 2.02%   |
| C-Media Electronics                  | 3         | 1.52%   |
| Logitech                             | 2         | 1.01%   |
| Generalplus Technology               | 2         | 1.01%   |
| Creative Labs                        | 2         | 1.01%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.51%   |
| Texas Instruments                    | 1         | 0.51%   |
| SteelSeries ApS                      | 1         | 0.51%   |
| Sennheiser Communications            | 1         | 0.51%   |
| RODE Microphones                     | 1         | 0.51%   |
| Realtek Semiconductor                | 1         | 0.51%   |
| Nordic Semiconductor ASA             | 1         | 0.51%   |
| Native Instruments                   | 1         | 0.51%   |
| Focusrite-Novation                   | 1         | 0.51%   |
| Cirrus Logic                         | 1         | 0.51%   |
| Apple                                | 1         | 0.51%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 13        | 4.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 11        | 4.21%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 3.83%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 10        | 3.83%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 3.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 8         | 3.07%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 8         | 3.07%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 2.68%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 2.68%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 2.68%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 2.3%    |
| AMD FCH Azalia Controller                                                                         | 6         | 2.3%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 5         | 1.92%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 1.92%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 5         | 1.92%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 1.53%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.53%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 1.53%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1.53%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 1.53%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.53%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1.15%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.15%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.15%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 1.15%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.15%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 1.15%   |
| AMD High Definition Audio Controller                                                              | 3         | 1.15%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 2         | 0.77%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 2         | 0.77%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.77%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 0.77%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 2         | 0.77%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 0.77%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.77%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.77%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 0.77%   |
| Intel DG2 Audio Controller                                                                        | 2         | 0.77%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.77%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 31        | 16.76%  |
| Unknown             | 30        | 16.22%  |
| SK hynix            | 30        | 16.22%  |
| Micron Technology   | 18        | 9.73%   |
| Crucial             | 18        | 9.73%   |
| Kingston            | 11        | 5.95%   |
| Elpida              | 10        | 5.41%   |
| Corsair             | 8         | 4.32%   |
| A-DATA Technology   | 5         | 2.7%    |
| Unknown             | 4         | 2.16%   |
| Unknown (ABCD)      | 2         | 1.08%   |
| Nanya Technology    | 2         | 1.08%   |
| Visipro             | 1         | 0.54%   |
| Transcend           | 1         | 0.54%   |
| Team                | 1         | 0.54%   |
| Smart Brazil        | 1         | 0.54%   |
| Smart               | 1         | 0.54%   |
| Ramaxel Technology  | 1         | 0.54%   |
| Qimonda             | 1         | 0.54%   |
| PNY                 | 1         | 0.54%   |
| Patriot             | 1         | 0.54%   |
| Novatech            | 1         | 0.54%   |
| Lexar               | 1         | 0.54%   |
| Hewlett-Packard     | 1         | 0.54%   |
| GOODRAM             | 1         | 0.54%   |
| Gold Key            | 1         | 0.54%   |
| G.Skill             | 1         | 0.54%   |
| Cors                | 1         | 0.54%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 4         | 1.9%    |
| Unknown RAM Module 512MB SODIMM DDR                              | 3         | 1.43%   |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 3         | 1.43%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 0.95%   |
| Unknown RAM Module 1GB SODIMM DRAM                               | 2         | 0.95%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 2         | 0.95%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 0.95%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.95%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.95%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.95%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s            | 2         | 0.95%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.95%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 0.95%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.95%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.95%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s              | 2         | 0.95%   |
| Elpida RAM EBJ41UF8BDW0-GN-F 4GB DIMM DDR3 1600MT/s              | 2         | 0.95%   |
| Crucial RAM BL16G36C16U4B.M16FE1 16GB DIMM DDR4 3600MT/s         | 2         | 0.95%   |
| Visipro RAM T2G88S1-H9H 2GB DIMM DDR3 1333MT/s                   | 1         | 0.48%   |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 0.48%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 0.48%   |
| Unknown RAM Module 512MB SODIMM DRAM                             | 1         | 0.48%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.48%   |
| Unknown RAM Module 512MB DIMM                                    | 1         | 0.48%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.48%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 1         | 0.48%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 0.48%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 0.48%   |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 1         | 0.48%   |
| Unknown RAM Module 2GB SODIMM LPDDR4 2133MT/s                    | 1         | 0.48%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 1         | 0.48%   |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                         | 1         | 0.48%   |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 1         | 0.48%   |
| Unknown RAM Module 256MB SODIMM DDR                              | 1         | 0.48%   |
| Unknown RAM Module 2048MB DIMM DDR3 1600MT/s                     | 1         | 0.48%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 1         | 0.48%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 0.48%   |
| Unknown RAM Module 1GB SODIMM DDR3 1066MT/s                      | 1         | 0.48%   |
| Unknown RAM Module 1GB SODIMM DDR3                               | 1         | 0.48%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 68        | 46.26%  |
| DDR4    | 38        | 25.85%  |
| SDRAM   | 8         | 5.44%   |
| LPDDR3  | 8         | 5.44%   |
| DDR2    | 7         | 4.76%   |
| DDR     | 6         | 4.08%   |
| LPDDR4  | 4         | 2.72%   |
| DRAM    | 3         | 2.04%   |
| DDR5    | 2         | 1.36%   |
| Unknown | 2         | 1.36%   |
| EEPROM  | 1         | 0.68%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 79        | 53.38%  |
| DIMM         | 54        | 36.49%  |
| Row Of Chips | 11        | 7.43%   |
| Unknown      | 2         | 1.35%   |
| RIMM         | 1         | 0.68%   |
| Chip         | 1         | 0.68%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 48        | 29.27%  |
| 8192  | 47        | 28.66%  |
| 2048  | 28        | 17.07%  |
| 1024  | 14        | 8.54%   |
| 16384 | 11        | 6.71%   |
| 512   | 6         | 3.66%   |
| 32768 | 5         | 3.05%   |
| 128   | 3         | 1.83%   |
| 256   | 1         | 0.61%   |
| 1     | 1         | 0.61%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 44        | 26.19%  |
| Unknown | 14        | 8.33%   |
| 2667    | 13        | 7.74%   |
| 1333    | 13        | 7.74%   |
| 2400    | 12        | 7.14%   |
| 3200    | 10        | 5.95%   |
| 667     | 8         | 4.76%   |
| 1867    | 7         | 4.17%   |
| 1334    | 7         | 4.17%   |
| 2133    | 6         | 3.57%   |
| 3600    | 5         | 2.98%   |
| 1067    | 3         | 1.79%   |
| 3800    | 2         | 1.19%   |
| 3266    | 2         | 1.19%   |
| 1866    | 2         | 1.19%   |
| 1800    | 2         | 1.19%   |
| 1066    | 2         | 1.19%   |
| 8400    | 1         | 0.6%    |
| 6000    | 1         | 0.6%    |
| 5808    | 1         | 0.6%    |
| 4800    | 1         | 0.6%    |
| 4267    | 1         | 0.6%    |
| 4199    | 1         | 0.6%    |
| 3666    | 1         | 0.6%    |
| 3066    | 1         | 0.6%    |
| 2200    | 1         | 0.6%    |
| 1400    | 1         | 0.6%    |
| 1331    | 1         | 0.6%    |
| 1200    | 1         | 0.6%    |
| 800     | 1         | 0.6%    |
| 533     | 1         | 0.6%    |
| 133     | 1         | 0.6%    |
| 33      | 1         | 0.6%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intermec Technologies | 1         | 33.33%  |
| Hewlett-Packard       | 1         | 33.33%  |
| Brother Industries    | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| Intermec PC43t           | 1         | 25%     |
| HP LaserJet 1020         | 1         | 25%     |
| HP Deskjet 3050A         | 1         | 25%     |
| Brother HL-L2360D series | 1         | 25%     |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 19        | 20.43%  |
| Realtek Semiconductor                  | 9         | 9.68%   |
| Microdia                               | 9         | 9.68%   |
| IMC Networks                           | 9         | 9.68%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 6.45%   |
| Bison Electronics                      | 6         | 6.45%   |
| Apple                                  | 5         | 5.38%   |
| Suyin                                  | 4         | 4.3%    |
| Quanta                                 | 4         | 4.3%    |
| Z-Star Microelectronics                | 2         | 2.15%   |
| Syntek                                 | 2         | 2.15%   |
| Sunplus Innovation Technology          | 2         | 2.15%   |
| Ricoh                                  | 2         | 2.15%   |
| Lite-On Technology                     | 2         | 2.15%   |
| Acer                                   | 2         | 2.15%   |
| Trust                                  | 1         | 1.08%   |
| Silicon Motion                         | 1         | 1.08%   |
| Samsung Electronics                    | 1         | 1.08%   |
| Olympus Optical                        | 1         | 1.08%   |
| MacroSilicon                           | 1         | 1.08%   |
| Luxvisions Innotech Limited            | 1         | 1.08%   |
| Logitech                               | 1         | 1.08%   |
| Linux Foundation                       | 1         | 1.08%   |
| Lenovo                                 | 1         | 1.08%   |
| Alcor Micro                            | 1         | 1.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                        | 4         | 4.26%   |
| Microdia Integrated_Webcam_HD                       | 4         | 4.26%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 3         | 3.19%   |
| IMC Networks Integrated Camera                      | 3         | 3.19%   |
| Chicony Integrated Camera                           | 3         | 3.19%   |
| Chicony HD Webcam                                   | 3         | 3.19%   |
| Realtek Acer 640 x 480 laptop camera                | 2         | 2.13%   |
| Microdia Laptop_Integrated_Webcam_2M                | 2         | 2.13%   |
| Chicony HP Wide Vision HD Camera                    | 2         | 2.13%   |
| Bison Integrated Camera                             | 2         | 2.13%   |
| Apple FaceTime HD Camera (Built-in)                 | 2         | 2.13%   |
| Z-Star Vimicro USB2.0 Camera                        | 1         | 1.06%   |
| Z-Star A4 TECH USB2.0 PC Camera J                   | 1         | 1.06%   |
| Trust QHD Webcam                                    | 1         | 1.06%   |
| Syntek Integrated Camera                            | 1         | 1.06%   |
| Syntek EasyCamera                                   | 1         | 1.06%   |
| Suyin Integrated_Webcam_HD                          | 1         | 1.06%   |
| Suyin HP Truevision HD                              | 1         | 1.06%   |
| Suyin HP High Definition 1MP Webcam                 | 1         | 1.06%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 1.06%   |
| Sunplus HP Universal Camera                         | 1         | 1.06%   |
| Sunplus HD WebCam                                   | 1         | 1.06%   |
| Silicon Motion NCM-G102                             | 1         | 1.06%   |
| Samsung Galaxy series, misc. (MTP mode)             | 1         | 1.06%   |
| Ricoh Visual Communication Camera VGP-VCC3 [R5U870] | 1         | 1.06%   |
| Ricoh Pavilion Webcam [R5U870]                      | 1         | 1.06%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 1.06%   |
| Realtek USB Camera                                  | 1         | 1.06%   |
| Realtek HP Webcam                                   | 1         | 1.06%   |
| Quanta USB2.0 HD UVC WebCam                         | 1         | 1.06%   |
| Quanta HP Wide Vision HD Camera                     | 1         | 1.06%   |
| Quanta HP TrueVision HD Camera                      | 1         | 1.06%   |
| Quanta HD User Facing                               | 1         | 1.06%   |
| Olympus Optical PCM RECORDER                        | 1         | 1.06%   |
| Microdia Webcam                                     | 1         | 1.06%   |
| Microdia Sonix 1.3 MP Laptop Integrated Webcam      | 1         | 1.06%   |
| Microdia Integrated Webcam                          | 1         | 1.06%   |
| MacroSilicon MS210x Video Grabber [EasierCAP]       | 1         | 1.06%   |
| Luxvisions Innotech Limited HP HD Camera            | 1         | 1.06%   |
| Logitech Webcam C270                                | 1         | 1.06%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 30%     |
| Synaptics                  | 2         | 20%     |
| STMicroelectronics         | 2         | 20%     |
| AuthenTec                  | 2         | 20%     |
| Shenzhen Goodix Technology | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| STMicroelectronics Fingerprint Reader                                      | 2         | 20%     |
| AuthenTec AES2810                                                          | 2         | 20%     |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 10%     |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 10%     |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 10%     |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 10%     |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 10%     |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 10%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Lenovo      | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 118       | 61.46%  |
| 1     | 43        | 22.4%   |
| 2     | 22        | 11.46%  |
| 4     | 5         | 2.6%    |
| 3     | 3         | 1.56%   |
| 7     | 1         | 0.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 37        | 32.17%  |
| Communication controller | 15        | 13.04%  |
| Net/wireless             | 12        | 10.43%  |
| Fingerprint reader       | 9         | 7.83%   |
| Modem                    | 7         | 6.09%   |
| Camera                   | 6         | 5.22%   |
| Bluetooth                | 5         | 4.35%   |
| Multimedia controller    | 4         | 3.48%   |
| Card reader              | 4         | 3.48%   |
| Network                  | 3         | 2.61%   |
| Unassigned class         | 2         | 1.74%   |
| Storage/ata              | 2         | 1.74%   |
| Sound                    | 2         | 1.74%   |
| Net/ethernet             | 2         | 1.74%   |
| Chipcard                 | 2         | 1.74%   |
| Unclassified device      | 1         | 0.87%   |
| Storage                  | 1         | 0.87%   |
| Flash memory             | 1         | 0.87%   |


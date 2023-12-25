Linux in Costa Rica - Tested Hardware & Statistics
--------------------------------------------------

A project to collect tested hardware configurations for Linux in Costa Rica.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Costa_Rica/Desktop/README.md) and [notebooks](/Location/Costa_Rica/Notebook/README.md).

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

Total: 418

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T420 4236DA4       | Notebook    | [1188c1619d](https://linux-hardware.org/?probe=1188c1619d) | Dec 20, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [bb58136a7c](https://linux-hardware.org/?probe=bb58136a7c) | Dec 18, 2023 |
| Dell          | G15 5515                    | Notebook    | [259739c8b5](https://linux-hardware.org/?probe=259739c8b5) | Dec 14, 2023 |
| Lenovo        | IdeaPad D330-10IGL 82H0     | Tablet      | [a73b0c39f2](https://linux-hardware.org/?probe=a73b0c39f2) | Dec 12, 2023 |
| Lenovo        | IdeaPad D330-10IGL 82H0     | Tablet      | [b569f37962](https://linux-hardware.org/?probe=b569f37962) | Dec 11, 2023 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [6b350f2aaf](https://linux-hardware.org/?probe=6b350f2aaf) | Dec 11, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [c723bcc62a](https://linux-hardware.org/?probe=c723bcc62a) | Dec 07, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [7d8d9279cd](https://linux-hardware.org/?probe=7d8d9279cd) | Nov 21, 2023 |
| Apple         | MacBookPro5,4               | Notebook    | [7045b84f52](https://linux-hardware.org/?probe=7045b84f52) | Nov 21, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [af8edff0b6](https://linux-hardware.org/?probe=af8edff0b6) | Nov 15, 2023 |
| Gigabyte      | B150-HD3-CF                 | Desktop     | [d7e062f534](https://linux-hardware.org/?probe=d7e062f534) | Nov 15, 2023 |
| Toshiba       | Satellite L845              | Notebook    | [4dc7e8931e](https://linux-hardware.org/?probe=4dc7e8931e) | Nov 05, 2023 |
| ZOTAC         | NM10                        | Desktop     | [5a951d80a6](https://linux-hardware.org/?probe=5a951d80a6) | Oct 31, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [9266111091](https://linux-hardware.org/?probe=9266111091) | Oct 27, 2023 |
| HP            | 3047h                       | Desktop     | [cdd7fbc37f](https://linux-hardware.org/?probe=cdd7fbc37f) | Oct 25, 2023 |
| HP            | 3047h                       | Desktop     | [4235f287b2](https://linux-hardware.org/?probe=4235f287b2) | Oct 25, 2023 |
| Dell          | Inspiron 3443               | Notebook    | [bbe3093cb4](https://linux-hardware.org/?probe=bbe3093cb4) | Oct 22, 2023 |
| ZOTAC         | NM10                        | Desktop     | [2e0ab67bec](https://linux-hardware.org/?probe=2e0ab67bec) | Oct 21, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [d8335b95a8](https://linux-hardware.org/?probe=d8335b95a8) | Oct 19, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [a8028e0998](https://linux-hardware.org/?probe=a8028e0998) | Oct 11, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [d1d30ae371](https://linux-hardware.org/?probe=d1d30ae371) | Oct 10, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [ae4ee327c0](https://linux-hardware.org/?probe=ae4ee327c0) | Oct 06, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [14ac97b405](https://linux-hardware.org/?probe=14ac97b405) | Oct 05, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [92e214fb3e](https://linux-hardware.org/?probe=92e214fb3e) | Oct 04, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [a814d9fa4b](https://linux-hardware.org/?probe=a814d9fa4b) | Sep 25, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [ef531e70d1](https://linux-hardware.org/?probe=ef531e70d1) | Sep 22, 2023 |
| HP            | Mini 110-1000               | Notebook    | [dda4d7a910](https://linux-hardware.org/?probe=dda4d7a910) | Sep 18, 2023 |
| HP            | Mini 110-1000               | Notebook    | [ee2d142228](https://linux-hardware.org/?probe=ee2d142228) | Sep 18, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [c7b5f9224a](https://linux-hardware.org/?probe=c7b5f9224a) | Sep 17, 2023 |
| ASUSTek       | X541UV                      | Notebook    | [a66fcc9edb](https://linux-hardware.org/?probe=a66fcc9edb) | Sep 11, 2023 |
| Sony          | SVE14123CLW                 | Notebook    | [2fffba7739](https://linux-hardware.org/?probe=2fffba7739) | Sep 08, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [3b740d65f2](https://linux-hardware.org/?probe=3b740d65f2) | Sep 04, 2023 |
| Dell          | 0RW203 A00                  | Desktop     | [0c76c5a1a7](https://linux-hardware.org/?probe=0c76c5a1a7) | Aug 30, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [40693c0171](https://linux-hardware.org/?probe=40693c0171) | Aug 29, 2023 |
| Lenovo        | B590 20208                  | Notebook    | [65bf0970da](https://linux-hardware.org/?probe=65bf0970da) | Aug 27, 2023 |
| Dell          | Latitude E6420              | Notebook    | [ae48a8c618](https://linux-hardware.org/?probe=ae48a8c618) | Aug 26, 2023 |
| MSI           | Katana 15 B13VGK            | Notebook    | [e92e058288](https://linux-hardware.org/?probe=e92e058288) | Aug 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b65293c5a8](https://linux-hardware.org/?probe=b65293c5a8) | Aug 17, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [d25700c10e](https://linux-hardware.org/?probe=d25700c10e) | Aug 16, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [9c2b1b1da7](https://linux-hardware.org/?probe=9c2b1b1da7) | Aug 06, 2023 |
| Samsung       | 930X2K/931X2K               | Notebook    | [5985901bef](https://linux-hardware.org/?probe=5985901bef) | Aug 03, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [a0394c8f0b](https://linux-hardware.org/?probe=a0394c8f0b) | Jul 30, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | Notebook    | [ec5a50d1d8](https://linux-hardware.org/?probe=ec5a50d1d8) | Jul 29, 2023 |
| ASUSTek       | Q551LN                      | Notebook    | [ad2abcddcf](https://linux-hardware.org/?probe=ad2abcddcf) | Jul 27, 2023 |
| Foxconn       | nT-iBT18/nT-iBT19/nT-iBT... | Desktop     | [23633cafce](https://linux-hardware.org/?probe=23633cafce) | Jul 27, 2023 |
| Lenovo        | ThinkPad E580 20KS003LLM    | Notebook    | [9bc92a8ef2](https://linux-hardware.org/?probe=9bc92a8ef2) | Jul 26, 2023 |
| ASUSTek       | A55BM-E                     | Desktop     | [4e99483733](https://linux-hardware.org/?probe=4e99483733) | Jul 13, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [cb309977d0](https://linux-hardware.org/?probe=cb309977d0) | Jul 08, 2023 |
| Samsung       | 930X2K/931X2K               | Notebook    | [fd0d25039d](https://linux-hardware.org/?probe=fd0d25039d) | Jul 07, 2023 |
| Samsung       | 930X2K/931X2K               | Notebook    | [294e57d915](https://linux-hardware.org/?probe=294e57d915) | Jul 07, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [a98b1d131d](https://linux-hardware.org/?probe=a98b1d131d) | Jul 06, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [eb913300f2](https://linux-hardware.org/?probe=eb913300f2) | Jul 06, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [607d40a328](https://linux-hardware.org/?probe=607d40a328) | Jul 04, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [7dffb9055b](https://linux-hardware.org/?probe=7dffb9055b) | Jun 29, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [638d6b4ef3](https://linux-hardware.org/?probe=638d6b4ef3) | Jun 27, 2023 |
| Dell          | Inspiron 5593               | Notebook    | [06f1256f88](https://linux-hardware.org/?probe=06f1256f88) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [3e3987b43f](https://linux-hardware.org/?probe=3e3987b43f) | Jun 20, 2023 |
| HP            | ENVY 15                     | Notebook    | [101fb8810b](https://linux-hardware.org/?probe=101fb8810b) | Jun 19, 2023 |
| HP            | Notebook                    | Notebook    | [42558904aa](https://linux-hardware.org/?probe=42558904aa) | Jun 10, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [cbf7ed91a7](https://linux-hardware.org/?probe=cbf7ed91a7) | Jun 08, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [1aa286ccff](https://linux-hardware.org/?probe=1aa286ccff) | Jun 03, 2023 |
| HP            | Notebook                    | Notebook    | [c246477ea2](https://linux-hardware.org/?probe=c246477ea2) | May 31, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [360e8fd5e5](https://linux-hardware.org/?probe=360e8fd5e5) | May 30, 2023 |
| HP            | Notebook                    | Notebook    | [10ab4427b5](https://linux-hardware.org/?probe=10ab4427b5) | May 29, 2023 |
| Lenovo        | ThinkPad E490 20N8A01YGI    | Notebook    | [c46cf56eb1](https://linux-hardware.org/?probe=c46cf56eb1) | May 27, 2023 |
| Dell          | 0WMJ54 A00                  | Desktop     | [5875771b0c](https://linux-hardware.org/?probe=5875771b0c) | May 24, 2023 |
| Dell          | 0WMJ54 A00                  | Desktop     | [50283ef123](https://linux-hardware.org/?probe=50283ef123) | May 24, 2023 |
| ZOTAC         | NM10                        | Desktop     | [0be7755cf9](https://linux-hardware.org/?probe=0be7755cf9) | May 19, 2023 |
| Samsung       | 930X2K/931X2K               | Notebook    | [14eae60f4f](https://linux-hardware.org/?probe=14eae60f4f) | May 13, 2023 |
| Samsung       | 930X2K/931X2K               | Notebook    | [7ac717a41d](https://linux-hardware.org/?probe=7ac717a41d) | May 13, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [ba104d9250](https://linux-hardware.org/?probe=ba104d9250) | May 10, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [b06388c1f4](https://linux-hardware.org/?probe=b06388c1f4) | May 09, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [68b1e1e6cb](https://linux-hardware.org/?probe=68b1e1e6cb) | May 05, 2023 |
| Samsung       | 930X2K/931X2K               | Notebook    | [bc4f78f7e7](https://linux-hardware.org/?probe=bc4f78f7e7) | Apr 29, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [36ec2bb4c2](https://linux-hardware.org/?probe=36ec2bb4c2) | Apr 22, 2023 |
| HP            | ProBook 6570b               | Notebook    | [2b01f67020](https://linux-hardware.org/?probe=2b01f67020) | Apr 14, 2023 |
| Samsung       | 930X2K/931X2K               | Notebook    | [126c7a430c](https://linux-hardware.org/?probe=126c7a430c) | Apr 13, 2023 |
| Samsung       | 930X2K/931X2K               | Notebook    | [80d44eb98b](https://linux-hardware.org/?probe=80d44eb98b) | Apr 12, 2023 |
| HP            | EliteBook 8560p             | Notebook    | [2ecc0fe5bc](https://linux-hardware.org/?probe=2ecc0fe5bc) | Apr 07, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [8b4666305d](https://linux-hardware.org/?probe=8b4666305d) | Apr 07, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [33d6b0fbc8](https://linux-hardware.org/?probe=33d6b0fbc8) | Apr 05, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [5f29b020ab](https://linux-hardware.org/?probe=5f29b020ab) | Apr 04, 2023 |
| Google        | Snappy                      | Notebook    | [16dda325bf](https://linux-hardware.org/?probe=16dda325bf) | Apr 02, 2023 |
| ASRock        | 970 Extreme3                | Desktop     | [906f9d6d04](https://linux-hardware.org/?probe=906f9d6d04) | Mar 30, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [b72701d99c](https://linux-hardware.org/?probe=b72701d99c) | Mar 29, 2023 |
| Acer          | Aspire E1-431               | Notebook    | [f56a2c21cf](https://linux-hardware.org/?probe=f56a2c21cf) | Mar 26, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [457915fe10](https://linux-hardware.org/?probe=457915fe10) | Mar 23, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [d8fee2b6b1](https://linux-hardware.org/?probe=d8fee2b6b1) | Mar 08, 2023 |
| ASUSTek       | PRO A320M-R WI-FI           | Desktop     | [2b64b38f7a](https://linux-hardware.org/?probe=2b64b38f7a) | Mar 01, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [3479df4ab9](https://linux-hardware.org/?probe=3479df4ab9) | Feb 26, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [b02e34a7f9](https://linux-hardware.org/?probe=b02e34a7f9) | Feb 25, 2023 |
| MSI           | 970A GAMING PRO CARBON      | Desktop     | [0649eea8a9](https://linux-hardware.org/?probe=0649eea8a9) | Feb 25, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [d6fea43eb5](https://linux-hardware.org/?probe=d6fea43eb5) | Feb 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [6707aef886](https://linux-hardware.org/?probe=6707aef886) | Feb 25, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [21335c1268](https://linux-hardware.org/?probe=21335c1268) | Feb 23, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [1942c9f528](https://linux-hardware.org/?probe=1942c9f528) | Feb 11, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [dcecd700f9](https://linux-hardware.org/?probe=dcecd700f9) | Feb 10, 2023 |
| Raspberry ... | Raspberry Pi Model B Rev... | Soc         | [4995c8c687](https://linux-hardware.org/?probe=4995c8c687) | Feb 06, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [ae644e258a](https://linux-hardware.org/?probe=ae644e258a) | Jan 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [cc2d26e52e](https://linux-hardware.org/?probe=cc2d26e52e) | Jan 22, 2023 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [8761a4096a](https://linux-hardware.org/?probe=8761a4096a) | Jan 22, 2023 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [7099ccff2f](https://linux-hardware.org/?probe=7099ccff2f) | Jan 22, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [394be1956b](https://linux-hardware.org/?probe=394be1956b) | Jan 22, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [f33868aba0](https://linux-hardware.org/?probe=f33868aba0) | Jan 15, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [927415e3d5](https://linux-hardware.org/?probe=927415e3d5) | Jan 07, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [46ea5b81b7](https://linux-hardware.org/?probe=46ea5b81b7) | Jan 07, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [f5ff2f8568](https://linux-hardware.org/?probe=f5ff2f8568) | Jan 06, 2023 |
| MACHINIST     | X79 V2.82H                  | Desktop     | [e6028c8640](https://linux-hardware.org/?probe=e6028c8640) | Jan 04, 2023 |
| Jumper        | EZpad                       | Tablet      | [cfa761d534](https://linux-hardware.org/?probe=cfa761d534) | Jan 03, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [b1a7532cf1](https://linux-hardware.org/?probe=b1a7532cf1) | Dec 23, 2022 |
| ZOTAC         | NM10                        | Desktop     | [98b6981431](https://linux-hardware.org/?probe=98b6981431) | Dec 21, 2022 |
| Gigabyte      | B150-HD3-CF                 | Desktop     | [173dde2177](https://linux-hardware.org/?probe=173dde2177) | Dec 14, 2022 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [485240a680](https://linux-hardware.org/?probe=485240a680) | Dec 13, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [75a9a0c076](https://linux-hardware.org/?probe=75a9a0c076) | Dec 12, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [15695e4deb](https://linux-hardware.org/?probe=15695e4deb) | Dec 11, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [71137ab051](https://linux-hardware.org/?probe=71137ab051) | Dec 08, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [651f6f4d18](https://linux-hardware.org/?probe=651f6f4d18) | Dec 07, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [de8272cf2e](https://linux-hardware.org/?probe=de8272cf2e) | Dec 05, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [0ade3eaab1](https://linux-hardware.org/?probe=0ade3eaab1) | Dec 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [a3746e8985](https://linux-hardware.org/?probe=a3746e8985) | Dec 01, 2022 |
| Gigabyte      | H410M H                     | Desktop     | [09129dad50](https://linux-hardware.org/?probe=09129dad50) | Nov 28, 2022 |
| Gigabyte      | H410M H                     | Desktop     | [88ca303518](https://linux-hardware.org/?probe=88ca303518) | Nov 28, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [f278eb7e59](https://linux-hardware.org/?probe=f278eb7e59) | Nov 27, 2022 |
| Toshiba       | Satellite S55-A             | Notebook    | [c188e01f20](https://linux-hardware.org/?probe=c188e01f20) | Nov 20, 2022 |
| HP            | Unknown                     | Notebook    | [9b1181bc4b](https://linux-hardware.org/?probe=9b1181bc4b) | Nov 19, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [8a52f497b0](https://linux-hardware.org/?probe=8a52f497b0) | Nov 19, 2022 |
| Toshiba       | Satellite S55-A             | Notebook    | [d5e9f0d98a](https://linux-hardware.org/?probe=d5e9f0d98a) | Nov 19, 2022 |
| ASRock        | B660M Steel Legend          | Desktop     | [708d98bf92](https://linux-hardware.org/?probe=708d98bf92) | Nov 06, 2022 |
| ASRock        | B660M Steel Legend          | Desktop     | [2fce0b247c](https://linux-hardware.org/?probe=2fce0b247c) | Nov 06, 2022 |
| Lenovo        | ThinkPad P16 Gen 1 21D7S... | Notebook    | [fc4b865872](https://linux-hardware.org/?probe=fc4b865872) | Nov 04, 2022 |
| Lenovo        | ThinkPad T60 1952F75        | Notebook    | [a6f536ca3d](https://linux-hardware.org/?probe=a6f536ca3d) | Oct 25, 2022 |
| Lenovo        | ThinkPad T60 1952F75        | Notebook    | [813bd112f8](https://linux-hardware.org/?probe=813bd112f8) | Oct 25, 2022 |
| MACHINIST     | X79 V2.82H                  | Desktop     | [5d99fbefc1](https://linux-hardware.org/?probe=5d99fbefc1) | Oct 17, 2022 |
| MSI           | GF65 Thin 10SDR             | Notebook    | [1c2a3b90e2](https://linux-hardware.org/?probe=1c2a3b90e2) | Oct 04, 2022 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [5d789a1783](https://linux-hardware.org/?probe=5d789a1783) | Sep 28, 2022 |
| Dell          | Inspiron 3493               | Notebook    | [b1f8d22e3e](https://linux-hardware.org/?probe=b1f8d22e3e) | Sep 25, 2022 |
| Intel         | DG41WV AAE90316-103         | Desktop     | [425dd57672](https://linux-hardware.org/?probe=425dd57672) | Sep 24, 2022 |
| Dell          | 0HD5W2 A01                  | Desktop     | [1bb8ad599d](https://linux-hardware.org/?probe=1bb8ad599d) | Sep 11, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | Convertible | [b49d726ab0](https://linux-hardware.org/?probe=b49d726ab0) | Sep 03, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | Convertible | [ee80be714e](https://linux-hardware.org/?probe=ee80be714e) | Sep 03, 2022 |
| ASRock        | N68-S UCC                   | Desktop     | [1d38f1f08e](https://linux-hardware.org/?probe=1d38f1f08e) | Aug 30, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | Notebook    | [9b23c4b82c](https://linux-hardware.org/?probe=9b23c4b82c) | Aug 30, 2022 |
| Dell          | G3 3579                     | Notebook    | [a3fc82fe9a](https://linux-hardware.org/?probe=a3fc82fe9a) | Aug 30, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [68d1385b7e](https://linux-hardware.org/?probe=68d1385b7e) | Aug 28, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [99faef3f00](https://linux-hardware.org/?probe=99faef3f00) | Aug 20, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [fb77adfb99](https://linux-hardware.org/?probe=fb77adfb99) | Aug 16, 2022 |
| Toshiba       | Satellite L655              | Notebook    | [5e3e45b5d5](https://linux-hardware.org/?probe=5e3e45b5d5) | Aug 08, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [992b4f4910](https://linux-hardware.org/?probe=992b4f4910) | Aug 06, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [b932802b52](https://linux-hardware.org/?probe=b932802b52) | Aug 04, 2022 |
| ASUSTek       | GL552VW                     | Notebook    | [cd24503d2f](https://linux-hardware.org/?probe=cd24503d2f) | Aug 02, 2022 |
| Acer          | Aspire E5-576               | Notebook    | [a31ceb9a36](https://linux-hardware.org/?probe=a31ceb9a36) | Jul 31, 2022 |
| MACHINIST     | X79 V2.82H                  | Desktop     | [da4a098248](https://linux-hardware.org/?probe=da4a098248) | Jul 22, 2022 |
| MACHINIST     | X79 V2.82H                  | Desktop     | [0e06f3fdf5](https://linux-hardware.org/?probe=0e06f3fdf5) | Jul 22, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [f4efe63bf8](https://linux-hardware.org/?probe=f4efe63bf8) | Jul 13, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [a06c4e1f6b](https://linux-hardware.org/?probe=a06c4e1f6b) | Jul 13, 2022 |
| Deffad        | Unknown                     | Notebook    | [af38c7120e](https://linux-hardware.org/?probe=af38c7120e) | Jul 04, 2022 |
| Dell          | Inspiron 3520               | Notebook    | [b865370f11](https://linux-hardware.org/?probe=b865370f11) | Jun 28, 2022 |
| Lenovo        | ThinkPad P50 20EN001PUS     | Notebook    | [52ef9383a4](https://linux-hardware.org/?probe=52ef9383a4) | Jun 09, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [46afe6a354](https://linux-hardware.org/?probe=46afe6a354) | Jun 02, 2022 |
| Lenovo        | ThinkPad T440s 20ARS29U0... | Notebook    | [50de8ad2e9](https://linux-hardware.org/?probe=50de8ad2e9) | Jun 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [b64c215325](https://linux-hardware.org/?probe=b64c215325) | May 30, 2022 |
| Dell          | Latitude 7400               | Notebook    | [caf85903ad](https://linux-hardware.org/?probe=caf85903ad) | May 19, 2022 |
| Dell          | Inspiron 5565               | Notebook    | [d5a8629a31](https://linux-hardware.org/?probe=d5a8629a31) | May 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [1aba67a1ac](https://linux-hardware.org/?probe=1aba67a1ac) | May 15, 2022 |
| Lenovo        | ThinkPad L420 7829AA4       | Notebook    | [9c1bbe8cf2](https://linux-hardware.org/?probe=9c1bbe8cf2) | May 14, 2022 |
| HP            | 0AECh D                     | Desktop     | [68adfe0740](https://linux-hardware.org/?probe=68adfe0740) | May 12, 2022 |
| HP            | 83EE                        | Desktop     | [55171637ca](https://linux-hardware.org/?probe=55171637ca) | Apr 29, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6ad1b34a48](https://linux-hardware.org/?probe=6ad1b34a48) | Apr 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [637af2dcc6](https://linux-hardware.org/?probe=637af2dcc6) | Apr 29, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [1f14473753](https://linux-hardware.org/?probe=1f14473753) | Apr 19, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [f74cae630d](https://linux-hardware.org/?probe=f74cae630d) | Apr 16, 2022 |
| ZOTAC         | NM10                        | Desktop     | [b2983fdd9d](https://linux-hardware.org/?probe=b2983fdd9d) | Apr 15, 2022 |
| ASUSTek       | STRIX Z270G GAMING          | Desktop     | [e04e7a6bc9](https://linux-hardware.org/?probe=e04e7a6bc9) | Apr 13, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [a1130d8070](https://linux-hardware.org/?probe=a1130d8070) | Apr 13, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [8e31fed1d4](https://linux-hardware.org/?probe=8e31fed1d4) | Apr 07, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [ff072aa20b](https://linux-hardware.org/?probe=ff072aa20b) | Apr 07, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [9cd507e648](https://linux-hardware.org/?probe=9cd507e648) | Apr 07, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [e5b52520a8](https://linux-hardware.org/?probe=e5b52520a8) | Apr 07, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [6a631fae48](https://linux-hardware.org/?probe=6a631fae48) | Mar 22, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [e1386a38c7](https://linux-hardware.org/?probe=e1386a38c7) | Mar 20, 2022 |
| Dell          | Latitude E5500              | Notebook    | [13be4a0a1b](https://linux-hardware.org/?probe=13be4a0a1b) | Mar 16, 2022 |
| Dell          | Latitude E5500              | Notebook    | [d5f8fd7890](https://linux-hardware.org/?probe=d5f8fd7890) | Mar 16, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [a8531f3837](https://linux-hardware.org/?probe=a8531f3837) | Mar 13, 2022 |
| Dell          | Latitude D630               | Notebook    | [b7b428082a](https://linux-hardware.org/?probe=b7b428082a) | Mar 05, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [8807d99cb4](https://linux-hardware.org/?probe=8807d99cb4) | Mar 01, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [c0adf77f3f](https://linux-hardware.org/?probe=c0adf77f3f) | Feb 26, 2022 |
| Sony          | SVD13215PLB                 | Notebook    | [82c4287f85](https://linux-hardware.org/?probe=82c4287f85) | Feb 23, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [b355ea1ff3](https://linux-hardware.org/?probe=b355ea1ff3) | Feb 20, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [8468cd0da9](https://linux-hardware.org/?probe=8468cd0da9) | Feb 19, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [80e2f3c47e](https://linux-hardware.org/?probe=80e2f3c47e) | Feb 19, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [b99a5f9b59](https://linux-hardware.org/?probe=b99a5f9b59) | Feb 14, 2022 |
| Dell          | 0RW203 A00                  | Desktop     | [21ac06a9f6](https://linux-hardware.org/?probe=21ac06a9f6) | Feb 12, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [ce15566bc3](https://linux-hardware.org/?probe=ce15566bc3) | Feb 12, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [8fc6552bc9](https://linux-hardware.org/?probe=8fc6552bc9) | Feb 08, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [dbc7cbcfe1](https://linux-hardware.org/?probe=dbc7cbcfe1) | Feb 07, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [ac53ba49ef](https://linux-hardware.org/?probe=ac53ba49ef) | Jan 28, 2022 |
| Toshiba       | Satellite L45-B             | Notebook    | [5e026ae9b0](https://linux-hardware.org/?probe=5e026ae9b0) | Jan 14, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [3f953ad7f3](https://linux-hardware.org/?probe=3f953ad7f3) | Jan 14, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [eecedd12b2](https://linux-hardware.org/?probe=eecedd12b2) | Jan 14, 2022 |
| Samsung       | 930QAA                      | Convertible | [56758d8bfb](https://linux-hardware.org/?probe=56758d8bfb) | Jan 10, 2022 |
| Samsung       | 930QAA                      | Convertible | [206f508be5](https://linux-hardware.org/?probe=206f508be5) | Jan 10, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [6837cca618](https://linux-hardware.org/?probe=6837cca618) | Jan 02, 2022 |
| Gigabyte      | Z690 UD AX DDR4             | Desktop     | [9158036ed3](https://linux-hardware.org/?probe=9158036ed3) | Dec 30, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [b482ef13ea](https://linux-hardware.org/?probe=b482ef13ea) | Dec 26, 2021 |
| ASUSTek       | H81M-C                      | Desktop     | [0b0241baf7](https://linux-hardware.org/?probe=0b0241baf7) | Dec 08, 2021 |
| MSI           | H55M-E33                    | Desktop     | [f0786be9c3](https://linux-hardware.org/?probe=f0786be9c3) | Nov 14, 2021 |
| HP            | 18E4                        | Desktop     | [692c64d7c1](https://linux-hardware.org/?probe=692c64d7c1) | Nov 08, 2021 |
| HP            | 18E4                        | Desktop     | [499e85c152](https://linux-hardware.org/?probe=499e85c152) | Nov 07, 2021 |
| MSI           | H55M-E33                    | Desktop     | [3d8c474259](https://linux-hardware.org/?probe=3d8c474259) | Nov 06, 2021 |
| Dell          | Latitude 5490               | Notebook    | [c5c1f555f1](https://linux-hardware.org/?probe=c5c1f555f1) | Nov 03, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [b6ac4539d1](https://linux-hardware.org/?probe=b6ac4539d1) | Oct 28, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [8264430178](https://linux-hardware.org/?probe=8264430178) | Oct 28, 2021 |
| Dell          | Inspiron 3595               | Notebook    | [1df662506b](https://linux-hardware.org/?probe=1df662506b) | Oct 27, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [e7e870c6cc](https://linux-hardware.org/?probe=e7e870c6cc) | Oct 22, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [a271c08df2](https://linux-hardware.org/?probe=a271c08df2) | Oct 21, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [5bb3c9bc8b](https://linux-hardware.org/?probe=5bb3c9bc8b) | Oct 19, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [bfadd59ae5](https://linux-hardware.org/?probe=bfadd59ae5) | Oct 18, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [2a9e8d32e2](https://linux-hardware.org/?probe=2a9e8d32e2) | Oct 15, 2021 |
| Acer          | Aspire 5750                 | Notebook    | [ff12aa7481](https://linux-hardware.org/?probe=ff12aa7481) | Oct 15, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [f0a9d13afb](https://linux-hardware.org/?probe=f0a9d13afb) | Oct 14, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [2a83508f22](https://linux-hardware.org/?probe=2a83508f22) | Oct 10, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [1dbff2c4f9](https://linux-hardware.org/?probe=1dbff2c4f9) | Oct 09, 2021 |
| TPV-INVENT... | 2AF2 A01                    | Desktop     | [23e967d7f5](https://linux-hardware.org/?probe=23e967d7f5) | Oct 06, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [da71bb02c1](https://linux-hardware.org/?probe=da71bb02c1) | Oct 03, 2021 |
| Dell          | Latitude D620               | Notebook    | [1dc8e001f5](https://linux-hardware.org/?probe=1dc8e001f5) | Sep 28, 2021 |
| ZOTAC         | NM10                        | Desktop     | [94313faa27](https://linux-hardware.org/?probe=94313faa27) | Sep 27, 2021 |
| Acer          | Aspire Z1-601               | All in one  | [29a6b45091](https://linux-hardware.org/?probe=29a6b45091) | Sep 26, 2021 |
| Acer          | Aspire Z1-601               | All in one  | [5ed9f083e1](https://linux-hardware.org/?probe=5ed9f083e1) | Sep 26, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [3a8451c3d2](https://linux-hardware.org/?probe=3a8451c3d2) | Sep 25, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [0a7625c3ec](https://linux-hardware.org/?probe=0a7625c3ec) | Sep 25, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [2c4c85f574](https://linux-hardware.org/?probe=2c4c85f574) | Sep 20, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [dcf03222dc](https://linux-hardware.org/?probe=dcf03222dc) | Sep 12, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [00b3e62e2e](https://linux-hardware.org/?probe=00b3e62e2e) | Sep 10, 2021 |
| MSI           | GF75 Thin 9SD               | Notebook    | [e70d1b33e1](https://linux-hardware.org/?probe=e70d1b33e1) | Sep 09, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [a7cc7fb98c](https://linux-hardware.org/?probe=a7cc7fb98c) | Aug 27, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [6972dfc45b](https://linux-hardware.org/?probe=6972dfc45b) | Aug 25, 2021 |
| ZOTAC         | NM10                        | Desktop     | [f735937235](https://linux-hardware.org/?probe=f735937235) | Aug 22, 2021 |
| MSI           | MPG Z390I GAMING EDGE AC    | Desktop     | [391c21db23](https://linux-hardware.org/?probe=391c21db23) | Aug 16, 2021 |
| Dell          | 0PU052                      | Desktop     | [25ce6d5bbd](https://linux-hardware.org/?probe=25ce6d5bbd) | Aug 05, 2021 |
| Olivetti      | CL133A                      | Notebook    | [59d8296ec4](https://linux-hardware.org/?probe=59d8296ec4) | Jul 31, 2021 |
| HP            | Pavilion g4                 | Notebook    | [3f01790d4e](https://linux-hardware.org/?probe=3f01790d4e) | Jul 21, 2021 |
| AZW           | GT-R                        | Notebook    | [115230aa47](https://linux-hardware.org/?probe=115230aa47) | Jul 19, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [a5a9cfcd44](https://linux-hardware.org/?probe=a5a9cfcd44) | Jul 18, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [689b83e978](https://linux-hardware.org/?probe=689b83e978) | Jul 18, 2021 |
| Olivetti      | CL133A                      | Notebook    | [a73133e4f3](https://linux-hardware.org/?probe=a73133e4f3) | Jul 15, 2021 |
| ASUSTek       | U46E                        | Notebook    | [720dec33c4](https://linux-hardware.org/?probe=720dec33c4) | Jul 14, 2021 |
| HP            | ProBook 6460b               | Notebook    | [b39eb9b256](https://linux-hardware.org/?probe=b39eb9b256) | Jul 13, 2021 |
| Dell          | G3 3590                     | Notebook    | [3781e31377](https://linux-hardware.org/?probe=3781e31377) | Jul 12, 2021 |
| Olivetti      | CL133A                      | Notebook    | [ba8eb5f003](https://linux-hardware.org/?probe=ba8eb5f003) | Jul 10, 2021 |
| Olivetti      | CL133A                      | Notebook    | [117e8fa0b4](https://linux-hardware.org/?probe=117e8fa0b4) | Jul 06, 2021 |
| Dell          | 05WNJ2 A02                  | Server      | [9e01fd5e8c](https://linux-hardware.org/?probe=9e01fd5e8c) | Jun 20, 2021 |
| Dell          | 05WNJ2 A02                  | Server      | [e937e8ba7e](https://linux-hardware.org/?probe=e937e8ba7e) | Jun 20, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [ab19b80507](https://linux-hardware.org/?probe=ab19b80507) | Jun 09, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [b05fbab283](https://linux-hardware.org/?probe=b05fbab283) | Jun 06, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [9908ba82e9](https://linux-hardware.org/?probe=9908ba82e9) | May 31, 2021 |
| Dell          | 05WNJ2 A02                  | Server      | [2d1d9030e8](https://linux-hardware.org/?probe=2d1d9030e8) | May 31, 2021 |
| HP            | Pavilion dv6000 (RP297UA... | Notebook    | [5f6d9f025a](https://linux-hardware.org/?probe=5f6d9f025a) | May 29, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [ebffa34fe2](https://linux-hardware.org/?probe=ebffa34fe2) | May 28, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3e92571a0c](https://linux-hardware.org/?probe=3e92571a0c) | May 26, 2021 |
| Toshiba       | Satellite C845              | Notebook    | [e3b90e238b](https://linux-hardware.org/?probe=e3b90e238b) | May 24, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [6f3c2aa3be](https://linux-hardware.org/?probe=6f3c2aa3be) | May 24, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [8ccda2ce59](https://linux-hardware.org/?probe=8ccda2ce59) | May 24, 2021 |
| Toshiba       | Satellite C845              | Notebook    | [4d346e2691](https://linux-hardware.org/?probe=4d346e2691) | May 24, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [5e2e76f838](https://linux-hardware.org/?probe=5e2e76f838) | May 20, 2021 |
| Acer          | Aspire A515-43              | Notebook    | [0a87ab06c5](https://linux-hardware.org/?probe=0a87ab06c5) | May 19, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [4a32129550](https://linux-hardware.org/?probe=4a32129550) | May 15, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [93286a0d38](https://linux-hardware.org/?probe=93286a0d38) | May 15, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [796f490bbb](https://linux-hardware.org/?probe=796f490bbb) | May 15, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [1da876ea0b](https://linux-hardware.org/?probe=1da876ea0b) | May 06, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [0216a041d2](https://linux-hardware.org/?probe=0216a041d2) | May 05, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [b91d32b11a](https://linux-hardware.org/?probe=b91d32b11a) | May 03, 2021 |
| Pegatron      | 2AE4                        | Desktop     | [604b735ad8](https://linux-hardware.org/?probe=604b735ad8) | May 02, 2021 |
| Acer          | Aspire A515-43              | Notebook    | [3c87a86111](https://linux-hardware.org/?probe=3c87a86111) | May 02, 2021 |
| HP            | Pavilion dv6                | Notebook    | [a181ae8691](https://linux-hardware.org/?probe=a181ae8691) | Apr 30, 2021 |
| HP            | Pavilion dv6                | Notebook    | [d363966e4c](https://linux-hardware.org/?probe=d363966e4c) | Apr 30, 2021 |
| HP            | Pavilion dv6                | Notebook    | [204cd9c44f](https://linux-hardware.org/?probe=204cd9c44f) | Apr 30, 2021 |
| HP            | Pavilion dv6                | Notebook    | [e20fc33e2b](https://linux-hardware.org/?probe=e20fc33e2b) | Apr 29, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | Notebook    | [3cca89aa74](https://linux-hardware.org/?probe=3cca89aa74) | Apr 28, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [fd209ac377](https://linux-hardware.org/?probe=fd209ac377) | Apr 24, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | Notebook    | [38c505f6bd](https://linux-hardware.org/?probe=38c505f6bd) | Apr 23, 2021 |
| Intel         | D33217CK G76541-302         | Desktop     | [1db9d29c38](https://linux-hardware.org/?probe=1db9d29c38) | Apr 19, 2021 |
| Apple         | MacBook2,1                  | Notebook    | [a0590a2529](https://linux-hardware.org/?probe=a0590a2529) | Apr 18, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [5afa66a433](https://linux-hardware.org/?probe=5afa66a433) | Apr 17, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [e990abe7f1](https://linux-hardware.org/?probe=e990abe7f1) | Apr 11, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [41c14db0ef](https://linux-hardware.org/?probe=41c14db0ef) | Apr 11, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [48f003363a](https://linux-hardware.org/?probe=48f003363a) | Apr 09, 2021 |
| Dell          | 096JG8 A01                  | Desktop     | [1cf6d1daea](https://linux-hardware.org/?probe=1cf6d1daea) | Apr 02, 2021 |
| Supermicro    | X9DAi                       | Desktop     | [ff94b1201c](https://linux-hardware.org/?probe=ff94b1201c) | Mar 31, 2021 |
| Unknown       | i845G-W83627HF              | Desktop     | [2ff9864ce6](https://linux-hardware.org/?probe=2ff9864ce6) | Mar 29, 2021 |
| Dell          | G3 3590                     | Notebook    | [3c952dbc96](https://linux-hardware.org/?probe=3c952dbc96) | Mar 26, 2021 |
| Toshiba       | QOSMIO X775                 | Notebook    | [d8f82a3984](https://linux-hardware.org/?probe=d8f82a3984) | Mar 26, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [127ea1feb8](https://linux-hardware.org/?probe=127ea1feb8) | Mar 13, 2021 |
| HP            | Pavilion g4                 | Notebook    | [1e7372e4f2](https://linux-hardware.org/?probe=1e7372e4f2) | Mar 01, 2021 |
| Toshiba       | Satellite C45-A             | Notebook    | [e00317dc4d](https://linux-hardware.org/?probe=e00317dc4d) | Mar 01, 2021 |
| Unknown       | Unknown                     | Notebook    | [941e941403](https://linux-hardware.org/?probe=941e941403) | Feb 27, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [16fca1f86b](https://linux-hardware.org/?probe=16fca1f86b) | Feb 24, 2021 |
| Google        | Celes                       | Notebook    | [b30c090b2b](https://linux-hardware.org/?probe=b30c090b2b) | Feb 22, 2021 |
| Dell          | Inspiron 3558               | Notebook    | [41ba11dbb4](https://linux-hardware.org/?probe=41ba11dbb4) | Feb 18, 2021 |
| Pegatron      | 2AE4                        | Desktop     | [8570b15385](https://linux-hardware.org/?probe=8570b15385) | Feb 14, 2021 |
| ASUSTek       | H110M-K                     | Desktop     | [34bf1da3fe](https://linux-hardware.org/?probe=34bf1da3fe) | Feb 13, 2021 |
| ASRock        | 970 Extreme3                | Desktop     | [48548effcd](https://linux-hardware.org/?probe=48548effcd) | Feb 13, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [660afa073b](https://linux-hardware.org/?probe=660afa073b) | Feb 11, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [840e0e2818](https://linux-hardware.org/?probe=840e0e2818) | Feb 04, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [e10690d1d2](https://linux-hardware.org/?probe=e10690d1d2) | Feb 04, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [e0de5d87e6](https://linux-hardware.org/?probe=e0de5d87e6) | Feb 04, 2021 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [84c932e071](https://linux-hardware.org/?probe=84c932e071) | Feb 02, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [473419d486](https://linux-hardware.org/?probe=473419d486) | Jan 24, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [738e03e488](https://linux-hardware.org/?probe=738e03e488) | Jan 23, 2021 |
| Dell          | Precision M4800             | Notebook    | [f24be700aa](https://linux-hardware.org/?probe=f24be700aa) | Jan 21, 2021 |
| Dell          | Precision M4800             | Notebook    | [316c7dd34b](https://linux-hardware.org/?probe=316c7dd34b) | Jan 21, 2021 |
| HP            | Laptop 14-bp0xx             | Notebook    | [4badbab2db](https://linux-hardware.org/?probe=4badbab2db) | Jan 19, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [1a731e13e0](https://linux-hardware.org/?probe=1a731e13e0) | Jan 18, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [6a0e9eff49](https://linux-hardware.org/?probe=6a0e9eff49) | Jan 16, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [76fe08b67a](https://linux-hardware.org/?probe=76fe08b67a) | Jan 14, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [8d9be2defd](https://linux-hardware.org/?probe=8d9be2defd) | Jan 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [b30b783683](https://linux-hardware.org/?probe=b30b783683) | Jan 12, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [6917b5bc30](https://linux-hardware.org/?probe=6917b5bc30) | Jan 11, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [cfa1367cf6](https://linux-hardware.org/?probe=cfa1367cf6) | Jan 10, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [60a171b505](https://linux-hardware.org/?probe=60a171b505) | Jan 10, 2021 |
| Unknown       | i845G-W83627HF              | Desktop     | [6c9d42b55d](https://linux-hardware.org/?probe=6c9d42b55d) | Jan 08, 2021 |
| Unknown       | i845G-W83627HF              | Desktop     | [9ff8161bec](https://linux-hardware.org/?probe=9ff8161bec) | Jan 08, 2021 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [6706c380ab](https://linux-hardware.org/?probe=6706c380ab) | Dec 21, 2020 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [93308d477a](https://linux-hardware.org/?probe=93308d477a) | Dec 18, 2020 |
| HP            | Laptop 14-bp0xx             | Notebook    | [a481e8e9c0](https://linux-hardware.org/?probe=a481e8e9c0) | Dec 16, 2020 |
| HP            | Laptop 14-bp0xx             | Notebook    | [266b8d7543](https://linux-hardware.org/?probe=266b8d7543) | Dec 16, 2020 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [a305c14111](https://linux-hardware.org/?probe=a305c14111) | Dec 13, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2d9e84acd0](https://linux-hardware.org/?probe=2d9e84acd0) | Dec 13, 2020 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [3c6c9b7bd3](https://linux-hardware.org/?probe=3c6c9b7bd3) | Dec 11, 2020 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [3070faaf5e](https://linux-hardware.org/?probe=3070faaf5e) | Dec 03, 2020 |
| Alienware     | 06G6JW A01                  | Desktop     | [812527d15d](https://linux-hardware.org/?probe=812527d15d) | Dec 02, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [c110de3643](https://linux-hardware.org/?probe=c110de3643) | Oct 31, 2020 |
| Dell          | Latitude 7480               | Notebook    | [2e569dcaed](https://linux-hardware.org/?probe=2e569dcaed) | Oct 22, 2020 |
| Dell          | Latitude 7480               | Notebook    | [1cc0a03f18](https://linux-hardware.org/?probe=1cc0a03f18) | Oct 22, 2020 |
| HP            | 2B54 100                    | All in one  | [161455efd7](https://linux-hardware.org/?probe=161455efd7) | Oct 17, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [9f10520397](https://linux-hardware.org/?probe=9f10520397) | Oct 11, 2020 |
| Dell          | G3 3590                     | Notebook    | [4c2ddd8b88](https://linux-hardware.org/?probe=4c2ddd8b88) | Oct 01, 2020 |
| Toshiba       | Satellite C55-B             | Notebook    | [6acb0908ff](https://linux-hardware.org/?probe=6acb0908ff) | Sep 18, 2020 |
| HP            | Unknown                     | Notebook    | [a446c81ca9](https://linux-hardware.org/?probe=a446c81ca9) | Sep 10, 2020 |
| HP            | 2B54 100                    | All in one  | [8e21d2bb01](https://linux-hardware.org/?probe=8e21d2bb01) | Sep 06, 2020 |
| HP            | EliteBook 8570p             | Notebook    | [48e494142e](https://linux-hardware.org/?probe=48e494142e) | Aug 27, 2020 |
| Toshiba       | Satellite X205              | Notebook    | [b0d5e7d0dd](https://linux-hardware.org/?probe=b0d5e7d0dd) | Aug 26, 2020 |
| Toshiba       | Satellite X205              | Notebook    | [45e52f3631](https://linux-hardware.org/?probe=45e52f3631) | Aug 26, 2020 |
| Dell          | 042P49 A01                  | Desktop     | [36ddd61132](https://linux-hardware.org/?probe=36ddd61132) | Aug 12, 2020 |
| Acer          | Aspire 4739Z                | Notebook    | [44ec59d132](https://linux-hardware.org/?probe=44ec59d132) | Aug 11, 2020 |
| HP            | Pavilion dv2500             | Notebook    | [4bdd603282](https://linux-hardware.org/?probe=4bdd603282) | Aug 06, 2020 |
| HP            | Pavilion dv2500             | Notebook    | [4114f58581](https://linux-hardware.org/?probe=4114f58581) | Aug 06, 2020 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [d8a8eb467a](https://linux-hardware.org/?probe=d8a8eb467a) | Aug 02, 2020 |
| Dell          | Latitude E5440              | Notebook    | [9d31b1e38d](https://linux-hardware.org/?probe=9d31b1e38d) | Jul 29, 2020 |
| Gateway       | FMCP7AM                     | Desktop     | [58e88b2df5](https://linux-hardware.org/?probe=58e88b2df5) | Jul 28, 2020 |
| ABIT          | AW9D-MAX                    | Desktop     | [fca26e4a11](https://linux-hardware.org/?probe=fca26e4a11) | Jul 21, 2020 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [c00d0feee3](https://linux-hardware.org/?probe=c00d0feee3) | Jul 21, 2020 |
| MSI           | 970 GAMING                  | Desktop     | [73c5756fdd](https://linux-hardware.org/?probe=73c5756fdd) | Jul 01, 2020 |
| Dell          | G3 3590                     | Notebook    | [e2fa394ba6](https://linux-hardware.org/?probe=e2fa394ba6) | Jun 28, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [8119688776](https://linux-hardware.org/?probe=8119688776) | Jun 27, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [d2a2900148](https://linux-hardware.org/?probe=d2a2900148) | Jun 20, 2020 |
| ASRock        | B450 Steel Legend           | Desktop     | [7d9ad3146b](https://linux-hardware.org/?probe=7d9ad3146b) | Jun 12, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [4619502a6b](https://linux-hardware.org/?probe=4619502a6b) | May 28, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b9c266ed55](https://linux-hardware.org/?probe=b9c266ed55) | May 20, 2020 |
| HP            | ProBook 455 G4              | Notebook    | [6b6fe8e0c1](https://linux-hardware.org/?probe=6b6fe8e0c1) | May 18, 2020 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [6252910769](https://linux-hardware.org/?probe=6252910769) | May 11, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [8fc4603f6c](https://linux-hardware.org/?probe=8fc4603f6c) | May 10, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [33cd43676f](https://linux-hardware.org/?probe=33cd43676f) | May 09, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [1a81d95494](https://linux-hardware.org/?probe=1a81d95494) | May 09, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [cd09b6b8a5](https://linux-hardware.org/?probe=cd09b6b8a5) | May 09, 2020 |
| HP            | 245 G4 Notebook PC          | Notebook    | [9311532f56](https://linux-hardware.org/?probe=9311532f56) | Apr 23, 2020 |
| HP            | 245 G4 Notebook PC          | Notebook    | [b662f230b2](https://linux-hardware.org/?probe=b662f230b2) | Apr 23, 2020 |
| Apple         | Mac-DB15BD556843C820 iMa... | All in one  | [3c2d508fc2](https://linux-hardware.org/?probe=3c2d508fc2) | Apr 23, 2020 |
| HP            | Notebook                    | Notebook    | [5815277bb0](https://linux-hardware.org/?probe=5815277bb0) | Apr 22, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [1dc3e83e11](https://linux-hardware.org/?probe=1dc3e83e11) | Apr 18, 2020 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [2f87bcd627](https://linux-hardware.org/?probe=2f87bcd627) | Apr 07, 2020 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [16ff51d343](https://linux-hardware.org/?probe=16ff51d343) | Apr 07, 2020 |
| Acer          | Aspire V3-471               | Notebook    | [024d5b0563](https://linux-hardware.org/?probe=024d5b0563) | Apr 06, 2020 |
| Dell          | G3 3590                     | Notebook    | [26a4f7e20b](https://linux-hardware.org/?probe=26a4f7e20b) | Mar 22, 2020 |
| Dell          | G3 3590                     | Notebook    | [96d9b68953](https://linux-hardware.org/?probe=96d9b68953) | Mar 21, 2020 |
| Lenovo        | IdeaPadFlex 4-1480 80VD     | Convertible | [fcea840696](https://linux-hardware.org/?probe=fcea840696) | Mar 04, 2020 |
| Toshiba       | Satellite C855D             | Notebook    | [9246f32b7e](https://linux-hardware.org/?probe=9246f32b7e) | Mar 01, 2020 |
| Lenovo        | IdeaPadFlex 4-1480 80VD     | Convertible | [9398ebaa03](https://linux-hardware.org/?probe=9398ebaa03) | Feb 29, 2020 |
| Lenovo        | IdeaPadFlex 4-1480 80VD     | Convertible | [1419b6c5e7](https://linux-hardware.org/?probe=1419b6c5e7) | Feb 29, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [2bbf18e9e5](https://linux-hardware.org/?probe=2bbf18e9e5) | Feb 20, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [68895d1461](https://linux-hardware.org/?probe=68895d1461) | Feb 20, 2020 |
| HP            | ProBook 6460b               | Notebook    | [121b074dd0](https://linux-hardware.org/?probe=121b074dd0) | Feb 19, 2020 |
| Dell          | Latitude 5500               | Notebook    | [3a7f8e19f1](https://linux-hardware.org/?probe=3a7f8e19f1) | Feb 17, 2020 |
| ASUSTek       | K52F                        | Notebook    | [9dde03d12c](https://linux-hardware.org/?probe=9dde03d12c) | Feb 13, 2020 |
| Microsoft     | Surface with Windows 8 P... | Tablet      | [750ccde7c5](https://linux-hardware.org/?probe=750ccde7c5) | Jan 19, 2020 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [9eb64d7269](https://linux-hardware.org/?probe=9eb64d7269) | Jan 17, 2020 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [8211b13acf](https://linux-hardware.org/?probe=8211b13acf) | Jan 17, 2020 |
| ASRock        | 775i65GV                    | Desktop     | [0367c8a291](https://linux-hardware.org/?probe=0367c8a291) | Jan 07, 2020 |
| Lenovo        | IdeaPadFlex 4-1480 80VD     | Convertible | [5662d620a5](https://linux-hardware.org/?probe=5662d620a5) | Jan 03, 2020 |
| Lenovo        | IdeaPadFlex 4-1480 80VD     | Convertible | [bd9a062902](https://linux-hardware.org/?probe=bd9a062902) | Jan 03, 2020 |
| ASRock        | 775i65GV                    | Desktop     | [d0a8b9d7da](https://linux-hardware.org/?probe=d0a8b9d7da) | Dec 25, 2019 |
| HP            | 240 G6 Notebook PC          | Notebook    | [73da3dccf1](https://linux-hardware.org/?probe=73da3dccf1) | Nov 14, 2019 |
| HP            | 240 G6 Notebook PC          | Notebook    | [efeee7f2fc](https://linux-hardware.org/?probe=efeee7f2fc) | Nov 14, 2019 |
| Dell          | 042P49 A01                  | Desktop     | [ce3194fcde](https://linux-hardware.org/?probe=ce3194fcde) | Oct 28, 2019 |
| System76      | Lemur                       | Notebook    | [a9cc263cb4](https://linux-hardware.org/?probe=a9cc263cb4) | Oct 09, 2019 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [4ddf2bb220](https://linux-hardware.org/?probe=4ddf2bb220) | Oct 06, 2019 |
| HP            | ProBook 450 G2              | Notebook    | [c7959cccb3](https://linux-hardware.org/?probe=c7959cccb3) | Sep 30, 2019 |
| HP            | Notebook                    | Notebook    | [163fc3e9dd](https://linux-hardware.org/?probe=163fc3e9dd) | Sep 14, 2019 |
| Biostar       | H61MGV3                     | Desktop     | [911486bcc2](https://linux-hardware.org/?probe=911486bcc2) | Sep 08, 2019 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [c34161a66d](https://linux-hardware.org/?probe=c34161a66d) | Sep 02, 2019 |
| System76      | Lemur                       | Notebook    | [01bbf99115](https://linux-hardware.org/?probe=01bbf99115) | Sep 02, 2019 |
| Lenovo        | ThinkPad P53 20QNS00P00     | Notebook    | [47182bd3e3](https://linux-hardware.org/?probe=47182bd3e3) | Sep 01, 2019 |
| Lenovo        | ThinkPad P53 20QNS00P00     | Notebook    | [2105fa4def](https://linux-hardware.org/?probe=2105fa4def) | Sep 01, 2019 |
| HP            | Notebook                    | Notebook    | [b7e9995b67](https://linux-hardware.org/?probe=b7e9995b67) | Aug 18, 2019 |
| HP            | Notebook                    | Notebook    | [273d0bcc2e](https://linux-hardware.org/?probe=273d0bcc2e) | Aug 18, 2019 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [2e5b92af00](https://linux-hardware.org/?probe=2e5b92af00) | Aug 17, 2019 |
| Dell          | Latitude E5450              | Notebook    | [3336801ccf](https://linux-hardware.org/?probe=3336801ccf) | Aug 10, 2019 |
| Toshiba       | Satellite A305D             | Notebook    | [ebf0a9c89e](https://linux-hardware.org/?probe=ebf0a9c89e) | Aug 08, 2019 |
| Acer          | SW5-017P                    | Notebook    | [fbf9b74a34](https://linux-hardware.org/?probe=fbf9b74a34) | Jul 29, 2019 |
| Dell          | Latitude 5480               | Notebook    | [f488cfd08f](https://linux-hardware.org/?probe=f488cfd08f) | Jun 22, 2019 |
| Biostar       | H61MGV3                     | Desktop     | [0b1e8f1f08](https://linux-hardware.org/?probe=0b1e8f1f08) | Jun 12, 2019 |
| Intel         | DG41WV AAE90316-103         | Desktop     | [7b2dc235f8](https://linux-hardware.org/?probe=7b2dc235f8) | May 18, 2019 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [328975f3a5](https://linux-hardware.org/?probe=328975f3a5) | May 15, 2019 |
| Dell          | Latitude 5480               | Notebook    | [694ca16d49](https://linux-hardware.org/?probe=694ca16d49) | May 04, 2019 |
| Lenovo        | SHARKBAY 31900003 STD       | Desktop     | [e7164fcda2](https://linux-hardware.org/?probe=e7164fcda2) | Dec 01, 2018 |
| Purism        | Librem 15 v3                | Notebook    | [00259367c8](https://linux-hardware.org/?probe=00259367c8) | Oct 29, 2018 |
| Purism        | Librem 15 v3                | Notebook    | [c5e1ab1520](https://linux-hardware.org/?probe=c5e1ab1520) | Oct 29, 2018 |
| ASUSTek       | X555LAB                     | Notebook    | [243803142a](https://linux-hardware.org/?probe=243803142a) | Aug 01, 2018 |
| Toshiba       | Satellite C645D             | Notebook    | [9d50eb7fdb](https://linux-hardware.org/?probe=9d50eb7fdb) | Nov 24, 2016 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 24        | 8.05%   |
| Ubuntu 22.04                 | 18        | 6.04%   |
| Ubuntu 18.04                 | 17        | 5.7%    |
| OpenMandriva 4.2             | 16        | 5.37%   |
| Zorin 16                     | 7         | 2.35%   |
| OpenMandriva 4.3             | 7         | 2.35%   |
| OpenMandriva 23.03           | 7         | 2.35%   |
| OpenMandriva 23.01           | 7         | 2.35%   |
| Debian 12                    | 6         | 2.01%   |
| Lubuntu 22.04                | 5         | 1.68%   |
| Fedora 38                    | 5         | 1.68%   |
| Debian 11                    | 5         | 1.68%   |
| Ubuntu 19.04                 | 4         | 1.34%   |
| OpenMandriva 23.08           | 4         | 1.34%   |
| Lubuntu 21.10                | 4         | 1.34%   |
| Linux Mint 20.2              | 4         | 1.34%   |
| Linux Mint 19.3              | 4         | 1.34%   |
| Fedora 36                    | 4         | 1.34%   |
| Ubuntu 23.04                 | 3         | 1.01%   |
| Raspbian 11                  | 3         | 1.01%   |
| Pop!_OS 22.04                | 3         | 1.01%   |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 1.01%   |
| Lubuntu 22.10                | 3         | 1.01%   |
| Lubuntu 21.04                | 3         | 1.01%   |
| Kubuntu 22.04                | 3         | 1.01%   |
| KDE neon 22.04               | 3         | 1.01%   |
| Debian 10                    | 3         | 1.01%   |
| Zorin 15                     | 2         | 0.67%   |
| Xubuntu 20.04                | 2         | 0.67%   |
| UbuntuDDE 20.04              | 2         | 0.67%   |
| Ubuntu Studio 20.04          | 2         | 0.67%   |
| Ubuntu 22.10                 | 2         | 0.67%   |
| Ubuntu 21.04                 | 2         | 0.67%   |
| Pop!_OS 21.04                | 2         | 0.67%   |
| Pop!_OS 20.10                | 2         | 0.67%   |
| Manjaro 20.2.1               | 2         | 0.67%   |
| Manjaro                      | 2         | 0.67%   |
| Lubuntu 23.10                | 2         | 0.67%   |
| Lubuntu 23.04                | 2         | 0.67%   |
| Lubuntu 20.04                | 2         | 0.67%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 72        | 26.67%  |
| OpenMandriva  | 40        | 14.81%  |
| Fedora        | 19        | 7.04%   |
| Linux Mint    | 17        | 6.3%    |
| Debian        | 16        | 5.93%   |
| Manjaro       | 11        | 4.07%   |
| Zorin         | 10        | 3.7%    |
| Pop!_OS       | 9         | 3.33%   |
| Lubuntu       | 9         | 3.33%   |
| Kubuntu       | 7         | 2.59%   |
| ROSA          | 6         | 2.22%   |
| KDE neon      | 6         | 2.22%   |
| Xubuntu       | 4         | 1.48%   |
| Raspbian      | 3         | 1.11%   |
| openSUSE      | 3         | 1.11%   |
| Elementary    | 3         | 1.11%   |
| Arch          | 3         | 1.11%   |
| UbuntuDDE     | 2         | 0.74%   |
| Ubuntu Unity  | 2         | 0.74%   |
| Ubuntu Studio | 2         | 0.74%   |
| Ubuntu MATE   | 2         | 0.74%   |
| Parrot        | 2         | 0.74%   |
| Kali          | 2         | 0.74%   |
| Endless       | 2         | 0.74%   |
| EndeavourOS   | 2         | 0.74%   |
| ArcoLinux     | 2         | 0.74%   |
| Ubuntu Budgie | 1         | 0.37%   |
| Reborn OS     | 1         | 0.37%   |
| PureOS        | 1         | 0.37%   |
| Peppermint    | 1         | 0.37%   |
| Nobara        | 1         | 0.37%   |
| Mageia        | 1         | 0.37%   |
| LMDE          | 1         | 0.37%   |
| LinuxFX       | 1         | 0.37%   |
| Crystal Linux | 1         | 0.37%   |
| Clear Linux   | 1         | 0.37%   |
| ChimeraOS     | 1         | 0.37%   |
| BlackPanther  | 1         | 0.37%   |
| BigLinux      | 1         | 0.37%   |
| ALT Linux     | 1         | 0.37%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 16        | 4.86%   |
| 6.2.6-desktop-1omv2390   | 7         | 2.13%   |
| 5.16.7-desktop-1omv4003  | 7         | 2.13%   |
| 6.4.11-desktop-1omv2390  | 5         | 1.52%   |
| 5.4.0-42-generic         | 5         | 1.52%   |
| 6.1.1-desktop-1omv2290   | 4         | 1.22%   |
| 5.4.0-70-generic         | 4         | 1.22%   |
| 5.13.0-16-generic        | 4         | 1.22%   |
| 5.11.0-27-generic        | 4         | 1.22%   |
| 5.0.0-23-generic         | 4         | 1.22%   |
| 6.3.8-200.fc38.x86_64    | 3         | 0.91%   |
| 5.8.0-50-generic         | 3         | 0.91%   |
| 5.4.0-77-generic         | 3         | 0.91%   |
| 5.19.0-32-generic        | 3         | 0.91%   |
| 5.19.0-26-generic        | 3         | 0.91%   |
| 5.15.0-52-generic        | 3         | 0.91%   |
| 5.0.0-25-generic         | 3         | 0.91%   |
| 6.5.0-5-generic          | 2         | 0.61%   |
| 6.2.0-26-generic         | 2         | 0.61%   |
| 6.2.0-20-generic         | 2         | 0.61%   |
| 6.2.0-18-generic         | 2         | 0.61%   |
| 6.1.4-desktop-1omv2301   | 2         | 0.61%   |
| 6.1.0-10-amd64           | 2         | 0.61%   |
| 6.0.6-76060006-generic   | 2         | 0.61%   |
| 5.9.16-1-MANJARO         | 2         | 0.61%   |
| 5.8.0-7630-generic       | 2         | 0.61%   |
| 5.4.0-52-generic         | 2         | 0.61%   |
| 5.4.0-29-generic         | 2         | 0.61%   |
| 5.4.0-26-generic         | 2         | 0.61%   |
| 5.4.0-21-generic         | 2         | 0.61%   |
| 5.3.0-40-generic         | 2         | 0.61%   |
| 5.3.0-28-generic         | 2         | 0.61%   |
| 5.19.0-45-generic        | 2         | 0.61%   |
| 5.18.13-200.fc36.x86_64  | 2         | 0.61%   |
| 5.15.0-83-generic        | 2         | 0.61%   |
| 5.15.0-58-generic        | 2         | 0.61%   |
| 5.15.0-53-generic        | 2         | 0.61%   |
| 5.15.0-41-generic        | 2         | 0.61%   |
| 5.15.0-27-generic        | 2         | 0.61%   |
| 5.15.0-25-generic        | 2         | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 37        | 11.94%  |
| 5.15.0  | 29        | 9.35%   |
| 5.10.14 | 16        | 5.16%   |
| 5.11.0  | 15        | 4.84%   |
| 5.19.0  | 14        | 4.52%   |
| 4.15.0  | 12        | 3.87%   |
| 5.3.0   | 10        | 3.23%   |
| 5.13.0  | 10        | 3.23%   |
| 6.2.0   | 9         | 2.9%    |
| 5.8.0   | 9         | 2.9%    |
| 5.0.0   | 9         | 2.9%    |
| 5.10.0  | 8         | 2.58%   |
| 6.2.6   | 7         | 2.26%   |
| 6.1.0   | 7         | 2.26%   |
| 5.16.7  | 7         | 2.26%   |
| 6.1.1   | 6         | 1.94%   |
| 6.4.11  | 5         | 1.61%   |
| 6.5.0   | 4         | 1.29%   |
| 6.3.8   | 3         | 0.97%   |
| 5.18.13 | 3         | 0.97%   |
| 4.19.0  | 3         | 0.97%   |
| 6.4.6   | 2         | 0.65%   |
| 6.3.6   | 2         | 0.65%   |
| 6.1.4   | 2         | 0.65%   |
| 6.1.2   | 2         | 0.65%   |
| 6.0.6   | 2         | 0.65%   |
| 5.9.16  | 2         | 0.65%   |
| 5.7.0   | 2         | 0.65%   |
| 4.18.0  | 2         | 0.65%   |
| 6.6.6   | 1         | 0.32%   |
| 6.6.2   | 1         | 0.32%   |
| 6.6.0   | 1         | 0.32%   |
| 6.5.9   | 1         | 0.32%   |
| 6.5.8   | 1         | 0.32%   |
| 6.5.6   | 1         | 0.32%   |
| 6.5.11  | 1         | 0.32%   |
| 6.3.4   | 1         | 0.32%   |
| 6.3.3   | 1         | 0.32%   |
| 6.3.1   | 1         | 0.32%   |
| 6.2.7   | 1         | 0.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 38        | 12.3%   |
| 5.15    | 37        | 11.97%  |
| 5.10    | 31        | 10.03%  |
| 6.1     | 21        | 6.8%    |
| 5.11    | 19        | 6.15%   |
| 6.2     | 18        | 5.83%   |
| 5.19    | 18        | 5.83%   |
| 4.15    | 12        | 3.88%   |
| 5.13    | 11        | 3.56%   |
| 5.8     | 10        | 3.24%   |
| 5.3     | 10        | 3.24%   |
| 5.0     | 10        | 3.24%   |
| 6.5     | 8         | 2.59%   |
| 6.3     | 8         | 2.59%   |
| 6.4     | 7         | 2.27%   |
| 6.0     | 7         | 2.27%   |
| 5.16    | 7         | 2.27%   |
| 5.18    | 6         | 1.94%   |
| 5.9     | 5         | 1.62%   |
| 5.6     | 4         | 1.29%   |
| 4.19    | 4         | 1.29%   |
| 6.6     | 3         | 0.97%   |
| 5.12    | 3         | 0.97%   |
| 4.18    | 3         | 0.97%   |
| 5.7     | 2         | 0.65%   |
| 5.14    | 2         | 0.65%   |
| 4.1     | 2         | 0.65%   |
| 5.2     | 1         | 0.32%   |
| 5.17    | 1         | 0.32%   |
| 4.9     | 1         | 0.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 244       | 96.44%  |
| i686   | 6         | 2.37%   |
| armv6l | 2         | 0.79%   |
| armv7l | 1         | 0.4%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 120       | 45.45%  |
| KDE5          | 58        | 21.97%  |
| Unknown       | 21        | 7.95%   |
| XFCE          | 14        | 5.3%    |
| LXQt          | 10        | 3.79%   |
| X-Cinnamon    | 9         | 3.41%   |
| MATE          | 9         | 3.41%   |
| KDE           | 4         | 1.52%   |
| Pantheon      | 3         | 1.14%   |
| LXDE          | 3         | 1.14%   |
| Unity         | 2         | 0.76%   |
| Openbox       | 2         | 0.76%   |
| i3            | 2         | 0.76%   |
| Deepin        | 2         | 0.76%   |
| Cinnamon      | 2         | 0.76%   |
| onyx:GNOME    | 1         | 0.38%   |
| GNOME Classic | 1         | 0.38%   |
| Budgie        | 1         | 0.38%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 186       | 72.09%  |
| Wayland | 58        | 22.48%  |
| Unknown | 8         | 3.1%    |
| Tty     | 6         | 2.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 104       | 39.69%  |
| SDDM    | 67        | 25.57%  |
| GDM3    | 30        | 11.45%  |
| GDM     | 27        | 10.31%  |
| LightDM | 23        | 8.78%   |
| TDM     | 11        | 4.2%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 119       | 44.74%  |
| es_CR   | 97        | 36.47%  |
| Unknown | 19        | 7.14%   |
| es_ES   | 16        | 6.02%   |
| es_MX   | 4         | 1.5%    |
| en_GB   | 3         | 1.13%   |
| C       | 3         | 1.13%   |
| fr_FR   | 2         | 0.75%   |
| es_EC   | 1         | 0.38%   |
| en_AG   | 1         | 0.38%   |
| de_DE   | 1         | 0.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 142       | 54.83%  |
| BIOS | 117       | 45.17%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 179       | 68.32%  |
| Overlay | 37        | 14.12%  |
| Btrfs   | 30        | 11.45%  |
| Tmpfs   | 9         | 3.44%   |
| Unknown | 5         | 1.91%   |
| Xfs     | 2         | 0.76%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 115       | 44.4%   |
| GPT     | 114       | 44.02%  |
| MBR     | 30        | 11.58%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 219       | 84.56%  |
| Yes       | 40        | 15.44%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 161       | 62.16%  |
| Yes       | 98        | 37.84%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 52        | 20.55%  |
| Hewlett-Packard         | 41        | 16.21%  |
| Lenovo                  | 30        | 11.86%  |
| ASUSTek Computer        | 29        | 11.46%  |
| Toshiba                 | 14        | 5.53%   |
| MSI                     | 13        | 5.14%   |
| Gigabyte Technology     | 12        | 4.74%   |
| Acer                    | 12        | 4.74%   |
| ASRock                  | 8         | 3.16%   |
| Apple                   | 8         | 3.16%   |
| Intel                   | 4         | 1.58%   |
| Raspberry Pi Foundation | 3         | 1.19%   |
| Unknown                 | 3         | 1.19%   |
| Sony                    | 2         | 0.79%   |
| Samsung Electronics     | 2         | 0.79%   |
| Google                  | 2         | 0.79%   |
| ZOTAC                   | 1         | 0.4%    |
| TPV-INVENTA             | 1         | 0.4%    |
| System76                | 1         | 0.4%    |
| Supermicro              | 1         | 0.4%    |
| Purism                  | 1         | 0.4%    |
| Pegatron                | 1         | 0.4%    |
| Olivetti                | 1         | 0.4%    |
| Microsoft               | 1         | 0.4%    |
| MACHINIST               | 1         | 0.4%    |
| Jumper                  | 1         | 0.4%    |
| HUAWEI                  | 1         | 0.4%    |
| Gateway                 | 1         | 0.4%    |
| Foxconn                 | 1         | 0.4%    |
| Deffad                  | 1         | 0.4%    |
| Biostar                 | 1         | 0.4%    |
| AZW                     | 1         | 0.4%    |
| Alienware               | 1         | 0.4%    |
| ABIT                    | 1         | 0.4%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| Dell OptiPlex 3020        | 6         | 2.37%   |
| Unknown                   | 6         | 2.37%   |
| Dell Inspiron 7506 2n1    | 4         | 1.58%   |
| Apple MacBookPro8,1       | 4         | 1.58%   |
| HP Notebook               | 3         | 1.19%   |
| Dell Inspiron 5584        | 3         | 1.19%   |
| RPi Raspberry Pi          | 2         | 0.79%   |
| MSI MS-7C51               | 2         | 0.79%   |
| Intel NUC12WSHi7          | 2         | 0.79%   |
| HP ProBook 6460b          | 2         | 0.79%   |
| HP Pavilion Notebook      | 2         | 0.79%   |
| HP Laptop 15-da0xxx       | 2         | 0.79%   |
| Gigabyte B250M-DS3H       | 2         | 0.79%   |
| Dell OptiPlex 7040        | 2         | 0.79%   |
| ASUS TUF Gaming X570-PLUS | 2         | 0.79%   |
| ASUS PRIME H310M-E R2.0   | 2         | 0.79%   |
| ASUS PRIME A320M-K        | 2         | 0.79%   |
| ASRock B450 Steel Legend  | 2         | 0.79%   |
| ZOTAC NM10                | 1         | 0.4%    |
| TPV-INVENTA 18-2003LA     | 1         | 0.4%    |
| Toshiba Satellite X205    | 1         | 0.4%    |
| Toshiba Satellite S55-A   | 1         | 0.4%    |
| Toshiba Satellite L845    | 1         | 0.4%    |
| Toshiba Satellite L755    | 1         | 0.4%    |
| Toshiba Satellite L655    | 1         | 0.4%    |
| Toshiba Satellite L45-B   | 1         | 0.4%    |
| Toshiba Satellite C855D   | 1         | 0.4%    |
| Toshiba Satellite C845    | 1         | 0.4%    |
| Toshiba Satellite C645D   | 1         | 0.4%    |
| Toshiba Satellite C55-C   | 1         | 0.4%    |
| Toshiba Satellite C55-B   | 1         | 0.4%    |
| Toshiba Satellite C45-A   | 1         | 0.4%    |
| Toshiba Satellite A305D   | 1         | 0.4%    |
| Toshiba QOSMIO X775       | 1         | 0.4%    |
| System76 Lemur            | 1         | 0.4%    |
| Supermicro X9DAi          | 1         | 0.4%    |
| Sony SVE14123CLW          | 1         | 0.4%    |
| Sony SVD13215PLB          | 1         | 0.4%    |
| Samsung 930X2K/931X2K     | 1         | 0.4%    |
| Samsung 930QAA            | 1         | 0.4%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 18        | 7.11%   |
| Dell Inspiron         | 18        | 7.11%   |
| Toshiba Satellite     | 13        | 5.14%   |
| Dell Latitude         | 12        | 4.74%   |
| Dell OptiPlex         | 11        | 4.35%   |
| Acer Aspire           | 10        | 3.95%   |
| HP Pavilion           | 8         | 3.16%   |
| Lenovo IdeaPad        | 7         | 2.77%   |
| HP EliteBook          | 7         | 2.77%   |
| HP Laptop             | 6         | 2.37%   |
| Unknown               | 6         | 2.37%   |
| HP ProBook            | 5         | 1.98%   |
| ASUS PRIME            | 5         | 1.98%   |
| Dell Precision        | 4         | 1.58%   |
| ASUS VivoBook         | 4         | 1.58%   |
| ASUS TUF              | 4         | 1.58%   |
| Apple MacBookPro8     | 4         | 1.58%   |
| RPi Raspberry         | 3         | 1.19%   |
| HP Notebook           | 3         | 1.19%   |
| Dell XPS              | 3         | 1.19%   |
| MSI MS-7C51           | 2         | 0.79%   |
| Lenovo IdeaPadFlex    | 2         | 0.79%   |
| Intel NUC12WSHi7      | 2         | 0.79%   |
| Gigabyte B250M-DS3H   | 2         | 0.79%   |
| Dell G3               | 2         | 0.79%   |
| ASUS Strix            | 2         | 0.79%   |
| ASUS SABERTOOTH       | 2         | 0.79%   |
| ASRock B450           | 2         | 0.79%   |
| ZOTAC NM10            | 1         | 0.4%    |
| TPV-INVENTA 18-2003LA | 1         | 0.4%    |
| Toshiba QOSMIO        | 1         | 0.4%    |
| System76 Lemur        | 1         | 0.4%    |
| Supermicro X9DAi      | 1         | 0.4%    |
| Sony SVE14123CLW      | 1         | 0.4%    |
| Sony SVD13215PLB      | 1         | 0.4%    |
| Samsung 930X2K        | 1         | 0.4%    |
| Samsung 930QAA        | 1         | 0.4%    |
| Purism Librem         | 1         | 0.4%    |
| Pegatron CQ2728LA     | 1         | 0.4%    |
| Olivetti CL133A       | 1         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 31        | 12.25%  |
| 2018    | 23        | 9.09%   |
| 2020    | 22        | 8.7%    |
| 2014    | 22        | 8.7%    |
| 2012    | 21        | 8.3%    |
| 2016    | 20        | 7.91%   |
| 2011    | 20        | 7.91%   |
| 2013    | 15        | 5.93%   |
| 2015    | 13        | 5.14%   |
| 2017    | 12        | 4.74%   |
| 2021    | 11        | 4.35%   |
| 2022    | 8         | 3.16%   |
| 2010    | 7         | 2.77%   |
| 2008    | 7         | 2.77%   |
| 2009    | 6         | 2.37%   |
| 2007    | 4         | 1.58%   |
| 2023    | 3         | 1.19%   |
| 2006    | 3         | 1.19%   |
| Unknown | 3         | 1.19%   |
| 2005    | 2         | 0.79%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 156       | 61.66%  |
| Desktop        | 77        | 30.43%  |
| Convertible    | 8         | 3.16%   |
| System on chip | 3         | 1.19%   |
| Tablet         | 3         | 1.19%   |
| All in one     | 3         | 1.19%   |
| Mini pc        | 2         | 0.79%   |
| Server         | 1         | 0.4%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 232       | 91.7%   |
| Enabled  | 21        | 8.3%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 250       | 98.81%  |
| Yes  | 3         | 1.19%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 58        | 22.22%  |
| 8.01-16.0       | 53        | 20.31%  |
| 16.01-24.0      | 52        | 19.92%  |
| 3.01-4.0        | 48        | 18.39%  |
| 32.01-64.0      | 20        | 7.66%   |
| 1.01-2.0        | 9         | 3.45%   |
| 24.01-32.0      | 6         | 2.3%    |
| 64.01-256.0     | 6         | 2.3%    |
| 2.01-3.0        | 4         | 1.53%   |
| 0.51-1.0        | 2         | 0.77%   |
| 0.01-0.5        | 2         | 0.77%   |
| More than 256.0 | 1         | 0.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 107       | 37.94%  |
| 2.01-3.0   | 71        | 25.18%  |
| 4.01-8.0   | 40        | 14.18%  |
| 3.01-4.0   | 33        | 11.7%   |
| 0.51-1.0   | 12        | 4.26%   |
| 8.01-16.0  | 8         | 2.84%   |
| 0.01-0.5   | 6         | 2.13%   |
| 16.01-24.0 | 4         | 1.42%   |
| 24.01-32.0 | 1         | 0.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 170       | 65.64%  |
| 2      | 62        | 23.94%  |
| 3      | 15        | 5.79%   |
| 4      | 8         | 3.09%   |
| 8      | 1         | 0.39%   |
| 7      | 1         | 0.39%   |
| 6      | 1         | 0.39%   |
| 5      | 1         | 0.39%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 150       | 58.37%  |
| Yes       | 107       | 41.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 225       | 88.93%  |
| No        | 28        | 11.07%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 203       | 79.61%  |
| No        | 52        | 20.39%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 152       | 58.69%  |
| No        | 107       | 41.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country    | Computers | Percent |
|------------|-----------|---------|
| Costa Rica | 253       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| San José     | 114       | 40.28%  |
| Heredia       | 49        | 17.31%  |
| Alajuela      | 20        | 7.07%   |
| Grecia        | 12        | 4.24%   |
| Escazu        | 10        | 3.53%   |
| Cartago       | 8         | 2.83%   |
| Rio Segundo   | 6         | 2.12%   |
| Quesada       | 5         | 1.77%   |
| Puntarenas    | 5         | 1.77%   |
| Santa Ana     | 3         | 1.06%   |
| San Ramon     | 3         | 1.06%   |
| Naranjo       | 3         | 1.06%   |
| Liberia       | 3         | 1.06%   |
| Tres Rios     | 2         | 0.71%   |
| Siquirres     | 2         | 0.71%   |
| Santa Fe      | 2         | 0.71%   |
| Santa Cruz    | 2         | 0.71%   |
| San Pedro     | 2         | 0.71%   |
| Pavas         | 2         | 0.71%   |
| Palmares      | 2         | 0.71%   |
| Nosara        | 2         | 0.71%   |
| Esparza       | 2         | 0.71%   |
| Curridabat    | 2         | 0.71%   |
| Colon         | 2         | 0.71%   |
| Bagaces       | 2         | 0.71%   |
| Zarcero       | 1         | 0.35%   |
| Tibas         | 1         | 0.35%   |
| Santo Domingo | 1         | 0.35%   |
| Santiago      | 1         | 0.35%   |
| San Rafael    | 1         | 0.35%   |
| San Pablo     | 1         | 0.35%   |
| San Juan      | 1         | 0.35%   |
| San Francisco | 1         | 0.35%   |
| San Felipe    | 1         | 0.35%   |
| Quepos        | 1         | 0.35%   |
| Perez Zeledon | 1         | 0.35%   |
| La Fortuna    | 1         | 0.35%   |
| Guapiles      | 1         | 0.35%   |
| Guacima       | 1         | 0.35%   |
| Cariblanca    | 1         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 51        | 84     | 14.45%  |
| WDC                         | 50        | 72     | 14.16%  |
| Samsung Electronics         | 32        | 54     | 9.07%   |
| Toshiba                     | 31        | 37     | 8.78%   |
| Kingston                    | 24        | 35     | 6.8%    |
| A-DATA Technology           | 21        | 22     | 5.95%   |
| Intel                       | 17        | 41     | 4.82%   |
| Unknown                     | 15        | 21     | 4.25%   |
| HGST                        | 12        | 13     | 3.4%    |
| Patriot                     | 9         | 11     | 2.55%   |
| Sandisk                     | 8         | 10     | 2.27%   |
| Hitachi                     | 8         | 11     | 2.27%   |
| Crucial                     | 8         | 8      | 2.27%   |
| JMicron Technology          | 7         | 7      | 1.98%   |
| SK hynix                    | 6         | 12     | 1.7%    |
| Micron Technology           | 5         | 6      | 1.42%   |
| XPG                         | 4         | 4      | 1.13%   |
| Team                        | 4         | 4      | 1.13%   |
| Realtek Semiconductor       | 4         | 6      | 1.13%   |
| Netac                       | 4         | 5      | 1.13%   |
| Mushkin                     | 3         | 3      | 0.85%   |
| ZOTAC                       | 2         | 3      | 0.57%   |
| Maxtor                      | 2         | 2      | 0.57%   |
| LITEONIT                    | 2         | 2      | 0.57%   |
| KIOXIA                      | 2         | 2      | 0.57%   |
| Kingston Technology Company | 2         | 2      | 0.57%   |
| Gigabyte Technology         | 2         | 3      | 0.57%   |
| ADATA Technology            | 2         | 2      | 0.57%   |
| Unknown                     | 2         | 2      | 0.57%   |
| Zheino                      | 1         | 1      | 0.28%   |
| WD MediaMax                 | 1         | 1      | 0.28%   |
| UMIS                        | 1         | 1      | 0.28%   |
| Transcend                   | 1         | 1      | 0.28%   |
| T-FORCE                     | 1         | 1      | 0.28%   |
| Silicon Motion              | 1         | 1      | 0.28%   |
| Phison Electronics          | 1         | 1      | 0.28%   |
| LITEON                      | 1         | 1      | 0.28%   |
| Fujitsu                     | 1         | 1      | 0.28%   |
| FORESEE                     | 1         | 3      | 0.28%   |
| Dell                        | 1         | 1      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD    | 9         | 2.33%   |
| JMicron Generic 250GB              | 7         | 1.81%   |
| Toshiba MQ01ABF050 500GB           | 6         | 1.55%   |
| Toshiba MQ01ABD100 1TB             | 6         | 1.55%   |
| A-DATA SU630 480GB SSD             | 6         | 1.55%   |
| Toshiba DT01ACA100 1TB             | 5         | 1.3%    |
| Seagate ST1000LM035-1RK172 1TB     | 4         | 1.04%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 4         | 1.04%   |
| Intel H10 HBRPEKNX0203AO NVMe 32GB | 4         | 1.04%   |
| Intel H10 HBRPEKNX0203A NVMe 1TB   | 4         | 1.04%   |
| HGST HTS541075A9E680 752GB         | 4         | 1.04%   |
| A-DATA SU650 120GB SSD             | 4         | 1.04%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 3         | 0.78%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 3         | 0.78%   |
| WDC WD10EZEX-75WN4A1 1TB           | 3         | 0.78%   |
| WDC WD10EZEX-08WN4A0 1TB           | 3         | 0.78%   |
| Toshiba KBG30ZMS256G NVMe 256GB    | 3         | 0.78%   |
| Seagate ST2000LM007-1R8174 2TB     | 3         | 0.78%   |
| Seagate ST1000DM003-1CH162 1TB     | 3         | 0.78%   |
| Kingston SV300S37A120G 120GB SSD   | 3         | 0.78%   |
| Kingston SA400S37960G 960GB SSD    | 3         | 0.78%   |
| Intel SSDSC2BF180A4H 180GB         | 3         | 0.78%   |
| Intel SSDSA2CW300G3 304GB          | 3         | 0.78%   |
| HGST HTS541010A9E680 1TB           | 3         | 0.78%   |
| XPG GAMMIX S11 Pro 256GB           | 2         | 0.52%   |
| WDC WDS200T2B0B-00YS70 2TB SSD     | 2         | 0.52%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 2         | 0.52%   |
| WDC WD5000LPCX-60VHAT0 500GB       | 2         | 0.52%   |
| WDC WD20SPZX-08UA7 2TB             | 2         | 0.52%   |
| Unknown MMC Card  64GB             | 2         | 0.52%   |
| Unknown MMC Card  128GB            | 2         | 0.52%   |
| Unknown 00000  32GB                | 2         | 0.52%   |
| Toshiba NVMe SSD Drive 256GB       | 2         | 0.52%   |
| Team T253X1240G 240GB SSD          | 2         | 0.52%   |
| SK hynix NVMe SSD Drive 128GB      | 2         | 0.52%   |
| Seagate ST9500325AS 500GB          | 2         | 0.52%   |
| Seagate ST8000DM004-2CX188 8TB     | 2         | 0.52%   |
| Seagate ST500LT012-1DG142 500GB    | 2         | 0.52%   |
| Seagate ST500LM021-1KJ152 500GB    | 2         | 0.52%   |
| Seagate ST500DM002-1BD142 500GB    | 2         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 49        | 82     | 35.25%  |
| WDC                 | 37        | 45     | 26.62%  |
| Toshiba             | 26        | 28     | 18.71%  |
| HGST                | 12        | 13     | 8.63%   |
| Hitachi             | 8         | 11     | 5.76%   |
| Samsung Electronics | 2         | 2      | 1.44%   |
| Maxtor              | 2         | 2      | 1.44%   |
| Unknown             | 1         | 2      | 0.72%   |
| Fujitsu             | 1         | 1      | 0.72%   |
| Apple               | 1         | 1      | 0.72%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 22        | 28     | 17.89%  |
| A-DATA Technology   | 17        | 18     | 13.82%  |
| WDC                 | 12        | 22     | 9.76%   |
| Samsung Electronics | 10        | 26     | 8.13%   |
| Intel               | 9         | 23     | 7.32%   |
| Patriot             | 8         | 10     | 6.5%    |
| JMicron Technology  | 7         | 7      | 5.69%   |
| SanDisk             | 6         | 8      | 4.88%   |
| Crucial             | 6         | 6      | 4.88%   |
| Team                | 4         | 4      | 3.25%   |
| Micron Technology   | 4         | 4      | 3.25%   |
| Netac               | 3         | 3      | 2.44%   |
| Mushkin             | 3         | 3      | 2.44%   |
| ZOTAC               | 2         | 3      | 1.63%   |
| LITEONIT            | 2         | 2      | 1.63%   |
| Gigabyte Technology | 2         | 3      | 1.63%   |
| Transcend           | 1         | 1      | 0.81%   |
| Seagate             | 1         | 1      | 0.81%   |
| LITEON              | 1         | 1      | 0.81%   |
| FORESEE             | 1         | 3      | 0.81%   |
| CT120BX5            | 1         | 1      | 0.81%   |
| BP4                 | 1         | 1      | 0.81%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 124       | 187    | 38.39%  |
| SSD     | 113       | 178    | 34.98%  |
| NVMe    | 67        | 111    | 20.74%  |
| MMC     | 15        | 20     | 4.64%   |
| Unknown | 4         | 5      | 1.24%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 209       | 351    | 68.52%  |
| NVMe | 66        | 110    | 21.64%  |
| SAS  | 15        | 20     | 4.92%   |
| MMC  | 15        | 20     | 4.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 146       | 218    | 60.08%  |
| 0.51-1.0   | 73        | 111    | 30.04%  |
| 1.01-2.0   | 16        | 19     | 6.58%   |
| 4.01-10.0  | 5         | 13     | 2.06%   |
| 3.01-4.0   | 2         | 2      | 0.82%   |
| 2.01-3.0   | 1         | 2      | 0.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 68        | 24.64%  |
| 251-500        | 48        | 17.39%  |
| 501-1000       | 47        | 17.03%  |
| 1-20           | 30        | 10.87%  |
| 1001-2000      | 24        | 8.7%    |
| 51-100         | 23        | 8.33%   |
| 21-50          | 13        | 4.71%   |
| More than 3000 | 12        | 4.35%   |
| 2001-3000      | 6         | 2.17%   |
| Unknown        | 5         | 1.81%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 126       | 44.06%  |
| 21-50          | 48        | 16.78%  |
| 101-250        | 30        | 10.49%  |
| 51-100         | 30        | 10.49%  |
| 251-500        | 23        | 8.04%   |
| 501-1000       | 13        | 4.55%   |
| More than 3000 | 5         | 1.75%   |
| Unknown        | 5         | 1.75%   |
| 1001-2000      | 4         | 1.4%    |
| 2001-3000      | 2         | 0.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Intel H10 HBRPEKNX0203A NVMe 1TB                    | 4         | 4      | 14.29%  |
| WDC WD5000LPCX-60VHAT0 500GB                        | 1         | 1      | 3.57%   |
| WDC WD10JPVX-60JC3T0 1TB                            | 1         | 1      | 3.57%   |
| Unknown MB3000EBKAB 3TB                             | 1         | 1      | 3.57%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 1      | 3.57%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 3.57%   |
| Toshiba MK6476GSX 640GB                             | 1         | 1      | 3.57%   |
| Toshiba MK2565GSXV 250GB                            | 1         | 1      | 3.57%   |
| Seagate ST9320310AS 320GB                           | 1         | 1      | 3.57%   |
| Seagate ST9160412AS 160GB                           | 1         | 1      | 3.57%   |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 1      | 3.57%   |
| Seagate ST500DM002-1BD142 500GB                     | 1         | 2      | 3.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 3.57%   |
| Seagate ST1000DM003-1CH162 1TB                      | 1         | 1      | 3.57%   |
| SanDisk SD6SB1M-128G-1006 128GB SSD                 | 1         | 2      | 3.57%   |
| Netac SSD 120GB                                     | 1         | 1      | 3.57%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 3.57%   |
| Maxtor STM3160215AS 160GB                           | 1         | 1      | 3.57%   |
| Kingston SV300S37A120G 120GB SSD                    | 1         | 1      | 3.57%   |
| Intel SSDSC2BF180A4H 180GB                          | 1         | 1      | 3.57%   |
| Hitachi HTS547550A9E384 500GB                       | 1         | 2      | 3.57%   |
| Hitachi HDE721010SLA330 1TB                         | 1         | 1      | 3.57%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 3.57%   |
| HGST HTS545050A7E380 500GB                          | 1         | 1      | 3.57%   |
| A-DATA Technology SX8100NP 256GB                    | 1         | 1      | 3.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 6         | 7      | 21.43%  |
| Intel             | 5         | 5      | 17.86%  |
| Toshiba           | 4         | 4      | 14.29%  |
| WDC               | 2         | 2      | 7.14%   |
| Hitachi           | 2         | 3      | 7.14%   |
| HGST              | 2         | 2      | 7.14%   |
| Unknown           | 1         | 1      | 3.57%   |
| SanDisk           | 1         | 2      | 3.57%   |
| Netac             | 1         | 1      | 3.57%   |
| Micron Technology | 1         | 1      | 3.57%   |
| Maxtor            | 1         | 1      | 3.57%   |
| Kingston          | 1         | 1      | 3.57%   |
| A-DATA Technology | 1         | 1      | 3.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 7      | 33.33%  |
| Toshiba | 4         | 4      | 22.22%  |
| WDC     | 2         | 2      | 11.11%  |
| Hitachi | 2         | 3      | 11.11%  |
| HGST    | 2         | 2      | 11.11%  |
| Unknown | 1         | 1      | 5.56%   |
| Maxtor  | 1         | 1      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 17        | 20     | 62.96%  |
| NVMe | 5         | 5      | 18.52%  |
| SSD  | 5         | 6      | 18.52%  |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 145       | 259    | 51.42%  |
| Works    | 111       | 211    | 39.36%  |
| Malfunc  | 26        | 31     | 9.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 181       | 58.58%  |
| AMD                          | 47        | 15.21%  |
| Samsung Electronics          | 20        | 6.47%   |
| ASMedia Technology           | 8         | 2.59%   |
| ADATA Technology             | 7         | 2.27%   |
| Realtek Semiconductor        | 6         | 1.94%   |
| SK hynix                     | 5         | 1.62%   |
| SanDisk                      | 5         | 1.62%   |
| Toshiba America Info Systems | 4         | 1.29%   |
| Nvidia                       | 4         | 1.29%   |
| Kingston Technology Company  | 4         | 1.29%   |
| Silicon Motion               | 2         | 0.65%   |
| Micron/Crucial Technology    | 2         | 0.65%   |
| Micron Technology            | 2         | 0.65%   |
| KIOXIA                       | 2         | 0.65%   |
| Union Memory (Shenzhen)      | 1         | 0.32%   |
| Solidigm                     | 1         | 0.32%   |
| Silicon Image                | 1         | 0.32%   |
| Phison Electronics           | 1         | 0.32%   |
| OCZ Technology Group         | 1         | 0.32%   |
| Marvell Technology Group     | 1         | 0.32%   |
| LSI Logic / Symbios Logic    | 1         | 0.32%   |
| JMicron Technology           | 1         | 0.32%   |
| INNOGRIT                     | 1         | 0.32%   |
| Apple                        | 1         | 0.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 31        | 9.09%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 18        | 5.28%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 16        | 4.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 15        | 4.4%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 14        | 4.11%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 11        | 3.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 9         | 2.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 9         | 2.64%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 8         | 2.35%   |
| ASMedia ASM1062 Serial ATA Controller                                                  | 8         | 2.35%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 7         | 2.05%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 6         | 1.76%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 6         | 1.76%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 6         | 1.76%   |
| AMD FCH SATA Controller D                                                              | 6         | 1.76%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                            | 6         | 1.76%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 5         | 1.47%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]                     | 5         | 1.47%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                       | 5         | 1.47%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 4         | 1.17%   |
| Realtek RTS5762 NVMe SSD Controller                                                    | 4         | 1.17%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 4         | 1.17%   |
| Intel SATA Controller [RAID mode]                                                      | 4         | 1.17%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 4         | 1.17%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 4         | 1.17%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 4         | 1.17%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)                    | 3         | 0.88%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                   | 3         | 0.88%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                            | 3         | 0.88%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                             | 3         | 0.88%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 3         | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller          | 3         | 0.88%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 3         | 0.88%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 3         | 0.88%   |
| AMD 400 Series Chipset SATA Controller                                                 | 3         | 0.88%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 2         | 0.59%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                      | 2         | 0.59%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                              | 2         | 0.59%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation                  | 2         | 0.59%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                       | 2         | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 192       | 61.54%  |
| NVMe | 67        | 21.47%  |
| IDE  | 29        | 9.29%   |
| RAID | 22        | 7.05%   |
| SAS  | 1         | 0.32%   |
| SCSI | 1         | 0.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 197       | 77.87%  |
| AMD    | 53        | 20.95%  |
| ARM    | 3         | 1.19%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz           | 6         | 2.37%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 6         | 2.37%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 5         | 1.98%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 4         | 1.58%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 4         | 1.58%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 4         | 1.58%   |
| AMD Ryzen 5 3600 6-Core Processor           | 4         | 1.58%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 3         | 1.19%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 1.19%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 3         | 1.19%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 3         | 1.19%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 3         | 1.19%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 3         | 1.19%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 3         | 1.19%   |
| ARM BCM2835 Processor                       | 3         | 1.19%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 3         | 1.19%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 2         | 0.79%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 2         | 0.79%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 2         | 0.79%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2         | 0.79%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 0.79%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2         | 0.79%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 0.79%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 2         | 0.79%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 2         | 0.79%   |
| Intel Core i3-8130U CPU @ 2.20GHz           | 2         | 0.79%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 2         | 0.79%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2         | 0.79%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2         | 0.79%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 2         | 0.79%   |
| Intel Core 2 CPU T7200 @ 2.00GHz            | 2         | 0.79%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 2         | 0.79%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 2         | 0.79%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 2         | 0.79%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 2         | 0.79%   |
| Intel 12th Gen Core i7-1260P                | 2         | 0.79%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz     | 2         | 0.79%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 2         | 0.79%   |
| AMD Ryzen 7 4700U with Radeon Graphics      | 2         | 0.79%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2         | 0.79%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 58        | 22.92%  |
| Intel Core i7                  | 47        | 18.58%  |
| Intel Core i3                  | 23        | 9.09%   |
| Other                          | 20        | 7.91%   |
| Intel Celeron                  | 19        | 7.51%   |
| AMD Ryzen 7                    | 10        | 3.95%   |
| AMD Ryzen 5                    | 10        | 3.95%   |
| AMD Ryzen 3                    | 7         | 2.77%   |
| Intel Xeon                     | 6         | 2.37%   |
| Intel Core 2 Duo               | 5         | 1.98%   |
| AMD FX                         | 5         | 1.98%   |
| Intel Pentium                  | 4         | 1.58%   |
| Intel Core 2                   | 4         | 1.58%   |
| Intel Atom                     | 4         | 1.58%   |
| AMD E1                         | 4         | 1.58%   |
| ARM BCM                        | 3         | 1.19%   |
| AMD A10                        | 3         | 1.19%   |
| Intel Genuine                  | 2         | 0.79%   |
| AMD A8                         | 2         | 0.79%   |
| Intel Xeon Silver              | 1         | 0.4%    |
| Intel Pentium Dual-Core        | 1         | 0.4%    |
| Intel Pentium 4                | 1         | 0.4%    |
| Intel Core M                   | 1         | 0.4%    |
| Intel Core i9                  | 1         | 0.4%    |
| Intel Core 2 Quad              | 1         | 0.4%    |
| AMD V120                       | 1         | 0.4%    |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.4%    |
| AMD Turion 64 X2               | 1         | 0.4%    |
| AMD Sempron                    | 1         | 0.4%    |
| AMD Ryzen 7 PRO                | 1         | 0.4%    |
| AMD PRO A10                    | 1         | 0.4%    |
| AMD Phenom II X4               | 1         | 0.4%    |
| AMD E2                         | 1         | 0.4%    |
| AMD Athlon II X2               | 1         | 0.4%    |
| AMD Athlon                     | 1         | 0.4%    |
| AMD A4                         | 1         | 0.4%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 118       | 46.64%  |
| 4      | 81        | 32.02%  |
| 6      | 21        | 8.3%    |
| 8      | 15        | 5.93%   |
| 1      | 9         | 3.56%   |
| 10     | 3         | 1.19%   |
| 12     | 2         | 0.79%   |
| 24     | 1         | 0.4%    |
| 20     | 1         | 0.4%    |
| 16     | 1         | 0.4%    |
| 3      | 1         | 0.4%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 251       | 99.21%  |
| 2      | 2         | 0.79%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 160       | 63.24%  |
| 1      | 93        | 36.76%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 245       | 96.46%  |
| Unknown        | 6         | 2.36%   |
| 32-bit         | 3         | 1.18%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 72        | 27.07%  |
| 0x206a7    | 14        | 5.26%   |
| 0x306c3    | 13        | 4.89%   |
| 0x306a9    | 11        | 4.14%   |
| 0x08108109 | 9         | 3.38%   |
| 0x40651    | 7         | 2.63%   |
| 0x806e9    | 6         | 2.26%   |
| 0x806c1    | 6         | 2.26%   |
| 0x506e3    | 6         | 2.26%   |
| 0x406e3    | 6         | 2.26%   |
| 0x306d4    | 6         | 2.26%   |
| 0x906ea    | 5         | 1.88%   |
| 0x906e9    | 5         | 1.88%   |
| 0x806ec    | 5         | 1.88%   |
| 0x406c4    | 5         | 1.88%   |
| 0x806ea    | 4         | 1.5%    |
| 0x706a1    | 4         | 1.5%    |
| 0x08701021 | 4         | 1.5%    |
| 0x806eb    | 3         | 1.13%   |
| 0x30678    | 3         | 1.13%   |
| 0x20655    | 3         | 1.13%   |
| 0x1067a    | 3         | 1.13%   |
| 0x05000119 | 3         | 1.13%   |
| 0x010000c8 | 3         | 1.13%   |
| 0x906eb    | 2         | 0.75%   |
| 0x706a8    | 2         | 0.75%   |
| 0x6fd      | 2         | 0.75%   |
| 0x6f6      | 2         | 0.75%   |
| 0x506c9    | 2         | 0.75%   |
| 0x306e4    | 2         | 0.75%   |
| 0x10676    | 2         | 0.75%   |
| 0x08600106 | 2         | 0.75%   |
| 0x08600104 | 2         | 0.75%   |
| 0x08101016 | 2         | 0.75%   |
| 0x07030105 | 2         | 0.75%   |
| 0x06001119 | 2         | 0.75%   |
| 0x06000852 | 2         | 0.75%   |
| 0xf49      | 1         | 0.38%   |
| 0xf29      | 1         | 0.38%   |
| 0xb06a2    | 1         | 0.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 41        | 16.21%  |
| Haswell          | 24        | 9.49%   |
| SandyBridge      | 23        | 9.09%   |
| IvyBridge        | 18        | 7.11%   |
| Skylake          | 16        | 6.32%   |
| Zen+             | 11        | 4.35%   |
| Unknown          | 11        | 4.35%   |
| Zen 2            | 10        | 3.95%   |
| TigerLake        | 9         | 3.56%   |
| Silvermont       | 9         | 3.56%   |
| Broadwell        | 8         | 3.16%   |
| Penryn           | 7         | 2.77%   |
| Goldmont plus    | 7         | 2.77%   |
| Piledriver       | 6         | 2.37%   |
| Core             | 6         | 2.37%   |
| Alderlake Hybrid | 5         | 1.98%   |
| Westmere         | 4         | 1.58%   |
| K10              | 4         | 1.58%   |
| IceLake          | 4         | 1.58%   |
| Excavator        | 4         | 1.58%   |
| Zen 3            | 3         | 1.19%   |
| Bobcat           | 3         | 1.19%   |
| Zen              | 2         | 0.79%   |
| Puma             | 2         | 0.79%   |
| NetBurst         | 2         | 0.79%   |
| Nehalem          | 2         | 0.79%   |
| Goldmont         | 2         | 0.79%   |
| CometLake        | 2         | 0.79%   |
| Bonnell          | 2         | 0.79%   |
| P6               | 1         | 0.4%    |
| K8 Hammer        | 1         | 0.4%    |
| K8 & K10 hybrid  | 1         | 0.4%    |
| K10 Llano        | 1         | 0.4%    |
| Jaguar           | 1         | 0.4%    |
| Bulldozer        | 1         | 0.4%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 169       | 57.48%  |
| Nvidia | 68        | 23.13%  |
| AMD    | 57        | 19.39%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 19        | 6.11%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 3.54%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 10        | 3.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9         | 2.89%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 8         | 2.57%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 2.57%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 2.57%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 2.25%   |
| Intel HD Graphics 620                                                                    | 7         | 2.25%   |
| Intel HD Graphics 5500                                                                   | 7         | 2.25%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 2.25%   |
| Intel UHD Graphics 620                                                                   | 6         | 1.93%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 1.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 1.93%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 1.61%   |
| Intel HD Graphics 530                                                                    | 5         | 1.61%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 5         | 1.61%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 4         | 1.29%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 1.29%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 4         | 1.29%   |
| Intel HD Graphics 630                                                                    | 4         | 1.29%   |
| Intel DG1 [Iris Xe MAX Graphics]                                                         | 4         | 1.29%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 1.29%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.29%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 1.29%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 3         | 0.96%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.96%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 0.96%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 0.96%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 0.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 0.96%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 0.96%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 0.96%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 0.96%   |
| Nvidia GP108M [GeForce MX230]                                                            | 2         | 0.64%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.64%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.64%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 2         | 0.64%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 0.64%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 129       | 50%     |
| 1 x AMD        | 42        | 16.28%  |
| 1 x Nvidia     | 34        | 13.18%  |
| Intel + Nvidia | 30        | 11.63%  |
| 2 x AMD        | 7         | 2.71%   |
| AMD + Nvidia   | 5         | 1.94%   |
| Other          | 4         | 1.55%   |
| 2 x Intel      | 4         | 1.55%   |
| Intel + AMD    | 3         | 1.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 216       | 83.72%  |
| Proprietary | 35        | 13.57%  |
| Unknown     | 7         | 2.71%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 165       | 62.74%  |
| 1.01-2.0   | 34        | 12.93%  |
| 0.01-0.5   | 21        | 7.98%   |
| 3.01-4.0   | 16        | 6.08%   |
| 0.51-1.0   | 15        | 5.7%    |
| 5.01-6.0   | 7         | 2.66%   |
| 7.01-8.0   | 4         | 1.52%   |
| 8.01-16.0  | 1         | 0.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 43        | 14.05%  |
| LG Display              | 31        | 10.13%  |
| Samsung Electronics     | 27        | 8.82%   |
| AOC                     | 27        | 8.82%   |
| BOE                     | 25        | 8.17%   |
| Dell                    | 23        | 7.52%   |
| Chimei Innolux          | 21        | 6.86%   |
| Hewlett-Packard         | 16        | 5.23%   |
| Goldstar                | 16        | 5.23%   |
| Apple                   | 8         | 2.61%   |
| Acer                    | 6         | 1.96%   |
| ViewSonic               | 5         | 1.63%   |
| Sony                    | 4         | 1.31%   |
| Chi Mei Optoelectronics | 4         | 1.31%   |
| BenQ                    | 4         | 1.31%   |
| AGO                     | 4         | 1.31%   |
| Panasonic               | 3         | 0.98%   |
| MSI                     | 3         | 0.98%   |
| Lenovo                  | 3         | 0.98%   |
| ASUSTek Computer        | 3         | 0.98%   |
| Ancor Communications    | 3         | 0.98%   |
| Sharp                   | 2         | 0.65%   |
| PANDA                   | 2         | 0.65%   |
| Hitachi                 | 2         | 0.65%   |
| CPT                     | 2         | 0.65%   |
| Xerox                   | 1         | 0.33%   |
| Unknown (XXX)           | 1         | 0.33%   |
| Sun                     | 1         | 0.33%   |
| RTK                     | 1         | 0.33%   |
| Royal Information       | 1         | 0.33%   |
| PRISM+                  | 1         | 0.33%   |
| Philips                 | 1         | 0.33%   |
| PAR                     | 1         | 0.33%   |
| LTM                     | 1         | 0.33%   |
| LG Philips              | 1         | 0.33%   |
| KDC                     | 1         | 0.33%   |
| ITE                     | 1         | 0.33%   |
| InnoLux Display         | 1         | 0.33%   |
| Haier                   | 1         | 0.33%   |
| GAOMON                  | 1         | 0.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Dell AW2518HF DELA102 1920x1080 544x303mm 24.5-inch                  | 6         | 1.9%    |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch               | 5         | 1.59%   |
| AOC 2370 AOC2370 1920x1080 509x286mm 23.0-inch                       | 5         | 1.59%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 4         | 1.27%   |
| AU Optronics LCD Monitor AUO35EB 3840x2160 344x193mm 15.5-inch       | 4         | 1.27%   |
| AGO LCD Monitor AGO0001 1920x1080 256x192mm 12.6-inch                | 4         | 1.27%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                   | 3         | 0.95%   |
| Goldstar HD GSM5ACD 1366x768 410x230mm 18.5-inch                     | 3         | 0.95%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 3         | 0.95%   |
| AU Optronics LCD Monitor AUO25ED 1920x1080 344x194mm 15.5-inch       | 3         | 0.95%   |
| AOC 2070W AOC2070 1600x900 434x236mm 19.4-inch                       | 3         | 0.95%   |
| Sony TV SNY1B02 1360x768                                             | 2         | 0.63%   |
| Sony TV SNY0902 1920x1080                                            | 2         | 0.63%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch | 2         | 0.63%   |
| Samsung Electronics LCD Monitor SAM0A76 1280x720 949x543mm 43.0-inch | 2         | 0.63%   |
| MSI G271 MSI3CB5 1920x1080 598x336mm 27.0-inch                       | 2         | 0.63%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch         | 2         | 0.63%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch          | 2         | 0.63%   |
| Hewlett-Packard LCD Monitor E232 2944x1080                           | 2         | 0.63%   |
| Hewlett-Packard L1908w HWP26F0 1440x900 410x256mm 19.0-inch          | 2         | 0.63%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch          | 2         | 0.63%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                 | 2         | 0.63%   |
| Dell E207WFP DELD011 1680x1050 430x270mm 20.0-inch                   | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch      | 2         | 0.63%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 2         | 0.63%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch       | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch        | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch        | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 2         | 0.63%   |
| AOC 2343 AOC2343 1920x1080 509x286mm 23.0-inch                       | 2         | 0.63%   |
| Xerox XA3-17 XER7B10 1280x1024 337x270mm 17.0-inch                   | 1         | 0.32%   |
| ViewSonic VX2778 Series VSC8432 2560x1440 597x336mm 27.0-inch        | 1         | 0.32%   |
| ViewSonic VA2359 Series VSC6332 1920x1080 509x286mm 23.0-inch        | 1         | 0.32%   |
| ViewSonic VA1703wb-2 VSCA21F 1440x900 367x230mm 17.1-inch            | 1         | 0.32%   |
| ViewSonic LCD Monitor VX2458-mhd 3286x1080                           | 1         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 105       | 36.21%  |
| 1366x768 (WXGA)    | 81        | 27.93%  |
| 3840x2160 (4K)     | 22        | 7.59%   |
| 1600x900 (HD+)     | 16        | 5.52%   |
| 1440x900 (WXGA+)   | 11        | 3.79%   |
| 1280x800 (WXGA)    | 11        | 3.79%   |
| 1280x1024 (SXGA)   | 11        | 3.79%   |
| 2560x1440 (QHD)    | 8         | 2.76%   |
| 1920x1200 (WUXGA)  | 3         | 1.03%   |
| 1680x1050 (WSXGA+) | 3         | 1.03%   |
| 1360x768           | 3         | 1.03%   |
| 3286x1080          | 2         | 0.69%   |
| 2944x1080          | 2         | 0.69%   |
| 2560x1080          | 2         | 0.69%   |
| 1280x720 (HD)      | 2         | 0.69%   |
| Unknown            | 2         | 0.69%   |
| 3840x2400          | 1         | 0.34%   |
| 3200x2000          | 1         | 0.34%   |
| 2560x1600          | 1         | 0.34%   |
| 1400x1050          | 1         | 0.34%   |
| 1280x960           | 1         | 0.34%   |
| 1024x576           | 1         | 0.34%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 82        | 26.8%   |
| 14      | 33        | 10.78%  |
| 13      | 30        | 9.8%    |
| 23      | 19        | 6.21%   |
| 24      | 17        | 5.56%   |
| 21      | 17        | 5.56%   |
| 19      | 17        | 5.56%   |
| 18      | 14        | 4.58%   |
| 17      | 13        | 4.25%   |
| 27      | 10        | 3.27%   |
| Unknown | 9         | 2.94%   |
| 12      | 6         | 1.96%   |
| 84      | 5         | 1.63%   |
| 72      | 4         | 1.31%   |
| 31      | 4         | 1.31%   |
| 20      | 4         | 1.31%   |
| 11      | 4         | 1.31%   |
| 16      | 3         | 0.98%   |
| 57      | 2         | 0.65%   |
| 43      | 2         | 0.65%   |
| 34      | 2         | 0.65%   |
| 32      | 2         | 0.65%   |
| 58      | 1         | 0.33%   |
| 54      | 1         | 0.33%   |
| 40      | 1         | 0.33%   |
| 36      | 1         | 0.33%   |
| 26      | 1         | 0.33%   |
| 22      | 1         | 0.33%   |
| 10      | 1         | 0.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 142       | 47.02%  |
| 401-500     | 48        | 15.89%  |
| 501-600     | 46        | 15.23%  |
| 201-300     | 21        | 6.95%   |
| 351-400     | 11        | 3.64%   |
| 1501-2000   | 9         | 2.98%   |
| Unknown     | 9         | 2.98%   |
| 701-800     | 6         | 1.99%   |
| 601-700     | 4         | 1.32%   |
| 1001-1500   | 3         | 0.99%   |
| 901-1000    | 2         | 0.66%   |
| 801-900     | 1         | 0.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 205       | 77.36%  |
| 16/10   | 32        | 12.08%  |
| 5/4     | 10        | 3.77%   |
| Unknown | 9         | 3.4%    |
| 4/3     | 6         | 2.26%   |
| 21/9    | 2         | 0.75%   |
| 0.56    | 1         | 0.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 81        | 26.56%  |
| 81-90          | 59        | 19.34%  |
| 201-250        | 40        | 13.11%  |
| 151-200        | 27        | 8.85%   |
| 141-150        | 18        | 5.9%    |
| More than 1000 | 13        | 4.26%   |
| 301-350        | 10        | 3.28%   |
| 251-300        | 10        | 3.28%   |
| Unknown        | 9         | 2.95%   |
| 351-500        | 8         | 2.62%   |
| 71-80          | 7         | 2.3%    |
| 121-130        | 5         | 1.64%   |
| 51-60          | 4         | 1.31%   |
| 111-120        | 4         | 1.31%   |
| 501-1000       | 4         | 1.31%   |
| 61-70          | 2         | 0.66%   |
| 131-140        | 2         | 0.66%   |
| 41-50          | 1         | 0.33%   |
| 91-100         | 1         | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 97        | 32.77%  |
| 51-100        | 92        | 31.08%  |
| 121-160       | 69        | 23.31%  |
| 1-50          | 11        | 3.72%   |
| More than 240 | 9         | 3.04%   |
| 161-240       | 9         | 3.04%   |
| Unknown       | 9         | 3.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 193       | 72.83%  |
| 2     | 60        | 22.64%  |
| 0     | 8         | 3.02%   |
| 3     | 4         | 1.51%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 152       | 38.78%  |
| Intel                           | 103       | 26.28%  |
| Qualcomm Atheros                | 51        | 13.01%  |
| Broadcom                        | 30        | 7.65%   |
| TP-Link                         | 11        | 2.81%   |
| Broadcom Limited                | 8         | 2.04%   |
| Nvidia                          | 4         | 1.02%   |
| MediaTek                        | 4         | 1.02%   |
| Xiaomi                          | 3         | 0.77%   |
| Ralink                          | 3         | 0.77%   |
| Huawei Technologies             | 3         | 0.77%   |
| Ralink Technology               | 2         | 0.51%   |
| Microchip Technology            | 2         | 0.51%   |
| Linksys                         | 2         | 0.51%   |
| D-Link                          | 2         | 0.51%   |
| ASIX Electronics                | 2         | 0.51%   |
| Standard Microsystems           | 1         | 0.26%   |
| Qualcomm Atheros Communications | 1         | 0.26%   |
| Marvell Technology Group        | 1         | 0.26%   |
| Lenovo                          | 1         | 0.26%   |
| JMicron Technology              | 1         | 0.26%   |
| Hewlett-Packard                 | 1         | 0.26%   |
| DisplayLink                     | 1         | 0.26%   |
| Dell                            | 1         | 0.26%   |
| Davicom Semiconductor           | 1         | 0.26%   |
| Aquantia                        | 1         | 0.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 91        | 19.4%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 27        | 5.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 14        | 2.99%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 11        | 2.35%   |
| Intel Wireless 7265                                               | 9         | 1.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 1.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 8         | 1.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 8         | 1.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7         | 1.49%   |
| Intel Wireless 7260                                               | 7         | 1.49%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 1.49%   |
| Intel Wi-Fi 6 AX200                                               | 7         | 1.49%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 6         | 1.28%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 1.28%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 5         | 1.07%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 1.07%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 5         | 1.07%   |
| Intel Ethernet Controller I225-V                                  | 5         | 1.07%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 1.07%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 5         | 1.07%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 1.07%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 4         | 0.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.85%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 4         | 0.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 0.85%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 4         | 0.85%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.64%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                         | 3         | 0.64%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 0.64%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 3         | 0.64%   |
| Realtek 802.11ac NIC                                              | 3         | 0.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 0.64%   |
| Intel Wireless-AC 9260                                            | 3         | 0.64%   |
| Intel Wireless 8265 / 8275                                        | 3         | 0.64%   |
| Intel Wireless 8260                                               | 3         | 0.64%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.64%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.64%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.64%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 78        | 36.45%  |
| Realtek Semiconductor           | 44        | 20.56%  |
| Qualcomm Atheros                | 39        | 18.22%  |
| Broadcom                        | 21        | 9.81%   |
| TP-Link                         | 11        | 5.14%   |
| Broadcom Limited                | 7         | 3.27%   |
| Ralink                          | 3         | 1.4%    |
| MediaTek                        | 3         | 1.4%    |
| Ralink Technology               | 2         | 0.93%   |
| Linksys                         | 2         | 0.93%   |
| D-Link                          | 2         | 0.93%   |
| Qualcomm Atheros Communications | 1         | 0.47%   |
| Dell                            | 1         | 0.47%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 11        | 5.07%   |
| Intel Wireless 7265                                            | 9         | 4.15%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 8         | 3.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 8         | 3.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 7         | 3.23%   |
| Intel Wireless 7260                                            | 7         | 3.23%   |
| Intel Wi-Fi 6 AX201                                            | 7         | 3.23%   |
| Intel Wi-Fi 6 AX200                                            | 7         | 3.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 6         | 2.76%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 6         | 2.76%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 5         | 2.3%    |
| Broadcom BCM4331 802.11a/b/g/n                                 | 5         | 2.3%    |
| Broadcom BCM43142 802.11b/g/n                                  | 5         | 2.3%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 4         | 1.84%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 1.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 1.84%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 1.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 4         | 1.84%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 4         | 1.84%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                      | 3         | 1.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3         | 1.38%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 3         | 1.38%   |
| Realtek 802.11ac NIC                                           | 3         | 1.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3         | 1.38%   |
| Intel Wireless-AC 9260                                         | 3         | 1.38%   |
| Intel Wireless 8265 / 8275                                     | 3         | 1.38%   |
| Intel Wireless 8260                                            | 3         | 1.38%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 1.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 1.38%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 0.92%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller      | 2         | 0.92%   |
| Ralink MT7601U Wireless Adapter                                | 2         | 0.92%   |
| Intel Wireless 3165                                            | 2         | 0.92%   |
| Intel Wireless 3160                                            | 2         | 0.92%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 0.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 0.92%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 0.92%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 0.92%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 2         | 0.92%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 0.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 135       | 56.02%  |
| Intel                    | 51        | 21.16%  |
| Broadcom                 | 17        | 7.05%   |
| Qualcomm Atheros         | 15        | 6.22%   |
| Nvidia                   | 4         | 1.66%   |
| Xiaomi                   | 3         | 1.24%   |
| Huawei Technologies      | 3         | 1.24%   |
| Microchip Technology     | 2         | 0.83%   |
| ASIX Electronics         | 2         | 0.83%   |
| Standard Microsystems    | 1         | 0.41%   |
| MediaTek                 | 1         | 0.41%   |
| Marvell Technology Group | 1         | 0.41%   |
| Lenovo                   | 1         | 0.41%   |
| JMicron Technology       | 1         | 0.41%   |
| DisplayLink              | 1         | 0.41%   |
| Davicom Semiconductor    | 1         | 0.41%   |
| Broadcom Limited         | 1         | 0.41%   |
| Aquantia                 | 1         | 0.41%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 91        | 36.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 27        | 10.76%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 14        | 5.58%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 3.59%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 1.99%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 5         | 1.99%   |
| Intel Ethernet Controller I225-V                                  | 5         | 1.99%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 1.99%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 1.2%    |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.2%    |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.2%    |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.2%    |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.2%    |
| Intel 82579V Gigabit Network Connection                           | 3         | 1.2%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 3         | 1.2%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.8%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 0.8%    |
| Nvidia MCP79 Ethernet                                             | 2         | 0.8%    |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 2         | 0.8%    |
| Intel I211 Gigabit Network Connection                             | 2         | 0.8%    |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.8%    |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.8%    |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.8%    |
| Huawei MAR-LX1M                                                   | 2         | 0.8%    |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 2         | 0.8%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 0.8%    |
| Standard Microsystems Ethernet controller                         | 1         | 0.4%    |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.4%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 0.4%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.4%    |
| Realtek PCIe GbE Family Controller                                | 1         | 0.4%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.4%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.4%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.4%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.4%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.4%    |
| Nvidia MCP67 Ethernet                                             | 1         | 0.4%    |
| Nvidia MCP61 Ethernet                                             | 1         | 0.4%    |
| MediaTek X55                                                      | 1         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 224       | 52.34%  |
| WiFi     | 203       | 47.43%  |
| Modem    | 1         | 0.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 147       | 55.47%  |
| Ethernet | 118       | 44.53%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 158       | 61.48%  |
| 1     | 84        | 32.68%  |
| 3     | 7         | 2.72%   |
| 0     | 7         | 2.72%   |
| 4     | 1         | 0.39%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 249       | 97.27%  |
| Yes  | 7         | 2.73%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 64        | 41.56%  |
| Realtek Semiconductor           | 20        | 12.99%  |
| Qualcomm Atheros Communications | 18        | 11.69%  |
| Cambridge Silicon Radio         | 11        | 7.14%   |
| Broadcom                        | 10        | 6.49%   |
| Apple                           | 8         | 5.19%   |
| Lite-On Technology              | 4         | 2.6%    |
| IMC Networks                    | 4         | 2.6%    |
| Toshiba                         | 3         | 1.95%   |
| Foxconn / Hon Hai               | 3         | 1.95%   |
| ASUSTek Computer                | 3         | 1.95%   |
| Hewlett-Packard                 | 2         | 1.3%    |
| Realtek                         | 1         | 0.65%   |
| MediaTek                        | 1         | 0.65%   |
| Marvell Semiconductor           | 1         | 0.65%   |
| Dell                            | 1         | 0.65%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 24        | 15.58%  |
| Realtek Bluetooth Radio                             | 11        | 7.14%   |
| Qualcomm Atheros  Bluetooth Device                  | 11        | 7.14%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 11        | 7.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 10        | 6.49%   |
| Intel AX201 Bluetooth                               | 10        | 6.49%   |
| Realtek  Bluetooth 4.2 Adapter                      | 7         | 4.55%   |
| Intel AX200 Bluetooth                               | 7         | 4.55%   |
| Apple Bluetooth Host Controller                     | 5         | 3.25%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 2.6%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.95%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 1.95%   |
| Intel Bluetooth Device                              | 3         | 1.95%   |
| Broadcom HP Portable SoftSailing                    | 3         | 1.95%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 3         | 1.95%   |
| Toshiba Bluetooth Device                            | 2         | 1.3%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 1.3%    |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.3%    |
| Intel AX210 Bluetooth                               | 2         | 1.3%    |
| IMC Networks Bluetooth Radio                        | 2         | 1.3%    |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 1.3%    |
| Apple Bluetooth USB Host Controller                 | 2         | 1.3%    |
| Toshiba BCM43142A0                                  | 1         | 0.65%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.65%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 0.65%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 0.65%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.65%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.65%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.65%   |
| MediaTek Wireless_Device                            | 1         | 0.65%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 0.65%   |
| Lite-On Wireless_Device                             | 1         | 0.65%   |
| Lite-On Bluetooth Device                            | 1         | 0.65%   |
| IMC Networks Wireless_Device                        | 1         | 0.65%   |
| IMC Networks Bluetooth                              | 1         | 0.65%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.65%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.65%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.65%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1         | 0.65%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 0.65%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 193       | 55.78%  |
| AMD                     | 63        | 18.21%  |
| Nvidia                  | 51        | 14.74%  |
| C-Media Electronics     | 6         | 1.73%   |
| Logitech                | 3         | 0.87%   |
| GN Netcom               | 3         | 0.87%   |
| Generalplus Technology  | 3         | 0.87%   |
| Unknown                 | 2         | 0.58%   |
| Sony                    | 2         | 0.58%   |
| Realtek Semiconductor   | 2         | 0.58%   |
| Plantronics             | 2         | 0.58%   |
| JMTek                   | 2         | 0.58%   |
| Soundprese              | 1         | 0.29%   |
| Medeli Electronics      | 1         | 0.29%   |
| Lenovo                  | 1         | 0.29%   |
| Ensoniq                 | 1         | 0.29%   |
| DCMT Technology         | 1         | 0.29%   |
| Creative Labs           | 1         | 0.29%   |
| Corsair                 | 1         | 0.29%   |
| CMX Systems             | 1         | 0.29%   |
| Blue Microphones        | 1         | 0.29%   |
| BEHRINGER International | 1         | 0.29%   |
| Astro Gaming            | 1         | 0.29%   |
| Argosy Research         | 1         | 0.29%   |
| Afatech                 | 1         | 0.29%   |
| A-DATA Technology       | 1         | 0.29%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 21        | 5.11%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 21        | 5.11%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 20        | 4.87%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 18        | 4.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 14        | 3.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 13        | 3.16%   |
| Intel Cannon Lake PCH cAVS                                                                        | 11        | 2.68%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 11        | 2.68%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 10        | 2.43%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10        | 2.43%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 9         | 2.19%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 2.19%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 8         | 1.95%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 8         | 1.95%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 1.95%   |
| Intel Broadwell-U Audio Controller                                                                | 8         | 1.95%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 1.95%   |
| AMD FCH Azalia Controller                                                                         | 8         | 1.95%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 1.7%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 1.7%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 7         | 1.7%    |
| Intel 200 Series PCH HD Audio                                                                     | 6         | 1.46%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 1.46%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.22%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 1.22%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 5         | 1.22%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 0.97%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 0.97%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4         | 0.97%   |
| Nvidia Audio device                                                                               | 4         | 0.97%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 0.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 0.97%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 0.97%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 0.97%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 4         | 0.97%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3         | 0.73%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.73%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.73%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.73%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 3         | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 41        | 22.53%  |
| SK hynix            | 28        | 15.38%  |
| Micron Technology   | 25        | 13.74%  |
| Kingston            | 24        | 13.19%  |
| Crucial             | 15        | 8.24%   |
| A-DATA Technology   | 9         | 4.95%   |
| Unknown             | 8         | 4.4%    |
| Corsair             | 8         | 4.4%    |
| Nanya Technology    | 5         | 2.75%   |
| Team                | 4         | 2.2%    |
| G.Skill             | 4         | 2.2%    |
| Ramaxel Technology  | 2         | 1.1%    |
| Patriot             | 2         | 1.1%    |
| V-Color             | 1         | 0.55%   |
| Unknown (ABCD)      | 1         | 0.55%   |
| Transcend           | 1         | 0.55%   |
| Super Talent        | 1         | 0.55%   |
| Kimtigo             | 1         | 0.55%   |
| fef5                | 1         | 0.55%   |
| Unknown             | 1         | 0.55%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s              | 5         | 2.43%   |
| Team RAM TEAMGROUP-SD4-2666 32GB SODIMM DDR4 2667MT/s            | 4         | 1.94%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 1.94%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s      | 4         | 1.94%   |
| Corsair RAM Module 8GB SODIMM DDR3 1333MT/s                      | 4         | 1.94%   |
| Corsair RAM Module 4GB SODIMM DDR3 1333MT/s                      | 4         | 1.94%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 3         | 1.46%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.46%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 3         | 1.46%   |
| Kingston RAM 9905584-015.A00LF 4GB DIMM DDR3 1600MT/s            | 3         | 1.46%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 2         | 0.97%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.97%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.97%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.97%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.97%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.97%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.97%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.97%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.97%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.97%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.97%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.97%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 2         | 0.97%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 0.97%   |
| Kingston RAM 9905402-174.A00G 4GB DIMM DDR3 1600MT/s             | 2         | 0.97%   |
| Crucial RAM CT32G4SFD832A.M16FF 32GB SODIMM DDR4 3200MT/s        | 2         | 0.97%   |
| A-DATA RAM Module 16GB DIMM DDR4 2667MT/s                        | 2         | 0.97%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                      | 2         | 0.97%   |
| V-Color RAM TN4G8C11-H11 4GB DIMM DDR3 1600MT/s                  | 1         | 0.49%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                      | 1         | 0.49%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 1         | 0.49%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 0.49%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.49%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.49%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 0.49%   |
| Unknown RAM 3600 C18 Series 16GB DIMM DDR4 2933MT/s              | 1         | 0.49%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.49%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM DDR3 1334MT/s              | 1         | 0.49%   |
| Super Talent RAM SUPERTALENT02 8GB SODIMM DDR3 1600MT/s          | 1         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 66        | 44%     |
| DDR3    | 59        | 39.33%  |
| LPDDR4  | 8         | 5.33%   |
| SDRAM   | 5         | 3.33%   |
| DDR5    | 4         | 2.67%   |
| DDR2    | 4         | 2.67%   |
| Unknown | 2         | 1.33%   |
| LPDDR5  | 1         | 0.67%   |
| LPDDR3  | 1         | 0.67%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 96        | 65.31%  |
| DIMM         | 40        | 27.21%  |
| Row Of Chips | 9         | 6.12%   |
| Chip         | 1         | 0.68%   |
| Unknown      | 1         | 0.68%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 61        | 35.88%  |
| 8192  | 60        | 35.29%  |
| 16384 | 21        | 12.35%  |
| 2048  | 14        | 8.24%   |
| 32768 | 12        | 7.06%   |
| 1024  | 2         | 1.18%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 43        | 24.71%  |
| 2667    | 30        | 17.24%  |
| 3200    | 16        | 9.2%    |
| 1333    | 13        | 7.47%   |
| 2400    | 9         | 5.17%   |
| 2133    | 7         | 4.02%   |
| 1334    | 7         | 4.02%   |
| 3600    | 5         | 2.87%   |
| 667     | 5         | 2.87%   |
| 4267    | 4         | 2.3%    |
| 3266    | 4         | 2.3%    |
| 2933    | 4         | 2.3%    |
| 4800    | 3         | 1.72%   |
| Unknown | 3         | 1.72%   |
| 4199    | 2         | 1.15%   |
| 1867    | 2         | 1.15%   |
| 1067    | 2         | 1.15%   |
| 8400    | 1         | 0.57%   |
| 6400    | 1         | 0.57%   |
| 5600    | 1         | 0.57%   |
| 3866    | 1         | 0.57%   |
| 3666    | 1         | 0.57%   |
| 3466    | 1         | 0.57%   |
| 3400    | 1         | 0.57%   |
| 3100    | 1         | 0.57%   |
| 2934    | 1         | 0.57%   |
| 2800    | 1         | 0.57%   |
| 2666    | 1         | 0.57%   |
| 2465    | 1         | 0.57%   |
| 2448    | 1         | 0.57%   |
| 1866    | 1         | 0.57%   |
| 1800    | 1         | 0.57%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 3         | 37.5%   |
| Hewlett-Packard | 3         | 37.5%   |
| Canon           | 2         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seiko Epson L382 Series            | 1         | 12.5%   |
| Seiko Epson L360 Series            | 1         | 12.5%   |
| Seiko Epson L3110 Series           | 1         | 12.5%   |
| HP DeskJet 2620 All-in-One Printer | 1         | 12.5%   |
| HP DeskJet 2130 series             | 1         | 12.5%   |
| HP Deskjet 2050 J510               | 1         | 12.5%   |
| Canon G2000 series                 | 1         | 12.5%   |
| Canon E400 series                  | 1         | 12.5%   |

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
| Chicony Electronics                    | 34        | 19.1%   |
| Microdia                               | 21        | 11.8%   |
| Realtek Semiconductor                  | 17        | 9.55%   |
| IMC Networks                           | 15        | 8.43%   |
| Sunplus Innovation Technology          | 14        | 7.87%   |
| Logitech                               | 9         | 5.06%   |
| Apple                                  | 9         | 5.06%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 3.93%   |
| Quanta                                 | 6         | 3.37%   |
| Microsoft                              | 5         | 2.81%   |
| Primax Electronics                     | 4         | 2.25%   |
| Lite-On Technology                     | 4         | 2.25%   |
| Bison Electronics                      | 4         | 2.25%   |
| Suyin                                  | 3         | 1.69%   |
| Alcor Micro                            | 3         | 1.69%   |
| Z-Star Microelectronics                | 2         | 1.12%   |
| Syntek                                 | 2         | 1.12%   |
| Silicon Motion                         | 2         | 1.12%   |
| Luxvisions Innotech Limited            | 2         | 1.12%   |
| Acer                                   | 2         | 1.12%   |
| TANDBERG                               | 1         | 0.56%   |
| Sonix Technology                       | 1         | 0.56%   |
| Samsung Electronics                    | 1         | 0.56%   |
| Philips (or NXP)                       | 1         | 0.56%   |
| LG Electronics                         | 1         | 0.56%   |
| Jieli Technology                       | 1         | 0.56%   |
| Importek                               | 1         | 0.56%   |
| Huawei Technologies                    | 1         | 0.56%   |
| GEMBIRD                                | 1         | 0.56%   |
| Creative Technology                    | 1         | 0.56%   |
| Aveo Technology                        | 1         | 0.56%   |
| Arkmicro Technologies                  | 1         | 0.56%   |
| Alpha Imaging Technology               | 1         | 0.56%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                    | 12        | 6.59%   |
| Chicony Integrated Camera                        | 9         | 4.95%   |
| Realtek Integrated_Webcam_HD                     | 7         | 3.85%   |
| Sunplus HD WebCam                                | 5         | 2.75%   |
| IMC Networks Integrated Camera                   | 5         | 2.75%   |
| Apple FaceTime HD Camera                         | 5         | 2.75%   |
| Sunplus Integrated_Webcam_HD                     | 4         | 2.2%    |
| Primax HP HD Webcam [Fixed]                      | 3         | 1.65%   |
| Microsoft LifeCam HD-3000                        | 3         | 1.65%   |
| Microdia Integrated Camera                       | 3         | 1.65%   |
| Logitech Webcam C270                             | 3         | 1.65%   |
| IMC Networks USB2.0 HD UVC WebCam                | 3         | 1.65%   |
| Chicony TOSHIBA Web Camera - HD                  | 3         | 1.65%   |
| Syntek EasyCamera                                | 2         | 1.1%    |
| Sunplus HP HD Webcam [Fixed]                     | 2         | 1.1%    |
| Realtek USB Camera                               | 2         | 1.1%    |
| Realtek Integrated Webcam HD                     | 2         | 1.1%    |
| Realtek Integrated Webcam                        | 2         | 1.1%    |
| Quanta HP TrueVision HD Camera                   | 2         | 1.1%    |
| Quanta HD WebCam                                 | 2         | 1.1%    |
| Microdia USB 2.0 Camera                          | 2         | 1.1%    |
| Microdia Integrated Webcam                       | 2         | 1.1%    |
| Lite-On TOSHIBA Web Camera - HD                  | 2         | 1.1%    |
| IMC Networks USB2.0 VGA UVC WebCam               | 2         | 1.1%    |
| Chicony USB 2.0 Camera                           | 2         | 1.1%    |
| Chicony Integrated HP HD Webcam                  | 2         | 1.1%    |
| Chicony HP Truevision HD                         | 2         | 1.1%    |
| Chicony HP HD Webcam                             | 2         | 1.1%    |
| Chicony HP HD Camera                             | 2         | 1.1%    |
| Chicony 720p HD Camera                           | 2         | 1.1%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 2         | 1.1%    |
| Alcor Micro USB 2.0 Camera                       | 2         | 1.1%    |
| Z-Star Vega USB2.0 Camera                        | 1         | 0.55%   |
| Z-Star A4 TECH USB2.0 PC Camera E                | 1         | 0.55%   |
| TANDBERG PrecisionHD Camera                      | 1         | 0.55%   |
| Suyin TOSHIBA Web Camera - HD                    | 1         | 0.55%   |
| Suyin HP TrueVision HD                           | 1         | 0.55%   |
| Suyin 1.3M HD WebCam                             | 1         | 0.55%   |
| Sunplus Laptop_Integrated_Webcam_HD              | 1         | 0.55%   |
| Sunplus Integrated Camera                        | 1         | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 16        | 50%     |
| Synaptics                  | 7         | 21.88%  |
| Shenzhen Goodix Technology | 3         | 9.38%   |
| Upek                       | 1         | 3.13%   |
| STMicroelectronics         | 1         | 3.13%   |
| Samsung Electronics        | 1         | 3.13%   |
| LighTuning Technology      | 1         | 3.13%   |
| Elan Microelectronics      | 1         | 3.13%   |
| AuthenTec                  | 1         | 3.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 4         | 12.5%   |
| Validity Sensors VFS491                                | 3         | 9.38%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 3         | 9.38%   |
| Shenzhen Goodix  FingerPrint Device                    | 3         | 9.38%   |
| Validity Sensors VFS471 Fingerprint Reader             | 2         | 6.25%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 2         | 6.25%   |
| Validity Sensors Synaptics WBDI                        | 2         | 6.25%   |
| Synaptics WBDI                                         | 2         | 6.25%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 2         | 6.25%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 3.13%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 3.13%   |
| Validity Sensors Fingerprint scanner                   | 1         | 3.13%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 3.13%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 3.13%   |
| Samsung Fingerprint Device                             | 1         | 3.13%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 3.13%   |
| Elan ELAN:ARM-M4                                       | 1         | 3.13%   |
| AuthenTec AES1600                                      | 1         | 3.13%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Broadcom                   | 4         | 28.57%  |
| Athena Smartcard Solutions | 4         | 28.57%  |
| O2 Micro                   | 3         | 21.43%  |
| SCM Microsystems           | 1         | 7.14%   |
| OmniKey                    | 1         | 7.14%   |
| Alcor Micro                | 1         | 7.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Athena Smartcard Solutions ASEDrive CCID                                     | 4         | 28.57%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 14.29%  |
| Broadcom 5880                                                                | 2         | 14.29%  |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 7.14%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 7.14%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 7.14%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 7.14%   |
| Broadcom 58200                                                               | 1         | 7.14%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 7.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 177       | 67.56%  |
| 1     | 71        | 27.1%   |
| 2     | 9         | 3.44%   |
| 3     | 5         | 1.91%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 31        | 30.39%  |
| Graphics card            | 23        | 22.55%  |
| Net/wireless             | 21        | 20.59%  |
| Chipcard                 | 11        | 10.78%  |
| Communication controller | 4         | 3.92%   |
| Sound                    | 2         | 1.96%   |
| Multimedia controller    | 2         | 1.96%   |
| Unassigned class         | 1         | 0.98%   |
| Storage                  | 1         | 0.98%   |
| Network                  | 1         | 0.98%   |
| Net/ethernet             | 1         | 0.98%   |
| Firewire controller      | 1         | 0.98%   |
| Card reader              | 1         | 0.98%   |
| Camera                   | 1         | 0.98%   |
| Bluetooth                | 1         | 0.98%   |


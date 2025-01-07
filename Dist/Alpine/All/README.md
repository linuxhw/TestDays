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

Total: 360

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | 0HR330                      | Desktop     | [b0a5f47c54](https://linux-hardware.org/?probe=b0a5f47c54) | Dec 30, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [face1f6c37](https://linux-hardware.org/?probe=face1f6c37) | Dec 25, 2024 |
| MSI           | Creator 15 A11UE            | Notebook    | [9beee8397d](https://linux-hardware.org/?probe=9beee8397d) | Dec 23, 2024 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [53bab82fae](https://linux-hardware.org/?probe=53bab82fae) | Dec 10, 2024 |
| Dell          | Inspiron 14 Plus 7440       | Notebook    | [b0c9087a18](https://linux-hardware.org/?probe=b0c9087a18) | Dec 08, 2024 |
| Dell          | Inspiron 14 Plus 7440       | Notebook    | [253c2d74fb](https://linux-hardware.org/?probe=253c2d74fb) | Dec 08, 2024 |
| Unknown       | Unknown                     | Desktop     | [d58ff3bf72](https://linux-hardware.org/?probe=d58ff3bf72) | Dec 07, 2024 |
| Unknown       | Unknown                     | Desktop     | [722fa16afd](https://linux-hardware.org/?probe=722fa16afd) | Dec 07, 2024 |
| Lenovo        | ThinkPad T400 27658JG       | Notebook    | [0e628ec7f3](https://linux-hardware.org/?probe=0e628ec7f3) | Dec 06, 2024 |
| Lenovo        | ThinkPad T400 27658JG       | Notebook    | [19da4f0a7b](https://linux-hardware.org/?probe=19da4f0a7b) | Dec 06, 2024 |
| Lenovo        | ThinkPad X1 Yoga 4th 20S... | Convertible | [a56dabb4f0](https://linux-hardware.org/?probe=a56dabb4f0) | Dec 02, 2024 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [413b02dc7a](https://linux-hardware.org/?probe=413b02dc7a) | Nov 25, 2024 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [21f300941c](https://linux-hardware.org/?probe=21f300941c) | Nov 20, 2024 |
| HPE           | ProLiant DL380 Gen10        | Server      | [b6af75aff4](https://linux-hardware.org/?probe=b6af75aff4) | Nov 18, 2024 |
| Google        | Kefka                       | Notebook    | [bf5cd8a623](https://linux-hardware.org/?probe=bf5cd8a623) | Nov 12, 2024 |
| Google        | Kefka                       | Notebook    | [affed9dd1e](https://linux-hardware.org/?probe=affed9dd1e) | Nov 12, 2024 |
| HP            | 8053                        | Desktop     | [b08855c6d0](https://linux-hardware.org/?probe=b08855c6d0) | Nov 07, 2024 |
| Sony          | VPCEC3A4E                   | Notebook    | [6a6d904b6a](https://linux-hardware.org/?probe=6a6d904b6a) | Nov 01, 2024 |
| Lenovo        | V15 G3 IAP 82TT             | Notebook    | [bdb953f731](https://linux-hardware.org/?probe=bdb953f731) | Oct 29, 2024 |
| HP            | EliteBook 820 G2            | Notebook    | [648ab7b15f](https://linux-hardware.org/?probe=648ab7b15f) | Oct 29, 2024 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [50274618bd](https://linux-hardware.org/?probe=50274618bd) | Oct 25, 2024 |
| Dell          | XPS 13 7390                 | Notebook    | [4bc8b23ee8](https://linux-hardware.org/?probe=4bc8b23ee8) | Oct 13, 2024 |
| ASUSTek       | F5SL                        | Notebook    | [8b5218d324](https://linux-hardware.org/?probe=8b5218d324) | Oct 12, 2024 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [0ae2204768](https://linux-hardware.org/?probe=0ae2204768) | Oct 10, 2024 |
| Gateway       | MD7811U                     | Notebook    | [7df8e45ea9](https://linux-hardware.org/?probe=7df8e45ea9) | Oct 03, 2024 |
| Gateway       | MD7811U                     | Notebook    | [23ddfbc0e6](https://linux-hardware.org/?probe=23ddfbc0e6) | Oct 03, 2024 |
| Microsoft     | Surface Pro 2               | Tablet      | [7517c14706](https://linux-hardware.org/?probe=7517c14706) | Sep 29, 2024 |
| Loongson      | 3A6000-HV-7A2000-1w-V0.1... | Desktop     | [b50072f24a](https://linux-hardware.org/?probe=b50072f24a) | Sep 23, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [78febce1fa](https://linux-hardware.org/?probe=78febce1fa) | Sep 21, 2024 |
| HP            | Stream 7 Tablet             | Tablet      | [bd41d30e3b](https://linux-hardware.org/?probe=bd41d30e3b) | Sep 21, 2024 |
| HP            | Stream 7 Tablet             | Tablet      | [3263b88e56](https://linux-hardware.org/?probe=3263b88e56) | Sep 21, 2024 |
| HP            | 0ACCh                       | Desktop     | [55a1298155](https://linux-hardware.org/?probe=55a1298155) | Sep 19, 2024 |
| HP            | EliteBook 840 G1            | Notebook    | [cb3d0e7a13](https://linux-hardware.org/?probe=cb3d0e7a13) | Sep 06, 2024 |
| Inventec      | DQ Class A02                | Desktop     | [f02f65b629](https://linux-hardware.org/?probe=f02f65b629) | Sep 06, 2024 |
| Fujitsu       | D3183-A1 S26361-D3183-A1    | Desktop     | [27f36952e8](https://linux-hardware.org/?probe=27f36952e8) | Aug 25, 2024 |
| Fujitsu       | D3183-A1 S26361-D3183-A1    | Desktop     | [444f676cab](https://linux-hardware.org/?probe=444f676cab) | Aug 25, 2024 |
| Lenovo        | ThinkPad T480 20L6S0WY00    | Notebook    | [c99c4f1732](https://linux-hardware.org/?probe=c99c4f1732) | Aug 25, 2024 |
| Dell          | Inspiron 5547               | Notebook    | [75994d1146](https://linux-hardware.org/?probe=75994d1146) | Aug 18, 2024 |
| Lenovo        | ThinkPad T480 20L6S0WY00    | Notebook    | [2b23906005](https://linux-hardware.org/?probe=2b23906005) | Aug 15, 2024 |
| Samsung       | 100NZC                      | Notebook    | [866404351e](https://linux-hardware.org/?probe=866404351e) | Aug 15, 2024 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [673e7d713c](https://linux-hardware.org/?probe=673e7d713c) | Aug 11, 2024 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [e5ed694576](https://linux-hardware.org/?probe=e5ed694576) | Aug 11, 2024 |
| Fujitsu       | D3183-A1 S26361-D3183-A1    | Desktop     | [76144977df](https://linux-hardware.org/?probe=76144977df) | Aug 08, 2024 |
| Fujitsu       | D3183-A1 S26361-D3183-A1    | Desktop     | [716c1dd778](https://linux-hardware.org/?probe=716c1dd778) | Aug 06, 2024 |
| Acer          | Nitro AN517-51              | Notebook    | [680a0fc9bd](https://linux-hardware.org/?probe=680a0fc9bd) | Aug 05, 2024 |
| Dell          | Cherry Trail CR A00         | Mini pc     | [c7ddd015c2](https://linux-hardware.org/?probe=c7ddd015c2) | Jul 30, 2024 |
| Lenovo        | ThinkPad T480 20L6S0WY00    | Notebook    | [41c870c893](https://linux-hardware.org/?probe=41c870c893) | Jul 26, 2024 |
| Unknown       | Unknown                     | Desktop     | [8be7f502c9](https://linux-hardware.org/?probe=8be7f502c9) | Jul 13, 2024 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [b9b8467b56](https://linux-hardware.org/?probe=b9b8467b56) | Jul 12, 2024 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [c583344cb5](https://linux-hardware.org/?probe=c583344cb5) | Jul 10, 2024 |
| Intel         | NUC13ANBi7 N13084-202       | Mini pc     | [d4a67ed5a8](https://linux-hardware.org/?probe=d4a67ed5a8) | Jul 08, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [1fb3302507](https://linux-hardware.org/?probe=1fb3302507) | Jul 08, 2024 |
| HP            | Laptop 15-bs0xx             | Notebook    | [e7d34a0b87](https://linux-hardware.org/?probe=e7d34a0b87) | Jul 08, 2024 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [7a92877b6b](https://linux-hardware.org/?probe=7a92877b6b) | Jul 07, 2024 |
| Dell          | Inspiron 1545               | Notebook    | [16a84d453a](https://linux-hardware.org/?probe=16a84d453a) | Jul 05, 2024 |
| Dell          | Inspiron 1545               | Notebook    | [57f7d3d2e8](https://linux-hardware.org/?probe=57f7d3d2e8) | Jul 04, 2024 |
| Dell          | Inspiron 5575               | Notebook    | [7e022ade86](https://linux-hardware.org/?probe=7e022ade86) | Jul 01, 2024 |
| HP            | ProBook 450 G7              | Notebook    | [f45e2bd9fe](https://linux-hardware.org/?probe=f45e2bd9fe) | Jun 26, 2024 |
| Dell          | Inspiron 14 Plus 7440       | Notebook    | [103438691e](https://linux-hardware.org/?probe=103438691e) | Jun 17, 2024 |
| Dell          | Inspiron N5110              | Notebook    | [110790c81a](https://linux-hardware.org/?probe=110790c81a) | Jun 14, 2024 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [4e3f98ce9b](https://linux-hardware.org/?probe=4e3f98ce9b) | Jun 12, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [8d3c1d6921](https://linux-hardware.org/?probe=8d3c1d6921) | Jun 11, 2024 |
| HP            | EliteBook 2560p             | Notebook    | [08989abc4e](https://linux-hardware.org/?probe=08989abc4e) | Jun 09, 2024 |
| HP            | EliteBook 2560p             | Notebook    | [a8eb359b6e](https://linux-hardware.org/?probe=a8eb359b6e) | Jun 09, 2024 |
| Dell          | 007MXD A00                  | Mini pc     | [ba0b743aa4](https://linux-hardware.org/?probe=ba0b743aa4) | Jun 05, 2024 |
| Toshiba       | Satellite M50Dt-A           | Notebook    | [40c29073b1](https://linux-hardware.org/?probe=40c29073b1) | May 31, 2024 |
| Sony          | VPCEC3A4E                   | Notebook    | [7cbeb425cf](https://linux-hardware.org/?probe=7cbeb425cf) | May 31, 2024 |
| Inventec      | D CLASS A02                 | Desktop     | [1bfbba2797](https://linux-hardware.org/?probe=1bfbba2797) | May 28, 2024 |
| Lenovo        | ThinkPad T480 20L6S0WY00    | Notebook    | [c84cce1d60](https://linux-hardware.org/?probe=c84cce1d60) | May 26, 2024 |
| Lenovo        | ThinkPad T480 20L6S0WY00    | Notebook    | [7d2a37b22b](https://linux-hardware.org/?probe=7d2a37b22b) | May 26, 2024 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [41b5caad82](https://linux-hardware.org/?probe=41b5caad82) | May 26, 2024 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | Desktop     | [acdb0e0544](https://linux-hardware.org/?probe=acdb0e0544) | May 25, 2024 |
| Inventec      | D CLASS A02                 | Desktop     | [50cec6d29b](https://linux-hardware.org/?probe=50cec6d29b) | May 12, 2024 |
| Fujitsu       | D3183-A1 S26361-D3183-A1    | Desktop     | [553927672a](https://linux-hardware.org/?probe=553927672a) | May 11, 2024 |
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
| Dell          | Inspiron 14 Plus 7440       | Notebook    | [9b975edbf7](https://linux-hardware.org/?probe=9b975edbf7) | Mar 23, 2024 |
| Inventec      | DQ Class A02                | Desktop     | [6539e1cbe7](https://linux-hardware.org/?probe=6539e1cbe7) | Mar 22, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [2c5499e776](https://linux-hardware.org/?probe=2c5499e776) | Mar 22, 2024 |
| Lenovo        | V15 G3 IAP 82TT             | Notebook    | [fb281cfb94](https://linux-hardware.org/?probe=fb281cfb94) | Mar 18, 2024 |
| MACHINIST     | X99 PR9                     | Desktop     | [481821b9ad](https://linux-hardware.org/?probe=481821b9ad) | Mar 12, 2024 |
| Sony          | VPCEC3A4E                   | Notebook    | [38f3380fcf](https://linux-hardware.org/?probe=38f3380fcf) | Mar 11, 2024 |
| Dell          | Inspiron 14 Plus 7440       | Notebook    | [98c56ac1d0](https://linux-hardware.org/?probe=98c56ac1d0) | Mar 10, 2024 |
| Intel         | D102GGC2 AAD42789-204       | Desktop     | [0da90b1518](https://linux-hardware.org/?probe=0da90b1518) | Mar 03, 2024 |
| SLIMBOOK      | EXECUTIVE-14                | Notebook    | [39d528dadf](https://linux-hardware.org/?probe=39d528dadf) | Mar 01, 2024 |
| SLIMBOOK      | EXECUTIVE-14                | Notebook    | [5fc24348a8](https://linux-hardware.org/?probe=5fc24348a8) | Mar 01, 2024 |
| HP            | Laptop 15-bw0xx             | Notebook    | [39ed74cf97](https://linux-hardware.org/?probe=39ed74cf97) | Feb 24, 2024 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [340e79c73f](https://linux-hardware.org/?probe=340e79c73f) | Feb 22, 2024 |
| Sony          | VPCEC3A4E                   | Notebook    | [e365c35e91](https://linux-hardware.org/?probe=e365c35e91) | Feb 22, 2024 |
| Unknown       | Unknown                     | Soc         | [17963d5911](https://linux-hardware.org/?probe=17963d5911) | Feb 20, 2024 |
| Dell          | Inspiron 14 Plus 7440       | Notebook    | [0ee9f9ca69](https://linux-hardware.org/?probe=0ee9f9ca69) | Feb 18, 2024 |
| Sony          | VPCEC3A4E                   | Notebook    | [cc5290daff](https://linux-hardware.org/?probe=cc5290daff) | Feb 18, 2024 |
| Sony          | VPCEC3A4E                   | Notebook    | [b31170da6a](https://linux-hardware.org/?probe=b31170da6a) | Feb 17, 2024 |
| Acer          | TDPS05                      | Desktop     | [9156de5a01](https://linux-hardware.org/?probe=9156de5a01) | Feb 15, 2024 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [f3d4535f87](https://linux-hardware.org/?probe=f3d4535f87) | Feb 13, 2024 |
| AMI           | Intel                       | Desktop     | [15abbc4eb4](https://linux-hardware.org/?probe=15abbc4eb4) | Feb 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [6b61926dd2](https://linux-hardware.org/?probe=6b61926dd2) | Feb 09, 2024 |
| Dell          | Inspiron 14 Plus 7440       | Notebook    | [1e2603f833](https://linux-hardware.org/?probe=1e2603f833) | Feb 04, 2024 |
| HP            | 158Ch                       | Mini pc     | [2cef0fa0f1](https://linux-hardware.org/?probe=2cef0fa0f1) | Feb 03, 2024 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [dc84848e79](https://linux-hardware.org/?probe=dc84848e79) | Jan 24, 2024 |
| Apple         | MacBook5,1                  | Notebook    | [d3a48ce5b5](https://linux-hardware.org/?probe=d3a48ce5b5) | Jan 24, 2024 |
| Apple         | MacBook5,1                  | Notebook    | [2fa13d832c](https://linux-hardware.org/?probe=2fa13d832c) | Jan 24, 2024 |
| Dell          | Inspiron 14 Plus 7440       | Notebook    | [876874e8b5](https://linux-hardware.org/?probe=876874e8b5) | Jan 24, 2024 |
| Lenovo        | Y70-70 Touch 80DU           | Notebook    | [fb81d9ccfe](https://linux-hardware.org/?probe=fb81d9ccfe) | Jan 20, 2024 |
| Unknown       | Unknown                     | Desktop     | [413fbae0c9](https://linux-hardware.org/?probe=413fbae0c9) | Jan 17, 2024 |
| Unknown       | Unknown                     | Desktop     | [69d393fc55](https://linux-hardware.org/?probe=69d393fc55) | Jan 17, 2024 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [3f6d4a63ee](https://linux-hardware.org/?probe=3f6d4a63ee) | Jan 09, 2024 |
| HP            | 3397                        | Desktop     | [c33a1d3b01](https://linux-hardware.org/?probe=c33a1d3b01) | Jan 09, 2024 |
| Wortmann      | M660SE                      | Notebook    | [225361b7c3](https://linux-hardware.org/?probe=225361b7c3) | Jan 06, 2024 |
| Dell          | Inspiron 14 Plus 7440       | Notebook    | [6f9241e288](https://linux-hardware.org/?probe=6f9241e288) | Jan 04, 2024 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [cf4135541d](https://linux-hardware.org/?probe=cf4135541d) | Jan 03, 2024 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [9d5aa2f8ae](https://linux-hardware.org/?probe=9d5aa2f8ae) | Jan 02, 2024 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [db0bed1921](https://linux-hardware.org/?probe=db0bed1921) | Jan 02, 2024 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [018238aa79](https://linux-hardware.org/?probe=018238aa79) | Jan 01, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [cee7f7036e](https://linux-hardware.org/?probe=cee7f7036e) | Dec 31, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [d6121834a4](https://linux-hardware.org/?probe=d6121834a4) | Dec 31, 2023 |
| Dell          | Inspiron 14 Plus 7440       | Notebook    | [7528cb1c24](https://linux-hardware.org/?probe=7528cb1c24) | Dec 30, 2023 |
| Dell          | Inspiron 14 Plus 7440       | Notebook    | [f071a372c0](https://linux-hardware.org/?probe=f071a372c0) | Dec 29, 2023 |
| Acer          | Aspire A515-54              | Notebook    | [ea0b7cd870](https://linux-hardware.org/?probe=ea0b7cd870) | Dec 26, 2023 |
| Acer          | TDPS05                      | Desktop     | [ce9b5d0c48](https://linux-hardware.org/?probe=ce9b5d0c48) | Dec 23, 2023 |
| Acer          | TDPS05                      | Desktop     | [d0260b1327](https://linux-hardware.org/?probe=d0260b1327) | Dec 23, 2023 |
| Dell          | Inspiron 14 Plus 7440       | Notebook    | [2432d4f585](https://linux-hardware.org/?probe=2432d4f585) | Dec 22, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | Notebook    | [d33b5845ef](https://linux-hardware.org/?probe=d33b5845ef) | Dec 20, 2023 |
| Dell          | Inspiron 14 Plus 7440       | Notebook    | [4b404f8509](https://linux-hardware.org/?probe=4b404f8509) | Dec 15, 2023 |
| ZOTAC         | Unknown                     | Desktop     | [a91d567af3](https://linux-hardware.org/?probe=a91d567af3) | Dec 14, 2023 |
| Dell          | Latitude 3420               | Notebook    | [b344d71410](https://linux-hardware.org/?probe=b344d71410) | Dec 13, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [2199caf331](https://linux-hardware.org/?probe=2199caf331) | Dec 10, 2023 |
| Compaq        | 0684h                       | Desktop     | [54c2d84103](https://linux-hardware.org/?probe=54c2d84103) | Dec 02, 2023 |
| Compaq        | 0684h                       | Desktop     | [b2d96b48dc](https://linux-hardware.org/?probe=b2d96b48dc) | Dec 02, 2023 |
| ECS           | M789CG                      | Desktop     | [7c2e2de188](https://linux-hardware.org/?probe=7c2e2de188) | Dec 01, 2023 |
| ASUSTek       | 1001PX                      | Notebook    | [74bc5aeded](https://linux-hardware.org/?probe=74bc5aeded) | Nov 22, 2023 |
| ASUSTek       | 1001PX                      | Notebook    | [2069694d95](https://linux-hardware.org/?probe=2069694d95) | Nov 22, 2023 |
| Dell          | Inspiron 14 Plus 7440       | Notebook    | [b312b34d74](https://linux-hardware.org/?probe=b312b34d74) | Nov 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [f576d94ac0](https://linux-hardware.org/?probe=f576d94ac0) | Nov 17, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [1909f3fbff](https://linux-hardware.org/?probe=1909f3fbff) | Nov 15, 2023 |
| Dell          | Inspiron 14 Plus 7440       | Notebook    | [f48f05994e](https://linux-hardware.org/?probe=f48f05994e) | Nov 14, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [60e418e27f](https://linux-hardware.org/?probe=60e418e27f) | Nov 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [80774e2d18](https://linux-hardware.org/?probe=80774e2d18) | Nov 14, 2023 |
| Unknown       | MT6737 (DT)                 | Soc         | [ed82b4c1c7](https://linux-hardware.org/?probe=ed82b4c1c7) | Nov 12, 2023 |
| ZOTAC         | ZBOX-EN1070/1060,EN1070K... | Mini pc     | [bfd62247aa](https://linux-hardware.org/?probe=bfd62247aa) | Nov 12, 2023 |
| Dell          | Inspiron 14 Plus 7440       | Notebook    | [65a7263504](https://linux-hardware.org/?probe=65a7263504) | Nov 09, 2023 |
| ECS           | M789CG                      | Desktop     | [49edfe005c](https://linux-hardware.org/?probe=49edfe005c) | Nov 07, 2023 |
| Gigabyte      | 945GCM-S2C                  | Desktop     | [c714bf35c2](https://linux-hardware.org/?probe=c714bf35c2) | Nov 06, 2023 |
| Dell          | Inspiron 14 Plus 7440       | Notebook    | [ccc7d658ea](https://linux-hardware.org/?probe=ccc7d658ea) | Nov 06, 2023 |
| ECS           | M789CG                      | Desktop     | [87fe73ee84](https://linux-hardware.org/?probe=87fe73ee84) | Nov 02, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [0656d1a0a8](https://linux-hardware.org/?probe=0656d1a0a8) | Oct 28, 2023 |
| Dell          | Inspiron 14 Plus 7440       | Notebook    | [e116ef83e9](https://linux-hardware.org/?probe=e116ef83e9) | Oct 27, 2023 |
| Dell          | Inspiron 14 Plus 7440       | Notebook    | [6df3cd6820](https://linux-hardware.org/?probe=6df3cd6820) | Oct 20, 2023 |
| ECS           | M789CG                      | Desktop     | [b767549953](https://linux-hardware.org/?probe=b767549953) | Oct 15, 2023 |
| ASRock        | Q1900B-ITX                  | Desktop     | [8625166ef3](https://linux-hardware.org/?probe=8625166ef3) | Oct 14, 2023 |
| ECS           | M789CG                      | Desktop     | [6f446a6f77](https://linux-hardware.org/?probe=6f446a6f77) | Oct 14, 2023 |
| ECS           | M789CG                      | Desktop     | [0a0df79fcd](https://linux-hardware.org/?probe=0a0df79fcd) | Oct 14, 2023 |
| Inventec      | D CLASS A02                 | Desktop     | [9559c016fb](https://linux-hardware.org/?probe=9559c016fb) | Oct 13, 2023 |
| ASRock        | Z790M-ITX WiFi              | Desktop     | [560aec8a01](https://linux-hardware.org/?probe=560aec8a01) | Oct 06, 2023 |
| Dell          | Inspiron 14 Plus 7440       | Notebook    | [8356867b4d](https://linux-hardware.org/?probe=8356867b4d) | Oct 04, 2023 |
| Dell          | Inspiron 14 Plus 7440       | Notebook    | [1d2bd102c6](https://linux-hardware.org/?probe=1d2bd102c6) | Sep 28, 2023 |
| Dell          | Inspiron 14 Plus 7440       | Notebook    | [6295f7193c](https://linux-hardware.org/?probe=6295f7193c) | Sep 27, 2023 |
| Dell          | Inspiron 14 Plus 7440       | Notebook    | [793c32918d](https://linux-hardware.org/?probe=793c32918d) | Sep 23, 2023 |
| ASRock        | H55M-LE                     | Desktop     | [6b7e52fd8c](https://linux-hardware.org/?probe=6b7e52fd8c) | Sep 20, 2023 |
| ASRock        | H55M-LE                     | Desktop     | [ceefe742e2](https://linux-hardware.org/?probe=ceefe742e2) | Sep 20, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [b858f753b2](https://linux-hardware.org/?probe=b858f753b2) | Sep 19, 2023 |
| Dell          | 0RY007                      | Desktop     | [3bcbd1f6c3](https://linux-hardware.org/?probe=3bcbd1f6c3) | Sep 19, 2023 |
| Unknown       | Unknown                     | Notebook    | [cc13e0926e](https://linux-hardware.org/?probe=cc13e0926e) | Sep 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [416798463e](https://linux-hardware.org/?probe=416798463e) | Sep 16, 2023 |
| LG Electro... | LW25-B7HG                   | Notebook    | [e9998203e6](https://linux-hardware.org/?probe=e9998203e6) | Sep 12, 2023 |
| Dell          | Inspiron 14 Plus 7440       | Notebook    | [d59c2170bb](https://linux-hardware.org/?probe=d59c2170bb) | Sep 08, 2023 |
| Unknown       | MT6737 (DT)                 | Soc         | [ca65758798](https://linux-hardware.org/?probe=ca65758798) | Sep 07, 2023 |
| Dell          | Inspiron 14 Plus 7440       | Notebook    | [ed1061dbb1](https://linux-hardware.org/?probe=ed1061dbb1) | Sep 07, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [00e5bebc6a](https://linux-hardware.org/?probe=00e5bebc6a) | Sep 06, 2023 |
| Dell          | Inspiron 14 Plus 7440       | Notebook    | [30368099b8](https://linux-hardware.org/?probe=30368099b8) | Sep 06, 2023 |
| Dell          | Inspiron 14 Plus 7440       | Notebook    | [f71590bc2b](https://linux-hardware.org/?probe=f71590bc2b) | Sep 03, 2023 |
| HP            | Presario V2000 (ES307UA#... | Notebook    | [6c727b9e00](https://linux-hardware.org/?probe=6c727b9e00) | Aug 23, 2023 |
| Dell          | 007MXD A00                  | Mini pc     | [1eab959e9a](https://linux-hardware.org/?probe=1eab959e9a) | Aug 15, 2023 |
| Dell          | Inspiron 14 Plus 7440       | Notebook    | [d81314b86d](https://linux-hardware.org/?probe=d81314b86d) | Aug 12, 2023 |
| Dell          | Inspiron 14 Plus 7440       | Notebook    | [4d26902a65](https://linux-hardware.org/?probe=4d26902a65) | Aug 12, 2023 |
| Dell          | Inspiron 14 Plus 7440       | Notebook    | [d4a16b0b3e](https://linux-hardware.org/?probe=d4a16b0b3e) | Aug 10, 2023 |
| Dell          | Inspiron 14 Plus 7440       | Notebook    | [294dcce02b](https://linux-hardware.org/?probe=294dcce02b) | Aug 04, 2023 |
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
| Dell          | Inspiron 14 Plus 7440       | Notebook    | [b3d00219b0](https://linux-hardware.org/?probe=b3d00219b0) | Feb 07, 2023 |
| Google        | Leona                       | Notebook    | [59b146e197](https://linux-hardware.org/?probe=59b146e197) | Jan 21, 2023 |
| ASRock        | X470 Master SLI/ac          | Desktop     | [d8f1121a19](https://linux-hardware.org/?probe=d8f1121a19) | Jan 19, 2023 |
| Dell          | Cherry Trail CR A00         | Mini pc     | [68a73ee517](https://linux-hardware.org/?probe=68a73ee517) | Jan 19, 2023 |
| ASRock        | X470 Master SLI/ac          | Desktop     | [6b6a4929de](https://linux-hardware.org/?probe=6b6a4929de) | Jan 16, 2023 |
| ASRock        | X470 Master SLI/ac          | Desktop     | [8775308115](https://linux-hardware.org/?probe=8775308115) | Jan 15, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [473b4d0e6e](https://linux-hardware.org/?probe=473b4d0e6e) | Jan 11, 2023 |
| Dell          | Cherry Trail CR A00         | Mini pc     | [747c3d8c1f](https://linux-hardware.org/?probe=747c3d8c1f) | Jan 11, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [9635348d10](https://linux-hardware.org/?probe=9635348d10) | Jan 09, 2023 |
| Lenovo        | ThinkPad X131e 33711Q7      | Notebook    | [3336313cae](https://linux-hardware.org/?probe=3336313cae) | Jan 06, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [053b8697ce](https://linux-hardware.org/?probe=053b8697ce) | Jan 06, 2023 |
| Lenovo        | ThinkPad X131e 33711Q7      | Notebook    | [7e0f8a38bf](https://linux-hardware.org/?probe=7e0f8a38bf) | Jan 04, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [5da7f2d3a9](https://linux-hardware.org/?probe=5da7f2d3a9) | Dec 27, 2022 |
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
| Dell          | Inspiron 14 Plus 7440       | Notebook    | [3199a22608](https://linux-hardware.org/?probe=3199a22608) | Jul 15, 2021 |
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
| Dell          | Inspiron 14 Plus 7440       | Notebook    | [d05c262e67](https://linux-hardware.org/?probe=d05c262e67) | Aug 06, 2020 |
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
| Alpine 3.19.1               | 22        | 8.63%   |
| Alpine 3.20.3               | 14        | 5.49%   |
| Alpine 3.18.0               | 11        | 4.31%   |
| Alpine 3.12.0               | 11        | 4.31%   |
| Alpine 3.15.0               | 10        | 3.92%   |
| Alpine 3.21.0_alpha20240606 | 9         | 3.53%   |
| Alpine 3.19.0               | 9         | 3.53%   |
| Alpine 3.16.0               | 9         | 3.53%   |
| Alpine 3.15.4               | 9         | 3.53%   |
| Alpine 3.18.3               | 7         | 2.75%   |
| Alpine 3.15.0_alpha20210804 | 7         | 2.75%   |
| Alpine 3.20.0               | 6         | 2.35%   |
| Alpine 3.19_alpha20230901   | 6         | 2.35%   |
| Alpine 3.18.4               | 6         | 2.35%   |
| Alpine 3.17_alpha20220809   | 5         | 1.96%   |
| Alpine 3.17.2               | 5         | 1.96%   |
| Alpine 3.14.0               | 5         | 1.96%   |
| Alpine 3.21.0_alpha20240923 | 4         | 1.57%   |
| Alpine 3.21.0_alpha20240807 | 4         | 1.57%   |
| Alpine 3.20.2               | 4         | 1.57%   |
| Alpine 3.20.0_alpha20231219 | 4         | 1.57%   |
| Alpine 3.18.5               | 4         | 1.57%   |
| Alpine 3.18.2               | 4         | 1.57%   |
| Alpine 3.17.1               | 4         | 1.57%   |
| Alpine 3.17.0               | 4         | 1.57%   |
| Alpine 3.16.1               | 4         | 1.57%   |
| Alpine 3.14.2               | 4         | 1.57%   |
| Alpine 3.13.0_alpha20200917 | 4         | 1.57%   |
| Alpine 3.13.0_alpha20200626 | 4         | 1.57%   |
| Alpine 3.11.2               | 4         | 1.57%   |
| Alpine 3.21.0               | 3         | 1.18%   |
| Alpine 3.20.1               | 3         | 1.18%   |
| Alpine 3.20.0_alpha20240329 | 3         | 1.18%   |
| Alpine 3.18.6               | 3         | 1.18%   |
| Alpine 3.16.2               | 3         | 1.18%   |
| Alpine 3.13.1               | 3         | 1.18%   |
| Alpine 3.13.0_alpha20201218 | 3         | 1.18%   |
| Alpine 3.18_alpha20230329   | 2         | 0.78%   |
| Alpine 3.16.3               | 2         | 0.78%   |
| Alpine 3.15.6               | 2         | 0.78%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Alpine | 232       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version       | Computers | Percent |
|---------------|-----------|---------|
| 5.4.43-1-lts  | 8         | 3.03%   |
| 6.6.32-0-lts  | 5         | 1.89%   |
| 6.6.30-0-lts  | 5         | 1.89%   |
| 6.6.37-0-lts  | 3         | 1.14%   |
| 6.6.16-0-lts  | 3         | 1.14%   |
| 6.1.57-0-lts  | 3         | 1.14%   |
| 6.1.32-0-lts  | 3         | 1.14%   |
| 5.15.86-0-lts | 3         | 1.14%   |
| 5.15.60-0-lts | 3         | 1.14%   |
| 5.15.16-0-lts | 3         | 1.14%   |
| 5.10.61-0-lts | 3         | 1.14%   |
| 6.6.7-0-lts   | 2         | 0.76%   |
| 6.6.63-0-lts  | 2         | 0.76%   |
| 6.6.61-0-lts  | 2         | 0.76%   |
| 6.6.60-0-lts  | 2         | 0.76%   |
| 6.6.58-0-lts  | 2         | 0.76%   |
| 6.6.52-0-lts  | 2         | 0.76%   |
| 6.6.45-0-lts  | 2         | 0.76%   |
| 6.6.44-0-lts  | 2         | 0.76%   |
| 6.6.36-0-lts  | 2         | 0.76%   |
| 6.6.35-0-lts  | 2         | 0.76%   |
| 6.6.33-haos   | 2         | 0.76%   |
| 6.6.23-0-lts  | 2         | 0.76%   |
| 6.6.22-0-lts  | 2         | 0.76%   |
| 6.6.21-0-lts  | 2         | 0.76%   |
| 6.6.17-0-lts  | 2         | 0.76%   |
| 6.6.12-0-lts  | 2         | 0.76%   |
| 6.6.1-0-edge  | 2         | 0.76%   |
| 6.5.11-4-pve  | 2         | 0.76%   |
| 6.1.77-0-lts  | 2         | 0.76%   |
| 6.1.62-0-lts  | 2         | 0.76%   |
| 6.1.55-0-lts  | 2         | 0.76%   |
| 6.1.51-0-lts  | 2         | 0.76%   |
| 6.1.28-2-lts  | 2         | 0.76%   |
| 5.4.84-0-lts  | 2         | 0.76%   |
| 5.4.83-0-lts  | 2         | 0.76%   |
| 5.17.9-0-edge | 2         | 0.76%   |
| 5.15.74-0-lts | 2         | 0.76%   |
| 5.15.59-0-lts | 2         | 0.76%   |
| 5.15.47-0-lts | 2         | 0.76%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.43  | 8         | 3.08%   |
| 6.6.32  | 5         | 1.92%   |
| 6.6.30  | 5         | 1.92%   |
| 6.6.58  | 3         | 1.15%   |
| 6.6.37  | 3         | 1.15%   |
| 6.6.33  | 3         | 1.15%   |
| 6.6.16  | 3         | 1.15%   |
| 6.1.57  | 3         | 1.15%   |
| 6.1.55  | 3         | 1.15%   |
| 6.1.32  | 3         | 1.15%   |
| 5.15.86 | 3         | 1.15%   |
| 5.15.60 | 3         | 1.15%   |
| 5.15.16 | 3         | 1.15%   |
| 5.15.0  | 3         | 1.15%   |
| 5.10.61 | 3         | 1.15%   |
| 6.6.7   | 2         | 0.77%   |
| 6.6.63  | 2         | 0.77%   |
| 6.6.61  | 2         | 0.77%   |
| 6.6.60  | 2         | 0.77%   |
| 6.6.52  | 2         | 0.77%   |
| 6.6.49  | 2         | 0.77%   |
| 6.6.45  | 2         | 0.77%   |
| 6.6.44  | 2         | 0.77%   |
| 6.6.36  | 2         | 0.77%   |
| 6.6.35  | 2         | 0.77%   |
| 6.6.23  | 2         | 0.77%   |
| 6.6.22  | 2         | 0.77%   |
| 6.6.21  | 2         | 0.77%   |
| 6.6.17  | 2         | 0.77%   |
| 6.6.12  | 2         | 0.77%   |
| 6.6.1   | 2         | 0.77%   |
| 6.5.11  | 2         | 0.77%   |
| 6.2.0   | 2         | 0.77%   |
| 6.1.77  | 2         | 0.77%   |
| 6.1.64  | 2         | 0.77%   |
| 6.1.62  | 2         | 0.77%   |
| 6.1.51  | 2         | 0.77%   |
| 6.1.34  | 2         | 0.77%   |
| 6.1.28  | 2         | 0.77%   |
| 5.4.84  | 2         | 0.77%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.6     | 69        | 27.82%  |
| 5.15    | 52        | 20.97%  |
| 6.1     | 36        | 14.52%  |
| 5.4     | 23        | 9.27%   |
| 5.10    | 23        | 9.27%   |
| 6.11    | 4         | 1.61%   |
| 5.17    | 4         | 1.61%   |
| 6.5     | 3         | 1.21%   |
| 6.12    | 3         | 1.21%   |
| 3.10    | 3         | 1.21%   |
| 6.9     | 2         | 0.81%   |
| 6.8     | 2         | 0.81%   |
| 6.2     | 2         | 0.81%   |
| 5.8     | 2         | 0.81%   |
| 5.19    | 2         | 0.81%   |
| 5.14    | 2         | 0.81%   |
| 4.4     | 2         | 0.81%   |
| 3.18    | 2         | 0.81%   |
| 6.4     | 1         | 0.4%    |
| 6.3     | 1         | 0.4%    |
| 6.0     | 1         | 0.4%    |
| 5.7     | 1         | 0.4%    |
| 5.6     | 1         | 0.4%    |
| 5.18    | 1         | 0.4%    |
| 5.16    | 1         | 0.4%    |
| 5.13    | 1         | 0.4%    |
| 5.12    | 1         | 0.4%    |
| 4.9     | 1         | 0.4%    |
| 4.20    | 1         | 0.4%    |
| 4.14    | 1         | 0.4%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| x86_64      | 200       | 86.21%  |
| i686        | 20        | 8.62%   |
| aarch64     | 6         | 2.59%   |
| armv7l      | 3         | 1.29%   |
| loongarch64 | 1         | 0.43%   |
| i586        | 1         | 0.43%   |
| armv6l      | 1         | 0.43%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 175       | 75.43%  |
| XFCE          | 24        | 10.34%  |
| GNOME         | 9         | 3.88%   |
| KDE5          | 7         | 3.02%   |
| KDE6          | 6         | 2.59%   |
| sway          | 4         | 1.72%   |
| MATE          | 2         | 0.86%   |
| LXQt          | 2         | 0.86%   |
| KDE           | 1         | 0.43%   |
| i3            | 1         | 0.43%   |
| GNOME Classic | 1         | 0.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 136       | 57.14%  |
| X11     | 78        | 32.77%  |
| Wayland | 22        | 9.24%   |
| Tty     | 2         | 0.84%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 182       | 77.78%  |
| LightDM | 30        | 12.82%  |
| GDM     | 11        | 4.7%    |
| SDDM    | 8         | 3.42%   |
| LXDM    | 2         | 0.85%   |
| XDM     | 1         | 0.43%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| C       | 140       | 59.07%  |
| Unknown | 79        | 33.33%  |
| en_US   | 9         | 3.8%    |
| ru_RU   | 3         | 1.27%   |
| pt_BR   | 2         | 0.84%   |
| en_GB   | 2         | 0.84%   |
| tr_TR   | 1         | 0.42%   |
| es_NI   | 1         | 0.42%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 138       | 58.72%  |
| EFI  | 97        | 41.28%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 185       | 77.41%  |
| Btrfs   | 19        | 7.95%   |
| Overlay | 13        | 5.44%   |
| Tmpfs   | 7         | 2.93%   |
| Unknown | 5         | 2.09%   |
| Xfs     | 2         | 0.84%   |
| F2fs    | 2         | 0.84%   |
| Ext2    | 2         | 0.84%   |
| Zfs     | 1         | 0.42%   |
| XXXXX   | 1         | 0.42%   |
| Rootfs  | 1         | 0.42%   |
| Fake    | 1         | 0.42%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 133       | 55.65%  |
| GPT     | 77        | 32.22%  |
| MBR     | 29        | 12.13%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 206       | 88.03%  |
| Yes       | 28        | 11.97%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 219       | 93.19%  |
| Yes       | 16        | 6.81%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 40        | 17.24%  |
| Dell                    | 31        | 13.36%  |
| ASUSTek Computer        | 24        | 10.34%  |
| Lenovo                  | 23        | 9.91%   |
| Gigabyte Technology     | 11        | 4.74%   |
| Unknown                 | 10        | 4.31%   |
| ASRock                  | 9         | 3.88%   |
| Intel                   | 8         | 3.45%   |
| Fujitsu                 | 8         | 3.45%   |
| Acer                    | 8         | 3.45%   |
| Apple                   | 6         | 2.59%   |
| Inventec                | 5         | 2.16%   |
| Toshiba                 | 4         | 1.72%   |
| Raspberry Pi Foundation | 4         | 1.72%   |
| Google                  | 4         | 1.72%   |
| MSI                     | 3         | 1.29%   |
| IBM                     | 3         | 1.29%   |
| Gateway                 | 3         | 1.29%   |
| ZOTAC                   | 2         | 0.86%   |
| Sony                    | 2         | 0.86%   |
| AMI                     | 2         | 0.86%   |
| Wortmann AG             | 1         | 0.43%   |
| VIA Technologies        | 1         | 0.43%   |
| UGREEN                  | 1         | 0.43%   |
| Synology                | 1         | 0.43%   |
| Supermicro              | 1         | 0.43%   |
| SLIMBOOK                | 1         | 0.43%   |
| Shuttle                 | 1         | 0.43%   |
| Samsung Electronics     | 1         | 0.43%   |
| Pegatron                | 1         | 0.43%   |
| Olivetti                | 1         | 0.43%   |
| Notebook                | 1         | 0.43%   |
| Microsoft               | 1         | 0.43%   |
| MACHINIST               | 1         | 0.43%   |
| Loongson                | 1         | 0.43%   |
| LG Electronics          | 1         | 0.43%   |
| HPE                     | 1         | 0.43%   |
| Haier                   | 1         | 0.43%   |
| Fanless Mini PC         | 1         | 0.43%   |
| F5 Networks             | 1         | 0.43%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 11        | 4.74%   |
| HP ENVY Laptop 13-ad1xx               | 4         | 1.72%   |
| RPi Raspberry Pi                      | 3         | 1.29%   |
| Inventec D CLASS                      | 3         | 1.29%   |
| Dell Dell Thin Client Desktop 3030 LT | 3         | 1.29%   |
| ASUS All Series                       | 3         | 1.29%   |
| Lenovo V15 G3 IAP 82TT                | 2         | 0.86%   |
| Inventec DQ Class                     | 2         | 0.86%   |
| HP ProLiant DL360 G6                  | 2         | 0.86%   |
| Google Kefka                          | 2         | 0.86%   |
| Gigabyte Z490I AORUS ULTRA            | 2         | 0.86%   |
| ZOTAC ZBOX-EN1070/1060,EN1070K/1060K  | 1         | 0.43%   |
| Wortmann AG M660SE                    | 1         | 0.43%   |
| VIA KM266APro-835                     | 1         | 0.43%   |
| UGREEN DX4600                         | 1         | 0.43%   |
| Toshiba WT8-A                         | 1         | 0.43%   |
| Toshiba Satellite Pro L50-A           | 1         | 0.43%   |
| Toshiba Satellite M645                | 1         | 0.43%   |
| Toshiba Satellite M50Dt-A             | 1         | 0.43%   |
| Synology DS1019+                      | 1         | 0.43%   |
| Supermicro X10SLL-F                   | 1         | 0.43%   |
| Sony VPCEC3A4E                        | 1         | 0.43%   |
| Sony VGN-UX27GN                       | 1         | 0.43%   |
| SLIMBOOK EXECUTIVE-14                 | 1         | 0.43%   |
| Shuttle DS81D                         | 1         | 0.43%   |
| Samsung 100NZC                        | 1         | 0.43%   |
| RPi Raspberry Pi 4 Model B Rev 1.5    | 1         | 0.43%   |
| Pegatron Deepcam                      | 1         | 0.43%   |
| Olivetti Spring Peak                  | 1         | 0.43%   |
| Notebook NV4XMB,ME,MZ                 | 1         | 0.43%   |
| MSI MS-7C82                           | 1         | 0.43%   |
| MSI MS-7877                           | 1         | 0.43%   |
| MSI GL72M 7REX                        | 1         | 0.43%   |
| Microsoft Surface Pro 2               | 1         | 0.43%   |
| MACHINIST X99 PR9                     | 1         | 0.43%   |
| Loongson 3A6000-HV-7A2000-1w-V0.1-EVB | 1         | 0.43%   |
| LG LW25-B7HG                          | 1         | 0.43%   |
| Lenovo Yoga 14sARH 2021 82LB          | 1         | 0.43%   |
| Lenovo Y70-70 Touch 80DU              | 1         | 0.43%   |
| Lenovo V14-ADA 82C6                   | 1         | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell Inspiron       | 13        | 5.6%    |
| Lenovo ThinkPad     | 11        | 4.74%   |
| Unknown             | 11        | 4.74%   |
| HP EliteBook        | 7         | 3.02%   |
| Dell OptiPlex       | 7         | 3.02%   |
| Acer Aspire         | 6         | 2.59%   |
| HP Laptop           | 5         | 2.16%   |
| HP ENVY             | 5         | 2.16%   |
| RPi Raspberry       | 4         | 1.72%   |
| ASUS PRIME          | 4         | 1.72%   |
| Toshiba Satellite   | 3         | 1.29%   |
| Inventec D          | 3         | 1.29%   |
| HP ProLiant         | 3         | 1.29%   |
| HP Pavilion         | 3         | 1.29%   |
| HP Compaq           | 3         | 1.29%   |
| Dell XPS            | 3         | 1.29%   |
| Dell Dell           | 3         | 1.29%   |
| ASUS VivoBook       | 3         | 1.29%   |
| ASUS All            | 3         | 1.29%   |
| Lenovo V15          | 2         | 0.86%   |
| Lenovo MIIX         | 2         | 0.86%   |
| Lenovo IdeaPad      | 2         | 0.86%   |
| Inventec DQ         | 2         | 0.86%   |
| HP Stream           | 2         | 0.86%   |
| HP ProBook          | 2         | 0.86%   |
| HP Presario         | 2         | 0.86%   |
| HP EliteDesk        | 2         | 0.86%   |
| Google Kefka        | 2         | 0.86%   |
| Gigabyte Z490I      | 2         | 0.86%   |
| Fujitsu LIFEBOOK    | 2         | 0.86%   |
| Fujitsu ESPRIMO     | 2         | 0.86%   |
| Dell Latitude       | 2         | 0.86%   |
| ZOTAC ZBOX-EN1070   | 1         | 0.43%   |
| Wortmann AG M660SE  | 1         | 0.43%   |
| VIA KM266APro-835   | 1         | 0.43%   |
| UGREEN DX4600       | 1         | 0.43%   |
| Toshiba WT8-A       | 1         | 0.43%   |
| Synology DS1019+    | 1         | 0.43%   |
| Supermicro X10SLL-F | 1         | 0.43%   |
| Sony VPCEC3A4E      | 1         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2014    | 23        | 9.91%   |
| 2019    | 19        | 8.19%   |
| 2013    | 18        | 7.76%   |
| 2012    | 18        | 7.76%   |
| 2016    | 16        | 6.9%    |
| 2018    | 14        | 6.03%   |
| 2017    | 14        | 6.03%   |
| 2010    | 14        | 6.03%   |
| Unknown | 13        | 5.6%    |
| 2021    | 11        | 4.74%   |
| 2011    | 10        | 4.31%   |
| 2020    | 9         | 3.88%   |
| 2022    | 8         | 3.45%   |
| 2009    | 8         | 3.45%   |
| 2007    | 8         | 3.45%   |
| 2015    | 7         | 3.02%   |
| 2006    | 6         | 2.59%   |
| 2023    | 4         | 1.72%   |
| 2008    | 4         | 1.72%   |
| 2024    | 2         | 0.86%   |
| 2005    | 2         | 0.86%   |
| 2001    | 2         | 0.86%   |
| 2004    | 1         | 0.43%   |
| 1999    | 1         | 0.43%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 114       | 49.14%  |
| Desktop        | 82        | 35.34%  |
| Mini pc        | 14        | 6.03%   |
| System on chip | 7         | 3.02%   |
| Server         | 6         | 2.59%   |
| Tablet         | 5         | 2.16%   |
| Convertible    | 2         | 0.86%   |
| All in one     | 2         | 0.86%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 231       | 99.14%  |
| Enabled  | 2         | 0.86%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 228       | 98.28%  |
| Yes  | 4         | 1.72%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 53        | 21.99%  |
| 3.01-4.0        | 47        | 19.5%   |
| 16.01-24.0      | 36        | 14.94%  |
| 8.01-16.0       | 30        | 12.45%  |
| 1.01-2.0        | 21        | 8.71%   |
| 0.51-1.0        | 16        | 6.64%   |
| 32.01-64.0      | 15        | 6.22%   |
| 64.01-256.0     | 8         | 3.32%   |
| 2.01-3.0        | 7         | 2.9%    |
| 0.01-0.5        | 6         | 2.49%   |
| More than 256.0 | 2         | 0.83%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 64        | 25.81%  |
| 1.01-2.0   | 57        | 22.98%  |
| 0.51-1.0   | 40        | 16.13%  |
| 2.01-3.0   | 33        | 13.31%  |
| 4.01-8.0   | 18        | 7.26%   |
| 3.01-4.0   | 16        | 6.45%   |
| 8.01-16.0  | 8         | 3.23%   |
| 0          | 7         | 2.82%   |
| Unknown    | 4         | 1.61%   |
| 24.01-32.0 | 1         | 0.4%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 156       | 65.27%  |
| 2      | 46        | 19.25%  |
| 3      | 14        | 5.86%   |
| 4      | 9         | 3.77%   |
| 5      | 4         | 1.67%   |
| 0      | 4         | 1.67%   |
| 14     | 2         | 0.84%   |
| 12     | 1         | 0.42%   |
| 10     | 1         | 0.42%   |
| 8      | 1         | 0.42%   |
| 7      | 1         | 0.42%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 186       | 79.49%  |
| Yes       | 48        | 20.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 194       | 83.26%  |
| No        | 39        | 16.74%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 151       | 63.71%  |
| No        | 86        | 36.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 123       | 52.12%  |
| Yes       | 113       | 47.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 50        | 20.49%  |
| Germany      | 29        | 11.89%  |
| Russia       | 18        | 7.38%   |
| Canada       | 15        | 6.15%   |
| UK           | 12        | 4.92%   |
| Brazil       | 10        | 4.1%    |
| France       | 8         | 3.28%   |
| Turkey       | 7         | 2.87%   |
| Sweden       | 5         | 2.05%   |
| Spain        | 5         | 2.05%   |
| Poland       | 5         | 2.05%   |
| Norway       | 5         | 2.05%   |
| Australia    | 5         | 2.05%   |
| Netherlands  | 4         | 1.64%   |
| Italy        | 4         | 1.64%   |
| Switzerland  | 3         | 1.23%   |
| Slovakia     | 3         | 1.23%   |
| Romania      | 3         | 1.23%   |
| Portugal     | 3         | 1.23%   |
| Finland      | 3         | 1.23%   |
| China        | 3         | 1.23%   |
| Argentina    | 3         | 1.23%   |
| Ukraine      | 2         | 0.82%   |
| Mexico       | 2         | 0.82%   |
| Israel       | 2         | 0.82%   |
| Hungary      | 2         | 0.82%   |
| Guatemala    | 2         | 0.82%   |
| Austria      | 2         | 0.82%   |
| Vietnam      | 1         | 0.41%   |
| Venezuela    | 1         | 0.41%   |
| Uruguay      | 1         | 0.41%   |
| UAE          | 1         | 0.41%   |
| Thailand     | 1         | 0.41%   |
| South Korea  | 1         | 0.41%   |
| South Africa | 1         | 0.41%   |
| Réunion     | 1         | 0.41%   |
| Puerto Rico  | 1         | 0.41%   |
| Philippines  | 1         | 0.41%   |
| Paraguay     | 1         | 0.41%   |
| Pakistan     | 1         | 0.41%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Traunstein        | 9         | 3.57%   |
| Springfield       | 7         | 2.78%   |
| Istanbul          | 7         | 2.78%   |
| St Petersburg     | 6         | 2.38%   |
| Vernon            | 5         | 1.98%   |
| Moscow            | 5         | 1.98%   |
| Manitowoc         | 5         | 1.98%   |
| Zurich            | 3         | 1.19%   |
| Waukesha          | 2         | 0.79%   |
| Ufa               | 2         | 0.79%   |
| Sydney            | 2         | 0.79%   |
| Stuttgart         | 2         | 0.79%   |
| Stratford         | 2         | 0.79%   |
| Stillwater        | 2         | 0.79%   |
| Siegsdorf         | 2         | 0.79%   |
| Seattle           | 2         | 0.79%   |
| Sao Paulo         | 2         | 0.79%   |
| Kharkiv           | 2         | 0.79%   |
| Helsinki          | 2         | 0.79%   |
| Harrisonburg      | 2         | 0.79%   |
| Guatemala City    | 2         | 0.79%   |
| Gothenburg        | 2         | 0.79%   |
| Fulham            | 2         | 0.79%   |
| Frankfurt am Main | 2         | 0.79%   |
| Clermont-Ferrand  | 2         | 0.79%   |
| Buenos Aires      | 2         | 0.79%   |
| Bucharest         | 2         | 0.79%   |
| Bratislava        | 2         | 0.79%   |
| As                | 2         | 0.79%   |
| Zhangzhou         | 1         | 0.4%    |
| Yakima            | 1         | 0.4%    |
| Wimborne Minster  | 1         | 0.4%    |
| Warsaw            | 1         | 0.4%    |
| Vragender         | 1         | 0.4%    |
| Vilnius           | 1         | 0.4%    |
| Vienna            | 1         | 0.4%    |
| Ventura           | 1         | 0.4%    |
| Vejle             | 1         | 0.4%    |
| Vancouver         | 1         | 0.4%    |
| Ulyanovsk         | 1         | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 43        | 84     | 13.07%  |
| WDC                       | 36        | 71     | 10.94%  |
| Seagate                   | 35        | 72     | 10.64%  |
| Unknown                   | 30        | 39     | 9.12%   |
| Toshiba                   | 24        | 27     | 7.29%   |
| Sandisk                   | 15        | 18     | 4.56%   |
| Kingston                  | 14        | 19     | 4.26%   |
| Hitachi                   | 14        | 14     | 4.26%   |
| Crucial                   | 12        | 21     | 3.65%   |
| HGST                      | 11        | 11     | 3.34%   |
| Intel                     | 10        | 15     | 3.04%   |
| SK hynix                  | 9         | 11     | 2.74%   |
| A-DATA Technology         | 8         | 11     | 2.43%   |
| Micron Technology         | 5         | 6      | 1.52%   |
| SPCC                      | 4         | 4      | 1.22%   |
| Realtek Semiconductor     | 4         | 4      | 1.22%   |
| Unknown                   | 4         | 4      | 1.22%   |
| LITEON                    | 3         | 3      | 0.91%   |
| Intenso                   | 3         | 3      | 0.91%   |
| Transcend                 | 2         | 2      | 0.61%   |
| OCZ                       | 2         | 2      | 0.61%   |
| Hewlett-Packard           | 2         | 4      | 0.61%   |
| Fujitsu                   | 2         | 2      | 0.61%   |
| Corsair                   | 2         | 3      | 0.61%   |
| China                     | 2         | 2      | 0.61%   |
| AMD                       | 2         | 2      | 0.61%   |
| STEC                      | 1         | 1      | 0.3%    |
| SINTECHI                  | 1         | 1      | 0.3%    |
| Silicon Motion            | 1         | 1      | 0.3%    |
| Secure                    | 1         | 1      | 0.3%    |
| SABRENT                   | 1         | 1      | 0.3%    |
| PNY                       | 1         | 1      | 0.3%    |
| Plextor                   | 1         | 1      | 0.3%    |
| Phison Electronics        | 1         | 1      | 0.3%    |
| Patriot                   | 1         | 1      | 0.3%    |
| NETAPP                    | 1         | 1      | 0.3%    |
| Netac                     | 1         | 1      | 0.3%    |
| MSI                       | 1         | 1      | 0.3%    |
| Micron/Crucial Technology | 1         | 1      | 0.3%    |
| Maxtor                    | 1         | 1      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                              | 6         | 1.56%   |
| Unknown MMC Card  16GB                              | 5         | 1.3%    |
| Unknown SD/MMC/MS PRO 128GB                         | 4         | 1.04%   |
| Unknown MMC Card  64GB                              | 4         | 1.04%   |
| Unknown MMC Card  4GB                               | 4         | 1.04%   |
| Unknown MMC Card                                    | 4         | 1.04%   |
| Toshiba KXG50ZNV256G 256GB                          | 4         | 1.04%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 4         | 1.04%   |
| Unknown                                             | 4         | 1.04%   |
| SK hynix BC501 NVMe Solid State Drive 512GB         | 3         | 0.78%   |
| Seagate ST1000LM035-1RK172 1TB                      | 3         | 0.78%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB    | 3         | 0.78%   |
| Samsung SSD 870 EVO 1TB                             | 3         | 0.78%   |
| Samsung NVMe SSD Drive 1024GB                       | 3         | 0.78%   |
| Crucial CT500MX500SSD1 500GB                        | 3         | 0.78%   |
| Crucial CT1000MX500SSD1 1TB                         | 3         | 0.78%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 2         | 0.52%   |
| WDC WDS250G2B0A 250GB SSD                           | 2         | 0.52%   |
| WDC WD3000BLFS-60YBU2 304GB                         | 2         | 0.52%   |
| Toshiba MQ01ABD100 1TB                              | 2         | 0.52%   |
| Toshiba MQ01ABD075 752GB                            | 2         | 0.52%   |
| Seagate ST4000VN008-2DR1 4TB                        | 2         | 0.52%   |
| Seagate ST380815AS 80GB                             | 2         | 0.52%   |
| Seagate ST2000LM015-2E81 2TB                        | 2         | 0.52%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 0.52%   |
| Samsung SSD 980 PRO 1TB                             | 2         | 0.52%   |
| Samsung SSD 970 EVO Plus 250GB                      | 2         | 0.52%   |
| Samsung SSD 960 EVO 500GB                           | 2         | 0.52%   |
| Samsung SSD 870 QVO 1TB                             | 2         | 0.52%   |
| Samsung SSD 860 1TB                                 | 2         | 0.52%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 2         | 0.52%   |
| Kingston SV300S37A120G 120GB SSD                    | 2         | 0.52%   |
| Kingston SA400S37120G 120GB SSD                     | 2         | 0.52%   |
| Kingston SA400S3 960GB SSD                          | 2         | 0.52%   |
| Intenso SSD 128GB                                   | 2         | 0.52%   |
| Intel SSDSC2BB08 80GB                               | 2         | 0.52%   |
| HP LOGICAL VOLUME 160GB                             | 2         | 0.52%   |
| Crucial CT120BX500SSD1 120GB                        | 2         | 0.52%   |
| A-DATA SU800 128GB SSD                              | 2         | 0.52%   |
| WDC WDS500G2X0C-00L350 500GB                        | 1         | 0.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 35        | 72     | 28.23%  |
| WDC                 | 28        | 57     | 22.58%  |
| Toshiba             | 16        | 18     | 12.9%   |
| Hitachi             | 14        | 14     | 11.29%  |
| HGST                | 11        | 11     | 8.87%   |
| Samsung Electronics | 6         | 10     | 4.84%   |
| Unknown             | 4         | 4      | 3.23%   |
| Hewlett-Packard     | 2         | 4      | 1.61%   |
| Fujitsu             | 2         | 2      | 1.61%   |
| SINTECHI            | 1         | 1      | 0.81%   |
| SABRENT             | 1         | 1      | 0.81%   |
| Maxtor              | 1         | 1      | 0.81%   |
| JMicron Technology  | 1         | 1      | 0.81%   |
| IBM                 | 1         | 1      | 0.81%   |
| EDILOCA             | 1         | 1      | 0.81%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 20        | 38     | 17.09%  |
| Kingston            | 13        | 15     | 11.11%  |
| Crucial             | 12        | 21     | 10.26%  |
| WDC                 | 8         | 10     | 6.84%   |
| Intel               | 8         | 11     | 6.84%   |
| SanDisk             | 5         | 6      | 4.27%   |
| A-DATA Technology   | 5         | 6      | 4.27%   |
| SPCC                | 4         | 4      | 3.42%   |
| SK hynix            | 3         | 4      | 2.56%   |
| LITEON              | 3         | 3      | 2.56%   |
| Intenso             | 3         | 3      | 2.56%   |
| Unknown             | 3         | 3      | 2.56%   |
| Transcend           | 2         | 2      | 1.71%   |
| OCZ                 | 2         | 2      | 1.71%   |
| Micron Technology   | 2         | 2      | 1.71%   |
| Corsair             | 2         | 3      | 1.71%   |
| China               | 2         | 2      | 1.71%   |
| AMD                 | 2         | 2      | 1.71%   |
| Toshiba             | 1         | 1      | 0.85%   |
| Secure              | 1         | 1      | 0.85%   |
| PNY                 | 1         | 1      | 0.85%   |
| Plextor             | 1         | 1      | 0.85%   |
| Patriot             | 1         | 1      | 0.85%   |
| Netac               | 1         | 1      | 0.85%   |
| MSI                 | 1         | 1      | 0.85%   |
| LITEONIT            | 1         | 1      | 0.85%   |
| Lexar               | 1         | 1      | 0.85%   |
| KingSpec            | 1         | 1      | 0.85%   |
| Kingmax             | 1         | 1      | 0.85%   |
| KC600               | 1         | 1      | 0.85%   |
| INNOVATION IT       | 1         | 1      | 0.85%   |
| Emtec               | 1         | 1      | 0.85%   |
| Dell                | 1         | 2      | 0.85%   |
| Aura                | 1         | 1      | 0.85%   |
| ASMT                | 1         | 1      | 0.85%   |
| Apacer              | 1         | 1      | 0.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 106       | 198    | 36.68%  |
| SSD     | 97        | 156    | 33.56%  |
| NVMe    | 59        | 96     | 20.42%  |
| MMC     | 26        | 36     | 9%      |
| Unknown | 1         | 2      | 0.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 163       | 335    | 61.74%  |
| NVMe | 59        | 96     | 22.35%  |
| MMC  | 26        | 36     | 9.85%   |
| SAS  | 16        | 21     | 6.06%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 130       | 208    | 64.04%  |
| 0.51-1.0   | 41        | 56     | 20.2%   |
| 1.01-2.0   | 11        | 17     | 5.42%   |
| 4.01-10.0  | 8         | 29     | 3.94%   |
| 3.01-4.0   | 7         | 24     | 3.45%   |
| 2.01-3.0   | 3         | 7      | 1.48%   |
| 10.01-20.0 | 3         | 13     | 1.48%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 51        | 21.43%  |
| Unknown        | 44        | 18.49%  |
| 1-20           | 31        | 13.03%  |
| 251-500        | 25        | 10.5%   |
| 501-1000       | 25        | 10.5%   |
| More than 3000 | 16        | 6.72%   |
| 21-50          | 15        | 6.3%    |
| 51-100         | 14        | 5.88%   |
| 1001-2000      | 12        | 5.04%   |
| 2001-3000      | 5         | 2.1%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 125       | 52.74%  |
| Unknown        | 44        | 18.57%  |
| 21-50          | 18        | 7.59%   |
| 51-100         | 16        | 6.75%   |
| 251-500        | 10        | 4.22%   |
| 501-1000       | 8         | 3.38%   |
| 101-250        | 6         | 2.53%   |
| 1001-2000      | 5         | 2.11%   |
| More than 3000 | 3         | 1.27%   |
| 2001-3000      | 2         | 0.84%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD3000BLFS-60YBU2 304GB                    | 2         | 14     | 5.41%   |
| WDC WD3200AAKX-0 320GB                         | 1         | 1      | 2.7%    |
| WDC WD20EFAX-68F 2TB                           | 1         | 2      | 2.7%    |
| WDC WD10SPZX-80Z10T2 1TB                       | 1         | 1      | 2.7%    |
| WDC WD Blue SA510 2. 500GB SSD                 | 1         | 1      | 2.7%    |
| Toshiba MK4009GAL 40GB                         | 1         | 1      | 2.7%    |
| Toshiba MK3252GS 320GB                         | 1         | 1      | 2.7%    |
| Secure Net 256GB SSD                           | 1         | 1      | 2.7%    |
| Seagate ST9250315AS 250GB                      | 1         | 1      | 2.7%    |
| Seagate ST500LM021-1KJ152 500GB                | 1         | 1      | 2.7%    |
| Seagate ST3250318AS 250GB                      | 1         | 1      | 2.7%    |
| Seagate ST320LT007-9ZV14 320GB                 | 1         | 2      | 2.7%    |
| Seagate ST2000LM015-2E81 2TB                   | 1         | 1      | 2.7%    |
| SanDisk SDSA6MM 16GB SSD                       | 1         | 1      | 2.7%    |
| Samsung Electronics SSD PM81 128GB             | 1         | 1      | 2.7%    |
| Samsung Electronics SP0411N 40GB               | 1         | 2      | 2.7%    |
| Samsung Electronics HM160HI 160GB              | 1         | 2      | 2.7%    |
| Samsung Electronics HD252HJ 250GB              | 1         | 1      | 2.7%    |
| Netac SSD 256GB                                | 1         | 1      | 2.7%    |
| Micron Technology 1100_MTFDDAK256TBN 256GB SSD | 1         | 1      | 2.7%    |
| Maxtor 2B020H1 20GB                            | 1         | 1      | 2.7%    |
| Kingmax SSD 120G                               | 1         | 1      | 2.7%    |
| Hitachi HTS725025A9A364 250GB                  | 1         | 1      | 2.7%    |
| Hitachi HTS723232A7A364 320GB                  | 1         | 1      | 2.7%    |
| Hitachi HTS722080K9A300 80GB                   | 1         | 1      | 2.7%    |
| Hitachi HTS72101 99GB                          | 1         | 1      | 2.7%    |
| Hitachi HTS542516K9SA00 160GB                  | 1         | 1      | 2.7%    |
| Hitachi HTC426040G9AT00 40GB                   | 1         | 1      | 2.7%    |
| HGST HTS725050A7 500GB                         | 1         | 1      | 2.7%    |
| HGST HTS721010A9E630 1TB                       | 1         | 1      | 2.7%    |
| HGST HTS545050A7E380 500GB                     | 1         | 1      | 2.7%    |
| Corsair Force LE SSD 120GB                     | 1         | 2      | 2.7%    |
| AMD R3SL120G 120GB SSD                         | 1         | 1      | 2.7%    |
| A-DATA Technology SU800 128GB SSD              | 1         | 2      | 2.7%    |
| A-DATA Technology IM2P33F8ABR1-1TB             | 1         | 1      | 2.7%    |
| Unknown                                        | 1         | 1      | 2.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 6         | 6      | 16.67%  |
| WDC                 | 5         | 19     | 13.89%  |
| Seagate             | 5         | 6      | 13.89%  |
| Samsung Electronics | 4         | 6      | 11.11%  |
| HGST                | 3         | 3      | 8.33%   |
| Toshiba             | 2         | 2      | 5.56%   |
| A-DATA Technology   | 2         | 3      | 5.56%   |
| Secure              | 1         | 1      | 2.78%   |
| SanDisk             | 1         | 1      | 2.78%   |
| Netac               | 1         | 1      | 2.78%   |
| Micron Technology   | 1         | 1      | 2.78%   |
| Maxtor              | 1         | 1      | 2.78%   |
| Kingmax             | 1         | 1      | 2.78%   |
| Corsair             | 1         | 2      | 2.78%   |
| AMD                 | 1         | 1      | 2.78%   |
| Unknown             | 1         | 1      | 2.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 6         | 6      | 24%     |
| WDC                 | 5         | 18     | 20%     |
| Seagate             | 5         | 6      | 20%     |
| Samsung Electronics | 3         | 5      | 12%     |
| HGST                | 3         | 3      | 12%     |
| Toshiba             | 2         | 2      | 8%      |
| Maxtor              | 1         | 1      | 4%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 24        | 41     | 68.57%  |
| SSD  | 10        | 13     | 28.57%  |
| NVMe | 1         | 1      | 2.86%   |

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
| Works    | 143       | 296    | 55%     |
| Detected | 86        | 137    | 33.08%  |
| Malfunc  | 31        | 55     | 11.92%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 146       | 53.87%  |
| AMD                              | 34        | 12.55%  |
| Samsung Electronics              | 21        | 7.75%   |
| SanDisk                          | 12        | 4.43%   |
| Toshiba America Info Systems     | 6         | 2.21%   |
| SK hynix                         | 5         | 1.85%   |
| VIA Technologies                 | 4         | 1.48%   |
| Realtek Semiconductor            | 4         | 1.48%   |
| Marvell Technology Group         | 4         | 1.48%   |
| LSI Logic / Symbios Logic        | 4         | 1.48%   |
| ASMedia Technology               | 4         | 1.48%   |
| ADATA Technology                 | 4         | 1.48%   |
| Nvidia                           | 3         | 1.11%   |
| Micron Technology                | 3         | 1.11%   |
| Adaptec                          | 3         | 1.11%   |
| Micron/Crucial Technology        | 2         | 0.74%   |
| KIOXIA                           | 2         | 0.74%   |
| Kingston Technology Company      | 2         | 0.74%   |
| Hewlett-Packard                  | 2         | 0.74%   |
| Silicon Motion                   | 1         | 0.37%   |
| Silicon Integrated Systems [SiS] | 1         | 0.37%   |
| Promise Technology               | 1         | 0.37%   |
| Phison Electronics               | 1         | 0.37%   |
| Loongson Technology              | 1         | 0.37%   |
| Broadcom / LSI                   | 1         | 0.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 24        | 7.36%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 14        | 4.29%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 11        | 3.37%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 10        | 3.07%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 8         | 2.45%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 7         | 2.15%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 6         | 1.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 6         | 1.84%   |
| Intel Comet Lake SATA AHCI Controller                                          | 5         | 1.53%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 5         | 1.53%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 1.53%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 5         | 1.53%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 5         | 1.53%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 5         | 1.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5         | 1.53%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 4         | 1.23%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.23%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 4         | 1.23%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 4         | 1.23%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 1.23%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 1.23%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 4         | 1.23%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 4         | 1.23%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 1.23%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4         | 1.23%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 4         | 1.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 1.23%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 3         | 0.92%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 3         | 0.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 0.92%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller               | 3         | 0.92%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 0.92%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 3         | 0.92%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 3         | 0.92%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 3         | 0.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 0.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 0.92%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 3         | 0.92%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3         | 0.92%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 3         | 0.92%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 153       | 57.09%  |
| NVMe | 57        | 21.27%  |
| IDE  | 37        | 13.81%  |
| RAID | 16        | 5.97%   |
| SAS  | 5         | 1.87%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 182       | 77.78%  |
| AMD          | 38        | 16.24%  |
| ARM          | 9         | 3.85%   |
| CentaurHauls | 2         | 0.85%   |
| Loongson     | 1         | 0.43%   |
| iSH          | 1         | 0.43%   |
| Unknown      | 1         | 0.43%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 1.63%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 4         | 1.63%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 1.22%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 1.22%   |
| Intel Celeron CPU N2807 @ 1.58GHz             | 3         | 1.22%   |
| ARM Processor                                 | 3         | 1.22%   |
| AMD G-T48E Processor                          | 3         | 1.22%   |
| Intel Xeon CPU L5640 @ 2.27GHz                | 2         | 0.82%   |
| Intel Pentium M processor 1.70GHz             | 2         | 0.82%   |
| Intel Pentium III (Coppermine)                | 2         | 0.82%   |
| Intel Core i9-10900 CPU @ 2.80GHz             | 2         | 0.82%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 2         | 0.82%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 2         | 0.82%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 0.82%   |
| Intel Core i5-4590T CPU @ 2.00GHz             | 2         | 0.82%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 2         | 0.82%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.82%   |
| Intel Core i5-3470T CPU @ 2.90GHz             | 2         | 0.82%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 2         | 0.82%   |
| Intel Core i3-4150 CPU @ 3.50GHz              | 2         | 0.82%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 0.82%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 0.82%   |
| Intel Celeron CPU J3455 @ 1.50GHz             | 2         | 0.82%   |
| Intel Celeron CPU J1900 @ 1.99GHz             | 2         | 0.82%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 2         | 0.82%   |
| Intel Atom CPU D525 @ 1.80GHz                 | 2         | 0.82%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 0.82%   |
| ARM BCM2835 Processor                         | 2         | 0.82%   |
| ARM AArch64 Processor rev 4 (aarch64)         | 2         | 0.82%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 2         | 0.82%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 0.82%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 0.82%   |
| AMD GX-415GA SOC with Radeon HD Graphics      | 2         | 0.82%   |
| AMD FX-8350 Eight-Core Processor              | 2         | 0.82%   |
| Loongson Loongson 3A                          | 1         | 0.41%   |
| iSH Processor                                 | 1         | 0.41%   |
| Intel Xeon Gold 6336Y CPU @ 2.40GHz           | 1         | 0.41%   |
| Intel Xeon Gold 5218 CPU @ 2.30GHz            | 1         | 0.41%   |
| Intel Xeon Gold 5120 CPU @ 2.20GHz            | 1         | 0.41%   |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 1         | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                 | Computers | Percent |
|-----------------------|-----------|---------|
| Intel Core i5         | 46        | 19.01%  |
| Intel Core i7         | 28        | 11.57%  |
| Other                 | 27        | 11.16%  |
| Intel Celeron         | 21        | 8.68%   |
| Intel Core i3         | 16        | 6.61%   |
| Intel Atom            | 15        | 6.2%    |
| Intel Core 2 Duo      | 9         | 3.72%   |
| Intel Xeon            | 8         | 3.31%   |
| AMD Ryzen 5           | 7         | 2.89%   |
| Intel Pentium         | 5         | 2.07%   |
| AMD Ryzen 7           | 5         | 2.07%   |
| Intel Pentium M       | 4         | 1.65%   |
| Intel Genuine         | 3         | 1.24%   |
| Intel Core i9         | 3         | 1.24%   |
| AMD Ryzen 9           | 3         | 1.24%   |
| AMD G                 | 3         | 1.24%   |
| AMD A6                | 3         | 1.24%   |
| Intel Xeon Gold       | 2         | 0.83%   |
| Intel Pentium III     | 2         | 0.83%   |
| Intel Pentium Dual    | 2         | 0.83%   |
| Intel Core 2          | 2         | 0.83%   |
| ARM BCM               | 2         | 0.83%   |
| ARM AArch64           | 2         | 0.83%   |
| AMD Ryzen 3           | 2         | 0.83%   |
| AMD GX                | 2         | 0.83%   |
| AMD FX                | 2         | 0.83%   |
| AMD A4                | 2         | 0.83%   |
| Intel Pentium Gold    | 1         | 0.41%   |
| Intel Core Solo       | 1         | 0.41%   |
| Intel Core m3         | 1         | 0.41%   |
| Intel Core Duo        | 1         | 0.41%   |
| Intel Core 2 Quad     | 1         | 0.41%   |
| Intel Core            | 1         | 0.41%   |
| Intel Celeron M       | 1         | 0.41%   |
| CentaurHauls VIA Eden | 1         | 0.41%   |
| ARM ARMv7             | 1         | 0.41%   |
| AMD Turion 64 Mobile  | 1         | 0.41%   |
| AMD Sempron           | 1         | 0.41%   |
| AMD E2                | 1         | 0.41%   |
| AMD E1                | 1         | 0.41%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 94        | 39%     |
| 4       | 83        | 34.44%  |
| 1       | 21        | 8.71%   |
| 6       | 8         | 3.32%   |
| Unknown | 8         | 3.32%   |
| 12      | 7         | 2.9%    |
| 8       | 7         | 2.9%    |
| 10      | 4         | 1.66%   |
| 16      | 3         | 1.24%   |
| 48      | 1         | 0.41%   |
| 32      | 1         | 0.41%   |
| 28      | 1         | 0.41%   |
| 24      | 1         | 0.41%   |
| 14      | 1         | 0.41%   |
| 3       | 1         | 0.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 218       | 93.56%  |
| Unknown | 8         | 3.43%   |
| 2       | 5         | 2.15%   |
| 0       | 2         | 0.86%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 116       | 49.57%  |
| 1       | 110       | 47.01%  |
| Unknown | 8         | 3.42%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 116       | 49.36%  |
| Unknown        | 113       | 48.09%  |
| 32-bit         | 5         | 2.13%   |
| 64-bit         | 1         | 0.43%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 160       | 64.52%  |
| 0x306c3    | 8         | 3.23%   |
| 0x306a9    | 5         | 2.02%   |
| 0x30678    | 5         | 2.02%   |
| 0x906ea    | 4         | 1.61%   |
| 0x20655    | 4         | 1.61%   |
| 0x106ca    | 4         | 1.61%   |
| 0x506e3    | 3         | 1.21%   |
| 0x206c2    | 3         | 1.21%   |
| 0x08108109 | 3         | 1.21%   |
| 0x05000101 | 3         | 1.21%   |
| 0x806eb    | 2         | 0.81%   |
| 0x806c1    | 2         | 0.81%   |
| 0x506c9    | 2         | 0.81%   |
| 0x406c4    | 2         | 0.81%   |
| 0x206a7    | 2         | 0.81%   |
| 0x106e5    | 2         | 0.81%   |
| 0x1067a    | 2         | 0.81%   |
| 0x08108102 | 2         | 0.81%   |
| 0x06006704 | 2         | 0.81%   |
| 0xb0671    | 1         | 0.4%    |
| 0xa0671    | 1         | 0.4%    |
| 0xa0655    | 1         | 0.4%    |
| 0xa0652    | 1         | 0.4%    |
| 0x906a3    | 1         | 0.4%    |
| 0x90672    | 1         | 0.4%    |
| 0x806ec    | 1         | 0.4%    |
| 0x806ea    | 1         | 0.4%    |
| 0x706e5    | 1         | 0.4%    |
| 0x6fd      | 1         | 0.4%    |
| 0x6f2      | 1         | 0.4%    |
| 0x6d8      | 1         | 0.4%    |
| 0x68a      | 1         | 0.4%    |
| 0x683      | 1         | 0.4%    |
| 0x606a6    | 1         | 0.4%    |
| 0x306d4    | 1         | 0.4%    |
| 0x0a20120e | 1         | 0.4%    |
| 0x08701030 | 1         | 0.4%    |
| 0x08701021 | 1         | 0.4%    |
| 0x08608103 | 1         | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 27        | 11.11%  |
| Haswell          | 22        | 9.05%   |
| Unknown          | 22        | 9.05%   |
| Silvermont       | 20        | 8.23%   |
| Skylake          | 12        | 4.94%   |
| IvyBridge        | 12        | 4.94%   |
| P6               | 10        | 4.12%   |
| Westmere         | 9         | 3.7%    |
| SandyBridge      | 9         | 3.7%    |
| Penryn           | 9         | 3.7%    |
| Core             | 8         | 3.29%   |
| Broadwell        | 8         | 3.29%   |
| Bonnell          | 7         | 2.88%   |
| Alderlake Hybrid | 7         | 2.88%   |
| Zen+             | 6         | 2.47%   |
| Jaguar           | 5         | 2.06%   |
| IceLake          | 5         | 2.06%   |
| Goldmont         | 5         | 2.06%   |
| Zen 3            | 4         | 1.65%   |
| TigerLake        | 4         | 1.65%   |
| Excavator        | 4         | 1.65%   |
| CometLake        | 4         | 1.65%   |
| Bobcat           | 4         | 1.65%   |
| Zen 2            | 3         | 1.23%   |
| Piledriver       | 3         | 1.23%   |
| Goldmont plus    | 3         | 1.23%   |
| Zen              | 2         | 0.82%   |
| Nehalem          | 2         | 0.82%   |
| K8 Hammer        | 2         | 0.82%   |
| K10              | 2         | 0.82%   |
| Puma             | 1         | 0.41%   |
| K6               | 1         | 0.41%   |
| Gracemont        | 1         | 0.41%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 151       | 59.68%  |
| AMD                        | 57        | 22.53%  |
| Nvidia                     | 31        | 12.25%  |
| Matrox Electronics Systems | 5         | 1.98%   |
| VIA Technologies           | 4         | 1.58%   |
| Neomagic                   | 2         | 0.79%   |
| ASPEED Technology          | 2         | 0.79%   |
| S3 Graphics                | 1         | 0.4%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 12        | 4.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 11        | 3.82%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 3.13%   |
| Intel UHD Graphics 620                                                                   | 8         | 2.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 2.78%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 2.08%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6         | 2.08%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5         | 1.74%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 1.74%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 1.74%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 1.74%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 1.74%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 1.39%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 1.39%   |
| Intel HD Graphics 5500                                                                   | 4         | 1.39%   |
| Intel HD Graphics 500                                                                    | 4         | 1.39%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.39%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 1.39%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4         | 1.39%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.04%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 1.04%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 1.04%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 3         | 1.04%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.04%   |
| Intel HD Graphics 630                                                                    | 3         | 1.04%   |
| Intel HD Graphics 530                                                                    | 3         | 1.04%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.04%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 3         | 1.04%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.04%   |
| AMD ES1000                                                                               | 3         | 1.04%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.69%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.69%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 2         | 0.69%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.69%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.69%   |
| Intel HD Graphics 620                                                                    | 2         | 0.69%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 0.69%   |
| Intel AlderLake-S GT1                                                                    | 2         | 0.69%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 2         | 0.69%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 118       | 49.58%  |
| 1 x AMD         | 47        | 19.75%  |
| Intel + Nvidia  | 18        | 7.56%   |
| Other           | 13        | 5.46%   |
| 1 x Nvidia      | 10        | 4.2%    |
| 2 x Intel       | 9         | 3.78%   |
| Intel + AMD     | 6         | 2.52%   |
| 1 x Matrox      | 4         | 1.68%   |
| 1 x VIA         | 3         | 1.26%   |
| 1 x Neomagic    | 2         | 0.84%   |
| 1 x ASPEED      | 2         | 0.84%   |
| AMD + Nvidia    | 2         | 0.84%   |
| 2 x AMD         | 1         | 0.42%   |
| 1 x S3 Graphics | 1         | 0.42%   |
| Nvidia + Matrox | 1         | 0.42%   |
| AMD + VIA       | 1         | 0.42%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 196       | 82.7%   |
| Unknown     | 37        | 15.61%  |
| Proprietary | 4         | 1.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 192       | 81.7%   |
| 0.01-0.5   | 21        | 8.94%   |
| 1.01-2.0   | 8         | 3.4%    |
| 0.51-1.0   | 5         | 2.13%   |
| 7.01-8.0   | 4         | 1.7%    |
| 3.01-4.0   | 2         | 0.85%   |
| 2.01-3.0   | 1         | 0.43%   |
| 16.01-24.0 | 1         | 0.43%   |
| 8.01-16.0  | 1         | 0.43%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 26        | 12.94%  |
| LG Display              | 21        | 10.45%  |
| Samsung Electronics     | 17        | 8.46%   |
| BOE                     | 16        | 7.96%   |
| Dell                    | 12        | 5.97%   |
| Goldstar                | 11        | 5.47%   |
| Chimei Innolux          | 11        | 5.47%   |
| BenQ                    | 7         | 3.48%   |
| AOC                     | 7         | 3.48%   |
| Hewlett-Packard         | 5         | 2.49%   |
| Apple                   | 5         | 2.49%   |
| Acer                    | 5         | 2.49%   |
| LG Philips              | 4         | 1.99%   |
| Lenovo                  | 4         | 1.99%   |
| Sony                    | 3         | 1.49%   |
| Sharp                   | 3         | 1.49%   |
| InfoVision              | 3         | 1.49%   |
| Chi Mei Optoelectronics | 3         | 1.49%   |
| ASUSTek Computer        | 3         | 1.49%   |
| Vizio                   | 2         | 1%      |
| Philips                 | 2         | 1%      |
| PANDA                   | 2         | 1%      |
| Jean                    | 2         | 1%      |
| HannStar                | 2         | 1%      |
| CSO                     | 2         | 1%      |
| Belinea                 | 2         | 1%      |
| ViewSonic               | 1         | 0.5%    |
| Toshiba                 | 1         | 0.5%    |
| SKY                     | 1         | 0.5%    |
| Sceptre Tech            | 1         | 0.5%    |
| Quanta Display          | 1         | 0.5%    |
| ONN                     | 1         | 0.5%    |
| Mi                      | 1         | 0.5%    |
| KVM                     | 1         | 0.5%    |
| Huion                   | 1         | 0.5%    |
| HJW                     | 1         | 0.5%    |
| HCL                     | 1         | 0.5%    |
| Envision                | 1         | 0.5%    |
| Elo Touch               | 1         | 0.5%    |
| Element                 | 1         | 0.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0597 1920x1080 294x165mm 13.3-inch           | 4         | 1.81%   |
| Samsung Electronics SE790C SAM0BFE 3440x1440 797x333mm 34.0-inch       | 3         | 1.36%   |
| Dell 2009W DEL4041 1680x1050 433x270mm 20.1-inch                       | 3         | 1.36%   |
| BOE LCD Monitor BOE08D5 1920x1080 344x194mm 15.5-inch                  | 3         | 1.36%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch            | 2         | 0.9%    |
| Jean JT229x6-4 JEN51C6 1680x1050 474x297mm 22.0-inch                   | 2         | 0.9%    |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch              | 2         | 0.9%    |
| Goldstar W2253 GSM56DD 1920x1080 510x290mm 23.1-inch                   | 2         | 0.9%    |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                  | 2         | 0.9%    |
| BenQ E2200HD BNQ790B 1920x1080 476x268mm 21.5-inch                     | 2         | 0.9%    |
| Belinea B101555 MAX05DF 1024x768 304x228mm 15.0-inch                   | 2         | 0.9%    |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch          | 2         | 0.9%    |
| Vizio VX42L HDTV10A VIZ0030 1366x768 930x523mm 42.0-inch               | 1         | 0.45%   |
| Vizio D43f-J04 VIZ1044 1920x1080 527x296mm 23.8-inch                   | 1         | 0.45%   |
| ViewSonic VG2030wm VSCA51E 1680x1050 433x270mm 20.1-inch               | 1         | 0.45%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                  | 1         | 0.45%   |
| Sony TV SNY1503 1360x768                                               | 1         | 0.45%   |
| Sony TV *02 SNY9703 1920x1080 1218x685mm 55.0-inch                     | 1         | 0.45%   |
| Sony LCD Monitor SNY06FA 1600x900 380x210mm 17.1-inch                  | 1         | 0.45%   |
| SKY TV-monitor SKY0001 1920x1080 890x500mm 40.2-inch                   | 1         | 0.45%   |
| Sharp LCD Monitor SHP1513 1920x1080 309x174mm 14.0-inch                | 1         | 0.45%   |
| Sharp LCD Monitor SHP14AF 1920x1200 288x180mm 13.4-inch                | 1         | 0.45%   |
| Sharp LCD Monitor SHP14AE 1920x1080 294x165mm 13.3-inch                | 1         | 0.45%   |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 526x296mm 23.8-inch         | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM0320 1680x1050 474x296mm 22.0-inch   | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch   | 1         | 0.45%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch      | 1         | 0.45%   |
| Samsung Electronics S27A950D SAM079E 1920x1080 598x336mm 27.0-inch     | 1         | 0.45%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 1         | 0.45%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 477x268mm 21.5-inch      | 1         | 0.45%   |
| Samsung Electronics LS24AG30x SAM7179 1920x1080 527x296mm 23.8-inch    | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC5A42 1366x768 309x174mm 14.0-inch   | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC5642 1280x768 305x183mm 14.0-inch   | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch   | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch   | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch  | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SDC4147 3840x2160 294x165mm 13.3-inch  | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch   | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1060x626mm 48.5-inch | 1         | 0.45%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch    | 1         | 0.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 66        | 34.38%  |
| 1366x768 (WXGA)    | 42        | 21.88%  |
| 3840x2160 (4K)     | 9         | 4.69%   |
| 1280x800 (WXGA)    | 9         | 4.69%   |
| 1680x1050 (WSXGA+) | 8         | 4.17%   |
| 2560x1440 (QHD)    | 7         | 3.65%   |
| 1280x1024 (SXGA)   | 7         | 3.65%   |
| 1024x768 (XGA)     | 6         | 3.13%   |
| 3440x1440          | 5         | 2.6%    |
| 1600x900 (HD+)     | 5         | 2.6%    |
| 1920x1200 (WUXGA)  | 4         | 2.08%   |
| 1440x900 (WXGA+)   | 4         | 2.08%   |
| 1360x768           | 4         | 2.08%   |
| 1024x600           | 4         | 2.08%   |
| 2880x1800          | 3         | 1.56%   |
| 2560x1080          | 2         | 1.04%   |
| 1280x768           | 2         | 1.04%   |
| 2560x1700          | 1         | 0.52%   |
| 2560x1600          | 1         | 0.52%   |
| 2240x1400          | 1         | 0.52%   |
| 1400x1050          | 1         | 0.52%   |
| 1280x960           | 1         | 0.52%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 47        | 23.5%   |
| 13     | 22        | 11%     |
| 14     | 18        | 9%      |
| 17     | 13        | 6.5%    |
| 27     | 12        | 6%      |
| 23     | 12        | 6%      |
| 21     | 8         | 4%      |
| 24     | 7         | 3.5%    |
| 11     | 7         | 3.5%    |
| 19     | 6         | 3%      |
| 12     | 6         | 3%      |
| 34     | 5         | 2.5%    |
| 22     | 5         | 2.5%    |
| 20     | 5         | 2.5%    |
| 31     | 4         | 2%      |
| 18     | 4         | 2%      |
| 10     | 4         | 2%      |
| 72     | 2         | 1%      |
| 40     | 2         | 1%      |
| 32     | 2         | 1%      |
| 25     | 2         | 1%      |
| 86     | 1         | 0.5%    |
| 65     | 1         | 0.5%    |
| 60     | 1         | 0.5%    |
| 48     | 1         | 0.5%    |
| 42     | 1         | 0.5%    |
| 29     | 1         | 0.5%    |
| 16     | 1         | 0.5%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 77        | 40.31%  |
| 501-600     | 29        | 15.18%  |
| 201-300     | 29        | 15.18%  |
| 401-500     | 22        | 11.52%  |
| 351-400     | 14        | 7.33%   |
| 701-800     | 6         | 3.14%   |
| 601-700     | 5         | 2.62%   |
| 1001-1500   | 4         | 2.09%   |
| 801-900     | 2         | 1.05%   |
| 1501-2000   | 2         | 1.05%   |
| 901-1000    | 1         | 0.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 127       | 70.56%  |
| 16/10 | 31        | 17.22%  |
| 5/4   | 7         | 3.89%   |
| 4/3   | 6         | 3.33%   |
| 21/9  | 6         | 3.33%   |
| 6/5   | 1         | 0.56%   |
| 3/2   | 1         | 0.56%   |
| 0.56  | 1         | 0.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 45        | 23.44%  |
| 81-90          | 30        | 15.63%  |
| 201-250        | 22        | 11.46%  |
| 151-200        | 15        | 7.81%   |
| 301-350        | 13        | 6.77%   |
| 71-80          | 11        | 5.73%   |
| 351-500        | 9         | 4.69%   |
| 51-60          | 7         | 3.65%   |
| 141-150        | 7         | 3.65%   |
| 121-130        | 7         | 3.65%   |
| More than 1000 | 6         | 3.13%   |
| 61-70          | 5         | 2.6%    |
| 41-50          | 4         | 2.08%   |
| 251-300        | 4         | 2.08%   |
| 501-1000       | 3         | 1.56%   |
| 131-140        | 2         | 1.04%   |
| 111-120        | 1         | 0.52%   |
| 91-100         | 1         | 0.52%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 57        | 31.32%  |
| 101-120       | 52        | 28.57%  |
| 121-160       | 46        | 25.27%  |
| 161-240       | 12        | 6.59%   |
| 1-50          | 11        | 6.04%   |
| More than 240 | 4         | 2.2%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 164       | 68.91%  |
| 0     | 58        | 24.37%  |
| 2     | 14        | 5.88%   |
| 4     | 1         | 0.42%   |
| 3     | 1         | 0.42%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 113       | 33.33%  |
| Intel                             | 104       | 30.68%  |
| Qualcomm Atheros                  | 36        | 10.62%  |
| Broadcom                          | 29        | 8.55%   |
| Marvell Technology Group          | 6         | 1.77%   |
| VIA Technologies                  | 4         | 1.18%   |
| Broadcom Limited                  | 4         | 1.18%   |
| Xiaomi                            | 3         | 0.88%   |
| TP-Link                           | 3         | 0.88%   |
| Qualcomm Atheros Communications   | 3         | 0.88%   |
| MediaTek                          | 3         | 0.88%   |
| ASIX Electronics                  | 3         | 0.88%   |
| Qualcomm                          | 2         | 0.59%   |
| Nvidia                            | 2         | 0.59%   |
| Microchip Technology              | 2         | 0.59%   |
| Mellanox Technologies             | 2         | 0.59%   |
| LSI                               | 2         | 0.59%   |
| T & A Mobile Phones               | 1         | 0.29%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.29%   |
| Sigma Designs                     | 1         | 0.29%   |
| Samsung Electronics               | 1         | 0.29%   |
| Raspberry Pi                      | 1         | 0.29%   |
| Ralink Technology                 | 1         | 0.29%   |
| Ralink                            | 1         | 0.29%   |
| QLogic                            | 1         | 0.29%   |
| QinHeng Electronics               | 1         | 0.29%   |
| NetGear                           | 1         | 0.29%   |
| Google                            | 1         | 0.29%   |
| Ericsson Business Mobile Networks | 1         | 0.29%   |
| Dresden Elektronik                | 1         | 0.29%   |
| DisplayLink                       | 1         | 0.29%   |
| D-Link System                     | 1         | 0.29%   |
| D-Link                            | 1         | 0.29%   |
| Belkin Components                 | 1         | 0.29%   |
| AMD                               | 1         | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 71        | 16.78%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 18        | 4.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 11        | 2.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 11        | 2.6%    |
| Intel Wireless 7265                                                     | 10        | 2.36%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 9         | 2.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.42%   |
| Intel Wireless 8265 / 8275                                              | 6         | 1.42%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 1.42%   |
| Intel Ethernet Controller I225-V                                        | 6         | 1.42%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 1.18%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.95%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 4         | 0.95%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 4         | 0.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 0.95%   |
| Intel Wireless 3160                                                     | 4         | 0.95%   |
| Intel I210 Gigabit Network Connection                                   | 4         | 0.95%   |
| Intel Ethernet Connection (2) I219-V                                    | 4         | 0.95%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 0.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 0.95%   |
| VIA VT6102/VT6103 [Rhine-II]                                            | 3         | 0.71%   |
| Realtek RTL8125 2.5GbE Controller                                       | 3         | 0.71%   |
| Qualcomm Atheros AR9271 802.11n                                         | 3         | 0.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 0.71%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 0.71%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 0.71%   |
| Intel I211 Gigabit Network Connection                                   | 3         | 0.71%   |
| Intel Ethernet Connection I217-LM                                       | 3         | 0.71%   |
| Intel Ethernet Connection (4) I219-LM                                   | 3         | 0.71%   |
| Intel Ethernet Connection (2) I219-LM                                   | 3         | 0.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 0.71%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 0.71%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 3         | 0.71%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 0.71%   |
| ASIX AX88179 Gigabit Ethernet                                           | 3         | 0.71%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                    | 2         | 0.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 0.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.47%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.47%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                           | 2         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 71        | 44.38%  |
| Qualcomm Atheros                | 30        | 18.75%  |
| Realtek Semiconductor           | 23        | 14.38%  |
| Broadcom                        | 17        | 10.63%  |
| TP-Link                         | 3         | 1.88%   |
| Qualcomm Atheros Communications | 3         | 1.88%   |
| MediaTek                        | 3         | 1.88%   |
| Broadcom Limited                | 3         | 1.88%   |
| VIA Technologies                | 1         | 0.63%   |
| Ralink Technology               | 1         | 0.63%   |
| Ralink                          | 1         | 0.63%   |
| NetGear                         | 1         | 0.63%   |
| Marvell Technology Group        | 1         | 0.63%   |
| D-Link                          | 1         | 0.63%   |
| Belkin Components               | 1         | 0.63%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 11        | 6.43%   |
| Intel Wireless 7265                                                     | 10        | 5.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 3.51%   |
| Intel Wireless 8265 / 8275                                              | 6         | 3.51%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 3.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 2.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 2.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 2.34%   |
| Intel Wireless 3160                                                     | 4         | 2.34%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 2.34%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 2.34%   |
| Qualcomm Atheros AR9271 802.11n                                         | 3         | 1.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 1.75%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 1.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 1.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.75%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.75%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 1.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.17%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 1.17%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.17%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 1.17%   |
| Intel Wireless 8260                                                     | 2         | 1.17%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 2         | 1.17%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 1.17%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 1.17%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 2         | 1.17%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 1.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.17%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 1.17%   |
| Broadcom Limited BCM4352 802.11ac Dual Band Wireless Network Adapter    | 2         | 1.17%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 2         | 1.17%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 1.17%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 1.17%   |
| VIA VIA USB2.0 WLAN                                                     | 1         | 0.58%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.58%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 1         | 0.58%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 103       | 46.82%  |
| Intel                            | 61        | 27.73%  |
| Broadcom                         | 17        | 7.73%   |
| Qualcomm Atheros                 | 9         | 4.09%   |
| Marvell Technology Group         | 5         | 2.27%   |
| Xiaomi                           | 3         | 1.36%   |
| VIA Technologies                 | 3         | 1.36%   |
| ASIX Electronics                 | 3         | 1.36%   |
| Qualcomm                         | 2         | 0.91%   |
| Nvidia                           | 2         | 0.91%   |
| Microchip Technology             | 2         | 0.91%   |
| Mellanox Technologies            | 2         | 0.91%   |
| T & A Mobile Phones              | 1         | 0.45%   |
| Silicon Integrated Systems [SiS] | 1         | 0.45%   |
| Samsung Electronics              | 1         | 0.45%   |
| Raspberry Pi                     | 1         | 0.45%   |
| LSI                              | 1         | 0.45%   |
| DisplayLink                      | 1         | 0.45%   |
| D-Link System                    | 1         | 0.45%   |
| Broadcom Limited                 | 1         | 0.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 71        | 29.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 18        | 7.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 11        | 4.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 9         | 3.77%   |
| Intel Ethernet Controller I225-V                                       | 6         | 2.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 4         | 1.67%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 4         | 1.67%   |
| Intel I210 Gigabit Network Connection                                  | 4         | 1.67%   |
| Intel Ethernet Connection (2) I219-V                                   | 4         | 1.67%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 3         | 1.26%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 1.26%   |
| Intel I211 Gigabit Network Connection                                  | 3         | 1.26%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 1.26%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 1.26%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3         | 1.26%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 1.26%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 2         | 0.84%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                          | 2         | 0.84%   |
| Intel Ethernet Controller I226-V                                       | 2         | 0.84%   |
| Intel Ethernet Connection (7) I219-V                                   | 2         | 0.84%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 0.84%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 0.84%   |
| Intel Ethernet Connection (17) I219-LM                                 | 2         | 0.84%   |
| Intel 82579V Gigabit Network Connection                                | 2         | 0.84%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                         | 2         | 0.84%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 2         | 0.84%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 0.84%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                       | 2         | 0.84%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 2         | 0.84%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.42%   |
| T & A Mobile Phones TCL 30 Z                                           | 1         | 0.42%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1         | 0.42%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.42%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 1         | 0.42%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 0.42%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.42%   |
| Raspberry Pi RP1 PCIe 2.0 South Bridge                                 | 1         | 0.42%   |
| Qualcomm POCO F3                                                       | 1         | 0.42%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.42%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 193       | 54.06%  |
| WiFi     | 151       | 42.3%   |
| Modem    | 10        | 2.8%    |
| Unknown  | 3         | 0.84%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 119       | 55.61%  |
| WiFi     | 95        | 44.39%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 114       | 48.31%  |
| 1     | 91        | 38.56%  |
| 0     | 18        | 7.63%   |
| 3     | 6         | 2.54%   |
| 4     | 4         | 1.69%   |
| 5     | 2         | 0.85%   |
| 12    | 1         | 0.42%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 176       | 74.89%  |
| Yes  | 59        | 25.11%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 51        | 41.46%  |
| Realtek Semiconductor           | 14        | 11.38%  |
| Qualcomm Atheros Communications | 10        | 8.13%   |
| IMC Networks                    | 8         | 6.5%    |
| Apple                           | 7         | 5.69%   |
| Broadcom                        | 6         | 4.88%   |
| Cambridge Silicon Radio         | 5         | 4.07%   |
| Foxconn / Hon Hai               | 4         | 3.25%   |
| Lite-On Technology              | 3         | 2.44%   |
| ASUSTek Computer                | 3         | 2.44%   |
| Marvell Semiconductor           | 2         | 1.63%   |
| Actions                         | 2         | 1.63%   |
| Toshiba                         | 1         | 0.81%   |
| MediaTek                        | 1         | 0.81%   |
| Hewlett-Packard                 | 1         | 0.81%   |
| Edimax Technology               | 1         | 0.81%   |
| Dell                            | 1         | 0.81%   |
| Askey Computer                  | 1         | 0.81%   |
| Alps Electric                   | 1         | 0.81%   |
| Unknown                         | 1         | 0.81%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 22        | 17.46%  |
| Realtek Bluetooth Radio                                                             | 10        | 7.94%   |
| Intel AX201 Bluetooth                                                               | 10        | 7.94%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 7         | 5.56%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 6         | 4.76%   |
| Intel AX200 Bluetooth                                                               | 5         | 3.97%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 5         | 3.97%   |
| Apple Bluetooth Host Controller                                                     | 4         | 3.17%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 2.38%   |
| Intel AX211 Bluetooth                                                               | 3         | 2.38%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 2.38%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 1.59%   |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 2         | 1.59%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.59%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 1.59%   |
| IMC Networks Wireless_Device                                                        | 2         | 1.59%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.59%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth                                     | 2         | 1.59%   |
| Broadcom HP Portable Bumble Bee                                                     | 2         | 1.59%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 1.59%   |
| Actions general adapter                                                             | 2         | 1.59%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.79%   |
| Realtek Bluetooth 5.3 Radio                                                         | 1         | 0.79%   |
| Realtek 802.11ac WLAN Adapter                                                       | 1         | 0.79%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.79%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.79%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.79%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.79%   |
| MediaTek Wireless_Device                                                            | 1         | 0.79%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.79%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.79%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.79%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.79%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.79%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 1         | 0.79%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.79%   |
| Edimax Bluetooth Adapter                                                            | 1         | 0.79%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 0.79%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.79%   |
| Broadcom BCM20702A0                                                                 | 1         | 0.79%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 159       | 62.6%   |
| AMD                                  | 53        | 20.87%  |
| Nvidia                               | 15        | 5.91%   |
| VIA Technologies                     | 4         | 1.57%   |
| Creative Labs                        | 3         | 1.18%   |
| C-Media Electronics                  | 3         | 1.18%   |
| Logitech                             | 2         | 0.79%   |
| Generalplus Technology               | 2         | 0.79%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.39%   |
| Texas Instruments                    | 1         | 0.39%   |
| SteelSeries ApS                      | 1         | 0.39%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.39%   |
| Sennheiser Communications            | 1         | 0.39%   |
| RODE Microphones                     | 1         | 0.39%   |
| Realtek Semiconductor                | 1         | 0.39%   |
| Nordic Semiconductor ASA             | 1         | 0.39%   |
| Native Instruments                   | 1         | 0.39%   |
| Loongson Technology                  | 1         | 0.39%   |
| Focusrite-Novation                   | 1         | 0.39%   |
| Cirrus Logic                         | 1         | 0.39%   |
| Apple                                | 1         | 0.39%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 14        | 4.2%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 13        | 3.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12        | 3.6%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 11        | 3.3%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 3.3%    |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 11        | 3.3%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10        | 3%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9         | 2.7%    |
| AMD FCH Azalia Controller                                                                         | 9         | 2.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 8         | 2.4%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8         | 2.4%    |
| Intel Cannon Lake PCH cAVS                                                                        | 7         | 2.1%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 2.1%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 2.1%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 2.1%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 7         | 2.1%    |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 1.8%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 1.5%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 1.5%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 5         | 1.5%    |
| Intel Broadwell-U Audio Controller                                                                | 5         | 1.5%    |
| Intel 8 Series HD Audio Controller                                                                | 5         | 1.5%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 5         | 1.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.2%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 1.2%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.2%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 1.2%    |
| AMD Wrestler HDMI Audio                                                                           | 4         | 1.2%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.2%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.2%    |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.9%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 0.9%    |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 0.9%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 0.9%    |
| Intel Alder Lake-S HD Audio Controller                                                            | 3         | 0.9%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 0.9%    |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3         | 0.9%    |
| AMD High Definition Audio Controller                                                              | 3         | 0.9%    |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 2         | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 40        | 17.24%  |
| Unknown             | 39        | 16.81%  |
| Samsung Electronics | 39        | 16.81%  |
| Micron Technology   | 22        | 9.48%   |
| Crucial             | 22        | 9.48%   |
| Kingston            | 13        | 5.6%    |
| Elpida              | 11        | 4.74%   |
| Corsair             | 8         | 3.45%   |
| Unknown             | 6         | 2.59%   |
| A-DATA Technology   | 5         | 2.16%   |
| Unknown (ABCD)      | 2         | 0.86%   |
| Transcend           | 2         | 0.86%   |
| Qimonda             | 2         | 0.86%   |
| Nanya Technology    | 2         | 0.86%   |
| GOODRAM             | 2         | 0.86%   |
| G.Skill             | 2         | 0.86%   |
| Visipro             | 1         | 0.43%   |
| Team                | 1         | 0.43%   |
| Smart Brazil        | 1         | 0.43%   |
| Smart               | 1         | 0.43%   |
| Ramaxel Technology  | 1         | 0.43%   |
| PNY                 | 1         | 0.43%   |
| Patriot             | 1         | 0.43%   |
| Novatech            | 1         | 0.43%   |
| Lexar               | 1         | 0.43%   |
| HPE                 | 1         | 0.43%   |
| Hewlett-Packard     | 1         | 0.43%   |
| Gold Key            | 1         | 0.43%   |
| Cors                | 1         | 0.43%   |
| Avant               | 1         | 0.43%   |
| Apacer              | 1         | 0.43%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 6         | 2.33%   |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 4         | 1.56%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 3         | 1.17%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 1.17%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 0.78%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 2         | 0.78%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 2         | 0.78%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 2         | 0.78%   |
| Unknown RAM Module 1GB SODIMM DRAM                               | 2         | 0.78%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 2         | 0.78%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 2         | 0.78%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.78%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.78%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 0.78%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 2         | 0.78%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.78%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1333MT/s            | 2         | 0.78%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 2         | 0.78%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 0.78%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.78%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.78%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM 1600MT/s                   | 2         | 0.78%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s            | 2         | 0.78%   |
| Elpida RAM EBJ41UF8BDW0-GN-F 4GB DIMM DDR3 1600MT/s              | 2         | 0.78%   |
| Crucial RAM BL16G36C16U4B.M16FE1 16GB DIMM DDR4 3600MT/s         | 2         | 0.78%   |
| Visipro RAM T2G88S1-H9H 2GB DIMM DDR3 1333MT/s                   | 1         | 0.39%   |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 0.39%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 0.39%   |
| Unknown RAM Module 512MB SODIMM DRAM                             | 1         | 0.39%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.39%   |
| Unknown RAM Module 512MB DIMM                                    | 1         | 0.39%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 1         | 0.39%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 0.39%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 0.39%   |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 1         | 0.39%   |
| Unknown RAM Module 2GB SODIMM LPDDR4 2133MT/s                    | 1         | 0.39%   |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                         | 1         | 0.39%   |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 1         | 0.39%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 0.39%   |
| Unknown RAM Module 256MB SODIMM DDR                              | 1         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 82        | 43.85%  |
| DDR4    | 51        | 27.27%  |
| LPDDR3  | 12        | 6.42%   |
| SDRAM   | 10        | 5.35%   |
| DDR2    | 9         | 4.81%   |
| DDR     | 7         | 3.74%   |
| LPDDR4  | 5         | 2.67%   |
| Unknown | 4         | 2.14%   |
| DRAM    | 3         | 1.6%    |
| DDR5    | 3         | 1.6%    |
| EEPROM  | 1         | 0.53%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 105       | 56.15%  |
| DIMM         | 62        | 33.16%  |
| Row Of Chips | 14        | 7.49%   |
| Unknown      | 3         | 1.6%    |
| Chip         | 2         | 1.07%   |
| RIMM         | 1         | 0.53%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 61        | 29.9%   |
| 8192  | 53        | 25.98%  |
| 2048  | 37        | 18.14%  |
| 16384 | 17        | 8.33%   |
| 1024  | 17        | 8.33%   |
| 32768 | 8         | 3.92%   |
| 512   | 6         | 2.94%   |
| 128   | 3         | 1.47%   |
| 256   | 1         | 0.49%   |
| 1     | 1         | 0.49%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 53        | 25.6%   |
| 2667    | 19        | 9.18%   |
| Unknown | 16        | 7.73%   |
| 2400    | 15        | 7.25%   |
| 1333    | 15        | 7.25%   |
| 3200    | 14        | 6.76%   |
| 1867    | 10        | 4.83%   |
| 667     | 10        | 4.83%   |
| 2133    | 9         | 4.35%   |
| 1334    | 7         | 3.38%   |
| 3600    | 5         | 2.42%   |
| 1067    | 5         | 2.42%   |
| 1066    | 3         | 1.45%   |
| 3800    | 2         | 0.97%   |
| 3266    | 2         | 0.97%   |
| 1866    | 2         | 0.97%   |
| 1800    | 2         | 0.97%   |
| 8400    | 1         | 0.48%   |
| 6000    | 1         | 0.48%   |
| 5808    | 1         | 0.48%   |
| 5600    | 1         | 0.48%   |
| 4800    | 1         | 0.48%   |
| 4267    | 1         | 0.48%   |
| 4199    | 1         | 0.48%   |
| 3666    | 1         | 0.48%   |
| 2666    | 1         | 0.48%   |
| 2200    | 1         | 0.48%   |
| 2048    | 1         | 0.48%   |
| 1400    | 1         | 0.48%   |
| 1331    | 1         | 0.48%   |
| 1200    | 1         | 0.48%   |
| 800     | 1         | 0.48%   |
| 533     | 1         | 0.48%   |
| 133     | 1         | 0.48%   |
| 33      | 1         | 0.48%   |

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
| Chicony Electronics                    | 23        | 19.49%  |
| Realtek Semiconductor                  | 14        | 11.86%  |
| Microdia                               | 10        | 8.47%   |
| IMC Networks                           | 10        | 8.47%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 7.63%   |
| Quanta                                 | 6         | 5.08%   |
| Bison Electronics                      | 6         | 5.08%   |
| Apple                                  | 5         | 4.24%   |
| Suyin                                  | 4         | 3.39%   |
| Acer                                   | 4         | 3.39%   |
| Syntek                                 | 3         | 2.54%   |
| Lite-On Technology                     | 3         | 2.54%   |
| Z-Star Microelectronics                | 2         | 1.69%   |
| Sunplus Innovation Technology          | 2         | 1.69%   |
| Silicon Motion                         | 2         | 1.69%   |
| Ricoh                                  | 2         | 1.69%   |
| Logitech                               | 2         | 1.69%   |
| Lenovo                                 | 2         | 1.69%   |
| Trust                                  | 1         | 0.85%   |
| Samsung Electronics                    | 1         | 0.85%   |
| Olympus Optical                        | 1         | 0.85%   |
| Microsoft                              | 1         | 0.85%   |
| MacroSilicon                           | 1         | 0.85%   |
| Luxvisions Innotech Limited            | 1         | 0.85%   |
| Linux Foundation                       | 1         | 0.85%   |
| Generalplus Technology                 | 1         | 0.85%   |
| Alcor Micro                            | 1         | 0.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                        | 5         | 4.1%    |
| Microdia Integrated_Webcam_HD                       | 5         | 4.1%    |
| Chicony Integrated Camera                           | 5         | 4.1%    |
| Realtek HP Webcam                                   | 3         | 2.46%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 3         | 2.46%   |
| IMC Networks Integrated Camera                      | 3         | 2.46%   |
| Chicony HP Wide Vision HD Camera                    | 3         | 2.46%   |
| Chicony HD Webcam                                   | 3         | 2.46%   |
| Realtek Integrated Webcam                           | 2         | 1.64%   |
| Realtek Acer 640 x 480 laptop camera                | 2         | 1.64%   |
| Quanta HD User Facing                               | 2         | 1.64%   |
| Microdia Laptop_Integrated_Webcam_2M                | 2         | 1.64%   |
| Lite-On TOSHIBA Web Camera - HD                     | 2         | 1.64%   |
| Lenovo Integrated Webcam                            | 2         | 1.64%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 2         | 1.64%   |
| Chicony 2.0M UVC Webcam / CNF7129                   | 2         | 1.64%   |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 2         | 1.64%   |
| Bison Integrated Camera                             | 2         | 1.64%   |
| Apple FaceTime HD Camera (Built-in)                 | 2         | 1.64%   |
| Z-Star Vimicro USB2.0 Camera                        | 1         | 0.82%   |
| Z-Star A4 TECH USB2.0 PC Camera J                   | 1         | 0.82%   |
| Trust QHD Webcam                                    | 1         | 0.82%   |
| Syntek Sonix 1.3MPixel USB 2.0 Camera               | 1         | 0.82%   |
| Syntek Integrated Camera                            | 1         | 0.82%   |
| Syntek EasyCamera                                   | 1         | 0.82%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.82%   |
| Suyin HP TrueVision HD                              | 1         | 0.82%   |
| Suyin HP High Definition 1MP Webcam                 | 1         | 0.82%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.82%   |
| Sunplus HP Universal Camera                         | 1         | 0.82%   |
| Sunplus HD WebCam                                   | 1         | 0.82%   |
| Silicon Motion WebCam SC-03FFL11939N                | 1         | 0.82%   |
| Silicon Motion NCM-G102                             | 1         | 0.82%   |
| Samsung Galaxy series, misc. (MTP mode)             | 1         | 0.82%   |
| Ricoh Visual Communication Camera VGP-VCC3 [R5U870] | 1         | 0.82%   |
| Ricoh Pavilion Webcam [R5U870]                      | 1         | 0.82%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 0.82%   |
| Realtek USB Camera                                  | 1         | 0.82%   |
| Realtek Integrated_Webcam_FHD                       | 1         | 0.82%   |
| Quanta USB2.0 HD UVC WebCam                         | 1         | 0.82%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 5         | 33.33%  |
| Validity Sensors           | 4         | 26.67%  |
| AuthenTec                  | 3         | 20%     |
| STMicroelectronics         | 2         | 13.33%  |
| Shenzhen Goodix Technology | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AuthenTec AES2810                                                          | 3         | 20%     |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 13.33%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 13.33%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 13.33%  |
| STMicroelectronics Fingerprint Reader                                      | 2         | 13.33%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 6.67%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 6.67%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 6.67%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 6.67%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 2         | 66.67%  |
| Lenovo      | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 2         | 66.67%  |
| Lenovo Integrated Smart Card Reader | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 148       | 60.66%  |
| 1     | 59        | 24.18%  |
| 2     | 27        | 11.07%  |
| 3     | 5         | 2.05%   |
| 4     | 4         | 1.64%   |
| 7     | 1         | 0.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 46        | 32.17%  |
| Communication controller | 18        | 12.59%  |
| Fingerprint reader       | 14        | 9.79%   |
| Net/wireless             | 12        | 8.39%   |
| Modem                    | 8         | 5.59%   |
| Multimedia controller    | 7         | 4.9%    |
| Camera                   | 7         | 4.9%    |
| Bluetooth                | 7         | 4.9%    |
| Card reader              | 5         | 3.5%    |
| Unassigned class         | 3         | 2.1%    |
| Network                  | 3         | 2.1%    |
| Chipcard                 | 3         | 2.1%    |
| Storage/ata              | 2         | 1.4%    |
| Storage                  | 2         | 1.4%    |
| Sound                    | 2         | 1.4%    |
| Net/ethernet             | 2         | 1.4%    |
| Unclassified device      | 1         | 0.7%    |
| Flash memory             | 1         | 0.7%    |


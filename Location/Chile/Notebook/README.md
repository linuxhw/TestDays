Linux in Chile - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Chile.

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

Total: 1136

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | ZBook Power 15.6 inch G8... | [e49b5301ae](https://linux-hardware.org/?probe=e49b5301ae) | May 08, 2024 |
| HP            | ZBook Power 15.6 inch G8... | [8acc6c69a3](https://linux-hardware.org/?probe=8acc6c69a3) | May 08, 2024 |
| HP            | EliteBook 840 G2            | [76e6f087bb](https://linux-hardware.org/?probe=76e6f087bb) | May 08, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [3292b37df6](https://linux-hardware.org/?probe=3292b37df6) | May 08, 2024 |
| Dell          | Latitude 7480               | [124ec816c7](https://linux-hardware.org/?probe=124ec816c7) | May 05, 2024 |
| Unknown       | Unknown                     | [53c592f858](https://linux-hardware.org/?probe=53c592f858) | May 04, 2024 |
| ASUSTek       | X555LB                      | [31db777b68](https://linux-hardware.org/?probe=31db777b68) | May 04, 2024 |
| Unknown       | Unknown                     | [3f7e899e58](https://linux-hardware.org/?probe=3f7e899e58) | May 04, 2024 |
| HP            | 1000                        | [5cbdf4ea65](https://linux-hardware.org/?probe=5cbdf4ea65) | May 03, 2024 |
| Dell          | System XPS L502X            | [ba86210a01](https://linux-hardware.org/?probe=ba86210a01) | May 02, 2024 |
| HP            | 1000                        | [57f342d3ff](https://linux-hardware.org/?probe=57f342d3ff) | May 02, 2024 |
| HP            | 250 G6 Notebook PC          | [ff4a31241b](https://linux-hardware.org/?probe=ff4a31241b) | May 02, 2024 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | [060878050f](https://linux-hardware.org/?probe=060878050f) | Apr 30, 2024 |
| Samsung       | 750XED                      | [d4c8fa3bde](https://linux-hardware.org/?probe=d4c8fa3bde) | Apr 29, 2024 |
| Samsung       | 750XED                      | [37fcaff384](https://linux-hardware.org/?probe=37fcaff384) | Apr 29, 2024 |
| Dell          | Inspiron 5459               | [b63833a7b2](https://linux-hardware.org/?probe=b63833a7b2) | Apr 28, 2024 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [814f4429a4](https://linux-hardware.org/?probe=814f4429a4) | Apr 27, 2024 |
| Dell          | Latitude 3420               | [c0bc583333](https://linux-hardware.org/?probe=c0bc583333) | Apr 26, 2024 |
| Dell          | Latitude 3420               | [522bdc6fd0](https://linux-hardware.org/?probe=522bdc6fd0) | Apr 26, 2024 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [537da6819a](https://linux-hardware.org/?probe=537da6819a) | Apr 25, 2024 |
| HP            | ENVY 15                     | [20cb7a828b](https://linux-hardware.org/?probe=20cb7a828b) | Apr 24, 2024 |
| Dell          | System XPS L502X            | [1546699c7b](https://linux-hardware.org/?probe=1546699c7b) | Apr 24, 2024 |
| Unknown       | Unknown                     | [def20611a4](https://linux-hardware.org/?probe=def20611a4) | Apr 23, 2024 |
| Acer          | Aspire A515-52G             | [9ee2e8d42a](https://linux-hardware.org/?probe=9ee2e8d42a) | Apr 23, 2024 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [cfba8255a3](https://linux-hardware.org/?probe=cfba8255a3) | Apr 22, 2024 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [d89b09df70](https://linux-hardware.org/?probe=d89b09df70) | Apr 19, 2024 |
| Acer          | V5-131                      | [5ca622b910](https://linux-hardware.org/?probe=5ca622b910) | Apr 18, 2024 |
| Acer          | V5-131                      | [984da3beb5](https://linux-hardware.org/?probe=984da3beb5) | Apr 18, 2024 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | [d7cf8c586e](https://linux-hardware.org/?probe=d7cf8c586e) | Apr 16, 2024 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | [8ef5274513](https://linux-hardware.org/?probe=8ef5274513) | Apr 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M360... | [25a93e1b63](https://linux-hardware.org/?probe=25a93e1b63) | Apr 14, 2024 |
| HP            | Pavilion dv6000 (GM695LA... | [21796df3a5](https://linux-hardware.org/?probe=21796df3a5) | Apr 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M360... | [f6d12e0e88](https://linux-hardware.org/?probe=f6d12e0e88) | Apr 13, 2024 |
| Dell          | Inspiron 3458               | [550b5dcdc0](https://linux-hardware.org/?probe=550b5dcdc0) | Apr 12, 2024 |
| Dell          | Inspiron 3458               | [d263334708](https://linux-hardware.org/?probe=d263334708) | Apr 12, 2024 |
| HP            | ENVY Laptop 15-ep0xxx       | [65d523fbeb](https://linux-hardware.org/?probe=65d523fbeb) | Apr 10, 2024 |
| Dell          | Latitude 7290               | [b23f2a505a](https://linux-hardware.org/?probe=b23f2a505a) | Apr 10, 2024 |
| Lenovo        | IdeaPad S540-15IWL 81NE     | [5b676c4d65](https://linux-hardware.org/?probe=5b676c4d65) | Apr 09, 2024 |
| HP            | 240 G6 Notebook PC          | [00731ce19b](https://linux-hardware.org/?probe=00731ce19b) | Apr 07, 2024 |
| Dell          | Latitude 7480               | [60c813fedb](https://linux-hardware.org/?probe=60c813fedb) | Apr 06, 2024 |
| Dell          | Inspiron 5459               | [fb9702f65e](https://linux-hardware.org/?probe=fb9702f65e) | Apr 05, 2024 |
| HP            | ProBook 440 G8 Notebook ... | [99296143a7](https://linux-hardware.org/?probe=99296143a7) | Apr 03, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [2bb5c3d295](https://linux-hardware.org/?probe=2bb5c3d295) | Apr 03, 2024 |
| Wings Mobi... | Wings Book 1                | [532ae4633c](https://linux-hardware.org/?probe=532ae4633c) | Apr 02, 2024 |
| HP            | Pavilion Aero Laptop 13-... | [7f542aae1b](https://linux-hardware.org/?probe=7f542aae1b) | Apr 02, 2024 |
| HP            | Pavilion Aero Laptop 13-... | [0474c0e2a0](https://linux-hardware.org/?probe=0474c0e2a0) | Apr 02, 2024 |
| Dell          | System XPS L502X            | [e176a846de](https://linux-hardware.org/?probe=e176a846de) | Apr 01, 2024 |
| Dell          | System XPS L502X            | [ca3fdd569e](https://linux-hardware.org/?probe=ca3fdd569e) | Mar 31, 2024 |
| Sony          | SVF14221CLW                 | [a6a658aa9b](https://linux-hardware.org/?probe=a6a658aa9b) | Mar 30, 2024 |
| Sony          | SVF14221CLW                 | [1530abd2d4](https://linux-hardware.org/?probe=1530abd2d4) | Mar 30, 2024 |
| Apple         | MacBookPro11,3              | [b90fd9c218](https://linux-hardware.org/?probe=b90fd9c218) | Mar 28, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [17ddcfee74](https://linux-hardware.org/?probe=17ddcfee74) | Mar 27, 2024 |
| HP            | ENVY 15                     | [11821b80b7](https://linux-hardware.org/?probe=11821b80b7) | Mar 26, 2024 |
| Samsung       | N100                        | [d7a66b3835](https://linux-hardware.org/?probe=d7a66b3835) | Mar 22, 2024 |
| Alienware     | 17 R2                       | [eb210f842b](https://linux-hardware.org/?probe=eb210f842b) | Mar 21, 2024 |
| Dell          | Latitude 7290               | [060d4f8054](https://linux-hardware.org/?probe=060d4f8054) | Mar 20, 2024 |
| Lenovo        | ThinkPad X280 20KEA03YCL    | [304f0db93a](https://linux-hardware.org/?probe=304f0db93a) | Mar 16, 2024 |
| HP            | Pavilion g4                 | [f36a2c4d30](https://linux-hardware.org/?probe=f36a2c4d30) | Mar 15, 2024 |
| ASUSTek       | X580VD                      | [f33436ccfe](https://linux-hardware.org/?probe=f33436ccfe) | Mar 13, 2024 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | [b3176660a1](https://linux-hardware.org/?probe=b3176660a1) | Mar 12, 2024 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | [25e788b418](https://linux-hardware.org/?probe=25e788b418) | Mar 12, 2024 |
| Lenovo        | G400s 20244                 | [dc5ea071de](https://linux-hardware.org/?probe=dc5ea071de) | Mar 12, 2024 |
| HP            | Compaq 8510p                | [9a70629877](https://linux-hardware.org/?probe=9a70629877) | Mar 09, 2024 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [c7b2c1d469](https://linux-hardware.org/?probe=c7b2c1d469) | Mar 08, 2024 |
| Acer          | Aspire A114-33              | [5201890093](https://linux-hardware.org/?probe=5201890093) | Mar 07, 2024 |
| Acer          | Aspire A515-54              | [d4f875966c](https://linux-hardware.org/?probe=d4f875966c) | Mar 06, 2024 |
| HP            | Notebook                    | [025b54a984](https://linux-hardware.org/?probe=025b54a984) | Mar 06, 2024 |
| HP            | Notebook                    | [5f90d8f25b](https://linux-hardware.org/?probe=5f90d8f25b) | Mar 06, 2024 |
| HP            | ENVY 15                     | [6f74377b0a](https://linux-hardware.org/?probe=6f74377b0a) | Mar 05, 2024 |
| HP            | ENVY 15                     | [86b5b9b7d7](https://linux-hardware.org/?probe=86b5b9b7d7) | Mar 04, 2024 |
| HP            | ENVY 15                     | [f8fc004a9c](https://linux-hardware.org/?probe=f8fc004a9c) | Mar 03, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | [a33280c60d](https://linux-hardware.org/?probe=a33280c60d) | Feb 28, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [c7441889f1](https://linux-hardware.org/?probe=c7441889f1) | Feb 26, 2024 |
| Lenovo        | ThinkPad X280 20KEA03YCL    | [039aae7236](https://linux-hardware.org/?probe=039aae7236) | Feb 24, 2024 |
| ASUSTek       | Zenbook UX3404VA_UX3404V... | [474d7d9a50](https://linux-hardware.org/?probe=474d7d9a50) | Feb 24, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | [8fe4f0e76d](https://linux-hardware.org/?probe=8fe4f0e76d) | Feb 22, 2024 |
| Acer          | Aspire A515-54              | [7a847ee2ac](https://linux-hardware.org/?probe=7a847ee2ac) | Feb 21, 2024 |
| Valve         | Jupiter                     | [cdcf85f04c](https://linux-hardware.org/?probe=cdcf85f04c) | Feb 21, 2024 |
| HP            | Pavilion Laptop 15-eh0xx... | [e843792ce5](https://linux-hardware.org/?probe=e843792ce5) | Feb 18, 2024 |
| HP            | Pavilion Laptop 15-eh0xx... | [63eec59f69](https://linux-hardware.org/?probe=63eec59f69) | Feb 18, 2024 |
| Lenovo        | Yoga 300-11IBY 80M0         | [ced438a574](https://linux-hardware.org/?probe=ced438a574) | Feb 17, 2024 |
| Sony          | VPCEE37FL                   | [611371a88b](https://linux-hardware.org/?probe=611371a88b) | Feb 16, 2024 |
| HP            | ENVY Laptop 15-ep0xxx       | [f8d949c6e1](https://linux-hardware.org/?probe=f8d949c6e1) | Feb 16, 2024 |
| HP            | ENVY Laptop 15-ep0xxx       | [dcd36d6705](https://linux-hardware.org/?probe=dcd36d6705) | Feb 16, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [44eb92e9e8](https://linux-hardware.org/?probe=44eb92e9e8) | Feb 11, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [27231005d1](https://linux-hardware.org/?probe=27231005d1) | Feb 11, 2024 |
| Dell          | Inspiron 5459               | [d40f482a25](https://linux-hardware.org/?probe=d40f482a25) | Feb 10, 2024 |
| ASUSTek       | Zenbook UX3404VA_UX3404V... | [17e2d4fc72](https://linux-hardware.org/?probe=17e2d4fc72) | Feb 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [2490245b2a](https://linux-hardware.org/?probe=2490245b2a) | Feb 10, 2024 |
| HP            | Pavilion g4                 | [ab845ec197](https://linux-hardware.org/?probe=ab845ec197) | Feb 06, 2024 |
| HP            | Pavilion m6                 | [f12679a936](https://linux-hardware.org/?probe=f12679a936) | Feb 03, 2024 |
| HP            | 240 G8 Notebook PC          | [d4c61a6527](https://linux-hardware.org/?probe=d4c61a6527) | Feb 01, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | [d743247f69](https://linux-hardware.org/?probe=d743247f69) | Jan 31, 2024 |
| ASUSTek       | X556UQK                     | [970dc5b87d](https://linux-hardware.org/?probe=970dc5b87d) | Jan 31, 2024 |
| HP            | 240 G8 Notebook PC          | [02a1844f63](https://linux-hardware.org/?probe=02a1844f63) | Jan 31, 2024 |
| Lenovo        | ThinkPad T495 20NKS1EP00    | [addeb3711c](https://linux-hardware.org/?probe=addeb3711c) | Jan 30, 2024 |
| Lenovo        | ThinkPad T490 20N3S8DK00    | [4e9cad214e](https://linux-hardware.org/?probe=4e9cad214e) | Jan 28, 2024 |
| HP            | 240 G8 Notebook PC          | [68364930e7](https://linux-hardware.org/?probe=68364930e7) | Jan 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [3bc0546f62](https://linux-hardware.org/?probe=3bc0546f62) | Jan 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [95692e9f04](https://linux-hardware.org/?probe=95692e9f04) | Jan 23, 2024 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [2c5947d48c](https://linux-hardware.org/?probe=2c5947d48c) | Jan 22, 2024 |
| HP            | Pavilion g4                 | [ecddd3e100](https://linux-hardware.org/?probe=ecddd3e100) | Jan 21, 2024 |
| Lenovo        | IdeaPad 320-14IKB 80XK      | [de30e068d6](https://linux-hardware.org/?probe=de30e068d6) | Jan 21, 2024 |
| Lenovo        | ThinkPad X280 20KEA03YCL    | [6d4961e126](https://linux-hardware.org/?probe=6d4961e126) | Jan 21, 2024 |
| HP            | ProBook 440 G5              | [1ad08b8198](https://linux-hardware.org/?probe=1ad08b8198) | Jan 21, 2024 |
| Acer          | Nitro AN517-54              | [e736d57544](https://linux-hardware.org/?probe=e736d57544) | Jan 18, 2024 |
| Sony          | VPCF120FL                   | [6ada0707e6](https://linux-hardware.org/?probe=6ada0707e6) | Jan 18, 2024 |
| Valve         | Jupiter                     | [5a872c599e](https://linux-hardware.org/?probe=5a872c599e) | Jan 15, 2024 |
| ASUSTek       | X542UQ                      | [80e9791b86](https://linux-hardware.org/?probe=80e9791b86) | Jan 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [68a601314f](https://linux-hardware.org/?probe=68a601314f) | Jan 10, 2024 |
| HP            | ProBook 440 G5              | [d7c1f42897](https://linux-hardware.org/?probe=d7c1f42897) | Jan 10, 2024 |
| HP            | 240 G6 Notebook PC          | [52fa49b647](https://linux-hardware.org/?probe=52fa49b647) | Jan 08, 2024 |
| HP            | Notebook                    | [79932769a2](https://linux-hardware.org/?probe=79932769a2) | Jan 08, 2024 |
| ASUSTek       | X542UA                      | [028b7c4d83](https://linux-hardware.org/?probe=028b7c4d83) | Jan 08, 2024 |
| Apple         | MacBook5,2                  | [2ed16f6a80](https://linux-hardware.org/?probe=2ed16f6a80) | Jan 07, 2024 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [4285b072d7](https://linux-hardware.org/?probe=4285b072d7) | Jan 05, 2024 |
| HP            | EliteBook 6930p             | [868c32afaa](https://linux-hardware.org/?probe=868c32afaa) | Jan 05, 2024 |
| ASUSTek       | X542UA                      | [5d7b076a1c](https://linux-hardware.org/?probe=5d7b076a1c) | Jan 05, 2024 |
| Lenovo        | IdeaPad S540-15IWL 81NE     | [65ef79e8a1](https://linux-hardware.org/?probe=65ef79e8a1) | Jan 04, 2024 |
| HP            | Notebook                    | [3db48f7d59](https://linux-hardware.org/?probe=3db48f7d59) | Jan 02, 2024 |
| HP            | ProBook 440 G5              | [04753e77e0](https://linux-hardware.org/?probe=04753e77e0) | Jan 02, 2024 |
| ASUSTek       | N551JW                      | [12339778af](https://linux-hardware.org/?probe=12339778af) | Dec 30, 2023 |
| Dell          | Latitude 7390               | [8c74383dab](https://linux-hardware.org/?probe=8c74383dab) | Dec 27, 2023 |
| Dell          | Latitude 7390               | [889337bb1c](https://linux-hardware.org/?probe=889337bb1c) | Dec 27, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [029b043cec](https://linux-hardware.org/?probe=029b043cec) | Dec 25, 2023 |
| Dell          | Latitude 7280               | [5397e7633e](https://linux-hardware.org/?probe=5397e7633e) | Dec 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E203... | [ae01ab2ebe](https://linux-hardware.org/?probe=ae01ab2ebe) | Dec 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [dbbab5f96b](https://linux-hardware.org/?probe=dbbab5f96b) | Dec 19, 2023 |
| Acer          | Aspire A515-57              | [f6f623f0d8](https://linux-hardware.org/?probe=f6f623f0d8) | Dec 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [5223e586fd](https://linux-hardware.org/?probe=5223e586fd) | Dec 15, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | [165e16505d](https://linux-hardware.org/?probe=165e16505d) | Dec 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [53ee047174](https://linux-hardware.org/?probe=53ee047174) | Dec 12, 2023 |
| HP            | ProBook 440 G5              | [af38b45c59](https://linux-hardware.org/?probe=af38b45c59) | Dec 12, 2023 |
| Acer          | V5-171                      | [79abc82869](https://linux-hardware.org/?probe=79abc82869) | Dec 11, 2023 |
| SK hynix      | HyBook                      | [cf29911599](https://linux-hardware.org/?probe=cf29911599) | Dec 11, 2023 |
| HP            | 245 G5 Notebook PC          | [f3abc9d11d](https://linux-hardware.org/?probe=f3abc9d11d) | Dec 05, 2023 |
| HP            | Notebook                    | [8d58f80f77](https://linux-hardware.org/?probe=8d58f80f77) | Dec 03, 2023 |
| ASUSTek       | K501UW                      | [bb2313602b](https://linux-hardware.org/?probe=bb2313602b) | Nov 29, 2023 |
| Valve         | Jupiter                     | [933ce1aa7d](https://linux-hardware.org/?probe=933ce1aa7d) | Nov 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [5b41f73363](https://linux-hardware.org/?probe=5b41f73363) | Nov 25, 2023 |
| ASUSTek       | K501UW                      | [4f1442fcc4](https://linux-hardware.org/?probe=4f1442fcc4) | Nov 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [f17333cca3](https://linux-hardware.org/?probe=f17333cca3) | Nov 24, 2023 |
| ASUSTek       | X456UV                      | [f38105228e](https://linux-hardware.org/?probe=f38105228e) | Nov 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [94962a7ceb](https://linux-hardware.org/?probe=94962a7ceb) | Nov 19, 2023 |
| ASUSTek       | N551JW                      | [b05c08e4ab](https://linux-hardware.org/?probe=b05c08e4ab) | Nov 17, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [5077cde917](https://linux-hardware.org/?probe=5077cde917) | Nov 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [4c653190f6](https://linux-hardware.org/?probe=4c653190f6) | Nov 14, 2023 |
| HUAWEI        | BOHB-WAX9                   | [1d2a92df29](https://linux-hardware.org/?probe=1d2a92df29) | Nov 12, 2023 |
| Lenovo        | ThinkPad L15 Gen 2a 20X8... | [4bf49cfb42](https://linux-hardware.org/?probe=4bf49cfb42) | Nov 11, 2023 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [3f794fd46d](https://linux-hardware.org/?probe=3f794fd46d) | Nov 11, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [5c39f44ed5](https://linux-hardware.org/?probe=5c39f44ed5) | Nov 08, 2023 |
| ASUSTek       | K501UW                      | [54d6d39995](https://linux-hardware.org/?probe=54d6d39995) | Nov 07, 2023 |
| ASUSTek       | X555LN                      | [7971055e99](https://linux-hardware.org/?probe=7971055e99) | Nov 06, 2023 |
| Dell          | Inspiron 5459               | [fc242f51bf](https://linux-hardware.org/?probe=fc242f51bf) | Nov 05, 2023 |
| Toshiba       | Satellite L515              | [70a66852db](https://linux-hardware.org/?probe=70a66852db) | Nov 05, 2023 |
| HP            | ENVY 15                     | [74dae44745](https://linux-hardware.org/?probe=74dae44745) | Nov 01, 2023 |
| Dell          | Latitude 7290               | [b7170343fb](https://linux-hardware.org/?probe=b7170343fb) | Oct 31, 2023 |
| HP            | Laptop 15-dy2xxx            | [8c6cbf3608](https://linux-hardware.org/?probe=8c6cbf3608) | Oct 27, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [c4b4502472](https://linux-hardware.org/?probe=c4b4502472) | Oct 20, 2023 |
| Lenovo        | E41-50 82HW                 | [f31f632ea0](https://linux-hardware.org/?probe=f31f632ea0) | Oct 17, 2023 |
| HP            | 240 G5 Notebook PC          | [22f4ada2e9](https://linux-hardware.org/?probe=22f4ada2e9) | Oct 10, 2023 |
| HP            | 240 G5 Notebook PC          | [db5dd15d83](https://linux-hardware.org/?probe=db5dd15d83) | Oct 08, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [26247d8807](https://linux-hardware.org/?probe=26247d8807) | Oct 05, 2023 |
| Dell          | Inspiron 5459               | [965f7580d3](https://linux-hardware.org/?probe=965f7580d3) | Oct 05, 2023 |
| Dell          | Inspiron 13-5378            | [06c1e095a7](https://linux-hardware.org/?probe=06c1e095a7) | Oct 03, 2023 |
| Acer          | Aspire VN7-571G             | [0babc8185b](https://linux-hardware.org/?probe=0babc8185b) | Oct 03, 2023 |
| Toshiba       | Satellite C845D             | [92651c9e51](https://linux-hardware.org/?probe=92651c9e51) | Sep 30, 2023 |
| Acer          | Aspire A514-53              | [6d8a5b1a13](https://linux-hardware.org/?probe=6d8a5b1a13) | Sep 30, 2023 |
| Acer          | Nitro AN515-52              | [e7fb14ee98](https://linux-hardware.org/?probe=e7fb14ee98) | Sep 28, 2023 |
| Dell          | Inspiron 5567               | [91e89424ef](https://linux-hardware.org/?probe=91e89424ef) | Sep 25, 2023 |
| HP            | 250 G6 Notebook PC          | [88ce9be8a1](https://linux-hardware.org/?probe=88ce9be8a1) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [fc14083064](https://linux-hardware.org/?probe=fc14083064) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [acba7de2ec](https://linux-hardware.org/?probe=acba7de2ec) | Sep 24, 2023 |
| Lenovo        | ThinkPad Edge E431 62778... | [31b0e8e9ce](https://linux-hardware.org/?probe=31b0e8e9ce) | Sep 24, 2023 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [b61b5cb7e3](https://linux-hardware.org/?probe=b61b5cb7e3) | Sep 23, 2023 |
| Lenovo        | Yoga Slim 9 14ITL5 82D1     | [05ef373ef0](https://linux-hardware.org/?probe=05ef373ef0) | Sep 23, 2023 |
| Lenovo        | Yoga Slim 9 14ITL5 82D1     | [a57b236842](https://linux-hardware.org/?probe=a57b236842) | Sep 23, 2023 |
| Acer          | Aspire ES1-531              | [50023a1d3a](https://linux-hardware.org/?probe=50023a1d3a) | Sep 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [68c0d7834d](https://linux-hardware.org/?probe=68c0d7834d) | Sep 18, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | [62375851b3](https://linux-hardware.org/?probe=62375851b3) | Sep 13, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | [c87b0b463c](https://linux-hardware.org/?probe=c87b0b463c) | Sep 13, 2023 |
| Dell          | Inspiron 3501               | [f7eae2e7c4](https://linux-hardware.org/?probe=f7eae2e7c4) | Sep 09, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [d075cbe2e0](https://linux-hardware.org/?probe=d075cbe2e0) | Sep 04, 2023 |
| HP            | ProBook 440 G7              | [2c90811519](https://linux-hardware.org/?probe=2c90811519) | Sep 03, 2023 |
| HP            | ProBook 640 G2              | [c0af84c629](https://linux-hardware.org/?probe=c0af84c629) | Sep 02, 2023 |
| Samsung       | RF511/RF411/RF711           | [ab39767c20](https://linux-hardware.org/?probe=ab39767c20) | Sep 02, 2023 |
| Lenovo        | ThinkPad X201 3680KS9       | [561d8c3891](https://linux-hardware.org/?probe=561d8c3891) | Sep 02, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | [52e8a720ba](https://linux-hardware.org/?probe=52e8a720ba) | Sep 01, 2023 |
| Dell          | Inspiron N4050              | [d354a59a67](https://linux-hardware.org/?probe=d354a59a67) | Aug 29, 2023 |
| HP            | Laptop 14-dq2xxx            | [0c46e2d419](https://linux-hardware.org/?probe=0c46e2d419) | Aug 26, 2023 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [0b3afd5dce](https://linux-hardware.org/?probe=0b3afd5dce) | Aug 24, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | [4d1d53f6d8](https://linux-hardware.org/?probe=4d1d53f6d8) | Aug 24, 2023 |
| Toshiba       | Satellite L515              | [fa5d7d5547](https://linux-hardware.org/?probe=fa5d7d5547) | Aug 23, 2023 |
| ASUSTek       | ROG Strix G531GU_G531GU     | [627606b933](https://linux-hardware.org/?probe=627606b933) | Aug 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [1b985f59a1](https://linux-hardware.org/?probe=1b985f59a1) | Aug 21, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [272e3307fe](https://linux-hardware.org/?probe=272e3307fe) | Aug 21, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [6f1a280aa5](https://linux-hardware.org/?probe=6f1a280aa5) | Aug 21, 2023 |
| Acer          | Aspire A315-42              | [e84eba7c7d](https://linux-hardware.org/?probe=e84eba7c7d) | Aug 20, 2023 |
| Acer          | TravelMate P645-S           | [658d88e2a5](https://linux-hardware.org/?probe=658d88e2a5) | Aug 20, 2023 |
| HP            | Pavilion dv4                | [5f1e0c4484](https://linux-hardware.org/?probe=5f1e0c4484) | Aug 19, 2023 |
| HP            | 435                         | [cb02103775](https://linux-hardware.org/?probe=cb02103775) | Aug 17, 2023 |
| TAGTech       | TAGITOP-UNI C               | [d7402c2c8d](https://linux-hardware.org/?probe=d7402c2c8d) | Aug 17, 2023 |
| TAGTech       | TAGITOP-UNI C               | [1cccdef7f4](https://linux-hardware.org/?probe=1cccdef7f4) | Aug 17, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [dbdb6ca163](https://linux-hardware.org/?probe=dbdb6ca163) | Aug 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [4404dc3287](https://linux-hardware.org/?probe=4404dc3287) | Aug 12, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [79889c3f89](https://linux-hardware.org/?probe=79889c3f89) | Aug 11, 2023 |
| Acer          | Aspire A514-53              | [26e60daa62](https://linux-hardware.org/?probe=26e60daa62) | Aug 10, 2023 |
| Lenovo        | G460 20041                  | [709445c691](https://linux-hardware.org/?probe=709445c691) | Aug 09, 2023 |
| HP            | Compaq 15                   | [387a3b8af2](https://linux-hardware.org/?probe=387a3b8af2) | Aug 09, 2023 |
| HP            | 240 G5 Notebook PC          | [c801f4bbd0](https://linux-hardware.org/?probe=c801f4bbd0) | Aug 09, 2023 |
| HP            | Laptop 14-dq1xxx            | [f8f4442b09](https://linux-hardware.org/?probe=f8f4442b09) | Aug 05, 2023 |
| Acer          | Nitro AN515-45              | [fda8d0a543](https://linux-hardware.org/?probe=fda8d0a543) | Aug 02, 2023 |
| HP            | EliteBook Folio 1040 G2     | [752821ae1a](https://linux-hardware.org/?probe=752821ae1a) | Aug 01, 2023 |
| HP            | EliteBook Folio 1040 G2     | [b847ac4535](https://linux-hardware.org/?probe=b847ac4535) | Aug 01, 2023 |
| Lenovo        | ThinkPad Edge E430 32543... | [b30651e46f](https://linux-hardware.org/?probe=b30651e46f) | Jul 30, 2023 |
| Lenovo        | ThinkPad X201 3680KS9       | [968bd5d46b](https://linux-hardware.org/?probe=968bd5d46b) | Jul 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [2ca3c71f4a](https://linux-hardware.org/?probe=2ca3c71f4a) | Jul 24, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [19aa0d748d](https://linux-hardware.org/?probe=19aa0d748d) | Jul 24, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [3d8ec4447b](https://linux-hardware.org/?probe=3d8ec4447b) | Jul 24, 2023 |
| HP            | 240 G6 Notebook PC          | [ec2be7713c](https://linux-hardware.org/?probe=ec2be7713c) | Jul 22, 2023 |
| Acer          | Aspire A514-53              | [b754fb3410](https://linux-hardware.org/?probe=b754fb3410) | Jul 21, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [d163198c13](https://linux-hardware.org/?probe=d163198c13) | Jul 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [35d1400354](https://linux-hardware.org/?probe=35d1400354) | Jul 20, 2023 |
| Dell          | Latitude E6410              | [2a09336b72](https://linux-hardware.org/?probe=2a09336b72) | Jul 20, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [64b51936ea](https://linux-hardware.org/?probe=64b51936ea) | Jul 20, 2023 |
| Lenovo        | M490s 20215                 | [d029f6cf0b](https://linux-hardware.org/?probe=d029f6cf0b) | Jul 16, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [48b3d62237](https://linux-hardware.org/?probe=48b3d62237) | Jul 15, 2023 |
| HP            | ENVY 15                     | [5cfb9d33bd](https://linux-hardware.org/?probe=5cfb9d33bd) | Jul 14, 2023 |
| Valve         | Jupiter                     | [110622383d](https://linux-hardware.org/?probe=110622383d) | Jul 11, 2023 |
| HP            | EliteBook 840 G6            | [52fafabf05](https://linux-hardware.org/?probe=52fafabf05) | Jul 10, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | [275acaaa00](https://linux-hardware.org/?probe=275acaaa00) | Jul 03, 2023 |
| Lenovo        | ThinkPad X230 23254W5       | [5842896b76](https://linux-hardware.org/?probe=5842896b76) | Jul 03, 2023 |
| HP            | 245 G6 Notebook PC          | [48195d85f8](https://linux-hardware.org/?probe=48195d85f8) | Jul 02, 2023 |
| HP            | 245 G6 Notebook PC          | [189320a2cf](https://linux-hardware.org/?probe=189320a2cf) | Jul 01, 2023 |
| HP            | 245 G6 Notebook PC          | [22a896d74b](https://linux-hardware.org/?probe=22a896d74b) | Jun 30, 2023 |
| HP            | 240 G6 Notebook PC          | [f72fe64697](https://linux-hardware.org/?probe=f72fe64697) | Jun 29, 2023 |
| Acer          | Aspire A315-42              | [d2a1351f86](https://linux-hardware.org/?probe=d2a1351f86) | Jun 28, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | [7487f61ff1](https://linux-hardware.org/?probe=7487f61ff1) | Jun 26, 2023 |
| HONOR         | NBR-WAX9                    | [dfeaf221e6](https://linux-hardware.org/?probe=dfeaf221e6) | Jun 22, 2023 |
| Lenovo        | ThinkPad T440p 20AWS02V0... | [bed60c3010](https://linux-hardware.org/?probe=bed60c3010) | Jun 21, 2023 |
| MSI           | GE75 Raider 10SF            | [b3ce37b2cb](https://linux-hardware.org/?probe=b3ce37b2cb) | Jun 21, 2023 |
| HP            | Compaq 15                   | [d89a75cb42](https://linux-hardware.org/?probe=d89a75cb42) | Jun 20, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | [34610e62fe](https://linux-hardware.org/?probe=34610e62fe) | Jun 18, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | [bd4abe1a68](https://linux-hardware.org/?probe=bd4abe1a68) | Jun 18, 2023 |
| HP            | Compaq 15                   | [a60f50ade5](https://linux-hardware.org/?probe=a60f50ade5) | Jun 18, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [97a4ed6110](https://linux-hardware.org/?probe=97a4ed6110) | Jun 17, 2023 |
| Acer          | Aspire V5-471P              | [b00b3b8570](https://linux-hardware.org/?probe=b00b3b8570) | Jun 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [eb6dc5143e](https://linux-hardware.org/?probe=eb6dc5143e) | Jun 12, 2023 |
| Acer          | Aspire E5-575G              | [90bcfaba60](https://linux-hardware.org/?probe=90bcfaba60) | Jun 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [758afab931](https://linux-hardware.org/?probe=758afab931) | Jun 10, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D7S... | [246facab73](https://linux-hardware.org/?probe=246facab73) | Jun 10, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D7S... | [233dac6c68](https://linux-hardware.org/?probe=233dac6c68) | Jun 09, 2023 |
| HP            | 240 G6 Notebook PC          | [f7470e08b0](https://linux-hardware.org/?probe=f7470e08b0) | Jun 08, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20S5... | [0372aa0747](https://linux-hardware.org/?probe=0372aa0747) | Jun 08, 2023 |
| HP            | 240 G6 Notebook PC          | [eda13b898c](https://linux-hardware.org/?probe=eda13b898c) | Jun 08, 2023 |
| HP            | ENVY 15                     | [3776ac93b3](https://linux-hardware.org/?probe=3776ac93b3) | Jun 08, 2023 |
| Acer          | Aspire E5-573G              | [277ddf45b4](https://linux-hardware.org/?probe=277ddf45b4) | Jun 08, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [9c9fb1b1a6](https://linux-hardware.org/?probe=9c9fb1b1a6) | Jun 08, 2023 |
| Unknown       | Unknown                     | [829839a3b3](https://linux-hardware.org/?probe=829839a3b3) | Jun 07, 2023 |
| MSI           | Modern 14 B5M               | [25ffe9ad37](https://linux-hardware.org/?probe=25ffe9ad37) | Jun 03, 2023 |
| SK hynix      | HyBook                      | [c25f19e040](https://linux-hardware.org/?probe=c25f19e040) | Jun 03, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | [f1e9073b3d](https://linux-hardware.org/?probe=f1e9073b3d) | May 31, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | [2f61fcf47d](https://linux-hardware.org/?probe=2f61fcf47d) | May 31, 2023 |
| HP            | EliteBook 6930p             | [882f43330b](https://linux-hardware.org/?probe=882f43330b) | May 30, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [46f455ce35](https://linux-hardware.org/?probe=46f455ce35) | May 30, 2023 |
| MSI           | GE75 Raider 10SF            | [5ee0afea25](https://linux-hardware.org/?probe=5ee0afea25) | May 25, 2023 |
| HUAWEI        | BOHB-WAX9                   | [f69b95b887](https://linux-hardware.org/?probe=f69b95b887) | May 19, 2023 |
| MSI           | GE75 Raider 10SF            | [8aaec63d14](https://linux-hardware.org/?probe=8aaec63d14) | May 19, 2023 |
| MSI           | GE75 Raider 10SF            | [f3724cb7da](https://linux-hardware.org/?probe=f3724cb7da) | May 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [33a9b42068](https://linux-hardware.org/?probe=33a9b42068) | May 15, 2023 |
| Dell          | Vostro 3400                 | [37eeeb2f31](https://linux-hardware.org/?probe=37eeeb2f31) | May 13, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [2674c1ddb6](https://linux-hardware.org/?probe=2674c1ddb6) | May 12, 2023 |
| Dell          | Latitude 5480               | [eb671ee7d2](https://linux-hardware.org/?probe=eb671ee7d2) | May 11, 2023 |
| HP            | Laptop 14-dq1xxx            | [76f23f434d](https://linux-hardware.org/?probe=76f23f434d) | May 10, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | [ce04ace3b3](https://linux-hardware.org/?probe=ce04ace3b3) | May 09, 2023 |
| SK hynix      | HyBook Plus                 | [817a46f154](https://linux-hardware.org/?probe=817a46f154) | May 09, 2023 |
| Valve         | Jupiter                     | [d0eb83c0af](https://linux-hardware.org/?probe=d0eb83c0af) | May 07, 2023 |
| Lenovo        | ThinkPad T460p 20FXS0BB0... | [881068ac47](https://linux-hardware.org/?probe=881068ac47) | May 06, 2023 |
| Apple         | MacBookPro8,1               | [e3dd9f70f6](https://linux-hardware.org/?probe=e3dd9f70f6) | May 04, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | [29f68ce8d7](https://linux-hardware.org/?probe=29f68ce8d7) | May 03, 2023 |
| Toshiba       | Satellite L45               | [044db31897](https://linux-hardware.org/?probe=044db31897) | May 02, 2023 |
| Acer          | Aspire V5-471P              | [d44b4f12a5](https://linux-hardware.org/?probe=d44b4f12a5) | May 01, 2023 |
| Lenovo        | B490 20205                  | [c786307607](https://linux-hardware.org/?probe=c786307607) | May 01, 2023 |
| HP            | Compaq 15                   | [0c65bb3d3c](https://linux-hardware.org/?probe=0c65bb3d3c) | May 01, 2023 |
| Lenovo        | ThinkPad T480 20L6A0LJCL    | [f67154866c](https://linux-hardware.org/?probe=f67154866c) | May 01, 2023 |
| Lenovo        | B490 20205                  | [bc1fdb2575](https://linux-hardware.org/?probe=bc1fdb2575) | May 01, 2023 |
| Acer          | Aspire E5-551G              | [bba2f8d1ad](https://linux-hardware.org/?probe=bba2f8d1ad) | Apr 30, 2023 |
| Toshiba       | PORTEGE R830                | [11dc4b3a3e](https://linux-hardware.org/?probe=11dc4b3a3e) | Apr 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [ed7c1abb38](https://linux-hardware.org/?probe=ed7c1abb38) | Apr 28, 2023 |
| HP            | ENVY 15                     | [d870c486c7](https://linux-hardware.org/?probe=d870c486c7) | Apr 27, 2023 |
| HP            | EliteBook 6930p             | [014215365a](https://linux-hardware.org/?probe=014215365a) | Apr 27, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [f797b7112c](https://linux-hardware.org/?probe=f797b7112c) | Apr 25, 2023 |
| HP            | ENVY 15                     | [3539894e49](https://linux-hardware.org/?probe=3539894e49) | Apr 25, 2023 |
| Chuwi         | GemiBook Pro                | [1287b17594](https://linux-hardware.org/?probe=1287b17594) | Apr 25, 2023 |
| HP            | ENVY 15                     | [39d32b035a](https://linux-hardware.org/?probe=39d32b035a) | Apr 25, 2023 |
| Lenovo        | ThinkPad X220 4286A44       | [6b6e909d11](https://linux-hardware.org/?probe=6b6e909d11) | Apr 23, 2023 |
| HP            | Pavilion 15                 | [e72f221b5b](https://linux-hardware.org/?probe=e72f221b5b) | Apr 23, 2023 |
| HP            | Notebook                    | [31d24dfe38](https://linux-hardware.org/?probe=31d24dfe38) | Apr 21, 2023 |
| Dell          | G15 5510                    | [43d4ce3c37](https://linux-hardware.org/?probe=43d4ce3c37) | Apr 21, 2023 |
| Toshiba       | Satellite L515              | [5262a186b5](https://linux-hardware.org/?probe=5262a186b5) | Apr 20, 2023 |
| Gear          | Geranium                    | [5e67931961](https://linux-hardware.org/?probe=5e67931961) | Apr 17, 2023 |
| Gear          | Geranium                    | [fe70506e6c](https://linux-hardware.org/?probe=fe70506e6c) | Apr 17, 2023 |
| Lenovo        | G405 20239                  | [e79c183bde](https://linux-hardware.org/?probe=e79c183bde) | Apr 17, 2023 |
| Dell          | Inspiron 3501               | [19b858e5f8](https://linux-hardware.org/?probe=19b858e5f8) | Apr 16, 2023 |
| HP            | Laptop 15-ef1xxx            | [33c25e0c22](https://linux-hardware.org/?probe=33c25e0c22) | Apr 15, 2023 |
| HP            | Laptop 15-ef1xxx            | [33936188c8](https://linux-hardware.org/?probe=33936188c8) | Apr 15, 2023 |
| Dell          | XPS 15 9560                 | [5ab7cc057f](https://linux-hardware.org/?probe=5ab7cc057f) | Apr 14, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [eb800f7d1b](https://linux-hardware.org/?probe=eb800f7d1b) | Apr 14, 2023 |
| HP            | 250 G6 Notebook PC          | [22da370a63](https://linux-hardware.org/?probe=22da370a63) | Apr 08, 2023 |
| HP            | EliteBook 6930p             | [b7d43d9e23](https://linux-hardware.org/?probe=b7d43d9e23) | Apr 06, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [ff65115a04](https://linux-hardware.org/?probe=ff65115a04) | Apr 06, 2023 |
| Dell          | Latitude E5440              | [771f3d8665](https://linux-hardware.org/?probe=771f3d8665) | Apr 05, 2023 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [a7cb3cf668](https://linux-hardware.org/?probe=a7cb3cf668) | Apr 05, 2023 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [16f81f8254](https://linux-hardware.org/?probe=16f81f8254) | Apr 05, 2023 |
| Lenovo        | V110-14IAP 80TF             | [ad6e45cead](https://linux-hardware.org/?probe=ad6e45cead) | Apr 05, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [4710939159](https://linux-hardware.org/?probe=4710939159) | Apr 05, 2023 |
| HP            | EliteBook 6930p             | [98f2b162e1](https://linux-hardware.org/?probe=98f2b162e1) | Apr 01, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [4191279e7e](https://linux-hardware.org/?probe=4191279e7e) | Apr 01, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [27fbf62ba0](https://linux-hardware.org/?probe=27fbf62ba0) | Apr 01, 2023 |
| HP            | EliteBook 6930p             | [5b087b11f5](https://linux-hardware.org/?probe=5b087b11f5) | Mar 30, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [e9600e8bfe](https://linux-hardware.org/?probe=e9600e8bfe) | Mar 29, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [f7222bf293](https://linux-hardware.org/?probe=f7222bf293) | Mar 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [a438a0c994](https://linux-hardware.org/?probe=a438a0c994) | Mar 27, 2023 |
| Acer          | Swift SF113-31              | [698b73783e](https://linux-hardware.org/?probe=698b73783e) | Mar 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E203... | [036c2c771c](https://linux-hardware.org/?probe=036c2c771c) | Mar 23, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [4cbcbc3025](https://linux-hardware.org/?probe=4cbcbc3025) | Mar 22, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [d08f174747](https://linux-hardware.org/?probe=d08f174747) | Mar 20, 2023 |
| Dell          | G3 3590                     | [cba689e7f5](https://linux-hardware.org/?probe=cba689e7f5) | Mar 20, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [23c1be0005](https://linux-hardware.org/?probe=23c1be0005) | Mar 19, 2023 |
| HP            | ProBook 640 G2              | [9439371137](https://linux-hardware.org/?probe=9439371137) | Mar 18, 2023 |
| HP            | ProBook 640 G2              | [c968526666](https://linux-hardware.org/?probe=c968526666) | Mar 18, 2023 |
| Lenovo        | IdeaPad S540-15IWL 81NE     | [11b2e17886](https://linux-hardware.org/?probe=11b2e17886) | Mar 13, 2023 |
| Toshiba       | Satellite L515              | [11116a9517](https://linux-hardware.org/?probe=11116a9517) | Mar 13, 2023 |
| Gear          | Geranium                    | [8567411d91](https://linux-hardware.org/?probe=8567411d91) | Mar 13, 2023 |
| Gear          | Geranium                    | [1303244018](https://linux-hardware.org/?probe=1303244018) | Mar 13, 2023 |
| Toshiba       | Satellite L515              | [f2ffca7459](https://linux-hardware.org/?probe=f2ffca7459) | Mar 12, 2023 |
| ASUSTek       | K501UW                      | [322b5bf476](https://linux-hardware.org/?probe=322b5bf476) | Mar 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [87779bfdea](https://linux-hardware.org/?probe=87779bfdea) | Mar 11, 2023 |
| ASUSTek       | K501UW                      | [9a61fd62b3](https://linux-hardware.org/?probe=9a61fd62b3) | Mar 05, 2023 |
| Dell          | Latitude 5410               | [6f55e8bbfe](https://linux-hardware.org/?probe=6f55e8bbfe) | Mar 05, 2023 |
| Toshiba       | Satellite L515              | [daf95cc1e5](https://linux-hardware.org/?probe=daf95cc1e5) | Mar 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [76645fa513](https://linux-hardware.org/?probe=76645fa513) | Feb 28, 2023 |
| HP            | 240 G4 Notebook PC          | [02744836e7](https://linux-hardware.org/?probe=02744836e7) | Feb 28, 2023 |
| Dell          | G3 3590                     | [eb9009fad9](https://linux-hardware.org/?probe=eb9009fad9) | Feb 27, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [6b712e555f](https://linux-hardware.org/?probe=6b712e555f) | Feb 26, 2023 |
| Dell          | System XPS L321X            | [4de5ba1c80](https://linux-hardware.org/?probe=4de5ba1c80) | Feb 25, 2023 |
| HP            | ProBook 4730s               | [6d563800a1](https://linux-hardware.org/?probe=6d563800a1) | Feb 24, 2023 |
| Toshiba       | Satellite L515              | [969c2042b9](https://linux-hardware.org/?probe=969c2042b9) | Feb 24, 2023 |
| HP            | Pavilion Notebook           | [f0cb288b9f](https://linux-hardware.org/?probe=f0cb288b9f) | Feb 23, 2023 |
| HP            | 15                          | [470b07302a](https://linux-hardware.org/?probe=470b07302a) | Feb 22, 2023 |
| HP            | Pavilion Notebook           | [63636ce164](https://linux-hardware.org/?probe=63636ce164) | Feb 22, 2023 |
| Samsung       | R430/P430                   | [3bbea19ca4](https://linux-hardware.org/?probe=3bbea19ca4) | Feb 21, 2023 |
| ASUSTek       | Zenbook UM5401QA_UM5401Q... | [51a7f0e66d](https://linux-hardware.org/?probe=51a7f0e66d) | Feb 19, 2023 |
| HP            | 15                          | [60ecad0be7](https://linux-hardware.org/?probe=60ecad0be7) | Feb 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [764c7eaffe](https://linux-hardware.org/?probe=764c7eaffe) | Feb 17, 2023 |
| ASUSTek       | K501UW                      | [6d64083839](https://linux-hardware.org/?probe=6d64083839) | Feb 17, 2023 |
| ASUSTek       | K501UW                      | [7857666504](https://linux-hardware.org/?probe=7857666504) | Feb 16, 2023 |
| Dell          | Precision 7560              | [7ed10eebe9](https://linux-hardware.org/?probe=7ed10eebe9) | Feb 16, 2023 |
| ASUSTek       | K501UW                      | [45e719d7c0](https://linux-hardware.org/?probe=45e719d7c0) | Feb 15, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [247ab26b54](https://linux-hardware.org/?probe=247ab26b54) | Feb 14, 2023 |
| HP            | 14                          | [38554cf215](https://linux-hardware.org/?probe=38554cf215) | Feb 14, 2023 |
| Valve         | Jupiter                     | [c3f554a4bf](https://linux-hardware.org/?probe=c3f554a4bf) | Feb 14, 2023 |
| Valve         | Jupiter                     | [4ba93ea14d](https://linux-hardware.org/?probe=4ba93ea14d) | Feb 14, 2023 |
| HP            | 14                          | [610e26434d](https://linux-hardware.org/?probe=610e26434d) | Feb 12, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [1867884ede](https://linux-hardware.org/?probe=1867884ede) | Feb 06, 2023 |
| HP            | Presario CQ43               | [76bfeffd5f](https://linux-hardware.org/?probe=76bfeffd5f) | Feb 02, 2023 |
| Apple         | MacBookPro11,4              | [8a5423443a](https://linux-hardware.org/?probe=8a5423443a) | Jan 28, 2023 |
| Lenovo        | V14 G1 IML 82NA             | [c346600bdc](https://linux-hardware.org/?probe=c346600bdc) | Jan 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [30b373aafe](https://linux-hardware.org/?probe=30b373aafe) | Jan 25, 2023 |
| Google        | Treeya                      | [27a381272a](https://linux-hardware.org/?probe=27a381272a) | Jan 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [a715541f02](https://linux-hardware.org/?probe=a715541f02) | Jan 24, 2023 |
| Dell          | Inspiron 3501               | [a9cad4d873](https://linux-hardware.org/?probe=a9cad4d873) | Jan 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [c2c13271fd](https://linux-hardware.org/?probe=c2c13271fd) | Jan 17, 2023 |
| HP            | ProBook 655 G1              | [e5f3b2835d](https://linux-hardware.org/?probe=e5f3b2835d) | Jan 16, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | [47d090108d](https://linux-hardware.org/?probe=47d090108d) | Jan 16, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | [219091b4e0](https://linux-hardware.org/?probe=219091b4e0) | Jan 15, 2023 |
| Acer          | Aspire 2920                 | [0766ea34c6](https://linux-hardware.org/?probe=0766ea34c6) | Jan 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [2455d11a72](https://linux-hardware.org/?probe=2455d11a72) | Jan 11, 2023 |
| HP            | ProBook 655 G1              | [f61b79535e](https://linux-hardware.org/?probe=f61b79535e) | Jan 10, 2023 |
| Acer          | Aspire A315-41              | [6c7f37297d](https://linux-hardware.org/?probe=6c7f37297d) | Jan 09, 2023 |
| HP            | ProBook 655 G1              | [91948448b6](https://linux-hardware.org/?probe=91948448b6) | Jan 09, 2023 |
| Acer          | Aspire A314-22              | [5729420a54](https://linux-hardware.org/?probe=5729420a54) | Jan 09, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [2923dcfe6f](https://linux-hardware.org/?probe=2923dcfe6f) | Jan 09, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [b345c4d626](https://linux-hardware.org/?probe=b345c4d626) | Jan 06, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [3a3164f63f](https://linux-hardware.org/?probe=3a3164f63f) | Jan 04, 2023 |
| HP            | EliteBook 8740w (WH274UT... | [e42d4e66a0](https://linux-hardware.org/?probe=e42d4e66a0) | Dec 31, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [68b3b51892](https://linux-hardware.org/?probe=68b3b51892) | Dec 30, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [fdb827eff9](https://linux-hardware.org/?probe=fdb827eff9) | Dec 29, 2022 |
| HP            | 240 G6 Notebook PC          | [b593030fef](https://linux-hardware.org/?probe=b593030fef) | Dec 28, 2022 |
| HP            | 240 G6 Notebook PC          | [27e4ff648f](https://linux-hardware.org/?probe=27e4ff648f) | Dec 28, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [321cc72064](https://linux-hardware.org/?probe=321cc72064) | Dec 27, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | [06d788f40a](https://linux-hardware.org/?probe=06d788f40a) | Dec 27, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [6de981f1fc](https://linux-hardware.org/?probe=6de981f1fc) | Dec 24, 2022 |
| HP            | Pavilion dv7                | [5e5eb2c983](https://linux-hardware.org/?probe=5e5eb2c983) | Dec 22, 2022 |
| HP            | Pavilion 11 x360 PC         | [1397ed80b3](https://linux-hardware.org/?probe=1397ed80b3) | Dec 21, 2022 |
| HP            | 14                          | [4794938b36](https://linux-hardware.org/?probe=4794938b36) | Dec 14, 2022 |
| Dell          | Inspiron 7380               | [29d4feb456](https://linux-hardware.org/?probe=29d4feb456) | Dec 12, 2022 |
| Valve         | Jupiter                     | [d41bef1f84](https://linux-hardware.org/?probe=d41bef1f84) | Dec 09, 2022 |
| Acer          | Aspire E1-532               | [4fd43d5aff](https://linux-hardware.org/?probe=4fd43d5aff) | Dec 09, 2022 |
| Acer          | Aspire A515-52              | [99e671f55f](https://linux-hardware.org/?probe=99e671f55f) | Dec 09, 2022 |
| Acer          | Aspire E1-532               | [13e9fa6c58](https://linux-hardware.org/?probe=13e9fa6c58) | Dec 09, 2022 |
| Dell          | Inspiron 5459               | [9b714617c8](https://linux-hardware.org/?probe=9b714617c8) | Dec 04, 2022 |
| HP            | 14                          | [868daee488](https://linux-hardware.org/?probe=868daee488) | Dec 03, 2022 |
| ASUSTek       | K501UW                      | [1571941805](https://linux-hardware.org/?probe=1571941805) | Dec 03, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | [aa9ad07031](https://linux-hardware.org/?probe=aa9ad07031) | Dec 01, 2022 |
| Dell          | Inspiron MM061              | [703ef1c899](https://linux-hardware.org/?probe=703ef1c899) | Nov 30, 2022 |
| Chuwi         | CoreBook X                  | [f6745ce587](https://linux-hardware.org/?probe=f6745ce587) | Nov 29, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [1e52ea39e4](https://linux-hardware.org/?probe=1e52ea39e4) | Nov 28, 2022 |
| Chuwi         | CoreBook X                  | [810ed5914a](https://linux-hardware.org/?probe=810ed5914a) | Nov 28, 2022 |
| Toshiba       | TECRA M11                   | [509dfbf1a4](https://linux-hardware.org/?probe=509dfbf1a4) | Nov 27, 2022 |
| Acer          | Aspire A315-42              | [3413fb7947](https://linux-hardware.org/?probe=3413fb7947) | Nov 26, 2022 |
| Alienware     | M17xR3                      | [438f3639aa](https://linux-hardware.org/?probe=438f3639aa) | Nov 24, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [0627894c6b](https://linux-hardware.org/?probe=0627894c6b) | Nov 18, 2022 |
| Lenovo        | IdeaPad 1 14IAU7 82QC       | [12073cb314](https://linux-hardware.org/?probe=12073cb314) | Nov 16, 2022 |
| Sony          | SVE1411EGXB                 | [dafea482eb](https://linux-hardware.org/?probe=dafea482eb) | Nov 14, 2022 |
| HP            | Pavilion g4                 | [44162d8878](https://linux-hardware.org/?probe=44162d8878) | Nov 11, 2022 |
| HP            | ENVY 17 Leap Motion SE N... | [ae40e6e5b3](https://linux-hardware.org/?probe=ae40e6e5b3) | Nov 10, 2022 |
| Acer          | Aspire A515-51G             | [7f498c5723](https://linux-hardware.org/?probe=7f498c5723) | Nov 08, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | [3d53644c05](https://linux-hardware.org/?probe=3d53644c05) | Nov 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [44e88f2879](https://linux-hardware.org/?probe=44e88f2879) | Nov 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [61756efe8c](https://linux-hardware.org/?probe=61756efe8c) | Nov 07, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [ece385acfe](https://linux-hardware.org/?probe=ece385acfe) | Nov 05, 2022 |
| HP            | ProBook 440 G7              | [7a183bdeb7](https://linux-hardware.org/?probe=7a183bdeb7) | Nov 05, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [f078009dc8](https://linux-hardware.org/?probe=f078009dc8) | Nov 05, 2022 |
| Acer          | Aspire E5-575G              | [af85812864](https://linux-hardware.org/?probe=af85812864) | Nov 04, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [3bd662e577](https://linux-hardware.org/?probe=3bd662e577) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [4a158afdfd](https://linux-hardware.org/?probe=4a158afdfd) | Nov 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [325516bbce](https://linux-hardware.org/?probe=325516bbce) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [740d19ba42](https://linux-hardware.org/?probe=740d19ba42) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [424aaaf5bd](https://linux-hardware.org/?probe=424aaaf5bd) | Oct 30, 2022 |
| Toshiba       | TECRA M11                   | [15690a2198](https://linux-hardware.org/?probe=15690a2198) | Oct 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [293877c614](https://linux-hardware.org/?probe=293877c614) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d7491bf8e7](https://linux-hardware.org/?probe=d7491bf8e7) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [6bdf703faf](https://linux-hardware.org/?probe=6bdf703faf) | Oct 29, 2022 |
| Apple         | MacBookAir7,2               | [3d3ac2530c](https://linux-hardware.org/?probe=3d3ac2530c) | Oct 25, 2022 |
| Acer          | Aspire ES1-111M             | [ebff9e2fa5](https://linux-hardware.org/?probe=ebff9e2fa5) | Oct 25, 2022 |
| Acer          | Aspire E5-575G              | [b6b5c1468c](https://linux-hardware.org/?probe=b6b5c1468c) | Oct 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7cafd024ea](https://linux-hardware.org/?probe=7cafd024ea) | Oct 22, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [9f16b5a7e2](https://linux-hardware.org/?probe=9f16b5a7e2) | Oct 22, 2022 |
| Google        | Treeya                      | [1a93d190b0](https://linux-hardware.org/?probe=1a93d190b0) | Oct 21, 2022 |
| Lenovo        | ThinkPad T470 20JNS01R01    | [abb8194196](https://linux-hardware.org/?probe=abb8194196) | Oct 21, 2022 |
| Samsung       | R430/P430/R480              | [a2db8aeade](https://linux-hardware.org/?probe=a2db8aeade) | Oct 19, 2022 |
| Samsung       | R430/P430/R480              | [92957e0afc](https://linux-hardware.org/?probe=92957e0afc) | Oct 19, 2022 |
| Samsung       | R430/P430/R480              | [c2f91318fe](https://linux-hardware.org/?probe=c2f91318fe) | Oct 17, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [e515cd0e66](https://linux-hardware.org/?probe=e515cd0e66) | Oct 15, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [3028d439cf](https://linux-hardware.org/?probe=3028d439cf) | Oct 14, 2022 |
| HP            | 250 G6 Notebook PC          | [2b3c91d2b0](https://linux-hardware.org/?probe=2b3c91d2b0) | Oct 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [318b3ef82b](https://linux-hardware.org/?probe=318b3ef82b) | Oct 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [17feafd680](https://linux-hardware.org/?probe=17feafd680) | Oct 12, 2022 |
| HP            | Pavilion Laptop 15-cw0xx... | [593d28a4cf](https://linux-hardware.org/?probe=593d28a4cf) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [04e29685a6](https://linux-hardware.org/?probe=04e29685a6) | Oct 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [2a8fd02f04](https://linux-hardware.org/?probe=2a8fd02f04) | Oct 07, 2022 |
| Acer          | Aspire E5-575G              | [5e60e8faae](https://linux-hardware.org/?probe=5e60e8faae) | Oct 04, 2022 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [a7764ad0f6](https://linux-hardware.org/?probe=a7764ad0f6) | Oct 03, 2022 |
| Toshiba       | TECRA M11                   | [6680cedc5e](https://linux-hardware.org/?probe=6680cedc5e) | Oct 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [55f843ecf6](https://linux-hardware.org/?probe=55f843ecf6) | Oct 02, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [3bbd57ceea](https://linux-hardware.org/?probe=3bbd57ceea) | Oct 02, 2022 |
| Acer          | Swift SF114-34              | [5283dee456](https://linux-hardware.org/?probe=5283dee456) | Oct 02, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [9a2de7b77f](https://linux-hardware.org/?probe=9a2de7b77f) | Oct 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [32dba0444e](https://linux-hardware.org/?probe=32dba0444e) | Oct 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [46d6046fce](https://linux-hardware.org/?probe=46d6046fce) | Oct 02, 2022 |
| Toshiba       | Satellite L45               | [79ff097329](https://linux-hardware.org/?probe=79ff097329) | Oct 02, 2022 |
| Dell          | Inspiron 3501               | [4684b672f6](https://linux-hardware.org/?probe=4684b672f6) | Sep 30, 2022 |
| SK hynix      | HyBook                      | [38b5f704a1](https://linux-hardware.org/?probe=38b5f704a1) | Sep 30, 2022 |
| Dell          | Inspiron 3501               | [ce2d41ee99](https://linux-hardware.org/?probe=ce2d41ee99) | Sep 30, 2022 |
| Samsung       | R430/P430/R480              | [09795617ab](https://linux-hardware.org/?probe=09795617ab) | Sep 30, 2022 |
| AMI           | Cherry Trail CR             | [58caf99a77](https://linux-hardware.org/?probe=58caf99a77) | Sep 29, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [bd2dea6653](https://linux-hardware.org/?probe=bd2dea6653) | Sep 29, 2022 |
| AMI           | Cherry Trail CR             | [2d55b9b35e](https://linux-hardware.org/?probe=2d55b9b35e) | Sep 28, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [01cf3c6f99](https://linux-hardware.org/?probe=01cf3c6f99) | Sep 26, 2022 |
| HP            | Pavilion 15                 | [32670a0451](https://linux-hardware.org/?probe=32670a0451) | Sep 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [7dc3fbcf76](https://linux-hardware.org/?probe=7dc3fbcf76) | Sep 21, 2022 |
| Dell          | Latitude 7490               | [b8c3a5519a](https://linux-hardware.org/?probe=b8c3a5519a) | Sep 21, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [277daa8d6d](https://linux-hardware.org/?probe=277daa8d6d) | Sep 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [2ac6776181](https://linux-hardware.org/?probe=2ac6776181) | Sep 13, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [6f309073f2](https://linux-hardware.org/?probe=6f309073f2) | Sep 11, 2022 |
| Acer          | Aspire A315-42              | [820c1e2ac6](https://linux-hardware.org/?probe=820c1e2ac6) | Sep 11, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [f19e04efc1](https://linux-hardware.org/?probe=f19e04efc1) | Sep 10, 2022 |
| MSI           | Modern 14 B5M               | [b11b5bcba5](https://linux-hardware.org/?probe=b11b5bcba5) | Sep 09, 2022 |
| Lenovo        | 14w 81MQ00AVCL              | [c1a16c7963](https://linux-hardware.org/?probe=c1a16c7963) | Sep 06, 2022 |
| Lenovo        | 14w 81MQ00AVCL              | [2ae4968612](https://linux-hardware.org/?probe=2ae4968612) | Sep 06, 2022 |
| Lenovo        | ThinkPad T480 20L6S80G00    | [bd599c876c](https://linux-hardware.org/?probe=bd599c876c) | Sep 02, 2022 |
| HP            | Laptop 14-dq2xxx            | [bc4f5f8811](https://linux-hardware.org/?probe=bc4f5f8811) | Aug 24, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [7169cd34ab](https://linux-hardware.org/?probe=7169cd34ab) | Aug 22, 2022 |
| HP            | Pavilion g4                 | [f8c2fc628e](https://linux-hardware.org/?probe=f8c2fc628e) | Aug 21, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [59080cc039](https://linux-hardware.org/?probe=59080cc039) | Aug 17, 2022 |
| HP            | Laptop 14-dq2xxx            | [9cefc23bb3](https://linux-hardware.org/?probe=9cefc23bb3) | Aug 17, 2022 |
| Lenovo        | IdeaPad S540-13IML 81XA     | [9ee2e85959](https://linux-hardware.org/?probe=9ee2e85959) | Aug 14, 2022 |
| A-DATA Tec... | XENIA 14                    | [51cc14cc1f](https://linux-hardware.org/?probe=51cc14cc1f) | Aug 14, 2022 |
| HP            | Laptop 14-dq2xxx            | [eeed6b3d08](https://linux-hardware.org/?probe=eeed6b3d08) | Aug 14, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [818d0c73e8](https://linux-hardware.org/?probe=818d0c73e8) | Aug 12, 2022 |
| HP            | ENVY 17 Leap Motion SE N... | [efd4ec3ee7](https://linux-hardware.org/?probe=efd4ec3ee7) | Aug 11, 2022 |
| HP            | TouchSmart tm2              | [541d75d7ee](https://linux-hardware.org/?probe=541d75d7ee) | Aug 11, 2022 |
| HP            | TouchSmart tm2              | [77b260c9f1](https://linux-hardware.org/?probe=77b260c9f1) | Aug 11, 2022 |
| HP            | 240 G3                      | [77225815d2](https://linux-hardware.org/?probe=77225815d2) | Aug 10, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [832967e639](https://linux-hardware.org/?probe=832967e639) | Aug 09, 2022 |
| Google        | Treeya                      | [11f77c6171](https://linux-hardware.org/?probe=11f77c6171) | Aug 08, 2022 |
| Render        | NOTEBOOK Revision A         | [90a540652f](https://linux-hardware.org/?probe=90a540652f) | Aug 06, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | [53c997fe1f](https://linux-hardware.org/?probe=53c997fe1f) | Aug 05, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581LV_... | [764d4ebd1b](https://linux-hardware.org/?probe=764d4ebd1b) | Aug 04, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581LV_... | [5dab148c3e](https://linux-hardware.org/?probe=5dab148c3e) | Aug 04, 2022 |
| MOTILE        | M141                        | [7cdc678c70](https://linux-hardware.org/?probe=7cdc678c70) | Aug 03, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [745f6815cb](https://linux-hardware.org/?probe=745f6815cb) | Jul 30, 2022 |
| Sony          | VPCEA45FL                   | [8079ec1351](https://linux-hardware.org/?probe=8079ec1351) | Jul 29, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [a58ae4eb60](https://linux-hardware.org/?probe=a58ae4eb60) | Jul 24, 2022 |
| ASUSTek       | X541NA                      | [51aefa0464](https://linux-hardware.org/?probe=51aefa0464) | Jul 21, 2022 |
| Samsung       | 750XED                      | [546562ffbb](https://linux-hardware.org/?probe=546562ffbb) | Jul 21, 2022 |
| HP            | 245 G2                      | [03a8791b0c](https://linux-hardware.org/?probe=03a8791b0c) | Jul 18, 2022 |
| Dell          | MXG061                      | [9301162b93](https://linux-hardware.org/?probe=9301162b93) | Jul 18, 2022 |
| Lenovo        | ThinkPad Edge E430 32543... | [75cfb6ffa8](https://linux-hardware.org/?probe=75cfb6ffa8) | Jul 17, 2022 |
| HP            | 245 G2                      | [f37ddc5aed](https://linux-hardware.org/?probe=f37ddc5aed) | Jul 17, 2022 |
| Samsung       | 750XED                      | [eb7c27f7ff](https://linux-hardware.org/?probe=eb7c27f7ff) | Jul 15, 2022 |
| HP            | Pavilion g4                 | [40067cace0](https://linux-hardware.org/?probe=40067cace0) | Jul 14, 2022 |
| HP            | Laptop 14-fq0xxx            | [c21113bf90](https://linux-hardware.org/?probe=c21113bf90) | Jul 14, 2022 |
| Lenovo        | ThinkPad P50 20EQA05JCL     | [43f5b3c05d](https://linux-hardware.org/?probe=43f5b3c05d) | Jul 13, 2022 |
| HP            | Notebook                    | [1358a12fdf](https://linux-hardware.org/?probe=1358a12fdf) | Jul 13, 2022 |
| HP            | Pavilion g4                 | [96ba266748](https://linux-hardware.org/?probe=96ba266748) | Jul 11, 2022 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | [269ebd1a4d](https://linux-hardware.org/?probe=269ebd1a4d) | Jul 09, 2022 |
| Lenovo        | ThinkPad T61 6457B5S        | [34e97dae1e](https://linux-hardware.org/?probe=34e97dae1e) | Jul 08, 2022 |
| Samsung       | 305V4A/305V5A/3415VA        | [bcb40b4a21](https://linux-hardware.org/?probe=bcb40b4a21) | Jul 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [c8b9e41a50](https://linux-hardware.org/?probe=c8b9e41a50) | Jul 06, 2022 |
| HP            | Compaq 15                   | [fb14abab4d](https://linux-hardware.org/?probe=fb14abab4d) | Jun 30, 2022 |
| Lenovo        | ThinkPad X230 2325U5P       | [5b8770aaf7](https://linux-hardware.org/?probe=5b8770aaf7) | Jun 27, 2022 |
| Lenovo        | ThinkPad X230 2325U5P       | [d80f5059d2](https://linux-hardware.org/?probe=d80f5059d2) | Jun 27, 2022 |
| Lenovo        | ThinkPad X230 2325U5P       | [89b9650228](https://linux-hardware.org/?probe=89b9650228) | Jun 27, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [b56f69ff9c](https://linux-hardware.org/?probe=b56f69ff9c) | Jun 26, 2022 |
| Dell          | Inspiron 3505               | [1eaa95f069](https://linux-hardware.org/?probe=1eaa95f069) | Jun 24, 2022 |
| Samsung       | 750XED                      | [49322b3456](https://linux-hardware.org/?probe=49322b3456) | Jun 21, 2022 |
| Dell          | XPS 12 9Q23                 | [463461920a](https://linux-hardware.org/?probe=463461920a) | Jun 21, 2022 |
| Packard Be... | EasyNote MH36               | [ecd7a50e8e](https://linux-hardware.org/?probe=ecd7a50e8e) | Jun 20, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | [bbb3795dc2](https://linux-hardware.org/?probe=bbb3795dc2) | Jun 20, 2022 |
| HP            | Laptop 14-ck0xxx            | [234a9c1523](https://linux-hardware.org/?probe=234a9c1523) | Jun 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [cb268bf1ab](https://linux-hardware.org/?probe=cb268bf1ab) | Jun 18, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | [7d8683dfac](https://linux-hardware.org/?probe=7d8683dfac) | Jun 16, 2022 |
| Dell          | XPS 12 9Q23                 | [77c4dc4a62](https://linux-hardware.org/?probe=77c4dc4a62) | Jun 14, 2022 |
| HP            | Pavilion Notebook           | [cf08ff4333](https://linux-hardware.org/?probe=cf08ff4333) | Jun 14, 2022 |
| HP            | Pavilion Notebook           | [4b4bd76de7](https://linux-hardware.org/?probe=4b4bd76de7) | Jun 14, 2022 |
| Sony          | VPCM120AL                   | [9eb0e19bd0](https://linux-hardware.org/?probe=9eb0e19bd0) | Jun 13, 2022 |
| HP            | 240 G7                      | [2af5911cf8](https://linux-hardware.org/?probe=2af5911cf8) | Jun 12, 2022 |
| HP            | 240 G7                      | [bf52288eb2](https://linux-hardware.org/?probe=bf52288eb2) | Jun 10, 2022 |
| HP            | EliteBook 840 G5            | [73ba6fe3c0](https://linux-hardware.org/?probe=73ba6fe3c0) | Jun 06, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [83b786e73a](https://linux-hardware.org/?probe=83b786e73a) | Jun 04, 2022 |
| MSI           | Bravo 15 B5DD               | [d561d8dbdb](https://linux-hardware.org/?probe=d561d8dbdb) | Jun 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [abaa4456ea](https://linux-hardware.org/?probe=abaa4456ea) | Jun 01, 2022 |
| HP            | EliteBook 2560p             | [4ad762abcb](https://linux-hardware.org/?probe=4ad762abcb) | May 31, 2022 |
| HP            | 240 G7                      | [687546391a](https://linux-hardware.org/?probe=687546391a) | May 23, 2022 |
| Dell          | Inspiron 5459               | [ea99252046](https://linux-hardware.org/?probe=ea99252046) | May 20, 2022 |
| Unknown       | Unknown                     | [834d86e9da](https://linux-hardware.org/?probe=834d86e9da) | May 17, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [be93982cf0](https://linux-hardware.org/?probe=be93982cf0) | May 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [84ae0966e6](https://linux-hardware.org/?probe=84ae0966e6) | May 15, 2022 |
| HP            | EliteBook 840 G3            | [a7fb96d9aa](https://linux-hardware.org/?probe=a7fb96d9aa) | May 13, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | [74d92cc46f](https://linux-hardware.org/?probe=74d92cc46f) | May 11, 2022 |
| LG Electro... | 15Z995-U.ARS5U1             | [4efbc907db](https://linux-hardware.org/?probe=4efbc907db) | May 11, 2022 |
| Acer          | Aspire R7-371T              | [207110a3d4](https://linux-hardware.org/?probe=207110a3d4) | May 07, 2022 |
| HP            | EliteBook 2560p             | [c275c52e93](https://linux-hardware.org/?probe=c275c52e93) | May 04, 2022 |
| HP            | EliteBook 2560p             | [799038a9eb](https://linux-hardware.org/?probe=799038a9eb) | May 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [61e54407f3](https://linux-hardware.org/?probe=61e54407f3) | May 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [7d0cabeccf](https://linux-hardware.org/?probe=7d0cabeccf) | May 04, 2022 |
| HP            | Pavilion g4                 | [afad13fa01](https://linux-hardware.org/?probe=afad13fa01) | May 04, 2022 |
| Lenovo        | ThinkPad T61 7659A39        | [e5c32846e2](https://linux-hardware.org/?probe=e5c32846e2) | Apr 30, 2022 |
| Acer          | Aspire E5-411G              | [0629e76746](https://linux-hardware.org/?probe=0629e76746) | Apr 30, 2022 |
| HP            | Pavilion 14                 | [84bde5e223](https://linux-hardware.org/?probe=84bde5e223) | Apr 29, 2022 |
| HP            | Pavilion g4                 | [a10918283d](https://linux-hardware.org/?probe=a10918283d) | Apr 28, 2022 |
| Intel         | Unknown                     | [41b673dda8](https://linux-hardware.org/?probe=41b673dda8) | Apr 26, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [6fbbf00053](https://linux-hardware.org/?probe=6fbbf00053) | Apr 23, 2022 |
| Lenovo        | IdeaPadFlex 15 20309        | [6dac014a49](https://linux-hardware.org/?probe=6dac014a49) | Apr 22, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [4e2119abc8](https://linux-hardware.org/?probe=4e2119abc8) | Apr 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [d43a69ef63](https://linux-hardware.org/?probe=d43a69ef63) | Apr 21, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [28897f0c7b](https://linux-hardware.org/?probe=28897f0c7b) | Apr 13, 2022 |
| ASUSTek       | X405UQ                      | [4b63447e77](https://linux-hardware.org/?probe=4b63447e77) | Apr 10, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [4c367d8a9c](https://linux-hardware.org/?probe=4c367d8a9c) | Apr 08, 2022 |
| Dell          | Vostro A860                 | [15ce9e1f63](https://linux-hardware.org/?probe=15ce9e1f63) | Apr 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [4ad9fe021c](https://linux-hardware.org/?probe=4ad9fe021c) | Mar 31, 2022 |
| Dell          | Latitude E5450              | [776f0672a0](https://linux-hardware.org/?probe=776f0672a0) | Mar 23, 2022 |
| Dell          | Latitude E5450              | [fb7f18d5a2](https://linux-hardware.org/?probe=fb7f18d5a2) | Mar 23, 2022 |
| HUAWEI        | KLVL-WXX9                   | [95acb8d0af](https://linux-hardware.org/?probe=95acb8d0af) | Mar 21, 2022 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [95c6b15672](https://linux-hardware.org/?probe=95c6b15672) | Mar 14, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [82cfb46909](https://linux-hardware.org/?probe=82cfb46909) | Mar 13, 2022 |
| Packard Be... | EasyNote MH35               | [66bff1bcfd](https://linux-hardware.org/?probe=66bff1bcfd) | Mar 08, 2022 |
| ASUSTek       | G752VY                      | [379733b3e7](https://linux-hardware.org/?probe=379733b3e7) | Mar 07, 2022 |
| Elife         | series                      | [dddf04aa69](https://linux-hardware.org/?probe=dddf04aa69) | Mar 05, 2022 |
| Elife         | series                      | [979e43c05a](https://linux-hardware.org/?probe=979e43c05a) | Mar 05, 2022 |
| HP            | 2140                        | [6956607bfd](https://linux-hardware.org/?probe=6956607bfd) | Mar 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2f1bb56767](https://linux-hardware.org/?probe=2f1bb56767) | Feb 28, 2022 |
| Lenovo        | ThinkPad T490 20RXS0VX00    | [8f42f6fd5f](https://linux-hardware.org/?probe=8f42f6fd5f) | Feb 28, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [8dfdb07f98](https://linux-hardware.org/?probe=8dfdb07f98) | Feb 24, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [7a8aaaa5a6](https://linux-hardware.org/?probe=7a8aaaa5a6) | Feb 23, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [849ceb3653](https://linux-hardware.org/?probe=849ceb3653) | Feb 23, 2022 |
| Lenovo        | ThinkPad T495 20NJ0004US    | [d8002e9eae](https://linux-hardware.org/?probe=d8002e9eae) | Feb 23, 2022 |
| Google        | Barla                       | [12180ab1ff](https://linux-hardware.org/?probe=12180ab1ff) | Feb 22, 2022 |
| Toshiba       | Satellite L505              | [16e608fb6b](https://linux-hardware.org/?probe=16e608fb6b) | Feb 22, 2022 |
| HP            | ENVY 15                     | [9758bb9b66](https://linux-hardware.org/?probe=9758bb9b66) | Feb 20, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [46021e669f](https://linux-hardware.org/?probe=46021e669f) | Feb 17, 2022 |
| Apple         | MacBookPro11,3              | [4de3659979](https://linux-hardware.org/?probe=4de3659979) | Feb 16, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [c81bbf6c93](https://linux-hardware.org/?probe=c81bbf6c93) | Feb 16, 2022 |
| Apple         | MacBookPro11,3              | [309f440466](https://linux-hardware.org/?probe=309f440466) | Feb 15, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [81f2a365be](https://linux-hardware.org/?probe=81f2a365be) | Feb 13, 2022 |
| HP            | Laptop 15-da0xxx            | [18fa19a4f0](https://linux-hardware.org/?probe=18fa19a4f0) | Feb 10, 2022 |
| HP            | EliteBook 840 G6            | [dae40dba1f](https://linux-hardware.org/?probe=dae40dba1f) | Feb 09, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [3060acc083](https://linux-hardware.org/?probe=3060acc083) | Jan 22, 2022 |
| Acer          | Aspire ES1-111M             | [02368f5bb1](https://linux-hardware.org/?probe=02368f5bb1) | Jan 22, 2022 |
| Lenovo        | G400 20235                  | [cba5cda239](https://linux-hardware.org/?probe=cba5cda239) | Jan 21, 2022 |
| HP            | Laptop 15-da1xxx            | [d6706833ff](https://linux-hardware.org/?probe=d6706833ff) | Jan 21, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [c00dd7c570](https://linux-hardware.org/?probe=c00dd7c570) | Jan 18, 2022 |
| Dell          | Inspiron 3480               | [ca729da91f](https://linux-hardware.org/?probe=ca729da91f) | Jan 16, 2022 |
| Lenovo        | ThinkPad T480 20L6A0UGCL    | [e9dbb29c83](https://linux-hardware.org/?probe=e9dbb29c83) | Jan 16, 2022 |
| Acer          | AOD255E                     | [cf1f3ab0e0](https://linux-hardware.org/?probe=cf1f3ab0e0) | Jan 13, 2022 |
| HP            | Pavilion 15                 | [95f3d87b66](https://linux-hardware.org/?probe=95f3d87b66) | Jan 09, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [edc40344ef](https://linux-hardware.org/?probe=edc40344ef) | Jan 08, 2022 |
| HONOR         | NBR-WAX9                    | [979f80197d](https://linux-hardware.org/?probe=979f80197d) | Jan 07, 2022 |
| Sony          | SVE14A390X                  | [3b11d123cf](https://linux-hardware.org/?probe=3b11d123cf) | Jan 04, 2022 |
| HP            | EliteBook 6930p             | [0346ff374d](https://linux-hardware.org/?probe=0346ff374d) | Dec 26, 2021 |
| Acer          | Aspire E1-531               | [d1d6054fc3](https://linux-hardware.org/?probe=d1d6054fc3) | Dec 22, 2021 |
| Google        | Barla                       | [cfdb4935cd](https://linux-hardware.org/?probe=cfdb4935cd) | Dec 21, 2021 |
| Google        | Barla                       | [0629410759](https://linux-hardware.org/?probe=0629410759) | Dec 21, 2021 |
| HP            | EliteBook 840 G6            | [46dab8c74a](https://linux-hardware.org/?probe=46dab8c74a) | Dec 16, 2021 |
| Samsung       | R510/P510                   | [37a9793570](https://linux-hardware.org/?probe=37a9793570) | Dec 08, 2021 |
| Dell          | Inspiron 14-3467            | [c53e56384e](https://linux-hardware.org/?probe=c53e56384e) | Dec 07, 2021 |
| Samsung       | R510/P510                   | [f55c0c88cc](https://linux-hardware.org/?probe=f55c0c88cc) | Dec 07, 2021 |
| Lenovo        | ThinkPad T460 20FMA03MCL    | [aecb392c83](https://linux-hardware.org/?probe=aecb392c83) | Dec 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [18da52385a](https://linux-hardware.org/?probe=18da52385a) | Dec 04, 2021 |
| Acer          | Swift SF113-31              | [f1e3d8c722](https://linux-hardware.org/?probe=f1e3d8c722) | Nov 29, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [baa3bf4a04](https://linux-hardware.org/?probe=baa3bf4a04) | Nov 27, 2021 |
| Dell          | Inspiron M5010              | [489679b294](https://linux-hardware.org/?probe=489679b294) | Nov 27, 2021 |
| ASUSTek       | TUF Gaming FX506LI_FX506... | [93b6cabcb6](https://linux-hardware.org/?probe=93b6cabcb6) | Nov 25, 2021 |
| HP            | 245 G6                      | [103da5dd76](https://linux-hardware.org/?probe=103da5dd76) | Nov 25, 2021 |
| Acer          | Aspire V5-471P              | [bf3b81cbb6](https://linux-hardware.org/?probe=bf3b81cbb6) | Nov 20, 2021 |
| HP            | 250 G5 Notebook PC          | [befb5b9afe](https://linux-hardware.org/?probe=befb5b9afe) | Nov 18, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [787fc2d581](https://linux-hardware.org/?probe=787fc2d581) | Nov 18, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [d26e2fac89](https://linux-hardware.org/?probe=d26e2fac89) | Nov 17, 2021 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | [10a3cb9d12](https://linux-hardware.org/?probe=10a3cb9d12) | Nov 15, 2021 |
| Lenovo        | IdeaPad 720S-14IKB 80XC     | [d0f383a016](https://linux-hardware.org/?probe=d0f383a016) | Nov 13, 2021 |
| Unknown       | Unknown                     | [a61385548e](https://linux-hardware.org/?probe=a61385548e) | Nov 13, 2021 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [8b26cea464](https://linux-hardware.org/?probe=8b26cea464) | Nov 13, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [835c948f68](https://linux-hardware.org/?probe=835c948f68) | Nov 13, 2021 |
| Samsung       | 550P5C/550P7C               | [31bc59dcb9](https://linux-hardware.org/?probe=31bc59dcb9) | Nov 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [ab746b7399](https://linux-hardware.org/?probe=ab746b7399) | Nov 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [258e2f1594](https://linux-hardware.org/?probe=258e2f1594) | Nov 08, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [1dd0c3ba0a](https://linux-hardware.org/?probe=1dd0c3ba0a) | Nov 05, 2021 |
| HP            | 250 G5 Notebook PC          | [d6eff141a3](https://linux-hardware.org/?probe=d6eff141a3) | Nov 04, 2021 |
| Acer          | Aspire ES1-311              | [594175a2ac](https://linux-hardware.org/?probe=594175a2ac) | Nov 01, 2021 |
| Dell          | Vostro 3500                 | [befb41472e](https://linux-hardware.org/?probe=befb41472e) | Oct 23, 2021 |
| Samsung       | 550P5C/550P7C               | [2713972f14](https://linux-hardware.org/?probe=2713972f14) | Oct 22, 2021 |
| HP            | 250 G6 Notebook PC          | [7076268ecc](https://linux-hardware.org/?probe=7076268ecc) | Oct 17, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [f7524634b9](https://linux-hardware.org/?probe=f7524634b9) | Oct 16, 2021 |
| HP            | Compaq CQ45                 | [e51cebc629](https://linux-hardware.org/?probe=e51cebc629) | Oct 16, 2021 |
| HP            | Compaq CQ45                 | [18a1e9d294](https://linux-hardware.org/?probe=18a1e9d294) | Oct 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [06b7518f72](https://linux-hardware.org/?probe=06b7518f72) | Oct 14, 2021 |
| Acer          | Aspire ES1-311              | [8f1dd3ce3a](https://linux-hardware.org/?probe=8f1dd3ce3a) | Oct 12, 2021 |
| ASUSTek       | X302LJ                      | [a0e3e93f48](https://linux-hardware.org/?probe=a0e3e93f48) | Oct 12, 2021 |
| Acer          | Aspire ES1-311              | [df266accf1](https://linux-hardware.org/?probe=df266accf1) | Oct 12, 2021 |
| ASUSTek       | X302LJ                      | [ad35db71c7](https://linux-hardware.org/?probe=ad35db71c7) | Oct 12, 2021 |
| Lenovo        | Y520-15IKBM 80YY            | [fc28e4f7f8](https://linux-hardware.org/?probe=fc28e4f7f8) | Oct 10, 2021 |
| HP            | x2 210                      | [ccf01919ab](https://linux-hardware.org/?probe=ccf01919ab) | Oct 09, 2021 |
| HP            | x2 210                      | [a35274c0a7](https://linux-hardware.org/?probe=a35274c0a7) | Oct 09, 2021 |
| HP            | Notebook                    | [d332712e6f](https://linux-hardware.org/?probe=d332712e6f) | Oct 08, 2021 |
| HP            | Notebook                    | [04313f623e](https://linux-hardware.org/?probe=04313f623e) | Oct 07, 2021 |
| HP            | Notebook                    | [282f030bc4](https://linux-hardware.org/?probe=282f030bc4) | Oct 07, 2021 |
| Alienware     | M17xR3                      | [740de1796c](https://linux-hardware.org/?probe=740de1796c) | Oct 05, 2021 |
| Dell          | Inspiron N5110              | [8ea6adfced](https://linux-hardware.org/?probe=8ea6adfced) | Oct 03, 2021 |
| ASUSTek       | X555LB                      | [3af223c792](https://linux-hardware.org/?probe=3af223c792) | Sep 30, 2021 |
| Dell          | G3 3590                     | [519cea3f38](https://linux-hardware.org/?probe=519cea3f38) | Sep 25, 2021 |
| Dell          | G3 3590                     | [bb25c895cf](https://linux-hardware.org/?probe=bb25c895cf) | Sep 25, 2021 |
| ASUSTek       | X302LJ                      | [281beb5fe7](https://linux-hardware.org/?probe=281beb5fe7) | Sep 23, 2021 |
| Acer          | Aspire ES1-572              | [36c622eabc](https://linux-hardware.org/?probe=36c622eabc) | Sep 21, 2021 |
| Acer          | Aspire ES1-572              | [0ce8da0fe0](https://linux-hardware.org/?probe=0ce8da0fe0) | Sep 21, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [079bf76915](https://linux-hardware.org/?probe=079bf76915) | Sep 18, 2021 |
| HP            | EliteBook 840 G5            | [68305a2ede](https://linux-hardware.org/?probe=68305a2ede) | Sep 15, 2021 |
| Dell          | Inspiron 5459               | [ef87caa5ba](https://linux-hardware.org/?probe=ef87caa5ba) | Sep 12, 2021 |
| Dell          | Inspiron 5459               | [feea6f3fec](https://linux-hardware.org/?probe=feea6f3fec) | Sep 11, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [15ed5db330](https://linux-hardware.org/?probe=15ed5db330) | Sep 09, 2021 |
| ASUSTek       | TUF Gaming FX506LI_FX506... | [890790d388](https://linux-hardware.org/?probe=890790d388) | Sep 07, 2021 |
| ASUSTek       | TUF Gaming FX506LI_FX506... | [341d88eae9](https://linux-hardware.org/?probe=341d88eae9) | Sep 07, 2021 |
| Dell          | Inspiron N5110              | [a8f9c859be](https://linux-hardware.org/?probe=a8f9c859be) | Sep 05, 2021 |
| Dell          | Inspiron N5110              | [3c5b6aa997](https://linux-hardware.org/?probe=3c5b6aa997) | Sep 05, 2021 |
| Acer          | Swift SF314-59              | [f6df33267b](https://linux-hardware.org/?probe=f6df33267b) | Sep 02, 2021 |
| Lenovo        | G480 20156                  | [436287e7dc](https://linux-hardware.org/?probe=436287e7dc) | Sep 02, 2021 |
| Lenovo        | G480 20156                  | [a89f3e4acf](https://linux-hardware.org/?probe=a89f3e4acf) | Sep 02, 2021 |
| HP            | EliteBook Folio 1040 G3     | [6bf33dd2cb](https://linux-hardware.org/?probe=6bf33dd2cb) | Sep 01, 2021 |
| ASUSTek       | UX410UQK                    | [d2804fad00](https://linux-hardware.org/?probe=d2804fad00) | Sep 01, 2021 |
| ASUSTek       | UX410UQK                    | [819b70e8cb](https://linux-hardware.org/?probe=819b70e8cb) | Sep 01, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [93a7aa0485](https://linux-hardware.org/?probe=93a7aa0485) | Aug 31, 2021 |
| Apple         | MacBookPro11,1              | [1dbc26a990](https://linux-hardware.org/?probe=1dbc26a990) | Aug 29, 2021 |
| Toshiba       | Satellite C845D             | [ac992ef3e5](https://linux-hardware.org/?probe=ac992ef3e5) | Aug 29, 2021 |
| Lenovo        | ThinkPad X260 20F5S3J00D    | [eeb6586c28](https://linux-hardware.org/?probe=eeb6586c28) | Aug 26, 2021 |
| Sony          | VGN-NW215T                  | [3b59710f01](https://linux-hardware.org/?probe=3b59710f01) | Aug 25, 2021 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | [207f0c8966](https://linux-hardware.org/?probe=207f0c8966) | Aug 24, 2021 |
| Acer          | Aspire 7741                 | [849c1fe7e3](https://linux-hardware.org/?probe=849c1fe7e3) | Aug 22, 2021 |
| HP            | ProBook 440 G3              | [80aa412668](https://linux-hardware.org/?probe=80aa412668) | Aug 22, 2021 |
| Lenovo        | V145-15AST 81MT             | [28d8feb60d](https://linux-hardware.org/?probe=28d8feb60d) | Aug 20, 2021 |
| Lenovo        | V145-15AST 81MT             | [f207dc8e9a](https://linux-hardware.org/?probe=f207dc8e9a) | Aug 20, 2021 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | [ab27a12603](https://linux-hardware.org/?probe=ab27a12603) | Aug 18, 2021 |
| Dell          | Inspiron 5459               | [b99b48660a](https://linux-hardware.org/?probe=b99b48660a) | Aug 08, 2021 |
| Sony          | SVE14A27CLS                 | [53a5965063](https://linux-hardware.org/?probe=53a5965063) | Aug 07, 2021 |
| HP            | ProBook 640 G1              | [4d0bb591af](https://linux-hardware.org/?probe=4d0bb591af) | Aug 06, 2021 |
| Dell          | G3 3590                     | [16bdb588e1](https://linux-hardware.org/?probe=16bdb588e1) | Aug 05, 2021 |
| Dell          | G3 3590                     | [01a9560f9c](https://linux-hardware.org/?probe=01a9560f9c) | Aug 05, 2021 |
| Packard Be... | EasyNote MH35               | [e053c132dc](https://linux-hardware.org/?probe=e053c132dc) | Aug 02, 2021 |
| Dell          | Inspiron 5459               | [acc597c748](https://linux-hardware.org/?probe=acc597c748) | Aug 02, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [2e753f12ce](https://linux-hardware.org/?probe=2e753f12ce) | Jul 28, 2021 |
| Medion        | Unknown                     | [021ba4d5b5](https://linux-hardware.org/?probe=021ba4d5b5) | Jul 25, 2021 |
| Medion        | Unknown                     | [e9c5e99e0b](https://linux-hardware.org/?probe=e9c5e99e0b) | Jul 25, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [1d0f458592](https://linux-hardware.org/?probe=1d0f458592) | Jul 23, 2021 |
| Acer          | Swift SF314-42              | [f8812e14cb](https://linux-hardware.org/?probe=f8812e14cb) | Jul 23, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [0d3be70373](https://linux-hardware.org/?probe=0d3be70373) | Jul 20, 2021 |
| HP            | ENVY 15                     | [d2a3149a9a](https://linux-hardware.org/?probe=d2a3149a9a) | Jul 17, 2021 |
| HP            | ProBook 640 G1              | [2db57969aa](https://linux-hardware.org/?probe=2db57969aa) | Jul 17, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [f024f2512e](https://linux-hardware.org/?probe=f024f2512e) | Jul 14, 2021 |
| HP            | Spectre Laptop 13-af0xx     | [bfef4cded0](https://linux-hardware.org/?probe=bfef4cded0) | Jul 09, 2021 |
| Lenovo        | G40-30 80FY                 | [ef9a6d3444](https://linux-hardware.org/?probe=ef9a6d3444) | Jul 08, 2021 |
| HP            | Notebook                    | [3087e92283](https://linux-hardware.org/?probe=3087e92283) | Jun 29, 2021 |
| HP            | ENVY Laptop 13-ah0xxx       | [48a1dddc38](https://linux-hardware.org/?probe=48a1dddc38) | Jun 27, 2021 |
| ASUSTek       | N551JX                      | [3ef394cafb](https://linux-hardware.org/?probe=3ef394cafb) | Jun 24, 2021 |
| Toshiba       | PORTEGE R705                | [fe7063735e](https://linux-hardware.org/?probe=fe7063735e) | Jun 24, 2021 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [9d80703f35](https://linux-hardware.org/?probe=9d80703f35) | Jun 23, 2021 |
| Dell          | Inspiron 5459               | [22f31e0de1](https://linux-hardware.org/?probe=22f31e0de1) | Jun 19, 2021 |
| Toshiba       | PORTEGE R705                | [a53fb9eb09](https://linux-hardware.org/?probe=a53fb9eb09) | Jun 19, 2021 |
| HP            | Notebook                    | [f1263ec1fc](https://linux-hardware.org/?probe=f1263ec1fc) | Jun 13, 2021 |
| Acer          | Aspire A515-56              | [6529cc537c](https://linux-hardware.org/?probe=6529cc537c) | Jun 13, 2021 |
| Acer          | Aspire A515-56              | [2aa173f32b](https://linux-hardware.org/?probe=2aa173f32b) | Jun 12, 2021 |
| Unknown       | Unknown                     | [16d75c0003](https://linux-hardware.org/?probe=16d75c0003) | Jun 11, 2021 |
| Samsung       | 670Z5E                      | [252e20c152](https://linux-hardware.org/?probe=252e20c152) | Jun 11, 2021 |
| Dell          | Inspiron 5567               | [0ffe39ef8d](https://linux-hardware.org/?probe=0ffe39ef8d) | Jun 09, 2021 |
| Sony          | SVE14113ELW                 | [738c72c21c](https://linux-hardware.org/?probe=738c72c21c) | Jun 09, 2021 |
| HP            | ENVY 15                     | [8d7a772e05](https://linux-hardware.org/?probe=8d7a772e05) | Jun 07, 2021 |
| Dell          | Precision 5520              | [199dec46c7](https://linux-hardware.org/?probe=199dec46c7) | Jun 01, 2021 |
| HP            | 1000                        | [21fb6389e7](https://linux-hardware.org/?probe=21fb6389e7) | Jun 01, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [4688dc5b46](https://linux-hardware.org/?probe=4688dc5b46) | May 29, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [b1500a1319](https://linux-hardware.org/?probe=b1500a1319) | May 28, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [abc55fc46d](https://linux-hardware.org/?probe=abc55fc46d) | May 28, 2021 |
| Personal C... | Iris                        | [835df5c61e](https://linux-hardware.org/?probe=835df5c61e) | May 27, 2021 |
| Toshiba       | PORTEGE R705                | [afd83c5750](https://linux-hardware.org/?probe=afd83c5750) | May 25, 2021 |
| Acer          | Swift SF313-53              | [66e4f1aeff](https://linux-hardware.org/?probe=66e4f1aeff) | May 23, 2021 |
| Unknown       | Unknown                     | [e9dc8181d8](https://linux-hardware.org/?probe=e9dc8181d8) | May 20, 2021 |
| Toshiba       | Satellite L45-B             | [544d468137](https://linux-hardware.org/?probe=544d468137) | May 16, 2021 |
| HP            | 435                         | [65bbde1e13](https://linux-hardware.org/?probe=65bbde1e13) | May 16, 2021 |
| HP            | 435                         | [fe5a82cf02](https://linux-hardware.org/?probe=fe5a82cf02) | May 16, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [a98d93888d](https://linux-hardware.org/?probe=a98d93888d) | May 14, 2021 |
| Dell          | Latitude 7490               | [c533165389](https://linux-hardware.org/?probe=c533165389) | May 13, 2021 |
| Samsung       | RF712                       | [a3624b29fa](https://linux-hardware.org/?probe=a3624b29fa) | May 11, 2021 |
| Samsung       | RF712                       | [652fb28adb](https://linux-hardware.org/?probe=652fb28adb) | May 11, 2021 |
| Acer          | Swift SF313-53              | [2e4262cb53](https://linux-hardware.org/?probe=2e4262cb53) | May 11, 2021 |
| Dell          | Inspiron 5567               | [aacf9438d2](https://linux-hardware.org/?probe=aacf9438d2) | May 11, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [2196430972](https://linux-hardware.org/?probe=2196430972) | May 09, 2021 |
| HP            | EliteBook 840 G6            | [08d59f23ab](https://linux-hardware.org/?probe=08d59f23ab) | May 09, 2021 |
| HP            | 1000                        | [4205750e24](https://linux-hardware.org/?probe=4205750e24) | May 08, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [ce41256b96](https://linux-hardware.org/?probe=ce41256b96) | May 07, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [566133628f](https://linux-hardware.org/?probe=566133628f) | May 07, 2021 |
| Toshiba       | Satellite U505              | [50baa8508f](https://linux-hardware.org/?probe=50baa8508f) | May 05, 2021 |
| Toshiba       | Satellite U505              | [c5785176bd](https://linux-hardware.org/?probe=c5785176bd) | May 05, 2021 |
| Packard Be... | EasyNote TM98               | [2bb98626e9](https://linux-hardware.org/?probe=2bb98626e9) | May 03, 2021 |
| HUAWEI        | WRTB-WXX9                   | [f9ceb7c523](https://linux-hardware.org/?probe=f9ceb7c523) | May 02, 2021 |
| Dell          | Latitude D630               | [40a03f054f](https://linux-hardware.org/?probe=40a03f054f) | May 02, 2021 |
| Acer          | Aspire ES1-431              | [cc8dd98cc6](https://linux-hardware.org/?probe=cc8dd98cc6) | May 01, 2021 |
| HP            | 14                          | [f2874ea965](https://linux-hardware.org/?probe=f2874ea965) | May 01, 2021 |
| HP            | ENVY 17 Leap Motion SE N... | [18b8d3d480](https://linux-hardware.org/?probe=18b8d3d480) | Apr 30, 2021 |
| HP            | Pavilion dm4                | [dd8938cac1](https://linux-hardware.org/?probe=dd8938cac1) | Apr 29, 2021 |
| Dell          | System Inspiron N4110       | [17b9bc8eb3](https://linux-hardware.org/?probe=17b9bc8eb3) | Apr 27, 2021 |
| HP            | ProBook 430 G3              | [c3acaeb030](https://linux-hardware.org/?probe=c3acaeb030) | Apr 26, 2021 |
| HP            | ProBook 430 G3              | [de3298645e](https://linux-hardware.org/?probe=de3298645e) | Apr 26, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [8ff356e9be](https://linux-hardware.org/?probe=8ff356e9be) | Apr 25, 2021 |
| Packard Be... | EasyNote_BU45               | [83204d550c](https://linux-hardware.org/?probe=83204d550c) | Apr 19, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0DU0... | [998919a455](https://linux-hardware.org/?probe=998919a455) | Apr 18, 2021 |
| Dell          | Latitude 7410               | [7792c66c17](https://linux-hardware.org/?probe=7792c66c17) | Apr 15, 2021 |
| ASUSTek       | ROG Zephyrus GX550LXS_GX... | [8eeff8c77c](https://linux-hardware.org/?probe=8eeff8c77c) | Apr 13, 2021 |
| Dell          | Latitude 7400               | [41a2361010](https://linux-hardware.org/?probe=41a2361010) | Apr 11, 2021 |
| Acer          | Aspire ES1-431              | [9109f31570](https://linux-hardware.org/?probe=9109f31570) | Apr 10, 2021 |
| Acer          | Aspire ES1-431              | [df53cbed23](https://linux-hardware.org/?probe=df53cbed23) | Apr 10, 2021 |
| Toshiba       | PORTEGE R705                | [dd16cda442](https://linux-hardware.org/?probe=dd16cda442) | Apr 10, 2021 |
| ASUSTek       | N46VB                       | [a425e290d7](https://linux-hardware.org/?probe=a425e290d7) | Apr 09, 2021 |
| Personal C... | Iris                        | [add36a3a7c](https://linux-hardware.org/?probe=add36a3a7c) | Apr 09, 2021 |
| Personal C... | Iris                        | [4ec2ee9e6d](https://linux-hardware.org/?probe=4ec2ee9e6d) | Apr 09, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [adb7fbfc0d](https://linux-hardware.org/?probe=adb7fbfc0d) | Apr 08, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [9b9172e5a7](https://linux-hardware.org/?probe=9b9172e5a7) | Apr 08, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U2S... | [3c44770d1a](https://linux-hardware.org/?probe=3c44770d1a) | Apr 07, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U2S... | [3a85124409](https://linux-hardware.org/?probe=3a85124409) | Apr 07, 2021 |
| HP            | ENVY Notebook               | [83a0078309](https://linux-hardware.org/?probe=83a0078309) | Apr 06, 2021 |
| Dell          | Inspiron 5459               | [f3b9205a6c](https://linux-hardware.org/?probe=f3b9205a6c) | Apr 06, 2021 |
| Dell          | Inspiron 1545               | [ace9676e8c](https://linux-hardware.org/?probe=ace9676e8c) | Apr 05, 2021 |
| HP            | 15                          | [69d2aa2538](https://linux-hardware.org/?probe=69d2aa2538) | Apr 05, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0DU0... | [8d5f33367e](https://linux-hardware.org/?probe=8d5f33367e) | Apr 04, 2021 |
| Lenovo        | IdeaPad Y480                | [d0aeb8aafc](https://linux-hardware.org/?probe=d0aeb8aafc) | Apr 03, 2021 |
| Dell          | Inspiron 3420               | [4d76b6366d](https://linux-hardware.org/?probe=4d76b6366d) | Apr 01, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [742b7afcc8](https://linux-hardware.org/?probe=742b7afcc8) | Apr 01, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [8856c82ed6](https://linux-hardware.org/?probe=8856c82ed6) | Mar 31, 2021 |
| HP            | ENVY 15                     | [31c601923e](https://linux-hardware.org/?probe=31c601923e) | Mar 31, 2021 |
| HP            | ENVY 15                     | [3628d88bc1](https://linux-hardware.org/?probe=3628d88bc1) | Mar 31, 2021 |
| HP            | 250 G4 Notebook PC          | [e3119c3a18](https://linux-hardware.org/?probe=e3119c3a18) | Mar 30, 2021 |
| HP            | 245 G7 Notebook PC          | [3a4703f85d](https://linux-hardware.org/?probe=3a4703f85d) | Mar 27, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [867936010e](https://linux-hardware.org/?probe=867936010e) | Mar 25, 2021 |
| Dell          | Inspiron 14-3467            | [6079a062b3](https://linux-hardware.org/?probe=6079a062b3) | Mar 18, 2021 |
| HP            | 240 G7 Notebook PC          | [669e53f097](https://linux-hardware.org/?probe=669e53f097) | Mar 16, 2021 |
| Dell          | Inspiron 5721               | [0f95174924](https://linux-hardware.org/?probe=0f95174924) | Mar 15, 2021 |
| HP            | Notebook                    | [9c176242dd](https://linux-hardware.org/?probe=9c176242dd) | Mar 14, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [e2e99630ca](https://linux-hardware.org/?probe=e2e99630ca) | Mar 14, 2021 |
| HP            | 15                          | [08b381f369](https://linux-hardware.org/?probe=08b381f369) | Mar 12, 2021 |
| Dell          | Inspiron 14-3467            | [0611d13dff](https://linux-hardware.org/?probe=0611d13dff) | Mar 11, 2021 |
| HP            | ProBook 440 G3              | [fc6181a7c1](https://linux-hardware.org/?probe=fc6181a7c1) | Mar 11, 2021 |
| HP            | ProBook 440 G3              | [38042c5772](https://linux-hardware.org/?probe=38042c5772) | Mar 11, 2021 |
| Toshiba       | PORTEGE R705                | [f537f51a95](https://linux-hardware.org/?probe=f537f51a95) | Mar 09, 2021 |
| Acer          | Aspire 5738                 | [a1a9e12988](https://linux-hardware.org/?probe=a1a9e12988) | Mar 07, 2021 |
| MSI           | Stealth 15M A11SEK          | [1187156178](https://linux-hardware.org/?probe=1187156178) | Mar 05, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [76006e9ba5](https://linux-hardware.org/?probe=76006e9ba5) | Mar 01, 2021 |
| Dell          | Inspiron 14-3467            | [7991d50dfd](https://linux-hardware.org/?probe=7991d50dfd) | Mar 01, 2021 |
| Unknown       | Unknown                     | [e8359056f7](https://linux-hardware.org/?probe=e8359056f7) | Feb 26, 2021 |
| HP            | Pavilion Notebook           | [45dfe3c2b1](https://linux-hardware.org/?probe=45dfe3c2b1) | Feb 24, 2021 |
| Dell          | Vostro V13                  | [f9b40741e7](https://linux-hardware.org/?probe=f9b40741e7) | Feb 19, 2021 |
| Toshiba       | Satellite C845D             | [6a73d1fd72](https://linux-hardware.org/?probe=6a73d1fd72) | Feb 19, 2021 |
| Packard Be... | EasyNote TM85               | [972a7d0f8c](https://linux-hardware.org/?probe=972a7d0f8c) | Feb 17, 2021 |
| ASUSTek       | GL502VMK                    | [54b49d2dc7](https://linux-hardware.org/?probe=54b49d2dc7) | Feb 15, 2021 |
| ASUSTek       | GL502VMK                    | [514a434029](https://linux-hardware.org/?probe=514a434029) | Feb 15, 2021 |
| Dell          | Latitude 3440               | [d2806294ef](https://linux-hardware.org/?probe=d2806294ef) | Feb 13, 2021 |
| Unknown       | Unknown                     | [acd23bb798](https://linux-hardware.org/?probe=acd23bb798) | Feb 13, 2021 |
| Sony          | VPCEG15FL                   | [48a16e8a4a](https://linux-hardware.org/?probe=48a16e8a4a) | Feb 10, 2021 |
| Dell          | System Inspiron N411Z       | [eed8ecb624](https://linux-hardware.org/?probe=eed8ecb624) | Feb 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd F... | [799c301ad6](https://linux-hardware.org/?probe=799c301ad6) | Feb 08, 2021 |
| Dell          | System Inspiron N411Z       | [f6ea43033f](https://linux-hardware.org/?probe=f6ea43033f) | Feb 07, 2021 |
| Toshiba       | Satellite L745              | [01a4eafbb6](https://linux-hardware.org/?probe=01a4eafbb6) | Feb 02, 2021 |
| Toshiba       | Satellite L745              | [9cc5c245d0](https://linux-hardware.org/?probe=9cc5c245d0) | Feb 02, 2021 |
| HP            | 240 G6 Notebook PC          | [2ba1c141b8](https://linux-hardware.org/?probe=2ba1c141b8) | Feb 01, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [3f400fbc08](https://linux-hardware.org/?probe=3f400fbc08) | Jan 31, 2021 |
| ASUSTek       | UX430UNR                    | [e32eec7802](https://linux-hardware.org/?probe=e32eec7802) | Jan 27, 2021 |
| HP            | EliteBook 2560p             | [8289f3c10b](https://linux-hardware.org/?probe=8289f3c10b) | Jan 24, 2021 |
| HP            | Pavilion 15                 | [b83dc673fd](https://linux-hardware.org/?probe=b83dc673fd) | Jan 23, 2021 |
| HP            | 14                          | [7c1ff6f4a8](https://linux-hardware.org/?probe=7c1ff6f4a8) | Jan 22, 2021 |
| Dell          | Vostro 1520                 | [36392e13b5](https://linux-hardware.org/?probe=36392e13b5) | Jan 22, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [5f648131f5](https://linux-hardware.org/?probe=5f648131f5) | Jan 19, 2021 |
| ASUSTek       | UX310UQK                    | [7006cf4aa0](https://linux-hardware.org/?probe=7006cf4aa0) | Jan 13, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [4b69e8576c](https://linux-hardware.org/?probe=4b69e8576c) | Jan 11, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [7ae430600b](https://linux-hardware.org/?probe=7ae430600b) | Jan 07, 2021 |
| HP            | EliteBook 840 G6            | [5d26e74a5d](https://linux-hardware.org/?probe=5d26e74a5d) | Jan 07, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [1ce6d33d5b](https://linux-hardware.org/?probe=1ce6d33d5b) | Jan 07, 2021 |
| HP            | Notebook                    | [38341a3370](https://linux-hardware.org/?probe=38341a3370) | Jan 06, 2021 |
| HP            | EliteBook 840 G6            | [724662dec7](https://linux-hardware.org/?probe=724662dec7) | Jan 05, 2021 |
| Sony          | SVE14113ELW                 | [695f68585f](https://linux-hardware.org/?probe=695f68585f) | Jan 05, 2021 |
| Sony          | SVE14113ELW                 | [88ef270eb5](https://linux-hardware.org/?probe=88ef270eb5) | Jan 03, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [019f053a89](https://linux-hardware.org/?probe=019f053a89) | Jan 02, 2021 |
| HP            | Notebook                    | [cf3a2917d1](https://linux-hardware.org/?probe=cf3a2917d1) | Dec 28, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [0a8ed33e62](https://linux-hardware.org/?probe=0a8ed33e62) | Dec 26, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [9a02f6b2cf](https://linux-hardware.org/?probe=9a02f6b2cf) | Dec 22, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [680d4771b2](https://linux-hardware.org/?probe=680d4771b2) | Dec 15, 2020 |
| Acer          | Aspire 5738                 | [ad2cafcbe8](https://linux-hardware.org/?probe=ad2cafcbe8) | Dec 13, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [43e55c9de6](https://linux-hardware.org/?probe=43e55c9de6) | Dec 13, 2020 |
| HP            | EliteBook 840r G4           | [ebc64db4ca](https://linux-hardware.org/?probe=ebc64db4ca) | Dec 12, 2020 |
| Acer          | Aspire 5738                 | [f29c073cfb](https://linux-hardware.org/?probe=f29c073cfb) | Dec 11, 2020 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [5bae11079c](https://linux-hardware.org/?probe=5bae11079c) | Dec 09, 2020 |
| Toshiba       | Satellite C645              | [0e17d5e680](https://linux-hardware.org/?probe=0e17d5e680) | Dec 09, 2020 |
| Toshiba       | Satellite C645              | [0fcca906f6](https://linux-hardware.org/?probe=0fcca906f6) | Dec 09, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [d9258de65c](https://linux-hardware.org/?probe=d9258de65c) | Dec 09, 2020 |
| Apple         | MacBookPro9,2               | [7469e3af08](https://linux-hardware.org/?probe=7469e3af08) | Dec 08, 2020 |
| HP            | ProBook 440 G7              | [01b2a334c8](https://linux-hardware.org/?probe=01b2a334c8) | Dec 04, 2020 |
| Lenovo        | IdeaPad Z400 20201          | [9f4318e1fa](https://linux-hardware.org/?probe=9f4318e1fa) | Dec 03, 2020 |
| Lenovo        | K2450 20243                 | [33409ba105](https://linux-hardware.org/?probe=33409ba105) | Dec 03, 2020 |
| Dell          | Latitude E7470              | [ff5ee269cb](https://linux-hardware.org/?probe=ff5ee269cb) | Dec 01, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [9be5961a82](https://linux-hardware.org/?probe=9be5961a82) | Nov 25, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [2ce0bde22b](https://linux-hardware.org/?probe=2ce0bde22b) | Nov 21, 2020 |
| ASUSTek       | X405UA                      | [e27b62e8d8](https://linux-hardware.org/?probe=e27b62e8d8) | Nov 19, 2020 |
| Lenovo        | K2450 20243                 | [4d44042257](https://linux-hardware.org/?probe=4d44042257) | Nov 19, 2020 |
| HP            | EliteBook 840r G4           | [4782db92e6](https://linux-hardware.org/?probe=4782db92e6) | Nov 19, 2020 |
| Lenovo        | IdeaPad S206 20154          | [393f27acf7](https://linux-hardware.org/?probe=393f27acf7) | Nov 18, 2020 |
| Lenovo        | G400 20235                  | [7cdfc8df41](https://linux-hardware.org/?probe=7cdfc8df41) | Nov 17, 2020 |
| Lenovo        | G400 20235                  | [9d19c00f4e](https://linux-hardware.org/?probe=9d19c00f4e) | Nov 17, 2020 |
| Positivo      | Mobile                      | [87704474ae](https://linux-hardware.org/?probe=87704474ae) | Nov 12, 2020 |
| HP            | 1000                        | [a79972678b](https://linux-hardware.org/?probe=a79972678b) | Nov 10, 2020 |
| Lenovo        | ThinkPad T400 6474AU5       | [1b3d0a7938](https://linux-hardware.org/?probe=1b3d0a7938) | Nov 09, 2020 |
| HP            | 420                         | [8b2ce5df27](https://linux-hardware.org/?probe=8b2ce5df27) | Nov 09, 2020 |
| Unknown       | Unknown                     | [8651ede6c2](https://linux-hardware.org/?probe=8651ede6c2) | Nov 04, 2020 |
| Dell          | XPS 13 9300                 | [764cabc447](https://linux-hardware.org/?probe=764cabc447) | Nov 03, 2020 |
| HP            | Pavilion dv4                | [80f9a1311e](https://linux-hardware.org/?probe=80f9a1311e) | Oct 30, 2020 |
| Toshiba       | Satellite C45-A             | [bbfec71882](https://linux-hardware.org/?probe=bbfec71882) | Oct 30, 2020 |
| HP            | Laptop 14-cf0xxx            | [5ae192d7e1](https://linux-hardware.org/?probe=5ae192d7e1) | Oct 26, 2020 |
| HP            | Laptop 14-cf0xxx            | [8999670eb2](https://linux-hardware.org/?probe=8999670eb2) | Oct 25, 2020 |
| Acer          | Swift SF314-42              | [628265bca0](https://linux-hardware.org/?probe=628265bca0) | Oct 25, 2020 |
| Lenovo        | IdeaPad S300 20197          | [d03e3dc110](https://linux-hardware.org/?probe=d03e3dc110) | Oct 23, 2020 |
| Dell          | Latitude E6440              | [46a2699a96](https://linux-hardware.org/?probe=46a2699a96) | Oct 21, 2020 |
| Acer          | Swift SF314-42              | [01143e194b](https://linux-hardware.org/?probe=01143e194b) | Oct 20, 2020 |
| ASUSTek       | X555LB                      | [75ba1f9ee4](https://linux-hardware.org/?probe=75ba1f9ee4) | Oct 19, 2020 |
| Acer          | Aspire E1-531               | [78a57e6fb8](https://linux-hardware.org/?probe=78a57e6fb8) | Oct 13, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [63831d979c](https://linux-hardware.org/?probe=63831d979c) | Oct 06, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [887dc701b4](https://linux-hardware.org/?probe=887dc701b4) | Oct 05, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [eed07ba536](https://linux-hardware.org/?probe=eed07ba536) | Oct 05, 2020 |
| Unknown       | Unknown                     | [afc109116d](https://linux-hardware.org/?probe=afc109116d) | Oct 01, 2020 |
| HP            | 530                         | [c330f06c15](https://linux-hardware.org/?probe=c330f06c15) | Sep 30, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [ad0d202176](https://linux-hardware.org/?probe=ad0d202176) | Sep 29, 2020 |
| HP            | Pavilion Power Laptop 15... | [6f97a1bc53](https://linux-hardware.org/?probe=6f97a1bc53) | Sep 28, 2020 |
| Lenovo        | ThinkPad T460 20FMS05G4L    | [2934114047](https://linux-hardware.org/?probe=2934114047) | Sep 28, 2020 |
| Dell          | XPS 13 9370                 | [bd632f89ef](https://linux-hardware.org/?probe=bd632f89ef) | Sep 26, 2020 |
| HP            | EliteBook 840r G4           | [2ed34e371e](https://linux-hardware.org/?probe=2ed34e371e) | Sep 26, 2020 |
| Unknown       | Unknown                     | [be59c4d6c4](https://linux-hardware.org/?probe=be59c4d6c4) | Sep 23, 2020 |
| HP            | EliteBook 840 G6            | [42e3c550cb](https://linux-hardware.org/?probe=42e3c550cb) | Sep 22, 2020 |
| ASUSTek       | X556URK                     | [1c0033b367](https://linux-hardware.org/?probe=1c0033b367) | Sep 20, 2020 |
| ASUSTek       | G55VW                       | [8bfec34af2](https://linux-hardware.org/?probe=8bfec34af2) | Sep 20, 2020 |
| HP            | 245 G5 Notebook PC          | [d2e8cd8f97](https://linux-hardware.org/?probe=d2e8cd8f97) | Sep 15, 2020 |
| HP            | 245 G5 Notebook PC          | [da0f03edfc](https://linux-hardware.org/?probe=da0f03edfc) | Sep 14, 2020 |
| Acer          | Aspire 5542                 | [da115e748b](https://linux-hardware.org/?probe=da115e748b) | Sep 14, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [1f5bd64812](https://linux-hardware.org/?probe=1f5bd64812) | Sep 09, 2020 |
| HP            | Pavilion 15                 | [df560484b4](https://linux-hardware.org/?probe=df560484b4) | Sep 09, 2020 |
| Acer          | Nitro AN515-43              | [44782a039e](https://linux-hardware.org/?probe=44782a039e) | Sep 07, 2020 |
| Lenovo        | ThinkPad A485 20MVS0N300    | [6ad17e6cf7](https://linux-hardware.org/?probe=6ad17e6cf7) | Sep 05, 2020 |
| HP            | Notebook                    | [c5d0ec5edb](https://linux-hardware.org/?probe=c5d0ec5edb) | Aug 30, 2020 |
| Acer          | Aspire E1-422               | [a239e53a11](https://linux-hardware.org/?probe=a239e53a11) | Aug 29, 2020 |
| Acer          | Aspire A315-21              | [02f9010c71](https://linux-hardware.org/?probe=02f9010c71) | Aug 26, 2020 |
| HP            | Pavilion Notebook           | [341b0f6231](https://linux-hardware.org/?probe=341b0f6231) | Aug 24, 2020 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [be74487ec4](https://linux-hardware.org/?probe=be74487ec4) | Aug 23, 2020 |
| Acer          | Aspire ES1-111M             | [fcee1a2241](https://linux-hardware.org/?probe=fcee1a2241) | Aug 21, 2020 |
| Acer          | Aspire ES1-111M             | [43f35553ae](https://linux-hardware.org/?probe=43f35553ae) | Aug 21, 2020 |
| HP            | Pavilion 15                 | [d9c1a66672](https://linux-hardware.org/?probe=d9c1a66672) | Aug 20, 2020 |
| HP            | Laptop 15-bs0xx             | [f6678c3632](https://linux-hardware.org/?probe=f6678c3632) | Aug 17, 2020 |
| Lenovo        | ThinkPad E420 1141DAS       | [ab579f2102](https://linux-hardware.org/?probe=ab579f2102) | Aug 17, 2020 |
| Lenovo        | ThinkPad E420 1141DAS       | [d4beb495bd](https://linux-hardware.org/?probe=d4beb495bd) | Aug 17, 2020 |
| ASUSTek       | FX503VD                     | [26ce95f067](https://linux-hardware.org/?probe=26ce95f067) | Aug 03, 2020 |
| HP            | Laptop 15-bs0xx             | [467112cf04](https://linux-hardware.org/?probe=467112cf04) | Jul 31, 2020 |
| HP            | ProBook 440 G3              | [9a34cb7ec7](https://linux-hardware.org/?probe=9a34cb7ec7) | Jul 28, 2020 |
| Acer          | Aspire ES1-572              | [1db75aee39](https://linux-hardware.org/?probe=1db75aee39) | Jul 27, 2020 |
| Acer          | Aspire R3-431T              | [b3bc6f8d90](https://linux-hardware.org/?probe=b3bc6f8d90) | Jul 24, 2020 |
| HP            | Pavilion 15                 | [7410d46ef8](https://linux-hardware.org/?probe=7410d46ef8) | Jul 24, 2020 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [dbb48c14f0](https://linux-hardware.org/?probe=dbb48c14f0) | Jul 22, 2020 |
| HP            | Notebook                    | [431d1d1482](https://linux-hardware.org/?probe=431d1d1482) | Jul 22, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [3216dbc594](https://linux-hardware.org/?probe=3216dbc594) | Jul 18, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [f8c9b50bc3](https://linux-hardware.org/?probe=f8c9b50bc3) | Jul 18, 2020 |
| Sony          | VGN-FW360TJ                 | [8b037cac91](https://linux-hardware.org/?probe=8b037cac91) | Jul 18, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [f77f8a2639](https://linux-hardware.org/?probe=f77f8a2639) | Jul 15, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [4afe4f5961](https://linux-hardware.org/?probe=4afe4f5961) | Jul 15, 2020 |
| Apple         | MacBookAir7,2               | [f53c9923c4](https://linux-hardware.org/?probe=f53c9923c4) | Jul 11, 2020 |
| HP            | Presario CQ43               | [48fe8649ca](https://linux-hardware.org/?probe=48fe8649ca) | Jul 08, 2020 |
| HP            | Presario CQ43               | [db6a9d6546](https://linux-hardware.org/?probe=db6a9d6546) | Jul 06, 2020 |
| HP            | ProBook 4440s               | [48a7e1a88c](https://linux-hardware.org/?probe=48a7e1a88c) | Jul 05, 2020 |
| Dell          | Inspiron N5110              | [bd30f237dd](https://linux-hardware.org/?probe=bd30f237dd) | Jul 05, 2020 |
| Acer          | Aspire ES1-331              | [b154bdb93b](https://linux-hardware.org/?probe=b154bdb93b) | Jul 02, 2020 |
| HP            | ProBook 640 G1              | [1a2462dee7](https://linux-hardware.org/?probe=1a2462dee7) | Jul 01, 2020 |
| Toshiba       | PORTEGE R30-A               | [d33d8295b1](https://linux-hardware.org/?probe=d33d8295b1) | Jun 29, 2020 |
| Corporativ... | LX4SI                       | [3a15f8865d](https://linux-hardware.org/?probe=3a15f8865d) | Jun 26, 2020 |
| ASUSTek       | X450LN                      | [347ebd88a5](https://linux-hardware.org/?probe=347ebd88a5) | Jun 25, 2020 |
| ASUSTek       | X450LN                      | [10dd68f147](https://linux-hardware.org/?probe=10dd68f147) | Jun 25, 2020 |
| Corporativ... | LX4SI                       | [f9e67e8a5f](https://linux-hardware.org/?probe=f9e67e8a5f) | Jun 25, 2020 |
| HP            | 240 G6 Notebook PC          | [c43e5357b0](https://linux-hardware.org/?probe=c43e5357b0) | Jun 24, 2020 |
| Packard Be... | DOT S                       | [d2cd9b2728](https://linux-hardware.org/?probe=d2cd9b2728) | Jun 24, 2020 |
| Lenovo        | IdeaPad 500-14ISK 80NS      | [1af5a3043b](https://linux-hardware.org/?probe=1af5a3043b) | Jun 23, 2020 |
| HP            | ProBook 430 G2              | [d988a74820](https://linux-hardware.org/?probe=d988a74820) | Jun 23, 2020 |
| Lenovo        | IdeaPad 720S-14IKB 80XC     | [0fbefbc62c](https://linux-hardware.org/?probe=0fbefbc62c) | Jun 21, 2020 |
| Lenovo        | IdeaPad 720S-14IKB 80XC     | [a281f8c305](https://linux-hardware.org/?probe=a281f8c305) | Jun 19, 2020 |
| HP            | 245 G4 Notebook PC          | [4f96cc852f](https://linux-hardware.org/?probe=4f96cc852f) | Jun 18, 2020 |
| HP            | 245 G4 Notebook PC          | [2c0356727d](https://linux-hardware.org/?probe=2c0356727d) | Jun 18, 2020 |
| Dell          | Inspiron 3420               | [5101d0c83c](https://linux-hardware.org/?probe=5101d0c83c) | Jun 17, 2020 |
| Dell          | Inspiron 14-3452            | [c83e4c2dd8](https://linux-hardware.org/?probe=c83e4c2dd8) | Jun 15, 2020 |
| Lenovo        | IdeaPad Z470                | [7167c9a1eb](https://linux-hardware.org/?probe=7167c9a1eb) | Jun 10, 2020 |
| Packard Be... | ENNS11HR                    | [952d5d4772](https://linux-hardware.org/?probe=952d5d4772) | Jun 05, 2020 |
| HP            | ProBook 4440s               | [730e093bc4](https://linux-hardware.org/?probe=730e093bc4) | Jun 05, 2020 |
| Acer          | Aspire V5-132               | [44a89c002a](https://linux-hardware.org/?probe=44a89c002a) | Jun 02, 2020 |
| Acer          | Aspire V5-132               | [5b82f8d7d3](https://linux-hardware.org/?probe=5b82f8d7d3) | Jun 02, 2020 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [fbccea1bb2](https://linux-hardware.org/?probe=fbccea1bb2) | May 29, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X420... | [9a867c7a5b](https://linux-hardware.org/?probe=9a867c7a5b) | May 28, 2020 |
| Dell          | Latitude E7450              | [c3eab25bca](https://linux-hardware.org/?probe=c3eab25bca) | May 28, 2020 |
| Clevo         | W240HU/W250HUQ              | [9fac55b56b](https://linux-hardware.org/?probe=9fac55b56b) | May 28, 2020 |
| Clevo         | W240HU/W250HUQ              | [9403cfc9c4](https://linux-hardware.org/?probe=9403cfc9c4) | May 27, 2020 |
| Clevo         | W240HU/W250HUQ              | [216a9db389](https://linux-hardware.org/?probe=216a9db389) | May 27, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [38e63a05e2](https://linux-hardware.org/?probe=38e63a05e2) | May 26, 2020 |
| Dell          | Inspiron 14-3452            | [f894499ac3](https://linux-hardware.org/?probe=f894499ac3) | May 26, 2020 |
| HP            | OMEN by Laptop              | [6cea5aa3fd](https://linux-hardware.org/?probe=6cea5aa3fd) | May 26, 2020 |
| HP            | OMEN by Laptop              | [a621749c2d](https://linux-hardware.org/?probe=a621749c2d) | May 26, 2020 |
| Acer          | ES1-111M                    | [53e45e403c](https://linux-hardware.org/?probe=53e45e403c) | May 23, 2020 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [fae71925c5](https://linux-hardware.org/?probe=fae71925c5) | May 21, 2020 |
| Acer          | Aspire 4739Z                | [f51ee0fe5a](https://linux-hardware.org/?probe=f51ee0fe5a) | May 20, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [910d27523a](https://linux-hardware.org/?probe=910d27523a) | May 20, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [ffe1142072](https://linux-hardware.org/?probe=ffe1142072) | May 19, 2020 |
| Acer          | Aspire A114-32              | [35ddb37c29](https://linux-hardware.org/?probe=35ddb37c29) | May 17, 2020 |
| Acer          | Aspire E5-551G              | [cda77789ec](https://linux-hardware.org/?probe=cda77789ec) | May 17, 2020 |
| Acer          | Aspire E5-551G              | [ee3ddbe726](https://linux-hardware.org/?probe=ee3ddbe726) | May 17, 2020 |
| Dell          | Latitude E6420              | [46a7b9904a](https://linux-hardware.org/?probe=46a7b9904a) | May 17, 2020 |
| Dell          | Latitude E6420              | [15d9716666](https://linux-hardware.org/?probe=15d9716666) | May 17, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [55850d2bd2](https://linux-hardware.org/?probe=55850d2bd2) | May 17, 2020 |
| Dell          | Inspiron 14-3452            | [65292593ee](https://linux-hardware.org/?probe=65292593ee) | May 15, 2020 |
| Lenovo        | ThinkPad T495s 20QKA008C... | [fd09b801b7](https://linux-hardware.org/?probe=fd09b801b7) | May 14, 2020 |
| HP            | Pavilion Notebook           | [825d07d907](https://linux-hardware.org/?probe=825d07d907) | May 14, 2020 |
| Dell          | Precision 7520              | [bf1d29844b](https://linux-hardware.org/?probe=bf1d29844b) | May 13, 2020 |
| Dell          | Inspiron 1420               | [917741e728](https://linux-hardware.org/?probe=917741e728) | May 13, 2020 |
| Lenovo        | ThinkPad T495s 20QKA008C... | [8006d3f65a](https://linux-hardware.org/?probe=8006d3f65a) | May 12, 2020 |
| Lenovo        | ThinkPad T495s 20QKA008C... | [9767ed89e1](https://linux-hardware.org/?probe=9767ed89e1) | May 12, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [f15c21aabd](https://linux-hardware.org/?probe=f15c21aabd) | May 11, 2020 |
| Toshiba       | NB505                       | [26eaa80c8a](https://linux-hardware.org/?probe=26eaa80c8a) | May 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [ebf32d4cbf](https://linux-hardware.org/?probe=ebf32d4cbf) | May 08, 2020 |
| ASUSTek       | K50AB                       | [ac598fedba](https://linux-hardware.org/?probe=ac598fedba) | May 06, 2020 |
| ASUSTek       | K50AB                       | [9e3de662ae](https://linux-hardware.org/?probe=9e3de662ae) | May 06, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [3abae5c4a3](https://linux-hardware.org/?probe=3abae5c4a3) | May 05, 2020 |
| HP            | Pavilion Notebook           | [b995e0664a](https://linux-hardware.org/?probe=b995e0664a) | May 03, 2020 |
| HP            | ElitePad 1000 G2            | [40df66d7b8](https://linux-hardware.org/?probe=40df66d7b8) | Apr 29, 2020 |
| Acer          | Aspire E1-531               | [c814274f99](https://linux-hardware.org/?probe=c814274f99) | Apr 27, 2020 |
| HP            | 240 G6 Notebook PC          | [542ddefbc5](https://linux-hardware.org/?probe=542ddefbc5) | Apr 25, 2020 |
| Samsung       | RV410/RV510/S3510/E3510     | [3fd8a137d5](https://linux-hardware.org/?probe=3fd8a137d5) | Apr 21, 2020 |
| HP            | 240 G6 Notebook PC          | [e96b3b2ace](https://linux-hardware.org/?probe=e96b3b2ace) | Apr 21, 2020 |
| HP            | 240 G6 Notebook PC          | [5058e946ea](https://linux-hardware.org/?probe=5058e946ea) | Apr 21, 2020 |
| Acer          | Aspire E1-531               | [a7e6d42571](https://linux-hardware.org/?probe=a7e6d42571) | Apr 21, 2020 |
| Acer          | Aspire E1-531               | [384b1e8269](https://linux-hardware.org/?probe=384b1e8269) | Apr 20, 2020 |
| HP            | EliteBook 840 G6            | [57feb728c2](https://linux-hardware.org/?probe=57feb728c2) | Apr 19, 2020 |
| Toshiba       | NB505                       | [174dd8b4cd](https://linux-hardware.org/?probe=174dd8b4cd) | Apr 16, 2020 |
| HP            | ENVY 15                     | [d38936efb2](https://linux-hardware.org/?probe=d38936efb2) | Apr 16, 2020 |
| Toshiba       | NB505                       | [a28c9ef432](https://linux-hardware.org/?probe=a28c9ef432) | Apr 12, 2020 |
| HP            | Pavilion g4                 | [ee7f720be3](https://linux-hardware.org/?probe=ee7f720be3) | Apr 12, 2020 |
| HP            | Pavilion Sleekbook 15       | [309b26e9a7](https://linux-hardware.org/?probe=309b26e9a7) | Apr 12, 2020 |
| HP            | Pavilion Sleekbook 15       | [ca7cea286a](https://linux-hardware.org/?probe=ca7cea286a) | Apr 12, 2020 |
| Toshiba       | PORTEGE Z20t-C              | [9411f4e22a](https://linux-hardware.org/?probe=9411f4e22a) | Apr 09, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Chile/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 76        | 9.39%   |
| Ubuntu 18.04                 | 51        | 6.3%    |
| Ubuntu 22.04                 | 46        | 5.69%   |
| Fedora 38                    | 27        | 3.34%   |
| Arch Rolling                 | 21        | 2.6%    |
| Fedora 39                    | 16        | 1.98%   |
| Debian 12                    | 16        | 1.98%   |
| Pop!_OS 22.04                | 15        | 1.85%   |
| OpenMandriva 4.3             | 15        | 1.85%   |
| Manjaro                      | 15        | 1.85%   |
| Debian 10                    | 15        | 1.85%   |
| Ubuntu 19.04                 | 14        | 1.73%   |
| OpenMandriva 4.2             | 14        | 1.73%   |
| Debian 11                    | 14        | 1.73%   |
| Zorin 16                     | 13        | 1.61%   |
| Fedora 37                    | 13        | 1.61%   |
| KDE neon 22.04               | 12        | 1.48%   |
| Arch                         | 11        | 1.36%   |
| KDE neon 20.04               | 10        | 1.24%   |
| Fedora 35                    | 10        | 1.24%   |
| Ubuntu 22.10                 | 9         | 1.11%   |
| Pop!_OS 20.04                | 9         | 1.11%   |
| openSUSE Tumbleweed-XXXXXXXX | 9         | 1.11%   |
| Linux Mint 21.1              | 9         | 1.11%   |
| Linux Mint 20.1              | 9         | 1.11%   |
| Fedora 36                    | 9         | 1.11%   |
| Fedora 34                    | 9         | 1.11%   |
| Zorin 15                     | 8         | 0.99%   |
| Ubuntu 23.04                 | 8         | 0.99%   |
| Ubuntu 21.10                 | 8         | 0.99%   |
| Ubuntu 20.10                 | 8         | 0.99%   |
| Ubuntu 19.10                 | 8         | 0.99%   |
| OpenMandriva 23.08           | 8         | 0.99%   |
| Linux Mint 21                | 8         | 0.99%   |
| Elementary 6.1               | 8         | 0.99%   |
| ArcoLinux Rolling            | 8         | 0.99%   |
| OpenMandriva 23.01           | 7         | 0.87%   |
| ROSA R10                     | 6         | 0.74%   |
| Fedora 33                    | 6         | 0.74%   |
| Fedora 32                    | 6         | 0.74%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 234       | 30.35%  |
| Fedora        | 90        | 11.67%  |
| Linux Mint    | 53        | 6.87%   |
| Debian        | 50        | 6.49%   |
| OpenMandriva  | 46        | 5.97%   |
| Arch          | 32        | 4.15%   |
| Pop!_OS       | 31        | 4.02%   |
| KDE neon      | 25        | 3.24%   |
| Zorin         | 23        | 2.98%   |
| Manjaro       | 21        | 2.72%   |
| ROSA          | 14        | 1.82%   |
| Elementary    | 13        | 1.69%   |
| Xubuntu       | 12        | 1.56%   |
| Kubuntu       | 12        | 1.56%   |
| openSUSE      | 11        | 1.43%   |
| Lubuntu       | 8         | 1.04%   |
| ArcoLinux     | 8         | 1.04%   |
| Ubuntu MATE   | 7         | 0.91%   |
| SteamOS       | 7         | 0.91%   |
| Endless       | 6         | 0.78%   |
| LMDE          | 5         | 0.65%   |
| Xero          | 4         | 0.52%   |
| Ubuntu Budgie | 4         | 0.52%   |
| Nobara        | 4         | 0.52%   |
| Loc OS        | 4         | 0.52%   |
| Kali          | 4         | 0.52%   |
| Solus         | 3         | 0.39%   |
| RHEL          | 3         | 0.39%   |
| Gentoo        | 3         | 0.39%   |
| EndeavourOS   | 3         | 0.39%   |
| Deepin        | 3         | 0.39%   |
| Clear Linux   | 3         | 0.39%   |
| Ultramarine   | 2         | 0.26%   |
| Ubuntu Unity  | 2         | 0.26%   |
| Slackware     | 2         | 0.26%   |
| Parrot        | 2         | 0.26%   |
| MX            | 2         | 0.26%   |
| CentOS        | 2         | 0.26%   |
| Sparky        | 1         | 0.13%   |
| Reborn OS     | 1         | 0.13%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 15        | 1.7%    |
| 5.10.14-desktop-1omv4002 | 13        | 1.48%   |
| 5.4.0-58-generic         | 8         | 0.91%   |
| 5.15.0-56-generic        | 8         | 0.91%   |
| 6.1.1-desktop-1omv2290   | 6         | 0.68%   |
| 5.8.0-48-generic         | 6         | 0.68%   |
| 5.4.0-56-generic         | 6         | 0.68%   |
| 5.4.0-48-generic         | 6         | 0.68%   |
| 5.4.0-42-generic         | 6         | 0.68%   |
| 5.4.0-26-generic         | 6         | 0.68%   |
| 5.15.0-48-generic        | 6         | 0.68%   |
| 5.11.0-37-generic        | 6         | 0.68%   |
| 6.4.11-desktop-1omv2390  | 5         | 0.57%   |
| 6.2.0-39-generic         | 5         | 0.57%   |
| 5.8.0-50-generic         | 5         | 0.57%   |
| 5.3.0-46-generic         | 5         | 0.57%   |
| 5.19.0-38-generic        | 5         | 0.57%   |
| 5.19.0-35-generic        | 5         | 0.57%   |
| 5.15.0-60-generic        | 5         | 0.57%   |
| 5.15.0-52-generic        | 5         | 0.57%   |
| 5.15.0-41-generic        | 5         | 0.57%   |
| 5.11.0-27-generic        | 5         | 0.57%   |
| 5.0.0-23-generic         | 5         | 0.57%   |
| 4.18.0-15-generic        | 5         | 0.57%   |
| 6.5.0-27-generic         | 4         | 0.45%   |
| 6.5.0-26-generic         | 4         | 0.45%   |
| 6.5.0-25-generic         | 4         | 0.45%   |
| 6.2.6-76060206-generic   | 4         | 0.45%   |
| 6.2.0-36-generic         | 4         | 0.45%   |
| 6.2.0-20-generic         | 4         | 0.45%   |
| 6.1.0-18-amd64           | 4         | 0.45%   |
| 6.1.0-11-amd64           | 4         | 0.45%   |
| 5.4.0-72-generic         | 4         | 0.45%   |
| 5.4.0-47-generic         | 4         | 0.45%   |
| 5.4.0-37-generic         | 4         | 0.45%   |
| 5.3.0-42-generic         | 4         | 0.45%   |
| 5.19.0-41-generic        | 4         | 0.45%   |
| 5.15.0-46-generic        | 4         | 0.45%   |
| 5.15.0-43-generic        | 4         | 0.45%   |
| 5.13.0-30-generic        | 4         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 104       | 12.41%  |
| 5.15.0  | 66        | 7.88%   |
| 5.8.0   | 34        | 4.06%   |
| 5.11.0  | 33        | 3.94%   |
| 5.0.0   | 33        | 3.94%   |
| 5.19.0  | 29        | 3.46%   |
| 6.2.0   | 27        | 3.22%   |
| 5.3.0   | 26        | 3.1%    |
| 4.15.0  | 25        | 2.98%   |
| 5.13.0  | 23        | 2.74%   |
| 6.5.0   | 22        | 2.63%   |
| 5.10.0  | 19        | 2.27%   |
| 4.18.0  | 18        | 2.15%   |
| 6.1.0   | 15        | 1.79%   |
| 5.16.7  | 15        | 1.79%   |
| 5.10.14 | 13        | 1.55%   |
| 4.19.0  | 12        | 1.43%   |
| 5.14.0  | 10        | 1.19%   |
| 6.1.1   | 8         | 0.95%   |
| 6.4.11  | 6         | 0.72%   |
| 6.2.6   | 6         | 0.72%   |
| 6.0.0   | 6         | 0.72%   |
| 6.4.8   | 5         | 0.6%    |
| 4.9.60  | 5         | 0.6%    |
| 6.8.7   | 3         | 0.36%   |
| 6.8.5   | 3         | 0.36%   |
| 6.8.4   | 3         | 0.36%   |
| 6.7.4   | 3         | 0.36%   |
| 6.7.3   | 3         | 0.36%   |
| 6.7.0   | 3         | 0.36%   |
| 6.6.8   | 3         | 0.36%   |
| 6.5.9   | 3         | 0.36%   |
| 6.5.6   | 3         | 0.36%   |
| 6.5.5   | 3         | 0.36%   |
| 6.3.8   | 3         | 0.36%   |
| 6.3.6   | 3         | 0.36%   |
| 6.3.12  | 3         | 0.36%   |
| 6.2.9   | 3         | 0.36%   |
| 6.2.15  | 3         | 0.36%   |
| 6.2.14  | 3         | 0.36%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 109       | 13.12%  |
| 5.15    | 72        | 8.66%   |
| 5.10    | 50        | 6.02%   |
| 6.2     | 48        | 5.78%   |
| 6.1     | 46        | 5.54%   |
| 5.11    | 44        | 5.29%   |
| 5.19    | 42        | 5.05%   |
| 5.8     | 37        | 4.45%   |
| 5.0     | 36        | 4.33%   |
| 6.5     | 33        | 3.97%   |
| 5.13    | 29        | 3.49%   |
| 5.3     | 27        | 3.25%   |
| 4.15    | 25        | 3.01%   |
| 5.16    | 24        | 2.89%   |
| 6.4     | 22        | 2.65%   |
| 4.18    | 19        | 2.29%   |
| 6.7     | 17        | 2.05%   |
| 6.0     | 17        | 2.05%   |
| 6.3     | 16        | 1.93%   |
| 5.17    | 15        | 1.81%   |
| 6.6     | 14        | 1.68%   |
| 6.8     | 13        | 1.56%   |
| 5.14    | 13        | 1.56%   |
| 4.19    | 13        | 1.56%   |
| 5.12    | 9         | 1.08%   |
| 4.9     | 9         | 1.08%   |
| 5.9     | 7         | 0.84%   |
| 5.18    | 6         | 0.72%   |
| 5.5     | 5         | 0.6%    |
| 5.6     | 4         | 0.48%   |
| 4.4     | 4         | 0.48%   |
| 5.1     | 3         | 0.36%   |
| 4.13    | 1         | 0.12%   |
| 3.10    | 1         | 0.12%   |
| Unknown | 1         | 0.12%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 724       | 97.44%  |
| i686    | 18        | 2.42%   |
| Unknown | 1         | 0.13%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 350       | 45.22%  |
| KDE5             | 139       | 17.96%  |
| Unknown          | 75        | 9.69%   |
| XFCE             | 52        | 6.72%   |
| X-Cinnamon       | 41        | 5.3%    |
| MATE             | 16        | 2.07%   |
| KDE              | 16        | 2.07%   |
| Pantheon         | 14        | 1.81%   |
| KDE4             | 10        | 1.29%   |
| LXQt             | 8         | 1.03%   |
| i3               | 8         | 1.03%   |
| Budgie           | 8         | 1.03%   |
| LXDE             | 7         | 0.9%    |
| KDE6             | 6         | 0.78%   |
| Cinnamon         | 6         | 0.78%   |
| Deepin           | 4         | 0.52%   |
| GNOME Flashback  | 3         | 0.39%   |
| awesome          | 3         | 0.39%   |
| Unity            | 2         | 0.26%   |
| qtile            | 2         | 0.26%   |
| Trinity          | 1         | 0.13%   |
| lightdm-xsession | 1         | 0.13%   |
| icewm            | 1         | 0.13%   |
| bspwm            | 1         | 0.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 538       | 69.87%  |
| Wayland | 187       | 24.29%  |
| Unknown | 38        | 4.94%   |
| Tty     | 7         | 0.91%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 419       | 54.2%   |
| SDDM    | 103       | 13.32%  |
| GDM3    | 82        | 10.61%  |
| GDM     | 81        | 10.48%  |
| LightDM | 55        | 7.12%   |
| TDM     | 18        | 2.33%   |
| KDM     | 9         | 1.16%   |
| XDM     | 3         | 0.39%   |
| SLIMSKI | 1         | 0.13%   |
| Ly      | 1         | 0.13%   |
| LXDM    | 1         | 0.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| es_CL      | 406       | 53.35%  |
| en_US      | 161       | 21.16%  |
| Unknown    | 75        | 9.86%   |
| es_ES      | 52        | 6.83%   |
| es_MX      | 24        | 3.15%   |
| en_GB      | 11        | 1.45%   |
| C          | 11        | 1.45%   |
| es_AR      | 7         | 0.92%   |
| fr_FR      | 2         | 0.26%   |
| es_BO      | 2         | 0.26%   |
| en_CA      | 2         | 0.26%   |
| de_DE      | 2         | 0.26%   |
| ru_RU      | 1         | 0.13%   |
| es_VE      | 1         | 0.13%   |
| es_CO      | 1         | 0.13%   |
| es_CL.UTF8 | 1         | 0.13%   |
| en_AG      | 1         | 0.13%   |
| arn_CL     | 1         | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 413       | 54.85%  |
| BIOS | 340       | 45.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 550       | 71.52%  |
| Btrfs   | 111       | 14.43%  |
| Overlay | 37        | 4.81%   |
| Unknown | 33        | 4.29%   |
| Tmpfs   | 28        | 3.64%   |
| Xfs     | 9         | 1.17%   |
| Zfs     | 1         | 0.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 435       | 56.64%  |
| GPT     | 283       | 36.85%  |
| MBR     | 50        | 6.51%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 691       | 91.04%  |
| Yes       | 68        | 8.96%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 577       | 75.72%  |
| Yes       | 185       | 24.28%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Hewlett-Packard           | 204       | 27.49%  |
| Lenovo                    | 144       | 19.41%  |
| ASUSTek Computer          | 92        | 12.4%   |
| Dell                      | 77        | 10.38%  |
| Acer                      | 71        | 9.57%   |
| Samsung Electronics       | 30        | 4.04%   |
| Toshiba                   | 21        | 2.83%   |
| Sony                      | 16        | 2.16%   |
| Apple                     | 12        | 1.62%   |
| HUAWEI                    | 11        | 1.48%   |
| Unknown                   | 9         | 1.21%   |
| Packard Bell              | 8         | 1.08%   |
| Valve                     | 7         | 0.94%   |
| MSI                       | 6         | 0.81%   |
| SK hynix                  | 4         | 0.54%   |
| Google                    | 4         | 0.54%   |
| HONOR                     | 2         | 0.27%   |
| Chuwi                     | 2         | 0.27%   |
| AMI                       | 2         | 0.27%   |
| Alienware                 | 2         | 0.27%   |
| Wings Mobile              | 1         | 0.13%   |
| TAGTech                   | 1         | 0.13%   |
| Render                    | 1         | 0.13%   |
| Positivo                  | 1         | 0.13%   |
| Personal Computer Factory | 1         | 0.13%   |
| OX                        | 1         | 0.13%   |
| OEM                       | 1         | 0.13%   |
| MOTILE                    | 1         | 0.13%   |
| Medion                    | 1         | 0.13%   |
| LG Electronics            | 1         | 0.13%   |
| Intel                     | 1         | 0.13%   |
| Insyde                    | 1         | 0.13%   |
| Gear                      | 1         | 0.13%   |
| Elife                     | 1         | 0.13%   |
| Creative Vision           | 1         | 0.13%   |
| Corporativo Lanix         | 1         | 0.13%   |
| Clevo                     | 1         | 0.13%   |
| A-DATA Technology         | 1         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                           | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Unknown                                        | 13        | 1.75%   |
| HP Notebook                                    | 12        | 1.62%   |
| HP 240 G6 Notebook PC                          | 11        | 1.48%   |
| HP ENVY 15                                     | 8         | 1.08%   |
| Valve Jupiter                                  | 7         | 0.94%   |
| HP Pavilion Notebook                           | 7         | 0.94%   |
| HP Pavilion g4                                 | 6         | 0.81%   |
| HP Pavilion Laptop 15-eh0xxx                   | 5         | 0.67%   |
| HP Pavilion Laptop 15-cw1xxx                   | 5         | 0.67%   |
| HP Pavilion 15                                 | 5         | 0.67%   |
| ASUS ZenBook UX325EA_UX325EA                   | 5         | 0.67%   |
| Lenovo Legion Y530-15ICH 81FV                  | 4         | 0.54%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK          | 4         | 0.54%   |
| HUAWEI BOHK-WAX9X                              | 4         | 0.54%   |
| HP Pavilion Gaming Laptop 15-ec1xxx            | 4         | 0.54%   |
| HP 250 G6 Notebook PC                          | 4         | 0.54%   |
| HP 14                                          | 4         | 0.54%   |
| HP 1000                                        | 4         | 0.54%   |
| Dell Inspiron 3501                             | 4         | 0.54%   |
| Acer Aspire ES1-111M                           | 4         | 0.54%   |
| SK hynix HyBook                                | 3         | 0.4%    |
| Samsung RF511/RF411/RF711                      | 3         | 0.4%    |
| Samsung 750XED                                 | 3         | 0.4%    |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV | 3         | 0.4%    |
| Lenovo Y520-15IKBN 80WK                        | 3         | 0.4%    |
| Lenovo IdeaPad S540-15IWL 81NE                 | 3         | 0.4%    |
| Lenovo IdeaPad 330S-15ARR 81FB                 | 3         | 0.4%    |
| HP ProBook 440 G3                              | 3         | 0.4%    |
| HP Pavilion Laptop 15-cw0xxx                   | 3         | 0.4%    |
| HP Pavilion Gaming Laptop 15-dk0xxx            | 3         | 0.4%    |
| HP Pavilion dv4                                | 3         | 0.4%    |
| HP EliteBook 840 G6                            | 3         | 0.4%    |
| HP EliteBook 2560p                             | 3         | 0.4%    |
| HP 15                                          | 3         | 0.4%    |
| Google Treeya                                  | 3         | 0.4%    |
| Dell Latitude E6420                            | 3         | 0.4%    |
| Dell Inspiron 14-3467                          | 3         | 0.4%    |
| ASUS ZenBook UX433FN_UX433FN                   | 3         | 0.4%    |
| ASUS X555LB                                    | 3         | 0.4%    |
| ASUS VivoBook_ASUSLaptop X1605VA_X1605VA       | 3         | 0.4%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 65        | 8.76%   |
| HP Pavilion           | 57        | 7.68%   |
| Acer Aspire           | 53        | 7.14%   |
| Lenovo IdeaPad        | 48        | 6.47%   |
| Dell Inspiron         | 32        | 4.31%   |
| ASUS VivoBook         | 27        | 3.64%   |
| Dell Latitude         | 25        | 3.37%   |
| HP EliteBook          | 20        | 2.7%    |
| HP 240                | 18        | 2.43%   |
| HP ProBook            | 16        | 2.16%   |
| HP Laptop             | 16        | 2.16%   |
| HP ENVY               | 16        | 2.16%   |
| Toshiba Satellite     | 15        | 2.02%   |
| ASUS ZenBook          | 13        | 1.75%   |
| Unknown               | 13        | 1.75%   |
| HP Notebook           | 12        | 1.62%   |
| ASUS ASUS             | 9         | 1.21%   |
| Acer Swift            | 8         | 1.08%   |
| Valve Jupiter         | 7         | 0.94%   |
| Lenovo Legion         | 7         | 0.94%   |
| HP 250                | 7         | 0.94%   |
| HP 245                | 7         | 0.94%   |
| ASUS TUF              | 7         | 0.94%   |
| Packard Bell EasyNote | 6         | 0.81%   |
| Dell Vostro           | 5         | 0.67%   |
| Toshiba PORTEGE       | 4         | 0.54%   |
| SK hynix HyBook       | 4         | 0.54%   |
| Samsung 300E5EV       | 4         | 0.54%   |
| HUAWEI BOHK-WAX9X     | 4         | 0.54%   |
| HP Presario           | 4         | 0.54%   |
| HP Compaq             | 4         | 0.54%   |
| HP 14                 | 4         | 0.54%   |
| HP 1000               | 4         | 0.54%   |
| Dell XPS              | 4         | 0.54%   |
| Dell System           | 4         | 0.54%   |
| Dell Precision        | 4         | 0.54%   |
| ASUS ROG              | 4         | 0.54%   |
| Apple MacBookPro11    | 4         | 0.54%   |
| Acer Nitro            | 4         | 0.54%   |
| Samsung RF511         | 3         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 79        | 10.65%  |
| 2017 | 79        | 10.65%  |
| 2019 | 72        | 9.7%    |
| 2021 | 60        | 8.09%   |
| 2018 | 58        | 7.82%   |
| 2011 | 55        | 7.41%   |
| 2013 | 53        | 7.14%   |
| 2016 | 45        | 6.06%   |
| 2012 | 42        | 5.66%   |
| 2015 | 41        | 5.53%   |
| 2014 | 37        | 4.99%   |
| 2010 | 36        | 4.85%   |
| 2008 | 19        | 2.56%   |
| 2022 | 18        | 2.43%   |
| 2009 | 18        | 2.43%   |
| 2007 | 18        | 2.43%   |
| 2023 | 10        | 1.35%   |
| 2006 | 2         | 0.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 742       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 666       | 88.8%   |
| Enabled  | 84        | 11.2%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 738       | 99.46%  |
| Yes  | 4         | 0.54%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 245       | 32.45%  |
| 3.01-4.0    | 164       | 21.72%  |
| 8.01-16.0   | 148       | 19.6%   |
| 16.01-24.0  | 107       | 14.17%  |
| 1.01-2.0    | 32        | 4.24%   |
| 32.01-64.0  | 28        | 3.71%   |
| 2.01-3.0    | 13        | 1.72%   |
| 24.01-32.0  | 10        | 1.32%   |
| 64.01-256.0 | 5         | 0.66%   |
| 0.51-1.0    | 2         | 0.26%   |
| Unknown     | 1         | 0.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 254       | 30.9%   |
| 2.01-3.0   | 206       | 25.06%  |
| 3.01-4.0   | 152       | 18.49%  |
| 4.01-8.0   | 137       | 16.67%  |
| 0.51-1.0   | 45        | 5.47%   |
| 8.01-16.0  | 22        | 2.68%   |
| 0.01-0.5   | 3         | 0.36%   |
| 24.01-32.0 | 1         | 0.12%   |
| 16.01-24.0 | 1         | 0.12%   |
| Unknown    | 1         | 0.12%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 571       | 75.43%  |
| 2      | 165       | 21.8%   |
| 3      | 15        | 1.98%   |
| 0      | 4         | 0.53%   |
| 4      | 2         | 0.26%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 550       | 73.24%  |
| Yes       | 201       | 26.76%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 603       | 81.16%  |
| No        | 140       | 18.84%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 733       | 98.65%  |
| No        | 10        | 1.35%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 605       | 80.77%  |
| No        | 144       | 19.23%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Chile   | 742       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Santiago            | 281       | 35.66%  |
| Viña del Mar       | 41        | 5.2%    |
| Concepción         | 39        | 4.95%   |
| Puente Alto         | 23        | 2.92%   |
| Maipu               | 23        | 2.92%   |
| Las Condes          | 21        | 2.66%   |
| Temuco              | 20        | 2.54%   |
| Valdivia            | 16        | 2.03%   |
| La Florida          | 16        | 2.03%   |
| Providencia         | 14        | 1.78%   |
| Nunoa               | 14        | 1.78%   |
| San Miguel          | 12        | 1.52%   |
| La Serena           | 12        | 1.52%   |
| Iquique             | 10        | 1.27%   |
| Port Montt          | 9         | 1.14%   |
| Coronel             | 9         | 1.14%   |
| Antofagasta         | 9         | 1.14%   |
| Valparaíso         | 8         | 1.02%   |
| Quilpué            | 8         | 1.02%   |
| Talcahuano          | 7         | 0.89%   |
| Rancagua            | 7         | 0.89%   |
| Los Ángeles        | 6         | 0.76%   |
| Curicó             | 6         | 0.76%   |
| Coquimbo            | 6         | 0.76%   |
| Talca               | 5         | 0.63%   |
| San Pedro de la Paz | 5         | 0.63%   |
| San Bernardo        | 5         | 0.63%   |
| Punta Arenas        | 5         | 0.63%   |
| Melipilla           | 5         | 0.63%   |
| La Reina            | 5         | 0.63%   |
| Villa Alemana       | 4         | 0.51%   |
| Quillota            | 4         | 0.51%   |
| Osorno              | 4         | 0.51%   |
| Macul               | 4         | 0.51%   |
| Independencia       | 4         | 0.51%   |
| Hualpen             | 4         | 0.51%   |
| Copiapó            | 4         | 0.51%   |
| Quilicura           | 3         | 0.38%   |
| Penalolen           | 3         | 0.38%   |
| Padre Las Casas     | 3         | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 146       | 193    | 16.11%  |
| Seagate                     | 93        | 120    | 10.26%  |
| Samsung Electronics         | 93        | 118    | 10.26%  |
| Toshiba                     | 78        | 93     | 8.61%   |
| Kingston                    | 66        | 85     | 7.28%   |
| Crucial                     | 56        | 63     | 6.18%   |
| Unknown                     | 50        | 59     | 5.52%   |
| SanDisk                     | 44        | 49     | 4.86%   |
| HGST                        | 40        | 45     | 4.42%   |
| SK hynix                    | 36        | 43     | 3.97%   |
| Intel                       | 32        | 48     | 3.53%   |
| Hitachi                     | 28        | 32     | 3.09%   |
| Micron Technology           | 13        | 18     | 1.43%   |
| China                       | 13        | 15     | 1.43%   |
| KIOXIA                      | 11        | 15     | 1.21%   |
| Apple                       | 9         | 9      | 0.99%   |
| Kingston Technology Company | 8         | 9      | 0.88%   |
| KingSpec                    | 8         | 17     | 0.88%   |
| JMicron Technology          | 6         | 8      | 0.66%   |
| Micron/Crucial Technology   | 5         | 6      | 0.55%   |
| LITEON                      | 5         | 5      | 0.55%   |
| A-DATA Technology           | 5         | 7      | 0.55%   |
| SSSTC                       | 3         | 4      | 0.33%   |
| Phison                      | 3         | 3      | 0.33%   |
| O2 Micro                    | 3         | 3      | 0.33%   |
| MAXIO Technology (Hangzhou) | 3         | 4      | 0.33%   |
| Lexar                       | 3         | 12     | 0.33%   |
| XrayDisk                    | 2         | 2      | 0.22%   |
| UMIS                        | 2         | 2      | 0.22%   |
| Silicon Motion              | 2         | 2      | 0.22%   |
| Realtek                     | 2         | 3      | 0.22%   |
| Phison Electronics          | 2         | 2      | 0.22%   |
| Netac                       | 2         | 2      | 0.22%   |
| Mass                        | 2         | 2      | 0.22%   |
| LITEONIT                    | 2         | 2      | 0.22%   |
| HS-SSD-E100N                | 2         | 2      | 0.22%   |
| FORESEE                     | 2         | 3      | 0.22%   |
| Corsair                     | 2         | 2      | 0.22%   |
| Unknown                     | 2         | 2      | 0.22%   |
| XPG                         | 1         | 2      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                    | 19        | 2.01%   |
| Toshiba MQ01ABF050 500GB                          | 15        | 1.59%   |
| Kingston SA400S37480G 480GB SSD                   | 13        | 1.38%   |
| Toshiba MQ01ABD100 1TB                            | 12        | 1.27%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 11        | 1.17%   |
| Toshiba MQ04ABF100 1TB                            | 11        | 1.17%   |
| Kingston SA400S37240G 240GB SSD                   | 11        | 1.17%   |
| Crucial CT240BX500SSD1 240GB                      | 11        | 1.17%   |
| Unknown MMC Card  64GB                            | 10        | 1.06%   |
| Seagate ST9500325AS 500GB                         | 10        | 1.06%   |
| HGST HTS545050A7E680 500GB                        | 9         | 0.95%   |
| HGST HTS541010A9E680 1TB                          | 9         | 0.95%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                  | 8         | 0.85%   |
| Seagate ST500LM012 HN-M500MBB 500GB               | 8         | 0.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 8         | 0.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 8         | 0.85%   |
| WDC WD10SPZX-24Z10 1TB                            | 7         | 0.74%   |
| Unknown MMC Card  32GB                            | 7         | 0.74%   |
| Unknown MMC Card  128GB                           | 7         | 0.74%   |
| Seagate ST500LT012-1DG142 500GB                   | 7         | 0.74%   |
| Samsung NVMe SSD Drive 512GB                      | 7         | 0.74%   |
| Intel SSDPEKNU512GZ 512GB                         | 7         | 0.74%   |
| Intel HBRPEKNX0101AHO 16GB                        | 7         | 0.74%   |
| Intel HBRPEKNX0101AH 256GB                        | 7         | 0.74%   |
| HGST HTS545050A7E380 500GB                        | 7         | 0.74%   |
| Crucial CT480BX500SSD1 480GB                      | 7         | 0.74%   |
| Crucial CT120BX500SSD1 120GB                      | 7         | 0.74%   |
| Crucial CT1000MX500SSD1 1TB                       | 7         | 0.74%   |
| Kingston SNVS500G 500GB                           | 6         | 0.64%   |
| HGST HTS541010B7E610 1TB                          | 6         | 0.64%   |
| WDC WD10SPZX-60Z10T0 1TB                          | 5         | 0.53%   |
| WDC WD10JPVX-60JC3T0 1TB                          | 5         | 0.53%   |
| Toshiba MQ01ABD075 752GB                          | 5         | 0.53%   |
| Seagate ST500LT012-9WS142 500GB                   | 5         | 0.53%   |
| Seagate ST500LM021-1KJ152 500GB                   | 5         | 0.53%   |
| Sandisk WD Blue SN550 NVMe SSD 2TB                | 5         | 0.53%   |
| Samsung HN-M500MBB 500GB                          | 5         | 0.53%   |
| JMicron Generic 320GB                             | 5         | 0.53%   |
| Hitachi HTS545050B9A300 500GB                     | 5         | 0.53%   |
| Crucial CT500MX500SSD1 500GB                      | 5         | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 92        | 111    | 27.06%  |
| Seagate             | 92        | 118    | 27.06%  |
| Toshiba             | 66        | 77     | 19.41%  |
| HGST                | 40        | 45     | 11.76%  |
| Hitachi             | 28        | 32     | 8.24%   |
| Samsung Electronics | 10        | 12     | 2.94%   |
| JMicron Technology  | 5         | 7      | 1.47%   |
| Unknown             | 2         | 2      | 0.59%   |
| Apple               | 2         | 2      | 0.59%   |
| SABRENT             | 1         | 1      | 0.29%   |
| Fujitsu             | 1         | 1      | 0.29%   |
| ASMT                | 1         | 2      | 0.29%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 54        | 61     | 20.07%  |
| WDC                 | 48        | 68     | 17.84%  |
| Kingston            | 48        | 63     | 17.84%  |
| Samsung Electronics | 27        | 30     | 10.04%  |
| SanDisk             | 19        | 21     | 7.06%   |
| China               | 13        | 15     | 4.83%   |
| KingSpec            | 8         | 17     | 2.97%   |
| Apple               | 7         | 7      | 2.6%    |
| SK hynix            | 5         | 8      | 1.86%   |
| A-DATA Technology   | 5         | 7      | 1.86%   |
| Toshiba             | 3         | 7      | 1.12%   |
| LITEON              | 3         | 3      | 1.12%   |
| Lexar               | 3         | 12     | 1.12%   |
| Netac               | 2         | 2      | 0.74%   |
| Micron Technology   | 2         | 2      | 0.74%   |
| LITEONIT            | 2         | 2      | 0.74%   |
| Intel               | 2         | 3      | 0.74%   |
| FORESEE             | 2         | 3      | 0.74%   |
| Corsair             | 2         | 2      | 0.74%   |
| XrayDisk            | 1         | 1      | 0.37%   |
| Wdxsky              | 1         | 1      | 0.37%   |
| Vaseky              | 1         | 1      | 0.37%   |
| StoreJet            | 1         | 1      | 0.37%   |
| SCY                 | 1         | 1      | 0.37%   |
| OSCOO               | 1         | 1      | 0.37%   |
| MemoiresTek         | 1         | 1      | 0.37%   |
| Maxell              | 1         | 1      | 0.37%   |
| KingDian            | 1         | 2      | 0.37%   |
| HS-SSD-C100         | 1         | 1      | 0.37%   |
| Hewlett-Packard     | 1         | 1      | 0.37%   |
| Gigabyte Technology | 1         | 1      | 0.37%   |
| Faspeed             | 1         | 1      | 0.37%   |
| Unknown             | 1         | 1      | 0.37%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 331       | 410    | 38%     |
| SSD     | 255       | 348    | 29.28%  |
| NVMe    | 229       | 315    | 26.29%  |
| MMC     | 45        | 53     | 5.17%   |
| Unknown | 11        | 13     | 1.26%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 534       | 748    | 64.49%  |
| NVMe | 229       | 312    | 27.66%  |
| MMC  | 45        | 53     | 5.43%   |
| SAS  | 20        | 26     | 2.42%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 374       | 510    | 65.73%  |
| 0.51-1.0   | 183       | 235    | 32.16%  |
| 1.01-2.0   | 12        | 13     | 2.11%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 258       | 32.87%  |
| 101-250        | 213       | 27.13%  |
| 501-1000       | 127       | 16.18%  |
| 1-20           | 49        | 6.24%   |
| 1001-2000      | 44        | 5.61%   |
| 51-100         | 37        | 4.71%   |
| 21-50          | 27        | 3.44%   |
| Unknown        | 14        | 1.78%   |
| 2001-3000      | 9         | 1.15%   |
| More than 3000 | 7         | 0.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 321       | 39.24%  |
| 21-50          | 159       | 19.44%  |
| 101-250        | 109       | 13.33%  |
| 51-100         | 108       | 13.2%   |
| 251-500        | 69        | 8.44%   |
| 501-1000       | 30        | 3.67%   |
| Unknown        | 14        | 1.71%   |
| 1001-2000      | 7         | 0.86%   |
| More than 3000 | 1         | 0.12%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB            | 4         | 4      | 6.9%    |
| Seagate ST500LT012-9WS142 500GB       | 3         | 3      | 5.17%   |
| HGST HTS545050A7E380 500GB            | 3         | 3      | 5.17%   |
| Toshiba MQ01ABD075 752GB              | 2         | 3      | 3.45%   |
| Seagate ST9500325AS 500GB             | 2         | 2      | 3.45%   |
| Seagate ST500LT012-1DG142 500GB       | 2         | 2      | 3.45%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 2         | 2      | 3.45%   |
| HGST HTS541010B7E610 1TB              | 2         | 3      | 3.45%   |
| HGST HTS541010A9E680 1TB              | 2         | 3      | 3.45%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 1.72%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD      | 1         | 1      | 1.72%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 1      | 1.72%   |
| WDC WD5000LPLX-60ZNTT1 500GB          | 1         | 1      | 1.72%   |
| WDC WD5000LPCX-60VHAT0 500GB          | 1         | 1      | 1.72%   |
| WDC WD10SPZX-24Z10 1TB                | 1         | 1      | 1.72%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 1      | 1.72%   |
| WDC WD Green 2.5 240GB                | 1         | 3      | 1.72%   |
| Vaseky V820/1TB 1024GB                | 1         | 1      | 1.72%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 1.72%   |
| Toshiba MQ01ABD050 500GB              | 1         | 1      | 1.72%   |
| Toshiba MK3265GSXN 320GB              | 1         | 1      | 1.72%   |
| Toshiba MK3265GSX 320GB               | 1         | 1      | 1.72%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 1.72%   |
| SK hynix BC711 HFM256GD3JX013N 256GB  | 1         | 1      | 1.72%   |
| Seagate ST9750420AS 752GB             | 1         | 1      | 1.72%   |
| Seagate ST9250315AS 250GB             | 1         | 1      | 1.72%   |
| Seagate ST1000LM048-2E7172 1TB        | 1         | 1      | 1.72%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 1.72%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 6      | 1.72%   |
| LITEON CV8-8E128-HP 128GB SSD         | 1         | 1      | 1.72%   |
| Kingston SVP200S3120G 120GB SSD       | 1         | 1      | 1.72%   |
| Hitachi HTS722016K9A300 160GB         | 1         | 1      | 1.72%   |
| Hitachi HTS547575A9E384 752GB         | 1         | 2      | 1.72%   |
| Hitachi HTS547564A9E384 640GB         | 1         | 2      | 1.72%   |
| Hitachi HTS545050B9A300 500GB         | 1         | 2      | 1.72%   |
| Hitachi HTS545050A7E380 500GB         | 1         | 1      | 1.72%   |
| Hitachi HTS543232L9A300 320GB         | 1         | 1      | 1.72%   |
| HGST HTS725032A7E630 320GB            | 1         | 1      | 1.72%   |
| HGST HTS545050A7E660 500GB            | 1         | 1      | 1.72%   |
| HGST HTS541075A9E680 752GB            | 1         | 1      | 1.72%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| HGST     | 15        | 17     | 25.86%  |
| Seagate  | 14        | 19     | 24.14%  |
| WDC      | 8         | 10     | 13.79%  |
| Toshiba  | 6         | 7      | 10.34%  |
| Hitachi  | 6         | 9      | 10.34%  |
| SK hynix | 2         | 2      | 3.45%   |
| Crucial  | 2         | 2      | 3.45%   |
| Vaseky   | 1         | 1      | 1.72%   |
| LITEON   | 1         | 1      | 1.72%   |
| Kingston | 1         | 1      | 1.72%   |
| Faspeed  | 1         | 1      | 1.72%   |
| China    | 1         | 1      | 1.72%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 15        | 17     | 32.61%  |
| Seagate | 14        | 19     | 30.43%  |
| Toshiba | 6         | 7      | 13.04%  |
| Hitachi | 6         | 9      | 13.04%  |
| WDC     | 5         | 5      | 10.87%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 46        | 57     | 79.31%  |
| SSD  | 11        | 13     | 18.97%  |
| NVMe | 1         | 1      | 1.72%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST9320325AS 320GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 487       | 703    | 61.72%  |
| Works    | 243       | 364    | 30.8%   |
| Malfunc  | 58        | 71     | 7.35%   |
| Failed   | 1         | 1      | 0.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 502       | 58.71%  |
| AMD                                  | 121       | 14.15%  |
| Samsung Electronics                  | 65        | 7.6%    |
| SanDisk                              | 38        | 4.44%   |
| SK hynix                             | 31        | 3.63%   |
| Kingston Technology Company          | 25        | 2.92%   |
| KIOXIA                               | 12        | 1.4%    |
| Micron Technology                    | 11        | 1.29%   |
| Toshiba America Info Systems         | 8         | 0.94%   |
| Micron/Crucial Technology            | 7         | 0.82%   |
| Phison Electronics                   | 5         | 0.58%   |
| Silicon Integrated Systems [SiS]     | 4         | 0.47%   |
| Nvidia                               | 4         | 0.47%   |
| MAXIO Technology (Hangzhou)          | 4         | 0.47%   |
| Union Memory (Shenzhen)              | 3         | 0.35%   |
| Solid State Storage Technology       | 3         | 0.35%   |
| O2 Micro                             | 3         | 0.35%   |
| Silicon Motion                       | 2         | 0.23%   |
| Lite-On Technology                   | 2         | 0.23%   |
| ADATA Technology                     | 2         | 0.23%   |
| Solidigm                             | 1         | 0.12%   |
| Ramaxel Technology(Shenzhen) Limited | 1         | 0.12%   |
| Hosin Global Electronics             | 1         | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 105       | 11.43%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 83        | 9.03%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 50        | 5.44%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 50        | 5.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 28        | 3.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 28        | 3.05%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 24        | 2.61%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 22        | 2.39%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 22        | 2.39%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                            | 18        | 1.96%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 18        | 1.96%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 17        | 1.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 16        | 1.74%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 15        | 1.63%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 14        | 1.52%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 14        | 1.52%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 13        | 1.41%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 13        | 1.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 13        | 1.41%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                   | 12        | 1.31%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                              | 11        | 1.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 11        | 1.2%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                   | 10        | 1.09%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                             | 10        | 1.09%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 9         | 0.98%   |
| Intel SSD 670p Series [Keystone Harbor]                                                | 9         | 0.98%   |
| Intel SSD 660P Series                                                                  | 9         | 0.98%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]                     | 9         | 0.98%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 8         | 0.87%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 8         | 0.87%   |
| SK hynix BC511 NVMe SSD                                                                | 7         | 0.76%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 7         | 0.76%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 7         | 0.76%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 7         | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 7         | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 7         | 0.76%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 6         | 0.65%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                                  | 6         | 0.65%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 6         | 0.65%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 6         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 526       | 59.64%  |
| NVMe | 230       | 26.08%  |
| RAID | 81        | 9.18%   |
| IDE  | 45        | 5.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 570       | 76.82%  |
| AMD    | 172       | 23.18%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 22        | 2.96%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 16        | 2.15%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 14        | 1.88%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 13        | 1.75%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 11        | 1.48%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 10        | 1.35%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 10        | 1.35%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 10        | 1.35%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 1.21%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 9         | 1.21%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 9         | 1.21%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 8         | 1.08%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 8         | 1.08%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 7         | 0.94%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 7         | 0.94%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 7         | 0.94%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 7         | 0.94%   |
| AMD Custom APU 0405                           | 7         | 0.94%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 6         | 0.81%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 6         | 0.81%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 6         | 0.81%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 6         | 0.81%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 6         | 0.81%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 6         | 0.81%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 6         | 0.81%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 6         | 0.81%   |
| AMD Ryzen 3 4300U with Radeon Graphics        | 6         | 0.81%   |
| AMD E1-2100 APU with Radeon HD Graphics       | 6         | 0.81%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 5         | 0.67%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 5         | 0.67%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 0.67%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 5         | 0.67%   |
| Intel Celeron N4500 @ 1.10GHz                 | 5         | 0.67%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 5         | 0.67%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 5         | 0.67%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 5         | 0.67%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 5         | 0.67%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 5         | 0.67%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 4         | 0.54%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 4         | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 167       | 22.48%  |
| Intel Core i7           | 128       | 17.23%  |
| Intel Core i3           | 70        | 9.42%   |
| Intel Celeron           | 58        | 7.81%   |
| Other                   | 55        | 7.4%    |
| AMD Ryzen 5             | 38        | 5.11%   |
| Intel Pentium           | 30        | 4.04%   |
| AMD Ryzen 7             | 21        | 2.83%   |
| Intel Core 2 Duo        | 18        | 2.42%   |
| Intel Atom              | 18        | 2.42%   |
| AMD A10                 | 15        | 2.02%   |
| AMD Ryzen 3             | 11        | 1.48%   |
| Intel Pentium Dual-Core | 10        | 1.35%   |
| AMD A8                  | 10        | 1.35%   |
| AMD E1                  | 9         | 1.21%   |
| AMD A6                  | 9         | 1.21%   |
| AMD E2                  | 7         | 0.94%   |
| AMD A4                  | 7         | 0.94%   |
| Intel Pentium Dual      | 6         | 0.81%   |
| AMD E                   | 6         | 0.81%   |
| AMD Turion II Dual-Core | 4         | 0.54%   |
| AMD Ryzen 5 PRO         | 4         | 0.54%   |
| AMD A12                 | 4         | 0.54%   |
| Intel Pentium Silver    | 3         | 0.4%    |
| Intel Genuine           | 3         | 0.4%    |
| Intel Celeron Dual-Core | 3         | 0.4%    |
| AMD Ryzen 9             | 3         | 0.4%    |
| AMD Ryzen 7 PRO         | 3         | 0.4%    |
| Intel Xeon              | 2         | 0.27%   |
| Intel Core i9           | 2         | 0.27%   |
| Intel Core 2            | 2         | 0.27%   |
| Intel Celeron M         | 2         | 0.27%   |
| AMD Mobile Sempron      | 2         | 0.27%   |
| AMD C-60                | 2         | 0.27%   |
| AMD Athlon II           | 2         | 0.27%   |
| Intel Core m5           | 1         | 0.13%   |
| Intel Core Duo          | 1         | 0.13%   |
| Intel Core 2 Extreme    | 1         | 0.13%   |
| AMD Turion II           | 1         | 0.13%   |
| AMD Turion 64 X2 Mobile | 1         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 400       | 53.84%  |
| 4       | 258       | 34.72%  |
| 8       | 29        | 3.9%    |
| 6       | 28        | 3.77%   |
| 1       | 11        | 1.48%   |
| 14      | 5         | 0.67%   |
| Unknown | 5         | 0.67%   |
| 10      | 3         | 0.4%    |
| 16      | 2         | 0.27%   |
| 12      | 1         | 0.13%   |
| 3       | 1         | 0.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 740       | 99.73%  |
| 4       | 1         | 0.13%   |
| Unknown | 1         | 0.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 515       | 69.03%  |
| 1       | 226       | 30.29%  |
| Unknown | 5         | 0.67%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 722       | 97.04%  |
| Unknown        | 10        | 1.34%   |
| 32-bit         | 7         | 0.94%   |
| 64-bit         | 5         | 0.67%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 254       | 33.2%   |
| 0x206a7    | 38        | 4.97%   |
| 0x406e3    | 31        | 4.05%   |
| 0x806ec    | 24        | 3.14%   |
| 0x306a9    | 24        | 3.14%   |
| 0x806e9    | 21        | 2.75%   |
| 0x40651    | 21        | 2.75%   |
| 0x1067a    | 18        | 2.35%   |
| 0x806c1    | 16        | 2.09%   |
| 0x30678    | 16        | 2.09%   |
| 0x906ea    | 15        | 1.96%   |
| 0x806ea    | 14        | 1.83%   |
| 0x20655    | 13        | 1.7%    |
| 0x08108102 | 12        | 1.57%   |
| 0xa0652    | 11        | 1.44%   |
| 0x306d4    | 11        | 1.44%   |
| 0x08108109 | 11        | 1.44%   |
| 0x0a50000c | 10        | 1.31%   |
| 0x6fd      | 9         | 1.18%   |
| 0x0810100b | 9         | 1.18%   |
| 0x05000119 | 9         | 1.18%   |
| 0x906e9    | 8         | 1.05%   |
| 0x406c4    | 8         | 1.05%   |
| 0x306c3    | 8         | 1.05%   |
| 0x506c9    | 7         | 0.92%   |
| 0x406c3    | 7         | 0.92%   |
| 0x08608103 | 7         | 0.92%   |
| 0x08600106 | 7         | 0.92%   |
| 0x07030105 | 7         | 0.92%   |
| 0x706e5    | 6         | 0.78%   |
| 0x706a8    | 6         | 0.78%   |
| 0x0700010f | 6         | 0.78%   |
| 0x06006705 | 6         | 0.78%   |
| 0x806eb    | 5         | 0.65%   |
| 0x706a1    | 5         | 0.65%   |
| 0x106ca    | 5         | 0.65%   |
| 0x906c0    | 4         | 0.52%   |
| 0x10676    | 4         | 0.52%   |
| 0x07030106 | 4         | 0.52%   |
| 0x06001119 | 4         | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 153       | 20.59%  |
| SandyBridge      | 52        | 7%      |
| Skylake          | 43        | 5.79%   |
| Haswell          | 42        | 5.65%   |
| Silvermont       | 38        | 5.11%   |
| IvyBridge        | 36        | 4.85%   |
| TigerLake        | 30        | 4.04%   |
| Penryn           | 30        | 4.04%   |
| Zen+             | 28        | 3.77%   |
| Unknown          | 27        | 3.63%   |
| Westmere         | 22        | 2.96%   |
| Excavator        | 20        | 2.69%   |
| Broadwell        | 20        | 2.69%   |
| Zen 2            | 18        | 2.42%   |
| Goldmont plus    | 18        | 2.42%   |
| IceLake          | 16        | 2.15%   |
| CometLake        | 16        | 2.15%   |
| Bobcat           | 14        | 1.88%   |
| Zen 3            | 13        | 1.75%   |
| Puma             | 12        | 1.62%   |
| Zen              | 11        | 1.48%   |
| Core             | 11        | 1.48%   |
| Piledriver       | 10        | 1.35%   |
| Jaguar           | 10        | 1.35%   |
| Bonnell          | 10        | 1.35%   |
| K10              | 8         | 1.08%   |
| Goldmont         | 8         | 1.08%   |
| Alderlake Hybrid | 8         | 1.08%   |
| Tremont          | 4         | 0.54%   |
| P6               | 4         | 0.54%   |
| K10 Llano        | 4         | 0.54%   |
| K8 Hammer        | 3         | 0.4%    |
| Steamroller      | 2         | 0.27%   |
| Nehalem          | 1         | 0.13%   |
| K8 & K10 hybrid  | 1         | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 538       | 59.06%  |
| AMD                              | 203       | 22.28%  |
| Nvidia                           | 165       | 18.11%  |
| Silicon Integrated Systems [SiS] | 4         | 0.44%   |
| ATI Technologies                 | 1         | 0.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 50        | 5.24%   |
| Intel HD Graphics 620                                                                    | 45        | 4.71%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 35        | 3.66%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 33        | 3.46%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 28        | 2.93%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 26        | 2.72%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 24        | 2.51%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 24        | 2.51%   |
| Intel UHD Graphics 620                                                                   | 23        | 2.41%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 22        | 2.3%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 21        | 2.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 19        | 1.99%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 19        | 1.99%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 18        | 1.88%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 18        | 1.88%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 17        | 1.78%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 16        | 1.68%   |
| Intel Core Processor Integrated Graphics Controller                                      | 16        | 1.68%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 16        | 1.68%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 15        | 1.57%   |
| Intel HD Graphics 5500                                                                   | 15        | 1.57%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 15        | 1.57%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 14        | 1.47%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 13        | 1.36%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 12        | 1.26%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 12        | 1.26%   |
| Intel HD Graphics 630                                                                    | 11        | 1.15%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 11        | 1.15%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 11        | 1.15%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 10        | 1.05%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 9         | 0.94%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 9         | 0.94%   |
| AMD Lucienne                                                                             | 9         | 0.94%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 8         | 0.84%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 8         | 0.84%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 7         | 0.73%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 7         | 0.73%   |
| Nvidia GM108M [GeForce 840M]                                                             | 6         | 0.63%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 6         | 0.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 6         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 384       | 51.75%  |
| 1 x AMD        | 132       | 17.79%  |
| Intel + Nvidia | 127       | 17.12%  |
| 2 x AMD        | 30        | 4.04%   |
| Intel + AMD    | 26        | 3.5%    |
| 1 x Nvidia     | 22        | 2.96%   |
| AMD + Nvidia   | 16        | 2.16%   |
| 1 x SiS        | 4         | 0.54%   |
| 2 x Intel      | 1         | 0.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 640       | 85.56%  |
| Proprietary | 85        | 11.36%  |
| Unknown     | 23        | 3.07%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 497       | 65.48%  |
| 0.01-0.5   | 97        | 12.78%  |
| 1.01-2.0   | 82        | 10.8%   |
| 0.51-1.0   | 43        | 5.67%   |
| 3.01-4.0   | 29        | 3.82%   |
| 5.01-6.0   | 5         | 0.66%   |
| 2.01-3.0   | 3         | 0.4%    |
| 7.01-8.0   | 2         | 0.26%   |
| 8.01-16.0  | 1         | 0.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 157       | 18.13%  |
| BOE                     | 148       | 17.09%  |
| Chimei Innolux          | 142       | 16.4%   |
| Samsung Electronics     | 115       | 13.28%  |
| LG Display              | 88        | 10.16%  |
| Goldstar                | 28        | 3.23%   |
| PANDA                   | 14        | 1.62%   |
| Lenovo                  | 13        | 1.5%    |
| AOC                     | 13        | 1.5%    |
| Apple                   | 12        | 1.39%   |
| ViewSonic               | 10        | 1.15%   |
| Dell                    | 10        | 1.15%   |
| Chi Mei Optoelectronics | 10        | 1.15%   |
| Sony                    | 8         | 0.92%   |
| InfoVision              | 8         | 0.92%   |
| Sharp                   | 7         | 0.81%   |
| Hewlett-Packard         | 7         | 0.81%   |
| Valve                   | 6         | 0.69%   |
| LG Philips              | 6         | 0.69%   |
| Envision                | 5         | 0.58%   |
| CSO                     | 5         | 0.58%   |
| Acer                    | 5         | 0.58%   |
| SAC                     | 4         | 0.46%   |
| ASUSTek Computer        | 4         | 0.46%   |
| Unknown                 | 3         | 0.35%   |
| SLD                     | 3         | 0.35%   |
| MSI                     | 3         | 0.35%   |
| HKC                     | 3         | 0.35%   |
| Ancor Communications    | 3         | 0.35%   |
| STA                     | 2         | 0.23%   |
| Panasonic               | 2         | 0.23%   |
| LGD                     | 2         | 0.23%   |
| InnoLux Display         | 2         | 0.23%   |
| Hitachi                 | 2         | 0.23%   |
| CPT                     | 2         | 0.23%   |
| ___                     | 1         | 0.12%   |
| SGT                     | 1         | 0.12%   |
| RGT                     | 1         | 0.12%   |
| Onkyo                   | 1         | 0.12%   |
| NCS                     | 1         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 11        | 1.26%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                  | 11        | 1.26%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 10        | 1.15%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 9         | 1.03%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 8         | 0.92%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 7         | 0.8%    |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 6         | 0.69%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch | 6         | 0.69%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 6         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 6         | 0.69%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 6         | 0.69%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 6         | 0.69%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 6         | 0.69%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 6         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 5         | 0.57%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 5         | 0.57%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 5         | 0.57%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch       | 5         | 0.57%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 5         | 0.57%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 5         | 0.57%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 5         | 0.57%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 5         | 0.57%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 5         | 0.57%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 4         | 0.46%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch  | 4         | 0.46%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 4         | 0.46%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 4         | 0.46%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch           | 4         | 0.46%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 4         | 0.46%   |
| Chimei Innolux LCD Monitor CMN1618 1920x1200 344x215mm 16.0-inch      | 4         | 0.46%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x173mm 13.9-inch       | 4         | 0.46%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 4         | 0.46%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 4         | 0.46%   |
| BOE LCD Monitor BOE0628 1366x768 309x173mm 13.9-inch                  | 4         | 0.46%   |
| BOE LCD Monitor BOE0602 1366x768 344x193mm 15.5-inch                  | 4         | 0.46%   |
| BOE LCD Monitor BOE05BA 1366x768 309x173mm 13.9-inch                  | 4         | 0.46%   |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch         | 4         | 0.46%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 4         | 0.46%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch         | 4         | 0.46%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch         | 4         | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 363       | 44.27%  |
| 1920x1080 (FHD)    | 273       | 33.29%  |
| 1280x800 (WXGA)    | 26        | 3.17%   |
| 1600x900 (HD+)     | 25        | 3.05%   |
| 3840x2160 (4K)     | 17        | 2.07%   |
| 1360x768           | 16        | 1.95%   |
| 1920x1200 (WUXGA)  | 14        | 1.71%   |
| 1440x900 (WXGA+)   | 9         | 1.1%    |
| 1680x1050 (WSXGA+) | 8         | 0.98%   |
| 1280x1024 (SXGA)   | 8         | 0.98%   |
| 800x1280           | 7         | 0.85%   |
| 2560x1600          | 7         | 0.85%   |
| 2560x1440 (QHD)    | 7         | 0.85%   |
| 2560x1080          | 7         | 0.85%   |
| 2880x1800          | 4         | 0.49%   |
| 2160x1440          | 4         | 0.49%   |
| 1024x600           | 4         | 0.49%   |
| 3840x1100          | 3         | 0.37%   |
| 1920x540           | 3         | 0.37%   |
| 3440x1440          | 2         | 0.24%   |
| 1024x576           | 2         | 0.24%   |
| Unknown            | 2         | 0.24%   |
| 5440x1800          | 1         | 0.12%   |
| 3840x2400          | 1         | 0.12%   |
| 3840x1080          | 1         | 0.12%   |
| 3286x1080          | 1         | 0.12%   |
| 2288x1287          | 1         | 0.12%   |
| 1920x515           | 1         | 0.12%   |
| 1680x945           | 1         | 0.12%   |
| 1600x2560          | 1         | 0.12%   |
| 1280x720 (HD)      | 1         | 0.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 261       | 30%     |
| 13      | 185       | 21.26%  |
| 14      | 167       | 19.2%   |
| 23      | 31        | 3.56%   |
| 21      | 28        | 3.22%   |
| 17      | 24        | 2.76%   |
| 12      | 18        | 2.07%   |
| 11      | 17        | 1.95%   |
| 27      | 16        | 1.84%   |
| 24      | 16        | 1.84%   |
| 16      | 12        | 1.38%   |
| 31      | 11        | 1.26%   |
| 19      | 10        | 1.15%   |
| 18      | 10        | 1.15%   |
| 34      | 9         | 1.03%   |
| Unknown | 9         | 1.03%   |
| 10      | 8         | 0.92%   |
| 7       | 6         | 0.69%   |
| 72      | 5         | 0.57%   |
| 22      | 5         | 0.57%   |
| 32      | 4         | 0.46%   |
| 20      | 4         | 0.46%   |
| 48      | 3         | 0.34%   |
| 54      | 2         | 0.23%   |
| 40      | 2         | 0.23%   |
| 142     | 1         | 0.11%   |
| 84      | 1         | 0.11%   |
| 58      | 1         | 0.11%   |
| 49      | 1         | 0.11%   |
| 46      | 1         | 0.11%   |
| 43      | 1         | 0.11%   |
| 3       | 1         | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 563       | 65.47%  |
| 201-300        | 94        | 10.93%  |
| 501-600        | 57        | 6.63%   |
| 401-500        | 49        | 5.7%    |
| 351-400        | 35        | 4.07%   |
| 601-700        | 15        | 1.74%   |
| 701-800        | 13        | 1.51%   |
| Unknown        | 9         | 1.05%   |
| 1001-1500      | 8         | 0.93%   |
| 1-100          | 7         | 0.81%   |
| 1501-2000      | 6         | 0.7%    |
| 801-900        | 2         | 0.23%   |
| More than 2000 | 1         | 0.12%   |
| 901-1000       | 1         | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 631       | 84.13%  |
| 16/10   | 75        | 10%     |
| 21/9    | 9         | 1.2%    |
| 5/4     | 8         | 1.07%   |
| 0.67    | 6         | 0.8%    |
| 3/2     | 5         | 0.67%   |
| Unknown | 4         | 0.53%   |
| 4/3     | 3         | 0.4%    |
| 3.40    | 3         | 0.4%    |
| 1.96    | 2         | 0.27%   |
| 6/5     | 1         | 0.13%   |
| 32/9    | 1         | 0.13%   |
| 3.73    | 1         | 0.13%   |
| 1.00    | 1         | 0.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 306       | 35.33%  |
| 101-110        | 261       | 30.14%  |
| 201-250        | 65        | 7.51%   |
| 71-80          | 44        | 5.08%   |
| 351-500        | 24        | 2.77%   |
| 151-200        | 21        | 2.42%   |
| 51-60          | 20        | 2.31%   |
| 301-350        | 16        | 1.85%   |
| 121-130        | 16        | 1.85%   |
| 61-70          | 15        | 1.73%   |
| 141-150        | 13        | 1.5%    |
| More than 1000 | 11        | 1.27%   |
| 111-120        | 11        | 1.27%   |
| Unknown        | 9         | 1.04%   |
| 41-50          | 8         | 0.92%   |
| 1-40           | 7         | 0.81%   |
| 501-1000       | 7         | 0.81%   |
| 131-140        | 5         | 0.58%   |
| 251-300        | 4         | 0.46%   |
| 91-100         | 3         | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 377       | 44.35%  |
| 121-160       | 252       | 29.65%  |
| 51-100        | 124       | 14.59%  |
| 161-240       | 53        | 6.24%   |
| 1-50          | 23        | 2.71%   |
| More than 240 | 12        | 1.41%   |
| Unknown       | 9         | 1.06%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 586       | 76.5%   |
| 2     | 149       | 19.45%  |
| 0     | 19        | 2.48%   |
| 3     | 11        | 1.44%   |
| 4     | 1         | 0.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 480       | 40.89%  |
| Intel                            | 304       | 25.89%  |
| Qualcomm Atheros                 | 168       | 14.31%  |
| Broadcom                         | 77        | 6.56%   |
| Ralink                           | 18        | 1.53%   |
| MediaTek                         | 17        | 1.45%   |
| Marvell Technology Group         | 12        | 1.02%   |
| Huawei Technologies              | 12        | 1.02%   |
| Broadcom Limited                 | 12        | 1.02%   |
| Samsung Electronics              | 10        | 0.85%   |
| Xiaomi                           | 9         | 0.77%   |
| TP-Link                          | 9         | 0.77%   |
| Ralink Technology                | 7         | 0.6%    |
| Silicon Integrated Systems [SiS] | 4         | 0.34%   |
| Qualcomm Atheros Communications  | 4         | 0.34%   |
| Nvidia                           | 4         | 0.34%   |
| JMicron Technology               | 4         | 0.34%   |
| ICS Advent                       | 3         | 0.26%   |
| D-Link                           | 3         | 0.26%   |
| ASIX Electronics                 | 3         | 0.26%   |
| Lenovo                           | 2         | 0.17%   |
| Qualcomm                         | 1         | 0.09%   |
| Qcom                             | 1         | 0.09%   |
| Netchip Technology               | 1         | 0.09%   |
| Motorola PCS                     | 1         | 0.09%   |
| Microsoft                        | 1         | 0.09%   |
| Microchip Technology             | 1         | 0.09%   |
| Hewlett-Packard                  | 1         | 0.09%   |
| DisplayLink                      | 1         | 0.09%   |
| D-Link System                    | 1         | 0.09%   |
| ASUSTek Computer                 | 1         | 0.09%   |
| Arduino SA                       | 1         | 0.09%   |
| Apple                            | 1         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 272       | 19.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 113       | 8%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 39        | 2.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 34        | 2.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 32        | 2.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 32        | 2.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 29        | 2.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 27        | 1.91%   |
| Intel Wireless 8265 / 8275                                              | 27        | 1.91%   |
| Intel Wi-Fi 6 AX200                                                     | 25        | 1.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 24        | 1.7%    |
| Realtek RTL8723DE Wireless Network Adapter                              | 22        | 1.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 22        | 1.56%   |
| Intel Wi-Fi 6 AX201                                                     | 21        | 1.49%   |
| Broadcom BCM43142 802.11b/g/n                                           | 21        | 1.49%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 20        | 1.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 19        | 1.34%   |
| Intel Wireless 8260                                                     | 19        | 1.34%   |
| Intel Wireless 7265                                                     | 15        | 1.06%   |
| Intel Wireless 7260                                                     | 15        | 1.06%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 14        | 0.99%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 13        | 0.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 13        | 0.92%   |
| Intel Ethernet Connection I219-LM                                       | 12        | 0.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 12        | 0.85%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 11        | 0.78%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 11        | 0.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 11        | 0.78%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 10        | 0.71%   |
| Intel Ethernet Connection (4) I219-V                                    | 10        | 0.71%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 10        | 0.71%   |
| Huawei VTR-L09                                                          | 10        | 0.71%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 9         | 0.64%   |
| Intel Ethernet Connection (4) I219-LM                                   | 9         | 0.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 9         | 0.64%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 8         | 0.57%   |
| Intel Wireless 3165                                                     | 8         | 0.57%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 0.5%    |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 7         | 0.5%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 295       | 38.41%  |
| Realtek Semiconductor           | 186       | 24.22%  |
| Qualcomm Atheros                | 152       | 19.79%  |
| Broadcom                        | 65        | 8.46%   |
| Ralink                          | 18        | 2.34%   |
| MediaTek                        | 15        | 1.95%   |
| Broadcom Limited                | 10        | 1.3%    |
| TP-Link                         | 8         | 1.04%   |
| Ralink Technology               | 7         | 0.91%   |
| Qualcomm Atheros Communications | 4         | 0.52%   |
| D-Link                          | 2         | 0.26%   |
| Qualcomm                        | 1         | 0.13%   |
| Qcom                            | 1         | 0.13%   |
| Microsoft                       | 1         | 0.13%   |
| Hewlett-Packard                 | 1         | 0.13%   |
| D-Link System                   | 1         | 0.13%   |
| ASUSTek Computer                | 1         | 0.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 39        | 5.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 34        | 4.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 32        | 4.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 32        | 4.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 29        | 3.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 27        | 3.5%    |
| Intel Wireless 8265 / 8275                                              | 27        | 3.5%    |
| Intel Wi-Fi 6 AX200                                                     | 25        | 3.24%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 24        | 3.11%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 22        | 2.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 22        | 2.85%   |
| Intel Wi-Fi 6 AX201                                                     | 21        | 2.72%   |
| Broadcom BCM43142 802.11b/g/n                                           | 21        | 2.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 20        | 2.59%   |
| Intel Wireless 8260                                                     | 19        | 2.46%   |
| Intel Wireless 7265                                                     | 15        | 1.94%   |
| Intel Wireless 7260                                                     | 15        | 1.94%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 14        | 1.81%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 13        | 1.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 13        | 1.68%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 11        | 1.42%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 11        | 1.42%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 11        | 1.42%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 10        | 1.3%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 10        | 1.3%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 9         | 1.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 9         | 1.17%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 8         | 1.04%   |
| Intel Wireless 3165                                                     | 8         | 1.04%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 0.91%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 0.91%   |
| Intel Centrino Advanced-N 6235                                          | 7         | 0.91%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 0.91%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 6         | 0.78%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 6         | 0.78%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 6         | 0.78%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 6         | 0.78%   |
| Intel Wireless 3160                                                     | 5         | 0.65%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 5         | 0.65%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 5         | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 414       | 65.09%  |
| Intel                            | 101       | 15.88%  |
| Qualcomm Atheros                 | 28        | 4.4%    |
| Broadcom                         | 20        | 3.14%   |
| Marvell Technology Group         | 12        | 1.89%   |
| Huawei Technologies              | 12        | 1.89%   |
| Xiaomi                           | 9         | 1.42%   |
| Samsung Electronics              | 9         | 1.42%   |
| Silicon Integrated Systems [SiS] | 4         | 0.63%   |
| Nvidia                           | 4         | 0.63%   |
| JMicron Technology               | 4         | 0.63%   |
| ICS Advent                       | 3         | 0.47%   |
| ASIX Electronics                 | 3         | 0.47%   |
| MediaTek                         | 2         | 0.31%   |
| Lenovo                           | 2         | 0.31%   |
| Broadcom Limited                 | 2         | 0.31%   |
| TP-Link                          | 1         | 0.16%   |
| Netchip Technology               | 1         | 0.16%   |
| Motorola PCS                     | 1         | 0.16%   |
| Microchip Technology             | 1         | 0.16%   |
| DisplayLink                      | 1         | 0.16%   |
| D-Link                           | 1         | 0.16%   |
| Apple                            | 1         | 0.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 272       | 42.63%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 113       | 17.71%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 19        | 2.98%   |
| Intel Ethernet Connection I219-LM                                      | 12        | 1.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 12        | 1.88%   |
| Intel Ethernet Connection (4) I219-V                                   | 10        | 1.57%   |
| Huawei VTR-L09                                                         | 10        | 1.57%   |
| Intel Ethernet Connection (4) I219-LM                                  | 9         | 1.41%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 7         | 1.1%    |
| Intel Ethernet Connection (3) I218-LM                                  | 7         | 1.1%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 6         | 0.94%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 6         | 0.94%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 6         | 0.94%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 6         | 0.94%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 5         | 0.78%   |
| Intel Ethernet Connection I217-LM                                      | 5         | 0.78%   |
| Intel Ethernet Connection (6) I219-V                                   | 5         | 0.78%   |
| Intel Ethernet Connection (13) I219-V                                  | 5         | 0.78%   |
| Intel 82567LM Gigabit Network Connection                               | 5         | 0.78%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 4         | 0.63%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 4         | 0.63%   |
| Intel Ethernet Connection I218-LM                                      | 4         | 0.63%   |
| Intel Ethernet Connection (10) I219-V                                  | 4         | 0.63%   |
| Intel Ethernet Connection (10) I219-LM                                 | 4         | 0.63%   |
| Intel 82577LM Gigabit Network Connection                               | 4         | 0.63%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 4         | 0.63%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 4         | 0.63%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 3         | 0.47%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 3         | 0.47%   |
| Realtek Killer E2600 GbE Controller                                    | 3         | 0.47%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 3         | 0.47%   |
| Intel 82566MM Gigabit Network Connection                               | 3         | 0.47%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 3         | 0.47%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2         | 0.31%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 0.31%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 0.31%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 2         | 0.31%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 2         | 0.31%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 2         | 0.31%   |
| Nvidia MCP51 Ethernet Controller                                       | 2         | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 733       | 54.74%  |
| Ethernet | 603       | 45.03%  |
| Modem    | 3         | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 607       | 77.82%  |
| Ethernet | 173       | 22.18%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 546       | 73.49%  |
| 1     | 181       | 24.36%  |
| 0     | 10        | 1.35%   |
| 3     | 6         | 0.81%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 657       | 87.6%   |
| Yes  | 93        | 12.4%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 243       | 39.64%  |
| Realtek Semiconductor           | 116       | 18.92%  |
| Qualcomm Atheros Communications | 50        | 8.16%   |
| Lite-On Technology              | 40        | 6.53%   |
| Broadcom                        | 39        | 6.36%   |
| IMC Networks                    | 38        | 6.2%    |
| Foxconn / Hon Hai               | 22        | 3.59%   |
| Apple                           | 12        | 1.96%   |
| Ralink                          | 10        | 1.63%   |
| Dell                            | 8         | 1.31%   |
| Realtek                         | 7         | 1.14%   |
| Hewlett-Packard                 | 7         | 1.14%   |
| Cambridge Silicon Radio         | 4         | 0.65%   |
| Toshiba                         | 3         | 0.49%   |
| Ralink Technology               | 3         | 0.49%   |
| Foxconn International           | 3         | 0.49%   |
| ASUSTek Computer                | 2         | 0.33%   |
| Actions                         | 2         | 0.33%   |
| USI                             | 1         | 0.16%   |
| MediaTek                        | 1         | 0.16%   |
| Integrated System Solution      | 1         | 0.16%   |
| Alps Electric                   | 1         | 0.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 54        | 8.79%   |
| Intel AX201 Bluetooth                               | 53        | 8.63%   |
| Intel Bluetooth wireless interface                  | 50        | 8.14%   |
| Intel Bluetooth Device                              | 41        | 6.68%   |
| Realtek  Bluetooth 4.2 Adapter                      | 39        | 6.35%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 38        | 6.19%   |
| Intel AX200 Bluetooth                               | 25        | 4.07%   |
| Qualcomm Atheros  Bluetooth Device                  | 21        | 3.42%   |
| IMC Networks Bluetooth Radio                        | 18        | 2.93%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 12        | 1.95%   |
| Realtek RTL8821A Bluetooth                          | 11        | 1.79%   |
| Lite-On Atheros AR3012 Bluetooth                    | 11        | 1.79%   |
| Ralink RT3290 Bluetooth                             | 10        | 1.63%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 10        | 1.63%   |
| Lite-On Bluetooth Device                            | 10        | 1.63%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 10        | 1.63%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 10        | 1.63%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 10        | 1.63%   |
| IMC Networks Bluetooth Device                       | 9         | 1.47%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 8         | 1.3%    |
| IMC Networks Wireless_Device                        | 8         | 1.3%    |
| Realtek 802.11ac WLAN Adapter                       | 7         | 1.14%   |
| Realtek Bluetooth Radio                             | 7         | 1.14%   |
| Intel AX210 Bluetooth                               | 6         | 0.98%   |
| Apple Bluetooth USB Host Controller                 | 6         | 0.98%   |
| Qualcomm Atheros Bluetooth                          | 5         | 0.81%   |
| Intel Wireless-AC 3168 Bluetooth                    | 5         | 0.81%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 0.81%   |
| Broadcom BCM2070 Bluetooth Device                   | 5         | 0.81%   |
| Apple Bluetooth Host Controller                     | 5         | 0.81%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 4         | 0.65%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 4         | 0.65%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 4         | 0.65%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 4         | 0.65%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 0.65%   |
| Broadcom HP Portable Bumble Bee                     | 4         | 0.65%   |
| Broadcom BCM43142A0 Bluetooth Device                | 4         | 0.65%   |
| Toshiba Bluetooth Device                            | 3         | 0.49%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 3         | 0.49%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 0.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 557       | 64.92%  |
| AMD                              | 177       | 20.63%  |
| Nvidia                           | 78        | 9.09%   |
| Logitech                         | 7         | 0.82%   |
| C-Media Electronics              | 5         | 0.58%   |
| Silicon Integrated Systems [SiS] | 4         | 0.47%   |
| JMTek                            | 4         | 0.47%   |
| Generalplus Technology           | 3         | 0.35%   |
| Creative Technology              | 3         | 0.35%   |
| Microsoft                        | 2         | 0.23%   |
| Lenovo                           | 2         | 0.23%   |
| Kingston Technology              | 2         | 0.23%   |
| Focusrite-Novation               | 2         | 0.23%   |
| Texas Instruments                | 1         | 0.12%   |
| Shenzhen Riitek Technology       | 1         | 0.12%   |
| Realtek Semiconductor            | 1         | 0.12%   |
| Plantronics                      | 1         | 0.12%   |
| Pixart Imaging                   | 1         | 0.12%   |
| Medeli Electronics               | 1         | 0.12%   |
| Huawei Technologies              | 1         | 0.12%   |
| ESS Technology                   | 1         | 0.12%   |
| DigiTech                         | 1         | 0.12%   |
| CMX Systems                      | 1         | 0.12%   |
| Apple                            | 1         | 0.12%   |
| Unknown                          | 1         | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 107       | 10.12%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 80        | 7.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 53        | 5.01%   |
| AMD FCH Azalia Controller                                                                         | 45        | 4.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 36        | 3.41%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 36        | 3.41%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 31        | 2.93%   |
| AMD Kabini HDMI/DP Audio                                                                          | 31        | 2.93%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 30        | 2.84%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 26        | 2.46%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 26        | 2.46%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 25        | 2.37%   |
| Intel 8 Series HD Audio Controller                                                                | 25        | 2.37%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 24        | 2.27%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 23        | 2.18%   |
| Intel Cannon Lake PCH cAVS                                                                        | 21        | 1.99%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 20        | 1.89%   |
| Intel Broadwell-U Audio Controller                                                                | 20        | 1.89%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 18        | 1.7%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 17        | 1.61%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 17        | 1.61%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 16        | 1.51%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 16        | 1.51%   |
| Intel Comet Lake PCH cAVS                                                                         | 16        | 1.51%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 16        | 1.51%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 16        | 1.51%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 16        | 1.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 13        | 1.23%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 13        | 1.23%   |
| Intel CM238 HD Audio Controller                                                                   | 13        | 1.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 13        | 1.23%   |
| AMD High Definition Audio Controller                                                              | 11        | 1.04%   |
| AMD Wrestler HDMI Audio                                                                           | 10        | 0.95%   |
| AMD Trinity HDMI Audio Controller                                                                 | 10        | 0.95%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 8         | 0.76%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 8         | 0.76%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 8         | 0.76%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 8         | 0.76%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 7         | 0.66%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 7         | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 136       | 29%     |
| SK hynix            | 103       | 21.96%  |
| Micron Technology   | 63        | 13.43%  |
| Crucial             | 46        | 9.81%   |
| Kingston            | 45        | 9.59%   |
| Ramaxel Technology  | 22        | 4.69%   |
| Unknown             | 17        | 3.62%   |
| A-DATA Technology   | 7         | 1.49%   |
| Avant               | 5         | 1.07%   |
| Unknown (ABCD)      | 3         | 0.64%   |
| G.Skill             | 3         | 0.64%   |
| Corsair             | 3         | 0.64%   |
| Nanya Technology    | 2         | 0.43%   |
| Elpida              | 2         | 0.43%   |
| Unknown             | 2         | 0.43%   |
| Unknown (0x0E9D)    | 1         | 0.21%   |
| Unknown (0BF7)      | 1         | 0.21%   |
| Unknown (090E)      | 1         | 0.21%   |
| Unknown (08C8)      | 1         | 0.21%   |
| Smart               | 1         | 0.21%   |
| PNY                 | 1         | 0.21%   |
| Lexar               | 1         | 0.21%   |
| Kllisre             | 1         | 0.21%   |
| ASint Technology    | 1         | 0.21%   |
| 48spaces            | 1         | 0.21%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 11        | 2.26%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 1.85%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 9         | 1.85%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 1.44%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 7         | 1.44%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 6         | 1.23%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 6         | 1.23%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 1.23%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 1.23%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 6         | 1.23%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 6         | 1.23%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 1.03%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 5         | 1.03%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 1.03%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 4         | 0.82%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 4         | 0.82%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.82%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.82%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.82%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 4         | 0.82%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 4         | 0.82%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 4         | 0.82%   |
| Micron RAM 8KTF51264HZ-1G6N1 4096MB SODIMM DDR3 1600MT/s         | 4         | 0.82%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s            | 4         | 0.82%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 4         | 0.82%   |
| Crucial RAM CT8G4SFRA32A.M4FF 8GB SODIMM DDR4 3200MT/s           | 4         | 0.82%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 4         | 0.82%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 0.62%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.62%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.62%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 3         | 0.62%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 3         | 0.62%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 3         | 0.62%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 0.62%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.62%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 3         | 0.62%   |
| Samsung RAM K4U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s     | 3         | 0.62%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 3         | 0.62%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 3         | 0.62%   |
| Crucial RAM CT8G4SFRA32A.M8FRS 8GB SODIMM DDR4 3200MT/s          | 3         | 0.62%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 191       | 53.65%  |
| DDR3   | 113       | 31.74%  |
| LPDDR4 | 21        | 5.9%    |
| LPDDR3 | 12        | 3.37%   |
| DDR2   | 9         | 2.53%   |
| SDRAM  | 7         | 1.97%   |
| RAM    | 1         | 0.28%   |
| DDR5   | 1         | 0.28%   |
| DDR    | 1         | 0.28%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 317       | 89.8%   |
| Row Of Chips | 33        | 9.35%   |
| DIMM         | 1         | 0.28%   |
| Chip         | 1         | 0.28%   |
| Unknown      | 1         | 0.28%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 168       | 41.48%  |
| 4096  | 146       | 36.05%  |
| 16384 | 45        | 11.11%  |
| 2048  | 33        | 8.15%   |
| 32768 | 8         | 1.98%   |
| 1024  | 4         | 0.99%   |
| 64    | 1         | 0.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 88        | 21.67%  |
| 1600    | 87        | 21.43%  |
| 3200    | 84        | 20.69%  |
| 2400    | 39        | 9.61%   |
| 2133    | 23        | 5.67%   |
| 1334    | 16        | 3.94%   |
| 4267    | 11        | 2.71%   |
| 3266    | 11        | 2.71%   |
| 1333    | 9         | 2.22%   |
| Unknown | 8         | 1.97%   |
| 667     | 7         | 1.72%   |
| 800     | 4         | 0.99%   |
| 4266    | 3         | 0.74%   |
| 4199    | 3         | 0.74%   |
| 1867    | 3         | 0.74%   |
| 2048    | 2         | 0.49%   |
| 1067    | 2         | 0.49%   |
| 975     | 2         | 0.49%   |
| 8400    | 1         | 0.25%   |
| 4800    | 1         | 0.25%   |
| 933     | 1         | 0.25%   |
| 533     | 1         | 0.25%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Brother Industries | 3         | 37.5%   |
| Canon              | 2         | 25%     |
| Seiko Epson        | 1         | 12.5%   |
| PM                 | 1         | 12.5%   |
| Hewlett-Packard    | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon MF110/910 Series  | 2         | 25%     |
| Brother DCP-1600        | 2         | 25%     |
| Seiko Epson L355 Series | 1         | 12.5%   |
| PM PM241-BT             | 1         | 12.5%   |
| HP DeskJet 5820 series  | 1         | 12.5%   |
| Brother HL-1200 series  | 1         | 12.5%   |

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
| Chicony Electronics                    | 167       | 23.89%  |
| IMC Networks                           | 94        | 13.45%  |
| Realtek Semiconductor                  | 54        | 7.73%   |
| Microdia                               | 46        | 6.58%   |
| Quanta                                 | 43        | 6.15%   |
| Cheng Uei Precision Industry (Foxlink) | 41        | 5.87%   |
| Sunplus Innovation Technology          | 36        | 5.15%   |
| Bison Electronics                      | 34        | 4.86%   |
| Suyin                                  | 25        | 3.58%   |
| Lite-On Technology                     | 23        | 3.29%   |
| Silicon Motion                         | 20        | 2.86%   |
| Luxvisions Innotech Limited            | 15        | 2.15%   |
| Syntek                                 | 11        | 1.57%   |
| Acer                                   | 9         | 1.29%   |
| Logitech                               | 8         | 1.14%   |
| Apple                                  | 8         | 1.14%   |
| Ricoh                                  | 6         | 0.86%   |
| Z-Star Microelectronics                | 5         | 0.72%   |
| Sonix Technology                       | 4         | 0.57%   |
| Samsung Electronics                    | 4         | 0.57%   |
| Importek                               | 4         | 0.57%   |
| Alcor Micro                            | 4         | 0.57%   |
| USB Camera CS                          | 3         | 0.43%   |
| SunplusIT                              | 3         | 0.43%   |
| Lenovo                                 | 3         | 0.43%   |
| YGTek                                  | 2         | 0.29%   |
| Shinetech                              | 2         | 0.29%   |
| Microsoft                              | 2         | 0.29%   |
| Leap Motion                            | 2         | 0.29%   |
| KYE Systems (Mouse Systems)            | 2         | 0.29%   |
| Generalplus Technology                 | 2         | 0.29%   |
| GEMBIRD                                | 2         | 0.29%   |
| Foxconn / Hon Hai                      | 2         | 0.29%   |
| DigiTech                               | 2         | 0.29%   |
| ALi                                    | 2         | 0.29%   |
| Sunplus Technology                     | 1         | 0.14%   |
| SHENZHEN EMEET TECHNOLOGY              | 1         | 0.14%   |
| Ruision                                | 1         | 0.14%   |
| OmniVision Technologies                | 1         | 0.14%   |
| Jieli Technology                       | 1         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                               | 37        | 5.28%   |
| Chicony Integrated Camera                                       | 24        | 3.42%   |
| IMC Networks Integrated Camera                                  | 23        | 3.28%   |
| Chicony HD WebCam                                               | 17        | 2.43%   |
| Realtek Integrated_Webcam_HD                                    | 12        | 1.71%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 12        | 1.71%   |
| Bison Integrated Camera                                         | 12        | 1.71%   |
| Microdia Integrated_Webcam_HD                                   | 11        | 1.57%   |
| Chicony HP Wide Vision HD Camera                                | 10        | 1.43%   |
| Chicony HP Truevision HD camera                                 | 10        | 1.43%   |
| Realtek HP Truevision HD                                        | 9         | 1.28%   |
| Quanta HP TrueVision HD Camera                                  | 9         | 1.28%   |
| Lite-On Integrated Camera                                       | 9         | 1.28%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 9         | 1.28%   |
| Chicony EasyCamera                                              | 9         | 1.28%   |
| Suyin HP Truevision HD                                          | 8         | 1.14%   |
| Sunplus Integrated_Webcam_HD                                    | 8         | 1.14%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 8         | 1.14%   |
| Bison EasyCamera                                                | 8         | 1.14%   |
| Sunplus HP TrueVision HD Camera                                 | 7         | 1%      |
| Quanta HD User Facing                                           | 7         | 1%      |
| Chicony VGA WebCam                                              | 7         | 1%      |
| Chicony HP Webcam                                               | 7         | 1%      |
| Chicony HP TrueVision HD                                        | 7         | 1%      |
| Chicony HD User Facing                                          | 7         | 1%      |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD         | 7         | 1%      |
| Realtek USB Camera                                              | 6         | 0.86%   |
| Microdia Webcam Vitade AF                                       | 6         | 0.86%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 6         | 0.86%   |
| Syntek Integrated Camera                                        | 5         | 0.71%   |
| Silicon Motion WebCam SCB-1100N                                 | 5         | 0.71%   |
| Quanta VGA WebCam                                               | 5         | 0.71%   |
| Quanta USB2.0 HD UVC WebCam                                     | 5         | 0.71%   |
| Microdia HP Webcam                                              | 5         | 0.71%   |
| Lite-On HP Wide Vision HD Camera                                | 5         | 0.71%   |
| IMC Networks ov9734_azurewave_camera                            | 5         | 0.71%   |
| Chicony HP HD Camera                                            | 5         | 0.71%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 5         | 0.71%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                | 5         | 0.71%   |
| Sunplus Laptop Integrated WebCam HD                             | 4         | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 45        | 39.13%  |
| Synaptics                  | 25        | 21.74%  |
| Shenzhen Goodix Technology | 15        | 13.04%  |
| Elan Microelectronics      | 9         | 7.83%   |
| AuthenTec                  | 7         | 6.09%   |
| Upek                       | 6         | 5.22%   |
| LighTuning Technology      | 4         | 3.48%   |
| STMicroelectronics         | 2         | 1.74%   |
| Focal-systems.Corp         | 2         | 1.74%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors Swipe Fingerprint Sensor                                  | 11        | 9.57%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 10        | 8.7%    |
| Shenzhen Goodix  Fingerprint Device                                        | 8         | 6.96%   |
| Elan ELAN:ARM-M4                                                           | 8         | 6.96%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 7         | 6.09%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 7         | 6.09%   |
| Shenzhen Goodix Fingerprint Reader                                         | 7         | 6.09%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 5.22%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 5.22%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 4.35%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 4.35%   |
| AuthenTec AES2810                                                          | 4         | 3.48%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 2.61%   |
| Synaptics  WBDI                                                            | 3         | 2.61%   |
| Synaptics Fingerprint reader [HP G6]                                       | 3         | 2.61%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 2.61%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.74%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.74%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 1.74%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 2         | 1.74%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.87%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 0.87%   |
| Validity Sensors VFS491                                                    | 1         | 0.87%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.87%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.87%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.87%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.87%   |
| Elan ELAN:Fingerprint                                                      | 1         | 0.87%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.87%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.87%   |
| AuthenTec AES1600                                                          | 1         | 0.87%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 16        | 80%     |
| Upek     | 2         | 10%     |
| O2 Micro | 2         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 30%     |
| Broadcom 5880                                                                | 6         | 30%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 15%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 10%     |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 5%      |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 5%      |
| Broadcom 58200                                                               | 1         | 5%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 502       | 66.84%  |
| 1     | 211       | 28.1%   |
| 2     | 35        | 4.66%   |
| 5     | 1         | 0.13%   |
| 4     | 1         | 0.13%   |
| 3     | 1         | 0.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 115       | 40.78%  |
| Graphics card            | 55        | 19.5%   |
| Net/wireless             | 38        | 13.48%  |
| Chipcard                 | 19        | 6.74%   |
| Multimedia controller    | 18        | 6.38%   |
| Bluetooth                | 14        | 4.96%   |
| Camera                   | 8         | 2.84%   |
| Storage                  | 4         | 1.42%   |
| Communication controller | 4         | 1.42%   |
| Sound                    | 2         | 0.71%   |
| Net/ethernet             | 2         | 0.71%   |
| Card reader              | 2         | 0.71%   |
| Network                  | 1         | 0.35%   |


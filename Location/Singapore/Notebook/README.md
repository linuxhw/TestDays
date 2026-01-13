Linux in Singapore - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Singapore.

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

Total: 558

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [82d2fd0c20](https://linux-hardware.org/?probe=82d2fd0c20) | Jan 01, 2026 |
| MSI           | Katana A15 AI B8VG          | [53c3c4ab7d](https://linux-hardware.org/?probe=53c3c4ab7d) | Dec 14, 2025 |
| Acer          | Aspire Lite AL15-41         | [f4321d657c](https://linux-hardware.org/?probe=f4321d657c) | Dec 06, 2025 |
| HUAWEI        | CREFG-XX                    | [95a826dd0c](https://linux-hardware.org/?probe=95a826dd0c) | Dec 02, 2025 |
| Lenovo        | Legion Pro 5 16IAX10 83F... | [270f276458](https://linux-hardware.org/?probe=270f276458) | Nov 28, 2025 |
| Valve         | Jupiter                     | [354d0a239b](https://linux-hardware.org/?probe=354d0a239b) | Nov 23, 2025 |
| MECHREVO      | Kuangshi16Pro Series GM6... | [f565e1c8a5](https://linux-hardware.org/?probe=f565e1c8a5) | Nov 22, 2025 |
| MECHREVO      | Kuangshi16Pro Series GM6... | [43ad04787d](https://linux-hardware.org/?probe=43ad04787d) | Nov 22, 2025 |
| Dell          | Latitude 7400               | [b93d333b65](https://linux-hardware.org/?probe=b93d333b65) | Nov 15, 2025 |
| Lenovo        | ThinkPad X220 42911H8       | [59b15b58af](https://linux-hardware.org/?probe=59b15b58af) | Nov 15, 2025 |
| Lenovo        | ThinkBook 14 G6+ IMH 21L... | [91bd2a79f9](https://linux-hardware.org/?probe=91bd2a79f9) | Nov 03, 2025 |
| Acer          | Aspire A315-44P             | [a9668be042](https://linux-hardware.org/?probe=a9668be042) | Oct 29, 2025 |
| Lenovo        | ThinkPad X220 42911H8       | [631287d616](https://linux-hardware.org/?probe=631287d616) | Oct 20, 2025 |
| Acer          | Nitro AN515-45              | [e4d5bda0b7](https://linux-hardware.org/?probe=e4d5bda0b7) | Oct 11, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [2a8acd5a5d](https://linux-hardware.org/?probe=2a8acd5a5d) | Oct 11, 2025 |
| ASUSTek       | N550JV                      | [bfcee0d61e](https://linux-hardware.org/?probe=bfcee0d61e) | Sep 25, 2025 |
| ASUSTek       | ASUS Vivobook 16 Flip TP... | [5a83a66546](https://linux-hardware.org/?probe=5a83a66546) | Sep 25, 2025 |
| ASUSTek       | ASUS Zenbook A14 UX3407Q... | [a55979576d](https://linux-hardware.org/?probe=a55979576d) | Sep 24, 2025 |
| HONOR         | BRN-HXXB                    | [6048741e72](https://linux-hardware.org/?probe=6048741e72) | Sep 20, 2025 |
| HP            | OMEN Laptop 15-en1xxx       | [f54a9e39f6](https://linux-hardware.org/?probe=f54a9e39f6) | Sep 20, 2025 |
| THUNDEROBO... | R15                         | [a91ea93a17](https://linux-hardware.org/?probe=a91ea93a17) | Sep 08, 2025 |
| HP            | Laptop 14s-dk0xxx           | [00954b7622](https://linux-hardware.org/?probe=00954b7622) | Sep 07, 2025 |
| ASUSTek       | ASUS Vivobook 16 Flip TP... | [7c3dc7a3b4](https://linux-hardware.org/?probe=7c3dc7a3b4) | Sep 06, 2025 |
| Lenovo        | ThinkPad X220 42911H8       | [c3ced04be1](https://linux-hardware.org/?probe=c3ced04be1) | Sep 03, 2025 |
| Lenovo        | Legion Y9000P IAH7H 82RF    | [5bd8945ba5](https://linux-hardware.org/?probe=5bd8945ba5) | Sep 01, 2025 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [4769d68eb5](https://linux-hardware.org/?probe=4769d68eb5) | Aug 27, 2025 |
| Lenovo        | ThinkPad X220 42911H8       | [62f453fdb6](https://linux-hardware.org/?probe=62f453fdb6) | Aug 27, 2025 |
| WOOKING       | X16                         | [edbe7497ae](https://linux-hardware.org/?probe=edbe7497ae) | Aug 24, 2025 |
| Lenovo        | ThinkPad X220 42911H8       | [97891b5acf](https://linux-hardware.org/?probe=97891b5acf) | Aug 22, 2025 |
| Dell          | Latitude 7400               | [562f46fb8a](https://linux-hardware.org/?probe=562f46fb8a) | Aug 16, 2025 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [0fe7888038](https://linux-hardware.org/?probe=0fe7888038) | Aug 15, 2025 |
| MECHREVO      | WUJIE16 Pro                 | [6401631b8a](https://linux-hardware.org/?probe=6401631b8a) | Aug 14, 2025 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [c783366591](https://linux-hardware.org/?probe=c783366591) | Aug 11, 2025 |
| ASUSTek       | ROG Strix G733QS_G743QS     | [5d2ee9ae49](https://linux-hardware.org/?probe=5d2ee9ae49) | Aug 09, 2025 |
| Fujitsu       | LIFEBOOK LH531              | [198ae80d52](https://linux-hardware.org/?probe=198ae80d52) | Aug 07, 2025 |
| Lenovo        | Legion Y7000P IRH8 82YA     | [2ef145f349](https://linux-hardware.org/?probe=2ef145f349) | Aug 01, 2025 |
| ASUSTek       | ROG Zephyrus G14 GA403UM... | [47a368e3fb](https://linux-hardware.org/?probe=47a368e3fb) | Jul 26, 2025 |
| Fujitsu       | LIFEBOOK LH531              | [52b147e2c8](https://linux-hardware.org/?probe=52b147e2c8) | Jul 22, 2025 |
| Acer          | Swift SF314-55G             | [50f41d2328](https://linux-hardware.org/?probe=50f41d2328) | Jul 15, 2025 |
| Lenovo        | Legion 7 16IRX9 83FD        | [9b129b43ab](https://linux-hardware.org/?probe=9b129b43ab) | Jul 12, 2025 |
| HP            | EliteBook 845 G8 Noteboo... | [d7c9a1a7e5](https://linux-hardware.org/?probe=d7c9a1a7e5) | Jul 10, 2025 |
| Lenovo        | IdeaPad Y470 20090          | [f01761db84](https://linux-hardware.org/?probe=f01761db84) | Jul 09, 2025 |
| ASUSTek       | G750JS                      | [c9f6e8cc2b](https://linux-hardware.org/?probe=c9f6e8cc2b) | Jul 06, 2025 |
| Razer         | Blade Stealth 13 Late 20... | [7e3d59a1f8](https://linux-hardware.org/?probe=7e3d59a1f8) | Jul 03, 2025 |
| Apple         | MacBookPro9,2               | [8838ee75f4](https://linux-hardware.org/?probe=8838ee75f4) | Jun 25, 2025 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [d121557ba3](https://linux-hardware.org/?probe=d121557ba3) | Jun 21, 2025 |
| Google        | Boten                       | [00f3c03db4](https://linux-hardware.org/?probe=00f3c03db4) | Jun 18, 2025 |
| Lenovo        | IdeaPad Slim 3 15IAH8 83... | [7a23ccc76f](https://linux-hardware.org/?probe=7a23ccc76f) | Jun 11, 2025 |
| LG Electro... | 14Z90T-G.AA75A3             | [4ee698412e](https://linux-hardware.org/?probe=4ee698412e) | Jun 08, 2025 |
| LG Electro... | 14Z90T-G.AA75A3             | [374a79ff66](https://linux-hardware.org/?probe=374a79ff66) | Jun 08, 2025 |
| Fujitsu       | LIFEBOOK UH572              | [85dd4a730e](https://linux-hardware.org/?probe=85dd4a730e) | Jun 07, 2025 |
| Lenovo        | ThinkPad T15p Gen 1 20TN... | [5467fa9574](https://linux-hardware.org/?probe=5467fa9574) | Jun 03, 2025 |
| Apple         | MacBookAir7,2               | [5dfae8be32](https://linux-hardware.org/?probe=5dfae8be32) | Jun 02, 2025 |
| Apple         | MacBookAir7,2               | [7d8cedc1c0](https://linux-hardware.org/?probe=7d8cedc1c0) | Jun 01, 2025 |
| Dell          | Latitude 7400               | [14c09b60ca](https://linux-hardware.org/?probe=14c09b60ca) | May 30, 2025 |
| Lenovo        | ThinkPad X220 42911H8       | [545128fab2](https://linux-hardware.org/?probe=545128fab2) | May 29, 2025 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [0ae8ab1f35](https://linux-hardware.org/?probe=0ae8ab1f35) | May 17, 2025 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [1402af7b9a](https://linux-hardware.org/?probe=1402af7b9a) | May 14, 2025 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [264e5c94a8](https://linux-hardware.org/?probe=264e5c94a8) | May 14, 2025 |
| MECHREVO      | WUJIE15XA                   | [567d285f72](https://linux-hardware.org/?probe=567d285f72) | Apr 26, 2025 |
| Lenovo        | ThinkPad P53 20QQS3S203     | [620177f55f](https://linux-hardware.org/?probe=620177f55f) | Apr 16, 2025 |
| HP            | Notebook                    | [06ec3d5100](https://linux-hardware.org/?probe=06ec3d5100) | Apr 15, 2025 |
| HP            | Notebook                    | [e0fce6b4b1](https://linux-hardware.org/?probe=e0fce6b4b1) | Apr 15, 2025 |
| Lenovo        | ThinkPad P53 20QQS3S203     | [34f4fb7a1a](https://linux-hardware.org/?probe=34f4fb7a1a) | Apr 09, 2025 |
| Valve         | Jupiter                     | [25c21d31f3](https://linux-hardware.org/?probe=25c21d31f3) | Apr 08, 2025 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [a95a884bb3](https://linux-hardware.org/?probe=a95a884bb3) | Apr 08, 2025 |
| Apple         | MacBookPro9,2               | [80a36f67d0](https://linux-hardware.org/?probe=80a36f67d0) | Apr 08, 2025 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [85c7a57800](https://linux-hardware.org/?probe=85c7a57800) | Apr 06, 2025 |
| Apple         | MacBookPro9,2               | [dcc7a8a7e3](https://linux-hardware.org/?probe=dcc7a8a7e3) | Apr 03, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [1d8b7de3da](https://linux-hardware.org/?probe=1d8b7de3da) | Mar 29, 2025 |
| Dell          | Latitude 7400               | [dd5d8cb466](https://linux-hardware.org/?probe=dd5d8cb466) | Mar 23, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop N740... | [7b729b2486](https://linux-hardware.org/?probe=7b729b2486) | Mar 17, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop N740... | [b8fcd27f01](https://linux-hardware.org/?probe=b8fcd27f01) | Mar 15, 2025 |
| Apple         | MacBookPro9,2               | [154ba9b6a0](https://linux-hardware.org/?probe=154ba9b6a0) | Mar 15, 2025 |
| Acer          | Aspire A515-45              | [85d75ee082](https://linux-hardware.org/?probe=85d75ee082) | Mar 15, 2025 |
| HP            | OMEN by Gaming Laptop 16... | [3da405d1c9](https://linux-hardware.org/?probe=3da405d1c9) | Mar 12, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop N740... | [6f8ddbc848](https://linux-hardware.org/?probe=6f8ddbc848) | Mar 05, 2025 |
| Lenovo        | ThinkPad X220 42911H8       | [e2c17e27fe](https://linux-hardware.org/?probe=e2c17e27fe) | Mar 04, 2025 |
| Lenovo        | ThinkPad X220 42911H8       | [cdd809f5d6](https://linux-hardware.org/?probe=cdd809f5d6) | Mar 04, 2025 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [fdbeafd077](https://linux-hardware.org/?probe=fdbeafd077) | Mar 02, 2025 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | [f641098bdf](https://linux-hardware.org/?probe=f641098bdf) | Feb 25, 2025 |
| Lenovo        | ThinkPad X220 42911H8       | [90452a90ad](https://linux-hardware.org/?probe=90452a90ad) | Feb 25, 2025 |
| ASUSTek       | ASUS Zenbook S 14 UX5406... | [1ee11db1ac](https://linux-hardware.org/?probe=1ee11db1ac) | Feb 24, 2025 |
| Apple         | MacBookAir6,1               | [18b8daa00d](https://linux-hardware.org/?probe=18b8daa00d) | Feb 20, 2025 |
| Valve         | Jupiter                     | [1182c1cc7a](https://linux-hardware.org/?probe=1182c1cc7a) | Feb 17, 2025 |
| Apple         | MacBookPro9,2               | [ee85cb0515](https://linux-hardware.org/?probe=ee85cb0515) | Feb 14, 2025 |
| ASUSTek       | ROG Strix G16 G634JZR_G6... | [601b7ffd39](https://linux-hardware.org/?probe=601b7ffd39) | Feb 13, 2025 |
| ASUSTek       | X450LD                      | [5936a3e6c7](https://linux-hardware.org/?probe=5936a3e6c7) | Feb 12, 2025 |
| Lenovo        | Legion 5 15ARH05 82B5       | [24dd6dfb6f](https://linux-hardware.org/?probe=24dd6dfb6f) | Feb 08, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [9f1f9f96db](https://linux-hardware.org/?probe=9f1f9f96db) | Feb 08, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [3e869fe7fc](https://linux-hardware.org/?probe=3e869fe7fc) | Feb 07, 2025 |
| Apple         | MacBookPro9,2               | [6234399034](https://linux-hardware.org/?probe=6234399034) | Jan 28, 2025 |
| HUAWEI        | VGHH-XX                     | [2e8fd355ef](https://linux-hardware.org/?probe=2e8fd355ef) | Jan 20, 2025 |
| Lenovo        | ThinkBook 16 G5+ APO 21J... | [f6ec2ac2ee](https://linux-hardware.org/?probe=f6ec2ac2ee) | Jan 18, 2025 |
| Apple         | MacBookPro9,2               | [20133702e9](https://linux-hardware.org/?probe=20133702e9) | Jan 11, 2025 |
| Acer          | Swift SFG14-73              | [b3191e5474](https://linux-hardware.org/?probe=b3191e5474) | Jan 10, 2025 |
| Apple         | MacBookPro9,2               | [319272bf03](https://linux-hardware.org/?probe=319272bf03) | Jan 01, 2025 |
| Apple         | MacBookPro9,2               | [c7b700cc18](https://linux-hardware.org/?probe=c7b700cc18) | Dec 26, 2024 |
| Dell          | Inspiron 1525               | [cd4f5695b9](https://linux-hardware.org/?probe=cd4f5695b9) | Dec 22, 2024 |
| ASUSTek       | ASUS Zenbook S 14 UX5406... | [78598d0f36](https://linux-hardware.org/?probe=78598d0f36) | Dec 21, 2024 |
| Dell          | Latitude E6500              | [f173d0af82](https://linux-hardware.org/?probe=f173d0af82) | Dec 19, 2024 |
| Apple         | MacBookPro9,2               | [ac5dad0554](https://linux-hardware.org/?probe=ac5dad0554) | Dec 15, 2024 |
| MECHREVO      | WUJIE14XA                   | [cb76a6f8c5](https://linux-hardware.org/?probe=cb76a6f8c5) | Dec 13, 2024 |
| HP            | Pavilion Laptop 15-cc1xx    | [8f790073ab](https://linux-hardware.org/?probe=8f790073ab) | Dec 07, 2024 |
| Dell          | Latitude E6440              | [595f6a32d7](https://linux-hardware.org/?probe=595f6a32d7) | Dec 04, 2024 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [ded958606e](https://linux-hardware.org/?probe=ded958606e) | Dec 02, 2024 |
| Apple         | MacBookPro14,1              | [c725b25dfc](https://linux-hardware.org/?probe=c725b25dfc) | Nov 11, 2024 |
| Lenovo        | ThinkPad X220 42911H8       | [89f9b8697e](https://linux-hardware.org/?probe=89f9b8697e) | Oct 29, 2024 |
| ASUSTek       | ASUS Zenbook S 16 UM5606... | [50608db984](https://linux-hardware.org/?probe=50608db984) | Oct 23, 2024 |
| Dell          | Latitude E6440              | [8755de9d32](https://linux-hardware.org/?probe=8755de9d32) | Oct 17, 2024 |
| Dell          | Latitude E6440              | [a632b6e574](https://linux-hardware.org/?probe=a632b6e574) | Oct 14, 2024 |
| Lenovo        | ThinkPad X220 42911H8       | [32eb262404](https://linux-hardware.org/?probe=32eb262404) | Oct 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [57602cd2d9](https://linux-hardware.org/?probe=57602cd2d9) | Oct 04, 2024 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [010be6e7fb](https://linux-hardware.org/?probe=010be6e7fb) | Sep 30, 2024 |
| Alienware     | m18 R2                      | [51332eaf8a](https://linux-hardware.org/?probe=51332eaf8a) | Sep 27, 2024 |
| MicroByte     | ezbook                      | [5b878e7b72](https://linux-hardware.org/?probe=5b878e7b72) | Sep 24, 2024 |
| MicroByte     | ezbook                      | [79104622de](https://linux-hardware.org/?probe=79104622de) | Sep 24, 2024 |
| Acer          | Swift SF314-57G             | [4becd67ee7](https://linux-hardware.org/?probe=4becd67ee7) | Sep 21, 2024 |
| Lenovo        | G40-45 80E1                 | [5e7135c91f](https://linux-hardware.org/?probe=5e7135c91f) | Sep 16, 2024 |
| Lenovo        | ThinkPad X220 42911H8       | [5b6c362951](https://linux-hardware.org/?probe=5b6c362951) | Sep 09, 2024 |
| Lenovo        | ThinkPad X220 42911H8       | [a13cb84209](https://linux-hardware.org/?probe=a13cb84209) | Sep 04, 2024 |
| Lenovo        | Legion S7 16IAH7 82TF       | [615190ebfe](https://linux-hardware.org/?probe=615190ebfe) | Sep 03, 2024 |
| Lenovo        | Legion S7 16IAH7 82TF       | [f846cf875c](https://linux-hardware.org/?probe=f846cf875c) | Sep 02, 2024 |
| HUAWEI        | MACHD-WXX9                  | [87961c091a](https://linux-hardware.org/?probe=87961c091a) | Aug 15, 2024 |
| Lenovo        | ThinkPad X220 42911H8       | [e3308aee33](https://linux-hardware.org/?probe=e3308aee33) | Aug 11, 2024 |
| Dell          | Latitude 7400               | [5a1203ee67](https://linux-hardware.org/?probe=5a1203ee67) | Aug 11, 2024 |
| Lenovo        | ThinkPad X220 42911H8       | [5fd9dd8b45](https://linux-hardware.org/?probe=5fd9dd8b45) | Aug 10, 2024 |
| Lenovo        | ThinkPad X220 42911H8       | [48b67b8342](https://linux-hardware.org/?probe=48b67b8342) | Aug 10, 2024 |
| Unknown       | Alder Lake N                | [c1fc9502d2](https://linux-hardware.org/?probe=c1fc9502d2) | Aug 03, 2024 |
| Unknown       | Alder Lake N                | [827d3a9aad](https://linux-hardware.org/?probe=827d3a9aad) | Aug 03, 2024 |
| Apple         | MacBookPro11,5              | [9167682d99](https://linux-hardware.org/?probe=9167682d99) | Aug 01, 2024 |
| Dell          | Latitude 3320               | [7eb3fdd1da](https://linux-hardware.org/?probe=7eb3fdd1da) | Jun 24, 2024 |
| Dell          | Latitude 3320               | [c5072f72e6](https://linux-hardware.org/?probe=c5072f72e6) | Jun 20, 2024 |
| Lenovo        | IdeaPad Slim 5 16AHP9 83... | [dbb3d92cc6](https://linux-hardware.org/?probe=dbb3d92cc6) | Jun 17, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [d3a402bdca](https://linux-hardware.org/?probe=d3a402bdca) | Jun 12, 2024 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | [30840e7e74](https://linux-hardware.org/?probe=30840e7e74) | Jun 11, 2024 |
| ASUSTek       | ZenBook UX481FLY_UX481FL    | [7d0530d329](https://linux-hardware.org/?probe=7d0530d329) | Jun 07, 2024 |
| Chuwi         | MiniBook X                  | [2bc0868e88](https://linux-hardware.org/?probe=2bc0868e88) | May 26, 2024 |
| Dell          | Latitude 7400               | [ede288f63c](https://linux-hardware.org/?probe=ede288f63c) | May 26, 2024 |
| HUAWEI        | MACHD-WXX9                  | [53c26896f2](https://linux-hardware.org/?probe=53c26896f2) | May 25, 2024 |
| MECHREVO      | WUJIE14 PRO                 | [5eef345507](https://linux-hardware.org/?probe=5eef345507) | May 24, 2024 |
| Lenovo        | ThinkPad X220 42911H8       | [b957b23e2d](https://linux-hardware.org/?probe=b957b23e2d) | May 21, 2024 |
| Lenovo        | ThinkPad X220 42911H8       | [bd0c6454d1](https://linux-hardware.org/?probe=bd0c6454d1) | May 21, 2024 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [6a7d29fe24](https://linux-hardware.org/?probe=6a7d29fe24) | Apr 15, 2024 |
| Valve         | Jupiter                     | [1cd9cc4807](https://linux-hardware.org/?probe=1cd9cc4807) | Apr 07, 2024 |
| Lenovo        | ThinkPad X220 42911H8       | [927e58d8ee](https://linux-hardware.org/?probe=927e58d8ee) | Mar 31, 2024 |
| Dell          | Latitude 7400               | [19bc09a2fb](https://linux-hardware.org/?probe=19bc09a2fb) | Mar 31, 2024 |
| Lenovo        | Yoga Pro 7 14IRH8 82Y7      | [3cf788c2ee](https://linux-hardware.org/?probe=3cf788c2ee) | Mar 24, 2024 |
| Dell          | Latitude 7400               | [6cc8d0a55c](https://linux-hardware.org/?probe=6cc8d0a55c) | Mar 01, 2024 |
| Lenovo        | ThinkPad X220 42911H8       | [d9a64479f5](https://linux-hardware.org/?probe=d9a64479f5) | Mar 01, 2024 |
| Lenovo        | ThinkPad X220 42911H8       | [c91afbe38c](https://linux-hardware.org/?probe=c91afbe38c) | Mar 01, 2024 |
| Valve         | Jupiter                     | [fc900c86f1](https://linux-hardware.org/?probe=fc900c86f1) | Feb 18, 2024 |
| Acer          | Aspire 4750                 | [bc24c666de](https://linux-hardware.org/?probe=bc24c666de) | Feb 16, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [5eb2b65d31](https://linux-hardware.org/?probe=5eb2b65d31) | Feb 13, 2024 |
| Lenovo        | ThinkPad X230 23256N6       | [6f6d39cf77](https://linux-hardware.org/?probe=6f6d39cf77) | Feb 12, 2024 |
| Dell          | Latitude E7250              | [24ea631399](https://linux-hardware.org/?probe=24ea631399) | Jan 31, 2024 |
| Lenovo        | ThinkPad X220 42911H8       | [2ab9e19a09](https://linux-hardware.org/?probe=2ab9e19a09) | Jan 22, 2024 |
| MECHREVO      | WUJIE 14                    | [70a728ef39](https://linux-hardware.org/?probe=70a728ef39) | Jan 17, 2024 |
| System76      | Oryx Pro                    | [db771e1a08](https://linux-hardware.org/?probe=db771e1a08) | Jan 16, 2024 |
| Lenovo        | ThinkPad X220 42911H8       | [65ec7304a9](https://linux-hardware.org/?probe=65ec7304a9) | Jan 09, 2024 |
| HUAWEI        | CREM-WXX9                   | [29104c358b](https://linux-hardware.org/?probe=29104c358b) | Jan 07, 2024 |
| MECHREVO      | JiguangE Series GM5AR0E     | [dcaf044fe4](https://linux-hardware.org/?probe=dcaf044fe4) | Jan 05, 2024 |
| Apple         | MacBookPro11,5              | [4987fb1cb9](https://linux-hardware.org/?probe=4987fb1cb9) | Dec 30, 2023 |
| Lenovo        | Legion Y7000 81FW           | [f67367aa62](https://linux-hardware.org/?probe=f67367aa62) | Dec 23, 2023 |
| Dell          | Latitude 5440               | [bd5e743ebb](https://linux-hardware.org/?probe=bd5e743ebb) | Dec 21, 2023 |
| Valve         | Jupiter                     | [b746c80979](https://linux-hardware.org/?probe=b746c80979) | Dec 13, 2023 |
| ASUSTek       | X202E                       | [3d45a17e7f](https://linux-hardware.org/?probe=3d45a17e7f) | Dec 11, 2023 |
| MSI           | Prestige 15 A10SC           | [b1c3e47458](https://linux-hardware.org/?probe=b1c3e47458) | Dec 07, 2023 |
| Acer          | Swift SFE16-42              | [f61134a2d0](https://linux-hardware.org/?probe=f61134a2d0) | Dec 04, 2023 |
| Dell          | XPS 13 9300                 | [68ba1c0162](https://linux-hardware.org/?probe=68ba1c0162) | Nov 26, 2023 |
| Dell          | XPS 15 9570                 | [8e243668e7](https://linux-hardware.org/?probe=8e243668e7) | Nov 26, 2023 |
| Acer          | Swift SFE16-42              | [6b2a075d5a](https://linux-hardware.org/?probe=6b2a075d5a) | Nov 25, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX95D... | [0a24a8ef6d](https://linux-hardware.org/?probe=0a24a8ef6d) | Nov 24, 2023 |
| Apple         | MacBookPro11,1              | [2018ab1ad9](https://linux-hardware.org/?probe=2018ab1ad9) | Nov 19, 2023 |
| Valve         | Jupiter                     | [31a965ca9d](https://linux-hardware.org/?probe=31a965ca9d) | Nov 14, 2023 |
| Timi          | RedmiBook 15                | [5f0d169445](https://linux-hardware.org/?probe=5f0d169445) | Nov 12, 2023 |
| ASUSTek       | K401UB                      | [3bc894aa34](https://linux-hardware.org/?probe=3bc894aa34) | Nov 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [d690fa8f27](https://linux-hardware.org/?probe=d690fa8f27) | Oct 29, 2023 |
| ASUSTek       | UX310UQK                    | [9c8029cd07](https://linux-hardware.org/?probe=9c8029cd07) | Oct 17, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | [fb1c2503cf](https://linux-hardware.org/?probe=fb1c2503cf) | Sep 29, 2023 |
| Acer          | Aspire 5750                 | [89dc9a349f](https://linux-hardware.org/?probe=89dc9a349f) | Sep 26, 2023 |
| HP            | EliteBook 725 G4            | [1ef194c5fd](https://linux-hardware.org/?probe=1ef194c5fd) | Sep 22, 2023 |
| EUROCOM       | RAPTOR X17                  | [bbd769440e](https://linux-hardware.org/?probe=bbd769440e) | Sep 21, 2023 |
| TUXEDO        | Stellaris Intel Gen5        | [fb5af8d0d8](https://linux-hardware.org/?probe=fb5af8d0d8) | Sep 19, 2023 |
| TUXEDO        | Stellaris Intel Gen5        | [c75315410e](https://linux-hardware.org/?probe=c75315410e) | Sep 19, 2023 |
| EUROCOM       | RAPTOR X17                  | [15e2ca1220](https://linux-hardware.org/?probe=15e2ca1220) | Sep 19, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [a32457e14d](https://linux-hardware.org/?probe=a32457e14d) | Sep 15, 2023 |
| Dell          | Latitude 7280               | [ecca4887d5](https://linux-hardware.org/?probe=ecca4887d5) | Sep 15, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | [032cd70e81](https://linux-hardware.org/?probe=032cd70e81) | Sep 15, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [938cec3228](https://linux-hardware.org/?probe=938cec3228) | Sep 09, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [7ce5ebe4bc](https://linux-hardware.org/?probe=7ce5ebe4bc) | Sep 07, 2023 |
| Lenovo        | Legion Y7000P IRH8 82YA     | [235e80247e](https://linux-hardware.org/?probe=235e80247e) | Sep 05, 2023 |
| ASUSTek       | K401UB                      | [14a7bf0f59](https://linux-hardware.org/?probe=14a7bf0f59) | Aug 28, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [efa1e38911](https://linux-hardware.org/?probe=efa1e38911) | Aug 26, 2023 |
| MSI           | GP66 Leopard 10UE           | [54eaec1cae](https://linux-hardware.org/?probe=54eaec1cae) | Aug 26, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [4d631eed0e](https://linux-hardware.org/?probe=4d631eed0e) | Aug 21, 2023 |
| Lenovo        | Legion Y7000P IRH8 82YA     | [70062471e2](https://linux-hardware.org/?probe=70062471e2) | Aug 19, 2023 |
| Acer          | Aspire A514-55              | [98ebe4bf9a](https://linux-hardware.org/?probe=98ebe4bf9a) | Aug 19, 2023 |
| Acer          | Aspire A514-55              | [cace7d6efb](https://linux-hardware.org/?probe=cace7d6efb) | Aug 18, 2023 |
| MSI           | GP66 Leopard 10UE           | [9f6cf770d1](https://linux-hardware.org/?probe=9f6cf770d1) | Aug 18, 2023 |
| Beelink       | Gemini X                    | [d5c4e54794](https://linux-hardware.org/?probe=d5c4e54794) | Aug 14, 2023 |
| Beelink       | Gemini X                    | [1610652627](https://linux-hardware.org/?probe=1610652627) | Aug 14, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | [f46a14b981](https://linux-hardware.org/?probe=f46a14b981) | Aug 12, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [dfc4d46266](https://linux-hardware.org/?probe=dfc4d46266) | Aug 05, 2023 |
| HUAWEI        | MACHD-WXX9                  | [8511f4c245](https://linux-hardware.org/?probe=8511f4c245) | Aug 05, 2023 |
| Dell          | Inspiron 14-3462            | [9300232981](https://linux-hardware.org/?probe=9300232981) | Aug 05, 2023 |
| Lenovo        | ThinkPad X250 20CL0007SG    | [f30d61c851](https://linux-hardware.org/?probe=f30d61c851) | Aug 01, 2023 |
| Apple         | MacBookPro12,1              | [5bc4bf8334](https://linux-hardware.org/?probe=5bc4bf8334) | Jul 28, 2023 |
| Apple         | MacBookPro11,5              | [57e295e5cf](https://linux-hardware.org/?probe=57e295e5cf) | Jul 27, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [78560cbf59](https://linux-hardware.org/?probe=78560cbf59) | Jul 24, 2023 |
| ASUSTek       | K46CB                       | [144d523bf1](https://linux-hardware.org/?probe=144d523bf1) | Jul 18, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [dfe9381867](https://linux-hardware.org/?probe=dfe9381867) | Jul 14, 2023 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [b50c5ad983](https://linux-hardware.org/?probe=b50c5ad983) | Jul 06, 2023 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [e141746297](https://linux-hardware.org/?probe=e141746297) | Jul 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [d94ad2e231](https://linux-hardware.org/?probe=d94ad2e231) | Jun 28, 2023 |
| Lenovo        | Legion R7000P2021 82JW      | [df59b5e8b7](https://linux-hardware.org/?probe=df59b5e8b7) | Jun 19, 2023 |
| Dell          | Precision 5520              | [8d5ec720c1](https://linux-hardware.org/?probe=8d5ec720c1) | Jun 19, 2023 |
| Lenovo        | Legion Y7000 2019 PG0 81... | [46ffcb9672](https://linux-hardware.org/?probe=46ffcb9672) | Jun 18, 2023 |
| Sony          | SVE11116FGW                 | [4c34707bef](https://linux-hardware.org/?probe=4c34707bef) | Jun 13, 2023 |
| Sony          | SVE11116FGW                 | [a048cbcdeb](https://linux-hardware.org/?probe=a048cbcdeb) | Jun 13, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | [e28e041a5c](https://linux-hardware.org/?probe=e28e041a5c) | Jun 02, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | [dcba8dc683](https://linux-hardware.org/?probe=dcba8dc683) | Jun 02, 2023 |
| Dell          | Latitude 7400               | [ef9ef10e4e](https://linux-hardware.org/?probe=ef9ef10e4e) | Jun 02, 2023 |
| Lenovo        | Yoga Slim 7 proX 14ARH7 ... | [684751d3db](https://linux-hardware.org/?probe=684751d3db) | May 26, 2023 |
| Acer          | Aspire 4750                 | [704221c10c](https://linux-hardware.org/?probe=704221c10c) | May 21, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | [d6933984d7](https://linux-hardware.org/?probe=d6933984d7) | May 10, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | [6beb57f72d](https://linux-hardware.org/?probe=6beb57f72d) | May 10, 2023 |
| Unknown       | AG958                       | [70aa4b6cf2](https://linux-hardware.org/?probe=70aa4b6cf2) | May 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | [9355511511](https://linux-hardware.org/?probe=9355511511) | May 07, 2023 |
| Acer          | Swift SF314-57G             | [6fd79b811f](https://linux-hardware.org/?probe=6fd79b811f) | Apr 28, 2023 |
| Dell          | XPS 13 7390                 | [318ea8ad1e](https://linux-hardware.org/?probe=318ea8ad1e) | Apr 27, 2023 |
| Dell          | Inspiron 15 5510            | [c8f22361f6](https://linux-hardware.org/?probe=c8f22361f6) | Apr 24, 2023 |
| AZW           | GT-R                        | [c37dabb7a7](https://linux-hardware.org/?probe=c37dabb7a7) | Apr 15, 2023 |
| Dell          | Latitude 7400               | [0f917420a1](https://linux-hardware.org/?probe=0f917420a1) | Apr 14, 2023 |
| Dell          | Inspiron 1525               | [c518902ba7](https://linux-hardware.org/?probe=c518902ba7) | Apr 13, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | [7eee4a859e](https://linux-hardware.org/?probe=7eee4a859e) | Apr 12, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | [874513db8d](https://linux-hardware.org/?probe=874513db8d) | Apr 12, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [0779903086](https://linux-hardware.org/?probe=0779903086) | Apr 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [c1f1d2bcc8](https://linux-hardware.org/?probe=c1f1d2bcc8) | Mar 28, 2023 |
| ASUSTek       | X45A                        | [a0401520d5](https://linux-hardware.org/?probe=a0401520d5) | Mar 27, 2023 |
| ASUSTek       | X45A                        | [dbe8e77436](https://linux-hardware.org/?probe=dbe8e77436) | Mar 27, 2023 |
| ASUSTek       | X45A                        | [675de376da](https://linux-hardware.org/?probe=675de376da) | Mar 27, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [c7ec617422](https://linux-hardware.org/?probe=c7ec617422) | Mar 24, 2023 |
| Apple         | MacBookPro11,2              | [92208949d5](https://linux-hardware.org/?probe=92208949d5) | Mar 22, 2023 |
| Apple         | MacBookPro11,2              | [aa71c25dba](https://linux-hardware.org/?probe=aa71c25dba) | Mar 22, 2023 |
| Lenovo        | ThinkPad X270 20HMS1KL0C    | [f27bb76a32](https://linux-hardware.org/?probe=f27bb76a32) | Mar 12, 2023 |
| ASUSTek       | ZenBook 13 UX331UAL         | [9b38c9668e](https://linux-hardware.org/?probe=9b38c9668e) | Mar 10, 2023 |
| Dell          | XPS 13 9310                 | [037f2e4a2d](https://linux-hardware.org/?probe=037f2e4a2d) | Mar 10, 2023 |
| Dell          | Inspiron 3468               | [e5977ee094](https://linux-hardware.org/?probe=e5977ee094) | Feb 21, 2023 |
| HUAWEI        | MACHC-WAX9                  | [69a8710cbb](https://linux-hardware.org/?probe=69a8710cbb) | Feb 18, 2023 |
| HUAWEI        | MACHC-WAX9                  | [db5d2b956a](https://linux-hardware.org/?probe=db5d2b956a) | Feb 18, 2023 |
| MSI           | GE62VR 6RF                  | [89c148a5f9](https://linux-hardware.org/?probe=89c148a5f9) | Feb 12, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [c454139724](https://linux-hardware.org/?probe=c454139724) | Feb 06, 2023 |
| Acer          | Aspire V5-132               | [7f74397112](https://linux-hardware.org/?probe=7f74397112) | Jan 24, 2023 |
| ASUSTek       | K45VM                       | [7fef453cdb](https://linux-hardware.org/?probe=7fef453cdb) | Jan 23, 2023 |
| Acer          | Aspire ES1-432              | [4a81caf8b2](https://linux-hardware.org/?probe=4a81caf8b2) | Jan 18, 2023 |
| Acer          | Aspire 5750G                | [d696233b84](https://linux-hardware.org/?probe=d696233b84) | Jan 18, 2023 |
| Dell          | Latitude 7390               | [cc5d8632f5](https://linux-hardware.org/?probe=cc5d8632f5) | Jan 13, 2023 |
| Dell          | Latitude 7390               | [a8ee39edc5](https://linux-hardware.org/?probe=a8ee39edc5) | Jan 13, 2023 |
| Unknown       | Unknown                     | [ae506ac561](https://linux-hardware.org/?probe=ae506ac561) | Jan 12, 2023 |
| HUAWEI        | MACHD-WXX9                  | [3e870855db](https://linux-hardware.org/?probe=3e870855db) | Jan 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [14273d90fd](https://linux-hardware.org/?probe=14273d90fd) | Jan 08, 2023 |
| ASUSTek       | X555LAB                     | [3af1bc02b8](https://linux-hardware.org/?probe=3af1bc02b8) | Jan 05, 2023 |
| ASUSTek       | X555LAB                     | [0a1360a7dc](https://linux-hardware.org/?probe=0a1360a7dc) | Jan 05, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [09d6510700](https://linux-hardware.org/?probe=09d6510700) | Jan 01, 2023 |
| Dell          | Inspiron 1420               | [fe6a8714da](https://linux-hardware.org/?probe=fe6a8714da) | Dec 31, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [6b09c2afcf](https://linux-hardware.org/?probe=6b09c2afcf) | Dec 23, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [efc1b154fb](https://linux-hardware.org/?probe=efc1b154fb) | Dec 23, 2022 |
| ASUSTek       | K45VM                       | [ee344993aa](https://linux-hardware.org/?probe=ee344993aa) | Dec 22, 2022 |
| ASUSTek       | K45VM                       | [cc9fb3fd05](https://linux-hardware.org/?probe=cc9fb3fd05) | Dec 22, 2022 |
| Lenovo        | Legion 5 15ARH7H 82RD       | [51f520d152](https://linux-hardware.org/?probe=51f520d152) | Dec 21, 2022 |
| Lenovo        | Legion 5 15ARH7H 82RD       | [d5171f9491](https://linux-hardware.org/?probe=d5171f9491) | Dec 19, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [615d3e1599](https://linux-hardware.org/?probe=615d3e1599) | Dec 14, 2022 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | [52546b1dd0](https://linux-hardware.org/?probe=52546b1dd0) | Dec 10, 2022 |
| HP            | ZBook 15                    | [2ff5969ae6](https://linux-hardware.org/?probe=2ff5969ae6) | Nov 26, 2022 |
| HP            | ZBook 15                    | [55e4fb5ba0](https://linux-hardware.org/?probe=55e4fb5ba0) | Nov 26, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [a462983d82](https://linux-hardware.org/?probe=a462983d82) | Nov 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop N740... | [37145c9282](https://linux-hardware.org/?probe=37145c9282) | Nov 19, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | [61f6e057e6](https://linux-hardware.org/?probe=61f6e057e6) | Nov 17, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [facd5aa317](https://linux-hardware.org/?probe=facd5aa317) | Nov 16, 2022 |
| Dell          | Precision 3571              | [039ece6391](https://linux-hardware.org/?probe=039ece6391) | Nov 10, 2022 |
| Google        | Atlas                       | [77922a522d](https://linux-hardware.org/?probe=77922a522d) | Nov 09, 2022 |
| Google        | Atlas                       | [829fcb8f6a](https://linux-hardware.org/?probe=829fcb8f6a) | Nov 09, 2022 |
| Dell          | Precision 3571              | [d305848533](https://linux-hardware.org/?probe=d305848533) | Nov 08, 2022 |
| Dell          | Precision 3571              | [681a655e1c](https://linux-hardware.org/?probe=681a655e1c) | Nov 08, 2022 |
| Dell          | Precision 3571              | [6f845855a5](https://linux-hardware.org/?probe=6f845855a5) | Nov 08, 2022 |
| Dell          | Precision 3571              | [9da55445b0](https://linux-hardware.org/?probe=9da55445b0) | Nov 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [cd0e637d88](https://linux-hardware.org/?probe=cd0e637d88) | Nov 01, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [a2d71fd3ca](https://linux-hardware.org/?probe=a2d71fd3ca) | Oct 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [0a0922ed82](https://linux-hardware.org/?probe=0a0922ed82) | Oct 27, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [52701ec9f4](https://linux-hardware.org/?probe=52701ec9f4) | Oct 24, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [1dc7719a4d](https://linux-hardware.org/?probe=1dc7719a4d) | Oct 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [ef7b367052](https://linux-hardware.org/?probe=ef7b367052) | Oct 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [18893915f3](https://linux-hardware.org/?probe=18893915f3) | Oct 17, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [e59c8f50b4](https://linux-hardware.org/?probe=e59c8f50b4) | Oct 07, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [d67006c592](https://linux-hardware.org/?probe=d67006c592) | Oct 07, 2022 |
| Fujitsu       | LIFEBOOK LH531              | [5ace2d0c1f](https://linux-hardware.org/?probe=5ace2d0c1f) | Oct 06, 2022 |
| Fujitsu       | LIFEBOOK LH531              | [3338607f1a](https://linux-hardware.org/?probe=3338607f1a) | Oct 05, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [082814c248](https://linux-hardware.org/?probe=082814c248) | Oct 04, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [ec44263cbd](https://linux-hardware.org/?probe=ec44263cbd) | Oct 01, 2022 |
| MSI           | Modern 14 B5M               | [1914cf579b](https://linux-hardware.org/?probe=1914cf579b) | Sep 29, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [f061f902ff](https://linux-hardware.org/?probe=f061f902ff) | Sep 25, 2022 |
| Acer          | Aspire E1-422               | [855ad327a4](https://linux-hardware.org/?probe=855ad327a4) | Sep 25, 2022 |
| Acer          | Aspire E1-422               | [829ec8aac1](https://linux-hardware.org/?probe=829ec8aac1) | Sep 25, 2022 |
| Acer          | Swift SF314-511             | [93680a7429](https://linux-hardware.org/?probe=93680a7429) | Sep 25, 2022 |
| Acer          | Swift SF314-511             | [ae5fd894b6](https://linux-hardware.org/?probe=ae5fd894b6) | Sep 25, 2022 |
| Lenovo        | Legion R9000K2021H 82N6     | [d739547049](https://linux-hardware.org/?probe=d739547049) | Sep 23, 2022 |
| Dell          | Inspiron 15 5510            | [0f698c857c](https://linux-hardware.org/?probe=0f698c857c) | Sep 16, 2022 |
| Dell          | Precision 3561              | [b61765a085](https://linux-hardware.org/?probe=b61765a085) | Sep 15, 2022 |
| Dell          | Inspiron 5567               | [3af5d11f3f](https://linux-hardware.org/?probe=3af5d11f3f) | Sep 14, 2022 |
| Dell          | Inspiron 5567               | [22e62266a2](https://linux-hardware.org/?probe=22e62266a2) | Sep 13, 2022 |
| Dell          | Latitude 3320               | [1ab9888966](https://linux-hardware.org/?probe=1ab9888966) | Sep 09, 2022 |
| MSI           | Pulse GL66 11UGK            | [db7f9099f2](https://linux-hardware.org/?probe=db7f9099f2) | Sep 05, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | [814c094769](https://linux-hardware.org/?probe=814c094769) | Sep 01, 2022 |
| Timi          | Redmi Book Pro 14 2022      | [3f61df6540](https://linux-hardware.org/?probe=3f61df6540) | Aug 26, 2022 |
| Apple         | MacBookPro8,1               | [c94e06f68f](https://linux-hardware.org/?probe=c94e06f68f) | Aug 26, 2022 |
| Apple         | MacBookPro8,1               | [7be66c9d4c](https://linux-hardware.org/?probe=7be66c9d4c) | Aug 25, 2022 |
| Acer          | Aspire V5-471PG             | [c91dcf26c8](https://linux-hardware.org/?probe=c91dcf26c8) | Aug 14, 2022 |
| Dell          | Latitude 3320               | [b8e1190875](https://linux-hardware.org/?probe=b8e1190875) | Aug 14, 2022 |
| Dell          | Latitude 3320               | [f489cd4f21](https://linux-hardware.org/?probe=f489cd4f21) | Aug 14, 2022 |
| Timi          | TM1701                      | [dc4d12ca83](https://linux-hardware.org/?probe=dc4d12ca83) | Aug 14, 2022 |
| Acer          | Aspire V5-471PG             | [5c2d9bf35f](https://linux-hardware.org/?probe=5c2d9bf35f) | Aug 13, 2022 |
| Dell          | G15 5520                    | [07feaad5d2](https://linux-hardware.org/?probe=07feaad5d2) | Aug 11, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [5931b46fe1](https://linux-hardware.org/?probe=5931b46fe1) | Aug 10, 2022 |
| Dell          | Latitude 3320               | [b99f237d17](https://linux-hardware.org/?probe=b99f237d17) | Aug 09, 2022 |
| Acer          | Aspire A315-41              | [6a9c811ea3](https://linux-hardware.org/?probe=6a9c811ea3) | Aug 07, 2022 |
| HP            | ZBook 15v G5                | [b08d670a98](https://linux-hardware.org/?probe=b08d670a98) | Jul 28, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [b41ce610a4](https://linux-hardware.org/?probe=b41ce610a4) | Jul 22, 2022 |
| Acer          | Aspire A315-41              | [366f3c9611](https://linux-hardware.org/?probe=366f3c9611) | Jul 14, 2022 |
| Acer          | Aspire A315-41              | [27f2c99f99](https://linux-hardware.org/?probe=27f2c99f99) | Jul 14, 2022 |
| Sony          | SVF1531V8CW                 | [bebf2fb162](https://linux-hardware.org/?probe=bebf2fb162) | Jul 13, 2022 |
| Dell          | Latitude 3120               | [361c9c4fa3](https://linux-hardware.org/?probe=361c9c4fa3) | Jul 06, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [3af286a188](https://linux-hardware.org/?probe=3af286a188) | Jun 30, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [e91c32dba7](https://linux-hardware.org/?probe=e91c32dba7) | Jun 25, 2022 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [c434fdda77](https://linux-hardware.org/?probe=c434fdda77) | Jun 20, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | [6941a8232a](https://linux-hardware.org/?probe=6941a8232a) | Jun 17, 2022 |
| ASUSTek       | GL552VW                     | [8ed24a5d98](https://linux-hardware.org/?probe=8ed24a5d98) | Jun 11, 2022 |
| Sony          | VPCCA15FG                   | [d155f5ee52](https://linux-hardware.org/?probe=d155f5ee52) | Jun 08, 2022 |
| Dell          | Inspiron 13 5310            | [70eccb19d4](https://linux-hardware.org/?probe=70eccb19d4) | Jun 01, 2022 |
| Lenovo        | 14w 81MQS02H00              | [e31087bfa9](https://linux-hardware.org/?probe=e31087bfa9) | May 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [f1f75187e1](https://linux-hardware.org/?probe=f1f75187e1) | May 21, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [bdc04b3c5d](https://linux-hardware.org/?probe=bdc04b3c5d) | May 19, 2022 |
| Lenovo        | ThinkPad X220 4286C11       | [8fd4bc6a6d](https://linux-hardware.org/?probe=8fd4bc6a6d) | May 15, 2022 |
| Lenovo        | ThinkPad X220 4286C11       | [0906d694b9](https://linux-hardware.org/?probe=0906d694b9) | May 15, 2022 |
| Dell          | XPS 13 7390                 | [8deb85f8e2](https://linux-hardware.org/?probe=8deb85f8e2) | May 03, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [3a7cd290f6](https://linux-hardware.org/?probe=3a7cd290f6) | Apr 30, 2022 |
| Dell          | Latitude 3120               | [c6b9dfe36e](https://linux-hardware.org/?probe=c6b9dfe36e) | Apr 18, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [7fe8e51699](https://linux-hardware.org/?probe=7fe8e51699) | Apr 13, 2022 |
| Foxconn       | Kangaroo Mobile Desktop     | [8e602bc358](https://linux-hardware.org/?probe=8e602bc358) | Apr 07, 2022 |
| Foxconn       | Kangaroo Mobile Desktop     | [7309102f77](https://linux-hardware.org/?probe=7309102f77) | Apr 07, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [ceee79344c](https://linux-hardware.org/?probe=ceee79344c) | Mar 31, 2022 |
| Acer          | Swift SF314-54G             | [615009b8ee](https://linux-hardware.org/?probe=615009b8ee) | Mar 23, 2022 |
| Acer          | Aspire VN7-592G             | [f4d3207c6d](https://linux-hardware.org/?probe=f4d3207c6d) | Mar 22, 2022 |
| AMI           | Intel                       | [6d581b03a6](https://linux-hardware.org/?probe=6d581b03a6) | Mar 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [d7f14afdd4](https://linux-hardware.org/?probe=d7f14afdd4) | Feb 26, 2022 |
| Dell          | Inspiron 3501               | [a8c8bdd208](https://linux-hardware.org/?probe=a8c8bdd208) | Feb 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [fbb2caeacf](https://linux-hardware.org/?probe=fbb2caeacf) | Feb 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [c5acc050e4](https://linux-hardware.org/?probe=c5acc050e4) | Feb 19, 2022 |
| Dell          | Precision 7560              | [811983afdd](https://linux-hardware.org/?probe=811983afdd) | Feb 17, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [25da470504](https://linux-hardware.org/?probe=25da470504) | Feb 14, 2022 |
| ASUSTek       | N501JW                      | [55550ca825](https://linux-hardware.org/?probe=55550ca825) | Feb 13, 2022 |
| COPELION I... | ZX Series                   | [764c80257b](https://linux-hardware.org/?probe=764c80257b) | Feb 12, 2022 |
| COPELION I... | ZX Series                   | [958dcebefa](https://linux-hardware.org/?probe=958dcebefa) | Feb 12, 2022 |
| Dell          | Latitude E5450              | [b426feb1d9](https://linux-hardware.org/?probe=b426feb1d9) | Feb 11, 2022 |
| Acer          | Predator G9-792             | [a01c295f77](https://linux-hardware.org/?probe=a01c295f77) | Feb 09, 2022 |
| Acer          | Predator G9-792             | [c030ff8b96](https://linux-hardware.org/?probe=c030ff8b96) | Feb 09, 2022 |
| Dell          | Latitude E7250              | [a7ba3830f7](https://linux-hardware.org/?probe=a7ba3830f7) | Feb 07, 2022 |
| Dell          | Inspiron 15 5510            | [3dbd4103ce](https://linux-hardware.org/?probe=3dbd4103ce) | Feb 06, 2022 |
| ASUSTek       | K45VM                       | [5cb4dcfe48](https://linux-hardware.org/?probe=5cb4dcfe48) | Jan 29, 2022 |
| ASUSTek       | K45VM                       | [39cac76612](https://linux-hardware.org/?probe=39cac76612) | Jan 28, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [a172ae51cf](https://linux-hardware.org/?probe=a172ae51cf) | Jan 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [efbe19b07b](https://linux-hardware.org/?probe=efbe19b07b) | Jan 20, 2022 |
| ASUSTek       | N501JW                      | [af9aaff7ee](https://linux-hardware.org/?probe=af9aaff7ee) | Jan 05, 2022 |
| Apple         | MacBookPro7,1               | [9f745065df](https://linux-hardware.org/?probe=9f745065df) | Dec 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [aae3ae242f](https://linux-hardware.org/?probe=aae3ae242f) | Dec 21, 2021 |
| Apple         | MacBookAir3,1               | [ef12425b00](https://linux-hardware.org/?probe=ef12425b00) | Dec 19, 2021 |
| Apple         | MacBookPro7,1               | [b92a9a109f](https://linux-hardware.org/?probe=b92a9a109f) | Dec 18, 2021 |
| Dell          | Inspiron 5580               | [29d56d5a5e](https://linux-hardware.org/?probe=29d56d5a5e) | Dec 06, 2021 |
| ASUSTek       | K501UX                      | [3f9b547c57](https://linux-hardware.org/?probe=3f9b547c57) | Dec 04, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [8876123555](https://linux-hardware.org/?probe=8876123555) | Nov 26, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [97e66fa893](https://linux-hardware.org/?probe=97e66fa893) | Nov 09, 2021 |
| Dell          | XPS 15 9570                 | [8e3c5b2ef0](https://linux-hardware.org/?probe=8e3c5b2ef0) | Nov 03, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [4b9f5aed33](https://linux-hardware.org/?probe=4b9f5aed33) | Nov 01, 2021 |
| Dell          | XPS 15 9510                 | [9ad082f18e](https://linux-hardware.org/?probe=9ad082f18e) | Nov 01, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [7ad1f07edb](https://linux-hardware.org/?probe=7ad1f07edb) | Oct 21, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [6edbff3019](https://linux-hardware.org/?probe=6edbff3019) | Oct 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [5ac27f4e29](https://linux-hardware.org/?probe=5ac27f4e29) | Oct 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [6e2173f8b4](https://linux-hardware.org/?probe=6e2173f8b4) | Sep 30, 2021 |
| ASUSTek       | UX32LA                      | [9763fb0928](https://linux-hardware.org/?probe=9763fb0928) | Sep 25, 2021 |
| ASUSTek       | UX32LA                      | [e97b7fce6b](https://linux-hardware.org/?probe=e97b7fce6b) | Sep 25, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [3d0115d011](https://linux-hardware.org/?probe=3d0115d011) | Sep 15, 2021 |
| Acer          | Aspire 6935                 | [fc440eee50](https://linux-hardware.org/?probe=fc440eee50) | Sep 12, 2021 |
| Acer          | Aspire 6935                 | [24cfb86539](https://linux-hardware.org/?probe=24cfb86539) | Sep 12, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [b7ff195931](https://linux-hardware.org/?probe=b7ff195931) | Sep 02, 2021 |
| Dell          | Precision 7560              | [75c607555e](https://linux-hardware.org/?probe=75c607555e) | Aug 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [a613776a9c](https://linux-hardware.org/?probe=a613776a9c) | Aug 18, 2021 |
| Acer          | Nitro AN515-43              | [d0952296d7](https://linux-hardware.org/?probe=d0952296d7) | Aug 17, 2021 |
| Dell          | Inspiron 7370               | [b702f17a07](https://linux-hardware.org/?probe=b702f17a07) | Aug 17, 2021 |
| Acer          | Swift SF314-57G             | [a5f10ae10b](https://linux-hardware.org/?probe=a5f10ae10b) | Aug 17, 2021 |
| Lenovo        | IdeaPad S530 13IML 81WU     | [978dbea880](https://linux-hardware.org/?probe=978dbea880) | Jul 27, 2021 |
| Lenovo        | IdeaPad S530 13IML 81WU     | [e3c0726e19](https://linux-hardware.org/?probe=e3c0726e19) | Jul 27, 2021 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [e74f010570](https://linux-hardware.org/?probe=e74f010570) | Jul 26, 2021 |
| Toshiba       | PORTEGE R930                | [6141314610](https://linux-hardware.org/?probe=6141314610) | Jul 22, 2021 |
| ASUSTek       | K45VM                       | [6d08e71c4e](https://linux-hardware.org/?probe=6d08e71c4e) | Jul 07, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [f4778083d9](https://linux-hardware.org/?probe=f4778083d9) | Jul 02, 2021 |
| Acer          | Swift SF314-41G             | [fe5e126da1](https://linux-hardware.org/?probe=fe5e126da1) | Jul 01, 2021 |
| Acer          | Aspire one                  | [adae8c183d](https://linux-hardware.org/?probe=adae8c183d) | Jun 22, 2021 |
| Sony          | VPCSB36FG                   | [c834499816](https://linux-hardware.org/?probe=c834499816) | Jun 10, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [650e1b9bf5](https://linux-hardware.org/?probe=650e1b9bf5) | Jun 05, 2021 |
| Dell          | Latitude 7490               | [879fc7a838](https://linux-hardware.org/?probe=879fc7a838) | May 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [920ef637b1](https://linux-hardware.org/?probe=920ef637b1) | May 21, 2021 |
| Razer         | Blade 15 Advanced Model ... | [c9c9d02ede](https://linux-hardware.org/?probe=c9c9d02ede) | May 20, 2021 |
| Sony          | VPCSB36FG                   | [828a8ac75d](https://linux-hardware.org/?probe=828a8ac75d) | May 18, 2021 |
| Dell          | XPS 15 9500                 | [ffa207ed1e](https://linux-hardware.org/?probe=ffa207ed1e) | May 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [c17ba8c1a6](https://linux-hardware.org/?probe=c17ba8c1a6) | May 04, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [46bb05613f](https://linux-hardware.org/?probe=46bb05613f) | Apr 13, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [ecc3dfa09a](https://linux-hardware.org/?probe=ecc3dfa09a) | Apr 13, 2021 |
| Foxconn       | Kangaroo Mobile Desktop     | [e26f3c0f44](https://linux-hardware.org/?probe=e26f3c0f44) | Mar 29, 2021 |
| Foxconn       | Kangaroo Mobile Desktop     | [e4c813c694](https://linux-hardware.org/?probe=e4c813c694) | Mar 29, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [ce138f71dd](https://linux-hardware.org/?probe=ce138f71dd) | Mar 15, 2021 |
| Toshiba       | PORTEGE R930                | [6e5981a1c8](https://linux-hardware.org/?probe=6e5981a1c8) | Mar 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [81b4d6916d](https://linux-hardware.org/?probe=81b4d6916d) | Mar 11, 2021 |
| Acer          | Swift SF314-56G             | [46ff93e8b8](https://linux-hardware.org/?probe=46ff93e8b8) | Mar 09, 2021 |
| Acer          | Swift SF314-56G             | [98a5817785](https://linux-hardware.org/?probe=98a5817785) | Mar 09, 2021 |
| Acer          | Aspire A515-51G             | [820e208bca](https://linux-hardware.org/?probe=820e208bca) | Mar 05, 2021 |
| Dell          | XPS 13 9310                 | [d8b4e607e1](https://linux-hardware.org/?probe=d8b4e607e1) | Mar 02, 2021 |
| Dell          | XPS 13 9310                 | [eca0e7f55f](https://linux-hardware.org/?probe=eca0e7f55f) | Mar 02, 2021 |
| Lenovo        | ThinkPad X395 20NL000TCD    | [eb33727eff](https://linux-hardware.org/?probe=eb33727eff) | Feb 18, 2021 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | [b2795c1a02](https://linux-hardware.org/?probe=b2795c1a02) | Feb 13, 2021 |
| Acer          | Swift SF314-56G             | [e67e7f24e8](https://linux-hardware.org/?probe=e67e7f24e8) | Feb 11, 2021 |
| Lenovo        | ThinkPad X220 4286C11       | [cbb8e959b4](https://linux-hardware.org/?probe=cbb8e959b4) | Feb 05, 2021 |
| Lenovo        | ThinkPad X220 4286C11       | [a8f5211aee](https://linux-hardware.org/?probe=a8f5211aee) | Feb 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [f4505630e3](https://linux-hardware.org/?probe=f4505630e3) | Feb 03, 2021 |
| Foxconn       | Kangaroo Mobile Desktop     | [0e5eeb215d](https://linux-hardware.org/?probe=0e5eeb215d) | Jan 28, 2021 |
| Lenovo        | RESCUER R720-15IKBN 80WW    | [15d05a517c](https://linux-hardware.org/?probe=15d05a517c) | Jan 23, 2021 |
| Notebook      | P65_P67SE                   | [1b4cd968fd](https://linux-hardware.org/?probe=1b4cd968fd) | Jan 22, 2021 |
| Lenovo        | ThinkPad X395 20NL000TCD    | [08990229db](https://linux-hardware.org/?probe=08990229db) | Jan 17, 2021 |
| Lenovo        | ThinkPad X395 20NL000TCD    | [dc6edb4a25](https://linux-hardware.org/?probe=dc6edb4a25) | Jan 14, 2021 |
| Dell          | G3 3500                     | [27386ee67b](https://linux-hardware.org/?probe=27386ee67b) | Jan 12, 2021 |
| Lenovo        | ThinkPad E14 20RA0058VA     | [3c08ce49f5](https://linux-hardware.org/?probe=3c08ce49f5) | Jan 08, 2021 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | [4b19f38fcd](https://linux-hardware.org/?probe=4b19f38fcd) | Jan 02, 2021 |
| Samsung       | RF510/RF410/RF710           | [3f041f4b71](https://linux-hardware.org/?probe=3f041f4b71) | Jan 01, 2021 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | [c30d1c7374](https://linux-hardware.org/?probe=c30d1c7374) | Dec 31, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [ccd41dd67e](https://linux-hardware.org/?probe=ccd41dd67e) | Dec 28, 2020 |
| HP            | EliteBook 845 G7 Noteboo... | [2fd914ada2](https://linux-hardware.org/?probe=2fd914ada2) | Dec 25, 2020 |
| Acer          | Aspire one                  | [556332908d](https://linux-hardware.org/?probe=556332908d) | Dec 14, 2020 |
| Lenovo        | ThinkPad T400 2768CJ6       | [1d878eeb02](https://linux-hardware.org/?probe=1d878eeb02) | Dec 10, 2020 |
| HP            | ProBook 440 G4              | [e28bcb99e5](https://linux-hardware.org/?probe=e28bcb99e5) | Dec 07, 2020 |
| ASUSTek       | K45VM                       | [9dedb35f93](https://linux-hardware.org/?probe=9dedb35f93) | Dec 04, 2020 |
| Aftershock    | N15_N17RF1                  | [09b42b449a](https://linux-hardware.org/?probe=09b42b449a) | Nov 27, 2020 |
| Dell          | Precision 7530              | [6ea3afdb4a](https://linux-hardware.org/?probe=6ea3afdb4a) | Nov 26, 2020 |
| Samsung       | RF510/RF410/RF710           | [1250c7dfbe](https://linux-hardware.org/?probe=1250c7dfbe) | Nov 25, 2020 |
| Lenovo        | ThinkPad X220 42911H8       | [cc79643d27](https://linux-hardware.org/?probe=cc79643d27) | Nov 22, 2020 |
| Dell          | Latitude 7400               | [3154149e40](https://linux-hardware.org/?probe=3154149e40) | Nov 21, 2020 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [93678477d7](https://linux-hardware.org/?probe=93678477d7) | Nov 20, 2020 |
| Lenovo        | ThinkPad X220 42911H8       | [c0ab31022d](https://linux-hardware.org/?probe=c0ab31022d) | Nov 20, 2020 |
| Dell          | Inspiron 5379               | [63815d0103](https://linux-hardware.org/?probe=63815d0103) | Nov 15, 2020 |
| Fujitsu       | LIFEBOOK SH561              | [759718c54b](https://linux-hardware.org/?probe=759718c54b) | Nov 10, 2020 |
| Lenovo        | ThinkPad X240 20AMS00100    | [f3f5326846](https://linux-hardware.org/?probe=f3f5326846) | Nov 08, 2020 |
| Dell          | Inspiron 3421               | [e08c38affc](https://linux-hardware.org/?probe=e08c38affc) | Nov 04, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [14cf318590](https://linux-hardware.org/?probe=14cf318590) | Oct 29, 2020 |
| Acer          | Swift SF314-54              | [35aa366265](https://linux-hardware.org/?probe=35aa366265) | Oct 18, 2020 |
| Acer          | ConceptD CN715-71           | [8396c1d9e6](https://linux-hardware.org/?probe=8396c1d9e6) | Oct 13, 2020 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [b47f8da412](https://linux-hardware.org/?probe=b47f8da412) | Oct 09, 2020 |
| HP            | Compaq 6510b                | [cf190a85ea](https://linux-hardware.org/?probe=cf190a85ea) | Oct 08, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | [05ef194f79](https://linux-hardware.org/?probe=05ef194f79) | Sep 28, 2020 |
| Lenovo        | ThinkPad X240 20AMS00100    | [78566669f0](https://linux-hardware.org/?probe=78566669f0) | Sep 27, 2020 |
| ASUSTek       | T300LA                      | [9ca4cba592](https://linux-hardware.org/?probe=9ca4cba592) | Sep 27, 2020 |
| Dell          | Inspiron 3476               | [021351472c](https://linux-hardware.org/?probe=021351472c) | Sep 26, 2020 |
| HP            | Compaq 6510b                | [9b9a4b4614](https://linux-hardware.org/?probe=9b9a4b4614) | Sep 22, 2020 |
| HP            | Compaq 6510b                | [3487aab3a6](https://linux-hardware.org/?probe=3487aab3a6) | Sep 20, 2020 |
| HP            | Compaq 6510b                | [b7382d2141](https://linux-hardware.org/?probe=b7382d2141) | Sep 19, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [4a4a01267c](https://linux-hardware.org/?probe=4a4a01267c) | Sep 18, 2020 |
| ASUSTek       | UX305CA                     | [dc9532c57b](https://linux-hardware.org/?probe=dc9532c57b) | Sep 12, 2020 |
| Samsung       | 305U1A                      | [9949d76953](https://linux-hardware.org/?probe=9949d76953) | Sep 09, 2020 |
| Samsung       | 305U1A                      | [9dbf37ad63](https://linux-hardware.org/?probe=9dbf37ad63) | Sep 09, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [cab06cdbd7](https://linux-hardware.org/?probe=cab06cdbd7) | Sep 07, 2020 |
| Acer          | Aspire A515-51G             | [c9d6ce6954](https://linux-hardware.org/?probe=c9d6ce6954) | Sep 05, 2020 |
| Aftershock    | N8xxEP6                     | [d8e9d4edfd](https://linux-hardware.org/?probe=d8e9d4edfd) | Sep 04, 2020 |
| Dell          | Precision 7530              | [91306b715e](https://linux-hardware.org/?probe=91306b715e) | Sep 03, 2020 |
| Aftershock    | N15_N17RF1                  | [e3e85f51cc](https://linux-hardware.org/?probe=e3e85f51cc) | Sep 03, 2020 |
| Dell          | Latitude 5400               | [498b1be7bd](https://linux-hardware.org/?probe=498b1be7bd) | Sep 02, 2020 |
| Toshiba       | PORTEGE R930                | [64ba8fde9d](https://linux-hardware.org/?probe=64ba8fde9d) | Aug 31, 2020 |
| Toshiba       | PORTEGE R930                | [b37b0d860d](https://linux-hardware.org/?probe=b37b0d860d) | Aug 31, 2020 |
| Lenovo        | Yoga 3 14 80JH              | [3623866056](https://linux-hardware.org/?probe=3623866056) | Aug 28, 2020 |
| HP            | Compaq 6510b                | [7db74443d5](https://linux-hardware.org/?probe=7db74443d5) | Aug 25, 2020 |
| HP            | Compaq 6510b                | [20f281e6e5](https://linux-hardware.org/?probe=20f281e6e5) | Aug 25, 2020 |
| HP            | Compaq 6510b                | [2791e33d53](https://linux-hardware.org/?probe=2791e33d53) | Aug 24, 2020 |
| ASUSTek       | ZenBook UX434FLC_UX433FL... | [8bc9e504d7](https://linux-hardware.org/?probe=8bc9e504d7) | Aug 13, 2020 |
| Toshiba       | PORTEGE R930                | [9f944b581d](https://linux-hardware.org/?probe=9f944b581d) | Aug 09, 2020 |
| Sony          | VGN-CR32G_W                 | [faf8f6a6fa](https://linux-hardware.org/?probe=faf8f6a6fa) | Aug 08, 2020 |
| Sony          | VGN-CR32G_W                 | [421ed7dcba](https://linux-hardware.org/?probe=421ed7dcba) | Aug 08, 2020 |
| MECHREVO      | Code 01 Series PF5NU1G      | [4dffd28998](https://linux-hardware.org/?probe=4dffd28998) | Aug 07, 2020 |
| Lenovo        | ThinkPad X230 23257VA       | [4319315cd0](https://linux-hardware.org/?probe=4319315cd0) | Jul 25, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [b6111e69ca](https://linux-hardware.org/?probe=b6111e69ca) | Jul 19, 2020 |
| HP            | Pavilion Sleekbook 14 PC    | [b554a2c8ec](https://linux-hardware.org/?probe=b554a2c8ec) | Jul 14, 2020 |
| HP            | Pavilion dv6000 (GF659EA... | [84a4ec9209](https://linux-hardware.org/?probe=84a4ec9209) | Jul 09, 2020 |
| HP            | EliteBook 725 G4            | [941e94f528](https://linux-hardware.org/?probe=941e94f528) | Jul 09, 2020 |
| Lenovo        | ThinkPad T490 20N3S5DU27    | [d4bb886295](https://linux-hardware.org/?probe=d4bb886295) | Jul 08, 2020 |
| Dell          | XPS 13 9370                 | [e794850de2](https://linux-hardware.org/?probe=e794850de2) | Jul 05, 2020 |
| HP            | EliteBook 725 G4            | [b3e1336d2f](https://linux-hardware.org/?probe=b3e1336d2f) | Jul 04, 2020 |
| Acer          | Swift SF514-54GT            | [a5b63702a2](https://linux-hardware.org/?probe=a5b63702a2) | Jul 03, 2020 |
| Lenovo        | ThinkPad T420s 417429U      | [8d9ec3fd6e](https://linux-hardware.org/?probe=8d9ec3fd6e) | Jun 27, 2020 |
| ASUSTek       | UX305CA                     | [7b35a1c840](https://linux-hardware.org/?probe=7b35a1c840) | Jun 26, 2020 |
| Toshiba       | PORTEGE Z10t-A              | [dd0834c2dd](https://linux-hardware.org/?probe=dd0834c2dd) | Jun 23, 2020 |
| Lenovo        | IdeaPad U460 20056          | [31c7edc616](https://linux-hardware.org/?probe=31c7edc616) | Jun 17, 2020 |
| ASUSTek       | ZenBook UX434FLC_UX433FL... | [4add01698f](https://linux-hardware.org/?probe=4add01698f) | Jun 14, 2020 |
| Dell          | Latitude E7440              | [1664235765](https://linux-hardware.org/?probe=1664235765) | Jun 03, 2020 |
| Dell          | Latitude E7440              | [d71cf3dba2](https://linux-hardware.org/?probe=d71cf3dba2) | Jun 03, 2020 |
| Lenovo        | G550 2958                   | [a8c4b1a8cf](https://linux-hardware.org/?probe=a8c4b1a8cf) | Jun 01, 2020 |
| Lenovo        | ThinkPad L460 20FUCTO1WW    | [da2a23020c](https://linux-hardware.org/?probe=da2a23020c) | May 21, 2020 |
| Dell          | XPS 15 7590                 | [c91cd5679c](https://linux-hardware.org/?probe=c91cd5679c) | May 19, 2020 |
| Dell          | XPS 13 9360                 | [10e8823c6b](https://linux-hardware.org/?probe=10e8823c6b) | May 17, 2020 |
| Lenovo        | G550 2958                   | [4e4bcc14f1](https://linux-hardware.org/?probe=4e4bcc14f1) | May 11, 2020 |
| Lenovo        | G550 2958                   | [ea8d2d9296](https://linux-hardware.org/?probe=ea8d2d9296) | May 11, 2020 |
| Lenovo        | G550 2958                   | [cfd6e82a6f](https://linux-hardware.org/?probe=cfd6e82a6f) | May 11, 2020 |
| Acer          | Predator PH315-52           | [7adb1a873c](https://linux-hardware.org/?probe=7adb1a873c) | May 04, 2020 |
| Lenovo        | ThinkPad X230 23257VA       | [09817eac19](https://linux-hardware.org/?probe=09817eac19) | May 01, 2020 |
| Lenovo        | ThinkPad T400 2768AA6       | [665d6e56af](https://linux-hardware.org/?probe=665d6e56af) | May 01, 2020 |
| ASUSTek       | T300LA                      | [c173e838c3](https://linux-hardware.org/?probe=c173e838c3) | Apr 26, 2020 |
| ASUSTek       | T300LA                      | [6311e7f4b5](https://linux-hardware.org/?probe=6311e7f4b5) | Apr 26, 2020 |
| Apple         | MacBookPro8,1               | [42636a47b1](https://linux-hardware.org/?probe=42636a47b1) | Apr 26, 2020 |
| ASUSTek       | ASUS Gaming FX570UD         | [a9cd8ef28f](https://linux-hardware.org/?probe=a9cd8ef28f) | Apr 22, 2020 |
| Acer          | Prespa1                     | [791259386e](https://linux-hardware.org/?probe=791259386e) | Apr 16, 2020 |
| Lenovo        | B50-30 20382                | [57b8f867a1](https://linux-hardware.org/?probe=57b8f867a1) | Apr 09, 2020 |
| Acer          | Aspire E5-473G              | [17f3a0e473](https://linux-hardware.org/?probe=17f3a0e473) | Apr 08, 2020 |
| Apple         | MacBookPro8,1               | [429fde3ebd](https://linux-hardware.org/?probe=429fde3ebd) | Apr 02, 2020 |
| Dell          | Latitude E6410              | [920a80dc90](https://linux-hardware.org/?probe=920a80dc90) | Mar 31, 2020 |
| Apple         | MacBookPro11,4              | [3c9bd63848](https://linux-hardware.org/?probe=3c9bd63848) | Mar 30, 2020 |
| Acer          | ConceptD CN715-71           | [2a99d0f76b](https://linux-hardware.org/?probe=2a99d0f76b) | Mar 28, 2020 |
| Acer          | ConceptD CN715-71           | [93d970f678](https://linux-hardware.org/?probe=93d970f678) | Mar 24, 2020 |
| Samsung       | RF510/RF410/RF710           | [daa4d098dc](https://linux-hardware.org/?probe=daa4d098dc) | Mar 13, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th E... | [b913bc5cc5](https://linux-hardware.org/?probe=b913bc5cc5) | Feb 18, 2020 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [819116ee69](https://linux-hardware.org/?probe=819116ee69) | Feb 16, 2020 |
| Acer          | ConceptD CN715-71           | [93c40180a2](https://linux-hardware.org/?probe=93c40180a2) | Feb 11, 2020 |
| Acer          | ConceptD CN715-71           | [f6c3a576c2](https://linux-hardware.org/?probe=f6c3a576c2) | Feb 11, 2020 |
| Lenovo        | ThinkPad W540 20BG001KUK    | [627909b9e5](https://linux-hardware.org/?probe=627909b9e5) | Feb 04, 2020 |
| Dell          | Inspiron 7591               | [b33d5cddc5](https://linux-hardware.org/?probe=b33d5cddc5) | Jan 25, 2020 |
| ASUSTek       | U24E                        | [563b794d8a](https://linux-hardware.org/?probe=563b794d8a) | Dec 23, 2019 |
| Lenovo        | ThinkPad T400 2768CJ6       | [011ab343ef](https://linux-hardware.org/?probe=011ab343ef) | Dec 22, 2019 |
| Lenovo        | ThinkPad T400 2768CJ6       | [bb9da61133](https://linux-hardware.org/?probe=bb9da61133) | Dec 21, 2019 |
| Acer          | ConceptD CN715-71           | [54109739eb](https://linux-hardware.org/?probe=54109739eb) | Dec 20, 2019 |
| Acer          | ConceptD CN715-71           | [5d75e45350](https://linux-hardware.org/?probe=5d75e45350) | Dec 20, 2019 |
| Acer          | ConceptD CN715-71           | [fb27c8cabb](https://linux-hardware.org/?probe=fb27c8cabb) | Dec 20, 2019 |
| Lenovo        | ThinkPad X395 20NL000TCD    | [adec400398](https://linux-hardware.org/?probe=adec400398) | Dec 19, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [86221df903](https://linux-hardware.org/?probe=86221df903) | Nov 30, 2019 |
| HP            | ZBook Studio G5             | [87503b1263](https://linux-hardware.org/?probe=87503b1263) | Aug 22, 2019 |
| ASUSTek       | X406UAR                     | [5e3ebad239](https://linux-hardware.org/?probe=5e3ebad239) | Jul 05, 2019 |
| Apple         | MacBookPro9,2               | [1d4494ee1f](https://linux-hardware.org/?probe=1d4494ee1f) | Jul 03, 2019 |
| Lenovo        | S20-30 20421                | [5c27867f6e](https://linux-hardware.org/?probe=5c27867f6e) | Jun 26, 2019 |
| Dell          | Inspiron 13-5378            | [f938ce631a](https://linux-hardware.org/?probe=f938ce631a) | Jun 17, 2019 |
| Dell          | Inspiron 13-5378            | [5e33156c57](https://linux-hardware.org/?probe=5e33156c57) | Jun 17, 2019 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [0ab22425ea](https://linux-hardware.org/?probe=0ab22425ea) | May 28, 2019 |
| Apple         | MacBookPro11,5              | [ab95788992](https://linux-hardware.org/?probe=ab95788992) | May 18, 2019 |
| ASUSTek       | S500CA                      | [c0218275f7](https://linux-hardware.org/?probe=c0218275f7) | Apr 28, 2019 |
| Acer          | AO751h                      | [0ee57513c5](https://linux-hardware.org/?probe=0ee57513c5) | Apr 07, 2019 |
| MSI           | GE63VR 7RE                  | [635226b290](https://linux-hardware.org/?probe=635226b290) | May 31, 2018 |
| Lenovo        | ThinkPad W540 20BG001KUK    | [ecd2f8138f](https://linux-hardware.org/?probe=ecd2f8138f) | Dec 27, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Singapore/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 48        | 12.37%  |
| Ubuntu 22.04                 | 29        | 7.47%   |
| Ubuntu 18.04                 | 19        | 4.9%    |
| Arch Rolling                 | 17        | 4.38%   |
| Pop!_OS 22.04                | 11        | 2.84%   |
| Fedora 41                    | 10        | 2.58%   |
| Fedora 33                    | 10        | 2.58%   |
| Ubuntu 24.04                 | 9         | 2.32%   |
| Fedora 42                    | 8         | 2.06%   |
| Fedora 38                    | 6         | 1.55%   |
| Zorin 17                     | 5         | 1.29%   |
| Pop!_OS 20.04                | 5         | 1.29%   |
| EndeavourOS Rolling          | 5         | 1.29%   |
| Debian 12                    | 5         | 1.29%   |
| Debian                       | 5         | 1.29%   |
| ArcoLinux Rolling            | 5         | 1.29%   |
| Arch                         | 5         | 1.29%   |
| Zorin 16                     | 4         | 1.03%   |
| Ubuntu 24.10                 | 4         | 1.03%   |
| OpenMandriva 23.01           | 4         | 1.03%   |
| Linux Mint 21                | 4         | 1.03%   |
| Kubuntu 22.04                | 4         | 1.03%   |
| Fedora 43                    | 4         | 1.03%   |
| Fedora 40                    | 4         | 1.03%   |
| Fedora 39                    | 4         | 1.03%   |
| Fedora 37                    | 4         | 1.03%   |
| Debian Testing               | 4         | 1.03%   |
| Debian 11                    | 4         | 1.03%   |
| Xubuntu 20.04                | 3         | 0.77%   |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 0.77%   |
| Linux Mint 22.1              | 3         | 0.77%   |
| Linux Mint 21.2              | 3         | 0.77%   |
| Linux Mint 21.1              | 3         | 0.77%   |
| Linux Mint 20                | 3         | 0.77%   |
| KDE neon 22.04               | 3         | 0.77%   |
| Fedora 36                    | 3         | 0.77%   |
| Fedora 32                    | 3         | 0.77%   |
| Elementary 6.1               | 3         | 0.77%   |
| Zorin 15                     | 2         | 0.52%   |
| Ubuntu 21.10                 | 2         | 0.52%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 116       | 32.77%  |
| Fedora        | 41        | 11.58%  |
| OpenMandriva  | 23        | 6.5%    |
| Arch          | 21        | 5.93%   |
| Debian        | 20        | 5.65%   |
| Pop!_OS       | 19        | 5.37%   |
| Linux Mint    | 18        | 5.08%   |
| Zorin         | 11        | 3.11%   |
| Kubuntu       | 9         | 2.54%   |
| Manjaro       | 7         | 1.98%   |
| ArcoLinux     | 6         | 1.69%   |
| NixOS         | 5         | 1.41%   |
| KDE neon      | 5         | 1.41%   |
| EndeavourOS   | 5         | 1.41%   |
| Xubuntu       | 4         | 1.13%   |
| SteamOS       | 4         | 1.13%   |
| Lubuntu       | 4         | 1.13%   |
| openSUSE      | 3         | 0.85%   |
| Gentoo        | 3         | 0.85%   |
| Elementary    | 3         | 0.85%   |
| Ubuntu Unity  | 2         | 0.56%   |
| Ubuntu Budgie | 2         | 0.56%   |
| ROSA          | 2         | 0.56%   |
| RHEL          | 2         | 0.56%   |
| Nobara        | 2         | 0.56%   |
| Kali          | 2         | 0.56%   |
| Garuda Linux  | 2         | 0.56%   |
| Endless       | 2         | 0.56%   |
| Deepin        | 2         | 0.56%   |
| Clear Linux   | 2         | 0.56%   |
| TUXEDO OS     | 1         | 0.28%   |
| Solus         | 1         | 0.28%   |
| Q4OS          | 1         | 0.28%   |
| MX            | 1         | 0.28%   |
| LMDE          | 1         | 0.28%   |
| Bazzite       | 1         | 0.28%   |
| Alpine        | 1         | 0.28%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                  | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| 5.15.0-56-generic                        | 6         | 1.35%   |
| 5.4.0-48-generic                         | 5         | 1.13%   |
| 5.15.0-46-generic                        | 5         | 1.13%   |
| 6.2.0-39-generic                         | 4         | 0.9%    |
| 6.14.2-desktop-3omv2590                  | 4         | 0.9%    |
| 6.1.1-desktop-1omv2290                   | 4         | 0.9%    |
| 5.9.8-200.fc33.x86_64                    | 4         | 0.9%    |
| 5.4.0-42-generic                         | 4         | 0.9%    |
| 5.4.0-40-generic                         | 4         | 0.9%    |
| 5.3.0-62-generic                         | 4         | 0.9%    |
| 5.11.0-43-generic                        | 4         | 0.9%    |
| 6.9.3-76060903-generic                   | 3         | 0.68%   |
| 6.8.0-60-generic                         | 3         | 0.68%   |
| 6.8.0-45-generic                         | 3         | 0.68%   |
| 6.8.0-0.rc6.49.fc40.x86_64               | 3         | 0.68%   |
| 6.2.15-300.fc38.x86_64                   | 3         | 0.68%   |
| 6.2.0-26-generic                         | 3         | 0.68%   |
| 5.4.0-65-generic                         | 3         | 0.68%   |
| 5.4.0-52-generic                         | 3         | 0.68%   |
| 5.4.0-47-generic                         | 3         | 0.68%   |
| 5.4.0-37-generic                         | 3         | 0.68%   |
| 5.4.0-29-generic                         | 3         | 0.68%   |
| 5.15.0-41-generic                        | 3         | 0.68%   |
| 5.13.0-28-generic                        | 3         | 0.68%   |
| 5.11.0-38-generic                        | 3         | 0.68%   |
| 6.8.9-300.fc40.x86_64                    | 2         | 0.45%   |
| 6.8.12-amd64                             | 2         | 0.45%   |
| 6.8.0-79-generic                         | 2         | 0.45%   |
| 6.8.0-57-generic                         | 2         | 0.45%   |
| 6.8.0-49-generic                         | 2         | 0.45%   |
| 6.8.0-40-generic                         | 2         | 0.45%   |
| 6.5.12-300.fc39.x86_64                   | 2         | 0.45%   |
| 6.5.0-valve23-1-neptune-65-g385b5e207ae2 | 2         | 0.45%   |
| 6.4.6-76060406-generic                   | 2         | 0.45%   |
| 6.3.8-200.fc38.x86_64                    | 2         | 0.45%   |
| 6.3.5-desktop-3omv2390                   | 2         | 0.45%   |
| 6.2.6-desktop-1omv2390                   | 2         | 0.45%   |
| 6.2.10-300.fc38.x86_64                   | 2         | 0.45%   |
| 6.2.0-32-generic                         | 2         | 0.45%   |
| 6.2.0-20-generic                         | 2         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 38        | 9%      |
| 5.15.0  | 35        | 8.29%   |
| 6.8.0   | 22        | 5.21%   |
| 5.11.0  | 13        | 3.08%   |
| 6.2.0   | 12        | 2.84%   |
| 5.8.0   | 11        | 2.61%   |
| 5.13.0  | 11        | 2.61%   |
| 6.11.0  | 8         | 1.9%    |
| 5.19.0  | 8         | 1.9%    |
| 6.14.0  | 7         | 1.66%   |
| 5.3.0   | 7         | 1.66%   |
| 4.18.0  | 7         | 1.66%   |
| 4.15.0  | 7         | 1.66%   |
| 6.1.0   | 6         | 1.42%   |
| 5.18.0  | 6         | 1.42%   |
| 6.5.0   | 5         | 1.18%   |
| 5.10.0  | 5         | 1.18%   |
| 6.9.3   | 4         | 0.95%   |
| 6.14.2  | 4         | 0.95%   |
| 6.1.1   | 4         | 0.95%   |
| 5.9.8   | 4         | 0.95%   |
| 5.0.0   | 4         | 0.95%   |
| 6.8.9   | 3         | 0.71%   |
| 6.3.8   | 3         | 0.71%   |
| 6.3.5   | 3         | 0.71%   |
| 6.2.15  | 3         | 0.71%   |
| 6.2.10  | 3         | 0.71%   |
| 6.8.12  | 2         | 0.47%   |
| 6.8.10  | 2         | 0.47%   |
| 6.6.7   | 2         | 0.47%   |
| 6.6.1   | 2         | 0.47%   |
| 6.5.12  | 2         | 0.47%   |
| 6.4.6   | 2         | 0.47%   |
| 6.2.6   | 2         | 0.47%   |
| 6.17.7  | 2         | 0.47%   |
| 6.17.0  | 2         | 0.47%   |
| 6.16.4  | 2         | 0.47%   |
| 6.15.4  | 2         | 0.47%   |
| 6.15.10 | 2         | 0.47%   |
| 6.14.8  | 2         | 0.47%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 45        | 11.11%  |
| 5.15    | 41        | 10.12%  |
| 6.8     | 27        | 6.67%   |
| 6.2     | 18        | 4.44%   |
| 5.8     | 17        | 4.2%    |
| 5.13    | 17        | 4.2%    |
| 6.14    | 15        | 3.7%    |
| 6.1     | 15        | 3.7%    |
| 5.11    | 14        | 3.46%   |
| 6.6     | 12        | 2.96%   |
| 6.12    | 12        | 2.96%   |
| 5.19    | 11        | 2.72%   |
| 5.10    | 11        | 2.72%   |
| 6.11    | 10        | 2.47%   |
| 5.18    | 10        | 2.47%   |
| 6.5     | 9         | 2.22%   |
| 6.13    | 9         | 2.22%   |
| 6.0     | 8         | 1.98%   |
| 6.3     | 7         | 1.73%   |
| 6.17    | 7         | 1.73%   |
| 6.15    | 7         | 1.73%   |
| 5.9     | 7         | 1.73%   |
| 5.3     | 7         | 1.73%   |
| 4.18    | 7         | 1.73%   |
| 4.15    | 7         | 1.73%   |
| 6.9     | 6         | 1.48%   |
| 6.4     | 6         | 1.48%   |
| 5.16    | 6         | 1.48%   |
| 5.0     | 5         | 1.23%   |
| 6.16    | 4         | 0.99%   |
| 6.10    | 4         | 0.99%   |
| 5.6     | 4         | 0.99%   |
| 5.17    | 4         | 0.99%   |
| 5.12    | 4         | 0.99%   |
| 4.19    | 3         | 0.74%   |
| 5.5     | 2         | 0.49%   |
| 6.7     | 1         | 0.25%   |
| 6.18    | 1         | 0.25%   |
| 5.7     | 1         | 0.25%   |
| 5.14    | 1         | 0.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 340       | 99.13%  |
| i686    | 2         | 0.58%   |
| aarch64 | 1         | 0.29%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 185       | 51.25%  |
| KDE5            | 50        | 13.85%  |
| Unknown         | 27        | 7.48%   |
| KDE6            | 25        | 6.93%   |
| X-Cinnamon      | 19        | 5.26%   |
| XFCE            | 14        | 3.88%   |
| KDE             | 9         | 2.49%   |
| LXQt            | 8         | 2.22%   |
| Cinnamon        | 4         | 1.11%   |
| Pantheon        | 3         | 0.83%   |
| Hyprland        | 3         | 0.83%   |
| Budgie          | 3         | 0.83%   |
| Unity           | 2         | 0.55%   |
| KDE4            | 2         | 0.55%   |
| i3              | 2         | 0.55%   |
| GNOME Flashback | 2         | 0.55%   |
| MATE            | 1         | 0.28%   |
| GNOME Classic   | 1         | 0.28%   |
| Deepin          | 1         | 0.28%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 218       | 61.06%  |
| Wayland | 113       | 31.65%  |
| Unknown | 16        | 4.48%   |
| Tty     | 10        | 2.8%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 135       | 38.03%  |
| SDDM    | 69        | 19.44%  |
| GDM3    | 67        | 18.87%  |
| GDM     | 49        | 13.8%   |
| LightDM | 29        | 8.17%   |
| TDM     | 4         | 1.13%   |
| KDM     | 1         | 0.28%   |
| GREETD  | 1         | 0.28%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| en_US      | 145       | 40.73%  |
| en_SG      | 129       | 36.24%  |
| zh_CN      | 24        | 6.74%   |
| Unknown    | 19        | 5.34%   |
| en_GB      | 11        | 3.09%   |
| C          | 7         | 1.97%   |
| en_IN      | 6         | 1.69%   |
| en_PH      | 3         | 0.84%   |
| de_DE      | 3         | 0.84%   |
| id_ID      | 2         | 0.56%   |
| en_AU      | 2         | 0.56%   |
| zh_SG      | 1         | 0.28%   |
| zh_CN.UTF8 | 1         | 0.28%   |
| ru_UA      | 1         | 0.28%   |
| en_IE      | 1         | 0.28%   |
| en_HK      | 1         | 0.28%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 239       | 68.29%  |
| BIOS | 111       | 31.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 255       | 72.86%  |
| Btrfs   | 53        | 15.14%  |
| Overlay | 16        | 4.57%   |
| Tmpfs   | 14        | 4%      |
| Unknown | 6         | 1.71%   |
| Xfs     | 4         | 1.14%   |
| Zfs     | 2         | 0.57%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 197       | 56.94%  |
| Unknown | 138       | 39.88%  |
| MBR     | 11        | 3.18%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 309       | 88.03%  |
| Yes       | 42        | 11.97%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 211       | 60.29%  |
| Yes       | 139       | 39.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 90        | 26.24%  |
| ASUSTek Computer       | 59        | 17.2%   |
| Dell                   | 54        | 15.74%  |
| Acer                   | 37        | 10.79%  |
| Hewlett-Packard        | 18        | 5.25%   |
| Apple                  | 17        | 4.96%   |
| MECHREVO               | 8         | 2.33%   |
| MSI                    | 7         | 2.04%   |
| HUAWEI                 | 6         | 1.75%   |
| Sony                   | 5         | 1.46%   |
| Valve                  | 4         | 1.17%   |
| Fujitsu                | 4         | 1.17%   |
| Timi                   | 3         | 0.87%   |
| Unknown                | 3         | 0.87%   |
| TUXEDO                 | 2         | 0.58%   |
| Toshiba                | 2         | 0.58%   |
| Samsung Electronics    | 2         | 0.58%   |
| Razer                  | 2         | 0.58%   |
| Google                 | 2         | 0.58%   |
| Foxconn                | 2         | 0.58%   |
| Aftershock             | 2         | 0.58%   |
| WOOKING                | 1         | 0.29%   |
| THUNDEROBOT            | 1         | 0.29%   |
| System76               | 1         | 0.29%   |
| Notebook               | 1         | 0.29%   |
| MicroByte              | 1         | 0.29%   |
| LG Electronics         | 1         | 0.29%   |
| HONOR                  | 1         | 0.29%   |
| EUROCOM                | 1         | 0.29%   |
| COPELION INTERNATIONAL | 1         | 0.29%   |
| Chuwi                  | 1         | 0.29%   |
| Beelink                | 1         | 0.29%   |
| AZW                    | 1         | 0.29%   |
| AMI                    | 1         | 0.29%   |
| Alienware              | 1         | 0.29%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Valve Jupiter                            | 4         | 1.17%   |
| Apple MacBookPro9,2                      | 4         | 1.17%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ         | 3         | 0.87%   |
| Dell Inspiron 15 5510                    | 3         | 0.87%   |
| Acer Swift SF314-57G                     | 3         | 0.87%   |
| Unknown                                  | 3         | 0.87%   |
| Lenovo ThinkPad X220 42911H8             | 2         | 0.58%   |
| Lenovo Legion Y7000P IRH8 82YA           | 2         | 0.58%   |
| Lenovo Legion 5 15ARH05 82B5             | 2         | 0.58%   |
| Lenovo IdeaPad S340-14API 81NB           | 2         | 0.58%   |
| Lenovo IdeaPad 100-14IBY 80MH            | 2         | 0.58%   |
| HUAWEI MACHD-WXX9                        | 2         | 0.58%   |
| HP Compaq 6510b                          | 2         | 0.58%   |
| Fujitsu LIFEBOOK LH531                   | 2         | 0.58%   |
| Foxconn Kangaroo Mobile Desktop          | 2         | 0.58%   |
| Dell XPS 13 9310                         | 2         | 0.58%   |
| Dell XPS 13 7390                         | 2         | 0.58%   |
| Dell Latitude E7250                      | 2         | 0.58%   |
| Dell Latitude 3320                       | 2         | 0.58%   |
| Dell Latitude 3120                       | 2         | 0.58%   |
| Dell Inspiron 1525                       | 2         | 0.58%   |
| ASUS VivoBook_ASUSLaptop N7401ZE_N7401ZE | 2         | 0.58%   |
| ASUS VivoBook_ASUSLaptop M3500QC_M3500QC | 2         | 0.58%   |
| ASUS T300LA                              | 2         | 0.58%   |
| ASUS K45VM                               | 2         | 0.58%   |
| Apple MacBookPro8,1                      | 2         | 0.58%   |
| Apple MacBookPro11,5                     | 2         | 0.58%   |
| Acer ConceptD CN715-71                   | 2         | 0.58%   |
| WOOKING X16                              | 1         | 0.29%   |
| TUXEDO Stellaris Intel Gen5              | 1         | 0.29%   |
| TUXEDO InfinityBook Pro Gen7 (MK1)       | 1         | 0.29%   |
| Toshiba PORTEGE Z10t-A                   | 1         | 0.29%   |
| Toshiba PORTEGE R930                     | 1         | 0.29%   |
| Timi TM1701                              | 1         | 0.29%   |
| Timi RedmiBook 15                        | 1         | 0.29%   |
| Timi Redmi Book Pro 14 2022              | 1         | 0.29%   |
| THUNDEROBOT R15                          | 1         | 0.29%   |
| System76 Oryx Pro                        | 1         | 0.29%   |
| Sony VPCSB36FG                           | 1         | 0.29%   |
| Sony VPCCA15FG                           | 1         | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 42        | 12.24%  |
| Dell Inspiron       | 19        | 5.54%   |
| Acer Aspire         | 18        | 5.25%   |
| Lenovo IdeaPad      | 17        | 4.96%   |
| Dell Latitude       | 17        | 4.96%   |
| Lenovo Legion       | 16        | 4.66%   |
| ASUS VivoBook       | 16        | 4.66%   |
| Acer Swift          | 12        | 3.5%    |
| Dell XPS            | 11        | 3.21%   |
| ASUS ASUS           | 9         | 2.62%   |
| Lenovo Yoga         | 6         | 1.75%   |
| ASUS ZenBook        | 6         | 1.75%   |
| ASUS ROG            | 6         | 1.75%   |
| Dell Precision      | 5         | 1.46%   |
| Apple MacBookPro11  | 5         | 1.46%   |
| Valve Jupiter       | 4         | 1.17%   |
| Lenovo ThinkBook    | 4         | 1.17%   |
| HP Pavilion         | 4         | 1.17%   |
| HP EliteBook        | 4         | 1.17%   |
| Fujitsu LIFEBOOK    | 4         | 1.17%   |
| Apple MacBookPro9   | 4         | 1.17%   |
| HP ZBook            | 3         | 0.87%   |
| Unknown             | 3         | 0.87%   |
| Toshiba PORTEGE     | 2         | 0.58%   |
| Razer Blade         | 2         | 0.58%   |
| HUAWEI MACHD-WXX9   | 2         | 0.58%   |
| HP OMEN             | 2         | 0.58%   |
| HP Compaq           | 2         | 0.58%   |
| Foxconn Kangaroo    | 2         | 0.58%   |
| ASUS TUF            | 2         | 0.58%   |
| ASUS T300LA         | 2         | 0.58%   |
| ASUS K45VM          | 2         | 0.58%   |
| Apple MacBookPro8   | 2         | 0.58%   |
| Acer Predator       | 2         | 0.58%   |
| Acer Nitro          | 2         | 0.58%   |
| Acer ConceptD       | 2         | 0.58%   |
| WOOKING X16         | 1         | 0.29%   |
| TUXEDO Stellaris    | 1         | 0.29%   |
| TUXEDO InfinityBook | 1         | 0.29%   |
| Timi TM1701         | 1         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 48        | 13.99%  |
| 2019 | 38        | 11.08%  |
| 2020 | 29        | 8.45%   |
| 2022 | 27        | 7.87%   |
| 2018 | 24        | 7%      |
| 2023 | 23        | 6.71%   |
| 2011 | 20        | 5.83%   |
| 2024 | 17        | 4.96%   |
| 2017 | 16        | 4.66%   |
| 2012 | 16        | 4.66%   |
| 2015 | 15        | 4.37%   |
| 2014 | 15        | 4.37%   |
| 2013 | 13        | 3.79%   |
| 2016 | 12        | 3.5%    |
| 2008 | 9         | 2.62%   |
| 2025 | 7         | 2.04%   |
| 2010 | 5         | 1.46%   |
| 2007 | 5         | 1.46%   |
| 2009 | 3         | 0.87%   |
| 2006 | 1         | 0.29%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 343       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 296       | 85.8%   |
| Enabled  | 49        | 14.2%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 340       | 99.13%  |
| Yes  | 3         | 0.87%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 90        | 25.71%  |
| 4.01-8.0    | 74        | 21.14%  |
| 8.01-16.0   | 64        | 18.29%  |
| 32.01-64.0  | 49        | 14%     |
| 3.01-4.0    | 42        | 12%     |
| 24.01-32.0  | 13        | 3.71%   |
| 1.01-2.0    | 8         | 2.29%   |
| 64.01-256.0 | 7         | 2%      |
| 2.01-3.0    | 3         | 0.86%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 95        | 24.3%   |
| 2.01-3.0   | 94        | 24.04%  |
| 1.01-2.0   | 88        | 22.51%  |
| 3.01-4.0   | 65        | 16.62%  |
| 8.01-16.0  | 27        | 6.91%   |
| 0.51-1.0   | 13        | 3.32%   |
| 16.01-24.0 | 5         | 1.28%   |
| 24.01-32.0 | 2         | 0.51%   |
| 0.01-0.5   | 2         | 0.51%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 244       | 69.32%  |
| 2      | 90        | 25.57%  |
| 3      | 15        | 4.26%   |
| 0      | 2         | 0.57%   |
| 4      | 1         | 0.28%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 293       | 85.17%  |
| Yes       | 51        | 14.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 224       | 64.93%  |
| No        | 121       | 35.07%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 324       | 94.46%  |
| No        | 19        | 5.54%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 297       | 85.34%  |
| No        | 51        | 14.66%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Singapore | 343       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Singapore            | 335       | 97.38%  |
| Jurong West          | 4         | 1.16%   |
| Yio Chu Kang         | 1         | 0.29%   |
| Sembawang Estate     | 1         | 0.29%   |
| Queenstown Estate    | 1         | 0.29%   |
| Kampong Ulu Jurong   | 1         | 0.29%   |
| Bukit Batok New Town | 1         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 81        | 146    | 17.8%   |
| Sandisk                     | 45        | 65     | 9.89%   |
| WDC                         | 36        | 60     | 7.91%   |
| SK hynix                    | 34        | 37     | 7.47%   |
| Unknown                     | 27        | 42     | 5.93%   |
| Seagate                     | 25        | 32     | 5.49%   |
| Micron Technology           | 22        | 24     | 4.84%   |
| Toshiba                     | 21        | 30     | 4.62%   |
| Intel                       | 15        | 17     | 3.3%    |
| HGST                        | 11        | 16     | 2.42%   |
| KIOXIA                      | 9         | 9      | 1.98%   |
| Hitachi                     | 9         | 9      | 1.98%   |
| Apple                       | 9         | 10     | 1.98%   |
| Crucial                     | 8         | 8      | 1.76%   |
| Kingston                    | 6         | 7      | 1.32%   |
| Yangtze Memory Technologies | 5         | 5      | 1.1%    |
| Phison                      | 5         | 7      | 1.1%    |
| Micron/Crucial Technology   | 5         | 5      | 1.1%    |
| MAXIO Technology (Hangzhou) | 4         | 4      | 0.88%   |
| JMicron Technology          | 4         | 7      | 0.88%   |
| External                    | 4         | 4      | 0.88%   |
| China                       | 4         | 4      | 0.88%   |
| YMTC                        | 3         | 4      | 0.66%   |
| UMIS                        | 3         | 4      | 0.66%   |
| Transcend                   | 3         | 4      | 0.66%   |
| Silicon Motion              | 3         | 5      | 0.66%   |
| Phison Electronics          | 3         | 3      | 0.66%   |
| Kingston Technology Company | 3         | 3      | 0.66%   |
| Union Memory (Shenzhen)     | 2         | 2      | 0.44%   |
| SPCC                        | 2         | 2      | 0.44%   |
| Patriot                     | 2         | 2      | 0.44%   |
| LITEON                      | 2         | 3      | 0.44%   |
| Lexar                       | 2         | 2      | 0.44%   |
| Lenovo                      | 2         | 2      | 0.44%   |
| Hewlett-Packard             | 2         | 3      | 0.44%   |
| FORESEE                     | 2         | 2      | 0.44%   |
| Biwin Storage Technology    | 2         | 2      | 0.44%   |
| ACASIS                      | 2         | 2      | 0.44%   |
| A-DATA Technology           | 2         | 2      | 0.44%   |
| Verbatim                    | 1         | 1      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                        | 7         | 1.48%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 7         | 1.48%   |
| Unknown MMC Card  64GB                                | 6         | 1.27%   |
| Toshiba MQ04ABF100 1TB                                | 5         | 1.05%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 5         | 1.05%   |
| SK hynix SKHynix_HFS001TDE9X084N 1024GB               | 4         | 0.84%   |
| SK hynix HFM001TD3JX013N 1024GB                       | 4         | 0.84%   |
| Samsung SSD 860 EVO 500GB                             | 4         | 0.84%   |
| Samsung NVMe SSD Drive 1024GB                         | 4         | 0.84%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 2TB      | 4         | 0.84%   |
| HGST HTS721010A9E630 1TB                              | 4         | 0.84%   |
| External USB3.0 250GB                                 | 4         | 0.84%   |
| Unknown MMC Card  128GB                               | 3         | 0.63%   |
| Toshiba MQ01ABD100 1TB                                | 3         | 0.63%   |
| SK hynix SKHynix_HFS001TEJ9X115N 1024GB               | 3         | 0.63%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB | 3         | 0.63%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB                 | 3         | 0.63%   |
| SanDisk SSD PLUS 480GB                                | 3         | 0.63%   |
| SanDisk NVMe SSD Drive 512GB                          | 3         | 0.63%   |
| Samsung SSD 860 EVO 250GB                             | 3         | 0.63%   |
| Micron 2210_MTFDHBA512QFD 512GB                       | 3         | 0.63%   |
| JMicron Generic 320GB                                 | 3         | 0.63%   |
| Intel SSD 660P Series 512GB                           | 3         | 0.63%   |
| WDC WDS500G2X0C-00L350 500GB                          | 2         | 0.42%   |
| WDC WDS100T2X0C-00L350 1TB                            | 2         | 0.42%   |
| WDC WD7500BPVT-80HXZT3 752GB                          | 2         | 0.42%   |
| WDC WD5000LPVX-22V0TT0 500GB                          | 2         | 0.42%   |
| WDC WD10SPZX-21Z10T0 1TB                              | 2         | 0.42%   |
| WDC WD10JPVX-22JC3T0 1TB                              | 2         | 0.42%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB                    | 2         | 0.42%   |
| WDC PC SN720 SED SDAQNTW-1T00 1TB                     | 2         | 0.42%   |
| Unknown NVMe SSD Drive 512GB                          | 2         | 0.42%   |
| Unknown NVMe SSD Drive 1TB                            | 2         | 0.42%   |
| Unknown NVMe SSD Drive 1024GB                         | 2         | 0.42%   |
| Unknown MMC Card  32GB                                | 2         | 0.42%   |
| Unknown MMC Card  256GB                               | 2         | 0.42%   |
| UMIS RPEYJ1T24MKN2QWY 1TB                             | 2         | 0.42%   |
| Toshiba MQ01ABF050 500GB                              | 2         | 0.42%   |
| Toshiba MK5055GSX 500GB                               | 2         | 0.42%   |
| SK hynix SKHynix_HFS512GDE9X084N 512GB                | 2         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 22        | 28     | 25.29%  |
| WDC                 | 16        | 21     | 18.39%  |
| Toshiba             | 16        | 24     | 18.39%  |
| HGST                | 11        | 16     | 12.64%  |
| Hitachi             | 9         | 9      | 10.34%  |
| External            | 4         | 4      | 4.6%    |
| JMicron Technology  | 3         | 6      | 3.45%   |
| Unknown             | 1         | 2      | 1.15%   |
| TO Exter            | 1         | 1      | 1.15%   |
| Samsung Electronics | 1         | 3      | 1.15%   |
| SAGE                | 1         | 1      | 1.15%   |
| Fujitsu             | 1         | 1      | 1.15%   |
| Apple               | 1         | 1      | 1.15%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 32        | 84     | 30.77%  |
| SanDisk             | 18        | 29     | 17.31%  |
| Apple               | 7         | 7      | 6.73%   |
| Micron Technology   | 5         | 6      | 4.81%   |
| Crucial             | 5         | 5      | 4.81%   |
| WDC                 | 4         | 5      | 3.85%   |
| SK hynix            | 4         | 4      | 3.85%   |
| China               | 4         | 4      | 3.85%   |
| Transcend           | 3         | 4      | 2.88%   |
| SPCC                | 2         | 2      | 1.92%   |
| Patriot             | 2         | 2      | 1.92%   |
| LITEON              | 2         | 3      | 1.92%   |
| Kingston            | 2         | 3      | 1.92%   |
| FORESEE             | 2         | 2      | 1.92%   |
| Toshiba             | 1         | 1      | 0.96%   |
| Ramos Technology    | 1         | 2      | 0.96%   |
| ORICO               | 1         | 1      | 0.96%   |
| OCZ                 | 1         | 1      | 0.96%   |
| LT                  | 1         | 2      | 0.96%   |
| Lexar               | 1         | 1      | 0.96%   |
| LALAK               | 1         | 1      | 0.96%   |
| Hewlett-Packard     | 1         | 2      | 0.96%   |
| Haizhide            | 1         | 1      | 0.96%   |
| GALAX               | 1         | 1      | 0.96%   |
| CT1000MX            | 1         | 2      | 0.96%   |
| Unknown             | 1         | 1      | 0.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 202       | 300    | 49.51%  |
| SSD     | 97        | 176    | 23.77%  |
| HDD     | 81        | 117    | 19.85%  |
| MMC     | 20        | 31     | 4.9%    |
| Unknown | 8         | 8      | 1.96%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 201       | 288    | 50.76%  |
| SATA | 151       | 274    | 38.13%  |
| SAS  | 24        | 39     | 6.06%   |
| MMC  | 20        | 31     | 5.05%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 119       | 206    | 66.85%  |
| 0.51-1.0   | 52        | 78     | 29.21%  |
| 1.01-2.0   | 7         | 9      | 3.93%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 89        | 24.38%  |
| 251-500        | 87        | 23.84%  |
| 501-1000       | 67        | 18.36%  |
| 1001-2000      | 37        | 10.14%  |
| 51-100         | 26        | 7.12%   |
| 1-20           | 20        | 5.48%   |
| More than 3000 | 12        | 3.29%   |
| 21-50          | 9         | 2.47%   |
| 2001-3000      | 9         | 2.47%   |
| Unknown        | 9         | 2.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 123       | 32.63%  |
| 21-50          | 74        | 19.63%  |
| 101-250        | 54        | 14.32%  |
| 51-100         | 38        | 10.08%  |
| 251-500        | 35        | 9.28%   |
| 501-1000       | 29        | 7.69%   |
| Unknown        | 9         | 2.39%   |
| 1001-2000      | 8         | 2.12%   |
| 2001-3000      | 3         | 0.8%    |
| More than 3000 | 2         | 0.53%   |
| 0              | 2         | 0.53%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                       | Notebooks | Drives | Percent |
|-------------------------------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-22V0TT0 500GB                                | 1         | 1      | 6.67%   |
| WDC WD5000BPVT-16HXZT1 500GB                                | 1         | 1      | 6.67%   |
| WDC WD10SPZX-21Z10T0 1TB                                    | 1         | 2      | 6.67%   |
| SK hynix SC210 2.5 7MM 128GB SSD                            | 1         | 1      | 6.67%   |
| SK hynix PC711 HFS512GDE9X073N 512GB                        | 1         | 1      | 6.67%   |
| Seagate ST9320325AS 320GB                                   | 1         | 1      | 6.67%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                          | 1         | 1      | 6.67%   |
| Seagate ST1000LM024 HN-M 1TB                                | 1         | 1      | 6.67%   |
| SanDisk SSD U100 24GB                                       | 1         | 1      | 6.67%   |
| Samsung Electronics SSD 980 1TB                             | 1         | 1      | 6.67%   |
| MAXIO Technology (Hangzhou) NVMe SSD Controller MAP1202 2TB | 1         | 1      | 6.67%   |
| Hitachi HTS545032B9A300 320GB                               | 1         | 1      | 6.67%   |
| Hitachi HTS541010A9E680 1TB                                 | 1         | 1      | 6.67%   |
| Crucial CT750MX300SSD1 752GB                                | 1         | 1      | 6.67%   |
| China SSD 128GB                                             | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 3         | 4      | 20%     |
| Seagate                     | 3         | 3      | 20%     |
| SK hynix                    | 2         | 2      | 13.33%  |
| Hitachi                     | 2         | 2      | 13.33%  |
| SanDisk                     | 1         | 1      | 6.67%   |
| Samsung Electronics         | 1         | 1      | 6.67%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 6.67%   |
| Crucial                     | 1         | 1      | 6.67%   |
| China                       | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 4      | 37.5%   |
| Seagate | 3         | 3      | 37.5%   |
| Hitachi | 2         | 2      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 9      | 53.33%  |
| SSD  | 4         | 4      | 26.67%  |
| NVMe | 3         | 3      | 20%     |

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
| Detected | 182       | 300    | 49.46%  |
| Works    | 171       | 316    | 46.47%  |
| Malfunc  | 15        | 16     | 4.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 173       | 40.05%  |
| Samsung Electronics                     | 53        | 12.27%  |
| SanDisk                                 | 41        | 9.49%   |
| AMD                                     | 35        | 8.1%    |
| SK hynix                                | 30        | 6.94%   |
| Micron Technology                       | 17        | 3.94%   |
| Phison Electronics                      | 8         | 1.85%   |
| KIOXIA                                  | 8         | 1.85%   |
| Yangtze Memory Technologies             | 7         | 1.62%   |
| Toshiba America Info Systems            | 7         | 1.62%   |
| Micron/Crucial Technology               | 7         | 1.62%   |
| Kingston Technology Company             | 7         | 1.62%   |
| MAXIO Technology (Hangzhou)             | 6         | 1.39%   |
| Silicon Motion                          | 4         | 0.93%   |
| Shenzhen Unionmemory Information System | 4         | 0.93%   |
| ADATA Technology                        | 4         | 0.93%   |
| Shenzhen Longsys Electronics            | 3         | 0.69%   |
| Nvidia                                  | 3         | 0.69%   |
| Union Memory (Shenzhen)                 | 2         | 0.46%   |
| Seagate Technology                      | 2         | 0.46%   |
| Lenovo                                  | 2         | 0.46%   |
| Biwin Storage Technology                | 2         | 0.46%   |
| Transcend                               | 1         | 0.23%   |
| Marvell Technology Group                | 1         | 0.23%   |
| INNOGRIT                                | 1         | 0.23%   |
| Hosin Global Electronics                | 1         | 0.23%   |
| ASMedia Technology                      | 1         | 0.23%   |
| Apple                                   | 1         | 0.23%   |
| Unknown                                 | 1         | 0.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                              | Notebooks | Percent |
|------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                | 34        | 7.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                      | 22        | 4.91%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                 | 21        | 4.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                   | 18        | 4.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller       | 17        | 3.79%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                               | 15        | 3.35%   |
| Intel Volume Management Device NVMe RAID Controller                                | 14        | 3.13%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                     | 12        | 2.68%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                        | 11        | 2.46%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                  | 10        | 2.23%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                     | 9         | 2.01%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD               | 8         | 1.79%   |
| Intel SSD 660P Series                                                              | 8         | 1.79%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                       | 8         | 1.79%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)          | 7         | 1.56%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                             | 7         | 1.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]     | 7         | 1.56%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                                 | 6         | 1.34%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                       | 6         | 1.34%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                        | 6         | 1.34%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                              | 6         | 1.34%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                           | 5         | 1.12%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                         | 5         | 1.12%   |
| Intel Tiger Lake-LP SATA Controller                                                | 5         | 1.12%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]              | 5         | 1.12%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                      | 5         | 1.12%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                   | 5         | 1.12%   |
| Yangtze Memory PC300 M.2 2280 NVMe SSD (DRAM-less)                                 | 4         | 0.89%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                  | 4         | 0.89%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)               | 4         | 0.89%   |
| Micron 2210 NVMe SSD [Cobain]                                                      | 4         | 0.89%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                 | 4         | 0.89%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                             | 4         | 0.89%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                               | 3         | 0.67%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                               | 3         | 0.67%   |
| SK hynix PC611 NVMe Solid State Drive                                              | 3         | 0.67%   |
| SK hynix BC501 NVMe Solid State Drive                                              | 3         | 0.67%   |
| Shenzhen Unionmemory Information System AM6A1 PCIe 4.0 NVMe SSD 1024GB (DRAM-less) | 3         | 0.67%   |
| Sandisk WD Black SN850X NVMe SSD                                                   | 3         | 0.67%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                         | 3         | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 202       | 48.44%  |
| SATA | 174       | 41.73%  |
| RAID | 31        | 7.43%   |
| IDE  | 10        | 2.4%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Intel    | 259       | 75.51%  |
| AMD      | 83        | 24.2%   |
| Qualcomm | 1         | 0.29%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 5800H with Radeon Graphics        | 13        | 3.79%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 10        | 2.92%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 9         | 2.62%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 8         | 2.33%   |
| Intel 12th Gen Core i7-12700H                 | 7         | 2.04%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 6         | 1.75%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 1.75%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 6         | 1.75%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 5         | 1.46%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 5         | 1.46%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 5         | 1.46%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 1.46%   |
| AMD Ryzen 7 8845HS w/ Radeon 780M Graphics    | 5         | 1.46%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.17%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.17%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 1.17%   |
| AMD Custom APU 0405                           | 4         | 1.17%   |
| Intel Core i9-14900HX                         | 3         | 0.87%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 0.87%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 0.87%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 0.87%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 0.87%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 0.87%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 3         | 0.87%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 3         | 0.87%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 0.87%   |
| Intel 13th Gen Core i9-13900HX                | 3         | 0.87%   |
| Intel 12th Gen Core i5-12450H                 | 3         | 0.87%   |
| Intel 11th Gen Core i7-11390H @ 3.40GHz       | 3         | 0.87%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 3         | 0.87%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 0.87%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 0.87%   |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 2         | 0.58%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 2         | 0.58%   |
| Intel Core Ultra 7 258V                       | 2         | 0.58%   |
| Intel Core Ultra 5 125H                       | 2         | 0.58%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.58%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 2         | 0.58%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 0.58%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz            | 2         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 88        | 25.66%  |
| Other                   | 61        | 17.78%  |
| Intel Core i5           | 57        | 16.62%  |
| AMD Ryzen 7             | 35        | 10.2%   |
| AMD Ryzen 5             | 17        | 4.96%   |
| Intel Celeron           | 15        | 4.37%   |
| Intel Core 2 Duo        | 11        | 3.21%   |
| Intel Core              | 7         | 2.04%   |
| AMD Ryzen 7 PRO         | 7         | 2.04%   |
| Intel Core i3           | 6         | 1.75%   |
| Intel Core i9           | 5         | 1.46%   |
| AMD Ryzen 9             | 5         | 1.46%   |
| Intel Xeon              | 4         | 1.17%   |
| Intel Pentium Silver    | 4         | 1.17%   |
| Intel Atom              | 4         | 1.17%   |
| Intel Pentium Dual      | 2         | 0.58%   |
| Intel Core m3           | 2         | 0.58%   |
| AMD Ryzen 3             | 2         | 0.58%   |
| AMD E2                  | 2         | 0.58%   |
| Intel Core 2            | 1         | 0.29%   |
| AMD Turion 64 X2 Mobile | 1         | 0.29%   |
| AMD Ryzen 5 PRO         | 1         | 0.29%   |
| AMD PRO A10             | 1         | 0.29%   |
| AMD E1                  | 1         | 0.29%   |
| AMD E                   | 1         | 0.29%   |
| AMD Athlon              | 1         | 0.29%   |
| AMD A8                  | 1         | 0.29%   |
| AMD A6                  | 1         | 0.29%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 114       | 33.24%  |
| 2      | 107       | 31.2%   |
| 8      | 60        | 17.49%  |
| 6      | 26        | 7.58%   |
| 14     | 15        | 4.37%   |
| 24     | 7         | 2.04%   |
| 10     | 5         | 1.46%   |
| 16     | 4         | 1.17%   |
| 12     | 3         | 0.87%   |
| 1      | 2         | 0.58%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 341       | 99.42%  |
| 16     | 1         | 0.29%   |
| 2      | 1         | 0.29%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 284       | 82.08%  |
| 1      | 62        | 17.92%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 338       | 98.54%  |
| 32-bit         | 2         | 0.58%   |
| Unknown        | 2         | 0.58%   |
| 64-bit         | 1         | 0.29%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 163       | 45.53%  |
| 0x806ea    | 14        | 3.91%   |
| 0x806ec    | 13        | 3.63%   |
| 0x206a7    | 13        | 3.63%   |
| 0x306a9    | 12        | 3.35%   |
| 0x0a50000c | 11        | 3.07%   |
| 0x906ea    | 10        | 2.79%   |
| 0x806c1    | 9         | 2.51%   |
| 0x40651    | 7         | 1.96%   |
| 0x806e9    | 6         | 1.68%   |
| 0x306d4    | 6         | 1.68%   |
| 0x806eb    | 5         | 1.4%    |
| 0x6fd      | 5         | 1.4%    |
| 0x806d1    | 4         | 1.12%   |
| 0x506e3    | 4         | 1.12%   |
| 0x406e3    | 4         | 1.12%   |
| 0x1067a    | 4         | 1.12%   |
| 0x08108109 | 4         | 1.12%   |
| 0xa0652    | 3         | 0.84%   |
| 0x806c2    | 3         | 0.84%   |
| 0x706e5    | 3         | 0.84%   |
| 0x706a1    | 3         | 0.84%   |
| 0x40661    | 3         | 0.84%   |
| 0x306c3    | 3         | 0.84%   |
| 0x20655    | 3         | 0.84%   |
| 0x0a404102 | 3         | 0.84%   |
| 0x08600106 | 3         | 0.84%   |
| 0x906e9    | 2         | 0.56%   |
| 0x906c0    | 2         | 0.56%   |
| 0x906a3    | 2         | 0.56%   |
| 0x706a8    | 2         | 0.56%   |
| 0x406c3    | 2         | 0.56%   |
| 0x30678    | 2         | 0.56%   |
| 0x106c2    | 2         | 0.56%   |
| 0x0a404101 | 2         | 0.56%   |
| 0x08600103 | 2         | 0.56%   |
| 0x08108102 | 2         | 0.56%   |
| 0x06006705 | 2         | 0.56%   |
| 0xb06a2    | 1         | 0.28%   |
| 0xb0671    | 1         | 0.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 68        | 19.83%  |
| Unknown           | 49        | 14.29%  |
| Zen 3             | 22        | 6.41%   |
| Haswell           | 21        | 6.12%   |
| Alderlake Hybrid  | 20        | 5.83%   |
| TigerLake         | 19        | 5.54%   |
| SandyBridge       | 18        | 5.25%   |
| IvyBridge         | 18        | 5.25%   |
| Skylake           | 12        | 3.5%    |
| Zen+              | 10        | 2.92%   |
| Icelake           | 10        | 2.92%   |
| Zen 2             | 9         | 2.62%   |
| Broadwell         | 9         | 2.62%   |
| Penryn            | 7         | 2.04%   |
| Goldmont plus     | 7         | 2.04%   |
| Core              | 7         | 2.04%   |
| CometLake         | 7         | 2.04%   |
| Silvermont        | 6         | 1.75%   |
| Excavator         | 4         | 1.17%   |
| Westmere          | 3         | 0.87%   |
| Tremont           | 3         | 0.87%   |
| Puma              | 2         | 0.58%   |
| Meteorlake Hybrid | 2         | 0.58%   |
| Goldmont          | 2         | 0.58%   |
| Bonnell           | 2         | 0.58%   |
| Bobcat            | 2         | 0.58%   |
| Zen               | 1         | 0.29%   |
| K8 Hammer         | 1         | 0.29%   |
| Jaguar            | 1         | 0.29%   |
| Gracemont         | 1         | 0.29%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 246       | 52.34%  |
| Nvidia | 138       | 29.36%  |
| AMD    | 86        | 18.3%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                  | 18        | 3.72%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 18        | 3.72%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 17        | 3.51%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 17        | 3.51%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 17        | 3.51%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 13        | 2.69%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 11        | 2.27%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 11        | 2.27%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 11        | 2.27%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 11        | 2.27%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 10        | 2.07%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]               | 9         | 1.86%   |
| AMD Rembrandt [Radeon 680M]                                               | 9         | 1.86%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                   | 8         | 1.65%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 7         | 1.45%   |
| Nvidia GP108BM [GeForce MX250]                                            | 7         | 1.45%   |
| Intel Raptor Lake-S UHD Graphics                                          | 7         | 1.45%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 7         | 1.45%   |
| Nvidia GP108M [GeForce MX150]                                             | 6         | 1.24%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                     | 6         | 1.24%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                    | 6         | 1.24%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 6         | 1.24%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 6         | 1.24%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 6         | 1.24%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                  | 6         | 1.24%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 6         | 1.24%   |
| AMD HawkPoint1                                                            | 6         | 1.24%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 5         | 1.03%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                           | 5         | 1.03%   |
| Intel Iris Plus Graphics G7                                               | 5         | 1.03%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 5         | 1.03%   |
| Intel Alder Lake-P GT1 [UHD Graphics]                                     | 5         | 1.03%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 4         | 0.83%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                           | 4         | 0.83%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                     | 4         | 0.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 4         | 0.83%   |
| AMD VanGogh [AMD Custom GPU 0405]                                         | 4         | 0.83%   |
| AMD Phoenix1                                                              | 4         | 0.83%   |
| AMD Lucienne                                                              | 4         | 0.83%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 3         | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 138       | 40.12%  |
| Intel + Nvidia     | 98        | 28.49%  |
| 1 x AMD            | 53        | 15.41%  |
| 1 x Nvidia         | 20        | 5.81%   |
| AMD + Nvidia       | 19        | 5.52%   |
| Intel + AMD        | 8         | 2.33%   |
| 2 x AMD            | 5         | 1.45%   |
| Other              | 1         | 0.29%   |
| 2 x Intel          | 1         | 0.29%   |
| Intel + 2 x Nvidia | 1         | 0.29%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 265       | 75.93%  |
| Proprietary | 68        | 19.48%  |
| Unknown     | 16        | 4.58%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 247       | 69.38%  |
| 0.01-0.5   | 35        | 9.83%   |
| 1.01-2.0   | 33        | 9.27%   |
| 3.01-4.0   | 19        | 5.34%   |
| 0.51-1.0   | 8         | 2.25%   |
| 7.01-8.0   | 6         | 1.69%   |
| 5.01-6.0   | 6         | 1.69%   |
| 2.01-3.0   | 1         | 0.28%   |
| 8.01-16.0  | 1         | 0.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 80        | 19.9%   |
| BOE                 | 56        | 13.93%  |
| Samsung Electronics | 48        | 11.94%  |
| Chimei Innolux      | 39        | 9.7%    |
| LG Display          | 37        | 9.2%    |
| Dell                | 18        | 4.48%   |
| Apple               | 17        | 4.23%   |
| Sharp               | 15        | 3.73%   |
| Philips             | 9         | 2.24%   |
| CSO                 | 8         | 1.99%   |
| Acer                | 8         | 1.99%   |
| Lenovo              | 7         | 1.74%   |
| Goldstar            | 6         | 1.49%   |
| InfoVision          | 5         | 1.24%   |
| Valve               | 4         | 1%      |
| PANDA               | 4         | 1%      |
| CSOT                | 4         | 1%      |
| TMA                 | 3         | 0.75%   |
| Hewlett-Packard     | 3         | 0.75%   |
| YMK                 | 2         | 0.5%    |
| TMX                 | 2         | 0.5%    |
| Mi                  | 2         | 0.5%    |
| LG Philips          | 2         | 0.5%    |
| BenQ                | 2         | 0.5%    |
| VXN                 | 1         | 0.25%   |
| ViewSonic           | 1         | 0.25%   |
| Toshiba             | 1         | 0.25%   |
| Tianma XM           | 1         | 0.25%   |
| SZL                 | 1         | 0.25%   |
| Sony                | 1         | 0.25%   |
| SNR                 | 1         | 0.25%   |
| SKG                 | 1         | 0.25%   |
| JDI                 | 1         | 0.25%   |
| IPS                 | 1         | 0.25%   |
| HKC                 | 1         | 0.25%   |
| EXP                 | 1         | 0.25%   |
| DMS                 | 1         | 0.25%   |
| Denver              | 1         | 0.25%   |
| DENON               | 1         | 0.25%   |
| CVT                 | 1         | 0.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                    | 4         | 0.99%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch           | 4         | 0.99%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch         | 4         | 0.99%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch  | 3         | 0.74%   |
| Hewlett-Packard 23es HWP331E 1920x1080 509x286mm 23.0-inch             | 3         | 0.74%   |
| Dell S2340L DELD058 1920x1080 509x286mm 23.0-inch                      | 3         | 0.74%   |
| Dell P2421D DELD0FF 2560x1440 527x296mm 23.8-inch                      | 3         | 0.74%   |
| AU Optronics LCD Monitor AUO408D 1920x1080 309x174mm 14.0-inch         | 3         | 0.74%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch          | 3         | 0.74%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                   | 3         | 0.74%   |
| YMK EM160 TOUCH YMK4A68 2880x1800 342x220mm 16.0-inch                  | 2         | 0.49%   |
| TMA TL140ADXP24-0 TMA2004 2880x1800 300x190mm 14.0-inch                | 2         | 0.49%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch   | 2         | 0.49%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch   | 2         | 0.49%   |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch  | 2         | 0.49%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 2         | 0.49%   |
| Samsung Electronics ATNA60CL10-0 SDC41AF 2880x1800 344x215mm 16.0-inch | 2         | 0.49%   |
| Philips 227E4QH PHLC0AA 1920x1080 477x268mm 21.5-inch                  | 2         | 0.49%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 2         | 0.49%   |
| LG Philips LCD Monitor LPL8D00 1280x800 304x190mm 14.1-inch            | 2         | 0.49%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch           | 2         | 0.49%   |
| Lenovo LCD Monitor LEN8AB1 3072x1920 312x195mm 14.5-inch               | 2         | 0.49%   |
| Chimei Innolux N156HMA-GA1 CMN1556 1920x1080 344x193mm 15.5-inch       | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch       | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch       | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch       | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch        | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch       | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch        | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch        | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN1354 1920x1080 293x165mm 13.2-inch       | 2         | 0.49%   |
| BOE LCD Monitor BOE0A3B 2560x1600 344x215mm 16.0-inch                  | 2         | 0.49%   |
| BOE LCD Monitor BOE09C3 1366x768 256x144mm 11.6-inch                   | 2         | 0.49%   |
| BOE LCD Monitor BOE09B6 2560x1600 345x215mm 16.0-inch                  | 2         | 0.49%   |
| BOE LCD Monitor BOE06A7 1920x1080 294x165mm 13.3-inch                  | 2         | 0.49%   |
| AU Optronics LCD Monitor AUO413D 1920x1080 309x174mm 14.0-inch         | 2         | 0.49%   |
| AU Optronics LCD Monitor AUO3892 1920x1080 344x194mm 15.5-inch         | 2         | 0.49%   |
| AU Optronics LCD Monitor AUO343C 1366x768 309x173mm 13.9-inch          | 2         | 0.49%   |
| AU Optronics LCD Monitor AUO31EB 3840x2160 344x193mm 15.5-inch         | 2         | 0.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 163       | 43.7%   |
| 1366x768 (WXGA)    | 57        | 15.28%  |
| 2560x1600          | 22        | 5.9%    |
| 2880x1800          | 20        | 5.36%   |
| 3840x2160 (4K)     | 19        | 5.09%   |
| 2560x1440 (QHD)    | 19        | 5.09%   |
| 1920x1200 (WUXGA)  | 15        | 4.02%   |
| 1280x800 (WXGA)    | 14        | 3.75%   |
| 3840x2400          | 5         | 1.34%   |
| 3440x1440          | 5         | 1.34%   |
| 800x1280           | 4         | 1.07%   |
| 3072x1920          | 4         | 1.07%   |
| 1440x900 (WXGA+)   | 4         | 1.07%   |
| 3000x2000          | 3         | 0.8%    |
| 1600x900 (HD+)     | 3         | 0.8%    |
| 3200x1800 (QHD+)   | 2         | 0.54%   |
| 2520x1680          | 2         | 0.54%   |
| 2240x1400          | 2         | 0.54%   |
| 1360x768           | 2         | 0.54%   |
| Unknown            | 2         | 0.54%   |
| 3200x2000          | 1         | 0.27%   |
| 2048x1280          | 1         | 0.27%   |
| 1920x515           | 1         | 0.27%   |
| 1680x1050 (WSXGA+) | 1         | 0.27%   |
| 1280x1024 (SXGA)   | 1         | 0.27%   |
| 1024x600           | 1         | 0.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 98        | 24.62%  |
| 13      | 82        | 20.6%   |
| 14      | 71        | 17.84%  |
| 16      | 30        | 7.54%   |
| 27      | 19        | 4.77%   |
| 12      | 13        | 3.27%   |
| 24      | 12        | 3.02%   |
| 23      | 12        | 3.02%   |
| 11      | 12        | 3.02%   |
| 21      | 10        | 2.51%   |
| 17      | 6         | 1.51%   |
| 34      | 4         | 1.01%   |
| 7       | 4         | 1.01%   |
| Unknown | 4         | 1.01%   |
| 31      | 3         | 0.75%   |
| 19      | 3         | 0.75%   |
| 18      | 3         | 0.75%   |
| 40      | 2         | 0.5%    |
| 32      | 2         | 0.5%    |
| 65      | 1         | 0.25%   |
| 54      | 1         | 0.25%   |
| 52      | 1         | 0.25%   |
| 42      | 1         | 0.25%   |
| 36      | 1         | 0.25%   |
| 35      | 1         | 0.25%   |
| 10      | 1         | 0.25%   |
| 8       | 1         | 0.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 224       | 57%     |
| 201-300     | 75        | 19.08%  |
| 501-600     | 41        | 10.43%  |
| 401-500     | 14        | 3.56%   |
| 351-400     | 13        | 3.31%   |
| 701-800     | 7         | 1.78%   |
| 1-100       | 4         | 1.02%   |
| Unknown     | 4         | 1.02%   |
| 801-900     | 3         | 0.76%   |
| 601-700     | 3         | 0.76%   |
| 1001-1500   | 3         | 0.76%   |
| 101-200     | 1         | 0.25%   |
| 901-1000    | 1         | 0.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 248       | 70.25%  |
| 16/10   | 84        | 23.8%   |
| 3/2     | 7         | 1.98%   |
| 21/9    | 5         | 1.42%   |
| 0.67    | 4         | 1.13%   |
| Unknown | 2         | 0.57%   |
| 5/4     | 1         | 0.28%   |
| 3.73    | 1         | 0.28%   |
| 0.62    | 1         | 0.28%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 117       | 29.7%   |
| 101-110        | 97        | 24.62%  |
| 71-80          | 30        | 7.61%   |
| 111-120        | 30        | 7.61%   |
| 201-250        | 29        | 7.36%   |
| 301-350        | 19        | 4.82%   |
| 61-70          | 13        | 3.3%    |
| 51-60          | 12        | 3.05%   |
| 351-500        | 10        | 2.54%   |
| 91-100         | 6         | 1.52%   |
| 1-40           | 5         | 1.27%   |
| 121-130        | 5         | 1.27%   |
| 151-200        | 4         | 1.02%   |
| 501-1000       | 4         | 1.02%   |
| Unknown        | 4         | 1.02%   |
| More than 1000 | 3         | 0.76%   |
| 141-150        | 3         | 0.76%   |
| 41-50          | 1         | 0.25%   |
| 251-300        | 1         | 0.25%   |
| 131-140        | 1         | 0.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 154       | 39.9%   |
| 161-240       | 79        | 20.47%  |
| 101-120       | 67        | 17.36%  |
| 51-100        | 45        | 11.66%  |
| More than 240 | 33        | 8.55%   |
| 1-50          | 4         | 1.04%   |
| Unknown       | 4         | 1.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 276       | 77.97%  |
| 2     | 62        | 17.51%  |
| 0     | 10        | 2.82%   |
| 3     | 6         | 1.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 198       | 39.6%   |
| Realtek Semiconductor                  | 139       | 27.8%   |
| Qualcomm Atheros                       | 53        | 10.6%   |
| Broadcom                               | 27        | 5.4%    |
| MediaTek                               | 25        | 5%      |
| ASIX Electronics                       | 13        | 2.6%    |
| Broadcom Limited                       | 7         | 1.4%    |
| Qualcomm                               | 6         | 1.2%    |
| Shenzhen Goodix Technology             | 5         | 1%      |
| Marvell Technology Group               | 4         | 0.8%    |
| Ralink Technology                      | 3         | 0.6%    |
| Suzhou Motorcomm Electronic Technology | 2         | 0.4%    |
| Sierra Wireless                        | 2         | 0.4%    |
| Google                                 | 2         | 0.4%    |
| Xiaomi                                 | 1         | 0.2%    |
| Samsung Electronics                    | 1         | 0.2%    |
| Realtek                                | 1         | 0.2%    |
| Ralink                                 | 1         | 0.2%    |
| Qualcomm Technologies                  | 1         | 0.2%    |
| Nvidia                                 | 1         | 0.2%    |
| MosChip Semiconductor                  | 1         | 0.2%    |
| Linksys                                | 1         | 0.2%    |
| Lenovo                                 | 1         | 0.2%    |
| Hewlett-Packard                        | 1         | 0.2%    |
| Edimax Technology                      | 1         | 0.2%    |
| Dell                                   | 1         | 0.2%    |
| D-Link                                 | 1         | 0.2%    |
| Apple                                  | 1         | 0.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 80        | 13.56%  |
| Intel Wi-Fi 6 AX200                                                    | 25        | 4.24%   |
| Intel Wi-Fi 6 AX201                                                    | 18        | 3.05%   |
| Intel Wireless 7265                                                    | 15        | 2.54%   |
| Intel Wireless 8265 / 8275                                             | 14        | 2.37%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 14        | 2.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 13        | 2.2%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 12        | 2.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 12        | 2.03%   |
| ASIX AX88179 Gigabit Ethernet                                          | 12        | 2.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 11        | 1.86%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 11        | 1.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 10        | 1.69%   |
| Intel Wireless 7260                                                    | 9         | 1.53%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 9         | 1.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 8         | 1.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 8         | 1.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 7         | 1.19%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 7         | 1.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7         | 1.19%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 6         | 1.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 6         | 1.02%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 6         | 1.02%   |
| Intel Wireless 3165                                                    | 6         | 1.02%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 6         | 1.02%   |
| Intel Ethernet Connection (4) I219-LM                                  | 6         | 1.02%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 6         | 1.02%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 6         | 1.02%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 6         | 1.02%   |
| Shenzhen Goodix Fingerprint Reader                                     | 5         | 0.85%   |
| Realtek RTL8125 2.5GbE Controller                                      | 5         | 0.85%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 5         | 0.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 5         | 0.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 5         | 0.85%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 5         | 0.85%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 4         | 0.68%   |
| Intel Wireless 8260                                                    | 4         | 0.68%   |
| Intel Ethernet Connection (3) I218-LM                                  | 4         | 0.68%   |
| Intel 700 Series Chipset CNVi WiFi                                     | 4         | 0.68%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                            | 4         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 188       | 55.46%  |
| Qualcomm Atheros      | 47        | 13.86%  |
| Realtek Semiconductor | 38        | 11.21%  |
| MediaTek              | 23        | 6.78%   |
| Broadcom              | 20        | 5.9%    |
| Qualcomm              | 6         | 1.77%   |
| Broadcom Limited      | 5         | 1.47%   |
| Ralink Technology     | 3         | 0.88%   |
| Sierra Wireless       | 2         | 0.59%   |
| Realtek               | 1         | 0.29%   |
| Ralink                | 1         | 0.29%   |
| Qualcomm Technologies | 1         | 0.29%   |
| Hewlett-Packard       | 1         | 0.29%   |
| Edimax Technology     | 1         | 0.29%   |
| Dell                  | 1         | 0.29%   |
| D-Link                | 1         | 0.29%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                           | Notebooks | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                             | 25        | 7.31%   |
| Intel Wi-Fi 6 AX201                                                             | 18        | 5.26%   |
| Intel Wireless 7265                                                             | 15        | 4.39%   |
| Intel Wireless 8265 / 8275                                                      | 14        | 4.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                      | 12        | 3.51%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                      | 11        | 3.22%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]            | 11        | 3.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                               | 10        | 2.92%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                | 10        | 2.92%   |
| Intel Wireless 7260                                                             | 9         | 2.63%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                        | 9         | 2.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                | 8         | 2.34%   |
| Intel Cannon Lake PCH CNVi WiFi                                                 | 8         | 2.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                        | 7         | 2.05%   |
| Intel Raptor Lake PCH CNVi WiFi                                                 | 7         | 2.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                        | 6         | 1.75%   |
| Intel Wireless 3165                                                             | 6         | 1.75%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                 | 6         | 1.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                    | 6         | 1.75%   |
| Broadcom BCM4331 802.11a/b/g/n                                                  | 6         | 1.75%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                     | 5         | 1.46%   |
| Qualcomm QCNFA765 Wireless Network Adapter                                      | 5         | 1.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                      | 5         | 1.46%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                  | 5         | 1.46%   |
| Intel Comet Lake PCH CNVi WiFi                                                  | 5         | 1.46%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                        | 4         | 1.17%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                   | 4         | 1.17%   |
| Intel Wireless 8260                                                             | 4         | 1.17%   |
| Intel 700 Series Chipset CNVi WiFi                                              | 4         | 1.17%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                     | 4         | 1.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                 | 3         | 0.88%   |
| Realtek 802.11ac NIC                                                            | 3         | 0.88%   |
| MediaTek MT7925 802.11be 160MHz 2x2 PCIe Wireless Network Adapter [Filogic 360] | 3         | 0.88%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                         | 3         | 0.88%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                       | 3         | 0.88%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                         | 3         | 0.88%   |
| Intel Tiger Lake PCH CNVi WiFi                                                  | 3         | 0.88%   |
| Intel Jasper Lake PCH CNVi WiFi                                                 | 3         | 0.88%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter            | 3         | 0.88%   |
| Sierra Wireless EM7455                                                          | 2         | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 119       | 49.79%  |
| Intel                                  | 61        | 25.52%  |
| Broadcom                               | 14        | 5.86%   |
| Qualcomm Atheros                       | 13        | 5.44%   |
| ASIX Electronics                       | 13        | 5.44%   |
| Marvell Technology Group               | 4         | 1.67%   |
| Suzhou Motorcomm Electronic Technology | 2         | 0.84%   |
| MediaTek                               | 2         | 0.84%   |
| Google                                 | 2         | 0.84%   |
| Broadcom Limited                       | 2         | 0.84%   |
| Xiaomi                                 | 1         | 0.42%   |
| Samsung Electronics                    | 1         | 0.42%   |
| Nvidia                                 | 1         | 0.42%   |
| MosChip Semiconductor                  | 1         | 0.42%   |
| Linksys                                | 1         | 0.42%   |
| Lenovo                                 | 1         | 0.42%   |
| Apple                                  | 1         | 0.42%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 80        | 32.92%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 13        | 5.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 12        | 4.94%   |
| ASIX AX88179 Gigabit Ethernet                                          | 12        | 4.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7         | 2.88%   |
| Intel Ethernet Connection (4) I219-LM                                  | 6         | 2.47%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 6         | 2.47%   |
| Realtek RTL8125 2.5GbE Controller                                      | 5         | 2.06%   |
| Intel Ethernet Connection (3) I218-LM                                  | 4         | 1.65%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 4         | 1.65%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 3         | 1.23%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 3         | 1.23%   |
| Intel Ethernet Connection I218-LM                                      | 3         | 1.23%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 1.23%   |
| Intel Ethernet Connection (7) I219-V                                   | 3         | 1.23%   |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 1.23%   |
| Intel 82567LM Gigabit Network Connection                               | 3         | 1.23%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 3         | 1.23%   |
| Suzhou Motorcomm Electronic YT6801 Gigabit Ethernet Controller         | 2         | 0.82%   |
| Realtek PCIe GbE Family Controller                                     | 2         | 0.82%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 2         | 0.82%   |
| Realtek Killer E2600 GbE Controller                                    | 2         | 0.82%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 0.82%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 2         | 0.82%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 2         | 0.82%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 2         | 0.82%   |
| Intel Wi-Fi 7(802.11be) AX1775*/AX1790*/BE20*/BE401/BE1750* 2x2        | 2         | 0.82%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 0.82%   |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 0.82%   |
| Intel Ethernet Connection (14) I219-LM                                 | 2         | 0.82%   |
| Intel Ethernet Connection (10) I219-V                                  | 2         | 0.82%   |
| Intel BE201 320MHz                                                     | 2         | 0.82%   |
| Intel 82579V Gigabit Network Connection                                | 2         | 0.82%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 2         | 0.82%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.41%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.41%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller            | 1         | 0.41%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1         | 0.41%   |
| Realtek Killer E5000 5GbE Controller                                   | 1         | 0.41%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 325       | 58.66%  |
| Ethernet | 224       | 40.43%  |
| Modem    | 5         | 0.9%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 284       | 77.81%  |
| Ethernet | 81        | 22.19%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 181       | 52.62%  |
| 1     | 157       | 45.64%  |
| 3     | 3         | 0.87%   |
| 0     | 3         | 0.87%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 311       | 90.41%  |
| Yes  | 33        | 9.59%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 169       | 55.96%  |
| IMC Networks                    | 28        | 9.27%   |
| Foxconn / Hon Hai               | 19        | 6.29%   |
| Qualcomm Atheros Communications | 18        | 5.96%   |
| Apple                           | 15        | 4.97%   |
| Realtek Semiconductor           | 13        | 4.3%    |
| Lite-On Technology              | 13        | 4.3%    |
| Broadcom                        | 9         | 2.98%   |
| MediaTek                        | 4         | 1.32%   |
| USI                             | 3         | 0.99%   |
| Chicony Electronics             | 2         | 0.66%   |
| Cambridge Silicon Radio         | 2         | 0.66%   |
| Toshiba                         | 1         | 0.33%   |
| Realtek                         | 1         | 0.33%   |
| Ralink Technology               | 1         | 0.33%   |
| Foxconn International           | 1         | 0.33%   |
| Dell                            | 1         | 0.33%   |
| Askey Computer                  | 1         | 0.33%   |
| Alps Electric                   | 1         | 0.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 47        | 15.56%  |
| Intel Bluetooth wireless interface                  | 44        | 14.57%  |
| Intel Bluetooth Device                              | 24        | 7.95%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 24        | 7.95%   |
| Intel AX200 Bluetooth                               | 22        | 7.28%   |
| IMC Networks Bluetooth Radio                        | 12        | 3.97%   |
| Realtek Bluetooth Radio                             | 11        | 3.64%   |
| IMC Networks Wireless_Device                        | 8         | 2.65%   |
| Apple Bluetooth Host Controller                     | 8         | 2.65%   |
| Apple Bluetooth USB Host Controller                 | 7         | 2.32%   |
| Qualcomm Atheros  Bluetooth Device                  | 6         | 1.99%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 6         | 1.99%   |
| IMC Networks Bluetooth Device                       | 5         | 1.66%   |
| Foxconn / Hon Hai Wireless_Device                   | 5         | 1.66%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 1.66%   |
| MediaTek Wireless_Device                            | 4         | 1.32%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 4         | 1.32%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 1.32%   |
| USI Bluetooth Device                                | 3         | 0.99%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 0.99%   |
| Lite-On Wireless_Device                             | 3         | 0.99%   |
| Lite-On Atheros Bluetooth                           | 3         | 0.99%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 0.99%   |
| Intel AX210 Bluetooth                               | 3         | 0.99%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.66%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 0.66%   |
| Lite-On Bluetooth Radio                             | 2         | 0.66%   |
| Lite-On Bluetooth Device                            | 2         | 0.66%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 0.66%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 2         | 0.66%   |
| Chicony Bluetooth (RTL8723BE)                       | 2         | 0.66%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 0.66%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 0.66%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 0.66%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.33%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.33%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 0.33%   |
| Realtek Bluetooth Radio                             | 1         | 0.33%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.33%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 254       | 58.12%  |
| AMD                   | 85        | 19.45%  |
| Nvidia                | 75        | 17.16%  |
| Plantronics           | 2         | 0.46%   |
| Lenovo                | 2         | 0.46%   |
| Kingston Technology   | 2         | 0.46%   |
| C-Media Electronics   | 2         | 0.46%   |
| Apple                 | 2         | 0.46%   |
| Tenx Technology       | 1         | 0.23%   |
| Sennheiser electronic | 1         | 0.23%   |
| SAVITECH              | 1         | 0.23%   |
| Razer USA             | 1         | 0.23%   |
| Quanta                | 1         | 0.23%   |
| Logitech              | 1         | 0.23%   |
| Jieli Technology      | 1         | 0.23%   |
| JBL                   | 1         | 0.23%   |
| GN Netcom             | 1         | 0.23%   |
| Elgato Systems        | 1         | 0.23%   |
| Cooler Master         | 1         | 0.23%   |
| Conexant Systems      | 1         | 0.23%   |
| ASUSTek Computer      | 1         | 0.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                              | 70        | 13.11%  |
| Intel Sunrise Point-LP HD Audio                                            | 35        | 6.55%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 26        | 4.87%   |
| AMD Radeon High Definition Audio Controller                                | 25        | 4.68%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 19        | 3.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 19        | 3.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 17        | 3.18%   |
| Intel Cannon Lake PCH cAVS                                                 | 15        | 2.81%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 14        | 2.62%   |
| Intel Comet Lake PCH-LP cAVS                                               | 12        | 2.25%   |
| Nvidia GA106 High Definition Audio Controller                              | 11        | 2.06%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11        | 2.06%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 11        | 2.06%   |
| Intel Haswell-ULT HD Audio Controller                                      | 10        | 1.87%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 10        | 1.87%   |
| Intel 8 Series HD Audio Controller                                         | 10        | 1.87%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 9         | 1.69%   |
| Intel Broadwell-U Audio Controller                                         | 9         | 1.69%   |
| Nvidia GA107 High Definition Audio Controller                              | 7         | 1.31%   |
| Nvidia GA104 High Definition Audio Controller                              | 7         | 1.31%   |
| Nvidia AD107 High Definition Audio Controller                              | 7         | 1.31%   |
| Intel Raptor Lake High Definition Audio Controller                         | 7         | 1.31%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 7         | 1.31%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 1.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6         | 1.12%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 6         | 1.12%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 6         | 1.12%   |
| Intel Comet Lake PCH cAVS                                                  | 6         | 1.12%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 6         | 1.12%   |
| Nvidia GF108 High Definition Audio Controller                              | 5         | 0.94%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 0.94%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 0.94%   |
| Nvidia TU104 HD Audio Controller                                           | 4         | 0.75%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 0.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 4         | 0.75%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 0.75%   |
| AMD FCH Azalia Controller                                                  | 4         | 0.75%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 0.75%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 0.56%   |
| Nvidia GB206 High Definition Audio Controller                              | 3         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 67        | 26.07%  |
| Samsung Electronics | 65        | 25.29%  |
| Micron Technology   | 45        | 17.51%  |
| Kingston            | 20        | 7.78%   |
| Crucial             | 19        | 7.39%   |
| Unknown             | 11        | 4.28%   |
| Ramaxel Technology  | 5         | 1.95%   |
| Unknown (ABCD)      | 3         | 1.17%   |
| Transcend           | 3         | 1.17%   |
| Elpida              | 3         | 1.17%   |
| A-DATA Technology   | 3         | 1.17%   |
| Unknown             | 3         | 1.17%   |
| Nanya Technology    | 2         | 0.78%   |
| V-GeN               | 1         | 0.39%   |
| Team                | 1         | 0.39%   |
| Super Talent        | 1         | 0.39%   |
| Patriot             | 1         | 0.39%   |
| Lexar               | 1         | 0.39%   |
| Corsair             | 1         | 0.39%   |
| Carry               | 1         | 0.39%   |
| ASint Technology    | 1         | 0.39%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s            | 6         | 2.21%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s            | 4         | 1.47%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s            | 4         | 1.47%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s             | 4         | 1.47%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s               | 3         | 1.1%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s  | 3         | 1.1%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 3         | 1.1%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s            | 3         | 1.1%    |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s           | 3         | 1.1%    |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s  | 3         | 1.1%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s             | 3         | 1.1%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s             | 3         | 1.1%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s              | 3         | 1.1%    |
| Unknown                                                           | 3         | 1.1%    |
| Unknown RAM Module 4GB SODIMM DDR3                                | 2         | 0.74%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 2         | 0.74%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                      | 2         | 0.74%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s            | 2         | 0.74%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 2667MT/s            | 2         | 0.74%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s           | 2         | 0.74%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s            | 2         | 0.74%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s           | 2         | 0.74%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s            | 2         | 0.74%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s            | 2         | 0.74%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 1GB Row Of Chips LPDDR4 4267MT/s    | 2         | 0.74%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB SODIMM LPDDR5 6400MT/s        | 2         | 0.74%   |
| SK hynix RAM H9HCNNNCPMALHR-NEE 8GiB Row Of Chips LPDDR4 4800MT/s | 2         | 0.74%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s        | 2         | 0.74%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                      | 2         | 0.74%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s             | 2         | 0.74%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s             | 2         | 0.74%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s             | 2         | 0.74%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s            | 2         | 0.74%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s            | 2         | 0.74%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s            | 2         | 0.74%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s            | 2         | 0.74%   |
| Micron RAM Module 4GB Row Of Chips LPDDR5 8533MT/s                | 2         | 0.74%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s              | 2         | 0.74%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s              | 2         | 0.74%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s              | 2         | 0.74%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 93        | 43.46%  |
| DDR3   | 48        | 22.43%  |
| LPDDR5 | 22        | 10.28%  |
| DDR5   | 19        | 8.88%   |
| LPDDR4 | 17        | 7.94%   |
| LPDDR3 | 13        | 6.07%   |
| SDRAM  | 1         | 0.47%   |
| DDR2   | 1         | 0.47%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 168       | 78.14%  |
| Row Of Chips | 44        | 20.47%  |
| Chip         | 2         | 0.93%   |
| Unknown      | 1         | 0.47%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 100       | 41.67%  |
| 4096  | 54        | 22.5%   |
| 16384 | 53        | 22.08%  |
| 32768 | 14        | 5.83%   |
| 2048  | 14        | 5.83%   |
| 1024  | 3         | 1.25%   |
| 12288 | 1         | 0.42%   |
| 3072  | 1         | 0.42%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 54        | 23.28%  |
| 2667    | 39        | 16.81%  |
| 1600    | 36        | 15.52%  |
| 5600    | 11        | 4.74%   |
| 4267    | 11        | 4.74%   |
| 2400    | 11        | 4.74%   |
| 2133    | 11        | 4.74%   |
| 4800    | 10        | 4.31%   |
| 6400    | 9         | 3.88%   |
| 7500    | 8         | 3.45%   |
| 1333    | 6         | 2.59%   |
| 1334    | 4         | 1.72%   |
| 1867    | 3         | 1.29%   |
| 8533    | 2         | 0.86%   |
| 8400    | 2         | 0.86%   |
| 7467    | 2         | 0.86%   |
| 3266    | 2         | 0.86%   |
| 1067    | 2         | 0.86%   |
| Unknown | 2         | 0.86%   |
| 8000    | 1         | 0.43%   |
| 7400    | 1         | 0.43%   |
| 4199    | 1         | 0.43%   |
| 2933    | 1         | 0.43%   |
| 1200    | 1         | 0.43%   |
| 800     | 1         | 0.43%   |
| 667     | 1         | 0.43%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 1         | 50%     |
| Brother Industries | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| HP Ink Tank Wireless 410 series | 1         | 50%     |
| Brother DCP-L2535DW series      | 1         | 50%     |

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
| Chicony Electronics                    | 68        | 22.74%  |
| IMC Networks                           | 45        | 15.05%  |
| Microdia                               | 32        | 10.7%   |
| Realtek Semiconductor                  | 23        | 7.69%   |
| Bison Electronics                      | 21        | 7.02%   |
| Sunplus Innovation Technology          | 15        | 5.02%   |
| Luxvisions Innotech Limited            | 10        | 3.34%   |
| Syntek                                 | 9         | 3.01%   |
| Quanta                                 | 9         | 3.01%   |
| Suyin                                  | 7         | 2.34%   |
| Sonix Technology                       | 7         | 2.34%   |
| Apple                                  | 7         | 2.34%   |
| Samsung Electronics                    | 5         | 1.67%   |
| Lite-On Technology                     | 5         | 1.67%   |
| SunplusIT                              | 4         | 1.34%   |
| ShineTech                              | 4         | 1.34%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 1.34%   |
| OmniVision Technologies                | 3         | 1%      |
| Logitech                               | 3         | 1%      |
| Silicon Motion                         | 2         | 0.67%   |
| Ricoh                                  | 2         | 0.67%   |
| Alcor Micro                            | 2         | 0.67%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.33%   |
| ShineOptics                            | 1         | 0.33%   |
| Shine-optics                           | 1         | 0.33%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.33%   |
| Magic Control Technology               | 1         | 0.33%   |
| Lenovo                                 | 1         | 0.33%   |
| kingcome                               | 1         | 0.33%   |
| Intel                                  | 1         | 0.33%   |
| Importek                               | 1         | 0.33%   |
| HYGD-220831-A                          | 1         | 0.33%   |
| Acer                                   | 1         | 0.33%   |
| Unknown                                | 1         | 0.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                     | 20        | 6.62%   |
| IMC Networks Integrated Camera                    | 14        | 4.64%   |
| Chicony Integrated Camera                         | 14        | 4.64%   |
| Chicony HD Webcam                                 | 13        | 4.3%    |
| IMC Networks USB2.0 HD UVC WebCam                 | 10        | 3.31%   |
| Bison Integrated Camera                           | 9         | 2.98%   |
| Syntek Integrated Camera                          | 7         | 2.32%   |
| Sunplus Integrated_Webcam_HD                      | 7         | 2.32%   |
| Realtek Integrated_Webcam_HD                      | 7         | 2.32%   |
| IMC Networks USB2.0 VGA UVC WebCam                | 7         | 2.32%   |
| Luxvisions Innotech Limited Integrated Camera     | 6         | 1.99%   |
| Samsung Galaxy series, misc. (MTP mode)           | 5         | 1.66%   |
| IMC Networks USB2.0 HD IR UVC WebCam              | 5         | 1.66%   |
| Apple FaceTime HD Camera                          | 5         | 1.66%   |
| Lite-On Integrated Camera                         | 4         | 1.32%   |
| Chicony HP HD Camera                              | 4         | 1.32%   |
| Sonix USB2.0 HD UVC WebCam                        | 3         | 0.99%   |
| Sonix USB2.0 FHD UVC WebCam                       | 3         | 0.99%   |
| OmniVision OV2640 Webcam                          | 3         | 0.99%   |
| Chicony USB2.0 HD UVC WebCam                      | 3         | 0.99%   |
| Chicony Lenovo Integrated Camera (0.3MP)          | 3         | 0.99%   |
| Chicony HP Wide Vision HD Camera                  | 3         | 0.99%   |
| Chicony HD User Facing                            | 3         | 0.99%   |
| Chicony Chicony USB2.0 Camera                     | 3         | 0.99%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera  | 3         | 0.99%   |
| Bison HD Webcam                                   | 3         | 0.99%   |
| Syntek Lenovo EasyCamera                          | 2         | 0.66%   |
| SunplusIT HD Webcam                               | 2         | 0.66%   |
| Shinetech ASUS FHD webcam                         | 2         | 0.66%   |
| Realtek Integrated Webcam_HD                      | 2         | 0.66%   |
| Realtek Asus 2.0 USB Webcam                       | 2         | 0.66%   |
| Quanta HD Webcam                                  | 2         | 0.66%   |
| Quanta HD User Facing                             | 2         | 0.66%   |
| Microdia USB 2.0 Camera                           | 2         | 0.66%   |
| Microdia Sonix USB 2.0 Camera                     | 2         | 0.66%   |
| Microdia Integrated_Webcam_FHD                    | 2         | 0.66%   |
| Microdia Integrated Webcam                        | 2         | 0.66%   |
| Microdia HDE Webcam USB                           | 2         | 0.66%   |
| Luxvisions Innotech Limited Integrated RGB Camera | 2         | 0.66%   |
| IMC Networks Lenovo EasyCamera                    | 2         | 0.66%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 21        | 28%     |
| Validity Sensors                   | 13        | 17.33%  |
| Shenzhen Goodix Technology         | 10        | 13.33%  |
| LighTuning Technology              | 9         | 12%     |
| Elan Microelectronics              | 7         | 9.33%   |
| Upek                               | 6         | 8%      |
| AuthenTec                          | 6         | 8%      |
| Realtek USB2.0 Finger Print Bridge | 2         | 2.67%   |
| Focal-systems.Corp                 | 1         | 1.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 12        | 16%     |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 9         | 12%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 8%      |
| Elan ELAN:Fingerprint                                                      | 5         | 6.67%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 5.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 5.33%   |
| Shenzhen Goodix  Fingerprint Device                                        | 4         | 5.33%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 5.33%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 4%      |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 2.67%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 2.67%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 2.67%   |
| Elan ELAN:ARM-M4                                                           | 2         | 2.67%   |
| AuthenTec AES2810                                                          | 2         | 2.67%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 2.67%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.33%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.33%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.33%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.33%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 1.33%   |
| Synaptics UWP WBDI Device                                                  | 1         | 1.33%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.33%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 1.33%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 1.33%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.33%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.33%   |
| Unknown                                                                    | 1         | 1.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 8         | 80%     |
| Alcor Micro | 2         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard) | 4         | 40%     |
| Broadcom BCM5880 Secure Applications Processor                              | 3         | 30%     |
| Alcor Micro AU9540 Smartcard Reader                                         | 2         | 20%     |
| Broadcom 5880                                                               | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 207       | 57.5%   |
| 1     | 115       | 31.94%  |
| 2     | 32        | 8.89%   |
| 3     | 4         | 1.11%   |
| 5     | 1         | 0.28%   |
| 4     | 1         | 0.28%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 70        | 36.27%  |
| Graphics card            | 53        | 27.46%  |
| Net/wireless             | 19        | 9.84%   |
| Multimedia controller    | 15        | 7.77%   |
| Chipcard                 | 9         | 4.66%   |
| Camera                   | 9         | 4.66%   |
| Communication controller | 7         | 3.63%   |
| Net/ethernet             | 5         | 2.59%   |
| Bluetooth                | 2         | 1.04%   |
| Wireless                 | 1         | 0.52%   |
| Storage/raid             | 1         | 0.52%   |
| Sound                    | 1         | 0.52%   |
| Firewire controller      | 1         | 0.52%   |


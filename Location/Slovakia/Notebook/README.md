Linux in Slovakia - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Slovakia.

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

Total: 1118

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Pavilion dv6                | [3d1becb26c](https://linux-hardware.org/?probe=3d1becb26c) | Dec 31, 2025 |
| HP            | Pavilion dv6                | [28336e5980](https://linux-hardware.org/?probe=28336e5980) | Dec 31, 2025 |
| Lenovo        | ThinkPad X13 Gen 4 21J3C... | [50ca8779bd](https://linux-hardware.org/?probe=50ca8779bd) | Dec 26, 2025 |
| ASUSTek       | Vivobook Go E1504GA_E150... | [6ea2602e42](https://linux-hardware.org/?probe=6ea2602e42) | Dec 26, 2025 |
| Lenovo        | ThinkPad T495 20NKS1ER02    | [ca8b4720f4](https://linux-hardware.org/?probe=ca8b4720f4) | Dec 25, 2025 |
| MSI           | Katana GF66 11UE            | [cdf9653561](https://linux-hardware.org/?probe=cdf9653561) | Dec 24, 2025 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [3428f63516](https://linux-hardware.org/?probe=3428f63516) | Dec 22, 2025 |
| ASUSTek       | Vivobook Go E1504GA_E150... | [47c43543c1](https://linux-hardware.org/?probe=47c43543c1) | Dec 21, 2025 |
| MSI           | GT70 2PC                    | [ffd88a8766](https://linux-hardware.org/?probe=ffd88a8766) | Dec 20, 2025 |
| MSI           | GT70 2PC                    | [46b50d223b](https://linux-hardware.org/?probe=46b50d223b) | Dec 16, 2025 |
| Dell          | Latitude 3590               | [4a78a84e96](https://linux-hardware.org/?probe=4a78a84e96) | Dec 10, 2025 |
| Dell          | Latitude 3590               | [19f6cb8294](https://linux-hardware.org/?probe=19f6cb8294) | Dec 10, 2025 |
| Lenovo        | ThinkPad P14s Gen 6 AMD ... | [49b3373121](https://linux-hardware.org/?probe=49b3373121) | Dec 10, 2025 |
| Apple         | MacBookPro11,5              | [824ede1d91](https://linux-hardware.org/?probe=824ede1d91) | Dec 09, 2025 |
| Acer          | Predator PH315-55           | [4cd4aed2f1](https://linux-hardware.org/?probe=4cd4aed2f1) | Dec 06, 2025 |
| ASUSTek       | ASUS EXPERTBOOK P5405CSA    | [fe1fa1e6b2](https://linux-hardware.org/?probe=fe1fa1e6b2) | Dec 01, 2025 |
| Lenovo        | ThinkPad X13 Gen 4 21J3C... | [538788c9f9](https://linux-hardware.org/?probe=538788c9f9) | Nov 27, 2025 |
| GPD           | G1628-04                    | [5a80bbc96b](https://linux-hardware.org/?probe=5a80bbc96b) | Nov 23, 2025 |
| SIEMENS       | SIMATIC Field PG M2         | [eca5a420e8](https://linux-hardware.org/?probe=eca5a420e8) | Nov 21, 2025 |
| HP            | Pavilion dv6                | [733a0d47da](https://linux-hardware.org/?probe=733a0d47da) | Nov 14, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [b400280b08](https://linux-hardware.org/?probe=b400280b08) | Nov 10, 2025 |
| Acer          | Aspire V5-551G              | [58868d504d](https://linux-hardware.org/?probe=58868d504d) | Nov 10, 2025 |
| Acer          | Aspire V5-551G              | [b0f55686e1](https://linux-hardware.org/?probe=b0f55686e1) | Nov 10, 2025 |
| Lenovo        | Legion Slim 5 16ARP9 83E... | [3777ff31c3](https://linux-hardware.org/?probe=3777ff31c3) | Nov 08, 2025 |
| Toshiba       | Satellite Pro C50-A-1EP     | [28fd7ffbe5](https://linux-hardware.org/?probe=28fd7ffbe5) | Nov 07, 2025 |
| Dell          | Vostro 15 3515              | [ffd6ef88da](https://linux-hardware.org/?probe=ffd6ef88da) | Nov 01, 2025 |
| MSI           | Thin A15 B7VE               | [13ecdcb65b](https://linux-hardware.org/?probe=13ecdcb65b) | Oct 30, 2025 |
| Dell          | Latitude 5450               | [64c4a45bd4](https://linux-hardware.org/?probe=64c4a45bd4) | Oct 28, 2025 |
| Lenovo        | ThinkPad P14s Gen 6 AMD ... | [d435b3c0f8](https://linux-hardware.org/?probe=d435b3c0f8) | Oct 28, 2025 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [00efe581c1](https://linux-hardware.org/?probe=00efe581c1) | Oct 22, 2025 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [a94fdc541c](https://linux-hardware.org/?probe=a94fdc541c) | Oct 22, 2025 |
| Fujitsu Si... | AMILO A7645                 | [bfb4443389](https://linux-hardware.org/?probe=bfb4443389) | Oct 14, 2025 |
| Fujitsu       | LIFEBOOK E5512A             | [066101c67a](https://linux-hardware.org/?probe=066101c67a) | Oct 14, 2025 |
| Dell          | Latitude E7250              | [ce8f12b0c0](https://linux-hardware.org/?probe=ce8f12b0c0) | Oct 13, 2025 |
| Dell          | Latitude 5591               | [b0ef0ca78b](https://linux-hardware.org/?probe=b0ef0ca78b) | Oct 13, 2025 |
| Dell          | Latitude 5591               | [d727b8f8ec](https://linux-hardware.org/?probe=d727b8f8ec) | Oct 13, 2025 |
| Acer          | Aspire V3-771               | [5cad34f243](https://linux-hardware.org/?probe=5cad34f243) | Oct 13, 2025 |
| Acer          | Aspire V3-771               | [8233fc3cbb](https://linux-hardware.org/?probe=8233fc3cbb) | Oct 13, 2025 |
| HP            | Compaq 610                  | [a9e1169b4a](https://linux-hardware.org/?probe=a9e1169b4a) | Oct 11, 2025 |
| HP            | Pavilion dv6                | [b7d1434bb9](https://linux-hardware.org/?probe=b7d1434bb9) | Oct 08, 2025 |
| HP            | Pavilion dv6                | [aec082d61a](https://linux-hardware.org/?probe=aec082d61a) | Oct 08, 2025 |
| HP            | 250 G5 Notebook PC          | [f9763be764](https://linux-hardware.org/?probe=f9763be764) | Oct 05, 2025 |
| Dell          | Latitude 5290 2-in-1        | [4ce59f6623](https://linux-hardware.org/?probe=4ce59f6623) | Oct 05, 2025 |
| Lenovo        | IdeaPad Pro 5 14IAH10 83... | [7ed6b7b04a](https://linux-hardware.org/?probe=7ed6b7b04a) | Oct 03, 2025 |
| Lenovo        | IdeaPad Pro 5 14IAH10 83... | [c73493b54c](https://linux-hardware.org/?probe=c73493b54c) | Oct 03, 2025 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [08ff5c44d7](https://linux-hardware.org/?probe=08ff5c44d7) | Oct 02, 2025 |
| ASUSTek       | G751JY                      | [339328a6f3](https://linux-hardware.org/?probe=339328a6f3) | Oct 02, 2025 |
| HP            | EliteBook 8440p             | [49d7df7ffe](https://linux-hardware.org/?probe=49d7df7ffe) | Sep 28, 2025 |
| HP            | EliteBook 845 G8 Noteboo... | [e17d4bfcbf](https://linux-hardware.org/?probe=e17d4bfcbf) | Sep 26, 2025 |
| Intel         | CHERRYVIEW D1 PLATFORM      | [6584fd39bf](https://linux-hardware.org/?probe=6584fd39bf) | Sep 26, 2025 |
| Dell          | Latitude 5450               | [4a1dacb0e5](https://linux-hardware.org/?probe=4a1dacb0e5) | Sep 23, 2025 |
| Lenovo        | ThinkPad Edge E530 3259C... | [c8b48cbec5](https://linux-hardware.org/?probe=c8b48cbec5) | Sep 22, 2025 |
| Dell          | Latitude E5470              | [15fa5d7f44](https://linux-hardware.org/?probe=15fa5d7f44) | Sep 21, 2025 |
| Dell          | Latitude 3510               | [dd16b51671](https://linux-hardware.org/?probe=dd16b51671) | Sep 21, 2025 |
| Dell          | Latitude 5580               | [091733527d](https://linux-hardware.org/?probe=091733527d) | Sep 21, 2025 |
| Dell          | Latitude 5590               | [8d850d6e9c](https://linux-hardware.org/?probe=8d850d6e9c) | Sep 21, 2025 |
| Lenovo        | Legion 7 16IAX10 83KY       | [8baa5ebaba](https://linux-hardware.org/?probe=8baa5ebaba) | Sep 18, 2025 |
| MSI           | GX701                       | [72ec6bf202](https://linux-hardware.org/?probe=72ec6bf202) | Sep 09, 2025 |
| HP            | ProBook 430 G1              | [7ee751f6e7](https://linux-hardware.org/?probe=7ee751f6e7) | Sep 04, 2025 |
| Acer          | Aspire 5250                 | [a3a73df4fa](https://linux-hardware.org/?probe=a3a73df4fa) | Sep 03, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [3e972409be](https://linux-hardware.org/?probe=3e972409be) | Sep 02, 2025 |
| Chuwi         | GemiBook                    | [0031b00ba6](https://linux-hardware.org/?probe=0031b00ba6) | Sep 02, 2025 |
| HP            | Stream Laptop 14-ds0xxx     | [266bad0d8c](https://linux-hardware.org/?probe=266bad0d8c) | Aug 30, 2025 |
| HP            | Stream Laptop 14-ds0xxx     | [e7e079a82e](https://linux-hardware.org/?probe=e7e079a82e) | Aug 29, 2025 |
| HP            | ProBook 650 G4              | [242d396e2d](https://linux-hardware.org/?probe=242d396e2d) | Aug 24, 2025 |
| Dell          | XPS 14 9440                 | [697ac285c1](https://linux-hardware.org/?probe=697ac285c1) | Aug 19, 2025 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [b038d9743e](https://linux-hardware.org/?probe=b038d9743e) | Aug 18, 2025 |
| HP            | ENVY Laptop 13-ad1xx        | [f296c2d8c3](https://linux-hardware.org/?probe=f296c2d8c3) | Aug 16, 2025 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [60fc6d703e](https://linux-hardware.org/?probe=60fc6d703e) | Aug 16, 2025 |
| Acer          | Aspire E3-112               | [a308b64758](https://linux-hardware.org/?probe=a308b64758) | Aug 08, 2025 |
| ASUSTek       | ROG Strix SCAR 16 G635LW... | [f2e24d0d51](https://linux-hardware.org/?probe=f2e24d0d51) | Aug 07, 2025 |
| HP            | Pavilion dv6                | [6e0d4c6a16](https://linux-hardware.org/?probe=6e0d4c6a16) | Aug 07, 2025 |
| HP            | Pavilion dv6                | [d01e450a30](https://linux-hardware.org/?probe=d01e450a30) | Aug 06, 2025 |
| Packard Be... | EasyNote TK85               | [839b4dc13b](https://linux-hardware.org/?probe=839b4dc13b) | Aug 06, 2025 |
| Lenovo        | ThinkPad L470 20J4000LMD    | [e47442b5de](https://linux-hardware.org/?probe=e47442b5de) | Aug 01, 2025 |
| Dell          | Latitude E5450              | [7c855fccc1](https://linux-hardware.org/?probe=7c855fccc1) | Jul 29, 2025 |
| HP            | ZBook 15 G3                 | [a338f5638d](https://linux-hardware.org/?probe=a338f5638d) | Jul 28, 2025 |
| Lenovo        | ThinkPad T560 20FJS40100    | [5504716d07](https://linux-hardware.org/?probe=5504716d07) | Jul 25, 2025 |
| Dell          | Latitude E7250              | [ef7a871962](https://linux-hardware.org/?probe=ef7a871962) | Jul 20, 2025 |
| Dell          | Latitude 5590               | [f895eac556](https://linux-hardware.org/?probe=f895eac556) | Jul 19, 2025 |
| Dell          | Latitude 5300               | [23d0a35db9](https://linux-hardware.org/?probe=23d0a35db9) | Jul 17, 2025 |
| Dell          | Latitude 5300               | [37b9ddc0af](https://linux-hardware.org/?probe=37b9ddc0af) | Jul 17, 2025 |
| HP            | 250 G7 Notebook PC          | [ac1b487166](https://linux-hardware.org/?probe=ac1b487166) | Jul 16, 2025 |
| MSI           | Summit E13FlipEvo A12MT     | [a56034e62e](https://linux-hardware.org/?probe=a56034e62e) | Jul 14, 2025 |
| ASUSTek       | N750JV                      | [3ac14a7b34](https://linux-hardware.org/?probe=3ac14a7b34) | Jul 12, 2025 |
| ASUSTek       | N71Ja                       | [0f337bb6c2](https://linux-hardware.org/?probe=0f337bb6c2) | Jul 11, 2025 |
| ASUSTek       | N71Ja                       | [2d2cf28cd5](https://linux-hardware.org/?probe=2d2cf28cd5) | Jul 11, 2025 |
| ASUSTek       | F5VL                        | [92ca2d7600](https://linux-hardware.org/?probe=92ca2d7600) | Jul 11, 2025 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | [51908164d1](https://linux-hardware.org/?probe=51908164d1) | Jul 09, 2025 |
| ASUSTek       | N750JV                      | [7fd9c3383f](https://linux-hardware.org/?probe=7fd9c3383f) | Jul 09, 2025 |
| HP            | 250 G7 Notebook PC          | [456d5a2fcc](https://linux-hardware.org/?probe=456d5a2fcc) | Jul 06, 2025 |
| Dell          | Latitude E7250              | [db37a38dc6](https://linux-hardware.org/?probe=db37a38dc6) | Jul 04, 2025 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [2aafb5929c](https://linux-hardware.org/?probe=2aafb5929c) | Jul 01, 2025 |
| Lenovo        | IdeaPad 1 14ALC7 82R3       | [998aaa0ad7](https://linux-hardware.org/?probe=998aaa0ad7) | Jul 01, 2025 |
| Dell          | Latitude 7490               | [ade19baefc](https://linux-hardware.org/?probe=ade19baefc) | Jun 29, 2025 |
| HP            | EliteBook 8560p             | [3cdff34f13](https://linux-hardware.org/?probe=3cdff34f13) | Jun 29, 2025 |
| HP            | 250 G7 Notebook PC          | [c641bb1b40](https://linux-hardware.org/?probe=c641bb1b40) | Jun 15, 2025 |
| Lenovo        | ThinkPad L540 20AUS0KN00    | [d177fe32f3](https://linux-hardware.org/?probe=d177fe32f3) | Jun 09, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [dc7f3bc6ec](https://linux-hardware.org/?probe=dc7f3bc6ec) | Jun 04, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [ad9d0c98aa](https://linux-hardware.org/?probe=ad9d0c98aa) | Jun 04, 2025 |
| Lenovo        | Legion Pro 7 16IAX10H 83... | [89f26e8c66](https://linux-hardware.org/?probe=89f26e8c66) | May 30, 2025 |
| HP            | Laptop 15s-fq3xxx           | [dd3b0fd7b1](https://linux-hardware.org/?probe=dd3b0fd7b1) | May 20, 2025 |
| ASUSTek       | ROG Zephyrus G16 GU603VI... | [baa0d334ab](https://linux-hardware.org/?probe=baa0d334ab) | May 15, 2025 |
| HP            | 250 G7 Notebook PC          | [b9f1632b1c](https://linux-hardware.org/?probe=b9f1632b1c) | May 14, 2025 |
| Acer          | Aspire VN7-792G             | [d51b370004](https://linux-hardware.org/?probe=d51b370004) | May 12, 2025 |
| HP            | Laptop 15-bs1xx             | [b21d182b39](https://linux-hardware.org/?probe=b21d182b39) | May 12, 2025 |
| HP            | Laptop 15-bs1xx             | [04b5d1100b](https://linux-hardware.org/?probe=04b5d1100b) | May 12, 2025 |
| MSI           | GT60 2OC/2OD                | [0a9d7a2b34](https://linux-hardware.org/?probe=0a9d7a2b34) | May 12, 2025 |
| Lenovo        | Legion 5 17ARH05H 82GN      | [f2933cfa87](https://linux-hardware.org/?probe=f2933cfa87) | Apr 29, 2025 |
| Dell          | Vostro 15 3515              | [907cf313cd](https://linux-hardware.org/?probe=907cf313cd) | Apr 28, 2025 |
| Dell          | Latitude 5480               | [9b2b522849](https://linux-hardware.org/?probe=9b2b522849) | Apr 23, 2025 |
| HP            | ProBook 450 G8 Notebook ... | [264a594839](https://linux-hardware.org/?probe=264a594839) | Apr 22, 2025 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [6490815b8a](https://linux-hardware.org/?probe=6490815b8a) | Apr 22, 2025 |
| TUXEDO        | Sirius 16 Gen1              | [cd10f8d239](https://linux-hardware.org/?probe=cd10f8d239) | Apr 21, 2025 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [664f90ac17](https://linux-hardware.org/?probe=664f90ac17) | Apr 21, 2025 |
| Acer          | Aspire A515-47              | [a2adba1de3](https://linux-hardware.org/?probe=a2adba1de3) | Apr 17, 2025 |
| Acer          | Aspire A515-47              | [aee7738522](https://linux-hardware.org/?probe=aee7738522) | Apr 17, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [eef3cf635c](https://linux-hardware.org/?probe=eef3cf635c) | Apr 16, 2025 |
| HP            | Pavilion dv6                | [bd7ca8a0e7](https://linux-hardware.org/?probe=bd7ca8a0e7) | Apr 12, 2025 |
| HP            | Pavilion dv6                | [a544c67e79](https://linux-hardware.org/?probe=a544c67e79) | Apr 10, 2025 |
| Acer          | Aspire 6920                 | [968a6ffce2](https://linux-hardware.org/?probe=968a6ffce2) | Apr 09, 2025 |
| HP            | ProBook 4530s               | [c5a459946a](https://linux-hardware.org/?probe=c5a459946a) | Apr 09, 2025 |
| Lenovo        | ThinkPad Edge E431 62774... | [9938e4a2b9](https://linux-hardware.org/?probe=9938e4a2b9) | Apr 05, 2025 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [3678d0d2be](https://linux-hardware.org/?probe=3678d0d2be) | Apr 05, 2025 |
| MSI           | GT60 2OC/2OD                | [f9d02b9f80](https://linux-hardware.org/?probe=f9d02b9f80) | Mar 31, 2025 |
| Lenovo        | Flex 2 Pro-15 80K8          | [9e0f280202](https://linux-hardware.org/?probe=9e0f280202) | Mar 29, 2025 |
| ASUSTek       | ROG Zephyrus G16 GU605MY... | [4d1596992f](https://linux-hardware.org/?probe=4d1596992f) | Mar 29, 2025 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [a8c42905a7](https://linux-hardware.org/?probe=a8c42905a7) | Mar 28, 2025 |
| Lenovo        | ThinkPad X200 7458CU2       | [cffed3fa6d](https://linux-hardware.org/?probe=cffed3fa6d) | Mar 28, 2025 |
| HP            | ProBook 4510s               | [ed83f78ccb](https://linux-hardware.org/?probe=ed83f78ccb) | Mar 27, 2025 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [ba516a497e](https://linux-hardware.org/?probe=ba516a497e) | Mar 23, 2025 |
| METAPHYUNI    | MetawillBook03              | [291dc33b5f](https://linux-hardware.org/?probe=291dc33b5f) | Mar 22, 2025 |
| Lenovo        | G500 20236                  | [b47f403d4d](https://linux-hardware.org/?probe=b47f403d4d) | Mar 15, 2025 |
| HP            | 250 15.6 inch G10 Notebo... | [128df29c0f](https://linux-hardware.org/?probe=128df29c0f) | Mar 11, 2025 |
| Lenovo        | ThinkPad T430 2347AH7       | [6a24f8c5db](https://linux-hardware.org/?probe=6a24f8c5db) | Mar 06, 2025 |
| Lenovo        | ThinkPad Z13 Gen 2 21JVC... | [5d9e8d5abf](https://linux-hardware.org/?probe=5d9e8d5abf) | Mar 05, 2025 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [7157515442](https://linux-hardware.org/?probe=7157515442) | Mar 04, 2025 |
| Acer          | Aspire A515-47              | [511e6a036d](https://linux-hardware.org/?probe=511e6a036d) | Mar 02, 2025 |
| Acer          | Aspire V3-731               | [1e7bbb9752](https://linux-hardware.org/?probe=1e7bbb9752) | Feb 27, 2025 |
| Acer          | Aspire V3-731               | [bacb48484e](https://linux-hardware.org/?probe=bacb48484e) | Feb 25, 2025 |
| Lenovo        | G500 20236                  | [2bed3a3053](https://linux-hardware.org/?probe=2bed3a3053) | Feb 24, 2025 |
| Acer          | Aspire A515-47              | [e33305f6d0](https://linux-hardware.org/?probe=e33305f6d0) | Feb 23, 2025 |
| HP            | OMEN by Laptop 15-dc0xxx    | [033339457c](https://linux-hardware.org/?probe=033339457c) | Feb 22, 2025 |
| Lenovo        | G550 20023                  | [833aae39d5](https://linux-hardware.org/?probe=833aae39d5) | Feb 22, 2025 |
| ASUSTek       | M70Vr                       | [6a5de626a3](https://linux-hardware.org/?probe=6a5de626a3) | Feb 21, 2025 |
| Lenovo        | ThinkPad X270 20HMS7TJ01    | [d77efcb350](https://linux-hardware.org/?probe=d77efcb350) | Feb 20, 2025 |
| HP            | ProBook 450 G6              | [fdcaa89b37](https://linux-hardware.org/?probe=fdcaa89b37) | Feb 20, 2025 |
| Lenovo        | G550 20023                  | [f9f8de8a01](https://linux-hardware.org/?probe=f9f8de8a01) | Feb 19, 2025 |
| Lenovo        | ThinkPad L480 20LS0016MC    | [e6c4d3ee92](https://linux-hardware.org/?probe=e6c4d3ee92) | Feb 16, 2025 |
| Dell          | Latitude E5430 non-vPro     | [5072f6ae3b](https://linux-hardware.org/?probe=5072f6ae3b) | Feb 15, 2025 |
| Lenovo        | ThinkPad L480 20LS0016MC    | [44528952ab](https://linux-hardware.org/?probe=44528952ab) | Feb 15, 2025 |
| Dell          | Latitude E5430 non-vPro     | [cfe97ceb23](https://linux-hardware.org/?probe=cfe97ceb23) | Feb 13, 2025 |
| ASUSTek       | G551JM                      | [93e6855ae7](https://linux-hardware.org/?probe=93e6855ae7) | Feb 13, 2025 |
| Lenovo        | ThinkPad T480 20L6SB7M00    | [e3390322c0](https://linux-hardware.org/?probe=e3390322c0) | Feb 12, 2025 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [865bc88f6b](https://linux-hardware.org/?probe=865bc88f6b) | Feb 09, 2025 |
| Dell          | Latitude E7250              | [3473bcef36](https://linux-hardware.org/?probe=3473bcef36) | Feb 09, 2025 |
| Acer          | Swift SF114-34              | [031300eaaf](https://linux-hardware.org/?probe=031300eaaf) | Feb 08, 2025 |
| Lenovo        | G50-30 80G0                 | [75b3eee2d5](https://linux-hardware.org/?probe=75b3eee2d5) | Feb 04, 2025 |
| Lenovo        | ThinkPad T480 20L6SB7M00    | [fd0a430644](https://linux-hardware.org/?probe=fd0a430644) | Feb 03, 2025 |
| HP            | Pavilion dv6                | [fe23780b39](https://linux-hardware.org/?probe=fe23780b39) | Feb 01, 2025 |
| HP            | Pavilion dv6                | [3a7c3b9648](https://linux-hardware.org/?probe=3a7c3b9648) | Feb 01, 2025 |
| Apple         | MacBookPro8,3               | [cb543048e9](https://linux-hardware.org/?probe=cb543048e9) | Feb 01, 2025 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [8e03ef4728](https://linux-hardware.org/?probe=8e03ef4728) | Jan 31, 2025 |
| Dell          | Latitude 5590               | [dc4ba405fb](https://linux-hardware.org/?probe=dc4ba405fb) | Jan 31, 2025 |
| Dell          | Latitude 7490               | [653768d449](https://linux-hardware.org/?probe=653768d449) | Jan 31, 2025 |
| Lenovo        | ThinkPad X270 20HMS7TJ01    | [d5522bd684](https://linux-hardware.org/?probe=d5522bd684) | Jan 30, 2025 |
| Dell          | Latitude 3510               | [a54e325519](https://linux-hardware.org/?probe=a54e325519) | Jan 30, 2025 |
| Dell          | Latitude 5580               | [e9dc7c3e68](https://linux-hardware.org/?probe=e9dc7c3e68) | Jan 29, 2025 |
| Intel         | Jasper Lake Client Platf... | [87a112adb8](https://linux-hardware.org/?probe=87a112adb8) | Jan 29, 2025 |
| Intel         | Jasper Lake Client Platf... | [8d0ef6f42b](https://linux-hardware.org/?probe=8d0ef6f42b) | Jan 28, 2025 |
| Acer          | Nitro AN16-42               | [c431688386](https://linux-hardware.org/?probe=c431688386) | Jan 27, 2025 |
| ASUSTek       | ASUS EXPERTBOOK B5404CMA... | [b0f60fc604](https://linux-hardware.org/?probe=b0f60fc604) | Jan 23, 2025 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [b833ba2c07](https://linux-hardware.org/?probe=b833ba2c07) | Jan 21, 2025 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [dad69e65f4](https://linux-hardware.org/?probe=dad69e65f4) | Jan 20, 2025 |
| Dell          | G5 5587                     | [ac5a10727b](https://linux-hardware.org/?probe=ac5a10727b) | Jan 19, 2025 |
| Dell          | Latitude 5500               | [decfec2fc9](https://linux-hardware.org/?probe=decfec2fc9) | Jan 17, 2025 |
| Lenovo        | B70-80 80MR                 | [46a2dfb5a3](https://linux-hardware.org/?probe=46a2dfb5a3) | Jan 17, 2025 |
| Acer          | Aspire V3-571G              | [cc238493c1](https://linux-hardware.org/?probe=cc238493c1) | Jan 12, 2025 |
| Lenovo        | G580                        | [27bcf4c155](https://linux-hardware.org/?probe=27bcf4c155) | Jan 10, 2025 |
| HP            | ProBook 4510s               | [d74e06d912](https://linux-hardware.org/?probe=d74e06d912) | Jan 06, 2025 |
| HP            | ProBook 4510s               | [cf51ebf11d](https://linux-hardware.org/?probe=cf51ebf11d) | Jan 06, 2025 |
| HP            | 250 G7 Notebook PC          | [0562d753f2](https://linux-hardware.org/?probe=0562d753f2) | Jan 05, 2025 |
| HP            | 250 G7 Notebook PC          | [0cf6343ea2](https://linux-hardware.org/?probe=0cf6343ea2) | Jan 05, 2025 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [271c85b332](https://linux-hardware.org/?probe=271c85b332) | Jan 05, 2025 |
| Lenovo        | ThinkPad L470 20J4000LMD    | [e2fa70f2b4](https://linux-hardware.org/?probe=e2fa70f2b4) | Jan 02, 2025 |
| HP            | ProBook 4535s               | [e0f48651c0](https://linux-hardware.org/?probe=e0f48651c0) | Dec 30, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [71d10a1993](https://linux-hardware.org/?probe=71d10a1993) | Dec 26, 2024 |
| Lenovo        | IdeaPad Pro 5 16AHP9 83D... | [28dcf6960e](https://linux-hardware.org/?probe=28dcf6960e) | Dec 26, 2024 |
| Lenovo        | Legion 9 16IRX9 83G0        | [128debb210](https://linux-hardware.org/?probe=128debb210) | Dec 25, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [4505762848](https://linux-hardware.org/?probe=4505762848) | Dec 25, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [e7ad20e4e1](https://linux-hardware.org/?probe=e7ad20e4e1) | Dec 24, 2024 |
| HP            | Pavilion dv6                | [89ec19d64a](https://linux-hardware.org/?probe=89ec19d64a) | Dec 17, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [532c74b6c3](https://linux-hardware.org/?probe=532c74b6c3) | Dec 16, 2024 |
| Dell          | Latitude E5530 non-vPro     | [9feabc8ce6](https://linux-hardware.org/?probe=9feabc8ce6) | Dec 14, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [331f53945b](https://linux-hardware.org/?probe=331f53945b) | Dec 13, 2024 |
| Dell          | Inspiron 13-5368            | [bd47986d73](https://linux-hardware.org/?probe=bd47986d73) | Dec 13, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [dc2afedb8a](https://linux-hardware.org/?probe=dc2afedb8a) | Dec 08, 2024 |
| HP            | 250 15.6 inch G10 Notebo... | [f92ea0cda1](https://linux-hardware.org/?probe=f92ea0cda1) | Dec 04, 2024 |
| Dell          | Inspiron 13-5368            | [5f256e8e33](https://linux-hardware.org/?probe=5f256e8e33) | Dec 01, 2024 |
| Acer          | Swift SF314-43              | [82fcdbb537](https://linux-hardware.org/?probe=82fcdbb537) | Nov 28, 2024 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | [e65f68056f](https://linux-hardware.org/?probe=e65f68056f) | Nov 24, 2024 |
| Dell          | Vostro 3500                 | [723a673611](https://linux-hardware.org/?probe=723a673611) | Nov 24, 2024 |
| Lenovo        | IdeaPad Pro 5 14IMH9 83D... | [e7b45b99c1](https://linux-hardware.org/?probe=e7b45b99c1) | Nov 23, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [87836c3a98](https://linux-hardware.org/?probe=87836c3a98) | Nov 22, 2024 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [5a37374d2d](https://linux-hardware.org/?probe=5a37374d2d) | Nov 21, 2024 |
| Timi          | TM1701                      | [4a2509bd5a](https://linux-hardware.org/?probe=4a2509bd5a) | Nov 18, 2024 |
| HP            | Victus by Gaming Laptop ... | [f68a7fb475](https://linux-hardware.org/?probe=f68a7fb475) | Nov 17, 2024 |
| XIAOMI        | Redmi Book Pro 15 2023      | [c3dd3deab0](https://linux-hardware.org/?probe=c3dd3deab0) | Nov 16, 2024 |
| XIAOMI        | Redmi Book Pro 15 2023      | [038c91db6e](https://linux-hardware.org/?probe=038c91db6e) | Nov 15, 2024 |
| ASUSTek       | ROG Zephyrus G16 GU603ZV... | [d31a355a2d](https://linux-hardware.org/?probe=d31a355a2d) | Nov 14, 2024 |
| MSI           | GT60 2OC/2OD                | [d4624f582f](https://linux-hardware.org/?probe=d4624f582f) | Nov 11, 2024 |
| ASUSTek       | X550VB                      | [c995cf0e55](https://linux-hardware.org/?probe=c995cf0e55) | Nov 09, 2024 |
| Fujitsu Si... | AMILO A7645                 | [82b3b117c2](https://linux-hardware.org/?probe=82b3b117c2) | Nov 08, 2024 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [f851654ac1](https://linux-hardware.org/?probe=f851654ac1) | Nov 03, 2024 |
| Toshiba       | TECRA A10                   | [f7cfa0f796](https://linux-hardware.org/?probe=f7cfa0f796) | Nov 02, 2024 |
| HP            | 250 G8 Notebook PC          | [c6d19560ba](https://linux-hardware.org/?probe=c6d19560ba) | Oct 26, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [8caf6adea5](https://linux-hardware.org/?probe=8caf6adea5) | Oct 20, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [c5e97b1a91](https://linux-hardware.org/?probe=c5e97b1a91) | Oct 20, 2024 |
| Dell          | Latitude E6400              | [45684f9885](https://linux-hardware.org/?probe=45684f9885) | Oct 20, 2024 |
| TUXEDO        | Pulse 15 Gen2               | [08951a5d7d](https://linux-hardware.org/?probe=08951a5d7d) | Oct 20, 2024 |
| TUXEDO        | Sirius 16 Gen1              | [30d8c17c67](https://linux-hardware.org/?probe=30d8c17c67) | Oct 19, 2024 |
| ASUSTek       | G55VW                       | [a1b8fade8a](https://linux-hardware.org/?probe=a1b8fade8a) | Oct 19, 2024 |
| Lenovo        | ThinkPad X1 Carbon 3460C... | [553cb8fd6e](https://linux-hardware.org/?probe=553cb8fd6e) | Oct 16, 2024 |
| HP            | 250 G4                      | [0bc4a73563](https://linux-hardware.org/?probe=0bc4a73563) | Oct 13, 2024 |
| ASUSTek       | G55VW                       | [101bba7262](https://linux-hardware.org/?probe=101bba7262) | Oct 12, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [f314e87727](https://linux-hardware.org/?probe=f314e87727) | Oct 04, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [884d99dd9f](https://linux-hardware.org/?probe=884d99dd9f) | Oct 04, 2024 |
| HP            | Laptop 15s-eq2xxx           | [a79dcec2fd](https://linux-hardware.org/?probe=a79dcec2fd) | Sep 29, 2024 |
| HP            | 250 G4 Notebook PC          | [69917b9ff3](https://linux-hardware.org/?probe=69917b9ff3) | Sep 27, 2024 |
| Dell          | Latitude E7250              | [bae9276346](https://linux-hardware.org/?probe=bae9276346) | Sep 25, 2024 |
| Lenovo        | ThinkPad P14s Gen 5 AMD ... | [07e66697a0](https://linux-hardware.org/?probe=07e66697a0) | Sep 23, 2024 |
| Lenovo        | ThinkPad P14s Gen 5 AMD ... | [c8b757063d](https://linux-hardware.org/?probe=c8b757063d) | Sep 22, 2024 |
| Dell          | Latitude 5590               | [5a284e9384](https://linux-hardware.org/?probe=5a284e9384) | Sep 16, 2024 |
| HP            | Pavilion dv6                | [f4e2729ed2](https://linux-hardware.org/?probe=f4e2729ed2) | Sep 14, 2024 |
| HP            | Pavilion dv6                | [0ffe1545df](https://linux-hardware.org/?probe=0ffe1545df) | Sep 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [58d0cd3141](https://linux-hardware.org/?probe=58d0cd3141) | Sep 13, 2024 |
| ASUSTek       | ASUS Vivobook S 16 M5606... | [fac034c3d1](https://linux-hardware.org/?probe=fac034c3d1) | Sep 12, 2024 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [10d6c62594](https://linux-hardware.org/?probe=10d6c62594) | Sep 12, 2024 |
| HP            | Laptop 15s-eq2xxx           | [dc90d7b0f6](https://linux-hardware.org/?probe=dc90d7b0f6) | Sep 09, 2024 |
| Dell          | Inspiron 7577               | [fd08888941](https://linux-hardware.org/?probe=fd08888941) | Sep 08, 2024 |
| Dell          | Inspiron 1120               | [08463f81cc](https://linux-hardware.org/?probe=08463f81cc) | Sep 03, 2024 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [8b4a507262](https://linux-hardware.org/?probe=8b4a507262) | Sep 03, 2024 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [6d4b600de7](https://linux-hardware.org/?probe=6d4b600de7) | Sep 02, 2024 |
| Lenovo        | Legion 5 17IMH05 82B3       | [84cfff520c](https://linux-hardware.org/?probe=84cfff520c) | Aug 31, 2024 |
| MSI           | GT60 2OC/2OD                | [4266a67086](https://linux-hardware.org/?probe=4266a67086) | Aug 30, 2024 |
| HP            | 250 G3                      | [4b1cd9dccd](https://linux-hardware.org/?probe=4b1cd9dccd) | Aug 25, 2024 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | [ebc8f6a03b](https://linux-hardware.org/?probe=ebc8f6a03b) | Aug 23, 2024 |
| Dell          | Latitude 5590               | [7117d9db5d](https://linux-hardware.org/?probe=7117d9db5d) | Aug 19, 2024 |
| Dell          | Latitude 5580               | [4e33bc99e9](https://linux-hardware.org/?probe=4e33bc99e9) | Aug 19, 2024 |
| Dell          | Latitude 3510               | [87f51c188d](https://linux-hardware.org/?probe=87f51c188d) | Aug 19, 2024 |
| ASUSTek       | ASUS EXPERTBOOK L2402CYA... | [a8bd6d5797](https://linux-hardware.org/?probe=a8bd6d5797) | Aug 18, 2024 |
| Lenovo        | Legion 5 17IMH05 82B3       | [3a017ae9fc](https://linux-hardware.org/?probe=3a017ae9fc) | Aug 16, 2024 |
| Acer          | Nitro AN515-52              | [4105f16710](https://linux-hardware.org/?probe=4105f16710) | Aug 14, 2024 |
| Acer          | Nitro AN515-52              | [f7706f241c](https://linux-hardware.org/?probe=f7706f241c) | Aug 14, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [5cbd1cc972](https://linux-hardware.org/?probe=5cbd1cc972) | Aug 11, 2024 |
| Dell          | Precision 5550              | [8781ec6a32](https://linux-hardware.org/?probe=8781ec6a32) | Aug 07, 2024 |
| Dell          | Precision 5550              | [d181c91bbe](https://linux-hardware.org/?probe=d181c91bbe) | Aug 07, 2024 |
| MSI           | GT60 2OC/2OD                | [a7e9801aa5](https://linux-hardware.org/?probe=a7e9801aa5) | Aug 05, 2024 |
| ASUSTek       | ASUS Vivobook S 14 M5406... | [ec4802e83f](https://linux-hardware.org/?probe=ec4802e83f) | Aug 03, 2024 |
| HP            | ProBook 650 G5              | [01a53a7211](https://linux-hardware.org/?probe=01a53a7211) | Aug 01, 2024 |
| Dell          | Precision M6800             | [4a4a9d649a](https://linux-hardware.org/?probe=4a4a9d649a) | Aug 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [72badb1215](https://linux-hardware.org/?probe=72badb1215) | Jul 31, 2024 |
| Lenovo        | Legion 5 17IMH05 82B3       | [ddab685cb8](https://linux-hardware.org/?probe=ddab685cb8) | Jul 24, 2024 |
| Dell          | XPS 15 9500                 | [fc6a4ed60b](https://linux-hardware.org/?probe=fc6a4ed60b) | Jul 18, 2024 |
| Dell          | Latitude E5450              | [16fb580b5c](https://linux-hardware.org/?probe=16fb580b5c) | Jul 10, 2024 |
| Lenovo        | B50-30 20382                | [4a4df5cc6a](https://linux-hardware.org/?probe=4a4df5cc6a) | Jul 08, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [1fb3302507](https://linux-hardware.org/?probe=1fb3302507) | Jul 08, 2024 |
| MSI           | GT60 2OC/2OD                | [a05ce4ae88](https://linux-hardware.org/?probe=a05ce4ae88) | Jul 07, 2024 |
| HP            | ZBook 17 G2                 | [10a9a60fa9](https://linux-hardware.org/?probe=10a9a60fa9) | Jul 05, 2024 |
| Samsung       | RV420/RV520/RV720/E3530/... | [e62a05f921](https://linux-hardware.org/?probe=e62a05f921) | Jul 04, 2024 |
| Lenovo        | IdeaPad Pro 5 14AHP9 83D... | [78d572c8c9](https://linux-hardware.org/?probe=78d572c8c9) | Jul 04, 2024 |
| Lenovo        | Legion 5 17IMH05 82B3       | [c5562c765c](https://linux-hardware.org/?probe=c5562c765c) | Jul 01, 2024 |
| HP            | Pavilion dv6                | [9223a7cb0e](https://linux-hardware.org/?probe=9223a7cb0e) | Jun 28, 2024 |
| HP            | Pavilion dv7                | [7f174e80a0](https://linux-hardware.org/?probe=7f174e80a0) | Jun 27, 2024 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | [f172d83ec7](https://linux-hardware.org/?probe=f172d83ec7) | Jun 24, 2024 |
| MSI           | GT60 2OC/2OD                | [60f48f36ca](https://linux-hardware.org/?probe=60f48f36ca) | Jun 23, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [d72c7b70ee](https://linux-hardware.org/?probe=d72c7b70ee) | Jun 13, 2024 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | [bf1706da47](https://linux-hardware.org/?probe=bf1706da47) | Jun 11, 2024 |
| Dell          | Latitude E6400              | [0f678e72a7](https://linux-hardware.org/?probe=0f678e72a7) | Jun 10, 2024 |
| Lenovo        | B590 20206                  | [b1b26a1bd2](https://linux-hardware.org/?probe=b1b26a1bd2) | Jun 10, 2024 |
| Lenovo        | B590 20206                  | [f01af7f707](https://linux-hardware.org/?probe=f01af7f707) | Jun 10, 2024 |
| Apple         | MacBookAir6,2               | [d5968d09b8](https://linux-hardware.org/?probe=d5968d09b8) | Jun 06, 2024 |
| Lenovo        | IdeaPad Pro 5 14IMH9 83D... | [0e6ffaf99b](https://linux-hardware.org/?probe=0e6ffaf99b) | Jun 02, 2024 |
| Acer          | Aspire A315-51              | [584437cbf8](https://linux-hardware.org/?probe=584437cbf8) | May 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [40b2158d92](https://linux-hardware.org/?probe=40b2158d92) | May 17, 2024 |
| Valve         | Galileo                     | [3b501f9708](https://linux-hardware.org/?probe=3b501f9708) | May 13, 2024 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [7ec91a9d57](https://linux-hardware.org/?probe=7ec91a9d57) | May 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [89f7812c21](https://linux-hardware.org/?probe=89f7812c21) | May 11, 2024 |
| HP            | Pavilion dv6                | [1abf1a3f44](https://linux-hardware.org/?probe=1abf1a3f44) | May 10, 2024 |
| MSI           | GT60 2OC/2OD                | [aa9d5951b9](https://linux-hardware.org/?probe=aa9d5951b9) | May 08, 2024 |
| MSI           | GT60 2OC/2OD                | [d71303b21c](https://linux-hardware.org/?probe=d71303b21c) | May 06, 2024 |
| MSI           | GT60 2OC/2OD                | [3330ada128](https://linux-hardware.org/?probe=3330ada128) | May 06, 2024 |
| Dell          | Latitude E6540              | [1e6dfd1900](https://linux-hardware.org/?probe=1e6dfd1900) | May 04, 2024 |
| Dell          | XPS 15 9500                 | [efce8fa0ba](https://linux-hardware.org/?probe=efce8fa0ba) | May 02, 2024 |
| HP            | Laptop 15s-eq2xxx           | [90d5348bf5](https://linux-hardware.org/?probe=90d5348bf5) | Apr 28, 2024 |
| Dell          | Latitude 5420               | [1fa9f586bb](https://linux-hardware.org/?probe=1fa9f586bb) | Apr 27, 2024 |
| Dell          | Latitude 5420               | [5c878504f5](https://linux-hardware.org/?probe=5c878504f5) | Apr 27, 2024 |
| Toshiba       | PORTEGE Z30-A               | [e6fa07d931](https://linux-hardware.org/?probe=e6fa07d931) | Apr 25, 2024 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [85b36d2613](https://linux-hardware.org/?probe=85b36d2613) | Apr 24, 2024 |
| HP            | Pavilion g7                 | [b700499e3c](https://linux-hardware.org/?probe=b700499e3c) | Apr 21, 2024 |
| HP            | Unknown                     | [9e1527f7a4](https://linux-hardware.org/?probe=9e1527f7a4) | Apr 17, 2024 |
| HP            | Unknown                     | [3a23f043ac](https://linux-hardware.org/?probe=3a23f043ac) | Apr 17, 2024 |
| Intel         | CHERRYVIEW D1 PLATFORM      | [86ab252a30](https://linux-hardware.org/?probe=86ab252a30) | Apr 16, 2024 |
| Valve         | Jupiter                     | [c5c95abb79](https://linux-hardware.org/?probe=c5c95abb79) | Apr 12, 2024 |
| HP            | Pavilion g7                 | [6d84e70e34](https://linux-hardware.org/?probe=6d84e70e34) | Apr 10, 2024 |
| Lenovo        | ThinkPad T550 20CKCTO1WW    | [616e9e6be4](https://linux-hardware.org/?probe=616e9e6be4) | Apr 07, 2024 |
| Acer          | Aspire E5-573G              | [da60008a10](https://linux-hardware.org/?probe=da60008a10) | Apr 06, 2024 |
| Dell          | Latitude E4300              | [43c75dde9f](https://linux-hardware.org/?probe=43c75dde9f) | Apr 05, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | [86ccf9c2ca](https://linux-hardware.org/?probe=86ccf9c2ca) | Apr 05, 2024 |
| Dell          | Latitude E6430              | [c871f1007a](https://linux-hardware.org/?probe=c871f1007a) | Mar 31, 2024 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [c498cd96d4](https://linux-hardware.org/?probe=c498cd96d4) | Mar 31, 2024 |
| HP            | EliteBook 840 G4            | [79814f384f](https://linux-hardware.org/?probe=79814f384f) | Mar 28, 2024 |
| HP            | EliteBook 840 G4            | [eea8a3164d](https://linux-hardware.org/?probe=eea8a3164d) | Mar 27, 2024 |
| Acer          | Swift SF14-71T              | [0dcdd95ff5](https://linux-hardware.org/?probe=0dcdd95ff5) | Mar 25, 2024 |
| HP            | Pavilion dv6                | [9070fdfab3](https://linux-hardware.org/?probe=9070fdfab3) | Mar 23, 2024 |
| Dell          | Latitude 3510               | [2324bf3720](https://linux-hardware.org/?probe=2324bf3720) | Mar 23, 2024 |
| Dell          | Latitude 5590               | [bae9210ad3](https://linux-hardware.org/?probe=bae9210ad3) | Mar 21, 2024 |
| MSI           | GT60 2OC/2OD                | [11156842cb](https://linux-hardware.org/?probe=11156842cb) | Mar 21, 2024 |
| XIAOMI        | Redmi Book Pro 15 2023      | [d2662aa4ae](https://linux-hardware.org/?probe=d2662aa4ae) | Mar 17, 2024 |
| Lenovo        | Legion S7 16ARHA7 82UG      | [a83e990b4e](https://linux-hardware.org/?probe=a83e990b4e) | Mar 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [00ab8a1013](https://linux-hardware.org/?probe=00ab8a1013) | Mar 10, 2024 |
| Lenovo        | IdeaPad Slim 3 15AMN8 82... | [9433e012df](https://linux-hardware.org/?probe=9433e012df) | Mar 03, 2024 |
| Lenovo        | V15 G1 IML 82NB             | [b51e9d56f2](https://linux-hardware.org/?probe=b51e9d56f2) | Feb 27, 2024 |
| ASUSTek       | ROG Strix G513IM_G513IM     | [44cc34fb38](https://linux-hardware.org/?probe=44cc34fb38) | Feb 27, 2024 |
| Acer          | EX5235                      | [98b84f5c24](https://linux-hardware.org/?probe=98b84f5c24) | Feb 27, 2024 |
| Samsung       | R530/R730/P530              | [a178c4f940](https://linux-hardware.org/?probe=a178c4f940) | Feb 26, 2024 |
| ASUSTek       | ROG Strix G513IM_G513IM     | [d3f9302555](https://linux-hardware.org/?probe=d3f9302555) | Feb 25, 2024 |
| Samsung       | R530/R730/P530              | [4a557d45bc](https://linux-hardware.org/?probe=4a557d45bc) | Feb 25, 2024 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [6d570ec5af](https://linux-hardware.org/?probe=6d570ec5af) | Feb 24, 2024 |
| Acer          | EX5235                      | [898256f492](https://linux-hardware.org/?probe=898256f492) | Feb 24, 2024 |
| HP            | Pavilion 11 x360 PC         | [f317a83d41](https://linux-hardware.org/?probe=f317a83d41) | Feb 22, 2024 |
| Dell          | Latitude 5590               | [97d36b66b8](https://linux-hardware.org/?probe=97d36b66b8) | Feb 20, 2024 |
| 10ZiG Tech... | 5900q                       | [99b0385f93](https://linux-hardware.org/?probe=99b0385f93) | Feb 19, 2024 |
| Dell          | Vostro 5625                 | [04e53619c6](https://linux-hardware.org/?probe=04e53619c6) | Feb 19, 2024 |
| HP            | Pavilion dv6                | [30a1d043d5](https://linux-hardware.org/?probe=30a1d043d5) | Feb 18, 2024 |
| Dell          | Latitude 5580               | [7525d4aa92](https://linux-hardware.org/?probe=7525d4aa92) | Feb 18, 2024 |
| Dell          | Latitude E5570              | [d1040245b4](https://linux-hardware.org/?probe=d1040245b4) | Feb 18, 2024 |
| Dell          | Inspiron 7566               | [9d3c279e4c](https://linux-hardware.org/?probe=9d3c279e4c) | Feb 16, 2024 |
| Dell          | Studio XPS 1640             | [79baf0c0bf](https://linux-hardware.org/?probe=79baf0c0bf) | Feb 15, 2024 |
| HUAWEI        | BOM-WXX9                    | [71764575ba](https://linux-hardware.org/?probe=71764575ba) | Feb 15, 2024 |
| HUAWEI        | BOM-WXX9                    | [2579f92bcd](https://linux-hardware.org/?probe=2579f92bcd) | Feb 15, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [fe21d31fbd](https://linux-hardware.org/?probe=fe21d31fbd) | Feb 14, 2024 |
| TUXEDO        | Sirius 16 Gen1              | [44b101b616](https://linux-hardware.org/?probe=44b101b616) | Feb 14, 2024 |
| Dell          | Latitude 5580               | [37765cd0c7](https://linux-hardware.org/?probe=37765cd0c7) | Feb 12, 2024 |
| Lenovo        | ThinkPad E15 20RD001XMC     | [5fe617e8a5](https://linux-hardware.org/?probe=5fe617e8a5) | Feb 08, 2024 |
| Lenovo        | G770 20089                  | [d09f6449fa](https://linux-hardware.org/?probe=d09f6449fa) | Feb 08, 2024 |
| Lenovo        | G770 20089                  | [a11d054bb4](https://linux-hardware.org/?probe=a11d054bb4) | Feb 08, 2024 |
| HP            | ProBook 4545s               | [cc45a314f7](https://linux-hardware.org/?probe=cc45a314f7) | Feb 07, 2024 |
| MSI           | GT60 2OC/2OD                | [77186f987a](https://linux-hardware.org/?probe=77186f987a) | Feb 05, 2024 |
| ASUSTek       | K53BR                       | [bd5284a0e8](https://linux-hardware.org/?probe=bd5284a0e8) | Feb 02, 2024 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [58f11b08b0](https://linux-hardware.org/?probe=58f11b08b0) | Feb 01, 2024 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [5f2635ae3a](https://linux-hardware.org/?probe=5f2635ae3a) | Feb 01, 2024 |
| MSI           | GT60 2OC/2OD                | [182643a957](https://linux-hardware.org/?probe=182643a957) | Jan 29, 2024 |
| HP            | Pavilion dv6                | [68d4e31014](https://linux-hardware.org/?probe=68d4e31014) | Jan 28, 2024 |
| HP            | Laptop 17-cp0xxx            | [88cd6c7ca6](https://linux-hardware.org/?probe=88cd6c7ca6) | Jan 23, 2024 |
| MSI           | GT60 2OC/2OD                | [2a30b19d47](https://linux-hardware.org/?probe=2a30b19d47) | Jan 23, 2024 |
| ASUSTek       | N61Jv                       | [ede176e0ca](https://linux-hardware.org/?probe=ede176e0ca) | Jan 21, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402NU... | [9c805e9195](https://linux-hardware.org/?probe=9c805e9195) | Jan 17, 2024 |
| Packard Be... | EasyNote TS11HR             | [41076ef28d](https://linux-hardware.org/?probe=41076ef28d) | Jan 14, 2024 |
| HP            | ProBook 4330s               | [44ddddb2d1](https://linux-hardware.org/?probe=44ddddb2d1) | Jan 13, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [0823cf66ec](https://linux-hardware.org/?probe=0823cf66ec) | Jan 13, 2024 |
| HP            | ProBook 4330s               | [35ef27eb5a](https://linux-hardware.org/?probe=35ef27eb5a) | Jan 12, 2024 |
| Valve         | Jupiter                     | [bc2f7eea4c](https://linux-hardware.org/?probe=bc2f7eea4c) | Jan 10, 2024 |
| Valve         | Jupiter                     | [4ee3e89964](https://linux-hardware.org/?probe=4ee3e89964) | Jan 07, 2024 |
| Acer          | Aspire VN7-791              | [f013dfcc3b](https://linux-hardware.org/?probe=f013dfcc3b) | Jan 05, 2024 |
| HP            | Pavilion dv6                | [d0a6270f74](https://linux-hardware.org/?probe=d0a6270f74) | Jan 04, 2024 |
| HP            | EliteBook 840 G6            | [7fc5a1c4d0](https://linux-hardware.org/?probe=7fc5a1c4d0) | Jan 04, 2024 |
| Acer          | EX5235                      | [c92709aa57](https://linux-hardware.org/?probe=c92709aa57) | Dec 31, 2023 |
| Acer          | EX5235                      | [4a0cb756ff](https://linux-hardware.org/?probe=4a0cb756ff) | Dec 31, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | [815e8736a2](https://linux-hardware.org/?probe=815e8736a2) | Dec 31, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | [4dd47839a4](https://linux-hardware.org/?probe=4dd47839a4) | Dec 31, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [895594b67d](https://linux-hardware.org/?probe=895594b67d) | Dec 30, 2023 |
| MSI           | GT60 2OC/2OD                | [d0a3fb037a](https://linux-hardware.org/?probe=d0a3fb037a) | Dec 28, 2023 |
| Dell          | Latitude E6430              | [a5ce676225](https://linux-hardware.org/?probe=a5ce676225) | Dec 27, 2023 |
| Chuwi         | GemiBook Pro                | [52f704d54a](https://linux-hardware.org/?probe=52f704d54a) | Dec 26, 2023 |
| Acer          | Aspire A515-57              | [9eccf6133e](https://linux-hardware.org/?probe=9eccf6133e) | Dec 25, 2023 |
| HP            | ProBook 4330s               | [fce67d52c0](https://linux-hardware.org/?probe=fce67d52c0) | Dec 22, 2023 |
| HP            | ProBook 450 G1              | [980f7dfed7](https://linux-hardware.org/?probe=980f7dfed7) | Dec 22, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | [d33b5845ef](https://linux-hardware.org/?probe=d33b5845ef) | Dec 20, 2023 |
| Valve         | Jupiter                     | [6235a63aa5](https://linux-hardware.org/?probe=6235a63aa5) | Dec 17, 2023 |
| Dell          | Latitude E7450              | [f429af38c1](https://linux-hardware.org/?probe=f429af38c1) | Dec 17, 2023 |
| Apple         | MacBookAir7,2               | [5b6d840c0a](https://linux-hardware.org/?probe=5b6d840c0a) | Dec 12, 2023 |
| Dell          | Latitude 5400               | [b4317f7856](https://linux-hardware.org/?probe=b4317f7856) | Dec 11, 2023 |
| Acer          | Extensa 5630                | [4709657363](https://linux-hardware.org/?probe=4709657363) | Dec 11, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [2a22b3adb4](https://linux-hardware.org/?probe=2a22b3adb4) | Dec 10, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [8395e5f595](https://linux-hardware.org/?probe=8395e5f595) | Dec 08, 2023 |
| ASUSTek       | K54C                        | [8f1abfdd9a](https://linux-hardware.org/?probe=8f1abfdd9a) | Dec 03, 2023 |
| ASUSTek       | K54C                        | [6702d5257d](https://linux-hardware.org/?probe=6702d5257d) | Dec 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | [0869816e7a](https://linux-hardware.org/?probe=0869816e7a) | Dec 02, 2023 |
| HP            | Pavilion dv6                | [6c2a58400d](https://linux-hardware.org/?probe=6c2a58400d) | Dec 01, 2023 |
| HP            | Pavilion dv6                | [6ee138ba11](https://linux-hardware.org/?probe=6ee138ba11) | Dec 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [9d88b4ad0b](https://linux-hardware.org/?probe=9d88b4ad0b) | Nov 28, 2023 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [f813230b08](https://linux-hardware.org/?probe=f813230b08) | Nov 27, 2023 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [23d18fc15e](https://linux-hardware.org/?probe=23d18fc15e) | Nov 27, 2023 |
| Lenovo        | ThinkPad L480 20LS0015UK    | [5f786955fc](https://linux-hardware.org/?probe=5f786955fc) | Nov 26, 2023 |
| MSI           | GT60 2OC/2OD                | [11086675c9](https://linux-hardware.org/?probe=11086675c9) | Nov 26, 2023 |
| HP            | Pavilion dv6                | [2f757867e7](https://linux-hardware.org/?probe=2f757867e7) | Nov 26, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [41443f69e3](https://linux-hardware.org/?probe=41443f69e3) | Nov 26, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [5a01c502bd](https://linux-hardware.org/?probe=5a01c502bd) | Nov 24, 2023 |
| Lenovo        | Yoga S740-15IRH 81NX        | [8806cbd1e7](https://linux-hardware.org/?probe=8806cbd1e7) | Nov 23, 2023 |
| ASUSTek       | X555LN                      | [e2f9466842](https://linux-hardware.org/?probe=e2f9466842) | Nov 19, 2023 |
| UMAX          | 13Wa_Flex                   | [621a71f736](https://linux-hardware.org/?probe=621a71f736) | Nov 19, 2023 |
| Lenovo        | 3000 V100 076346G           | [039632f3f3](https://linux-hardware.org/?probe=039632f3f3) | Nov 18, 2023 |
| MSI           | GT60 2OC/2OD                | [a29bea944f](https://linux-hardware.org/?probe=a29bea944f) | Nov 16, 2023 |
| MSI           | GT60 2OC/2OD                | [3648bc5b55](https://linux-hardware.org/?probe=3648bc5b55) | Nov 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [2a8696e0f5](https://linux-hardware.org/?probe=2a8696e0f5) | Nov 10, 2023 |
| HP            | 255 15.6 inch G10 Notebo... | [df5983435c](https://linux-hardware.org/?probe=df5983435c) | Nov 08, 2023 |
| Dell          | Latitude E7270              | [0410c1ba06](https://linux-hardware.org/?probe=0410c1ba06) | Nov 08, 2023 |
| Lenovo        | ThinkPad P16v Gen 1 21FE... | [d0d84fed9a](https://linux-hardware.org/?probe=d0d84fed9a) | Nov 04, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [c07d28d9bc](https://linux-hardware.org/?probe=c07d28d9bc) | Nov 04, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [00cab2c4d1](https://linux-hardware.org/?probe=00cab2c4d1) | Nov 04, 2023 |
| HP            | Pavilion dv6                | [bf6361ff84](https://linux-hardware.org/?probe=bf6361ff84) | Nov 03, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [0b00fd801c](https://linux-hardware.org/?probe=0b00fd801c) | Nov 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [7c297acb1f](https://linux-hardware.org/?probe=7c297acb1f) | Nov 01, 2023 |
| Lenovo        | ThinkPad T490 20N3000FRT    | [14710d3709](https://linux-hardware.org/?probe=14710d3709) | Oct 31, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [b553bb2a36](https://linux-hardware.org/?probe=b553bb2a36) | Oct 31, 2023 |
| Dell          | Latitude E7250              | [a83b95ce44](https://linux-hardware.org/?probe=a83b95ce44) | Oct 30, 2023 |
| Lenovo        | B575 Brazos                 | [189361193e](https://linux-hardware.org/?probe=189361193e) | Oct 29, 2023 |
| HP            | 250 15.6 inch G10 Notebo... | [f5f8e6f37d](https://linux-hardware.org/?probe=f5f8e6f37d) | Oct 21, 2023 |
| HP            | ProBook 4535s               | [e52e92c95b](https://linux-hardware.org/?probe=e52e92c95b) | Oct 14, 2023 |
| MSI           | GT60 2OC/2OD                | [1d1d1e17eb](https://linux-hardware.org/?probe=1d1d1e17eb) | Oct 11, 2023 |
| MSI           | GT60 2OC/2OD                | [12d88836d5](https://linux-hardware.org/?probe=12d88836d5) | Oct 11, 2023 |
| Sony          | VPCEJ1L1E                   | [a51252de41](https://linux-hardware.org/?probe=a51252de41) | Oct 03, 2023 |
| MSI           | MS-1651 Ver                 | [7450925b18](https://linux-hardware.org/?probe=7450925b18) | Oct 02, 2023 |
| Acer          | Aspire A315-24P             | [f8033479b2](https://linux-hardware.org/?probe=f8033479b2) | Oct 02, 2023 |
| Dell          | Latitude E7270              | [bf1def4fc3](https://linux-hardware.org/?probe=bf1def4fc3) | Oct 01, 2023 |
| Packard Be... | DOT S                       | [ccf952e34c](https://linux-hardware.org/?probe=ccf952e34c) | Sep 28, 2023 |
| HP            | Notebook                    | [b13debd2fa](https://linux-hardware.org/?probe=b13debd2fa) | Sep 27, 2023 |
| Acer          | Aspire A315-510P            | [794f8f35c8](https://linux-hardware.org/?probe=794f8f35c8) | Sep 25, 2023 |
| Acer          | Aspire A315-510P            | [89ba5bd7dd](https://linux-hardware.org/?probe=89ba5bd7dd) | Sep 25, 2023 |
| MSI           | MS-1651 Ver                 | [93cfb04861](https://linux-hardware.org/?probe=93cfb04861) | Sep 23, 2023 |
| MSI           | MS-1651 Ver                 | [e71155ca01](https://linux-hardware.org/?probe=e71155ca01) | Sep 23, 2023 |
| Acer          | Aspire 5732Z                | [c86094eac8](https://linux-hardware.org/?probe=c86094eac8) | Sep 23, 2023 |
| MSI           | GT60 2OC/2OD                | [0b5a8a95dc](https://linux-hardware.org/?probe=0b5a8a95dc) | Sep 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [ed4753b8e2](https://linux-hardware.org/?probe=ed4753b8e2) | Sep 21, 2023 |
| Acer          | Aspire E1-531               | [f0173f0458](https://linux-hardware.org/?probe=f0173f0458) | Sep 20, 2023 |
| Lenovo        | ThinkPad P50 20EQS0VV2S     | [b7d1f6f3cf](https://linux-hardware.org/?probe=b7d1f6f3cf) | Sep 20, 2023 |
| Acer          | Aspire 5750ZG               | [c9ce4cde54](https://linux-hardware.org/?probe=c9ce4cde54) | Sep 13, 2023 |
| Acer          | Aspire 5750ZG               | [9029730ffb](https://linux-hardware.org/?probe=9029730ffb) | Sep 12, 2023 |
| HP            | ProBook 4740s               | [7166a2d286](https://linux-hardware.org/?probe=7166a2d286) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [dbad37486d](https://linux-hardware.org/?probe=dbad37486d) | Sep 11, 2023 |
| HUAWEI        | MACHC-WAX9                  | [5dde8dd026](https://linux-hardware.org/?probe=5dde8dd026) | Sep 08, 2023 |
| HP            | ProBook 455 G7              | [7ae653c6c1](https://linux-hardware.org/?probe=7ae653c6c1) | Sep 05, 2023 |
| HP            | ZBook 15 G3                 | [faac131992](https://linux-hardware.org/?probe=faac131992) | Sep 05, 2023 |
| HP            | Pavilion dv6                | [cf6a67d073](https://linux-hardware.org/?probe=cf6a67d073) | Sep 03, 2023 |
| Apple         | MacBookPro16,2              | [9ab1a9731d](https://linux-hardware.org/?probe=9ab1a9731d) | Sep 03, 2023 |
| Apple         | MacBookPro16,2              | [78d7ccad98](https://linux-hardware.org/?probe=78d7ccad98) | Sep 02, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [db2e607ae6](https://linux-hardware.org/?probe=db2e607ae6) | Sep 02, 2023 |
| Lenovo        | IdeaPad 1 14ADA7 82R0       | [d70ba1aaf4](https://linux-hardware.org/?probe=d70ba1aaf4) | Sep 01, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [6f5bafed6c](https://linux-hardware.org/?probe=6f5bafed6c) | Aug 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [48450e1a26](https://linux-hardware.org/?probe=48450e1a26) | Aug 29, 2023 |
| MSI           | GT60 2OC/2OD                | [998ee50b04](https://linux-hardware.org/?probe=998ee50b04) | Aug 27, 2023 |
| Toshiba       | Satellite P770              | [8618c83c93](https://linux-hardware.org/?probe=8618c83c93) | Aug 26, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [475563b8b4](https://linux-hardware.org/?probe=475563b8b4) | Aug 24, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [7975d95ea8](https://linux-hardware.org/?probe=7975d95ea8) | Aug 21, 2023 |
| MSI           | GT60 2OC/2OD                | [e610051fdc](https://linux-hardware.org/?probe=e610051fdc) | Aug 20, 2023 |
| HP            | Pavilion dv6                | [a6d62bc041](https://linux-hardware.org/?probe=a6d62bc041) | Aug 18, 2023 |
| Lenovo        | ThinkPad X200 7459Y8Y       | [3a707993c2](https://linux-hardware.org/?probe=3a707993c2) | Aug 16, 2023 |
| Lenovo        | ThinkPad X200 7459Y8Y       | [2f98dd0ac1](https://linux-hardware.org/?probe=2f98dd0ac1) | Aug 16, 2023 |
| HP            | Pavilion g7                 | [43351d6476](https://linux-hardware.org/?probe=43351d6476) | Aug 12, 2023 |
| Acer          | Extensa 5220                | [92605dd73d](https://linux-hardware.org/?probe=92605dd73d) | Aug 12, 2023 |
| Lenovo        | IdeaPad Slim 1-11AST-05 ... | [30c7051967](https://linux-hardware.org/?probe=30c7051967) | Aug 11, 2023 |
| HP            | ProBook 4330s               | [5c854bed9f](https://linux-hardware.org/?probe=5c854bed9f) | Aug 09, 2023 |
| HP            | ProBook 4330s               | [d23ce497d2](https://linux-hardware.org/?probe=d23ce497d2) | Aug 09, 2023 |
| ASUSTek       | F3L                         | [b97c082eff](https://linux-hardware.org/?probe=b97c082eff) | Aug 09, 2023 |
| ASUSTek       | G750JW                      | [fe527d6231](https://linux-hardware.org/?probe=fe527d6231) | Aug 08, 2023 |
| ASUSTek       | 1001P                       | [b4326c3c45](https://linux-hardware.org/?probe=b4326c3c45) | Aug 08, 2023 |
| HP            | Laptop 15s-eq2xxx           | [4a4ac95dcc](https://linux-hardware.org/?probe=4a4ac95dcc) | Aug 01, 2023 |
| Dell          | Latitude 3510               | [8bfe0fe5fb](https://linux-hardware.org/?probe=8bfe0fe5fb) | Jul 30, 2023 |
| Dell          | Latitude E5570              | [1f9be76313](https://linux-hardware.org/?probe=1f9be76313) | Jul 30, 2023 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [451cbfaee5](https://linux-hardware.org/?probe=451cbfaee5) | Jul 29, 2023 |
| Dell          | Latitude 5290 2-in-1        | [26f325a346](https://linux-hardware.org/?probe=26f325a346) | Jul 23, 2023 |
| ASUSTek       | X505BA                      | [fcd96492f0](https://linux-hardware.org/?probe=fcd96492f0) | Jul 17, 2023 |
| Toshiba       | Satellite C650              | [252f8adf16](https://linux-hardware.org/?probe=252f8adf16) | Jul 15, 2023 |
| Lenovo        | ThinkPad T460s 20FAS42W0... | [add1dac3cb](https://linux-hardware.org/?probe=add1dac3cb) | Jul 11, 2023 |
| ASUSTek       | N61Vn                       | [6bbb5b2105](https://linux-hardware.org/?probe=6bbb5b2105) | Jul 10, 2023 |
| ASUSTek       | N61Vn                       | [dd1a0f1acf](https://linux-hardware.org/?probe=dd1a0f1acf) | Jul 10, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [68daff498d](https://linux-hardware.org/?probe=68daff498d) | Jul 02, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [f587b9a46c](https://linux-hardware.org/?probe=f587b9a46c) | Jul 02, 2023 |
| HP            | Pavilion g6                 | [ec6a70b7d4](https://linux-hardware.org/?probe=ec6a70b7d4) | Jun 27, 2023 |
| HUAWEI        | NBD-WXX9                    | [4e7d62b30a](https://linux-hardware.org/?probe=4e7d62b30a) | Jun 21, 2023 |
| Acer          | Aspire VN7-792G             | [ab55f9b492](https://linux-hardware.org/?probe=ab55f9b492) | Jun 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [5141d5dd1a](https://linux-hardware.org/?probe=5141d5dd1a) | Jun 15, 2023 |
| Dell          | XPS 15 9510                 | [9a8a71741e](https://linux-hardware.org/?probe=9a8a71741e) | Jun 14, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [5349772ea1](https://linux-hardware.org/?probe=5349772ea1) | Jun 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c0d6d68272](https://linux-hardware.org/?probe=c0d6d68272) | Jun 12, 2023 |
| MSI           | GT60 2OC/2OD                | [f5a1226b72](https://linux-hardware.org/?probe=f5a1226b72) | Jun 12, 2023 |
| Toshiba       | Satellite C660D             | [a6c222681d](https://linux-hardware.org/?probe=a6c222681d) | Jun 09, 2023 |
| Fujitsu       | LIFEBOOK E5512A             | [7381bd00f3](https://linux-hardware.org/?probe=7381bd00f3) | Jun 07, 2023 |
| MSI           | GT60 2OC/2OD                | [ed3b6abc56](https://linux-hardware.org/?probe=ed3b6abc56) | Jun 05, 2023 |
| Dell          | Latitude E4300              | [cfd95b7e5e](https://linux-hardware.org/?probe=cfd95b7e5e) | Jun 05, 2023 |
| Lenovo        | ThinkPad X61 76738AG        | [7f52d18c2f](https://linux-hardware.org/?probe=7f52d18c2f) | May 30, 2023 |
| Dell          | Latitude E5430 non-vPro     | [278fefa10a](https://linux-hardware.org/?probe=278fefa10a) | May 24, 2023 |
| Dell          | Latitude E5430 non-vPro     | [6ab7e9c82d](https://linux-hardware.org/?probe=6ab7e9c82d) | May 23, 2023 |
| Lenovo        | ThinkPad T410s 2904FAG      | [742f2c09c5](https://linux-hardware.org/?probe=742f2c09c5) | May 21, 2023 |
| HP            | EliteBook 2570p             | [60ec2d6e04](https://linux-hardware.org/?probe=60ec2d6e04) | May 21, 2023 |
| Dell          | Latitude E5430 non-vPro     | [51827f5ae5](https://linux-hardware.org/?probe=51827f5ae5) | May 19, 2023 |
| MSI           | GF63 Thin 11SC              | [89e05e4477](https://linux-hardware.org/?probe=89e05e4477) | May 17, 2023 |
| Dell          | Latitude E5430 non-vPro     | [a1fb71ff2f](https://linux-hardware.org/?probe=a1fb71ff2f) | May 17, 2023 |
| Hampoo        | Cherry Trail CR V200        | [1167f27914](https://linux-hardware.org/?probe=1167f27914) | May 15, 2023 |
| Samsung       | R530/R730/P530              | [9f619133b7](https://linux-hardware.org/?probe=9f619133b7) | May 15, 2023 |
| HP            | Pavilion dv6                | [733703c761](https://linux-hardware.org/?probe=733703c761) | May 09, 2023 |
| ASUSTek       | X553MA                      | [4ab42c06ea](https://linux-hardware.org/?probe=4ab42c06ea) | May 09, 2023 |
| ASUSTek       | X553MA                      | [0952e2922b](https://linux-hardware.org/?probe=0952e2922b) | May 09, 2023 |
| Apple         | MacBook3,1                  | [fca1201c9f](https://linux-hardware.org/?probe=fca1201c9f) | May 07, 2023 |
| HP            | Pavilion g6                 | [d6e340501e](https://linux-hardware.org/?probe=d6e340501e) | May 07, 2023 |
| HP            | ProBook 445 G7              | [c78f20f332](https://linux-hardware.org/?probe=c78f20f332) | May 06, 2023 |
| HP            | Pavilion g6                 | [6c8f0f4521](https://linux-hardware.org/?probe=6c8f0f4521) | May 06, 2023 |
| MSI           | GT60 2OC/2OD                | [8754e79840](https://linux-hardware.org/?probe=8754e79840) | May 04, 2023 |
| Lenovo        | Z50-75 80EC                 | [af5d37f4f7](https://linux-hardware.org/?probe=af5d37f4f7) | Apr 30, 2023 |
| Lenovo        | G50-30 80G0                 | [c8d8595af5](https://linux-hardware.org/?probe=c8d8595af5) | Apr 29, 2023 |
| Dell          | Vostro 3500                 | [7719e2a6c9](https://linux-hardware.org/?probe=7719e2a6c9) | Apr 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [e0f4a4d0f4](https://linux-hardware.org/?probe=e0f4a4d0f4) | Apr 26, 2023 |
| Dell          | Latitude E5570              | [1a6b35e077](https://linux-hardware.org/?probe=1a6b35e077) | Apr 22, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [040d876c1e](https://linux-hardware.org/?probe=040d876c1e) | Apr 16, 2023 |
| MSI           | GT60 2OC/2OD                | [2a389c9c58](https://linux-hardware.org/?probe=2a389c9c58) | Apr 16, 2023 |
| MSI           | GT60 2OC/2OD                | [af0678336d](https://linux-hardware.org/?probe=af0678336d) | Apr 16, 2023 |
| HP            | Laptop 15s-eq2xxx           | [abedf2741f](https://linux-hardware.org/?probe=abedf2741f) | Apr 12, 2023 |
| Acer          | Swift SF314-43              | [95cf4404c3](https://linux-hardware.org/?probe=95cf4404c3) | Apr 08, 2023 |
| Dell          | Latitude E5570              | [7d6ff0e0d8](https://linux-hardware.org/?probe=7d6ff0e0d8) | Apr 07, 2023 |
| Acer          | Aspire E1-532               | [ba90a2c123](https://linux-hardware.org/?probe=ba90a2c123) | Apr 05, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [c529f9d1cc](https://linux-hardware.org/?probe=c529f9d1cc) | Apr 03, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [b9a98e8656](https://linux-hardware.org/?probe=b9a98e8656) | Apr 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | [3034a3d11a](https://linux-hardware.org/?probe=3034a3d11a) | Apr 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | [2f2326e574](https://linux-hardware.org/?probe=2f2326e574) | Apr 02, 2023 |
| HP            | 250 G7 Notebook PC          | [fcb8359930](https://linux-hardware.org/?probe=fcb8359930) | Mar 28, 2023 |
| HP            | 250 G7 Notebook PC          | [2558605a4b](https://linux-hardware.org/?probe=2558605a4b) | Mar 28, 2023 |
| Toshiba       | Satellite C855-1TT          | [ac8e41d993](https://linux-hardware.org/?probe=ac8e41d993) | Mar 27, 2023 |
| Valve         | Jupiter                     | [3ad7937aaf](https://linux-hardware.org/?probe=3ad7937aaf) | Mar 26, 2023 |
| HP            | Laptop 15s-eq2xxx           | [c17f20a679](https://linux-hardware.org/?probe=c17f20a679) | Mar 23, 2023 |
| HP            | ProBook 6470b               | [dd23ab1a2e](https://linux-hardware.org/?probe=dd23ab1a2e) | Mar 19, 2023 |
| HP            | Laptop 15s-eq2xxx           | [1ca9befb7a](https://linux-hardware.org/?probe=1ca9befb7a) | Mar 18, 2023 |
| HP            | Pavilion dv6                | [9c24401930](https://linux-hardware.org/?probe=9c24401930) | Mar 18, 2023 |
| Lenovo        | ThinkPad T590 20N4000DXS    | [c145898fae](https://linux-hardware.org/?probe=c145898fae) | Mar 17, 2023 |
| Lenovo        | ThinkPad T590 20N4000DXS    | [293fe8b4ab](https://linux-hardware.org/?probe=293fe8b4ab) | Mar 17, 2023 |
| HP            | EliteBook 2570p             | [374bab39d7](https://linux-hardware.org/?probe=374bab39d7) | Mar 17, 2023 |
| MSI           | CR500                       | [28eeb3bd71](https://linux-hardware.org/?probe=28eeb3bd71) | Mar 16, 2023 |
| Dell          | Latitude 5580               | [819b5d8dc2](https://linux-hardware.org/?probe=819b5d8dc2) | Mar 14, 2023 |
| Fujitsu       | LIFEBOOK E5512A             | [ae9f2da5a4](https://linux-hardware.org/?probe=ae9f2da5a4) | Mar 14, 2023 |
| Acer          | Aspire VN7-791              | [ca10594901](https://linux-hardware.org/?probe=ca10594901) | Mar 12, 2023 |
| ASUSTek       | X541SA                      | [4adcb5ab0f](https://linux-hardware.org/?probe=4adcb5ab0f) | Mar 08, 2023 |
| Acer          | Aspire VN7-792G             | [3b4a3b74a1](https://linux-hardware.org/?probe=3b4a3b74a1) | Mar 07, 2023 |
| Lenovo        | G505s 20255                 | [b338e704d9](https://linux-hardware.org/?probe=b338e704d9) | Mar 05, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [925e02d1dc](https://linux-hardware.org/?probe=925e02d1dc) | Mar 04, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [7d9acf8639](https://linux-hardware.org/?probe=7d9acf8639) | Mar 04, 2023 |
| HP            | 255 G8 Notebook PC          | [0c76255503](https://linux-hardware.org/?probe=0c76255503) | Mar 04, 2023 |
| HP            | Pavilion 11 x360 PC         | [a7860ee046](https://linux-hardware.org/?probe=a7860ee046) | Mar 04, 2023 |
| HP            | Pavilion 11 x360 PC         | [82847b3b1f](https://linux-hardware.org/?probe=82847b3b1f) | Mar 02, 2023 |
| Google        | Voxel                       | [ce917fe8ec](https://linux-hardware.org/?probe=ce917fe8ec) | Feb 25, 2023 |
| Google        | Voxel                       | [93ea143f69](https://linux-hardware.org/?probe=93ea143f69) | Feb 25, 2023 |
| Lenovo        | ThinkPad T15g Gen 2i 20Y... | [faeee1c46c](https://linux-hardware.org/?probe=faeee1c46c) | Feb 24, 2023 |
| HP            | ProBook 4540s               | [cc3e78f73f](https://linux-hardware.org/?probe=cc3e78f73f) | Feb 18, 2023 |
| Medion        | P651x series                | [23b3fb7ce5](https://linux-hardware.org/?probe=23b3fb7ce5) | Feb 16, 2023 |
| HP            | Pavilion 11 x360 PC         | [b2a1267353](https://linux-hardware.org/?probe=b2a1267353) | Feb 15, 2023 |
| HP            | ProBook 4340s               | [caed0e9f2d](https://linux-hardware.org/?probe=caed0e9f2d) | Feb 13, 2023 |
| Lenovo        | IdeaPad Y580                | [f396fdb21f](https://linux-hardware.org/?probe=f396fdb21f) | Feb 05, 2023 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [bac184b151](https://linux-hardware.org/?probe=bac184b151) | Feb 04, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E1S    | [3f3e5b3a1e](https://linux-hardware.org/?probe=3f3e5b3a1e) | Feb 03, 2023 |
| Dell          | Vostro 5481                 | [40bc04540d](https://linux-hardware.org/?probe=40bc04540d) | Feb 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [1cfa73407d](https://linux-hardware.org/?probe=1cfa73407d) | Jan 31, 2023 |
| HP            | 255 G8 Notebook PC          | [d8e161e2b0](https://linux-hardware.org/?probe=d8e161e2b0) | Jan 25, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [e589b4bd78](https://linux-hardware.org/?probe=e589b4bd78) | Jan 25, 2023 |
| ASUSTek       | TUF Gaming FX505DY_TUF50... | [92a3e34781](https://linux-hardware.org/?probe=92a3e34781) | Jan 24, 2023 |
| Acer          | Aspire E3-111               | [fde7baf9e8](https://linux-hardware.org/?probe=fde7baf9e8) | Jan 19, 2023 |
| Dell          | Inspiron 5770               | [64976ae263](https://linux-hardware.org/?probe=64976ae263) | Jan 19, 2023 |
| PC Special... | Recoil II RTX               | [33850c8810](https://linux-hardware.org/?probe=33850c8810) | Jan 16, 2023 |
| Dell          | Precision 7520              | [c57fdfbe1e](https://linux-hardware.org/?probe=c57fdfbe1e) | Jan 15, 2023 |
| HUAWEI        | KLVL-WXX9                   | [2687f89612](https://linux-hardware.org/?probe=2687f89612) | Jan 14, 2023 |
| Dell          | Latitude E6410              | [a11818f59a](https://linux-hardware.org/?probe=a11818f59a) | Jan 13, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | [22d0c82134](https://linux-hardware.org/?probe=22d0c82134) | Jan 12, 2023 |
| ASUSTek       | G53SX                       | [ef2d9747e2](https://linux-hardware.org/?probe=ef2d9747e2) | Jan 12, 2023 |
| HP            | ProBook 6450b               | [0ae783d261](https://linux-hardware.org/?probe=0ae783d261) | Jan 11, 2023 |
| Dell          | XPS 15 9570                 | [8032d8e1be](https://linux-hardware.org/?probe=8032d8e1be) | Jan 07, 2023 |
| MSI           | Prestige 14 A10RAS          | [fc119df9bc](https://linux-hardware.org/?probe=fc119df9bc) | Jan 02, 2023 |
| Dell          | Latitude E5500              | [f04cd8f466](https://linux-hardware.org/?probe=f04cd8f466) | Dec 31, 2022 |
| Dell          | Latitude E5500              | [24a0ca1b65](https://linux-hardware.org/?probe=24a0ca1b65) | Dec 31, 2022 |
| Google        | Voxel                       | [430244f188](https://linux-hardware.org/?probe=430244f188) | Dec 28, 2022 |
| ASUSTek       | K52Je                       | [28cac9b262](https://linux-hardware.org/?probe=28cac9b262) | Dec 27, 2022 |
| Acer          | Swift SF314-43              | [3d9a51ce6e](https://linux-hardware.org/?probe=3d9a51ce6e) | Dec 27, 2022 |
| Dell          | Latitude 3510               | [ac931934de](https://linux-hardware.org/?probe=ac931934de) | Dec 27, 2022 |
| Dell          | Latitude 3510               | [5db1cf6cb6](https://linux-hardware.org/?probe=5db1cf6cb6) | Dec 27, 2022 |
| Samsung       | 270E5G/270E5U               | [705baed85a](https://linux-hardware.org/?probe=705baed85a) | Dec 26, 2022 |
| ASUSTek       | K52Je                       | [dc13c122ed](https://linux-hardware.org/?probe=dc13c122ed) | Dec 26, 2022 |
| HP            | Pavilion g6                 | [71d7947da6](https://linux-hardware.org/?probe=71d7947da6) | Dec 24, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [30c3f8d777](https://linux-hardware.org/?probe=30c3f8d777) | Dec 21, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [0d273375d6](https://linux-hardware.org/?probe=0d273375d6) | Dec 18, 2022 |
| HP            | Pavilion g6                 | [b5662e5fec](https://linux-hardware.org/?probe=b5662e5fec) | Dec 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c715acf0ea](https://linux-hardware.org/?probe=c715acf0ea) | Dec 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [18b2579f75](https://linux-hardware.org/?probe=18b2579f75) | Dec 09, 2022 |
| HP            | Pavilion g6                 | [d2b43c2803](https://linux-hardware.org/?probe=d2b43c2803) | Dec 05, 2022 |
| ASUSTek       | Zenbook UX5400EA_UX5400E... | [fa46f1d34a](https://linux-hardware.org/?probe=fa46f1d34a) | Dec 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c0f7c4b788](https://linux-hardware.org/?probe=c0f7c4b788) | Dec 03, 2022 |
| Google        | Voxel                       | [b64ebf7db7](https://linux-hardware.org/?probe=b64ebf7db7) | Dec 03, 2022 |
| HP            | 620                         | [6be09298b6](https://linux-hardware.org/?probe=6be09298b6) | Dec 01, 2022 |
| HUAWEI        | KLVL-WXX9                   | [af7d162434](https://linux-hardware.org/?probe=af7d162434) | Nov 28, 2022 |
| Dell          | XPS 15 7590                 | [2355853fda](https://linux-hardware.org/?probe=2355853fda) | Nov 23, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [326b5bad4c](https://linux-hardware.org/?probe=326b5bad4c) | Nov 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [d7992855ba](https://linux-hardware.org/?probe=d7992855ba) | Nov 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [8e17476123](https://linux-hardware.org/?probe=8e17476123) | Nov 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [f48e29fef2](https://linux-hardware.org/?probe=f48e29fef2) | Nov 16, 2022 |
| Acer          | Aspire VN7-791              | [736c2f5664](https://linux-hardware.org/?probe=736c2f5664) | Nov 14, 2022 |
| Lenovo        | V14-IIL 82C4                | [ca336329c8](https://linux-hardware.org/?probe=ca336329c8) | Nov 12, 2022 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | [4f40815737](https://linux-hardware.org/?probe=4f40815737) | Nov 12, 2022 |
| GPD           | G1619-04                    | [cf4cb47a12](https://linux-hardware.org/?probe=cf4cb47a12) | Nov 09, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [87cfe8ed2e](https://linux-hardware.org/?probe=87cfe8ed2e) | Oct 11, 2022 |
| HP            | ENVY Laptop 13-ad0xx        | [52658eb393](https://linux-hardware.org/?probe=52658eb393) | Oct 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [19c7d98b00](https://linux-hardware.org/?probe=19c7d98b00) | Oct 06, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [72163c289e](https://linux-hardware.org/?probe=72163c289e) | Oct 05, 2022 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | [97d1b5e6c5](https://linux-hardware.org/?probe=97d1b5e6c5) | Sep 30, 2022 |
| Dell          | Vostro 5391                 | [61a25cdb83](https://linux-hardware.org/?probe=61a25cdb83) | Sep 28, 2022 |
| ASUSTek       | K55VJ                       | [8e87d041c3](https://linux-hardware.org/?probe=8e87d041c3) | Sep 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [afd66066bc](https://linux-hardware.org/?probe=afd66066bc) | Sep 21, 2022 |
| Lenovo        | G780                        | [04f924450d](https://linux-hardware.org/?probe=04f924450d) | Sep 17, 2022 |
| Valve         | Jupiter                     | [1dc4620833](https://linux-hardware.org/?probe=1dc4620833) | Sep 10, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [ecaa040ba1](https://linux-hardware.org/?probe=ecaa040ba1) | Sep 04, 2022 |
| Dell          | Latitude 3510               | [9477575b26](https://linux-hardware.org/?probe=9477575b26) | Sep 03, 2022 |
| UMAX          | VisionBook 14Wr Plus        | [6a2cb26049](https://linux-hardware.org/?probe=6a2cb26049) | Sep 02, 2022 |
| Toshiba       | TECRA S5                    | [121c8e110b](https://linux-hardware.org/?probe=121c8e110b) | Aug 31, 2022 |
| Toshiba       | TECRA S5                    | [6ec2bd9539](https://linux-hardware.org/?probe=6ec2bd9539) | Aug 31, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c407e3a17c](https://linux-hardware.org/?probe=c407e3a17c) | Aug 29, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [4b56f15871](https://linux-hardware.org/?probe=4b56f15871) | Aug 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [dd415db306](https://linux-hardware.org/?probe=dd415db306) | Aug 28, 2022 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | [8756581baa](https://linux-hardware.org/?probe=8756581baa) | Aug 21, 2022 |
| Samsung       | NC210/NC110                 | [3dcdc1dc6a](https://linux-hardware.org/?probe=3dcdc1dc6a) | Aug 15, 2022 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | [1bcc13e6b4](https://linux-hardware.org/?probe=1bcc13e6b4) | Aug 15, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [9a06c0c10c](https://linux-hardware.org/?probe=9a06c0c10c) | Aug 09, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [7e5a0c0004](https://linux-hardware.org/?probe=7e5a0c0004) | Aug 06, 2022 |
| Acer          | Aspire VN7-791G             | [3e72040097](https://linux-hardware.org/?probe=3e72040097) | Jul 31, 2022 |
| Dell          | XPS 15 9570                 | [e7f56631b1](https://linux-hardware.org/?probe=e7f56631b1) | Jul 27, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [b4a9542143](https://linux-hardware.org/?probe=b4a9542143) | Jul 27, 2022 |
| Dell          | XPS 15 9570                 | [f3972b3a7d](https://linux-hardware.org/?probe=f3972b3a7d) | Jul 26, 2022 |
| HP            | ProBook 440 G3              | [04b2ed9273](https://linux-hardware.org/?probe=04b2ed9273) | Jul 19, 2022 |
| UMAX          | VisionBook-N12R             | [9ccb1f57ab](https://linux-hardware.org/?probe=9ccb1f57ab) | Jul 16, 2022 |
| HP            | ProBook 440 G3              | [c546e3b537](https://linux-hardware.org/?probe=c546e3b537) | Jul 13, 2022 |
| ASUSTek       | N550JK                      | [bc0c9431e1](https://linux-hardware.org/?probe=bc0c9431e1) | Jul 04, 2022 |
| ASUSTek       | N550JK                      | [539ce50149](https://linux-hardware.org/?probe=539ce50149) | Jul 04, 2022 |
| MSI           | EX705                       | [d85dfacff5](https://linux-hardware.org/?probe=d85dfacff5) | Jun 30, 2022 |
| MSI           | EX705                       | [3de108279f](https://linux-hardware.org/?probe=3de108279f) | Jun 30, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [5ebcb2f152](https://linux-hardware.org/?probe=5ebcb2f152) | Jun 29, 2022 |
| HP            | ZBook 15 G6                 | [2e4663e8c3](https://linux-hardware.org/?probe=2e4663e8c3) | Jun 22, 2022 |
| HP            | Pavilion dv6                | [1ba5e6c491](https://linux-hardware.org/?probe=1ba5e6c491) | Jun 18, 2022 |
| Dell          | Latitude 3510               | [4b6e3aeb9e](https://linux-hardware.org/?probe=4b6e3aeb9e) | Jun 16, 2022 |
| Dell          | Latitude E5570              | [ce4d3bb373](https://linux-hardware.org/?probe=ce4d3bb373) | Jun 09, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [fdda1deb12](https://linux-hardware.org/?probe=fdda1deb12) | Jun 07, 2022 |
| Valve         | Jupiter                     | [cc0a20bb93](https://linux-hardware.org/?probe=cc0a20bb93) | Jun 06, 2022 |
| Dell          | Latitude E6440              | [dd05b883a6](https://linux-hardware.org/?probe=dd05b883a6) | Jun 04, 2022 |
| Dell          | Vostro 5515                 | [ae8649e10b](https://linux-hardware.org/?probe=ae8649e10b) | May 28, 2022 |
| MSI           | GT60 2OC/2OD                | [c3b5eb704d](https://linux-hardware.org/?probe=c3b5eb704d) | May 22, 2022 |
| MSI           | GT60 2OC/2OD                | [96f6fda5d5](https://linux-hardware.org/?probe=96f6fda5d5) | May 22, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [0793a5608a](https://linux-hardware.org/?probe=0793a5608a) | May 15, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [d8361f7895](https://linux-hardware.org/?probe=d8361f7895) | May 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [3ba9de57d1](https://linux-hardware.org/?probe=3ba9de57d1) | May 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [96be9cb5e7](https://linux-hardware.org/?probe=96be9cb5e7) | May 12, 2022 |
| Acer          | Aspire E5-575G              | [71e7f1c760](https://linux-hardware.org/?probe=71e7f1c760) | May 09, 2022 |
| MSI           | GT60 2OC/2OD                | [21f08dbab6](https://linux-hardware.org/?probe=21f08dbab6) | May 06, 2022 |
| Dell          | Inspiron 3576               | [85901f28cb](https://linux-hardware.org/?probe=85901f28cb) | May 05, 2022 |
| Acer          | Extensa 5635G               | [6e69a86d63](https://linux-hardware.org/?probe=6e69a86d63) | Apr 28, 2022 |
| HP            | ProBook 4540s               | [17272efb83](https://linux-hardware.org/?probe=17272efb83) | Apr 22, 2022 |
| Dell          | G3 3579                     | [a85e01d9d0](https://linux-hardware.org/?probe=a85e01d9d0) | Apr 20, 2022 |
| Dell          | Latitude E6520              | [33502900d8](https://linux-hardware.org/?probe=33502900d8) | Apr 19, 2022 |
| Fujitsu       | LIFEBOOK E751               | [54de39efb5](https://linux-hardware.org/?probe=54de39efb5) | Apr 12, 2022 |
| HP            | 15                          | [443dd5b9e8](https://linux-hardware.org/?probe=443dd5b9e8) | Apr 02, 2022 |
| Dell          | XPS 13 9333                 | [f4fb42182f](https://linux-hardware.org/?probe=f4fb42182f) | Apr 01, 2022 |
| ASUSTek       | X555LF                      | [35cceb0f0a](https://linux-hardware.org/?probe=35cceb0f0a) | Mar 31, 2022 |
| Fujitsu Si... | AMILO Pi 3525               | [b77907b9b6](https://linux-hardware.org/?probe=b77907b9b6) | Mar 31, 2022 |
| HP            | ProBook 4340s               | [787443949a](https://linux-hardware.org/?probe=787443949a) | Mar 27, 2022 |
| Lenovo        | ThinkPad T420 42364F2       | [d82acaba71](https://linux-hardware.org/?probe=d82acaba71) | Mar 23, 2022 |
| HP            | EliteBook 8740w             | [3ae23e0d6b](https://linux-hardware.org/?probe=3ae23e0d6b) | Mar 22, 2022 |
| ASUSTek       | K50IN                       | [02326ae250](https://linux-hardware.org/?probe=02326ae250) | Mar 22, 2022 |
| ASUSTek       | X555LNB                     | [ae49172b0f](https://linux-hardware.org/?probe=ae49172b0f) | Mar 21, 2022 |
| ASUSTek       | X555LNB                     | [33e081f100](https://linux-hardware.org/?probe=33e081f100) | Mar 21, 2022 |
| Dell          | Latitude 3510               | [f24ba2791e](https://linux-hardware.org/?probe=f24ba2791e) | Mar 19, 2022 |
| ASUSTek       | N53SN                       | [f335baa4a4](https://linux-hardware.org/?probe=f335baa4a4) | Mar 18, 2022 |
| Lenovo        | B580 20144                  | [9918c132f0](https://linux-hardware.org/?probe=9918c132f0) | Mar 13, 2022 |
| Lenovo        | B580 20144                  | [fd9ec44205](https://linux-hardware.org/?probe=fd9ec44205) | Mar 13, 2022 |
| HP            | ProBook 4340s               | [01af2dee98](https://linux-hardware.org/?probe=01af2dee98) | Mar 13, 2022 |
| HP            | EliteBook 8470p             | [76e54baafe](https://linux-hardware.org/?probe=76e54baafe) | Mar 09, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [f78b6db0bd](https://linux-hardware.org/?probe=f78b6db0bd) | Mar 08, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [351e05ccc8](https://linux-hardware.org/?probe=351e05ccc8) | Mar 08, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [dc09f11788](https://linux-hardware.org/?probe=dc09f11788) | Mar 08, 2022 |
| Dell          | Vostro 5515                 | [7707d7dc14](https://linux-hardware.org/?probe=7707d7dc14) | Feb 23, 2022 |
| Sony          | VPCEH3S6E                   | [334451b6e7](https://linux-hardware.org/?probe=334451b6e7) | Feb 23, 2022 |
| UMAX          | VisionBook 14Wr Plus        | [2e2c2de75c](https://linux-hardware.org/?probe=2e2c2de75c) | Feb 20, 2022 |
| ASUSTek       | K56CM                       | [c6e3cad977](https://linux-hardware.org/?probe=c6e3cad977) | Feb 19, 2022 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [9df089b1ef](https://linux-hardware.org/?probe=9df089b1ef) | Feb 19, 2022 |
| HP            | ZBook Firefly 14 G7 Mobi... | [c9b5c461da](https://linux-hardware.org/?probe=c9b5c461da) | Feb 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [b4d07e8ab1](https://linux-hardware.org/?probe=b4d07e8ab1) | Feb 15, 2022 |
| Dell          | Latitude E6500              | [4b35cc763b](https://linux-hardware.org/?probe=4b35cc763b) | Feb 11, 2022 |
| Dell          | Latitude E6500              | [097664c430](https://linux-hardware.org/?probe=097664c430) | Feb 11, 2022 |
| HP            | EliteBook 840 G3            | [383572d5be](https://linux-hardware.org/?probe=383572d5be) | Feb 08, 2022 |
| Toshiba       | Satellite C855-1TT          | [87eacffdb8](https://linux-hardware.org/?probe=87eacffdb8) | Feb 07, 2022 |
| MSI           | VR201                       | [5d514ac721](https://linux-hardware.org/?probe=5d514ac721) | Feb 01, 2022 |
| HP            | ProBook 450 G5              | [39511f4010](https://linux-hardware.org/?probe=39511f4010) | Jan 29, 2022 |
| ASUSTek       | K50C                        | [a285a1e873](https://linux-hardware.org/?probe=a285a1e873) | Jan 27, 2022 |
| Dell          | Latitude E5570              | [7b6a4470d6](https://linux-hardware.org/?probe=7b6a4470d6) | Jan 27, 2022 |
| Acer          | Swift SF314-43              | [11f5908f13](https://linux-hardware.org/?probe=11f5908f13) | Jan 26, 2022 |
| Lenovo        | ThinkPad 20TDZMS            | [143bc3f79b](https://linux-hardware.org/?probe=143bc3f79b) | Jan 23, 2022 |
| MSI           | MS-163B Ver                 | [2e2d0c47bd](https://linux-hardware.org/?probe=2e2d0c47bd) | Jan 23, 2022 |
| Dell          | Latitude 3510               | [47793faf9f](https://linux-hardware.org/?probe=47793faf9f) | Jan 18, 2022 |
| MSI           | EX705                       | [bf23179311](https://linux-hardware.org/?probe=bf23179311) | Jan 17, 2022 |
| ASUSTek       | X553MA                      | [a1f88f8fc7](https://linux-hardware.org/?probe=a1f88f8fc7) | Jan 15, 2022 |
| HP            | Pavilion Gaming Laptop-c... | [bc679e8ef6](https://linux-hardware.org/?probe=bc679e8ef6) | Jan 14, 2022 |
| ASUSTek       | X553MA                      | [3260495670](https://linux-hardware.org/?probe=3260495670) | Jan 13, 2022 |
| HP            | ZBook 15 G3                 | [e91280cb30](https://linux-hardware.org/?probe=e91280cb30) | Dec 31, 2021 |
| Lenovo        | Yoga Slim 9 14ITL5 82D1     | [b5709d8fd1](https://linux-hardware.org/?probe=b5709d8fd1) | Dec 31, 2021 |
| Lenovo        | Yoga Slim 9 14ITL5 82D1     | [b79036063e](https://linux-hardware.org/?probe=b79036063e) | Dec 31, 2021 |
| ASUSTek       | G751JY                      | [e7a5fad002](https://linux-hardware.org/?probe=e7a5fad002) | Dec 29, 2021 |
| HP            | ZBook 15 G3                 | [a2a0923008](https://linux-hardware.org/?probe=a2a0923008) | Dec 20, 2021 |
| HP            | ZBook 15 G3                 | [0cba25aac5](https://linux-hardware.org/?probe=0cba25aac5) | Dec 20, 2021 |
| Lenovo        | G505 20240                  | [e29df1e2a0](https://linux-hardware.org/?probe=e29df1e2a0) | Dec 19, 2021 |
| ASUSTek       | X555BP                      | [770e3752e6](https://linux-hardware.org/?probe=770e3752e6) | Dec 18, 2021 |
| Dell          | Latitude E6430              | [5d4005ae4c](https://linux-hardware.org/?probe=5d4005ae4c) | Dec 13, 2021 |
| Dell          | Latitude 3510               | [e2834c5ef6](https://linux-hardware.org/?probe=e2834c5ef6) | Dec 08, 2021 |
| Dell          | Latitude 5401               | [796c461b16](https://linux-hardware.org/?probe=796c461b16) | Dec 01, 2021 |
| Dell          | Latitude D630               | [6044bc3e07](https://linux-hardware.org/?probe=6044bc3e07) | Nov 28, 2021 |
| Apple         | MacBookPro14,1              | [795a9ffd0f](https://linux-hardware.org/?probe=795a9ffd0f) | Nov 27, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [e1827cbbc6](https://linux-hardware.org/?probe=e1827cbbc6) | Nov 24, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [6fb3466f59](https://linux-hardware.org/?probe=6fb3466f59) | Nov 23, 2021 |
| Dell          | Latitude 5590               | [d8b69c36bd](https://linux-hardware.org/?probe=d8b69c36bd) | Nov 23, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [6189028e3d](https://linux-hardware.org/?probe=6189028e3d) | Nov 23, 2021 |
| Toshiba       | Satellite Pro C850-1D5      | [22ed560714](https://linux-hardware.org/?probe=22ed560714) | Nov 21, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [55384cc552](https://linux-hardware.org/?probe=55384cc552) | Nov 18, 2021 |
| Lenovo        | Z50-70 20354                | [4c1c718d65](https://linux-hardware.org/?probe=4c1c718d65) | Nov 14, 2021 |
| Toshiba       | Satellite L500              | [82d6b16382](https://linux-hardware.org/?probe=82d6b16382) | Nov 08, 2021 |
| Toshiba       | Satellite L500              | [70e2057cff](https://linux-hardware.org/?probe=70e2057cff) | Nov 07, 2021 |
| Toshiba       | Satellite U400              | [7b2364e53a](https://linux-hardware.org/?probe=7b2364e53a) | Nov 04, 2021 |
| HP            | Presario CQ57               | [8e3ceb5db9](https://linux-hardware.org/?probe=8e3ceb5db9) | Oct 23, 2021 |
| HP            | Presario CQ57               | [78828b2790](https://linux-hardware.org/?probe=78828b2790) | Oct 21, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [644553839a](https://linux-hardware.org/?probe=644553839a) | Oct 18, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [ee6fdf4608](https://linux-hardware.org/?probe=ee6fdf4608) | Oct 18, 2021 |
| ASUSTek       | K50C                        | [02e59a3759](https://linux-hardware.org/?probe=02e59a3759) | Oct 16, 2021 |
| ASUSTek       | K50C                        | [c47941a383](https://linux-hardware.org/?probe=c47941a383) | Oct 16, 2021 |
| HP            | Pavilion dv6                | [dbfa388218](https://linux-hardware.org/?probe=dbfa388218) | Oct 10, 2021 |
| HP            | 15                          | [6974f988e3](https://linux-hardware.org/?probe=6974f988e3) | Oct 06, 2021 |
| Dell          | Studio XPS 1340             | [e54daea8f9](https://linux-hardware.org/?probe=e54daea8f9) | Oct 06, 2021 |
| Dell          | Studio XPS 1340             | [ed56dc2a85](https://linux-hardware.org/?probe=ed56dc2a85) | Oct 06, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [0540c800c7](https://linux-hardware.org/?probe=0540c800c7) | Oct 02, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [a508d7f60d](https://linux-hardware.org/?probe=a508d7f60d) | Oct 02, 2021 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [1e0f7c12ef](https://linux-hardware.org/?probe=1e0f7c12ef) | Oct 01, 2021 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [7efbe48343](https://linux-hardware.org/?probe=7efbe48343) | Oct 01, 2021 |
| Dell          | Latitude E6440              | [14a1218871](https://linux-hardware.org/?probe=14a1218871) | Sep 26, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [fd875fbe8c](https://linux-hardware.org/?probe=fd875fbe8c) | Sep 24, 2021 |
| Lenovo        | G580                        | [d7e35103d9](https://linux-hardware.org/?probe=d7e35103d9) | Sep 20, 2021 |
| HP            | Pavilion Notebook           | [835f183d57](https://linux-hardware.org/?probe=835f183d57) | Sep 17, 2021 |
| Toshiba       | Satellite C660              | [b2f55e8760](https://linux-hardware.org/?probe=b2f55e8760) | Sep 16, 2021 |
| Lenovo        | ThinkPad T450 20BV003SMS    | [352b2b53b8](https://linux-hardware.org/?probe=352b2b53b8) | Sep 14, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [727f3718a1](https://linux-hardware.org/?probe=727f3718a1) | Sep 08, 2021 |
| Dell          | Latitude 3510               | [797c9c49c9](https://linux-hardware.org/?probe=797c9c49c9) | Sep 02, 2021 |
| HP            | Pavilion dv6700             | [48ef40abbf](https://linux-hardware.org/?probe=48ef40abbf) | Sep 02, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [05d2b6e067](https://linux-hardware.org/?probe=05d2b6e067) | Sep 01, 2021 |
| Dell          | Latitude E5570              | [7e6202db9d](https://linux-hardware.org/?probe=7e6202db9d) | Aug 31, 2021 |
| Dell          | Latitude E5570              | [95667a8c8f](https://linux-hardware.org/?probe=95667a8c8f) | Aug 31, 2021 |
| HP            | EliteBook 745 G6            | [71e3489cd9](https://linux-hardware.org/?probe=71e3489cd9) | Aug 18, 2021 |
| Lenovo        | ThinkPad X230 2325AT6       | [9e66245080](https://linux-hardware.org/?probe=9e66245080) | Aug 17, 2021 |
| ASUSTek       | X51R                        | [1d1aad3900](https://linux-hardware.org/?probe=1d1aad3900) | Aug 08, 2021 |
| Teclast       | F15S                        | [49f33bd674](https://linux-hardware.org/?probe=49f33bd674) | Jul 28, 2021 |
| ASUSTek       | N551JM                      | [4334fcb285](https://linux-hardware.org/?probe=4334fcb285) | Jul 27, 2021 |
| Dell          | Latitude E5470              | [f26e3c7b39](https://linux-hardware.org/?probe=f26e3c7b39) | Jul 26, 2021 |
| Timi          | TM1701                      | [2d44d6cccb](https://linux-hardware.org/?probe=2d44d6cccb) | Jul 23, 2021 |
| HP            | Presario CQ57               | [3726c1e8c4](https://linux-hardware.org/?probe=3726c1e8c4) | Jul 15, 2021 |
| HP            | Pavilion dv6                | [4ffd108654](https://linux-hardware.org/?probe=4ffd108654) | Jul 15, 2021 |
| Lenovo        | ThinkPad L560 20F10029MC    | [a96e4cc1a5](https://linux-hardware.org/?probe=a96e4cc1a5) | Jul 12, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [8ed58d00f1](https://linux-hardware.org/?probe=8ed58d00f1) | Jun 19, 2021 |
| HP            | Pavilion dv6700             | [8d86cdfbad](https://linux-hardware.org/?probe=8d86cdfbad) | Jun 19, 2021 |
| Lenovo        | ThinkPad L540 20AUS0DW00    | [a3e83938c3](https://linux-hardware.org/?probe=a3e83938c3) | Jun 19, 2021 |
| HP            | Pavilion dv6700             | [44b174fec2](https://linux-hardware.org/?probe=44b174fec2) | Jun 18, 2021 |
| Unknown       | Unknown                     | [001462994e](https://linux-hardware.org/?probe=001462994e) | Jun 18, 2021 |
| Unknown       | Unknown                     | [049e5221b4](https://linux-hardware.org/?probe=049e5221b4) | Jun 18, 2021 |
| HP            | Pavilion dv6700             | [56342fd485](https://linux-hardware.org/?probe=56342fd485) | Jun 17, 2021 |
| Dell          | Precision 7530              | [3e5d3c4292](https://linux-hardware.org/?probe=3e5d3c4292) | Jun 15, 2021 |
| Sony          | VPCEB3L1E                   | [9048edb5d2](https://linux-hardware.org/?probe=9048edb5d2) | Jun 13, 2021 |
| Sony          | VPCEB3L1E                   | [93557b8c32](https://linux-hardware.org/?probe=93557b8c32) | Jun 13, 2021 |
| Sony          | VPCEB3L1E                   | [b90e553e8e](https://linux-hardware.org/?probe=b90e553e8e) | Jun 11, 2021 |
| Sony          | VPCEB3L1E                   | [bc3c3b537b](https://linux-hardware.org/?probe=bc3c3b537b) | Jun 06, 2021 |
| ASUSTek       | K54C                        | [dcdfadb154](https://linux-hardware.org/?probe=dcdfadb154) | May 31, 2021 |
| ASUSTek       | K54C                        | [252cf3ef89](https://linux-hardware.org/?probe=252cf3ef89) | May 31, 2021 |
| Lenovo        | ThinkPad T430 2350B58       | [07b30926e1](https://linux-hardware.org/?probe=07b30926e1) | May 29, 2021 |
| ASUSTek       | F3M                         | [05d9306fcc](https://linux-hardware.org/?probe=05d9306fcc) | May 28, 2021 |
| eMachines     | E725                        | [f573488bda](https://linux-hardware.org/?probe=f573488bda) | May 25, 2021 |
| Lenovo        | ThinkPad T430 2350B58       | [95b045c1a1](https://linux-hardware.org/?probe=95b045c1a1) | May 25, 2021 |
| ASUSTek       | X550CC                      | [26f506ff94](https://linux-hardware.org/?probe=26f506ff94) | May 23, 2021 |
| HP            | Unknown                     | [3584a13ae5](https://linux-hardware.org/?probe=3584a13ae5) | May 22, 2021 |
| HP            | Laptop 15-bw0xx             | [535d153c75](https://linux-hardware.org/?probe=535d153c75) | May 21, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ITL5 8... | [01af2920f0](https://linux-hardware.org/?probe=01af2920f0) | May 19, 2021 |
| Acer          | Nitro AN515-54              | [c8ac6c4b93](https://linux-hardware.org/?probe=c8ac6c4b93) | May 16, 2021 |
| Lenovo        | ThinkPad T490 20N20048GE    | [7c9dbf982e](https://linux-hardware.org/?probe=7c9dbf982e) | May 14, 2021 |
| Toshiba       | Satellite L735              | [177d534fdc](https://linux-hardware.org/?probe=177d534fdc) | May 11, 2021 |
| HP            | Pavilion dv6                | [63656472a4](https://linux-hardware.org/?probe=63656472a4) | May 10, 2021 |
| Toshiba       | Satellite L735              | [52e1221ae0](https://linux-hardware.org/?probe=52e1221ae0) | May 09, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [bc90a54ebf](https://linux-hardware.org/?probe=bc90a54ebf) | May 06, 2021 |
| Dell          | Latitude 5401               | [660bb28d6a](https://linux-hardware.org/?probe=660bb28d6a) | May 04, 2021 |
| Lenovo        | ThinkPad X200T 7449FWG      | [2d8d1beca4](https://linux-hardware.org/?probe=2d8d1beca4) | May 03, 2021 |
| Lenovo        | V110-15IAP 80TG             | [d4307627a7](https://linux-hardware.org/?probe=d4307627a7) | May 01, 2021 |
| Dell          | Latitude 5520               | [d339546263](https://linux-hardware.org/?probe=d339546263) | Apr 30, 2021 |
| Acer          | Aspire 3690                 | [96bd8e49db](https://linux-hardware.org/?probe=96bd8e49db) | Apr 27, 2021 |
| Lenovo        | V110-15IAP 80TG             | [530bf24d20](https://linux-hardware.org/?probe=530bf24d20) | Apr 25, 2021 |
| ASUSTek       | X550CA                      | [103cc770c2](https://linux-hardware.org/?probe=103cc770c2) | Apr 18, 2021 |
| Dell          | System XPS L702X            | [6752a255ca](https://linux-hardware.org/?probe=6752a255ca) | Apr 18, 2021 |
| Dell          | System XPS L702X            | [20c39630ac](https://linux-hardware.org/?probe=20c39630ac) | Apr 18, 2021 |
| HP            | Pavilion 11 x360 PC         | [8aab148f59](https://linux-hardware.org/?probe=8aab148f59) | Apr 17, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ITL5 8... | [1b8f927465](https://linux-hardware.org/?probe=1b8f927465) | Apr 16, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ITL5 8... | [7878f15fa6](https://linux-hardware.org/?probe=7878f15fa6) | Apr 15, 2021 |
| Dell          | Latitude 5490               | [bb7e4cf726](https://linux-hardware.org/?probe=bb7e4cf726) | Apr 13, 2021 |
| Sony          | VGN-FW31ZJ                  | [b1bc398f58](https://linux-hardware.org/?probe=b1bc398f58) | Apr 10, 2021 |
| HP            | EliteBook 840 G1            | [c6fc94dd62](https://linux-hardware.org/?probe=c6fc94dd62) | Apr 08, 2021 |
| Sony          | VGN-FW31ZJ                  | [9de66e685f](https://linux-hardware.org/?probe=9de66e685f) | Apr 05, 2021 |
| HP            | ProBook 650 G1              | [051017604f](https://linux-hardware.org/?probe=051017604f) | Apr 04, 2021 |
| Dell          | Latitude E6400              | [f4e375c3e4](https://linux-hardware.org/?probe=f4e375c3e4) | Apr 01, 2021 |
| Dell          | Latitude E5440              | [757746e097](https://linux-hardware.org/?probe=757746e097) | Apr 01, 2021 |
| ASUSTek       | X550CL                      | [72ec76771c](https://linux-hardware.org/?probe=72ec76771c) | Mar 24, 2021 |
| Toshiba       | Satellite C850-13Z          | [f8b44b58ee](https://linux-hardware.org/?probe=f8b44b58ee) | Mar 21, 2021 |
| ASUSTek       | X550CC                      | [67ef60c8b1](https://linux-hardware.org/?probe=67ef60c8b1) | Mar 20, 2021 |
| HP            | Pavilion dv5                | [f84bed8734](https://linux-hardware.org/?probe=f84bed8734) | Mar 19, 2021 |
| ASUSTek       | X550CC                      | [2f2bf700ae](https://linux-hardware.org/?probe=2f2bf700ae) | Mar 18, 2021 |
| ASUSTek       | X550CC                      | [0f7e04c439](https://linux-hardware.org/?probe=0f7e04c439) | Mar 17, 2021 |
| ASUSTek       | TUF Gaming FX505DY_TUF50... | [60ad7c7aec](https://linux-hardware.org/?probe=60ad7c7aec) | Mar 17, 2021 |
| Dell          | Latitude 3510               | [24bc2a77b2](https://linux-hardware.org/?probe=24bc2a77b2) | Mar 16, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [fbebe98252](https://linux-hardware.org/?probe=fbebe98252) | Mar 13, 2021 |
| HP            | Pavilion dv6500             | [4aae1e6d26](https://linux-hardware.org/?probe=4aae1e6d26) | Mar 11, 2021 |
| HP            | Laptop 15-db1xxx            | [3d4aacd619](https://linux-hardware.org/?probe=3d4aacd619) | Mar 05, 2021 |
| HP            | Pavilion dv6                | [c26d9748f4](https://linux-hardware.org/?probe=c26d9748f4) | Mar 05, 2021 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [aedc60a146](https://linux-hardware.org/?probe=aedc60a146) | Mar 04, 2021 |
| Lenovo        | ThinkPad SL 2746AEG         | [4591f5d5af](https://linux-hardware.org/?probe=4591f5d5af) | Mar 03, 2021 |
| Lenovo        | ThinkPad T540p 20BFS14A0... | [5f75eafa25](https://linux-hardware.org/?probe=5f75eafa25) | Feb 28, 2021 |
| Google        | Gnawty                      | [252bc4cb46](https://linux-hardware.org/?probe=252bc4cb46) | Feb 25, 2021 |
| Dell          | Inspiron 5559               | [eca76d9f64](https://linux-hardware.org/?probe=eca76d9f64) | Feb 25, 2021 |
| Dell          | Latitude D430               | [63906404d0](https://linux-hardware.org/?probe=63906404d0) | Feb 25, 2021 |
| ASUSTek       | X101CH                      | [7897616bb0](https://linux-hardware.org/?probe=7897616bb0) | Feb 25, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [b91a419a64](https://linux-hardware.org/?probe=b91a419a64) | Feb 25, 2021 |
| ASUSTek       | X200CA                      | [2817beb96d](https://linux-hardware.org/?probe=2817beb96d) | Feb 25, 2021 |
| Dell          | Latitude 3510               | [8a6676e538](https://linux-hardware.org/?probe=8a6676e538) | Feb 25, 2021 |
| Acer          | Extensa 5235                | [48868a0c5e](https://linux-hardware.org/?probe=48868a0c5e) | Feb 24, 2021 |
| ASUSTek       | K52F                        | [1492b277a3](https://linux-hardware.org/?probe=1492b277a3) | Feb 24, 2021 |
| ASUSTek       | K52F                        | [0369d16c88](https://linux-hardware.org/?probe=0369d16c88) | Feb 24, 2021 |
| Lenovo        | ThinkPad T540p 20BFS14A0... | [3103f52c54](https://linux-hardware.org/?probe=3103f52c54) | Feb 24, 2021 |
| Dell          | Inspiron 5559               | [08723d28a4](https://linux-hardware.org/?probe=08723d28a4) | Feb 24, 2021 |
| HP            | Pavilion g6                 | [f23e85a87a](https://linux-hardware.org/?probe=f23e85a87a) | Feb 23, 2021 |
| Google        | Gnawty                      | [7614a9a19c](https://linux-hardware.org/?probe=7614a9a19c) | Feb 23, 2021 |
| eMachines     | eM350                       | [7826551972](https://linux-hardware.org/?probe=7826551972) | Feb 20, 2021 |
| Dell          | Inspiron 5559               | [cc6c16c095](https://linux-hardware.org/?probe=cc6c16c095) | Feb 19, 2021 |
| Dell          | Inspiron 7559               | [4d4377253f](https://linux-hardware.org/?probe=4d4377253f) | Feb 15, 2021 |
| Lenovo        | IdeaPad Z460 20059          | [b0b1eb3196](https://linux-hardware.org/?probe=b0b1eb3196) | Feb 14, 2021 |
| Lenovo        | IdeaPad Z460 20059          | [68fdda8114](https://linux-hardware.org/?probe=68fdda8114) | Feb 14, 2021 |
| Dell          | Inspiron 5559               | [4f0639f7c9](https://linux-hardware.org/?probe=4f0639f7c9) | Feb 10, 2021 |
| Dell          | Inspiron 5559               | [e3d953f88d](https://linux-hardware.org/?probe=e3d953f88d) | Feb 10, 2021 |
| Dell          | XPS 13 7390                 | [9d9da95c79](https://linux-hardware.org/?probe=9d9da95c79) | Feb 10, 2021 |
| Dell          | XPS 13 7390                 | [4b6ec0748c](https://linux-hardware.org/?probe=4b6ec0748c) | Feb 10, 2021 |
| Lenovo        | G500 20236                  | [bef7d62361](https://linux-hardware.org/?probe=bef7d62361) | Feb 03, 2021 |
| Dell          | Latitude D620               | [8f4c2819b9](https://linux-hardware.org/?probe=8f4c2819b9) | Feb 01, 2021 |
| HP            | ProBook 4545s               | [9c55ad844b](https://linux-hardware.org/?probe=9c55ad844b) | Jan 28, 2021 |
| HP            | Laptop 15-db1xxx            | [b38aa1a092](https://linux-hardware.org/?probe=b38aa1a092) | Jan 25, 2021 |
| HP            | Laptop 15-db1xxx            | [7a321f0327](https://linux-hardware.org/?probe=7a321f0327) | Jan 25, 2021 |
| HP            | Presario CQ57               | [7dcbdb9d0d](https://linux-hardware.org/?probe=7dcbdb9d0d) | Jan 25, 2021 |
| Lenovo        | IdeaPad 120S-14IAP          | [1469bc5f96](https://linux-hardware.org/?probe=1469bc5f96) | Jan 21, 2021 |
| Toshiba       | Satellite L850-1HP          | [1e0aa7f353](https://linux-hardware.org/?probe=1e0aa7f353) | Jan 17, 2021 |
| Lenovo        | IdeaPad 120S-14IAP          | [ce71ff03d7](https://linux-hardware.org/?probe=ce71ff03d7) | Jan 16, 2021 |
| HP            | Pavilion g6                 | [c4b4831246](https://linux-hardware.org/?probe=c4b4831246) | Jan 15, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [989e87e18e](https://linux-hardware.org/?probe=989e87e18e) | Jan 15, 2021 |
| ASUSTek       | X101CH                      | [3dfb714393](https://linux-hardware.org/?probe=3dfb714393) | Jan 15, 2021 |
| Google        | Gnawty                      | [b110360fd0](https://linux-hardware.org/?probe=b110360fd0) | Jan 15, 2021 |
| MSI           | CR500                       | [ff982a100f](https://linux-hardware.org/?probe=ff982a100f) | Jan 14, 2021 |
| MSI           | CR500                       | [509fd7cfd1](https://linux-hardware.org/?probe=509fd7cfd1) | Jan 14, 2021 |
| Dell          | Latitude D430               | [874d8f3925](https://linux-hardware.org/?probe=874d8f3925) | Jan 14, 2021 |
| ASUSTek       | X556UQK                     | [f70c845b60](https://linux-hardware.org/?probe=f70c845b60) | Jan 13, 2021 |
| HP            | ProBook 455 G6              | [da3110fdce](https://linux-hardware.org/?probe=da3110fdce) | Jan 11, 2021 |
| ASUSTek       | X550CC                      | [95a034c1f0](https://linux-hardware.org/?probe=95a034c1f0) | Jan 10, 2021 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [77af1025e7](https://linux-hardware.org/?probe=77af1025e7) | Jan 08, 2021 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [f3d55068a4](https://linux-hardware.org/?probe=f3d55068a4) | Jan 06, 2021 |
| HP            | EliteBook 8730w (VQ683EA... | [9650848634](https://linux-hardware.org/?probe=9650848634) | Jan 05, 2021 |
| Lenovo        | ThinkPad X230 2325AT6       | [70b6c077a6](https://linux-hardware.org/?probe=70b6c077a6) | Jan 05, 2021 |
| Acer          | Swift sf514-54t             | [f56b772338](https://linux-hardware.org/?probe=f56b772338) | Jan 05, 2021 |
| HP            | ProBook 4540s               | [03c94ff635](https://linux-hardware.org/?probe=03c94ff635) | Jan 04, 2021 |
| HP            | ProBook 4540s               | [eb99a077b0](https://linux-hardware.org/?probe=eb99a077b0) | Jan 04, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [caa3d1d91f](https://linux-hardware.org/?probe=caa3d1d91f) | Jan 03, 2021 |
| MSI           | MS-163B Ver                 | [2406d3e9a2](https://linux-hardware.org/?probe=2406d3e9a2) | Jan 02, 2021 |
| Acer          | Aspire A515-51G             | [0440c76ce6](https://linux-hardware.org/?probe=0440c76ce6) | Jan 01, 2021 |
| MSI           | MS-163B Ver                 | [d3f6e8b5b6](https://linux-hardware.org/?probe=d3f6e8b5b6) | Dec 30, 2020 |
| Acer          | Extensa 5635G               | [a089e8fb2a](https://linux-hardware.org/?probe=a089e8fb2a) | Dec 27, 2020 |
| HP            | ProBook 450 G5              | [183d05951e](https://linux-hardware.org/?probe=183d05951e) | Dec 22, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [bab0eb442f](https://linux-hardware.org/?probe=bab0eb442f) | Dec 22, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [e59a36ff39](https://linux-hardware.org/?probe=e59a36ff39) | Dec 22, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [d239275c54](https://linux-hardware.org/?probe=d239275c54) | Dec 21, 2020 |
| Lenovo        | IdeaPad U260 20067          | [f8b68b1481](https://linux-hardware.org/?probe=f8b68b1481) | Dec 19, 2020 |
| ASUSTek       | X200MA                      | [662934e08a](https://linux-hardware.org/?probe=662934e08a) | Dec 18, 2020 |
| Lenovo        | IdeaPad Y510P 20217         | [a30ab2cb96](https://linux-hardware.org/?probe=a30ab2cb96) | Dec 16, 2020 |
| Fujitsu       | CELSIUS H760                | [bf6b408b8a](https://linux-hardware.org/?probe=bf6b408b8a) | Dec 15, 2020 |
| Toshiba       | Satellite P300              | [207e6367f2](https://linux-hardware.org/?probe=207e6367f2) | Dec 13, 2020 |
| Toshiba       | Satellite P300              | [3c0a54f9df](https://linux-hardware.org/?probe=3c0a54f9df) | Dec 11, 2020 |
| HP            | ProBook 4330s               | [22a64b85be](https://linux-hardware.org/?probe=22a64b85be) | Dec 06, 2020 |
| Dell          | Precision 7530              | [0d9da6571f](https://linux-hardware.org/?probe=0d9da6571f) | Dec 04, 2020 |
| HP            | ProBook 4330s               | [d7d25ffae4](https://linux-hardware.org/?probe=d7d25ffae4) | Dec 03, 2020 |
| Dell          | Precision 7530              | [2ea7f280b2](https://linux-hardware.org/?probe=2ea7f280b2) | Dec 02, 2020 |
| Acer          | Aspire 5742G                | [c17b4a5c87](https://linux-hardware.org/?probe=c17b4a5c87) | Nov 29, 2020 |
| ASUSTek       | ROG Zephyrus S17 GX701LW... | [f0b41bab99](https://linux-hardware.org/?probe=f0b41bab99) | Nov 28, 2020 |
| Lenovo        | ThinkPad P50 20EQS0VV2S     | [e89b91cab1](https://linux-hardware.org/?probe=e89b91cab1) | Nov 25, 2020 |
| Dell          | Vostro 5370                 | [653a970a7e](https://linux-hardware.org/?probe=653a970a7e) | Nov 22, 2020 |
| ASUSTek       | X550CC                      | [0d8cea2372](https://linux-hardware.org/?probe=0d8cea2372) | Nov 21, 2020 |
| HP            | Presario CQ57               | [43ffcec233](https://linux-hardware.org/?probe=43ffcec233) | Nov 18, 2020 |
| HP            | Presario CQ57               | [ff87b0c6d6](https://linux-hardware.org/?probe=ff87b0c6d6) | Nov 16, 2020 |
| HP            | ProBook 4330s               | [c9597f3a0d](https://linux-hardware.org/?probe=c9597f3a0d) | Nov 15, 2020 |
| Acer          | Swift SF315-41              | [43d05784be](https://linux-hardware.org/?probe=43d05784be) | Nov 12, 2020 |
| Dell          | Latitude E6540              | [33d4c9409a](https://linux-hardware.org/?probe=33d4c9409a) | Nov 11, 2020 |
| Lenovo        | G780                        | [145d3ccb54](https://linux-hardware.org/?probe=145d3ccb54) | Nov 08, 2020 |
| Lenovo        | G780                        | [56faed1607](https://linux-hardware.org/?probe=56faed1607) | Nov 06, 2020 |
| Dell          | Latitude 5411               | [e880b200a0](https://linux-hardware.org/?probe=e880b200a0) | Nov 06, 2020 |
| ASUSTek       | K75VJ                       | [aa4d1aabd8](https://linux-hardware.org/?probe=aa4d1aabd8) | Nov 03, 2020 |
| MSI           | EX705                       | [4307aff155](https://linux-hardware.org/?probe=4307aff155) | Nov 02, 2020 |
| MSI           | EX705                       | [c93a29a4ec](https://linux-hardware.org/?probe=c93a29a4ec) | Nov 02, 2020 |
| HP            | 15                          | [8d582da744](https://linux-hardware.org/?probe=8d582da744) | Nov 01, 2020 |
| HP            | 15                          | [0f0be86a64](https://linux-hardware.org/?probe=0f0be86a64) | Nov 01, 2020 |
| ASUSTek       | F5GL                        | [03675a2262](https://linux-hardware.org/?probe=03675a2262) | Oct 31, 2020 |
| Packard Be... | EasyNote TK85               | [544a018464](https://linux-hardware.org/?probe=544a018464) | Oct 30, 2020 |
| Dell          | G7 7790                     | [7dd8ac2676](https://linux-hardware.org/?probe=7dd8ac2676) | Oct 30, 2020 |
| ASUSTek       | UX32VD                      | [6c9095c4b8](https://linux-hardware.org/?probe=6c9095c4b8) | Oct 30, 2020 |
| Packard Be... | EasyNote TK85               | [0d1db60c39](https://linux-hardware.org/?probe=0d1db60c39) | Oct 24, 2020 |
| Lenovo        | ThinkPad T480 20L50006XS    | [782fe456b2](https://linux-hardware.org/?probe=782fe456b2) | Oct 16, 2020 |
| Lenovo        | ThinkPad T480 20L50006XS    | [51a31505c0](https://linux-hardware.org/?probe=51a31505c0) | Oct 16, 2020 |
| HP            | Presario CQ57               | [d2883f7a48](https://linux-hardware.org/?probe=d2883f7a48) | Oct 14, 2020 |
| HP            | Presario CQ57               | [3646e51370](https://linux-hardware.org/?probe=3646e51370) | Oct 13, 2020 |
| HP            | ProBook 4540s               | [095196f795](https://linux-hardware.org/?probe=095196f795) | Oct 09, 2020 |
| HP            | ProBook 4540s               | [0272418c87](https://linux-hardware.org/?probe=0272418c87) | Oct 09, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [dd1a01df40](https://linux-hardware.org/?probe=dd1a01df40) | Oct 09, 2020 |
| HP            | EliteBook 8470p             | [51aeeb5a22](https://linux-hardware.org/?probe=51aeeb5a22) | Oct 07, 2020 |
| HP            | EliteBook 8470p             | [6bd0eacb71](https://linux-hardware.org/?probe=6bd0eacb71) | Oct 07, 2020 |
| Toshiba       | Satellite P770              | [9a6b14ab65](https://linux-hardware.org/?probe=9a6b14ab65) | Oct 07, 2020 |
| Fujitsu Si... | LIFEBOOK S6420              | [cea718db3d](https://linux-hardware.org/?probe=cea718db3d) | Sep 30, 2020 |
| Dell          | XPS 13 9380                 | [1bcd88fae1](https://linux-hardware.org/?probe=1bcd88fae1) | Sep 30, 2020 |
| HP            | ProBook 6570b               | [c36d7a3815](https://linux-hardware.org/?probe=c36d7a3815) | Sep 27, 2020 |
| Lenovo        | ThinkPad T460s 20F9003SG... | [5ee1f4ba42](https://linux-hardware.org/?probe=5ee1f4ba42) | Sep 21, 2020 |
| Lenovo        | IdeaPad 530S-15IKB 81EV     | [25a18b6913](https://linux-hardware.org/?probe=25a18b6913) | Sep 20, 2020 |
| Lenovo        | IdeaPad U260 20067          | [c7ee126272](https://linux-hardware.org/?probe=c7ee126272) | Sep 18, 2020 |
| Lenovo        | G710 20252                  | [bda90e6285](https://linux-hardware.org/?probe=bda90e6285) | Sep 16, 2020 |
| MSI           | Prestige 15 A10SC           | [f9c109d38a](https://linux-hardware.org/?probe=f9c109d38a) | Sep 14, 2020 |
| Lenovo        | B590 20206                  | [241a96fabe](https://linux-hardware.org/?probe=241a96fabe) | Sep 13, 2020 |
| Lenovo        | B590 20206                  | [68c8013cac](https://linux-hardware.org/?probe=68c8013cac) | Sep 13, 2020 |
| ASUSTek       | X550CC                      | [c28899f07f](https://linux-hardware.org/?probe=c28899f07f) | Sep 10, 2020 |
| ASUSTek       | X550CC                      | [3a6d68dfe1](https://linux-hardware.org/?probe=3a6d68dfe1) | Sep 10, 2020 |
| ASUSTek       | X550CC                      | [654281ba17](https://linux-hardware.org/?probe=654281ba17) | Sep 02, 2020 |
| Dell          | Inspiron 7577               | [9243047fd5](https://linux-hardware.org/?probe=9243047fd5) | Aug 30, 2020 |
| ASUSTek       | X550CC                      | [92266759e0](https://linux-hardware.org/?probe=92266759e0) | Aug 29, 2020 |
| ASUSTek       | X550CC                      | [93baa51bda](https://linux-hardware.org/?probe=93baa51bda) | Aug 29, 2020 |
| Acer          | Swift SF314-58              | [3aa1021468](https://linux-hardware.org/?probe=3aa1021468) | Aug 28, 2020 |
| Toshiba       | Satellite C855-1TT          | [7a5dc01f13](https://linux-hardware.org/?probe=7a5dc01f13) | Aug 22, 2020 |
| Toshiba       | Satellite C855-1TT          | [98b59c7ddf](https://linux-hardware.org/?probe=98b59c7ddf) | Aug 21, 2020 |
| Lenovo        | G580                        | [e6435f1530](https://linux-hardware.org/?probe=e6435f1530) | Aug 13, 2020 |
| Sony          | VPCEH1S1E                   | [10c3c1d9d0](https://linux-hardware.org/?probe=10c3c1d9d0) | Aug 13, 2020 |
| MSI           | CR500                       | [6b04b72ba8](https://linux-hardware.org/?probe=6b04b72ba8) | Aug 06, 2020 |
| Lenovo        | ThinkPad T61 7659AB7        | [371a42eb7e](https://linux-hardware.org/?probe=371a42eb7e) | Jul 26, 2020 |
| Acer          | Aspire ES1-523              | [030cf77080](https://linux-hardware.org/?probe=030cf77080) | Jul 20, 2020 |
| Acer          | Aspire ES1-523              | [4d9339959a](https://linux-hardware.org/?probe=4d9339959a) | Jul 20, 2020 |
| HP            | Presario CQ57               | [680685ed32](https://linux-hardware.org/?probe=680685ed32) | Jul 19, 2020 |
| Dell          | Vostro 5370                 | [f8487e0c66](https://linux-hardware.org/?probe=f8487e0c66) | Jul 13, 2020 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [51d0966405](https://linux-hardware.org/?probe=51d0966405) | Jul 07, 2020 |
| UMAX          | VisionBook 14Wg Pro         | [5d2b6ed775](https://linux-hardware.org/?probe=5d2b6ed775) | Jul 06, 2020 |
| Fujitsu       | LIFEBOOK U904               | [57ca2c447b](https://linux-hardware.org/?probe=57ca2c447b) | Jul 06, 2020 |
| Lenovo        | IdeaPad Z500 20202          | [dc66cb5caf](https://linux-hardware.org/?probe=dc66cb5caf) | Jun 25, 2020 |
| UMAX          | VisionBook 14Wg Pro         | [a50a75e674](https://linux-hardware.org/?probe=a50a75e674) | Jun 21, 2020 |
| HP            | ProBook 6570b               | [f2370339d5](https://linux-hardware.org/?probe=f2370339d5) | Jun 21, 2020 |
| HP            | ProBook 6570b               | [c477dc5d5b](https://linux-hardware.org/?probe=c477dc5d5b) | Jun 18, 2020 |
| HP            | ProBook 6570b               | [d1f562df2f](https://linux-hardware.org/?probe=d1f562df2f) | Jun 18, 2020 |
| Sony          | VPCEH1L8E                   | [3b8814bf8e](https://linux-hardware.org/?probe=3b8814bf8e) | Jun 15, 2020 |
| Acer          | Aspire 5100                 | [481320cdb6](https://linux-hardware.org/?probe=481320cdb6) | Jun 09, 2020 |
| Acer          | Aspire 5100                 | [0e89938085](https://linux-hardware.org/?probe=0e89938085) | Jun 09, 2020 |
| ASUSTek       | X550CC                      | [d832045294](https://linux-hardware.org/?probe=d832045294) | Jun 06, 2020 |
| Lenovo        | ThinkPad Edge E220s 5038... | [e37f8c0d24](https://linux-hardware.org/?probe=e37f8c0d24) | Jun 05, 2020 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | [a570720ce6](https://linux-hardware.org/?probe=a570720ce6) | May 26, 2020 |
| ASUSTek       | X550CC                      | [82c8b62b02](https://linux-hardware.org/?probe=82c8b62b02) | May 24, 2020 |
| ASUSTek       | X550CC                      | [8ebd135c78](https://linux-hardware.org/?probe=8ebd135c78) | May 23, 2020 |
| HP            | EliteBook 745 G3            | [1d082fe95a](https://linux-hardware.org/?probe=1d082fe95a) | May 14, 2020 |
| Lenovo        | IdeaPad 720S-15IKB 81AC     | [b8dfa98b13](https://linux-hardware.org/?probe=b8dfa98b13) | May 10, 2020 |
| Lenovo        | ThinkPad P50 20EQS0VV2S     | [31d9941f79](https://linux-hardware.org/?probe=31d9941f79) | May 05, 2020 |
| Lenovo        | ThinkPad P50 20EQS0VV2S     | [ddfe727f57](https://linux-hardware.org/?probe=ddfe727f57) | May 04, 2020 |
| HP            | EliteBook 850 G5            | [3e455caa1a](https://linux-hardware.org/?probe=3e455caa1a) | Apr 25, 2020 |
| HP            | Presario CQ57               | [0ba9cb0077](https://linux-hardware.org/?probe=0ba9cb0077) | Apr 25, 2020 |
| Acer          | Swift SF314-41              | [00dcbaa8f0](https://linux-hardware.org/?probe=00dcbaa8f0) | Apr 24, 2020 |
| Lenovo        | Z710 20250                  | [cf3d4e04cc](https://linux-hardware.org/?probe=cf3d4e04cc) | Apr 19, 2020 |
| ASUSTek       | T100TA                      | [ba03f5b5dd](https://linux-hardware.org/?probe=ba03f5b5dd) | Apr 19, 2020 |
| Dell          | Latitude E6540              | [0a2c664d30](https://linux-hardware.org/?probe=0a2c664d30) | Apr 19, 2020 |
| Lenovo        | B51-80 80LM                 | [b54cb44723](https://linux-hardware.org/?probe=b54cb44723) | Apr 17, 2020 |
| HP            | EliteBook 2760p             | [6631b4c0f1](https://linux-hardware.org/?probe=6631b4c0f1) | Apr 17, 2020 |
| HP            | Presario CQ57               | [9e1ad378a1](https://linux-hardware.org/?probe=9e1ad378a1) | Apr 13, 2020 |
| Lenovo        | B51-80 80LM                 | [054456ab1e](https://linux-hardware.org/?probe=054456ab1e) | Apr 12, 2020 |
| Dell          | Latitude E6540              | [1daf9c5f1a](https://linux-hardware.org/?probe=1daf9c5f1a) | Apr 10, 2020 |
| HP            | ProBook 450 G4              | [9c62a9edc6](https://linux-hardware.org/?probe=9c62a9edc6) | Apr 09, 2020 |
| Lenovo        | ThinkPad Edge E531 6885B... | [9dd9a20b65](https://linux-hardware.org/?probe=9dd9a20b65) | Apr 05, 2020 |
| Toshiba       | Satellite L450              | [b18b01a081](https://linux-hardware.org/?probe=b18b01a081) | Apr 04, 2020 |
| Lenovo        | Z710 20250                  | [0f9b8a8fc0](https://linux-hardware.org/?probe=0f9b8a8fc0) | Mar 31, 2020 |
| HP            | EliteBook 850 G6            | [f638a70ec4](https://linux-hardware.org/?probe=f638a70ec4) | Mar 30, 2020 |
| HP            | 530 Notebook PC(KD080AA#... | [aec394a418](https://linux-hardware.org/?probe=aec394a418) | Mar 27, 2020 |
| Packard Be... | EasyNote TE11BZ             | [5aaa403dee](https://linux-hardware.org/?probe=5aaa403dee) | Mar 26, 2020 |
| ASUSTek       | A6Km                        | [2c47a900f8](https://linux-hardware.org/?probe=2c47a900f8) | Mar 25, 2020 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [3f0773955d](https://linux-hardware.org/?probe=3f0773955d) | Mar 25, 2020 |
| ASUSTek       | A6Km                        | [3183eb860e](https://linux-hardware.org/?probe=3183eb860e) | Mar 24, 2020 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [56566f3fbb](https://linux-hardware.org/?probe=56566f3fbb) | Mar 23, 2020 |
| Toshiba       | Satellite P300              | [e51afe4271](https://linux-hardware.org/?probe=e51afe4271) | Mar 23, 2020 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [d5242f2534](https://linux-hardware.org/?probe=d5242f2534) | Mar 15, 2020 |
| ASUSTek       | X51L                        | [3ce2f3c47e](https://linux-hardware.org/?probe=3ce2f3c47e) | Mar 11, 2020 |
| Lenovo        | 3000 V100 07635CG           | [8c9c933a22](https://linux-hardware.org/?probe=8c9c933a22) | Mar 07, 2020 |
| Dell          | Latitude 5490               | [ab3da12d55](https://linux-hardware.org/?probe=ab3da12d55) | Feb 22, 2020 |
| Dell          | Latitude 5490               | [6b43e4ae7f](https://linux-hardware.org/?probe=6b43e4ae7f) | Feb 22, 2020 |
| ASUSTek       | F3Ke                        | [f1eaad7ea4](https://linux-hardware.org/?probe=f1eaad7ea4) | Feb 22, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Slovakia/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 53        | 6.87%   |
| Ubuntu 18.04        | 39        | 5.06%   |
| BlackPanther 18.1   | 38        | 4.93%   |
| Ubuntu 22.04        | 27        | 3.5%    |
| Ubuntu 24.04        | 25        | 3.24%   |
| Arch Rolling        | 23        | 2.98%   |
| OpenMandriva 4.3    | 18        | 2.33%   |
| Pop!_OS 22.04       | 16        | 2.08%   |
| OpenMandriva 4.2    | 12        | 1.56%   |
| Linux Mint 22.1     | 11        | 1.43%   |
| Linux Mint 21.2     | 11        | 1.43%   |
| Linux Mint 21.1     | 11        | 1.43%   |
| Debian 12           | 11        | 1.43%   |
| Linux Mint 22.2     | 9         | 1.17%   |
| Linux Mint 21       | 9         | 1.17%   |
| Linux Mint 19.3     | 9         | 1.17%   |
| Debian 11           | 9         | 1.17%   |
| ROSA R10            | 8         | 1.04%   |
| OpenMandriva 25.90  | 8         | 1.04%   |
| Linux Mint 20.3     | 8         | 1.04%   |
| Linux Mint 20.1     | 8         | 1.04%   |
| Fedora 42           | 8         | 1.04%   |
| Fedora 41           | 8         | 1.04%   |
| Fedora 40           | 8         | 1.04%   |
| Fedora 39           | 8         | 1.04%   |
| EndeavourOS Rolling | 8         | 1.04%   |
| Xubuntu 18.04       | 7         | 0.91%   |
| OpenMandriva 23.01  | 7         | 0.91%   |
| Fedora 37           | 7         | 0.91%   |
| Fedora 34           | 7         | 0.91%   |
| Zorin 16            | 6         | 0.78%   |
| Ubuntu 19.04        | 6         | 0.78%   |
| ROSA 12.5.1         | 6         | 0.78%   |
| OpenMandriva 24.12  | 6         | 0.78%   |
| OpenMandriva 23.08  | 6         | 0.78%   |
| MX 19               | 6         | 0.78%   |
| Linux Mint 22       | 6         | 0.78%   |
| Fedora 38           | 6         | 0.78%   |
| Zorin 17            | 5         | 0.65%   |
| Ubuntu 23.10        | 5         | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 171       | 23.88%  |
| OpenMandriva  | 79        | 11.03%  |
| Linux Mint    | 77        | 10.75%  |
| Fedora        | 69        | 9.64%   |
| BlackPanther  | 43        | 6.01%   |
| Debian        | 29        | 4.05%   |
| Arch          | 27        | 3.77%   |
| Pop!_OS       | 26        | 3.63%   |
| ROSA          | 23        | 3.21%   |
| Zorin         | 19        | 2.65%   |
| Kubuntu       | 19        | 2.65%   |
| Xubuntu       | 14        | 1.96%   |
| Manjaro       | 11        | 1.54%   |
| KDE neon      | 9         | 1.26%   |
| EndeavourOS   | 9         | 1.26%   |
| SteamOS       | 8         | 1.12%   |
| MX            | 8         | 1.12%   |
| openSUSE      | 7         | 0.98%   |
| Elementary    | 6         | 0.84%   |
| Lubuntu       | 5         | 0.7%    |
| Gentoo        | 5         | 0.7%    |
| Endless       | 4         | 0.56%   |
| CachyOS       | 4         | 0.56%   |
| Ubuntu Unity  | 3         | 0.42%   |
| Ubuntu MATE   | 3         | 0.42%   |
| Nobara        | 3         | 0.42%   |
| NixOS         | 3         | 0.42%   |
| ArcoLinux     | 3         | 0.42%   |
| Alpine        | 3         | 0.42%   |
| Ubuntu Budgie | 2         | 0.28%   |
| TUXEDO OS     | 2         | 0.28%   |
| Parrot        | 2         | 0.28%   |
| Kali          | 2         | 0.28%   |
| Devuan        | 2         | 0.28%   |
| Bluefin       | 2         | 0.28%   |
| Artix         | 2         | 0.28%   |
| Rocky Linux   | 1         | 0.14%   |
| RHEL          | 1         | 0.14%   |
| Puppy         | 1         | 0.14%   |
| Oracle        | 1         | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                           | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| 4.18.16-desktop-1bP               | 30        | 3.61%   |
| 5.16.7-desktop-1omv4003           | 16        | 1.93%   |
| 6.14.2-desktop-3omv2590           | 14        | 1.68%   |
| 5.10.14-desktop-1omv4002          | 12        | 1.44%   |
| 5.6.14-desktop-2bP                | 11        | 1.32%   |
| 5.15.0-56-generic                 | 10        | 1.2%    |
| 6.8.0-52-generic                  | 9         | 1.08%   |
| 6.14.0-29-generic                 | 9         | 1.08%   |
| 5.4.0-58-generic                  | 8         | 0.96%   |
| 6.2.0-26-generic                  | 7         | 0.84%   |
| 6.1.1-desktop-1omv2290            | 7         | 0.84%   |
| 5.4.0-42-generic                  | 7         | 0.84%   |
| 6.8.0-51-generic                  | 6         | 0.72%   |
| 6.9.3-76060903-generic            | 5         | 0.6%    |
| 6.8.0-40-generic                  | 5         | 0.6%    |
| 6.6.2-desktop-1omv2390            | 5         | 0.6%    |
| 6.5.0-18-generic                  | 5         | 0.6%    |
| 6.2.6-desktop-1omv2390            | 5         | 0.6%    |
| 6.14.0-33-generic                 | 5         | 0.6%    |
| 5.4.0-52-generic                  | 5         | 0.6%    |
| 5.15.0-58-generic                 | 5         | 0.6%    |
| 5.11.0-27-generic                 | 5         | 0.6%    |
| 6.8.0-45-generic                  | 4         | 0.48%   |
| 6.6.32-power-1bP                  | 4         | 0.48%   |
| 6.6.27-generic-3rosa2021.1-x86_64 | 4         | 0.48%   |
| 6.2.0-33-generic                  | 4         | 0.48%   |
| 6.12.1-desktop-1omv2490           | 4         | 0.48%   |
| 5.8.0-43-generic                  | 4         | 0.48%   |
| 5.4.0-73-generic                  | 4         | 0.48%   |
| 5.4.0-47-generic                  | 4         | 0.48%   |
| 5.19.0-35-generic                 | 4         | 0.48%   |
| 5.15.0-91-generic                 | 4         | 0.48%   |
| 5.15.0-83-generic                 | 4         | 0.48%   |
| 5.15.0-67-generic                 | 4         | 0.48%   |
| 4.9.60-nrj-desktop-1rosa-x86_64   | 4         | 0.48%   |
| 4.15.0-66-generic                 | 4         | 0.48%   |
| 6.8.0-41-generic                  | 3         | 0.36%   |
| 6.5.0-27-generic                  | 3         | 0.36%   |
| 6.5.0-26-generic                  | 3         | 0.36%   |
| 6.4.8-desktop-2omv2390            | 3         | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 71        | 9.08%   |
| 5.15.0  | 49        | 6.27%   |
| 6.8.0   | 44        | 5.63%   |
| 4.15.0  | 36        | 4.6%    |
| 4.18.16 | 30        | 3.84%   |
| 6.5.0   | 25        | 3.2%    |
| 5.8.0   | 23        | 2.94%   |
| 6.14.0  | 22        | 2.81%   |
| 6.2.0   | 19        | 2.43%   |
| 5.13.0  | 18        | 2.3%    |
| 5.3.0   | 17        | 2.17%   |
| 6.14.2  | 16        | 2.05%   |
| 5.16.7  | 16        | 2.05%   |
| 5.11.0  | 16        | 2.05%   |
| 5.0.0   | 15        | 1.92%   |
| 5.19.0  | 14        | 1.79%   |
| 6.1.0   | 13        | 1.66%   |
| 5.10.14 | 12        | 1.53%   |
| 5.10.0  | 12        | 1.53%   |
| 6.11.0  | 11        | 1.41%   |
| 5.6.14  | 11        | 1.41%   |
| 6.2.6   | 7         | 0.9%    |
| 6.1.1   | 7         | 0.9%    |
| 4.19.0  | 7         | 0.9%    |
| 4.18.0  | 7         | 0.9%    |
| 6.9.3   | 6         | 0.77%   |
| 6.6.2   | 6         | 0.77%   |
| 6.6.32  | 5         | 0.64%   |
| 6.12.1  | 5         | 0.64%   |
| 6.6.27  | 4         | 0.51%   |
| 6.12.6  | 4         | 0.51%   |
| 6.12.10 | 4         | 0.51%   |
| 6.1.52  | 4         | 0.51%   |
| 4.9.60  | 4         | 0.51%   |
| 6.6.8   | 3         | 0.38%   |
| 6.4.8   | 3         | 0.38%   |
| 6.4.11  | 3         | 0.38%   |
| 6.4.0   | 3         | 0.38%   |
| 6.17.9  | 3         | 0.38%   |
| 6.15.4  | 3         | 0.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 75        | 9.62%   |
| 5.15    | 65        | 8.33%   |
| 6.8     | 49        | 6.28%   |
| 6.14    | 38        | 4.87%   |
| 4.18    | 37        | 4.74%   |
| 4.15    | 36        | 4.62%   |
| 6.5     | 34        | 4.36%   |
| 6.1     | 33        | 4.23%   |
| 5.10    | 32        | 4.1%    |
| 6.2     | 31        | 3.97%   |
| 6.6     | 28        | 3.59%   |
| 6.12    | 25        | 3.21%   |
| 5.8     | 24        | 3.08%   |
| 5.11    | 22        | 2.82%   |
| 5.16    | 21        | 2.69%   |
| 5.13    | 21        | 2.69%   |
| 6.11    | 20        | 2.56%   |
| 5.3     | 19        | 2.44%   |
| 5.19    | 17        | 2.18%   |
| 5.0     | 17        | 2.18%   |
| 5.6     | 14        | 1.79%   |
| 6.4     | 12        | 1.54%   |
| 4.9     | 12        | 1.54%   |
| 6.9     | 10        | 1.28%   |
| 6.17    | 8         | 1.03%   |
| 6.13    | 8         | 1.03%   |
| 6.10    | 8         | 1.03%   |
| 4.19    | 8         | 1.03%   |
| 5.17    | 7         | 0.9%    |
| 6.3     | 6         | 0.77%   |
| 6.15    | 5         | 0.64%   |
| 5.5     | 5         | 0.64%   |
| 6.7     | 4         | 0.51%   |
| 6.16    | 4         | 0.51%   |
| 6.0     | 4         | 0.51%   |
| 5.9     | 4         | 0.51%   |
| 5.12    | 3         | 0.38%   |
| 5.7     | 2         | 0.26%   |
| 5.18    | 2         | 0.26%   |
| 5.14    | 2         | 0.26%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 659       | 95.51%  |
| i686   | 31        | 4.49%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 256       | 35.56%  |
| KDE5            | 153       | 21.25%  |
| Unknown         | 66        | 9.17%   |
| X-Cinnamon      | 64        | 8.89%   |
| XFCE            | 61        | 8.47%   |
| KDE6            | 46        | 6.39%   |
| MATE            | 14        | 1.94%   |
| KDE             | 10        | 1.39%   |
| KDE4            | 9         | 1.25%   |
| LXQt            | 8         | 1.11%   |
| Pantheon        | 6         | 0.83%   |
| LXDE            | 5         | 0.69%   |
| Hyprland        | 5         | 0.69%   |
| Cinnamon        | 5         | 0.69%   |
| Unity           | 3         | 0.42%   |
| Budgie          | 3         | 0.42%   |
| qtile           | 1         | 0.14%   |
| NsCDE           | 1         | 0.14%   |
| GNOME Flashback | 1         | 0.14%   |
| GNOME Classic   | 1         | 0.14%   |
| COSMIC          | 1         | 0.14%   |
| awesome         | 1         | 0.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| X11         | 485       | 68.5%   |
| Wayland     | 183       | 25.85%  |
| Unknown     | 31        | 4.38%   |
| Tty         | 8         | 1.13%   |
| Unspecified | 1         | 0.14%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 296       | 41.46%  |
| SDDM    | 175       | 24.51%  |
| GDM3    | 89        | 12.46%  |
| LightDM | 74        | 10.36%  |
| GDM     | 55        | 7.7%    |
| TDM     | 11        | 1.54%   |
| KDM     | 8         | 1.12%   |
| XDM     | 1         | 0.14%   |
| SLiM    | 1         | 0.14%   |
| LY-DM   | 1         | 0.14%   |
| Ly      | 1         | 0.14%   |
| LXDM    | 1         | 0.14%   |
| GREETD  | 1         | 0.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 321       | 45.02%  |
| sk_SK   | 190       | 26.65%  |
| Unknown | 108       | 15.15%  |
| cs_CZ   | 25        | 3.51%   |
| C       | 22        | 3.09%   |
| en_GB   | 17        | 2.38%   |
| hu_HU   | 13        | 1.82%   |
| ru_RU   | 7         | 0.98%   |
| pl_PL   | 2         | 0.28%   |
| uk_UA   | 1         | 0.14%   |
| ru_UA   | 1         | 0.14%   |
| POSIX   | 1         | 0.14%   |
| it_IT   | 1         | 0.14%   |
| en_US  | 1         | 0.14%   |
| en_CA   | 1         | 0.14%   |
| de_DE   | 1         | 0.14%   |
| C.UTF8  | 1         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 381       | 53.81%  |
| EFI  | 327       | 46.19%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 432       | 60.5%   |
| Overlay  | 102       | 14.29%  |
| Btrfs    | 91        | 12.75%  |
| Tmpfs    | 51        | 7.14%   |
| Unknown  | 16        | 2.24%   |
| Zfs      | 7         | 0.98%   |
| Xfs      | 7         | 0.98%   |
| Ext3     | 4         | 0.56%   |
| Ext2     | 2         | 0.28%   |
| F2fs     | 1         | 0.14%   |
| Bcachefs | 1         | 0.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 301       | 42.76%  |
| GPT     | 294       | 41.76%  |
| MBR     | 109       | 15.48%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 599       | 84.72%  |
| Yes       | 108       | 15.28%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 487       | 69.97%  |
| Yes       | 209       | 30.03%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 187       | 27.14%  |
| Hewlett-Packard     | 118       | 17.13%  |
| ASUSTek Computer    | 115       | 16.69%  |
| Dell                | 93        | 13.5%   |
| Acer                | 55        | 7.98%   |
| Toshiba             | 21        | 3.05%   |
| MSI                 | 19        | 2.76%   |
| Sony                | 9         | 1.31%   |
| Apple               | 8         | 1.16%   |
| Valve               | 7         | 1.02%   |
| Samsung Electronics | 6         | 0.87%   |
| UMAX                | 5         | 0.73%   |
| Packard Bell        | 5         | 0.73%   |
| HUAWEI              | 5         | 0.73%   |
| Fujitsu Siemens     | 5         | 0.73%   |
| Fujitsu             | 4         | 0.58%   |
| Timi                | 3         | 0.44%   |
| Intel               | 3         | 0.44%   |
| eMachines           | 3         | 0.44%   |
| TUXEDO              | 2         | 0.29%   |
| Medion              | 2         | 0.29%   |
| GPD                 | 2         | 0.29%   |
| Google              | 2         | 0.29%   |
| Chuwi               | 2         | 0.29%   |
| XIAOMI              | 1         | 0.15%   |
| Teclast             | 1         | 0.15%   |
| SIEMENS             | 1         | 0.15%   |
| PC Specialist       | 1         | 0.15%   |
| METAPHYUNI          | 1         | 0.15%   |
| Hampoo              | 1         | 0.15%   |
| 10ZiG Technology    | 1         | 0.15%   |
| Unknown             | 1         | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| HP Pavilion dv6                        | 7         | 1.02%   |
| Valve Jupiter                          | 6         | 0.87%   |
| MSI GT60 2OC/2OD                       | 4         | 0.58%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2    | 4         | 0.58%   |
| ASUS X550CC                            | 4         | 0.58%   |
| Acer Swift SF314-43                    | 4         | 0.58%   |
| Lenovo IdeaPad 320-15IAP 80XR          | 3         | 0.44%   |
| Lenovo G580                            | 3         | 0.44%   |
| HP ZBook 15 G3                         | 3         | 0.44%   |
| HP ProBook 4540s                       | 3         | 0.44%   |
| HP ProBook 4330s                       | 3         | 0.44%   |
| HP Pavilion g6                         | 3         | 0.44%   |
| Dell Latitude E6540                    | 3         | 0.44%   |
| ASUS VivoBook_ASUSLaptop X509DJ_D509DJ | 3         | 0.44%   |
| Unknown                                | 3         | 0.44%   |
| UMAX VisionBook 14Wr Plus              | 2         | 0.29%   |
| Toshiba Satellite P300                 | 2         | 0.29%   |
| Timi Redmi Book Pro 15 2022            | 2         | 0.29%   |
| Samsung R530/R730/P530                 | 2         | 0.29%   |
| Packard Bell EasyNote TK85             | 2         | 0.29%   |
| MSI VR610                              | 2         | 0.29%   |
| Lenovo Yoga Slim 7 Pro 14ITL5 82FX     | 2         | 0.29%   |
| Lenovo Y520-15IKBN 80WK                | 2         | 0.29%   |
| Lenovo ThinkPad P50 20EQS0VV2S         | 2         | 0.29%   |
| Lenovo ThinkBook 15 G3 ACL 21A4        | 2         | 0.29%   |
| Lenovo Legion 5 15ACH6H 82JU           | 2         | 0.29%   |
| Lenovo IdeaPad Z500 20202              | 2         | 0.29%   |
| Lenovo IdeaPad U260 20067              | 2         | 0.29%   |
| Lenovo IdeaPad S145-14AST 81ST         | 2         | 0.29%   |
| Lenovo IdeaPad S130-14IGM 81J2         | 2         | 0.29%   |
| Lenovo IdeaPad Pro 5 14IMH9 83D2       | 2         | 0.29%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY   | 2         | 0.29%   |
| Lenovo IdeaPad 5 15ABA7 82SG           | 2         | 0.29%   |
| Lenovo G550 20023                      | 2         | 0.29%   |
| Lenovo G500 20236                      | 2         | 0.29%   |
| Lenovo B590 20206                      | 2         | 0.29%   |
| Intel CHERRYVIEW D1 PLATFORM           | 2         | 0.29%   |
| HUAWEI KLVL-WXX9                       | 2         | 0.29%   |
| HP ProBook 6570b                       | 2         | 0.29%   |
| HP ProBook 650 G1                      | 2         | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 79        | 11.47%  |
| Lenovo IdeaPad        | 54        | 7.84%   |
| Dell Latitude         | 51        | 7.4%    |
| HP ProBook            | 37        | 5.37%   |
| Acer Aspire           | 32        | 4.64%   |
| HP Pavilion           | 20        | 2.9%    |
| HP EliteBook          | 19        | 2.76%   |
| Toshiba Satellite     | 17        | 2.47%   |
| ASUS VivoBook         | 15        | 2.18%   |
| ASUS ROG              | 15        | 2.18%   |
| Lenovo Legion         | 12        | 1.74%   |
| Dell XPS              | 11        | 1.6%    |
| ASUS ASUS             | 11        | 1.6%    |
| HP 250                | 10        | 1.45%   |
| Dell Inspiron         | 10        | 1.45%   |
| Acer Swift            | 10        | 1.45%   |
| Dell Vostro           | 9         | 1.31%   |
| Valve Jupiter         | 6         | 0.87%   |
| HP ZBook              | 6         | 0.87%   |
| HP Laptop             | 6         | 0.87%   |
| ASUS ZenBook          | 6         | 0.87%   |
| Acer Extensa          | 6         | 0.87%   |
| Lenovo Yoga           | 5         | 0.73%   |
| Dell Precision        | 5         | 0.73%   |
| Packard Bell EasyNote | 4         | 0.58%   |
| MSI GT60              | 4         | 0.58%   |
| ASUS X550CC           | 4         | 0.58%   |
| UMAX VisionBook       | 3         | 0.44%   |
| Lenovo V15            | 3         | 0.44%   |
| Lenovo G580           | 3         | 0.44%   |
| HP Compaq             | 3         | 0.44%   |
| Fujitsu LIFEBOOK      | 3         | 0.44%   |
| Dell Studio           | 3         | 0.44%   |
| Acer Nitro            | 3         | 0.44%   |
| Unknown               | 3         | 0.44%   |
| Toshiba TECRA         | 2         | 0.29%   |
| Timi Redmi            | 2         | 0.29%   |
| Samsung R530          | 2         | 0.29%   |
| MSI VR610             | 2         | 0.29%   |
| MSI Prestige          | 2         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 60        | 8.71%   |
| 2013 | 54        | 7.84%   |
| 2020 | 49        | 7.11%   |
| 2019 | 49        | 7.11%   |
| 2021 | 48        | 6.97%   |
| 2011 | 46        | 6.68%   |
| 2008 | 42        | 6.1%    |
| 2018 | 41        | 5.95%   |
| 2017 | 40        | 5.81%   |
| 2022 | 34        | 4.93%   |
| 2010 | 34        | 4.93%   |
| 2014 | 32        | 4.64%   |
| 2016 | 29        | 4.21%   |
| 2009 | 29        | 4.21%   |
| 2015 | 24        | 3.48%   |
| 2023 | 22        | 3.19%   |
| 2007 | 22        | 3.19%   |
| 2024 | 17        | 2.47%   |
| 2006 | 9         | 1.31%   |
| 2025 | 6         | 0.87%   |
| 2005 | 2         | 0.29%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 689       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 628       | 90.1%   |
| Enabled  | 69        | 9.9%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 687       | 99.71%  |
| Yes  | 2         | 0.29%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 175       | 25.04%  |
| 3.01-4.0    | 157       | 22.46%  |
| 16.01-24.0  | 124       | 17.74%  |
| 8.01-16.0   | 114       | 16.31%  |
| 32.01-64.0  | 46        | 6.58%   |
| 1.01-2.0    | 34        | 4.86%   |
| 2.01-3.0    | 19        | 2.72%   |
| 24.01-32.0  | 14        | 2%      |
| 64.01-256.0 | 9         | 1.29%   |
| 0.51-1.0    | 7         | 1%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 253       | 33.2%   |
| 2.01-3.0   | 165       | 21.65%  |
| 4.01-8.0   | 112       | 14.7%   |
| 3.01-4.0   | 89        | 11.68%  |
| 0.51-1.0   | 82        | 10.76%  |
| 8.01-16.0  | 37        | 4.86%   |
| 0.01-0.5   | 17        | 2.23%   |
| 16.01-24.0 | 5         | 0.66%   |
| 32.01-64.0 | 1         | 0.13%   |
| 24.01-32.0 | 1         | 0.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 507       | 71.51%  |
| 2      | 167       | 23.55%  |
| 3      | 25        | 3.53%   |
| 0      | 9         | 1.27%   |
| 5      | 1         | 0.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 429       | 62.17%  |
| Yes       | 261       | 37.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 564       | 81.62%  |
| No        | 127       | 18.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 673       | 97.4%   |
| No        | 18        | 2.6%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 540       | 77.59%  |
| No        | 156       | 22.41%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Slovakia | 689       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Bratislava             | 247       | 32.76%  |
| Košice                | 46        | 6.1%    |
| Banská Bystrica       | 33        | 4.38%   |
| Nitra                  | 29        | 3.85%   |
| Trnava                 | 20        | 2.65%   |
| Žilina                | 15        | 1.99%   |
| Prešov                | 14        | 1.86%   |
| Martin                 | 14        | 1.86%   |
| Humenné               | 10        | 1.33%   |
| Bardejov               | 9         | 1.19%   |
| Poprad                 | 8         | 1.06%   |
| Brezno                 | 8         | 1.06%   |
| Tornaľa               | 7         | 0.93%   |
| Galanta                | 7         | 0.93%   |
| Trenčín              | 6         | 0.8%    |
| Senec                  | 6         | 0.8%    |
| Liptovský Mikuláš   | 6         | 0.8%    |
| Zvolen                 | 5         | 0.66%   |
| Rožňava              | 5         | 0.66%   |
| Nové Zámky           | 5         | 0.66%   |
| Michalovce             | 5         | 0.66%   |
| Lučenec               | 5         | 0.66%   |
| Levice                 | 5         | 0.66%   |
| Velky Krtis            | 4         | 0.53%   |
| Topoľčany            | 4         | 0.53%   |
| Soblahov               | 4         | 0.53%   |
| Sabinov                | 4         | 0.53%   |
| Dunajská Streda       | 4         | 0.53%   |
| Ziar nad Hronom        | 3         | 0.4%    |
| Velky Meder            | 3         | 0.4%    |
| Štúrovo              | 3         | 0.4%    |
| Stará Ľubovňa       | 3         | 0.4%    |
| Šaľa                 | 3         | 0.4%    |
| Ružomberok            | 3         | 0.4%    |
| Považská Bystrica    | 3         | 0.4%    |
| Piešťany             | 3         | 0.4%    |
| Pezinok                | 3         | 0.4%    |
| Partizánske           | 3         | 0.4%    |
| Nové Mesto nad Váhom | 3         | 0.4%    |
| Námestovo             | 3         | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 138       | 166    | 15.65%  |
| WDC                         | 100       | 166    | 11.34%  |
| Seagate                     | 98        | 127    | 11.11%  |
| Sandisk                     | 60        | 76     | 6.8%    |
| Toshiba                     | 53        | 78     | 6.01%   |
| Kingston                    | 52        | 76     | 5.9%    |
| Unknown                     | 50        | 74     | 5.67%   |
| SK hynix                    | 45        | 60     | 5.1%    |
| Micron Technology           | 36        | 43     | 4.08%   |
| Intel                       | 31        | 44     | 3.51%   |
| Patriot                     | 28        | 37     | 3.17%   |
| Hitachi                     | 27        | 29     | 3.06%   |
| Crucial                     | 22        | 28     | 2.49%   |
| A-DATA Technology           | 20        | 28     | 2.27%   |
| HGST                        | 18        | 22     | 2.04%   |
| Verbatim                    | 8         | 10     | 0.91%   |
| Apacer                      | 8         | 14     | 0.91%   |
| KIOXIA                      | 7         | 23     | 0.79%   |
| Phison Electronics          | 6         | 6      | 0.68%   |
| Fujitsu                     | 5         | 5      | 0.57%   |
| Apple                       | 5         | 6      | 0.57%   |
| Union Memory                | 4         | 4      | 0.45%   |
| MAXIO Technology (Hangzhou) | 4         | 7      | 0.45%   |
| LITEON                      | 4         | 4      | 0.45%   |
| Unknown                     | 4         | 4      | 0.45%   |
| Transcend                   | 3         | 3      | 0.34%   |
| OCZ                         | 3         | 3      | 0.34%   |
| China                       | 3         | 4      | 0.34%   |
| Phison                      | 2         | 2      | 0.23%   |
| Micron/Crucial Technology   | 2         | 2      | 0.23%   |
| LITEONIT                    | 2         | 2      | 0.23%   |
| Kingston Technology Company | 2         | 2      | 0.23%   |
| ZTE                         | 1         | 1      | 0.11%   |
| Yangtze Memory Technologies | 1         | 1      | 0.11%   |
| XPG                         | 1         | 1      | 0.11%   |
| WDC WDS2                    | 1         | 1      | 0.11%   |
| Viper                       | 1         | 1      | 0.11%   |
| StoreJet                    | 1         | 1      | 0.11%   |
| Solid State Storage         | 1         | 1      | 0.11%   |
| Plextor                     | 1         | 1      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB    | 14        | 1.51%   |
| Unknown MMC Card  64GB                               | 12        | 1.29%   |
| Patriot Burst 240GB SSD                              | 12        | 1.29%   |
| Samsung SSD 860 EVO 500GB                            | 11        | 1.18%   |
| Seagate ST1000LM035-1RK172 1TB                       | 9         | 0.97%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 9         | 0.97%   |
| Samsung SSD 870 EVO 500GB                            | 9         | 0.97%   |
| Seagate ST9500325AS 500GB                            | 8         | 0.86%   |
| Patriot Burst 480GB SSD                              | 8         | 0.86%   |
| Kingston SA400S37120G 120GB SSD                      | 8         | 0.86%   |
| Samsung SSD 850 EVO 250GB                            | 7         | 0.75%   |
| Kingston SV300S37A120G 120GB SSD                     | 7         | 0.75%   |
| SanDisk NVMe SSD Drive 512GB                         | 6         | 0.65%   |
| Samsung SSD 850 EVO 500GB                            | 6         | 0.65%   |
| Kingston SA400S37240G 240GB SSD                      | 6         | 0.65%   |
| HGST HTS725050A7E630 500GB                           | 6         | 0.65%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                     | 5         | 0.54%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 5         | 0.54%   |
| WDC WD10JPLX-00MBPT0 1TB                             | 5         | 0.54%   |
| Unknown MMC Card  32GB                               | 5         | 0.54%   |
| Toshiba MQ01ABF050 500GB                             | 5         | 0.54%   |
| Seagate ST9500420AS 500GB                            | 5         | 0.54%   |
| Seagate ST500LT012-9WS142 500GB                      | 5         | 0.54%   |
| SanDisk NVMe SSD Drive 1024GB                        | 5         | 0.54%   |
| Samsung SSD 980 1TB                                  | 5         | 0.54%   |
| Samsung SSD 860 EVO 250GB                            | 5         | 0.54%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB   | 5         | 0.54%   |
| Samsung MZALQ512HBLU-00BL2 512GB                     | 5         | 0.54%   |
| Hitachi HTS545050B9A300 500GB                        | 5         | 0.54%   |
| Crucial CT1000MX500SSD1 1TB                          | 5         | 0.54%   |
| WDC WD5000BEKT-22KA9T0 500GB                         | 4         | 0.43%   |
| Unknown MMC Card  1GB                                | 4         | 0.43%   |
| Unknown MMC Card  16GB                               | 4         | 0.43%   |
| SK hynix SKHynix_HFS001TEJ9X162N 1024GB              | 4         | 0.43%   |
| Samsung SSD 990 PRO 4TB                              | 4         | 0.43%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB | 4         | 0.43%   |
| Samsung MZALQ512HALU-000L2 512GB                     | 4         | 0.43%   |
| Patriot P210 256GB SSD                               | 4         | 0.43%   |
| Patriot Burst 120GB SSD                              | 4         | 0.43%   |
| Micron MTFDKBA1T0QFM-1BD1AABGB 1024GB                | 4         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 98        | 127    | 37.98%  |
| WDC                 | 70        | 130    | 27.13%  |
| Toshiba             | 34        | 58     | 13.18%  |
| Hitachi             | 27        | 29     | 10.47%  |
| HGST                | 18        | 22     | 6.98%   |
| Fujitsu             | 5         | 5      | 1.94%   |
| Unknown             | 2         | 2      | 0.78%   |
| StoreJet            | 1         | 1      | 0.39%   |
| Samsung Electronics | 1         | 2      | 0.39%   |
| IBM/Hitachi         | 1         | 1      | 0.39%   |
| HGST HTS            | 1         | 1      | 0.39%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 66        | 71     | 21.93%  |
| Kingston            | 42        | 66     | 13.95%  |
| Patriot             | 27        | 35     | 8.97%   |
| SanDisk             | 24        | 29     | 7.97%   |
| Crucial             | 22        | 28     | 7.31%   |
| WDC                 | 17        | 21     | 5.65%   |
| A-DATA Technology   | 17        | 25     | 5.65%   |
| Intel               | 13        | 17     | 4.32%   |
| Micron Technology   | 9         | 11     | 2.99%   |
| Verbatim            | 8         | 10     | 2.66%   |
| Toshiba             | 7         | 7      | 2.33%   |
| SK hynix            | 7         | 10     | 2.33%   |
| Apacer              | 7         | 13     | 2.33%   |
| LITEON              | 4         | 4      | 1.33%   |
| Transcend           | 3         | 3      | 1%      |
| OCZ                 | 3         | 3      | 1%      |
| China               | 3         | 4      | 1%      |
| Apple               | 3         | 3      | 1%      |
| Union Memory        | 2         | 2      | 0.66%   |
| LITEONIT            | 2         | 2      | 0.66%   |
| WDC WDS2            | 1         | 1      | 0.33%   |
| Plextor             | 1         | 1      | 0.33%   |
| Netac               | 1         | 1      | 0.33%   |
| KingSpec            | 1         | 1      | 0.33%   |
| KingDian            | 1         | 3      | 0.33%   |
| Intenso             | 1         | 1      | 0.33%   |
| IM3D                | 1         | 1      | 0.33%   |
| HS-SSD-E100         | 1         | 1      | 0.33%   |
| Hewlett-Packard     | 1         | 1      | 0.33%   |
| GOODRAM             | 1         | 1      | 0.33%   |
| Gigabyte Technology | 1         | 1      | 0.33%   |
| Faspeed             | 1         | 1      | 0.33%   |
| Dahua               | 1         | 1      | 0.33%   |
| BHT                 | 1         | 1      | 0.33%   |
| 2.5                 | 1         | 1      | 0.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 274       | 381    | 33.29%  |
| NVMe    | 248       | 349    | 30.13%  |
| HDD     | 244       | 378    | 29.65%  |
| MMC     | 51        | 75     | 6.2%    |
| Unknown | 6         | 6      | 0.73%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 447       | 737    | 57.68%  |
| NVMe | 248       | 345    | 32%     |
| MMC  | 51        | 75     | 6.58%   |
| SAS  | 29        | 32     | 3.74%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 368       | 557    | 73.6%   |
| 0.51-1.0   | 111       | 173    | 22.2%   |
| 1.01-2.0   | 19        | 26     | 3.8%    |
| 3.01-4.0   | 2         | 3      | 0.4%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 186       | 25.41%  |
| 251-500        | 166       | 22.68%  |
| 501-1000       | 109       | 14.89%  |
| 1-20           | 74        | 10.11%  |
| 51-100         | 56        | 7.65%   |
| Unknown        | 56        | 7.65%   |
| 21-50          | 32        | 4.37%   |
| 1001-2000      | 29        | 3.96%   |
| 2001-3000      | 13        | 1.78%   |
| More than 3000 | 11        | 1.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 297       | 39.13%  |
| 21-50          | 128       | 16.86%  |
| 101-250        | 93        | 12.25%  |
| 51-100         | 90        | 11.86%  |
| 251-500        | 56        | 7.38%   |
| Unknown        | 56        | 7.38%   |
| 501-1000       | 22        | 2.9%    |
| 1001-2000      | 13        | 1.71%   |
| More than 3000 | 2         | 0.26%   |
| 2001-3000      | 2         | 0.26%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Notebooks | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| WDC WD5000BEKT-22KA9T0 500GB            | 4         | 14     | 4.76%   |
| WDC WD10JPLX-00MBPT0 1TB                | 4         | 20     | 4.76%   |
| WDC WD5000BEVT-60A0RT0 500GB            | 2         | 2      | 2.38%   |
| Toshiba MK7575GSX 752GB                 | 2         | 3      | 2.38%   |
| Toshiba MK5056GSY 500GB                 | 2         | 2      | 2.38%   |
| Seagate ST980811AS 80GB                 | 2         | 2      | 2.38%   |
| Seagate ST500LT012-1DG142 500GB         | 2         | 2      | 2.38%   |
| Seagate ST500LM000-SSHD-8GB             | 2         | 7      | 2.38%   |
| Kingston SV300S37A60G 64GB SSD          | 2         | 2      | 2.38%   |
| Kingston SA400S37120G 120GB SSD         | 2         | 2      | 2.38%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 1      | 1.19%   |
| WDC WD7500BPVT-80HXZT3 752GB            | 1         | 1      | 1.19%   |
| WDC WD5000LPVT-24G33T1 500GB            | 1         | 1      | 1.19%   |
| WDC WD5000LPCX-60VHAT0 500GB            | 1         | 1      | 1.19%   |
| WDC WD5000BUCT-63PUZY0 500GB            | 1         | 2      | 1.19%   |
| WDC WD5000BPVT-00HXZT1 500GB            | 1         | 1      | 1.19%   |
| WDC WD5000BEVT-22A0RT0 500GB            | 1         | 2      | 1.19%   |
| WDC WD3200BEVT-75ZCT2 320GB             | 1         | 1      | 1.19%   |
| WDC WD1600BEVT-60ZCT1 160GB             | 1         | 1      | 1.19%   |
| WDC WD Green 2.5 240GB                  | 1         | 1      | 1.19%   |
| Toshiba MQ01ABF050 500GB                | 1         | 3      | 1.19%   |
| Toshiba MQ01ABD100 1TB                  | 1         | 1      | 1.19%   |
| Toshiba MQ01ABD075 752GB                | 1         | 1      | 1.19%   |
| Toshiba MK3252GSX 320GB                 | 1         | 1      | 1.19%   |
| Toshiba MK1646GSX 160GB                 | 1         | 2      | 1.19%   |
| Toshiba MK1637GSX 160GB                 | 1         | 1      | 1.19%   |
| SK hynix SH920 mSATA 128GB SSD          | 1         | 1      | 1.19%   |
| SK hynix SC300 mSATA 512GB SSD          | 1         | 4      | 1.19%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB | 1         | 1      | 1.19%   |
| Seagate ST96812AS 64GB                  | 1         | 1      | 1.19%   |
| Seagate ST9500423AS 500GB               | 1         | 1      | 1.19%   |
| Seagate ST9500420AS 500GB               | 1         | 1      | 1.19%   |
| Seagate ST9500325AS 500GB               | 1         | 1      | 1.19%   |
| Seagate ST940210AS 40GB                 | 1         | 1      | 1.19%   |
| Seagate ST9320325AS 320GB               | 1         | 1      | 1.19%   |
| Seagate ST9250315AS 250GB               | 1         | 1      | 1.19%   |
| Seagate ST9120823ASG 120GB              | 1         | 1      | 1.19%   |
| Seagate ST500LT012-9WS142 500GB         | 1         | 1      | 1.19%   |
| Seagate ST500LM000-1EJ162 500GB         | 1         | 2      | 1.19%   |
| Seagate ST320LT020-9YG142 320GB         | 1         | 4      | 1.19%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 29     | 24.68%  |
| WDC                 | 15        | 48     | 19.48%  |
| Hitachi             | 11        | 12     | 14.29%  |
| Toshiba             | 9         | 14     | 11.69%  |
| Kingston            | 5         | 5      | 6.49%   |
| Samsung Electronics | 4         | 5      | 5.19%   |
| SK hynix            | 3         | 6      | 3.9%    |
| Micron Technology   | 3         | 3      | 3.9%    |
| SanDisk             | 2         | 4      | 2.6%    |
| Intel               | 2         | 2      | 2.6%    |
| Lenovo              | 1         | 1      | 1.3%    |
| IM3D                | 1         | 1      | 1.3%    |
| HGST                | 1         | 1      | 1.3%    |
| A-DATA Technology   | 1         | 2      | 1.3%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 29     | 35.19%  |
| WDC                 | 13        | 46     | 24.07%  |
| Hitachi             | 11        | 12     | 20.37%  |
| Toshiba             | 9         | 14     | 16.67%  |
| Samsung Electronics | 1         | 2      | 1.85%   |
| HGST                | 1         | 1      | 1.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 51        | 104    | 68.92%  |
| SSD  | 18        | 24     | 24.32%  |
| NVMe | 5         | 5      | 6.76%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST9320325AS 320GB                        | 1         | 1      | 50%     |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD 500GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| Sandisk | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 392       | 610    | 52.76%  |
| Works    | 275       | 444    | 37.01%  |
| Malfunc  | 74        | 133    | 9.96%   |
| Failed   | 2         | 2      | 0.27%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 445       | 55.63%  |
| AMD                              | 89        | 11.13%  |
| Samsung Electronics              | 76        | 9.5%    |
| SanDisk                          | 49        | 6.13%   |
| SK hynix                         | 38        | 4.75%   |
| Micron Technology                | 27        | 3.38%   |
| Toshiba America Info Systems     | 12        | 1.5%    |
| Kingston Technology Company      | 12        | 1.5%    |
| Phison Electronics               | 8         | 1%      |
| Nvidia                           | 7         | 0.88%   |
| MAXIO Technology (Hangzhou)      | 7         | 0.88%   |
| KIOXIA                           | 7         | 0.88%   |
| Silicon Integrated Systems [SiS] | 5         | 0.63%   |
| ADATA Technology                 | 5         | 0.63%   |
| Union Memory (Shenzhen)          | 2         | 0.25%   |
| Micron/Crucial Technology        | 2         | 0.25%   |
| Apple                            | 2         | 0.25%   |
| Yangtze Memory Technologies      | 1         | 0.13%   |
| Solid State Storage Technology   | 1         | 0.13%   |
| Silicon Image                    | 1         | 0.13%   |
| Realtek Semiconductor            | 1         | 0.13%   |
| O2 Micro                         | 1         | 0.13%   |
| Lenovo                           | 1         | 0.13%   |
| ASMedia Technology               | 1         | 0.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 66        | 7.47%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 62        | 7.01%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 37        | 4.19%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 31        | 3.51%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 30        | 3.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 30        | 3.39%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 29        | 3.28%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 25        | 2.83%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 24        | 2.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 23        | 2.6%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 23        | 2.6%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 18        | 2.04%   |
| Intel Volume Management Device NVMe RAID Controller                            | 16        | 1.81%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 14        | 1.58%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 14        | 1.58%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 14        | 1.58%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 13        | 1.47%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 12        | 1.36%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 11        | 1.24%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 11        | 1.24%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 11        | 1.24%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 11        | 1.24%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                   | 9         | 1.02%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 9         | 1.02%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 9         | 1.02%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 8         | 0.9%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 8         | 0.9%    |
| Micron 2200S NVMe SSD [Cassandra]                                              | 8         | 0.9%    |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 8         | 0.9%    |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 8         | 0.9%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 7         | 0.79%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 7         | 0.79%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 6         | 0.68%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 6         | 0.68%   |
| Intel SSD 660P Series                                                          | 6         | 0.68%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 6         | 0.68%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 6         | 0.68%   |
| AMD SB600 IDE                                                                  | 6         | 0.68%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 5         | 0.57%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 5         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 453       | 54.06%  |
| NVMe | 249       | 29.71%  |
| IDE  | 82        | 9.79%   |
| RAID | 54        | 6.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 528       | 76.63%  |
| AMD    | 161       | 23.37%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 5500U with Radeon Graphics        | 12        | 1.74%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 11        | 1.59%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 9         | 1.3%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 9         | 1.3%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 9         | 1.3%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 8         | 1.16%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 7         | 1.01%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 7         | 1.01%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 7         | 1.01%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 7         | 1.01%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 7         | 1.01%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 0.87%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 6         | 0.87%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 6         | 0.87%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 0.87%   |
| AMD Ryzen 7 8845HS w/ Radeon 780M Graphics    | 6         | 0.87%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 6         | 0.87%   |
| AMD Custom APU 0405                           | 6         | 0.87%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 5         | 0.72%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 5         | 0.72%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 5         | 0.72%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 5         | 0.72%   |
| Intel Core i3 CPU M 350 @ 2.27GHz             | 5         | 0.72%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 5         | 0.72%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 5         | 0.72%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 0.72%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 4         | 0.58%   |
| Intel Pentium Dual CPU T2330 @ 1.60GHz        | 4         | 0.58%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 4         | 0.58%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 4         | 0.58%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 0.58%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 0.58%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 4         | 0.58%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 0.58%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 0.58%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 4         | 0.58%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 4         | 0.58%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 4         | 0.58%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 4         | 0.58%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 145       | 21.01%  |
| Intel Core i7                        | 106       | 15.36%  |
| Intel Core i3                        | 59        | 8.55%   |
| Other                                | 53        | 7.68%   |
| Intel Core 2 Duo                     | 45        | 6.52%   |
| AMD Ryzen 5                          | 42        | 6.09%   |
| Intel Pentium                        | 35        | 5.07%   |
| Intel Celeron                        | 35        | 5.07%   |
| AMD Ryzen 7                          | 31        | 4.49%   |
| Intel Atom                           | 12        | 1.74%   |
| Intel Core                           | 11        | 1.59%   |
| Intel Pentium Dual-Core              | 9         | 1.3%    |
| Intel Pentium Dual                   | 9         | 1.3%    |
| AMD Ryzen 3                          | 8         | 1.16%   |
| AMD Ryzen 9                          | 7         | 1.01%   |
| AMD Ryzen 7 PRO                      | 7         | 1.01%   |
| AMD E                                | 7         | 1.01%   |
| AMD A8                               | 6         | 0.87%   |
| AMD A6                               | 6         | 0.87%   |
| Intel Celeron Dual-Core              | 5         | 0.72%   |
| AMD Ryzen 5 PRO                      | 5         | 0.72%   |
| AMD A4                               | 5         | 0.72%   |
| Intel Celeron M                      | 4         | 0.58%   |
| AMD A10                              | 4         | 0.58%   |
| Intel Genuine                        | 3         | 0.43%   |
| Intel Core 2                         | 3         | 0.43%   |
| AMD Turion 64 Mobile                 | 3         | 0.43%   |
| AMD Athlon 64 X2                     | 3         | 0.43%   |
| Intel Pentium Silver                 | 2         | 0.29%   |
| Intel Pentium M                      | 2         | 0.29%   |
| Intel Core 2 Quad                    | 2         | 0.29%   |
| AMD E1                               | 2         | 0.29%   |
| AMD Athlon II                        | 2         | 0.29%   |
| AMD Athlon                           | 2         | 0.29%   |
| Intel Core i9                        | 1         | 0.14%   |
| AMD V140                             | 1         | 0.14%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 1         | 0.14%   |
| AMD Turion X2 Dual-Core Mobile       | 1         | 0.14%   |
| AMD Turion 64 X2 Mobile              | 1         | 0.14%   |
| AMD PRO A10                          | 1         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 344       | 49.93%  |
| 4       | 189       | 27.43%  |
| 6       | 58        | 8.42%   |
| 8       | 49        | 7.11%   |
| 1       | 21        | 3.05%   |
| 14      | 8         | 1.16%   |
| 16      | 6         | 0.87%   |
| 12      | 6         | 0.87%   |
| 24      | 3         | 0.44%   |
| 10      | 3         | 0.44%   |
| 20      | 1         | 0.15%   |
| Unknown | 1         | 0.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 688       | 99.85%  |
| 2      | 1         | 0.15%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 463       | 67.1%   |
| 1       | 225       | 32.61%  |
| 4       | 1         | 0.14%   |
| Unknown | 1         | 0.14%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 674       | 97.26%  |
| Unknown        | 10        | 1.44%   |
| 32-bit         | 9         | 1.3%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 315       | 43.99%  |
| 0x306a9    | 44        | 6.15%   |
| 0x206a7    | 34        | 4.75%   |
| 0x1067a    | 21        | 2.93%   |
| 0x806ea    | 14        | 1.96%   |
| 0x6fd      | 14        | 1.96%   |
| 0x20655    | 14        | 1.96%   |
| 0x306c3    | 13        | 1.82%   |
| 0x906ea    | 11        | 1.54%   |
| 0x10676    | 11        | 1.54%   |
| 0x806e9    | 10        | 1.4%    |
| 0x806c1    | 10        | 1.4%    |
| 0x406e3    | 10        | 1.4%    |
| 0x806ec    | 9         | 1.26%   |
| 0x0a50000c | 9         | 1.26%   |
| 0x506e3    | 8         | 1.12%   |
| 0x08608103 | 8         | 1.12%   |
| 0x40651    | 7         | 0.98%   |
| 0x306d4    | 7         | 0.98%   |
| 0x30678    | 7         | 0.98%   |
| 0x20652    | 7         | 0.98%   |
| 0x06006705 | 6         | 0.84%   |
| 0x706a1    | 5         | 0.7%    |
| 0x08108109 | 5         | 0.7%    |
| 0x506c9    | 4         | 0.56%   |
| 0x406c3    | 4         | 0.56%   |
| 0x106ca    | 4         | 0.56%   |
| 0x0a404102 | 4         | 0.56%   |
| 0x08600106 | 4         | 0.56%   |
| 0x08108102 | 4         | 0.56%   |
| 0x07030105 | 4         | 0.56%   |
| 0x05000119 | 4         | 0.56%   |
| 0xa0652    | 3         | 0.42%   |
| 0x906ed    | 3         | 0.42%   |
| 0x906e9    | 3         | 0.42%   |
| 0x706a8    | 3         | 0.42%   |
| 0x6e8      | 3         | 0.42%   |
| 0x6d8      | 3         | 0.42%   |
| 0x10661    | 3         | 0.42%   |
| 0x08608104 | 3         | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 93        | 13.48%  |
| Unknown           | 74        | 10.72%  |
| IvyBridge         | 62        | 8.99%   |
| SandyBridge       | 45        | 6.52%   |
| Penryn            | 45        | 6.52%   |
| Haswell           | 44        | 6.38%   |
| Core              | 33        | 4.78%   |
| Skylake           | 32        | 4.64%   |
| Westmere          | 30        | 4.35%   |
| Silvermont        | 23        | 3.33%   |
| Zen 3             | 22        | 3.19%   |
| TigerLake         | 20        | 2.9%    |
| Zen 2             | 17        | 2.46%   |
| Broadwell         | 17        | 2.46%   |
| Zen+              | 14        | 2.03%   |
| Excavator         | 13        | 1.88%   |
| Goldmont plus     | 12        | 1.74%   |
| Alderlake Hybrid  | 10        | 1.45%   |
| K8 Hammer         | 9         | 1.3%    |
| CometLake         | 9         | 1.3%    |
| P6                | 8         | 1.16%   |
| Goldmont          | 7         | 1.01%   |
| Bonnell           | 7         | 1.01%   |
| Bobcat            | 7         | 1.01%   |
| Piledriver        | 5         | 0.72%   |
| Puma              | 4         | 0.58%   |
| K8 & K10 hybrid   | 4         | 0.58%   |
| K10               | 4         | 0.58%   |
| IceLake           | 4         | 0.58%   |
| Zen               | 3         | 0.43%   |
| Lunarlake Hybrid  | 3         | 0.43%   |
| K10 Llano         | 3         | 0.43%   |
| Tremont           | 2         | 0.29%   |
| Meteorlake Hybrid | 2         | 0.29%   |
| Steamroller       | 1         | 0.14%   |
| Nehalem           | 1         | 0.14%   |
| Jaguar            | 1         | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 465       | 53.33%  |
| Nvidia                           | 205       | 23.51%  |
| AMD                              | 199       | 22.82%  |
| Silicon Integrated Systems [SiS] | 3         | 0.34%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 58        | 6.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 38        | 4.16%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 26        | 2.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 24        | 2.63%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 24        | 2.63%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 21        | 2.3%    |
| Intel Core Processor Integrated Graphics Controller                                      | 20        | 2.19%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 17        | 1.86%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 17        | 1.86%   |
| AMD Lucienne                                                                             | 17        | 1.86%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 16        | 1.75%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 15        | 1.64%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 15        | 1.64%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 15        | 1.64%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 14        | 1.53%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 14        | 1.53%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 14        | 1.53%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 14        | 1.53%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 13        | 1.42%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 1.42%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 11        | 1.2%    |
| Intel Skylake-H GT2 [HD Graphics 530]                                                    | 11        | 1.2%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 11        | 1.2%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 11        | 1.2%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 11        | 1.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 0.99%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 8         | 0.88%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 8         | 0.88%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 8         | 0.88%   |
| AMD Rembrandt [Radeon 680M]                                                              | 8         | 0.88%   |
| Nvidia GP108M [GeForce MX150]                                                            | 7         | 0.77%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 7         | 0.77%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 7         | 0.77%   |
| AMD HawkPoint1                                                                           | 7         | 0.77%   |
| AMD Barcelo                                                                              | 7         | 0.77%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 6         | 0.66%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 6         | 0.66%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 6         | 0.66%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 0.66%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 308       | 44.25%  |
| Intel + Nvidia | 129       | 18.53%  |
| 1 x AMD        | 127       | 18.25%  |
| 1 x Nvidia     | 49        | 7.04%   |
| AMD + Nvidia   | 28        | 4.02%   |
| Intel + AMD    | 26        | 3.74%   |
| 2 x AMD        | 18        | 2.59%   |
| 2 x Intel      | 8         | 1.15%   |
| 1 x SiS        | 3         | 0.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 604       | 87.03%  |
| Proprietary | 65        | 9.37%   |
| Unknown     | 25        | 3.6%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 417       | 58.98%  |
| 0.01-0.5   | 117       | 16.55%  |
| 1.01-2.0   | 79        | 11.17%  |
| 0.51-1.0   | 41        | 5.8%    |
| 3.01-4.0   | 33        | 4.67%   |
| 7.01-8.0   | 7         | 0.99%   |
| 2.01-3.0   | 6         | 0.85%   |
| 5.01-6.0   | 4         | 0.57%   |
| 8.01-16.0  | 3         | 0.42%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 133       | 16.86%  |
| LG Display              | 114       | 14.45%  |
| BOE                     | 100       | 12.67%  |
| Samsung Electronics     | 98        | 12.42%  |
| Chimei Innolux          | 85        | 10.77%  |
| Chi Mei Optoelectronics | 39        | 4.94%   |
| Dell                    | 25        | 3.17%   |
| Lenovo                  | 21        | 2.66%   |
| Philips                 | 18        | 2.28%   |
| PANDA                   | 16        | 2.03%   |
| Sharp                   | 15        | 1.9%    |
| Hewlett-Packard         | 12        | 1.52%   |
| Apple                   | 11        | 1.39%   |
| LG Philips              | 8         | 1.01%   |
| AOC                     | 8         | 1.01%   |
| Acer                    | 8         | 1.01%   |
| Goldstar                | 7         | 0.89%   |
| CSO                     | 6         | 0.76%   |
| Valve                   | 5         | 0.63%   |
| TMX                     | 5         | 0.63%   |
| Sony                    | 4         | 0.51%   |
| MSI                     | 4         | 0.51%   |
| Ancor Communications    | 4         | 0.51%   |
| InfoVision              | 3         | 0.38%   |
| HannStar                | 3         | 0.38%   |
| CPT                     | 3         | 0.38%   |
| ASUSTek Computer        | 3         | 0.38%   |
| Toshiba                 | 2         | 0.25%   |
| Panasonic               | 2         | 0.25%   |
| JDI                     | 2         | 0.25%   |
| InnoLux Display         | 2         | 0.25%   |
| Iiyama                  | 2         | 0.25%   |
| Fujitsu Siemens         | 2         | 0.25%   |
| BenQ                    | 2         | 0.25%   |
| ViewSonic               | 1         | 0.13%   |
| TMA                     | 1         | 0.13%   |
| Seiko/Epson             | 1         | 0.13%   |
| Quanta Display          | 1         | 0.13%   |
| Plain Tree Systems      | 1         | 0.13%   |
| Olevia                  | 1         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 7         | 0.88%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 7         | 0.88%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 6         | 0.75%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 6         | 0.75%   |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch | 6         | 0.75%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 6         | 0.75%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 5         | 0.63%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 5         | 0.63%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 5         | 0.63%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.63%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 5         | 0.63%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 4         | 0.5%    |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 4         | 0.5%    |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 4         | 0.5%    |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch             | 4         | 0.5%    |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 4         | 0.5%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 4         | 0.5%    |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 4         | 0.5%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 4         | 0.5%    |
| BOE LCD Monitor BOE07F1 1920x1080 344x193mm 15.5-inch                    | 4         | 0.5%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 4         | 0.5%    |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 4         | 0.5%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 4         | 0.5%    |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 3         | 0.38%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 3         | 0.38%   |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch     | 3         | 0.38%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch     | 3         | 0.38%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 3         | 0.38%   |
| LG Display LCD Monitor LGD033B 1366x768 344x194mm 15.5-inch              | 3         | 0.38%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 3         | 0.38%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch              | 3         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 3         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 3         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 3         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 3         | 0.38%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 3         | 0.38%   |
| BOE LCD Monitor BOE08D5 1920x1080 344x194mm 15.5-inch                    | 3         | 0.38%   |
| BOE LCD Monitor BOE07BB 1920x1080 309x173mm 13.9-inch                    | 3         | 0.38%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 3         | 0.38%   |
| BOE LCD Monitor BOE06CB 1920x1080 344x194mm 15.5-inch                    | 3         | 0.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 291       | 39.27%  |
| 1366x768 (WXGA)    | 191       | 25.78%  |
| 1280x800 (WXGA)    | 41        | 5.53%   |
| 1600x900 (HD+)     | 39        | 5.26%   |
| 2560x1440 (QHD)    | 31        | 4.18%   |
| 1920x1200 (WUXGA)  | 25        | 3.37%   |
| 3840x2160 (4K)     | 23        | 3.1%    |
| 1440x900 (WXGA+)   | 17        | 2.29%   |
| 2560x1600          | 13        | 1.75%   |
| 1680x1050 (WSXGA+) | 10        | 1.35%   |
| 2880x1800          | 9         | 1.21%   |
| 1024x600           | 6         | 0.81%   |
| 800x1280           | 5         | 0.67%   |
| 3440x1440          | 5         | 0.67%   |
| 3200x2000          | 5         | 0.67%   |
| Unknown            | 5         | 0.67%   |
| 2160x1440          | 4         | 0.54%   |
| 3840x2400          | 3         | 0.4%    |
| 1280x1024 (SXGA)   | 3         | 0.4%    |
| 1920x1280          | 2         | 0.27%   |
| 1024x768 (XGA)     | 2         | 0.27%   |
| 3200x1800 (QHD+)   | 1         | 0.13%   |
| 3072x1920          | 1         | 0.13%   |
| 3000x2000          | 1         | 0.13%   |
| 2880x1620          | 1         | 0.13%   |
| 2560x1080          | 1         | 0.13%   |
| 2256x1504          | 1         | 0.13%   |
| 2160x1350          | 1         | 0.13%   |
| 1680x945           | 1         | 0.13%   |
| 1600x2560          | 1         | 0.13%   |
| 1400x1050          | 1         | 0.13%   |
| 1280x720 (HD)      | 1         | 0.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 342       | 43.4%   |
| 14      | 92        | 11.68%  |
| 13      | 86        | 10.91%  |
| 17      | 45        | 5.71%   |
| 24      | 36        | 4.57%   |
| 27      | 26        | 3.3%    |
| 12      | 20        | 2.54%   |
| 23      | 19        | 2.41%   |
| 16      | 18        | 2.28%   |
| 11      | 13        | 1.65%   |
| 21      | 12        | 1.52%   |
| Unknown | 12        | 1.52%   |
| 18      | 10        | 1.27%   |
| 22      | 8         | 1.02%   |
| 31      | 7         | 0.89%   |
| 34      | 6         | 0.76%   |
| 10      | 6         | 0.76%   |
| 7       | 5         | 0.63%   |
| 19      | 4         | 0.51%   |
| 25      | 3         | 0.38%   |
| 84      | 2         | 0.25%   |
| 26      | 2         | 0.25%   |
| 20      | 2         | 0.25%   |
| 100     | 1         | 0.13%   |
| 86      | 1         | 0.13%   |
| 75      | 1         | 0.13%   |
| 72      | 1         | 0.13%   |
| 58      | 1         | 0.13%   |
| 54      | 1         | 0.13%   |
| 50      | 1         | 0.13%   |
| 46      | 1         | 0.13%   |
| 40      | 1         | 0.13%   |
| 33      | 1         | 0.13%   |
| 32      | 1         | 0.13%   |
| 8       | 1         | 0.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 481       | 61.67%  |
| 201-300        | 85        | 10.9%   |
| 501-600        | 76        | 9.74%   |
| 351-400        | 57        | 7.31%   |
| 401-500        | 33        | 4.23%   |
| Unknown        | 12        | 1.54%   |
| 601-700        | 11        | 1.41%   |
| 701-800        | 8         | 1.03%   |
| 1001-1500      | 5         | 0.64%   |
| 1-100          | 5         | 0.64%   |
| 1501-2000      | 4         | 0.51%   |
| More than 2000 | 1         | 0.13%   |
| 801-900        | 1         | 0.13%   |
| 101-200        | 1         | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 536       | 76.68%  |
| 16/10   | 123       | 17.6%   |
| Unknown | 11        | 1.57%   |
| 3/2     | 10        | 1.43%   |
| 21/9    | 6         | 0.86%   |
| 0.67    | 4         | 0.57%   |
| 5/4     | 3         | 0.43%   |
| 4/3     | 3         | 0.43%   |
| 0.63    | 1         | 0.14%   |
| 0.62    | 1         | 0.14%   |
| 0.56    | 1         | 0.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 338       | 43.11%  |
| 81-90          | 142       | 18.11%  |
| 201-250        | 60        | 7.65%   |
| 71-80          | 35        | 4.46%   |
| 121-130        | 33        | 4.21%   |
| 301-350        | 28        | 3.57%   |
| 61-70          | 20        | 2.55%   |
| 111-120        | 17        | 2.17%   |
| 351-500        | 15        | 1.91%   |
| 51-60          | 13        | 1.66%   |
| 141-150        | 13        | 1.66%   |
| 251-300        | 12        | 1.53%   |
| 131-140        | 12        | 1.53%   |
| Unknown        | 12        | 1.53%   |
| More than 1000 | 9         | 1.15%   |
| 151-200        | 8         | 1.02%   |
| 41-50          | 6         | 0.77%   |
| 1-40           | 6         | 0.77%   |
| 91-100         | 3         | 0.38%   |
| 501-1000       | 2         | 0.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 301       | 38.99%  |
| 101-120       | 209       | 27.07%  |
| 51-100        | 159       | 20.6%   |
| 161-240       | 58        | 7.51%   |
| More than 240 | 25        | 3.24%   |
| Unknown       | 12        | 1.55%   |
| 1-50          | 8         | 1.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 544       | 77.49%  |
| 2     | 125       | 17.81%  |
| 0     | 22        | 3.13%   |
| 3     | 11        | 1.57%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 346       | 30.78%  |
| Intel                             | 338       | 30.07%  |
| Qualcomm Atheros                  | 174       | 15.48%  |
| Broadcom                          | 74        | 6.58%   |
| MediaTek                          | 32        | 2.85%   |
| Broadcom Limited                  | 21        | 1.87%   |
| Marvell Technology Group          | 18        | 1.6%    |
| Ralink                            | 16        | 1.42%   |
| Xiaomi                            | 8         | 0.71%   |
| Shenzhen Goodix Technology        | 8         | 0.71%   |
| TP-Link                           | 7         | 0.62%   |
| Dell                              | 7         | 0.62%   |
| Sierra Wireless                   | 6         | 0.53%   |
| Nvidia                            | 6         | 0.53%   |
| Fibocom                           | 6         | 0.53%   |
| Hewlett-Packard                   | 5         | 0.44%   |
| Ralink Technology                 | 4         | 0.36%   |
| Qualcomm                          | 4         | 0.36%   |
| Ericsson Business Mobile Networks | 4         | 0.36%   |
| ASIX Electronics                  | 4         | 0.36%   |
| Samsung Electronics               | 3         | 0.27%   |
| Qualcomm Atheros Communications   | 3         | 0.27%   |
| Lenovo                            | 3         | 0.27%   |
| JMicron Technology                | 3         | 0.27%   |
| DisplayLink                       | 3         | 0.27%   |
| D-Link                            | 3         | 0.27%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.18%   |
| Huawei Technologies               | 2         | 0.18%   |
| ASUSTek Computer                  | 2         | 0.18%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.09%   |
| T & A Mobile Phones               | 1         | 0.09%   |
| Spreadtrum Communications         | 1         | 0.09%   |
| Sigma Sport                       | 1         | 0.09%   |
| SIEMENS                           | 1         | 0.09%   |
| OPPO Electronics                  | 1         | 0.09%   |
| Nokia Mobile Phones               | 1         | 0.09%   |
| Microsoft                         | 1         | 0.09%   |
| ICS Advent                        | 1         | 0.09%   |
| Google                            | 1         | 0.09%   |
| Attansic Technology               | 1         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 213       | 15.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 52        | 3.87%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 44        | 3.28%   |
| Intel Wireless 8265 / 8275                                              | 34        | 2.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 29        | 2.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 23        | 1.71%   |
| Intel Wi-Fi 6 AX200                                                     | 21        | 1.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 21        | 1.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 20        | 1.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 20        | 1.49%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 20        | 1.49%   |
| Intel Wireless 8260                                                     | 17        | 1.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 16        | 1.19%   |
| Intel Wireless 7260                                                     | 16        | 1.19%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 15        | 1.12%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 15        | 1.12%   |
| Intel Wi-Fi 6 AX201                                                     | 15        | 1.12%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]    | 14        | 1.04%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 14        | 1.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 13        | 0.97%   |
| Intel Wireless 3165                                                     | 13        | 0.97%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 0.89%   |
| Intel Wireless 7265                                                     | 12        | 0.89%   |
| Intel Ethernet Connection (4) I219-LM                                   | 12        | 0.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 11        | 0.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 11        | 0.82%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 10        | 0.74%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 10        | 0.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 10        | 0.74%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 10        | 0.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 10        | 0.74%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 9         | 0.67%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 9         | 0.67%   |
| Intel WiFi Link 5100                                                    | 9         | 0.67%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 9         | 0.67%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 9         | 0.67%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 9         | 0.67%   |
| Intel Ethernet Connection I219-LM                                       | 9         | 0.67%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 9         | 0.67%   |
| Intel 82567LM Gigabit Network Connection                                | 9         | 0.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 314       | 44.1%   |
| Qualcomm Atheros                | 147       | 20.65%  |
| Realtek Semiconductor           | 94        | 13.2%   |
| Broadcom                        | 51        | 7.16%   |
| MediaTek                        | 30        | 4.21%   |
| Broadcom Limited                | 18        | 2.53%   |
| Ralink                          | 16        | 2.25%   |
| TP-Link                         | 7         | 0.98%   |
| Sierra Wireless                 | 6         | 0.84%   |
| Fibocom                         | 6         | 0.84%   |
| Dell                            | 5         | 0.7%    |
| Ralink Technology               | 4         | 0.56%   |
| Qualcomm                        | 4         | 0.56%   |
| Qualcomm Atheros Communications | 3         | 0.42%   |
| D-Link                          | 3         | 0.42%   |
| ASUSTek Computer                | 2         | 0.28%   |
| Microsoft                       | 1         | 0.14%   |
| Unknown                         | 1         | 0.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 44        | 6.14%   |
| Intel Wireless 8265 / 8275                                              | 34        | 4.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 23        | 3.21%   |
| Intel Wi-Fi 6 AX200                                                     | 21        | 2.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 20        | 2.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 20        | 2.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 20        | 2.79%   |
| Intel Wireless 8260                                                     | 17        | 2.37%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 16        | 2.23%   |
| Intel Wireless 7260                                                     | 16        | 2.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 15        | 2.09%   |
| Intel Wi-Fi 6 AX201                                                     | 15        | 2.09%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 14        | 1.95%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]    | 14        | 1.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 14        | 1.95%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 13        | 1.81%   |
| Intel Wireless 3165                                                     | 13        | 1.81%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 1.67%   |
| Intel Wireless 7265                                                     | 12        | 1.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 11        | 1.53%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 11        | 1.53%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 10        | 1.39%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 10        | 1.39%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 10        | 1.39%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 10        | 1.39%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 9         | 1.26%   |
| Intel WiFi Link 5100                                                    | 9         | 1.26%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 9         | 1.26%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 9         | 1.26%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 9         | 1.26%   |
| Broadcom BCM43142 802.11b/g/n                                           | 9         | 1.26%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 8         | 1.12%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 7         | 0.98%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 7         | 0.98%   |
| Intel Centrino Wireless-N 2230                                          | 7         | 0.98%   |
| Intel Centrino Ultimate-N 6300                                          | 7         | 0.98%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 7         | 0.98%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 6         | 0.84%   |
| Intel Meteor Lake PCH CNVi WiFi                                         | 6         | 0.84%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 6         | 0.84%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 307       | 52.12%  |
| Intel                            | 140       | 23.77%  |
| Qualcomm Atheros                 | 53        | 9%      |
| Broadcom                         | 27        | 4.58%   |
| Marvell Technology Group         | 18        | 3.06%   |
| Xiaomi                           | 8         | 1.36%   |
| Nvidia                           | 6         | 1.02%   |
| ASIX Electronics                 | 4         | 0.68%   |
| Samsung Electronics              | 3         | 0.51%   |
| Lenovo                           | 3         | 0.51%   |
| JMicron Technology               | 3         | 0.51%   |
| DisplayLink                      | 3         | 0.51%   |
| Broadcom Limited                 | 3         | 0.51%   |
| MediaTek                         | 2         | 0.34%   |
| T & A Mobile Phones              | 1         | 0.17%   |
| Spreadtrum Communications        | 1         | 0.17%   |
| Silicon Integrated Systems [SiS] | 1         | 0.17%   |
| OPPO Electronics                 | 1         | 0.17%   |
| Nokia Mobile Phones              | 1         | 0.17%   |
| ICS Advent                       | 1         | 0.17%   |
| Huawei Technologies              | 1         | 0.17%   |
| Google                           | 1         | 0.17%   |
| Attansic Technology              | 1         | 0.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 213       | 35.62%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 52        | 8.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 29        | 4.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 21        | 3.51%   |
| Intel Ethernet Connection (4) I219-LM                                          | 12        | 2.01%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 10        | 1.67%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 9         | 1.51%   |
| Intel Ethernet Connection I219-LM                                              | 9         | 1.51%   |
| Intel 82567LM Gigabit Network Connection                                       | 9         | 1.51%   |
| Intel Ethernet Connection I217-LM                                              | 8         | 1.34%   |
| Intel Ethernet Connection (4) I219-V                                           | 8         | 1.34%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 7         | 1.17%   |
| Intel Ethernet Connection (3) I218-LM                                          | 7         | 1.17%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 6         | 1%      |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 6         | 1%      |
| Intel Ethernet Connection (7) I219-LM                                          | 6         | 1%      |
| Intel Ethernet Connection (6) I219-V                                           | 6         | 1%      |
| Intel Ethernet Connection (2) I219-LM                                          | 6         | 1%      |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 5         | 0.84%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 5         | 0.84%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 5         | 0.84%   |
| Intel Ethernet Connection I218-LM                                              | 5         | 0.84%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 5         | 0.84%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 4         | 0.67%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                          | 4         | 0.67%   |
| Intel Ethernet Connection I217-V                                               | 4         | 0.67%   |
| Intel 82577LM Gigabit Network Connection                                       | 4         | 0.67%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 3         | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                                  | 3         | 0.5%    |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 0.5%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 3         | 0.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 3         | 0.5%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 3         | 0.5%    |
| Nvidia MCP79 Ethernet                                                          | 3         | 0.5%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 3         | 0.5%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 3         | 0.5%    |
| Intel Ethernet Connection (6) I219-LM                                          | 3         | 0.5%    |
| Intel 82566MM Gigabit Network Connection                                       | 3         | 0.5%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 3         | 0.5%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 3         | 0.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 673       | 53.24%  |
| Ethernet | 563       | 44.54%  |
| Modem    | 27        | 2.14%   |
| Unknown  | 1         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 555       | 77.41%  |
| Ethernet | 162       | 22.59%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 513       | 74.13%  |
| 1     | 165       | 23.84%  |
| 3     | 7         | 1.01%   |
| 0     | 7         | 1.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 634       | 91.35%  |
| Yes  | 60        | 8.65%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 223       | 40.69%  |
| Realtek Semiconductor           | 51        | 9.31%   |
| IMC Networks                    | 45        | 8.21%   |
| Qualcomm Atheros Communications | 44        | 8.03%   |
| Broadcom                        | 32        | 5.84%   |
| Foxconn / Hon Hai               | 30        | 5.47%   |
| Lite-On Technology              | 28        | 5.11%   |
| Hewlett-Packard                 | 14        | 2.55%   |
| ASUSTek Computer                | 13        | 2.37%   |
| Dell                            | 11        | 2.01%   |
| Ralink                          | 10        | 1.82%   |
| Cambridge Silicon Radio         | 10        | 1.82%   |
| Apple                           | 8         | 1.46%   |
| Toshiba                         | 7         | 1.28%   |
| MediaTek                        | 4         | 0.73%   |
| Foxconn International           | 4         | 0.73%   |
| USI                             | 3         | 0.55%   |
| Realtek                         | 3         | 0.55%   |
| Micro Star International        | 3         | 0.55%   |
| Taiyo Yuden                     | 2         | 0.36%   |
| Ralink Technology               | 1         | 0.18%   |
| Fujitsu                         | 1         | 0.18%   |
| Alps Electric                   | 1         | 0.18%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 91        | 16.58%  |
| Intel AX201 Bluetooth                               | 38        | 6.92%   |
| Realtek Bluetooth Radio                             | 36        | 6.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 28        | 5.1%    |
| Intel Bluetooth Device                              | 22        | 4.01%   |
| Intel AX200 Bluetooth                               | 20        | 3.64%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 19        | 3.46%   |
| IMC Networks Bluetooth Radio                        | 19        | 3.46%   |
| Foxconn / Hon Hai Wireless_Device                   | 12        | 2.19%   |
| Qualcomm Atheros  Bluetooth Device                  | 11        | 2%      |
| Ralink RT3290 Bluetooth                             | 10        | 1.82%   |
| Intel AX210 Bluetooth                               | 10        | 1.82%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 10        | 1.82%   |
| Lite-On Bluetooth Device                            | 9         | 1.64%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 9         | 1.64%   |
| IMC Networks Wireless_Device                        | 9         | 1.64%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 9         | 1.64%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 8         | 1.46%   |
| Realtek  Bluetooth 4.2 Adapter                      | 7         | 1.28%   |
| IMC Networks Bluetooth Device                       | 7         | 1.28%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 7         | 1.28%   |
| Realtek RTL8821A Bluetooth                          | 6         | 1.09%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6         | 1.09%   |
| Broadcom HP Portable SoftSailing                    | 6         | 1.09%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 1.09%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 6         | 1.09%   |
| Lite-On Wireless_Device                             | 5         | 0.91%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 5         | 0.91%   |
| HP Broadcom 2070 Bluetooth Combo                    | 5         | 0.91%   |
| MediaTek Wireless_Device                            | 4         | 0.73%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 4         | 0.73%   |
| Foxconn International BCM43142A0 Bluetooth module   | 4         | 0.73%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 0.73%   |
| Dell BCM20702A0 Bluetooth Module                    | 4         | 0.73%   |
| Apple Bluetooth Host Controller                     | 4         | 0.73%   |
| USI Bluetooth Device                                | 3         | 0.55%   |
| Toshiba Integrated Bluetooth HCI                    | 3         | 0.55%   |
| Realtek Bluetooth Radio                             | 3         | 0.55%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 0.55%   |
| Micro Star International Bluetooth EDR Device       | 3         | 0.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 513       | 60.14%  |
| AMD                              | 183       | 21.45%  |
| Nvidia                           | 105       | 12.31%  |
| GN Netcom                        | 9         | 1.06%   |
| C-Media Electronics              | 9         | 1.06%   |
| Silicon Integrated Systems [SiS] | 5         | 0.59%   |
| Realtek Semiconductor            | 4         | 0.47%   |
| Lenovo                           | 4         | 0.47%   |
| Samson Technologies              | 2         | 0.23%   |
| Logitech                         | 2         | 0.23%   |
| JMTek                            | 2         | 0.23%   |
| Hewlett-Packard                  | 2         | 0.23%   |
| Focusrite-Novation               | 2         | 0.23%   |
| Yamaha                           | 1         | 0.12%   |
| Trust                            | 1         | 0.12%   |
| Textech International            | 1         | 0.12%   |
| Texas Instruments                | 1         | 0.12%   |
| Plantronics                      | 1         | 0.12%   |
| KTMicro                          | 1         | 0.12%   |
| FiiO Electronics Technology      | 1         | 0.12%   |
| Behringer.......                 | 1         | 0.12%   |
| ASUSTek Computer                 | 1         | 0.12%   |
| Apple                            | 1         | 0.12%   |
| AKAI Professional M.I.           | 1         | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                              | 100       | 9.66%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 72        | 6.96%   |
| Intel Sunrise Point-LP HD Audio                                            | 60        | 5.8%    |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 50        | 4.83%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 40        | 3.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 34        | 3.29%   |
| AMD Radeon High Definition Audio Controller                                | 33        | 3.19%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 31        | 3%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 30        | 2.9%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 27        | 2.61%   |
| Intel Cannon Lake PCH cAVS                                                 | 21        | 2.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 20        | 1.93%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 20        | 1.93%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 19        | 1.84%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 17        | 1.64%   |
| Intel Broadwell-U Audio Controller                                         | 17        | 1.64%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 16        | 1.55%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 15        | 1.45%   |
| AMD FCH Azalia Controller                                                  | 15        | 1.45%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 14        | 1.35%   |
| Intel Haswell-ULT HD Audio Controller                                      | 14        | 1.35%   |
| Intel 8 Series HD Audio Controller                                         | 14        | 1.35%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 13        | 1.26%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 13        | 1.26%   |
| Intel Comet Lake PCH-LP cAVS                                               | 12        | 1.16%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 12        | 1.16%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 12        | 1.16%   |
| Nvidia GF108 High Definition Audio Controller                              | 11        | 1.06%   |
| AMD High Definition Audio Controller                                       | 11        | 1.06%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 10        | 0.97%   |
| Intel Comet Lake PCH cAVS                                                  | 8         | 0.77%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 7         | 0.68%   |
| Nvidia High Definition Audio Controller                                    | 7         | 0.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 7         | 0.68%   |
| AMD Kabini HDMI/DP Audio                                                   | 7         | 0.68%   |
| Nvidia TU106 High Definition Audio Controller                              | 6         | 0.58%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 6         | 0.58%   |
| Nvidia GA107 High Definition Audio Controller                              | 6         | 0.58%   |
| Nvidia GA106 High Definition Audio Controller                              | 6         | 0.58%   |
| Intel Meteor Lake-P HD Audio Controller                                    | 6         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 116       | 24.07%  |
| SK hynix                     | 112       | 23.24%  |
| Micron Technology            | 65        | 13.49%  |
| Kingston                     | 55        | 11.41%  |
| Unknown                      | 44        | 9.13%   |
| Crucial                      | 23        | 4.77%   |
| Ramaxel Technology           | 15        | 3.11%   |
| Elpida                       | 11        | 2.28%   |
| Patriot                      | 6         | 1.24%   |
| A-DATA Technology            | 6         | 1.24%   |
| Unknown (ABCD)               | 5         | 1.04%   |
| Nanya Technology             | 5         | 1.04%   |
| Corsair                      | 5         | 1.04%   |
| Transcend                    | 2         | 0.41%   |
| ASint Technology             | 2         | 0.41%   |
| Apacer                       | 2         | 0.41%   |
| Unigen                       | 1         | 0.21%   |
| SHARETRONIC                  | 1         | 0.21%   |
| Patriot Memory (PDP Systems) | 1         | 0.21%   |
| Hikvision                    | 1         | 0.21%   |
| G.Skill                      | 1         | 0.21%   |
| Atermiter                    | 1         | 0.21%   |
| 48spaces                     | 1         | 0.21%   |
| Unknown                      | 1         | 0.21%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 1.36%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 1.36%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 6         | 1.16%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 1.16%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 1.16%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 0.97%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 0.97%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 5         | 0.97%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.97%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 0.97%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s           | 5         | 0.97%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 4         | 0.78%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 4         | 0.78%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.78%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 4         | 0.78%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.78%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.78%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.78%   |
| Micron RAM MT8KTF51264HZ-1G6 4GB SODIMM DDR3 1600MT/s            | 4         | 0.78%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 4         | 0.78%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 3         | 0.58%   |
| Unknown RAM Module 2GB SODIMM 800MT/s                            | 3         | 0.58%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.58%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 2667MT/s           | 3         | 0.58%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GiB SODIMM DDR3 2667MT/s          | 3         | 0.58%   |
| SK hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 3         | 0.58%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 3         | 0.58%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.58%   |
| SK hynix RAM H9HCNNNBKMMLXR-NEE 4GB SODIMM LPDDR4 4266MT/s       | 3         | 0.58%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 0.58%   |
| Samsung RAM M425R2GA3PB0-CWMOL 16GB SODIMM DDR5 5600MT/s         | 3         | 0.58%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s          | 3         | 0.58%   |
| Patriot RAM PSD34G16002S 4GB SODIMM DDR3 4199MT/s                | 3         | 0.58%   |
| Patriot RAM PSD34G13332S 4GB SODIMM DDR3 1334MT/s                | 3         | 0.58%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.58%   |
| Micron RAM 16JSF25664HZ-1G1F1 2GB SODIMM 1067MT/s                | 3         | 0.58%   |
| Kingston RAM KHX1866C11S3L/8G 8GB SODIMM DDR3 1867MT/s           | 3         | 0.58%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s            | 3         | 0.58%   |
| Crucial RAM CT8G4SFRA32A.M4FE 8GB SODIMM DDR4 3200MT/s           | 3         | 0.58%   |
| Crucial RAM CT51264BF160BJ.C8F 4GB SODIMM DDR3 1600MT/s          | 3         | 0.58%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 136       | 34.34%  |
| DDR3    | 134       | 33.84%  |
| DDR2    | 31        | 7.83%   |
| SDRAM   | 22        | 5.56%   |
| LPDDR4  | 21        | 5.3%    |
| LPDDR5  | 19        | 4.8%    |
| DDR5    | 16        | 4.04%   |
| LPDDR3  | 7         | 1.77%   |
| Unknown | 7         | 1.77%   |
| DDR     | 2         | 0.51%   |
| DRAM    | 1         | 0.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 352       | 88.89%  |
| Row Of Chips | 38        | 9.6%    |
| Chip         | 4         | 1.01%   |
| DIMM         | 1         | 0.25%   |
| Unknown      | 1         | 0.25%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 145       | 32.81%  |
| 4096  | 124       | 28.05%  |
| 2048  | 72        | 16.29%  |
| 16384 | 58        | 13.12%  |
| 1024  | 27        | 6.11%   |
| 32768 | 14        | 3.17%   |
| 512   | 2         | 0.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 96        | 22.07%  |
| 3200    | 72        | 16.55%  |
| 2667    | 56        | 12.87%  |
| 667     | 22        | 5.06%   |
| 2400    | 21        | 4.83%   |
| 2133    | 18        | 4.14%   |
| 1334    | 18        | 4.14%   |
| 4199    | 13        | 2.99%   |
| 1333    | 12        | 2.76%   |
| 1067    | 11        | 2.53%   |
| Unknown | 10        | 2.3%    |
| 6400    | 9         | 2.07%   |
| 5600    | 9         | 2.07%   |
| 800     | 9         | 2.07%   |
| 2048    | 8         | 1.84%   |
| 7500    | 7         | 1.61%   |
| 4800    | 7         | 1.61%   |
| 4266    | 6         | 1.38%   |
| 4267    | 5         | 1.15%   |
| 1867    | 5         | 1.15%   |
| 8400    | 4         | 0.92%   |
| 533     | 4         | 0.92%   |
| 8533    | 2         | 0.46%   |
| 3266    | 2         | 0.46%   |
| 975     | 2         | 0.46%   |
| 8000    | 1         | 0.23%   |
| 5500    | 1         | 0.23%   |
| 2933    | 1         | 0.23%   |
| 1866    | 1         | 0.23%   |
| 1639    | 1         | 0.23%   |
| 1066    | 1         | 0.23%   |
| 333     | 1         | 0.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 3         | 50%     |
| Seiko Epson           | 1         | 16.67%  |
| Samsung Electronics   | 1         | 16.67%  |
| Lexmark International | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Seiko Epson L380 Series           | 1         | 16.67%  |
| Samsung M2070 Series              | 1         | 16.67%  |
| Lexmark International 2600 Series | 1         | 16.67%  |
| HP LaserJet P1006                 | 1         | 16.67%  |
| HP LaserJet CP 1025               | 1         | 16.67%  |
| HP LaserJet 1018                  | 1         | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 50%     |
| Canon           | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| HP Scanjet 200          | 1         | 50%     |
| Canon CanoScan LiDE 110 | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 162       | 27.74%  |
| IMC Networks                           | 68        | 11.64%  |
| Bison Electronics                      | 54        | 9.25%   |
| Microdia                               | 52        | 8.9%    |
| Realtek Semiconductor                  | 44        | 7.53%   |
| Sunplus Innovation Technology          | 33        | 5.65%   |
| Quanta                                 | 24        | 4.11%   |
| Suyin                                  | 23        | 3.94%   |
| Syntek                                 | 20        | 3.42%   |
| Cheng Uei Precision Industry (Foxlink) | 17        | 2.91%   |
| Lite-On Technology                     | 10        | 1.71%   |
| Luxvisions Innotech Limited            | 9         | 1.54%   |
| Sonix Technology                       | 8         | 1.37%   |
| Silicon Motion                         | 6         | 1.03%   |
| SunplusIT                              | 4         | 0.68%   |
| Shinetech                              | 4         | 0.68%   |
| Ricoh                                  | 4         | 0.68%   |
| Apple                                  | 4         | 0.68%   |
| Alcor Micro                            | 4         | 0.68%   |
| Samsung Electronics                    | 3         | 0.51%   |
| Primax Electronics                     | 3         | 0.51%   |
| Logitech                               | 3         | 0.51%   |
| GEMBIRD                                | 3         | 0.51%   |
| Lenovo                                 | 2         | 0.34%   |
| Importek                               | 2         | 0.34%   |
| DigiTech                               | 2         | 0.34%   |
| BillionPixels                          | 2         | 0.34%   |
| Z-Star Microelectronics                | 1         | 0.17%   |
| Tripath Technology                     | 1         | 0.17%   |
| SN0002                                 | 1         | 0.17%   |
| Shine-optics                           | 1         | 0.17%   |
| OmniVision Technologies                | 1         | 0.17%   |
| Microsoft                              | 1         | 0.17%   |
| MacroSilicon                           | 1         | 0.17%   |
| LG Electronics                         | 1         | 0.17%   |
| kingcome                               | 1         | 0.17%   |
| icSpring                               | 1         | 0.17%   |
| Elecom                                 | 1         | 0.17%   |
| Creative Technology                    | 1         | 0.17%   |
| ALi                                    | 1         | 0.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 40        | 6.8%    |
| Microdia Integrated_Webcam_HD            | 22        | 3.74%   |
| IMC Networks Integrated Camera           | 19        | 3.23%   |
| Bison Integrated Camera                  | 17        | 2.89%   |
| IMC Networks USB2.0 HD UVC WebCam        | 15        | 2.55%   |
| Realtek Integrated_Webcam_HD             | 12        | 2.04%   |
| Syntek Integrated Camera                 | 11        | 1.87%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 11        | 1.87%   |
| Chicony HD WebCam                        | 11        | 1.87%   |
| Chicony HP HD Webcam [Fixed]             | 10        | 1.7%    |
| Sunplus Integrated_Webcam_HD             | 9         | 1.53%   |
| Bison Lenovo EasyCamera                  | 9         | 1.53%   |
| Quanta HP HD Camera                      | 8         | 1.36%   |
| Sunplus HD WebCam                        | 7         | 1.19%   |
| Realtek USB2.0 HD UVC WebCam             | 7         | 1.19%   |
| Chicony HP HD Camera                     | 7         | 1.19%   |
| Bison Lenovo Integrated Webcam           | 7         | 1.19%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 6         | 1.02%   |
| Bison EasyCamera                         | 6         | 1.02%   |
| Sunplus HP HD Webcam [Fixed]             | 5         | 0.85%   |
| Sonix USB2.0 HD UVC WebCam               | 5         | 0.85%   |
| Microdia Integrated Webcam               | 5         | 0.85%   |
| Lite-On HP HD Camera                     | 5         | 0.85%   |
| IMC Networks 2M Integrated Webcam        | 5         | 0.85%   |
| Chicony USB2.0 VGA UVC WebCam            | 5         | 0.85%   |
| Chicony Integrated Camera (1280x720@30)  | 5         | 0.85%   |
| Chicony HP HD Webcam                     | 5         | 0.85%   |
| Syntek Lenovo EasyCamera                 | 4         | 0.68%   |
| Suyin HP Webcam                          | 4         | 0.68%   |
| Quanta HD User Facing                    | 4         | 0.68%   |
| Microdia Webcam Vitade AF                | 4         | 0.68%   |
| IMC Networks Integrated Webcam           | 4         | 0.68%   |
| Chicony USB2.0 HD UVC WebCam             | 4         | 0.68%   |
| Chicony USB 2.0 Camera                   | 4         | 0.68%   |
| Chicony TOSHIBA Web Camera - HD          | 4         | 0.68%   |
| Chicony Lenovo EasyCamera                | 4         | 0.68%   |
| Chicony Integrated IR Camera             | 4         | 0.68%   |
| Chicony EasyCamera                       | 4         | 0.68%   |
| Syntek EasyCamera                        | 3         | 0.51%   |
| Suyin HP Integrated Webcam               | 3         | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 61        | 46.21%  |
| Synaptics                          | 33        | 25%     |
| Shenzhen Goodix Technology         | 12        | 9.09%   |
| AuthenTec                          | 11        | 8.33%   |
| LighTuning Technology              | 5         | 3.79%   |
| Upek                               | 3         | 2.27%   |
| STMicroelectronics                 | 3         | 2.27%   |
| Elan Microelectronics              | 2         | 1.52%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.76%   |
| HOLTEK                             | 1         | 0.76%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 16        | 12.12%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 11        | 8.33%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 7         | 5.3%    |
| Shenzhen Goodix  FingerPrint Device                                        | 7         | 5.3%    |
| Validity Sensors VFS491                                                    | 6         | 4.55%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 4.55%   |
| Synaptics Fingerprint reader [HP G6]                                       | 6         | 4.55%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 3.79%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 3.03%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 3.03%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 3.03%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 4         | 3.03%   |
| AuthenTec AES1600                                                          | 4         | 3.03%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 2.27%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 2.27%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 2.27%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 2.27%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 2.27%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 2.27%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 2.27%   |
| AuthenTec AES2810                                                          | 3         | 2.27%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 1.52%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 1.52%   |
| Synaptics WBDI                                                             | 2         | 1.52%   |
| Synaptics UWP WBDI Device                                                  | 2         | 1.52%   |
| Synaptics  WBDI                                                            | 2         | 1.52%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.52%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 1.52%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 1.52%   |
| Elan ELAN:Fingerprint                                                      | 2         | 1.52%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.76%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.76%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.76%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.76%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.76%   |
| HOLTEK FocalTech Fingerprint Device                                        | 1         | 0.76%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Broadcom             | 30        | 42.25%  |
| Alcor Micro          | 26        | 36.62%  |
| O2 Micro             | 7         | 9.86%   |
| Lenovo               | 3         | 4.23%   |
| Upek                 | 2         | 2.82%   |
| Bit4id               | 2         | 2.82%   |
| Microchip Technology | 1         | 1.41%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 26        | 36.62%  |
| Broadcom 5880                                                                | 11        | 15.49%  |
| Broadcom BCM5880 Secure Applications Processor                               | 8         | 11.27%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 7.04%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 5         | 7.04%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 4.23%   |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 3         | 4.23%   |
| Broadcom 58200                                                               | 3         | 4.23%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 2.82%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 2.82%   |
| Bit4id miniLector EVO                                                        | 2         | 2.82%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 1.41%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 396       | 55.93%  |
| 1     | 239       | 33.76%  |
| 2     | 63        | 8.9%    |
| 3     | 9         | 1.27%   |
| 4     | 1         | 0.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 132       | 34.55%  |
| Graphics card            | 87        | 22.77%  |
| Chipcard                 | 60        | 15.71%  |
| Net/wireless             | 21        | 5.5%    |
| Multimedia controller    | 19        | 4.97%   |
| Bluetooth                | 12        | 3.14%   |
| Card reader              | 10        | 2.62%   |
| Storage                  | 9         | 2.36%   |
| Communication controller | 9         | 2.36%   |
| Modem                    | 7         | 1.83%   |
| Camera                   | 6         | 1.57%   |
| Network                  | 4         | 1.05%   |
| Sound                    | 2         | 0.52%   |
| Flash memory             | 2         | 0.52%   |
| Storage/ide              | 1         | 0.26%   |
| Net/ethernet             | 1         | 0.26%   |


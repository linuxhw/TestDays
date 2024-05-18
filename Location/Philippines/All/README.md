Linux in Philippines - Tested Hardware & Statistics
---------------------------------------------------

A project to collect tested hardware configurations for Linux in Philippines.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Philippines/Desktop/README.md) and [notebooks](/Location/Philippines/Notebook/README.md).

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

Total: 1090

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| AZW           | MINI S                      | Desktop     | [12557a4240](https://linux-hardware.org/?probe=12557a4240) | May 09, 2024 |
| AZW           | MINI S                      | Desktop     | [7c8e83b2ed](https://linux-hardware.org/?probe=7c8e83b2ed) | May 09, 2024 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [5c2ce66225](https://linux-hardware.org/?probe=5c2ce66225) | May 08, 2024 |
| Acer          | Predator PH16-71            | Notebook    | [516e53ae7f](https://linux-hardware.org/?probe=516e53ae7f) | May 08, 2024 |
| HP            | ProBook 645 G1              | Notebook    | [02d7e5f984](https://linux-hardware.org/?probe=02d7e5f984) | May 04, 2024 |
| Lenovo        | ThinkPad L530 24812K6       | Notebook    | [e7d0c76f65](https://linux-hardware.org/?probe=e7d0c76f65) | May 01, 2024 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [53cec6c7a1](https://linux-hardware.org/?probe=53cec6c7a1) | May 01, 2024 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [1a48c73aca](https://linux-hardware.org/?probe=1a48c73aca) | Apr 30, 2024 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [1e4b5f233f](https://linux-hardware.org/?probe=1e4b5f233f) | Apr 30, 2024 |
| ASUSTek       | X450CA                      | Notebook    | [60f305379c](https://linux-hardware.org/?probe=60f305379c) | Apr 24, 2024 |
| HP            | ZHAN 66 Pro A 14 G4 Note... | Notebook    | [700a5789b7](https://linux-hardware.org/?probe=700a5789b7) | Apr 24, 2024 |
| HUAWEI        | KLVDZ-WXX9                  | Notebook    | [27a77a0975](https://linux-hardware.org/?probe=27a77a0975) | Apr 23, 2024 |
| ASRock        | A520M-HDV                   | Desktop     | [7fab320f1b](https://linux-hardware.org/?probe=7fab320f1b) | Apr 19, 2024 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [43c66c672d](https://linux-hardware.org/?probe=43c66c672d) | Apr 17, 2024 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [ddf3999a87](https://linux-hardware.org/?probe=ddf3999a87) | Apr 17, 2024 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [32237e05f1](https://linux-hardware.org/?probe=32237e05f1) | Apr 15, 2024 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [c205fddaa6](https://linux-hardware.org/?probe=c205fddaa6) | Apr 14, 2024 |
| System76      | Oryx Pro                    | Notebook    | [ea8426e115](https://linux-hardware.org/?probe=ea8426e115) | Apr 10, 2024 |
| Acer          | Predator PH16-71            | Notebook    | [fc34fae4a8](https://linux-hardware.org/?probe=fc34fae4a8) | Apr 09, 2024 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [b899a5846f](https://linux-hardware.org/?probe=b899a5846f) | Apr 09, 2024 |
| Unknown       | Unknown                     | All in one  | [b37445b5e1](https://linux-hardware.org/?probe=b37445b5e1) | Apr 08, 2024 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [113bdef0c9](https://linux-hardware.org/?probe=113bdef0c9) | Apr 08, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [7e5d44baee](https://linux-hardware.org/?probe=7e5d44baee) | Apr 08, 2024 |
| Acer          | Aspire E1-471               | Notebook    | [60745df0a0](https://linux-hardware.org/?probe=60745df0a0) | Apr 08, 2024 |
| Dell          | XPS 15 9530                 | Notebook    | [213a87b9d0](https://linux-hardware.org/?probe=213a87b9d0) | Apr 07, 2024 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [a02e47dcca](https://linux-hardware.org/?probe=a02e47dcca) | Apr 06, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [439cec9b7a](https://linux-hardware.org/?probe=439cec9b7a) | Apr 05, 2024 |
| HUAWEI        | YTF-XXX                     | Notebook    | [0ca4e52c33](https://linux-hardware.org/?probe=0ca4e52c33) | Apr 04, 2024 |
| HUAWEI        | YTF-XXX                     | Notebook    | [d1703a058f](https://linux-hardware.org/?probe=d1703a058f) | Apr 04, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [c6f0c787bf](https://linux-hardware.org/?probe=c6f0c787bf) | Apr 03, 2024 |
| Acer          | Predator PH16-71            | Notebook    | [9884825f87](https://linux-hardware.org/?probe=9884825f87) | Apr 02, 2024 |
| Dell          | 0J2J3Y A00                  | Desktop     | [34c276b20a](https://linux-hardware.org/?probe=34c276b20a) | Mar 31, 2024 |
| Valve         | Jupiter                     | Notebook    | [1a14e1128b](https://linux-hardware.org/?probe=1a14e1128b) | Mar 29, 2024 |
| Gigabyte      | A620M GAMING X              | Desktop     | [49e76a8df1](https://linux-hardware.org/?probe=49e76a8df1) | Mar 28, 2024 |
| Gigabyte      | A620M GAMING X              | Desktop     | [dc41666398](https://linux-hardware.org/?probe=dc41666398) | Mar 28, 2024 |
| Lenovo        | Legion Y9000P IAH7H 82RF    | Notebook    | [bc908f87b5](https://linux-hardware.org/?probe=bc908f87b5) | Mar 27, 2024 |
| Lenovo        | ThinkPad T480 20L6S4G713    | Notebook    | [00b299696d](https://linux-hardware.org/?probe=00b299696d) | Mar 27, 2024 |
| Lenovo        | ThinkPad T490s 20NYS42N0... | Notebook    | [5c7d81f9a4](https://linux-hardware.org/?probe=5c7d81f9a4) | Mar 27, 2024 |
| ASRock        | B460M Steel Legend          | Desktop     | [81687517db](https://linux-hardware.org/?probe=81687517db) | Mar 26, 2024 |
| ASRock        | B460M Steel Legend          | Desktop     | [fb3bee6574](https://linux-hardware.org/?probe=fb3bee6574) | Mar 26, 2024 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [954efe1d9b](https://linux-hardware.org/?probe=954efe1d9b) | Mar 25, 2024 |
| MSI           | GT62VR 7RE                  | Notebook    | [5a46a7a194](https://linux-hardware.org/?probe=5a46a7a194) | Mar 24, 2024 |
| ASUSTek       | X455LJ                      | Notebook    | [aa4f64e1b7](https://linux-hardware.org/?probe=aa4f64e1b7) | Mar 22, 2024 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [13d3b8e805](https://linux-hardware.org/?probe=13d3b8e805) | Mar 20, 2024 |
| Dell          | XPS 15 7590                 | Notebook    | [7c1ffcae88](https://linux-hardware.org/?probe=7c1ffcae88) | Mar 20, 2024 |
| Dell          | Inspiron 5458               | Notebook    | [0a7979787f](https://linux-hardware.org/?probe=0a7979787f) | Mar 19, 2024 |
| Dell          | Inspiron 5458               | Notebook    | [21e80f0295](https://linux-hardware.org/?probe=21e80f0295) | Mar 19, 2024 |
| HP            | 829E                        | Mini pc     | [37f9ae393e](https://linux-hardware.org/?probe=37f9ae393e) | Mar 18, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402NU... | Notebook    | [10d62d48f9](https://linux-hardware.org/?probe=10d62d48f9) | Mar 18, 2024 |
| MSI           | Modern 14 B4MW              | Notebook    | [c29ef44f2b](https://linux-hardware.org/?probe=c29ef44f2b) | Mar 18, 2024 |
| ASUSTek       | ROG GU501GM                 | Notebook    | [6a2786c694](https://linux-hardware.org/?probe=6a2786c694) | Mar 17, 2024 |
| Acer          | Predator PH16-71            | Notebook    | [e45e64cb9d](https://linux-hardware.org/?probe=e45e64cb9d) | Mar 16, 2024 |
| HP            | 18E5                        | Desktop     | [4ae7d1e99b](https://linux-hardware.org/?probe=4ae7d1e99b) | Mar 14, 2024 |
| HP            | 18E5                        | Desktop     | [0d777cf53f](https://linux-hardware.org/?probe=0d777cf53f) | Mar 14, 2024 |
| ASUSTek       | X450CA                      | Notebook    | [2c8ef0476a](https://linux-hardware.org/?probe=2c8ef0476a) | Mar 14, 2024 |
| MSI           | Modern 14 B4MW              | Notebook    | [66d5671a75](https://linux-hardware.org/?probe=66d5671a75) | Mar 10, 2024 |
| HP            | 3646h                       | Desktop     | [262b859dc2](https://linux-hardware.org/?probe=262b859dc2) | Mar 09, 2024 |
| HP            | ProBook 650 G1              | Notebook    | [994590f6a8](https://linux-hardware.org/?probe=994590f6a8) | Mar 06, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [9ac6447d8f](https://linux-hardware.org/?probe=9ac6447d8f) | Mar 06, 2024 |
| HP            | 3646h                       | Desktop     | [319c1272f7](https://linux-hardware.org/?probe=319c1272f7) | Mar 04, 2024 |
| HP            | 2AE5 A01                    | Desktop     | [60660db51f](https://linux-hardware.org/?probe=60660db51f) | Mar 03, 2024 |
| HP            | EliteBook 8570p             | Notebook    | [f91440705e](https://linux-hardware.org/?probe=f91440705e) | Mar 03, 2024 |
| HP            | 2AE5 A01                    | Desktop     | [4273399935](https://linux-hardware.org/?probe=4273399935) | Mar 02, 2024 |
| HP            | Pavilion 17                 | Notebook    | [9bc5ed54e4](https://linux-hardware.org/?probe=9bc5ed54e4) | Feb 27, 2024 |
| ASUSTek       | ROG GU501GM                 | Notebook    | [7ce7387f87](https://linux-hardware.org/?probe=7ce7387f87) | Feb 24, 2024 |
| Dell          | 042P49 A01                  | Desktop     | [3e64e4a44e](https://linux-hardware.org/?probe=3e64e4a44e) | Feb 22, 2024 |
| Unknown       | Unknown                     | Desktop     | [b9bba8bd7f](https://linux-hardware.org/?probe=b9bba8bd7f) | Feb 22, 2024 |
| ASUSTek       | X450CA                      | Notebook    | [cfcc5bb8ac](https://linux-hardware.org/?probe=cfcc5bb8ac) | Feb 19, 2024 |
| Apple         | MacBookPro16,3              | Notebook    | [c5da783ff8](https://linux-hardware.org/?probe=c5da783ff8) | Feb 19, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [c795e9fcb9](https://linux-hardware.org/?probe=c795e9fcb9) | Feb 16, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [8127c6afdc](https://linux-hardware.org/?probe=8127c6afdc) | Feb 15, 2024 |
| ASUSTek       | H81M-D                      | Desktop     | [9df4273ea0](https://linux-hardware.org/?probe=9df4273ea0) | Feb 14, 2024 |
| HP            | Compaq CQ45                 | Notebook    | [62b54ac7d5](https://linux-hardware.org/?probe=62b54ac7d5) | Feb 13, 2024 |
| HP            | Compaq CQ45                 | Notebook    | [8c87c5a050](https://linux-hardware.org/?probe=8c87c5a050) | Feb 13, 2024 |
| Dell          | Inspiron N4030              | Notebook    | [81753e03ae](https://linux-hardware.org/?probe=81753e03ae) | Feb 11, 2024 |
| Acer          | Aspire E5-476G              | Notebook    | [dbdd6adbd1](https://linux-hardware.org/?probe=dbdd6adbd1) | Feb 11, 2024 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [ece84ea9af](https://linux-hardware.org/?probe=ece84ea9af) | Feb 11, 2024 |
| ASUSTek       | X450CA                      | Notebook    | [9aeef6dd21](https://linux-hardware.org/?probe=9aeef6dd21) | Feb 11, 2024 |
| Acer          | Predator PH16-71            | Notebook    | [78c603a8f0](https://linux-hardware.org/?probe=78c603a8f0) | Feb 10, 2024 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [33127dc72f](https://linux-hardware.org/?probe=33127dc72f) | Feb 07, 2024 |
| ASUSTek       | X450CA                      | Notebook    | [701cfd5c41](https://linux-hardware.org/?probe=701cfd5c41) | Feb 02, 2024 |
| HP            | ProBook 4540s               | Notebook    | [ba6e31a8d3](https://linux-hardware.org/?probe=ba6e31a8d3) | Jan 29, 2024 |
| Valve         | Jupiter                     | Notebook    | [ad91e418c3](https://linux-hardware.org/?probe=ad91e418c3) | Jan 25, 2024 |
| Gigabyte      | H410M H V3                  | Desktop     | [0610c346d8](https://linux-hardware.org/?probe=0610c346d8) | Jan 25, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [00c6aa68c6](https://linux-hardware.org/?probe=00c6aa68c6) | Jan 22, 2024 |
| HP            | EliteBook x360 1030 G3      | Convertible | [2310e3c41a](https://linux-hardware.org/?probe=2310e3c41a) | Jan 20, 2024 |
| HP            | EliteBook x360 1030 G3      | Convertible | [27fae922ff](https://linux-hardware.org/?probe=27fae922ff) | Jan 20, 2024 |
| Dell          | 0G679R A00                  | Desktop     | [993e7a71b2](https://linux-hardware.org/?probe=993e7a71b2) | Jan 18, 2024 |
| Dell          | 0G679R A00                  | Desktop     | [31f196442f](https://linux-hardware.org/?probe=31f196442f) | Jan 18, 2024 |
| Gigabyte      | B450 AORUS M                | Desktop     | [06cced7a39](https://linux-hardware.org/?probe=06cced7a39) | Jan 18, 2024 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [4b0eb86898](https://linux-hardware.org/?probe=4b0eb86898) | Jan 15, 2024 |
| Acer          | Predator PH16-71            | Notebook    | [e2d230f52c](https://linux-hardware.org/?probe=e2d230f52c) | Jan 14, 2024 |
| MSI           | GT62VR 7RE                  | Notebook    | [11a6fc29dd](https://linux-hardware.org/?probe=11a6fc29dd) | Jan 14, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bddc683db5](https://linux-hardware.org/?probe=bddc683db5) | Jan 12, 2024 |
| Acer          | Swift SF314-54              | Notebook    | [c947abcab4](https://linux-hardware.org/?probe=c947abcab4) | Jan 11, 2024 |
| Acer          | Aspire V3-471G              | Notebook    | [d96fe50b0e](https://linux-hardware.org/?probe=d96fe50b0e) | Jan 07, 2024 |
| Lenovo        | ThinkPad X270 20HMS22H00    | Notebook    | [302c8659c3](https://linux-hardware.org/?probe=302c8659c3) | Jan 06, 2024 |
| Acer          | Aspire A315-51              | Notebook    | [753ed1e625](https://linux-hardware.org/?probe=753ed1e625) | Jan 05, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [b301f85af7](https://linux-hardware.org/?probe=b301f85af7) | Jan 04, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [cf07066830](https://linux-hardware.org/?probe=cf07066830) | Jan 03, 2024 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [00e99b0067](https://linux-hardware.org/?probe=00e99b0067) | Jan 02, 2024 |
| Acer          | Predator PH16-71            | Notebook    | [deae7730f2](https://linux-hardware.org/?probe=deae7730f2) | Dec 31, 2023 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [dc498a88a6](https://linux-hardware.org/?probe=dc498a88a6) | Dec 27, 2023 |
| Acer          | Predator PHN16-71           | Notebook    | [f7d4fcd885](https://linux-hardware.org/?probe=f7d4fcd885) | Dec 27, 2023 |
| Acer          | Predator PHN16-71           | Notebook    | [865ecc4a8b](https://linux-hardware.org/?probe=865ecc4a8b) | Dec 27, 2023 |
| Apple         | MacBookAir3,1               | Notebook    | [860a7b9b4c](https://linux-hardware.org/?probe=860a7b9b4c) | Dec 23, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [2fcf77279a](https://linux-hardware.org/?probe=2fcf77279a) | Dec 23, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [341417afe4](https://linux-hardware.org/?probe=341417afe4) | Dec 21, 2023 |
| Acer          | Predator PH16-71            | Notebook    | [403fcc076f](https://linux-hardware.org/?probe=403fcc076f) | Dec 21, 2023 |
| Lenovo        | ThinkPad X220 4286AQ7       | Notebook    | [ffea6e3dbe](https://linux-hardware.org/?probe=ffea6e3dbe) | Dec 17, 2023 |
| Lenovo        | ThinkPad X220 4286AQ7       | Notebook    | [a09d44706c](https://linux-hardware.org/?probe=a09d44706c) | Dec 17, 2023 |
| Acer          | Aspire A314-35              | Notebook    | [ece32548bb](https://linux-hardware.org/?probe=ece32548bb) | Dec 12, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [dfe75293a5](https://linux-hardware.org/?probe=dfe75293a5) | Dec 12, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [1eaf3dd454](https://linux-hardware.org/?probe=1eaf3dd454) | Dec 10, 2023 |
| Unknown       | Unknown                     | Notebook    | [130b4fa28a](https://linux-hardware.org/?probe=130b4fa28a) | Dec 09, 2023 |
| Acer          | Predator PH16-71            | Notebook    | [234562596d](https://linux-hardware.org/?probe=234562596d) | Dec 09, 2023 |
| MSI           | A520M PRO-VH                | Desktop     | [96475c0e77](https://linux-hardware.org/?probe=96475c0e77) | Dec 08, 2023 |
| Valve         | Jupiter                     | Notebook    | [326f2a7596](https://linux-hardware.org/?probe=326f2a7596) | Dec 08, 2023 |
| Google        | Chell                       | Notebook    | [b19b6452e3](https://linux-hardware.org/?probe=b19b6452e3) | Dec 07, 2023 |
| MSI           | CX62 7QL                    | Notebook    | [33cd9ad75d](https://linux-hardware.org/?probe=33cd9ad75d) | Dec 07, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | Desktop     | [0dade4f111](https://linux-hardware.org/?probe=0dade4f111) | Dec 06, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e90c011500](https://linux-hardware.org/?probe=e90c011500) | Dec 05, 2023 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [997c250e85](https://linux-hardware.org/?probe=997c250e85) | Dec 05, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [6f41c9ca50](https://linux-hardware.org/?probe=6f41c9ca50) | Dec 02, 2023 |
| Gigabyte      | H470 HD3                    | Desktop     | [0b9cf3a0a5](https://linux-hardware.org/?probe=0b9cf3a0a5) | Dec 02, 2023 |
| Acer          | Aspire E5-473               | Notebook    | [f3b2c01ef7](https://linux-hardware.org/?probe=f3b2c01ef7) | Dec 01, 2023 |
| Gigabyte      | H470 HD3                    | Desktop     | [0ecb969c2c](https://linux-hardware.org/?probe=0ecb969c2c) | Nov 28, 2023 |
| ASUSTek       | GL553VW                     | Notebook    | [dba63ed53c](https://linux-hardware.org/?probe=dba63ed53c) | Nov 26, 2023 |
| ASUSTek       | A55BM-E                     | Desktop     | [28fe1a1fe1](https://linux-hardware.org/?probe=28fe1a1fe1) | Nov 26, 2023 |
| HP            | 2AE5 A01                    | Desktop     | [d23f45244b](https://linux-hardware.org/?probe=d23f45244b) | Nov 25, 2023 |
| Gigabyte      | B550M AORUS ELITE AX        | Notebook    | [6ec8b667b0](https://linux-hardware.org/?probe=6ec8b667b0) | Nov 23, 2023 |
| Lenovo        | SHARKBAY 31900059 STD       | Desktop     | [bc11e1264c](https://linux-hardware.org/?probe=bc11e1264c) | Nov 22, 2023 |
| Gigabyte      | B550M AORUS ELITE AX        | Notebook    | [4e71e8e7b7](https://linux-hardware.org/?probe=4e71e8e7b7) | Nov 20, 2023 |
| HP            | 2AE5 A01                    | Desktop     | [90e640454c](https://linux-hardware.org/?probe=90e640454c) | Nov 18, 2023 |
| Lenovo        | SHARKBAY 31900059 STD       | Desktop     | [5368b237d8](https://linux-hardware.org/?probe=5368b237d8) | Nov 18, 2023 |
| Lenovo        | SHARKBAY 31900059 STD       | Desktop     | [7af93dbd28](https://linux-hardware.org/?probe=7af93dbd28) | Nov 17, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [a7467830d5](https://linux-hardware.org/?probe=a7467830d5) | Nov 17, 2023 |
| Acer          | TMP215-52-32DT              | Notebook    | [582fca0005](https://linux-hardware.org/?probe=582fca0005) | Nov 15, 2023 |
| Acer          | TMP215-52-32DT              | Notebook    | [1aec98605f](https://linux-hardware.org/?probe=1aec98605f) | Nov 15, 2023 |
| HP            | 2AE5 A01                    | Desktop     | [729cec323f](https://linux-hardware.org/?probe=729cec323f) | Nov 14, 2023 |
| HP            | 8054                        | Desktop     | [66fa2fd8c5](https://linux-hardware.org/?probe=66fa2fd8c5) | Nov 11, 2023 |
| HP            | 8054                        | Desktop     | [91d4d659b4](https://linux-hardware.org/?probe=91d4d659b4) | Nov 11, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [eb9b1302fd](https://linux-hardware.org/?probe=eb9b1302fd) | Nov 08, 2023 |
| Acer          | Predator PH16-71            | Notebook    | [5fcac9e7de](https://linux-hardware.org/?probe=5fcac9e7de) | Nov 08, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [b5e4afb8e9](https://linux-hardware.org/?probe=b5e4afb8e9) | Nov 06, 2023 |
| HP            | ProBook 4330s               | Notebook    | [046f30b044](https://linux-hardware.org/?probe=046f30b044) | Nov 03, 2023 |
| HP            | ProBook 4330s               | Notebook    | [0d3ba579b4](https://linux-hardware.org/?probe=0d3ba579b4) | Nov 02, 2023 |
| Lenovo        | ThinkPad T400 2768BB1       | Notebook    | [56bbf7c0bb](https://linux-hardware.org/?probe=56bbf7c0bb) | Nov 02, 2023 |
| Lenovo        | ThinkPad T400 2768BB1       | Notebook    | [249ea48334](https://linux-hardware.org/?probe=249ea48334) | Oct 30, 2023 |
| Valve         | Jupiter                     | Notebook    | [3e84a41deb](https://linux-hardware.org/?probe=3e84a41deb) | Oct 28, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [0656d1a0a8](https://linux-hardware.org/?probe=0656d1a0a8) | Oct 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [a524108535](https://linux-hardware.org/?probe=a524108535) | Oct 26, 2023 |
| ASRock        | B650M PG Riptide WiFi       | Desktop     | [387c91f530](https://linux-hardware.org/?probe=387c91f530) | Oct 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [ae2eee1640](https://linux-hardware.org/?probe=ae2eee1640) | Oct 26, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [851db330be](https://linux-hardware.org/?probe=851db330be) | Oct 24, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [d3e630e86d](https://linux-hardware.org/?probe=d3e630e86d) | Oct 23, 2023 |
| Unknown       | Unknown                     | Notebook    | [251baa33d7](https://linux-hardware.org/?probe=251baa33d7) | Oct 23, 2023 |
| Unknown       | Unknown                     | Notebook    | [a06cdb13fc](https://linux-hardware.org/?probe=a06cdb13fc) | Oct 23, 2023 |
| HP            | 805E                        | All in one  | [94013a53b7](https://linux-hardware.org/?probe=94013a53b7) | Oct 22, 2023 |
| Lenovo        | XiaoXin Air 15IKBR 81GY     | Notebook    | [755849af68](https://linux-hardware.org/?probe=755849af68) | Oct 20, 2023 |
| Biostar       | A320MH                      | Desktop     | [e2c20a6c0c](https://linux-hardware.org/?probe=e2c20a6c0c) | Oct 19, 2023 |
| Biostar       | A320MH                      | Desktop     | [62a3d049b2](https://linux-hardware.org/?probe=62a3d049b2) | Oct 18, 2023 |
| Acer          | Aspire A514-55              | Notebook    | [f25a7d5b9e](https://linux-hardware.org/?probe=f25a7d5b9e) | Oct 18, 2023 |
| Acer          | Veriton X2660G              | Desktop     | [d122988e18](https://linux-hardware.org/?probe=d122988e18) | Oct 17, 2023 |
| HP            | 805E                        | All in one  | [04d2314394](https://linux-hardware.org/?probe=04d2314394) | Oct 16, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [04d307e685](https://linux-hardware.org/?probe=04d307e685) | Oct 16, 2023 |
| Unknown       | Unknown                     | Notebook    | [6bb8ddbcda](https://linux-hardware.org/?probe=6bb8ddbcda) | Oct 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [5e866a9155](https://linux-hardware.org/?probe=5e866a9155) | Oct 10, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [80b914414e](https://linux-hardware.org/?probe=80b914414e) | Oct 07, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [d5f3037077](https://linux-hardware.org/?probe=d5f3037077) | Oct 05, 2023 |
| Lenovo        | ThinkPad T450 20BUA007SG    | Notebook    | [85af04a1cc](https://linux-hardware.org/?probe=85af04a1cc) | Oct 03, 2023 |
| Toshiba       | Satellite C55-C             | Notebook    | [e9ce3eada7](https://linux-hardware.org/?probe=e9ce3eada7) | Oct 02, 2023 |
| Acer          | Predator PH16-71            | Notebook    | [a07278dc43](https://linux-hardware.org/?probe=a07278dc43) | Oct 01, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [054707cbd2](https://linux-hardware.org/?probe=054707cbd2) | Sep 27, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [ecef286c2a](https://linux-hardware.org/?probe=ecef286c2a) | Sep 26, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [7c547aa37a](https://linux-hardware.org/?probe=7c547aa37a) | Sep 26, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [eef80142a9](https://linux-hardware.org/?probe=eef80142a9) | Sep 24, 2023 |
| ASUSTek       | X451MA                      | Notebook    | [ed779c5de4](https://linux-hardware.org/?probe=ed779c5de4) | Sep 20, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [bf29b07e79](https://linux-hardware.org/?probe=bf29b07e79) | Sep 19, 2023 |
| Acer          | Aspire A314-35              | Notebook    | [5f584efb57](https://linux-hardware.org/?probe=5f584efb57) | Sep 19, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [1259637f6b](https://linux-hardware.org/?probe=1259637f6b) | Sep 18, 2023 |
| Valve         | Jupiter                     | Notebook    | [2c3f76de4d](https://linux-hardware.org/?probe=2c3f76de4d) | Sep 18, 2023 |
| Lenovo        | ThinkPad X230 2325FG0       | Notebook    | [e60aae9a1b](https://linux-hardware.org/?probe=e60aae9a1b) | Sep 17, 2023 |
| Acer          | Aspire E5-473G              | Notebook    | [936a48fb5a](https://linux-hardware.org/?probe=936a48fb5a) | Sep 16, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [c0723e7eae](https://linux-hardware.org/?probe=c0723e7eae) | Sep 16, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [426914b6e5](https://linux-hardware.org/?probe=426914b6e5) | Sep 14, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [820a13876a](https://linux-hardware.org/?probe=820a13876a) | Sep 14, 2023 |
| Colorful T... | C.A68HM-K PLUS YV18         | Desktop     | [e4f73d159c](https://linux-hardware.org/?probe=e4f73d159c) | Sep 12, 2023 |
| Colorful T... | C.A68HM-K PLUS YV18         | Desktop     | [c57a3a012d](https://linux-hardware.org/?probe=c57a3a012d) | Sep 11, 2023 |
| Acer          | Predator PH16-71            | Notebook    | [f0b0cc7736](https://linux-hardware.org/?probe=f0b0cc7736) | Sep 09, 2023 |
| Dell          | Precision M6800             | Notebook    | [b50e95f460](https://linux-hardware.org/?probe=b50e95f460) | Sep 07, 2023 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [06a65572fe](https://linux-hardware.org/?probe=06a65572fe) | Sep 05, 2023 |
| MSI           | PRO B760M-G DDR4            | Desktop     | [a8f42a3c96](https://linux-hardware.org/?probe=a8f42a3c96) | Sep 05, 2023 |
| HP            | 8158 A01                    | Mini pc     | [de8c371188](https://linux-hardware.org/?probe=de8c371188) | Sep 04, 2023 |
| Dell          | 0G679R A00                  | Desktop     | [30755bff92](https://linux-hardware.org/?probe=30755bff92) | Sep 03, 2023 |
| Intel         | H81                         | Desktop     | [75aabbccf5](https://linux-hardware.org/?probe=75aabbccf5) | Sep 03, 2023 |
| AMI           | Intel                       | Convertible | [dd24abacfc](https://linux-hardware.org/?probe=dd24abacfc) | Sep 02, 2023 |
| Dell          | 0G679R A00                  | Desktop     | [cc4b4ad10d](https://linux-hardware.org/?probe=cc4b4ad10d) | Sep 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [af78cafb1a](https://linux-hardware.org/?probe=af78cafb1a) | Sep 01, 2023 |
| HP            | Laptop 14-bs1xx             | Notebook    | [335b828114](https://linux-hardware.org/?probe=335b828114) | Aug 31, 2023 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [a75e60a457](https://linux-hardware.org/?probe=a75e60a457) | Aug 30, 2023 |
| ASUSTek       | K55VD                       | Notebook    | [7bdfc94045](https://linux-hardware.org/?probe=7bdfc94045) | Aug 27, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [4ea7c3580b](https://linux-hardware.org/?probe=4ea7c3580b) | Aug 26, 2023 |
| Acer          | Predator PH16-71            | Notebook    | [ef267bc627](https://linux-hardware.org/?probe=ef267bc627) | Aug 26, 2023 |
| Lenovo        | Legion Y9000P IAH7H 82RF    | Notebook    | [f429d18938](https://linux-hardware.org/?probe=f429d18938) | Aug 23, 2023 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [d23fefd908](https://linux-hardware.org/?probe=d23fefd908) | Aug 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [692495c520](https://linux-hardware.org/?probe=692495c520) | Aug 20, 2023 |
| ASUSTek       | X510UQ                      | Notebook    | [169472a4fa](https://linux-hardware.org/?probe=169472a4fa) | Aug 19, 2023 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [0a747fe196](https://linux-hardware.org/?probe=0a747fe196) | Aug 19, 2023 |
| Acer          | Aspire 7560G                | Notebook    | [a4a5ddf1b0](https://linux-hardware.org/?probe=a4a5ddf1b0) | Aug 13, 2023 |
| MSI           | GT62VR 7RE                  | Notebook    | [105839bee0](https://linux-hardware.org/?probe=105839bee0) | Aug 13, 2023 |
| Valve         | Jupiter                     | Notebook    | [c34cb54bc8](https://linux-hardware.org/?probe=c34cb54bc8) | Aug 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [22fc28c382](https://linux-hardware.org/?probe=22fc28c382) | Aug 11, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [1a3b5297dd](https://linux-hardware.org/?probe=1a3b5297dd) | Aug 08, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [18208500ee](https://linux-hardware.org/?probe=18208500ee) | Aug 08, 2023 |
| EMAXX TECH... | EMX-B450M-GAMING            | Desktop     | [3f5c0e83d4](https://linux-hardware.org/?probe=3f5c0e83d4) | Aug 06, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [286cc8b0dd](https://linux-hardware.org/?probe=286cc8b0dd) | Aug 04, 2023 |
| Acer          | Aspire V3-371               | Notebook    | [5d5a4b489b](https://linux-hardware.org/?probe=5d5a4b489b) | Aug 03, 2023 |
| ASUSTek       | K55VD                       | Notebook    | [6478fd4e76](https://linux-hardware.org/?probe=6478fd4e76) | Aug 03, 2023 |
| Dell          | Vostro 5515                 | Notebook    | [0e031a4729](https://linux-hardware.org/?probe=0e031a4729) | Aug 02, 2023 |
| Samsung       | 535U3C                      | Notebook    | [8d0ebb957a](https://linux-hardware.org/?probe=8d0ebb957a) | Jul 31, 2023 |
| Samsung       | 535U3C                      | Notebook    | [030fc15fac](https://linux-hardware.org/?probe=030fc15fac) | Jul 31, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [42ca7b346e](https://linux-hardware.org/?probe=42ca7b346e) | Jul 29, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [fdcac9e445](https://linux-hardware.org/?probe=fdcac9e445) | Jul 29, 2023 |
| MSI           | A320M PRO-VH                | Desktop     | [0728a96775](https://linux-hardware.org/?probe=0728a96775) | Jul 29, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [bf3f7b4c2d](https://linux-hardware.org/?probe=bf3f7b4c2d) | Jul 27, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [ba305b3271](https://linux-hardware.org/?probe=ba305b3271) | Jul 26, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [00e9bb8973](https://linux-hardware.org/?probe=00e9bb8973) | Jul 26, 2023 |
| Gigabyte      | B360M HD3                   | Desktop     | [900f299e10](https://linux-hardware.org/?probe=900f299e10) | Jul 26, 2023 |
| Samsung       | DeskTop System              | Desktop     | [c1d4c8efb2](https://linux-hardware.org/?probe=c1d4c8efb2) | Jul 24, 2023 |
| Dell          | Latitude E6330              | Notebook    | [32dbf41885](https://linux-hardware.org/?probe=32dbf41885) | Jul 24, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [fdbe29a1db](https://linux-hardware.org/?probe=fdbe29a1db) | Jul 22, 2023 |
| Unknown       | Unknown                     | Notebook    | [516853cca9](https://linux-hardware.org/?probe=516853cca9) | Jul 21, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [d1dee26c33](https://linux-hardware.org/?probe=d1dee26c33) | Jul 20, 2023 |
| Samsung       | DeskTop System              | Desktop     | [715ff16efc](https://linux-hardware.org/?probe=715ff16efc) | Jul 17, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [4d00148664](https://linux-hardware.org/?probe=4d00148664) | Jul 16, 2023 |
| ASUSTek       | P8Z77-V LX2                 | Desktop     | [eedcf805f7](https://linux-hardware.org/?probe=eedcf805f7) | Jul 14, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [75d40e5a2b](https://linux-hardware.org/?probe=75d40e5a2b) | Jul 14, 2023 |
| ASUSTek       | X756UXK                     | Notebook    | [746e141543](https://linux-hardware.org/?probe=746e141543) | Jul 10, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [59f06e2baf](https://linux-hardware.org/?probe=59f06e2baf) | Jul 09, 2023 |
| Dell          | Latitude E5470              | Notebook    | [ac0f0dd893](https://linux-hardware.org/?probe=ac0f0dd893) | Jul 08, 2023 |
| MSI           | Modern 14 B4MW              | Notebook    | [210a7aea7f](https://linux-hardware.org/?probe=210a7aea7f) | Jul 05, 2023 |
| ASUSTek       | X455LJ                      | Notebook    | [60c1acd1fc](https://linux-hardware.org/?probe=60c1acd1fc) | Jul 04, 2023 |
| GPD           | G1618-03                    | Desktop     | [0cb58087bf](https://linux-hardware.org/?probe=0cb58087bf) | Jul 04, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [fc70411ea4](https://linux-hardware.org/?probe=fc70411ea4) | Jul 03, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [ec4bf131f5](https://linux-hardware.org/?probe=ec4bf131f5) | Jun 30, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [a5dd94faa7](https://linux-hardware.org/?probe=a5dd94faa7) | Jun 28, 2023 |
| ASUSTek       | X455LJ                      | Notebook    | [c147d5716d](https://linux-hardware.org/?probe=c147d5716d) | Jun 27, 2023 |
| ASUSTek       | H110M-D                     | Desktop     | [f95d5e83f5](https://linux-hardware.org/?probe=f95d5e83f5) | Jun 25, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [9408842ffc](https://linux-hardware.org/?probe=9408842ffc) | Jun 24, 2023 |
| Dell          | Vostro 5515                 | Notebook    | [350e1d5a7b](https://linux-hardware.org/?probe=350e1d5a7b) | Jun 23, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [d5c387d28e](https://linux-hardware.org/?probe=d5c387d28e) | Jun 18, 2023 |
| Biostar       | B450MH                      | Desktop     | [04c924ce6f](https://linux-hardware.org/?probe=04c924ce6f) | Jun 16, 2023 |
| Lenovo        | 315F SDK0J40697 WIN 3305... | Desktop     | [dac73c9b94](https://linux-hardware.org/?probe=dac73c9b94) | Jun 16, 2023 |
| MSI           | GL62M 7RDX                  | Notebook    | [d1fb646d9a](https://linux-hardware.org/?probe=d1fb646d9a) | Jun 11, 2023 |
| HP            | 1496                        | Desktop     | [7189030996](https://linux-hardware.org/?probe=7189030996) | Jun 11, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7c9662b5eb](https://linux-hardware.org/?probe=7c9662b5eb) | Jun 10, 2023 |
| HP            | 1496                        | Desktop     | [68db57fde8](https://linux-hardware.org/?probe=68db57fde8) | Jun 10, 2023 |
| Lenovo        | ThinkPad L430 24655Q7       | Notebook    | [7b45c0777e](https://linux-hardware.org/?probe=7b45c0777e) | Jun 08, 2023 |
| Lenovo        | ThinkPad T460 20FMS2292K    | Notebook    | [380ffe6574](https://linux-hardware.org/?probe=380ffe6574) | Jun 06, 2023 |
| AMD           | A88                         | Desktop     | [a7f64b7e4b](https://linux-hardware.org/?probe=a7f64b7e4b) | Jun 05, 2023 |
| Dell          | Inspiron 7472               | Notebook    | [53b9d0dfa6](https://linux-hardware.org/?probe=53b9d0dfa6) | Jun 03, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [44571410f0](https://linux-hardware.org/?probe=44571410f0) | Jun 03, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [d54d77b051](https://linux-hardware.org/?probe=d54d77b051) | Jun 03, 2023 |
| Lenovo        | ThinkPad X230 2325SLU       | Notebook    | [3a1d630346](https://linux-hardware.org/?probe=3a1d630346) | Jun 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [49135876a9](https://linux-hardware.org/?probe=49135876a9) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [1334997a22](https://linux-hardware.org/?probe=1334997a22) | Jun 01, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [f688bc50e0](https://linux-hardware.org/?probe=f688bc50e0) | Jun 01, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ebd7782079](https://linux-hardware.org/?probe=ebd7782079) | May 31, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [953ee1ef05](https://linux-hardware.org/?probe=953ee1ef05) | May 31, 2023 |
| Biostar       | B450MH                      | Desktop     | [36947ca7e1](https://linux-hardware.org/?probe=36947ca7e1) | May 30, 2023 |
| Pegatron      | NARRA3                      | Desktop     | [5c016d4faf](https://linux-hardware.org/?probe=5c016d4faf) | May 28, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [7884ad9bf4](https://linux-hardware.org/?probe=7884ad9bf4) | May 25, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [b291f783a2](https://linux-hardware.org/?probe=b291f783a2) | May 25, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [76bd19169a](https://linux-hardware.org/?probe=76bd19169a) | May 22, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [f511a54601](https://linux-hardware.org/?probe=f511a54601) | May 21, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [e4b87f1e56](https://linux-hardware.org/?probe=e4b87f1e56) | May 19, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [c9d2b44907](https://linux-hardware.org/?probe=c9d2b44907) | May 17, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [53a5e2e7d7](https://linux-hardware.org/?probe=53a5e2e7d7) | May 16, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [a7c2953571](https://linux-hardware.org/?probe=a7c2953571) | May 15, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [274fbdb43e](https://linux-hardware.org/?probe=274fbdb43e) | May 14, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [80158c51fb](https://linux-hardware.org/?probe=80158c51fb) | May 12, 2023 |
| Acer          | Aspire E5-521G              | Notebook    | [9ddcbd7a95](https://linux-hardware.org/?probe=9ddcbd7a95) | May 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [cf4ff7fcb1](https://linux-hardware.org/?probe=cf4ff7fcb1) | Apr 29, 2023 |
| ECS           | G41T-R3                     | Desktop     | [fcbdd2737a](https://linux-hardware.org/?probe=fcbdd2737a) | Apr 26, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [96f6b41a5c](https://linux-hardware.org/?probe=96f6b41a5c) | Apr 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6ce11cef12](https://linux-hardware.org/?probe=6ce11cef12) | Apr 18, 2023 |
| HP            | Laptop 14-bs1xx             | Notebook    | [1bc4428cb1](https://linux-hardware.org/?probe=1bc4428cb1) | Apr 17, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [c5c1b213f2](https://linux-hardware.org/?probe=c5c1b213f2) | Apr 16, 2023 |
| ECS           | G41T-R3                     | Desktop     | [2c589a38f7](https://linux-hardware.org/?probe=2c589a38f7) | Apr 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [0120f0db62](https://linux-hardware.org/?probe=0120f0db62) | Apr 12, 2023 |
| HP            | Pavilion (EH737UA#ABA)      | Notebook    | [cc8ff92529](https://linux-hardware.org/?probe=cc8ff92529) | Apr 11, 2023 |
| Dell          | Inspiron 5584               | Notebook    | [5ca9178d00](https://linux-hardware.org/?probe=5ca9178d00) | Apr 09, 2023 |
| Dell          | Inspiron 1720               | Notebook    | [93e9be5f34](https://linux-hardware.org/?probe=93e9be5f34) | Apr 09, 2023 |
| Xunlong       | Orange Pi One               | Soc         | [8d982c6cd9](https://linux-hardware.org/?probe=8d982c6cd9) | Apr 01, 2023 |
| HP            | 3397                        | Desktop     | [5a25984320](https://linux-hardware.org/?probe=5a25984320) | Mar 31, 2023 |
| ASRock        | H61M-HVS                    | Desktop     | [0672578da7](https://linux-hardware.org/?probe=0672578da7) | Mar 30, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [628d2ea05c](https://linux-hardware.org/?probe=628d2ea05c) | Mar 24, 2023 |
| MSI           | Modern 14 B4MW              | Notebook    | [c81d9f3b07](https://linux-hardware.org/?probe=c81d9f3b07) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [4eb8132fd2](https://linux-hardware.org/?probe=4eb8132fd2) | Mar 24, 2023 |
| EMAXX TECH... | EMX-B450M-GAMING            | Desktop     | [f147ee8484](https://linux-hardware.org/?probe=f147ee8484) | Mar 21, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [ae258d05b1](https://linux-hardware.org/?probe=ae258d05b1) | Mar 16, 2023 |
| Jumper        | EZbook                      | Notebook    | [a6114c514f](https://linux-hardware.org/?probe=a6114c514f) | Mar 13, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [26ecc0b7a2](https://linux-hardware.org/?probe=26ecc0b7a2) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [87eec74772](https://linux-hardware.org/?probe=87eec74772) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [38599c9b97](https://linux-hardware.org/?probe=38599c9b97) | Mar 10, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [a3d866a82b](https://linux-hardware.org/?probe=a3d866a82b) | Mar 09, 2023 |
| Toshiba       | Satellite L855              | Notebook    | [3832889508](https://linux-hardware.org/?probe=3832889508) | Mar 09, 2023 |
| ASUSTek       | X556UQ                      | Notebook    | [c124d02c5b](https://linux-hardware.org/?probe=c124d02c5b) | Mar 09, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [8c709c4723](https://linux-hardware.org/?probe=8c709c4723) | Mar 07, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [4a698cb3eb](https://linux-hardware.org/?probe=4a698cb3eb) | Mar 07, 2023 |
| Acer          | Aspire A514-55              | Notebook    | [97e8238d87](https://linux-hardware.org/?probe=97e8238d87) | Mar 05, 2023 |
| Acer          | Aspire A314-35              | Notebook    | [3e4fdfbb73](https://linux-hardware.org/?probe=3e4fdfbb73) | Mar 05, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [ada5bd893b](https://linux-hardware.org/?probe=ada5bd893b) | Mar 04, 2023 |
| Lenovo        | ThinkPad X230 23255SM       | Notebook    | [2f5cd26eae](https://linux-hardware.org/?probe=2f5cd26eae) | Mar 04, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [ce3d086582](https://linux-hardware.org/?probe=ce3d086582) | Mar 04, 2023 |
| HP            | ENVY Sleekbook 4            | Notebook    | [d771874d8b](https://linux-hardware.org/?probe=d771874d8b) | Mar 03, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [25d1509478](https://linux-hardware.org/?probe=25d1509478) | Mar 03, 2023 |
| Acer          | Aspire A314-35              | Notebook    | [587096ec48](https://linux-hardware.org/?probe=587096ec48) | Mar 03, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [ca7d449be6](https://linux-hardware.org/?probe=ca7d449be6) | Feb 28, 2023 |
| MSI           | A320M PRO-VH                | Desktop     | [e1266ebf79](https://linux-hardware.org/?probe=e1266ebf79) | Feb 27, 2023 |
| ASUSTek       | A68HM-K                     | Desktop     | [d6f5b00609](https://linux-hardware.org/?probe=d6f5b00609) | Feb 26, 2023 |
| ASUSTek       | A68HM-K                     | Desktop     | [89cd5d5c44](https://linux-hardware.org/?probe=89cd5d5c44) | Feb 26, 2023 |
| Acer          | TravelMate P633-V           | Notebook    | [b4841d9589](https://linux-hardware.org/?probe=b4841d9589) | Feb 26, 2023 |
| Acer          | TravelMate P633-V           | Notebook    | [fd426b6c71](https://linux-hardware.org/?probe=fd426b6c71) | Feb 25, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO II     | Desktop     | [99b1ae3224](https://linux-hardware.org/?probe=99b1ae3224) | Feb 25, 2023 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [e88df81d6f](https://linux-hardware.org/?probe=e88df81d6f) | Feb 24, 2023 |
| NEC Comput... | PC-VY25AAZR7                | Notebook    | [bc17a98c15](https://linux-hardware.org/?probe=bc17a98c15) | Feb 24, 2023 |
| Biostar       | A320MH                      | Desktop     | [b6f7ef6e4a](https://linux-hardware.org/?probe=b6f7ef6e4a) | Feb 23, 2023 |
| Biostar       | A320MH                      | Desktop     | [e80f86a0bf](https://linux-hardware.org/?probe=e80f86a0bf) | Feb 23, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [9caa421a49](https://linux-hardware.org/?probe=9caa421a49) | Feb 19, 2023 |
| Dell          | Latitude E4200              | Notebook    | [18868db8a1](https://linux-hardware.org/?probe=18868db8a1) | Feb 17, 2023 |
| Dell          | 0W2F8G A00                  | Desktop     | [aa7bf98168](https://linux-hardware.org/?probe=aa7bf98168) | Feb 16, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [eb8434e607](https://linux-hardware.org/?probe=eb8434e607) | Feb 15, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [22b77a1f78](https://linux-hardware.org/?probe=22b77a1f78) | Feb 13, 2023 |
| Acer          | Aspire A314-35              | Notebook    | [0a6d50bc2a](https://linux-hardware.org/?probe=0a6d50bc2a) | Feb 13, 2023 |
| Acer          | Aspire A314-35              | Notebook    | [75980f2f55](https://linux-hardware.org/?probe=75980f2f55) | Feb 13, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [24c1c37b05](https://linux-hardware.org/?probe=24c1c37b05) | Feb 13, 2023 |
| ASUSTek       | BM6630_BM6330_BP6230        | Desktop     | [abe1e578c0](https://linux-hardware.org/?probe=abe1e578c0) | Feb 12, 2023 |
| Lenovo        | ThinkPad T450 20BV0001US    | Notebook    | [d149fd1ed6](https://linux-hardware.org/?probe=d149fd1ed6) | Feb 12, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [94c0fadd44](https://linux-hardware.org/?probe=94c0fadd44) | Feb 10, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [e3bbec75c5](https://linux-hardware.org/?probe=e3bbec75c5) | Feb 10, 2023 |
| Lenovo        | ThinkPad E490 20N9S2AS00    | Notebook    | [5d2f191a6f](https://linux-hardware.org/?probe=5d2f191a6f) | Feb 09, 2023 |
| Lenovo        | ThinkPad E490 20N9S2AS00    | Notebook    | [668b9a0bfe](https://linux-hardware.org/?probe=668b9a0bfe) | Feb 09, 2023 |
| Valve         | Jupiter                     | Notebook    | [f7f1655bc2](https://linux-hardware.org/?probe=f7f1655bc2) | Feb 08, 2023 |
| Valve         | Jupiter                     | Notebook    | [df167dd152](https://linux-hardware.org/?probe=df167dd152) | Feb 08, 2023 |
| Unknown       | Unknown                     | Notebook    | [83e2eaf929](https://linux-hardware.org/?probe=83e2eaf929) | Feb 07, 2023 |
| Dell          | 0W2F8G A00                  | Desktop     | [b0694cfc5c](https://linux-hardware.org/?probe=b0694cfc5c) | Feb 06, 2023 |
| Acer          | Aspire V3-574G              | Notebook    | [5ce729f67f](https://linux-hardware.org/?probe=5ce729f67f) | Feb 04, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [4029c64aec](https://linux-hardware.org/?probe=4029c64aec) | Feb 02, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [71bfc02926](https://linux-hardware.org/?probe=71bfc02926) | Feb 01, 2023 |
| Gigabyte      | H97M-D3H                    | Desktop     | [3ccdc4fa2b](https://linux-hardware.org/?probe=3ccdc4fa2b) | Jan 31, 2023 |
| Dell          | Inspiron 13-5368            | Notebook    | [4e74651840](https://linux-hardware.org/?probe=4e74651840) | Jan 20, 2023 |
| Unknown       | X133                        | Notebook    | [ad31153d58](https://linux-hardware.org/?probe=ad31153d58) | Jan 20, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [907784afb2](https://linux-hardware.org/?probe=907784afb2) | Jan 12, 2023 |
| MSI           | Modern 14 B4MW              | Notebook    | [815ee96451](https://linux-hardware.org/?probe=815ee96451) | Jan 11, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [cb037b984e](https://linux-hardware.org/?probe=cb037b984e) | Jan 10, 2023 |
| Acer          | Aspire 4738                 | Notebook    | [62914eb5f1](https://linux-hardware.org/?probe=62914eb5f1) | Jan 09, 2023 |
| MSI           | MAG B560M MORTAR WIFI       | Desktop     | [33f6781ba8](https://linux-hardware.org/?probe=33f6781ba8) | Jan 08, 2023 |
| Dell          | Inspiron 14-3462            | Notebook    | [99d81ca38e](https://linux-hardware.org/?probe=99d81ca38e) | Jan 06, 2023 |
| Dell          | Inspiron 14-3462            | Notebook    | [582d8bfa18](https://linux-hardware.org/?probe=582d8bfa18) | Jan 06, 2023 |
| MSI           | Modern 14 B4MW              | Notebook    | [b7855a84cf](https://linux-hardware.org/?probe=b7855a84cf) | Jan 05, 2023 |
| Acer          | Aspire A515-57T             | Notebook    | [bc905f86da](https://linux-hardware.org/?probe=bc905f86da) | Jan 02, 2023 |
| Dell          | Inspiron 14-3462            | Notebook    | [1a8ed5998a](https://linux-hardware.org/?probe=1a8ed5998a) | Dec 30, 2022 |
| HP            | 431 Notebook                | Notebook    | [6a8d323e0c](https://linux-hardware.org/?probe=6a8d323e0c) | Dec 30, 2022 |
| Lenovo        | IdeaPad 320-14IAP 80XQ      | Notebook    | [e133481ab3](https://linux-hardware.org/?probe=e133481ab3) | Dec 29, 2022 |
| Dell          | Inspiron 5505               | Notebook    | [ba2d75cfa7](https://linux-hardware.org/?probe=ba2d75cfa7) | Dec 28, 2022 |
| Acer          | Aspire 4738                 | Notebook    | [ffbbc9ecb5](https://linux-hardware.org/?probe=ffbbc9ecb5) | Dec 26, 2022 |
| Acer          | Aspire 4738                 | Notebook    | [f5277ba6a0](https://linux-hardware.org/?probe=f5277ba6a0) | Dec 26, 2022 |
| Dell          | Inspiron 14-3462            | Notebook    | [f95fd7ca72](https://linux-hardware.org/?probe=f95fd7ca72) | Dec 25, 2022 |
| Dell          | Inspiron 14-3462            | Notebook    | [7b38daddb5](https://linux-hardware.org/?probe=7b38daddb5) | Dec 25, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [e9dbd838ec](https://linux-hardware.org/?probe=e9dbd838ec) | Dec 25, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [64cd4afc6d](https://linux-hardware.org/?probe=64cd4afc6d) | Dec 21, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [cfeb9545a3](https://linux-hardware.org/?probe=cfeb9545a3) | Dec 21, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [2d446beedf](https://linux-hardware.org/?probe=2d446beedf) | Dec 21, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [06d690e9fe](https://linux-hardware.org/?probe=06d690e9fe) | Dec 15, 2022 |
| ALLDOCUBE     | i1405C                      | Notebook    | [10d8101488](https://linux-hardware.org/?probe=10d8101488) | Dec 15, 2022 |
| Unknown       | NVIDIA Jetson Xavier NX ... | Soc         | [b05faac149](https://linux-hardware.org/?probe=b05faac149) | Dec 15, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [fe7f585504](https://linux-hardware.org/?probe=fe7f585504) | Dec 14, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [63cbf5d0e9](https://linux-hardware.org/?probe=63cbf5d0e9) | Dec 13, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [8489ca12d8](https://linux-hardware.org/?probe=8489ca12d8) | Dec 13, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [3c5a5379a4](https://linux-hardware.org/?probe=3c5a5379a4) | Dec 13, 2022 |
| Biostar       | A520MH                      | Desktop     | [b6c4fdd80b](https://linux-hardware.org/?probe=b6c4fdd80b) | Dec 11, 2022 |
| Lenovo        | G470 20078                  | Notebook    | [65264ef208](https://linux-hardware.org/?probe=65264ef208) | Dec 11, 2022 |
| ASUSTek       | BM5242                      | Desktop     | [d37b75dc52](https://linux-hardware.org/?probe=d37b75dc52) | Dec 10, 2022 |
| ASUSTek       | BM5242                      | Desktop     | [7c17c8d773](https://linux-hardware.org/?probe=7c17c8d773) | Dec 10, 2022 |
| Lenovo        | G470 20078                  | Notebook    | [ea75ebf831](https://linux-hardware.org/?probe=ea75ebf831) | Dec 09, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [03c0b9e50d](https://linux-hardware.org/?probe=03c0b9e50d) | Dec 05, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [6890b98eeb](https://linux-hardware.org/?probe=6890b98eeb) | Dec 03, 2022 |
| HP            | Laptop 15-da3xxx            | Notebook    | [335fce26dd](https://linux-hardware.org/?probe=335fce26dd) | Nov 26, 2022 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [913b35d3f0](https://linux-hardware.org/?probe=913b35d3f0) | Nov 25, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [f0bebe7a20](https://linux-hardware.org/?probe=f0bebe7a20) | Nov 24, 2022 |
| Intel         | D946GZAB AAD66610-302       | Desktop     | [5433ee5bc1](https://linux-hardware.org/?probe=5433ee5bc1) | Nov 22, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [4792cdbba2](https://linux-hardware.org/?probe=4792cdbba2) | Nov 21, 2022 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | Notebook    | [09285b9428](https://linux-hardware.org/?probe=09285b9428) | Nov 13, 2022 |
| MSI           | B450M BAZOOKA PLUS          | Desktop     | [f63b2757ea](https://linux-hardware.org/?probe=f63b2757ea) | Nov 12, 2022 |
| Unknown       | X133                        | Notebook    | [f89481552e](https://linux-hardware.org/?probe=f89481552e) | Nov 11, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [70daf967f2](https://linux-hardware.org/?probe=70daf967f2) | Nov 10, 2022 |
| Lenovo        | ThinkPad E14 20RA004VPH     | Notebook    | [abbb784ea9](https://linux-hardware.org/?probe=abbb784ea9) | Nov 09, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [5384de4df1](https://linux-hardware.org/?probe=5384de4df1) | Nov 09, 2022 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [c08b835f58](https://linux-hardware.org/?probe=c08b835f58) | Nov 07, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [7db5fcb7b0](https://linux-hardware.org/?probe=7db5fcb7b0) | Nov 05, 2022 |
| Lenovo        | ThinkPad E14 20RA004VPH     | Notebook    | [fbe5c4578c](https://linux-hardware.org/?probe=fbe5c4578c) | Nov 04, 2022 |
| HP            | EliteBook 745 G2            | Notebook    | [6eca80dabf](https://linux-hardware.org/?probe=6eca80dabf) | Nov 04, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [28cc86118e](https://linux-hardware.org/?probe=28cc86118e) | Nov 03, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [e4dfd41fa4](https://linux-hardware.org/?probe=e4dfd41fa4) | Nov 02, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [452ec1a1ee](https://linux-hardware.org/?probe=452ec1a1ee) | Nov 02, 2022 |
| Dell          | Vostro 5515                 | Notebook    | [881cd60670](https://linux-hardware.org/?probe=881cd60670) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [4fdbc3c415](https://linux-hardware.org/?probe=4fdbc3c415) | Oct 30, 2022 |
| HP            | 3048h                       | Desktop     | [6ce1d2bf43](https://linux-hardware.org/?probe=6ce1d2bf43) | Oct 30, 2022 |
| ASRock        | H61M-VS                     | Desktop     | [9a48b2a679](https://linux-hardware.org/?probe=9a48b2a679) | Oct 28, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [e9ce57f1c1](https://linux-hardware.org/?probe=e9ce57f1c1) | Oct 25, 2022 |
| MSI           | MAG A520M VECTOR WIFI       | Desktop     | [91a8a52c4a](https://linux-hardware.org/?probe=91a8a52c4a) | Oct 25, 2022 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [dd5c78f136](https://linux-hardware.org/?probe=dd5c78f136) | Oct 24, 2022 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [10d8d16b6c](https://linux-hardware.org/?probe=10d8d16b6c) | Oct 24, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [f91daeac73](https://linux-hardware.org/?probe=f91daeac73) | Oct 19, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [d267c64062](https://linux-hardware.org/?probe=d267c64062) | Oct 19, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [e5a34da4a2](https://linux-hardware.org/?probe=e5a34da4a2) | Oct 19, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [fc0a9a6b24](https://linux-hardware.org/?probe=fc0a9a6b24) | Oct 18, 2022 |
| MSI           | H110M PRO-D                 | Desktop     | [d0580b46f2](https://linux-hardware.org/?probe=d0580b46f2) | Oct 18, 2022 |
| HP            | 431 Notebook                | Notebook    | [fd2980af46](https://linux-hardware.org/?probe=fd2980af46) | Oct 16, 2022 |
| Lenovo        | ThinkPad E14 20RA004VPH     | Notebook    | [23adba19e0](https://linux-hardware.org/?probe=23adba19e0) | Oct 15, 2022 |
| Lenovo        | ThinkPad X230 2325CF6       | Notebook    | [622d37f892](https://linux-hardware.org/?probe=622d37f892) | Oct 15, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [fbb018d1ef](https://linux-hardware.org/?probe=fbb018d1ef) | Oct 14, 2022 |
| Acer          | Swift SF314-57              | Notebook    | [a1b02901a1](https://linux-hardware.org/?probe=a1b02901a1) | Oct 13, 2022 |
| Acer          | Swift SF314-57              | Notebook    | [a0f4cd454d](https://linux-hardware.org/?probe=a0f4cd454d) | Oct 13, 2022 |
| Acer          | Swift SF314-57              | Notebook    | [5eafc7c12c](https://linux-hardware.org/?probe=5eafc7c12c) | Oct 13, 2022 |
| HP            | Laptop 14s-dk1xxx           | Notebook    | [1eb06e8e12](https://linux-hardware.org/?probe=1eb06e8e12) | Oct 12, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [0355b3f7b8](https://linux-hardware.org/?probe=0355b3f7b8) | Oct 11, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [9f52e46640](https://linux-hardware.org/?probe=9f52e46640) | Oct 11, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [aa7d067a6f](https://linux-hardware.org/?probe=aa7d067a6f) | Oct 11, 2022 |
| Toshiba       | TECRA Z50-C                 | Notebook    | [fc6e63a30a](https://linux-hardware.org/?probe=fc6e63a30a) | Oct 11, 2022 |
| HP            | ENVY Sleekbook 4            | Notebook    | [c14c5b1ee3](https://linux-hardware.org/?probe=c14c5b1ee3) | Oct 10, 2022 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [379f85dfb3](https://linux-hardware.org/?probe=379f85dfb3) | Oct 09, 2022 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [f02be8db4c](https://linux-hardware.org/?probe=f02be8db4c) | Oct 09, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2e020fe882](https://linux-hardware.org/?probe=2e020fe882) | Oct 07, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [ddb0e3fb81](https://linux-hardware.org/?probe=ddb0e3fb81) | Oct 05, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [700c5cc2bc](https://linux-hardware.org/?probe=700c5cc2bc) | Oct 05, 2022 |
| HP            | ENVY Sleekbook 4            | Notebook    | [0b820a1c7e](https://linux-hardware.org/?probe=0b820a1c7e) | Oct 04, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [4ba3e28201](https://linux-hardware.org/?probe=4ba3e28201) | Oct 04, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3595e90895](https://linux-hardware.org/?probe=3595e90895) | Oct 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [29648b493a](https://linux-hardware.org/?probe=29648b493a) | Oct 01, 2022 |
| Dell          | Latitude 5490               | Notebook    | [4c59654ea9](https://linux-hardware.org/?probe=4c59654ea9) | Sep 29, 2022 |
| Acer          | Aspire E3-111               | Notebook    | [6646e09597](https://linux-hardware.org/?probe=6646e09597) | Sep 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [27d8d35004](https://linux-hardware.org/?probe=27d8d35004) | Sep 25, 2022 |
| Acer          | AOD257                      | Notebook    | [35ca1c0b33](https://linux-hardware.org/?probe=35ca1c0b33) | Sep 24, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [6c34753f58](https://linux-hardware.org/?probe=6c34753f58) | Sep 22, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [37dbdb48dd](https://linux-hardware.org/?probe=37dbdb48dd) | Sep 20, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1ad10d3c4b](https://linux-hardware.org/?probe=1ad10d3c4b) | Sep 18, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [4d460404c8](https://linux-hardware.org/?probe=4d460404c8) | Sep 16, 2022 |
| Google        | Treeya                      | Notebook    | [a2723e9afa](https://linux-hardware.org/?probe=a2723e9afa) | Sep 15, 2022 |
| Google        | Treeya                      | Notebook    | [0553290711](https://linux-hardware.org/?probe=0553290711) | Sep 14, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [4b5a146dc9](https://linux-hardware.org/?probe=4b5a146dc9) | Sep 13, 2022 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | Desktop     | [34c1beb103](https://linux-hardware.org/?probe=34c1beb103) | Sep 13, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [7ce5d8e865](https://linux-hardware.org/?probe=7ce5d8e865) | Sep 12, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [ec5f57ab65](https://linux-hardware.org/?probe=ec5f57ab65) | Sep 12, 2022 |
| Biostar       | A780L3B                     | Desktop     | [bc83f32ddf](https://linux-hardware.org/?probe=bc83f32ddf) | Sep 12, 2022 |
| Biostar       | A780L3B                     | Desktop     | [61057dc040](https://linux-hardware.org/?probe=61057dc040) | Sep 12, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1ecadc5740](https://linux-hardware.org/?probe=1ecadc5740) | Sep 11, 2022 |
| ASUSTek       | X441NA                      | Notebook    | [40f5cb1550](https://linux-hardware.org/?probe=40f5cb1550) | Sep 10, 2022 |
| Google        | Treeya                      | Notebook    | [d7a00caa63](https://linux-hardware.org/?probe=d7a00caa63) | Sep 10, 2022 |
| Biostar       | A780L3B                     | Desktop     | [6463bcc136](https://linux-hardware.org/?probe=6463bcc136) | Sep 10, 2022 |
| Biostar       | A780L3B                     | Desktop     | [f65db263d7](https://linux-hardware.org/?probe=f65db263d7) | Sep 10, 2022 |
| Acer          | Aspire A314-22G             | Notebook    | [b6f9c0a0e7](https://linux-hardware.org/?probe=b6f9c0a0e7) | Sep 10, 2022 |
| Gigabyte      | GA-990FXA-UD5               | Desktop     | [b77aa249c8](https://linux-hardware.org/?probe=b77aa249c8) | Sep 09, 2022 |
| Gigabyte      | GA-990FXA-UD5               | Desktop     | [dc69b9dde6](https://linux-hardware.org/?probe=dc69b9dde6) | Sep 09, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | Desktop     | [051ea3b002](https://linux-hardware.org/?probe=051ea3b002) | Sep 08, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [af2641c077](https://linux-hardware.org/?probe=af2641c077) | Sep 07, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [85d4f11486](https://linux-hardware.org/?probe=85d4f11486) | Sep 01, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [7d69c012fb](https://linux-hardware.org/?probe=7d69c012fb) | Aug 28, 2022 |
| Dell          | Inspiron 5577               | Notebook    | [b40621d5f6](https://linux-hardware.org/?probe=b40621d5f6) | Aug 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1c75cbf917](https://linux-hardware.org/?probe=1c75cbf917) | Aug 27, 2022 |
| HP            | 83F3                        | Desktop     | [71d62174e2](https://linux-hardware.org/?probe=71d62174e2) | Aug 27, 2022 |
| HP            | 1850                        | Desktop     | [85b5eedc40](https://linux-hardware.org/?probe=85b5eedc40) | Aug 26, 2022 |
| Dell          | Inspiron 7472               | Notebook    | [d9ff6dc8b4](https://linux-hardware.org/?probe=d9ff6dc8b4) | Aug 25, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [65b569c23c](https://linux-hardware.org/?probe=65b569c23c) | Aug 23, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [bfdd1ab294](https://linux-hardware.org/?probe=bfdd1ab294) | Aug 23, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [390e67b458](https://linux-hardware.org/?probe=390e67b458) | Aug 21, 2022 |
| realme        | RMNBXXXX                    | Notebook    | [d98be8821f](https://linux-hardware.org/?probe=d98be8821f) | Aug 20, 2022 |
| HP            | Laptop 14-bs1xx             | Notebook    | [4b603b6b08](https://linux-hardware.org/?probe=4b603b6b08) | Aug 15, 2022 |
| ASUSTek       | K56CB                       | Notebook    | [0ec4449fe2](https://linux-hardware.org/?probe=0ec4449fe2) | Aug 09, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [49ab4e0197](https://linux-hardware.org/?probe=49ab4e0197) | Aug 08, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [7a37d5e6a5](https://linux-hardware.org/?probe=7a37d5e6a5) | Aug 07, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [db237c843c](https://linux-hardware.org/?probe=db237c843c) | Aug 06, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [5251e7868a](https://linux-hardware.org/?probe=5251e7868a) | Aug 06, 2022 |
| Dell          | Precision 3510              | Notebook    | [2d74356174](https://linux-hardware.org/?probe=2d74356174) | Aug 03, 2022 |
| Dell          | Precision 3510              | Notebook    | [d2e79b01bb](https://linux-hardware.org/?probe=d2e79b01bb) | Aug 02, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [93ae3bfcfd](https://linux-hardware.org/?probe=93ae3bfcfd) | Aug 02, 2022 |
| Gigabyte      | H81M-D2V                    | Desktop     | [64da165357](https://linux-hardware.org/?probe=64da165357) | Aug 01, 2022 |
| Lenovo        | ThinkPad E590 20NB0032CD    | Notebook    | [502b0eeb39](https://linux-hardware.org/?probe=502b0eeb39) | Aug 01, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [0f38b878b5](https://linux-hardware.org/?probe=0f38b878b5) | Jul 31, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [8a472804e4](https://linux-hardware.org/?probe=8a472804e4) | Jul 30, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | Notebook    | [9c0b784d1d](https://linux-hardware.org/?probe=9c0b784d1d) | Jul 27, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [a0e19ce405](https://linux-hardware.org/?probe=a0e19ce405) | Jul 26, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [437ba53b68](https://linux-hardware.org/?probe=437ba53b68) | Jul 25, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [f47a0ecbf5](https://linux-hardware.org/?probe=f47a0ecbf5) | Jul 25, 2022 |
| MSI           | CX62 6QD                    | Notebook    | [d0c23fefca](https://linux-hardware.org/?probe=d0c23fefca) | Jul 24, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [d404840b57](https://linux-hardware.org/?probe=d404840b57) | Jul 24, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [37521f84c8](https://linux-hardware.org/?probe=37521f84c8) | Jul 20, 2022 |
| ASUSTek       | M4A88T-M                    | Desktop     | [57ed9f00c7](https://linux-hardware.org/?probe=57ed9f00c7) | Jul 18, 2022 |
| ASUSTek       | M4A88T-M                    | Desktop     | [f99189e2d0](https://linux-hardware.org/?probe=f99189e2d0) | Jul 18, 2022 |
| Unknown       | Unknown                     | Notebook    | [251f348fe5](https://linux-hardware.org/?probe=251f348fe5) | Jul 17, 2022 |
| Dell          | Vostro 3700                 | Notebook    | [2b7a37d662](https://linux-hardware.org/?probe=2b7a37d662) | Jul 16, 2022 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | Notebook    | [24c803a5fc](https://linux-hardware.org/?probe=24c803a5fc) | Jul 15, 2022 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [c1ed74053e](https://linux-hardware.org/?probe=c1ed74053e) | Jul 11, 2022 |
| YANYU         | EPIC-C19                    | Desktop     | [5bda78db57](https://linux-hardware.org/?probe=5bda78db57) | Jul 11, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [b6a7451086](https://linux-hardware.org/?probe=b6a7451086) | Jul 11, 2022 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | Notebook    | [b9c939b2e2](https://linux-hardware.org/?probe=b9c939b2e2) | Jul 09, 2022 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | Notebook    | [88cc242e02](https://linux-hardware.org/?probe=88cc242e02) | Jul 09, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [264b084b00](https://linux-hardware.org/?probe=264b084b00) | Jul 08, 2022 |
| Acer          | Aspire E5-473G              | Notebook    | [11b488a036](https://linux-hardware.org/?probe=11b488a036) | Jul 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [c9d2a76068](https://linux-hardware.org/?probe=c9d2a76068) | Jul 03, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [b7fedc25e4](https://linux-hardware.org/?probe=b7fedc25e4) | Jul 01, 2022 |
| Gigabyte      | A520M DS3H                  | Desktop     | [b56fe3beb3](https://linux-hardware.org/?probe=b56fe3beb3) | Jun 28, 2022 |
| Lenovo        | IdeaPad 320-14AST 80XU      | Notebook    | [78eaeff700](https://linux-hardware.org/?probe=78eaeff700) | Jun 27, 2022 |
| Acer          | Predator PH315-53           | Notebook    | [c23e943030](https://linux-hardware.org/?probe=c23e943030) | Jun 21, 2022 |
| MSI           | A320M PRO-VH                | Desktop     | [47f765c61f](https://linux-hardware.org/?probe=47f765c61f) | Jun 14, 2022 |
| MSI           | H81M-E33                    | Desktop     | [49191a1c98](https://linux-hardware.org/?probe=49191a1c98) | Jun 08, 2022 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [017e41e32c](https://linux-hardware.org/?probe=017e41e32c) | Jun 07, 2022 |
| MSI           | H81M-E33                    | Desktop     | [6a2d6cbe74](https://linux-hardware.org/?probe=6a2d6cbe74) | Jun 04, 2022 |
| Dell          | Inspiron 3531               | Notebook    | [c2d9f4b84b](https://linux-hardware.org/?probe=c2d9f4b84b) | Jun 02, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [512fb81a9b](https://linux-hardware.org/?probe=512fb81a9b) | May 31, 2022 |
| MSI           | Z97 XPOWER AC               | Desktop     | [dd5c7a981a](https://linux-hardware.org/?probe=dd5c7a981a) | May 29, 2022 |
| MSI           | MS-7717                     | Desktop     | [101b488b80](https://linux-hardware.org/?probe=101b488b80) | May 28, 2022 |
| MSI           | MS-7717                     | Desktop     | [9b0c2d0d8c](https://linux-hardware.org/?probe=9b0c2d0d8c) | May 28, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [0656adeb11](https://linux-hardware.org/?probe=0656adeb11) | May 24, 2022 |
| Dell          | Vostro 5515                 | Notebook    | [b884e51280](https://linux-hardware.org/?probe=b884e51280) | May 21, 2022 |
| ASUSTek       | TUF Gaming FX705DU_FX705... | Notebook    | [a3e1bf045d](https://linux-hardware.org/?probe=a3e1bf045d) | May 20, 2022 |
| ASUSTek       | ROG Strix G731GT_G731GT     | Notebook    | [5c20c841d1](https://linux-hardware.org/?probe=5c20c841d1) | May 18, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [0571b7cb83](https://linux-hardware.org/?probe=0571b7cb83) | May 18, 2022 |
| Acer          | TravelMate P249-G2-MG       | Notebook    | [e6f35b116a](https://linux-hardware.org/?probe=e6f35b116a) | May 15, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [debbc95647](https://linux-hardware.org/?probe=debbc95647) | May 12, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [915b95cae4](https://linux-hardware.org/?probe=915b95cae4) | May 11, 2022 |
| Unknown       | Unknown                     | Notebook    | [fac14402be](https://linux-hardware.org/?probe=fac14402be) | May 11, 2022 |
| Acer          | Aspire E5-576G              | Notebook    | [27f577ec86](https://linux-hardware.org/?probe=27f577ec86) | May 10, 2022 |
| ECS           | A68M-C4DL                   | Desktop     | [b8c60cf7a0](https://linux-hardware.org/?probe=b8c60cf7a0) | May 09, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [5b877349c1](https://linux-hardware.org/?probe=5b877349c1) | May 09, 2022 |
| HP            | 212A                        | Desktop     | [acd660910f](https://linux-hardware.org/?probe=acd660910f) | May 09, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [07ed7fd709](https://linux-hardware.org/?probe=07ed7fd709) | May 08, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [443d537d91](https://linux-hardware.org/?probe=443d537d91) | May 05, 2022 |
| Apple         | MacBookAir5,1               | Notebook    | [45c12c8fc4](https://linux-hardware.org/?probe=45c12c8fc4) | Apr 30, 2022 |
| Acer          | TravelMate P249-G2-MG       | Notebook    | [2e0bd790c6](https://linux-hardware.org/?probe=2e0bd790c6) | Apr 26, 2022 |
| Acer          | Aspire E5-551G              | Notebook    | [8dd5e105d1](https://linux-hardware.org/?probe=8dd5e105d1) | Apr 21, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [74323309f1](https://linux-hardware.org/?probe=74323309f1) | Apr 20, 2022 |
| Toshiba       | TECRA R940                  | Notebook    | [e7dc07a41c](https://linux-hardware.org/?probe=e7dc07a41c) | Apr 20, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [1f3827f38e](https://linux-hardware.org/?probe=1f3827f38e) | Apr 18, 2022 |
| Unknown       | Unknown                     | Notebook    | [cfd3bd53a8](https://linux-hardware.org/?probe=cfd3bd53a8) | Apr 18, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [b824b88050](https://linux-hardware.org/?probe=b824b88050) | Apr 15, 2022 |
| Toshiba       | Satellite E45t-A            | Notebook    | [3698a21b91](https://linux-hardware.org/?probe=3698a21b91) | Apr 15, 2022 |
| Toshiba       | dynabook B45/A              | Notebook    | [f430a05b2d](https://linux-hardware.org/?probe=f430a05b2d) | Apr 09, 2022 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [5a576e8488](https://linux-hardware.org/?probe=5a576e8488) | Apr 01, 2022 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [83800436e5](https://linux-hardware.org/?probe=83800436e5) | Mar 31, 2022 |
| Shenzhen B... | NBPC1078                    | Tablet      | [33e297566b](https://linux-hardware.org/?probe=33e297566b) | Mar 30, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [03b7f74d31](https://linux-hardware.org/?probe=03b7f74d31) | Mar 29, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [42e921877b](https://linux-hardware.org/?probe=42e921877b) | Mar 29, 2022 |
| HP            | 2B38                        | Desktop     | [99fd9bb200](https://linux-hardware.org/?probe=99fd9bb200) | Mar 27, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [8dbd85ced8](https://linux-hardware.org/?probe=8dbd85ced8) | Mar 25, 2022 |
| MSI           | MS-7619                     | Desktop     | [65c73f26b0](https://linux-hardware.org/?probe=65c73f26b0) | Mar 22, 2022 |
| MSI           | H510M PRO-E                 | Desktop     | [111cf21b7f](https://linux-hardware.org/?probe=111cf21b7f) | Mar 21, 2022 |
| ASUSTek       | ROG STRIX Z490-I GAMING     | Desktop     | [95373e24b7](https://linux-hardware.org/?probe=95373e24b7) | Mar 16, 2022 |
| MSI           | B560M PRO-VDH WIFI          | Desktop     | [c15007b668](https://linux-hardware.org/?probe=c15007b668) | Mar 15, 2022 |
| MSI           | H510M PRO-E                 | Desktop     | [ad5840ceb1](https://linux-hardware.org/?probe=ad5840ceb1) | Mar 14, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [1a9459872a](https://linux-hardware.org/?probe=1a9459872a) | Mar 13, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [bd9b6ec157](https://linux-hardware.org/?probe=bd9b6ec157) | Mar 11, 2022 |
| Lenovo        | ThinkPad E480 20KN002YPH    | Notebook    | [2f136d5bf5](https://linux-hardware.org/?probe=2f136d5bf5) | Mar 11, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [946300c067](https://linux-hardware.org/?probe=946300c067) | Mar 10, 2022 |
| Dell          | 0K9T56 A00                  | All in one  | [503d10d676](https://linux-hardware.org/?probe=503d10d676) | Mar 09, 2022 |
| Unknown       | Unknown                     | Notebook    | [23c7cd9c12](https://linux-hardware.org/?probe=23c7cd9c12) | Mar 09, 2022 |
| Dell          | 0K9T56 A00                  | All in one  | [206a6faf1c](https://linux-hardware.org/?probe=206a6faf1c) | Mar 09, 2022 |
| Unknown       | Unknown                     | Notebook    | [dc2ae12852](https://linux-hardware.org/?probe=dc2ae12852) | Mar 07, 2022 |
| Unknown       | Unknown                     | Notebook    | [1b5e705cf1](https://linux-hardware.org/?probe=1b5e705cf1) | Mar 07, 2022 |
| Lenovo        | ThinkPad Edge 0578BBA       | Notebook    | [cf314fb57a](https://linux-hardware.org/?probe=cf314fb57a) | Mar 07, 2022 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [a1b757e234](https://linux-hardware.org/?probe=a1b757e234) | Mar 05, 2022 |
| ASUSTek       | H81M-D                      | Desktop     | [4f6714e804](https://linux-hardware.org/?probe=4f6714e804) | Mar 01, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [809dad2888](https://linux-hardware.org/?probe=809dad2888) | Mar 01, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [70f59ecacf](https://linux-hardware.org/?probe=70f59ecacf) | Feb 28, 2022 |
| ASUSTek       | H81M-D                      | Desktop     | [2bc13ee0e2](https://linux-hardware.org/?probe=2bc13ee0e2) | Feb 28, 2022 |
| ASUSTek       | H81M-D                      | Desktop     | [a8334fb3c3](https://linux-hardware.org/?probe=a8334fb3c3) | Feb 28, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [02ea37a7a8](https://linux-hardware.org/?probe=02ea37a7a8) | Feb 28, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [f269ebd3a2](https://linux-hardware.org/?probe=f269ebd3a2) | Feb 28, 2022 |
| Acer          | AOD270                      | Notebook    | [491fbe6832](https://linux-hardware.org/?probe=491fbe6832) | Feb 21, 2022 |
| Acer          | AOD270                      | Notebook    | [90f9f56240](https://linux-hardware.org/?probe=90f9f56240) | Feb 21, 2022 |
| ASUSTek       | 900                         | Notebook    | [8373f78d4e](https://linux-hardware.org/?probe=8373f78d4e) | Feb 19, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [1e700d65ea](https://linux-hardware.org/?probe=1e700d65ea) | Feb 17, 2022 |
| ASUSTek       | A88XM-PLUS                  | Desktop     | [3a6147e5db](https://linux-hardware.org/?probe=3a6147e5db) | Feb 16, 2022 |
| HP            | Unknown                     | Notebook    | [2f4edd8b04](https://linux-hardware.org/?probe=2f4edd8b04) | Feb 13, 2022 |
| HP            | Unknown                     | Notebook    | [1284e8c58f](https://linux-hardware.org/?probe=1284e8c58f) | Feb 13, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [a25fea3795](https://linux-hardware.org/?probe=a25fea3795) | Feb 12, 2022 |
| Lenovo        | ThinkPad X220 4290MN4       | Notebook    | [c0c3368738](https://linux-hardware.org/?probe=c0c3368738) | Feb 08, 2022 |
| Acer          | Aspire V5-471               | Notebook    | [9bbd70f06c](https://linux-hardware.org/?probe=9bbd70f06c) | Feb 06, 2022 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [da8ce5d5b5](https://linux-hardware.org/?probe=da8ce5d5b5) | Feb 05, 2022 |
| Lenovo        | ThinkPad E480 20KN002YPH    | Notebook    | [c8f0deedbc](https://linux-hardware.org/?probe=c8f0deedbc) | Feb 03, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [ca4c953595](https://linux-hardware.org/?probe=ca4c953595) | Jan 27, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [e01afda31f](https://linux-hardware.org/?probe=e01afda31f) | Jan 22, 2022 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [56bbe3562f](https://linux-hardware.org/?probe=56bbe3562f) | Jan 15, 2022 |
| HP            | Notebook                    | Notebook    | [826345f64e](https://linux-hardware.org/?probe=826345f64e) | Jan 13, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [b04287afb1](https://linux-hardware.org/?probe=b04287afb1) | Jan 11, 2022 |
| Acer          | Aspire A315-41G             | Notebook    | [647b2f2da2](https://linux-hardware.org/?probe=647b2f2da2) | Jan 06, 2022 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [266128f234](https://linux-hardware.org/?probe=266128f234) | Jan 06, 2022 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [900b250e00](https://linux-hardware.org/?probe=900b250e00) | Jan 05, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [d770cc3fe5](https://linux-hardware.org/?probe=d770cc3fe5) | Jan 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | Notebook    | [0cf6f2102c](https://linux-hardware.org/?probe=0cf6f2102c) | Jan 03, 2022 |
| Dell          | Inspiron 5555               | Notebook    | [5f4e7a5f4b](https://linux-hardware.org/?probe=5f4e7a5f4b) | Dec 28, 2021 |
| HP            | Pavilion tx1000             | Notebook    | [a3639ffcd5](https://linux-hardware.org/?probe=a3639ffcd5) | Dec 21, 2021 |
| Unknown       | Unknown                     | Notebook    | [a1b24f9ab7](https://linux-hardware.org/?probe=a1b24f9ab7) | Dec 21, 2021 |
| Unknown       | Unknown                     | Notebook    | [0fb793d2a7](https://linux-hardware.org/?probe=0fb793d2a7) | Dec 21, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [e0b5bc37a4](https://linux-hardware.org/?probe=e0b5bc37a4) | Dec 18, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [60daadb8b0](https://linux-hardware.org/?probe=60daadb8b0) | Dec 18, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [448cdcb300](https://linux-hardware.org/?probe=448cdcb300) | Dec 17, 2021 |
| HP            | Pavilion tx1000             | Notebook    | [e568b07f70](https://linux-hardware.org/?probe=e568b07f70) | Dec 14, 2021 |
| EMAXX TECH... | EMX-A55GT-iCafe V1.0        | Desktop     | [d6d799c3d8](https://linux-hardware.org/?probe=d6d799c3d8) | Nov 28, 2021 |
| Dell          | MXG061                      | Notebook    | [72d7e58977](https://linux-hardware.org/?probe=72d7e58977) | Nov 28, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [31e306a09d](https://linux-hardware.org/?probe=31e306a09d) | Nov 26, 2021 |
| Sony          | SVT13115FGS                 | Notebook    | [a5821de326](https://linux-hardware.org/?probe=a5821de326) | Nov 22, 2021 |
| HP            | ProBook 4730s               | Notebook    | [ffaa64e329](https://linux-hardware.org/?probe=ffaa64e329) | Nov 19, 2021 |
| Acer          | TravelMate P249-G2-M        | Notebook    | [7dbc9e305c](https://linux-hardware.org/?probe=7dbc9e305c) | Nov 11, 2021 |
| Toshiba       | NB255                       | Notebook    | [3c30b0d7ad](https://linux-hardware.org/?probe=3c30b0d7ad) | Nov 09, 2021 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [bfd4d51591](https://linux-hardware.org/?probe=bfd4d51591) | Nov 09, 2021 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [2302fee654](https://linux-hardware.org/?probe=2302fee654) | Nov 09, 2021 |
| MSI           | Z97 GAMING 3                | Desktop     | [249f25308e](https://linux-hardware.org/?probe=249f25308e) | Nov 08, 2021 |
| MSI           | B350M PRO-VDH               | Desktop     | [7e77378fb3](https://linux-hardware.org/?probe=7e77378fb3) | Nov 07, 2021 |
| HP            | Unknown                     | Notebook    | [4ce778dffc](https://linux-hardware.org/?probe=4ce778dffc) | Nov 06, 2021 |
| HP            | Unknown                     | Notebook    | [285c5d9c85](https://linux-hardware.org/?probe=285c5d9c85) | Nov 06, 2021 |
| Acer          | Aspire E5-411               | Notebook    | [0155c64e23](https://linux-hardware.org/?probe=0155c64e23) | Nov 04, 2021 |
| PERSONA       | MYBOOK 14                   | Notebook    | [bf2929c7e3](https://linux-hardware.org/?probe=bf2929c7e3) | Nov 03, 2021 |
| Acer          | Aspire E5-411               | Notebook    | [63287ab4e6](https://linux-hardware.org/?probe=63287ab4e6) | Nov 02, 2021 |
| ECS           | G41T-R3                     | Desktop     | [892069341e](https://linux-hardware.org/?probe=892069341e) | Oct 31, 2021 |
| ASUSTek       | F2A85-M LE                  | Desktop     | [0ac8e061f1](https://linux-hardware.org/?probe=0ac8e061f1) | Oct 31, 2021 |
| ASUSTek       | F2A85-M LE                  | Desktop     | [655000678d](https://linux-hardware.org/?probe=655000678d) | Oct 30, 2021 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [fd3aefd54a](https://linux-hardware.org/?probe=fd3aefd54a) | Oct 27, 2021 |
| Dell          | Vostro 1400                 | Notebook    | [ba2e7123ba](https://linux-hardware.org/?probe=ba2e7123ba) | Oct 24, 2021 |
| Jumper        | EZbook                      | Notebook    | [557738cd7d](https://linux-hardware.org/?probe=557738cd7d) | Oct 23, 2021 |
| HASEE Comp... | HNX4S                       | Notebook    | [aba8e89b9a](https://linux-hardware.org/?probe=aba8e89b9a) | Oct 17, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [ec3329e68a](https://linux-hardware.org/?probe=ec3329e68a) | Oct 17, 2021 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [b8292ace4e](https://linux-hardware.org/?probe=b8292ace4e) | Oct 14, 2021 |
| EMAXX TECH... | EMX-MCP61D3-iCafe V2.0      | Desktop     | [cb279cfeaf](https://linux-hardware.org/?probe=cb279cfeaf) | Oct 09, 2021 |
| EMAXX TECH... | EMX-MCP61D3-iCafe V2.0      | Desktop     | [2444a742a8](https://linux-hardware.org/?probe=2444a742a8) | Oct 09, 2021 |
| HP            | Unknown                     | Notebook    | [c65be179d9](https://linux-hardware.org/?probe=c65be179d9) | Oct 08, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e584636758](https://linux-hardware.org/?probe=e584636758) | Oct 04, 2021 |
| HP            | 14                          | Notebook    | [71ed61e3e0](https://linux-hardware.org/?probe=71ed61e3e0) | Oct 02, 2021 |
| HP            | 14                          | Notebook    | [8fc4fceaa1](https://linux-hardware.org/?probe=8fc4fceaa1) | Oct 02, 2021 |
| HP            | EliteBook 745 G2            | Notebook    | [d80eb2d42c](https://linux-hardware.org/?probe=d80eb2d42c) | Sep 30, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [6e927dafdd](https://linux-hardware.org/?probe=6e927dafdd) | Sep 28, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [ccccaee5bb](https://linux-hardware.org/?probe=ccccaee5bb) | Sep 28, 2021 |
| ASUSTek       | GD30CI                      | Desktop     | [9782c6bff5](https://linux-hardware.org/?probe=9782c6bff5) | Sep 25, 2021 |
| ASUSTek       | EX-H310M-V3 R2.0            | Desktop     | [a9a92c303c](https://linux-hardware.org/?probe=a9a92c303c) | Sep 24, 2021 |
| HP            | G60                         | Notebook    | [36ad0dc4bc](https://linux-hardware.org/?probe=36ad0dc4bc) | Sep 22, 2021 |
| HP            | Unknown                     | Notebook    | [b0b3846ace](https://linux-hardware.org/?probe=b0b3846ace) | Sep 17, 2021 |
| JOOYON        | IPM41-D3G                   | Desktop     | [54cc0ff25b](https://linux-hardware.org/?probe=54cc0ff25b) | Sep 17, 2021 |
| ASUSTek       | X510UQ                      | Notebook    | [ffeab1f23c](https://linux-hardware.org/?probe=ffeab1f23c) | Sep 16, 2021 |
| Toshiba       | Satellite P845              | Notebook    | [27d8557047](https://linux-hardware.org/?probe=27d8557047) | Sep 12, 2021 |
| JOOYON        | IPM41-D3G                   | Desktop     | [4f8d90f8ef](https://linux-hardware.org/?probe=4f8d90f8ef) | Sep 12, 2021 |
| Toshiba       | Satellite C55D-B            | Notebook    | [e9f2b0ceda](https://linux-hardware.org/?probe=e9f2b0ceda) | Sep 11, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [9b620ade68](https://linux-hardware.org/?probe=9b620ade68) | Sep 08, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS            | Desktop     | [f6388fb1b0](https://linux-hardware.org/?probe=f6388fb1b0) | Sep 07, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS            | Desktop     | [a19fc44e26](https://linux-hardware.org/?probe=a19fc44e26) | Sep 07, 2021 |
| Dell          | Latitude E7450              | Notebook    | [531e888c8b](https://linux-hardware.org/?probe=531e888c8b) | Sep 04, 2021 |
| Lenovo        | ThinkPad X220 42863MJ       | Notebook    | [68cbfb3edb](https://linux-hardware.org/?probe=68cbfb3edb) | Sep 04, 2021 |
| Cubix         | Morph                       | Notebook    | [ffc9d93c9b](https://linux-hardware.org/?probe=ffc9d93c9b) | Aug 30, 2021 |
| Gigabyte      | F2A58M-DS2                  | Desktop     | [8ea19cfa9d](https://linux-hardware.org/?probe=8ea19cfa9d) | Aug 25, 2021 |
| Gigabyte      | Q2006                       | Notebook    | [754a3fc1b5](https://linux-hardware.org/?probe=754a3fc1b5) | Aug 23, 2021 |
| Gigabyte      | Q2006                       | Notebook    | [a384b10b00](https://linux-hardware.org/?probe=a384b10b00) | Aug 23, 2021 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [54f7c9deec](https://linux-hardware.org/?probe=54f7c9deec) | Aug 14, 2021 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [07f3a8a2c9](https://linux-hardware.org/?probe=07f3a8a2c9) | Aug 13, 2021 |
| Acer          | Aspire V3-772G              | Notebook    | [58d92680bb](https://linux-hardware.org/?probe=58d92680bb) | Aug 13, 2021 |
| Unknown       | Ionics Carrier Board Adv... | Desktop     | [62a47a18c2](https://linux-hardware.org/?probe=62a47a18c2) | Aug 12, 2021 |
| Apple         | MacBookAir4,1               | Notebook    | [cc00e74712](https://linux-hardware.org/?probe=cc00e74712) | Aug 09, 2021 |
| ECS           | H81H3-M4                    | Desktop     | [a595ba80d3](https://linux-hardware.org/?probe=a595ba80d3) | Aug 08, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [90e7e1e008](https://linux-hardware.org/?probe=90e7e1e008) | Aug 05, 2021 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [4bf2729f88](https://linux-hardware.org/?probe=4bf2729f88) | Aug 04, 2021 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [57f0c24236](https://linux-hardware.org/?probe=57f0c24236) | Aug 03, 2021 |
| Toshiba       | Satellite C650              | Notebook    | [3b5f090e84](https://linux-hardware.org/?probe=3b5f090e84) | Aug 01, 2021 |
| Gigabyte      | MZGLKCP-00                  | Desktop     | [4d9f134679](https://linux-hardware.org/?probe=4d9f134679) | Jul 30, 2021 |
| Biostar       | H110MHV3                    | Desktop     | [28344398db](https://linux-hardware.org/?probe=28344398db) | Jul 27, 2021 |
| Acer          | Aspire E3-111               | Notebook    | [29d6febd6e](https://linux-hardware.org/?probe=29d6febd6e) | Jul 24, 2021 |
| Acer          | Aspire E3-111               | Notebook    | [f9c8b1d3ff](https://linux-hardware.org/?probe=f9c8b1d3ff) | Jul 24, 2021 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [9576a81942](https://linux-hardware.org/?probe=9576a81942) | Jul 23, 2021 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [d86a6d7c9a](https://linux-hardware.org/?probe=d86a6d7c9a) | Jul 23, 2021 |
| Acer          | Aspire E5-551G              | Notebook    | [519515ce84](https://linux-hardware.org/?probe=519515ce84) | Jul 15, 2021 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [a5daecad1d](https://linux-hardware.org/?probe=a5daecad1d) | Jul 15, 2021 |
| Dell          | Inspiron 7373               | Convertible | [5514ed070a](https://linux-hardware.org/?probe=5514ed070a) | Jul 14, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [2151a0b75d](https://linux-hardware.org/?probe=2151a0b75d) | Jul 13, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [8165fc4d95](https://linux-hardware.org/?probe=8165fc4d95) | Jul 06, 2021 |
| Lenovo        | ThinkPad X220 4291LL6       | Notebook    | [3e8ed9be02](https://linux-hardware.org/?probe=3e8ed9be02) | Jul 02, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [ceedeef480](https://linux-hardware.org/?probe=ceedeef480) | Jul 01, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [63055a9c60](https://linux-hardware.org/?probe=63055a9c60) | Jun 29, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [5e0e7e2b80](https://linux-hardware.org/?probe=5e0e7e2b80) | Jun 25, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [00ef418c43](https://linux-hardware.org/?probe=00ef418c43) | Jun 24, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [ca6df82553](https://linux-hardware.org/?probe=ca6df82553) | Jun 22, 2021 |
| Biostar       | A320MH                      | Desktop     | [16e2552ccc](https://linux-hardware.org/?probe=16e2552ccc) | Jun 20, 2021 |
| Lenovo        | ThinkPad X220 4291LR8       | Notebook    | [69031eda12](https://linux-hardware.org/?probe=69031eda12) | Jun 18, 2021 |
| Lenovo        | ThinkPad X220 4291LR8       | Notebook    | [d7b3c8fc20](https://linux-hardware.org/?probe=d7b3c8fc20) | Jun 18, 2021 |
| Lenovo        | ThinkPad L530 24811K2       | Notebook    | [3517541065](https://linux-hardware.org/?probe=3517541065) | Jun 11, 2021 |
| Dell          | 040DDP A01                  | Desktop     | [8a9bdad1fd](https://linux-hardware.org/?probe=8a9bdad1fd) | Jun 10, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [cc3c9e3798](https://linux-hardware.org/?probe=cc3c9e3798) | Jun 08, 2021 |
| MSI           | A68HM-E33 V2                | Desktop     | [10ccc894a1](https://linux-hardware.org/?probe=10ccc894a1) | Jun 07, 2021 |
| Toshiba       | Satellite L515              | Notebook    | [72858b36e6](https://linux-hardware.org/?probe=72858b36e6) | Jun 02, 2021 |
| HP            | 82A5                        | Mini pc     | [08b98b6a88](https://linux-hardware.org/?probe=08b98b6a88) | May 29, 2021 |
| NEC Comput... | PC-VK25MXZCB                | Notebook    | [0a1b7b959f](https://linux-hardware.org/?probe=0a1b7b959f) | May 24, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [e31519274b](https://linux-hardware.org/?probe=e31519274b) | May 22, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [523ced455c](https://linux-hardware.org/?probe=523ced455c) | May 22, 2021 |
| Acer          | Aspire X1900                | Desktop     | [c4e0203ed9](https://linux-hardware.org/?probe=c4e0203ed9) | May 19, 2021 |
| MSI           | A68HM-E33 V2                | Desktop     | [a14cf2a48e](https://linux-hardware.org/?probe=a14cf2a48e) | May 18, 2021 |
| Dell          | Inspiron 7373               | Convertible | [e4ffc93c6a](https://linux-hardware.org/?probe=e4ffc93c6a) | May 16, 2021 |
| Lenovo        | ThinkPad E15 20RES0GF00     | Notebook    | [8722c3498e](https://linux-hardware.org/?probe=8722c3498e) | May 14, 2021 |
| Acer          | Aspire 4750                 | Notebook    | [5f6a294b7d](https://linux-hardware.org/?probe=5f6a294b7d) | May 12, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [ac4ce770fc](https://linux-hardware.org/?probe=ac4ce770fc) | May 10, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [cbe08b6f59](https://linux-hardware.org/?probe=cbe08b6f59) | May 09, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [b2e6deb92e](https://linux-hardware.org/?probe=b2e6deb92e) | May 09, 2021 |
| ASUSTek       | X450MD                      | Notebook    | [b77e4abcd8](https://linux-hardware.org/?probe=b77e4abcd8) | May 06, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [8467906058](https://linux-hardware.org/?probe=8467906058) | May 04, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [55bfc7d608](https://linux-hardware.org/?probe=55bfc7d608) | May 03, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [bb346e5b0c](https://linux-hardware.org/?probe=bb346e5b0c) | Apr 26, 2021 |
| ASUSTek       | EX-B365M-V5                 | Desktop     | [c169d54571](https://linux-hardware.org/?probe=c169d54571) | Apr 25, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [ff01911cb6](https://linux-hardware.org/?probe=ff01911cb6) | Apr 22, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [b866ec6925](https://linux-hardware.org/?probe=b866ec6925) | Apr 20, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [2e91d0c330](https://linux-hardware.org/?probe=2e91d0c330) | Apr 20, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [f8a3bc6b1d](https://linux-hardware.org/?probe=f8a3bc6b1d) | Apr 19, 2021 |
| Acer          | Nitro AN715-51              | Notebook    | [1cd3975ffa](https://linux-hardware.org/?probe=1cd3975ffa) | Apr 16, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [ef9ba18b59](https://linux-hardware.org/?probe=ef9ba18b59) | Apr 11, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [f66e7cbdfd](https://linux-hardware.org/?probe=f66e7cbdfd) | Apr 11, 2021 |
| HP            | Notebook                    | Notebook    | [023066c915](https://linux-hardware.org/?probe=023066c915) | Apr 08, 2021 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [b11b4274e4](https://linux-hardware.org/?probe=b11b4274e4) | Apr 08, 2021 |
| Dell          | OptiPlex 9010 AIO           | All in one  | [23fdbd4caa](https://linux-hardware.org/?probe=23fdbd4caa) | Apr 08, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YD      | Notebook    | [2870ee333f](https://linux-hardware.org/?probe=2870ee333f) | Apr 07, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YD      | Notebook    | [43b581a270](https://linux-hardware.org/?probe=43b581a270) | Apr 07, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [d1b688c0a9](https://linux-hardware.org/?probe=d1b688c0a9) | Mar 31, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [40b47343b7](https://linux-hardware.org/?probe=40b47343b7) | Mar 28, 2021 |
| Notebook      | NH5x_7xDCx_DDx              | Notebook    | [4f1b6f18bf](https://linux-hardware.org/?probe=4f1b6f18bf) | Mar 26, 2021 |
| Notebook      | NH5x_7xDCx_DDx              | Notebook    | [aec0de9a30](https://linux-hardware.org/?probe=aec0de9a30) | Mar 26, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [4c93424ea5](https://linux-hardware.org/?probe=4c93424ea5) | Mar 26, 2021 |
| Acer          | TravelMate B117-M           | Notebook    | [c205b164c5](https://linux-hardware.org/?probe=c205b164c5) | Mar 26, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [53f5f073d5](https://linux-hardware.org/?probe=53f5f073d5) | Mar 18, 2021 |
| MSI           | Z270 GAMING M7              | Desktop     | [b72439b299](https://linux-hardware.org/?probe=b72439b299) | Mar 17, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [d9ec96bf45](https://linux-hardware.org/?probe=d9ec96bf45) | Mar 15, 2021 |
| Gigabyte      | GA-MA78GM-US2H              | Desktop     | [0f6037a19e](https://linux-hardware.org/?probe=0f6037a19e) | Mar 14, 2021 |
| HP            | Pavilion Laptop 15-cc0xx    | Notebook    | [4b98fb1e80](https://linux-hardware.org/?probe=4b98fb1e80) | Mar 13, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [42dd14b17d](https://linux-hardware.org/?probe=42dd14b17d) | Mar 09, 2021 |
| MSI           | CX62 7QL                    | Notebook    | [8241c594e5](https://linux-hardware.org/?probe=8241c594e5) | Mar 07, 2021 |
| eMachines     | eM250                       | Notebook    | [e20e648698](https://linux-hardware.org/?probe=e20e648698) | Mar 04, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [ec866fbb40](https://linux-hardware.org/?probe=ec866fbb40) | Mar 04, 2021 |
| Lenovo        | ThinkPad T430 2349PS9       | Notebook    | [4f805206d4](https://linux-hardware.org/?probe=4f805206d4) | Mar 03, 2021 |
| Acer          | TravelMate B115-M           | Notebook    | [46b6080608](https://linux-hardware.org/?probe=46b6080608) | Mar 02, 2021 |
| Acer          | TravelMate B115-M           | Notebook    | [4567b99e4e](https://linux-hardware.org/?probe=4567b99e4e) | Mar 02, 2021 |
| HP            | 82A5                        | Mini pc     | [fa16fba963](https://linux-hardware.org/?probe=fa16fba963) | Feb 28, 2021 |
| MSI           | Z97 XPOWER AC               | Desktop     | [c627833398](https://linux-hardware.org/?probe=c627833398) | Feb 23, 2021 |
| Acer          | TravelMate B113             | Notebook    | [5ff9f9bb03](https://linux-hardware.org/?probe=5ff9f9bb03) | Feb 23, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [3582928f83](https://linux-hardware.org/?probe=3582928f83) | Feb 20, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [d392637e95](https://linux-hardware.org/?probe=d392637e95) | Feb 20, 2021 |
| Lenovo        | G450 20022                  | Notebook    | [a98aa9041e](https://linux-hardware.org/?probe=a98aa9041e) | Feb 17, 2021 |
| Sony          | VPCEA36FA                   | Notebook    | [050c395bd5](https://linux-hardware.org/?probe=050c395bd5) | Feb 16, 2021 |
| Lenovo        | ThinkPad L530 24812K6       | Notebook    | [d78f3099e4](https://linux-hardware.org/?probe=d78f3099e4) | Feb 14, 2021 |
| AMD           | A88                         | Desktop     | [11ecb6d298](https://linux-hardware.org/?probe=11ecb6d298) | Feb 14, 2021 |
| Dell          | 0JP3NX A00                  | Desktop     | [3e5d4f837a](https://linux-hardware.org/?probe=3e5d4f837a) | Feb 10, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [8b736da7f7](https://linux-hardware.org/?probe=8b736da7f7) | Feb 09, 2021 |
| JOOYON        | IPM41-D3G                   | Desktop     | [6feab903f8](https://linux-hardware.org/?probe=6feab903f8) | Feb 05, 2021 |
| JOOYON        | IPM41-D3G                   | Desktop     | [5fa1dabba9](https://linux-hardware.org/?probe=5fa1dabba9) | Feb 05, 2021 |
| Acer          | TravelMate B113             | Notebook    | [7e439b847d](https://linux-hardware.org/?probe=7e439b847d) | Feb 04, 2021 |
| Dell          | 0JP3NX A00                  | Desktop     | [1f5d53a4a2](https://linux-hardware.org/?probe=1f5d53a4a2) | Feb 03, 2021 |
| QTQD          | Unknown                     | Desktop     | [2912607416](https://linux-hardware.org/?probe=2912607416) | Jan 27, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YD      | Notebook    | [4c9b44d2d4](https://linux-hardware.org/?probe=4c9b44d2d4) | Jan 26, 2021 |
| Gigabyte      | H97M-D3H                    | Desktop     | [76f0201d14](https://linux-hardware.org/?probe=76f0201d14) | Jan 26, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [795b4f4c7b](https://linux-hardware.org/?probe=795b4f4c7b) | Jan 26, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [6e4545c96a](https://linux-hardware.org/?probe=6e4545c96a) | Jan 23, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [603bb5d8e4](https://linux-hardware.org/?probe=603bb5d8e4) | Jan 22, 2021 |
| ASUSTek       | H81M-C                      | Desktop     | [c108942b4e](https://linux-hardware.org/?probe=c108942b4e) | Jan 19, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [9d8720f796](https://linux-hardware.org/?probe=9d8720f796) | Jan 19, 2021 |
| Acer          | Aspire X1900                | Desktop     | [d0a0250e62](https://linux-hardware.org/?probe=d0a0250e62) | Jan 15, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [1e55ffedfe](https://linux-hardware.org/?probe=1e55ffedfe) | Jan 15, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [6f9868755e](https://linux-hardware.org/?probe=6f9868755e) | Jan 15, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [15b8546bd4](https://linux-hardware.org/?probe=15b8546bd4) | Jan 11, 2021 |
| Gigabyte      | AM1M-S2P                    | Desktop     | [433295603d](https://linux-hardware.org/?probe=433295603d) | Jan 09, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [3f75d5f2e1](https://linux-hardware.org/?probe=3f75d5f2e1) | Jan 07, 2021 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [e6533b7b24](https://linux-hardware.org/?probe=e6533b7b24) | Jan 07, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [91ccfb9b5a](https://linux-hardware.org/?probe=91ccfb9b5a) | Jan 06, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [b5fa895a91](https://linux-hardware.org/?probe=b5fa895a91) | Jan 05, 2021 |
| MSI           | A320M PRO-VD/S V2           | Desktop     | [5d05e8d607](https://linux-hardware.org/?probe=5d05e8d607) | Jan 04, 2021 |
| Toshiba       | dynabook R73/W              | Notebook    | [b84a72cace](https://linux-hardware.org/?probe=b84a72cace) | Jan 02, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [031ad52398](https://linux-hardware.org/?probe=031ad52398) | Jan 01, 2021 |
| ASUSTek       | EX-H310M-V3 R2.0            | Desktop     | [11a5fd5bae](https://linux-hardware.org/?probe=11a5fd5bae) | Dec 30, 2020 |
| MSI           | IONA                        | Desktop     | [bfb84589dd](https://linux-hardware.org/?probe=bfb84589dd) | Dec 28, 2020 |
| MSI           | IONA                        | Desktop     | [0ec5c79eb8](https://linux-hardware.org/?probe=0ec5c79eb8) | Dec 26, 2020 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [459afa05c1](https://linux-hardware.org/?probe=459afa05c1) | Dec 26, 2020 |
| ECS           | H110M-C3D/C3V               | Desktop     | [aa44a6674f](https://linux-hardware.org/?probe=aa44a6674f) | Dec 23, 2020 |
| ASRock        | N68-S3                      | Desktop     | [bfa6bd97d5](https://linux-hardware.org/?probe=bfa6bd97d5) | Dec 23, 2020 |
| MSI           | MS-7541                     | Desktop     | [a6e134920c](https://linux-hardware.org/?probe=a6e134920c) | Dec 22, 2020 |
| MSI           | MS-7541                     | Desktop     | [a44769cfd2](https://linux-hardware.org/?probe=a44769cfd2) | Dec 22, 2020 |
| HP            | ZBook Create G7 Notebook... | Notebook    | [e40ffb436c](https://linux-hardware.org/?probe=e40ffb436c) | Dec 20, 2020 |
| HP            | ZBook Create G7 Notebook... | Notebook    | [b1a2ee65e0](https://linux-hardware.org/?probe=b1a2ee65e0) | Dec 20, 2020 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [d186067403](https://linux-hardware.org/?probe=d186067403) | Dec 17, 2020 |
| ASRock        | N68-S3                      | Desktop     | [1d3067d8cb](https://linux-hardware.org/?probe=1d3067d8cb) | Dec 17, 2020 |
| Acer          | Aspire ES1-431              | Notebook    | [6a99509d25](https://linux-hardware.org/?probe=6a99509d25) | Dec 16, 2020 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [e315898f10](https://linux-hardware.org/?probe=e315898f10) | Dec 16, 2020 |
| Toshiba       | dynabook R73/W              | Notebook    | [96710da884](https://linux-hardware.org/?probe=96710da884) | Dec 14, 2020 |
| Intel         | NUC10i3FNB K61362-303       | Mini pc     | [d942ed05b5](https://linux-hardware.org/?probe=d942ed05b5) | Dec 13, 2020 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [db8ffa8342](https://linux-hardware.org/?probe=db8ffa8342) | Dec 06, 2020 |
| HP            | 8061                        | Desktop     | [0f0bc8b49a](https://linux-hardware.org/?probe=0f0bc8b49a) | Dec 04, 2020 |
| HP            | 8061                        | Desktop     | [a63c8237f1](https://linux-hardware.org/?probe=a63c8237f1) | Dec 04, 2020 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [2a35d394f9](https://linux-hardware.org/?probe=2a35d394f9) | Dec 04, 2020 |
| NEC Comput... | IS8XM                       | Desktop     | [57afeee773](https://linux-hardware.org/?probe=57afeee773) | Nov 30, 2020 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | Notebook    | [4dd4445d4d](https://linux-hardware.org/?probe=4dd4445d4d) | Nov 29, 2020 |
| Acer          | Aspire A315-53G             | Notebook    | [9498233954](https://linux-hardware.org/?probe=9498233954) | Nov 26, 2020 |
| eMachines     | eM350                       | Notebook    | [2bafdd62aa](https://linux-hardware.org/?probe=2bafdd62aa) | Nov 23, 2020 |
| eMachines     | eM350                       | Notebook    | [03b9a0de29](https://linux-hardware.org/?probe=03b9a0de29) | Nov 23, 2020 |
| Apple         | MacBookPro5,5               | Notebook    | [d63213adad](https://linux-hardware.org/?probe=d63213adad) | Nov 22, 2020 |
| ASUSTek       | K43SD                       | Notebook    | [869c3395e8](https://linux-hardware.org/?probe=869c3395e8) | Nov 20, 2020 |
| ASUSTek       | K43SD                       | Notebook    | [3ce330e163](https://linux-hardware.org/?probe=3ce330e163) | Nov 19, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | Desktop     | [354202e98e](https://linux-hardware.org/?probe=354202e98e) | Nov 19, 2020 |
| HP            | Unknown                     | Notebook    | [b525a6fdd2](https://linux-hardware.org/?probe=b525a6fdd2) | Nov 15, 2020 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [f86e0d2af5](https://linux-hardware.org/?probe=f86e0d2af5) | Nov 11, 2020 |
| HP            | 3031h                       | Desktop     | [fb54f48959](https://linux-hardware.org/?probe=fb54f48959) | Nov 10, 2020 |
| HP            | 8061                        | Desktop     | [7936b223e9](https://linux-hardware.org/?probe=7936b223e9) | Nov 10, 2020 |
| ASUSTek       | B85M-G                      | Desktop     | [2c9a8f0838](https://linux-hardware.org/?probe=2c9a8f0838) | Nov 08, 2020 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [c812c2b6f9](https://linux-hardware.org/?probe=c812c2b6f9) | Nov 07, 2020 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [e21be2124d](https://linux-hardware.org/?probe=e21be2124d) | Nov 04, 2020 |
| ASUSTek       | X540NA                      | Notebook    | [7c1cb4cac0](https://linux-hardware.org/?probe=7c1cb4cac0) | Nov 02, 2020 |
| HP            | 8061                        | Desktop     | [d11b92ef18](https://linux-hardware.org/?probe=d11b92ef18) | Nov 01, 2020 |
| Gigabyte      | H81M-DS2                    | Desktop     | [a3cdedf351](https://linux-hardware.org/?probe=a3cdedf351) | Oct 30, 2020 |
| Lenovo        | ThinkPad X220 4290MN4       | Notebook    | [f305f22059](https://linux-hardware.org/?probe=f305f22059) | Oct 29, 2020 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [80d72786c1](https://linux-hardware.org/?probe=80d72786c1) | Oct 26, 2020 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [3919d06624](https://linux-hardware.org/?probe=3919d06624) | Oct 25, 2020 |
| Acer          | Aspire SW3-016              | Notebook    | [e110233803](https://linux-hardware.org/?probe=e110233803) | Oct 24, 2020 |
| Acer          | Aspire ES1-132              | Notebook    | [ecf79444ac](https://linux-hardware.org/?probe=ecf79444ac) | Oct 21, 2020 |
| Pegatron      | IPMSB-H61                   | Desktop     | [c569d86fff](https://linux-hardware.org/?probe=c569d86fff) | Oct 19, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [bfe2deec18](https://linux-hardware.org/?probe=bfe2deec18) | Oct 17, 2020 |
| Acer          | Aspire SW3-016              | Notebook    | [2f0952fbb5](https://linux-hardware.org/?probe=2f0952fbb5) | Oct 15, 2020 |
| HP            | 8061                        | Desktop     | [b2cf684801](https://linux-hardware.org/?probe=b2cf684801) | Oct 13, 2020 |
| Lenovo        | ThinkPad X260 20F5S04206    | Notebook    | [147c40fe70](https://linux-hardware.org/?probe=147c40fe70) | Oct 12, 2020 |
| HP            | Notebook                    | Notebook    | [8cbf9133f7](https://linux-hardware.org/?probe=8cbf9133f7) | Oct 11, 2020 |
| MSI           | MAG B550M MORTAR            | Desktop     | [653a4a9f6e](https://linux-hardware.org/?probe=653a4a9f6e) | Oct 11, 2020 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [9c83568b79](https://linux-hardware.org/?probe=9c83568b79) | Oct 07, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [0053b1ef76](https://linux-hardware.org/?probe=0053b1ef76) | Oct 07, 2020 |
| HP            | 15                          | Notebook    | [c44a5eaea1](https://linux-hardware.org/?probe=c44a5eaea1) | Oct 07, 2020 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [11b8e32835](https://linux-hardware.org/?probe=11b8e32835) | Oct 06, 2020 |
| Lenovo        | ThinkPad X230 2325CTO       | Notebook    | [c1812f8ee0](https://linux-hardware.org/?probe=c1812f8ee0) | Oct 05, 2020 |
| Lenovo        | ThinkPad X230 2325CTO       | Notebook    | [4e98739f72](https://linux-hardware.org/?probe=4e98739f72) | Oct 05, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [73fd7565f6](https://linux-hardware.org/?probe=73fd7565f6) | Oct 05, 2020 |
| Unknown       | Generic RK322x TV Box       | Mini pc     | [2d6256e8c5](https://linux-hardware.org/?probe=2d6256e8c5) | Oct 05, 2020 |
| ASUSTek       | X540NA                      | Notebook    | [a2cee62097](https://linux-hardware.org/?probe=a2cee62097) | Oct 02, 2020 |
| Acer          | Aspire A314-32              | Notebook    | [a51d2f268d](https://linux-hardware.org/?probe=a51d2f268d) | Oct 02, 2020 |
| HP            | Pavilion Laptop 15-cc0xx    | Notebook    | [a8678813c5](https://linux-hardware.org/?probe=a8678813c5) | Oct 01, 2020 |
| ASUSTek       | K75DE                       | Notebook    | [b4cb493794](https://linux-hardware.org/?probe=b4cb493794) | Sep 28, 2020 |
| Dell          | OptiPlex 9010 AIO           | All in one  | [074fb7cc02](https://linux-hardware.org/?probe=074fb7cc02) | Sep 28, 2020 |
| MSI           | A88XM-E35                   | Desktop     | [32556e96bf](https://linux-hardware.org/?probe=32556e96bf) | Sep 27, 2020 |
| MSI           | A88XM-E35                   | Desktop     | [7176092b12](https://linux-hardware.org/?probe=7176092b12) | Sep 27, 2020 |
| HP            | 8061                        | Desktop     | [1d3e0a6b3d](https://linux-hardware.org/?probe=1d3e0a6b3d) | Sep 25, 2020 |
| Dell          | OptiPlex 9010 AIO           | All in one  | [bf1e06fe4f](https://linux-hardware.org/?probe=bf1e06fe4f) | Sep 23, 2020 |
| Dell          | OptiPlex 9010 AIO           | All in one  | [337ba51577](https://linux-hardware.org/?probe=337ba51577) | Sep 23, 2020 |
| ASUSTek       | TUF Gaming FA506IV_FA506... | Notebook    | [72f627fd0e](https://linux-hardware.org/?probe=72f627fd0e) | Sep 21, 2020 |
| Apple         | MacBookAir3,1               | Notebook    | [73e9128968](https://linux-hardware.org/?probe=73e9128968) | Sep 21, 2020 |
| Fujitsu       | FMVA05008                   | Notebook    | [36816f2b18](https://linux-hardware.org/?probe=36816f2b18) | Sep 18, 2020 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [546b3fec83](https://linux-hardware.org/?probe=546b3fec83) | Sep 16, 2020 |
| Lenovo        | V110-14IAP 80TF             | Notebook    | [f0ac65615d](https://linux-hardware.org/?probe=f0ac65615d) | Sep 14, 2020 |
| Lenovo        | V110-14IAP 80TF             | Notebook    | [5acf002102](https://linux-hardware.org/?probe=5acf002102) | Sep 14, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [1cf35a6180](https://linux-hardware.org/?probe=1cf35a6180) | Sep 13, 2020 |
| Lenovo        | V110-14IAP 80TF             | Notebook    | [d2fde2a21e](https://linux-hardware.org/?probe=d2fde2a21e) | Sep 13, 2020 |
| MSI           | CX61 0NC/CX61 0ND/CX61 0... | Notebook    | [5a3c4a23bb](https://linux-hardware.org/?probe=5a3c4a23bb) | Sep 12, 2020 |
| ASUSTek       | X441URK                     | Notebook    | [f883ed5e4b](https://linux-hardware.org/?probe=f883ed5e4b) | Sep 12, 2020 |
| Dell          | OptiPlex 9010 AIO           | All in one  | [a2e7991749](https://linux-hardware.org/?probe=a2e7991749) | Sep 11, 2020 |
| Dell          | Latitude E4300              | Notebook    | [8b163ddf1e](https://linux-hardware.org/?probe=8b163ddf1e) | Sep 09, 2020 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [eaff730455](https://linux-hardware.org/?probe=eaff730455) | Sep 09, 2020 |
| Apple         | MacBookAir2,1               | Notebook    | [c4b26d8019](https://linux-hardware.org/?probe=c4b26d8019) | Sep 08, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [809af585ab](https://linux-hardware.org/?probe=809af585ab) | Sep 08, 2020 |
| Lenovo        | ThinkPad E580 20KSA00UAU    | Notebook    | [becbbe530b](https://linux-hardware.org/?probe=becbbe530b) | Sep 07, 2020 |
| Acer          | Aspire 4752                 | Notebook    | [9c779dc588](https://linux-hardware.org/?probe=9c779dc588) | Sep 04, 2020 |
| Acer          | Aspire 4752                 | Notebook    | [efeb5dd920](https://linux-hardware.org/?probe=efeb5dd920) | Sep 04, 2020 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [9557e9d02c](https://linux-hardware.org/?probe=9557e9d02c) | Sep 04, 2020 |
| Acer          | Aspire A315-41G             | Notebook    | [ec1a232ba9](https://linux-hardware.org/?probe=ec1a232ba9) | Sep 03, 2020 |
| Acer          | Aspire A315-41G             | Notebook    | [3cff1527be](https://linux-hardware.org/?probe=3cff1527be) | Sep 03, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [0fda90e55c](https://linux-hardware.org/?probe=0fda90e55c) | Sep 03, 2020 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | Notebook    | [4a5f93ed76](https://linux-hardware.org/?probe=4a5f93ed76) | Sep 03, 2020 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | Notebook    | [e11793b02c](https://linux-hardware.org/?probe=e11793b02c) | Sep 02, 2020 |
| ASUSTek       | X441URK                     | Notebook    | [35b06d497e](https://linux-hardware.org/?probe=35b06d497e) | Sep 02, 2020 |
| Clevo         | M7x0S                       | Notebook    | [100fc7862e](https://linux-hardware.org/?probe=100fc7862e) | Sep 02, 2020 |
| Clevo         | M7x0S                       | Notebook    | [6d9f5403eb](https://linux-hardware.org/?probe=6d9f5403eb) | Sep 02, 2020 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [288f4f772c](https://linux-hardware.org/?probe=288f4f772c) | Sep 01, 2020 |
| Lenovo        | IdeaPad Z460 20059          | Notebook    | [9568d009c0](https://linux-hardware.org/?probe=9568d009c0) | Sep 01, 2020 |
| Lenovo        | ThinkPad X240 20AMS0SA0J    | Notebook    | [5e85d0fa0e](https://linux-hardware.org/?probe=5e85d0fa0e) | Aug 31, 2020 |
| Clevo         | M7x0S                       | Notebook    | [7efc902d33](https://linux-hardware.org/?probe=7efc902d33) | Aug 31, 2020 |
| Clevo         | M7x0S                       | Notebook    | [58b7846f61](https://linux-hardware.org/?probe=58b7846f61) | Aug 30, 2020 |
| Dell          | Latitude E7450              | Notebook    | [7b6b25e684](https://linux-hardware.org/?probe=7b6b25e684) | Aug 27, 2020 |
| Acer          | Swift SF314-41              | Notebook    | [290159761f](https://linux-hardware.org/?probe=290159761f) | Aug 27, 2020 |
| HP            | Pavilion g4                 | Notebook    | [55dec82070](https://linux-hardware.org/?probe=55dec82070) | Aug 26, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [de3f00fc50](https://linux-hardware.org/?probe=de3f00fc50) | Aug 26, 2020 |
| ASUSTek       | X540NA                      | Notebook    | [8747f9eb75](https://linux-hardware.org/?probe=8747f9eb75) | Aug 22, 2020 |
| ASUSTek       | X540NA                      | Notebook    | [b1d91b9932](https://linux-hardware.org/?probe=b1d91b9932) | Aug 21, 2020 |
| Biostar       | H81MHV3                     | Desktop     | [ecd87de5e0](https://linux-hardware.org/?probe=ecd87de5e0) | Aug 21, 2020 |
| Sony          | SVF14216SGP                 | Notebook    | [31495e375f](https://linux-hardware.org/?probe=31495e375f) | Aug 19, 2020 |
| Dell          | 0VRWRC A00                  | Desktop     | [b5e17b6229](https://linux-hardware.org/?probe=b5e17b6229) | Aug 16, 2020 |
| HP            | Pavilion dv6000 (RU700UA... | Notebook    | [56702de7d4](https://linux-hardware.org/?probe=56702de7d4) | Aug 15, 2020 |
| HP            | Pavilion dv6000 (RU700UA... | Notebook    | [d868e4a7f9](https://linux-hardware.org/?probe=d868e4a7f9) | Aug 15, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [eed0bce682](https://linux-hardware.org/?probe=eed0bce682) | Aug 14, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [532d54162a](https://linux-hardware.org/?probe=532d54162a) | Aug 14, 2020 |
| Lenovo        | ThinkPad T400 2768CC1       | Notebook    | [a5e0d02669](https://linux-hardware.org/?probe=a5e0d02669) | Aug 12, 2020 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [6b5b2287e0](https://linux-hardware.org/?probe=6b5b2287e0) | Aug 07, 2020 |
| Lenovo        | ThinkPad T400 2768CC1       | Notebook    | [aa6089eda7](https://linux-hardware.org/?probe=aa6089eda7) | Aug 06, 2020 |
| Lenovo        | ThinkPad T400 2768CC1       | Notebook    | [86ee9f7736](https://linux-hardware.org/?probe=86ee9f7736) | Aug 06, 2020 |
| MSI           | GV62 8RD                    | Notebook    | [0b6cd63268](https://linux-hardware.org/?probe=0b6cd63268) | Aug 04, 2020 |
| HP            | Pavilion g4                 | Notebook    | [4fc16d6e09](https://linux-hardware.org/?probe=4fc16d6e09) | Aug 02, 2020 |
| HP            | Pavilion g4                 | Notebook    | [0b9fc56cd1](https://linux-hardware.org/?probe=0b9fc56cd1) | Aug 02, 2020 |
| HP            | 805D                        | Desktop     | [b0f200fe77](https://linux-hardware.org/?probe=b0f200fe77) | Jul 29, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [3fd417f684](https://linux-hardware.org/?probe=3fd417f684) | Jul 29, 2020 |
| Acer          | Aspire ES1-521              | Notebook    | [64a762e6b8](https://linux-hardware.org/?probe=64a762e6b8) | Jul 26, 2020 |
| HP            | Notebook                    | Notebook    | [7dd7f12bb9](https://linux-hardware.org/?probe=7dd7f12bb9) | Jul 25, 2020 |
| HP            | Notebook                    | Notebook    | [55ab6c06c5](https://linux-hardware.org/?probe=55ab6c06c5) | Jul 25, 2020 |
| Acer          | Aspire ES1-521              | Notebook    | [23d8c2d2cf](https://linux-hardware.org/?probe=23d8c2d2cf) | Jul 25, 2020 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [ca9dc81053](https://linux-hardware.org/?probe=ca9dc81053) | Jul 25, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YD      | Notebook    | [d486d4bc03](https://linux-hardware.org/?probe=d486d4bc03) | Jul 24, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YD      | Notebook    | [f12d8d16e5](https://linux-hardware.org/?probe=f12d8d16e5) | Jul 16, 2020 |
| Acer          | Aspire ES1-132              | Notebook    | [d1bc3c3a8a](https://linux-hardware.org/?probe=d1bc3c3a8a) | Jul 10, 2020 |
| Acer          | Aspire ES1-132              | Notebook    | [cb26f9925f](https://linux-hardware.org/?probe=cb26f9925f) | Jul 09, 2020 |
| ASUSTek       | X540NA                      | Notebook    | [2e3aac14fe](https://linux-hardware.org/?probe=2e3aac14fe) | Jul 02, 2020 |
| Acer          | Aspire V5-431               | Notebook    | [0287b85983](https://linux-hardware.org/?probe=0287b85983) | Jun 30, 2020 |
| Lenovo        | ThinkPad T530 2429HC3       | Notebook    | [fb0a45d925](https://linux-hardware.org/?probe=fb0a45d925) | Jun 27, 2020 |
| Lenovo        | ThinkPad T530 2429HC3       | Notebook    | [99e750162d](https://linux-hardware.org/?probe=99e750162d) | Jun 27, 2020 |
| eMachines     | eM350                       | Notebook    | [b699bf9fb6](https://linux-hardware.org/?probe=b699bf9fb6) | Jun 25, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [1107791eab](https://linux-hardware.org/?probe=1107791eab) | Jun 22, 2020 |
| MSI           | Z170A GAMING M3             | Desktop     | [22963b821f](https://linux-hardware.org/?probe=22963b821f) | Jun 20, 2020 |
| MSI           | Z170A GAMING M3             | Desktop     | [c5779593cc](https://linux-hardware.org/?probe=c5779593cc) | Jun 20, 2020 |
| Acer          | Aspire ES1-132              | Notebook    | [7c1783588a](https://linux-hardware.org/?probe=7c1783588a) | Jun 12, 2020 |
| Acer          | Aspire ES1-132              | Notebook    | [cbbefff0a6](https://linux-hardware.org/?probe=cbbefff0a6) | Jun 12, 2020 |
| Biostar       | Hi-Fi A68U3P                | Desktop     | [ec653ae1fc](https://linux-hardware.org/?probe=ec653ae1fc) | Jun 11, 2020 |
| HP            | 15                          | Notebook    | [a4b90e7ad1](https://linux-hardware.org/?probe=a4b90e7ad1) | Jun 05, 2020 |
| ASUSTek       | X540UP                      | Notebook    | [2ec9f9c770](https://linux-hardware.org/?probe=2ec9f9c770) | Jun 05, 2020 |
| Dell          | Latitude 7490               | Notebook    | [b7b69c9cbf](https://linux-hardware.org/?probe=b7b69c9cbf) | Jun 05, 2020 |
| MSI           | MS-N014                     | Notebook    | [e9fd398a70](https://linux-hardware.org/?probe=e9fd398a70) | Jun 04, 2020 |
| Gigabyte      | X299 UD4 Pro-CF             | Desktop     | [5cde7141d6](https://linux-hardware.org/?probe=5cde7141d6) | Jun 02, 2020 |
| Google        | Caroline                    | Notebook    | [4e305a0551](https://linux-hardware.org/?probe=4e305a0551) | May 31, 2020 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [2a2f1b6680](https://linux-hardware.org/?probe=2a2f1b6680) | May 27, 2020 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [6bdc484d30](https://linux-hardware.org/?probe=6bdc484d30) | May 25, 2020 |
| ASUSTek       | N45SF                       | Notebook    | [a73c8a7057](https://linux-hardware.org/?probe=a73c8a7057) | May 24, 2020 |
| Acer          | Aspire A315-51              | Notebook    | [8d5860b41f](https://linux-hardware.org/?probe=8d5860b41f) | May 23, 2020 |
| Acer          | Aspire A315-51              | Notebook    | [931084ae9c](https://linux-hardware.org/?probe=931084ae9c) | May 23, 2020 |
| ASUSTek       | N45SF                       | Notebook    | [e35a078b83](https://linux-hardware.org/?probe=e35a078b83) | May 23, 2020 |
| HP            | 17E2                        | Mini pc     | [b62ca0352c](https://linux-hardware.org/?probe=b62ca0352c) | May 22, 2020 |
| HP            | EliteBook 745 G3            | Notebook    | [ebd5778f8c](https://linux-hardware.org/?probe=ebd5778f8c) | May 22, 2020 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [a36437dc35](https://linux-hardware.org/?probe=a36437dc35) | May 22, 2020 |
| Lenovo        | ThinkPad X280 20KES69A00    | Notebook    | [c1fc46e405](https://linux-hardware.org/?probe=c1fc46e405) | May 21, 2020 |
| Acer          | Aspire ES1-431              | Notebook    | [58ad8d0b01](https://linux-hardware.org/?probe=58ad8d0b01) | May 18, 2020 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [9e80b645d9](https://linux-hardware.org/?probe=9e80b645d9) | May 17, 2020 |
| Toshiba       | Satellite Pro U400          | Notebook    | [7114a6459c](https://linux-hardware.org/?probe=7114a6459c) | May 17, 2020 |
| Acer          | Aspire ES1-431              | Notebook    | [32fb20af11](https://linux-hardware.org/?probe=32fb20af11) | May 16, 2020 |
| Lenovo        | IdeaPad S540-15IML 81NG     | Notebook    | [89e361466e](https://linux-hardware.org/?probe=89e361466e) | May 14, 2020 |
| HP            | Notebook                    | Notebook    | [142457c9ea](https://linux-hardware.org/?probe=142457c9ea) | May 12, 2020 |
| Dell          | 0D28YY A03                  | Desktop     | [7ae56aa829](https://linux-hardware.org/?probe=7ae56aa829) | May 11, 2020 |
| Acer          | Aspire M5-481PT             | Notebook    | [772cc038ae](https://linux-hardware.org/?probe=772cc038ae) | May 09, 2020 |
| Acer          | Aspire M5-481PT             | Notebook    | [332e871ec3](https://linux-hardware.org/?probe=332e871ec3) | May 09, 2020 |
| Acer          | Aspire ES1-431              | Notebook    | [429d4a7720](https://linux-hardware.org/?probe=429d4a7720) | May 03, 2020 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [028f510367](https://linux-hardware.org/?probe=028f510367) | May 03, 2020 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [d4cbef0ab2](https://linux-hardware.org/?probe=d4cbef0ab2) | May 02, 2020 |
| HP            | EliteBook 745 G2            | Notebook    | [60ee09d8aa](https://linux-hardware.org/?probe=60ee09d8aa) | May 02, 2020 |
| Dell          | 0D28YY A03                  | Desktop     | [285c59f702](https://linux-hardware.org/?probe=285c59f702) | Apr 29, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | Desktop     | [36bb48017f](https://linux-hardware.org/?probe=36bb48017f) | Apr 29, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | Desktop     | [1f91672dce](https://linux-hardware.org/?probe=1f91672dce) | Apr 28, 2020 |
| ASRock        | 960GC-GS FX                 | Desktop     | [6b07754d1d](https://linux-hardware.org/?probe=6b07754d1d) | Apr 27, 2020 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [e487e06d2c](https://linux-hardware.org/?probe=e487e06d2c) | Apr 26, 2020 |
| ASRock        | 960GC-GS FX                 | Desktop     | [390a1cbbb3](https://linux-hardware.org/?probe=390a1cbbb3) | Apr 25, 2020 |
| Biostar       | H81MHV3                     | Desktop     | [252b646f8b](https://linux-hardware.org/?probe=252b646f8b) | Apr 25, 2020 |
| Biostar       | H81MHV3                     | Desktop     | [0fe6d54c09](https://linux-hardware.org/?probe=0fe6d54c09) | Apr 25, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | Desktop     | [eec2e1e90f](https://linux-hardware.org/?probe=eec2e1e90f) | Apr 24, 2020 |
| Dell          | 0D28YY A03                  | Desktop     | [cb0a381ca1](https://linux-hardware.org/?probe=cb0a381ca1) | Apr 22, 2020 |
| Lenovo        | ThinkPad T460s 20F9004FU... | Notebook    | [8eacfd828e](https://linux-hardware.org/?probe=8eacfd828e) | Apr 21, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | Desktop     | [dbe36dfd4f](https://linux-hardware.org/?probe=dbe36dfd4f) | Apr 21, 2020 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [06c5a92500](https://linux-hardware.org/?probe=06c5a92500) | Apr 18, 2020 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [b87b3feefd](https://linux-hardware.org/?probe=b87b3feefd) | Apr 18, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | Desktop     | [d092c3db85](https://linux-hardware.org/?probe=d092c3db85) | Apr 16, 2020 |
| Clevo         | M7x0S                       | Notebook    | [7ba28306d0](https://linux-hardware.org/?probe=7ba28306d0) | Apr 16, 2020 |
| Clevo         | M7x0S                       | Notebook    | [23aa6b7beb](https://linux-hardware.org/?probe=23aa6b7beb) | Apr 16, 2020 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [8eca04a69b](https://linux-hardware.org/?probe=8eca04a69b) | Apr 14, 2020 |
| Dell          | Inspiron 3442               | Notebook    | [4d48cc531a](https://linux-hardware.org/?probe=4d48cc531a) | Apr 13, 2020 |
| Dell          | Inspiron 3442               | Notebook    | [07a7a6e630](https://linux-hardware.org/?probe=07a7a6e630) | Apr 13, 2020 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [576c3b1853](https://linux-hardware.org/?probe=576c3b1853) | Apr 13, 2020 |
| TriGem Com... | DreamSys                    | Desktop     | [e5a22f4123](https://linux-hardware.org/?probe=e5a22f4123) | Apr 09, 2020 |
| Clevo         | E412X                       | Notebook    | [0cca012f20](https://linux-hardware.org/?probe=0cca012f20) | Apr 09, 2020 |
| Acer          | Aspire ES1-431              | Notebook    | [3bf24f9dd6](https://linux-hardware.org/?probe=3bf24f9dd6) | Apr 07, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [c00e4e1a0e](https://linux-hardware.org/?probe=c00e4e1a0e) | Apr 07, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [087a36a4bd](https://linux-hardware.org/?probe=087a36a4bd) | Apr 04, 2020 |
| Biostar       | Hi-Fi A68U3P                | Desktop     | [35b973ebbb](https://linux-hardware.org/?probe=35b973ebbb) | Apr 03, 2020 |
| HP            | EliteBook 745 G2            | Notebook    | [68ecbaa367](https://linux-hardware.org/?probe=68ecbaa367) | Apr 03, 2020 |
| Acer          | Aspire V3-772G              | Notebook    | [9e4c202def](https://linux-hardware.org/?probe=9e4c202def) | Apr 03, 2020 |
| Acer          | Aspire ES1-431              | Notebook    | [3959954db3](https://linux-hardware.org/?probe=3959954db3) | Apr 02, 2020 |
| NEC Comput... | PC-VY24GXZ7A                | Notebook    | [bc0996781f](https://linux-hardware.org/?probe=bc0996781f) | Apr 02, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [9355c0ff9e](https://linux-hardware.org/?probe=9355c0ff9e) | Apr 01, 2020 |
| HP            | 0A5Ch                       | Desktop     | [5f4bf573ad](https://linux-hardware.org/?probe=5f4bf573ad) | Mar 28, 2020 |
| HP            | 0A5Ch                       | Desktop     | [7411b1a819](https://linux-hardware.org/?probe=7411b1a819) | Mar 28, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [8c6dbdb971](https://linux-hardware.org/?probe=8c6dbdb971) | Mar 25, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [70b408e2f0](https://linux-hardware.org/?probe=70b408e2f0) | Mar 25, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [be10de1b16](https://linux-hardware.org/?probe=be10de1b16) | Mar 24, 2020 |
| Dell          | Latitude E6430              | Notebook    | [e38eb04918](https://linux-hardware.org/?probe=e38eb04918) | Mar 23, 2020 |
| ASUSTek       | N45SF                       | Notebook    | [17ec9504f1](https://linux-hardware.org/?probe=17ec9504f1) | Mar 22, 2020 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [92e778ba2a](https://linux-hardware.org/?probe=92e778ba2a) | Mar 21, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [f7cbec79e8](https://linux-hardware.org/?probe=f7cbec79e8) | Mar 15, 2020 |
| Gigabyte      | H310M DS2                   | Desktop     | [529f84f7d1](https://linux-hardware.org/?probe=529f84f7d1) | Mar 12, 2020 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [636f6029b4](https://linux-hardware.org/?probe=636f6029b4) | Mar 11, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [861919e59d](https://linux-hardware.org/?probe=861919e59d) | Mar 08, 2020 |
| MSI           | MS-7309                     | Desktop     | [dff3f373f6](https://linux-hardware.org/?probe=dff3f373f6) | Mar 08, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [2b1b62332c](https://linux-hardware.org/?probe=2b1b62332c) | Mar 08, 2020 |
| MSI           | MS-7309                     | Desktop     | [e52b770dff](https://linux-hardware.org/?probe=e52b770dff) | Mar 08, 2020 |
| MSI           | MS-7309                     | Desktop     | [a06909608c](https://linux-hardware.org/?probe=a06909608c) | Mar 08, 2020 |
| MSI           | MS-7309                     | Desktop     | [b3e1633a13](https://linux-hardware.org/?probe=b3e1633a13) | Mar 08, 2020 |
| Sony          | SVP13215CDB                 | Notebook    | [0aac039fdc](https://linux-hardware.org/?probe=0aac039fdc) | Mar 06, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Philippines/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 22.04                 | 58        | 7.73%   |
| Ubuntu 20.04                 | 58        | 7.73%   |
| Pop!_OS 22.04                | 29        | 3.87%   |
| Pop!_OS 20.04                | 25        | 3.33%   |
| Ubuntu 18.04                 | 23        | 3.07%   |
| KDE neon 20.04               | 18        | 2.4%    |
| Arch Rolling                 | 17        | 2.27%   |
| Fedora 38                    | 15        | 2%      |
| OpenMandriva 4.2             | 14        | 1.87%   |
| Manjaro                      | 13        | 1.73%   |
| Zorin 16                     | 12        | 1.6%    |
| Debian 12                    | 12        | 1.6%    |
| ArcoLinux Rolling            | 12        | 1.6%    |
| Zorin 15                     | 11        | 1.47%   |
| Fedora 39                    | 11        | 1.47%   |
| Fedora 36                    | 11        | 1.47%   |
| Pop!_OS 21.04                | 10        | 1.33%   |
| KDE neon 22.04               | 10        | 1.33%   |
| OpenMandriva 4.3             | 9         | 1.2%    |
| Ubuntu 23.04                 | 8         | 1.07%   |
| Linux Mint 21.2              | 8         | 1.07%   |
| Linux Mint 20.2              | 8         | 1.07%   |
| Kubuntu 22.04                | 8         | 1.07%   |
| Debian 11                    | 8         | 1.07%   |
| BlackPanther 18.1            | 8         | 1.07%   |
| Arch                         | 8         | 1.07%   |
| Linux Mint 20.1              | 7         | 0.93%   |
| Pop!_OS 20.10                | 6         | 0.8%    |
| Linux Mint 21.1              | 6         | 0.8%    |
| Linux Mint 20.3              | 6         | 0.8%    |
| Fedora 33                    | 6         | 0.8%    |
| Endless 3.7.7                | 6         | 0.8%    |
| Ubuntu 20.10                 | 5         | 0.67%   |
| openSUSE Tumbleweed-XXXXXXXX | 5         | 0.67%   |
| Linux Mint 21                | 5         | 0.67%   |
| Linux Mint 19.3              | 5         | 0.67%   |
| Fedora 37                    | 5         | 0.67%   |
| Fedora 35                    | 5         | 0.67%   |
| Fedora 32                    | 5         | 0.67%   |
| Endless 3.7.6                | 5         | 0.67%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 162       | 23.01%  |
| Pop!_OS       | 74        | 10.51%  |
| Fedora        | 60        | 8.52%   |
| Linux Mint    | 57        | 8.1%    |
| OpenMandriva  | 37        | 5.26%   |
| Endless       | 32        | 4.55%   |
| KDE neon      | 30        | 4.26%   |
| Zorin         | 26        | 3.69%   |
| Debian        | 25        | 3.55%   |
| Arch          | 25        | 3.55%   |
| Manjaro       | 22        | 3.13%   |
| Kubuntu       | 14        | 1.99%   |
| ArcoLinux     | 14        | 1.99%   |
| Kali          | 12        | 1.7%    |
| Xubuntu       | 11        | 1.56%   |
| SteamOS       | 11        | 1.56%   |
| BlackPanther  | 10        | 1.42%   |
| Nobara        | 8         | 1.14%   |
| Elementary    | 7         | 0.99%   |
| openSUSE      | 6         | 0.85%   |
| EndeavourOS   | 6         | 0.85%   |
| Ubuntu Unity  | 5         | 0.71%   |
| Lubuntu       | 5         | 0.71%   |
| LMDE          | 5         | 0.71%   |
| Ubuntu MATE   | 4         | 0.57%   |
| Xero          | 3         | 0.43%   |
| ROSA          | 3         | 0.43%   |
| Peppermint    | 3         | 0.43%   |
| Pikaos        | 2         | 0.28%   |
| MX            | 2         | 0.28%   |
| Linux Lite    | 2         | 0.28%   |
| Gentoo        | 2         | 0.28%   |
| Garuda Linux  | 2         | 0.28%   |
| Clear Linux   | 2         | 0.28%   |
| BunsenLabs    | 2         | 0.28%   |
| Ultramarine   | 1         | 0.14%   |
| Ubuntu Budgie | 1         | 0.14%   |
| Sparky        | 1         | 0.14%   |
| Solus         | 1         | 0.14%   |
| Slackware     | 1         | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 18        | 2.21%   |
| 5.10.14-desktop-1omv4002 | 14        | 1.72%   |
| 5.3.0-28-generic         | 10        | 1.23%   |
| 5.16.7-desktop-1omv4003  | 9         | 1.1%    |
| 5.4.0-7634-generic       | 8         | 0.98%   |
| 5.4.0-48-generic         | 8         | 0.98%   |
| 4.18.16-desktop-1bP      | 8         | 0.98%   |
| 5.3.0-23-generic         | 7         | 0.86%   |
| 5.15.0-56-generic        | 7         | 0.86%   |
| 6.2.6-76060206-generic   | 6         | 0.74%   |
| 5.8.0-7630-generic       | 6         | 0.74%   |
| 5.8.0-14-generic         | 6         | 0.74%   |
| 5.4.0-58-generic         | 6         | 0.74%   |
| 5.19.0-32-generic        | 6         | 0.74%   |
| 5.15.0-52-generic        | 6         | 0.74%   |
| 5.15.0-41-generic        | 6         | 0.74%   |
| 5.13.0-valve36-1-neptune | 6         | 0.74%   |
| 6.5.0-27-generic         | 5         | 0.61%   |
| 6.5.0-26-generic         | 5         | 0.61%   |
| 6.2.9-300.fc38.x86_64    | 5         | 0.61%   |
| 6.2.0-37-generic         | 5         | 0.61%   |
| 6.2.0-26-generic         | 5         | 0.61%   |
| 6.2.0-20-generic         | 5         | 0.61%   |
| 5.4.0-47-generic         | 5         | 0.61%   |
| 5.15.0-58-generic        | 5         | 0.61%   |
| 5.15.0-50-generic        | 5         | 0.61%   |
| 5.11.0-7620-generic      | 5         | 0.61%   |
| 4.9.20-desktop-pae-1bP   | 5         | 0.61%   |
| 6.5.0-17-generic         | 4         | 0.49%   |
| 6.4.11-desktop-1omv2390  | 4         | 0.49%   |
| 6.2.6-desktop-1omv2390   | 4         | 0.49%   |
| 6.2.0-33-generic         | 4         | 0.49%   |
| 6.2.0-32-generic         | 4         | 0.49%   |
| 5.4.0-7642-generic       | 4         | 0.49%   |
| 5.4.0-73-generic         | 4         | 0.49%   |
| 5.4.0-19-generic         | 4         | 0.49%   |
| 5.15.0-60-generic        | 4         | 0.49%   |
| 5.15.0-48-generic        | 4         | 0.49%   |
| 5.13.0-7614-generic      | 4         | 0.49%   |
| 5.13.0-30-generic        | 4         | 0.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 100       | 12.82%  |
| 5.15.0  | 75        | 9.62%   |
| 5.13.0  | 37        | 4.74%   |
| 5.3.0   | 32        | 4.1%    |
| 5.8.0   | 31        | 3.97%   |
| 6.2.0   | 30        | 3.85%   |
| 5.11.0  | 26        | 3.33%   |
| 6.5.0   | 25        | 3.21%   |
| 5.19.0  | 23        | 2.95%   |
| 4.15.0  | 22        | 2.82%   |
| 5.10.14 | 14        | 1.79%   |
| 6.1.0   | 13        | 1.67%   |
| 6.2.6   | 11        | 1.41%   |
| 5.0.0   | 11        | 1.41%   |
| 4.18.0  | 10        | 1.28%   |
| 5.16.7  | 9         | 1.15%   |
| 5.10.0  | 8         | 1.03%   |
| 4.19.0  | 8         | 1.03%   |
| 4.18.16 | 8         | 1.03%   |
| 5.17.5  | 6         | 0.77%   |
| 4.9.20  | 6         | 0.77%   |
| 6.4.11  | 5         | 0.64%   |
| 6.2.9   | 5         | 0.64%   |
| 6.0.6   | 5         | 0.64%   |
| 6.8.1   | 4         | 0.51%   |
| 6.5.6   | 4         | 0.51%   |
| 6.5.5   | 4         | 0.51%   |
| 6.0.0   | 4         | 0.51%   |
| 6.8.2   | 3         | 0.38%   |
| 6.7.0   | 3         | 0.38%   |
| 6.6.6   | 3         | 0.38%   |
| 6.6.4   | 3         | 0.38%   |
| 6.6.3   | 3         | 0.38%   |
| 6.6.2   | 3         | 0.38%   |
| 6.5.7   | 3         | 0.38%   |
| 6.3.5   | 3         | 0.38%   |
| 6.1.52  | 3         | 0.38%   |
| 6.1.1   | 3         | 0.38%   |
| 6.0.12  | 3         | 0.38%   |
| 5.9.16  | 3         | 0.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 111       | 14.49%  |
| 5.15    | 95        | 12.4%   |
| 6.2     | 52        | 6.79%   |
| 6.5     | 42        | 5.48%   |
| 5.13    | 40        | 5.22%   |
| 5.8     | 38        | 4.96%   |
| 6.1     | 37        | 4.83%   |
| 5.10    | 35        | 4.57%   |
| 5.3     | 34        | 4.44%   |
| 5.19    | 33        | 4.31%   |
| 5.11    | 31        | 4.05%   |
| 4.15    | 22        | 2.87%   |
| 6.6     | 20        | 2.61%   |
| 6.0     | 20        | 2.61%   |
| 5.16    | 20        | 2.61%   |
| 4.18    | 18        | 2.35%   |
| 6.4     | 17        | 2.22%   |
| 5.18    | 12        | 1.57%   |
| 5.0     | 12        | 1.57%   |
| 6.8     | 11        | 1.44%   |
| 6.3     | 8         | 1.04%   |
| 5.17    | 8         | 1.04%   |
| 4.9     | 8         | 1.04%   |
| 4.19    | 8         | 1.04%   |
| 6.7     | 7         | 0.91%   |
| 5.9     | 7         | 0.91%   |
| 5.14    | 4         | 0.52%   |
| 4.4     | 4         | 0.52%   |
| 5.6     | 3         | 0.39%   |
| 5.7     | 2         | 0.26%   |
| 5.12    | 2         | 0.26%   |
| 4.13    | 2         | 0.26%   |
| 5.2     | 1         | 0.13%   |
| 5.1     | 1         | 0.13%   |
| 3.8     | 1         | 0.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 651       | 96.16%  |
| i686    | 15        | 2.22%   |
| aarch64 | 6         | 0.89%   |
| armv7l  | 5         | 0.74%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 326       | 46.11%  |
| KDE5            | 150       | 21.22%  |
| XFCE            | 55        | 7.78%   |
| X-Cinnamon      | 53        | 7.5%    |
| Unknown         | 44        | 6.22%   |
| KDE             | 17        | 2.4%    |
| MATE            | 11        | 1.56%   |
| LXQt            | 9         | 1.27%   |
| Pantheon        | 6         | 0.85%   |
| Budgie          | 5         | 0.71%   |
| Unity           | 4         | 0.57%   |
| KDE6            | 4         | 0.57%   |
| LXDE            | 3         | 0.42%   |
| Hyprland        | 3         | 0.42%   |
| Cinnamon        | 3         | 0.42%   |
| Openbox         | 2         | 0.28%   |
| sway            | 1         | 0.14%   |
| river           | 1         | 0.14%   |
| pika:GNOME      | 1         | 0.14%   |
| GNOME Flashback | 1         | 0.14%   |
| GNOME Classic   | 1         | 0.14%   |
| dwm             | 1         | 0.14%   |
| default         | 1         | 0.14%   |
| Deepin          | 1         | 0.14%   |
| Cutefish        | 1         | 0.14%   |
| BunsenLabs      | 1         | 0.14%   |
| bspwm           | 1         | 0.14%   |
| awesome         | 1         | 0.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 517       | 74.39%  |
| Wayland | 143       | 20.58%  |
| Unknown | 21        | 3.02%   |
| Tty     | 14        | 2.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 366       | 51.84%  |
| SDDM    | 107       | 15.16%  |
| GDM3    | 93        | 13.17%  |
| GDM     | 65        | 9.21%   |
| LightDM | 62        | 8.78%   |
| TDM     | 10        | 1.42%   |
| SLiM    | 1         | 0.14%   |
| MDM     | 1         | 0.14%   |
| LXDM    | 1         | 0.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| en_PH            | 327       | 46.78%  |
| en_US            | 275       | 39.34%  |
| Unknown          | 46        | 6.58%   |
| C                | 17        | 2.43%   |
| en_GB            | 8         | 1.14%   |
| de_DE            | 7         | 1%      |
| en_AU            | 4         | 0.57%   |
| zh_CN            | 2         | 0.29%   |
| en_HK            | 2         | 0.29%   |
| zh_HK            | 1         | 0.14%   |
| tl_PH            | 1         | 0.14%   |
| ja_JP            | 1         | 0.14%   |
| fil_PH           | 1         | 0.14%   |
| en_ZA            | 1         | 0.14%   |
| en_US.ISO-8859-1 | 1         | 0.14%   |
| en_NZ            | 1         | 0.14%   |
| en_IN            | 1         | 0.14%   |
| en_DK            | 1         | 0.14%   |
| en_CA            | 1         | 0.14%   |
| da_DK            | 1         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 351       | 50.5%   |
| BIOS | 344       | 49.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 488       | 69.81%  |
| Btrfs   | 106       | 15.16%  |
| Overlay | 59        | 8.44%   |
| Tmpfs   | 22        | 3.15%   |
| Unknown | 11        | 1.57%   |
| Xfs     | 7         | 1%      |
| Zfs     | 3         | 0.43%   |
| Ext2    | 3         | 0.43%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 372       | 53.14%  |
| GPT     | 262       | 37.43%  |
| MBR     | 66        | 9.43%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 609       | 88.01%  |
| Yes       | 83        | 11.99%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 506       | 72.7%   |
| Yes       | 190       | 27.3%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| Lenovo                    | 98        | 14.54%  |
| ASUSTek Computer          | 93        | 13.8%   |
| Hewlett-Packard           | 83        | 12.31%  |
| Acer                      | 77        | 11.42%  |
| Dell                      | 59        | 8.75%   |
| Gigabyte Technology       | 54        | 8.01%   |
| MSI                       | 50        | 7.42%   |
| ASRock                    | 17        | 2.52%   |
| Unknown                   | 15        | 2.23%   |
| Toshiba                   | 14        | 2.08%   |
| Apple                     | 12        | 1.78%   |
| Valve                     | 9         | 1.34%   |
| Samsung Electronics       | 8         | 1.19%   |
| HUAWEI                    | 8         | 1.19%   |
| Biostar                   | 8         | 1.19%   |
| Raspberry Pi Foundation   | 6         | 0.89%   |
| ECS                       | 6         | 0.89%   |
| Foxconn                   | 5         | 0.74%   |
| Sony                      | 4         | 0.59%   |
| NEC Computers             | 4         | 0.59%   |
| EMAXX TECHNOLOGY          | 4         | 0.59%   |
| Clevo                     | 4         | 0.59%   |
| Pegatron                  | 3         | 0.45%   |
| Intel                     | 3         | 0.45%   |
| Google                    | 3         | 0.45%   |
| eMachines                 | 3         | 0.45%   |
| Jumper                    | 2         | 0.3%    |
| AMD                       | 2         | 0.3%    |
| YANYU                     | 1         | 0.15%   |
| Xunlong                   | 1         | 0.15%   |
| Wacom                     | 1         | 0.15%   |
| TriGem Computer           | 1         | 0.15%   |
| System76                  | 1         | 0.15%   |
| Shenzhen Bmorn Technology | 1         | 0.15%   |
| realme                    | 1         | 0.15%   |
| QTQD                      | 1         | 0.15%   |
| PERSONA                   | 1         | 0.15%   |
| Notebook                  | 1         | 0.15%   |
| Microsoft                 | 1         | 0.15%   |
| JOOYON                    | 1         | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 19        | 2.82%   |
| Valve Jupiter                       | 9         | 1.34%   |
| Gigabyte F2A68HM-S1                 | 6         | 0.89%   |
| Acer Aspire ES1-132                 | 6         | 0.89%   |
| MSI MS-7309                         | 5         | 0.74%   |
| Gigabyte A320M-S2H V2               | 5         | 0.74%   |
| ASUS All Series                     | 5         | 0.74%   |
| ASRock B450M Steel Legend           | 5         | 0.74%   |
| RPi Raspberry Pi                    | 4         | 0.59%   |
| MSI MS-7721                         | 4         | 0.59%   |
| ASUS P8H61-M LX3 PLUS R2.0          | 4         | 0.59%   |
| MSI Modern 14 B4MW                  | 3         | 0.45%   |
| HP Notebook                         | 3         | 0.45%   |
| Foxconn G31MX Series                | 3         | 0.45%   |
| ECS G41T-R3                         | 3         | 0.45%   |
| Clevo M7x0S                         | 3         | 0.45%   |
| Acer Aspire A315-51                 | 3         | 0.45%   |
| Pegatron IPMSB-H61                  | 2         | 0.3%    |
| MSI MS-7C94                         | 2         | 0.3%    |
| MSI MS-7C52                         | 2         | 0.3%    |
| Lenovo Yoga 520-14IKB 81C8          | 2         | 0.3%    |
| Lenovo V110-14IAP 80TF              | 2         | 0.3%    |
| Lenovo IdeaPad 330-15IKB 81DE       | 2         | 0.3%    |
| Lenovo IdeaPad 100-15IBY 80MJ       | 2         | 0.3%    |
| Lenovo IdeaPad 100-14IBY 80MH       | 2         | 0.3%    |
| Jumper EZbook                       | 2         | 0.3%    |
| HUAWEI KLVL-WXXW                    | 2         | 0.3%    |
| HP Pavilion Notebook                | 2         | 0.3%    |
| HP Pavilion Gaming Laptop 15-ec2xxx | 2         | 0.3%    |
| HP Pavilion Gaming Laptop 15-dk2xxx | 2         | 0.3%    |
| HP EliteBook 840 G6                 | 2         | 0.3%    |
| Gigabyte Z590 AORUS ULTRA           | 2         | 0.3%    |
| Gigabyte H97M-D3H                   | 2         | 0.3%    |
| Gigabyte H410M H V3                 | 2         | 0.3%    |
| Gigabyte B450 AORUS M               | 2         | 0.3%    |
| Gigabyte A320M-S2H                  | 2         | 0.3%    |
| Foxconn 500B Microtower             | 2         | 0.3%    |
| eMachines eM350                     | 2         | 0.3%    |
| Dell Vostro 5515                    | 2         | 0.3%    |
| Dell OptiPlex 9010 AIO              | 2         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Acer Aspire         | 52        | 7.72%   |
| Lenovo ThinkPad     | 42        | 6.23%   |
| Lenovo IdeaPad      | 34        | 5.04%   |
| Dell Inspiron       | 25        | 3.71%   |
| Unknown             | 19        | 2.82%   |
| HP Pavilion         | 17        | 2.52%   |
| Dell OptiPlex       | 11        | 1.63%   |
| ASUS VivoBook       | 11        | 1.63%   |
| ASUS ROG            | 11        | 1.63%   |
| Valve Jupiter       | 9         | 1.34%   |
| HP Laptop           | 9         | 1.34%   |
| Dell Latitude       | 9         | 1.34%   |
| ASUS TUF            | 9         | 1.34%   |
| Toshiba Satellite   | 8         | 1.19%   |
| HP EliteBook        | 8         | 1.19%   |
| HP Compaq           | 8         | 1.19%   |
| ASUS PRIME          | 8         | 1.19%   |
| Acer TravelMate     | 8         | 1.19%   |
| HP ProBook          | 7         | 1.04%   |
| Gigabyte A320M-S2H  | 7         | 1.04%   |
| RPi Raspberry       | 6         | 0.89%   |
| Gigabyte F2A68HM-S1 | 6         | 0.89%   |
| ASUS P8H61-M        | 6         | 0.89%   |
| MSI MS-7309         | 5         | 0.74%   |
| HP ProDesk          | 5         | 0.74%   |
| Dell XPS            | 5         | 0.74%   |
| ASUS All            | 5         | 0.74%   |
| ASRock B450M        | 5         | 0.74%   |
| Acer Nitro          | 5         | 0.74%   |
| MSI MS-7721         | 4         | 0.59%   |
| Lenovo Legion       | 4         | 0.59%   |
| Gigabyte B450       | 4         | 0.59%   |
| Dell Vostro         | 4         | 0.59%   |
| Acer Swift          | 4         | 0.59%   |
| MSI Modern          | 3         | 0.45%   |
| Lenovo Yoga         | 3         | 0.45%   |
| Lenovo ThinkCentre  | 3         | 0.45%   |
| HP Notebook         | 3         | 0.45%   |
| HP ENVY             | 3         | 0.45%   |
| Foxconn G31MX       | 3         | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 61        | 9.05%   |
| 2018    | 60        | 8.9%    |
| 2019    | 57        | 8.46%   |
| 2017    | 52        | 7.72%   |
| 2021    | 51        | 7.57%   |
| 2014    | 51        | 7.57%   |
| 2020    | 48        | 7.12%   |
| 2016    | 41        | 6.08%   |
| 2015    | 40        | 5.93%   |
| 2011    | 37        | 5.49%   |
| 2010    | 36        | 5.34%   |
| 2013    | 30        | 4.45%   |
| 2022    | 29        | 4.3%    |
| 2009    | 23        | 3.41%   |
| 2023    | 17        | 2.52%   |
| 2008    | 16        | 2.37%   |
| Unknown | 11        | 1.63%   |
| 2007    | 7         | 1.04%   |
| 2006    | 7         | 1.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 413       | 61.28%  |
| Desktop        | 226       | 33.53%  |
| Mini pc        | 10        | 1.48%   |
| System on chip | 8         | 1.19%   |
| Convertible    | 8         | 1.19%   |
| All in one     | 6         | 0.89%   |
| Tablet         | 3         | 0.45%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 608       | 89.54%  |
| Enabled  | 71        | 10.46%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 671       | 99.55%  |
| Yes  | 3         | 0.45%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 173       | 24.93%  |
| 8.01-16.0   | 145       | 20.89%  |
| 3.01-4.0    | 138       | 19.88%  |
| 16.01-24.0  | 107       | 15.42%  |
| 1.01-2.0    | 49        | 7.06%   |
| 32.01-64.0  | 48        | 6.92%   |
| 2.01-3.0    | 13        | 1.87%   |
| 64.01-256.0 | 10        | 1.44%   |
| 0.51-1.0    | 7         | 1.01%   |
| 24.01-32.0  | 4         | 0.58%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 237       | 31.18%  |
| 2.01-3.0    | 229       | 30.13%  |
| 4.01-8.0    | 109       | 14.34%  |
| 3.01-4.0    | 95        | 12.5%   |
| 0.51-1.0    | 46        | 6.05%   |
| 8.01-16.0   | 28        | 3.68%   |
| 0.01-0.5    | 10        | 1.32%   |
| 16.01-24.0  | 3         | 0.39%   |
| 24.01-32.0  | 1         | 0.13%   |
| 64.01-256.0 | 1         | 0.13%   |
| Unknown     | 1         | 0.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 427       | 60.83%  |
| 2      | 196       | 27.92%  |
| 3      | 36        | 5.13%   |
| 4      | 21        | 2.99%   |
| 5      | 8         | 1.14%   |
| 0      | 8         | 1.14%   |
| 6      | 3         | 0.43%   |
| 14     | 1         | 0.14%   |
| 13     | 1         | 0.14%   |
| 12     | 1         | 0.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 505       | 73.72%  |
| Yes       | 180       | 26.28%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 561       | 82.99%  |
| No        | 115       | 17.01%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 526       | 77.7%   |
| No        | 151       | 22.3%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 419       | 61.53%  |
| No        | 262       | 38.47%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Philippines | 674       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Quezon City         | 112       | 14.89%  |
| Cebu City           | 48        | 6.38%   |
| Davao City          | 40        | 5.32%   |
| Manila              | 39        | 5.19%   |
| Angeles City        | 29        | 3.86%   |
| Cagayan de Oro      | 25        | 3.32%   |
| Caloocan City       | 23        | 3.06%   |
| Makati City         | 22        | 2.93%   |
| Bacolod City        | 22        | 2.93%   |
| Paranaque City      | 19        | 2.53%   |
| Pasig               | 17        | 2.26%   |
| Lahug               | 16        | 2.13%   |
| Bacoor              | 16        | 2.13%   |
| Mandaluyong City    | 14        | 1.86%   |
| Tarlac City         | 12        | 1.6%    |
| San Miguel          | 12        | 1.6%    |
| Manajao             | 12        | 1.6%    |
| Imus                | 12        | 1.6%    |
| Iloilo City         | 12        | 1.6%    |
| Iligan City         | 12        | 1.6%    |
| Santa Rosa          | 10        | 1.33%   |
| San Jose del Monte  | 10        | 1.33%   |
| San Pablo City      | 8         | 1.06%   |
| San Fernando City   | 8         | 1.06%   |
| Calamba             | 8         | 1.06%   |
| San Juan            | 7         | 0.93%   |
| Las Pinas           | 7         | 0.93%   |
| Dasmarinas          | 7         | 0.93%   |
| Cabanatuan City     | 7         | 0.93%   |
| Zamboanga City      | 6         | 0.8%    |
| Lipa City           | 6         | 0.8%    |
| General Santos      | 6         | 0.8%    |
| Malolos             | 5         | 0.66%   |
| City of Muntinglupa | 5         | 0.66%   |
| Baguio City         | 5         | 0.66%   |
| Antipolo City       | 5         | 0.66%   |
| Tagbilaran          | 4         | 0.53%   |
| Marikina City       | 4         | 0.53%   |
| Lucena City         | 4         | 0.53%   |
| Legazpi             | 4         | 0.53%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 158       | 225    | 15.98%  |
| WDC                         | 136       | 170    | 13.75%  |
| Samsung Electronics         | 90        | 131    | 9.1%    |
| Toshiba                     | 86        | 113    | 8.7%    |
| Kingston                    | 60        | 73     | 6.07%   |
| SanDisk                     | 48        | 70     | 4.85%   |
| Unknown                     | 43        | 54     | 4.35%   |
| Hitachi                     | 34        | 55     | 3.44%   |
| SK hynix                    | 24        | 39     | 2.43%   |
| Intel                       | 19        | 23     | 1.92%   |
| HGST                        | 18        | 22     | 1.82%   |
| Ramsta                      | 16        | 17     | 1.62%   |
| Crucial                     | 14        | 17     | 1.42%   |
| A-DATA Technology           | 12        | 18     | 1.21%   |
| Phison Electronics          | 11        | 16     | 1.11%   |
| Micron Technology           | 11        | 17     | 1.11%   |
| Team                        | 10        | 14     | 1.01%   |
| China                       | 9         | 21     | 0.91%   |
| Transcend                   | 8         | 8      | 0.81%   |
| Lexar                       | 8         | 9      | 0.81%   |
| Kingston Technology Company | 8         | 9      | 0.81%   |
| PNY                         | 7         | 8      | 0.71%   |
| Phison                      | 7         | 7      | 0.71%   |
| Micron/Crucial Technology   | 7         | 13     | 0.71%   |
| Gigabyte Technology         | 7         | 12     | 0.71%   |
| Fujitsu                     | 7         | 9      | 0.71%   |
| Unknown                     | 7         | 8      | 0.71%   |
| Apple                       | 6         | 6      | 0.61%   |
| WALRAM                      | 5         | 6      | 0.51%   |
| Silicon Motion              | 5         | 6      | 0.51%   |
| KingSpec                    | 5         | 7      | 0.51%   |
| JMicron Technology          | 5         | 8      | 0.51%   |
| TAMMUZ                      | 4         | 8      | 0.4%    |
| Indilinx                    | 4         | 4      | 0.4%    |
| HS-SSD-C100                 | 4         | 5      | 0.4%    |
| SPCC                        | 3         | 4      | 0.3%    |
| LITEONIT                    | 3         | 5      | 0.3%    |
| HS-SSD-E100                 | 3         | 3      | 0.3%    |
| BR                          | 3         | 4      | 0.3%    |
| XPG                         | 2         | 2      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                          | 18        | 1.69%   |
| Seagate ST500DM002-1BD142 500GB                   | 15        | 1.41%   |
| Seagate ST1000LM035-1RK172 1TB                    | 15        | 1.41%   |
| Seagate ST1000DM010-2EP102 1TB                    | 15        | 1.41%   |
| Kingston SA400S37240G 240GB SSD                   | 12        | 1.13%   |
| Phison PS5013 E13 NVMe Controller 512GB           | 10        | 0.94%   |
| Kingston SA400S37120G 120GB SSD                   | 10        | 0.94%   |
| Unknown MMC Card  32GB                            | 9         | 0.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 9         | 0.85%   |
| Toshiba MQ04ABF100 1TB                            | 8         | 0.75%   |
| Toshiba MQ01ABD100 1TB                            | 8         | 0.75%   |
| Samsung SSD 860 EVO 500GB                         | 8         | 0.75%   |
| WDC WD5000LPCX-21VHAT0 500GB                      | 7         | 0.66%   |
| WDC WD10JPVX-22JC3T0 1TB                          | 7         | 0.66%   |
| Toshiba DT01ACA050 500GB                          | 7         | 0.66%   |
| Kingston SA400S37480G 480GB SSD                   | 7         | 0.66%   |
| Unknown                                           | 7         | 0.66%   |
| Unknown MMC Card  64GB                            | 6         | 0.56%   |
| Seagate ST500LT012-1DG142 500GB                   | 6         | 0.56%   |
| SanDisk SSD PLUS 1000GB                           | 6         | 0.56%   |
| Samsung SSD 860 EVO 250GB                         | 6         | 0.56%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 5         | 0.47%   |
| Unknown MMC Card  128GB                           | 5         | 0.47%   |
| Toshiba DT01ACA100 1TB                            | 5         | 0.47%   |
| Seagate ST500LT012-9WS142 500GB                   | 5         | 0.47%   |
| Seagate ST4000DM004-2CV104 4TB                    | 5         | 0.47%   |
| Seagate ST2000DM008-2FR102 2TB                    | 5         | 0.47%   |
| Seagate ST1000LM049-2GH172 1TB                    | 5         | 0.47%   |
| Hitachi HTS543232A7A384 320GB                     | 5         | 0.47%   |
| Hitachi HDS721050CLA362 500GB                     | 5         | 0.47%   |
| HGST HTS721010A9E630 1TB                          | 5         | 0.47%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 4         | 0.38%   |
| WDC WD5000LPCX-60VHAT0 500GB                      | 4         | 0.38%   |
| WDC WD5000LPCX-24VHAT0 500GB                      | 4         | 0.38%   |
| WDC WD10SPZX-21Z10T0 1TB                          | 4         | 0.38%   |
| Toshiba MK2555GSX 250GB                           | 4         | 0.38%   |
| Seagate ST500LM030-2E717D 500GB                   | 4         | 0.38%   |
| Seagate ST2000LM007-1R8174 2TB                    | 4         | 0.38%   |
| Seagate BUP Slim 2TB                              | 4         | 0.38%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB  | 4         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 156       | 221    | 36.45%  |
| WDC                 | 121       | 149    | 28.27%  |
| Toshiba             | 75        | 95     | 17.52%  |
| Hitachi             | 34        | 55     | 7.94%   |
| HGST                | 18        | 22     | 4.21%   |
| Fujitsu             | 7         | 9      | 1.64%   |
| Unknown             | 5         | 6      | 1.17%   |
| Samsung Electronics | 5         | 6      | 1.17%   |
| JMicron Technology  | 2         | 2      | 0.47%   |
| XrayDisk            | 1         | 1      | 0.23%   |
| Shenzhen            | 1         | 1      | 0.23%   |
| SAGE                | 1         | 1      | 0.23%   |
| HGST HTS            | 1         | 1      | 0.23%   |
| ExcelStor           | 1         | 1      | 0.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 47        | 54     | 16.1%   |
| Samsung Electronics | 39        | 56     | 13.36%  |
| SanDisk             | 26        | 33     | 8.9%    |
| Ramsta              | 14        | 15     | 4.79%   |
| WDC                 | 13        | 16     | 4.45%   |
| Team                | 10        | 14     | 3.42%   |
| Crucial             | 9         | 11     | 3.08%   |
| China               | 9         | 21     | 3.08%   |
| A-DATA Technology   | 9         | 14     | 3.08%   |
| Transcend           | 7         | 7      | 2.4%    |
| Toshiba             | 7         | 10     | 2.4%    |
| SK hynix            | 7         | 19     | 2.4%    |
| Lexar               | 6         | 7      | 2.05%   |
| PNY                 | 5         | 6      | 1.71%   |
| Micron Technology   | 5         | 5      | 1.71%   |
| KingSpec            | 5         | 7      | 1.71%   |
| Intel               | 5         | 6      | 1.71%   |
| Apple               | 5         | 5      | 1.71%   |
| TAMMUZ              | 4         | 8      | 1.37%   |
| Gigabyte Technology | 4         | 5      | 1.37%   |
| LITEONIT            | 3         | 5      | 1.03%   |
| HS-SSD-E100         | 3         | 3      | 1.03%   |
| WALRAM              | 2         | 2      | 0.68%   |
| USB3.0              | 2         | 2      | 0.68%   |
| SPCC                | 2         | 2      | 0.68%   |
| Patriot             | 2         | 2      | 0.68%   |
| Netac               | 2         | 2      | 0.68%   |
| Kingmax             | 2         | 2      | 0.68%   |
| Indilinx            | 2         | 2      | 0.68%   |
| HS-SSD-C100         | 2         | 2      | 0.68%   |
| Hikvision           | 2         | 3      | 0.68%   |
| ETOPSO              | 2         | 2      | 0.68%   |
| CERVVO              | 2         | 2      | 0.68%   |
| BR                  | 2         | 2      | 0.68%   |
| ZOTAC               | 1         | 1      | 0.34%   |
| Vaseky              | 1         | 2      | 0.34%   |
| Unknown             | 1         | 2      | 0.34%   |
| Teclast             | 1         | 4      | 0.34%   |
| SKIHOTAR            | 1         | 1      | 0.34%   |
| ShiJi               | 1         | 1      | 0.34%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 376       | 570    | 42.58%  |
| SSD     | 252       | 388    | 28.54%  |
| NVMe    | 191       | 292    | 21.63%  |
| MMC     | 40        | 49     | 4.53%   |
| Unknown | 24        | 33     | 2.72%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 529       | 938    | 65.96%  |
| NVMe | 191       | 290    | 23.82%  |
| SAS  | 42        | 55     | 5.24%   |
| MMC  | 40        | 49     | 4.99%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 422       | 656    | 67.2%   |
| 0.51-1.0   | 159       | 231    | 25.32%  |
| 1.01-2.0   | 32        | 44     | 5.1%    |
| 3.01-4.0   | 10        | 22     | 1.59%   |
| 10.01-20.0 | 3         | 3      | 0.48%   |
| 4.01-10.0  | 2         | 2      | 0.32%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 199       | 27.52%  |
| 251-500        | 182       | 25.17%  |
| 501-1000       | 96        | 13.28%  |
| 1001-2000      | 68        | 9.41%   |
| 1-20           | 53        | 7.33%   |
| 51-100         | 49        | 6.78%   |
| 21-50          | 26        | 3.6%    |
| More than 3000 | 21        | 2.9%    |
| 2001-3000      | 15        | 2.07%   |
| Unknown        | 14        | 1.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 274       | 36.2%   |
| 21-50          | 155       | 20.48%  |
| 51-100         | 104       | 13.74%  |
| 101-250        | 96        | 12.68%  |
| 251-500        | 53        | 7%      |
| 501-1000       | 32        | 4.23%   |
| Unknown        | 14        | 1.85%   |
| 1001-2000      | 13        | 1.72%   |
| 2001-3000      | 9         | 1.19%   |
| More than 3000 | 7         | 0.92%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Hitachi HDS721050CLA362 500GB         | 5         | 10     | 7.58%   |
| Hitachi HTS543232A7A384 320GB         | 3         | 5      | 4.55%   |
| Unknown S050 Hard drive 500GB         | 2         | 2      | 3.03%   |
| Toshiba MQ01ABF050 500GB              | 2         | 2      | 3.03%   |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 3.03%   |
| Seagate ST2000LM007-1R8174 2TB        | 2         | 3      | 3.03%   |
| Seagate ST1000LM048-2E7172 1TB        | 2         | 2      | 3.03%   |
| HGST HTS541010A9E680 1TB              | 2         | 3      | 3.03%   |
| WDC WD5003ABYZ-011FA0 500GB           | 1         | 1      | 1.52%   |
| WDC WD5000LPVT-75G33T0 500GB          | 1         | 1      | 1.52%   |
| WDC WD5000LPVT-22G33T0 500GB          | 1         | 1      | 1.52%   |
| WDC WD5000LPCX-60VHAT0 500GB          | 1         | 2      | 1.52%   |
| WDC WD5000AAVS-00ZTB0 500GB           | 1         | 1      | 1.52%   |
| WDC WD5000AAKX-603CA0 500GB           | 1         | 1      | 1.52%   |
| WDC WD3200BEVT-22A23T0 320GB          | 1         | 1      | 1.52%   |
| WDC WD3200AAJS-08L7A0 320GB           | 1         | 1      | 1.52%   |
| WDC WD1600BEVT-24A23T0 160GB          | 1         | 1      | 1.52%   |
| WDC WD10JPVX-60JC3T1 1TB              | 1         | 2      | 1.52%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 1      | 1.52%   |
| WDC WD10EZEX-00MFCA0 1TB              | 1         | 1      | 1.52%   |
| Toshiba MK6465GSX 640GB               | 1         | 1      | 1.52%   |
| Toshiba MK3259GSXP 320GB              | 1         | 1      | 1.52%   |
| Toshiba MK2555GSX 250GB               | 1         | 1      | 1.52%   |
| Toshiba DT01ACA100 1TB                | 1         | 1      | 1.52%   |
| Toshiba DT01ACA050 500GB              | 1         | 1      | 1.52%   |
| SK hynix HFS128G3AMNB-2200A 128GB SSD | 1         | 1      | 1.52%   |
| Seagate ST9250315AS 250GB             | 1         | 1      | 1.52%   |
| Seagate ST9120821AS 120GB             | 1         | 1      | 1.52%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 1.52%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1      | 1.52%   |
| Seagate ST500DM002-1BD142 500GB       | 1         | 2      | 1.52%   |
| Seagate ST500DM002 500GB              | 1         | 2      | 1.52%   |
| Seagate ST380815AS 80GB               | 1         | 1      | 1.52%   |
| Seagate ST3500514NS 500GB             | 1         | 1      | 1.52%   |
| Seagate ST3500418AS 500GB             | 1         | 1      | 1.52%   |
| Seagate ST2000DM008-2FR102 2TB        | 1         | 1      | 1.52%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 1.52%   |
| Seagate ST1000DM010-2EP102 1TB        | 1         | 1      | 1.52%   |
| SanDisk SSD PLUS 1000GB               | 1         | 1      | 1.52%   |
| SanDisk SDSSDA240G 240GB              | 1         | 1      | 1.52%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 19     | 25.81%  |
| WDC                 | 12        | 14     | 19.35%  |
| Hitachi             | 10        | 22     | 16.13%  |
| Toshiba             | 8         | 9      | 12.9%   |
| HGST                | 3         | 4      | 4.84%   |
| Unknown             | 2         | 2      | 3.23%   |
| SanDisk             | 2         | 2      | 3.23%   |
| Kingston            | 2         | 2      | 3.23%   |
| SK hynix            | 1         | 1      | 1.61%   |
| Samsung Electronics | 1         | 2      | 1.61%   |
| Ramsta              | 1         | 1      | 1.61%   |
| Micron Technology   | 1         | 1      | 1.61%   |
| Fujitsu             | 1         | 1      | 1.61%   |
| Colorful            | 1         | 1      | 1.61%   |
| A-DATA Technology   | 1         | 1      | 1.61%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 16        | 19     | 30.77%  |
| WDC     | 12        | 14     | 23.08%  |
| Hitachi | 10        | 22     | 19.23%  |
| Toshiba | 8         | 9      | 15.38%  |
| HGST    | 3         | 4      | 5.77%   |
| Unknown | 2         | 2      | 3.85%   |
| Fujitsu | 1         | 1      | 1.92%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 47        | 71     | 82.46%  |
| SSD  | 8         | 8      | 14.04%  |
| NVMe | 2         | 3      | 3.51%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD10SPZX-21Z10T0 1TB        | 1         | 1      | 50%     |
| Seagate ST500DM002-1BD142 500GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 427       | 831    | 58.41%  |
| Works    | 247       | 417    | 33.79%  |
| Malfunc  | 55        | 82     | 7.52%   |
| Failed   | 2         | 2      | 0.27%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 443       | 55.17%  |
| AMD                              | 140       | 17.43%  |
| Samsung Electronics              | 50        | 6.23%   |
| SanDisk                          | 23        | 2.86%   |
| Phison Electronics               | 20        | 2.49%   |
| Kingston Technology Company      | 20        | 2.49%   |
| SK hynix                         | 17        | 2.12%   |
| Nvidia                           | 17        | 2.12%   |
| Micron/Crucial Technology        | 11        | 1.37%   |
| Silicon Motion                   | 8         | 1%      |
| Toshiba America Info Systems     | 6         | 0.75%   |
| Micron Technology                | 6         | 0.75%   |
| ADATA Technology                 | 5         | 0.62%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.5%    |
| Lite-On Technology               | 4         | 0.5%    |
| Solid State Storage Technology   | 3         | 0.37%   |
| Silicon Integrated Systems [SiS] | 3         | 0.37%   |
| Marvell Technology Group         | 3         | 0.37%   |
| JMicron Technology               | 3         | 0.37%   |
| ASMedia Technology               | 3         | 0.37%   |
| Union Memory (Shenzhen)          | 2         | 0.25%   |
| Shenzhen Longsys Electronics     | 2         | 0.25%   |
| Realtek Semiconductor            | 2         | 0.25%   |
| O2 Micro                         | 2         | 0.25%   |
| KIOXIA                           | 2         | 0.25%   |
| Lenovo                           | 1         | 0.12%   |
| Broadcom / LSI                   | 1         | 0.12%   |
| Biwin Storage Technology         | 1         | 0.12%   |
| Apple                            | 1         | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 95        | 10.05%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 43        | 4.55%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 38        | 4.02%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 31        | 3.28%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 24        | 2.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 21        | 2.22%   |
| AMD 400 Series Chipset SATA Controller                                                  | 21        | 2.22%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 19        | 2.01%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 18        | 1.9%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 18        | 1.9%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 18        | 1.9%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 17        | 1.8%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 16        | 1.69%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 16        | 1.69%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 13        | 1.38%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 13        | 1.38%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 12        | 1.27%   |
| AMD 500 Series Chipset SATA Controller                                                  | 12        | 1.27%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 11        | 1.16%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 11        | 1.16%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 11        | 1.16%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 11        | 1.16%   |
| AMD FCH SATA Controller D                                                               | 11        | 1.16%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 10        | 1.06%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 10        | 1.06%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 10        | 1.06%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 10        | 1.06%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 10        | 1.06%   |
| Nvidia MCP61 SATA Controller                                                            | 9         | 0.95%   |
| Nvidia MCP61 IDE                                                                        | 9         | 0.95%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 9         | 0.95%   |
| Intel SSD 670p Series [Keystone Harbor]                                                 | 9         | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 9         | 0.95%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 8         | 0.85%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 8         | 0.85%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 8         | 0.85%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 8         | 0.85%   |
| AMD FCH IDE Controller                                                                  | 8         | 0.85%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 7         | 0.74%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 7         | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 498       | 59.86%  |
| NVMe | 191       | 22.96%  |
| IDE  | 84        | 10.1%   |
| RAID | 58        | 6.97%   |
| SAS  | 1         | 0.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 482       | 71.51%  |
| AMD     | 181       | 26.85%  |
| ARM     | 10        | 1.48%   |
| Unknown | 1         | 0.15%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 10        | 1.48%   |
| AMD Ryzen 5 3600 6-Core Processor             | 10        | 1.48%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 1.34%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 9         | 1.34%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 9         | 1.34%   |
| AMD Custom APU 0405                           | 9         | 1.34%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 8         | 1.19%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 8         | 1.19%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 7         | 1.04%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 7         | 1.04%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 0.89%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 6         | 0.89%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 6         | 0.89%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 6         | 0.89%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 6         | 0.89%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 0.74%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 5         | 0.74%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 0.74%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 5         | 0.74%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 0.74%   |
| ARM Processor                                 | 5         | 0.74%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 5         | 0.74%   |
| AMD A6-6400K APU with Radeon HD Graphics      | 5         | 0.74%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 0.59%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 4         | 0.59%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 4         | 0.59%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 0.59%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 4         | 0.59%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 0.59%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 4         | 0.59%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 4         | 0.59%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 4         | 0.59%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 0.59%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 4         | 0.59%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 4         | 0.59%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 4         | 0.59%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 4         | 0.59%   |
| AMD Sempron Processor LE-1100                 | 4         | 0.59%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 4         | 0.59%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 4         | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 157       | 23.29%  |
| Intel Core i7           | 90        | 13.35%  |
| Intel Core i3           | 61        | 9.05%   |
| Other                   | 58        | 8.61%   |
| AMD Ryzen 5             | 51        | 7.57%   |
| Intel Celeron           | 50        | 7.42%   |
| Intel Core 2 Duo        | 26        | 3.86%   |
| AMD Ryzen 7             | 20        | 2.97%   |
| AMD Ryzen 3             | 20        | 2.97%   |
| AMD A6                  | 16        | 2.37%   |
| Intel Pentium           | 15        | 2.23%   |
| Intel Atom              | 12        | 1.78%   |
| Intel Pentium Dual-Core | 9         | 1.34%   |
| AMD A8                  | 9         | 1.34%   |
| AMD A10                 | 7         | 1.04%   |
| AMD Athlon              | 6         | 0.89%   |
| Intel Pentium Silver    | 5         | 0.74%   |
| Intel Core 2 Quad       | 5         | 0.74%   |
| AMD FX                  | 5         | 0.74%   |
| AMD A4                  | 5         | 0.74%   |
| AMD Sempron             | 4         | 0.59%   |
| AMD Ryzen 9             | 4         | 0.59%   |
| AMD Phenom II X4        | 3         | 0.45%   |
| AMD Athlon II X2        | 3         | 0.45%   |
| Intel Pentium Gold      | 2         | 0.3%    |
| Intel Genuine           | 2         | 0.3%    |
| Intel Core m3           | 2         | 0.3%    |
| Intel Core 2            | 2         | 0.3%    |
| AMD Turion 64 X2 Mobile | 2         | 0.3%    |
| AMD Ryzen 7 PRO         | 2         | 0.3%    |
| Intel Xeon              | 1         | 0.15%   |
| Intel Pentium Dual      | 1         | 0.15%   |
| Intel Core m5           | 1         | 0.15%   |
| Intel Core i9           | 1         | 0.15%   |
| Intel Celeron M         | 1         | 0.15%   |
| ARM BCM                 | 1         | 0.15%   |
| ARM Allwinner           | 1         | 0.15%   |
| AMD Turion 64 Mobile    | 1         | 0.15%   |
| AMD Ryzen 5 PRO         | 1         | 0.15%   |
| AMD Quad-Core           | 1         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 279       | 41.39%  |
| 4      | 251       | 37.24%  |
| 6      | 72        | 10.68%  |
| 1      | 30        | 4.45%   |
| 8      | 28        | 4.15%   |
| 14     | 4         | 0.59%   |
| 10     | 4         | 0.59%   |
| 16     | 2         | 0.3%    |
| 12     | 2         | 0.3%    |
| 24     | 1         | 0.15%   |
| 3      | 1         | 0.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 672       | 99.7%   |
| 3      | 1         | 0.15%   |
| 2      | 1         | 0.15%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 447       | 66.22%  |
| 1      | 228       | 33.78%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 656       | 96.9%   |
| Unknown        | 16        | 2.36%   |
| 32-bit         | 4         | 0.59%   |
| 64-bit         | 1         | 0.15%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 267       | 38.14%  |
| 0x306a9    | 36        | 5.14%   |
| 0x206a7    | 24        | 3.43%   |
| 0x1067a    | 23        | 3.29%   |
| 0x306c3    | 19        | 2.71%   |
| 0x806ea    | 14        | 2%      |
| 0x506c9    | 14        | 2%      |
| 0x406e3    | 14        | 2%      |
| 0x906ea    | 12        | 1.71%   |
| 0x806ec    | 11        | 1.57%   |
| 0x806e9    | 10        | 1.43%   |
| 0x30678    | 10        | 1.43%   |
| 0x08701021 | 10        | 1.43%   |
| 0x06001119 | 10        | 1.43%   |
| 0x906e9    | 9         | 1.29%   |
| 0x306d4    | 9         | 1.29%   |
| 0x10676    | 9         | 1.29%   |
| 0x06003106 | 9         | 1.29%   |
| 0x40651    | 8         | 1.14%   |
| 0x0a50000c | 8         | 1.14%   |
| 0x08108109 | 8         | 1.14%   |
| 0x806c1    | 7         | 1%      |
| 0x506e3    | 7         | 1%      |
| 0x0a50000d | 7         | 1%      |
| 0x0800820d | 7         | 1%      |
| 0x706a1    | 6         | 0.86%   |
| 0x08600106 | 6         | 0.86%   |
| 0x706e5    | 5         | 0.71%   |
| 0x406c4    | 5         | 0.71%   |
| 0x20655    | 5         | 0.71%   |
| 0x106ca    | 5         | 0.71%   |
| 0xa0671    | 4         | 0.57%   |
| 0xa0652    | 4         | 0.57%   |
| 0x806eb    | 4         | 0.57%   |
| 0x08608103 | 4         | 0.57%   |
| 0x08600104 | 4         | 0.57%   |
| 0x0810100b | 4         | 0.57%   |
| 0x0600611a | 4         | 0.57%   |
| 0x906a4    | 3         | 0.43%   |
| 0x706a8    | 3         | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 108       | 15.93%  |
| IvyBridge        | 60        | 8.85%   |
| Haswell          | 41        | 6.05%   |
| Unknown          | 41        | 6.05%   |
| Penryn           | 39        | 5.75%   |
| SandyBridge      | 35        | 5.16%   |
| Skylake          | 34        | 5.01%   |
| Zen+             | 26        | 3.83%   |
| Zen 2            | 26        | 3.83%   |
| Zen 3            | 24        | 3.54%   |
| Silvermont       | 22        | 3.24%   |
| Piledriver       | 21        | 3.1%    |
| TigerLake        | 18        | 2.65%   |
| Broadwell        | 18        | 2.65%   |
| Goldmont         | 17        | 2.51%   |
| CometLake        | 17        | 2.51%   |
| Zen              | 13        | 1.92%   |
| Goldmont plus    | 12        | 1.77%   |
| Alderlake Hybrid | 12        | 1.77%   |
| Westmere         | 11        | 1.62%   |
| Steamroller      | 10        | 1.47%   |
| K8 Hammer        | 9         | 1.33%   |
| Icelake          | 9         | 1.33%   |
| Bonnell          | 9         | 1.33%   |
| K10              | 8         | 1.18%   |
| Excavator        | 8         | 1.18%   |
| Core             | 6         | 0.88%   |
| Puma             | 5         | 0.74%   |
| Tremont          | 3         | 0.44%   |
| P6               | 3         | 0.44%   |
| Jaguar           | 3         | 0.44%   |
| Bobcat           | 3         | 0.44%   |
| Nehalem          | 2         | 0.29%   |
| K10 Llano        | 2         | 0.29%   |
| K8 & K10 hybrid  | 1         | 0.15%   |
| Gracemont        | 1         | 0.15%   |
| Bulldozer        | 1         | 0.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 420       | 51.72%  |
| AMD                              | 195       | 24.01%  |
| Nvidia                           | 194       | 23.89%  |
| Silicon Integrated Systems [SiS] | 3         | 0.37%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 43        | 5.15%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 33        | 3.95%   |
| Intel UHD Graphics 620                                                                   | 24        | 2.87%   |
| Intel HD Graphics 620                                                                    | 18        | 2.16%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 18        | 2.16%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 17        | 2.04%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 16        | 1.92%   |
| Intel HD Graphics 630                                                                    | 15        | 1.8%    |
| Intel HD Graphics 5500                                                                   | 15        | 1.8%    |
| Intel HD Graphics 500                                                                    | 15        | 1.8%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 14        | 1.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 13        | 1.56%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 12        | 1.44%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 11        | 1.32%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 11        | 1.32%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 11        | 1.32%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 10        | 1.2%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 10        | 1.2%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 1.2%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 10        | 1.2%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 9         | 1.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9         | 1.08%   |
| Intel HD Graphics 530                                                                    | 9         | 1.08%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 1.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 1.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 1.08%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 9         | 1.08%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 8         | 0.96%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 0.96%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 8         | 0.96%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 7         | 0.84%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 7         | 0.84%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 7         | 0.84%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7         | 0.84%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 0.84%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 7         | 0.84%   |
| Nvidia GM108M [GeForce MX130]                                                            | 6         | 0.72%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 6         | 0.72%   |
| Nvidia G72 [GeForce 7200 GS / 7300 SE]                                                   | 6         | 0.72%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 6         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 290       | 42.34%  |
| 1 x AMD        | 146       | 21.31%  |
| Intel + Nvidia | 93        | 13.58%  |
| 1 x Nvidia     | 88        | 12.85%  |
| Intel + AMD    | 26        | 3.8%    |
| 2 x AMD        | 12        | 1.75%   |
| AMD + Nvidia   | 12        | 1.75%   |
| Other          | 11        | 1.61%   |
| 1 x SiS        | 3         | 0.44%   |
| 2 x Nvidia     | 2         | 0.29%   |
| 2 x Intel      | 2         | 0.29%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 542       | 79.47%  |
| Proprietary | 112       | 16.42%  |
| Unknown     | 28        | 4.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 438       | 62.75%  |
| 1.01-2.0   | 83        | 11.89%  |
| 0.01-0.5   | 63        | 9.03%   |
| 0.51-1.0   | 38        | 5.44%   |
| 3.01-4.0   | 35        | 5.01%   |
| 7.01-8.0   | 19        | 2.72%   |
| 5.01-6.0   | 12        | 1.72%   |
| 8.01-16.0  | 8         | 1.15%   |
| 2.01-3.0   | 2         | 0.29%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 79        | 11.05%  |
| Chimei Innolux          | 79        | 11.05%  |
| BOE                     | 78        | 10.91%  |
| AU Optronics            | 75        | 10.49%  |
| LG Display              | 60        | 8.39%   |
| Dell                    | 36        | 5.03%   |
| AOC                     | 26        | 3.64%   |
| Acer                    | 24        | 3.36%   |
| Lenovo                  | 22        | 3.08%   |
| Goldstar                | 16        | 2.24%   |
| Hewlett-Packard         | 14        | 1.96%   |
| Philips                 | 13        | 1.82%   |
| ASUSTek Computer        | 12        | 1.68%   |
| InfoVision              | 11        | 1.54%   |
| BenQ                    | 11        | 1.54%   |
| Sony                    | 10        | 1.4%    |
| Sharp                   | 10        | 1.4%    |
| Valve                   | 9         | 1.26%   |
| Apple                   | 9         | 1.26%   |
| Ancor Communications    | 9         | 1.26%   |
| IPS                     | 7         | 0.98%   |
| PANDA                   | 6         | 0.84%   |
| Unknown                 | 6         | 0.84%   |
| Chi Mei Optoelectronics | 5         | 0.7%    |
| ViewSonic               | 4         | 0.56%   |
| Unknown                 | 4         | 0.56%   |
| Mi                      | 4         | 0.56%   |
| RTK                     | 3         | 0.42%   |
| MStar                   | 3         | 0.42%   |
| MSI                     | 3         | 0.42%   |
| InnoLux Display         | 3         | 0.42%   |
| VIE                     | 2         | 0.28%   |
| Unknown (XXX)           | 2         | 0.28%   |
| TMX                     | 2         | 0.28%   |
| SGT                     | 2         | 0.28%   |
| Pixio                   | 2         | 0.28%   |
| MDA                     | 2         | 0.28%   |
| LG Philips              | 2         | 0.28%   |
| HKC                     | 2         | 0.28%   |
| Gigabyte Technology     | 2         | 0.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch               | 9         | 1.23%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch   | 7         | 0.96%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                    | 7         | 0.96%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch     | 6         | 0.82%   |
| Unknown                                                           | 6         | 0.82%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch | 5         | 0.68%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch | 5         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch  | 5         | 0.68%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch  | 4         | 0.55%   |
| Dell SE177FP DELF001 1280x1024 338x270mm 17.0-inch                | 4         | 0.55%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch   | 4         | 0.55%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch   | 4         | 0.55%   |
| Chimei Innolux LCD Monitor CMN1480 1366x768 309x174mm 14.0-inch   | 4         | 0.55%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch             | 4         | 0.55%   |
| AOC 2060W3 AOC2060 1920x1080 435x239mm 19.5-inch                  | 4         | 0.55%   |
| Samsung Electronics S22R35x SAM103A 1920x1080 476x268mm 21.5-inch | 3         | 0.41%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch  | 3         | 0.41%   |
| Philips PHL 227E7 PHLC100 1920x1080 476x268mm 21.5-inch           | 3         | 0.41%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                    | 3         | 0.41%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch      | 3         | 0.41%   |
| LG Display LCD Monitor LGD033F 1366x768 309x174mm 14.0-inch       | 3         | 0.41%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch           | 3         | 0.41%   |
| Lenovo LCD Monitor LEN40A0 1366x768 309x174mm 14.0-inch           | 3         | 0.41%   |
| Lenovo L1951p Wide LEN0990 1440x900 408x255mm 18.9-inch           | 3         | 0.41%   |
| Dell P170S DEL4058 1280x1024 338x270mm 17.0-inch                  | 3         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch  | 3         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch   | 3         | 0.41%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch  | 3         | 0.41%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch             | 3         | 0.41%   |
| BOE LCD Monitor BOE06BD 1366x768 309x173mm 13.9-inch              | 3         | 0.41%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch              | 3         | 0.41%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch    | 3         | 0.41%   |
| AU Optronics LCD Monitor AUO2992 1920x1080 344x193mm 15.5-inch    | 3         | 0.41%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch    | 3         | 0.41%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch     | 3         | 0.41%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch              | 3         | 0.41%   |
| AOC 1670W AOC1670 1366x768 344x194mm 15.5-inch                    | 3         | 0.41%   |
| VIE A/G1956 VIE1850 1366x768 414x257mm 19.2-inch                  | 2         | 0.27%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch         | 2         | 0.27%   |
| Sony TV SNYAB03 1920x1080                                         | 2         | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 269       | 39.68%  |
| 1366x768 (WXGA)    | 216       | 31.86%  |
| 1600x900 (HD+)     | 29        | 4.28%   |
| 3840x2160 (4K)     | 26        | 3.83%   |
| 1280x1024 (SXGA)   | 24        | 3.54%   |
| 2560x1440 (QHD)    | 17        | 2.51%   |
| 1440x900 (WXGA+)   | 14        | 2.06%   |
| 1920x1200 (WUXGA)  | 11        | 1.62%   |
| 800x1280           | 9         | 1.33%   |
| 1280x800 (WXGA)    | 7         | 1.03%   |
| 1024x600           | 7         | 1.03%   |
| 2560x1600          | 6         | 0.88%   |
| 2160x1440          | 6         | 0.88%   |
| 1680x1050 (WSXGA+) | 6         | 0.88%   |
| 1360x768           | 6         | 0.88%   |
| 3440x1440          | 5         | 0.74%   |
| 1920x540           | 3         | 0.44%   |
| 1024x768 (XGA)     | 3         | 0.44%   |
| 2560x1080          | 2         | 0.29%   |
| 2288x1287          | 2         | 0.29%   |
| Unknown            | 2         | 0.29%   |
| 3840x2400          | 1         | 0.15%   |
| 3200x1080          | 1         | 0.15%   |
| 3000x2000          | 1         | 0.15%   |
| 2966x900           | 1         | 0.15%   |
| 2880x1800          | 1         | 0.15%   |
| 2400x1600          | 1         | 0.15%   |
| 1600x1200          | 1         | 0.15%   |
| 1280x768           | 1         | 0.15%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 165       | 22.98%  |
| 13      | 84        | 11.7%   |
| 14      | 78        | 10.86%  |
| 21      | 46        | 6.41%   |
| 23      | 41        | 5.71%   |
| 18      | 40        | 5.57%   |
| 17      | 36        | 5.01%   |
| 27      | 31        | 4.32%   |
| 24      | 25        | 3.48%   |
| 11      | 21        | 2.92%   |
| Unknown | 21        | 2.92%   |
| 20      | 18        | 2.51%   |
| 19      | 17        | 2.37%   |
| 12      | 15        | 2.09%   |
| 31      | 11        | 1.53%   |
| 72      | 9         | 1.25%   |
| 7       | 9         | 1.25%   |
| 34      | 7         | 0.97%   |
| 32      | 7         | 0.97%   |
| 10      | 7         | 0.97%   |
| 16      | 6         | 0.84%   |
| 52      | 5         | 0.7%    |
| 22      | 5         | 0.7%    |
| 54      | 4         | 0.56%   |
| 142     | 2         | 0.28%   |
| 84      | 2         | 0.28%   |
| 40      | 2         | 0.28%   |
| 58      | 1         | 0.14%   |
| 50      | 1         | 0.14%   |
| 39      | 1         | 0.14%   |
| 8       | 1         | 0.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 313       | 44.46%  |
| 401-500        | 117       | 16.62%  |
| 501-600        | 86        | 12.22%  |
| 201-300        | 74        | 10.51%  |
| 351-400        | 26        | 3.69%   |
| Unknown        | 21        | 2.98%   |
| 601-700        | 16        | 2.27%   |
| 701-800        | 14        | 1.99%   |
| 1501-2000      | 11        | 1.56%   |
| 1001-1500      | 11        | 1.56%   |
| 1-100          | 9         | 1.28%   |
| 801-900        | 3         | 0.43%   |
| More than 2000 | 2         | 0.28%   |
| 101-200        | 1         | 0.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 535       | 82.31%  |
| 16/10   | 45        | 6.92%   |
| 5/4     | 21        | 3.23%   |
| Unknown | 19        | 2.92%   |
| 0.67    | 9         | 1.38%   |
| 3/2     | 7         | 1.08%   |
| 21/9    | 7         | 1.08%   |
| 4/3     | 4         | 0.62%   |
| 1.00    | 2         | 0.31%   |
| 0.62    | 1         | 0.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 161       | 22.74%  |
| 81-90          | 140       | 19.77%  |
| 201-250        | 85        | 12.01%  |
| 151-200        | 55        | 7.77%   |
| 141-150        | 54        | 7.63%   |
| 301-350        | 31        | 4.38%   |
| 351-500        | 25        | 3.53%   |
| More than 1000 | 24        | 3.39%   |
| 71-80          | 22        | 3.11%   |
| 51-60          | 21        | 2.97%   |
| Unknown        | 21        | 2.97%   |
| 121-130        | 18        | 2.54%   |
| 61-70          | 15        | 2.12%   |
| 1-40           | 10        | 1.41%   |
| 41-50          | 7         | 0.99%   |
| 111-120        | 7         | 0.99%   |
| 251-300        | 5         | 0.71%   |
| 501-1000       | 3         | 0.42%   |
| 91-100         | 3         | 0.42%   |
| 131-140        | 1         | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 236       | 34.1%   |
| 121-160       | 186       | 26.88%  |
| 51-100        | 183       | 26.45%  |
| 161-240       | 33        | 4.77%   |
| 1-50          | 24        | 3.47%   |
| Unknown       | 21        | 3.03%   |
| More than 240 | 9         | 1.3%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 559       | 80.9%   |
| 2     | 96        | 13.89%  |
| 0     | 30        | 4.34%   |
| 3     | 6         | 0.87%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 422       | 41.91%  |
| Intel                                 | 258       | 25.62%  |
| Qualcomm Atheros                      | 124       | 12.31%  |
| Broadcom                              | 57        | 5.66%   |
| Ralink Technology                     | 27        | 2.68%   |
| TP-Link                               | 15        | 1.49%   |
| MediaTek                              | 15        | 1.49%   |
| Nvidia                                | 12        | 1.19%   |
| Broadcom Limited                      | 8         | 0.79%   |
| Samsung Electronics                   | 7         | 0.7%    |
| Ralink                                | 7         | 0.7%    |
| JMicron Technology                    | 5         | 0.5%    |
| ASIX Electronics                      | 5         | 0.5%    |
| Qualcomm Atheros Communications       | 4         | 0.4%    |
| OPPO Electronics                      | 4         | 0.4%    |
| Marvell Technology Group              | 4         | 0.4%    |
| Xiaomi                                | 3         | 0.3%    |
| Silicon Integrated Systems [SiS]      | 3         | 0.3%    |
| Huawei Technologies                   | 3         | 0.3%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.3%    |
| Qualcomm                              | 2         | 0.2%    |
| ICS Advent                            | 2         | 0.2%    |
| DisplayLink                           | 2         | 0.2%    |
| D-Link                                | 2         | 0.2%    |
| Apple                                 | 2         | 0.2%    |
| Tenda                                 | 1         | 0.1%    |
| Sundance Technology Inc / IC Plus     | 1         | 0.1%    |
| NetGear                               | 1         | 0.1%    |
| Microchip Technology                  | 1         | 0.1%    |
| Hewlett-Packard                       | 1         | 0.1%    |
| Encore Electronics                    | 1         | 0.1%    |
| Dell                                  | 1         | 0.1%    |
| D-Link System                         | 1         | 0.1%    |
| BUFFALO                               | 1         | 0.1%    |
| ASUSTek Computer                      | 1         | 0.1%    |
| AMD                                   | 1         | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 297       | 25.54%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 51        | 4.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 25        | 2.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 24        | 2.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 23        | 1.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 20        | 1.72%   |
| Intel Wireless 7265                                                    | 20        | 1.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 18        | 1.55%   |
| Ralink MT7601U Wireless Adapter                                        | 17        | 1.46%   |
| Intel Wi-Fi 6 AX200                                                    | 17        | 1.46%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 16        | 1.38%   |
| Realtek RTL8125 2.5GbE Controller                                      | 15        | 1.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 15        | 1.29%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 14        | 1.2%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 14        | 1.2%    |
| Intel Wireless 3165                                                    | 14        | 1.2%    |
| Realtek 802.11ac NIC                                                   | 12        | 1.03%   |
| Intel Wi-Fi 6 AX201                                                    | 12        | 1.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 11        | 0.95%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 11        | 0.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 11        | 0.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 10        | 0.86%   |
| Intel Wireless 8265 / 8275                                             | 10        | 0.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 10        | 0.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 10        | 0.86%   |
| Broadcom BCM43142 802.11b/g/n                                          | 10        | 0.86%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 9         | 0.77%   |
| Intel Wireless 8260                                                    | 8         | 0.69%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 8         | 0.69%   |
| Realtek Killer E2600 GbE Controller                                    | 7         | 0.6%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 7         | 0.6%    |
| Nvidia MCP61 Ethernet                                                  | 7         | 0.6%    |
| Intel I211 Gigabit Network Connection                                  | 7         | 0.6%    |
| Intel Ethernet Controller I225-V                                       | 7         | 0.6%    |
| Intel Comet Lake PCH CNVi WiFi                                         | 7         | 0.6%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 6         | 0.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 6         | 0.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 6         | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 6         | 0.52%   |
| Intel Wireless 7260                                                    | 6         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 214       | 38.63%  |
| Realtek Semiconductor                 | 112       | 20.22%  |
| Qualcomm Atheros                      | 102       | 18.41%  |
| Broadcom                              | 42        | 7.58%   |
| Ralink Technology                     | 27        | 4.87%   |
| TP-Link                               | 15        | 2.71%   |
| MediaTek                              | 14        | 2.53%   |
| Ralink                                | 7         | 1.26%   |
| Qualcomm Atheros Communications       | 4         | 0.72%   |
| Broadcom Limited                      | 4         | 0.72%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.54%   |
| D-Link                                | 2         | 0.36%   |
| Tenda                                 | 1         | 0.18%   |
| Samsung Electronics                   | 1         | 0.18%   |
| NetGear                               | 1         | 0.18%   |
| Marvell Technology Group              | 1         | 0.18%   |
| Encore Electronics                    | 1         | 0.18%   |
| Dell                                  | 1         | 0.18%   |
| BUFFALO                               | 1         | 0.18%   |
| ASUSTek Computer                      | 1         | 0.18%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 24        | 4.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 23        | 4.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 20        | 3.6%    |
| Intel Wireless 7265                                            | 20        | 3.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 18        | 3.24%   |
| Ralink MT7601U Wireless Adapter                                | 17        | 3.06%   |
| Intel Wi-Fi 6 AX200                                            | 17        | 3.06%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 16        | 2.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 15        | 2.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 14        | 2.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 14        | 2.52%   |
| Intel Wireless 3165                                            | 14        | 2.52%   |
| Realtek 802.11ac NIC                                           | 12        | 2.16%   |
| Intel Wi-Fi 6 AX201                                            | 12        | 2.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 11        | 1.98%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 11        | 1.98%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 11        | 1.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 10        | 1.8%    |
| Intel Wireless 8265 / 8275                                     | 10        | 1.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 10        | 1.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 10        | 1.8%    |
| Broadcom BCM43142 802.11b/g/n                                  | 10        | 1.8%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 9         | 1.62%   |
| Intel Wireless 8260                                            | 8         | 1.44%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 8         | 1.44%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 7         | 1.26%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 6         | 1.08%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 6         | 1.08%   |
| Intel Wireless 7260                                            | 6         | 1.08%   |
| Intel Centrino Advanced-N 6235                                 | 6         | 1.08%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 6         | 1.08%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 5         | 0.9%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 5         | 0.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 5         | 0.9%    |
| Broadcom BCM43228 802.11a/b/g/n                                | 5         | 0.9%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 4         | 0.72%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 4         | 0.72%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 4         | 0.72%   |
| Ralink RT5370 Wireless Adapter                                 | 4         | 0.72%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 4         | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 378       | 63.74%  |
| Intel                             | 107       | 18.04%  |
| Qualcomm Atheros                  | 33        | 5.56%   |
| Broadcom                          | 19        | 3.2%    |
| Nvidia                            | 12        | 2.02%   |
| JMicron Technology                | 5         | 0.84%   |
| ASIX Electronics                  | 5         | 0.84%   |
| Samsung Electronics               | 4         | 0.67%   |
| OPPO Electronics                  | 4         | 0.67%   |
| Broadcom Limited                  | 4         | 0.67%   |
| Xiaomi                            | 3         | 0.51%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.51%   |
| Marvell Technology Group          | 3         | 0.51%   |
| ICS Advent                        | 2         | 0.34%   |
| Huawei Technologies               | 2         | 0.34%   |
| DisplayLink                       | 2         | 0.34%   |
| Apple                             | 2         | 0.34%   |
| Sundance Technology Inc / IC Plus | 1         | 0.17%   |
| Qualcomm                          | 1         | 0.17%   |
| Microchip Technology              | 1         | 0.17%   |
| MediaTek                          | 1         | 0.17%   |
| D-Link System                     | 1         | 0.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 297       | 49.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 51        | 8.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 25        | 4.17%   |
| Realtek RTL8125 2.5GbE Controller                                      | 15        | 2.5%    |
| Realtek Killer E2600 GbE Controller                                    | 7         | 1.17%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 7         | 1.17%   |
| Nvidia MCP61 Ethernet                                                  | 7         | 1.17%   |
| Intel I211 Gigabit Network Connection                                  | 7         | 1.17%   |
| Intel Ethernet Controller I225-V                                       | 7         | 1.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 6         | 1%      |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 6         | 1%      |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 5         | 0.83%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 0.83%   |
| Intel Ethernet Connection (2) I219-LM                                  | 5         | 0.83%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 4         | 0.67%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 4         | 0.67%   |
| OPPO SM8350-MTP _SN:9338D66C                                           | 4         | 0.67%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                    | 4         | 0.67%   |
| Intel Ethernet Connection I217-V                                       | 4         | 0.67%   |
| Intel Ethernet Connection (6) I219-LM                                  | 4         | 0.67%   |
| Intel 82579V Gigabit Network Connection                                | 4         | 0.67%   |
| Intel 82567LM Gigabit Network Connection                               | 4         | 0.67%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 4         | 0.67%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 0.67%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 3         | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 0.5%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 3         | 0.5%    |
| Intel Ethernet Connection I217-LM                                      | 3         | 0.5%    |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 0.5%    |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 0.5%    |
| Intel Ethernet Connection (2) I219-V                                   | 3         | 0.5%    |
| Intel Ethernet Connection (10) I219-V                                  | 3         | 0.5%    |
| Intel 82567LM-3 Gigabit Network Connection                             | 3         | 0.5%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 0.5%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 3         | 0.5%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2         | 0.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2         | 0.33%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2         | 0.33%   |
| Nvidia MCP79 Ethernet                                                  | 2         | 0.33%   |
| Intel I210 Gigabit Network Connection                                  | 2         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 559       | 51.19%  |
| WiFi     | 526       | 48.17%  |
| Modem    | 5         | 0.46%   |
| Unknown  | 2         | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 420       | 61.05%  |
| Ethernet | 268       | 38.95%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 343       | 50.66%  |
| 1     | 303       | 44.76%  |
| 0     | 15        | 2.22%   |
| 3     | 12        | 1.77%   |
| 6     | 3         | 0.44%   |
| 5     | 1         | 0.15%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 613       | 89.23%  |
| Yes  | 74        | 10.77%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 166       | 39.15%  |
| Realtek Semiconductor           | 48        | 11.32%  |
| IMC Networks                    | 38        | 8.96%   |
| Qualcomm Atheros Communications | 31        | 7.31%   |
| Lite-On Technology              | 28        | 6.6%    |
| Broadcom                        | 27        | 6.37%   |
| Cambridge Silicon Radio         | 24        | 5.66%   |
| Foxconn / Hon Hai               | 20        | 4.72%   |
| Apple                           | 10        | 2.36%   |
| Toshiba                         | 4         | 0.94%   |
| Ralink                          | 4         | 0.94%   |
| Hewlett-Packard                 | 4         | 0.94%   |
| Chicony Electronics             | 4         | 0.94%   |
| TP-Link                         | 3         | 0.71%   |
| Dell                            | 3         | 0.71%   |
| Realtek                         | 2         | 0.47%   |
| SINO WEALTH                     | 1         | 0.24%   |
| Ralink Technology               | 1         | 0.24%   |
| MediaTek                        | 1         | 0.24%   |
| Marvell Semiconductor           | 1         | 0.24%   |
| Integrated System Solution      | 1         | 0.24%   |
| Foxconn International           | 1         | 0.24%   |
| Actions                         | 1         | 0.24%   |
| Unknown                         | 1         | 0.24%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 42        | 9.91%   |
| Realtek Bluetooth Radio                             | 31        | 7.31%   |
| Intel AX201 Bluetooth                               | 31        | 7.31%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 27        | 6.37%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 24        | 5.66%   |
| IMC Networks Bluetooth Radio                        | 18        | 4.25%   |
| Intel AX200 Bluetooth                               | 16        | 3.77%   |
| Intel Bluetooth Device                              | 14        | 3.3%    |
| Intel Wireless-AC 3168 Bluetooth                    | 13        | 3.07%   |
| Qualcomm Atheros  Bluetooth Device                  | 12        | 2.83%   |
| IMC Networks Bluetooth Device                       | 12        | 2.83%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 11        | 2.59%   |
| Intel AX210 Bluetooth                               | 8         | 1.89%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 7         | 1.65%   |
| Lite-On Bluetooth Device                            | 7         | 1.65%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 7         | 1.65%   |
| Foxconn / Hon Hai Bluetooth Device                  | 7         | 1.65%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 1.65%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 6         | 1.42%   |
| IMC Networks Wireless_Device                        | 6         | 1.42%   |
| Realtek 802.11ac WLAN Adapter                       | 5         | 1.18%   |
| Realtek RTL8821A Bluetooth                          | 4         | 0.94%   |
| Realtek RTL8723B Bluetooth                          | 4         | 0.94%   |
| Ralink RT3290 Bluetooth                             | 4         | 0.94%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 4         | 0.94%   |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 0.94%   |
| Intel AX211 Bluetooth                               | 4         | 0.94%   |
| Chicony Bluetooth (RTL8723BE)                       | 4         | 0.94%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 0.94%   |
| Apple Bluetooth USB Host Controller                 | 4         | 0.94%   |
| TP-Link UB500 Adapter                               | 3         | 0.71%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 3         | 0.71%   |
| Apple Bluetooth Host Controller                     | 3         | 0.71%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 0.47%   |
| Realtek Bluetooth Radio                             | 2         | 0.47%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.47%   |
| Lite-On Wireless_Device                             | 2         | 0.47%   |
| Lite-On BCM43142A0                                  | 2         | 0.47%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 0.47%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 468       | 53.73%  |
| AMD                              | 188       | 21.58%  |
| Nvidia                           | 137       | 15.73%  |
| C-Media Electronics              | 12        | 1.38%   |
| Logitech                         | 8         | 0.92%   |
| Generalplus Technology           | 7         | 0.8%    |
| JMTek                            | 5         | 0.57%   |
| DCMT Technology                  | 4         | 0.46%   |
| SteelSeries ApS                  | 3         | 0.34%   |
| Silicon Integrated Systems [SiS] | 3         | 0.34%   |
| Plantronics                      | 3         | 0.34%   |
| Kingston Technology              | 3         | 0.34%   |
| Realtek Semiconductor            | 2         | 0.23%   |
| Razer USA                        | 2         | 0.23%   |
| GN Netcom                        | 2         | 0.23%   |
| Giga-Byte Technology             | 2         | 0.23%   |
| ZOOM                             | 1         | 0.11%   |
| XMOS                             | 1         | 0.11%   |
| Stadium USB microphone           | 1         | 0.11%   |
| Sony                             | 1         | 0.11%   |
| OPPO Electronics                 | 1         | 0.11%   |
| Micronas                         | 1         | 0.11%   |
| M-Audio                          | 1         | 0.11%   |
| Hewlett-Packard                  | 1         | 0.11%   |
| Fry's Electronics                | 1         | 0.11%   |
| Focusrite-Novation               | 1         | 0.11%   |
| FiiO Electronics Technology      | 1         | 0.11%   |
| FIFINE 683 Microphone            | 1         | 0.11%   |
| Elgato Systems                   | 1         | 0.11%   |
| Creative Technology              | 1         | 0.11%   |
| Corsair                          | 1         | 0.11%   |
| Cooler Master                    | 1         | 0.11%   |
| Audeze                           | 1         | 0.11%   |
| ASUSTek Computer                 | 1         | 0.11%   |
| Arturia                          | 1         | 0.11%   |
| Apple                            | 1         | 0.11%   |
| AKAI Professional M.I.           | 1         | 0.11%   |
| Unknown                          | 1         | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 70        | 6.67%   |
| Intel Sunrise Point-LP HD Audio                                            | 62        | 5.91%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 53        | 5.05%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 42        | 4%      |
| AMD FCH Azalia Controller                                                  | 40        | 3.81%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 33        | 3.15%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 30        | 2.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 25        | 2.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 25        | 2.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 20        | 1.91%   |
| AMD Starship/Matisse HD Audio Controller                                   | 19        | 1.81%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 18        | 1.72%   |
| Intel Cannon Lake PCH cAVS                                                 | 18        | 1.72%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 17        | 1.62%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 17        | 1.62%   |
| Intel Broadwell-U Audio Controller                                         | 17        | 1.62%   |
| Intel 200 Series PCH HD Audio                                              | 15        | 1.43%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 15        | 1.43%   |
| Nvidia GF108 High Definition Audio Controller                              | 14        | 1.33%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 14        | 1.33%   |
| Nvidia GP107GL High Definition Audio Controller                            | 13        | 1.24%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 13        | 1.24%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 13        | 1.24%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 12        | 1.14%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 12        | 1.14%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 12        | 1.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 12        | 1.14%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 12        | 1.14%   |
| Intel Haswell-ULT HD Audio Controller                                      | 11        | 1.05%   |
| Intel Comet Lake PCH-LP cAVS                                               | 11        | 1.05%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 11        | 1.05%   |
| Intel 8 Series HD Audio Controller                                         | 11        | 1.05%   |
| AMD Trinity HDMI Audio Controller                                          | 10        | 0.95%   |
| AMD Kabini HDMI/DP Audio                                                   | 10        | 0.95%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10        | 0.95%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 10        | 0.95%   |
| Nvidia TU116 High Definition Audio Controller                              | 9         | 0.86%   |
| Nvidia TU106 High Definition Audio Controller                              | 9         | 0.86%   |
| Nvidia MCP61 High Definition Audio                                         | 9         | 0.86%   |
| Nvidia Audio device                                                        | 9         | 0.86%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Kingston            | 75        | 18.99%  |
| Samsung Electronics | 73        | 18.48%  |
| SK hynix            | 72        | 18.23%  |
| Micron Technology   | 30        | 7.59%   |
| Unknown             | 28        | 7.09%   |
| Crucial             | 18        | 4.56%   |
| Team                | 15        | 3.8%    |
| Ramaxel Technology  | 12        | 3.04%   |
| G.Skill             | 11        | 2.78%   |
| Corsair             | 7         | 1.77%   |
| Unknown             | 7         | 1.77%   |
| Nanya Technology    | 6         | 1.52%   |
| Transcend           | 5         | 1.27%   |
| Elpida              | 5         | 1.27%   |
| A-DATA Technology   | 5         | 1.27%   |
| Unknown (ABCD)      | 4         | 1.01%   |
| Patriot             | 3         | 0.76%   |
| Unknown (8A5D)      | 2         | 0.51%   |
| PNY                 | 2         | 0.51%   |
| Kingmax             | 2         | 0.51%   |
| Uroad               | 1         | 0.25%   |
| Unknown (89BA)      | 1         | 0.25%   |
| Unknown (0x0B79)    | 1         | 0.25%   |
| Unifosa             | 1         | 0.25%   |
| Silicon Power       | 1         | 0.25%   |
| Qimonda             | 1         | 0.25%   |
| PUSKILL             | 1         | 0.25%   |
| Mitsubishi          | 1         | 0.25%   |
| ChangXin Memory     | 1         | 0.25%   |
| Carry               | 1         | 0.25%   |
| Avant               | 1         | 0.25%   |
| ASint Technology    | 1         | 0.25%   |
| Apacer              | 1         | 0.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 7         | 1.69%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 1.45%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 6         | 1.45%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 6         | 1.45%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 6         | 1.45%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 5         | 1.21%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 0.97%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.97%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 0.97%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 4         | 0.97%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s              | 4         | 0.97%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 4         | 0.97%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 3         | 0.72%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.72%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.72%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 3         | 0.72%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 3         | 0.72%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.72%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 3         | 0.72%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 3         | 0.72%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.72%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.72%   |
| Kingston RAM KF2666C16D4/8G 8GB DIMM DDR4 2667MT/s               | 3         | 0.72%   |
| Kingston RAM ACR16D3LFS1KBG/2G 2GB SODIMM DDR3 1600MT/s          | 3         | 0.72%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 3         | 0.72%   |
| Unknown RAM Module 4GB SODIMM DDR4 2133MT/s                      | 2         | 0.48%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 2         | 0.48%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s              | 2         | 0.48%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s              | 2         | 0.48%   |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 2400MT/s               | 2         | 0.48%   |
| Team RAM TEAMGROUP-SD4-2400 8GB SODIMM DDR4 8400MT/s             | 2         | 0.48%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s             | 2         | 0.48%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.48%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.48%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.48%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.48%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 2         | 0.48%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s            | 2         | 0.48%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 0.48%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 165       | 50.77%  |
| DDR3    | 111       | 34.15%  |
| LPDDR4  | 14        | 4.31%   |
| DDR2    | 13        | 4%      |
| DDR5    | 8         | 2.46%   |
| LPDDR3  | 4         | 1.23%   |
| Unknown | 4         | 1.23%   |
| SDRAM   | 2         | 0.62%   |
| LPDDR5  | 2         | 0.62%   |
| DRAM    | 1         | 0.31%   |
| DDR     | 1         | 0.31%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 211       | 65.33%  |
| DIMM         | 90        | 27.86%  |
| Row Of Chips | 21        | 6.5%    |
| Unknown      | 1         | 0.31%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 149       | 41.16%  |
| 4096  | 108       | 29.83%  |
| 16384 | 37        | 10.22%  |
| 2048  | 34        | 9.39%   |
| 32768 | 18        | 4.97%   |
| 1024  | 16        | 4.42%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 77        | 21.63%  |
| 3200    | 62        | 17.42%  |
| 2667    | 62        | 17.42%  |
| 2400    | 27        | 7.58%   |
| 2133    | 20        | 5.62%   |
| 1333    | 14        | 3.93%   |
| 667     | 12        | 3.37%   |
| 1334    | 10        | 2.81%   |
| 3733    | 8         | 2.25%   |
| 4800    | 5         | 1.4%    |
| 3600    | 5         | 1.4%    |
| 1067    | 5         | 1.4%    |
| Unknown | 5         | 1.4%    |
| 3866    | 4         | 1.12%   |
| 2666    | 4         | 1.12%   |
| 4267    | 3         | 0.84%   |
| 3800    | 3         | 0.84%   |
| 1867    | 3         | 0.84%   |
| 8400    | 2         | 0.56%   |
| 6000    | 2         | 0.56%   |
| 3266    | 2         | 0.56%   |
| 1800    | 2         | 0.56%   |
| 1648    | 2         | 0.56%   |
| 1066    | 2         | 0.56%   |
| 800     | 2         | 0.56%   |
| 6400    | 1         | 0.28%   |
| 5600    | 1         | 0.28%   |
| 5500    | 1         | 0.28%   |
| 4333    | 1         | 0.28%   |
| 4266    | 1         | 0.28%   |
| 3500    | 1         | 0.28%   |
| 3466    | 1         | 0.28%   |
| 2933    | 1         | 0.28%   |
| 2448    | 1         | 0.28%   |
| 2048    | 1         | 0.28%   |
| 1866    | 1         | 0.28%   |
| 533     | 1         | 0.28%   |
| 400     | 1         | 0.28%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 4         | 36.36%  |
| Brother Industries | 3         | 27.27%  |
| Canon              | 2         | 18.18%  |
| Hewlett-Packard    | 1         | 9.09%   |
| Unknown            | 1         | 9.09%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Computers | Percent |
|---------------------------|-----------|---------|
| Seiko Epson L120 Series   | 2         | 18.18%  |
| Seiko Epson L360 Series   | 1         | 9.09%   |
| Seiko Epson L3110 Series  | 1         | 9.09%   |
| HP Smart Tank 610 series  | 1         | 9.09%   |
| Canon PIXMA MG2500 Series | 1         | 9.09%   |
| Canon G2010 series        | 1         | 9.09%   |
| Brother DCP-T710W         | 1         | 9.09%   |
| Brother DCP-T700W         | 1         | 9.09%   |
| Brother DCP-T310          | 1         | 9.09%   |
| Unknown                   | 1         | 9.09%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 105       | 24.08%  |
| Realtek Semiconductor                  | 37        | 8.49%   |
| IMC Networks                           | 37        | 8.49%   |
| Microdia                               | 33        | 7.57%   |
| Quanta                                 | 26        | 5.96%   |
| Sunplus Innovation Technology          | 19        | 4.36%   |
| Bison Electronics                      | 19        | 4.36%   |
| Cheng Uei Precision Industry (Foxlink) | 15        | 3.44%   |
| Logitech                               | 13        | 2.98%   |
| Apple                                  | 13        | 2.98%   |
| Lite-On Technology                     | 11        | 2.52%   |
| Syntek                                 | 9         | 2.06%   |
| Suyin                                  | 9         | 2.06%   |
| Silicon Motion                         | 8         | 1.83%   |
| Luxvisions Innotech Limited            | 8         | 1.83%   |
| A4Tech                                 | 8         | 1.83%   |
| Z-Star Microelectronics                | 6         | 1.38%   |
| Alcor Micro                            | 6         | 1.38%   |
| Samsung Electronics                    | 5         | 1.15%   |
| Acer                                   | 5         | 1.15%   |
| Jieli Technology                       | 4         | 0.92%   |
| Pixart Imaging                         | 3         | 0.69%   |
| Cubeternet                             | 3         | 0.69%   |
| ALi                                    | 3         | 0.69%   |
| Razer USA                              | 2         | 0.46%   |
| OPPO Electronics                       | 2         | 0.46%   |
| OmniVision Technologies                | 2         | 0.46%   |
| Importek                               | 2         | 0.46%   |
| icSpring                               | 2         | 0.46%   |
| Generalplus Technology                 | 2         | 0.46%   |
| Alpha Imaging Technology               | 2         | 0.46%   |
| Y Media                                | 1         | 0.23%   |
| WaveRider Communications               | 1         | 0.23%   |
| vivo                                   | 1         | 0.23%   |
| SunplusIT                              | 1         | 0.23%   |
| Sunplus Technology                     | 1         | 0.23%   |
| Sonix Technology                       | 1         | 0.23%   |
| Ricoh                                  | 1         | 0.23%   |
| Owon                                   | 1         | 0.23%   |
| Microsoft                              | 1         | 0.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 23        | 5.25%   |
| Chicony HD WebCam                                               | 20        | 4.57%   |
| Microdia Integrated_Webcam_HD                                   | 11        | 2.51%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 11        | 2.51%   |
| Quanta VGA WebCam                                               | 9         | 2.05%   |
| Realtek Integrated_Webcam_HD                                    | 8         | 1.83%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 8         | 1.83%   |
| Realtek Acer 640 x 480 laptop camera                            | 7         | 1.6%    |
| Chicony VGA WebCam                                              | 6         | 1.37%   |
| Quanta ACER HD User Facing                                      | 5         | 1.14%   |
| Logitech Webcam C270                                            | 5         | 1.14%   |
| IMC Networks Integrated Camera                                  | 5         | 1.14%   |
| Syntek Lenovo EasyCamera                                        | 4         | 0.91%   |
| Sunplus Integrated_Webcam_HD                                    | 4         | 0.91%   |
| Samsung Galaxy series, misc. (MTP mode)                         | 4         | 0.91%   |
| Realtek USB2.0 VGA UVC WebCam                                   | 4         | 0.91%   |
| Realtek Integrated Webcam                                       | 4         | 0.91%   |
| Microdia Laptop_Integrated_Webcam_HD                            | 4         | 0.91%   |
| Lite-On Integrated Camera                                       | 4         | 0.91%   |
| Jieli USB PHY 2.0                                               | 4         | 0.91%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 4         | 0.91%   |
| Chicony Integrated Camera [ThinkPad]                            | 4         | 0.91%   |
| Chicony HP Wide Vision HD Camera                                | 4         | 0.91%   |
| Chicony HP Truevision HD                                        | 4         | 0.91%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 4         | 0.91%   |
| Z-Star Venus USB2.0 Camera                                      | 3         | 0.68%   |
| Syntek Integrated Camera                                        | 3         | 0.68%   |
| Sunplus HD WebCam                                               | 3         | 0.68%   |
| Quanta HD User Facing                                           | 3         | 0.68%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                            | 3         | 0.68%   |
| Microdia Sonix USB 2.0 Camera                                   | 3         | 0.68%   |
| Microdia Integrated Camera                                      | 3         | 0.68%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 3         | 0.68%   |
| IMC Networks HD Camera                                          | 3         | 0.68%   |
| IMC Networks EasyCamera                                         | 3         | 0.68%   |
| Chicony TOSHIBA Web Camera - HD                                 | 3         | 0.68%   |
| Chicony Lenovo Integrated Camera (0.3MP)                        | 3         | 0.68%   |
| Chicony Lenovo EasyCamera                                       | 3         | 0.68%   |
| Chicony HP HD Camera                                            | 3         | 0.68%   |
| Chicony EasyCamera                                              | 3         | 0.68%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 17        | 30.36%  |
| Shenzhen Goodix Technology | 13        | 23.21%  |
| Synaptics                  | 10        | 17.86%  |
| LighTuning Technology      | 5         | 8.93%   |
| Elan Microelectronics      | 4         | 7.14%   |
| Upek                       | 3         | 5.36%   |
| AuthenTec                  | 3         | 5.36%   |
| GDMicroelectronics         | 1         | 1.79%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 10        | 17.86%  |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 7.14%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 5.36%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 5.36%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 5.36%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 5.36%   |
| Elan ELAN:Fingerprint                                                      | 3         | 5.36%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 3.57%   |
| Synaptics  WBDI                                                            | 2         | 3.57%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 3.57%   |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 3.57%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 3.57%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.79%   |
| Validity Sensors VFS491                                                    | 1         | 1.79%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 1.79%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.79%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 1.79%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.79%   |
| Synaptics TouchPad                                                         | 1         | 1.79%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.79%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.79%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 1.79%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.79%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.79%   |
| GDMicroelectronics Touch Fingerprint Sensor                                | 1         | 1.79%   |
| Elan ELAN:ARM-M4                                                           | 1         | 1.79%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.79%   |
| AuthenTec AES2810                                                          | 1         | 1.79%   |
| AuthenTec AES1600                                                          | 1         | 1.79%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Broadcom         | 7         | 41.18%  |
| Upek             | 3         | 17.65%  |
| Alcor Micro      | 3         | 17.65%  |
| O2 Micro         | 2         | 11.76%  |
| SCM Microsystems | 1         | 5.88%   |
| Lenovo           | 1         | 5.88%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 17.65%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 17.65%  |
| Broadcom 5880                                                                | 3         | 17.65%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 17.65%  |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 5.88%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 5.88%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 5.88%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 5.88%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 5.88%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 521       | 74.64%  |
| 1     | 151       | 21.63%  |
| 2     | 22        | 3.15%   |
| 3     | 4         | 0.57%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 55        | 27.36%  |
| Graphics card            | 49        | 24.38%  |
| Net/wireless             | 32        | 15.92%  |
| Chipcard                 | 16        | 7.96%   |
| Camera                   | 12        | 5.97%   |
| Multimedia controller    | 9         | 4.48%   |
| Net/ethernet             | 6         | 2.99%   |
| Bluetooth                | 5         | 2.49%   |
| Sound                    | 4         | 1.99%   |
| Communication controller | 4         | 1.99%   |
| Network                  | 2         | 1%      |
| Wireless                 | 1         | 0.5%    |
| Unassigned class         | 1         | 0.5%    |
| Storage/raid             | 1         | 0.5%    |
| Storage/nvme             | 1         | 0.5%    |
| Storage                  | 1         | 0.5%    |
| Modem                    | 1         | 0.5%    |
| Card reader              | 1         | 0.5%    |


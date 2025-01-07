Linux in Algeria - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Algeria.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Algeria/Desktop/README.md) and [notebooks](/Location/Algeria/Notebook/README.md).

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

Total: 589

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | UL80VT                      | Notebook    | [51fb360728](https://linux-hardware.org/?probe=51fb360728) | Jan 01, 2025 |
| Apple         | MacBookPro9,2               | Notebook    | [e6da658e0f](https://linux-hardware.org/?probe=e6da658e0f) | Jan 01, 2025 |
| ASUSTek       | X750JB                      | Notebook    | [c3848bc769](https://linux-hardware.org/?probe=c3848bc769) | Dec 28, 2024 |
| Lenovo        | ThinkPad E15 Gen 4 21E7S... | Notebook    | [ce166a3364](https://linux-hardware.org/?probe=ce166a3364) | Dec 28, 2024 |
| MSI           | H61M-P22                    | Desktop     | [ea858ac153](https://linux-hardware.org/?probe=ea858ac153) | Dec 28, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [2a99f4c635](https://linux-hardware.org/?probe=2a99f4c635) | Dec 26, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [0b609d2a62](https://linux-hardware.org/?probe=0b609d2a62) | Dec 26, 2024 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [675e3b2432](https://linux-hardware.org/?probe=675e3b2432) | Dec 20, 2024 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [28c2c92f61](https://linux-hardware.org/?probe=28c2c92f61) | Dec 19, 2024 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [a4239ba143](https://linux-hardware.org/?probe=a4239ba143) | Dec 17, 2024 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [3dafc8c3c6](https://linux-hardware.org/?probe=3dafc8c3c6) | Dec 06, 2024 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [34f8b6bc0b](https://linux-hardware.org/?probe=34f8b6bc0b) | Dec 06, 2024 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [8aeea5fc7c](https://linux-hardware.org/?probe=8aeea5fc7c) | Nov 27, 2024 |
| ASUSTek       | UL80VT                      | Notebook    | [e19cedbb78](https://linux-hardware.org/?probe=e19cedbb78) | Nov 25, 2024 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [4f167ce54b](https://linux-hardware.org/?probe=4f167ce54b) | Nov 24, 2024 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [abd518a26a](https://linux-hardware.org/?probe=abd518a26a) | Nov 23, 2024 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [acc6910742](https://linux-hardware.org/?probe=acc6910742) | Nov 22, 2024 |
| Supermicro    | X7DVL-3                     | Desktop     | [871c1bb144](https://linux-hardware.org/?probe=871c1bb144) | Nov 20, 2024 |
| Supermicro    | X7DVL-3                     | Desktop     | [3e09e8757c](https://linux-hardware.org/?probe=3e09e8757c) | Nov 20, 2024 |
| Dell          | 07WP95 A02                  | Desktop     | [ad630acc87](https://linux-hardware.org/?probe=ad630acc87) | Nov 18, 2024 |
| Dell          | 07WP95 A02                  | Desktop     | [a5cf2b973a](https://linux-hardware.org/?probe=a5cf2b973a) | Nov 17, 2024 |
| Dell          | Latitude 5580               | Notebook    | [23ae65a443](https://linux-hardware.org/?probe=23ae65a443) | Nov 15, 2024 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [af47ab24d4](https://linux-hardware.org/?probe=af47ab24d4) | Nov 14, 2024 |
| ASRock        | B550M-HVS SE                | Desktop     | [4259078823](https://linux-hardware.org/?probe=4259078823) | Nov 09, 2024 |
| ASUSTek       | UL80VT                      | Notebook    | [9e47f77eb2](https://linux-hardware.org/?probe=9e47f77eb2) | Nov 05, 2024 |
| MSI           | H61M-P20                    | Desktop     | [b19de2a571](https://linux-hardware.org/?probe=b19de2a571) | Nov 03, 2024 |
| MSI           | H61M-P20                    | Desktop     | [dbd2254213](https://linux-hardware.org/?probe=dbd2254213) | Nov 03, 2024 |
| Dell          | Inspiron 3543               | Notebook    | [e0b72cc4f7](https://linux-hardware.org/?probe=e0b72cc4f7) | Nov 02, 2024 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [b98436c123](https://linux-hardware.org/?probe=b98436c123) | Oct 24, 2024 |
| Google        | Drobit                      | Notebook    | [26edf296d3](https://linux-hardware.org/?probe=26edf296d3) | Oct 20, 2024 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [2c5dd173ae](https://linux-hardware.org/?probe=2c5dd173ae) | Oct 18, 2024 |
| Dell          | Inspiron 3543               | Notebook    | [eb86e7059c](https://linux-hardware.org/?probe=eb86e7059c) | Oct 16, 2024 |
| ASUSTek       | UL80VT                      | Notebook    | [c6cc761721](https://linux-hardware.org/?probe=c6cc761721) | Oct 13, 2024 |
| Dell          | Inspiron 3543               | Notebook    | [e5860959f4](https://linux-hardware.org/?probe=e5860959f4) | Oct 09, 2024 |
| Dell          | Inspiron 3543               | Notebook    | [1fcb3d5c10](https://linux-hardware.org/?probe=1fcb3d5c10) | Oct 03, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [2a065d3b6e](https://linux-hardware.org/?probe=2a065d3b6e) | Sep 27, 2024 |
| Dell          | Latitude 5490               | Notebook    | [897e69a84d](https://linux-hardware.org/?probe=897e69a84d) | Sep 27, 2024 |
| Dell          | Vostro 3520                 | Notebook    | [fc512f0d70](https://linux-hardware.org/?probe=fc512f0d70) | Sep 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [42bd818b1e](https://linux-hardware.org/?probe=42bd818b1e) | Sep 24, 2024 |
| Unknown       | Unknown                     | Notebook    | [556cdc2448](https://linux-hardware.org/?probe=556cdc2448) | Sep 21, 2024 |
| Unknown       | Unknown                     | Notebook    | [7e13c15a7b](https://linux-hardware.org/?probe=7e13c15a7b) | Sep 21, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [abdf739930](https://linux-hardware.org/?probe=abdf739930) | Sep 12, 2024 |
| ASUSTek       | X441SA                      | Notebook    | [35fe8d4aa5](https://linux-hardware.org/?probe=35fe8d4aa5) | Sep 09, 2024 |
| ASUSTek       | UL80VT                      | Notebook    | [7d4ad043e7](https://linux-hardware.org/?probe=7d4ad043e7) | Sep 08, 2024 |
| Pegatron      | 2A73h                       | Desktop     | [b089bc4cec](https://linux-hardware.org/?probe=b089bc4cec) | Aug 31, 2024 |
| Pegatron      | 2A73h                       | Desktop     | [8ba01a7663](https://linux-hardware.org/?probe=8ba01a7663) | Aug 31, 2024 |
| ASUSTek       | X540LJ                      | Notebook    | [82349f49b3](https://linux-hardware.org/?probe=82349f49b3) | Aug 28, 2024 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [c51c37be47](https://linux-hardware.org/?probe=c51c37be47) | Aug 20, 2024 |
| ASUSTek       | UL80VT                      | Notebook    | [2dfcfbc9d9](https://linux-hardware.org/?probe=2dfcfbc9d9) | Aug 18, 2024 |
| Lenovo        | Yoga Slim 9 14IAP7 82T0     | Notebook    | [53709855bd](https://linux-hardware.org/?probe=53709855bd) | Aug 16, 2024 |
| Lenovo        | Yoga Slim 9 14IAP7 82T0     | Notebook    | [dfd8518d3e](https://linux-hardware.org/?probe=dfd8518d3e) | Aug 16, 2024 |
| Unknown       | Unknown                     | Desktop     | [a66eadcbfc](https://linux-hardware.org/?probe=a66eadcbfc) | Aug 06, 2024 |
| ASUSTek       | X540SC                      | Notebook    | [88d86a9a73](https://linux-hardware.org/?probe=88d86a9a73) | Jul 21, 2024 |
| Acer          | Aspire F5-572               | Notebook    | [25a7a5ebdd](https://linux-hardware.org/?probe=25a7a5ebdd) | Jul 19, 2024 |
| Unknown       | Unknown                     | Tablet      | [f456628e1b](https://linux-hardware.org/?probe=f456628e1b) | Jul 17, 2024 |
| SPA CONDOR    | P401                        | Notebook    | [bb7d750281](https://linux-hardware.org/?probe=bb7d750281) | Jul 17, 2024 |
| Dell          | Inspiron 3521               | Notebook    | [3c2a399aef](https://linux-hardware.org/?probe=3c2a399aef) | Jul 15, 2024 |
| Acer          | TravelMate 5744             | Notebook    | [dd44567736](https://linux-hardware.org/?probe=dd44567736) | Jul 09, 2024 |
| ASUSTek       | UL80VT                      | Notebook    | [f43d972a57](https://linux-hardware.org/?probe=f43d972a57) | Jul 09, 2024 |
| Gigabyte      | P41T-D3                     | Desktop     | [cc80c6a7cb](https://linux-hardware.org/?probe=cc80c6a7cb) | Jul 09, 2024 |
| MSI           | A320M-A PRO MAX             | Desktop     | [877b8a130e](https://linux-hardware.org/?probe=877b8a130e) | Jul 05, 2024 |
| MSI           | A320M-A PRO MAX             | Desktop     | [497ab84801](https://linux-hardware.org/?probe=497ab84801) | Jul 05, 2024 |
| Dell          | Inspiron 3521               | Notebook    | [64d61866bd](https://linux-hardware.org/?probe=64d61866bd) | Jul 04, 2024 |
| Dell          | Inspiron 3521               | Notebook    | [8f03d5365d](https://linux-hardware.org/?probe=8f03d5365d) | Jul 04, 2024 |
| ASUSTek       | H81M-K                      | Desktop     | [9978535f5e](https://linux-hardware.org/?probe=9978535f5e) | Jul 01, 2024 |
| Dell          | 05WNJ2 A02                  | Server      | [506164554c](https://linux-hardware.org/?probe=506164554c) | Jun 29, 2024 |
| HP            | 3048h                       | Desktop     | [d2376a292e](https://linux-hardware.org/?probe=d2376a292e) | Jun 26, 2024 |
| HP            | Pavilion g6                 | Notebook    | [01e6b073ab](https://linux-hardware.org/?probe=01e6b073ab) | Jun 23, 2024 |
| HP            | Pavilion g6                 | Notebook    | [0f4c9ec0a7](https://linux-hardware.org/?probe=0f4c9ec0a7) | Jun 23, 2024 |
| Packard Be... | MCP73PV                     | Desktop     | [cee96d28a1](https://linux-hardware.org/?probe=cee96d28a1) | Jun 13, 2024 |
| HP            | ProBook 4540s               | Notebook    | [0c0ddd802d](https://linux-hardware.org/?probe=0c0ddd802d) | Jun 11, 2024 |
| Foxconn       | H61MXV/H61MXV-LE/H67MXV ... | Desktop     | [bc79f3daa4](https://linux-hardware.org/?probe=bc79f3daa4) | May 30, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [8c1450cf10](https://linux-hardware.org/?probe=8c1450cf10) | May 28, 2024 |
| Packard Be... | MCP73PV                     | Desktop     | [62a8a9494e](https://linux-hardware.org/?probe=62a8a9494e) | May 22, 2024 |
| Apple         | Mac-F2268CC8                | All in one  | [50de34aa91](https://linux-hardware.org/?probe=50de34aa91) | May 19, 2024 |
| Apple         | Mac-F2268CC8                | All in one  | [a28400a750](https://linux-hardware.org/?probe=a28400a750) | May 19, 2024 |
| ASUSTek       | UL80VT                      | Notebook    | [b732300ffb](https://linux-hardware.org/?probe=b732300ffb) | May 19, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [ad7c6b6a36](https://linux-hardware.org/?probe=ad7c6b6a36) | May 19, 2024 |
| Acer          | Aspire V5-121               | Notebook    | [ee7af6bc3d](https://linux-hardware.org/?probe=ee7af6bc3d) | May 09, 2024 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [a415a1e824](https://linux-hardware.org/?probe=a415a1e824) | May 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [3c551032a7](https://linux-hardware.org/?probe=3c551032a7) | Apr 30, 2024 |
| HP            | EliteBook Folio 9470m       | Notebook    | [0d587f3e64](https://linux-hardware.org/?probe=0d587f3e64) | Apr 27, 2024 |
| HP            | EliteBook Folio 9470m       | Notebook    | [30d9ddd3f9](https://linux-hardware.org/?probe=30d9ddd3f9) | Apr 27, 2024 |
| HP            | EliteBook 8570p             | Notebook    | [cbe3543005](https://linux-hardware.org/?probe=cbe3543005) | Apr 26, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b8f62dc34c](https://linux-hardware.org/?probe=b8f62dc34c) | Apr 13, 2024 |
| Dell          | Inspiron N5110              | Notebook    | [1d379b09d7](https://linux-hardware.org/?probe=1d379b09d7) | Apr 11, 2024 |
| ASUSTek       | UL80VT                      | Notebook    | [8c290e2826](https://linux-hardware.org/?probe=8c290e2826) | Apr 07, 2024 |
| Foxconn       | H61MXL/H61MXL-K             | Desktop     | [333a0e4aa4](https://linux-hardware.org/?probe=333a0e4aa4) | Mar 29, 2024 |
| Apple         | MacBookPro14,2              | Notebook    | [8af3aa3110](https://linux-hardware.org/?probe=8af3aa3110) | Mar 27, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [b97398e770](https://linux-hardware.org/?probe=b97398e770) | Mar 23, 2024 |
| Acer          | Aspire A315-21              | Notebook    | [99e9828926](https://linux-hardware.org/?probe=99e9828926) | Mar 15, 2024 |
| Lenovo        | ThinkPad T480 20L6S69X08    | Notebook    | [63c84de71e](https://linux-hardware.org/?probe=63c84de71e) | Mar 15, 2024 |
| Acer          | Aspire ES1-571              | Notebook    | [e8fe3e1197](https://linux-hardware.org/?probe=e8fe3e1197) | Mar 13, 2024 |
| Lenovo        | G560 20042                  | Notebook    | [d7fffe52e5](https://linux-hardware.org/?probe=d7fffe52e5) | Mar 05, 2024 |
| Lenovo        | ThinkPad T480 20L6S69X08    | Notebook    | [16326b521f](https://linux-hardware.org/?probe=16326b521f) | Mar 01, 2024 |
| Dell          | Inspiron N5110              | Notebook    | [0338bf3523](https://linux-hardware.org/?probe=0338bf3523) | Mar 01, 2024 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [c6209a30c6](https://linux-hardware.org/?probe=c6209a30c6) | Feb 28, 2024 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [3d502260aa](https://linux-hardware.org/?probe=3d502260aa) | Feb 28, 2024 |
| Dell          | Inspiron N5110              | Notebook    | [ad7bc2d3d3](https://linux-hardware.org/?probe=ad7bc2d3d3) | Feb 21, 2024 |
| ASUSTek       | UL80VT                      | Notebook    | [f186dd9b24](https://linux-hardware.org/?probe=f186dd9b24) | Feb 19, 2024 |
| Acer          | Aspire M3-581T              | Notebook    | [5d8055a703](https://linux-hardware.org/?probe=5d8055a703) | Feb 19, 2024 |
| Dell          | Vostro 15-3568              | Notebook    | [dd1878c08e](https://linux-hardware.org/?probe=dd1878c08e) | Feb 18, 2024 |
| Dell          | Vostro 15-3568              | Notebook    | [75d09cfc27](https://linux-hardware.org/?probe=75d09cfc27) | Feb 18, 2024 |
| HP            | Pavilion dm3 Notebook PC    | Notebook    | [3e0f898cc8](https://linux-hardware.org/?probe=3e0f898cc8) | Feb 16, 2024 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [9616627427](https://linux-hardware.org/?probe=9616627427) | Feb 13, 2024 |
| MSI           | H61M-P20                    | Desktop     | [b364c76f36](https://linux-hardware.org/?probe=b364c76f36) | Feb 10, 2024 |
| MSI           | H61M-P20                    | Desktop     | [2dd188e5d9](https://linux-hardware.org/?probe=2dd188e5d9) | Feb 10, 2024 |
| Fujitsu       | LIFEBOOK E544               | Notebook    | [2cb0310c0f](https://linux-hardware.org/?probe=2cb0310c0f) | Feb 09, 2024 |
| Lenovo        | ThinkPad X240 20AMS5K70S    | Notebook    | [3ca238a44f](https://linux-hardware.org/?probe=3ca238a44f) | Feb 05, 2024 |
| ASUSTek       | UL80VT                      | Notebook    | [e2f97be622](https://linux-hardware.org/?probe=e2f97be622) | Feb 03, 2024 |
| Lenovo        | MIIX 520-12IKB 20M3         | Tablet      | [0fb22a9b60](https://linux-hardware.org/?probe=0fb22a9b60) | Feb 02, 2024 |
| Dell          | Inspiron N5110              | Notebook    | [e7338ad21d](https://linux-hardware.org/?probe=e7338ad21d) | Feb 01, 2024 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [98dc9736d7](https://linux-hardware.org/?probe=98dc9736d7) | Feb 01, 2024 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [4661ceab45](https://linux-hardware.org/?probe=4661ceab45) | Feb 01, 2024 |
| ASUSTek       | UL80VT                      | Notebook    | [865619250b](https://linux-hardware.org/?probe=865619250b) | Feb 01, 2024 |
| Acer          | Aspire E5-571               | Notebook    | [6ebe6ae5be](https://linux-hardware.org/?probe=6ebe6ae5be) | Jan 28, 2024 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [28dfa3aae0](https://linux-hardware.org/?probe=28dfa3aae0) | Jan 20, 2024 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [bf37fabc09](https://linux-hardware.org/?probe=bf37fabc09) | Jan 13, 2024 |
| HP            | Laptop 15 da0018nk          | Notebook    | [11c54a0e5b](https://linux-hardware.org/?probe=11c54a0e5b) | Jan 12, 2024 |
| HP            | Pavilion 15                 | Notebook    | [dad46e573f](https://linux-hardware.org/?probe=dad46e573f) | Jan 07, 2024 |
| Dell          | Inspiron N5110              | Notebook    | [0f0d661119](https://linux-hardware.org/?probe=0f0d661119) | Jan 06, 2024 |
| ASUSTek       | UL80VT                      | Notebook    | [7780af9eb5](https://linux-hardware.org/?probe=7780af9eb5) | Jan 05, 2024 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [3055333756](https://linux-hardware.org/?probe=3055333756) | Jan 03, 2024 |
| Dell          | Inspiron N5110              | Notebook    | [bf974230c7](https://linux-hardware.org/?probe=bf974230c7) | Jan 01, 2024 |
| HP            | EliteBook 820 G1            | Notebook    | [60a0cb2296](https://linux-hardware.org/?probe=60a0cb2296) | Jan 01, 2024 |
| Dell          | Inspiron N5110              | Notebook    | [439d746143](https://linux-hardware.org/?probe=439d746143) | Dec 31, 2023 |
| Dell          | Latitude 7480               | Notebook    | [9872ef6241](https://linux-hardware.org/?probe=9872ef6241) | Dec 31, 2023 |
| Dell          | Latitude 7480               | Notebook    | [527544c2de](https://linux-hardware.org/?probe=527544c2de) | Dec 31, 2023 |
| ASUSTek       | X750JB                      | Notebook    | [3c2f9bd15e](https://linux-hardware.org/?probe=3c2f9bd15e) | Dec 28, 2023 |
| ASUSTek       | UL80VT                      | Notebook    | [5b04b67d44](https://linux-hardware.org/?probe=5b04b67d44) | Dec 23, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [761103087e](https://linux-hardware.org/?probe=761103087e) | Dec 19, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [6440dbccd4](https://linux-hardware.org/?probe=6440dbccd4) | Dec 13, 2023 |
| Gigabyte      | D-700                       | Desktop     | [18e3ee84cc](https://linux-hardware.org/?probe=18e3ee84cc) | Dec 11, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [c7a949f9e8](https://linux-hardware.org/?probe=c7a949f9e8) | Dec 09, 2023 |
| AMI           | Intel                       | Desktop     | [7fdef1f7fc](https://linux-hardware.org/?probe=7fdef1f7fc) | Dec 04, 2023 |
| Dell          | Latitude 6430U              | Notebook    | [45d1723559](https://linux-hardware.org/?probe=45d1723559) | Dec 03, 2023 |
| Dell          | Latitude 6430U              | Notebook    | [1e4dda911f](https://linux-hardware.org/?probe=1e4dda911f) | Dec 03, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [39dd843280](https://linux-hardware.org/?probe=39dd843280) | Nov 28, 2023 |
| ASUSTek       | X540SC                      | Notebook    | [5a56e0886b](https://linux-hardware.org/?probe=5a56e0886b) | Nov 27, 2023 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [0ff86eddc6](https://linux-hardware.org/?probe=0ff86eddc6) | Nov 27, 2023 |
| ASUSTek       | UL80VT                      | Notebook    | [21f0f94735](https://linux-hardware.org/?probe=21f0f94735) | Nov 22, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [e0f2e8180d](https://linux-hardware.org/?probe=e0f2e8180d) | Nov 21, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [f8d242150d](https://linux-hardware.org/?probe=f8d242150d) | Nov 19, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [d297e1365c](https://linux-hardware.org/?probe=d297e1365c) | Nov 16, 2023 |
| Intel         | H61                         | Desktop     | [56e954caa1](https://linux-hardware.org/?probe=56e954caa1) | Nov 11, 2023 |
| ASUSTek       | UL80VT                      | Notebook    | [25fe802d18](https://linux-hardware.org/?probe=25fe802d18) | Nov 06, 2023 |
| Gigabyte      | 945GCM-S2C                  | Desktop     | [c714bf35c2](https://linux-hardware.org/?probe=c714bf35c2) | Nov 06, 2023 |
| HP            | 2B34                        | Desktop     | [52737869e2](https://linux-hardware.org/?probe=52737869e2) | Nov 06, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [ad0e3ec9ea](https://linux-hardware.org/?probe=ad0e3ec9ea) | Nov 01, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [523fd59139](https://linux-hardware.org/?probe=523fd59139) | Nov 01, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [d2d21dcf50](https://linux-hardware.org/?probe=d2d21dcf50) | Nov 01, 2023 |
| AMI           | Intel                       | Desktop     | [c4587092bf](https://linux-hardware.org/?probe=c4587092bf) | Nov 01, 2023 |
| Dell          | Latitude 5490               | Notebook    | [fcee866d9a](https://linux-hardware.org/?probe=fcee866d9a) | Oct 31, 2023 |
| Notebook      | PA70Hx                      | Notebook    | [627ed781b5](https://linux-hardware.org/?probe=627ed781b5) | Oct 30, 2023 |
| Notebook      | PA70Hx                      | Notebook    | [e13de47400](https://linux-hardware.org/?probe=e13de47400) | Oct 29, 2023 |
| HP            | Compaq 15                   | Notebook    | [83fab35dec](https://linux-hardware.org/?probe=83fab35dec) | Oct 26, 2023 |
| HP            | Compaq 15                   | Notebook    | [41ada9e77d](https://linux-hardware.org/?probe=41ada9e77d) | Oct 26, 2023 |
| UNOWHY        | Y13G012S4EI                 | Notebook    | [eb2ef3f8d5](https://linux-hardware.org/?probe=eb2ef3f8d5) | Oct 24, 2023 |
| ASUSTek       | UL80VT                      | Notebook    | [7991ecc4ee](https://linux-hardware.org/?probe=7991ecc4ee) | Oct 22, 2023 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [67e51cbac1](https://linux-hardware.org/?probe=67e51cbac1) | Oct 19, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [35a5d0ac7c](https://linux-hardware.org/?probe=35a5d0ac7c) | Oct 14, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [081856b4e9](https://linux-hardware.org/?probe=081856b4e9) | Oct 14, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [7a11989cb0](https://linux-hardware.org/?probe=7a11989cb0) | Oct 08, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [1ce86e7416](https://linux-hardware.org/?probe=1ce86e7416) | Oct 08, 2023 |
| ASUSTek       | UL80VT                      | Notebook    | [fc4a10d945](https://linux-hardware.org/?probe=fc4a10d945) | Oct 04, 2023 |
| HP            | Pavilion 15                 | Notebook    | [b54af646b7](https://linux-hardware.org/?probe=b54af646b7) | Oct 03, 2023 |
| HP            | Pavilion 15                 | Notebook    | [96c6a8d31e](https://linux-hardware.org/?probe=96c6a8d31e) | Oct 03, 2023 |
| Dell          | Latitude 5480               | Notebook    | [3672418d7a](https://linux-hardware.org/?probe=3672418d7a) | Oct 02, 2023 |
| ASUSTek       | UL80VT                      | Notebook    | [1d3c36ccf4](https://linux-hardware.org/?probe=1d3c36ccf4) | Sep 25, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [e98b118b85](https://linux-hardware.org/?probe=e98b118b85) | Sep 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [162a680d7d](https://linux-hardware.org/?probe=162a680d7d) | Sep 19, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [6903c7fc50](https://linux-hardware.org/?probe=6903c7fc50) | Sep 18, 2023 |
| Foxconn       | H61MXL/H61MXL-K             | Desktop     | [b5b49fefb3](https://linux-hardware.org/?probe=b5b49fefb3) | Sep 09, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [eaf6dbaf3e](https://linux-hardware.org/?probe=eaf6dbaf3e) | Sep 09, 2023 |
| Dell          | Latitude E5470              | Notebook    | [a404e86063](https://linux-hardware.org/?probe=a404e86063) | Sep 08, 2023 |
| ASUSTek       | UL80VT                      | Notebook    | [daa7101bf4](https://linux-hardware.org/?probe=daa7101bf4) | Sep 07, 2023 |
| Unknown       | TBYF-1014WIN32              | Notebook    | [11ef48e0c0](https://linux-hardware.org/?probe=11ef48e0c0) | Sep 06, 2023 |
| ASUSTek       | UL80VT                      | Notebook    | [aec41416ac](https://linux-hardware.org/?probe=aec41416ac) | Sep 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [471b71bda5](https://linux-hardware.org/?probe=471b71bda5) | Sep 04, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [ba40b3b859](https://linux-hardware.org/?probe=ba40b3b859) | Sep 01, 2023 |
| HP            | 18E9                        | Desktop     | [fd1f6decb2](https://linux-hardware.org/?probe=fd1f6decb2) | Sep 01, 2023 |
| ASUSTek       | UL80VT                      | Notebook    | [858a6c3ea1](https://linux-hardware.org/?probe=858a6c3ea1) | Aug 26, 2023 |
| Dell          | Latitude 7430               | Notebook    | [7daf0301c5](https://linux-hardware.org/?probe=7daf0301c5) | Aug 24, 2023 |
| MSI           | CR610M                      | Notebook    | [e2432b72a5](https://linux-hardware.org/?probe=e2432b72a5) | Aug 22, 2023 |
| Dell          | Latitude 7430               | Notebook    | [1ccbb8329f](https://linux-hardware.org/?probe=1ccbb8329f) | Aug 22, 2023 |
| Intel         | H61                         | Desktop     | [4d6bf88f48](https://linux-hardware.org/?probe=4d6bf88f48) | Aug 21, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [439b66555d](https://linux-hardware.org/?probe=439b66555d) | Aug 17, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [e11ae0d2b7](https://linux-hardware.org/?probe=e11ae0d2b7) | Aug 17, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [8218626de4](https://linux-hardware.org/?probe=8218626de4) | Aug 06, 2023 |
| Foxconn       | H61MXL/H61MXL-K             | Desktop     | [e51e841817](https://linux-hardware.org/?probe=e51e841817) | Jul 31, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a0a79ddb19](https://linux-hardware.org/?probe=a0a79ddb19) | Jul 27, 2023 |
| MSI           | Z87-G43 GAMING              | Desktop     | [99dadfd3f5](https://linux-hardware.org/?probe=99dadfd3f5) | Jul 21, 2023 |
| MSI           | 2A9C                        | Desktop     | [676f61f0c9](https://linux-hardware.org/?probe=676f61f0c9) | Jul 17, 2023 |
| MSI           | 2A9C                        | Desktop     | [87dd24dabe](https://linux-hardware.org/?probe=87dd24dabe) | Jul 17, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [e6c5dadeef](https://linux-hardware.org/?probe=e6c5dadeef) | Jul 14, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [b72c043646](https://linux-hardware.org/?probe=b72c043646) | Jul 13, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [8c816d8f1b](https://linux-hardware.org/?probe=8c816d8f1b) | Jul 07, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [355ccda3d5](https://linux-hardware.org/?probe=355ccda3d5) | Jul 05, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [354dd05c7f](https://linux-hardware.org/?probe=354dd05c7f) | Jul 01, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [b465607eea](https://linux-hardware.org/?probe=b465607eea) | Jun 30, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [0668932749](https://linux-hardware.org/?probe=0668932749) | Jun 30, 2023 |
| Lenovo        | ThinkPad W520 428425G       | Notebook    | [48d9a1b9fc](https://linux-hardware.org/?probe=48d9a1b9fc) | Jun 26, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [46ed210eb0](https://linux-hardware.org/?probe=46ed210eb0) | Jun 26, 2023 |
| Lenovo        | ThinkPad W520 428425G       | Notebook    | [813d5adfd5](https://linux-hardware.org/?probe=813d5adfd5) | Jun 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [3de2e4c6f9](https://linux-hardware.org/?probe=3de2e4c6f9) | Jun 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [2e6901471f](https://linux-hardware.org/?probe=2e6901471f) | Jun 10, 2023 |
| HP            | 2B34                        | Desktop     | [d0b5c9767f](https://linux-hardware.org/?probe=d0b5c9767f) | Jun 07, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [04e50de864](https://linux-hardware.org/?probe=04e50de864) | May 28, 2023 |
| Lenovo        | ThinkPad E595 20NFS0TH00    | Notebook    | [c843de4a39](https://linux-hardware.org/?probe=c843de4a39) | May 23, 2023 |
| ASUSTek       | N75SF                       | Notebook    | [a385375f4d](https://linux-hardware.org/?probe=a385375f4d) | May 23, 2023 |
| ASUSTek       | P8H67                       | Desktop     | [d1d1ef644d](https://linux-hardware.org/?probe=d1d1ef644d) | May 15, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [2d5e375a3d](https://linux-hardware.org/?probe=2d5e375a3d) | May 09, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [fccfcd375f](https://linux-hardware.org/?probe=fccfcd375f) | May 06, 2023 |
| Foxconn       | H61MXV/H67MXV               | Desktop     | [ffb03b8bd4](https://linux-hardware.org/?probe=ffb03b8bd4) | May 05, 2023 |
| HP            | Notebook                    | Notebook    | [749fa6a38e](https://linux-hardware.org/?probe=749fa6a38e) | May 02, 2023 |
| HP            | Laptop 15-bs1xx             | Notebook    | [e68f2bc46e](https://linux-hardware.org/?probe=e68f2bc46e) | Apr 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [98ffa037d9](https://linux-hardware.org/?probe=98ffa037d9) | Apr 24, 2023 |
| ASUSTek       | Maximus VII FORMULA         | Desktop     | [0d45b24479](https://linux-hardware.org/?probe=0d45b24479) | Apr 23, 2023 |
| Toshiba       | Satellite Pro A100          | Notebook    | [4240870be8](https://linux-hardware.org/?probe=4240870be8) | Apr 19, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [48b2d021fa](https://linux-hardware.org/?probe=48b2d021fa) | Apr 17, 2023 |
| MSI           | G41M-P26                    | Desktop     | [80c102169c](https://linux-hardware.org/?probe=80c102169c) | Apr 16, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [065b7d4c01](https://linux-hardware.org/?probe=065b7d4c01) | Apr 13, 2023 |
| MSI           | G41M-P26                    | Desktop     | [5b6831f7fc](https://linux-hardware.org/?probe=5b6831f7fc) | Apr 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [3792cccd19](https://linux-hardware.org/?probe=3792cccd19) | Apr 11, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [a3ecc0f893](https://linux-hardware.org/?probe=a3ecc0f893) | Apr 07, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [a6e4c91ee0](https://linux-hardware.org/?probe=a6e4c91ee0) | Apr 07, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [e27fc333c6](https://linux-hardware.org/?probe=e27fc333c6) | Apr 05, 2023 |
| ASUSTek       | M5401WUA                    | All in one  | [f6285d1100](https://linux-hardware.org/?probe=f6285d1100) | Apr 03, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [f4b76d1e01](https://linux-hardware.org/?probe=f4b76d1e01) | Apr 03, 2023 |
| Toshiba       | Satellite C55-B             | Notebook    | [da341e3be8](https://linux-hardware.org/?probe=da341e3be8) | Apr 02, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [aa74b25c97](https://linux-hardware.org/?probe=aa74b25c97) | Apr 02, 2023 |
| Dell          | Latitude E7470              | Notebook    | [ee66bc49a5](https://linux-hardware.org/?probe=ee66bc49a5) | Apr 01, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [7ff133a50e](https://linux-hardware.org/?probe=7ff133a50e) | Mar 27, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [6b3c579924](https://linux-hardware.org/?probe=6b3c579924) | Mar 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [3711318620](https://linux-hardware.org/?probe=3711318620) | Mar 26, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [69e58cde56](https://linux-hardware.org/?probe=69e58cde56) | Mar 23, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [2be6f0d943](https://linux-hardware.org/?probe=2be6f0d943) | Mar 22, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [015c8dac04](https://linux-hardware.org/?probe=015c8dac04) | Mar 21, 2023 |
| Dell          | 07N90W A02                  | Desktop     | [267dad60ba](https://linux-hardware.org/?probe=267dad60ba) | Mar 18, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [314245636a](https://linux-hardware.org/?probe=314245636a) | Mar 18, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [6752797fe9](https://linux-hardware.org/?probe=6752797fe9) | Mar 14, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [2e0019e450](https://linux-hardware.org/?probe=2e0019e450) | Mar 14, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [57a009cdd4](https://linux-hardware.org/?probe=57a009cdd4) | Feb 25, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [fc1a3d88ae](https://linux-hardware.org/?probe=fc1a3d88ae) | Feb 25, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [91c8d45121](https://linux-hardware.org/?probe=91c8d45121) | Feb 24, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [f6b6b24623](https://linux-hardware.org/?probe=f6b6b24623) | Feb 24, 2023 |
| Dell          | Latitude E7470              | Notebook    | [6b5f9db086](https://linux-hardware.org/?probe=6b5f9db086) | Feb 21, 2023 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [fd2b985f41](https://linux-hardware.org/?probe=fd2b985f41) | Feb 21, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [28a0794b08](https://linux-hardware.org/?probe=28a0794b08) | Feb 20, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [e87f489185](https://linux-hardware.org/?probe=e87f489185) | Feb 20, 2023 |
| HP            | Notebook                    | Notebook    | [2c17c1256f](https://linux-hardware.org/?probe=2c17c1256f) | Feb 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [515525584c](https://linux-hardware.org/?probe=515525584c) | Feb 14, 2023 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [c69ee15636](https://linux-hardware.org/?probe=c69ee15636) | Feb 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [46981444b1](https://linux-hardware.org/?probe=46981444b1) | Feb 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [ce78e6cdb9](https://linux-hardware.org/?probe=ce78e6cdb9) | Feb 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [f5e5e27e8e](https://linux-hardware.org/?probe=f5e5e27e8e) | Feb 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [cb0a834e1a](https://linux-hardware.org/?probe=cb0a834e1a) | Feb 10, 2023 |
| ASRock        | H81M-GL                     | Desktop     | [059a818847](https://linux-hardware.org/?probe=059a818847) | Feb 09, 2023 |
| Dell          | Latitude E7470              | Notebook    | [5c8d26c4ff](https://linux-hardware.org/?probe=5c8d26c4ff) | Feb 05, 2023 |
| Dell          | Latitude E7470              | Notebook    | [d68227808b](https://linux-hardware.org/?probe=d68227808b) | Feb 05, 2023 |
| HP            | 1589                        | Desktop     | [1872d63c2b](https://linux-hardware.org/?probe=1872d63c2b) | Feb 05, 2023 |
| HP            | 1589                        | Desktop     | [69c0ab962c](https://linux-hardware.org/?probe=69c0ab962c) | Feb 05, 2023 |
| HP            | EliteBook Revolve 810 G3    | Notebook    | [1f55ca148f](https://linux-hardware.org/?probe=1f55ca148f) | Jan 30, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [4042b92ee1](https://linux-hardware.org/?probe=4042b92ee1) | Jan 29, 2023 |
| HP            | 18E7                        | Desktop     | [01cbafc241](https://linux-hardware.org/?probe=01cbafc241) | Jan 28, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [f1f0543123](https://linux-hardware.org/?probe=f1f0543123) | Jan 28, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [b2eb47268c](https://linux-hardware.org/?probe=b2eb47268c) | Jan 27, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [6a8408404e](https://linux-hardware.org/?probe=6a8408404e) | Jan 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [5169fb5013](https://linux-hardware.org/?probe=5169fb5013) | Jan 17, 2023 |
| Acer          | Aspire M3-581T              | Notebook    | [f0ed3b4989](https://linux-hardware.org/?probe=f0ed3b4989) | Jan 14, 2023 |
| MSI           | H270-A PRO                  | Desktop     | [f150327257](https://linux-hardware.org/?probe=f150327257) | Jan 14, 2023 |
| Acer          | Calpella                    | Notebook    | [108843a25a](https://linux-hardware.org/?probe=108843a25a) | Jan 14, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [9cc37ff271](https://linux-hardware.org/?probe=9cc37ff271) | Jan 09, 2023 |
| HP            | Pavilion dv6000 (GA131UA... | Notebook    | [115a479990](https://linux-hardware.org/?probe=115a479990) | Jan 05, 2023 |
| Sony          | VGN-NS10J_S                 | Notebook    | [3789038010](https://linux-hardware.org/?probe=3789038010) | Jan 04, 2023 |
| MSI           | Z87-G45 GAMING              | Desktop     | [c2d592a9e5](https://linux-hardware.org/?probe=c2d592a9e5) | Dec 30, 2022 |
| Toshiba       | Satellite C55-B             | Notebook    | [8f81c02bbf](https://linux-hardware.org/?probe=8f81c02bbf) | Dec 21, 2022 |
| Dell          | Inspiron N7010              | Notebook    | [de5dc0c3ea](https://linux-hardware.org/?probe=de5dc0c3ea) | Dec 17, 2022 |
| HP            | EliteBook Revolve 810 G3    | Notebook    | [3b340e6b29](https://linux-hardware.org/?probe=3b340e6b29) | Dec 16, 2022 |
| Dell          | Latitude 5480               | Notebook    | [01c96ca524](https://linux-hardware.org/?probe=01c96ca524) | Dec 11, 2022 |
| HP            | EliteBook Revolve 810 G3    | Notebook    | [ca043cff45](https://linux-hardware.org/?probe=ca043cff45) | Nov 30, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [20219ca82a](https://linux-hardware.org/?probe=20219ca82a) | Nov 29, 2022 |
| HP            | EliteBook Revolve 810 G3    | Notebook    | [08d7f00868](https://linux-hardware.org/?probe=08d7f00868) | Nov 24, 2022 |
| sunxi         | LeMaker Banana Pi           | Soc         | [56f65f30b3](https://linux-hardware.org/?probe=56f65f30b3) | Nov 24, 2022 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [67cc68fbfe](https://linux-hardware.org/?probe=67cc68fbfe) | Nov 23, 2022 |
| HP            | EliteBook Revolve 810 G3    | Notebook    | [da02cb82bf](https://linux-hardware.org/?probe=da02cb82bf) | Nov 23, 2022 |
| ASUSTek       | S300CA                      | Notebook    | [3efc297b44](https://linux-hardware.org/?probe=3efc297b44) | Nov 23, 2022 |
| ECS           | G41T-M7                     | Desktop     | [f97036df33](https://linux-hardware.org/?probe=f97036df33) | Nov 18, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [cae1dbbb12](https://linux-hardware.org/?probe=cae1dbbb12) | Nov 12, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [64c65685da](https://linux-hardware.org/?probe=64c65685da) | Nov 03, 2022 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [5dbeb8f7dd](https://linux-hardware.org/?probe=5dbeb8f7dd) | Nov 03, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [6c979bdf58](https://linux-hardware.org/?probe=6c979bdf58) | Oct 27, 2022 |
| Unknown       | X79                         | Desktop     | [fd8f23bc70](https://linux-hardware.org/?probe=fd8f23bc70) | Oct 21, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [4727244665](https://linux-hardware.org/?probe=4727244665) | Oct 18, 2022 |
| ECS           | G41T-M7                     | Desktop     | [3abe70653e](https://linux-hardware.org/?probe=3abe70653e) | Oct 16, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [6a0a056c36](https://linux-hardware.org/?probe=6a0a056c36) | Oct 15, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [fefb833511](https://linux-hardware.org/?probe=fefb833511) | Oct 14, 2022 |
| Dell          | Precision M4800             | Notebook    | [be05dcbe15](https://linux-hardware.org/?probe=be05dcbe15) | Oct 08, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [7d65aefb93](https://linux-hardware.org/?probe=7d65aefb93) | Oct 06, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [719ac47bc6](https://linux-hardware.org/?probe=719ac47bc6) | Oct 06, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [d547ed6f83](https://linux-hardware.org/?probe=d547ed6f83) | Sep 30, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [9781419cc1](https://linux-hardware.org/?probe=9781419cc1) | Sep 30, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [cd06f54882](https://linux-hardware.org/?probe=cd06f54882) | Sep 30, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [4308420b28](https://linux-hardware.org/?probe=4308420b28) | Sep 27, 2022 |
| Gigabyte      | H61M-S2P-R3                 | Desktop     | [21d9eb0a71](https://linux-hardware.org/?probe=21d9eb0a71) | Sep 26, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [e78a82387b](https://linux-hardware.org/?probe=e78a82387b) | Sep 24, 2022 |
| Dell          | Latitude 7480               | Notebook    | [e1a3ca1d32](https://linux-hardware.org/?probe=e1a3ca1d32) | Sep 22, 2022 |
| HP            | 2B34                        | Desktop     | [a9e82bbb40](https://linux-hardware.org/?probe=a9e82bbb40) | Sep 19, 2022 |
| Lenovo        | ThinkPad X230 2325CZ1       | Notebook    | [b484febc13](https://linux-hardware.org/?probe=b484febc13) | Sep 17, 2022 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [e61fe6932b](https://linux-hardware.org/?probe=e61fe6932b) | Sep 13, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [3b1c07d561](https://linux-hardware.org/?probe=3b1c07d561) | Sep 01, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [26c9be116e](https://linux-hardware.org/?probe=26c9be116e) | Aug 24, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [1f4f742288](https://linux-hardware.org/?probe=1f4f742288) | Aug 23, 2022 |
| Gigabyte      | H61M-S2PT                   | Desktop     | [b7e6228017](https://linux-hardware.org/?probe=b7e6228017) | Aug 22, 2022 |
| HP            | Pavilion dm3                | Notebook    | [7152a48ede](https://linux-hardware.org/?probe=7152a48ede) | Aug 10, 2022 |
| Acer          | Aspire 7741                 | Notebook    | [02e9f6a808](https://linux-hardware.org/?probe=02e9f6a808) | Jul 29, 2022 |
| Foxconn       | H61MXL/H61MXL-K             | Desktop     | [708f9572ad](https://linux-hardware.org/?probe=708f9572ad) | Jul 26, 2022 |
| ECS           | G41T-M16                    | Desktop     | [5a3363d66f](https://linux-hardware.org/?probe=5a3363d66f) | Jun 28, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [e478f31175](https://linux-hardware.org/?probe=e478f31175) | Jun 25, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [4eadb7ee17](https://linux-hardware.org/?probe=4eadb7ee17) | Jun 19, 2022 |
| ASUSTek       | M5401WUA                    | All in one  | [fd9f1b2ef6](https://linux-hardware.org/?probe=fd9f1b2ef6) | Jun 17, 2022 |
| Dell          | Inspiron N7010              | Notebook    | [149eb0bab7](https://linux-hardware.org/?probe=149eb0bab7) | Jun 14, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [9ff02a8c0c](https://linux-hardware.org/?probe=9ff02a8c0c) | Jun 12, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [9273aa4844](https://linux-hardware.org/?probe=9273aa4844) | Jun 12, 2022 |
| ASUSTek       | X551CA                      | Notebook    | [15532b1663](https://linux-hardware.org/?probe=15532b1663) | Jun 07, 2022 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [0dd5791ff8](https://linux-hardware.org/?probe=0dd5791ff8) | Jun 05, 2022 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [1b7a237b9b](https://linux-hardware.org/?probe=1b7a237b9b) | Jun 05, 2022 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [9f18dbe621](https://linux-hardware.org/?probe=9f18dbe621) | May 26, 2022 |
| HP            | ProBook 4720s               | Notebook    | [887ea9cd89](https://linux-hardware.org/?probe=887ea9cd89) | May 16, 2022 |
| HP            | ProBook 4720s               | Notebook    | [09bb5a5088](https://linux-hardware.org/?probe=09bb5a5088) | May 16, 2022 |
| ASUSTek       | X205TAW                     | Notebook    | [57d9d59b56](https://linux-hardware.org/?probe=57d9d59b56) | May 13, 2022 |
| ASUSTek       | X205TAW                     | Notebook    | [577c71e530](https://linux-hardware.org/?probe=577c71e530) | May 06, 2022 |
| Biostar       | H61MLV2                     | Desktop     | [43a89f5d91](https://linux-hardware.org/?probe=43a89f5d91) | Apr 14, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [95d53f5fc0](https://linux-hardware.org/?probe=95d53f5fc0) | Mar 31, 2022 |
| Dell          | 07N90W A02                  | Desktop     | [4fd59735d6](https://linux-hardware.org/?probe=4fd59735d6) | Mar 30, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [698654a73f](https://linux-hardware.org/?probe=698654a73f) | Mar 26, 2022 |
| Foxconn       | G41MXE/G41MXE-K             | Desktop     | [cd5c0f974e](https://linux-hardware.org/?probe=cd5c0f974e) | Mar 18, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [4f7aa0f57c](https://linux-hardware.org/?probe=4f7aa0f57c) | Mar 10, 2022 |
| Acer          | Aspire E5-511               | Notebook    | [00e72ee0ce](https://linux-hardware.org/?probe=00e72ee0ce) | Mar 04, 2022 |
| Lenovo        | B50-70 20384                | Notebook    | [eb4abb6e15](https://linux-hardware.org/?probe=eb4abb6e15) | Mar 02, 2022 |
| Packard Be... | DOT S                       | Notebook    | [4110664747](https://linux-hardware.org/?probe=4110664747) | Mar 02, 2022 |
| Lenovo        | B50-70 20384                | Notebook    | [9d0a21adb1](https://linux-hardware.org/?probe=9d0a21adb1) | Mar 02, 2022 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [7bdf3a8998](https://linux-hardware.org/?probe=7bdf3a8998) | Feb 27, 2022 |
| HP            | 630                         | Notebook    | [6bf505d86b](https://linux-hardware.org/?probe=6bf505d86b) | Feb 26, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [214381cf00](https://linux-hardware.org/?probe=214381cf00) | Feb 16, 2022 |
| Lenovo        | 0B98417 PRO                 | Desktop     | [6e5fa50531](https://linux-hardware.org/?probe=6e5fa50531) | Feb 13, 2022 |
| Intel         | H55                         | Desktop     | [1b1b5c3ed8](https://linux-hardware.org/?probe=1b1b5c3ed8) | Feb 12, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [3f5b85f478](https://linux-hardware.org/?probe=3f5b85f478) | Feb 07, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [9f4f77f51d](https://linux-hardware.org/?probe=9f4f77f51d) | Feb 06, 2022 |
| Dell          | Latitude E7440              | Notebook    | [03d4a4af15](https://linux-hardware.org/?probe=03d4a4af15) | Feb 05, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [b6d5344f4e](https://linux-hardware.org/?probe=b6d5344f4e) | Feb 04, 2022 |
| MSI           | H61M-S20                    | Desktop     | [7d0384b2d2](https://linux-hardware.org/?probe=7d0384b2d2) | Jan 28, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [3253470667](https://linux-hardware.org/?probe=3253470667) | Jan 22, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [0d6dacc5dc](https://linux-hardware.org/?probe=0d6dacc5dc) | Jan 20, 2022 |
| ECS           | H61H2-M4                    | Desktop     | [2995a79728](https://linux-hardware.org/?probe=2995a79728) | Jan 07, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [8834da8d25](https://linux-hardware.org/?probe=8834da8d25) | Jan 02, 2022 |
| Unknown       | X79                         | Desktop     | [ec1620ee82](https://linux-hardware.org/?probe=ec1620ee82) | Jan 01, 2022 |
| Dell          | Inspiron 3520               | Notebook    | [33df9edd07](https://linux-hardware.org/?probe=33df9edd07) | Dec 25, 2021 |
| LDLC          | Mercure MH                  | Notebook    | [ff094fa4f3](https://linux-hardware.org/?probe=ff094fa4f3) | Dec 23, 2021 |
| Sony          | VGN-AW21M_H                 | Notebook    | [b4cf74ec7d](https://linux-hardware.org/?probe=b4cf74ec7d) | Dec 23, 2021 |
| ASUSTek       | X55U                        | Notebook    | [6260fe5ca9](https://linux-hardware.org/?probe=6260fe5ca9) | Dec 13, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [5cd58ae5d9](https://linux-hardware.org/?probe=5cd58ae5d9) | Dec 12, 2021 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [69ecf03c84](https://linux-hardware.org/?probe=69ecf03c84) | Dec 12, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [dfa992fc24](https://linux-hardware.org/?probe=dfa992fc24) | Dec 12, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [15e97e023d](https://linux-hardware.org/?probe=15e97e023d) | Dec 12, 2021 |
| ASUSTek       | X555LAB                     | Notebook    | [c07bccb6c7](https://linux-hardware.org/?probe=c07bccb6c7) | Dec 07, 2021 |
| Sony          | SVF1531GSFB                 | Notebook    | [fb251b93e9](https://linux-hardware.org/?probe=fb251b93e9) | Dec 04, 2021 |
| MSI           | H61M-S20                    | Desktop     | [5e73200702](https://linux-hardware.org/?probe=5e73200702) | Dec 02, 2021 |
| MSI           | H61M-S20                    | Desktop     | [7e1fdb578c](https://linux-hardware.org/?probe=7e1fdb578c) | Dec 02, 2021 |
| ASUSTek       | K50IE                       | Notebook    | [49a6b75a43](https://linux-hardware.org/?probe=49a6b75a43) | Nov 29, 2021 |
| Foxconn       | 17A0                        | Desktop     | [0fc17817a1](https://linux-hardware.org/?probe=0fc17817a1) | Nov 23, 2021 |
| Dell          | Latitude E7240              | Notebook    | [e26d674874](https://linux-hardware.org/?probe=e26d674874) | Nov 14, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [233d576651](https://linux-hardware.org/?probe=233d576651) | Nov 12, 2021 |
| Foxconn       | H61M/H61M-S                 | Desktop     | [62ae26dca0](https://linux-hardware.org/?probe=62ae26dca0) | Nov 07, 2021 |
| Foxconn       | H61M/H61M-S                 | Desktop     | [7f3894059d](https://linux-hardware.org/?probe=7f3894059d) | Nov 04, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [0862dc626b](https://linux-hardware.org/?probe=0862dc626b) | Oct 29, 2021 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [545b983e7c](https://linux-hardware.org/?probe=545b983e7c) | Oct 22, 2021 |
| Unknown       | G41 Series V10              | Desktop     | [ce791f779f](https://linux-hardware.org/?probe=ce791f779f) | Oct 21, 2021 |
| Pegatron      | 2A94h                       | Desktop     | [ebd6264587](https://linux-hardware.org/?probe=ebd6264587) | Oct 19, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [a629aeaa1b](https://linux-hardware.org/?probe=a629aeaa1b) | Oct 15, 2021 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [9855c138d4](https://linux-hardware.org/?probe=9855c138d4) | Oct 11, 2021 |
| MSI           | H61M-S20                    | Desktop     | [9669908158](https://linux-hardware.org/?probe=9669908158) | Sep 29, 2021 |
| MSI           | H61M-S20                    | Desktop     | [481ecaa854](https://linux-hardware.org/?probe=481ecaa854) | Sep 28, 2021 |
| Lenovo        | B50-70 20384                | Notebook    | [8641901755](https://linux-hardware.org/?probe=8641901755) | Sep 27, 2021 |
| Lenovo        | 0x30F617AA NOK              | Desktop     | [d986a2e532](https://linux-hardware.org/?probe=d986a2e532) | Sep 26, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [3b43d9b42f](https://linux-hardware.org/?probe=3b43d9b42f) | Sep 22, 2021 |
| Lenovo        | G560 20042                  | Notebook    | [a31437072c](https://linux-hardware.org/?probe=a31437072c) | Sep 20, 2021 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [1c77028990](https://linux-hardware.org/?probe=1c77028990) | Sep 18, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [b740654686](https://linux-hardware.org/?probe=b740654686) | Sep 17, 2021 |
| ASRock        | K10N78FullHD-hSLI           | Desktop     | [e817658118](https://linux-hardware.org/?probe=e817658118) | Sep 10, 2021 |
| Sony          | SVE1713A6EW                 | Notebook    | [b8661880d2](https://linux-hardware.org/?probe=b8661880d2) | Sep 07, 2021 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [95d654f778](https://linux-hardware.org/?probe=95d654f778) | Sep 04, 2021 |
| ASRock        | K10N78FullHD-hSLI           | Desktop     | [78886ef280](https://linux-hardware.org/?probe=78886ef280) | Aug 31, 2021 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [82aceb2458](https://linux-hardware.org/?probe=82aceb2458) | Aug 30, 2021 |
| HP            | 15                          | Notebook    | [5520042e14](https://linux-hardware.org/?probe=5520042e14) | Aug 28, 2021 |
| HP            | 15                          | Notebook    | [cc4e936b38](https://linux-hardware.org/?probe=cc4e936b38) | Aug 26, 2021 |
| Lenovo        | B50-70 20384                | Notebook    | [8a71545b54](https://linux-hardware.org/?probe=8a71545b54) | Aug 26, 2021 |
| Lenovo        | B50-70 20384                | Notebook    | [297e2e187c](https://linux-hardware.org/?probe=297e2e187c) | Aug 25, 2021 |
| ECS           | P4M900T-M2                  | Desktop     | [b1490652d3](https://linux-hardware.org/?probe=b1490652d3) | Aug 20, 2021 |
| HP            | ProBook 450 G6              | Notebook    | [47ed88595b](https://linux-hardware.org/?probe=47ed88595b) | Aug 20, 2021 |
| Sony          | SVE1713A6EW                 | Notebook    | [cf362e966f](https://linux-hardware.org/?probe=cf362e966f) | Aug 19, 2021 |
| Acer          | Aspire A515-56G             | Notebook    | [795edc5779](https://linux-hardware.org/?probe=795edc5779) | Aug 15, 2021 |
| Dell          | Latitude E6400              | Notebook    | [eb029acad6](https://linux-hardware.org/?probe=eb029acad6) | Aug 12, 2021 |
| Dell          | Latitude E5430 vPro         | Notebook    | [84199b59aa](https://linux-hardware.org/?probe=84199b59aa) | Aug 10, 2021 |
| Dell          | Latitude E5430 vPro         | Notebook    | [a4be1b3322](https://linux-hardware.org/?probe=a4be1b3322) | Aug 10, 2021 |
| MSI           | CR610M                      | Notebook    | [68759b0315](https://linux-hardware.org/?probe=68759b0315) | Aug 08, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [007cd499bf](https://linux-hardware.org/?probe=007cd499bf) | Aug 06, 2021 |
| Lenovo        | G560 20042                  | Notebook    | [405dddebf5](https://linux-hardware.org/?probe=405dddebf5) | Aug 05, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [57037eb714](https://linux-hardware.org/?probe=57037eb714) | Aug 05, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [89852ab731](https://linux-hardware.org/?probe=89852ab731) | Aug 05, 2021 |
| Dell          | Latitude 7380               | Notebook    | [c83f32076d](https://linux-hardware.org/?probe=c83f32076d) | Aug 05, 2021 |
| Dell          | 0WG864                      | Desktop     | [2e28996126](https://linux-hardware.org/?probe=2e28996126) | Jul 28, 2021 |
| Acer          | Aspire A515-56G             | Notebook    | [185f27f184](https://linux-hardware.org/?probe=185f27f184) | Jul 22, 2021 |
| Foxconn       | H61MXT1/F2/-S/-V            | Desktop     | [cf7ebc455f](https://linux-hardware.org/?probe=cf7ebc455f) | Jul 20, 2021 |
| Dell          | Latitude E7440              | Notebook    | [d8fd7fe06d](https://linux-hardware.org/?probe=d8fd7fe06d) | Jul 20, 2021 |
| Intel         | H55                         | Desktop     | [47c7c454ac](https://linux-hardware.org/?probe=47c7c454ac) | Jul 09, 2021 |
| Intel         | H55                         | Desktop     | [9e4504d3a3](https://linux-hardware.org/?probe=9e4504d3a3) | Jul 09, 2021 |
| Dell          | Latitude 7480               | Notebook    | [28d1d17f13](https://linux-hardware.org/?probe=28d1d17f13) | Jun 22, 2021 |
| HP            | 2B34                        | Desktop     | [d2c91c450b](https://linux-hardware.org/?probe=d2c91c450b) | May 31, 2021 |
| MSI           | ZH77A-G41                   | Desktop     | [8755040ea2](https://linux-hardware.org/?probe=8755040ea2) | May 25, 2021 |
| Toshiba       | Satellite C50-A539          | Notebook    | [c6c8ae87d9](https://linux-hardware.org/?probe=c6c8ae87d9) | May 25, 2021 |
| Unknown       | Unknown                     | Desktop     | [f54143a81d](https://linux-hardware.org/?probe=f54143a81d) | May 24, 2021 |
| Toshiba       | Satellite C50-A545          | Notebook    | [8a9dc6ab53](https://linux-hardware.org/?probe=8a9dc6ab53) | May 24, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [36b88b7391](https://linux-hardware.org/?probe=36b88b7391) | May 23, 2021 |
| Toshiba       | Satellite C50-A545          | Notebook    | [34c12e6041](https://linux-hardware.org/?probe=34c12e6041) | May 18, 2021 |
| Toshiba       | Satellite C50-A545          | Notebook    | [d91a5890c9](https://linux-hardware.org/?probe=d91a5890c9) | May 18, 2021 |
| Toshiba       | Satellite C50-A545          | Notebook    | [d12a52a705](https://linux-hardware.org/?probe=d12a52a705) | May 14, 2021 |
| Dell          | Inspiron 3576               | Notebook    | [be3e7aa080](https://linux-hardware.org/?probe=be3e7aa080) | May 09, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [0252beb838](https://linux-hardware.org/?probe=0252beb838) | May 04, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [bd06d6bb56](https://linux-hardware.org/?probe=bd06d6bb56) | May 04, 2021 |
| HP            | 2B34                        | Desktop     | [861a11fe04](https://linux-hardware.org/?probe=861a11fe04) | May 04, 2021 |
| HP            | 2B34                        | Desktop     | [66faef6161](https://linux-hardware.org/?probe=66faef6161) | May 02, 2021 |
| Lenovo        | G560 20042                  | Notebook    | [62fc21894d](https://linux-hardware.org/?probe=62fc21894d) | Apr 28, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [7a97f404a4](https://linux-hardware.org/?probe=7a97f404a4) | Apr 24, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [ba300d050b](https://linux-hardware.org/?probe=ba300d050b) | Apr 24, 2021 |
| Lenovo        | G560 20042                  | Notebook    | [7a72fc45b4](https://linux-hardware.org/?probe=7a72fc45b4) | Apr 22, 2021 |
| Apple         | MacBookPro8,2               | Notebook    | [b46bb85400](https://linux-hardware.org/?probe=b46bb85400) | Apr 21, 2021 |
| Dell          | Latitude E7440              | Notebook    | [4acb0ea358](https://linux-hardware.org/?probe=4acb0ea358) | Apr 19, 2021 |
| eMachines     | eME732                      | Notebook    | [a48b0c422f](https://linux-hardware.org/?probe=a48b0c422f) | Apr 19, 2021 |
| eMachines     | eME732                      | Notebook    | [6fd83225c1](https://linux-hardware.org/?probe=6fd83225c1) | Apr 18, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [2953bef8d1](https://linux-hardware.org/?probe=2953bef8d1) | Apr 18, 2021 |
| ECS           | P4M900T-M2                  | Desktop     | [f3b2236c7a](https://linux-hardware.org/?probe=f3b2236c7a) | Apr 15, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [8e5a3a6e19](https://linux-hardware.org/?probe=8e5a3a6e19) | Apr 05, 2021 |
| Fujitsu       | LIFEBOOK A532               | Notebook    | [843dae0f43](https://linux-hardware.org/?probe=843dae0f43) | Apr 04, 2021 |
| MSI           | Z77A-G43                    | Desktop     | [2df99824aa](https://linux-hardware.org/?probe=2df99824aa) | Apr 03, 2021 |
| Toshiba       | PORTEGE R30-A               | Notebook    | [765ae993b9](https://linux-hardware.org/?probe=765ae993b9) | Mar 16, 2021 |
| ECS           | H61H2-MV                    | Desktop     | [6408cdb8b2](https://linux-hardware.org/?probe=6408cdb8b2) | Mar 14, 2021 |
| Lenovo        | ThinkPad X201 3680AQ1       | Notebook    | [210d440087](https://linux-hardware.org/?probe=210d440087) | Mar 13, 2021 |
| Lenovo        | ThinkPad X201 3680AQ1       | Notebook    | [a9068d7ec4](https://linux-hardware.org/?probe=a9068d7ec4) | Mar 12, 2021 |
| Lenovo        | G580 2189                   | Notebook    | [387b714e2f](https://linux-hardware.org/?probe=387b714e2f) | Mar 12, 2021 |
| Unknown       | Unknown                     | Desktop     | [5f41497264](https://linux-hardware.org/?probe=5f41497264) | Mar 02, 2021 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [5cf7ce91a7](https://linux-hardware.org/?probe=5cf7ce91a7) | Mar 01, 2021 |
| Acer          | Extensa 2508                | Notebook    | [7fb16dc91b](https://linux-hardware.org/?probe=7fb16dc91b) | Feb 28, 2021 |
| Lenovo        | ThinkPad X201 3680AQ1       | Notebook    | [0eb94c0487](https://linux-hardware.org/?probe=0eb94c0487) | Feb 26, 2021 |
| Lenovo        | ThinkPad X201 3680AQ1       | Notebook    | [5582abd577](https://linux-hardware.org/?probe=5582abd577) | Feb 26, 2021 |
| Lenovo        | ThinkPad X260 20F5S1G104    | Notebook    | [97f3e486f0](https://linux-hardware.org/?probe=97f3e486f0) | Feb 22, 2021 |
| Lenovo        | ThinkPad X260 20F5S1G104    | Notebook    | [d4273cb949](https://linux-hardware.org/?probe=d4273cb949) | Feb 22, 2021 |
| Samsung       | N102SP/N100SP/N101SP        | Notebook    | [7ec7f64225](https://linux-hardware.org/?probe=7ec7f64225) | Feb 20, 2021 |
| Sony          | SVE1513K1EW                 | Notebook    | [35ca18e322](https://linux-hardware.org/?probe=35ca18e322) | Feb 18, 2021 |
| Sony          | SVE1513K1EW                 | Notebook    | [67702a7546](https://linux-hardware.org/?probe=67702a7546) | Feb 17, 2021 |
| HP            | ProBook 4540s               | Notebook    | [f6618c225b](https://linux-hardware.org/?probe=f6618c225b) | Feb 16, 2021 |
| Acer          | Aspire 5738                 | Notebook    | [c107fc9c40](https://linux-hardware.org/?probe=c107fc9c40) | Feb 15, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [74fb8b5b1d](https://linux-hardware.org/?probe=74fb8b5b1d) | Feb 14, 2021 |
| ECS           | H61H2-MV                    | Desktop     | [da10465006](https://linux-hardware.org/?probe=da10465006) | Feb 08, 2021 |
| ECS           | H61H2-MV                    | Desktop     | [b050103b48](https://linux-hardware.org/?probe=b050103b48) | Feb 04, 2021 |
| ECS           | H61H2-MV                    | Desktop     | [8c36c3c601](https://linux-hardware.org/?probe=8c36c3c601) | Feb 03, 2021 |
| Gigabyte      | H61M-S2P-R3                 | Desktop     | [807a0ea003](https://linux-hardware.org/?probe=807a0ea003) | Jan 31, 2021 |
| Dell          | Precision M6600             | Notebook    | [3731eb952c](https://linux-hardware.org/?probe=3731eb952c) | Jan 29, 2021 |
| Acer          | Aspire V5-571               | Notebook    | [74f0d86e1e](https://linux-hardware.org/?probe=74f0d86e1e) | Jan 28, 2021 |
| Dell          | Precision M6600             | Notebook    | [105a9a66c3](https://linux-hardware.org/?probe=105a9a66c3) | Jan 23, 2021 |
| Dell          | Precision M6600             | Notebook    | [84d3a754fb](https://linux-hardware.org/?probe=84d3a754fb) | Jan 23, 2021 |
| Sony          | VPCEH2H1E                   | Notebook    | [891e9364e0](https://linux-hardware.org/?probe=891e9364e0) | Jan 14, 2021 |
| Gigabyte      | H61M-S2P-R3                 | Desktop     | [9286a611a0](https://linux-hardware.org/?probe=9286a611a0) | Jan 04, 2021 |
| Dell          | Inspiron 3543               | Notebook    | [aae61a1ca3](https://linux-hardware.org/?probe=aae61a1ca3) | Dec 22, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [ce37e65007](https://linux-hardware.org/?probe=ce37e65007) | Dec 21, 2020 |
| Biostar       | P4M89-M7B Ver:1.0           | Desktop     | [cf12b04ead](https://linux-hardware.org/?probe=cf12b04ead) | Dec 21, 2020 |
| Lenovo        | G50-30 80G0                 | Notebook    | [9e347f10ee](https://linux-hardware.org/?probe=9e347f10ee) | Dec 12, 2020 |
| Unknown       | Unknown                     | Desktop     | [83507a1ac0](https://linux-hardware.org/?probe=83507a1ac0) | Dec 11, 2020 |
| Unknown       | Unknown                     | Desktop     | [688a7e3a73](https://linux-hardware.org/?probe=688a7e3a73) | Dec 11, 2020 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [3bab146c4c](https://linux-hardware.org/?probe=3bab146c4c) | Dec 10, 2020 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [997a066f37](https://linux-hardware.org/?probe=997a066f37) | Dec 08, 2020 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [356e5f32f8](https://linux-hardware.org/?probe=356e5f32f8) | Dec 08, 2020 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [8dec91d656](https://linux-hardware.org/?probe=8dec91d656) | Dec 01, 2020 |
| Dell          | Vostro 3500                 | Notebook    | [a76707659b](https://linux-hardware.org/?probe=a76707659b) | Nov 29, 2020 |
| Dell          | 0T656F A02                  | Desktop     | [668f859641](https://linux-hardware.org/?probe=668f859641) | Nov 28, 2020 |
| Gigabyte      | P61A-D3                     | Desktop     | [c547f76923](https://linux-hardware.org/?probe=c547f76923) | Nov 21, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [cfbfec849d](https://linux-hardware.org/?probe=cfbfec849d) | Nov 21, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [97d5763d6b](https://linux-hardware.org/?probe=97d5763d6b) | Nov 21, 2020 |
| Acer          | Aspire 5738                 | Notebook    | [4ead657ec9](https://linux-hardware.org/?probe=4ead657ec9) | Nov 21, 2020 |
| Unknown       | Unknown                     | Desktop     | [a9f4ce29b9](https://linux-hardware.org/?probe=a9f4ce29b9) | Nov 15, 2020 |
| MSI           | G41M-P33 Combo              | Desktop     | [36ffd6debb](https://linux-hardware.org/?probe=36ffd6debb) | Nov 13, 2020 |
| Unknown       | Unknown                     | Desktop     | [51b974180e](https://linux-hardware.org/?probe=51b974180e) | Nov 11, 2020 |
| Acer          | Aspire F5-572               | Notebook    | [1bbbaf1f8c](https://linux-hardware.org/?probe=1bbbaf1f8c) | Oct 31, 2020 |
| HP            | EliteBook Folio 9470m       | Notebook    | [39251e283c](https://linux-hardware.org/?probe=39251e283c) | Oct 29, 2020 |
| HP            | ProBook 450 G0              | Notebook    | [85e77f85c7](https://linux-hardware.org/?probe=85e77f85c7) | Oct 26, 2020 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [230a4dff71](https://linux-hardware.org/?probe=230a4dff71) | Oct 26, 2020 |
| HP            | ProBook 4540s               | Notebook    | [e2bb03b7da](https://linux-hardware.org/?probe=e2bb03b7da) | Oct 23, 2020 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [1425d1ebde](https://linux-hardware.org/?probe=1425d1ebde) | Oct 20, 2020 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [f1040f264c](https://linux-hardware.org/?probe=f1040f264c) | Oct 19, 2020 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [6a54c56b7a](https://linux-hardware.org/?probe=6a54c56b7a) | Oct 19, 2020 |
| HP            | ProBook 4540s               | Notebook    | [b369817417](https://linux-hardware.org/?probe=b369817417) | Oct 15, 2020 |
| Lenovo        | G50-30 80G0                 | Notebook    | [b12687c62b](https://linux-hardware.org/?probe=b12687c62b) | Oct 12, 2020 |
| Sony          | VPCEH2H1E                   | Notebook    | [07077a7194](https://linux-hardware.org/?probe=07077a7194) | Oct 02, 2020 |
| Sony          | VPCEH2H1E                   | Notebook    | [c35dfa149d](https://linux-hardware.org/?probe=c35dfa149d) | Sep 24, 2020 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [1efd90cecb](https://linux-hardware.org/?probe=1efd90cecb) | Sep 20, 2020 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [ebaa6b30e4](https://linux-hardware.org/?probe=ebaa6b30e4) | Sep 20, 2020 |
| HP            | 3397                        | Desktop     | [5232568c4a](https://linux-hardware.org/?probe=5232568c4a) | Sep 06, 2020 |
| ASRock        | X470 Taichi                 | Desktop     | [ec99eca757](https://linux-hardware.org/?probe=ec99eca757) | Sep 03, 2020 |
| Acer          | Aspire F5-572               | Notebook    | [9ab161c8d7](https://linux-hardware.org/?probe=9ab161c8d7) | Sep 03, 2020 |
| ECS           | P4M900T-M2                  | Desktop     | [c4e5d02631](https://linux-hardware.org/?probe=c4e5d02631) | Sep 02, 2020 |
| HP            | ZBook 15 G4                 | Notebook    | [c36d170750](https://linux-hardware.org/?probe=c36d170750) | Aug 27, 2020 |
| HP            | ZBook 15 G4                 | Notebook    | [00d13faf2a](https://linux-hardware.org/?probe=00d13faf2a) | Aug 27, 2020 |
| Packard Be... | EasyNote LJ71               | Notebook    | [8848f3250d](https://linux-hardware.org/?probe=8848f3250d) | Aug 26, 2020 |
| HP            | 250 G4                      | Notebook    | [84bd70a658](https://linux-hardware.org/?probe=84bd70a658) | Jul 24, 2020 |
| HP            | 250 G4                      | Notebook    | [bb773c0ade](https://linux-hardware.org/?probe=bb773c0ade) | Jul 24, 2020 |
| HP            | ProBook 650 G1              | Notebook    | [33e5e60503](https://linux-hardware.org/?probe=33e5e60503) | Jul 05, 2020 |
| HP            | EliteBook Folio 9470m       | Notebook    | [2273ab39c8](https://linux-hardware.org/?probe=2273ab39c8) | Jun 27, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [734c3a7d86](https://linux-hardware.org/?probe=734c3a7d86) | Jun 22, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [9451ca4468](https://linux-hardware.org/?probe=9451ca4468) | Jun 22, 2020 |
| Toshiba       | Satellite C50-A560          | Notebook    | [cb406c43ec](https://linux-hardware.org/?probe=cb406c43ec) | Jun 21, 2020 |
| Toshiba       | Satellite C50-A560          | Notebook    | [46894e19cd](https://linux-hardware.org/?probe=46894e19cd) | Jun 21, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [81cf9fa7cf](https://linux-hardware.org/?probe=81cf9fa7cf) | Jun 11, 2020 |
| ECS           | P4M900T-M2                  | Desktop     | [b4ef87de2d](https://linux-hardware.org/?probe=b4ef87de2d) | Jun 04, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [c349a84934](https://linux-hardware.org/?probe=c349a84934) | Jun 02, 2020 |
| Toshiba       | Satellite C55-B             | Notebook    | [0bc2465c23](https://linux-hardware.org/?probe=0bc2465c23) | May 25, 2020 |
| ASUSTek       | X541UV                      | Notebook    | [25108243d2](https://linux-hardware.org/?probe=25108243d2) | May 23, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [148b457da1](https://linux-hardware.org/?probe=148b457da1) | May 21, 2020 |
| Acer          | Extensa 2510                | Notebook    | [3c56d54986](https://linux-hardware.org/?probe=3c56d54986) | May 16, 2020 |
| Toshiba       | Satellite C55-B             | Notebook    | [800fe450a7](https://linux-hardware.org/?probe=800fe450a7) | May 16, 2020 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [ad602ee170](https://linux-hardware.org/?probe=ad602ee170) | May 15, 2020 |
| Dell          | Inspiron 3558               | Notebook    | [e1f352ee7e](https://linux-hardware.org/?probe=e1f352ee7e) | May 15, 2020 |
| Acer          | Aspire 5733                 | Notebook    | [42424919ae](https://linux-hardware.org/?probe=42424919ae) | May 14, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [165c5e3446](https://linux-hardware.org/?probe=165c5e3446) | May 11, 2020 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [9deb8b9d38](https://linux-hardware.org/?probe=9deb8b9d38) | May 01, 2020 |
| HP            | 15                          | Notebook    | [bc0640c653](https://linux-hardware.org/?probe=bc0640c653) | May 01, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [30806c27ea](https://linux-hardware.org/?probe=30806c27ea) | May 01, 2020 |
| Dell          | Inspiron 3558               | Notebook    | [bc3989f5fd](https://linux-hardware.org/?probe=bc3989f5fd) | Apr 30, 2020 |
| Lenovo        | ThinkPad T450 20BUS2RN1H    | Notebook    | [eb26a0a6dd](https://linux-hardware.org/?probe=eb26a0a6dd) | Apr 26, 2020 |
| Lenovo        | ThinkPad T450 20BUS2RN1H    | Notebook    | [27139478ff](https://linux-hardware.org/?probe=27139478ff) | Apr 24, 2020 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [1e23113365](https://linux-hardware.org/?probe=1e23113365) | Apr 19, 2020 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [a06745a31b](https://linux-hardware.org/?probe=a06745a31b) | Apr 19, 2020 |
| Biostar       | P4M89-M7B Ver:1.0           | Desktop     | [300ccfbb68](https://linux-hardware.org/?probe=300ccfbb68) | Apr 15, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [32919aba44](https://linux-hardware.org/?probe=32919aba44) | Apr 08, 2020 |
| Sony          | SVE1713A6EW                 | Notebook    | [998290195d](https://linux-hardware.org/?probe=998290195d) | Mar 26, 2020 |
| Dell          | Precision M4600             | Notebook    | [995809b82f](https://linux-hardware.org/?probe=995809b82f) | Mar 12, 2020 |
| Dell          | Latitude 7490               | Notebook    | [394723d5ec](https://linux-hardware.org/?probe=394723d5ec) | Mar 12, 2020 |
| Dell          | Latitude 7490               | Notebook    | [9a4b04d5c6](https://linux-hardware.org/?probe=9a4b04d5c6) | Mar 10, 2020 |
| Dell          | Latitude 7490               | Notebook    | [3b7100f499](https://linux-hardware.org/?probe=3b7100f499) | Mar 10, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [b0b0e640c9](https://linux-hardware.org/?probe=b0b0e640c9) | Mar 01, 2020 |
| ECS           | G41T-M7                     | Desktop     | [39f9889169](https://linux-hardware.org/?probe=39f9889169) | Feb 26, 2020 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [46a39dcec8](https://linux-hardware.org/?probe=46a39dcec8) | Feb 10, 2020 |
| Dell          | Inspiron 15-3567            | Notebook    | [52020faf85](https://linux-hardware.org/?probe=52020faf85) | Feb 05, 2020 |
| Dell          | 0F0TGN A00                  | Desktop     | [1f4a60f810](https://linux-hardware.org/?probe=1f4a60f810) | Feb 03, 2020 |
| Toshiba       | PORTEGE M780                | Notebook    | [ed6be60ed5](https://linux-hardware.org/?probe=ed6be60ed5) | Jan 07, 2020 |
| Toshiba       | PORTEGE M780                | Notebook    | [b8f52696c7](https://linux-hardware.org/?probe=b8f52696c7) | Jan 07, 2020 |
| MSI           | H55M-E21                    | Desktop     | [a586112d3f](https://linux-hardware.org/?probe=a586112d3f) | Jan 01, 2020 |
| MSI           | H55M-E21                    | Desktop     | [71183fc4d2](https://linux-hardware.org/?probe=71183fc4d2) | Jan 01, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [170967f63e](https://linux-hardware.org/?probe=170967f63e) | Dec 31, 2019 |
| HP            | Pavilion 15                 | Notebook    | [e190391a64](https://linux-hardware.org/?probe=e190391a64) | Dec 10, 2019 |
| Lenovo        | ThinkPad T440 20B6S00200    | Notebook    | [8491772fe8](https://linux-hardware.org/?probe=8491772fe8) | Nov 19, 2019 |
| ASUSTek       | GL753VD                     | Notebook    | [3aed06c634](https://linux-hardware.org/?probe=3aed06c634) | Nov 05, 2019 |
| ASUSTek       | GL753VD                     | Notebook    | [80803b7502](https://linux-hardware.org/?probe=80803b7502) | Nov 05, 2019 |
| Sony          | VPCEJ2S1E                   | Notebook    | [909ce7c754](https://linux-hardware.org/?probe=909ce7c754) | Oct 25, 2019 |
| Toshiba       | Satellite C850-A979         | Notebook    | [742402d677](https://linux-hardware.org/?probe=742402d677) | Oct 01, 2019 |
| Toshiba       | Satellite C850-A979         | Notebook    | [bf938959f0](https://linux-hardware.org/?probe=bf938959f0) | Sep 30, 2019 |
| MSI           | Z77A-G45                    | Desktop     | [169e8e49d9](https://linux-hardware.org/?probe=169e8e49d9) | Sep 27, 2019 |
| HP            | 3397                        | Desktop     | [4367666d7a](https://linux-hardware.org/?probe=4367666d7a) | Sep 18, 2019 |
| HP            | 3397                        | Desktop     | [148b5948f9](https://linux-hardware.org/?probe=148b5948f9) | Sep 18, 2019 |
| HP            | Pavilion 15                 | Notebook    | [7e407e7cd4](https://linux-hardware.org/?probe=7e407e7cd4) | Sep 15, 2019 |
| HP            | Pavilion 15                 | Notebook    | [447f75484c](https://linux-hardware.org/?probe=447f75484c) | Sep 11, 2019 |
| HP            | Pavilion 15                 | Notebook    | [9352d1efae](https://linux-hardware.org/?probe=9352d1efae) | Sep 11, 2019 |
| Intel         | H55                         | Desktop     | [4529486397](https://linux-hardware.org/?probe=4529486397) | Jul 17, 2019 |
| Fujitsu       | LIFEBOOK AH532/G21          | Notebook    | [a9f20406b7](https://linux-hardware.org/?probe=a9f20406b7) | Jul 17, 2019 |
| Packard Be... | EasyNote TJ75               | Notebook    | [84742985cb](https://linux-hardware.org/?probe=84742985cb) | Apr 30, 2019 |
| Dell          | Latitude E5430 vPro         | Notebook    | [d88e664ef7](https://linux-hardware.org/?probe=d88e664ef7) | Apr 29, 2019 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [ec6b1b90c3](https://linux-hardware.org/?probe=ec6b1b90c3) | Apr 22, 2019 |
| Lenovo        | G50-30 80G0                 | Notebook    | [5aeb26c21c](https://linux-hardware.org/?probe=5aeb26c21c) | Apr 10, 2019 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | Notebook    | [92ce529502](https://linux-hardware.org/?probe=92ce529502) | Apr 10, 2019 |
| ASUSTek       | T102HA                      | Tablet      | [53ac040baf](https://linux-hardware.org/?probe=53ac040baf) | Mar 28, 2019 |
| HP            | Notebook                    | Notebook    | [a94921a2ad](https://linux-hardware.org/?probe=a94921a2ad) | Dec 29, 2018 |
| WeiBu         | SIMM INT G-41D3 G1.0L       | Desktop     | [d8be685baa](https://linux-hardware.org/?probe=d8be685baa) | Dec 01, 2018 |
| Dell          | 0TP406                      | Desktop     | [620c3d413f](https://linux-hardware.org/?probe=620c3d413f) | Nov 28, 2018 |
| Dell          | 0TP406                      | Desktop     | [e33d9fb70d](https://linux-hardware.org/?probe=e33d9fb70d) | Nov 28, 2018 |
| Unknown       | Unknown                     | Desktop     | [1ee83f48b0](https://linux-hardware.org/?probe=1ee83f48b0) | Oct 14, 2018 |
| MSI           | H55-GD65                    | Desktop     | [6cbd59f0a9](https://linux-hardware.org/?probe=6cbd59f0a9) | Feb 27, 2018 |
| HP            | Pavilion Notebook           | Notebook    | [283bc29327](https://linux-hardware.org/?probe=283bc29327) | Dec 24, 2017 |
| HP            | Pavilion Notebook           | Notebook    | [af28f98e0a](https://linux-hardware.org/?probe=af28f98e0a) | Dec 07, 2017 |
| MSI           | 970A-G46                    | Desktop     | [693800273f](https://linux-hardware.org/?probe=693800273f) | Apr 01, 2017 |
| ASUSTek       | X540SA                      | Notebook    | [f76ee802c9](https://linux-hardware.org/?probe=f76ee802c9) | Mar 09, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Algeria/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 54        | 13.04%  |
| Ubuntu 22.04       | 23        | 5.56%   |
| Ubuntu 18.04       | 21        | 5.07%   |
| OpenMandriva 4.3   | 17        | 4.11%   |
| OpenMandriva 4.2   | 16        | 3.86%   |
| Debian 12          | 10        | 2.42%   |
| Zorin 16           | 9         | 2.17%   |
| Zorin 17           | 8         | 1.93%   |
| OpenMandriva 23.03 | 7         | 1.69%   |
| Linux Mint 20.1    | 7         | 1.69%   |
| Ubuntu 24.04       | 6         | 1.45%   |
| Pop!_OS 22.04      | 6         | 1.45%   |
| OpenMandriva 23.08 | 6         | 1.45%   |
| KDE neon 20.04     | 6         | 1.45%   |
| Fedora 39          | 6         | 1.45%   |
| Fedora 35          | 6         | 1.45%   |
| ArcoLinux Rolling  | 6         | 1.45%   |
| Pop!_OS 20.04      | 5         | 1.21%   |
| Manjaro            | 5         | 1.21%   |
| KDE neon 22.04     | 5         | 1.21%   |
| Fedora 40          | 5         | 1.21%   |
| Arch               | 5         | 1.21%   |
| Ubuntu 21.04       | 4         | 0.97%   |
| Ubuntu 19.10       | 4         | 0.97%   |
| OpenMandriva 24.07 | 4         | 0.97%   |
| OpenMandriva 23.11 | 4         | 0.97%   |
| OpenMandriva 23.09 | 4         | 0.97%   |
| OpenMandriva 23.01 | 4         | 0.97%   |
| Fedora 37          | 4         | 0.97%   |
| Debian 11          | 4         | 0.97%   |
| Xubuntu 20.04      | 3         | 0.72%   |
| Ubuntu 20.10       | 3         | 0.72%   |
| ROSA R11           | 3         | 0.72%   |
| ROSA R10           | 3         | 0.72%   |
| OpenMandriva 24.09 | 3         | 0.72%   |
| OpenMandriva 24.01 | 3         | 0.72%   |
| MX 23              | 3         | 0.72%   |
| Linux Mint 21.3    | 3         | 0.72%   |
| Linux Mint 20.2    | 3         | 0.72%   |
| Kubuntu 20.04      | 3         | 0.72%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 119       | 29.82%  |
| OpenMandriva  | 72        | 18.05%  |
| Fedora        | 28        | 7.02%   |
| Linux Mint    | 23        | 5.76%   |
| Zorin         | 18        | 4.51%   |
| Debian        | 18        | 4.51%   |
| Pop!_OS       | 14        | 3.51%   |
| KDE neon      | 12        | 3.01%   |
| Manjaro       | 9         | 2.26%   |
| ROSA          | 8         | 2.01%   |
| Kali          | 8         | 2.01%   |
| Xubuntu       | 7         | 1.75%   |
| Arch          | 7         | 1.75%   |
| Parrot        | 6         | 1.5%    |
| ArcoLinux     | 6         | 1.5%    |
| MX            | 4         | 1%      |
| Kubuntu       | 4         | 1%      |
| openSUSE      | 3         | 0.75%   |
| BlackPanther  | 3         | 0.75%   |
| Ubuntu MATE   | 2         | 0.5%    |
| Peppermint    | 2         | 0.5%    |
| Gentoo        | 2         | 0.5%    |
| Garuda Linux  | 2         | 0.5%    |
| antiX         | 2         | 0.5%    |
| Xero          | 1         | 0.25%   |
| UbuntuDDE     | 1         | 0.25%   |
| Ubuntu Unity  | 1         | 0.25%   |
| Ubuntu Budgie | 1         | 0.25%   |
| TUXEDO OS     | 1         | 0.25%   |
| Skygate       | 1         | 0.25%   |
| Q4OS          | 1         | 0.25%   |
| Pear OS       | 1         | 0.25%   |
| Lubuntu       | 1         | 0.25%   |
| Endless       | 1         | 0.25%   |
| EndeavourOS   | 1         | 0.25%   |
| Elementary    | 1         | 0.25%   |
| Deepin        | 1         | 0.25%   |
| Clear Linux   | 1         | 0.25%   |
| ChimeraOS     | 1         | 0.25%   |
| CentOS        | 1         | 0.25%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 17        | 3.91%   |
| 5.10.14-desktop-1omv4002 | 16        | 3.68%   |
| 6.6.2-desktop-1omv2390   | 7         | 1.61%   |
| 6.2.6-desktop-1omv2390   | 6         | 1.38%   |
| 6.5.0-15-generic         | 5         | 1.15%   |
| 5.4.0-42-generic         | 5         | 1.15%   |
| 5.15.0-47-generic        | 5         | 1.15%   |
| 6.4.11-desktop-1omv2390  | 4         | 0.92%   |
| 6.1.1-desktop-1omv2290   | 4         | 0.92%   |
| 5.8.0-50-generic         | 4         | 0.92%   |
| 5.4.0-72-generic         | 4         | 0.92%   |
| 5.4.0-54-generic         | 4         | 0.92%   |
| 5.4.0-29-generic         | 4         | 0.92%   |
| 5.0.0-37-generic         | 4         | 0.92%   |
| 6.5.5-desktop-1omv2390   | 3         | 0.69%   |
| 6.5.0-17-generic         | 3         | 0.69%   |
| 6.2.0-33-generic         | 3         | 0.69%   |
| 6.10.0-desktop-1omv2490  | 3         | 0.69%   |
| 6.1.0-13-amd64           | 3         | 0.69%   |
| 6.0.12-100.fc35.x86_64   | 3         | 0.69%   |
| 5.4.0-65-generic         | 3         | 0.69%   |
| 5.4.0-56-generic         | 3         | 0.69%   |
| 5.4.0-52-generic         | 3         | 0.69%   |
| 5.3.0-46-generic         | 3         | 0.69%   |
| 5.15.0-86-generic        | 3         | 0.69%   |
| 5.15.0-58-generic        | 3         | 0.69%   |
| 5.15.0-56-generic        | 3         | 0.69%   |
| 5.13.0-30-generic        | 3         | 0.69%   |
| 5.11.0-38-generic        | 3         | 0.69%   |
| 5.11.0-27-generic        | 3         | 0.69%   |
| 6.9.7-desktop-1omv2490   | 2         | 0.46%   |
| 6.8.0-51-generic         | 2         | 0.46%   |
| 6.8.0-48-generic         | 2         | 0.46%   |
| 6.8.0-45-generic         | 2         | 0.46%   |
| 6.5.0-desktop-1omv2390   | 2         | 0.46%   |
| 6.5.0-41-generic         | 2         | 0.46%   |
| 6.4.8-desktop-2omv2390   | 2         | 0.46%   |
| 6.2.0-36-generic         | 2         | 0.46%   |
| 6.12.6-desktop-1omv2490  | 2         | 0.46%   |
| 6.11.0-desktop-2omv2490  | 2         | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 52        | 12.47%  |
| 5.15.0  | 36        | 8.63%   |
| 6.5.0   | 18        | 4.32%   |
| 5.16.7  | 17        | 4.08%   |
| 5.11.0  | 16        | 3.84%   |
| 5.10.14 | 16        | 3.84%   |
| 6.1.0   | 14        | 3.36%   |
| 5.8.0   | 14        | 3.36%   |
| 4.15.0  | 13        | 3.12%   |
| 5.3.0   | 10        | 2.4%    |
| 5.0.0   | 10        | 2.4%    |
| 6.8.0   | 9         | 2.16%   |
| 5.13.0  | 9         | 2.16%   |
| 6.2.0   | 8         | 1.92%   |
| 5.10.0  | 8         | 1.92%   |
| 6.6.2   | 7         | 1.68%   |
| 6.2.6   | 7         | 1.68%   |
| 5.19.0  | 5         | 1.2%    |
| 6.8.7   | 4         | 0.96%   |
| 6.4.11  | 4         | 0.96%   |
| 6.10.0  | 4         | 0.96%   |
| 6.1.1   | 4         | 0.96%   |
| 6.9.7   | 3         | 0.72%   |
| 6.5.5   | 3         | 0.72%   |
| 6.11.0  | 3         | 0.72%   |
| 6.0.12  | 3         | 0.72%   |
| 4.18.16 | 3         | 0.72%   |
| 6.6.9   | 2         | 0.48%   |
| 6.6.8   | 2         | 0.48%   |
| 6.5.6   | 2         | 0.48%   |
| 6.4.8   | 2         | 0.48%   |
| 6.2.8   | 2         | 0.48%   |
| 6.12.6  | 2         | 0.48%   |
| 6.10.1  | 2         | 0.48%   |
| 6.1.12  | 2         | 0.48%   |
| 6.0.7   | 2         | 0.48%   |
| 5.15.7  | 2         | 0.48%   |
| 5.14.0  | 2         | 0.48%   |
| 4.9.60  | 2         | 0.48%   |
| 4.4.0   | 2         | 0.48%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 55        | 13.22%  |
| 5.15    | 46        | 11.06%  |
| 6.1     | 29        | 6.97%   |
| 5.10    | 29        | 6.97%   |
| 6.5     | 25        | 6.01%   |
| 6.2     | 20        | 4.81%   |
| 5.16    | 19        | 4.57%   |
| 5.11    | 18        | 4.33%   |
| 6.8     | 17        | 4.09%   |
| 5.8     | 15        | 3.61%   |
| 6.6     | 14        | 3.37%   |
| 4.15    | 13        | 3.13%   |
| 6.4     | 10        | 2.4%    |
| 5.3     | 10        | 2.4%    |
| 5.19    | 10        | 2.4%    |
| 5.13    | 10        | 2.4%    |
| 5.0     | 10        | 2.4%    |
| 6.10    | 8         | 1.92%   |
| 6.0     | 7         | 1.68%   |
| 6.9     | 5         | 1.2%    |
| 6.11    | 5         | 1.2%    |
| 5.14    | 5         | 1.2%    |
| 4.9     | 4         | 0.96%   |
| 4.19    | 4         | 0.96%   |
| 4.18    | 4         | 0.96%   |
| 6.7     | 3         | 0.72%   |
| 5.17    | 3         | 0.72%   |
| 5.12    | 3         | 0.72%   |
| 6.3     | 2         | 0.48%   |
| 6.12    | 2         | 0.48%   |
| 5.7     | 2         | 0.48%   |
| 5.6     | 2         | 0.48%   |
| 5.18    | 2         | 0.48%   |
| 4.4     | 2         | 0.48%   |
| 5.9     | 1         | 0.24%   |
| 4.1     | 1         | 0.24%   |
| 3.10    | 1         | 0.24%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 360       | 97.56%  |
| i686   | 8         | 2.17%   |
| armv7l | 1         | 0.27%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 169       | 43.22%  |
| KDE5             | 93        | 23.79%  |
| Unknown          | 35        | 8.95%   |
| XFCE             | 28        | 7.16%   |
| X-Cinnamon       | 14        | 3.58%   |
| MATE             | 9         | 2.3%    |
| Cinnamon         | 8         | 2.05%   |
| KDE6             | 6         | 1.53%   |
| KDE4             | 5         | 1.28%   |
| KDE              | 5         | 1.28%   |
| LXQt             | 4         | 1.02%   |
| i3               | 2         | 0.51%   |
| Unity            | 1         | 0.26%   |
| Trinity          | 1         | 0.26%   |
| Peppermint       | 1         | 0.26%   |
| Pantheon         | 1         | 0.26%   |
| LXDE             | 1         | 0.26%   |
| lightdm-xsession | 1         | 0.26%   |
| icewm            | 1         | 0.26%   |
| GNOME Flashback  | 1         | 0.26%   |
| fvwm             | 1         | 0.26%   |
| fluxbox          | 1         | 0.26%   |
| Deepin           | 1         | 0.26%   |
| DDE              | 1         | 0.26%   |
| Budgie           | 1         | 0.26%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 253       | 66.75%  |
| Wayland | 110       | 29.02%  |
| Unknown | 13        | 3.43%   |
| Tty     | 3         | 0.79%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 166       | 42.46%  |
| SDDM    | 90        | 23.02%  |
| GDM3    | 50        | 12.79%  |
| LightDM | 36        | 9.21%   |
| GDM     | 33        | 8.44%   |
| TDM     | 8         | 2.05%   |
| KDM     | 5         | 1.28%   |
| SLIMSKI | 2         | 0.51%   |
| SLiM    | 1         | 0.26%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 165       | 42.97%  |
| fr_FR       | 146       | 38.02%  |
| Unknown     | 28        | 7.29%   |
| en_GB       | 14        | 3.65%   |
| C           | 9         | 2.34%   |
| ar_DZ       | 9         | 2.34%   |
| ar_EG       | 3         | 0.78%   |
| fr_DZ       | 2         | 0.52%   |
| fr_BE       | 2         | 0.52%   |
| es_ES       | 2         | 0.52%   |
| en_IE       | 1         | 0.26%   |
| en_DK       | 1         | 0.26%   |
| en-US-UTF-8 | 1         | 0.26%   |
| ar_AE       | 1         | 0.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 253       | 66.4%   |
| EFI  | 128       | 33.6%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 274       | 70.98%  |
| Overlay | 44        | 11.4%   |
| Btrfs   | 36        | 9.33%   |
| Tmpfs   | 16        | 4.15%   |
| Unknown | 9         | 2.33%   |
| Xfs     | 3         | 0.78%   |
| Ext2    | 3         | 0.78%   |
| Ext3    | 1         | 0.26%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 179       | 46.98%  |
| GPT     | 113       | 29.66%  |
| MBR     | 89        | 23.36%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 290       | 75.72%  |
| Yes       | 93        | 24.28%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 206       | 54.21%  |
| Yes       | 174       | 45.79%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 59        | 15.99%  |
| ASUSTek Computer    | 57        | 15.45%  |
| Hewlett-Packard     | 52        | 14.09%  |
| Lenovo              | 41        | 11.11%  |
| MSI                 | 24        | 6.5%    |
| Gigabyte Technology | 21        | 5.69%   |
| Acer                | 19        | 5.15%   |
| Unknown             | 13        | 3.52%   |
| Toshiba             | 11        | 2.98%   |
| Foxconn             | 9         | 2.44%   |
| ECS                 | 8         | 2.17%   |
| Apple               | 8         | 2.17%   |
| Sony                | 7         | 1.9%    |
| Intel               | 5         | 1.36%   |
| Samsung Electronics | 4         | 1.08%   |
| Packard Bell        | 4         | 1.08%   |
| ASRock              | 4         | 1.08%   |
| Fujitsu             | 3         | 0.81%   |
| Biostar             | 3         | 0.81%   |
| Pegatron            | 2         | 0.54%   |
| LORD ELECTRONICS    | 2         | 0.54%   |
| Wistron             | 1         | 0.27%   |
| WeiBu               | 1         | 0.27%   |
| UNOWHY              | 1         | 0.27%   |
| Supermicro          | 1         | 0.27%   |
| sunxi               | 1         | 0.27%   |
| SPA CONDOR          | 1         | 0.27%   |
| Notebook            | 1         | 0.27%   |
| Microsoft           | 1         | 0.27%   |
| LDLC                | 1         | 0.27%   |
| HUAWEI              | 1         | 0.27%   |
| Google              | 1         | 0.27%   |
| eMachines           | 1         | 0.27%   |
| AMI                 | 1         | 0.27%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| ASUS UL80VT                                       | 22        | 5.96%   |
| Unknown                                           | 13        | 3.52%   |
| Dell Inspiron N5110                               | 5         | 1.36%   |
| Toshiba Satellite C55-B                           | 4         | 1.08%   |
| HP Pavilion 15                                    | 4         | 1.08%   |
| Dell Inspiron 15-3567                             | 4         | 1.08%   |
| MSI MS-7788                                       | 3         | 0.81%   |
| Lenovo IdeaPad 300-15ISK 80Q7                     | 3         | 0.81%   |
| Lenovo G560 20042                                 | 3         | 0.81%   |
| Intel H55                                         | 3         | 0.81%   |
| HP ProBook 4540s                                  | 3         | 0.81%   |
| HP Notebook                                       | 3         | 0.81%   |
| HP 280 G1 MT                                      | 3         | 0.81%   |
| Gigabyte H61M-S2PV                                | 3         | 0.81%   |
| Foxconn H61MXL/H61MXL-K                           | 3         | 0.81%   |
| ECS G41T-M7                                       | 3         | 0.81%   |
| Dell Latitude 7480                                | 3         | 0.81%   |
| Dell Inspiron 3542                                | 3         | 0.81%   |
| ASUS All Series                                   | 3         | 0.81%   |
| MSI MS-7C52                                       | 2         | 0.54%   |
| MSI MS-7758                                       | 2         | 0.54%   |
| MSI MS-7636                                       | 2         | 0.54%   |
| MSI MS-7592                                       | 2         | 0.54%   |
| LORD ELECTRONICS LORD G4x 775 ICH7 8712 As Design | 2         | 0.54%   |
| Lenovo G50-30 80G0                                | 2         | 0.54%   |
| Lenovo B50-70 20384                               | 2         | 0.54%   |
| Intel H61                                         | 2         | 0.54%   |
| HP EliteBook 840 G3                               | 2         | 0.54%   |
| HP 15                                             | 2         | 0.54%   |
| Gigabyte G41MT-S2PT                               | 2         | 0.54%   |
| Gigabyte B85M-DS3H-A                              | 2         | 0.54%   |
| ECS H61H2-MV                                      | 2         | 0.54%   |
| Dell Latitude E7440                               | 2         | 0.54%   |
| Dell Latitude E5430 vPro                          | 2         | 0.54%   |
| Dell Latitude 5490                                | 2         | 0.54%   |
| Dell Latitude 5480                                | 2         | 0.54%   |
| Dell Inspiron 3543                                | 2         | 0.54%   |
| Biostar P4M89-M7B                                 | 2         | 0.54%   |
| ASUS H61M-K                                       | 2         | 0.54%   |
| Acer Aspire 5738                                  | 2         | 0.54%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| ASUS UL80VT           | 22        | 5.96%   |
| Dell Latitude         | 21        | 5.69%   |
| Dell Inspiron         | 21        | 5.69%   |
| Acer Aspire           | 15        | 4.07%   |
| Lenovo ThinkPad       | 13        | 3.52%   |
| Unknown               | 13        | 3.52%   |
| HP ProBook            | 10        | 2.71%   |
| Toshiba Satellite     | 9         | 2.44%   |
| HP Pavilion           | 9         | 2.44%   |
| HP EliteBook          | 9         | 2.44%   |
| Lenovo IdeaPad        | 8         | 2.17%   |
| Dell Vostro           | 6         | 1.63%   |
| HP Laptop             | 4         | 1.08%   |
| Dell Precision        | 4         | 1.08%   |
| Dell OptiPlex         | 4         | 1.08%   |
| MSI MS-7788           | 3         | 0.81%   |
| Lenovo Yoga           | 3         | 0.81%   |
| Lenovo G560           | 3         | 0.81%   |
| Intel H55             | 3         | 0.81%   |
| HP Notebook           | 3         | 0.81%   |
| HP 280                | 3         | 0.81%   |
| Gigabyte H61M-S2PV    | 3         | 0.81%   |
| Fujitsu LIFEBOOK      | 3         | 0.81%   |
| Foxconn H61MXL        | 3         | 0.81%   |
| ECS G41T-M7           | 3         | 0.81%   |
| ASUS VivoBook         | 3         | 0.81%   |
| ASUS TUF              | 3         | 0.81%   |
| ASUS PRIME            | 3         | 0.81%   |
| ASUS ASUS             | 3         | 0.81%   |
| ASUS All              | 3         | 0.81%   |
| Toshiba PORTEGE       | 2         | 0.54%   |
| Packard Bell EasyNote | 2         | 0.54%   |
| MSI MS-7C52           | 2         | 0.54%   |
| MSI MS-7758           | 2         | 0.54%   |
| MSI MS-7636           | 2         | 0.54%   |
| MSI MS-7592           | 2         | 0.54%   |
| LORD ELECTRONICS LORD | 2         | 0.54%   |
| Lenovo G580           | 2         | 0.54%   |
| Lenovo G50-30         | 2         | 0.54%   |
| Lenovo B50-70         | 2         | 0.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 51        | 13.82%  |
| 2013    | 38        | 10.3%   |
| 2009    | 38        | 10.3%   |
| 2014    | 36        | 9.76%   |
| 2011    | 33        | 8.94%   |
| 2015    | 26        | 7.05%   |
| 2017    | 25        | 6.78%   |
| 2016    | 24        | 6.5%    |
| 2010    | 20        | 5.42%   |
| 2018    | 17        | 4.61%   |
| 2019    | 11        | 2.98%   |
| 2020    | 10        | 2.71%   |
| 2021    | 9         | 2.44%   |
| 2008    | 8         | 2.17%   |
| 2007    | 7         | 1.9%    |
| 2022    | 6         | 1.63%   |
| 2023    | 5         | 1.36%   |
| 2006    | 2         | 0.54%   |
| Unknown | 2         | 0.54%   |
| 2024    | 1         | 0.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 234       | 63.41%  |
| Desktop        | 124       | 33.6%   |
| Tablet         | 4         | 1.08%   |
| All in one     | 4         | 1.08%   |
| System on chip | 1         | 0.27%   |
| Convertible    | 1         | 0.27%   |
| Server         | 1         | 0.27%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 358       | 96.76%  |
| Enabled  | 12        | 3.24%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 368       | 99.73%  |
| Yes  | 1         | 0.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 118       | 31.13%  |
| 4.01-8.0        | 103       | 27.18%  |
| 8.01-16.0       | 81        | 21.37%  |
| 16.01-24.0      | 30        | 7.92%   |
| 1.01-2.0        | 23        | 6.07%   |
| 32.01-64.0      | 8         | 2.11%   |
| 2.01-3.0        | 8         | 2.11%   |
| 0.51-1.0        | 5         | 1.32%   |
| 64.01-256.0     | 2         | 0.53%   |
| More than 256.0 | 1         | 0.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 173       | 41.99%  |
| 2.01-3.0   | 111       | 26.94%  |
| 3.01-4.0   | 58        | 14.08%  |
| 4.01-8.0   | 35        | 8.5%    |
| 0.51-1.0   | 22        | 5.34%   |
| 8.01-16.0  | 8         | 1.94%   |
| 0.01-0.5   | 4         | 0.97%   |
| 32.01-64.0 | 1         | 0.24%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 254       | 67.2%   |
| 2      | 95        | 25.13%  |
| 3      | 16        | 4.23%   |
| 4      | 7         | 1.85%   |
| 0      | 4         | 1.06%   |
| 7      | 1         | 0.26%   |
| 5      | 1         | 0.26%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 204       | 54.26%  |
| No        | 172       | 45.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 337       | 91.33%  |
| No        | 32        | 8.67%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 304       | 81.28%  |
| No        | 70        | 18.72%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 194       | 51.73%  |
| Yes       | 181       | 48.27%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Algeria | 369       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Algiers            | 64        | 15.24%  |
| Sétif             | 22        | 5.24%   |
| Oran               | 22        | 5.24%   |
| Belcourt           | 21        | 5%      |
| Annaba             | 15        | 3.57%   |
| Constantine        | 12        | 2.86%   |
| Tlemcen            | 11        | 2.62%   |
| Béjaïa           | 11        | 2.62%   |
| Tizi Ouzou         | 9         | 2.14%   |
| Batna City         | 8         | 1.9%    |
| Skikda             | 7         | 1.67%   |
| Jijelli            | 7         | 1.67%   |
| Blida              | 7         | 1.67%   |
| Relizane           | 6         | 1.43%   |
| Cheraga            | 6         | 1.43%   |
| Bab Ezzouar        | 6         | 1.43%   |
| Tipasa             | 5         | 1.19%   |
| Ouargla            | 5         | 1.19%   |
| Mostaganem         | 5         | 1.19%   |
| Laghouat           | 5         | 1.19%   |
| Bordj Bou Arreridj | 5         | 1.19%   |
| Biskra             | 5         | 1.19%   |
| ash-Shalif         | 5         | 1.19%   |
| Sidi Bel Abbes     | 4         | 0.95%   |
| Sidi Akkacha       | 4         | 0.95%   |
| Djelfa             | 4         | 0.95%   |
| Bordj el Kiffan    | 4         | 0.95%   |
| Birkhadem          | 4         | 0.95%   |
| Ben ’Aknoûn     | 4         | 0.95%   |
| Béchar            | 4         | 0.95%   |
| Tolga              | 3         | 0.71%   |
| Saoula             | 3         | 0.71%   |
| Kouba              | 3         | 0.71%   |
| Boumerdes          | 3         | 0.71%   |
| Saida              | 2         | 0.48%   |
| Reghaia            | 2         | 0.48%   |
| Ouenza             | 2         | 0.48%   |
| Medea              | 2         | 0.48%   |
| Khenchela          | 2         | 0.48%   |
| El Aouinet         | 2         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 96        | 120    | 19.83%  |
| WDC                         | 73        | 99     | 15.08%  |
| Toshiba                     | 49        | 66     | 10.12%  |
| Hitachi                     | 39        | 50     | 8.06%   |
| Samsung Electronics         | 34        | 38     | 7.02%   |
| A-DATA Technology           | 22        | 28     | 4.55%   |
| HGST                        | 20        | 27     | 4.13%   |
| Team                        | 12        | 13     | 2.48%   |
| Intel                       | 12        | 14     | 2.48%   |
| Unknown                     | 11        | 17     | 2.27%   |
| SanDisk                     | 11        | 13     | 2.27%   |
| SK hynix                    | 9         | 12     | 1.86%   |
| China                       | 8         | 10     | 1.65%   |
| Lexar                       | 7         | 11     | 1.45%   |
| Maxtor                      | 6         | 8      | 1.24%   |
| Micron Technology           | 5         | 6      | 1.03%   |
| LITEON                      | 5         | 9      | 1.03%   |
| Fujitsu                     | 4         | 5      | 0.83%   |
| Crucial                     | 4         | 4      | 0.83%   |
| XPG                         | 3         | 3      | 0.62%   |
| TwinMOS                     | 3         | 3      | 0.62%   |
| Realtek Semiconductor       | 3         | 3      | 0.62%   |
| Kingston                    | 3         | 3      | 0.62%   |
| ZTE                         | 2         | 2      | 0.41%   |
| XrayDisk                    | 2         | 3      | 0.41%   |
| tecmiyo                     | 2         | 2      | 0.41%   |
| Silicon Motion              | 2         | 2      | 0.41%   |
| KingSpec                    | 2         | 2      | 0.41%   |
| KESU                        | 2         | 2      | 0.41%   |
| HS-SSD-E100                 | 2         | 2      | 0.41%   |
| Apple                       | 2         | 2      | 0.41%   |
| ADATA Technology            | 2         | 3      | 0.41%   |
| WD MediaMax                 | 1         | 1      | 0.21%   |
| T-FORCE                     | 1         | 1      | 0.21%   |
| STAR                        | 1         | 1      | 0.21%   |
| Smart                       | 1         | 1      | 0.21%   |
| PNY                         | 1         | 1      | 0.21%   |
| Micron/Crucial Technology   | 1         | 1      | 0.21%   |
| MDT                         | 1         | 1      | 0.21%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seagate ST9500325AS 500GB          | 25        | 4.9%    |
| Toshiba MQ01ABF050 500GB           | 9         | 1.76%   |
| Toshiba MQ01ABD100 1TB             | 7         | 1.37%   |
| Seagate ST500LT012-1DG142 500GB    | 7         | 1.37%   |
| Toshiba DT01ACA100 1TB             | 6         | 1.18%   |
| Toshiba DT01ACA050 500GB           | 5         | 0.98%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 5         | 0.98%   |
| Seagate Expansion 1TB              | 5         | 0.98%   |
| HGST HTS545050A7E680 500GB         | 5         | 0.98%   |
| WDC WD5000LPCX-24C6HT0 500GB       | 4         | 0.78%   |
| Team T253256GB SSD                 | 4         | 0.78%   |
| Seagate ST500VT000-1DK142 500GB    | 4         | 0.78%   |
| Seagate ST500LT012-9WS142 500GB    | 4         | 0.78%   |
| Seagate ST1000LM035-1RK172 1TB     | 4         | 0.78%   |
| Intel SSDPEKNU512GZ 512GB          | 4         | 0.78%   |
| Hitachi HTS545050A7E380 500GB      | 4         | 0.78%   |
| Hitachi HDS721616PLA380 160GB      | 4         | 0.78%   |
| HGST HTS545050A7E380 500GB         | 4         | 0.78%   |
| China SSD 256GB                    | 4         | 0.78%   |
| A-DATA SU650 120GB SSD             | 4         | 0.78%   |
| A-DATA SU630 240GB SSD             | 4         | 0.78%   |
| WDC WD5000AAKX-001CA0 500GB        | 3         | 0.59%   |
| WDC WD10EZEX-08WN4A0 1TB           | 3         | 0.59%   |
| WDC WD10EZEX-00WN4A0 1TB           | 3         | 0.59%   |
| Unknown MMC Card  64GB             | 3         | 0.59%   |
| Toshiba MQ01ABD050V 500GB          | 3         | 0.59%   |
| Team T253512GB SSD                 | 3         | 0.59%   |
| Seagate ST500LM021-1KJ152 500GB    | 3         | 0.59%   |
| Lexar 512GB SSD                    | 3         | 0.59%   |
| Lexar 128GB SSD                    | 3         | 0.59%   |
| Hitachi HTS545050B9A300 500GB      | 3         | 0.59%   |
| HGST HTS725050A7E630 500GB         | 3         | 0.59%   |
| HGST HTS541010A9E680 1TB           | 3         | 0.59%   |
| A-DATA LEGEND 710 512GB            | 3         | 0.59%   |
| ZTE MMC Storage 942MB              | 2         | 0.39%   |
| XPG SX950U 240GB SSD               | 2         | 0.39%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 2         | 0.39%   |
| WDC WD5000AVVS-63M8B0 500GB        | 2         | 0.39%   |
| WDC WD5000AVCS-632DY1 500GB        | 2         | 0.39%   |
| WDC WD1600AVJS-63WNA0 160GB        | 2         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 96        | 120    | 31.79%  |
| WDC                 | 69        | 91     | 22.85%  |
| Toshiba             | 48        | 63     | 15.89%  |
| Hitachi             | 39        | 50     | 12.91%  |
| HGST                | 20        | 27     | 6.62%   |
| Samsung Electronics | 13        | 14     | 4.3%    |
| Maxtor              | 6         | 8      | 1.99%   |
| Fujitsu             | 4         | 5      | 1.32%   |
| WD MediaMax         | 1         | 1      | 0.33%   |
| Magnetic Data       | 1         | 1      | 0.33%   |
| KESU                | 1         | 1      | 0.33%   |
| JMicron Technology  | 1         | 1      | 0.33%   |
| Initio              | 1         | 1      | 0.33%   |
| Hewlett-Packard     | 1         | 1      | 0.33%   |
| Apple               | 1         | 1      | 0.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| A-DATA Technology   | 16        | 20     | 15.09%  |
| Team                | 10        | 11     | 9.43%   |
| SanDisk             | 8         | 8      | 7.55%   |
| China               | 8         | 10     | 7.55%   |
| Samsung Electronics | 7         | 7      | 6.6%    |
| Lexar               | 6         | 10     | 5.66%   |
| WDC                 | 5         | 7      | 4.72%   |
| LITEON              | 5         | 9      | 4.72%   |
| SK hynix            | 4         | 6      | 3.77%   |
| Crucial             | 4         | 4      | 3.77%   |
| TwinMOS             | 3         | 3      | 2.83%   |
| Intel               | 3         | 4      | 2.83%   |
| XrayDisk            | 2         | 3      | 1.89%   |
| XPG                 | 2         | 2      | 1.89%   |
| tecmiyo             | 2         | 2      | 1.89%   |
| Kingston            | 2         | 2      | 1.89%   |
| KingSpec            | 2         | 2      | 1.89%   |
| T-FORCE             | 1         | 1      | 0.94%   |
| STAR                | 1         | 1      | 0.94%   |
| PNY                 | 1         | 1      | 0.94%   |
| Micron Technology   | 1         | 1      | 0.94%   |
| MAX                 | 1         | 1      | 0.94%   |
| Londisk             | 1         | 1      | 0.94%   |
| LITEONIT            | 1         | 1      | 0.94%   |
| Lenovo              | 1         | 1      | 0.94%   |
| KODAK               | 1         | 2      | 0.94%   |
| HS-SSD-E100         | 1         | 1      | 0.94%   |
| HS-SSD-C100         | 1         | 1      | 0.94%   |
| faspeed             | 1         | 1      | 0.94%   |
| Corsair             | 1         | 1      | 0.94%   |
| Asgard              | 1         | 1      | 0.94%   |
| Apple               | 1         | 1      | 0.94%   |
| AGI                 | 1         | 1      | 0.94%   |
| Unknown             | 1         | 1      | 0.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 271       | 385    | 61.17%  |
| SSD     | 100       | 128    | 22.57%  |
| NVMe    | 49        | 70     | 11.06%  |
| Unknown | 12        | 17     | 2.71%   |
| MMC     | 11        | 13     | 2.48%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 322       | 508    | 80.9%   |
| NVMe | 49        | 70     | 12.31%  |
| SAS  | 16        | 22     | 4.02%   |
| MMC  | 11        | 13     | 2.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 259       | 378    | 71.15%  |
| 0.51-1.0   | 94        | 122    | 25.82%  |
| 1.01-2.0   | 10        | 12     | 2.75%   |
| 3.01-4.0   | 1         | 1      | 0.27%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 95        | 23.63%  |
| 101-250        | 87        | 21.64%  |
| 51-100         | 58        | 14.43%  |
| 21-50          | 50        | 12.44%  |
| 501-1000       | 47        | 11.69%  |
| 1-20           | 39        | 9.7%    |
| 1001-2000      | 16        | 3.98%   |
| Unknown        | 5         | 1.24%   |
| More than 3000 | 3         | 0.75%   |
| 2001-3000      | 2         | 0.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 182       | 44.61%  |
| 21-50     | 88        | 21.57%  |
| 101-250   | 49        | 12.01%  |
| 51-100    | 42        | 10.29%  |
| 251-500   | 24        | 5.88%   |
| 501-1000  | 12        | 2.94%   |
| 1001-2000 | 5         | 1.23%   |
| Unknown   | 5         | 1.23%   |
| 2001-3000 | 1         | 0.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                       | Computers | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                   | 23        | 23     | 25.56%  |
| Seagate ST500LT012-9WS142 500GB             | 3         | 3      | 3.33%   |
| Toshiba MQ01ABD100 1TB                      | 2         | 2      | 2.22%   |
| Seagate ST500LT012-1DG142 500GB             | 2         | 2      | 2.22%   |
| Seagate ST500LM021-1KJ152 500GB             | 2         | 2      | 2.22%   |
| Seagate ST1000DM010-2EP102 1TB              | 2         | 3      | 2.22%   |
| Samsung Electronics HD502HI 500GB           | 2         | 2      | 2.22%   |
| HGST HTS725050A7E630 500GB                  | 2         | 5      | 2.22%   |
| XPG SPECTRIX S40G 1TB                       | 1         | 1      | 1.11%   |
| WDC WD7500AARS-00Y5B1 752GB                 | 1         | 1      | 1.11%   |
| WDC WD5000LUCT-62C26Y0 500GB                | 1         | 1      | 1.11%   |
| WDC WD5000BEVT-24A0RT0 500GB                | 1         | 1      | 1.11%   |
| WDC WD5000BEVT-22A0RT0 500GB                | 1         | 1      | 1.11%   |
| WDC WD5000AVVS-63M8B0 500GB                 | 1         | 1      | 1.11%   |
| WDC WD5000AVCS-632DY1 500GB                 | 1         | 1      | 1.11%   |
| WDC WD5000AAKX-00ERMA0 500GB                | 1         | 1      | 1.11%   |
| WDC WD400EB-00CPF0 40GB                     | 1         | 1      | 1.11%   |
| WDC WD3200BPVT-22JJ5T0 320GB                | 1         | 1      | 1.11%   |
| WDC WD3200AVJS-63B6A0 320GB                 | 1         | 1      | 1.11%   |
| WDC WD1600AAJS-08WAA0 160GB                 | 1         | 1      | 1.11%   |
| WDC WD10EZEX-60WN4A0 1TB                    | 1         | 2      | 1.11%   |
| WDC WD1001FALS-403AA0 1TB                   | 1         | 1      | 1.11%   |
| WD MediaMax WL120GBSATA                     | 1         | 1      | 1.11%   |
| Toshiba MQ01ABF050 500GB                    | 1         | 1      | 1.11%   |
| Toshiba DT01ACA050 500GB                    | 1         | 1      | 1.11%   |
| tecmiyo SATA SSD 128GB                      | 1         | 1      | 1.11%   |
| Seagate ST9320325AS 320GB                   | 1         | 1      | 1.11%   |
| Seagate ST9250410AS 250GB                   | 1         | 1      | 1.11%   |
| Seagate ST500DM002-1BD142 500GB             | 1         | 2      | 1.11%   |
| Seagate ST3500413AS 500GB                   | 1         | 1      | 1.11%   |
| Seagate ST3250310AS 250GB                   | 1         | 1      | 1.11%   |
| Seagate ST1000LM048-2E7172 1TB              | 1         | 1      | 1.11%   |
| Seagate ST1000LM035-1RK172 1TB              | 1         | 1      | 1.11%   |
| Seagate ST1000LM024 HN-M101MBB 1TB          | 1         | 1      | 1.11%   |
| Samsung Electronics SSD PM810 2.5 7mm 128GB | 1         | 1      | 1.11%   |
| Samsung Electronics HM320HJ 320GB           | 1         | 1      | 1.11%   |
| Samsung Electronics HD256GJ 250GB           | 1         | 1      | 1.11%   |
| Samsung Electronics HD160JJ 160GB           | 1         | 1      | 1.11%   |
| Samsung Electronics HD103SI 1TB             | 1         | 1      | 1.11%   |
| Maxtor STM3320613AS 320GB                   | 1         | 1      | 1.11%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 40        | 42     | 44.94%  |
| WDC                 | 12        | 14     | 13.48%  |
| Hitachi             | 8         | 9      | 8.99%   |
| Samsung Electronics | 7         | 7      | 7.87%   |
| Toshiba             | 4         | 4      | 4.49%   |
| Maxtor              | 4         | 4      | 4.49%   |
| HGST                | 4         | 7      | 4.49%   |
| A-DATA Technology   | 2         | 2      | 2.25%   |
| XPG                 | 1         | 1      | 1.12%   |
| WD MediaMax         | 1         | 1      | 1.12%   |
| tecmiyo             | 1         | 1      | 1.12%   |
| Magnetic Data       | 1         | 1      | 1.12%   |
| LITEONIT            | 1         | 1      | 1.12%   |
| KingSpec            | 1         | 1      | 1.12%   |
| Fujitsu             | 1         | 1      | 1.12%   |
| Crucial             | 1         | 1      | 1.12%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 40        | 42     | 49.38%  |
| WDC                 | 12        | 14     | 14.81%  |
| Hitachi             | 8         | 9      | 9.88%   |
| Samsung Electronics | 6         | 6      | 7.41%   |
| Toshiba             | 4         | 4      | 4.94%   |
| Maxtor              | 4         | 4      | 4.94%   |
| HGST                | 4         | 7      | 4.94%   |
| WD MediaMax         | 1         | 1      | 1.23%   |
| Magnetic Data       | 1         | 1      | 1.23%   |
| Fujitsu             | 1         | 1      | 1.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 78        | 89     | 90.7%   |
| SSD  | 6         | 6      | 6.98%   |
| NVMe | 2         | 2      | 2.33%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Toshiba DT01ACA050 500GB      | 1         | 1      | 33.33%  |
| Seagate ST31000528AS 1TB      | 1         | 1      | 33.33%  |
| Hitachi HDS721050CLA360 500GB | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 33.33%  |
| Seagate | 1         | 1      | 33.33%  |
| Hitachi | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 210       | 355    | 52.5%   |
| Works    | 104       | 158    | 26%     |
| Malfunc  | 83        | 97     | 20.75%  |
| Failed   | 3         | 3      | 0.75%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 316       | 78.22%  |
| AMD                          | 23        | 5.69%   |
| Samsung Electronics          | 14        | 3.47%   |
| Nvidia                       | 7         | 1.73%   |
| Realtek Semiconductor        | 6         | 1.49%   |
| ADATA Technology             | 5         | 1.24%   |
| VIA Technologies             | 4         | 0.99%   |
| SK hynix                     | 4         | 0.99%   |
| Silicon Motion               | 4         | 0.99%   |
| Micron Technology            | 4         | 0.99%   |
| ASMedia Technology           | 4         | 0.99%   |
| MAXIO Technology (Hangzhou)  | 2         | 0.5%    |
| Kingston Technology Company  | 2         | 0.5%    |
| JMicron Technology           | 2         | 0.5%    |
| Toshiba America Info Systems | 1         | 0.25%   |
| SanDisk                      | 1         | 0.25%   |
| Micron/Crucial Technology    | 1         | 0.25%   |
| Marvell Technology Group     | 1         | 0.25%   |
| KIOXIA                       | 1         | 0.25%   |
| Hosin Global Electronics     | 1         | 0.25%   |
| Broadcom / LSI               | 1         | 0.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 32        | 6.54%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 30        | 6.13%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 28        | 5.73%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 26        | 5.32%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 26        | 5.32%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 21        | 4.29%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 18        | 3.68%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 17        | 3.48%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 16        | 3.27%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 16        | 3.27%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 16        | 3.27%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 12        | 2.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 12        | 2.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 11        | 2.25%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 10        | 2.04%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 7         | 1.43%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7         | 1.43%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 7         | 1.43%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 7         | 1.43%   |
| Intel SATA Controller [RAID mode]                                                       | 6         | 1.23%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6         | 1.23%   |
| Intel SSD 670p Series [Keystone Harbor]                                                 | 5         | 1.02%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 5         | 1.02%   |
| ADATA XPG GAMMIXS1 1L, XPG GAMMIX S5, LEGEND 710 / 740, SWORDFISH NVMe SSD (DRAM-less)  | 5         | 1.02%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 4         | 0.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4         | 0.82%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 4         | 0.82%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                       | 4         | 0.82%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4         | 0.82%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4         | 0.82%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 3         | 0.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3         | 0.61%   |
| Nvidia MCP79 AHCI Controller                                                            | 3         | 0.61%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 3         | 0.61%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 0.61%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3         | 0.61%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3         | 0.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 3         | 0.61%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 3         | 0.61%   |
| VIA Serial ATA Controller                                                               | 2         | 0.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 253       | 61.11%  |
| IDE  | 79        | 19.08%  |
| NVMe | 50        | 12.08%  |
| RAID | 30        | 7.25%   |
| SAS  | 1         | 0.24%   |
| SCSI | 1         | 0.24%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 341       | 92.41%  |
| AMD    | 27        | 7.32%   |
| ARM    | 1         | 0.27%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Genuine CPU U7300 @ 1.30GHz           | 22        | 5.93%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 8         | 2.16%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 7         | 1.89%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 6         | 1.62%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 6         | 1.62%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 6         | 1.62%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 6         | 1.62%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 5         | 1.35%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 5         | 1.35%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 5         | 1.35%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 5         | 1.35%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 5         | 1.35%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 5         | 1.35%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 4         | 1.08%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 4         | 1.08%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 4         | 1.08%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 4         | 1.08%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 4         | 1.08%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 4         | 1.08%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 4         | 1.08%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 4         | 1.08%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 3         | 0.81%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 3         | 0.81%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 3         | 0.81%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 3         | 0.81%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 3         | 0.81%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 3         | 0.81%   |
| Intel Core i7-2760QM CPU @ 2.40GHz          | 3         | 0.81%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 3         | 0.81%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3         | 0.81%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 3         | 0.81%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 0.81%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 3         | 0.81%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 3         | 0.81%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 3         | 0.81%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 3         | 0.81%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3         | 0.81%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 3         | 0.81%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 3         | 0.81%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz         | 2         | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 84        | 22.64%  |
| Intel Core i3           | 76        | 20.49%  |
| Intel Core i7           | 45        | 12.13%  |
| Intel Pentium           | 25        | 6.74%   |
| Intel Genuine           | 24        | 6.47%   |
| Intel Core 2 Duo        | 19        | 5.12%   |
| Intel Pentium Dual-Core | 18        | 4.85%   |
| Other                   | 16        | 4.31%   |
| Intel Celeron           | 15        | 4.04%   |
| AMD Ryzen 5             | 8         | 2.16%   |
| Intel Atom              | 6         | 1.62%   |
| Intel Xeon              | 5         | 1.35%   |
| Intel Pentium Dual      | 5         | 1.35%   |
| AMD Ryzen 7             | 5         | 1.35%   |
| Intel Core 2 Quad       | 2         | 0.54%   |
| AMD Ryzen 5 PRO         | 2         | 0.54%   |
| AMD A4                  | 2         | 0.54%   |
| Intel Xeon Gold         | 1         | 0.27%   |
| Intel Pentium D         | 1         | 0.27%   |
| Intel Pentium 4         | 1         | 0.27%   |
| Intel Core i9           | 1         | 0.27%   |
| ARM Allwinner           | 1         | 0.27%   |
| AMD Ryzen 9             | 1         | 0.27%   |
| AMD Ryzen 3             | 1         | 0.27%   |
| AMD FX                  | 1         | 0.27%   |
| AMD E2                  | 1         | 0.27%   |
| AMD E1                  | 1         | 0.27%   |
| AMD C-70                | 1         | 0.27%   |
| AMD Athlon Neo X2       | 1         | 0.27%   |
| AMD Athlon II Dual-Core | 1         | 0.27%   |
| AMD Athlon 64           | 1         | 0.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 256       | 69.19%  |
| 4      | 82        | 22.16%  |
| 6      | 12        | 3.24%   |
| 8      | 6         | 1.62%   |
| 1      | 5         | 1.35%   |
| 10     | 3         | 0.81%   |
| 16     | 2         | 0.54%   |
| 40     | 1         | 0.27%   |
| 14     | 1         | 0.27%   |
| 12     | 1         | 0.27%   |
| 3      | 1         | 0.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 367       | 99.46%  |
| 2      | 2         | 0.54%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 224       | 60.54%  |
| 1      | 145       | 39.19%  |
| 4      | 1         | 0.27%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 363       | 98.11%  |
| Unknown        | 5         | 1.35%   |
| 32-bit         | 2         | 0.54%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 159       | 40.66%  |
| 0x306a9    | 34        | 8.7%    |
| 0x206a7    | 27        | 6.91%   |
| 0x1067a    | 24        | 6.14%   |
| 0x20655    | 18        | 4.6%    |
| 0x40651    | 13        | 3.32%   |
| 0x406e3    | 12        | 3.07%   |
| 0x306c3    | 12        | 3.07%   |
| 0x306d4    | 9         | 2.3%    |
| 0x806e9    | 8         | 2.05%   |
| 0x30678    | 8         | 2.05%   |
| 0x906e9    | 5         | 1.28%   |
| 0x806ea    | 5         | 1.28%   |
| 0x6fd      | 5         | 1.28%   |
| 0x20652    | 3         | 0.77%   |
| 0x0a50000d | 3         | 0.77%   |
| 0x806ec    | 2         | 0.51%   |
| 0x706a8    | 2         | 0.51%   |
| 0x6fb      | 2         | 0.51%   |
| 0x506e3    | 2         | 0.51%   |
| 0x506c9    | 2         | 0.51%   |
| 0x406c4    | 2         | 0.51%   |
| 0x306e4    | 2         | 0.51%   |
| 0x30661    | 2         | 0.51%   |
| 0x10676    | 2         | 0.51%   |
| 0x08701021 | 2         | 0.51%   |
| 0x08600106 | 2         | 0.51%   |
| 0x0800820d | 2         | 0.51%   |
| 0x05000119 | 2         | 0.51%   |
| 0xf65      | 1         | 0.26%   |
| 0xa0652    | 1         | 0.26%   |
| 0x906eb    | 1         | 0.26%   |
| 0x906a4    | 1         | 0.26%   |
| 0x806c1    | 1         | 0.26%   |
| 0x706a1    | 1         | 0.26%   |
| 0x6ec      | 1         | 0.26%   |
| 0x6e8      | 1         | 0.26%   |
| 0x50654    | 1         | 0.26%   |
| 0x406c3    | 1         | 0.26%   |
| 0x206d7    | 1         | 0.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Penryn           | 58        | 15.63%  |
| IvyBridge        | 53        | 14.29%  |
| Haswell          | 42        | 11.32%  |
| SandyBridge      | 41        | 11.05%  |
| KabyLake         | 36        | 9.7%    |
| Westmere         | 22        | 5.93%   |
| Skylake          | 22        | 5.93%   |
| Silvermont       | 16        | 4.31%   |
| Broadwell        | 13        | 3.5%    |
| Core             | 11        | 2.96%   |
| TigerLake        | 9         | 2.43%   |
| Zen 3            | 6         | 1.62%   |
| Zen 2            | 5         | 1.35%   |
| Unknown          | 5         | 1.35%   |
| Zen+             | 4         | 1.08%   |
| Goldmont plus    | 4         | 1.08%   |
| Alderlake Hybrid | 3         | 0.81%   |
| P6               | 2         | 0.54%   |
| NetBurst         | 2         | 0.54%   |
| K8 Hammer        | 2         | 0.54%   |
| Jaguar           | 2         | 0.54%   |
| Goldmont         | 2         | 0.54%   |
| Excavator        | 2         | 0.54%   |
| CometLake        | 2         | 0.54%   |
| Bonnell          | 2         | 0.54%   |
| Bobcat           | 2         | 0.54%   |
| Zen              | 1         | 0.27%   |
| K10              | 1         | 0.27%   |
| Bulldozer        | 1         | 0.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 285       | 62.5%   |
| Nvidia                                       | 98        | 21.49%  |
| AMD                                          | 69        | 15.13%  |
| VIA Technologies                             | 2         | 0.44%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.22%   |
| Matrox Electronics Systems                   | 1         | 0.22%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 32        | 6.97%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 28        | 6.1%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 27        | 5.88%   |
| Nvidia GT218M [GeForce G210M]                                                            | 22        | 4.79%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 20        | 4.36%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 17        | 3.7%    |
| Intel Core Processor Integrated Graphics Controller                                      | 15        | 3.27%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 15        | 3.27%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 12        | 2.61%   |
| Intel HD Graphics 620                                                                    | 12        | 2.61%   |
| Intel UHD Graphics 620                                                                   | 11        | 2.4%    |
| Intel HD Graphics 5500                                                                   | 11        | 2.4%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 11        | 2.4%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 10        | 2.18%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 10        | 2.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9         | 1.96%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 1.96%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 1.53%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 6         | 1.31%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 1.31%   |
| Intel HD Graphics 630                                                                    | 5         | 1.09%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 0.87%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 4         | 0.87%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 0.65%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 3         | 0.65%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 3         | 0.65%   |
| Intel HD Graphics 530                                                                    | 3         | 0.65%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 0.65%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 3         | 0.65%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 3         | 0.65%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 0.65%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 2         | 0.44%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 0.44%   |
| Nvidia GP107M [GeForce MX350]                                                            | 2         | 0.44%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 0.44%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 2         | 0.44%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 2         | 0.44%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.44%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 2         | 0.44%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2         | 0.44%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 200       | 53.91%  |
| Intel + Nvidia | 58        | 15.63%  |
| 1 x AMD        | 43        | 11.59%  |
| 1 x Nvidia     | 38        | 10.24%  |
| Intel + AMD    | 25        | 6.74%   |
| 1 x VIA        | 2         | 0.54%   |
| Other          | 1         | 0.27%   |
| 2 x Nvidia     | 1         | 0.27%   |
| 1 x XGI        | 1         | 0.27%   |
| 1 x Matrox     | 1         | 0.27%   |
| AMD + Nvidia   | 1         | 0.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 331       | 88.03%  |
| Proprietary | 29        | 7.71%   |
| Unknown     | 16        | 4.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 243       | 64.29%  |
| 1.01-2.0   | 58        | 15.34%  |
| 0.01-0.5   | 40        | 10.58%  |
| 0.51-1.0   | 21        | 5.56%   |
| 3.01-4.0   | 9         | 2.38%   |
| 7.01-8.0   | 4         | 1.06%   |
| 5.01-6.0   | 2         | 0.53%   |
| 2.01-3.0   | 1         | 0.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 61        | 16.01%  |
| Samsung Electronics     | 60        | 15.75%  |
| LG Display              | 45        | 11.81%  |
| BOE                     | 36        | 9.45%   |
| Acer                    | 29        | 7.61%   |
| Chimei Innolux          | 26        | 6.82%   |
| Hewlett-Packard         | 17        | 4.46%   |
| AOC                     | 16        | 4.2%    |
| Chi Mei Optoelectronics | 14        | 3.67%   |
| Apple                   | 8         | 2.1%    |
| Goldstar                | 7         | 1.84%   |
| KTC                     | 6         | 1.57%   |
| Dell                    | 5         | 1.31%   |
| Lenovo                  | 4         | 1.05%   |
| BenQ                    | 4         | 1.05%   |
| Ancor Communications    | 4         | 1.05%   |
| Unknown                 | 4         | 1.05%   |
| Sharp                   | 3         | 0.79%   |
| InfoVision              | 3         | 0.79%   |
| Unknown (XXX)           | 2         | 0.52%   |
| Unknown                 | 2         | 0.52%   |
| SKY                     | 2         | 0.52%   |
| PANDA                   | 2         | 0.52%   |
| MStar                   | 2         | 0.52%   |
| Fujitsu Siemens         | 2         | 0.52%   |
| ___                     | 1         | 0.26%   |
| Westinghouse            | 1         | 0.26%   |
| TSN                     | 1         | 0.26%   |
| TMU                     | 1         | 0.26%   |
| TGC                     | 1         | 0.26%   |
| PTW                     | 1         | 0.26%   |
| PiLot                   | 1         | 0.26%   |
| MDA                     | 1         | 0.26%   |
| LGD                     | 1         | 0.26%   |
| ITE                     | 1         | 0.26%   |
| InnoLux Display         | 1         | 0.26%   |
| HKC                     | 1         | 0.26%   |
| Hitachi                 | 1         | 0.26%   |
| EMP                     | 1         | 0.26%   |
| EDW                     | 1         | 0.26%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO213C 1366x768 309x174mm 14.0-inch            | 22        | 5.71%   |
| Acer V193HQ ACR00F9 1366x768 410x230mm 18.5-inch                         | 22        | 5.71%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                           | 5         | 1.3%    |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch     | 4         | 1.04%   |
| LG Display LCD Monitor LGD04BD 1366x768 344x194mm 15.5-inch              | 4         | 1.04%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 4         | 1.04%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 4         | 1.04%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A4 1366x768 344x194mm 15.5-inch | 4         | 1.04%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                     | 4         | 1.04%   |
| Unknown                                                                  | 4         | 1.04%   |
| Samsung Electronics SMS22A100 SAM0868 1920x1080 477x268mm 21.5-inch      | 3         | 0.78%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch     | 3         | 0.78%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 3         | 0.78%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                     | 3         | 0.78%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch            | 3         | 0.78%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 0.78%   |
| AOC F22 AOC2200 1920x1080 476x268mm 21.5-inch                            | 3         | 0.78%   |
| Unknown (XXX) HDMI XXX0029 1920x1080 1152x648mm 52.0-inch                | 2         | 0.52%   |
| Sharp HDMI SHP10DB 1920x1080 1330x750mm 60.1-inch                        | 2         | 0.52%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch       | 2         | 0.52%   |
| Samsung Electronics SMBX1931N SAM0768 1366x768 410x230mm 18.5-inch       | 2         | 0.52%   |
| Samsung Electronics SMB2030N SAM0634 1600x900 443x249mm 20.0-inch        | 2         | 0.52%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 309x174mm 14.0-inch     | 2         | 0.52%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch     | 2         | 0.52%   |
| Samsung Electronics LCD Monitor SDC4146 1366x768 344x194mm 15.5-inch     | 2         | 0.52%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                         | 2         | 0.52%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch            | 2         | 0.52%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch              | 2         | 0.52%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch              | 2         | 0.52%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 2         | 0.52%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 2         | 0.52%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 2         | 0.52%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 2         | 0.52%   |
| KTC W9023S5 KTC1852 1360x768 410x230mm 18.5-inch                         | 2         | 0.52%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 2         | 0.52%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.52%   |
| Chimei Innolux LCD Monitor CMN14D3 1920x1080 309x173mm 13.9-inch         | 2         | 0.52%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 2         | 0.52%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch         | 2         | 0.52%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 173       | 49.86%  |
| 1920x1080 (FHD)    | 97        | 27.95%  |
| 1600x900 (HD+)     | 17        | 4.9%    |
| 1440x900 (WXGA+)   | 13        | 3.75%   |
| 1280x1024 (SXGA)   | 7         | 2.02%   |
| 2560x1440 (QHD)    | 6         | 1.73%   |
| 1680x1050 (WSXGA+) | 6         | 1.73%   |
| 1280x800 (WXGA)    | 6         | 1.73%   |
| 1360x768           | 5         | 1.44%   |
| 3840x2160 (4K)     | 4         | 1.15%   |
| 1920x540           | 2         | 0.58%   |
| 1920x1200 (WUXGA)  | 2         | 0.58%   |
| 3840x2400          | 1         | 0.29%   |
| 2880x1800          | 1         | 0.29%   |
| 2160x1440          | 1         | 0.29%   |
| 1680x945           | 1         | 0.29%   |
| 1600x1200          | 1         | 0.29%   |
| 1280x720 (HD)      | 1         | 0.29%   |
| 1152x864           | 1         | 0.29%   |
| 1024x768 (XGA)     | 1         | 0.29%   |
| 1024x600           | 1         | 0.29%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 136       | 35.6%   |
| 18      | 48        | 12.57%  |
| 14      | 43        | 11.26%  |
| 13      | 29        | 7.59%   |
| 21      | 16        | 4.19%   |
| 19      | 15        | 3.93%   |
| 23      | 13        | 3.4%    |
| 17      | 12        | 3.14%   |
| 20      | 10        | 2.62%   |
| 27      | 9         | 2.36%   |
| 12      | 9         | 2.36%   |
| Unknown | 9         | 2.36%   |
| 24      | 6         | 1.57%   |
| 52      | 5         | 1.31%   |
| 22      | 4         | 1.05%   |
| 11      | 3         | 0.79%   |
| 60      | 2         | 0.52%   |
| 40      | 2         | 0.52%   |
| 31      | 2         | 0.52%   |
| 10      | 2         | 0.52%   |
| 72      | 1         | 0.26%   |
| 48      | 1         | 0.26%   |
| 46      | 1         | 0.26%   |
| 37      | 1         | 0.26%   |
| 32      | 1         | 0.26%   |
| 29      | 1         | 0.26%   |
| 16      | 1         | 0.26%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 198       | 52.11%  |
| 401-500     | 87        | 22.89%  |
| 501-600     | 28        | 7.37%   |
| 201-300     | 22        | 5.79%   |
| 351-400     | 19        | 5%      |
| 1001-1500   | 9         | 2.37%   |
| Unknown     | 9         | 2.37%   |
| 801-900     | 3         | 0.79%   |
| 601-700     | 3         | 0.79%   |
| 701-800     | 1         | 0.26%   |
| 1501-2000   | 1         | 0.26%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 291       | 85.09%  |
| 16/10   | 28        | 8.19%   |
| Unknown | 7         | 2.05%   |
| 5/4     | 6         | 1.75%   |
| 4/3     | 5         | 1.46%   |
| 32/9    | 2         | 0.58%   |
| 3/2     | 2         | 0.58%   |
| 6/5     | 1         | 0.29%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 133       | 35%     |
| 81-90          | 67        | 17.63%  |
| 141-150        | 50        | 13.16%  |
| 151-200        | 32        | 8.42%   |
| 201-250        | 30        | 7.89%   |
| More than 1000 | 9         | 2.37%   |
| 301-350        | 9         | 2.37%   |
| Unknown        | 9         | 2.37%   |
| 61-70          | 8         | 2.11%   |
| 121-130        | 7         | 1.84%   |
| 71-80          | 6         | 1.58%   |
| 351-500        | 4         | 1.05%   |
| 111-120        | 4         | 1.05%   |
| 501-1000       | 4         | 1.05%   |
| 51-60          | 3         | 0.79%   |
| 41-50          | 2         | 0.53%   |
| 131-140        | 2         | 0.53%   |
| 251-300        | 1         | 0.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 155       | 41.11%  |
| 51-100        | 130       | 34.48%  |
| 121-160       | 62        | 16.45%  |
| 1-50          | 11        | 2.92%   |
| Unknown       | 9         | 2.39%   |
| 161-240       | 7         | 1.86%   |
| More than 240 | 3         | 0.8%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 306       | 81.6%   |
| 2     | 52        | 13.87%  |
| 0     | 15        | 4%      |
| 3     | 2         | 0.53%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 233       | 38.77%  |
| Qualcomm Atheros                | 106       | 17.64%  |
| Intel                           | 100       | 16.64%  |
| Broadcom                        | 46        | 7.65%   |
| Ralink Technology               | 37        | 6.16%   |
| Ralink                          | 14        | 2.33%   |
| MediaTek                        | 8         | 1.33%   |
| Samsung Electronics             | 7         | 1.16%   |
| Qualcomm Atheros Communications | 7         | 1.16%   |
| Broadcom Limited                | 6         | 1%      |
| Nvidia                          | 5         | 0.83%   |
| Xiaomi                          | 4         | 0.67%   |
| TP-Link                         | 4         | 0.67%   |
| Marvell Technology Group        | 4         | 0.67%   |
| D-Link                          | 4         | 0.67%   |
| VIA Technologies                | 3         | 0.5%    |
| D-Link System                   | 3         | 0.5%    |
| Sierra Wireless                 | 2         | 0.33%   |
| Huawei Technologies             | 2         | 0.33%   |
| Hewlett-Packard                 | 2         | 0.33%   |
| ZTopInc                         | 1         | 0.17%   |
| ZTE WCDMA Technologies MSM      | 1         | 0.17%   |
| LG Electronics                  | 1         | 0.17%   |
| AMD                             | 1         | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 123       | 17.93%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 74        | 10.79%  |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 22        | 3.21%   |
| Ralink MT7601U Wireless Adapter                                        | 22        | 3.21%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 22        | 3.21%   |
| Broadcom BCM43142 802.11b/g/n                                          | 18        | 2.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 16        | 2.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 16        | 2.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 15        | 2.19%   |
| Intel Wireless 8265 / 8275                                             | 15        | 2.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 11        | 1.6%    |
| Intel Ethernet Connection (4) I219-LM                                  | 11        | 1.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 11        | 1.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 8         | 1.17%   |
| Ralink RT5370 Wireless Adapter                                         | 8         | 1.17%   |
| Qualcomm Atheros AR9271 802.11n                                        | 7         | 1.02%   |
| Intel Wireless 8260                                                    | 7         | 1.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 6         | 0.87%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 6         | 0.87%   |
| Intel Wireless 7265                                                    | 6         | 0.87%   |
| Intel Wireless 7260                                                    | 6         | 0.87%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 5         | 0.73%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 5         | 0.73%   |
| Intel Wi-Fi 6 AX201                                                    | 5         | 0.73%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 0.73%   |
| Intel Ethernet Connection I218-LM                                      | 5         | 0.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 5         | 0.73%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 5         | 0.73%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 4         | 0.58%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 4         | 0.58%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 4         | 0.58%   |
| MediaTek Infinix SMART 5                                               | 4         | 0.58%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 4         | 0.58%   |
| Intel Centrino Ultimate-N 6300                                         | 4         | 0.58%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3         | 0.44%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 3         | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 0.44%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 3         | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3         | 0.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 3         | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 86        | 26.14%  |
| Qualcomm Atheros                | 69        | 20.97%  |
| Realtek Semiconductor           | 56        | 17.02%  |
| Ralink Technology               | 37        | 11.25%  |
| Broadcom                        | 37        | 11.25%  |
| Ralink                          | 14        | 4.26%   |
| Qualcomm Atheros Communications | 7         | 2.13%   |
| TP-Link                         | 4         | 1.22%   |
| MediaTek                        | 4         | 1.22%   |
| D-Link                          | 4         | 1.22%   |
| D-Link System                   | 3         | 0.91%   |
| Sierra Wireless                 | 2         | 0.61%   |
| Hewlett-Packard                 | 2         | 0.61%   |
| Broadcom Limited                | 2         | 0.61%   |
| ZTopInc                         | 1         | 0.3%    |
| Marvell Technology Group        | 1         | 0.3%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 22        | 6.65%   |
| Ralink MT7601U Wireless Adapter                                | 22        | 6.65%   |
| Broadcom BCM43142 802.11b/g/n                                  | 18        | 5.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 16        | 4.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 16        | 4.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 15        | 4.53%   |
| Intel Wireless 8265 / 8275                                     | 15        | 4.53%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 11        | 3.32%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 8         | 2.42%   |
| Ralink RT5370 Wireless Adapter                                 | 8         | 2.42%   |
| Qualcomm Atheros AR9271 802.11n                                | 7         | 2.11%   |
| Intel Wireless 8260                                            | 7         | 2.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6         | 1.81%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 6         | 1.81%   |
| Intel Wireless 7265                                            | 6         | 1.81%   |
| Intel Wireless 7260                                            | 6         | 1.81%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 5         | 1.51%   |
| Intel Wi-Fi 6 AX201                                            | 5         | 1.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 1.51%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 4         | 1.21%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 4         | 1.21%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 1.21%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 3         | 0.91%   |
| Intel Wireless 3160                                            | 3         | 0.91%   |
| Intel WiFi Link 5100                                           | 3         | 0.91%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 3         | 0.91%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 3         | 0.91%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 0.91%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 0.6%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 2         | 0.6%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 2         | 0.6%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 2         | 0.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 0.6%    |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 0.6%    |
| Ralink RT2870 Wireless Adapter                                 | 2         | 0.6%    |
| Ralink RT2561/RT61 rev B 802.11g                               | 2         | 0.6%    |
| Ralink RT2561/RT61 802.11g PCI                                 | 2         | 0.6%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 0.6%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 0.6%    |
| Intel Wireless 3165                                            | 2         | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 201       | 57.76%  |
| Intel                    | 60        | 17.24%  |
| Qualcomm Atheros         | 43        | 12.36%  |
| Broadcom                 | 15        | 4.31%   |
| Nvidia                   | 5         | 1.44%   |
| Xiaomi                   | 4         | 1.15%   |
| MediaTek                 | 4         | 1.15%   |
| Broadcom Limited         | 4         | 1.15%   |
| VIA Technologies         | 3         | 0.86%   |
| Samsung Electronics      | 3         | 0.86%   |
| Marvell Technology Group | 3         | 0.86%   |
| LG Electronics           | 1         | 0.29%   |
| Huawei Technologies      | 1         | 0.29%   |
| AMD                      | 1         | 0.29%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 123       | 35.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 74        | 21.2%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 22        | 6.3%    |
| Intel Ethernet Connection (4) I219-LM                                  | 11        | 3.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 11        | 3.15%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 5         | 1.43%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 1.43%   |
| Intel Ethernet Connection I218-LM                                      | 5         | 1.43%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 5         | 1.43%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 4         | 1.15%   |
| MediaTek Infinix SMART 5                                               | 4         | 1.15%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3         | 0.86%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 3         | 0.86%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 0.86%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3         | 0.86%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 3         | 0.86%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 0.86%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 3         | 0.86%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 3         | 0.86%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2         | 0.57%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 2         | 0.57%   |
| Nvidia MCP79 Ethernet                                                  | 2         | 0.57%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 2         | 0.57%   |
| Intel PRO/100 VE Network Connection                                    | 2         | 0.57%   |
| Intel I211 Gigabit Network Connection                                  | 2         | 0.57%   |
| Intel Ethernet Connection (5) I219-LM                                  | 2         | 0.57%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 0.57%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 0.57%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 0.57%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 2         | 0.57%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1         | 0.29%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.29%   |
| Realtek PCIe GbE Family Controller                                     | 1         | 0.29%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 0.29%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 1         | 0.29%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                          | 1         | 0.29%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.29%   |
| Nvidia MCP89 Ethernet                                                  | 1         | 0.29%   |
| Nvidia MCP77 Ethernet                                                  | 1         | 0.29%   |
| Nvidia MCP73 Ethernet                                                  | 1         | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 336       | 52.01%  |
| WiFi     | 304       | 47.06%  |
| Modem    | 6         | 0.93%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 247       | 64.32%  |
| Ethernet | 137       | 35.68%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 232       | 62.03%  |
| 1     | 133       | 35.56%  |
| 0     | 8         | 2.14%   |
| 3     | 1         | 0.27%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 369       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 61        | 33.7%   |
| Qualcomm Atheros Communications | 21        | 11.6%   |
| Realtek Semiconductor           | 16        | 8.84%   |
| Broadcom                        | 14        | 7.73%   |
| Cambridge Silicon Radio         | 11        | 6.08%   |
| IMC Networks                    | 9         | 4.97%   |
| Lite-On Technology              | 8         | 4.42%   |
| Apple                           | 8         | 4.42%   |
| Ralink                          | 6         | 3.31%   |
| Foxconn / Hon Hai               | 6         | 3.31%   |
| Dell                            | 5         | 2.76%   |
| Toshiba                         | 3         | 1.66%   |
| Foxconn International           | 3         | 1.66%   |
| Integrated System Solution      | 2         | 1.1%    |
| SiW                             | 1         | 0.55%   |
| Ralink Technology               | 1         | 0.55%   |
| Marvell Semiconductor           | 1         | 0.55%   |
| Hewlett-Packard                 | 1         | 0.55%   |
| Chicony Electronics             | 1         | 0.55%   |
| ASUSTek Computer                | 1         | 0.55%   |
| Alps Electric                   | 1         | 0.55%   |
| Actions                         | 1         | 0.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 37        | 20.44%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 11        | 6.08%   |
| Realtek Bluetooth Radio                               | 9         | 4.97%   |
| Qualcomm Atheros  Bluetooth Device                    | 8         | 4.42%   |
| Ralink RT3290 Bluetooth                               | 6         | 3.31%   |
| Intel AX201 Bluetooth                                 | 6         | 3.31%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 5         | 2.76%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 5         | 2.76%   |
| IMC Networks Bluetooth Device                         | 5         | 2.76%   |
| Broadcom BCM43142 Bluetooth 4.0                       | 5         | 2.76%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 4         | 2.21%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 4         | 2.21%   |
| Apple Bluetooth Host Controller                       | 4         | 2.21%   |
| Realtek RTL8723B Bluetooth                            | 3         | 1.66%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 3         | 1.66%   |
| Foxconn International BCM43142A0 Bluetooth module     | 3         | 1.66%   |
| Foxconn / Hon Hai Bluetooth Device                    | 3         | 1.66%   |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 3         | 1.66%   |
| Toshiba Bluetooth Device                              | 2         | 1.1%    |
| Realtek  Bluetooth 4.2 Adapter                        | 2         | 1.1%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 2         | 1.1%    |
| Qualcomm Atheros AR9462 Bluetooth                     | 2         | 1.1%    |
| Lite-On Wireless_Device                               | 2         | 1.1%    |
| Lite-On BCM43142A0                                    | 2         | 1.1%    |
| Intel Wireless-AC 3168 Bluetooth                      | 2         | 1.1%    |
| Intel AX211 Bluetooth                                 | 2         | 1.1%    |
| Intel AX200 Bluetooth                                 | 2         | 1.1%    |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 2         | 1.1%    |
| IMC Networks Wireless_Device                          | 2         | 1.1%    |
| Dell Wireless 365 Bluetooth                           | 2         | 1.1%    |
| Dell BCM20702A0 Bluetooth Module                      | 2         | 1.1%    |
| Broadcom BCM2045B (BDC-2.1)                           | 2         | 1.1%    |
| Apple Bluetooth USB Host Controller                   | 2         | 1.1%    |
| Toshiba BCM43142A0                                    | 1         | 0.55%   |
| SiW SiW                                               | 1         | 0.55%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter               | 1         | 0.55%   |
| Realtek RTL8821A Bluetooth                            | 1         | 0.55%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter          | 1         | 0.55%   |
| Qualcomm Atheros Bluetooth                            | 1         | 0.55%   |
| Marvell Bluetooth and Wireless LAN Composite Device   | 1         | 0.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 325       | 68.86%  |
| Nvidia                 | 74        | 15.68%  |
| AMD                    | 54        | 11.44%  |
| JMTek                  | 4         | 0.85%   |
| VIA Technologies       | 3         | 0.64%   |
| Goldvish               | 2         | 0.42%   |
| Texas Instruments      | 1         | 0.21%   |
| Samsung Electronics    | 1         | 0.21%   |
| Medeli Electronics     | 1         | 0.21%   |
| Logitech               | 1         | 0.21%   |
| Logic3 / SpectraVideo  | 1         | 0.21%   |
| Guillemot              | 1         | 0.21%   |
| GN Netcom              | 1         | 0.21%   |
| Generalplus Technology | 1         | 0.21%   |
| C-Media Electronics    | 1         | 0.21%   |
| ASUSTek Computer       | 1         | 0.21%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 50        | 9.28%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 42        | 7.79%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 42        | 7.79%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 33        | 6.12%   |
| Nvidia High Definition Audio Controller                                                           | 27        | 5.01%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 24        | 4.45%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 22        | 4.08%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 20        | 3.71%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 20        | 3.71%   |
| Intel 8 Series HD Audio Controller                                                                | 20        | 3.71%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 13        | 2.41%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 13        | 2.41%   |
| Intel Broadwell-U Audio Controller                                                                | 13        | 2.41%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 12        | 2.23%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 10        | 1.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 9         | 1.67%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 8         | 1.48%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 1.3%    |
| Nvidia GF119 HDMI Audio Controller                                                                | 6         | 1.11%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 1.11%   |
| Intel CM238 HD Audio Controller                                                                   | 5         | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 0.93%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 5         | 0.93%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5         | 0.93%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 4         | 0.74%   |
| JMTek USB PnP Audio Device                                                                        | 4         | 0.74%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 0.74%   |
| AMD FCH Azalia Controller                                                                         | 4         | 0.74%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 3         | 0.56%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.56%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.56%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.56%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 0.56%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 3         | 0.56%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 0.56%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 0.56%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 0.56%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.37%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.37%   |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 0.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 64        | 25.4%   |
| SK hynix            | 43        | 17.06%  |
| Samsung Electronics | 43        | 17.06%  |
| Micron Technology   | 27        | 10.71%  |
| Kingston            | 18        | 7.14%   |
| A-DATA Technology   | 12        | 4.76%   |
| Ramaxel Technology  | 6         | 2.38%   |
| Crucial             | 6         | 2.38%   |
| Nanya Technology    | 5         | 1.98%   |
| Unknown (ABCD)      | 3         | 1.19%   |
| TwinMOS             | 3         | 1.19%   |
| Corsair             | 3         | 1.19%   |
| Team                | 2         | 0.79%   |
| Patriot             | 2         | 0.79%   |
| Goldkey             | 2         | 0.79%   |
| Unknown             | 2         | 0.79%   |
| Unifosa             | 1         | 0.4%    |
| Thermaltake         | 1         | 0.4%    |
| SemsoTai            | 1         | 0.4%    |
| Hikvision           | 1         | 0.4%    |
| GeIL                | 1         | 0.4%    |
| G.Skill             | 1         | 0.4%    |
| Elpida              | 1         | 0.4%    |
| Dynet               | 1         | 0.4%    |
| CSX                 | 1         | 0.4%    |
| ASint Technology    | 1         | 0.4%    |
| Asgard              | 1         | 0.4%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM 1066MT/s                           | 22        | 8.03%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 6         | 2.19%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 6         | 2.19%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 2.19%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 3         | 1.09%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 3         | 1.09%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 1.09%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.09%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 3         | 1.09%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 2         | 0.73%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 2         | 0.73%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 2         | 0.73%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 2         | 0.73%   |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 2         | 0.73%   |
| Unknown RAM Module 2GB DIMM 400MT/s                              | 2         | 0.73%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 2         | 0.73%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.73%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.73%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.73%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.73%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.73%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 0.73%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.73%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.73%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 0.73%   |
| Nanya RAM Module 8GB SODIMM DDR4 2667MT/s                        | 2         | 0.73%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM 1600MT/s                   | 2         | 0.73%   |
| Micron RAM 16ATF1G64HZ-2G1B1 8GB SODIMM DDR4 2133MT/s            | 2         | 0.73%   |
| Kingston RAM ACR256X64D3S1333C9 2GB SODIMM DDR3 1334MT/s         | 2         | 0.73%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                      | 2         | 0.73%   |
| Unknown                                                          | 2         | 0.73%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.36%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 0.36%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                     | 1         | 0.36%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 0.36%   |
| Unknown RAM Module 4GB SODIMM DDR2                               | 1         | 0.36%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 1         | 0.36%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                        | 1         | 0.36%   |
| Unknown RAM Module 4GB DIMM 400MT/s                              | 1         | 0.36%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 99        | 47.83%  |
| DDR4    | 46        | 22.22%  |
| Unknown | 31        | 14.98%  |
| DDR2    | 11        | 5.31%   |
| SDRAM   | 10        | 4.83%   |
| LPDDR4  | 5         | 2.42%   |
| LPDDR3  | 2         | 0.97%   |
| LPDDR5  | 1         | 0.48%   |
| DDR5    | 1         | 0.48%   |
| DDR     | 1         | 0.48%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 129       | 63.86%  |
| DIMM         | 70        | 34.65%  |
| Row Of Chips | 3         | 1.49%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 109       | 47.81%  |
| 2048  | 49        | 21.49%  |
| 8192  | 45        | 19.74%  |
| 16384 | 9         | 3.95%   |
| 1024  | 8         | 3.51%   |
| 32768 | 5         | 2.19%   |
| 512   | 2         | 0.88%   |
| 65536 | 1         | 0.44%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 61        | 26.52%  |
| 1333    | 28        | 12.17%  |
| 1066    | 23        | 10%     |
| 2667    | 17        | 7.39%   |
| 3200    | 14        | 6.09%   |
| 2400    | 13        | 5.65%   |
| 2133    | 9         | 3.91%   |
| 800     | 9         | 3.91%   |
| 1334    | 8         | 3.48%   |
| 1067    | 7         | 3.04%   |
| Unknown | 7         | 3.04%   |
| 667     | 5         | 2.17%   |
| 4199    | 3         | 1.3%    |
| 400     | 3         | 1.3%    |
| 6400    | 2         | 0.87%   |
| 3800    | 2         | 0.87%   |
| 3600    | 2         | 0.87%   |
| 3266    | 2         | 0.87%   |
| 533     | 2         | 0.87%   |
| 3066    | 1         | 0.43%   |
| 3000    | 1         | 0.43%   |
| 2666    | 1         | 0.43%   |
| 2200    | 1         | 0.43%   |
| 2000    | 1         | 0.43%   |
| 1867    | 1         | 0.43%   |
| 1800    | 1         | 0.43%   |
| 1648    | 1         | 0.43%   |
| 1639    | 1         | 0.43%   |
| 1400    | 1         | 0.43%   |
| 333     | 1         | 0.43%   |
| 266     | 1         | 0.43%   |
| 200     | 1         | 0.43%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 11        | 55%     |
| Seiko Epson        | 4         | 20%     |
| Hewlett-Packard    | 3         | 15%     |
| Kyocera            | 1         | 5%      |
| Brother Industries | 1         | 5%      |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Canon LBP6000                                                         | 2         | 10%     |
| Canon CAPT USB Device                                                 | 2         | 10%     |
| Seiko Epson XP-243 245 247 Series                                     | 1         | 5%      |
| Seiko Epson XP-205 207 Series                                         | 1         | 5%      |
| Seiko Epson Printer                                                   | 1         | 5%      |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 5%      |
| Kyocera FS-1040                                                       | 1         | 5%      |
| HP LaserJet 1010                                                      | 1         | 5%      |
| HP Ink Tank 310 series                                                | 1         | 5%      |
| HP DeskJet 5810 series                                                | 1         | 5%      |
| Canon MG5700 series                                                   | 1         | 5%      |
| Canon MF4010 series                                                   | 1         | 5%      |
| Canon MF3010                                                          | 1         | 5%      |
| Canon LBP6030/6030B/6018L                                             | 1         | 5%      |
| Canon LBP3010/LBP3018/LBP3050                                         | 1         | 5%      |
| Canon LBP3000                                                         | 1         | 5%      |
| Canon LBP2900                                                         | 1         | 5%      |
| Brother MFC-J480DW                                                    | 1         | 5%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LIDE 25 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 67        | 30.32%  |
| Microdia                               | 29        | 13.12%  |
| Realtek Semiconductor                  | 23        | 10.41%  |
| Cheng Uei Precision Industry (Foxlink) | 14        | 6.33%   |
| Sunplus Innovation Technology          | 11        | 4.98%   |
| IMC Networks                           | 11        | 4.98%   |
| Bison Electronics                      | 11        | 4.98%   |
| Suyin                                  | 10        | 4.52%   |
| Apple                                  | 8         | 3.62%   |
| Syntek                                 | 6         | 2.71%   |
| Quanta                                 | 5         | 2.26%   |
| Silicon Motion                         | 3         | 1.36%   |
| Samsung Electronics                    | 3         | 1.36%   |
| Lite-On Technology                     | 3         | 1.36%   |
| Luxvisions Innotech Limited            | 2         | 0.9%    |
| Alcor Micro                            | 2         | 0.9%    |
| Acer                                   | 2         | 0.9%    |
| Sonix Technology                       | 1         | 0.45%   |
| Ricoh                                  | 1         | 0.45%   |
| Primax Electronics                     | 1         | 0.45%   |
| Pixart Imaging                         | 1         | 0.45%   |
| Microsoft                              | 1         | 0.45%   |
| Logitech                               | 1         | 0.45%   |
| GEMBIRD                                | 1         | 0.45%   |
| Cubeternet                             | 1         | 0.45%   |
| Aveo Technology                        | 1         | 0.45%   |
| Arkmicro Technologies                  | 1         | 0.45%   |
| ALi                                    | 1         | 0.45%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chicony Asus Integrated 0.3M UVC Webcam                                  | 22        | 9.91%   |
| Microdia Integrated_Webcam_HD                                            | 10        | 4.5%    |
| Chicony Integrated Camera                                                | 7         | 3.15%   |
| Chicony TOSHIBA Web Camera - HD                                          | 6         | 2.7%    |
| Bison Lenovo EasyCamera                                                  | 6         | 2.7%    |
| Microdia Laptop_Integrated_Webcam_HD                                     | 5         | 2.25%   |
| Sunplus Integrated_Webcam_HD                                             | 4         | 1.8%    |
| Realtek USB2.0 VGA UVC WebCam                                            | 4         | 1.8%    |
| Realtek Integrated_Webcam_HD                                             | 4         | 1.8%    |
| Chicony HP Truevision HD                                                 | 4         | 1.8%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                      | 4         | 1.8%    |
| Apple Built-in iSight                                                    | 4         | 1.8%    |
| Syntek Lenovo EasyCamera                                                 | 3         | 1.35%   |
| Suyin HP Truevision HD                                                   | 3         | 1.35%   |
| Samsung Galaxy series, misc. (MTP mode)                                  | 3         | 1.35%   |
| Microdia Laptop_Integrated_Webcam_E4HD                                   | 3         | 1.35%   |
| Microdia Integrated Webcam                                               | 3         | 1.35%   |
| IMC Networks Lenovo EasyCamera                                           | 3         | 1.35%   |
| IMC Networks Integrated Camera                                           | 3         | 1.35%   |
| Chicony HP HD Webcam [Fixed]                                             | 3         | 1.35%   |
| Chicony HD WebCam                                                        | 3         | 1.35%   |
| Suyin HD WebCam                                                          | 2         | 0.9%    |
| Sunplus Laptop_Integrated_Webcam_FHD                                     | 2         | 0.9%    |
| Realtek Integrated Webcam                                                | 2         | 0.9%    |
| Realtek HP Truevision HD                                                 | 2         | 0.9%    |
| Realtek Acer 640 x 480 laptop camera                                     | 2         | 0.9%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera                      | 2         | 0.9%    |
| IMC Networks USB2.0 HD UVC WebCam                                        | 2         | 0.9%    |
| Chicony USB2.0 VGA UVC WebCam                                            | 2         | 0.9%    |
| Chicony FJ Camera                                                        | 2         | 0.9%    |
| Chicony Acer CrystalEye Webcam                                           | 2         | 0.9%    |
| Cheng Uei Precision Industry (Foxlink) Webcam                            | 2         | 0.9%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                         | 2         | 0.9%    |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 2         | 0.9%    |
| Bison Integrated Camera                                                  | 2         | 0.9%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                                       | 2         | 0.9%    |
| Syntek USB2.0 Camera                                                     | 1         | 0.45%   |
| Syntek Integrated Camera                                                 | 1         | 0.45%   |
| Syntek EasyCamera                                                        | 1         | 0.45%   |
| Suyin WebCam                                                             | 1         | 0.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 15        | 65.22%  |
| Synaptics             | 4         | 17.39%  |
| AuthenTec             | 2         | 8.7%    |
| LighTuning Technology | 1         | 4.35%   |
| Elan Microelectronics | 1         | 4.35%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 7         | 30.43%  |
| Validity Sensors VFS491                                                    | 3         | 13.04%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 8.7%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 4.35%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 4.35%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 4.35%   |
| Synaptics WBDI Device                                                      | 1         | 4.35%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 4.35%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 4.35%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 4.35%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 4.35%   |
| Elan ELAN:Fingerprint                                                      | 1         | 4.35%   |
| AuthenTec AES2810                                                          | 1         | 4.35%   |
| AuthenTec AES1600                                                          | 1         | 4.35%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 14        | 93.33%  |
| OmniKey  | 1         | 6.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 8         | 53.33%  |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 26.67%  |
| OmniKey CardMan 4321                                                         | 1         | 6.67%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 6.67%   |
| Broadcom 58200                                                               | 1         | 6.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 261       | 68.32%  |
| 1     | 100       | 26.18%  |
| 2     | 16        | 4.19%   |
| 3     | 4         | 1.05%   |
| 7     | 1         | 0.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 48        | 32.88%  |
| Fingerprint reader       | 23        | 15.75%  |
| Net/wireless             | 19        | 13.01%  |
| Chipcard                 | 15        | 10.27%  |
| Communication controller | 10        | 6.85%   |
| Bluetooth                | 7         | 4.79%   |
| Multimedia controller    | 6         | 4.11%   |
| Sound                    | 4         | 2.74%   |
| Camera                   | 4         | 2.74%   |
| Storage                  | 3         | 2.05%   |
| Net/ethernet             | 3         | 2.05%   |
| Unassigned class         | 1         | 0.68%   |
| Storage/nvme             | 1         | 0.68%   |
| Storage/ata              | 1         | 0.68%   |
| Card reader              | 1         | 0.68%   |


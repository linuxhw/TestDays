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

Total: 511

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 51        | 14.17%  |
| Ubuntu 22.04       | 21        | 5.83%   |
| Ubuntu 18.04       | 20        | 5.56%   |
| OpenMandriva 4.3   | 17        | 4.72%   |
| OpenMandriva 4.2   | 15        | 4.17%   |
| Zorin 16           | 9         | 2.5%    |
| Zorin 17           | 7         | 1.94%   |
| OpenMandriva 23.03 | 7         | 1.94%   |
| Linux Mint 20.1    | 7         | 1.94%   |
| KDE neon 20.04     | 6         | 1.67%   |
| Fedora 39          | 6         | 1.67%   |
| Fedora 35          | 6         | 1.67%   |
| ArcoLinux Rolling  | 6         | 1.67%   |
| Pop!_OS 20.04      | 5         | 1.39%   |
| OpenMandriva 23.08 | 5         | 1.39%   |
| Arch               | 5         | 1.39%   |
| Ubuntu 21.04       | 4         | 1.11%   |
| Ubuntu 19.10       | 4         | 1.11%   |
| Pop!_OS 22.04      | 4         | 1.11%   |
| OpenMandriva 23.11 | 4         | 1.11%   |
| OpenMandriva 23.09 | 4         | 1.11%   |
| OpenMandriva 23.01 | 4         | 1.11%   |
| Manjaro            | 4         | 1.11%   |
| KDE neon 22.04     | 4         | 1.11%   |
| Fedora 37          | 4         | 1.11%   |
| Debian 11          | 4         | 1.11%   |
| Xubuntu 20.04      | 3         | 0.83%   |
| Ubuntu 20.10       | 3         | 0.83%   |
| ROSA R11           | 3         | 0.83%   |
| ROSA R10           | 3         | 0.83%   |
| OpenMandriva 24.01 | 3         | 0.83%   |
| MX 23              | 3         | 0.83%   |
| Linux Mint 20.2    | 3         | 0.83%   |
| Fedora 38          | 3         | 0.83%   |
| BlackPanther 18.1  | 3         | 0.83%   |
| Xubuntu 22.04      | 2         | 0.56%   |
| Ubuntu 21.10       | 2         | 0.56%   |
| Ubuntu 19.04       | 2         | 0.56%   |
| ROSA R8.1          | 2         | 0.56%   |
| Parrot 5.0         | 2         | 0.56%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 107       | 30.92%  |
| OpenMandriva  | 59        | 17.05%  |
| Fedora        | 23        | 6.65%   |
| Linux Mint    | 22        | 6.36%   |
| Zorin         | 17        | 4.91%   |
| Pop!_OS       | 12        | 3.47%   |
| KDE neon      | 10        | 2.89%   |
| Debian        | 9         | 2.6%    |
| ROSA          | 8         | 2.31%   |
| Manjaro       | 8         | 2.31%   |
| Kali          | 7         | 2.02%   |
| Arch          | 7         | 2.02%   |
| Xubuntu       | 6         | 1.73%   |
| Parrot        | 6         | 1.73%   |
| ArcoLinux     | 6         | 1.73%   |
| MX            | 4         | 1.16%   |
| Kubuntu       | 3         | 0.87%   |
| BlackPanther  | 3         | 0.87%   |
| Ubuntu MATE   | 2         | 0.58%   |
| Peppermint    | 2         | 0.58%   |
| openSUSE      | 2         | 0.58%   |
| Gentoo        | 2         | 0.58%   |
| Xero          | 1         | 0.29%   |
| UbuntuDDE     | 1         | 0.29%   |
| Ubuntu Unity  | 1         | 0.29%   |
| Ubuntu Budgie | 1         | 0.29%   |
| Skygate       | 1         | 0.29%   |
| Q4OS          | 1         | 0.29%   |
| Pear OS       | 1         | 0.29%   |
| Lubuntu       | 1         | 0.29%   |
| Garuda Linux  | 1         | 0.29%   |
| Endless       | 1         | 0.29%   |
| EndeavourOS   | 1         | 0.29%   |
| Elementary    | 1         | 0.29%   |
| Deepin        | 1         | 0.29%   |
| Clear Linux   | 1         | 0.29%   |
| ChimeraOS     | 1         | 0.29%   |
| CentOS        | 1         | 0.29%   |
| Athena        | 1         | 0.29%   |
| Artix         | 1         | 0.29%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 17        | 4.49%   |
| 5.10.14-desktop-1omv4002 | 15        | 3.96%   |
| 6.6.2-desktop-1omv2390   | 7         | 1.85%   |
| 6.2.6-desktop-1omv2390   | 6         | 1.58%   |
| 6.5.0-15-generic         | 5         | 1.32%   |
| 5.4.0-42-generic         | 5         | 1.32%   |
| 5.15.0-47-generic        | 5         | 1.32%   |
| 6.1.1-desktop-1omv2290   | 4         | 1.06%   |
| 5.8.0-50-generic         | 4         | 1.06%   |
| 5.4.0-72-generic         | 4         | 1.06%   |
| 5.4.0-54-generic         | 4         | 1.06%   |
| 5.4.0-29-generic         | 4         | 1.06%   |
| 5.0.0-37-generic         | 4         | 1.06%   |
| 6.5.5-desktop-1omv2390   | 3         | 0.79%   |
| 6.5.0-17-generic         | 3         | 0.79%   |
| 6.4.11-desktop-1omv2390  | 3         | 0.79%   |
| 6.2.0-33-generic         | 3         | 0.79%   |
| 6.1.0-13-amd64           | 3         | 0.79%   |
| 6.0.12-100.fc35.x86_64   | 3         | 0.79%   |
| 5.4.0-65-generic         | 3         | 0.79%   |
| 5.4.0-56-generic         | 3         | 0.79%   |
| 5.4.0-52-generic         | 3         | 0.79%   |
| 5.3.0-46-generic         | 3         | 0.79%   |
| 5.15.0-86-generic        | 3         | 0.79%   |
| 5.15.0-58-generic        | 3         | 0.79%   |
| 5.15.0-56-generic        | 3         | 0.79%   |
| 5.13.0-30-generic        | 3         | 0.79%   |
| 5.11.0-38-generic        | 3         | 0.79%   |
| 5.11.0-27-generic        | 3         | 0.79%   |
| 6.5.0-desktop-1omv2390   | 2         | 0.53%   |
| 6.4.8-desktop-2omv2390   | 2         | 0.53%   |
| 6.2.0-36-generic         | 2         | 0.53%   |
| 6.0.7-301.fc37.x86_64    | 2         | 0.53%   |
| 5.8.0-44-generic         | 2         | 0.53%   |
| 5.4.0-88-generic         | 2         | 0.53%   |
| 5.4.0-81-generic         | 2         | 0.53%   |
| 5.4.0-80-generic         | 2         | 0.53%   |
| 5.4.0-7625-generic       | 2         | 0.53%   |
| 5.4.0-48-generic         | 2         | 0.53%   |
| 5.4.0-33-generic         | 2         | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 50        | 13.81%  |
| 5.15.0  | 32        | 8.84%   |
| 5.16.7  | 17        | 4.7%    |
| 5.11.0  | 16        | 4.42%   |
| 5.10.14 | 15        | 4.14%   |
| 6.5.0   | 14        | 3.87%   |
| 5.8.0   | 14        | 3.87%   |
| 4.15.0  | 13        | 3.59%   |
| 5.3.0   | 10        | 2.76%   |
| 5.0.0   | 10        | 2.76%   |
| 5.13.0  | 9         | 2.49%   |
| 6.2.0   | 8         | 2.21%   |
| 6.1.0   | 8         | 2.21%   |
| 5.10.0  | 8         | 2.21%   |
| 6.6.2   | 7         | 1.93%   |
| 6.2.6   | 7         | 1.93%   |
| 5.19.0  | 5         | 1.38%   |
| 6.1.1   | 4         | 1.1%    |
| 6.5.5   | 3         | 0.83%   |
| 6.4.11  | 3         | 0.83%   |
| 6.0.12  | 3         | 0.83%   |
| 4.18.16 | 3         | 0.83%   |
| 6.8.7   | 2         | 0.55%   |
| 6.6.8   | 2         | 0.55%   |
| 6.5.6   | 2         | 0.55%   |
| 6.4.8   | 2         | 0.55%   |
| 6.2.8   | 2         | 0.55%   |
| 6.1.12  | 2         | 0.55%   |
| 6.0.7   | 2         | 0.55%   |
| 5.15.7  | 2         | 0.55%   |
| 5.14.0  | 2         | 0.55%   |
| 4.9.60  | 2         | 0.55%   |
| 4.4.0   | 2         | 0.55%   |
| 4.19.0  | 2         | 0.55%   |
| 6.8.1   | 1         | 0.28%   |
| 6.7.9   | 1         | 0.28%   |
| 6.7.5   | 1         | 0.28%   |
| 6.7.4   | 1         | 0.28%   |
| 6.6.9   | 1         | 0.28%   |
| 6.6.6   | 1         | 0.28%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 53        | 14.68%  |
| 5.15    | 42        | 11.63%  |
| 5.10    | 28        | 7.76%   |
| 6.5     | 21        | 5.82%   |
| 6.1     | 21        | 5.82%   |
| 6.2     | 20        | 5.54%   |
| 5.16    | 19        | 5.26%   |
| 5.11    | 18        | 4.99%   |
| 5.8     | 15        | 4.16%   |
| 6.6     | 13        | 3.6%    |
| 4.15    | 13        | 3.6%    |
| 5.3     | 10        | 2.77%   |
| 5.19    | 10        | 2.77%   |
| 5.13    | 10        | 2.77%   |
| 5.0     | 10        | 2.77%   |
| 6.4     | 9         | 2.49%   |
| 6.0     | 7         | 1.94%   |
| 5.14    | 5         | 1.39%   |
| 4.9     | 4         | 1.11%   |
| 4.19    | 4         | 1.11%   |
| 4.18    | 4         | 1.11%   |
| 6.8     | 3         | 0.83%   |
| 6.7     | 3         | 0.83%   |
| 5.17    | 3         | 0.83%   |
| 5.12    | 3         | 0.83%   |
| 6.3     | 2         | 0.55%   |
| 5.7     | 2         | 0.55%   |
| 5.6     | 2         | 0.55%   |
| 5.18    | 2         | 0.55%   |
| 4.4     | 2         | 0.55%   |
| 5.9     | 1         | 0.28%   |
| 4.1     | 1         | 0.28%   |
| 3.10    | 1         | 0.28%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 310       | 97.18%  |
| i686   | 8         | 2.51%   |
| armv7l | 1         | 0.31%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 151       | 44.67%  |
| KDE5             | 82        | 24.26%  |
| Unknown          | 25        | 7.4%    |
| XFCE             | 23        | 6.8%    |
| X-Cinnamon       | 13        | 3.85%   |
| MATE             | 9         | 2.66%   |
| Cinnamon         | 8         | 2.37%   |
| KDE4             | 5         | 1.48%   |
| KDE              | 5         | 1.48%   |
| LXQt             | 3         | 0.89%   |
| i3               | 2         | 0.59%   |
| Unity            | 1         | 0.3%    |
| Trinity          | 1         | 0.3%    |
| Peppermint       | 1         | 0.3%    |
| Pantheon         | 1         | 0.3%    |
| LXDE             | 1         | 0.3%    |
| lightdm-xsession | 1         | 0.3%    |
| icewm            | 1         | 0.3%    |
| GNOME Flashback  | 1         | 0.3%    |
| fvwm             | 1         | 0.3%    |
| Deepin           | 1         | 0.3%    |
| DDE              | 1         | 0.3%    |
| Budgie           | 1         | 0.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 232       | 70.52%  |
| Wayland | 83        | 25.23%  |
| Unknown | 12        | 3.65%   |
| Tty     | 2         | 0.61%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 150       | 44.51%  |
| SDDM    | 75        | 22.26%  |
| GDM3    | 34        | 10.09%  |
| LightDM | 33        | 9.79%   |
| GDM     | 30        | 8.9%    |
| TDM     | 8         | 2.37%   |
| KDM     | 5         | 1.48%   |
| SLIMSKI | 1         | 0.3%    |
| SLiM    | 1         | 0.3%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 139       | 41.74%  |
| fr_FR       | 129       | 38.74%  |
| Unknown     | 27        | 8.11%   |
| en_GB       | 13        | 3.9%    |
| C           | 7         | 2.1%    |
| ar_DZ       | 7         | 2.1%    |
| ar_EG       | 3         | 0.9%    |
| fr_DZ       | 2         | 0.6%    |
| fr_BE       | 2         | 0.6%    |
| es_ES       | 2         | 0.6%    |
| en-US-UTF-8 | 1         | 0.3%    |
| ar_AE       | 1         | 0.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 219       | 66.77%  |
| EFI  | 109       | 33.23%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 239       | 71.77%  |
| Overlay | 43        | 12.91%  |
| Btrfs   | 29        | 8.71%   |
| Unknown | 9         | 2.7%    |
| Tmpfs   | 6         | 1.8%    |
| Xfs     | 3         | 0.9%    |
| Ext2    | 3         | 0.9%    |
| Ext3    | 1         | 0.3%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 164       | 49.7%   |
| GPT     | 92        | 27.88%  |
| MBR     | 74        | 22.42%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 256       | 77.58%  |
| Yes       | 74        | 22.42%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 176       | 53.5%   |
| Yes       | 153       | 46.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 52        | 16.3%   |
| Hewlett-Packard     | 46        | 14.42%  |
| ASUSTek Computer    | 45        | 14.11%  |
| Lenovo              | 35        | 10.97%  |
| MSI                 | 20        | 6.27%   |
| Gigabyte Technology | 20        | 6.27%   |
| Acer                | 18        | 5.64%   |
| Toshiba             | 11        | 3.45%   |
| Unknown             | 10        | 3.13%   |
| Foxconn             | 8         | 2.51%   |
| ECS                 | 8         | 2.51%   |
| Sony                | 7         | 2.19%   |
| Apple               | 6         | 1.88%   |
| Intel               | 5         | 1.57%   |
| Samsung Electronics | 3         | 0.94%   |
| Packard Bell        | 3         | 0.94%   |
| Fujitsu             | 3         | 0.94%   |
| Biostar             | 3         | 0.94%   |
| ASRock              | 3         | 0.94%   |
| LORD ELECTRONICS    | 2         | 0.63%   |
| Wistron             | 1         | 0.31%   |
| WeiBu               | 1         | 0.31%   |
| UNOWHY              | 1         | 0.31%   |
| sunxi               | 1         | 0.31%   |
| Pegatron            | 1         | 0.31%   |
| Notebook            | 1         | 0.31%   |
| Microsoft           | 1         | 0.31%   |
| LDLC                | 1         | 0.31%   |
| HUAWEI              | 1         | 0.31%   |
| eMachines           | 1         | 0.31%   |
| AMI                 | 1         | 0.31%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| ASUS UL80VT                                       | 14        | 4.39%   |
| Unknown                                           | 10        | 3.13%   |
| Dell Inspiron N5110                               | 5         | 1.57%   |
| Toshiba Satellite C55-B                           | 4         | 1.25%   |
| HP Pavilion 15                                    | 4         | 1.25%   |
| Dell Inspiron 15-3567                             | 4         | 1.25%   |
| Lenovo IdeaPad 300-15ISK 80Q7                     | 3         | 0.94%   |
| Lenovo G560 20042                                 | 3         | 0.94%   |
| Intel H55                                         | 3         | 0.94%   |
| HP Notebook                                       | 3         | 0.94%   |
| HP 280 G1 MT                                      | 3         | 0.94%   |
| Gigabyte H61M-S2PV                                | 3         | 0.94%   |
| Foxconn H61MXL/H61MXL-K                           | 3         | 0.94%   |
| ECS G41T-M7                                       | 3         | 0.94%   |
| Dell Latitude 7480                                | 3         | 0.94%   |
| Dell Inspiron 3542                                | 3         | 0.94%   |
| MSI MS-7788                                       | 2         | 0.63%   |
| MSI MS-7758                                       | 2         | 0.63%   |
| MSI MS-7636                                       | 2         | 0.63%   |
| MSI MS-7592                                       | 2         | 0.63%   |
| LORD ELECTRONICS LORD G4x 775 ICH7 8712 As Design | 2         | 0.63%   |
| Lenovo G50-30 80G0                                | 2         | 0.63%   |
| Lenovo B50-70 20384                               | 2         | 0.63%   |
| Intel H61                                         | 2         | 0.63%   |
| HP ProBook 4540s                                  | 2         | 0.63%   |
| HP 15                                             | 2         | 0.63%   |
| Gigabyte G41MT-S2PT                               | 2         | 0.63%   |
| Gigabyte B85M-DS3H-A                              | 2         | 0.63%   |
| ECS H61H2-MV                                      | 2         | 0.63%   |
| Dell Latitude E7440                               | 2         | 0.63%   |
| Dell Latitude E5430 vPro                          | 2         | 0.63%   |
| Dell Latitude 5480                                | 2         | 0.63%   |
| Biostar P4M89-M7B                                 | 2         | 0.63%   |
| ASUS H61M-K                                       | 2         | 0.63%   |
| ASUS All Series                                   | 2         | 0.63%   |
| Acer Aspire 5738                                  | 2         | 0.63%   |
| Wistron ProLiant ML110 G5                         | 1         | 0.31%   |
| WeiBu SIMM INT G-41D3 G1.0L                       | 1         | 0.31%   |
| UNOWHY Y13G012S4EI                                | 1         | 0.31%   |
| Toshiba Satellite Pro A100                        | 1         | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 19        | 5.96%   |
| Dell Inspiron         | 19        | 5.96%   |
| Acer Aspire           | 15        | 4.7%    |
| ASUS UL80VT           | 14        | 4.39%   |
| Lenovo ThinkPad       | 11        | 3.45%   |
| Unknown               | 10        | 3.13%   |
| Toshiba Satellite     | 9         | 2.82%   |
| HP ProBook            | 9         | 2.82%   |
| HP Pavilion           | 8         | 2.51%   |
| HP EliteBook          | 7         | 2.19%   |
| Lenovo IdeaPad        | 6         | 1.88%   |
| Dell Vostro           | 5         | 1.57%   |
| Lenovo G560           | 3         | 0.94%   |
| Intel H55             | 3         | 0.94%   |
| HP Notebook           | 3         | 0.94%   |
| HP Laptop             | 3         | 0.94%   |
| HP 280                | 3         | 0.94%   |
| Gigabyte H61M-S2PV    | 3         | 0.94%   |
| Fujitsu LIFEBOOK      | 3         | 0.94%   |
| Foxconn H61MXL        | 3         | 0.94%   |
| ECS G41T-M7           | 3         | 0.94%   |
| Dell Precision        | 3         | 0.94%   |
| Dell OptiPlex         | 3         | 0.94%   |
| ASUS TUF              | 3         | 0.94%   |
| ASUS PRIME            | 3         | 0.94%   |
| ASUS ASUS             | 3         | 0.94%   |
| Toshiba PORTEGE       | 2         | 0.63%   |
| Packard Bell EasyNote | 2         | 0.63%   |
| MSI MS-7788           | 2         | 0.63%   |
| MSI MS-7758           | 2         | 0.63%   |
| MSI MS-7636           | 2         | 0.63%   |
| MSI MS-7592           | 2         | 0.63%   |
| LORD ELECTRONICS LORD | 2         | 0.63%   |
| Lenovo Yoga           | 2         | 0.63%   |
| Lenovo G580           | 2         | 0.63%   |
| Lenovo G50-30         | 2         | 0.63%   |
| Lenovo B50-70         | 2         | 0.63%   |
| Intel H61             | 2         | 0.63%   |
| HP ProDesk            | 2         | 0.63%   |
| HP Compaq             | 2         | 0.63%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 46        | 14.42%  |
| 2014    | 36        | 11.29%  |
| 2013    | 36        | 11.29%  |
| 2011    | 29        | 9.09%   |
| 2009    | 28        | 8.78%   |
| 2017    | 22        | 6.9%    |
| 2016    | 22        | 6.9%    |
| 2015    | 22        | 6.9%    |
| 2010    | 18        | 5.64%   |
| 2018    | 14        | 4.39%   |
| 2019    | 9         | 2.82%   |
| 2020    | 8         | 2.51%   |
| 2021    | 7         | 2.19%   |
| 2007    | 7         | 2.19%   |
| 2008    | 6         | 1.88%   |
| 2022    | 4         | 1.25%   |
| 2023    | 2         | 0.63%   |
| 2006    | 2         | 0.63%   |
| Unknown | 1         | 0.31%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 201       | 63.01%  |
| Desktop        | 110       | 34.48%  |
| Tablet         | 3         | 0.94%   |
| All in one     | 3         | 0.94%   |
| System on chip | 1         | 0.31%   |
| Convertible    | 1         | 0.31%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 310       | 96.88%  |
| Enabled  | 10        | 3.13%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 319       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 108       | 33.03%  |
| 4.01-8.0    | 88        | 26.91%  |
| 8.01-16.0   | 65        | 19.88%  |
| 16.01-24.0  | 23        | 7.03%   |
| 1.01-2.0    | 22        | 6.73%   |
| 2.01-3.0    | 8         | 2.45%   |
| 32.01-64.0  | 7         | 2.14%   |
| 0.51-1.0    | 4         | 1.22%   |
| 64.01-256.0 | 2         | 0.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 153       | 43.1%   |
| 2.01-3.0   | 98        | 27.61%  |
| 3.01-4.0   | 47        | 13.24%  |
| 4.01-8.0   | 27        | 7.61%   |
| 0.51-1.0   | 20        | 5.63%   |
| 8.01-16.0  | 6         | 1.69%   |
| 0.01-0.5   | 3         | 0.85%   |
| 32.01-64.0 | 1         | 0.28%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 217       | 66.56%  |
| 2      | 86        | 26.38%  |
| 3      | 13        | 3.99%   |
| 4      | 5         | 1.53%   |
| 0      | 3         | 0.92%   |
| 7      | 1         | 0.31%   |
| 5      | 1         | 0.31%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 184       | 56.62%  |
| No        | 141       | 43.38%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 294       | 92.16%  |
| No        | 25        | 7.84%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 258       | 79.88%  |
| No        | 65        | 20.12%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 173       | 53.23%  |
| Yes       | 152       | 46.77%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Algeria | 319       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Algiers            | 52        | 14.25%  |
| Oran               | 19        | 5.21%   |
| Belcourt           | 19        | 5.21%   |
| Sétif             | 14        | 3.84%   |
| Annaba             | 13        | 3.56%   |
| Tlemcen            | 11        | 3.01%   |
| Constantine        | 11        | 3.01%   |
| Béjaïa           | 8         | 2.19%   |
| Tizi Ouzou         | 7         | 1.92%   |
| Skikda             | 7         | 1.92%   |
| Jijelli            | 7         | 1.92%   |
| Blida              | 7         | 1.92%   |
| Batna City         | 7         | 1.92%   |
| Relizane           | 6         | 1.64%   |
| Tipasa             | 5         | 1.37%   |
| Ouargla            | 5         | 1.37%   |
| Laghouat           | 5         | 1.37%   |
| Cheraga            | 5         | 1.37%   |
| Bordj Bou Arreridj | 5         | 1.37%   |
| Biskra             | 5         | 1.37%   |
| Bab Ezzouar        | 5         | 1.37%   |
| ash-Shalif         | 5         | 1.37%   |
| Mostaganem         | 4         | 1.1%    |
| Birkhadem          | 4         | 1.1%    |
| Ben ’Aknoûn     | 4         | 1.1%    |
| Béchar            | 4         | 1.1%    |
| Tolga              | 3         | 0.82%   |
| Sidi Bel Abbes     | 3         | 0.82%   |
| Sidi Akkacha       | 3         | 0.82%   |
| Saoula             | 3         | 0.82%   |
| Kouba              | 3         | 0.82%   |
| Bordj el Kiffan    | 3         | 0.82%   |
| Saida              | 2         | 0.55%   |
| Ouenza             | 2         | 0.55%   |
| Khenchela          | 2         | 0.55%   |
| El Aouinet         | 2         | 0.55%   |
| Draria             | 2         | 0.55%   |
| Djelfa             | 2         | 0.55%   |
| Debila             | 2         | 0.55%   |
| Boumerdes          | 2         | 0.55%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 80        | 100    | 18.96%  |
| WDC                         | 65        | 89     | 15.4%   |
| Toshiba                     | 46        | 62     | 10.9%   |
| Hitachi                     | 36        | 47     | 8.53%   |
| Samsung Electronics         | 31        | 35     | 7.35%   |
| A-DATA Technology           | 21        | 26     | 4.98%   |
| HGST                        | 19        | 26     | 4.5%    |
| Unknown                     | 11        | 17     | 2.61%   |
| Team                        | 9         | 10     | 2.13%   |
| SanDisk                     | 9         | 10     | 2.13%   |
| Lexar                       | 7         | 11     | 1.66%   |
| Intel                       | 7         | 8      | 1.66%   |
| Maxtor                      | 6         | 8      | 1.42%   |
| SK hynix                    | 5         | 7      | 1.18%   |
| LITEON                      | 5         | 9      | 1.18%   |
| China                       | 5         | 7      | 1.18%   |
| Fujitsu                     | 4         | 5      | 0.95%   |
| Realtek Semiconductor       | 3         | 3      | 0.71%   |
| Micron Technology           | 3         | 4      | 0.71%   |
| Kingston                    | 3         | 3      | 0.71%   |
| ZTE                         | 2         | 2      | 0.47%   |
| XrayDisk                    | 2         | 3      | 0.47%   |
| XPG                         | 2         | 2      | 0.47%   |
| tecmiyo                     | 2         | 2      | 0.47%   |
| Silicon Motion              | 2         | 2      | 0.47%   |
| KingSpec                    | 2         | 2      | 0.47%   |
| KESU                        | 2         | 2      | 0.47%   |
| HS-SSD-E100                 | 2         | 2      | 0.47%   |
| Crucial                     | 2         | 2      | 0.47%   |
| Apple                       | 2         | 2      | 0.47%   |
| ADATA Technology            | 2         | 2      | 0.47%   |
| WD MediaMax                 | 1         | 1      | 0.24%   |
| TwinMOS                     | 1         | 1      | 0.24%   |
| T-FORCE                     | 1         | 1      | 0.24%   |
| STAR                        | 1         | 1      | 0.24%   |
| Smart                       | 1         | 1      | 0.24%   |
| PNY                         | 1         | 1      | 0.24%   |
| Micron/Crucial Technology   | 1         | 1      | 0.24%   |
| MDT                         | 1         | 1      | 0.24%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seagate ST9500325AS 500GB          | 17        | 3.83%   |
| Toshiba MQ01ABF050 500GB           | 9         | 2.03%   |
| Toshiba MQ01ABD100 1TB             | 6         | 1.35%   |
| Seagate ST500LT012-1DG142 500GB    | 6         | 1.35%   |
| Toshiba DT01ACA100 1TB             | 5         | 1.13%   |
| Toshiba DT01ACA050 500GB           | 5         | 1.13%   |
| HGST HTS545050A7E680 500GB         | 5         | 1.13%   |
| WDC WD5000LPCX-24C6HT0 500GB       | 4         | 0.9%    |
| Seagate ST500LT012-9WS142 500GB    | 4         | 0.9%    |
| Seagate ST1000LM035-1RK172 1TB     | 4         | 0.9%    |
| Seagate Expansion 2TB              | 4         | 0.9%    |
| Hitachi HTS545050A7E380 500GB      | 4         | 0.9%    |
| Hitachi HDS721616PLA380 160GB      | 4         | 0.9%    |
| HGST HTS545050A7E380 500GB         | 4         | 0.9%    |
| A-DATA SU650 120GB SSD             | 4         | 0.9%    |
| A-DATA SU630 240GB SSD             | 4         | 0.9%    |
| WDC WD5000AAKX-001CA0 500GB        | 3         | 0.68%   |
| WDC WD10EZEX-08WN4A0 1TB           | 3         | 0.68%   |
| WDC WD10EZEX-00WN4A0 1TB           | 3         | 0.68%   |
| Unknown MMC Card  64GB             | 3         | 0.68%   |
| Toshiba MQ01ABD050V 500GB          | 3         | 0.68%   |
| Team T253256GB SSD                 | 3         | 0.68%   |
| Seagate ST500VT000-1DK142 500GB    | 3         | 0.68%   |
| Seagate ST500LM021-1KJ152 500GB    | 3         | 0.68%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 0.68%   |
| Lexar 512GB SSD                    | 3         | 0.68%   |
| Lexar 128GB SSD                    | 3         | 0.68%   |
| Intel SSDPEKNU512GZ 512GB          | 3         | 0.68%   |
| Hitachi HTS545050B9A300 500GB      | 3         | 0.68%   |
| HGST HTS725050A7E630 500GB         | 3         | 0.68%   |
| HGST HTS541010A9E680 1TB           | 3         | 0.68%   |
| A-DATA LEGEND 710 512GB            | 3         | 0.68%   |
| ZTE MMC Storage 942MB              | 2         | 0.45%   |
| XPG SX950U 240GB                   | 2         | 0.45%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 2         | 0.45%   |
| WDC WD5000AVVS-63M8B0 500GB        | 2         | 0.45%   |
| WDC WD1600AVJS-63WNA0 160GB        | 2         | 0.45%   |
| Unknown SD/MMC 2GB                 | 2         | 0.45%   |
| Unknown MMC Card  32GB             | 2         | 0.45%   |
| Unknown M.S./M.S.Pro/HG 16GB       | 2         | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 80        | 100    | 29.63%  |
| WDC                 | 61        | 81     | 22.59%  |
| Toshiba             | 45        | 59     | 16.67%  |
| Hitachi             | 36        | 47     | 13.33%  |
| HGST                | 19        | 26     | 7.04%   |
| Samsung Electronics | 12        | 13     | 4.44%   |
| Maxtor              | 6         | 8      | 2.22%   |
| Fujitsu             | 4         | 5      | 1.48%   |
| WD MediaMax         | 1         | 1      | 0.37%   |
| Magnetic Data       | 1         | 1      | 0.37%   |
| KESU                | 1         | 1      | 0.37%   |
| JMicron Technology  | 1         | 1      | 0.37%   |
| Initio              | 1         | 1      | 0.37%   |
| Hewlett-Packard     | 1         | 1      | 0.37%   |
| Apple               | 1         | 1      | 0.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| A-DATA Technology   | 15        | 18     | 16.85%  |
| Team                | 7         | 8      | 7.87%   |
| Samsung Electronics | 7         | 7      | 7.87%   |
| SanDisk             | 6         | 6      | 6.74%   |
| Lexar               | 6         | 10     | 6.74%   |
| WDC                 | 5         | 7      | 5.62%   |
| LITEON              | 5         | 9      | 5.62%   |
| China               | 5         | 7      | 5.62%   |
| SK hynix            | 3         | 5      | 3.37%   |
| Intel               | 3         | 4      | 3.37%   |
| XrayDisk            | 2         | 3      | 2.25%   |
| XPG                 | 2         | 2      | 2.25%   |
| tecmiyo             | 2         | 2      | 2.25%   |
| Kingston            | 2         | 2      | 2.25%   |
| KingSpec            | 2         | 2      | 2.25%   |
| Crucial             | 2         | 2      | 2.25%   |
| TwinMOS             | 1         | 1      | 1.12%   |
| T-FORCE             | 1         | 1      | 1.12%   |
| STAR                | 1         | 1      | 1.12%   |
| PNY                 | 1         | 1      | 1.12%   |
| Micron Technology   | 1         | 1      | 1.12%   |
| MAX                 | 1         | 1      | 1.12%   |
| Londisk             | 1         | 1      | 1.12%   |
| LITEONIT            | 1         | 1      | 1.12%   |
| Lenovo              | 1         | 1      | 1.12%   |
| KODAK               | 1         | 1      | 1.12%   |
| HS-SSD-E100         | 1         | 1      | 1.12%   |
| HS-SSD-C100         | 1         | 1      | 1.12%   |
| Corsair             | 1         | 1      | 1.12%   |
| Apple               | 1         | 1      | 1.12%   |
| Unknown             | 1         | 1      | 1.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 240       | 346    | 62.99%  |
| SSD     | 83        | 109    | 21.78%  |
| NVMe    | 36        | 52     | 9.45%   |
| MMC     | 11        | 13     | 2.89%   |
| Unknown | 11        | 16     | 2.89%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 283       | 450    | 82.03%  |
| NVMe | 36        | 52     | 10.43%  |
| SAS  | 15        | 21     | 4.35%   |
| MMC  | 11        | 13     | 3.19%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 230       | 340    | 71.43%  |
| 0.51-1.0   | 76        | 97     | 23.6%   |
| 1.01-2.0   | 16        | 18     | 4.97%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 82        | 23.77%  |
| 101-250        | 70        | 20.29%  |
| 51-100         | 52        | 15.07%  |
| 501-1000       | 40        | 11.59%  |
| 21-50          | 39        | 11.3%   |
| 1-20           | 39        | 11.3%   |
| 1001-2000      | 15        | 4.35%   |
| More than 3000 | 3         | 0.87%   |
| Unknown        | 3         | 0.87%   |
| 2001-3000      | 2         | 0.58%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 159       | 45.3%   |
| 21-50     | 77        | 21.94%  |
| 101-250   | 42        | 11.97%  |
| 51-100    | 34        | 9.69%   |
| 251-500   | 21        | 5.98%   |
| 501-1000  | 9         | 2.56%   |
| 1001-2000 | 5         | 1.42%   |
| Unknown   | 3         | 0.85%   |
| 2001-3000 | 1         | 0.28%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                       | Computers | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                   | 15        | 15     | 20%     |
| Seagate ST500LT012-9WS142 500GB             | 3         | 3      | 4%      |
| Toshiba MQ01ABD100 1TB                      | 2         | 2      | 2.67%   |
| Seagate ST500LM021-1KJ152 500GB             | 2         | 2      | 2.67%   |
| Seagate ST1000DM010-2EP102 1TB              | 2         | 3      | 2.67%   |
| Samsung Electronics HD502HI 500GB           | 2         | 2      | 2.67%   |
| HGST HTS725050A7E630 500GB                  | 2         | 5      | 2.67%   |
| WDC WD5000LUCT-62C26Y0 500GB                | 1         | 1      | 1.33%   |
| WDC WD5000BEVT-24A0RT0 500GB                | 1         | 1      | 1.33%   |
| WDC WD5000BEVT-22A0RT0 500GB                | 1         | 1      | 1.33%   |
| WDC WD5000AVVS-63M8B0 500GB                 | 1         | 1      | 1.33%   |
| WDC WD5000AVCS-632DY1 500GB                 | 1         | 1      | 1.33%   |
| WDC WD5000AAKX-00ERMA0 500GB                | 1         | 1      | 1.33%   |
| WDC WD400EB-00CPF0 40GB                     | 1         | 1      | 1.33%   |
| WDC WD3200BPVT-22JJ5T0 320GB                | 1         | 1      | 1.33%   |
| WDC WD3200AVJS-63B6A0 320GB                 | 1         | 1      | 1.33%   |
| WDC WD1600AAJS-08WAA0 160GB                 | 1         | 1      | 1.33%   |
| WDC WD1001FALS-403AA0 1TB                   | 1         | 1      | 1.33%   |
| WD MediaMax WL120GBSATA                     | 1         | 1      | 1.33%   |
| Toshiba MQ01ABF050 500GB                    | 1         | 1      | 1.33%   |
| Toshiba DT01ACA050 500GB                    | 1         | 1      | 1.33%   |
| tecmiyo SATA SSD 128GB                      | 1         | 1      | 1.33%   |
| Seagate ST9320325AS 320GB                   | 1         | 1      | 1.33%   |
| Seagate ST9250410AS 250GB                   | 1         | 1      | 1.33%   |
| Seagate ST500LT012-1DG142 500GB             | 1         | 1      | 1.33%   |
| Seagate ST500DM002-1BD142 500GB             | 1         | 2      | 1.33%   |
| Seagate ST3500413AS 500GB                   | 1         | 1      | 1.33%   |
| Seagate ST3250310AS 250GB                   | 1         | 1      | 1.33%   |
| Seagate ST1000LM048-2E7172 1TB              | 1         | 1      | 1.33%   |
| Seagate ST1000LM035-1RK172 1TB              | 1         | 1      | 1.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB          | 1         | 1      | 1.33%   |
| Samsung Electronics SSD PM810 2.5 7mm 128GB | 1         | 1      | 1.33%   |
| Samsung Electronics HM320HJ 320GB           | 1         | 1      | 1.33%   |
| Samsung Electronics HD256GJ 250GB           | 1         | 1      | 1.33%   |
| Samsung Electronics HD160JJ 160GB           | 1         | 1      | 1.33%   |
| Samsung Electronics HD103SI 1TB             | 1         | 1      | 1.33%   |
| Maxtor STM3320613AS 320GB                   | 1         | 1      | 1.33%   |
| Maxtor STM3160215AS 160GB                   | 1         | 1      | 1.33%   |
| Maxtor 6L300S0 304GB                        | 1         | 1      | 1.33%   |
| Maxtor 32049H2 20GB                         | 1         | 1      | 1.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 31        | 33     | 41.89%  |
| WDC                 | 10        | 11     | 13.51%  |
| Samsung Electronics | 7         | 7      | 9.46%   |
| Hitachi             | 7         | 8      | 9.46%   |
| Toshiba             | 4         | 4      | 5.41%   |
| Maxtor              | 4         | 4      | 5.41%   |
| HGST                | 3         | 6      | 4.05%   |
| A-DATA Technology   | 2         | 2      | 2.7%    |
| WD MediaMax         | 1         | 1      | 1.35%   |
| tecmiyo             | 1         | 1      | 1.35%   |
| Magnetic Data       | 1         | 1      | 1.35%   |
| LITEONIT            | 1         | 1      | 1.35%   |
| KingSpec            | 1         | 1      | 1.35%   |
| Fujitsu             | 1         | 1      | 1.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 31        | 33     | 45.59%  |
| WDC                 | 10        | 11     | 14.71%  |
| Hitachi             | 7         | 8      | 10.29%  |
| Samsung Electronics | 6         | 6      | 8.82%   |
| Toshiba             | 4         | 4      | 5.88%   |
| Maxtor              | 4         | 4      | 5.88%   |
| HGST                | 3         | 6      | 4.41%   |
| WD MediaMax         | 1         | 1      | 1.47%   |
| Magnetic Data       | 1         | 1      | 1.47%   |
| Fujitsu             | 1         | 1      | 1.47%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 65        | 75     | 91.55%  |
| SSD  | 5         | 5      | 7.04%   |
| NVMe | 1         | 1      | 1.41%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Toshiba DT01ACA050 500GB | 1         | 1      | 50%     |
| Seagate ST31000528AS 1TB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 188       | 319    | 53.87%  |
| Works    | 90        | 134    | 25.79%  |
| Malfunc  | 69        | 81     | 19.77%  |
| Failed   | 2         | 2      | 0.57%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 275       | 79.25%  |
| AMD                          | 20        | 5.76%   |
| Samsung Electronics          | 12        | 3.46%   |
| Realtek Semiconductor        | 5         | 1.44%   |
| Nvidia                       | 5         | 1.44%   |
| VIA Technologies             | 4         | 1.15%   |
| ASMedia Technology           | 4         | 1.15%   |
| ADATA Technology             | 4         | 1.15%   |
| Silicon Motion               | 3         | 0.86%   |
| Micron Technology            | 2         | 0.58%   |
| MAXIO Technology (Hangzhou)  | 2         | 0.58%   |
| Kingston Technology Company  | 2         | 0.58%   |
| JMicron Technology           | 2         | 0.58%   |
| Toshiba America Info Systems | 1         | 0.29%   |
| SK hynix                     | 1         | 0.29%   |
| SanDisk                      | 1         | 0.29%   |
| Micron/Crucial Technology    | 1         | 0.29%   |
| Marvell Technology Group     | 1         | 0.29%   |
| KIOXIA                       | 1         | 0.29%   |
| Hosin Global Electronics     | 1         | 0.29%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 28        | 6.71%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 28        | 6.71%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 23        | 5.52%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 23        | 5.52%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 20        | 4.8%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 20        | 4.8%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 17        | 4.08%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 16        | 3.84%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 16        | 3.84%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 15        | 3.6%    |
| AMD FCH SATA Controller [AHCI mode]                                                     | 15        | 3.6%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 11        | 2.64%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 11        | 2.64%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 9         | 2.16%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 9         | 2.16%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7         | 1.68%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 7         | 1.68%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 7         | 1.68%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6         | 1.44%   |
| Intel SATA Controller [RAID mode]                                                       | 5         | 1.2%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 5         | 1.2%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4         | 0.96%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                       | 4         | 0.96%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4         | 0.96%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4         | 0.96%   |
| ADATA XPG GAMMIXS1 1L, XPG GAMMIX S5, LEGEND 710 / 740, SWORDFISH NVMe SSD (DRAM-less)  | 4         | 0.96%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 3         | 0.72%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 3         | 0.72%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3         | 0.72%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 3         | 0.72%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3         | 0.72%   |
| Intel SSD 670p Series [Keystone Harbor]                                                 | 3         | 0.72%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 0.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 3         | 0.72%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 3         | 0.72%   |
| VIA Serial ATA Controller                                                               | 2         | 0.48%   |
| Nvidia MCP79 AHCI Controller                                                            | 2         | 0.48%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 2         | 0.48%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 2         | 0.48%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2         | 0.48%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 220       | 62.86%  |
| IDE  | 69        | 19.71%  |
| NVMe | 36        | 10.29%  |
| RAID | 24        | 6.86%   |
| SAS  | 1         | 0.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 294       | 92.16%  |
| AMD    | 24        | 7.52%   |
| ARM    | 1         | 0.31%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Genuine CPU U7300 @ 1.30GHz           | 14        | 4.36%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 8         | 2.49%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 6         | 1.87%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 6         | 1.87%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 6         | 1.87%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 6         | 1.87%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 5         | 1.56%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 5         | 1.56%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 5         | 1.56%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 4         | 1.25%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 4         | 1.25%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 4         | 1.25%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 4         | 1.25%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 4         | 1.25%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 4         | 1.25%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 4         | 1.25%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 3         | 0.93%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 3         | 0.93%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 3         | 0.93%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 3         | 0.93%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 3         | 0.93%   |
| Intel Core i7-2760QM CPU @ 2.40GHz          | 3         | 0.93%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 3         | 0.93%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3         | 0.93%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 3         | 0.93%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 0.93%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 3         | 0.93%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 3         | 0.93%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 3         | 0.93%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 3         | 0.93%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 3         | 0.93%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 3         | 0.93%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3         | 0.93%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 3         | 0.93%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz         | 2         | 0.62%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 0.62%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 2         | 0.62%   |
| Intel Pentium CPU G645 @ 2.90GHz            | 2         | 0.62%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 2         | 0.62%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 0.62%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 75        | 23.36%  |
| Intel Core i3           | 69        | 21.5%   |
| Intel Core i7           | 40        | 12.46%  |
| Intel Pentium           | 25        | 7.79%   |
| Intel Pentium Dual-Core | 16        | 4.98%   |
| Intel Genuine           | 16        | 4.98%   |
| Intel Core 2 Duo        | 16        | 4.98%   |
| Intel Celeron           | 13        | 4.05%   |
| Other                   | 9         | 2.8%    |
| Intel Atom              | 6         | 1.87%   |
| AMD Ryzen 5             | 6         | 1.87%   |
| AMD Ryzen 7             | 5         | 1.56%   |
| Intel Xeon              | 4         | 1.25%   |
| Intel Pentium Dual      | 4         | 1.25%   |
| Intel Core 2 Quad       | 2         | 0.62%   |
| AMD A4                  | 2         | 0.62%   |
| Intel Pentium D         | 1         | 0.31%   |
| Intel Pentium 4         | 1         | 0.31%   |
| ARM Allwinner           | 1         | 0.31%   |
| AMD Ryzen 9             | 1         | 0.31%   |
| AMD Ryzen 5 PRO         | 1         | 0.31%   |
| AMD Ryzen 3             | 1         | 0.31%   |
| AMD FX                  | 1         | 0.31%   |
| AMD E2                  | 1         | 0.31%   |
| AMD E1                  | 1         | 0.31%   |
| AMD C-70                | 1         | 0.31%   |
| AMD Athlon Neo X2       | 1         | 0.31%   |
| AMD Athlon II Dual-Core | 1         | 0.31%   |
| AMD Athlon 64           | 1         | 0.31%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 226       | 70.63%  |
| 4      | 70        | 21.88%  |
| 6      | 9         | 2.81%   |
| 8      | 5         | 1.56%   |
| 1      | 5         | 1.56%   |
| 16     | 2         | 0.63%   |
| 12     | 1         | 0.31%   |
| 10     | 1         | 0.31%   |
| 3      | 1         | 0.31%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 319       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 195       | 60.94%  |
| 1      | 124       | 38.75%  |
| 4      | 1         | 0.31%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 314       | 98.13%  |
| Unknown        | 4         | 1.25%   |
| 32-bit         | 2         | 0.63%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 115       | 33.92%  |
| 0x306a9    | 33        | 9.73%   |
| 0x206a7    | 27        | 7.96%   |
| 0x1067a    | 23        | 6.78%   |
| 0x20655    | 18        | 5.31%   |
| 0x40651    | 13        | 3.83%   |
| 0x406e3    | 11        | 3.24%   |
| 0x306c3    | 11        | 3.24%   |
| 0x306d4    | 9         | 2.65%   |
| 0x806e9    | 8         | 2.36%   |
| 0x30678    | 8         | 2.36%   |
| 0x906e9    | 5         | 1.47%   |
| 0x806ea    | 5         | 1.47%   |
| 0x6fd      | 5         | 1.47%   |
| 0x20652    | 3         | 0.88%   |
| 0x806ec    | 2         | 0.59%   |
| 0x706a8    | 2         | 0.59%   |
| 0x6fb      | 2         | 0.59%   |
| 0x506e3    | 2         | 0.59%   |
| 0x306e4    | 2         | 0.59%   |
| 0x30661    | 2         | 0.59%   |
| 0x10676    | 2         | 0.59%   |
| 0x0a50000d | 2         | 0.59%   |
| 0x08701021 | 2         | 0.59%   |
| 0x08600106 | 2         | 0.59%   |
| 0x0800820d | 2         | 0.59%   |
| 0x05000119 | 2         | 0.59%   |
| 0xf65      | 1         | 0.29%   |
| 0xa0652    | 1         | 0.29%   |
| 0x906eb    | 1         | 0.29%   |
| 0x906a4    | 1         | 0.29%   |
| 0x806c1    | 1         | 0.29%   |
| 0x706a1    | 1         | 0.29%   |
| 0x6ec      | 1         | 0.29%   |
| 0x6e8      | 1         | 0.29%   |
| 0x506c9    | 1         | 0.29%   |
| 0x406c4    | 1         | 0.29%   |
| 0x406c3    | 1         | 0.29%   |
| 0x206d7    | 1         | 0.29%   |
| 0x0a201016 | 1         | 0.29%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| IvyBridge        | 46        | 14.33%  |
| Penryn           | 44        | 13.71%  |
| SandyBridge      | 40        | 12.46%  |
| Haswell          | 40        | 12.46%  |
| KabyLake         | 32        | 9.97%   |
| Westmere         | 21        | 6.54%   |
| Skylake          | 18        | 5.61%   |
| Silvermont       | 15        | 4.67%   |
| Core             | 10        | 3.12%   |
| Broadwell        | 10        | 3.12%   |
| Zen 3            | 5         | 1.56%   |
| TigerLake        | 5         | 1.56%   |
| Zen 2            | 4         | 1.25%   |
| Goldmont plus    | 4         | 1.25%   |
| Unknown          | 4         | 1.25%   |
| Zen+             | 3         | 0.93%   |
| P6               | 2         | 0.62%   |
| NetBurst         | 2         | 0.62%   |
| K8 Hammer        | 2         | 0.62%   |
| Jaguar           | 2         | 0.62%   |
| Excavator        | 2         | 0.62%   |
| Bonnell          | 2         | 0.62%   |
| Bobcat           | 2         | 0.62%   |
| Zen              | 1         | 0.31%   |
| K10              | 1         | 0.31%   |
| Goldmont         | 1         | 0.31%   |
| CometLake        | 1         | 0.31%   |
| Bulldozer        | 1         | 0.31%   |
| Alderlake Hybrid | 1         | 0.31%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 244       | 62.4%   |
| Nvidia                     | 81        | 20.72%  |
| AMD                        | 63        | 16.11%  |
| VIA Technologies           | 2         | 0.51%   |
| Matrox Electronics Systems | 1         | 0.26%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 31        | 7.89%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 24        | 6.11%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 20        | 5.09%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 19        | 4.83%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 15        | 3.82%   |
| Nvidia GT218M [GeForce G210M]                                                            | 14        | 3.56%   |
| Intel Core Processor Integrated Graphics Controller                                      | 14        | 3.56%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 14        | 3.56%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 12        | 3.05%   |
| Intel HD Graphics 620                                                                    | 12        | 3.05%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 11        | 2.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 10        | 2.54%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 10        | 2.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9         | 2.29%   |
| Intel UHD Graphics 620                                                                   | 9         | 2.29%   |
| Intel HD Graphics 5500                                                                   | 8         | 2.04%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 1.53%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 1.27%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 1.27%   |
| Intel HD Graphics 630                                                                    | 5         | 1.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.27%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.02%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 3         | 0.76%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 3         | 0.76%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3         | 0.76%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 0.76%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 3         | 0.76%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 2         | 0.51%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 0.51%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.51%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 0.51%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 2         | 0.51%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 2         | 0.51%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.51%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 2         | 0.51%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 2         | 0.51%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 2         | 0.51%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 0.51%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.51%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 174       | 54.21%  |
| Intel + Nvidia | 45        | 14.02%  |
| 1 x AMD        | 39        | 12.15%  |
| 1 x Nvidia     | 35        | 10.9%   |
| Intel + AMD    | 23        | 7.17%   |
| 1 x VIA        | 2         | 0.62%   |
| Other          | 1         | 0.31%   |
| 1 x Matrox     | 1         | 0.31%   |
| AMD + Nvidia   | 1         | 0.31%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 289       | 88.92%  |
| Proprietary | 26        | 8%      |
| Unknown     | 10        | 3.08%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 203       | 62.27%  |
| 1.01-2.0   | 54        | 16.56%  |
| 0.01-0.5   | 33        | 10.12%  |
| 0.51-1.0   | 20        | 6.13%   |
| 3.01-4.0   | 9         | 2.76%   |
| 7.01-8.0   | 4         | 1.23%   |
| 5.01-6.0   | 2         | 0.61%   |
| 2.01-3.0   | 1         | 0.31%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 55        | 16.82%  |
| AU Optronics            | 46        | 14.07%  |
| LG Display              | 44        | 13.46%  |
| BOE                     | 28        | 8.56%   |
| Chimei Innolux          | 22        | 6.73%   |
| Acer                    | 20        | 6.12%   |
| Hewlett-Packard         | 16        | 4.89%   |
| AOC                     | 15        | 4.59%   |
| Chi Mei Optoelectronics | 13        | 3.98%   |
| Apple                   | 7         | 2.14%   |
| KTC                     | 6         | 1.83%   |
| Goldstar                | 6         | 1.83%   |
| Lenovo                  | 4         | 1.22%   |
| Dell                    | 4         | 1.22%   |
| BenQ                    | 4         | 1.22%   |
| Ancor Communications    | 4         | 1.22%   |
| Unknown                 | 4         | 1.22%   |
| Sharp                   | 3         | 0.92%   |
| Unknown (XXX)           | 2         | 0.61%   |
| Unknown                 | 2         | 0.61%   |
| SKY                     | 2         | 0.61%   |
| PANDA                   | 2         | 0.61%   |
| InfoVision              | 2         | 0.61%   |
| Fujitsu Siemens         | 2         | 0.61%   |
| ___                     | 1         | 0.31%   |
| Westinghouse            | 1         | 0.31%   |
| TSN                     | 1         | 0.31%   |
| TGC                     | 1         | 0.31%   |
| PTW                     | 1         | 0.31%   |
| PiLot                   | 1         | 0.31%   |
| MStar                   | 1         | 0.31%   |
| LGD                     | 1         | 0.31%   |
| ITE                     | 1         | 0.31%   |
| InnoLux Display         | 1         | 0.31%   |
| Hitachi                 | 1         | 0.31%   |
| EMP                     | 1         | 0.31%   |
| EDW                     | 1         | 0.31%   |
| AGO                     | 1         | 0.31%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO213C 1366x768 309x174mm 14.0-inch            | 14        | 4.23%   |
| Acer V193HQ ACR00F9 1366x768 410x230mm 18.5-inch                         | 14        | 4.23%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                           | 5         | 1.51%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 4         | 1.21%   |
| LG Display LCD Monitor LGD04BD 1366x768 344x194mm 15.5-inch              | 4         | 1.21%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 4         | 1.21%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 4         | 1.21%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A4 1366x768 344x194mm 15.5-inch | 4         | 1.21%   |
| Unknown                                                                  | 4         | 1.21%   |
| Samsung Electronics SMS22A100 SAM0868 1920x1080 477x268mm 21.5-inch      | 3         | 0.91%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch     | 3         | 0.91%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 3         | 0.91%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                     | 3         | 0.91%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch            | 3         | 0.91%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 0.91%   |
| AOC F22 AOC2200 1920x1080 476x268mm 21.5-inch                            | 3         | 0.91%   |
| Unknown (XXX) HDMI XXX0029 1920x1080 1152x648mm 52.0-inch                | 2         | 0.6%    |
| Sharp HDMI SHP10DB 1920x1080 1330x750mm 60.1-inch                        | 2         | 0.6%    |
| Samsung Electronics SMBX1931N SAM0768 1366x768 410x230mm 18.5-inch       | 2         | 0.6%    |
| Samsung Electronics SMB2030N SAM0634 1600x900 443x249mm 20.0-inch        | 2         | 0.6%    |
| Samsung Electronics LCD Monitor SEC3642 1366x768 309x174mm 14.0-inch     | 2         | 0.6%    |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch     | 2         | 0.6%    |
| Samsung Electronics LCD Monitor SDC4146 1366x768 344x194mm 15.5-inch     | 2         | 0.6%    |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch            | 2         | 0.6%    |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch              | 2         | 0.6%    |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch              | 2         | 0.6%    |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 2         | 0.6%    |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 2         | 0.6%    |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 2         | 0.6%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 2         | 0.6%    |
| KTC W9023S5 KTC1852 1360x768 410x230mm 18.5-inch                         | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN14D3 1920x1080 309x173mm 13.9-inch         | 2         | 0.6%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.6%    |
| BOE LCD Monitor BOE0661 1366x768 344x194mm 15.5-inch                     | 2         | 0.6%    |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                     | 2         | 0.6%    |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch            | 2         | 0.6%    |
| AOC 1950W AOC1950 1366x768 410x230mm 18.5-inch                           | 2         | 0.6%    |
| ___ SMART TV ___9687 1920x1080 820x460mm 37.0-inch                       | 1         | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 150       | 49.5%   |
| 1920x1080 (FHD)    | 80        | 26.4%   |
| 1600x900 (HD+)     | 17        | 5.61%   |
| 1440x900 (WXGA+)   | 13        | 4.29%   |
| 2560x1440 (QHD)    | 6         | 1.98%   |
| 1680x1050 (WSXGA+) | 6         | 1.98%   |
| 1280x1024 (SXGA)   | 6         | 1.98%   |
| 1360x768           | 5         | 1.65%   |
| 1280x800 (WXGA)    | 5         | 1.65%   |
| 3840x2160 (4K)     | 3         | 0.99%   |
| 1920x540           | 2         | 0.66%   |
| 1920x1200 (WUXGA)  | 2         | 0.66%   |
| 2880x1800          | 1         | 0.33%   |
| 2160x1440          | 1         | 0.33%   |
| 1680x945           | 1         | 0.33%   |
| 1600x1200          | 1         | 0.33%   |
| 1280x720 (HD)      | 1         | 0.33%   |
| 1152x864           | 1         | 0.33%   |
| 1024x768 (XGA)     | 1         | 0.33%   |
| 1024x600           | 1         | 0.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 121       | 36.89%  |
| 18      | 37        | 11.28%  |
| 14      | 32        | 9.76%   |
| 13      | 21        | 6.4%    |
| 21      | 15        | 4.57%   |
| 19      | 14        | 4.27%   |
| 17      | 12        | 3.66%   |
| 23      | 10        | 3.05%   |
| 20      | 10        | 3.05%   |
| 12      | 9         | 2.74%   |
| 27      | 8         | 2.44%   |
| Unknown | 8         | 2.44%   |
| 24      | 6         | 1.83%   |
| 52      | 4         | 1.22%   |
| 22      | 4         | 1.22%   |
| 11      | 3         | 0.91%   |
| 60      | 2         | 0.61%   |
| 40      | 2         | 0.61%   |
| 10      | 2         | 0.61%   |
| 72      | 1         | 0.3%    |
| 48      | 1         | 0.3%    |
| 46      | 1         | 0.3%    |
| 37      | 1         | 0.3%    |
| 32      | 1         | 0.3%    |
| 31      | 1         | 0.3%    |
| 29      | 1         | 0.3%    |
| 16      | 1         | 0.3%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 165       | 50.61%  |
| 401-500     | 75        | 23.01%  |
| 501-600     | 24        | 7.36%   |
| 201-300     | 21        | 6.44%   |
| 351-400     | 18        | 5.52%   |
| 1001-1500   | 8         | 2.45%   |
| Unknown     | 8         | 2.45%   |
| 801-900     | 3         | 0.92%   |
| 601-700     | 2         | 0.61%   |
| 701-800     | 1         | 0.31%   |
| 1501-2000   | 1         | 0.31%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 252       | 84.28%  |
| 16/10   | 26        | 8.7%    |
| Unknown | 6         | 2.01%   |
| 5/4     | 5         | 1.67%   |
| 4/3     | 5         | 1.67%   |
| 32/9    | 2         | 0.67%   |
| 3/2     | 2         | 0.67%   |
| 6/5     | 1         | 0.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 118       | 36.2%   |
| 81-90          | 48        | 14.72%  |
| 141-150        | 39        | 11.96%  |
| 151-200        | 30        | 9.2%    |
| 201-250        | 27        | 8.28%   |
| More than 1000 | 8         | 2.45%   |
| 61-70          | 8         | 2.45%   |
| 301-350        | 8         | 2.45%   |
| Unknown        | 8         | 2.45%   |
| 121-130        | 7         | 2.15%   |
| 71-80          | 6         | 1.84%   |
| 111-120        | 4         | 1.23%   |
| 501-1000       | 4         | 1.23%   |
| 51-60          | 3         | 0.92%   |
| 351-500        | 3         | 0.92%   |
| 41-50          | 2         | 0.61%   |
| 131-140        | 2         | 0.61%   |
| 251-300        | 1         | 0.31%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 134       | 41.49%  |
| 51-100        | 112       | 34.67%  |
| 121-160       | 50        | 15.48%  |
| 1-50          | 10        | 3.1%    |
| Unknown       | 8         | 2.48%   |
| 161-240       | 7         | 2.17%   |
| More than 240 | 2         | 0.62%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 270       | 83.33%  |
| 2     | 41        | 12.65%  |
| 0     | 11        | 3.4%    |
| 3     | 2         | 0.62%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 200       | 38.61%  |
| Qualcomm Atheros                | 91        | 17.57%  |
| Intel                           | 83        | 16.02%  |
| Broadcom                        | 42        | 8.11%   |
| Ralink Technology               | 30        | 5.79%   |
| Ralink                          | 13        | 2.51%   |
| MediaTek                        | 8         | 1.54%   |
| Qualcomm Atheros Communications | 7         | 1.35%   |
| Samsung Electronics             | 5         | 0.97%   |
| Broadcom Limited                | 5         | 0.97%   |
| Xiaomi                          | 4         | 0.77%   |
| TP-Link                         | 4         | 0.77%   |
| Marvell Technology Group        | 4         | 0.77%   |
| D-Link                          | 4         | 0.77%   |
| VIA Technologies                | 3         | 0.58%   |
| Nvidia                          | 3         | 0.58%   |
| D-Link System                   | 3         | 0.58%   |
| Sierra Wireless                 | 2         | 0.39%   |
| Huawei Technologies             | 2         | 0.39%   |
| Hewlett-Packard                 | 2         | 0.39%   |
| ZTE WCDMA Technologies MSM      | 1         | 0.19%   |
| LG Electronics                  | 1         | 0.19%   |
| AMD                             | 1         | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 110       | 18.55%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 66        | 11.13%  |
| Broadcom BCM43142 802.11b/g/n                                          | 17        | 2.87%   |
| Ralink MT7601U Wireless Adapter                                        | 15        | 2.53%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 14        | 2.36%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 14        | 2.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 14        | 2.36%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 14        | 2.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 13        | 2.19%   |
| Intel Wireless 8265 / 8275                                             | 12        | 2.02%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 11        | 1.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 11        | 1.85%   |
| Intel Ethernet Connection (4) I219-LM                                  | 9         | 1.52%   |
| Ralink RT5370 Wireless Adapter                                         | 8         | 1.35%   |
| Qualcomm Atheros AR9271 802.11n                                        | 7         | 1.18%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 6         | 1.01%   |
| Intel Wireless 7265                                                    | 6         | 1.01%   |
| Intel Wireless 7260                                                    | 6         | 1.01%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 5         | 0.84%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 5         | 0.84%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 5         | 0.84%   |
| Intel Wireless 8260                                                    | 5         | 0.84%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 0.84%   |
| Intel Ethernet Connection I218-LM                                      | 5         | 0.84%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 5         | 0.84%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 5         | 0.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 4         | 0.67%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 4         | 0.67%   |
| MediaTek RMX3085                                                       | 4         | 0.67%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 4         | 0.67%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 4         | 0.67%   |
| Intel Centrino Ultimate-N 6300                                         | 4         | 0.67%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3         | 0.51%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 3         | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3         | 0.51%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 3         | 0.51%   |
| Intel Wireless 3160                                                    | 3         | 0.51%   |
| Intel WiFi Link 5100                                                   | 3         | 0.51%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 72        | 25.62%  |
| Qualcomm Atheros                | 62        | 22.06%  |
| Realtek Semiconductor           | 42        | 14.95%  |
| Broadcom                        | 33        | 11.74%  |
| Ralink Technology               | 30        | 10.68%  |
| Ralink                          | 13        | 4.63%   |
| Qualcomm Atheros Communications | 7         | 2.49%   |
| TP-Link                         | 4         | 1.42%   |
| MediaTek                        | 4         | 1.42%   |
| D-Link                          | 4         | 1.42%   |
| D-Link System                   | 3         | 1.07%   |
| Sierra Wireless                 | 2         | 0.71%   |
| Hewlett-Packard                 | 2         | 0.71%   |
| Broadcom Limited                | 2         | 0.71%   |
| Marvell Technology Group        | 1         | 0.36%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Broadcom BCM43142 802.11b/g/n                                  | 17        | 6.01%   |
| Ralink MT7601U Wireless Adapter                                | 15        | 5.3%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 14        | 4.95%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 14        | 4.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 14        | 4.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 13        | 4.59%   |
| Intel Wireless 8265 / 8275                                     | 12        | 4.24%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 11        | 3.89%   |
| Ralink RT5370 Wireless Adapter                                 | 8         | 2.83%   |
| Qualcomm Atheros AR9271 802.11n                                | 7         | 2.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 6         | 2.12%   |
| Intel Wireless 7265                                            | 6         | 2.12%   |
| Intel Wireless 7260                                            | 6         | 2.12%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 5         | 1.77%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 5         | 1.77%   |
| Intel Wireless 8260                                            | 5         | 1.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 1.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 1.41%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 4         | 1.41%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 4         | 1.41%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 1.41%   |
| Intel Wireless 3160                                            | 3         | 1.06%   |
| Intel WiFi Link 5100                                           | 3         | 1.06%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 3         | 1.06%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 0.71%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 2         | 0.71%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 0.71%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 0.71%   |
| Ralink RT2870 Wireless Adapter                                 | 2         | 0.71%   |
| Ralink RT2561/RT61 rev B 802.11g                               | 2         | 0.71%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 2         | 0.71%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 0.71%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 0.71%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 0.71%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 0.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 0.71%   |
| Intel Centrino Wireless-N 2230                                 | 2         | 0.71%   |
| Intel Centrino Wireless-N 135                                  | 2         | 0.71%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 0.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 178       | 57.79%  |
| Intel                      | 52        | 16.88%  |
| Qualcomm Atheros           | 35        | 11.36%  |
| Broadcom                   | 14        | 4.55%   |
| Samsung Electronics        | 5         | 1.62%   |
| Xiaomi                     | 4         | 1.3%    |
| MediaTek                   | 4         | 1.3%    |
| VIA Technologies           | 3         | 0.97%   |
| Nvidia                     | 3         | 0.97%   |
| Marvell Technology Group   | 3         | 0.97%   |
| Broadcom Limited           | 3         | 0.97%   |
| ZTE WCDMA Technologies MSM | 1         | 0.32%   |
| LG Electronics             | 1         | 0.32%   |
| Huawei Technologies        | 1         | 0.32%   |
| AMD                        | 1         | 0.32%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 110       | 35.6%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 66        | 21.36%  |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 14        | 4.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 11        | 3.56%   |
| Intel Ethernet Connection (4) I219-LM                                  | 9         | 2.91%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 5         | 1.62%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 1.62%   |
| Intel Ethernet Connection I218-LM                                      | 5         | 1.62%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 5         | 1.62%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 4         | 1.29%   |
| MediaTek RMX3085                                                       | 4         | 1.29%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3         | 0.97%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 3         | 0.97%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 0.97%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3         | 0.97%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 3         | 0.97%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 0.97%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 3         | 0.97%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 2         | 0.65%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 2         | 0.65%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 2         | 0.65%   |
| Intel PRO/100 VE Network Connection                                    | 2         | 0.65%   |
| Intel I211 Gigabit Network Connection                                  | 2         | 0.65%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 0.65%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 0.65%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 2         | 0.65%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 2         | 0.65%   |
| ZTE WCDMA MSM DEMO Mobile Boardband                                    | 1         | 0.32%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1         | 0.32%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 0.32%   |
| Realtek PCIe GbE Family Controller                                     | 1         | 0.32%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 0.32%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 1         | 0.32%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                          | 1         | 0.32%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.32%   |
| Nvidia MCP89 Ethernet                                                  | 1         | 0.32%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.32%   |
| Nvidia MCP77 Ethernet                                                  | 1         | 0.32%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 1         | 0.32%   |
| LG G2 Android Phone [tethering mode]                                   | 1         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 293       | 53.08%  |
| WiFi     | 258       | 46.74%  |
| Modem    | 1         | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 210       | 64.42%  |
| Ethernet | 116       | 35.58%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 200       | 61.73%  |
| 1     | 115       | 35.49%  |
| 0     | 8         | 2.47%   |
| 3     | 1         | 0.31%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 319       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 47        | 30.92%  |
| Qualcomm Atheros Communications | 19        | 12.5%   |
| Broadcom                        | 13        | 8.55%   |
| Realtek Semiconductor           | 12        | 7.89%   |
| Lite-On Technology              | 8         | 5.26%   |
| IMC Networks                    | 8         | 5.26%   |
| Cambridge Silicon Radio         | 7         | 4.61%   |
| Foxconn / Hon Hai               | 6         | 3.95%   |
| Apple                           | 6         | 3.95%   |
| Ralink                          | 5         | 3.29%   |
| Dell                            | 5         | 3.29%   |
| Toshiba                         | 3         | 1.97%   |
| Foxconn International           | 3         | 1.97%   |
| Integrated System Solution      | 2         | 1.32%   |
| SiW                             | 1         | 0.66%   |
| Ralink Technology               | 1         | 0.66%   |
| Marvell Semiconductor           | 1         | 0.66%   |
| Hewlett-Packard                 | 1         | 0.66%   |
| Chicony Electronics             | 1         | 0.66%   |
| ASUSTek Computer                | 1         | 0.66%   |
| Alps Electric                   | 1         | 0.66%   |
| Actions                         | 1         | 0.66%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 17        | 11.18%  |
| Intel Bluetooth Device                                | 14        | 9.21%   |
| Qualcomm Atheros  Bluetooth Device                    | 8         | 5.26%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 7         | 4.61%   |
| Realtek Bluetooth Radio                               | 6         | 3.95%   |
| Ralink RT3290 Bluetooth                               | 5         | 3.29%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 5         | 3.29%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 4         | 2.63%   |
| IMC Networks Bluetooth Device                         | 4         | 2.63%   |
| Broadcom BCM43142 Bluetooth 4.0                       | 4         | 2.63%   |
| Apple Bluetooth Host Controller                       | 4         | 2.63%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 3         | 1.97%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 3         | 1.97%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 3         | 1.97%   |
| Foxconn International BCM43142A0 Bluetooth module     | 3         | 1.97%   |
| Foxconn / Hon Hai Bluetooth Device                    | 3         | 1.97%   |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 3         | 1.97%   |
| Toshiba Bluetooth Device                              | 2         | 1.32%   |
| Realtek RTL8723B Bluetooth                            | 2         | 1.32%   |
| Realtek  Bluetooth 4.2 Adapter                        | 2         | 1.32%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 2         | 1.32%   |
| Lite-On Wireless_Device                               | 2         | 1.32%   |
| Lite-On BCM43142A0                                    | 2         | 1.32%   |
| Intel Wireless-AC 3168 Bluetooth                      | 2         | 1.32%   |
| Intel AX201 Bluetooth                                 | 2         | 1.32%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 2         | 1.32%   |
| IMC Networks Wireless_Device                          | 2         | 1.32%   |
| Dell Wireless 365 Bluetooth                           | 2         | 1.32%   |
| Dell BCM20702A0 Bluetooth Module                      | 2         | 1.32%   |
| Broadcom BCM2045B (BDC-2.1)                           | 2         | 1.32%   |
| Toshiba BCM43142A0                                    | 1         | 0.66%   |
| SiW SiW                                               | 1         | 0.66%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter               | 1         | 0.66%   |
| Realtek RTL8821A Bluetooth                            | 1         | 0.66%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter          | 1         | 0.66%   |
| Qualcomm Atheros Bluetooth                            | 1         | 0.66%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1         | 0.66%   |
| Marvell Bluetooth and Wireless LAN Composite Device   | 1         | 0.66%   |
| Lite-On Bluetooth 4.0 [Broadcom BCM20702A0]           | 1         | 0.66%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1         | 0.66%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 281       | 69.04%  |
| Nvidia                 | 59        | 14.5%   |
| AMD                    | 50        | 12.29%  |
| JMTek                  | 4         | 0.98%   |
| VIA Technologies       | 3         | 0.74%   |
| Goldvish               | 2         | 0.49%   |
| Texas Instruments      | 1         | 0.25%   |
| Medeli Electronics     | 1         | 0.25%   |
| Logitech               | 1         | 0.25%   |
| Logic3 / SpectraVideo  | 1         | 0.25%   |
| Guillemot              | 1         | 0.25%   |
| GN Netcom              | 1         | 0.25%   |
| Generalplus Technology | 1         | 0.25%   |
| ASUSTek Computer       | 1         | 0.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 46        | 9.85%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 38        | 8.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 38        | 8.14%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 24        | 5.14%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 23        | 4.93%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 21        | 4.5%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 20        | 4.28%   |
| Intel 8 Series HD Audio Controller                                                                | 20        | 4.28%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 18        | 3.85%   |
| Nvidia High Definition Audio Controller                                                           | 17        | 3.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12        | 2.57%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 12        | 2.57%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 10        | 2.14%   |
| Intel Broadwell-U Audio Controller                                                                | 10        | 2.14%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 8         | 1.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 1.5%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 1.5%    |
| Nvidia GF119 HDMI Audio Controller                                                                | 5         | 1.07%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 1.07%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5         | 1.07%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 1.07%   |
| JMTek USB PnP Audio Device                                                                        | 4         | 0.86%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 0.86%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 0.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 0.86%   |
| AMD FCH Azalia Controller                                                                         | 4         | 0.86%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 3         | 0.64%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.64%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 3         | 0.64%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 0.64%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.43%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.43%   |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 0.43%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.43%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.43%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.43%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.43%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 0.43%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 0.43%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 0.43%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 54        | 24.88%  |
| SK hynix            | 39        | 17.97%  |
| Samsung Electronics | 39        | 17.97%  |
| Micron Technology   | 25        | 11.52%  |
| Kingston            | 15        | 6.91%   |
| A-DATA Technology   | 11        | 5.07%   |
| Crucial             | 6         | 2.76%   |
| Ramaxel Technology  | 4         | 1.84%   |
| Nanya Technology    | 4         | 1.84%   |
| TwinMOS             | 3         | 1.38%   |
| Unknown (ABCD)      | 2         | 0.92%   |
| Unknown             | 2         | 0.92%   |
| Thermaltake         | 1         | 0.46%   |
| Team                | 1         | 0.46%   |
| SemsoTai            | 1         | 0.46%   |
| Patriot             | 1         | 0.46%   |
| Goldkey             | 1         | 0.46%   |
| GeIL                | 1         | 0.46%   |
| G.Skill             | 1         | 0.46%   |
| Elpida              | 1         | 0.46%   |
| Dynet               | 1         | 0.46%   |
| CSX                 | 1         | 0.46%   |
| Corsair             | 1         | 0.46%   |
| ASint Technology    | 1         | 0.46%   |
| Asgard              | 1         | 0.46%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM 1066MT/s                   | 14        | 5.91%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                | 6         | 2.53%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s   | 6         | 2.53%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s    | 6         | 2.53%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 5         | 2.11%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                | 3         | 1.27%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s    | 3         | 1.27%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s    | 3         | 1.27%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s              | 2         | 0.84%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s           | 2         | 0.84%   |
| Unknown RAM Module 4096MB SODIMM DDR3                    | 2         | 0.84%   |
| Unknown RAM Module 2GB DIMM 800MT/s                      | 2         | 0.84%   |
| Unknown RAM Module 2GB DIMM 667MT/s                      | 2         | 0.84%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s             | 2         | 0.84%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s   | 2         | 0.84%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s   | 2         | 0.84%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s     | 2         | 0.84%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s   | 2         | 0.84%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s    | 2         | 0.84%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s    | 2         | 0.84%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s    | 2         | 0.84%   |
| Nanya RAM Module 8GB SODIMM DDR4 2667MT/s                | 2         | 0.84%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 2         | 0.84%   |
| Micron RAM 16ATF1G64HZ-2G1B1 8GB SODIMM DDR4 2133MT/s    | 2         | 0.84%   |
| Kingston RAM ACR256X64D3S1333C9 2GB SODIMM DDR3 1334MT/s | 2         | 0.84%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s              | 2         | 0.84%   |
| Unknown                                                  | 2         | 0.84%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s              | 1         | 0.42%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s           | 1         | 0.42%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s             | 1         | 0.42%   |
| Unknown RAM Module 4GB SODIMM DDR2                       | 1         | 0.42%   |
| Unknown RAM Module 4GB DIMM SDRAM                        | 1         | 0.42%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                | 1         | 0.42%   |
| Unknown RAM Module 4GB DIMM 400MT/s                      | 1         | 0.42%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s           | 1         | 0.42%   |
| Unknown RAM Module 4096MB SODIMM DDR2                    | 1         | 0.42%   |
| Unknown RAM Module 4096MB DIMM SDRAM 1333MT/s            | 1         | 0.42%   |
| Unknown RAM Module 4096MB DIMM SDRAM                     | 1         | 0.42%   |
| Unknown RAM Module 4096MB DIMM DDR3 800MT/s              | 1         | 0.42%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s             | 1         | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 88        | 50%     |
| DDR4    | 39        | 22.16%  |
| Unknown | 22        | 12.5%   |
| SDRAM   | 10        | 5.68%   |
| DDR2    | 9         | 5.11%   |
| LPDDR4  | 4         | 2.27%   |
| LPDDR3  | 2         | 1.14%   |
| DDR5    | 1         | 0.57%   |
| DDR     | 1         | 0.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 108       | 63.16%  |
| DIMM         | 61        | 35.67%  |
| Row Of Chips | 2         | 1.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 92        | 47.42%  |
| 2048  | 43        | 22.16%  |
| 8192  | 38        | 19.59%  |
| 1024  | 8         | 4.12%   |
| 16384 | 7         | 3.61%   |
| 32768 | 4         | 2.06%   |
| 512   | 2         | 1.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 52        | 26.4%   |
| 1333    | 28        | 14.21%  |
| 1066    | 15        | 7.61%   |
| 2667    | 14        | 7.11%   |
| 3200    | 12        | 6.09%   |
| 2400    | 9         | 4.57%   |
| 2133    | 9         | 4.57%   |
| 1334    | 7         | 3.55%   |
| 800     | 7         | 3.55%   |
| Unknown | 7         | 3.55%   |
| 1067    | 6         | 3.05%   |
| 667     | 5         | 2.54%   |
| 4199    | 3         | 1.52%   |
| 3600    | 2         | 1.02%   |
| 3266    | 2         | 1.02%   |
| 533     | 2         | 1.02%   |
| 400     | 2         | 1.02%   |
| 6400    | 1         | 0.51%   |
| 3800    | 1         | 0.51%   |
| 3066    | 1         | 0.51%   |
| 3000    | 1         | 0.51%   |
| 2666    | 1         | 0.51%   |
| 2200    | 1         | 0.51%   |
| 2000    | 1         | 0.51%   |
| 1867    | 1         | 0.51%   |
| 1800    | 1         | 0.51%   |
| 1648    | 1         | 0.51%   |
| 1639    | 1         | 0.51%   |
| 1400    | 1         | 0.51%   |
| 333     | 1         | 0.51%   |
| 266     | 1         | 0.51%   |
| 200     | 1         | 0.51%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 11        | 61.11%  |
| Seiko Epson        | 4         | 22.22%  |
| Hewlett-Packard    | 2         | 11.11%  |
| Brother Industries | 1         | 5.56%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Canon LBP6000                                                         | 2         | 11.11%  |
| Canon CAPT USB Device                                                 | 2         | 11.11%  |
| Seiko Epson XP-240 Series                                             | 1         | 5.56%   |
| Seiko Epson XP-205 207 Series                                         | 1         | 5.56%   |
| Seiko Epson Printer                                                   | 1         | 5.56%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 5.56%   |
| HP Ink Tank 310 series                                                | 1         | 5.56%   |
| HP DeskJet 5810 series                                                | 1         | 5.56%   |
| Canon MG5700 series                                                   | 1         | 5.56%   |
| Canon MF4010 series                                                   | 1         | 5.56%   |
| Canon MF3010                                                          | 1         | 5.56%   |
| Canon LBP6030w/6018w                                                  | 1         | 5.56%   |
| Canon LBP3010/LBP3018/LBP3050                                         | 1         | 5.56%   |
| Canon LBP3000                                                         | 1         | 5.56%   |
| Canon LBP2900                                                         | 1         | 5.56%   |
| Brother MFC-J480DW                                                    | 1         | 5.56%   |

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


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LIDE 25 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 58        | 29.9%   |
| Microdia                               | 27        | 13.92%  |
| Realtek Semiconductor                  | 20        | 10.31%  |
| Cheng Uei Precision Industry (Foxlink) | 13        | 6.7%    |
| Sunplus Innovation Technology          | 10        | 5.15%   |
| Suyin                                  | 9         | 4.64%   |
| IMC Networks                           | 8         | 4.12%   |
| Bison Electronics                      | 7         | 3.61%   |
| Apple                                  | 6         | 3.09%   |
| Syntek                                 | 5         | 2.58%   |
| Acer                                   | 5         | 2.58%   |
| Silicon Motion                         | 3         | 1.55%   |
| Samsung Electronics                    | 3         | 1.55%   |
| Quanta                                 | 3         | 1.55%   |
| Lite-On Technology                     | 3         | 1.55%   |
| Alcor Micro                            | 2         | 1.03%   |
| Sonix Technology                       | 1         | 0.52%   |
| Ricoh                                  | 1         | 0.52%   |
| Primax Electronics                     | 1         | 0.52%   |
| Pixart Imaging                         | 1         | 0.52%   |
| Microsoft                              | 1         | 0.52%   |
| Luxvisions Innotech Limited            | 1         | 0.52%   |
| Logitech                               | 1         | 0.52%   |
| GEMBIRD                                | 1         | 0.52%   |
| Cubeternet                             | 1         | 0.52%   |
| Aveo Technology                        | 1         | 0.52%   |
| Arkmicro Technologies                  | 1         | 0.52%   |
| ALi                                    | 1         | 0.52%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chicony Asus Integrated 0.3M UVC Webcam                                  | 14        | 7.18%   |
| Microdia Integrated_Webcam_HD                                            | 8         | 4.1%    |
| Chicony Integrated Camera                                                | 7         | 3.59%   |
| Chicony TOSHIBA Web Camera - HD                                          | 6         | 3.08%   |
| Microdia Laptop_Integrated_Webcam_HD                                     | 5         | 2.56%   |
| Chicony HP Truevision HD                                                 | 4         | 2.05%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                      | 4         | 2.05%   |
| Acer Lenovo EasyCamera                                                   | 4         | 2.05%   |
| Syntek Lenovo EasyCamera                                                 | 3         | 1.54%   |
| Suyin HP Truevision HD                                                   | 3         | 1.54%   |
| Sunplus Integrated_Webcam_HD                                             | 3         | 1.54%   |
| Samsung Galaxy series, misc. (MTP mode)                                  | 3         | 1.54%   |
| Realtek Integrated_Webcam_HD                                             | 3         | 1.54%   |
| Microdia Laptop_Integrated_Webcam_E4HD                                   | 3         | 1.54%   |
| Microdia Integrated Webcam                                               | 3         | 1.54%   |
| Chicony HD WebCam                                                        | 3         | 1.54%   |
| Bison Lenovo EasyCamera                                                  | 3         | 1.54%   |
| Apple Built-in iSight                                                    | 3         | 1.54%   |
| Suyin HD WebCam                                                          | 2         | 1.03%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                     | 2         | 1.03%   |
| Realtek USB2.0 VGA UVC WebCam                                            | 2         | 1.03%   |
| Realtek USB Camera                                                       | 2         | 1.03%   |
| Realtek Integrated Webcam                                                | 2         | 1.03%   |
| Realtek HP Truevision HD                                                 | 2         | 1.03%   |
| Realtek Acer 640 x 480 laptop camera                                     | 2         | 1.03%   |
| IMC Networks USB2.0 HD UVC WebCam                                        | 2         | 1.03%   |
| IMC Networks Lenovo EasyCamera                                           | 2         | 1.03%   |
| Chicony USB2.0 VGA UVC WebCam                                            | 2         | 1.03%   |
| Chicony HP HD Webcam [Fixed]                                             | 2         | 1.03%   |
| Chicony FJ Camera                                                        | 2         | 1.03%   |
| Chicony Acer CrystalEye Webcam                                           | 2         | 1.03%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                            | 2         | 1.03%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                         | 2         | 1.03%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 2         | 1.03%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                          | 2         | 1.03%   |
| Syntek USB2.0 Camera                                                     | 1         | 0.51%   |
| Syntek EasyCamera                                                        | 1         | 0.51%   |
| Suyin WebCam                                                             | 1         | 0.51%   |
| Suyin Laptop_Integrated_Webcam_2HDM                                      | 1         | 0.51%   |
| Suyin Integrated_Webcam_HD                                               | 1         | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 13        | 65%     |
| Synaptics             | 4         | 20%     |
| AuthenTec             | 2         | 10%     |
| Elan Microelectronics | 1         | 5%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader        | 6         | 30%     |
| Validity Sensors VFS491                           | 3         | 15%     |
| Validity Sensors VFS 5011 fingerprint sensor      | 2         | 10%     |
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 5%      |
| Validity Sensors Synaptics WBDI                   | 1         | 5%      |
| Synaptics WBDI Device                             | 1         | 5%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 5%      |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 5%      |
| Synaptics Fingerprint reader [HP G6]              | 1         | 5%      |
| Elan ELAN:Fingerprint                             | 1         | 5%      |
| AuthenTec AES2810                                 | 1         | 5%      |
| AuthenTec AES1600                                 | 1         | 5%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 13        | 92.86%  |
| OmniKey  | 1         | 7.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 7         | 50%     |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 28.57%  |
| OmniKey CardMan 4321                                                         | 1         | 7.14%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 7.14%   |
| Broadcom 58200                                                               | 1         | 7.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 232       | 70.3%   |
| 1     | 81        | 24.55%  |
| 2     | 13        | 3.94%   |
| 3     | 4         | 1.21%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 34        | 29.06%  |
| Fingerprint reader       | 20        | 17.09%  |
| Net/wireless             | 17        | 14.53%  |
| Chipcard                 | 14        | 11.97%  |
| Communication controller | 7         | 5.98%   |
| Bluetooth                | 6         | 5.13%   |
| Multimedia controller    | 5         | 4.27%   |
| Camera                   | 4         | 3.42%   |
| Storage                  | 3         | 2.56%   |
| Sound                    | 3         | 2.56%   |
| Net/ethernet             | 3         | 2.56%   |
| Card reader              | 1         | 0.85%   |


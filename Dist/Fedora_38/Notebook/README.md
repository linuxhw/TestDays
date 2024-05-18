Fedora 38 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Fedora 38.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 2466

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Sony          | SVE1512Z1EB                 | [18a1eb8f10](https://linux-hardware.org/?probe=18a1eb8f10) | Apr 30, 2024 |
| HP            | ZBook Firefly 14 inch G9... | [22dcf39db0](https://linux-hardware.org/?probe=22dcf39db0) | Apr 29, 2024 |
| Lenovo        | ThinkPad T520 42424WU       | [f54ef8bc01](https://linux-hardware.org/?probe=f54ef8bc01) | Apr 27, 2024 |
| Dell          | Inspiron 15 3520            | [3c7367dc40](https://linux-hardware.org/?probe=3c7367dc40) | Apr 25, 2024 |
| Unknown       | W1415A                      | [50907a4878](https://linux-hardware.org/?probe=50907a4878) | Apr 25, 2024 |
| Dell          | Latitude E5420              | [29150a7b19](https://linux-hardware.org/?probe=29150a7b19) | Apr 17, 2024 |
| Dell          | G15 5525                    | [74c6d6a8f8](https://linux-hardware.org/?probe=74c6d6a8f8) | Apr 15, 2024 |
| Dell          | G15 5525                    | [7842ec2d68](https://linux-hardware.org/?probe=7842ec2d68) | Apr 12, 2024 |
| Acer          | Nitro AN515-52              | [e08da0d2dd](https://linux-hardware.org/?probe=e08da0d2dd) | Apr 11, 2024 |
| HUAWEI        | CREM-WXX9                   | [2abd83a846](https://linux-hardware.org/?probe=2abd83a846) | Apr 09, 2024 |
| HUAWEI        | CREM-WXX9                   | [622d81532a](https://linux-hardware.org/?probe=622d81532a) | Apr 08, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a93a4109d7](https://linux-hardware.org/?probe=a93a4109d7) | Apr 07, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [b51e077a23](https://linux-hardware.org/?probe=b51e077a23) | Apr 07, 2024 |
| Dell          | G15 5525                    | [761f9399bc](https://linux-hardware.org/?probe=761f9399bc) | Apr 02, 2024 |
| Lenovo        | Legion Y9000P IAH7H 82RF    | [bc908f87b5](https://linux-hardware.org/?probe=bc908f87b5) | Mar 27, 2024 |
| Dell          | Studio 1537                 | [eaec8e4b11](https://linux-hardware.org/?probe=eaec8e4b11) | Mar 24, 2024 |
| Dell          | Studio 1537                 | [80777d58fb](https://linux-hardware.org/?probe=80777d58fb) | Mar 24, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [8041a52ffe](https://linux-hardware.org/?probe=8041a52ffe) | Mar 21, 2024 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | [a72ccae833](https://linux-hardware.org/?probe=a72ccae833) | Mar 19, 2024 |
| Dell          | Inspiron 5567               | [3828683188](https://linux-hardware.org/?probe=3828683188) | Mar 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [076b0dcbc4](https://linux-hardware.org/?probe=076b0dcbc4) | Mar 16, 2024 |
| Lenovo        | Legion 5 15ARH05 82B5       | [71d3373343](https://linux-hardware.org/?probe=71d3373343) | Mar 13, 2024 |
| Lenovo        | Legion 5 15ARH05 82B5       | [24bd77109e](https://linux-hardware.org/?probe=24bd77109e) | Mar 13, 2024 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [fbc1335ccc](https://linux-hardware.org/?probe=fbc1335ccc) | Mar 12, 2024 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [2417a59037](https://linux-hardware.org/?probe=2417a59037) | Mar 12, 2024 |
| Lenovo        | ThinkPad T430 2349SA2       | [ff165c1172](https://linux-hardware.org/?probe=ff165c1172) | Mar 09, 2024 |
| Lenovo        | ThinkPad T430 2349SA2       | [36f2425c6d](https://linux-hardware.org/?probe=36f2425c6d) | Mar 05, 2024 |
| Medion        | ME Series                   | [ace6388b48](https://linux-hardware.org/?probe=ace6388b48) | Mar 04, 2024 |
| HP            | ENVY 15                     | [86b5b9b7d7](https://linux-hardware.org/?probe=86b5b9b7d7) | Mar 04, 2024 |
| HP            | ENVY 15                     | [f8fc004a9c](https://linux-hardware.org/?probe=f8fc004a9c) | Mar 03, 2024 |
| Lenovo        | ThinkPad T430 2349SA2       | [2a2fc2e55c](https://linux-hardware.org/?probe=2a2fc2e55c) | Mar 03, 2024 |
| MSI           | GL65 Leopard 10SCXR         | [c7a95a6968](https://linux-hardware.org/?probe=c7a95a6968) | Feb 29, 2024 |
| Acer          | Aspire A315-24P             | [fc38526fc2](https://linux-hardware.org/?probe=fc38526fc2) | Feb 26, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [3f760d848e](https://linux-hardware.org/?probe=3f760d848e) | Feb 26, 2024 |
| HP            | ZBook 17 G5                 | [6be338eb09](https://linux-hardware.org/?probe=6be338eb09) | Feb 25, 2024 |
| Lenovo        | G500 20236                  | [414d89413c](https://linux-hardware.org/?probe=414d89413c) | Feb 24, 2024 |
| ASUSTek       | K53SC                       | [35b1dda2a4](https://linux-hardware.org/?probe=35b1dda2a4) | Feb 24, 2024 |
| HP            | Pavilion 17                 | [689fe676e5](https://linux-hardware.org/?probe=689fe676e5) | Feb 21, 2024 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [e3eb549631](https://linux-hardware.org/?probe=e3eb549631) | Feb 21, 2024 |
| Acer          | Nitro AN515-52              | [d87447cdf2](https://linux-hardware.org/?probe=d87447cdf2) | Feb 16, 2024 |
| Acer          | Aspire A715-75G             | [0c08871a46](https://linux-hardware.org/?probe=0c08871a46) | Feb 11, 2024 |
| HP            | Pavilion Notebook           | [7da16fe9d7](https://linux-hardware.org/?probe=7da16fe9d7) | Feb 09, 2024 |
| Dell          | Latitude 5510               | [e0d5fe1c62](https://linux-hardware.org/?probe=e0d5fe1c62) | Feb 07, 2024 |
| HP            | EliteBook 840 G2            | [4a3954a4c1](https://linux-hardware.org/?probe=4a3954a4c1) | Feb 02, 2024 |
| Acer          | Aspire VN7-591G             | [c0f024d3e0](https://linux-hardware.org/?probe=c0f024d3e0) | Feb 02, 2024 |
| Lenovo        | ThinkPad P52 20M9001MMX     | [0270f75e12](https://linux-hardware.org/?probe=0270f75e12) | Jan 29, 2024 |
| Dell          | Latitude 5420               | [459fbb3448](https://linux-hardware.org/?probe=459fbb3448) | Jan 28, 2024 |
| Lenovo        | ThinkPad T430 2349SA2       | [8c4e929f6f](https://linux-hardware.org/?probe=8c4e929f6f) | Jan 27, 2024 |
| Apple         | MacBookAir7,2               | [0aeced0805](https://linux-hardware.org/?probe=0aeced0805) | Jan 26, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [8cafa419c5](https://linux-hardware.org/?probe=8cafa419c5) | Jan 26, 2024 |
| Apple         | MacBookPro16,1              | [62447a80b3](https://linux-hardware.org/?probe=62447a80b3) | Jan 22, 2024 |
| Apple         | MacBookPro16,1              | [f9faae4b87](https://linux-hardware.org/?probe=f9faae4b87) | Jan 22, 2024 |
| Lenovo        | ThinkPad X220 429044U       | [d5fd867450](https://linux-hardware.org/?probe=d5fd867450) | Jan 21, 2024 |
| Nuvision      | L1W6_I1101_G Hampoo Rese... | [fb82a79de2](https://linux-hardware.org/?probe=fb82a79de2) | Jan 19, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [c699d403f6](https://linux-hardware.org/?probe=c699d403f6) | Jan 14, 2024 |
| Apple         | MacBookPro11,2              | [c9f084fd2a](https://linux-hardware.org/?probe=c9f084fd2a) | Jan 13, 2024 |
| ASUSTek       | X580VD                      | [25e38b0f43](https://linux-hardware.org/?probe=25e38b0f43) | Jan 12, 2024 |
| ASUSTek       | G53SX                       | [01ccd618c5](https://linux-hardware.org/?probe=01ccd618c5) | Jan 11, 2024 |
| Lenovo        | ThinkPad X230 2325Y3G       | [f2c9141668](https://linux-hardware.org/?probe=f2c9141668) | Jan 08, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [81d7f1e405](https://linux-hardware.org/?probe=81d7f1e405) | Jan 08, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [1673e31468](https://linux-hardware.org/?probe=1673e31468) | Jan 08, 2024 |
| Lenovo        | Legion 5 Pro 16IAH7 82S0    | [94a6c6bf63](https://linux-hardware.org/?probe=94a6c6bf63) | Jan 07, 2024 |
| HP            | ProBook 445 G7              | [758fdda6d6](https://linux-hardware.org/?probe=758fdda6d6) | Jan 05, 2024 |
| Framework     | Laptop (13th Gen Intel C... | [183851c797](https://linux-hardware.org/?probe=183851c797) | Jan 04, 2024 |
| Apple         | MacBookPro11,2              | [65c5154739](https://linux-hardware.org/?probe=65c5154739) | Jan 04, 2024 |
| HUAWEI        | NBM-WXX9                    | [f1a366a5a9](https://linux-hardware.org/?probe=f1a366a5a9) | Jan 03, 2024 |
| HP            | ProBook 6570b               | [98ccfce078](https://linux-hardware.org/?probe=98ccfce078) | Jan 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [689f8869db](https://linux-hardware.org/?probe=689f8869db) | Jan 01, 2024 |
| Apple         | MacBookPro11,2              | [4a37a9b35c](https://linux-hardware.org/?probe=4a37a9b35c) | Jan 01, 2024 |
| Lenovo        | ThinkPad T460 20FMS2291P    | [1a86f2a3d4](https://linux-hardware.org/?probe=1a86f2a3d4) | Jan 01, 2024 |
| Dell          | Inspiron 5748               | [20017233b9](https://linux-hardware.org/?probe=20017233b9) | Dec 30, 2023 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [53fc03e451](https://linux-hardware.org/?probe=53fc03e451) | Dec 29, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [6c5599855c](https://linux-hardware.org/?probe=6c5599855c) | Dec 29, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [0be6e9ce52](https://linux-hardware.org/?probe=0be6e9ce52) | Dec 29, 2023 |
| HP            | EliteBook 2570p             | [935d08358c](https://linux-hardware.org/?probe=935d08358c) | Dec 29, 2023 |
| HP            | EliteBook 840 G2            | [bbce6fb229](https://linux-hardware.org/?probe=bbce6fb229) | Dec 28, 2023 |
| HP            | EliteBook 840 G2            | [6ba5504a6f](https://linux-hardware.org/?probe=6ba5504a6f) | Dec 28, 2023 |
| Chuwi         | MiniBook X                  | [6249e8f644](https://linux-hardware.org/?probe=6249e8f644) | Dec 27, 2023 |
| Lenovo        | ThinkPad T460p 20FWCTO1W... | [00e7af074b](https://linux-hardware.org/?probe=00e7af074b) | Dec 25, 2023 |
| Apple         | MacBookPro9,2               | [5206fdfe7e](https://linux-hardware.org/?probe=5206fdfe7e) | Dec 24, 2023 |
| Apple         | MacBookPro9,2               | [976944381c](https://linux-hardware.org/?probe=976944381c) | Dec 24, 2023 |
| HP            | Elite x2 1012 G1            | [c93fffc388](https://linux-hardware.org/?probe=c93fffc388) | Dec 23, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [5c4d1c7d64](https://linux-hardware.org/?probe=5c4d1c7d64) | Dec 23, 2023 |
| ASUSTek       | T100TA                      | [9ad17d2d3c](https://linux-hardware.org/?probe=9ad17d2d3c) | Dec 23, 2023 |
| Dell          | Latitude 5420               | [9858586a84](https://linux-hardware.org/?probe=9858586a84) | Dec 22, 2023 |
| Dell          | Precision M4800             | [ce7a9239f4](https://linux-hardware.org/?probe=ce7a9239f4) | Dec 22, 2023 |
| Lenovo        | ThinkPad E14 20RB000UBR     | [d65cca0578](https://linux-hardware.org/?probe=d65cca0578) | Dec 22, 2023 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [e864a3cd22](https://linux-hardware.org/?probe=e864a3cd22) | Dec 21, 2023 |
| HP            | ProBook 445 G7              | [4153ae7cc6](https://linux-hardware.org/?probe=4153ae7cc6) | Dec 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [eef5dcab57](https://linux-hardware.org/?probe=eef5dcab57) | Dec 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [19fe61d807](https://linux-hardware.org/?probe=19fe61d807) | Dec 18, 2023 |
| Samsung       | 550P5C/550P7C               | [b06e8fbef4](https://linux-hardware.org/?probe=b06e8fbef4) | Dec 18, 2023 |
| HP            | ZBook 17 G5                 | [288e976604](https://linux-hardware.org/?probe=288e976604) | Dec 17, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [845e586dba](https://linux-hardware.org/?probe=845e586dba) | Dec 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [f4c923a84a](https://linux-hardware.org/?probe=f4c923a84a) | Dec 16, 2023 |
| HP            | ZBook 15u G6                | [4467debb1c](https://linux-hardware.org/?probe=4467debb1c) | Dec 15, 2023 |
| Dell          | Inspiron 3793               | [90804693a6](https://linux-hardware.org/?probe=90804693a6) | Dec 14, 2023 |
| Apple         | MacBookAir9,1               | [6cadf8d04e](https://linux-hardware.org/?probe=6cadf8d04e) | Dec 14, 2023 |
| Dell          | XPS 15 9530                 | [33d1f683ba](https://linux-hardware.org/?probe=33d1f683ba) | Dec 13, 2023 |
| Acer          | V5-171                      | [79abc82869](https://linux-hardware.org/?probe=79abc82869) | Dec 11, 2023 |
| Lenovo        | ThinkPad T440p 20ANCTO1W... | [070ba5c3c1](https://linux-hardware.org/?probe=070ba5c3c1) | Dec 10, 2023 |
| Dell          | Latitude E6430              | [dee39185ec](https://linux-hardware.org/?probe=dee39185ec) | Dec 08, 2023 |
| Dell          | Precision M4700             | [54abe2ce35](https://linux-hardware.org/?probe=54abe2ce35) | Dec 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [cf832dba27](https://linux-hardware.org/?probe=cf832dba27) | Dec 08, 2023 |
| HONOR         | HGF-WX6                     | [0ba74f97d0](https://linux-hardware.org/?probe=0ba74f97d0) | Dec 07, 2023 |
| Dell          | System Inspiron N4110       | [72874bcc85](https://linux-hardware.org/?probe=72874bcc85) | Dec 07, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [de12499622](https://linux-hardware.org/?probe=de12499622) | Dec 05, 2023 |
| Lenovo        | Legion 5 15ITH6H 82JH       | [fe13325e26](https://linux-hardware.org/?probe=fe13325e26) | Dec 05, 2023 |
| Dell          | Latitude 5420               | [b3ebc9b0fc](https://linux-hardware.org/?probe=b3ebc9b0fc) | Dec 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [da6b435afa](https://linux-hardware.org/?probe=da6b435afa) | Dec 02, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [6189dc268f](https://linux-hardware.org/?probe=6189dc268f) | Dec 02, 2023 |
| Lenovo        | ThinkPad T460s 20FAS09H0... | [94274c6313](https://linux-hardware.org/?probe=94274c6313) | Dec 02, 2023 |
| Dell          | Inspiron 7720               | [974a2661e2](https://linux-hardware.org/?probe=974a2661e2) | Dec 01, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [f2dc650bdf](https://linux-hardware.org/?probe=f2dc650bdf) | Nov 30, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [d9b203868f](https://linux-hardware.org/?probe=d9b203868f) | Nov 29, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [7db0c2781b](https://linux-hardware.org/?probe=7db0c2781b) | Nov 29, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [4fb92d7fe0](https://linux-hardware.org/?probe=4fb92d7fe0) | Nov 29, 2023 |
| Dell          | Precision M3800             | [a01e02361f](https://linux-hardware.org/?probe=a01e02361f) | Nov 26, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [ce1806eec5](https://linux-hardware.org/?probe=ce1806eec5) | Nov 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [ce68d047a6](https://linux-hardware.org/?probe=ce68d047a6) | Nov 26, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [78b8e2f560](https://linux-hardware.org/?probe=78b8e2f560) | Nov 26, 2023 |
| MSI           | PS63 Modern 8RC             | [d647ccba36](https://linux-hardware.org/?probe=d647ccba36) | Nov 26, 2023 |
| HP            | Stream Laptop 11-ah1XX      | [1e704edcd6](https://linux-hardware.org/?probe=1e704edcd6) | Nov 26, 2023 |
| Lenovo        | G510 20238                  | [75a5b58cb8](https://linux-hardware.org/?probe=75a5b58cb8) | Nov 25, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [2852a62f61](https://linux-hardware.org/?probe=2852a62f61) | Nov 24, 2023 |
| Dell          | Latitude E5450              | [fad9a32575](https://linux-hardware.org/?probe=fad9a32575) | Nov 23, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [bf30102553](https://linux-hardware.org/?probe=bf30102553) | Nov 23, 2023 |
| Gigabyte      | AX370-Gaming-CF se1         | [541752a388](https://linux-hardware.org/?probe=541752a388) | Nov 21, 2023 |
| Lenovo        | B580 20144                  | [634e12256a](https://linux-hardware.org/?probe=634e12256a) | Nov 21, 2023 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [26ebeb2504](https://linux-hardware.org/?probe=26ebeb2504) | Nov 20, 2023 |
| BTO           | 17X1183                     | [6cd57738ff](https://linux-hardware.org/?probe=6cd57738ff) | Nov 20, 2023 |
| Dell          | Inspiron 7375               | [b72b8abe13](https://linux-hardware.org/?probe=b72b8abe13) | Nov 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [94962a7ceb](https://linux-hardware.org/?probe=94962a7ceb) | Nov 19, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [d957a1a8c5](https://linux-hardware.org/?probe=d957a1a8c5) | Nov 19, 2023 |
| Timi          | TM1701                      | [f14bab873b](https://linux-hardware.org/?probe=f14bab873b) | Nov 18, 2023 |
| Acer          | Aspire A315-53G             | [7f9669bf0b](https://linux-hardware.org/?probe=7f9669bf0b) | Nov 18, 2023 |
| Google        | Kano                        | [3a0f7846c4](https://linux-hardware.org/?probe=3a0f7846c4) | Nov 17, 2023 |
| Google        | Kano                        | [0c5e699794](https://linux-hardware.org/?probe=0c5e699794) | Nov 17, 2023 |
| Acer          | Aspire A515-45              | [d1800f3356](https://linux-hardware.org/?probe=d1800f3356) | Nov 16, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [f1ba9de4ad](https://linux-hardware.org/?probe=f1ba9de4ad) | Nov 16, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [ffc320e32c](https://linux-hardware.org/?probe=ffc320e32c) | Nov 15, 2023 |
| Acer          | Predator PH315-53           | [f2a6eea13e](https://linux-hardware.org/?probe=f2a6eea13e) | Nov 14, 2023 |
| HP            | EliteBook 840 G2            | [64cfcced5b](https://linux-hardware.org/?probe=64cfcced5b) | Nov 14, 2023 |
| MSI           | Prestige 14 A10SC           | [59ad7e7e27](https://linux-hardware.org/?probe=59ad7e7e27) | Nov 14, 2023 |
| MSI           | Prestige 14 A10SC           | [6b1a5452f8](https://linux-hardware.org/?probe=6b1a5452f8) | Nov 14, 2023 |
| Dell          | Latitude 7390 2-in-1        | [f92b2d58ec](https://linux-hardware.org/?probe=f92b2d58ec) | Nov 14, 2023 |
| HP            | EliteBook 840 G2            | [4b522b316d](https://linux-hardware.org/?probe=4b522b316d) | Nov 14, 2023 |
| Acer          | Aspire A515-57              | [bb0f5fe1e2](https://linux-hardware.org/?probe=bb0f5fe1e2) | Nov 14, 2023 |
| ASUSTek       | TUF Gaming FA506II_FA506... | [2e60a77926](https://linux-hardware.org/?probe=2e60a77926) | Nov 14, 2023 |
| HP            | EliteBook 840 G2            | [74c6e6efae](https://linux-hardware.org/?probe=74c6e6efae) | Nov 13, 2023 |
| ASUSTek       | F3Sv                        | [7cc246f28e](https://linux-hardware.org/?probe=7cc246f28e) | Nov 13, 2023 |
| Apple         | MacBookPro5,5               | [87e3c4fa90](https://linux-hardware.org/?probe=87e3c4fa90) | Nov 12, 2023 |
| HP            | EliteBook 840 G4            | [2651393e60](https://linux-hardware.org/?probe=2651393e60) | Nov 12, 2023 |
| HP            | ZBook Firefly 14 inch G8... | [4fd542edf2](https://linux-hardware.org/?probe=4fd542edf2) | Nov 11, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [7d86488ec6](https://linux-hardware.org/?probe=7d86488ec6) | Nov 11, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | [cfc1427577](https://linux-hardware.org/?probe=cfc1427577) | Nov 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [60d38c4fae](https://linux-hardware.org/?probe=60d38c4fae) | Nov 09, 2023 |
| Lenovo        | ThinkPad X250 20CLAOMLIN    | [88967f98bd](https://linux-hardware.org/?probe=88967f98bd) | Nov 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [80431017dc](https://linux-hardware.org/?probe=80431017dc) | Nov 09, 2023 |
| Valve         | Jupiter                     | [2e7ed7b6c8](https://linux-hardware.org/?probe=2e7ed7b6c8) | Nov 09, 2023 |
| Notebook      | NJ50_70CU                   | [f48a185656](https://linux-hardware.org/?probe=f48a185656) | Nov 08, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [63e0b9fc88](https://linux-hardware.org/?probe=63e0b9fc88) | Nov 08, 2023 |
| Sony          | SVF15N17CXB                 | [e8497bf6f6](https://linux-hardware.org/?probe=e8497bf6f6) | Nov 08, 2023 |
| HP            | Laptop 15-rb0xx             | [3d2ec07a57](https://linux-hardware.org/?probe=3d2ec07a57) | Nov 08, 2023 |
| HP            | Laptop 15-rb0xx             | [eb27db3944](https://linux-hardware.org/?probe=eb27db3944) | Nov 08, 2023 |
| HP            | ZBook Studio G7 Mobile W... | [5cfd80c832](https://linux-hardware.org/?probe=5cfd80c832) | Nov 08, 2023 |
| HP            | ZBook Studio G7 Mobile W... | [675571ef30](https://linux-hardware.org/?probe=675571ef30) | Nov 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [da7463eff8](https://linux-hardware.org/?probe=da7463eff8) | Nov 07, 2023 |
| HP            | Laptop 15-ef2xxx            | [b0d207b140](https://linux-hardware.org/?probe=b0d207b140) | Nov 07, 2023 |
| Apple         | MacBookPro13,1              | [e5ae7e8a94](https://linux-hardware.org/?probe=e5ae7e8a94) | Nov 07, 2023 |
| Dell          | Vostro 3500                 | [c85bdae7e5](https://linux-hardware.org/?probe=c85bdae7e5) | Nov 07, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [e874ddf25c](https://linux-hardware.org/?probe=e874ddf25c) | Nov 07, 2023 |
| Dell          | Latitude E5470              | [19fc06d0b2](https://linux-hardware.org/?probe=19fc06d0b2) | Nov 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [ce00056643](https://linux-hardware.org/?probe=ce00056643) | Nov 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [0cc84d3b82](https://linux-hardware.org/?probe=0cc84d3b82) | Nov 07, 2023 |
| Samsung       | 550P5C/550P7C               | [c7d84926af](https://linux-hardware.org/?probe=c7d84926af) | Nov 07, 2023 |
| Acer          | Aspire A315-41              | [e275461ffe](https://linux-hardware.org/?probe=e275461ffe) | Nov 07, 2023 |
| ASUSTek       | X55A                        | [705bc0e6a5](https://linux-hardware.org/?probe=705bc0e6a5) | Nov 07, 2023 |
| Dell          | Precision M4600             | [0aabbcfa0b](https://linux-hardware.org/?probe=0aabbcfa0b) | Nov 06, 2023 |
| Lenovo        | ThinkPad T480s 20L7002HU... | [53fd99e067](https://linux-hardware.org/?probe=53fd99e067) | Nov 06, 2023 |
| Lenovo        | ThinkPad T480s 20L7002HU... | [d8adc9ee0d](https://linux-hardware.org/?probe=d8adc9ee0d) | Nov 06, 2023 |
| Dell          | XPS 15 9500                 | [e07422acdd](https://linux-hardware.org/?probe=e07422acdd) | Nov 06, 2023 |
| HP            | EliteBook 850 G3            | [dadc34f1bb](https://linux-hardware.org/?probe=dadc34f1bb) | Nov 06, 2023 |
| HP            | EliteBook 850 G3            | [b5b4c26e1e](https://linux-hardware.org/?probe=b5b4c26e1e) | Nov 06, 2023 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [a7c5843f17](https://linux-hardware.org/?probe=a7c5843f17) | Nov 06, 2023 |
| Timi          | Mi NoteBook Pro             | [a8a46eb495](https://linux-hardware.org/?probe=a8a46eb495) | Nov 06, 2023 |
| Lenovo        | ThinkPad E15 20RD0011IX     | [88cc97d0be](https://linux-hardware.org/?probe=88cc97d0be) | Nov 06, 2023 |
| Lenovo        | ThinkPad T480s 20L7002HU... | [f09ace6b9d](https://linux-hardware.org/?probe=f09ace6b9d) | Nov 06, 2023 |
| HP            | G61                         | [65f7664fe3](https://linux-hardware.org/?probe=65f7664fe3) | Nov 06, 2023 |
| Samsung       | 550P5C/550P7C               | [f87e3a97c4](https://linux-hardware.org/?probe=f87e3a97c4) | Nov 06, 2023 |
| Acer          | Aspire A315-53              | [3daa9909b3](https://linux-hardware.org/?probe=3daa9909b3) | Nov 06, 2023 |
| Dell          | Venue 11 Pro 5130           | [d643312744](https://linux-hardware.org/?probe=d643312744) | Nov 06, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [d61e270082](https://linux-hardware.org/?probe=d61e270082) | Nov 06, 2023 |
| ASUSTek       | X550WA                      | [8c15da796b](https://linux-hardware.org/?probe=8c15da796b) | Nov 05, 2023 |
| Lenovo        | ThinkPad T480s 20L7002HU... | [92ef56cc92](https://linux-hardware.org/?probe=92ef56cc92) | Nov 05, 2023 |
| Acer          | Predator PT516-52s          | [30b7a47643](https://linux-hardware.org/?probe=30b7a47643) | Nov 05, 2023 |
| Dell          | Inspiron 7559               | [da97d12548](https://linux-hardware.org/?probe=da97d12548) | Nov 05, 2023 |
| Toshiba       | Satellite L845              | [4dc7e8931e](https://linux-hardware.org/?probe=4dc7e8931e) | Nov 05, 2023 |
| Dell          | Latitude E7440              | [5a151e929f](https://linux-hardware.org/?probe=5a151e929f) | Nov 05, 2023 |
| Lenovo        | S145-15IWL 81MV             | [d38fdaf0eb](https://linux-hardware.org/?probe=d38fdaf0eb) | Nov 04, 2023 |
| Lenovo        | ThinkPad W550s 20E2000PM... | [1294d54c1a](https://linux-hardware.org/?probe=1294d54c1a) | Nov 04, 2023 |
| MSI           | Modern 15 B7M               | [b4a588e60e](https://linux-hardware.org/?probe=b4a588e60e) | Nov 04, 2023 |
| HP            | ProBook 430 G8 Notebook ... | [5d8cae0407](https://linux-hardware.org/?probe=5d8cae0407) | Nov 04, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [b390f8cd05](https://linux-hardware.org/?probe=b390f8cd05) | Nov 04, 2023 |
| Apple         | MacBook5,2                  | [1d8dad6600](https://linux-hardware.org/?probe=1d8dad6600) | Nov 04, 2023 |
| HP            | EliteBook 850 G5            | [a7f0f43604](https://linux-hardware.org/?probe=a7f0f43604) | Nov 04, 2023 |
| Sony          | VPCEH3J1E                   | [e0ae745034](https://linux-hardware.org/?probe=e0ae745034) | Nov 04, 2023 |
| Lenovo        | ThinkPad P16v Gen 1 21FE... | [d0d84fed9a](https://linux-hardware.org/?probe=d0d84fed9a) | Nov 04, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [85e528f1bf](https://linux-hardware.org/?probe=85e528f1bf) | Nov 04, 2023 |
| Dell          | Inspiron 15 3511            | [8c23fbf7d1](https://linux-hardware.org/?probe=8c23fbf7d1) | Nov 04, 2023 |
| POV           | I102A                       | [955f97d47e](https://linux-hardware.org/?probe=955f97d47e) | Nov 04, 2023 |
| Irbis         | NB211                       | [694ca0f127](https://linux-hardware.org/?probe=694ca0f127) | Nov 03, 2023 |
| HUAWEI        | KLVL-WXX9                   | [61342b31ea](https://linux-hardware.org/?probe=61342b31ea) | Nov 03, 2023 |
| HP            | Laptop 15-dy2xxx            | [f4bae2d5b5](https://linux-hardware.org/?probe=f4bae2d5b5) | Nov 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [ff0d013246](https://linux-hardware.org/?probe=ff0d013246) | Nov 03, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [f9bdbf6371](https://linux-hardware.org/?probe=f9bdbf6371) | Nov 03, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [bcea72b22f](https://linux-hardware.org/?probe=bcea72b22f) | Nov 03, 2023 |
| Lenovo        | ThinkPad T470s 20HF0047U... | [00a8b74f46](https://linux-hardware.org/?probe=00a8b74f46) | Nov 03, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D3S... | [6a2591b5e9](https://linux-hardware.org/?probe=6a2591b5e9) | Nov 03, 2023 |
| HP            | Laptop 15-dy2xxx            | [28990f206a](https://linux-hardware.org/?probe=28990f206a) | Nov 03, 2023 |
| Irbis         | NB211                       | [3ebca4338a](https://linux-hardware.org/?probe=3ebca4338a) | Nov 03, 2023 |
| HP            | Pavilion Notebook           | [f23e44229f](https://linux-hardware.org/?probe=f23e44229f) | Nov 03, 2023 |
| HP            | Stream Laptop 11-ah1XX      | [94cdd979b2](https://linux-hardware.org/?probe=94cdd979b2) | Nov 03, 2023 |
| Fujitsu       | LIFEBOOK A3510              | [0929326be0](https://linux-hardware.org/?probe=0929326be0) | Nov 03, 2023 |
| HP            | Stream Laptop 11-ah1XX      | [5149df3a58](https://linux-hardware.org/?probe=5149df3a58) | Nov 03, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [26bc5f025c](https://linux-hardware.org/?probe=26bc5f025c) | Nov 02, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [741bcd1343](https://linux-hardware.org/?probe=741bcd1343) | Nov 02, 2023 |
| Lenovo        | ThinkPad T400 2768BB1       | [56bbf7c0bb](https://linux-hardware.org/?probe=56bbf7c0bb) | Nov 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [bb1da2575d](https://linux-hardware.org/?probe=bb1da2575d) | Nov 02, 2023 |
| Lenovo        | ThinkBook Plus G3 IAP 21... | [c6634f090f](https://linux-hardware.org/?probe=c6634f090f) | Nov 02, 2023 |
| Acer          | Aspire A715-41G             | [664191098d](https://linux-hardware.org/?probe=664191098d) | Nov 02, 2023 |
| HUAWEI        | BOM-WXX9                    | [97ca7a0bfd](https://linux-hardware.org/?probe=97ca7a0bfd) | Nov 02, 2023 |
| HP            | ProBook 650 G1              | [60c6e3a5d2](https://linux-hardware.org/?probe=60c6e3a5d2) | Nov 01, 2023 |
| Dell          | G3 3579                     | [0b33f63284](https://linux-hardware.org/?probe=0b33f63284) | Nov 01, 2023 |
| Acer          | TravelMate P259-MG          | [ba3faece8c](https://linux-hardware.org/?probe=ba3faece8c) | Nov 01, 2023 |
| HP            | Laptop 15s-eq2xxx           | [685b1b18eb](https://linux-hardware.org/?probe=685b1b18eb) | Nov 01, 2023 |
| Acer          | Nitro AN515-52              | [829c16d044](https://linux-hardware.org/?probe=829c16d044) | Nov 01, 2023 |
| Apple         | MacBookPro16,2              | [37b53d54e8](https://linux-hardware.org/?probe=37b53d54e8) | Nov 01, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | [bbf2002cea](https://linux-hardware.org/?probe=bbf2002cea) | Nov 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [7dd972fb0d](https://linux-hardware.org/?probe=7dd972fb0d) | Nov 01, 2023 |
| Acer          | Aspire A715-41G             | [63fa5e90b2](https://linux-hardware.org/?probe=63fa5e90b2) | Nov 01, 2023 |
| Apple         | MacBookPro15,2              | [b724e20965](https://linux-hardware.org/?probe=b724e20965) | Nov 01, 2023 |
| HP            | Laptop 15-fc0xxx            | [d0be3aec4e](https://linux-hardware.org/?probe=d0be3aec4e) | Nov 01, 2023 |
| ASUSTek       | X555QG                      | [f047c1d264](https://linux-hardware.org/?probe=f047c1d264) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21HDC... | [0d9316dbcf](https://linux-hardware.org/?probe=0d9316dbcf) | Oct 31, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [aef3dccca0](https://linux-hardware.org/?probe=aef3dccca0) | Oct 31, 2023 |
| Alienware     | 14                          | [e88b7c0ac6](https://linux-hardware.org/?probe=e88b7c0ac6) | Oct 31, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | [af854a07c5](https://linux-hardware.org/?probe=af854a07c5) | Oct 31, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | [fadc897ee2](https://linux-hardware.org/?probe=fadc897ee2) | Oct 31, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | [ebec8d6fd1](https://linux-hardware.org/?probe=ebec8d6fd1) | Oct 31, 2023 |
| Apple         | MacBookPro8,1               | [0ea1a71a53](https://linux-hardware.org/?probe=0ea1a71a53) | Oct 31, 2023 |
| Lenovo        | ThinkPad T490 20N2S0QE00    | [9785ae64c0](https://linux-hardware.org/?probe=9785ae64c0) | Oct 31, 2023 |
| Lenovo        | ThinkPad E470 20H1006KIX    | [d84959fadc](https://linux-hardware.org/?probe=d84959fadc) | Oct 31, 2023 |
| HP            | ProBook 645 G1              | [b637cedab4](https://linux-hardware.org/?probe=b637cedab4) | Oct 31, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [54a64f0a7e](https://linux-hardware.org/?probe=54a64f0a7e) | Oct 31, 2023 |
| Dell          | Latitude 5414               | [fd7b086e1b](https://linux-hardware.org/?probe=fd7b086e1b) | Oct 31, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | [487222ef3e](https://linux-hardware.org/?probe=487222ef3e) | Oct 31, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [055e34b095](https://linux-hardware.org/?probe=055e34b095) | Oct 30, 2023 |
| Acer          | Aspire A515-45              | [25431e9c91](https://linux-hardware.org/?probe=25431e9c91) | Oct 30, 2023 |
| ASUSTek       | X555UJ                      | [de6e2775a4](https://linux-hardware.org/?probe=de6e2775a4) | Oct 30, 2023 |
| Lenovo        | ThinkPad T440 20B7S03Q00    | [de24032ac7](https://linux-hardware.org/?probe=de24032ac7) | Oct 30, 2023 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [0b129d4a95](https://linux-hardware.org/?probe=0b129d4a95) | Oct 30, 2023 |
| Dell          | Vostro 3525                 | [ad34d5b54f](https://linux-hardware.org/?probe=ad34d5b54f) | Oct 30, 2023 |
| Dell          | Latitude 5490               | [63f4fce332](https://linux-hardware.org/?probe=63f4fce332) | Oct 30, 2023 |
| Lenovo        | ThinkPad T400 2768BB1       | [249ea48334](https://linux-hardware.org/?probe=249ea48334) | Oct 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [6cbfd91e78](https://linux-hardware.org/?probe=6cbfd91e78) | Oct 30, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D3S... | [8730c3de9d](https://linux-hardware.org/?probe=8730c3de9d) | Oct 30, 2023 |
| Dell          | Precision 3551              | [4f054a63ef](https://linux-hardware.org/?probe=4f054a63ef) | Oct 30, 2023 |
| ASUSTek       | F3Sv                        | [3da2894228](https://linux-hardware.org/?probe=3da2894228) | Oct 30, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [b1adeb2f86](https://linux-hardware.org/?probe=b1adeb2f86) | Oct 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [fe7dbb2385](https://linux-hardware.org/?probe=fe7dbb2385) | Oct 29, 2023 |
| Apple         | MacBookPro15,4              | [09ee918b60](https://linux-hardware.org/?probe=09ee918b60) | Oct 29, 2023 |
| HP            | Notebook                    | [79843ed7c3](https://linux-hardware.org/?probe=79843ed7c3) | Oct 29, 2023 |
| Dell          | Precision 5480              | [5df408828c](https://linux-hardware.org/?probe=5df408828c) | Oct 29, 2023 |
| Dell          | Precision M6800             | [a5e2100522](https://linux-hardware.org/?probe=a5e2100522) | Oct 29, 2023 |
| Lenovo        | ThinkPad E14 20RA0020AU     | [1d1a7bd472](https://linux-hardware.org/?probe=1d1a7bd472) | Oct 28, 2023 |
| Thomson       | N14C4WH64                   | [8dd9b1dbde](https://linux-hardware.org/?probe=8dd9b1dbde) | Oct 28, 2023 |
| HP            | Pavilion Laptop 15-cc6xx    | [da25874b12](https://linux-hardware.org/?probe=da25874b12) | Oct 28, 2023 |
| Apple         | MacBookPro8,1               | [762e9a6d4d](https://linux-hardware.org/?probe=762e9a6d4d) | Oct 28, 2023 |
| Apple         | MacBookPro8,1               | [b4645667a4](https://linux-hardware.org/?probe=b4645667a4) | Oct 28, 2023 |
| HP            | Notebook                    | [791dfef3cc](https://linux-hardware.org/?probe=791dfef3cc) | Oct 28, 2023 |
| HUAWEI        | CREM-WXX9                   | [217aaa00da](https://linux-hardware.org/?probe=217aaa00da) | Oct 28, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | [f78fcbc612](https://linux-hardware.org/?probe=f78fcbc612) | Oct 28, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [5591930fc0](https://linux-hardware.org/?probe=5591930fc0) | Oct 27, 2023 |
| Lenovo        | YogaAir 14s APU8 83AA       | [4f120347b7](https://linux-hardware.org/?probe=4f120347b7) | Oct 27, 2023 |
| Dell          | Precision 5530              | [e707fe59cc](https://linux-hardware.org/?probe=e707fe59cc) | Oct 27, 2023 |
| Acer          | Aspire V5-572P              | [18938afb70](https://linux-hardware.org/?probe=18938afb70) | Oct 27, 2023 |
| HP            | ZBook Firefly 14 inch G8... | [bd82dd57be](https://linux-hardware.org/?probe=bd82dd57be) | Oct 27, 2023 |
| Lenovo        | ThinkPad T480 20L6S69X08    | [61da163866](https://linux-hardware.org/?probe=61da163866) | Oct 27, 2023 |
| Apple         | MacBookPro14,2              | [346fad17ff](https://linux-hardware.org/?probe=346fad17ff) | Oct 27, 2023 |
| Apple         | MacBookPro14,2              | [481d6c83fb](https://linux-hardware.org/?probe=481d6c83fb) | Oct 27, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | [057e350f82](https://linux-hardware.org/?probe=057e350f82) | Oct 27, 2023 |
| Lenovo        | IdeaPad 1 15IAU7 82QD       | [a20c6e2c77](https://linux-hardware.org/?probe=a20c6e2c77) | Oct 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [9650e62539](https://linux-hardware.org/?probe=9650e62539) | Oct 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [82ba56a70d](https://linux-hardware.org/?probe=82ba56a70d) | Oct 26, 2023 |
| Dell          | Latitude 5440               | [e7d56ee207](https://linux-hardware.org/?probe=e7d56ee207) | Oct 26, 2023 |
| Dell          | Latitude 7490               | [58324a8dfd](https://linux-hardware.org/?probe=58324a8dfd) | Oct 26, 2023 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [3aa43f0bf7](https://linux-hardware.org/?probe=3aa43f0bf7) | Oct 26, 2023 |
| Maibenben     | MaiBook M                   | [ccee3b60c7](https://linux-hardware.org/?probe=ccee3b60c7) | Oct 26, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [4506629e6a](https://linux-hardware.org/?probe=4506629e6a) | Oct 26, 2023 |
| Toshiba       | Satellite L75D-A            | [82efb2dd44](https://linux-hardware.org/?probe=82efb2dd44) | Oct 26, 2023 |
| Apple         | MacBookPro15,4              | [751e98cb04](https://linux-hardware.org/?probe=751e98cb04) | Oct 26, 2023 |
| Schenker      | VISION (M23)                | [64cead24ba](https://linux-hardware.org/?probe=64cead24ba) | Oct 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [a17a8b4360](https://linux-hardware.org/?probe=a17a8b4360) | Oct 25, 2023 |
| Acer          | Aspire 7750G                | [673c675bc6](https://linux-hardware.org/?probe=673c675bc6) | Oct 25, 2023 |
| Timi          | TM1701                      | [13801c83a2](https://linux-hardware.org/?probe=13801c83a2) | Oct 25, 2023 |
| Lenovo        | IdeaPadFlex 15 20309        | [7476940ad0](https://linux-hardware.org/?probe=7476940ad0) | Oct 25, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [3eee01cd16](https://linux-hardware.org/?probe=3eee01cd16) | Oct 24, 2023 |
| Lenovo        | ThinkPad T410 2537NT8       | [52b5addead](https://linux-hardware.org/?probe=52b5addead) | Oct 24, 2023 |
| Dell          | XPS 9315                    | [9246bb9a28](https://linux-hardware.org/?probe=9246bb9a28) | Oct 24, 2023 |
| Apple         | MacBookPro15,1              | [41fd350f12](https://linux-hardware.org/?probe=41fd350f12) | Oct 24, 2023 |
| Apple         | MacBookPro5,5               | [ed7e1a1932](https://linux-hardware.org/?probe=ed7e1a1932) | Oct 24, 2023 |
| Lenovo        | ThinkPad T430 2349UA9       | [84883d560d](https://linux-hardware.org/?probe=84883d560d) | Oct 24, 2023 |
| GPD           | G1621-02                    | [ea3897be17](https://linux-hardware.org/?probe=ea3897be17) | Oct 24, 2023 |
| Apple         | MacBookPro5,5               | [37be8caf53](https://linux-hardware.org/?probe=37be8caf53) | Oct 23, 2023 |
| Dell          | Latitude 5320               | [520c2effa3](https://linux-hardware.org/?probe=520c2effa3) | Oct 23, 2023 |
| Schenker      | XMG NEO (TGL/M21)           | [6d63f6c5ba](https://linux-hardware.org/?probe=6d63f6c5ba) | Oct 23, 2023 |
| TUXEDO        | Unknown                     | [0994b60ab4](https://linux-hardware.org/?probe=0994b60ab4) | Oct 23, 2023 |
| Dell          | G15 5515                    | [16754901cb](https://linux-hardware.org/?probe=16754901cb) | Oct 23, 2023 |
| HP            | ProBook 4530s               | [104df79d8e](https://linux-hardware.org/?probe=104df79d8e) | Oct 23, 2023 |
| Lenovo        | ThinkPad T480s 20L8S2SS0... | [9877bb17c1](https://linux-hardware.org/?probe=9877bb17c1) | Oct 23, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [2e4786bb32](https://linux-hardware.org/?probe=2e4786bb32) | Oct 23, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [7981b12a61](https://linux-hardware.org/?probe=7981b12a61) | Oct 22, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [705aaea029](https://linux-hardware.org/?probe=705aaea029) | Oct 22, 2023 |
| Dell          | XPS 13 9300                 | [ccf935ca37](https://linux-hardware.org/?probe=ccf935ca37) | Oct 22, 2023 |
| HP            | ENVY Laptop 13-ba0xxx       | [38823c0a55](https://linux-hardware.org/?probe=38823c0a55) | Oct 22, 2023 |
| Lenovo        | ThinkPad L13 20R30005RT     | [23a9651432](https://linux-hardware.org/?probe=23a9651432) | Oct 22, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | [c725f222a3](https://linux-hardware.org/?probe=c725f222a3) | Oct 22, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [92d3be3fff](https://linux-hardware.org/?probe=92d3be3fff) | Oct 22, 2023 |
| Dell          | Venue 11 Pro 5130           | [7105618a0a](https://linux-hardware.org/?probe=7105618a0a) | Oct 22, 2023 |
| Dell          | Venue 11 Pro 5130           | [0b91bab038](https://linux-hardware.org/?probe=0b91bab038) | Oct 22, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [1eed0a53b6](https://linux-hardware.org/?probe=1eed0a53b6) | Oct 22, 2023 |
| Apple         | MacBookPro12,1              | [5d9310d00e](https://linux-hardware.org/?probe=5d9310d00e) | Oct 21, 2023 |
| ASUSTek       | N551JK                      | [863f309154](https://linux-hardware.org/?probe=863f309154) | Oct 21, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [1f4b7f796f](https://linux-hardware.org/?probe=1f4b7f796f) | Oct 21, 2023 |
| Apple         | MacBookAir4,2               | [dcef0a70af](https://linux-hardware.org/?probe=dcef0a70af) | Oct 21, 2023 |
| Dell          | Latitude E6320              | [c6965e07e3](https://linux-hardware.org/?probe=c6965e07e3) | Oct 21, 2023 |
| HP            | Pavilion Notebook           | [ffeaa7da2f](https://linux-hardware.org/?probe=ffeaa7da2f) | Oct 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [f1b2f555ef](https://linux-hardware.org/?probe=f1b2f555ef) | Oct 21, 2023 |
| Schenker      | XMG NEO (TGL/M21)           | [3afdd1b0da](https://linux-hardware.org/?probe=3afdd1b0da) | Oct 21, 2023 |
| Lenovo        | ThinkPad T540p 20BE0086M... | [a149fbf417](https://linux-hardware.org/?probe=a149fbf417) | Oct 21, 2023 |
| ASUSTek       | X442UAR                     | [454f454638](https://linux-hardware.org/?probe=454f454638) | Oct 21, 2023 |
| Dell          | Latitude 7440               | [e0997ac78c](https://linux-hardware.org/?probe=e0997ac78c) | Oct 20, 2023 |
| Lenovo        | ThinkPad T540p 20BE0086M... | [f4f7d19069](https://linux-hardware.org/?probe=f4f7d19069) | Oct 20, 2023 |
| BANGHO        | M7x0K                       | [1f72eb6b91](https://linux-hardware.org/?probe=1f72eb6b91) | Oct 20, 2023 |
| Dell          | Vostro 14 5410              | [4cb4e5aab9](https://linux-hardware.org/?probe=4cb4e5aab9) | Oct 20, 2023 |
| Dell          | Latitude 7280               | [ec9e688b4e](https://linux-hardware.org/?probe=ec9e688b4e) | Oct 20, 2023 |
| HP            | Pavilion Notebook           | [9d49844572](https://linux-hardware.org/?probe=9d49844572) | Oct 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [aa76e46b18](https://linux-hardware.org/?probe=aa76e46b18) | Oct 20, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [32d375b029](https://linux-hardware.org/?probe=32d375b029) | Oct 20, 2023 |
| Lenovo        | G500 20236                  | [6e5d214cb8](https://linux-hardware.org/?probe=6e5d214cb8) | Oct 20, 2023 |
| ASUSTek       | Zephyrus M GU502GW_GU502... | [c96f9ccef3](https://linux-hardware.org/?probe=c96f9ccef3) | Oct 19, 2023 |
| Toshiba       | Satellite A500              | [15b78585e0](https://linux-hardware.org/?probe=15b78585e0) | Oct 19, 2023 |
| HP            | ProBook 445 G7              | [10fab445ad](https://linux-hardware.org/?probe=10fab445ad) | Oct 19, 2023 |
| Toshiba       | Satellite A500              | [0d2e2856a9](https://linux-hardware.org/?probe=0d2e2856a9) | Oct 19, 2023 |
| ASUSTek       | PRIME X570-P                | [4506612f98](https://linux-hardware.org/?probe=4506612f98) | Oct 19, 2023 |
| Acer          | Aspire A315-57G             | [7e39a647e3](https://linux-hardware.org/?probe=7e39a647e3) | Oct 19, 2023 |
| ASUSTek       | X555QG                      | [e2e11a852f](https://linux-hardware.org/?probe=e2e11a852f) | Oct 19, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [8d38f6e16d](https://linux-hardware.org/?probe=8d38f6e16d) | Oct 19, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [fbb4ce606d](https://linux-hardware.org/?probe=fbb4ce606d) | Oct 19, 2023 |
| Lenovo        | G50-80 80E5                 | [1f244ed949](https://linux-hardware.org/?probe=1f244ed949) | Oct 19, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [e94e48868c](https://linux-hardware.org/?probe=e94e48868c) | Oct 19, 2023 |
| Lenovo        | G450 2949                   | [abafeadb35](https://linux-hardware.org/?probe=abafeadb35) | Oct 19, 2023 |
| Lenovo        | G450 2949                   | [ab3c18427d](https://linux-hardware.org/?probe=ab3c18427d) | Oct 19, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [a25bc084fc](https://linux-hardware.org/?probe=a25bc084fc) | Oct 19, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [4d4e3d82fd](https://linux-hardware.org/?probe=4d4e3d82fd) | Oct 18, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [1984a8305d](https://linux-hardware.org/?probe=1984a8305d) | Oct 18, 2023 |
| HP            | EliteBook 860 16 inch G1... | [bde071302f](https://linux-hardware.org/?probe=bde071302f) | Oct 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [48b90d30be](https://linux-hardware.org/?probe=48b90d30be) | Oct 18, 2023 |
| Dell          | Precision 7680              | [70f6453d4c](https://linux-hardware.org/?probe=70f6453d4c) | Oct 18, 2023 |
| Dell          | XPS 13 9360                 | [dbbedd9f06](https://linux-hardware.org/?probe=dbbedd9f06) | Oct 18, 2023 |
| Samsung       | 670Z5E                      | [65ee0747bc](https://linux-hardware.org/?probe=65ee0747bc) | Oct 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [04885ecaa3](https://linux-hardware.org/?probe=04885ecaa3) | Oct 18, 2023 |
| Lenovo        | ThinkPad T480s 20L8002AM... | [b8d09ca2f5](https://linux-hardware.org/?probe=b8d09ca2f5) | Oct 18, 2023 |
| Dell          | Latitude 5440               | [2097e4ed5e](https://linux-hardware.org/?probe=2097e4ed5e) | Oct 18, 2023 |
| ASUSTek       | X556UJ                      | [010c7b3e14](https://linux-hardware.org/?probe=010c7b3e14) | Oct 17, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ARH7 8... | [6193aa3ed1](https://linux-hardware.org/?probe=6193aa3ed1) | Oct 17, 2023 |
| ASUSTek       | X556UJ                      | [e9065ad0d2](https://linux-hardware.org/?probe=e9065ad0d2) | Oct 17, 2023 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | [4d69a046ff](https://linux-hardware.org/?probe=4d69a046ff) | Oct 17, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [660d60e1a8](https://linux-hardware.org/?probe=660d60e1a8) | Oct 17, 2023 |
| HUAWEI        | MACH-WX9                    | [8cb8d0943c](https://linux-hardware.org/?probe=8cb8d0943c) | Oct 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [0b4065c185](https://linux-hardware.org/?probe=0b4065c185) | Oct 17, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [6f1f662d3a](https://linux-hardware.org/?probe=6f1f662d3a) | Oct 17, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [8b92e44d64](https://linux-hardware.org/?probe=8b92e44d64) | Oct 17, 2023 |
| Lenovo        | ThinkPad T480 20L6S69X08    | [efc4ad7803](https://linux-hardware.org/?probe=efc4ad7803) | Oct 17, 2023 |
| Lenovo        | E41-50 82HW                 | [f31f632ea0](https://linux-hardware.org/?probe=f31f632ea0) | Oct 17, 2023 |
| MSI           | Prestige 14H B12UCX         | [81dac6f109](https://linux-hardware.org/?probe=81dac6f109) | Oct 17, 2023 |
| Positivo B... | VJFE42F11X-XXXXXX           | [d271c61b92](https://linux-hardware.org/?probe=d271c61b92) | Oct 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [d14e5830b2](https://linux-hardware.org/?probe=d14e5830b2) | Oct 16, 2023 |
| Dell          | Vostro 14 5410              | [219d504a89](https://linux-hardware.org/?probe=219d504a89) | Oct 16, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [73e2838408](https://linux-hardware.org/?probe=73e2838408) | Oct 16, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [5651db5e36](https://linux-hardware.org/?probe=5651db5e36) | Oct 16, 2023 |
| HP            | Notebook                    | [44730825fa](https://linux-hardware.org/?probe=44730825fa) | Oct 16, 2023 |
| GLM           | 14-Z8350-C                  | [2db6571799](https://linux-hardware.org/?probe=2db6571799) | Oct 15, 2023 |
| HUAWEI        | MACH-WX9                    | [19ec3283fc](https://linux-hardware.org/?probe=19ec3283fc) | Oct 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [8c4e60d5ca](https://linux-hardware.org/?probe=8c4e60d5ca) | Oct 15, 2023 |
| Lenovo        | ThinkPad T430s 2352CTO      | [1a38144f94](https://linux-hardware.org/?probe=1a38144f94) | Oct 15, 2023 |
| Dell          | Latitude 5591               | [ef0287bbad](https://linux-hardware.org/?probe=ef0287bbad) | Oct 15, 2023 |
| Gigabyte      | G7 GD                       | [667243780c](https://linux-hardware.org/?probe=667243780c) | Oct 15, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [85e073cb44](https://linux-hardware.org/?probe=85e073cb44) | Oct 15, 2023 |
| Acer          | Aspire VN7-592G             | [13b64fc9bd](https://linux-hardware.org/?probe=13b64fc9bd) | Oct 15, 2023 |
| HP            | Laptop 15-dy2xxx            | [5079c96f33](https://linux-hardware.org/?probe=5079c96f33) | Oct 15, 2023 |
| Toshiba       | Satellite CL10-C-102        | [cdaab4e230](https://linux-hardware.org/?probe=cdaab4e230) | Oct 15, 2023 |
| MSI           | Prestige 14H B12UCX         | [ddc0082c22](https://linux-hardware.org/?probe=ddc0082c22) | Oct 14, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [4b4d5899fa](https://linux-hardware.org/?probe=4b4d5899fa) | Oct 14, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [d68359ee50](https://linux-hardware.org/?probe=d68359ee50) | Oct 14, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [11d91a0246](https://linux-hardware.org/?probe=11d91a0246) | Oct 14, 2023 |
| Dell          | XPS 9320                    | [21de4b869f](https://linux-hardware.org/?probe=21de4b869f) | Oct 14, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [1215db6b88](https://linux-hardware.org/?probe=1215db6b88) | Oct 13, 2023 |
| Google        | Morphius                    | [fd4be61654](https://linux-hardware.org/?probe=fd4be61654) | Oct 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [3a6c620560](https://linux-hardware.org/?probe=3a6c620560) | Oct 13, 2023 |
| Dell          | Precision 7520              | [e9cb628c83](https://linux-hardware.org/?probe=e9cb628c83) | Oct 13, 2023 |
| Framework     | Laptop                      | [760f431061](https://linux-hardware.org/?probe=760f431061) | Oct 13, 2023 |
| Dell          | Precision 3580              | [f2a080ed43](https://linux-hardware.org/?probe=f2a080ed43) | Oct 13, 2023 |
| Apple         | MacBookPro11,3              | [1c1d7152a3](https://linux-hardware.org/?probe=1c1d7152a3) | Oct 13, 2023 |
| Lenovo        | ThinkPad P53 20QN20VZZC     | [4485ad6d0b](https://linux-hardware.org/?probe=4485ad6d0b) | Oct 13, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [a4dfa6f17f](https://linux-hardware.org/?probe=a4dfa6f17f) | Oct 13, 2023 |
| MSI           | Prestige 14H B12UCX         | [63a132c897](https://linux-hardware.org/?probe=63a132c897) | Oct 13, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [d268453669](https://linux-hardware.org/?probe=d268453669) | Oct 13, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [17b0ef31ee](https://linux-hardware.org/?probe=17b0ef31ee) | Oct 13, 2023 |
| HP            | G61                         | [34e955886e](https://linux-hardware.org/?probe=34e955886e) | Oct 13, 2023 |
| Dell          | Precision M4700             | [1c10565d3f](https://linux-hardware.org/?probe=1c10565d3f) | Oct 13, 2023 |
| Dell          | Precision 7520              | [de5b9c8fa1](https://linux-hardware.org/?probe=de5b9c8fa1) | Oct 13, 2023 |
| Acer          | Nitro AN515-44              | [1f1524c080](https://linux-hardware.org/?probe=1f1524c080) | Oct 13, 2023 |
| Dell          | Latitude 7430               | [fb8c320433](https://linux-hardware.org/?probe=fb8c320433) | Oct 13, 2023 |
| Dell          | Inspiron N5110              | [92726caa44](https://linux-hardware.org/?probe=92726caa44) | Oct 12, 2023 |
| Dell          | Latitude 3490               | [1c5aa8fca4](https://linux-hardware.org/?probe=1c5aa8fca4) | Oct 12, 2023 |
| Infinix       | ZERO BOOK 13                | [c20c04a240](https://linux-hardware.org/?probe=c20c04a240) | Oct 12, 2023 |
| MSI           | Modern 15 A11M              | [33272a00fb](https://linux-hardware.org/?probe=33272a00fb) | Oct 12, 2023 |
| Dell          | XPS 9320                    | [33d6205766](https://linux-hardware.org/?probe=33d6205766) | Oct 12, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [6396467c6d](https://linux-hardware.org/?probe=6396467c6d) | Oct 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS29Y0... | [18b3c9fef8](https://linux-hardware.org/?probe=18b3c9fef8) | Oct 12, 2023 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | [87e16d607b](https://linux-hardware.org/?probe=87e16d607b) | Oct 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS29Y0... | [7c843b4c27](https://linux-hardware.org/?probe=7c843b4c27) | Oct 12, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [cc8062e568](https://linux-hardware.org/?probe=cc8062e568) | Oct 12, 2023 |
| HP            | EliteBook 840 G6 HC         | [e1b3f5dbeb](https://linux-hardware.org/?probe=e1b3f5dbeb) | Oct 11, 2023 |
| Lenovo        | LOQ 15IRH8 82XV             | [3fe12fb88e](https://linux-hardware.org/?probe=3fe12fb88e) | Oct 11, 2023 |
| MSI           | PS42 Modern 8MO             | [be9a0659d4](https://linux-hardware.org/?probe=be9a0659d4) | Oct 11, 2023 |
| Lenovo        | ThinkPad P53 20QN20VZZC     | [2659f02d19](https://linux-hardware.org/?probe=2659f02d19) | Oct 11, 2023 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [d7d6c74d55](https://linux-hardware.org/?probe=d7d6c74d55) | Oct 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [ea3f6440b2](https://linux-hardware.org/?probe=ea3f6440b2) | Oct 11, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [7aeb935c28](https://linux-hardware.org/?probe=7aeb935c28) | Oct 11, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | [3d389cfbfa](https://linux-hardware.org/?probe=3d389cfbfa) | Oct 11, 2023 |
| Avell High... | B.ON                        | [3a419fbd20](https://linux-hardware.org/?probe=3a419fbd20) | Oct 11, 2023 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [e06a4e6c13](https://linux-hardware.org/?probe=e06a4e6c13) | Oct 11, 2023 |
| Dell          | Precision 3571              | [ac3735cea4](https://linux-hardware.org/?probe=ac3735cea4) | Oct 11, 2023 |
| HP            | 240 G5 Notebook PC          | [22f4ada2e9](https://linux-hardware.org/?probe=22f4ada2e9) | Oct 10, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [50682769d9](https://linux-hardware.org/?probe=50682769d9) | Oct 10, 2023 |
| Apple         | MacBookPro12,1              | [9de05646a3](https://linux-hardware.org/?probe=9de05646a3) | Oct 10, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [162889c4a3](https://linux-hardware.org/?probe=162889c4a3) | Oct 10, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [47ba0bddd0](https://linux-hardware.org/?probe=47ba0bddd0) | Oct 10, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [28a78b32e5](https://linux-hardware.org/?probe=28a78b32e5) | Oct 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [7d759c245f](https://linux-hardware.org/?probe=7d759c245f) | Oct 10, 2023 |
| Teclast       | F7S                         | [92c51af32a](https://linux-hardware.org/?probe=92c51af32a) | Oct 10, 2023 |
| Notebook      | PCx0Dx                      | [9e8bfb1d9e](https://linux-hardware.org/?probe=9e8bfb1d9e) | Oct 09, 2023 |
| Lenovo        | ThinkPad T490 20N3S8HL00    | [e75ca9bf06](https://linux-hardware.org/?probe=e75ca9bf06) | Oct 09, 2023 |
| Dell          | Vostro 3700                 | [5776334e3a](https://linux-hardware.org/?probe=5776334e3a) | Oct 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [749e1a7e28](https://linux-hardware.org/?probe=749e1a7e28) | Oct 09, 2023 |
| Acer          | Predator PH315-51           | [265a8e5346](https://linux-hardware.org/?probe=265a8e5346) | Oct 09, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [f269e7a6ee](https://linux-hardware.org/?probe=f269e7a6ee) | Oct 09, 2023 |
| MSI           | Summit E16Flip A12UCT       | [882d0daf54](https://linux-hardware.org/?probe=882d0daf54) | Oct 09, 2023 |
| Google        | Lindar                      | [75852e1ad7](https://linux-hardware.org/?probe=75852e1ad7) | Oct 08, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [d400853f78](https://linux-hardware.org/?probe=d400853f78) | Oct 08, 2023 |
| HP            | 240 G5 Notebook PC          | [db5dd15d83](https://linux-hardware.org/?probe=db5dd15d83) | Oct 08, 2023 |
| Dell          | Inspiron 14 5410            | [5f69a24978](https://linux-hardware.org/?probe=5f69a24978) | Oct 08, 2023 |
| Acer          | Nitro AN515-58              | [907f3a4cf1](https://linux-hardware.org/?probe=907f3a4cf1) | Oct 08, 2023 |
| Acer          | Nitro AN515-58              | [d003fa7343](https://linux-hardware.org/?probe=d003fa7343) | Oct 08, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [173accc37f](https://linux-hardware.org/?probe=173accc37f) | Oct 08, 2023 |
| Dell          | Inspiron 16 Plus 7630       | [51571d43df](https://linux-hardware.org/?probe=51571d43df) | Oct 07, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | [bad231ff7d](https://linux-hardware.org/?probe=bad231ff7d) | Oct 07, 2023 |
| Samsung       | 960XFH                      | [0d8aca1f6e](https://linux-hardware.org/?probe=0d8aca1f6e) | Oct 07, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | [eac5ec9d19](https://linux-hardware.org/?probe=eac5ec9d19) | Oct 07, 2023 |
| Samsung       | 960XFH                      | [a2138fa3f8](https://linux-hardware.org/?probe=a2138fa3f8) | Oct 07, 2023 |
| HP            | ProBook 455 15.6 inch G9... | [3c93fdc206](https://linux-hardware.org/?probe=3c93fdc206) | Oct 07, 2023 |
| Framework     | Laptop                      | [92ced4e3c6](https://linux-hardware.org/?probe=92ced4e3c6) | Oct 07, 2023 |
| Lenovo        | IdeaPad 320-14IKB 80XK      | [2adab9deb5](https://linux-hardware.org/?probe=2adab9deb5) | Oct 07, 2023 |
| Dell          | Latitude 3490               | [723d6797ae](https://linux-hardware.org/?probe=723d6797ae) | Oct 07, 2023 |
| VANT          | MOOVE14_2023                | [d9379b5405](https://linux-hardware.org/?probe=d9379b5405) | Oct 06, 2023 |
| Lenovo        | G400 20235                  | [4f9d192833](https://linux-hardware.org/?probe=4f9d192833) | Oct 06, 2023 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | [c5c7ad01ed](https://linux-hardware.org/?probe=c5c7ad01ed) | Oct 06, 2023 |
| Lenovo        | Mullins-LarneML             | [73b6f496a3](https://linux-hardware.org/?probe=73b6f496a3) | Oct 06, 2023 |
| HP            | Notebook                    | [be54658252](https://linux-hardware.org/?probe=be54658252) | Oct 06, 2023 |
| HP            | Notebook                    | [02dae8739a](https://linux-hardware.org/?probe=02dae8739a) | Oct 06, 2023 |
| HP            | EliteBook 840 G6            | [e8ae378997](https://linux-hardware.org/?probe=e8ae378997) | Oct 06, 2023 |
| HP            | EliteBook 735 G5            | [108728a0b6](https://linux-hardware.org/?probe=108728a0b6) | Oct 06, 2023 |
| HP            | Laptop 17-bs0xx             | [0b9d1772cd](https://linux-hardware.org/?probe=0b9d1772cd) | Oct 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [676106fbb7](https://linux-hardware.org/?probe=676106fbb7) | Oct 06, 2023 |
| Razer         | Blade 15 Base Model (Lat... | [8ae84cb1dc](https://linux-hardware.org/?probe=8ae84cb1dc) | Oct 05, 2023 |
| Dell          | Precision 5480              | [3a87c7a065](https://linux-hardware.org/?probe=3a87c7a065) | Oct 05, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [bfe115219f](https://linux-hardware.org/?probe=bfe115219f) | Oct 05, 2023 |
| Acer          | Aspire A314-23P             | [2ed7997cfe](https://linux-hardware.org/?probe=2ed7997cfe) | Oct 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [01f88bafa7](https://linux-hardware.org/?probe=01f88bafa7) | Oct 05, 2023 |
| Google        | Magpie                      | [91fa583b13](https://linux-hardware.org/?probe=91fa583b13) | Oct 05, 2023 |
| HP            | EliteBook 655 15.6 inch ... | [7b888eeb58](https://linux-hardware.org/?probe=7b888eeb58) | Oct 05, 2023 |
| Direkt-Tek    | DTLAPY116-1                 | [09c308ed3d](https://linux-hardware.org/?probe=09c308ed3d) | Oct 05, 2023 |
| HP            | EliteBook 8460p             | [6be4af5bb3](https://linux-hardware.org/?probe=6be4af5bb3) | Oct 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [7700b3d342](https://linux-hardware.org/?probe=7700b3d342) | Oct 04, 2023 |
| Samsung       | 940Z5L                      | [120b5dac7e](https://linux-hardware.org/?probe=120b5dac7e) | Oct 04, 2023 |
| HP            | EliteBook 745 G6            | [77cfc34723](https://linux-hardware.org/?probe=77cfc34723) | Oct 04, 2023 |
| Lenovo        | ThinkPad L13 20R30009RT     | [8bc32c8cb6](https://linux-hardware.org/?probe=8bc32c8cb6) | Oct 04, 2023 |
| Dell          | Latitude 7340               | [713640e574](https://linux-hardware.org/?probe=713640e574) | Oct 04, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | [b2f26d1c00](https://linux-hardware.org/?probe=b2f26d1c00) | Oct 04, 2023 |
| MSI           | PR600                       | [09fe9eb818](https://linux-hardware.org/?probe=09fe9eb818) | Oct 04, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [7bb81b99a0](https://linux-hardware.org/?probe=7bb81b99a0) | Oct 04, 2023 |
| Direkt-Tek    | DTLAPY116-1                 | [eb797a8074](https://linux-hardware.org/?probe=eb797a8074) | Oct 03, 2023 |
| ASUSTek       | K52JT                       | [30a087cc37](https://linux-hardware.org/?probe=30a087cc37) | Oct 03, 2023 |
| HP            | Laptop 14-cf2xxx            | [4c6c3c41b3](https://linux-hardware.org/?probe=4c6c3c41b3) | Oct 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [452537ff56](https://linux-hardware.org/?probe=452537ff56) | Oct 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [0085d7a6ca](https://linux-hardware.org/?probe=0085d7a6ca) | Oct 03, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | [5813f8d107](https://linux-hardware.org/?probe=5813f8d107) | Oct 03, 2023 |
| Samsung       | 940XGK                      | [63aededb0c](https://linux-hardware.org/?probe=63aededb0c) | Oct 03, 2023 |
| Samsung       | 940XGK                      | [805cef3023](https://linux-hardware.org/?probe=805cef3023) | Oct 03, 2023 |
| HUAWEI        | KLVL-WXXW                   | [a55f97899c](https://linux-hardware.org/?probe=a55f97899c) | Oct 03, 2023 |
| Lenovo        | ThinkPad T420 4236BR4       | [002422b029](https://linux-hardware.org/?probe=002422b029) | Oct 03, 2023 |
| ASUSTek       | Zenbook UX7602ZM_UX7602Z... | [cc7ba8c1ea](https://linux-hardware.org/?probe=cc7ba8c1ea) | Oct 03, 2023 |
| Acer          | Aspire A715-51G             | [6bc4edfef5](https://linux-hardware.org/?probe=6bc4edfef5) | Oct 02, 2023 |
| MSI           | VR630                       | [a9ce96c1ff](https://linux-hardware.org/?probe=a9ce96c1ff) | Oct 02, 2023 |
| HP            | Pavilion 17                 | [d78757ca20](https://linux-hardware.org/?probe=d78757ca20) | Oct 02, 2023 |
| HP            | 15                          | [254f7000e9](https://linux-hardware.org/?probe=254f7000e9) | Oct 02, 2023 |
| Acer          | Aspire A715-51G             | [a9b3098036](https://linux-hardware.org/?probe=a9b3098036) | Oct 02, 2023 |
| Acer          | Swift SF515-51T             | [2452e6e54f](https://linux-hardware.org/?probe=2452e6e54f) | Oct 02, 2023 |
| Apple         | MacBookPro16,3              | [9ca487f2cf](https://linux-hardware.org/?probe=9ca487f2cf) | Oct 02, 2023 |
| HP            | Laptop 14s-dq2xxx           | [4c5eef8118](https://linux-hardware.org/?probe=4c5eef8118) | Oct 02, 2023 |
| HP            | 15                          | [a5814d048c](https://linux-hardware.org/?probe=a5814d048c) | Oct 02, 2023 |
| MSI           | Vector GP68HX 12VH          | [e582127237](https://linux-hardware.org/?probe=e582127237) | Oct 02, 2023 |
| Fujitsu       | LIFEBOOK A357               | [6f11536a5f](https://linux-hardware.org/?probe=6f11536a5f) | Oct 02, 2023 |
| Lenovo        | IdeaPad L3 15ITL6 82HL      | [ae0c9bf33a](https://linux-hardware.org/?probe=ae0c9bf33a) | Oct 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [4462bfcb6d](https://linux-hardware.org/?probe=4462bfcb6d) | Oct 02, 2023 |
| Acer          | Aspire A515-45              | [9e09848439](https://linux-hardware.org/?probe=9e09848439) | Oct 02, 2023 |
| Google        | Magpie                      | [32a7bba307](https://linux-hardware.org/?probe=32a7bba307) | Oct 01, 2023 |
| Lenovo        | G500 20236                  | [96ce4b8060](https://linux-hardware.org/?probe=96ce4b8060) | Oct 01, 2023 |
| Dell          | Inspiron 15 3515            | [44bfa52d57](https://linux-hardware.org/?probe=44bfa52d57) | Oct 01, 2023 |
| HP            | ProBook 640 G1              | [e1945fe82f](https://linux-hardware.org/?probe=e1945fe82f) | Oct 01, 2023 |
| Acer          | Nitro AN515-55              | [9dd550337d](https://linux-hardware.org/?probe=9dd550337d) | Oct 01, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [16354c8d94](https://linux-hardware.org/?probe=16354c8d94) | Oct 01, 2023 |
| Dell          | XPS 15 9500                 | [a8f95ea32d](https://linux-hardware.org/?probe=a8f95ea32d) | Oct 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [34b8e1853b](https://linux-hardware.org/?probe=34b8e1853b) | Oct 01, 2023 |
| Toshiba       | Satellite L735              | [c969a72669](https://linux-hardware.org/?probe=c969a72669) | Oct 01, 2023 |
| Acer          | Predator PH16-71            | [a07278dc43](https://linux-hardware.org/?probe=a07278dc43) | Oct 01, 2023 |
| Dell          | Latitude 5520               | [024af71640](https://linux-hardware.org/?probe=024af71640) | Oct 01, 2023 |
| Apple         | MacBookPro9,2               | [124425b8b3](https://linux-hardware.org/?probe=124425b8b3) | Oct 01, 2023 |
| Dell          | Latitude E6420              | [55c45fb7cb](https://linux-hardware.org/?probe=55c45fb7cb) | Oct 01, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [30bf4415dc](https://linux-hardware.org/?probe=30bf4415dc) | Sep 30, 2023 |
| HUAWEI        | VLT-WX0                     | [a312a57d16](https://linux-hardware.org/?probe=a312a57d16) | Sep 30, 2023 |
| MSI           | Prestige 14H B12UCX         | [b3a006adc7](https://linux-hardware.org/?probe=b3a006adc7) | Sep 30, 2023 |
| MSI           | Prestige 14H B12UCX         | [1c1f35d1c8](https://linux-hardware.org/?probe=1c1f35d1c8) | Sep 30, 2023 |
| Dell          | Latitude 7280               | [dbe9d3e4be](https://linux-hardware.org/?probe=dbe9d3e4be) | Sep 30, 2023 |
| Toshiba       | PORTEGE R30-D               | [04ef694f1d](https://linux-hardware.org/?probe=04ef694f1d) | Sep 30, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1402CBA... | [91873a529a](https://linux-hardware.org/?probe=91873a529a) | Sep 30, 2023 |
| Lenovo        | ThinkPad T420 4180BV1       | [e81749053b](https://linux-hardware.org/?probe=e81749053b) | Sep 30, 2023 |
| Acer          | Aspire A514-53              | [6d8a5b1a13](https://linux-hardware.org/?probe=6d8a5b1a13) | Sep 30, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [c1a605af33](https://linux-hardware.org/?probe=c1a605af33) | Sep 29, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [ec1384a424](https://linux-hardware.org/?probe=ec1384a424) | Sep 29, 2023 |
| Razer         | Blade 15 Base Model (Lat... | [95dc405a73](https://linux-hardware.org/?probe=95dc405a73) | Sep 29, 2023 |
| HP            | Laptop 17-cn1xxx            | [051a233121](https://linux-hardware.org/?probe=051a233121) | Sep 29, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [e51fd2a8e9](https://linux-hardware.org/?probe=e51fd2a8e9) | Sep 29, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [d958b4e16a](https://linux-hardware.org/?probe=d958b4e16a) | Sep 29, 2023 |
| HP            | EliteBook 745 G5            | [b734ec49e2](https://linux-hardware.org/?probe=b734ec49e2) | Sep 29, 2023 |
| HP            | EliteBook 840 G6            | [e57cdefe7a](https://linux-hardware.org/?probe=e57cdefe7a) | Sep 29, 2023 |
| HUAWEI        | HVY-WXX9                    | [713d59f3d0](https://linux-hardware.org/?probe=713d59f3d0) | Sep 29, 2023 |
| HUAWEI        | HVY-WXX9                    | [c434f30a15](https://linux-hardware.org/?probe=c434f30a15) | Sep 29, 2023 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [d95e370c54](https://linux-hardware.org/?probe=d95e370c54) | Sep 29, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [4cef8be854](https://linux-hardware.org/?probe=4cef8be854) | Sep 28, 2023 |
| HP            | EliteBook 840 G2            | [bec979fcd0](https://linux-hardware.org/?probe=bec979fcd0) | Sep 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | [356b5f053d](https://linux-hardware.org/?probe=356b5f053d) | Sep 28, 2023 |
| HP            | EliteBook 840 G6            | [5b87382fce](https://linux-hardware.org/?probe=5b87382fce) | Sep 28, 2023 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [64a85b8eb3](https://linux-hardware.org/?probe=64a85b8eb3) | Sep 28, 2023 |
| Lenovo        | ThinkPad T495 20NJ000XGE    | [737b3910bb](https://linux-hardware.org/?probe=737b3910bb) | Sep 28, 2023 |
| Lenovo        | ThinkPad T495 20NJ000XGE    | [b064b5b9ca](https://linux-hardware.org/?probe=b064b5b9ca) | Sep 28, 2023 |
| HP            | Notebook                    | [b13debd2fa](https://linux-hardware.org/?probe=b13debd2fa) | Sep 27, 2023 |
| Dell          | Latitude 7490               | [6f5e4547fa](https://linux-hardware.org/?probe=6f5e4547fa) | Sep 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [a95feaee78](https://linux-hardware.org/?probe=a95feaee78) | Sep 27, 2023 |
| Framework     | Laptop                      | [2a65b0dff2](https://linux-hardware.org/?probe=2a65b0dff2) | Sep 27, 2023 |
| Acer          | Predator G3-571             | [f301a514ad](https://linux-hardware.org/?probe=f301a514ad) | Sep 27, 2023 |
| Samsung       | 550XDA                      | [ab1fabfe9b](https://linux-hardware.org/?probe=ab1fabfe9b) | Sep 27, 2023 |
| Chuwi         | CoreBook X                  | [0c31a47880](https://linux-hardware.org/?probe=0c31a47880) | Sep 27, 2023 |
| Notebook      | PCx0Dx                      | [53dd8cbd0d](https://linux-hardware.org/?probe=53dd8cbd0d) | Sep 27, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | [fed9f17a22](https://linux-hardware.org/?probe=fed9f17a22) | Sep 27, 2023 |
| Acer          | Predator G3-571             | [06b0300670](https://linux-hardware.org/?probe=06b0300670) | Sep 27, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | [0dd1b47aa0](https://linux-hardware.org/?probe=0dd1b47aa0) | Sep 27, 2023 |
| Dell          | Latitude E7450              | [afa1cce666](https://linux-hardware.org/?probe=afa1cce666) | Sep 27, 2023 |
| Dell          | Latitude 5420               | [4f890f283a](https://linux-hardware.org/?probe=4f890f283a) | Sep 26, 2023 |
| Dell          | Latitude 7490               | [8bb2e054ec](https://linux-hardware.org/?probe=8bb2e054ec) | Sep 26, 2023 |
| Dell          | G15 5520                    | [64cfeba3ee](https://linux-hardware.org/?probe=64cfeba3ee) | Sep 26, 2023 |
| Dell          | Latitude 5420               | [3a22857022](https://linux-hardware.org/?probe=3a22857022) | Sep 26, 2023 |
| HP            | Laptop 14s-dq2xxx           | [424e7e3d87](https://linux-hardware.org/?probe=424e7e3d87) | Sep 26, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [dd48e0075b](https://linux-hardware.org/?probe=dd48e0075b) | Sep 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21HD0... | [35e9d35a69](https://linux-hardware.org/?probe=35e9d35a69) | Sep 26, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [dc762f9ae6](https://linux-hardware.org/?probe=dc762f9ae6) | Sep 26, 2023 |
| Lenovo        | ThinkPad T490s 20NX003NR... | [0a38f1e9a4](https://linux-hardware.org/?probe=0a38f1e9a4) | Sep 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [14766bbd15](https://linux-hardware.org/?probe=14766bbd15) | Sep 26, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [7c547aa37a](https://linux-hardware.org/?probe=7c547aa37a) | Sep 26, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [b22a584cea](https://linux-hardware.org/?probe=b22a584cea) | Sep 26, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [73d2dae51c](https://linux-hardware.org/?probe=73d2dae51c) | Sep 26, 2023 |
| Lenovo        | Z50-70 20354                | [ccdfae441b](https://linux-hardware.org/?probe=ccdfae441b) | Sep 26, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [37fdb062e1](https://linux-hardware.org/?probe=37fdb062e1) | Sep 26, 2023 |
| Apple         | MacBookPro10,1              | [1c1268d4e0](https://linux-hardware.org/?probe=1c1268d4e0) | Sep 25, 2023 |
| Apple         | MacBookPro10,1              | [4fbb517b71](https://linux-hardware.org/?probe=4fbb517b71) | Sep 25, 2023 |
| HP            | EliteBook 840 G3            | [4e0f83e1fe](https://linux-hardware.org/?probe=4e0f83e1fe) | Sep 25, 2023 |
| HP            | EliteBook 840 G3            | [60ff167d14](https://linux-hardware.org/?probe=60ff167d14) | Sep 25, 2023 |
| System76      | Pangolin                    | [3c56c50463](https://linux-hardware.org/?probe=3c56c50463) | Sep 25, 2023 |
| Acer          | Aspire V3-571G              | [6b5dcea023](https://linux-hardware.org/?probe=6b5dcea023) | Sep 25, 2023 |
| Dell          | Latitude E7270              | [98dd5eefb6](https://linux-hardware.org/?probe=98dd5eefb6) | Sep 25, 2023 |
| HP            | 255 G8 Notebook PC          | [91c3333a18](https://linux-hardware.org/?probe=91c3333a18) | Sep 25, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [9a24a19f6e](https://linux-hardware.org/?probe=9a24a19f6e) | Sep 25, 2023 |
| HP            | ProBook 6570b               | [a67981aa91](https://linux-hardware.org/?probe=a67981aa91) | Sep 25, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [88385cbacc](https://linux-hardware.org/?probe=88385cbacc) | Sep 25, 2023 |
| Dell          | XPS 13 9310                 | [4233a2e5e3](https://linux-hardware.org/?probe=4233a2e5e3) | Sep 25, 2023 |
| Dell          | XPS 13 9380                 | [705c3fdeff](https://linux-hardware.org/?probe=705c3fdeff) | Sep 25, 2023 |
| MSI           | GL65 Leopard 10SER          | [e97a8fa2c7](https://linux-hardware.org/?probe=e97a8fa2c7) | Sep 25, 2023 |
| HP            | 250 G6 Notebook PC          | [88ce9be8a1](https://linux-hardware.org/?probe=88ce9be8a1) | Sep 24, 2023 |
| MSI           | GL65 Leopard 10SER          | [fac92f385c](https://linux-hardware.org/?probe=fac92f385c) | Sep 24, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [0531db8cb8](https://linux-hardware.org/?probe=0531db8cb8) | Sep 24, 2023 |
| Acer          | TravelMate P259-MG          | [26ca7317b2](https://linux-hardware.org/?probe=26ca7317b2) | Sep 24, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [408377c3fd](https://linux-hardware.org/?probe=408377c3fd) | Sep 24, 2023 |
| Apple         | MacBookPro8,2               | [cba55a15ec](https://linux-hardware.org/?probe=cba55a15ec) | Sep 24, 2023 |
| Dell          | Latitude 7400               | [f537b79d15](https://linux-hardware.org/?probe=f537b79d15) | Sep 24, 2023 |
| Lenovo        | V14-ARE 82DQ                | [31a635bff8](https://linux-hardware.org/?probe=31a635bff8) | Sep 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | [72940bf53e](https://linux-hardware.org/?probe=72940bf53e) | Sep 24, 2023 |
| HP            | 350 G2                      | [8440938e22](https://linux-hardware.org/?probe=8440938e22) | Sep 24, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [01b1c1acdb](https://linux-hardware.org/?probe=01b1c1acdb) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [fc14083064](https://linux-hardware.org/?probe=fc14083064) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [acba7de2ec](https://linux-hardware.org/?probe=acba7de2ec) | Sep 24, 2023 |
| HP            | 255 15.6 inch G10           | [9f02426c5d](https://linux-hardware.org/?probe=9f02426c5d) | Sep 23, 2023 |
| Apple         | MacBookPro10,1              | [18b2a7026b](https://linux-hardware.org/?probe=18b2a7026b) | Sep 23, 2023 |
| Apple         | MacBookPro10,1              | [60f81eeb50](https://linux-hardware.org/?probe=60f81eeb50) | Sep 23, 2023 |
| Lenovo        | ThinkPad T550 20CK0002MZ    | [a34763914d](https://linux-hardware.org/?probe=a34763914d) | Sep 23, 2023 |
| HP            | Pavilion dv6                | [bd8ae0385b](https://linux-hardware.org/?probe=bd8ae0385b) | Sep 23, 2023 |
| Dell          | Latitude 7280               | [1d032535e1](https://linux-hardware.org/?probe=1d032535e1) | Sep 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [a6ff891fa1](https://linux-hardware.org/?probe=a6ff891fa1) | Sep 23, 2023 |
| Casper        | NIRVANA NB F500             | [1f66f22544](https://linux-hardware.org/?probe=1f66f22544) | Sep 23, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | [d464d79df3](https://linux-hardware.org/?probe=d464d79df3) | Sep 23, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [11ce4105e1](https://linux-hardware.org/?probe=11ce4105e1) | Sep 23, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | [b96887841e](https://linux-hardware.org/?probe=b96887841e) | Sep 23, 2023 |
| Toshiba       | Satellite C70-B             | [904a43b77e](https://linux-hardware.org/?probe=904a43b77e) | Sep 23, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [6a6fde2ca9](https://linux-hardware.org/?probe=6a6fde2ca9) | Sep 23, 2023 |
| Toshiba       | Satellite C70-B             | [eedf248084](https://linux-hardware.org/?probe=eedf248084) | Sep 23, 2023 |
| Acer          | Aspire ES1-520              | [22ce921c1e](https://linux-hardware.org/?probe=22ce921c1e) | Sep 22, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | [535d4769c8](https://linux-hardware.org/?probe=535d4769c8) | Sep 22, 2023 |
| Acer          | Aspire A715-51G             | [674c086aa5](https://linux-hardware.org/?probe=674c086aa5) | Sep 22, 2023 |
| Apple         | MacBookPro11,1              | [169fe58269](https://linux-hardware.org/?probe=169fe58269) | Sep 22, 2023 |
| Apple         | MacBookPro14,1              | [8b1188ba33](https://linux-hardware.org/?probe=8b1188ba33) | Sep 22, 2023 |
| HUAWEI        | BOD-WXX9                    | [909efbf81b](https://linux-hardware.org/?probe=909efbf81b) | Sep 22, 2023 |
| Dell          | Latitude 5420               | [d9c1c1537f](https://linux-hardware.org/?probe=d9c1c1537f) | Sep 22, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [7b093ed910](https://linux-hardware.org/?probe=7b093ed910) | Sep 22, 2023 |
| HP            | EliteBook 840 G5 NOTEBOO... | [0e85445e8e](https://linux-hardware.org/?probe=0e85445e8e) | Sep 21, 2023 |
| HP            | EliteBook 840 G5 NOTEBOO... | [3a372bed63](https://linux-hardware.org/?probe=3a372bed63) | Sep 21, 2023 |
| Lenovo        | Slim 7 14IRP8 83A4          | [b1ccf59045](https://linux-hardware.org/?probe=b1ccf59045) | Sep 21, 2023 |
| HP            | Pavilion dv6                | [270b0c0878](https://linux-hardware.org/?probe=270b0c0878) | Sep 21, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [3cd9b7841a](https://linux-hardware.org/?probe=3cd9b7841a) | Sep 21, 2023 |
| Lenovo        | Mullins-LarneML             | [56157a1cff](https://linux-hardware.org/?probe=56157a1cff) | Sep 21, 2023 |
| Samsung       | R530/R730/R540              | [658ca13022](https://linux-hardware.org/?probe=658ca13022) | Sep 21, 2023 |
| Samsung       | 550XBE/350XBE               | [522d50a437](https://linux-hardware.org/?probe=522d50a437) | Sep 21, 2023 |
| HP            | Pavilion g6                 | [11c60c8645](https://linux-hardware.org/?probe=11c60c8645) | Sep 21, 2023 |
| Dell          | Vostro 1310                 | [bc0c23c23c](https://linux-hardware.org/?probe=bc0c23c23c) | Sep 21, 2023 |
| Dell          | XPS 15 9520                 | [2bb7ed1454](https://linux-hardware.org/?probe=2bb7ed1454) | Sep 21, 2023 |
| HP            | 250 G7 Notebook PC          | [a2a2bc81e9](https://linux-hardware.org/?probe=a2a2bc81e9) | Sep 20, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [b4f1770e14](https://linux-hardware.org/?probe=b4f1770e14) | Sep 20, 2023 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [ddf1d6a712](https://linux-hardware.org/?probe=ddf1d6a712) | Sep 20, 2023 |
| MSI           | Prestige 14 A10SC           | [6f81167a6c](https://linux-hardware.org/?probe=6f81167a6c) | Sep 20, 2023 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [7377101d6d](https://linux-hardware.org/?probe=7377101d6d) | Sep 20, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [79111191a0](https://linux-hardware.org/?probe=79111191a0) | Sep 20, 2023 |
| MSI           | Prestige 14 A10SC           | [e0ee68b1a7](https://linux-hardware.org/?probe=e0ee68b1a7) | Sep 20, 2023 |
| TUXEDO        | P65_P67RGRERA               | [97bae35595](https://linux-hardware.org/?probe=97bae35595) | Sep 20, 2023 |
| TUXEDO        | P65_P67RGRERA               | [0aefa5e3c6](https://linux-hardware.org/?probe=0aefa5e3c6) | Sep 20, 2023 |
| Apple         | MacBook4,1                  | [3434dd8b54](https://linux-hardware.org/?probe=3434dd8b54) | Sep 20, 2023 |
| Samsung       | NC210/NC110                 | [1e194a2568](https://linux-hardware.org/?probe=1e194a2568) | Sep 20, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [27002ca3a9](https://linux-hardware.org/?probe=27002ca3a9) | Sep 20, 2023 |
| Timi          | Xiaomi Book Pro 16 2022     | [94e8c710d5](https://linux-hardware.org/?probe=94e8c710d5) | Sep 20, 2023 |
| Acer          | Aspire A515-56              | [bb52b1ddc5](https://linux-hardware.org/?probe=bb52b1ddc5) | Sep 20, 2023 |
| Samsung       | 960XFH                      | [c25c858bd4](https://linux-hardware.org/?probe=c25c858bd4) | Sep 19, 2023 |
| Maibenben     | MaiBook M Series            | [dc2eb7a7d7](https://linux-hardware.org/?probe=dc2eb7a7d7) | Sep 19, 2023 |
| Apple         | MacBookAir7,2               | [6edec4d045](https://linux-hardware.org/?probe=6edec4d045) | Sep 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [ca0ad87f0b](https://linux-hardware.org/?probe=ca0ad87f0b) | Sep 19, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [aeffbe0fe5](https://linux-hardware.org/?probe=aeffbe0fe5) | Sep 19, 2023 |
| Lenovo        | ThinkPad W540 20BG0014US    | [2d1c5101ea](https://linux-hardware.org/?probe=2d1c5101ea) | Sep 19, 2023 |
| HP            | ProBook 6475b               | [43c4870e11](https://linux-hardware.org/?probe=43c4870e11) | Sep 19, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [f9e5656f54](https://linux-hardware.org/?probe=f9e5656f54) | Sep 19, 2023 |
| Lenovo        | ThinkPad X240 20AMS1WN0A    | [858aed6617](https://linux-hardware.org/?probe=858aed6617) | Sep 19, 2023 |
| Dell          | Precision 3581              | [e1c8eb2810](https://linux-hardware.org/?probe=e1c8eb2810) | Sep 18, 2023 |
| Dell          | Inspiron 5480               | [51aca22643](https://linux-hardware.org/?probe=51aca22643) | Sep 18, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [4d986c5384](https://linux-hardware.org/?probe=4d986c5384) | Sep 18, 2023 |
| Dell          | Latitude 5490               | [94eb709dfc](https://linux-hardware.org/?probe=94eb709dfc) | Sep 18, 2023 |
| MSI           | Katana GF76 11UD            | [f797b137a3](https://linux-hardware.org/?probe=f797b137a3) | Sep 18, 2023 |
| Acer          | Aspire 5755G                | [f58cf1f72d](https://linux-hardware.org/?probe=f58cf1f72d) | Sep 18, 2023 |
| Acer          | Aspire 5755G                | [68cef2242a](https://linux-hardware.org/?probe=68cef2242a) | Sep 18, 2023 |
| HUAWEI        | KLVDZ-WXX9                  | [a4964c1b7a](https://linux-hardware.org/?probe=a4964c1b7a) | Sep 18, 2023 |
| HP            | EliteBook 745 G2            | [7e5ee5a990](https://linux-hardware.org/?probe=7e5ee5a990) | Sep 18, 2023 |
| Lenovo        | ThinkPad T480 20L6SCYF0P    | [c406bf7b56](https://linux-hardware.org/?probe=c406bf7b56) | Sep 18, 2023 |
| Lenovo        | G50-30 80G0                 | [fa9bd484cd](https://linux-hardware.org/?probe=fa9bd484cd) | Sep 17, 2023 |
| Lenovo        | G400 20235                  | [bd7a7a6f22](https://linux-hardware.org/?probe=bd7a7a6f22) | Sep 17, 2023 |
| Lenovo        | G400 20235                  | [c8ecd1e0c9](https://linux-hardware.org/?probe=c8ecd1e0c9) | Sep 17, 2023 |
| Timi          | Xiaomi Book Pro 16 2022     | [290f6c66d1](https://linux-hardware.org/?probe=290f6c66d1) | Sep 17, 2023 |
| Dell          | XPS 15 9520                 | [2b66c2969e](https://linux-hardware.org/?probe=2b66c2969e) | Sep 17, 2023 |
| HP            | Pavilion g6                 | [dd1ade8736](https://linux-hardware.org/?probe=dd1ade8736) | Sep 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XY... | [93d01648a0](https://linux-hardware.org/?probe=93d01648a0) | Sep 17, 2023 |
| Dell          | Inspiron 1464               | [9830a0345b](https://linux-hardware.org/?probe=9830a0345b) | Sep 17, 2023 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [21b0d9faff](https://linux-hardware.org/?probe=21b0d9faff) | Sep 17, 2023 |
| MSI           | Modern 14 B4MW              | [83a224edea](https://linux-hardware.org/?probe=83a224edea) | Sep 17, 2023 |
| Dell          | Inspiron 5566               | [56f2d4d1eb](https://linux-hardware.org/?probe=56f2d4d1eb) | Sep 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [3bb8e84b6b](https://linux-hardware.org/?probe=3bb8e84b6b) | Sep 17, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [a53b964a47](https://linux-hardware.org/?probe=a53b964a47) | Sep 17, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [648af5d937](https://linux-hardware.org/?probe=648af5d937) | Sep 17, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [77a72808f7](https://linux-hardware.org/?probe=77a72808f7) | Sep 17, 2023 |
| HP            | 250 G1                      | [0e052c1de2](https://linux-hardware.org/?probe=0e052c1de2) | Sep 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [bf532ab6ec](https://linux-hardware.org/?probe=bf532ab6ec) | Sep 16, 2023 |
| HP            | EliteBook 820 G4            | [a16a2ef714](https://linux-hardware.org/?probe=a16a2ef714) | Sep 16, 2023 |
| MSI           | Modern 14 B4MW              | [06e45359c0](https://linux-hardware.org/?probe=06e45359c0) | Sep 16, 2023 |
| Lenovo        | Legion 5-15IMH05H 81Y6      | [1b2e11b609](https://linux-hardware.org/?probe=1b2e11b609) | Sep 16, 2023 |
| Lenovo        | IdeaPad Z500 5931           | [0986123aac](https://linux-hardware.org/?probe=0986123aac) | Sep 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F7... | [2c90700f4f](https://linux-hardware.org/?probe=2c90700f4f) | Sep 16, 2023 |
| HP            | Laptop 14s-dq2xxx           | [12456f4694](https://linux-hardware.org/?probe=12456f4694) | Sep 16, 2023 |
| Dell          | XPS 9320                    | [99fce2103f](https://linux-hardware.org/?probe=99fce2103f) | Sep 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [a5c073ca7a](https://linux-hardware.org/?probe=a5c073ca7a) | Sep 16, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [2085bafc62](https://linux-hardware.org/?probe=2085bafc62) | Sep 16, 2023 |
| Acer          | TravelMate 5335             | [d440c12063](https://linux-hardware.org/?probe=d440c12063) | Sep 16, 2023 |
| Dell          | XPS L501X                   | [13d0075027](https://linux-hardware.org/?probe=13d0075027) | Sep 16, 2023 |
| Dell          | Inspiron M5010              | [c78ab23cc7](https://linux-hardware.org/?probe=c78ab23cc7) | Sep 16, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [ec3d359099](https://linux-hardware.org/?probe=ec3d359099) | Sep 15, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [fa207e873a](https://linux-hardware.org/?probe=fa207e873a) | Sep 15, 2023 |
| Lenovo        | G550 20023                  | [054463900e](https://linux-hardware.org/?probe=054463900e) | Sep 15, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [b76ae8f9db](https://linux-hardware.org/?probe=b76ae8f9db) | Sep 15, 2023 |
| Lenovo        | G550 20023                  | [cdc9163353](https://linux-hardware.org/?probe=cdc9163353) | Sep 15, 2023 |
| Timi          | Mi NoteBook Ultra           | [1c5a009557](https://linux-hardware.org/?probe=1c5a009557) | Sep 15, 2023 |
| Lenovo        | Legion Pro 7 16IRX8 82WR    | [951dc3d5b0](https://linux-hardware.org/?probe=951dc3d5b0) | Sep 15, 2023 |
| HP            | EliteBook Folio 9470m       | [4a598eb0b3](https://linux-hardware.org/?probe=4a598eb0b3) | Sep 15, 2023 |
| Acer          | Swift SF314-43              | [ae2f1fa903](https://linux-hardware.org/?probe=ae2f1fa903) | Sep 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [982f29b6cc](https://linux-hardware.org/?probe=982f29b6cc) | Sep 14, 2023 |
| Fujitsu       | LIFEBOOK A357               | [a02233b901](https://linux-hardware.org/?probe=a02233b901) | Sep 14, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | [934dc9c297](https://linux-hardware.org/?probe=934dc9c297) | Sep 14, 2023 |
| Apple         | MacBookPro9,2               | [37e1d06001](https://linux-hardware.org/?probe=37e1d06001) | Sep 14, 2023 |
| Acer          | Swift SF314-42              | [d907642716](https://linux-hardware.org/?probe=d907642716) | Sep 14, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [426914b6e5](https://linux-hardware.org/?probe=426914b6e5) | Sep 14, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [756eff685a](https://linux-hardware.org/?probe=756eff685a) | Sep 14, 2023 |
| System76      | Darter Pro                  | [78c45153a3](https://linux-hardware.org/?probe=78c45153a3) | Sep 14, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [820a13876a](https://linux-hardware.org/?probe=820a13876a) | Sep 14, 2023 |
| Dell          | Latitude 7390               | [4d8e0cb72b](https://linux-hardware.org/?probe=4d8e0cb72b) | Sep 14, 2023 |
| HP            | Pavilion 13 x360 PC         | [58de71a548](https://linux-hardware.org/?probe=58de71a548) | Sep 14, 2023 |
| Toshiba       | PORTEGE M750                | [1c3442d87f](https://linux-hardware.org/?probe=1c3442d87f) | Sep 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [9ace0dfae8](https://linux-hardware.org/?probe=9ace0dfae8) | Sep 14, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [d61823257e](https://linux-hardware.org/?probe=d61823257e) | Sep 13, 2023 |
| Dell          | Latitude 5421               | [6942c0131d](https://linux-hardware.org/?probe=6942c0131d) | Sep 13, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | [cb29d8cb77](https://linux-hardware.org/?probe=cb29d8cb77) | Sep 13, 2023 |
| Dell          | Latitude 7390               | [2afdbd653c](https://linux-hardware.org/?probe=2afdbd653c) | Sep 13, 2023 |
| Fujitsu       | LIFEBOOK UH554              | [92f2e6135e](https://linux-hardware.org/?probe=92f2e6135e) | Sep 13, 2023 |
| Dell          | Inspiron 5566               | [6c9eaad10e](https://linux-hardware.org/?probe=6c9eaad10e) | Sep 13, 2023 |
| Dell          | Inspiron 5558               | [046d28d32d](https://linux-hardware.org/?probe=046d28d32d) | Sep 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [0918609cf3](https://linux-hardware.org/?probe=0918609cf3) | Sep 13, 2023 |
| Apple         | MacBookPro9,2               | [e8b1e251a3](https://linux-hardware.org/?probe=e8b1e251a3) | Sep 13, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [0317b3bcf6](https://linux-hardware.org/?probe=0317b3bcf6) | Sep 13, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [37f8406bab](https://linux-hardware.org/?probe=37f8406bab) | Sep 13, 2023 |
| Lenovo        | IdeaPad Slim 3 15AMN8 82... | [fcac50bfba](https://linux-hardware.org/?probe=fcac50bfba) | Sep 13, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [52a1dc1e19](https://linux-hardware.org/?probe=52a1dc1e19) | Sep 12, 2023 |
| ASUSTek       | K53SK                       | [5dcbdaa6d7](https://linux-hardware.org/?probe=5dcbdaa6d7) | Sep 12, 2023 |
| ASUSTek       | X550JK                      | [0965a776b0](https://linux-hardware.org/?probe=0965a776b0) | Sep 12, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [d1d5edf95c](https://linux-hardware.org/?probe=d1d5edf95c) | Sep 12, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [b11bc1c28f](https://linux-hardware.org/?probe=b11bc1c28f) | Sep 12, 2023 |
| ASUSTek       | X550JK                      | [00a34c8719](https://linux-hardware.org/?probe=00a34c8719) | Sep 12, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [3ef24a5b48](https://linux-hardware.org/?probe=3ef24a5b48) | Sep 12, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [4715a2425e](https://linux-hardware.org/?probe=4715a2425e) | Sep 12, 2023 |
| Apple         | MacBookPro9,2               | [77db8877eb](https://linux-hardware.org/?probe=77db8877eb) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [564a2ea72e](https://linux-hardware.org/?probe=564a2ea72e) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [58b852c7cb](https://linux-hardware.org/?probe=58b852c7cb) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [10ff64dcf5](https://linux-hardware.org/?probe=10ff64dcf5) | Sep 12, 2023 |
| HP            | Laptop 15-dy5xxx            | [20ff9ece53](https://linux-hardware.org/?probe=20ff9ece53) | Sep 12, 2023 |
| Lenovo        | G770 20089                  | [39c8088b09](https://linux-hardware.org/?probe=39c8088b09) | Sep 12, 2023 |
| Apple         | MacBookAir6,2               | [e71b5644ea](https://linux-hardware.org/?probe=e71b5644ea) | Sep 12, 2023 |
| Dell          | XPS L521X                   | [d9e9a65142](https://linux-hardware.org/?probe=d9e9a65142) | Sep 12, 2023 |
| Positivo      | S14CT01                     | [57ed555d4b](https://linux-hardware.org/?probe=57ed555d4b) | Sep 11, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [84f6190c40](https://linux-hardware.org/?probe=84f6190c40) | Sep 11, 2023 |
| HUAWEI        | MACHC-WAX9                  | [3cafef18bf](https://linux-hardware.org/?probe=3cafef18bf) | Sep 11, 2023 |
| Dell          | XPS L322X                   | [77135f7967](https://linux-hardware.org/?probe=77135f7967) | Sep 11, 2023 |
| Dell          | Inspiron M5010              | [70147b0015](https://linux-hardware.org/?probe=70147b0015) | Sep 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [d4178bc91c](https://linux-hardware.org/?probe=d4178bc91c) | Sep 11, 2023 |
| HP            | ProBook 645 G1              | [ced1631b20](https://linux-hardware.org/?probe=ced1631b20) | Sep 11, 2023 |
| ASUSTek       | X505BA                      | [cbb45a815f](https://linux-hardware.org/?probe=cbb45a815f) | Sep 11, 2023 |
| Dell          | XPS L322X                   | [fdf4ba47e1](https://linux-hardware.org/?probe=fdf4ba47e1) | Sep 11, 2023 |
| HP            | EliteBook 2570p             | [6259de24be](https://linux-hardware.org/?probe=6259de24be) | Sep 11, 2023 |
| Samsung       | 530XBB                      | [f6039477c2](https://linux-hardware.org/?probe=f6039477c2) | Sep 11, 2023 |
| Dell          | Inspiron 7548               | [0259762efc](https://linux-hardware.org/?probe=0259762efc) | Sep 11, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [38a80416eb](https://linux-hardware.org/?probe=38a80416eb) | Sep 10, 2023 |
| HP            | ProBook 645 G1              | [e78c297114](https://linux-hardware.org/?probe=e78c297114) | Sep 10, 2023 |
| Lenovo        | ThinkPad T480s 20L8S6RF0... | [6c62d111db](https://linux-hardware.org/?probe=6c62d111db) | Sep 10, 2023 |
| Acer          | Aspire 5742G                | [8dc4477486](https://linux-hardware.org/?probe=8dc4477486) | Sep 10, 2023 |
| Acer          | Aspire 5742G                | [e737851117](https://linux-hardware.org/?probe=e737851117) | Sep 10, 2023 |
| Apple         | MacBookPro8,1               | [d3b821a061](https://linux-hardware.org/?probe=d3b821a061) | Sep 10, 2023 |
| MSI           | Modern 14 A10M              | [c78162f5fd](https://linux-hardware.org/?probe=c78162f5fd) | Sep 10, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [30fd7bf070](https://linux-hardware.org/?probe=30fd7bf070) | Sep 10, 2023 |
| Dell          | Latitude E6400              | [b0943a149a](https://linux-hardware.org/?probe=b0943a149a) | Sep 10, 2023 |
| Packard Be... | EasyNote TK85               | [45261be082](https://linux-hardware.org/?probe=45261be082) | Sep 10, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [8b6b039242](https://linux-hardware.org/?probe=8b6b039242) | Sep 10, 2023 |
| Apple         | MacBookPro13,3              | [225a9ae1c5](https://linux-hardware.org/?probe=225a9ae1c5) | Sep 10, 2023 |
| HP            | Laptop 14-ck0xxx            | [8c5abbf5a2](https://linux-hardware.org/?probe=8c5abbf5a2) | Sep 10, 2023 |
| Packard Be... | EasyNote TK85               | [4dfd50fada](https://linux-hardware.org/?probe=4dfd50fada) | Sep 10, 2023 |
| Apple         | MacBookPro8,1               | [69a1a556e0](https://linux-hardware.org/?probe=69a1a556e0) | Sep 09, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [64ea9bc56d](https://linux-hardware.org/?probe=64ea9bc56d) | Sep 09, 2023 |
| Dell          | XPS 13 9310                 | [f898a390e2](https://linux-hardware.org/?probe=f898a390e2) | Sep 09, 2023 |
| Acer          | Aspire 5745G                | [0528523e15](https://linux-hardware.org/?probe=0528523e15) | Sep 09, 2023 |
| Acer          | Aspire A715-51G             | [25649c8a92](https://linux-hardware.org/?probe=25649c8a92) | Sep 09, 2023 |
| Dell          | Inspiron 15-3552            | [eaf6dbaf3e](https://linux-hardware.org/?probe=eaf6dbaf3e) | Sep 09, 2023 |
| Acer          | Predator PH16-71            | [f0b0cc7736](https://linux-hardware.org/?probe=f0b0cc7736) | Sep 09, 2023 |
| Apple         | MacBookPro11,1              | [bc1887667f](https://linux-hardware.org/?probe=bc1887667f) | Sep 09, 2023 |
| Apple         | MacBookPro11,1              | [2da701e211](https://linux-hardware.org/?probe=2da701e211) | Sep 09, 2023 |
| Dell          | Inspiron 1545               | [95d13f26f0](https://linux-hardware.org/?probe=95d13f26f0) | Sep 09, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [ec08aee6ff](https://linux-hardware.org/?probe=ec08aee6ff) | Sep 09, 2023 |
| Lenovo        | Legion Pro 7 16IRX8 82WR    | [aa6e5c75fc](https://linux-hardware.org/?probe=aa6e5c75fc) | Sep 09, 2023 |
| Lenovo        | Flex 2-14 20404             | [139a93ab8b](https://linux-hardware.org/?probe=139a93ab8b) | Sep 09, 2023 |
| HUAWEI        | KLVL-WXX9                   | [ff8e50a7ea](https://linux-hardware.org/?probe=ff8e50a7ea) | Sep 08, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [a7026388f3](https://linux-hardware.org/?probe=a7026388f3) | Sep 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [7c5a19bc69](https://linux-hardware.org/?probe=7c5a19bc69) | Sep 08, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [6ea0b6ed9f](https://linux-hardware.org/?probe=6ea0b6ed9f) | Sep 08, 2023 |
| HP            | 630                         | [11393e1391](https://linux-hardware.org/?probe=11393e1391) | Sep 08, 2023 |
| Lenovo        | ThinkPad E14 20RA001BUK     | [6bd319be4e](https://linux-hardware.org/?probe=6bd319be4e) | Sep 08, 2023 |
| Dell          | Inspiron 3543               | [74e5f6b8a5](https://linux-hardware.org/?probe=74e5f6b8a5) | Sep 08, 2023 |
| Dell          | Inspiron 3543               | [d4df00af33](https://linux-hardware.org/?probe=d4df00af33) | Sep 08, 2023 |
| Unknown       | W1415A                      | [67fc8d5ea8](https://linux-hardware.org/?probe=67fc8d5ea8) | Sep 08, 2023 |
| Acer          | Predator PH315-51           | [89e33145c3](https://linux-hardware.org/?probe=89e33145c3) | Sep 08, 2023 |
| Sony          | SVE14A25CLW                 | [9646f55c7d](https://linux-hardware.org/?probe=9646f55c7d) | Sep 08, 2023 |
| Sony          | SVE14A25CLW                 | [3f8a5dcaaf](https://linux-hardware.org/?probe=3f8a5dcaaf) | Sep 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [0de4c341fa](https://linux-hardware.org/?probe=0de4c341fa) | Sep 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [89772ef854](https://linux-hardware.org/?probe=89772ef854) | Sep 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [c9ea6ff204](https://linux-hardware.org/?probe=c9ea6ff204) | Sep 07, 2023 |
| Acer          | Aspire V5-531               | [f2df6b2c70](https://linux-hardware.org/?probe=f2df6b2c70) | Sep 07, 2023 |
| Acer          | Aspire V5-531               | [e39cb4e3e6](https://linux-hardware.org/?probe=e39cb4e3e6) | Sep 07, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | [69fc5aab82](https://linux-hardware.org/?probe=69fc5aab82) | Sep 07, 2023 |
| Lenovo        | V580c 20160                 | [87f8bad27d](https://linux-hardware.org/?probe=87f8bad27d) | Sep 07, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | [384d2074ad](https://linux-hardware.org/?probe=384d2074ad) | Sep 07, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | [8a05090057](https://linux-hardware.org/?probe=8a05090057) | Sep 07, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [a2fab791b4](https://linux-hardware.org/?probe=a2fab791b4) | Sep 07, 2023 |
| Timi          | Redmi Book Pro 14S          | [b2776d8282](https://linux-hardware.org/?probe=b2776d8282) | Sep 07, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [24eca3030c](https://linux-hardware.org/?probe=24eca3030c) | Sep 07, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | [da7303433d](https://linux-hardware.org/?probe=da7303433d) | Sep 07, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [9911fc5254](https://linux-hardware.org/?probe=9911fc5254) | Sep 07, 2023 |
| MSI           | Bravo 17 A4DDR              | [2592f883ef](https://linux-hardware.org/?probe=2592f883ef) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b982251e82](https://linux-hardware.org/?probe=b982251e82) | Sep 07, 2023 |
| Dell          | Latitude E6500              | [b4b035c4f7](https://linux-hardware.org/?probe=b4b035c4f7) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [3c6e29c3c3](https://linux-hardware.org/?probe=3c6e29c3c3) | Sep 06, 2023 |
| GPU Compan... | GWNR71517                   | [b6a521128f](https://linux-hardware.org/?probe=b6a521128f) | Sep 06, 2023 |
| Samsung       | 550P5C/550P7C               | [f59dbec9af](https://linux-hardware.org/?probe=f59dbec9af) | Sep 06, 2023 |
| Samsung       | 550P5C/550P7C               | [83c77f6733](https://linux-hardware.org/?probe=83c77f6733) | Sep 06, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [c8ee0a00a5](https://linux-hardware.org/?probe=c8ee0a00a5) | Sep 06, 2023 |
| Dell          | XPS 13 9310                 | [7e81f7531b](https://linux-hardware.org/?probe=7e81f7531b) | Sep 06, 2023 |
| Lenovo        | ThinkPad P1 Gen 6 21FV00... | [c9a07c44d5](https://linux-hardware.org/?probe=c9a07c44d5) | Sep 06, 2023 |
| Dell          | Inspiron 3542               | [1756563167](https://linux-hardware.org/?probe=1756563167) | Sep 06, 2023 |
| Lenovo        | Legion Pro 7 16IRX8 82WR    | [f946665a24](https://linux-hardware.org/?probe=f946665a24) | Sep 06, 2023 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [b5f142ae13](https://linux-hardware.org/?probe=b5f142ae13) | Sep 06, 2023 |
| Apple         | MacBookPro13,1              | [d6b6455af2](https://linux-hardware.org/?probe=d6b6455af2) | Sep 06, 2023 |
| Lenovo        | Yoga S740-15IRH 81NX        | [c31e15f2ba](https://linux-hardware.org/?probe=c31e15f2ba) | Sep 05, 2023 |
| HP            | EliteBook 845 14 inch G9... | [25ec8e4a16](https://linux-hardware.org/?probe=25ec8e4a16) | Sep 05, 2023 |
| Dell          | Latitude 7400               | [e1ea4eb614](https://linux-hardware.org/?probe=e1ea4eb614) | Sep 05, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [bb7f6aed1a](https://linux-hardware.org/?probe=bb7f6aed1a) | Sep 05, 2023 |
| ASUSTek       | E402SA                      | [efad2958a0](https://linux-hardware.org/?probe=efad2958a0) | Sep 05, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [3c55d4d55b](https://linux-hardware.org/?probe=3c55d4d55b) | Sep 05, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | [0309bcca29](https://linux-hardware.org/?probe=0309bcca29) | Sep 05, 2023 |
| Dell          | Latitude 7490               | [c03e42edee](https://linux-hardware.org/?probe=c03e42edee) | Sep 05, 2023 |
| Unknown       | Unknown                     | [9b4d95cf35](https://linux-hardware.org/?probe=9b4d95cf35) | Sep 05, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [5dbf7515d1](https://linux-hardware.org/?probe=5dbf7515d1) | Sep 05, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [7619d8e5e8](https://linux-hardware.org/?probe=7619d8e5e8) | Sep 05, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | [ea1d0861a1](https://linux-hardware.org/?probe=ea1d0861a1) | Sep 05, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [229ca6e8cb](https://linux-hardware.org/?probe=229ca6e8cb) | Sep 05, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [ab9c556dc7](https://linux-hardware.org/?probe=ab9c556dc7) | Sep 05, 2023 |
| Acer          | Aspire 4738Z                | [88b34596c0](https://linux-hardware.org/?probe=88b34596c0) | Sep 05, 2023 |
| Dell          | XPS 13 7390                 | [5154be8883](https://linux-hardware.org/?probe=5154be8883) | Sep 05, 2023 |
| Dell          | G15 5530                    | [91dcc569ee](https://linux-hardware.org/?probe=91dcc569ee) | Sep 05, 2023 |
| HUAWEI        | KLVL-WXX9                   | [d3cde5f4c5](https://linux-hardware.org/?probe=d3cde5f4c5) | Sep 04, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [2a53f8dc55](https://linux-hardware.org/?probe=2a53f8dc55) | Sep 04, 2023 |
| Dell          | Inspiron 3576               | [5139d104cc](https://linux-hardware.org/?probe=5139d104cc) | Sep 04, 2023 |
| Acer          | Aspire E1-571               | [032fca9d1d](https://linux-hardware.org/?probe=032fca9d1d) | Sep 04, 2023 |
| HP            | Laptop 14s-dq2xxx           | [3a5b200954](https://linux-hardware.org/?probe=3a5b200954) | Sep 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [da42098f81](https://linux-hardware.org/?probe=da42098f81) | Sep 04, 2023 |
| Dell          | XPS 13 9380                 | [94e7b43fe2](https://linux-hardware.org/?probe=94e7b43fe2) | Sep 04, 2023 |
| HP            | Laptop 15-dw2xxx            | [fff758a5d9](https://linux-hardware.org/?probe=fff758a5d9) | Sep 04, 2023 |
| Chuwi         | GemiBook                    | [cfdc48e9f6](https://linux-hardware.org/?probe=cfdc48e9f6) | Sep 04, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [1d6a4b4279](https://linux-hardware.org/?probe=1d6a4b4279) | Sep 04, 2023 |
| Dell          | Latitude 5285               | [9ddc47c6a9](https://linux-hardware.org/?probe=9ddc47c6a9) | Sep 04, 2023 |
| Maibenben     | MaiBook M                   | [7189994067](https://linux-hardware.org/?probe=7189994067) | Sep 04, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [18d1abc9ca](https://linux-hardware.org/?probe=18d1abc9ca) | Sep 04, 2023 |
| HUAWEI        | KLVL-WXX9                   | [c3e4035d47](https://linux-hardware.org/?probe=c3e4035d47) | Sep 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [1211fca3e2](https://linux-hardware.org/?probe=1211fca3e2) | Sep 03, 2023 |
| Notebook      | PCx0Dx                      | [89d5a9b606](https://linux-hardware.org/?probe=89d5a9b606) | Sep 03, 2023 |
| Lenovo        | ThinkPad T550 20CKA00ECD    | [20be702d65](https://linux-hardware.org/?probe=20be702d65) | Sep 03, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | [2973871c04](https://linux-hardware.org/?probe=2973871c04) | Sep 03, 2023 |
| HP            | Pavilion Gaming Laptop      | [733f5cb987](https://linux-hardware.org/?probe=733f5cb987) | Sep 03, 2023 |
| Framework     | Laptop                      | [d153316fdd](https://linux-hardware.org/?probe=d153316fdd) | Sep 03, 2023 |
| Dell          | Latitude 3540               | [e7d1d4f160](https://linux-hardware.org/?probe=e7d1d4f160) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e0f8242693](https://linux-hardware.org/?probe=e0f8242693) | Sep 02, 2023 |
| Lenovo        | Legion Slim 5 16IRH8 82Y... | [8f29742c47](https://linux-hardware.org/?probe=8f29742c47) | Sep 02, 2023 |
| ASUSTek       | X540NA                      | [69ccd7d6f2](https://linux-hardware.org/?probe=69ccd7d6f2) | Sep 02, 2023 |
| Dell          | Latitude 5400               | [aac8791780](https://linux-hardware.org/?probe=aac8791780) | Sep 02, 2023 |
| Lenovo        | 14w Gen 2 82N9              | [87c8a118b5](https://linux-hardware.org/?probe=87c8a118b5) | Sep 02, 2023 |
| Prestigio     | Multipad Visconte V         | [3c60fe1d14](https://linux-hardware.org/?probe=3c60fe1d14) | Sep 01, 2023 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [3080550241](https://linux-hardware.org/?probe=3080550241) | Sep 01, 2023 |
| Fujitsu       | LIFEBOOK S760               | [b7439f4404](https://linux-hardware.org/?probe=b7439f4404) | Sep 01, 2023 |
| Timi          | Mi NoteBook Pro             | [7d3823ff94](https://linux-hardware.org/?probe=7d3823ff94) | Sep 01, 2023 |
| Acer          | Aspire E5-551G              | [864a10779f](https://linux-hardware.org/?probe=864a10779f) | Sep 01, 2023 |
| HP            | EliteBook 820 G3            | [24d0eafc15](https://linux-hardware.org/?probe=24d0eafc15) | Sep 01, 2023 |
| Apple         | MacBookAir5,2               | [bda3b1837c](https://linux-hardware.org/?probe=bda3b1837c) | Sep 01, 2023 |
| ASUSTek       | ZenBook UX535LI_UX535LI     | [edd00c35fd](https://linux-hardware.org/?probe=edd00c35fd) | Sep 01, 2023 |
| Apple         | MacBookAir4,1               | [61da3436a8](https://linux-hardware.org/?probe=61da3436a8) | Sep 01, 2023 |
| Lenovo        | Legion Pro 7 16IRX8 82WR    | [239b46961f](https://linux-hardware.org/?probe=239b46961f) | Sep 01, 2023 |
| Lenovo        | ThinkPad X270 20HMS6AT00    | [e111bad271](https://linux-hardware.org/?probe=e111bad271) | Sep 01, 2023 |
| HP            | EliteBook 860 16 inch G9... | [5e0da96bdd](https://linux-hardware.org/?probe=5e0da96bdd) | Sep 01, 2023 |
| Dell          | Latitude 5290 2-in-1        | [3a4c0e0930](https://linux-hardware.org/?probe=3a4c0e0930) | Aug 31, 2023 |
| Apple         | MacBook9,1                  | [b6a28c1e1a](https://linux-hardware.org/?probe=b6a28c1e1a) | Aug 31, 2023 |
| Dell          | Latitude 5290 2-in-1        | [5b632410e7](https://linux-hardware.org/?probe=5b632410e7) | Aug 31, 2023 |
| ASUSTek       | ASUS EXPERTBOOK L2402CYA... | [9881dd3268](https://linux-hardware.org/?probe=9881dd3268) | Aug 31, 2023 |
| Lenovo        | ThinkPad L470 20J40010GE    | [53adc42d66](https://linux-hardware.org/?probe=53adc42d66) | Aug 31, 2023 |
| Dell          | Latitude 5590               | [59d99ec581](https://linux-hardware.org/?probe=59d99ec581) | Aug 31, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [c3d8f5daca](https://linux-hardware.org/?probe=c3d8f5daca) | Aug 31, 2023 |
| Lenovo        | ThinkPad L450 20DSS0LR00    | [a85743e60e](https://linux-hardware.org/?probe=a85743e60e) | Aug 31, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [f94ed7f5d1](https://linux-hardware.org/?probe=f94ed7f5d1) | Aug 31, 2023 |
| System76      | Lemur Pro                   | [c04af9751f](https://linux-hardware.org/?probe=c04af9751f) | Aug 31, 2023 |
| Apple         | MacBookPro15,2              | [a93751de6d](https://linux-hardware.org/?probe=a93751de6d) | Aug 30, 2023 |
| HP            | EliteBook 845 14 inch G9... | [4c595a576a](https://linux-hardware.org/?probe=4c595a576a) | Aug 30, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [78e163bc13](https://linux-hardware.org/?probe=78e163bc13) | Aug 30, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [0842215d23](https://linux-hardware.org/?probe=0842215d23) | Aug 30, 2023 |
| Acer          | TravelMate P259-MG          | [dc9b122d90](https://linux-hardware.org/?probe=dc9b122d90) | Aug 30, 2023 |
| Dell          | Latitude 5430               | [477898be1f](https://linux-hardware.org/?probe=477898be1f) | Aug 30, 2023 |
| Dell          | Latitude 5480               | [88c6621b31](https://linux-hardware.org/?probe=88c6621b31) | Aug 29, 2023 |
| Dell          | Precision 5480              | [5fd5bf187d](https://linux-hardware.org/?probe=5fd5bf187d) | Aug 29, 2023 |
| Lenovo        | ThinkBook 14 G4+ IAP 21C... | [0eeb1276f0](https://linux-hardware.org/?probe=0eeb1276f0) | Aug 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [d036282290](https://linux-hardware.org/?probe=d036282290) | Aug 29, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [7e48b59643](https://linux-hardware.org/?probe=7e48b59643) | Aug 29, 2023 |
| Timi          | A34S                        | [eb6a3c2430](https://linux-hardware.org/?probe=eb6a3c2430) | Aug 29, 2023 |
| Acer          | Aspire E1-571               | [3208c59e9c](https://linux-hardware.org/?probe=3208c59e9c) | Aug 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d627b8c625](https://linux-hardware.org/?probe=d627b8c625) | Aug 28, 2023 |
| Dell          | XPS 15 9510                 | [4b78bfab47](https://linux-hardware.org/?probe=4b78bfab47) | Aug 28, 2023 |
| Dell          | Latitude E6400              | [2af0a423ef](https://linux-hardware.org/?probe=2af0a423ef) | Aug 28, 2023 |
| Dell          | XPS 15 9560                 | [8288d35dff](https://linux-hardware.org/?probe=8288d35dff) | Aug 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [5fddb9cc18](https://linux-hardware.org/?probe=5fddb9cc18) | Aug 28, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [a762e96941](https://linux-hardware.org/?probe=a762e96941) | Aug 28, 2023 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [40c64b6ec2](https://linux-hardware.org/?probe=40c64b6ec2) | Aug 28, 2023 |
| Acer          | Nitro AN515-57              | [7608fab281](https://linux-hardware.org/?probe=7608fab281) | Aug 28, 2023 |
| Lenovo        | IdeaPad 1 14IAU7 82QC       | [90e0cad295](https://linux-hardware.org/?probe=90e0cad295) | Aug 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [da73419cb5](https://linux-hardware.org/?probe=da73419cb5) | Aug 27, 2023 |
| Framework     | Laptop                      | [b3e9d2d48d](https://linux-hardware.org/?probe=b3e9d2d48d) | Aug 27, 2023 |
| Corsair       | Voyager a1600               | [405bce7897](https://linux-hardware.org/?probe=405bce7897) | Aug 27, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [8acc158836](https://linux-hardware.org/?probe=8acc158836) | Aug 27, 2023 |
| HP            | Laptop 15s-eq2xxx           | [864a9d9f37](https://linux-hardware.org/?probe=864a9d9f37) | Aug 27, 2023 |
| ASUSTek       | T100TA                      | [69d14b429e](https://linux-hardware.org/?probe=69d14b429e) | Aug 27, 2023 |
| Dell          | Latitude E6400              | [fdcbc50452](https://linux-hardware.org/?probe=fdcbc50452) | Aug 27, 2023 |
| ASUSTek       | GL753VD                     | [3903bc9e14](https://linux-hardware.org/?probe=3903bc9e14) | Aug 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | [fe02fb8d64](https://linux-hardware.org/?probe=fe02fb8d64) | Aug 27, 2023 |
| Timi          | TM1701                      | [2a6a4225a0](https://linux-hardware.org/?probe=2a6a4225a0) | Aug 27, 2023 |
| Timi          | TM1701                      | [8ea7c21e18](https://linux-hardware.org/?probe=8ea7c21e18) | Aug 27, 2023 |
| HP            | Pavilion 15                 | [1731ba4ae5](https://linux-hardware.org/?probe=1731ba4ae5) | Aug 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [5d220003c1](https://linux-hardware.org/?probe=5d220003c1) | Aug 27, 2023 |
| HP            | Pavilion 15                 | [0f51268684](https://linux-hardware.org/?probe=0f51268684) | Aug 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [a8600db157](https://linux-hardware.org/?probe=a8600db157) | Aug 27, 2023 |
| ASUSTek       | K55VD                       | [7bdfc94045](https://linux-hardware.org/?probe=7bdfc94045) | Aug 27, 2023 |
| Lenovo        | IdeaPad Z570 1024DCU        | [8a11757d37](https://linux-hardware.org/?probe=8a11757d37) | Aug 26, 2023 |
| Corsair       | Voyager a1600               | [97a1c576f7](https://linux-hardware.org/?probe=97a1c576f7) | Aug 26, 2023 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | [4e5f7a05c6](https://linux-hardware.org/?probe=4e5f7a05c6) | Aug 26, 2023 |
| ASUSTek       | Strix 17 GL703GE            | [b2ad72336f](https://linux-hardware.org/?probe=b2ad72336f) | Aug 26, 2023 |
| HP            | OMEN by Laptop              | [df71a92503](https://linux-hardware.org/?probe=df71a92503) | Aug 26, 2023 |
| Acer          | Aspire A715-72G             | [cbbaecabb1](https://linux-hardware.org/?probe=cbbaecabb1) | Aug 26, 2023 |
| ASUSTek       | X542BP                      | [58cc535a58](https://linux-hardware.org/?probe=58cc535a58) | Aug 26, 2023 |
| Chuwi         | CoreBook X                  | [95548b426e](https://linux-hardware.org/?probe=95548b426e) | Aug 26, 2023 |
| Chuwi         | CoreBook X                  | [6bd0ecde29](https://linux-hardware.org/?probe=6bd0ecde29) | Aug 26, 2023 |
| Acer          | Predator PH16-71            | [ef267bc627](https://linux-hardware.org/?probe=ef267bc627) | Aug 26, 2023 |
| Apple         | MacBookPro13,2              | [b910d52198](https://linux-hardware.org/?probe=b910d52198) | Aug 26, 2023 |
| Acer          | Nitro AN515-44              | [b14dfb0798](https://linux-hardware.org/?probe=b14dfb0798) | Aug 25, 2023 |
| Acer          | Aspire ES1-512              | [22187e6de0](https://linux-hardware.org/?probe=22187e6de0) | Aug 25, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [810ccd6f4f](https://linux-hardware.org/?probe=810ccd6f4f) | Aug 25, 2023 |
| Dell          | Latitude 3490               | [05705b1834](https://linux-hardware.org/?probe=05705b1834) | Aug 25, 2023 |
| ASUSTek       | T100TA                      | [ef7b263d48](https://linux-hardware.org/?probe=ef7b263d48) | Aug 25, 2023 |
| Toshiba       | Satellite C70-B             | [2647e2edd8](https://linux-hardware.org/?probe=2647e2edd8) | Aug 24, 2023 |
| Dell          | G15 5510                    | [f9e857e751](https://linux-hardware.org/?probe=f9e857e751) | Aug 24, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [7e6a7de337](https://linux-hardware.org/?probe=7e6a7de337) | Aug 24, 2023 |
| Sony          | SVF15A1M2ES                 | [b352453232](https://linux-hardware.org/?probe=b352453232) | Aug 24, 2023 |
| Dell          | Inspiron 5759               | [bf7413fc5f](https://linux-hardware.org/?probe=bf7413fc5f) | Aug 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [1a9c135840](https://linux-hardware.org/?probe=1a9c135840) | Aug 24, 2023 |
| LDLC          | SPC-I                       | [bb114215e6](https://linux-hardware.org/?probe=bb114215e6) | Aug 24, 2023 |
| Lenovo        | ThinkPad T560 20FJS18V00    | [5f18850003](https://linux-hardware.org/?probe=5f18850003) | Aug 24, 2023 |
| Lenovo        | ThinkPad T560 20FJS18V00    | [de37c3c7eb](https://linux-hardware.org/?probe=de37c3c7eb) | Aug 24, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [ce5f964a0c](https://linux-hardware.org/?probe=ce5f964a0c) | Aug 24, 2023 |
| Dell          | Latitude 3490               | [148d4806cb](https://linux-hardware.org/?probe=148d4806cb) | Aug 24, 2023 |
| HP            | 255 G8 Notebook PC          | [68c01672c3](https://linux-hardware.org/?probe=68c01672c3) | Aug 24, 2023 |
| Xplore        | iX104C6                     | [5d8ea1a454](https://linux-hardware.org/?probe=5d8ea1a454) | Aug 24, 2023 |
| Lenovo        | Yoga710-14ISK 80TY          | [17525a9aef](https://linux-hardware.org/?probe=17525a9aef) | Aug 24, 2023 |
| Positivo B... | VJFE59F11X-B0411H           | [5e5059f835](https://linux-hardware.org/?probe=5e5059f835) | Aug 23, 2023 |
| Lenovo        | ThinkPad X200 74591P0       | [adda6295fb](https://linux-hardware.org/?probe=adda6295fb) | Aug 23, 2023 |
| Acer          | Predator PT715-51           | [e187e199c9](https://linux-hardware.org/?probe=e187e199c9) | Aug 23, 2023 |
| Dell          | XPS 15 7590                 | [66b46e04d3](https://linux-hardware.org/?probe=66b46e04d3) | Aug 23, 2023 |
| Google        | Nami                        | [db2c6bfb0a](https://linux-hardware.org/?probe=db2c6bfb0a) | Aug 23, 2023 |
| HUAWEI        | BOM-WXX9                    | [08801db21d](https://linux-hardware.org/?probe=08801db21d) | Aug 23, 2023 |
| HUAWEI        | BOM-WXX9                    | [9b3cf2a525](https://linux-hardware.org/?probe=9b3cf2a525) | Aug 23, 2023 |
| Lenovo        | Legion Y9000P IAH7H 82RF    | [f429d18938](https://linux-hardware.org/?probe=f429d18938) | Aug 23, 2023 |
| Dell          | Inspiron 5559               | [310e1f561c](https://linux-hardware.org/?probe=310e1f561c) | Aug 22, 2023 |
| HUAWEI        | BOHB-WAX9                   | [f7580a556b](https://linux-hardware.org/?probe=f7580a556b) | Aug 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [68d28831a5](https://linux-hardware.org/?probe=68d28831a5) | Aug 22, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [25d163ad9e](https://linux-hardware.org/?probe=25d163ad9e) | Aug 22, 2023 |
| Google        | Nami                        | [69d8c7bfb8](https://linux-hardware.org/?probe=69d8c7bfb8) | Aug 22, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [9ad109a4df](https://linux-hardware.org/?probe=9ad109a4df) | Aug 22, 2023 |
| HP            | Pavilion 11 x360 PC         | [bf401f98a7](https://linux-hardware.org/?probe=bf401f98a7) | Aug 22, 2023 |
| HP            | EliteBook 8440p             | [f35c644052](https://linux-hardware.org/?probe=f35c644052) | Aug 22, 2023 |
| HP            | EliteBook 8440p             | [4f4bed768e](https://linux-hardware.org/?probe=4f4bed768e) | Aug 22, 2023 |
| Dell          | Latitude 7430               | [1ccbb8329f](https://linux-hardware.org/?probe=1ccbb8329f) | Aug 22, 2023 |
| HP            | ProBook 655 G1              | [39dbb86112](https://linux-hardware.org/?probe=39dbb86112) | Aug 22, 2023 |
| HP            | ProBook 655 G1              | [2d616412f1](https://linux-hardware.org/?probe=2d616412f1) | Aug 22, 2023 |
| Dell          | Inspiron 5567               | [76c16d7ffe](https://linux-hardware.org/?probe=76c16d7ffe) | Aug 22, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora_38/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 6.2.9-300.fc38.x86_64  | 220       | 11.18%  |
| 6.2.15-300.fc38.x86_64 | 142       | 7.22%   |
| 6.3.8-200.fc38.x86_64  | 114       | 5.79%   |
| 6.4.15-200.fc38.x86_64 | 102       | 5.18%   |
| 6.5.5-200.fc38.x86_64  | 90        | 4.57%   |
| 6.2.14-300.fc38.x86_64 | 90        | 4.57%   |
| 6.2.11-300.fc38.x86_64 | 87        | 4.42%   |
| 6.5.8-200.fc38.x86_64  | 67        | 3.4%    |
| 6.3.12-200.fc38.x86_64 | 67        | 3.4%    |
| 6.4.6-200.fc38.x86_64  | 57        | 2.9%    |
| 6.5.6-200.fc38.x86_64  | 52        | 2.64%   |
| 6.3.11-200.fc38.x86_64 | 52        | 2.64%   |
| 6.4.14-200.fc38.x86_64 | 51        | 2.59%   |
| 6.5.7-200.fc38.x86_64  | 49        | 2.49%   |
| 6.3.5-200.fc38.x86_64  | 48        | 2.44%   |
| 6.4.7-200.fc38.x86_64  | 47        | 2.39%   |
| 6.4.11-200.fc38.x86_64 | 47        | 2.39%   |
| 6.2.13-300.fc38.x86_64 | 45        | 2.29%   |
| 6.4.13-200.fc38.x86_64 | 44        | 2.24%   |
| 6.4.10-200.fc38.x86_64 | 43        | 2.18%   |
| 6.3.6-200.fc38.x86_64  | 43        | 2.18%   |
| 6.4.12-200.fc38.x86_64 | 42        | 2.13%   |
| 6.2.12-300.fc38.x86_64 | 34        | 1.73%   |
| 6.5.9-200.fc38.x86_64  | 30        | 1.52%   |
| 6.4.4-200.fc38.x86_64  | 27        | 1.37%   |
| 6.4.9-200.fc38.x86_64  | 25        | 1.27%   |
| 6.3.4-201.fc38.x86_64  | 25        | 1.27%   |
| 6.5.10-200.fc38.x86_64 | 22        | 1.12%   |
| 6.3.7-200.fc38.x86_64  | 22        | 1.12%   |
| 6.6.6-100.fc38.x86_64  | 10        | 0.51%   |
| 6.2.8-300.fc38.x86_64  | 9         | 0.46%   |
| 6.6.8-100.fc38.x86_64  | 8         | 0.41%   |
| 6.4.8-200.fc38.x86_64  | 7         | 0.36%   |
| 6.2.10-300.fc38.x86_64 | 7         | 0.36%   |
| 6.2.6-300.fc38.x86_64  | 6         | 0.3%    |
| 6.8.7-100.fc38.x86_64  | 5         | 0.25%   |
| 6.7.7-100.fc38.x86_64  | 5         | 0.25%   |
| 6.6.7-100.fc38.x86_64  | 5         | 0.25%   |
| 6.6.4-100.fc38.x86_64  | 5         | 0.25%   |
| 6.7.9-100.fc38.x86_64  | 4         | 0.2%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2.9   | 220       | 11.18%  |
| 6.2.15  | 148       | 7.52%   |
| 6.3.8   | 115       | 5.84%   |
| 6.4.15  | 102       | 5.18%   |
| 6.5.5   | 92        | 4.67%   |
| 6.2.14  | 92        | 4.67%   |
| 6.2.11  | 89        | 4.52%   |
| 6.5.8   | 67        | 3.4%    |
| 6.3.12  | 67        | 3.4%    |
| 6.4.6   | 57        | 2.9%    |
| 6.5.6   | 52        | 2.64%   |
| 6.3.11  | 52        | 2.64%   |
| 6.4.14  | 51        | 2.59%   |
| 6.5.7   | 49        | 2.49%   |
| 6.4.7   | 48        | 2.44%   |
| 6.3.5   | 48        | 2.44%   |
| 6.4.11  | 47        | 2.39%   |
| 6.4.13  | 45        | 2.29%   |
| 6.4.10  | 45        | 2.29%   |
| 6.2.13  | 45        | 2.29%   |
| 6.3.6   | 44        | 2.24%   |
| 6.4.12  | 43        | 2.18%   |
| 6.2.12  | 34        | 1.73%   |
| 6.5.9   | 30        | 1.52%   |
| 6.4.4   | 27        | 1.37%   |
| 6.4.9   | 25        | 1.27%   |
| 6.3.4   | 25        | 1.27%   |
| 6.5.10  | 22        | 1.12%   |
| 6.3.7   | 22        | 1.12%   |
| 6.6.6   | 10        | 0.51%   |
| 6.2.8   | 9         | 0.46%   |
| 6.6.8   | 8         | 0.41%   |
| 6.2.10  | 8         | 0.41%   |
| 6.2.0   | 8         | 0.41%   |
| 6.4.8   | 7         | 0.36%   |
| 6.2.6   | 6         | 0.3%    |
| 6.8.7   | 5         | 0.25%   |
| 6.7.7   | 5         | 0.25%   |
| 6.6.7   | 5         | 0.25%   |
| 6.6.4   | 5         | 0.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2     | 647       | 33.73%  |
| 6.4     | 485       | 25.29%  |
| 6.3     | 376       | 19.6%   |
| 6.5     | 321       | 16.74%  |
| 6.6     | 48        | 2.5%    |
| 6.7     | 21        | 1.09%   |
| 6.8     | 7         | 0.36%   |
| 6.0     | 6         | 0.31%   |
| 6.1     | 3         | 0.16%   |
| 5.4     | 1         | 0.05%   |
| 5.19    | 1         | 0.05%   |
| 5.15    | 1         | 0.05%   |
| 5.10    | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 1796      | 99.89%  |
| aarch64 | 2         | 0.11%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 1425      | 78.6%   |
| KDE5          | 256       | 14.12%  |
| Unknown       | 31        | 1.71%   |
| XFCE          | 26        | 1.43%   |
| X-Cinnamon    | 23        | 1.27%   |
| Cinnamon      | 11        | 0.61%   |
| GNOME Classic | 8         | 0.44%   |
| MATE          | 7         | 0.39%   |
| sway          | 6         | 0.33%   |
| Budgie        | 5         | 0.28%   |
| LXDE          | 4         | 0.22%   |
| i3            | 3         | 0.17%   |
| Hyprland      | 3         | 0.17%   |
| LXQt          | 2         | 0.11%   |
| Unity         | 1         | 0.06%   |
| Pantheon      | 1         | 0.06%   |
| KDE4          | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 1483      | 81.75%  |
| X11     | 299       | 16.48%  |
| Unknown | 18        | 0.99%   |
| Tty     | 13        | 0.72%   |
| Xcb     | 1         | 0.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1134      | 62.51%  |
| GDM     | 483       | 26.63%  |
| SDDM    | 125       | 6.89%   |
| LightDM | 68        | 3.75%   |
| LXDM    | 3         | 0.17%   |
| SLiM    | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 944       | 52.18%  |
| en_GB   | 136       | 7.52%   |
| ru_RU   | 92        | 5.09%   |
| pt_BR   | 86        | 4.75%   |
| de_DE   | 81        | 4.48%   |
| fr_FR   | 53        | 2.93%   |
| it_IT   | 43        | 2.38%   |
| es_ES   | 33        | 1.82%   |
| es_MX   | 29        | 1.6%    |
| en_CA   | 25        | 1.38%   |
| en_IN   | 24        | 1.33%   |
| en_AU   | 24        | 1.33%   |
| pl_PL   | 23        | 1.27%   |
| es_CL   | 21        | 1.16%   |
| es_CO   | 14        | 0.77%   |
| en_DK   | 14        | 0.77%   |
| pt_PT   | 12        | 0.66%   |
| zh_CN   | 9         | 0.5%    |
| cs_CZ   | 9         | 0.5%    |
| tr_TR   | 8         | 0.44%   |
| hu_HU   | 8         | 0.44%   |
| Unknown | 8         | 0.44%   |
| es_PE   | 7         | 0.39%   |
| es_AR   | 7         | 0.39%   |
| de_AT   | 7         | 0.39%   |
| ru_UA   | 6         | 0.33%   |
| fr_CA   | 6         | 0.33%   |
| sk_SK   | 5         | 0.28%   |
| en_IE   | 5         | 0.28%   |
| nl_NL   | 4         | 0.22%   |
| id_ID   | 4         | 0.22%   |
| en_ZA   | 4         | 0.22%   |
| en_PH   | 4         | 0.22%   |
| nl_BE   | 3         | 0.17%   |
| ja_JP   | 3         | 0.17%   |
| es_UY   | 3         | 0.17%   |
| es_EC   | 3         | 0.17%   |
| en_SG   | 3         | 0.17%   |
| en_NZ   | 3         | 0.17%   |
| da_DK   | 3         | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1518      | 83.59%  |
| BIOS | 298       | 16.41%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 1529      | 84.94%  |
| Ext4    | 240       | 13.33%  |
| Xfs     | 29        | 1.61%   |
| Overlay | 1         | 0.06%   |
| Unknown | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1105      | 61.02%  |
| GPT     | 679       | 37.49%  |
| MBR     | 27        | 1.49%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1671      | 92.78%  |
| Yes       | 130       | 7.22%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1541      | 85.56%  |
| Yes       | 260       | 14.44%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 493       | 27.42%  |
| Dell                   | 285       | 15.85%  |
| Hewlett-Packard        | 269       | 14.96%  |
| ASUSTek Computer       | 223       | 12.4%   |
| Acer                   | 109       | 6.06%   |
| Apple                  | 84        | 4.67%   |
| HUAWEI                 | 49        | 2.73%   |
| MSI                    | 46        | 2.56%   |
| Samsung Electronics    | 27        | 1.5%    |
| Timi                   | 20        | 1.11%   |
| Toshiba                | 17        | 0.95%   |
| Google                 | 17        | 0.95%   |
| Sony                   | 12        | 0.67%   |
| Framework              | 11        | 0.61%   |
| Unknown                | 9         | 0.5%    |
| Notebook               | 8         | 0.44%   |
| Gigabyte Technology    | 8         | 0.44%   |
| Fujitsu                | 7         | 0.39%   |
| System76               | 6         | 0.33%   |
| Chuwi                  | 6         | 0.33%   |
| TUXEDO                 | 5         | 0.28%   |
| Schenker               | 4         | 0.22%   |
| Razer                  | 4         | 0.22%   |
| Positivo Bahia - VAIO  | 4         | 0.22%   |
| Positivo               | 4         | 0.22%   |
| HONOR                  | 4         | 0.22%   |
| PC Specialist          | 3         | 0.17%   |
| Maibenben              | 3         | 0.17%   |
| GPU Company            | 3         | 0.17%   |
| Avell High Performance | 3         | 0.17%   |
| Alienware              | 3         | 0.17%   |
| Valve                  | 2         | 0.11%   |
| UNOWHY                 | 2         | 0.11%   |
| Packard Bell           | 2         | 0.11%   |
| MECHREVO               | 2         | 0.11%   |
| LDLC                   | 2         | 0.11%   |
| Intel Client Systems   | 2         | 0.11%   |
| Corsair                | 2         | 0.11%   |
| Xplore                 | 1         | 0.06%   |
| XIAOMI                 | 1         | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Unknown                                 | 13        | 0.72%   |
| Apple MacBookPro9,2                     | 12        | 0.67%   |
| HP Notebook                             | 10        | 0.56%   |
| Apple MacBookPro8,1                     | 10        | 0.56%   |
| Framework Laptop                        | 8         | 0.44%   |
| Dell XPS 13 9310                        | 7         | 0.39%   |
| Lenovo IdeaPad 3 15ITL6 82H8            | 6         | 0.33%   |
| Dell Latitude 5420                      | 6         | 0.33%   |
| Apple MacBookAir7,2                     | 6         | 0.33%   |
| Samsung 550XDA                          | 5         | 0.28%   |
| HUAWEI CREM-WXX9                        | 5         | 0.28%   |
| HP EliteBook 840 G6                     | 5         | 0.28%   |
| HP EliteBook 840 G2                     | 5         | 0.28%   |
| Dell Latitude 7490                      | 5         | 0.28%   |
| Apple MacBookPro12,1                    | 5         | 0.28%   |
| Apple MacBookPro11,1                    | 5         | 0.28%   |
| Timi Redmi Book Pro 14 2022             | 4         | 0.22%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ        | 4         | 0.22%   |
| Lenovo IdeaPad 3 15ALC6 82MF            | 4         | 0.22%   |
| HUAWEI HVY-WXX9                         | 4         | 0.22%   |
| HUAWEI BOM-WXX9                         | 4         | 0.22%   |
| HP Victus by Laptop 16-e0xxx            | 4         | 0.22%   |
| HP ProBook 450 15.6 inch G9 Notebook PC | 4         | 0.22%   |
| HP ProBook 445 G8 Notebook PC           | 4         | 0.22%   |
| HP Pavilion Notebook                    | 4         | 0.22%   |
| HP Pavilion Aero Laptop 13-be0xxx       | 4         | 0.22%   |
| HP 255 G8 Notebook PC                   | 4         | 0.22%   |
| Dell XPS 9320                           | 4         | 0.22%   |
| Dell XPS 15 9560                        | 4         | 0.22%   |
| Dell XPS 15 9500                        | 4         | 0.22%   |
| Dell XPS 13 9380                        | 4         | 0.22%   |
| Dell XPS 13 9305                        | 4         | 0.22%   |
| Dell Latitude E7470                     | 4         | 0.22%   |
| Dell Latitude E7450                     | 4         | 0.22%   |
| Dell Latitude 5490                      | 4         | 0.22%   |
| Dell Inspiron 15 5510                   | 4         | 0.22%   |
| ASUS Vivobook Go E1504FA_E1504FA        | 4         | 0.22%   |
| Apple MacBookPro5,5                     | 4         | 0.22%   |
| Acer Nitro AN515-55                     | 4         | 0.22%   |
| Acer Aspire A515-45                     | 4         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 260       | 14.46%  |
| Lenovo IdeaPad     | 110       | 6.12%   |
| Dell Latitude      | 103       | 5.73%   |
| ASUS VivoBook      | 71        | 3.95%   |
| Dell Inspiron      | 69        | 3.84%   |
| Acer Aspire        | 66        | 3.67%   |
| HP Pavilion        | 54        | 3%      |
| HP EliteBook       | 54        | 3%      |
| Dell XPS           | 53        | 2.95%   |
| ASUS ROG           | 44        | 2.45%   |
| Lenovo Legion      | 38        | 2.11%   |
| HP Laptop          | 38        | 2.11%   |
| HP ProBook         | 35        | 1.95%   |
| Dell Precision     | 28        | 1.56%   |
| ASUS ASUS          | 27        | 1.5%    |
| Lenovo ThinkBook   | 20        | 1.11%   |
| Acer Nitro         | 20        | 1.11%   |
| Lenovo Yoga        | 19        | 1.06%   |
| ASUS Zenbook       | 19        | 1.06%   |
| Toshiba Satellite  | 13        | 0.72%   |
| Apple MacBookPro9  | 13        | 0.72%   |
| Unknown            | 13        | 0.72%   |
| HP ENVY            | 12        | 0.67%   |
| Dell Vostro        | 12        | 0.67%   |
| Apple MacBookPro8  | 12        | 0.67%   |
| HP ZBook           | 11        | 0.61%   |
| HP OMEN            | 11        | 0.61%   |
| Framework Laptop   | 11        | 0.61%   |
| HP Notebook        | 10        | 0.56%   |
| MSI Modern         | 9         | 0.5%    |
| Apple MacBookPro11 | 9         | 0.5%    |
| HP 255             | 8         | 0.44%   |
| Dell G15           | 8         | 0.44%   |
| ASUS TUF           | 8         | 0.44%   |
| Acer Swift         | 8         | 0.44%   |
| Acer Predator      | 7         | 0.39%   |
| Timi Redmi         | 6         | 0.33%   |
| MSI Prestige       | 6         | 0.33%   |
| HP Victus          | 6         | 0.33%   |
| Apple MacBookPro5  | 6         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 284       | 15.8%   |
| 2022    | 244       | 13.57%  |
| 2020    | 221       | 12.29%  |
| 2019    | 149       | 8.29%   |
| 2018    | 143       | 7.95%   |
| 2023    | 115       | 6.4%    |
| 2012    | 99        | 5.51%   |
| 2017    | 98        | 5.45%   |
| 2014    | 81        | 4.51%   |
| 2013    | 73        | 4.06%   |
| 2015    | 70        | 3.89%   |
| 2011    | 65        | 3.62%   |
| 2016    | 61        | 3.39%   |
| 2010    | 32        | 1.78%   |
| 2009    | 23        | 1.28%   |
| 2008    | 23        | 1.28%   |
| 2007    | 15        | 0.83%   |
| 2006    | 1         | 0.06%   |
| Unknown | 1         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1798      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1345      | 74.19%  |
| Enabled  | 468       | 25.81%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1775      | 98.72%  |
| Yes  | 23        | 1.28%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 505       | 27.98%  |
| 16.01-24.0  | 399       | 22.11%  |
| 8.01-16.0   | 373       | 20.66%  |
| 32.01-64.0  | 234       | 12.96%  |
| 3.01-4.0    | 176       | 9.75%   |
| 24.01-32.0  | 49        | 2.71%   |
| 64.01-256.0 | 34        | 1.88%   |
| 1.01-2.0    | 27        | 1.5%    |
| 2.01-3.0    | 8         | 0.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 583       | 30.51%  |
| 2.01-3.0   | 500       | 26.16%  |
| 3.01-4.0   | 465       | 24.33%  |
| 1.01-2.0   | 201       | 10.52%  |
| 8.01-16.0  | 143       | 7.48%   |
| 0.51-1.0   | 9         | 0.47%   |
| 16.01-24.0 | 7         | 0.37%   |
| 24.01-32.0 | 2         | 0.1%    |
| 0.01-0.5   | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1355      | 74.9%   |
| 2      | 401       | 22.17%  |
| 3      | 35        | 1.93%   |
| 4      | 8         | 0.44%   |
| 5      | 4         | 0.22%   |
| 0      | 3         | 0.17%   |
| 6      | 2         | 0.11%   |
| 8      | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1484      | 82.44%  |
| Yes       | 316       | 17.56%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1285      | 71.15%  |
| No        | 521       | 28.85%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1772      | 98.5%   |
| No        | 27        | 1.5%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1558      | 86.17%  |
| No        | 250       | 13.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 272       | 15.06%  |
| Germany     | 137       | 7.59%   |
| Brazil      | 122       | 6.76%   |
| Russia      | 111       | 6.15%   |
| Italy       | 81        | 4.49%   |
| India       | 76        | 4.21%   |
| UK          | 69        | 3.82%   |
| France      | 66        | 3.65%   |
| Canada      | 55        | 3.05%   |
| Mexico      | 53        | 2.93%   |
| Spain       | 51        | 2.82%   |
| Poland      | 47        | 2.6%    |
| Netherlands | 44        | 2.44%   |
| Turkey      | 35        | 1.94%   |
| Czechia     | 28        | 1.55%   |
| Chile       | 27        | 1.5%    |
| Australia   | 27        | 1.5%    |
| Colombia    | 23        | 1.27%   |
| Portugal    | 21        | 1.16%   |
| Indonesia   | 18        | 1%      |
| Switzerland | 17        | 0.94%   |
| Hungary     | 17        | 0.94%   |
| Denmark     | 17        | 0.94%   |
| Belgium     | 17        | 0.94%   |
| Austria     | 16        | 0.89%   |
| Bulgaria    | 15        | 0.83%   |
| Sweden      | 14        | 0.78%   |
| Romania     | 14        | 0.78%   |
| Argentina   | 13        | 0.72%   |
| Philippines | 12        | 0.66%   |
| Finland     | 12        | 0.66%   |
| Norway      | 11        | 0.61%   |
| Israel      | 11        | 0.61%   |
| Belarus     | 11        | 0.61%   |
| Egypt       | 10        | 0.55%   |
| China       | 10        | 0.55%   |
| Peru        | 8         | 0.44%   |
| Ireland     | 8         | 0.44%   |
| Iran        | 8         | 0.44%   |
| Vietnam     | 7         | 0.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Moscow           | 27        | 1.47%   |
| Berlin           | 20        | 1.09%   |
| Santiago         | 16        | 0.87%   |
| Mexico City      | 15        | 0.82%   |
| Sao Paulo        | 13        | 0.71%   |
| St Petersburg    | 12        | 0.65%   |
| Delhi            | 12        | 0.65%   |
| Sofia            | 11        | 0.6%    |
| Madrid           | 11        | 0.6%    |
| Vienna           | 10        | 0.54%   |
| Prague           | 10        | 0.54%   |
| Paris            | 10        | 0.54%   |
| Milan            | 10        | 0.54%   |
| Warsaw           | 9         | 0.49%   |
| Munich           | 9         | 0.49%   |
| Istanbul         | 9         | 0.49%   |
| Budapest         | 9         | 0.49%   |
| Sydney           | 8         | 0.44%   |
| Lisbon           | 8         | 0.44%   |
| Helsinki         | 8         | 0.44%   |
| Hamburg          | 8         | 0.44%   |
| Bengaluru        | 8         | 0.44%   |
| Amsterdam        | 8         | 0.44%   |
| Singapore        | 7         | 0.38%   |
| Rio de Janeiro   | 7         | 0.38%   |
| Montreal         | 7         | 0.38%   |
| Minsk            | 7         | 0.38%   |
| Dublin           | 7         | 0.38%   |
| Bogotá          | 7         | 0.38%   |
| Barcelona        | 7         | 0.38%   |
| Zurich           | 6         | 0.33%   |
| Toronto          | 6         | 0.33%   |
| San José        | 6         | 0.33%   |
| Nizhniy Novgorod | 6         | 0.33%   |
| Naaldwijk        | 6         | 0.33%   |
| Melbourne        | 6         | 0.33%   |
| Cologne          | 6         | 0.33%   |
| Brasília        | 6         | 0.33%   |
| Bangkok          | 6         | 0.33%   |
| Atlanta          | 6         | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 458       | 559    | 20.51%  |
| Sandisk                        | 240       | 270    | 10.75%  |
| WDC                            | 129       | 136    | 5.78%   |
| SK hynix                       | 127       | 137    | 5.69%   |
| Micron Technology              | 126       | 138    | 5.64%   |
| Seagate                        | 124       | 138    | 5.55%   |
| Kingston                       | 111       | 127    | 4.97%   |
| Toshiba                        | 108       | 124    | 4.84%   |
| Unknown                        | 106       | 123    | 4.75%   |
| Intel                          | 97        | 115    | 4.34%   |
| Crucial                        | 48        | 57     | 2.15%   |
| Apple                          | 45        | 59     | 2.02%   |
| KIOXIA                         | 38        | 47     | 1.7%    |
| Phison Electronics             | 35        | 36     | 1.57%   |
| Micron/Crucial Technology      | 30        | 31     | 1.34%   |
| HGST                           | 27        | 27     | 1.21%   |
| Kingston Technology Company    | 25        | 28     | 1.12%   |
| Silicon Motion                 | 23        | 23     | 1.03%   |
| China                          | 23        | 29     | 1.03%   |
| A-DATA Technology              | 23        | 25     | 1.03%   |
| ADATA Technology               | 17        | 19     | 0.76%   |
| Hitachi                        | 14        | 15     | 0.63%   |
| JMicron Technology             | 12        | 15     | 0.54%   |
| Solid State Storage            | 10        | 11     | 0.45%   |
| Netac                          | 10        | 11     | 0.45%   |
| SPCC                           | 9         | 9      | 0.4%    |
| Solid State Storage Technology | 8         | 8      | 0.36%   |
| PNY                            | 8         | 8      | 0.36%   |
| Phison                         | 8         | 10     | 0.36%   |
| MAXIO Technology (Hangzhou)    | 8         | 8      | 0.36%   |
| LITEON                         | 8         | 9      | 0.36%   |
| Union Memory (Shenzhen)        | 7         | 13     | 0.31%   |
| Lenovo                         | 7         | 7      | 0.31%   |
| Shenzhen Longsys Electronics   | 6         | 8      | 0.27%   |
| LITEONIT                       | 6         | 6      | 0.27%   |
| Unknown                        | 6         | 6      | 0.27%   |
| Yangtze Memory Technologies    | 5         | 5      | 0.22%   |
| Union Memory                   | 5         | 5      | 0.22%   |
| Team                           | 5         | 5      | 0.22%   |
| SABRENT                        | 5         | 5      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 105       | 4.57%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 71        | 3.09%   |
| Sandisk WD Blue SN550 NVMe SSD 2TB                    | 37        | 1.61%   |
| Seagate ST1000LM035-1RK172 1TB                        | 30        | 1.31%   |
| Unknown MMC Card  64GB                                | 28        | 1.22%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB      | 24        | 1.04%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                   | 24        | 1.04%   |
| Kingston SA400S37480G 480GB SSD                       | 24        | 1.04%   |
| Intel SSD 660P Series 1024GB                          | 24        | 1.04%   |
| Kingston SA400S37240G 240GB SSD                       | 23        | 1%      |
| Intel SSDPEKNU512GZ 512GB                             | 23        | 1%      |
| Toshiba XG6 NVMe SSD Controller 1024GB                | 22        | 0.96%   |
| Samsung SSD 980 1TB                                   | 21        | 0.91%   |
| Unknown MMC Card  128GB                               | 19        | 0.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1TB     | 19        | 0.83%   |
| Unknown MMC Card  32GB                                | 18        | 0.78%   |
| Sandisk WD Black SN850 512GB                          | 17        | 0.74%   |
| Toshiba MQ04ABF100 1TB                                | 16        | 0.7%    |
| SK hynix BC501 NVMe Solid State Drive 512GB           | 14        | 0.61%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 14        | 0.61%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 512GB       | 14        | 0.61%   |
| Phison PS5013 E13 NVMe Controller 512GB               | 14        | 0.61%   |
| Phison E12 NVMe Controller 2TB                        | 13        | 0.57%   |
| Micron 2450_MTFDKBA512TFK 512GB                       | 13        | 0.57%   |
| HGST HTS721010A9E630 1TB                              | 12        | 0.52%   |
| Seagate ST500LT012-1DG142 500GB                       | 11        | 0.48%   |
| JMicron Generic 320GB                                 | 11        | 0.48%   |
| Intel SSDPEKNW512GZL 512GB                            | 11        | 0.48%   |
| Toshiba MQ01ABF050 500GB                              | 10        | 0.44%   |
| Samsung MZVLQ512HBLU-00BH1 512GB                      | 10        | 0.44%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                  | 9         | 0.39%   |
| SK hynix BC511 256GB                                  | 9         | 0.39%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 9         | 0.39%   |
| Sandisk WD_BLACK SN770 1TB                            | 9         | 0.39%   |
| Sandisk WD Blue SN570 1TB                             | 9         | 0.39%   |
| Samsung MZALQ512HALU-000L2 512GB                      | 9         | 0.39%   |
| Micron 2450_MTFDKBA1T0TFK 1TB                         | 9         | 0.39%   |
| Micron 2210_MTFDHBA512QFD 512GB                       | 9         | 0.39%   |
| Intel SSD Pro 7600p/760p/E 6100p Series 256GB         | 9         | 0.39%   |
| Toshiba MQ01ABD100 1TB                                | 8         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 116       | 128    | 33.82%  |
| WDC                 | 88        | 93     | 25.66%  |
| Toshiba             | 59        | 66     | 17.2%   |
| HGST                | 27        | 27     | 7.87%   |
| Hitachi             | 14        | 15     | 4.08%   |
| JMicron Technology  | 11        | 13     | 3.21%   |
| SABRENT             | 5         | 5      | 1.46%   |
| Apple               | 5         | 6      | 1.46%   |
| Unknown             | 4         | 6      | 1.17%   |
| Samsung Electronics | 4         | 4      | 1.17%   |
| Fujitsu             | 3         | 3      | 0.87%   |
| XrayDisk            | 1         | 1      | 0.29%   |
| SAGE                | 1         | 1      | 0.29%   |
| QNAP                | 1         | 4      | 0.29%   |
| LIO-ORG             | 1         | 4      | 0.29%   |
| LaCie               | 1         | 1      | 0.29%   |
| IB                  | 1         | 2      | 0.29%   |
| ACASIS              | 1         | 1      | 0.29%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 116       | 138    | 20.6%   |
| Kingston            | 82        | 92     | 14.56%  |
| SanDisk             | 52        | 55     | 9.24%   |
| Crucial             | 47        | 56     | 8.35%   |
| WDC                 | 33        | 34     | 5.86%   |
| Apple               | 25        | 26     | 4.44%   |
| China               | 23        | 29     | 4.09%   |
| Micron Technology   | 17        | 18     | 3.02%   |
| Intel               | 15        | 20     | 2.66%   |
| Toshiba             | 14        | 14     | 2.49%   |
| A-DATA Technology   | 13        | 13     | 2.31%   |
| SPCC                | 9         | 9      | 1.6%    |
| PNY                 | 8         | 8      | 1.42%   |
| LITEON              | 8         | 9      | 1.42%   |
| SK hynix            | 6         | 8      | 1.07%   |
| Netac               | 6         | 6      | 1.07%   |
| LITEONIT            | 6         | 6      | 1.07%   |
| Lexar               | 5         | 5      | 0.89%   |
| Team                | 4         | 4      | 0.71%   |
| Hewlett-Packard     | 4         | 4      | 0.71%   |
| GOODRAM             | 4         | 6      | 0.71%   |
| Gigabyte Technology | 4         | 5      | 0.71%   |
| Apacer              | 4         | 5      | 0.71%   |
| Mushkin             | 3         | 3      | 0.53%   |
| MidasForce          | 3         | 3      | 0.53%   |
| KingSpec            | 3         | 4      | 0.53%   |
| Aura                | 3         | 3      | 0.53%   |
| V-GeN               | 2         | 2      | 0.36%   |
| Transcend           | 2         | 2      | 0.36%   |
| Smartbuy            | 2         | 2      | 0.36%   |
| Ramsta              | 2         | 2      | 0.36%   |
| Patriot             | 2         | 2      | 0.36%   |
| Lenovo              | 2         | 2      | 0.36%   |
| Intenso             | 2         | 2      | 0.36%   |
| Advantech           | 2         | 2      | 0.36%   |
| YS                  | 1         | 1      | 0.18%   |
| XrayDisk            | 1         | 1      | 0.18%   |
| Wibtek              | 1         | 1      | 0.18%   |
| Union Memory        | 1         | 1      | 0.18%   |
| Teclast             | 1         | 1      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1108      | 1389   | 52.61%  |
| SSD     | 531       | 633    | 25.21%  |
| HDD     | 330       | 380    | 15.67%  |
| MMC     | 102       | 116    | 4.84%   |
| Unknown | 35        | 37     | 1.66%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 1107      | 1382   | 54.13%  |
| SATA | 762       | 964    | 37.26%  |
| MMC  | 102       | 116    | 4.99%   |
| SAS  | 74        | 93     | 3.62%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 548       | 672    | 64.17%  |
| 0.51-1.0   | 271       | 305    | 31.73%  |
| 1.01-2.0   | 30        | 31     | 3.51%   |
| 3.01-4.0   | 3         | 3      | 0.35%   |
| 10.01-20.0 | 1         | 1      | 0.12%   |
| 4.01-10.0  | 1         | 1      | 0.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 442       | 24.25%  |
| 251-500        | 385       | 21.12%  |
| 1001-2000      | 265       | 14.54%  |
| 101-250        | 213       | 11.68%  |
| 1-20           | 178       | 9.76%   |
| Unknown        | 173       | 9.49%   |
| 51-100         | 60        | 3.29%   |
| More than 3000 | 49        | 2.69%   |
| 2001-3000      | 38        | 2.08%   |
| 21-50          | 20        | 1.1%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 637       | 34.12%  |
| 21-50          | 304       | 16.28%  |
| 101-250        | 243       | 13.02%  |
| 51-100         | 203       | 10.87%  |
| Unknown        | 173       | 9.27%   |
| 251-500        | 167       | 8.94%   |
| 501-1000       | 92        | 4.93%   |
| 1001-2000      | 34        | 1.82%   |
| More than 3000 | 8         | 0.43%   |
| 2001-3000      | 6         | 0.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABF050 500GB                     | 3         | 3      | 7.5%    |
| WDC WDS240G2G0A-00JH30 240GB SSD             | 2         | 2      | 5%      |
| Seagate ST500LT012-1DG142 500GB              | 2         | 2      | 5%      |
| HGST HTS721010A9E630 1TB                     | 2         | 2      | 5%      |
| YS SSD 240GB                                 | 1         | 1      | 2.5%    |
| Wibtek W800S 256GB SSD                       | 1         | 1      | 2.5%    |
| WDC WD5000LPCX-60VHAT0 500GB                 | 1         | 1      | 2.5%    |
| WDC WD5000BPVT-75HXZT1 500GB                 | 1         | 1      | 2.5%    |
| WDC WD3200BPVT-75ZEST0 320GB                 | 1         | 1      | 2.5%    |
| SSSTC CVB-8D128-HP 128GB SSD                 | 1         | 1      | 2.5%    |
| SK hynix HFS128G39TND-N210A 128GB SSD        | 1         | 1      | 2.5%    |
| Seagate ST9750420AS 752GB                    | 1         | 1      | 2.5%    |
| Seagate ST9500420AS 500GB                    | 1         | 1      | 2.5%    |
| Seagate ST1000LM049-2GH172 1TB               | 1         | 1      | 2.5%    |
| SanDisk SSD PLUS 480GB                       | 1         | 1      | 2.5%    |
| SanDisk SD8SBAT256G1122 256GB SSD            | 1         | 1      | 2.5%    |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 2.5%    |
| Samsung Electronics HD154UI 1TB              | 1         | 1      | 2.5%    |
| Netac NVMe SSD 2TB                           | 1         | 1      | 2.5%    |
| Mushkin MKNSSDCR240GB                        | 1         | 1      | 2.5%    |
| Micron Technology 1100 SATA 256GB SSD        | 1         | 1      | 2.5%    |
| LITEONIT LCT-128M3S 128GB SSD                | 1         | 1      | 2.5%    |
| LITEONIT LAT-256M2S 256GB SSD                | 1         | 1      | 2.5%    |
| Kingston SA400S37480G 480GB SSD              | 1         | 1      | 2.5%    |
| Kingston RBU-SNS8350DES3128GP 128GB SSD      | 1         | 3      | 2.5%    |
| Intel SSDSC2KF256H6 SATA 256GB               | 1         | 2      | 2.5%    |
| Intel SSDSC2BF180A5H SED 180GB               | 1         | 1      | 2.5%    |
| Intel HBRPEKNX0202AHO 32GB                   | 1         | 1      | 2.5%    |
| Hitachi HTS547575A9E384 752GB                | 1         | 1      | 2.5%    |
| Hitachi HTS545050B9A300 500GB                | 1         | 1      | 2.5%    |
| Hitachi HTS545025B9SA02 250GB                | 1         | 1      | 2.5%    |
| HGST HTS541010A9E680 1TB                     | 1         | 1      | 2.5%    |
| Crucial CT1050MX300SSD1 1050GB               | 1         | 1      | 2.5%    |
| China SSD 256GB                              | 1         | 1      | 2.5%    |
| Apple HDD HTS545050A7E362 500GB              | 1         | 1      | 2.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 12.5%   |
| Seagate             | 5         | 5      | 12.5%   |
| Toshiba             | 3         | 3      | 7.5%    |
| Intel               | 3         | 4      | 7.5%    |
| Hitachi             | 3         | 3      | 7.5%    |
| HGST                | 3         | 3      | 7.5%    |
| SanDisk             | 2         | 2      | 5%      |
| Samsung Electronics | 2         | 2      | 5%      |
| LITEONIT            | 2         | 2      | 5%      |
| Kingston            | 2         | 4      | 5%      |
| YS                  | 1         | 1      | 2.5%    |
| Wibtek              | 1         | 1      | 2.5%    |
| SSSTC               | 1         | 1      | 2.5%    |
| SK hynix            | 1         | 1      | 2.5%    |
| Netac               | 1         | 1      | 2.5%    |
| Mushkin             | 1         | 1      | 2.5%    |
| Micron Technology   | 1         | 1      | 2.5%    |
| Crucial             | 1         | 1      | 2.5%    |
| China               | 1         | 1      | 2.5%    |
| Apple               | 1         | 1      | 2.5%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 26.32%  |
| WDC                 | 3         | 3      | 15.79%  |
| Toshiba             | 3         | 3      | 15.79%  |
| Hitachi             | 3         | 3      | 15.79%  |
| HGST                | 3         | 3      | 15.79%  |
| Samsung Electronics | 1         | 1      | 5.26%   |
| Apple               | 1         | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 19        | 22     | 47.5%   |
| HDD  | 19        | 19     | 47.5%   |
| NVMe | 2         | 2      | 5%      |

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
| Detected | 1201      | 1689   | 64.05%  |
| Works    | 635       | 823    | 33.87%  |
| Malfunc  | 39        | 43     | 2.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 965       | 42.05%  |
| Samsung Electronics                     | 354       | 15.42%  |
| AMD                                     | 194       | 8.45%   |
| SanDisk                                 | 193       | 8.41%   |
| SK hynix                                | 121       | 5.27%   |
| Micron Technology                       | 109       | 4.75%   |
| Kingston Technology Company             | 56        | 2.44%   |
| Phison Electronics                      | 41        | 1.79%   |
| Toshiba America Info Systems            | 39        | 1.7%    |
| KIOXIA                                  | 36        | 1.57%   |
| Micron/Crucial Technology               | 30        | 1.31%   |
| ADATA Technology                        | 26        | 1.13%   |
| Silicon Motion                          | 25        | 1.09%   |
| Solid State Storage Technology          | 19        | 0.83%   |
| Apple                                   | 14        | 0.61%   |
| Union Memory (Shenzhen)                 | 11        | 0.48%   |
| Nvidia                                  | 10        | 0.44%   |
| MAXIO Technology (Hangzhou)             | 9         | 0.39%   |
| Shenzhen Longsys Electronics            | 6         | 0.26%   |
| Yangtze Memory Technologies             | 5         | 0.22%   |
| Realtek Semiconductor                   | 5         | 0.22%   |
| Netac Technology                        | 5         | 0.22%   |
| Marvell Technology Group                | 5         | 0.22%   |
| Lenovo                                  | 5         | 0.22%   |
| Solidigm                                | 4         | 0.17%   |
| Shenzhen Unionmemory Information System | 2         | 0.09%   |
| Seagate Technology                      | 2         | 0.09%   |
| Lite-On Technology                      | 1         | 0.04%   |
| INNOGRIT                                | 1         | 0.04%   |
| Biwin Storage Technology                | 1         | 0.04%   |
| ASMedia Technology                      | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 188       | 7.8%    |
| Intel Volume Management Device NVMe RAID Controller                            | 122       | 5.06%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 114       | 4.73%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 113       | 4.69%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 113       | 4.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 89        | 3.69%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 78        | 3.24%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 71        | 2.95%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 55        | 2.28%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 52        | 2.16%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 42        | 1.74%   |
| Intel Tiger Lake-LP SATA Controller                                            | 41        | 1.7%    |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 38        | 1.58%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 38        | 1.58%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 37        | 1.54%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 37        | 1.54%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 36        | 1.49%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 30        | 1.24%   |
| Intel Comet Lake SATA AHCI Controller                                          | 28        | 1.16%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 28        | 1.16%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 26        | 1.08%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 26        | 1.08%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 26        | 1.08%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 25        | 1.04%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 24        | 1%      |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 24        | 1%      |
| Intel SSD 660P Series                                                          | 24        | 1%      |
| Intel Alder Lake-P SATA AHCI Controller                                        | 24        | 1%      |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 22        | 0.91%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 21        | 0.87%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 21        | 0.87%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 21        | 0.87%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 20        | 0.83%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 20        | 0.83%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 19        | 0.79%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 18        | 0.75%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 17        | 0.71%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 16        | 0.66%   |
| Micron 2300 NVMe SSD [Santana]                                                 | 16        | 0.66%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 16        | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 1099      | 47.91%  |
| SATA | 944       | 41.15%  |
| RAID | 220       | 9.59%   |
| IDE  | 31        | 1.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 1355      | 75.36%  |
| AMD          | 440       | 24.47%  |
| CentaurHauls | 1         | 0.06%   |
| ARM          | 1         | 0.06%   |
| Unknown      | 1         | 0.06%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 58        | 3.22%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 34        | 1.89%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 33        | 1.83%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 32        | 1.78%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 27        | 1.5%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 25        | 1.39%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 23        | 1.28%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 23        | 1.28%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 22        | 1.22%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 21        | 1.17%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 21        | 1.17%   |
| Intel 12th Gen Core i7-12700H                 | 21        | 1.17%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 20        | 1.11%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 19        | 1.06%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 19        | 1.06%   |
| Intel 12th Gen Core i7-1255U                  | 19        | 1.06%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 18        | 1%      |
| Intel Core i5-6200U CPU @ 2.30GHz             | 18        | 1%      |
| Intel 12th Gen Core i5-12500H                 | 18        | 1%      |
| Intel 12th Gen Core i5-1235U                  | 18        | 1%      |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 18        | 1%      |
| Intel Core i7-8750H CPU @ 2.20GHz             | 17        | 0.94%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 16        | 0.89%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 16        | 0.89%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 16        | 0.89%   |
| Intel 12th Gen Core i7-1260P                  | 15        | 0.83%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 15        | 0.83%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 15        | 0.83%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 14        | 0.78%   |
| AMD Ryzen 7 5825U with Radeon Graphics        | 14        | 0.78%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 13        | 0.72%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 13        | 0.72%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 12        | 0.67%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 12        | 0.67%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 12        | 0.67%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 12        | 0.67%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 12        | 0.67%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 12        | 0.67%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 12        | 0.67%   |
| Intel 12th Gen Core i5-1240P                  | 11        | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 392       | 21.79%  |
| Other                   | 389       | 21.62%  |
| Intel Core i7           | 330       | 18.34%  |
| AMD Ryzen 7             | 159       | 8.84%   |
| AMD Ryzen 5             | 138       | 7.67%   |
| Intel Core i3           | 85        | 4.72%   |
| Intel Celeron           | 62        | 3.45%   |
| Intel Core 2 Duo        | 35        | 1.95%   |
| AMD Ryzen 9             | 34        | 1.89%   |
| AMD Ryzen 7 PRO         | 22        | 1.22%   |
| AMD Ryzen 3             | 20        | 1.11%   |
| Intel Atom              | 17        | 0.94%   |
| Intel Pentium           | 14        | 0.78%   |
| Intel Pentium Silver    | 12        | 0.67%   |
| AMD Ryzen 5 PRO         | 11        | 0.61%   |
| AMD A6                  | 11        | 0.61%   |
| AMD A10                 | 9         | 0.5%    |
| AMD A8                  | 8         | 0.44%   |
| Intel Core i9           | 7         | 0.39%   |
| AMD E2                  | 4         | 0.22%   |
| Intel Pentium Dual-Core | 3         | 0.17%   |
| Intel Pentium Dual      | 3         | 0.17%   |
| Intel Genuine           | 3         | 0.17%   |
| Intel Core m5           | 3         | 0.17%   |
| AMD E1                  | 3         | 0.17%   |
| AMD Athlon              | 3         | 0.17%   |
| AMD A4                  | 3         | 0.17%   |
| Intel Xeon              | 2         | 0.11%   |
| Intel Core m3           | 2         | 0.11%   |
| Intel Core M            | 2         | 0.11%   |
| Intel Core 2            | 2         | 0.11%   |
| Intel Celeron Dual-Core | 2         | 0.11%   |
| AMD A12                 | 2         | 0.11%   |
| Intel Core 2 Quad       | 1         | 0.06%   |
| AMD Turion II Dual-Core | 1         | 0.06%   |
| AMD Ryzen 3 PRO         | 1         | 0.06%   |
| AMD FX                  | 1         | 0.06%   |
| AMD Athlon X2           | 1         | 0.06%   |
| AMD Athlon II Dual-Core | 1         | 0.06%   |
| AMD Athlon II           | 1         | 0.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 593       | 32.98%  |
| 2      | 584       | 32.48%  |
| 8      | 250       | 13.9%   |
| 6      | 181       | 10.07%  |
| 12     | 60        | 3.34%   |
| 14     | 58        | 3.23%   |
| 10     | 58        | 3.23%   |
| 1      | 5         | 0.28%   |
| 24     | 4         | 0.22%   |
| 16     | 3         | 0.17%   |
| 20     | 1         | 0.06%   |
| 11     | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1797      | 99.94%  |
| 11     | 1         | 0.06%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1580      | 87.83%  |
| 1      | 219       | 12.17%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1796      | 99.89%  |
| 64-bit         | 2         | 0.11%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1383      | 76.62%  |
| 0x0a50000c | 71        | 3.93%   |
| 0x0a50000d | 39        | 2.16%   |
| 0x0a404102 | 38        | 2.11%   |
| 0x08608103 | 35        | 1.94%   |
| 0x08600106 | 33        | 1.83%   |
| 0x08108109 | 30        | 1.66%   |
| 0x08600104 | 18        | 1%      |
| 0x08108102 | 17        | 0.94%   |
| 0x0a404101 | 13        | 0.72%   |
| 0x06006705 | 11        | 0.61%   |
| 0x08a00008 | 9         | 0.5%    |
| 0x08608102 | 9         | 0.5%    |
| 0x08600103 | 7         | 0.39%   |
| 0x08608104 | 6         | 0.33%   |
| 0x06001119 | 6         | 0.33%   |
| 0x0a704103 | 5         | 0.28%   |
| 0x0a601203 | 5         | 0.28%   |
| 0x08600109 | 5         | 0.28%   |
| 0x0810100b | 5         | 0.28%   |
| 0x08101007 | 5         | 0.28%   |
| 0x0a50000b | 4         | 0.22%   |
| 0x0700010f | 4         | 0.22%   |
| 0x0a704101 | 3         | 0.17%   |
| 0x07030105 | 3         | 0.17%   |
| 0x06006118 | 3         | 0.17%   |
| 0x0600111f | 3         | 0.17%   |
| 0x06001116 | 3         | 0.17%   |
| 0x08900201 | 2         | 0.11%   |
| 0x08101016 | 2         | 0.11%   |
| 0x07030104 | 2         | 0.11%   |
| 0x0600611a | 2         | 0.11%   |
| 0x06006110 | 2         | 0.11%   |
| 0x906ea    | 1         | 0.06%   |
| 0x806e9    | 1         | 0.06%   |
| 0x806c1    | 1         | 0.06%   |
| 0x506c9    | 1         | 0.06%   |
| 0x406e3    | 1         | 0.06%   |
| 0x40651    | 1         | 0.06%   |
| 0x306a9    | 1         | 0.06%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 331       | 18.4%   |
| Alderlake Hybrid | 184       | 10.23%  |
| Unknown          | 155       | 8.62%   |
| TigerLake        | 153       | 8.5%    |
| Zen 3            | 120       | 6.67%   |
| IvyBridge        | 90        | 5%      |
| Haswell          | 89        | 4.95%   |
| Skylake          | 84        | 4.67%   |
| SandyBridge      | 74        | 4.11%   |
| Zen 2            | 67        | 3.72%   |
| Icelake          | 60        | 3.34%   |
| CometLake        | 54        | 3%      |
| Broadwell        | 52        | 2.89%   |
| Zen+             | 49        | 2.72%   |
| Silvermont       | 36        | 2%      |
| Penryn           | 35        | 1.95%   |
| Westmere         | 33        | 1.83%   |
| Goldmont plus    | 33        | 1.83%   |
| Excavator        | 19        | 1.06%   |
| Zen              | 16        | 0.89%   |
| Piledriver       | 12        | 0.67%   |
| Goldmont         | 12        | 0.67%   |
| Core             | 12        | 0.67%   |
| Puma             | 7         | 0.39%   |
| Tremont          | 6         | 0.33%   |
| Jaguar           | 4         | 0.22%   |
| K10              | 3         | 0.17%   |
| Steamroller      | 2         | 0.11%   |
| Nehalem          | 2         | 0.11%   |
| K8 Hammer        | 1         | 0.06%   |
| K8 & K10 hybrid  | 1         | 0.06%   |
| Gracemont        | 1         | 0.06%   |
| Bonnell          | 1         | 0.06%   |
| Bobcat           | 1         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 1282      | 55.55%  |
| Nvidia  | 539       | 23.35%  |
| AMD     | 486       | 21.06%  |
| Zhaoxin | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 141       | 5.99%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 83        | 3.53%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 80        | 3.4%    |
| Intel UHD Graphics 620                                                                   | 76        | 3.23%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 73        | 3.1%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 71        | 3.02%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 67        | 2.85%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 57        | 2.42%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 57        | 2.42%   |
| AMD Rembrandt [Radeon 680M]                                                              | 57        | 2.42%   |
| Intel HD Graphics 620                                                                    | 53        | 2.25%   |
| AMD Lucienne                                                                             | 52        | 2.21%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 51        | 2.17%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 50        | 2.13%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 50        | 2.13%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 49        | 2.08%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 48        | 2.04%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 41        | 1.74%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 39        | 1.66%   |
| Intel HD Graphics 5500                                                                   | 38        | 1.62%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 36        | 1.53%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 34        | 1.45%   |
| AMD Barcelo                                                                              | 32        | 1.36%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 29        | 1.23%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 28        | 1.19%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 27        | 1.15%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 24        | 1.02%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 24        | 1.02%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 23        | 0.98%   |
| Intel Core Processor Integrated Graphics Controller                                      | 23        | 0.98%   |
| Intel HD Graphics 630                                                                    | 21        | 0.89%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 20        | 0.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 20        | 0.85%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 18        | 0.77%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 18        | 0.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 16        | 0.68%   |
| Nvidia GP108M [GeForce MX150]                                                            | 13        | 0.55%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 13        | 0.55%   |
| Intel HD Graphics 530                                                                    | 13        | 0.55%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 13        | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 851       | 47.15%  |
| Intel + Nvidia | 380       | 21.05%  |
| 1 x AMD        | 328       | 18.17%  |
| AMD + Nvidia   | 90        | 4.99%   |
| 1 x Nvidia     | 71        | 3.93%   |
| Intel + AMD    | 40        | 2.22%   |
| 2 x AMD        | 29        | 1.61%   |
| 2 x Intel      | 9         | 0.5%    |
| Other          | 5         | 0.28%   |
| 2 x Nvidia     | 1         | 0.06%   |
| 1 x Zhaoxin    | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1524      | 84.2%   |
| Proprietary | 240       | 13.26%  |
| Unknown     | 46        | 2.54%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1119      | 61.48%  |
| 0.01-0.5   | 237       | 13.02%  |
| 1.01-2.0   | 164       | 9.01%   |
| 3.01-4.0   | 131       | 7.2%    |
| 0.51-1.0   | 95        | 5.22%   |
| 5.01-6.0   | 32        | 1.76%   |
| 7.01-8.0   | 28        | 1.54%   |
| 8.01-16.0  | 11        | 0.6%    |
| 2.01-3.0   | 3         | 0.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 409       | 19.12%  |
| AU Optronics            | 336       | 15.71%  |
| Chimei Innolux          | 302       | 14.12%  |
| LG Display              | 205       | 9.58%   |
| Samsung Electronics     | 186       | 8.7%    |
| Apple                   | 82        | 3.83%   |
| Dell                    | 81        | 3.79%   |
| Goldstar                | 67        | 3.13%   |
| Sharp                   | 65        | 3.04%   |
| Lenovo                  | 40        | 1.87%   |
| PANDA                   | 39        | 1.82%   |
| CSO                     | 37        | 1.73%   |
| InfoVision              | 26        | 1.22%   |
| Hewlett-Packard         | 26        | 1.22%   |
| Chi Mei Optoelectronics | 22        | 1.03%   |
| AOC                     | 21        | 0.98%   |
| TMX                     | 16        | 0.75%   |
| Philips                 | 15        | 0.7%    |
| Acer                    | 15        | 0.7%    |
| ASUSTek Computer        | 13        | 0.61%   |
| BenQ                    | 12        | 0.56%   |
| Ancor Communications    | 9         | 0.42%   |
| MSI                     | 8         | 0.37%   |
| LG Philips              | 8         | 0.37%   |
| Iiyama                  | 8         | 0.37%   |
| Gigabyte Technology     | 6         | 0.28%   |
| ViewSonic               | 5         | 0.23%   |
| Unknown                 | 4         | 0.19%   |
| Panasonic               | 4         | 0.19%   |
| HKC                     | 4         | 0.19%   |
| Toshiba                 | 3         | 0.14%   |
| Sony                    | 3         | 0.14%   |
| NEC Computers           | 3         | 0.14%   |
| Eizo                    | 3         | 0.14%   |
| ___                     | 2         | 0.09%   |
| Vizio                   | 2         | 0.09%   |
| Valve                   | 2         | 0.09%   |
| Unknown (XXX)           | 2         | 0.09%   |
| Tianma XM               | 2         | 0.09%   |
| SLD                     | 2         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 21        | 0.97%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 16        | 0.74%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 14        | 0.65%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 13        | 0.6%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 12        | 0.55%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 12        | 0.55%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 11        | 0.51%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 11        | 0.51%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 11        | 0.51%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 11        | 0.51%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 10        | 0.46%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 9         | 0.42%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 9         | 0.42%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 9         | 0.42%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 8         | 0.37%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 8         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 8         | 0.37%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 8         | 0.37%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 8         | 0.37%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 7         | 0.32%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 7         | 0.32%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 7         | 0.32%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                 | 7         | 0.32%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 7         | 0.32%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch        | 7         | 0.32%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 7         | 0.32%   |
| AU Optronics LCD Monitor AUO408D 1920x1080 309x174mm 14.0-inch        | 7         | 0.32%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 7         | 0.32%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch          | 6         | 0.28%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 6         | 0.28%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch       | 6         | 0.28%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch      | 6         | 0.28%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                 | 6         | 0.28%   |
| BOE LCD Monitor BOE08D5 1920x1080 344x194mm 15.5-inch                 | 6         | 0.28%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                  | 6         | 0.28%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 6         | 0.28%   |
| AU Optronics LCD Monitor AUO369F 1920x1080 344x194mm 15.5-inch        | 6         | 0.28%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 6         | 0.28%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 6         | 0.28%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                | 6         | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 952       | 47.58%  |
| 1366x768 (WXGA)    | 348       | 17.39%  |
| 3840x2160 (4K)     | 97        | 4.85%   |
| 2560x1600          | 91        | 4.55%   |
| 2560x1440 (QHD)    | 82        | 4.1%    |
| 1920x1200 (WUXGA)  | 79        | 3.95%   |
| 1600x900 (HD+)     | 52        | 2.6%    |
| 1280x800 (WXGA)    | 45        | 2.25%   |
| 2880x1800          | 44        | 2.2%    |
| 1440x900 (WXGA+)   | 29        | 1.45%   |
| 3440x1440          | 22        | 1.1%    |
| 2560x1080          | 22        | 1.1%    |
| 3840x2400          | 19        | 0.95%   |
| 2256x1504          | 14        | 0.7%    |
| 2160x1440          | 14        | 0.7%    |
| 1680x1050 (WSXGA+) | 10        | 0.5%    |
| 1280x1024 (SXGA)   | 8         | 0.4%    |
| 3200x2000          | 7         | 0.35%   |
| 2880x1620          | 7         | 0.35%   |
| 2520x1680          | 7         | 0.35%   |
| 2240x1400          | 6         | 0.3%    |
| 3200x1800 (QHD+)   | 5         | 0.25%   |
| 2160x1350          | 5         | 0.25%   |
| 3840x1600          | 4         | 0.2%    |
| 3456x2160          | 4         | 0.2%    |
| 3072x1920          | 4         | 0.2%    |
| 1920x1280          | 4         | 0.2%    |
| 3000x2000          | 3         | 0.15%   |
| 1360x768           | 3         | 0.15%   |
| 800x1280           | 2         | 0.1%    |
| 3840x1100          | 2         | 0.1%    |
| 3840x1080          | 2         | 0.1%    |
| 2304x1440          | 2         | 0.1%    |
| 1024x768 (XGA)     | 2         | 0.1%    |
| 3120x2080          | 1         | 0.05%   |
| 2944x1840          | 1         | 0.05%   |
| 2288x1287          | 1         | 0.05%   |
| 1920x540           | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 779       | 36.37%  |
| 14      | 349       | 16.29%  |
| 13      | 344       | 16.06%  |
| 16      | 90        | 4.2%    |
| 27      | 89        | 4.15%   |
| 17      | 82        | 3.83%   |
| 24      | 72        | 3.36%   |
| 23      | 51        | 2.38%   |
| 21      | 47        | 2.19%   |
| 12      | 45        | 2.1%    |
| 34      | 38        | 1.77%   |
| 31      | 24        | 1.12%   |
| 11      | 21        | 0.98%   |
| 18      | 11        | 0.51%   |
| 28      | 9         | 0.42%   |
| 19      | 9         | 0.42%   |
| 84      | 7         | 0.33%   |
| 72      | 6         | 0.28%   |
| 32      | 6         | 0.28%   |
| 22      | 6         | 0.28%   |
| 20      | 6         | 0.28%   |
| 54      | 5         | 0.23%   |
| 10      | 5         | 0.23%   |
| 40      | 4         | 0.19%   |
| 37      | 4         | 0.19%   |
| Unknown | 4         | 0.19%   |
| 25      | 3         | 0.14%   |
| 64      | 2         | 0.09%   |
| 52      | 2         | 0.09%   |
| 49      | 2         | 0.09%   |
| 35      | 2         | 0.09%   |
| 26      | 2         | 0.09%   |
| 7       | 2         | 0.09%   |
| 142     | 1         | 0.05%   |
| 95      | 1         | 0.05%   |
| 86      | 1         | 0.05%   |
| 65      | 1         | 0.05%   |
| 63      | 1         | 0.05%   |
| 55      | 1         | 0.05%   |
| 48      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 1335      | 62.94%  |
| 201-300        | 269       | 12.68%  |
| 501-600        | 190       | 8.96%   |
| 351-400        | 109       | 5.14%   |
| 401-500        | 74        | 3.49%   |
| 601-700        | 47        | 2.22%   |
| 701-800        | 46        | 2.17%   |
| 1001-1500      | 17        | 0.8%    |
| 1501-2000      | 14        | 0.66%   |
| 801-900        | 11        | 0.52%   |
| Unknown        | 4         | 0.19%   |
| 901-1000       | 2         | 0.09%   |
| 1-100          | 2         | 0.09%   |
| More than 2000 | 1         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1413      | 75.44%  |
| 16/10   | 345       | 18.42%  |
| 21/9    | 48        | 2.56%   |
| 3/2     | 44        | 2.35%   |
| 5/4     | 8         | 0.43%   |
| 4/3     | 5         | 0.27%   |
| 32/9    | 3         | 0.16%   |
| 3.40    | 2         | 0.11%   |
| 0.67    | 2         | 0.11%   |
| 1.00    | 1         | 0.05%   |
| 0.56    | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 788       | 36.82%  |
| 81-90          | 558       | 26.07%  |
| 201-250        | 138       | 6.45%   |
| 71-80          | 121       | 5.65%   |
| 301-350        | 93        | 4.35%   |
| 111-120        | 79        | 3.69%   |
| 121-130        | 78        | 3.64%   |
| 351-500        | 76        | 3.55%   |
| 61-70          | 43        | 2.01%   |
| 251-300        | 34        | 1.59%   |
| More than 1000 | 28        | 1.31%   |
| 151-200        | 24        | 1.12%   |
| 51-60          | 23        | 1.07%   |
| 501-1000       | 16        | 0.75%   |
| 141-150        | 14        | 0.65%   |
| 91-100         | 13        | 0.61%   |
| 41-50          | 5         | 0.23%   |
| Unknown        | 4         | 0.19%   |
| 131-140        | 3         | 0.14%   |
| 1-40           | 2         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 940       | 44.83%  |
| 101-120       | 441       | 21.03%  |
| 161-240       | 312       | 14.88%  |
| 51-100        | 279       | 13.3%   |
| More than 240 | 103       | 4.91%   |
| 1-50          | 18        | 0.86%   |
| Unknown       | 4         | 0.19%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1382      | 75.68%  |
| 2     | 343       | 18.78%  |
| 0     | 55        | 3.01%   |
| 3     | 44        | 2.41%   |
| 4     | 2         | 0.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1025      | 37.64%  |
| Realtek Semiconductor             | 925       | 33.97%  |
| Qualcomm Atheros                  | 190       | 6.98%   |
| Broadcom                          | 170       | 6.24%   |
| MediaTek                          | 122       | 4.48%   |
| Broadcom Limited                  | 34        | 1.25%   |
| ASIX Electronics                  | 31        | 1.14%   |
| Qualcomm                          | 25        | 0.92%   |
| Lenovo                            | 22        | 0.81%   |
| TP-Link                           | 18        | 0.66%   |
| Samsung Electronics               | 18        | 0.66%   |
| Ralink Technology                 | 16        | 0.59%   |
| Xiaomi                            | 13        | 0.48%   |
| Sierra Wireless                   | 11        | 0.4%    |
| DisplayLink                       | 11        | 0.4%    |
| Google                            | 10        | 0.37%   |
| Ralink                            | 8         | 0.29%   |
| Nvidia                            | 8         | 0.29%   |
| Dell                              | 8         | 0.29%   |
| Marvell Technology Group          | 7         | 0.26%   |
| Hewlett-Packard                   | 5         | 0.18%   |
| OPPO Electronics                  | 4         | 0.15%   |
| Qualcomm Atheros Communications   | 3         | 0.11%   |
| Microsoft                         | 3         | 0.11%   |
| JMicron Technology                | 3         | 0.11%   |
| Huawei Technologies               | 3         | 0.11%   |
| ASUSTek Computer                  | 3         | 0.11%   |
| Apple                             | 3         | 0.11%   |
| NetGear                           | 2         | 0.07%   |
| Ericsson Business Mobile Networks | 2         | 0.07%   |
| D-Link                            | 2         | 0.07%   |
| ZyDAS                             | 1         | 0.04%   |
| WEMOS.CC                          | 1         | 0.04%   |
| U-Blox                            | 1         | 0.04%   |
| Spreadtrum Communications         | 1         | 0.04%   |
| Sitecom Europe                    | 1         | 0.04%   |
| Shenzhen Goodix Technology        | 1         | 0.04%   |
| Quectel Wireless Solutions        | 1         | 0.04%   |
| Qualcomm Technologies             | 1         | 0.04%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 548       | 16.79%  |
| Intel Wi-Fi 6 AX201                                                    | 121       | 3.71%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 110       | 3.37%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 108       | 3.31%   |
| Intel Wi-Fi 6 AX200                                                    | 97        | 2.97%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 93        | 2.85%   |
| Intel Wireless 8265 / 8275                                             | 92        | 2.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 68        | 2.08%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 65        | 1.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 55        | 1.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 55        | 1.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 47        | 1.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 45        | 1.38%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 44        | 1.35%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 44        | 1.35%   |
| Intel Wireless 7265                                                    | 43        | 1.32%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 41        | 1.26%   |
| Intel Wireless 7260                                                    | 41        | 1.26%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 40        | 1.23%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 40        | 1.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 38        | 1.16%   |
| Intel Wireless 8260                                                    | 37        | 1.13%   |
| Intel Ethernet Connection (4) I219-LM                                  | 36        | 1.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 33        | 1.01%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 32        | 0.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 31        | 0.95%   |
| Broadcom BCM43142 802.11b/g/n                                          | 30        | 0.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 28        | 0.86%   |
| ASIX AX88179 Gigabit Ethernet                                          | 28        | 0.86%   |
| Realtek RTL8125 2.5GbE Controller                                      | 27        | 0.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 27        | 0.83%   |
| Intel Ethernet Connection (4) I219-V                                   | 25        | 0.77%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 25        | 0.77%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 25        | 0.77%   |
| Intel Wireless 3165                                                    | 23        | 0.7%    |
| Intel Ethernet Connection I219-LM                                      | 23        | 0.7%    |
| Intel Tiger Lake PCH CNVi WiFi                                         | 22        | 0.67%   |
| Intel Ethernet Connection (3) I218-LM                                  | 20        | 0.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 19        | 0.58%   |
| Intel Ethernet Connection (16) I219-V                                  | 19        | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 997       | 53.83%  |
| Realtek Semiconductor                 | 287       | 15.5%   |
| Qualcomm Atheros                      | 167       | 9.02%   |
| Broadcom                              | 155       | 8.37%   |
| MediaTek                              | 120       | 6.48%   |
| Broadcom Limited                      | 28        | 1.51%   |
| Qualcomm                              | 19        | 1.03%   |
| TP-Link                               | 16        | 0.86%   |
| Ralink Technology                     | 16        | 0.86%   |
| Sierra Wireless                       | 11        | 0.59%   |
| Ralink                                | 8         | 0.43%   |
| Dell                                  | 6         | 0.32%   |
| Qualcomm Atheros Communications       | 3         | 0.16%   |
| ASUSTek Computer                      | 3         | 0.16%   |
| NetGear                               | 2         | 0.11%   |
| D-Link                                | 2         | 0.11%   |
| ZyDAS                                 | 1         | 0.05%   |
| Sitecom Europe                        | 1         | 0.05%   |
| Quectel Wireless Solutions            | 1         | 0.05%   |
| Qualcomm Technologies                 | 1         | 0.05%   |
| Microsoft                             | 1         | 0.05%   |
| Hewlett-Packard                       | 1         | 0.05%   |
| Edimax Technology                     | 1         | 0.05%   |
| D-Link System                         | 1         | 0.05%   |
| Belkin Components                     | 1         | 0.05%   |
| AVM                                   | 1         | 0.05%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.05%   |
| Unknown                               | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                  | 121       | 6.5%    |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 108       | 5.8%    |
| Intel Wi-Fi 6 AX200                                                  | 97        | 5.21%   |
| Intel Wireless 8265 / 8275                                           | 92        | 4.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 68        | 3.65%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 65        | 3.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 55        | 2.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 55        | 2.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 47        | 2.53%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 44        | 2.36%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 44        | 2.36%   |
| Intel Wireless 7265                                                  | 43        | 2.31%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 41        | 2.2%    |
| Intel Wireless 7260                                                  | 41        | 2.2%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 40        | 2.15%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 40        | 2.15%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 38        | 2.04%   |
| Intel Wireless 8260                                                  | 37        | 1.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 33        | 1.77%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 32        | 1.72%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 31        | 1.67%   |
| Broadcom BCM43142 802.11b/g/n                                        | 30        | 1.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 28        | 1.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 27        | 1.45%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 25        | 1.34%   |
| Intel Wireless 3165                                                  | 23        | 1.24%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 22        | 1.18%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 19        | 1.02%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 19        | 1.02%   |
| Qualcomm QCNFA765 Wireless Network Adapter                           | 15        | 0.81%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 15        | 0.81%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 15        | 0.81%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 13        | 0.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 13        | 0.7%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 12        | 0.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 12        | 0.64%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                          | 12        | 0.64%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 12        | 0.64%   |
| Intel Centrino Ultimate-N 6300                                       | 11        | 0.59%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 11        | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 781       | 57.43%  |
| Intel                         | 339       | 24.93%  |
| Broadcom                      | 49        | 3.6%    |
| Qualcomm Atheros              | 36        | 2.65%   |
| ASIX Electronics              | 31        | 2.28%   |
| Lenovo                        | 21        | 1.54%   |
| Samsung Electronics           | 18        | 1.32%   |
| Xiaomi                        | 13        | 0.96%   |
| DisplayLink                   | 11        | 0.81%   |
| Google                        | 10        | 0.74%   |
| Nvidia                        | 8         | 0.59%   |
| Marvell Technology Group      | 7         | 0.51%   |
| Qualcomm                      | 6         | 0.44%   |
| Broadcom Limited              | 6         | 0.44%   |
| OPPO Electronics              | 4         | 0.29%   |
| JMicron Technology            | 3         | 0.22%   |
| Huawei Technologies           | 3         | 0.22%   |
| Apple                         | 3         | 0.22%   |
| TP-Link                       | 2         | 0.15%   |
| Microsoft                     | 2         | 0.15%   |
| MediaTek                      | 2         | 0.15%   |
| Hewlett-Packard               | 2         | 0.15%   |
| Spreadtrum Communications     | 1         | 0.07%   |
| OnePlus Technology (Shenzhen) | 1         | 0.07%   |
| Foxconn / Hon Hai             | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 548       | 39.54%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 110       | 7.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 93        | 6.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 45        | 3.25%   |
| Intel Ethernet Connection (4) I219-LM                                  | 36        | 2.6%    |
| ASIX AX88179 Gigabit Ethernet                                          | 28        | 2.02%   |
| Realtek RTL8125 2.5GbE Controller                                      | 27        | 1.95%   |
| Intel Ethernet Connection (4) I219-V                                   | 25        | 1.8%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 25        | 1.8%    |
| Intel Ethernet Connection I219-LM                                      | 23        | 1.66%   |
| Intel Ethernet Connection (3) I218-LM                                  | 20        | 1.44%   |
| Intel Ethernet Connection (16) I219-V                                  | 19        | 1.37%   |
| Intel Ethernet Connection I217-LM                                      | 18        | 1.3%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 16        | 1.15%   |
| Realtek Killer E2600 GbE Controller                                    | 15        | 1.08%   |
| Intel Ethernet Connection (16) I219-LM                                 | 12        | 0.87%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 11        | 0.79%   |
| Intel Ethernet Connection I218-LM                                      | 11        | 0.79%   |
| Intel Ethernet Connection (6) I219-V                                   | 11        | 0.79%   |
| Intel 82577LM Gigabit Network Connection                               | 11        | 0.79%   |
| Intel Ethernet Connection (6) I219-LM                                  | 10        | 0.72%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 9         | 0.65%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 8         | 0.58%   |
| Nvidia MCP79 Ethernet                                                  | 8         | 0.58%   |
| Intel Ethernet Connection (7) I219-LM                                  | 8         | 0.58%   |
| Intel Ethernet Connection (13) I219-LM                                 | 8         | 0.58%   |
| Intel Ethernet Connection I219-V                                       | 7         | 0.51%   |
| Intel 82567LM Gigabit Network Connection                               | 7         | 0.51%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 7         | 0.51%   |
| Qualcomm Nokia G42 5G                                                  | 6         | 0.43%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 6         | 0.43%   |
| Intel Ethernet Connection (2) I219-LM                                  | 6         | 0.43%   |
| Intel Ethernet Connection (10) I219-V                                  | 6         | 0.43%   |
| Google Pixel 7 Pro                                                     | 6         | 0.43%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 5         | 0.36%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 5         | 0.36%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 5         | 0.36%   |
| Intel Ethernet Connection (7) I219-V                                   | 5         | 0.36%   |
| Intel Ethernet Connection (13) I219-V                                  | 5         | 0.36%   |
| DisplayLink Dell Universal Dock D6000                                  | 5         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1770      | 57.73%  |
| Ethernet | 1280      | 41.75%  |
| Modem    | 10        | 0.33%   |
| Unknown  | 6         | 0.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1503      | 79.86%  |
| Ethernet | 379       | 20.14%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1101      | 61.23%  |
| 1     | 652       | 36.26%  |
| 0     | 32        | 1.78%   |
| 3     | 13        | 0.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1245      | 68.44%  |
| Yes  | 574       | 31.56%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 856       | 54.52%  |
| Realtek Semiconductor           | 177       | 11.27%  |
| Qualcomm Atheros Communications | 94        | 5.99%   |
| Foxconn / Hon Hai               | 87        | 5.54%   |
| IMC Networks                    | 85        | 5.41%   |
| Apple                           | 67        | 4.27%   |
| Broadcom                        | 62        | 3.95%   |
| Lite-On Technology              | 42        | 2.68%   |
| Realtek                         | 21        | 1.34%   |
| USI                             | 12        | 0.76%   |
| Dell                            | 12        | 0.76%   |
| Toshiba                         | 8         | 0.51%   |
| Hewlett-Packard                 | 7         | 0.45%   |
| Ralink                          | 6         | 0.38%   |
| Opticis                         | 6         | 0.38%   |
| MediaTek                        | 6         | 0.38%   |
| Cambridge Silicon Radio         | 6         | 0.38%   |
| Foxconn International           | 4         | 0.25%   |
| ASUSTek Computer                | 4         | 0.25%   |
| Askey Computer                  | 2         | 0.13%   |
| TP-Link                         | 1         | 0.06%   |
| Taiyo Yuden                     | 1         | 0.06%   |
| Syntek                          | 1         | 0.06%   |
| Smart Modular Technologies      | 1         | 0.06%   |
| Fujitsu                         | 1         | 0.06%   |
| Dynex                           | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 239       | 15.2%   |
| Realtek Bluetooth Radio                             | 135       | 8.59%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 119       | 7.57%   |
| Intel Bluetooth wireless interface                  | 111       | 7.06%   |
| Intel AX211 Bluetooth                               | 108       | 6.87%   |
| Intel Bluetooth Device                              | 104       | 6.62%   |
| Intel AX200 Bluetooth                               | 94        | 5.98%   |
| Qualcomm Atheros  Bluetooth Device                  | 56        | 3.56%   |
| IMC Networks Wireless_Device                        | 48        | 3.05%   |
| Intel AX210 Bluetooth                               | 41        | 2.61%   |
| Apple Bluetooth Host Controller                     | 35        | 2.23%   |
| Foxconn / Hon Hai Wireless_Device                   | 28        | 1.78%   |
| IMC Networks Bluetooth Radio                        | 26        | 1.65%   |
| Apple Bluetooth USB Host Controller                 | 25        | 1.59%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 23        | 1.46%   |
| Realtek Bluetooth Radio                             | 21        | 1.34%   |
| Realtek  Bluetooth 4.2 Adapter                      | 17        | 1.08%   |
| Realtek 802.11ac WLAN Adapter                       | 17        | 1.08%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 15        | 0.95%   |
| Foxconn / Hon Hai Bluetooth Device                  | 15        | 0.95%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 13        | 0.83%   |
| USI Bluetooth Device                                | 12        | 0.76%   |
| Lite-On Wireless_Device                             | 12        | 0.76%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 12        | 0.76%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 11        | 0.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 11        | 0.7%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 10        | 0.64%   |
| Intel Wireless-AC 3168 Bluetooth                    | 10        | 0.64%   |
| IMC Networks Bluetooth Device                       | 9         | 0.57%   |
| Broadcom BCM2045B (BDC-2.1)                         | 9         | 0.57%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 8         | 0.51%   |
| Broadcom HP Portable Bumble Bee                     | 7         | 0.45%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 7         | 0.45%   |
| Ralink RT3290 Bluetooth                             | 6         | 0.38%   |
| Opticis Bluetooth Radio                             | 6         | 0.38%   |
| MediaTek Wireless_Device                            | 6         | 0.38%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 6         | 0.38%   |
| HP Broadcom 2070 Bluetooth Combo                    | 6         | 0.38%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 0.38%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 6         | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1329      | 56.7%   |
| AMD                                  | 456       | 19.45%  |
| Nvidia                               | 331       | 14.12%  |
| Lenovo                               | 32        | 1.37%   |
| Logitech                             | 25        | 1.07%   |
| C-Media Electronics                  | 22        | 0.94%   |
| Realtek Semiconductor                | 16        | 0.68%   |
| GN Netcom                            | 14        | 0.6%    |
| JMTek                                | 11        | 0.47%   |
| ASUSTek Computer                     | 8         | 0.34%   |
| Apple                                | 8         | 0.34%   |
| Sony                                 | 7         | 0.3%    |
| Kingston Technology                  | 7         | 0.3%    |
| Hewlett-Packard                      | 7         | 0.3%    |
| Razer USA                            | 5         | 0.21%   |
| Plantronics                          | 5         | 0.21%   |
| Dell                                 | 4         | 0.17%   |
| Creative Technology                  | 4         | 0.17%   |
| Microsoft                            | 3         | 0.13%   |
| Focusrite-Novation                   | 3         | 0.13%   |
| Texas Instruments                    | 2         | 0.09%   |
| SteelSeries ApS                      | 2         | 0.09%   |
| Generalplus Technology               | 2         | 0.09%   |
| FiiO Electronics Technology          | 2         | 0.09%   |
| DSEA A/S                             | 2         | 0.09%   |
| Blue Microphones                     | 2         | 0.09%   |
| Audio-Technica                       | 2         | 0.09%   |
| Zhaoxin                              | 1         | 0.04%   |
| Yamaha                               | 1         | 0.04%   |
| XMOS                                 | 1         | 0.04%   |
| Trust                                | 1         | 0.04%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.04%   |
| Tenx Technology                      | 1         | 0.04%   |
| Synaptics                            | 1         | 0.04%   |
| Silicon Motion                       | 1         | 0.04%   |
| shw                                  | 1         | 0.04%   |
| Samsung Electronics                  | 1         | 0.04%   |
| Samson Technologies                  | 1         | 0.04%   |
| RODE Microphones                     | 1         | 0.04%   |
| ROCCAT                               | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 365       | 12.73%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 205       | 7.15%   |
| Intel Sunrise Point-LP HD Audio                                            | 199       | 6.94%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 153       | 5.34%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 138       | 4.81%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 103       | 3.59%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 78        | 2.72%   |
| Nvidia Audio device                                                        | 74        | 2.58%   |
| Intel Cannon Lake PCH cAVS                                                 | 62        | 2.16%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 61        | 2.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 57        | 1.99%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 56        | 1.95%   |
| Intel Comet Lake PCH-LP cAVS                                               | 54        | 1.88%   |
| Intel Broadwell-U Audio Controller                                         | 52        | 1.81%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 51        | 1.78%   |
| Intel Haswell-ULT HD Audio Controller                                      | 50        | 1.74%   |
| Intel 8 Series HD Audio Controller                                         | 50        | 1.74%   |
| Intel Comet Lake PCH cAVS                                                  | 49        | 1.71%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 48        | 1.67%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 47        | 1.64%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 39        | 1.36%   |
| Nvidia GA106 High Definition Audio Controller                              | 35        | 1.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 35        | 1.22%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 33        | 1.15%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 31        | 1.08%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 29        | 1.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 27        | 0.94%   |
| Intel CM238 HD Audio Controller                                            | 26        | 0.91%   |
| AMD FCH Azalia Controller                                                  | 26        | 0.91%   |
| Nvidia GP107GL High Definition Audio Controller                            | 25        | 0.87%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 25        | 0.87%   |
| Nvidia GA104 High Definition Audio Controller                              | 21        | 0.73%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 20        | 0.7%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 19        | 0.66%   |
| Nvidia GF108 High Definition Audio Controller                              | 18        | 0.63%   |
| AMD Kabini HDMI/DP Audio                                                   | 18        | 0.63%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 17        | 0.59%   |
| Realtek Semiconductor USB Audio                                            | 16        | 0.56%   |
| Nvidia TU106 High Definition Audio Controller                              | 15        | 0.52%   |
| Nvidia GK107 HDMI Audio Controller                                         | 14        | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 278       | 32.44%  |
| SK hynix            | 177       | 20.65%  |
| Micron Technology   | 133       | 15.52%  |
| Kingston            | 61        | 7.12%   |
| Crucial             | 54        | 6.3%    |
| Unknown             | 28        | 3.27%   |
| Ramaxel Technology  | 18        | 2.1%    |
| Unknown             | 18        | 2.1%    |
| A-DATA Technology   | 11        | 1.28%   |
| Corsair             | 9         | 1.05%   |
| Elpida              | 8         | 0.93%   |
| Unknown (ABCD)      | 6         | 0.7%    |
| Teikon              | 6         | 0.7%    |
| Smart               | 5         | 0.58%   |
| G.Skill             | 4         | 0.47%   |
| V-GeN               | 3         | 0.35%   |
| Timetec             | 3         | 0.35%   |
| Team                | 3         | 0.35%   |
| Nanya Technology    | 3         | 0.35%   |
| 4ea5                | 3         | 0.35%   |
| Transcend           | 2         | 0.23%   |
| Patriot             | 2         | 0.23%   |
| ff                  | 2         | 0.23%   |
| Unknown (0x0CDC)    | 1         | 0.12%   |
| Unknown (0x0B5E)    | 1         | 0.12%   |
| Smart Brazil        | 1         | 0.12%   |
| Qumo                | 1         | 0.12%   |
| PUSKILL             | 1         | 0.12%   |
| Neo Forza           | 1         | 0.12%   |
| Lexar               | 1         | 0.12%   |
| Kllisre             | 1         | 0.12%   |
| Hikvision           | 1         | 0.12%   |
| HANA                | 1         | 0.12%   |
| GOODRAM             | 1         | 0.12%   |
| Goldkey             | 1         | 0.12%   |
| Gold Key            | 1         | 0.12%   |
| CSX                 | 1         | 0.12%   |
| ChangXin Memory     | 1         | 0.12%   |
| Avant               | 1         | 0.12%   |
| Apacer              | 1         | 0.12%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 18        | 2.03%   |
| Unknown                                                          | 18        | 2.03%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 13        | 1.47%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 1.36%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 11        | 1.24%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 11        | 1.24%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 11        | 1.24%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 10        | 1.13%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 1.13%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 8         | 0.9%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 8         | 0.9%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 7         | 0.79%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 7         | 0.79%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 7         | 0.79%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 6         | 0.68%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.68%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 6         | 0.68%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 6         | 0.68%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 6         | 0.68%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 0.68%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 0.68%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 0.68%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM 4800MT/s               | 6         | 0.68%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.68%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 5         | 0.56%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 5         | 0.56%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.56%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.56%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.56%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.56%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.56%   |
| Micron RAM Module 2GB Row Of Chips LPDDR5 6400MT/s               | 5         | 0.56%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.56%   |
| Micron RAM 4ATF51264HZ-3G2J1 4096MB Row Of Chips DDR4 3200MT/s   | 5         | 0.56%   |
| Crucial RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s          | 5         | 0.56%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 4         | 0.45%   |
| SK hynix RAM HMCG78AEBSA095N 16GB SODIMM 4800MT/s                | 4         | 0.45%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 4         | 0.45%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 4         | 0.45%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 381       | 52.62%  |
| DDR3    | 138       | 19.06%  |
| LPDDR5  | 65        | 8.98%   |
| DDR5    | 54        | 7.46%   |
| LPDDR4  | 44        | 6.08%   |
| LPDDR3  | 34        | 4.7%    |
| DDR2    | 5         | 0.69%   |
| SDRAM   | 2         | 0.28%   |
| Unknown | 1         | 0.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 574       | 78.1%   |
| Row Of Chips | 145       | 19.73%  |
| Unknown      | 10        | 1.36%   |
| Chip         | 4         | 0.54%   |
| DIMM         | 2         | 0.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 341       | 44.06%  |
| 4096  | 177       | 22.87%  |
| 16384 | 164       | 21.19%  |
| 2048  | 51        | 6.59%   |
| 32768 | 33        | 4.26%   |
| 1024  | 7         | 0.9%    |
| 3072  | 1         | 0.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 228       | 29.88%  |
| 2667    | 125       | 16.38%  |
| 1600    | 97        | 12.71%  |
| 6400    | 58        | 7.6%    |
| 4800    | 45        | 5.9%    |
| 2400    | 41        | 5.37%   |
| 2133    | 36        | 4.72%   |
| 4267    | 20        | 2.62%   |
| 1334    | 20        | 2.62%   |
| 1867    | 17        | 2.23%   |
| 1333    | 11        | 1.44%   |
| 5600    | 10        | 1.31%   |
| 1067    | 10        | 1.31%   |
| 4266    | 8         | 1.05%   |
| 3266    | 6         | 0.79%   |
| 8400    | 4         | 0.52%   |
| Unknown | 4         | 0.52%   |
| 7500    | 3         | 0.39%   |
| 7467    | 3         | 0.39%   |
| 800     | 3         | 0.39%   |
| 667     | 3         | 0.39%   |
| 5500    | 2         | 0.26%   |
| 3733    | 2         | 0.26%   |
| 2048    | 2         | 0.26%   |
| 1066    | 2         | 0.26%   |
| 3600    | 1         | 0.13%   |
| 2933    | 1         | 0.13%   |
| 975     | 1         | 0.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Hewlett-Packard               | 5         | 41.67%  |
| Seiko Epson                   | 3         | 25%     |
| STMicroelectronics            | 1         | 8.33%   |
| Samsung Info. Systems America | 1         | 8.33%   |
| Pantum                        | 1         | 8.33%   |
| Brother Industries            | 1         | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 2         | 16.67%  |
| HP LaserJet P1102                                                     | 2         | 16.67%  |
| STMicroelectronics USB Printing Support                               | 1         | 8.33%   |
| Seiko Epson L312 Series                                               | 1         | 8.33%   |
| Samsung Info. Systems America SAMSUNG SRP-270                         | 1         | 8.33%   |
| Pantum P2500W series                                                  | 1         | 8.33%   |
| HP LaserJet 1010                                                      | 1         | 8.33%   |
| HP Ink Tank 310 series                                                | 1         | 8.33%   |
| HP DeskJet 2600 series                                                | 1         | 8.33%   |
| Brother DCP-1600                                                      | 1         | 8.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Seiko Epson GT-X900 [Perfection V700/V750 Photo] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 320       | 19.52%  |
| IMC Networks                           | 212       | 12.93%  |
| Microdia                               | 135       | 8.24%   |
| Quanta                                 | 124       | 7.57%   |
| Bison Electronics                      | 116       | 7.08%   |
| Realtek Semiconductor                  | 113       | 6.89%   |
| Sunplus Innovation Technology          | 87        | 5.31%   |
| Apple                                  | 66        | 4.03%   |
| Cheng Uei Precision Industry (Foxlink) | 64        | 3.9%    |
| Syntek                                 | 51        | 3.11%   |
| Luxvisions Innotech Limited            | 51        | 3.11%   |
| Sonix Technology                       | 45        | 2.75%   |
| Acer                                   | 39        | 2.38%   |
| Logitech                               | 36        | 2.2%    |
| Lite-On Technology                     | 33        | 2.01%   |
| Suyin                                  | 25        | 1.53%   |
| Silicon Motion                         | 15        | 0.92%   |
| Alcor Micro                            | 12        | 0.73%   |
| SunplusIT                              | 10        | 0.61%   |
| ShineTech                              | 10        | 0.61%   |
| Samsung Electronics                    | 8         | 0.49%   |
| Lenovo                                 | 7         | 0.43%   |
| Ricoh                                  | 6         | 0.37%   |
| Shenzhen Kingcome Optoelectronic       | 5         | 0.31%   |
| Importek                               | 4         | 0.24%   |
| Primax Electronics                     | 3         | 0.18%   |
| Creative Technology                    | 3         | 0.18%   |
| ALi                                    | 3         | 0.18%   |
| Unknown                                | 3         | 0.18%   |
| Razer USA                              | 2         | 0.12%   |
| Qtech                                  | 2         | 0.12%   |
| Microsoft                              | 2         | 0.12%   |
| MacroSilicon                           | 2         | 0.12%   |
| icSpring                               | 2         | 0.12%   |
| Foxconn / Hon Hai                      | 2         | 0.12%   |
| ZOOM                                   | 1         | 0.06%   |
| Z-Star Microelectronics                | 1         | 0.06%   |
| WaveRider Communications               | 1         | 0.06%   |
| Trust                                  | 1         | 0.06%   |
| Shine-optics                           | 1         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 113       | 6.86%   |
| Microdia Integrated_Webcam_HD                        | 83        | 5.04%   |
| IMC Networks Integrated Camera                       | 75        | 4.55%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 69        | 4.19%   |
| Realtek Integrated_Webcam_HD                         | 52        | 3.16%   |
| Bison Integrated Camera                              | 42        | 2.55%   |
| Syntek Integrated Camera                             | 41        | 2.49%   |
| Sunplus Integrated_Webcam_HD                         | 29        | 1.76%   |
| Apple FaceTime HD Camera                             | 25        | 1.52%   |
| Quanta HD User Facing                                | 24        | 1.46%   |
| Sonix USB2.0 FHD UVC WebCam                          | 23        | 1.4%    |
| Chicony HD Webcam                                    | 23        | 1.4%    |
| Sonix USB2.0 HD UVC WebCam                           | 21        | 1.27%   |
| Acer Integrated Camera                               | 20        | 1.21%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                      | 19        | 1.15%   |
| Lite-On Integrated Camera                            | 18        | 1.09%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 18        | 1.09%   |
| Quanta HP Wide Vision HD Camera                      | 17        | 1.03%   |
| Bison HD Webcam                                      | 17        | 1.03%   |
| Quanta HP HD Camera                                  | 15        | 0.91%   |
| IMC Networks HD Camera                               | 15        | 0.91%   |
| Chicony Integrated Camera (1280x720@30)              | 15        | 0.91%   |
| Chicony HP Truevision HD camera                      | 15        | 0.91%   |
| Luxvisions Innotech Limited Integrated Camera        | 13        | 0.79%   |
| Chicony HP HD Camera                                 | 13        | 0.79%   |
| Quanta ACER HD User Facing                           | 12        | 0.73%   |
| Chicony HD User Facing                               | 12        | 0.73%   |
| Bison Integrated RGB Camera                          | 12        | 0.73%   |
| Microdia Integrated_Webcam_FHD                       | 11        | 0.67%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 11        | 0.67%   |
| Bison SunplusIT Integrated Camera                    | 11        | 0.67%   |
| Realtek USB Camera                                   | 10        | 0.61%   |
| Quanta HD Camera                                     | 10        | 0.61%   |
| Chicony USB2.0 Camera                                | 10        | 0.61%   |
| Chicony Integrated IR Camera                         | 10        | 0.61%   |
| Chicony HP Truevision HD                             | 10        | 0.61%   |
| Quanta HP TrueVision HD Camera                       | 9         | 0.55%   |
| Luxvisions Innotech Limited Integrated RGB Camera    | 9         | 0.55%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 9         | 0.55%   |
| Bison BisonCam,NB Pro                                | 9         | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 118       | 31.22%  |
| Shenzhen Goodix Technology         | 89        | 23.54%  |
| Validity Sensors                   | 81        | 21.43%  |
| Elan Microelectronics              | 33        | 8.73%   |
| Upek                               | 16        | 4.23%   |
| Realtek USB2.0 Finger Print Bridge | 15        | 3.97%   |
| AuthenTec                          | 10        | 2.65%   |
| LighTuning Technology              | 9         | 2.38%   |
| Samsung Electronics                | 5         | 1.32%   |
| STMicroelectronics                 | 1         | 0.26%   |
| Focal-systems.Corp                 | 1         | 0.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 66        | 17.46%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 41        | 10.85%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 26        | 6.88%   |
| Elan ELAN:ARM-M4                                                           | 21        | 5.56%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 18        | 4.76%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 17        | 4.5%    |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 15        | 3.97%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 14        | 3.7%    |
| Validity Sensors Synaptics WBDI                                            | 13        | 3.44%   |
| Shenzhen Goodix FingerPrint                                                | 13        | 3.44%   |
| Elan ELAN:Fingerprint                                                      | 11        | 2.91%   |
| Synaptics UWP WBDI Device                                                  | 10        | 2.65%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 10        | 2.65%   |
| Shenzhen Goodix Fingerprint Reader                                         | 10        | 2.65%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 8         | 2.12%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 7         | 1.85%   |
| Synaptics Fingerprint reader [HP G6]                                       | 7         | 1.85%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 1.59%   |
| Validity Sensors VFS491                                                    | 5         | 1.32%   |
| Synaptics WBDI                                                             | 5         | 1.32%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 1.06%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 1.06%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 1.06%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 1.06%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 4         | 1.06%   |
| Synaptics TouchPad                                                         | 3         | 0.79%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 0.79%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 0.79%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.53%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 0.53%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 0.53%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.53%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 0.53%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.53%   |
| AuthenTec AES2810                                                          | 2         | 0.53%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.53%   |
| AuthenTec AES1600                                                          | 2         | 0.53%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.26%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.26%   |
| Synaptics UWP WBDI                                                         | 1         | 0.26%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 77        | 54.23%  |
| Alcor Micro               | 41        | 28.87%  |
| Upek                      | 7         | 4.93%   |
| Lenovo                    | 5         | 3.52%   |
| O2 Micro                  | 3         | 2.11%   |
| Gemalto (was Gemplus)     | 3         | 2.11%   |
| Yubico.com                | 1         | 0.7%    |
| Reiner SCT Kartensysteme  | 1         | 0.7%    |
| Realtek Semiconductor     | 1         | 0.7%    |
| Bit4id                    | 1         | 0.7%    |
| Aladdin Knowledge Systems | 1         | 0.7%    |
| Advanced Card Systems     | 1         | 0.7%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 41        | 28.87%  |
| Broadcom 58200                                                               | 33        | 23.24%  |
| Broadcom 5880                                                                | 19        | 13.38%  |
| Broadcom BCM5880 Secure Applications Processor                               | 14        | 9.86%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 7.75%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 4.93%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 3.52%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 1.41%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 1.41%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.7%    |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.7%    |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.7%    |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.7%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.7%    |
| Bit4id miniLector EVO                                                        | 1         | 0.7%    |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.7%    |
| Advanced Card Systems ACR39U                                                 | 1         | 0.7%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1016      | 55.7%   |
| 1     | 658       | 36.07%  |
| 2     | 127       | 6.96%   |
| 3     | 17        | 0.93%   |
| 6     | 2         | 0.11%   |
| 5     | 2         | 0.11%   |
| 8     | 1         | 0.05%   |
| 4     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 371       | 38.33%  |
| Graphics card            | 250       | 25.83%  |
| Multimedia controller    | 145       | 14.98%  |
| Net/wireless             | 82        | 8.47%   |
| Chipcard                 | 27        | 2.79%   |
| Camera                   | 24        | 2.48%   |
| Bluetooth                | 18        | 1.86%   |
| Storage                  | 14        | 1.45%   |
| Sound                    | 14        | 1.45%   |
| Card reader              | 10        | 1.03%   |
| Network                  | 4         | 0.41%   |
| Net/ethernet             | 4         | 0.41%   |
| Communication controller | 3         | 0.31%   |
| Modem                    | 2         | 0.21%   |


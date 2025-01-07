Linux in Norway - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Norway.

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

Total: 1305

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Vostro 15 3530              | [20a13b2865](https://linux-hardware.org/?probe=20a13b2865) | Jan 04, 2025 |
| Dell          | XPS 13 9380                 | [063a26fa4d](https://linux-hardware.org/?probe=063a26fa4d) | Jan 02, 2025 |
| Apple         | MacBookPro11,3              | [5dcd5abfd5](https://linux-hardware.org/?probe=5dcd5abfd5) | Jan 02, 2025 |
| Dell          | XPS 13 9380                 | [fd629307a9](https://linux-hardware.org/?probe=fd629307a9) | Jan 02, 2025 |
| Apple         | MacBookPro11,3              | [29c6fca19b](https://linux-hardware.org/?probe=29c6fca19b) | Jan 01, 2025 |
| Lenovo        | ThinkPad T460 20FN004CMN    | [c918606381](https://linux-hardware.org/?probe=c918606381) | Dec 29, 2024 |
| Dell          | Latitude E7450              | [6677188d5d](https://linux-hardware.org/?probe=6677188d5d) | Dec 27, 2024 |
| Notebook      | L2x0TU                      | [da7db18331](https://linux-hardware.org/?probe=da7db18331) | Dec 24, 2024 |
| Samsung       | 700G7A                      | [0f56340187](https://linux-hardware.org/?probe=0f56340187) | Dec 23, 2024 |
| HP            | EliteBook 8560w (XX058AV... | [fd12235221](https://linux-hardware.org/?probe=fd12235221) | Dec 23, 2024 |
| Lenovo        | ThinkPad T440 20B6009EMN    | [cc41649abd](https://linux-hardware.org/?probe=cc41649abd) | Dec 22, 2024 |
| TUXEDO        | Pulse 14 Gen4               | [dfdca3924e](https://linux-hardware.org/?probe=dfdca3924e) | Dec 22, 2024 |
| Notebook      | P375SM                      | [d888f7c54b](https://linux-hardware.org/?probe=d888f7c54b) | Dec 20, 2024 |
| Dell          | Vostro 15 3530              | [efe67ce19b](https://linux-hardware.org/?probe=efe67ce19b) | Dec 19, 2024 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [98eb4dd31b](https://linux-hardware.org/?probe=98eb4dd31b) | Dec 18, 2024 |
| Dell          | Vostro 15 3530              | [4c4dc318a7](https://linux-hardware.org/?probe=4c4dc318a7) | Dec 16, 2024 |
| Acer          | Aspire A315-24P             | [c2c84cd977](https://linux-hardware.org/?probe=c2c84cd977) | Dec 12, 2024 |
| ASUSTek       | K56CB                       | [7bf07316a0](https://linux-hardware.org/?probe=7bf07316a0) | Dec 09, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [4fef924a63](https://linux-hardware.org/?probe=4fef924a63) | Dec 09, 2024 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [d1af1da978](https://linux-hardware.org/?probe=d1af1da978) | Dec 08, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [31a8469396](https://linux-hardware.org/?probe=31a8469396) | Dec 08, 2024 |
| ASUSTek       | N53SN                       | [fcda31ce2d](https://linux-hardware.org/?probe=fcda31ce2d) | Dec 08, 2024 |
| HP            | EliteBook 8560w (XX058AV... | [8eac1d1836](https://linux-hardware.org/?probe=8eac1d1836) | Dec 08, 2024 |
| MSI           | GE75 Raider 9SG             | [cafb130468](https://linux-hardware.org/?probe=cafb130468) | Dec 07, 2024 |
| Acer          | Swift SF314-52              | [4ac3dc04a3](https://linux-hardware.org/?probe=4ac3dc04a3) | Dec 06, 2024 |
| Samsung       | 930X5J/910S5J/940X5J        | [0ac516c429](https://linux-hardware.org/?probe=0ac516c429) | Dec 05, 2024 |
| Lenovo        | ThinkPad P51 20HJS02H00     | [2839330374](https://linux-hardware.org/?probe=2839330374) | Dec 05, 2024 |
| Lenovo        | ThinkPad T480s 20L7S0BM0... | [77513c5287](https://linux-hardware.org/?probe=77513c5287) | Dec 03, 2024 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [a3435f001c](https://linux-hardware.org/?probe=a3435f001c) | Dec 03, 2024 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [601d3d0748](https://linux-hardware.org/?probe=601d3d0748) | Dec 02, 2024 |
| Acer          | Aspire AV15-51              | [c98b2b5898](https://linux-hardware.org/?probe=c98b2b5898) | Dec 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [68e95f2aff](https://linux-hardware.org/?probe=68e95f2aff) | Nov 27, 2024 |
| MSI           | GL62 6QF                    | [a78b9f5e5d](https://linux-hardware.org/?probe=a78b9f5e5d) | Nov 26, 2024 |
| Google        | Lillipup rev3               | [26051de0da](https://linux-hardware.org/?probe=26051de0da) | Nov 24, 2024 |
| HP            | Compaq 15                   | [6c4420c44c](https://linux-hardware.org/?probe=6c4420c44c) | Nov 16, 2024 |
| HP            | Pavilion Laptop 14-ec0xx... | [2aba476766](https://linux-hardware.org/?probe=2aba476766) | Nov 15, 2024 |
| HP            | Laptop 15-db0xxx            | [660923eef0](https://linux-hardware.org/?probe=660923eef0) | Nov 14, 2024 |
| Lenovo        | Yoga Pro 7 14AHP9 83E3      | [75fd7eeca3](https://linux-hardware.org/?probe=75fd7eeca3) | Nov 13, 2024 |
| HUAWEI        | WRT-WX9                     | [1334a3e15b](https://linux-hardware.org/?probe=1334a3e15b) | Nov 11, 2024 |
| Intel Clie... | LAPQC71A                    | [f25cf6f8a6](https://linux-hardware.org/?probe=f25cf6f8a6) | Nov 08, 2024 |
| Intel Clie... | LAPQC71A                    | [f349a34202](https://linux-hardware.org/?probe=f349a34202) | Nov 06, 2024 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [81c61ad299](https://linux-hardware.org/?probe=81c61ad299) | Oct 30, 2024 |
| HP            | EliteBook 850 G8 Noteboo... | [bad5c7e702](https://linux-hardware.org/?probe=bad5c7e702) | Oct 29, 2024 |
| HP            | EliteBook 820 G2            | [648ab7b15f](https://linux-hardware.org/?probe=648ab7b15f) | Oct 29, 2024 |
| Lenovo        | Yoga 300-11IBR 80M1         | [d47c826466](https://linux-hardware.org/?probe=d47c826466) | Oct 28, 2024 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [76d1943e3b](https://linux-hardware.org/?probe=76d1943e3b) | Oct 28, 2024 |
| TUXEDO        | Sirius 16 Gen2              | [701fca6089](https://linux-hardware.org/?probe=701fca6089) | Oct 28, 2024 |
| Samsung       | 550P5C/550P7C               | [68724c7216](https://linux-hardware.org/?probe=68724c7216) | Oct 26, 2024 |
| Lenovo        | Yoga Pro 7 14IMH9 83E2      | [9c4dde9307](https://linux-hardware.org/?probe=9c4dde9307) | Oct 22, 2024 |
| Dell          | Latitude 7390               | [2859da8ef7](https://linux-hardware.org/?probe=2859da8ef7) | Oct 19, 2024 |
| Dell          | Latitude 5550               | [31ec440570](https://linux-hardware.org/?probe=31ec440570) | Oct 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [dc830d2570](https://linux-hardware.org/?probe=dc830d2570) | Oct 16, 2024 |
| Dell          | Precision 5570              | [91acfd36a9](https://linux-hardware.org/?probe=91acfd36a9) | Oct 14, 2024 |
| Dell          | Precision 5570              | [59646d280c](https://linux-hardware.org/?probe=59646d280c) | Oct 14, 2024 |
| Lenovo        | Yoga Slim 6 14APU8 82X3     | [846f23a439](https://linux-hardware.org/?probe=846f23a439) | Oct 14, 2024 |
| Dell          | Precision 5470              | [f4c728542b](https://linux-hardware.org/?probe=f4c728542b) | Oct 14, 2024 |
| Acer          | Swift SF314-52              | [2c18405cfe](https://linux-hardware.org/?probe=2c18405cfe) | Oct 14, 2024 |
| Apple         | MacBookPro8,1               | [d2d644c166](https://linux-hardware.org/?probe=d2d644c166) | Oct 13, 2024 |
| HP            | 250 G7 Notebook PC          | [e1c4a5a26f](https://linux-hardware.org/?probe=e1c4a5a26f) | Oct 12, 2024 |
| Lenovo        | ThinkPad X13 Gen 3 21BQS... | [b3284fe53e](https://linux-hardware.org/?probe=b3284fe53e) | Oct 10, 2024 |
| HP            | OMEN by Gaming Laptop 16... | [8adc49985c](https://linux-hardware.org/?probe=8adc49985c) | Oct 08, 2024 |
| Acer          | Swift SFG16-72              | [b8f102b8b2](https://linux-hardware.org/?probe=b8f102b8b2) | Oct 08, 2024 |
| Dell          | Latitude 7480               | [9c71766baa](https://linux-hardware.org/?probe=9c71766baa) | Oct 07, 2024 |
| Lenovo        | Yoga Slim 6 14APU8 82X3     | [f295336477](https://linux-hardware.org/?probe=f295336477) | Oct 06, 2024 |
| Samsung       | 900X3F                      | [12e6b46207](https://linux-hardware.org/?probe=12e6b46207) | Oct 03, 2024 |
| Samsung       | 900X3F                      | [5b7f51059a](https://linux-hardware.org/?probe=5b7f51059a) | Oct 03, 2024 |
| Lenovo        | Yoga Pro 7 14AHP9 83E3      | [ed0a6b20fe](https://linux-hardware.org/?probe=ed0a6b20fe) | Oct 02, 2024 |
| Acer          | Aspire A315-24P             | [f6b769cb7f](https://linux-hardware.org/?probe=f6b769cb7f) | Oct 01, 2024 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [fc70ade81c](https://linux-hardware.org/?probe=fc70ade81c) | Sep 30, 2024 |
| Dell          | Latitude E6520              | [4ed4a2acc3](https://linux-hardware.org/?probe=4ed4a2acc3) | Sep 30, 2024 |
| Acer          | Aspire A315-44P             | [99406631a5](https://linux-hardware.org/?probe=99406631a5) | Sep 30, 2024 |
| HP            | ProBook 440 G5              | [9cc0b761cf](https://linux-hardware.org/?probe=9cc0b761cf) | Sep 27, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [2091c77d29](https://linux-hardware.org/?probe=2091c77d29) | Sep 24, 2024 |
| Lenovo        | ThinkPad L430 24662W2       | [a44f25c4d7](https://linux-hardware.org/?probe=a44f25c4d7) | Sep 22, 2024 |
| Lenovo        | ThinkPad T470 20HDS14L00    | [4944f4cf4f](https://linux-hardware.org/?probe=4944f4cf4f) | Sep 22, 2024 |
| HP            | Elite Dragonfly 13.5 inc... | [dfc03a83e8](https://linux-hardware.org/?probe=dfc03a83e8) | Sep 19, 2024 |
| Lenovo        | Yoga Slim 6 14APU8 82X3     | [b39128c23f](https://linux-hardware.org/?probe=b39128c23f) | Sep 18, 2024 |
| MSI           | GT72VR 7RD                  | [2a5a3fd32e](https://linux-hardware.org/?probe=2a5a3fd32e) | Sep 16, 2024 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [797d319058](https://linux-hardware.org/?probe=797d319058) | Sep 14, 2024 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [2200373513](https://linux-hardware.org/?probe=2200373513) | Sep 14, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [7c8b25d3fc](https://linux-hardware.org/?probe=7c8b25d3fc) | Sep 14, 2024 |
| ASUSTek       | Vivobook Go E1404FA_L140... | [b1c4f4a5a0](https://linux-hardware.org/?probe=b1c4f4a5a0) | Sep 13, 2024 |
| HP            | Laptop 15-db0xxx            | [98dd12cddc](https://linux-hardware.org/?probe=98dd12cddc) | Sep 12, 2024 |
| HP            | Elite Dragonfly 13.5 inc... | [e8ae45a202](https://linux-hardware.org/?probe=e8ae45a202) | Sep 10, 2024 |
| Lenovo        | ThinkPad E590 20NBCTO1WW    | [8e796bbcbb](https://linux-hardware.org/?probe=8e796bbcbb) | Sep 10, 2024 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [ae2092a033](https://linux-hardware.org/?probe=ae2092a033) | Sep 04, 2024 |
| Samsung       | 940XFG                      | [aa1058489d](https://linux-hardware.org/?probe=aa1058489d) | Sep 02, 2024 |
| Lenovo        | Yoga Slim 6 14APU8 82X3     | [66bca1f436](https://linux-hardware.org/?probe=66bca1f436) | Sep 01, 2024 |
| Dell          | XPS 14 9440                 | [7d09dc6039](https://linux-hardware.org/?probe=7d09dc6039) | Sep 01, 2024 |
| ASUSTek       | G75VW                       | [1029d7df86](https://linux-hardware.org/?probe=1029d7df86) | Sep 01, 2024 |
| HP            | ZBook Studio 16 inch G10... | [12c5234bb4](https://linux-hardware.org/?probe=12c5234bb4) | Aug 31, 2024 |
| Lenovo        | ThinkPad L480 20LTS15Q00    | [c7bd2c3d2e](https://linux-hardware.org/?probe=c7bd2c3d2e) | Aug 26, 2024 |
| Lenovo        | IdeaPad 510S-14IKB 80UV     | [d5aa8a720a](https://linux-hardware.org/?probe=d5aa8a720a) | Aug 26, 2024 |
| Lenovo        | ThinkPad T431s 20AA000EM... | [ac07d62bd7](https://linux-hardware.org/?probe=ac07d62bd7) | Aug 26, 2024 |
| Dell          | Precision 5470              | [88ce2aa72b](https://linux-hardware.org/?probe=88ce2aa72b) | Aug 26, 2024 |
| Dell          | Latitude E7440              | [86020e73b7](https://linux-hardware.org/?probe=86020e73b7) | Aug 26, 2024 |
| HP            | ProBook 640 G8 Notebook ... | [c8c7a1fc43](https://linux-hardware.org/?probe=c8c7a1fc43) | Aug 24, 2024 |
| HP            | ProBook 640 G8 Notebook ... | [d9ae779618](https://linux-hardware.org/?probe=d9ae779618) | Aug 24, 2024 |
| Apple         | MacBookPro15,2              | [6d965eb60b](https://linux-hardware.org/?probe=6d965eb60b) | Aug 24, 2024 |
| Dell          | Precision 3581              | [4812e53bbd](https://linux-hardware.org/?probe=4812e53bbd) | Aug 22, 2024 |
| Lenovo        | Yoga Slim 6 14APU8 82X3     | [eb3ae6069e](https://linux-hardware.org/?probe=eb3ae6069e) | Aug 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [27c1719af0](https://linux-hardware.org/?probe=27c1719af0) | Aug 20, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [9119a914b1](https://linux-hardware.org/?probe=9119a914b1) | Aug 19, 2024 |
| ASUSTek       | UX32VD                      | [6ac8ebe2f4](https://linux-hardware.org/?probe=6ac8ebe2f4) | Aug 18, 2024 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | [b426ce3ac2](https://linux-hardware.org/?probe=b426ce3ac2) | Aug 17, 2024 |
| HP            | EliteBook 840 G6            | [bdd1d10448](https://linux-hardware.org/?probe=bdd1d10448) | Aug 16, 2024 |
| Lenovo        | Yoga Slim 6 14APU8 82X3     | [316a411fbd](https://linux-hardware.org/?probe=316a411fbd) | Aug 13, 2024 |
| Dell          | Latitude 7450               | [70b1ad6bf2](https://linux-hardware.org/?probe=70b1ad6bf2) | Aug 13, 2024 |
| Lenovo        | Yoga Slim 6 14APU8 82X3     | [0932664d6f](https://linux-hardware.org/?probe=0932664d6f) | Aug 11, 2024 |
| Apple         | MacBookAir4,2               | [a7885ab6c7](https://linux-hardware.org/?probe=a7885ab6c7) | Aug 10, 2024 |
| Chuwi         | CoreBook X                  | [626b500f3e](https://linux-hardware.org/?probe=626b500f3e) | Aug 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [7d0bd59b78](https://linux-hardware.org/?probe=7d0bd59b78) | Aug 08, 2024 |
| Acer          | Aspire A314-23P             | [e2643f5f7f](https://linux-hardware.org/?probe=e2643f5f7f) | Aug 08, 2024 |
| LG Electro... | 16Z90Q-G.AD78B              | [1a7313e7df](https://linux-hardware.org/?probe=1a7313e7df) | Aug 06, 2024 |
| HUAWEI        | MACH-WX9                    | [dec24e68aa](https://linux-hardware.org/?probe=dec24e68aa) | Aug 06, 2024 |
| ASUSTek       | K53E                        | [3a238385b4](https://linux-hardware.org/?probe=3a238385b4) | Aug 03, 2024 |
| HUAWEI        | KPL-W0X                     | [ef1e8a18e7](https://linux-hardware.org/?probe=ef1e8a18e7) | Aug 03, 2024 |
| Lenovo        | ThinkPad X61s 76693KG       | [26fdf1c09d](https://linux-hardware.org/?probe=26fdf1c09d) | Aug 02, 2024 |
| Lenovo        | ThinkPad T400 276552G       | [4311887bdf](https://linux-hardware.org/?probe=4311887bdf) | Jul 31, 2024 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | [4c340a6167](https://linux-hardware.org/?probe=4c340a6167) | Jul 30, 2024 |
| Unknown       | Unknown                     | [f2b5207407](https://linux-hardware.org/?probe=f2b5207407) | Jul 28, 2024 |
| HP            | ZBook Fury 15 G7 Mobile ... | [e077261e5a](https://linux-hardware.org/?probe=e077261e5a) | Jul 24, 2024 |
| Unknown       | Unknown                     | [73874c0806](https://linux-hardware.org/?probe=73874c0806) | Jul 24, 2024 |
| Acer          | Aspire S3-391               | [60eea9dc9a](https://linux-hardware.org/?probe=60eea9dc9a) | Jul 22, 2024 |
| HP            | Pavilion 13                 | [8b052076e8](https://linux-hardware.org/?probe=8b052076e8) | Jul 22, 2024 |
| Unknown       | Unknown                     | [2af4aa15ea](https://linux-hardware.org/?probe=2af4aa15ea) | Jul 21, 2024 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [b0be759962](https://linux-hardware.org/?probe=b0be759962) | Jul 16, 2024 |
| Lenovo        | LOQ 15APH8 82XT             | [80c4e78361](https://linux-hardware.org/?probe=80c4e78361) | Jul 14, 2024 |
| Dell          | Latitude 7370               | [1f1b9c9726](https://linux-hardware.org/?probe=1f1b9c9726) | Jul 14, 2024 |
| Dell          | XPS 15 7590                 | [08d6f2654e](https://linux-hardware.org/?probe=08d6f2654e) | Jul 11, 2024 |
| Acer          | Aspire A315-44P             | [a919306bf7](https://linux-hardware.org/?probe=a919306bf7) | Jul 11, 2024 |
| Dell          | XPS 15 9520                 | [c4078b647c](https://linux-hardware.org/?probe=c4078b647c) | Jul 08, 2024 |
| HP            | EliteBook 840 G6            | [ff7b2c54f1](https://linux-hardware.org/?probe=ff7b2c54f1) | Jul 07, 2024 |
| Lenovo        | Yoga Slim 6 14APU8 82X3     | [d3bd873756](https://linux-hardware.org/?probe=d3bd873756) | Jul 06, 2024 |
| Lenovo        | ThinkPad W541 20EF0020MN    | [302903fcd9](https://linux-hardware.org/?probe=302903fcd9) | Jul 06, 2024 |
| Acer          | Aspire A315-44P             | [36c4d7b87f](https://linux-hardware.org/?probe=36c4d7b87f) | Jul 06, 2024 |
| Lenovo        | IdeaPad 530S-15IKB 81EV     | [8c7530298d](https://linux-hardware.org/?probe=8c7530298d) | Jul 04, 2024 |
| Lenovo        | Yoga Pro 7 14IRH8 82Y7      | [95cdf4988a](https://linux-hardware.org/?probe=95cdf4988a) | Jul 01, 2024 |
| Dell          | Latitude E7240              | [0fa0d32428](https://linux-hardware.org/?probe=0fa0d32428) | Jun 29, 2024 |
| Acer          | Swift SFE16-42              | [18caa8c46b](https://linux-hardware.org/?probe=18caa8c46b) | Jun 28, 2024 |
| Apple         | MacBookAir7,2               | [1f18213681](https://linux-hardware.org/?probe=1f18213681) | Jun 27, 2024 |
| Apple         | MacBookAir7,2               | [7c932fd75a](https://linux-hardware.org/?probe=7c932fd75a) | Jun 23, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [3789df3305](https://linux-hardware.org/?probe=3789df3305) | Jun 22, 2024 |
| Dell          | Precision 5480              | [37179d6d1c](https://linux-hardware.org/?probe=37179d6d1c) | Jun 20, 2024 |
| HP            | ProBook 450 G2              | [b844682a3b](https://linux-hardware.org/?probe=b844682a3b) | Jun 19, 2024 |
| HP            | Unknown                     | [79daced6d2](https://linux-hardware.org/?probe=79daced6d2) | Jun 18, 2024 |
| Dell          | Latitude 3350               | [8f3c5adaf1](https://linux-hardware.org/?probe=8f3c5adaf1) | Jun 17, 2024 |
| Dell          | Latitude E7240              | [10ea2586d7](https://linux-hardware.org/?probe=10ea2586d7) | Jun 16, 2024 |
| Notebook      | NS50_70MU                   | [dcd8f923f3](https://linux-hardware.org/?probe=dcd8f923f3) | Jun 16, 2024 |
| Lenovo        | IdeaPad Slim 3 14AMN8 82... | [f3996c1ab2](https://linux-hardware.org/?probe=f3996c1ab2) | Jun 15, 2024 |
| Lenovo        | IdeaPad Slim 3 14AMN8 82... | [467d268175](https://linux-hardware.org/?probe=467d268175) | Jun 15, 2024 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [8364c453eb](https://linux-hardware.org/?probe=8364c453eb) | Jun 12, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [318d35c49a](https://linux-hardware.org/?probe=318d35c49a) | Jun 05, 2024 |
| Dell          | XPS 15 9570                 | [4f3b26e053](https://linux-hardware.org/?probe=4f3b26e053) | Jun 02, 2024 |
| HP            | Laptop 14-ck0xxx            | [c9932cd3cf](https://linux-hardware.org/?probe=c9932cd3cf) | May 29, 2024 |
| Lenovo        | ThinkPad L490 20Q6S93T00    | [d289a1a217](https://linux-hardware.org/?probe=d289a1a217) | May 28, 2024 |
| HP            | Laptop 14-ck0xxx            | [ddf6c003ee](https://linux-hardware.org/?probe=ddf6c003ee) | May 27, 2024 |
| Acer          | Aspire A315-44P             | [2bae45a3cc](https://linux-hardware.org/?probe=2bae45a3cc) | May 26, 2024 |
| MSI           | GS65 Stealth 9SF            | [f8a0862274](https://linux-hardware.org/?probe=f8a0862274) | May 23, 2024 |
| MSI           | GS65 Stealth 9SF            | [321be6fff1](https://linux-hardware.org/?probe=321be6fff1) | May 23, 2024 |
| Lenovo        | ThinkPad T14 Gen 5 21MLC... | [c712ae4c63](https://linux-hardware.org/?probe=c712ae4c63) | May 15, 2024 |
| Dell          | XPS 15 9520                 | [ddfa8c6085](https://linux-hardware.org/?probe=ddfa8c6085) | May 15, 2024 |
| Dell          | XPS 15 9520                 | [6c753b0264](https://linux-hardware.org/?probe=6c753b0264) | May 14, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [98c20b9fc4](https://linux-hardware.org/?probe=98c20b9fc4) | May 09, 2024 |
| Panasonic     | CF-53SAWZYMN                | [15a322275f](https://linux-hardware.org/?probe=15a322275f) | May 08, 2024 |
| Lenovo        | IdeaPad S510p 20298         | [b941b8d062](https://linux-hardware.org/?probe=b941b8d062) | May 07, 2024 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [c7a39f14e7](https://linux-hardware.org/?probe=c7a39f14e7) | May 03, 2024 |
| HP            | ProBook 430 G8 Notebook ... | [67f5f847c9](https://linux-hardware.org/?probe=67f5f847c9) | May 03, 2024 |
| HP            | EliteBook 8570w             | [050889a119](https://linux-hardware.org/?probe=050889a119) | May 03, 2024 |
| HP            | EliteBook 8570w             | [6b53737811](https://linux-hardware.org/?probe=6b53737811) | May 03, 2024 |
| Lenovo        | ThinkPad T480 20L60034MX    | [eec0c4ee95](https://linux-hardware.org/?probe=eec0c4ee95) | May 02, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [def7a0898e](https://linux-hardware.org/?probe=def7a0898e) | May 02, 2024 |
| IGEL Techn... | M350C                       | [c63a48250c](https://linux-hardware.org/?probe=c63a48250c) | May 01, 2024 |
| Lenovo        | ThinkPad T510 43494JG       | [fe8480c6c4](https://linux-hardware.org/?probe=fe8480c6c4) | Apr 30, 2024 |
| HP            | ProBook 440 G6              | [3cf105c072](https://linux-hardware.org/?probe=3cf105c072) | Apr 26, 2024 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | [3f76329bd6](https://linux-hardware.org/?probe=3f76329bd6) | Apr 23, 2024 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [5d84a72fcf](https://linux-hardware.org/?probe=5d84a72fcf) | Apr 22, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [994aae0769](https://linux-hardware.org/?probe=994aae0769) | Apr 21, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [e26cecc411](https://linux-hardware.org/?probe=e26cecc411) | Apr 21, 2024 |
| Samsung       | 950XDB/951XDB/950XDY        | [252a0c4e05](https://linux-hardware.org/?probe=252a0c4e05) | Apr 21, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [0231457347](https://linux-hardware.org/?probe=0231457347) | Apr 21, 2024 |
| Acer          | Enduro EUN314-51W           | [7a57f25e0e](https://linux-hardware.org/?probe=7a57f25e0e) | Apr 20, 2024 |
| Lenovo        | ThinkPad T520 42433ZG       | [d2899d8de6](https://linux-hardware.org/?probe=d2899d8de6) | Apr 19, 2024 |
| Apple         | MacBookAir6,1               | [08ca3d5ea0](https://linux-hardware.org/?probe=08ca3d5ea0) | Apr 19, 2024 |
| Clevo         | P170EM                      | [62fe8276aa](https://linux-hardware.org/?probe=62fe8276aa) | Apr 18, 2024 |
| Clevo         | P170EM                      | [46daa154fe](https://linux-hardware.org/?probe=46daa154fe) | Apr 18, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [0cd0c2f953](https://linux-hardware.org/?probe=0cd0c2f953) | Apr 17, 2024 |
| Google        | Morphius                    | [422dcd7238](https://linux-hardware.org/?probe=422dcd7238) | Apr 14, 2024 |
| Google        | Morphius                    | [97da05767b](https://linux-hardware.org/?probe=97da05767b) | Apr 13, 2024 |
| Acer          | Enduro EUN314-51W           | [fa7d224ee9](https://linux-hardware.org/?probe=fa7d224ee9) | Apr 11, 2024 |
| Lenovo        | Yoga Slim 6 14APU8 82X3     | [5ec749c52a](https://linux-hardware.org/?probe=5ec749c52a) | Apr 08, 2024 |
| Dell          | Latitude E7240              | [a323cf8e2e](https://linux-hardware.org/?probe=a323cf8e2e) | Apr 08, 2024 |
| MSI           | Katana GF76 11SC            | [937a23fec5](https://linux-hardware.org/?probe=937a23fec5) | Apr 08, 2024 |
| Lenovo        | ThinkPad W530 24476F1       | [14d694fe39](https://linux-hardware.org/?probe=14d694fe39) | Apr 05, 2024 |
| HP            | ProBook 450 G2              | [1753d19bc6](https://linux-hardware.org/?probe=1753d19bc6) | Mar 30, 2024 |
| Notebook      | NJx0AU                      | [93425cb488](https://linux-hardware.org/?probe=93425cb488) | Mar 29, 2024 |
| ASUSTek       | G53SX                       | [6d2eeefcd5](https://linux-hardware.org/?probe=6d2eeefcd5) | Mar 27, 2024 |
| Lenovo        | ThinkPad X280 20KES6M100    | [07c23b72ec](https://linux-hardware.org/?probe=07c23b72ec) | Mar 25, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [8ee75a3460](https://linux-hardware.org/?probe=8ee75a3460) | Mar 23, 2024 |
| Dell          | Latitude E7240              | [a295e64d94](https://linux-hardware.org/?probe=a295e64d94) | Mar 21, 2024 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | [69a6ff7b62](https://linux-hardware.org/?probe=69a6ff7b62) | Mar 18, 2024 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | [f58b97df65](https://linux-hardware.org/?probe=f58b97df65) | Mar 18, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | [8406675c12](https://linux-hardware.org/?probe=8406675c12) | Mar 11, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | [dac802bc03](https://linux-hardware.org/?probe=dac802bc03) | Mar 11, 2024 |
| MSI           | GP70 2QF                    | [0b3d8c1b0e](https://linux-hardware.org/?probe=0b3d8c1b0e) | Mar 10, 2024 |
| Dell          | Latitude 7280               | [1149975fb9](https://linux-hardware.org/?probe=1149975fb9) | Mar 08, 2024 |
| Toshiba       | Satellite C50D-A-133        | [65ea7ee4de](https://linux-hardware.org/?probe=65ea7ee4de) | Mar 07, 2024 |
| Apple         | MacBookPro11,2              | [3c91f66fcd](https://linux-hardware.org/?probe=3c91f66fcd) | Mar 04, 2024 |
| Cepter        | N530-01                     | [00dd983443](https://linux-hardware.org/?probe=00dd983443) | Mar 03, 2024 |
| Acer          | Aspire VN7-592G             | [dd6617c3d7](https://linux-hardware.org/?probe=dd6617c3d7) | Feb 23, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | [a87320ad88](https://linux-hardware.org/?probe=a87320ad88) | Feb 22, 2024 |
| Dell          | XPS 13 9370                 | [086a1782c7](https://linux-hardware.org/?probe=086a1782c7) | Feb 22, 2024 |
| Apple         | MacBookPro9,2               | [a308cdb145](https://linux-hardware.org/?probe=a308cdb145) | Feb 20, 2024 |
| MSI           | Katana GF76 11SC            | [255453e6e0](https://linux-hardware.org/?probe=255453e6e0) | Feb 18, 2024 |
| HP            | ProBook 430 G2              | [a4b236fd41](https://linux-hardware.org/?probe=a4b236fd41) | Feb 17, 2024 |
| Acer          | Aspire V5-552               | [e442dc1b93](https://linux-hardware.org/?probe=e442dc1b93) | Feb 13, 2024 |
| Acer          | Swift SF14-71T              | [be5a1a32c8](https://linux-hardware.org/?probe=be5a1a32c8) | Feb 13, 2024 |
| HP            | EliteBook 840 G5            | [ba2e17a0f0](https://linux-hardware.org/?probe=ba2e17a0f0) | Feb 11, 2024 |
| HP            | ProBook 430 G1              | [191e61f6f6](https://linux-hardware.org/?probe=191e61f6f6) | Feb 09, 2024 |
| Dell          | Inspiron 7559               | [9f3df9cfa3](https://linux-hardware.org/?probe=9f3df9cfa3) | Feb 09, 2024 |
| HP            | ProBook 6450b               | [423b15dea2](https://linux-hardware.org/?probe=423b15dea2) | Feb 09, 2024 |
| ASUSTek       | ROG Strix G712LV_G712LV     | [9a088ac635](https://linux-hardware.org/?probe=9a088ac635) | Feb 08, 2024 |
| ASUSTek       | ROG Strix G712LV_G712LV     | [24923511bf](https://linux-hardware.org/?probe=24923511bf) | Feb 08, 2024 |
| HP            | ProBook 450 G2              | [7a2fbcd83a](https://linux-hardware.org/?probe=7a2fbcd83a) | Feb 08, 2024 |
| HP            | ProBook 450 G2              | [77995292b4](https://linux-hardware.org/?probe=77995292b4) | Feb 08, 2024 |
| HP            | ProBook 440 G5              | [d4ab212d03](https://linux-hardware.org/?probe=d4ab212d03) | Feb 06, 2024 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [f6f21ad952](https://linux-hardware.org/?probe=f6f21ad952) | Feb 04, 2024 |
| HP            | ProBook 650 G1              | [26cf710a63](https://linux-hardware.org/?probe=26cf710a63) | Jan 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [5948bdd871](https://linux-hardware.org/?probe=5948bdd871) | Jan 25, 2024 |
| MSI           | P65 Creator 9SE             | [863ad9098e](https://linux-hardware.org/?probe=863ad9098e) | Jan 24, 2024 |
| HP            | Elite Dragonfly 13.5 inc... | [e78a5c9804](https://linux-hardware.org/?probe=e78a5c9804) | Jan 24, 2024 |
| Lenovo        | ThinkPad T490 20N3SA9100    | [02efe357c0](https://linux-hardware.org/?probe=02efe357c0) | Jan 21, 2024 |
| HP            | EliteBook 830 G6            | [7f5c817c53](https://linux-hardware.org/?probe=7f5c817c53) | Jan 21, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [50d318d640](https://linux-hardware.org/?probe=50d318d640) | Jan 18, 2024 |
| HP            | ZBook 14 G2                 | [e2c1850473](https://linux-hardware.org/?probe=e2c1850473) | Jan 18, 2024 |
| Samsung       | R780                        | [b3adbfa6ae](https://linux-hardware.org/?probe=b3adbfa6ae) | Jan 17, 2024 |
| Lenovo        | ThinkPad T460p 20FXS1G70... | [519458acdc](https://linux-hardware.org/?probe=519458acdc) | Jan 15, 2024 |
| Acer          | Aspire V5-551G              | [699c652ddd](https://linux-hardware.org/?probe=699c652ddd) | Jan 12, 2024 |
| Acer          | Aspire V5-551G              | [8c23e0fefc](https://linux-hardware.org/?probe=8c23e0fefc) | Jan 12, 2024 |
| HP            | Elite Dragonfly 13.5 inc... | [1b8551739b](https://linux-hardware.org/?probe=1b8551739b) | Jan 12, 2024 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | [9b78bbc950](https://linux-hardware.org/?probe=9b78bbc950) | Jan 11, 2024 |
| Dell          | Latitude 7420               | [03a0ad44ae](https://linux-hardware.org/?probe=03a0ad44ae) | Jan 09, 2024 |
| MSI           | Katana GF76 11SC            | [e85c0b091c](https://linux-hardware.org/?probe=e85c0b091c) | Jan 08, 2024 |
| MSI           | P65 Creator 9SE             | [33a2ceb954](https://linux-hardware.org/?probe=33a2ceb954) | Jan 08, 2024 |
| HP            | ZBook 14 G2                 | [a5d8d9ecc9](https://linux-hardware.org/?probe=a5d8d9ecc9) | Jan 06, 2024 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [329f1f3fa2](https://linux-hardware.org/?probe=329f1f3fa2) | Jan 05, 2024 |
| Notebook      | X170KM-G                    | [731411ae4d](https://linux-hardware.org/?probe=731411ae4d) | Jan 02, 2024 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [67ef36b749](https://linux-hardware.org/?probe=67ef36b749) | Jan 01, 2024 |
| MSI           | P65 Creator 9SE             | [2e5c1a6b06](https://linux-hardware.org/?probe=2e5c1a6b06) | Jan 01, 2024 |
| HP            | Elite Dragonfly 13.5 inc... | [bc788ac36f](https://linux-hardware.org/?probe=bc788ac36f) | Dec 31, 2023 |
| HP            | ZBook 14 G2                 | [0d092c7ece](https://linux-hardware.org/?probe=0d092c7ece) | Dec 29, 2023 |
| HP            | EliteBook 820 G3            | [42985f8c13](https://linux-hardware.org/?probe=42985f8c13) | Dec 28, 2023 |
| HP            | Laptop 14-ck0xxx            | [6be155ee0d](https://linux-hardware.org/?probe=6be155ee0d) | Dec 27, 2023 |
| Acer          | Nitro AN515-54              | [67492721ec](https://linux-hardware.org/?probe=67492721ec) | Dec 26, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [6d8c495e90](https://linux-hardware.org/?probe=6d8c495e90) | Dec 23, 2023 |
| HP            | EliteBook 8460p             | [6ff6445717](https://linux-hardware.org/?probe=6ff6445717) | Dec 22, 2023 |
| Dell          | Latitude 5430               | [bce74a439e](https://linux-hardware.org/?probe=bce74a439e) | Dec 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [d34cfca6c8](https://linux-hardware.org/?probe=d34cfca6c8) | Dec 16, 2023 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | [41ff1cd0ca](https://linux-hardware.org/?probe=41ff1cd0ca) | Dec 12, 2023 |
| Dell          | Latitude 5400               | [6e887e1547](https://linux-hardware.org/?probe=6e887e1547) | Dec 11, 2023 |
| Google        | Electro                     | [503645df79](https://linux-hardware.org/?probe=503645df79) | Dec 11, 2023 |
| ASUSTek       | G53SX                       | [6d01f19f82](https://linux-hardware.org/?probe=6d01f19f82) | Dec 08, 2023 |
| HUAWEI        | KLVC-WXX9                   | [cd7c131bf1](https://linux-hardware.org/?probe=cd7c131bf1) | Dec 07, 2023 |
| Acer          | Nitro AN517-41              | [a1b25ec823](https://linux-hardware.org/?probe=a1b25ec823) | Dec 04, 2023 |
| HP            | ProBook 4330s               | [48a060af86](https://linux-hardware.org/?probe=48a060af86) | Dec 04, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | [e9b9374641](https://linux-hardware.org/?probe=e9b9374641) | Dec 02, 2023 |
| Dell          | Latitude E7240              | [e5ac912c4c](https://linux-hardware.org/?probe=e5ac912c4c) | Dec 02, 2023 |
| HP            | Pavilion dv7                | [dc015f1023](https://linux-hardware.org/?probe=dc015f1023) | Dec 01, 2023 |
| Lenovo        | ThinkPad P51 20HJS02H00     | [deafec47f7](https://linux-hardware.org/?probe=deafec47f7) | Dec 01, 2023 |
| ASUSTek       | Zenbook UX6404VI_UX6404V... | [e52dad2488](https://linux-hardware.org/?probe=e52dad2488) | Nov 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K540... | [fc00682f42](https://linux-hardware.org/?probe=fc00682f42) | Nov 29, 2023 |
| Dell          | Latitude 7440               | [aa4dce8576](https://linux-hardware.org/?probe=aa4dce8576) | Nov 27, 2023 |
| Dell          | Latitude 3350               | [395158b705](https://linux-hardware.org/?probe=395158b705) | Nov 27, 2023 |
| Lenovo        | ThinkPad P51 20HJS02H00     | [440b3f0798](https://linux-hardware.org/?probe=440b3f0798) | Nov 25, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | [4515ea6be6](https://linux-hardware.org/?probe=4515ea6be6) | Nov 24, 2023 |
| Dell          | Latitude 7440               | [c05ecee673](https://linux-hardware.org/?probe=c05ecee673) | Nov 23, 2023 |
| Lenovo        | Z50-75 80EC                 | [8470d1677a](https://linux-hardware.org/?probe=8470d1677a) | Nov 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [c4ade3f05e](https://linux-hardware.org/?probe=c4ade3f05e) | Nov 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [ead4849578](https://linux-hardware.org/?probe=ead4849578) | Nov 22, 2023 |
| Dell          | Latitude 5400               | [a2994234ca](https://linux-hardware.org/?probe=a2994234ca) | Nov 21, 2023 |
| Lenovo        | ThinkPad P51 20HJS02H00     | [9c025dacfd](https://linux-hardware.org/?probe=9c025dacfd) | Nov 19, 2023 |
| MSI           | Cyborg 15 A12VF             | [fc41df67a4](https://linux-hardware.org/?probe=fc41df67a4) | Nov 19, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [204303d116](https://linux-hardware.org/?probe=204303d116) | Nov 17, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [c8af1c096b](https://linux-hardware.org/?probe=c8af1c096b) | Nov 17, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [75009bf512](https://linux-hardware.org/?probe=75009bf512) | Nov 17, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [362ad8efa4](https://linux-hardware.org/?probe=362ad8efa4) | Nov 16, 2023 |
| MSI           | Cyborg 15 A12VF             | [3cd966cd6a](https://linux-hardware.org/?probe=3cd966cd6a) | Nov 14, 2023 |
| Acer          | Aspire A515-57              | [7b7cf69882](https://linux-hardware.org/?probe=7b7cf69882) | Nov 14, 2023 |
| Acer          | Aspire A515-57              | [bb0f5fe1e2](https://linux-hardware.org/?probe=bb0f5fe1e2) | Nov 14, 2023 |
| Dell          | XPS 15 9510                 | [d660dfe17a](https://linux-hardware.org/?probe=d660dfe17a) | Nov 09, 2023 |
| Lenovo        | ThinkPad P51 20HJS02H00     | [4345e63ae2](https://linux-hardware.org/?probe=4345e63ae2) | Nov 08, 2023 |
| MSI           | Cyborg 15 A12VF             | [be39067306](https://linux-hardware.org/?probe=be39067306) | Nov 05, 2023 |
| ASUSTek       | G53SX                       | [7834b537a1](https://linux-hardware.org/?probe=7834b537a1) | Nov 05, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [9ea1c674f9](https://linux-hardware.org/?probe=9ea1c674f9) | Nov 03, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [26bc5f025c](https://linux-hardware.org/?probe=26bc5f025c) | Nov 02, 2023 |
| HP            | ProBook 6450b               | [75ad2cf5f8](https://linux-hardware.org/?probe=75ad2cf5f8) | Nov 02, 2023 |
| Lenovo        | ThinkPad L460 20FVS12A00    | [fab360eece](https://linux-hardware.org/?probe=fab360eece) | Nov 02, 2023 |
| Lenovo        | ThinkPad L460 20FVS12A00    | [a2273dea0e](https://linux-hardware.org/?probe=a2273dea0e) | Nov 01, 2023 |
| Dell          | Latitude 7430               | [3e9717ffe0](https://linux-hardware.org/?probe=3e9717ffe0) | Oct 31, 2023 |
| Lenovo        | IdeaPad Slim 3 14AMN8 82... | [3fe09c27c2](https://linux-hardware.org/?probe=3fe09c27c2) | Oct 29, 2023 |
| ASUSTek       | ZenBook UX431FA_UX431FA     | [8f56c1076b](https://linux-hardware.org/?probe=8f56c1076b) | Oct 28, 2023 |
| Lenovo        | IdeaPad Slim 3 14AMN8 82... | [0277411276](https://linux-hardware.org/?probe=0277411276) | Oct 28, 2023 |
| Dell          | Latitude 7430               | [e9cfada6a4](https://linux-hardware.org/?probe=e9cfada6a4) | Oct 26, 2023 |
| HP            | Pavilion Notebook           | [4f269eeaa7](https://linux-hardware.org/?probe=4f269eeaa7) | Oct 23, 2023 |
| Dell          | Latitude E7240              | [6fead70e93](https://linux-hardware.org/?probe=6fead70e93) | Oct 23, 2023 |
| Lenovo        | Y50-70 20378                | [6f65dcd448](https://linux-hardware.org/?probe=6f65dcd448) | Oct 23, 2023 |
| ASUSTek       | X550JX                      | [b1a9053ac6](https://linux-hardware.org/?probe=b1a9053ac6) | Oct 22, 2023 |
| ASUSTek       | G53SX                       | [d19756d24b](https://linux-hardware.org/?probe=d19756d24b) | Oct 22, 2023 |
| MSI           | Cyborg 15 A12VF             | [b1a3bf1a75](https://linux-hardware.org/?probe=b1a3bf1a75) | Oct 21, 2023 |
| MSI           | Cyborg 15 A12VF             | [7fab57f39a](https://linux-hardware.org/?probe=7fab57f39a) | Oct 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [9d7f8ee0f1](https://linux-hardware.org/?probe=9d7f8ee0f1) | Oct 17, 2023 |
| Lenovo        | ThinkPad T480 20L50101US    | [c6913c1b75](https://linux-hardware.org/?probe=c6913c1b75) | Oct 16, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [a2d4463dfc](https://linux-hardware.org/?probe=a2d4463dfc) | Oct 12, 2023 |
| HP            | ProBook 6450b               | [70e33902c1](https://linux-hardware.org/?probe=70e33902c1) | Oct 07, 2023 |
| HP            | ProBook 6450b               | [ddd8417a28](https://linux-hardware.org/?probe=ddd8417a28) | Oct 07, 2023 |
| Dell          | Precision 5530              | [38fdcea75f](https://linux-hardware.org/?probe=38fdcea75f) | Oct 06, 2023 |
| ASUSTek       | G750JH                      | [66396378dd](https://linux-hardware.org/?probe=66396378dd) | Oct 06, 2023 |
| Dell          | Latitude E6540              | [78c4b71781](https://linux-hardware.org/?probe=78c4b71781) | Oct 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [82820de211](https://linux-hardware.org/?probe=82820de211) | Oct 03, 2023 |
| Dell          | Latitude E6540              | [290b4bd42e](https://linux-hardware.org/?probe=290b4bd42e) | Oct 03, 2023 |
| Lenovo        | ThinkPad L430 24662W2       | [21ee2a6e8f](https://linux-hardware.org/?probe=21ee2a6e8f) | Oct 03, 2023 |
| Lenovo        | ThinkPad L460 20FVS12A00    | [ad3d8f3522](https://linux-hardware.org/?probe=ad3d8f3522) | Oct 02, 2023 |
| HP            | EliteBook 650 15.6 inch ... | [75667a0116](https://linux-hardware.org/?probe=75667a0116) | Oct 02, 2023 |
| HP            | EliteBook 640 14 inch G9... | [336d3c6536](https://linux-hardware.org/?probe=336d3c6536) | Oct 02, 2023 |
| HP            | EliteBook 640 14 inch G9... | [7144e87b6b](https://linux-hardware.org/?probe=7144e87b6b) | Oct 02, 2023 |
| ASUSTek       | G53SX                       | [21e6d88bd9](https://linux-hardware.org/?probe=21e6d88bd9) | Oct 02, 2023 |
| Dell          | XPS 13 9350                 | [42f7e22cf3](https://linux-hardware.org/?probe=42f7e22cf3) | Oct 02, 2023 |
| MSI           | Cyborg 15 A12VF             | [5f76307503](https://linux-hardware.org/?probe=5f76307503) | Oct 01, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [83d91ea2fe](https://linux-hardware.org/?probe=83d91ea2fe) | Sep 30, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [0fad85dfc9](https://linux-hardware.org/?probe=0fad85dfc9) | Sep 30, 2023 |
| Dell          | Latitude 5430               | [583aa8cf02](https://linux-hardware.org/?probe=583aa8cf02) | Sep 29, 2023 |
| Intel         | SharkBay Platform           | [2406bf1c0d](https://linux-hardware.org/?probe=2406bf1c0d) | Sep 29, 2023 |
| MSI           | Cyborg 15 A12VF             | [960cd34617](https://linux-hardware.org/?probe=960cd34617) | Sep 29, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | [a5e7296c29](https://linux-hardware.org/?probe=a5e7296c29) | Sep 28, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | [2a507c567b](https://linux-hardware.org/?probe=2a507c567b) | Sep 28, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [ab332c2dcb](https://linux-hardware.org/?probe=ab332c2dcb) | Sep 25, 2023 |
| MSI           | Cyborg 15 A12VF             | [f934062b23](https://linux-hardware.org/?probe=f934062b23) | Sep 25, 2023 |
| MSI           | Cyborg 15 A12VF             | [7aa2ea2853](https://linux-hardware.org/?probe=7aa2ea2853) | Sep 24, 2023 |
| HP            | EliteBook 8470p             | [220a0f8733](https://linux-hardware.org/?probe=220a0f8733) | Sep 23, 2023 |
| Dell          | XPS 15 9530                 | [908d74fdc8](https://linux-hardware.org/?probe=908d74fdc8) | Sep 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [987e4c193b](https://linux-hardware.org/?probe=987e4c193b) | Sep 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [1180346586](https://linux-hardware.org/?probe=1180346586) | Sep 19, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F7... | [2c90700f4f](https://linux-hardware.org/?probe=2c90700f4f) | Sep 16, 2023 |
| Acer          | Predator PH317-53           | [13e8645c6c](https://linux-hardware.org/?probe=13e8645c6c) | Sep 16, 2023 |
| Acer          | Predator PH317-53           | [183adfb8b6](https://linux-hardware.org/?probe=183adfb8b6) | Sep 16, 2023 |
| Notebook      | NV4XMB,ME,MZ                | [35bc7480cb](https://linux-hardware.org/?probe=35bc7480cb) | Sep 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [de94d54f00](https://linux-hardware.org/?probe=de94d54f00) | Sep 15, 2023 |
| MSI           | Cyborg 15 A12VF             | [d1ef9fa580](https://linux-hardware.org/?probe=d1ef9fa580) | Sep 15, 2023 |
| Lenovo        | ThinkPad E14 20RA005MMX     | [d9d0c012b3](https://linux-hardware.org/?probe=d9d0c012b3) | Sep 13, 2023 |
| Lenovo        | ThinkPad X260 20F5S7QT00    | [8475dc74df](https://linux-hardware.org/?probe=8475dc74df) | Sep 09, 2023 |
| Apple         | MacBookPro11,2              | [83b997b3ab](https://linux-hardware.org/?probe=83b997b3ab) | Sep 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [8c22ca23f2](https://linux-hardware.org/?probe=8c22ca23f2) | Sep 07, 2023 |
| Acer          | Swift SF314-51              | [7e7c32364d](https://linux-hardware.org/?probe=7e7c32364d) | Sep 06, 2023 |
| Panasonic     | CF-191HACHFN                | [2c3ca0bdcf](https://linux-hardware.org/?probe=2c3ca0bdcf) | Sep 06, 2023 |
| Star Labs     | StarBook                    | [ac568bfcd4](https://linux-hardware.org/?probe=ac568bfcd4) | Sep 03, 2023 |
| Dell          | XPS 15 9570                 | [9607f36921](https://linux-hardware.org/?probe=9607f36921) | Sep 03, 2023 |
| Dell          | Latitude 3540               | [e7d1d4f160](https://linux-hardware.org/?probe=e7d1d4f160) | Sep 03, 2023 |
| Dell          | XPS 15 9570                 | [72c5c271b6](https://linux-hardware.org/?probe=72c5c271b6) | Sep 03, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [19e076e3e1](https://linux-hardware.org/?probe=19e076e3e1) | Sep 01, 2023 |
| Google        | Galtic                      | [e9ccd3a286](https://linux-hardware.org/?probe=e9ccd3a286) | Sep 01, 2023 |
| Dell          | Latitude E7240              | [cb61859037](https://linux-hardware.org/?probe=cb61859037) | Aug 24, 2023 |
| HP            | 255 G8 Notebook PC          | [68c01672c3](https://linux-hardware.org/?probe=68c01672c3) | Aug 24, 2023 |
| Dell          | Precision M4700             | [9ec95d5a4d](https://linux-hardware.org/?probe=9ec95d5a4d) | Aug 21, 2023 |
| eMachines     | E520 V1.06                  | [bd63874856](https://linux-hardware.org/?probe=bd63874856) | Aug 20, 2023 |
| Dell          | Precision 5520              | [42587aac96](https://linux-hardware.org/?probe=42587aac96) | Aug 20, 2023 |
| Dell          | Precision 5520              | [bec735d800](https://linux-hardware.org/?probe=bec735d800) | Aug 20, 2023 |
| Lenovo        | ThinkPad L430 24662W2       | [10b7d76c38](https://linux-hardware.org/?probe=10b7d76c38) | Aug 20, 2023 |
| Lenovo        | V320-17ISK 81B6             | [cc96bcc8d9](https://linux-hardware.org/?probe=cc96bcc8d9) | Aug 19, 2023 |
| Lenovo        | IdeaPad 1 14ADA7 82R0       | [41b00dc8b3](https://linux-hardware.org/?probe=41b00dc8b3) | Aug 18, 2023 |
| MSI           | Cyborg 15 A12VF             | [b80142953c](https://linux-hardware.org/?probe=b80142953c) | Aug 17, 2023 |
| MSI           | Cyborg 15 A12VF             | [1ba4da3bec](https://linux-hardware.org/?probe=1ba4da3bec) | Aug 17, 2023 |
| HP            | EliteBook Folio 9470m       | [d7f0d8e9cd](https://linux-hardware.org/?probe=d7f0d8e9cd) | Aug 15, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [cec1060cd6](https://linux-hardware.org/?probe=cec1060cd6) | Aug 10, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [33beb40ea6](https://linux-hardware.org/?probe=33beb40ea6) | Aug 09, 2023 |
| MSI           | Cyborg 15 A12VF             | [5fe9a17769](https://linux-hardware.org/?probe=5fe9a17769) | Aug 07, 2023 |
| HP            | EliteBook 840 G6            | [9f230de889](https://linux-hardware.org/?probe=9f230de889) | Aug 07, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [2f529a830c](https://linux-hardware.org/?probe=2f529a830c) | Aug 05, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [9d00f10bab](https://linux-hardware.org/?probe=9d00f10bab) | Aug 05, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [24dc4f34a2](https://linux-hardware.org/?probe=24dc4f34a2) | Aug 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [f7354ee466](https://linux-hardware.org/?probe=f7354ee466) | Aug 04, 2023 |
| Dell          | Latitude E7240              | [ec5ec88e59](https://linux-hardware.org/?probe=ec5ec88e59) | Aug 02, 2023 |
| HP            | ProBook x360 11 G1 EE       | [ab8efe91ea](https://linux-hardware.org/?probe=ab8efe91ea) | Jul 30, 2023 |
| HP            | ProBook x360 11 G1 EE       | [30784ff697](https://linux-hardware.org/?probe=30784ff697) | Jul 30, 2023 |
| HP            | ZBook 15u G5                | [1b0bb754bc](https://linux-hardware.org/?probe=1b0bb754bc) | Jul 28, 2023 |
| HP            | ZBook 15u G5                | [54684f905d](https://linux-hardware.org/?probe=54684f905d) | Jul 28, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [f3cc428da8](https://linux-hardware.org/?probe=f3cc428da8) | Jul 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [6c03bf1d0d](https://linux-hardware.org/?probe=6c03bf1d0d) | Jul 25, 2023 |
| HP            | Laptop 14s-dq1xxx           | [405387be09](https://linux-hardware.org/?probe=405387be09) | Jul 23, 2023 |
| MSI           | Cyborg 15 A12VF             | [62efe51727](https://linux-hardware.org/?probe=62efe51727) | Jul 23, 2023 |
| Lenovo        | V145-15AST 81MT             | [ecce500445](https://linux-hardware.org/?probe=ecce500445) | Jul 22, 2023 |
| MSI           | GL72 6QF                    | [0484bc209c](https://linux-hardware.org/?probe=0484bc209c) | Jul 21, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [a05f11a6b4](https://linux-hardware.org/?probe=a05f11a6b4) | Jul 20, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [2e18524ef0](https://linux-hardware.org/?probe=2e18524ef0) | Jul 20, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [15ef7f9ce4](https://linux-hardware.org/?probe=15ef7f9ce4) | Jul 16, 2023 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [bae54aa498](https://linux-hardware.org/?probe=bae54aa498) | Jul 12, 2023 |
| MSI           | Cyborg 15 A12VF             | [2c4a8d9d63](https://linux-hardware.org/?probe=2c4a8d9d63) | Jul 12, 2023 |
| Dell          | Precision 5680              | [e1363522ee](https://linux-hardware.org/?probe=e1363522ee) | Jul 11, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [0fbc8ca097](https://linux-hardware.org/?probe=0fbc8ca097) | Jul 11, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [fddbab0cf6](https://linux-hardware.org/?probe=fddbab0cf6) | Jul 11, 2023 |
| HP            | EliteBook 1040 G4           | [d7209e7141](https://linux-hardware.org/?probe=d7209e7141) | Jul 11, 2023 |
| HP            | EliteBook 1040 G4           | [33aa3fcdbc](https://linux-hardware.org/?probe=33aa3fcdbc) | Jul 10, 2023 |
| Dell          | Latitude 7370               | [d47bb47c61](https://linux-hardware.org/?probe=d47bb47c61) | Jul 10, 2023 |
| MSI           | GL72 6QF                    | [487fd6cc0e](https://linux-hardware.org/?probe=487fd6cc0e) | Jul 09, 2023 |
| Acer          | Swift SF514-51              | [74c43ecd5c](https://linux-hardware.org/?probe=74c43ecd5c) | Jul 08, 2023 |
| Apple         | MacBookPro8,1               | [ee299280f8](https://linux-hardware.org/?probe=ee299280f8) | Jul 07, 2023 |
| HP            | EliteBook 1040 G4           | [cbc100e6b1](https://linux-hardware.org/?probe=cbc100e6b1) | Jul 07, 2023 |
| HP            | EliteBook 1040 G4           | [3177785c7f](https://linux-hardware.org/?probe=3177785c7f) | Jul 07, 2023 |
| Dell          | Latitude 7480               | [4c07c7b04a](https://linux-hardware.org/?probe=4c07c7b04a) | Jul 07, 2023 |
| HP            | EliteBook 840 G6            | [2fa3986e67](https://linux-hardware.org/?probe=2fa3986e67) | Jul 05, 2023 |
| ASUSTek       | X556UR                      | [79d8c96e3c](https://linux-hardware.org/?probe=79d8c96e3c) | Jul 05, 2023 |
| MSI           | Cyborg 15 A12VF             | [156f923a72](https://linux-hardware.org/?probe=156f923a72) | Jul 04, 2023 |
| Lenovo        | ThinkPad T440s 20ARA1DJM... | [18230f7c64](https://linux-hardware.org/?probe=18230f7c64) | Jul 03, 2023 |
| Dell          | XPS 17 9710                 | [8f6145f929](https://linux-hardware.org/?probe=8f6145f929) | Jul 02, 2023 |
| Dell          | Latitude 7390               | [ef05796af7](https://linux-hardware.org/?probe=ef05796af7) | Jul 01, 2023 |
| Dell          | Latitude 7390               | [ea8982e574](https://linux-hardware.org/?probe=ea8982e574) | Jul 01, 2023 |
| MSI           | Katana GF66 11UG            | [e9f98cc102](https://linux-hardware.org/?probe=e9f98cc102) | Jun 30, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [c44fba1fa2](https://linux-hardware.org/?probe=c44fba1fa2) | Jun 29, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [ff560998d8](https://linux-hardware.org/?probe=ff560998d8) | Jun 28, 2023 |
| Lenovo        | ThinkPad T470s 20HF005QM... | [fee1e04033](https://linux-hardware.org/?probe=fee1e04033) | Jun 28, 2023 |
| Dell          | XPS 15 9510                 | [0294ef5e1f](https://linux-hardware.org/?probe=0294ef5e1f) | Jun 28, 2023 |
| HP            | EliteBook 840 G3            | [ef2e8da48a](https://linux-hardware.org/?probe=ef2e8da48a) | Jun 26, 2023 |
| Lenovo        | ThinkPad P51 20HJS02H00     | [6cb0af7fea](https://linux-hardware.org/?probe=6cb0af7fea) | Jun 24, 2023 |
| MSI           | Cyborg 15 A12VF             | [703e12843e](https://linux-hardware.org/?probe=703e12843e) | Jun 23, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [fed92425f3](https://linux-hardware.org/?probe=fed92425f3) | Jun 23, 2023 |
| Dell          | Latitude E7240              | [f8b3fce80b](https://linux-hardware.org/?probe=f8b3fce80b) | Jun 21, 2023 |
| HP            | EliteBook 840 G6            | [8d35565fd3](https://linux-hardware.org/?probe=8d35565fd3) | Jun 20, 2023 |
| Lenovo        | ThinkPad L490 20Q5001YMX    | [c04ebf8de3](https://linux-hardware.org/?probe=c04ebf8de3) | Jun 20, 2023 |
| HP            | EliteBook 840 G6            | [058b2ea405](https://linux-hardware.org/?probe=058b2ea405) | Jun 20, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [785b0849fd](https://linux-hardware.org/?probe=785b0849fd) | Jun 13, 2023 |
| Lenovo        | G565 4385                   | [2fd61f3fc5](https://linux-hardware.org/?probe=2fd61f3fc5) | Jun 11, 2023 |
| ASUSTek       | GX501VIK                    | [e54a895262](https://linux-hardware.org/?probe=e54a895262) | Jun 11, 2023 |
| Dell          | Latitude E7240              | [e21cc2151b](https://linux-hardware.org/?probe=e21cc2151b) | Jun 08, 2023 |
| HP            | EliteBook 840 G6            | [0763f751ac](https://linux-hardware.org/?probe=0763f751ac) | Jun 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [a39c2e8d55](https://linux-hardware.org/?probe=a39c2e8d55) | Jun 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [58f688ebc5](https://linux-hardware.org/?probe=58f688ebc5) | Jun 02, 2023 |
| Sony          | SVT1121B2EW                 | [67819a243c](https://linux-hardware.org/?probe=67819a243c) | May 31, 2023 |
| ASUSTek       | ROG Strix G513RS_G513RS     | [69b1782cce](https://linux-hardware.org/?probe=69b1782cce) | May 31, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [b4b6bfda0c](https://linux-hardware.org/?probe=b4b6bfda0c) | May 31, 2023 |
| Lenovo        | ThinkPad E495 20NE001GMX    | [cc966f1ede](https://linux-hardware.org/?probe=cc966f1ede) | May 23, 2023 |
| Dell          | Latitude 7370               | [756455c062](https://linux-hardware.org/?probe=756455c062) | May 19, 2023 |
| ASUSTek       | UX430UNR                    | [36f918cce7](https://linux-hardware.org/?probe=36f918cce7) | May 15, 2023 |
| ASUSTek       | UX430UNR                    | [1ba0adc2ba](https://linux-hardware.org/?probe=1ba0adc2ba) | May 15, 2023 |
| ASUSTek       | UX430UNR                    | [a15b90ff4b](https://linux-hardware.org/?probe=a15b90ff4b) | May 13, 2023 |
| Lenovo        | ThinkPad T420 4238AB4       | [795e44d159](https://linux-hardware.org/?probe=795e44d159) | May 12, 2023 |
| Acer          | Aspire VN7-591G             | [1fe1a8fcd2](https://linux-hardware.org/?probe=1fe1a8fcd2) | May 09, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [727163d7b9](https://linux-hardware.org/?probe=727163d7b9) | May 09, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [96d3be3118](https://linux-hardware.org/?probe=96d3be3118) | May 09, 2023 |
| Dell          | XPS 13 9300                 | [7bbdc5e568](https://linux-hardware.org/?probe=7bbdc5e568) | May 07, 2023 |
| Lenovo        | ThinkPad X230 23252CG       | [00ff147a9a](https://linux-hardware.org/?probe=00ff147a9a) | May 03, 2023 |
| Dell          | Precision 7510              | [1e73564cf9](https://linux-hardware.org/?probe=1e73564cf9) | May 03, 2023 |
| Lenovo        | ThinkPad T420 4238AB4       | [3f6a89023c](https://linux-hardware.org/?probe=3f6a89023c) | Apr 28, 2023 |
| HP            | EliteBook 2570p             | [dd76e10243](https://linux-hardware.org/?probe=dd76e10243) | Apr 28, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [e7b20d71b7](https://linux-hardware.org/?probe=e7b20d71b7) | Apr 25, 2023 |
| HP            | EliteBook 2570p             | [2a8a92135b](https://linux-hardware.org/?probe=2a8a92135b) | Apr 24, 2023 |
| Dell          | Latitude E6520              | [a8b5c5c3ad](https://linux-hardware.org/?probe=a8b5c5c3ad) | Apr 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [620334c0fc](https://linux-hardware.org/?probe=620334c0fc) | Apr 23, 2023 |
| Lenovo        | ThinkPad T460s 20F9005CM... | [2aa36b9cfd](https://linux-hardware.org/?probe=2aa36b9cfd) | Apr 22, 2023 |
| Dell          | Latitude 7420               | [480290fd34](https://linux-hardware.org/?probe=480290fd34) | Apr 19, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [c622c73721](https://linux-hardware.org/?probe=c622c73721) | Apr 16, 2023 |
| HP            | Mini 210-1000               | [e8b0b26e10](https://linux-hardware.org/?probe=e8b0b26e10) | Apr 15, 2023 |
| HP            | Pavilion Power Laptop 15... | [b66c208e18](https://linux-hardware.org/?probe=b66c208e18) | Apr 15, 2023 |
| Notebook      | NLx0MU                      | [6d04c51285](https://linux-hardware.org/?probe=6d04c51285) | Apr 11, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [332f3ed32f](https://linux-hardware.org/?probe=332f3ed32f) | Apr 09, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [d6cbe10f95](https://linux-hardware.org/?probe=d6cbe10f95) | Apr 09, 2023 |
| Apple         | MacBookPro12,1              | [0844c71fd0](https://linux-hardware.org/?probe=0844c71fd0) | Apr 07, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | [7f55348e8b](https://linux-hardware.org/?probe=7f55348e8b) | Apr 05, 2023 |
| Apple         | MacBookPro12,1              | [c77ef60bcc](https://linux-hardware.org/?probe=c77ef60bcc) | Apr 05, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [3f750a4d82](https://linux-hardware.org/?probe=3f750a4d82) | Apr 05, 2023 |
| Dell          | Latitude E7240              | [fce3da8380](https://linux-hardware.org/?probe=fce3da8380) | Apr 04, 2023 |
| Apple         | MacBookPro12,1              | [edb2f4188e](https://linux-hardware.org/?probe=edb2f4188e) | Apr 03, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | [c76f4f4354](https://linux-hardware.org/?probe=c76f4f4354) | Mar 31, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | [3a74487ae8](https://linux-hardware.org/?probe=3a74487ae8) | Mar 31, 2023 |
| HP            | ProBook 6360b               | [cf027e03de](https://linux-hardware.org/?probe=cf027e03de) | Mar 30, 2023 |
| Apple         | MacBookPro12,1              | [21515b7373](https://linux-hardware.org/?probe=21515b7373) | Mar 30, 2023 |
| Apple         | MacBookPro12,1              | [080e22fdb2](https://linux-hardware.org/?probe=080e22fdb2) | Mar 30, 2023 |
| MSI           | GT70 2PE                    | [493cabf3f8](https://linux-hardware.org/?probe=493cabf3f8) | Mar 29, 2023 |
| Toshiba       | Satellite L750              | [0bc21ff162](https://linux-hardware.org/?probe=0bc21ff162) | Mar 28, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [df27b06a95](https://linux-hardware.org/?probe=df27b06a95) | Mar 28, 2023 |
| Dell          | Latitude E7240              | [3d91b46fda](https://linux-hardware.org/?probe=3d91b46fda) | Mar 26, 2023 |
| Lenovo        | ThinkPad T460s 20F9005CM... | [640a9ac505](https://linux-hardware.org/?probe=640a9ac505) | Mar 24, 2023 |
| Apple         | MacBookPro12,1              | [aff8d829e0](https://linux-hardware.org/?probe=aff8d829e0) | Mar 22, 2023 |
| Apple         | MacBookPro12,1              | [af60ed4cde](https://linux-hardware.org/?probe=af60ed4cde) | Mar 22, 2023 |
| Lenovo        | ThinkPad T540p 20BE00B8M... | [4cb81db618](https://linux-hardware.org/?probe=4cb81db618) | Mar 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [ac3bb4cdf4](https://linux-hardware.org/?probe=ac3bb4cdf4) | Mar 18, 2023 |
| Dell          | Latitude E7240              | [d4ed345a47](https://linux-hardware.org/?probe=d4ed345a47) | Mar 14, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1C20... | [4853be01f6](https://linux-hardware.org/?probe=4853be01f6) | Mar 14, 2023 |
| Dell          | Latitude E7240              | [4a7d442938](https://linux-hardware.org/?probe=4a7d442938) | Mar 14, 2023 |
| Acer          | Aspire V3-571G              | [2d722aa2b5](https://linux-hardware.org/?probe=2d722aa2b5) | Mar 13, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1C20... | [41cee24fa8](https://linux-hardware.org/?probe=41cee24fa8) | Mar 13, 2023 |
| MSI           | GT72 2QE                    | [b3c4766473](https://linux-hardware.org/?probe=b3c4766473) | Mar 12, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | [e101a1c94c](https://linux-hardware.org/?probe=e101a1c94c) | Mar 11, 2023 |
| HP            | Presario CQ57               | [87bbd773ac](https://linux-hardware.org/?probe=87bbd773ac) | Mar 09, 2023 |
| HP            | Presario CQ57               | [ffa117dde1](https://linux-hardware.org/?probe=ffa117dde1) | Mar 08, 2023 |
| HP            | Pavilion g7                 | [c5c1815bc8](https://linux-hardware.org/?probe=c5c1815bc8) | Mar 08, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | [c3476001d3](https://linux-hardware.org/?probe=c3476001d3) | Mar 07, 2023 |
| Dell          | Latitude 3510               | [983c57e386](https://linux-hardware.org/?probe=983c57e386) | Mar 06, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [779113ef3c](https://linux-hardware.org/?probe=779113ef3c) | Mar 05, 2023 |
| GMKtec        | NucBox5                     | [fc11280fe6](https://linux-hardware.org/?probe=fc11280fe6) | Mar 02, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [7b7df086e0](https://linux-hardware.org/?probe=7b7df086e0) | Feb 28, 2023 |
| Apple         | MacBookPro9,2               | [97192c0aef](https://linux-hardware.org/?probe=97192c0aef) | Feb 26, 2023 |
| Lenovo        | ThinkPad T400s 2808D9G      | [b101883e65](https://linux-hardware.org/?probe=b101883e65) | Feb 24, 2023 |
| Dell          | Latitude E7240              | [7f8278ff44](https://linux-hardware.org/?probe=7f8278ff44) | Feb 23, 2023 |
| Acer          | Swift SF314-42              | [48817e62c6](https://linux-hardware.org/?probe=48817e62c6) | Feb 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [5b33608a35](https://linux-hardware.org/?probe=5b33608a35) | Feb 20, 2023 |
| Dell          | Latitude E7240              | [461873da2d](https://linux-hardware.org/?probe=461873da2d) | Feb 18, 2023 |
| Lenovo        | ThinkPad T520 4243W83       | [e6abb63f33](https://linux-hardware.org/?probe=e6abb63f33) | Feb 17, 2023 |
| Apple         | MacBookPro12,1              | [bdb6e585b0](https://linux-hardware.org/?probe=bdb6e585b0) | Feb 15, 2023 |
| Apple         | MacBookPro12,1              | [139b92595a](https://linux-hardware.org/?probe=139b92595a) | Feb 12, 2023 |
| Lenovo        | V310-15ISK 80SY             | [b96dc1b089](https://linux-hardware.org/?probe=b96dc1b089) | Feb 12, 2023 |
| HP            | Pavilion Laptop 14-ce0xx... | [49b463f14c](https://linux-hardware.org/?probe=49b463f14c) | Feb 10, 2023 |
| Acer          | Aspire V3-571G              | [dcb244db8e](https://linux-hardware.org/?probe=dcb244db8e) | Feb 08, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [81a3a141ba](https://linux-hardware.org/?probe=81a3a141ba) | Feb 08, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [30db5b00f4](https://linux-hardware.org/?probe=30db5b00f4) | Feb 08, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [e9fac81aa1](https://linux-hardware.org/?probe=e9fac81aa1) | Feb 08, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [0e4bbcc317](https://linux-hardware.org/?probe=0e4bbcc317) | Feb 07, 2023 |
| Dell          | Latitude E7240              | [da54499919](https://linux-hardware.org/?probe=da54499919) | Feb 03, 2023 |
| Dell          | Precision 3571              | [8ee8f6f768](https://linux-hardware.org/?probe=8ee8f6f768) | Feb 02, 2023 |
| Dell          | Precision 3571              | [9453f26568](https://linux-hardware.org/?probe=9453f26568) | Feb 02, 2023 |
| Dell          | Latitude E7240              | [a1f713f6e3](https://linux-hardware.org/?probe=a1f713f6e3) | Jan 30, 2023 |
| Dell          | Precision 5530              | [92399ea8dc](https://linux-hardware.org/?probe=92399ea8dc) | Jan 29, 2023 |
| Toshiba       | Satellite L500              | [327e2d4e3e](https://linux-hardware.org/?probe=327e2d4e3e) | Jan 28, 2023 |
| Dell          | Precision 5530              | [a9a54c5b7f](https://linux-hardware.org/?probe=a9a54c5b7f) | Jan 28, 2023 |
| Dell          | Latitude E7240              | [d88cdedff3](https://linux-hardware.org/?probe=d88cdedff3) | Jan 26, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [293a308d86](https://linux-hardware.org/?probe=293a308d86) | Jan 25, 2023 |
| Dell          | Latitude E7240              | [2d488752b6](https://linux-hardware.org/?probe=2d488752b6) | Jan 25, 2023 |
| Dell          | Latitude E7240              | [9d44efa2f9](https://linux-hardware.org/?probe=9d44efa2f9) | Jan 24, 2023 |
| HP            | Notebook                    | [57bf6826ef](https://linux-hardware.org/?probe=57bf6826ef) | Jan 22, 2023 |
| Samsung       | 3570R/370R/470R/450R/510... | [8c4a855d8e](https://linux-hardware.org/?probe=8c4a855d8e) | Jan 21, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [e8a0c0066b](https://linux-hardware.org/?probe=e8a0c0066b) | Jan 21, 2023 |
| Samsung       | 3570R/370R/470R/450R/510... | [0ea26f4af6](https://linux-hardware.org/?probe=0ea26f4af6) | Jan 20, 2023 |
| Dell          | Latitude E7240              | [a4e01b187f](https://linux-hardware.org/?probe=a4e01b187f) | Jan 20, 2023 |
| Dell          | Latitude E7240              | [475187029d](https://linux-hardware.org/?probe=475187029d) | Jan 19, 2023 |
| Dell          | XPS 15 9570                 | [859d3c1b58](https://linux-hardware.org/?probe=859d3c1b58) | Jan 18, 2023 |
| HP            | Laptop 17-ca0xxx            | [a8fbe01fc5](https://linux-hardware.org/?probe=a8fbe01fc5) | Jan 17, 2023 |
| ASUSTek       | K55VM                       | [5b8deec807](https://linux-hardware.org/?probe=5b8deec807) | Jan 16, 2023 |
| Dell          | Latitude E7240              | [dc47f005d6](https://linux-hardware.org/?probe=dc47f005d6) | Jan 16, 2023 |
| Lenovo        | ThinkPad P51 20HJS02H00     | [ab26ff36b1](https://linux-hardware.org/?probe=ab26ff36b1) | Jan 14, 2023 |
| Dell          | Latitude E7240              | [76f54ae84c](https://linux-hardware.org/?probe=76f54ae84c) | Jan 14, 2023 |
| Dell          | Latitude 3350               | [d7ca8710c2](https://linux-hardware.org/?probe=d7ca8710c2) | Jan 14, 2023 |
| Dell          | Latitude E7240              | [9eed89d744](https://linux-hardware.org/?probe=9eed89d744) | Jan 14, 2023 |
| Dell          | Latitude E7240              | [ed7ff7569c](https://linux-hardware.org/?probe=ed7ff7569c) | Jan 14, 2023 |
| Dell          | Latitude E7240              | [93d832d08f](https://linux-hardware.org/?probe=93d832d08f) | Jan 11, 2023 |
| HP            | ProBook 650 G1              | [1dba72668b](https://linux-hardware.org/?probe=1dba72668b) | Jan 10, 2023 |
| HP            | ProBook 650 G1              | [e6d3982bc0](https://linux-hardware.org/?probe=e6d3982bc0) | Jan 10, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | [e14b3158f3](https://linux-hardware.org/?probe=e14b3158f3) | Jan 10, 2023 |
| Dell          | Latitude 7490               | [0780580a38](https://linux-hardware.org/?probe=0780580a38) | Jan 09, 2023 |
| Dell          | Latitude E7240              | [c191d76ac2](https://linux-hardware.org/?probe=c191d76ac2) | Jan 09, 2023 |
| Notebook      | NLx0MU                      | [69b46423cb](https://linux-hardware.org/?probe=69b46423cb) | Jan 08, 2023 |
| Notebook      | NLx0MU                      | [e43de3e94e](https://linux-hardware.org/?probe=e43de3e94e) | Jan 08, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | [2b8c216e1a](https://linux-hardware.org/?probe=2b8c216e1a) | Jan 08, 2023 |
| Cepter        | N530-01                     | [2b5d455bfd](https://linux-hardware.org/?probe=2b5d455bfd) | Jan 07, 2023 |
| Dell          | Latitude E7240              | [c7cf2afdd9](https://linux-hardware.org/?probe=c7cf2afdd9) | Jan 07, 2023 |
| Dell          | Latitude E7240              | [7018e90a09](https://linux-hardware.org/?probe=7018e90a09) | Jan 07, 2023 |
| Dell          | Latitude E7240              | [d4dc080444](https://linux-hardware.org/?probe=d4dc080444) | Jan 07, 2023 |
| Dell          | Latitude E7240              | [b00208bba7](https://linux-hardware.org/?probe=b00208bba7) | Jan 06, 2023 |
| Dell          | Latitude E7240              | [6eae9dc932](https://linux-hardware.org/?probe=6eae9dc932) | Jan 05, 2023 |
| Dell          | Latitude E5520              | [fd30377f05](https://linux-hardware.org/?probe=fd30377f05) | Jan 04, 2023 |
| Acer          | Aspire A515-57G             | [854bee8efb](https://linux-hardware.org/?probe=854bee8efb) | Jan 02, 2023 |
| Dell          | Latitude E7240              | [ccf48432e0](https://linux-hardware.org/?probe=ccf48432e0) | Jan 02, 2023 |
| MSI           | GE60 2OC\2OE                | [c307379c36](https://linux-hardware.org/?probe=c307379c36) | Dec 30, 2022 |
| Dell          | Latitude E7240              | [5f83c8f4ad](https://linux-hardware.org/?probe=5f83c8f4ad) | Dec 30, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [78c6c15502](https://linux-hardware.org/?probe=78c6c15502) | Dec 27, 2022 |
| Acer          | Aspire A114-32              | [593969da1f](https://linux-hardware.org/?probe=593969da1f) | Dec 26, 2022 |
| Dell          | Latitude E7240              | [918223cece](https://linux-hardware.org/?probe=918223cece) | Dec 23, 2022 |
| Dell          | Latitude E7240              | [7bd2309063](https://linux-hardware.org/?probe=7bd2309063) | Dec 23, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [d7b8ef01e2](https://linux-hardware.org/?probe=d7b8ef01e2) | Dec 23, 2022 |
| Dell          | Latitude E7240              | [d81efafde1](https://linux-hardware.org/?probe=d81efafde1) | Dec 22, 2022 |
| Dell          | Latitude E7240              | [545294a23a](https://linux-hardware.org/?probe=545294a23a) | Dec 21, 2022 |
| Dell          | Latitude E7240              | [a368a7be00](https://linux-hardware.org/?probe=a368a7be00) | Dec 21, 2022 |
| Dell          | XPS 13 9360                 | [30eb665688](https://linux-hardware.org/?probe=30eb665688) | Dec 20, 2022 |
| Lenovo        | ThinkPad Edge E531 68852... | [24affad285](https://linux-hardware.org/?probe=24affad285) | Dec 18, 2022 |
| Google        | Cyan                        | [df6e213ea7](https://linux-hardware.org/?probe=df6e213ea7) | Dec 17, 2022 |
| Google        | Cyan                        | [b0872d0327](https://linux-hardware.org/?probe=b0872d0327) | Dec 17, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [544e464dab](https://linux-hardware.org/?probe=544e464dab) | Dec 15, 2022 |
| Dell          | Latitude E7240              | [d6dddd9632](https://linux-hardware.org/?probe=d6dddd9632) | Dec 11, 2022 |
| Acer          | Aspire E1-572               | [7a6c67f095](https://linux-hardware.org/?probe=7a6c67f095) | Dec 09, 2022 |
| Apple         | MacBookPro6,1               | [6bb486dbb5](https://linux-hardware.org/?probe=6bb486dbb5) | Dec 07, 2022 |
| Apple         | MacBookPro6,1               | [68fa42c5f5](https://linux-hardware.org/?probe=68fa42c5f5) | Dec 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [a6763bdd89](https://linux-hardware.org/?probe=a6763bdd89) | Dec 05, 2022 |
| HP            | EliteBook 840 G5            | [3caa213ecf](https://linux-hardware.org/?probe=3caa213ecf) | Dec 04, 2022 |
| Dell          | Latitude E7240              | [6f34110d45](https://linux-hardware.org/?probe=6f34110d45) | Dec 04, 2022 |
| HP            | ZBook 14 G2                 | [b2bba919b2](https://linux-hardware.org/?probe=b2bba919b2) | Nov 30, 2022 |
| Dell          | Latitude E7240              | [8b0b984870](https://linux-hardware.org/?probe=8b0b984870) | Nov 29, 2022 |
| Dell          | Latitude E7240              | [831ec54e18](https://linux-hardware.org/?probe=831ec54e18) | Nov 26, 2022 |
| HP            | Presario CQ56               | [919fad0653](https://linux-hardware.org/?probe=919fad0653) | Nov 25, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [71c464a407](https://linux-hardware.org/?probe=71c464a407) | Nov 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [0278a1f18d](https://linux-hardware.org/?probe=0278a1f18d) | Nov 18, 2022 |
| HP            | ZBook 14 G2                 | [8ce9402aad](https://linux-hardware.org/?probe=8ce9402aad) | Nov 16, 2022 |
| Acer          | Aspire A114-32              | [5a76aee400](https://linux-hardware.org/?probe=5a76aee400) | Nov 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [6677ca6be8](https://linux-hardware.org/?probe=6677ca6be8) | Nov 12, 2022 |
| Acer          | Aspire A114-32              | [aec286073d](https://linux-hardware.org/?probe=aec286073d) | Nov 12, 2022 |
| Acer          | Aspire A114-32              | [3884507df6](https://linux-hardware.org/?probe=3884507df6) | Nov 11, 2022 |
| Dell          | Latitude E7240              | [d6644079ac](https://linux-hardware.org/?probe=d6644079ac) | Nov 11, 2022 |
| Acer          | Aspire A114-32              | [a06fb78621](https://linux-hardware.org/?probe=a06fb78621) | Nov 10, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [d6fd1a5ecd](https://linux-hardware.org/?probe=d6fd1a5ecd) | Nov 10, 2022 |
| HP            | EliteBook 850 G5            | [3408fb4c36](https://linux-hardware.org/?probe=3408fb4c36) | Nov 07, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [5264f28363](https://linux-hardware.org/?probe=5264f28363) | Nov 07, 2022 |
| HP            | Pavilion dv6                | [f715c6e15c](https://linux-hardware.org/?probe=f715c6e15c) | Nov 07, 2022 |
| Dell          | Latitude 3340               | [2c6380f259](https://linux-hardware.org/?probe=2c6380f259) | Nov 06, 2022 |
| Dell          | Latitude E7240              | [2db569e056](https://linux-hardware.org/?probe=2db569e056) | Nov 06, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [e2cadc512e](https://linux-hardware.org/?probe=e2cadc512e) | Nov 05, 2022 |
| HP            | EliteBook 840 G5            | [34c050ed44](https://linux-hardware.org/?probe=34c050ed44) | Nov 03, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [ada830a489](https://linux-hardware.org/?probe=ada830a489) | Nov 03, 2022 |
| Dell          | Precision 14 5470           | [dab29b7f5b](https://linux-hardware.org/?probe=dab29b7f5b) | Nov 03, 2022 |
| Acer          | Aspire A114-32              | [2394d00673](https://linux-hardware.org/?probe=2394d00673) | Nov 03, 2022 |
| Acer          | Aspire A114-32              | [036ff9e51f](https://linux-hardware.org/?probe=036ff9e51f) | Nov 02, 2022 |
| Acer          | Aspire A114-32              | [d5d1583252](https://linux-hardware.org/?probe=d5d1583252) | Nov 02, 2022 |
| Dell          | Latitude E7240              | [effafc033d](https://linux-hardware.org/?probe=effafc033d) | Nov 01, 2022 |
| ASUSTek       | K55VD                       | [6e2ff87fad](https://linux-hardware.org/?probe=6e2ff87fad) | Nov 01, 2022 |
| Dell          | Latitude E7240              | [d8ae1a7195](https://linux-hardware.org/?probe=d8ae1a7195) | Nov 01, 2022 |
| MSI           | GF63 Thin 11UD              | [8f48ae7586](https://linux-hardware.org/?probe=8f48ae7586) | Oct 29, 2022 |
| MSI           | GF63 Thin 11UD              | [8f1f41f3b0](https://linux-hardware.org/?probe=8f1f41f3b0) | Oct 29, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [f845ed2866](https://linux-hardware.org/?probe=f845ed2866) | Oct 28, 2022 |
| MSI           | GF63 Thin 11UD              | [e2a6e0f610](https://linux-hardware.org/?probe=e2a6e0f610) | Oct 28, 2022 |
| MSI           | GF63 Thin 11UD              | [9f7121381b](https://linux-hardware.org/?probe=9f7121381b) | Oct 27, 2022 |
| MSI           | GF63 Thin 11UD              | [2b6b8d3854](https://linux-hardware.org/?probe=2b6b8d3854) | Oct 26, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [3375318388](https://linux-hardware.org/?probe=3375318388) | Oct 25, 2022 |
| Dell          | Latitude E7240              | [6966cfc71f](https://linux-hardware.org/?probe=6966cfc71f) | Oct 25, 2022 |
| Dell          | Latitude 5480               | [0b8576ce3b](https://linux-hardware.org/?probe=0b8576ce3b) | Oct 25, 2022 |
| Apple         | MacBookAir6,2               | [c271de3628](https://linux-hardware.org/?probe=c271de3628) | Oct 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [5eeed3a9f0](https://linux-hardware.org/?probe=5eeed3a9f0) | Oct 24, 2022 |
| MSI           | GF63 Thin 11UD              | [ca39605260](https://linux-hardware.org/?probe=ca39605260) | Oct 18, 2022 |
| Lenovo        | IdeaPad 5 Pro 16IAH7 82S... | [dfa3140411](https://linux-hardware.org/?probe=dfa3140411) | Oct 17, 2022 |
| MSI           | GF63 Thin 11UD              | [d522208941](https://linux-hardware.org/?probe=d522208941) | Oct 17, 2022 |
| Lenovo        | ThinkPad T510 43495KG       | [4668319862](https://linux-hardware.org/?probe=4668319862) | Oct 16, 2022 |
| Getac         | V110G3                      | [09cd83f0ec](https://linux-hardware.org/?probe=09cd83f0ec) | Oct 14, 2022 |
| Lenovo        | ThinkPad T510 43495KG       | [dbe29306f4](https://linux-hardware.org/?probe=dbe29306f4) | Oct 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [46b44504df](https://linux-hardware.org/?probe=46b44504df) | Oct 08, 2022 |
| MSI           | GL62 6QD                    | [d97ad417e9](https://linux-hardware.org/?probe=d97ad417e9) | Oct 07, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | [b27c3b70a7](https://linux-hardware.org/?probe=b27c3b70a7) | Oct 07, 2022 |
| Acer          | Aspire A515-57G             | [f8d3a419e6](https://linux-hardware.org/?probe=f8d3a419e6) | Oct 07, 2022 |
| Dell          | Latitude 5400               | [00789b23c6](https://linux-hardware.org/?probe=00789b23c6) | Oct 06, 2022 |
| HP            | ProBook 645 G1              | [a085d5e42c](https://linux-hardware.org/?probe=a085d5e42c) | Oct 06, 2022 |
| Dell          | Latitude 5400               | [14ed107028](https://linux-hardware.org/?probe=14ed107028) | Oct 05, 2022 |
| MSI           | GF63 Thin 11UD              | [25077cf5e8](https://linux-hardware.org/?probe=25077cf5e8) | Oct 04, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [5037913bd4](https://linux-hardware.org/?probe=5037913bd4) | Oct 04, 2022 |
| Dell          | Latitude E7240              | [0a41ea4b4c](https://linux-hardware.org/?probe=0a41ea4b4c) | Oct 04, 2022 |
| MSI           | GF63 Thin 11UD              | [b8237b1bd7](https://linux-hardware.org/?probe=b8237b1bd7) | Oct 04, 2022 |
| Intel Clie... | LAPQC71A                    | [6d7beecaf6](https://linux-hardware.org/?probe=6d7beecaf6) | Sep 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [54bc787611](https://linux-hardware.org/?probe=54bc787611) | Sep 29, 2022 |
| Dell          | XPS 13 9350                 | [23142407b0](https://linux-hardware.org/?probe=23142407b0) | Sep 28, 2022 |
| MSI           | GS66 Stealth 10SGS          | [644efb07cf](https://linux-hardware.org/?probe=644efb07cf) | Sep 27, 2022 |
| Dell          | XPS 15 9520                 | [fab5b34402](https://linux-hardware.org/?probe=fab5b34402) | Sep 25, 2022 |
| Dell          | XPS 15 9500                 | [1095e2f7f0](https://linux-hardware.org/?probe=1095e2f7f0) | Sep 25, 2022 |
| MSI           | GF63 Thin 11UD              | [fac56b0962](https://linux-hardware.org/?probe=fac56b0962) | Sep 24, 2022 |
| HP            | Presario CQ56               | [ed937514cf](https://linux-hardware.org/?probe=ed937514cf) | Sep 23, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [4dd83a1b80](https://linux-hardware.org/?probe=4dd83a1b80) | Sep 16, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [80638ed98f](https://linux-hardware.org/?probe=80638ed98f) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [3196144640](https://linux-hardware.org/?probe=3196144640) | Sep 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [38fa0eaf03](https://linux-hardware.org/?probe=38fa0eaf03) | Sep 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [72c53fd3c8](https://linux-hardware.org/?probe=72c53fd3c8) | Sep 15, 2022 |
| HUAWEI        | KLVL-WXX9                   | [7bc7cbca76](https://linux-hardware.org/?probe=7bc7cbca76) | Sep 12, 2022 |
| Acer          | Aspire 6930G                | [cb054f2964](https://linux-hardware.org/?probe=cb054f2964) | Sep 12, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [e1d128b56a](https://linux-hardware.org/?probe=e1d128b56a) | Sep 12, 2022 |
| HP            | ZBook 15 G5                 | [fe1d0da2fc](https://linux-hardware.org/?probe=fe1d0da2fc) | Sep 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [30488e19df](https://linux-hardware.org/?probe=30488e19df) | Sep 08, 2022 |
| MSI           | Katana GF66 11UE            | [36b2cba297](https://linux-hardware.org/?probe=36b2cba297) | Sep 05, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [5472c45d04](https://linux-hardware.org/?probe=5472c45d04) | Sep 03, 2022 |
| MSI           | GF65 Thin 10SER             | [9438d3a4fe](https://linux-hardware.org/?probe=9438d3a4fe) | Sep 03, 2022 |
| MSI           | GF65 Thin 10SER             | [5344528fa4](https://linux-hardware.org/?probe=5344528fa4) | Sep 03, 2022 |
| Intel Clie... | LAPQC71A                    | [9bc39724f8](https://linux-hardware.org/?probe=9bc39724f8) | Sep 02, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [b6e6d0a261](https://linux-hardware.org/?probe=b6e6d0a261) | Sep 02, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [7277e72eb4](https://linux-hardware.org/?probe=7277e72eb4) | Aug 31, 2022 |
| Notebook      | NLx0MU                      | [90c9b01136](https://linux-hardware.org/?probe=90c9b01136) | Aug 31, 2022 |
| Notebook      | NLx0MU                      | [77d4b4ff99](https://linux-hardware.org/?probe=77d4b4ff99) | Aug 31, 2022 |
| MSI           | GL72 6QF                    | [1ffe55389e](https://linux-hardware.org/?probe=1ffe55389e) | Aug 27, 2022 |
| MSI           | GL72 6QF                    | [46b40c3c67](https://linux-hardware.org/?probe=46b40c3c67) | Aug 27, 2022 |
| HP            | ProBook 430 G8 Notebook ... | [17260bd4fb](https://linux-hardware.org/?probe=17260bd4fb) | Aug 24, 2022 |
| Acer          | Aspire 5742                 | [6692313edb](https://linux-hardware.org/?probe=6692313edb) | Aug 22, 2022 |
| HP            | EliteBook 645 14 inch G9... | [d287893b82](https://linux-hardware.org/?probe=d287893b82) | Aug 22, 2022 |
| Lenovo        | B570e 476022G               | [ad4a4c25d5](https://linux-hardware.org/?probe=ad4a4c25d5) | Aug 22, 2022 |
| Dell          | Latitude E7240              | [4adf6ab444](https://linux-hardware.org/?probe=4adf6ab444) | Aug 22, 2022 |
| Dell          | XPS 13 9350                 | [e663637449](https://linux-hardware.org/?probe=e663637449) | Aug 21, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [2b746c613f](https://linux-hardware.org/?probe=2b746c613f) | Aug 16, 2022 |
| MSI           | GF63 Thin 11UD              | [82bfe63c71](https://linux-hardware.org/?probe=82bfe63c71) | Aug 14, 2022 |
| Acer          | Aspire 6930G                | [c0ba049caf](https://linux-hardware.org/?probe=c0ba049caf) | Aug 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [3dcb75072e](https://linux-hardware.org/?probe=3dcb75072e) | Aug 12, 2022 |
| HP            | Compaq Presario CQ71        | [68c8f97537](https://linux-hardware.org/?probe=68c8f97537) | Aug 11, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | [e2a0bef6d4](https://linux-hardware.org/?probe=e2a0bef6d4) | Aug 10, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | [fc0389fd3e](https://linux-hardware.org/?probe=fc0389fd3e) | Aug 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [4312639df6](https://linux-hardware.org/?probe=4312639df6) | Aug 09, 2022 |
| HP            | EliteBook 820 G1            | [1bdfc2f218](https://linux-hardware.org/?probe=1bdfc2f218) | Aug 09, 2022 |
| Dell          | Latitude E5470              | [8cd7ffad9e](https://linux-hardware.org/?probe=8cd7ffad9e) | Aug 08, 2022 |
| MSI           | GF63 Thin 11UD              | [67e1664484](https://linux-hardware.org/?probe=67e1664484) | Aug 07, 2022 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [6b1d79046a](https://linux-hardware.org/?probe=6b1d79046a) | Aug 06, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | [06da05d12b](https://linux-hardware.org/?probe=06da05d12b) | Aug 03, 2022 |
| Notebook      | NV4XMB,ME,MZ                | [7b369e1cdf](https://linux-hardware.org/?probe=7b369e1cdf) | Aug 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [4bcdc51e89](https://linux-hardware.org/?probe=4bcdc51e89) | Jul 27, 2022 |
| MSI           | GF63 Thin 11UD              | [ce18b4e9ab](https://linux-hardware.org/?probe=ce18b4e9ab) | Jul 26, 2022 |
| Acer          | Aspire 5739G                | [aef89fc83f](https://linux-hardware.org/?probe=aef89fc83f) | Jul 26, 2022 |
| MSI           | GS40 6QE Phantom            | [137d7c8701](https://linux-hardware.org/?probe=137d7c8701) | Jul 26, 2022 |
| MSI           | GS40 6QE Phantom            | [76bd6feebe](https://linux-hardware.org/?probe=76bd6feebe) | Jul 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [37ebea2647](https://linux-hardware.org/?probe=37ebea2647) | Jul 25, 2022 |
| HP            | ProBook 450 G2              | [3e2f9e1e86](https://linux-hardware.org/?probe=3e2f9e1e86) | Jul 25, 2022 |
| Notebook      | NV4XMB,ME,MZ                | [f965008c98](https://linux-hardware.org/?probe=f965008c98) | Jul 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [ca9e042e30](https://linux-hardware.org/?probe=ca9e042e30) | Jul 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [68a78a8ed1](https://linux-hardware.org/?probe=68a78a8ed1) | Jul 18, 2022 |
| Lenovo        | ThinkPad W540 20BG001CMN    | [117f9a585b](https://linux-hardware.org/?probe=117f9a585b) | Jul 17, 2022 |
| Toshiba       | Satellite L500              | [5ac3a7aa95](https://linux-hardware.org/?probe=5ac3a7aa95) | Jul 17, 2022 |
| Lenovo        | ThinkPad W540 20BG001CMN    | [e408c1236c](https://linux-hardware.org/?probe=e408c1236c) | Jul 17, 2022 |
| HP            | ProBook 430 G2              | [0be149d703](https://linux-hardware.org/?probe=0be149d703) | Jul 16, 2022 |
| HUAWEI        | MACH-WX9                    | [76035ea427](https://linux-hardware.org/?probe=76035ea427) | Jul 15, 2022 |
| Dell          | XPS 15 9520                 | [271277c36b](https://linux-hardware.org/?probe=271277c36b) | Jul 14, 2022 |
| MSI           | GF63 Thin 11UD              | [b4cf81df26](https://linux-hardware.org/?probe=b4cf81df26) | Jul 13, 2022 |
| Acer          | Aspire A515-44              | [c0d1086ae8](https://linux-hardware.org/?probe=c0d1086ae8) | Jul 09, 2022 |
| HUAWEI        | MACH-WX9                    | [486d051b71](https://linux-hardware.org/?probe=486d051b71) | Jul 08, 2022 |
| Dell          | Latitude D531               | [008236dd11](https://linux-hardware.org/?probe=008236dd11) | Jul 07, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | [fec0786471](https://linux-hardware.org/?probe=fec0786471) | Jul 06, 2022 |
| MSI           | GF63 Thin 11UD              | [7847c0275c](https://linux-hardware.org/?probe=7847c0275c) | Jul 02, 2022 |
| MSI           | GF63 Thin 11UD              | [325fec2ac6](https://linux-hardware.org/?probe=325fec2ac6) | Jul 01, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [1967dad271](https://linux-hardware.org/?probe=1967dad271) | Jun 22, 2022 |
| Dell          | Latitude E7240              | [1c76f3cdf4](https://linux-hardware.org/?probe=1c76f3cdf4) | Jun 21, 2022 |
| Dell          | Latitude E7240              | [2974c5fa7c](https://linux-hardware.org/?probe=2974c5fa7c) | Jun 21, 2022 |
| HP            | EliteBook 840 G1            | [4a3e29a7c0](https://linux-hardware.org/?probe=4a3e29a7c0) | Jun 20, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [4a1a0294d8](https://linux-hardware.org/?probe=4a1a0294d8) | Jun 18, 2022 |
| Dell          | Latitude E7240              | [2ed64f08f3](https://linux-hardware.org/?probe=2ed64f08f3) | Jun 17, 2022 |
| Dell          | Latitude E7240              | [31340542c2](https://linux-hardware.org/?probe=31340542c2) | Jun 17, 2022 |
| Dell          | Latitude E7240              | [08efb8dcc5](https://linux-hardware.org/?probe=08efb8dcc5) | Jun 17, 2022 |
| Dell          | Latitude E7240              | [b6978a823c](https://linux-hardware.org/?probe=b6978a823c) | Jun 17, 2022 |
| Lenovo        | ThinkPad X220 4286CTO       | [fd2fb2f646](https://linux-hardware.org/?probe=fd2fb2f646) | Jun 14, 2022 |
| HP            | Mini 210-1000               | [8746b5b684](https://linux-hardware.org/?probe=8746b5b684) | Jun 10, 2022 |
| HP            | Mini 210-1000               | [65b65f1319](https://linux-hardware.org/?probe=65b65f1319) | Jun 08, 2022 |
| ASUSTek       | X55U                        | [66e1c7ed1d](https://linux-hardware.org/?probe=66e1c7ed1d) | Jun 06, 2022 |
| Toshiba       | Satellite L500              | [b4b4831c86](https://linux-hardware.org/?probe=b4b4831c86) | Jun 05, 2022 |
| Acer          | Aspire 5739G                | [6f6f16ee08](https://linux-hardware.org/?probe=6f6f16ee08) | May 31, 2022 |
| Notebook      | Multicom Xishan NL50        | [9ffa89c7a9](https://linux-hardware.org/?probe=9ffa89c7a9) | May 31, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [ed28d49715](https://linux-hardware.org/?probe=ed28d49715) | May 30, 2022 |
| Notebook      | Multicom Xishan NL50        | [0c45263f11](https://linux-hardware.org/?probe=0c45263f11) | May 30, 2022 |
| Acer          | Aspire 6930G                | [a07fb7cbcd](https://linux-hardware.org/?probe=a07fb7cbcd) | May 25, 2022 |
| Lenovo        | ThinkPad T490s 20NX0077M... | [cea81a1d63](https://linux-hardware.org/?probe=cea81a1d63) | May 24, 2022 |
| Acer          | Aspire 5739G                | [428631aa4a](https://linux-hardware.org/?probe=428631aa4a) | May 23, 2022 |
| Notebook      | N8xEJEK                     | [5c2c66e8f5](https://linux-hardware.org/?probe=5c2c66e8f5) | May 17, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [48c983a184](https://linux-hardware.org/?probe=48c983a184) | May 15, 2022 |
| Lenovo        | ThinkPad P51 20HJS02H00     | [fc7562c140](https://linux-hardware.org/?probe=fc7562c140) | May 12, 2022 |
| Lenovo        | ThinkPad P51 20HJS02H00     | [810fda94b1](https://linux-hardware.org/?probe=810fda94b1) | May 12, 2022 |
| HP            | ZBook Power 15.6 inch G8... | [c195f80f3c](https://linux-hardware.org/?probe=c195f80f3c) | May 12, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [1b52e22774](https://linux-hardware.org/?probe=1b52e22774) | May 10, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [47b730f9bd](https://linux-hardware.org/?probe=47b730f9bd) | May 10, 2022 |
| Dell          | Latitude E5430 non-vPro     | [2075bfcc02](https://linux-hardware.org/?probe=2075bfcc02) | May 05, 2022 |
| Dell          | Latitude E5430 non-vPro     | [71f8f45765](https://linux-hardware.org/?probe=71f8f45765) | May 05, 2022 |
| HP            | ProBook 4330s               | [7cad0acb2c](https://linux-hardware.org/?probe=7cad0acb2c) | May 04, 2022 |
| HP            | ProBook 4330s               | [ca6474fbfc](https://linux-hardware.org/?probe=ca6474fbfc) | May 04, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [0295d9e820](https://linux-hardware.org/?probe=0295d9e820) | May 04, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFC... | [3835b6bdb8](https://linux-hardware.org/?probe=3835b6bdb8) | May 03, 2022 |
| Apple         | MacBookPro12,1              | [5f68858e66](https://linux-hardware.org/?probe=5f68858e66) | May 01, 2022 |
| HP            | ZBook Firefly 15 inch G8... | [6cdff366fa](https://linux-hardware.org/?probe=6cdff366fa) | Apr 28, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [620718bb9e](https://linux-hardware.org/?probe=620718bb9e) | Apr 26, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [743177a467](https://linux-hardware.org/?probe=743177a467) | Apr 24, 2022 |
| Acer          | Swift SF514-51              | [d6c47a5367](https://linux-hardware.org/?probe=d6c47a5367) | Apr 23, 2022 |
| Dell          | Latitude E6430              | [91bbf4068b](https://linux-hardware.org/?probe=91bbf4068b) | Apr 20, 2022 |
| Google        | Cave                        | [c762019e08](https://linux-hardware.org/?probe=c762019e08) | Apr 18, 2022 |
| Lenovo        | V130-14IKB 81HQ             | [19299bc16d](https://linux-hardware.org/?probe=19299bc16d) | Apr 14, 2022 |
| ASUSTek       | K52Dr                       | [29124147fe](https://linux-hardware.org/?probe=29124147fe) | Apr 14, 2022 |
| Lenovo        | ThinkPad T490s 20NX003UM... | [60dca75a93](https://linux-hardware.org/?probe=60dca75a93) | Apr 14, 2022 |
| HP            | ZBook Power 15.6 inch G8... | [7f83d03bf3](https://linux-hardware.org/?probe=7f83d03bf3) | Apr 13, 2022 |
| HP            | ZBook Power 15.6 inch G8... | [bbcb05781f](https://linux-hardware.org/?probe=bbcb05781f) | Apr 13, 2022 |
| Lenovo        | ThinkPad T460s 20F90044M... | [47498ed4aa](https://linux-hardware.org/?probe=47498ed4aa) | Apr 13, 2022 |
| MSI           | GS66 Stealth 10UH           | [5589b339ed](https://linux-hardware.org/?probe=5589b339ed) | Apr 11, 2022 |
| HP            | EliteBook 840 G4            | [dd511f4bf0](https://linux-hardware.org/?probe=dd511f4bf0) | Apr 09, 2022 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | [5328fde624](https://linux-hardware.org/?probe=5328fde624) | Apr 08, 2022 |
| Dell          | Inspiron 5370               | [abc7562fb9](https://linux-hardware.org/?probe=abc7562fb9) | Apr 07, 2022 |
| MSI           | GS66 Stealth 10UH           | [bd6f031bc8](https://linux-hardware.org/?probe=bd6f031bc8) | Apr 06, 2022 |
| Apple         | MacBookPro11,1              | [f41079b495](https://linux-hardware.org/?probe=f41079b495) | Apr 05, 2022 |
| Lenovo        | ThinkPad T520 4243W83       | [79c6231f19](https://linux-hardware.org/?probe=79c6231f19) | Apr 02, 2022 |
| Dell          | Latitude E5430 non-vPro     | [b47f5b30db](https://linux-hardware.org/?probe=b47f5b30db) | Apr 01, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | [ea012026c5](https://linux-hardware.org/?probe=ea012026c5) | Mar 30, 2022 |
| HP            | Laptop 14s-fq0xxx           | [0a68b0e55c](https://linux-hardware.org/?probe=0a68b0e55c) | Mar 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [f4e2b38106](https://linux-hardware.org/?probe=f4e2b38106) | Mar 20, 2022 |
| ASUSTek       | UL50VT                      | [6911af9ce1](https://linux-hardware.org/?probe=6911af9ce1) | Mar 20, 2022 |
| HP            | ZBook Firefly 15 inch G8... | [674a4429c2](https://linux-hardware.org/?probe=674a4429c2) | Mar 19, 2022 |
| ASUSTek       | GL502VMK                    | [f2fedaa3c3](https://linux-hardware.org/?probe=f2fedaa3c3) | Mar 18, 2022 |
| Notebook      | NV4XMB,ME,MZ                | [ce34107bae](https://linux-hardware.org/?probe=ce34107bae) | Mar 14, 2022 |
| Dell          | XPS 13 9310                 | [acef37559c](https://linux-hardware.org/?probe=acef37559c) | Mar 14, 2022 |
| Dell          | XPS 13 9310                 | [884e853e6f](https://linux-hardware.org/?probe=884e853e6f) | Mar 14, 2022 |
| Intel Clie... | LAPQC71A                    | [14108beccf](https://linux-hardware.org/?probe=14108beccf) | Mar 12, 2022 |
| Intel Clie... | LAPQC71A                    | [ee7f4f0b82](https://linux-hardware.org/?probe=ee7f4f0b82) | Mar 12, 2022 |
| Dell          | Latitude 5480               | [d7fe091593](https://linux-hardware.org/?probe=d7fe091593) | Mar 12, 2022 |
| Dell          | Latitude E5450              | [0e4fb3e1fd](https://linux-hardware.org/?probe=0e4fb3e1fd) | Mar 12, 2022 |
| Dell          | Latitude 7480               | [bb03e5e22e](https://linux-hardware.org/?probe=bb03e5e22e) | Mar 11, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [917a6b65a8](https://linux-hardware.org/?probe=917a6b65a8) | Mar 10, 2022 |
| Dell          | Precision M6800             | [239dd5797a](https://linux-hardware.org/?probe=239dd5797a) | Mar 10, 2022 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [3a9118e8bc](https://linux-hardware.org/?probe=3a9118e8bc) | Mar 07, 2022 |
| ASUSTek       | UL50VT                      | [5a711af850](https://linux-hardware.org/?probe=5a711af850) | Mar 07, 2022 |
| Lenovo        | ThinkPad T480 20L60033MX    | [fda7557aa0](https://linux-hardware.org/?probe=fda7557aa0) | Mar 07, 2022 |
| Lenovo        | ThinkPad T400s 2808D9G      | [6a5d0584bd](https://linux-hardware.org/?probe=6a5d0584bd) | Mar 02, 2022 |
| Lenovo        | ThinkPad T460 20FMS1XX00    | [78e82c6674](https://linux-hardware.org/?probe=78e82c6674) | Feb 24, 2022 |
| Dell          | XPS 15 7590                 | [69896e5117](https://linux-hardware.org/?probe=69896e5117) | Feb 23, 2022 |
| HP            | EliteBook 840 G4            | [7bb148611f](https://linux-hardware.org/?probe=7bb148611f) | Feb 23, 2022 |
| Lenovo        | ThinkPad T460s 20F9S1G20... | [6a6c0b0b39](https://linux-hardware.org/?probe=6a6c0b0b39) | Feb 21, 2022 |
| ASUSTek       | UX430UAR                    | [c7cd5ce50d](https://linux-hardware.org/?probe=c7cd5ce50d) | Feb 21, 2022 |
| Lenovo        | ThinkPad Edge E330 3354D... | [0337480978](https://linux-hardware.org/?probe=0337480978) | Feb 17, 2022 |
| HUAWEI        | KLVL-WXX9                   | [34bd2af067](https://linux-hardware.org/?probe=34bd2af067) | Feb 14, 2022 |
| HP            | ProBook 4330s               | [3781146b1f](https://linux-hardware.org/?probe=3781146b1f) | Feb 14, 2022 |
| ASUSTek       | G74Sx                       | [a3709f6df1](https://linux-hardware.org/?probe=a3709f6df1) | Feb 12, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [68d863ab48](https://linux-hardware.org/?probe=68d863ab48) | Feb 10, 2022 |
| Lenovo        | ThinkPad Edge 0301DMG       | [ab580c3edd](https://linux-hardware.org/?probe=ab580c3edd) | Feb 10, 2022 |
| Lenovo        | ThinkPad Edge 0301DMG       | [c11f9d5c6d](https://linux-hardware.org/?probe=c11f9d5c6d) | Feb 10, 2022 |
| Lenovo        | ThinkPad T470s 20HGS0FJ0... | [6dc9215373](https://linux-hardware.org/?probe=6dc9215373) | Feb 07, 2022 |
| Acer          | Swift SF314-511             | [9f7733e6ec](https://linux-hardware.org/?probe=9f7733e6ec) | Feb 03, 2022 |
| Dell          | Latitude E4200              | [35dbab3b2e](https://linux-hardware.org/?probe=35dbab3b2e) | Jan 31, 2022 |
| Toshiba       | Satellite C660D             | [d6498c16bb](https://linux-hardware.org/?probe=d6498c16bb) | Jan 27, 2022 |
| Lenovo        | ThinkPad T520 4243W83       | [698c80468a](https://linux-hardware.org/?probe=698c80468a) | Jan 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [29ce7637f6](https://linux-hardware.org/?probe=29ce7637f6) | Jan 23, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | [cbf995ff80](https://linux-hardware.org/?probe=cbf995ff80) | Jan 22, 2022 |
| HUAWEI        | KLVL-WXX9                   | [ae399035f5](https://linux-hardware.org/?probe=ae399035f5) | Jan 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [634d45ff9e](https://linux-hardware.org/?probe=634d45ff9e) | Jan 21, 2022 |
| Dell          | Latitude 7280               | [6b9dcc88b7](https://linux-hardware.org/?probe=6b9dcc88b7) | Jan 21, 2022 |
| Dell          | Latitude 7280               | [beb9306791](https://linux-hardware.org/?probe=beb9306791) | Jan 21, 2022 |
| Lenovo        | ThinkPad X230 23252EG       | [e236263783](https://linux-hardware.org/?probe=e236263783) | Jan 19, 2022 |
| Lenovo        | G50-30 80G0                 | [5a609ef492](https://linux-hardware.org/?probe=5a609ef492) | Jan 16, 2022 |
| HP            | Laptop 17-cn0xxx            | [5cb4bc2ed8](https://linux-hardware.org/?probe=5cb4bc2ed8) | Jan 14, 2022 |
| Dell          | Precision 7560              | [a58a852902](https://linux-hardware.org/?probe=a58a852902) | Jan 13, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [9fa645342b](https://linux-hardware.org/?probe=9fa645342b) | Jan 12, 2022 |
| HP            | EliteBook 820 G1            | [37dd78dd6e](https://linux-hardware.org/?probe=37dd78dd6e) | Jan 11, 2022 |
| Apple         | MacBookPro9,2               | [831591fe79](https://linux-hardware.org/?probe=831591fe79) | Jan 11, 2022 |
| MSI           | GS66 Stealth 10UH           | [a38abf3dd0](https://linux-hardware.org/?probe=a38abf3dd0) | Jan 10, 2022 |
| Dell          | Latitude 5480               | [c572bd1eac](https://linux-hardware.org/?probe=c572bd1eac) | Jan 08, 2022 |
| Apple         | MacBookPro9,2               | [b5bd2eca7d](https://linux-hardware.org/?probe=b5bd2eca7d) | Jan 07, 2022 |
| HP            | Pavilion dv6000 (GH912EA... | [a41f8d2d74](https://linux-hardware.org/?probe=a41f8d2d74) | Jan 03, 2022 |
| Dell          | Latitude E7440              | [9df6480d3e](https://linux-hardware.org/?probe=9df6480d3e) | Jan 02, 2022 |
| Lenovo        | ThinkPad T410s 2924W79      | [43fe13f2a4](https://linux-hardware.org/?probe=43fe13f2a4) | Dec 30, 2021 |
| Dell          | Latitude 5480               | [e560c10eb8](https://linux-hardware.org/?probe=e560c10eb8) | Dec 29, 2021 |
| Acer          | Aspire E1-572               | [ab9c63e097](https://linux-hardware.org/?probe=ab9c63e097) | Dec 28, 2021 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | [04ebd359f1](https://linux-hardware.org/?probe=04ebd359f1) | Dec 28, 2021 |
| Acer          | Aspire E1-572               | [63f4428f24](https://linux-hardware.org/?probe=63f4428f24) | Dec 28, 2021 |
| Lenovo        | ThinkPad L512 44444WG       | [0f7bd5b933](https://linux-hardware.org/?probe=0f7bd5b933) | Dec 26, 2021 |
| MSI           | GS66 Stealth 10UH           | [6246228e2d](https://linux-hardware.org/?probe=6246228e2d) | Dec 26, 2021 |
| Lenovo        | ThinkPad L512 44444WG       | [113b39ddbc](https://linux-hardware.org/?probe=113b39ddbc) | Dec 25, 2021 |
| HP            | ZBook 15                    | [57cb28cc81](https://linux-hardware.org/?probe=57cb28cc81) | Dec 24, 2021 |
| Dell          | Latitude 5480               | [5c91ed91a8](https://linux-hardware.org/?probe=5c91ed91a8) | Dec 24, 2021 |
| Acer          | Aspire xxxx                 | [13b21c09d2](https://linux-hardware.org/?probe=13b21c09d2) | Dec 23, 2021 |
| Dell          | XPS 15 9500                 | [86789982ba](https://linux-hardware.org/?probe=86789982ba) | Dec 21, 2021 |
| Lenovo        | ThinkPad E580 20KS001EMX    | [366aae1cd6](https://linux-hardware.org/?probe=366aae1cd6) | Dec 18, 2021 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [3cd4b5c111](https://linux-hardware.org/?probe=3cd4b5c111) | Dec 18, 2021 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [03115bdd2e](https://linux-hardware.org/?probe=03115bdd2e) | Dec 18, 2021 |
| Lenovo        | ThinkPad T410s 2924W79      | [f26b8b4f98](https://linux-hardware.org/?probe=f26b8b4f98) | Dec 17, 2021 |
| Acer          | Aspire xxxx                 | [dfa568d766](https://linux-hardware.org/?probe=dfa568d766) | Dec 17, 2021 |
| Toshiba       | Satellite L750              | [30ad7918cd](https://linux-hardware.org/?probe=30ad7918cd) | Dec 13, 2021 |
| Acer          | Aspire A114-32              | [dd9fb384ea](https://linux-hardware.org/?probe=dd9fb384ea) | Dec 13, 2021 |
| Lenovo        | ThinkPad L512 44444WG       | [711aa97225](https://linux-hardware.org/?probe=711aa97225) | Dec 13, 2021 |
| HP            | ZBook 15                    | [cb2487cb67](https://linux-hardware.org/?probe=cb2487cb67) | Dec 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [204f77ca68](https://linux-hardware.org/?probe=204f77ca68) | Dec 10, 2021 |
| HP            | ZBook 15                    | [c0d2e24505](https://linux-hardware.org/?probe=c0d2e24505) | Dec 10, 2021 |
| ASUSTek       | N550JV                      | [696dd578ab](https://linux-hardware.org/?probe=696dd578ab) | Dec 08, 2021 |
| HP            | OMEN by Laptop              | [b44117a400](https://linux-hardware.org/?probe=b44117a400) | Dec 06, 2021 |
| Dell          | Inspiron M5030              | [b28a3fe6a7](https://linux-hardware.org/?probe=b28a3fe6a7) | Dec 05, 2021 |
| ASUSTek       | ZenBook UX425EA_BX425EA     | [c579de06b5](https://linux-hardware.org/?probe=c579de06b5) | Dec 03, 2021 |
| Lenovo        | ThinkPad T580 20LAS2BH00    | [e85a481d36](https://linux-hardware.org/?probe=e85a481d36) | Dec 02, 2021 |
| Acer          | Aspire A114-32              | [64005f7018](https://linux-hardware.org/?probe=64005f7018) | Nov 30, 2021 |
| Dell          | Inspiron 15-3552            | [7fbb6be9e3](https://linux-hardware.org/?probe=7fbb6be9e3) | Nov 30, 2021 |
| Acer          | Aspire A114-32              | [a380d2a0c8](https://linux-hardware.org/?probe=a380d2a0c8) | Nov 29, 2021 |
| Acer          | Aspire A315-42              | [a0483c5539](https://linux-hardware.org/?probe=a0483c5539) | Nov 27, 2021 |
| HP            | EliteBook 8460p             | [ca30b13118](https://linux-hardware.org/?probe=ca30b13118) | Nov 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [969dde57b0](https://linux-hardware.org/?probe=969dde57b0) | Nov 22, 2021 |
| Lenovo        | ThinkPad L512 44444WG       | [1d12ea147a](https://linux-hardware.org/?probe=1d12ea147a) | Nov 20, 2021 |
| Dell          | Latitude E7440              | [89fdff42c1](https://linux-hardware.org/?probe=89fdff42c1) | Nov 20, 2021 |
| Acer          | Aspire 5810T                | [c6e0003dcb](https://linux-hardware.org/?probe=c6e0003dcb) | Nov 20, 2021 |
| Acer          | Aspire 5810T                | [6b485f4c9a](https://linux-hardware.org/?probe=6b485f4c9a) | Nov 20, 2021 |
| Acer          | Swift SF514-51              | [07e73dc8ab](https://linux-hardware.org/?probe=07e73dc8ab) | Nov 19, 2021 |
| Lenovo        | ThinkPad T520 42433VG       | [529262c2e4](https://linux-hardware.org/?probe=529262c2e4) | Nov 17, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | [6196137046](https://linux-hardware.org/?probe=6196137046) | Nov 17, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [564ef15a99](https://linux-hardware.org/?probe=564ef15a99) | Nov 16, 2021 |
| HP            | ProBook 440 G4              | [f5d53e44ae](https://linux-hardware.org/?probe=f5d53e44ae) | Nov 15, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [bb1201e75c](https://linux-hardware.org/?probe=bb1201e75c) | Nov 06, 2021 |
| Lenovo        | ThinkPad W540 20BHS0NQ00    | [69f4b3d974](https://linux-hardware.org/?probe=69f4b3d974) | Nov 03, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [0b7ae3ebf5](https://linux-hardware.org/?probe=0b7ae3ebf5) | Nov 03, 2021 |
| Dell          | XPS 13 9370                 | [458d3682a5](https://linux-hardware.org/?probe=458d3682a5) | Nov 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [070b533b05](https://linux-hardware.org/?probe=070b533b05) | Nov 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [3acc230d6a](https://linux-hardware.org/?probe=3acc230d6a) | Nov 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [c88adaac6e](https://linux-hardware.org/?probe=c88adaac6e) | Nov 02, 2021 |
| Acer          | Aspire 5739G                | [9366122bdb](https://linux-hardware.org/?probe=9366122bdb) | Nov 01, 2021 |
| Acer          | Aspire 5739G                | [aaf8f33249](https://linux-hardware.org/?probe=aaf8f33249) | Nov 01, 2021 |
| Acer          | Aspire 5739G                | [7979c29593](https://linux-hardware.org/?probe=7979c29593) | Oct 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [2eac1bfc4f](https://linux-hardware.org/?probe=2eac1bfc4f) | Oct 24, 2021 |
| Lenovo        | ThinkPad T450s 20BWS3EG0... | [df466b506d](https://linux-hardware.org/?probe=df466b506d) | Oct 20, 2021 |
| Lenovo        | ThinkPad T450s 20BWS3EG0... | [748d3e56a7](https://linux-hardware.org/?probe=748d3e56a7) | Oct 20, 2021 |
| HP            | EliteBook 820 G1            | [278ec34902](https://linux-hardware.org/?probe=278ec34902) | Oct 19, 2021 |
| Dell          | XPS 15 9570                 | [26d1a4225d](https://linux-hardware.org/?probe=26d1a4225d) | Oct 17, 2021 |
| Lenovo        | ThinkPad X260 20F5S08Q00    | [2929e779ad](https://linux-hardware.org/?probe=2929e779ad) | Oct 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [fe7520a392](https://linux-hardware.org/?probe=fe7520a392) | Oct 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [8fab065f3b](https://linux-hardware.org/?probe=8fab065f3b) | Oct 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [8502c5d5f7](https://linux-hardware.org/?probe=8502c5d5f7) | Oct 13, 2021 |
| Lenovo        | ThinkPad T460p 20FWCTO1W... | [d7f1b3f27e](https://linux-hardware.org/?probe=d7f1b3f27e) | Oct 12, 2021 |
| Acer          | Aspire A515-45              | [4b45531984](https://linux-hardware.org/?probe=4b45531984) | Oct 09, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [4206d52561](https://linux-hardware.org/?probe=4206d52561) | Oct 07, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [8e94483caf](https://linux-hardware.org/?probe=8e94483caf) | Oct 07, 2021 |
| HP            | EliteBook 840 G5            | [e64aeb5fa4](https://linux-hardware.org/?probe=e64aeb5fa4) | Oct 01, 2021 |
| HP            | EliteBook 840 G5            | [28bfae31ee](https://linux-hardware.org/?probe=28bfae31ee) | Oct 01, 2021 |
| Acer          | Aspire A114-32              | [e1dc7a64a4](https://linux-hardware.org/?probe=e1dc7a64a4) | Sep 30, 2021 |
| Dell          | Latitude E5530 non-vPro     | [7e710da685](https://linux-hardware.org/?probe=7e710da685) | Sep 27, 2021 |
| Dell          | Latitude E5530 non-vPro     | [87dd9f48a9](https://linux-hardware.org/?probe=87dd9f48a9) | Sep 26, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [bf5a5a2c74](https://linux-hardware.org/?probe=bf5a5a2c74) | Sep 26, 2021 |
| Apple         | MacBookPro12,1              | [4d798633db](https://linux-hardware.org/?probe=4d798633db) | Sep 25, 2021 |
| Dell          | XPS 15 9570                 | [a54466b990](https://linux-hardware.org/?probe=a54466b990) | Sep 24, 2021 |
| ASUSTek       | E403NA                      | [382c1a7b47](https://linux-hardware.org/?probe=382c1a7b47) | Sep 24, 2021 |
| Dell          | Latitude E5470              | [17d97e59de](https://linux-hardware.org/?probe=17d97e59de) | Sep 23, 2021 |
| ASUSTek       | E402NA                      | [8262dd102f](https://linux-hardware.org/?probe=8262dd102f) | Sep 23, 2021 |
| Lenovo        | ThinkPad E15 20RES6DF07     | [2f5045ab95](https://linux-hardware.org/?probe=2f5045ab95) | Sep 21, 2021 |
| Acer          | Aspire A114-32              | [333d881ec2](https://linux-hardware.org/?probe=333d881ec2) | Sep 20, 2021 |
| Acer          | Aspire A114-32              | [da860f1378](https://linux-hardware.org/?probe=da860f1378) | Sep 20, 2021 |
| HUAWEI        | EUL-WX9                     | [4ab59b64df](https://linux-hardware.org/?probe=4ab59b64df) | Sep 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [b640e5da6d](https://linux-hardware.org/?probe=b640e5da6d) | Sep 17, 2021 |
| Dell          | Latitude 5480               | [ac2c5649d3](https://linux-hardware.org/?probe=ac2c5649d3) | Sep 17, 2021 |
| Dell          | Latitude E5470              | [82aca1d7b4](https://linux-hardware.org/?probe=82aca1d7b4) | Sep 16, 2021 |
| Dell          | Latitude E5470              | [c898d2b210](https://linux-hardware.org/?probe=c898d2b210) | Sep 16, 2021 |
| HP            | ZBook 15u G5                | [a5331a4d5e](https://linux-hardware.org/?probe=a5331a4d5e) | Sep 15, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | [a92f9c3457](https://linux-hardware.org/?probe=a92f9c3457) | Sep 15, 2021 |
| HP            | EliteBook 820 G1            | [cf1e0581f3](https://linux-hardware.org/?probe=cf1e0581f3) | Sep 15, 2021 |
| MSI           | Alpha 17 A4DE               | [0be8b0b607](https://linux-hardware.org/?probe=0be8b0b607) | Sep 14, 2021 |
| Lenovo        | ThinkPad E590 20NBCTO1WW    | [2b5735f34c](https://linux-hardware.org/?probe=2b5735f34c) | Sep 13, 2021 |
| Samsung       | RF511/RF411/RF711           | [0918a27e6a](https://linux-hardware.org/?probe=0918a27e6a) | Sep 08, 2021 |
| Acer          | Aspire 5745G                | [680d788d4b](https://linux-hardware.org/?probe=680d788d4b) | Sep 07, 2021 |
| MSI           | Alpha 17 A4DE               | [3f0de31253](https://linux-hardware.org/?probe=3f0de31253) | Sep 06, 2021 |
| Dell          | Precision 5510              | [1339721ac0](https://linux-hardware.org/?probe=1339721ac0) | Sep 06, 2021 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [7bc3201683](https://linux-hardware.org/?probe=7bc3201683) | Sep 06, 2021 |
| Samsung       | RF511/RF411/RF711           | [332124aa7f](https://linux-hardware.org/?probe=332124aa7f) | Sep 04, 2021 |
| Acer          | Aspire A515-45              | [16a250faf6](https://linux-hardware.org/?probe=16a250faf6) | Sep 01, 2021 |
| Acer          | Aspire E1-772               | [2b6d07434a](https://linux-hardware.org/?probe=2b6d07434a) | Sep 01, 2021 |
| Dell          | Latitude E7270              | [1bd5f17116](https://linux-hardware.org/?probe=1bd5f17116) | Sep 01, 2021 |
| Acer          | Aspire E1-772               | [4c1d560351](https://linux-hardware.org/?probe=4c1d560351) | Sep 01, 2021 |
| ASUSTek       | UX430UQ                     | [2bd5adb706](https://linux-hardware.org/?probe=2bd5adb706) | Aug 31, 2021 |
| Lenovo        | G710 20252                  | [bcb68ab6d0](https://linux-hardware.org/?probe=bcb68ab6d0) | Aug 21, 2021 |
| Dell          | Studio 1747                 | [ba0f2b7d03](https://linux-hardware.org/?probe=ba0f2b7d03) | Aug 15, 2021 |
| Teclast       | F6 Plus                     | [a1df449dea](https://linux-hardware.org/?probe=a1df449dea) | Aug 13, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [5742cb7dd7](https://linux-hardware.org/?probe=5742cb7dd7) | Aug 12, 2021 |
| Alienware     | x17 R1                      | [447d4de752](https://linux-hardware.org/?probe=447d4de752) | Aug 12, 2021 |
| Clevo         | W55xEU                      | [ee96e1ca32](https://linux-hardware.org/?probe=ee96e1ca32) | Aug 08, 2021 |
| Lenovo        | ThinkPad X240 20AMS0BU0T    | [f22b591a0a](https://linux-hardware.org/?probe=f22b591a0a) | Aug 07, 2021 |
| Lenovo        | ThinkPad T440s 20ARA1DJM... | [3d02d8b67f](https://linux-hardware.org/?probe=3d02d8b67f) | Aug 07, 2021 |
| Apple         | MacBookPro11,5              | [938ff270ef](https://linux-hardware.org/?probe=938ff270ef) | Jul 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [b62fb400bf](https://linux-hardware.org/?probe=b62fb400bf) | Jul 31, 2021 |
| HP            | ProBook 4740s               | [624b649eb0](https://linux-hardware.org/?probe=624b649eb0) | Jul 28, 2021 |
| HP            | EliteBook 1040 G4           | [693137b6b8](https://linux-hardware.org/?probe=693137b6b8) | Jul 26, 2021 |
| Dell          | Latitude 5480               | [64665ed287](https://linux-hardware.org/?probe=64665ed287) | Jul 25, 2021 |
| Dell          | Latitude 5480               | [1b32299688](https://linux-hardware.org/?probe=1b32299688) | Jul 24, 2021 |
| HP            | Presario CQ56               | [7148aa989e](https://linux-hardware.org/?probe=7148aa989e) | Jul 21, 2021 |
| Apple         | MacBook8,1                  | [1220a734d7](https://linux-hardware.org/?probe=1220a734d7) | Jul 20, 2021 |
| Packard Be... | EasyNote ENTG71BM           | [788b497894](https://linux-hardware.org/?probe=788b497894) | Jul 19, 2021 |
| Dell          | XPS 15 9500                 | [610bb918de](https://linux-hardware.org/?probe=610bb918de) | Jul 14, 2021 |
| Notebook      | NV4XMB,ME,MZ                | [eba2e6ade8](https://linux-hardware.org/?probe=eba2e6ade8) | Jul 13, 2021 |
| HP            | Presario CQ56               | [7a202a99e9](https://linux-hardware.org/?probe=7a202a99e9) | Jul 11, 2021 |
| Acer          | Aspire E5-575G              | [27fd4c16ae](https://linux-hardware.org/?probe=27fd4c16ae) | Jul 08, 2021 |
| Lenovo        | IdeaPad 320-17AST 80XW      | [b8a40b6dbd](https://linux-hardware.org/?probe=b8a40b6dbd) | Jul 02, 2021 |
| Lenovo        | G50-80 80L0                 | [ca1d482329](https://linux-hardware.org/?probe=ca1d482329) | Jun 27, 2021 |
| Lenovo        | ThinkPad X230 23252EG       | [77c68fb077](https://linux-hardware.org/?probe=77c68fb077) | Jun 23, 2021 |
| Lenovo        | ThinkPad T460s 20FA0047M... | [eeb383631b](https://linux-hardware.org/?probe=eeb383631b) | Jun 20, 2021 |
| Lenovo        | ThinkPad T520 4243W83       | [b17a1f2c15](https://linux-hardware.org/?probe=b17a1f2c15) | Jun 19, 2021 |
| HP            | EliteBook 820 G1            | [09ff787c3f](https://linux-hardware.org/?probe=09ff787c3f) | Jun 17, 2021 |
| HP            | EliteBook 820 G1            | [b64bd1afcd](https://linux-hardware.org/?probe=b64bd1afcd) | Jun 17, 2021 |
| Lenovo        | ThinkPad T580 20LAS2BH00    | [bbedefdee0](https://linux-hardware.org/?probe=bbedefdee0) | Jun 16, 2021 |
| Dell          | XPS 13 9380                 | [41972327e1](https://linux-hardware.org/?probe=41972327e1) | Jun 15, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [4ecc3eec8f](https://linux-hardware.org/?probe=4ecc3eec8f) | Jun 14, 2021 |
| Lenovo        | ThinkPad T440p 20AW0048G... | [8b1ba139f9](https://linux-hardware.org/?probe=8b1ba139f9) | Jun 13, 2021 |
| Lenovo        | ThinkPad T580 20LAS2BH00    | [9674952e07](https://linux-hardware.org/?probe=9674952e07) | Jun 11, 2021 |
| Lenovo        | ThinkPad T580 20LAS2BH00    | [b39699b009](https://linux-hardware.org/?probe=b39699b009) | Jun 11, 2021 |
| Lenovo        | ThinkPad T410s 291236G      | [ebbdc74a27](https://linux-hardware.org/?probe=ebbdc74a27) | Jun 06, 2021 |
| Acer          | Nitro AN515-42              | [28aadacd07](https://linux-hardware.org/?probe=28aadacd07) | Jun 02, 2021 |
| Lenovo        | ThinkPad T430s 2356GBG      | [aef8c27b50](https://linux-hardware.org/?probe=aef8c27b50) | May 31, 2021 |
| Lenovo        | ThinkPad T430s 2356GBG      | [e67f4b0fd4](https://linux-hardware.org/?probe=e67f4b0fd4) | May 31, 2021 |
| HUAWEI        | MACH-WX9                    | [7fd687d091](https://linux-hardware.org/?probe=7fd687d091) | May 29, 2021 |
| Lenovo        | ThinkPad T450 20BUS0WK03    | [6131e3c22a](https://linux-hardware.org/?probe=6131e3c22a) | May 27, 2021 |
| ASUSTek       | N53TK                       | [cee81adbaf](https://linux-hardware.org/?probe=cee81adbaf) | May 25, 2021 |
| Dell          | XPS 15 9500                 | [8c072ea1c4](https://linux-hardware.org/?probe=8c072ea1c4) | May 24, 2021 |
| Acer          | Aspire 5745G                | [30f455f132](https://linux-hardware.org/?probe=30f455f132) | May 22, 2021 |
| HP            | Spectre Pro x360 G2         | [236efc033e](https://linux-hardware.org/?probe=236efc033e) | May 21, 2021 |
| Razer         | Blade 15 Base Model (Ear... | [2b97441fb1](https://linux-hardware.org/?probe=2b97441fb1) | May 17, 2021 |
| Razer         | Blade 15 Base Model (Ear... | [f9420a7960](https://linux-hardware.org/?probe=f9420a7960) | May 16, 2021 |
| Acer          | Aspire 5745G                | [cb987a733a](https://linux-hardware.org/?probe=cb987a733a) | May 15, 2021 |
| Lenovo        | ThinkPad X230 2325AJG       | [c4b7c3340c](https://linux-hardware.org/?probe=c4b7c3340c) | May 11, 2021 |
| Toshiba       | Satellite L510              | [01753d1f93](https://linux-hardware.org/?probe=01753d1f93) | May 02, 2021 |
| Acer          | TravelMate 8472             | [bdf53780fb](https://linux-hardware.org/?probe=bdf53780fb) | May 01, 2021 |
| Lenovo        | ThinkPad T490s 20NX0054M... | [4cc25622a5](https://linux-hardware.org/?probe=4cc25622a5) | Apr 28, 2021 |
| Acer          | TravelMate 8472             | [84fea7d029](https://linux-hardware.org/?probe=84fea7d029) | Apr 25, 2021 |
| Acer          | TravelMate 8472             | [a4aafc8541](https://linux-hardware.org/?probe=a4aafc8541) | Apr 25, 2021 |
| MSI           | GP70 2QF                    | [3e3f73559d](https://linux-hardware.org/?probe=3e3f73559d) | Apr 23, 2021 |
| MSI           | GP70 2QF                    | [22e9e676d9](https://linux-hardware.org/?probe=22e9e676d9) | Apr 23, 2021 |
| Samsung       | 900X3C/900X3D/900X4C/900... | [58df3a61b0](https://linux-hardware.org/?probe=58df3a61b0) | Apr 21, 2021 |
| Dell          | Precision M4500             | [8c35250407](https://linux-hardware.org/?probe=8c35250407) | Apr 17, 2021 |
| ASUSTek       | Zephyrus M GU502GU_GU502... | [67c2373bdf](https://linux-hardware.org/?probe=67c2373bdf) | Apr 15, 2021 |
| ASUSTek       | Zephyrus M GU502GU_GU502... | [db960abcdb](https://linux-hardware.org/?probe=db960abcdb) | Apr 15, 2021 |
| Dell          | XPS 13 9380                 | [cf23d87096](https://linux-hardware.org/?probe=cf23d87096) | Apr 08, 2021 |
| Acer          | NU-A515-44-R68D             | [7e8724905f](https://linux-hardware.org/?probe=7e8724905f) | Apr 06, 2021 |
| Dell          | XPS 13 9380                 | [1631f6bb81](https://linux-hardware.org/?probe=1631f6bb81) | Apr 06, 2021 |
| HP            | ProBook 430 G1              | [6d2b17825a](https://linux-hardware.org/?probe=6d2b17825a) | Apr 05, 2021 |
| Dell          | Latitude E6530              | [0078b55697](https://linux-hardware.org/?probe=0078b55697) | Apr 05, 2021 |
| Acer          | Aspire V3-571G              | [a5268098b2](https://linux-hardware.org/?probe=a5268098b2) | Apr 02, 2021 |
| Dell          | Studio 1747                 | [31c1b6a828](https://linux-hardware.org/?probe=31c1b6a828) | Apr 01, 2021 |
| HP            | Pavilion Notebook           | [6189b0e033](https://linux-hardware.org/?probe=6189b0e033) | Mar 27, 2021 |
| HP            | Pavilion Notebook           | [df09bd2c58](https://linux-hardware.org/?probe=df09bd2c58) | Mar 25, 2021 |
| Dell          | Latitude E6530              | [7cce6316f6](https://linux-hardware.org/?probe=7cce6316f6) | Mar 24, 2021 |
| Lenovo        | ThinkPad X201 4492A23       | [0cace83a52](https://linux-hardware.org/?probe=0cace83a52) | Mar 23, 2021 |
| ASUSTek       | GL553VW                     | [7d8aed9645](https://linux-hardware.org/?probe=7d8aed9645) | Mar 21, 2021 |
| Acer          | Nitro AN515-51              | [79b5d4aed8](https://linux-hardware.org/?probe=79b5d4aed8) | Mar 16, 2021 |
| Acer          | Nitro AN515-51              | [ac92ab9404](https://linux-hardware.org/?probe=ac92ab9404) | Mar 15, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [1725699a96](https://linux-hardware.org/?probe=1725699a96) | Mar 12, 2021 |
| Lenovo        | ThinkPad X230 2325AJG       | [f55532e284](https://linux-hardware.org/?probe=f55532e284) | Mar 12, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [e74933164b](https://linux-hardware.org/?probe=e74933164b) | Mar 10, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [406b41e802](https://linux-hardware.org/?probe=406b41e802) | Mar 10, 2021 |
| HP            | EliteBook 830 G6            | [45f8bdabb0](https://linux-hardware.org/?probe=45f8bdabb0) | Mar 09, 2021 |
| HP            | EliteBook 830 G6            | [de6b1ee9fe](https://linux-hardware.org/?probe=de6b1ee9fe) | Mar 09, 2021 |
| HP            | EliteBook 8470p             | [d97eb7724a](https://linux-hardware.org/?probe=d97eb7724a) | Mar 04, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Norway/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 83        | 9.34%   |
| Ubuntu 22.04                 | 60        | 6.75%   |
| Pop!_OS 22.04                | 38        | 4.27%   |
| Ubuntu 18.04                 | 36        | 4.05%   |
| Arch Rolling                 | 28        | 3.15%   |
| Debian 11                    | 22        | 2.47%   |
| Fedora 40                    | 21        | 2.36%   |
| Debian 12                    | 20        | 2.25%   |
| ArcoLinux Rolling            | 18        | 2.02%   |
| Ubuntu 23.04                 | 17        | 1.91%   |
| Zorin 16                     | 16        | 1.8%    |
| Ubuntu 24.04                 | 14        | 1.57%   |
| Fedora 35                    | 13        | 1.46%   |
| OpenMandriva 4.2             | 11        | 1.24%   |
| Manjaro                      | 11        | 1.24%   |
| Fedora 39                    | 11        | 1.24%   |
| Fedora 38                    | 11        | 1.24%   |
| Fedora 31                    | 11        | 1.24%   |
| Ubuntu 23.10                 | 10        | 1.12%   |
| Ubuntu 22.10                 | 10        | 1.12%   |
| Ubuntu 20.10                 | 10        | 1.12%   |
| KDE neon 20.04               | 10        | 1.12%   |
| Pop!_OS 21.10                | 9         | 1.01%   |
| openSUSE Tumbleweed-XXXXXXXX | 9         | 1.01%   |
| OpenMandriva 4.3             | 9         | 1.01%   |
| Linux Mint 20.3              | 9         | 1.01%   |
| Fedora 36                    | 9         | 1.01%   |
| Fedora 34                    | 9         | 1.01%   |
| Ubuntu 19.04                 | 8         | 0.9%    |
| Pop!_OS 21.04                | 8         | 0.9%    |
| Pop!_OS 20.10                | 8         | 0.9%    |
| Linux Mint 21.3              | 8         | 0.9%    |
| Linux Mint 20.2              | 8         | 0.9%    |
| KDE neon 22.04               | 8         | 0.9%    |
| Zorin 17                     | 7         | 0.79%   |
| Xubuntu 20.04                | 7         | 0.79%   |
| Ubuntu 19.10                 | 6         | 0.67%   |
| Pop!_OS 20.04                | 6         | 0.67%   |
| OpenMandriva 5.0             | 6         | 0.67%   |
| OpenMandriva 24.07           | 6         | 0.67%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 256       | 30.62%  |
| Fedora        | 93        | 11.12%  |
| Pop!_OS       | 66        | 7.89%   |
| Linux Mint    | 52        | 6.22%   |
| Debian        | 51        | 6.1%    |
| OpenMandriva  | 48        | 5.74%   |
| Arch          | 32        | 3.83%   |
| Manjaro       | 29        | 3.47%   |
| Zorin         | 28        | 3.35%   |
| KDE neon      | 21        | 2.51%   |
| ArcoLinux     | 18        | 2.15%   |
| openSUSE      | 13        | 1.56%   |
| Xubuntu       | 11        | 1.32%   |
| Kubuntu       | 11        | 1.32%   |
| Kali          | 11        | 1.32%   |
| Elementary    | 11        | 1.32%   |
| Ubuntu MATE   | 7         | 0.84%   |
| ROSA          | 6         | 0.72%   |
| Gentoo        | 6         | 0.72%   |
| EndeavourOS   | 6         | 0.72%   |
| Lubuntu       | 5         | 0.6%    |
| Xero          | 4         | 0.48%   |
| Ubuntu Budgie | 4         | 0.48%   |
| NixOS         | 4         | 0.48%   |
| MX            | 4         | 0.48%   |
| TUXEDO OS     | 3         | 0.36%   |
| Nobara        | 3         | 0.36%   |
| LMDE          | 3         | 0.36%   |
| Clear Linux   | 3         | 0.36%   |
| CentOS        | 3         | 0.36%   |
| Bazzite       | 3         | 0.36%   |
| Void Linux    | 2         | 0.24%   |
| Ubuntu Unity  | 2         | 0.24%   |
| Ubuntu Studio | 2         | 0.24%   |
| Solus         | 2         | 0.24%   |
| Parrot        | 2         | 0.24%   |
| Devuan        | 2         | 0.24%   |
| Rocky Linux   | 1         | 0.12%   |
| RHEL          | 1         | 0.12%   |
| Pikaos        | 1         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002            | 10        | 1.01%   |
| 5.4.0-42-generic                    | 9         | 0.91%   |
| 6.2.0-39-generic                    | 8         | 0.81%   |
| 6.2.0-20-generic                    | 8         | 0.81%   |
| 5.16.7-desktop-1omv4003             | 8         | 0.81%   |
| 6.8.0-45-generic                    | 7         | 0.71%   |
| 5.3.0-46-generic                    | 7         | 0.71%   |
| 5.15.0-46-generic                   | 7         | 0.71%   |
| 6.6.2-desktop-1omv2390              | 6         | 0.61%   |
| 6.2.6-desktop-1omv2390              | 6         | 0.61%   |
| 6.2.6-76060206-generic              | 6         | 0.61%   |
| 6.2.0-26-generic                    | 6         | 0.61%   |
| 5.4.0-58-generic                    | 6         | 0.61%   |
| 5.19.0-76051900-generic             | 6         | 0.61%   |
| 5.15.0-48-generic                   | 6         | 0.61%   |
| 5.11.0-40-generic                   | 6         | 0.61%   |
| 6.8.0-40-generic                    | 5         | 0.51%   |
| 6.5.6-76060506-generic              | 5         | 0.51%   |
| 6.4.6-76060406-generic              | 5         | 0.51%   |
| 6.10.0-desktop-1omv2490             | 5         | 0.51%   |
| 5.8.0-44-generic                    | 5         | 0.51%   |
| 5.4.0-91-generic                    | 5         | 0.51%   |
| 5.4.0-74-generic                    | 5         | 0.51%   |
| 5.4.0-48-generic                    | 5         | 0.51%   |
| 5.4.0-26-generic                    | 5         | 0.51%   |
| 6.8.0-76060800daily20240311-generic | 4         | 0.4%    |
| 6.8.0-49-generic                    | 4         | 0.4%    |
| 6.8.0-31-generic                    | 4         | 0.4%    |
| 6.5.0-41-generic                    | 4         | 0.4%    |
| 6.5.0-28-generic                    | 4         | 0.4%    |
| 6.5.0-27-generic                    | 4         | 0.4%    |
| 6.5.0-14-generic                    | 4         | 0.4%    |
| 6.10.6-200.fc40.x86_64              | 4         | 0.4%    |
| 6.1.1-desktop-1omv2290              | 4         | 0.4%    |
| 6.0.12-76060006-generic             | 4         | 0.4%    |
| 5.8.0-7630-generic                  | 4         | 0.4%    |
| 5.8.0-43-generic                    | 4         | 0.4%    |
| 5.4.0-45-generic                    | 4         | 0.4%    |
| 5.4.0-33-generic                    | 4         | 0.4%    |
| 5.3.0-40-generic                    | 4         | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 103       | 10.98%  |
| 5.15.0  | 61        | 6.5%    |
| 6.2.0   | 42        | 4.48%   |
| 6.5.0   | 34        | 3.62%   |
| 6.8.0   | 33        | 3.52%   |
| 5.19.0  | 33        | 3.52%   |
| 5.8.0   | 32        | 3.41%   |
| 5.11.0  | 29        | 3.09%   |
| 4.15.0  | 25        | 2.67%   |
| 6.1.0   | 24        | 2.56%   |
| 5.3.0   | 23        | 2.45%   |
| 5.10.0  | 22        | 2.35%   |
| 5.13.0  | 21        | 2.24%   |
| 5.0.0   | 15        | 1.6%    |
| 6.2.6   | 13        | 1.39%   |
| 4.18.0  | 12        | 1.28%   |
| 5.10.14 | 10        | 1.07%   |
| 5.16.7  | 8         | 0.85%   |
| 6.6.2   | 6         | 0.64%   |
| 6.5.6   | 6         | 0.64%   |
| 6.5.3   | 6         | 0.64%   |
| 6.11.0  | 6         | 0.64%   |
| 6.8.7   | 5         | 0.53%   |
| 6.4.6   | 5         | 0.53%   |
| 6.4.12  | 5         | 0.53%   |
| 6.12.1  | 5         | 0.53%   |
| 6.10.6  | 5         | 0.53%   |
| 6.10.0  | 5         | 0.53%   |
| 5.17.5  | 5         | 0.53%   |
| 5.17.0  | 5         | 0.53%   |
| 5.16.11 | 5         | 0.53%   |
| 6.9.7   | 4         | 0.43%   |
| 6.9.3   | 4         | 0.43%   |
| 6.4.0   | 4         | 0.43%   |
| 6.1.1   | 4         | 0.43%   |
| 6.0.12  | 4         | 0.43%   |
| 6.0.0   | 4         | 0.43%   |
| 5.18.0  | 4         | 0.43%   |
| 5.17.15 | 4         | 0.43%   |
| 5.14.0  | 4         | 0.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 115       | 12.49%  |
| 5.15    | 77        | 8.36%   |
| 6.2     | 59        | 6.41%   |
| 6.5     | 50        | 5.43%   |
| 6.8     | 46        | 4.99%   |
| 6.1     | 41        | 4.45%   |
| 5.19    | 41        | 4.45%   |
| 5.10    | 40        | 4.34%   |
| 5.8     | 38        | 4.13%   |
| 5.13    | 36        | 3.91%   |
| 5.11    | 35        | 3.8%    |
| 5.3     | 31        | 3.37%   |
| 5.16    | 27        | 2.93%   |
| 4.15    | 25        | 2.71%   |
| 6.6     | 22        | 2.39%   |
| 6.4     | 22        | 2.39%   |
| 6.10    | 21        | 2.28%   |
| 5.17    | 20        | 2.17%   |
| 6.9     | 17        | 1.85%   |
| 6.0     | 17        | 1.85%   |
| 6.11    | 16        | 1.74%   |
| 5.14    | 16        | 1.74%   |
| 5.0     | 15        | 1.63%   |
| 4.18    | 15        | 1.63%   |
| 5.9     | 11        | 1.19%   |
| 5.18    | 11        | 1.19%   |
| 6.12    | 9         | 0.98%   |
| 6.7     | 8         | 0.87%   |
| 6.3     | 8         | 0.87%   |
| 5.12    | 8         | 0.87%   |
| 4.19    | 6         | 0.65%   |
| 5.5     | 5         | 0.54%   |
| 5.7     | 3         | 0.33%   |
| 4.9     | 3         | 0.33%   |
| 5.6     | 2         | 0.22%   |
| 5.2     | 2         | 0.22%   |
| 5.1     | 2         | 0.22%   |
| 4.4     | 1         | 0.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 787       | 98.38%  |
| i686   | 12        | 1.5%    |
| armv7l | 1         | 0.13%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 406       | 48.56%  |
| KDE5              | 121       | 14.47%  |
| Unknown           | 84        | 10.05%  |
| XFCE              | 75        | 8.97%   |
| X-Cinnamon        | 40        | 4.78%   |
| MATE              | 17        | 2.03%   |
| KDE6              | 13        | 1.56%   |
| KDE               | 13        | 1.56%   |
| Pantheon          | 11        | 1.32%   |
| i3                | 10        | 1.2%    |
| LXQt              | 9         | 1.08%   |
| Cinnamon          | 8         | 0.96%   |
| GNOME Flashback   | 6         | 0.72%   |
| Budgie            | 5         | 0.6%    |
| Hyprland          | 4         | 0.48%   |
| KDE4              | 3         | 0.36%   |
| Unity             | 2         | 0.24%   |
| LXDE              | 2         | 0.24%   |
| Yaru:ubuntu:GNOME | 1         | 0.12%   |
| xmonad            | 1         | 0.12%   |
| xinit-compat      | 1         | 0.12%   |
| i3-with-shmlog    | 1         | 0.12%   |
| Deepin            | 1         | 0.12%   |
| COSMIC            | 1         | 0.12%   |
| bspwm             | 1         | 0.12%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 537       | 64.7%   |
| Wayland | 236       | 28.43%  |
| Unknown | 44        | 5.3%    |
| Tty     | 13        | 1.57%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 358       | 42.52%  |
| GDM3    | 144       | 17.1%   |
| SDDM    | 124       | 14.73%  |
| GDM     | 97        | 11.52%  |
| LightDM | 95        | 11.28%  |
| TDM     | 17        | 2.02%   |
| KDM     | 3         | 0.36%   |
| XDM     | 1         | 0.12%   |
| SLiM    | 1         | 0.12%   |
| LY-DM   | 1         | 0.12%   |
| GREETD  | 1         | 0.12%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 441       | 53.52%  |
| nb_NO       | 198       | 24.03%  |
| Unknown     | 57        | 6.92%   |
| en_GB       | 48        | 5.83%   |
| C           | 19        | 2.31%   |
| nn_NO       | 15        | 1.82%   |
| pl_PL       | 10        | 1.21%   |
| en_DK       | 10        | 1.21%   |
| de_DE       | 5         | 0.61%   |
| sv_SE       | 2         | 0.24%   |
| ru_RU       | 2         | 0.24%   |
| it_IT       | 2         | 0.24%   |
| fi_FI       | 2         | 0.24%   |
| es_ES       | 2         | 0.24%   |
| en_IE       | 2         | 0.24%   |
| ru_UA       | 1         | 0.12%   |
| pt_PT       | 1         | 0.12%   |
| POSIX       | 1         | 0.12%   |
| fr_FR       | 1         | 0.12%   |
| en_US.utf-8 | 1         | 0.12%   |
| en_NZ       | 1         | 0.12%   |
| en_150      | 1         | 0.12%   |
| en_001      | 1         | 0.12%   |
| el_GR       | 1         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 438       | 53.61%  |
| BIOS | 379       | 46.39%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 564       | 68.03%  |
| Btrfs   | 118       | 14.23%  |
| Tmpfs   | 58        | 7%      |
| Overlay | 50        | 6.03%   |
| Xfs     | 17        | 2.05%   |
| Unknown | 12        | 1.45%   |
| Zfs     | 6         | 0.72%   |
| Ext3    | 2         | 0.24%   |
| Ext2    | 2         | 0.24%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 406       | 48.97%  |
| Unknown | 362       | 43.67%  |
| MBR     | 61        | 7.36%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 725       | 88.85%  |
| Yes       | 91        | 11.15%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 647       | 79.48%  |
| Yes       | 167       | 20.52%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 239       | 29.88%  |
| Hewlett-Packard      | 144       | 18%     |
| Dell                 | 122       | 15.25%  |
| ASUSTek Computer     | 83        | 10.38%  |
| Acer                 | 58        | 7.25%   |
| Apple                | 32        | 4%      |
| MSI                  | 26        | 3.25%   |
| Samsung Electronics  | 18        | 2.25%   |
| HUAWEI               | 16        | 2%      |
| Notebook             | 10        | 1.25%   |
| Toshiba              | 9         | 1.13%   |
| Packard Bell         | 6         | 0.75%   |
| Google               | 6         | 0.75%   |
| Clevo                | 5         | 0.63%   |
| Unknown              | 5         | 0.63%   |
| TUXEDO               | 3         | 0.38%   |
| Panasonic            | 2         | 0.25%   |
| Teclast              | 1         | 0.13%   |
| Star Labs            | 1         | 0.13%   |
| Sony                 | 1         | 0.13%   |
| Razer                | 1         | 0.13%   |
| Nokia                | 1         | 0.13%   |
| LG Electronics       | 1         | 0.13%   |
| LAMINA               | 1         | 0.13%   |
| Intel Client Systems | 1         | 0.13%   |
| Intel                | 1         | 0.13%   |
| IGEL Technology      | 1         | 0.13%   |
| GMKtec               | 1         | 0.13%   |
| Getac                | 1         | 0.13%   |
| eMachines            | 1         | 0.13%   |
| Chuwi                | 1         | 0.13%   |
| Cepter               | 1         | 0.13%   |
| Alienware            | 1         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| HP EliteBook 840 G6                        | 7         | 0.88%   |
| Apple MacBookPro12,1                       | 7         | 0.88%   |
| Unknown                                    | 7         | 0.88%   |
| HUAWEI MACH-WX9                            | 6         | 0.75%   |
| Dell Precision 5530                        | 6         | 0.75%   |
| Dell XPS 15 9570                           | 5         | 0.63%   |
| Lenovo Yoga Slim 7 14ARE05 82A2            | 4         | 0.5%    |
| HUAWEI WRT-WX9                             | 4         | 0.5%    |
| HP ProBook 430 G2                          | 4         | 0.5%    |
| Dell XPS 15 9520                           | 4         | 0.5%    |
| Dell XPS 13 9380                           | 4         | 0.5%    |
| Dell Latitude E7240                        | 4         | 0.5%    |
| Samsung 950XCJ/951XCJ/950XCR               | 3         | 0.38%   |
| Lenovo Yoga Slim 7 Pro 14IAH7 82UT         | 3         | 0.38%   |
| Lenovo Yoga Slim 7 Carbon 14ACN6 82L0      | 3         | 0.38%   |
| HP ProBook 450 G2                          | 3         | 0.38%   |
| HP ProBook 440 G5                          | 3         | 0.38%   |
| HP Pavilion Notebook                       | 3         | 0.38%   |
| HP OMEN by Laptop                          | 3         | 0.38%   |
| HP EliteBook 8470p                         | 3         | 0.38%   |
| HP EliteBook 840 G5                        | 3         | 0.38%   |
| HP EliteBook 830 G6                        | 3         | 0.38%   |
| Dell XPS 15 9500                           | 3         | 0.38%   |
| Dell XPS 15 7590                           | 3         | 0.38%   |
| Dell Latitude E5470                        | 3         | 0.38%   |
| Dell Latitude 7480                         | 3         | 0.38%   |
| Dell Latitude 5480                         | 3         | 0.38%   |
| ASUS VivoBook_ASUSLaptop K3604ZA_K3604ZA   | 3         | 0.38%   |
| ASUS VivoBook_ASUSLaptop K3402ZA_K3402ZA   | 3         | 0.38%   |
| ASUS VivoBook_ASUSLaptop E410MAB_E410MA    | 3         | 0.38%   |
| Apple MacBookPro9,2                        | 3         | 0.38%   |
| Acer Aspire V3-571G                        | 3         | 0.38%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 2         | 0.25%   |
| MSI Katana GF76 11SC                       | 2         | 0.25%   |
| MSI GF63 Thin 11UD                         | 2         | 0.25%   |
| Lenovo Z50-70 20354                        | 2         | 0.25%   |
| Lenovo Yoga Pro 7 14AHP9 83E3              | 2         | 0.25%   |
| Lenovo Y520-15IKBN 80WK                    | 2         | 0.25%   |
| Lenovo ThinkPad X230 23252EG               | 2         | 0.25%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW | 2         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 163       | 20.38%  |
| Dell Latitude         | 57        | 7.13%   |
| HP EliteBook          | 52        | 6.5%    |
| Acer Aspire           | 37        | 4.63%   |
| HP ProBook            | 33        | 4.13%   |
| Dell XPS              | 31        | 3.88%   |
| Lenovo IdeaPad        | 25        | 3.13%   |
| Dell Precision        | 24        | 3%      |
| ASUS Vivobook         | 20        | 2.5%    |
| Lenovo Yoga           | 18        | 2.25%   |
| HP Pavilion           | 16        | 2%      |
| HP ZBook              | 12        | 1.5%    |
| Acer Swift            | 11        | 1.38%   |
| Lenovo Legion         | 8         | 1%      |
| HP Laptop             | 8         | 1%      |
| Toshiba Satellite     | 7         | 0.88%   |
| Dell Inspiron         | 7         | 0.88%   |
| ASUS Zenbook          | 7         | 0.88%   |
| Apple MacBookPro12    | 7         | 0.88%   |
| Unknown               | 7         | 0.88%   |
| HUAWEI MACH-WX9       | 6         | 0.75%   |
| HP OMEN               | 6         | 0.75%   |
| Apple MacBookPro11    | 6         | 0.75%   |
| Packard Bell EasyNote | 5         | 0.63%   |
| Lenovo ThinkBook      | 5         | 0.63%   |
| ASUS ROG              | 5         | 0.63%   |
| Acer Nitro            | 5         | 0.63%   |
| MSI Katana            | 4         | 0.5%    |
| HUAWEI WRT-WX9        | 4         | 0.5%    |
| Samsung 950XCJ        | 3         | 0.38%   |
| HP Presario           | 3         | 0.38%   |
| HP Compaq             | 3         | 0.38%   |
| ASUS TUF              | 3         | 0.38%   |
| Apple MacBookPro9     | 3         | 0.38%   |
| Apple MacBookPro8     | 3         | 0.38%   |
| Samsung 300V3A        | 2         | 0.25%   |
| MSI GS66              | 2         | 0.25%   |
| MSI GS65              | 2         | 0.25%   |
| MSI GL62              | 2         | 0.25%   |
| MSI GF63              | 2         | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2018    | 77        | 9.63%   |
| 2020    | 69        | 8.63%   |
| 2019    | 68        | 8.5%    |
| 2012    | 59        | 7.38%   |
| 2021    | 58        | 7.25%   |
| 2017    | 56        | 7%      |
| 2013    | 53        | 6.63%   |
| 2016    | 51        | 6.38%   |
| 2011    | 51        | 6.38%   |
| 2014    | 46        | 5.75%   |
| 2015    | 45        | 5.63%   |
| 2022    | 42        | 5.25%   |
| 2023    | 33        | 4.13%   |
| 2010    | 29        | 3.63%   |
| 2024    | 16        | 2%      |
| 2009    | 16        | 2%      |
| 2008    | 16        | 2%      |
| 2007    | 12        | 1.5%    |
| 2006    | 1         | 0.13%   |
| 2005    | 1         | 0.13%   |
| Unknown | 1         | 0.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 800       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 717       | 88.96%  |
| Enabled  | 89        | 11.04%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 792       | 99%     |
| Yes  | 8         | 1%      |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 234       | 28.75%  |
| 16.01-24.0  | 185       | 22.73%  |
| 8.01-16.0   | 148       | 18.18%  |
| 3.01-4.0    | 103       | 12.65%  |
| 32.01-64.0  | 95        | 11.67%  |
| 1.01-2.0    | 15        | 1.84%   |
| 24.01-32.0  | 14        | 1.72%   |
| 64.01-256.0 | 13        | 1.6%    |
| 2.01-3.0    | 3         | 0.37%   |
| 0.51-1.0    | 3         | 0.37%   |
| 0.01-0.5    | 1         | 0.12%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 236       | 26.08%  |
| 2.01-3.0   | 227       | 25.08%  |
| 4.01-8.0   | 191       | 21.1%   |
| 3.01-4.0   | 147       | 16.24%  |
| 8.01-16.0  | 54        | 5.97%   |
| 0.51-1.0   | 32        | 3.54%   |
| 0.01-0.5   | 10        | 1.1%    |
| 16.01-24.0 | 5         | 0.55%   |
| 24.01-32.0 | 3         | 0.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 650       | 79.08%  |
| 2      | 140       | 17.03%  |
| 3      | 21        | 2.55%   |
| 0      | 7         | 0.85%   |
| 4      | 2         | 0.24%   |
| 6      | 1         | 0.12%   |
| 5      | 1         | 0.12%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 619       | 77.09%  |
| Yes       | 184       | 22.91%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 622       | 77.27%  |
| No        | 183       | 22.73%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 784       | 98%     |
| No        | 16        | 2%      |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 677       | 83.37%  |
| No        | 135       | 16.63%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Norway  | 800       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Oslo                 | 268       | 31.31%  |
| Trondheim            | 49        | 5.72%   |
| Bergen               | 39        | 4.56%   |
| Stavanger            | 23        | 2.69%   |
| Kristiansand         | 21        | 2.45%   |
| Tromsø              | 14        | 1.64%   |
| Skien                | 11        | 1.29%   |
| Drammen              | 11        | 1.29%   |
| Ålesund             | 10        | 1.17%   |
| Moss                 | 9         | 1.05%   |
| Røyken Municipality | 8         | 0.93%   |
| Haugesund            | 8         | 0.93%   |
| Fornebu              | 8         | 0.93%   |
| Bodø                | 8         | 0.93%   |
| Fredrikstad          | 7         | 0.82%   |
| Sarpsborg            | 6         | 0.7%    |
| Sandnes              | 6         | 0.7%    |
| Lillehammer          | 6         | 0.7%    |
| Hamar                | 6         | 0.7%    |
| Asker                | 6         | 0.7%    |
| Arendal              | 6         | 0.7%    |
| Tønsberg            | 5         | 0.58%   |
| Ski                  | 5         | 0.58%   |
| Melhus               | 5         | 0.58%   |
| Drobak               | 5         | 0.58%   |
| Porsgrunn            | 4         | 0.47%   |
| Nesttun              | 4         | 0.47%   |
| Mo i Rana            | 4         | 0.47%   |
| Kristiansund         | 4         | 0.47%   |
| Jessheim             | 4         | 0.47%   |
| Algard               | 4         | 0.47%   |
| Verdal               | 3         | 0.35%   |
| Vear                 | 3         | 0.35%   |
| Sandefjord           | 3         | 0.35%   |
| Rong                 | 3         | 0.35%   |
| Notodden             | 3         | 0.35%   |
| Nesodden             | 3         | 0.35%   |
| Mjondalen            | 3         | 0.35%   |
| Lysaker              | 3         | 0.35%   |
| Lyngdal              | 3         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 224       | 315    | 23.14%  |
| SanDisk                        | 86        | 112    | 8.88%   |
| Toshiba                        | 70        | 85     | 7.23%   |
| WDC                            | 63        | 77     | 6.51%   |
| SK hynix                       | 60        | 80     | 6.2%    |
| Seagate                        | 55        | 66     | 5.68%   |
| Kingston                       | 54        | 79     | 5.58%   |
| Unknown                        | 47        | 57     | 4.86%   |
| Micron Technology              | 44        | 60     | 4.55%   |
| Intel                          | 36        | 41     | 3.72%   |
| Hitachi                        | 28        | 40     | 2.89%   |
| Crucial                        | 21        | 23     | 2.17%   |
| Apple                          | 21        | 24     | 2.17%   |
| HGST                           | 18        | 20     | 1.86%   |
| KIOXIA                         | 14        | 22     | 1.45%   |
| PNY                            | 13        | 18     | 1.34%   |
| LITEON                         | 13        | 17     | 1.34%   |
| LITEONIT                       | 7         | 16     | 0.72%   |
| Lenovo                         | 6         | 6      | 0.62%   |
| Kingston Technology Company    | 6         | 6      | 0.62%   |
| A-DATA Technology              | 5         | 8      | 0.52%   |
| Verbatim                       | 4         | 4      | 0.41%   |
| Phison                         | 4         | 6      | 0.41%   |
| JMicron Technology             | 4         | 5      | 0.41%   |
| Fujitsu                        | 4         | 4      | 0.41%   |
| Corsair                        | 4         | 5      | 0.41%   |
| China                          | 4         | 4      | 0.41%   |
| Union Memory                   | 3         | 3      | 0.31%   |
| Transcend                      | 3         | 3      | 0.31%   |
| OCZ                            | 3         | 3      | 0.31%   |
| Intenso                        | 3         | 8      | 0.31%   |
| Unknown                        | 3         | 3      | 0.31%   |
| XPG                            | 2         | 2      | 0.21%   |
| UMIS                           | 2         | 2      | 0.21%   |
| Solid State Storage Technology | 2         | 2      | 0.21%   |
| Realtek Semiconductor          | 2         | 3      | 0.21%   |
| Phison Electronics             | 2         | 2      | 0.21%   |
| Netac                          | 2         | 2      | 0.21%   |
| Lexar                          | 2         | 2      | 0.21%   |
| ASMT                           | 2         | 3      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 14        | 1.38%   |
| Samsung NVMe SSD Drive 256GB                         | 13        | 1.28%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 12        | 1.18%   |
| PNY ELITE PSSD 960GB                                 | 10        | 0.99%   |
| HGST HTS721010A9E630 1TB                             | 9         | 0.89%   |
| Unknown MMC Card  64GB                               | 7         | 0.69%   |
| Apple SSD SM0128G 121GB                              | 7         | 0.69%   |
| Toshiba NVMe SSD Drive 256GB                         | 6         | 0.59%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                 | 6         | 0.59%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB  | 6         | 0.59%   |
| Kingston SV300S37A120G 120GB SSD                     | 6         | 0.59%   |
| Toshiba XG6 NVMe SSD Controller 1024GB               | 5         | 0.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 5         | 0.49%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 256GB      | 5         | 0.49%   |
| SanDisk NVMe SSD Drive 512GB                         | 5         | 0.49%   |
| SanDisk NVMe SSD Drive 256GB                         | 5         | 0.49%   |
| Samsung NVMe SSD Drive 1024GB                        | 5         | 0.49%   |
| Micron 2450_MTFDKBA512TFK 512GB                      | 5         | 0.49%   |
| Kingston SA400S37240G 240GB SSD                      | 5         | 0.49%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB                 | 4         | 0.39%   |
| Unknown NVMe SSD Drive 512GB                         | 4         | 0.39%   |
| Unknown MMC Card  16GB                               | 4         | 0.39%   |
| Toshiba NVMe SSD Drive 512GB                         | 4         | 0.39%   |
| SK hynix SKHynix_HFS512GDE9X084N 512GB               | 4         | 0.39%   |
| SK hynix NVMe SSD Drive 512GB                        | 4         | 0.39%   |
| SK hynix HFS128G39TND-N210A 128GB SSD                | 4         | 0.39%   |
| Seagate ST9500325AS 500GB                            | 4         | 0.39%   |
| Seagate Expansion 1TB                                | 4         | 0.39%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB     | 4         | 0.39%   |
| SanDisk SD8SN8U-128G-1006 128GB SSD                  | 4         | 0.39%   |
| SanDisk NVMe SSD Drive 500GB                         | 4         | 0.39%   |
| SanDisk NVMe SSD Drive 1TB                           | 4         | 0.39%   |
| Samsung SSD 850 EVO 500GB                            | 4         | 0.39%   |
| Samsung SSD 850 EVO 250GB                            | 4         | 0.39%   |
| Samsung NVMe SSD Drive 500GB                         | 4         | 0.39%   |
| Micron MTFDKBA512TFH 512GB                           | 4         | 0.39%   |
| Kingston Company SNV2S1000G 1TB                      | 4         | 0.39%   |
| Kingston SFYRD2000G 2TB                              | 4         | 0.39%   |
| Kingston OM8PCP3512F-AI1 512GB                       | 4         | 0.39%   |
| Intel NVMe SSD Drive 512GB                           | 4         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 54        | 65     | 32.73%  |
| WDC                 | 29        | 41     | 17.58%  |
| Hitachi             | 28        | 40     | 16.97%  |
| Toshiba             | 21        | 25     | 12.73%  |
| HGST                | 18        | 20     | 10.91%  |
| Fujitsu             | 4         | 4      | 2.42%   |
| Intenso             | 3         | 8      | 1.82%   |
| JMicron Technology  | 2         | 3      | 1.21%   |
| Unknown             | 1         | 1      | 0.61%   |
| STEC                | 1         | 1      | 0.61%   |
| Samsung Electronics | 1         | 3      | 0.61%   |
| LaCie               | 1         | 1      | 0.61%   |
| ASMT                | 1         | 1      | 0.61%   |
| Apple               | 1         | 1      | 0.61%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 101       | 128    | 29.45%  |
| SanDisk             | 39        | 48     | 11.37%  |
| Kingston            | 35        | 46     | 10.2%   |
| Intel               | 19        | 21     | 5.54%   |
| Crucial             | 18        | 20     | 5.25%   |
| Apple               | 18        | 21     | 5.25%   |
| PNY                 | 13        | 18     | 3.79%   |
| Micron Technology   | 13        | 17     | 3.79%   |
| SK hynix            | 12        | 14     | 3.5%    |
| Toshiba             | 11        | 14     | 3.21%   |
| LITEON              | 11        | 15     | 3.21%   |
| WDC                 | 9         | 11     | 2.62%   |
| LITEONIT            | 7         | 16     | 2.04%   |
| Verbatim            | 4         | 4      | 1.17%   |
| Corsair             | 4         | 5      | 1.17%   |
| China               | 4         | 4      | 1.17%   |
| A-DATA Technology   | 4         | 7      | 1.17%   |
| Transcend           | 3         | 3      | 0.87%   |
| OCZ                 | 3         | 3      | 0.87%   |
| Netac               | 2         | 2      | 0.58%   |
| Unknown             | 2         | 2      | 0.58%   |
| Teclast             | 1         | 1      | 0.29%   |
| Seagate             | 1         | 1      | 0.29%   |
| PNY CS90            | 1         | 1      | 0.29%   |
| Phison              | 1         | 2      | 0.29%   |
| Patriot             | 1         | 1      | 0.29%   |
| OWC                 | 1         | 1      | 0.29%   |
| KingSpec            | 1         | 1      | 0.29%   |
| Hewlett-Packard     | 1         | 1      | 0.29%   |
| GOODRAM             | 1         | 1      | 0.29%   |
| BIWIN               | 1         | 1      | 0.29%   |
| ASMT                | 1         | 2      | 0.29%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 379       | 551    | 41.88%  |
| SSD     | 312       | 432    | 34.48%  |
| HDD     | 162       | 214    | 17.9%   |
| MMC     | 44        | 54     | 4.86%   |
| Unknown | 8         | 9      | 0.88%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 415       | 587    | 46.89%  |
| NVMe | 379       | 544    | 42.82%  |
| SAS  | 47        | 75     | 5.31%   |
| MMC  | 44        | 54     | 4.97%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 347       | 481    | 72.29%  |
| 0.51-1.0   | 115       | 143    | 23.96%  |
| 1.01-2.0   | 10        | 12     | 2.08%   |
| 3.01-4.0   | 4         | 5      | 0.83%   |
| 10.01-20.0 | 2         | 2      | 0.42%   |
| 2.01-3.0   | 1         | 2      | 0.21%   |
| 4.01-10.0  | 1         | 1      | 0.21%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 270       | 31.69%  |
| 251-500        | 210       | 24.65%  |
| 501-1000       | 127       | 14.91%  |
| 1-20           | 70        | 8.22%   |
| 1001-2000      | 62        | 7.28%   |
| 51-100         | 32        | 3.76%   |
| Unknown        | 23        | 2.7%    |
| More than 3000 | 21        | 2.46%   |
| 21-50          | 21        | 2.46%   |
| 2001-3000      | 16        | 1.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 339       | 37.58%  |
| 21-50          | 160       | 17.74%  |
| 101-250        | 127       | 14.08%  |
| 51-100         | 121       | 13.41%  |
| 251-500        | 74        | 8.2%    |
| 501-1000       | 29        | 3.22%   |
| Unknown        | 23        | 2.55%   |
| 1001-2000      | 19        | 2.11%   |
| More than 3000 | 9         | 1%      |
| 0              | 1         | 0.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD7500BPVX-22JC3T0 752GB                        | 2         | 2      | 5.88%   |
| SK hynix HFS128G39TND-N210A 128GB SSD               | 2         | 2      | 5.88%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 1      | 2.94%   |
| Toshiba MK5055GSX 500GB                             | 1         | 3      | 2.94%   |
| SK hynix SH920 2.5 7MM 128GB SSD                    | 1         | 1      | 2.94%   |
| SK hynix SC210 2.5 7MM 256GB SSD                    | 1         | 1      | 2.94%   |
| SK hynix HFS256G39TND-N210A 256GB SSD               | 1         | 1      | 2.94%   |
| Seagate ST9750420AS 752GB                           | 1         | 1      | 2.94%   |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 1      | 2.94%   |
| Seagate ST500LM000-SSHD-8GB                         | 1         | 1      | 2.94%   |
| Seagate ST1000LM014-SSHD-8GB                        | 1         | 1      | 2.94%   |
| SanDisk SSD i100 24GB                               | 1         | 1      | 2.94%   |
| SanDisk SD8TN8U-256G-1006 256GB SSD                 | 1         | 1      | 2.94%   |
| Samsung Electronics SSD SM841 2.5 7mm 256GB         | 1         | 1      | 2.94%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 4      | 2.94%   |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD      | 1         | 1      | 2.94%   |
| Micron Technology 1100_MTFDDAK512TBN 512GB SSD      | 1         | 1      | 2.94%   |
| Lenovo LENSE20256GMSP34MEAT2TA 256GB                | 1         | 1      | 2.94%   |
| Kingston SA400S37960G 960GB SSD                     | 1         | 1      | 2.94%   |
| Kingston SA2000M81000G 1TB                          | 1         | 2      | 2.94%   |
| Intel SSDSA1M080G2LE 80GB                           | 1         | 1      | 2.94%   |
| Intel SSDPEKNW512G8H 512GB                          | 1         | 2      | 2.94%   |
| Hitachi HTS725032A9A364 320GB                       | 1         | 1      | 2.94%   |
| Hitachi HTS725025A9A364 250GB                       | 1         | 2      | 2.94%   |
| Hitachi HTS723232A7A364 320GB                       | 1         | 1      | 2.94%   |
| Hitachi HTS547564A9E384 640GB                       | 1         | 1      | 2.94%   |
| HGST HTS725050A7E630 500GB                          | 1         | 1      | 2.94%   |
| HGST HTS545050A7E680 500GB                          | 1         | 1      | 2.94%   |
| Crucial CT256M550SSD1 256GB                         | 1         | 1      | 2.94%   |
| Corsair Performance Pro 128GB SSD                   | 1         | 1      | 2.94%   |
| Corsair Force GS 240GB SSD                          | 1         | 2      | 2.94%   |
| Apple SSD SM0256F 256GB                             | 1         | 1      | 2.94%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SK hynix            | 5         | 5      | 14.71%  |
| Seagate             | 4         | 4      | 11.76%  |
| Hitachi             | 4         | 5      | 11.76%  |
| WDC                 | 3         | 3      | 8.82%   |
| Micron Technology   | 3         | 6      | 8.82%   |
| SanDisk             | 2         | 2      | 5.88%   |
| Kingston            | 2         | 3      | 5.88%   |
| Intel               | 2         | 3      | 5.88%   |
| HGST                | 2         | 2      | 5.88%   |
| Corsair             | 2         | 3      | 5.88%   |
| Toshiba             | 1         | 3      | 2.94%   |
| Samsung Electronics | 1         | 1      | 2.94%   |
| Lenovo              | 1         | 1      | 2.94%   |
| Crucial             | 1         | 1      | 2.94%   |
| Apple               | 1         | 1      | 2.94%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 28.57%  |
| Hitachi | 4         | 5      | 28.57%  |
| WDC     | 3         | 3      | 21.43%  |
| HGST    | 2         | 2      | 14.29%  |
| Toshiba | 1         | 3      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 17        | 21     | 50%     |
| HDD  | 14        | 17     | 41.18%  |
| NVMe | 3         | 5      | 8.82%   |

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
| Detected | 483       | 747    | 56.29%  |
| Works    | 341       | 470    | 39.74%  |
| Malfunc  | 34        | 43     | 3.96%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 499       | 51.71%  |
| Samsung Electronics                     | 138       | 14.3%   |
| SanDisk                                 | 69        | 7.15%   |
| AMD                                     | 61        | 6.32%   |
| SK hynix                                | 47        | 4.87%   |
| Toshiba America Info Systems            | 39        | 4.04%   |
| Micron Technology                       | 31        | 3.21%   |
| Kingston Technology Company             | 25        | 2.59%   |
| KIOXIA                                  | 12        | 1.24%   |
| Lenovo                                  | 6         | 0.62%   |
| Union Memory (Shenzhen)                 | 5         | 0.52%   |
| Solidigm                                | 5         | 0.52%   |
| Phison Electronics                      | 4         | 0.41%   |
| Micron/Crucial Technology               | 4         | 0.41%   |
| Lite-On Technology                      | 3         | 0.31%   |
| Solid State Storage Technology          | 2         | 0.21%   |
| Realtek Semiconductor                   | 2         | 0.21%   |
| Nvidia                                  | 2         | 0.21%   |
| Marvell Technology Group                | 2         | 0.21%   |
| Apple                                   | 2         | 0.21%   |
| ADATA Technology                        | 2         | 0.21%   |
| Silicon Motion                          | 1         | 0.1%    |
| Shenzhen Unionmemory Information System | 1         | 0.1%    |
| MAXIO Technology (Hangzhou)             | 1         | 0.1%    |
| Biwin Storage Technology                | 1         | 0.1%    |
| ASMedia Technology                      | 1         | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 63        | 6.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 57        | 5.63%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 49        | 4.84%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 48        | 4.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 45        | 4.44%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 41        | 4.05%   |
| Intel Volume Management Device NVMe RAID Controller                            | 37        | 3.65%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 32        | 3.16%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 29        | 2.86%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 24        | 2.37%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 23        | 2.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 23        | 2.27%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 21        | 2.07%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 21        | 2.07%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 21        | 2.07%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 17        | 1.68%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 16        | 1.58%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 16        | 1.58%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 15        | 1.48%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 14        | 1.38%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 13        | 1.28%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 11        | 1.09%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 10        | 0.99%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 10        | 0.99%   |
| Intel SSD 660P Series                                                          | 10        | 0.99%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 9         | 0.89%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 9         | 0.89%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 9         | 0.89%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 9         | 0.89%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 8         | 0.79%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 8         | 0.79%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 8         | 0.79%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 8         | 0.79%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 7         | 0.69%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 7         | 0.69%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 7         | 0.69%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 7         | 0.69%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 6         | 0.59%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 6         | 0.59%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 6         | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 473       | 48.91%  |
| NVMe | 378       | 39.09%  |
| RAID | 87        | 9%      |
| IDE  | 29        | 3%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 676       | 84.5%   |
| AMD    | 123       | 15.38%  |
| ARM    | 1         | 0.13%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz       | 21        | 2.63%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 16        | 2%      |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 16        | 2%      |
| Intel Core i5-7200U CPU @ 2.50GHz       | 15        | 1.88%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 13        | 1.63%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 13        | 1.63%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 12        | 1.5%    |
| Intel Core i7-8750H CPU @ 2.20GHz       | 11        | 1.38%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 11        | 1.38%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 11        | 1.38%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 10        | 1.25%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 9         | 1.13%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 9         | 1.13%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 9         | 1.13%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 8         | 1%      |
| Intel Core i7-3520M CPU @ 2.90GHz       | 8         | 1%      |
| Intel Core i5-5200U CPU @ 2.20GHz       | 8         | 1%      |
| Intel Core i7-5600U CPU @ 2.60GHz       | 7         | 0.88%   |
| Intel Core i5-5257U CPU @ 2.70GHz       | 7         | 0.88%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 7         | 0.88%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 7         | 0.88%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 7         | 0.88%   |
| Intel 12th Gen Core i5-12500H           | 7         | 0.88%   |
| AMD Ryzen 5 4500U with Radeon Graphics  | 7         | 0.88%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 6         | 0.75%   |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 6         | 0.75%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 6         | 0.75%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 6         | 0.75%   |
| Intel Core i3-4030U CPU @ 1.90GHz       | 6         | 0.75%   |
| Intel 12th Gen Core i7-1260P            | 6         | 0.75%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz | 6         | 0.75%   |
| AMD Ryzen 7 4700U with Radeon Graphics  | 6         | 0.75%   |
| AMD Ryzen 5 7520U with Radeon Graphics  | 6         | 0.75%   |
| Intel Core i9-8950HK CPU @ 2.90GHz      | 5         | 0.63%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 5         | 0.63%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz      | 5         | 0.63%   |
| Intel Core i7-3610QM CPU @ 2.30GHz      | 5         | 0.63%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 5         | 0.63%   |
| Intel Core i5-9300H CPU @ 2.40GHz       | 5         | 0.63%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz      | 5         | 0.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 223       | 27.88%  |
| Intel Core i5           | 212       | 26.5%   |
| Other                   | 105       | 13.13%  |
| Intel Core i3           | 40        | 5%      |
| AMD Ryzen 7             | 32        | 4%      |
| AMD Ryzen 5             | 29        | 3.63%   |
| Intel Celeron           | 27        | 3.38%   |
| Intel Pentium           | 15        | 1.88%   |
| Intel Core 2 Duo        | 15        | 1.88%   |
| Intel Core i9           | 9         | 1.13%   |
| AMD Ryzen 3             | 8         | 1%      |
| Intel Core              | 7         | 0.88%   |
| AMD Ryzen 7 PRO         | 7         | 0.88%   |
| Intel Atom              | 6         | 0.75%   |
| AMD A8                  | 6         | 0.75%   |
| Intel Genuine           | 5         | 0.63%   |
| AMD Ryzen 9             | 5         | 0.63%   |
| AMD A6                  | 5         | 0.63%   |
| Intel Core 2            | 4         | 0.5%    |
| AMD Ryzen 5 PRO         | 4         | 0.5%    |
| Intel Pentium Dual-Core | 3         | 0.38%   |
| AMD E2                  | 3         | 0.38%   |
| AMD E1                  | 3         | 0.38%   |
| AMD E                   | 3         | 0.38%   |
| AMD A10                 | 3         | 0.38%   |
| AMD Turion 64 X2 Mobile | 2         | 0.25%   |
| AMD Phenom II           | 2         | 0.25%   |
| AMD Athlon II           | 2         | 0.25%   |
| Intel Xeon              | 1         | 0.13%   |
| Intel Pentium Silver    | 1         | 0.13%   |
| Intel Pentium Gold      | 1         | 0.13%   |
| Intel Core m7           | 1         | 0.13%   |
| Intel Core M            | 1         | 0.13%   |
| Intel Core 2 Solo       | 1         | 0.13%   |
| Intel Celeron Dual-Core | 1         | 0.13%   |
| AMD V160                | 1         | 0.13%   |
| AMD V120                | 1         | 0.13%   |
| AMD Ryzen Embedded      | 1         | 0.13%   |
| AMD Ryzen 3 PRO         | 1         | 0.13%   |
| AMD Athlon II Dual-Core | 1         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 338       | 42.14%  |
| 4      | 264       | 32.92%  |
| 6      | 71        | 8.85%   |
| 8      | 54        | 6.73%   |
| 12     | 20        | 2.49%   |
| 10     | 19        | 2.37%   |
| 14     | 17        | 2.12%   |
| 1      | 12        | 1.5%    |
| 16     | 5         | 0.62%   |
| 24     | 1         | 0.12%   |
| 3      | 1         | 0.12%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 800       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 664       | 82.38%  |
| 1      | 140       | 17.37%  |
| 8      | 2         | 0.25%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 787       | 98.25%  |
| Unknown        | 9         | 1.12%   |
| 32-bit         | 5         | 0.62%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 384       | 45.77%  |
| 0x206a7    | 30        | 3.58%   |
| 0x906ea    | 27        | 3.22%   |
| 0x306a9    | 27        | 3.22%   |
| 0x806ea    | 25        | 2.98%   |
| 0x40651    | 25        | 2.98%   |
| 0x406e3    | 24        | 2.86%   |
| 0x806ec    | 20        | 2.38%   |
| 0x306d4    | 20        | 2.38%   |
| 0x806e9    | 17        | 2.03%   |
| 0x806c1    | 14        | 1.67%   |
| 0x306c3    | 13        | 1.55%   |
| 0x20655    | 13        | 1.55%   |
| 0x506e3    | 12        | 1.43%   |
| 0xa0652    | 11        | 1.31%   |
| 0x1067a    | 11        | 1.31%   |
| 0x08600106 | 11        | 1.31%   |
| 0x906a3    | 10        | 1.19%   |
| 0x906e9    | 9         | 1.07%   |
| 0x806eb    | 8         | 0.95%   |
| 0x806d1    | 8         | 0.95%   |
| 0x0a50000c | 6         | 0.72%   |
| 0x010000c8 | 6         | 0.72%   |
| 0x20652    | 5         | 0.6%    |
| 0x08600103 | 5         | 0.6%    |
| 0x08108109 | 5         | 0.6%    |
| 0x906ed    | 4         | 0.48%   |
| 0x506c9    | 4         | 0.48%   |
| 0x08108102 | 4         | 0.48%   |
| 0x05000119 | 4         | 0.48%   |
| 0x906a4    | 3         | 0.36%   |
| 0x706a1    | 3         | 0.36%   |
| 0x6fd      | 3         | 0.36%   |
| 0x406c4    | 3         | 0.36%   |
| 0x0a404102 | 3         | 0.36%   |
| 0x08608103 | 3         | 0.36%   |
| 0x08600104 | 3         | 0.36%   |
| 0xb06a3    | 2         | 0.24%   |
| 0x906c0    | 2         | 0.24%   |
| 0x706e5    | 2         | 0.24%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 185       | 23.04%  |
| Haswell           | 71        | 8.84%   |
| Skylake           | 62        | 7.72%   |
| IvyBridge         | 56        | 6.97%   |
| SandyBridge       | 52        | 6.48%   |
| Unknown           | 49        | 6.1%    |
| Alderlake Hybrid  | 40        | 4.98%   |
| Broadwell         | 35        | 4.36%   |
| TigerLake         | 34        | 4.23%   |
| Zen 2             | 29        | 3.61%   |
| Westmere          | 23        | 2.86%   |
| Penryn            | 17        | 2.12%   |
| IceLake           | 17        | 2.12%   |
| Zen 3             | 16        | 1.99%   |
| CometLake         | 13        | 1.62%   |
| Zen+              | 12        | 1.49%   |
| Silvermont        | 11        | 1.37%   |
| Core              | 9         | 1.12%   |
| Goldmont plus     | 8         | 1%      |
| Meteorlake Hybrid | 7         | 0.87%   |
| K10               | 7         | 0.87%   |
| Piledriver        | 5         | 0.62%   |
| Goldmont          | 5         | 0.62%   |
| Excavator         | 5         | 0.62%   |
| Bobcat            | 5         | 0.62%   |
| Zen               | 4         | 0.5%    |
| Bonnell           | 4         | 0.5%    |
| Tremont           | 3         | 0.37%   |
| Puma              | 3         | 0.37%   |
| P6                | 3         | 0.37%   |
| Nehalem           | 3         | 0.37%   |
| K8 Hammer         | 3         | 0.37%   |
| K10 Llano         | 3         | 0.37%   |
| Steamroller       | 2         | 0.25%   |
| Jaguar            | 2         | 0.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 619       | 60.63%  |
| Nvidia | 246       | 24.09%  |
| AMD    | 156       | 15.28%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 50        | 4.81%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 46        | 4.42%   |
| Intel UHD Graphics 620                                                                   | 44        | 4.23%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 39        | 3.75%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 38        | 3.65%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 37        | 3.56%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 33        | 3.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 31        | 2.98%   |
| Intel HD Graphics 620                                                                    | 31        | 2.98%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 29        | 2.79%   |
| Intel HD Graphics 5500                                                                   | 25        | 2.4%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 25        | 2.4%    |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 21        | 2.02%   |
| Intel HD Graphics 530                                                                    | 17        | 1.63%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 15        | 1.44%   |
| Intel Core Processor Integrated Graphics Controller                                      | 15        | 1.44%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 14        | 1.35%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 14        | 1.35%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 13        | 1.25%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 12        | 1.15%   |
| Nvidia GP108M [GeForce MX150]                                                            | 11        | 1.06%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 11        | 1.06%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 11        | 1.06%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 10        | 0.96%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 9         | 0.87%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 9         | 0.87%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 9         | 0.87%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 8         | 0.77%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 8         | 0.77%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 8         | 0.77%   |
| Intel HD Graphics 630                                                                    | 8         | 0.77%   |
| AMD Mendocino                                                                            | 8         | 0.77%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 7         | 0.67%   |
| Intel Iris Graphics 6100                                                                 | 7         | 0.67%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 0.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 0.67%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 6         | 0.58%   |
| AMD Lucienne                                                                             | 6         | 0.58%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 5         | 0.48%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 5         | 0.48%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 412       | 51.37%  |
| Intel + Nvidia | 185       | 23.07%  |
| 1 x AMD        | 108       | 13.47%  |
| 1 x Nvidia     | 45        | 5.61%   |
| Intel + AMD    | 21        | 2.62%   |
| AMD + Nvidia   | 16        | 2%      |
| 2 x AMD        | 12        | 1.5%    |
| 2 x Intel      | 2         | 0.25%   |
| Other          | 1         | 0.12%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 642       | 78.77%  |
| Proprietary | 138       | 16.93%  |
| Unknown     | 35        | 4.29%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 591       | 72.43%  |
| 1.01-2.0   | 68        | 8.33%   |
| 0.01-0.5   | 67        | 8.21%   |
| 3.01-4.0   | 38        | 4.66%   |
| 0.51-1.0   | 28        | 3.43%   |
| 5.01-6.0   | 14        | 1.72%   |
| 7.01-8.0   | 7         | 0.86%   |
| 2.01-3.0   | 2         | 0.25%   |
| 16.01-24.0 | 1         | 0.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 165       | 17.19%  |
| LG Display              | 133       | 13.85%  |
| Chimei Innolux          | 122       | 12.71%  |
| Samsung Electronics     | 112       | 11.67%  |
| BOE                     | 96        | 10%     |
| Sharp                   | 42        | 4.38%   |
| Dell                    | 36        | 3.75%   |
| Apple                   | 29        | 3.02%   |
| Lenovo                  | 27        | 2.81%   |
| InfoVision              | 21        | 2.19%   |
| Chi Mei Optoelectronics | 17        | 1.77%   |
| Hewlett-Packard         | 16        | 1.67%   |
| BenQ                    | 16        | 1.67%   |
| AOC                     | 14        | 1.46%   |
| CSO                     | 13        | 1.35%   |
| Philips                 | 12        | 1.25%   |
| PANDA                   | 9         | 0.94%   |
| Panasonic               | 7         | 0.73%   |
| JDI                     | 7         | 0.73%   |
| Ancor Communications    | 7         | 0.73%   |
| Sony                    | 6         | 0.63%   |
| Acer                    | 6         | 0.63%   |
| Goldstar                | 5         | 0.52%   |
| NEC Computers           | 4         | 0.42%   |
| ASUSTek Computer        | 4         | 0.42%   |
| MSI                     | 3         | 0.31%   |
| Grundig                 | 3         | 0.31%   |
| ViewSonic               | 2         | 0.21%   |
| MiTAC                   | 2         | 0.21%   |
| LG Philips              | 2         | 0.21%   |
| HannStar                | 2         | 0.21%   |
| Fujitsu Siemens         | 2         | 0.21%   |
| VOXICON                 | 1         | 0.1%    |
| Vestel Elektronik       | 1         | 0.1%    |
| Toshiba                 | 1         | 0.1%    |
| TMX                     | 1         | 0.1%    |
| TMA                     | 1         | 0.1%    |
| Tatung                  | 1         | 0.1%    |
| STA                     | 1         | 0.1%    |
| SSD                     | 1         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                   | 8         | 0.82%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 8         | 0.82%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch          | 7         | 0.71%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 7         | 0.71%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch               | 6         | 0.61%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                     | 6         | 0.61%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 6         | 0.61%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 5         | 0.51%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch              | 5         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 5         | 0.51%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch          | 5         | 0.51%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 5         | 0.51%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 344x193mm 15.5-inch            | 5         | 0.51%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 5         | 0.51%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 5         | 0.51%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                        | 5         | 0.51%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                   | 4         | 0.41%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch         | 4         | 0.41%   |
| Samsung Electronics LCD Monitor SEC3859 1366x768 293x165mm 13.2-inch      | 4         | 0.41%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch               | 4         | 0.41%   |
| NEC Computers P403 NEC692B 1920x1080 886x498mm 40.0-inch                  | 4         | 0.41%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch              | 4         | 0.41%   |
| LG Display LCD Monitor LGD0354 1366x768 293x165mm 13.2-inch               | 4         | 0.41%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 4         | 0.41%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x189mm 14.1-inch                   | 4         | 0.41%   |
| CSO LCD Monitor CSO1404 1920x1200 302x189mm 14.0-inch                     | 4         | 0.41%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch          | 4         | 0.41%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch           | 4         | 0.41%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch            | 4         | 0.41%   |
| AU Optronics LCD Monitor AUO213D 1920x1080 309x173mm 13.9-inch            | 4         | 0.41%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 4         | 0.41%   |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch                   | 3         | 0.31%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 3         | 0.31%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch      | 3         | 0.31%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch      | 3         | 0.31%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch      | 3         | 0.31%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch      | 3         | 0.31%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch     | 3         | 0.31%   |
| Samsung Electronics LCD Monitor SDC4152 2880x1800 302x189mm 14.0-inch     | 3         | 0.31%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 3         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 432       | 47.37%  |
| 1366x768 (WXGA)    | 144       | 15.79%  |
| 3840x2160 (4K)     | 57        | 6.25%   |
| 1920x1200 (WUXGA)  | 47        | 5.15%   |
| 1600x900 (HD+)     | 40        | 4.39%   |
| 2560x1440 (QHD)    | 38        | 4.17%   |
| 2880x1800          | 22        | 2.41%   |
| 2560x1600          | 21        | 2.3%    |
| 1280x800 (WXGA)    | 18        | 1.97%   |
| 3840x2400          | 12        | 1.32%   |
| 1440x900 (WXGA+)   | 11        | 1.21%   |
| 3440x1440          | 9         | 0.99%   |
| 3840x1080          | 8         | 0.88%   |
| 3000x2000          | 7         | 0.77%   |
| 2160x1440          | 7         | 0.77%   |
| 1280x1024 (SXGA)   | 4         | 0.44%   |
| 1024x600           | 4         | 0.44%   |
| Unknown            | 4         | 0.44%   |
| 1920x540           | 3         | 0.33%   |
| 1360x768           | 3         | 0.33%   |
| 1280x720 (HD)      | 3         | 0.33%   |
| 3200x2000          | 2         | 0.22%   |
| 3200x1800 (QHD+)   | 2         | 0.22%   |
| 1680x1050 (WSXGA+) | 2         | 0.22%   |
| 9600x2160          | 1         | 0.11%   |
| 3840x1600          | 1         | 0.11%   |
| 3840x1100          | 1         | 0.11%   |
| 3456x2160          | 1         | 0.11%   |
| 3072x1920          | 1         | 0.11%   |
| 2880x1620          | 1         | 0.11%   |
| 2646x1024          | 1         | 0.11%   |
| 2560x1080          | 1         | 0.11%   |
| 2304x1440          | 1         | 0.11%   |
| 2240x1400          | 1         | 0.11%   |
| 2048x1152          | 1         | 0.11%   |
| 1920x1280          | 1         | 0.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 285       | 29.66%  |
| 14      | 171       | 17.79%  |
| 13      | 161       | 16.75%  |
| 17      | 57        | 5.93%   |
| 27      | 53        | 5.52%   |
| 24      | 44        | 4.58%   |
| 12      | 38        | 3.95%   |
| 16      | 24        | 2.5%    |
| 31      | 20        | 2.08%   |
| Unknown | 13        | 1.35%   |
| 23      | 11        | 1.14%   |
| 34      | 9         | 0.94%   |
| 40      | 7         | 0.73%   |
| 21      | 7         | 0.73%   |
| 11      | 6         | 0.62%   |
| 54      | 5         | 0.52%   |
| 48      | 5         | 0.52%   |
| 32      | 5         | 0.52%   |
| 49      | 4         | 0.42%   |
| 84      | 3         | 0.31%   |
| 72      | 3         | 0.31%   |
| 25      | 3         | 0.31%   |
| 22      | 3         | 0.31%   |
| 10      | 3         | 0.31%   |
| 55      | 2         | 0.21%   |
| 43      | 2         | 0.21%   |
| 26      | 2         | 0.21%   |
| 19      | 2         | 0.21%   |
| 85      | 1         | 0.1%    |
| 65      | 1         | 0.1%    |
| 60      | 1         | 0.1%    |
| 42      | 1         | 0.1%    |
| 39      | 1         | 0.1%    |
| 38      | 1         | 0.1%    |
| 37      | 1         | 0.1%    |
| 36      | 1         | 0.1%    |
| 33      | 1         | 0.1%    |
| 29      | 1         | 0.1%    |
| 28      | 1         | 0.1%    |
| 18      | 1         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 541       | 56.65%  |
| 201-300     | 135       | 14.14%  |
| 501-600     | 97        | 10.16%  |
| 351-400     | 71        | 7.43%   |
| 601-700     | 31        | 3.25%   |
| 1001-1500   | 18        | 1.88%   |
| 701-800     | 16        | 1.68%   |
| Unknown     | 13        | 1.36%   |
| 401-500     | 12        | 1.26%   |
| 801-900     | 10        | 1.05%   |
| 1501-2000   | 7         | 0.73%   |
| 901-1000    | 3         | 0.31%   |
| 101-200     | 1         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 652       | 77.71%  |
| 16/10   | 134       | 15.97%  |
| 3/2     | 18        | 2.15%   |
| 21/9    | 11        | 1.31%   |
| Unknown | 10        | 1.19%   |
| 32/9    | 8         | 0.95%   |
| 5/4     | 5         | 0.6%    |
| 3.40    | 1         | 0.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 280       | 29.11%  |
| 81-90          | 259       | 26.92%  |
| 71-80          | 67        | 6.96%   |
| 301-350        | 53        | 5.51%   |
| 121-130        | 51        | 5.3%    |
| 201-250        | 48        | 4.99%   |
| 61-70          | 37        | 3.85%   |
| 351-500        | 36        | 3.74%   |
| 111-120        | 25        | 2.6%    |
| 501-1000       | 22        | 2.29%   |
| 251-300        | 21        | 2.18%   |
| More than 1000 | 17        | 1.77%   |
| Unknown        | 13        | 1.35%   |
| 91-100         | 8         | 0.83%   |
| 51-60          | 7         | 0.73%   |
| 131-140        | 7         | 0.73%   |
| 151-200        | 4         | 0.42%   |
| 41-50          | 3         | 0.31%   |
| 141-150        | 3         | 0.31%   |
| 1-40           | 1         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 431       | 45.56%  |
| 101-120       | 179       | 18.92%  |
| 51-100        | 146       | 15.43%  |
| 161-240       | 104       | 10.99%  |
| More than 240 | 60        | 6.34%   |
| 1-50          | 13        | 1.37%   |
| Unknown       | 13        | 1.37%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 618       | 74.64%  |
| 2     | 160       | 19.32%  |
| 3     | 28        | 3.38%   |
| 0     | 21        | 2.54%   |
| 4     | 1         | 0.12%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 540       | 43.9%   |
| Realtek Semiconductor             | 326       | 26.5%   |
| Qualcomm Atheros                  | 111       | 9.02%   |
| Broadcom                          | 68        | 5.53%   |
| MediaTek                          | 28        | 2.28%   |
| Broadcom Limited                  | 22        | 1.79%   |
| Ericsson Business Mobile Networks | 19        | 1.54%   |
| Dell                              | 16        | 1.3%    |
| Sierra Wireless                   | 15        | 1.22%   |
| Hewlett-Packard                   | 9         | 0.73%   |
| Lenovo                            | 8         | 0.65%   |
| DisplayLink                       | 8         | 0.65%   |
| Ralink Technology                 | 6         | 0.49%   |
| Ralink                            | 6         | 0.49%   |
| ASUSTek Computer                  | 6         | 0.49%   |
| Samsung Electronics               | 5         | 0.41%   |
| Marvell Technology Group          | 5         | 0.41%   |
| Qualcomm                          | 4         | 0.33%   |
| NetGear                           | 4         | 0.33%   |
| Fibocom                           | 4         | 0.33%   |
| TP-Link                           | 3         | 0.24%   |
| Qualcomm Atheros Communications   | 3         | 0.24%   |
| Nvidia                            | 2         | 0.16%   |
| Microsoft                         | 2         | 0.16%   |
| JMicron Technology                | 2         | 0.16%   |
| Google                            | 2         | 0.16%   |
| D-Link                            | 2         | 0.16%   |
| Apple                             | 2         | 0.16%   |
| T & A Mobile Phones               | 1         | 0.08%   |
| Huawei Technologies               | 1         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 203       | 13.21%  |
| Intel Wireless 8265 / 8275                                             | 59        | 3.84%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 58        | 3.77%   |
| Intel Wi-Fi 6 AX200                                                    | 47        | 3.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 46        | 2.99%   |
| Intel Wireless 8260                                                    | 39        | 2.54%   |
| Intel Wireless 7265                                                    | 37        | 2.41%   |
| Intel Wireless 7260                                                    | 34        | 2.21%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 29        | 1.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 28        | 1.82%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 24        | 1.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 23        | 1.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 23        | 1.5%    |
| Intel Wi-Fi 6 AX201                                                    | 22        | 1.43%   |
| Intel Ethernet Connection (4) I219-LM                                  | 22        | 1.43%   |
| Intel Ethernet Connection (4) I219-V                                   | 18        | 1.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 18        | 1.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 17        | 1.11%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 17        | 1.11%   |
| Intel Centrino Ultimate-N 6300                                         | 17        | 1.11%   |
| Intel Centrino Advanced-N 6235                                         | 17        | 1.11%   |
| Intel Ethernet Connection (6) I219-V                                   | 16        | 1.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 15        | 0.98%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 14        | 0.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 14        | 0.91%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 14        | 0.91%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 13        | 0.85%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 13        | 0.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 13        | 0.85%   |
| Intel Ethernet Connection I219-LM                                      | 13        | 0.85%   |
| Intel Ethernet Connection I218-LM                                      | 13        | 0.85%   |
| Intel Ethernet Connection (3) I218-LM                                  | 13        | 0.85%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 12        | 0.78%   |
| Intel Ethernet Connection I219-V                                       | 12        | 0.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 12        | 0.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 11        | 0.72%   |
| Broadcom BCM43228 802.11a/b/g/n                                        | 11        | 0.72%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 10        | 0.65%   |
| Intel 82577LM Gigabit Network Connection                               | 10        | 0.65%   |
| Intel Ethernet Connection I217-LM                                      | 9         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 516       | 60.71%  |
| Qualcomm Atheros                | 92        | 10.82%  |
| Realtek Semiconductor           | 74        | 8.71%   |
| Broadcom                        | 58        | 6.82%   |
| MediaTek                        | 22        | 2.59%   |
| Broadcom Limited                | 19        | 2.24%   |
| Sierra Wireless                 | 15        | 1.76%   |
| Dell                            | 10        | 1.18%   |
| Ralink Technology               | 6         | 0.71%   |
| Ralink                          | 6         | 0.71%   |
| ASUSTek Computer                | 6         | 0.71%   |
| Hewlett-Packard                 | 5         | 0.59%   |
| Qualcomm                        | 4         | 0.47%   |
| NetGear                         | 4         | 0.47%   |
| Fibocom                         | 4         | 0.47%   |
| TP-Link                         | 3         | 0.35%   |
| Qualcomm Atheros Communications | 3         | 0.35%   |
| Microsoft                       | 2         | 0.24%   |
| D-Link                          | 1         | 0.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                           | 59        | 6.92%   |
| Intel Wi-Fi 6 AX200                                                  | 47        | 5.51%   |
| Intel Wireless 8260                                                  | 39        | 4.57%   |
| Intel Wireless 7265                                                  | 37        | 4.34%   |
| Intel Wireless 7260                                                  | 34        | 3.99%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 29        | 3.4%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 28        | 3.28%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 24        | 2.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 23        | 2.7%    |
| Intel Wi-Fi 6 AX201                                                  | 22        | 2.58%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 18        | 2.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 17        | 1.99%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 17        | 1.99%   |
| Intel Centrino Ultimate-N 6300                                       | 17        | 1.99%   |
| Intel Centrino Advanced-N 6235                                       | 17        | 1.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 15        | 1.76%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 14        | 1.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 14        | 1.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 14        | 1.64%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 13        | 1.52%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 13        | 1.52%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 13        | 1.52%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 12        | 1.41%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 12        | 1.41%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 11        | 1.29%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 11        | 1.29%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 10        | 1.17%   |
| Sierra Wireless EM7455                                               | 8         | 0.94%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 8         | 0.94%   |
| Intel Wireless 3165                                                  | 8         | 0.94%   |
| Intel Wireless 3160                                                  | 8         | 0.94%   |
| Intel WiFi Link 5100                                                 | 8         | 0.94%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 8         | 0.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 7         | 0.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 7         | 0.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 7         | 0.82%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                 | 7         | 0.82%   |
| Broadcom BCM43224 802.11a/b/g/n                                      | 7         | 0.82%   |
| Intel Meteor Lake PCH CNVi WiFi                                      | 6         | 0.7%    |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 6         | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 288       | 44.65%  |
| Intel                    | 244       | 37.83%  |
| Qualcomm Atheros         | 42        | 6.51%   |
| Broadcom                 | 26        | 4.03%   |
| Lenovo                   | 8         | 1.24%   |
| DisplayLink              | 8         | 1.24%   |
| MediaTek                 | 6         | 0.93%   |
| Marvell Technology Group | 5         | 0.78%   |
| Broadcom Limited         | 5         | 0.78%   |
| Nvidia                   | 2         | 0.31%   |
| JMicron Technology       | 2         | 0.31%   |
| Google                   | 2         | 0.31%   |
| Apple                    | 2         | 0.31%   |
| T & A Mobile Phones      | 1         | 0.16%   |
| Samsung Electronics      | 1         | 0.16%   |
| Huawei Technologies      | 1         | 0.16%   |
| Hewlett-Packard          | 1         | 0.16%   |
| D-Link                   | 1         | 0.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 203       | 31.13%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 58        | 8.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 46        | 7.06%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 23        | 3.53%   |
| Intel Ethernet Connection (4) I219-LM                                  | 22        | 3.37%   |
| Intel Ethernet Connection (4) I219-V                                   | 18        | 2.76%   |
| Intel Ethernet Connection (6) I219-V                                   | 16        | 2.45%   |
| Intel Ethernet Connection I219-LM                                      | 13        | 1.99%   |
| Intel Ethernet Connection I218-LM                                      | 13        | 1.99%   |
| Intel Ethernet Connection (3) I218-LM                                  | 13        | 1.99%   |
| Intel Ethernet Connection I219-V                                       | 12        | 1.84%   |
| Intel 82577LM Gigabit Network Connection                               | 10        | 1.53%   |
| Intel Ethernet Connection I217-LM                                      | 9         | 1.38%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 7         | 1.07%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 7         | 1.07%   |
| Intel Ethernet Connection (13) I219-V                                  | 7         | 1.07%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 6         | 0.92%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 6         | 0.92%   |
| Intel Ethernet Connection (6) I219-LM                                  | 6         | 0.92%   |
| Intel Ethernet Connection (2) I219-LM                                  | 6         | 0.92%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 6         | 0.92%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 5         | 0.77%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 5         | 0.77%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 4         | 0.61%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 4         | 0.61%   |
| Intel Ethernet Connection (3) I218-V                                   | 4         | 0.61%   |
| Intel Ethernet Connection (16) I219-V                                  | 4         | 0.61%   |
| Intel Ethernet Connection (16) I219-LM                                 | 4         | 0.61%   |
| Intel 82567LM Gigabit Network Connection                               | 4         | 0.61%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 4         | 0.61%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 3         | 0.46%   |
| Intel Ethernet Connection (7) I219-LM                                  | 3         | 0.46%   |
| Intel Ethernet Connection (5) I219-LM                                  | 3         | 0.46%   |
| Intel 82579V Gigabit Network Connection                                | 3         | 0.46%   |
| Intel 82577LC Gigabit Network Connection                               | 3         | 0.46%   |
| Intel 82566MM Gigabit Network Connection                               | 3         | 0.46%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 3         | 0.46%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller            | 2         | 0.31%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 0.31%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2         | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 784       | 54.75%  |
| Ethernet | 616       | 43.02%  |
| Modem    | 32        | 2.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 694       | 81.65%  |
| Ethernet | 156       | 18.35%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 541       | 67.46%  |
| 1     | 246       | 30.67%  |
| 3     | 9         | 1.12%   |
| 0     | 6         | 0.75%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 667       | 80.36%  |
| Yes  | 163       | 19.64%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 403       | 59.09%  |
| Broadcom                        | 52        | 7.62%   |
| Realtek Semiconductor           | 47        | 6.89%   |
| Qualcomm Atheros Communications | 33        | 4.84%   |
| Foxconn / Hon Hai               | 29        | 4.25%   |
| IMC Networks                    | 25        | 3.67%   |
| Lite-On Technology              | 24        | 3.52%   |
| Apple                           | 24        | 3.52%   |
| Hewlett-Packard                 | 15        | 2.2%    |
| Dell                            | 11        | 1.61%   |
| ASUSTek Computer                | 6         | 0.88%   |
| Cambridge Silicon Radio         | 3         | 0.44%   |
| Realtek                         | 2         | 0.29%   |
| USI                             | 1         | 0.15%   |
| TP-Link                         | 1         | 0.15%   |
| Toshiba                         | 1         | 0.15%   |
| Ralink Technology               | 1         | 0.15%   |
| Ralink                          | 1         | 0.15%   |
| MediaTek                        | 1         | 0.15%   |
| Integrated System Solution      | 1         | 0.15%   |
| Edimax Technology               | 1         | 0.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 161       | 23.54%  |
| Intel AX201 Bluetooth                               | 58        | 8.48%   |
| Intel AX211 Bluetooth                               | 47        | 6.87%   |
| Intel AX200 Bluetooth                               | 46        | 6.73%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 45        | 6.58%   |
| Realtek Bluetooth Radio                             | 33        | 4.82%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 18        | 2.63%   |
| Broadcom BCM2045B (BDC-2.1)                         | 15        | 2.19%   |
| Apple Bluetooth Host Controller                     | 14        | 2.05%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 13        | 1.9%    |
| Lite-On Bluetooth Device                            | 11        | 1.61%   |
| Intel AX210 Bluetooth                               | 11        | 1.61%   |
| HP Broadcom 2070 Bluetooth Combo                    | 11        | 1.61%   |
| Foxconn / Hon Hai Bluetooth Device                  | 10        | 1.46%   |
| Qualcomm Atheros  Bluetooth Device                  | 9         | 1.32%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 9         | 1.32%   |
| IMC Networks Wireless_Device                        | 9         | 1.32%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 9         | 1.32%   |
| Realtek  Bluetooth 4.2 Adapter                      | 8         | 1.17%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 7         | 1.02%   |
| IMC Networks Bluetooth Radio                        | 7         | 1.02%   |
| Foxconn / Hon Hai Wireless_Device                   | 7         | 1.02%   |
| Apple Bluetooth USB Host Controller                 | 7         | 1.02%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 5         | 0.73%   |
| Lite-On Wireless_Device                             | 5         | 0.73%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 5         | 0.73%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 5         | 0.73%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 5         | 0.73%   |
| IMC Networks Bluetooth Device                       | 4         | 0.58%   |
| Dell DW375 Bluetooth Module                         | 4         | 0.58%   |
| Dell BCM20702A0 Bluetooth Module                    | 4         | 0.58%   |
| Broadcom HP Portable SoftSailing                    | 4         | 0.58%   |
| Broadcom BCM20702A0                                 | 4         | 0.58%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 3         | 0.44%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 0.44%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 3         | 0.44%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 0.44%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 0.44%   |
| Broadcom HP Portable Bumble Bee                     | 3         | 0.44%   |
| Broadcom BCM43142A0 Bluetooth Device                | 3         | 0.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 669       | 65.33%  |
| AMD                                          | 139       | 13.57%  |
| Nvidia                                       | 123       | 12.01%  |
| Realtek Semiconductor                        | 16        | 1.56%   |
| Lenovo                                       | 16        | 1.56%   |
| Logitech                                     | 8         | 0.78%   |
| Kingston Technology                          | 7         | 0.68%   |
| GN Netcom                                    | 6         | 0.59%   |
| Hewlett-Packard                              | 3         | 0.29%   |
| C-Media Electronics                          | 3         | 0.29%   |
| Sony                                         | 2         | 0.2%    |
| Plantronics                                  | 2         | 0.2%    |
| KTMicro                                      | 2         | 0.2%    |
| Dell                                         | 2         | 0.2%    |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.1%    |
| Texas Instruments                            | 1         | 0.1%    |
| SteelSeries ApS                              | 1         | 0.1%    |
| Sonicstar                                    | 1         | 0.1%    |
| Sennheiser Communications                    | 1         | 0.1%    |
| SAVITECH                                     | 1         | 0.1%    |
| Roland                                       | 1         | 0.1%    |
| ROCCAT                                       | 1         | 0.1%    |
| RME                                          | 1         | 0.1%    |
| Razer USA                                    | 1         | 0.1%    |
| Ploytec                                      | 1         | 0.1%    |
| Nordic Semiconductor ASA                     | 1         | 0.1%    |
| NAD                                          | 1         | 0.1%    |
| Mark of the Unicorn                          | 1         | 0.1%    |
| JMTek                                        | 1         | 0.1%    |
| Generalplus Technology                       | 1         | 0.1%    |
| Focusrite-Novation                           | 1         | 0.1%    |
| FiiO Electronics Technology                  | 1         | 0.1%    |
| Elgato Systems                               | 1         | 0.1%    |
| DSEA A/S                                     | 1         | 0.1%    |
| Drop                                         | 1         | 0.1%    |
| Corsair                                      | 1         | 0.1%    |
| Conexant Systems                             | 1         | 0.1%    |
| Audeze                                       | 1         | 0.1%    |
| Arturia                                      | 1         | 0.1%    |
| Apple                                        | 1         | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 121       | 9.85%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 86        | 7%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 59        | 4.8%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 49        | 3.99%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 45        | 3.66%   |
| Intel Cannon Lake PCH cAVS                                                 | 41        | 3.34%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 40        | 3.26%   |
| Intel Haswell-ULT HD Audio Controller                                      | 39        | 3.18%   |
| Intel 8 Series HD Audio Controller                                         | 39        | 3.18%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 35        | 2.85%   |
| Intel Broadwell-U Audio Controller                                         | 35        | 2.85%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 35        | 2.85%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 34        | 2.77%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 32        | 2.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 26        | 2.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 23        | 1.87%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 19        | 1.55%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 18        | 1.47%   |
| AMD FCH Azalia Controller                                                  | 18        | 1.47%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 17        | 1.38%   |
| Realtek Semiconductor USB Audio                                            | 16        | 1.3%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 16        | 1.3%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 15        | 1.22%   |
| Intel CM238 HD Audio Controller                                            | 14        | 1.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 14        | 1.14%   |
| Intel Comet Lake PCH cAVS                                                  | 12        | 0.98%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 12        | 0.98%   |
| Intel Comet Lake PCH-LP cAVS                                               | 11        | 0.9%    |
| Nvidia TU106 High Definition Audio Controller                              | 10        | 0.81%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 9         | 0.73%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 9         | 0.73%   |
| Nvidia TU116 High Definition Audio Controller                              | 8         | 0.65%   |
| Nvidia GF108 High Definition Audio Controller                              | 8         | 0.65%   |
| Nvidia GA106 High Definition Audio Controller                              | 8         | 0.65%   |
| Nvidia GA104 High Definition Audio Controller                              | 8         | 0.65%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 8         | 0.65%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 8         | 0.65%   |
| Nvidia GT216 HDMI Audio Controller                                         | 7         | 0.57%   |
| Nvidia GP107GL High Definition Audio Controller                            | 7         | 0.57%   |
| Intel Meteor Lake-P HD Audio Controller                                    | 7         | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 175       | 34.11%  |
| SK hynix               | 144       | 28.07%  |
| Micron Technology      | 66        | 12.87%  |
| Kingston               | 42        | 8.19%   |
| Unknown                | 18        | 3.51%   |
| Crucial                | 13        | 2.53%   |
| Elpida                 | 9         | 1.75%   |
| Corsair                | 9         | 1.75%   |
| Ramaxel Technology     | 8         | 1.56%   |
| Unknown                | 8         | 1.56%   |
| A-DATA Technology      | 6         | 1.17%   |
| Nanya Technology       | 3         | 0.58%   |
| Unknown (ABCD)         | 1         | 0.19%   |
| Unknown (89F7)         | 1         | 0.19%   |
| Unknown (0x0D0E)       | 1         | 0.19%   |
| Unknown (00000000802C) | 1         | 0.19%   |
| Transcend              | 1         | 0.19%   |
| Toshiba                | 1         | 0.19%   |
| Team                   | 1         | 0.19%   |
| GSkill                 | 1         | 0.19%   |
| G.Skill                | 1         | 0.19%   |
| fef5                   | 1         | 0.19%   |
| ASint Technology       | 1         | 0.19%   |
| 48spaces               | 1         | 0.19%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown                                                             | 8         | 1.48%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 7         | 1.3%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 7         | 1.3%    |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 7         | 1.3%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 7         | 1.3%    |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 6         | 1.11%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 6         | 1.11%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 6         | 1.11%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                           | 5         | 0.93%   |
| Samsung RAM Module 4GB SODIMM DDR3 1867MT/s                         | 5         | 0.93%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 5         | 0.93%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 5         | 0.93%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s               | 5         | 0.93%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 5         | 0.93%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s       | 5         | 0.93%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 2667MT/s              | 4         | 0.74%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 4         | 0.74%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 4         | 0.74%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 4         | 0.74%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 4         | 0.74%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 4         | 0.74%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 4         | 0.74%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 4         | 0.74%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s          | 4         | 0.74%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s              | 4         | 0.74%   |
| Kingston RAM KN2M64-ETB 8GB SODIMM DDR3 1600MT/s                    | 4         | 0.74%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                       | 3         | 0.56%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 0.56%   |
| SK hynix RAM HMAG68EXNSA051N 8GB SODIMM DDR4 3200MT/s               | 3         | 0.56%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 3         | 0.56%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 3         | 0.56%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 3         | 0.56%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 3         | 0.56%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 3         | 0.56%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB SODIMM LPDDR5 6400MT/s          | 3         | 0.56%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s    | 3         | 0.56%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                         | 3         | 0.56%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                      | 3         | 0.56%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 3         | 0.56%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 208       | 46.74%  |
| DDR3    | 120       | 26.97%  |
| LPDDR5  | 33        | 7.42%   |
| LPDDR3  | 32        | 7.19%   |
| LPDDR4  | 25        | 5.62%   |
| DDR5    | 14        | 3.15%   |
| DDR2    | 6         | 1.35%   |
| SDRAM   | 5         | 1.12%   |
| Unknown | 2         | 0.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 351       | 78.17%  |
| Row Of Chips | 82        | 18.26%  |
| Chip         | 11        | 2.45%   |
| Unknown      | 5         | 1.11%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 201       | 42.32%  |
| 4096  | 139       | 29.26%  |
| 16384 | 88        | 18.53%  |
| 2048  | 27        | 5.68%   |
| 32768 | 18        | 3.79%   |
| 1024  | 2         | 0.42%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 105       | 22.11%  |
| 1600  | 83        | 17.47%  |
| 3200  | 77        | 16.21%  |
| 2133  | 48        | 10.11%  |
| 2400  | 30        | 6.32%   |
| 6400  | 24        | 5.05%   |
| 1334  | 19        | 4%      |
| 1867  | 16        | 3.37%   |
| 4267  | 12        | 2.53%   |
| 5600  | 8         | 1.68%   |
| 1333  | 8         | 1.68%   |
| 4800  | 6         | 1.26%   |
| 1067  | 6         | 1.26%   |
| 667   | 5         | 1.05%   |
| 7500  | 4         | 0.84%   |
| 4199  | 4         | 0.84%   |
| 7467  | 3         | 0.63%   |
| 4266  | 3         | 0.63%   |
| 8400  | 2         | 0.42%   |
| 3266  | 2         | 0.42%   |
| 1066  | 2         | 0.42%   |
| 8600  | 1         | 0.21%   |
| 8533  | 1         | 0.21%   |
| 3733  | 1         | 0.21%   |
| 2933  | 1         | 0.21%   |
| 2048  | 1         | 0.21%   |
| 1866  | 1         | 0.21%   |
| 975   | 1         | 0.21%   |
| 800   | 1         | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 3         | 50%     |
| Brother Industries | 2         | 33.33%  |
| Canon              | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Notebooks | Percent |
|---------------------------|-----------|---------|
| HP Printing Support       | 1         | 16.67%  |
| HP ENVY Photo 6200 series | 1         | 16.67%  |
| HP DeskJet 2700 series    | 1         | 16.67%  |
| Canon TS5300 series       | 1         | 16.67%  |
| Brother PT-2450DX         | 1         | 16.67%  |
| Brother HL-1210W series   | 1         | 16.67%  |

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
| Chicony Electronics                    | 178       | 23.96%  |
| IMC Networks                           | 78        | 10.5%   |
| Bison Electronics                      | 71        | 9.56%   |
| Microdia                               | 55        | 7.4%    |
| Sunplus Innovation Technology          | 49        | 6.59%   |
| Realtek Semiconductor                  | 44        | 5.92%   |
| Quanta                                 | 35        | 4.71%   |
| Lite-On Technology                     | 30        | 4.04%   |
| Cheng Uei Precision Industry (Foxlink) | 26        | 3.5%    |
| Apple                                  | 26        | 3.5%    |
| Luxvisions Innotech Limited            | 19        | 2.56%   |
| Suyin                                  | 18        | 2.42%   |
| Logitech                               | 18        | 2.42%   |
| Acer                                   | 16        | 2.15%   |
| Lenovo                                 | 13        | 1.75%   |
| Silicon Motion                         | 9         | 1.21%   |
| Alcor Micro                            | 7         | 0.94%   |
| Syntek                                 | 6         | 0.81%   |
| Shinetech                              | 6         | 0.81%   |
| Samsung Electronics                    | 6         | 0.81%   |
| Primax Electronics                     | 5         | 0.67%   |
| Sonix Technology                       | 4         | 0.54%   |
| Shenzhen Kingcome Optoelectronic       | 4         | 0.54%   |
| Z-Star Microelectronics                | 2         | 0.27%   |
| Ricoh                                  | 2         | 0.27%   |
| Microsoft                              | 2         | 0.27%   |
| Generalplus Technology                 | 2         | 0.27%   |
| Creative Technology                    | 2         | 0.27%   |
| ALi                                    | 2         | 0.27%   |
| Y Media                                | 1         | 0.13%   |
| Sunplus Technology                     | 1         | 0.13%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.13%   |
| Mustek Systems                         | 1         | 0.13%   |
| Intel                                  | 1         | 0.13%   |
| icSpring                               | 1         | 0.13%   |
| DigiTech                               | 1         | 0.13%   |
| Dell                                   | 1         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 66        | 8.84%   |
| Microdia Integrated_Webcam_HD                       | 33        | 4.42%   |
| IMC Networks Integrated Camera                      | 28        | 3.75%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 21        | 2.81%   |
| Bison Integrated Camera                             | 20        | 2.68%   |
| Chicony HP HD Camera                                | 15        | 2.01%   |
| Sunplus Integrated_Webcam_HD                        | 14        | 1.87%   |
| Realtek Integrated_Webcam_HD                        | 14        | 1.87%   |
| Lite-On Integrated Camera                           | 13        | 1.74%   |
| Chicony HP HD Webcam                                | 13        | 1.74%   |
| Chicony HD Webcam                                   | 13        | 1.74%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 12        | 1.61%   |
| Lite-On HP HD Camera                                | 11        | 1.47%   |
| Bison HD Webcam                                     | 10        | 1.34%   |
| Bison SunplusIT Integrated Camera                   | 9         | 1.2%    |
| Quanta HP HD Camera                                 | 8         | 1.07%   |
| Quanta HD User Facing                               | 7         | 0.94%   |
| Luxvisions Innotech Limited Integrated Camera       | 7         | 0.94%   |
| Lenovo Integrated Webcam [R5U877]                   | 7         | 0.94%   |
| Chicony Integrated HP HD Webcam                     | 7         | 0.94%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 7         | 0.94%   |
| Sunplus HD WebCam                                   | 6         | 0.8%    |
| Sunplus ASUS Webcam                                 | 6         | 0.8%    |
| Samsung Galaxy series, misc. (MTP mode)             | 6         | 0.8%    |
| Quanta ACER HD User Facing                          | 6         | 0.8%    |
| Microdia Integrated Webcam                          | 6         | 0.8%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 6         | 0.8%    |
| Bison Lenovo EasyCamera                             | 6         | 0.8%    |
| Apple FaceTime HD Camera                            | 6         | 0.8%    |
| Sunplus Laptop Integrated Webcam HD                 | 5         | 0.67%   |
| Realtek USB2.0 HD UVC WebCam                        | 5         | 0.67%   |
| Lite-On HP HD Webcam                                | 5         | 0.67%   |
| IMC Networks HD Camera                              | 5         | 0.67%   |
| Chicony HP Wide Vision HD Camera                    | 5         | 0.67%   |
| Bison Lenovo Integrated Webcam                      | 5         | 0.67%   |
| Bison BisonCam, NB Pro                              | 5         | 0.67%   |
| ShineTech USB2.0 HD UVC WebCam                      | 4         | 0.54%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera     | 4         | 0.54%   |
| Realtek Integrated Webcam_HD                        | 4         | 0.54%   |
| Quanta HP TrueVision HD Camera                      | 4         | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 77        | 38.5%   |
| Synaptics                          | 67        | 33.5%   |
| Upek                               | 19        | 9.5%    |
| Shenzhen Goodix Technology         | 14        | 7%      |
| Elan Microelectronics              | 6         | 3%      |
| LighTuning Technology              | 5         | 2.5%    |
| AuthenTec                          | 5         | 2.5%    |
| Samsung Electronics                | 3         | 1.5%    |
| Realtek USB2.0 Finger Print Bridge | 3         | 1.5%    |
| STMicroelectronics                 | 1         | 0.5%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 25        | 12.5%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 18        | 9%      |
| Validity Sensors VFS495 Fingerprint Reader                                 | 17        | 8.5%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 17        | 8.5%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 11        | 5.5%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 9         | 4.5%    |
| Validity Sensors Synaptics WBDI                                            | 8         | 4%      |
| Synaptics Fingerprint reader [HP G6]                                       | 7         | 3.5%    |
| Validity Sensors VFS491                                                    | 6         | 3%      |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 3%      |
| Synaptics Prometheus Fingerprint Reader                                    | 6         | 3%      |
| Shenzhen Goodix FingerPrint                                                | 6         | 3%      |
| Synaptics UWP WBDI Device                                                  | 5         | 2.5%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 5         | 2.5%    |
| Shenzhen Goodix  FingerPrint Device                                        | 5         | 2.5%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 2%      |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 2%      |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 2%      |
| Elan ELAN:Fingerprint                                                      | 4         | 2%      |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 1.5%    |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 1.5%    |
| Samsung Fingerprint Sensor Device - 730B                                   | 3         | 1.5%    |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 1.5%    |
| AuthenTec AES2810                                                          | 3         | 1.5%    |
| Synaptics WBDI                                                             | 2         | 1%      |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1%      |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1%      |
| Elan WBF Fingerprint Sensor                                                | 2         | 1%      |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.5%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.5%    |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.5%    |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.5%    |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.5%    |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.5%    |
| LighTuning Fingerprint Reader                                              | 1         | 0.5%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.5%    |
| AuthenTec AES1600                                                          | 1         | 0.5%    |
| Unknown                                                                    | 1         | 0.5%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 45        | 43.69%  |
| Broadcom              | 41        | 39.81%  |
| Upek                  | 10        | 9.71%   |
| Lenovo                | 5         | 4.85%   |
| Hewlett-Packard       | 1         | 0.97%   |
| Gemalto (was Gemplus) | 1         | 0.97%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 45        | 43.69%  |
| Broadcom 58200                                                               | 13        | 12.62%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 10.68%  |
| Broadcom 5880                                                                | 11        | 10.68%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 10        | 9.71%   |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 5.83%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 4.85%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.97%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.97%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 451       | 54.27%  |
| 1     | 283       | 34.06%  |
| 2     | 81        | 9.75%   |
| 3     | 14        | 1.68%   |
| 7     | 1         | 0.12%   |
| 4     | 1         | 0.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 199       | 41.81%  |
| Chipcard                 | 88        | 18.49%  |
| Graphics card            | 81        | 17.02%  |
| Multimedia controller    | 33        | 6.93%   |
| Net/wireless             | 32        | 6.72%   |
| Camera                   | 18        | 3.78%   |
| Card reader              | 8         | 1.68%   |
| Storage                  | 6         | 1.26%   |
| Bluetooth                | 4         | 0.84%   |
| Sound                    | 2         | 0.42%   |
| Net/ethernet             | 2         | 0.42%   |
| Modem                    | 2         | 0.42%   |
| Communication controller | 1         | 0.21%   |


Linux in Serbia - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Serbia.

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

Total: 606

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad Edge 03193VG       | [abb370836a](https://linux-hardware.org/?probe=abb370836a) | Aug 10, 2023 |
| HP            | EliteBook 8560w             | [ea34946fbd](https://linux-hardware.org/?probe=ea34946fbd) | Aug 09, 2023 |
| Alienware     | 14                          | [192b13997d](https://linux-hardware.org/?probe=192b13997d) | Aug 09, 2023 |
| Dell          | Latitude E7450              | [a426887b24](https://linux-hardware.org/?probe=a426887b24) | Aug 08, 2023 |
| HP            | EliteBook 8560w             | [b2177d3c55](https://linux-hardware.org/?probe=b2177d3c55) | Aug 06, 2023 |
| Dell          | Inspiron 5521               | [21063bc0bb](https://linux-hardware.org/?probe=21063bc0bb) | Aug 05, 2023 |
| Apple         | MacBookPro8,2               | [573e7f6ad0](https://linux-hardware.org/?probe=573e7f6ad0) | Aug 03, 2023 |
| Acer          | Aspire ES1-520              | [437e15fae7](https://linux-hardware.org/?probe=437e15fae7) | Aug 03, 2023 |
| Acer          | Aspire 5733                 | [f09853c0ed](https://linux-hardware.org/?probe=f09853c0ed) | Aug 03, 2023 |
| Acer          | Aspire ES1-520              | [1cf260b959](https://linux-hardware.org/?probe=1cf260b959) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [f75ea8cfef](https://linux-hardware.org/?probe=f75ea8cfef) | Aug 02, 2023 |
| ASUSTek       | K54C                        | [f4fcf79e7e](https://linux-hardware.org/?probe=f4fcf79e7e) | Aug 02, 2023 |
| Lenovo        | V15-IGL 82C3                | [6c0a6fff0a](https://linux-hardware.org/?probe=6c0a6fff0a) | Jul 31, 2023 |
| HP            | EliteBook 840 G5            | [875ac8e861](https://linux-hardware.org/?probe=875ac8e861) | Jul 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [19b6ecf591](https://linux-hardware.org/?probe=19b6ecf591) | Jul 29, 2023 |
| Apple         | MacBookPro8,2               | [10db13c772](https://linux-hardware.org/?probe=10db13c772) | Jul 26, 2023 |
| Synology      | DS923+                      | [4e023a4222](https://linux-hardware.org/?probe=4e023a4222) | Jul 21, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [31c0d94d23](https://linux-hardware.org/?probe=31c0d94d23) | Jul 18, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [d4a4fec7c0](https://linux-hardware.org/?probe=d4a4fec7c0) | Jul 17, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [6130474cb1](https://linux-hardware.org/?probe=6130474cb1) | Jul 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [b1ceb90106](https://linux-hardware.org/?probe=b1ceb90106) | Jul 12, 2023 |
| Lenovo        | ThinkPad T460 20FMS43Q00    | [3f0c520d07](https://linux-hardware.org/?probe=3f0c520d07) | Jul 10, 2023 |
| HP            | EliteBook 830 G6            | [7a29f3d086](https://linux-hardware.org/?probe=7a29f3d086) | Jun 20, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [8550e224ec](https://linux-hardware.org/?probe=8550e224ec) | Jun 20, 2023 |
| Lenovo        | G550 20023                  | [a1eac5da7c](https://linux-hardware.org/?probe=a1eac5da7c) | Jun 18, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [9529a983b8](https://linux-hardware.org/?probe=9529a983b8) | Jun 07, 2023 |
| Lenovo        | ThinkPad X201 3680Y4F       | [7823148e7d](https://linux-hardware.org/?probe=7823148e7d) | Jun 07, 2023 |
| Acer          | Aspire A315-31              | [d5da1b4b30](https://linux-hardware.org/?probe=d5da1b4b30) | Jun 06, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [c198463bc3](https://linux-hardware.org/?probe=c198463bc3) | May 31, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [574e88c4f3](https://linux-hardware.org/?probe=574e88c4f3) | May 28, 2023 |
| Acer          | Nitro AN517-54              | [4feb3e3196](https://linux-hardware.org/?probe=4feb3e3196) | May 27, 2023 |
| Dell          | Latitude 5440               | [9ed4f0e7ac](https://linux-hardware.org/?probe=9ed4f0e7ac) | May 27, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [4362f979b8](https://linux-hardware.org/?probe=4362f979b8) | May 26, 2023 |
| HP            | EliteBook 820 G1            | [1498cf091b](https://linux-hardware.org/?probe=1498cf091b) | May 26, 2023 |
| HP            | EliteBook 820 G1            | [46a6988c7a](https://linux-hardware.org/?probe=46a6988c7a) | May 25, 2023 |
| Dell          | Latitude 5440               | [5a27bd40e7](https://linux-hardware.org/?probe=5a27bd40e7) | May 25, 2023 |
| HP            | 250 G8 Notebook PC          | [b7d26b3293](https://linux-hardware.org/?probe=b7d26b3293) | May 24, 2023 |
| HP            | 250 G8 Notebook PC          | [e3a554c09d](https://linux-hardware.org/?probe=e3a554c09d) | May 24, 2023 |
| Acer          | Aspire A715-42G             | [39bb190ac7](https://linux-hardware.org/?probe=39bb190ac7) | May 22, 2023 |
| Apple         | MacBookPro16,2              | [e4adcd71f1](https://linux-hardware.org/?probe=e4adcd71f1) | May 21, 2023 |
| Apple         | MacBookPro16,2              | [09f37f2540](https://linux-hardware.org/?probe=09f37f2540) | May 21, 2023 |
| ASUSTek       | X540SC                      | [240bb6c246](https://linux-hardware.org/?probe=240bb6c246) | May 21, 2023 |
| HP            | EliteBook 820 G1            | [386869568d](https://linux-hardware.org/?probe=386869568d) | May 17, 2023 |
| HP            | 250 G8 Notebook PC          | [47430a463a](https://linux-hardware.org/?probe=47430a463a) | May 15, 2023 |
| HP            | EliteBook 820 G1            | [e50adfaff9](https://linux-hardware.org/?probe=e50adfaff9) | May 15, 2023 |
| Acer          | Aspire A715-42G             | [b43ec1363a](https://linux-hardware.org/?probe=b43ec1363a) | May 14, 2023 |
| Acer          | Aspire A715-42G             | [b80a472c1a](https://linux-hardware.org/?probe=b80a472c1a) | May 14, 2023 |
| Dell          | Precision M4500             | [315cccc082](https://linux-hardware.org/?probe=315cccc082) | May 14, 2023 |
| Timi          | Xiaomi Book Pro 14 2022     | [d01779a93b](https://linux-hardware.org/?probe=d01779a93b) | May 09, 2023 |
| Lenovo        | G550 20023                  | [33cc483e77](https://linux-hardware.org/?probe=33cc483e77) | May 09, 2023 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [a9fe0fdf88](https://linux-hardware.org/?probe=a9fe0fdf88) | May 07, 2023 |
| Apple         | MacBookPro6,2               | [3e154e4ccc](https://linux-hardware.org/?probe=3e154e4ccc) | Apr 28, 2023 |
| Apple         | MacBookPro6,2               | [2628c3040f](https://linux-hardware.org/?probe=2628c3040f) | Apr 28, 2023 |
| HP            | OMEN by Laptop 15-dh1xxx    | [3c104a89ef](https://linux-hardware.org/?probe=3c104a89ef) | Apr 26, 2023 |
| Dell          | Vostro 15 3510              | [81cae0ba77](https://linux-hardware.org/?probe=81cae0ba77) | Apr 26, 2023 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | [167000be9b](https://linux-hardware.org/?probe=167000be9b) | Apr 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [258a5bb354](https://linux-hardware.org/?probe=258a5bb354) | Apr 19, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [889301578c](https://linux-hardware.org/?probe=889301578c) | Apr 18, 2023 |
| Acer          | Aspire 5336                 | [ddf5053ffa](https://linux-hardware.org/?probe=ddf5053ffa) | Apr 18, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [55a12acf3a](https://linux-hardware.org/?probe=55a12acf3a) | Apr 12, 2023 |
| Lenovo        | V570 1066EDG                | [8a8a256b79](https://linux-hardware.org/?probe=8a8a256b79) | Apr 02, 2023 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | [51c7ed9156](https://linux-hardware.org/?probe=51c7ed9156) | Apr 01, 2023 |
| ASUSTek       | E200HA                      | [5dfef9c764](https://linux-hardware.org/?probe=5dfef9c764) | Mar 26, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [178936b7f4](https://linux-hardware.org/?probe=178936b7f4) | Mar 24, 2023 |
| HP            | EliteBook 2530p             | [06ad8714ea](https://linux-hardware.org/?probe=06ad8714ea) | Mar 22, 2023 |
| ASUSTek       | T300CHI                     | [371961ad53](https://linux-hardware.org/?probe=371961ad53) | Mar 19, 2023 |
| Lenovo        | G550 20023                  | [6296457407](https://linux-hardware.org/?probe=6296457407) | Mar 18, 2023 |
| Lenovo        | G550 20023                  | [f5bd764775](https://linux-hardware.org/?probe=f5bd764775) | Mar 18, 2023 |
| Lenovo        | G550 20023                  | [c356d98a54](https://linux-hardware.org/?probe=c356d98a54) | Mar 17, 2023 |
| ASUSTek       | K93SV                       | [aa66f39ad6](https://linux-hardware.org/?probe=aa66f39ad6) | Mar 13, 2023 |
| ASUSTek       | E200HA                      | [46a16afb4b](https://linux-hardware.org/?probe=46a16afb4b) | Mar 03, 2023 |
| Lenovo        | V570 1066EDG                | [deb326cc4b](https://linux-hardware.org/?probe=deb326cc4b) | Feb 26, 2023 |
| Lenovo        | V570 1066EDG                | [cc220b6122](https://linux-hardware.org/?probe=cc220b6122) | Feb 26, 2023 |
| Lenovo        | ThinkPad T495s 20QJS0GG0... | [6186149a54](https://linux-hardware.org/?probe=6186149a54) | Feb 24, 2023 |
| HONOR         | NBR-WAX9                    | [b16ea0055d](https://linux-hardware.org/?probe=b16ea0055d) | Feb 17, 2023 |
| HP            | OMEN by Laptop 17-ck1xxx    | [18f60be847](https://linux-hardware.org/?probe=18f60be847) | Feb 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2f721ad33a](https://linux-hardware.org/?probe=2f721ad33a) | Feb 10, 2023 |
| ASUSTek       | ROG Strix G733QR_G733QR     | [da12318597](https://linux-hardware.org/?probe=da12318597) | Feb 10, 2023 |
| Dell          | Inspiron 3558               | [310425ba43](https://linux-hardware.org/?probe=310425ba43) | Feb 08, 2023 |
| Lenovo        | V570 1066EDG                | [f963048c4c](https://linux-hardware.org/?probe=f963048c4c) | Feb 08, 2023 |
| Lenovo        | V570 1066EDG                | [e3ffc73e43](https://linux-hardware.org/?probe=e3ffc73e43) | Feb 06, 2023 |
| TWC           | Unknown                     | [4ea2803396](https://linux-hardware.org/?probe=4ea2803396) | Feb 06, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [fcd4f7a01a](https://linux-hardware.org/?probe=fcd4f7a01a) | Feb 06, 2023 |
| HP            | 250 G5 Notebook PC          | [d389ca29d1](https://linux-hardware.org/?probe=d389ca29d1) | Feb 06, 2023 |
| Lenovo        | V570 1066EDG                | [00714979fe](https://linux-hardware.org/?probe=00714979fe) | Feb 06, 2023 |
| Dell          | XPS 15 9550                 | [200495d065](https://linux-hardware.org/?probe=200495d065) | Feb 04, 2023 |
| Dell          | Vostro 15 3515              | [357d14774f](https://linux-hardware.org/?probe=357d14774f) | Jan 30, 2023 |
| ASUSTek       | K55A                        | [e3088b45e1](https://linux-hardware.org/?probe=e3088b45e1) | Jan 29, 2023 |
| ASUSTek       | K93SV                       | [3b4dd13d9f](https://linux-hardware.org/?probe=3b4dd13d9f) | Jan 29, 2023 |
| Toshiba       | Satellite C870-17H          | [8fe4718795](https://linux-hardware.org/?probe=8fe4718795) | Jan 28, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [d825caa85e](https://linux-hardware.org/?probe=d825caa85e) | Jan 27, 2023 |
| Dell          | Precision 3550              | [4c42615cef](https://linux-hardware.org/?probe=4c42615cef) | Jan 27, 2023 |
| HP            | Laptop 15s-eq3xxx           | [b871955b27](https://linux-hardware.org/?probe=b871955b27) | Jan 23, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [2194886c52](https://linux-hardware.org/?probe=2194886c52) | Jan 23, 2023 |
| Acer          | Aspire 5755G                | [1bf0fe4342](https://linux-hardware.org/?probe=1bf0fe4342) | Jan 22, 2023 |
| Apple         | MacBookPro5,3               | [2375f407c7](https://linux-hardware.org/?probe=2375f407c7) | Jan 22, 2023 |
| ASUSTek       | X453MA                      | [94b155d9c2](https://linux-hardware.org/?probe=94b155d9c2) | Jan 21, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [db998abdae](https://linux-hardware.org/?probe=db998abdae) | Jan 19, 2023 |
| ASUSTek       | X201EP                      | [def6593908](https://linux-hardware.org/?probe=def6593908) | Jan 16, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [a09ace045e](https://linux-hardware.org/?probe=a09ace045e) | Jan 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [295ef21c8b](https://linux-hardware.org/?probe=295ef21c8b) | Jan 15, 2023 |
| Lenovo        | IdeaPad Y570 20091          | [3538dd1b8a](https://linux-hardware.org/?probe=3538dd1b8a) | Jan 11, 2023 |
| Lenovo        | ThinkPad T430 2349JN0       | [fceb17b32c](https://linux-hardware.org/?probe=fceb17b32c) | Jan 10, 2023 |
| Lenovo        | ThinkPad T430 2349JN0       | [04a54f4c2f](https://linux-hardware.org/?probe=04a54f4c2f) | Jan 09, 2023 |
| Dell          | Inspiron 3537               | [234580243d](https://linux-hardware.org/?probe=234580243d) | Jan 08, 2023 |
| Lenovo        | ThinkPad W500 4061WFA       | [4850dba7c8](https://linux-hardware.org/?probe=4850dba7c8) | Jan 08, 2023 |
| ASUSTek       | E200HA                      | [f84fb1bab3](https://linux-hardware.org/?probe=f84fb1bab3) | Jan 08, 2023 |
| eMachines     | E725                        | [0655d63f70](https://linux-hardware.org/?probe=0655d63f70) | Jan 06, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | [1afcc520de](https://linux-hardware.org/?probe=1afcc520de) | Jan 05, 2023 |
| ASUSTek       | K52JT                       | [77abcf7aee](https://linux-hardware.org/?probe=77abcf7aee) | Jan 05, 2023 |
| HP            | 255 G8 Notebook PC          | [05209e0503](https://linux-hardware.org/?probe=05209e0503) | Dec 29, 2022 |
| HP            | Victus by Laptop 16-e1xx... | [25183d70e2](https://linux-hardware.org/?probe=25183d70e2) | Dec 29, 2022 |
| Acer          | Aspire 5741                 | [1c41b5afb0](https://linux-hardware.org/?probe=1c41b5afb0) | Dec 27, 2022 |
| HUAWEI        | CREM-WXX9                   | [a48a2f6362](https://linux-hardware.org/?probe=a48a2f6362) | Dec 24, 2022 |
| Lenovo        | Legion 7 16IAX7 82TD        | [46e5d4fe56](https://linux-hardware.org/?probe=46e5d4fe56) | Dec 20, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [e8b0c03cb9](https://linux-hardware.org/?probe=e8b0c03cb9) | Dec 15, 2022 |
| Acer          | Nitro AN517-51              | [6b5fd6a48c](https://linux-hardware.org/?probe=6b5fd6a48c) | Dec 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [937053920b](https://linux-hardware.org/?probe=937053920b) | Dec 04, 2022 |
| Dell          | Inspiron N5050              | [c6bca6efa8](https://linux-hardware.org/?probe=c6bca6efa8) | Dec 03, 2022 |
| Dell          | Inspiron N5050              | [e4c533a89b](https://linux-hardware.org/?probe=e4c533a89b) | Nov 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon 34601... | [ed678da106](https://linux-hardware.org/?probe=ed678da106) | Nov 26, 2022 |
| HP            | ProBook 445 14 inch G9 N... | [a20535bd66](https://linux-hardware.org/?probe=a20535bd66) | Nov 24, 2022 |
| HP            | Pavilion dv7                | [839266e415](https://linux-hardware.org/?probe=839266e415) | Nov 19, 2022 |
| HP            | Notebook                    | [2721a90e68](https://linux-hardware.org/?probe=2721a90e68) | Nov 19, 2022 |
| Dell          | Inspiron 3584               | [c3fde80859](https://linux-hardware.org/?probe=c3fde80859) | Nov 14, 2022 |
| Dell          | Inspiron 3584               | [c8e8add499](https://linux-hardware.org/?probe=c8e8add499) | Nov 14, 2022 |
| ASUSTek       | K93SV                       | [8511ee86ad](https://linux-hardware.org/?probe=8511ee86ad) | Nov 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [db62973b36](https://linux-hardware.org/?probe=db62973b36) | Nov 06, 2022 |
| Acer          | Aspire V3-571G              | [3d642bde4b](https://linux-hardware.org/?probe=3d642bde4b) | Nov 05, 2022 |
| Timi          | RedmiBook 14 II             | [374be77f36](https://linux-hardware.org/?probe=374be77f36) | Nov 05, 2022 |
| ASUSTek       | X751LB                      | [b9f1ea7699](https://linux-hardware.org/?probe=b9f1ea7699) | Nov 04, 2022 |
| ASUSTek       | X751LB                      | [e7334f33eb](https://linux-hardware.org/?probe=e7334f33eb) | Nov 04, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [7d6d6c3c3a](https://linux-hardware.org/?probe=7d6d6c3c3a) | Nov 04, 2022 |
| Acer          | Aspire V3-571G              | [990a38ea87](https://linux-hardware.org/?probe=990a38ea87) | Nov 01, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [491477817a](https://linux-hardware.org/?probe=491477817a) | Oct 25, 2022 |
| ASUSTek       | N750JK                      | [341d4b53b1](https://linux-hardware.org/?probe=341d4b53b1) | Oct 20, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [d928c22430](https://linux-hardware.org/?probe=d928c22430) | Oct 14, 2022 |
| MSI           | GP66 Leopard 10UG           | [c2082a042d](https://linux-hardware.org/?probe=c2082a042d) | Oct 06, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [b07d3b7b7f](https://linux-hardware.org/?probe=b07d3b7b7f) | Oct 05, 2022 |
| Lenovo        | B50-45 20388                | [c5f81be3fd](https://linux-hardware.org/?probe=c5f81be3fd) | Oct 02, 2022 |
| Lenovo        | V570 1066EDG                | [8e2439c590](https://linux-hardware.org/?probe=8e2439c590) | Oct 01, 2022 |
| Dell          | Precision M4800             | [d4142adadc](https://linux-hardware.org/?probe=d4142adadc) | Sep 29, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [d06b40ddf1](https://linux-hardware.org/?probe=d06b40ddf1) | Sep 29, 2022 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [9fbedd972e](https://linux-hardware.org/?probe=9fbedd972e) | Sep 24, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X1S... | [6e943a4d35](https://linux-hardware.org/?probe=6e943a4d35) | Sep 23, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [641ad27b06](https://linux-hardware.org/?probe=641ad27b06) | Sep 22, 2022 |
| HP            | ProBook 6560b               | [743f401352](https://linux-hardware.org/?probe=743f401352) | Sep 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [d0d43b3cc5](https://linux-hardware.org/?probe=d0d43b3cc5) | Sep 14, 2022 |
| Dell          | Inspiron N5050              | [131f5046db](https://linux-hardware.org/?probe=131f5046db) | Sep 11, 2022 |
| Apple         | MacBookPro8,2               | [a30032ef92](https://linux-hardware.org/?probe=a30032ef92) | Sep 11, 2022 |
| Apple         | MacBookPro8,2               | [0645f03606](https://linux-hardware.org/?probe=0645f03606) | Sep 11, 2022 |
| LG Electro... | 17Z990-R.AAS8U1             | [2df5aeabed](https://linux-hardware.org/?probe=2df5aeabed) | Sep 08, 2022 |
| Dell          | Inspiron 3593               | [fd6ab0c9e5](https://linux-hardware.org/?probe=fd6ab0c9e5) | Sep 07, 2022 |
| ASUSTek       | Zenbook UX5400EA_UX5400E... | [6ce8accfb1](https://linux-hardware.org/?probe=6ce8accfb1) | Sep 04, 2022 |
| Apple         | MacBookPro5,1               | [beec88b95c](https://linux-hardware.org/?probe=beec88b95c) | Sep 04, 2022 |
| Apple         | MacBookPro5,1               | [4c90105342](https://linux-hardware.org/?probe=4c90105342) | Sep 01, 2022 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [e3c7cd81e8](https://linux-hardware.org/?probe=e3c7cd81e8) | Aug 27, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [f945f778b2](https://linux-hardware.org/?probe=f945f778b2) | Aug 26, 2022 |
| Apple         | MacBookPro5,1               | [6efab17b42](https://linux-hardware.org/?probe=6efab17b42) | Aug 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | [255a1cdf9a](https://linux-hardware.org/?probe=255a1cdf9a) | Aug 24, 2022 |
| ASUSTek       | X542BA                      | [7e86736ebc](https://linux-hardware.org/?probe=7e86736ebc) | Aug 21, 2022 |
| ASUSTek       | K54C                        | [e10b52270f](https://linux-hardware.org/?probe=e10b52270f) | Aug 17, 2022 |
| Dell          | Inspiron 3521               | [ebf974be3e](https://linux-hardware.org/?probe=ebf974be3e) | Aug 13, 2022 |
| Dell          | Inspiron 3521               | [6dd71dbcf3](https://linux-hardware.org/?probe=6dd71dbcf3) | Aug 12, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [fa9cdcd977](https://linux-hardware.org/?probe=fa9cdcd977) | Aug 12, 2022 |
| Apple         | MacBookPro5,1               | [ab09f2f44b](https://linux-hardware.org/?probe=ab09f2f44b) | Aug 11, 2022 |
| Sony          | VPCZ12M9E                   | [75f1c2f156](https://linux-hardware.org/?probe=75f1c2f156) | Aug 02, 2022 |
| Sony          | VPCEE23FX                   | [b4108910d3](https://linux-hardware.org/?probe=b4108910d3) | Jul 25, 2022 |
| Acer          | Nitro AN515-55              | [b121274e4f](https://linux-hardware.org/?probe=b121274e4f) | Jul 23, 2022 |
| Apple         | MacBookPro5,1               | [4bae560f04](https://linux-hardware.org/?probe=4bae560f04) | Jul 22, 2022 |
| Apple         | MacBookPro5,1               | [8a81341ecd](https://linux-hardware.org/?probe=8a81341ecd) | Jul 18, 2022 |
| HP            | Compaq nx7300 (RU373ES#A... | [3004f1d2b9](https://linux-hardware.org/?probe=3004f1d2b9) | Jul 16, 2022 |
| Gigabyte      | AERO 17 KC                  | [b6398b12e2](https://linux-hardware.org/?probe=b6398b12e2) | Jul 13, 2022 |
| Lenovo        | ThinkPad X280 20KES8D400    | [fdc339a6b0](https://linux-hardware.org/?probe=fdc339a6b0) | Jul 09, 2022 |
| Lenovo        | ThinkPad X280 20KES8D400    | [7d2b04b0ce](https://linux-hardware.org/?probe=7d2b04b0ce) | Jul 09, 2022 |
| Dell          | Vostro 15 3515              | [c6e9a42a66](https://linux-hardware.org/?probe=c6e9a42a66) | Jul 08, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [c01cf9f7fc](https://linux-hardware.org/?probe=c01cf9f7fc) | Jul 05, 2022 |
| HP            | 250 G4                      | [3d629889b2](https://linux-hardware.org/?probe=3d629889b2) | Jul 05, 2022 |
| HP            | 250 G4                      | [e19f8a8485](https://linux-hardware.org/?probe=e19f8a8485) | Jul 05, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | [be7fd47ea1](https://linux-hardware.org/?probe=be7fd47ea1) | Jul 04, 2022 |
| Timi          | TM1613                      | [6d3f245289](https://linux-hardware.org/?probe=6d3f245289) | Jul 04, 2022 |
| Timi          | TM1613                      | [38d9919cfd](https://linux-hardware.org/?probe=38d9919cfd) | Jul 03, 2022 |
| Dell          | Inspiron 3593               | [5b091180ec](https://linux-hardware.org/?probe=5b091180ec) | Jun 28, 2022 |
| Lenovo        | ThinkPad T560 20FJS1KE00    | [f0cd91b4d2](https://linux-hardware.org/?probe=f0cd91b4d2) | Jun 21, 2022 |
| Lenovo        | Unknown                     | [cd2f32d91c](https://linux-hardware.org/?probe=cd2f32d91c) | Jun 16, 2022 |
| HP            | Pavilion Notebook           | [06c982ad14](https://linux-hardware.org/?probe=06c982ad14) | Jun 16, 2022 |
| Lenovo        | ThinkPad T60 2007FUG        | [2c1a306677](https://linux-hardware.org/?probe=2c1a306677) | Jun 16, 2022 |
| ASUSTek       | K55VD                       | [7fa5d36a45](https://linux-hardware.org/?probe=7fa5d36a45) | Jun 04, 2022 |
| HP            | ProBook 470 G1              | [ef73457d51](https://linux-hardware.org/?probe=ef73457d51) | May 31, 2022 |
| Lenovo        | ThinkPad T490 20N2000LMZ    | [9ebff03a43](https://linux-hardware.org/?probe=9ebff03a43) | May 26, 2022 |
| Lenovo        | ThinkPad T490 20N2000LMZ    | [cc80808aea](https://linux-hardware.org/?probe=cc80808aea) | May 26, 2022 |
| Lenovo        | ThinkPad T61 6463Y3W        | [065aa2538b](https://linux-hardware.org/?probe=065aa2538b) | May 18, 2022 |
| HP            | Laptop 15-db1xxx            | [f6262ce7f2](https://linux-hardware.org/?probe=f6262ce7f2) | May 12, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [e90b6752ba](https://linux-hardware.org/?probe=e90b6752ba) | May 12, 2022 |
| HP            | ProBook 450 G2              | [2c2a15aab2](https://linux-hardware.org/?probe=2c2a15aab2) | May 12, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [d18df271fd](https://linux-hardware.org/?probe=d18df271fd) | May 09, 2022 |
| Medion        | X781X/X782X                 | [fbe630f91c](https://linux-hardware.org/?probe=fbe630f91c) | May 07, 2022 |
| Lenovo        | IdeaPad Z370                | [be37f3c962](https://linux-hardware.org/?probe=be37f3c962) | May 04, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [633bddd44b](https://linux-hardware.org/?probe=633bddd44b) | Apr 30, 2022 |
| Acer          | Nitro AN517-51              | [81d7fd8d2e](https://linux-hardware.org/?probe=81d7fd8d2e) | Apr 30, 2022 |
| Dell          | Latitude 7280               | [e64ba65609](https://linux-hardware.org/?probe=e64ba65609) | Apr 22, 2022 |
| Lenovo        | Unknown                     | [6e1760aed0](https://linux-hardware.org/?probe=6e1760aed0) | Apr 17, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [b888c78ed6](https://linux-hardware.org/?probe=b888c78ed6) | Apr 12, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [45dad76f04](https://linux-hardware.org/?probe=45dad76f04) | Apr 12, 2022 |
| HP            | Notebook                    | [4ffd4d11a5](https://linux-hardware.org/?probe=4ffd4d11a5) | Apr 09, 2022 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [0dbb9e7eb0](https://linux-hardware.org/?probe=0dbb9e7eb0) | Apr 09, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [950a436db3](https://linux-hardware.org/?probe=950a436db3) | Apr 06, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [906de71a65](https://linux-hardware.org/?probe=906de71a65) | Apr 02, 2022 |
| Lenovo        | V330-15IKB 81AX             | [8a881c75f4](https://linux-hardware.org/?probe=8a881c75f4) | Mar 29, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [5eb56f360e](https://linux-hardware.org/?probe=5eb56f360e) | Mar 29, 2022 |
| Fujitsu       | LIFEBOOK AH531              | [f92c8b77dc](https://linux-hardware.org/?probe=f92c8b77dc) | Mar 25, 2022 |
| Fujitsu Si... | AMILO Li3710                | [ab84e23108](https://linux-hardware.org/?probe=ab84e23108) | Mar 24, 2022 |
| Dell          | Inspiron 3542               | [6a8c31fa33](https://linux-hardware.org/?probe=6a8c31fa33) | Mar 21, 2022 |
| Apple         | MacBookPro8,1               | [f55145f34a](https://linux-hardware.org/?probe=f55145f34a) | Mar 16, 2022 |
| Toshiba       | Satellite C870-17H          | [0169bf05d7](https://linux-hardware.org/?probe=0169bf05d7) | Mar 10, 2022 |
| Fujitsu Si... | AMILO Li3710                | [7a4a682f45](https://linux-hardware.org/?probe=7a4a682f45) | Mar 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [2c44722344](https://linux-hardware.org/?probe=2c44722344) | Mar 03, 2022 |
| ASUSTek       | E200HA                      | [69ec87e43a](https://linux-hardware.org/?probe=69ec87e43a) | Mar 02, 2022 |
| HP            | Laptop 15s-fq0xxx           | [9acf95b26b](https://linux-hardware.org/?probe=9acf95b26b) | Feb 28, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [03a49e64cf](https://linux-hardware.org/?probe=03a49e64cf) | Feb 28, 2022 |
| Gigabyte      | AERO 17 KC                  | [08b488b969](https://linux-hardware.org/?probe=08b488b969) | Feb 27, 2022 |
| Dell          | Latitude 7490               | [003b6b4a95](https://linux-hardware.org/?probe=003b6b4a95) | Feb 21, 2022 |
| Dell          | Inspiron 3581               | [0ae0e53b53](https://linux-hardware.org/?probe=0ae0e53b53) | Feb 20, 2022 |
| HP            | Notebook                    | [a1f9f76ed0](https://linux-hardware.org/?probe=a1f9f76ed0) | Feb 19, 2022 |
| Toshiba       | Satellite C55-A             | [19133950aa](https://linux-hardware.org/?probe=19133950aa) | Feb 15, 2022 |
| ASUSTek       | X55A                        | [c6b17158ac](https://linux-hardware.org/?probe=c6b17158ac) | Feb 14, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X1S... | [4f80537faf](https://linux-hardware.org/?probe=4f80537faf) | Feb 06, 2022 |
| Toshiba       | Satellite C55-C             | [379d3b37b1](https://linux-hardware.org/?probe=379d3b37b1) | Feb 05, 2022 |
| BenQ          | Joybook Lite U121           | [28f254dd8d](https://linux-hardware.org/?probe=28f254dd8d) | Feb 02, 2022 |
| Dell          | Vostro 3500                 | [729abacd12](https://linux-hardware.org/?probe=729abacd12) | Feb 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [5e9f8a1c0d](https://linux-hardware.org/?probe=5e9f8a1c0d) | Jan 29, 2022 |
| Dell          | Latitude E6510              | [efc619cc61](https://linux-hardware.org/?probe=efc619cc61) | Jan 28, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [37ec4f5294](https://linux-hardware.org/?probe=37ec4f5294) | Jan 25, 2022 |
| ASUSTek       | E200HA                      | [2c53d21746](https://linux-hardware.org/?probe=2c53d21746) | Jan 22, 2022 |
| ASUSTek       | E200HA                      | [02be439ac8](https://linux-hardware.org/?probe=02be439ac8) | Jan 22, 2022 |
| HP            | EliteBook 1050 G1           | [1bb5cb826f](https://linux-hardware.org/?probe=1bb5cb826f) | Jan 19, 2022 |
| TWC           | Unknown                     | [85a8fd2cf1](https://linux-hardware.org/?probe=85a8fd2cf1) | Jan 18, 2022 |
| TWC           | Unknown                     | [d4cc69cea7](https://linux-hardware.org/?probe=d4cc69cea7) | Jan 16, 2022 |
| Fujitsu       | LIFEBOOK A3510              | [b673072fbb](https://linux-hardware.org/?probe=b673072fbb) | Jan 11, 2022 |
| Dell          | Vostro 5402                 | [f586d10ee6](https://linux-hardware.org/?probe=f586d10ee6) | Jan 05, 2022 |
| MSI           | GT70 2PC                    | [61a5023d6a](https://linux-hardware.org/?probe=61a5023d6a) | Jan 03, 2022 |
| Dell          | Latitude 7490               | [2d6469644a](https://linux-hardware.org/?probe=2d6469644a) | Jan 02, 2022 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | [afb7fa66f5](https://linux-hardware.org/?probe=afb7fa66f5) | Dec 30, 2021 |
| Dell          | Latitude 7490               | [4e350048ed](https://linux-hardware.org/?probe=4e350048ed) | Dec 27, 2021 |
| Fujitsu Si... | AMILO Li3710                | [183a47572f](https://linux-hardware.org/?probe=183a47572f) | Dec 27, 2021 |
| ASUSTek       | X580VD                      | [fe350107e3](https://linux-hardware.org/?probe=fe350107e3) | Dec 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | [74591e1700](https://linux-hardware.org/?probe=74591e1700) | Dec 12, 2021 |
| Toshiba       | Satellite Pro L650          | [fd40a9d639](https://linux-hardware.org/?probe=fd40a9d639) | Dec 07, 2021 |
| HP            | Laptop 15s-eq1xxx           | [a61a3df5f9](https://linux-hardware.org/?probe=a61a3df5f9) | Dec 04, 2021 |
| Dell          | Vostro 3500                 | [3df309c91c](https://linux-hardware.org/?probe=3df309c91c) | Dec 03, 2021 |
| Fujitsu Si... | AMILO Li3910                | [6f355c1c73](https://linux-hardware.org/?probe=6f355c1c73) | Dec 01, 2021 |
| HP            | Laptop 14-ck0xxx            | [60a074698a](https://linux-hardware.org/?probe=60a074698a) | Dec 01, 2021 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [440d34a6b0](https://linux-hardware.org/?probe=440d34a6b0) | Nov 28, 2021 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [bb7b625409](https://linux-hardware.org/?probe=bb7b625409) | Nov 28, 2021 |
| ASUSTek       | N53SN                       | [67d66feb3e](https://linux-hardware.org/?probe=67d66feb3e) | Nov 20, 2021 |
| Acer          | Aspire ES1-533              | [14a4c57e27](https://linux-hardware.org/?probe=14a4c57e27) | Nov 05, 2021 |
| Lenovo        | G500 20236                  | [7708d61566](https://linux-hardware.org/?probe=7708d61566) | Nov 05, 2021 |
| eMachines     | eME440                      | [1427ebffb0](https://linux-hardware.org/?probe=1427ebffb0) | Oct 29, 2021 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | [f8024b89d4](https://linux-hardware.org/?probe=f8024b89d4) | Oct 28, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [d180cf6efc](https://linux-hardware.org/?probe=d180cf6efc) | Oct 23, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X1S... | [cb8bcc4d2d](https://linux-hardware.org/?probe=cb8bcc4d2d) | Oct 22, 2021 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | [a99866abc1](https://linux-hardware.org/?probe=a99866abc1) | Oct 21, 2021 |
| HP            | EliteBook 840 G3            | [650c91f4db](https://linux-hardware.org/?probe=650c91f4db) | Oct 18, 2021 |
| HP            | EliteBook 840 G3            | [5e28e542c2](https://linux-hardware.org/?probe=5e28e542c2) | Oct 17, 2021 |
| Dell          | Inspiron 3520               | [7eafd054fc](https://linux-hardware.org/?probe=7eafd054fc) | Oct 17, 2021 |
| HP            | Laptop 15s-eq2xxx           | [2e7ac4731f](https://linux-hardware.org/?probe=2e7ac4731f) | Oct 16, 2021 |
| Lenovo        | G555 0873                   | [a38f52851a](https://linux-hardware.org/?probe=a38f52851a) | Oct 05, 2021 |
| ASUSTek       | 1005PE                      | [bd2044749b](https://linux-hardware.org/?probe=bd2044749b) | Sep 22, 2021 |
| Acer          | Aspire V3-571G              | [b9fcdffa50](https://linux-hardware.org/?probe=b9fcdffa50) | Sep 22, 2021 |
| ASUSTek       | 1005PE                      | [02ccb36302](https://linux-hardware.org/?probe=02ccb36302) | Sep 21, 2021 |
| ASUSTek       | 1005PE                      | [081e791398](https://linux-hardware.org/?probe=081e791398) | Sep 19, 2021 |
| Toshiba       | Satellite C55-B             | [59a0efda89](https://linux-hardware.org/?probe=59a0efda89) | Sep 18, 2021 |
| ASUSTek       | 1005PE                      | [a3adf0356c](https://linux-hardware.org/?probe=a3adf0356c) | Sep 18, 2021 |
| Acer          | Aspire V3-571G              | [cedbbde363](https://linux-hardware.org/?probe=cedbbde363) | Sep 13, 2021 |
| Lenovo        | G500 20236                  | [f77883b614](https://linux-hardware.org/?probe=f77883b614) | Sep 07, 2021 |
| HP            | ProBook 4730s               | [36834479ab](https://linux-hardware.org/?probe=36834479ab) | Sep 03, 2021 |
| Apple         | MacBookPro8,1               | [da332ba09e](https://linux-hardware.org/?probe=da332ba09e) | Sep 01, 2021 |
| Dell          | Inspiron 3537               | [cad80329d8](https://linux-hardware.org/?probe=cad80329d8) | Aug 31, 2021 |
| Lenovo        | G500 20236                  | [60f43f8815](https://linux-hardware.org/?probe=60f43f8815) | Aug 29, 2021 |
| Dell          | Inspiron 5593               | [ebac51e403](https://linux-hardware.org/?probe=ebac51e403) | Aug 28, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [62c96ffa5b](https://linux-hardware.org/?probe=62c96ffa5b) | Aug 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [516b9ff2ed](https://linux-hardware.org/?probe=516b9ff2ed) | Aug 25, 2021 |
| Dell          | Inspiron 7520               | [056e1c0825](https://linux-hardware.org/?probe=056e1c0825) | Aug 21, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [79051f2400](https://linux-hardware.org/?probe=79051f2400) | Aug 19, 2021 |
| HP            | EliteBook 840 G5            | [4c196e1abd](https://linux-hardware.org/?probe=4c196e1abd) | Aug 18, 2021 |
| HP            | G62                         | [b6eeeba9d1](https://linux-hardware.org/?probe=b6eeeba9d1) | Aug 15, 2021 |
| HP            | G62                         | [4adea9bed4](https://linux-hardware.org/?probe=4adea9bed4) | Aug 14, 2021 |
| HP            | Pavilion g6                 | [df95184640](https://linux-hardware.org/?probe=df95184640) | Aug 02, 2021 |
| HP            | Pavilion g6                 | [0e0aaaac98](https://linux-hardware.org/?probe=0e0aaaac98) | Aug 02, 2021 |
| Toshiba       | Satellite Pro L650          | [10e8624257](https://linux-hardware.org/?probe=10e8624257) | Jul 27, 2021 |
| Toshiba       | Satellite C55-B             | [c703c827c6](https://linux-hardware.org/?probe=c703c827c6) | Jul 21, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b44e9be41b](https://linux-hardware.org/?probe=b44e9be41b) | Jul 19, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [56faa89619](https://linux-hardware.org/?probe=56faa89619) | Jul 16, 2021 |
| Lenovo        | V330-15IKB 81AX             | [70128f07ea](https://linux-hardware.org/?probe=70128f07ea) | Jul 13, 2021 |
| HP            | Compaq nx7400 (RU429EA#A... | [ce0542775b](https://linux-hardware.org/?probe=ce0542775b) | Jun 22, 2021 |
| Lenovo        | ThinkPad X201 Tablet 298... | [d04705eaef](https://linux-hardware.org/?probe=d04705eaef) | Jun 20, 2021 |
| ASUSTek       | G551JK                      | [aace05a48f](https://linux-hardware.org/?probe=aace05a48f) | Jun 17, 2021 |
| ASUSTek       | G551JK                      | [2947ae8fc2](https://linux-hardware.org/?probe=2947ae8fc2) | Jun 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [80b26a6c37](https://linux-hardware.org/?probe=80b26a6c37) | Jun 16, 2021 |
| Dell          | Inspiron 15-3567            | [8487e42c1e](https://linux-hardware.org/?probe=8487e42c1e) | Jun 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [18fd922adc](https://linux-hardware.org/?probe=18fd922adc) | Jun 10, 2021 |
| Dell          | Latitude 5520               | [45b3e7c2af](https://linux-hardware.org/?probe=45b3e7c2af) | Jun 06, 2021 |
| Dell          | Vostro 5402                 | [ec4c7c0192](https://linux-hardware.org/?probe=ec4c7c0192) | Jun 04, 2021 |
| MSI           | CR500                       | [76d2d77034](https://linux-hardware.org/?probe=76d2d77034) | Jun 03, 2021 |
| MSI           | CR500                       | [93f6fd0ae4](https://linux-hardware.org/?probe=93f6fd0ae4) | Jun 02, 2021 |
| MSI           | CR500                       | [b1d00d1444](https://linux-hardware.org/?probe=b1d00d1444) | May 30, 2021 |
| HP            | Notebook                    | [f60121b761](https://linux-hardware.org/?probe=f60121b761) | May 30, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [f794ea73e4](https://linux-hardware.org/?probe=f794ea73e4) | May 28, 2021 |
| Apple         | MacBookPro1,1               | [cc14c7fa2e](https://linux-hardware.org/?probe=cc14c7fa2e) | May 16, 2021 |
| HP            | ProBook 4530s               | [3d5a77511e](https://linux-hardware.org/?probe=3d5a77511e) | May 12, 2021 |
| Dell          | Vostro 5402                 | [03aa94f52f](https://linux-hardware.org/?probe=03aa94f52f) | May 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [b57920ccda](https://linux-hardware.org/?probe=b57920ccda) | May 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [19bf5a98df](https://linux-hardware.org/?probe=19bf5a98df) | May 10, 2021 |
| ASUSTek       | K53E                        | [314e6bbbd2](https://linux-hardware.org/?probe=314e6bbbd2) | May 04, 2021 |
| ASUSTek       | K53E                        | [9a34eba18a](https://linux-hardware.org/?probe=9a34eba18a) | May 03, 2021 |
| Fujitsu Si... | AMILO Pi 2512               | [bc0294a996](https://linux-hardware.org/?probe=bc0294a996) | May 03, 2021 |
| HP            | EliteBook 2540p             | [506fb4d003](https://linux-hardware.org/?probe=506fb4d003) | May 02, 2021 |
| Lenovo        | ThinkPad T440s 20ARS3B00... | [fa546522c1](https://linux-hardware.org/?probe=fa546522c1) | May 02, 2021 |
| Medion        | P6812                       | [a45bd7fc22](https://linux-hardware.org/?probe=a45bd7fc22) | Apr 19, 2021 |
| Acer          | Aspire A315-31              | [2b821447d2](https://linux-hardware.org/?probe=2b821447d2) | Apr 14, 2021 |
| Acer          | Aspire A315-31              | [e7a7c4b64f](https://linux-hardware.org/?probe=e7a7c4b64f) | Apr 14, 2021 |
| Acer          | Aspire A315-23              | [c7a0c1bf24](https://linux-hardware.org/?probe=c7a0c1bf24) | Apr 13, 2021 |
| HP            | Pavilion 15                 | [88ca55e5af](https://linux-hardware.org/?probe=88ca55e5af) | Apr 08, 2021 |
| Acer          | Aspire A515-51G             | [97f260c7d5](https://linux-hardware.org/?probe=97f260c7d5) | Mar 31, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [084a69a05a](https://linux-hardware.org/?probe=084a69a05a) | Mar 30, 2021 |
| Dell          | G5 5587                     | [862386a9b4](https://linux-hardware.org/?probe=862386a9b4) | Mar 27, 2021 |
| HP            | Laptop 15-db1xxx            | [59fb434d97](https://linux-hardware.org/?probe=59fb434d97) | Mar 21, 2021 |
| HP            | Laptop 15-db1xxx            | [aab4f11f05](https://linux-hardware.org/?probe=aab4f11f05) | Mar 21, 2021 |
| Dell          | Inspiron 3542               | [517406f8b6](https://linux-hardware.org/?probe=517406f8b6) | Mar 21, 2021 |
| HP            | ZBook 15 G3                 | [4ab4d49018](https://linux-hardware.org/?probe=4ab4d49018) | Mar 17, 2021 |
| HP            | Laptop 15-da1xxx            | [ed4ddd6238](https://linux-hardware.org/?probe=ed4ddd6238) | Mar 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [640a0a3857](https://linux-hardware.org/?probe=640a0a3857) | Mar 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [66de852009](https://linux-hardware.org/?probe=66de852009) | Mar 11, 2021 |
| Acer          | Aspire 5742G                | [659f9d690c](https://linux-hardware.org/?probe=659f9d690c) | Mar 10, 2021 |
| Dell          | Latitude E6320              | [a69653a323](https://linux-hardware.org/?probe=a69653a323) | Mar 08, 2021 |
| Acer          | Aspire 5735                 | [cde827bd2e](https://linux-hardware.org/?probe=cde827bd2e) | Mar 07, 2021 |
| Acer          | Aspire 5735                 | [9730b9273d](https://linux-hardware.org/?probe=9730b9273d) | Mar 07, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [7d5313fdad](https://linux-hardware.org/?probe=7d5313fdad) | Mar 06, 2021 |
| Toshiba       | Satellite L20               | [875478a51a](https://linux-hardware.org/?probe=875478a51a) | Mar 06, 2021 |
| HP            | ProBook 650 G1              | [e21aaf16e3](https://linux-hardware.org/?probe=e21aaf16e3) | Mar 03, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [a94321f4aa](https://linux-hardware.org/?probe=a94321f4aa) | Feb 27, 2021 |
| Dell          | Inspiron 7520               | [4611155200](https://linux-hardware.org/?probe=4611155200) | Feb 20, 2021 |
| HP            | ProBook 470 G3              | [12ef122267](https://linux-hardware.org/?probe=12ef122267) | Feb 19, 2021 |
| Dell          | Inspiron 3542               | [d77d8a8749](https://linux-hardware.org/?probe=d77d8a8749) | Feb 18, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [5843b21ecd](https://linux-hardware.org/?probe=5843b21ecd) | Feb 14, 2021 |
| HP            | ProBook 650 G1              | [2dcb1a408a](https://linux-hardware.org/?probe=2dcb1a408a) | Feb 13, 2021 |
| HP            | ProBook 650 G1              | [1d63d4f78d](https://linux-hardware.org/?probe=1d63d4f78d) | Feb 10, 2021 |
| Dell          | Latitude E5470              | [ac140ada48](https://linux-hardware.org/?probe=ac140ada48) | Feb 09, 2021 |
| Lenovo        | IdeaPad Y570 20091          | [e80a31db39](https://linux-hardware.org/?probe=e80a31db39) | Feb 03, 2021 |
| Dell          | Latitude E5470              | [72db68119a](https://linux-hardware.org/?probe=72db68119a) | Jan 27, 2021 |
| Dell          | Latitude E6430              | [b7f8906f0f](https://linux-hardware.org/?probe=b7f8906f0f) | Jan 27, 2021 |
| Lenovo        | IdeaPad Y570 20091          | [68fdde328b](https://linux-hardware.org/?probe=68fdde328b) | Jan 27, 2021 |
| HP            | EliteBook 8560p             | [875db98e08](https://linux-hardware.org/?probe=875db98e08) | Jan 23, 2021 |
| Acer          | Aspire 5736Z                | [6bb8df4de2](https://linux-hardware.org/?probe=6bb8df4de2) | Jan 21, 2021 |
| Lenovo        | Legion Y7000 2019 PG0 81... | [9f77ea6e17](https://linux-hardware.org/?probe=9f77ea6e17) | Jan 14, 2021 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [ab2decc440](https://linux-hardware.org/?probe=ab2decc440) | Jan 12, 2021 |
| Lenovo        | ThinkPad R400 2786W1L       | [5335da910d](https://linux-hardware.org/?probe=5335da910d) | Jan 10, 2021 |
| Lenovo        | ThinkPad R400 2786W1L       | [c7fbffcc09](https://linux-hardware.org/?probe=c7fbffcc09) | Jan 10, 2021 |
| Packard Be... | EasyNote TS11HR             | [ab603b2fe8](https://linux-hardware.org/?probe=ab603b2fe8) | Jan 06, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [7e0f5ef3ce](https://linux-hardware.org/?probe=7e0f5ef3ce) | Jan 04, 2021 |
| Toshiba       | Satellite C650              | [da33e577bf](https://linux-hardware.org/?probe=da33e577bf) | Jan 02, 2021 |
| Packard Be... | EasyNote TS11HR             | [343249d2da](https://linux-hardware.org/?probe=343249d2da) | Jan 02, 2021 |
| Toshiba       | Satellite C650              | [3ccf619144](https://linux-hardware.org/?probe=3ccf619144) | Dec 31, 2020 |
| ASUSTek       | X541NA                      | [ce08535027](https://linux-hardware.org/?probe=ce08535027) | Dec 25, 2020 |
| ASUSTek       | X541NA                      | [a026c30d04](https://linux-hardware.org/?probe=a026c30d04) | Dec 25, 2020 |
| HP            | Laptop 15-db0xxx            | [87ecbeb3f9](https://linux-hardware.org/?probe=87ecbeb3f9) | Dec 22, 2020 |
| Lenovo        | V330-15IKB 81AX             | [7bbfaa08a2](https://linux-hardware.org/?probe=7bbfaa08a2) | Dec 19, 2020 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [a3f26b77de](https://linux-hardware.org/?probe=a3f26b77de) | Dec 17, 2020 |
| Acer          | Aspire A315-31              | [3d19374493](https://linux-hardware.org/?probe=3d19374493) | Dec 17, 2020 |
| Dell          | XPS 13 9380                 | [1eae71a2dd](https://linux-hardware.org/?probe=1eae71a2dd) | Dec 14, 2020 |
| Acer          | Aspire A315-31              | [630a5fce15](https://linux-hardware.org/?probe=630a5fce15) | Dec 11, 2020 |
| Acer          | Aspire A715-75G             | [9c6b3be687](https://linux-hardware.org/?probe=9c6b3be687) | Dec 10, 2020 |
| Acer          | Aspire A717-71G             | [f355a859fe](https://linux-hardware.org/?probe=f355a859fe) | Dec 05, 2020 |
| Acer          | Aspire A717-71G             | [e0144299e5](https://linux-hardware.org/?probe=e0144299e5) | Dec 05, 2020 |
| Acer          | Aspire A715-75G             | [4d6f15896a](https://linux-hardware.org/?probe=4d6f15896a) | Dec 01, 2020 |
| Acer          | Aspire A715-75G             | [cea1efd2f4](https://linux-hardware.org/?probe=cea1efd2f4) | Dec 01, 2020 |
| Acer          | Aspire ES1-533              | [e20dc3c4e4](https://linux-hardware.org/?probe=e20dc3c4e4) | Nov 26, 2020 |
| Acer          | Aspire ES1-533              | [1ff481eb22](https://linux-hardware.org/?probe=1ff481eb22) | Nov 26, 2020 |
| Lenovo        | V15-ADA 82C7                | [c25d3746ee](https://linux-hardware.org/?probe=c25d3746ee) | Nov 24, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [b59cef94de](https://linux-hardware.org/?probe=b59cef94de) | Nov 22, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [cb540754ed](https://linux-hardware.org/?probe=cb540754ed) | Nov 22, 2020 |
| MSI           | CR610                       | [8e7bf69342](https://linux-hardware.org/?probe=8e7bf69342) | Nov 22, 2020 |
| MSI           | CR610                       | [ba50d62533](https://linux-hardware.org/?probe=ba50d62533) | Nov 22, 2020 |
| Dell          | Inspiron 3541               | [f10a3f7947](https://linux-hardware.org/?probe=f10a3f7947) | Nov 21, 2020 |
| Dell          | Inspiron 3541               | [28a2250b7c](https://linux-hardware.org/?probe=28a2250b7c) | Nov 21, 2020 |
| Lenovo        | V130-14IGM 81HM             | [e282aa9ff3](https://linux-hardware.org/?probe=e282aa9ff3) | Nov 20, 2020 |
| Lenovo        | V15-ADA 82C7                | [aa224b81ef](https://linux-hardware.org/?probe=aa224b81ef) | Nov 18, 2020 |
| HP            | Laptop 15-da0xxx            | [2cc03df5d0](https://linux-hardware.org/?probe=2cc03df5d0) | Nov 16, 2020 |
| HP            | Pavilion Notebook           | [c68070f9b3](https://linux-hardware.org/?probe=c68070f9b3) | Nov 10, 2020 |
| HP            | Pavilion Notebook           | [99e25d58ad](https://linux-hardware.org/?probe=99e25d58ad) | Nov 10, 2020 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [9555e785bb](https://linux-hardware.org/?probe=9555e785bb) | Nov 09, 2020 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [0de6c928a4](https://linux-hardware.org/?probe=0de6c928a4) | Nov 09, 2020 |
| Lenovo        | V130-14IGM 81HM             | [23fd9c7140](https://linux-hardware.org/?probe=23fd9c7140) | Nov 09, 2020 |
| Dell          | Inspiron 1720               | [d2018981ad](https://linux-hardware.org/?probe=d2018981ad) | Nov 05, 2020 |
| Lenovo        | V330-15IKB 81AX             | [c6872a9a60](https://linux-hardware.org/?probe=c6872a9a60) | Nov 03, 2020 |
| ASUSTek       | X541NA                      | [a3067761af](https://linux-hardware.org/?probe=a3067761af) | Oct 18, 2020 |
| ASUSTek       | X541NA                      | [baf94800b6](https://linux-hardware.org/?probe=baf94800b6) | Oct 18, 2020 |
| Lenovo        | 3000 N200 0769BNG           | [233a47535c](https://linux-hardware.org/?probe=233a47535c) | Oct 15, 2020 |
| ASUSTek       | TUF Gaming FA506II_FA506... | [9356879a60](https://linux-hardware.org/?probe=9356879a60) | Oct 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [4ccef20bb6](https://linux-hardware.org/?probe=4ccef20bb6) | Oct 13, 2020 |
| Lenovo        | 3000 N200 0769BNG           | [8ea03b6d29](https://linux-hardware.org/?probe=8ea03b6d29) | Oct 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [43c0586dbe](https://linux-hardware.org/?probe=43c0586dbe) | Oct 12, 2020 |
| Acer          | Aspire A315-31              | [00686fcd7b](https://linux-hardware.org/?probe=00686fcd7b) | Oct 12, 2020 |
| Dell          | Latitude E5470              | [a1ae53e261](https://linux-hardware.org/?probe=a1ae53e261) | Oct 06, 2020 |
| Acer          | Aspire A515-55              | [d88d774f7f](https://linux-hardware.org/?probe=d88d774f7f) | Oct 05, 2020 |
| Lenovo        | B50-45 20388                | [c25c3ef2d8](https://linux-hardware.org/?probe=c25c3ef2d8) | Oct 05, 2020 |
| Lenovo        | B50-45 20388                | [e3d174f961](https://linux-hardware.org/?probe=e3d174f961) | Oct 05, 2020 |
| Lenovo        | V330-15IKB 81AX             | [cb2c394f1a](https://linux-hardware.org/?probe=cb2c394f1a) | Oct 02, 2020 |
| HP            | Notebook                    | [9fcfc67d9c](https://linux-hardware.org/?probe=9fcfc67d9c) | Sep 29, 2020 |
| Lenovo        | V330-15IKB 81AX             | [1734ca75eb](https://linux-hardware.org/?probe=1734ca75eb) | Sep 29, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0KK0... | [d231920967](https://linux-hardware.org/?probe=d231920967) | Sep 28, 2020 |
| HP            | 355 G2                      | [07981744ab](https://linux-hardware.org/?probe=07981744ab) | Sep 27, 2020 |
| HP            | 355 G2                      | [08e4ab3c53](https://linux-hardware.org/?probe=08e4ab3c53) | Sep 26, 2020 |
| Lenovo        | V330-15IKB 81AX             | [a34c376304](https://linux-hardware.org/?probe=a34c376304) | Sep 18, 2020 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [20c5e9395d](https://linux-hardware.org/?probe=20c5e9395d) | Sep 16, 2020 |
| Toshiba       | QOSMIO F50                  | [b60fe2f9e5](https://linux-hardware.org/?probe=b60fe2f9e5) | Sep 16, 2020 |
| HP            | Laptop 17-by2xxx            | [d3fcaecf43](https://linux-hardware.org/?probe=d3fcaecf43) | Sep 12, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [eea494974a](https://linux-hardware.org/?probe=eea494974a) | Sep 11, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [00956078a0](https://linux-hardware.org/?probe=00956078a0) | Sep 03, 2020 |
| Acer          | AOA150                      | [d7397a31d7](https://linux-hardware.org/?probe=d7397a31d7) | Aug 31, 2020 |
| Dell          | Inspiron 3593               | [2c97a34461](https://linux-hardware.org/?probe=2c97a34461) | Aug 20, 2020 |
| HP            | 530 Notebook PC(GU327AA#... | [55d79e4d6a](https://linux-hardware.org/?probe=55d79e4d6a) | Aug 17, 2020 |
| HP            | 530 Notebook PC(GU327AA#... | [19b6cecfad](https://linux-hardware.org/?probe=19b6cecfad) | Aug 17, 2020 |
| Lenovo        | ThinkPad T480 20L6S43212    | [e408e4045b](https://linux-hardware.org/?probe=e408e4045b) | Aug 16, 2020 |
| Dell          | Inspiron 5577               | [f10ef91563](https://linux-hardware.org/?probe=f10ef91563) | Aug 06, 2020 |
| MSI           | CR500                       | [a347574891](https://linux-hardware.org/?probe=a347574891) | Aug 03, 2020 |
| MSI           | CR500                       | [21b1264f8c](https://linux-hardware.org/?probe=21b1264f8c) | Aug 03, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [a2dd413553](https://linux-hardware.org/?probe=a2dd413553) | Jul 26, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [e1073052d4](https://linux-hardware.org/?probe=e1073052d4) | Jul 26, 2020 |
| HP            | ProBook 450 G1              | [8db5efa1fc](https://linux-hardware.org/?probe=8db5efa1fc) | Jul 22, 2020 |
| Acer          | Aspire A315-42              | [b5aacd7b39](https://linux-hardware.org/?probe=b5aacd7b39) | Jul 12, 2020 |
| Acer          | Aspire A315-42              | [88afcfbe5b](https://linux-hardware.org/?probe=88afcfbe5b) | Jul 11, 2020 |
| Lenovo        | V110-15AST 80TD             | [6a86c949a2](https://linux-hardware.org/?probe=6a86c949a2) | Jul 10, 2020 |
| Acer          | Aspire A315-31              | [3ab4bed99e](https://linux-hardware.org/?probe=3ab4bed99e) | Jul 05, 2020 |
| Acer          | Aspire E1-531               | [7baad79bd7](https://linux-hardware.org/?probe=7baad79bd7) | Jul 04, 2020 |
| Lenovo        | V110-15AST 80TD             | [16211b52a1](https://linux-hardware.org/?probe=16211b52a1) | Jun 25, 2020 |
| Sony          | VPCZ21X9E                   | [72e4be4ea5](https://linux-hardware.org/?probe=72e4be4ea5) | Jun 12, 2020 |
| Sony          | VPCZ21X9E                   | [26affa7385](https://linux-hardware.org/?probe=26affa7385) | Jun 12, 2020 |
| Apple         | MacBook5,1                  | [099f5faf14](https://linux-hardware.org/?probe=099f5faf14) | Jun 02, 2020 |
| ASUSTek       | N550JX                      | [99693da42c](https://linux-hardware.org/?probe=99693da42c) | May 31, 2020 |
| Dell          | Inspiron 5559               | [3eee5b1f3d](https://linux-hardware.org/?probe=3eee5b1f3d) | May 31, 2020 |
| HP            | 250 G5 Notebook PC          | [1a72632c64](https://linux-hardware.org/?probe=1a72632c64) | May 27, 2020 |
| Lenovo        | V330-15IKB 81AX             | [c4087d6c6a](https://linux-hardware.org/?probe=c4087d6c6a) | May 21, 2020 |
| ASUSTek       | K50AB                       | [96ccf326a8](https://linux-hardware.org/?probe=96ccf326a8) | May 19, 2020 |
| Dell          | Inspiron N5010              | [f1e4f13c21](https://linux-hardware.org/?probe=f1e4f13c21) | May 18, 2020 |
| Lenovo        | V310-15ISK 80SY             | [a608769eb0](https://linux-hardware.org/?probe=a608769eb0) | May 15, 2020 |
| Lenovo        | ThinkPad T460 20FNS0KT00    | [92e676e189](https://linux-hardware.org/?probe=92e676e189) | May 15, 2020 |
| Lenovo        | ThinkPad T460 20FNS0KT00    | [b7fd9a70e0](https://linux-hardware.org/?probe=b7fd9a70e0) | May 15, 2020 |
| ASUSTek       | G551JK                      | [1d29493d79](https://linux-hardware.org/?probe=1d29493d79) | May 14, 2020 |
| ASUSTek       | G551JK                      | [2aa55f08d0](https://linux-hardware.org/?probe=2aa55f08d0) | May 14, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [03ba757adf](https://linux-hardware.org/?probe=03ba757adf) | May 13, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [dadd9d2790](https://linux-hardware.org/?probe=dadd9d2790) | May 12, 2020 |
| HP            | ZBook 15 G3                 | [3474070eb8](https://linux-hardware.org/?probe=3474070eb8) | May 10, 2020 |
| Lenovo        | G50-30 80G0                 | [4ac3289ec9](https://linux-hardware.org/?probe=4ac3289ec9) | May 09, 2020 |
| ASUSTek       | K54C                        | [3188c4843a](https://linux-hardware.org/?probe=3188c4843a) | May 08, 2020 |
| Dell          | Inspiron 5567               | [099e174bf4](https://linux-hardware.org/?probe=099e174bf4) | May 07, 2020 |
| Lenovo        | ThinkPad L470 20J5S4RS00    | [b646e36068](https://linux-hardware.org/?probe=b646e36068) | May 04, 2020 |
| Dell          | Inspiron 3537               | [a26c6f5812](https://linux-hardware.org/?probe=a26c6f5812) | Apr 21, 2020 |
| HP            | 250 G5 Notebook PC          | [01f3f0f185](https://linux-hardware.org/?probe=01f3f0f185) | Apr 14, 2020 |
| Lenovo        | ThinkPad E560 20EV003EMS    | [0b978ac786](https://linux-hardware.org/?probe=0b978ac786) | Apr 14, 2020 |
| HP            | ZBook 15 G3                 | [16ee557e51](https://linux-hardware.org/?probe=16ee557e51) | Apr 12, 2020 |
| HP            | Mini 110-3100               | [a32c0db8bb](https://linux-hardware.org/?probe=a32c0db8bb) | Apr 11, 2020 |
| Acer          | Aspire 7520G                | [d5bc992097](https://linux-hardware.org/?probe=d5bc992097) | Apr 04, 2020 |
| Toshiba       | TECRA Z50-A                 | [889a5aa1a6](https://linux-hardware.org/?probe=889a5aa1a6) | Apr 02, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [cb84e8c9af](https://linux-hardware.org/?probe=cb84e8c9af) | Mar 23, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [8670fa919e](https://linux-hardware.org/?probe=8670fa919e) | Mar 23, 2020 |
| ASUSTek       | X541NC                      | [63b197a2c0](https://linux-hardware.org/?probe=63b197a2c0) | Mar 21, 2020 |
| Fujitsu Si... | AMILO Li3710                | [11ebf93798](https://linux-hardware.org/?probe=11ebf93798) | Mar 18, 2020 |
| Lenovo        | Yoga 300-11IBR 80M1         | [b19ba42878](https://linux-hardware.org/?probe=b19ba42878) | Mar 17, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [334884c294](https://linux-hardware.org/?probe=334884c294) | Mar 10, 2020 |
| HP            | 250 G1                      | [7a7e2dfcee](https://linux-hardware.org/?probe=7a7e2dfcee) | Mar 10, 2020 |
| HP            | 250 G4                      | [d8b2caab0f](https://linux-hardware.org/?probe=d8b2caab0f) | Mar 08, 2020 |
| Acer          | Aspire A315-41              | [5870ecc433](https://linux-hardware.org/?probe=5870ecc433) | Mar 08, 2020 |
| Acer          | Aspire E3-112               | [62041aa7fa](https://linux-hardware.org/?probe=62041aa7fa) | Mar 08, 2020 |
| Lenovo        | ThinkPad T500 2056W2J       | [1923e28174](https://linux-hardware.org/?probe=1923e28174) | Mar 05, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [bda2f29230](https://linux-hardware.org/?probe=bda2f29230) | Feb 24, 2020 |
| Fujitsu       | LIFEBOOK AH530              | [5d93dd0911](https://linux-hardware.org/?probe=5d93dd0911) | Feb 20, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [eb55029938](https://linux-hardware.org/?probe=eb55029938) | Feb 18, 2020 |
| ASUSTek       | X551MA                      | [530fb26de2](https://linux-hardware.org/?probe=530fb26de2) | Feb 16, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [4d942fa22c](https://linux-hardware.org/?probe=4d942fa22c) | Feb 10, 2020 |
| ASUSTek       | X541UVK                     | [9e44db3513](https://linux-hardware.org/?probe=9e44db3513) | Feb 06, 2020 |
| Lenovo        | G505 20240                  | [3208a023bf](https://linux-hardware.org/?probe=3208a023bf) | Feb 04, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [91bdd7eccf](https://linux-hardware.org/?probe=91bdd7eccf) | Feb 01, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a4a64dfa74](https://linux-hardware.org/?probe=a4a64dfa74) | Feb 01, 2020 |
| Acer          | Aspire E1-530               | [0e64af354b](https://linux-hardware.org/?probe=0e64af354b) | Jan 30, 2020 |
| Acer          | Swift SF314-56              | [303332d310](https://linux-hardware.org/?probe=303332d310) | Jan 29, 2020 |
| Toshiba       | Satellite C50-B             | [06c487df1d](https://linux-hardware.org/?probe=06c487df1d) | Jan 28, 2020 |
| Acer          | Aspire A315-31              | [b482e7ef86](https://linux-hardware.org/?probe=b482e7ef86) | Jan 25, 2020 |
| Lenovo        | ThinkPad T520 42406AG       | [7de4fdce8d](https://linux-hardware.org/?probe=7de4fdce8d) | Jan 23, 2020 |
| Lenovo        | V330-15IKB 81AX             | [b0d2c5611e](https://linux-hardware.org/?probe=b0d2c5611e) | Jan 22, 2020 |
| HP            | Compaq nc6320 (RU381ES#A... | [d3a7e386ae](https://linux-hardware.org/?probe=d3a7e386ae) | Jan 16, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [84bf577e7d](https://linux-hardware.org/?probe=84bf577e7d) | Jan 16, 2020 |
| Acer          | Aspire A315-31              | [36dcda44ba](https://linux-hardware.org/?probe=36dcda44ba) | Jan 15, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [cc4a9ba559](https://linux-hardware.org/?probe=cc4a9ba559) | Jan 15, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [72f2c4c12a](https://linux-hardware.org/?probe=72f2c4c12a) | Jan 15, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b5d63aec77](https://linux-hardware.org/?probe=b5d63aec77) | Jan 15, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [7d389b1fcb](https://linux-hardware.org/?probe=7d389b1fcb) | Jan 15, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | [b2c0da1b44](https://linux-hardware.org/?probe=b2c0da1b44) | Jan 12, 2020 |
| HP            | ProBook 650 G1              | [224d2a830f](https://linux-hardware.org/?probe=224d2a830f) | Jan 08, 2020 |
| ASUSTek       | X55A                        | [3482727e9f](https://linux-hardware.org/?probe=3482727e9f) | Jan 03, 2020 |
| Lenovo        | ThinkPad P50 20EQS1AC00     | [0767220809](https://linux-hardware.org/?probe=0767220809) | Jan 03, 2020 |
| Dell          | Inspiron 3558               | [63be3850f8](https://linux-hardware.org/?probe=63be3850f8) | Dec 31, 2019 |
| Acer          | Aspire A315-51              | [fb858f1586](https://linux-hardware.org/?probe=fb858f1586) | Dec 30, 2019 |
| Acer          | Aspire A315-51              | [0dfa591b1c](https://linux-hardware.org/?probe=0dfa591b1c) | Dec 30, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [dfac3d950c](https://linux-hardware.org/?probe=dfac3d950c) | Dec 29, 2019 |
| Samsung       | N250P/N145P                 | [708195d4f1](https://linux-hardware.org/?probe=708195d4f1) | Dec 27, 2019 |
| Toshiba       | Satellite C850-1H6          | [a0ffb29c6c](https://linux-hardware.org/?probe=a0ffb29c6c) | Dec 18, 2019 |
| HP            | ProBook 640 G1              | [0813940da0](https://linux-hardware.org/?probe=0813940da0) | Dec 09, 2019 |
| Lenovo        | IdeaPad L340-15API 81LW     | [3193d44169](https://linux-hardware.org/?probe=3193d44169) | Dec 04, 2019 |
| ASUSTek       | X550MJ                      | [3fde87c7b4](https://linux-hardware.org/?probe=3fde87c7b4) | Dec 04, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [8a33af729e](https://linux-hardware.org/?probe=8a33af729e) | Dec 03, 2019 |
| Acer          | Aspire A315-51              | [77affe222c](https://linux-hardware.org/?probe=77affe222c) | Nov 16, 2019 |
| HP            | Notebook                    | [8df47391f9](https://linux-hardware.org/?probe=8df47391f9) | Nov 15, 2019 |
| Acer          | Aspire A315-31              | [3812d4729c](https://linux-hardware.org/?probe=3812d4729c) | Nov 14, 2019 |
| HP            | Notebook                    | [fe0316d8bb](https://linux-hardware.org/?probe=fe0316d8bb) | Nov 14, 2019 |
| Lenovo        | ThinkPad T420s 4174BB2      | [53037be14e](https://linux-hardware.org/?probe=53037be14e) | Nov 03, 2019 |
| Lenovo        | ThinkPad Edge E330 33544... | [c27afaa8d2](https://linux-hardware.org/?probe=c27afaa8d2) | Oct 20, 2019 |
| Acer          | Aspire 5350                 | [bfca910110](https://linux-hardware.org/?probe=bfca910110) | Oct 20, 2019 |
| Lenovo        | ThinkPad Edge E330 33544... | [0e391bc5f7](https://linux-hardware.org/?probe=0e391bc5f7) | Oct 20, 2019 |
| HP            | ProBook 650 G1              | [4886df0de1](https://linux-hardware.org/?probe=4886df0de1) | Oct 20, 2019 |
| Acer          | Aspire 5350                 | [6c1a1b4cd5](https://linux-hardware.org/?probe=6c1a1b4cd5) | Oct 19, 2019 |
| Dell          | Latitude 5580               | [e2d5fd3182](https://linux-hardware.org/?probe=e2d5fd3182) | Oct 18, 2019 |
| Dell          | Latitude 5580               | [fbb2c68803](https://linux-hardware.org/?probe=fbb2c68803) | Oct 18, 2019 |
| Dell          | Latitude 5580               | [4ba29dd71c](https://linux-hardware.org/?probe=4ba29dd71c) | Oct 18, 2019 |
| Acer          | Aspire A315-31              | [2ab608ac7e](https://linux-hardware.org/?probe=2ab608ac7e) | Oct 13, 2019 |
| HP            | Pavilion Notebook           | [dffd6ce6cb](https://linux-hardware.org/?probe=dffd6ce6cb) | Oct 13, 2019 |
| Lenovo        | IdeaPad S540-14API 81NH     | [d0671b5d7f](https://linux-hardware.org/?probe=d0671b5d7f) | Oct 12, 2019 |
| Acer          | Aspire A717-71G             | [4bad7bd17c](https://linux-hardware.org/?probe=4bad7bd17c) | Sep 21, 2019 |
| Lenovo        | ThinkPad T520 42406AG       | [3e835a3fea](https://linux-hardware.org/?probe=3e835a3fea) | Sep 15, 2019 |
| Razer         | Blade                       | [da397f901b](https://linux-hardware.org/?probe=da397f901b) | Sep 10, 2019 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [655aa5059b](https://linux-hardware.org/?probe=655aa5059b) | Sep 04, 2019 |
| HP            | Laptop 15-ra0xx             | [2e41137334](https://linux-hardware.org/?probe=2e41137334) | Sep 03, 2019 |
| HP            | Laptop 15-ra0xx             | [8aadf9c34a](https://linux-hardware.org/?probe=8aadf9c34a) | Sep 02, 2019 |
| HP            | Laptop 15-ra0xx             | [96e535cece](https://linux-hardware.org/?probe=96e535cece) | Sep 02, 2019 |
| Acer          | Aspire A315-31              | [9d8698e977](https://linux-hardware.org/?probe=9d8698e977) | Aug 28, 2019 |
| Acer          | Aspire A315-31              | [95dba17d9a](https://linux-hardware.org/?probe=95dba17d9a) | Aug 17, 2019 |
| Dell          | Precision 7730              | [b9281326d7](https://linux-hardware.org/?probe=b9281326d7) | Jul 25, 2019 |
| ASUSTek       | X201EP                      | [a1a1f1965a](https://linux-hardware.org/?probe=a1a1f1965a) | Jul 22, 2019 |
| Dell          | Latitude E5440              | [f40c3d18fb](https://linux-hardware.org/?probe=f40c3d18fb) | Jul 19, 2019 |
| Lenovo        | ThinkPad P51 20HHS04800     | [4013dc5bc1](https://linux-hardware.org/?probe=4013dc5bc1) | Jul 16, 2019 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [1613715663](https://linux-hardware.org/?probe=1613715663) | Jul 15, 2019 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [62ebee4d1f](https://linux-hardware.org/?probe=62ebee4d1f) | Jul 15, 2019 |
| ASUSTek       | X541NA                      | [5fdb751780](https://linux-hardware.org/?probe=5fdb751780) | Jul 11, 2019 |
| ASUSTek       | X541NA                      | [8676bfc466](https://linux-hardware.org/?probe=8676bfc466) | Jul 11, 2019 |
| HP            | Laptop 15-ra0xx             | [f28399b983](https://linux-hardware.org/?probe=f28399b983) | Jul 09, 2019 |
| Toshiba       | Satellite L755              | [e2413cea5d](https://linux-hardware.org/?probe=e2413cea5d) | Jul 06, 2019 |
| HP            | 250 G6 Notebook PC          | [7d8551e612](https://linux-hardware.org/?probe=7d8551e612) | Jun 29, 2019 |
| Lenovo        | G500 20236                  | [4faa6112c3](https://linux-hardware.org/?probe=4faa6112c3) | Jun 28, 2019 |
| HP            | Laptop 15-db0xxx            | [df6f074dbd](https://linux-hardware.org/?probe=df6f074dbd) | Jun 11, 2019 |
| IBM           | ThinkPad R52p 1847W5R       | [1dc1d8e6f2](https://linux-hardware.org/?probe=1dc1d8e6f2) | Jun 09, 2019 |
| HP            | Unknown                     | [cf3a7ad203](https://linux-hardware.org/?probe=cf3a7ad203) | Jun 05, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | [f1a85fe5ba](https://linux-hardware.org/?probe=f1a85fe5ba) | Jun 05, 2019 |
| HP            | Pavilion Notebook           | [ad610739b6](https://linux-hardware.org/?probe=ad610739b6) | Jun 01, 2019 |
| HP            | Pavilion Notebook           | [476f3cfb4a](https://linux-hardware.org/?probe=476f3cfb4a) | May 26, 2019 |
| Acer          | Aspire A717-71G             | [882e32aaf7](https://linux-hardware.org/?probe=882e32aaf7) | May 21, 2019 |
| Dell          | Inspiron 5567               | [29fadee02e](https://linux-hardware.org/?probe=29fadee02e) | May 19, 2019 |
| Lenovo        | V330-15IKB 81AX             | [8f1cfe4955](https://linux-hardware.org/?probe=8f1cfe4955) | May 17, 2019 |
| HP            | 250 G1                      | [4550b3fdf6](https://linux-hardware.org/?probe=4550b3fdf6) | May 17, 2019 |
| HP            | 250 G1                      | [7dda48b144](https://linux-hardware.org/?probe=7dda48b144) | May 17, 2019 |
| ASUSTek       | X541SA                      | [dff8b29714](https://linux-hardware.org/?probe=dff8b29714) | May 10, 2019 |
| ASUSTek       | X541SA                      | [308cc99aee](https://linux-hardware.org/?probe=308cc99aee) | May 10, 2019 |
| ASUSTek       | X541SA                      | [f03f0840fb](https://linux-hardware.org/?probe=f03f0840fb) | May 10, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [8195906a99](https://linux-hardware.org/?probe=8195906a99) | May 06, 2019 |
| Acer          | Aspire E1-530               | [e5658355fa](https://linux-hardware.org/?probe=e5658355fa) | May 03, 2019 |
| LG Electro... | LW70-JJKG                   | [76f306de39](https://linux-hardware.org/?probe=76f306de39) | Apr 27, 2019 |
| Dell          | G3 3779                     | [8407de048a](https://linux-hardware.org/?probe=8407de048a) | Apr 26, 2019 |
| Acer          | Aspire A717-71G             | [7385402cb8](https://linux-hardware.org/?probe=7385402cb8) | Apr 25, 2019 |
| ASUSTek       | X541NC                      | [50aeeec380](https://linux-hardware.org/?probe=50aeeec380) | Apr 19, 2019 |
| ASUSTek       | X541NC                      | [5278c50f95](https://linux-hardware.org/?probe=5278c50f95) | Apr 13, 2019 |
| Fujitsu Si... | AMILO PRO V3515             | [1d96b8f60d](https://linux-hardware.org/?probe=1d96b8f60d) | Apr 11, 2019 |
| ASUSTek       | X541NA                      | [b94a9e24c1](https://linux-hardware.org/?probe=b94a9e24c1) | Apr 07, 2019 |
| Toshiba       | Satellite C870-17H          | [dc2ce35421](https://linux-hardware.org/?probe=dc2ce35421) | Apr 06, 2019 |
| Acer          | Aspire A717-71G             | [600ac82384](https://linux-hardware.org/?probe=600ac82384) | Mar 30, 2019 |
| Acer          | Aspire 6935                 | [d8a5d80999](https://linux-hardware.org/?probe=d8a5d80999) | Mar 23, 2019 |
| Dell          | Inspiron N5110              | [5137b5b274](https://linux-hardware.org/?probe=5137b5b274) | Mar 21, 2019 |
| HP            | Pavilion dv5                | [3f857e2920](https://linux-hardware.org/?probe=3f857e2920) | Mar 18, 2019 |
| ASUSTek       | X550MD                      | [4e37ad043d](https://linux-hardware.org/?probe=4e37ad043d) | Mar 14, 2019 |
| Sony          | VGN-FE31Z                   | [860dcaf74d](https://linux-hardware.org/?probe=860dcaf74d) | Feb 16, 2019 |
| Dell          | Precision M4600             | [6f6a52607b](https://linux-hardware.org/?probe=6f6a52607b) | Feb 14, 2019 |
| ASUSTek       | X540LA                      | [03ab6a3cd8](https://linux-hardware.org/?probe=03ab6a3cd8) | Feb 11, 2019 |
| Acer          | Aspire A315-21              | [b28972ad25](https://linux-hardware.org/?probe=b28972ad25) | Feb 10, 2019 |
| MSI           | MS-16Y1                     | [a676d0126f](https://linux-hardware.org/?probe=a676d0126f) | Feb 07, 2019 |
| ASUSTek       | X540LA                      | [a7cb02a6fb](https://linux-hardware.org/?probe=a7cb02a6fb) | Feb 02, 2019 |
| ASUSTek       | X540LA                      | [18752af5af](https://linux-hardware.org/?probe=18752af5af) | Jan 31, 2019 |
| ASUSTek       | X540LA                      | [dea612f99d](https://linux-hardware.org/?probe=dea612f99d) | Jan 31, 2019 |
| ASUSTek       | X541NA                      | [d66eb82eac](https://linux-hardware.org/?probe=d66eb82eac) | Jan 23, 2019 |
| ASUSTek       | K55DR                       | [13a17add51](https://linux-hardware.org/?probe=13a17add51) | Jan 22, 2019 |
| Acer          | Aspire ES1-532G             | [af17a54207](https://linux-hardware.org/?probe=af17a54207) | Jan 12, 2019 |
| ASUSTek       | X541NA                      | [53fba97f8a](https://linux-hardware.org/?probe=53fba97f8a) | Jan 04, 2019 |
| ASUSTek       | X541NA                      | [a0cb966487](https://linux-hardware.org/?probe=a0cb966487) | Jan 04, 2019 |
| Acer          | Aspire A717-71G             | [c3edad77d8](https://linux-hardware.org/?probe=c3edad77d8) | Dec 24, 2018 |
| Acer          | Aspire A315-21              | [9289091c83](https://linux-hardware.org/?probe=9289091c83) | Nov 28, 2018 |
| Acer          | Aspire A717-71G             | [3c22bb7c43](https://linux-hardware.org/?probe=3c22bb7c43) | Nov 04, 2018 |
| Acer          | Aspire A717-71G             | [65968eaade](https://linux-hardware.org/?probe=65968eaade) | Nov 01, 2018 |
| HP            | 15                          | [a6c00a0fde](https://linux-hardware.org/?probe=a6c00a0fde) | Jul 08, 2018 |
| HP            | 250 G5 Notebook PC          | [24f9e4ee20](https://linux-hardware.org/?probe=24f9e4ee20) | Jun 24, 2018 |
| HP            | Pavilion dv7                | [566fa1aed1](https://linux-hardware.org/?probe=566fa1aed1) | Feb 24, 2018 |
| HP            | ProBook 650 G1              | [b0a5c81710](https://linux-hardware.org/?probe=b0a5c81710) | Jan 24, 2018 |
| HP            | 250 G5 Notebook PC          | [c939de9629](https://linux-hardware.org/?probe=c939de9629) | Dec 17, 2017 |
| Toshiba       | Satellite C50-A-1G3         | [4d2b35494b](https://linux-hardware.org/?probe=4d2b35494b) | Dec 16, 2017 |
| HP            | 15                          | [93985df093](https://linux-hardware.org/?probe=93985df093) | Sep 26, 2017 |
| Dell          | Inspiron 7520               | [3b5516e47b](https://linux-hardware.org/?probe=3b5516e47b) | Aug 27, 2017 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | [5ab0f522c2](https://linux-hardware.org/?probe=5ab0f522c2) | Aug 19, 2017 |
| Lenovo        | G560 20042                  | [6f5d9b39bb](https://linux-hardware.org/?probe=6f5d9b39bb) | May 09, 2017 |
| ASUSTek       | K55VD                       | [5fecb30529](https://linux-hardware.org/?probe=5fecb30529) | Jan 08, 2017 |
| ASUSTek       | K55VD                       | [f9af076683](https://linux-hardware.org/?probe=f9af076683) | Jan 07, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Serbia/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 43        | 9.73%   |
| Ubuntu 18.04                 | 31        | 7.01%   |
| Ubuntu 22.04                 | 29        | 6.56%   |
| OpenMandriva 4.3             | 11        | 2.49%   |
| Pop!_OS 22.04                | 10        | 2.26%   |
| Zorin 15                     | 9         | 2.04%   |
| BlackPanther 18.1            | 9         | 2.04%   |
| ROSA R11                     | 8         | 1.81%   |
| Arch                         | 8         | 1.81%   |
| Ubuntu 19.10                 | 7         | 1.58%   |
| OpenMandriva 23.01           | 7         | 1.58%   |
| Linux Mint 19.3              | 7         | 1.58%   |
| OpenMandriva 4.2             | 6         | 1.36%   |
| Linux Mint 20.3              | 6         | 1.36%   |
| Fedora 37                    | 6         | 1.36%   |
| Zorin 16                     | 5         | 1.13%   |
| Ubuntu 21.10                 | 5         | 1.13%   |
| Ubuntu 18.10                 | 5         | 1.13%   |
| ROSA R10                     | 5         | 1.13%   |
| KDE neon 20.04               | 5         | 1.13%   |
| ArcoLinux Rolling            | 5         | 1.13%   |
| Arch Rolling                 | 5         | 1.13%   |
| ROSA R11.1                   | 4         | 0.9%    |
| Pop!_OS 21.04                | 4         | 0.9%    |
| openSUSE Tumbleweed-XXXXXXXX | 4         | 0.9%    |
| MX 21                        | 4         | 0.9%    |
| Linux Mint 21.1              | 4         | 0.9%    |
| Kubuntu 22.04                | 4         | 0.9%    |
| Fedora 34                    | 4         | 0.9%    |
| Xubuntu 20.04                | 3         | 0.68%   |
| Ubuntu 23.04                 | 3         | 0.68%   |
| Ubuntu 21.04                 | 3         | 0.68%   |
| Ubuntu 19.04                 | 3         | 0.68%   |
| ROSA R9                      | 3         | 0.68%   |
| ROSA 12.2                    | 3         | 0.68%   |
| Manjaro                      | 3         | 0.68%   |
| Linux Mint 21                | 3         | 0.68%   |
| Linux Mint 20.2              | 3         | 0.68%   |
| Linux Mint 20.1              | 3         | 0.68%   |
| Kubuntu 20.04                | 3         | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 134       | 32.68%  |
| Endless       | 31        | 7.56%   |
| OpenMandriva  | 28        | 6.83%   |
| Linux Mint    | 28        | 6.83%   |
| ROSA          | 22        | 5.37%   |
| Fedora        | 22        | 5.37%   |
| Pop!_OS       | 18        | 4.39%   |
| Zorin         | 15        | 3.66%   |
| Manjaro       | 13        | 3.17%   |
| Arch          | 13        | 3.17%   |
| BlackPanther  | 10        | 2.44%   |
| Kubuntu       | 9         | 2.2%    |
| KDE neon      | 8         | 1.95%   |
| Xubuntu       | 6         | 1.46%   |
| openSUSE      | 6         | 1.46%   |
| Kali          | 5         | 1.22%   |
| ArcoLinux     | 5         | 1.22%   |
| MX            | 4         | 0.98%   |
| Ubuntu MATE   | 3         | 0.73%   |
| Lubuntu       | 3         | 0.73%   |
| EndeavourOS   | 3         | 0.73%   |
| Elementary    | 3         | 0.73%   |
| Debian        | 2         | 0.49%   |
| Void Linux    | 1         | 0.24%   |
| UbuntuDDE     | 1         | 0.24%   |
| Ubuntu Unity  | 1         | 0.24%   |
| Ubuntu Budgie | 1         | 0.24%   |
| Slackware     | 1         | 0.24%   |
| Peppermint    | 1         | 0.24%   |
| Nobara        | 1         | 0.24%   |
| NixOS         | 1         | 0.24%   |
| LMDE          | 1         | 0.24%   |
| Linux Lite    | 1         | 0.24%   |
| LFS           | 1         | 0.24%   |
| GNOME OS      | 1         | 0.24%   |
| Generic       | 1         | 0.24%   |
| Garuda Linux  | 1         | 0.24%   |
| Devuan        | 1         | 0.24%   |
| Deepin        | 1         | 0.24%   |
| Clear Linux   | 1         | 0.24%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003            | 11        | 2.31%   |
| 6.1.1-desktop-1omv2290             | 7         | 1.47%   |
| 5.8.0-14-generic                   | 7         | 1.47%   |
| 4.18.16-desktop-1bP                | 7         | 1.47%   |
| 5.3.0-40-generic                   | 6         | 1.26%   |
| 5.15.0-48-generic                  | 6         | 1.26%   |
| 5.10.14-desktop-1omv4002           | 6         | 1.26%   |
| 4.18.0-15-generic                  | 6         | 1.26%   |
| 5.15.0-56-generic                  | 5         | 1.05%   |
| 5.15.0-46-generic                  | 5         | 1.05%   |
| 5.11.0-27-generic                  | 5         | 1.05%   |
| 5.4.0-47-generic                   | 4         | 0.84%   |
| 5.4.0-42-generic                   | 4         | 0.84%   |
| 5.3.0-23-generic                   | 4         | 0.84%   |
| 5.15.0-58-generic                  | 4         | 0.84%   |
| 5.15.0-52-generic                  | 4         | 0.84%   |
| 4.18.0-25-generic                  | 4         | 0.84%   |
| 4.18.0-12-generic                  | 4         | 0.84%   |
| 4.15.0-15-generic                  | 4         | 0.84%   |
| 5.4.0-58-generic                   | 3         | 0.63%   |
| 5.4.0-52-generic                   | 3         | 0.63%   |
| 5.4.0-48-generic                   | 3         | 0.63%   |
| 5.4.0-19-generic                   | 3         | 0.63%   |
| 5.3.0-51-generic                   | 3         | 0.63%   |
| 5.3.0-29-generic                   | 3         | 0.63%   |
| 5.3.0-28-generic                   | 3         | 0.63%   |
| 5.15.0-78-generic                  | 3         | 0.63%   |
| 5.15.0-76-generic                  | 3         | 0.63%   |
| 5.15.0-40-generic                  | 3         | 0.63%   |
| 5.13.0-30-generic                  | 3         | 0.63%   |
| 5.11.0-35-generic                  | 3         | 0.63%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 3         | 0.63%   |
| 5.0.0-31-generic                   | 3         | 0.63%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 3         | 0.63%   |
| 4.18.0-10-generic                  | 3         | 0.63%   |
| 4.15.0-desktop-45.1rosa-x86_64     | 3         | 0.63%   |
| 6.2.6-desktop-1omv2390             | 2         | 0.42%   |
| 6.2.6-76060206-generic             | 2         | 0.42%   |
| 6.2.0-26-generic                   | 2         | 0.42%   |
| 6.1.9-200.fc37.x86_64              | 2         | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 56        | 12.42%  |
| 5.15.0  | 41        | 9.09%   |
| 4.15.0  | 29        | 6.43%   |
| 5.3.0   | 27        | 5.99%   |
| 5.11.0  | 22        | 4.88%   |
| 4.18.0  | 22        | 4.88%   |
| 5.8.0   | 21        | 4.66%   |
| 5.13.0  | 17        | 3.77%   |
| 5.0.0   | 17        | 3.77%   |
| 5.19.0  | 14        | 3.1%    |
| 5.16.7  | 11        | 2.44%   |
| 6.1.1   | 8         | 1.77%   |
| 5.10.0  | 8         | 1.77%   |
| 4.18.16 | 7         | 1.55%   |
| 5.10.14 | 6         | 1.33%   |
| 6.2.6   | 4         | 0.89%   |
| 6.2.0   | 4         | 0.89%   |
| 4.9.20  | 4         | 0.89%   |
| 5.8.11  | 3         | 0.67%   |
| 5.10.74 | 3         | 0.67%   |
| 6.2.9   | 2         | 0.44%   |
| 6.1.9   | 2         | 0.44%   |
| 6.1.8   | 2         | 0.44%   |
| 6.1.7   | 2         | 0.44%   |
| 6.1.0   | 2         | 0.44%   |
| 6.0.12  | 2         | 0.44%   |
| 6.0.10  | 2         | 0.44%   |
| 5.6.14  | 2         | 0.44%   |
| 5.19.7  | 2         | 0.44%   |
| 5.18.10 | 2         | 0.44%   |
| 5.17.0  | 2         | 0.44%   |
| 5.16.0  | 2         | 0.44%   |
| 5.15.11 | 2         | 0.44%   |
| 5.12.9  | 2         | 0.44%   |
| 4.9.76  | 2         | 0.44%   |
| 4.13.0  | 2         | 0.44%   |
| 6.4.6   | 1         | 0.22%   |
| 6.4.4   | 1         | 0.22%   |
| 6.3.8   | 1         | 0.22%   |
| 6.3.6   | 1         | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 65        | 14.61%  |
| 5.15    | 51        | 11.46%  |
| 4.18    | 29        | 6.52%   |
| 4.15    | 29        | 6.52%   |
| 5.3     | 28        | 6.29%   |
| 5.11    | 28        | 6.29%   |
| 5.8     | 25        | 5.62%   |
| 5.10    | 22        | 4.94%   |
| 6.1     | 20        | 4.49%   |
| 5.19    | 20        | 4.49%   |
| 5.13    | 19        | 4.27%   |
| 5.0     | 19        | 4.27%   |
| 5.16    | 15        | 3.37%   |
| 6.2     | 11        | 2.47%   |
| 4.9     | 11        | 2.47%   |
| 6.0     | 10        | 2.25%   |
| 6.3     | 5         | 1.12%   |
| 5.18    | 5         | 1.12%   |
| 5.12    | 5         | 1.12%   |
| 5.6     | 4         | 0.9%    |
| 5.17    | 4         | 0.9%    |
| 5.9     | 2         | 0.45%   |
| 5.7     | 2         | 0.45%   |
| 5.14    | 2         | 0.45%   |
| 5.1     | 2         | 0.45%   |
| 4.19    | 2         | 0.45%   |
| 4.13    | 2         | 0.45%   |
| 4.1     | 2         | 0.45%   |
| 6.4     | 1         | 0.22%   |
| 5.5     | 1         | 0.22%   |
| 4.4     | 1         | 0.22%   |
| 4.17    | 1         | 0.22%   |
| 4.12    | 1         | 0.22%   |
| 4.10    | 1         | 0.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 383       | 96.47%  |
| i686   | 14        | 3.53%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 177       | 42.34%  |
| KDE5            | 75        | 17.94%  |
| Unknown         | 56        | 13.4%   |
| XFCE            | 35        | 8.37%   |
| X-Cinnamon      | 21        | 5.02%   |
| KDE4            | 11        | 2.63%   |
| MATE            | 6         | 1.44%   |
| KDE             | 6         | 1.44%   |
| i3              | 6         | 1.44%   |
| Cinnamon        | 6         | 1.44%   |
| LXQt            | 4         | 0.96%   |
| Pantheon        | 3         | 0.72%   |
| qtile           | 2         | 0.48%   |
| GNOME Flashback | 2         | 0.48%   |
| Deepin          | 2         | 0.48%   |
| Unity           | 1         | 0.24%   |
| LXDE            | 1         | 0.24%   |
| Hyprland        | 1         | 0.24%   |
| DWM             | 1         | 0.24%   |
| BunsenLabs      | 1         | 0.24%   |
| Budgie          | 1         | 0.24%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 316       | 76.33%  |
| Wayland | 60        | 14.49%  |
| Unknown | 33        | 7.97%   |
| Tty     | 5         | 1.21%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 196       | 47.69%  |
| SDDM    | 68        | 16.55%  |
| GDM3    | 48        | 11.68%  |
| GDM     | 41        | 9.98%   |
| LightDM | 35        | 8.52%   |
| KDM     | 12        | 2.92%   |
| TDM     | 9         | 2.19%   |
| XDM     | 1         | 0.24%   |
| Ly      | 1         | 0.24%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 278       | 66.51%  |
| Unknown     | 76        | 18.18%  |
| sr_RS       | 20        | 4.78%   |
| sr_RS@latin | 14        | 3.35%   |
| en_GB       | 10        | 2.39%   |
| C           | 5         | 1.2%    |
| ru_RU       | 4         | 0.96%   |
| de_DE       | 4         | 0.96%   |
| hu_HU       | 3         | 0.72%   |
| nl_NL       | 1         | 0.24%   |
| hr_HR       | 1         | 0.24%   |
| en_IE       | 1         | 0.24%   |
| en_AU       | 1         | 0.24%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 223       | 55.06%  |
| BIOS | 182       | 44.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 301       | 73.59%  |
| Overlay | 39        | 9.54%   |
| Btrfs   | 28        | 6.85%   |
| Unknown | 26        | 6.36%   |
| Tmpfs   | 12        | 2.93%   |
| Zfs     | 2         | 0.49%   |
| Xfs     | 1         | 0.24%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 202       | 49.27%  |
| GPT     | 146       | 35.61%  |
| MBR     | 62        | 15.12%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 352       | 87.56%  |
| Yes       | 50        | 12.44%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 298       | 73.95%  |
| Yes       | 105       | 26.05%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 107       | 27.09%  |
| Hewlett-Packard     | 71        | 17.97%  |
| ASUSTek Computer    | 59        | 14.94%  |
| Dell                | 54        | 13.67%  |
| Acer                | 41        | 10.38%  |
| Toshiba             | 13        | 3.29%   |
| Apple               | 9         | 2.28%   |
| MSI                 | 6         | 1.52%   |
| Fujitsu Siemens     | 6         | 1.52%   |
| Sony                | 4         | 1.01%   |
| Timi                | 3         | 0.76%   |
| Fujitsu             | 3         | 0.76%   |
| Samsung Electronics | 2         | 0.51%   |
| Medion              | 2         | 0.51%   |
| LG Electronics      | 2         | 0.51%   |
| HUAWEI              | 2         | 0.51%   |
| eMachines           | 2         | 0.51%   |
| TWC                 | 1         | 0.25%   |
| Synology            | 1         | 0.25%   |
| Razer               | 1         | 0.25%   |
| Packard Bell        | 1         | 0.25%   |
| IBM                 | 1         | 0.25%   |
| HONOR               | 1         | 0.25%   |
| Gigabyte Technology | 1         | 0.25%   |
| BenQ                | 1         | 0.25%   |
| Alienware           | 1         | 0.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Acer Aspire A315-31                        | 7         | 1.77%   |
| HP Notebook                                | 5         | 1.27%   |
| Lenovo V330-15IKB 81AX                     | 4         | 1.01%   |
| Lenovo IdeaPad 5 14ARE05 81YM              | 3         | 0.76%   |
| Lenovo IdeaPad 330-15IKB 81DE              | 3         | 0.76%   |
| Lenovo IdeaPad 3 15IIL05 81WE              | 3         | 0.76%   |
| Lenovo IdeaPad 110-15IBR 80T7              | 3         | 0.76%   |
| HP 250 G5 Notebook PC                      | 3         | 0.76%   |
| Dell Inspiron 3593                         | 3         | 0.76%   |
| ASUS X541NA                                | 3         | 0.76%   |
| Unknown                                    | 3         | 0.76%   |
| MSI CR500                                  | 2         | 0.51%   |
| Lenovo Legion Y530-15ICH 81FV              | 2         | 0.51%   |
| Lenovo Legion 5 15ARH05H 82B1              | 2         | 0.51%   |
| Lenovo IdeaPad S540-14API 81NH             | 2         | 0.51%   |
| Lenovo IdeaPad L340-15API 81LW             | 2         | 0.51%   |
| Lenovo IdeaPad 5 14ALC05 82LM              | 2         | 0.51%   |
| Lenovo G500 20236                          | 2         | 0.51%   |
| Lenovo B50-45 20388                        | 2         | 0.51%   |
| HP Pavilion Notebook                       | 2         | 0.51%   |
| HP Pavilion dv7                            | 2         | 0.51%   |
| HP Laptop 15-ra0xx                         | 2         | 0.51%   |
| HP Laptop 15-db1xxx                        | 2         | 0.51%   |
| HP Laptop 15-db0xxx                        | 2         | 0.51%   |
| HP G62                                     | 2         | 0.51%   |
| HP EliteBook 840 G5                        | 2         | 0.51%   |
| Fujitsu Siemens AMILO Li3710               | 2         | 0.51%   |
| Dell Vostro 3500                           | 2         | 0.51%   |
| Dell Vostro 15 3515                        | 2         | 0.51%   |
| Dell Latitude E5470                        | 2         | 0.51%   |
| Dell Latitude 7490                         | 2         | 0.51%   |
| Dell Inspiron 3558                         | 2         | 0.51%   |
| Dell Inspiron 3542                         | 2         | 0.51%   |
| Dell Inspiron 3537                         | 2         | 0.51%   |
| ASUS X55A                                  | 2         | 0.51%   |
| ASUS X541NC                                | 2         | 0.51%   |
| ASUS VivoBook_ASUSLaptop X580GD_N580GD     | 2         | 0.51%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X543MA | 2         | 0.51%   |
| ASUS K54C                                  | 2         | 0.51%   |
| Apple MacBookPro8,1                        | 2         | 0.51%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo IdeaPad        | 37        | 9.37%   |
| Lenovo ThinkPad       | 36        | 9.11%   |
| Acer Aspire           | 36        | 9.11%   |
| Dell Inspiron         | 26        | 6.58%   |
| ASUS VivoBook         | 17        | 4.3%    |
| HP Laptop             | 14        | 3.54%   |
| Dell Latitude         | 13        | 3.29%   |
| Toshiba Satellite     | 11        | 2.78%   |
| HP EliteBook          | 11        | 2.78%   |
| HP ProBook            | 10        | 2.53%   |
| HP Pavilion           | 8         | 2.03%   |
| Lenovo Legion         | 7         | 1.77%   |
| HP 250                | 7         | 1.77%   |
| Dell Vostro           | 6         | 1.52%   |
| Lenovo ThinkBook      | 5         | 1.27%   |
| HP Notebook           | 5         | 1.27%   |
| Fujitsu Siemens AMILO | 5         | 1.27%   |
| Dell Precision        | 5         | 1.27%   |
| Lenovo V330-15IKB     | 4         | 1.01%   |
| HP OMEN               | 3         | 0.76%   |
| HP Compaq             | 3         | 0.76%   |
| Fujitsu LIFEBOOK      | 3         | 0.76%   |
| ASUS ZenBook          | 3         | 0.76%   |
| ASUS X541NA           | 3         | 0.76%   |
| Apple MacBookPro8     | 3         | 0.76%   |
| Acer Nitro            | 3         | 0.76%   |
| Unknown               | 3         | 0.76%   |
| MSI CR500             | 2         | 0.51%   |
| Lenovo G500           | 2         | 0.51%   |
| Lenovo B50-45         | 2         | 0.51%   |
| HP G62                | 2         | 0.51%   |
| Dell XPS              | 2         | 0.51%   |
| ASUS X55A             | 2         | 0.51%   |
| ASUS X541NC           | 2         | 0.51%   |
| ASUS TUF              | 2         | 0.51%   |
| ASUS K54C             | 2         | 0.51%   |
| Apple MacBookPro5     | 2         | 0.51%   |
| Toshiba TECRA         | 1         | 0.25%   |
| Toshiba QOSMIO        | 1         | 0.25%   |
| Timi Xiaomi           | 1         | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 41        | 10.38%  |
| 2020 | 40        | 10.13%  |
| 2019 | 34        | 8.61%   |
| 2011 | 33        | 8.35%   |
| 2017 | 32        | 8.1%    |
| 2016 | 29        | 7.34%   |
| 2012 | 25        | 6.33%   |
| 2013 | 23        | 5.82%   |
| 2010 | 23        | 5.82%   |
| 2021 | 21        | 5.32%   |
| 2014 | 19        | 4.81%   |
| 2015 | 18        | 4.56%   |
| 2008 | 16        | 4.05%   |
| 2022 | 13        | 3.29%   |
| 2009 | 12        | 3.04%   |
| 2007 | 7         | 1.77%   |
| 2006 | 6         | 1.52%   |
| 2005 | 2         | 0.51%   |
| 2023 | 1         | 0.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 395       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 361       | 90.02%  |
| Enabled  | 40        | 9.98%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 395       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 118       | 29.21%  |
| 4.01-8.0    | 104       | 25.74%  |
| 8.01-16.0   | 70        | 17.33%  |
| 16.01-24.0  | 58        | 14.36%  |
| 1.01-2.0    | 19        | 4.7%    |
| 32.01-64.0  | 18        | 4.46%   |
| 2.01-3.0    | 11        | 2.72%   |
| 24.01-32.0  | 4         | 0.99%   |
| 64.01-256.0 | 1         | 0.25%   |
| 0.51-1.0    | 1         | 0.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 155       | 35.15%  |
| 2.01-3.0   | 105       | 23.81%  |
| 3.01-4.0   | 59        | 13.38%  |
| 4.01-8.0   | 51        | 11.56%  |
| 0.51-1.0   | 50        | 11.34%  |
| 8.01-16.0  | 19        | 4.31%   |
| 16.01-24.0 | 1         | 0.23%   |
| 0.01-0.5   | 1         | 0.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 308       | 75.68%  |
| 2      | 83        | 20.39%  |
| 3      | 8         | 1.97%   |
| 0      | 8         | 1.97%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 235       | 58.9%   |
| Yes       | 164       | 41.1%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 342       | 86.58%  |
| No        | 53        | 13.42%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 394       | 99.49%  |
| No        | 2         | 0.51%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 325       | 81.05%  |
| No        | 76        | 18.95%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Serbia  | 395       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Belgrade      | 253       | 60.1%   |
| Novi Sad      | 43        | 10.21%  |
| Niš          | 25        | 5.94%   |
| Subotica      | 7         | 1.66%   |
| Zrenjanin     | 5         | 1.19%   |
| Savski Venac  | 4         | 0.95%   |
| Pančevo      | 4         | 0.95%   |
| Novi Belgrade | 4         | 0.95%   |
| Leskovac      | 4         | 0.95%   |
| Senta         | 3         | 0.71%   |
| Novi Karlovci | 3         | 0.71%   |
| Lozovik       | 3         | 0.71%   |
| Kragujevac    | 3         | 0.71%   |
| Kovin         | 3         | 0.71%   |
| Jagodina      | 3         | 0.71%   |
| Čačak       | 3         | 0.71%   |
| Backa Topola  | 3         | 0.71%   |
| Varvarin      | 2         | 0.48%   |
| Trstenik      | 2         | 0.48%   |
| Sabac         | 2         | 0.48%   |
| Požarevac    | 2         | 0.48%   |
| Palanka       | 2         | 0.48%   |
| Mladenovac    | 2         | 0.48%   |
| Lazarevac     | 2         | 0.48%   |
| Branicevo     | 2         | 0.48%   |
| Bor           | 2         | 0.48%   |
| Becej         | 2         | 0.48%   |
| Vršac        | 1         | 0.24%   |
| Vranje        | 1         | 0.24%   |
| Valjevo       | 1         | 0.24%   |
| Užice        | 1         | 0.24%   |
| UÅ¾ice      | 1         | 0.24%   |
| Stara Pazova  | 1         | 0.24%   |
| Semlin        | 1         | 0.24%   |
| Ruma          | 1         | 0.24%   |
| Ripanj        | 1         | 0.24%   |
| Pukovac       | 1         | 0.24%   |
| Pirot         | 1         | 0.24%   |
| Novi Knezevac | 1         | 0.24%   |
| New Belgrade  | 1         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC                          | 62        | 90     | 13.36%  |
| Samsung Electronics          | 61        | 73     | 13.15%  |
| Seagate                      | 54        | 64     | 11.64%  |
| Toshiba                      | 52        | 66     | 11.21%  |
| Kingston                     | 28        | 32     | 6.03%   |
| SK hynix                     | 23        | 27     | 4.96%   |
| Hitachi                      | 22        | 23     | 4.74%   |
| SanDisk                      | 20        | 27     | 4.31%   |
| Intel                        | 17        | 28     | 3.66%   |
| Micron Technology            | 16        | 18     | 3.45%   |
| HGST                         | 14        | 23     | 3.02%   |
| Unknown                      | 12        | 17     | 2.59%   |
| Patriot                      | 10        | 13     | 2.16%   |
| SPCC                         | 8         | 14     | 1.72%   |
| KIOXIA                       | 6         | 7      | 1.29%   |
| GeIL                         | 5         | 5      | 1.08%   |
| Fujitsu                      | 5         | 5      | 1.08%   |
| A-DATA Technology            | 5         | 5      | 1.08%   |
| Transcend                    | 4         | 4      | 0.86%   |
| LITEON                       | 4         | 5      | 0.86%   |
| Gigabyte Technology          | 4         | 4      | 0.86%   |
| Crucial                      | 3         | 5      | 0.65%   |
| Unknown                      | 3         | 3      | 0.65%   |
| Union Memory                 | 2         | 2      | 0.43%   |
| Phison                       | 2         | 3      | 0.43%   |
| Kingston Technology Company  | 2         | 2      | 0.43%   |
| Biostar                      | 2         | 2      | 0.43%   |
| AMD                          | 2         | 2      | 0.43%   |
| Verbatim                     | 1         | 1      | 0.22%   |
| Union Memory (Shenzhen)      | 1         | 1      | 0.22%   |
| SSSTC                        | 1         | 1      | 0.22%   |
| Solid State Storage          | 1         | 1      | 0.22%   |
| Silicon Motion               | 1         | 1      | 0.22%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.22%   |
| Realtek Semiconductor        | 1         | 4      | 0.22%   |
| PNY                          | 1         | 1      | 0.22%   |
| Netac                        | 1         | 1      | 0.22%   |
| LITEONIT                     | 1         | 1      | 0.22%   |
| JMicron Technology           | 1         | 1      | 0.22%   |
| IBM/Hitachi                  | 1         | 1      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 18        | 3.82%   |
| Toshiba MQ01ABF050 500GB                            | 13        | 2.76%   |
| Seagate ST500LT012-1DG142 500GB                     | 8         | 1.7%    |
| Kingston SA400S37240G 240GB SSD                     | 7         | 1.49%   |
| Toshiba MQ04ABF100 1TB                              | 5         | 1.06%   |
| Toshiba MQ01ABD100 1TB                              | 5         | 1.06%   |
| Seagate ST500LT012-9WS142 500GB                     | 5         | 1.06%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 5         | 1.06%   |
| Samsung NVMe SSD Drive 256GB                        | 5         | 1.06%   |
| Samsung MZALQ512HALU-000L2 512GB                    | 5         | 1.06%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB                | 4         | 0.85%   |
| Kingston SA400S37480G 480GB SSD                     | 4         | 0.85%   |
| Kingston SA400S37120G 120GB SSD                     | 4         | 0.85%   |
| Hitachi HTS545050A7E380 500GB                       | 4         | 0.85%   |
| WDC WDS500G2B0A 500GB SSD                           | 3         | 0.64%   |
| WDC WD5000LPCX-24VHAT0 500GB                        | 3         | 0.64%   |
| WDC WD3200BEVT-22ZCT0 320GB                         | 3         | 0.64%   |
| SPCC Solid State Disk 256GB                         | 3         | 0.64%   |
| SK hynix NVMe SSD Drive 256GB                       | 3         | 0.64%   |
| Sandisk WD Blue SN550 NVMe SSD 250GB                | 3         | 0.64%   |
| SanDisk NVMe SSD Drive 256GB                        | 3         | 0.64%   |
| Samsung SSD 850 EVO 250GB                           | 3         | 0.64%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 3         | 0.64%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD                 | 3         | 0.64%   |
| Kingston RBUSC180DS37256GJ 256GB SSD                | 3         | 0.64%   |
| Hitachi HTS547575A9E384 752GB                       | 3         | 0.64%   |
| Hitachi HTS545032B9A300 320GB                       | 3         | 0.64%   |
| HGST HTS721010A9E630 1TB                            | 3         | 0.64%   |
| HGST HTS545050A7E680 500GB                          | 3         | 0.64%   |
| HGST HTS545050A7E380 500GB                          | 3         | 0.64%   |
| GeIL R3_128GB                                       | 3         | 0.64%   |
| Unknown                                             | 3         | 0.64%   |
| WDC WD5000LPVX-75V0TT0 500GB                        | 2         | 0.42%   |
| WDC WD5000LPCX-80VHAT1 500GB                        | 2         | 0.42%   |
| WDC WD5000LPCX-60VHAT0 500GB                        | 2         | 0.42%   |
| WDC WD3200BEVT-22A23T0 320GB                        | 2         | 0.42%   |
| WDC WD2500BEVS-22UST0 250GB                         | 2         | 0.42%   |
| WDC WD1200BEVS-22UST0 120GB                         | 2         | 0.42%   |
| WDC WD10SPZX-24Z10 1TB                              | 2         | 0.42%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 2         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 54        | 64     | 28.72%  |
| WDC                 | 46        | 72     | 24.47%  |
| Toshiba             | 43        | 54     | 22.87%  |
| Hitachi             | 22        | 23     | 11.7%   |
| HGST                | 14        | 23     | 7.45%   |
| Fujitsu             | 5         | 5      | 2.66%   |
| Unknown             | 1         | 1      | 0.53%   |
| Samsung Electronics | 1         | 2      | 0.53%   |
| JMicron Technology  | 1         | 1      | 0.53%   |
| IBM/Hitachi         | 1         | 1      | 0.53%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 28        | 34     | 20.59%  |
| Kingston            | 24        | 27     | 17.65%  |
| Patriot             | 10        | 13     | 7.35%   |
| SPCC                | 8         | 14     | 5.88%   |
| SanDisk             | 8         | 12     | 5.88%   |
| Micron Technology   | 6         | 6      | 4.41%   |
| WDC                 | 5         | 6      | 3.68%   |
| Toshiba             | 5         | 6      | 3.68%   |
| Intel               | 5         | 6      | 3.68%   |
| GeIL                | 5         | 5      | 3.68%   |
| Transcend           | 4         | 4      | 2.94%   |
| LITEON              | 4         | 5      | 2.94%   |
| A-DATA Technology   | 4         | 4      | 2.94%   |
| SK hynix            | 3         | 3      | 2.21%   |
| Crucial             | 3         | 5      | 2.21%   |
| Gigabyte Technology | 2         | 2      | 1.47%   |
| Biostar             | 2         | 2      | 1.47%   |
| AMD                 | 2         | 2      | 1.47%   |
| Unknown             | 2         | 2      | 1.47%   |
| Verbatim            | 1         | 1      | 0.74%   |
| SSSTC               | 1         | 1      | 0.74%   |
| PNY                 | 1         | 1      | 0.74%   |
| Netac               | 1         | 1      | 0.74%   |
| LITEONIT            | 1         | 1      | 0.74%   |
| Apacer              | 1         | 1      | 0.74%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 188       | 246    | 41.87%  |
| SSD     | 127       | 164    | 28.29%  |
| NVMe    | 122       | 161    | 27.17%  |
| MMC     | 11        | 16     | 2.45%   |
| Unknown | 1         | 1      | 0.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 280       | 403    | 66.83%  |
| NVMe | 122       | 161    | 29.12%  |
| MMC  | 11        | 16     | 2.63%   |
| SAS  | 6         | 8      | 1.43%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 223       | 293    | 73.84%  |
| 0.51-1.0   | 74        | 103    | 24.5%   |
| 1.01-2.0   | 4         | 11     | 1.32%   |
| 4.01-10.0  | 1         | 3      | 0.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 126       | 29.37%  |
| 251-500        | 118       | 27.51%  |
| 501-1000       | 52        | 12.12%  |
| 1-20           | 42        | 9.79%   |
| 51-100         | 27        | 6.29%   |
| 21-50          | 21        | 4.9%    |
| Unknown        | 18        | 4.2%    |
| 1001-2000      | 14        | 3.26%   |
| 2001-3000      | 8         | 1.86%   |
| More than 3000 | 3         | 0.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 176       | 39.91%  |
| 21-50     | 85        | 19.27%  |
| 101-250   | 63        | 14.29%  |
| 51-100    | 52        | 11.79%  |
| 251-500   | 28        | 6.35%   |
| Unknown   | 18        | 4.08%   |
| 501-1000  | 13        | 2.95%   |
| 1001-2000 | 5         | 1.13%   |
| 2001-3000 | 1         | 0.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Notebooks | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABF050 500GB                | 3         | 3      | 9.68%   |
| Seagate ST1000LM035-1RK172 1TB          | 2         | 2      | 6.45%   |
| Hitachi HTS545050A7E380 500GB           | 2         | 2      | 6.45%   |
| HGST HTS725050A7E630 500GB              | 2         | 6      | 6.45%   |
| WDC WD5000BEVT-24A0RT0 500GB            | 1         | 1      | 3.23%   |
| WDC WD3200BEVT-22ZCT0 320GB             | 1         | 1      | 3.23%   |
| Toshiba MQ01ABD032 320GB                | 1         | 1      | 3.23%   |
| Toshiba MK5061GSYN 500GB                | 1         | 1      | 3.23%   |
| Toshiba MK1652GSX 160GB                 | 1         | 1      | 3.23%   |
| Toshiba MK1637GSX 160GB                 | 1         | 1      | 3.23%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD | 1         | 1      | 3.23%   |
| SPCC Solid State DiskB27 32GB           | 1         | 1      | 3.23%   |
| Seagate ST980813AS 80GB                 | 1         | 1      | 3.23%   |
| Seagate ST9250827AS 250GB               | 1         | 1      | 3.23%   |
| Seagate ST9120822AS 120GB               | 1         | 1      | 3.23%   |
| Seagate ST750LM022 HN-M750MBB 752GB     | 1         | 1      | 3.23%   |
| Seagate ST500LT012-9WS142 500GB         | 1         | 1      | 3.23%   |
| Seagate ST500LT012-1DG142 500GB         | 1         | 2      | 3.23%   |
| Seagate ST1000LM048-2E7172 1TB          | 1         | 1      | 3.23%   |
| Samsung Electronics HM120JI 120GB       | 1         | 2      | 3.23%   |
| Kingston SA400S37480G 480GB SSD         | 1         | 1      | 3.23%   |
| Hitachi HTS722080K9A300 80GB            | 1         | 1      | 3.23%   |
| Hitachi HTS541612J9SA00 120GB           | 1         | 1      | 3.23%   |
| HGST HTS721010A9E630 1TB                | 1         | 2      | 3.23%   |
| Fujitsu MHZ2160BH G1 160GB              | 1         | 1      | 3.23%   |
| Fujitsu MHW2160BH PL 160GB              | 1         | 1      | 3.23%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 10     | 29.03%  |
| Toshiba             | 8         | 8      | 25.81%  |
| Hitachi             | 4         | 4      | 12.9%   |
| HGST                | 3         | 8      | 9.68%   |
| WDC                 | 2         | 2      | 6.45%   |
| Fujitsu             | 2         | 2      | 6.45%   |
| SPCC                | 1         | 1      | 3.23%   |
| Samsung Electronics | 1         | 2      | 3.23%   |
| Kingston            | 1         | 1      | 3.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 10     | 32.14%  |
| Toshiba             | 7         | 7      | 25%     |
| Hitachi             | 4         | 4      | 14.29%  |
| HGST                | 3         | 8      | 10.71%  |
| WDC                 | 2         | 2      | 7.14%   |
| Fujitsu             | 2         | 2      | 7.14%   |
| Samsung Electronics | 1         | 2      | 3.57%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 28        | 35     | 90.32%  |
| SSD  | 3         | 3      | 9.68%   |

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
| Detected | 226       | 359    | 54.85%  |
| Works    | 155       | 191    | 37.62%  |
| Malfunc  | 31        | 38     | 7.52%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 289       | 61.1%   |
| AMD                            | 52        | 10.99%  |
| Samsung Electronics            | 37        | 7.82%   |
| SanDisk                        | 23        | 4.86%   |
| SK hynix                       | 20        | 4.23%   |
| Micron Technology              | 10        | 2.11%   |
| Nvidia                         | 6         | 1.27%   |
| KIOXIA                         | 6         | 1.27%   |
| Kingston Technology Company    | 6         | 1.27%   |
| Toshiba America Info Systems   | 5         | 1.06%   |
| Phison Electronics             | 4         | 0.85%   |
| Union Memory (Shenzhen)        | 3         | 0.63%   |
| JMicron Technology             | 2         | 0.42%   |
| ADATA Technology               | 2         | 0.42%   |
| VIA Technologies               | 1         | 0.21%   |
| Solid State Storage Technology | 1         | 0.21%   |
| Silicon Motion                 | 1         | 0.21%   |
| Silicon Image                  | 1         | 0.21%   |
| Shenzhen Longsys Electronics   | 1         | 0.21%   |
| Realtek Semiconductor          | 1         | 0.21%   |
| ASMedia Technology             | 1         | 0.21%   |
| Apple                          | 1         | 0.21%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 43        | 8.48%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 34        | 6.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 28        | 5.52%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 27        | 5.33%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 22        | 4.34%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 14        | 2.76%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 14        | 2.76%   |
| Samsung NVMe SSD Controller 980                                                  | 13        | 2.56%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 13        | 2.56%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 12        | 2.37%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 11        | 2.17%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 10        | 1.97%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 10        | 1.97%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 10        | 1.97%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 9         | 1.78%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 9         | 1.78%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 8         | 1.58%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 8         | 1.58%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 8         | 1.58%   |
| SK hynix BC511 NVMe SSD                                                          | 7         | 1.38%   |
| Intel Volume Management Device NVMe RAID Controller                              | 7         | 1.38%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 7         | 1.38%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 6         | 1.18%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 6         | 1.18%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 6         | 1.18%   |
| Intel Tiger Lake-LP SATA Controller                                              | 6         | 1.18%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 6         | 1.18%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 6         | 1.18%   |
| Nvidia MCP79 AHCI Controller                                                     | 5         | 0.99%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 5         | 0.99%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 5         | 0.99%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 5         | 0.99%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 4         | 0.79%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 4         | 0.79%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 4         | 0.79%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 4         | 0.79%   |
| Intel SSD 660P Series                                                            | 4         | 0.79%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 4         | 0.79%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 3         | 0.59%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 3         | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 301       | 61.43%  |
| NVMe | 126       | 25.71%  |
| RAID | 32        | 6.53%   |
| IDE  | 31        | 6.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 320       | 81.01%  |
| AMD    | 75        | 18.99%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 8         | 2.03%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 7         | 1.77%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 6         | 1.52%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 6         | 1.52%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 6         | 1.52%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 6         | 1.52%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 6         | 1.52%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 5         | 1.27%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 1.27%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 5         | 1.27%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.27%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 5         | 1.27%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 5         | 1.27%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 4         | 1.01%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 4         | 1.01%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 4         | 1.01%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 4         | 1.01%   |
| Intel Celeron CPU 1000M @ 1.80GHz             | 4         | 1.01%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.01%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 1.01%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 4         | 1.01%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 4         | 1.01%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 3         | 0.76%   |
| Intel Pentium M processor 1.86GHz             | 3         | 0.76%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 0.76%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 3         | 0.76%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 3         | 0.76%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 0.76%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 0.76%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 3         | 0.76%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 3         | 0.76%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 0.76%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 3         | 0.76%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 0.76%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 0.76%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 0.76%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 3         | 0.76%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 3         | 0.76%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 3         | 0.76%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 3         | 0.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 80        | 20.25%  |
| Intel Core i5           | 72        | 18.23%  |
| Intel Core i3           | 39        | 9.87%   |
| Intel Celeron           | 34        | 8.61%   |
| Intel Pentium           | 30        | 7.59%   |
| AMD Ryzen 5             | 28        | 7.09%   |
| Other                   | 20        | 5.06%   |
| Intel Core 2 Duo        | 17        | 4.3%    |
| AMD Ryzen 7             | 15        | 3.8%    |
| Intel Atom              | 7         | 1.77%   |
| Intel Pentium Silver    | 4         | 1.01%   |
| Intel Core 2            | 4         | 1.01%   |
| AMD Ryzen 3             | 4         | 1.01%   |
| AMD A8                  | 4         | 1.01%   |
| Intel Pentium M         | 3         | 0.76%   |
| Intel Pentium Dual-Core | 3         | 0.76%   |
| Intel Pentium Dual      | 3         | 0.76%   |
| Intel Genuine           | 2         | 0.51%   |
| AMD Ryzen 9             | 2         | 0.51%   |
| AMD Ryzen 5 PRO         | 2         | 0.51%   |
| AMD Phenom II           | 2         | 0.51%   |
| AMD E1                  | 2         | 0.51%   |
| AMD Athlon X2           | 2         | 0.51%   |
| AMD Athlon II Dual-Core | 2         | 0.51%   |
| AMD Athlon II           | 2         | 0.51%   |
| AMD A4                  | 2         | 0.51%   |
| Intel Pentium Gold      | 1         | 0.25%   |
| Intel Core M            | 1         | 0.25%   |
| Intel Core Duo          | 1         | 0.25%   |
| Intel Celeron M         | 1         | 0.25%   |
| AMD V120                | 1         | 0.25%   |
| AMD Turion 64 X2 Mobile | 1         | 0.25%   |
| AMD Ryzen Embedded      | 1         | 0.25%   |
| AMD Ryzen 7 PRO         | 1         | 0.25%   |
| AMD E2                  | 1         | 0.25%   |
| AMD A6                  | 1         | 0.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 194       | 49.11%  |
| 4      | 139       | 35.19%  |
| 6      | 29        | 7.34%   |
| 1      | 15        | 3.8%    |
| 8      | 12        | 3.04%   |
| 14     | 3         | 0.76%   |
| 16     | 1         | 0.25%   |
| 12     | 1         | 0.25%   |
| 10     | 1         | 0.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 395       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 263       | 66.58%  |
| 1      | 132       | 33.42%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 376       | 94.95%  |
| Unknown        | 11        | 2.78%   |
| 32-bit         | 9         | 2.27%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 77        | 18.73%  |
| 0x206a7    | 33        | 8.03%   |
| 0x306a9    | 19        | 4.62%   |
| 0x406e3    | 18        | 4.38%   |
| 0x806ea    | 17        | 4.14%   |
| 0x506c9    | 12        | 2.92%   |
| 0x906ea    | 10        | 2.43%   |
| 0x706e5    | 10        | 2.43%   |
| 0x1067a    | 10        | 2.43%   |
| 0x806e9    | 9         | 2.19%   |
| 0x40651    | 9         | 2.19%   |
| 0x306d4    | 9         | 2.19%   |
| 0x806ec    | 8         | 1.95%   |
| 0x806c1    | 7         | 1.7%    |
| 0x6fd      | 7         | 1.7%    |
| 0x306c3    | 7         | 1.7%    |
| 0x0a50000c | 7         | 1.7%    |
| 0x08108102 | 7         | 1.7%    |
| 0x906e9    | 6         | 1.46%   |
| 0x806eb    | 6         | 1.46%   |
| 0x506e3    | 6         | 1.46%   |
| 0x406c4    | 6         | 1.46%   |
| 0x30678    | 6         | 1.46%   |
| 0x20655    | 6         | 1.46%   |
| 0x08600106 | 6         | 1.46%   |
| 0x08108109 | 6         | 1.46%   |
| 0xa0652    | 5         | 1.22%   |
| 0x20652    | 5         | 1.22%   |
| 0x10676    | 5         | 1.22%   |
| 0x08608103 | 5         | 1.22%   |
| 0x706a8    | 4         | 0.97%   |
| 0x706a1    | 3         | 0.73%   |
| 0x6d8      | 3         | 0.73%   |
| 0x406c3    | 3         | 0.73%   |
| 0x30673    | 3         | 0.73%   |
| 0x106ca    | 3         | 0.73%   |
| 0x08600104 | 3         | 0.73%   |
| 0x0810100b | 3         | 0.73%   |
| 0x07030104 | 3         | 0.73%   |
| 0x010000c8 | 3         | 0.73%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 62        | 15.7%   |
| SandyBridge      | 38        | 9.62%   |
| Skylake          | 25        | 6.33%   |
| Haswell          | 22        | 5.57%   |
| Silvermont       | 21        | 5.32%   |
| IvyBridge        | 21        | 5.32%   |
| Zen+             | 17        | 4.3%    |
| Westmere         | 16        | 4.05%   |
| Penryn           | 15        | 3.8%    |
| IceLake          | 14        | 3.54%   |
| Goldmont         | 14        | 3.54%   |
| Core             | 14        | 3.54%   |
| Broadwell        | 13        | 3.29%   |
| TigerLake        | 12        | 3.04%   |
| Zen 2            | 11        | 2.78%   |
| Zen 3            | 9         | 2.28%   |
| Unknown          | 9         | 2.28%   |
| Zen              | 8         | 2.03%   |
| Goldmont plus    | 8         | 2.03%   |
| P6               | 7         | 1.77%   |
| K10              | 7         | 1.77%   |
| CometLake        | 6         | 1.52%   |
| Alderlake Hybrid | 6         | 1.52%   |
| Bonnell          | 5         | 1.27%   |
| Puma             | 4         | 1.01%   |
| Excavator        | 3         | 0.76%   |
| Piledriver       | 2         | 0.51%   |
| K8 & K10 hybrid  | 2         | 0.51%   |
| Jaguar           | 2         | 0.51%   |
| Nehalem          | 1         | 0.25%   |
| K8 Hammer        | 1         | 0.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 288       | 56.03%  |
| Nvidia           | 114       | 22.18%  |
| AMD              | 111       | 21.6%   |
| VIA Technologies | 1         | 0.19%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 34        | 6.38%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 21        | 3.94%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 17        | 3.19%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 17        | 3.19%   |
| Intel UHD Graphics 620                                                                   | 13        | 2.44%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 12        | 2.25%   |
| Intel HD Graphics 620                                                                    | 12        | 2.25%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 2.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 12        | 2.25%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 11        | 2.06%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 2.06%   |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 2.06%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 11        | 2.06%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10        | 1.88%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 10        | 1.88%   |
| Intel HD Graphics 5500                                                                   | 10        | 1.88%   |
| AMD Renoir                                                                               | 10        | 1.88%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 9         | 1.69%   |
| Intel HD Graphics 500                                                                    | 9         | 1.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 1.69%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 8         | 1.5%    |
| AMD Lucienne                                                                             | 8         | 1.5%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 7         | 1.31%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 7         | 1.31%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 7         | 1.31%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 7         | 1.31%   |
| Intel HD Graphics 530                                                                    | 6         | 1.13%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 0.94%   |
| Intel HD Graphics 630                                                                    | 5         | 0.94%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 0.94%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 5         | 0.94%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.75%   |
| Nvidia GP108M [GeForce MX230]                                                            | 4         | 0.75%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 0.75%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 4         | 0.75%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 4         | 0.75%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 0.75%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 0.56%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 3         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 180       | 45.23%  |
| Intel + Nvidia | 83        | 20.85%  |
| 1 x AMD        | 66        | 16.58%  |
| Intel + AMD    | 28        | 7.04%   |
| 1 x Nvidia     | 20        | 5.03%   |
| AMD + Nvidia   | 9         | 2.26%   |
| 2 x AMD        | 8         | 2.01%   |
| 2 x Nvidia     | 2         | 0.5%    |
| Other          | 1         | 0.25%   |
| 1 x VIA        | 1         | 0.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 338       | 84.29%  |
| Proprietary | 51        | 12.72%  |
| Unknown     | 12        | 2.99%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 236       | 57.56%  |
| 1.01-2.0   | 64        | 15.61%  |
| 0.01-0.5   | 59        | 14.39%  |
| 3.01-4.0   | 28        | 6.83%   |
| 0.51-1.0   | 21        | 5.12%   |
| 7.01-8.0   | 1         | 0.24%   |
| 5.01-6.0   | 1         | 0.24%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 88        | 19.64%  |
| BOE                     | 71        | 15.85%  |
| LG Display              | 67        | 14.96%  |
| Chimei Innolux          | 58        | 12.95%  |
| Samsung Electronics     | 41        | 9.15%   |
| Dell                    | 15        | 3.35%   |
| Lenovo                  | 13        | 2.9%    |
| Chi Mei Optoelectronics | 13        | 2.9%    |
| PANDA                   | 9         | 2.01%   |
| Apple                   | 9         | 2.01%   |
| Sharp                   | 7         | 1.56%   |
| Philips                 | 6         | 1.34%   |
| Goldstar                | 6         | 1.34%   |
| LG Philips              | 5         | 1.12%   |
| Hewlett-Packard         | 5         | 1.12%   |
| Sony                    | 4         | 0.89%   |
| CPT                     | 4         | 0.89%   |
| Toshiba                 | 3         | 0.67%   |
| InfoVision              | 3         | 0.67%   |
| BenQ                    | 3         | 0.67%   |
| Unknown                 | 2         | 0.45%   |
| ASUSTek Computer        | 2         | 0.45%   |
| AOC                     | 2         | 0.45%   |
| ViewSonic               | 1         | 0.22%   |
| SKY                     | 1         | 0.22%   |
| Seiko/Epson             | 1         | 0.22%   |
| LPL                     | 1         | 0.22%   |
| InnoLux Display         | 1         | 0.22%   |
| Iiyama                  | 1         | 0.22%   |
| Hitachi                 | 1         | 0.22%   |
| HannStar                | 1         | 0.22%   |
| Gigabyte Technology     | 1         | 0.22%   |
| CSO                     | 1         | 0.22%   |
| CHD                     | 1         | 0.22%   |
| Ancor Communications    | 1         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 17        | 3.75%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 10        | 2.21%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 8         | 1.77%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 7         | 1.55%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 5         | 1.1%    |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 5         | 1.1%    |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 5         | 1.1%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 4         | 0.88%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 4         | 0.88%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                 | 4         | 0.88%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 4         | 0.88%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                  | 4         | 0.88%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 4         | 0.88%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch  | 3         | 0.66%   |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch | 3         | 0.66%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch         | 3         | 0.66%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 3         | 0.66%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch           | 3         | 0.66%   |
| Dell P2417H DELA0DC 1920x1080 527x296mm 23.8-inch                     | 3         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 3         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch       | 3         | 0.66%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch      | 3         | 0.66%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 3         | 0.66%   |
| BOE LCD Monitor BOE07A3 1920x1080 344x193mm 15.5-inch                 | 3         | 0.66%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 3         | 0.66%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch         | 3         | 0.66%   |
| Sony LCD SNY06FA 1600x900 291x164mm 13.2-inch                         | 2         | 0.44%   |
| Sharp LQ173M1JW04 SHP14E1 1920x1080 382x215mm 17.3-inch               | 2         | 0.44%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 2         | 0.44%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch | 2         | 0.44%   |
| PANDA LCD Monitor NCP006E 1920x1080 344x194mm 15.5-inch               | 2         | 0.44%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch          | 2         | 0.44%   |
| LG Display LCD Monitor LGD0519 1920x1080 344x194mm 15.5-inch          | 2         | 0.44%   |
| LG Display LCD Monitor LGD0484 1366x768 344x194mm 15.5-inch           | 2         | 0.44%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 0.44%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch           | 2         | 0.44%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 2         | 0.44%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch               | 2         | 0.44%   |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                  | 2         | 0.44%   |
| Dell U2412M DELA079 1920x1200 518x324mm 24.1-inch                     | 2         | 0.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 196       | 46.89%  |
| 1366x768 (WXGA)    | 137       | 32.78%  |
| 1280x800 (WXGA)    | 15        | 3.59%   |
| 1600x900 (HD+)     | 12        | 2.87%   |
| 2560x1440 (QHD)    | 8         | 1.91%   |
| 3840x2160 (4K)     | 7         | 1.67%   |
| 1440x900 (WXGA+)   | 7         | 1.67%   |
| 1920x1200 (WUXGA)  | 5         | 1.2%    |
| 2880x1800          | 4         | 0.96%   |
| 2560x1600          | 4         | 0.96%   |
| 1360x768           | 4         | 0.96%   |
| 1680x1050 (WSXGA+) | 3         | 0.72%   |
| 1024x600           | 3         | 0.72%   |
| 1280x1024 (SXGA)   | 2         | 0.48%   |
| 1024x768 (XGA)     | 2         | 0.48%   |
| Unknown            | 2         | 0.48%   |
| 3360x1200          | 1         | 0.24%   |
| 3280x1080          | 1         | 0.24%   |
| 2520x1680          | 1         | 0.24%   |
| 2160x1350          | 1         | 0.24%   |
| 1920x540           | 1         | 0.24%   |
| 1680x945           | 1         | 0.24%   |
| 1400x1050          | 1         | 0.24%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 246       | 55.03%  |
| 13      | 38        | 8.5%    |
| 14      | 33        | 7.38%   |
| 17      | 27        | 6.04%   |
| 24      | 21        | 4.7%    |
| 23      | 14        | 3.13%   |
| 12      | 11        | 2.46%   |
| 21      | 9         | 2.01%   |
| Unknown | 7         | 1.57%   |
| 31      | 6         | 1.34%   |
| 27      | 6         | 1.34%   |
| 16      | 5         | 1.12%   |
| 11      | 5         | 1.12%   |
| 72      | 3         | 0.67%   |
| 18      | 3         | 0.67%   |
| 40      | 2         | 0.45%   |
| 10      | 2         | 0.45%   |
| 84      | 1         | 0.22%   |
| 54      | 1         | 0.22%   |
| 46      | 1         | 0.22%   |
| 43      | 1         | 0.22%   |
| 32      | 1         | 0.22%   |
| 26      | 1         | 0.22%   |
| 20      | 1         | 0.22%   |
| 19      | 1         | 0.22%   |
| 8       | 1         | 0.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 302       | 67.87%  |
| 501-600     | 41        | 9.21%   |
| 351-400     | 32        | 7.19%   |
| 201-300     | 32        | 7.19%   |
| 401-500     | 14        | 3.15%   |
| Unknown     | 7         | 1.57%   |
| 601-700     | 6         | 1.35%   |
| 1501-2000   | 4         | 0.9%    |
| 801-900     | 2         | 0.45%   |
| 1001-1500   | 2         | 0.45%   |
| 701-800     | 1         | 0.22%   |
| 101-200     | 1         | 0.22%   |
| 901-1000    | 1         | 0.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 342       | 87.92%  |
| 16/10   | 34        | 8.74%   |
| 4/3     | 4         | 1.03%   |
| 3/2     | 4         | 1.03%   |
| Unknown | 4         | 1.03%   |
| 5/4     | 1         | 0.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 246       | 55.03%  |
| 81-90          | 59        | 13.2%   |
| 201-250        | 38        | 8.5%    |
| 121-130        | 26        | 5.82%   |
| 71-80          | 12        | 2.68%   |
| 61-70          | 10        | 2.24%   |
| 351-500        | 7         | 1.57%   |
| 301-350        | 7         | 1.57%   |
| Unknown        | 7         | 1.57%   |
| 251-300        | 6         | 1.34%   |
| More than 1000 | 5         | 1.12%   |
| 51-60          | 5         | 1.12%   |
| 111-120        | 4         | 0.89%   |
| 501-1000       | 4         | 0.89%   |
| 141-150        | 3         | 0.67%   |
| 41-50          | 2         | 0.45%   |
| 151-200        | 2         | 0.45%   |
| 91-100         | 2         | 0.45%   |
| 1-40           | 1         | 0.22%   |
| 131-140        | 1         | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 186       | 42.86%  |
| 101-120       | 146       | 33.64%  |
| 51-100        | 66        | 15.21%  |
| 161-240       | 18        | 4.15%   |
| Unknown       | 7         | 1.61%   |
| More than 240 | 6         | 1.38%   |
| 1-50          | 5         | 1.15%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 324       | 79.8%   |
| 2     | 62        | 15.27%  |
| 3     | 10        | 2.46%   |
| 0     | 10        | 2.46%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 231       | 35.43%  |
| Intel                             | 177       | 27.15%  |
| Qualcomm Atheros                  | 114       | 17.48%  |
| Broadcom                          | 52        | 7.98%   |
| Broadcom Limited                  | 10        | 1.53%   |
| Ralink                            | 9         | 1.38%   |
| MediaTek                          | 8         | 1.23%   |
| Nvidia                            | 6         | 0.92%   |
| Ralink Technology                 | 5         | 0.77%   |
| Marvell Technology Group          | 5         | 0.77%   |
| Sierra Wireless                   | 4         | 0.61%   |
| Ericsson Business Mobile Networks | 4         | 0.61%   |
| Dell                              | 4         | 0.61%   |
| ZTE WCDMA Technologies MSM        | 3         | 0.46%   |
| TP-Link                           | 3         | 0.46%   |
| Huawei Technologies               | 3         | 0.46%   |
| Qualcomm Atheros Communications   | 2         | 0.31%   |
| JMicron Technology                | 2         | 0.31%   |
| Xiaomi                            | 1         | 0.15%   |
| VIA Technologies                  | 1         | 0.15%   |
| Samsung Electronics               | 1         | 0.15%   |
| Linksys                           | 1         | 0.15%   |
| Lenovo                            | 1         | 0.15%   |
| IMC Networks                      | 1         | 0.15%   |
| Hewlett-Packard                   | 1         | 0.15%   |
| D-Link                            | 1         | 0.15%   |
| Arduino SA                        | 1         | 0.15%   |
| Apple                             | 1         | 0.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 136       | 17.55%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 63        | 8.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 31        | 4%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 21        | 2.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 19        | 2.45%   |
| Intel Wireless 8265 / 8275                                              | 18        | 2.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 13        | 1.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 13        | 1.68%   |
| Broadcom BCM43142 802.11b/g/n                                           | 13        | 1.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 12        | 1.55%   |
| Intel Wireless 8260                                                     | 12        | 1.55%   |
| Intel Wireless 7260                                                     | 11        | 1.42%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 10        | 1.29%   |
| Intel Wi-Fi 6 AX200                                                     | 9         | 1.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 9         | 1.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 1.03%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 8         | 1.03%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 8         | 1.03%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 1.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 0.9%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 0.9%    |
| Intel Wireless 3165                                                     | 7         | 0.9%    |
| Intel Wi-Fi 6 AX201                                                     | 7         | 0.9%    |
| Intel Ethernet Connection I219-LM                                       | 7         | 0.9%    |
| Intel Ethernet Connection (4) I219-LM                                   | 7         | 0.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 0.9%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 6         | 0.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 6         | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 6         | 0.77%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 0.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 0.77%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 6         | 0.77%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 0.65%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 5         | 0.65%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 5         | 0.65%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 0.65%   |
| Nvidia MCP79 Ethernet                                                   | 5         | 0.65%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 0.65%   |
| Intel 82577LM Gigabit Network Connection                                | 5         | 0.65%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 4         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 167       | 40.34%  |
| Qualcomm Atheros                  | 99        | 23.91%  |
| Realtek Semiconductor             | 67        | 16.18%  |
| Broadcom                          | 40        | 9.66%   |
| Ralink                            | 9         | 2.17%   |
| MediaTek                          | 8         | 1.93%   |
| Ralink Technology                 | 5         | 1.21%   |
| Sierra Wireless                   | 4         | 0.97%   |
| Dell                              | 3         | 0.72%   |
| Broadcom Limited                  | 3         | 0.72%   |
| TP-Link                           | 2         | 0.48%   |
| Qualcomm Atheros Communications   | 2         | 0.48%   |
| Linksys                           | 1         | 0.24%   |
| IMC Networks                      | 1         | 0.24%   |
| Hewlett-Packard                   | 1         | 0.24%   |
| Ericsson Business Mobile Networks | 1         | 0.24%   |
| D-Link                            | 1         | 0.24%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 31        | 7.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 21        | 5.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 19        | 4.58%   |
| Intel Wireless 8265 / 8275                                              | 18        | 4.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 13        | 3.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 13        | 3.13%   |
| Broadcom BCM43142 802.11b/g/n                                           | 13        | 3.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 12        | 2.89%   |
| Intel Wireless 8260                                                     | 12        | 2.89%   |
| Intel Wireless 7260                                                     | 11        | 2.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 10        | 2.41%   |
| Intel Wi-Fi 6 AX200                                                     | 9         | 2.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 1.93%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 8         | 1.93%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 8         | 1.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 1.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 1.69%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 1.69%   |
| Intel Wireless 3165                                                     | 7         | 1.69%   |
| Intel Wi-Fi 6 AX201                                                     | 7         | 1.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 1.69%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.45%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 1.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 1.45%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 1.2%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 5         | 1.2%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 5         | 1.2%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 1.2%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 1.2%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 4         | 0.96%   |
| Intel Wireless 7265                                                     | 4         | 0.96%   |
| Intel Wireless 3160                                                     | 4         | 0.96%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 4         | 0.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 0.96%   |
| Intel Centrino Wireless-N 2230                                          | 4         | 0.96%   |
| Intel Centrino Ultimate-N 6300                                          | 4         | 0.96%   |
| Sierra Wireless EM7455                                                  | 3         | 0.72%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 3         | 0.72%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 210       | 60.52%  |
| Intel                      | 66        | 19.02%  |
| Qualcomm Atheros           | 24        | 6.92%   |
| Broadcom                   | 18        | 5.19%   |
| Broadcom Limited           | 7         | 2.02%   |
| Nvidia                     | 6         | 1.73%   |
| Marvell Technology Group   | 5         | 1.44%   |
| ZTE WCDMA Technologies MSM | 3         | 0.86%   |
| JMicron Technology         | 2         | 0.58%   |
| Xiaomi                     | 1         | 0.29%   |
| VIA Technologies           | 1         | 0.29%   |
| TP-Link                    | 1         | 0.29%   |
| Lenovo                     | 1         | 0.29%   |
| Huawei Technologies        | 1         | 0.29%   |
| Apple                      | 1         | 0.29%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 136       | 38.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 63        | 18%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 2.57%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 2%      |
| Intel Ethernet Connection (4) I219-LM                             | 7         | 2%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 1.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 1.71%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 6         | 1.71%   |
| Nvidia MCP79 Ethernet                                             | 5         | 1.43%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 1.43%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 4         | 1.14%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 1.14%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.14%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.86%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.86%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.86%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 3         | 0.86%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.86%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 0.86%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 0.86%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 3         | 0.86%   |
| ZTE WCDMA MSM USB SCSI CD-ROM                                     | 2         | 0.57%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.57%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.57%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 0.57%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.57%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.57%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.57%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.57%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.57%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.57%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 2         | 0.57%   |
| ZTE WCDMA MSM Android                                             | 1         | 0.29%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.29%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.29%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.29%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.29%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.29%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.29%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 394       | 52.82%  |
| Ethernet | 342       | 45.84%  |
| Modem    | 10        | 1.34%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 329       | 78.52%  |
| Ethernet | 90        | 21.48%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 327       | 82.58%  |
| 1     | 68        | 17.17%  |
| 3     | 1         | 0.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 390       | 98.48%  |
| Yes  | 6         | 1.52%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 122       | 37.54%  |
| Realtek Semiconductor           | 51        | 15.69%  |
| Qualcomm Atheros Communications | 36        | 11.08%  |
| Lite-On Technology              | 25        | 7.69%   |
| IMC Networks                    | 21        | 6.46%   |
| Broadcom                        | 20        | 6.15%   |
| Foxconn / Hon Hai               | 11        | 3.38%   |
| Apple                           | 7         | 2.15%   |
| Toshiba                         | 6         | 1.85%   |
| Hewlett-Packard                 | 6         | 1.85%   |
| Dell                            | 4         | 1.23%   |
| Ralink                          | 3         | 0.92%   |
| Foxconn International           | 3         | 0.92%   |
| USI                             | 2         | 0.62%   |
| Ralink Technology               | 2         | 0.62%   |
| Cambridge Silicon Radio         | 2         | 0.62%   |
| Realtek                         | 1         | 0.31%   |
| Opticis                         | 1         | 0.31%   |
| Askey Computer                  | 1         | 0.31%   |
| Alps Electric                   | 1         | 0.31%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 54        | 16.62%  |
| Realtek Bluetooth Radio                            | 29        | 8.92%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 25        | 7.69%   |
| Qualcomm Atheros  Bluetooth Device                 | 18        | 5.54%   |
| Intel AX201 Bluetooth                              | 16        | 4.92%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth         | 13        | 4%      |
| Realtek  Bluetooth 4.2 Adapter                     | 12        | 3.69%   |
| Intel AX200 Bluetooth                              | 9         | 2.77%   |
| IMC Networks Bluetooth Radio                       | 7         | 2.15%   |
| Lite-On Bluetooth Device                           | 6         | 1.85%   |
| Apple Bluetooth Host Controller                    | 6         | 1.85%   |
| Realtek RTL8821A Bluetooth                         | 5         | 1.54%   |
| Qualcomm Atheros AR3011 Bluetooth                  | 5         | 1.54%   |
| Intel Centrino Bluetooth Wireless Transceiver      | 5         | 1.54%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0             | 4         | 1.23%   |
| Qualcomm Atheros AR9462 Bluetooth                  | 4         | 1.23%   |
| IMC Networks Wireless_Device                       | 4         | 1.23%   |
| IMC Networks Bluetooth Device                      | 4         | 1.23%   |
| Foxconn / Hon Hai Bluetooth Device                 | 4         | 1.23%   |
| Dell DW375 Bluetooth Module                        | 4         | 1.23%   |
| Broadcom BCM43142A0 Bluetooth 4.0                  | 4         | 1.23%   |
| Realtek RTL8723B Bluetooth                         | 3         | 0.92%   |
| Ralink RT3290 Bluetooth                            | 3         | 0.92%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0              | 3         | 0.92%   |
| Intel Wireless-AC 3168 Bluetooth                   | 3         | 0.92%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter   | 3         | 0.92%   |
| Intel Bluetooth Device                             | 3         | 0.92%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter  | 3         | 0.92%   |
| HP Broadcom 2070 Bluetooth Combo                   | 3         | 0.92%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]      | 3         | 0.92%   |
| Foxconn International BCM43142A0 Bluetooth module  | 3         | 0.92%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter       | 3         | 0.92%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 3         | 0.92%   |
| USI Bluetooth Module BCM92070                      | 2         | 0.62%   |
| Toshiba Bluetooth Device                           | 2         | 0.62%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter            | 2         | 0.62%   |
| Qualcomm Atheros AR3012 Bluetooth                  | 2         | 0.62%   |
| Lite-On Atheros AR3012 Bluetooth                   | 2         | 0.62%   |
| Intel Wireless-AC 9260 Bluetooth Adapter           | 2         | 0.62%   |
| Intel AX210 Bluetooth                              | 2         | 0.62%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 311       | 66.88%  |
| AMD                         | 81        | 17.42%  |
| Nvidia                      | 57        | 12.26%  |
| Logitech                    | 2         | 0.43%   |
| Hewlett-Packard             | 2         | 0.43%   |
| GN Netcom                   | 2         | 0.43%   |
| C-Media Electronics         | 2         | 0.43%   |
| Apple                       | 2         | 0.43%   |
| VIA Technologies            | 1         | 0.22%   |
| Native Instruments          | 1         | 0.22%   |
| Microsoft                   | 1         | 0.22%   |
| Kingston Technology         | 1         | 0.22%   |
| Focusrite-Novation          | 1         | 0.22%   |
| FiiO Electronics Technology | 1         | 0.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 54        | 9.52%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 46        | 8.11%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 31        | 5.47%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 28        | 4.94%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 25        | 4.41%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 23        | 4.06%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 16        | 2.82%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 14        | 2.47%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 14        | 2.47%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 13        | 2.29%   |
| Intel Broadwell-U Audio Controller                                                                | 13        | 2.29%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 12        | 2.12%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 12        | 2.12%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 12        | 2.12%   |
| Intel Cannon Lake PCH cAVS                                                                        | 12        | 2.12%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 11        | 1.94%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 1.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 11        | 1.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 11        | 1.94%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 1.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10        | 1.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 9         | 1.59%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 9         | 1.59%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 8         | 1.41%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 8         | 1.41%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 1.41%   |
| AMD FCH Azalia Controller                                                                         | 8         | 1.41%   |
| Intel Comet Lake PCH cAVS                                                                         | 6         | 1.06%   |
| Intel CM238 HD Audio Controller                                                                   | 6         | 1.06%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 1.06%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6         | 1.06%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 1.06%   |
| Nvidia MCP79 High Definition Audio                                                                | 5         | 0.88%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 0.88%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 5         | 0.88%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 5         | 0.88%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 0.71%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 0.71%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 4         | 0.71%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 3         | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 73        | 26.94%  |
| SK hynix            | 64        | 23.62%  |
| Micron Technology   | 38        | 14.02%  |
| Kingston            | 34        | 12.55%  |
| Unknown             | 17        | 6.27%   |
| Ramaxel Technology  | 12        | 4.43%   |
| Transcend           | 7         | 2.58%   |
| Elpida              | 5         | 1.85%   |
| Crucial             | 4         | 1.48%   |
| Patriot             | 3         | 1.11%   |
| A-DATA Technology   | 3         | 1.11%   |
| Corsair             | 2         | 0.74%   |
| Unknown (06F1)      | 1         | 0.37%   |
| SHARETRONIC         | 1         | 0.37%   |
| PNY                 | 1         | 0.37%   |
| Nanya Technology    | 1         | 0.37%   |
| CSX                 | 1         | 0.37%   |
| Apacer              | 1         | 0.37%   |
| AMD                 | 1         | 0.37%   |
| 48spaces            | 1         | 0.37%   |
| Unknown             | 1         | 0.37%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s  | 6         | 2.04%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s     | 6         | 2.04%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s    | 5         | 1.7%    |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s | 5         | 1.7%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s      | 5         | 1.7%    |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s    | 4         | 1.36%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s     | 4         | 1.36%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s     | 4         | 1.36%   |
| Micron RAM 4ATF51264HZ-2G6E! 4GB SODIMM DDR4 2400MT/s     | 4         | 1.36%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s   | 4         | 1.36%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 1.02%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 1.02%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s    | 3         | 1.02%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s    | 3         | 1.02%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 3         | 1.02%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 3         | 1.02%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s  | 3         | 1.02%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s     | 3         | 1.02%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s     | 3         | 1.02%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s     | 3         | 1.02%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s      | 3         | 1.02%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s      | 3         | 1.02%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s     | 3         | 1.02%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                | 2         | 0.68%   |
| Unknown RAM Module 1024MB SODIMM DDR                      | 2         | 0.68%   |
| Transcend RAM JM3200HSG-8G 8GB SODIMM DDR4 3200MT/s       | 2         | 0.68%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 2048MT/s    | 2         | 0.68%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 2         | 0.68%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s    | 2         | 0.68%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 2         | 0.68%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s    | 2         | 0.68%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM 1600MT/s         | 2         | 0.68%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s    | 2         | 0.68%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 2         | 0.68%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s    | 2         | 0.68%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM 1600MT/s          | 2         | 0.68%   |
| Samsung RAM M471B5674EB0-YK0 2GB SODIMM DDR3 1600MT/s     | 2         | 0.68%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s     | 2         | 0.68%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s  | 2         | 0.68%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s     | 2         | 0.68%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 104       | 47.93%  |
| DDR3    | 74        | 34.1%   |
| DDR2    | 12        | 5.53%   |
| SDRAM   | 7         | 3.23%   |
| LPDDR4  | 7         | 3.23%   |
| DDR5    | 4         | 1.84%   |
| Unknown | 3         | 1.38%   |
| LPDDR5  | 2         | 0.92%   |
| LPDDR3  | 2         | 0.92%   |
| DDR     | 2         | 0.92%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 197       | 90.37%  |
| Row Of Chips | 18        | 8.26%   |
| Chip         | 3         | 1.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 86        | 36.75%  |
| 4096  | 78        | 33.33%  |
| 2048  | 36        | 15.38%  |
| 16384 | 20        | 8.55%   |
| 1024  | 9         | 3.85%   |
| 32768 | 4         | 1.71%   |
| 512   | 1         | 0.43%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 54        | 22.41%  |
| 3200    | 49        | 20.33%  |
| 2667    | 47        | 19.5%   |
| 2400    | 18        | 7.47%   |
| 1334    | 14        | 5.81%   |
| 1067    | 8         | 3.32%   |
| 2133    | 7         | 2.9%    |
| 667     | 7         | 2.9%    |
| Unknown | 6         | 2.49%   |
| 4800    | 4         | 1.66%   |
| 4199    | 4         | 1.66%   |
| 1333    | 4         | 1.66%   |
| 3266    | 3         | 1.24%   |
| 2048    | 3         | 1.24%   |
| 800     | 3         | 1.24%   |
| 6400    | 2         | 0.83%   |
| 4267    | 2         | 0.83%   |
| 975     | 2         | 0.83%   |
| 533     | 2         | 0.83%   |
| 2933    | 1         | 0.41%   |
| 1066    | 1         | 0.41%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 5         | 50%     |
| Canon                 | 2         | 20%     |
| Seiko Epson           | 1         | 10%     |
| Samsung Electronics   | 1         | 10%     |
| Lexmark International | 1         | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| HP LaserJet 1018                      | 2         | 20%     |
| Seiko Epson L365 Series               | 1         | 10%     |
| Samsung M2070 Series                  | 1         | 10%     |
| Lexmark International Lexmark MS312dn | 1         | 10%     |
| HP LaserJet M14-M17                   | 1         | 10%     |
| HP LaserJet 1020                      | 1         | 10%     |
| HP DeskJet 845c                       | 1         | 10%     |
| Canon LBP6030w/6018w                  | 1         | 10%     |
| Canon iP7200 series                   | 1         | 10%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Canon              | 4         | 80%     |
| Ultima Electronics | 1         | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                               | 2         | 40%     |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1         | 20%     |
| Canon CanoScan LIDE 25                                                                | 1         | 20%     |
| Canon CanoScan LiDE 210                                                               | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 97        | 26.65%  |
| IMC Networks                           | 52        | 14.29%  |
| Realtek Semiconductor                  | 31        | 8.52%   |
| Microdia                               | 27        | 7.42%   |
| Quanta                                 | 23        | 6.32%   |
| Bison Electronics                      | 20        | 5.49%   |
| Sunplus Innovation Technology          | 18        | 4.95%   |
| Cheng Uei Precision Industry (Foxlink) | 18        | 4.95%   |
| Suyin                                  | 16        | 4.4%    |
| Syntek                                 | 13        | 3.57%   |
| Apple                                  | 8         | 2.2%    |
| Lite-On Technology                     | 7         | 1.92%   |
| Acer                                   | 7         | 1.92%   |
| Silicon Motion                         | 3         | 0.82%   |
| Luxvisions Innotech Limited            | 3         | 0.82%   |
| Logitech                               | 3         | 0.82%   |
| Lenovo                                 | 3         | 0.82%   |
| Importek                               | 3         | 0.82%   |
| ALi                                    | 3         | 0.82%   |
| Alcor Micro                            | 3         | 0.82%   |
| Samsung Electronics                    | 1         | 0.27%   |
| Ricoh                                  | 1         | 0.27%   |
| OmniVision Technologies                | 1         | 0.27%   |
| KYE Systems (Mouse Systems)            | 1         | 0.27%   |
| Generalplus Technology                 | 1         | 0.27%   |
| DigiTech                               | 1         | 0.27%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 22        | 6.03%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 19        | 5.21%   |
| Realtek Integrated_Webcam_HD                                   | 11        | 3.01%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 11        | 3.01%   |
| Syntek Integrated Camera                                       | 9         | 2.47%   |
| Microdia Integrated_Webcam_HD                                  | 9         | 2.47%   |
| IMC Networks Integrated Camera                                 | 9         | 2.47%   |
| Bison Integrated Camera                                        | 9         | 2.47%   |
| Sunplus Integrated_Webcam_HD                                   | 8         | 2.19%   |
| Chicony VGA Webcam                                             | 6         | 1.64%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 5         | 1.37%   |
| Quanta VGA WebCam                                              | 5         | 1.37%   |
| Quanta HD WebCam                                               | 5         | 1.37%   |
| Chicony TOSHIBA Web Camera - HD                                | 5         | 1.37%   |
| Chicony Integrated Camera (1280x720@30)                        | 5         | 1.37%   |
| Chicony HP Webcam                                              | 5         | 1.37%   |
| Chicony EasyCamera                                             | 5         | 1.37%   |
| Syntek EasyCamera                                              | 4         | 1.1%    |
| Realtek USB Camera                                             | 4         | 1.1%    |
| Realtek Lenovo EasyCamera                                      | 4         | 1.1%    |
| Quanta HP TrueVision HD Camera                                 | 4         | 1.1%    |
| Microdia Integrated Webcam                                     | 4         | 1.1%    |
| IMC Networks EasyCamera                                        | 4         | 1.1%    |
| Chicony HD WebCam                                              | 4         | 1.1%    |
| Chicony HD User Facing                                         | 4         | 1.1%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 4         | 1.1%    |
| Apple Built-in iSight                                          | 4         | 1.1%    |
| Sunplus Asus Webcam                                            | 3         | 0.82%   |
| Realtek Integrated Webcam HD                                   | 3         | 0.82%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 3         | 0.82%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 3         | 0.82%   |
| Chicony USB 2.0 Camera                                         | 3         | 0.82%   |
| Chicony Integrated HP HD Webcam                                | 3         | 0.82%   |
| Chicony HP Truevision HD                                       | 3         | 0.82%   |
| Chicony HP HD Camera                                           | 3         | 0.82%   |
| Chicony 1.3M HD WebCam                                         | 3         | 0.82%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 3         | 0.82%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 3         | 0.82%   |
| Bison Lenovo Integrated Webcam                                 | 3         | 0.82%   |
| Apple FaceTime HD Camera                                       | 3         | 0.82%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 24        | 37.5%   |
| Synaptics                  | 13        | 20.31%  |
| Shenzhen Goodix Technology | 11        | 17.19%  |
| AuthenTec                  | 6         | 9.38%   |
| Upek                       | 4         | 6.25%   |
| Elan Microelectronics      | 3         | 4.69%   |
| LighTuning Technology      | 2         | 3.13%   |
| STMicroelectronics         | 1         | 1.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 9         | 14.06%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 6         | 9.38%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 9.38%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 7.81%   |
| Synaptics  WBDI                                                            | 4         | 6.25%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 4.69%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 4.69%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 4.69%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 3.13%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 3.13%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 3.13%   |
| Synaptics WBDI                                                             | 2         | 3.13%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 3.13%   |
| Elan ELAN:Fingerprint                                                      | 2         | 3.13%   |
| AuthenTec AES2810                                                          | 2         | 3.13%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.56%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 1.56%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 1.56%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 1.56%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 1.56%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 1.56%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.56%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.56%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 1.56%   |
| Elan ELAN:ARM-M4                                                           | 1         | 1.56%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 13        | 37.14%  |
| Alcor Micro               | 12        | 34.29%  |
| Upek                      | 2         | 5.71%   |
| OmniKey                   | 2         | 5.71%   |
| O2 Micro                  | 2         | 5.71%   |
| Lenovo                    | 2         | 5.71%   |
| Gemalto (was Gemplus)     | 1         | 2.86%   |
| Fujitsu Siemens Computers | 1         | 2.86%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 12        | 34.29%  |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 11.43%  |
| Broadcom 5880                                                                | 4         | 11.43%  |
| Broadcom 58200                                                               | 3         | 8.57%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 5.71%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 5.71%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 5.71%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 5.71%   |
| OmniKey CardMan 4321                                                         | 1         | 2.86%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 2.86%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 2.86%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 2.86%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 256       | 62.44%  |
| 1     | 120       | 29.27%  |
| 2     | 27        | 6.59%   |
| 4     | 3         | 0.73%   |
| 3     | 3         | 0.73%   |
| 8     | 1         | 0.24%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 64        | 32.99%  |
| Graphics card            | 42        | 21.65%  |
| Chipcard                 | 32        | 16.49%  |
| Net/wireless             | 19        | 9.79%   |
| Multimedia controller    | 9         | 4.64%   |
| Bluetooth                | 7         | 3.61%   |
| Sound                    | 5         | 2.58%   |
| Communication controller | 5         | 2.58%   |
| Camera                   | 4         | 2.06%   |
| Card reader              | 3         | 1.55%   |
| Net/ethernet             | 2         | 1.03%   |
| Storage                  | 1         | 0.52%   |
| Modem                    | 1         | 0.52%   |


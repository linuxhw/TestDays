Linux in Singapore - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for Linux in Singapore.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Singapore/Desktop/README.md) and [notebooks](/Location/Singapore/Notebook/README.md).

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

Total: 392

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 830 G8 Noteboo... | Notebook    | [814c094769](https://linux-hardware.org/?probe=814c094769) | Sep 01, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [54f5dc3cf8](https://linux-hardware.org/?probe=54f5dc3cf8) | Aug 26, 2022 |
| Timi          | Redmi Book Pro 14 2022      | Notebook    | [3f61df6540](https://linux-hardware.org/?probe=3f61df6540) | Aug 26, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [c94e06f68f](https://linux-hardware.org/?probe=c94e06f68f) | Aug 26, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [7be66c9d4c](https://linux-hardware.org/?probe=7be66c9d4c) | Aug 25, 2022 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [5e20db2905](https://linux-hardware.org/?probe=5e20db2905) | Aug 24, 2022 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [f0c2f3a689](https://linux-hardware.org/?probe=f0c2f3a689) | Aug 24, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [a332f284ab](https://linux-hardware.org/?probe=a332f284ab) | Aug 22, 2022 |
| Acer          | Aspire V5-471PG             | Notebook    | [c91dcf26c8](https://linux-hardware.org/?probe=c91dcf26c8) | Aug 14, 2022 |
| Dell          | Latitude 3320               | Notebook    | [b8e1190875](https://linux-hardware.org/?probe=b8e1190875) | Aug 14, 2022 |
| Dell          | Latitude 3320               | Notebook    | [f489cd4f21](https://linux-hardware.org/?probe=f489cd4f21) | Aug 14, 2022 |
| Timi          | TM1701                      | Notebook    | [dc4d12ca83](https://linux-hardware.org/?probe=dc4d12ca83) | Aug 14, 2022 |
| Acer          | Aspire V5-471PG             | Notebook    | [5c2d9bf35f](https://linux-hardware.org/?probe=5c2d9bf35f) | Aug 13, 2022 |
| Dell          | G15 5520                    | Notebook    | [07feaad5d2](https://linux-hardware.org/?probe=07feaad5d2) | Aug 11, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [5931b46fe1](https://linux-hardware.org/?probe=5931b46fe1) | Aug 10, 2022 |
| HP            | 843B                        | Desktop     | [6033dabb9d](https://linux-hardware.org/?probe=6033dabb9d) | Aug 09, 2022 |
| Dell          | Latitude 3320               | Notebook    | [b99f237d17](https://linux-hardware.org/?probe=b99f237d17) | Aug 09, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [681326262a](https://linux-hardware.org/?probe=681326262a) | Aug 08, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [6a9c811ea3](https://linux-hardware.org/?probe=6a9c811ea3) | Aug 07, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [9893d12c54](https://linux-hardware.org/?probe=9893d12c54) | Aug 06, 2022 |
| Gigabyte      | H61M-S2PH                   | Desktop     | [31bd0a48c9](https://linux-hardware.org/?probe=31bd0a48c9) | Aug 02, 2022 |
| HP            | ZBook 15v G5                | Notebook    | [b08d670a98](https://linux-hardware.org/?probe=b08d670a98) | Jul 28, 2022 |
| Acer          | Spin SP513-52N              | Convertible | [975a56edb1](https://linux-hardware.org/?probe=975a56edb1) | Jul 28, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [b41ce610a4](https://linux-hardware.org/?probe=b41ce610a4) | Jul 22, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [1a28383fee](https://linux-hardware.org/?probe=1a28383fee) | Jul 19, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [f6670624ed](https://linux-hardware.org/?probe=f6670624ed) | Jul 16, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [366f3c9611](https://linux-hardware.org/?probe=366f3c9611) | Jul 14, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [27f2c99f99](https://linux-hardware.org/?probe=27f2c99f99) | Jul 14, 2022 |
| Sony          | SVF1531V8CW                 | Notebook    | [bebf2fb162](https://linux-hardware.org/?probe=bebf2fb162) | Jul 13, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [b33dcf5312](https://linux-hardware.org/?probe=b33dcf5312) | Jul 12, 2022 |
| Dell          | Latitude 3120               | Notebook    | [361c9c4fa3](https://linux-hardware.org/?probe=361c9c4fa3) | Jul 06, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [3af286a188](https://linux-hardware.org/?probe=3af286a188) | Jun 30, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [e91c32dba7](https://linux-hardware.org/?probe=e91c32dba7) | Jun 25, 2022 |
| congatec      | conga-MA5 B.2               | Mini pc     | [a49c763e59](https://linux-hardware.org/?probe=a49c763e59) | Jun 23, 2022 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [c434fdda77](https://linux-hardware.org/?probe=c434fdda77) | Jun 20, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | Notebook    | [6941a8232a](https://linux-hardware.org/?probe=6941a8232a) | Jun 17, 2022 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [613bb8fe40](https://linux-hardware.org/?probe=613bb8fe40) | Jun 16, 2022 |
| congatec      | conga-MA5 B.2               | Mini pc     | [b30a078392](https://linux-hardware.org/?probe=b30a078392) | Jun 15, 2022 |
| congatec      | conga-MA5 B.2               | Mini pc     | [0415226162](https://linux-hardware.org/?probe=0415226162) | Jun 11, 2022 |
| congatec      | conga-MA5 B.2               | Mini pc     | [df2d1b5c12](https://linux-hardware.org/?probe=df2d1b5c12) | Jun 11, 2022 |
| ASUSTek       | GL552VW                     | Notebook    | [8ed24a5d98](https://linux-hardware.org/?probe=8ed24a5d98) | Jun 11, 2022 |
| MSI           | Z87-G45 GAMING              | Desktop     | [53877eebd1](https://linux-hardware.org/?probe=53877eebd1) | Jun 10, 2022 |
| Sony          | VPCCA15FG                   | Notebook    | [d155f5ee52](https://linux-hardware.org/?probe=d155f5ee52) | Jun 08, 2022 |
| Dell          | Inspiron 13 5310            | Notebook    | [70eccb19d4](https://linux-hardware.org/?probe=70eccb19d4) | Jun 01, 2022 |
| Unknown       | ZynqMP SMK-K26 Rev1/B/A     | Soc         | [1acb6dc064](https://linux-hardware.org/?probe=1acb6dc064) | May 31, 2022 |
| Lenovo        | 14w 81MQS02H00              | Notebook    | [e31087bfa9](https://linux-hardware.org/?probe=e31087bfa9) | May 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [f1f75187e1](https://linux-hardware.org/?probe=f1f75187e1) | May 21, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [bdc04b3c5d](https://linux-hardware.org/?probe=bdc04b3c5d) | May 19, 2022 |
| Lenovo        | ThinkPad X220 4286C11       | Notebook    | [8fd4bc6a6d](https://linux-hardware.org/?probe=8fd4bc6a6d) | May 15, 2022 |
| Lenovo        | ThinkPad X220 4286C11       | Notebook    | [0906d694b9](https://linux-hardware.org/?probe=0906d694b9) | May 15, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [bd4201a786](https://linux-hardware.org/?probe=bd4201a786) | May 09, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [8deb85f8e2](https://linux-hardware.org/?probe=8deb85f8e2) | May 03, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [78752966d0](https://linux-hardware.org/?probe=78752966d0) | May 02, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [200ed04d31](https://linux-hardware.org/?probe=200ed04d31) | May 02, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [3a7cd290f6](https://linux-hardware.org/?probe=3a7cd290f6) | Apr 30, 2022 |
| Dell          | 06CV2N A00                  | Desktop     | [f9e949ad9b](https://linux-hardware.org/?probe=f9e949ad9b) | Apr 24, 2022 |
| Dell          | Latitude 3120               | Notebook    | [c6b9dfe36e](https://linux-hardware.org/?probe=c6b9dfe36e) | Apr 18, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [69b4016133](https://linux-hardware.org/?probe=69b4016133) | Apr 15, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [7fe8e51699](https://linux-hardware.org/?probe=7fe8e51699) | Apr 13, 2022 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [b8c46a667d](https://linux-hardware.org/?probe=b8c46a667d) | Apr 12, 2022 |
| Foxconn       | Kangaroo Mobile Desktop     | Notebook    | [8e602bc358](https://linux-hardware.org/?probe=8e602bc358) | Apr 07, 2022 |
| Foxconn       | Kangaroo Mobile Desktop     | Notebook    | [7309102f77](https://linux-hardware.org/?probe=7309102f77) | Apr 07, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [ceee79344c](https://linux-hardware.org/?probe=ceee79344c) | Mar 31, 2022 |
| Acer          | Swift SF314-54G             | Notebook    | [615009b8ee](https://linux-hardware.org/?probe=615009b8ee) | Mar 23, 2022 |
| Acer          | Aspire VN7-592G             | Notebook    | [f4d3207c6d](https://linux-hardware.org/?probe=f4d3207c6d) | Mar 22, 2022 |
| AMI           | Intel                       | Notebook    | [6d581b03a6](https://linux-hardware.org/?probe=6d581b03a6) | Mar 19, 2022 |
| Dell          | 0NK70N A03                  | Desktop     | [7d4e906833](https://linux-hardware.org/?probe=7d4e906833) | Mar 11, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [17b7d9dd0c](https://linux-hardware.org/?probe=17b7d9dd0c) | Mar 10, 2022 |
| HP            | 8054                        | Desktop     | [dfbd7e95d0](https://linux-hardware.org/?probe=dfbd7e95d0) | Mar 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [d7f14afdd4](https://linux-hardware.org/?probe=d7f14afdd4) | Feb 26, 2022 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [f92ae76fed](https://linux-hardware.org/?probe=f92ae76fed) | Feb 24, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [a8c8bdd208](https://linux-hardware.org/?probe=a8c8bdd208) | Feb 23, 2022 |
| Dell          | 09M8Y8 A02                  | Desktop     | [862667e874](https://linux-hardware.org/?probe=862667e874) | Feb 22, 2022 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [9eb75ab42f](https://linux-hardware.org/?probe=9eb75ab42f) | Feb 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [fbb2caeacf](https://linux-hardware.org/?probe=fbb2caeacf) | Feb 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [c5acc050e4](https://linux-hardware.org/?probe=c5acc050e4) | Feb 19, 2022 |
| Dell          | Precision 7560              | Notebook    | [811983afdd](https://linux-hardware.org/?probe=811983afdd) | Feb 17, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [25da470504](https://linux-hardware.org/?probe=25da470504) | Feb 14, 2022 |
| ASUSTek       | N501JW                      | Notebook    | [55550ca825](https://linux-hardware.org/?probe=55550ca825) | Feb 13, 2022 |
| COPELION I... | ZX Series                   | Notebook    | [764c80257b](https://linux-hardware.org/?probe=764c80257b) | Feb 12, 2022 |
| COPELION I... | ZX Series                   | Notebook    | [958dcebefa](https://linux-hardware.org/?probe=958dcebefa) | Feb 12, 2022 |
| Dell          | Latitude E5450              | Notebook    | [b426feb1d9](https://linux-hardware.org/?probe=b426feb1d9) | Feb 11, 2022 |
| Acer          | Predator G9-792             | Notebook    | [a01c295f77](https://linux-hardware.org/?probe=a01c295f77) | Feb 09, 2022 |
| Acer          | Predator G9-792             | Notebook    | [c030ff8b96](https://linux-hardware.org/?probe=c030ff8b96) | Feb 09, 2022 |
| Dell          | Latitude E7250              | Notebook    | [a7ba3830f7](https://linux-hardware.org/?probe=a7ba3830f7) | Feb 07, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [3dbd4103ce](https://linux-hardware.org/?probe=3dbd4103ce) | Feb 06, 2022 |
| Dell          | 06CV2N A00                  | Desktop     | [b3be05cbce](https://linux-hardware.org/?probe=b3be05cbce) | Feb 06, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [190a99dd63](https://linux-hardware.org/?probe=190a99dd63) | Jan 31, 2022 |
| ASUSTek       | K45VM                       | Notebook    | [5cb4dcfe48](https://linux-hardware.org/?probe=5cb4dcfe48) | Jan 29, 2022 |
| ASUSTek       | K45VM                       | Notebook    | [39cac76612](https://linux-hardware.org/?probe=39cac76612) | Jan 28, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [a172ae51cf](https://linux-hardware.org/?probe=a172ae51cf) | Jan 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [efbe19b07b](https://linux-hardware.org/?probe=efbe19b07b) | Jan 20, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [6c19d2fbd6](https://linux-hardware.org/?probe=6c19d2fbd6) | Jan 11, 2022 |
| ASUSTek       | N501JW                      | Notebook    | [af9aaff7ee](https://linux-hardware.org/?probe=af9aaff7ee) | Jan 05, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [9309138e99](https://linux-hardware.org/?probe=9309138e99) | Dec 31, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [9f745065df](https://linux-hardware.org/?probe=9f745065df) | Dec 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [aae3ae242f](https://linux-hardware.org/?probe=aae3ae242f) | Dec 21, 2021 |
| Apple         | MacBookAir3,1               | Notebook    | [ef12425b00](https://linux-hardware.org/?probe=ef12425b00) | Dec 19, 2021 |
| ASRock        | B560M Pro4                  | Desktop     | [bd3ec294cb](https://linux-hardware.org/?probe=bd3ec294cb) | Dec 18, 2021 |
| Dell          | 0VD5HY A04                  | Desktop     | [2aaa0df82d](https://linux-hardware.org/?probe=2aaa0df82d) | Dec 18, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [b92a9a109f](https://linux-hardware.org/?probe=b92a9a109f) | Dec 18, 2021 |
| Dell          | 0HD5W2 A01                  | Desktop     | [72329a4b56](https://linux-hardware.org/?probe=72329a4b56) | Dec 17, 2021 |
| AMI           | Cherry Trail CR             | Desktop     | [96c2c68676](https://linux-hardware.org/?probe=96c2c68676) | Dec 16, 2021 |
| Dell          | 0C96W1 A02                  | Desktop     | [31f32bf184](https://linux-hardware.org/?probe=31f32bf184) | Dec 16, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [91b2a03d70](https://linux-hardware.org/?probe=91b2a03d70) | Dec 13, 2021 |
| Dell          | Inspiron 5580               | Notebook    | [29d56d5a5e](https://linux-hardware.org/?probe=29d56d5a5e) | Dec 06, 2021 |
| INET          | Z12B                        | Mini pc     | [a18fff612e](https://linux-hardware.org/?probe=a18fff612e) | Dec 05, 2021 |
| ASUSTek       | K501UX                      | Notebook    | [3f9b547c57](https://linux-hardware.org/?probe=3f9b547c57) | Dec 04, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [8876123555](https://linux-hardware.org/?probe=8876123555) | Nov 26, 2021 |
| MSI           | MPG Z690 CARBON WIFI        | Desktop     | [19812541db](https://linux-hardware.org/?probe=19812541db) | Nov 23, 2021 |
| MSI           | MPG Z690 CARBON WIFI        | Desktop     | [0eac4a44ef](https://linux-hardware.org/?probe=0eac4a44ef) | Nov 23, 2021 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [cf60dd841c](https://linux-hardware.org/?probe=cf60dd841c) | Nov 10, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [97e66fa893](https://linux-hardware.org/?probe=97e66fa893) | Nov 09, 2021 |
| Dell          | 0XCR8D A03                  | Desktop     | [97e2f36d1f](https://linux-hardware.org/?probe=97e2f36d1f) | Nov 07, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [5d9f112e39](https://linux-hardware.org/?probe=5d9f112e39) | Nov 07, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [8e3c5b2ef0](https://linux-hardware.org/?probe=8e3c5b2ef0) | Nov 03, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [4b9f5aed33](https://linux-hardware.org/?probe=4b9f5aed33) | Nov 01, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [9ad082f18e](https://linux-hardware.org/?probe=9ad082f18e) | Nov 01, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [7ad1f07edb](https://linux-hardware.org/?probe=7ad1f07edb) | Oct 21, 2021 |
| congatec      | conga-MA5 B.2               | Mini pc     | [a393bc32f9](https://linux-hardware.org/?probe=a393bc32f9) | Oct 18, 2021 |
| congatec      | conga-MA5 B.2               | Mini pc     | [10851c579f](https://linux-hardware.org/?probe=10851c579f) | Oct 16, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [6edbff3019](https://linux-hardware.org/?probe=6edbff3019) | Oct 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [5ac27f4e29](https://linux-hardware.org/?probe=5ac27f4e29) | Oct 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [6e2173f8b4](https://linux-hardware.org/?probe=6e2173f8b4) | Sep 30, 2021 |
| ASUSTek       | UX32LA                      | Notebook    | [9763fb0928](https://linux-hardware.org/?probe=9763fb0928) | Sep 25, 2021 |
| ASUSTek       | UX32LA                      | Notebook    | [e97b7fce6b](https://linux-hardware.org/?probe=e97b7fce6b) | Sep 25, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [3d0115d011](https://linux-hardware.org/?probe=3d0115d011) | Sep 15, 2021 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [e1c9dadb12](https://linux-hardware.org/?probe=e1c9dadb12) | Sep 12, 2021 |
| Acer          | Aspire 6935                 | Notebook    | [fc440eee50](https://linux-hardware.org/?probe=fc440eee50) | Sep 12, 2021 |
| Acer          | Aspire 6935                 | Notebook    | [24cfb86539](https://linux-hardware.org/?probe=24cfb86539) | Sep 12, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [02983fa577](https://linux-hardware.org/?probe=02983fa577) | Sep 08, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [6daf2c7553](https://linux-hardware.org/?probe=6daf2c7553) | Sep 04, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [bea89f1164](https://linux-hardware.org/?probe=bea89f1164) | Sep 04, 2021 |
| ASRock        | Z77 Extreme3                | Desktop     | [0e95fc1e3d](https://linux-hardware.org/?probe=0e95fc1e3d) | Sep 03, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [b7ff195931](https://linux-hardware.org/?probe=b7ff195931) | Sep 02, 2021 |
| Dell          | Precision 7560              | Notebook    | [75c607555e](https://linux-hardware.org/?probe=75c607555e) | Aug 27, 2021 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | Desktop     | [adf156f9db](https://linux-hardware.org/?probe=adf156f9db) | Aug 26, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [d97a42e31e](https://linux-hardware.org/?probe=d97a42e31e) | Aug 26, 2021 |
| Lenovo        | NOK                         | Desktop     | [274005087d](https://linux-hardware.org/?probe=274005087d) | Aug 23, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [606b3cf160](https://linux-hardware.org/?probe=606b3cf160) | Aug 23, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f4ec2b8446](https://linux-hardware.org/?probe=f4ec2b8446) | Aug 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [a613776a9c](https://linux-hardware.org/?probe=a613776a9c) | Aug 18, 2021 |
| Acer          | Nitro AN515-43              | Notebook    | [d0952296d7](https://linux-hardware.org/?probe=d0952296d7) | Aug 17, 2021 |
| Dell          | Inspiron 7370               | Notebook    | [b702f17a07](https://linux-hardware.org/?probe=b702f17a07) | Aug 17, 2021 |
| Acer          | Swift SF314-57G             | Notebook    | [a5f10ae10b](https://linux-hardware.org/?probe=a5f10ae10b) | Aug 17, 2021 |
| Biostar       | TB250-BTC+                  | Desktop     | [f45d61ab64](https://linux-hardware.org/?probe=f45d61ab64) | Jul 31, 2021 |
| Dell          | 0NKW6Y A00                  | Desktop     | [85f066488a](https://linux-hardware.org/?probe=85f066488a) | Jul 29, 2021 |
| Dell          | 0NKW6Y A00                  | Desktop     | [fd1285b7f2](https://linux-hardware.org/?probe=fd1285b7f2) | Jul 29, 2021 |
| Lenovo        | IdeaPad S530 13IML 81WU     | Notebook    | [978dbea880](https://linux-hardware.org/?probe=978dbea880) | Jul 27, 2021 |
| Lenovo        | IdeaPad S530 13IML 81WU     | Notebook    | [e3c0726e19](https://linux-hardware.org/?probe=e3c0726e19) | Jul 27, 2021 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [e74f010570](https://linux-hardware.org/?probe=e74f010570) | Jul 26, 2021 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [f938836ae3](https://linux-hardware.org/?probe=f938836ae3) | Jul 24, 2021 |
| Toshiba       | PORTEGE R930                | Notebook    | [6141314610](https://linux-hardware.org/?probe=6141314610) | Jul 22, 2021 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [502fe1bf66](https://linux-hardware.org/?probe=502fe1bf66) | Jul 19, 2021 |
| MSI           | A68HM-E33 V2                | Desktop     | [983bc90bc7](https://linux-hardware.org/?probe=983bc90bc7) | Jul 14, 2021 |
| ASUSTek       | K45VM                       | Notebook    | [6d08e71c4e](https://linux-hardware.org/?probe=6d08e71c4e) | Jul 07, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [f4778083d9](https://linux-hardware.org/?probe=f4778083d9) | Jul 02, 2021 |
| Acer          | Swift SF314-41G             | Notebook    | [fe5e126da1](https://linux-hardware.org/?probe=fe5e126da1) | Jul 01, 2021 |
| Acer          | Aspire one                  | Notebook    | [adae8c183d](https://linux-hardware.org/?probe=adae8c183d) | Jun 22, 2021 |
| LattePanda    | Alpha                       | Desktop     | [1d9daab9aa](https://linux-hardware.org/?probe=1d9daab9aa) | Jun 20, 2021 |
| LattePanda    | Alpha                       | Desktop     | [e9ef19ed6e](https://linux-hardware.org/?probe=e9ef19ed6e) | Jun 20, 2021 |
| Sony          | VPCSB36FG                   | Notebook    | [c834499816](https://linux-hardware.org/?probe=c834499816) | Jun 10, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [650e1b9bf5](https://linux-hardware.org/?probe=650e1b9bf5) | Jun 05, 2021 |
| Dell          | Latitude 7490               | Notebook    | [879fc7a838](https://linux-hardware.org/?probe=879fc7a838) | May 27, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [8bf489a0cb](https://linux-hardware.org/?probe=8bf489a0cb) | May 26, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [e16504b6f4](https://linux-hardware.org/?probe=e16504b6f4) | May 25, 2021 |
| HP            | 198E                        | Desktop     | [a44ce74aaa](https://linux-hardware.org/?probe=a44ce74aaa) | May 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [920ef637b1](https://linux-hardware.org/?probe=920ef637b1) | May 21, 2021 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [c9c9d02ede](https://linux-hardware.org/?probe=c9c9d02ede) | May 20, 2021 |
| Sony          | VPCSB36FG                   | Notebook    | [828a8ac75d](https://linux-hardware.org/?probe=828a8ac75d) | May 18, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [ffa207ed1e](https://linux-hardware.org/?probe=ffa207ed1e) | May 14, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [d2d2eb910a](https://linux-hardware.org/?probe=d2d2eb910a) | May 12, 2021 |
| Gigabyte      | H81M-DS2                    | Desktop     | [589d53b7ce](https://linux-hardware.org/?probe=589d53b7ce) | May 11, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [c17ba8c1a6](https://linux-hardware.org/?probe=c17ba8c1a6) | May 04, 2021 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [e20da66200](https://linux-hardware.org/?probe=e20da66200) | Apr 17, 2021 |
| ASRock        | HM55-MXM                    | Desktop     | [e56d216ab7](https://linux-hardware.org/?probe=e56d216ab7) | Apr 14, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [46bb05613f](https://linux-hardware.org/?probe=46bb05613f) | Apr 13, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [ecc3dfa09a](https://linux-hardware.org/?probe=ecc3dfa09a) | Apr 13, 2021 |
| Lenovo        | ThinkCentre M90p 5864BM3    | Desktop     | [666e4f970e](https://linux-hardware.org/?probe=666e4f970e) | Apr 10, 2021 |
| Dell          | 0D6H9T A00                  | Desktop     | [94d321f020](https://linux-hardware.org/?probe=94d321f020) | Apr 02, 2021 |
| Foxconn       | Kangaroo Mobile Desktop     | Notebook    | [e26f3c0f44](https://linux-hardware.org/?probe=e26f3c0f44) | Mar 29, 2021 |
| Foxconn       | Kangaroo Mobile Desktop     | Notebook    | [e4c813c694](https://linux-hardware.org/?probe=e4c813c694) | Mar 29, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [ce138f71dd](https://linux-hardware.org/?probe=ce138f71dd) | Mar 15, 2021 |
| Toshiba       | PORTEGE R930                | Notebook    | [6e5981a1c8](https://linux-hardware.org/?probe=6e5981a1c8) | Mar 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [81b4d6916d](https://linux-hardware.org/?probe=81b4d6916d) | Mar 11, 2021 |
| Acer          | Swift SF314-56G             | Notebook    | [46ff93e8b8](https://linux-hardware.org/?probe=46ff93e8b8) | Mar 09, 2021 |
| Acer          | Swift SF314-56G             | Notebook    | [98a5817785](https://linux-hardware.org/?probe=98a5817785) | Mar 09, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [820e208bca](https://linux-hardware.org/?probe=820e208bca) | Mar 05, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [d8b4e607e1](https://linux-hardware.org/?probe=d8b4e607e1) | Mar 02, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [eca0e7f55f](https://linux-hardware.org/?probe=eca0e7f55f) | Mar 02, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [9eff035231](https://linux-hardware.org/?probe=9eff035231) | Mar 01, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [e6cb859b40](https://linux-hardware.org/?probe=e6cb859b40) | Feb 21, 2021 |
| Lenovo        | ThinkPad X395 20NL000TCD    | Notebook    | [eb33727eff](https://linux-hardware.org/?probe=eb33727eff) | Feb 18, 2021 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | Notebook    | [b2795c1a02](https://linux-hardware.org/?probe=b2795c1a02) | Feb 13, 2021 |
| Acer          | Swift SF314-56G             | Notebook    | [e67e7f24e8](https://linux-hardware.org/?probe=e67e7f24e8) | Feb 11, 2021 |
| Lenovo        | ThinkPad X220 4286C11       | Notebook    | [cbb8e959b4](https://linux-hardware.org/?probe=cbb8e959b4) | Feb 05, 2021 |
| Lenovo        | ThinkPad X220 4286C11       | Notebook    | [a8f5211aee](https://linux-hardware.org/?probe=a8f5211aee) | Feb 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [f4505630e3](https://linux-hardware.org/?probe=f4505630e3) | Feb 03, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [563ceb4238](https://linux-hardware.org/?probe=563ceb4238) | Jan 28, 2021 |
| Foxconn       | Kangaroo Mobile Desktop     | Notebook    | [0e5eeb215d](https://linux-hardware.org/?probe=0e5eeb215d) | Jan 28, 2021 |
| ASUSTek       | UX360UAK                    | Convertible | [93b1606116](https://linux-hardware.org/?probe=93b1606116) | Jan 27, 2021 |
| Lenovo        | RESCUER R720-15IKBN 80WW    | Notebook    | [15d05a517c](https://linux-hardware.org/?probe=15d05a517c) | Jan 23, 2021 |
| Notebook      | P65_P67SE                   | Notebook    | [1b4cd968fd](https://linux-hardware.org/?probe=1b4cd968fd) | Jan 22, 2021 |
| Lenovo        | ThinkPad X395 20NL000TCD    | Notebook    | [08990229db](https://linux-hardware.org/?probe=08990229db) | Jan 17, 2021 |
| Lenovo        | ThinkPad X395 20NL000TCD    | Notebook    | [dc6edb4a25](https://linux-hardware.org/?probe=dc6edb4a25) | Jan 14, 2021 |
| Dell          | G3 3500                     | Notebook    | [27386ee67b](https://linux-hardware.org/?probe=27386ee67b) | Jan 12, 2021 |
| Dell          | 00V62H A01                  | Desktop     | [e08b05c812](https://linux-hardware.org/?probe=e08b05c812) | Jan 09, 2021 |
| Lenovo        | ThinkPad E14 20RA0058VA     | Notebook    | [3c08ce49f5](https://linux-hardware.org/?probe=3c08ce49f5) | Jan 08, 2021 |
| Intel         | NUC10i7FNB K61360-305       | Mini pc     | [10b66f86e5](https://linux-hardware.org/?probe=10b66f86e5) | Jan 04, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [e5b808ee57](https://linux-hardware.org/?probe=e5b808ee57) | Jan 02, 2021 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | Notebook    | [4b19f38fcd](https://linux-hardware.org/?probe=4b19f38fcd) | Jan 02, 2021 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [3f041f4b71](https://linux-hardware.org/?probe=3f041f4b71) | Jan 01, 2021 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | Notebook    | [c30d1c7374](https://linux-hardware.org/?probe=c30d1c7374) | Dec 31, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [ccd41dd67e](https://linux-hardware.org/?probe=ccd41dd67e) | Dec 28, 2020 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [2fd914ada2](https://linux-hardware.org/?probe=2fd914ada2) | Dec 25, 2020 |
| Microsoft     | Surface Pro                 | Tablet      | [38d64b5845](https://linux-hardware.org/?probe=38d64b5845) | Dec 22, 2020 |
| Acer          | Aspire one                  | Notebook    | [556332908d](https://linux-hardware.org/?probe=556332908d) | Dec 14, 2020 |
| ASUSTek       | P9D-X Series                | Server      | [519b6669d2](https://linux-hardware.org/?probe=519b6669d2) | Dec 11, 2020 |
| Lenovo        | ThinkPad T400 2768CJ6       | Notebook    | [1d878eeb02](https://linux-hardware.org/?probe=1d878eeb02) | Dec 10, 2020 |
| HP            | ProBook 440 G4              | Notebook    | [e28bcb99e5](https://linux-hardware.org/?probe=e28bcb99e5) | Dec 07, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [ca915222e5](https://linux-hardware.org/?probe=ca915222e5) | Dec 07, 2020 |
| Dell          | 0D02VH A01                  | Desktop     | [1d822ef5a3](https://linux-hardware.org/?probe=1d822ef5a3) | Dec 07, 2020 |
| ASUSTek       | K45VM                       | Notebook    | [9dedb35f93](https://linux-hardware.org/?probe=9dedb35f93) | Dec 04, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [b9461ebddd](https://linux-hardware.org/?probe=b9461ebddd) | Nov 29, 2020 |
| Aftershock    | N15_N17RF1                  | Notebook    | [09b42b449a](https://linux-hardware.org/?probe=09b42b449a) | Nov 27, 2020 |
| Dell          | Precision 7530              | Notebook    | [6ea3afdb4a](https://linux-hardware.org/?probe=6ea3afdb4a) | Nov 26, 2020 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [1250c7dfbe](https://linux-hardware.org/?probe=1250c7dfbe) | Nov 25, 2020 |
| Lenovo        | ThinkPad X220 42911H8       | Notebook    | [cc79643d27](https://linux-hardware.org/?probe=cc79643d27) | Nov 22, 2020 |
| Dell          | Latitude 7400               | Notebook    | [3154149e40](https://linux-hardware.org/?probe=3154149e40) | Nov 21, 2020 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [93678477d7](https://linux-hardware.org/?probe=93678477d7) | Nov 20, 2020 |
| Lenovo        | ThinkPad X220 42911H8       | Notebook    | [c0ab31022d](https://linux-hardware.org/?probe=c0ab31022d) | Nov 20, 2020 |
| Dell          | 0D441T A03                  | Desktop     | [b57394e325](https://linux-hardware.org/?probe=b57394e325) | Nov 20, 2020 |
| ASUSTek       | E3M-ET V5 SERIES            | Desktop     | [f1faffa793](https://linux-hardware.org/?probe=f1faffa793) | Nov 20, 2020 |
| ASUSTek       | E3M-ET V5 SERIES            | Desktop     | [e727ca80a6](https://linux-hardware.org/?probe=e727ca80a6) | Nov 20, 2020 |
| HP            | 81C6 MVB 0C                 | Server      | [298cea57e1](https://linux-hardware.org/?probe=298cea57e1) | Nov 19, 2020 |
| Dell          | Inspiron 5379               | Notebook    | [63815d0103](https://linux-hardware.org/?probe=63815d0103) | Nov 15, 2020 |
| ASUSTek       | M4A78-EM-1394               | Desktop     | [3736bdc191](https://linux-hardware.org/?probe=3736bdc191) | Nov 12, 2020 |
| ASRock        | H110M-HDS R3.0              | Desktop     | [7dea4e7c04](https://linux-hardware.org/?probe=7dea4e7c04) | Nov 10, 2020 |
| Fujitsu       | LIFEBOOK SH561              | Notebook    | [759718c54b](https://linux-hardware.org/?probe=759718c54b) | Nov 10, 2020 |
| Lenovo        | ThinkPad X240 20AMS00100    | Notebook    | [f3f5326846](https://linux-hardware.org/?probe=f3f5326846) | Nov 08, 2020 |
| Dell          | Inspiron 3421               | Notebook    | [e08c38affc](https://linux-hardware.org/?probe=e08c38affc) | Nov 04, 2020 |
| HP            | 81C6 MVB 0C                 | Server      | [eaa10c5051](https://linux-hardware.org/?probe=eaa10c5051) | Oct 29, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [14cf318590](https://linux-hardware.org/?probe=14cf318590) | Oct 29, 2020 |
| Acer          | Swift SF314-54              | Notebook    | [35aa366265](https://linux-hardware.org/?probe=35aa366265) | Oct 18, 2020 |
| Acer          | ConceptD CN715-71           | Notebook    | [8396c1d9e6](https://linux-hardware.org/?probe=8396c1d9e6) | Oct 13, 2020 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [b47f8da412](https://linux-hardware.org/?probe=b47f8da412) | Oct 09, 2020 |
| ASRock        | 990FX Killer                | Desktop     | [4faf15fe7f](https://linux-hardware.org/?probe=4faf15fe7f) | Oct 08, 2020 |
| HP            | Compaq 6510b                | Notebook    | [cf190a85ea](https://linux-hardware.org/?probe=cf190a85ea) | Oct 08, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2dada3cfbe](https://linux-hardware.org/?probe=2dada3cfbe) | Sep 30, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c0f7498f1b](https://linux-hardware.org/?probe=c0f7498f1b) | Sep 30, 2020 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [f542320df7](https://linux-hardware.org/?probe=f542320df7) | Sep 28, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [05ef194f79](https://linux-hardware.org/?probe=05ef194f79) | Sep 28, 2020 |
| Lenovo        | ThinkPad X240 20AMS00100    | Notebook    | [78566669f0](https://linux-hardware.org/?probe=78566669f0) | Sep 27, 2020 |
| ASUSTek       | T300LA                      | Notebook    | [9ca4cba592](https://linux-hardware.org/?probe=9ca4cba592) | Sep 27, 2020 |
| Dell          | Inspiron 3476               | Notebook    | [021351472c](https://linux-hardware.org/?probe=021351472c) | Sep 26, 2020 |
| ASUSTek       | M3A78-EM                    | Desktop     | [65ed8bba9c](https://linux-hardware.org/?probe=65ed8bba9c) | Sep 23, 2020 |
| HP            | Compaq 6510b                | Notebook    | [9b9a4b4614](https://linux-hardware.org/?probe=9b9a4b4614) | Sep 22, 2020 |
| HP            | Compaq 6510b                | Notebook    | [3487aab3a6](https://linux-hardware.org/?probe=3487aab3a6) | Sep 20, 2020 |
| HP            | Compaq 6510b                | Notebook    | [b7382d2141](https://linux-hardware.org/?probe=b7382d2141) | Sep 19, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [4a4a01267c](https://linux-hardware.org/?probe=4a4a01267c) | Sep 18, 2020 |
| ASUSTek       | UX305CA                     | Notebook    | [dc9532c57b](https://linux-hardware.org/?probe=dc9532c57b) | Sep 12, 2020 |
| Samsung       | 305U1A                      | Notebook    | [9949d76953](https://linux-hardware.org/?probe=9949d76953) | Sep 09, 2020 |
| Samsung       | 305U1A                      | Notebook    | [9dbf37ad63](https://linux-hardware.org/?probe=9dbf37ad63) | Sep 09, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [cab06cdbd7](https://linux-hardware.org/?probe=cab06cdbd7) | Sep 07, 2020 |
| Acer          | Aspire A515-51G             | Notebook    | [c9d6ce6954](https://linux-hardware.org/?probe=c9d6ce6954) | Sep 05, 2020 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [db8a9ea1ef](https://linux-hardware.org/?probe=db8a9ea1ef) | Sep 04, 2020 |
| Aftershock    | N8xxEP6                     | Notebook    | [d8e9d4edfd](https://linux-hardware.org/?probe=d8e9d4edfd) | Sep 04, 2020 |
| Gigabyte      | 945GZM-S2                   | Desktop     | [56d2f5c077](https://linux-hardware.org/?probe=56d2f5c077) | Sep 03, 2020 |
| Dell          | Precision 7530              | Notebook    | [91306b715e](https://linux-hardware.org/?probe=91306b715e) | Sep 03, 2020 |
| Aftershock    | N15_N17RF1                  | Notebook    | [e3e85f51cc](https://linux-hardware.org/?probe=e3e85f51cc) | Sep 03, 2020 |
| Dell          | Latitude 5400               | Notebook    | [498b1be7bd](https://linux-hardware.org/?probe=498b1be7bd) | Sep 02, 2020 |
| Gigabyte      | 945GZM-S2                   | Desktop     | [3a8e991dee](https://linux-hardware.org/?probe=3a8e991dee) | Sep 01, 2020 |
| Toshiba       | PORTEGE R930                | Notebook    | [64ba8fde9d](https://linux-hardware.org/?probe=64ba8fde9d) | Aug 31, 2020 |
| Toshiba       | PORTEGE R930                | Notebook    | [b37b0d860d](https://linux-hardware.org/?probe=b37b0d860d) | Aug 31, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d6a3031f11](https://linux-hardware.org/?probe=d6a3031f11) | Aug 30, 2020 |
| Lenovo        | Yoga 3 14 80JH              | Notebook    | [3623866056](https://linux-hardware.org/?probe=3623866056) | Aug 28, 2020 |
| HP            | Compaq 6510b                | Notebook    | [7db74443d5](https://linux-hardware.org/?probe=7db74443d5) | Aug 25, 2020 |
| HP            | Compaq 6510b                | Notebook    | [20f281e6e5](https://linux-hardware.org/?probe=20f281e6e5) | Aug 25, 2020 |
| HP            | Compaq 6510b                | Notebook    | [2791e33d53](https://linux-hardware.org/?probe=2791e33d53) | Aug 24, 2020 |
| ASUSTek       | V200IB                      | All in one  | [16748c4ba8](https://linux-hardware.org/?probe=16748c4ba8) | Aug 23, 2020 |
| ASUSTek       | ZenBook UX434FLC_UX433FL... | Notebook    | [8bc9e504d7](https://linux-hardware.org/?probe=8bc9e504d7) | Aug 13, 2020 |
| Toshiba       | PORTEGE R930                | Notebook    | [9f944b581d](https://linux-hardware.org/?probe=9f944b581d) | Aug 09, 2020 |
| Sony          | VGN-CR32G_W                 | Notebook    | [faf8f6a6fa](https://linux-hardware.org/?probe=faf8f6a6fa) | Aug 08, 2020 |
| Sony          | VGN-CR32G_W                 | Notebook    | [421ed7dcba](https://linux-hardware.org/?probe=421ed7dcba) | Aug 08, 2020 |
| MECHREVO      | Code 01 Series PF5NU1G      | Notebook    | [4dffd28998](https://linux-hardware.org/?probe=4dffd28998) | Aug 07, 2020 |
| Lenovo        | ThinkPad X230 23257VA       | Notebook    | [4319315cd0](https://linux-hardware.org/?probe=4319315cd0) | Jul 25, 2020 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [efb532b71e](https://linux-hardware.org/?probe=efb532b71e) | Jul 24, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [b6111e69ca](https://linux-hardware.org/?probe=b6111e69ca) | Jul 19, 2020 |
| ASRock        | HM55-MXM                    | Desktop     | [7f12e5a53c](https://linux-hardware.org/?probe=7f12e5a53c) | Jul 19, 2020 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [b554a2c8ec](https://linux-hardware.org/?probe=b554a2c8ec) | Jul 14, 2020 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [6d5b75622f](https://linux-hardware.org/?probe=6d5b75622f) | Jul 10, 2020 |
| HP            | Pavilion dv6000 (GF659EA... | Notebook    | [84a4ec9209](https://linux-hardware.org/?probe=84a4ec9209) | Jul 09, 2020 |
| HP            | EliteBook 725 G4            | Notebook    | [941e94f528](https://linux-hardware.org/?probe=941e94f528) | Jul 09, 2020 |
| Lenovo        | ThinkPad T490 20N3S5DU27    | Notebook    | [d4bb886295](https://linux-hardware.org/?probe=d4bb886295) | Jul 08, 2020 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [16b4aed55f](https://linux-hardware.org/?probe=16b4aed55f) | Jul 07, 2020 |
| Dell          | XPS 13 9370                 | Notebook    | [e794850de2](https://linux-hardware.org/?probe=e794850de2) | Jul 05, 2020 |
| HP            | EliteBook 725 G4            | Notebook    | [b3e1336d2f](https://linux-hardware.org/?probe=b3e1336d2f) | Jul 04, 2020 |
| Acer          | Swift SF514-54GT            | Notebook    | [a5b63702a2](https://linux-hardware.org/?probe=a5b63702a2) | Jul 03, 2020 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [3769ee6e50](https://linux-hardware.org/?probe=3769ee6e50) | Jul 01, 2020 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [121efa47d4](https://linux-hardware.org/?probe=121efa47d4) | Jul 01, 2020 |
| Lenovo        | ThinkPad T420s 417429U      | Notebook    | [8d9ec3fd6e](https://linux-hardware.org/?probe=8d9ec3fd6e) | Jun 27, 2020 |
| ASUSTek       | UX305CA                     | Notebook    | [7b35a1c840](https://linux-hardware.org/?probe=7b35a1c840) | Jun 26, 2020 |
| Toshiba       | PORTEGE Z10t-A              | Notebook    | [dd0834c2dd](https://linux-hardware.org/?probe=dd0834c2dd) | Jun 23, 2020 |
| ECS           | H61H2-MV                    | Desktop     | [a4ebb57c65](https://linux-hardware.org/?probe=a4ebb57c65) | Jun 19, 2020 |
| Lenovo        | IdeaPad U460 20056          | Notebook    | [31c7edc616](https://linux-hardware.org/?probe=31c7edc616) | Jun 17, 2020 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [5d31ba79a1](https://linux-hardware.org/?probe=5d31ba79a1) | Jun 17, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [2c22387cdf](https://linux-hardware.org/?probe=2c22387cdf) | Jun 17, 2020 |
| ASUSTek       | ZenBook UX434FLC_UX433FL... | Notebook    | [4add01698f](https://linux-hardware.org/?probe=4add01698f) | Jun 14, 2020 |
| ASUSTek       | H87I-PLUS                   | Desktop     | [9e8603cab8](https://linux-hardware.org/?probe=9e8603cab8) | Jun 05, 2020 |
| Dell          | Latitude E7440              | Notebook    | [1664235765](https://linux-hardware.org/?probe=1664235765) | Jun 03, 2020 |
| Dell          | Latitude E7440              | Notebook    | [d71cf3dba2](https://linux-hardware.org/?probe=d71cf3dba2) | Jun 03, 2020 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [3da3ba498c](https://linux-hardware.org/?probe=3da3ba498c) | Jun 03, 2020 |
| ASRock        | H110M-HDS R3.0              | Desktop     | [8610132ae8](https://linux-hardware.org/?probe=8610132ae8) | Jun 03, 2020 |
| Lenovo        | G550 2958                   | Notebook    | [a8c4b1a8cf](https://linux-hardware.org/?probe=a8c4b1a8cf) | Jun 01, 2020 |
| ASUSTek       | H87I-PLUS                   | Desktop     | [74e66b2a4a](https://linux-hardware.org/?probe=74e66b2a4a) | May 30, 2020 |
| Lenovo        | ThinkPad L460 20FUCTO1WW    | Notebook    | [da2a23020c](https://linux-hardware.org/?probe=da2a23020c) | May 21, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [c91cd5679c](https://linux-hardware.org/?probe=c91cd5679c) | May 19, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [10e8823c6b](https://linux-hardware.org/?probe=10e8823c6b) | May 17, 2020 |
| ASUSTek       | Berkeley                    | Desktop     | [ebb35e1770](https://linux-hardware.org/?probe=ebb35e1770) | May 14, 2020 |
| ASUSTek       | Berkeley                    | Desktop     | [038ada5ee3](https://linux-hardware.org/?probe=038ada5ee3) | May 14, 2020 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [b56e1d0e1a](https://linux-hardware.org/?probe=b56e1d0e1a) | May 13, 2020 |
| ASUSTek       | Berkeley                    | Desktop     | [ea544afa99](https://linux-hardware.org/?probe=ea544afa99) | May 12, 2020 |
| ASUSTek       | Berkeley                    | Desktop     | [058ecc2781](https://linux-hardware.org/?probe=058ecc2781) | May 12, 2020 |
| Lenovo        | G550 2958                   | Notebook    | [4e4bcc14f1](https://linux-hardware.org/?probe=4e4bcc14f1) | May 11, 2020 |
| Lenovo        | G550 2958                   | Notebook    | [ea8d2d9296](https://linux-hardware.org/?probe=ea8d2d9296) | May 11, 2020 |
| Lenovo        | G550 2958                   | Notebook    | [cfd6e82a6f](https://linux-hardware.org/?probe=cfd6e82a6f) | May 11, 2020 |
| ASUSTek       | PRIME H310M-A               | Desktop     | [aaed21ffd0](https://linux-hardware.org/?probe=aaed21ffd0) | May 08, 2020 |
| Acer          | Predator PH315-52           | Notebook    | [7adb1a873c](https://linux-hardware.org/?probe=7adb1a873c) | May 04, 2020 |
| Lenovo        | ThinkPad X230 23257VA       | Notebook    | [09817eac19](https://linux-hardware.org/?probe=09817eac19) | May 01, 2020 |
| Lenovo        | ThinkPad T400 2768AA6       | Notebook    | [665d6e56af](https://linux-hardware.org/?probe=665d6e56af) | May 01, 2020 |
| Dell          | 06D7TR A00                  | Desktop     | [60b49366ed](https://linux-hardware.org/?probe=60b49366ed) | Apr 30, 2020 |
| ASUSTek       | T300LA                      | Notebook    | [c173e838c3](https://linux-hardware.org/?probe=c173e838c3) | Apr 26, 2020 |
| ASUSTek       | T300LA                      | Notebook    | [6311e7f4b5](https://linux-hardware.org/?probe=6311e7f4b5) | Apr 26, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [42636a47b1](https://linux-hardware.org/?probe=42636a47b1) | Apr 26, 2020 |
| ASUSTek       | ASUS Gaming FX570UD         | Notebook    | [a9cd8ef28f](https://linux-hardware.org/?probe=a9cd8ef28f) | Apr 22, 2020 |
| Acer          | Prespa1                     | Notebook    | [791259386e](https://linux-hardware.org/?probe=791259386e) | Apr 16, 2020 |
| Lenovo        | ThinkPad X1 Yoga 4th 20S... | Convertible | [d5124038f4](https://linux-hardware.org/?probe=d5124038f4) | Apr 15, 2020 |
| Lenovo        | ThinkPad X1 Yoga 4th 20S... | Convertible | [7e6120b5c7](https://linux-hardware.org/?probe=7e6120b5c7) | Apr 10, 2020 |
| Lenovo        | B50-30 20382                | Notebook    | [57b8f867a1](https://linux-hardware.org/?probe=57b8f867a1) | Apr 09, 2020 |
| Acer          | Aspire E5-473G              | Notebook    | [17f3a0e473](https://linux-hardware.org/?probe=17f3a0e473) | Apr 08, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [429fde3ebd](https://linux-hardware.org/?probe=429fde3ebd) | Apr 02, 2020 |
| Dell          | Latitude E6410              | Notebook    | [920a80dc90](https://linux-hardware.org/?probe=920a80dc90) | Mar 31, 2020 |
| Apple         | MacBookPro11,4              | Notebook    | [3c9bd63848](https://linux-hardware.org/?probe=3c9bd63848) | Mar 30, 2020 |
| Acer          | ConceptD CN715-71           | Notebook    | [2a99d0f76b](https://linux-hardware.org/?probe=2a99d0f76b) | Mar 28, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [26486f2fff](https://linux-hardware.org/?probe=26486f2fff) | Mar 24, 2020 |
| Acer          | ConceptD CN715-71           | Notebook    | [93d970f678](https://linux-hardware.org/?probe=93d970f678) | Mar 24, 2020 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [daa4d098dc](https://linux-hardware.org/?probe=daa4d098dc) | Mar 13, 2020 |
| Dell          | 0X8DXD A01                  | Desktop     | [37012211e0](https://linux-hardware.org/?probe=37012211e0) | Mar 05, 2020 |
| Dell          | 00V62H A01                  | Desktop     | [001695659e](https://linux-hardware.org/?probe=001695659e) | Mar 04, 2020 |
| Dell          | 00V62H A01                  | Desktop     | [199fc82812](https://linux-hardware.org/?probe=199fc82812) | Mar 04, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th E... | Notebook    | [b913bc5cc5](https://linux-hardware.org/?probe=b913bc5cc5) | Feb 18, 2020 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [819116ee69](https://linux-hardware.org/?probe=819116ee69) | Feb 16, 2020 |
| Acer          | ConceptD CN715-71           | Notebook    | [93c40180a2](https://linux-hardware.org/?probe=93c40180a2) | Feb 11, 2020 |
| Acer          | ConceptD CN715-71           | Notebook    | [f6c3a576c2](https://linux-hardware.org/?probe=f6c3a576c2) | Feb 11, 2020 |
| Lenovo        | ThinkPad W540 20BG001KUK    | Notebook    | [627909b9e5](https://linux-hardware.org/?probe=627909b9e5) | Feb 04, 2020 |
| Dell          | Inspiron 7591               | Notebook    | [b33d5cddc5](https://linux-hardware.org/?probe=b33d5cddc5) | Jan 25, 2020 |
| Microsoft     | Surface Laptop 3            | Tablet      | [7910582d7c](https://linux-hardware.org/?probe=7910582d7c) | Jan 06, 2020 |
| Microsoft     | Surface Laptop 3            | Tablet      | [eb592eeb36](https://linux-hardware.org/?probe=eb592eeb36) | Jan 05, 2020 |
| Gigabyte      | Z270X-UD5-CF                | Desktop     | [a38c129cd9](https://linux-hardware.org/?probe=a38c129cd9) | Jan 04, 2020 |
| Acer          | Aspire X3950                | Desktop     | [fd467d33f5](https://linux-hardware.org/?probe=fd467d33f5) | Jan 03, 2020 |
| ASUSTek       | U24E                        | Notebook    | [563b794d8a](https://linux-hardware.org/?probe=563b794d8a) | Dec 23, 2019 |
| Lenovo        | ThinkPad T400 2768CJ6       | Notebook    | [011ab343ef](https://linux-hardware.org/?probe=011ab343ef) | Dec 22, 2019 |
| Lenovo        | ThinkPad T400 2768CJ6       | Notebook    | [bb9da61133](https://linux-hardware.org/?probe=bb9da61133) | Dec 21, 2019 |
| Acer          | ConceptD CN715-71           | Notebook    | [54109739eb](https://linux-hardware.org/?probe=54109739eb) | Dec 20, 2019 |
| Acer          | ConceptD CN715-71           | Notebook    | [5d75e45350](https://linux-hardware.org/?probe=5d75e45350) | Dec 20, 2019 |
| Acer          | ConceptD CN715-71           | Notebook    | [fb27c8cabb](https://linux-hardware.org/?probe=fb27c8cabb) | Dec 20, 2019 |
| Lenovo        | ThinkPad X395 20NL000TCD    | Notebook    | [adec400398](https://linux-hardware.org/?probe=adec400398) | Dec 19, 2019 |
| ASRock        | Z370 Pro4                   | Desktop     | [f681da046d](https://linux-hardware.org/?probe=f681da046d) | Dec 09, 2019 |
| Lenovo        | 30C0 SDK0J40697 WIN 3305... | Desktop     | [f35675231e](https://linux-hardware.org/?probe=f35675231e) | Dec 02, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [86221df903](https://linux-hardware.org/?probe=86221df903) | Nov 30, 2019 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [6bee5d9a22](https://linux-hardware.org/?probe=6bee5d9a22) | Nov 16, 2019 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [1b0467dde0](https://linux-hardware.org/?probe=1b0467dde0) | Nov 16, 2019 |
| Dell          | 0F3KHR A00                  | Desktop     | [636fbfdcb6](https://linux-hardware.org/?probe=636fbfdcb6) | Sep 22, 2019 |
| HP            | ZBook Studio G5             | Notebook    | [87503b1263](https://linux-hardware.org/?probe=87503b1263) | Aug 22, 2019 |
| ASUSTek       | X406UAR                     | Notebook    | [5e3ebad239](https://linux-hardware.org/?probe=5e3ebad239) | Jul 05, 2019 |
| Apple         | MacBookPro9,2               | Notebook    | [1d4494ee1f](https://linux-hardware.org/?probe=1d4494ee1f) | Jul 03, 2019 |
| Lenovo        | S20-30 20421                | Notebook    | [5c27867f6e](https://linux-hardware.org/?probe=5c27867f6e) | Jun 26, 2019 |
| Dell          | Inspiron 13-5378            | Notebook    | [f938ce631a](https://linux-hardware.org/?probe=f938ce631a) | Jun 17, 2019 |
| Dell          | Inspiron 13-5378            | Notebook    | [5e33156c57](https://linux-hardware.org/?probe=5e33156c57) | Jun 17, 2019 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [c6888a9735](https://linux-hardware.org/?probe=c6888a9735) | May 31, 2019 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [0ab22425ea](https://linux-hardware.org/?probe=0ab22425ea) | May 28, 2019 |
| Apple         | MacBookPro11,5              | Notebook    | [ab95788992](https://linux-hardware.org/?probe=ab95788992) | May 18, 2019 |
| ASUSTek       | S500CA                      | Notebook    | [c0218275f7](https://linux-hardware.org/?probe=c0218275f7) | Apr 28, 2019 |
| Microsoft     | Surface Pro 4               | Tablet      | [6a82c09344](https://linux-hardware.org/?probe=6a82c09344) | Apr 16, 2019 |
| Microsoft     | Surface Pro 4               | Tablet      | [037f7f95c0](https://linux-hardware.org/?probe=037f7f95c0) | Apr 15, 2019 |
| ASUSTek       | ET2020I                     | Desktop     | [a695a9c422](https://linux-hardware.org/?probe=a695a9c422) | Apr 07, 2019 |
| Acer          | AO751h                      | Notebook    | [0ee57513c5](https://linux-hardware.org/?probe=0ee57513c5) | Apr 07, 2019 |
| MSI           | X299 RAIDER                 | Desktop     | [3f982f3e86](https://linux-hardware.org/?probe=3f982f3e86) | Dec 04, 2018 |
| MSI           | X299 RAIDER                 | Desktop     | [1207b80721](https://linux-hardware.org/?probe=1207b80721) | Dec 04, 2018 |
| MSI           | Boston                      | Desktop     | [104569cafb](https://linux-hardware.org/?probe=104569cafb) | Oct 24, 2018 |
| MSI           | GE63VR 7RE                  | Notebook    | [635226b290](https://linux-hardware.org/?probe=635226b290) | May 31, 2018 |
| Lenovo        | ThinkPad W540 20BG001KUK    | Notebook    | [ecd2f8138f](https://linux-hardware.org/?probe=ecd2f8138f) | Dec 27, 2016 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 70        | 24.14%  |
| Ubuntu 18.04                 | 35        | 12.07%  |
| Ubuntu 22.04                 | 12        | 4.14%   |
| Fedora 33                    | 12        | 4.14%   |
| Pop!_OS 20.04                | 8         | 2.76%   |
| Arch Rolling                 | 8         | 2.76%   |
| Arch                         | 8         | 2.76%   |
| Debian 11                    | 7         | 2.41%   |
| Ubuntu 21.10                 | 5         | 1.72%   |
| Ubuntu 21.04                 | 5         | 1.72%   |
| Linux Mint 20                | 5         | 1.72%   |
| Xubuntu 20.04                | 4         | 1.38%   |
| Pop!_OS 21.04                | 4         | 1.38%   |
| OpenMandriva 4.3             | 4         | 1.38%   |
| KDE neon 20.04               | 4         | 1.38%   |
| Fedora 36                    | 4         | 1.38%   |
| Debian Testing               | 4         | 1.38%   |
| Pop!_OS 22.04                | 3         | 1.03%   |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 1.03%   |
| Manjaro                      | 3         | 1.03%   |
| Fedora 34                    | 3         | 1.03%   |
| Fedora 32                    | 3         | 1.03%   |
| ArcoLinux Rolling            | 3         | 1.03%   |
| Zorin 16                     | 2         | 0.69%   |
| Zorin 15                     | 2         | 0.69%   |
| Ubuntu 19.10                 | 2         | 0.69%   |
| Ubuntu 19.04                 | 2         | 0.69%   |
| Ubuntu 18.10                 | 2         | 0.69%   |
| Ubuntu 16.04                 | 2         | 0.69%   |
| Rocky Linux 8.5              | 2         | 0.69%   |
| Raspbian 10                  | 2         | 0.69%   |
| Pop!_OS 21.10                | 2         | 0.69%   |
| Pop!_OS 20.10                | 2         | 0.69%   |
| OpenMandriva 4.50            | 2         | 0.69%   |
| OpenMandriva 4.2             | 2         | 0.69%   |
| Manjaro 20.2                 | 2         | 0.69%   |
| Manjaro 20.1                 | 2         | 0.69%   |
| Lubuntu 20.04                | 2         | 0.69%   |
| Linux Mint 21                | 2         | 0.69%   |
| Kubuntu 20.10                | 2         | 0.69%   |
| Gentoo 2.6                   | 2         | 0.69%   |
| Fedora 35                    | 2         | 0.69%   |
| Fedora 31                    | 2         | 0.69%   |
| EndeavourOS Rolling          | 2         | 0.69%   |
| Xubuntu 21.04                | 1         | 0.34%   |
| Ubuntu MATE 20.04            | 1         | 0.34%   |
| Ubuntu Budgie 20.04          | 1         | 0.34%   |
| ROSA R8                      | 1         | 0.34%   |
| ROSA R11                     | 1         | 0.34%   |
| Rocky Linux 8.4              | 1         | 0.34%   |
| RHEL 8                       | 1         | 0.34%   |
| RHEL 7                       | 1         | 0.34%   |
| Q4OS 4                       | 1         | 0.34%   |
| OpenMandriva 4.1             | 1         | 0.34%   |
| Manjaro 21.3.0               | 1         | 0.34%   |
| Manjaro 18.0.4               | 1         | 0.34%   |
| Lubuntu 18.04                | 1         | 0.34%   |
| LMDE 4                       | 1         | 0.34%   |
| Linux Mint 20.3              | 1         | 0.34%   |
| Linux Mint 20.1              | 1         | 0.34%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 134       | 47.52%  |
| Fedora        | 23        | 8.16%   |
| Pop!_OS       | 19        | 6.74%   |
| Arch          | 15        | 5.32%   |
| Debian        | 14        | 4.96%   |
| OpenMandriva  | 9         | 3.19%   |
| Manjaro       | 8         | 2.84%   |
| Linux Mint    | 8         | 2.84%   |
| Xubuntu       | 5         | 1.77%   |
| Zorin         | 4         | 1.42%   |
| Kubuntu       | 4         | 1.42%   |
| KDE neon      | 4         | 1.42%   |
| Rocky Linux   | 3         | 1.06%   |
| openSUSE      | 3         | 1.06%   |
| Lubuntu       | 3         | 1.06%   |
| ArcoLinux     | 3         | 1.06%   |
| ROSA          | 2         | 0.71%   |
| RHEL          | 2         | 0.71%   |
| Raspbian      | 2         | 0.71%   |
| Gentoo        | 2         | 0.71%   |
| Endless       | 2         | 0.71%   |
| EndeavourOS   | 2         | 0.71%   |
| Clear Linux   | 2         | 0.71%   |
| Ubuntu MATE   | 1         | 0.35%   |
| Ubuntu Budgie | 1         | 0.35%   |
| Q4OS          | 1         | 0.35%   |
| LMDE          | 1         | 0.35%   |
| Kali          | 1         | 0.35%   |
| Garuda Linux  | 1         | 0.35%   |
| Devuan        | 1         | 0.35%   |
| Deepin        | 1         | 0.35%   |
| CentOS        | 1         | 0.35%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 5.9.8-200.fc33.x86_64        | 6         | 1.89%   |
| 5.4.0-48-generic             | 6         | 1.89%   |
| 5.4.0-42-generic             | 6         | 1.89%   |
| 5.4.0-40-generic             | 6         | 1.89%   |
| 5.4.0-37-generic             | 6         | 1.89%   |
| 5.4.0-29-generic             | 6         | 1.89%   |
| 5.4.0-52-generic             | 5         | 1.58%   |
| 5.11.0-43-generic            | 5         | 1.58%   |
| 5.4.0-65-generic             | 4         | 1.26%   |
| 5.3.0-62-generic             | 4         | 1.26%   |
| 5.16.7-desktop-1omv4003      | 4         | 1.26%   |
| 5.15.0-46-generic            | 4         | 1.26%   |
| 5.4.0-7634-generic           | 3         | 0.95%   |
| 5.4.0-47-generic             | 3         | 0.95%   |
| 5.4.0-26-generic             | 3         | 0.95%   |
| 5.3.0-51-generic             | 3         | 0.95%   |
| 5.15.0-43-generic            | 3         | 0.95%   |
| 5.13.0-40-generic            | 3         | 0.95%   |
| 5.13.0-28-generic            | 3         | 0.95%   |
| 5.11.0-38-generic            | 3         | 0.95%   |
| 5.11.0-37-generic            | 3         | 0.95%   |
| 5.11.0-25-generic            | 3         | 0.95%   |
| 5.10.0-11-amd64              | 3         | 0.95%   |
| 5.0.0-23-generic             | 3         | 0.95%   |
| 5.8.0-7630-generic           | 2         | 0.63%   |
| 5.8.0-53-generic             | 2         | 0.63%   |
| 5.8.0-48-generic             | 2         | 0.63%   |
| 5.8.0-43-generic             | 2         | 0.63%   |
| 5.4.51-v7l+                  | 2         | 0.63%   |
| 5.4.5-050405-generic         | 2         | 0.63%   |
| 5.4.0-96-generic             | 2         | 0.63%   |
| 5.4.0-81-generic             | 2         | 0.63%   |
| 5.4.0-7642-generic           | 2         | 0.63%   |
| 5.4.0-70-generic             | 2         | 0.63%   |
| 5.4.0-45-generic             | 2         | 0.63%   |
| 5.4.0-33-generic             | 2         | 0.63%   |
| 5.4.0-31-generic             | 2         | 0.63%   |
| 5.3.0-40-generic             | 2         | 0.63%   |
| 5.18.0-3-amd64               | 2         | 0.63%   |
| 5.18.0-2-amd64               | 2         | 0.63%   |
| 5.17.5-76051705-generic      | 2         | 0.63%   |
| 5.15.0-41-generic            | 2         | 0.63%   |
| 5.15.0-39-generic            | 2         | 0.63%   |
| 5.15.0-37-generic            | 2         | 0.63%   |
| 5.13.13-xanmod1              | 2         | 0.63%   |
| 5.13.0-37-generic            | 2         | 0.63%   |
| 5.13.0-30-generic            | 2         | 0.63%   |
| 5.13.0-19-generic            | 2         | 0.63%   |
| 5.12.7-desktop-1omv4003      | 2         | 0.63%   |
| 5.11.0-27-generic            | 2         | 0.63%   |
| 5.10.14-desktop-1omv4002     | 2         | 0.63%   |
| 5.0.0-36-generic             | 2         | 0.63%   |
| 5.0.0-15-generic             | 2         | 0.63%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 2         | 0.63%   |
| 4.18.0-15-generic            | 2         | 0.63%   |
| 4.15.0-72-generic            | 2         | 0.63%   |
| 5.9.9-200.fc33.x86_64        | 1         | 0.32%   |
| 5.9.16-200.fc33.x86_64       | 1         | 0.32%   |
| 5.9.15-200.fc33.x86_64       | 1         | 0.32%   |
| 5.9.11-3-MANJARO             | 1         | 0.32%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 67        | 22.19%  |
| 5.11.0  | 21        | 6.95%   |
| 5.13.0  | 17        | 5.63%   |
| 5.8.0   | 16        | 5.3%    |
| 5.15.0  | 15        | 4.97%   |
| 4.18.0  | 13        | 4.3%    |
| 5.3.0   | 12        | 3.97%   |
| 5.0.0   | 11        | 3.64%   |
| 4.15.0  | 10        | 3.31%   |
| 5.10.0  | 9         | 2.98%   |
| 5.9.8   | 6         | 1.99%   |
| 5.18.0  | 5         | 1.66%   |
| 5.16.7  | 4         | 1.32%   |
| 5.17.5  | 3         | 0.99%   |
| 5.13.13 | 3         | 0.99%   |
| 5.4.51  | 2         | 0.66%   |
| 5.4.5   | 2         | 0.66%   |
| 5.15.5  | 2         | 0.66%   |
| 5.13.12 | 2         | 0.66%   |
| 5.12.7  | 2         | 0.66%   |
| 5.10.14 | 2         | 0.66%   |
| 4.19.0  | 2         | 0.66%   |
| 3.10.0  | 2         | 0.66%   |
| 5.9.9   | 1         | 0.33%   |
| 5.9.16  | 1         | 0.33%   |
| 5.9.15  | 1         | 0.33%   |
| 5.9.11  | 1         | 0.33%   |
| 5.9.10  | 1         | 0.33%   |
| 5.8.7   | 1         | 0.33%   |
| 5.8.5   | 1         | 0.33%   |
| 5.8.4   | 1         | 0.33%   |
| 5.8.3   | 1         | 0.33%   |
| 5.8.18  | 1         | 0.33%   |
| 5.8.12  | 1         | 0.33%   |
| 5.8.11  | 1         | 0.33%   |
| 5.8.1   | 1         | 0.33%   |
| 5.7.0   | 1         | 0.33%   |
| 5.6.7   | 1         | 0.33%   |
| 5.6.5   | 1         | 0.33%   |
| 5.6.15  | 1         | 0.33%   |
| 5.6.0   | 1         | 0.33%   |
| 5.5.2   | 1         | 0.33%   |
| 5.5.0   | 1         | 0.33%   |
| 5.4.8   | 1         | 0.33%   |
| 5.4.78  | 1         | 0.33%   |
| 5.4.77  | 1         | 0.33%   |
| 5.4.70  | 1         | 0.33%   |
| 5.4.60  | 1         | 0.33%   |
| 5.4.12  | 1         | 0.33%   |
| 5.19.0  | 1         | 0.33%   |
| 5.18.7  | 1         | 0.33%   |
| 5.18.5  | 1         | 0.33%   |
| 5.18.2  | 1         | 0.33%   |
| 5.18.16 | 1         | 0.33%   |
| 5.18.14 | 1         | 0.33%   |
| 5.18.12 | 1         | 0.33%   |
| 5.18.10 | 1         | 0.33%   |
| 5.17.9  | 1         | 0.33%   |
| 5.17.6  | 1         | 0.33%   |
| 5.16.9  | 1         | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 76        | 25.5%   |
| 5.15    | 25        | 8.39%   |
| 5.13    | 25        | 8.39%   |
| 5.8     | 24        | 8.05%   |
| 5.11    | 23        | 7.72%   |
| 5.10    | 18        | 6.04%   |
| 4.18    | 13        | 4.36%   |
| 5.3     | 12        | 4.03%   |
| 5.0     | 12        | 4.03%   |
| 5.9     | 10        | 3.36%   |
| 5.18    | 10        | 3.36%   |
| 5.16    | 10        | 3.36%   |
| 4.15    | 10        | 3.36%   |
| 5.12    | 6         | 2.01%   |
| 5.17    | 5         | 1.68%   |
| 5.6     | 4         | 1.34%   |
| 5.14    | 3         | 1.01%   |
| 4.19    | 3         | 1.01%   |
| 5.5     | 2         | 0.67%   |
| 4.16    | 2         | 0.67%   |
| 3.10    | 2         | 0.67%   |
| 5.7     | 1         | 0.34%   |
| 5.19    | 1         | 0.34%   |
| 4.4     | 1         | 0.34%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 265       | 97.43%  |
| aarch64 | 3         | 1.1%    |
| i686    | 2         | 0.74%   |
| armv7l  | 2         | 0.74%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 165       | 57.89%  |
| Unknown         | 41        | 14.39%  |
| KDE5            | 33        | 11.58%  |
| X-Cinnamon      | 10        | 3.51%   |
| XFCE            | 7         | 2.46%   |
| KDE             | 6         | 2.11%   |
| Cinnamon        | 6         | 2.11%   |
| LXQt            | 4         | 1.4%    |
| Unity           | 3         | 1.05%   |
| i3              | 3         | 1.05%   |
| GNOME Classic   | 2         | 0.7%    |
| Budgie          | 2         | 0.7%    |
| MATE            | 1         | 0.35%   |
| KDE4            | 1         | 0.35%   |
| GNOME Flashback | 1         | 0.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 215       | 77.06%  |
| Wayland | 32        | 11.47%  |
| Unknown | 22        | 7.89%   |
| Tty     | 10        | 3.58%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 148       | 52.48%  |
| GDM     | 60        | 21.28%  |
| SDDM    | 32        | 11.35%  |
| GDM3    | 25        | 8.87%   |
| LightDM | 11        | 3.9%    |
| TDM     | 5         | 1.77%   |
| KDM     | 1         | 0.35%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_SG   | 111       | 40.22%  |
| en_US   | 103       | 37.32%  |
| Unknown | 23        | 8.33%   |
| C       | 9         | 3.26%   |
| zh_CN   | 6         | 2.17%   |
| en_IN   | 6         | 2.17%   |
| en_AU   | 5         | 1.81%   |
| de_DE   | 5         | 1.81%   |
| en_GB   | 4         | 1.45%   |
| ru_UA   | 1         | 0.36%   |
| fr_FR   | 1         | 0.36%   |
| en_PH   | 1         | 0.36%   |
| en_IE   | 1         | 0.36%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 180       | 65.93%  |
| BIOS | 93        | 34.07%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 226       | 82.18%  |
| Btrfs   | 20        | 7.27%   |
| Overlay | 10        | 3.64%   |
| Unknown | 10        | 3.64%   |
| Xfs     | 7         | 2.55%   |
| Zfs     | 2         | 0.73%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 150       | 54.74%  |
| GPT     | 114       | 41.61%  |
| MBR     | 10        | 3.65%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 244       | 87.46%  |
| Yes       | 35        | 12.54%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 183       | 67.03%  |
| Yes       | 90        | 32.97%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 51        | 18.75%  |
| Dell                    | 49        | 18.01%  |
| ASUSTek Computer        | 45        | 16.54%  |
| Acer                    | 22        | 8.09%   |
| Hewlett-Packard         | 20        | 7.35%   |
| Gigabyte Technology     | 13        | 4.78%   |
| MSI                     | 12        | 4.41%   |
| Apple                   | 11        | 4.04%   |
| ASRock                  | 9         | 3.31%   |
| Sony                    | 4         | 1.47%   |
| Raspberry Pi Foundation | 4         | 1.47%   |
| Intel                   | 4         | 1.47%   |
| Microsoft               | 3         | 1.1%    |
| congatec                | 3         | 1.1%    |
| Toshiba                 | 2         | 0.74%   |
| Timi                    | 2         | 0.74%   |
| Samsung Electronics     | 2         | 0.74%   |
| Foxconn                 | 2         | 0.74%   |
| AMI                     | 2         | 0.74%   |
| Aftershock              | 2         | 0.74%   |
| Razer                   | 1         | 0.37%   |
| Notebook                | 1         | 0.37%   |
| MECHREVO                | 1         | 0.37%   |
| LattePanda              | 1         | 0.37%   |
| INET                    | 1         | 0.37%   |
| Fujitsu                 | 1         | 0.37%   |
| ECS                     | 1         | 0.37%   |
| COPELION INTERNATIONAL  | 1         | 0.37%   |
| Biostar                 | 1         | 0.37%   |
| Unknown                 | 1         | 0.37%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Gigabyte X570 AORUS PRO WIFI                          | 3         | 1.1%    |
| congatec conga-MA5 B.2                                | 3         | 1.1%    |
| ASUS All Series                                       | 3         | 1.1%    |
| RPi Raspberry Pi 4 Model B Rev 1.4                    | 2         | 0.74%   |
| RPi Raspberry Pi 4 Model B Rev 1.2                    | 2         | 0.74%   |
| MSI MS-7C84                                           | 2         | 0.74%   |
| Lenovo ThinkPad X220 42911H8                          | 2         | 0.74%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ                      | 2         | 0.74%   |
| Lenovo IdeaPad S340-14API 81NB                        | 2         | 0.74%   |
| Intel NUC11PAHi7                                      | 2         | 0.74%   |
| HP Compaq 6510b                                       | 2         | 0.74%   |
| Gigabyte B550I AORUS PRO AX                           | 2         | 0.74%   |
| Foxconn Kangaroo Mobile Desktop                       | 2         | 0.74%   |
| Dell OptiPlex 990                                     | 2         | 0.74%   |
| Dell OptiPlex 9020                                    | 2         | 0.74%   |
| Dell Latitude 3320                                    | 2         | 0.74%   |
| Dell Latitude 3120                                    | 2         | 0.74%   |
| ASUS T300LA                                           | 2         | 0.74%   |
| ASUS ROG STRIX B550-I GAMING                          | 2         | 0.74%   |
| Apple MacBookPro8,1                                   | 2         | 0.74%   |
| Apple iMac19,1                                        | 2         | 0.74%   |
| Acer ConceptD CN715-71                                | 2         | 0.74%   |
| Toshiba PORTEGE Z10t-A                                | 1         | 0.37%   |
| Toshiba PORTEGE R930                                  | 1         | 0.37%   |
| Timi TM1701                                           | 1         | 0.37%   |
| Timi Redmi Book Pro 14 2022                           | 1         | 0.37%   |
| Sony VPCSB36FG                                        | 1         | 0.37%   |
| Sony VPCCA15FG                                        | 1         | 0.37%   |
| Sony VGN-CR32G_W                                      | 1         | 0.37%   |
| Sony SVF1531V8CW                                      | 1         | 0.37%   |
| Samsung RF510/RF410/RF710                             | 1         | 0.37%   |
| Samsung 305U1A                                        | 1         | 0.37%   |
| Razer Blade 15 Advanced Model (Early 2020) - RZ09-033 | 1         | 0.37%   |
| Notebook P65_P67SE                                    | 1         | 0.37%   |
| MSI MS-7D43                                           | 1         | 0.37%   |
| MSI MS-7D30                                           | 1         | 0.37%   |
| MSI MS-7C52                                           | 1         | 0.37%   |
| MSI MS-7C02                                           | 1         | 0.37%   |
| MSI MS-7A94                                           | 1         | 0.37%   |
| MSI MS-7A32                                           | 1         | 0.37%   |
| MSI MS-7821                                           | 1         | 0.37%   |
| MSI MS-7721                                           | 1         | 0.37%   |
| MSI KT308AA-AB4 SR5472CF                              | 1         | 0.37%   |
| MSI GE63VR 7RE                                        | 1         | 0.37%   |
| Microsoft Surface Pro 4                               | 1         | 0.37%   |
| Microsoft Surface Pro                                 | 1         | 0.37%   |
| Microsoft Surface Laptop 3                            | 1         | 0.37%   |
| MECHREVO Code 01 Series PF5NU1G                       | 1         | 0.37%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS                    | 1         | 0.37%   |
| Lenovo Yoga C640-13IML 81UE                           | 1         | 0.37%   |
| Lenovo Yoga 3 Pro-1370 80HE                           | 1         | 0.37%   |
| Lenovo Yoga 3 14 80JH                                 | 1         | 0.37%   |
| Lenovo ThinkStation P620 30E1S3VH00                   | 1         | 0.37%   |
| Lenovo ThinkStation P310 30ASS2WG00                   | 1         | 0.37%   |
| Lenovo ThinkPad X395 20NL000TCD                       | 1         | 0.37%   |
| Lenovo ThinkPad X240 20AMS00100                       | 1         | 0.37%   |
| Lenovo ThinkPad X230 23257VA                          | 1         | 0.37%   |
| Lenovo ThinkPad X220 Tablet 4298WBT                   | 1         | 0.37%   |
| Lenovo ThinkPad X220 4286C11                          | 1         | 0.37%   |
| Lenovo ThinkPad X1 Yoga 4th 20SBS03N00                | 1         | 0.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 27        | 9.93%   |
| Dell Inspiron       | 12        | 4.41%   |
| Dell Latitude       | 11        | 4.04%   |
| Dell OptiPlex       | 9         | 3.31%   |
| Acer Aspire         | 9         | 3.31%   |
| Dell XPS            | 8         | 2.94%   |
| HP Pavilion         | 7         | 2.57%   |
| Lenovo IdeaPad      | 6         | 2.21%   |
| ASUS VivoBook       | 6         | 2.21%   |
| Acer Swift          | 6         | 2.21%   |
| Dell Precision      | 5         | 1.84%   |
| RPi Raspberry       | 4         | 1.47%   |
| Lenovo Yoga         | 4         | 1.47%   |
| Lenovo Legion       | 4         | 1.47%   |
| ASUS ZenBook        | 4         | 1.47%   |
| ASUS ROG            | 4         | 1.47%   |
| Microsoft Surface   | 3         | 1.1%    |
| Lenovo ThinkCentre  | 3         | 1.1%    |
| HP EliteBook        | 3         | 1.1%    |
| Gigabyte X570       | 3         | 1.1%    |
| congatec conga-MA5  | 3         | 1.1%    |
| ASUS All            | 3         | 1.1%    |
| Toshiba PORTEGE     | 2         | 0.74%   |
| MSI MS-7C84         | 2         | 0.74%   |
| Lenovo ThinkStation | 2         | 0.74%   |
| Intel NUC11PAHi7    | 2         | 0.74%   |
| HP ZBook            | 2         | 0.74%   |
| HP ENVY             | 2         | 0.74%   |
| HP Compaq           | 2         | 0.74%   |
| Gigabyte B550I      | 2         | 0.74%   |
| Foxconn Kangaroo    | 2         | 0.74%   |
| ASUS TUF            | 2         | 0.74%   |
| ASUS T300LA         | 2         | 0.74%   |
| Apple MacBookPro8   | 2         | 0.74%   |
| Apple MacBookPro11  | 2         | 0.74%   |
| Apple iMac19        | 2         | 0.74%   |
| Acer Predator       | 2         | 0.74%   |
| Acer ConceptD       | 2         | 0.74%   |
| Timi TM1701         | 1         | 0.37%   |
| Timi Redmi          | 1         | 0.37%   |
| Sony VPCSB36FG      | 1         | 0.37%   |
| Sony VPCCA15FG      | 1         | 0.37%   |
| Sony VGN-CR32G      | 1         | 0.37%   |
| Sony SVF1531V8CW    | 1         | 0.37%   |
| Samsung RF510       | 1         | 0.37%   |
| Samsung 305U1A      | 1         | 0.37%   |
| Razer Blade         | 1         | 0.37%   |
| Notebook P65        | 1         | 0.37%   |
| MSI MS-7D43         | 1         | 0.37%   |
| MSI MS-7D30         | 1         | 0.37%   |
| MSI MS-7C52         | 1         | 0.37%   |
| MSI MS-7C02         | 1         | 0.37%   |
| MSI MS-7A94         | 1         | 0.37%   |
| MSI MS-7A32         | 1         | 0.37%   |
| MSI MS-7821         | 1         | 0.37%   |
| MSI MS-7721         | 1         | 0.37%   |
| MSI KT308AA-AB4     | 1         | 0.37%   |
| MSI GE63VR          | 1         | 0.37%   |
| MECHREVO Code       | 1         | 0.37%   |
| Lenovo ThinkBook    | 1         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 41        | 15.07%  |
| 2020    | 36        | 13.24%  |
| 2018    | 34        | 12.5%   |
| 2021    | 20        | 7.35%   |
| 2011    | 19        | 6.99%   |
| 2013    | 17        | 6.25%   |
| 2014    | 16        | 5.88%   |
| 2015    | 15        | 5.51%   |
| 2017    | 14        | 5.15%   |
| 2016    | 13        | 4.78%   |
| 2012    | 13        | 4.78%   |
| 2010    | 10        | 3.68%   |
| 2008    | 6         | 2.21%   |
| 2007    | 6         | 2.21%   |
| 2022    | 5         | 1.84%   |
| Unknown | 4         | 1.47%   |
| 2009    | 3         | 1.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 162       | 59.56%  |
| Desktop        | 78        | 28.68%  |
| Convertible    | 8         | 2.94%   |
| Mini pc        | 8         | 2.94%   |
| System on chip | 5         | 1.84%   |
| All in one     | 5         | 1.84%   |
| Tablet         | 4         | 1.47%   |
| Server         | 2         | 0.74%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 240       | 87.91%  |
| Enabled  | 33        | 12.09%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 272       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 74        | 26.91%  |
| 4.01-8.0        | 59        | 21.45%  |
| 8.01-16.0       | 48        | 17.45%  |
| 3.01-4.0        | 39        | 14.18%  |
| 32.01-64.0      | 30        | 10.91%  |
| 1.01-2.0        | 8         | 2.91%   |
| 24.01-32.0      | 7         | 2.55%   |
| 64.01-256.0     | 7         | 2.55%   |
| 2.01-3.0        | 2         | 0.73%   |
| More than 256.0 | 1         | 0.36%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 81        | 27%     |
| 2.01-3.0   | 75        | 25%     |
| 4.01-8.0   | 54        | 18%     |
| 3.01-4.0   | 50        | 16.67%  |
| 8.01-16.0  | 18        | 6%      |
| 0.51-1.0   | 16        | 5.33%   |
| 0.01-0.5   | 5         | 1.67%   |
| 16.01-24.0 | 1         | 0.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 177       | 63.67%  |
| 2      | 67        | 24.1%   |
| 3      | 20        | 7.19%   |
| 4      | 9         | 3.24%   |
| 0      | 3         | 1.08%   |
| 5      | 2         | 0.72%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 206       | 75.74%  |
| Yes       | 66        | 24.26%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 205       | 75.09%  |
| No        | 68        | 24.91%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 224       | 82.05%  |
| No        | 49        | 17.95%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 185       | 67.77%  |
| No        | 88        | 32.23%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Singapore | 272       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Singapore            | 260       | 95.59%  |
| Jurong West          | 7         | 2.57%   |
| Queenstown Estate    | 2         | 0.74%   |
| Sembawang Estate     | 1         | 0.37%   |
| Kampong Ulu Jurong   | 1         | 0.37%   |
| Bukit Batok New Town | 1         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 78        | 108    | 20.53%  |
| Seagate                   | 46        | 54     | 12.11%  |
| WDC                       | 39        | 67     | 10.26%  |
| Toshiba                   | 31        | 36     | 8.16%   |
| SanDisk                   | 24        | 26     | 6.32%   |
| Unknown                   | 19        | 21     | 5%      |
| SK hynix                  | 17        | 19     | 4.47%   |
| Hitachi                   | 13        | 14     | 3.42%   |
| HGST                      | 11        | 18     | 2.89%   |
| Intel                     | 10        | 12     | 2.63%   |
| Kingston                  | 9         | 12     | 2.37%   |
| Phison                    | 6         | 8      | 1.58%   |
| Micron Technology         | 6         | 8      | 1.58%   |
| JMicron Technology        | 6         | 7      | 1.58%   |
| Crucial                   | 6         | 7      | 1.58%   |
| Hewlett-Packard           | 5         | 6      | 1.32%   |
| Apple                     | 5         | 6      | 1.32%   |
| Lexar                     | 3         | 3      | 0.79%   |
| Lenovo                    | 3         | 3      | 0.79%   |
| KIOXIA                    | 3         | 3      | 0.79%   |
| China                     | 3         | 3      | 0.79%   |
| A-DATA Technology         | 3         | 3      | 0.79%   |
| Unknown                   | 3         | 3      | 0.79%   |
| Transcend                 | 2         | 3      | 0.53%   |
| OCZ                       | 2         | 2      | 0.53%   |
| LITEON                    | 2         | 3      | 0.53%   |
| KLEVV                     | 2         | 2      | 0.53%   |
| Vaseky                    | 1         | 1      | 0.26%   |
| USB30                     | 1         | 1      | 0.26%   |
| UMIS                      | 1         | 1      | 0.26%   |
| TO Exter                  | 1         | 1      | 0.26%   |
| SPCC                      | 1         | 1      | 0.26%   |
| Silicon Motion            | 1         | 2      | 0.26%   |
| Realtek                   | 1         | 2      | 0.26%   |
| Plextor                   | 1         | 1      | 0.26%   |
| Pioneer                   | 1         | 1      | 0.26%   |
| Netac                     | 1         | 1      | 0.26%   |
| Mushkin                   | 1         | 1      | 0.26%   |
| MidasForce                | 1         | 1      | 0.26%   |
| Micron/Crucial Technology | 1         | 1      | 0.26%   |
| KESU                      | 1         | 1      | 0.26%   |
| INTEL SS                  | 1         | 2      | 0.26%   |
| GAMER                     | 1         | 1      | 0.26%   |
| GALAX                     | 1         | 1      | 0.26%   |
| Fujitsu                   | 1         | 1      | 0.26%   |
| External                  | 1         | 1      | 0.26%   |
| Drevo                     | 1         | 1      | 0.26%   |
| CT1000MX                  | 1         | 2      | 0.26%   |
| Corsair                   | 1         | 2      | 0.26%   |
| Apacer                    | 1         | 1      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Toshiba DT01ACA100 1TB                  | 7         | 1.73%   |
| Seagate ST1000LM035-1RK172 1TB          | 7         | 1.73%   |
| Unknown MMC Card  32GB                  | 5         | 1.24%   |
| Samsung SM963 2.5" NVMe PCIe SSD 1024GB | 5         | 1.24%   |
| JMicron Generic 160GB                   | 5         | 1.24%   |
| Samsung SSD 970 EVO Plus 500GB          | 4         | 0.99%   |
| Samsung SSD 860 EVO 500GB               | 4         | 0.99%   |
| Samsung SSD 850 EVO 250GB               | 4         | 0.99%   |
| Unknown MMC Card  64GB                  | 3         | 0.74%   |
| Toshiba MQ04ABF100 1TB                  | 3         | 0.74%   |
| Toshiba MQ01ABD100 1TB                  | 3         | 0.74%   |
| Seagate ST1000DM010-2EP102 1TB          | 3         | 0.74%   |
| SanDisk NVMe SSD Drive 512GB            | 3         | 0.74%   |
| Samsung SSD 850 EVO 500GB               | 3         | 0.74%   |
| Samsung SSD 840 EVO 250GB               | 3         | 0.74%   |
| Samsung NVMe SSD Drive 500GB            | 3         | 0.74%   |
| Samsung NVMe SSD Drive 256GB            | 3         | 0.74%   |
| HGST HTS721010A9E630 1TB                | 3         | 0.74%   |
| HGST HTS545050A7E380 500GB              | 3         | 0.74%   |
| Crucial CT500MX500SSD1 500GB            | 3         | 0.74%   |
| Unknown                                 | 3         | 0.74%   |
| WDC WDS500G2X0C-00L350 500GB            | 2         | 0.5%    |
| WDC WDS120G2G0A-00JH30 120GB SSD        | 2         | 0.5%    |
| WDC WDS100T2X0C-00L350 1TB              | 2         | 0.5%    |
| WDC WD6400AAKS-22A7B2 640GB             | 2         | 0.5%    |
| WDC WD10SPZX-21Z10T0 1TB                | 2         | 0.5%    |
| WDC PC SN720 SED SDAQNTW-1T00 1TB       | 2         | 0.5%    |
| Toshiba MK5055GSX 500GB                 | 2         | 0.5%    |
| Toshiba KBG30ZMS128G 128GB NVMe SSD     | 2         | 0.5%    |
| Toshiba DT01ACA200 2TB                  | 2         | 0.5%    |
| SK hynix SKHynix_HFS001TDE9X084N 1TB    | 2         | 0.5%    |
| SK hynix SC311 SATA 128GB SSD           | 2         | 0.5%    |
| SK hynix NVMe SSD Drive 256GB           | 2         | 0.5%    |
| SK hynix HFM512GDJTNG-8310A 512GB       | 2         | 0.5%    |
| Seagate ST2000DM008-2FR102 2TB          | 2         | 0.5%    |
| Seagate ST1000LM049-2GH172 1TB          | 2         | 0.5%    |
| Seagate BUP Portable 5TB                | 2         | 0.5%    |
| SanDisk SSD PLUS 240GB                  | 2         | 0.5%    |
| SanDisk SSD PLUS 120 GB                 | 2         | 0.5%    |
| SanDisk SD6SN1M128G1002 128GB SSD       | 2         | 0.5%    |
| SanDisk NVMe SSD Drive 1TB              | 2         | 0.5%    |
| Samsung SSD 860 EVO 250GB               | 2         | 0.5%    |
| Samsung SSD 860 EVO 1TB                 | 2         | 0.5%    |
| Samsung SSD 850 EVO M.2 250GB           | 2         | 0.5%    |
| Samsung SSD 850 EVO 1TB                 | 2         | 0.5%    |
| Samsung NVMe SSD Drive 512GB            | 2         | 0.5%    |
| Samsung NVMe SSD Drive 2TB              | 2         | 0.5%    |
| Samsung NVMe SSD Drive 250GB            | 2         | 0.5%    |
| Samsung MZVLB1T0HBLR-000L7 1TB          | 2         | 0.5%    |
| KIOXIA KBG40ZNS128G NVMe 128GB          | 2         | 0.5%    |
| Intel NVMe SSD Drive 512GB              | 2         | 0.5%    |
| Intel NVMe SSD Drive 1024GB             | 2         | 0.5%    |
| Hitachi HTS545050A7E380 500GB           | 2         | 0.5%    |
| HGST HTS725050A7E630 500GB              | 2         | 0.5%    |
| HP SSD S700 250GB                       | 2         | 0.5%    |
| China SSD 128GB                         | 2         | 0.5%    |
| A-DATA HC660 1TB SSD                    | 2         | 0.5%    |
| WDC WDS500G3X0C-00SJG0 500GB            | 1         | 0.25%   |
| WDC WDS500G2B0C-00PXH0 500GB            | 1         | 0.25%   |
| WDC WDS500G1X0E-00AFY0 500GB            | 1         | 0.25%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 44        | 52     | 37.29%  |
| WDC                 | 23        | 32     | 19.49%  |
| Toshiba             | 21        | 25     | 17.8%   |
| Hitachi             | 13        | 14     | 11.02%  |
| HGST                | 11        | 18     | 9.32%   |
| Samsung Electronics | 2         | 4      | 1.69%   |
| Apple               | 2         | 2      | 1.69%   |
| KESU                | 1         | 1      | 0.85%   |
| Fujitsu             | 1         | 1      | 0.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 43        | 59     | 34.96%  |
| SanDisk             | 16        | 16     | 13.01%  |
| Kingston            | 8         | 11     | 6.5%    |
| JMicron Technology  | 5         | 6      | 4.07%   |
| Crucial             | 5         | 6      | 4.07%   |
| WDC                 | 4         | 5      | 3.25%   |
| SK hynix            | 4         | 4      | 3.25%   |
| Hewlett-Packard     | 4         | 5      | 3.25%   |
| Micron Technology   | 3         | 5      | 2.44%   |
| China               | 3         | 3      | 2.44%   |
| Apple               | 3         | 3      | 2.44%   |
| Transcend           | 2         | 3      | 1.63%   |
| OCZ                 | 2         | 2      | 1.63%   |
| LITEON              | 2         | 3      | 1.63%   |
| Lexar               | 2         | 2      | 1.63%   |
| A-DATA Technology   | 2         | 2      | 1.63%   |
| Vaseky              | 1         | 1      | 0.81%   |
| USB30               | 1         | 1      | 0.81%   |
| Toshiba             | 1         | 1      | 0.81%   |
| TO Exter            | 1         | 1      | 0.81%   |
| SPCC                | 1         | 1      | 0.81%   |
| Plextor             | 1         | 1      | 0.81%   |
| Pioneer             | 1         | 1      | 0.81%   |
| Netac               | 1         | 1      | 0.81%   |
| MidasForce          | 1         | 1      | 0.81%   |
| KLEVV               | 1         | 1      | 0.81%   |
| Intel               | 1         | 1      | 0.81%   |
| GAMER               | 1         | 1      | 0.81%   |
| GALAX               | 1         | 1      | 0.81%   |
| CT1000MX            | 1         | 2      | 0.81%   |
| Apacer              | 1         | 1      | 0.81%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 113       | 160    | 32.1%   |
| SSD     | 109       | 151    | 30.97%  |
| HDD     | 107       | 149    | 30.4%   |
| MMC     | 19        | 21     | 5.4%    |
| Unknown | 4         | 4      | 1.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 171       | 280    | 52.29%  |
| NVMe | 113       | 155    | 34.56%  |
| SAS  | 24        | 29     | 7.34%   |
| MMC  | 19        | 21     | 5.81%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 124       | 176    | 56.62%  |
| 0.51-1.0   | 65        | 88     | 29.68%  |
| 1.01-2.0   | 14        | 17     | 6.39%   |
| 4.01-10.0  | 8         | 10     | 3.65%   |
| 3.01-4.0   | 5         | 6      | 2.28%   |
| 2.01-3.0   | 3         | 3      | 1.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 72        | 25.09%  |
| 251-500        | 55        | 19.16%  |
| 501-1000       | 52        | 18.12%  |
| 1001-2000      | 26        | 9.06%   |
| 1-20           | 20        | 6.97%   |
| 51-100         | 16        | 5.57%   |
| More than 3000 | 15        | 5.23%   |
| 21-50          | 14        | 4.88%   |
| Unknown        | 9         | 3.14%   |
| 2001-3000      | 8         | 2.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 111       | 38.28%  |
| 21-50          | 49        | 16.9%   |
| 101-250        | 40        | 13.79%  |
| 251-500        | 28        | 9.66%   |
| 51-100         | 28        | 9.66%   |
| 501-1000       | 12        | 4.14%   |
| Unknown        | 9         | 3.1%    |
| 1001-2000      | 6         | 2.07%   |
| More than 3000 | 4         | 1.38%   |
| 2001-3000      | 3         | 1.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD6400AAKS-22A7B2 640GB        | 2         | 3      | 13.33%  |
| WDC WD5000AAKS-22V1A0 500GB        | 1         | 1      | 6.67%   |
| WDC WD50 EZRX-00MVLB1 5TB          | 1         | 1      | 6.67%   |
| WDC WD10SPZX-21Z10T0 1TB           | 1         | 2      | 6.67%   |
| WDC WD10EZEX-60M2NA0 1TB           | 1         | 1      | 6.67%   |
| Toshiba DT01ACA100 1TB             | 1         | 1      | 6.67%   |
| Seagate ST2000LM003 HN-M201RAD 2TB | 1         | 1      | 6.67%   |
| Seagate ST1000LM024 HN-M 1TB       | 1         | 1      | 6.67%   |
| Hitachi HTS545032B9A300 320GB      | 1         | 1      | 6.67%   |
| Hitachi HTS541010A9E680 1TB        | 1         | 1      | 6.67%   |
| Hitachi HDS721010CLA632 1TB        | 1         | 1      | 6.67%   |
| HGST HTS545050A7E380 500GB         | 1         | 1      | 6.67%   |
| Crucial CT120M500SSD1 120GB        | 1         | 1      | 6.67%   |
| China SSD 128GB                    | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 6         | 8      | 40%     |
| Hitachi | 3         | 3      | 20%     |
| Seagate | 2         | 2      | 13.33%  |
| Toshiba | 1         | 1      | 6.67%   |
| HGST    | 1         | 1      | 6.67%   |
| Crucial | 1         | 1      | 6.67%   |
| China   | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 6         | 8      | 46.15%  |
| Hitachi | 3         | 3      | 23.08%  |
| Seagate | 2         | 2      | 15.38%  |
| Toshiba | 1         | 1      | 7.69%   |
| HGST    | 1         | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 15     | 86.67%  |
| SSD  | 2         | 2      | 13.33%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| JMicron Technology Tech 250GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor             | Computers | Drives | Percent |
|--------------------|-----------|--------|---------|
| JMicron Technology | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 172       | 284    | 57.91%  |
| Works    | 109       | 183    | 36.7%   |
| Malfunc  | 15        | 17     | 5.05%   |
| Failed   | 1         | 1      | 0.34%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 177       | 52.21%  |
| Samsung Electronics          | 42        | 12.39%  |
| AMD                          | 40        | 11.8%   |
| SanDisk                      | 22        | 6.49%   |
| SK hynix                     | 13        | 3.83%   |
| Toshiba America Info Systems | 8         | 2.36%   |
| Phison Electronics           | 6         | 1.77%   |
| KIOXIA                       | 5         | 1.47%   |
| Silicon Motion               | 4         | 1.18%   |
| Nvidia                       | 3         | 0.88%   |
| Micron Technology            | 3         | 0.88%   |
| Lenovo                       | 3         | 0.88%   |
| Micron/Crucial Technology    | 2         | 0.59%   |
| ASMedia Technology           | 2         | 0.59%   |
| ADATA Technology             | 2         | 0.59%   |
| VIA Technologies             | 1         | 0.29%   |
| Union Memory (Shenzhen)      | 1         | 0.29%   |
| Shenzhen Longsys Electronics | 1         | 0.29%   |
| Seagate Technology           | 1         | 0.29%   |
| Marvell Technology Group     | 1         | 0.29%   |
| Kingston Technology Company  | 1         | 0.29%   |
| Broadcom / LSI               | 1         | 0.29%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 30        | 8.2%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 26        | 7.1%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 16        | 4.37%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 12        | 3.28%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 12        | 3.28%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 11        | 3.01%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 8         | 2.19%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 8         | 2.19%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 7         | 1.91%   |
| Intel SATA Controller [RAID mode]                                                       | 7         | 1.91%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 7         | 1.91%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 6         | 1.64%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 6         | 1.64%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 6         | 1.64%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6         | 1.64%   |
| SK hynix Gold P31 SSD                                                                   | 5         | 1.37%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 5         | 1.37%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 5         | 1.37%   |
| Intel SSD 660P Series                                                                   | 5         | 1.37%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5         | 1.37%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 5         | 1.37%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5         | 1.37%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 4         | 1.09%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 4         | 1.09%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 4         | 1.09%   |
| Samsung NVMe SSD Controller 980                                                         | 4         | 1.09%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 4         | 1.09%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4         | 1.09%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4         | 1.09%   |
| AMD 500 Series Chipset SATA Controller                                                  | 4         | 1.09%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 3         | 0.82%   |
| SK hynix Non-Volatile memory controller                                                 | 3         | 0.82%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 3         | 0.82%   |
| SanDisk Non-Volatile memory controller                                                  | 3         | 0.82%   |
| Phison E12 NVMe Controller                                                              | 3         | 0.82%   |
| Micron Non-Volatile memory controller                                                   | 3         | 0.82%   |
| Lenovo Non-Volatile memory controller                                                   | 3         | 0.82%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 3         | 0.82%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3         | 0.82%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3         | 0.82%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 3         | 0.82%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 3         | 0.82%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3         | 0.82%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 0.82%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3         | 0.82%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3         | 0.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3         | 0.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3         | 0.82%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3         | 0.82%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 2         | 0.55%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 2         | 0.55%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2         | 0.55%   |
| Samsung Electronics SATA controller                                                     | 2         | 0.55%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                                | 2         | 0.55%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2         | 0.55%   |
| Intel Non-Volatile memory controller                                                    | 2         | 0.55%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2         | 0.55%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2         | 0.55%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2         | 0.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 2         | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 178       | 52.2%   |
| NVMe | 114       | 33.43%  |
| RAID | 27        | 7.92%   |
| IDE  | 21        | 6.16%   |
| SAS  | 1         | 0.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 215       | 79.04%  |
| AMD    | 52        | 19.12%  |
| ARM    | 5         | 1.84%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 11        | 4.04%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 7         | 2.57%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 6         | 2.21%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 1.84%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 1.84%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 5         | 1.84%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 1.84%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 1.47%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 4         | 1.47%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.47%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 1.47%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.47%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 1.47%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 1.1%    |
| Intel Core i7-2600 CPU @ 3.40GHz              | 3         | 1.1%    |
| Intel Core i5-8400 CPU @ 2.80GHz              | 3         | 1.1%    |
| Intel Core i5-6500 CPU @ 3.20GHz              | 3         | 1.1%    |
| ARM Processor                                 | 3         | 1.1%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 1.1%    |
| AMD Ryzen 5 5600X 6-Core Processor            | 3         | 1.1%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.1%    |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 2         | 0.74%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 2         | 0.74%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.74%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.74%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 0.74%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 2         | 0.74%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.74%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 0.74%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 0.74%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 2         | 0.74%   |
| Intel Core i5-4690 CPU @ 3.50GHz              | 2         | 0.74%   |
| Intel Core i5-4670K CPU @ 3.40GHz             | 2         | 0.74%   |
| Intel Core i5-3570 CPU @ 3.40GHz              | 2         | 0.74%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 2         | 0.74%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 0.74%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 2         | 0.74%   |
| Intel Core i5 CPU 650 @ 3.20GHz               | 2         | 0.74%   |
| Intel Core i3 CPU 550 @ 3.20GHz               | 2         | 0.74%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz          | 2         | 0.74%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 0.74%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 2         | 0.74%   |
| Intel Atom x5-Z8500 CPU @ 1.44GHz             | 2         | 0.74%   |
| ARM BCM2711 Processor                         | 2         | 0.74%   |
| AMD Ryzen Threadripper PRO 3955WX 16-Cores    | 2         | 0.74%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 0.74%   |
| AMD Ryzen 5 3600X 6-Core Processor            | 2         | 0.74%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 0.74%   |
| AMD Ryzen 5 3500X 6-Core Processor            | 2         | 0.74%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 2         | 0.74%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 2         | 0.74%   |
| Intel Xeon W-2155 CPU @ 3.30GHz               | 1         | 0.37%   |
| Intel Xeon W-11955M CPU @ 2.60GHz             | 1         | 0.37%   |
| Intel Xeon Silver 4110 CPU @ 2.10GHz          | 1         | 0.37%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz          | 1         | 0.37%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz           | 1         | 0.37%   |
| Intel Xeon CPU E3-1240 v3 @ 3.40GHz           | 1         | 0.37%   |
| Intel Xeon CPU E3-1230 v5 @ 3.40GHz           | 1         | 0.37%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz           | 1         | 0.37%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz           | 1         | 0.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 71        | 26.1%   |
| Intel Core i5           | 65        | 23.9%   |
| Other                   | 22        | 8.09%   |
| AMD Ryzen 5             | 17        | 6.25%   |
| AMD Ryzen 7             | 14        | 5.15%   |
| Intel Xeon              | 10        | 3.68%   |
| Intel Core i3           | 9         | 3.31%   |
| Intel Celeron           | 9         | 3.31%   |
| Intel Core 2 Duo        | 8         | 2.94%   |
| Intel Atom              | 6         | 2.21%   |
| Intel Core i9           | 4         | 1.47%   |
| Intel Pentium Silver    | 3         | 1.1%    |
| Intel Pentium Dual      | 2         | 0.74%   |
| Intel Pentium           | 2         | 0.74%   |
| Intel Core m3           | 2         | 0.74%   |
| ARM BCM                 | 2         | 0.74%   |
| AMD Ryzen Threadripper  | 2         | 0.74%   |
| AMD Ryzen 9             | 2         | 0.74%   |
| AMD Ryzen 7 PRO         | 2         | 0.74%   |
| AMD Ryzen 5 PRO         | 2         | 0.74%   |
| AMD Ryzen 3             | 2         | 0.74%   |
| AMD FX                  | 2         | 0.74%   |
| AMD Athlon              | 2         | 0.74%   |
| AMD A10                 | 2         | 0.74%   |
| Intel Xeon Silver       | 1         | 0.37%   |
| Intel Pentium Gold      | 1         | 0.37%   |
| Intel Pentium 4         | 1         | 0.37%   |
| Intel Core 2 Quad       | 1         | 0.37%   |
| Intel Core 2            | 1         | 0.37%   |
| AMD Turion 64 X2 Mobile | 1         | 0.37%   |
| AMD PRO A10             | 1         | 0.37%   |
| AMD Phenom II X4        | 1         | 0.37%   |
| AMD E                   | 1         | 0.37%   |
| AMD A6                  | 1         | 0.37%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 119       | 43.75%  |
| 2      | 83        | 30.51%  |
| 6      | 31        | 11.4%   |
| 8      | 25        | 9.19%   |
| 16     | 4         | 1.47%   |
| 1      | 3         | 1.1%    |
| 14     | 2         | 0.74%   |
| 12     | 2         | 0.74%   |
| 10     | 2         | 0.74%   |
| 3      | 1         | 0.37%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 271       | 99.63%  |
| 2      | 1         | 0.37%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 198       | 72.26%  |
| 1      | 76        | 27.74%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 265       | 97.43%  |
| Unknown        | 5         | 1.84%   |
| 32-bit         | 2         | 0.74%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 47        | 16.91%  |
| 0x906ea    | 15        | 5.4%    |
| 0x806ea    | 14        | 5.04%   |
| 0x306a9    | 14        | 5.04%   |
| 0x206a7    | 14        | 5.04%   |
| 0x306c3    | 13        | 4.68%   |
| 0x806ec    | 11        | 3.96%   |
| 0x506e3    | 9         | 3.24%   |
| 0x20655    | 8         | 2.88%   |
| 0x806eb    | 7         | 2.52%   |
| 0x806c1    | 7         | 2.52%   |
| 0x40651    | 7         | 2.52%   |
| 0x0a50000c | 6         | 2.16%   |
| 0x306d4    | 5         | 1.8%    |
| 0x08108109 | 5         | 1.8%    |
| 0x906e9    | 4         | 1.44%   |
| 0x806e9    | 4         | 1.44%   |
| 0x6fd      | 4         | 1.44%   |
| 0x406e3    | 4         | 1.44%   |
| 0x1067a    | 4         | 1.44%   |
| 0x08701021 | 4         | 1.44%   |
| 0xa0652    | 3         | 1.08%   |
| 0x906ed    | 3         | 1.08%   |
| 0x506ca    | 3         | 1.08%   |
| 0x50654    | 3         | 1.08%   |
| 0x406c3    | 3         | 1.08%   |
| 0x08701013 | 3         | 1.08%   |
| 0x08600106 | 3         | 1.08%   |
| 0x08108102 | 3         | 1.08%   |
| 0xa0660    | 2         | 0.72%   |
| 0x906c0    | 2         | 0.72%   |
| 0x806d1    | 2         | 0.72%   |
| 0x806c2    | 2         | 0.72%   |
| 0x706a1    | 2         | 0.72%   |
| 0x40661    | 2         | 0.72%   |
| 0x306e4    | 2         | 0.72%   |
| 0x30678    | 2         | 0.72%   |
| 0x106c2    | 2         | 0.72%   |
| 0x08600103 | 2         | 0.72%   |
| 0x06003106 | 2         | 0.72%   |
| 0x06000852 | 2         | 0.72%   |
| 0xf41      | 1         | 0.36%   |
| 0xa0671    | 1         | 0.36%   |
| 0xa0655    | 1         | 0.36%   |
| 0x906a3    | 1         | 0.36%   |
| 0x90672    | 1         | 0.36%   |
| 0x706e5    | 1         | 0.36%   |
| 0x706a8    | 1         | 0.36%   |
| 0x6fb      | 1         | 0.36%   |
| 0x6f6      | 1         | 0.36%   |
| 0x10676    | 1         | 0.36%   |
| 0x0a201016 | 1         | 0.36%   |
| 0x0a201009 | 1         | 0.36%   |
| 0x08608103 | 1         | 0.36%   |
| 0x0830104d | 1         | 0.36%   |
| 0x08301039 | 1         | 0.36%   |
| 0x08101102 | 1         | 0.36%   |
| 0x0810100b | 1         | 0.36%   |
| 0x08001138 | 1         | 0.36%   |
| 0x08001137 | 1         | 0.36%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 67        | 24.63%  |
| Haswell          | 24        | 8.82%   |
| SandyBridge      | 18        | 6.62%   |
| Skylake          | 17        | 6.25%   |
| IvyBridge        | 17        | 6.25%   |
| Zen 2            | 15        | 5.51%   |
| TigerLake        | 12        | 4.41%   |
| Zen+             | 11        | 4.04%   |
| Zen 3            | 11        | 4.04%   |
| Unknown          | 10        | 3.68%   |
| Westmere         | 8         | 2.94%   |
| Silvermont       | 7         | 2.57%   |
| CometLake        | 7         | 2.57%   |
| Penryn           | 6         | 2.21%   |
| Core             | 6         | 2.21%   |
| Icelake          | 5         | 1.84%   |
| Broadwell        | 5         | 1.84%   |
| Zen              | 4         | 1.47%   |
| Goldmont plus    | 3         | 1.1%    |
| Goldmont         | 3         | 1.1%    |
| Tremont          | 2         | 0.74%   |
| Steamroller      | 2         | 0.74%   |
| Piledriver       | 2         | 0.74%   |
| K10              | 2         | 0.74%   |
| Excavator        | 2         | 0.74%   |
| Bonnell          | 2         | 0.74%   |
| NetBurst         | 1         | 0.37%   |
| K8 Hammer        | 1         | 0.37%   |
| Bobcat           | 1         | 0.37%   |
| Alderlake Hybrid | 1         | 0.37%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 182       | 53.06%  |
| Nvidia            | 103       | 30.03%  |
| AMD               | 56        | 16.33%  |
| ASPEED Technology | 2         | 0.58%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 17        | 4.82%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17        | 4.82%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 11        | 3.12%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 3.12%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 11        | 3.12%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 2.83%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 2.27%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 2.27%   |
| Intel HD Graphics 530                                                                    | 7         | 1.98%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 1.98%   |
| Nvidia GP108M [GeForce MX150]                                                            | 6         | 1.7%    |
| Intel HD Graphics 620                                                                    | 6         | 1.7%    |
| AMD Renoir                                                                               | 6         | 1.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 1.42%   |
| AMD Cezanne                                                                              | 5         | 1.42%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4         | 1.13%   |
| Intel HD Graphics 5500                                                                   | 4         | 1.13%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.13%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 1.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.13%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.85%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 3         | 0.85%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.85%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 0.85%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 0.85%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.85%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 3         | 0.85%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 0.85%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 0.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 0.85%   |
| Intel JasperLake [UHD Graphics]                                                          | 3         | 0.85%   |
| Intel HD Graphics 630                                                                    | 3         | 0.85%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 0.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 0.85%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 0.85%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 0.85%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.57%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 2         | 0.57%   |
| Nvidia TU104M [GeForce RTX 2080 Mobile]                                                  | 2         | 0.57%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 0.57%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 0.57%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2         | 0.57%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.57%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 0.57%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.57%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 2         | 0.57%   |
| Nvidia GM108M [GeForce 940M]                                                             | 2         | 0.57%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 0.57%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.57%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.57%   |
| Intel HD Graphics 500                                                                    | 2         | 0.57%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.57%   |
| Intel Comet Lake UHD Graphics                                                            | 2         | 0.57%   |
| Intel AlderLake-S GT1                                                                    | 2         | 0.57%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2         | 0.57%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 0.57%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 2         | 0.57%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 2         | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 115       | 41.67%  |
| Intel + Nvidia  | 54        | 19.57%  |
| 1 x Nvidia      | 42        | 15.22%  |
| 1 x AMD         | 40        | 14.49%  |
| Intel + AMD     | 9         | 3.26%   |
| Other           | 5         | 1.81%   |
| AMD + Nvidia    | 4         | 1.45%   |
| 2 x AMD         | 3         | 1.09%   |
| 2 x Nvidia      | 2         | 0.72%   |
| Nvidia + ASPEED | 2         | 0.72%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 208       | 74.82%  |
| Proprietary | 58        | 20.86%  |
| Unknown     | 12        | 4.32%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 164       | 57.75%  |
| 1.01-2.0   | 42        | 14.79%  |
| 3.01-4.0   | 25        | 8.8%    |
| 0.01-0.5   | 17        | 5.99%   |
| 7.01-8.0   | 12        | 4.23%   |
| 0.51-1.0   | 11        | 3.87%   |
| 5.01-6.0   | 6         | 2.11%   |
| 8.01-16.0  | 6         | 2.11%   |
| 2.01-3.0   | 1         | 0.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 51        | 17.47%  |
| Dell                    | 42        | 14.38%  |
| Samsung Electronics     | 32        | 10.96%  |
| LG Display              | 27        | 9.25%   |
| BOE                     | 26        | 8.9%    |
| Chimei Innolux          | 16        | 5.48%   |
| Goldstar                | 12        | 4.11%   |
| Acer                    | 11        | 3.77%   |
| Apple                   | 10        | 3.42%   |
| Sharp                   | 8         | 2.74%   |
| Philips                 | 6         | 2.05%   |
| Hewlett-Packard         | 5         | 1.71%   |
| InfoVision              | 4         | 1.37%   |
| AOC                     | 4         | 1.37%   |
| PRISM+                  | 3         | 1.03%   |
| Lenovo                  | 3         | 1.03%   |
| Denver                  | 3         | 1.03%   |
| CSO                     | 3         | 1.03%   |
| PANDA                   | 2         | 0.68%   |
| LG Philips              | 2         | 0.68%   |
| Lenovo Group Limited    | 2         | 0.68%   |
| ASUSTek Computer        | 2         | 0.68%   |
| Ancor Communications    | 2         | 0.68%   |
| Wacom                   | 1         | 0.34%   |
| ViewSonic               | 1         | 0.34%   |
| Unknown                 | 1         | 0.34%   |
| Toshiba                 | 1         | 0.34%   |
| Sony                    | 1         | 0.34%   |
| SGT                     | 1         | 0.34%   |
| SAC                     | 1         | 0.34%   |
| RTK                     | 1         | 0.34%   |
| Pixio                   | 1         | 0.34%   |
| Mi                      | 1         | 0.34%   |
| EXP                     | 1         | 0.34%   |
| CVT                     | 1         | 0.34%   |
| CPT                     | 1         | 0.34%   |
| CHR                     | 1         | 0.34%   |
| Chi Mei Optoelectronics | 1         | 0.34%   |
| BenQ                    | 1         | 0.34%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch     | 3         | 1.01%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 3         | 1.01%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 3         | 1.01%   |
| Dell S2340L DELD058 1920x1080 509x286mm 23.0-inch                     | 3         | 1.01%   |
| Dell P2421D DELD0FF 2560x1440 527x296mm 23.8-inch                     | 3         | 1.01%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 2         | 0.68%   |
| PRISM+ X315 INN3200 2560x1440 697x393mm 31.5-inch                     | 2         | 0.68%   |
| LG Philips LCD Monitor LPL8D00 1280x800 304x190mm 14.1-inch           | 2         | 0.68%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch          | 2         | 0.68%   |
| Hewlett-Packard 23er HWP331E 1920x1080 509x286mm 23.0-inch            | 2         | 0.68%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 2         | 0.68%   |
| Goldstar IPS224 GSM58D5 1920x1080 477x268mm 21.5-inch                 | 2         | 0.68%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 0.68%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                | 2         | 0.68%   |
| Denver F240v LHC0236 1920x1080 530x280mm 23.6-inch                    | 2         | 0.68%   |
| Dell SE2417HG DELD08C 1920x1080 521x293mm 23.5-inch                   | 2         | 0.68%   |
| Dell E2213H DELA08F 1920x1080 477x268mm 21.5-inch                     | 2         | 0.68%   |
| Dell E2011H DEL406C 1600x900 443x249mm 20.0-inch                      | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN1354 1920x1080 293x165mm 13.2-inch      | 2         | 0.68%   |
| BOE LCD Monitor BOE09C3 1366x768 256x144mm 11.6-inch                  | 2         | 0.68%   |
| BOE LCD Monitor BOE06A7 1920x1080 294x165mm 13.3-inch                 | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO31EB 3840x2160 344x193mm 15.5-inch        | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch        | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch         | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO2B99 1920x1080 293x165mm 13.2-inch        | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO205C 1366x768 256x144mm 11.6-inch         | 2         | 0.68%   |
| Apple iMac APPAE25 3840x2160 597x336mm 27.0-inch                      | 2         | 0.68%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 2         | 0.68%   |
| Acer S201HL ACR01A5 1600x900 443x249mm 20.0-inch                      | 2         | 0.68%   |
| Acer EB321HQU ACR0507 2560x1440 699x393mm 31.6-inch                   | 2         | 0.68%   |
| Wacom CintiqPro24P WAC1063 3840x2160 530x300mm 24.0-inch              | 1         | 0.34%   |
| ViewSonic LCD Monitor VX2480-2K 2560x1440                             | 1         | 0.34%   |
| Unknown LCD Monitor AAA HDTV 3286x1080                                | 1         | 0.34%   |
| Toshiba LCD TV LCD0030 1920x1080 708x398mm 32.0-inch                  | 1         | 0.34%   |
| Sony TV SNY2C02 1920x1080 708x398mm 32.0-inch                         | 1         | 0.34%   |
| Sharp LQ150P1JX51 SHP14B4 2496x1664 317x211mm 15.0-inch               | 1         | 0.34%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch               | 1         | 0.34%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 1         | 0.34%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.34%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch               | 1         | 0.34%   |
| Sharp LCD Monitor SHP1485 1920x1080 294x165mm 13.3-inch               | 1         | 0.34%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.34%   |
| Sharp HDMI SHP115C 1920x1080 880x480mm 39.5-inch                      | 1         | 0.34%   |
| SGT C FORCE SGT0156 3840x2160 345x194mm 15.6-inch                     | 1         | 0.34%   |
| Samsung Electronics U32R59x SAM0F94 3840x2160 697x392mm 31.5-inch     | 1         | 0.34%   |
| Samsung Electronics S34J55x SAM0F72 1720x1440                         | 1         | 0.34%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch     | 1         | 0.34%   |
| Samsung Electronics S24R35xFZ SAM71A8 1920x1080 527x296mm 23.8-inch   | 1         | 0.34%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.34%   |
| Samsung Electronics S24D300 SAM0B42 1920x1080 531x299mm 24.0-inch     | 1         | 0.34%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch     | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC554E 1024x600 223x125mm 10.1-inch  | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch  | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 223x125mm 10.1-inch  | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch  | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch  | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 1         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 144       | 51.61%  |
| 1366x768 (WXGA)    | 33        | 11.83%  |
| 3840x2160 (4K)     | 25        | 8.96%   |
| 2560x1440 (QHD)    | 21        | 7.53%   |
| 1600x900 (HD+)     | 9         | 3.23%   |
| 1280x800 (WXGA)    | 9         | 3.23%   |
| 1920x1200 (WUXGA)  | 5         | 1.79%   |
| 2560x1600          | 4         | 1.43%   |
| 1360x768           | 4         | 1.43%   |
| 3440x1440          | 3         | 1.08%   |
| 3200x1800 (QHD+)   | 2         | 0.72%   |
| 2880x1800          | 2         | 0.72%   |
| 2736x1824          | 2         | 0.72%   |
| 2240x1400          | 2         | 0.72%   |
| 1440x900 (WXGA+)   | 2         | 0.72%   |
| 1280x1024 (SXGA)   | 2         | 0.72%   |
| 3840x2400          | 1         | 0.36%   |
| 3840x1600          | 1         | 0.36%   |
| 3286x1080          | 1         | 0.36%   |
| 3000x2000          | 1         | 0.36%   |
| 2560x1080          | 1         | 0.36%   |
| 2496x1664          | 1         | 0.36%   |
| 1680x1050 (WSXGA+) | 1         | 0.36%   |
| 1280x720 (HD)      | 1         | 0.36%   |
| 1024x600           | 1         | 0.36%   |
| Unknown            | 1         | 0.36%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 55        | 19.03%  |
| 13      | 49        | 16.96%  |
| 14      | 35        | 12.11%  |
| 27      | 27        | 9.34%   |
| 23      | 21        | 7.27%   |
| 24      | 18        | 6.23%   |
| 21      | 12        | 4.15%   |
| 12      | 10        | 3.46%   |
| Unknown | 10        | 3.46%   |
| 20      | 7         | 2.42%   |
| 18      | 6         | 2.08%   |
| 11      | 6         | 2.08%   |
| 31      | 5         | 1.73%   |
| 19      | 5         | 1.73%   |
| 32      | 3         | 1.04%   |
| 16      | 3         | 1.04%   |
| 34      | 2         | 0.69%   |
| 28      | 2         | 0.69%   |
| 25      | 2         | 0.69%   |
| 84      | 1         | 0.35%   |
| 55      | 1         | 0.35%   |
| 54      | 1         | 0.35%   |
| 52      | 1         | 0.35%   |
| 40      | 1         | 0.35%   |
| 39      | 1         | 0.35%   |
| 37      | 1         | 0.35%   |
| 35      | 1         | 0.35%   |
| 22      | 1         | 0.35%   |
| 17      | 1         | 0.35%   |
| 10      | 1         | 0.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 109       | 37.72%  |
| 501-600     | 68        | 23.53%  |
| 201-300     | 47        | 16.26%  |
| 401-500     | 28        | 9.69%   |
| Unknown     | 10        | 3.46%   |
| 601-700     | 7         | 2.42%   |
| 351-400     | 7         | 2.42%   |
| 701-800     | 5         | 1.73%   |
| 801-900     | 4         | 1.38%   |
| 1001-1500   | 3         | 1.04%   |
| 1501-2000   | 1         | 0.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 212       | 81.54%  |
| 16/10   | 27        | 10.38%  |
| Unknown | 8         | 3.08%   |
| 3/2     | 5         | 1.92%   |
| 21/9    | 5         | 1.92%   |
| 5/4     | 2         | 0.77%   |
| 6/5     | 1         | 0.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 58        | 20.14%  |
| 101-110        | 55        | 19.1%   |
| 201-250        | 44        | 15.28%  |
| 71-80          | 27        | 9.38%   |
| 301-350        | 27        | 9.38%   |
| 151-200        | 15        | 5.21%   |
| 351-500        | 12        | 4.17%   |
| Unknown        | 10        | 3.47%   |
| 61-70          | 9         | 3.13%   |
| 251-300        | 8         | 2.78%   |
| 51-60          | 6         | 2.08%   |
| 141-150        | 5         | 1.74%   |
| More than 1000 | 4         | 1.39%   |
| 111-120        | 3         | 1.04%   |
| 501-1000       | 3         | 1.04%   |
| 41-50          | 1         | 0.35%   |
| 121-130        | 1         | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 91        | 32.27%  |
| 51-100        | 74        | 26.24%  |
| 101-120       | 51        | 18.09%  |
| 161-240       | 41        | 14.54%  |
| More than 240 | 11        | 3.9%    |
| Unknown       | 10        | 3.55%   |
| 1-50          | 4         | 1.42%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 224       | 79.72%  |
| 2     | 41        | 14.59%  |
| 0     | 15        | 5.34%   |
| 3     | 1         | 0.36%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 157       | 40.46%  |
| Realtek Semiconductor    | 115       | 29.64%  |
| Qualcomm Atheros         | 46        | 11.86%  |
| Broadcom                 | 23        | 5.93%   |
| ASIX Electronics         | 7         | 1.8%    |
| TP-Link                  | 5         | 1.29%   |
| MediaTek                 | 4         | 1.03%   |
| Marvell Technology Group | 4         | 1.03%   |
| Samsung Electronics      | 3         | 0.77%   |
| Broadcom Limited         | 3         | 0.77%   |
| Sierra Wireless          | 2         | 0.52%   |
| Ralink Technology        | 2         | 0.52%   |
| Lenovo                   | 2         | 0.52%   |
| STMicroelectronics       | 1         | 0.26%   |
| Ralink                   | 1         | 0.26%   |
| Qualcomm                 | 1         | 0.26%   |
| Nvidia                   | 1         | 0.26%   |
| MosChip Semiconductor    | 1         | 0.26%   |
| Microsoft                | 1         | 0.26%   |
| Linksys                  | 1         | 0.26%   |
| Hewlett-Packard          | 1         | 0.26%   |
| Google                   | 1         | 0.26%   |
| Fargo                    | 1         | 0.26%   |
| Exar                     | 1         | 0.26%   |
| Edimax Technology        | 1         | 0.26%   |
| D-Link                   | 1         | 0.26%   |
| Aquantia                 | 1         | 0.26%   |
| Apple                    | 1         | 0.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 68        | 14.78%  |
| Intel Wi-Fi 6 AX200                                                     | 25        | 5.43%   |
| Intel Wireless 7265                                                     | 13        | 2.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 12        | 2.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 12        | 2.61%   |
| Intel Wi-Fi 6 AX201                                                     | 11        | 2.39%   |
| Intel Wireless 8265 / 8275                                              | 10        | 2.17%   |
| Intel I211 Gigabit Network Connection                                   | 10        | 2.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 9         | 1.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 1.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 1.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 7         | 1.52%   |
| Intel Wireless 7260                                                     | 7         | 1.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 1.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 1.52%   |
| ASIX AX88179 Gigabit Ethernet                                           | 7         | 1.52%   |
| Realtek RTL8125 2.5GbE Controller                                       | 6         | 1.3%    |
| Intel Ethernet Controller I225-V                                        | 6         | 1.3%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 1.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.09%   |
| Intel Wireless 3165                                                     | 5         | 1.09%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 1.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 0.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 0.87%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 0.87%   |
| Intel Ethernet Connection I217-LM                                       | 4         | 0.87%   |
| Intel Ethernet Connection (2) I219-V                                    | 4         | 0.87%   |
| Intel Ethernet Connection (10) I219-V                                   | 4         | 0.87%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 4         | 0.87%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 3         | 0.65%   |
| Intel Wireless-AC 9260                                                  | 3         | 0.65%   |
| Intel Wireless 8260                                                     | 3         | 0.65%   |
| Intel Ethernet Connection I218-LM                                       | 3         | 0.65%   |
| Intel Ethernet Connection I217-V                                        | 3         | 0.65%   |
| Intel Ethernet Connection (7) I219-LM                                   | 3         | 0.65%   |
| Intel Ethernet Connection (4) I219-LM                                   | 3         | 0.65%   |
| Intel Ethernet Connection (2) I219-LM                                   | 3         | 0.65%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 0.65%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 3         | 0.65%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 3         | 0.65%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                              | 2         | 0.43%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 2         | 0.43%   |
| Sierra Wireless EM7455                                                  | 2         | 0.43%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 2         | 0.43%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 0.43%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 2         | 0.43%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 0.43%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 2         | 0.43%   |
| Realtek Killer E3000 2.5GbE Controller                                  | 2         | 0.43%   |
| Realtek 802.11ac NIC                                                    | 2         | 0.43%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 2         | 0.43%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller               | 2         | 0.43%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.43%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.43%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 2         | 0.43%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 2         | 0.43%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.43%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 2         | 0.43%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 129       | 55.13%  |
| Qualcomm Atheros         | 38        | 16.24%  |
| Realtek Semiconductor    | 27        | 11.54%  |
| Broadcom                 | 18        | 7.69%   |
| TP-Link                  | 5         | 2.14%   |
| MediaTek                 | 4         | 1.71%   |
| Sierra Wireless          | 2         | 0.85%   |
| Ralink Technology        | 2         | 0.85%   |
| Marvell Technology Group | 2         | 0.85%   |
| Broadcom Limited         | 2         | 0.85%   |
| Ralink                   | 1         | 0.43%   |
| Qualcomm                 | 1         | 0.43%   |
| Linksys                  | 1         | 0.43%   |
| Edimax Technology        | 1         | 0.43%   |
| D-Link                   | 1         | 0.43%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 25        | 10.64%  |
| Intel Wireless 7265                                                     | 13        | 5.53%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 12        | 5.11%   |
| Intel Wi-Fi 6 AX201                                                     | 11        | 4.68%   |
| Intel Wireless 8265 / 8275                                              | 10        | 4.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 3.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 3.4%    |
| Intel Wireless 7260                                                     | 7         | 2.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 2.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 2.98%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 2.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 2.13%   |
| Intel Wireless 3165                                                     | 5         | 2.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 2.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 1.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.7%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 1.7%    |
| Intel Wireless-AC 9260                                                  | 3         | 1.28%   |
| Intel Wireless 8260                                                     | 3         | 1.28%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.28%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 3         | 1.28%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 3         | 1.28%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                              | 2         | 0.85%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 2         | 0.85%   |
| Sierra Wireless EM7455                                                  | 2         | 0.85%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 2         | 0.85%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 0.85%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 2         | 0.85%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 0.85%   |
| Realtek 802.11ac NIC                                                    | 2         | 0.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.85%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 0.85%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.85%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 2         | 0.85%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 0.85%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 2         | 0.85%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 0.85%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 0.85%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 0.85%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 2         | 0.85%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                      | 2         | 0.85%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 2         | 0.85%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 0.85%   |
| Broadcom BCM4311 802.11a/b/g                                            | 2         | 0.85%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]     | 1         | 0.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.43%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.43%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.43%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 0.43%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                  | 1         | 0.43%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 0.43%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.43%   |
| Realtek 802.11ax WLAN Adapter                                           | 1         | 0.43%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.43%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.43%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.43%   |
| Qualcomm QCA6390 Wireless Network Adapter                               | 1         | 0.43%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 1         | 0.43%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.43%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 96        | 44.24%  |
| Intel                    | 76        | 35.02%  |
| Qualcomm Atheros         | 12        | 5.53%   |
| Broadcom                 | 11        | 5.07%   |
| ASIX Electronics         | 7         | 3.23%   |
| Samsung Electronics      | 3         | 1.38%   |
| Marvell Technology Group | 2         | 0.92%   |
| Lenovo                   | 2         | 0.92%   |
| Nvidia                   | 1         | 0.46%   |
| MosChip Semiconductor    | 1         | 0.46%   |
| Microsoft                | 1         | 0.46%   |
| Hewlett-Packard          | 1         | 0.46%   |
| Google                   | 1         | 0.46%   |
| Broadcom Limited         | 1         | 0.46%   |
| Aquantia                 | 1         | 0.46%   |
| Apple                    | 1         | 0.46%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 68        | 30.63%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 12        | 5.41%   |
| Intel I211 Gigabit Network Connection                                          | 10        | 4.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 9         | 4.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 7         | 3.15%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 7         | 3.15%   |
| Realtek RTL8125 2.5GbE Controller                                              | 6         | 2.7%    |
| Intel Ethernet Controller I225-V                                               | 6         | 2.7%    |
| Intel Ethernet Connection I217-LM                                              | 4         | 1.8%    |
| Intel Ethernet Connection (2) I219-V                                           | 4         | 1.8%    |
| Intel Ethernet Connection (10) I219-V                                          | 4         | 1.8%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 4         | 1.8%    |
| Samsung Galaxy series, misc. (tethering mode)                                  | 3         | 1.35%   |
| Intel Ethernet Connection I218-LM                                              | 3         | 1.35%   |
| Intel Ethernet Connection I217-V                                               | 3         | 1.35%   |
| Intel Ethernet Connection (7) I219-LM                                          | 3         | 1.35%   |
| Intel Ethernet Connection (4) I219-LM                                          | 3         | 1.35%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 1.35%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 0.9%    |
| Realtek Killer E3000 2.5GbE Controller                                         | 2         | 0.9%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 0.9%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2         | 0.9%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 0.9%    |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.9%    |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.9%    |
| Intel 82579V Gigabit Network Connection                                        | 2         | 0.9%    |
| Intel 82578DM Gigabit Network Connection                                       | 2         | 0.9%    |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 0.9%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 2         | 0.9%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2         | 0.9%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.45%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1         | 0.45%   |
| Realtek Realtek Ethernet controller                                            | 1         | 0.45%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.45%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.45%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.45%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.45%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.45%   |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 0.45%   |
| MosChip MCS7830 10/100 Mbps Ethernet adapter                                   | 1         | 0.45%   |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                              | 1         | 0.45%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.45%   |
| Marvell Group 88E8038 PCI-E Fast Ethernet Controller                           | 1         | 0.45%   |
| Lenovo USB-C Hub                                                               | 1         | 0.45%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.45%   |
| Intel I210 Gigabit Network Connection                                          | 1         | 0.45%   |
| Intel Ethernet Controller X550                                                 | 1         | 0.45%   |
| Intel Ethernet Connection X722 for 1GbE                                        | 1         | 0.45%   |
| Intel Ethernet Connection X722                                                 | 1         | 0.45%   |
| Intel Ethernet Connection (7) I219-V                                           | 1         | 0.45%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.45%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 0.45%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.45%   |
| Intel Ethernet Connection (3) I219-LM                                          | 1         | 0.45%   |
| Intel Ethernet Connection (2) I218-V                                           | 1         | 0.45%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 0.45%   |
| Intel Ethernet Connection (11) I219-V                                          | 1         | 0.45%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.45%   |
| Intel 82566DC-2 Gigabit Network Connection                                     | 1         | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 224       | 51.85%  |
| Ethernet | 205       | 47.45%  |
| Modem    | 2         | 0.46%   |
| Unknown  | 1         | 0.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 179       | 62.37%  |
| Ethernet | 107       | 37.28%  |
| Unknown  | 1         | 0.35%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 132       | 48.35%  |
| 1     | 128       | 46.89%  |
| 0     | 7         | 2.56%   |
| 3     | 5         | 1.83%   |
| 4     | 1         | 0.37%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 256       | 94.12%  |
| Yes  | 16        | 5.88%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 107       | 56.61%  |
| Qualcomm Atheros Communications | 13        | 6.88%   |
| IMC Networks                    | 11        | 5.82%   |
| Foxconn / Hon Hai               | 10        | 5.29%   |
| Realtek Semiconductor           | 8         | 4.23%   |
| Broadcom                        | 8         | 4.23%   |
| Apple                           | 8         | 4.23%   |
| Cambridge Silicon Radio         | 7         | 3.7%    |
| Lite-On Technology              | 6         | 3.17%   |
| TP-Link                         | 2         | 1.06%   |
| Marvell Semiconductor           | 2         | 1.06%   |
| Toshiba                         | 1         | 0.53%   |
| SINO WEALTH                     | 1         | 0.53%   |
| Realtek                         | 1         | 0.53%   |
| Ralink Technology               | 1         | 0.53%   |
| Foxconn International           | 1         | 0.53%   |
| Chicony Electronics             | 1         | 0.53%   |
| Alps Electric                   | 1         | 0.53%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 36        | 18.95%  |
| Intel AX201 Bluetooth                               | 25        | 13.16%  |
| Intel AX200 Bluetooth                               | 21        | 11.05%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 20        | 10.53%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7         | 3.68%   |
| Qualcomm Atheros  Bluetooth Device                  | 6         | 3.16%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 5         | 2.63%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 2.11%   |
| IMC Networks Bluetooth Radio                        | 4         | 2.11%   |
| IMC Networks Bluetooth Device                       | 4         | 2.11%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 2.11%   |
| Apple Bluetooth Host Controller                     | 4         | 2.11%   |
| Realtek Bluetooth Radio                             | 3         | 1.58%   |
| Lite-On Bluetooth Device                            | 3         | 1.58%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.58%   |
| Foxconn / Hon Hai BCM20702A0                        | 3         | 1.58%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 1.58%   |
| TP-Link UB500 Adapter                               | 2         | 1.05%   |
| Marvell Bluetooth and Wireless LAN Composite        | 2         | 1.05%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 1.05%   |
| Intel AX210 Bluetooth                               | 2         | 1.05%   |
| IMC Networks Wireless_Device                        | 2         | 1.05%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 1.05%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 1.05%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 1.05%   |
| Apple Bluetooth USB Host Controller                 | 2         | 1.05%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.53%   |
| SINO WEALTH RK Bluetooth Keyboar                    | 1         | 0.53%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.53%   |
| Realtek Bluetooth Radio                             | 1         | 0.53%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.53%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.53%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.53%   |
| Lite-On Bluetooth Radio                             | 1         | 0.53%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.53%   |
| IMC Networks Bluetooth module                       | 1         | 0.53%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.53%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 0.53%   |
| Chicony Bluetooth (RTL8723BE)                       | 1         | 0.53%   |
| Broadcom Bluetooth                                  | 1         | 0.53%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 0.53%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 0.53%   |
| Alps Electric Bluetooth Adapter                     | 1         | 0.53%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 206       | 59.03%  |
| Nvidia                      | 61        | 17.48%  |
| AMD                         | 59        | 16.91%  |
| Kingston Technology         | 2         | 0.57%   |
| C-Media Electronics         | 2         | 0.57%   |
| Apple                       | 2         | 0.57%   |
| XMOS                        | 1         | 0.29%   |
| Unknown                     | 1         | 0.29%   |
| SteelSeries ApS             | 1         | 0.29%   |
| Sony                        | 1         | 0.29%   |
| Samson Technologies         | 1         | 0.29%   |
| Realtek Semiconductor       | 1         | 0.29%   |
| Razer USA                   | 1         | 0.29%   |
| Plantronics                 | 1         | 0.29%   |
| NXP Semiconductors          | 1         | 0.29%   |
| Micro Star International    | 1         | 0.29%   |
| Logitech                    | 1         | 0.29%   |
| Lenovo                      | 1         | 0.29%   |
| JBL                         | 1         | 0.29%   |
| FiiO Electronics Technology | 1         | 0.29%   |
| Cooler Master               | 1         | 0.29%   |
| Conexant Systems            | 1         | 0.29%   |
| ASUSTek Computer            | 1         | 0.29%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 28        | 6.83%   |
| AMD Family 17h/19h HD Audio Controller                                     | 28        | 6.83%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 19        | 4.63%   |
| Intel Cannon Lake PCH cAVS                                                 | 18        | 4.39%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 15        | 3.66%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 14        | 3.41%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 13        | 3.17%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 12        | 2.93%   |
| AMD Starship/Matisse HD Audio Controller                                   | 11        | 2.68%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 11        | 2.68%   |
| Intel Comet Lake PCH-LP cAVS                                               | 10        | 2.44%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 10        | 2.44%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 10        | 2.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9         | 2.2%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 1.95%   |
| Nvidia GP107GL High Definition Audio Controller                            | 7         | 1.71%   |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 1.71%   |
| Intel 8 Series HD Audio Controller                                         | 7         | 1.71%   |
| Intel 200 Series PCH HD Audio                                              | 6         | 1.46%   |
| Nvidia TU104 HD Audio Controller                                           | 5         | 1.22%   |
| Nvidia GF108 High Definition Audio Controller                              | 5         | 1.22%   |
| Nvidia GA104 High Definition Audio Controller                              | 5         | 1.22%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 1.22%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 1.22%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 1.22%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5         | 1.22%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 0.98%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4         | 0.98%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 0.98%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 0.98%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4         | 0.98%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 0.73%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 0.73%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 0.73%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 0.73%   |
| Intel Jasper Lake HD Audio                                                 | 3         | 0.73%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 0.73%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 0.73%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 0.73%   |
| AMD Navi 10 HDMI Audio                                                     | 3         | 0.73%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3         | 0.73%   |
| Nvidia MCP89 High Definition Audio                                         | 2         | 0.49%   |
| Nvidia High Definition Audio Controller                                    | 2         | 0.49%   |
| Nvidia GP108 High Definition Audio Controller                              | 2         | 0.49%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.49%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 0.49%   |
| Nvidia GP102 HDMI Audio Controller                                         | 2         | 0.49%   |
| Nvidia GM204 High Definition Audio Controller                              | 2         | 0.49%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.49%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2         | 0.49%   |
| Nvidia GA102 High Definition Audio Controller                              | 2         | 0.49%   |
| Kingston Technology HyperX 7.1 Audio                                       | 2         | 0.49%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 0.49%   |
| Intel CM238 HD Audio Controller                                            | 2         | 0.49%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2         | 0.49%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2         | 0.49%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 0.49%   |
| Apple USB-C to 3.5mm Headphone Jack Adapter                                | 2         | 0.49%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 0.49%   |
| XMOS iFi (by AMR) HD USB Audio                                             | 1         | 0.24%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| SK hynix                       | 41        | 22.78%  |
| Samsung Electronics            | 35        | 19.44%  |
| Micron Technology              | 23        | 12.78%  |
| Kingston                       | 19        | 10.56%  |
| Crucial                        | 13        | 7.22%   |
| Unknown                        | 8         | 4.44%   |
| Corsair                        | 7         | 3.89%   |
| G.Skill                        | 6         | 3.33%   |
| Transcend                      | 4         | 2.22%   |
| A-DATA Technology              | 4         | 2.22%   |
| Undefi                         | 3         | 1.67%   |
| Ramaxel Technology             | 3         | 1.67%   |
| Kingmax                        | 2         | 1.11%   |
| Elpida                         | 2         | 1.11%   |
| Unknown (ABCD)                 | 1         | 0.56%   |
| Unknown (0x02BA)               | 1         | 0.56%   |
| Qimonda                        | 1         | 0.56%   |
| Patriot                        | 1         | 0.56%   |
| Nanya Technology               | 1         | 0.56%   |
| MKF_SMBIOS_TYPE17_MANUFACTURER | 1         | 0.56%   |
| Lexar                          | 1         | 0.56%   |
| KLEVV                          | 1         | 0.56%   |
| Essencore Limited              | 1         | 0.56%   |
| ASint Technology               | 1         | 0.56%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 3         | 1.57%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s    | 3         | 1.57%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 3         | 1.57%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s                 | 2         | 1.05%   |
| Undefi RAM Module 2GB SODIMM DDR3 1866MT/s                          | 2         | 1.05%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                     | 2         | 1.05%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 1.05%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 1.05%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 1.05%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 2         | 1.05%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 1.05%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s      | 2         | 1.05%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 2         | 1.05%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 1.05%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 1.05%   |
| Micron RAM MT52L512M32D2PF-10 4GB Row Of Chips LPDDR3 1867MT/s      | 2         | 1.05%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s                | 2         | 1.05%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 2         | 1.05%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s               | 2         | 1.05%   |
| Kingston RAM KY7N41-MIE 8192MB DIMM DDR4 2666MT/s                   | 2         | 1.05%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s                 | 2         | 1.05%   |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1600MT/s               | 2         | 1.05%   |
| Kingmax RAM GLLG42F-DA--------- 8GB DIMM DDR4 2400MT/s              | 2         | 1.05%   |
| G.Skill RAM F4-3200C16-8GTZN 8GB DIMM DDR4 3200MT/s                 | 2         | 1.05%   |
| Crucial RAM CT32G4SFD832A.C16FE 32GB SODIMM DDR4 3200MT/s           | 2         | 1.05%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s                 | 1         | 0.52%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                                | 1         | 0.52%   |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 1         | 0.52%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                                | 1         | 0.52%   |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s                    | 1         | 0.52%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                         | 1         | 0.52%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                      | 1         | 0.52%   |
| Unknown RAM Module 1GB SODIMM DDR3 1600MT/s                         | 1         | 0.52%   |
| Unknown RAM Module 16GB Row Of Chips LPDDR4 4267MT/s                | 1         | 0.52%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 0.52%   |
| Unknown (0x02BA) RAM Module 4096MB SODIMM DDR3 1333MT/s             | 1         | 0.52%   |
| Undefi RAM Module 4GB SODIMM DDR3 1866MT/s                          | 1         | 0.52%   |
| Transcend RAM TS1GSK64V3H 8192MB SODIMM DDR3 1333MT/s               | 1         | 0.52%   |
| Transcend RAM JM800QLU-2G 2GB DIMM DDR2 2048MT/s                    | 1         | 0.52%   |
| Transcend RAM JM3200HSB-16G 16GB SODIMM DDR4 3200MT/s               | 1         | 0.52%   |
| Transcend RAM JM1600KLH-8G 8GB DIMM DDR3 1600MT/s                   | 1         | 0.52%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                     | 1         | 0.52%   |
| SK hynix RAM HMT451U7AFR8A-PB 4GB DIMM DDR3 1600MT/s                | 1         | 0.52%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.52%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.52%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB DIMM DDR3 1600MT/s                | 1         | 0.52%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.52%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s                | 1         | 0.52%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s                | 1         | 0.52%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.52%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.52%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.52%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 0.52%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s                | 1         | 0.52%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB Row Of Chips DDR4 3200MT/s       | 1         | 0.52%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 1         | 0.52%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 1         | 0.52%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s             | 1         | 0.52%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.52%   |
| SK hynix RAM HMA451U6AFR8N-TF 4GB DIMM DDR4 2133MT/s                | 1         | 0.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 84        | 56%     |
| DDR3    | 45        | 30%     |
| LPDDR3  | 9         | 6%      |
| LPDDR4  | 7         | 4.67%   |
| SDRAM   | 2         | 1.33%   |
| DDR2    | 2         | 1.33%   |
| Unknown | 1         | 0.67%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 86        | 58.11%  |
| DIMM         | 43        | 29.05%  |
| Row Of Chips | 18        | 12.16%  |
| Chip         | 1         | 0.68%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 65        | 38.46%  |
| 4096  | 50        | 29.59%  |
| 16384 | 32        | 18.93%  |
| 2048  | 11        | 6.51%   |
| 32768 | 8         | 4.73%   |
| 1024  | 3         | 1.78%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 32        | 18.93%  |
| 1600    | 32        | 18.93%  |
| 2667    | 30        | 17.75%  |
| 2400    | 16        | 9.47%   |
| 2133    | 11        | 6.51%   |
| 1333    | 6         | 3.55%   |
| 4267    | 5         | 2.96%   |
| 1866    | 5         | 2.96%   |
| 3600    | 4         | 2.37%   |
| 2666    | 3         | 1.78%   |
| 1867    | 3         | 1.78%   |
| 1334    | 3         | 1.78%   |
| 3266    | 2         | 1.18%   |
| 2048    | 2         | 1.18%   |
| 1800    | 2         | 1.18%   |
| 1067    | 2         | 1.18%   |
| 8400    | 1         | 0.59%   |
| 4800    | 1         | 0.59%   |
| 4333    | 1         | 0.59%   |
| 4199    | 1         | 0.59%   |
| 3666    | 1         | 0.59%   |
| 3400    | 1         | 0.59%   |
| 2200    | 1         | 0.59%   |
| 2134    | 1         | 0.59%   |
| 1200    | 1         | 0.59%   |
| 667     | 1         | 0.59%   |
| Unknown | 1         | 0.59%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Samsung M2020 Series | 1         | 100%    |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 41        | 24.4%   |
| IMC Networks                           | 24        | 14.29%  |
| Microdia                               | 19        | 11.31%  |
| Realtek Semiconductor                  | 18        | 10.71%  |
| Apple                                  | 10        | 5.95%   |
| Sunplus Innovation Technology          | 9         | 5.36%   |
| Logitech                               | 7         | 4.17%   |
| Suyin                                  | 6         | 3.57%   |
| Acer                                   | 6         | 3.57%   |
| Samsung Electronics                    | 5         | 2.98%   |
| Syntek                                 | 4         | 2.38%   |
| Lite-On Technology                     | 4         | 2.38%   |
| Silicon Motion                         | 2         | 1.19%   |
| Ricoh                                  | 2         | 1.19%   |
| SunplusIT                              | 1         | 0.6%    |
| Sony Ericsson Mobile Communications AB | 1         | 0.6%    |
| Quanta                                 | 1         | 0.6%    |
| OnePlus Technology (Shenzhen)          | 1         | 0.6%    |
| Microsoft                              | 1         | 0.6%    |
| Magic Control Technology               | 1         | 0.6%    |
| Luxvisions Innotech Limited            | 1         | 0.6%    |
| Lenovo                                 | 1         | 0.6%    |
| Intel                                  | 1         | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) | 1         | 0.6%    |
| Alcor Micro                            | 1         | 0.6%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                              | 13        | 7.69%   |
| Chicony Integrated Camera                                  | 9         | 5.33%   |
| Chicony HD WebCam                                          | 9         | 5.33%   |
| IMC Networks Integrated Camera                             | 7         | 4.14%   |
| Realtek Integrated_Webcam_HD                               | 6         | 3.55%   |
| Sunplus Integrated_Webcam_HD                               | 5         | 2.96%   |
| Samsung Galaxy series, misc. (MTP mode)                    | 5         | 2.96%   |
| IMC Networks USB2.0 HD UVC WebCam                          | 5         | 2.96%   |
| IMC Networks USB2.0 VGA UVC WebCam                         | 4         | 2.37%   |
| IMC Networks USB2.0 HD IR UVC WebCam                       | 4         | 2.37%   |
| Chicony HP HD Camera                                       | 4         | 2.37%   |
| Apple FaceTime HD Camera (Built-in)                        | 4         | 2.37%   |
| Syntek Integrated Camera                                   | 3         | 1.78%   |
| Logitech HD Webcam C615                                    | 3         | 1.78%   |
| Chicony Lenovo Integrated Camera (0.3MP)                   | 3         | 1.78%   |
| Chicony HP Wide Vision HD Camera                           | 3         | 1.78%   |
| Apple FaceTime HD Camera                                   | 3         | 1.78%   |
| Realtek Integrated Webcam_HD                               | 2         | 1.18%   |
| Realtek Asus 2.0 USB Webcam                                | 2         | 1.18%   |
| Microdia Sonix USB 2.0 Camera                              | 2         | 1.18%   |
| Logitech C922 Pro Stream Webcam                            | 2         | 1.18%   |
| Lite-On HP Wide Vision HD Camera                           | 2         | 1.18%   |
| IMC Networks Lenovo EasyCamera                             | 2         | 1.18%   |
| Chicony USB2.0 HD UVC WebCam                               | 2         | 1.18%   |
| Chicony USB2.0 Camera                                      | 2         | 1.18%   |
| Apple iPhone 5/5C/5S/6/SE                                  | 2         | 1.18%   |
| Acer Integrated Camera                                     | 2         | 1.18%   |
| Acer BisonCam, NB Pro                                      | 2         | 1.18%   |
| Syntek Lenovo EasyCamera                                   | 1         | 0.59%   |
| Suyin UVC HD Webcam                                        | 1         | 0.59%   |
| Suyin Laptop_Integrated_Webcam_HD                          | 1         | 0.59%   |
| Suyin HD WebCam                                            | 1         | 0.59%   |
| Suyin HD Video WebCam                                      | 1         | 0.59%   |
| Suyin Asus Integrated Webcam                               | 1         | 0.59%   |
| Suyin Acer/Lenovo Webcam [CN0316]                          | 1         | 0.59%   |
| SunplusIT XiaoMi USB 2.0 Webcam                            | 1         | 0.59%   |
| Sunplus TOSHIBA Web Camera - HD                            | 1         | 0.59%   |
| Sunplus Lenovo EasyCamera                                  | 1         | 0.59%   |
| Sunplus Laptop Integrated Webcam HD                        | 1         | 0.59%   |
| Sunplus HD User Facing                                     | 1         | 0.59%   |
| Sony Ericsson Mobile AB XQ-BT52                            | 1         | 0.59%   |
| Silicon Motion WebCam SCB-1100N                            | 1         | 0.59%   |
| Silicon Motion WebCam SCB-0370N                            | 1         | 0.59%   |
| Ricoh Visual Communication Camera VGP-VCC6 [R5U870]        | 1         | 0.59%   |
| Ricoh USB2.0 Camera                                        | 1         | 0.59%   |
| Realtek USB2.0 HD UVC WebCam                               | 1         | 0.59%   |
| Realtek USB Camera                                         | 1         | 0.59%   |
| Realtek USB Boot                                           | 1         | 0.59%   |
| Realtek Integrated Webcam HD                               | 1         | 0.59%   |
| Realtek HP Wide Vision FHD Camera                          | 1         | 0.59%   |
| Realtek HD Webcam - Realtek                                | 1         | 0.59%   |
| Realtek Front Camera                                       | 1         | 0.59%   |
| Realtek Asus laptop camera                                 | 1         | 0.59%   |
| Quanta HD User Facing                                      | 1         | 0.59%   |
| OnePlus (Shenzhen) A3000 phone (PTP mode, with debug) [3T] | 1         | 0.59%   |
| Microsoft Surface Camera Front                             | 1         | 0.59%   |
| Microdia USB 2.0 Camera                                    | 1         | 0.59%   |
| Microdia Integrated Webcam HD                              | 1         | 0.59%   |
| Microdia Integrated Webcam                                 | 1         | 0.59%   |
| Microdia Integrated Camera                                 | 1         | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 13        | 26%     |
| Validity Sensors           | 8         | 16%     |
| Elan Microelectronics      | 7         | 14%     |
| LighTuning Technology      | 6         | 12%     |
| AuthenTec                  | 6         | 12%     |
| Upek                       | 5         | 10%     |
| Shenzhen Goodix Technology | 5         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 16%     |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 12%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 5         | 10%     |
| Elan ELAN:Fingerprint                                                      | 5         | 10%     |
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 4%      |
| Validity Sensors Synaptics WBDI                                            | 2         | 4%      |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 4%      |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 4%      |
| Shenzhen Goodix FingerPrint                                                | 2         | 4%      |
| Elan ELAN:ARM-M4                                                           | 2         | 4%      |
| AuthenTec AES2810                                                          | 2         | 4%      |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 4%      |
| Unknown                                                                    | 2         | 4%      |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 2%      |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 2%      |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 2%      |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2%      |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 2%      |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 2%      |
| AuthenTec Fingerprint Sensor                                               | 1         | 2%      |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 2%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor     | Computers | Percent |
|------------|-----------|---------|
| Broadcom   | 6         | 85.71%  |
| Clay Logic | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 58200                                 | 3         | 42.86%  |
| Broadcom BCM5880 Secure Applications Processor | 2         | 28.57%  |
| Clay Logic Nitrokey Start                      | 1         | 14.29%  |
| Broadcom 5880                                  | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 178       | 62.9%   |
| 1     | 80        | 28.27%  |
| 2     | 21        | 7.42%   |
| 3     | 3         | 1.06%   |
| 5     | 1         | 0.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 49        | 37.4%   |
| Graphics card            | 32        | 24.43%  |
| Net/wireless             | 16        | 12.21%  |
| Multimedia controller    | 6         | 4.58%   |
| Chipcard                 | 6         | 4.58%   |
| Camera                   | 5         | 3.82%   |
| Net/ethernet             | 4         | 3.05%   |
| Communication controller | 4         | 3.05%   |
| Network                  | 2         | 1.53%   |
| Bluetooth                | 2         | 1.53%   |
| Wireless                 | 1         | 0.76%   |
| Unassigned class         | 1         | 0.76%   |
| Storage/raid             | 1         | 0.76%   |
| Sound                    | 1         | 0.76%   |
| Firewire controller      | 1         | 0.76%   |


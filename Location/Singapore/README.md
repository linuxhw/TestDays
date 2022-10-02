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

Total: 420

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [ec44263cbd](https://linux-hardware.org/?probe=ec44263cbd) | Oct 01, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [1914cf579b](https://linux-hardware.org/?probe=1914cf579b) | Sep 29, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [8e77417877](https://linux-hardware.org/?probe=8e77417877) | Sep 28, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [f061f902ff](https://linux-hardware.org/?probe=f061f902ff) | Sep 25, 2022 |
| Acer          | Aspire E1-422               | Notebook    | [855ad327a4](https://linux-hardware.org/?probe=855ad327a4) | Sep 25, 2022 |
| Acer          | Aspire E1-422               | Notebook    | [829ec8aac1](https://linux-hardware.org/?probe=829ec8aac1) | Sep 25, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [93680a7429](https://linux-hardware.org/?probe=93680a7429) | Sep 25, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [ae5fd894b6](https://linux-hardware.org/?probe=ae5fd894b6) | Sep 25, 2022 |
| Dell          | Latitude 7275               | Tablet      | [49ee35636b](https://linux-hardware.org/?probe=49ee35636b) | Sep 24, 2022 |
| Lenovo        | Legion R9000K2021H 82N6     | Notebook    | [d739547049](https://linux-hardware.org/?probe=d739547049) | Sep 23, 2022 |
| Lenovo        | 10051                       | All in one  | [195ec7cb8c](https://linux-hardware.org/?probe=195ec7cb8c) | Sep 23, 2022 |
| Gigabyte      | X99-Ultra Gaming-CF         | Desktop     | [568bffc355](https://linux-hardware.org/?probe=568bffc355) | Sep 22, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [73fd6c23e1](https://linux-hardware.org/?probe=73fd6c23e1) | Sep 21, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [0f698c857c](https://linux-hardware.org/?probe=0f698c857c) | Sep 16, 2022 |
| Dell          | Precision 3561              | Notebook    | [b61765a085](https://linux-hardware.org/?probe=b61765a085) | Sep 15, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [3af5d11f3f](https://linux-hardware.org/?probe=3af5d11f3f) | Sep 14, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [356956ad10](https://linux-hardware.org/?probe=356956ad10) | Sep 14, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [1ca8786a47](https://linux-hardware.org/?probe=1ca8786a47) | Sep 13, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [22e62266a2](https://linux-hardware.org/?probe=22e62266a2) | Sep 13, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [b50a1bc29b](https://linux-hardware.org/?probe=b50a1bc29b) | Sep 09, 2022 |
| Dell          | Latitude 3320               | Notebook    | [1ab9888966](https://linux-hardware.org/?probe=1ab9888966) | Sep 09, 2022 |
| ASUSTek       | X99-E WS                    | Desktop     | [c76dceef8e](https://linux-hardware.org/?probe=c76dceef8e) | Sep 08, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [58062d2ad3](https://linux-hardware.org/?probe=58062d2ad3) | Sep 06, 2022 |
| ASUSTek       | ROG STRIX H370-F GAMING     | Desktop     | [a61798e4d3](https://linux-hardware.org/?probe=a61798e4d3) | Sep 05, 2022 |
| ASUSTek       | ROG STRIX H370-F GAMING     | Desktop     | [0ba66b6e07](https://linux-hardware.org/?probe=0ba66b6e07) | Sep 05, 2022 |
| ASUSTek       | ROG STRIX H370-F GAMING     | Desktop     | [169df470a6](https://linux-hardware.org/?probe=169df470a6) | Sep 05, 2022 |
| MSI           | Pulse GL66 11UGK            | Notebook    | [db7f9099f2](https://linux-hardware.org/?probe=db7f9099f2) | Sep 05, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [45dceb981a](https://linux-hardware.org/?probe=45dceb981a) | Sep 03, 2022 |
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
| Ubuntu 20.04                 | 75        | 24.59%  |
| Ubuntu 18.04                 | 35        | 11.48%  |
| Ubuntu 22.04                 | 13        | 4.26%   |
| Fedora 33                    | 12        | 3.93%   |
| Pop!_OS 20.04                | 8         | 2.62%   |
| Arch Rolling                 | 8         | 2.62%   |
| Arch                         | 8         | 2.62%   |
| Debian 11                    | 7         | 2.3%    |
| Ubuntu 21.10                 | 5         | 1.64%   |
| Ubuntu 21.04                 | 5         | 1.64%   |
| Linux Mint 20                | 5         | 1.64%   |
| KDE neon 20.04               | 5         | 1.64%   |
| Xubuntu 20.04                | 4         | 1.31%   |
| Pop!_OS 22.04                | 4         | 1.31%   |
| Pop!_OS 21.04                | 4         | 1.31%   |
| OpenMandriva 4.3             | 4         | 1.31%   |
| Fedora 36                    | 4         | 1.31%   |
| Debian Testing               | 4         | 1.31%   |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 0.98%   |
| Manjaro                      | 3         | 0.98%   |
| Kubuntu 22.04                | 3         | 0.98%   |
| Fedora 34                    | 3         | 0.98%   |
| Fedora 32                    | 3         | 0.98%   |
| ArcoLinux Rolling            | 3         | 0.98%   |
| Zorin 16                     | 2         | 0.66%   |
| Zorin 15                     | 2         | 0.66%   |
| Ubuntu Unity 16.04           | 2         | 0.66%   |
| Ubuntu 19.10                 | 2         | 0.66%   |
| Ubuntu 19.04                 | 2         | 0.66%   |
| Ubuntu 18.10                 | 2         | 0.66%   |
| Rocky Linux 8.5              | 2         | 0.66%   |
| Raspbian 10                  | 2         | 0.66%   |
| Pop!_OS 21.10                | 2         | 0.66%   |
| Pop!_OS 20.10                | 2         | 0.66%   |
| OpenMandriva 4.50            | 2         | 0.66%   |
| OpenMandriva 4.2             | 2         | 0.66%   |
| Manjaro 20.2                 | 2         | 0.66%   |
| Manjaro 20.1                 | 2         | 0.66%   |
| Lubuntu 20.04                | 2         | 0.66%   |
| Linux Mint 21                | 2         | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 138       | 46.46%  |
| Fedora        | 23        | 7.74%   |
| Pop!_OS       | 20        | 6.73%   |
| Arch          | 15        | 5.05%   |
| Debian        | 14        | 4.71%   |
| OpenMandriva  | 9         | 3.03%   |
| Linux Mint    | 9         | 3.03%   |
| Manjaro       | 8         | 2.69%   |
| Kubuntu       | 6         | 2.02%   |
| Xubuntu       | 5         | 1.68%   |
| KDE neon      | 5         | 1.68%   |
| Zorin         | 4         | 1.35%   |
| Ubuntu Unity  | 3         | 1.01%   |
| Rocky Linux   | 3         | 1.01%   |
| openSUSE      | 3         | 1.01%   |
| Lubuntu       | 3         | 1.01%   |
| EndeavourOS   | 3         | 1.01%   |
| ArcoLinux     | 3         | 1.01%   |
| ROSA          | 2         | 0.67%   |
| RHEL          | 2         | 0.67%   |
| Raspbian      | 2         | 0.67%   |
| Kali          | 2         | 0.67%   |
| Gentoo        | 2         | 0.67%   |
| Endless       | 2         | 0.67%   |
| Clear Linux   | 2         | 0.67%   |
| Ubuntu MATE   | 1         | 0.34%   |
| Ubuntu Budgie | 1         | 0.34%   |
| Q4OS          | 1         | 0.34%   |
| Nobara        | 1         | 0.34%   |
| LMDE          | 1         | 0.34%   |
| Garuda Linux  | 1         | 0.34%   |
| Devuan        | 1         | 0.34%   |
| Deepin        | 1         | 0.34%   |
| CentOS        | 1         | 0.34%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 5.15.0-46-generic       | 9         | 2.7%    |
| 5.9.8-200.fc33.x86_64   | 6         | 1.8%    |
| 5.4.0-48-generic        | 6         | 1.8%    |
| 5.4.0-42-generic        | 6         | 1.8%    |
| 5.4.0-40-generic        | 6         | 1.8%    |
| 5.4.0-37-generic        | 6         | 1.8%    |
| 5.4.0-29-generic        | 6         | 1.8%    |
| 5.4.0-52-generic        | 5         | 1.5%    |
| 5.11.0-43-generic       | 5         | 1.5%    |
| 5.4.0-65-generic        | 4         | 1.2%    |
| 5.3.0-62-generic        | 4         | 1.2%    |
| 5.16.7-desktop-1omv4003 | 4         | 1.2%    |
| 5.4.0-7634-generic      | 3         | 0.9%    |
| 5.4.0-47-generic        | 3         | 0.9%    |
| 5.4.0-26-generic        | 3         | 0.9%    |
| 5.3.0-51-generic        | 3         | 0.9%    |
| 5.15.0-48-generic       | 3         | 0.9%    |
| 5.15.0-47-generic       | 3         | 0.9%    |
| 5.15.0-43-generic       | 3         | 0.9%    |
| 5.13.0-40-generic       | 3         | 0.9%    |
| 5.13.0-28-generic       | 3         | 0.9%    |
| 5.11.0-38-generic       | 3         | 0.9%    |
| 5.11.0-37-generic       | 3         | 0.9%    |
| 5.11.0-25-generic       | 3         | 0.9%    |
| 5.10.0-11-amd64         | 3         | 0.9%    |
| 5.0.0-23-generic        | 3         | 0.9%    |
| 5.8.0-7630-generic      | 2         | 0.6%    |
| 5.8.0-53-generic        | 2         | 0.6%    |
| 5.8.0-48-generic        | 2         | 0.6%    |
| 5.8.0-43-generic        | 2         | 0.6%    |
| 5.4.51-v7l+             | 2         | 0.6%    |
| 5.4.5-050405-generic    | 2         | 0.6%    |
| 5.4.0-96-generic        | 2         | 0.6%    |
| 5.4.0-81-generic        | 2         | 0.6%    |
| 5.4.0-7642-generic      | 2         | 0.6%    |
| 5.4.0-70-generic        | 2         | 0.6%    |
| 5.4.0-45-generic        | 2         | 0.6%    |
| 5.4.0-33-generic        | 2         | 0.6%    |
| 5.4.0-31-generic        | 2         | 0.6%    |
| 5.3.0-40-generic        | 2         | 0.6%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 68        | 21.45%  |
| 5.15.0  | 24        | 7.57%   |
| 5.11.0  | 21        | 6.62%   |
| 5.13.0  | 17        | 5.36%   |
| 5.8.0   | 16        | 5.05%   |
| 4.18.0  | 13        | 4.1%    |
| 5.3.0   | 12        | 3.79%   |
| 5.0.0   | 11        | 3.47%   |
| 4.15.0  | 10        | 3.15%   |
| 5.10.0  | 9         | 2.84%   |
| 5.9.8   | 6         | 1.89%   |
| 5.18.0  | 6         | 1.89%   |
| 5.16.7  | 4         | 1.26%   |
| 5.17.5  | 3         | 0.95%   |
| 5.13.13 | 3         | 0.95%   |
| 5.4.51  | 2         | 0.63%   |
| 5.4.5   | 2         | 0.63%   |
| 5.19.0  | 2         | 0.63%   |
| 5.15.5  | 2         | 0.63%   |
| 5.15.10 | 2         | 0.63%   |
| 5.13.12 | 2         | 0.63%   |
| 5.12.7  | 2         | 0.63%   |
| 5.10.14 | 2         | 0.63%   |
| 4.19.0  | 2         | 0.63%   |
| 3.10.0  | 2         | 0.63%   |
| 5.9.9   | 1         | 0.32%   |
| 5.9.16  | 1         | 0.32%   |
| 5.9.15  | 1         | 0.32%   |
| 5.9.11  | 1         | 0.32%   |
| 5.9.10  | 1         | 0.32%   |
| 5.8.7   | 1         | 0.32%   |
| 5.8.5   | 1         | 0.32%   |
| 5.8.4   | 1         | 0.32%   |
| 5.8.3   | 1         | 0.32%   |
| 5.8.18  | 1         | 0.32%   |
| 5.8.12  | 1         | 0.32%   |
| 5.8.11  | 1         | 0.32%   |
| 5.8.1   | 1         | 0.32%   |
| 5.7.0   | 1         | 0.32%   |
| 5.6.7   | 1         | 0.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 77        | 24.6%   |
| 5.15    | 35        | 11.18%  |
| 5.13    | 25        | 7.99%   |
| 5.8     | 24        | 7.67%   |
| 5.11    | 23        | 7.35%   |
| 5.10    | 18        | 5.75%   |
| 4.18    | 13        | 4.15%   |
| 5.3     | 12        | 3.83%   |
| 5.0     | 12        | 3.83%   |
| 5.18    | 11        | 3.51%   |
| 5.9     | 10        | 3.19%   |
| 5.16    | 10        | 3.19%   |
| 4.15    | 10        | 3.19%   |
| 5.12    | 6         | 1.92%   |
| 5.17    | 5         | 1.6%    |
| 5.6     | 4         | 1.28%   |
| 5.19    | 4         | 1.28%   |
| 5.14    | 3         | 0.96%   |
| 4.19    | 3         | 0.96%   |
| 5.5     | 2         | 0.64%   |
| 4.16    | 2         | 0.64%   |
| 3.10    | 2         | 0.64%   |
| 5.7     | 1         | 0.32%   |
| 4.4     | 1         | 0.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 280       | 97.56%  |
| aarch64 | 3         | 1.05%   |
| i686    | 2         | 0.7%    |
| armv7l  | 2         | 0.7%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 173       | 57.67%  |
| Unknown         | 44        | 14.67%  |
| KDE5            | 36        | 12%     |
| X-Cinnamon      | 11        | 3.67%   |
| XFCE            | 7         | 2.33%   |
| KDE             | 6         | 2%      |
| Cinnamon        | 6         | 2%      |
| LXQt            | 4         | 1.33%   |
| Unity           | 3         | 1%      |
| i3              | 3         | 1%      |
| GNOME Classic   | 2         | 0.67%   |
| Budgie          | 2         | 0.67%   |
| MATE            | 1         | 0.33%   |
| KDE4            | 1         | 0.33%   |
| GNOME Flashback | 1         | 0.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 226       | 76.87%  |
| Wayland | 35        | 11.9%   |
| Unknown | 22        | 7.48%   |
| Tty     | 11        | 3.74%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 155       | 52.19%  |
| GDM     | 62        | 20.88%  |
| SDDM    | 33        | 11.11%  |
| GDM3    | 29        | 9.76%   |
| LightDM | 12        | 4.04%   |
| TDM     | 5         | 1.68%   |
| KDM     | 1         | 0.34%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_SG   | 117       | 40.21%  |
| en_US   | 109       | 37.46%  |
| Unknown | 26        | 8.93%   |
| C       | 9         | 3.09%   |
| zh_CN   | 6         | 2.06%   |
| en_IN   | 6         | 2.06%   |
| en_AU   | 5         | 1.72%   |
| de_DE   | 5         | 1.72%   |
| en_GB   | 4         | 1.37%   |
| ru_UA   | 1         | 0.34%   |
| fr_FR   | 1         | 0.34%   |
| en_PH   | 1         | 0.34%   |
| en_IE   | 1         | 0.34%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 190       | 65.97%  |
| BIOS | 98        | 34.03%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 240       | 82.76%  |
| Btrfs   | 21        | 7.24%   |
| Overlay | 10        | 3.45%   |
| Unknown | 10        | 3.45%   |
| Xfs     | 7         | 2.41%   |
| Zfs     | 2         | 0.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 156       | 53.98%  |
| GPT     | 121       | 41.87%  |
| MBR     | 12        | 4.15%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 254       | 86.39%  |
| Yes       | 40        | 13.61%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 195       | 67.47%  |
| Yes       | 94        | 32.53%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 54        | 18.82%  |
| Dell                    | 53        | 18.47%  |
| ASUSTek Computer        | 47        | 16.38%  |
| Acer                    | 24        | 8.36%   |
| Hewlett-Packard         | 20        | 6.97%   |
| MSI                     | 15        | 5.23%   |
| Gigabyte Technology     | 14        | 4.88%   |
| Apple                   | 11        | 3.83%   |
| ASRock                  | 9         | 3.14%   |
| Sony                    | 4         | 1.39%   |
| Raspberry Pi Foundation | 4         | 1.39%   |
| Intel                   | 4         | 1.39%   |
| Microsoft               | 3         | 1.05%   |
| congatec                | 3         | 1.05%   |
| Toshiba                 | 2         | 0.7%    |
| Timi                    | 2         | 0.7%    |
| Samsung Electronics     | 2         | 0.7%    |
| Foxconn                 | 2         | 0.7%    |
| AMI                     | 2         | 0.7%    |
| Aftershock              | 2         | 0.7%    |
| Razer                   | 1         | 0.35%   |
| Notebook                | 1         | 0.35%   |
| MECHREVO                | 1         | 0.35%   |
| LattePanda              | 1         | 0.35%   |
| INET                    | 1         | 0.35%   |
| Fujitsu                 | 1         | 0.35%   |
| ECS                     | 1         | 0.35%   |
| COPELION INTERNATIONAL  | 1         | 0.35%   |
| Biostar                 | 1         | 0.35%   |
| Unknown                 | 1         | 0.35%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| ASUS All Series                                       | 4         | 1.39%   |
| MSI MS-7C84                                           | 3         | 1.05%   |
| Gigabyte X570 AORUS PRO WIFI                          | 3         | 1.05%   |
| congatec conga-MA5 B.2                                | 3         | 1.05%   |
| RPi Raspberry Pi 4 Model B Rev 1.4                    | 2         | 0.7%    |
| RPi Raspberry Pi 4 Model B Rev 1.2                    | 2         | 0.7%    |
| Lenovo ThinkPad X220 42911H8                          | 2         | 0.7%    |
| Lenovo Legion 5 Pro 16ACH6H 82JQ                      | 2         | 0.7%    |
| Lenovo IdeaPad S340-14API 81NB                        | 2         | 0.7%    |
| Intel NUC11PAHi7                                      | 2         | 0.7%    |
| HP Compaq 6510b                                       | 2         | 0.7%    |
| Gigabyte B550I AORUS PRO AX                           | 2         | 0.7%    |
| Foxconn Kangaroo Mobile Desktop                       | 2         | 0.7%    |
| Dell OptiPlex 990                                     | 2         | 0.7%    |
| Dell OptiPlex 9020                                    | 2         | 0.7%    |
| Dell Latitude 3320                                    | 2         | 0.7%    |
| Dell Latitude 3120                                    | 2         | 0.7%    |
| Dell Inspiron 15 5510                                 | 2         | 0.7%    |
| ASUS T300LA                                           | 2         | 0.7%    |
| ASUS ROG STRIX B550-I GAMING                          | 2         | 0.7%    |
| Apple MacBookPro8,1                                   | 2         | 0.7%    |
| Apple iMac19,1                                        | 2         | 0.7%    |
| Acer ConceptD CN715-71                                | 2         | 0.7%    |
| Toshiba PORTEGE Z10t-A                                | 1         | 0.35%   |
| Toshiba PORTEGE R930                                  | 1         | 0.35%   |
| Timi TM1701                                           | 1         | 0.35%   |
| Timi Redmi Book Pro 14 2022                           | 1         | 0.35%   |
| Sony VPCSB36FG                                        | 1         | 0.35%   |
| Sony VPCCA15FG                                        | 1         | 0.35%   |
| Sony VGN-CR32G_W                                      | 1         | 0.35%   |
| Sony SVF1531V8CW                                      | 1         | 0.35%   |
| Samsung RF510/RF410/RF710                             | 1         | 0.35%   |
| Samsung 305U1A                                        | 1         | 0.35%   |
| Razer Blade 15 Advanced Model (Early 2020) - RZ09-033 | 1         | 0.35%   |
| Notebook P65_P67SE                                    | 1         | 0.35%   |
| MSI Pulse GL66 11UGK                                  | 1         | 0.35%   |
| MSI MS-7D43                                           | 1         | 0.35%   |
| MSI MS-7D30                                           | 1         | 0.35%   |
| MSI MS-7C52                                           | 1         | 0.35%   |
| MSI MS-7C02                                           | 1         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 28        | 9.76%   |
| Dell Inspiron       | 14        | 4.88%   |
| Dell Latitude       | 12        | 4.18%   |
| Acer Aspire         | 10        | 3.48%   |
| Dell OptiPlex       | 9         | 3.14%   |
| Dell XPS            | 8         | 2.79%   |
| HP Pavilion         | 7         | 2.44%   |
| Acer Swift          | 7         | 2.44%   |
| Lenovo IdeaPad      | 6         | 2.09%   |
| Dell Precision      | 6         | 2.09%   |
| ASUS VivoBook       | 6         | 2.09%   |
| Lenovo Legion       | 5         | 1.74%   |
| ASUS ROG            | 5         | 1.74%   |
| RPi Raspberry       | 4         | 1.39%   |
| Lenovo Yoga         | 4         | 1.39%   |
| ASUS ZenBook        | 4         | 1.39%   |
| ASUS All            | 4         | 1.39%   |
| MSI MS-7C84         | 3         | 1.05%   |
| Microsoft Surface   | 3         | 1.05%   |
| Lenovo ThinkCentre  | 3         | 1.05%   |
| HP EliteBook        | 3         | 1.05%   |
| Gigabyte X570       | 3         | 1.05%   |
| congatec conga-MA5  | 3         | 1.05%   |
| Toshiba PORTEGE     | 2         | 0.7%    |
| Lenovo ThinkStation | 2         | 0.7%    |
| Intel NUC11PAHi7    | 2         | 0.7%    |
| HP ZBook            | 2         | 0.7%    |
| HP ENVY             | 2         | 0.7%    |
| HP Compaq           | 2         | 0.7%    |
| Gigabyte B550I      | 2         | 0.7%    |
| Foxconn Kangaroo    | 2         | 0.7%    |
| ASUS TUF            | 2         | 0.7%    |
| ASUS T300LA         | 2         | 0.7%    |
| Apple MacBookPro8   | 2         | 0.7%    |
| Apple MacBookPro11  | 2         | 0.7%    |
| Apple iMac19        | 2         | 0.7%    |
| Acer Predator       | 2         | 0.7%    |
| Acer ConceptD       | 2         | 0.7%    |
| Timi TM1701         | 1         | 0.35%   |
| Timi Redmi          | 1         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 42        | 14.63%  |
| 2020    | 37        | 12.89%  |
| 2018    | 35        | 12.2%   |
| 2021    | 27        | 9.41%   |
| 2011    | 19        | 6.62%   |
| 2013    | 18        | 6.27%   |
| 2015    | 16        | 5.57%   |
| 2014    | 16        | 5.57%   |
| 2016    | 15        | 5.23%   |
| 2017    | 14        | 4.88%   |
| 2012    | 14        | 4.88%   |
| 2010    | 11        | 3.83%   |
| 2008    | 6         | 2.09%   |
| 2007    | 6         | 2.09%   |
| 2022    | 4         | 1.39%   |
| Unknown | 4         | 1.39%   |
| 2009    | 3         | 1.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 171       | 59.58%  |
| Desktop        | 82        | 28.57%  |
| Convertible    | 8         | 2.79%   |
| Mini pc        | 8         | 2.79%   |
| All in one     | 6         | 2.09%   |
| System on chip | 5         | 1.74%   |
| Tablet         | 5         | 1.74%   |
| Server         | 2         | 0.7%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 253       | 87.85%  |
| Enabled  | 35        | 12.15%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 287       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 77        | 26.46%  |
| 4.01-8.0        | 62        | 21.31%  |
| 8.01-16.0       | 50        | 17.18%  |
| 3.01-4.0        | 40        | 13.75%  |
| 32.01-64.0      | 36        | 12.37%  |
| 64.01-256.0     | 8         | 2.75%   |
| 1.01-2.0        | 8         | 2.75%   |
| 24.01-32.0      | 7         | 2.41%   |
| 2.01-3.0        | 2         | 0.69%   |
| More than 256.0 | 1         | 0.34%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 85        | 26.9%   |
| 2.01-3.0   | 76        | 24.05%  |
| 4.01-8.0   | 57        | 18.04%  |
| 3.01-4.0   | 55        | 17.41%  |
| 8.01-16.0  | 20        | 6.33%   |
| 0.51-1.0   | 16        | 5.06%   |
| 0.01-0.5   | 5         | 1.58%   |
| 16.01-24.0 | 2         | 0.63%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 185       | 63.14%  |
| 2      | 72        | 24.57%  |
| 3      | 21        | 7.17%   |
| 4      | 10        | 3.41%   |
| 0      | 3         | 1.02%   |
| 5      | 2         | 0.68%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 219       | 76.31%  |
| Yes       | 68        | 23.69%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 216       | 75%     |
| No        | 72        | 25%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 237       | 82.29%  |
| No        | 51        | 17.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 195       | 67.47%  |
| No        | 94        | 32.53%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Singapore | 287       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Singapore            | 275       | 95.82%  |
| Jurong West          | 7         | 2.44%   |
| Queenstown Estate    | 2         | 0.7%    |
| Sembawang Estate     | 1         | 0.35%   |
| Kampong Ulu Jurong   | 1         | 0.35%   |
| Bukit Batok New Town | 1         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 83        | 114    | 20.49%  |
| Seagate                   | 49        | 57     | 12.1%   |
| WDC                       | 40        | 68     | 9.88%   |
| Toshiba                   | 33        | 41     | 8.15%   |
| SanDisk                   | 25        | 28     | 6.17%   |
| Unknown                   | 19        | 21     | 4.69%   |
| SK hynix                  | 18        | 20     | 4.44%   |
| Hitachi                   | 13        | 14     | 3.21%   |
| HGST                      | 12        | 19     | 2.96%   |
| Kingston                  | 11        | 14     | 2.72%   |
| Intel                     | 10        | 12     | 2.47%   |
| Micron Technology         | 7         | 9      | 1.73%   |
| Crucial                   | 7         | 8      | 1.73%   |
| Phison                    | 6         | 8      | 1.48%   |
| JMicron Technology        | 6         | 7      | 1.48%   |
| Hewlett-Packard           | 5         | 6      | 1.23%   |
| Apple                     | 5         | 6      | 1.23%   |
| KIOXIA                    | 4         | 4      | 0.99%   |
| Lexar                     | 3         | 3      | 0.74%   |
| Lenovo                    | 3         | 3      | 0.74%   |
| China                     | 3         | 3      | 0.74%   |
| A-DATA Technology         | 3         | 3      | 0.74%   |
| Unknown                   | 3         | 3      | 0.74%   |
| Transcend                 | 2         | 3      | 0.49%   |
| Patriot                   | 2         | 2      | 0.49%   |
| OCZ                       | 2         | 2      | 0.49%   |
| Micron/Crucial Technology | 2         | 2      | 0.49%   |
| LITEON                    | 2         | 3      | 0.49%   |
| KLEVV                     | 2         | 2      | 0.49%   |
| Vaseky                    | 1         | 1      | 0.25%   |
| USB30                     | 1         | 1      | 0.25%   |
| UMIS                      | 1         | 1      | 0.25%   |
| TO Exter                  | 1         | 1      | 0.25%   |
| Team                      | 1         | 1      | 0.25%   |
| SPCC                      | 1         | 1      | 0.25%   |
| Silicon Motion            | 1         | 2      | 0.25%   |
| SAGE                      | 1         | 1      | 0.25%   |
| Realtek                   | 1         | 2      | 0.25%   |
| Plextor                   | 1         | 1      | 0.25%   |
| Pioneer                   | 1         | 1      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Toshiba DT01ACA100 1TB               | 7         | 1.63%   |
| Seagate ST1000LM035-1RK172 1TB       | 7         | 1.63%   |
| Samsung NVMe SSD Drive 1024GB        | 6         | 1.4%    |
| Unknown MMC Card  32GB               | 5         | 1.17%   |
| Samsung SSD 860 EVO 500GB            | 5         | 1.17%   |
| JMicron Generic 120GB                | 5         | 1.17%   |
| Toshiba DT01ACA200 2TB               | 4         | 0.93%   |
| Samsung SSD 970 EVO Plus 500GB       | 4         | 0.93%   |
| Samsung SSD 850 EVO 250GB            | 4         | 0.93%   |
| Crucial CT500MX500SSD1 500GB         | 4         | 0.93%   |
| Unknown MMC Card  64GB               | 3         | 0.7%    |
| Toshiba MQ04ABF100 1TB               | 3         | 0.7%    |
| Toshiba MQ01ABD100 1TB               | 3         | 0.7%    |
| SK hynix SKHynix_HFS001TDE9X084N 1TB | 3         | 0.7%    |
| Seagate ST1000DM010-2EP102 1TB       | 3         | 0.7%    |
| Seagate Expansion 1TB                | 3         | 0.7%    |
| SanDisk NVMe SSD Drive 512GB         | 3         | 0.7%    |
| Samsung SSD 850 EVO 500GB            | 3         | 0.7%    |
| Samsung SSD 840 EVO 250GB            | 3         | 0.7%    |
| Samsung NVMe SSD Drive 500GB         | 3         | 0.7%    |
| Samsung NVMe SSD Drive 256GB         | 3         | 0.7%    |
| HGST HTS721010A9E630 1TB             | 3         | 0.7%    |
| HGST HTS545050A7E380 500GB           | 3         | 0.7%    |
| Unknown                              | 3         | 0.7%    |
| WDC WDS500G2X0C-00L350 500GB         | 2         | 0.47%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 2         | 0.47%   |
| WDC WDS100T2X0C-00L350 1TB           | 2         | 0.47%   |
| WDC WD6400AAKS-22A7B2 640GB          | 2         | 0.47%   |
| WDC WD10SPZX-21Z10T0 1TB             | 2         | 0.47%   |
| WDC PC SN720 SED SDAQNTW-1T00 1TB    | 2         | 0.47%   |
| Toshiba NVMe SSD Drive 256GB         | 2         | 0.47%   |
| Toshiba MK5055GSX 500GB              | 2         | 0.47%   |
| SK hynix SC311 SATA 128GB SSD        | 2         | 0.47%   |
| SK hynix NVMe SSD Drive 256GB        | 2         | 0.47%   |
| SK hynix HFM512GDJTNG-8310A 512GB    | 2         | 0.47%   |
| Seagate ST2000DM008-2FR102 2TB       | 2         | 0.47%   |
| Seagate ST1000LM049-2GH172 1TB       | 2         | 0.47%   |
| Seagate BUP Portable 4TB             | 2         | 0.47%   |
| SanDisk SSD PLUS 240GB               | 2         | 0.47%   |
| SanDisk SSD PLUS 120 GB              | 2         | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 47        | 55     | 37.3%   |
| WDC                 | 24        | 33     | 19.05%  |
| Toshiba             | 23        | 29     | 18.25%  |
| Hitachi             | 13        | 14     | 10.32%  |
| HGST                | 12        | 19     | 9.52%   |
| Samsung Electronics | 2         | 4      | 1.59%   |
| Apple               | 2         | 2      | 1.59%   |
| SAGE                | 1         | 1      | 0.79%   |
| KESU                | 1         | 1      | 0.79%   |
| Fujitsu             | 1         | 1      | 0.79%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 45        | 62     | 36.29%  |
| SanDisk             | 17        | 18     | 13.71%  |
| Kingston            | 8         | 11     | 6.45%   |
| Crucial             | 6         | 7      | 4.84%   |
| WDC                 | 4         | 5      | 3.23%   |
| SK hynix            | 4         | 4      | 3.23%   |
| Hewlett-Packard     | 4         | 5      | 3.23%   |
| Micron Technology   | 3         | 5      | 2.42%   |
| China               | 3         | 3      | 2.42%   |
| Apple               | 3         | 3      | 2.42%   |
| Transcend           | 2         | 3      | 1.61%   |
| Patriot             | 2         | 2      | 1.61%   |
| OCZ                 | 2         | 2      | 1.61%   |
| LITEON              | 2         | 3      | 1.61%   |
| Lexar               | 2         | 2      | 1.61%   |
| A-DATA Technology   | 2         | 2      | 1.61%   |
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
| NVMe    | 123       | 178    | 33.24%  |
| HDD     | 114       | 159    | 30.81%  |
| SSD     | 110       | 153    | 29.73%  |
| MMC     | 19        | 21     | 5.14%   |
| Unknown | 4         | 4      | 1.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 180       | 295    | 52.02%  |
| NVMe | 122       | 167    | 35.26%  |
| SAS  | 25        | 32     | 7.23%   |
| MMC  | 19        | 21     | 5.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 125       | 179    | 55.56%  |
| 0.51-1.0   | 67        | 92     | 29.78%  |
| 1.01-2.0   | 17        | 22     | 7.56%   |
| 3.01-4.0   | 8         | 9      | 3.56%   |
| 4.01-10.0  | 5         | 7      | 2.22%   |
| 2.01-3.0   | 3         | 3      | 1.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 78        | 25.66%  |
| 251-500        | 57        | 18.75%  |
| 501-1000       | 53        | 17.43%  |
| 1001-2000      | 27        | 8.88%   |
| 1-20           | 20        | 6.58%   |
| 51-100         | 18        | 5.92%   |
| More than 3000 | 16        | 5.26%   |
| 21-50          | 14        | 4.61%   |
| Unknown        | 12        | 3.95%   |
| 2001-3000      | 9         | 2.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 113       | 36.93%  |
| 21-50          | 53        | 17.32%  |
| 101-250        | 44        | 14.38%  |
| 251-500        | 29        | 9.48%   |
| 51-100         | 29        | 9.48%   |
| 501-1000       | 13        | 4.25%   |
| Unknown        | 12        | 3.92%   |
| 1001-2000      | 6         | 1.96%   |
| More than 3000 | 4         | 1.31%   |
| 2001-3000      | 3         | 0.98%   |

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
| Detected | 180       | 296    | 57.32%  |
| Works    | 118       | 201    | 37.58%  |
| Malfunc  | 15        | 17     | 4.78%   |
| Failed   | 1         | 1      | 0.32%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 186       | 51.24%  |
| Samsung Electronics          | 45        | 12.4%   |
| AMD                          | 43        | 11.85%  |
| SanDisk                      | 22        | 6.06%   |
| SK hynix                     | 14        | 3.86%   |
| Toshiba America Info Systems | 8         | 2.2%    |
| KIOXIA                       | 7         | 1.93%   |
| Phison Electronics           | 6         | 1.65%   |
| Silicon Motion               | 4         | 1.1%    |
| Micron Technology            | 4         | 1.1%    |
| Nvidia                       | 3         | 0.83%   |
| Micron/Crucial Technology    | 3         | 0.83%   |
| Lenovo                       | 3         | 0.83%   |
| Kingston Technology Company  | 3         | 0.83%   |
| ASMedia Technology           | 3         | 0.83%   |
| Shenzhen Longsys Electronics | 2         | 0.55%   |
| ADATA Technology             | 2         | 0.55%   |
| VIA Technologies             | 1         | 0.28%   |
| Union Memory (Shenzhen)      | 1         | 0.28%   |
| Seagate Technology           | 1         | 0.28%   |
| Marvell Technology Group     | 1         | 0.28%   |
| Broadcom / LSI               | 1         | 0.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 33        | 8.42%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 27        | 6.89%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 17        | 4.34%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 12        | 3.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 12        | 3.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 11        | 2.81%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 9         | 2.3%    |
| Intel Volume Management Device NVMe RAID Controller                              | 8         | 2.04%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 8         | 2.04%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 7         | 1.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 7         | 1.79%   |
| Intel SATA Controller [RAID mode]                                                | 7         | 1.79%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 7         | 1.79%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 7         | 1.79%   |
| SK hynix Gold P31 SSD                                                            | 6         | 1.53%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 6         | 1.53%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 6         | 1.53%   |
| Samsung NVMe SSD Controller 980                                                  | 5         | 1.28%   |
| Intel Tiger Lake-LP SATA Controller                                              | 5         | 1.28%   |
| Intel SSD 660P Series                                                            | 5         | 1.28%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 5         | 1.28%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 5         | 1.28%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 5         | 1.28%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 4         | 1.02%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 4         | 1.02%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 4         | 1.02%   |
| Micron Non-Volatile memory controller                                            | 4         | 1.02%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 1.02%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 1.02%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 4         | 1.02%   |
| AMD 500 Series Chipset SATA Controller                                           | 4         | 1.02%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 3         | 0.77%   |
| SK hynix Non-Volatile memory controller                                          | 3         | 0.77%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 3         | 0.77%   |
| SanDisk Non-Volatile memory controller                                           | 3         | 0.77%   |
| Phison E12 NVMe Controller                                                       | 3         | 0.77%   |
| Lenovo Non-Volatile memory controller                                            | 3         | 0.77%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 0.77%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 3         | 0.77%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 0.77%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 188       | 51.79%  |
| NVMe | 123       | 33.88%  |
| RAID | 29        | 7.99%   |
| IDE  | 22        | 6.06%   |
| SAS  | 1         | 0.28%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 226       | 78.75%  |
| AMD    | 56        | 19.51%  |
| ARM    | 5         | 1.74%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 11        | 3.83%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 7         | 2.44%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 7         | 2.44%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 1.74%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 1.74%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 5         | 1.74%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 1.74%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 1.74%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 1.39%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 4         | 1.39%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.39%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 1.39%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.39%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 1.05%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 3         | 1.05%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 3         | 1.05%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 3         | 1.05%   |
| ARM Processor                                 | 3         | 1.05%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 1.05%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 3         | 1.05%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.05%   |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 2         | 0.7%    |
| Intel Pentium Silver N6000 @ 1.10GHz          | 2         | 0.7%    |
| Intel Core i7-8700 CPU @ 3.20GHz              | 2         | 0.7%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.7%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.7%    |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 0.7%    |
| Intel Core i7-10710U CPU @ 1.10GHz            | 2         | 0.7%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.7%    |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 0.7%    |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 0.7%    |
| Intel Core i5-7300U CPU @ 2.60GHz             | 2         | 0.7%    |
| Intel Core i5-4690 CPU @ 3.50GHz              | 2         | 0.7%    |
| Intel Core i5-4670K CPU @ 3.40GHz             | 2         | 0.7%    |
| Intel Core i5-3570 CPU @ 3.40GHz              | 2         | 0.7%    |
| Intel Core i5-3317U CPU @ 1.70GHz             | 2         | 0.7%    |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 0.7%    |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 2         | 0.7%    |
| Intel Core i5 CPU 650 @ 3.20GHz               | 2         | 0.7%    |
| Intel Core i3 CPU 550 @ 3.20GHz               | 2         | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 73        | 25.44%  |
| Intel Core i5           | 67        | 23.34%  |
| Other                   | 26        | 9.06%   |
| AMD Ryzen 5             | 17        | 5.92%   |
| AMD Ryzen 7             | 16        | 5.57%   |
| Intel Xeon              | 11        | 3.83%   |
| Intel Core i3           | 9         | 3.14%   |
| Intel Celeron           | 9         | 3.14%   |
| Intel Core 2 Duo        | 8         | 2.79%   |
| Intel Atom              | 6         | 2.09%   |
| Intel Core i9           | 4         | 1.39%   |
| Intel Pentium Silver    | 3         | 1.05%   |
| AMD Ryzen 9             | 3         | 1.05%   |
| Intel Pentium Dual      | 2         | 0.7%    |
| Intel Pentium           | 2         | 0.7%    |
| Intel Core m3           | 2         | 0.7%    |
| ARM BCM                 | 2         | 0.7%    |
| AMD Ryzen Threadripper  | 2         | 0.7%    |
| AMD Ryzen 7 PRO         | 2         | 0.7%    |
| AMD Ryzen 5 PRO         | 2         | 0.7%    |
| AMD Ryzen 3             | 2         | 0.7%    |
| AMD FX                  | 2         | 0.7%    |
| AMD Athlon              | 2         | 0.7%    |
| AMD A10                 | 2         | 0.7%    |
| Intel Xeon Silver       | 1         | 0.35%   |
| Intel Pentium Gold      | 1         | 0.35%   |
| Intel Pentium Dual-Core | 1         | 0.35%   |
| Intel Pentium 4         | 1         | 0.35%   |
| Intel Core m7           | 1         | 0.35%   |
| Intel Core 2 Quad       | 1         | 0.35%   |
| Intel Core 2            | 1         | 0.35%   |
| AMD Turion 64 X2 Mobile | 1         | 0.35%   |
| AMD PRO A10             | 1         | 0.35%   |
| AMD Phenom II X4        | 1         | 0.35%   |
| AMD E1                  | 1         | 0.35%   |
| AMD E                   | 1         | 0.35%   |
| AMD A6                  | 1         | 0.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 121       | 42.16%  |
| 2      | 88        | 30.66%  |
| 6      | 33        | 11.5%   |
| 8      | 30        | 10.45%  |
| 16     | 4         | 1.39%   |
| 12     | 3         | 1.05%   |
| 1      | 3         | 1.05%   |
| 14     | 2         | 0.7%    |
| 10     | 2         | 0.7%    |
| 3      | 1         | 0.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 286       | 99.65%  |
| 2      | 1         | 0.35%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 211       | 73.01%  |
| 1      | 78        | 26.99%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 280       | 97.56%  |
| Unknown        | 5         | 1.74%   |
| 32-bit         | 2         | 0.7%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 49        | 16.72%  |
| 0x906ea    | 16        | 5.46%   |
| 0x306a9    | 15        | 5.12%   |
| 0x806ea    | 14        | 4.78%   |
| 0x206a7    | 14        | 4.78%   |
| 0x306c3    | 13        | 4.44%   |
| 0x806ec    | 11        | 3.75%   |
| 0x506e3    | 9         | 3.07%   |
| 0x806c1    | 8         | 2.73%   |
| 0x20655    | 8         | 2.73%   |
| 0x806eb    | 7         | 2.39%   |
| 0x40651    | 7         | 2.39%   |
| 0x0a50000c | 7         | 2.39%   |
| 0x406e3    | 5         | 1.71%   |
| 0x306d4    | 5         | 1.71%   |
| 0x1067a    | 5         | 1.71%   |
| 0x08108109 | 5         | 1.71%   |
| 0x906e9    | 4         | 1.37%   |
| 0x806e9    | 4         | 1.37%   |
| 0x806d1    | 4         | 1.37%   |
| 0x6fd      | 4         | 1.37%   |
| 0x08701021 | 4         | 1.37%   |
| 0xa0652    | 3         | 1.02%   |
| 0x906ed    | 3         | 1.02%   |
| 0x806c2    | 3         | 1.02%   |
| 0x506ca    | 3         | 1.02%   |
| 0x50654    | 3         | 1.02%   |
| 0x406c3    | 3         | 1.02%   |
| 0x08701013 | 3         | 1.02%   |
| 0x08600106 | 3         | 1.02%   |
| 0x08108102 | 3         | 1.02%   |
| 0xa0660    | 2         | 0.68%   |
| 0x906c0    | 2         | 0.68%   |
| 0x706a1    | 2         | 0.68%   |
| 0x406f1    | 2         | 0.68%   |
| 0x40661    | 2         | 0.68%   |
| 0x306e4    | 2         | 0.68%   |
| 0x30678    | 2         | 0.68%   |
| 0x106c2    | 2         | 0.68%   |
| 0x0a201016 | 2         | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 69        | 24.04%  |
| Haswell          | 24        | 8.36%   |
| Skylake          | 18        | 6.27%   |
| SandyBridge      | 18        | 6.27%   |
| IvyBridge        | 18        | 6.27%   |
| Zen 2            | 15        | 5.23%   |
| TigerLake        | 14        | 4.88%   |
| Zen 3            | 13        | 4.53%   |
| Zen+             | 11        | 3.83%   |
| Unknown          | 11        | 3.83%   |
| Westmere         | 8         | 2.79%   |
| Silvermont       | 7         | 2.44%   |
| Penryn           | 7         | 2.44%   |
| Icelake          | 7         | 2.44%   |
| CometLake        | 7         | 2.44%   |
| Broadwell        | 7         | 2.44%   |
| Core             | 6         | 2.09%   |
| Zen              | 4         | 1.39%   |
| Goldmont plus    | 3         | 1.05%   |
| Goldmont         | 3         | 1.05%   |
| Tremont          | 2         | 0.7%    |
| Steamroller      | 2         | 0.7%    |
| Piledriver       | 2         | 0.7%    |
| K10              | 2         | 0.7%    |
| Excavator        | 2         | 0.7%    |
| Bonnell          | 2         | 0.7%    |
| NetBurst         | 1         | 0.35%   |
| K8 Hammer        | 1         | 0.35%   |
| Jaguar           | 1         | 0.35%   |
| Bobcat           | 1         | 0.35%   |
| Alderlake Hybrid | 1         | 0.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 189       | 52.35%  |
| Nvidia            | 109       | 30.19%  |
| AMD               | 61        | 16.9%   |
| ASPEED Technology | 2         | 0.55%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 17        | 4.58%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17        | 4.58%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 13        | 3.5%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 11        | 2.96%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 11        | 2.96%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 2.7%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 2.43%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 2.16%   |
| Intel HD Graphics 620                                                                    | 7         | 1.89%   |
| Intel HD Graphics 530                                                                    | 7         | 1.89%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 1.89%   |
| Nvidia GP108M [GeForce MX150]                                                            | 6         | 1.62%   |
| AMD Renoir                                                                               | 6         | 1.62%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 5         | 1.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 1.35%   |
| AMD Cezanne                                                                              | 5         | 1.35%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4         | 1.08%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 4         | 1.08%   |
| Intel HD Graphics 5500                                                                   | 4         | 1.08%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.08%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 1.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.08%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.81%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 3         | 0.81%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.81%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 3         | 0.81%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 0.81%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 0.81%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.81%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 0.81%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 0.81%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 0.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.81%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 0.81%   |
| Intel JasperLake [UHD Graphics]                                                          | 3         | 0.81%   |
| Intel HD Graphics 630                                                                    | 3         | 0.81%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 0.81%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 0.81%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 0.81%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 119       | 40.89%  |
| Intel + Nvidia  | 56        | 19.24%  |
| 1 x Nvidia      | 45        | 15.46%  |
| 1 x AMD         | 44        | 15.12%  |
| Intel + AMD     | 10        | 3.44%   |
| Other           | 5         | 1.72%   |
| AMD + Nvidia    | 4         | 1.37%   |
| 2 x Nvidia      | 3         | 1.03%   |
| 2 x AMD         | 3         | 1.03%   |
| Nvidia + ASPEED | 2         | 0.69%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 218       | 74.4%   |
| Proprietary | 63        | 21.5%   |
| Unknown     | 12        | 4.1%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 172       | 57.53%  |
| 1.01-2.0   | 43        | 14.38%  |
| 3.01-4.0   | 25        | 8.36%   |
| 0.01-0.5   | 18        | 6.02%   |
| 7.01-8.0   | 13        | 4.35%   |
| 0.51-1.0   | 11        | 3.68%   |
| 8.01-16.0  | 9         | 3.01%   |
| 5.01-6.0   | 7         | 2.34%   |
| 2.01-3.0   | 1         | 0.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 58        | 18.77%  |
| Dell                    | 44        | 14.24%  |
| Samsung Electronics     | 33        | 10.68%  |
| LG Display              | 28        | 9.06%   |
| BOE                     | 26        | 8.41%   |
| Chimei Innolux          | 16        | 5.18%   |
| Goldstar                | 12        | 3.88%   |
| Acer                    | 11        | 3.56%   |
| Apple                   | 10        | 3.24%   |
| Sharp                   | 9         | 2.91%   |
| Philips                 | 6         | 1.94%   |
| Hewlett-Packard         | 5         | 1.62%   |
| Lenovo                  | 4         | 1.29%   |
| InfoVision              | 4         | 1.29%   |
| CSO                     | 4         | 1.29%   |
| AOC                     | 4         | 1.29%   |
| PRISM+                  | 3         | 0.97%   |
| Denver                  | 3         | 0.97%   |
| PANDA                   | 2         | 0.65%   |
| LG Philips              | 2         | 0.65%   |
| Lenovo Group Limited    | 2         | 0.65%   |
| CVT                     | 2         | 0.65%   |
| ASUSTek Computer        | 2         | 0.65%   |
| Ancor Communications    | 2         | 0.65%   |
| Wacom                   | 1         | 0.32%   |
| ViewSonic               | 1         | 0.32%   |
| Unknown                 | 1         | 0.32%   |
| Toshiba                 | 1         | 0.32%   |
| Sony                    | 1         | 0.32%   |
| SGT                     | 1         | 0.32%   |
| SAC                     | 1         | 0.32%   |
| RTK                     | 1         | 0.32%   |
| Pixio                   | 1         | 0.32%   |
| MSI                     | 1         | 0.32%   |
| Mi                      | 1         | 0.32%   |
| HPN                     | 1         | 0.32%   |
| EXP                     | 1         | 0.32%   |
| CPT                     | 1         | 0.32%   |
| CHR                     | 1         | 0.32%   |
| Chi Mei Optoelectronics | 1         | 0.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 3         | 0.96%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 3         | 0.96%   |
| Goldstar LG HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch             | 3         | 0.96%   |
| Dell S2340L DELD058 1920x1080 510x290mm 23.1-inch                    | 3         | 0.96%   |
| Dell P2421D DELD0FF 2560x1440 530x300mm 24.0-inch                    | 3         | 0.96%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 3         | 0.96%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch | 2         | 0.64%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch    | 2         | 0.64%   |
| PRISM+ X315 INN3200 2560x1440 697x393mm 31.5-inch                    | 2         | 0.64%   |
| LG Philips LCD Monitor LPL8D00 1280x800 304x190mm 14.1-inch          | 2         | 0.64%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch         | 2         | 0.64%   |
| Hewlett-Packard 23es HWP331E 1920x1080 509x286mm 23.0-inch           | 2         | 0.64%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 2         | 0.64%   |
| Goldstar IPS224 GSM58D5 1920x1080 477x268mm 21.5-inch                | 2         | 0.64%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 2         | 0.64%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 600x340mm 27.2-inch               | 2         | 0.64%   |
| Denver F240v LHC0236 1920x1080 530x280mm 23.6-inch                   | 2         | 0.64%   |
| Dell SE2417HG DELD08C 1920x1080 521x293mm 23.5-inch                  | 2         | 0.64%   |
| Dell LCD Monitor P2217H 1920x1080                                    | 2         | 0.64%   |
| Dell E2213H DELA08F 1920x1080 477x268mm 21.5-inch                    | 2         | 0.64%   |
| Dell E2011H DEL406C 1600x900 443x249mm 20.0-inch                     | 2         | 0.64%   |
| Chimei Innolux LCD Monitor CMN1354 1920x1080 293x165mm 13.2-inch     | 2         | 0.64%   |
| BOE LCD Monitor BOE09C3 1366x768 256x144mm 11.6-inch                 | 2         | 0.64%   |
| BOE LCD Monitor BOE06A7 1920x1080 294x165mm 13.3-inch                | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 344x193mm 15.5-inch       | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch       | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO3892 1920x1080 344x194mm 15.5-inch       | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO31EB 3840x2160 344x193mm 15.5-inch       | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch       | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch        | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO2B99 1920x1080 293x165mm 13.2-inch       | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO205C 1366x768 256x144mm 11.6-inch        | 2         | 0.64%   |
| Apple iMac APPAE25 3840x2160 597x336mm 27.0-inch                     | 2         | 0.64%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                 | 2         | 0.64%   |
| Acer S201HL ACR01A5 1600x900 443x249mm 20.0-inch                     | 2         | 0.64%   |
| Acer EB321HQU ACR0507 2560x1440 699x393mm 31.6-inch                  | 2         | 0.64%   |
| Wacom CintiqPro24P WAC1063 3840x2160 522x293mm 23.6-inch             | 1         | 0.32%   |
| ViewSonic LCD Monitor VX2480-2K 2560x1440                            | 1         | 0.32%   |
| Unknown LCD Monitor AAA HDTV 3286x1080                               | 1         | 0.32%   |
| Toshiba LCD TV LCD0030 1920x1080 708x398mm 32.0-inch                 | 1         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 155       | 52.54%  |
| 1366x768 (WXGA)    | 35        | 11.86%  |
| 3840x2160 (4K)     | 26        | 8.81%   |
| 2560x1440 (QHD)    | 21        | 7.12%   |
| 1600x900 (HD+)     | 10        | 3.39%   |
| 1280x800 (WXGA)    | 9         | 3.05%   |
| 2560x1600          | 5         | 1.69%   |
| 1920x1200 (WUXGA)  | 5         | 1.69%   |
| 1360x768           | 4         | 1.36%   |
| 3440x1440          | 3         | 1.02%   |
| 3200x1800 (QHD+)   | 2         | 0.68%   |
| 2880x1800          | 2         | 0.68%   |
| 2736x1824          | 2         | 0.68%   |
| 2240x1400          | 2         | 0.68%   |
| 1440x900 (WXGA+)   | 2         | 0.68%   |
| 1280x1024 (SXGA)   | 2         | 0.68%   |
| 3840x2400          | 1         | 0.34%   |
| 3840x1600          | 1         | 0.34%   |
| 3286x1080          | 1         | 0.34%   |
| 3000x2000          | 1         | 0.34%   |
| 2560x1080          | 1         | 0.34%   |
| 2496x1664          | 1         | 0.34%   |
| 1680x1050 (WSXGA+) | 1         | 0.34%   |
| 1280x720 (HD)      | 1         | 0.34%   |
| 1024x600           | 1         | 0.34%   |
| Unknown            | 1         | 0.34%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 61        | 19.87%  |
| 13      | 50        | 16.29%  |
| 14      | 37        | 12.05%  |
| 27      | 28        | 9.12%   |
| 23      | 22        | 7.17%   |
| 24      | 18        | 5.86%   |
| Unknown | 13        | 4.23%   |
| 21      | 12        | 3.91%   |
| 12      | 12        | 3.91%   |
| 20      | 8         | 2.61%   |
| 18      | 6         | 1.95%   |
| 11      | 6         | 1.95%   |
| 31      | 5         | 1.63%   |
| 19      | 5         | 1.63%   |
| 16      | 4         | 1.3%    |
| 32      | 3         | 0.98%   |
| 34      | 2         | 0.65%   |
| 28      | 2         | 0.65%   |
| 25      | 2         | 0.65%   |
| 84      | 1         | 0.33%   |
| 55      | 1         | 0.33%   |
| 54      | 1         | 0.33%   |
| 52      | 1         | 0.33%   |
| 40      | 1         | 0.33%   |
| 39      | 1         | 0.33%   |
| 37      | 1         | 0.33%   |
| 35      | 1         | 0.33%   |
| 22      | 1         | 0.33%   |
| 17      | 1         | 0.33%   |
| 10      | 1         | 0.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 119       | 38.76%  |
| 501-600     | 70        | 22.8%   |
| 201-300     | 49        | 15.96%  |
| 401-500     | 29        | 9.45%   |
| Unknown     | 13        | 4.23%   |
| 601-700     | 7         | 2.28%   |
| 351-400     | 7         | 2.28%   |
| 701-800     | 5         | 1.63%   |
| 801-900     | 4         | 1.3%    |
| 1001-1500   | 3         | 0.98%   |
| 1501-2000   | 1         | 0.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 224       | 80.87%  |
| 16/10   | 29        | 10.47%  |
| Unknown | 11        | 3.97%   |
| 3/2     | 5         | 1.81%   |
| 21/9    | 5         | 1.81%   |
| 5/4     | 2         | 0.72%   |
| 6/5     | 1         | 0.36%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 61        | 19.93%  |
| 101-110        | 61        | 19.93%  |
| 201-250        | 45        | 14.71%  |
| 301-350        | 28        | 9.15%   |
| 71-80          | 27        | 8.82%   |
| 151-200        | 16        | 5.23%   |
| Unknown        | 13        | 4.25%   |
| 351-500        | 12        | 3.92%   |
| 61-70          | 11        | 3.59%   |
| 251-300        | 8         | 2.61%   |
| 51-60          | 6         | 1.96%   |
| 141-150        | 5         | 1.63%   |
| More than 1000 | 4         | 1.31%   |
| 111-120        | 4         | 1.31%   |
| 501-1000       | 3         | 0.98%   |
| 41-50          | 1         | 0.33%   |
| 121-130        | 1         | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 99        | 33.11%  |
| 51-100        | 77        | 25.75%  |
| 101-120       | 52        | 17.39%  |
| 161-240       | 42        | 14.05%  |
| Unknown       | 13        | 4.35%   |
| More than 240 | 12        | 4.01%   |
| 1-50          | 4         | 1.34%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 236       | 79.73%  |
| 2     | 44        | 14.86%  |
| 0     | 15        | 5.07%   |
| 3     | 1         | 0.34%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 168       | 40.88%  |
| Realtek Semiconductor    | 121       | 29.44%  |
| Qualcomm Atheros         | 49        | 11.92%  |
| Broadcom                 | 23        | 5.6%    |
| ASIX Electronics         | 7         | 1.7%    |
| MediaTek                 | 6         | 1.46%   |
| TP-Link                  | 5         | 1.22%   |
| Marvell Technology Group | 4         | 0.97%   |
| Samsung Electronics      | 3         | 0.73%   |
| Broadcom Limited         | 3         | 0.73%   |
| Sierra Wireless          | 2         | 0.49%   |
| Ralink Technology        | 2         | 0.49%   |
| Lenovo                   | 2         | 0.49%   |
| Hewlett-Packard          | 2         | 0.49%   |
| STMicroelectronics       | 1         | 0.24%   |
| Ralink                   | 1         | 0.24%   |
| Qualcomm                 | 1         | 0.24%   |
| Nvidia                   | 1         | 0.24%   |
| MosChip Semiconductor    | 1         | 0.24%   |
| Microsoft                | 1         | 0.24%   |
| Linksys                  | 1         | 0.24%   |
| Google                   | 1         | 0.24%   |
| Fargo                    | 1         | 0.24%   |
| Exar                     | 1         | 0.24%   |
| Edimax Technology        | 1         | 0.24%   |
| D-Link                   | 1         | 0.24%   |
| Aquantia                 | 1         | 0.24%   |
| Apple                    | 1         | 0.24%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 70        | 14.37%  |
| Intel Wi-Fi 6 AX200                                               | 27        | 5.54%   |
| Intel Wireless 7265                                               | 13        | 2.67%   |
| Intel Wi-Fi 6 AX201                                               | 13        | 2.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13        | 2.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 12        | 2.46%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 2.26%   |
| Intel Wireless 8265 / 8275                                        | 10        | 2.05%   |
| Intel I211 Gigabit Network Connection                             | 10        | 2.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 9         | 1.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 1.64%   |
| Intel Wireless 7260                                               | 8         | 1.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 1.44%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 1.44%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 7         | 1.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 7         | 1.44%   |
| ASIX AX88179 Gigabit Ethernet                                     | 7         | 1.44%   |
| Intel Ethernet Controller I225-V                                  | 6         | 1.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 1.23%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 5         | 1.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 1.03%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 5         | 1.03%   |
| Intel Wireless 3165                                               | 5         | 1.03%   |
| Realtek 802.11ac NIC                                              | 4         | 0.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 0.82%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 0.82%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 0.82%   |
| Intel Ethernet Connection (10) I219-V                             | 4         | 0.82%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 0.82%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.62%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 0.62%   |
| Intel Wireless-AC 9260                                            | 3         | 0.62%   |
| Intel Wireless 8260                                               | 3         | 0.62%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 3         | 0.62%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.62%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.62%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 0.62%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.62%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 137       | 55.24%  |
| Qualcomm Atheros         | 40        | 16.13%  |
| Realtek Semiconductor    | 28        | 11.29%  |
| Broadcom                 | 18        | 7.26%   |
| MediaTek                 | 6         | 2.42%   |
| TP-Link                  | 5         | 2.02%   |
| Sierra Wireless          | 2         | 0.81%   |
| Ralink Technology        | 2         | 0.81%   |
| Marvell Technology Group | 2         | 0.81%   |
| Broadcom Limited         | 2         | 0.81%   |
| Ralink                   | 1         | 0.4%    |
| Qualcomm                 | 1         | 0.4%    |
| Linksys                  | 1         | 0.4%    |
| Hewlett-Packard          | 1         | 0.4%    |
| Edimax Technology        | 1         | 0.4%    |
| D-Link                   | 1         | 0.4%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 27        | 10.84%  |
| Intel Wireless 7265                                                     | 13        | 5.22%   |
| Intel Wi-Fi 6 AX201                                                     | 13        | 5.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 12        | 4.82%   |
| Intel Wireless 8265 / 8275                                              | 10        | 4.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 3.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 3.21%   |
| Intel Wireless 7260                                                     | 8         | 3.21%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 2.81%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 2.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 2.41%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 2.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 2.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 2.01%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 2.01%   |
| Intel Wireless 3165                                                     | 5         | 2.01%   |
| Realtek 802.11ac NIC                                                    | 4         | 1.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 1.2%    |
| Intel Wireless-AC 9260                                                  | 3         | 1.2%    |
| Intel Wireless 8260                                                     | 3         | 1.2%    |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 1.2%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.2%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 3         | 1.2%    |
| Broadcom BCM4331 802.11a/b/g/n                                          | 3         | 1.2%    |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                              | 2         | 0.8%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 2         | 0.8%    |
| Sierra Wireless EM7455                                                  | 2         | 0.8%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 0.8%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 2         | 0.8%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 0.8%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.8%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.8%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.8%    |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 2         | 0.8%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 0.8%    |
| Intel Wi-Fi 6 AX201 160MHz                                              | 2         | 0.8%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 0.8%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 0.8%    |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 101       | 44.1%   |
| Intel                    | 81        | 35.37%  |
| Qualcomm Atheros         | 14        | 6.11%   |
| Broadcom                 | 11        | 4.8%    |
| ASIX Electronics         | 7         | 3.06%   |
| Samsung Electronics      | 3         | 1.31%   |
| Marvell Technology Group | 2         | 0.87%   |
| Lenovo                   | 2         | 0.87%   |
| Nvidia                   | 1         | 0.44%   |
| MosChip Semiconductor    | 1         | 0.44%   |
| Microsoft                | 1         | 0.44%   |
| Hewlett-Packard          | 1         | 0.44%   |
| Google                   | 1         | 0.44%   |
| Broadcom Limited         | 1         | 0.44%   |
| Aquantia                 | 1         | 0.44%   |
| Apple                    | 1         | 0.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 70        | 29.79%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13        | 5.53%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 4.68%   |
| Intel I211 Gigabit Network Connection                             | 10        | 4.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 2.98%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 2.98%   |
| ASIX AX88179 Gigabit Ethernet                                     | 7         | 2.98%   |
| Intel Ethernet Controller I225-V                                  | 6         | 2.55%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.7%    |
| Intel Ethernet Connection (2) I219-V                              | 4         | 1.7%    |
| Intel Ethernet Connection (10) I219-V                             | 4         | 1.7%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 1.7%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 1.28%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.28%   |
| Intel Ethernet Connection I217-V                                  | 3         | 1.28%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 1.28%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.28%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.28%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.85%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.85%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.85%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.85%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.85%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.85%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.85%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.85%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.85%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.85%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.85%   |
| Intel Ethernet Connection (14) I219-LM                            | 2         | 0.85%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.85%   |
| Intel 82578DM Gigabit Network Connection                          | 2         | 0.85%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.85%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 0.85%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 0.85%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.43%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 0.43%   |
| Realtek Realtek Ethernet controller                               | 1         | 0.43%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 237       | 51.97%  |
| Ethernet | 216       | 47.37%  |
| Modem    | 2         | 0.44%   |
| Unknown  | 1         | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 189       | 62.38%  |
| Ethernet | 113       | 37.29%  |
| Unknown  | 1         | 0.33%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 143       | 49.65%  |
| 1     | 132       | 45.83%  |
| 0     | 7         | 2.43%   |
| 3     | 5         | 1.74%   |
| 4     | 1         | 0.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 270       | 94.08%  |
| Yes  | 17        | 5.92%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 113       | 56.5%   |
| Qualcomm Atheros Communications | 13        | 6.5%    |
| IMC Networks                    | 11        | 5.5%    |
| Foxconn / Hon Hai               | 11        | 5.5%    |
| Broadcom                        | 9         | 4.5%    |
| Realtek Semiconductor           | 8         | 4%      |
| Apple                           | 8         | 4%      |
| Lite-On Technology              | 7         | 3.5%    |
| Cambridge Silicon Radio         | 7         | 3.5%    |
| TP-Link                         | 3         | 1.5%    |
| Marvell Semiconductor           | 2         | 1%      |
| Toshiba                         | 1         | 0.5%    |
| SINO WEALTH                     | 1         | 0.5%    |
| Realtek                         | 1         | 0.5%    |
| Ralink Technology               | 1         | 0.5%    |
| MediaTek                        | 1         | 0.5%    |
| Foxconn International           | 1         | 0.5%    |
| Chicony Electronics             | 1         | 0.5%    |
| Alps Electric                   | 1         | 0.5%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 37        | 18.41%  |
| Intel AX201 Bluetooth                               | 28        | 13.93%  |
| Intel AX200 Bluetooth                               | 23        | 11.44%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 20        | 9.95%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7         | 3.48%   |
| Qualcomm Atheros  Bluetooth Device                  | 6         | 2.99%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 5         | 2.49%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 1.99%   |
| IMC Networks Bluetooth Radio                        | 4         | 1.99%   |
| IMC Networks Bluetooth Device                       | 4         | 1.99%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 1.99%   |
| Apple Bluetooth Host Controller                     | 4         | 1.99%   |
| TP-Link UB500 Adapter                               | 3         | 1.49%   |
| Realtek Bluetooth Radio                             | 3         | 1.49%   |
| Lite-On Bluetooth Device                            | 3         | 1.49%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.49%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 1.49%   |
| Foxconn / Hon Hai BCM20702A0                        | 3         | 1.49%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 1.49%   |
| Marvell Bluetooth and Wireless LAN Composite        | 2         | 1%      |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 1%      |
| Intel AX210 Bluetooth                               | 2         | 1%      |
| IMC Networks Wireless_Device                        | 2         | 1%      |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1%      |
| Broadcom BCM2045 Bluetooth                          | 2         | 1%      |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 1%      |
| Apple Bluetooth USB Host Controller                 | 2         | 1%      |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.5%    |
| SINO WEALTH RK Bluetooth Keyboar                    | 1         | 0.5%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.5%    |
| Realtek Bluetooth Radio                             | 1         | 0.5%    |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.5%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.5%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.5%    |
| MediaTek Wireless_Device                            | 1         | 0.5%    |
| Lite-On Bluetooth Radio                             | 1         | 0.5%    |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.5%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.5%    |
| IMC Networks Bluetooth module                       | 1         | 0.5%    |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 217       | 58.65%  |
| Nvidia                      | 66        | 17.84%  |
| AMD                         | 63        | 17.03%  |
| Kingston Technology         | 2         | 0.54%   |
| C-Media Electronics         | 2         | 0.54%   |
| Apple                       | 2         | 0.54%   |
| XMOS                        | 1         | 0.27%   |
| Unknown                     | 1         | 0.27%   |
| SteelSeries ApS             | 1         | 0.27%   |
| Sony                        | 1         | 0.27%   |
| Samson Technologies         | 1         | 0.27%   |
| Realtek Semiconductor       | 1         | 0.27%   |
| Razer USA                   | 1         | 0.27%   |
| Plantronics                 | 1         | 0.27%   |
| NXP Semiconductors          | 1         | 0.27%   |
| Micro Star International    | 1         | 0.27%   |
| Logitech                    | 1         | 0.27%   |
| Lenovo                      | 1         | 0.27%   |
| JMTek                       | 1         | 0.27%   |
| JBL                         | 1         | 0.27%   |
| FiiO Electronics Technology | 1         | 0.27%   |
| Cooler Master               | 1         | 0.27%   |
| Conexant Systems            | 1         | 0.27%   |
| ASUSTek Computer            | 1         | 0.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 30        | 6.91%   |
| AMD Family 17h/19h HD Audio Controller                                     | 30        | 6.91%   |
| Intel Cannon Lake PCH cAVS                                                 | 19        | 4.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 19        | 4.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 15        | 3.46%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 15        | 3.46%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 14        | 3.23%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 13        | 3%      |
| AMD Starship/Matisse HD Audio Controller                                   | 12        | 2.76%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 12        | 2.76%   |
| Intel Comet Lake PCH-LP cAVS                                               | 10        | 2.3%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 10        | 2.3%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 10        | 2.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9         | 2.07%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 1.84%   |
| Nvidia GP107GL High Definition Audio Controller                            | 7         | 1.61%   |
| Nvidia GA104 High Definition Audio Controller                              | 7         | 1.61%   |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 1.61%   |
| Intel 8 Series HD Audio Controller                                         | 7         | 1.61%   |
| Intel 200 Series PCH HD Audio                                              | 6         | 1.38%   |
| Nvidia TU104 HD Audio Controller                                           | 5         | 1.15%   |
| Nvidia GF108 High Definition Audio Controller                              | 5         | 1.15%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 1.15%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 5         | 1.15%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 1.15%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 1.15%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 1.15%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5         | 1.15%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 0.92%   |
| Nvidia GP102 HDMI Audio Controller                                         | 4         | 0.92%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4         | 0.92%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 0.92%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4         | 0.92%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 0.69%   |
| Nvidia GP106 High Definition Audio Controller                              | 3         | 0.69%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 0.69%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 0.69%   |
| Intel Jasper Lake HD Audio                                                 | 3         | 0.69%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 0.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| SK hynix                       | 43        | 22.28%  |
| Samsung Electronics            | 38        | 19.69%  |
| Micron Technology              | 23        | 11.92%  |
| Kingston                       | 20        | 10.36%  |
| Crucial                        | 17        | 8.81%   |
| Unknown                        | 10        | 5.18%   |
| Corsair                        | 7         | 3.63%   |
| G.Skill                        | 6         | 3.11%   |
| Transcend                      | 4         | 2.07%   |
| A-DATA Technology              | 4         | 2.07%   |
| Undefi                         | 3         | 1.55%   |
| Ramaxel Technology             | 3         | 1.55%   |
| Kingmax                        | 2         | 1.04%   |
| Elpida                         | 2         | 1.04%   |
| Unknown (ABCD)                 | 1         | 0.52%   |
| Unknown (0x02BA)               | 1         | 0.52%   |
| Team                           | 1         | 0.52%   |
| Qimonda                        | 1         | 0.52%   |
| Patriot                        | 1         | 0.52%   |
| Nanya Technology               | 1         | 0.52%   |
| MKF_SMBIOS_TYPE17_MANUFACTURER | 1         | 0.52%   |
| Lexar                          | 1         | 0.52%   |
| KLEVV                          | 1         | 0.52%   |
| Essencore Limited              | 1         | 0.52%   |
| ASint Technology               | 1         | 0.52%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 1.47%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 3         | 1.47%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.47%   |
| Crucial RAM CT32G4SFD832A.C16FE 32GB SODIMM DDR4 3200MT/s        | 3         | 1.47%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s              | 2         | 0.98%   |
| Undefi RAM Module 2GB SODIMM DDR3 1866MT/s                       | 2         | 0.98%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 2         | 0.98%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.98%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.98%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.98%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.98%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.98%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 2         | 0.98%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.98%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 0.98%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.98%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.98%   |
| Micron RAM MT52L512M32D2PF-10 4GB Row Of Chips LPDDR3 1867MT/s   | 2         | 0.98%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s             | 2         | 0.98%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 0.98%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 2         | 0.98%   |
| Kingston RAM KY7N41-MIE 8GB DIMM DDR4 2666MT/s                   | 2         | 0.98%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s              | 2         | 0.98%   |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1600MT/s            | 2         | 0.98%   |
| Kingmax RAM GLLG42F-DA--------- 8GB DIMM DDR4 2400MT/s           | 2         | 0.98%   |
| G.Skill RAM F4-3200C16-8GTZN 8GB DIMM DDR4 3200MT/s              | 2         | 0.98%   |
| Unknown RAM Module 8GB SODIMM DDR3 800MT/s                       | 1         | 0.49%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.49%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                             | 1         | 0.49%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.49%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                             | 1         | 0.49%   |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s                 | 1         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 1         | 0.49%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 0.49%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                    | 1         | 0.49%   |
| Unknown RAM Module 1GB SODIMM DDR3 1600MT/s                      | 1         | 0.49%   |
| Unknown RAM Module 16GB Row Of Chips LPDDR4 4267MT/s             | 1         | 0.49%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 1         | 0.49%   |
| Unknown (0x02BA) RAM Module 4096MB SODIMM DDR3 1333MT/s          | 1         | 0.49%   |
| Undefi RAM Module 4GB SODIMM DDR3 1866MT/s                       | 1         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 90        | 56.25%  |
| DDR3    | 47        | 29.38%  |
| LPDDR3  | 9         | 5.63%   |
| LPDDR4  | 8         | 5%      |
| DDR2    | 3         | 1.88%   |
| SDRAM   | 2         | 1.25%   |
| Unknown | 1         | 0.63%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 92        | 58.23%  |
| DIMM         | 46        | 29.11%  |
| Row Of Chips | 19        | 12.03%  |
| Chip         | 1         | 0.63%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 67        | 37.02%  |
| 4096  | 51        | 28.18%  |
| 16384 | 38        | 20.99%  |
| 2048  | 12        | 6.63%   |
| 32768 | 10        | 5.52%   |
| 1024  | 3         | 1.66%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 34        | 18.89%  |
| 1600    | 33        | 18.33%  |
| 2667    | 30        | 16.67%  |
| 2400    | 19        | 10.56%  |
| 2133    | 11        | 6.11%   |
| 4267    | 6         | 3.33%   |
| 1333    | 6         | 3.33%   |
| 1866    | 5         | 2.78%   |
| 3600    | 4         | 2.22%   |
| 1334    | 4         | 2.22%   |
| 2666    | 3         | 1.67%   |
| 1867    | 3         | 1.67%   |
| 3400    | 2         | 1.11%   |
| 3266    | 2         | 1.11%   |
| 2048    | 2         | 1.11%   |
| 1800    | 2         | 1.11%   |
| 1067    | 2         | 1.11%   |
| 800     | 2         | 1.11%   |
| 8400    | 1         | 0.56%   |
| 4800    | 1         | 0.56%   |
| 4333    | 1         | 0.56%   |
| 4199    | 1         | 0.56%   |
| 3666    | 1         | 0.56%   |
| 2200    | 1         | 0.56%   |
| 2134    | 1         | 0.56%   |
| 1200    | 1         | 0.56%   |
| 667     | 1         | 0.56%   |
| Unknown | 1         | 0.56%   |

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
| Chicony Electronics                    | 44        | 24.72%  |
| IMC Networks                           | 24        | 13.48%  |
| Microdia                               | 20        | 11.24%  |
| Realtek Semiconductor                  | 18        | 10.11%  |
| Sunplus Innovation Technology          | 11        | 6.18%   |
| Apple                                  | 10        | 5.62%   |
| Logitech                               | 8         | 4.49%   |
| Acer                                   | 8         | 4.49%   |
| Suyin                                  | 6         | 3.37%   |
| Samsung Electronics                    | 5         | 2.81%   |
| Syntek                                 | 4         | 2.25%   |
| Lite-On Technology                     | 4         | 2.25%   |
| Silicon Motion                         | 2         | 1.12%   |
| Ricoh                                  | 2         | 1.12%   |
| Z-Star Microelectronics                | 1         | 0.56%   |
| SunplusIT                              | 1         | 0.56%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.56%   |
| Quanta                                 | 1         | 0.56%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.56%   |
| Microsoft                              | 1         | 0.56%   |
| Magic Control Technology               | 1         | 0.56%   |
| Luxvisions Innotech Limited            | 1         | 0.56%   |
| Lenovo                                 | 1         | 0.56%   |
| Intel                                  | 1         | 0.56%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 0.56%   |
| Alcor Micro                            | 1         | 0.56%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD            | 14        | 7.82%   |
| Chicony HD WebCam                        | 10        | 5.59%   |
| Chicony Integrated Camera                | 9         | 5.03%   |
| IMC Networks Integrated Camera           | 7         | 3.91%   |
| Realtek Integrated_Webcam_HD             | 6         | 3.35%   |
| Sunplus Integrated_Webcam_HD             | 5         | 2.79%   |
| Samsung Galaxy A5 (MTP)                  | 5         | 2.79%   |
| IMC Networks USB2.0 HD UVC WebCam        | 5         | 2.79%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 4         | 2.23%   |
| IMC Networks USB2.0 HD IR UVC WebCam     | 4         | 2.23%   |
| Chicony HP HD Camera                     | 4         | 2.23%   |
| Apple FaceTime HD Camera (Built-in)      | 4         | 2.23%   |
| Syntek Integrated Camera                 | 3         | 1.68%   |
| Logitech HD Webcam C615                  | 3         | 1.68%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 3         | 1.68%   |
| Chicony HP Wide Vision HD Camera         | 3         | 1.68%   |
| Apple FaceTime HD Camera                 | 3         | 1.68%   |
| Acer Integrated Camera                   | 3         | 1.68%   |
| Realtek Integrated Webcam_HD             | 2         | 1.12%   |
| Realtek Asus 2.0 USB Webcam              | 2         | 1.12%   |
| Microdia USB 2.0 Camera                  | 2         | 1.12%   |
| Microdia Sonix USB 2.0 Camera            | 2         | 1.12%   |
| Logitech C922 Pro Stream Webcam          | 2         | 1.12%   |
| Lite-On HP Wide Vision HD Camera         | 2         | 1.12%   |
| IMC Networks Lenovo EasyCamera           | 2         | 1.12%   |
| Chicony USB2.0 HD UVC WebCam             | 2         | 1.12%   |
| Chicony USB2.0 Camera                    | 2         | 1.12%   |
| Chicony Integrated Camera [ThinkPad]     | 2         | 1.12%   |
| Chicony HD User Facing                   | 2         | 1.12%   |
| Apple iPhone5/5C/5S/6                    | 2         | 1.12%   |
| Acer BisonCam, NB Pro                    | 2         | 1.12%   |
| Z-Star Lenovo USB2.0 UVC Camera          | 1         | 0.56%   |
| Syntek Lenovo EasyCamera                 | 1         | 0.56%   |
| Suyin UVC HD Webcam                      | 1         | 0.56%   |
| Suyin Laptop_Integrated_Webcam_HD        | 1         | 0.56%   |
| Suyin HD WebCam                          | 1         | 0.56%   |
| Suyin Asus Integrated Webcam             | 1         | 0.56%   |
| Suyin Acer/Lenovo Webcam [CN0316]        | 1         | 0.56%   |
| Suyin Acer HD Crystal Eye webcam         | 1         | 0.56%   |
| SunplusIT XiaoMi USB 2.0 Webcam          | 1         | 0.56%   |

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
| 0     | 190       | 63.76%  |
| 1     | 82        | 27.52%  |
| 2     | 22        | 7.38%   |
| 3     | 3         | 1.01%   |
| 5     | 1         | 0.34%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 49        | 36.3%   |
| Graphics card            | 33        | 24.44%  |
| Net/wireless             | 17        | 12.59%  |
| Multimedia controller    | 6         | 4.44%   |
| Chipcard                 | 6         | 4.44%   |
| Camera                   | 5         | 3.7%    |
| Net/ethernet             | 4         | 2.96%   |
| Communication controller | 4         | 2.96%   |
| Unassigned class         | 3         | 2.22%   |
| Network                  | 2         | 1.48%   |
| Bluetooth                | 2         | 1.48%   |
| Wireless                 | 1         | 0.74%   |
| Storage/raid             | 1         | 0.74%   |
| Sound                    | 1         | 0.74%   |
| Firewire controller      | 1         | 0.74%   |


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

Total: 310

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| ASUSTek       | VivoBook_ASUSLaptop X409... | [a613776a9c](https://linux-hardware.org/?probe=a613776a9c) | Aug 18, 2021 |
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

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 46        | 21.5%   |
| Ubuntu 18.04                 | 18        | 8.41%   |
| Ubuntu 22.04                 | 12        | 5.61%   |
| Fedora 33                    | 10        | 4.67%   |
| Arch Rolling                 | 7         | 3.27%   |
| Pop!_OS 22.04                | 5         | 2.34%   |
| Pop!_OS 20.04                | 5         | 2.34%   |
| Arch                         | 5         | 2.34%   |
| OpenMandriva 23.01           | 4         | 1.87%   |
| Linux Mint 21                | 4         | 1.87%   |
| Debian Testing               | 4         | 1.87%   |
| Zorin 16                     | 3         | 1.4%    |
| Xubuntu 20.04                | 3         | 1.4%    |
| Linux Mint 20                | 3         | 1.4%    |
| Kubuntu 22.04                | 3         | 1.4%    |
| Fedora 36                    | 3         | 1.4%    |
| Fedora 32                    | 3         | 1.4%    |
| Elementary 6.1               | 3         | 1.4%    |
| Debian 11                    | 3         | 1.4%    |
| Debian                       | 3         | 1.4%    |
| ArcoLinux Rolling            | 3         | 1.4%    |
| Zorin 15                     | 2         | 0.93%   |
| Ubuntu 21.10                 | 2         | 0.93%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.93%   |
| OpenMandriva 4.3             | 2         | 0.93%   |
| Manjaro 20.1                 | 2         | 0.93%   |
| Kubuntu 20.10                | 2         | 0.93%   |
| Gentoo 2.6                   | 2         | 0.93%   |
| Garuda Linux Soaring         | 2         | 0.93%   |
| Fedora 35                    | 2         | 0.93%   |
| Fedora 34                    | 2         | 0.93%   |
| Fedora 31                    | 2         | 0.93%   |
| EndeavourOS Rolling          | 2         | 0.93%   |
| Xubuntu 21.04                | 1         | 0.47%   |
| Ubuntu Unity 16.04           | 1         | 0.47%   |
| Ubuntu Budgie 20.04          | 1         | 0.47%   |
| Ubuntu 22.10                 | 1         | 0.47%   |
| Ubuntu 21.04                 | 1         | 0.47%   |
| Ubuntu 19.10                 | 1         | 0.47%   |
| Ubuntu 19.04                 | 1         | 0.47%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 82        | 39.61%  |
| Fedora        | 20        | 9.66%   |
| Pop!_OS       | 13        | 6.28%   |
| Debian        | 12        | 5.8%    |
| Arch          | 11        | 5.31%   |
| OpenMandriva  | 8         | 3.86%   |
| Linux Mint    | 8         | 3.86%   |
| Kubuntu       | 6         | 2.9%    |
| Zorin         | 5         | 2.42%   |
| Manjaro       | 5         | 2.42%   |
| Xubuntu       | 4         | 1.93%   |
| Elementary    | 3         | 1.45%   |
| ArcoLinux     | 3         | 1.45%   |
| ROSA          | 2         | 0.97%   |
| RHEL          | 2         | 0.97%   |
| openSUSE      | 2         | 0.97%   |
| Lubuntu       | 2         | 0.97%   |
| KDE neon      | 2         | 0.97%   |
| Kali          | 2         | 0.97%   |
| Gentoo        | 2         | 0.97%   |
| Garuda Linux  | 2         | 0.97%   |
| Endless       | 2         | 0.97%   |
| EndeavourOS   | 2         | 0.97%   |
| Clear Linux   | 2         | 0.97%   |
| Ubuntu Unity  | 1         | 0.48%   |
| Ubuntu Budgie | 1         | 0.48%   |
| Q4OS          | 1         | 0.48%   |
| LMDE          | 1         | 0.48%   |
| Deepin        | 1         | 0.48%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.4.0-48-generic        | 5         | 2.11%   |
| 5.15.0-46-generic       | 5         | 2.11%   |
| 6.1.1-desktop-1omv2290  | 4         | 1.69%   |
| 5.9.8-200.fc33.x86_64   | 4         | 1.69%   |
| 5.4.0-42-generic        | 4         | 1.69%   |
| 5.4.0-40-generic        | 4         | 1.69%   |
| 5.3.0-62-generic        | 4         | 1.69%   |
| 5.15.0-56-generic       | 4         | 1.69%   |
| 5.11.0-43-generic       | 4         | 1.69%   |
| 5.4.0-65-generic        | 3         | 1.27%   |
| 5.4.0-52-generic        | 3         | 1.27%   |
| 5.4.0-47-generic        | 3         | 1.27%   |
| 5.4.0-37-generic        | 3         | 1.27%   |
| 5.4.0-29-generic        | 3         | 1.27%   |
| 5.15.0-41-generic       | 3         | 1.27%   |
| 5.13.0-28-generic       | 3         | 1.27%   |
| 5.11.0-38-generic       | 3         | 1.27%   |
| 6.0.6-76060006-generic  | 2         | 0.84%   |
| 5.4.5-050405-generic    | 2         | 0.84%   |
| 5.4.0-7634-generic      | 2         | 0.84%   |
| 5.4.0-31-generic        | 2         | 0.84%   |
| 5.4.0-26-generic        | 2         | 0.84%   |
| 5.18.0-3-amd64          | 2         | 0.84%   |
| 5.18.0-2-amd64          | 2         | 0.84%   |
| 5.17.5-76051705-generic | 2         | 0.84%   |
| 5.16.7-desktop-1omv4003 | 2         | 0.84%   |
| 5.15.0-58-generic       | 2         | 0.84%   |
| 5.15.0-48-generic       | 2         | 0.84%   |
| 5.15.0-47-generic       | 2         | 0.84%   |
| 5.15.0-43-generic       | 2         | 0.84%   |
| 5.13.0-40-generic       | 2         | 0.84%   |
| 5.13.0-37-generic       | 2         | 0.84%   |
| 5.11.0-37-generic       | 2         | 0.84%   |
| 5.11.0-25-generic       | 2         | 0.84%   |
| 5.0.0-23-generic        | 2         | 0.84%   |
| 4.18.0-15-generic       | 2         | 0.84%   |
| 6.1.3-arch1-1           | 1         | 0.42%   |
| 6.1.0-3-amd64           | 1         | 0.42%   |
| 6.1.0-1-MANJARO         | 1         | 0.42%   |
| 6.0.7-arch1-1           | 1         | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 38        | 16.89%  |
| 5.15.0  | 26        | 11.56%  |
| 5.11.0  | 13        | 5.78%   |
| 5.8.0   | 11        | 4.89%   |
| 5.13.0  | 10        | 4.44%   |
| 5.3.0   | 7         | 3.11%   |
| 4.18.0  | 7         | 3.11%   |
| 4.15.0  | 7         | 3.11%   |
| 5.18.0  | 6         | 2.67%   |
| 6.1.1   | 4         | 1.78%   |
| 5.9.8   | 4         | 1.78%   |
| 5.10.0  | 4         | 1.78%   |
| 5.0.0   | 4         | 1.78%   |
| 6.1.0   | 2         | 0.89%   |
| 6.0.7   | 2         | 0.89%   |
| 6.0.6   | 2         | 0.89%   |
| 6.0.0   | 2         | 0.89%   |
| 5.4.5   | 2         | 0.89%   |
| 5.19.13 | 2         | 0.89%   |
| 5.19.0  | 2         | 0.89%   |
| 5.17.5  | 2         | 0.89%   |
| 5.16.7  | 2         | 0.89%   |
| 5.13.13 | 2         | 0.89%   |
| 4.19.0  | 2         | 0.89%   |
| 6.1.3   | 1         | 0.44%   |
| 6.0.2   | 1         | 0.44%   |
| 5.9.9   | 1         | 0.44%   |
| 5.9.16  | 1         | 0.44%   |
| 5.9.15  | 1         | 0.44%   |
| 5.9.10  | 1         | 0.44%   |
| 5.8.7   | 1         | 0.44%   |
| 5.8.5   | 1         | 0.44%   |
| 5.8.4   | 1         | 0.44%   |
| 5.8.3   | 1         | 0.44%   |
| 5.8.12  | 1         | 0.44%   |
| 5.8.11  | 1         | 0.44%   |
| 5.7.0   | 1         | 0.44%   |
| 5.6.7   | 1         | 0.44%   |
| 5.6.5   | 1         | 0.44%   |
| 5.6.15  | 1         | 0.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 44        | 20%     |
| 5.15    | 31        | 14.09%  |
| 5.8     | 17        | 7.73%   |
| 5.13    | 16        | 7.27%   |
| 5.11    | 14        | 6.36%   |
| 5.18    | 10        | 4.55%   |
| 5.10    | 10        | 4.55%   |
| 6.0     | 7         | 3.18%   |
| 5.9     | 7         | 3.18%   |
| 5.3     | 7         | 3.18%   |
| 4.18    | 7         | 3.18%   |
| 4.15    | 7         | 3.18%   |
| 6.1     | 6         | 2.73%   |
| 5.16    | 6         | 2.73%   |
| 5.19    | 5         | 2.27%   |
| 5.0     | 5         | 2.27%   |
| 5.6     | 4         | 1.82%   |
| 5.17    | 4         | 1.82%   |
| 5.12    | 3         | 1.36%   |
| 4.19    | 3         | 1.36%   |
| 5.5     | 2         | 0.91%   |
| 5.7     | 1         | 0.45%   |
| 5.14    | 1         | 0.45%   |
| 4.4     | 1         | 0.45%   |
| 4.16    | 1         | 0.45%   |
| 3.10    | 1         | 0.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 196       | 98.99%  |
| i686   | 2         | 1.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 118       | 56.73%  |
| KDE5            | 32        | 15.38%  |
| Unknown         | 20        | 9.62%   |
| XFCE            | 8         | 3.85%   |
| X-Cinnamon      | 8         | 3.85%   |
| KDE             | 5         | 2.4%    |
| Cinnamon        | 4         | 1.92%   |
| Pantheon        | 3         | 1.44%   |
| LXQt            | 3         | 1.44%   |
| Unity           | 1         | 0.48%   |
| MATE            | 1         | 0.48%   |
| KDE4            | 1         | 0.48%   |
| i3              | 1         | 0.48%   |
| GNOME Flashback | 1         | 0.48%   |
| GNOME Classic   | 1         | 0.48%   |
| Budgie          | 1         | 0.48%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 154       | 75.49%  |
| Wayland | 31        | 15.2%   |
| Unknown | 13        | 6.37%   |
| Tty     | 6         | 2.94%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 94        | 45.19%  |
| GDM     | 40        | 19.23%  |
| SDDM    | 30        | 14.42%  |
| GDM3    | 28        | 13.46%  |
| LightDM | 11        | 5.29%   |
| TDM     | 4         | 1.92%   |
| KDM     | 1         | 0.48%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 79        | 39.11%  |
| en_SG   | 79        | 39.11%  |
| Unknown | 16        | 7.92%   |
| en_IN   | 6         | 2.97%   |
| C       | 6         | 2.97%   |
| zh_CN   | 5         | 2.48%   |
| de_DE   | 3         | 1.49%   |
| en_PH   | 2         | 0.99%   |
| en_GB   | 2         | 0.99%   |
| en_AU   | 2         | 0.99%   |
| ru_UA   | 1         | 0.5%    |
| en_IE   | 1         | 0.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 140       | 70%     |
| BIOS | 60        | 30%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 165       | 82.09%  |
| Btrfs   | 15        | 7.46%   |
| Overlay | 9         | 4.48%   |
| Unknown | 7         | 3.48%   |
| Xfs     | 3         | 1.49%   |
| Zfs     | 2         | 1%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 102       | 50.75%  |
| GPT     | 93        | 46.27%  |
| MBR     | 6         | 2.99%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 180       | 88.24%  |
| Yes       | 24        | 11.76%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 124       | 62%     |
| Yes       | 76        | 38%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 52        | 26.26%  |
| Dell                   | 41        | 20.71%  |
| ASUSTek Computer       | 31        | 15.66%  |
| Acer                   | 25        | 12.63%  |
| Hewlett-Packard        | 13        | 6.57%   |
| Apple                  | 7         | 3.54%   |
| Sony                   | 4         | 2.02%   |
| MSI                    | 4         | 2.02%   |
| Toshiba                | 2         | 1.01%   |
| Timi                   | 2         | 1.01%   |
| Samsung Electronics    | 2         | 1.01%   |
| HUAWEI                 | 2         | 1.01%   |
| Fujitsu                | 2         | 1.01%   |
| Foxconn                | 2         | 1.01%   |
| Aftershock             | 2         | 1.01%   |
| Razer                  | 1         | 0.51%   |
| Notebook               | 1         | 0.51%   |
| MECHREVO               | 1         | 0.51%   |
| Google                 | 1         | 0.51%   |
| COPELION INTERNATIONAL | 1         | 0.51%   |
| AMI                    | 1         | 0.51%   |
| Unknown                | 1         | 0.51%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Lenovo ThinkPad X220 42911H8                          | 2         | 1.01%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ                      | 2         | 1.01%   |
| Lenovo IdeaPad S340-14API 81NB                        | 2         | 1.01%   |
| HP Compaq 6510b                                       | 2         | 1.01%   |
| Foxconn Kangaroo Mobile Desktop                       | 2         | 1.01%   |
| Dell Latitude 3320                                    | 2         | 1.01%   |
| Dell Latitude 3120                                    | 2         | 1.01%   |
| Dell Inspiron 15 5510                                 | 2         | 1.01%   |
| ASUS VivoBook_ASUSLaptop M3500QC_M3500QC              | 2         | 1.01%   |
| ASUS T300LA                                           | 2         | 1.01%   |
| ASUS K45VM                                            | 2         | 1.01%   |
| Apple MacBookPro8,1                                   | 2         | 1.01%   |
| Acer ConceptD CN715-71                                | 2         | 1.01%   |
| Toshiba PORTEGE Z10t-A                                | 1         | 0.51%   |
| Toshiba PORTEGE R930                                  | 1         | 0.51%   |
| Timi TM1701                                           | 1         | 0.51%   |
| Timi Redmi Book Pro 14 2022                           | 1         | 0.51%   |
| Sony VPCSB36FG                                        | 1         | 0.51%   |
| Sony VPCCA15FG                                        | 1         | 0.51%   |
| Sony VGN-CR32G_W                                      | 1         | 0.51%   |
| Sony SVF1531V8CW                                      | 1         | 0.51%   |
| Samsung RF510/RF410/RF710                             | 1         | 0.51%   |
| Samsung 305U1A                                        | 1         | 0.51%   |
| Razer Blade 15 Advanced Model (Early 2020) - RZ09-033 | 1         | 0.51%   |
| Notebook P65_P67SE                                    | 1         | 0.51%   |
| MSI Pulse GL66 11UGK                                  | 1         | 0.51%   |
| MSI Modern 14 B5M                                     | 1         | 0.51%   |
| MSI GE63VR 7RE                                        | 1         | 0.51%   |
| MSI GE62VR 6RF                                        | 1         | 0.51%   |
| MECHREVO Code 01 Series PF5NU1G                       | 1         | 0.51%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS                    | 1         | 0.51%   |
| Lenovo Yoga 3 Pro-1370 80HE                           | 1         | 0.51%   |
| Lenovo Yoga 3 14 80JH                                 | 1         | 0.51%   |
| Lenovo ThinkPad X395 20NL000TCD                       | 1         | 0.51%   |
| Lenovo ThinkPad X390 20Q0CTO1WW                       | 1         | 0.51%   |
| Lenovo ThinkPad X240 20AMS00100                       | 1         | 0.51%   |
| Lenovo ThinkPad X230 23257VA                          | 1         | 0.51%   |
| Lenovo ThinkPad X230 23256N6                          | 1         | 0.51%   |
| Lenovo ThinkPad X220 Tablet 4298WBT                   | 1         | 0.51%   |
| Lenovo ThinkPad X220 4286C11                          | 1         | 0.51%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 30        | 15.15%  |
| Dell Inspiron      | 15        | 7.58%   |
| Dell Latitude      | 12        | 6.06%   |
| Acer Aspire        | 12        | 6.06%   |
| ASUS VivoBook      | 10        | 5.05%   |
| Lenovo IdeaPad     | 8         | 4.04%   |
| Dell XPS           | 8         | 4.04%   |
| Acer Swift         | 7         | 3.54%   |
| Lenovo Legion      | 6         | 3.03%   |
| HP Pavilion        | 4         | 2.02%   |
| Dell Precision     | 4         | 2.02%   |
| ASUS ZenBook       | 4         | 2.02%   |
| Lenovo Yoga        | 3         | 1.52%   |
| HP ZBook           | 3         | 1.52%   |
| HP EliteBook       | 3         | 1.52%   |
| Toshiba PORTEGE    | 2         | 1.01%   |
| HP Compaq          | 2         | 1.01%   |
| Fujitsu LIFEBOOK   | 2         | 1.01%   |
| Foxconn Kangaroo   | 2         | 1.01%   |
| ASUS TUF           | 2         | 1.01%   |
| ASUS T300LA        | 2         | 1.01%   |
| ASUS K45VM         | 2         | 1.01%   |
| ASUS ASUS          | 2         | 1.01%   |
| Apple MacBookPro8  | 2         | 1.01%   |
| Apple MacBookPro11 | 2         | 1.01%   |
| Acer Predator      | 2         | 1.01%   |
| Acer ConceptD      | 2         | 1.01%   |
| Timi TM1701        | 1         | 0.51%   |
| Timi Redmi         | 1         | 0.51%   |
| Sony VPCSB36FG     | 1         | 0.51%   |
| Sony VPCCA15FG     | 1         | 0.51%   |
| Sony VGN-CR32G     | 1         | 0.51%   |
| Sony SVF1531V8CW   | 1         | 0.51%   |
| Samsung RF510      | 1         | 0.51%   |
| Samsung 305U1A     | 1         | 0.51%   |
| Razer Blade        | 1         | 0.51%   |
| Notebook P65       | 1         | 0.51%   |
| MSI Pulse          | 1         | 0.51%   |
| MSI Modern         | 1         | 0.51%   |
| MSI GE63VR         | 1         | 0.51%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 27        | 13.64%  |
| 2019 | 26        | 13.13%  |
| 2020 | 24        | 12.12%  |
| 2018 | 20        | 10.1%   |
| 2011 | 14        | 7.07%   |
| 2022 | 11        | 5.56%   |
| 2017 | 11        | 5.56%   |
| 2014 | 11        | 5.56%   |
| 2012 | 11        | 5.56%   |
| 2016 | 10        | 5.05%   |
| 2015 | 9         | 4.55%   |
| 2013 | 7         | 3.54%   |
| 2010 | 5         | 2.53%   |
| 2007 | 5         | 2.53%   |
| 2008 | 4         | 2.02%   |
| 2009 | 3         | 1.52%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 198       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 165       | 82.5%   |
| Enabled  | 35        | 17.5%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 197       | 99.49%  |
| Yes  | 1         | 0.51%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 58        | 28.57%  |
| 4.01-8.0    | 49        | 24.14%  |
| 8.01-16.0   | 32        | 15.76%  |
| 3.01-4.0    | 31        | 15.27%  |
| 32.01-64.0  | 20        | 9.85%   |
| 1.01-2.0    | 6         | 2.96%   |
| 64.01-256.0 | 3         | 1.48%   |
| 24.01-32.0  | 2         | 0.99%   |
| 2.01-3.0    | 2         | 0.99%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 63        | 27.75%  |
| 2.01-3.0   | 54        | 23.79%  |
| 4.01-8.0   | 48        | 21.15%  |
| 3.01-4.0   | 34        | 14.98%  |
| 8.01-16.0  | 15        | 6.61%   |
| 0.51-1.0   | 10        | 4.41%   |
| 16.01-24.0 | 2         | 0.88%   |
| 0.01-0.5   | 1         | 0.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 145       | 71.43%  |
| 2      | 48        | 23.65%  |
| 3      | 8         | 3.94%   |
| 4      | 1         | 0.49%   |
| 0      | 1         | 0.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 161       | 80.5%   |
| Yes       | 39        | 19.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 130       | 65.66%  |
| No        | 68        | 34.34%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 191       | 96.46%  |
| No        | 7         | 3.54%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 169       | 84.5%   |
| No        | 31        | 15.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Singapore | 198       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Singapore            | 189       | 95.45%  |
| Jurong West          | 4         | 2.02%   |
| Yio Chu Kang         | 1         | 0.51%   |
| Sembawang Estate     | 1         | 0.51%   |
| Queenstown Estate    | 1         | 0.51%   |
| Kampong Ulu Jurong   | 1         | 0.51%   |
| Bukit Batok New Town | 1         | 0.51%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 48        | 69     | 18.97%  |
| WDC                         | 25        | 46     | 9.88%   |
| Seagate                     | 22        | 26     | 8.7%    |
| SanDisk                     | 20        | 26     | 7.91%   |
| SK hynix                    | 18        | 20     | 7.11%   |
| Toshiba                     | 17        | 24     | 6.72%   |
| Unknown                     | 13        | 16     | 5.14%   |
| Intel                       | 11        | 13     | 4.35%   |
| Micron Technology           | 10        | 11     | 3.95%   |
| HGST                        | 9         | 13     | 3.56%   |
| Hitachi                     | 6         | 6      | 2.37%   |
| Kingston                    | 5         | 6      | 1.98%   |
| Phison                      | 4         | 6      | 1.58%   |
| KIOXIA                      | 4         | 4      | 1.58%   |
| Apple                       | 4         | 4      | 1.58%   |
| China                       | 3         | 3      | 1.19%   |
| Transcend                   | 2         | 3      | 0.79%   |
| Patriot                     | 2         | 2      | 0.79%   |
| LITEON                      | 2         | 3      | 0.79%   |
| Lexar                       | 2         | 2      | 0.79%   |
| Lenovo                      | 2         | 2      | 0.79%   |
| JMicron Technology          | 2         | 3      | 0.79%   |
| Hewlett-Packard             | 2         | 3      | 0.79%   |
| External                    | 2         | 2      | 0.79%   |
| Crucial                     | 2         | 2      | 0.79%   |
| Yangtze Memory Technologies | 1         | 1      | 0.4%    |
| UMIS                        | 1         | 1      | 0.4%    |
| TO Exter                    | 1         | 1      | 0.4%    |
| Team                        | 1         | 1      | 0.4%    |
| SPCC                        | 1         | 1      | 0.4%    |
| Phison Electronics          | 1         | 1      | 0.4%    |
| OCZ                         | 1         | 1      | 0.4%    |
| INTEL SS                    | 1         | 2      | 0.4%    |
| Haizhide                    | 1         | 1      | 0.4%    |
| GALAX                       | 1         | 1      | 0.4%    |
| Fujitsu                     | 1         | 1      | 0.4%    |
| CT1000MX                    | 1         | 2      | 0.4%    |
| Corsair                     | 1         | 2      | 0.4%    |
| ADATA Technology            | 1         | 1      | 0.4%    |
| A-DATA Technology           | 1         | 1      | 0.4%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 6         | 2.3%    |
| Toshiba MQ04ABF100 1TB               | 4         | 1.53%   |
| Samsung NVMe SSD Drive 1024GB        | 4         | 1.53%   |
| HGST HTS721010A9E630 1TB             | 4         | 1.53%   |
| Unknown MMC Card  64GB               | 3         | 1.15%   |
| Toshiba MQ01ABD100 1TB               | 3         | 1.15%   |
| SK hynix SKHynix_HFS001TDE9X084N 1TB | 3         | 1.15%   |
| SanDisk NVMe SSD Drive 512GB         | 3         | 1.15%   |
| WDC WDS500G2X0C-00L350 500GB         | 2         | 0.77%   |
| WDC WDS100T2X0C-00L350 1TB           | 2         | 0.77%   |
| WDC WD7500BPVT-80HXZT3 752GB         | 2         | 0.77%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 2         | 0.77%   |
| WDC WD10SPZX-21Z10T0 1TB             | 2         | 0.77%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB   | 2         | 0.77%   |
| WDC PC SN720 SED SDAQNTW-1T00 1TB    | 2         | 0.77%   |
| Unknown MMC Card  32GB               | 2         | 0.77%   |
| Toshiba MK5055GSX 500GB              | 2         | 0.77%   |
| SK hynix HFM512GDJTNG-8310A 512GB    | 2         | 0.77%   |
| Seagate ST1000LM049-2GH172 1TB       | 2         | 0.77%   |
| Seagate Expansion 1TB                | 2         | 0.77%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB   | 2         | 0.77%   |
| SanDisk SSD PLUS 240GB               | 2         | 0.77%   |
| SanDisk SD6SN1M128G1002 128GB SSD    | 2         | 0.77%   |
| Samsung SSD 970 EVO Plus 500GB       | 2         | 0.77%   |
| Samsung SSD 860 EVO 500GB            | 2         | 0.77%   |
| Samsung SSD 860 EVO 250GB            | 2         | 0.77%   |
| Samsung SSD 850 EVO 500GB            | 2         | 0.77%   |
| Samsung SSD 840 EVO 250GB            | 2         | 0.77%   |
| Samsung NVMe SSD Drive 512GB         | 2         | 0.77%   |
| Samsung MZVLB1T0HBLR-000L7 1TB       | 2         | 0.77%   |
| Samsung MZALQ512HALU-000L2 512GB     | 2         | 0.77%   |
| Micron 2210_MTFDHBA512QFD 512GB      | 2         | 0.77%   |
| KIOXIA KBG40ZNS128G NVMe 128GB       | 2         | 0.77%   |
| JMicron Generic 200GB                | 2         | 0.77%   |
| Intel SSDPEKNU512GZ 512GB            | 2         | 0.77%   |
| Intel NVMe SSD Drive 512GB           | 2         | 0.77%   |
| Intel NVMe SSD Drive 1024GB          | 2         | 0.77%   |
| HGST HTS725050A7E630 500GB           | 2         | 0.77%   |
| HGST HTS545050A7E380 500GB           | 2         | 0.77%   |
| External USB3.0 320GB                | 2         | 0.77%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 25     | 32.31%  |
| Toshiba             | 13        | 20     | 20%     |
| WDC                 | 11        | 15     | 16.92%  |
| HGST                | 9         | 13     | 13.85%  |
| Hitachi             | 6         | 6      | 9.23%   |
| JMicron Technology  | 2         | 3      | 3.08%   |
| Samsung Electronics | 1         | 3      | 1.54%   |
| Fujitsu             | 1         | 1      | 1.54%   |
| Apple               | 1         | 1      | 1.54%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 25        | 38     | 35.71%  |
| SanDisk             | 12        | 17     | 17.14%  |
| Micron Technology   | 3         | 4      | 4.29%   |
| China               | 3         | 3      | 4.29%   |
| Apple               | 3         | 3      | 4.29%   |
| WDC                 | 2         | 3      | 2.86%   |
| Transcend           | 2         | 3      | 2.86%   |
| SK hynix            | 2         | 2      | 2.86%   |
| Patriot             | 2         | 2      | 2.86%   |
| LITEON              | 2         | 3      | 2.86%   |
| Kingston            | 2         | 3      | 2.86%   |
| Crucial             | 2         | 2      | 2.86%   |
| Toshiba             | 1         | 1      | 1.43%   |
| TO Exter            | 1         | 1      | 1.43%   |
| SPCC                | 1         | 1      | 1.43%   |
| OCZ                 | 1         | 1      | 1.43%   |
| Lexar               | 1         | 1      | 1.43%   |
| Hewlett-Packard     | 1         | 2      | 1.43%   |
| Haizhide            | 1         | 1      | 1.43%   |
| GALAX               | 1         | 1      | 1.43%   |
| CT1000MX            | 1         | 2      | 1.43%   |
| Unknown             | 1         | 1      | 1.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 98        | 138    | 41.35%  |
| SSD     | 66        | 95     | 27.85%  |
| HDD     | 62        | 87     | 26.16%  |
| MMC     | 10        | 13     | 4.22%   |
| Unknown | 1         | 1      | 0.42%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 107       | 171    | 47.14%  |
| NVMe | 98        | 134    | 43.17%  |
| SAS  | 12        | 16     | 5.29%   |
| MMC  | 10        | 13     | 4.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 81        | 118    | 64.8%   |
| 0.51-1.0   | 40        | 58     | 32%     |
| 1.01-2.0   | 4         | 6      | 3.2%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 59        | 27.7%   |
| 251-500        | 49        | 23%     |
| 501-1000       | 38        | 17.84%  |
| 51-100         | 16        | 7.51%   |
| 1-20           | 15        | 7.04%   |
| 1001-2000      | 14        | 6.57%   |
| 21-50          | 8         | 3.76%   |
| More than 3000 | 7         | 3.29%   |
| Unknown        | 5         | 2.35%   |
| 2001-3000      | 2         | 0.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 87        | 40.65%  |
| 21-50          | 38        | 17.76%  |
| 101-250        | 31        | 14.49%  |
| 51-100         | 20        | 9.35%   |
| 251-500        | 19        | 8.88%   |
| 501-1000       | 8         | 3.74%   |
| Unknown        | 5         | 2.34%   |
| 1001-2000      | 3         | 1.4%    |
| 2001-3000      | 2         | 0.93%   |
| More than 3000 | 1         | 0.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-22V0TT0 500GB       | 1         | 1      | 12.5%   |
| WDC WD5000BPVT-16HXZT1 500GB       | 1         | 1      | 12.5%   |
| WDC WD10SPZX-21Z10T0 1TB           | 1         | 2      | 12.5%   |
| Seagate ST2000LM003 HN-M201RAD 2TB | 1         | 1      | 12.5%   |
| Seagate ST1000LM024 HN-M 1TB       | 1         | 1      | 12.5%   |
| Hitachi HTS545032B9A300 320GB      | 1         | 1      | 12.5%   |
| Hitachi HTS541010A9E680 1TB        | 1         | 1      | 12.5%   |
| China SSD 128GB                    | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 4      | 37.5%   |
| Seagate | 2         | 2      | 25%     |
| Hitachi | 2         | 2      | 25%     |
| China   | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 4      | 42.86%  |
| Seagate | 2         | 2      | 28.57%  |
| Hitachi | 2         | 2      | 28.57%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 8      | 87.5%   |
| SSD  | 1         | 1      | 12.5%   |

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
| Detected | 119       | 188    | 55.87%  |
| Works    | 86        | 137    | 40.38%  |
| Malfunc  | 8         | 9      | 3.76%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 126       | 51.85%  |
| Samsung Electronics          | 25        | 10.29%  |
| SanDisk                      | 20        | 8.23%   |
| AMD                          | 19        | 7.82%   |
| SK hynix                     | 16        | 6.58%   |
| Micron Technology            | 7         | 2.88%   |
| Phison Electronics           | 5         | 2.06%   |
| KIOXIA                       | 5         | 2.06%   |
| Toshiba America Info Systems | 3         | 1.23%   |
| Nvidia                       | 3         | 1.23%   |
| Kingston Technology Company  | 3         | 1.23%   |
| ADATA Technology             | 3         | 1.23%   |
| Shenzhen Longsys Electronics | 2         | 0.82%   |
| Lenovo                       | 2         | 0.82%   |
| Yangtze Memory Technologies  | 1         | 0.41%   |
| Union Memory (Shenzhen)      | 1         | 0.41%   |
| Silicon Motion               | 1         | 0.41%   |
| Seagate Technology           | 1         | 0.41%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 18        | 7.11%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 15        | 5.93%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 15        | 5.93%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 13        | 5.14%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 11        | 4.35%   |
| Intel Volume Management Device NVMe RAID Controller                            | 10        | 3.95%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 10        | 3.95%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 8         | 3.16%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 7         | 2.77%   |
| Micron Non-Volatile memory controller                                          | 7         | 2.77%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 7         | 2.77%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 6         | 2.37%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 6         | 2.37%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 6         | 2.37%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 5         | 1.98%   |
| Samsung NVMe SSD Controller 980                                                | 5         | 1.98%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 5         | 1.98%   |
| Intel SSD 660P Series                                                          | 5         | 1.98%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 1.58%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 1.58%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 1.58%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 3         | 1.19%   |
| SK hynix Non-Volatile memory controller                                        | 3         | 1.19%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 3         | 1.19%   |
| Phison E12 NVMe Controller                                                     | 3         | 1.19%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.19%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 1.19%   |
| Intel Non-Volatile memory controller                                           | 3         | 1.19%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 1.19%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 1.19%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 1.19%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 1.19%   |
| SK hynix Platinum P41 NVMe Solid State Drive 2TB                               | 2         | 0.79%   |
| SanDisk Non-Volatile memory controller                                         | 2         | 0.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 0.79%   |
| Samsung Electronics SATA controller                                            | 2         | 0.79%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 2         | 0.79%   |
| Lenovo Non-Volatile memory controller                                          | 2         | 0.79%   |
| Kingston Company Company Non-Volatile memory controller                        | 2         | 0.79%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 2         | 0.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 118       | 47.97%  |
| NVMe | 99        | 40.24%  |
| RAID | 21        | 8.54%   |
| IDE  | 8         | 3.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 163       | 82.32%  |
| AMD    | 35        | 17.68%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 4.55%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 7         | 3.54%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 7         | 3.54%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 3.03%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 2.53%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 2.53%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 5         | 2.53%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 5         | 2.53%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 2.02%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 2.02%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 2.02%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 1.52%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 1.52%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 1.52%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.52%   |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 2         | 1.01%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 2         | 1.01%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.01%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.01%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 1.01%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 1.01%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 1.01%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 1.01%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 1.01%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 1.01%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 1.01%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 2         | 1.01%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 1.01%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 2         | 1.01%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz          | 2         | 1.01%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 1.01%   |
| Intel Atom x5-Z8500 CPU @ 1.44GHz             | 2         | 1.01%   |
| Intel 12th Gen Core i7-12700H                 | 2         | 1.01%   |
| Intel 12th Gen Core i7-12650H                 | 2         | 1.01%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 1.01%   |
| Intel 11th Gen Core i7-11390H @ 3.40GHz       | 2         | 1.01%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 1.01%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 1.01%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 1.01%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 2         | 1.01%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 62        | 31.31%  |
| Intel Core i5           | 40        | 20.2%   |
| Other                   | 22        | 11.11%  |
| AMD Ryzen 7             | 12        | 6.06%   |
| AMD Ryzen 5             | 10        | 5.05%   |
| Intel Core 2 Duo        | 9         | 4.55%   |
| Intel Celeron           | 8         | 4.04%   |
| Intel Core i3           | 5         | 2.53%   |
| Intel Pentium Silver    | 4         | 2.02%   |
| Intel Atom              | 4         | 2.02%   |
| Intel Xeon              | 3         | 1.52%   |
| AMD Ryzen 7 PRO         | 3         | 1.52%   |
| Intel Core m3           | 2         | 1.01%   |
| Intel Core i9           | 2         | 1.01%   |
| AMD Ryzen 9             | 2         | 1.01%   |
| AMD Ryzen 3             | 2         | 1.01%   |
| Intel Pentium Dual      | 1         | 0.51%   |
| Intel Core 2            | 1         | 0.51%   |
| AMD Turion 64 X2 Mobile | 1         | 0.51%   |
| AMD Ryzen 5 PRO         | 1         | 0.51%   |
| AMD PRO A10             | 1         | 0.51%   |
| AMD E1                  | 1         | 0.51%   |
| AMD E                   | 1         | 0.51%   |
| AMD A6                  | 1         | 0.51%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 79        | 39.9%   |
| 2      | 71        | 35.86%  |
| 8      | 24        | 12.12%  |
| 6      | 17        | 8.59%   |
| 10     | 3         | 1.52%   |
| 14     | 2         | 1.01%   |
| 1      | 2         | 1.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 198       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 163       | 81.5%   |
| 1      | 37        | 18.5%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 195       | 98.48%  |
| 32-bit         | 2         | 1.01%   |
| Unknown        | 1         | 0.51%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 36        | 17.65%  |
| 0x806ea    | 13        | 6.37%   |
| 0x806ec    | 12        | 5.88%   |
| 0x206a7    | 12        | 5.88%   |
| 0x306a9    | 11        | 5.39%   |
| 0x906ea    | 10        | 4.9%    |
| 0x0a50000c | 9         | 4.41%   |
| 0x806c1    | 7         | 3.43%   |
| 0x40651    | 7         | 3.43%   |
| 0x806eb    | 5         | 2.45%   |
| 0x806e9    | 5         | 2.45%   |
| 0x306d4    | 5         | 2.45%   |
| 0x806d1    | 4         | 1.96%   |
| 0x6fd      | 4         | 1.96%   |
| 0x506e3    | 4         | 1.96%   |
| 0x406e3    | 4         | 1.96%   |
| 0x1067a    | 4         | 1.96%   |
| 0x08108109 | 4         | 1.96%   |
| 0xa0652    | 3         | 1.47%   |
| 0x806c2    | 3         | 1.47%   |
| 0x306c3    | 3         | 1.47%   |
| 0x20655    | 3         | 1.47%   |
| 0x08600106 | 3         | 1.47%   |
| 0x906e9    | 2         | 0.98%   |
| 0x906c0    | 2         | 0.98%   |
| 0x906a3    | 2         | 0.98%   |
| 0x706a8    | 2         | 0.98%   |
| 0x706a1    | 2         | 0.98%   |
| 0x406c3    | 2         | 0.98%   |
| 0x40661    | 2         | 0.98%   |
| 0x30678    | 2         | 0.98%   |
| 0x106c2    | 2         | 0.98%   |
| 0x08600103 | 2         | 0.98%   |
| 0x08108102 | 2         | 0.98%   |
| 0x906ed    | 1         | 0.49%   |
| 0x706e5    | 1         | 0.49%   |
| 0x6f6      | 1         | 0.49%   |
| 0x506c9    | 1         | 0.49%   |
| 0x10676    | 1         | 0.49%   |
| 0x0a404102 | 1         | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 55        | 27.78%  |
| SandyBridge      | 14        | 7.07%   |
| TigerLake        | 13        | 6.57%   |
| Haswell          | 13        | 6.57%   |
| Zen 3            | 11        | 5.56%   |
| IvyBridge        | 11        | 5.56%   |
| Skylake          | 9         | 4.55%   |
| Zen+             | 8         | 4.04%   |
| Unknown          | 8         | 4.04%   |
| Zen 2            | 7         | 3.54%   |
| Penryn           | 6         | 3.03%   |
| IceLake          | 6         | 3.03%   |
| Silvermont       | 5         | 2.53%   |
| Core             | 5         | 2.53%   |
| Broadwell        | 5         | 2.53%   |
| Goldmont plus    | 4         | 2.02%   |
| CometLake        | 4         | 2.02%   |
| Westmere         | 3         | 1.52%   |
| Tremont          | 2         | 1.01%   |
| Excavator        | 2         | 1.01%   |
| Bonnell          | 2         | 1.01%   |
| K8 Hammer        | 1         | 0.51%   |
| Jaguar           | 1         | 0.51%   |
| Goldmont         | 1         | 0.51%   |
| Bobcat           | 1         | 0.51%   |
| Alderlake Hybrid | 1         | 0.51%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 152       | 56.51%  |
| Nvidia | 78        | 29%     |
| AMD    | 39        | 14.5%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                    | 16        | 5.78%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 13        | 4.69%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 12        | 4.33%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 11        | 3.97%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 10        | 3.61%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 10        | 3.61%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 8         | 2.89%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 8         | 2.89%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 7         | 2.53%   |
| AMD Renoir                                                                | 7         | 2.53%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 7         | 2.53%   |
| Intel HD Graphics 620                                                     | 6         | 2.17%   |
| Nvidia GP108M [GeForce MX150]                                             | 5         | 1.81%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                           | 5         | 1.81%   |
| Nvidia GP108BM [GeForce MX250]                                            | 4         | 1.44%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 4         | 1.44%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 4         | 1.44%   |
| Intel HD Graphics 5500                                                    | 4         | 1.44%   |
| Intel HD Graphics 530                                                     | 4         | 1.44%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 4         | 1.44%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 3         | 1.08%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 3         | 1.08%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                   | 3         | 1.08%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 3         | 1.08%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 3         | 1.08%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 3         | 1.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 3         | 1.08%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 3         | 1.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 3         | 1.08%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 3         | 1.08%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 2         | 0.72%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 2         | 0.72%   |
| Nvidia TU104M [GeForce RTX 2080 Mobile]                                   | 2         | 0.72%   |
| Nvidia MCP89 [GeForce 320M]                                               | 2         | 0.72%   |
| Nvidia GP108M [GeForce MX250]                                             | 2         | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 2         | 0.72%   |
| Nvidia GM108M [GeForce 940M]                                              | 2         | 0.72%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                         | 2         | 0.72%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 2         | 0.72%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 2         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 88        | 44.22%  |
| Intel + Nvidia | 56        | 28.14%  |
| 1 x AMD        | 22        | 11.06%  |
| 1 x Nvidia     | 16        | 8.04%   |
| Intel + AMD    | 8         | 4.02%   |
| AMD + Nvidia   | 7         | 3.52%   |
| 2 x AMD        | 2         | 1.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 156       | 76.85%  |
| Proprietary | 42        | 20.69%  |
| Unknown     | 5         | 2.46%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 137       | 65.55%  |
| 1.01-2.0   | 30        | 14.35%  |
| 0.01-0.5   | 16        | 7.66%   |
| 3.01-4.0   | 13        | 6.22%   |
| 7.01-8.0   | 4         | 1.91%   |
| 0.51-1.0   | 4         | 1.91%   |
| 5.01-6.0   | 3         | 1.44%   |
| 2.01-3.0   | 1         | 0.48%   |
| 8.01-16.0  | 1         | 0.48%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 64        | 28.57%  |
| BOE                     | 28        | 12.5%   |
| LG Display              | 27        | 12.05%  |
| Samsung Electronics     | 23        | 10.27%  |
| Chimei Innolux          | 18        | 8.04%   |
| Dell                    | 13        | 5.8%    |
| Apple                   | 7         | 3.13%   |
| Sharp                   | 6         | 2.68%   |
| Philips                 | 5         | 2.23%   |
| Goldstar                | 4         | 1.79%   |
| CSO                     | 4         | 1.79%   |
| Acer                    | 4         | 1.79%   |
| Lenovo                  | 3         | 1.34%   |
| InfoVision              | 3         | 1.34%   |
| PANDA                   | 2         | 0.89%   |
| LG Philips              | 2         | 0.89%   |
| Toshiba                 | 1         | 0.45%   |
| Tianma XM               | 1         | 0.45%   |
| Sony                    | 1         | 0.45%   |
| Mi                      | 1         | 0.45%   |
| JDI                     | 1         | 0.45%   |
| Hewlett-Packard         | 1         | 0.45%   |
| EXP                     | 1         | 0.45%   |
| CVT                     | 1         | 0.45%   |
| CPT                     | 1         | 0.45%   |
| Chi Mei Optoelectronics | 1         | 0.45%   |
| ASUSTek Computer        | 1         | 0.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 4         | 1.79%   |
| Dell P2421D DELD0FF 2560x1440 527x296mm 23.8-inch                     | 3         | 1.34%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 3         | 1.34%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch  | 2         | 0.89%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 2         | 0.89%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2         | 0.89%   |
| LG Philips LCD Monitor LPL8D00 1280x800 304x190mm 14.1-inch           | 2         | 0.89%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch          | 2         | 0.89%   |
| Goldstar ULTRAGEAR GSM5B7F 2560x1440 597x336mm 27.0-inch              | 2         | 0.89%   |
| Dell S2340L DELD058 1920x1080 509x286mm 23.0-inch                     | 2         | 0.89%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 2         | 0.89%   |
| Chimei Innolux LCD Monitor CMN1354 1920x1080 293x165mm 13.2-inch      | 2         | 0.89%   |
| BOE LCD Monitor BOE09C3 1366x768 256x144mm 11.6-inch                  | 2         | 0.89%   |
| BOE LCD Monitor BOE06A7 1920x1080 294x165mm 13.3-inch                 | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO408D 1920x1080 309x174mm 14.0-inch        | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO3892 1920x1080 344x194mm 15.5-inch        | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO31EB 3840x2160 344x193mm 15.5-inch        | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch        | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch         | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO2B99 1920x1080 293x165mm 13.2-inch        | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO205C 1366x768 256x144mm 11.6-inch         | 2         | 0.89%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 2         | 0.89%   |
| Toshiba LCD TV LCD0030 1920x1080 708x398mm 32.0-inch                  | 1         | 0.45%   |
| Tianma XM LCD Monitor TLX1388 3000x2000 293x196mm 13.9-inch           | 1         | 0.45%   |
| Sony BW8 MS_9001 1600x2560 113x181mm 8.4-inch                         | 1         | 0.45%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch               | 1         | 0.45%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 1         | 0.45%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.45%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch               | 1         | 0.45%   |
| Sharp LCD Monitor SHP1485 1920x1080 294x165mm 13.3-inch               | 1         | 0.45%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.45%   |
| Samsung Electronics U32R59x SAM0F94 3840x2160 697x392mm 31.5-inch     | 1         | 0.45%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch     | 1         | 0.45%   |
| Samsung Electronics S24R35xFZ SAM71A8 1920x1080 527x296mm 23.8-inch   | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC554E 1024x600 223x125mm 10.1-inch  | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch  | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC4457 1440x900 303x190mm 14.1-inch  | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch  | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC3052 1366x768 256x144mm 11.6-inch  | 1         | 0.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 110       | 53.14%  |
| 1366x768 (WXGA)   | 39        | 18.84%  |
| 3840x2160 (4K)    | 10        | 4.83%   |
| 1280x800 (WXGA)   | 9         | 4.35%   |
| 2560x1440 (QHD)   | 8         | 3.86%   |
| 2560x1600         | 6         | 2.9%    |
| 1920x1200 (WUXGA) | 6         | 2.9%    |
| 3440x1440         | 3         | 1.45%   |
| 2880x1800         | 3         | 1.45%   |
| 3000x2000         | 2         | 0.97%   |
| 2240x1400         | 2         | 0.97%   |
| 1440x900 (WXGA+)  | 2         | 0.97%   |
| 1360x768          | 2         | 0.97%   |
| 3840x2400         | 1         | 0.48%   |
| 3200x1800 (QHD+)  | 1         | 0.48%   |
| 1600x900 (HD+)    | 1         | 0.48%   |
| 1280x1024 (SXGA)  | 1         | 0.48%   |
| 1024x600          | 1         | 0.48%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 65        | 29.15%  |
| 13      | 53        | 23.77%  |
| 14      | 41        | 18.39%  |
| 23      | 10        | 4.48%   |
| 12      | 9         | 4.04%   |
| 27      | 8         | 3.59%   |
| 11      | 7         | 3.14%   |
| 24      | 5         | 2.24%   |
| 21      | 5         | 2.24%   |
| 16      | 4         | 1.79%   |
| 34      | 2         | 0.9%    |
| 32      | 2         | 0.9%    |
| 19      | 2         | 0.9%    |
| 18      | 2         | 0.9%    |
| 52      | 1         | 0.45%   |
| 40      | 1         | 0.45%   |
| 35      | 1         | 0.45%   |
| 31      | 1         | 0.45%   |
| 17      | 1         | 0.45%   |
| 10      | 1         | 0.45%   |
| 8       | 1         | 0.45%   |
| Unknown | 1         | 0.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 131       | 58.74%  |
| 201-300     | 46        | 20.63%  |
| 501-600     | 23        | 10.31%  |
| 401-500     | 8         | 3.59%   |
| 351-400     | 5         | 2.24%   |
| 701-800     | 4         | 1.79%   |
| 801-900     | 2         | 0.9%    |
| 601-700     | 1         | 0.45%   |
| 101-200     | 1         | 0.45%   |
| 1001-1500   | 1         | 0.45%   |
| Unknown     | 1         | 0.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 158       | 81.44%  |
| 16/10 | 28        | 14.43%  |
| 3/2   | 3         | 1.55%   |
| 21/9  | 3         | 1.55%   |
| 5/4   | 1         | 0.52%   |
| 0.62  | 1         | 0.52%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 70        | 31.39%  |
| 101-110        | 65        | 29.15%  |
| 71-80          | 23        | 10.31%  |
| 201-250        | 18        | 8.07%   |
| 61-70          | 9         | 4.04%   |
| 301-350        | 8         | 3.59%   |
| 51-60          | 7         | 3.14%   |
| 351-500        | 6         | 2.69%   |
| 151-200        | 4         | 1.79%   |
| 111-120        | 4         | 1.79%   |
| 141-150        | 2         | 0.9%    |
| More than 1000 | 1         | 0.45%   |
| 41-50          | 1         | 0.45%   |
| 1-40           | 1         | 0.45%   |
| 121-130        | 1         | 0.45%   |
| 501-1000       | 1         | 0.45%   |
| 91-100         | 1         | 0.45%   |
| Unknown        | 1         | 0.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 100       | 46.51%  |
| 101-120       | 40        | 18.6%   |
| 161-240       | 36        | 16.74%  |
| 51-100        | 25        | 11.63%  |
| More than 240 | 11        | 5.12%   |
| 1-50          | 2         | 0.93%   |
| Unknown       | 1         | 0.47%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 160       | 77.67%  |
| 2     | 37        | 17.96%  |
| 0     | 8         | 3.88%   |
| 3     | 1         | 0.49%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 121       | 42.31%  |
| Realtek Semiconductor    | 74        | 25.87%  |
| Qualcomm Atheros         | 41        | 14.34%  |
| Broadcom                 | 17        | 5.94%   |
| MediaTek                 | 7         | 2.45%   |
| ASIX Electronics         | 7         | 2.45%   |
| Broadcom Limited         | 3         | 1.05%   |
| Qualcomm                 | 2         | 0.7%    |
| Marvell Technology Group | 2         | 0.7%    |
| Sierra Wireless          | 1         | 0.35%   |
| Samsung Electronics      | 1         | 0.35%   |
| Ralink Technology        | 1         | 0.35%   |
| Ralink                   | 1         | 0.35%   |
| Nvidia                   | 1         | 0.35%   |
| MosChip Semiconductor    | 1         | 0.35%   |
| Lenovo                   | 1         | 0.35%   |
| Hewlett-Packard          | 1         | 0.35%   |
| Google                   | 1         | 0.35%   |
| Dell                     | 1         | 0.35%   |
| D-Link                   | 1         | 0.35%   |
| Apple                    | 1         | 0.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 44        | 12.98%  |
| Intel Wi-Fi 6 AX200                                                     | 14        | 4.13%   |
| Intel Wireless 7265                                                     | 12        | 3.54%   |
| Intel Wi-Fi 6 AX201                                                     | 12        | 3.54%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 10        | 2.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 10        | 2.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 2.65%   |
| Intel Wireless 8265 / 8275                                              | 9         | 2.65%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 2.36%   |
| Intel Wireless 7260                                                     | 7         | 2.06%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 2.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 7         | 2.06%   |
| ASIX AX88179 Gigabit Ethernet                                           | 7         | 2.06%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 1.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 1.77%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 1.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 5         | 1.47%   |
| Intel Wireless 3165                                                     | 5         | 1.47%   |
| Intel Ethernet Connection (4) I219-LM                                   | 5         | 1.47%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 5         | 1.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 1.18%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.18%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 1.18%   |
| Intel Wireless-AC 9260                                                  | 3         | 0.88%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 0.88%   |
| Intel Ethernet Connection I218-LM                                       | 3         | 0.88%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 0.88%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 3         | 0.88%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 3         | 0.88%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 0.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.59%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.59%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 0.59%   |
| Realtek Killer E3000 2.5GbE Controller                                  | 2         | 0.59%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 2         | 0.59%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 2         | 0.59%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.59%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.59%   |
| Intel Wireless 8260                                                     | 2         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 119       | 60.1%   |
| Qualcomm Atheros      | 36        | 18.18%  |
| Realtek Semiconductor | 17        | 8.59%   |
| Broadcom              | 12        | 6.06%   |
| MediaTek              | 4         | 2.02%   |
| Qualcomm              | 2         | 1.01%   |
| Broadcom Limited      | 2         | 1.01%   |
| Sierra Wireless       | 1         | 0.51%   |
| Ralink Technology     | 1         | 0.51%   |
| Ralink                | 1         | 0.51%   |
| Hewlett-Packard       | 1         | 0.51%   |
| Dell                  | 1         | 0.51%   |
| D-Link                | 1         | 0.51%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 14        | 7.04%   |
| Intel Wireless 7265                                                     | 12        | 6.03%   |
| Intel Wi-Fi 6 AX201                                                     | 12        | 6.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 10        | 5.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 4.52%   |
| Intel Wireless 8265 / 8275                                              | 9         | 4.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 4.02%   |
| Intel Wireless 7260                                                     | 7         | 3.52%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 3.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 3.02%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 3.02%   |
| Intel Wireless 3165                                                     | 5         | 2.51%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 5         | 2.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 2.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 2.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 2.01%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 2.01%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 1.51%   |
| Intel Wireless-AC 9260                                                  | 3         | 1.51%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 1.51%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.51%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 3         | 1.51%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 1.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.01%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.01%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 1.01%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1.01%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.01%   |
| Intel Wireless 8260                                                     | 2         | 1.01%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 2         | 1.01%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 1.01%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 1.01%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 1.01%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 1.01%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 2         | 1.01%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 2         | 1.01%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 1.01%   |
| Broadcom BCM4311 802.11a/b/g                                            | 2         | 1.01%   |
| Sierra Wireless EM7455                                                  | 1         | 0.5%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 63        | 45.32%  |
| Intel                    | 38        | 27.34%  |
| Qualcomm Atheros         | 10        | 7.19%   |
| Broadcom                 | 9         | 6.47%   |
| ASIX Electronics         | 7         | 5.04%   |
| MediaTek                 | 3         | 2.16%   |
| Marvell Technology Group | 2         | 1.44%   |
| Samsung Electronics      | 1         | 0.72%   |
| Nvidia                   | 1         | 0.72%   |
| MosChip Semiconductor    | 1         | 0.72%   |
| Lenovo                   | 1         | 0.72%   |
| Google                   | 1         | 0.72%   |
| Broadcom Limited         | 1         | 0.72%   |
| Apple                    | 1         | 0.72%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 44        | 31.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 10        | 7.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7         | 5%      |
| ASIX AX88179 Gigabit Ethernet                                                  | 7         | 5%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 3.57%   |
| Intel Ethernet Connection (4) I219-LM                                          | 5         | 3.57%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                  | 3         | 2.14%   |
| Intel Ethernet Connection I218-LM                                              | 3         | 2.14%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 3         | 2.14%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 2         | 1.43%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 1.43%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 1.43%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.43%   |
| Intel Ethernet Connection (7) I219-LM                                          | 2         | 1.43%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 1.43%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 1.43%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 1.43%   |
| Intel Ethernet Connection (14) I219-LM                                         | 2         | 1.43%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 1.43%   |
| Intel 82579V Gigabit Network Connection                                        | 2         | 1.43%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 1.43%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 2         | 1.43%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.71%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.71%   |
| Realtek Realtek Ethernet controller                                            | 1         | 0.71%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.71%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.71%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.71%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.71%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.71%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.71%   |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 0.71%   |
| MosChip MCS7830 10/100 Mbps Ethernet adapter                                   | 1         | 0.71%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.71%   |
| Marvell Group 88E8038 PCI-E Fast Ethernet Controller                           | 1         | 0.71%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.71%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.71%   |
| Intel Ethernet Connection (7) I219-V                                           | 1         | 0.71%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 0.71%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 191       | 59.5%   |
| Ethernet | 130       | 40.5%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 171       | 80.66%  |
| Ethernet | 41        | 19.34%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 114       | 57.29%  |
| 1     | 83        | 41.71%  |
| 3     | 1         | 0.5%    |
| 0     | 1         | 0.5%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 180       | 90.91%  |
| Yes  | 18        | 9.09%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 98        | 57.65%  |
| IMC Networks                    | 13        | 7.65%   |
| Qualcomm Atheros Communications | 12        | 7.06%   |
| Foxconn / Hon Hai               | 11        | 6.47%   |
| Lite-On Technology              | 8         | 4.71%   |
| Broadcom                        | 8         | 4.71%   |
| Apple                           | 6         | 3.53%   |
| Realtek Semiconductor           | 4         | 2.35%   |
| Cambridge Silicon Radio         | 2         | 1.18%   |
| USI                             | 1         | 0.59%   |
| Toshiba                         | 1         | 0.59%   |
| Ralink Technology               | 1         | 0.59%   |
| MediaTek                        | 1         | 0.59%   |
| Foxconn International           | 1         | 0.59%   |
| Chicony Electronics             | 1         | 0.59%   |
| Askey Computer                  | 1         | 0.59%   |
| Alps Electric                   | 1         | 0.59%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 33        | 19.41%  |
| Intel AX201 Bluetooth                               | 27        | 15.88%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 19        | 11.18%  |
| Intel AX200 Bluetooth                               | 12        | 7.06%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 5         | 2.94%   |
| IMC Networks Bluetooth Radio                        | 5         | 2.94%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 2.35%   |
| IMC Networks Bluetooth Device                       | 4         | 2.35%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 2.35%   |
| Apple Bluetooth Host Controller                     | 4         | 2.35%   |
| Realtek Bluetooth Radio                             | 3         | 1.76%   |
| IMC Networks Wireless_Device                        | 3         | 1.76%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 1.76%   |
| Foxconn / Hon Hai BCM20702A0                        | 3         | 1.76%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 1.76%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 1.18%   |
| Lite-On Bluetooth Radio                             | 2         | 1.18%   |
| Lite-On Bluetooth Device                            | 2         | 1.18%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 1.18%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.18%   |
| Intel Bluetooth Device                              | 2         | 1.18%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 1.18%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.18%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 1.18%   |
| Apple Bluetooth USB Host Controller                 | 2         | 1.18%   |
| USI Bluetooth Device                                | 1         | 0.59%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.59%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.59%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.59%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.59%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.59%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.59%   |
| MediaTek Wireless_Device                            | 1         | 0.59%   |
| Lite-On Atheros Bluetooth                           | 1         | 0.59%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.59%   |
| Intel AX210 Bluetooth                               | 1         | 0.59%   |
| IMC Networks Bluetooth module                       | 1         | 0.59%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.59%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 0.59%   |
| Chicony Bluetooth (RTL8723BE)                       | 1         | 0.59%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 158       | 64.75%  |
| Nvidia              | 36        | 14.75%  |
| AMD                 | 35        | 14.34%  |
| Plantronics         | 2         | 0.82%   |
| Lenovo              | 2         | 0.82%   |
| Kingston Technology | 2         | 0.82%   |
| Apple               | 2         | 0.82%   |
| Razer USA           | 1         | 0.41%   |
| Logitech            | 1         | 0.41%   |
| JBL                 | 1         | 0.41%   |
| GN Netcom           | 1         | 0.41%   |
| Cooler Master       | 1         | 0.41%   |
| Conexant Systems    | 1         | 0.41%   |
| ASUSTek Computer    | 1         | 0.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 30        | 10.34%  |
| Intel Sunrise Point-LP HD Audio                                            | 27        | 9.31%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 15        | 5.17%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 13        | 4.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 13        | 4.48%   |
| Intel Cannon Lake PCH cAVS                                                 | 12        | 4.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 12        | 4.14%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 9         | 3.1%    |
| Intel Comet Lake PCH-LP cAVS                                               | 8         | 2.76%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8         | 2.76%   |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 2.41%   |
| Intel 8 Series HD Audio Controller                                         | 7         | 2.41%   |
| Nvidia GA104 High Definition Audio Controller                              | 6         | 2.07%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 2.07%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 1.72%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 1.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 1.72%   |
| Nvidia TU104 HD Audio Controller                                           | 4         | 1.38%   |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 1.38%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 1.38%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 1.38%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 1.38%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 4         | 1.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 1.38%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 4         | 1.38%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.03%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 1.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 1.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 1.03%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 1.03%   |
| Plantronics Blackwire 3225 Series                                          | 2         | 0.69%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 0.69%   |
| Nvidia MCP89 High Definition Audio                                         | 2         | 0.69%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.69%   |
| Kingston Technology HyperX 7.1 Audio                                       | 2         | 0.69%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 0.69%   |
| Intel Jasper Lake HD Audio                                                 | 2         | 0.69%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 0.69%   |
| Intel CM238 HD Audio Controller                                            | 2         | 0.69%   |
| Apple USB-C to 3.5mm Headphone Jack Adapter                                | 2         | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 40        | 28.17%  |
| Samsung Electronics | 37        | 26.06%  |
| Micron Technology   | 20        | 14.08%  |
| Kingston            | 11        | 7.75%   |
| Unknown             | 8         | 5.63%   |
| Crucial             | 7         | 4.93%   |
| Transcend           | 3         | 2.11%   |
| Ramaxel Technology  | 3         | 2.11%   |
| A-DATA Technology   | 3         | 2.11%   |
| Elpida              | 2         | 1.41%   |
| V-GeN               | 1         | 0.7%    |
| Unknown (ABCD)      | 1         | 0.7%    |
| Team                | 1         | 0.7%    |
| Patriot             | 1         | 0.7%    |
| Nanya Technology    | 1         | 0.7%    |
| Lexar               | 1         | 0.7%    |
| Corsair             | 1         | 0.7%    |
| ASint Technology    | 1         | 0.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 2.01%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 3         | 2.01%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 2.01%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 2.01%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s              | 2         | 1.34%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 2         | 1.34%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 1.34%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 1.34%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.34%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 1.34%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 1.34%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 1.34%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 1GB Row Of Chips LPDDR4 4267MT/s   | 2         | 1.34%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 2         | 1.34%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 1.34%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.34%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s             | 2         | 1.34%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 1.34%   |
| Crucial RAM CT32G4SFD832A.C16FE 32GB SODIMM DDR4 3200MT/s        | 2         | 1.34%   |
| V-GeN RAM D3R4GS16B8R 4GB SODIMM DDR3 1600MT/s                   | 1         | 0.67%   |
| Unknown RAM Module 8GB SODIMM DDR3 800MT/s                       | 1         | 0.67%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.67%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.67%   |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s                 | 1         | 0.67%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 1         | 0.67%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 0.67%   |
| Unknown RAM Module 1GB SODIMM DDR3 1600MT/s                      | 1         | 0.67%   |
| Unknown RAM Module 16GB Row Of Chips LPDDR4 4267MT/s             | 1         | 0.67%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.67%   |
| Transcend RAM TS1GSK64V3H 8192MB SODIMM DDR3 1333MT/s            | 1         | 0.67%   |
| Transcend RAM JM3200HSB-16G 16GB SODIMM DDR4 3200MT/s            | 1         | 0.67%   |
| Transcend RAM JM1333KSN-2G 2GB SODIMM DDR3 1333MT/s              | 1         | 0.67%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 1         | 0.67%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 0.67%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.67%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.67%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.67%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.67%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.67%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 61        | 53.04%  |
| DDR3   | 32        | 27.83%  |
| LPDDR3 | 10        | 8.7%    |
| LPDDR4 | 9         | 7.83%   |
| SDRAM  | 1         | 0.87%   |
| LPDDR5 | 1         | 0.87%   |
| DDR5   | 1         | 0.87%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 92        | 80%     |
| Row Of Chips | 20        | 17.39%  |
| Chip         | 2         | 1.74%   |
| Unknown      | 1         | 0.87%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 54        | 40%     |
| 4096  | 39        | 28.89%  |
| 16384 | 25        | 18.52%  |
| 2048  | 8         | 5.93%   |
| 32768 | 7         | 5.19%   |
| 1024  | 2         | 1.48%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 29        | 22.83%  |
| 1600    | 26        | 20.47%  |
| 2667    | 23        | 18.11%  |
| 2400    | 10        | 7.87%   |
| 4267    | 7         | 5.51%   |
| 2133    | 7         | 5.51%   |
| 1334    | 5         | 3.94%   |
| 1333    | 5         | 3.94%   |
| 1867    | 3         | 2.36%   |
| 4800    | 2         | 1.57%   |
| 3266    | 2         | 1.57%   |
| 1067    | 2         | 1.57%   |
| 8400    | 1         | 0.79%   |
| 6400    | 1         | 0.79%   |
| 4199    | 1         | 0.79%   |
| 1200    | 1         | 0.79%   |
| 800     | 1         | 0.79%   |
| Unknown | 1         | 0.79%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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
| Chicony Electronics                    | 47        | 26.55%  |
| IMC Networks                           | 28        | 15.82%  |
| Microdia                               | 21        | 11.86%  |
| Realtek Semiconductor                  | 16        | 9.04%   |
| Sunplus Innovation Technology          | 13        | 7.34%   |
| Acer                                   | 10        | 5.65%   |
| Suyin                                  | 6         | 3.39%   |
| Samsung Electronics                    | 5         | 2.82%   |
| Syntek                                 | 4         | 2.26%   |
| Apple                                  | 4         | 2.26%   |
| Logitech                               | 3         | 1.69%   |
| Lite-On Technology                     | 3         | 1.69%   |
| Silicon Motion                         | 2         | 1.13%   |
| Ricoh                                  | 2         | 1.13%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.13%   |
| SunplusIT                              | 1         | 0.56%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.56%   |
| Sonix Technology                       | 1         | 0.56%   |
| Quanta                                 | 1         | 0.56%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.56%   |
| OmniVision Technologies                | 1         | 0.56%   |
| Magic Control Technology               | 1         | 0.56%   |
| Luxvisions Innotech Limited            | 1         | 0.56%   |
| Lenovo                                 | 1         | 0.56%   |
| Intel                                  | 1         | 0.56%   |
| Alcor Micro                            | 1         | 0.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                    | 14        | 7.91%   |
| Chicony Integrated Camera                        | 9         | 5.08%   |
| Chicony HD WebCam                                | 9         | 5.08%   |
| IMC Networks USB2.0 HD UVC WebCam                | 8         | 4.52%   |
| IMC Networks Integrated Camera                   | 8         | 4.52%   |
| Realtek Integrated_Webcam_HD                     | 7         | 3.95%   |
| Sunplus Integrated_Webcam_HD                     | 6         | 3.39%   |
| Samsung Galaxy A5 (MTP)                          | 5         | 2.82%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 5         | 2.82%   |
| IMC Networks USB2.0 HD IR UVC WebCam             | 4         | 2.26%   |
| Chicony HP HD Camera                             | 4         | 2.26%   |
| Acer Integrated Camera                           | 4         | 2.26%   |
| Syntek Integrated Camera                         | 3         | 1.69%   |
| Chicony Lenovo Integrated Camera (0.3MP)         | 3         | 1.69%   |
| Chicony HP Wide Vision HD Camera                 | 3         | 1.69%   |
| Apple FaceTime HD Camera                         | 3         | 1.69%   |
| Realtek Integrated Webcam_HD                     | 2         | 1.13%   |
| Realtek Asus 2.0 USB Webcam                      | 2         | 1.13%   |
| Microdia USB 2.0 Camera                          | 2         | 1.13%   |
| Microdia Sonix USB 2.0 Camera                    | 2         | 1.13%   |
| Lite-On Integrated Camera                        | 2         | 1.13%   |
| IMC Networks Lenovo EasyCamera                   | 2         | 1.13%   |
| Chicony VGA Webcam                               | 2         | 1.13%   |
| Chicony USB2.0 HD UVC WebCam                     | 2         | 1.13%   |
| Chicony USB2.0 Camera                            | 2         | 1.13%   |
| Chicony Integrated Camera [ThinkPad]             | 2         | 1.13%   |
| Chicony HD User Facing                           | 2         | 1.13%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera | 2         | 1.13%   |
| Acer BisonCam, NB Pro                            | 2         | 1.13%   |
| Syntek Lenovo EasyCamera                         | 1         | 0.56%   |
| Suyin UVC HD Webcam                              | 1         | 0.56%   |
| Suyin Laptop_Integrated_Webcam_HD                | 1         | 0.56%   |
| Suyin HD WebCam                                  | 1         | 0.56%   |
| Suyin Asus Integrated Webcam                     | 1         | 0.56%   |
| Suyin Acer/Lenovo Webcam [CN0316]                | 1         | 0.56%   |
| Suyin Acer HD Crystal Eye webcam                 | 1         | 0.56%   |
| SunplusIT XiaoMi USB 2.0 Webcam                  | 1         | 0.56%   |
| Sunplus TOSHIBA Web Camera - HD                  | 1         | 0.56%   |
| Sunplus Lenovo EasyCamera                        | 1         | 0.56%   |
| Sunplus Laptop Integrated Webcam HD              | 1         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 13        | 23.64%  |
| Validity Sensors                   | 10        | 18.18%  |
| Shenzhen Goodix Technology         | 7         | 12.73%  |
| Upek                               | 6         | 10.91%  |
| LighTuning Technology              | 6         | 10.91%  |
| Elan Microelectronics              | 6         | 10.91%  |
| AuthenTec                          | 6         | 10.91%  |
| Realtek USB2.0 Finger Print Bridge | 1         | 1.82%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 7         | 12.73%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 10.91%  |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 10.91%  |
| Elan ELAN:Fingerprint                                                      | 4         | 7.27%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 5.45%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 5.45%   |
| Shenzhen Goodix  Fingerprint Device                                        | 3         | 5.45%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 3.64%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 3.64%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 3.64%   |
| Elan ELAN:ARM-M4                                                           | 2         | 3.64%   |
| AuthenTec AES2810                                                          | 2         | 3.64%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 3.64%   |
| Unknown                                                                    | 2         | 3.64%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.82%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.82%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.82%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 1.82%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.82%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.82%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 1.82%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.82%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.82%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 7         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 58200                                 | 4         | 57.14%  |
| Broadcom BCM5880 Secure Applications Processor | 2         | 28.57%  |
| Broadcom 5880                                  | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 117       | 55.45%  |
| 1     | 69        | 32.7%   |
| 2     | 21        | 9.95%   |
| 3     | 2         | 0.95%   |
| 5     | 1         | 0.47%   |
| 4     | 1         | 0.47%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 52        | 42.28%  |
| Graphics card            | 32        | 26.02%  |
| Net/wireless             | 13        | 10.57%  |
| Chipcard                 | 6         | 4.88%   |
| Multimedia controller    | 5         | 4.07%   |
| Camera                   | 5         | 4.07%   |
| Communication controller | 3         | 2.44%   |
| Net/ethernet             | 2         | 1.63%   |
| Wireless                 | 1         | 0.81%   |
| Storage/raid             | 1         | 0.81%   |
| Sound                    | 1         | 0.81%   |
| Firewire controller      | 1         | 0.81%   |
| Bluetooth                | 1         | 0.81%   |


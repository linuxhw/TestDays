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

Total: 271

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 46        | 23.83%  |
| Ubuntu 18.04                 | 18        | 9.33%   |
| Ubuntu 22.04                 | 11        | 5.7%    |
| Fedora 33                    | 10        | 5.18%   |
| Pop!_OS 20.04                | 5         | 2.59%   |
| Arch Rolling                 | 5         | 2.59%   |
| Arch                         | 5         | 2.59%   |
| Debian Testing               | 4         | 2.07%   |
| Zorin 16                     | 3         | 1.55%   |
| Xubuntu 20.04                | 3         | 1.55%   |
| Pop!_OS 22.04                | 3         | 1.55%   |
| Linux Mint 20                | 3         | 1.55%   |
| Fedora 36                    | 3         | 1.55%   |
| Fedora 32                    | 3         | 1.55%   |
| Debian 11                    | 3         | 1.55%   |
| Zorin 15                     | 2         | 1.04%   |
| Ubuntu 21.10                 | 2         | 1.04%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 1.04%   |
| OpenMandriva 4.3             | 2         | 1.04%   |
| Manjaro 20.1                 | 2         | 1.04%   |
| Linux Mint 21                | 2         | 1.04%   |
| Kubuntu 22.04                | 2         | 1.04%   |
| Kubuntu 20.10                | 2         | 1.04%   |
| Gentoo 2.6                   | 2         | 1.04%   |
| Garuda Linux Soaring         | 2         | 1.04%   |
| Fedora 35                    | 2         | 1.04%   |
| Fedora 34                    | 2         | 1.04%   |
| Fedora 31                    | 2         | 1.04%   |
| EndeavourOS Rolling          | 2         | 1.04%   |
| Debian                       | 2         | 1.04%   |
| ArcoLinux Rolling            | 2         | 1.04%   |
| Xubuntu 21.04                | 1         | 0.52%   |
| Ubuntu Unity 16.04           | 1         | 0.52%   |
| Ubuntu Budgie 20.04          | 1         | 0.52%   |
| Ubuntu 21.04                 | 1         | 0.52%   |
| Ubuntu 19.10                 | 1         | 0.52%   |
| Ubuntu 19.04                 | 1         | 0.52%   |
| Ubuntu 18.10                 | 1         | 0.52%   |
| ROSA R8                      | 1         | 0.52%   |
| ROSA R11                     | 1         | 0.52%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 80        | 43.01%  |
| Fedora        | 19        | 10.22%  |
| Pop!_OS       | 11        | 5.91%   |
| Debian        | 11        | 5.91%   |
| Arch          | 9         | 4.84%   |
| Linux Mint    | 6         | 3.23%   |
| Zorin         | 5         | 2.69%   |
| Kubuntu       | 5         | 2.69%   |
| Xubuntu       | 4         | 2.15%   |
| OpenMandriva  | 4         | 2.15%   |
| Manjaro       | 4         | 2.15%   |
| ROSA          | 2         | 1.08%   |
| RHEL          | 2         | 1.08%   |
| openSUSE      | 2         | 1.08%   |
| Lubuntu       | 2         | 1.08%   |
| Kali          | 2         | 1.08%   |
| Gentoo        | 2         | 1.08%   |
| Garuda Linux  | 2         | 1.08%   |
| Endless       | 2         | 1.08%   |
| EndeavourOS   | 2         | 1.08%   |
| Clear Linux   | 2         | 1.08%   |
| ArcoLinux     | 2         | 1.08%   |
| Ubuntu Unity  | 1         | 0.54%   |
| Ubuntu Budgie | 1         | 0.54%   |
| Q4OS          | 1         | 0.54%   |
| LMDE          | 1         | 0.54%   |
| KDE neon      | 1         | 0.54%   |
| Deepin        | 1         | 0.54%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.4.0-48-generic        | 5         | 2.35%   |
| 5.15.0-46-generic       | 5         | 2.35%   |
| 5.9.8-200.fc33.x86_64   | 4         | 1.88%   |
| 5.4.0-42-generic        | 4         | 1.88%   |
| 5.4.0-40-generic        | 4         | 1.88%   |
| 5.3.0-62-generic        | 4         | 1.88%   |
| 5.11.0-43-generic       | 4         | 1.88%   |
| 5.4.0-65-generic        | 3         | 1.41%   |
| 5.4.0-52-generic        | 3         | 1.41%   |
| 5.4.0-47-generic        | 3         | 1.41%   |
| 5.4.0-37-generic        | 3         | 1.41%   |
| 5.4.0-29-generic        | 3         | 1.41%   |
| 5.13.0-28-generic       | 3         | 1.41%   |
| 5.11.0-38-generic       | 3         | 1.41%   |
| 5.4.5-050405-generic    | 2         | 0.94%   |
| 5.4.0-7634-generic      | 2         | 0.94%   |
| 5.4.0-31-generic        | 2         | 0.94%   |
| 5.4.0-26-generic        | 2         | 0.94%   |
| 5.18.0-3-amd64          | 2         | 0.94%   |
| 5.18.0-2-amd64          | 2         | 0.94%   |
| 5.17.5-76051705-generic | 2         | 0.94%   |
| 5.16.7-desktop-1omv4003 | 2         | 0.94%   |
| 5.15.0-48-generic       | 2         | 0.94%   |
| 5.15.0-47-generic       | 2         | 0.94%   |
| 5.15.0-43-generic       | 2         | 0.94%   |
| 5.13.0-40-generic       | 2         | 0.94%   |
| 5.13.0-37-generic       | 2         | 0.94%   |
| 5.11.0-37-generic       | 2         | 0.94%   |
| 5.11.0-25-generic       | 2         | 0.94%   |
| 5.0.0-23-generic        | 2         | 0.94%   |
| 4.18.0-15-generic       | 2         | 0.94%   |
| 6.0.2-zen1-1-zen        | 1         | 0.47%   |
| 6.0.0-2-amd64           | 1         | 0.47%   |
| 6.0.0-1-amd64           | 1         | 0.47%   |
| 5.9.9-200.fc33.x86_64   | 1         | 0.47%   |
| 5.9.16-200.fc33.x86_64  | 1         | 0.47%   |
| 5.9.15-200.fc33.x86_64  | 1         | 0.47%   |
| 5.9.10-arch1-1          | 1         | 0.47%   |
| 5.8.7-1-default         | 1         | 0.47%   |
| 5.8.5-arch1-1           | 1         | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 38        | 18.63%  |
| 5.15.0  | 18        | 8.82%   |
| 5.11.0  | 13        | 6.37%   |
| 5.8.0   | 11        | 5.39%   |
| 5.13.0  | 10        | 4.9%    |
| 5.3.0   | 7         | 3.43%   |
| 4.18.0  | 7         | 3.43%   |
| 4.15.0  | 7         | 3.43%   |
| 5.18.0  | 6         | 2.94%   |
| 5.9.8   | 4         | 1.96%   |
| 5.10.0  | 4         | 1.96%   |
| 5.0.0   | 4         | 1.96%   |
| 6.0.0   | 2         | 0.98%   |
| 5.4.5   | 2         | 0.98%   |
| 5.19.13 | 2         | 0.98%   |
| 5.17.5  | 2         | 0.98%   |
| 5.16.7  | 2         | 0.98%   |
| 5.13.13 | 2         | 0.98%   |
| 4.19.0  | 2         | 0.98%   |
| 6.0.2   | 1         | 0.49%   |
| 5.9.9   | 1         | 0.49%   |
| 5.9.16  | 1         | 0.49%   |
| 5.9.15  | 1         | 0.49%   |
| 5.9.10  | 1         | 0.49%   |
| 5.8.7   | 1         | 0.49%   |
| 5.8.5   | 1         | 0.49%   |
| 5.8.4   | 1         | 0.49%   |
| 5.8.3   | 1         | 0.49%   |
| 5.8.12  | 1         | 0.49%   |
| 5.8.11  | 1         | 0.49%   |
| 5.7.0   | 1         | 0.49%   |
| 5.6.7   | 1         | 0.49%   |
| 5.6.5   | 1         | 0.49%   |
| 5.6.15  | 1         | 0.49%   |
| 5.6.0   | 1         | 0.49%   |
| 5.5.2   | 1         | 0.49%   |
| 5.5.0   | 1         | 0.49%   |
| 5.4.8   | 1         | 0.49%   |
| 5.4.78  | 1         | 0.49%   |
| 5.4.70  | 1         | 0.49%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 44        | 22%     |
| 5.15    | 22        | 11%     |
| 5.8     | 17        | 8.5%    |
| 5.13    | 16        | 8%      |
| 5.11    | 14        | 7%      |
| 5.18    | 10        | 5%      |
| 5.10    | 10        | 5%      |
| 5.9     | 7         | 3.5%    |
| 5.3     | 7         | 3.5%    |
| 4.18    | 7         | 3.5%    |
| 4.15    | 7         | 3.5%    |
| 5.16    | 6         | 3%      |
| 5.0     | 5         | 2.5%    |
| 5.6     | 4         | 2%      |
| 5.19    | 4         | 2%      |
| 5.17    | 4         | 2%      |
| 6.0     | 3         | 1.5%    |
| 5.12    | 3         | 1.5%    |
| 4.19    | 3         | 1.5%    |
| 5.5     | 2         | 1%      |
| 5.7     | 1         | 0.5%    |
| 5.14    | 1         | 0.5%    |
| 4.4     | 1         | 0.5%    |
| 4.16    | 1         | 0.5%    |
| 3.10    | 1         | 0.5%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 176       | 98.88%  |
| i686   | 2         | 1.12%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 114       | 60.64%  |
| KDE5            | 23        | 12.23%  |
| Unknown         | 19        | 10.11%  |
| XFCE            | 7         | 3.72%   |
| X-Cinnamon      | 7         | 3.72%   |
| KDE             | 5         | 2.66%   |
| Cinnamon        | 4         | 2.13%   |
| LXQt            | 3         | 1.6%    |
| Unity           | 1         | 0.53%   |
| KDE4            | 1         | 0.53%   |
| i3              | 1         | 0.53%   |
| GNOME Flashback | 1         | 0.53%   |
| GNOME Classic   | 1         | 0.53%   |
| Budgie          | 1         | 0.53%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 139       | 75.96%  |
| Wayland | 26        | 14.21%  |
| Unknown | 12        | 6.56%   |
| Tty     | 6         | 3.28%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 84        | 44.92%  |
| GDM     | 40        | 21.39%  |
| GDM3    | 26        | 13.9%   |
| SDDM    | 23        | 12.3%   |
| LightDM | 9         | 4.81%   |
| TDM     | 4         | 2.14%   |
| KDM     | 1         | 0.53%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_SG   | 72        | 39.78%  |
| en_US   | 70        | 38.67%  |
| Unknown | 16        | 8.84%   |
| en_IN   | 6         | 3.31%   |
| zh_CN   | 3         | 1.66%   |
| de_DE   | 3         | 1.66%   |
| C       | 3         | 1.66%   |
| en_PH   | 2         | 1.1%    |
| en_GB   | 2         | 1.1%    |
| en_AU   | 2         | 1.1%    |
| ru_UA   | 1         | 0.55%   |
| en_IE   | 1         | 0.55%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 129       | 72.07%  |
| BIOS | 50        | 27.93%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 151       | 83.89%  |
| Btrfs   | 14        | 7.78%   |
| Unknown | 7         | 3.89%   |
| Overlay | 4         | 2.22%   |
| Zfs     | 2         | 1.11%   |
| Xfs     | 2         | 1.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 93        | 51.67%  |
| GPT     | 82        | 45.56%  |
| MBR     | 5         | 2.78%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 163       | 89.07%  |
| Yes       | 20        | 10.93%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 110       | 61.11%  |
| Yes       | 70        | 38.89%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 48        | 26.97%  |
| Dell                   | 37        | 20.79%  |
| ASUSTek Computer       | 28        | 15.73%  |
| Acer                   | 22        | 12.36%  |
| Hewlett-Packard        | 12        | 6.74%   |
| Apple                  | 7         | 3.93%   |
| Sony                   | 4         | 2.25%   |
| MSI                    | 3         | 1.69%   |
| Toshiba                | 2         | 1.12%   |
| Timi                   | 2         | 1.12%   |
| Samsung Electronics    | 2         | 1.12%   |
| Fujitsu                | 2         | 1.12%   |
| Foxconn                | 2         | 1.12%   |
| Aftershock             | 2         | 1.12%   |
| Razer                  | 1         | 0.56%   |
| Notebook               | 1         | 0.56%   |
| MECHREVO               | 1         | 0.56%   |
| COPELION INTERNATIONAL | 1         | 0.56%   |
| AMI                    | 1         | 0.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Lenovo ThinkPad X220 42911H8                          | 2         | 1.12%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ                      | 2         | 1.12%   |
| Lenovo IdeaPad S340-14API 81NB                        | 2         | 1.12%   |
| HP Compaq 6510b                                       | 2         | 1.12%   |
| Foxconn Kangaroo Mobile Desktop                       | 2         | 1.12%   |
| Dell Latitude 3320                                    | 2         | 1.12%   |
| Dell Latitude 3120                                    | 2         | 1.12%   |
| Dell Inspiron 15 5510                                 | 2         | 1.12%   |
| ASUS VivoBook_ASUSLaptop M3500QC_M3500QC              | 2         | 1.12%   |
| ASUS T300LA                                           | 2         | 1.12%   |
| Apple MacBookPro8,1                                   | 2         | 1.12%   |
| Acer ConceptD CN715-71                                | 2         | 1.12%   |
| Toshiba PORTEGE Z10t-A                                | 1         | 0.56%   |
| Toshiba PORTEGE R930                                  | 1         | 0.56%   |
| Timi TM1701                                           | 1         | 0.56%   |
| Timi Redmi Book Pro 14 2022                           | 1         | 0.56%   |
| Sony VPCSB36FG                                        | 1         | 0.56%   |
| Sony VPCCA15FG                                        | 1         | 0.56%   |
| Sony VGN-CR32G_W                                      | 1         | 0.56%   |
| Sony SVF1531V8CW                                      | 1         | 0.56%   |
| Samsung RF510/RF410/RF710                             | 1         | 0.56%   |
| Samsung 305U1A                                        | 1         | 0.56%   |
| Razer Blade 15 Advanced Model (Early 2020) - RZ09-033 | 1         | 0.56%   |
| Notebook P65_P67SE                                    | 1         | 0.56%   |
| MSI Pulse GL66 11UGK                                  | 1         | 0.56%   |
| MSI Modern 14 B5M                                     | 1         | 0.56%   |
| MSI GE63VR 7RE                                        | 1         | 0.56%   |
| MECHREVO Code 01 Series PF5NU1G                       | 1         | 0.56%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS                    | 1         | 0.56%   |
| Lenovo Yoga 3 Pro-1370 80HE                           | 1         | 0.56%   |
| Lenovo Yoga 3 14 80JH                                 | 1         | 0.56%   |
| Lenovo ThinkPad X395 20NL000TCD                       | 1         | 0.56%   |
| Lenovo ThinkPad X240 20AMS00100                       | 1         | 0.56%   |
| Lenovo ThinkPad X230 23257VA                          | 1         | 0.56%   |
| Lenovo ThinkPad X230 23256N6                          | 1         | 0.56%   |
| Lenovo ThinkPad X220 Tablet 4298WBT                   | 1         | 0.56%   |
| Lenovo ThinkPad X220 4286C11                          | 1         | 0.56%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QVCTO1WW             | 1         | 0.56%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9005TSG            | 1         | 0.56%   |
| Lenovo ThinkPad X1 Carbon 6th EX480SIT13              | 1         | 0.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 27        | 15.17%  |
| Dell Inspiron      | 13        | 7.3%    |
| Dell Latitude      | 11        | 6.18%   |
| ASUS VivoBook      | 9         | 5.06%   |
| Acer Aspire        | 9         | 5.06%   |
| Lenovo IdeaPad     | 8         | 4.49%   |
| Dell XPS           | 8         | 4.49%   |
| Acer Swift         | 7         | 3.93%   |
| Lenovo Legion      | 5         | 2.81%   |
| HP Pavilion        | 4         | 2.25%   |
| ASUS ZenBook       | 4         | 2.25%   |
| Lenovo Yoga        | 3         | 1.69%   |
| HP EliteBook       | 3         | 1.69%   |
| Dell Precision     | 3         | 1.69%   |
| Toshiba PORTEGE    | 2         | 1.12%   |
| HP ZBook           | 2         | 1.12%   |
| HP Compaq          | 2         | 1.12%   |
| Fujitsu LIFEBOOK   | 2         | 1.12%   |
| Foxconn Kangaroo   | 2         | 1.12%   |
| ASUS TUF           | 2         | 1.12%   |
| ASUS T300LA        | 2         | 1.12%   |
| Apple MacBookPro8  | 2         | 1.12%   |
| Apple MacBookPro11 | 2         | 1.12%   |
| Acer Predator      | 2         | 1.12%   |
| Acer ConceptD      | 2         | 1.12%   |
| Timi TM1701        | 1         | 0.56%   |
| Timi Redmi         | 1         | 0.56%   |
| Sony VPCSB36FG     | 1         | 0.56%   |
| Sony VPCCA15FG     | 1         | 0.56%   |
| Sony VGN-CR32G     | 1         | 0.56%   |
| Sony SVF1531V8CW   | 1         | 0.56%   |
| Samsung RF510      | 1         | 0.56%   |
| Samsung 305U1A     | 1         | 0.56%   |
| Razer Blade        | 1         | 0.56%   |
| Notebook P65       | 1         | 0.56%   |
| MSI Pulse          | 1         | 0.56%   |
| MSI Modern         | 1         | 0.56%   |
| MSI GE63VR         | 1         | 0.56%   |
| MECHREVO Code      | 1         | 0.56%   |
| Lenovo ThinkBook   | 1         | 0.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 25        | 14.04%  |
| 2021 | 24        | 13.48%  |
| 2020 | 23        | 12.92%  |
| 2018 | 18        | 10.11%  |
| 2011 | 13        | 7.3%    |
| 2014 | 11        | 6.18%   |
| 2017 | 10        | 5.62%   |
| 2012 | 10        | 5.62%   |
| 2016 | 9         | 5.06%   |
| 2015 | 9         | 5.06%   |
| 2022 | 5         | 2.81%   |
| 2013 | 5         | 2.81%   |
| 2010 | 5         | 2.81%   |
| 2008 | 4         | 2.25%   |
| 2007 | 4         | 2.25%   |
| 2009 | 3         | 1.69%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 178       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 148       | 82.22%  |
| Enabled  | 32        | 17.78%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 178       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 49        | 26.92%  |
| 4.01-8.0    | 44        | 24.18%  |
| 3.01-4.0    | 29        | 15.93%  |
| 8.01-16.0   | 28        | 15.38%  |
| 32.01-64.0  | 19        | 10.44%  |
| 1.01-2.0    | 6         | 3.3%    |
| 64.01-256.0 | 3         | 1.65%   |
| 24.01-32.0  | 2         | 1.1%    |
| 2.01-3.0    | 2         | 1.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 57        | 28.08%  |
| 2.01-3.0   | 47        | 23.15%  |
| 4.01-8.0   | 43        | 21.18%  |
| 3.01-4.0   | 31        | 15.27%  |
| 8.01-16.0  | 13        | 6.4%    |
| 0.51-1.0   | 9         | 4.43%   |
| 16.01-24.0 | 2         | 0.99%   |
| 0.01-0.5   | 1         | 0.49%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 130       | 71.43%  |
| 2      | 44        | 24.18%  |
| 3      | 7         | 3.85%   |
| 0      | 1         | 0.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 147       | 82.58%  |
| Yes       | 31        | 17.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 116       | 64.8%   |
| No        | 63        | 35.2%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 174       | 97.75%  |
| No        | 4         | 2.25%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 152       | 84.92%  |
| No        | 27        | 15.08%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Singapore | 178       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Singapore            | 170       | 95.51%  |
| Jurong West          | 4         | 2.25%   |
| Sembawang Estate     | 1         | 0.56%   |
| Queenstown Estate    | 1         | 0.56%   |
| Kampong Ulu Jurong   | 1         | 0.56%   |
| Bukit Batok New Town | 1         | 0.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 47        | 63     | 20.8%   |
| WDC                 | 22        | 42     | 9.73%   |
| Seagate             | 21        | 25     | 9.29%   |
| SanDisk             | 18        | 20     | 7.96%   |
| SK hynix            | 16        | 18     | 7.08%   |
| Toshiba             | 13        | 17     | 5.75%   |
| Unknown             | 12        | 14     | 5.31%   |
| Intel               | 9         | 11     | 3.98%   |
| HGST                | 8         | 12     | 3.54%   |
| Micron Technology   | 6         | 7      | 2.65%   |
| Hitachi             | 6         | 6      | 2.65%   |
| Kingston            | 5         | 6      | 2.21%   |
| Phison              | 4         | 6      | 1.77%   |
| KIOXIA              | 4         | 4      | 1.77%   |
| Apple               | 4         | 4      | 1.77%   |
| China               | 3         | 3      | 1.33%   |
| Transcend           | 2         | 3      | 0.88%   |
| Patriot             | 2         | 2      | 0.88%   |
| LITEON              | 2         | 3      | 0.88%   |
| Lexar               | 2         | 2      | 0.88%   |
| Lenovo              | 2         | 2      | 0.88%   |
| JMicron Technology  | 2         | 3      | 0.88%   |
| Hewlett-Packard     | 2         | 3      | 0.88%   |
| Crucial             | 2         | 2      | 0.88%   |
| UMIS                | 1         | 1      | 0.44%   |
| TO Exter            | 1         | 1      | 0.44%   |
| Team                | 1         | 1      | 0.44%   |
| SPCC                | 1         | 1      | 0.44%   |
| OCZ                 | 1         | 1      | 0.44%   |
| INTEL SS            | 1         | 2      | 0.44%   |
| GALAX               | 1         | 1      | 0.44%   |
| Fujitsu             | 1         | 1      | 0.44%   |
| External            | 1         | 1      | 0.44%   |
| CT1000MX            | 1         | 2      | 0.44%   |
| Corsair             | 1         | 2      | 0.44%   |
| A-DATA Technology   | 1         | 1      | 0.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 6         | 2.59%   |
| Samsung NVMe SSD Drive 1024GB        | 4         | 1.72%   |
| Toshiba MQ04ABF100 1TB               | 3         | 1.29%   |
| SK hynix SKHynix_HFS001TDE9X084N 1TB | 3         | 1.29%   |
| SanDisk NVMe SSD Drive 512GB         | 3         | 1.29%   |
| HGST HTS721010A9E630 1TB             | 3         | 1.29%   |
| WDC WDS500G2X0C-00L350 500GB         | 2         | 0.86%   |
| WDC WDS100T2X0C-00L350 1TB           | 2         | 0.86%   |
| WDC WD10SPZX-21Z10T0 1TB             | 2         | 0.86%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB   | 2         | 0.86%   |
| WDC PC SN720 SED SDAQNTW-1T00 1TB    | 2         | 0.86%   |
| Unknown MMC Card  64GB               | 2         | 0.86%   |
| Unknown MMC Card  32GB               | 2         | 0.86%   |
| Toshiba MQ01ABD100 1TB               | 2         | 0.86%   |
| Toshiba MK5055GSX 500GB              | 2         | 0.86%   |
| SK hynix HFM512GDJTNG-8310A 512GB    | 2         | 0.86%   |
| Seagate ST1000LM049-2GH172 1TB       | 2         | 0.86%   |
| Seagate Expansion 2TB                | 2         | 0.86%   |
| SanDisk SSD PLUS 240GB               | 2         | 0.86%   |
| SanDisk SD6SN1M128G1002 128GB SSD    | 2         | 0.86%   |
| Samsung SSD 970 EVO Plus 500GB       | 2         | 0.86%   |
| Samsung SSD 860 EVO 500GB            | 2         | 0.86%   |
| Samsung SSD 860 EVO 250GB            | 2         | 0.86%   |
| Samsung SSD 850 EVO 500GB            | 2         | 0.86%   |
| Samsung SSD 840 EVO 250GB            | 2         | 0.86%   |
| Samsung NVMe SSD Drive 512GB         | 2         | 0.86%   |
| Samsung MZVLB1T0HBLR-000L7 1TB       | 2         | 0.86%   |
| Samsung MZALQ512HALU-000L2 512GB     | 2         | 0.86%   |
| KIOXIA KBG40ZNS128G NVMe 128GB       | 2         | 0.86%   |
| JMicron Generic 500GB                | 2         | 0.86%   |
| Intel SSDPEKNU512GZ 512GB            | 2         | 0.86%   |
| Intel NVMe SSD Drive 512GB           | 2         | 0.86%   |
| Intel NVMe SSD Drive 1024GB          | 2         | 0.86%   |
| HGST HTS725050A7E630 500GB           | 2         | 0.86%   |
| HGST HTS545050A7E380 500GB           | 2         | 0.86%   |
| China SSD 128GB                      | 2         | 0.86%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD     | 1         | 0.43%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 1         | 0.43%   |
| WDC WDS100T2B0B-00YS70 1TB SSD       | 1         | 0.43%   |
| WDC WD7500BPVT-80HXZT3 752GB         | 1         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 24     | 37.04%  |
| Toshiba             | 9         | 13     | 16.67%  |
| WDC                 | 8         | 11     | 14.81%  |
| HGST                | 8         | 12     | 14.81%  |
| Hitachi             | 6         | 6      | 11.11%  |
| Samsung Electronics | 1         | 3      | 1.85%   |
| Fujitsu             | 1         | 1      | 1.85%   |
| Apple               | 1         | 1      | 1.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 25        | 33     | 37.31%  |
| SanDisk             | 12        | 13     | 17.91%  |
| China               | 3         | 3      | 4.48%   |
| Apple               | 3         | 3      | 4.48%   |
| WDC                 | 2         | 3      | 2.99%   |
| Transcend           | 2         | 3      | 2.99%   |
| SK hynix            | 2         | 2      | 2.99%   |
| Patriot             | 2         | 2      | 2.99%   |
| Micron Technology   | 2         | 3      | 2.99%   |
| LITEON              | 2         | 3      | 2.99%   |
| Kingston            | 2         | 3      | 2.99%   |
| Crucial             | 2         | 2      | 2.99%   |
| Toshiba             | 1         | 1      | 1.49%   |
| TO Exter            | 1         | 1      | 1.49%   |
| SPCC                | 1         | 1      | 1.49%   |
| OCZ                 | 1         | 1      | 1.49%   |
| Lexar               | 1         | 1      | 1.49%   |
| Hewlett-Packard     | 1         | 2      | 1.49%   |
| GALAX               | 1         | 1      | 1.49%   |
| CT1000MX            | 1         | 2      | 1.49%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 86        | 127    | 40.76%  |
| SSD     | 63        | 83     | 29.86%  |
| HDD     | 52        | 71     | 24.64%  |
| MMC     | 9         | 11     | 4.27%   |
| Unknown | 1         | 1      | 0.47%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 98        | 146    | 48.04%  |
| NVMe | 86        | 121    | 42.16%  |
| SAS  | 11        | 15     | 5.39%   |
| MMC  | 9         | 11     | 4.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 72        | 98     | 64.29%  |
| 0.51-1.0   | 34        | 49     | 30.36%  |
| 1.01-2.0   | 6         | 7      | 5.36%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 55        | 28.95%  |
| 251-500        | 42        | 22.11%  |
| 501-1000       | 32        | 16.84%  |
| 51-100         | 16        | 8.42%   |
| 1001-2000      | 14        | 7.37%   |
| 1-20           | 11        | 5.79%   |
| 21-50          | 7         | 3.68%   |
| More than 3000 | 6         | 3.16%   |
| Unknown        | 5         | 2.63%   |
| 2001-3000      | 2         | 1.05%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 75        | 38.86%  |
| 21-50          | 35        | 18.13%  |
| 101-250        | 28        | 14.51%  |
| 251-500        | 19        | 9.84%   |
| 51-100         | 18        | 9.33%   |
| 501-1000       | 8         | 4.15%   |
| Unknown        | 5         | 2.59%   |
| 1001-2000      | 3         | 1.55%   |
| More than 3000 | 1         | 0.52%   |
| 2001-3000      | 1         | 0.52%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-16HXZT1 500GB       | 1         | 1      | 14.29%  |
| WDC WD10SPZX-21Z10T0 1TB           | 1         | 2      | 14.29%  |
| Seagate ST2000LM003 HN-M201RAD 2TB | 1         | 1      | 14.29%  |
| Seagate ST1000LM024 HN-M 1TB       | 1         | 1      | 14.29%  |
| Hitachi HTS545032B9A300 320GB      | 1         | 1      | 14.29%  |
| Hitachi HTS541010A9E680 1TB        | 1         | 1      | 14.29%  |
| China SSD 128GB                    | 1         | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 3      | 28.57%  |
| Seagate | 2         | 2      | 28.57%  |
| Hitachi | 2         | 2      | 28.57%  |
| China   | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 3      | 33.33%  |
| Seagate | 2         | 2      | 33.33%  |
| Hitachi | 2         | 2      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 7      | 85.71%  |
| SSD  | 1         | 1      | 14.29%  |

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
| Detected | 109       | 173    | 56.77%  |
| Works    | 76        | 112    | 39.58%  |
| Malfunc  | 7         | 8      | 3.65%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 114       | 52.05%  |
| Samsung Electronics          | 24        | 10.96%  |
| SanDisk                      | 18        | 8.22%   |
| AMD                          | 18        | 8.22%   |
| SK hynix                     | 14        | 6.39%   |
| KIOXIA                       | 5         | 2.28%   |
| Phison Electronics           | 4         | 1.83%   |
| Micron Technology            | 4         | 1.83%   |
| Toshiba America Info Systems | 3         | 1.37%   |
| Nvidia                       | 3         | 1.37%   |
| Kingston Technology Company  | 3         | 1.37%   |
| Shenzhen Longsys Electronics | 2         | 0.91%   |
| Lenovo                       | 2         | 0.91%   |
| ADATA Technology             | 2         | 0.91%   |
| Union Memory (Shenzhen)      | 1         | 0.46%   |
| Silicon Motion               | 1         | 0.46%   |
| Seagate Technology           | 1         | 0.46%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 17        | 7.49%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 14        | 6.17%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 14        | 6.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 12        | 5.29%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 10        | 4.41%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 9         | 3.96%   |
| Intel Volume Management Device NVMe RAID Controller                              | 8         | 3.52%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 8         | 3.52%   |
| SK hynix Gold P31 SSD                                                            | 7         | 3.08%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 7         | 3.08%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 6         | 2.64%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 6         | 2.64%   |
| Samsung NVMe SSD Controller 980                                                  | 5         | 2.2%    |
| KIOXIA NVMe SSD Controller BG4                                                   | 5         | 2.2%    |
| Intel SSD 660P Series                                                            | 5         | 2.2%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 5         | 2.2%    |
| Micron Non-Volatile memory controller                                            | 4         | 1.76%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 1.76%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 1.76%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 3         | 1.32%   |
| SK hynix Non-Volatile memory controller                                          | 3         | 1.32%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 3         | 1.32%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 3         | 1.32%   |
| Phison E12 NVMe Controller                                                       | 3         | 1.32%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 1.32%   |
| Intel Tiger Lake-LP SATA Controller                                              | 3         | 1.32%   |
| Intel Non-Volatile memory controller                                             | 3         | 1.32%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 3         | 1.32%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 1.32%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 1.32%   |
| SanDisk Non-Volatile memory controller                                           | 2         | 0.88%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 0.88%   |
| Samsung Electronics SATA controller                                              | 2         | 0.88%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 2         | 0.88%   |
| Lenovo Non-Volatile memory controller                                            | 2         | 0.88%   |
| Kingston Company Company Non-Volatile memory controller                          | 2         | 0.88%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 0.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 0.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 0.88%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 2         | 0.88%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 108       | 48.87%  |
| NVMe | 87        | 39.37%  |
| RAID | 19        | 8.6%    |
| IDE  | 7         | 3.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 146       | 82.02%  |
| AMD    | 32        | 17.98%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 5.06%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 7         | 3.93%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 6         | 3.37%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 2.81%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 2.81%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 5         | 2.81%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 2.81%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 2.25%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 4         | 2.25%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 2.25%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.69%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 1.69%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 1.69%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.69%   |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 2         | 1.12%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 2         | 1.12%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.12%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.12%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 1.12%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 1.12%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 1.12%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 1.12%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 1.12%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.12%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 2         | 1.12%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 1.12%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 2         | 1.12%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz          | 2         | 1.12%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 1.12%   |
| Intel Atom x5-Z8500 CPU @ 1.44GHz             | 2         | 1.12%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 1.12%   |
| Intel 11th Gen Core i7-11390H @ 3.40GHz       | 2         | 1.12%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 1.12%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 1.12%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 1.12%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 2         | 1.12%   |
| Intel Xeon W-11955M CPU @ 2.60GHz             | 1         | 0.56%   |
| Intel Processor 5Y70 CPU @ 1.10GHz            | 1         | 0.56%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.56%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 56        | 31.46%  |
| Intel Core i5           | 37        | 20.79%  |
| Other                   | 18        | 10.11%  |
| AMD Ryzen 7             | 11        | 6.18%   |
| AMD Ryzen 5             | 10        | 5.62%   |
| Intel Core 2 Duo        | 8         | 4.49%   |
| Intel Celeron           | 6         | 3.37%   |
| Intel Core i3           | 5         | 2.81%   |
| Intel Pentium Silver    | 4         | 2.25%   |
| Intel Atom              | 4         | 2.25%   |
| Intel Xeon              | 3         | 1.69%   |
| Intel Core i9           | 2         | 1.12%   |
| AMD Ryzen 7 PRO         | 2         | 1.12%   |
| AMD Ryzen 3             | 2         | 1.12%   |
| Intel Pentium Dual      | 1         | 0.56%   |
| Intel Core m3           | 1         | 0.56%   |
| Intel Core 2            | 1         | 0.56%   |
| AMD Turion 64 X2 Mobile | 1         | 0.56%   |
| AMD Ryzen 9             | 1         | 0.56%   |
| AMD Ryzen 5 PRO         | 1         | 0.56%   |
| AMD PRO A10             | 1         | 0.56%   |
| AMD E1                  | 1         | 0.56%   |
| AMD E                   | 1         | 0.56%   |
| AMD A6                  | 1         | 0.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 70        | 39.33%  |
| 2      | 66        | 37.08%  |
| 8      | 21        | 11.8%   |
| 6      | 17        | 9.55%   |
| 1      | 2         | 1.12%   |
| 14     | 1         | 0.56%   |
| 10     | 1         | 0.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 178       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 147       | 81.67%  |
| 1      | 33        | 18.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 175       | 98.31%  |
| 32-bit         | 2         | 1.12%   |
| Unknown        | 1         | 0.56%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 30        | 16.39%  |
| 0x806ea    | 12        | 6.56%   |
| 0x206a7    | 11        | 6.01%   |
| 0x906ea    | 10        | 5.46%   |
| 0x806ec    | 10        | 5.46%   |
| 0x306a9    | 9         | 4.92%   |
| 0x0a50000c | 9         | 4.92%   |
| 0x40651    | 7         | 3.83%   |
| 0x806c1    | 6         | 3.28%   |
| 0x806eb    | 5         | 2.73%   |
| 0x306d4    | 5         | 2.73%   |
| 0x806d1    | 4         | 2.19%   |
| 0x406e3    | 4         | 2.19%   |
| 0x1067a    | 4         | 2.19%   |
| 0x08108109 | 4         | 2.19%   |
| 0xa0652    | 3         | 1.64%   |
| 0x806e9    | 3         | 1.64%   |
| 0x806c2    | 3         | 1.64%   |
| 0x6fd      | 3         | 1.64%   |
| 0x506e3    | 3         | 1.64%   |
| 0x306c3    | 3         | 1.64%   |
| 0x20655    | 3         | 1.64%   |
| 0x08600106 | 3         | 1.64%   |
| 0x906e9    | 2         | 1.09%   |
| 0x906c0    | 2         | 1.09%   |
| 0x706a8    | 2         | 1.09%   |
| 0x706a1    | 2         | 1.09%   |
| 0x406c3    | 2         | 1.09%   |
| 0x40661    | 2         | 1.09%   |
| 0x30678    | 2         | 1.09%   |
| 0x106c2    | 2         | 1.09%   |
| 0x08600103 | 2         | 1.09%   |
| 0x08108102 | 2         | 1.09%   |
| 0x906ed    | 1         | 0.55%   |
| 0x906a3    | 1         | 0.55%   |
| 0x706e5    | 1         | 0.55%   |
| 0x6f6      | 1         | 0.55%   |
| 0x10676    | 1         | 0.55%   |
| 0x08608103 | 1         | 0.55%   |
| 0x0700010f | 1         | 0.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 49        | 27.53%  |
| SandyBridge   | 13        | 7.3%    |
| TigerLake     | 12        | 6.74%   |
| Haswell       | 12        | 6.74%   |
| Zen 3         | 11        | 6.18%   |
| IvyBridge     | 9         | 5.06%   |
| Zen+          | 8         | 4.49%   |
| Skylake       | 8         | 4.49%   |
| Zen 2         | 6         | 3.37%   |
| Penryn        | 6         | 3.37%   |
| Icelake       | 6         | 3.37%   |
| Silvermont    | 5         | 2.81%   |
| Broadwell     | 5         | 2.81%   |
| Goldmont plus | 4         | 2.25%   |
| Core          | 4         | 2.25%   |
| CometLake     | 4         | 2.25%   |
| Unknown       | 4         | 2.25%   |
| Westmere      | 3         | 1.69%   |
| Tremont       | 2         | 1.12%   |
| Excavator     | 2         | 1.12%   |
| Bonnell       | 2         | 1.12%   |
| K8 Hammer     | 1         | 0.56%   |
| Jaguar        | 1         | 0.56%   |
| Bobcat        | 1         | 0.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 136       | 56.67%  |
| Nvidia | 69        | 28.75%  |
| AMD    | 35        | 14.58%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                        | 14        | 5.67%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 12        | 4.86%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 11        | 4.45%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 10        | 4.05%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 9         | 3.64%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 9         | 3.64%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 8         | 3.24%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 7         | 2.83%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 7         | 2.83%   |
| AMD Cezanne                                                                   | 7         | 2.83%   |
| AMD Renoir                                                                    | 6         | 2.43%   |
| Nvidia GP108M [GeForce MX150]                                                 | 5         | 2.02%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                               | 5         | 2.02%   |
| Intel HD Graphics 620                                                         | 5         | 2.02%   |
| Intel HD Graphics 5500                                                        | 4         | 1.62%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 4         | 1.62%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 3         | 1.21%   |
| Nvidia GP108BM [GeForce MX250]                                                | 3         | 1.21%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 3         | 1.21%   |
| Nvidia GM107M [GeForce GTX 960M]                                              | 3         | 1.21%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 3         | 1.21%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 3         | 1.21%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 3         | 1.21%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 3         | 1.21%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 3         | 1.21%   |
| Intel HD Graphics 530                                                         | 3         | 1.21%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 3         | 1.21%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 3         | 1.21%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 2         | 0.81%   |
| Nvidia TU104M [GeForce RTX 2080 Mobile]                                       | 2         | 0.81%   |
| Nvidia MCP89 [GeForce 320M]                                                   | 2         | 0.81%   |
| Nvidia GP108M [GeForce MX250]                                                 | 2         | 0.81%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 2         | 0.81%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 2         | 0.81%   |
| Nvidia GM108M [GeForce 940M]                                                  | 2         | 0.81%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 2         | 0.81%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 2         | 0.81%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 2         | 0.81%   |
| Intel JasperLake [UHD Graphics]                                               | 2         | 0.81%   |
| Intel Iris Plus Graphics G7                                                   | 2         | 0.81%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 79        | 44.13%  |
| Intel + Nvidia | 50        | 27.93%  |
| 1 x AMD        | 21        | 11.73%  |
| 1 x Nvidia     | 15        | 8.38%   |
| Intel + AMD    | 7         | 3.91%   |
| AMD + Nvidia   | 5         | 2.79%   |
| 2 x AMD        | 2         | 1.12%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 143       | 78.14%  |
| Proprietary | 37        | 20.22%  |
| Unknown     | 3         | 1.64%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 120       | 63.83%  |
| 1.01-2.0   | 28        | 14.89%  |
| 0.01-0.5   | 16        | 8.51%   |
| 3.01-4.0   | 13        | 6.91%   |
| 7.01-8.0   | 4         | 2.13%   |
| 5.01-6.0   | 3         | 1.6%    |
| 0.51-1.0   | 2         | 1.06%   |
| 2.01-3.0   | 1         | 0.53%   |
| 8.01-16.0  | 1         | 0.53%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 59        | 28.78%  |
| BOE                     | 25        | 12.2%   |
| LG Display              | 24        | 11.71%  |
| Samsung Electronics     | 21        | 10.24%  |
| Chimei Innolux          | 17        | 8.29%   |
| Dell                    | 13        | 6.34%   |
| Apple                   | 7         | 3.41%   |
| Sharp                   | 6         | 2.93%   |
| Philips                 | 4         | 1.95%   |
| Goldstar                | 4         | 1.95%   |
| CSO                     | 4         | 1.95%   |
| Acer                    | 4         | 1.95%   |
| Lenovo                  | 3         | 1.46%   |
| InfoVision              | 3         | 1.46%   |
| LG Philips              | 2         | 0.98%   |
| Toshiba                 | 1         | 0.49%   |
| PANDA                   | 1         | 0.49%   |
| Mi                      | 1         | 0.49%   |
| Hewlett-Packard         | 1         | 0.49%   |
| EXP                     | 1         | 0.49%   |
| CVT                     | 1         | 0.49%   |
| CPT                     | 1         | 0.49%   |
| Chi Mei Optoelectronics | 1         | 0.49%   |
| ASUSTek Computer        | 1         | 0.49%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 3         | 1.46%   |
| Dell P2421D DELD0FF 2560x1440 530x300mm 24.0-inch                     | 3         | 1.46%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 3         | 1.46%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch  | 2         | 0.98%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 2         | 0.98%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch     | 2         | 0.98%   |
| LG Philips LCD Monitor LPL8D00 1280x800 304x190mm 14.1-inch           | 2         | 0.98%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch          | 2         | 0.98%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                | 2         | 0.98%   |
| Dell S2340L DELD058 1920x1080 509x286mm 23.0-inch                     | 2         | 0.98%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 2         | 0.98%   |
| Chimei Innolux LCD Monitor CMN1354 1920x1080 293x165mm 13.2-inch      | 2         | 0.98%   |
| BOE LCD Monitor BOE09C3 1366x768 256x144mm 11.6-inch                  | 2         | 0.98%   |
| BOE LCD Monitor BOE06A7 1920x1080 294x165mm 13.3-inch                 | 2         | 0.98%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 2         | 0.98%   |
| AU Optronics LCD Monitor AUO408D 1920x1080 309x174mm 14.0-inch        | 2         | 0.98%   |
| AU Optronics LCD Monitor AUO3892 1920x1080 344x194mm 15.5-inch        | 2         | 0.98%   |
| AU Optronics LCD Monitor AUO31EB 3840x2160 344x193mm 15.5-inch        | 2         | 0.98%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch        | 2         | 0.98%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch         | 2         | 0.98%   |
| AU Optronics LCD Monitor AUO2B99 1920x1080 293x165mm 13.2-inch        | 2         | 0.98%   |
| AU Optronics LCD Monitor AUO205C 1366x768 256x144mm 11.6-inch         | 2         | 0.98%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 2         | 0.98%   |
| Toshiba LCD TV LCD0030 1920x1080 708x398mm 32.0-inch                  | 1         | 0.49%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch               | 1         | 0.49%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 1         | 0.49%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.49%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch               | 1         | 0.49%   |
| Sharp LCD Monitor SHP1485 1920x1080 294x165mm 13.3-inch               | 1         | 0.49%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.49%   |
| Samsung Electronics U32R59x SAM0F94 3840x2160 697x392mm 31.5-inch     | 1         | 0.49%   |
| Samsung Electronics S34J55x SAM0F72 1720x1440                         | 1         | 0.49%   |
| Samsung Electronics S24R35xFZ SAM71A8 1920x1080 527x296mm 23.8-inch   | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC554E 1024x600 223x125mm 10.1-inch  | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch  | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 223x125mm 10.1-inch  | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch  | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 410x230mm 18.5-inch | 1         | 0.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 103       | 54.79%  |
| 1366x768 (WXGA)   | 34        | 18.09%  |
| 3840x2160 (4K)    | 10        | 5.32%   |
| 1280x800 (WXGA)   | 9         | 4.79%   |
| 2560x1440 (QHD)   | 7         | 3.72%   |
| 2560x1600         | 5         | 2.66%   |
| 1920x1200 (WUXGA) | 5         | 2.66%   |
| 3440x1440         | 3         | 1.6%    |
| 2880x1800         | 2         | 1.06%   |
| 2240x1400         | 2         | 1.06%   |
| 1360x768          | 2         | 1.06%   |
| 3840x2400         | 1         | 0.53%   |
| 3200x1800 (QHD+)  | 1         | 0.53%   |
| 1600x900 (HD+)    | 1         | 0.53%   |
| 1440x900 (WXGA+)  | 1         | 0.53%   |
| 1280x1024 (SXGA)  | 1         | 0.53%   |
| 1024x600          | 1         | 0.53%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 60        | 29.41%  |
| 13      | 46        | 22.55%  |
| 14      | 37        | 18.14%  |
| 23      | 10        | 4.9%    |
| 12      | 9         | 4.41%   |
| 27      | 8         | 3.92%   |
| 11      | 6         | 2.94%   |
| 24      | 5         | 2.45%   |
| 21      | 4         | 1.96%   |
| 16      | 4         | 1.96%   |
| 34      | 2         | 0.98%   |
| 32      | 2         | 0.98%   |
| 19      | 2         | 0.98%   |
| 18      | 2         | 0.98%   |
| 52      | 1         | 0.49%   |
| 40      | 1         | 0.49%   |
| 35      | 1         | 0.49%   |
| 31      | 1         | 0.49%   |
| 17      | 1         | 0.49%   |
| 10      | 1         | 0.49%   |
| Unknown | 1         | 0.49%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 119       | 58.33%  |
| 201-300     | 41        | 20.1%   |
| 501-600     | 23        | 11.27%  |
| 401-500     | 7         | 3.43%   |
| 351-400     | 5         | 2.45%   |
| 701-800     | 4         | 1.96%   |
| 801-900     | 2         | 0.98%   |
| 601-700     | 1         | 0.49%   |
| 1001-1500   | 1         | 0.49%   |
| Unknown     | 1         | 0.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 146       | 82.95%  |
| 16/10 | 25        | 14.2%   |
| 21/9  | 3         | 1.7%    |
| 5/4   | 1         | 0.57%   |
| 3/2   | 1         | 0.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 62        | 30.39%  |
| 101-110        | 60        | 29.41%  |
| 71-80          | 21        | 10.29%  |
| 201-250        | 18        | 8.82%   |
| 61-70          | 9         | 4.41%   |
| 301-350        | 8         | 3.92%   |
| 51-60          | 6         | 2.94%   |
| 351-500        | 6         | 2.94%   |
| 111-120        | 4         | 1.96%   |
| 151-200        | 3         | 1.47%   |
| 141-150        | 2         | 0.98%   |
| More than 1000 | 1         | 0.49%   |
| 41-50          | 1         | 0.49%   |
| 121-130        | 1         | 0.49%   |
| 501-1000       | 1         | 0.49%   |
| Unknown        | 1         | 0.49%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 94        | 47.72%  |
| 101-120       | 36        | 18.27%  |
| 161-240       | 31        | 15.74%  |
| 51-100        | 25        | 12.69%  |
| More than 240 | 8         | 4.06%   |
| 1-50          | 2         | 1.02%   |
| Unknown       | 1         | 0.51%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 143       | 76.88%  |
| 2     | 36        | 19.35%  |
| 0     | 6         | 3.23%   |
| 3     | 1         | 0.54%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 108       | 41.86%  |
| Realtek Semiconductor    | 68        | 26.36%  |
| Qualcomm Atheros         | 36        | 13.95%  |
| Broadcom                 | 15        | 5.81%   |
| MediaTek                 | 7         | 2.71%   |
| ASIX Electronics         | 7         | 2.71%   |
| Broadcom Limited         | 3         | 1.16%   |
| Marvell Technology Group | 2         | 0.78%   |
| Sierra Wireless          | 1         | 0.39%   |
| Samsung Electronics      | 1         | 0.39%   |
| Ralink Technology        | 1         | 0.39%   |
| Ralink                   | 1         | 0.39%   |
| Qualcomm                 | 1         | 0.39%   |
| Nvidia                   | 1         | 0.39%   |
| MosChip Semiconductor    | 1         | 0.39%   |
| Lenovo                   | 1         | 0.39%   |
| Hewlett-Packard          | 1         | 0.39%   |
| Google                   | 1         | 0.39%   |
| D-Link                   | 1         | 0.39%   |
| Apple                    | 1         | 0.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 39        | 12.83%  |
| Intel Wi-Fi 6 AX200                                                     | 13        | 4.28%   |
| Intel Wireless 7265                                                     | 12        | 3.95%   |
| Intel Wi-Fi 6 AX201                                                     | 11        | 3.62%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 10        | 3.29%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 9         | 2.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 2.63%   |
| Intel Wireless 8265 / 8275                                              | 8         | 2.63%   |
| Intel Wireless 7260                                                     | 7         | 2.3%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 2.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 7         | 2.3%    |
| ASIX AX88179 Gigabit Ethernet                                           | 7         | 2.3%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 1.97%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 1.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 1.97%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 1.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 5         | 1.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.32%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 1.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 0.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 0.99%   |
| Intel Wireless 3165                                                     | 3         | 0.99%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 0.99%   |
| Intel Ethernet Connection I218-LM                                       | 3         | 0.99%   |
| Intel Ethernet Connection (4) I219-LM                                   | 3         | 0.99%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 0.99%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 3         | 0.99%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 3         | 0.99%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 0.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.66%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 0.66%   |
| Realtek Killer E3000 2.5GbE Controller                                  | 2         | 0.66%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 2         | 0.66%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.66%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.66%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.66%   |
| Intel Wireless 8260                                                     | 2         | 0.66%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 2         | 0.66%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 0.66%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 0.66%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 106       | 58.89%  |
| Qualcomm Atheros      | 32        | 17.78%  |
| Realtek Semiconductor | 15        | 8.33%   |
| Broadcom              | 12        | 6.67%   |
| MediaTek              | 7         | 3.89%   |
| Broadcom Limited      | 2         | 1.11%   |
| Sierra Wireless       | 1         | 0.56%   |
| Ralink Technology     | 1         | 0.56%   |
| Ralink                | 1         | 0.56%   |
| Qualcomm              | 1         | 0.56%   |
| Hewlett-Packard       | 1         | 0.56%   |
| D-Link                | 1         | 0.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 13        | 7.18%   |
| Intel Wireless 7265                                                     | 12        | 6.63%   |
| Intel Wi-Fi 6 AX201                                                     | 11        | 6.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 10        | 5.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 4.42%   |
| Intel Wireless 8265 / 8275                                              | 8         | 4.42%   |
| Intel Wireless 7260                                                     | 7         | 3.87%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 3.87%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 3.31%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 3.31%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 3.31%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 3.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 2.21%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 2.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 1.66%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 1.66%   |
| Intel Wireless 3165                                                     | 3         | 1.66%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 1.66%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.66%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 3         | 1.66%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 1.1%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.1%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 1.1%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1.1%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.1%    |
| Intel Wireless-AC 9260                                                  | 2         | 1.1%    |
| Intel Wireless 8260                                                     | 2         | 1.1%    |
| Intel Wi-Fi 6 AX201 160MHz                                              | 2         | 1.1%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 1.1%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 1.1%    |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 1.1%    |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 2         | 1.1%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 2         | 1.1%    |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 1.1%    |
| Broadcom BCM4311 802.11a/b/g                                            | 2         | 1.1%    |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A                     | 1         | 0.55%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.55%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.55%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 57        | 46.72%  |
| Intel                    | 33        | 27.05%  |
| Qualcomm Atheros         | 9         | 7.38%   |
| Broadcom                 | 7         | 5.74%   |
| ASIX Electronics         | 7         | 5.74%   |
| Marvell Technology Group | 2         | 1.64%   |
| Samsung Electronics      | 1         | 0.82%   |
| Nvidia                   | 1         | 0.82%   |
| MosChip Semiconductor    | 1         | 0.82%   |
| Lenovo                   | 1         | 0.82%   |
| Google                   | 1         | 0.82%   |
| Broadcom Limited         | 1         | 0.82%   |
| Apple                    | 1         | 0.82%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 39        | 31.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 9         | 7.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7         | 5.69%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 7         | 5.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 4.07%   |
| Intel Ethernet Connection I218-LM                                              | 3         | 2.44%   |
| Intel Ethernet Connection (4) I219-LM                                          | 3         | 2.44%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 3         | 2.44%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 2         | 1.63%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 1.63%   |
| Intel Ethernet Connection (7) I219-LM                                          | 2         | 1.63%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 1.63%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 1.63%   |
| Intel Ethernet Connection (14) I219-LM                                         | 2         | 1.63%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 1.63%   |
| Intel 82579V Gigabit Network Connection                                        | 2         | 1.63%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 1.63%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.81%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.81%   |
| Realtek Realtek Ethernet controller                                            | 1         | 0.81%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.81%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.81%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.81%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.81%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.81%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.81%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.81%   |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 0.81%   |
| MosChip MCS7830 10/100 Mbps Ethernet adapter                                   | 1         | 0.81%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.81%   |
| Marvell Group 88E8038 PCI-E Fast Ethernet Controller                           | 1         | 0.81%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.81%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.81%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 0.81%   |
| Intel Ethernet Connection (7) I219-V                                           | 1         | 0.81%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.81%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 0.81%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.81%   |
| Google Nexus/Pixel Device (tether)                                             | 1         | 0.81%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 174       | 60%     |
| Ethernet | 116       | 40%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 156       | 80.83%  |
| Ethernet | 37        | 19.17%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 100       | 55.87%  |
| 1     | 77        | 43.02%  |
| 3     | 1         | 0.56%   |
| 0     | 1         | 0.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 165       | 92.7%   |
| Yes  | 13        | 7.3%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 87        | 56.86%  |
| IMC Networks                    | 13        | 8.5%    |
| Qualcomm Atheros Communications | 11        | 7.19%   |
| Foxconn / Hon Hai               | 11        | 7.19%   |
| Broadcom                        | 8         | 5.23%   |
| Lite-On Technology              | 6         | 3.92%   |
| Apple                           | 6         | 3.92%   |
| Realtek Semiconductor           | 3         | 1.96%   |
| Toshiba                         | 1         | 0.65%   |
| Ralink Technology               | 1         | 0.65%   |
| MediaTek                        | 1         | 0.65%   |
| Foxconn International           | 1         | 0.65%   |
| Chicony Electronics             | 1         | 0.65%   |
| Cambridge Silicon Radio         | 1         | 0.65%   |
| Askey Computer                  | 1         | 0.65%   |
| Alps Electric                   | 1         | 0.65%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 30        | 19.61%  |
| Intel AX201 Bluetooth                               | 25        | 16.34%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 17        | 11.11%  |
| Intel AX200 Bluetooth                               | 12        | 7.84%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 5         | 3.27%   |
| IMC Networks Bluetooth Radio                        | 5         | 3.27%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 2.61%   |
| IMC Networks Bluetooth Device                       | 4         | 2.61%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 2.61%   |
| Apple Bluetooth Host Controller                     | 4         | 2.61%   |
| IMC Networks Wireless_Device                        | 3         | 1.96%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 1.96%   |
| Foxconn / Hon Hai BCM20702A0                        | 3         | 1.96%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 1.96%   |
| Realtek Bluetooth Radio                             | 2         | 1.31%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 1.31%   |
| Lite-On Bluetooth Device                            | 2         | 1.31%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.31%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 1.31%   |
| Apple Bluetooth USB Host Controller                 | 2         | 1.31%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.65%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.65%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.65%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.65%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.65%   |
| MediaTek Wireless_Device                            | 1         | 0.65%   |
| Lite-On Bluetooth Radio                             | 1         | 0.65%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.65%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.65%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.65%   |
| Intel AX210 Bluetooth                               | 1         | 0.65%   |
| IMC Networks Bluetooth module                       | 1         | 0.65%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.65%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 0.65%   |
| Chicony Bluetooth (RTL8723BE)                       | 1         | 0.65%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 0.65%   |
| Broadcom Bluetooth                                  | 1         | 0.65%   |
| Askey Bluetooth Device                              | 1         | 0.65%   |
| Alps Electric Bluetooth Adapter                     | 1         | 0.65%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 141       | 65.28%  |
| AMD                 | 32        | 14.81%  |
| Nvidia              | 29        | 13.43%  |
| Plantronics         | 2         | 0.93%   |
| Lenovo              | 2         | 0.93%   |
| Kingston Technology | 2         | 0.93%   |
| Apple               | 2         | 0.93%   |
| Razer USA           | 1         | 0.46%   |
| Logitech            | 1         | 0.46%   |
| JBL                 | 1         | 0.46%   |
| Cooler Master       | 1         | 0.46%   |
| Conexant Systems    | 1         | 0.46%   |
| ASUSTek Computer    | 1         | 0.46%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 27        | 10.42%  |
| Intel Sunrise Point-LP HD Audio                                            | 23        | 8.88%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 14        | 5.41%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 12        | 4.63%   |
| Intel Cannon Lake PCH cAVS                                                 | 12        | 4.63%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 12        | 4.63%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 10        | 3.86%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 8         | 3.09%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8         | 3.09%   |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 2.7%    |
| Intel Comet Lake PCH-LP cAVS                                               | 7         | 2.7%    |
| Intel 8 Series HD Audio Controller                                         | 7         | 2.7%    |
| Nvidia GA104 High Definition Audio Controller                              | 6         | 2.32%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 1.93%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 1.93%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 1.93%   |
| Nvidia TU104 HD Audio Controller                                           | 4         | 1.54%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 1.54%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 1.54%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 1.54%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 1.54%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 1.54%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 1.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 1.16%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 1.16%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 1.16%   |
| Plantronics Blackwire 3225 Series                                          | 2         | 0.77%   |
| Nvidia MCP89 High Definition Audio                                         | 2         | 0.77%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.77%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.77%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 0.77%   |
| Kingston Technology HyperX 7.1 Audio                                       | 2         | 0.77%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 0.77%   |
| Intel Jasper Lake HD Audio                                                 | 2         | 0.77%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 0.77%   |
| Intel CM238 HD Audio Controller                                            | 2         | 0.77%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 0.77%   |
| Apple USB-C to 3.5mm Headphone Jack Adapter                                | 2         | 0.77%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 0.77%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 38        | 29.92%  |
| Samsung Electronics | 33        | 25.98%  |
| Micron Technology   | 18        | 14.17%  |
| Kingston            | 9         | 7.09%   |
| Unknown             | 8         | 6.3%    |
| Crucial             | 7         | 5.51%   |
| Transcend           | 3         | 2.36%   |
| Ramaxel Technology  | 3         | 2.36%   |
| A-DATA Technology   | 3         | 2.36%   |
| Unknown (ABCD)      | 1         | 0.79%   |
| Team                | 1         | 0.79%   |
| Lexar               | 1         | 0.79%   |
| Elpida              | 1         | 0.79%   |
| Corsair             | 1         | 0.79%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 3         | 2.26%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 3         | 2.26%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 3         | 2.26%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 2.26%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s                 | 2         | 1.5%    |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                     | 2         | 1.5%    |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 1.5%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 1.5%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 1.5%    |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 2         | 1.5%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 1.5%    |
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s      | 2         | 1.5%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 1.5%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 2         | 1.5%    |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s                | 2         | 1.5%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 2         | 1.5%    |
| Crucial RAM CT32G4SFD832A.C16FE 32GB SODIMM DDR4 3200MT/s           | 2         | 1.5%    |
| Unknown RAM Module 8GB SODIMM DDR3 800MT/s                          | 1         | 0.75%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s                 | 1         | 0.75%   |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 1         | 0.75%   |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s                    | 1         | 0.75%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                         | 1         | 0.75%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                      | 1         | 0.75%   |
| Unknown RAM Module 1GB SODIMM DDR3 1600MT/s                         | 1         | 0.75%   |
| Unknown RAM Module 16GB Row Of Chips LPDDR4 4267MT/s                | 1         | 0.75%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s    | 1         | 0.75%   |
| Transcend RAM TS1GSK64V3H 8192MB SODIMM DDR3 1333MT/s               | 1         | 0.75%   |
| Transcend RAM JM3200HSB-16G 16GB SODIMM DDR4 3200MT/s               | 1         | 0.75%   |
| Transcend RAM JM1333KSN-2G 2GB SODIMM DDR3 1333MT/s                 | 1         | 0.75%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s               | 1         | 0.75%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                     | 1         | 0.75%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.75%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.75%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.75%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.75%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.75%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 0.75%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB Row Of Chips DDR4 3200MT/s       | 1         | 0.75%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s             | 1         | 0.75%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 1         | 0.75%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 59        | 57.28%  |
| DDR3   | 27        | 26.21%  |
| LPDDR4 | 8         | 7.77%   |
| LPDDR3 | 8         | 7.77%   |
| SDRAM  | 1         | 0.97%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 83        | 80.58%  |
| Row Of Chips | 18        | 17.48%  |
| Chip         | 2         | 1.94%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 49        | 40.83%  |
| 4096  | 35        | 29.17%  |
| 16384 | 24        | 20%     |
| 32768 | 6         | 5%      |
| 2048  | 4         | 3.33%   |
| 1024  | 2         | 1.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 29        | 25.66%  |
| 2667    | 22        | 19.47%  |
| 1600    | 22        | 19.47%  |
| 2400    | 9         | 7.96%   |
| 4267    | 6         | 5.31%   |
| 2133    | 6         | 5.31%   |
| 1334    | 4         | 3.54%   |
| 1333    | 3         | 2.65%   |
| 3266    | 2         | 1.77%   |
| 1867    | 2         | 1.77%   |
| 1067    | 2         | 1.77%   |
| 8400    | 1         | 0.88%   |
| 4800    | 1         | 0.88%   |
| 4199    | 1         | 0.88%   |
| 1200    | 1         | 0.88%   |
| 800     | 1         | 0.88%   |
| Unknown | 1         | 0.88%   |

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
| Chicony Electronics                    | 44        | 27.33%  |
| IMC Networks                           | 26        | 16.15%  |
| Microdia                               | 20        | 12.42%  |
| Realtek Semiconductor                  | 15        | 9.32%   |
| Sunplus Innovation Technology          | 11        | 6.83%   |
| Acer                                   | 9         | 5.59%   |
| Suyin                                  | 6         | 3.73%   |
| Samsung Electronics                    | 5         | 3.11%   |
| Syntek                                 | 4         | 2.48%   |
| Apple                                  | 4         | 2.48%   |
| Logitech                               | 3         | 1.86%   |
| Silicon Motion                         | 2         | 1.24%   |
| Ricoh                                  | 2         | 1.24%   |
| Lite-On Technology                     | 2         | 1.24%   |
| SunplusIT                              | 1         | 0.62%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.62%   |
| Quanta                                 | 1         | 0.62%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.62%   |
| Magic Control Technology               | 1         | 0.62%   |
| Luxvisions Innotech Limited            | 1         | 0.62%   |
| Lenovo                                 | 1         | 0.62%   |
| Intel                                  | 1         | 0.62%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD            | 14        | 8.7%    |
| Chicony Integrated Camera                | 9         | 5.59%   |
| Chicony HD WebCam                        | 9         | 5.59%   |
| IMC Networks USB2.0 HD UVC WebCam        | 7         | 4.35%   |
| IMC Networks Integrated Camera           | 7         | 4.35%   |
| Realtek Integrated_Webcam_HD             | 6         | 3.73%   |
| Sunplus Integrated_Webcam_HD             | 5         | 3.11%   |
| Samsung Galaxy series, misc. (MTP mode)  | 5         | 3.11%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 5         | 3.11%   |
| IMC Networks USB2.0 HD IR UVC WebCam     | 4         | 2.48%   |
| Chicony HP HD Camera                     | 4         | 2.48%   |
| Acer Integrated Camera                   | 4         | 2.48%   |
| Syntek Integrated Camera                 | 3         | 1.86%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 3         | 1.86%   |
| Chicony HP Wide Vision HD Camera         | 3         | 1.86%   |
| Apple FaceTime HD Camera                 | 3         | 1.86%   |
| Realtek Integrated Webcam_HD             | 2         | 1.24%   |
| Realtek Asus 2.0 USB Webcam              | 2         | 1.24%   |
| Microdia Sonix USB 2.0 Camera            | 2         | 1.24%   |
| IMC Networks Lenovo EasyCamera           | 2         | 1.24%   |
| Chicony USB2.0 HD UVC WebCam             | 2         | 1.24%   |
| Chicony USB2.0 Camera                    | 2         | 1.24%   |
| Chicony Integrated Camera [ThinkPad]     | 2         | 1.24%   |
| Chicony HD User Facing                   | 2         | 1.24%   |
| Acer BisonCam, NB Pro                    | 2         | 1.24%   |
| Syntek Lenovo EasyCamera                 | 1         | 0.62%   |
| Suyin UVC HD Webcam                      | 1         | 0.62%   |
| Suyin Laptop_Integrated_Webcam_HD        | 1         | 0.62%   |
| Suyin HD WebCam                          | 1         | 0.62%   |
| Suyin HD Video WebCam                    | 1         | 0.62%   |
| Suyin Asus Integrated Webcam             | 1         | 0.62%   |
| Suyin Acer/Lenovo Webcam [CN0316]        | 1         | 0.62%   |
| SunplusIT XiaoMi USB 2.0 Webcam          | 1         | 0.62%   |
| Sunplus TOSHIBA Web Camera - HD          | 1         | 0.62%   |
| Sunplus Lenovo EasyCamera                | 1         | 0.62%   |
| Sunplus Laptop Integrated Webcam HD      | 1         | 0.62%   |
| Sunplus Integrated Webcam                | 1         | 0.62%   |
| Sunplus HD User Facing                   | 1         | 0.62%   |
| Sunplus FHD Camera Microphone            | 1         | 0.62%   |
| Sony Ericsson Mobile AB XQ-BT52          | 1         | 0.62%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 11        | 22.45%  |
| Validity Sensors           | 9         | 18.37%  |
| Shenzhen Goodix Technology | 6         | 12.24%  |
| LighTuning Technology      | 6         | 12.24%  |
| Elan Microelectronics      | 6         | 12.24%  |
| AuthenTec                  | 6         | 12.24%  |
| Upek                       | 5         | 10.2%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 7         | 14.29%  |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 12.24%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 5         | 10.2%   |
| Elan ELAN:Fingerprint                                                      | 4         | 8.16%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 4.08%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 4.08%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 4.08%   |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 4.08%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 4.08%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 4.08%   |
| Elan ELAN:ARM-M4                                                           | 2         | 4.08%   |
| AuthenTec AES2810                                                          | 2         | 4.08%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 4.08%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 2.04%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.04%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 2.04%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 2.04%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.04%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 2.04%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 2.04%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 2.04%   |
| Unknown                                                                    | 1         | 2.04%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 6         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 58200                                 | 3         | 50%     |
| Broadcom BCM5880 Secure Applications Processor | 2         | 33.33%  |
| Broadcom 5880                                  | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 106       | 56.08%  |
| 1     | 61        | 32.28%  |
| 2     | 19        | 10.05%  |
| 3     | 2         | 1.06%   |
| 5     | 1         | 0.53%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 47        | 43.93%  |
| Graphics card            | 26        | 24.3%   |
| Net/wireless             | 11        | 10.28%  |
| Chipcard                 | 5         | 4.67%   |
| Camera                   | 5         | 4.67%   |
| Multimedia controller    | 4         | 3.74%   |
| Net/ethernet             | 2         | 1.87%   |
| Communication controller | 2         | 1.87%   |
| Wireless                 | 1         | 0.93%   |
| Storage/raid             | 1         | 0.93%   |
| Sound                    | 1         | 0.93%   |
| Firewire controller      | 1         | 0.93%   |
| Bluetooth                | 1         | 0.93%   |


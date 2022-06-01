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

Total: 349

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 68        | 26.46%  |
| Ubuntu 18.04                 | 34        | 13.23%  |
| Fedora 33                    | 12        | 4.67%   |
| Pop!_OS 20.04                | 8         | 3.11%   |
| Arch                         | 8         | 3.11%   |
| Arch Rolling                 | 7         | 2.72%   |
| Debian 11                    | 6         | 2.33%   |
| Ubuntu 21.10                 | 5         | 1.95%   |
| Ubuntu 21.04                 | 5         | 1.95%   |
| Linux Mint 20                | 5         | 1.95%   |
| Xubuntu 20.04                | 4         | 1.56%   |
| Pop!_OS 21.04                | 4         | 1.56%   |
| OpenMandriva 4.3             | 3         | 1.17%   |
| KDE neon 20.04               | 3         | 1.17%   |
| Fedora 34                    | 3         | 1.17%   |
| Fedora 32                    | 3         | 1.17%   |
| ArcoLinux Rolling            | 3         | 1.17%   |
| Zorin 16                     | 2         | 0.78%   |
| Zorin 15                     | 2         | 0.78%   |
| Ubuntu 22.04                 | 2         | 0.78%   |
| Ubuntu 19.10                 | 2         | 0.78%   |
| Ubuntu 19.04                 | 2         | 0.78%   |
| Ubuntu 18.10                 | 2         | 0.78%   |
| Ubuntu 16.04                 | 2         | 0.78%   |
| Rocky Linux 8.5              | 2         | 0.78%   |
| Raspbian 10                  | 2         | 0.78%   |
| Pop!_OS 21.10                | 2         | 0.78%   |
| Pop!_OS 20.10                | 2         | 0.78%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.78%   |
| OpenMandriva 4.50            | 2         | 0.78%   |
| OpenMandriva 4.2             | 2         | 0.78%   |
| Manjaro 20.2                 | 2         | 0.78%   |
| Manjaro 20.1                 | 2         | 0.78%   |
| Manjaro                      | 2         | 0.78%   |
| Lubuntu 20.04                | 2         | 0.78%   |
| Kubuntu 20.10                | 2         | 0.78%   |
| Gentoo 2.6                   | 2         | 0.78%   |
| Fedora 35                    | 2         | 0.78%   |
| Fedora 31                    | 2         | 0.78%   |
| Xubuntu 21.04                | 1         | 0.39%   |
| Ubuntu MATE 20.04            | 1         | 0.39%   |
| Ubuntu Budgie 20.04          | 1         | 0.39%   |
| ROSA R8                      | 1         | 0.39%   |
| ROSA R11                     | 1         | 0.39%   |
| Rocky Linux 8.4              | 1         | 0.39%   |
| RHEL 8                       | 1         | 0.39%   |
| RHEL 7                       | 1         | 0.39%   |
| Q4OS 4                       | 1         | 0.39%   |
| Pop!_OS 22.04                | 1         | 0.39%   |
| OpenMandriva 4.1             | 1         | 0.39%   |
| Manjaro 18.0.4               | 1         | 0.39%   |
| Lubuntu 18.04                | 1         | 0.39%   |
| LMDE 4                       | 1         | 0.39%   |
| Linux Mint 20.3              | 1         | 0.39%   |
| Linux Mint 20.1              | 1         | 0.39%   |
| Linux Mint 19.3              | 1         | 0.39%   |
| Kubuntu 20.04                | 1         | 0.39%   |
| Kali 2020.3                  | 1         | 0.39%   |
| Garuda Linux Soaring         | 1         | 0.39%   |
| Fedora 36                    | 1         | 0.39%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 121       | 48.59%  |
| Fedora        | 20        | 8.03%   |
| Pop!_OS       | 17        | 6.83%   |
| Arch          | 14        | 5.62%   |
| Debian        | 9         | 3.61%   |
| OpenMandriva  | 8         | 3.21%   |
| Manjaro       | 6         | 2.41%   |
| Linux Mint    | 6         | 2.41%   |
| Xubuntu       | 5         | 2.01%   |
| Zorin         | 4         | 1.61%   |
| Rocky Linux   | 3         | 1.2%    |
| Lubuntu       | 3         | 1.2%    |
| Kubuntu       | 3         | 1.2%    |
| KDE neon      | 3         | 1.2%    |
| ArcoLinux     | 3         | 1.2%    |
| ROSA          | 2         | 0.8%    |
| RHEL          | 2         | 0.8%    |
| Raspbian      | 2         | 0.8%    |
| openSUSE      | 2         | 0.8%    |
| Gentoo        | 2         | 0.8%    |
| Endless       | 2         | 0.8%    |
| Clear Linux   | 2         | 0.8%    |
| Ubuntu MATE   | 1         | 0.4%    |
| Ubuntu Budgie | 1         | 0.4%    |
| Q4OS          | 1         | 0.4%    |
| LMDE          | 1         | 0.4%    |
| Kali          | 1         | 0.4%    |
| Garuda Linux  | 1         | 0.4%    |
| EndeavourOS   | 1         | 0.4%    |
| Devuan        | 1         | 0.4%    |
| Deepin        | 1         | 0.4%    |
| CentOS        | 1         | 0.4%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 5.9.8-200.fc33.x86_64        | 6         | 2.12%   |
| 5.4.0-48-generic             | 6         | 2.12%   |
| 5.4.0-42-generic             | 6         | 2.12%   |
| 5.4.0-40-generic             | 6         | 2.12%   |
| 5.4.0-37-generic             | 6         | 2.12%   |
| 5.4.0-29-generic             | 6         | 2.12%   |
| 5.4.0-52-generic             | 5         | 1.77%   |
| 5.11.0-43-generic            | 5         | 1.77%   |
| 5.4.0-65-generic             | 4         | 1.41%   |
| 5.3.0-62-generic             | 4         | 1.41%   |
| 5.4.0-7634-generic           | 3         | 1.06%   |
| 5.4.0-47-generic             | 3         | 1.06%   |
| 5.4.0-26-generic             | 3         | 1.06%   |
| 5.3.0-51-generic             | 3         | 1.06%   |
| 5.16.7-desktop-1omv4003      | 3         | 1.06%   |
| 5.13.0-40-generic            | 3         | 1.06%   |
| 5.13.0-28-generic            | 3         | 1.06%   |
| 5.11.0-38-generic            | 3         | 1.06%   |
| 5.11.0-37-generic            | 3         | 1.06%   |
| 5.11.0-25-generic            | 3         | 1.06%   |
| 5.10.0-11-amd64              | 3         | 1.06%   |
| 5.0.0-23-generic             | 3         | 1.06%   |
| 5.8.0-7630-generic           | 2         | 0.71%   |
| 5.8.0-53-generic             | 2         | 0.71%   |
| 5.8.0-48-generic             | 2         | 0.71%   |
| 5.8.0-43-generic             | 2         | 0.71%   |
| 5.4.51-v7l+                  | 2         | 0.71%   |
| 5.4.5-050405-generic         | 2         | 0.71%   |
| 5.4.0-96-generic             | 2         | 0.71%   |
| 5.4.0-81-generic             | 2         | 0.71%   |
| 5.4.0-7642-generic           | 2         | 0.71%   |
| 5.4.0-70-generic             | 2         | 0.71%   |
| 5.4.0-45-generic             | 2         | 0.71%   |
| 5.4.0-33-generic             | 2         | 0.71%   |
| 5.4.0-31-generic             | 2         | 0.71%   |
| 5.3.0-40-generic             | 2         | 0.71%   |
| 5.13.13-xanmod1              | 2         | 0.71%   |
| 5.13.0-37-generic            | 2         | 0.71%   |
| 5.13.0-30-generic            | 2         | 0.71%   |
| 5.13.0-19-generic            | 2         | 0.71%   |
| 5.12.7-desktop-1omv4003      | 2         | 0.71%   |
| 5.11.0-27-generic            | 2         | 0.71%   |
| 5.10.14-desktop-1omv4002     | 2         | 0.71%   |
| 5.0.0-36-generic             | 2         | 0.71%   |
| 5.0.0-15-generic             | 2         | 0.71%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 2         | 0.71%   |
| 4.18.0-15-generic            | 2         | 0.71%   |
| 4.15.0-72-generic            | 2         | 0.71%   |
| 5.9.9-200.fc33.x86_64        | 1         | 0.35%   |
| 5.9.16-200.fc33.x86_64       | 1         | 0.35%   |
| 5.9.15-200.fc33.x86_64       | 1         | 0.35%   |
| 5.9.11-3-MANJARO             | 1         | 0.35%   |
| 5.9.10-arch1-1               | 1         | 0.35%   |
| 5.8.7-1-default              | 1         | 0.35%   |
| 5.8.5-arch1-1                | 1         | 0.35%   |
| 5.8.4-1-default              | 1         | 0.35%   |
| 5.8.3-arch1-1                | 1         | 0.35%   |
| 5.8.18-1-MANJARO             | 1         | 0.35%   |
| 5.8.12-200.fc32.x86_64       | 1         | 0.35%   |
| 5.8.11-200.fc32.x86_64       | 1         | 0.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 66        | 24.54%  |
| 5.11.0  | 21        | 7.81%   |
| 5.8.0   | 16        | 5.95%   |
| 5.13.0  | 16        | 5.95%   |
| 4.18.0  | 13        | 4.83%   |
| 5.3.0   | 12        | 4.46%   |
| 5.0.0   | 11        | 4.09%   |
| 4.15.0  | 10        | 3.72%   |
| 5.10.0  | 8         | 2.97%   |
| 5.9.8   | 6         | 2.23%   |
| 5.16.7  | 3         | 1.12%   |
| 5.13.13 | 3         | 1.12%   |
| 5.4.51  | 2         | 0.74%   |
| 5.4.5   | 2         | 0.74%   |
| 5.15.5  | 2         | 0.74%   |
| 5.15.0  | 2         | 0.74%   |
| 5.13.12 | 2         | 0.74%   |
| 5.12.7  | 2         | 0.74%   |
| 5.10.14 | 2         | 0.74%   |
| 4.19.0  | 2         | 0.74%   |
| 3.10.0  | 2         | 0.74%   |
| 5.9.9   | 1         | 0.37%   |
| 5.9.16  | 1         | 0.37%   |
| 5.9.15  | 1         | 0.37%   |
| 5.9.11  | 1         | 0.37%   |
| 5.9.10  | 1         | 0.37%   |
| 5.8.7   | 1         | 0.37%   |
| 5.8.5   | 1         | 0.37%   |
| 5.8.4   | 1         | 0.37%   |
| 5.8.3   | 1         | 0.37%   |
| 5.8.18  | 1         | 0.37%   |
| 5.8.12  | 1         | 0.37%   |
| 5.8.11  | 1         | 0.37%   |
| 5.8.1   | 1         | 0.37%   |
| 5.7.0   | 1         | 0.37%   |
| 5.6.7   | 1         | 0.37%   |
| 5.6.5   | 1         | 0.37%   |
| 5.6.15  | 1         | 0.37%   |
| 5.6.0   | 1         | 0.37%   |
| 5.5.2   | 1         | 0.37%   |
| 5.5.0   | 1         | 0.37%   |
| 5.4.8   | 1         | 0.37%   |
| 5.4.78  | 1         | 0.37%   |
| 5.4.77  | 1         | 0.37%   |
| 5.4.70  | 1         | 0.37%   |
| 5.4.60  | 1         | 0.37%   |
| 5.4.12  | 1         | 0.37%   |
| 5.17.9  | 1         | 0.37%   |
| 5.17.6  | 1         | 0.37%   |
| 5.17.5  | 1         | 0.37%   |
| 5.16.9  | 1         | 0.37%   |
| 5.16.8  | 1         | 0.37%   |
| 5.16.18 | 1         | 0.37%   |
| 5.16.15 | 1         | 0.37%   |
| 5.16.11 | 1         | 0.37%   |
| 5.16.0  | 1         | 0.37%   |
| 5.15.8  | 1         | 0.37%   |
| 5.15.7  | 1         | 0.37%   |
| 5.15.6  | 1         | 0.37%   |
| 5.15.32 | 1         | 0.37%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 75        | 28.09%  |
| 5.8     | 24        | 8.99%   |
| 5.13    | 24        | 8.99%   |
| 5.11    | 23        | 8.61%   |
| 5.10    | 17        | 6.37%   |
| 4.18    | 13        | 4.87%   |
| 5.3     | 12        | 4.49%   |
| 5.0     | 12        | 4.49%   |
| 5.15    | 11        | 4.12%   |
| 5.9     | 10        | 3.75%   |
| 4.15    | 10        | 3.75%   |
| 5.16    | 9         | 3.37%   |
| 5.12    | 6         | 2.25%   |
| 5.6     | 4         | 1.5%    |
| 5.17    | 3         | 1.12%   |
| 5.14    | 3         | 1.12%   |
| 4.19    | 3         | 1.12%   |
| 5.5     | 2         | 0.75%   |
| 4.16    | 2         | 0.75%   |
| 3.10    | 2         | 0.75%   |
| 5.7     | 1         | 0.37%   |
| 4.4     | 1         | 0.37%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 235       | 97.11%  |
| aarch64 | 3         | 1.24%   |
| i686    | 2         | 0.83%   |
| armv7l  | 2         | 0.83%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 145       | 57.31%  |
| Unknown         | 38        | 15.02%  |
| KDE5            | 26        | 10.28%  |
| X-Cinnamon      | 9         | 3.56%   |
| XFCE            | 7         | 2.77%   |
| KDE             | 6         | 2.37%   |
| Cinnamon        | 5         | 1.98%   |
| LXQt            | 4         | 1.58%   |
| Unity           | 3         | 1.19%   |
| i3              | 3         | 1.19%   |
| GNOME Classic   | 2         | 0.79%   |
| Budgie          | 2         | 0.79%   |
| MATE            | 1         | 0.4%    |
| KDE4            | 1         | 0.4%    |
| GNOME Flashback | 1         | 0.4%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 194       | 78.23%  |
| Wayland | 24        | 9.68%   |
| Unknown | 20        | 8.06%   |
| Tty     | 10        | 4.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 141       | 56.63%  |
| GDM     | 55        | 22.09%  |
| SDDM    | 27        | 10.84%  |
| GDM3    | 12        | 4.82%   |
| LightDM | 8         | 3.21%   |
| TDM     | 5         | 2.01%   |
| KDM     | 1         | 0.4%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_SG   | 98        | 39.84%  |
| en_US   | 93        | 37.8%   |
| Unknown | 22        | 8.94%   |
| C       | 7         | 2.85%   |
| zh_CN   | 5         | 2.03%   |
| de_DE   | 5         | 2.03%   |
| en_IN   | 4         | 1.63%   |
| en_GB   | 4         | 1.63%   |
| en_AU   | 4         | 1.63%   |
| ru_UA   | 1         | 0.41%   |
| fr_FR   | 1         | 0.41%   |
| en_PH   | 1         | 0.41%   |
| en_IE   | 1         | 0.41%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 158       | 65.02%  |
| BIOS | 85        | 34.98%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 200       | 81.63%  |
| Btrfs   | 17        | 6.94%   |
| Unknown | 10        | 4.08%   |
| Overlay | 9         | 3.67%   |
| Xfs     | 7         | 2.86%   |
| Zfs     | 2         | 0.82%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 142       | 58.2%   |
| GPT     | 93        | 38.11%  |
| MBR     | 9         | 3.69%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 217       | 87.85%  |
| Yes       | 30        | 12.15%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 165       | 67.9%   |
| Yes       | 78        | 32.1%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 48        | 19.83%  |
| Dell                    | 45        | 18.6%   |
| ASUSTek Computer        | 41        | 16.94%  |
| Acer                    | 19        | 7.85%   |
| Hewlett-Packard         | 16        | 6.61%   |
| Gigabyte Technology     | 11        | 4.55%   |
| MSI                     | 10        | 4.13%   |
| ASRock                  | 9         | 3.72%   |
| Apple                   | 9         | 3.72%   |
| Raspberry Pi Foundation | 4         | 1.65%   |
| Intel                   | 4         | 1.65%   |
| Microsoft               | 3         | 1.24%   |
| Toshiba                 | 2         | 0.83%   |
| Sony                    | 2         | 0.83%   |
| Samsung Electronics     | 2         | 0.83%   |
| Foxconn                 | 2         | 0.83%   |
| AMI                     | 2         | 0.83%   |
| Aftershock              | 2         | 0.83%   |
| Razer                   | 1         | 0.41%   |
| Notebook                | 1         | 0.41%   |
| MECHREVO                | 1         | 0.41%   |
| LattePanda              | 1         | 0.41%   |
| INET                    | 1         | 0.41%   |
| Fujitsu                 | 1         | 0.41%   |
| ECS                     | 1         | 0.41%   |
| COPELION INTERNATIONAL  | 1         | 0.41%   |
| congatec                | 1         | 0.41%   |
| Biostar                 | 1         | 0.41%   |
| Unknown                 | 1         | 0.41%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Gigabyte X570 AORUS PRO WIFI                          | 3         | 1.24%   |
| ASUS All Series                                       | 3         | 1.24%   |
| RPi Raspberry Pi 4 Model B Rev 1.4                    | 2         | 0.83%   |
| RPi Raspberry Pi 4 Model B Rev 1.2                    | 2         | 0.83%   |
| MSI MS-7C84                                           | 2         | 0.83%   |
| Lenovo ThinkPad X220 42911H8                          | 2         | 0.83%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ                      | 2         | 0.83%   |
| Lenovo IdeaPad S340-14API 81NB                        | 2         | 0.83%   |
| Intel NUC11PAHi7                                      | 2         | 0.83%   |
| HP Compaq 6510b                                       | 2         | 0.83%   |
| Gigabyte B550I AORUS PRO AX                           | 2         | 0.83%   |
| Foxconn Kangaroo Mobile Desktop                       | 2         | 0.83%   |
| Dell OptiPlex 990                                     | 2         | 0.83%   |
| Dell OptiPlex 9020                                    | 2         | 0.83%   |
| ASUS T300LA                                           | 2         | 0.83%   |
| Acer ConceptD CN715-71                                | 2         | 0.83%   |
| Toshiba PORTEGE Z10t-A                                | 1         | 0.41%   |
| Toshiba PORTEGE R930                                  | 1         | 0.41%   |
| Sony VPCSB36FG                                        | 1         | 0.41%   |
| Sony VGN-CR32G_W                                      | 1         | 0.41%   |
| Samsung RF510/RF410/RF710                             | 1         | 0.41%   |
| Samsung 305U1A                                        | 1         | 0.41%   |
| Razer Blade 15 Advanced Model (Early 2020) - RZ09-033 | 1         | 0.41%   |
| Notebook P65_P67SE                                    | 1         | 0.41%   |
| MSI MS-7D30                                           | 1         | 0.41%   |
| MSI MS-7C52                                           | 1         | 0.41%   |
| MSI MS-7C02                                           | 1         | 0.41%   |
| MSI MS-7A94                                           | 1         | 0.41%   |
| MSI MS-7A32                                           | 1         | 0.41%   |
| MSI MS-7721                                           | 1         | 0.41%   |
| MSI KT308AA-AB4 SR5472CF                              | 1         | 0.41%   |
| MSI GE63VR 7RE                                        | 1         | 0.41%   |
| Microsoft Surface Pro 4                               | 1         | 0.41%   |
| Microsoft Surface Pro                                 | 1         | 0.41%   |
| Microsoft Surface Laptop 3                            | 1         | 0.41%   |
| MECHREVO Code 01 Series PF5NU1G                       | 1         | 0.41%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS                    | 1         | 0.41%   |
| Lenovo Yoga 3 Pro-1370 80HE                           | 1         | 0.41%   |
| Lenovo Yoga 3 14 80JH                                 | 1         | 0.41%   |
| Lenovo ThinkStation P620 30E1S3VH00                   | 1         | 0.41%   |
| Lenovo ThinkStation P310 30ASS2WG00                   | 1         | 0.41%   |
| Lenovo ThinkPad X395 20NL000TCD                       | 1         | 0.41%   |
| Lenovo ThinkPad X240 20AMS00100                       | 1         | 0.41%   |
| Lenovo ThinkPad X230 23257VA                          | 1         | 0.41%   |
| Lenovo ThinkPad X220 Tablet 4298WBT                   | 1         | 0.41%   |
| Lenovo ThinkPad X220 4286C11                          | 1         | 0.41%   |
| Lenovo ThinkPad X1 Yoga 4th 20SBS03N00                | 1         | 0.41%   |
| Lenovo ThinkPad X1 Tablet Gen 3 20KJCTO1WW            | 1         | 0.41%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QVCTO1WW             | 1         | 0.41%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9005TSG            | 1         | 0.41%   |
| Lenovo ThinkPad X1 Carbon 6th EX480SIT13              | 1         | 0.41%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGCTO1WW              | 1         | 0.41%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRCTO1WW              | 1         | 0.41%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQCTO1WW              | 1         | 0.41%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A8S0WE01              | 1         | 0.41%   |
| Lenovo ThinkPad W540 20BG001KUK                       | 1         | 0.41%   |
| Lenovo ThinkPad T490 20N3S5DU27                       | 1         | 0.41%   |
| Lenovo ThinkPad T420s 417429U                         | 1         | 0.41%   |
| Lenovo ThinkPad T400 2768CJ6                          | 1         | 0.41%   |
| Lenovo ThinkPad T400 2768AA6                          | 1         | 0.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 26        | 10.74%  |
| Dell Inspiron       | 12        | 4.96%   |
| Dell OptiPlex       | 9         | 3.72%   |
| Dell XPS            | 8         | 3.31%   |
| Dell Latitude       | 8         | 3.31%   |
| Acer Aspire         | 7         | 2.89%   |
| Lenovo IdeaPad      | 6         | 2.48%   |
| Acer Swift          | 6         | 2.48%   |
| HP Pavilion         | 5         | 2.07%   |
| Dell Precision      | 5         | 2.07%   |
| ASUS VivoBook       | 5         | 2.07%   |
| RPi Raspberry       | 4         | 1.65%   |
| ASUS ZenBook        | 4         | 1.65%   |
| Microsoft Surface   | 3         | 1.24%   |
| Lenovo Yoga         | 3         | 1.24%   |
| Lenovo ThinkCentre  | 3         | 1.24%   |
| Lenovo Legion       | 3         | 1.24%   |
| Gigabyte X570       | 3         | 1.24%   |
| ASUS ROG            | 3         | 1.24%   |
| ASUS All            | 3         | 1.24%   |
| Toshiba PORTEGE     | 2         | 0.83%   |
| MSI MS-7C84         | 2         | 0.83%   |
| Lenovo ThinkStation | 2         | 0.83%   |
| Intel NUC11PAHi7    | 2         | 0.83%   |
| HP ENVY             | 2         | 0.83%   |
| HP EliteBook        | 2         | 0.83%   |
| HP Compaq           | 2         | 0.83%   |
| Gigabyte B550I      | 2         | 0.83%   |
| Foxconn Kangaroo    | 2         | 0.83%   |
| ASUS TUF            | 2         | 0.83%   |
| ASUS T300LA         | 2         | 0.83%   |
| Apple MacBookPro11  | 2         | 0.83%   |
| Acer Predator       | 2         | 0.83%   |
| Acer ConceptD       | 2         | 0.83%   |
| Sony VPCSB36FG      | 1         | 0.41%   |
| Sony VGN-CR32G      | 1         | 0.41%   |
| Samsung RF510       | 1         | 0.41%   |
| Samsung 305U1A      | 1         | 0.41%   |
| Razer Blade         | 1         | 0.41%   |
| Notebook P65        | 1         | 0.41%   |
| MSI MS-7D30         | 1         | 0.41%   |
| MSI MS-7C52         | 1         | 0.41%   |
| MSI MS-7C02         | 1         | 0.41%   |
| MSI MS-7A94         | 1         | 0.41%   |
| MSI MS-7A32         | 1         | 0.41%   |
| MSI MS-7721         | 1         | 0.41%   |
| MSI KT308AA-AB4     | 1         | 0.41%   |
| MSI GE63VR          | 1         | 0.41%   |
| MECHREVO Code       | 1         | 0.41%   |
| Lenovo ThinkBook    | 1         | 0.41%   |
| Lenovo S20-30       | 1         | 0.41%   |
| Lenovo G550         | 1         | 0.41%   |
| Lenovo B50-30       | 1         | 0.41%   |
| Lenovo 14w          | 1         | 0.41%   |
| LattePanda Alpha    | 1         | 0.41%   |
| Intel NUC11PAHi5    | 1         | 0.41%   |
| Intel NUC10i7FNH    | 1         | 0.41%   |
| INET HeroBox        | 1         | 0.41%   |
| HP ZBook            | 1         | 0.41%   |
| HP Z6               | 1         | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 36        | 14.88%  |
| 2020    | 32        | 13.22%  |
| 2018    | 31        | 12.81%  |
| 2011    | 17        | 7.02%   |
| 2021    | 16        | 6.61%   |
| 2014    | 16        | 6.61%   |
| 2016    | 14        | 5.79%   |
| 2015    | 14        | 5.79%   |
| 2017    | 13        | 5.37%   |
| 2013    | 12        | 4.96%   |
| 2012    | 12        | 4.96%   |
| 2010    | 10        | 4.13%   |
| 2008    | 6         | 2.48%   |
| 2007    | 6         | 2.48%   |
| Unknown | 4         | 1.65%   |
| 2009    | 3         | 1.24%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 144       | 59.5%   |
| Desktop        | 71        | 29.34%  |
| Convertible    | 6         | 2.48%   |
| Mini pc        | 6         | 2.48%   |
| System on chip | 5         | 2.07%   |
| Tablet         | 4         | 1.65%   |
| All in one     | 4         | 1.65%   |
| Server         | 2         | 0.83%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 215       | 88.48%  |
| Enabled  | 28        | 11.52%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 242       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 67        | 27.35%  |
| 4.01-8.0        | 53        | 21.63%  |
| 8.01-16.0       | 43        | 17.55%  |
| 3.01-4.0        | 32        | 13.06%  |
| 32.01-64.0      | 27        | 11.02%  |
| 1.01-2.0        | 8         | 3.27%   |
| 24.01-32.0      | 7         | 2.86%   |
| 64.01-256.0     | 5         | 2.04%   |
| 2.01-3.0        | 2         | 0.82%   |
| More than 256.0 | 1         | 0.41%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 78        | 29.1%   |
| 2.01-3.0   | 65        | 24.25%  |
| 4.01-8.0   | 46        | 17.16%  |
| 3.01-4.0   | 44        | 16.42%  |
| 8.01-16.0  | 15        | 5.6%    |
| 0.51-1.0   | 15        | 5.6%    |
| 0.01-0.5   | 4         | 1.49%   |
| 16.01-24.0 | 1         | 0.37%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 154       | 62.6%   |
| 2      | 59        | 23.98%  |
| 3      | 19        | 7.72%   |
| 4      | 9         | 3.66%   |
| 0      | 3         | 1.22%   |
| 5      | 2         | 0.81%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 183       | 75.62%  |
| Yes       | 59        | 24.38%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 179       | 73.97%  |
| No        | 63        | 26.03%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 196       | 80.66%  |
| No        | 47        | 19.34%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 162       | 66.67%  |
| No        | 81        | 33.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Singapore | 242       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Singapore          | 231       | 95.45%  |
| Jurong West        | 7         | 2.89%   |
| Queenstown Estate  | 2         | 0.83%   |
| Sembawang Estate   | 1         | 0.41%   |
| Kampong Ulu Jurong | 1         | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 71        | 101    | 20.76%  |
| Seagate                   | 44        | 51     | 12.87%  |
| WDC                       | 35        | 62     | 10.23%  |
| Toshiba                   | 28        | 32     | 8.19%   |
| SanDisk                   | 21        | 23     | 6.14%   |
| Unknown                   | 18        | 20     | 5.26%   |
| SK Hynix                  | 16        | 16     | 4.68%   |
| Hitachi                   | 12        | 13     | 3.51%   |
| Intel                     | 10        | 12     | 2.92%   |
| HGST                      | 10        | 17     | 2.92%   |
| Kingston                  | 8         | 11     | 2.34%   |
| Phison                    | 5         | 6      | 1.46%   |
| Micron Technology         | 5         | 7      | 1.46%   |
| JMicron                   | 5         | 6      | 1.46%   |
| Hewlett-Packard           | 5         | 6      | 1.46%   |
| Crucial                   | 5         | 6      | 1.46%   |
| Apple                     | 4         | 4      | 1.17%   |
| Lexar                     | 3         | 3      | 0.88%   |
| Lenovo                    | 3         | 3      | 0.88%   |
| A-DATA Technology         | 3         | 3      | 0.88%   |
| OCZ                       | 2         | 2      | 0.58%   |
| LITEON                    | 2         | 3      | 0.58%   |
| KLEVV                     | 2         | 2      | 0.58%   |
| KIOXIA                    | 2         | 2      | 0.58%   |
| China                     | 2         | 2      | 0.58%   |
| Vaseky                    | 1         | 1      | 0.29%   |
| USB30                     | 1         | 1      | 0.29%   |
| UMIS                      | 1         | 1      | 0.29%   |
| TO Exter                  | 1         | 1      | 0.29%   |
| SPCC                      | 1         | 1      | 0.29%   |
| Silicon Motion            | 1         | 2      | 0.29%   |
| PLEXTOR                   | 1         | 1      | 0.29%   |
| Pioneer                   | 1         | 1      | 0.29%   |
| Netac                     | 1         | 1      | 0.29%   |
| MidasForce                | 1         | 1      | 0.29%   |
| Micron/Crucial Technology | 1         | 1      | 0.29%   |
| KESU                      | 1         | 1      | 0.29%   |
| INTEL SS                  | 1         | 1      | 0.29%   |
| GAMER                     | 1         | 1      | 0.29%   |
| Fujitsu                   | 1         | 1      | 0.29%   |
| External                  | 1         | 1      | 0.29%   |
| DREVO                     | 1         | 1      | 0.29%   |
| CT1000MX                  | 1         | 2      | 0.29%   |
| Corsair                   | 1         | 2      | 0.29%   |
| Apacer                    | 1         | 1      | 0.29%   |
| Unknown                   | 1         | 1      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Toshiba DT01ACA100 1TB               | 7         | 1.92%   |
| Seagate ST1000LM035-1RK172 1TB       | 7         | 1.92%   |
| Unknown MMC Card  32GB               | 5         | 1.37%   |
| Samsung SSD 860 EVO 500GB            | 4         | 1.1%    |
| Samsung SSD 850 EVO 250GB            | 4         | 1.1%    |
| Samsung NVMe SSD Drive 1024GB        | 4         | 1.1%    |
| JMicron Generic 128GB                | 4         | 1.1%    |
| Unknown MMC Card  64GB               | 3         | 0.82%   |
| Seagate ST1000DM010-2EP102 1TB       | 3         | 0.82%   |
| Sandisk NVMe SSD Drive 512GB         | 3         | 0.82%   |
| Samsung SSD 970 EVO Plus 500GB       | 3         | 0.82%   |
| Samsung SSD 850 EVO 500GB            | 3         | 0.82%   |
| Samsung SSD 840 EVO 250GB            | 3         | 0.82%   |
| Samsung NVMe SSD Drive 500GB         | 3         | 0.82%   |
| Samsung NVMe SSD Drive 256GB         | 3         | 0.82%   |
| HGST HTS545050A7E380 500GB           | 3         | 0.82%   |
| WDC WDS500G2X0C-00L350 500GB         | 2         | 0.55%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 2         | 0.55%   |
| WDC WDS100T2X0C-00L350 1TB           | 2         | 0.55%   |
| WDC WD6400AAKS-22A7B2 640GB          | 2         | 0.55%   |
| WDC PC SN720 SED SDAQNTW-1T00 1TB    | 2         | 0.55%   |
| Toshiba MQ04ABF100 1TB               | 2         | 0.55%   |
| Toshiba MQ01ABD100 1TB               | 2         | 0.55%   |
| Toshiba MK5055GSX 500GB              | 2         | 0.55%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD  | 2         | 0.55%   |
| Toshiba DT01ACA200 2TB               | 2         | 0.55%   |
| SK Hynix SKHynix_HFS001TDE9X084N 1TB | 2         | 0.55%   |
| SK Hynix SC311 SATA 128GB SSD        | 2         | 0.55%   |
| SK Hynix NVMe SSD Drive 256GB        | 2         | 0.55%   |
| SK Hynix HFM512GDJTNG-8310A 512GB    | 2         | 0.55%   |
| Seagate ST1000LM049-2GH172 1TB       | 2         | 0.55%   |
| Seagate BUP Portable 5TB             | 2         | 0.55%   |
| SanDisk SSD PLUS 240GB               | 2         | 0.55%   |
| SanDisk SSD PLUS 120 GB              | 2         | 0.55%   |
| SanDisk SD6SN1M128G1002 128GB SSD    | 2         | 0.55%   |
| Sandisk NVMe SSD Drive 1TB           | 2         | 0.55%   |
| Samsung SSD 860 EVO 250GB            | 2         | 0.55%   |
| Samsung SSD 860 EVO 1TB              | 2         | 0.55%   |
| Samsung SSD 850 EVO M.2 250GB        | 2         | 0.55%   |
| Samsung SSD 850 EVO 1TB              | 2         | 0.55%   |
| Samsung NVMe SSD Drive 512GB         | 2         | 0.55%   |
| Samsung NVMe SSD Drive 2TB           | 2         | 0.55%   |
| Samsung NVMe SSD Drive 250GB         | 2         | 0.55%   |
| Samsung MZVLB1T0HBLR-000L7 1TB       | 2         | 0.55%   |
| Intel NVMe SSD Drive 512GB           | 2         | 0.55%   |
| Intel NVMe SSD Drive 1024GB          | 2         | 0.55%   |
| Hitachi HTS545050A7E380 500GB        | 2         | 0.55%   |
| HGST HTS725050A7E630 500GB           | 2         | 0.55%   |
| HGST HTS721010A9E630 1TB             | 2         | 0.55%   |
| HP SSD S700 250GB                    | 2         | 0.55%   |
| Crucial CT500MX500SSD1 500GB         | 2         | 0.55%   |
| A-DATA HC660 1TB SSD                 | 2         | 0.55%   |
| WDC WDS500G3X0C-00SJG0 500GB         | 1         | 0.27%   |
| WDC WDS500G2B0C-00PXH0 500GB         | 1         | 0.27%   |
| WDC WDS500G1X0E-00AFY0 500GB         | 1         | 0.27%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD     | 1         | 0.27%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 1         | 0.27%   |
| WDC WDS100T2B0B-00YS70 1TB SSD       | 1         | 0.27%   |
| WDC WD800JD-08MSA1 80GB              | 1         | 0.27%   |
| WDC WD7500BPVT-80HXZT3 752GB         | 1         | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 42        | 49     | 38.18%  |
| WDC                 | 22        | 30     | 20%     |
| Toshiba             | 19        | 23     | 17.27%  |
| Hitachi             | 12        | 13     | 10.91%  |
| HGST                | 10        | 17     | 9.09%   |
| Samsung Electronics | 2         | 4      | 1.82%   |
| KESU                | 1         | 1      | 0.91%   |
| Fujitsu             | 1         | 1      | 0.91%   |
| Apple               | 1         | 1      | 0.91%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 41        | 57     | 36.61%  |
| SanDisk             | 13        | 13     | 11.61%  |
| Kingston            | 7         | 10     | 6.25%   |
| WDC                 | 4         | 5      | 3.57%   |
| SK Hynix            | 4         | 4      | 3.57%   |
| JMicron             | 4         | 5      | 3.57%   |
| Hewlett-Packard     | 4         | 5      | 3.57%   |
| Crucial             | 4         | 5      | 3.57%   |
| Micron Technology   | 3         | 5      | 2.68%   |
| Apple               | 3         | 3      | 2.68%   |
| OCZ                 | 2         | 2      | 1.79%   |
| LITEON              | 2         | 3      | 1.79%   |
| Lexar               | 2         | 2      | 1.79%   |
| China               | 2         | 2      | 1.79%   |
| A-DATA Technology   | 2         | 2      | 1.79%   |
| Vaseky              | 1         | 1      | 0.89%   |
| USB30               | 1         | 1      | 0.89%   |
| Toshiba             | 1         | 1      | 0.89%   |
| TO Exter            | 1         | 1      | 0.89%   |
| SPCC                | 1         | 1      | 0.89%   |
| PLEXTOR             | 1         | 1      | 0.89%   |
| Pioneer             | 1         | 1      | 0.89%   |
| Netac               | 1         | 1      | 0.89%   |
| MidasForce          | 1         | 1      | 0.89%   |
| KLEVV               | 1         | 1      | 0.89%   |
| INTEL SS            | 1         | 1      | 0.89%   |
| Intel               | 1         | 1      | 0.89%   |
| External            | 1         | 1      | 0.89%   |
| CT1000MX            | 1         | 2      | 0.89%   |
| Apacer              | 1         | 1      | 0.89%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 100       | 139    | 31.45%  |
| NVMe    | 99        | 136    | 31.13%  |
| SSD     | 98        | 139    | 30.82%  |
| MMC     | 16        | 18     | 5.03%   |
| Unknown | 5         | 5      | 1.57%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 156       | 261    | 53.61%  |
| NVMe | 99        | 136    | 34.02%  |
| SAS  | 20        | 22     | 6.87%   |
| MMC  | 16        | 18     | 5.5%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 111       | 161    | 55.22%  |
| 0.51-1.0   | 61        | 82     | 30.35%  |
| 1.01-2.0   | 13        | 16     | 6.47%   |
| 4.01-10.0  | 7         | 9      | 3.48%   |
| 3.01-4.0   | 6         | 7      | 2.99%   |
| 2.01-3.0   | 3         | 3      | 1.49%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 61        | 23.92%  |
| 251-500        | 48        | 18.82%  |
| 501-1000       | 45        | 17.65%  |
| 1001-2000      | 24        | 9.41%   |
| 1-20           | 18        | 7.06%   |
| 51-100         | 16        | 6.27%   |
| More than 3000 | 14        | 5.49%   |
| 21-50          | 14        | 5.49%   |
| Unknown        | 8         | 3.14%   |
| 2001-3000      | 7         | 2.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 100       | 38.76%  |
| 21-50          | 41        | 15.89%  |
| 101-250        | 35        | 13.57%  |
| 51-100         | 27        | 10.47%  |
| 251-500        | 25        | 9.69%   |
| 501-1000       | 10        | 3.88%   |
| Unknown        | 8         | 3.1%    |
| 1001-2000      | 5         | 1.94%   |
| More than 3000 | 4         | 1.55%   |
| 2001-3000      | 3         | 1.16%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD6400AAKS-22A7B2 640GB        | 2         | 3      | 15.38%  |
| WDC WD5000AAKS-22V1A0 500GB        | 1         | 1      | 7.69%   |
| WDC WD50 EZRX-00MVLB1 5TB          | 1         | 1      | 7.69%   |
| WDC WD10EZEX-60M2NA0 1TB           | 1         | 1      | 7.69%   |
| Toshiba DT01ACA100 1TB             | 1         | 1      | 7.69%   |
| Seagate ST2000LM003 HN-M201RAD 2TB | 1         | 1      | 7.69%   |
| Seagate ST1000LM024 HN-M 1TB       | 1         | 1      | 7.69%   |
| Hitachi HTS545032B9A300 320GB      | 1         | 1      | 7.69%   |
| Hitachi HTS541010A9E680 1TB        | 1         | 1      | 7.69%   |
| Hitachi HDS721010CLA632 1TB        | 1         | 1      | 7.69%   |
| HGST HTS545050A7E380 500GB         | 1         | 1      | 7.69%   |
| Crucial CT120M500SSD1 120GB        | 1         | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 6      | 38.46%  |
| Hitachi | 3         | 3      | 23.08%  |
| Seagate | 2         | 2      | 15.38%  |
| Toshiba | 1         | 1      | 7.69%   |
| HGST    | 1         | 1      | 7.69%   |
| Crucial | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 6      | 41.67%  |
| Hitachi | 3         | 3      | 25%     |
| Seagate | 2         | 2      | 16.67%  |
| Toshiba | 1         | 1      | 8.33%   |
| HGST    | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 13     | 92.31%  |
| SSD  | 1         | 1      | 7.69%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model              | Computers | Drives | Percent |
|--------------------|-----------|--------|---------|
| JMicron Tech 250GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| JMicron | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 159       | 269    | 60.46%  |
| Works    | 90        | 153    | 34.22%  |
| Malfunc  | 13        | 14     | 4.94%   |
| Failed   | 1         | 1      | 0.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 158       | 52.67%  |
| Samsung Electronics          | 36        | 12%     |
| AMD                          | 36        | 12%     |
| Sandisk                      | 19        | 6.33%   |
| SK Hynix                     | 12        | 4%      |
| Toshiba America Info Systems | 8         | 2.67%   |
| Phison Electronics           | 5         | 1.67%   |
| Silicon Motion               | 3         | 1%      |
| Nvidia                       | 3         | 1%      |
| Lenovo                       | 3         | 1%      |
| KIOXIA                       | 3         | 1%      |
| Micron/Crucial Technology    | 2         | 0.67%   |
| Micron Technology            | 2         | 0.67%   |
| ADATA Technology             | 2         | 0.67%   |
| VIA Technologies             | 1         | 0.33%   |
| Union Memory (Shenzhen)      | 1         | 0.33%   |
| Shenzhen Longsys Electronics | 1         | 0.33%   |
| Seagate Technology           | 1         | 0.33%   |
| Marvell Technology Group     | 1         | 0.33%   |
| Kingston Technology Company  | 1         | 0.33%   |
| Broadcom / LSI               | 1         | 0.33%   |
| ASMedia Technology           | 1         | 0.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 27        | 8.28%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 25        | 7.67%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 14        | 4.29%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 12        | 3.68%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 10        | 3.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 9         | 2.76%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 7         | 2.15%   |
| Intel SATA Controller [RAID mode]                                                       | 7         | 2.15%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 7         | 2.15%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 7         | 2.15%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 6         | 1.84%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 6         | 1.84%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 5         | 1.53%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 5         | 1.53%   |
| Intel SSD 660P Series                                                                   | 5         | 1.53%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5         | 1.53%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5         | 1.53%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 4         | 1.23%   |
| SK Hynix Gold P31 SSD                                                                   | 4         | 1.23%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 4         | 1.23%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 4         | 1.23%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 4         | 1.23%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4         | 1.23%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 4         | 1.23%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4         | 1.23%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4         | 1.23%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 3         | 0.92%   |
| SK Hynix Non-Volatile memory controller                                                 | 3         | 0.92%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3         | 0.92%   |
| Lenovo Non-Volatile memory controller                                                   | 3         | 0.92%   |
| KIOXIA Non-Volatile memory controller                                                   | 3         | 0.92%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 3         | 0.92%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3         | 0.92%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 3         | 0.92%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3         | 0.92%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 0.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3         | 0.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3         | 0.92%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3         | 0.92%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3         | 0.92%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                              | 2         | 0.61%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 2         | 0.61%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 2         | 0.61%   |
| Samsung Electronics SATA controller                                                     | 2         | 0.61%   |
| Phison E12 NVMe Controller                                                              | 2         | 0.61%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                                | 2         | 0.61%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2         | 0.61%   |
| Micron Non-Volatile memory controller                                                   | 2         | 0.61%   |
| Intel Non-Volatile memory controller                                                    | 2         | 0.61%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2         | 0.61%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 0.61%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2         | 0.61%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 2         | 0.61%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 2         | 0.61%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 0.61%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 0.61%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2         | 0.61%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2         | 0.61%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 0.61%   |
| AMD FCH SATA Controller D                                                               | 2         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 158       | 51.97%  |
| NVMe | 100       | 32.89%  |
| RAID | 25        | 8.22%   |
| IDE  | 20        | 6.58%   |
| SAS  | 1         | 0.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 190       | 78.51%  |
| AMD    | 47        | 19.42%  |
| ARM    | 5         | 2.07%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 10        | 4.13%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 6         | 2.48%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 2.07%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 2.07%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 5         | 2.07%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.65%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 4         | 1.65%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.65%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.65%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.24%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 1.24%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 1.24%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 3         | 1.24%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.24%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 3         | 1.24%   |
| ARM Processor                                 | 3         | 1.24%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 1.24%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.24%   |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 2         | 0.83%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.83%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.83%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 0.83%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 2         | 0.83%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.83%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 2         | 0.83%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 0.83%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 0.83%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 2         | 0.83%   |
| Intel Core i5-4690 CPU @ 3.50GHz              | 2         | 0.83%   |
| Intel Core i5-3570 CPU @ 3.40GHz              | 2         | 0.83%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 2         | 0.83%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 0.83%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 2         | 0.83%   |
| Intel Core i5 CPU 650 @ 3.20GHz               | 2         | 0.83%   |
| Intel Core i3 CPU 550 @ 3.20GHz               | 2         | 0.83%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz          | 2         | 0.83%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 0.83%   |
| Intel Atom x5-Z8500 CPU @ 1.44GHz             | 2         | 0.83%   |
| ARM BCM2711 Processor                         | 2         | 0.83%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 0.83%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 2         | 0.83%   |
| AMD Ryzen 5 3600X 6-Core Processor            | 2         | 0.83%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 0.83%   |
| AMD Ryzen 5 3500X 6-Core Processor            | 2         | 0.83%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 2         | 0.83%   |
| Intel Xeon W-2155 CPU @ 3.30GHz               | 1         | 0.41%   |
| Intel Xeon W-11955M CPU @ 2.60GHz             | 1         | 0.41%   |
| Intel Xeon Silver 4110 CPU @ 2.10GHz          | 1         | 0.41%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz          | 1         | 0.41%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz           | 1         | 0.41%   |
| Intel Xeon CPU E3-1240 v3 @ 3.40GHz           | 1         | 0.41%   |
| Intel Xeon CPU E3-1230 v5 @ 3.40GHz           | 1         | 0.41%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz           | 1         | 0.41%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz           | 1         | 0.41%   |
| Intel Processor 5Y70 CPU @ 1.10GHz            | 1         | 0.41%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 0.41%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.41%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz        | 1         | 0.41%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz        | 1         | 0.41%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz        | 1         | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 66        | 27.27%  |
| Intel Core i5           | 56        | 23.14%  |
| Other                   | 15        | 6.2%    |
| AMD Ryzen 5             | 15        | 6.2%    |
| AMD Ryzen 7             | 13        | 5.37%   |
| Intel Xeon              | 10        | 4.13%   |
| Intel Core i3           | 9         | 3.72%   |
| Intel Core 2 Duo        | 8         | 3.31%   |
| Intel Celeron           | 6         | 2.48%   |
| Intel Atom              | 6         | 2.48%   |
| Intel Core i9           | 4         | 1.65%   |
| Intel Pentium Silver    | 2         | 0.83%   |
| Intel Pentium Dual      | 2         | 0.83%   |
| Intel Pentium           | 2         | 0.83%   |
| Intel Core m3           | 2         | 0.83%   |
| ARM BCM                 | 2         | 0.83%   |
| AMD Ryzen 9             | 2         | 0.83%   |
| AMD Ryzen 7 PRO         | 2         | 0.83%   |
| AMD Ryzen 5 PRO         | 2         | 0.83%   |
| AMD FX                  | 2         | 0.83%   |
| AMD Athlon              | 2         | 0.83%   |
| AMD A10                 | 2         | 0.83%   |
| Intel Xeon Silver       | 1         | 0.41%   |
| Intel Pentium Gold      | 1         | 0.41%   |
| Intel Pentium 4         | 1         | 0.41%   |
| Intel Core 2 Quad       | 1         | 0.41%   |
| Intel Core 2            | 1         | 0.41%   |
| AMD Turion 64 X2 Mobile | 1         | 0.41%   |
| AMD Ryzen Threadripper  | 1         | 0.41%   |
| AMD Ryzen 3             | 1         | 0.41%   |
| AMD PRO A10             | 1         | 0.41%   |
| AMD Phenom II X4        | 1         | 0.41%   |
| AMD E                   | 1         | 0.41%   |
| AMD A6                  | 1         | 0.41%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 107       | 44.21%  |
| 2      | 75        | 30.99%  |
| 6      | 26        | 10.74%  |
| 8      | 24        | 9.92%   |
| 16     | 3         | 1.24%   |
| 1      | 3         | 1.24%   |
| 14     | 1         | 0.41%   |
| 12     | 1         | 0.41%   |
| 10     | 1         | 0.41%   |
| 3      | 1         | 0.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 241       | 99.59%  |
| 2      | 1         | 0.41%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 180       | 73.77%  |
| 1      | 64        | 26.23%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 235       | 97.11%  |
| Unknown        | 5         | 2.07%   |
| 32-bit         | 2         | 0.83%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 41        | 16.53%  |
| 0x906ea    | 14        | 5.65%   |
| 0x806ea    | 13        | 5.24%   |
| 0x206a7    | 13        | 5.24%   |
| 0x306a9    | 12        | 4.84%   |
| 0x306c3    | 11        | 4.44%   |
| 0x806ec    | 10        | 4.03%   |
| 0x506e3    | 9         | 3.63%   |
| 0x20655    | 8         | 3.23%   |
| 0x806eb    | 7         | 2.82%   |
| 0x40651    | 6         | 2.42%   |
| 0x306d4    | 5         | 2.02%   |
| 0x08108109 | 5         | 2.02%   |
| 0x906e9    | 4         | 1.61%   |
| 0x806e9    | 4         | 1.61%   |
| 0x6fd      | 4         | 1.61%   |
| 0x406e3    | 4         | 1.61%   |
| 0x1067a    | 4         | 1.61%   |
| 0x0a50000c | 4         | 1.61%   |
| 0x08701021 | 4         | 1.61%   |
| 0xa0652    | 3         | 1.21%   |
| 0x806c1    | 3         | 1.21%   |
| 0x50654    | 3         | 1.21%   |
| 0x406c3    | 3         | 1.21%   |
| 0x08701013 | 3         | 1.21%   |
| 0x08600106 | 3         | 1.21%   |
| 0xa0660    | 2         | 0.81%   |
| 0x906ed    | 2         | 0.81%   |
| 0x806d1    | 2         | 0.81%   |
| 0x806c2    | 2         | 0.81%   |
| 0x706a1    | 2         | 0.81%   |
| 0x40661    | 2         | 0.81%   |
| 0x306e4    | 2         | 0.81%   |
| 0x30678    | 2         | 0.81%   |
| 0x106c2    | 2         | 0.81%   |
| 0x08600103 | 2         | 0.81%   |
| 0x08108102 | 2         | 0.81%   |
| 0x06003106 | 2         | 0.81%   |
| 0x06000852 | 2         | 0.81%   |
| 0xf41      | 1         | 0.4%    |
| 0xa0671    | 1         | 0.4%    |
| 0xa0655    | 1         | 0.4%    |
| 0x906c0    | 1         | 0.4%    |
| 0x706e5    | 1         | 0.4%    |
| 0x6fb      | 1         | 0.4%    |
| 0x6f6      | 1         | 0.4%    |
| 0x506ca    | 1         | 0.4%    |
| 0x10676    | 1         | 0.4%    |
| 0x0a201016 | 1         | 0.4%    |
| 0x0a201009 | 1         | 0.4%    |
| 0x08608103 | 1         | 0.4%    |
| 0x08301039 | 1         | 0.4%    |
| 0x08101102 | 1         | 0.4%    |
| 0x0810100b | 1         | 0.4%    |
| 0x08001138 | 1         | 0.4%    |
| 0x08001137 | 1         | 0.4%    |
| 0x06006705 | 1         | 0.4%    |
| 0x0600611a | 1         | 0.4%    |
| 0x0600081c | 1         | 0.4%    |
| 0x010000db | 1         | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 61        | 25.21%  |
| Haswell       | 21        | 8.68%   |
| Skylake       | 16        | 6.61%   |
| SandyBridge   | 16        | 6.61%   |
| IvyBridge     | 15        | 6.2%    |
| Zen 2         | 14        | 5.79%   |
| Zen+          | 10        | 4.13%   |
| Zen 3         | 8         | 3.31%   |
| Westmere      | 8         | 3.31%   |
| TigerLake     | 8         | 3.31%   |
| Unknown       | 8         | 3.31%   |
| Silvermont    | 7         | 2.89%   |
| CometLake     | 7         | 2.89%   |
| Penryn        | 6         | 2.48%   |
| Core          | 6         | 2.48%   |
| Icelake       | 5         | 2.07%   |
| Broadwell     | 5         | 2.07%   |
| Zen           | 4         | 1.65%   |
| Steamroller   | 2         | 0.83%   |
| Piledriver    | 2         | 0.83%   |
| K10           | 2         | 0.83%   |
| Goldmont plus | 2         | 0.83%   |
| Excavator     | 2         | 0.83%   |
| Bonnell       | 2         | 0.83%   |
| Tremont       | 1         | 0.41%   |
| NetBurst      | 1         | 0.41%   |
| K8 Hammer     | 1         | 0.41%   |
| Goldmont      | 1         | 0.41%   |
| Bobcat        | 1         | 0.41%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 159       | 52.3%   |
| Nvidia            | 94        | 30.92%  |
| AMD               | 50        | 16.45%  |
| ASPEED Technology | 1         | 0.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 15        | 4.78%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 4.78%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 11        | 3.5%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 10        | 3.18%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 9         | 2.87%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 2.23%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 7         | 2.23%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 2.23%   |
| Intel HD Graphics 620                                                                    | 6         | 1.91%   |
| Intel HD Graphics 530                                                                    | 6         | 1.91%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 1.91%   |
| AMD Renoir                                                                               | 6         | 1.91%   |
| Nvidia GP108M [GeForce MX150]                                                            | 5         | 1.59%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4         | 1.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 1.27%   |
| Intel HD Graphics 5500                                                                   | 4         | 1.27%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.27%   |
| AMD Cezanne                                                                              | 4         | 1.27%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.96%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 3         | 0.96%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.96%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 0.96%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.96%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 0.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.96%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 0.96%   |
| Intel HD Graphics 630                                                                    | 3         | 0.96%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 0.96%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 0.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 0.96%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 0.96%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.64%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 2         | 0.64%   |
| Nvidia TU104M [GeForce RTX 2080 Mobile]                                                  | 2         | 0.64%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 0.64%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 0.64%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2         | 0.64%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.64%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 0.64%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.64%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 2         | 0.64%   |
| Nvidia GM108M [GeForce 940M]                                                             | 2         | 0.64%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 0.64%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 2         | 0.64%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 0.64%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.64%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 0.64%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.64%   |
| Intel Comet Lake UHD Graphics                                                            | 2         | 0.64%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2         | 0.64%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 0.64%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 2         | 0.64%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 0.64%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 2         | 0.64%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 0.64%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                              | 2         | 0.64%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 2         | 0.64%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.32%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 100       | 40.65%  |
| Intel + Nvidia  | 48        | 19.51%  |
| 1 x Nvidia      | 40        | 16.26%  |
| 1 x AMD         | 36        | 14.63%  |
| Intel + AMD     | 7         | 2.85%   |
| Other           | 5         | 2.03%   |
| AMD + Nvidia    | 4         | 1.63%   |
| 2 x AMD         | 3         | 1.22%   |
| 2 x Nvidia      | 2         | 0.81%   |
| Nvidia + ASPEED | 1         | 0.41%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 187       | 75.4%   |
| Proprietary | 51        | 20.56%  |
| Unknown     | 10        | 4.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 141       | 55.73%  |
| 1.01-2.0   | 39        | 15.42%  |
| 3.01-4.0   | 24        | 9.49%   |
| 0.01-0.5   | 16        | 6.32%   |
| 7.01-8.0   | 11        | 4.35%   |
| 0.51-1.0   | 11        | 4.35%   |
| 5.01-6.0   | 6         | 2.37%   |
| 8.01-16.0  | 5         | 1.98%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 44        | 16.79%  |
| Dell                    | 39        | 14.89%  |
| Samsung Electronics     | 31        | 11.83%  |
| LG Display              | 25        | 9.54%   |
| BOE                     | 20        | 7.63%   |
| Chimei Innolux          | 16        | 6.11%   |
| Acer                    | 11        | 4.2%    |
| Goldstar                | 9         | 3.44%   |
| Sharp                   | 8         | 3.05%   |
| Apple                   | 8         | 3.05%   |
| Philips                 | 6         | 2.29%   |
| Hewlett-Packard         | 5         | 1.91%   |
| AOC                     | 4         | 1.53%   |
| PRISM+                  | 3         | 1.15%   |
| InfoVision              | 3         | 1.15%   |
| Denver                  | 3         | 1.15%   |
| CSO                     | 3         | 1.15%   |
| LG Philips              | 2         | 0.76%   |
| Lenovo Group Limited    | 2         | 0.76%   |
| Lenovo                  | 2         | 0.76%   |
| ASUSTek Computer        | 2         | 0.76%   |
| Ancor Communications    | 2         | 0.76%   |
| Wacom                   | 1         | 0.38%   |
| Unknown                 | 1         | 0.38%   |
| Toshiba                 | 1         | 0.38%   |
| Sony                    | 1         | 0.38%   |
| SGT                     | 1         | 0.38%   |
| SAC                     | 1         | 0.38%   |
| Pixio                   | 1         | 0.38%   |
| PANDA                   | 1         | 0.38%   |
| Mi                      | 1         | 0.38%   |
| EXP                     | 1         | 0.38%   |
| CVT                     | 1         | 0.38%   |
| CHR                     | 1         | 0.38%   |
| Chi Mei Optoelectronics | 1         | 0.38%   |
| BenQ                    | 1         | 0.38%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3         | 1.13%   |
| Dell S2340L DELD058 1920x1080 510x290mm 23.1-inch                     | 3         | 1.13%   |
| Dell P2421D DELD0FF 2560x1440 527x296mm 23.8-inch                     | 3         | 1.13%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2         | 0.75%   |
| PRISM+ X315 INN3200 2560x1440 697x393mm 31.5-inch                     | 2         | 0.75%   |
| LG Philips LCD Monitor LPL8D00 1280x800 304x190mm 14.1-inch           | 2         | 0.75%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch          | 2         | 0.75%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 2         | 0.75%   |
| Hewlett-Packard 23es HWP331E 1920x1080 509x286mm 23.0-inch            | 2         | 0.75%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 2         | 0.75%   |
| Goldstar LG ULTRAGEAR GSM5B7F 2560x1440 600x340mm 27.2-inch           | 2         | 0.75%   |
| Goldstar IPS224 GSM58D5 1920x1080 477x268mm 21.5-inch                 | 2         | 0.75%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 2         | 0.75%   |
| Denver F240v LHC0236 1920x1080 530x280mm 23.6-inch                    | 2         | 0.75%   |
| Dell SE2417HG DELD08C 1920x1080 521x293mm 23.5-inch                   | 2         | 0.75%   |
| Dell E2213H DELA08F 1920x1080 480x270mm 21.7-inch                     | 2         | 0.75%   |
| Dell E2011H DEL406C 1600x900 443x249mm 20.0-inch                      | 2         | 0.75%   |
| Chimei Innolux LCD Monitor CMN1354 1920x1080 293x165mm 13.2-inch      | 2         | 0.75%   |
| BOE LCD Monitor BOE06A7 1920x1080 294x165mm 13.3-inch                 | 2         | 0.75%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 2         | 0.75%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 2         | 0.75%   |
| AU Optronics LCD Monitor AUO31EB 3840x2160 344x193mm 15.5-inch        | 2         | 0.75%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch        | 2         | 0.75%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch         | 2         | 0.75%   |
| AU Optronics LCD Monitor AUO205C 1366x768 256x144mm 11.6-inch         | 2         | 0.75%   |
| Acer S201HL ACR01A5 1600x900 443x249mm 20.0-inch                      | 2         | 0.75%   |
| Acer EB321HQU ACR0507 2560x1440 699x393mm 31.6-inch                   | 2         | 0.75%   |
| Wacom CintiqPro24P WAC1063 3840x2160 530x300mm 24.0-inch              | 1         | 0.38%   |
| Unknown LCD Monitor AAA HDTV 3286x1080                                | 1         | 0.38%   |
| Toshiba LCD TV LCD0030 1920x1080 708x398mm 32.0-inch                  | 1         | 0.38%   |
| Sony TV SNY2C02 1920x1080 1018x573mm 46.0-inch                        | 1         | 0.38%   |
| Sharp LQ150P1JX51 SHP14B4 2496x1664 317x211mm 15.0-inch               | 1         | 0.38%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch               | 1         | 0.38%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 1         | 0.38%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.38%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch               | 1         | 0.38%   |
| Sharp LCD Monitor SHP1485 1920x1080 294x165mm 13.3-inch               | 1         | 0.38%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.38%   |
| Sharp HDMI SHP115C 1920x1080 880x480mm 39.5-inch                      | 1         | 0.38%   |
| SGT Split SGT0156 1920x1080 346x194mm 15.6-inch                       | 1         | 0.38%   |
| Samsung Electronics U32R59x SAM0F94 3840x2160 697x392mm 31.5-inch     | 1         | 0.38%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch     | 1         | 0.38%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch     | 1         | 0.38%   |
| Samsung Electronics S24R35xFZ SAM71A8 1920x1080 527x296mm 23.8-inch   | 1         | 0.38%   |
| Samsung Electronics S24D300 SAM0B42 1920x1080 531x299mm 24.0-inch     | 1         | 0.38%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 630x360mm 28.6-inch     | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC554E 1024x600 223x125mm 10.1-inch  | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch  | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC3052 1366x768 344x194mm 15.5-inch  | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 350x200mm 15.9-inch  | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch  | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 293x165mm 13.2-inch | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SDC4141 3840x2160 344x194mm 15.5-inch | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SDC3652 1366x768 344x194mm 15.5-inch  | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SAM0DF6 3840x2160 890x500mm 40.2-inch | 1         | 0.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 129       | 51.6%   |
| 1366x768 (WXGA)   | 29        | 11.6%   |
| 3840x2160 (4K)    | 22        | 8.8%    |
| 2560x1440 (QHD)   | 20        | 8%      |
| 1600x900 (HD+)    | 9         | 3.6%    |
| 1280x800 (WXGA)   | 8         | 3.2%    |
| 1920x1200 (WUXGA) | 4         | 1.6%    |
| 1360x768          | 4         | 1.6%    |
| 3440x1440         | 2         | 0.8%    |
| 3200x1800 (QHD+)  | 2         | 0.8%    |
| 2880x1800         | 2         | 0.8%    |
| 2736x1824         | 2         | 0.8%    |
| 2560x1600         | 2         | 0.8%    |
| 2240x1400         | 2         | 0.8%    |
| 1440x900 (WXGA+)  | 2         | 0.8%    |
| 1280x1024 (SXGA)  | 2         | 0.8%    |
| 3840x2400         | 1         | 0.4%    |
| 3840x1600         | 1         | 0.4%    |
| 3286x1080         | 1         | 0.4%    |
| 3000x2000         | 1         | 0.4%    |
| 2560x1080         | 1         | 0.4%    |
| 2496x1664         | 1         | 0.4%    |
| 1280x720 (HD)     | 1         | 0.4%    |
| 1024x600          | 1         | 0.4%    |
| Unknown           | 1         | 0.4%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 48        | 18.53%  |
| 13      | 40        | 15.44%  |
| 14      | 33        | 12.74%  |
| 27      | 24        | 9.27%   |
| 23      | 20        | 7.72%   |
| 24      | 16        | 6.18%   |
| 21      | 10        | 3.86%   |
| 12      | 10        | 3.86%   |
| Unknown | 9         | 3.47%   |
| 20      | 7         | 2.7%    |
| 18      | 6         | 2.32%   |
| 11      | 6         | 2.32%   |
| 31      | 5         | 1.93%   |
| 19      | 5         | 1.93%   |
| 32      | 3         | 1.16%   |
| 28      | 2         | 0.77%   |
| 25      | 2         | 0.77%   |
| 16      | 2         | 0.77%   |
| 84      | 1         | 0.39%   |
| 55      | 1         | 0.39%   |
| 54      | 1         | 0.39%   |
| 52      | 1         | 0.39%   |
| 40      | 1         | 0.39%   |
| 39      | 1         | 0.39%   |
| 37      | 1         | 0.39%   |
| 35      | 1         | 0.39%   |
| 34      | 1         | 0.39%   |
| 17      | 1         | 0.39%   |
| 10      | 1         | 0.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 97        | 37.45%  |
| 501-600     | 62        | 23.94%  |
| 201-300     | 40        | 15.44%  |
| 401-500     | 25        | 9.65%   |
| Unknown     | 9         | 3.47%   |
| 601-700     | 7         | 2.7%    |
| 351-400     | 7         | 2.7%    |
| 801-900     | 4         | 1.54%   |
| 701-800     | 4         | 1.54%   |
| 1001-1500   | 3         | 1.16%   |
| 1501-2000   | 1         | 0.39%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 191       | 82.33%  |
| 16/10   | 22        | 9.48%   |
| Unknown | 7         | 3.02%   |
| 3/2     | 5         | 2.16%   |
| 21/9    | 4         | 1.72%   |
| 5/4     | 2         | 0.86%   |
| 6/5     | 1         | 0.43%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 53        | 20.54%  |
| 101-110        | 48        | 18.6%   |
| 201-250        | 38        | 14.73%  |
| 301-350        | 24        | 9.3%    |
| 71-80          | 21        | 8.14%   |
| 151-200        | 15        | 5.81%   |
| 351-500        | 11        | 4.26%   |
| 61-70          | 9         | 3.49%   |
| Unknown        | 9         | 3.49%   |
| 251-300        | 8         | 3.1%    |
| 51-60          | 6         | 2.33%   |
| 141-150        | 5         | 1.94%   |
| More than 1000 | 4         | 1.55%   |
| 501-1000       | 3         | 1.16%   |
| 111-120        | 2         | 0.78%   |
| 41-50          | 1         | 0.39%   |
| 121-130        | 1         | 0.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 85        | 33.73%  |
| 51-100        | 68        | 26.98%  |
| 101-120       | 43        | 17.06%  |
| 161-240       | 32        | 12.7%   |
| More than 240 | 11        | 4.37%   |
| Unknown       | 9         | 3.57%   |
| 1-50          | 4         | 1.59%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 199       | 79.6%   |
| 2     | 38        | 15.2%   |
| 0     | 12        | 4.8%    |
| 3     | 1         | 0.4%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 139       | 41%     |
| Realtek Semiconductor    | 102       | 30.09%  |
| Qualcomm Atheros         | 39        | 11.5%   |
| Broadcom                 | 18        | 5.31%   |
| TP-Link                  | 5         | 1.47%   |
| MEDIATEK                 | 4         | 1.18%   |
| Marvell Technology Group | 4         | 1.18%   |
| ASIX Electronics         | 4         | 1.18%   |
| Samsung Electronics      | 3         | 0.88%   |
| Broadcom Limited         | 3         | 0.88%   |
| Sierra Wireless          | 2         | 0.59%   |
| Ralink Technology        | 1         | 0.29%   |
| Ralink                   | 1         | 0.29%   |
| Qualcomm                 | 1         | 0.29%   |
| Nvidia                   | 1         | 0.29%   |
| MosChip Semiconductor    | 1         | 0.29%   |
| Microsoft                | 1         | 0.29%   |
| Linksys                  | 1         | 0.29%   |
| Lenovo                   | 1         | 0.29%   |
| Hewlett-Packard          | 1         | 0.29%   |
| Google                   | 1         | 0.29%   |
| Fargo                    | 1         | 0.29%   |
| Exar                     | 1         | 0.29%   |
| Edimax Technology        | 1         | 0.29%   |
| D-Link                   | 1         | 0.29%   |
| Aquantia                 | 1         | 0.29%   |
| Apple                    | 1         | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 60        | 14.96%  |
| Intel Wi-Fi 6 AX200                                                     | 22        | 5.49%   |
| Intel Wireless 7265                                                     | 13        | 3.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 12        | 2.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 11        | 2.74%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 9         | 2.24%   |
| Intel Wireless 8265 / 8275                                              | 8         | 2%      |
| Intel I211 Gigabit Network Connection                                   | 8         | 2%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 2%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 1.75%   |
| Intel Wi-Fi 6 AX201                                                     | 7         | 1.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 1.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 6         | 1.5%    |
| Intel Wireless 7260                                                     | 6         | 1.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 1.5%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 1.25%   |
| Realtek RTL8125 2.5GbE Controller                                       | 5         | 1.25%   |
| Intel Wireless 3165                                                     | 5         | 1.25%   |
| Intel Ethernet Controller I225-V                                        | 5         | 1.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 1.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1%      |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 1%      |
| Intel Ethernet Connection I217-LM                                       | 4         | 1%      |
| Intel Ethernet Connection (2) I219-V                                    | 4         | 1%      |
| Intel Ethernet Connection (10) I219-V                                   | 4         | 1%      |
| ASIX AX88179 Gigabit Ethernet                                           | 4         | 1%      |
| Samsung Galaxy series, misc. (tethering mode)                           | 3         | 0.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 0.75%   |
| Intel Wireless-AC 9260                                                  | 3         | 0.75%   |
| Intel Wireless 8260                                                     | 3         | 0.75%   |
| Intel Ethernet Connection I218-LM                                       | 3         | 0.75%   |
| Intel Ethernet Connection (4) I219-LM                                   | 3         | 0.75%   |
| Intel Ethernet Connection (2) I219-LM                                   | 3         | 0.75%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 0.75%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 3         | 0.75%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                              | 2         | 0.5%    |
| TP-Link 802.11ac WLAN Adapter                                           | 2         | 0.5%    |
| Sierra Wireless EM7455                                                  | 2         | 0.5%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 2         | 0.5%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 0.5%    |
| Realtek Killer E3000 2.5GbE Controller                                  | 2         | 0.5%    |
| Realtek 802.11ac NIC                                                    | 2         | 0.5%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 2         | 0.5%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 0.5%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.5%    |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 2         | 0.5%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 0.5%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 0.5%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 0.5%    |
| Intel Ethernet Connection I217-V                                        | 2         | 0.5%    |
| Intel Ethernet Connection (7) I219-LM                                   | 2         | 0.5%    |
| Intel Ethernet Connection (4) I219-V                                    | 2         | 0.5%    |
| Intel Ethernet Connection (3) I218-LM                                   | 2         | 0.5%    |
| Intel 82579V Gigabit Network Connection                                 | 2         | 0.5%    |
| Intel 82578DM Gigabit Network Connection                                | 2         | 0.5%    |
| Intel 82567LM Gigabit Network Connection                                | 2         | 0.5%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                       | 2         | 0.5%    |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 2         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 112       | 54.9%   |
| Qualcomm Atheros         | 34        | 16.67%  |
| Realtek Semiconductor    | 23        | 11.27%  |
| Broadcom                 | 14        | 6.86%   |
| TP-Link                  | 5         | 2.45%   |
| MEDIATEK                 | 4         | 1.96%   |
| Sierra Wireless          | 2         | 0.98%   |
| Marvell Technology Group | 2         | 0.98%   |
| Broadcom Limited         | 2         | 0.98%   |
| Ralink Technology        | 1         | 0.49%   |
| Ralink                   | 1         | 0.49%   |
| Qualcomm                 | 1         | 0.49%   |
| Linksys                  | 1         | 0.49%   |
| Edimax Technology        | 1         | 0.49%   |
| D-Link                   | 1         | 0.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 22        | 10.73%  |
| Intel Wireless 7265                                                     | 13        | 6.34%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 11        | 5.37%   |
| Intel Wireless 8265 / 8275                                              | 8         | 3.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 3.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 3.41%   |
| Intel Wi-Fi 6 AX201                                                     | 7         | 3.41%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 3.41%   |
| Intel Wireless 7260                                                     | 6         | 2.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 2.93%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 2.44%   |
| Intel Wireless 3165                                                     | 5         | 2.44%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 2.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.95%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 1.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 1.46%   |
| Intel Wireless-AC 9260                                                  | 3         | 1.46%   |
| Intel Wireless 8260                                                     | 3         | 1.46%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.46%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                              | 2         | 0.98%   |
| TP-Link 802.11ac WLAN Adapter                                           | 2         | 0.98%   |
| Sierra Wireless EM7455                                                  | 2         | 0.98%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 2         | 0.98%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 0.98%   |
| Realtek 802.11ac NIC                                                    | 2         | 0.98%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 0.98%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.98%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 2         | 0.98%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 0.98%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 0.98%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 0.98%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 2         | 0.98%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 2         | 0.98%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 2         | 0.98%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 0.98%   |
| Broadcom BCM4311 802.11a/b/g                                            | 2         | 0.98%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]     | 1         | 0.49%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.49%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.49%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.49%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.49%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.49%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 0.49%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                  | 1         | 0.49%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 0.49%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.49%   |
| Realtek 802.11ax WLAN Adapter                                           | 1         | 0.49%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.49%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.49%   |
| Qualcomm QCA6390 Wireless Network Adapter                               | 1         | 0.49%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.49%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 1         | 0.49%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.49%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                     | 1         | 0.49%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 0.49%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 0.49%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 0.49%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 85        | 44.74%  |
| Intel                    | 70        | 36.84%  |
| Qualcomm Atheros         | 9         | 4.74%   |
| Broadcom                 | 8         | 4.21%   |
| ASIX Electronics         | 4         | 2.11%   |
| Samsung Electronics      | 3         | 1.58%   |
| Marvell Technology Group | 2         | 1.05%   |
| Nvidia                   | 1         | 0.53%   |
| MosChip Semiconductor    | 1         | 0.53%   |
| Microsoft                | 1         | 0.53%   |
| Lenovo                   | 1         | 0.53%   |
| Hewlett-Packard          | 1         | 0.53%   |
| Google                   | 1         | 0.53%   |
| Broadcom Limited         | 1         | 0.53%   |
| Aquantia                 | 1         | 0.53%   |
| Apple                    | 1         | 0.53%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 60        | 30.93%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 12        | 6.19%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 9         | 4.64%   |
| Intel I211 Gigabit Network Connection                                          | 8         | 4.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 6         | 3.09%   |
| Realtek RTL8125 2.5GbE Controller                                              | 5         | 2.58%   |
| Intel Ethernet Controller I225-V                                               | 5         | 2.58%   |
| Intel Ethernet Connection I217-LM                                              | 4         | 2.06%   |
| Intel Ethernet Connection (2) I219-V                                           | 4         | 2.06%   |
| Intel Ethernet Connection (10) I219-V                                          | 4         | 2.06%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 4         | 2.06%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 3         | 1.55%   |
| Intel Ethernet Connection I218-LM                                              | 3         | 1.55%   |
| Intel Ethernet Connection (4) I219-LM                                          | 3         | 1.55%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 1.55%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 3         | 1.55%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 2         | 1.03%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 1.03%   |
| Intel Ethernet Connection I217-V                                               | 2         | 1.03%   |
| Intel Ethernet Connection (7) I219-LM                                          | 2         | 1.03%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 1.03%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 1.03%   |
| Intel 82579V Gigabit Network Connection                                        | 2         | 1.03%   |
| Intel 82578DM Gigabit Network Connection                                       | 2         | 1.03%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 1.03%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2         | 1.03%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.52%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.52%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1         | 0.52%   |
| Realtek Realtek Ethernet controller                                            | 1         | 0.52%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.52%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.52%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.52%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.52%   |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 0.52%   |
| MosChip MCS7830 10/100 Mbps Ethernet adapter                                   | 1         | 0.52%   |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                              | 1         | 0.52%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.52%   |
| Marvell Group 88E8038 PCI-E Fast Ethernet Controller                           | 1         | 0.52%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.52%   |
| Intel I210 Gigabit Network Connection                                          | 1         | 0.52%   |
| Intel Ethernet Connection X722 for 1GbE                                        | 1         | 0.52%   |
| Intel Ethernet Connection X722                                                 | 1         | 0.52%   |
| Intel Ethernet Connection (7) I219-V                                           | 1         | 0.52%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.52%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 0.52%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.52%   |
| Intel Ethernet Connection (3) I219-LM                                          | 1         | 0.52%   |
| Intel Ethernet Connection (2) I218-V                                           | 1         | 0.52%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 0.52%   |
| Intel Ethernet Connection (11) I219-V                                          | 1         | 0.52%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.52%   |
| Intel 82566DC-2 Gigabit Network Connection                                     | 1         | 0.52%   |
| HP lt4120 Snapdragon X5 LTE                                                    | 1         | 0.52%   |
| Google Nexus/Pixel Device (tether)                                             | 1         | 0.52%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 1         | 0.52%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                               | 1         | 0.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 196       | 51.99%  |
| Ethernet | 179       | 47.48%  |
| Modem    | 1         | 0.27%   |
| Unknown  | 1         | 0.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 162       | 63.28%  |
| Ethernet | 93        | 36.33%  |
| Unknown  | 1         | 0.39%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 117       | 48.15%  |
| 2     | 115       | 47.33%  |
| 0     | 7         | 2.88%   |
| 3     | 3         | 1.23%   |
| 4     | 1         | 0.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 229       | 94.63%  |
| Yes  | 13        | 5.37%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 93        | 56.36%  |
| Qualcomm Atheros Communications | 13        | 7.88%   |
| IMC Networks                    | 9         | 5.45%   |
| Foxconn / Hon Hai               | 8         | 4.85%   |
| Broadcom                        | 8         | 4.85%   |
| Cambridge Silicon Radio         | 7         | 4.24%   |
| Apple                           | 7         | 4.24%   |
| Realtek Semiconductor           | 6         | 3.64%   |
| Lite-On Technology              | 4         | 2.42%   |
| TP-Link                         | 2         | 1.21%   |
| Marvell Semiconductor           | 2         | 1.21%   |
| Toshiba                         | 1         | 0.61%   |
| Realtek                         | 1         | 0.61%   |
| Ralink Technology               | 1         | 0.61%   |
| Foxconn International           | 1         | 0.61%   |
| Chicony Electronics             | 1         | 0.61%   |
| Alps Electric                   | 1         | 0.61%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 33        | 19.88%  |
| Intel AX200 Bluetooth                               | 19        | 11.45%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 18        | 10.84%  |
| Intel AX201 Bluetooth                               | 18        | 10.84%  |
| Qualcomm Atheros  Bluetooth Device                  | 7         | 4.22%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7         | 4.22%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 5         | 3.01%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 1.81%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.81%   |
| IMC Networks Bluetooth Radio                        | 3         | 1.81%   |
| IMC Networks Bluetooth Device                       | 3         | 1.81%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 1.81%   |
| Foxconn / Hon Hai BCM20702A0                        | 3         | 1.81%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 1.81%   |
| Apple Bluetooth Host Controller                     | 3         | 1.81%   |
| TP-Link UB500 Adapter                               | 2         | 1.2%    |
| Realtek Bluetooth Radio                             | 2         | 1.2%    |
| Marvell Bluetooth and Wireless LAN Composite        | 2         | 1.2%    |
| Lite-On Bluetooth Device                            | 2         | 1.2%    |
| Intel AX210 Bluetooth                               | 2         | 1.2%    |
| IMC Networks Wireless_Device                        | 2         | 1.2%    |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 1.2%    |
| Broadcom BCM2045 Bluetooth                          | 2         | 1.2%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 1.2%    |
| Apple Bluetooth USB Host Controller                 | 2         | 1.2%    |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.6%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.6%    |
| Realtek Bluetooth Radio                             | 1         | 0.6%    |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.6%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.6%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.6%    |
| Lite-On Bluetooth Radio                             | 1         | 0.6%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.6%    |
| IMC Networks Bluetooth module                       | 1         | 0.6%    |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.6%    |
| Chicony Bluetooth Radio                             | 1         | 0.6%    |
| Broadcom Bluetooth                                  | 1         | 0.6%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 0.6%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 0.6%    |
| Alps Electric Bluetooth Adapter                     | 1         | 0.6%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 183       | 59.22%  |
| Nvidia                      | 56        | 18.12%  |
| AMD                         | 52        | 16.83%  |
| C-Media Electronics         | 2         | 0.65%   |
| Apple                       | 2         | 0.65%   |
| XMOS                        | 1         | 0.32%   |
| Unknown                     | 1         | 0.32%   |
| SteelSeries ApS             | 1         | 0.32%   |
| Sony                        | 1         | 0.32%   |
| Samson Technologies         | 1         | 0.32%   |
| Realtek Semiconductor       | 1         | 0.32%   |
| Razer USA                   | 1         | 0.32%   |
| Plantronics                 | 1         | 0.32%   |
| NXP Semiconductors          | 1         | 0.32%   |
| Micro Star International    | 1         | 0.32%   |
| Logitech                    | 1         | 0.32%   |
| Lenovo                      | 1         | 0.32%   |
| Kingston Technology         | 1         | 0.32%   |
| FiiO Electronics Technology | 1         | 0.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 26        | 7.1%    |
| AMD Family 17h/19h HD Audio Controller                                     | 25        | 6.83%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 16        | 4.37%   |
| Intel Cannon Lake PCH cAVS                                                 | 15        | 4.1%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13        | 3.55%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 13        | 3.55%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 12        | 3.28%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 10        | 2.73%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 10        | 2.73%   |
| Intel Comet Lake PCH-LP cAVS                                               | 9         | 2.46%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9         | 2.46%   |
| AMD Starship/Matisse HD Audio Controller                                   | 9         | 2.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8         | 2.19%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 8         | 2.19%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 2.19%   |
| Nvidia GP107GL High Definition Audio Controller                            | 6         | 1.64%   |
| Intel Haswell-ULT HD Audio Controller                                      | 6         | 1.64%   |
| Intel 8 Series HD Audio Controller                                         | 6         | 1.64%   |
| Intel 200 Series PCH HD Audio                                              | 6         | 1.64%   |
| Nvidia TU104 HD Audio Controller                                           | 5         | 1.37%   |
| Nvidia GF108 High Definition Audio Controller                              | 5         | 1.37%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 1.37%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 1.37%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 1.37%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5         | 1.37%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 1.09%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4         | 1.09%   |
| Nvidia GA104 High Definition Audio Controller                              | 4         | 1.09%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 1.09%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 1.09%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4         | 1.09%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 0.82%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 0.82%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 0.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 0.82%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 0.82%   |
| AMD Navi 10 HDMI Audio                                                     | 3         | 0.82%   |
| Nvidia MCP89 High Definition Audio                                         | 2         | 0.55%   |
| Nvidia High Definition Audio Controller                                    | 2         | 0.55%   |
| Nvidia GP108 High Definition Audio Controller                              | 2         | 0.55%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.55%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 0.55%   |
| Nvidia GP102 HDMI Audio Controller                                         | 2         | 0.55%   |
| Nvidia GM204 High Definition Audio Controller                              | 2         | 0.55%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.55%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2         | 0.55%   |
| Intel Jasper Lake HD Audio                                                 | 2         | 0.55%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 0.55%   |
| Intel CM238 HD Audio Controller                                            | 2         | 0.55%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 0.55%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2         | 0.55%   |
| Apple USB-C to 3.5mm Headphone Jack Adapter                                | 2         | 0.55%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 0.55%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2         | 0.55%   |
| XMOS iFi (by AMR) HD USB Audio                                             | 1         | 0.27%   |
| Unknown Realtek USB Audio Rear                                             | 1         | 0.27%   |
| Unknown Realtek USB Audio Front                                            | 1         | 0.27%   |
| SteelSeries ApS SteelSeries Arctis 5                                       | 1         | 0.27%   |
| Sony WALKMAN                                                               | 1         | 0.27%   |
| Samson Technologies Meteor condenser microphone                            | 1         | 0.27%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| SK Hynix                       | 38        | 24.36%  |
| Samsung Electronics            | 30        | 19.23%  |
| Micron Technology              | 22        | 14.1%   |
| Kingston                       | 17        | 10.9%   |
| Crucial                        | 10        | 6.41%   |
| Unknown                        | 5         | 3.21%   |
| G.Skill                        | 5         | 3.21%   |
| Corsair                        | 5         | 3.21%   |
| Transcend                      | 4         | 2.56%   |
| Ramaxel Technology             | 3         | 1.92%   |
| A-DATA Technology              | 3         | 1.92%   |
| Kingmax                        | 2         | 1.28%   |
| Elpida                         | 2         | 1.28%   |
| Unknown (ABCD)                 | 1         | 0.64%   |
| Unknown (0x02BA)               | 1         | 0.64%   |
| Undefi                         | 1         | 0.64%   |
| Qimonda                        | 1         | 0.64%   |
| Patriot                        | 1         | 0.64%   |
| Nanya Technology               | 1         | 0.64%   |
| MKF_SMBIOS_TYPE17_MANUFACTURER | 1         | 0.64%   |
| Lexar                          | 1         | 0.64%   |
| Klevv                          | 1         | 0.64%   |
| Essencore Limited              | 1         | 0.64%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s            | 3         | 1.82%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s  | 3         | 1.82%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 3         | 1.82%   |
| SK Hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 2         | 1.21%   |
| SK Hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s            | 2         | 1.21%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 2         | 1.21%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s           | 2         | 1.21%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s            | 2         | 1.21%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s             | 2         | 1.21%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s             | 2         | 1.21%   |
| Micron RAM MT52L512M32D2PF-10 4096MB Row Of Chips LPDDR3 1867MT/s | 2         | 1.21%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8192MB SODIMM DDR4 2400MT/s           | 2         | 1.21%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s             | 2         | 1.21%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s             | 2         | 1.21%   |
| Kingston RAM KY7N41-MIE 8192MB DIMM DDR4 2666MT/s                 | 2         | 1.21%   |
| Kingston RAM KHX1600C9D3/4GX 4096MB DIMM DDR3 2400MT/s            | 2         | 1.21%   |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1600MT/s             | 2         | 1.21%   |
| Kingmax RAM GLLG42F-DA--------- 8GB DIMM DDR4 2400MT/s            | 2         | 1.21%   |
| G.Skill RAM F4-3200C16-8GTZN 8GB DIMM DDR4 3200MT/s               | 2         | 1.21%   |
| Crucial RAM CT32G4SFD832A.C16FE 32GB SODIMM DDR4 3200MT/s         | 2         | 1.21%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                              | 1         | 0.61%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                              | 1         | 0.61%   |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s                  | 1         | 0.61%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                       | 1         | 0.61%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                    | 1         | 0.61%   |
| Unknown RAM Module 1GB SODIMM DDR3 1600MT/s                       | 1         | 0.61%   |
| Unknown RAM Module 16GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.61%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM DDR4 2400MT/s    | 1         | 0.61%   |
| Unknown (0x02BA) RAM Module 4096MB SODIMM DDR3 1333MT/s           | 1         | 0.61%   |
| Undefi RAM Module 4GB SODIMM DDR3 1866MT/s                        | 1         | 0.61%   |
| Transcend RAM TS1GSK64V3H 8192MB SODIMM DDR3 1333MT/s             | 1         | 0.61%   |
| Transcend RAM JM800QLU-2G 2048MB DIMM DDR2 2048MT/s               | 1         | 0.61%   |
| Transcend RAM JM3200HSB-16G 16GB SODIMM DDR4 3200MT/s             | 1         | 0.61%   |
| Transcend RAM JM1600KLH-8G 8GB DIMM DDR3 1600MT/s                 | 1         | 0.61%   |
| SK Hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 0.61%   |
| SK Hynix RAM HMT451U7AFR8A-PB 4GB DIMM DDR3 1600MT/s              | 1         | 0.61%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 1         | 0.61%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB DIMM DDR3 1600MT/s              | 1         | 0.61%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 1         | 0.61%   |
| SK Hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s              | 1         | 0.61%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s           | 1         | 0.61%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 1         | 0.61%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s         | 1         | 0.61%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 1         | 0.61%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s         | 1         | 0.61%   |
| SK Hynix RAM HMT125U6TFR8C-H9 2048MB DIMM DDR3 1333MT/s           | 1         | 0.61%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16GB Row Of Chips DDR4 3200MT/s     | 1         | 0.61%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s            | 1         | 0.61%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s      | 1         | 0.61%   |
| SK Hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s            | 1         | 0.61%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s        | 1         | 0.61%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s         | 1         | 0.61%   |
| SK Hynix RAM HMA451U6AFR8N-TF 4GB DIMM DDR4 2133MT/s              | 1         | 0.61%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s            | 1         | 0.61%   |
| SK Hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s    | 1         | 0.61%   |
| SK Hynix RAM H9HCNNNCPMALHR-NEE 8GB Row Of Chips LPDDR4 4800MT/s  | 1         | 0.61%   |
| Samsung RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s            | 1         | 0.61%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                       | 1         | 0.61%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                       | 1         | 0.61%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                   | 1         | 0.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 71        | 55.91%  |
| DDR3    | 38        | 29.92%  |
| LPDDR3  | 9         | 7.09%   |
| LPDDR4  | 4         | 3.15%   |
| SDRAM   | 2         | 1.57%   |
| DDR2    | 2         | 1.57%   |
| Unknown | 1         | 0.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 71        | 56.8%   |
| DIMM         | 38        | 30.4%   |
| Row Of Chips | 15        | 12%     |
| Chip         | 1         | 0.8%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 59        | 40.69%  |
| 4096  | 43        | 29.66%  |
| 16384 | 26        | 17.93%  |
| 2048  | 8         | 5.52%   |
| 32768 | 6         | 4.14%   |
| 1024  | 3         | 2.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 29        | 19.86%  |
| 3200  | 27        | 18.49%  |
| 2667  | 27        | 18.49%  |
| 2400  | 15        | 10.27%  |
| 2133  | 10        | 6.85%   |
| 1333  | 6         | 4.11%   |
| 3600  | 4         | 2.74%   |
| 2666  | 3         | 2.05%   |
| 1867  | 3         | 2.05%   |
| 1866  | 3         | 2.05%   |
| 1334  | 3         | 2.05%   |
| 4267  | 2         | 1.37%   |
| 3266  | 2         | 1.37%   |
| 2048  | 2         | 1.37%   |
| 1800  | 2         | 1.37%   |
| 4800  | 1         | 0.68%   |
| 4333  | 1         | 0.68%   |
| 4199  | 1         | 0.68%   |
| 2200  | 1         | 0.68%   |
| 2134  | 1         | 0.68%   |
| 1200  | 1         | 0.68%   |
| 1067  | 1         | 0.68%   |
| 667   | 1         | 0.68%   |

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
| Chicony Electronics                    | 32        | 21.77%  |
| IMC Networks                           | 23        | 15.65%  |
| Realtek Semiconductor                  | 17        | 11.56%  |
| Microdia                               | 15        | 10.2%   |
| Sunplus Innovation Technology          | 9         | 6.12%   |
| Apple                                  | 8         | 5.44%   |
| Logitech                               | 7         | 4.76%   |
| Acer                                   | 6         | 4.08%   |
| Suyin                                  | 5         | 3.4%    |
| Syntek                                 | 4         | 2.72%   |
| Samsung Electronics                    | 4         | 2.72%   |
| Lite-On Technology                     | 4         | 2.72%   |
| Silicon Motion                         | 2         | 1.36%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.68%   |
| Ricoh                                  | 1         | 0.68%   |
| Quanta                                 | 1         | 0.68%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.68%   |
| Microsoft                              | 1         | 0.68%   |
| Magic Control Technology               | 1         | 0.68%   |
| Luxvisions Innotech Limited            | 1         | 0.68%   |
| Lenovo                                 | 1         | 0.68%   |
| Intel                                  | 1         | 0.68%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 0.68%   |
| Alcor Micro                            | 1         | 0.68%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                              | 10        | 6.76%   |
| Chicony HD WebCam                                          | 8         | 5.41%   |
| IMC Networks Integrated Camera                             | 7         | 4.73%   |
| Chicony Integrated Camera                                  | 7         | 4.73%   |
| Realtek Integrated_Webcam_HD                               | 6         | 4.05%   |
| Sunplus Integrated_Webcam_HD                               | 5         | 3.38%   |
| IMC Networks USB2.0 HD UVC WebCam                          | 5         | 3.38%   |
| Samsung Galaxy A5 (MTP)                                    | 4         | 2.7%    |
| IMC Networks USB2.0 HD IR UVC WebCam                       | 4         | 2.7%    |
| Syntek Integrated Camera                                   | 3         | 2.03%   |
| Logitech HD Webcam C615                                    | 3         | 2.03%   |
| IMC Networks USB2.0 VGA UVC WebCam                         | 3         | 2.03%   |
| Chicony Lenovo Integrated Camera (0.3MP)                   | 3         | 2.03%   |
| Chicony HP HD Camera                                       | 3         | 2.03%   |
| Apple FaceTime HD Camera (Built-in)                        | 3         | 2.03%   |
| Realtek Integrated Webcam_HD                               | 2         | 1.35%   |
| Realtek Asus 2.0 USB Webcam                                | 2         | 1.35%   |
| Microdia Sonix USB 2.0 Camera                              | 2         | 1.35%   |
| Logitech C922 Pro Stream Webcam                            | 2         | 1.35%   |
| Lite-On HP Wide Vision HD Camera                           | 2         | 1.35%   |
| IMC Networks Lenovo EasyCamera                             | 2         | 1.35%   |
| Chicony USB2.0 Camera                                      | 2         | 1.35%   |
| Apple iPhone 5/5C/5S/6/SE                                  | 2         | 1.35%   |
| Apple FaceTime HD Camera                                   | 2         | 1.35%   |
| Acer Integrated Camera                                     | 2         | 1.35%   |
| Acer BisonCam, NB Pro                                      | 2         | 1.35%   |
| Syntek Lenovo EasyCamera                                   | 1         | 0.68%   |
| Suyin UVC HD Webcam                                        | 1         | 0.68%   |
| Suyin Laptop_Integrated_Webcam_HD                          | 1         | 0.68%   |
| Suyin HD Video WebCam                                      | 1         | 0.68%   |
| Suyin Asus Integrated Webcam                               | 1         | 0.68%   |
| Suyin Acer/Lenovo Webcam [CN0316]                          | 1         | 0.68%   |
| Sunplus TOSHIBA Web Camera - HD                            | 1         | 0.68%   |
| Sunplus Lenovo EasyCamera                                  | 1         | 0.68%   |
| Sunplus Laptop Integrated Webcam HD                        | 1         | 0.68%   |
| Sunplus HD User Facing                                     | 1         | 0.68%   |
| Sony Ericsson Mobile AB XQ-BQ72                            | 1         | 0.68%   |
| Silicon Motion WebCam SCB-1100N                            | 1         | 0.68%   |
| Silicon Motion WebCam SCB-0370N                            | 1         | 0.68%   |
| Ricoh Visual Communication Camera VGP-VCC6 [R5U870]        | 1         | 0.68%   |
| Realtek USB2.0 HD UVC WebCam                               | 1         | 0.68%   |
| Realtek USB Camera                                         | 1         | 0.68%   |
| Realtek USB Boot                                           | 1         | 0.68%   |
| Realtek Integrated Webcam HD                               | 1         | 0.68%   |
| Realtek HP Wide Vision FHD Camera                          | 1         | 0.68%   |
| Realtek HD Webcam - Realtek                                | 1         | 0.68%   |
| Realtek Asus laptop camera                                 | 1         | 0.68%   |
| Quanta HD User Facing                                      | 1         | 0.68%   |
| OnePlus (Shenzhen) A3000 phone (PTP mode, with debug) [3T] | 1         | 0.68%   |
| Microsoft Surface Camera Front                             | 1         | 0.68%   |
| Microdia USB 2.0 Camera                                    | 1         | 0.68%   |
| Microdia JOYACCESS JA-Webcam                               | 1         | 0.68%   |
| Microdia Integrated Webcam                                 | 1         | 0.68%   |
| Magic Control j5 WebCam JVCU100                            | 1         | 0.68%   |
| Luxvisions Innotech Limited Integrated Camera              | 1         | 0.68%   |
| Logitech Webcam C310                                       | 1         | 0.68%   |
| Logitech Webcam C270                                       | 1         | 0.68%   |
| Lite-On Integrated Camera                                  | 1         | 0.68%   |
| Lite-On HP IR Camera                                       | 1         | 0.68%   |
| Lite-On HP HD Camera                                       | 1         | 0.68%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 12        | 26.67%  |
| Validity Sensors           | 7         | 15.56%  |
| LighTuning Technology      | 6         | 13.33%  |
| AuthenTec                  | 6         | 13.33%  |
| Upek                       | 5         | 11.11%  |
| Shenzhen Goodix Technology | 5         | 11.11%  |
| Elan Microelectronics      | 4         | 8.89%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 8         | 17.78%  |
| LighTuning EgisTec Touch Fingerprint Sensor               | 6         | 13.33%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 5         | 11.11%  |
| Elan ELAN:Fingerprint                                     | 3         | 6.67%   |
| Validity Sensors VFS495 Fingerprint Reader                | 2         | 4.44%   |
| Validity Sensors Synaptics WBDI                           | 2         | 4.44%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 2         | 4.44%   |
| Shenzhen Goodix Fingerprint Reader                        | 2         | 4.44%   |
| Shenzhen Goodix FingerPrint                               | 2         | 4.44%   |
| AuthenTec AES2810                                         | 2         | 4.44%   |
| AuthenTec AES2501 Fingerprint Sensor                      | 2         | 4.44%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor         | 1         | 2.22%   |
| Validity Sensors VFS101 Fingerprint Reader                | 1         | 2.22%   |
| Validity Sensors VFS 5011 fingerprint sensor              | 1         | 2.22%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 2.22%   |
| Shenzhen Goodix  FingerPrint Device                       | 1         | 2.22%   |
| Elan ELAN:ARM-M4                                          | 1         | 2.22%   |
| AuthenTec Fingerprint Sensor                              | 1         | 2.22%   |
| AuthenTec AES1660 Fingerprint Sensor                      | 1         | 2.22%   |
| Unknown                                                   | 1         | 2.22%   |

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
| 0     | 160       | 63.24%  |
| 1     | 73        | 28.85%  |
| 2     | 17        | 6.72%   |
| 3     | 3         | 1.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 44        | 39.64%  |
| Graphics card            | 26        | 23.42%  |
| Net/wireless             | 14        | 12.61%  |
| Chipcard                 | 6         | 5.41%   |
| Multimedia controller    | 5         | 4.5%    |
| Net/ethernet             | 4         | 3.6%    |
| Communication controller | 3         | 2.7%    |
| Camera                   | 3         | 2.7%    |
| Network                  | 2         | 1.8%    |
| Wireless                 | 1         | 0.9%    |
| Unassigned class         | 1         | 0.9%    |
| Firewire controller      | 1         | 0.9%    |
| Bluetooth                | 1         | 0.9%    |


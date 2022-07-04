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

Total: 226

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 42        | 25.77%  |
| Ubuntu 18.04                 | 17        | 10.43%  |
| Fedora 33                    | 10        | 6.13%   |
| Pop!_OS 20.04                | 5         | 3.07%   |
| Arch                         | 5         | 3.07%   |
| Ubuntu 22.04                 | 4         | 2.45%   |
| Xubuntu 20.04                | 3         | 1.84%   |
| Linux Mint 20                | 3         | 1.84%   |
| Fedora 32                    | 3         | 1.84%   |
| Debian 11                    | 3         | 1.84%   |
| Arch Rolling                 | 3         | 1.84%   |
| Zorin 16                     | 2         | 1.23%   |
| Zorin 15                     | 2         | 1.23%   |
| Ubuntu 21.10                 | 2         | 1.23%   |
| Pop!_OS 22.04                | 2         | 1.23%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 1.23%   |
| OpenMandriva 4.3             | 2         | 1.23%   |
| Manjaro 20.1                 | 2         | 1.23%   |
| Kubuntu 20.10                | 2         | 1.23%   |
| Gentoo 2.6                   | 2         | 1.23%   |
| Fedora 36                    | 2         | 1.23%   |
| Fedora 35                    | 2         | 1.23%   |
| Fedora 34                    | 2         | 1.23%   |
| Fedora 31                    | 2         | 1.23%   |
| ArcoLinux Rolling            | 2         | 1.23%   |
| Xubuntu 21.04                | 1         | 0.61%   |
| Ubuntu Budgie 20.04          | 1         | 0.61%   |
| Ubuntu 21.04                 | 1         | 0.61%   |
| Ubuntu 19.10                 | 1         | 0.61%   |
| Ubuntu 19.04                 | 1         | 0.61%   |
| Ubuntu 18.10                 | 1         | 0.61%   |
| Ubuntu 16.04                 | 1         | 0.61%   |
| ROSA R8                      | 1         | 0.61%   |
| ROSA R11                     | 1         | 0.61%   |
| RHEL 8                       | 1         | 0.61%   |
| RHEL 7                       | 1         | 0.61%   |
| Q4OS 4                       | 1         | 0.61%   |
| Pop!_OS 21.10                | 1         | 0.61%   |
| Pop!_OS 21.04                | 1         | 0.61%   |
| Pop!_OS 20.10                | 1         | 0.61%   |
| OpenMandriva 4.2             | 1         | 0.61%   |
| OpenMandriva 4.1             | 1         | 0.61%   |
| Manjaro 21.3.0               | 1         | 0.61%   |
| Manjaro 20.2                 | 1         | 0.61%   |
| Manjaro 18.0.4               | 1         | 0.61%   |
| Lubuntu 20.04                | 1         | 0.61%   |
| Lubuntu 18.04                | 1         | 0.61%   |
| LMDE 4                       | 1         | 0.61%   |
| Linux Mint 20.3              | 1         | 0.61%   |
| Linux Mint 20.1              | 1         | 0.61%   |
| Kubuntu 20.04                | 1         | 0.61%   |
| KDE neon 20.04               | 1         | 0.61%   |
| Kali 2020.3                  | 1         | 0.61%   |
| Garuda Linux Soaring         | 1         | 0.61%   |
| Endless 3.6.0                | 1         | 0.61%   |
| Endless 3.3.16-nexthw1       | 1         | 0.61%   |
| Deepin 20                    | 1         | 0.61%   |
| Debian Unstable              | 1         | 0.61%   |
| Debian Testing               | 1         | 0.61%   |
| Debian 10                    | 1         | 0.61%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 69        | 44.23%  |
| Fedora        | 18        | 11.54%  |
| Pop!_OS       | 10        | 6.41%   |
| Arch          | 7         | 4.49%   |
| Debian        | 6         | 3.85%   |
| Zorin         | 4         | 2.56%   |
| Xubuntu       | 4         | 2.56%   |
| OpenMandriva  | 4         | 2.56%   |
| Manjaro       | 4         | 2.56%   |
| Linux Mint    | 4         | 2.56%   |
| Kubuntu       | 3         | 1.92%   |
| ROSA          | 2         | 1.28%   |
| RHEL          | 2         | 1.28%   |
| openSUSE      | 2         | 1.28%   |
| Lubuntu       | 2         | 1.28%   |
| Gentoo        | 2         | 1.28%   |
| Endless       | 2         | 1.28%   |
| Clear Linux   | 2         | 1.28%   |
| ArcoLinux     | 2         | 1.28%   |
| Ubuntu Budgie | 1         | 0.64%   |
| Q4OS          | 1         | 0.64%   |
| LMDE          | 1         | 0.64%   |
| KDE neon      | 1         | 0.64%   |
| Kali          | 1         | 0.64%   |
| Garuda Linux  | 1         | 0.64%   |
| Deepin        | 1         | 0.64%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.4.0-48-generic        | 5         | 2.76%   |
| 5.9.8-200.fc33.x86_64   | 4         | 2.21%   |
| 5.4.0-42-generic        | 4         | 2.21%   |
| 5.4.0-40-generic        | 4         | 2.21%   |
| 5.3.0-62-generic        | 4         | 2.21%   |
| 5.11.0-43-generic       | 4         | 2.21%   |
| 5.4.0-65-generic        | 3         | 1.66%   |
| 5.4.0-52-generic        | 3         | 1.66%   |
| 5.4.0-47-generic        | 3         | 1.66%   |
| 5.4.0-37-generic        | 3         | 1.66%   |
| 5.4.0-29-generic        | 3         | 1.66%   |
| 5.13.0-28-generic       | 3         | 1.66%   |
| 5.11.0-38-generic       | 3         | 1.66%   |
| 5.4.5-050405-generic    | 2         | 1.1%    |
| 5.4.0-7634-generic      | 2         | 1.1%    |
| 5.4.0-31-generic        | 2         | 1.1%    |
| 5.4.0-26-generic        | 2         | 1.1%    |
| 5.17.5-76051705-generic | 2         | 1.1%    |
| 5.16.7-desktop-1omv4003 | 2         | 1.1%    |
| 5.13.0-40-generic       | 2         | 1.1%    |
| 5.13.0-37-generic       | 2         | 1.1%    |
| 5.11.0-37-generic       | 2         | 1.1%    |
| 5.11.0-25-generic       | 2         | 1.1%    |
| 5.0.0-23-generic        | 2         | 1.1%    |
| 4.18.0-15-generic       | 2         | 1.1%    |
| 5.9.9-200.fc33.x86_64   | 1         | 0.55%   |
| 5.9.16-200.fc33.x86_64  | 1         | 0.55%   |
| 5.9.15-200.fc33.x86_64  | 1         | 0.55%   |
| 5.9.10-arch1-1          | 1         | 0.55%   |
| 5.8.7-1-default         | 1         | 0.55%   |
| 5.8.5-arch1-1           | 1         | 0.55%   |
| 5.8.4-1-default         | 1         | 0.55%   |
| 5.8.3-arch1-1           | 1         | 0.55%   |
| 5.8.12-200.fc32.x86_64  | 1         | 0.55%   |
| 5.8.11-200.fc32.x86_64  | 1         | 0.55%   |
| 5.8.0-7630-generic      | 1         | 0.55%   |
| 5.8.0-63-generic        | 1         | 0.55%   |
| 5.8.0-55-generic        | 1         | 0.55%   |
| 5.8.0-53-generic        | 1         | 0.55%   |
| 5.8.0-50-generic        | 1         | 0.55%   |
| 5.8.0-48-generic        | 1         | 0.55%   |
| 5.8.0-45-generic        | 1         | 0.55%   |
| 5.8.0-44-generic        | 1         | 0.55%   |
| 5.8.0-43-generic        | 1         | 0.55%   |
| 5.8.0-41-generic        | 1         | 0.55%   |
| 5.8.0-38-generic        | 1         | 0.55%   |
| 5.8.0-33-generic        | 1         | 0.55%   |
| 5.8.0-29-generic        | 1         | 0.55%   |
| 5.7.0-kali3-amd64       | 1         | 0.55%   |
| 5.6.7-050607-generic    | 1         | 0.55%   |
| 5.6.5-941.native        | 1         | 0.55%   |
| 5.6.15-300.fc32.x86_64  | 1         | 0.55%   |
| 5.6.0-1047-oem          | 1         | 0.55%   |
| 5.5.2-050502-generic    | 1         | 0.55%   |
| 5.5.0-desktop-1omv4001  | 1         | 0.55%   |
| 5.4.8-200.fc31.x86_64   | 1         | 0.55%   |
| 5.4.78-1-MANJARO        | 1         | 0.55%   |
| 5.4.70-amd64-desktop    | 1         | 0.55%   |
| 5.4.60-2-MANJARO        | 1         | 0.55%   |
| 5.4.12-200.fc31.x86_64  | 1         | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 37        | 21.51%  |
| 5.11.0  | 13        | 7.56%   |
| 5.8.0   | 11        | 6.4%    |
| 5.13.0  | 10        | 5.81%   |
| 5.3.0   | 7         | 4.07%   |
| 4.18.0  | 7         | 4.07%   |
| 4.15.0  | 7         | 4.07%   |
| 5.9.8   | 4         | 2.33%   |
| 5.15.0  | 4         | 2.33%   |
| 5.10.0  | 4         | 2.33%   |
| 5.0.0   | 4         | 2.33%   |
| 5.4.5   | 2         | 1.16%   |
| 5.17.5  | 2         | 1.16%   |
| 5.16.7  | 2         | 1.16%   |
| 5.13.13 | 2         | 1.16%   |
| 4.19.0  | 2         | 1.16%   |
| 5.9.9   | 1         | 0.58%   |
| 5.9.16  | 1         | 0.58%   |
| 5.9.15  | 1         | 0.58%   |
| 5.9.10  | 1         | 0.58%   |
| 5.8.7   | 1         | 0.58%   |
| 5.8.5   | 1         | 0.58%   |
| 5.8.4   | 1         | 0.58%   |
| 5.8.3   | 1         | 0.58%   |
| 5.8.12  | 1         | 0.58%   |
| 5.8.11  | 1         | 0.58%   |
| 5.7.0   | 1         | 0.58%   |
| 5.6.7   | 1         | 0.58%   |
| 5.6.5   | 1         | 0.58%   |
| 5.6.15  | 1         | 0.58%   |
| 5.6.0   | 1         | 0.58%   |
| 5.5.2   | 1         | 0.58%   |
| 5.5.0   | 1         | 0.58%   |
| 5.4.8   | 1         | 0.58%   |
| 5.4.78  | 1         | 0.58%   |
| 5.4.70  | 1         | 0.58%   |
| 5.4.60  | 1         | 0.58%   |
| 5.4.12  | 1         | 0.58%   |
| 5.18.7  | 1         | 0.58%   |
| 5.18.5  | 1         | 0.58%   |
| 5.18.0  | 1         | 0.58%   |
| 5.17.9  | 1         | 0.58%   |
| 5.17.6  | 1         | 0.58%   |
| 5.16.9  | 1         | 0.58%   |
| 5.16.8  | 1         | 0.58%   |
| 5.16.15 | 1         | 0.58%   |
| 5.16.0  | 1         | 0.58%   |
| 5.15.5  | 1         | 0.58%   |
| 5.15.32 | 1         | 0.58%   |
| 5.15.1  | 1         | 0.58%   |
| 5.14.10 | 1         | 0.58%   |
| 5.13.9  | 1         | 0.58%   |
| 5.13.7  | 1         | 0.58%   |
| 5.13.4  | 1         | 0.58%   |
| 5.13.12 | 1         | 0.58%   |
| 5.12.6  | 1         | 0.58%   |
| 5.12.14 | 1         | 0.58%   |
| 5.12.1  | 1         | 0.58%   |
| 5.11.2  | 1         | 0.58%   |
| 5.10.8  | 1         | 0.58%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 43        | 25.29%  |
| 5.8     | 17        | 10%     |
| 5.13    | 16        | 9.41%   |
| 5.11    | 14        | 8.24%   |
| 5.10    | 10        | 5.88%   |
| 5.9     | 7         | 4.12%   |
| 5.3     | 7         | 4.12%   |
| 5.15    | 7         | 4.12%   |
| 4.18    | 7         | 4.12%   |
| 4.15    | 7         | 4.12%   |
| 5.16    | 6         | 3.53%   |
| 5.0     | 5         | 2.94%   |
| 5.6     | 4         | 2.35%   |
| 5.17    | 4         | 2.35%   |
| 5.18    | 3         | 1.76%   |
| 5.12    | 3         | 1.76%   |
| 4.19    | 3         | 1.76%   |
| 5.5     | 2         | 1.18%   |
| 5.7     | 1         | 0.59%   |
| 5.14    | 1         | 0.59%   |
| 4.4     | 1         | 0.59%   |
| 4.16    | 1         | 0.59%   |
| 3.10    | 1         | 0.59%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 147       | 98.66%  |
| i686   | 2         | 1.34%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 93        | 58.49%  |
| KDE5            | 20        | 12.58%  |
| Unknown         | 18        | 11.32%  |
| X-Cinnamon      | 6         | 3.77%   |
| XFCE            | 5         | 3.14%   |
| KDE             | 5         | 3.14%   |
| LXQt            | 3         | 1.89%   |
| Cinnamon        | 3         | 1.89%   |
| Unity           | 1         | 0.63%   |
| KDE4            | 1         | 0.63%   |
| i3              | 1         | 0.63%   |
| GNOME Flashback | 1         | 0.63%   |
| GNOME Classic   | 1         | 0.63%   |
| Budgie          | 1         | 0.63%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 120       | 77.92%  |
| Wayland | 17        | 11.04%  |
| Unknown | 12        | 7.79%   |
| Tty     | 5         | 3.25%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 81        | 51.59%  |
| GDM     | 34        | 21.66%  |
| SDDM    | 21        | 13.38%  |
| GDM3    | 12        | 7.64%   |
| TDM     | 4         | 2.55%   |
| LightDM | 4         | 2.55%   |
| KDM     | 1         | 0.64%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_SG   | 61        | 40.13%  |
| en_US   | 59        | 38.82%  |
| Unknown | 15        | 9.87%   |
| en_IN   | 4         | 2.63%   |
| de_DE   | 3         | 1.97%   |
| zh_CN   | 2         | 1.32%   |
| en_GB   | 2         | 1.32%   |
| en_AU   | 2         | 1.32%   |
| C       | 2         | 1.32%   |
| ru_UA   | 1         | 0.66%   |
| en_IE   | 1         | 0.66%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 108       | 72%     |
| BIOS | 42        | 28%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 125       | 82.78%  |
| Btrfs   | 11        | 7.28%   |
| Unknown | 7         | 4.64%   |
| Overlay | 4         | 2.65%   |
| Zfs     | 2         | 1.32%   |
| Xfs     | 2         | 1.32%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 86        | 56.95%  |
| GPT     | 63        | 41.72%  |
| MBR     | 2         | 1.32%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 136       | 88.89%  |
| Yes       | 17        | 11.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 94        | 62.67%  |
| Yes       | 56        | 37.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 42        | 28.19%  |
| Dell                   | 30        | 20.13%  |
| ASUSTek Computer       | 25        | 16.78%  |
| Acer                   | 18        | 12.08%  |
| Hewlett-Packard        | 10        | 6.71%   |
| Apple                  | 6         | 4.03%   |
| Sony                   | 3         | 2.01%   |
| Toshiba                | 2         | 1.34%   |
| Samsung Electronics    | 2         | 1.34%   |
| Foxconn                | 2         | 1.34%   |
| Aftershock             | 2         | 1.34%   |
| Razer                  | 1         | 0.67%   |
| Notebook               | 1         | 0.67%   |
| MSI                    | 1         | 0.67%   |
| MECHREVO               | 1         | 0.67%   |
| Fujitsu                | 1         | 0.67%   |
| COPELION INTERNATIONAL | 1         | 0.67%   |
| AMI                    | 1         | 0.67%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Lenovo ThinkPad X220 42911H8                          | 2         | 1.34%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ                      | 2         | 1.34%   |
| Lenovo IdeaPad S340-14API 81NB                        | 2         | 1.34%   |
| HP Compaq 6510b                                       | 2         | 1.34%   |
| Foxconn Kangaroo Mobile Desktop                       | 2         | 1.34%   |
| ASUS T300LA                                           | 2         | 1.34%   |
| Acer ConceptD CN715-71                                | 2         | 1.34%   |
| Toshiba PORTEGE Z10t-A                                | 1         | 0.67%   |
| Toshiba PORTEGE R930                                  | 1         | 0.67%   |
| Sony VPCSB36FG                                        | 1         | 0.67%   |
| Sony VPCCA15FG                                        | 1         | 0.67%   |
| Sony VGN-CR32G_W                                      | 1         | 0.67%   |
| Samsung RF510/RF410/RF710                             | 1         | 0.67%   |
| Samsung 305U1A                                        | 1         | 0.67%   |
| Razer Blade 15 Advanced Model (Early 2020) - RZ09-033 | 1         | 0.67%   |
| Notebook P65_P67SE                                    | 1         | 0.67%   |
| MSI GE63VR 7RE                                        | 1         | 0.67%   |
| MECHREVO Code 01 Series PF5NU1G                       | 1         | 0.67%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS                    | 1         | 0.67%   |
| Lenovo Yoga 3 Pro-1370 80HE                           | 1         | 0.67%   |
| Lenovo Yoga 3 14 80JH                                 | 1         | 0.67%   |
| Lenovo ThinkPad X395 20NL000TCD                       | 1         | 0.67%   |
| Lenovo ThinkPad X240 20AMS00100                       | 1         | 0.67%   |
| Lenovo ThinkPad X230 23257VA                          | 1         | 0.67%   |
| Lenovo ThinkPad X220 Tablet 4298WBT                   | 1         | 0.67%   |
| Lenovo ThinkPad X220 4286C11                          | 1         | 0.67%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QVCTO1WW             | 1         | 0.67%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9005TSG            | 1         | 0.67%   |
| Lenovo ThinkPad X1 Carbon 6th EX480SIT13              | 1         | 0.67%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGCTO1WW              | 1         | 0.67%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRCTO1WW              | 1         | 0.67%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQCTO1WW              | 1         | 0.67%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A8S0WE01              | 1         | 0.67%   |
| Lenovo ThinkPad W540 20BG001KUK                       | 1         | 0.67%   |
| Lenovo ThinkPad T490 20N3S5DU27                       | 1         | 0.67%   |
| Lenovo ThinkPad T420s 417429U                         | 1         | 0.67%   |
| Lenovo ThinkPad T400 2768CJ6                          | 1         | 0.67%   |
| Lenovo ThinkPad T400 2768AA6                          | 1         | 0.67%   |
| Lenovo ThinkPad T14s Gen 1 20UHCTO1WW                 | 1         | 0.67%   |
| Lenovo ThinkPad P14s Gen 1 20S4A001CD                 | 1         | 0.67%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F45V                   | 1         | 0.67%   |
| Lenovo ThinkPad L460 20FUCTO1WW                       | 1         | 0.67%   |
| Lenovo ThinkPad E14 20RA0058VA                        | 1         | 0.67%   |
| Lenovo ThinkBook 14p Gen 2 20YN                       | 1         | 0.67%   |
| Lenovo S20-30 20421                                   | 1         | 0.67%   |
| Lenovo Legion 7 16ACHg6 82N6                          | 1         | 0.67%   |
| Lenovo Legion 5 15ARH05 82B5                          | 1         | 0.67%   |
| Lenovo IdeaPad U460 20056                             | 1         | 0.67%   |
| Lenovo IdeaPad S530 13IML 81WU                        | 1         | 0.67%   |
| Lenovo IdeaPad 5 14ITL05 82FE                         | 1         | 0.67%   |
| Lenovo IdeaPad 100-14IBY 80MH                         | 1         | 0.67%   |
| Lenovo G550 2958                                      | 1         | 0.67%   |
| Lenovo B50-30 20382                                   | 1         | 0.67%   |
| Lenovo 14w 81MQS02H00                                 | 1         | 0.67%   |
| HP ZBook Studio G5                                    | 1         | 0.67%   |
| HP ProBook 440 G4                                     | 1         | 0.67%   |
| HP Pavilion Sleekbook 14 PC                           | 1         | 0.67%   |
| HP Pavilion Laptop 14-ec0xxx                          | 1         | 0.67%   |
| HP Pavilion dv6000 (GF659EA#ABF)                      | 1         | 0.67%   |
| HP Pavilion Aero Laptop 13-be0xxx                     | 1         | 0.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Lenovo ThinkPad           | 24        | 16.11%  |
| Dell Inspiron             | 11        | 7.38%   |
| Dell XPS                  | 8         | 5.37%   |
| Dell Latitude             | 8         | 5.37%   |
| Lenovo IdeaPad            | 6         | 4.03%   |
| ASUS VivoBook             | 6         | 4.03%   |
| Acer Swift                | 6         | 4.03%   |
| Acer Aspire               | 6         | 4.03%   |
| Lenovo Legion             | 4         | 2.68%   |
| HP Pavilion               | 4         | 2.68%   |
| ASUS ZenBook              | 4         | 2.68%   |
| Lenovo Yoga               | 3         | 2.01%   |
| Toshiba PORTEGE           | 2         | 1.34%   |
| HP EliteBook              | 2         | 1.34%   |
| HP Compaq                 | 2         | 1.34%   |
| Foxconn Kangaroo          | 2         | 1.34%   |
| Dell Precision            | 2         | 1.34%   |
| ASUS TUF                  | 2         | 1.34%   |
| ASUS T300LA               | 2         | 1.34%   |
| Apple MacBookPro11        | 2         | 1.34%   |
| Acer Predator             | 2         | 1.34%   |
| Acer ConceptD             | 2         | 1.34%   |
| Sony VPCSB36FG            | 1         | 0.67%   |
| Sony VPCCA15FG            | 1         | 0.67%   |
| Sony VGN-CR32G            | 1         | 0.67%   |
| Samsung RF510             | 1         | 0.67%   |
| Samsung 305U1A            | 1         | 0.67%   |
| Razer Blade               | 1         | 0.67%   |
| Notebook P65              | 1         | 0.67%   |
| MSI GE63VR                | 1         | 0.67%   |
| MECHREVO Code             | 1         | 0.67%   |
| Lenovo ThinkBook          | 1         | 0.67%   |
| Lenovo S20-30             | 1         | 0.67%   |
| Lenovo G550               | 1         | 0.67%   |
| Lenovo B50-30             | 1         | 0.67%   |
| Lenovo 14w                | 1         | 0.67%   |
| HP ZBook                  | 1         | 0.67%   |
| HP ProBook                | 1         | 0.67%   |
| Fujitsu LIFEBOOK          | 1         | 0.67%   |
| Dell G3                   | 1         | 0.67%   |
| COPELION INTERNATIONAL ZX | 1         | 0.67%   |
| ASUS X406UAR              | 1         | 0.67%   |
| ASUS UX32LA               | 1         | 0.67%   |
| ASUS UX305CA              | 1         | 0.67%   |
| ASUS U24E                 | 1         | 0.67%   |
| ASUS S500CA               | 1         | 0.67%   |
| ASUS ROG                  | 1         | 0.67%   |
| ASUS N501JW               | 1         | 0.67%   |
| ASUS K501UX               | 1         | 0.67%   |
| ASUS K45VM                | 1         | 0.67%   |
| ASUS GL552VW              | 1         | 0.67%   |
| ASUS ASUS                 | 1         | 0.67%   |
| Apple MacBookPro9         | 1         | 0.67%   |
| Apple MacBookPro8         | 1         | 0.67%   |
| Apple MacBookPro7         | 1         | 0.67%   |
| Apple MacBookAir3         | 1         | 0.67%   |
| AMI Intel                 | 1         | 0.67%   |
| Aftershock N8xxEP6        | 1         | 0.67%   |
| Aftershock N15            | 1         | 0.67%   |
| Acer Nitro                | 1         | 0.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 24        | 16.11%  |
| 2020 | 19        | 12.75%  |
| 2018 | 17        | 11.41%  |
| 2021 | 15        | 10.07%  |
| 2014 | 11        | 7.38%   |
| 2011 | 11        | 7.38%   |
| 2017 | 9         | 6.04%   |
| 2015 | 9         | 6.04%   |
| 2016 | 8         | 5.37%   |
| 2012 | 8         | 5.37%   |
| 2010 | 5         | 3.36%   |
| 2008 | 4         | 2.68%   |
| 2007 | 4         | 2.68%   |
| 2009 | 3         | 2.01%   |
| 2013 | 2         | 1.34%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 149       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 127       | 84.67%  |
| Enabled  | 23        | 15.33%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 149       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 39        | 25.66%  |
| 4.01-8.0    | 35        | 23.03%  |
| 3.01-4.0    | 25        | 16.45%  |
| 8.01-16.0   | 24        | 15.79%  |
| 32.01-64.0  | 16        | 10.53%  |
| 1.01-2.0    | 6         | 3.95%   |
| 64.01-256.0 | 3         | 1.97%   |
| 24.01-32.0  | 2         | 1.32%   |
| 2.01-3.0    | 2         | 1.32%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 50        | 28.9%   |
| 2.01-3.0   | 41        | 23.7%   |
| 4.01-8.0   | 36        | 20.81%  |
| 3.01-4.0   | 25        | 14.45%  |
| 8.01-16.0  | 10        | 5.78%   |
| 0.51-1.0   | 9         | 5.2%    |
| 16.01-24.0 | 1         | 0.58%   |
| 0.01-0.5   | 1         | 0.58%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 107       | 69.93%  |
| 2      | 39        | 25.49%  |
| 3      | 6         | 3.92%   |
| 0      | 1         | 0.65%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 121       | 80.67%  |
| Yes       | 29        | 19.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 97        | 64.67%  |
| No        | 53        | 35.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 145       | 97.32%  |
| No        | 4         | 2.68%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 124       | 82.67%  |
| No        | 26        | 17.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Singapore | 149       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Singapore            | 141       | 94.63%  |
| Jurong West          | 4         | 2.68%   |
| Sembawang Estate     | 1         | 0.67%   |
| Queenstown Estate    | 1         | 0.67%   |
| Kampong Ulu Jurong   | 1         | 0.67%   |
| Bukit Batok New Town | 1         | 0.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 41        | 56     | 21.58%  |
| Seagate             | 19        | 22     | 10%     |
| SanDisk             | 16        | 17     | 8.42%   |
| WDC                 | 15        | 34     | 7.89%   |
| SK hynix            | 13        | 14     | 6.84%   |
| Unknown             | 12        | 14     | 6.32%   |
| Toshiba             | 12        | 16     | 6.32%   |
| Intel               | 8         | 10     | 4.21%   |
| HGST                | 8         | 12     | 4.21%   |
| Hitachi             | 6         | 6      | 3.16%   |
| Phison              | 4         | 6      | 2.11%   |
| Micron Technology   | 4         | 5      | 2.11%   |
| Apple               | 4         | 4      | 2.11%   |
| Kingston            | 3         | 4      | 1.58%   |
| LITEON              | 2         | 3      | 1.05%   |
| Lexar               | 2         | 2      | 1.05%   |
| Lenovo              | 2         | 2      | 1.05%   |
| KIOXIA              | 2         | 2      | 1.05%   |
| JMicron Technology  | 2         | 2      | 1.05%   |
| Hewlett-Packard     | 2         | 3      | 1.05%   |
| China               | 2         | 2      | 1.05%   |
| UMIS                | 1         | 1      | 0.53%   |
| TO Exter            | 1         | 1      | 0.53%   |
| SPCC                | 1         | 1      | 0.53%   |
| OCZ                 | 1         | 1      | 0.53%   |
| INTEL SS            | 1         | 1      | 0.53%   |
| Fujitsu             | 1         | 1      | 0.53%   |
| External            | 1         | 1      | 0.53%   |
| CT1000MX            | 1         | 2      | 0.53%   |
| Crucial             | 1         | 1      | 0.53%   |
| Corsair             | 1         | 2      | 0.53%   |
| A-DATA Technology   | 1         | 1      | 0.53%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB            | 6         | 3.06%   |
| SanDisk NVMe SSD Drive 512GB              | 3         | 1.53%   |
| HGST HTS721010A9E630 1TB                  | 3         | 1.53%   |
| WDC WDS500G2X0C-00L350 500GB              | 2         | 1.02%   |
| WDC WDS100T2X0C-00L350 1TB                | 2         | 1.02%   |
| WDC PC SN720 SED SDAQNTW-1T00 1TB         | 2         | 1.02%   |
| Unknown MMC Card  64GB                    | 2         | 1.02%   |
| Unknown MMC Card  32GB                    | 2         | 1.02%   |
| Toshiba MQ04ABF100 1TB                    | 2         | 1.02%   |
| Toshiba MQ01ABD100 1TB                    | 2         | 1.02%   |
| Toshiba MK5055GSX 500GB                   | 2         | 1.02%   |
| SK hynix SKHynix_HFS001TDE9X084N 1TB      | 2         | 1.02%   |
| SK hynix HFM512GDJTNG-8310A 512GB         | 2         | 1.02%   |
| Seagate ST1000LM049-2GH172 1TB            | 2         | 1.02%   |
| SanDisk SSD PLUS 240GB                    | 2         | 1.02%   |
| SanDisk SD6SN1M128G1002 128GB SSD         | 2         | 1.02%   |
| Samsung SSD 860 EVO 500GB                 | 2         | 1.02%   |
| Samsung SSD 860 EVO 250GB                 | 2         | 1.02%   |
| Samsung SSD 850 EVO 500GB                 | 2         | 1.02%   |
| Samsung SSD 840 EVO 250GB                 | 2         | 1.02%   |
| Samsung NVMe SSD Drive 512GB              | 2         | 1.02%   |
| Samsung NVMe SSD Drive 1024GB             | 2         | 1.02%   |
| Samsung MZVLB1T0HBLR-000L7 1TB            | 2         | 1.02%   |
| JMicron Generic 2TB                       | 2         | 1.02%   |
| Intel NVMe SSD Drive 512GB                | 2         | 1.02%   |
| Intel NVMe SSD Drive 1024GB               | 2         | 1.02%   |
| HGST HTS725050A7E630 500GB                | 2         | 1.02%   |
| HGST HTS545050A7E380 500GB                | 2         | 1.02%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD          | 1         | 0.51%   |
| WDC WDS100T3X0C-00SJG0 1TB                | 1         | 0.51%   |
| WDC WDS100T2B0B-00YS70 1TB SSD            | 1         | 0.51%   |
| WDC WD7500BPVT-80HXZT3 752GB              | 1         | 0.51%   |
| WDC WD5000LPLX-60ZNTT1 500GB              | 1         | 0.51%   |
| WDC WD3200BEVT-22ZCT0 320GB               | 1         | 0.51%   |
| WDC WD10SPZX-21Z10T0 1TB                  | 1         | 0.51%   |
| WDC WD10JPVX-22JC3T0 1TB                  | 1         | 0.51%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB        | 1         | 0.51%   |
| WDC PC SN730 NVMe 256GB                   | 1         | 0.51%   |
| WDC PC SN520 SDAPMUW-512G-1101 512GB      | 1         | 0.51%   |
| Unknown SN256  256GB                      | 1         | 0.51%   |
| Unknown SEM64G  64GB                      | 1         | 0.51%   |
| Unknown SD/MMC 16GB                       | 1         | 0.51%   |
| Unknown SD  32GB                          | 1         | 0.51%   |
| Unknown SB32G  32GB                       | 1         | 0.51%   |
| Unknown NVMe SSD Drive 512GB              | 1         | 0.51%   |
| Unknown NVMe SSD Drive 1024GB             | 1         | 0.51%   |
| Unknown MMC Card  67GB                    | 1         | 0.51%   |
| Unknown MMC Card  394GB                   | 1         | 0.51%   |
| Unknown DA4128  128GB                     | 1         | 0.51%   |
| UMIS RPFTJ256PDD2MWX 256GB                | 1         | 0.51%   |
| Toshiba THNSNF128GMCS 128GB SSD           | 1         | 0.51%   |
| Toshiba MQ02ABD100H 1TB                   | 1         | 0.51%   |
| Toshiba MQ01ABD050 500GB                  | 1         | 0.51%   |
| Toshiba KXG50ZNV512G NVMe 512GB           | 1         | 0.51%   |
| Toshiba KXG50ZNV256G NVMe 256GB           | 1         | 0.51%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD       | 1         | 0.51%   |
| TO Exter nal USB 3.0 256GB                | 1         | 0.51%   |
| SPCC M.2 SSD 256GB                        | 1         | 0.51%   |
| SK hynix SKHynix_HFS512GDE9X084N 512GB    | 1         | 0.51%   |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB | 1         | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 21     | 36%     |
| Toshiba             | 8         | 12     | 16%     |
| HGST                | 8         | 12     | 16%     |
| Hitachi             | 6         | 6      | 12%     |
| WDC                 | 5         | 7      | 10%     |
| JMicron Technology  | 2         | 2      | 4%      |
| Samsung Electronics | 1         | 3      | 2%      |
| Fujitsu             | 1         | 1      | 2%      |
| Apple               | 1         | 1      | 2%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 24        | 32     | 41.38%  |
| SanDisk             | 10        | 10     | 17.24%  |
| Apple               | 3         | 3      | 5.17%   |
| WDC                 | 2         | 3      | 3.45%   |
| SK hynix            | 2         | 2      | 3.45%   |
| Micron Technology   | 2         | 3      | 3.45%   |
| LITEON              | 2         | 3      | 3.45%   |
| Kingston            | 2         | 3      | 3.45%   |
| China               | 2         | 2      | 3.45%   |
| Toshiba             | 1         | 1      | 1.72%   |
| TO Exter            | 1         | 1      | 1.72%   |
| SPCC                | 1         | 1      | 1.72%   |
| OCZ                 | 1         | 1      | 1.72%   |
| Lexar               | 1         | 1      | 1.72%   |
| INTEL SS            | 1         | 1      | 1.72%   |
| Hewlett-Packard     | 1         | 2      | 1.72%   |
| CT1000MX            | 1         | 2      | 1.72%   |
| Crucial             | 1         | 1      | 1.72%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 67        | 100    | 37.02%  |
| SSD     | 55        | 72     | 30.39%  |
| HDD     | 49        | 65     | 27.07%  |
| MMC     | 9         | 11     | 4.97%   |
| Unknown | 1         | 1      | 0.55%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 87        | 130    | 50.88%  |
| NVMe | 67        | 99     | 39.18%  |
| MMC  | 9         | 11     | 5.26%   |
| SAS  | 8         | 9      | 4.68%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 64        | 87     | 63.37%  |
| 0.51-1.0   | 32        | 44     | 31.68%  |
| 1.01-2.0   | 5         | 6      | 4.95%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 40        | 25.16%  |
| 251-500        | 36        | 22.64%  |
| 501-1000       | 29        | 18.24%  |
| 51-100         | 14        | 8.81%   |
| 1001-2000      | 12        | 7.55%   |
| 1-20           | 11        | 6.92%   |
| 21-50          | 7         | 4.4%    |
| More than 3000 | 4         | 2.52%   |
| Unknown        | 4         | 2.52%   |
| 2001-3000      | 2         | 1.26%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 66        | 40.74%  |
| 21-50          | 28        | 17.28%  |
| 101-250        | 21        | 12.96%  |
| 251-500        | 16        | 9.88%   |
| 51-100         | 16        | 9.88%   |
| 501-1000       | 6         | 3.7%    |
| Unknown        | 4         | 2.47%   |
| 1001-2000      | 3         | 1.85%   |
| More than 3000 | 1         | 0.62%   |
| 2001-3000      | 1         | 0.62%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST2000LM003 HN-M201RAD 2TB | 1         | 1      | 25%     |
| Seagate ST1000LM024 HN-M 1TB       | 1         | 1      | 25%     |
| Hitachi HTS545032B9A300 320GB      | 1         | 1      | 25%     |
| Hitachi HTS541010A9E680 1TB        | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 50%     |
| Hitachi | 2         | 2      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 50%     |
| Hitachi | 2         | 2      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 4      | 100%    |

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
| Detected | 100       | 161    | 62.5%   |
| Works    | 56        | 84     | 35%     |
| Malfunc  | 4         | 4      | 2.5%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 98        | 54.44%  |
| Samsung Electronics          | 19        | 10.56%  |
| SanDisk                      | 14        | 7.78%   |
| AMD                          | 14        | 7.78%   |
| SK hynix                     | 11        | 6.11%   |
| Phison Electronics           | 4         | 2.22%   |
| Toshiba America Info Systems | 3         | 1.67%   |
| Nvidia                       | 3         | 1.67%   |
| KIOXIA                       | 3         | 1.67%   |
| Micron Technology            | 2         | 1.11%   |
| Lenovo                       | 2         | 1.11%   |
| ADATA Technology             | 2         | 1.11%   |
| Union Memory (Shenzhen)      | 1         | 0.56%   |
| Silicon Motion               | 1         | 0.56%   |
| Shenzhen Longsys Electronics | 1         | 0.56%   |
| Seagate Technology           | 1         | 0.56%   |
| Kingston Technology Company  | 1         | 0.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 13        | 6.99%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 13        | 6.99%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 12        | 6.45%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 10        | 5.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 10        | 5.38%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 7         | 3.76%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 3.76%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 6         | 3.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 3.23%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 5         | 2.69%   |
| Intel SSD 660P Series                                                            | 5         | 2.69%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 5         | 2.69%   |
| SK hynix Gold P31 SSD                                                            | 4         | 2.15%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 2.15%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 3         | 1.61%   |
| SK hynix Non-Volatile memory controller                                          | 3         | 1.61%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 3         | 1.61%   |
| Phison E12 NVMe Controller                                                       | 3         | 1.61%   |
| KIOXIA Non-Volatile memory controller                                            | 3         | 1.61%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 1.61%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 1.61%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 1.61%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 3         | 1.61%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 1.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 1.61%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 1.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 1.08%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 1.08%   |
| Samsung Electronics SATA controller                                              | 2         | 1.08%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 2         | 1.08%   |
| Micron Non-Volatile memory controller                                            | 2         | 1.08%   |
| Lenovo Non-Volatile memory controller                                            | 2         | 1.08%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 2         | 1.08%   |
| Intel Non-Volatile memory controller                                             | 2         | 1.08%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.08%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 0.54%   |
| SK hynix BC511                                                                   | 1         | 0.54%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.54%   |
| Shenzhen Longsys SM2263EN/SM2263XT-based OEM SSD                                 | 1         | 0.54%   |
| Seagate FireCuda 520 SSD                                                         | 1         | 0.54%   |
| SanDisk PC SN520 NVMe SSD                                                        | 1         | 0.54%   |
| Phison NVMe Storage Controller                                                   | 1         | 0.54%   |
| Nvidia MCP51 Serial ATA Controller                                               | 1         | 0.54%   |
| Nvidia MCP51 IDE                                                                 | 1         | 0.54%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.54%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 1         | 0.54%   |
| Intel SSD 600P Series                                                            | 1         | 0.54%   |
| Intel Comet Lake PCH-H RAID                                                      | 1         | 0.54%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 1         | 0.54%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 0.54%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 1         | 0.54%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 1         | 0.54%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 0.54%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 1         | 0.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 0.54%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 1         | 0.54%   |
| ADATA Non-Volatile memory controller                                             | 1         | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 92        | 50.83%  |
| NVMe | 68        | 37.57%  |
| RAID | 14        | 7.73%   |
| IDE  | 7         | 3.87%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 124       | 83.22%  |
| AMD    | 25        | 16.78%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 8         | 5.37%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 6         | 4.03%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 6         | 4.03%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 3.36%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 3.36%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 4         | 2.68%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 4         | 2.68%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 2.68%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 2.01%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 2.01%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 2.01%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 2.01%   |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 2         | 1.34%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.34%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.34%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 1.34%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 1.34%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 1.34%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 1.34%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 1.34%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.34%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 2         | 1.34%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 1.34%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 2         | 1.34%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz          | 2         | 1.34%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 1.34%   |
| Intel Atom x5-Z8500 CPU @ 1.44GHz             | 2         | 1.34%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.34%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 1.34%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 1.34%   |
| Intel Xeon W-11955M CPU @ 2.60GHz             | 1         | 0.67%   |
| Intel Processor 5Y70 CPU @ 1.10GHz            | 1         | 0.67%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 0.67%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.67%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz        | 1         | 0.67%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz              | 1         | 0.67%   |
| Intel Core i9-9880H CPU @ 2.30GHz             | 1         | 0.67%   |
| Intel Core i9-10885H CPU @ 2.40GHz            | 1         | 0.67%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 0.67%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz            | 1         | 0.67%   |
| Intel Core i7-4770HQ CPU @ 2.20GHz            | 1         | 0.67%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 0.67%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 0.67%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 0.67%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 0.67%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 0.67%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 0.67%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 1         | 0.67%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 0.67%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 1         | 0.67%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 1         | 0.67%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 1         | 0.67%   |
| Intel Core i5-4310U CPU @ 2.00GHz             | 1         | 0.67%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 1         | 0.67%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 0.67%   |
| Intel Core i5-2435M CPU @ 2.40GHz             | 1         | 0.67%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 0.67%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 1         | 0.67%   |
| Intel Core i5 CPU M 450 @ 2.40GHz             | 1         | 0.67%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 1         | 0.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 53        | 35.57%  |
| Intel Core i5           | 32        | 21.48%  |
| AMD Ryzen 7             | 9         | 6.04%   |
| Intel Core 2 Duo        | 8         | 5.37%   |
| Other                   | 7         | 4.7%    |
| AMD Ryzen 5             | 7         | 4.7%    |
| Intel Celeron           | 6         | 4.03%   |
| Intel Core i3           | 4         | 2.68%   |
| Intel Atom              | 4         | 2.68%   |
| Intel Xeon              | 3         | 2.01%   |
| Intel Pentium Silver    | 2         | 1.34%   |
| Intel Core i9           | 2         | 1.34%   |
| AMD Ryzen 7 PRO         | 2         | 1.34%   |
| Intel Pentium Dual      | 1         | 0.67%   |
| Intel Core m3           | 1         | 0.67%   |
| Intel Core 2            | 1         | 0.67%   |
| AMD Turion 64 X2 Mobile | 1         | 0.67%   |
| AMD Ryzen 9             | 1         | 0.67%   |
| AMD Ryzen 5 PRO         | 1         | 0.67%   |
| AMD Ryzen 3             | 1         | 0.67%   |
| AMD PRO A10             | 1         | 0.67%   |
| AMD E                   | 1         | 0.67%   |
| AMD A6                  | 1         | 0.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 60        | 40.27%  |
| 2      | 57        | 38.26%  |
| 8      | 17        | 11.41%  |
| 6      | 13        | 8.72%   |
| 1      | 2         | 1.34%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 149       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 124       | 82.12%  |
| 1      | 27        | 17.88%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 146       | 97.99%  |
| 32-bit         | 2         | 1.34%   |
| Unknown        | 1         | 0.67%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 26        | 16.88%  |
| 0x806ea    | 11        | 7.14%   |
| 0x906ea    | 10        | 6.49%   |
| 0x806ec    | 10        | 6.49%   |
| 0x206a7    | 9         | 5.84%   |
| 0x306a9    | 7         | 4.55%   |
| 0x40651    | 6         | 3.9%    |
| 0x0a50000c | 6         | 3.9%    |
| 0x806eb    | 5         | 3.25%   |
| 0x306d4    | 5         | 3.25%   |
| 0x1067a    | 4         | 2.6%    |
| 0x08108109 | 4         | 2.6%    |
| 0xa0652    | 3         | 1.95%   |
| 0x806e9    | 3         | 1.95%   |
| 0x6fd      | 3         | 1.95%   |
| 0x506e3    | 3         | 1.95%   |
| 0x406e3    | 3         | 1.95%   |
| 0x306c3    | 3         | 1.95%   |
| 0x20655    | 3         | 1.95%   |
| 0x906e9    | 2         | 1.3%    |
| 0x806d1    | 2         | 1.3%    |
| 0x806c2    | 2         | 1.3%    |
| 0x706a1    | 2         | 1.3%    |
| 0x406c3    | 2         | 1.3%    |
| 0x40661    | 2         | 1.3%    |
| 0x30678    | 2         | 1.3%    |
| 0x106c2    | 2         | 1.3%    |
| 0x08600106 | 2         | 1.3%    |
| 0x08600103 | 2         | 1.3%    |
| 0x906ed    | 1         | 0.65%   |
| 0x906c0    | 1         | 0.65%   |
| 0x706e5    | 1         | 0.65%   |
| 0x706a8    | 1         | 0.65%   |
| 0x6f6      | 1         | 0.65%   |
| 0x10676    | 1         | 0.65%   |
| 0x08608103 | 1         | 0.65%   |
| 0x08108102 | 1         | 0.65%   |
| 0x06006705 | 1         | 0.65%   |
| 0x0600611a | 1         | 0.65%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 46        | 30.87%  |
| SandyBridge   | 11        | 7.38%   |
| Haswell       | 11        | 7.38%   |
| Zen 3         | 8         | 5.37%   |
| Zen+          | 7         | 4.7%    |
| Skylake       | 7         | 4.7%    |
| IvyBridge     | 7         | 4.7%    |
| Penryn        | 6         | 4.03%   |
| Zen 2         | 5         | 3.36%   |
| TigerLake     | 5         | 3.36%   |
| Silvermont    | 5         | 3.36%   |
| Broadwell     | 5         | 3.36%   |
| IceLake       | 4         | 2.68%   |
| Core          | 4         | 2.68%   |
| CometLake     | 4         | 2.68%   |
| Westmere      | 3         | 2.01%   |
| Goldmont plus | 3         | 2.01%   |
| Excavator     | 2         | 1.34%   |
| Bonnell       | 2         | 1.34%   |
| Tremont       | 1         | 0.67%   |
| K8 Hammer     | 1         | 0.67%   |
| Bobcat        | 1         | 0.67%   |
| Unknown       | 1         | 0.67%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 114       | 56.44%  |
| Nvidia | 60        | 29.7%   |
| AMD    | 28        | 13.86%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 13        | 6.22%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 4.78%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 4.31%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 9         | 4.31%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 7         | 3.35%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 3.35%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 3.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 2.87%   |
| AMD Renoir                                                                               | 5         | 2.39%   |
| AMD Cezanne                                                                              | 5         | 2.39%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 1.91%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 1.91%   |
| Intel HD Graphics 620                                                                    | 4         | 1.91%   |
| Intel HD Graphics 5500                                                                   | 4         | 1.91%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.91%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.44%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 3         | 1.44%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 1.44%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 1.44%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 3         | 1.44%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 1.44%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 1.44%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.44%   |
| Intel HD Graphics 530                                                                    | 3         | 1.44%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 1.44%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.44%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.96%   |
| Nvidia TU104M [GeForce RTX 2080 Mobile]                                                  | 2         | 0.96%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 0.96%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 0.96%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.96%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 0.96%   |
| Nvidia GM108M [GeForce 940M]                                                             | 2         | 0.96%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 0.96%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.96%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.96%   |
| Intel HD Graphics 630                                                                    | 2         | 0.96%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.96%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 2         | 0.96%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.48%   |
| Nvidia TU117M                                                                            | 1         | 0.48%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.48%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.48%   |
| Nvidia TU104M [GeForce RTX 2070 SUPER Mobile / Max-Q]                                    | 1         | 0.48%   |
| Nvidia TU104GLM [Quadro RTX 5000 Mobile / Max-Q]                                         | 1         | 0.48%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.48%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.48%   |
| Nvidia GP108GLM [Quadro P520]                                                            | 1         | 0.48%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 0.48%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 1         | 0.48%   |
| Nvidia GM206M [GeForce GTX 965M]                                                         | 1         | 0.48%   |
| Nvidia GM204M [GeForce GTX 980M]                                                         | 1         | 0.48%   |
| Nvidia GM204M [GeForce GTX 970M]                                                         | 1         | 0.48%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.48%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.48%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.48%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 0.48%   |
| Nvidia GF119M [GeForce GT 520M]                                                          | 1         | 0.48%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 0.48%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 65        | 43.33%  |
| Intel + Nvidia | 43        | 28.67%  |
| 1 x AMD        | 16        | 10.67%  |
| 1 x Nvidia     | 14        | 9.33%   |
| Intel + AMD    | 6         | 4%      |
| AMD + Nvidia   | 4         | 2.67%   |
| 2 x AMD        | 2         | 1.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 120       | 77.92%  |
| Proprietary | 31        | 20.13%  |
| Unknown     | 3         | 1.95%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 98        | 62.03%  |
| 1.01-2.0   | 25        | 15.82%  |
| 3.01-4.0   | 13        | 8.23%   |
| 0.01-0.5   | 13        | 8.23%   |
| 7.01-8.0   | 3         | 1.9%    |
| 5.01-6.0   | 3         | 1.9%    |
| 0.51-1.0   | 2         | 1.27%   |
| 8.01-16.0  | 1         | 0.63%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 45        | 26.01%  |
| LG Display              | 22        | 12.72%  |
| BOE                     | 20        | 11.56%  |
| Samsung Electronics     | 19        | 10.98%  |
| Chimei Innolux          | 15        | 8.67%   |
| Dell                    | 12        | 6.94%   |
| Sharp                   | 6         | 3.47%   |
| Apple                   | 6         | 3.47%   |
| Philips                 | 4         | 2.31%   |
| Acer                    | 4         | 2.31%   |
| InfoVision              | 3         | 1.73%   |
| Goldstar                | 3         | 1.73%   |
| CSO                     | 3         | 1.73%   |
| LG Philips              | 2         | 1.16%   |
| Toshiba                 | 1         | 0.58%   |
| PANDA                   | 1         | 0.58%   |
| Mi                      | 1         | 0.58%   |
| Lenovo                  | 1         | 0.58%   |
| Hewlett-Packard         | 1         | 0.58%   |
| EXP                     | 1         | 0.58%   |
| CPT                     | 1         | 0.58%   |
| Chi Mei Optoelectronics | 1         | 0.58%   |
| ASUSTek Computer        | 1         | 0.58%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 3         | 1.73%   |
| Dell P2421D DELD0FF 2560x1440 527x296mm 23.8-inch                     | 3         | 1.73%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2         | 1.16%   |
| LG Philips LCD Monitor LPL8D00 1280x800 304x190mm 14.1-inch           | 2         | 1.16%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch          | 2         | 1.16%   |
| Goldstar ULTRAGEAR GSM5B7F 2560x1440 597x336mm 27.0-inch              | 2         | 1.16%   |
| Chimei Innolux LCD Monitor CMN1354 1920x1080 293x165mm 13.2-inch      | 2         | 1.16%   |
| BOE LCD Monitor BOE06A7 1920x1080 294x165mm 13.3-inch                 | 2         | 1.16%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 2         | 1.16%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 2         | 1.16%   |
| AU Optronics LCD Monitor AUO31EB 3840x2160 344x193mm 15.5-inch        | 2         | 1.16%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch        | 2         | 1.16%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch         | 2         | 1.16%   |
| AU Optronics LCD Monitor AUO205C 1366x768 256x144mm 11.6-inch         | 2         | 1.16%   |
| Toshiba LCD TV LCD0030 1920x1080 708x398mm 32.0-inch                  | 1         | 0.58%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch               | 1         | 0.58%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 1         | 0.58%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.58%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch               | 1         | 0.58%   |
| Sharp LCD Monitor SHP1485 1920x1080 294x165mm 13.3-inch               | 1         | 0.58%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.58%   |
| Samsung Electronics U32R59x SAM0F94 3840x2160 697x392mm 31.5-inch     | 1         | 0.58%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch     | 1         | 0.58%   |
| Samsung Electronics S24R35xFZ SAM71A8 1920x1080 527x296mm 23.8-inch   | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC554E 1024x600 223x125mm 10.1-inch  | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch  | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 223x125mm 10.1-inch  | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch  | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch  | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 293x165mm 13.2-inch | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch  | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SDC3652 1366x768 344x194mm 15.5-inch  | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SAM03D4 1360x768                      | 1         | 0.58%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch   | 1         | 0.58%   |
| Samsung Electronics C27F591 SAM0D36 1920x1080 600x340mm 27.2-inch     | 1         | 0.58%   |
| Philips PHL 272P7VU PHL093A 3840x2160 597x336mm 27.0-inch             | 1         | 0.58%   |
| Philips PHL 223V7 PHLC154 1920x1080 476x268mm 21.5-inch               | 1         | 0.58%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 1         | 0.58%   |
| Philips 32PFL1335/98 PFL1335 1360x768 708x398mm 32.0-inch             | 1         | 0.58%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 1         | 0.58%   |
| Mi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                      | 1         | 0.58%   |
| LG Display LCD Monitor LGDD302 1366x768 277x156mm 12.5-inch           | 1         | 0.58%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch          | 1         | 0.58%   |
| LG Display LCD Monitor LGD0657 1920x1080 344x194mm 15.5-inch          | 1         | 0.58%   |
| LG Display LCD Monitor LGD061A 1920x1080 344x194mm 15.5-inch          | 1         | 0.58%   |
| LG Display LCD Monitor LGD060A 1920x1080 294x165mm 13.3-inch          | 1         | 0.58%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch          | 1         | 0.58%   |
| LG Display LCD Monitor LGD05E9 1920x1080 294x165mm 13.3-inch          | 1         | 0.58%   |
| LG Display LCD Monitor LGD05C4 1920x1080 344x194mm 15.5-inch          | 1         | 0.58%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch          | 1         | 0.58%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 1         | 0.58%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch          | 1         | 0.58%   |
| LG Display LCD Monitor LGD04F9 1920x1080 309x174mm 14.0-inch          | 1         | 0.58%   |
| LG Display LCD Monitor LGD0419 2560x1440 310x174mm 14.0-inch          | 1         | 0.58%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch           | 1         | 0.58%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch           | 1         | 0.58%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 1         | 0.58%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 84        | 52.5%   |
| 1366x768 (WXGA)   | 29        | 18.13%  |
| 3840x2160 (4K)    | 9         | 5.63%   |
| 1280x800 (WXGA)   | 8         | 5%      |
| 2560x1440 (QHD)   | 7         | 4.38%   |
| 1920x1200 (WUXGA) | 4         | 2.5%    |
| 3440x1440         | 3         | 1.88%   |
| 2560x1600         | 3         | 1.88%   |
| 2880x1800         | 2         | 1.25%   |
| 2240x1400         | 2         | 1.25%   |
| 1360x768          | 2         | 1.25%   |
| 3840x2400         | 1         | 0.63%   |
| 3200x1800 (QHD+)  | 1         | 0.63%   |
| 1600x900 (HD+)    | 1         | 0.63%   |
| 1440x900 (WXGA+)  | 1         | 0.63%   |
| 1280x720 (HD)     | 1         | 0.63%   |
| 1280x1024 (SXGA)  | 1         | 0.63%   |
| 1024x600          | 1         | 0.63%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 48        | 27.91%  |
| 13      | 38        | 22.09%  |
| 14      | 31        | 18.02%  |
| 27      | 8         | 4.65%   |
| 23      | 8         | 4.65%   |
| 12      | 8         | 4.65%   |
| 11      | 6         | 3.49%   |
| 24      | 4         | 2.33%   |
| 21      | 3         | 1.74%   |
| 16      | 3         | 1.74%   |
| 34      | 2         | 1.16%   |
| 32      | 2         | 1.16%   |
| 19      | 2         | 1.16%   |
| 18      | 2         | 1.16%   |
| 52      | 1         | 0.58%   |
| 40      | 1         | 0.58%   |
| 35      | 1         | 0.58%   |
| 31      | 1         | 0.58%   |
| 17      | 1         | 0.58%   |
| 10      | 1         | 0.58%   |
| Unknown | 1         | 0.58%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 96        | 55.81%  |
| 201-300     | 36        | 20.93%  |
| 501-600     | 20        | 11.63%  |
| 401-500     | 6         | 3.49%   |
| 351-400     | 5         | 2.91%   |
| 701-800     | 4         | 2.33%   |
| 801-900     | 2         | 1.16%   |
| 601-700     | 1         | 0.58%   |
| 1001-1500   | 1         | 0.58%   |
| Unknown     | 1         | 0.58%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 123       | 83.11%  |
| 16/10 | 20        | 13.51%  |
| 21/9  | 3         | 2.03%   |
| 5/4   | 1         | 0.68%   |
| 3/2   | 1         | 0.68%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 51        | 29.65%  |
| 101-110        | 48        | 27.91%  |
| 71-80          | 18        | 10.47%  |
| 201-250        | 14        | 8.14%   |
| 61-70          | 8         | 4.65%   |
| 301-350        | 8         | 4.65%   |
| 51-60          | 6         | 3.49%   |
| 351-500        | 6         | 3.49%   |
| 151-200        | 3         | 1.74%   |
| 111-120        | 3         | 1.74%   |
| 141-150        | 2         | 1.16%   |
| More than 1000 | 1         | 0.58%   |
| 41-50          | 1         | 0.58%   |
| 121-130        | 1         | 0.58%   |
| 501-1000       | 1         | 0.58%   |
| Unknown        | 1         | 0.58%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 78        | 46.99%  |
| 101-120       | 30        | 18.07%  |
| 161-240       | 26        | 15.66%  |
| 51-100        | 21        | 12.65%  |
| More than 240 | 8         | 4.82%   |
| 1-50          | 2         | 1.2%    |
| Unknown       | 1         | 0.6%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 120       | 76.92%  |
| 2     | 30        | 19.23%  |
| 0     | 5         | 3.21%   |
| 3     | 1         | 0.64%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 89        | 41.59%  |
| Realtek Semiconductor    | 57        | 26.64%  |
| Qualcomm Atheros         | 32        | 14.95%  |
| Broadcom                 | 12        | 5.61%   |
| MediaTek                 | 4         | 1.87%   |
| ASIX Electronics         | 4         | 1.87%   |
| Broadcom Limited         | 3         | 1.4%    |
| Marvell Technology Group | 2         | 0.93%   |
| Sierra Wireless          | 1         | 0.47%   |
| Samsung Electronics      | 1         | 0.47%   |
| Ralink Technology        | 1         | 0.47%   |
| Ralink                   | 1         | 0.47%   |
| Qualcomm                 | 1         | 0.47%   |
| Nvidia                   | 1         | 0.47%   |
| MosChip Semiconductor    | 1         | 0.47%   |
| Lenovo                   | 1         | 0.47%   |
| Google                   | 1         | 0.47%   |
| D-Link                   | 1         | 0.47%   |
| Apple                    | 1         | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 32        | 12.65%  |
| Intel Wireless 7265                                                     | 12        | 4.74%   |
| Intel Wi-Fi 6 AX200                                                     | 11        | 4.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 10        | 3.95%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 8         | 3.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 2.77%   |
| Intel Wireless 8265 / 8275                                              | 7         | 2.77%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 2.77%   |
| Intel Wireless 7260                                                     | 6         | 2.37%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 2.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 6         | 2.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 1.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 4         | 1.58%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 1.58%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 1.58%   |
| ASIX AX88179 Gigabit Ethernet                                           | 4         | 1.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.19%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 1.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 1.19%   |
| Intel Wireless 3165                                                     | 3         | 1.19%   |
| Intel Ethernet Connection I218-LM                                       | 3         | 1.19%   |
| Intel Ethernet Connection (4) I219-LM                                   | 3         | 1.19%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.19%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 0.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.79%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 0.79%   |
| Realtek Killer E3000 2.5GbE Controller                                  | 2         | 0.79%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 2         | 0.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 0.79%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.79%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.79%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 0.79%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 0.79%   |
| Intel Ethernet Connection (4) I219-V                                    | 2         | 0.79%   |
| Intel Ethernet Connection (3) I218-LM                                   | 2         | 0.79%   |
| Intel Ethernet Connection (10) I219-V                                   | 2         | 0.79%   |
| Intel 82579V Gigabit Network Connection                                 | 2         | 0.79%   |
| Intel 82567LM Gigabit Network Connection                                | 2         | 0.79%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 2         | 0.79%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 2         | 0.79%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 2         | 0.79%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 0.79%   |
| Broadcom BCM4311 802.11a/b/g                                            | 2         | 0.79%   |
| Sierra Wireless EM7455                                                  | 1         | 0.4%    |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 0.4%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.4%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.4%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.4%    |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 1         | 0.4%    |
| Realtek Realtek Ethernet controller                                     | 1         | 0.4%    |
| Realtek 802.11ax WLAN Adapter                                           | 1         | 0.4%    |
| Realtek 802.11ac NIC                                                    | 1         | 0.4%    |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.4%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.4%    |
| Qualcomm QCA6390 Wireless Network Adapter                               | 1         | 0.4%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 1         | 0.4%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 1         | 0.4%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1         | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 87        | 58.39%  |
| Qualcomm Atheros      | 28        | 18.79%  |
| Realtek Semiconductor | 13        | 8.72%   |
| Broadcom              | 10        | 6.71%   |
| MediaTek              | 4         | 2.68%   |
| Broadcom Limited      | 2         | 1.34%   |
| Sierra Wireless       | 1         | 0.67%   |
| Ralink Technology     | 1         | 0.67%   |
| Ralink                | 1         | 0.67%   |
| Qualcomm              | 1         | 0.67%   |
| D-Link                | 1         | 0.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                     | 12        | 8%      |
| Intel Wi-Fi 6 AX200                                                     | 11        | 7.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 10        | 6.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 4.67%   |
| Intel Wireless 8265 / 8275                                              | 7         | 4.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 4.67%   |
| Intel Wireless 7260                                                     | 6         | 4%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 4%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 3.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 3.33%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 2.67%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 2.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 2%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 2%      |
| Intel Wireless 3165                                                     | 3         | 2%      |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 2%      |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 1.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.33%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 1.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 1.33%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.33%   |
| Intel Wireless-AC 9260                                                  | 2         | 1.33%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 1.33%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 1.33%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 2         | 1.33%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 2         | 1.33%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 1.33%   |
| Broadcom BCM4311 802.11a/b/g                                            | 2         | 1.33%   |
| Sierra Wireless EM7455                                                  | 1         | 0.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.67%   |
| Realtek 802.11ax WLAN Adapter                                           | 1         | 0.67%   |
| Realtek 802.11ac NIC                                                    | 1         | 0.67%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.67%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.67%   |
| Qualcomm QCA6390 Wireless Network Adapter                               | 1         | 0.67%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.67%   |
| Intel Wireless 8260                                                     | 1         | 0.67%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 0.67%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 0.67%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 0.67%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 0.67%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.67%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 0.67%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 0.67%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 0.67%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 0.67%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                           | 1         | 0.67%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 0.67%   |
| D-Link DWA-182 Wireless AC Dualband Adapter(rev.C) [Realtek RTL8812AU]  | 1         | 0.67%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 1         | 0.67%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 0.67%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 0.67%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 1         | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 48        | 46.6%   |
| Intel                    | 29        | 28.16%  |
| Qualcomm Atheros         | 8         | 7.77%   |
| Broadcom                 | 5         | 4.85%   |
| ASIX Electronics         | 4         | 3.88%   |
| Marvell Technology Group | 2         | 1.94%   |
| Samsung Electronics      | 1         | 0.97%   |
| Nvidia                   | 1         | 0.97%   |
| MosChip Semiconductor    | 1         | 0.97%   |
| Lenovo                   | 1         | 0.97%   |
| Google                   | 1         | 0.97%   |
| Broadcom Limited         | 1         | 0.97%   |
| Apple                    | 1         | 0.97%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 32        | 31.07%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 8         | 7.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 6         | 5.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 3.88%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 4         | 3.88%   |
| Intel Ethernet Connection I218-LM                                              | 3         | 2.91%   |
| Intel Ethernet Connection (4) I219-LM                                          | 3         | 2.91%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 2         | 1.94%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 1.94%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 1.94%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 1.94%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 1.94%   |
| Intel 82579V Gigabit Network Connection                                        | 2         | 1.94%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 1.94%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 1.94%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.97%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.97%   |
| Realtek Realtek Ethernet controller                                            | 1         | 0.97%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.97%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.97%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.97%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.97%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.97%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.97%   |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 0.97%   |
| MosChip MCS7830 10/100 Mbps Ethernet adapter                                   | 1         | 0.97%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.97%   |
| Marvell Group 88E8038 PCI-E Fast Ethernet Controller                           | 1         | 0.97%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.97%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 0.97%   |
| Intel Ethernet Connection (7) I219-V                                           | 1         | 0.97%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.97%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.97%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 0.97%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 0.97%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.97%   |
| Google Nexus/Pixel Device (tether)                                             | 1         | 0.97%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 1         | 0.97%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                               | 1         | 0.97%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 1         | 0.97%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 1         | 0.97%   |
| Apple iPad 4/Mini1                                                             | 1         | 0.97%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 145       | 59.92%  |
| Ethernet | 97        | 40.08%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 131       | 80.86%  |
| Ethernet | 31        | 19.14%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 84        | 56%     |
| 1     | 64        | 42.67%  |
| 3     | 1         | 0.67%   |
| 0     | 1         | 0.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 141       | 94.63%  |
| Yes  | 8         | 5.37%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 70        | 56%     |
| Qualcomm Atheros Communications | 11        | 8.8%    |
| IMC Networks                    | 11        | 8.8%    |
| Foxconn / Hon Hai               | 8         | 6.4%    |
| Broadcom                        | 7         | 5.6%    |
| Apple                           | 5         | 4%      |
| Lite-On Technology              | 4         | 3.2%    |
| Realtek Semiconductor           | 3         | 2.4%    |
| Toshiba                         | 1         | 0.8%    |
| Ralink Technology               | 1         | 0.8%    |
| Foxconn International           | 1         | 0.8%    |
| Chicony Electronics             | 1         | 0.8%    |
| Cambridge Silicon Radio         | 1         | 0.8%    |
| Alps Electric                   | 1         | 0.8%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 27        | 21.6%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 16        | 12.8%   |
| Intel Bluetooth Device                              | 14        | 11.2%   |
| Intel AX200 Bluetooth                               | 10        | 8%      |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 5         | 4%      |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 3.2%    |
| IMC Networks Bluetooth Radio                        | 4         | 3.2%    |
| IMC Networks Bluetooth Device                       | 4         | 3.2%    |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 2.4%    |
| Foxconn / Hon Hai BCM20702A0                        | 3         | 2.4%    |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 2.4%    |
| Apple Bluetooth Host Controller                     | 3         | 2.4%    |
| Realtek Bluetooth Radio                             | 2         | 1.6%    |
| Lite-On Bluetooth Device                            | 2         | 1.6%    |
| IMC Networks Wireless_Device                        | 2         | 1.6%    |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 1.6%    |
| Broadcom BCM2045 Bluetooth                          | 2         | 1.6%    |
| Apple Bluetooth USB Host Controller                 | 2         | 1.6%    |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.8%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.8%    |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.8%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.8%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.8%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.8%    |
| Lite-On Bluetooth Radio                             | 1         | 0.8%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.8%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.8%    |
| Intel AX210 Bluetooth                               | 1         | 0.8%    |
| IMC Networks Bluetooth module                       | 1         | 0.8%    |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.8%    |
| Chicony Bluetooth (RTL8723BE)                       | 1         | 0.8%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 0.8%    |
| Broadcom Bluetooth                                  | 1         | 0.8%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 0.8%    |
| Alps Electric Bluetooth Adapter                     | 1         | 0.8%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 119       | 66.85%  |
| Nvidia              | 25        | 14.04%  |
| AMD                 | 25        | 14.04%  |
| Apple               | 2         | 1.12%   |
| Razer USA           | 1         | 0.56%   |
| Plantronics         | 1         | 0.56%   |
| Lenovo              | 1         | 0.56%   |
| Kingston Technology | 1         | 0.56%   |
| JBL                 | 1         | 0.56%   |
| Cooler Master       | 1         | 0.56%   |
| ASUSTek Computer    | 1         | 0.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 21        | 9.81%   |
| Intel Sunrise Point-LP HD Audio                                            | 20        | 9.35%   |
| Intel Cannon Lake PCH cAVS                                                 | 11        | 5.14%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10        | 4.67%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 10        | 4.67%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 8         | 3.74%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 3.74%   |
| Intel Comet Lake PCH-LP cAVS                                               | 7         | 3.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7         | 3.27%   |
| Intel Haswell-ULT HD Audio Controller                                      | 6         | 2.8%    |
| Intel 8 Series HD Audio Controller                                         | 6         | 2.8%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 2.34%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 2.34%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 2.34%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 2.34%   |
| Nvidia TU104 HD Audio Controller                                           | 4         | 1.87%   |
| Nvidia GA104 High Definition Audio Controller                              | 4         | 1.87%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 1.87%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 1.87%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 1.87%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 1.4%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.4%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 1.4%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 1.4%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 1.4%    |
| Nvidia MCP89 High Definition Audio                                         | 2         | 0.93%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.93%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 0.93%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 0.93%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 0.93%   |
| Intel CM238 HD Audio Controller                                            | 2         | 0.93%   |
| Apple USB-C to 3.5mm Headphone Jack Adapter                                | 2         | 0.93%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 0.93%   |
| Razer USA Electra V2 USB                                                   | 1         | 0.47%   |
| Plantronics Blackwire 3225 Series                                          | 1         | 0.47%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.47%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.47%   |
| Nvidia MCP51 High Definition Audio                                         | 1         | 0.47%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.47%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.47%   |
| Nvidia GM206 High Definition Audio Controller                              | 1         | 0.47%   |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 0.47%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.47%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.47%   |
| Nvidia Audio device                                                        | 1         | 0.47%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                  | 1         | 0.47%   |
| Kingston Technology HyperX 7.1 Audio                                       | 1         | 0.47%   |
| JBL Quantum 600                                                            | 1         | 0.47%   |
| Intel USB PnP Sound Device                                                 | 1         | 0.47%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 1         | 0.47%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 0.47%   |
| Intel Crystal Well HD Audio Controller                                     | 1         | 0.47%   |
| Cooler Master MH752                                                        | 1         | 0.47%   |
| ASUSTek Computer Xonar U5 sound card                                       | 1         | 0.47%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 0.47%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 0.47%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 0.47%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 0.47%   |
| AMD High Definition Audio Controller                                       | 1         | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 33        | 33.67%  |
| Samsung Electronics | 21        | 21.43%  |
| Micron Technology   | 17        | 17.35%  |
| Kingston            | 7         | 7.14%   |
| Crucial             | 5         | 5.1%    |
| Unknown             | 4         | 4.08%   |
| Ramaxel Technology  | 3         | 3.06%   |
| Transcend           | 2         | 2.04%   |
| A-DATA Technology   | 2         | 2.04%   |
| Unknown (ABCD)      | 1         | 1.02%   |
| Lexar               | 1         | 1.02%   |
| Elpida              | 1         | 1.02%   |
| Corsair             | 1         | 1.02%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 3         | 2.97%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s    | 3         | 2.97%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 3         | 2.97%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                     | 2         | 1.98%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 1.98%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 1.98%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 2         | 1.98%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 1.98%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 2         | 1.98%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s            | 2         | 1.98%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s                | 2         | 1.98%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 2         | 1.98%   |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s                    | 1         | 0.99%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                         | 1         | 0.99%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                      | 1         | 0.99%   |
| Unknown RAM Module 1GB SODIMM DDR3 1600MT/s                         | 1         | 0.99%   |
| Unknown RAM Module 16GB Row Of Chips LPDDR4 4267MT/s                | 1         | 0.99%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 0.99%   |
| Transcend RAM TS1GSK64V3H 8192MB SODIMM DDR3 1333MT/s               | 1         | 0.99%   |
| Transcend RAM JM3200HSB-16G 16GB SODIMM DDR4 3200MT/s               | 1         | 0.99%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                     | 1         | 0.99%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.99%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s           | 1         | 0.99%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.99%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.99%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.99%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 0.99%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB Row Of Chips DDR4 3200MT/s       | 1         | 0.99%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 0.99%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 1         | 0.99%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s           | 1         | 0.99%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 1         | 0.99%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s             | 1         | 0.99%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.99%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 1         | 0.99%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s      | 1         | 0.99%   |
| SK hynix RAM H9HCNNNCPMALHR-NEE 8GB Row Of Chips LPDDR4 4800MT/s    | 1         | 0.99%   |
| Samsung RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s              | 1         | 0.99%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                         | 1         | 0.99%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                     | 1         | 0.99%   |
| Samsung RAM M474A2K43BB1-CTD 16GB SODIMM DDR4 2667MT/s              | 1         | 0.99%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 4199MT/s               | 1         | 0.99%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.99%   |
| Samsung RAM M471B2874EH1-CF8 1024MB SODIMM 1067MT/s                 | 1         | 0.99%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 0.99%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 0.99%   |
| Samsung RAM M471A5244BB0-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 0.99%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 1         | 0.99%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s              | 1         | 0.99%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 1         | 0.99%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s              | 1         | 0.99%   |
| Samsung RAM M471A2G44AM0-CWE 16384MB SODIMM DDR4 3200MT/s           | 1         | 0.99%   |
| Samsung RAM M471A1K44BM0-CRC 8192MB SODIMM DDR4 2400MT/s            | 1         | 0.99%   |
| Ramaxel RAM RMSA3320MJ78HAF-3200 8GB SODIMM DDR4 3200MT/s           | 1         | 0.99%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s           | 1         | 0.99%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s           | 1         | 0.99%   |
| Micron RAM MTAF5121G64HZ-2G6E1 4GB SODIMM DDR4 1200MT/s             | 1         | 0.99%   |
| Micron RAM MT52L512M32D2PF-10 4096MB Row Of Chips LPDDR3 1867MT/s   | 1         | 0.99%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s       | 1         | 0.99%   |
| Micron RAM MT40A1G16RC-062E:B 8GB Row Of Chips DDR4 3200MT/s        | 1         | 0.99%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 46        | 58.23%  |
| DDR3   | 21        | 26.58%  |
| LPDDR3 | 7         | 8.86%   |
| LPDDR4 | 4         | 5.06%   |
| SDRAM  | 1         | 1.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 64        | 82.05%  |
| Row Of Chips | 13        | 16.67%  |
| Chip         | 1         | 1.28%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 40        | 43.48%  |
| 4096  | 26        | 28.26%  |
| 16384 | 18        | 19.57%  |
| 32768 | 4         | 4.35%   |
| 2048  | 2         | 2.17%   |
| 1024  | 2         | 2.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 21        | 23.86%  |
| 3200  | 19        | 21.59%  |
| 1600  | 19        | 21.59%  |
| 2400  | 9         | 10.23%  |
| 2133  | 6         | 6.82%   |
| 1334  | 3         | 3.41%   |
| 4267  | 2         | 2.27%   |
| 3266  | 2         | 2.27%   |
| 1333  | 2         | 2.27%   |
| 4800  | 1         | 1.14%   |
| 4199  | 1         | 1.14%   |
| 1867  | 1         | 1.14%   |
| 1200  | 1         | 1.14%   |
| 1067  | 1         | 1.14%   |

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
| Chicony Electronics                    | 34        | 25.95%  |
| IMC Networks                           | 22        | 16.79%  |
| Microdia                               | 15        | 11.45%  |
| Realtek Semiconductor                  | 14        | 10.69%  |
| Sunplus Innovation Technology          | 9         | 6.87%   |
| Acer                                   | 6         | 4.58%   |
| Suyin                                  | 5         | 3.82%   |
| Syntek                                 | 4         | 3.05%   |
| Samsung Electronics                    | 4         | 3.05%   |
| Apple                                  | 3         | 2.29%   |
| Silicon Motion                         | 2         | 1.53%   |
| Ricoh                                  | 2         | 1.53%   |
| Logitech                               | 2         | 1.53%   |
| Lite-On Technology                     | 2         | 1.53%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.76%   |
| Quanta                                 | 1         | 0.76%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.76%   |
| Magic Control Technology               | 1         | 0.76%   |
| Luxvisions Innotech Limited            | 1         | 0.76%   |
| Lenovo                                 | 1         | 0.76%   |
| Intel                                  | 1         | 0.76%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                              | 9         | 6.87%   |
| Chicony HD WebCam                                          | 8         | 6.11%   |
| Chicony Integrated Camera                                  | 7         | 5.34%   |
| Realtek Integrated_Webcam_HD                               | 6         | 4.58%   |
| IMC Networks Integrated Camera                             | 6         | 4.58%   |
| Sunplus Integrated_Webcam_HD                               | 5         | 3.82%   |
| IMC Networks USB2.0 HD UVC WebCam                          | 5         | 3.82%   |
| Samsung Galaxy series, misc. (MTP mode)                    | 4         | 3.05%   |
| IMC Networks USB2.0 VGA UVC WebCam                         | 4         | 3.05%   |
| IMC Networks USB2.0 HD IR UVC WebCam                       | 4         | 3.05%   |
| Syntek Integrated Camera                                   | 3         | 2.29%   |
| Chicony Lenovo Integrated Camera (0.3MP)                   | 3         | 2.29%   |
| Chicony HP HD Camera                                       | 3         | 2.29%   |
| Realtek Integrated Webcam_HD                               | 2         | 1.53%   |
| Realtek Asus 2.0 USB Webcam                                | 2         | 1.53%   |
| Microdia Sonix USB 2.0 Camera                              | 2         | 1.53%   |
| IMC Networks Lenovo EasyCamera                             | 2         | 1.53%   |
| Chicony USB2.0 HD UVC WebCam                               | 2         | 1.53%   |
| Chicony USB2.0 Camera                                      | 2         | 1.53%   |
| Chicony HP Wide Vision HD Camera                           | 2         | 1.53%   |
| Apple FaceTime HD Camera                                   | 2         | 1.53%   |
| Acer Integrated Camera                                     | 2         | 1.53%   |
| Acer BisonCam, NB Pro                                      | 2         | 1.53%   |
| Syntek Lenovo EasyCamera                                   | 1         | 0.76%   |
| Suyin UVC HD Webcam                                        | 1         | 0.76%   |
| Suyin Laptop_Integrated_Webcam_HD                          | 1         | 0.76%   |
| Suyin Asus Integrated Webcam                               | 1         | 0.76%   |
| Suyin Acer/Lenovo Webcam [CN0316]                          | 1         | 0.76%   |
| Suyin Acer HD Crystal Eye webcam                           | 1         | 0.76%   |
| Sunplus TOSHIBA Web Camera - HD                            | 1         | 0.76%   |
| Sunplus Lenovo EasyCamera                                  | 1         | 0.76%   |
| Sunplus Laptop Integrated Webcam HD                        | 1         | 0.76%   |
| Sunplus HD User Facing                                     | 1         | 0.76%   |
| Sony Ericsson Mobile AB XQ-BQ72                            | 1         | 0.76%   |
| Silicon Motion WebCam SCB-1100N                            | 1         | 0.76%   |
| Silicon Motion WebCam SCB-0370N                            | 1         | 0.76%   |
| Ricoh Visual Communication Camera VGP-VCC6 [R5U870]        | 1         | 0.76%   |
| Ricoh USB2.0 Camera                                        | 1         | 0.76%   |
| Realtek USB Camera                                         | 1         | 0.76%   |
| Realtek USB Boot                                           | 1         | 0.76%   |
| Realtek Integrated Webcam HD                               | 1         | 0.76%   |
| Realtek HD Webcam - Realtek                                | 1         | 0.76%   |
| Quanta HD User Facing                                      | 1         | 0.76%   |
| OnePlus (Shenzhen) A3000 phone (PTP mode, with debug) [3T] | 1         | 0.76%   |
| Microdia USB 2.0 Camera                                    | 1         | 0.76%   |
| Microdia JOYACCESS JA-Webcam                               | 1         | 0.76%   |
| Microdia Integrated Webcam HD                              | 1         | 0.76%   |
| Microdia Integrated Webcam                                 | 1         | 0.76%   |
| Magic Control j5 WebCam JVCU100                            | 1         | 0.76%   |
| Luxvisions Innotech Limited Integrated Camera              | 1         | 0.76%   |
| Logitech Webcam C270                                       | 1         | 0.76%   |
| Logitech HD Webcam C615                                    | 1         | 0.76%   |
| Lite-On Integrated Camera                                  | 1         | 0.76%   |
| Lite-On HP HD Camera                                       | 1         | 0.76%   |
| Lenovo Integrated Webcam                                   | 1         | 0.76%   |
| Intel RealSense Camera SR300                               | 1         | 0.76%   |
| IMC Networks SunplusIT Integrated Camera                   | 1         | 0.76%   |
| Chicony USB2.0 VGA UVC WebCam                              | 1         | 0.76%   |
| Chicony Lenovo EasyCamera                                  | 1         | 0.76%   |
| Chicony Integrated Camera [ThinkPad]                       | 1         | 0.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 11        | 25%     |
| Validity Sensors           | 7         | 15.91%  |
| LighTuning Technology      | 6         | 13.64%  |
| AuthenTec                  | 6         | 13.64%  |
| Upek                       | 5         | 11.36%  |
| Shenzhen Goodix Technology | 5         | 11.36%  |
| Elan Microelectronics      | 4         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 7         | 15.91%  |
| LighTuning EgisTec Touch Fingerprint Sensor               | 6         | 13.64%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 5         | 11.36%  |
| Validity Sensors VFS495 Fingerprint Reader                | 2         | 4.55%   |
| Validity Sensors Synaptics WBDI                           | 2         | 4.55%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 2         | 4.55%   |
| Shenzhen Goodix Fingerprint Reader                        | 2         | 4.55%   |
| Shenzhen Goodix FingerPrint                               | 2         | 4.55%   |
| Elan ELAN:Fingerprint                                     | 2         | 4.55%   |
| Elan ELAN:ARM-M4                                          | 2         | 4.55%   |
| AuthenTec AES2810                                         | 2         | 4.55%   |
| AuthenTec AES2501 Fingerprint Sensor                      | 2         | 4.55%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor         | 1         | 2.27%   |
| Validity Sensors VFS101 Fingerprint Reader                | 1         | 2.27%   |
| Validity Sensors VFS 5011 fingerprint sensor              | 1         | 2.27%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 2.27%   |
| Shenzhen Goodix  FingerPrint Device                       | 1         | 2.27%   |
| AuthenTec Fingerprint Sensor                              | 1         | 2.27%   |
| AuthenTec AES1660 Fingerprint Sensor                      | 1         | 2.27%   |
| Unknown                                                   | 1         | 2.27%   |

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
| 0     | 86        | 53.75%  |
| 1     | 56        | 35%     |
| 2     | 16        | 10%     |
| 3     | 2         | 1.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 43        | 47.25%  |
| Graphics card            | 22        | 24.18%  |
| Net/wireless             | 8         | 8.79%   |
| Chipcard                 | 5         | 5.49%   |
| Camera                   | 4         | 4.4%    |
| Multimedia controller    | 3         | 3.3%    |
| Net/ethernet             | 2         | 2.2%    |
| Wireless                 | 1         | 1.1%    |
| Firewire controller      | 1         | 1.1%    |
| Communication controller | 1         | 1.1%    |
| Bluetooth                | 1         | 1.1%    |


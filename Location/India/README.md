Linux in India - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Linux in India.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/India/Desktop/README.md) and [notebooks](/Location/India/Notebook/README.md).

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

Total: 5022

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MICROMAX      | Canvas Lapbook L1161        | Notebook    | [9efe9e89d6](https://linux-hardware.org/?probe=9efe9e89d6) | Oct 01, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [88c05ba074](https://linux-hardware.org/?probe=88c05ba074) | Oct 01, 2022 |
| MSI           | B350M PRO-VDH               | Desktop     | [1a0d8b695d](https://linux-hardware.org/?probe=1a0d8b695d) | Oct 01, 2022 |
| Lenovo        | 3098 NOK                    | Desktop     | [a46521af41](https://linux-hardware.org/?probe=a46521af41) | Oct 01, 2022 |
| ASUSTek       | K53SM                       | Notebook    | [f05f33fa9b](https://linux-hardware.org/?probe=f05f33fa9b) | Oct 01, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [82e89b9263](https://linux-hardware.org/?probe=82e89b9263) | Oct 01, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [e64a9cf0e2](https://linux-hardware.org/?probe=e64a9cf0e2) | Oct 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YES... | Notebook    | [1a210b9eb5](https://linux-hardware.org/?probe=1a210b9eb5) | Oct 01, 2022 |
| Lenovo        | ThinkPad L450 20DSS00M01    | Notebook    | [e52e98a7e7](https://linux-hardware.org/?probe=e52e98a7e7) | Oct 01, 2022 |
| Dell          | G3 3500                     | Notebook    | [245ebaabe5](https://linux-hardware.org/?probe=245ebaabe5) | Oct 01, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [c4688badf5](https://linux-hardware.org/?probe=c4688badf5) | Oct 01, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [ee185c669a](https://linux-hardware.org/?probe=ee185c669a) | Oct 01, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [af9b794734](https://linux-hardware.org/?probe=af9b794734) | Sep 30, 2022 |
| Lenovo        | G460 20041                  | Notebook    | [9018f40ad5](https://linux-hardware.org/?probe=9018f40ad5) | Sep 30, 2022 |
| Acer          | Predator PH315-51           | Notebook    | [68f7384e7a](https://linux-hardware.org/?probe=68f7384e7a) | Sep 30, 2022 |
| Google        | Relm                        | Notebook    | [e440e5c1cc](https://linux-hardware.org/?probe=e440e5c1cc) | Sep 30, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [a686f595ee](https://linux-hardware.org/?probe=a686f595ee) | Sep 29, 2022 |
| Lenovo        | G580 20157                  | Notebook    | [2b34d591ab](https://linux-hardware.org/?probe=2b34d591ab) | Sep 29, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [c23649cdd4](https://linux-hardware.org/?probe=c23649cdd4) | Sep 28, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [46cba6613f](https://linux-hardware.org/?probe=46cba6613f) | Sep 28, 2022 |
| Dell          | Latitude 3410               | Notebook    | [82fe1556b6](https://linux-hardware.org/?probe=82fe1556b6) | Sep 28, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [84187f87ed](https://linux-hardware.org/?probe=84187f87ed) | Sep 28, 2022 |
| MSI           | B450M GAMING PLUS           | Desktop     | [265d059992](https://linux-hardware.org/?probe=265d059992) | Sep 27, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [3aa314d706](https://linux-hardware.org/?probe=3aa314d706) | Sep 27, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [9f37c7c4fa](https://linux-hardware.org/?probe=9f37c7c4fa) | Sep 25, 2022 |
| Acer          | Aspire A515-57G             | Notebook    | [97c49cffe7](https://linux-hardware.org/?probe=97c49cffe7) | Sep 25, 2022 |
| Acer          | Aspire A515-57G             | Notebook    | [10813c8cb5](https://linux-hardware.org/?probe=10813c8cb5) | Sep 25, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [0d790a94fa](https://linux-hardware.org/?probe=0d790a94fa) | Sep 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9c7306d91e](https://linux-hardware.org/?probe=9c7306d91e) | Sep 25, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [0546e47f90](https://linux-hardware.org/?probe=0546e47f90) | Sep 25, 2022 |
| HP            | Pavilion Laptop 15-cs1xx... | Notebook    | [5cd2d8db8c](https://linux-hardware.org/?probe=5cd2d8db8c) | Sep 24, 2022 |
| Lenovo        | ThinkPad E470 20H1004UIG    | Notebook    | [310337a455](https://linux-hardware.org/?probe=310337a455) | Sep 24, 2022 |
| Dell          | Precision 7510              | Notebook    | [11c98b608a](https://linux-hardware.org/?probe=11c98b608a) | Sep 24, 2022 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [b77f4e7973](https://linux-hardware.org/?probe=b77f4e7973) | Sep 24, 2022 |
| Lenovo        | Yoga 7 16IAP7 82QG          | Convertible | [45f42656c3](https://linux-hardware.org/?probe=45f42656c3) | Sep 24, 2022 |
| Dell          | Inspiron 3584               | Notebook    | [626c79c116](https://linux-hardware.org/?probe=626c79c116) | Sep 24, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL Ub 2... | Notebook    | [2b3c66f0ee](https://linux-hardware.org/?probe=2b3c66f0ee) | Sep 24, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [214a55ad3e](https://linux-hardware.org/?probe=214a55ad3e) | Sep 24, 2022 |
| Lenovo        | ThinkPad X270 20HMS1QT0E    | Notebook    | [72caf18b5f](https://linux-hardware.org/?probe=72caf18b5f) | Sep 23, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [2bb811e308](https://linux-hardware.org/?probe=2bb811e308) | Sep 23, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [5f1b4b1679](https://linux-hardware.org/?probe=5f1b4b1679) | Sep 23, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [71766e04c0](https://linux-hardware.org/?probe=71766e04c0) | Sep 23, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [8e7a7a914c](https://linux-hardware.org/?probe=8e7a7a914c) | Sep 23, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ba0d37d696](https://linux-hardware.org/?probe=ba0d37d696) | Sep 23, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [872eafe5f7](https://linux-hardware.org/?probe=872eafe5f7) | Sep 23, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [68338b3080](https://linux-hardware.org/?probe=68338b3080) | Sep 23, 2022 |
| Dell          | Vostro 3558                 | Notebook    | [61f6c99c88](https://linux-hardware.org/?probe=61f6c99c88) | Sep 22, 2022 |
| HP            | 1998                        | Desktop     | [f8399e0d3a](https://linux-hardware.org/?probe=f8399e0d3a) | Sep 22, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [3fd067abd9](https://linux-hardware.org/?probe=3fd067abd9) | Sep 21, 2022 |
| Dell          | Latitude 3490               | Notebook    | [de749eeeb8](https://linux-hardware.org/?probe=de749eeeb8) | Sep 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [c0cc0dc101](https://linux-hardware.org/?probe=c0cc0dc101) | Sep 21, 2022 |
| Acer          | Nitro AN715-51              | Notebook    | [36fb85e6cb](https://linux-hardware.org/?probe=36fb85e6cb) | Sep 21, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [cbbf373937](https://linux-hardware.org/?probe=cbbf373937) | Sep 21, 2022 |
| Gigabyte      | H310M H                     | Desktop     | [1ec0fcefa2](https://linux-hardware.org/?probe=1ec0fcefa2) | Sep 21, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [4482b2913a](https://linux-hardware.org/?probe=4482b2913a) | Sep 21, 2022 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [5175ba7e7c](https://linux-hardware.org/?probe=5175ba7e7c) | Sep 20, 2022 |
| MSI           | H410M-A PRO                 | Desktop     | [76c03610be](https://linux-hardware.org/?probe=76c03610be) | Sep 20, 2022 |
| Lenovo        | IdeaPadFlex 10 20324        | Notebook    | [4e7f3b7bac](https://linux-hardware.org/?probe=4e7f3b7bac) | Sep 19, 2022 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [43c2f57807](https://linux-hardware.org/?probe=43c2f57807) | Sep 19, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [db46d34737](https://linux-hardware.org/?probe=db46d34737) | Sep 19, 2022 |
| ASUSTek       | ROG Flow X16 GV601RE_GV6... | Convertible | [ad99d47a5e](https://linux-hardware.org/?probe=ad99d47a5e) | Sep 19, 2022 |
| Acer          | A75F2-M2 P21-A1             | Desktop     | [2d00ba463b](https://linux-hardware.org/?probe=2d00ba463b) | Sep 18, 2022 |
| Lenovo        | ThinkCentre M58e 7298A76    | Desktop     | [4775ccd67f](https://linux-hardware.org/?probe=4775ccd67f) | Sep 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECC... | Notebook    | [e09b077e89](https://linux-hardware.org/?probe=e09b077e89) | Sep 18, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [3b06edf9e6](https://linux-hardware.org/?probe=3b06edf9e6) | Sep 18, 2022 |
| MiTAC         | Cedar Trail                 | Desktop     | [75dc595c8f](https://linux-hardware.org/?probe=75dc595c8f) | Sep 17, 2022 |
| MiTAC         | Cedar Trail                 | Desktop     | [c5bd90dad6](https://linux-hardware.org/?probe=c5bd90dad6) | Sep 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [abca74f17e](https://linux-hardware.org/?probe=abca74f17e) | Sep 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [5ffc7d13ac](https://linux-hardware.org/?probe=5ffc7d13ac) | Sep 16, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [a29728a871](https://linux-hardware.org/?probe=a29728a871) | Sep 16, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [eeb58ef0f2](https://linux-hardware.org/?probe=eeb58ef0f2) | Sep 15, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [2bc992ab7e](https://linux-hardware.org/?probe=2bc992ab7e) | Sep 15, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [8dfb715f1e](https://linux-hardware.org/?probe=8dfb715f1e) | Sep 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [c70951aae5](https://linux-hardware.org/?probe=c70951aae5) | Sep 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [4b19ce2aab](https://linux-hardware.org/?probe=4b19ce2aab) | Sep 15, 2022 |
| HP            | Laptop 14s-dr2xxx           | Notebook    | [39163aba8a](https://linux-hardware.org/?probe=39163aba8a) | Sep 15, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [578cb93789](https://linux-hardware.org/?probe=578cb93789) | Sep 14, 2022 |
| Dell          | Vostro 14-3468              | Notebook    | [fbe4062b6e](https://linux-hardware.org/?probe=fbe4062b6e) | Sep 14, 2022 |
| HP            | 339A                        | Desktop     | [78e4f67b19](https://linux-hardware.org/?probe=78e4f67b19) | Sep 14, 2022 |
| HP            | 15                          | Notebook    | [79aa0d618f](https://linux-hardware.org/?probe=79aa0d618f) | Sep 14, 2022 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [23c756841a](https://linux-hardware.org/?probe=23c756841a) | Sep 14, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [9a3cc70094](https://linux-hardware.org/?probe=9a3cc70094) | Sep 13, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [423008d102](https://linux-hardware.org/?probe=423008d102) | Sep 13, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [3e5c80e004](https://linux-hardware.org/?probe=3e5c80e004) | Sep 13, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1b8d9a04ae](https://linux-hardware.org/?probe=1b8d9a04ae) | Sep 13, 2022 |
| Dell          | Vostro 3491                 | Notebook    | [24d4349627](https://linux-hardware.org/?probe=24d4349627) | Sep 12, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [644ad9d55f](https://linux-hardware.org/?probe=644ad9d55f) | Sep 12, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [d5a0bdc1a9](https://linux-hardware.org/?probe=d5a0bdc1a9) | Sep 12, 2022 |
| Gigabyte      | H61MS                       | Desktop     | [9b10176111](https://linux-hardware.org/?probe=9b10176111) | Sep 12, 2022 |
| Dell          | Precision 5560              | Notebook    | [3120c2b781](https://linux-hardware.org/?probe=3120c2b781) | Sep 12, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [3f9a1f3db0](https://linux-hardware.org/?probe=3f9a1f3db0) | Sep 11, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [49fe1c56a3](https://linux-hardware.org/?probe=49fe1c56a3) | Sep 11, 2022 |
| Samsung       | 750XED                      | Notebook    | [ea68f0910d](https://linux-hardware.org/?probe=ea68f0910d) | Sep 10, 2022 |
| Samsung       | 750XED                      | Notebook    | [475088329e](https://linux-hardware.org/?probe=475088329e) | Sep 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [5a7c8dfacf](https://linux-hardware.org/?probe=5a7c8dfacf) | Sep 10, 2022 |
| Dell          | Precision 5560              | Notebook    | [f70da50728](https://linux-hardware.org/?probe=f70da50728) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [f752846656](https://linux-hardware.org/?probe=f752846656) | Sep 09, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [3397f75941](https://linux-hardware.org/?probe=3397f75941) | Sep 09, 2022 |
| Acer          | Aspire A315-58              | Notebook    | [5af4c5d3e1](https://linux-hardware.org/?probe=5af4c5d3e1) | Sep 09, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [871de5472c](https://linux-hardware.org/?probe=871de5472c) | Sep 08, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [fad1689295](https://linux-hardware.org/?probe=fad1689295) | Sep 08, 2022 |
| ASUSTek       | K53U                        | Notebook    | [d13ff70895](https://linux-hardware.org/?probe=d13ff70895) | Sep 08, 2022 |
| Gigabyte      | G41MT-S2                    | Desktop     | [1441e1783d](https://linux-hardware.org/?probe=1441e1783d) | Sep 06, 2022 |
| MSI           | 760GM-P21                   | Desktop     | [c3eb52f6ab](https://linux-hardware.org/?probe=c3eb52f6ab) | Sep 06, 2022 |
| Acer          | Aspire 5745                 | Notebook    | [39bc7728ac](https://linux-hardware.org/?probe=39bc7728ac) | Sep 06, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [1fd4585410](https://linux-hardware.org/?probe=1fd4585410) | Sep 06, 2022 |
| Lenovo        | G560 20042                  | Notebook    | [c661e65b46](https://linux-hardware.org/?probe=c661e65b46) | Sep 04, 2022 |
| Lenovo        | G560 20042                  | Notebook    | [ad86775475](https://linux-hardware.org/?probe=ad86775475) | Sep 04, 2022 |
| Dell          | Inspiron 3576               | Notebook    | [8f5998a9e4](https://linux-hardware.org/?probe=8f5998a9e4) | Sep 04, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [1c24950db2](https://linux-hardware.org/?probe=1c24950db2) | Sep 04, 2022 |
| Dell          | Vostro 3480                 | Notebook    | [65c846d249](https://linux-hardware.org/?probe=65c846d249) | Sep 03, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [2199481d0a](https://linux-hardware.org/?probe=2199481d0a) | Sep 03, 2022 |
| Dell          | Inspiron 5577               | Notebook    | [b06eacf424](https://linux-hardware.org/?probe=b06eacf424) | Sep 02, 2022 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [319d526423](https://linux-hardware.org/?probe=319d526423) | Sep 02, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [5b1f25ca62](https://linux-hardware.org/?probe=5b1f25ca62) | Sep 01, 2022 |
| Gigabyte      | H81M-WW                     | Desktop     | [2a56f256a3](https://linux-hardware.org/?probe=2a56f256a3) | Sep 01, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [c9841acd77](https://linux-hardware.org/?probe=c9841acd77) | Sep 01, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [e1b27f8003](https://linux-hardware.org/?probe=e1b27f8003) | Aug 31, 2022 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [6f3bb6200f](https://linux-hardware.org/?probe=6f3bb6200f) | Aug 31, 2022 |
| HP            | Notebook                    | Notebook    | [2ca7fbbfa9](https://linux-hardware.org/?probe=2ca7fbbfa9) | Aug 31, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [30457b898c](https://linux-hardware.org/?probe=30457b898c) | Aug 30, 2022 |
| ASUSTek       | ZenBook UX334FAC_UX333FA... | Notebook    | [ae84021e13](https://linux-hardware.org/?probe=ae84021e13) | Aug 30, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | Notebook    | [777f18537c](https://linux-hardware.org/?probe=777f18537c) | Aug 30, 2022 |
| Dell          | Latitude 3440               | Notebook    | [3e3f5ac9ab](https://linux-hardware.org/?probe=3e3f5ac9ab) | Aug 29, 2022 |
| HP            | Notebook                    | Notebook    | [e00cfcb387](https://linux-hardware.org/?probe=e00cfcb387) | Aug 29, 2022 |
| WIPRO         | G31T-M                      | Desktop     | [51cea718eb](https://linux-hardware.org/?probe=51cea718eb) | Aug 28, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [1a76248bf8](https://linux-hardware.org/?probe=1a76248bf8) | Aug 28, 2022 |
| Dell          | OptiPlex 3020M              | Desktop     | [84f424cfb7](https://linux-hardware.org/?probe=84f424cfb7) | Aug 28, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [608a16dc64](https://linux-hardware.org/?probe=608a16dc64) | Aug 27, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [1c87349faa](https://linux-hardware.org/?probe=1c87349faa) | Aug 27, 2022 |
| Gigabyte      | H61MS                       | Desktop     | [8ccf243309](https://linux-hardware.org/?probe=8ccf243309) | Aug 27, 2022 |
| Gigabyte      | H61MS                       | Desktop     | [24164369fd](https://linux-hardware.org/?probe=24164369fd) | Aug 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21E4C... | Notebook    | [cf1b2ff13c](https://linux-hardware.org/?probe=cf1b2ff13c) | Aug 27, 2022 |
| Lenovo        | ThinkPad X260 20F5A050IG    | Notebook    | [33b5154a7a](https://linux-hardware.org/?probe=33b5154a7a) | Aug 27, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [783495e971](https://linux-hardware.org/?probe=783495e971) | Aug 25, 2022 |
| Lenovo        | ThinkPad L490 20Q5S0LF00    | Notebook    | [3c1287dfd2](https://linux-hardware.org/?probe=3c1287dfd2) | Aug 25, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [f4862a3793](https://linux-hardware.org/?probe=f4862a3793) | Aug 25, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 Ub 82KU    | Notebook    | [5237518074](https://linux-hardware.org/?probe=5237518074) | Aug 25, 2022 |
| HP            | 15                          | Notebook    | [832c6247b2](https://linux-hardware.org/?probe=832c6247b2) | Aug 25, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [d988e1aeb9](https://linux-hardware.org/?probe=d988e1aeb9) | Aug 25, 2022 |
| Lenovo        | IdeaPad S540-15IML D 81N... | Notebook    | [a0c40a81ec](https://linux-hardware.org/?probe=a0c40a81ec) | Aug 24, 2022 |
| Gigabyte      | H81M-S                      | Desktop     | [0b1e1d125d](https://linux-hardware.org/?probe=0b1e1d125d) | Aug 23, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [cc66ac722b](https://linux-hardware.org/?probe=cc66ac722b) | Aug 23, 2022 |
| MSI           | H310M PRO-VH PLUS           | Desktop     | [b177563e19](https://linux-hardware.org/?probe=b177563e19) | Aug 23, 2022 |
| Dell          | Vostro 5481                 | Notebook    | [749e6c3622](https://linux-hardware.org/?probe=749e6c3622) | Aug 23, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [62dbb0625f](https://linux-hardware.org/?probe=62dbb0625f) | Aug 23, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [e5442dd2d4](https://linux-hardware.org/?probe=e5442dd2d4) | Aug 23, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [97772a7cb6](https://linux-hardware.org/?probe=97772a7cb6) | Aug 23, 2022 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [cb43b7a4cf](https://linux-hardware.org/?probe=cb43b7a4cf) | Aug 22, 2022 |
| Intel         | H61                         | Desktop     | [f2a42b45ca](https://linux-hardware.org/?probe=f2a42b45ca) | Aug 22, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [b41e95cd1b](https://linux-hardware.org/?probe=b41e95cd1b) | Aug 22, 2022 |
| Acer          | TravelMate P215-52G         | Notebook    | [1d36fcbc9f](https://linux-hardware.org/?probe=1d36fcbc9f) | Aug 21, 2022 |
| HP            | Notebook                    | Notebook    | [bd5bad0b49](https://linux-hardware.org/?probe=bd5bad0b49) | Aug 21, 2022 |
| Dell          | G3 3500                     | Notebook    | [1e8edd3350](https://linux-hardware.org/?probe=1e8edd3350) | Aug 21, 2022 |
| eMachines     | D725                        | Notebook    | [34394fab35](https://linux-hardware.org/?probe=34394fab35) | Aug 21, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [9a8166de9b](https://linux-hardware.org/?probe=9a8166de9b) | Aug 20, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [32e59cda1c](https://linux-hardware.org/?probe=32e59cda1c) | Aug 20, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [3f6370f978](https://linux-hardware.org/?probe=3f6370f978) | Aug 20, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [ac28d2918e](https://linux-hardware.org/?probe=ac28d2918e) | Aug 20, 2022 |
| OEM           | Intel H81                   | Desktop     | [5e354c60d1](https://linux-hardware.org/?probe=5e354c60d1) | Aug 20, 2022 |
| HP            | 81C5 MVB                    | Desktop     | [86a0520dc6](https://linux-hardware.org/?probe=86a0520dc6) | Aug 20, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [93c259f492](https://linux-hardware.org/?probe=93c259f492) | Aug 20, 2022 |
| HP            | 15                          | Notebook    | [4d736aca15](https://linux-hardware.org/?probe=4d736aca15) | Aug 20, 2022 |
| ASUSTek       | PRIME B365M-C               | Desktop     | [8ae386a7a0](https://linux-hardware.org/?probe=8ae386a7a0) | Aug 20, 2022 |
| ASUSTek       | H110M-CS                    | Desktop     | [df6dff3fa3](https://linux-hardware.org/?probe=df6dff3fa3) | Aug 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [f095219c78](https://linux-hardware.org/?probe=f095219c78) | Aug 19, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b97f13141f](https://linux-hardware.org/?probe=b97f13141f) | Aug 19, 2022 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [61f9640136](https://linux-hardware.org/?probe=61f9640136) | Aug 19, 2022 |
| HP            | 15                          | Notebook    | [166efee25e](https://linux-hardware.org/?probe=166efee25e) | Aug 19, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [7a9624c968](https://linux-hardware.org/?probe=7a9624c968) | Aug 19, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [0ed8a39444](https://linux-hardware.org/?probe=0ed8a39444) | Aug 19, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [46208653fa](https://linux-hardware.org/?probe=46208653fa) | Aug 18, 2022 |
| Dell          | Latitude 3420               | Notebook    | [49300ca856](https://linux-hardware.org/?probe=49300ca856) | Aug 18, 2022 |
| ASUSTek       | X542UQR                     | Notebook    | [4c8af9dc73](https://linux-hardware.org/?probe=4c8af9dc73) | Aug 18, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [dcb33e35ae](https://linux-hardware.org/?probe=dcb33e35ae) | Aug 18, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [ae2d8ade73](https://linux-hardware.org/?probe=ae2d8ade73) | Aug 18, 2022 |
| Acer          | Aspire E1-431               | Notebook    | [d4132b425f](https://linux-hardware.org/?probe=d4132b425f) | Aug 17, 2022 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [944a99ea66](https://linux-hardware.org/?probe=944a99ea66) | Aug 17, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [e6e4efd93a](https://linux-hardware.org/?probe=e6e4efd93a) | Aug 17, 2022 |
| Acer          | Nitro AN515-56              | Notebook    | [c62f8ea53b](https://linux-hardware.org/?probe=c62f8ea53b) | Aug 17, 2022 |
| ASUSTek       | X542UQR                     | Notebook    | [8236615818](https://linux-hardware.org/?probe=8236615818) | Aug 17, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [32ccd17130](https://linux-hardware.org/?probe=32ccd17130) | Aug 17, 2022 |
| Dell          | Latitude 3420               | Notebook    | [33a254b0e0](https://linux-hardware.org/?probe=33a254b0e0) | Aug 17, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [e5dbfdb922](https://linux-hardware.org/?probe=e5dbfdb922) | Aug 16, 2022 |
| Dell          | Vostro 2420                 | Notebook    | [1d2b1aa4bf](https://linux-hardware.org/?probe=1d2b1aa4bf) | Aug 16, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [1b12b01004](https://linux-hardware.org/?probe=1b12b01004) | Aug 16, 2022 |
| Dell          | Inspiron 5491 2n1           | Convertible | [6c0375d442](https://linux-hardware.org/?probe=6c0375d442) | Aug 16, 2022 |
| Toshiba       | TECRA R940                  | Notebook    | [f7a6618519](https://linux-hardware.org/?probe=f7a6618519) | Aug 14, 2022 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [265b666497](https://linux-hardware.org/?probe=265b666497) | Aug 14, 2022 |
| MSI           | Alpha 15 A3DD               | Notebook    | [fd548daf00](https://linux-hardware.org/?probe=fd548daf00) | Aug 14, 2022 |
| HP            | Presario CQ56               | Notebook    | [48dfc2da91](https://linux-hardware.org/?probe=48dfc2da91) | Aug 13, 2022 |
| Dell          | Latitude E6420              | Notebook    | [e295e29aa3](https://linux-hardware.org/?probe=e295e29aa3) | Aug 13, 2022 |
| HP            | Pavilion 15                 | Notebook    | [bafa6bfcb8](https://linux-hardware.org/?probe=bafa6bfcb8) | Aug 13, 2022 |
| Lenovo        | IdeaPad 3 15IML05 D1 81W... | Notebook    | [59b3324e73](https://linux-hardware.org/?probe=59b3324e73) | Aug 13, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [f8a6209b06](https://linux-hardware.org/?probe=f8a6209b06) | Aug 12, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [8c6f00600e](https://linux-hardware.org/?probe=8c6f00600e) | Aug 12, 2022 |
| ASUSTek       | H110M-CS                    | Desktop     | [80982f87bb](https://linux-hardware.org/?probe=80982f87bb) | Aug 12, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [1604d7a824](https://linux-hardware.org/?probe=1604d7a824) | Aug 11, 2022 |
| Dell          | Vostro 3401                 | Notebook    | [29f3354492](https://linux-hardware.org/?probe=29f3354492) | Aug 11, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [bc7a8afe56](https://linux-hardware.org/?probe=bc7a8afe56) | Aug 11, 2022 |
| Dell          | Inspiron 3584               | Notebook    | [3ba16dc3e1](https://linux-hardware.org/?probe=3ba16dc3e1) | Aug 11, 2022 |
| Dell          | Latitude E7450              | Notebook    | [3992650626](https://linux-hardware.org/?probe=3992650626) | Aug 10, 2022 |
| HP            | 2B2F MVB,A                  | All in one  | [13aef3e1ef](https://linux-hardware.org/?probe=13aef3e1ef) | Aug 10, 2022 |
| HP            | 245 G7 Notebook PC          | Notebook    | [567786673d](https://linux-hardware.org/?probe=567786673d) | Aug 10, 2022 |
| Dell          | Vostro 3480                 | Notebook    | [31b062c315](https://linux-hardware.org/?probe=31b062c315) | Aug 10, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [48722889b6](https://linux-hardware.org/?probe=48722889b6) | Aug 10, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [a24161deaa](https://linux-hardware.org/?probe=a24161deaa) | Aug 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [364f2e0a23](https://linux-hardware.org/?probe=364f2e0a23) | Aug 09, 2022 |
| HP            | Pavilion g6                 | Notebook    | [4b6fc67f06](https://linux-hardware.org/?probe=4b6fc67f06) | Aug 09, 2022 |
| Dell          | System XPS L502X            | Notebook    | [1453afc507](https://linux-hardware.org/?probe=1453afc507) | Aug 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [e4c7906333](https://linux-hardware.org/?probe=e4c7906333) | Aug 09, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [dab9f235f5](https://linux-hardware.org/?probe=dab9f235f5) | Aug 09, 2022 |
| ASUSTek       | UX430UAR                    | Notebook    | [e11856fcbc](https://linux-hardware.org/?probe=e11856fcbc) | Aug 09, 2022 |
| Timi          | Mi NoteBook Horizon Edit... | Notebook    | [52a0cb298b](https://linux-hardware.org/?probe=52a0cb298b) | Aug 09, 2022 |
| ASUSTek       | H110M-CS                    | Desktop     | [98c601bb55](https://linux-hardware.org/?probe=98c601bb55) | Aug 08, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [b719fff96d](https://linux-hardware.org/?probe=b719fff96d) | Aug 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [49c2378f28](https://linux-hardware.org/?probe=49c2378f28) | Aug 08, 2022 |
| Dell          | Latitude 3510               | Notebook    | [5dd81ae3c1](https://linux-hardware.org/?probe=5dd81ae3c1) | Aug 08, 2022 |
| HP            | 15                          | Notebook    | [ef66e0296e](https://linux-hardware.org/?probe=ef66e0296e) | Aug 08, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [d3f41ae4fb](https://linux-hardware.org/?probe=d3f41ae4fb) | Aug 08, 2022 |
| HP            | 2B2F MVB,A                  | All in one  | [f58caefd4f](https://linux-hardware.org/?probe=f58caefd4f) | Aug 08, 2022 |
| ASUSTek       | H110M-CS                    | Desktop     | [01e4feaac6](https://linux-hardware.org/?probe=01e4feaac6) | Aug 07, 2022 |
| HP            | Pavilion g6                 | Notebook    | [aa437aea14](https://linux-hardware.org/?probe=aa437aea14) | Aug 07, 2022 |
| HP            | Laptop 15s-gr0xxx           | Notebook    | [457fa11671](https://linux-hardware.org/?probe=457fa11671) | Aug 07, 2022 |
| HP            | Pavilion g6                 | Notebook    | [7543f383ad](https://linux-hardware.org/?probe=7543f383ad) | Aug 07, 2022 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | Notebook    | [8f7ef1d997](https://linux-hardware.org/?probe=8f7ef1d997) | Aug 07, 2022 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | Notebook    | [ffab2b901d](https://linux-hardware.org/?probe=ffab2b901d) | Aug 07, 2022 |
| HP            | Pavilion g6                 | Notebook    | [955d372528](https://linux-hardware.org/?probe=955d372528) | Aug 06, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [7e9b1406b1](https://linux-hardware.org/?probe=7e9b1406b1) | Aug 06, 2022 |
| Sony          | VPCEB16FG                   | Notebook    | [6baf989163](https://linux-hardware.org/?probe=6baf989163) | Aug 06, 2022 |
| HP            | 430                         | Notebook    | [c30f00d442](https://linux-hardware.org/?probe=c30f00d442) | Aug 05, 2022 |
| ASUSTek       | D340MC-C                    | Desktop     | [69ddbb7acd](https://linux-hardware.org/?probe=69ddbb7acd) | Aug 05, 2022 |
| ASUSTek       | D340MC-C                    | Desktop     | [a87fc1ec66](https://linux-hardware.org/?probe=a87fc1ec66) | Aug 05, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [e2545a7011](https://linux-hardware.org/?probe=e2545a7011) | Aug 04, 2022 |
| Dell          | Latitude E7470              | Notebook    | [16fd81987c](https://linux-hardware.org/?probe=16fd81987c) | Aug 04, 2022 |
| Gigabyte      | B360M GAMING HD             | Desktop     | [95e1eb0fcb](https://linux-hardware.org/?probe=95e1eb0fcb) | Aug 03, 2022 |
| LORD ELECT... | GM965 Series                | Desktop     | [b60dce21e7](https://linux-hardware.org/?probe=b60dce21e7) | Aug 03, 2022 |
| Acidanther... | Mac-CFF7D910A743CAAF iMa... | All in one  | [00c5ed086b](https://linux-hardware.org/?probe=00c5ed086b) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [4c75e1d374](https://linux-hardware.org/?probe=4c75e1d374) | Aug 03, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [91581d4ecd](https://linux-hardware.org/?probe=91581d4ecd) | Aug 02, 2022 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [ad8af5c718](https://linux-hardware.org/?probe=ad8af5c718) | Aug 02, 2022 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [b4e172e88b](https://linux-hardware.org/?probe=b4e172e88b) | Aug 02, 2022 |
| LG Electro... | 14Z990-V.AR52A2             | Notebook    | [6a1b44dfe0](https://linux-hardware.org/?probe=6a1b44dfe0) | Aug 02, 2022 |
| Dell          | G3 3500                     | Notebook    | [440b43e5e5](https://linux-hardware.org/?probe=440b43e5e5) | Aug 02, 2022 |
| Dell          | Latitude 3410               | Notebook    | [b2d717d59e](https://linux-hardware.org/?probe=b2d717d59e) | Aug 02, 2022 |
| HP            | Pavilion g6                 | Notebook    | [b48c146eff](https://linux-hardware.org/?probe=b48c146eff) | Aug 01, 2022 |
| Acer          | Aspire 5560                 | Notebook    | [d5b8ae56fd](https://linux-hardware.org/?probe=d5b8ae56fd) | Aug 01, 2022 |
| HP            | ProBook 440 G2              | Notebook    | [00dd80ba31](https://linux-hardware.org/?probe=00dd80ba31) | Aug 01, 2022 |
| Intel         | DH55TC AAE70932-303         | Desktop     | [f275229d83](https://linux-hardware.org/?probe=f275229d83) | Jul 31, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [8707ea39a2](https://linux-hardware.org/?probe=8707ea39a2) | Jul 31, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [09c15c1ed8](https://linux-hardware.org/?probe=09c15c1ed8) | Jul 31, 2022 |
| MSI           | Prestige 15 A10SC           | Notebook    | [9c161b860f](https://linux-hardware.org/?probe=9c161b860f) | Jul 31, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [b846739765](https://linux-hardware.org/?probe=b846739765) | Jul 30, 2022 |
| Acer          | Aspire A715-41G             | Notebook    | [3881e3998f](https://linux-hardware.org/?probe=3881e3998f) | Jul 30, 2022 |
| Dell          | Inspiron 3541               | Notebook    | [ab643dc6b0](https://linux-hardware.org/?probe=ab643dc6b0) | Jul 30, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [d67c93b534](https://linux-hardware.org/?probe=d67c93b534) | Jul 29, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [a42627d17e](https://linux-hardware.org/?probe=a42627d17e) | Jul 29, 2022 |
| Dell          | 05XTT1 A01                  | Mini pc     | [c4ce2965af](https://linux-hardware.org/?probe=c4ce2965af) | Jul 29, 2022 |
| Lenovo        | ThinkPad X230 23253B3       | Notebook    | [fa19ec3adf](https://linux-hardware.org/?probe=fa19ec3adf) | Jul 29, 2022 |
| Intel         | IS80 V117                   | Notebook    | [cf45970313](https://linux-hardware.org/?probe=cf45970313) | Jul 29, 2022 |
| Acer          | Aspire A715-42G             | Notebook    | [8d87e3bb3b](https://linux-hardware.org/?probe=8d87e3bb3b) | Jul 28, 2022 |
| HP            | Pavilion 15                 | Notebook    | [512f5ada4a](https://linux-hardware.org/?probe=512f5ada4a) | Jul 28, 2022 |
| Lenovo        | Yoga 510-14AST 80S9         | Convertible | [afaf75a141](https://linux-hardware.org/?probe=afaf75a141) | Jul 28, 2022 |
| HP            | Pavilion 15                 | Notebook    | [b74fec46a0](https://linux-hardware.org/?probe=b74fec46a0) | Jul 28, 2022 |
| HP            | 348 G4                      | Notebook    | [034e49f6dc](https://linux-hardware.org/?probe=034e49f6dc) | Jul 28, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [f84c29c4b6](https://linux-hardware.org/?probe=f84c29c4b6) | Jul 27, 2022 |
| Sony          | VPCEB26FG                   | Notebook    | [49c139799c](https://linux-hardware.org/?probe=49c139799c) | Jul 27, 2022 |
| HP            | 86E9 A                      | Desktop     | [6634eaee32](https://linux-hardware.org/?probe=6634eaee32) | Jul 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [89398a36b1](https://linux-hardware.org/?probe=89398a36b1) | Jul 27, 2022 |
| HP            | 15                          | Notebook    | [9177a1f411](https://linux-hardware.org/?probe=9177a1f411) | Jul 26, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [f9203ffeed](https://linux-hardware.org/?probe=f9203ffeed) | Jul 26, 2022 |
| Dell          | Latitude 3410               | Notebook    | [20636bf80f](https://linux-hardware.org/?probe=20636bf80f) | Jul 26, 2022 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [c9534903a2](https://linux-hardware.org/?probe=c9534903a2) | Jul 26, 2022 |
| Dell          | Latitude 3440               | Notebook    | [a47121441e](https://linux-hardware.org/?probe=a47121441e) | Jul 25, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [da71f235a2](https://linux-hardware.org/?probe=da71f235a2) | Jul 25, 2022 |
| Acer          | Predator PH315-52           | Notebook    | [a1346acc8a](https://linux-hardware.org/?probe=a1346acc8a) | Jul 25, 2022 |
| Dell          | Vostro 3491                 | Notebook    | [6ce65dccb7](https://linux-hardware.org/?probe=6ce65dccb7) | Jul 24, 2022 |
| Dell          | Inspiron 3537               | Notebook    | [df25f468ef](https://linux-hardware.org/?probe=df25f468ef) | Jul 24, 2022 |
| Dell          | Inspiron 3537               | Notebook    | [acc1cd1dcf](https://linux-hardware.org/?probe=acc1cd1dcf) | Jul 24, 2022 |
| Lenovo        | E41-25 81FS                 | Notebook    | [51b984566a](https://linux-hardware.org/?probe=51b984566a) | Jul 24, 2022 |
| Google        | Wolf                        | Notebook    | [f2397aadef](https://linux-hardware.org/?probe=f2397aadef) | Jul 23, 2022 |
| Google        | Wolf                        | Notebook    | [ffa74c4dc0](https://linux-hardware.org/?probe=ffa74c4dc0) | Jul 23, 2022 |
| HP            | Laptop 14q-bu1xx            | Notebook    | [7fa58abd22](https://linux-hardware.org/?probe=7fa58abd22) | Jul 23, 2022 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [492b4e1236](https://linux-hardware.org/?probe=492b4e1236) | Jul 23, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [9002ca2e54](https://linux-hardware.org/?probe=9002ca2e54) | Jul 23, 2022 |
| Acer          | Predator PH315-54           | Notebook    | [e06076002a](https://linux-hardware.org/?probe=e06076002a) | Jul 22, 2022 |
| Lenovo        | ThinkPad T490 20RYS01J00    | Notebook    | [415229917b](https://linux-hardware.org/?probe=415229917b) | Jul 22, 2022 |
| Sony          | SVF15318SNB                 | Notebook    | [176c871bf8](https://linux-hardware.org/?probe=176c871bf8) | Jul 22, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [b0a8b9eb01](https://linux-hardware.org/?probe=b0a8b9eb01) | Jul 21, 2022 |
| HP            | 3397                        | Desktop     | [017afa048c](https://linux-hardware.org/?probe=017afa048c) | Jul 20, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [ef41a8c220](https://linux-hardware.org/?probe=ef41a8c220) | Jul 20, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YES... | Notebook    | [48e2fa9544](https://linux-hardware.org/?probe=48e2fa9544) | Jul 19, 2022 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [db7cb6f32b](https://linux-hardware.org/?probe=db7cb6f32b) | Jul 18, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [c1c146a0f9](https://linux-hardware.org/?probe=c1c146a0f9) | Jul 18, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [672bba3723](https://linux-hardware.org/?probe=672bba3723) | Jul 17, 2022 |
| HP            | ProBook 4441s               | Notebook    | [b108eaada9](https://linux-hardware.org/?probe=b108eaada9) | Jul 17, 2022 |
| Dell          | 0Y2YM6 A00                  | Desktop     | [8b5480a55e](https://linux-hardware.org/?probe=8b5480a55e) | Jul 16, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [79168ebd0b](https://linux-hardware.org/?probe=79168ebd0b) | Jul 16, 2022 |
| Alienware     | 15 R2                       | Notebook    | [8a6bd6054f](https://linux-hardware.org/?probe=8a6bd6054f) | Jul 16, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [42de47cdc1](https://linux-hardware.org/?probe=42de47cdc1) | Jul 15, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 Ua 81W... | Notebook    | [513e2ede59](https://linux-hardware.org/?probe=513e2ede59) | Jul 15, 2022 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [a55538b651](https://linux-hardware.org/?probe=a55538b651) | Jul 14, 2022 |
| Teclast       | TbooK 10 S                  | Tablet      | [127f1fa76a](https://linux-hardware.org/?probe=127f1fa76a) | Jul 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [a8d726c8b2](https://linux-hardware.org/?probe=a8d726c8b2) | Jul 14, 2022 |
| HP            | Notebook -15q-bu004tu       | Notebook    | [b15814c3b1](https://linux-hardware.org/?probe=b15814c3b1) | Jul 14, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [b78b735f01](https://linux-hardware.org/?probe=b78b735f01) | Jul 14, 2022 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [fc969f7c75](https://linux-hardware.org/?probe=fc969f7c75) | Jul 13, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 Ua 81W... | Notebook    | [f0a069d567](https://linux-hardware.org/?probe=f0a069d567) | Jul 13, 2022 |
| HP            | Notebook -15q-bu004tu       | Notebook    | [f45fde1a93](https://linux-hardware.org/?probe=f45fde1a93) | Jul 13, 2022 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [c9842baa35](https://linux-hardware.org/?probe=c9842baa35) | Jul 12, 2022 |
| Lenovo        | ThinkPad X230 2325SDE       | Notebook    | [a002ac843c](https://linux-hardware.org/?probe=a002ac843c) | Jul 12, 2022 |
| Lenovo        | ThinkPad X230 2325SDE       | Notebook    | [79ecbebabd](https://linux-hardware.org/?probe=79ecbebabd) | Jul 12, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [aba10c973c](https://linux-hardware.org/?probe=aba10c973c) | Jul 11, 2022 |
| ASUSTek       | X541UJ                      | Notebook    | [1725714269](https://linux-hardware.org/?probe=1725714269) | Jul 11, 2022 |
| ASUSTek       | X541UJ                      | Notebook    | [cc10e6800a](https://linux-hardware.org/?probe=cc10e6800a) | Jul 11, 2022 |
| HP            | Pavilion 15                 | Notebook    | [2bfb2ba391](https://linux-hardware.org/?probe=2bfb2ba391) | Jul 11, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [41b46c06f1](https://linux-hardware.org/?probe=41b46c06f1) | Jul 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [1755faf164](https://linux-hardware.org/?probe=1755faf164) | Jul 11, 2022 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [46e84f6c32](https://linux-hardware.org/?probe=46e84f6c32) | Jul 10, 2022 |
| Intel         | DH61WW AAG23116-301         | Desktop     | [3b4120b3af](https://linux-hardware.org/?probe=3b4120b3af) | Jul 09, 2022 |
| ASUSTek       | X507UB                      | Notebook    | [53a07e58b8](https://linux-hardware.org/?probe=53a07e58b8) | Jul 09, 2022 |
| Lenovo        | IdeaPad 305-15IBD 80NJ      | Notebook    | [95ff55839b](https://linux-hardware.org/?probe=95ff55839b) | Jul 09, 2022 |
| HP            | ProBook 440 G2              | Notebook    | [a2a01affe3](https://linux-hardware.org/?probe=a2a01affe3) | Jul 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [b3cdd2b6f6](https://linux-hardware.org/?probe=b3cdd2b6f6) | Jul 09, 2022 |
| Intel         | H81                         | Desktop     | [e1a730a6e6](https://linux-hardware.org/?probe=e1a730a6e6) | Jul 08, 2022 |
| HP            | 15                          | Notebook    | [a7bfa741b3](https://linux-hardware.org/?probe=a7bfa741b3) | Jul 08, 2022 |
| HP            | Laptop 15-da1xxx            | Notebook    | [ec18f88382](https://linux-hardware.org/?probe=ec18f88382) | Jul 07, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [c9eb8f9a5f](https://linux-hardware.org/?probe=c9eb8f9a5f) | Jul 07, 2022 |
| Dell          | 0HD5W2 A01                  | Desktop     | [f9d01cacbb](https://linux-hardware.org/?probe=f9d01cacbb) | Jul 07, 2022 |
| HP            | 3397                        | Desktop     | [5f251b624d](https://linux-hardware.org/?probe=5f251b624d) | Jul 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [16c6df7b29](https://linux-hardware.org/?probe=16c6df7b29) | Jul 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [6b25430dc1](https://linux-hardware.org/?probe=6b25430dc1) | Jul 07, 2022 |
| Toshiba       | Satellite L650              | Notebook    | [76de8069a0](https://linux-hardware.org/?probe=76de8069a0) | Jul 07, 2022 |
| HP            | Mini 110-3100               | Notebook    | [5222f63258](https://linux-hardware.org/?probe=5222f63258) | Jul 06, 2022 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | Desktop     | [342362a5f8](https://linux-hardware.org/?probe=342362a5f8) | Jul 06, 2022 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | Desktop     | [21f58df6b0](https://linux-hardware.org/?probe=21f58df6b0) | Jul 06, 2022 |
| Dell          | Precision 5530              | Notebook    | [cbe37ac52f](https://linux-hardware.org/?probe=cbe37ac52f) | Jul 05, 2022 |
| Dell          | Latitude 3540               | Notebook    | [a689d5019b](https://linux-hardware.org/?probe=a689d5019b) | Jul 05, 2022 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [4f82c838cb](https://linux-hardware.org/?probe=4f82c838cb) | Jul 04, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [697729549b](https://linux-hardware.org/?probe=697729549b) | Jul 04, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [dc6e8358f8](https://linux-hardware.org/?probe=dc6e8358f8) | Jul 04, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [7d5ee550de](https://linux-hardware.org/?probe=7d5ee550de) | Jul 04, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [31226ebc70](https://linux-hardware.org/?probe=31226ebc70) | Jul 04, 2022 |
| HP            | Notebook                    | Notebook    | [b9eb2e4cdd](https://linux-hardware.org/?probe=b9eb2e4cdd) | Jul 04, 2022 |
| HP            | Laptop 15s-du2xxx           | Notebook    | [c208a1e955](https://linux-hardware.org/?probe=c208a1e955) | Jul 04, 2022 |
| HP            | Laptop 15s-du2xxx           | Notebook    | [65debb520a](https://linux-hardware.org/?probe=65debb520a) | Jul 04, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [2a4654f61b](https://linux-hardware.org/?probe=2a4654f61b) | Jul 03, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [ff830000cf](https://linux-hardware.org/?probe=ff830000cf) | Jul 03, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [5f2c58d24a](https://linux-hardware.org/?probe=5f2c58d24a) | Jul 03, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [8a10d711f8](https://linux-hardware.org/?probe=8a10d711f8) | Jul 03, 2022 |
| Dell          | Vostro 2420                 | Notebook    | [ce9585eac5](https://linux-hardware.org/?probe=ce9585eac5) | Jul 03, 2022 |
| MSI           | B365M PRO-VDH               | Desktop     | [8ce7059868](https://linux-hardware.org/?probe=8ce7059868) | Jul 03, 2022 |
| Gigabyte      | H81M-S                      | Desktop     | [4a6acd9191](https://linux-hardware.org/?probe=4a6acd9191) | Jul 02, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [fdb841889e](https://linux-hardware.org/?probe=fdb841889e) | Jul 02, 2022 |
| ASUSTek       | TUF Gaming FX705DD_FX705... | Notebook    | [048a900062](https://linux-hardware.org/?probe=048a900062) | Jul 02, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [dffcf6cd44](https://linux-hardware.org/?probe=dffcf6cd44) | Jul 02, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [54a9d6bcb3](https://linux-hardware.org/?probe=54a9d6bcb3) | Jul 02, 2022 |
| Lenovo        | Erazer Y50-70               | Notebook    | [c147e10488](https://linux-hardware.org/?probe=c147e10488) | Jul 02, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [9034bf7260](https://linux-hardware.org/?probe=9034bf7260) | Jul 01, 2022 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [0364230bc7](https://linux-hardware.org/?probe=0364230bc7) | Jul 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | Notebook    | [430c2e6760](https://linux-hardware.org/?probe=430c2e6760) | Jul 01, 2022 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [7e809da3ad](https://linux-hardware.org/?probe=7e809da3ad) | Jul 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f54987d748](https://linux-hardware.org/?probe=f54987d748) | Jul 01, 2022 |
| HP            | Laptop 15s-du2xxx           | Notebook    | [13e85826c2](https://linux-hardware.org/?probe=13e85826c2) | Jun 30, 2022 |
| HP            | Laptop 15s-du2xxx           | Notebook    | [bb4df4398e](https://linux-hardware.org/?probe=bb4df4398e) | Jun 30, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDC... | Notebook    | [f29c4de6b4](https://linux-hardware.org/?probe=f29c4de6b4) | Jun 30, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDC... | Notebook    | [7ecd760977](https://linux-hardware.org/?probe=7ecd760977) | Jun 30, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDC... | Notebook    | [8428ba0120](https://linux-hardware.org/?probe=8428ba0120) | Jun 30, 2022 |
| Gigabyte      | GB-BSi5-1135G7              | Desktop     | [4701b81ce2](https://linux-hardware.org/?probe=4701b81ce2) | Jun 30, 2022 |
| HP            | 1000                        | Notebook    | [65ae23140e](https://linux-hardware.org/?probe=65ae23140e) | Jun 30, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [1f9d3b4a6c](https://linux-hardware.org/?probe=1f9d3b4a6c) | Jun 29, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [0244eb4fde](https://linux-hardware.org/?probe=0244eb4fde) | Jun 29, 2022 |
| MSI           | A320M PRO-VD/S V2           | Desktop     | [fc5a5d812c](https://linux-hardware.org/?probe=fc5a5d812c) | Jun 29, 2022 |
| Acer          | H81-M1                      | Desktop     | [9ddfb2ec8d](https://linux-hardware.org/?probe=9ddfb2ec8d) | Jun 28, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [d240efa39f](https://linux-hardware.org/?probe=d240efa39f) | Jun 28, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [dc3e219327](https://linux-hardware.org/?probe=dc3e219327) | Jun 28, 2022 |
| Lenovo        | B41-80 80LG                 | Notebook    | [30f6e726bd](https://linux-hardware.org/?probe=30f6e726bd) | Jun 28, 2022 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [404e9daae2](https://linux-hardware.org/?probe=404e9daae2) | Jun 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [bd912e1acc](https://linux-hardware.org/?probe=bd912e1acc) | Jun 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [569faf34f1](https://linux-hardware.org/?probe=569faf34f1) | Jun 27, 2022 |
| Intel         | DH61WW AAG23116-302         | Desktop     | [7e1e1cf659](https://linux-hardware.org/?probe=7e1e1cf659) | Jun 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [3a651b23fb](https://linux-hardware.org/?probe=3a651b23fb) | Jun 26, 2022 |
| HP            | Laptop 15g-br1xx            | Notebook    | [aef95d312f](https://linux-hardware.org/?probe=aef95d312f) | Jun 26, 2022 |
| MSI           | GF63 Thin 9SCXR             | Notebook    | [db6195eed2](https://linux-hardware.org/?probe=db6195eed2) | Jun 26, 2022 |
| ASUSTek       | X510UNR                     | Notebook    | [d5f3803a24](https://linux-hardware.org/?probe=d5f3803a24) | Jun 26, 2022 |
| HP            | Pavilion 15                 | Notebook    | [929cd4988f](https://linux-hardware.org/?probe=929cd4988f) | Jun 26, 2022 |
| HP            | Pavilion g6                 | Notebook    | [d2e82f01d9](https://linux-hardware.org/?probe=d2e82f01d9) | Jun 25, 2022 |
| Lenovo        | G570 20079                  | Notebook    | [5ec853b08c](https://linux-hardware.org/?probe=5ec853b08c) | Jun 25, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a2f3ee6e42](https://linux-hardware.org/?probe=a2f3ee6e42) | Jun 24, 2022 |
| HP            | 8431                        | All in one  | [e8cbe50e2f](https://linux-hardware.org/?probe=e8cbe50e2f) | Jun 24, 2022 |
| HP            | 8431                        | All in one  | [1a65660840](https://linux-hardware.org/?probe=1a65660840) | Jun 24, 2022 |
| Dell          | Vostro 2420                 | Notebook    | [2d50f4b4d8](https://linux-hardware.org/?probe=2d50f4b4d8) | Jun 23, 2022 |
| Lenovo        | V330-14ARR 81B1             | Notebook    | [9816b1d616](https://linux-hardware.org/?probe=9816b1d616) | Jun 23, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [1b382e0eb0](https://linux-hardware.org/?probe=1b382e0eb0) | Jun 23, 2022 |
| Dell          | Inspiron 5459               | Notebook    | [d3a3e2cf32](https://linux-hardware.org/?probe=d3a3e2cf32) | Jun 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [d98df1e3c5](https://linux-hardware.org/?probe=d98df1e3c5) | Jun 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [8adbb8b56a](https://linux-hardware.org/?probe=8adbb8b56a) | Jun 22, 2022 |
| Lenovo        | ThinkPad T420 4177Q5U       | Notebook    | [cf27027c76](https://linux-hardware.org/?probe=cf27027c76) | Jun 22, 2022 |
| Acer          | H110H4-M14 P21-A2E          | Desktop     | [f3c553d3f0](https://linux-hardware.org/?probe=f3c553d3f0) | Jun 22, 2022 |
| Gigabyte      | H61M-S2P                    | Desktop     | [ac99674975](https://linux-hardware.org/?probe=ac99674975) | Jun 22, 2022 |
| Acer          | H110H4-M14 P21-A2E          | Desktop     | [17e46ecec3](https://linux-hardware.org/?probe=17e46ecec3) | Jun 22, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [f25ac785b7](https://linux-hardware.org/?probe=f25ac785b7) | Jun 22, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL Ub 2... | Notebook    | [93f08af289](https://linux-hardware.org/?probe=93f08af289) | Jun 21, 2022 |
| Gigabyte      | H410M S2 V3                 | Desktop     | [79ac3d3f38](https://linux-hardware.org/?probe=79ac3d3f38) | Jun 21, 2022 |
| Dell          | Vostro 2420                 | Notebook    | [84a4eb23c6](https://linux-hardware.org/?probe=84a4eb23c6) | Jun 21, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [6ce6e1d459](https://linux-hardware.org/?probe=6ce6e1d459) | Jun 20, 2022 |
| Dell          | Vostro 3490                 | Notebook    | [c203985c20](https://linux-hardware.org/?probe=c203985c20) | Jun 20, 2022 |
| Dell          | Vostro 3490                 | Notebook    | [e0968d0d2b](https://linux-hardware.org/?probe=e0968d0d2b) | Jun 20, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [d4aa7ef4a3](https://linux-hardware.org/?probe=d4aa7ef4a3) | Jun 20, 2022 |
| Dell          | Vostro 14-3468              | Notebook    | [1f0ee8f5fd](https://linux-hardware.org/?probe=1f0ee8f5fd) | Jun 20, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [90f4bec7db](https://linux-hardware.org/?probe=90f4bec7db) | Jun 19, 2022 |
| HP            | EliteBook 1050 G1           | Notebook    | [731ecfced1](https://linux-hardware.org/?probe=731ecfced1) | Jun 18, 2022 |
| Lenovo        | ThinkPad E490 20N8S01H00    | Notebook    | [7f96502192](https://linux-hardware.org/?probe=7f96502192) | Jun 18, 2022 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [31cdb7f2fc](https://linux-hardware.org/?probe=31cdb7f2fc) | Jun 17, 2022 |
| HP            | Unknown                     | Notebook    | [4c4cdf6526](https://linux-hardware.org/?probe=4c4cdf6526) | Jun 17, 2022 |
| Dell          | Latitude 5310               | Notebook    | [d34d939bae](https://linux-hardware.org/?probe=d34d939bae) | Jun 17, 2022 |
| Sony          | SVE15128CNB                 | Notebook    | [029a230c77](https://linux-hardware.org/?probe=029a230c77) | Jun 17, 2022 |
| Unknown       | G41 Series                  | Desktop     | [d257436f52](https://linux-hardware.org/?probe=d257436f52) | Jun 17, 2022 |
| Dell          | Latitude 3450               | Notebook    | [f0bff3d433](https://linux-hardware.org/?probe=f0bff3d433) | Jun 16, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [10304caa6b](https://linux-hardware.org/?probe=10304caa6b) | Jun 16, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [b136496151](https://linux-hardware.org/?probe=b136496151) | Jun 16, 2022 |
| ITI LIMITE... | SMAASH XU3i                 | Desktop     | [549a55efdf](https://linux-hardware.org/?probe=549a55efdf) | Jun 16, 2022 |
| ITI LIMITE... | SMAASH XU3i                 | Desktop     | [693d81e1a3](https://linux-hardware.org/?probe=693d81e1a3) | Jun 16, 2022 |
| ASUSTek       | ET2040I                     | Notebook    | [45273f0675](https://linux-hardware.org/?probe=45273f0675) | Jun 15, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [2b307211cd](https://linux-hardware.org/?probe=2b307211cd) | Jun 14, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [0ca08532ce](https://linux-hardware.org/?probe=0ca08532ce) | Jun 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | Notebook    | [b10e894950](https://linux-hardware.org/?probe=b10e894950) | Jun 14, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [002c21e90f](https://linux-hardware.org/?probe=002c21e90f) | Jun 14, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [dfa7cc38e7](https://linux-hardware.org/?probe=dfa7cc38e7) | Jun 14, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [0ac0a212e0](https://linux-hardware.org/?probe=0ac0a212e0) | Jun 13, 2022 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [7aaeea9280](https://linux-hardware.org/?probe=7aaeea9280) | Jun 13, 2022 |
| HP            | Laptop 15q-bu0xx            | Notebook    | [859d1ddbb0](https://linux-hardware.org/?probe=859d1ddbb0) | Jun 13, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [0d74445d24](https://linux-hardware.org/?probe=0d74445d24) | Jun 13, 2022 |
| BESSTAR Te... | ATB15                       | Server      | [d6e47a7c18](https://linux-hardware.org/?probe=d6e47a7c18) | Jun 12, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [9840a70112](https://linux-hardware.org/?probe=9840a70112) | Jun 11, 2022 |
| AVITA         | NE14A2                      | Notebook    | [3ac292714a](https://linux-hardware.org/?probe=3ac292714a) | Jun 10, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [ab0ad88b31](https://linux-hardware.org/?probe=ab0ad88b31) | Jun 10, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [d80ec10f91](https://linux-hardware.org/?probe=d80ec10f91) | Jun 09, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [39e10fd449](https://linux-hardware.org/?probe=39e10fd449) | Jun 09, 2022 |
| Dell          | 0XFWHV A00                  | Desktop     | [4102e98034](https://linux-hardware.org/?probe=4102e98034) | Jun 09, 2022 |
| Lenovo        | ThinkPad Edge E431 62771... | Notebook    | [ef8cc06070](https://linux-hardware.org/?probe=ef8cc06070) | Jun 09, 2022 |
| Lenovo        | ThinkPad E480 20KNS0E200    | Notebook    | [321a2df7db](https://linux-hardware.org/?probe=321a2df7db) | Jun 09, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [484996e8db](https://linux-hardware.org/?probe=484996e8db) | Jun 08, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [224023dfd2](https://linux-hardware.org/?probe=224023dfd2) | Jun 08, 2022 |
| Toshiba       | Satellite C50-A             | Notebook    | [1f5918622d](https://linux-hardware.org/?probe=1f5918622d) | Jun 08, 2022 |
| Biostar       | H61MLV3                     | Desktop     | [dd47d4aac6](https://linux-hardware.org/?probe=dd47d4aac6) | Jun 08, 2022 |
| Biostar       | H61MLV3                     | Desktop     | [906bb764d6](https://linux-hardware.org/?probe=906bb764d6) | Jun 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [b27a6ef652](https://linux-hardware.org/?probe=b27a6ef652) | Jun 08, 2022 |
| Toshiba       | Satellite C50-A             | Notebook    | [20a629adc2](https://linux-hardware.org/?probe=20a629adc2) | Jun 08, 2022 |
| Acer          | Swift SF313-53              | Notebook    | [68dff2bc8e](https://linux-hardware.org/?probe=68dff2bc8e) | Jun 08, 2022 |
| HP            | Laptop 15-da1xxx            | Notebook    | [0b67cbecfc](https://linux-hardware.org/?probe=0b67cbecfc) | Jun 07, 2022 |
| Lenovo        | IdeaPad S540-15IWL          | Notebook    | [1a79b3a2ab](https://linux-hardware.org/?probe=1a79b3a2ab) | Jun 07, 2022 |
| HP            | Laptop 15-da1xxx            | Notebook    | [02f5bd70bb](https://linux-hardware.org/?probe=02f5bd70bb) | Jun 07, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MG... | Notebook    | [f4c82e1fb6](https://linux-hardware.org/?probe=f4c82e1fb6) | Jun 07, 2022 |
| Dell          | Inspiron 3584               | Notebook    | [27ac9bc8f9](https://linux-hardware.org/?probe=27ac9bc8f9) | Jun 07, 2022 |
| Dell          | Inspiron 3584               | Notebook    | [7fdce576b4](https://linux-hardware.org/?probe=7fdce576b4) | Jun 07, 2022 |
| Flipkart I... | NKi510TL85S                 | Notebook    | [6e1326c27f](https://linux-hardware.org/?probe=6e1326c27f) | Jun 07, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [affa614c99](https://linux-hardware.org/?probe=affa614c99) | Jun 07, 2022 |
| Dell          | Latitude E6420              | Notebook    | [b2a364340d](https://linux-hardware.org/?probe=b2a364340d) | Jun 07, 2022 |
| Unknown       | X31_ICH7                    | Desktop     | [f8ab18b666](https://linux-hardware.org/?probe=f8ab18b666) | Jun 07, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [81fad50492](https://linux-hardware.org/?probe=81fad50492) | Jun 06, 2022 |
| Lenovo        | 81WE                        | Notebook    | [31217f3c4a](https://linux-hardware.org/?probe=31217f3c4a) | Jun 06, 2022 |
| Intel         | H61                         | Desktop     | [8178c4da07](https://linux-hardware.org/?probe=8178c4da07) | Jun 06, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [caa9a0cf2f](https://linux-hardware.org/?probe=caa9a0cf2f) | Jun 06, 2022 |
| HP            | 8648                        | Desktop     | [155bf69660](https://linux-hardware.org/?probe=155bf69660) | Jun 05, 2022 |
| Acer          | Aspire A715-75G             | Notebook    | [d8a8c3c8b4](https://linux-hardware.org/?probe=d8a8c3c8b4) | Jun 05, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [f1becc237d](https://linux-hardware.org/?probe=f1becc237d) | Jun 05, 2022 |
| Dell          | Latitude E6420              | Notebook    | [01eb3f0d4b](https://linux-hardware.org/?probe=01eb3f0d4b) | Jun 05, 2022 |
| Dell          | G3 3500                     | Notebook    | [6734206fa0](https://linux-hardware.org/?probe=6734206fa0) | Jun 05, 2022 |
| HP            | 15                          | Notebook    | [3e96827fe7](https://linux-hardware.org/?probe=3e96827fe7) | Jun 04, 2022 |
| Lenovo        | IdeaPad 530S-15IKB 81EV     | Notebook    | [41f0428c2b](https://linux-hardware.org/?probe=41f0428c2b) | Jun 04, 2022 |
| Dell          | Inspiron 3584               | Notebook    | [843797dc80](https://linux-hardware.org/?probe=843797dc80) | Jun 04, 2022 |
| HP            | 15                          | Notebook    | [b256b9e839](https://linux-hardware.org/?probe=b256b9e839) | Jun 04, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [66cc7342ec](https://linux-hardware.org/?probe=66cc7342ec) | Jun 04, 2022 |
| Lenovo        | ThinkPad T430 2349LTU       | Notebook    | [2c80cec3c3](https://linux-hardware.org/?probe=2c80cec3c3) | Jun 03, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [9533388943](https://linux-hardware.org/?probe=9533388943) | Jun 03, 2022 |
| Lenovo        | IdeaPad V15-ADA             | Notebook    | [94971f4968](https://linux-hardware.org/?probe=94971f4968) | Jun 03, 2022 |
| Dell          | Latitude 7390               | Notebook    | [0c7c9778aa](https://linux-hardware.org/?probe=0c7c9778aa) | Jun 02, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YFC... | Notebook    | [ac0d3882ca](https://linux-hardware.org/?probe=ac0d3882ca) | Jun 01, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [0f84f94a6a](https://linux-hardware.org/?probe=0f84f94a6a) | Jun 01, 2022 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [5b8924befc](https://linux-hardware.org/?probe=5b8924befc) | May 31, 2022 |
| MSI           | B450M GAMING PLUS           | Desktop     | [db537b41f4](https://linux-hardware.org/?probe=db537b41f4) | May 31, 2022 |
| Lenovo        | Erazer Y50-70               | Notebook    | [abb6af451d](https://linux-hardware.org/?probe=abb6af451d) | May 31, 2022 |
| Dell          | Inspiron 15 3511            | Notebook    | [3fbca187e7](https://linux-hardware.org/?probe=3fbca187e7) | May 31, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [2f14b6956f](https://linux-hardware.org/?probe=2f14b6956f) | May 31, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [871738fea2](https://linux-hardware.org/?probe=871738fea2) | May 31, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [f3a24fbc49](https://linux-hardware.org/?probe=f3a24fbc49) | May 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YFC... | Notebook    | [784e1ca4cc](https://linux-hardware.org/?probe=784e1ca4cc) | May 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [959728c7eb](https://linux-hardware.org/?probe=959728c7eb) | May 29, 2022 |
| HP            | Pavilion g6                 | Notebook    | [a82494e1f3](https://linux-hardware.org/?probe=a82494e1f3) | May 29, 2022 |
| Dell          | Vostro 3546                 | Notebook    | [3acd5d4cb0](https://linux-hardware.org/?probe=3acd5d4cb0) | May 28, 2022 |
| Lenovo        | CRESCENTBAY 31900059 STD... | All in one  | [d222b1e86e](https://linux-hardware.org/?probe=d222b1e86e) | May 28, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | Notebook    | [4c4689f4b7](https://linux-hardware.org/?probe=4c4689f4b7) | May 28, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [9d9d577f12](https://linux-hardware.org/?probe=9d9d577f12) | May 28, 2022 |
| Dell          | 0NKW6Y A00                  | Desktop     | [778ccadd42](https://linux-hardware.org/?probe=778ccadd42) | May 27, 2022 |
| Dell          | Latitude 5480               | Notebook    | [6056df9c22](https://linux-hardware.org/?probe=6056df9c22) | May 27, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [bf6cb72634](https://linux-hardware.org/?probe=bf6cb72634) | May 26, 2022 |
| Unknown       | G41 Series                  | Desktop     | [e9a273726a](https://linux-hardware.org/?probe=e9a273726a) | May 26, 2022 |
| Acer          | Aspire A515-46              | Notebook    | [e004aa3fd2](https://linux-hardware.org/?probe=e004aa3fd2) | May 25, 2022 |
| HP            | Notebook                    | Notebook    | [87460a83e8](https://linux-hardware.org/?probe=87460a83e8) | May 25, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [38ac6de56d](https://linux-hardware.org/?probe=38ac6de56d) | May 25, 2022 |
| Unknown       | G41 Series                  | Desktop     | [f0890bb556](https://linux-hardware.org/?probe=f0890bb556) | May 24, 2022 |
| INP           | i1000BTS                    | Desktop     | [95da2ada33](https://linux-hardware.org/?probe=95da2ada33) | May 24, 2022 |
| HP            | Laptop 15s-du2xxx           | Notebook    | [aeb154944d](https://linux-hardware.org/?probe=aeb154944d) | May 24, 2022 |
| HP            | Laptop 15s-du2xxx           | Notebook    | [bcccd55aab](https://linux-hardware.org/?probe=bcccd55aab) | May 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [8d8d5ff5e1](https://linux-hardware.org/?probe=8d8d5ff5e1) | May 24, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [bf692d5408](https://linux-hardware.org/?probe=bf692d5408) | May 23, 2022 |
| Dell          | Latitude 3450               | Notebook    | [f788f954ec](https://linux-hardware.org/?probe=f788f954ec) | May 23, 2022 |
| Dell          | Inspiron N4010              | Notebook    | [872649a8b4](https://linux-hardware.org/?probe=872649a8b4) | May 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [f2e32c336d](https://linux-hardware.org/?probe=f2e32c336d) | May 23, 2022 |
| Lenovo        | S20-30 20421                | Notebook    | [58d0509bff](https://linux-hardware.org/?probe=58d0509bff) | May 23, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [36a8a2a0ee](https://linux-hardware.org/?probe=36a8a2a0ee) | May 23, 2022 |
| Lenovo        | ThinkPad X270 20HMS1QT0E    | Notebook    | [f17079bdce](https://linux-hardware.org/?probe=f17079bdce) | May 22, 2022 |
| Acer          | Swift SF514-52T             | Notebook    | [d49880e4c2](https://linux-hardware.org/?probe=d49880e4c2) | May 22, 2022 |
| Acer          | Swift SF514-52T             | Notebook    | [40d5ca6bab](https://linux-hardware.org/?probe=40d5ca6bab) | May 22, 2022 |
| Acer          | Aspire A715-75G             | Notebook    | [10d158c79e](https://linux-hardware.org/?probe=10d158c79e) | May 22, 2022 |
| Acer          | Aspire A715-75G             | Notebook    | [4e1e3e6863](https://linux-hardware.org/?probe=4e1e3e6863) | May 22, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [afca2e1045](https://linux-hardware.org/?probe=afca2e1045) | May 22, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [914eca828e](https://linux-hardware.org/?probe=914eca828e) | May 22, 2022 |
| HP            | Pavilion g6                 | Notebook    | [3b904a10e3](https://linux-hardware.org/?probe=3b904a10e3) | May 21, 2022 |
| MSI           | B450M GAMING PLUS           | Desktop     | [99a1044b8a](https://linux-hardware.org/?probe=99a1044b8a) | May 21, 2022 |
| HP            | Pavilion g6                 | Notebook    | [e165a36a31](https://linux-hardware.org/?probe=e165a36a31) | May 21, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [f729776db3](https://linux-hardware.org/?probe=f729776db3) | May 21, 2022 |
| Acer          | Swift SF514-54T             | Notebook    | [29b06de977](https://linux-hardware.org/?probe=29b06de977) | May 21, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [01e2d063e8](https://linux-hardware.org/?probe=01e2d063e8) | May 21, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [f3986d7e7d](https://linux-hardware.org/?probe=f3986d7e7d) | May 21, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [d5e0667318](https://linux-hardware.org/?probe=d5e0667318) | May 20, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [efd1b236a1](https://linux-hardware.org/?probe=efd1b236a1) | May 20, 2022 |
| Alienware     | x17 R2                      | Notebook    | [019dbb46a4](https://linux-hardware.org/?probe=019dbb46a4) | May 20, 2022 |
| Unknown       | G41 Series                  | Desktop     | [94dcbec5e7](https://linux-hardware.org/?probe=94dcbec5e7) | May 20, 2022 |
| Toshiba       | Satellite U940              | Notebook    | [249374be01](https://linux-hardware.org/?probe=249374be01) | May 19, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [dba5104e21](https://linux-hardware.org/?probe=dba5104e21) | May 18, 2022 |
| HP            | EliteBook 745 G3            | Notebook    | [fac15b2640](https://linux-hardware.org/?probe=fac15b2640) | May 18, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [57610c67ba](https://linux-hardware.org/?probe=57610c67ba) | May 18, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [0a25740096](https://linux-hardware.org/?probe=0a25740096) | May 18, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [d831b6cb22](https://linux-hardware.org/?probe=d831b6cb22) | May 17, 2022 |
| Dell          | Inspiron 15 3511            | Notebook    | [0095bc3389](https://linux-hardware.org/?probe=0095bc3389) | May 16, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [2dac9974af](https://linux-hardware.org/?probe=2dac9974af) | May 16, 2022 |
| Dell          | Precision 3551              | Notebook    | [f134f92d00](https://linux-hardware.org/?probe=f134f92d00) | May 16, 2022 |
| HP            | Pavilion Laptop 13-an0xx... | Notebook    | [b4d7d75ad1](https://linux-hardware.org/?probe=b4d7d75ad1) | May 15, 2022 |
| Lenovo        | S20-30 20421                | Notebook    | [7436d81709](https://linux-hardware.org/?probe=7436d81709) | May 15, 2022 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [a2fa413622](https://linux-hardware.org/?probe=a2fa413622) | May 15, 2022 |
| MSI           | B350M MORTAR                | Desktop     | [459e7e3586](https://linux-hardware.org/?probe=459e7e3586) | May 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [a442279a0b](https://linux-hardware.org/?probe=a442279a0b) | May 15, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [88c0d2c252](https://linux-hardware.org/?probe=88c0d2c252) | May 15, 2022 |
| Sony          | VPCEA36FG                   | Notebook    | [0161a27629](https://linux-hardware.org/?probe=0161a27629) | May 13, 2022 |
| HP            | 15                          | Notebook    | [32a7709448](https://linux-hardware.org/?probe=32a7709448) | May 13, 2022 |
| Dell          | Vostro 3558                 | Notebook    | [2a1cf069bc](https://linux-hardware.org/?probe=2a1cf069bc) | May 13, 2022 |
| AVITA         | NS14A8                      | Notebook    | [bc86f7a17e](https://linux-hardware.org/?probe=bc86f7a17e) | May 13, 2022 |
| Dell          | Precision M2800             | Notebook    | [266af2c2b7](https://linux-hardware.org/?probe=266af2c2b7) | May 13, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [3eaf81c13c](https://linux-hardware.org/?probe=3eaf81c13c) | May 12, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [4d2b2c6a3c](https://linux-hardware.org/?probe=4d2b2c6a3c) | May 12, 2022 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [ed11a30da0](https://linux-hardware.org/?probe=ed11a30da0) | May 12, 2022 |
| Lenovo        | IdeaPad S540-15IWL          | Notebook    | [bbf4ef2a08](https://linux-hardware.org/?probe=bbf4ef2a08) | May 11, 2022 |
| Lenovo        | ThinkPad T440s 20AQ006HU... | Notebook    | [65fce47240](https://linux-hardware.org/?probe=65fce47240) | May 11, 2022 |
| Lenovo        | ThinkPad T590 20N5S2NC0N    | Notebook    | [61327f1e21](https://linux-hardware.org/?probe=61327f1e21) | May 11, 2022 |
| Dell          | G3 3579                     | Notebook    | [eff2c45d12](https://linux-hardware.org/?probe=eff2c45d12) | May 11, 2022 |
| Dell          | G15 5511                    | Notebook    | [17b75bcced](https://linux-hardware.org/?probe=17b75bcced) | May 10, 2022 |
| HP            | 15                          | Notebook    | [fdef27b310](https://linux-hardware.org/?probe=fdef27b310) | May 10, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [34272a60d1](https://linux-hardware.org/?probe=34272a60d1) | May 10, 2022 |
| HP            | 2000                        | Notebook    | [d0e74bfff6](https://linux-hardware.org/?probe=d0e74bfff6) | May 10, 2022 |
| HP            | Notebook                    | Notebook    | [afe98a811e](https://linux-hardware.org/?probe=afe98a811e) | May 10, 2022 |
| HP            | Pavilion dv6                | Notebook    | [165c15d078](https://linux-hardware.org/?probe=165c15d078) | May 09, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [911b8e4c5b](https://linux-hardware.org/?probe=911b8e4c5b) | May 09, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [8e43525285](https://linux-hardware.org/?probe=8e43525285) | May 09, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [3227adfd1a](https://linux-hardware.org/?probe=3227adfd1a) | May 07, 2022 |
| Lenovo        | ThinkPad T440 20B7S1QX01    | Notebook    | [68fbf0cacb](https://linux-hardware.org/?probe=68fbf0cacb) | May 07, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T2S... | Notebook    | [70fe076856](https://linux-hardware.org/?probe=70fe076856) | May 06, 2022 |
| Google        | Lick                        | Notebook    | [60e52e55e1](https://linux-hardware.org/?probe=60e52e55e1) | May 06, 2022 |
| Lenovo        | ThinkPad L13 20R3S10R00     | Notebook    | [b173909e06](https://linux-hardware.org/?probe=b173909e06) | May 06, 2022 |
| HP            | Notebook                    | Notebook    | [05f1b18534](https://linux-hardware.org/?probe=05f1b18534) | May 04, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [db81dd7652](https://linux-hardware.org/?probe=db81dd7652) | May 04, 2022 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [156de9d4de](https://linux-hardware.org/?probe=156de9d4de) | May 04, 2022 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [aa14a3b075](https://linux-hardware.org/?probe=aa14a3b075) | May 04, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [8bfd6ecc71](https://linux-hardware.org/?probe=8bfd6ecc71) | May 04, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [bf9f724f45](https://linux-hardware.org/?probe=bf9f724f45) | May 04, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [05585fedf4](https://linux-hardware.org/?probe=05585fedf4) | May 04, 2022 |
| HP            | Pavilion Laptop 15-cs1xx... | Notebook    | [ca91daf662](https://linux-hardware.org/?probe=ca91daf662) | May 04, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [329673fcbf](https://linux-hardware.org/?probe=329673fcbf) | May 03, 2022 |
| ASUSTek       | ROG Strix G713RC_G713RC     | Notebook    | [2ce25fb058](https://linux-hardware.org/?probe=2ce25fb058) | May 03, 2022 |
| Lenovo        | 3724                        | All in one  | [fa47d5fd48](https://linux-hardware.org/?probe=fa47d5fd48) | May 03, 2022 |
| HP            | Laptop 15-bs1xx             | Notebook    | [aa3fb50ed5](https://linux-hardware.org/?probe=aa3fb50ed5) | May 03, 2022 |
| Toshiba       | Satellite U940              | Notebook    | [3d6bd2511e](https://linux-hardware.org/?probe=3d6bd2511e) | May 03, 2022 |
| HP            | Presario CQ42               | Notebook    | [93ac0fd52a](https://linux-hardware.org/?probe=93ac0fd52a) | May 02, 2022 |
| Maxtone       | HIS-G41L V1.1               | Desktop     | [ce61ffd777](https://linux-hardware.org/?probe=ce61ffd777) | May 02, 2022 |
| MSI           | GP76 Leopard 11UG           | Notebook    | [dcea7cd8c0](https://linux-hardware.org/?probe=dcea7cd8c0) | May 02, 2022 |
| Maxtone       | HIS-G41L V1.1               | Desktop     | [63fc1199bc](https://linux-hardware.org/?probe=63fc1199bc) | May 01, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [0eb277ff80](https://linux-hardware.org/?probe=0eb277ff80) | May 01, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [549ca9da46](https://linux-hardware.org/?probe=549ca9da46) | May 01, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [ec3ccc4967](https://linux-hardware.org/?probe=ec3ccc4967) | May 01, 2022 |
| Dell          | Latitude 3490               | Notebook    | [ff6e81ce15](https://linux-hardware.org/?probe=ff6e81ce15) | May 01, 2022 |
| Acer          | Aspire A715-75G             | Notebook    | [50d37d9cf7](https://linux-hardware.org/?probe=50d37d9cf7) | May 01, 2022 |
| Acer          | Swift SF314-55G             | Notebook    | [1935c949a2](https://linux-hardware.org/?probe=1935c949a2) | May 01, 2022 |
| Dell          | Inspiron 7559               | Notebook    | [37b324ecf9](https://linux-hardware.org/?probe=37b324ecf9) | May 01, 2022 |
| Dell          | G3 3500                     | Notebook    | [df72f36c52](https://linux-hardware.org/?probe=df72f36c52) | Apr 30, 2022 |
| Google        | Lick                        | Notebook    | [33d1e6209a](https://linux-hardware.org/?probe=33d1e6209a) | Apr 30, 2022 |
| Dell          | G3 3500                     | Notebook    | [c9ee387b32](https://linux-hardware.org/?probe=c9ee387b32) | Apr 30, 2022 |
| eMachines     | eME730                      | Notebook    | [ac985950eb](https://linux-hardware.org/?probe=ac985950eb) | Apr 30, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [809ea3e76a](https://linux-hardware.org/?probe=809ea3e76a) | Apr 29, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [19f5e16bce](https://linux-hardware.org/?probe=19f5e16bce) | Apr 29, 2022 |
| Lenovo        | ThinkPad T450 20BUS1MN00    | Notebook    | [4e2b073a5c](https://linux-hardware.org/?probe=4e2b073a5c) | Apr 29, 2022 |
| Dell          | G5 5500                     | Notebook    | [c6064853ad](https://linux-hardware.org/?probe=c6064853ad) | Apr 29, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [1f6bbce46b](https://linux-hardware.org/?probe=1f6bbce46b) | Apr 28, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [6e00a18a0f](https://linux-hardware.org/?probe=6e00a18a0f) | Apr 28, 2022 |
| Gigabyte      | H310M H                     | Desktop     | [182e82d90e](https://linux-hardware.org/?probe=182e82d90e) | Apr 28, 2022 |
| HP            | Stream Laptop 14-ds0xxx     | Notebook    | [59a8e467c6](https://linux-hardware.org/?probe=59a8e467c6) | Apr 28, 2022 |
| Lenovo        | V14 G2 ITL Ua 82KA          | Notebook    | [f191c49754](https://linux-hardware.org/?probe=f191c49754) | Apr 28, 2022 |
| HP            | Notebook                    | Notebook    | [daaa31b65a](https://linux-hardware.org/?probe=daaa31b65a) | Apr 27, 2022 |
| HP            | Notebook                    | Notebook    | [cbac71290e](https://linux-hardware.org/?probe=cbac71290e) | Apr 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [a696a35961](https://linux-hardware.org/?probe=a696a35961) | Apr 27, 2022 |
| HP            | Notebook                    | Notebook    | [ec93418371](https://linux-hardware.org/?probe=ec93418371) | Apr 26, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [f0ed67e309](https://linux-hardware.org/?probe=f0ed67e309) | Apr 26, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [ea3e0b8695](https://linux-hardware.org/?probe=ea3e0b8695) | Apr 26, 2022 |
| Biostar       | J3160NH                     | Desktop     | [8ffd3a1aa4](https://linux-hardware.org/?probe=8ffd3a1aa4) | Apr 26, 2022 |
| MSI           | Z68A-GD80                   | Desktop     | [fedca9082a](https://linux-hardware.org/?probe=fedca9082a) | Apr 25, 2022 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [8197ac9c77](https://linux-hardware.org/?probe=8197ac9c77) | Apr 25, 2022 |
| HP            | 348 G4                      | Notebook    | [54db7eb2da](https://linux-hardware.org/?probe=54db7eb2da) | Apr 25, 2022 |
| ASUSTek       | X555LF                      | Notebook    | [0aa3a88c0c](https://linux-hardware.org/?probe=0aa3a88c0c) | Apr 25, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [b4577b2374](https://linux-hardware.org/?probe=b4577b2374) | Apr 25, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [99bd45c11d](https://linux-hardware.org/?probe=99bd45c11d) | Apr 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | Notebook    | [a260bf9ce6](https://linux-hardware.org/?probe=a260bf9ce6) | Apr 24, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [45b9330abf](https://linux-hardware.org/?probe=45b9330abf) | Apr 23, 2022 |
| Nvidia        | Tegra                       | Soc         | [36bbd53ec1](https://linux-hardware.org/?probe=36bbd53ec1) | Apr 23, 2022 |
| Lenovo        | E41-25 81FS                 | Notebook    | [4880f7c2d5](https://linux-hardware.org/?probe=4880f7c2d5) | Apr 22, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [6d50395aee](https://linux-hardware.org/?probe=6d50395aee) | Apr 22, 2022 |
| Intel         | DH61SA AAG38870-201         | Desktop     | [d8868878ca](https://linux-hardware.org/?probe=d8868878ca) | Apr 22, 2022 |
| Toshiba       | Satellite C850-A786         | Notebook    | [e57aca482e](https://linux-hardware.org/?probe=e57aca482e) | Apr 22, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [939f87564f](https://linux-hardware.org/?probe=939f87564f) | Apr 21, 2022 |
| Unknown       | G41 Series                  | Desktop     | [c6040e6638](https://linux-hardware.org/?probe=c6040e6638) | Apr 21, 2022 |
| HP            | Laptop 15s-du2xxx           | Notebook    | [fe39cbe3d1](https://linux-hardware.org/?probe=fe39cbe3d1) | Apr 20, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [88764ed497](https://linux-hardware.org/?probe=88764ed497) | Apr 20, 2022 |
| Toshiba       | Satellite L50-C             | Notebook    | [9e2b287533](https://linux-hardware.org/?probe=9e2b287533) | Apr 20, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [6ddb878f3e](https://linux-hardware.org/?probe=6ddb878f3e) | Apr 20, 2022 |
| HP            | Notebook                    | Notebook    | [bec9c06e6e](https://linux-hardware.org/?probe=bec9c06e6e) | Apr 20, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [53199db8c8](https://linux-hardware.org/?probe=53199db8c8) | Apr 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [f3d940677f](https://linux-hardware.org/?probe=f3d940677f) | Apr 19, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [4ec65c693a](https://linux-hardware.org/?probe=4ec65c693a) | Apr 19, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [7d16b45ebd](https://linux-hardware.org/?probe=7d16b45ebd) | Apr 18, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [6247b19a2f](https://linux-hardware.org/?probe=6247b19a2f) | Apr 18, 2022 |
| Dell          | Latitude E5520              | Notebook    | [1b428165cf](https://linux-hardware.org/?probe=1b428165cf) | Apr 18, 2022 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [b895187681](https://linux-hardware.org/?probe=b895187681) | Apr 17, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [66ef9c9e5f](https://linux-hardware.org/?probe=66ef9c9e5f) | Apr 16, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [ca0b0f6a8a](https://linux-hardware.org/?probe=ca0b0f6a8a) | Apr 16, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [8350598ef6](https://linux-hardware.org/?probe=8350598ef6) | Apr 15, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [cffdde259f](https://linux-hardware.org/?probe=cffdde259f) | Apr 15, 2022 |
| Timi          | Mi NoteBook 14              | Notebook    | [88abcd9e70](https://linux-hardware.org/?probe=88abcd9e70) | Apr 14, 2022 |
| Gigabyte      | H61MS                       | Desktop     | [84e8094305](https://linux-hardware.org/?probe=84e8094305) | Apr 14, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [ef76ce862d](https://linux-hardware.org/?probe=ef76ce862d) | Apr 14, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | Notebook    | [5f85d41ef2](https://linux-hardware.org/?probe=5f85d41ef2) | Apr 14, 2022 |
| ECS           | H81H3-I                     | Desktop     | [1bf6cc284c](https://linux-hardware.org/?probe=1bf6cc284c) | Apr 13, 2022 |
| Dynabook      | TECRA X40-F                 | Notebook    | [6d6f37f70e](https://linux-hardware.org/?probe=6d6f37f70e) | Apr 13, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [efc9013314](https://linux-hardware.org/?probe=efc9013314) | Apr 13, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [d06a50d75c](https://linux-hardware.org/?probe=d06a50d75c) | Apr 13, 2022 |
| Lenovo        | V14 G2 ITL Ua 82KA          | Notebook    | [b680349236](https://linux-hardware.org/?probe=b680349236) | Apr 12, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [64b8dd4120](https://linux-hardware.org/?probe=64b8dd4120) | Apr 12, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c7a9564044](https://linux-hardware.org/?probe=c7a9564044) | Apr 12, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [eccb5e26fc](https://linux-hardware.org/?probe=eccb5e26fc) | Apr 12, 2022 |
| Lenovo        | E41-25 81FS                 | Notebook    | [8d0dfa3de3](https://linux-hardware.org/?probe=8d0dfa3de3) | Apr 12, 2022 |
| HP            | Notebook                    | Notebook    | [de9a13770b](https://linux-hardware.org/?probe=de9a13770b) | Apr 11, 2022 |
| Toshiba       | Satellite C50D-A0386        | Notebook    | [31b131cc55](https://linux-hardware.org/?probe=31b131cc55) | Apr 11, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [4e0bcf3318](https://linux-hardware.org/?probe=4e0bcf3318) | Apr 11, 2022 |
| HP            | Laptop 15s-gr0xxx           | Notebook    | [36e02535fb](https://linux-hardware.org/?probe=36e02535fb) | Apr 11, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [6feb6018af](https://linux-hardware.org/?probe=6feb6018af) | Apr 10, 2022 |
| HP            | 246                         | Notebook    | [4ef673dd00](https://linux-hardware.org/?probe=4ef673dd00) | Apr 10, 2022 |
| Acer          | One 14 Z2-485               | Notebook    | [57f307fa80](https://linux-hardware.org/?probe=57f307fa80) | Apr 09, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [f76d101440](https://linux-hardware.org/?probe=f76d101440) | Apr 09, 2022 |
| Intel         | DH61SA AAG38870-201         | Desktop     | [516d1a3e43](https://linux-hardware.org/?probe=516d1a3e43) | Apr 08, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [7ec2454548](https://linux-hardware.org/?probe=7ec2454548) | Apr 08, 2022 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [a8c92b8a4c](https://linux-hardware.org/?probe=a8c92b8a4c) | Apr 08, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [21bef916af](https://linux-hardware.org/?probe=21bef916af) | Apr 08, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [94a611644c](https://linux-hardware.org/?probe=94a611644c) | Apr 07, 2022 |
| Gigabyte      | H310M H                     | Desktop     | [e392bf72e9](https://linux-hardware.org/?probe=e392bf72e9) | Apr 07, 2022 |
| Lenovo        | G560 20042                  | Notebook    | [945def6907](https://linux-hardware.org/?probe=945def6907) | Apr 07, 2022 |
| Lenovo        | MAHOBAY                     | All in one  | [787307fc39](https://linux-hardware.org/?probe=787307fc39) | Apr 07, 2022 |
| HP            | Laptop 14q-cy0xxx           | Notebook    | [625bad986e](https://linux-hardware.org/?probe=625bad986e) | Apr 07, 2022 |
| ASUSTek       | X542UQR                     | Notebook    | [57c9a10617](https://linux-hardware.org/?probe=57c9a10617) | Apr 07, 2022 |
| ASUSTek       | X542UQR                     | Notebook    | [15c5f13718](https://linux-hardware.org/?probe=15c5f13718) | Apr 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c5c24ea4c2](https://linux-hardware.org/?probe=c5c24ea4c2) | Apr 06, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [5b5118db5d](https://linux-hardware.org/?probe=5b5118db5d) | Apr 06, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [96b467ce52](https://linux-hardware.org/?probe=96b467ce52) | Apr 05, 2022 |
| Dell          | Vostro 3578                 | Notebook    | [8e2637c774](https://linux-hardware.org/?probe=8e2637c774) | Apr 05, 2022 |
| ASUSTek       | X550LC                      | Notebook    | [bc017137e8](https://linux-hardware.org/?probe=bc017137e8) | Apr 04, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [1d3cd04256](https://linux-hardware.org/?probe=1d3cd04256) | Apr 04, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [bd5be9b918](https://linux-hardware.org/?probe=bd5be9b918) | Apr 04, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [3e8d03d8d6](https://linux-hardware.org/?probe=3e8d03d8d6) | Apr 03, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [982bcd3a5b](https://linux-hardware.org/?probe=982bcd3a5b) | Apr 03, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [ba24b37041](https://linux-hardware.org/?probe=ba24b37041) | Apr 03, 2022 |
| Lenovo        | Erazer Y50-70               | Notebook    | [36d3d65801](https://linux-hardware.org/?probe=36d3d65801) | Apr 03, 2022 |
| HP            | Laptop 15s-dr1xxx           | Notebook    | [86ca12c772](https://linux-hardware.org/?probe=86ca12c772) | Apr 03, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [57a0d73ab9](https://linux-hardware.org/?probe=57a0d73ab9) | Apr 02, 2022 |
| HP            | Notebook                    | Notebook    | [f46a05a044](https://linux-hardware.org/?probe=f46a05a044) | Apr 02, 2022 |
| MSI           | GF63 Thin 9SCXR             | Notebook    | [3bc3694efb](https://linux-hardware.org/?probe=3bc3694efb) | Apr 02, 2022 |
| HP            | Pavilion Laptop 14-ce2xx... | Notebook    | [d103b2cb25](https://linux-hardware.org/?probe=d103b2cb25) | Apr 02, 2022 |
| Dell          | Inspiron 7386               | Convertible | [0052645485](https://linux-hardware.org/?probe=0052645485) | Apr 02, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [63f818dc19](https://linux-hardware.org/?probe=63f818dc19) | Apr 02, 2022 |
| Intel         | H61                         | Desktop     | [47b28b972b](https://linux-hardware.org/?probe=47b28b972b) | Apr 01, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [a1fc5c114a](https://linux-hardware.org/?probe=a1fc5c114a) | Apr 01, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [d2e5eda16f](https://linux-hardware.org/?probe=d2e5eda16f) | Apr 01, 2022 |
| Dell          | Inspiron 14 5410            | Notebook    | [3acec795a6](https://linux-hardware.org/?probe=3acec795a6) | Apr 01, 2022 |
| Dell          | G5 5500                     | Notebook    | [56b5d0d490](https://linux-hardware.org/?probe=56b5d0d490) | Apr 01, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [87dfbaa9e8](https://linux-hardware.org/?probe=87dfbaa9e8) | Apr 01, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [36563f3934](https://linux-hardware.org/?probe=36563f3934) | Apr 01, 2022 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [a4d2271eaa](https://linux-hardware.org/?probe=a4d2271eaa) | Mar 31, 2022 |
| MSI           | B450M GAMING PLUS           | Desktop     | [bd60416a2f](https://linux-hardware.org/?probe=bd60416a2f) | Mar 31, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [946628cb20](https://linux-hardware.org/?probe=946628cb20) | Mar 30, 2022 |
| Lenovo        | Legion 5 15ITH6 82JK        | Notebook    | [85f1411d0e](https://linux-hardware.org/?probe=85f1411d0e) | Mar 30, 2022 |
| Lenovo        | Legion 5 15ITH6 82JK        | Notebook    | [f8edce28d5](https://linux-hardware.org/?probe=f8edce28d5) | Mar 30, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [513f01a83f](https://linux-hardware.org/?probe=513f01a83f) | Mar 30, 2022 |
| Dell          | 0Y2YM6 A01                  | Desktop     | [4578be5a1e](https://linux-hardware.org/?probe=4578be5a1e) | Mar 30, 2022 |
| Dell          | Latitude E6420              | Notebook    | [411b1a3a51](https://linux-hardware.org/?probe=411b1a3a51) | Mar 30, 2022 |
| HP            | Laptop 15-da1xxx            | Notebook    | [fcbd3df931](https://linux-hardware.org/?probe=fcbd3df931) | Mar 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [58c7c253ca](https://linux-hardware.org/?probe=58c7c253ca) | Mar 28, 2022 |
| Dell          | Studio 1450                 | Notebook    | [1b7df0163d](https://linux-hardware.org/?probe=1b7df0163d) | Mar 28, 2022 |
| HP            | Pavilion dv3                | Notebook    | [bd8d09108e](https://linux-hardware.org/?probe=bd8d09108e) | Mar 28, 2022 |
| HP            | 18E7                        | Desktop     | [5dc3eea8b5](https://linux-hardware.org/?probe=5dc3eea8b5) | Mar 28, 2022 |
| Unknown       | G41 Series                  | Desktop     | [4dbde5e06f](https://linux-hardware.org/?probe=4dbde5e06f) | Mar 28, 2022 |
| HP            | Pavilion g4                 | Notebook    | [893eaf3bca](https://linux-hardware.org/?probe=893eaf3bca) | Mar 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d5e927b59e](https://linux-hardware.org/?probe=d5e927b59e) | Mar 26, 2022 |
| HP            | 18E7                        | Desktop     | [d8d1c3d468](https://linux-hardware.org/?probe=d8d1c3d468) | Mar 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [2465ab5a58](https://linux-hardware.org/?probe=2465ab5a58) | Mar 26, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e09438b057](https://linux-hardware.org/?probe=e09438b057) | Mar 26, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [11abcc854d](https://linux-hardware.org/?probe=11abcc854d) | Mar 25, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [870e407665](https://linux-hardware.org/?probe=870e407665) | Mar 25, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [4ba4683a05](https://linux-hardware.org/?probe=4ba4683a05) | Mar 24, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [f06216a521](https://linux-hardware.org/?probe=f06216a521) | Mar 24, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [8533e3cf0d](https://linux-hardware.org/?probe=8533e3cf0d) | Mar 23, 2022 |
| Lenovo        | ThinkPad L490 20Q5S0M600    | Notebook    | [1f816ed931](https://linux-hardware.org/?probe=1f816ed931) | Mar 23, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [a6718f483b](https://linux-hardware.org/?probe=a6718f483b) | Mar 22, 2022 |
| Acer          | Swift SF314-52              | Notebook    | [2d8ab46eed](https://linux-hardware.org/?probe=2d8ab46eed) | Mar 21, 2022 |
| Acer          | Swift SF314-52              | Notebook    | [b1bdc8c7d4](https://linux-hardware.org/?probe=b1bdc8c7d4) | Mar 21, 2022 |
| Lenovo        | ThinkPad X230 23251Q0       | Notebook    | [0a705ba05c](https://linux-hardware.org/?probe=0a705ba05c) | Mar 21, 2022 |
| Dell          | Latitude 3400               | Notebook    | [031b95db58](https://linux-hardware.org/?probe=031b95db58) | Mar 20, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [0e4992c717](https://linux-hardware.org/?probe=0e4992c717) | Mar 20, 2022 |
| HP            | Pavilion 14                 | Notebook    | [537e877606](https://linux-hardware.org/?probe=537e877606) | Mar 20, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [66de21a937](https://linux-hardware.org/?probe=66de21a937) | Mar 19, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [01bd3bd062](https://linux-hardware.org/?probe=01bd3bd062) | Mar 19, 2022 |
| HP            | Pavilion dv3                | Notebook    | [3dbd970796](https://linux-hardware.org/?probe=3dbd970796) | Mar 19, 2022 |
| Lenovo        | G505s 20255                 | Notebook    | [2b30c1219e](https://linux-hardware.org/?probe=2b30c1219e) | Mar 18, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [221de9592b](https://linux-hardware.org/?probe=221de9592b) | Mar 16, 2022 |
| Dell          | Latitude E7450              | Notebook    | [107065a152](https://linux-hardware.org/?probe=107065a152) | Mar 15, 2022 |
| ASUSTek       | VivoBook S14 X430UA         | Notebook    | [9a04e16d4a](https://linux-hardware.org/?probe=9a04e16d4a) | Mar 15, 2022 |
| Lenovo        | Erazer Y50-70               | Notebook    | [ae9a6ee7cb](https://linux-hardware.org/?probe=ae9a6ee7cb) | Mar 14, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [71dc914b7b](https://linux-hardware.org/?probe=71dc914b7b) | Mar 14, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [3af6b6632d](https://linux-hardware.org/?probe=3af6b6632d) | Mar 14, 2022 |
| Dell          | G5 5500                     | Notebook    | [12a4380cad](https://linux-hardware.org/?probe=12a4380cad) | Mar 14, 2022 |
| Intel         | G31                         | Desktop     | [02eaa5ef51](https://linux-hardware.org/?probe=02eaa5ef51) | Mar 14, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [89d17b56d6](https://linux-hardware.org/?probe=89d17b56d6) | Mar 14, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [737a2d4c61](https://linux-hardware.org/?probe=737a2d4c61) | Mar 14, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [8f4386fdc5](https://linux-hardware.org/?probe=8f4386fdc5) | Mar 14, 2022 |
| Intel         | DH61WW AAG23116-302         | Desktop     | [20682db2fa](https://linux-hardware.org/?probe=20682db2fa) | Mar 14, 2022 |
| Gigabyte      | H310M H x.x                 | Desktop     | [0a16c273a4](https://linux-hardware.org/?probe=0a16c273a4) | Mar 13, 2022 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [218c306874](https://linux-hardware.org/?probe=218c306874) | Mar 13, 2022 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [f7fe5893d5](https://linux-hardware.org/?probe=f7fe5893d5) | Mar 13, 2022 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | Notebook    | [11bd4e97e6](https://linux-hardware.org/?probe=11bd4e97e6) | Mar 13, 2022 |
| Intel         | H61                         | Desktop     | [8efa81cf12](https://linux-hardware.org/?probe=8efa81cf12) | Mar 12, 2022 |
| ASRock        | H61M-S1 PLUS                | Desktop     | [56c15fcbf6](https://linux-hardware.org/?probe=56c15fcbf6) | Mar 12, 2022 |
| Alienware     | 13 R3                       | Notebook    | [a8b07f9c17](https://linux-hardware.org/?probe=a8b07f9c17) | Mar 12, 2022 |
| Dell          | Latitude E5410              | Notebook    | [8015e22264](https://linux-hardware.org/?probe=8015e22264) | Mar 12, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [cb2918a35e](https://linux-hardware.org/?probe=cb2918a35e) | Mar 12, 2022 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | Desktop     | [508f6f6c0c](https://linux-hardware.org/?probe=508f6f6c0c) | Mar 11, 2022 |
| IBM           | 4367 SVT                    | Server      | [3d7400ea9b](https://linux-hardware.org/?probe=3d7400ea9b) | Mar 11, 2022 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | Desktop     | [59405132c9](https://linux-hardware.org/?probe=59405132c9) | Mar 11, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [41088e9fa5](https://linux-hardware.org/?probe=41088e9fa5) | Mar 11, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [2669052d03](https://linux-hardware.org/?probe=2669052d03) | Mar 11, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [04495b10d4](https://linux-hardware.org/?probe=04495b10d4) | Mar 11, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [e8d1f7870b](https://linux-hardware.org/?probe=e8d1f7870b) | Mar 11, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [cd44006f68](https://linux-hardware.org/?probe=cd44006f68) | Mar 11, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [a0206ab2c4](https://linux-hardware.org/?probe=a0206ab2c4) | Mar 11, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [2d8b8572f9](https://linux-hardware.org/?probe=2d8b8572f9) | Mar 11, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [77f1ffb185](https://linux-hardware.org/?probe=77f1ffb185) | Mar 11, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [03e601d730](https://linux-hardware.org/?probe=03e601d730) | Mar 11, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [fae4aba20f](https://linux-hardware.org/?probe=fae4aba20f) | Mar 11, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [19106d39f2](https://linux-hardware.org/?probe=19106d39f2) | Mar 11, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [953465453c](https://linux-hardware.org/?probe=953465453c) | Mar 11, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [d2bb880660](https://linux-hardware.org/?probe=d2bb880660) | Mar 11, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [da0ed74962](https://linux-hardware.org/?probe=da0ed74962) | Mar 11, 2022 |
| Dell          | Latitude 7480               | Notebook    | [cbff798f89](https://linux-hardware.org/?probe=cbff798f89) | Mar 11, 2022 |
| Dell          | Latitude 7480               | Notebook    | [02e748e3ac](https://linux-hardware.org/?probe=02e748e3ac) | Mar 11, 2022 |
| Dell          | Inspiron 5409               | Notebook    | [e99c4341ca](https://linux-hardware.org/?probe=e99c4341ca) | Mar 11, 2022 |
| Dell          | Inspiron 5409               | Notebook    | [777b585f05](https://linux-hardware.org/?probe=777b585f05) | Mar 11, 2022 |
| Dell          | Latitude 3410               | Notebook    | [49491fb71a](https://linux-hardware.org/?probe=49491fb71a) | Mar 11, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [145e63a7a5](https://linux-hardware.org/?probe=145e63a7a5) | Mar 09, 2022 |
| Dell          | 0HMX8D A01                  | Desktop     | [cfff92df80](https://linux-hardware.org/?probe=cfff92df80) | Mar 09, 2022 |
| Dell          | Inspiron 3793               | Notebook    | [1fb19c1b23](https://linux-hardware.org/?probe=1fb19c1b23) | Mar 09, 2022 |
| Micromax      | Canvas Laptab LT777         | Notebook    | [7ff8a61256](https://linux-hardware.org/?probe=7ff8a61256) | Mar 08, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [ea074742d5](https://linux-hardware.org/?probe=ea074742d5) | Mar 08, 2022 |
| Acer          | Aspire 4752                 | Notebook    | [291341394c](https://linux-hardware.org/?probe=291341394c) | Mar 07, 2022 |
| Gigabyte      | H310M H                     | Desktop     | [bd17b4c7fd](https://linux-hardware.org/?probe=bd17b4c7fd) | Mar 07, 2022 |
| ASRock        | H310M-HDV                   | Desktop     | [5be286e220](https://linux-hardware.org/?probe=5be286e220) | Mar 07, 2022 |
| Dell          | Latitude E6540              | Notebook    | [97de37d664](https://linux-hardware.org/?probe=97de37d664) | Mar 06, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [69b7c755dc](https://linux-hardware.org/?probe=69b7c755dc) | Mar 05, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U1S... | Notebook    | [61ebab5e1f](https://linux-hardware.org/?probe=61ebab5e1f) | Mar 04, 2022 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [479a3a52de](https://linux-hardware.org/?probe=479a3a52de) | Mar 03, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U1S... | Notebook    | [ae88c42f40](https://linux-hardware.org/?probe=ae88c42f40) | Mar 03, 2022 |
| Intel         | DG41CN AAE82429-102         | Desktop     | [0e75969d4d](https://linux-hardware.org/?probe=0e75969d4d) | Mar 03, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [c5bf02a4d7](https://linux-hardware.org/?probe=c5bf02a4d7) | Mar 03, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82C5     | Notebook    | [d4b6e7276e](https://linux-hardware.org/?probe=d4b6e7276e) | Mar 03, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [ee905a56c9](https://linux-hardware.org/?probe=ee905a56c9) | Mar 02, 2022 |
| Intel         | DG41CN AAE82429-102         | Desktop     | [a4145828e3](https://linux-hardware.org/?probe=a4145828e3) | Mar 02, 2022 |
| Lenovo        | E41-25 81FS                 | Notebook    | [f7cf64afde](https://linux-hardware.org/?probe=f7cf64afde) | Mar 02, 2022 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [f61c04b0a8](https://linux-hardware.org/?probe=f61c04b0a8) | Mar 01, 2022 |
| Dell          | Latitude 5289               | Convertible | [937ae2db89](https://linux-hardware.org/?probe=937ae2db89) | Feb 28, 2022 |
| HP            | Notebook                    | Notebook    | [24f32b44ea](https://linux-hardware.org/?probe=24f32b44ea) | Feb 28, 2022 |
| Lenovo        | ThinkPad X230 2330A17       | Notebook    | [ed014e00c8](https://linux-hardware.org/?probe=ed014e00c8) | Feb 27, 2022 |
| HP            | Presario CQ42               | Notebook    | [de34294599](https://linux-hardware.org/?probe=de34294599) | Feb 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [d7b815d3d6](https://linux-hardware.org/?probe=d7b815d3d6) | Feb 27, 2022 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [feb1d977ea](https://linux-hardware.org/?probe=feb1d977ea) | Feb 26, 2022 |
| Lenovo        | B40-70 20392                | Notebook    | [ab691617d6](https://linux-hardware.org/?probe=ab691617d6) | Feb 26, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [36e7b3c4aa](https://linux-hardware.org/?probe=36e7b3c4aa) | Feb 26, 2022 |
| HP            | Pavilion 15                 | Notebook    | [463d26d75c](https://linux-hardware.org/?probe=463d26d75c) | Feb 26, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [ea12d27cf9](https://linux-hardware.org/?probe=ea12d27cf9) | Feb 26, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [ab78767b82](https://linux-hardware.org/?probe=ab78767b82) | Feb 26, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b3e65653c6](https://linux-hardware.org/?probe=b3e65653c6) | Feb 25, 2022 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [b1fe013c4c](https://linux-hardware.org/?probe=b1fe013c4c) | Feb 25, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [b3086480e5](https://linux-hardware.org/?probe=b3086480e5) | Feb 25, 2022 |
| Dell          | 0GXM1W A02                  | Desktop     | [044a00e086](https://linux-hardware.org/?probe=044a00e086) | Feb 25, 2022 |
| Gigabyte      | H510M S2                    | Desktop     | [2049c813f6](https://linux-hardware.org/?probe=2049c813f6) | Feb 24, 2022 |
| Gigabyte      | H510M S2                    | Desktop     | [ae837f007b](https://linux-hardware.org/?probe=ae837f007b) | Feb 24, 2022 |
| HP            | 15                          | Notebook    | [7f0f38dc4d](https://linux-hardware.org/?probe=7f0f38dc4d) | Feb 24, 2022 |
| HP            | 15                          | Notebook    | [72f40f8b9a](https://linux-hardware.org/?probe=72f40f8b9a) | Feb 24, 2022 |
| HP            | 15                          | Notebook    | [9fad172623](https://linux-hardware.org/?probe=9fad172623) | Feb 24, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [0e9130cffe](https://linux-hardware.org/?probe=0e9130cffe) | Feb 24, 2022 |
| Lenovo        | IdeaPad 3 15IML05 U 81WB    | Notebook    | [73c7d63295](https://linux-hardware.org/?probe=73c7d63295) | Feb 23, 2022 |
| HP            | 245 G6 Notebook PC          | Notebook    | [4cf4344d75](https://linux-hardware.org/?probe=4cf4344d75) | Feb 23, 2022 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | Notebook    | [73c98934ee](https://linux-hardware.org/?probe=73c98934ee) | Feb 23, 2022 |
| Gigabyte      | G31M-S2L                    | Desktop     | [38511163be](https://linux-hardware.org/?probe=38511163be) | Feb 22, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [baa9583c06](https://linux-hardware.org/?probe=baa9583c06) | Feb 22, 2022 |
| Lenovo        | IdeaPad S540-15IWL D 81N... | Notebook    | [c736f239ba](https://linux-hardware.org/?probe=c736f239ba) | Feb 21, 2022 |
| HP            | Notebook                    | Notebook    | [d8dd214532](https://linux-hardware.org/?probe=d8dd214532) | Feb 21, 2022 |
| HP            | ZBook 15 G5                 | Notebook    | [1947127ef5](https://linux-hardware.org/?probe=1947127ef5) | Feb 21, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [5810a7b666](https://linux-hardware.org/?probe=5810a7b666) | Feb 20, 2022 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [ea2ce4070c](https://linux-hardware.org/?probe=ea2ce4070c) | Feb 20, 2022 |
| Dell          | System XPS L502X            | Notebook    | [110f0aa3e3](https://linux-hardware.org/?probe=110f0aa3e3) | Feb 19, 2022 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [8aaf1cdcde](https://linux-hardware.org/?probe=8aaf1cdcde) | Feb 19, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [0fd79af602](https://linux-hardware.org/?probe=0fd79af602) | Feb 19, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [413a122ef8](https://linux-hardware.org/?probe=413a122ef8) | Feb 19, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [e9ac28286b](https://linux-hardware.org/?probe=e9ac28286b) | Feb 18, 2022 |
| ASUSTek       | X550LC                      | Notebook    | [b6e0cd1dc2](https://linux-hardware.org/?probe=b6e0cd1dc2) | Feb 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [917db2bac9](https://linux-hardware.org/?probe=917db2bac9) | Feb 17, 2022 |
| Acer          | Aspire V3-472PG             | Notebook    | [70c80ae356](https://linux-hardware.org/?probe=70c80ae356) | Feb 16, 2022 |
| Lenovo        | ThinkPad X230 2330A17       | Notebook    | [882f7d3c8b](https://linux-hardware.org/?probe=882f7d3c8b) | Feb 16, 2022 |
| Acer          | Aspire ES1-572              | Notebook    | [ca8f1af83d](https://linux-hardware.org/?probe=ca8f1af83d) | Feb 15, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [bc0d38c096](https://linux-hardware.org/?probe=bc0d38c096) | Feb 15, 2022 |
| Acer          | Aspire ES1-572              | Notebook    | [9d72302b5a](https://linux-hardware.org/?probe=9d72302b5a) | Feb 15, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [2dd964cf93](https://linux-hardware.org/?probe=2dd964cf93) | Feb 15, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [44d0691c56](https://linux-hardware.org/?probe=44d0691c56) | Feb 15, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [647b6a350d](https://linux-hardware.org/?probe=647b6a350d) | Feb 15, 2022 |
| HP            | Snappy                      | Notebook    | [eae991d921](https://linux-hardware.org/?probe=eae991d921) | Feb 14, 2022 |
| Gigabyte      | H97M-D3H                    | Desktop     | [6a911fe257](https://linux-hardware.org/?probe=6a911fe257) | Feb 14, 2022 |
| ASUSTek       | H81M-CS                     | Desktop     | [28b9a2b500](https://linux-hardware.org/?probe=28b9a2b500) | Feb 14, 2022 |
| HP            | Laptop 15s-gr0xxx           | Notebook    | [db6e83a4b8](https://linux-hardware.org/?probe=db6e83a4b8) | Feb 14, 2022 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [9f58500ff7](https://linux-hardware.org/?probe=9f58500ff7) | Feb 13, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [6284595dc0](https://linux-hardware.org/?probe=6284595dc0) | Feb 13, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [1493ffdab1](https://linux-hardware.org/?probe=1493ffdab1) | Feb 13, 2022 |
| Dell          | Latitude E6410              | Notebook    | [787eacd33c](https://linux-hardware.org/?probe=787eacd33c) | Feb 13, 2022 |
| Dell          | Latitude 3420               | Notebook    | [625f453d9a](https://linux-hardware.org/?probe=625f453d9a) | Feb 12, 2022 |
| Sony          | SVE15115EN                  | Notebook    | [facd08033e](https://linux-hardware.org/?probe=facd08033e) | Feb 12, 2022 |
| Lenovo        | ThinkPad T440p 20AN00DJA... | Notebook    | [9209921869](https://linux-hardware.org/?probe=9209921869) | Feb 12, 2022 |
| ASUSTek       | H81M-CS                     | Desktop     | [4f647b985e](https://linux-hardware.org/?probe=4f647b985e) | Feb 12, 2022 |
| Acer          | Aspire A515-54G             | Notebook    | [f8e7f688a6](https://linux-hardware.org/?probe=f8e7f688a6) | Feb 11, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [d50e2fa538](https://linux-hardware.org/?probe=d50e2fa538) | Feb 11, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [e329340668](https://linux-hardware.org/?probe=e329340668) | Feb 11, 2022 |
| Lenovo        | No DPK                      | All in one  | [3e79cadcea](https://linux-hardware.org/?probe=3e79cadcea) | Feb 11, 2022 |
| Gigabyte      | H310M H                     | Desktop     | [1dc6783a71](https://linux-hardware.org/?probe=1dc6783a71) | Feb 11, 2022 |
| Foxconn       | ETON                        | Desktop     | [6069f286d8](https://linux-hardware.org/?probe=6069f286d8) | Feb 11, 2022 |
| HP            | Laptop 15s-dr1xxx           | Notebook    | [8abd201999](https://linux-hardware.org/?probe=8abd201999) | Feb 11, 2022 |
| HP            | Laptop 15s-dr1xxx           | Notebook    | [a84b20f4fd](https://linux-hardware.org/?probe=a84b20f4fd) | Feb 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [6df20f0f72](https://linux-hardware.org/?probe=6df20f0f72) | Feb 11, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [52eb1d5693](https://linux-hardware.org/?probe=52eb1d5693) | Feb 11, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [5182b3bbf6](https://linux-hardware.org/?probe=5182b3bbf6) | Feb 10, 2022 |
| HP            | Notebook                    | Notebook    | [d90ba0e218](https://linux-hardware.org/?probe=d90ba0e218) | Feb 10, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [473350fcea](https://linux-hardware.org/?probe=473350fcea) | Feb 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b2d14e7f15](https://linux-hardware.org/?probe=b2d14e7f15) | Feb 10, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [93c353df0c](https://linux-hardware.org/?probe=93c353df0c) | Feb 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [2661cf0743](https://linux-hardware.org/?probe=2661cf0743) | Feb 10, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [a70524e39c](https://linux-hardware.org/?probe=a70524e39c) | Feb 10, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [869a837ab1](https://linux-hardware.org/?probe=869a837ab1) | Feb 10, 2022 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [63cbb99892](https://linux-hardware.org/?probe=63cbb99892) | Feb 09, 2022 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [da2b6f0bce](https://linux-hardware.org/?probe=da2b6f0bce) | Feb 09, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [ba4d22ff13](https://linux-hardware.org/?probe=ba4d22ff13) | Feb 09, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [12985472a1](https://linux-hardware.org/?probe=12985472a1) | Feb 09, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [075bf197c2](https://linux-hardware.org/?probe=075bf197c2) | Feb 09, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [e17b468160](https://linux-hardware.org/?probe=e17b468160) | Feb 09, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [36ed4fcffa](https://linux-hardware.org/?probe=36ed4fcffa) | Feb 09, 2022 |
| Dell          | 0X2MKR A03                  | All in one  | [4a6b3c26fb](https://linux-hardware.org/?probe=4a6b3c26fb) | Feb 09, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7e1b85d2b0](https://linux-hardware.org/?probe=7e1b85d2b0) | Feb 08, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [bbedc56833](https://linux-hardware.org/?probe=bbedc56833) | Feb 08, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [23adc0f637](https://linux-hardware.org/?probe=23adc0f637) | Feb 08, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [b0f204f246](https://linux-hardware.org/?probe=b0f204f246) | Feb 08, 2022 |
| Lenovo        | G500s 20245                 | Notebook    | [841d62ce23](https://linux-hardware.org/?probe=841d62ce23) | Feb 08, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [231aaa6f98](https://linux-hardware.org/?probe=231aaa6f98) | Feb 07, 2022 |
| Dell          | G5 5500                     | Notebook    | [de24d5a5f8](https://linux-hardware.org/?probe=de24d5a5f8) | Feb 07, 2022 |
| HP            | Laptop 15q-ds0xxx           | Notebook    | [250ec15d99](https://linux-hardware.org/?probe=250ec15d99) | Feb 07, 2022 |
| Lenovo        | IdeaPad S540-15IML D 81N... | Notebook    | [978a3994a9](https://linux-hardware.org/?probe=978a3994a9) | Feb 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [14c25ecf4d](https://linux-hardware.org/?probe=14c25ecf4d) | Feb 07, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [88b0ecde64](https://linux-hardware.org/?probe=88b0ecde64) | Feb 07, 2022 |
| Dell          | 05XGC8 A00                  | Desktop     | [89478dc9b1](https://linux-hardware.org/?probe=89478dc9b1) | Feb 07, 2022 |
| Dell          | 0X2MKR A03                  | All in one  | [dccfa32dd7](https://linux-hardware.org/?probe=dccfa32dd7) | Feb 07, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [b298d77ce8](https://linux-hardware.org/?probe=b298d77ce8) | Feb 06, 2022 |
| Dell          | 07F37C A00                  | Desktop     | [7caf8ccbb1](https://linux-hardware.org/?probe=7caf8ccbb1) | Feb 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [6f11d75bcd](https://linux-hardware.org/?probe=6f11d75bcd) | Feb 06, 2022 |
| HP            | Pavilion 15                 | Notebook    | [58a4d59a59](https://linux-hardware.org/?probe=58a4d59a59) | Feb 05, 2022 |
| HP            | Pavilion 15                 | Notebook    | [35d4cb0015](https://linux-hardware.org/?probe=35d4cb0015) | Feb 05, 2022 |
| AVITA         | NS12T5                      | Tablet      | [74b4233584](https://linux-hardware.org/?probe=74b4233584) | Feb 05, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [db976889a5](https://linux-hardware.org/?probe=db976889a5) | Feb 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [9b802670e0](https://linux-hardware.org/?probe=9b802670e0) | Feb 05, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [d457ee5311](https://linux-hardware.org/?probe=d457ee5311) | Feb 05, 2022 |
| Lenovo        | Legion Y7000 2019 PG0 81... | Notebook    | [f79196e39c](https://linux-hardware.org/?probe=f79196e39c) | Feb 05, 2022 |
| Dell          | G5 5500                     | Notebook    | [edd04957d8](https://linux-hardware.org/?probe=edd04957d8) | Feb 05, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [a4e86f6259](https://linux-hardware.org/?probe=a4e86f6259) | Feb 05, 2022 |
| ASUSTek       | X510UNR                     | Notebook    | [df6616c490](https://linux-hardware.org/?probe=df6616c490) | Feb 04, 2022 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [80cf2c4065](https://linux-hardware.org/?probe=80cf2c4065) | Feb 04, 2022 |
| Lenovo        | G560 20042                  | Notebook    | [642e27a7bd](https://linux-hardware.org/?probe=642e27a7bd) | Feb 04, 2022 |
| HP            | Laptop 15g-br1xx            | Notebook    | [092ea39c7e](https://linux-hardware.org/?probe=092ea39c7e) | Feb 03, 2022 |
| Dell          | Inspiron 5509               | Notebook    | [40aa956ad5](https://linux-hardware.org/?probe=40aa956ad5) | Feb 03, 2022 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [05d8bff376](https://linux-hardware.org/?probe=05d8bff376) | Feb 02, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [a2876a28be](https://linux-hardware.org/?probe=a2876a28be) | Feb 01, 2022 |
| Dell          | Latitude 3520               | Notebook    | [7f6955e406](https://linux-hardware.org/?probe=7f6955e406) | Feb 01, 2022 |
| HP            | Laptop 15s-gr0xxx           | Notebook    | [5943c38ac0](https://linux-hardware.org/?probe=5943c38ac0) | Feb 01, 2022 |
| Samsung       | RV409/RV509/RV709           | Notebook    | [535f5504f0](https://linux-hardware.org/?probe=535f5504f0) | Feb 01, 2022 |
| Dell          | Inspiron 3584               | Notebook    | [14630b0a02](https://linux-hardware.org/?probe=14630b0a02) | Feb 01, 2022 |
| Lenovo        | G580 20157                  | Notebook    | [fe6a35d3f8](https://linux-hardware.org/?probe=fe6a35d3f8) | Jan 31, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [b86eb71aa1](https://linux-hardware.org/?probe=b86eb71aa1) | Jan 31, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [016bea7377](https://linux-hardware.org/?probe=016bea7377) | Jan 31, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [712c420215](https://linux-hardware.org/?probe=712c420215) | Jan 31, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [0c05019294](https://linux-hardware.org/?probe=0c05019294) | Jan 31, 2022 |
| Dell          | Vostro 3558                 | Notebook    | [05d97f5a85](https://linux-hardware.org/?probe=05d97f5a85) | Jan 30, 2022 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [58781ff3be](https://linux-hardware.org/?probe=58781ff3be) | Jan 30, 2022 |
| Lenovo        | Legion Y740-15IRHg 81UH     | Notebook    | [b0cc5e0cbc](https://linux-hardware.org/?probe=b0cc5e0cbc) | Jan 29, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [697f73bc7c](https://linux-hardware.org/?probe=697f73bc7c) | Jan 29, 2022 |
| HP            | 15                          | Notebook    | [81961b52a9](https://linux-hardware.org/?probe=81961b52a9) | Jan 29, 2022 |
| Acer          | TravelMate P214-53G         | Notebook    | [b81086aa28](https://linux-hardware.org/?probe=b81086aa28) | Jan 28, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [4a4b0e0660](https://linux-hardware.org/?probe=4a4b0e0660) | Jan 28, 2022 |
| Acer          | TravelMate P214-53          | Notebook    | [8b138118b8](https://linux-hardware.org/?probe=8b138118b8) | Jan 28, 2022 |
| Lenovo        | E41-25 81FS                 | Notebook    | [692c64fd48](https://linux-hardware.org/?probe=692c64fd48) | Jan 28, 2022 |
| Dell          | Studio 1450                 | Notebook    | [9c2bf5854d](https://linux-hardware.org/?probe=9c2bf5854d) | Jan 28, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [eb4d280c2e](https://linux-hardware.org/?probe=eb4d280c2e) | Jan 28, 2022 |
| ASUSTek       | F1A55-M LX PLUS             | Desktop     | [706b5f2fab](https://linux-hardware.org/?probe=706b5f2fab) | Jan 27, 2022 |
| HP            | EliteBook 1050 G1           | Notebook    | [cf9b0bf009](https://linux-hardware.org/?probe=cf9b0bf009) | Jan 27, 2022 |
| Unknown       | G41 Series                  | Desktop     | [28502ce22e](https://linux-hardware.org/?probe=28502ce22e) | Jan 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [75082acc94](https://linux-hardware.org/?probe=75082acc94) | Jan 27, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [eeadbaa61e](https://linux-hardware.org/?probe=eeadbaa61e) | Jan 26, 2022 |
| HP            | Pavilion Laptop 15-cc0xx    | Notebook    | [e12ec125c1](https://linux-hardware.org/?probe=e12ec125c1) | Jan 26, 2022 |
| Sony          | SVE15113ENW                 | Notebook    | [4ed2d681e5](https://linux-hardware.org/?probe=4ed2d681e5) | Jan 26, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [17282e26a5](https://linux-hardware.org/?probe=17282e26a5) | Jan 26, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [c9b1b53061](https://linux-hardware.org/?probe=c9b1b53061) | Jan 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X532... | Notebook    | [bc4d814298](https://linux-hardware.org/?probe=bc4d814298) | Jan 24, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [36709c59ac](https://linux-hardware.org/?probe=36709c59ac) | Jan 24, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [880cca4c8f](https://linux-hardware.org/?probe=880cca4c8f) | Jan 24, 2022 |
| Dell          | 0Y2YM6 A01                  | Desktop     | [7db41f9b7e](https://linux-hardware.org/?probe=7db41f9b7e) | Jan 24, 2022 |
| ASUSTek       | D642MF                      | Desktop     | [1d59c9470c](https://linux-hardware.org/?probe=1d59c9470c) | Jan 23, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [34568da477](https://linux-hardware.org/?probe=34568da477) | Jan 23, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [d6ea0ad749](https://linux-hardware.org/?probe=d6ea0ad749) | Jan 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [086f2b17b3](https://linux-hardware.org/?probe=086f2b17b3) | Jan 23, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [8e23028f92](https://linux-hardware.org/?probe=8e23028f92) | Jan 23, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [ce753b3532](https://linux-hardware.org/?probe=ce753b3532) | Jan 23, 2022 |
| HP            | Laptop 14q-cs0xxx           | Notebook    | [ec9061dcb1](https://linux-hardware.org/?probe=ec9061dcb1) | Jan 22, 2022 |
| Acer          | Predator PH315-51           | Notebook    | [1df9cf7c06](https://linux-hardware.org/?probe=1df9cf7c06) | Jan 22, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [af6171a374](https://linux-hardware.org/?probe=af6171a374) | Jan 22, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [33079ee3bf](https://linux-hardware.org/?probe=33079ee3bf) | Jan 22, 2022 |
| Acer          | Predator PH315-51           | Notebook    | [291f22ae53](https://linux-hardware.org/?probe=291f22ae53) | Jan 21, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [0df160c245](https://linux-hardware.org/?probe=0df160c245) | Jan 21, 2022 |
| Fujitsu       | LIFEBOOK LH532              | Notebook    | [0459069843](https://linux-hardware.org/?probe=0459069843) | Jan 21, 2022 |
| Dell          | G15 5511                    | Notebook    | [b1a127367b](https://linux-hardware.org/?probe=b1a127367b) | Jan 20, 2022 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [e092fc4b26](https://linux-hardware.org/?probe=e092fc4b26) | Jan 20, 2022 |
| Gigabyte      | H310M H                     | Desktop     | [462f42e8f1](https://linux-hardware.org/?probe=462f42e8f1) | Jan 20, 2022 |
| HP            | ZBook Power 15.6 inch G8... | Notebook    | [245123d0a8](https://linux-hardware.org/?probe=245123d0a8) | Jan 20, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [675d700954](https://linux-hardware.org/?probe=675d700954) | Jan 20, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [5fe905242e](https://linux-hardware.org/?probe=5fe905242e) | Jan 20, 2022 |
| Fujitsu       | LIFEBOOK LH532              | Notebook    | [58be376485](https://linux-hardware.org/?probe=58be376485) | Jan 20, 2022 |
| HP            | ZBook Power 15.6 inch G8... | Notebook    | [0b07369103](https://linux-hardware.org/?probe=0b07369103) | Jan 19, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [d99cb4b767](https://linux-hardware.org/?probe=d99cb4b767) | Jan 19, 2022 |
| Dell          | Precision 5540              | Notebook    | [2d971f9a85](https://linux-hardware.org/?probe=2d971f9a85) | Jan 19, 2022 |
| ASUSTek       | ROG Zephyrus M15 GU502LW... | Notebook    | [2407b5f5bb](https://linux-hardware.org/?probe=2407b5f5bb) | Jan 19, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [ec51f5ca3e](https://linux-hardware.org/?probe=ec51f5ca3e) | Jan 19, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [2e7e3ccc17](https://linux-hardware.org/?probe=2e7e3ccc17) | Jan 19, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [6efcabe998](https://linux-hardware.org/?probe=6efcabe998) | Jan 18, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [a30f5fabcd](https://linux-hardware.org/?probe=a30f5fabcd) | Jan 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0fddd05eae](https://linux-hardware.org/?probe=0fddd05eae) | Jan 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X411... | Notebook    | [6294ff032d](https://linux-hardware.org/?probe=6294ff032d) | Jan 18, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [9901f0a14a](https://linux-hardware.org/?probe=9901f0a14a) | Jan 18, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [3837c06ca1](https://linux-hardware.org/?probe=3837c06ca1) | Jan 18, 2022 |
| Lenovo        | ThinkCentre M71e 3157R75    | Desktop     | [871b2aecd9](https://linux-hardware.org/?probe=871b2aecd9) | Jan 17, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [8ffc80bc8d](https://linux-hardware.org/?probe=8ffc80bc8d) | Jan 17, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [5a6275014a](https://linux-hardware.org/?probe=5a6275014a) | Jan 17, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [7cc691c557](https://linux-hardware.org/?probe=7cc691c557) | Jan 16, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [ff8151d1c1](https://linux-hardware.org/?probe=ff8151d1c1) | Jan 16, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [b70c5a1312](https://linux-hardware.org/?probe=b70c5a1312) | Jan 16, 2022 |
| Dell          | Latitude E6510              | Notebook    | [c0d3a6c31a](https://linux-hardware.org/?probe=c0d3a6c31a) | Jan 16, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [a1fffe7c0f](https://linux-hardware.org/?probe=a1fffe7c0f) | Jan 16, 2022 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [339d7aa470](https://linux-hardware.org/?probe=339d7aa470) | Jan 15, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [a6c2013bf1](https://linux-hardware.org/?probe=a6c2013bf1) | Jan 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [80f7288259](https://linux-hardware.org/?probe=80f7288259) | Jan 15, 2022 |
| Lenovo        | G580 20157                  | Notebook    | [67c671c04f](https://linux-hardware.org/?probe=67c671c04f) | Jan 15, 2022 |
| HP            | Laptop 15s-du2xxx           | Notebook    | [7ea05d0591](https://linux-hardware.org/?probe=7ea05d0591) | Jan 15, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [71480de13b](https://linux-hardware.org/?probe=71480de13b) | Jan 14, 2022 |
| Acer          | Swift SF314-55G             | Notebook    | [fc48cf8ace](https://linux-hardware.org/?probe=fc48cf8ace) | Jan 14, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [23160ed698](https://linux-hardware.org/?probe=23160ed698) | Jan 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [eee9a2ae45](https://linux-hardware.org/?probe=eee9a2ae45) | Jan 14, 2022 |
| ASUSTek       | H61M-CS                     | Desktop     | [8855875fbd](https://linux-hardware.org/?probe=8855875fbd) | Jan 14, 2022 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [7a5a59c6e6](https://linux-hardware.org/?probe=7a5a59c6e6) | Jan 13, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/India/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 880       | 23.68%  |
| Ubuntu 18.04                 | 406       | 10.93%  |
| Ubuntu 22.04                 | 116       | 3.12%   |
| Arch                         | 104       | 2.8%    |
| KDE neon 20.04               | 81        | 2.18%   |
| OpenMandriva 4.3             | 68        | 1.83%   |
| Pop!_OS 20.04                | 67        | 1.8%    |
| Pop!_OS 21.04                | 59        | 1.59%   |
| Arch Rolling                 | 59        | 1.59%   |
| Ubuntu 20.10                 | 58        | 1.56%   |
| Fedora 34                    | 58        | 1.56%   |
| OpenMandriva 4.2             | 56        | 1.51%   |
| Fedora 36                    | 56        | 1.51%   |
| Zorin 16                     | 55        | 1.48%   |
| Zorin 15                     | 55        | 1.48%   |
| Ubuntu 21.04                 | 53        | 1.43%   |
| Ubuntu 19.10                 | 51        | 1.37%   |
| ArcoLinux Rolling            | 46        | 1.24%   |
| Ubuntu 19.04                 | 45        | 1.21%   |
| Ubuntu 21.10                 | 44        | 1.18%   |
| Pop!_OS 20.10                | 44        | 1.18%   |
| Manjaro                      | 42        | 1.13%   |
| Fedora 35                    | 39        | 1.05%   |
| Fedora 32                    | 38        | 1.02%   |
| Ubuntu Unity 16.04           | 34        | 0.91%   |
| Pop!_OS 22.04                | 34        | 0.91%   |
| Fedora 33                    | 34        | 0.91%   |
| Linux Mint 20                | 33        | 0.89%   |
| Ubuntu 16.04                 | 32        | 0.86%   |
| Linux Mint 20.2              | 32        | 0.86%   |
| Linux Mint 20.3              | 31        | 0.83%   |
| Linux Mint 20.1              | 30        | 0.81%   |
| Debian 10                    | 28        | 0.75%   |
| Debian 11                    | 25        | 0.67%   |
| Kubuntu 20.04                | 24        | 0.65%   |
| Linux Mint 19.3              | 22        | 0.59%   |
| Pop!_OS 21.10                | 20        | 0.54%   |
| openSUSE Tumbleweed-XXXXXXXX | 20        | 0.54%   |
| Elementary 6.1               | 19        | 0.51%   |
| Fedora 31                    | 18        | 0.48%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1662      | 46.28%  |
| Fedora        | 233       | 6.49%   |
| Pop!_OS       | 217       | 6.04%   |
| Linux Mint    | 157       | 4.37%   |
| Arch          | 157       | 4.37%   |
| OpenMandriva  | 134       | 3.73%   |
| Zorin         | 110       | 3.06%   |
| Manjaro       | 104       | 2.9%    |
| KDE neon      | 91        | 2.53%   |
| Debian        | 73        | 2.03%   |
| Ubuntu Unity  | 57        | 1.59%   |
| Kali          | 53        | 1.48%   |
| ArcoLinux     | 52        | 1.45%   |
| Kubuntu       | 50        | 1.39%   |
| Endless       | 49        | 1.36%   |
| Elementary    | 49        | 1.36%   |
| Xubuntu       | 29        | 0.81%   |
| openSUSE      | 25        | 0.7%    |
| CentOS        | 23        | 0.64%   |
| ROSA          | 22        | 0.61%   |
| Clear Linux   | 20        | 0.56%   |
| RHEL          | 19        | 0.53%   |
| EndeavourOS   | 18        | 0.5%    |
| Garuda Linux  | 17        | 0.47%   |
| Ubuntu MATE   | 13        | 0.36%   |
| Ubuntu Budgie | 12        | 0.33%   |
| Lubuntu       | 11        | 0.31%   |
| MX            | 10        | 0.28%   |
| Void Linux    | 9         | 0.25%   |
| Solus         | 9         | 0.25%   |
| Parrot        | 9         | 0.25%   |
| Xero          | 8         | 0.22%   |
| Peppermint    | 7         | 0.19%   |
| Gentoo        | 7         | 0.19%   |
| BlackPanther  | 6         | 0.17%   |
| Artix         | 5         | 0.14%   |
| Slackware     | 4         | 0.11%   |
| Nobara        | 4         | 0.11%   |
| LMDE          | 4         | 0.11%   |
| LinuxFX       | 4         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 152       | 3.82%   |
| 5.16.7-desktop-1omv4003  | 66        | 1.66%   |
| 5.4.0-40-generic         | 61        | 1.53%   |
| 5.10.14-desktop-1omv4002 | 56        | 1.41%   |
| 5.4.0-48-generic         | 47        | 1.18%   |
| 5.4.0-58-generic         | 43        | 1.08%   |
| 5.4.0-52-generic         | 40        | 1%      |
| 5.4.0-26-generic         | 40        | 1%      |
| 5.4.0-47-generic         | 39        | 0.98%   |
| 5.11.0-27-generic        | 38        | 0.95%   |
| 5.11.0-25-generic        | 35        | 0.88%   |
| 5.11.0-7620-generic      | 34        | 0.85%   |
| 5.4.0-29-generic         | 33        | 0.83%   |
| 5.8.0-48-generic         | 29        | 0.73%   |
| 5.3.0-28-generic         | 29        | 0.73%   |
| 5.11.0-40-generic        | 29        | 0.73%   |
| 5.8.0-53-generic         | 28        | 0.7%    |
| 5.15.0-46-generic        | 28        | 0.7%    |
| 5.8.0-55-generic         | 27        | 0.68%   |
| 5.8.0-43-generic         | 27        | 0.68%   |
| 5.4.0-37-generic         | 27        | 0.68%   |
| 5.11.0-43-generic        | 26        | 0.65%   |
| 5.11.0-38-generic        | 26        | 0.65%   |
| 5.11.0-37-generic        | 26        | 0.65%   |
| 5.0.0-37-generic         | 25        | 0.63%   |
| 5.8.0-59-generic         | 24        | 0.6%    |
| 5.8.0-44-generic         | 24        | 0.6%    |
| 5.4.0-74-generic         | 24        | 0.6%    |
| 5.3.0-40-generic         | 24        | 0.6%    |
| 4.15.0-45-generic        | 24        | 0.6%    |
| 5.4.0-45-generic         | 23        | 0.58%   |
| 5.3.0-51-generic         | 23        | 0.58%   |
| 5.13.0-30-generic        | 23        | 0.58%   |
| 5.0.0-23-generic         | 22        | 0.55%   |
| 5.8.0-7630-generic       | 21        | 0.53%   |
| 5.8.0-50-generic         | 21        | 0.53%   |
| 5.4.0-39-generic         | 21        | 0.53%   |
| 5.13.0-40-generic        | 21        | 0.53%   |
| 5.11.0-41-generic        | 21        | 0.53%   |
| 5.4.0-54-generic         | 20        | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 854       | 22.44%  |
| 5.11.0  | 330       | 8.67%   |
| 5.8.0   | 310       | 8.15%   |
| 4.15.0  | 235       | 6.18%   |
| 5.13.0  | 200       | 5.26%   |
| 5.3.0   | 192       | 5.05%   |
| 5.15.0  | 154       | 4.05%   |
| 5.0.0   | 130       | 3.42%   |
| 4.18.0  | 102       | 2.68%   |
| 5.16.7  | 68        | 1.79%   |
| 5.10.0  | 59        | 1.55%   |
| 5.10.14 | 56        | 1.47%   |
| 4.19.0  | 29        | 0.76%   |
| 4.4.0   | 25        | 0.66%   |
| 5.14.0  | 24        | 0.63%   |
| 5.17.5  | 19        | 0.5%    |
| 5.7.0   | 14        | 0.37%   |
| 5.9.0   | 12        | 0.32%   |
| 5.15.11 | 12        | 0.32%   |
| 5.17.9  | 11        | 0.29%   |
| 5.18.0  | 10        | 0.26%   |
| 5.16.11 | 10        | 0.26%   |
| 5.13.12 | 10        | 0.26%   |
| 5.6.6   | 9         | 0.24%   |
| 5.19.0  | 9         | 0.24%   |
| 5.16.0  | 9         | 0.24%   |
| 5.15.8  | 9         | 0.24%   |
| 5.15.5  | 9         | 0.24%   |
| 5.13.9  | 9         | 0.24%   |
| 5.9.16  | 8         | 0.21%   |
| 5.6.0   | 8         | 0.21%   |
| 5.5.0   | 8         | 0.21%   |
| 5.18.6  | 8         | 0.21%   |
| 5.18.5  | 8         | 0.21%   |
| 5.17.4  | 8         | 0.21%   |
| 5.13.19 | 8         | 0.21%   |
| 5.12.7  | 8         | 0.21%   |
| 5.8.15  | 7         | 0.18%   |
| 5.19.9  | 7         | 0.18%   |
| 5.19.8  | 7         | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 894       | 23.71%  |
| 5.8     | 370       | 9.81%   |
| 5.11    | 368       | 9.76%   |
| 5.15    | 264       | 7%      |
| 5.13    | 254       | 6.74%   |
| 4.15    | 238       | 6.31%   |
| 5.3     | 218       | 5.78%   |
| 5.10    | 186       | 4.93%   |
| 5.0     | 133       | 3.53%   |
| 5.16    | 129       | 3.42%   |
| 4.18    | 108       | 2.86%   |
| 5.17    | 78        | 2.07%   |
| 5.14    | 76        | 2.02%   |
| 5.18    | 67        | 1.78%   |
| 5.12    | 55        | 1.46%   |
| 5.9     | 50        | 1.33%   |
| 5.7     | 49        | 1.3%    |
| 5.19    | 42        | 1.11%   |
| 5.6     | 41        | 1.09%   |
| 4.19    | 41        | 1.09%   |
| 4.4     | 28        | 0.74%   |
| 5.5     | 26        | 0.69%   |
| 4.9     | 16        | 0.42%   |
| 5.2     | 8         | 0.21%   |
| 3.10    | 7         | 0.19%   |
| 4.13    | 5         | 0.13%   |
| 5.1     | 4         | 0.11%   |
| 4.20    | 3         | 0.08%   |
| 3.16    | 3         | 0.08%   |
| 4.14    | 2         | 0.05%   |
| 4.1     | 2         | 0.05%   |
| 5       | 1         | 0.03%   |
| 4.17    | 1         | 0.03%   |
| 4.16    | 1         | 0.03%   |
| 4.12    | 1         | 0.03%   |
| 4.10    | 1         | 0.03%   |
| 3.13    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3394      | 97.61%  |
| i686    | 65        | 1.87%   |
| aarch64 | 12        | 0.35%   |
| armv7l  | 6         | 0.17%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 2040      | 56.56%  |
| Unknown           | 460       | 12.75%  |
| KDE5              | 385       | 10.67%  |
| XFCE              | 166       | 4.6%    |
| X-Cinnamon        | 119       | 3.3%    |
| KDE               | 105       | 2.91%   |
| Unity             | 59        | 1.64%   |
| Pantheon          | 47        | 1.3%    |
| MATE              | 40        | 1.11%   |
| Cinnamon          | 34        | 0.94%   |
| GNOME Flashback   | 24        | 0.67%   |
| Budgie            | 19        | 0.53%   |
| LXDE              | 15        | 0.42%   |
| i3                | 15        | 0.42%   |
| Deepin            | 13        | 0.36%   |
| LXQt              | 11        | 0.3%    |
| KDE4              | 10        | 0.28%   |
| awesome           | 8         | 0.22%   |
| sway              | 6         | 0.17%   |
| bspwm             | 6         | 0.17%   |
| qtile             | 5         | 0.14%   |
| openbox           | 5         | 0.14%   |
| GNOME Classic     | 5         | 0.14%   |
| xmonad            | 3         | 0.08%   |
| LeftWM            | 2         | 0.06%   |
| Yaru:ubuntu:GNOME | 1         | 0.03%   |
| lightdm-xsession  | 1         | 0.03%   |
| i3-with-shmlog    | 1         | 0.03%   |
| i3-gaps           | 1         | 0.03%   |
| DWM               | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 2739      | 76.87%  |
| Wayland | 502       | 14.09%  |
| Unknown | 279       | 7.83%   |
| Tty     | 43        | 1.21%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1976      | 55.13%  |
| GDM     | 642       | 17.91%  |
| SDDM    | 362       | 10.1%   |
| GDM3    | 269       | 7.51%   |
| LightDM | 210       | 5.86%   |
| TDM     | 105       | 2.93%   |
| KDM     | 9         | 0.25%   |
| XDM     | 3         | 0.08%   |
| Ly      | 3         | 0.08%   |
| LXDM    | 3         | 0.08%   |
| SLiM    | 2         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_IN   | 2160      | 60.18%  |
| en_US   | 903       | 25.16%  |
| Unknown | 372       | 10.37%  |
| en_GB   | 67        | 1.87%   |
| C       | 60        | 1.67%   |
| en_AG   | 5         | 0.14%   |
| en_CA   | 3         | 0.08%   |
| zh_TW   | 2         | 0.06%   |
| POSIX   | 2         | 0.06%   |
| mr_IN   | 2         | 0.06%   |
| mni_IN  | 2         | 0.06%   |
| en_IE   | 2         | 0.06%   |
| en_AU   | 2         | 0.06%   |
| sa_IN   | 1         | 0.03%   |
| ks_IN   | 1         | 0.03%   |
| es_ES   | 1         | 0.03%   |
| en_SG   | 1         | 0.03%   |
| en_BW   | 1         | 0.03%   |
| de_DE   | 1         | 0.03%   |
| C.UTF8  | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 2030      | 57.43%  |
| BIOS | 1505      | 42.57%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 2942      | 83.34%  |
| Btrfs   | 264       | 7.48%   |
| Overlay | 155       | 4.39%   |
| Unknown | 78        | 2.21%   |
| Xfs     | 58        | 1.64%   |
| Ext2    | 12        | 0.34%   |
| Zfs     | 9         | 0.25%   |
| Ext3    | 7         | 0.2%    |
| F2fs    | 2         | 0.06%   |
| Tmpfs   | 1         | 0.03%   |
| Jfs     | 1         | 0.03%   |
| Aufs    | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2123      | 60.19%  |
| GPT     | 1153      | 32.69%  |
| MBR     | 251       | 7.12%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3069      | 86.97%  |
| Yes       | 460       | 13.03%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2125      | 60.22%  |
| Yes       | 1404      | 39.78%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo                   | 680       | 19.57%  |
| Hewlett-Packard          | 670       | 19.28%  |
| Dell                     | 658       | 18.94%  |
| ASUSTek Computer         | 440       | 12.66%  |
| Acer                     | 222       | 6.39%   |
| Gigabyte Technology      | 217       | 6.24%   |
| Intel                    | 112       | 3.22%   |
| MSI                      | 103       | 2.96%   |
| Unknown                  | 55        | 1.58%   |
| Sony                     | 44        | 1.27%   |
| Toshiba                  | 32        | 0.92%   |
| ASRock                   | 25        | 0.72%   |
| Apple                    | 23        | 0.66%   |
| Samsung Electronics      | 22        | 0.63%   |
| AVITA                    | 17        | 0.49%   |
| OEM                      | 12        | 0.35%   |
| ECS                      | 11        | 0.32%   |
| Biostar                  | 11        | 0.32%   |
| Timi                     | 10        | 0.29%   |
| Raspberry Pi Foundation  | 9         | 0.26%   |
| HCL Infosystems Limited  | 7         | 0.2%    |
| Fujitsu                  | 7         | 0.2%    |
| AMI                      | 7         | 0.2%    |
| Google                   | 6         | 0.17%   |
| Foxconn                  | 6         | 0.17%   |
| HUAWEI                   | 5         | 0.14%   |
| Radxa                    | 4         | 0.12%   |
| LG Electronics           | 4         | 0.12%   |
| eMachines                | 4         | 0.12%   |
| Alienware                | 4         | 0.12%   |
| WIPRO                    | 3         | 0.09%   |
| realme                   | 3         | 0.09%   |
| Pegatron                 | 3         | 0.09%   |
| LORD ELECTRONICS         | 3         | 0.09%   |
| Supermicro               | 2         | 0.06%   |
| Razer                    | 2         | 0.06%   |
| MICROMAX                 | 2         | 0.06%   |
| Insyde                   | 2         | 0.06%   |
| Gateway                  | 2         | 0.06%   |
| Coconics Private Limited | 2         | 0.06%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 77        | 2.22%   |
| HP Notebook                            | 68        | 1.96%   |
| HP 15                                  | 27        | 0.78%   |
| HP Pavilion 15                         | 26        | 0.75%   |
| Dell Inspiron 3542                     | 24        | 0.69%   |
| HP Pavilion g6                         | 23        | 0.66%   |
| Gigabyte H410M H V3                    | 23        | 0.66%   |
| HP Laptop 15-bs0xx                     | 20        | 0.58%   |
| Dell Inspiron 5570                     | 20        | 0.58%   |
| Dell Inspiron 15-3567                  | 20        | 0.58%   |
| Lenovo IdeaPad 330-15IKB 81DE          | 16        | 0.46%   |
| Lenovo E41-25 81FS                     | 16        | 0.46%   |
| HP Pavilion Notebook                   | 16        | 0.46%   |
| Dell Inspiron 3521                     | 16        | 0.46%   |
| Acer Aspire A715-75G                   | 16        | 0.46%   |
| Dell Vostro 3480                       | 14        | 0.4%    |
| ASUS TUF Gaming FX505DT_FX505DT        | 14        | 0.4%    |
| Intel H61                              | 13        | 0.37%   |
| Gigabyte H61MS                         | 13        | 0.37%   |
| Lenovo G50-80 80E5                     | 12        | 0.35%   |
| Dell Vostro 15-3568                    | 12        | 0.35%   |
| Lenovo G50-45 80E3                     | 11        | 0.32%   |
| HP Laptop 15-da0xxx                    | 11        | 0.32%   |
| HP Laptop 15-bw0xx                     | 11        | 0.32%   |
| Gigabyte H81M-S                        | 11        | 0.32%   |
| Dell Vostro 3578                       | 11        | 0.32%   |
| Dell Inspiron 5559                     | 11        | 0.32%   |
| ASUS X510UNR                           | 11        | 0.32%   |
| Intel HCL Desktop                      | 10        | 0.29%   |
| HP Pavilion x360 Convertible 14-dh1xxx | 10        | 0.29%   |
| Gigabyte H110M-S2                      | 10        | 0.29%   |
| Dell Vostro 3478                       | 10        | 0.29%   |
| ASUS X556UQK                           | 10        | 0.29%   |
| Lenovo ThinkBook 14-IML 20RV           | 9         | 0.26%   |
| Lenovo IdeaPad 520-15IKB 81BF          | 9         | 0.26%   |
| Lenovo IdeaPad 320-15ISK 80XH          | 9         | 0.26%   |
| HP Pavilion Gaming Laptop 15-ec2xxx    | 9         | 0.26%   |
| HP Pavilion dv6                        | 9         | 0.26%   |
| Gigabyte A320M-S2H                     | 9         | 0.26%   |
| Dell Inspiron 5520                     | 9         | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Dell Inspiron      | 296       | 8.52%   |
| Lenovo IdeaPad     | 222       | 6.39%   |
| Lenovo ThinkPad    | 212       | 6.1%    |
| HP Pavilion        | 187       | 5.38%   |
| HP Laptop          | 129       | 3.71%   |
| Dell Vostro        | 122       | 3.51%   |
| Dell Latitude      | 119       | 3.42%   |
| ASUS VivoBook      | 119       | 3.42%   |
| Acer Aspire        | 118       | 3.4%    |
| Unknown            | 77        | 2.22%   |
| HP Notebook        | 69        | 1.99%   |
| HP EliteBook       | 47        | 1.35%   |
| ASUS TUF           | 47        | 1.35%   |
| HP ProBook         | 40        | 1.15%   |
| Dell OptiPlex      | 40        | 1.15%   |
| ASUS ROG           | 39        | 1.12%   |
| ASUS ASUS          | 30        | 0.86%   |
| ASUS PRIME         | 29        | 0.83%   |
| HP 15              | 28        | 0.81%   |
| Dell XPS           | 28        | 0.81%   |
| Toshiba Satellite  | 27        | 0.78%   |
| Gigabyte H410M     | 27        | 0.78%   |
| Acer Nitro         | 27        | 0.78%   |
| Lenovo Legion      | 24        | 0.69%   |
| Acer Swift         | 24        | 0.69%   |
| HP ENVY            | 21        | 0.6%    |
| HP Compaq          | 21        | 0.6%    |
| Dell Precision     | 21        | 0.6%    |
| Lenovo ThinkBook   | 19        | 0.55%   |
| Lenovo E41-25      | 16        | 0.46%   |
| Lenovo ThinkCentre | 14        | 0.4%    |
| Lenovo IdeaPadFlex | 14        | 0.4%    |
| HP OMEN            | 14        | 0.4%    |
| Acer Predator      | 14        | 0.4%    |
| Lenovo Yoga        | 13        | 0.37%   |
| Intel H61          | 13        | 0.37%   |
| Gigabyte H61MS     | 13        | 0.37%   |
| Gigabyte H310M     | 13        | 0.37%   |
| Dell G3            | 13        | 0.37%   |
| Acer Veriton       | 13        | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 494       | 14.22%  |
| 2019    | 480       | 13.81%  |
| 2020    | 360       | 10.36%  |
| 2017    | 321       | 9.24%   |
| 2021    | 241       | 6.94%   |
| 2016    | 229       | 6.59%   |
| 2012    | 223       | 6.42%   |
| 2013    | 214       | 6.16%   |
| 2014    | 208       | 5.99%   |
| 2011    | 199       | 5.73%   |
| 2015    | 164       | 4.72%   |
| 2010    | 150       | 4.32%   |
| 2008    | 65        | 1.87%   |
| 2009    | 59        | 1.7%    |
| 2007    | 21        | 0.6%    |
| 2022    | 19        | 0.55%   |
| Unknown | 16        | 0.46%   |
| 2006    | 8         | 0.23%   |
| 2005    | 3         | 0.09%   |
| 2003    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2517      | 72.43%  |
| Desktop        | 788       | 22.68%  |
| Convertible    | 84        | 2.42%   |
| All in one     | 26        | 0.75%   |
| Mini pc        | 25        | 0.72%   |
| System on chip | 17        | 0.49%   |
| Tablet         | 9         | 0.26%   |
| Server         | 9         | 0.26%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3075      | 87.83%  |
| Enabled  | 426       | 12.17%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3465      | 99.71%  |
| Yes  | 10        | 0.29%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1100      | 31.32%  |
| 3.01-4.0    | 881       | 25.09%  |
| 8.01-16.0   | 652       | 18.56%  |
| 16.01-24.0  | 523       | 14.89%  |
| 1.01-2.0    | 144       | 4.1%    |
| 32.01-64.0  | 114       | 3.25%   |
| 2.01-3.0    | 37        | 1.05%   |
| 64.01-256.0 | 24        | 0.68%   |
| 24.01-32.0  | 19        | 0.54%   |
| 0.51-1.0    | 16        | 0.46%   |
| 0.01-0.5    | 2         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1301      | 34.42%  |
| 2.01-3.0   | 1196      | 31.64%  |
| 3.01-4.0   | 503       | 13.31%  |
| 4.01-8.0   | 500       | 13.23%  |
| 0.51-1.0   | 144       | 3.81%   |
| 8.01-16.0  | 93        | 2.46%   |
| 0.01-0.5   | 31        | 0.82%   |
| 16.01-24.0 | 8         | 0.21%   |
| 32.01-64.0 | 2         | 0.05%   |
| 24.01-32.0 | 1         | 0.03%   |
| Unknown    | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2492      | 70.76%  |
| 2      | 839       | 23.82%  |
| 3      | 111       | 3.15%   |
| 0      | 30        | 0.85%   |
| 4      | 28        | 0.8%    |
| 5      | 11        | 0.31%   |
| 6      | 7         | 0.2%    |
| 7      | 2         | 0.06%   |
| 9      | 1         | 0.03%   |
| 8      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2214      | 63.35%  |
| Yes       | 1281      | 36.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2916      | 83.77%  |
| No        | 565       | 16.23%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3028      | 86.71%  |
| No        | 464       | 13.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2525      | 71.96%  |
| No        | 984       | 28.04%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| India   | 3475      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Bengaluru     | 424       | 11.48%  |
| Mumbai        | 256       | 6.93%   |
| Chennai       | 235       | 6.37%   |
| Hyderabad     | 201       | 5.44%   |
| Pune          | 176       | 4.77%   |
| New Delhi     | 171       | 4.63%   |
| Kolkata       | 163       | 4.41%   |
| Delhi         | 141       | 3.82%   |
| Ahmedabad     | 81        | 2.19%   |
| Ernakulam     | 75        | 2.03%   |
| Patna         | 69        | 1.87%   |
| Lucknow       | 69        | 1.87%   |
| Jaipur        | 60        | 1.63%   |
| Gurgaon       | 52        | 1.41%   |
| Bhopal        | 47        | 1.27%   |
| Navi Mumbai   | 46        | 1.25%   |
| Indore        | 44        | 1.19%   |
| Coimbatore    | 40        | 1.08%   |
| Thrissur      | 37        | 1%      |
| Surat         | 36        | 0.98%   |
| Trivandrum    | 35        | 0.95%   |
| Malappuram    | 31        | 0.84%   |
| Guwahati      | 30        | 0.81%   |
| Ludhiana      | 28        | 0.76%   |
| Nagpur        | 25        | 0.68%   |
| Kochi         | 24        | 0.65%   |
| Bhubaneswar   | 24        | 0.65%   |
| Gonikoppal    | 22        | 0.6%    |
| Noida         | 21        | 0.57%   |
| Vijayawada    | 19        | 0.51%   |
| Thane         | 19        | 0.51%   |
| Vadodara      | 17        | 0.46%   |
| Ghaziabad     | 17        | 0.46%   |
| Visakhapatnam | 16        | 0.43%   |
| Mangalore     | 16        | 0.43%   |
| Kanpur        | 16        | 0.43%   |
| Kozhikode     | 15        | 0.41%   |
| Raipur        | 14        | 0.38%   |
| Mohali        | 14        | 0.38%   |
| Kottayam      | 14        | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 1007      | 1299   | 22.96%  |
| WDC                       | 864       | 1090   | 19.7%   |
| Toshiba                   | 472       | 533    | 10.76%  |
| Samsung Electronics       | 396       | 508    | 9.03%   |
| Kingston                  | 174       | 209    | 3.97%   |
| SanDisk                   | 166       | 207    | 3.79%   |
| Crucial                   | 154       | 198    | 3.51%   |
| HGST                      | 151       | 175    | 3.44%   |
| SK hynix                  | 143       | 160    | 3.26%   |
| Intel                     | 135       | 181    | 3.08%   |
| Unknown                   | 104       | 131    | 2.37%   |
| Hitachi                   | 97        | 117    | 2.21%   |
| Micron Technology         | 74        | 87     | 1.69%   |
| A-DATA Technology         | 63        | 69     | 1.44%   |
| KIOXIA                    | 46        | 56     | 1.05%   |
| China                     | 22        | 24     | 0.5%    |
| Gigabyte Technology       | 18        | 21     | 0.41%   |
| Unknown                   | 17        | 17     | 0.39%   |
| Phison                    | 16        | 19     | 0.36%   |
| Hewlett-Packard           | 16        | 22     | 0.36%   |
| Micron/Crucial Technology | 15        | 17     | 0.34%   |
| Silicon Motion            | 14        | 16     | 0.32%   |
| LITEON                    | 14        | 16     | 0.32%   |
| Apple                     | 14        | 18     | 0.32%   |
| UMIS                      | 13        | 15     | 0.3%    |
| Maxtor                    | 10        | 21     | 0.23%   |
| FORESEE                   | 10        | 11     | 0.23%   |
| SPCC                      | 9         | 13     | 0.21%   |
| TO Exter                  | 7         | 7      | 0.16%   |
| Fujitsu                   | 7         | 7      | 0.16%   |
| Transcend                 | 6         | 7      | 0.14%   |
| XPG                       | 5         | 6      | 0.11%   |
| Union Memory              | 5         | 6      | 0.11%   |
| Realtek Semiconductor     | 5         | 6      | 0.11%   |
| Lexar                     | 5         | 5      | 0.11%   |
| PNY                       | 4         | 6      | 0.09%   |
| Leven                     | 4         | 4      | 0.09%   |
| Lenovo                    | 4         | 6      | 0.09%   |
| HS-SSD-C100               | 4         | 6      | 0.09%   |
| External                  | 4         | 7      | 0.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB     | 250       | 5.43%   |
| Toshiba MQ04ABF100 1TB             | 126       | 2.74%   |
| Toshiba MQ01ABD100 1TB             | 100       | 2.17%   |
| Seagate ST1000DM010-2EP102 1TB     | 74        | 1.61%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 58        | 1.26%   |
| Seagate ST500LT012-1DG142 500GB    | 58        | 1.26%   |
| Seagate ST1000LM049-2GH172 1TB     | 56        | 1.22%   |
| Crucial CT240BX500SSD1 240GB       | 55        | 1.19%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 53        | 1.15%   |
| Intel NVMe SSD Drive 512GB         | 52        | 1.13%   |
| Kingston SA400S37240G 240GB SSD    | 46        | 1%      |
| Toshiba MQ01ABF050 500GB           | 38        | 0.83%   |
| SanDisk NVMe SSD Drive 256GB       | 38        | 0.83%   |
| Samsung NVMe SSD Drive 512GB       | 36        | 0.78%   |
| Toshiba DT01ACA100 1TB             | 35        | 0.76%   |
| Seagate ST500DM002-1BD142 500GB    | 34        | 0.74%   |
| SanDisk NVMe SSD Drive 512GB       | 33        | 0.72%   |
| Intel SSDPEKNW512G8 512GB          | 32        | 0.7%    |
| HGST HTS541010A9E680 1TB           | 32        | 0.7%    |
| Seagate ST9500325AS 500GB          | 31        | 0.67%   |
| SK hynix NVMe SSD Drive 512GB      | 30        | 0.65%   |
| WDC WD10SPZX-60Z10T0 1TB           | 27        | 0.59%   |
| WDC WD10SPZX-24Z10 1TB             | 27        | 0.59%   |
| Seagate ST2000LM007-1R8174 2TB     | 27        | 0.59%   |
| HGST HTS721010A9E630 1TB           | 27        | 0.59%   |
| WDC WD10JPVX-60JC3T1 1TB           | 26        | 0.56%   |
| Samsung NVMe SSD Drive 256GB       | 26        | 0.56%   |
| Seagate ST1000LM048-2E7172 1TB     | 25        | 0.54%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD   | 24        | 0.52%   |
| WDC WD10SPZX-21Z10T0 1TB           | 24        | 0.52%   |
| HGST HTS545050A7E680 500GB         | 23        | 0.5%    |
| A-DATA SU750 256GB SSD             | 23        | 0.5%    |
| WDC WD10EZEX-08WN4A0 1TB           | 22        | 0.48%   |
| Samsung SSD 860 EVO 250GB          | 22        | 0.48%   |
| HGST HTS545050A7E380 500GB         | 20        | 0.43%   |
| Seagate ST3500418AS 500GB          | 19        | 0.41%   |
| Seagate ST500LT012-9WS142 500GB    | 18        | 0.39%   |
| Samsung SSD 850 EVO 250GB          | 18        | 0.39%   |
| Micron NVMe SSD Drive 512GB        | 18        | 0.39%   |
| Kingston SA400S37120G 120GB SSD    | 18        | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 997       | 1285   | 41.87%  |
| WDC                 | 654       | 793    | 27.47%  |
| Toshiba             | 416       | 458    | 17.47%  |
| HGST                | 151       | 175    | 6.34%   |
| Hitachi             | 97        | 117    | 4.07%   |
| Samsung Electronics | 21        | 24     | 0.88%   |
| Unknown             | 17        | 21     | 0.71%   |
| Fujitsu             | 7         | 7      | 0.29%   |
| Apple               | 6         | 6      | 0.25%   |
| Hewlett-Packard     | 5         | 6      | 0.21%   |
| Maxtor              | 3         | 3      | 0.13%   |
| WD MediaMax         | 1         | 1      | 0.04%   |
| Synology            | 1         | 1      | 0.04%   |
| MARSHAL             | 1         | 1      | 0.04%   |
| Lenovo              | 1         | 1      | 0.04%   |
| KESU                | 1         | 2      | 0.04%   |
| IBM                 | 1         | 1      | 0.04%   |
| ASMedia             | 1         | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 166       | 210    | 17.36%  |
| WDC                 | 144       | 178    | 15.06%  |
| Crucial             | 139       | 182    | 14.54%  |
| Kingston            | 119       | 148    | 12.45%  |
| A-DATA Technology   | 59        | 65     | 6.17%   |
| SanDisk             | 55        | 72     | 5.75%   |
| SK hynix            | 33        | 35     | 3.45%   |
| Micron Technology   | 22        | 29     | 2.3%    |
| China               | 21        | 23     | 2.2%    |
| Intel               | 15        | 16     | 1.57%   |
| Gigabyte Technology | 13        | 14     | 1.36%   |
| Toshiba             | 12        | 13     | 1.26%   |
| LITEON              | 12        | 14     | 1.26%   |
| Hewlett-Packard     | 10        | 15     | 1.05%   |
| FORESEE             | 10        | 11     | 1.05%   |
| Unknown             | 8         | 8      | 0.84%   |
| TO Exter            | 7         | 7      | 0.73%   |
| SPCC                | 7         | 9      | 0.73%   |
| Seagate             | 7         | 7      | 0.73%   |
| Maxtor              | 7         | 18     | 0.73%   |
| Apple               | 7         | 11     | 0.73%   |
| Transcend           | 6         | 7      | 0.63%   |
| Unknown             | 5         | 5      | 0.52%   |
| Lexar               | 5         | 5      | 0.52%   |
| PNY                 | 4         | 6      | 0.42%   |
| Leven               | 4         | 4      | 0.42%   |
| StoreJet            | 3         | 3      | 0.31%   |
| Plextor             | 3         | 3      | 0.31%   |
| LITEONIT            | 3         | 4      | 0.31%   |
| KingSpec            | 3         | 3      | 0.31%   |
| HS-SSD-C100         | 3         | 4      | 0.31%   |
| Team                | 2         | 2      | 0.21%   |
| OCZ                 | 2         | 2      | 0.21%   |
| Netac               | 2         | 2      | 0.21%   |
| KLEVV               | 2         | 3      | 0.21%   |
| KIOXIA-EXCERIA      | 2         | 2      | 0.21%   |
| KingDian            | 2         | 2      | 0.21%   |
| BIWIN               | 2         | 2      | 0.21%   |
| ASMT                | 2         | 2      | 0.21%   |
| Aarvex              | 2         | 2      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2258      | 2903   | 53.6%   |
| NVMe    | 944       | 1211   | 22.41%  |
| SSD     | 902       | 1176   | 21.41%  |
| MMC     | 81        | 106    | 1.92%   |
| Unknown | 28        | 32     | 0.66%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2756      | 3985   | 71.05%  |
| NVMe | 941       | 1203   | 24.26%  |
| SAS  | 101       | 134    | 2.6%    |
| MMC  | 81        | 106    | 2.09%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1658      | 2132   | 51.96%  |
| 0.51-1.0   | 1369      | 1682   | 42.9%   |
| 1.01-2.0   | 116       | 173    | 3.64%   |
| 3.01-4.0   | 31        | 60     | 0.97%   |
| 2.01-3.0   | 8         | 14     | 0.25%   |
| 4.01-10.0  | 8         | 17     | 0.25%   |
| 10.01-20.0 | 1         | 1      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 960       | 26.47%  |
| 101-250        | 915       | 25.23%  |
| 501-1000       | 625       | 17.23%  |
| 51-100         | 343       | 9.46%   |
| 21-50          | 228       | 6.29%   |
| 1001-2000      | 221       | 6.09%   |
| 1-20           | 185       | 5.1%    |
| More than 3000 | 56        | 1.54%   |
| Unknown        | 53        | 1.46%   |
| 2001-3000      | 41        | 1.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1487      | 39.64%  |
| 21-50          | 775       | 20.66%  |
| 101-250        | 491       | 13.09%  |
| 51-100         | 440       | 11.73%  |
| 251-500        | 268       | 7.14%   |
| 501-1000       | 163       | 4.35%   |
| Unknown        | 53        | 1.41%   |
| 1001-2000      | 45        | 1.2%    |
| More than 3000 | 19        | 0.51%   |
| 2001-3000      | 9         | 0.24%   |
| 0              | 1         | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 21        | 22     | 6.91%   |
| HGST HTS541010A9E680 1TB             | 11        | 11     | 3.62%   |
| Toshiba MQ01ABD100 1TB               | 9         | 9      | 2.96%   |
| Seagate ST500LT012-1DG142 500GB      | 9         | 9      | 2.96%   |
| Seagate ST1000LM049-2GH172 1TB       | 9         | 10     | 2.96%   |
| HGST HTS545050A7E680 500GB           | 9         | 11     | 2.96%   |
| Seagate ST500DM002-1BD142 500GB      | 8         | 8      | 2.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 8         | 8      | 2.63%   |
| Seagate ST9500325AS 500GB            | 6         | 6      | 1.97%   |
| Seagate ST500LM021-1KJ152 500GB      | 5         | 5      | 1.64%   |
| WDC WD10EZEX-08WN4A0 1TB             | 4         | 4      | 1.32%   |
| Toshiba MQ04ABF100 1TB               | 4         | 5      | 1.32%   |
| Toshiba MQ01ABF050 500GB             | 4         | 4      | 1.32%   |
| Seagate ST500LT012-9WS142 500GB      | 4         | 4      | 1.32%   |
| Seagate ST3500418AS 500GB            | 4         | 4      | 1.32%   |
| Seagate ST320LT007-9ZV142 320GB      | 4         | 4      | 1.32%   |
| HGST HTS721010A9E630 1TB             | 4         | 4      | 1.32%   |
| HGST HTS545050A7E380 500GB           | 4         | 4      | 1.32%   |
| Seagate ST2000LM007-1R8174 2TB       | 3         | 3      | 0.99%   |
| Seagate ST1000DM003-1ER162 1TB       | 3         | 3      | 0.99%   |
| Hitachi HTS547575A9E384 752GB        | 3         | 3      | 0.99%   |
| HGST HTS725050A7E630 500GB           | 3         | 3      | 0.99%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 2         | 2      | 0.66%   |
| WDC WD5000LPVX-75V0TT0 500GB         | 2         | 2      | 0.66%   |
| WDC WD5000LPVT-22G33T0 500GB         | 2         | 2      | 0.66%   |
| WDC WD5000AAKX-001CA0 500GB          | 2         | 5      | 0.66%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 2         | 2      | 0.66%   |
| WDC WD3200AAJS-00L7A0 320GB          | 2         | 2      | 0.66%   |
| WDC WD10JPVX-60JC3T1 1TB             | 2         | 2      | 0.66%   |
| WDC WD10JPCX-24UE4T0 1TB             | 2         | 2      | 0.66%   |
| Toshiba MQ01ABD050 500GB             | 2         | 2      | 0.66%   |
| Toshiba HDWD110 1TB                  | 2         | 2      | 0.66%   |
| Toshiba DT01ACA100 1TB               | 2         | 2      | 0.66%   |
| SK hynix PC711 HFS512GDE9X073N 512GB | 2         | 2      | 0.66%   |
| Seagate ST9320325AS 320GB            | 2         | 2      | 0.66%   |
| Seagate ST9160314AS 160GB            | 2         | 2      | 0.66%   |
| Seagate ST1000LX015-1U7172-SSHD 1TB  | 2         | 3      | 0.66%   |
| Seagate ST1000LM014-1EJ164 1TB       | 2         | 2      | 0.66%   |
| Seagate ST1000DM010-2EP102 1TB       | 2         | 2      | 0.66%   |
| Seagate ST1000DM003-1CH162 1TB       | 2         | 2      | 0.66%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 118       | 127    | 39.6%   |
| WDC                 | 54        | 63     | 18.12%  |
| HGST                | 34        | 36     | 11.41%  |
| Toshiba             | 30        | 32     | 10.07%  |
| Hitachi             | 23        | 26     | 7.72%   |
| SK hynix            | 8         | 9      | 2.68%   |
| Samsung Electronics | 7         | 8      | 2.35%   |
| SanDisk             | 6         | 6      | 2.01%   |
| Crucial             | 4         | 5      | 1.34%   |
| A-DATA Technology   | 3         | 3      | 1.01%   |
| Apple               | 2         | 2      | 0.67%   |
| YS                  | 1         | 1      | 0.34%   |
| Unknown             | 1         | 1      | 0.34%   |
| Micron Technology   | 1         | 1      | 0.34%   |
| MARSHAL             | 1         | 1      | 0.34%   |
| LITEON              | 1         | 1      | 0.34%   |
| Leven               | 1         | 1      | 0.34%   |
| Lenovo              | 1         | 2      | 0.34%   |
| Innodisk            | 1         | 1      | 0.34%   |
| IBM                 | 1         | 1      | 0.34%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 118       | 127    | 44.87%  |
| WDC                 | 50        | 59     | 19.01%  |
| HGST                | 34        | 36     | 12.93%  |
| Toshiba             | 30        | 32     | 11.41%  |
| Hitachi             | 23        | 26     | 8.75%   |
| Samsung Electronics | 4         | 5      | 1.52%   |
| Apple               | 2         | 2      | 0.76%   |
| MARSHAL             | 1         | 1      | 0.38%   |
| IBM                 | 1         | 1      | 0.38%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 262       | 289    | 88.22%  |
| SSD  | 23        | 24     | 7.74%   |
| NVMe | 12        | 14     | 4.04%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD10SPZX-21Z10T0 1TB            | 1         | 1      | 16.67%  |
| Seagate ST500LT012-1DG142 500GB     | 1         | 1      | 16.67%  |
| Seagate ST3320418AS 320GB           | 1         | 1      | 16.67%  |
| Seagate ST1000LM 024 HN-M101MBB 1TB | 1         | 1      | 16.67%  |
| Samsung Electronics SSD 980 500GB   | 1         | 2      | 16.67%  |
| Apple HDD HTS545050A7E362 500GB     | 1         | 1      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 50%     |
| WDC                 | 1         | 1      | 16.67%  |
| Samsung Electronics | 1         | 2      | 16.67%  |
| Apple               | 1         | 1      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2206      | 3384   | 60.21%  |
| Works    | 1159      | 1710   | 31.63%  |
| Malfunc  | 293       | 327    | 8%      |
| Failed   | 6         | 7      | 0.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2651      | 64.47%  |
| AMD                              | 536       | 13.04%  |
| Samsung Electronics              | 229       | 5.57%   |
| SanDisk                          | 198       | 4.82%   |
| SK hynix                         | 109       | 2.65%   |
| Kingston Technology Company      | 58        | 1.41%   |
| Toshiba America Info Systems     | 56        | 1.36%   |
| Micron Technology                | 52        | 1.26%   |
| KIOXIA                           | 50        | 1.22%   |
| Micron/Crucial Technology        | 28        | 0.68%   |
| Union Memory (Shenzhen)          | 20        | 0.49%   |
| Phison Electronics               | 19        | 0.46%   |
| Silicon Motion                   | 17        | 0.41%   |
| ASMedia Technology               | 16        | 0.39%   |
| Nvidia                           | 15        | 0.36%   |
| Realtek Semiconductor            | 8         | 0.19%   |
| JMicron Technology               | 8         | 0.19%   |
| ADATA Technology                 | 7         | 0.17%   |
| Marvell Technology Group         | 6         | 0.15%   |
| Solid State Storage Technology   | 4         | 0.1%    |
| Silicon Integrated Systems [SiS] | 4         | 0.1%    |
| Lite-On Technology               | 4         | 0.1%    |
| Yangtze Memory Technologies      | 3         | 0.07%   |
| LSI Logic / Symbios Logic        | 3         | 0.07%   |
| Lenovo                           | 3         | 0.07%   |
| Broadcom / LSI                   | 3         | 0.07%   |
| VIA Technologies                 | 2         | 0.05%   |
| Shenzhen Longsys Electronics     | 1         | 0.02%   |
| Integrated Technology Express    | 1         | 0.02%   |
| Apple                            | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 459       | 9.96%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 408       | 8.85%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 273       | 5.92%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 169       | 3.67%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 155       | 3.36%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 127       | 2.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 113       | 2.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 110       | 2.39%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 102       | 2.21%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 100       | 2.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 99        | 2.15%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 97        | 2.11%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 94        | 2.04%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 92        | 2%      |
| Samsung NVMe SSD Controller 980                                                         | 85        | 1.84%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 83        | 1.8%    |
| Intel SSD 660P Series                                                                   | 82        | 1.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 63        | 1.37%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 60        | 1.3%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 57        | 1.24%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 54        | 1.17%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 53        | 1.15%   |
| Micron Non-Volatile memory controller                                                   | 52        | 1.13%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 48        | 1.04%   |
| AMD 400 Series Chipset SATA Controller                                                  | 46        | 1%      |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 45        | 0.98%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 43        | 0.93%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 40        | 0.87%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 40        | 0.87%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 38        | 0.82%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 37        | 0.8%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 36        | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 36        | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 36        | 0.78%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 34        | 0.74%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 34        | 0.74%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 32        | 0.69%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 31        | 0.67%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 31        | 0.67%   |
| SK hynix Gold P31 SSD                                                                   | 30        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2562      | 60.32%  |
| NVMe | 950       | 22.37%  |
| RAID | 401       | 9.44%   |
| IDE  | 330       | 7.77%   |
| SAS  | 2         | 0.05%   |
| SCSI | 2         | 0.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 2817      | 81.06%  |
| AMD          | 639       | 18.39%  |
| ARM          | 18        | 0.52%   |
| CentaurHauls | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 170       | 4.89%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 104       | 2.99%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 78        | 2.24%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 72        | 2.07%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 71        | 2.04%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 67        | 1.93%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 45        | 1.29%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 44        | 1.27%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 43        | 1.24%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 43        | 1.24%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 41        | 1.18%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 41        | 1.18%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 40        | 1.15%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 39        | 1.12%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 34        | 0.98%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 34        | 0.98%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 32        | 0.92%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 31        | 0.89%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 30        | 0.86%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 30        | 0.86%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 30        | 0.86%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 29        | 0.83%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 27        | 0.78%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 26        | 0.75%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 25        | 0.72%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 25        | 0.72%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 25        | 0.72%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 24        | 0.69%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 23        | 0.66%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 22        | 0.63%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 21        | 0.6%    |
| Intel Core i3-7100U CPU @ 2.40GHz             | 21        | 0.6%    |
| Intel Core i3-2350M CPU @ 2.30GHz             | 20        | 0.58%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 20        | 0.58%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 19        | 0.55%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 18        | 0.52%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 18        | 0.52%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 18        | 0.52%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 18        | 0.52%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 18        | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1109      | 31.9%   |
| Intel Core i3           | 613       | 17.64%  |
| Intel Core i7           | 450       | 12.95%  |
| AMD Ryzen 5             | 241       | 6.93%   |
| Other                   | 209       | 6.01%   |
| Intel Pentium           | 118       | 3.39%   |
| Intel Core 2 Duo        | 109       | 3.14%   |
| AMD Ryzen 7             | 90        | 2.59%   |
| Intel Celeron           | 66        | 1.9%    |
| Intel Pentium Dual-Core | 55        | 1.58%   |
| AMD Ryzen 3             | 49        | 1.41%   |
| AMD A6                  | 38        | 1.09%   |
| AMD A8                  | 30        | 0.86%   |
| AMD A4                  | 29        | 0.83%   |
| Intel Atom              | 26        | 0.75%   |
| AMD FX                  | 21        | 0.6%    |
| AMD Ryzen 9             | 20        | 0.58%   |
| Intel Xeon              | 19        | 0.55%   |
| Intel Pentium Dual      | 17        | 0.49%   |
| Intel Core 2            | 17        | 0.49%   |
| AMD A10                 | 15        | 0.43%   |
| Intel Core 2 Quad       | 13        | 0.37%   |
| AMD E1                  | 11        | 0.32%   |
| Intel Pentium Silver    | 8         | 0.23%   |
| Intel Core i9           | 8         | 0.23%   |
| Intel Pentium Gold      | 7         | 0.2%    |
| AMD Athlon II X2        | 7         | 0.2%    |
| AMD Ryzen 5 PRO         | 6         | 0.17%   |
| AMD E2                  | 6         | 0.17%   |
| AMD E                   | 6         | 0.17%   |
| Intel Pentium 4         | 5         | 0.14%   |
| ARM BCM                 | 5         | 0.14%   |
| AMD Ryzen 7 PRO         | 5         | 0.14%   |
| AMD Phenom II X4        | 4         | 0.12%   |
| AMD Phenom II X2        | 4         | 0.12%   |
| AMD Athlon              | 4         | 0.12%   |
| Intel Xeon Silver       | 3         | 0.09%   |
| Intel Pentium D         | 3         | 0.09%   |
| Intel Genuine           | 3         | 0.09%   |
| AMD Sempron             | 3         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1688      | 48.53%  |
| 4      | 1281      | 36.83%  |
| 6      | 297       | 8.54%   |
| 8      | 135       | 3.88%   |
| 1      | 42        | 1.21%   |
| 12     | 12        | 0.35%   |
| 3      | 7         | 0.2%    |
| 16     | 4         | 0.12%   |
| 14     | 3         | 0.09%   |
| 10     | 3         | 0.09%   |
| 32     | 2         | 0.06%   |
| 24     | 2         | 0.06%   |
| 36     | 1         | 0.03%   |
| 20     | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 3461      | 99.6%   |
| 2      | 14        | 0.4%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 2623      | 75.48%  |
| 1      | 852       | 24.52%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3421      | 98.36%  |
| Unknown        | 51        | 1.47%   |
| 32-bit         | 5         | 0.14%   |
| 64-bit         | 1         | 0.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 615       | 17.28%  |
| 0x806ea    | 216       | 6.07%   |
| 0x306a9    | 201       | 5.65%   |
| 0x806ec    | 200       | 5.62%   |
| 0x206a7    | 191       | 5.37%   |
| 0x906ea    | 136       | 3.82%   |
| 0x806e9    | 136       | 3.82%   |
| 0x40651    | 136       | 3.82%   |
| 0x406e3    | 127       | 3.57%   |
| 0x806c1    | 114       | 3.2%    |
| 0x1067a    | 113       | 3.18%   |
| 0x306d4    | 96        | 2.7%    |
| 0x306c3    | 96        | 2.7%    |
| 0x706e5    | 65        | 1.83%   |
| 0x08108109 | 59        | 1.66%   |
| 0x906e9    | 57        | 1.6%    |
| 0x20655    | 57        | 1.6%    |
| 0x806eb    | 54        | 1.52%   |
| 0x506e3    | 47        | 1.32%   |
| 0x08108102 | 44        | 1.24%   |
| 0x0a50000c | 36        | 1.01%   |
| 0x06006705 | 35        | 0.98%   |
| 0x6fd      | 34        | 0.96%   |
| 0xa0652    | 31        | 0.87%   |
| 0x07030105 | 29        | 0.81%   |
| 0x20652    | 27        | 0.76%   |
| 0xa0655    | 26        | 0.73%   |
| 0x08600104 | 26        | 0.73%   |
| 0x08701021 | 24        | 0.67%   |
| 0x08600106 | 23        | 0.65%   |
| 0x0810100b | 23        | 0.65%   |
| 0x906ed    | 21        | 0.59%   |
| 0x30678    | 21        | 0.59%   |
| 0x08101007 | 18        | 0.51%   |
| 0x06001119 | 18        | 0.51%   |
| 0x010000c8 | 17        | 0.48%   |
| 0x10676    | 15        | 0.42%   |
| 0x706a1    | 14        | 0.39%   |
| 0x08608103 | 14        | 0.39%   |
| 0x506c9    | 13        | 0.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 971       | 27.93%  |
| Haswell          | 277       | 7.97%   |
| IvyBridge        | 235       | 6.76%   |
| SandyBridge      | 224       | 6.44%   |
| Skylake          | 214       | 6.16%   |
| Penryn           | 149       | 4.29%   |
| Zen+             | 139       | 4%      |
| TigerLake        | 134       | 3.86%   |
| Zen 2            | 127       | 3.65%   |
| Broadwell        | 119       | 3.42%   |
| Westmere         | 99        | 2.85%   |
| Icelake          | 89        | 2.56%   |
| CometLake        | 82        | 2.36%   |
| Excavator        | 73        | 2.1%    |
| Zen              | 71        | 2.04%   |
| Core             | 70        | 2.01%   |
| Silvermont       | 58        | 1.67%   |
| Unknown          | 57        | 1.64%   |
| Zen 3            | 52        | 1.5%    |
| Puma             | 47        | 1.35%   |
| Piledriver       | 40        | 1.15%   |
| Goldmont plus    | 23        | 0.66%   |
| K10              | 20        | 0.58%   |
| Goldmont         | 19        | 0.55%   |
| Nehalem          | 14        | 0.4%    |
| K10 Llano        | 13        | 0.37%   |
| Bonnell          | 11        | 0.32%   |
| Bobcat           | 11        | 0.32%   |
| NetBurst         | 9         | 0.26%   |
| Alderlake Hybrid | 9         | 0.26%   |
| Jaguar           | 5         | 0.14%   |
| Bulldozer        | 5         | 0.14%   |
| Steamroller      | 4         | 0.12%   |
| P6               | 3         | 0.09%   |
| K8 Hammer        | 3         | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2563      | 57.79%  |
| Nvidia                           | 1004      | 22.64%  |
| AMD                              | 857       | 19.32%  |
| Silicon Integrated Systems [SiS] | 4         | 0.09%   |
| Matrox Electronics Systems       | 3         | 0.07%   |
| ASPEED Technology                | 2         | 0.05%   |
| VIA Technologies                 | 1         | 0.02%   |
| ATI Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                | 230       | 5.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 195       | 4.31%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 160       | 3.54%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 157       | 3.47%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 152       | 3.36%   |
| Intel HD Graphics 620                                                                 | 145       | 3.2%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 137       | 3.03%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 131       | 2.9%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 131       | 2.9%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 121       | 2.67%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 115       | 2.54%   |
| Intel HD Graphics 5500                                                                | 105       | 2.32%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 98        | 2.17%   |
| AMD Renoir                                                                            | 83        | 1.83%   |
| Intel Core Processor Integrated Graphics Controller                                   | 72        | 1.59%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 64        | 1.41%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 61        | 1.35%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 60        | 1.33%   |
| Nvidia GK208B [GeForce GT 710]                                                        | 57        | 1.26%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 56        | 1.24%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                      | 54        | 1.19%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                 | 54        | 1.19%   |
| Intel HD Graphics 630                                                                 | 52        | 1.15%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 51        | 1.13%   |
| Nvidia TU117M                                                                         | 49        | 1.08%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 45        | 0.99%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 45        | 0.99%   |
| Nvidia GP108M [GeForce MX250]                                                         | 43        | 0.95%   |
| AMD Cezanne                                                                           | 43        | 0.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 41        | 0.91%   |
| Nvidia GP108M [GeForce MX150]                                                         | 40        | 0.88%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 37        | 0.82%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 34        | 0.75%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                             | 34        | 0.75%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 34        | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 33        | 0.73%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                | 33        | 0.73%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                   | 33        | 0.73%   |
| Nvidia GM108M [GeForce MX130]                                                         | 32        | 0.71%   |
| Intel HD Graphics 530                                                                 | 32        | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 1692      | 48.47%  |
| Intel + Nvidia     | 606       | 17.36%  |
| 1 x AMD            | 445       | 12.75%  |
| 1 x Nvidia         | 293       | 8.39%   |
| Intel + AMD        | 254       | 7.28%   |
| AMD + Nvidia       | 101       | 2.89%   |
| 2 x AMD            | 62        | 1.78%   |
| Other              | 24        | 0.69%   |
| 1 x SiS            | 4         | 0.11%   |
| 2 x Nvidia         | 3         | 0.09%   |
| 1 x Matrox         | 3         | 0.09%   |
| 1 x VIA            | 1         | 0.03%   |
| Nvidia + ASPEED    | 1         | 0.03%   |
| Intel + 2 x Nvidia | 1         | 0.03%   |
| 1 x ASPEED         | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2856      | 81.16%  |
| Proprietary | 548       | 15.57%  |
| Unknown     | 115       | 3.27%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2110      | 59.15%  |
| 1.01-2.0   | 595       | 16.68%  |
| 0.01-0.5   | 306       | 8.58%   |
| 3.01-4.0   | 276       | 7.74%   |
| 0.51-1.0   | 178       | 4.99%   |
| 5.01-6.0   | 53        | 1.49%   |
| 7.01-8.0   | 33        | 0.93%   |
| 8.01-16.0  | 9         | 0.25%   |
| 16.01-24.0 | 4         | 0.11%   |
| 2.01-3.0   | 3         | 0.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 569       | 15.97%  |
| AU Optronics            | 564       | 15.83%  |
| Chimei Innolux          | 526       | 14.76%  |
| LG Display              | 443       | 12.43%  |
| Samsung Electronics     | 295       | 8.28%   |
| Dell                    | 206       | 5.78%   |
| Goldstar                | 147       | 4.13%   |
| BenQ                    | 110       | 3.09%   |
| Acer                    | 94        | 2.64%   |
| PANDA                   | 84        | 2.36%   |
| Hewlett-Packard         | 65        | 1.82%   |
| Lenovo                  | 50        | 1.4%    |
| AOC                     | 49        | 1.38%   |
| Sharp                   | 41        | 1.15%   |
| Chi Mei Optoelectronics | 35        | 0.98%   |
| InfoVision              | 30        | 0.84%   |
| ViewSonic               | 23        | 0.65%   |
| Sony                    | 21        | 0.59%   |
| HCL                     | 19        | 0.53%   |
| Apple                   | 17        | 0.48%   |
| Philips                 | 14        | 0.39%   |
| Unknown                 | 12        | 0.34%   |
| LG Electronics          | 11        | 0.31%   |
| TMX                     | 7         | 0.2%    |
| ASUSTek Computer        | 7         | 0.2%    |
| STD                     | 6         | 0.17%   |
| InnoLux Display         | 6         | 0.17%   |
| Ancor Communications    | 6         | 0.17%   |
| Toshiba                 | 5         | 0.14%   |
| Panasonic               | 5         | 0.14%   |
| LG Philips              | 5         | 0.14%   |
| AOpen                   | 4         | 0.11%   |
| Xiaomi                  | 3         | 0.08%   |
| LGD                     | 3         | 0.08%   |
| Gigabyte Technology     | 3         | 0.08%   |
| CPT                     | 3         | 0.08%   |
| ___                     | 2         | 0.06%   |
| STA                     | 2         | 0.06%   |
| SGT                     | 2         | 0.06%   |
| RTK                     | 2         | 0.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 71        | 1.97%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 63        | 1.75%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 37        | 1.03%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 37        | 1.03%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                | 33        | 0.92%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 32        | 0.89%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 30        | 0.83%   |
| Dell D1918H DEL2005 1366x768 410x230mm 18.5-inch                     | 29        | 0.81%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 27        | 0.75%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch        | 26        | 0.72%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch       | 25        | 0.69%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 25        | 0.69%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch | 24        | 0.67%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 22        | 0.61%   |
| BenQ GW2283 BNQ78E9 1920x1080 476x268mm 21.5-inch                    | 22        | 0.61%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 21        | 0.58%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch          | 19        | 0.53%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 19        | 0.53%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 19        | 0.53%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 19        | 0.53%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 19        | 0.53%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch        | 19        | 0.53%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 17        | 0.47%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch              | 16        | 0.44%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                | 16        | 0.44%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                | 16        | 0.44%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch          | 15        | 0.42%   |
| BOE LCD Monitor BOE07BD 1920x1080 309x174mm 14.0-inch                | 15        | 0.42%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                    | 15        | 0.42%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch         | 14        | 0.39%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch              | 13        | 0.36%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 13        | 0.36%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 13        | 0.36%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 13        | 0.36%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 13        | 0.36%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 13        | 0.36%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 12        | 0.33%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch     | 12        | 0.33%   |
| BOE LCD Monitor BOE07F1 1920x1080 344x193mm 15.5-inch                | 12        | 0.33%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                | 12        | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1667      | 48%     |
| 1366x768 (WXGA)    | 1299      | 37.4%   |
| 1600x900 (HD+)     | 112       | 3.22%   |
| 3840x2160 (4K)     | 77        | 2.22%   |
| 1440x900 (WXGA+)   | 49        | 1.41%   |
| 2560x1440 (QHD)    | 42        | 1.21%   |
| 1280x800 (WXGA)    | 36        | 1.04%   |
| 1920x1200 (WUXGA)  | 26        | 0.75%   |
| 1280x1024 (SXGA)   | 26        | 0.75%   |
| 1360x768           | 24        | 0.69%   |
| 2560x1080          | 17        | 0.49%   |
| Unknown            | 15        | 0.43%   |
| 2560x1600          | 12        | 0.35%   |
| 1680x1050 (WSXGA+) | 10        | 0.29%   |
| 3840x1080          | 9         | 0.26%   |
| 1024x768 (XGA)     | 8         | 0.23%   |
| 1024x600           | 7         | 0.2%    |
| 1280x720 (HD)      | 5         | 0.14%   |
| 3200x2000          | 4         | 0.12%   |
| 2160x1440          | 3         | 0.09%   |
| 3456x2160          | 2         | 0.06%   |
| 2256x1504          | 2         | 0.06%   |
| 1152x864           | 2         | 0.06%   |
| 8160x4627          | 1         | 0.03%   |
| 6400x2160          | 1         | 0.03%   |
| 5760x2160          | 1         | 0.03%   |
| 4480x1080          | 1         | 0.03%   |
| 3840x2400          | 1         | 0.03%   |
| 3840x1100          | 1         | 0.03%   |
| 3440x1440          | 1         | 0.03%   |
| 3286x1080          | 1         | 0.03%   |
| 3200x900           | 1         | 0.03%   |
| 3072x1920          | 1         | 0.03%   |
| 3000x2000          | 1         | 0.03%   |
| 2880x1800          | 1         | 0.03%   |
| 2736x1824          | 1         | 0.03%   |
| 2732x768           | 1         | 0.03%   |
| 2288x1287          | 1         | 0.03%   |
| 2240x1400          | 1         | 0.03%   |
| 1920x1280          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1571      | 44.13%  |
| 13      | 472       | 13.26%  |
| 14      | 418       | 11.74%  |
| 21      | 214       | 6.01%   |
| 18      | 195       | 5.48%   |
| 24      | 104       | 2.92%   |
| Unknown | 88        | 2.47%   |
| 19      | 86        | 2.42%   |
| 23      | 74        | 2.08%   |
| 27      | 64        | 1.8%    |
| 20      | 46        | 1.29%   |
| 12      | 42        | 1.18%   |
| 17      | 40        | 1.12%   |
| 31      | 23        | 0.65%   |
| 34      | 15        | 0.42%   |
| 11      | 14        | 0.39%   |
| 16      | 12        | 0.34%   |
| 72      | 11        | 0.31%   |
| 10      | 10        | 0.28%   |
| 40      | 9         | 0.25%   |
| 26      | 8         | 0.22%   |
| 22      | 7         | 0.2%    |
| 32      | 6         | 0.17%   |
| 84      | 5         | 0.14%   |
| 46      | 5         | 0.14%   |
| 65      | 4         | 0.11%   |
| 25      | 4         | 0.11%   |
| 54      | 3         | 0.08%   |
| 42      | 3         | 0.08%   |
| 39      | 3         | 0.08%   |
| 52      | 2         | 0.06%   |
| 142     | 1         | 0.03%   |
| 48      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2335      | 65.81%  |
| 401-500        | 539       | 15.19%  |
| 501-600        | 236       | 6.65%   |
| 201-300        | 180       | 5.07%   |
| Unknown        | 88        | 2.48%   |
| 351-400        | 70        | 1.97%   |
| 601-700        | 32        | 0.9%    |
| 701-800        | 21        | 0.59%   |
| 1501-2000      | 16        | 0.45%   |
| 1001-1500      | 15        | 0.42%   |
| 801-900        | 12        | 0.34%   |
| 901-1000       | 3         | 0.08%   |
| More than 2000 | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3053      | 90.89%  |
| 16/10   | 144       | 4.29%   |
| Unknown | 85        | 2.53%   |
| 4/3     | 24        | 0.71%   |
| 5/4     | 19        | 0.57%   |
| 21/9    | 15        | 0.45%   |
| 3/2     | 10        | 0.3%    |
| 6/5     | 6         | 0.18%   |
| 32/9    | 1         | 0.03%   |
| 3.40    | 1         | 0.03%   |
| 1.00    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1554      | 43.66%  |
| 81-90          | 796       | 22.37%  |
| 201-250        | 345       | 9.69%   |
| 141-150        | 202       | 5.68%   |
| 151-200        | 168       | 4.72%   |
| 71-80          | 95        | 2.67%   |
| Unknown        | 88        | 2.47%   |
| 301-350        | 68        | 1.91%   |
| 351-500        | 44        | 1.24%   |
| 61-70          | 35        | 0.98%   |
| 251-300        | 27        | 0.76%   |
| 121-130        | 27        | 0.76%   |
| More than 1000 | 26        | 0.73%   |
| 501-1000       | 21        | 0.59%   |
| 51-60          | 15        | 0.42%   |
| 111-120        | 15        | 0.42%   |
| 91-100         | 15        | 0.42%   |
| 41-50          | 10        | 0.28%   |
| 131-140        | 8         | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 1291      | 36.7%   |
| 101-120       | 1245      | 35.39%  |
| 51-100        | 719       | 20.44%  |
| 161-240       | 118       | 3.35%   |
| Unknown       | 88        | 2.5%    |
| 1-50          | 31        | 0.88%   |
| More than 240 | 26        | 0.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3147      | 89.45%  |
| 2     | 257       | 7.31%   |
| 0     | 106       | 3.01%   |
| 3     | 8         | 0.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2366      | 42.73%  |
| Intel                             | 1391      | 25.12%  |
| Qualcomm Atheros                  | 724       | 13.08%  |
| Broadcom                          | 249       | 4.5%    |
| Ralink Technology                 | 115       | 2.08%   |
| Xiaomi                            | 92        | 1.66%   |
| TP-Link                           | 73        | 1.32%   |
| Ralink                            | 57        | 1.03%   |
| MediaTek                          | 53        | 0.96%   |
| Samsung Electronics               | 43        | 0.78%   |
| OPPO Electronics                  | 43        | 0.78%   |
| Broadcom Limited                  | 43        | 0.78%   |
| Marvell Technology Group          | 29        | 0.52%   |
| D-Link                            | 28        | 0.51%   |
| Qualcomm                          | 26        | 0.47%   |
| Huawei Technologies               | 22        | 0.4%    |
| OnePlus Technology (Shenzhen)     | 20        | 0.36%   |
| Foxconn / Hon Hai                 | 15        | 0.27%   |
| Motorola PCS                      | 14        | 0.25%   |
| Qualcomm Atheros Communications   | 12        | 0.22%   |
| Nvidia                            | 11        | 0.2%    |
| ASIX Electronics                  | 11        | 0.2%    |
| ICS Advent                        | 7         | 0.13%   |
| vivo                              | 6         | 0.11%   |
| NetGear                           | 6         | 0.11%   |
| Lenovo                            | 6         | 0.11%   |
| Google                            | 6         | 0.11%   |
| Edimax Technology                 | 6         | 0.11%   |
| NTmore                            | 5         | 0.09%   |
| JMicron Technology                | 5         | 0.09%   |
| HMD Global                        | 5         | 0.09%   |
| Microchip Technology              | 4         | 0.07%   |
| DisplayLink                       | 4         | 0.07%   |
| D-Link System                     | 4         | 0.07%   |
| ASUSTek Computer                  | 4         | 0.07%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.04%   |
| Spreadtrum Communications         | 2         | 0.04%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.04%   |
| Sierra Wireless                   | 2         | 0.04%   |
| Ericsson Business Mobile Networks | 2         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1553      | 24.12%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 578       | 8.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 256       | 3.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 124       | 1.93%   |
| Intel Wi-Fi 6 AX200                                               | 123       | 1.91%   |
| Intel Wireless 8265 / 8275                                        | 114       | 1.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 109       | 1.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 104       | 1.62%   |
| Ralink MT7601U Wireless Adapter                                   | 102       | 1.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 100       | 1.55%   |
| Intel Wi-Fi 6 AX201                                               | 100       | 1.55%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 90        | 1.4%    |
| Broadcom BCM43142 802.11b/g/n                                     | 90        | 1.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 87        | 1.35%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 86        | 1.34%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 86        | 1.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 77        | 1.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 73        | 1.13%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 71        | 1.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 71        | 1.1%    |
| Intel Wireless 3165                                               | 70        | 1.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 70        | 1.09%   |
| Intel Wireless 7265                                               | 69        | 1.07%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 66        | 1.03%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 65        | 1.01%   |
| Intel Wireless 3160                                               | 57        | 0.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 57        | 0.89%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 54        | 0.84%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 43        | 0.67%   |
| OPPO RMX2117                                                      | 43        | 0.67%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 41        | 0.64%   |
| Intel Wireless 8260                                               | 35        | 0.54%   |
| Intel Ethernet Connection (4) I219-V                              | 34        | 0.53%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 34        | 0.53%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 33        | 0.51%   |
| Intel Wireless 7260                                               | 32        | 0.5%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 31        | 0.48%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 30        | 0.47%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 30        | 0.47%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 27        | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1202      | 38.32%  |
| Realtek Semiconductor             | 714       | 22.76%  |
| Qualcomm Atheros                  | 640       | 20.4%   |
| Broadcom                          | 207       | 6.6%    |
| Ralink Technology                 | 115       | 3.67%   |
| TP-Link                           | 67        | 2.14%   |
| Ralink                            | 56        | 1.79%   |
| MediaTek                          | 37        | 1.18%   |
| Broadcom Limited                  | 34        | 1.08%   |
| D-Link                            | 28        | 0.89%   |
| Qualcomm Atheros Communications   | 12        | 0.38%   |
| NetGear                           | 6         | 0.19%   |
| Edimax Technology                 | 6         | 0.19%   |
| Sierra Wireless                   | 2         | 0.06%   |
| Dell                              | 2         | 0.06%   |
| D-Link System                     | 2         | 0.06%   |
| Wacom                             | 1         | 0.03%   |
| Qualcomm                          | 1         | 0.03%   |
| Micro Star International          | 1         | 0.03%   |
| Marvell Technology Group          | 1         | 0.03%   |
| IMC Networks                      | 1         | 0.03%   |
| Ericsson Business Mobile Networks | 1         | 0.03%   |
| ASUSTek Computer                  | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 256       | 8.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 124       | 3.93%   |
| Intel Wi-Fi 6 AX200                                            | 123       | 3.9%    |
| Intel Wireless 8265 / 8275                                     | 114       | 3.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 109       | 3.46%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 104       | 3.3%    |
| Ralink MT7601U Wireless Adapter                                | 102       | 3.24%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 100       | 3.17%   |
| Intel Wi-Fi 6 AX201                                            | 100       | 3.17%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 90        | 2.86%   |
| Broadcom BCM43142 802.11b/g/n                                  | 90        | 2.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 87        | 2.76%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 86        | 2.73%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 86        | 2.73%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 77        | 2.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 73        | 2.32%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 71        | 2.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 71        | 2.25%   |
| Intel Wireless 3165                                            | 70        | 2.22%   |
| Intel Wireless 7265                                            | 69        | 2.19%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 66        | 2.09%   |
| Intel Wireless 3160                                            | 57        | 1.81%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 57        | 1.81%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 54        | 1.71%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 43        | 1.36%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 41        | 1.3%    |
| Intel Wireless 8260                                            | 35        | 1.11%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 34        | 1.08%   |
| Intel Wireless 7260                                            | 32        | 1.02%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 31        | 0.98%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 30        | 0.95%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 30        | 0.95%   |
| Intel Wireless-AC 9260                                         | 26        | 0.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 26        | 0.82%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 23        | 0.73%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 22        | 0.7%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 17        | 0.54%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 17        | 0.54%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 16        | 0.51%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 15        | 0.48%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2183      | 68.01%  |
| Intel                            | 448       | 13.96%  |
| Qualcomm Atheros                 | 124       | 3.86%   |
| Xiaomi                           | 92        | 2.87%   |
| Broadcom                         | 60        | 1.87%   |
| Samsung Electronics              | 43        | 1.34%   |
| OPPO Electronics                 | 43        | 1.34%   |
| Marvell Technology Group         | 28        | 0.87%   |
| Qualcomm                         | 25        | 0.78%   |
| Huawei Technologies              | 19        | 0.59%   |
| MediaTek                         | 17        | 0.53%   |
| OnePlus Technology (Shenzhen)    | 15        | 0.47%   |
| ASIX Electronics                 | 11        | 0.34%   |
| Nvidia                           | 10        | 0.31%   |
| Motorola PCS                     | 9         | 0.28%   |
| Broadcom Limited                 | 9         | 0.28%   |
| ICS Advent                       | 7         | 0.22%   |
| TP-Link                          | 6         | 0.19%   |
| Google                           | 6         | 0.19%   |
| vivo                             | 5         | 0.16%   |
| NTmore                           | 5         | 0.16%   |
| JMicron Technology               | 5         | 0.16%   |
| HMD Global                       | 5         | 0.16%   |
| Lenovo                           | 4         | 0.12%   |
| Foxconn / Hon Hai                | 4         | 0.12%   |
| DisplayLink                      | 4         | 0.12%   |
| Microchip Technology             | 3         | 0.09%   |
| ASUSTek Computer                 | 3         | 0.09%   |
| Spreadtrum Communications        | 2         | 0.06%   |
| Silicon Integrated Systems [SiS] | 2         | 0.06%   |
| D-Link System                    | 2         | 0.06%   |
| Attansic Technology              | 2         | 0.06%   |
| Aquantia                         | 2         | 0.06%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.03%   |
| VIA Technologies                 | 1         | 0.03%   |
| Standard Microsystems            | 1         | 0.03%   |
| LG Electronics                   | 1         | 0.03%   |
| Davicom Semiconductor            | 1         | 0.03%   |
| Apple                            | 1         | 0.03%   |
| Android                          | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1553      | 47.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 578       | 17.81%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 70        | 2.16%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 65        | 2%      |
| OPPO RMX2117                                                      | 43        | 1.33%   |
| Intel Ethernet Connection (4) I219-V                              | 34        | 1.05%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 33        | 1.02%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 27        | 0.83%   |
| Intel 82579V Gigabit Network Connection                           | 26        | 0.8%    |
| Intel Ethernet Connection I217-LM                                 | 24        | 0.74%   |
| Intel Ethernet Connection (2) I219-V                              | 23        | 0.71%   |
| Qualcomm Mobile Router                                            | 22        | 0.68%   |
| Intel I211 Gigabit Network Connection                             | 21        | 0.65%   |
| Intel Ethernet Connection I218-LM                                 | 21        | 0.65%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 20        | 0.62%   |
| Intel Ethernet Connection I219-LM                                 | 20        | 0.62%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 19        | 0.59%   |
| Realtek RTL8125 2.5GbE Controller                                 | 18        | 0.55%   |
| Intel Ethernet Connection (3) I218-LM                             | 17        | 0.52%   |
| Intel Ethernet Connection (4) I219-LM                             | 16        | 0.49%   |
| OnePlus (Shenzhen) OnePlus                                        | 15        | 0.46%   |
| Intel Ethernet Connection (7) I219-V                              | 15        | 0.46%   |
| Intel Ethernet Connection (10) I219-V                             | 15        | 0.46%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 14        | 0.43%   |
| Intel Ethernet Connection (6) I219-V                              | 14        | 0.43%   |
| Intel 82577LM Gigabit Network Connection                          | 14        | 0.43%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 13        | 0.4%    |
| MediaTek Nokia 5.1 Plus                                           | 13        | 0.4%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 12        | 0.37%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 12        | 0.37%   |
| Intel Ethernet Connection (2) I219-LM                             | 12        | 0.37%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 12        | 0.37%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 11        | 0.34%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 11        | 0.34%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 11        | 0.34%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 10        | 0.31%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 10        | 0.31%   |
| Intel Ethernet Connection (7) I219-LM                             | 10        | 0.31%   |
| Intel Ethernet Connection (6) I219-LM                             | 10        | 0.31%   |
| Huawei E353/E3131                                                 | 10        | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3028      | 50.62%  |
| Ethernet | 2912      | 48.68%  |
| Unknown  | 29        | 0.48%   |
| Modem    | 13        | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2502      | 72.86%  |
| Ethernet | 926       | 26.97%  |
| Unknown  | 5         | 0.15%   |
| Modem    | 1         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2142      | 61.52%  |
| 1     | 1251      | 35.93%  |
| 0     | 57        | 1.64%   |
| 3     | 26        | 0.75%   |
| 4     | 5         | 0.14%   |
| 6     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3007      | 85.57%  |
| Yes  | 507       | 14.43%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1040      | 40.93%  |
| Realtek Semiconductor           | 410       | 16.14%  |
| Qualcomm Atheros Communications | 390       | 15.35%  |
| Broadcom                        | 138       | 5.43%   |
| IMC Networks                    | 115       | 4.53%   |
| Cambridge Silicon Radio         | 108       | 4.25%   |
| Lite-On Technology              | 102       | 4.01%   |
| Foxconn / Hon Hai               | 73        | 2.87%   |
| Ralink                          | 43        | 1.69%   |
| Dell                            | 29        | 1.14%   |
| Apple                           | 23        | 0.91%   |
| Hewlett-Packard                 | 14        | 0.55%   |
| Foxconn International           | 10        | 0.39%   |
| Toshiba                         | 7         | 0.28%   |
| Ralink Technology               | 7         | 0.28%   |
| ASUSTek Computer                | 6         | 0.24%   |
| TP-Link                         | 5         | 0.2%    |
| Realtek                         | 5         | 0.2%    |
| MediaTek                        | 4         | 0.16%   |
| Integrated System Solution      | 3         | 0.12%   |
| SINO WEALTH                     | 2         | 0.08%   |
| Chicony Electronics             | 2         | 0.08%   |
| USI                             | 1         | 0.04%   |
| Unknown                         | 1         | 0.04%   |
| Micro Star International        | 1         | 0.04%   |
| Belkin Components               | 1         | 0.04%   |
| Alps Electric                   | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 377       | 14.84%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 257       | 10.11%  |
| Realtek Bluetooth Radio                                                             | 248       | 9.76%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 229       | 9.01%   |
| Intel AX201 Bluetooth                                                               | 187       | 7.36%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 132       | 5.19%   |
| Intel AX200 Bluetooth                                                               | 120       | 4.72%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 108       | 4.25%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 49        | 1.93%   |
| IMC Networks Bluetooth Radio                                                        | 48        | 1.89%   |
| Ralink RT3290 Bluetooth                                                             | 43        | 1.69%   |
| IMC Networks Bluetooth Device                                                       | 42        | 1.65%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 40        | 1.57%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 38        | 1.5%    |
| Lite-On Bluetooth Device                                                            | 37        | 1.46%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 34        | 1.34%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 32        | 1.26%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 32        | 1.26%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 24        | 0.94%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 24        | 0.94%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 23        | 0.91%   |
| IMC Networks Wireless_Device                                                        | 22        | 0.87%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 16        | 0.63%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 15        | 0.59%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 15        | 0.59%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 14        | 0.55%   |
| Realtek RTL8723B Bluetooth                                                          | 14        | 0.55%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 13        | 0.51%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 13        | 0.51%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 13        | 0.51%   |
| Dell Wireless 365 Bluetooth                                                         | 11        | 0.43%   |
| Qualcomm Atheros Bluetooth                                                          | 10        | 0.39%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 10        | 0.39%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 10        | 0.39%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 10        | 0.39%   |
| Apple Bluetooth USB Host Controller                                                 | 10        | 0.39%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 9         | 0.35%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 8         | 0.31%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 8         | 0.31%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 8         | 0.31%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 2779      | 66.8%   |
| AMD                                             | 689       | 16.56%  |
| Nvidia                                          | 550       | 13.22%  |
| C-Media Electronics                             | 21        | 0.5%    |
| GN Netcom                                       | 14        | 0.34%   |
| Creative Labs                                   | 9         | 0.22%   |
| Plantronics                                     | 7         | 0.17%   |
| Generalplus Technology                          | 7         | 0.17%   |
| Logitech                                        | 6         | 0.14%   |
| Texas Instruments                               | 5         | 0.12%   |
| Realtek Semiconductor                           | 5         | 0.12%   |
| JMTek                                           | 5         | 0.12%   |
| Creative Technology                             | 5         | 0.12%   |
| Tenx Technology                                 | 4         | 0.1%    |
| Silicon Integrated Systems [SiS]                | 4         | 0.1%    |
| SteelSeries ApS                                 | 3         | 0.07%   |
| DSEA A/S                                        | 3         | 0.07%   |
| OPPO Electronics                                | 2         | 0.05%   |
| M-Audio                                         | 2         | 0.05%   |
| Lenovo                                          | 2         | 0.05%   |
| Giga-Byte Technology                            | 2         | 0.05%   |
| DCMT Technology                                 | 2         | 0.05%   |
| Cambridge Silicon Radio                         | 2         | 0.05%   |
| Zoran Co. Personal Media Division (Nogatech)    | 1         | 0.02%   |
| ZOOM                                            | 1         | 0.02%   |
| Yamaha                                          | 1         | 0.02%   |
| XMOS                                            | 1         | 0.02%   |
| VIA Technologies                                | 1         | 0.02%   |
| Vault                                           | 1         | 0.02%   |
| SZSanJing                                       | 1         | 0.02%   |
| Sony                                            | 1         | 0.02%   |
| Shenzhen Rapoo Technology                       | 1         | 0.02%   |
| Sennheiser Communications                       | 1         | 0.02%   |
| SAVITECH                                        | 1         | 0.02%   |
| Razer USA                                       | 1         | 0.02%   |
| Panasonic (Matsushita)                          | 1         | 0.02%   |
| NEC Computers                                   | 1         | 0.02%   |
| Microsoft                                       | 1         | 0.02%   |
| Mad Catz                                        | 1         | 0.02%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 553       | 11.03%  |
| AMD Family 17h/19h HD Audio Controller                                     | 337       | 6.72%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 227       | 4.53%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 227       | 4.53%   |
| Intel Cannon Lake PCH cAVS                                                 | 174       | 3.47%   |
| Intel 8 Series HD Audio Controller                                         | 160       | 3.19%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 159       | 3.17%   |
| Intel Haswell-ULT HD Audio Controller                                      | 158       | 3.15%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 149       | 2.97%   |
| Intel Comet Lake PCH-LP cAVS                                               | 141       | 2.81%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 139       | 2.77%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 134       | 2.67%   |
| Intel Broadwell-U Audio Controller                                         | 115       | 2.29%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 114       | 2.27%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 114       | 2.27%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 110       | 2.19%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 107       | 2.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 107       | 2.13%   |
| AMD FCH Azalia Controller                                                  | 96        | 1.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 95        | 1.9%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 84        | 1.68%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 76        | 1.52%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 72        | 1.44%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 71        | 1.42%   |
| Nvidia GP107GL High Definition Audio Controller                            | 65        | 1.3%    |
| AMD Kabini HDMI/DP Audio                                                   | 65        | 1.3%    |
| AMD High Definition Audio Controller                                       | 55        | 1.1%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 51        | 1.02%   |
| Intel 200 Series PCH HD Audio                                              | 49        | 0.98%   |
| AMD Starship/Matisse HD Audio Controller                                   | 48        | 0.96%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 45        | 0.9%    |
| Intel Comet Lake PCH cAVS                                                  | 44        | 0.88%   |
| Nvidia TU116 High Definition Audio Controller                              | 40        | 0.8%    |
| Nvidia High Definition Audio Controller                                    | 38        | 0.76%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 33        | 0.66%   |
| Intel CM238 HD Audio Controller                                            | 32        | 0.64%   |
| Intel Audio device                                                         | 24        | 0.48%   |
| Nvidia GF119 HDMI Audio Controller                                         | 23        | 0.46%   |
| Nvidia GF108 High Definition Audio Controller                              | 23        | 0.46%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 23        | 0.46%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 562       | 25.67%  |
| SK hynix                     | 528       | 24.12%  |
| Micron Technology            | 268       | 12.24%  |
| Kingston                     | 189       | 8.63%   |
| Unknown                      | 116       | 5.3%    |
| Crucial                      | 116       | 5.3%    |
| A-DATA Technology            | 89        | 4.07%   |
| Corsair                      | 84        | 3.84%   |
| Ramaxel Technology           | 83        | 3.79%   |
| Transcend                    | 46        | 2.1%    |
| G.Skill                      | 20        | 0.91%   |
| CSX                          | 19        | 0.87%   |
| Nanya Technology             | 17        | 0.78%   |
| Elpida                       | 16        | 0.73%   |
| Unknown (ABCD)               | 4         | 0.18%   |
| Silicon Power                | 4         | 0.18%   |
| OM Nanotech                  | 4         | 0.18%   |
| Avant                        | 3         | 0.14%   |
| ZION                         | 2         | 0.09%   |
| Kllisre                      | 2         | 0.09%   |
| ASint Technology             | 2         | 0.09%   |
| Apacer                       | 2         | 0.09%   |
| Unknown (0xAD44594E45540000) | 1         | 0.05%   |
| Unknown (0x1007)             | 1         | 0.05%   |
| Unknown (09D5)               | 1         | 0.05%   |
| Unknown (07F7)               | 1         | 0.05%   |
| Team                         | 1         | 0.05%   |
| Strontium                    | 1         | 0.05%   |
| SHARETRONIC                  | 1         | 0.05%   |
| Qumo                         | 1         | 0.05%   |
| Qimonda                      | 1         | 0.05%   |
| NETSOL                       | 1         | 0.05%   |
| Goldkey                      | 1         | 0.05%   |
| Gold Key                     | 1         | 0.05%   |
| Unknown                      | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s       | 63        | 2.73%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 53        | 2.3%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s   | 42        | 1.82%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s      | 36        | 1.56%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 29        | 1.26%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 28        | 1.22%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s       | 25        | 1.09%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 25        | 1.09%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 24        | 1.04%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s    | 24        | 1.04%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 23        | 1%      |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 23        | 1%      |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s       | 23        | 1%      |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s        | 21        | 0.91%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s   | 20        | 0.87%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s       | 20        | 0.87%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s   | 18        | 0.78%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 18        | 0.78%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB SODIMM DDR4 3200MT/s     | 18        | 0.78%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 17        | 0.74%   |
| Micron RAM Module 8GB DIMM DDR4 2666MT/s                    | 17        | 0.74%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s    | 17        | 0.74%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 16        | 0.69%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 16        | 0.69%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s       | 16        | 0.69%   |
| Crucial RAM CB8GS2400.C8ET 8GB SODIMM DDR4 2667MT/s         | 16        | 0.69%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s       | 15        | 0.65%   |
| Corsair RAM CMK16GX4M1D3000C16 16GB DIMM DDR4 3000MT/s      | 15        | 0.65%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s   | 13        | 0.56%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 12        | 0.52%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 12        | 0.52%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 12        | 0.52%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s       | 12        | 0.52%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s      | 11        | 0.48%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s       | 11        | 0.48%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s        | 11        | 0.48%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 10        | 0.43%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s       | 10        | 0.43%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s   | 10        | 0.43%   |
| Crucial RAM CB8GS2400.C8JT 8GB SODIMM DDR4 2400MT/s         | 10        | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1122      | 61.99%  |
| DDR3    | 503       | 27.79%  |
| LPDDR4  | 59        | 3.26%   |
| SDRAM   | 45        | 2.49%   |
| DDR2    | 33        | 1.82%   |
| LPDDR3  | 24        | 1.33%   |
| Unknown | 18        | 0.99%   |
| DDR     | 5         | 0.28%   |
| DDR5    | 1         | 0.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1349      | 75.32%  |
| DIMM         | 340       | 18.98%  |
| Row Of Chips | 97        | 5.42%   |
| Chip         | 2         | 0.11%   |
| Unknown      | 2         | 0.11%   |
| RIMM         | 1         | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 857       | 43.48%  |
| 4096  | 683       | 34.65%  |
| 16384 | 204       | 10.35%  |
| 2048  | 180       | 9.13%   |
| 1024  | 27        | 1.37%   |
| 32768 | 16        | 0.81%   |
| 512   | 3         | 0.15%   |
| 1536  | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 535       | 27.1%   |
| 1600    | 368       | 18.64%  |
| 3200    | 322       | 16.31%  |
| 2400    | 207       | 10.49%  |
| 1333    | 90        | 4.56%   |
| 2133    | 76        | 3.85%   |
| 3266    | 63        | 3.19%   |
| 1334    | 53        | 2.68%   |
| Unknown | 29        | 1.47%   |
| 2666    | 28        | 1.42%   |
| 667     | 25        | 1.27%   |
| 3600    | 19        | 0.96%   |
| 4199    | 18        | 0.91%   |
| 1067    | 18        | 0.91%   |
| 3000    | 16        | 0.81%   |
| 800     | 15        | 0.76%   |
| 4267    | 14        | 0.71%   |
| 1867    | 14        | 0.71%   |
| 2800    | 12        | 0.61%   |
| 3400    | 7         | 0.35%   |
| 1866    | 6         | 0.3%    |
| 975     | 6         | 0.3%    |
| 8400    | 4         | 0.2%    |
| 2048    | 4         | 0.2%    |
| 1066    | 3         | 0.15%   |
| 4800    | 2         | 0.1%    |
| 3066    | 2         | 0.1%    |
| 1800    | 2         | 0.1%    |
| 1400    | 2         | 0.1%    |
| 4266    | 1         | 0.05%   |
| 4000    | 1         | 0.05%   |
| 3733    | 1         | 0.05%   |
| 3666    | 1         | 0.05%   |
| 3467    | 1         | 0.05%   |
| 3466    | 1         | 0.05%   |
| 2933    | 1         | 0.05%   |
| 2733    | 1         | 0.05%   |
| 2200    | 1         | 0.05%   |
| 2000    | 1         | 0.05%   |
| 1648    | 1         | 0.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 17        | 40.48%  |
| Seiko Epson         | 10        | 23.81%  |
| Canon               | 7         | 16.67%  |
| Brother Industries  | 4         | 9.52%   |
| STMicroelectronics  | 1         | 2.38%   |
| Samsung Electronics | 1         | 2.38%   |
| Ricoh               | 1         | 2.38%   |
| Konica Minolta      | 1         | 2.38%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| HP LaserJet 1020                                                      | 6         | 14.29%  |
| Seiko Epson L380 Series                                               | 2         | 4.76%   |
| HP Ink Tank 310 series                                                | 2         | 4.76%   |
| HP DeskJet 1110 series                                                | 2         | 4.76%   |
| Canon PIXMA MG2500 Series                                             | 2         | 4.76%   |
| STMicroelectronics USB Printer P                                      | 1         | 2.38%   |
| Seiko Epson USB2.0 Printer (Hi-speed)                                 | 1         | 2.38%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 2.38%   |
| Seiko Epson M100 Series                                               | 1         | 2.38%   |
| Seiko Epson L405 Series                                               | 1         | 2.38%   |
| Seiko Epson L3200 Series                                              | 1         | 2.38%   |
| Seiko Epson L222 Series                                               | 1         | 2.38%   |
| Seiko Epson L132 Series                                               | 1         | 2.38%   |
| Seiko Epson ET-2710 Series                                            | 1         | 2.38%   |
| Samsung ML-1640 Series Laser Printer                                  | 1         | 2.38%   |
| Ricoh SP 111SU                                                        | 1         | 2.38%   |
| Konica Minolta 206                                                    | 1         | 2.38%   |
| HP Printing Support                                                   | 1         | 2.38%   |
| HP LaserJet Professional P1566                                        | 1         | 2.38%   |
| HP LaserJet Pro M202dw                                                | 1         | 2.38%   |
| HP DeskJet 3630 series                                                | 1         | 2.38%   |
| HP DeskJet 2620 All-in-One Printer                                    | 1         | 2.38%   |
| HP DeskJet 2130 series                                                | 1         | 2.38%   |
| HP Deskjet 1510                                                       | 1         | 2.38%   |
| Canon PIXMA MP280                                                     | 1         | 2.38%   |
| Canon PIXMA MP190                                                     | 1         | 2.38%   |
| Canon MF4800 Series                                                   | 1         | 2.38%   |
| Canon LBP2900                                                         | 1         | 2.38%   |
| Canon G2000 series                                                    | 1         | 2.38%   |
| Brother Printer                                                       | 1         | 2.38%   |
| Brother HL-L2320D series                                              | 1         | 2.38%   |
| Brother DCP-T510W                                                     | 1         | 2.38%   |
| Brother DCP-T310                                                      | 1         | 2.38%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 6         | 75%     |
| Seiko Epson     | 1         | 12.5%   |
| Hewlett-Packard | 1         | 12.5%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                     | 5         | 62.5%   |
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 12.5%   |
| HP ScanJet 2200c                            | 1         | 12.5%   |
| Canon CanoScan LiDE 120                     | 1         | 12.5%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 490       | 18.98%  |
| IMC Networks                           | 357       | 13.83%  |
| Realtek Semiconductor                  | 282       | 10.92%  |
| Microdia                               | 255       | 9.88%   |
| Acer                                   | 162       | 6.27%   |
| Quanta                                 | 157       | 6.08%   |
| Sunplus Innovation Technology          | 147       | 5.69%   |
| Cheng Uei Precision Industry (Foxlink) | 133       | 5.15%   |
| Suyin                                  | 109       | 4.22%   |
| Syntek                                 | 102       | 3.95%   |
| Lite-On Technology                     | 54        | 2.09%   |
| Luxvisions Innotech Limited            | 52        | 2.01%   |
| Logitech                               | 49        | 1.9%    |
| Alcor Micro                            | 26        | 1.01%   |
| Silicon Motion                         | 19        | 0.74%   |
| Apple                                  | 19        | 0.74%   |
| Samsung Electronics                    | 18        | 0.7%    |
| Sonix Technology                       | 16        | 0.62%   |
| Ricoh                                  | 14        | 0.54%   |
| Importek                               | 11        | 0.43%   |
| Z-Star Microelectronics                | 10        | 0.39%   |
| Lenovo                                 | 10        | 0.39%   |
| Unknown                                | 8         | 0.31%   |
| Primax Electronics                     | 8         | 0.31%   |
| OmniVision Technologies                | 8         | 0.31%   |
| Microsoft                              | 6         | 0.23%   |
| GEMBIRD                                | 6         | 0.23%   |
| Arkmicro Technologies                  | 6         | 0.23%   |
| SunplusIT                              | 4         | 0.15%   |
| Intel                                  | 4         | 0.15%   |
| MSD                                    | 3         | 0.12%   |
| Jieli Technology                       | 3         | 0.12%   |
| Cubeternet                             | 3         | 0.12%   |
| Spreadtrum Communications              | 2         | 0.08%   |
| Sony                                   | 2         | 0.08%   |
| Pixart Imaging                         | 2         | 0.08%   |
| MacroSilicon                           | 2         | 0.08%   |
| Holitech                               | 2         | 0.08%   |
| Foxconn / Hon Hai                      | 2         | 0.08%   |
| eMPIA Technology                       | 2         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                  | 136       | 5.25%   |
| Realtek Integrated_Webcam_HD                                   | 110       | 4.24%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 110       | 4.24%   |
| Chicony Integrated Camera                                      | 97        | 3.74%   |
| IMC Networks Integrated Camera                                 | 94        | 3.63%   |
| Sunplus Integrated_Webcam_HD                                   | 81        | 3.13%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 72        | 2.78%   |
| Syntek Integrated Camera                                       | 55        | 2.12%   |
| Realtek Integrated Webcam                                      | 54        | 2.08%   |
| Acer Integrated Camera                                         | 50        | 1.93%   |
| Chicony HP TrueVision HD                                       | 47        | 1.81%   |
| Chicony HP Truevision HD camera                                | 45        | 1.74%   |
| Chicony HD WebCam                                              | 41        | 1.58%   |
| Chicony EasyCamera                                             | 39        | 1.5%    |
| Suyin HP Truevision HD                                         | 37        | 1.43%   |
| Quanta HP TrueVision HD Camera                                 | 35        | 1.35%   |
| Quanta HD User Facing                                          | 33        | 1.27%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 32        | 1.23%   |
| Syntek EasyCamera                                              | 28        | 1.08%   |
| Acer Lenovo EasyCamera                                         | 28        | 1.08%   |
| Acer EasyCamera                                                | 28        | 1.08%   |
| Logitech Webcam C270                                           | 27        | 1.04%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 26        | 1%      |
| Quanta HD Webcam                                               | 25        | 0.96%   |
| Chicony HD User Facing                                         | 25        | 0.96%   |
| Lite-On Integrated Camera                                      | 24        | 0.93%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 23        | 0.89%   |
| Microdia Integrated Webcam                                     | 21        | 0.81%   |
| Suyin Integrated_Webcam_HD                                     | 20        | 0.77%   |
| Realtek EasyCamera                                             | 20        | 0.77%   |
| Quanta HP Wide Vision HD Camera                                | 19        | 0.73%   |
| IMC Networks HP TrueVision HD Camera                           | 19        | 0.73%   |
| Chicony HP Wide Vision HD Camera                               | 19        | 0.73%   |
| Samsung Galaxy A5 (MTP)                                        | 18        | 0.69%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 18        | 0.69%   |
| Chicony Integrated Camera (1280x720@30)                        | 17        | 0.66%   |
| IMC Networks VGA UVC WebCam                                    | 16        | 0.62%   |
| Acer SunplusIT Integrated Camera                               | 16        | 0.62%   |
| Syntek Lenovo EasyCamera                                       | 15        | 0.58%   |
| Sunplus HP TrueVision HD Camera                                | 15        | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 154       | 32.35%  |
| Synaptics                          | 111       | 23.32%  |
| Shenzhen Goodix Technology         | 97        | 20.38%  |
| Elan Microelectronics              | 64        | 13.45%  |
| LighTuning Technology              | 21        | 4.41%   |
| Upek                               | 10        | 2.1%    |
| AuthenTec                          | 10        | 2.1%    |
| Focal-systems.Corp                 | 5         | 1.05%   |
| STMicroelectronics                 | 1         | 0.21%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.21%   |
| Futronic Technology                | 1         | 0.21%   |
| DigitalPersona                     | 1         | 0.21%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 46        | 9.66%   |
| Shenzhen Goodix Fingerprint Reader                                         | 45        | 9.45%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 42        | 8.82%   |
| Unknown                                                                    | 40        | 8.4%    |
| Elan ELAN:ARM-M4                                                           | 36        | 7.56%   |
| Elan ELAN:Fingerprint                                                      | 26        | 5.46%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 23        | 4.83%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 21        | 4.41%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 21        | 4.41%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 21        | 4.41%   |
| Synaptics  WBDI                                                            | 18        | 3.78%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 14        | 2.94%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 12        | 2.52%   |
| Validity Sensors VFS Fingerprint sensor                                    | 10        | 2.1%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 10        | 2.1%    |
| Validity Sensors VFS491                                                    | 9         | 1.89%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 9         | 1.89%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 8         | 1.68%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 1.26%   |
| Shenzhen Goodix FingerPrint                                                | 6         | 1.26%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 1.05%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.05%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 1.05%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 5         | 1.05%   |
| AuthenTec Fingerprint Sensor                                               | 5         | 1.05%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 0.84%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 0.84%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.63%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 0.42%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.42%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 2         | 0.42%   |
| AuthenTec AES1600                                                          | 2         | 0.42%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.21%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.21%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.21%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.21%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.21%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.21%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.21%   |
| Futronic FS81 Fingerprint Scanner Module                                   | 1         | 0.21%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 45        | 63.38%  |
| Alcor Micro | 13        | 18.31%  |
| Upek        | 6         | 8.45%   |
| O2 Micro    | 3         | 4.23%   |
| Lenovo      | 3         | 4.23%   |
| Clay Logic  | 1         | 1.41%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 17        | 23.94%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 13        | 18.31%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 10        | 14.08%  |
| Broadcom 5880                                                                | 10        | 14.08%  |
| Broadcom 58200                                                               | 8         | 11.27%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 8.45%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 4.23%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 2.82%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.41%   |
| Clay Logic Nitrokey HSM                                                      | 1         | 1.41%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2423      | 68.23%  |
| 1     | 952       | 26.81%  |
| 2     | 139       | 3.91%   |
| 3     | 23        | 0.65%   |
| 4     | 8         | 0.23%   |
| 5     | 4         | 0.11%   |
| 9     | 1         | 0.03%   |
| 6     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 471       | 35.82%  |
| Graphics card            | 291       | 22.13%  |
| Net/wireless             | 227       | 17.26%  |
| Chipcard                 | 69        | 5.25%   |
| Bluetooth                | 62        | 4.71%   |
| Multimedia controller    | 60        | 4.56%   |
| Communication controller | 43        | 3.27%   |
| Camera                   | 27        | 2.05%   |
| Net/ethernet             | 16        | 1.22%   |
| Sound                    | 15        | 1.14%   |
| Unassigned class         | 9         | 0.68%   |
| Storage                  | 8         | 0.61%   |
| Network                  | 6         | 0.46%   |
| Modem                    | 5         | 0.38%   |
| Card reader              | 3         | 0.23%   |
| Storage/raid             | 1         | 0.08%   |
| Storage/ide              | 1         | 0.08%   |
| Firewire controller      | 1         | 0.08%   |


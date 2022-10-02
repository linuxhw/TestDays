Pop!_OS - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for Pop!_OS.

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

Total: 5885

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Apple         | MacBookPro5,5               | [42113dd7e3](https://linux-hardware.org/?probe=42113dd7e3) | Oct 01, 2022 |
| HUAWEI        | HN-WX9X                     | [4168f641b5](https://linux-hardware.org/?probe=4168f641b5) | Oct 01, 2022 |
| HP            | Laptop 15s-eq1xxx           | [a4252ba03a](https://linux-hardware.org/?probe=a4252ba03a) | Oct 01, 2022 |
| Dell          | Latitude E5530 non-vPro     | [b2d146f923](https://linux-hardware.org/?probe=b2d146f923) | Oct 01, 2022 |
| HP            | Pavilion                    | [124e8b760a](https://linux-hardware.org/?probe=124e8b760a) | Oct 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [3595e90895](https://linux-hardware.org/?probe=3595e90895) | Oct 01, 2022 |
| System76      | Darter Pro                  | [2829e72506](https://linux-hardware.org/?probe=2829e72506) | Oct 01, 2022 |
| System76      | Darter Pro                  | [c142cf370a](https://linux-hardware.org/?probe=c142cf370a) | Oct 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [29648b493a](https://linux-hardware.org/?probe=29648b493a) | Oct 01, 2022 |
| Lenovo        | ThinkPad P1 Gen 5 21DCCT... | [bde2b36c88](https://linux-hardware.org/?probe=bde2b36c88) | Oct 01, 2022 |
| Lenovo        | ThinkPad T480 20L5001FUS    | [a7e0da7aa4](https://linux-hardware.org/?probe=a7e0da7aa4) | Sep 30, 2022 |
| MSI           | GF63 Thin 11UD              | [071194b58e](https://linux-hardware.org/?probe=071194b58e) | Sep 30, 2022 |
| MSI           | GF63 Thin 11UD              | [e29586cf56](https://linux-hardware.org/?probe=e29586cf56) | Sep 30, 2022 |
| Dell          | Latitude 5400               | [66a5bc26f0](https://linux-hardware.org/?probe=66a5bc26f0) | Sep 30, 2022 |
| Apple         | MacBookPro14,3              | [3ccd7ea5d6](https://linux-hardware.org/?probe=3ccd7ea5d6) | Sep 30, 2022 |
| Fujitsu       | LIFEBOOK A6210              | [81653ba834](https://linux-hardware.org/?probe=81653ba834) | Sep 30, 2022 |
| HUAWEI        | VLT-WX0                     | [1669dae0a6](https://linux-hardware.org/?probe=1669dae0a6) | Sep 30, 2022 |
| Fujitsu       | LIFEBOOK A6210              | [9ac200d143](https://linux-hardware.org/?probe=9ac200d143) | Sep 30, 2022 |
| Fujitsu       | LIFEBOOK A6210              | [d31b97630d](https://linux-hardware.org/?probe=d31b97630d) | Sep 29, 2022 |
| Dell          | Latitude 5400               | [4536a4b473](https://linux-hardware.org/?probe=4536a4b473) | Sep 29, 2022 |
| Dell          | Latitude 5400               | [972e4ab3fa](https://linux-hardware.org/?probe=972e4ab3fa) | Sep 29, 2022 |
| Dell          | Precision M4800             | [d4142adadc](https://linux-hardware.org/?probe=d4142adadc) | Sep 29, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [d06b40ddf1](https://linux-hardware.org/?probe=d06b40ddf1) | Sep 29, 2022 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | [f758c22d98](https://linux-hardware.org/?probe=f758c22d98) | Sep 28, 2022 |
| Lenovo        | ThinkPad X220 4286PJ2       | [2d0c850c3a](https://linux-hardware.org/?probe=2d0c850c3a) | Sep 28, 2022 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | [b08fc47990](https://linux-hardware.org/?probe=b08fc47990) | Sep 28, 2022 |
| Lenovo        | G510 20238                  | [46cba6613f](https://linux-hardware.org/?probe=46cba6613f) | Sep 28, 2022 |
| Dell          | Latitude E7450              | [daeb4afb69](https://linux-hardware.org/?probe=daeb4afb69) | Sep 28, 2022 |
| Apple         | MacBookPro9,2               | [5ce350f38b](https://linux-hardware.org/?probe=5ce350f38b) | Sep 28, 2022 |
| MSI           | GF63 Thin 11UD              | [455bfad933](https://linux-hardware.org/?probe=455bfad933) | Sep 28, 2022 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [a3c4032d28](https://linux-hardware.org/?probe=a3c4032d28) | Sep 27, 2022 |
| Gigabyte      | P34V7                       | [27b9651432](https://linux-hardware.org/?probe=27b9651432) | Sep 27, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [99b6a53bd2](https://linux-hardware.org/?probe=99b6a53bd2) | Sep 27, 2022 |
| ASUSTek       | GL702VSK                    | [3b69ddb263](https://linux-hardware.org/?probe=3b69ddb263) | Sep 27, 2022 |
| MSI           | GS73 Stealth 8RF            | [37d9172163](https://linux-hardware.org/?probe=37d9172163) | Sep 26, 2022 |
| Acer          | Nitro AN515-45              | [8579eba471](https://linux-hardware.org/?probe=8579eba471) | Sep 26, 2022 |
| ASUSTek       | GL702VSK                    | [e91056ceab](https://linux-hardware.org/?probe=e91056ceab) | Sep 26, 2022 |
| Dell          | Inspiron N5110              | [eff6424aa4](https://linux-hardware.org/?probe=eff6424aa4) | Sep 26, 2022 |
| System76      | Galago Pro                  | [e815519fb7](https://linux-hardware.org/?probe=e815519fb7) | Sep 26, 2022 |
| System76      | Galago Pro                  | [6b2de473b7](https://linux-hardware.org/?probe=6b2de473b7) | Sep 26, 2022 |
| Razer         | Blade 15 Base Model (Ear... | [1b4db0c30c](https://linux-hardware.org/?probe=1b4db0c30c) | Sep 26, 2022 |
| ASUSTek       | K52N                        | [8d7b00011f](https://linux-hardware.org/?probe=8d7b00011f) | Sep 26, 2022 |
| System76      | Darter Pro                  | [7ad4ae7df4](https://linux-hardware.org/?probe=7ad4ae7df4) | Sep 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [acbd9cc9af](https://linux-hardware.org/?probe=acbd9cc9af) | Sep 25, 2022 |
| Acer          | Aspire V5-573G              | [50792d0ac6](https://linux-hardware.org/?probe=50792d0ac6) | Sep 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [27d8d35004](https://linux-hardware.org/?probe=27d8d35004) | Sep 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [e9de38d8eb](https://linux-hardware.org/?probe=e9de38d8eb) | Sep 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [65742b8b14](https://linux-hardware.org/?probe=65742b8b14) | Sep 25, 2022 |
| System76      | Oryx Pro                    | [3cf39a6993](https://linux-hardware.org/?probe=3cf39a6993) | Sep 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [d9ceae039a](https://linux-hardware.org/?probe=d9ceae039a) | Sep 24, 2022 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [5c39bdf4ab](https://linux-hardware.org/?probe=5c39bdf4ab) | Sep 24, 2022 |
| Razer         | Blade 15 Base Model (Ear... | [029c059963](https://linux-hardware.org/?probe=029c059963) | Sep 24, 2022 |
| HP            | Laptop 15s-eq1xxx           | [2bc6e102ef](https://linux-hardware.org/?probe=2bc6e102ef) | Sep 24, 2022 |
| MSI           | GF63 Thin 11UD              | [fac56b0962](https://linux-hardware.org/?probe=fac56b0962) | Sep 24, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [214a55ad3e](https://linux-hardware.org/?probe=214a55ad3e) | Sep 24, 2022 |
| MSI           | GF63 Thin 11UD              | [f8448323d1](https://linux-hardware.org/?probe=f8448323d1) | Sep 24, 2022 |
| Apple         | MacBookPro9,2               | [86b6d46191](https://linux-hardware.org/?probe=86b6d46191) | Sep 24, 2022 |
| MSI           | Prestige 14Evo A11M         | [609225524a](https://linux-hardware.org/?probe=609225524a) | Sep 23, 2022 |
| System76      | Darter Pro                  | [012968a4a3](https://linux-hardware.org/?probe=012968a4a3) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [7910fab01e](https://linux-hardware.org/?probe=7910fab01e) | Sep 22, 2022 |
| System76      | Darter Pro                  | [8d3bdb7585](https://linux-hardware.org/?probe=8d3bdb7585) | Sep 22, 2022 |
| Dell          | Inspiron 5520               | [032bbec1e3](https://linux-hardware.org/?probe=032bbec1e3) | Sep 22, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [3c93753c6c](https://linux-hardware.org/?probe=3c93753c6c) | Sep 22, 2022 |
| Dell          | Latitude 3490               | [de749eeeb8](https://linux-hardware.org/?probe=de749eeeb8) | Sep 21, 2022 |
| Dell          | Precision 3561              | [b924a86b79](https://linux-hardware.org/?probe=b924a86b79) | Sep 21, 2022 |
| Acer          | Nitro AN715-51              | [36fb85e6cb](https://linux-hardware.org/?probe=36fb85e6cb) | Sep 21, 2022 |
| Dell          | Latitude 7490               | [b8c3a5519a](https://linux-hardware.org/?probe=b8c3a5519a) | Sep 21, 2022 |
| Dell          | XPS 13 9370                 | [facc4c1755](https://linux-hardware.org/?probe=facc4c1755) | Sep 21, 2022 |
| Acer          | Aspire A515-54              | [8116705a81](https://linux-hardware.org/?probe=8116705a81) | Sep 21, 2022 |
| Dell          | Vostro 3500                 | [7fa417e9a6](https://linux-hardware.org/?probe=7fa417e9a6) | Sep 21, 2022 |
| Apple         | MacBookAir6,2               | [7fc6799a48](https://linux-hardware.org/?probe=7fc6799a48) | Sep 21, 2022 |
| Dell          | Inspiron 5577               | [c6f4124e49](https://linux-hardware.org/?probe=c6f4124e49) | Sep 21, 2022 |
| Lenovo        | ThinkPad E490 20N8005JMH    | [8e78f3c776](https://linux-hardware.org/?probe=8e78f3c776) | Sep 20, 2022 |
| ASUSTek       | ROG Strix G712LV_G712LV     | [1e7ca74f13](https://linux-hardware.org/?probe=1e7ca74f13) | Sep 20, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [b1df3aa03f](https://linux-hardware.org/?probe=b1df3aa03f) | Sep 20, 2022 |
| Itronix       | GD8200                      | [d9f515b935](https://linux-hardware.org/?probe=d9f515b935) | Sep 20, 2022 |
| Lenovo        | Legion 5-15ACH6H 82JU       | [1f48647e32](https://linux-hardware.org/?probe=1f48647e32) | Sep 20, 2022 |
| GPU Compan... | GWTN141-10                  | [6d43012457](https://linux-hardware.org/?probe=6d43012457) | Sep 20, 2022 |
| HONOR         | NMH-WCX9                    | [dd2687098a](https://linux-hardware.org/?probe=dd2687098a) | Sep 19, 2022 |
| ASUSTek       | GL502VSK                    | [a6dc9b627f](https://linux-hardware.org/?probe=a6dc9b627f) | Sep 19, 2022 |
| HONOR         | NMH-WCX9                    | [060f3bd895](https://linux-hardware.org/?probe=060f3bd895) | Sep 19, 2022 |
| Apple         | MacBookPro10,2              | [ecc3b7e71d](https://linux-hardware.org/?probe=ecc3b7e71d) | Sep 19, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [731d19459a](https://linux-hardware.org/?probe=731d19459a) | Sep 19, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [4fcfd69ec1](https://linux-hardware.org/?probe=4fcfd69ec1) | Sep 19, 2022 |
| HP            | OMEN by Laptop 15z-en100    | [47b0aed151](https://linux-hardware.org/?probe=47b0aed151) | Sep 19, 2022 |
| Framework     | Laptop                      | [8dbbe54af9](https://linux-hardware.org/?probe=8dbbe54af9) | Sep 18, 2022 |
| HUAWEI        | KLVL-WXXW                   | [37b4da9922](https://linux-hardware.org/?probe=37b4da9922) | Sep 18, 2022 |
| Gateway       | NV55C                       | [e00587af22](https://linux-hardware.org/?probe=e00587af22) | Sep 18, 2022 |
| Dell          | Latitude E7470              | [ceed7544ab](https://linux-hardware.org/?probe=ceed7544ab) | Sep 18, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [f40cc0db8a](https://linux-hardware.org/?probe=f40cc0db8a) | Sep 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1ad10d3c4b](https://linux-hardware.org/?probe=1ad10d3c4b) | Sep 18, 2022 |
| Dell          | Precision 5530              | [8fc00af945](https://linux-hardware.org/?probe=8fc00af945) | Sep 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [50da0a8acf](https://linux-hardware.org/?probe=50da0a8acf) | Sep 18, 2022 |
| MSI           | Sword 15 A11UD              | [e749154c3d](https://linux-hardware.org/?probe=e749154c3d) | Sep 18, 2022 |
| Dell          | Latitude E6330              | [5a1085f939](https://linux-hardware.org/?probe=5a1085f939) | Sep 18, 2022 |
| ASUSTek       | S550CA                      | [a403b2a79d](https://linux-hardware.org/?probe=a403b2a79d) | Sep 17, 2022 |
| MSI           | Prestige 15 A12UC           | [48437ccf94](https://linux-hardware.org/?probe=48437ccf94) | Sep 17, 2022 |
| OriginPC      | NT17-PRO                    | [962138caa9](https://linux-hardware.org/?probe=962138caa9) | Sep 17, 2022 |
| System76      | Darter Pro                  | [5d1e0ddc1a](https://linux-hardware.org/?probe=5d1e0ddc1a) | Sep 16, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [7099830d0a](https://linux-hardware.org/?probe=7099830d0a) | Sep 16, 2022 |
| Dell          | Inspiron 5547               | [d66cbae64b](https://linux-hardware.org/?probe=d66cbae64b) | Sep 16, 2022 |
| ASUSTek       | E402NA                      | [9d97fe89bb](https://linux-hardware.org/?probe=9d97fe89bb) | Sep 16, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [4dd83a1b80](https://linux-hardware.org/?probe=4dd83a1b80) | Sep 16, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [b0e6601fbf](https://linux-hardware.org/?probe=b0e6601fbf) | Sep 16, 2022 |
| ASUSTek       | N550LF                      | [73f2edfe65](https://linux-hardware.org/?probe=73f2edfe65) | Sep 16, 2022 |
| Apple         | MacBookPro5,4               | [9cc24963d4](https://linux-hardware.org/?probe=9cc24963d4) | Sep 16, 2022 |
| Apple         | MacBookPro5,4               | [6d28bb81ce](https://linux-hardware.org/?probe=6d28bb81ce) | Sep 16, 2022 |
| Toshiba       | Satellite C55t-C            | [9c45d5a042](https://linux-hardware.org/?probe=9c45d5a042) | Sep 16, 2022 |
| Dell          | XPS 13 9380                 | [6d94f648e4](https://linux-hardware.org/?probe=6d94f648e4) | Sep 16, 2022 |
| GPD           | MicroPC                     | [dadac68a23](https://linux-hardware.org/?probe=dadac68a23) | Sep 15, 2022 |
| HP            | Laptop 15s-fq1xxx           | [dc870b4e8a](https://linux-hardware.org/?probe=dc870b4e8a) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [3196144640](https://linux-hardware.org/?probe=3196144640) | Sep 15, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | [d39fd89ab8](https://linux-hardware.org/?probe=d39fd89ab8) | Sep 15, 2022 |
| Dell          | Precision 3561              | [b61765a085](https://linux-hardware.org/?probe=b61765a085) | Sep 15, 2022 |
| Fujitsu       | LIFEBOOK A512               | [2d33f80fbd](https://linux-hardware.org/?probe=2d33f80fbd) | Sep 15, 2022 |
| Dell          | Latitude 3420               | [5c00a1875c](https://linux-hardware.org/?probe=5c00a1875c) | Sep 14, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ed284e43fb](https://linux-hardware.org/?probe=ed284e43fb) | Sep 14, 2022 |
| Dell          | XPS 13 9360                 | [750bf03293](https://linux-hardware.org/?probe=750bf03293) | Sep 14, 2022 |
| MSI           | Katana GF66 12UE            | [955b9787eb](https://linux-hardware.org/?probe=955b9787eb) | Sep 14, 2022 |
| ASUSTek       | X555LN                      | [64b85307ec](https://linux-hardware.org/?probe=64b85307ec) | Sep 14, 2022 |
| ASUSTek       | X405UA                      | [3b098addea](https://linux-hardware.org/?probe=3b098addea) | Sep 14, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | [aa0553a310](https://linux-hardware.org/?probe=aa0553a310) | Sep 13, 2022 |
| Lenovo        | ThinkBook 13x ITG 20WJ      | [2e6e759434](https://linux-hardware.org/?probe=2e6e759434) | Sep 13, 2022 |
| Lenovo        | Flex 2-14 20404             | [a27c60fbde](https://linux-hardware.org/?probe=a27c60fbde) | Sep 13, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | [81b9b18da4](https://linux-hardware.org/?probe=81b9b18da4) | Sep 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [b502b7938d](https://linux-hardware.org/?probe=b502b7938d) | Sep 13, 2022 |
| Dell          | Studio 1555                 | [0d0f3de3b4](https://linux-hardware.org/?probe=0d0f3de3b4) | Sep 12, 2022 |
| Apple         | MacBook5,1                  | [8bdaf4361b](https://linux-hardware.org/?probe=8bdaf4361b) | Sep 12, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | [0c3d0800eb](https://linux-hardware.org/?probe=0c3d0800eb) | Sep 12, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [e1d128b56a](https://linux-hardware.org/?probe=e1d128b56a) | Sep 12, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [1889334e1f](https://linux-hardware.org/?probe=1889334e1f) | Sep 12, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | [f9add8f93d](https://linux-hardware.org/?probe=f9add8f93d) | Sep 11, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [805f6366dc](https://linux-hardware.org/?probe=805f6366dc) | Sep 11, 2022 |
| MSI           | Modern 15 A11M              | [931f4d2ca7](https://linux-hardware.org/?probe=931f4d2ca7) | Sep 11, 2022 |
| Acer          | Aspire A315-42G             | [34964d8e2d](https://linux-hardware.org/?probe=34964d8e2d) | Sep 11, 2022 |
| Lenovo        | ThinkPad T430 2350A26       | [7374ee44fa](https://linux-hardware.org/?probe=7374ee44fa) | Sep 10, 2022 |
| MSI           | Modern 15 A11M              | [4f1849370d](https://linux-hardware.org/?probe=4f1849370d) | Sep 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [f19e04efc1](https://linux-hardware.org/?probe=f19e04efc1) | Sep 10, 2022 |
| System76      | Oryx Pro                    | [d84de42ab6](https://linux-hardware.org/?probe=d84de42ab6) | Sep 10, 2022 |
| HP            | Laptop 15s-eq2xxx           | [c0adc468b3](https://linux-hardware.org/?probe=c0adc468b3) | Sep 10, 2022 |
| Dell          | Inspiron 16 5625            | [5ae1f0d923](https://linux-hardware.org/?probe=5ae1f0d923) | Sep 10, 2022 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | [6c1c4c8712](https://linux-hardware.org/?probe=6c1c4c8712) | Sep 10, 2022 |
| HP            | Dev One Notebook PC         | [bb72f0c2f4](https://linux-hardware.org/?probe=bb72f0c2f4) | Sep 10, 2022 |
| Dell          | Vostro 3550                 | [2e9e331465](https://linux-hardware.org/?probe=2e9e331465) | Sep 10, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [5811e17863](https://linux-hardware.org/?probe=5811e17863) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [4d3543d03f](https://linux-hardware.org/?probe=4d3543d03f) | Sep 09, 2022 |
| Dell          | Precision 3551              | [78f7c77b35](https://linux-hardware.org/?probe=78f7c77b35) | Sep 09, 2022 |
| System76      | Galago Pro                  | [8d52d900f2](https://linux-hardware.org/?probe=8d52d900f2) | Sep 09, 2022 |
| Dell          | Inspiron 5457               | [e44e9d3a85](https://linux-hardware.org/?probe=e44e9d3a85) | Sep 08, 2022 |
| AZW           | SEi                         | [d3531738fa](https://linux-hardware.org/?probe=d3531738fa) | Sep 08, 2022 |
| Lenovo        | ThinkPad T460 20FN003LGE    | [6108c677a2](https://linux-hardware.org/?probe=6108c677a2) | Sep 08, 2022 |
| Lenovo        | ThinkPad T460 20FN003LGE    | [0f8da1f0c8](https://linux-hardware.org/?probe=0f8da1f0c8) | Sep 08, 2022 |
| Dell          | Latitude 5420               | [511ef8a105](https://linux-hardware.org/?probe=511ef8a105) | Sep 08, 2022 |
| Dell          | Latitude 5420               | [48db2c3954](https://linux-hardware.org/?probe=48db2c3954) | Sep 08, 2022 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [09e8283762](https://linux-hardware.org/?probe=09e8283762) | Sep 08, 2022 |
| HP            | 245 G6                      | [054d226709](https://linux-hardware.org/?probe=054d226709) | Sep 07, 2022 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [e73c83b5c7](https://linux-hardware.org/?probe=e73c83b5c7) | Sep 07, 2022 |
| HP            | EliteBook 840 G6            | [132a8e025a](https://linux-hardware.org/?probe=132a8e025a) | Sep 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [af2641c077](https://linux-hardware.org/?probe=af2641c077) | Sep 07, 2022 |
| Acer          | Aspire S3                   | [cb62300974](https://linux-hardware.org/?probe=cb62300974) | Sep 07, 2022 |
| Lenovo        | ThinkPad T470s 20HGA039U... | [43c002ad40](https://linux-hardware.org/?probe=43c002ad40) | Sep 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [11b9de78b5](https://linux-hardware.org/?probe=11b9de78b5) | Sep 06, 2022 |
| Lenovo        | ThinkPad T480s 20L8SC160... | [b860019cf4](https://linux-hardware.org/?probe=b860019cf4) | Sep 06, 2022 |
| HP            | ZBook Firefly 15.6 inch ... | [40d6a47565](https://linux-hardware.org/?probe=40d6a47565) | Sep 05, 2022 |
| Clevo         | P65_P67SE                   | [9a38027b73](https://linux-hardware.org/?probe=9a38027b73) | Sep 05, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [cb787086fa](https://linux-hardware.org/?probe=cb787086fa) | Sep 05, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [61e1164988](https://linux-hardware.org/?probe=61e1164988) | Sep 04, 2022 |
| Dell          | XPS 15 9500                 | [ea5f9662d7](https://linux-hardware.org/?probe=ea5f9662d7) | Sep 04, 2022 |
| Dell          | Inspiron 3576               | [8f5998a9e4](https://linux-hardware.org/?probe=8f5998a9e4) | Sep 04, 2022 |
| Apple         | MacBookPro11,3              | [c40b757ca3](https://linux-hardware.org/?probe=c40b757ca3) | Sep 04, 2022 |
| MSI           | GP72 7RDX                   | [5d4efc6589](https://linux-hardware.org/?probe=5d4efc6589) | Sep 04, 2022 |
| Apple         | MacBookPro5,5               | [5f36c97ec4](https://linux-hardware.org/?probe=5f36c97ec4) | Sep 03, 2022 |
| Apple         | MacBookPro5,5               | [70de682c06](https://linux-hardware.org/?probe=70de682c06) | Sep 03, 2022 |
| Lenovo        | ThinkPad T460s 20FAS30D0... | [b75636bf8b](https://linux-hardware.org/?probe=b75636bf8b) | Sep 03, 2022 |
| Dell          | Inspiron 13-7378            | [0ab8b4e169](https://linux-hardware.org/?probe=0ab8b4e169) | Sep 03, 2022 |
| Dell          | XPS 15 9520                 | [39e1d43301](https://linux-hardware.org/?probe=39e1d43301) | Sep 03, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [db5a53a31c](https://linux-hardware.org/?probe=db5a53a31c) | Sep 03, 2022 |
| HUAWEI        | KPL-W0X                     | [cfb4e75518](https://linux-hardware.org/?probe=cfb4e75518) | Sep 03, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [5472c45d04](https://linux-hardware.org/?probe=5472c45d04) | Sep 03, 2022 |
| ASUSTek       | X550CL                      | [6e45ea1408](https://linux-hardware.org/?probe=6e45ea1408) | Sep 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [6d1fcccbb8](https://linux-hardware.org/?probe=6d1fcccbb8) | Sep 03, 2022 |
| Dell          | Latitude E5570              | [20350411cf](https://linux-hardware.org/?probe=20350411cf) | Sep 03, 2022 |
| HUAWEI        | KPL-W0X                     | [2e3f16bc80](https://linux-hardware.org/?probe=2e3f16bc80) | Sep 02, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [088dad5cba](https://linux-hardware.org/?probe=088dad5cba) | Sep 02, 2022 |
| Lenovo        | ThinkPad T480 20L6S80G00    | [bd599c876c](https://linux-hardware.org/?probe=bd599c876c) | Sep 02, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [d8505e212b](https://linux-hardware.org/?probe=d8505e212b) | Sep 02, 2022 |
| TUXEDO        | Pulse 15 Gen2               | [9b42566191](https://linux-hardware.org/?probe=9b42566191) | Sep 02, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [8e366d7e21](https://linux-hardware.org/?probe=8e366d7e21) | Sep 02, 2022 |
| Dell          | Precision 5530              | [0151d15e28](https://linux-hardware.org/?probe=0151d15e28) | Sep 02, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [b6e6d0a261](https://linux-hardware.org/?probe=b6e6d0a261) | Sep 02, 2022 |
| Samsung       | 270E5G/270E5U               | [7ef3570396](https://linux-hardware.org/?probe=7ef3570396) | Sep 02, 2022 |
| Dell          | XPS 13 9305                 | [1746053c5b](https://linux-hardware.org/?probe=1746053c5b) | Sep 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [46e67b2b16](https://linux-hardware.org/?probe=46e67b2b16) | Sep 01, 2022 |
| Dell          | G3 3590                     | [cbe6c26276](https://linux-hardware.org/?probe=cbe6c26276) | Sep 01, 2022 |
| ASUSTek       | N552VW                      | [99d4a9be86](https://linux-hardware.org/?probe=99d4a9be86) | Sep 01, 2022 |
| Dell          | Precision 5530              | [298ce27830](https://linux-hardware.org/?probe=298ce27830) | Sep 01, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | [55073b08dc](https://linux-hardware.org/?probe=55073b08dc) | Sep 01, 2022 |
| Lenovo        | Z50-70 20354                | [8ac8531142](https://linux-hardware.org/?probe=8ac8531142) | Sep 01, 2022 |
| Toshiba       | Satellite C850              | [6cf6d8fca8](https://linux-hardware.org/?probe=6cf6d8fca8) | Sep 01, 2022 |
| Apple         | MacBookAir9,1               | [51c4002c97](https://linux-hardware.org/?probe=51c4002c97) | Sep 01, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [d96b24b7f3](https://linux-hardware.org/?probe=d96b24b7f3) | Sep 01, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [67eb62450a](https://linux-hardware.org/?probe=67eb62450a) | Sep 01, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [838e09c9cf](https://linux-hardware.org/?probe=838e09c9cf) | Sep 01, 2022 |
| Lenovo        | Z50-70 20354                | [6e245e4c63](https://linux-hardware.org/?probe=6e245e4c63) | Sep 01, 2022 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [d6e9455a63](https://linux-hardware.org/?probe=d6e9455a63) | Aug 31, 2022 |
| Dell          | Inspiron 13-7378            | [42666a5460](https://linux-hardware.org/?probe=42666a5460) | Aug 31, 2022 |
| Toshiba       | Satellite C850              | [d9505cea0a](https://linux-hardware.org/?probe=d9505cea0a) | Aug 31, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | [6eeadaf886](https://linux-hardware.org/?probe=6eeadaf886) | Aug 31, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | [56e8f54a3e](https://linux-hardware.org/?probe=56e8f54a3e) | Aug 31, 2022 |
| Acer          | Aspire E1-571               | [4db54180a8](https://linux-hardware.org/?probe=4db54180a8) | Aug 31, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [6d04d534fa](https://linux-hardware.org/?probe=6d04d534fa) | Aug 31, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [988032b933](https://linux-hardware.org/?probe=988032b933) | Aug 31, 2022 |
| Toshiba       | Satellite C850              | [5d7cb36794](https://linux-hardware.org/?probe=5d7cb36794) | Aug 31, 2022 |
| Dell          | Inspiron 3493               | [dc23941a16](https://linux-hardware.org/?probe=dc23941a16) | Aug 31, 2022 |
| ASUSTek       | G75VX                       | [e249508d61](https://linux-hardware.org/?probe=e249508d61) | Aug 30, 2022 |
| Lenovo        | V330 81AX                   | [1457fc2903](https://linux-hardware.org/?probe=1457fc2903) | Aug 30, 2022 |
| Dell          | XPS 9320                    | [7fe70d3907](https://linux-hardware.org/?probe=7fe70d3907) | Aug 30, 2022 |
| Lenovo        | V330 81AX                   | [0699372547](https://linux-hardware.org/?probe=0699372547) | Aug 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [e5545fc36a](https://linux-hardware.org/?probe=e5545fc36a) | Aug 30, 2022 |
| Toshiba       | Satellite C845              | [58d3152512](https://linux-hardware.org/?probe=58d3152512) | Aug 29, 2022 |
| ASUSTek       | N550JV                      | [059ab7e21e](https://linux-hardware.org/?probe=059ab7e21e) | Aug 29, 2022 |
| HP            | EliteBook 8570w             | [907d5f36e6](https://linux-hardware.org/?probe=907d5f36e6) | Aug 29, 2022 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [aa5f4a0207](https://linux-hardware.org/?probe=aa5f4a0207) | Aug 29, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [065da8ca1e](https://linux-hardware.org/?probe=065da8ca1e) | Aug 29, 2022 |
| Apple         | MacBook5,2                  | [780e5cbb44](https://linux-hardware.org/?probe=780e5cbb44) | Aug 28, 2022 |
| Dell          | XPS 13 9305                 | [d8bd3d6fc6](https://linux-hardware.org/?probe=d8bd3d6fc6) | Aug 28, 2022 |
| Lenovo        | ThinkPad W520 4270CTO       | [c4be3fe1b6](https://linux-hardware.org/?probe=c4be3fe1b6) | Aug 28, 2022 |
| Lenovo        | ThinkPad W520 4270CTO       | [568802fb43](https://linux-hardware.org/?probe=568802fb43) | Aug 28, 2022 |
| HP            | ENVY dv7                    | [cbd3824347](https://linux-hardware.org/?probe=cbd3824347) | Aug 28, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [2e085a419b](https://linux-hardware.org/?probe=2e085a419b) | Aug 27, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [c47cd7c7ed](https://linux-hardware.org/?probe=c47cd7c7ed) | Aug 27, 2022 |
| ASUSTek       | X556UQK                     | [262ff7d08a](https://linux-hardware.org/?probe=262ff7d08a) | Aug 27, 2022 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [e3c7cd81e8](https://linux-hardware.org/?probe=e3c7cd81e8) | Aug 27, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [1746f3874c](https://linux-hardware.org/?probe=1746f3874c) | Aug 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1c75cbf917](https://linux-hardware.org/?probe=1c75cbf917) | Aug 27, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [7f2e793766](https://linux-hardware.org/?probe=7f2e793766) | Aug 27, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [8aeb1b057b](https://linux-hardware.org/?probe=8aeb1b057b) | Aug 27, 2022 |
| Dell          | XPS 9315                    | [6ab1d7417d](https://linux-hardware.org/?probe=6ab1d7417d) | Aug 27, 2022 |
| Apple         | MacBook4,1                  | [fdb7c715b3](https://linux-hardware.org/?probe=fdb7c715b3) | Aug 26, 2022 |
| Panasonic     | FZ55-1                      | [a45848f10f](https://linux-hardware.org/?probe=a45848f10f) | Aug 26, 2022 |
| Acer          | Aspire A515-45              | [88467a99ae](https://linux-hardware.org/?probe=88467a99ae) | Aug 26, 2022 |
| Dell          | Precision M4600             | [de9a03d9be](https://linux-hardware.org/?probe=de9a03d9be) | Aug 26, 2022 |
| HP            | Laptop 15-da1xxx            | [51e23209a4](https://linux-hardware.org/?probe=51e23209a4) | Aug 26, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [8aa6fdef16](https://linux-hardware.org/?probe=8aa6fdef16) | Aug 26, 2022 |
| Panasonic     | FZ55-1                      | [0ec106ca31](https://linux-hardware.org/?probe=0ec106ca31) | Aug 26, 2022 |
| Dell          | Precision M4600             | [83c727c6db](https://linux-hardware.org/?probe=83c727c6db) | Aug 26, 2022 |
| Dell          | Latitude E6400              | [714643ef93](https://linux-hardware.org/?probe=714643ef93) | Aug 25, 2022 |
| ASUSTek       | X540LJ                      | [edac754e93](https://linux-hardware.org/?probe=edac754e93) | Aug 25, 2022 |
| Acer          | Swift SFX14-41G             | [8d1cad5e52](https://linux-hardware.org/?probe=8d1cad5e52) | Aug 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [945109f9f8](https://linux-hardware.org/?probe=945109f9f8) | Aug 25, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 Ub 82KU    | [5237518074](https://linux-hardware.org/?probe=5237518074) | Aug 25, 2022 |
| HONOR         | NBR-WAX9                    | [7e2c842043](https://linux-hardware.org/?probe=7e2c842043) | Aug 25, 2022 |
| HUAWEI        | KPL-W0X                     | [b502ab922f](https://linux-hardware.org/?probe=b502ab922f) | Aug 25, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [b008775e13](https://linux-hardware.org/?probe=b008775e13) | Aug 24, 2022 |
| HP            | Dev One Notebook PC         | [4263165650](https://linux-hardware.org/?probe=4263165650) | Aug 24, 2022 |
| MSI           | Prestige 15 A10SC           | [35ffc8d54b](https://linux-hardware.org/?probe=35ffc8d54b) | Aug 23, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [6cb194ca87](https://linux-hardware.org/?probe=6cb194ca87) | Aug 23, 2022 |
| Acer          | Aspire V3-772G              | [92b070c9be](https://linux-hardware.org/?probe=92b070c9be) | Aug 23, 2022 |
| Positivo      | W942SV_SV1                  | [24ad2b387d](https://linux-hardware.org/?probe=24ad2b387d) | Aug 23, 2022 |
| ASUSTek       | X556UQK                     | [62dbb0625f](https://linux-hardware.org/?probe=62dbb0625f) | Aug 23, 2022 |
| ASUSTek       | X556UQK                     | [e5442dd2d4](https://linux-hardware.org/?probe=e5442dd2d4) | Aug 23, 2022 |
| MSI           | PS63 Modern 8RC             | [33a1092c01](https://linux-hardware.org/?probe=33a1092c01) | Aug 22, 2022 |
| Dell          | XPS 15 9520                 | [33ff4e4962](https://linux-hardware.org/?probe=33ff4e4962) | Aug 22, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [b41e95cd1b](https://linux-hardware.org/?probe=b41e95cd1b) | Aug 22, 2022 |
| Acer          | Swift SFX14-41G             | [959dda5404](https://linux-hardware.org/?probe=959dda5404) | Aug 22, 2022 |
| Apple         | MacBookPro6,1               | [52a1f16ef3](https://linux-hardware.org/?probe=52a1f16ef3) | Aug 22, 2022 |
| Apple         | MacBookPro6,1               | [ae19610f33](https://linux-hardware.org/?probe=ae19610f33) | Aug 21, 2022 |
| Acer          | Swift SFX14-41G             | [3de1fd7f2c](https://linux-hardware.org/?probe=3de1fd7f2c) | Aug 21, 2022 |
| System76      | Oryx Pro                    | [7c763e43c6](https://linux-hardware.org/?probe=7c763e43c6) | Aug 21, 2022 |
| Dell          | Inspiron 5547               | [f67221bd42](https://linux-hardware.org/?probe=f67221bd42) | Aug 21, 2022 |
| Acer          | Aspire 5740                 | [19158f2e35](https://linux-hardware.org/?probe=19158f2e35) | Aug 21, 2022 |
| HP            | ENVY TS m6 Sleekbook        | [314250b1d7](https://linux-hardware.org/?probe=314250b1d7) | Aug 21, 2022 |
| MSI           | Katana GF76 11UD            | [256a057752](https://linux-hardware.org/?probe=256a057752) | Aug 21, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | [9c31fff4b2](https://linux-hardware.org/?probe=9c31fff4b2) | Aug 20, 2022 |
| Dell          | Vostro 15 3515              | [3f12b83029](https://linux-hardware.org/?probe=3f12b83029) | Aug 20, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [0cef35b44a](https://linux-hardware.org/?probe=0cef35b44a) | Aug 20, 2022 |
| MSI           | GF63 Thin 10UC              | [b04f79d93a](https://linux-hardware.org/?probe=b04f79d93a) | Aug 20, 2022 |
| ASUSTek       | GL703VD                     | [54f9d46a7d](https://linux-hardware.org/?probe=54f9d46a7d) | Aug 19, 2022 |
| Gateway       | NV55C                       | [37dc8b6dd5](https://linux-hardware.org/?probe=37dc8b6dd5) | Aug 19, 2022 |
| Gateway       | NV55C                       | [377412b832](https://linux-hardware.org/?probe=377412b832) | Aug 18, 2022 |
| System76      | Oryx Pro                    | [1583fbab76](https://linux-hardware.org/?probe=1583fbab76) | Aug 18, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [0887012e66](https://linux-hardware.org/?probe=0887012e66) | Aug 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [5967f639c3](https://linux-hardware.org/?probe=5967f639c3) | Aug 16, 2022 |
| Acer          | Aspire A515-43              | [bec0e1fbd6](https://linux-hardware.org/?probe=bec0e1fbd6) | Aug 16, 2022 |
| Apple         | MacBookPro13,3              | [6cf76ee482](https://linux-hardware.org/?probe=6cf76ee482) | Aug 15, 2022 |
| Acer          | Aspire ES1-512              | [cb59c4a321](https://linux-hardware.org/?probe=cb59c4a321) | Aug 15, 2022 |
| Acer          | Aspire ES1-512              | [496f0834ae](https://linux-hardware.org/?probe=496f0834ae) | Aug 15, 2022 |
| ASUSTek       | UX310UQ                     | [f058aa0bf2](https://linux-hardware.org/?probe=f058aa0bf2) | Aug 15, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [332459de48](https://linux-hardware.org/?probe=332459de48) | Aug 15, 2022 |
| System76      | Oryx Pro                    | [b2c1b403b8](https://linux-hardware.org/?probe=b2c1b403b8) | Aug 14, 2022 |
| Acer          | Aspire 4752                 | [9854c38629](https://linux-hardware.org/?probe=9854c38629) | Aug 14, 2022 |
| MSI           | GF63 Thin 11UD              | [82bfe63c71](https://linux-hardware.org/?probe=82bfe63c71) | Aug 14, 2022 |
| MSI           | Prestige 15 A10SC           | [58d3be66c0](https://linux-hardware.org/?probe=58d3be66c0) | Aug 14, 2022 |
| Dell          | Latitude E7470              | [1c49732e63](https://linux-hardware.org/?probe=1c49732e63) | Aug 14, 2022 |
| Apple         | MacBookAir3,2               | [0756ed833b](https://linux-hardware.org/?probe=0756ed833b) | Aug 14, 2022 |
| Apple         | MacBookAir6,2               | [2c210a5825](https://linux-hardware.org/?probe=2c210a5825) | Aug 14, 2022 |
| Dell          | Inspiron 3521               | [ebf974be3e](https://linux-hardware.org/?probe=ebf974be3e) | Aug 13, 2022 |
| ASUSTek       | G74Sx                       | [309312e25d](https://linux-hardware.org/?probe=309312e25d) | Aug 13, 2022 |
| Dell          | Inspiron 3521               | [6dd71dbcf3](https://linux-hardware.org/?probe=6dd71dbcf3) | Aug 12, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [fa9cdcd977](https://linux-hardware.org/?probe=fa9cdcd977) | Aug 12, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [da7cc3fcb6](https://linux-hardware.org/?probe=da7cc3fcb6) | Aug 12, 2022 |
| HP            | EliteBook 840 G3            | [d7735b3387](https://linux-hardware.org/?probe=d7735b3387) | Aug 12, 2022 |
| Dell          | Inspiron N5110              | [74624820da](https://linux-hardware.org/?probe=74624820da) | Aug 12, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [5e0a6f08b1](https://linux-hardware.org/?probe=5e0a6f08b1) | Aug 12, 2022 |
| Dell          | Inspiron 13-7378            | [097cd944e0](https://linux-hardware.org/?probe=097cd944e0) | Aug 12, 2022 |
| HP            | Laptop 15-db1xxx            | [0644c9f46c](https://linux-hardware.org/?probe=0644c9f46c) | Aug 12, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [688ae71abc](https://linux-hardware.org/?probe=688ae71abc) | Aug 12, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [31a967ba05](https://linux-hardware.org/?probe=31a967ba05) | Aug 12, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [ff6370169f](https://linux-hardware.org/?probe=ff6370169f) | Aug 11, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [fe91d8cdd3](https://linux-hardware.org/?probe=fe91d8cdd3) | Aug 11, 2022 |
| Dell          | XPS 9320                    | [bdb29b0481](https://linux-hardware.org/?probe=bdb29b0481) | Aug 11, 2022 |
| ASUSTek       | X455LJ                      | [f90572b8e2](https://linux-hardware.org/?probe=f90572b8e2) | Aug 11, 2022 |
| Lenovo        | ThinkPad T450s 20BWS1RT0... | [b2f479d0b0](https://linux-hardware.org/?probe=b2f479d0b0) | Aug 11, 2022 |
| HP            | ENVY TS m6 Sleekbook        | [1f0a966a58](https://linux-hardware.org/?probe=1f0a966a58) | Aug 11, 2022 |
| Dell          | XPS 9320                    | [1d0ef5711d](https://linux-hardware.org/?probe=1d0ef5711d) | Aug 11, 2022 |
| Acer          | Aspire 4736Z                | [16cf1afc2a](https://linux-hardware.org/?probe=16cf1afc2a) | Aug 11, 2022 |
| Dell          | Inspiron 13-7378            | [637b0f0905](https://linux-hardware.org/?probe=637b0f0905) | Aug 11, 2022 |
| System76      | Galago UltraPro             | [8c38c1dac4](https://linux-hardware.org/?probe=8c38c1dac4) | Aug 11, 2022 |
| Dell          | Latitude 3330               | [e1f58ad934](https://linux-hardware.org/?probe=e1f58ad934) | Aug 10, 2022 |
| Dell          | Latitude 3330               | [24c9c3fe68](https://linux-hardware.org/?probe=24c9c3fe68) | Aug 10, 2022 |
| Dell          | Inspiron 13-7378            | [4093a81a8d](https://linux-hardware.org/?probe=4093a81a8d) | Aug 10, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [84453db535](https://linux-hardware.org/?probe=84453db535) | Aug 10, 2022 |
| ASUSTek       | K55A                        | [fb75627e6c](https://linux-hardware.org/?probe=fb75627e6c) | Aug 10, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [87e84c988f](https://linux-hardware.org/?probe=87e84c988f) | Aug 10, 2022 |
| Fujitsu       | LIFEBOOK UH552              | [cbcfa4fc6e](https://linux-hardware.org/?probe=cbcfa4fc6e) | Aug 10, 2022 |
| Apple         | MacBookPro15,4              | [494f3495c8](https://linux-hardware.org/?probe=494f3495c8) | Aug 10, 2022 |
| Apple         | MacBookPro16,2              | [c0813b6c4e](https://linux-hardware.org/?probe=c0813b6c4e) | Aug 10, 2022 |
| Apple         | MacBookPro16,2              | [d93b98ed98](https://linux-hardware.org/?probe=d93b98ed98) | Aug 10, 2022 |
| GPU Compan... | GWTC116-2                   | [fa15ec0e79](https://linux-hardware.org/?probe=fa15ec0e79) | Aug 09, 2022 |
| MSI           | Creator Z16 Hiroshi F A1... | [6ca46e8126](https://linux-hardware.org/?probe=6ca46e8126) | Aug 09, 2022 |
| MSI           | Creator Z16 Hiroshi F A1... | [ad3cfbb4c9](https://linux-hardware.org/?probe=ad3cfbb4c9) | Aug 09, 2022 |
| HUAWEI        | NBD-WXX9                    | [6f0c6f7474](https://linux-hardware.org/?probe=6f0c6f7474) | Aug 09, 2022 |
| System76      | Gazelle                     | [a251ef0ac1](https://linux-hardware.org/?probe=a251ef0ac1) | Aug 08, 2022 |
| MSI           | GF63 Thin 11UD              | [29d3bf5483](https://linux-hardware.org/?probe=29d3bf5483) | Aug 08, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [10d18cd30b](https://linux-hardware.org/?probe=10d18cd30b) | Aug 08, 2022 |
| HP            | Laptop 14s-dk0xxx           | [49ab4e0197](https://linux-hardware.org/?probe=49ab4e0197) | Aug 08, 2022 |
| Dell          | XPS 13 7390                 | [15c1c667af](https://linux-hardware.org/?probe=15c1c667af) | Aug 08, 2022 |
| MSI           | GF63 Thin 11UD              | [d8a5d82c22](https://linux-hardware.org/?probe=d8a5d82c22) | Aug 08, 2022 |
| HP            | Laptop 15-db1xxx            | [9e849a1708](https://linux-hardware.org/?probe=9e849a1708) | Aug 07, 2022 |
| MSI           | GF63 Thin 11UD              | [53e660f72b](https://linux-hardware.org/?probe=53e660f72b) | Aug 07, 2022 |
| MSI           | GF63 Thin 11UD              | [67e1664484](https://linux-hardware.org/?probe=67e1664484) | Aug 07, 2022 |
| MSI           | GF63 Thin 11UD              | [ecb313e10d](https://linux-hardware.org/?probe=ecb313e10d) | Aug 07, 2022 |
| GPU Compan... | GWTN141-10                  | [c7a19f9e04](https://linux-hardware.org/?probe=c7a19f9e04) | Aug 07, 2022 |
| Avell High... | B.ON                        | [d16f62f2b9](https://linux-hardware.org/?probe=d16f62f2b9) | Aug 07, 2022 |
| HP            | Pavilion g7                 | [ecd57742f3](https://linux-hardware.org/?probe=ecd57742f3) | Aug 07, 2022 |
| Apple         | MacBookPro11,5              | [221e16bfb1](https://linux-hardware.org/?probe=221e16bfb1) | Aug 07, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [7e5a0c0004](https://linux-hardware.org/?probe=7e5a0c0004) | Aug 06, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [80794c55e8](https://linux-hardware.org/?probe=80794c55e8) | Aug 06, 2022 |
| GPU Compan... | GWTN141-10                  | [8a3db7da17](https://linux-hardware.org/?probe=8a3db7da17) | Aug 06, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [a711d41e0d](https://linux-hardware.org/?probe=a711d41e0d) | Aug 05, 2022 |
| Dell          | Inspiron 3480               | [637d2f9f41](https://linux-hardware.org/?probe=637d2f9f41) | Aug 05, 2022 |
| Lenovo        | XiaoXinPro 16 ARH7 82SN     | [abaec227ae](https://linux-hardware.org/?probe=abaec227ae) | Aug 05, 2022 |
| Lenovo        | XiaoXinPro 16 ARH7 82SN     | [a1effa04c3](https://linux-hardware.org/?probe=a1effa04c3) | Aug 05, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | [e4d16e5adf](https://linux-hardware.org/?probe=e4d16e5adf) | Aug 05, 2022 |
| Dell          | Inspiron 3583               | [508f6ab592](https://linux-hardware.org/?probe=508f6ab592) | Aug 04, 2022 |
| ASUSTek       | ROG Strix G713RS_G713RS     | [707ab083b3](https://linux-hardware.org/?probe=707ab083b3) | Aug 04, 2022 |
| HP            | ProBook 645 G1              | [0183d60d2c](https://linux-hardware.org/?probe=0183d60d2c) | Aug 04, 2022 |
| Lenovo        | V15-IIL 82C5                | [cc2c2e7ceb](https://linux-hardware.org/?probe=cc2c2e7ceb) | Aug 04, 2022 |
| Lenovo        | ThinkPad E470c 20H3A000C... | [047888752c](https://linux-hardware.org/?probe=047888752c) | Aug 04, 2022 |
| Lenovo        | V15-IIL 82C5                | [e0153e91b7](https://linux-hardware.org/?probe=e0153e91b7) | Aug 04, 2022 |
| Lenovo        | IdeaPad U410                | [048c78d129](https://linux-hardware.org/?probe=048c78d129) | Aug 04, 2022 |
| ASUSTek       | G550JK                      | [e73f25c149](https://linux-hardware.org/?probe=e73f25c149) | Aug 03, 2022 |
| Lenovo        | ThinkPad L590 20Q7001HGE    | [3549ef85b6](https://linux-hardware.org/?probe=3549ef85b6) | Aug 03, 2022 |
| Dell          | XPS 15 9520                 | [385e290982](https://linux-hardware.org/?probe=385e290982) | Aug 03, 2022 |
| Dell          | XPS 15 9520                 | [c7789bc8ca](https://linux-hardware.org/?probe=c7789bc8ca) | Aug 03, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [85f64b5fa5](https://linux-hardware.org/?probe=85f64b5fa5) | Aug 03, 2022 |
| Dell          | G7 7500                     | [981382d336](https://linux-hardware.org/?probe=981382d336) | Aug 03, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | [06da05d12b](https://linux-hardware.org/?probe=06da05d12b) | Aug 03, 2022 |
| MSI           | GF63 Thin 11UD              | [bf4a2c0e11](https://linux-hardware.org/?probe=bf4a2c0e11) | Aug 03, 2022 |
| MSI           | GF63 Thin 11UD              | [f31ac48621](https://linux-hardware.org/?probe=f31ac48621) | Aug 03, 2022 |
| Dell          | Inspiron N5040              | [2da4d2a843](https://linux-hardware.org/?probe=2da4d2a843) | Aug 03, 2022 |
| Alienware     | x17 R2                      | [48772fabd8](https://linux-hardware.org/?probe=48772fabd8) | Aug 02, 2022 |
| MSI           | GF63 Thin 11UD              | [2e6cf4c0bd](https://linux-hardware.org/?probe=2e6cf4c0bd) | Aug 02, 2022 |
| Acer          | Aspire A115-32              | [d7eb24100d](https://linux-hardware.org/?probe=d7eb24100d) | Aug 02, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [ed743724e7](https://linux-hardware.org/?probe=ed743724e7) | Aug 02, 2022 |
| Lenovo        | Legion 5 15ITH6H 82JH       | [0b8452087a](https://linux-hardware.org/?probe=0b8452087a) | Aug 02, 2022 |
| Dell          | Latitude 5520               | [0406990128](https://linux-hardware.org/?probe=0406990128) | Aug 01, 2022 |
| Notebook      | NV4XMB,ME,MZ                | [7b369e1cdf](https://linux-hardware.org/?probe=7b369e1cdf) | Aug 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [4e2361dd88](https://linux-hardware.org/?probe=4e2361dd88) | Aug 01, 2022 |
| GPU Compan... | GWTN141-10                  | [d73365fe3e](https://linux-hardware.org/?probe=d73365fe3e) | Jul 31, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | [bdc243bf9f](https://linux-hardware.org/?probe=bdc243bf9f) | Jul 31, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | [41a0eba80f](https://linux-hardware.org/?probe=41a0eba80f) | Jul 31, 2022 |
| HP            | Pavilion 17                 | [b2c0846cf5](https://linux-hardware.org/?probe=b2c0846cf5) | Jul 31, 2022 |
| Dell          | Precision M6800             | [3584b1693d](https://linux-hardware.org/?probe=3584b1693d) | Jul 31, 2022 |
| Acer          | Swift SF314-51              | [f9a61fd8ad](https://linux-hardware.org/?probe=f9a61fd8ad) | Jul 31, 2022 |
| Acer          | Swift SF314-43              | [36659d2410](https://linux-hardware.org/?probe=36659d2410) | Jul 30, 2022 |
| Toshiba       | Satellite C75D-C            | [f4a9c3bc7f](https://linux-hardware.org/?probe=f4a9c3bc7f) | Jul 30, 2022 |
| Toshiba       | Satellite C75D-C            | [f017593574](https://linux-hardware.org/?probe=f017593574) | Jul 30, 2022 |
| Dell          | Vostro 15 3515              | [74b9e88d97](https://linux-hardware.org/?probe=74b9e88d97) | Jul 30, 2022 |
| Lenovo        | ThinkPad X270 20HMS12K00    | [b3d3ab37ef](https://linux-hardware.org/?probe=b3d3ab37ef) | Jul 30, 2022 |
| Intel Clie... | LAPKC71F                    | [0783ac445f](https://linux-hardware.org/?probe=0783ac445f) | Jul 30, 2022 |
| Lenovo        | ThinkPad P53 20QN003TUS     | [bf8e504209](https://linux-hardware.org/?probe=bf8e504209) | Jul 30, 2022 |
| PC Special... | NS50MU                      | [b5dd220296](https://linux-hardware.org/?probe=b5dd220296) | Jul 29, 2022 |
| Positivo      | C4128E-S                    | [a06c799159](https://linux-hardware.org/?probe=a06c799159) | Jul 29, 2022 |
| Lenovo        | ThinkPad P53 20QN003TUS     | [cf54e60bf1](https://linux-hardware.org/?probe=cf54e60bf1) | Jul 29, 2022 |
| GPU Compan... | GWTN141-10                  | [e392f0348d](https://linux-hardware.org/?probe=e392f0348d) | Jul 29, 2022 |
| GPU Compan... | GWTN141-10                  | [dea75365be](https://linux-hardware.org/?probe=dea75365be) | Jul 29, 2022 |
| HP            | Pavilion 13 x360 PC         | [a5220ea2c0](https://linux-hardware.org/?probe=a5220ea2c0) | Jul 28, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [adb71c8acc](https://linux-hardware.org/?probe=adb71c8acc) | Jul 28, 2022 |
| Dell          | Inspiron 3542               | [d0ff2340b1](https://linux-hardware.org/?probe=d0ff2340b1) | Jul 28, 2022 |
| Sony          | VPCEG27FM                   | [b8c840d19a](https://linux-hardware.org/?probe=b8c840d19a) | Jul 28, 2022 |
| MSI           | Modern 15 A5M               | [c6643cb779](https://linux-hardware.org/?probe=c6643cb779) | Jul 28, 2022 |
| MSI           | GF63 Thin 11UD              | [7c25b2c2c7](https://linux-hardware.org/?probe=7c25b2c2c7) | Jul 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [be9941b639](https://linux-hardware.org/?probe=be9941b639) | Jul 28, 2022 |
| MSI           | GF63 Thin 11UD              | [97bbabec13](https://linux-hardware.org/?probe=97bbabec13) | Jul 28, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [c884d7548c](https://linux-hardware.org/?probe=c884d7548c) | Jul 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [56faf89859](https://linux-hardware.org/?probe=56faf89859) | Jul 28, 2022 |
| MSI           | Prestige 15 A10SC           | [0fe8633425](https://linux-hardware.org/?probe=0fe8633425) | Jul 27, 2022 |
| MSI           | Prestige 15 A10SC           | [36001f3112](https://linux-hardware.org/?probe=36001f3112) | Jul 27, 2022 |
| Dell          | Vostro 5470                 | [82192dcb1d](https://linux-hardware.org/?probe=82192dcb1d) | Jul 27, 2022 |
| Apple         | MacBookAir7,2               | [a33f728c24](https://linux-hardware.org/?probe=a33f728c24) | Jul 27, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [8e76bb6095](https://linux-hardware.org/?probe=8e76bb6095) | Jul 27, 2022 |
| HP            | Pavilion dv6                | [577c3ce56c](https://linux-hardware.org/?probe=577c3ce56c) | Jul 27, 2022 |
| Sony          | VPCF11M1E                   | [97a18303ee](https://linux-hardware.org/?probe=97a18303ee) | Jul 26, 2022 |
| MSI           | GF63 Thin 11UD              | [ce18b4e9ab](https://linux-hardware.org/?probe=ce18b4e9ab) | Jul 26, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [04ae47501b](https://linux-hardware.org/?probe=04ae47501b) | Jul 26, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [7005989783](https://linux-hardware.org/?probe=7005989783) | Jul 26, 2022 |
| Acer          | Ferrari One 200             | [023ff9a691](https://linux-hardware.org/?probe=023ff9a691) | Jul 25, 2022 |
| Acer          | Ferrari One 200             | [447f8a06ea](https://linux-hardware.org/?probe=447f8a06ea) | Jul 25, 2022 |
| System76      | Lemur Pro                   | [c6269208fe](https://linux-hardware.org/?probe=c6269208fe) | Jul 25, 2022 |
| Acer          | Nitro AN515-42              | [8c5e11fe0e](https://linux-hardware.org/?probe=8c5e11fe0e) | Jul 25, 2022 |
| Dynabook      | Satellite Pro C50D-B        | [bd7ef0af73](https://linux-hardware.org/?probe=bd7ef0af73) | Jul 25, 2022 |
| GPU Compan... | GWTC116-2                   | [ac0f2b51c0](https://linux-hardware.org/?probe=ac0f2b51c0) | Jul 25, 2022 |
| MSI           | GF63 Thin 11UD              | [03bb89eced](https://linux-hardware.org/?probe=03bb89eced) | Jul 24, 2022 |
| Lenovo        | E41-25 81FS                 | [51b984566a](https://linux-hardware.org/?probe=51b984566a) | Jul 24, 2022 |
| Acer          | Aspire V3-551G              | [970f226406](https://linux-hardware.org/?probe=970f226406) | Jul 24, 2022 |
| Intel Clie... | LAPKC71F                    | [baf09f6525](https://linux-hardware.org/?probe=baf09f6525) | Jul 24, 2022 |
| MSI           | GF63 Thin 11UD              | [d41e7515af](https://linux-hardware.org/?probe=d41e7515af) | Jul 24, 2022 |
| MSI           | GF63 Thin 11UD              | [fdada0c3a6](https://linux-hardware.org/?probe=fdada0c3a6) | Jul 24, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [c1515e724a](https://linux-hardware.org/?probe=c1515e724a) | Jul 24, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [147556bf0a](https://linux-hardware.org/?probe=147556bf0a) | Jul 23, 2022 |
| Apple         | MacBookPro12,1              | [752155f862](https://linux-hardware.org/?probe=752155f862) | Jul 23, 2022 |
| Apple         | MacBookPro8,2               | [e31685e3ae](https://linux-hardware.org/?probe=e31685e3ae) | Jul 23, 2022 |
| Apple         | MacBookAir7,2               | [a86b33bdc2](https://linux-hardware.org/?probe=a86b33bdc2) | Jul 22, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [f9e9de55c0](https://linux-hardware.org/?probe=f9e9de55c0) | Jul 22, 2022 |
| Dell          | Vostro 5470                 | [95c9916b84](https://linux-hardware.org/?probe=95c9916b84) | Jul 22, 2022 |
| ASUSTek       | K52Dr                       | [efd71c663d](https://linux-hardware.org/?probe=efd71c663d) | Jul 22, 2022 |
| ASUSTek       | K93SM                       | [add292129b](https://linux-hardware.org/?probe=add292129b) | Jul 22, 2022 |
| Samsung       | 760XDA                      | [c3e04193b8](https://linux-hardware.org/?probe=c3e04193b8) | Jul 22, 2022 |
| GPU Compan... | GWTC116-2                   | [4763ba77ba](https://linux-hardware.org/?probe=4763ba77ba) | Jul 22, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [da25f9d9b4](https://linux-hardware.org/?probe=da25f9d9b4) | Jul 22, 2022 |
| HP            | ProBook 450 G3              | [c35f07bb03](https://linux-hardware.org/?probe=c35f07bb03) | Jul 21, 2022 |
| HP            | ProBook 450 G3              | [a1cab26fa9](https://linux-hardware.org/?probe=a1cab26fa9) | Jul 21, 2022 |
| Lenovo        | ThinkPad P52 20MAS1R100     | [7a01b8819c](https://linux-hardware.org/?probe=7a01b8819c) | Jul 21, 2022 |
| Notebook      | NV4XMB,ME,MZ                | [f965008c98](https://linux-hardware.org/?probe=f965008c98) | Jul 21, 2022 |
| Toshiba       | BLB                         | [997a7c93d7](https://linux-hardware.org/?probe=997a7c93d7) | Jul 21, 2022 |
| Dell          | Vostro 5470                 | [e73fa302e0](https://linux-hardware.org/?probe=e73fa302e0) | Jul 21, 2022 |
| HP            | ZBook Firefly 14 G7 Mobi... | [ed3f7b7f50](https://linux-hardware.org/?probe=ed3f7b7f50) | Jul 21, 2022 |
| Dell          | Vostro 5470                 | [c6dcb4ffa6](https://linux-hardware.org/?probe=c6dcb4ffa6) | Jul 21, 2022 |
| Apple         | MacBookPro9,2               | [add1e46d7e](https://linux-hardware.org/?probe=add1e46d7e) | Jul 20, 2022 |
| Acer          | Aspire V3-551G              | [f5675c45dc](https://linux-hardware.org/?probe=f5675c45dc) | Jul 20, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YES... | [48e2fa9544](https://linux-hardware.org/?probe=48e2fa9544) | Jul 19, 2022 |
| ASUSTek       | K52Dr                       | [31471e3583](https://linux-hardware.org/?probe=31471e3583) | Jul 19, 2022 |
| Apple         | MacBookPro5,1               | [8a81341ecd](https://linux-hardware.org/?probe=8a81341ecd) | Jul 18, 2022 |
| Dell          | Latitude D430               | [22c020a070](https://linux-hardware.org/?probe=22c020a070) | Jul 18, 2022 |
| HP            | Laptop 14-bw0xx             | [df814add04](https://linux-hardware.org/?probe=df814add04) | Jul 18, 2022 |
| Acer          | Aspire V3-551G              | [2baa51bbc9](https://linux-hardware.org/?probe=2baa51bbc9) | Jul 18, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [b903541b55](https://linux-hardware.org/?probe=b903541b55) | Jul 18, 2022 |
| ASUSTek       | X555LAB                     | [8ae373a79c](https://linux-hardware.org/?probe=8ae373a79c) | Jul 17, 2022 |
| Acer          | Aspire 5520                 | [a471c15853](https://linux-hardware.org/?probe=a471c15853) | Jul 17, 2022 |
| ASUSTek       | K53SJ                       | [515f269efc](https://linux-hardware.org/?probe=515f269efc) | Jul 17, 2022 |
| Acer          | Nitro AN515-57              | [b9429f25d1](https://linux-hardware.org/?probe=b9429f25d1) | Jul 17, 2022 |
| Gigabyte      | Blade Pro                   | [3c2576e897](https://linux-hardware.org/?probe=3c2576e897) | Jul 16, 2022 |
| MSI           | GS75 Stealth 9SG            | [8707f3e800](https://linux-hardware.org/?probe=8707f3e800) | Jul 16, 2022 |
| Alienware     | 15 R2                       | [8a6bd6054f](https://linux-hardware.org/?probe=8a6bd6054f) | Jul 16, 2022 |
| MSI           | Katana GF76 11UD            | [61b03607fa](https://linux-hardware.org/?probe=61b03607fa) | Jul 15, 2022 |
| Dell          | Precision M4600             | [96f8364d87](https://linux-hardware.org/?probe=96f8364d87) | Jul 15, 2022 |
| HUAWEI        | MACH-WX9                    | [76035ea427](https://linux-hardware.org/?probe=76035ea427) | Jul 15, 2022 |
| HP            | Laptop 17z-ca200            | [1159e9b888](https://linux-hardware.org/?probe=1159e9b888) | Jul 15, 2022 |
| System76      | Pangolin                    | [690b7b5984](https://linux-hardware.org/?probe=690b7b5984) | Jul 15, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [1dac03f80a](https://linux-hardware.org/?probe=1dac03f80a) | Jul 15, 2022 |
| ASUSTek       | X555LAB                     | [5c5b387f6c](https://linux-hardware.org/?probe=5c5b387f6c) | Jul 14, 2022 |
| Dell          | XPS 15 9520                 | [271277c36b](https://linux-hardware.org/?probe=271277c36b) | Jul 14, 2022 |
| Lenovo        | ThinkPad X230 2325YHU       | [4720a42a7f](https://linux-hardware.org/?probe=4720a42a7f) | Jul 14, 2022 |
| HP            | Laptop 14-fq0xxx            | [c21113bf90](https://linux-hardware.org/?probe=c21113bf90) | Jul 14, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [285e41f0aa](https://linux-hardware.org/?probe=285e41f0aa) | Jul 14, 2022 |
| Samsung       | 950XED                      | [b7f59889a0](https://linux-hardware.org/?probe=b7f59889a0) | Jul 14, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [27f79db974](https://linux-hardware.org/?probe=27f79db974) | Jul 13, 2022 |
| MSI           | GF63 Thin 11UD              | [b4cf81df26](https://linux-hardware.org/?probe=b4cf81df26) | Jul 13, 2022 |
| Lenovo        | Legion Y540-17IRH 81UJ      | [b70dfefc75](https://linux-hardware.org/?probe=b70dfefc75) | Jul 13, 2022 |
| MSI           | GF63 Thin 11UD              | [7107c7c2eb](https://linux-hardware.org/?probe=7107c7c2eb) | Jul 13, 2022 |
| Dell          | Latitude 3500               | [f42f32c17f](https://linux-hardware.org/?probe=f42f32c17f) | Jul 12, 2022 |
| HP            | EliteBook 8570w             | [495c5afa4b](https://linux-hardware.org/?probe=495c5afa4b) | Jul 12, 2022 |
| Apple         | MacBookPro10,2              | [facbace782](https://linux-hardware.org/?probe=facbace782) | Jul 12, 2022 |
| Apple         | MacBookPro10,2              | [9cc1538196](https://linux-hardware.org/?probe=9cc1538196) | Jul 12, 2022 |
| ASUSTek       | K53SJ                       | [f3ead95b28](https://linux-hardware.org/?probe=f3ead95b28) | Jul 12, 2022 |
| GPU Compan... | GWTN141-10                  | [0ce04e7b03](https://linux-hardware.org/?probe=0ce04e7b03) | Jul 12, 2022 |
| Apple         | MacBookPro7,1               | [821459e114](https://linux-hardware.org/?probe=821459e114) | Jul 12, 2022 |
| Dell          | Vostro 5470                 | [aedb7a18da](https://linux-hardware.org/?probe=aedb7a18da) | Jul 11, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [34c2c24b3b](https://linux-hardware.org/?probe=34c2c24b3b) | Jul 11, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | [ebbc4ebc1d](https://linux-hardware.org/?probe=ebbc4ebc1d) | Jul 11, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | [d200cc6f06](https://linux-hardware.org/?probe=d200cc6f06) | Jul 11, 2022 |
| Lenovo        | 14w 81MQ0013AU              | [a93743a911](https://linux-hardware.org/?probe=a93743a911) | Jul 11, 2022 |
| ASUSTek       | K53SJ                       | [1a9d6df3b5](https://linux-hardware.org/?probe=1a9d6df3b5) | Jul 11, 2022 |
| Dell          | Latitude E5440              | [2b94e70ac9](https://linux-hardware.org/?probe=2b94e70ac9) | Jul 11, 2022 |
| Dell          | Inspiron 1750               | [c39e03e656](https://linux-hardware.org/?probe=c39e03e656) | Jul 10, 2022 |
| MSI           | Katana GF76 11UG            | [8f152d3669](https://linux-hardware.org/?probe=8f152d3669) | Jul 10, 2022 |
| Dell          | Inspiron 1750               | [a885fd8b41](https://linux-hardware.org/?probe=a885fd8b41) | Jul 10, 2022 |
| Medion        | Erazer P6661 MD60303        | [35fbb2c055](https://linux-hardware.org/?probe=35fbb2c055) | Jul 10, 2022 |
| Apple         | MacBookPro11,3              | [9b65b57a57](https://linux-hardware.org/?probe=9b65b57a57) | Jul 10, 2022 |
| Acer          | Aspire A515-52              | [9dc5c32b9f](https://linux-hardware.org/?probe=9dc5c32b9f) | Jul 09, 2022 |
| HP            | ProBook 440 G2              | [a2a01affe3](https://linux-hardware.org/?probe=a2a01affe3) | Jul 09, 2022 |
| Lenovo        | ThinkPad T480s 20L8S2330... | [4718003bb5](https://linux-hardware.org/?probe=4718003bb5) | Jul 09, 2022 |
| Dell          | Latitude E7450              | [d0c3f69765](https://linux-hardware.org/?probe=d0c3f69765) | Jul 09, 2022 |
| MSI           | MS-16G4                     | [53f40f3420](https://linux-hardware.org/?probe=53f40f3420) | Jul 09, 2022 |
| Dell          | Vostro 15 3515              | [38e90a5b4d](https://linux-hardware.org/?probe=38e90a5b4d) | Jul 08, 2022 |
| Apple         | MacBookPro9,2               | [663a6c9413](https://linux-hardware.org/?probe=663a6c9413) | Jul 08, 2022 |
| ASUSTek       | G751JT                      | [92eb60a700](https://linux-hardware.org/?probe=92eb60a700) | Jul 08, 2022 |
| Panasonic     | CF-C2AQAZXLM                | [be9cf3127a](https://linux-hardware.org/?probe=be9cf3127a) | Jul 08, 2022 |
| ASUSTek       | K53SJ                       | [f9d5ea94ec](https://linux-hardware.org/?probe=f9d5ea94ec) | Jul 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | [e34a9c3166](https://linux-hardware.org/?probe=e34a9c3166) | Jul 08, 2022 |
| ASUSTek       | X55CR                       | [9e40e3f8ad](https://linux-hardware.org/?probe=9e40e3f8ad) | Jul 08, 2022 |
| HUAWEI        | MACH-WX9                    | [486d051b71](https://linux-hardware.org/?probe=486d051b71) | Jul 08, 2022 |
| Dell          | Vostro 5625                 | [b2fde3bdef](https://linux-hardware.org/?probe=b2fde3bdef) | Jul 07, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [842c5317f7](https://linux-hardware.org/?probe=842c5317f7) | Jul 07, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [3b7528beab](https://linux-hardware.org/?probe=3b7528beab) | Jul 07, 2022 |
| System76      | Lemur Pro                   | [bdc2ddb608](https://linux-hardware.org/?probe=bdc2ddb608) | Jul 07, 2022 |
| Toshiba       | Satellite L650              | [76de8069a0](https://linux-hardware.org/?probe=76de8069a0) | Jul 07, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [861d7b3714](https://linux-hardware.org/?probe=861d7b3714) | Jul 07, 2022 |
| Acer          | Nitro AN515-53              | [d31c5d1c11](https://linux-hardware.org/?probe=d31c5d1c11) | Jul 06, 2022 |
| Acer          | Nitro AN515-53              | [0304267499](https://linux-hardware.org/?probe=0304267499) | Jul 06, 2022 |
| Pegatron      | H36FF                       | [87eac99d1b](https://linux-hardware.org/?probe=87eac99d1b) | Jul 06, 2022 |
| Acer          | Aspire E3-112M              | [6de763aad6](https://linux-hardware.org/?probe=6de763aad6) | Jul 06, 2022 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | [a9d516466a](https://linux-hardware.org/?probe=a9d516466a) | Jul 06, 2022 |
| ASUSTek       | K50ID                       | [a194cebb73](https://linux-hardware.org/?probe=a194cebb73) | Jul 06, 2022 |
| ASUSTek       | K50ID                       | [90ccec43bf](https://linux-hardware.org/?probe=90ccec43bf) | Jul 06, 2022 |
| HP            | EliteBook 745 G2            | [21b712ca64](https://linux-hardware.org/?probe=21b712ca64) | Jul 05, 2022 |
| MSI           | Katana GF76 11UD            | [ece534d446](https://linux-hardware.org/?probe=ece534d446) | Jul 05, 2022 |
| MSI           | Katana GF76 11UD            | [1c52419886](https://linux-hardware.org/?probe=1c52419886) | Jul 05, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [b4732a4bda](https://linux-hardware.org/?probe=b4732a4bda) | Jul 05, 2022 |
| Dell          | Precision M4700             | [48cbbf8dd2](https://linux-hardware.org/?probe=48cbbf8dd2) | Jul 05, 2022 |
| Dell          | Latitude 7280               | [b7ed5b72a9](https://linux-hardware.org/?probe=b7ed5b72a9) | Jul 05, 2022 |
| HP            | ProBook 640 G1              | [2f88b6162e](https://linux-hardware.org/?probe=2f88b6162e) | Jul 05, 2022 |
| HP            | Pavilion 15                 | [abbd7fd848](https://linux-hardware.org/?probe=abbd7fd848) | Jul 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [a673b1557d](https://linux-hardware.org/?probe=a673b1557d) | Jul 05, 2022 |
| Toshiba       | Satellite C650D             | [23da2ae018](https://linux-hardware.org/?probe=23da2ae018) | Jul 04, 2022 |
| Apple         | MacBookPro10,2              | [40d0cb89c5](https://linux-hardware.org/?probe=40d0cb89c5) | Jul 04, 2022 |
| Acer          | Aspire E1-572G              | [6f24a453bf](https://linux-hardware.org/?probe=6f24a453bf) | Jul 04, 2022 |
| Lenovo        | ThinkPad T440p 20AN009CU... | [67d4a66421](https://linux-hardware.org/?probe=67d4a66421) | Jul 04, 2022 |
| ASUSTek       | X541UJ                      | [d3f8e6dee5](https://linux-hardware.org/?probe=d3f8e6dee5) | Jul 04, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [903fedb0aa](https://linux-hardware.org/?probe=903fedb0aa) | Jul 03, 2022 |
| Notebook      | P65xHP                      | [2b81391bb4](https://linux-hardware.org/?probe=2b81391bb4) | Jul 03, 2022 |
| MSI           | MPG B550 GAMING CARBON W... | [80c5bb3483](https://linux-hardware.org/?probe=80c5bb3483) | Jul 03, 2022 |
| Acer          | Aspire A515-51G             | [98ef915ec8](https://linux-hardware.org/?probe=98ef915ec8) | Jul 03, 2022 |
| Acer          | Aspire E5-473G              | [11b488a036](https://linux-hardware.org/?probe=11b488a036) | Jul 03, 2022 |
| MSI           | GE62 2QF                    | [789826020e](https://linux-hardware.org/?probe=789826020e) | Jul 03, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [8999ce3eca](https://linux-hardware.org/?probe=8999ce3eca) | Jul 03, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [6e6839a1d0](https://linux-hardware.org/?probe=6e6839a1d0) | Jul 03, 2022 |
| ASUSTek       | G751JT                      | [f437b1ee99](https://linux-hardware.org/?probe=f437b1ee99) | Jul 03, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [a8c5e48dc8](https://linux-hardware.org/?probe=a8c5e48dc8) | Jul 03, 2022 |
| Dell          | Latitude E6420              | [ede3298bf4](https://linux-hardware.org/?probe=ede3298bf4) | Jul 02, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fdb841889e](https://linux-hardware.org/?probe=fdb841889e) | Jul 02, 2022 |
| ASUSTek       | TUF Gaming FX705DD_FX705... | [048a900062](https://linux-hardware.org/?probe=048a900062) | Jul 02, 2022 |
| Lenovo        | Y720-15IKB 80VR             | [516b60430c](https://linux-hardware.org/?probe=516b60430c) | Jul 02, 2022 |
| Lenovo        | Y720-15IKB 80VR             | [c70a95cfc1](https://linux-hardware.org/?probe=c70a95cfc1) | Jul 02, 2022 |
| Apple         | MacBookPro9,2               | [4f6364d861](https://linux-hardware.org/?probe=4f6364d861) | Jul 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [eef50332e8](https://linux-hardware.org/?probe=eef50332e8) | Jul 02, 2022 |
| Dell          | Precision 7510              | [4831b50f9a](https://linux-hardware.org/?probe=4831b50f9a) | Jul 02, 2022 |
| MSI           | GF63 Thin 11UD              | [7847c0275c](https://linux-hardware.org/?probe=7847c0275c) | Jul 02, 2022 |
| MSI           | GF63 Thin 11UD              | [6b1e1133e4](https://linux-hardware.org/?probe=6b1e1133e4) | Jul 01, 2022 |
| Dell          | Precision M4600             | [ea07b9e45f](https://linux-hardware.org/?probe=ea07b9e45f) | Jul 01, 2022 |
| Dell          | Precision M4600             | [535d6029bc](https://linux-hardware.org/?probe=535d6029bc) | Jul 01, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [10ff366630](https://linux-hardware.org/?probe=10ff366630) | Jul 01, 2022 |
| Samsung       | 930XED                      | [56a04fa69d](https://linux-hardware.org/?probe=56a04fa69d) | Jul 01, 2022 |
| ASUSTek       | S550CA                      | [8ed63bbdfd](https://linux-hardware.org/?probe=8ed63bbdfd) | Jul 01, 2022 |
| Dell          | Precision 5530              | [d6dc0ecd91](https://linux-hardware.org/?probe=d6dc0ecd91) | Jul 01, 2022 |
| Dell          | Precision 5550              | [0ddb8905e5](https://linux-hardware.org/?probe=0ddb8905e5) | Jul 01, 2022 |
| MSI           | GF63 Thin 11UD              | [63508059d3](https://linux-hardware.org/?probe=63508059d3) | Jul 01, 2022 |
| MSI           | GF63 Thin 11UD              | [b7aef43e9e](https://linux-hardware.org/?probe=b7aef43e9e) | Jul 01, 2022 |
| MSI           | GF63 Thin 11UD              | [325fec2ac6](https://linux-hardware.org/?probe=325fec2ac6) | Jul 01, 2022 |
| HP            | Pavilion 15                 | [e35e3b2e52](https://linux-hardware.org/?probe=e35e3b2e52) | Jul 01, 2022 |
| Dell          | Precision 7510              | [c82cc3cb0f](https://linux-hardware.org/?probe=c82cc3cb0f) | Jul 01, 2022 |
| Dell          | Inspiron 5547               | [c2a91cc81e](https://linux-hardware.org/?probe=c2a91cc81e) | Jul 01, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [ccb50bd0f4](https://linux-hardware.org/?probe=ccb50bd0f4) | Jun 30, 2022 |
| Apple         | MacBookAir7,2               | [ab31abf1d5](https://linux-hardware.org/?probe=ab31abf1d5) | Jun 30, 2022 |
| HP            | Pavilion 15                 | [f76f8dff7a](https://linux-hardware.org/?probe=f76f8dff7a) | Jun 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [6095915fb5](https://linux-hardware.org/?probe=6095915fb5) | Jun 30, 2022 |
| HP            | ProBook 445 G8 Notebook ... | [35ca7c4868](https://linux-hardware.org/?probe=35ca7c4868) | Jun 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1f66ba5535](https://linux-hardware.org/?probe=1f66ba5535) | Jun 30, 2022 |
| Notebook      | P7xxDM3(-G)                 | [6abdc9b40d](https://linux-hardware.org/?probe=6abdc9b40d) | Jun 29, 2022 |
| Dell          | Latitude E5470              | [2440e59a5a](https://linux-hardware.org/?probe=2440e59a5a) | Jun 29, 2022 |
| Dell          | Inspiron 7460               | [c5e8b7f098](https://linux-hardware.org/?probe=c5e8b7f098) | Jun 29, 2022 |
| Eluktronic... | MECH-15 G3                  | [d307b13800](https://linux-hardware.org/?probe=d307b13800) | Jun 28, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [c14a32dd6b](https://linux-hardware.org/?probe=c14a32dd6b) | Jun 28, 2022 |
| ASUSTek       | S550CA                      | [93807824df](https://linux-hardware.org/?probe=93807824df) | Jun 28, 2022 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [843cbccc63](https://linux-hardware.org/?probe=843cbccc63) | Jun 27, 2022 |
| HP            | Pavilion Notebook           | [8e17cfd388](https://linux-hardware.org/?probe=8e17cfd388) | Jun 26, 2022 |
| HP            | EliteBook 820 G2            | [e568c96372](https://linux-hardware.org/?probe=e568c96372) | Jun 25, 2022 |
| Lenovo        | ThinkPad X230 23331R5       | [c6589e02c4](https://linux-hardware.org/?probe=c6589e02c4) | Jun 25, 2022 |
| Dell          | Vostro 3460                 | [90c701411f](https://linux-hardware.org/?probe=90c701411f) | Jun 25, 2022 |
| Dell          | Vostro 3460                 | [fb02c13e80](https://linux-hardware.org/?probe=fb02c13e80) | Jun 25, 2022 |
| HUAWEI        | MACHC-WAX9                  | [00089c4dbe](https://linux-hardware.org/?probe=00089c4dbe) | Jun 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [490c1074fe](https://linux-hardware.org/?probe=490c1074fe) | Jun 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [51d3a22bf6](https://linux-hardware.org/?probe=51d3a22bf6) | Jun 25, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [289b09bf25](https://linux-hardware.org/?probe=289b09bf25) | Jun 24, 2022 |
| System76      | Darter Pro                  | [db7f217878](https://linux-hardware.org/?probe=db7f217878) | Jun 24, 2022 |
| HP            | EliteBook 745 G2            | [fe87d16f84](https://linux-hardware.org/?probe=fe87d16f84) | Jun 24, 2022 |
| Dell          | Latitude E7470              | [c2a22e5a3d](https://linux-hardware.org/?probe=c2a22e5a3d) | Jun 24, 2022 |
| Dell          | Latitude E7470              | [962571591a](https://linux-hardware.org/?probe=962571591a) | Jun 24, 2022 |
| Alienware     | 14                          | [8846f2e474](https://linux-hardware.org/?probe=8846f2e474) | Jun 24, 2022 |
| Toshiba       | Satellite S50-A             | [c2e7c1b26d](https://linux-hardware.org/?probe=c2e7c1b26d) | Jun 24, 2022 |
| ASUSTek       | S550CA                      | [c7c236e5a1](https://linux-hardware.org/?probe=c7c236e5a1) | Jun 23, 2022 |
| Acer          | Swift SF314-54              | [47420af7dc](https://linux-hardware.org/?probe=47420af7dc) | Jun 23, 2022 |
| Dell          | Vostro 5470                 | [592f0a2f63](https://linux-hardware.org/?probe=592f0a2f63) | Jun 23, 2022 |
| Dell          | Precision 5520              | [2216faa750](https://linux-hardware.org/?probe=2216faa750) | Jun 22, 2022 |
| Dell          | Inspiron 7560               | [a65b832b57](https://linux-hardware.org/?probe=a65b832b57) | Jun 22, 2022 |
| Lenovo        | V14-IIL 82C4                | [c288025720](https://linux-hardware.org/?probe=c288025720) | Jun 21, 2022 |
| HP            | Dev One Notebook PC         | [3086580cf5](https://linux-hardware.org/?probe=3086580cf5) | Jun 21, 2022 |
| HP            | Dev One Notebook PC         | [0bc7456f92](https://linux-hardware.org/?probe=0bc7456f92) | Jun 21, 2022 |
| Dell          | Latitude E7240              | [1c76f3cdf4](https://linux-hardware.org/?probe=1c76f3cdf4) | Jun 21, 2022 |
| Quanta        | TWC                         | [6a466d7eac](https://linux-hardware.org/?probe=6a466d7eac) | Jun 21, 2022 |
| Dell          | Latitude E7240              | [2974c5fa7c](https://linux-hardware.org/?probe=2974c5fa7c) | Jun 21, 2022 |
| Dell          | XPS 15 9570                 | [c6c4eda2cb](https://linux-hardware.org/?probe=c6c4eda2cb) | Jun 21, 2022 |
| System76      | Lemur Pro                   | [0350f8d8f7](https://linux-hardware.org/?probe=0350f8d8f7) | Jun 21, 2022 |
| HP            | ProBook 440 G7              | [3bbbcaea72](https://linux-hardware.org/?probe=3bbbcaea72) | Jun 20, 2022 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | [faa0749731](https://linux-hardware.org/?probe=faa0749731) | Jun 20, 2022 |
| Acer          | Iconia                      | [2d1f1a2c32](https://linux-hardware.org/?probe=2d1f1a2c32) | Jun 20, 2022 |
| System76      | Lemur Pro                   | [38b04af23d](https://linux-hardware.org/?probe=38b04af23d) | Jun 20, 2022 |
| MSI           | Pulse GL66 12UEK            | [9bffffd652](https://linux-hardware.org/?probe=9bffffd652) | Jun 20, 2022 |
| MSI           | Pulse GL66 12UEK            | [a8d859700b](https://linux-hardware.org/?probe=a8d859700b) | Jun 20, 2022 |
| HP            | ZBook 15 G3                 | [8c6f371222](https://linux-hardware.org/?probe=8c6f371222) | Jun 19, 2022 |
| ASUSTek       | N550JV                      | [d1d647724c](https://linux-hardware.org/?probe=d1d647724c) | Jun 19, 2022 |
| Apple         | MacBookPro11,1              | [b88b88ba84](https://linux-hardware.org/?probe=b88b88ba84) | Jun 19, 2022 |
| Apple         | MacBookPro11,1              | [ec132b0ba5](https://linux-hardware.org/?probe=ec132b0ba5) | Jun 19, 2022 |
| HP            | ProBook 450 G1              | [7ef2bab71d](https://linux-hardware.org/?probe=7ef2bab71d) | Jun 19, 2022 |
| Dell          | Inspiron 5537               | [2b31dedd45](https://linux-hardware.org/?probe=2b31dedd45) | Jun 19, 2022 |
| HP            | 15 Notebook PC              | [b3efe3d4b5](https://linux-hardware.org/?probe=b3efe3d4b5) | Jun 19, 2022 |
| Apple         | MacBookPro11,5              | [b04866cc36](https://linux-hardware.org/?probe=b04866cc36) | Jun 19, 2022 |
| Apple         | MacBook5,1                  | [e601e834f2](https://linux-hardware.org/?probe=e601e834f2) | Jun 18, 2022 |
| Lenovo        | ThinkPad X240 20AMS75900    | [47b7f42708](https://linux-hardware.org/?probe=47b7f42708) | Jun 18, 2022 |
| Lenovo        | ThinkPad X240 20AMS75900    | [e0eb6f7475](https://linux-hardware.org/?probe=e0eb6f7475) | Jun 18, 2022 |
| Dell          | XPS 13 7390                 | [6d1dcb879d](https://linux-hardware.org/?probe=6d1dcb879d) | Jun 18, 2022 |
| Apple         | MacBookPro7,1               | [41eb5a7de2](https://linux-hardware.org/?probe=41eb5a7de2) | Jun 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [cb268bf1ab](https://linux-hardware.org/?probe=cb268bf1ab) | Jun 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [ed83fdd673](https://linux-hardware.org/?probe=ed83fdd673) | Jun 18, 2022 |
| Lenovo        | ThinkPad T450 20BUS1110E    | [77dd393da8](https://linux-hardware.org/?probe=77dd393da8) | Jun 18, 2022 |
| Apple         | MacBookPro7,1               | [d542c2f694](https://linux-hardware.org/?probe=d542c2f694) | Jun 18, 2022 |
| Dell          | Latitude E7240              | [2ed64f08f3](https://linux-hardware.org/?probe=2ed64f08f3) | Jun 17, 2022 |
| Dell          | Latitude E7240              | [31340542c2](https://linux-hardware.org/?probe=31340542c2) | Jun 17, 2022 |
| HP            | Unknown                     | [4c4cdf6526](https://linux-hardware.org/?probe=4c4cdf6526) | Jun 17, 2022 |
| Apple         | MacBookAir7,2               | [13d72fd6f0](https://linux-hardware.org/?probe=13d72fd6f0) | Jun 17, 2022 |
| Dell          | Latitude E7240              | [08efb8dcc5](https://linux-hardware.org/?probe=08efb8dcc5) | Jun 17, 2022 |
| Schenker      | VIA 15 Pro                  | [1d1727713f](https://linux-hardware.org/?probe=1d1727713f) | Jun 17, 2022 |
| HP            | EliteBook 8560p             | [8f60c0fb25](https://linux-hardware.org/?probe=8f60c0fb25) | Jun 17, 2022 |
| Dell          | Precision 5540              | [6d3f2c188b](https://linux-hardware.org/?probe=6d3f2c188b) | Jun 17, 2022 |
| Acer          | Aspire E5-574G              | [23c2dd37fe](https://linux-hardware.org/?probe=23c2dd37fe) | Jun 17, 2022 |
| Dell          | Latitude E7240              | [b6978a823c](https://linux-hardware.org/?probe=b6978a823c) | Jun 17, 2022 |
| Acer          | Aspire 4741                 | [9f25816784](https://linux-hardware.org/?probe=9f25816784) | Jun 16, 2022 |
| Dell          | Inspiron 3442               | [10304caa6b](https://linux-hardware.org/?probe=10304caa6b) | Jun 16, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [b136496151](https://linux-hardware.org/?probe=b136496151) | Jun 16, 2022 |
| System76      | Oryx Pro                    | [4daa6c7d77](https://linux-hardware.org/?probe=4daa6c7d77) | Jun 16, 2022 |
| Dell          | Latitude E6540              | [93f049609f](https://linux-hardware.org/?probe=93f049609f) | Jun 16, 2022 |
| System76      | Galago Pro                  | [440ba53ef9](https://linux-hardware.org/?probe=440ba53ef9) | Jun 16, 2022 |
| Apple         | MacBookPro8,1               | [145a1e77fc](https://linux-hardware.org/?probe=145a1e77fc) | Jun 16, 2022 |
| Dell          | Inspiron 7520               | [d6e4d7642d](https://linux-hardware.org/?probe=d6e4d7642d) | Jun 16, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | [cc1947a21b](https://linux-hardware.org/?probe=cc1947a21b) | Jun 15, 2022 |
| Acer          | Aspire E5-575G              | [aa390f3eaa](https://linux-hardware.org/?probe=aa390f3eaa) | Jun 15, 2022 |
| Sony          | SVF15A1M2ES                 | [bdcd4a90fc](https://linux-hardware.org/?probe=bdcd4a90fc) | Jun 15, 2022 |
| Dell          | Latitude E6540              | [03fb6fa23c](https://linux-hardware.org/?probe=03fb6fa23c) | Jun 15, 2022 |
| Dell          | Precision 5550              | [f5f815ceed](https://linux-hardware.org/?probe=f5f815ceed) | Jun 14, 2022 |
| Acer          | Swift SF314-54              | [06bccc3696](https://linux-hardware.org/?probe=06bccc3696) | Jun 14, 2022 |
| Dell          | Precision 7720              | [8b4da2326e](https://linux-hardware.org/?probe=8b4da2326e) | Jun 14, 2022 |
| Dell          | Precision 7720              | [bf25929cec](https://linux-hardware.org/?probe=bf25929cec) | Jun 14, 2022 |
| Dell          | Latitude E6540              | [44b876534d](https://linux-hardware.org/?probe=44b876534d) | Jun 14, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [f4ef35b902](https://linux-hardware.org/?probe=f4ef35b902) | Jun 14, 2022 |
| Dell          | Inspiron 7737               | [6fa74e19b1](https://linux-hardware.org/?probe=6fa74e19b1) | Jun 13, 2022 |
| Notebook      | P65_P67SE                   | [590b7204da](https://linux-hardware.org/?probe=590b7204da) | Jun 13, 2022 |
| HP            | EliteBook 820 G2            | [45ca271974](https://linux-hardware.org/?probe=45ca271974) | Jun 13, 2022 |
| Lenovo        | B40-80 80F6                 | [7449f0f8d2](https://linux-hardware.org/?probe=7449f0f8d2) | Jun 13, 2022 |
| ASUSTek       | K70IJ                       | [2eb24f0195](https://linux-hardware.org/?probe=2eb24f0195) | Jun 13, 2022 |
| ASUSTek       | K70IJ                       | [110ff08266](https://linux-hardware.org/?probe=110ff08266) | Jun 13, 2022 |
| Apple         | MacBookPro11,1              | [7222fb776a](https://linux-hardware.org/?probe=7222fb776a) | Jun 13, 2022 |
| Dell          | Latitude E6540              | [91e07b8f2d](https://linux-hardware.org/?probe=91e07b8f2d) | Jun 12, 2022 |
| ASUSTek       | UX430UQ                     | [9754c7394d](https://linux-hardware.org/?probe=9754c7394d) | Jun 12, 2022 |
| Dell          | System XPS L702X            | [b79115e065](https://linux-hardware.org/?probe=b79115e065) | Jun 12, 2022 |
| MSI           | Alpha 17 A4DEK              | [42171e02bb](https://linux-hardware.org/?probe=42171e02bb) | Jun 11, 2022 |
| HP            | EliteBook 820 G2            | [0a0828f262](https://linux-hardware.org/?probe=0a0828f262) | Jun 11, 2022 |
| ASUSTek       | GL552VW                     | [8ed24a5d98](https://linux-hardware.org/?probe=8ed24a5d98) | Jun 11, 2022 |
| Dell          | Inspiron 7520               | [4916232f15](https://linux-hardware.org/?probe=4916232f15) | Jun 11, 2022 |
| Acer          | Aspire 4349                 | [7c8c3427a9](https://linux-hardware.org/?probe=7c8c3427a9) | Jun 11, 2022 |
| HP            | ProBook 455 G3              | [bac60198a3](https://linux-hardware.org/?probe=bac60198a3) | Jun 10, 2022 |
| ASUSTek       | K50IJ                       | [c8bac63870](https://linux-hardware.org/?probe=c8bac63870) | Jun 10, 2022 |
| Dell          | Latitude E7270              | [8d8f0db52c](https://linux-hardware.org/?probe=8d8f0db52c) | Jun 10, 2022 |
| ASUSTek       | K50IJ                       | [addb86fcb0](https://linux-hardware.org/?probe=addb86fcb0) | Jun 10, 2022 |
| ASUSTek       | Unknown                     | [1cc4adfa36](https://linux-hardware.org/?probe=1cc4adfa36) | Jun 09, 2022 |
| HP            | Elite x2 1012 G1            | [ad03ec2516](https://linux-hardware.org/?probe=ad03ec2516) | Jun 09, 2022 |
| Dell          | Inspiron 7520               | [ebbea30b2b](https://linux-hardware.org/?probe=ebbea30b2b) | Jun 09, 2022 |
| Dell          | G7 7790                     | [58cfc35862](https://linux-hardware.org/?probe=58cfc35862) | Jun 09, 2022 |
| Dell          | G7 7790                     | [495cfbb6f3](https://linux-hardware.org/?probe=495cfbb6f3) | Jun 09, 2022 |
| ASUSTek       | S550CA                      | [c87c7a989a](https://linux-hardware.org/?probe=c87c7a989a) | Jun 09, 2022 |
| ASUSTek       | S550CA                      | [9ba4a449c6](https://linux-hardware.org/?probe=9ba4a449c6) | Jun 09, 2022 |
| System76      | Oryx Pro                    | [bf9c9467d3](https://linux-hardware.org/?probe=bf9c9467d3) | Jun 08, 2022 |
| System76      | Oryx Pro                    | [2f96b6b08d](https://linux-hardware.org/?probe=2f96b6b08d) | Jun 08, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [5c2fedfca8](https://linux-hardware.org/?probe=5c2fedfca8) | Jun 08, 2022 |
| Dell          | Vostro 5402                 | [ebf8dce138](https://linux-hardware.org/?probe=ebf8dce138) | Jun 07, 2022 |
| Dell          | Inspiron 5537               | [7bb51064db](https://linux-hardware.org/?probe=7bb51064db) | Jun 07, 2022 |
| Dell          | Precision M4800             | [2607169dfe](https://linux-hardware.org/?probe=2607169dfe) | Jun 06, 2022 |
| System76      | Oryx Pro                    | [ec0e78e0f6](https://linux-hardware.org/?probe=ec0e78e0f6) | Jun 06, 2022 |
| Lenovo        | ThinkPad Edge E531 6885C... | [d98f987b46](https://linux-hardware.org/?probe=d98f987b46) | Jun 06, 2022 |
| Framework     | Laptop                      | [ed8e682778](https://linux-hardware.org/?probe=ed8e682778) | Jun 06, 2022 |
| Samsung       | 760XDA                      | [46350b515c](https://linux-hardware.org/?probe=46350b515c) | Jun 06, 2022 |
| MSI           | GS75 Stealth 9SF            | [9d18e7094e](https://linux-hardware.org/?probe=9d18e7094e) | Jun 05, 2022 |
| ASUSTek       | X556URK                     | [d6da70c8bd](https://linux-hardware.org/?probe=d6da70c8bd) | Jun 05, 2022 |
| Lenovo        | ThinkPad T450 20BVA02TCD    | [1485986503](https://linux-hardware.org/?probe=1485986503) | Jun 05, 2022 |
| Lenovo        | ThinkPad T450 20BVA02TCD    | [2f60fd04bf](https://linux-hardware.org/?probe=2f60fd04bf) | Jun 05, 2022 |
| Acer          | Aspire A715-75G             | [d8a8c3c8b4](https://linux-hardware.org/?probe=d8a8c3c8b4) | Jun 05, 2022 |
| Lenovo        | ThinkPad Edge E531 6885C... | [1b09ad54c8](https://linux-hardware.org/?probe=1b09ad54c8) | Jun 05, 2022 |
| Dell          | Inspiron 3502               | [afa1c5cd74](https://linux-hardware.org/?probe=afa1c5cd74) | Jun 04, 2022 |
| Timi          | RedmiBook Pro 14S           | [f729442cad](https://linux-hardware.org/?probe=f729442cad) | Jun 04, 2022 |
| Dell          | Precision M4800             | [3bd843466c](https://linux-hardware.org/?probe=3bd843466c) | Jun 04, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [0b2aab3dc7](https://linux-hardware.org/?probe=0b2aab3dc7) | Jun 04, 2022 |
| Lenovo        | G470 20078                  | [44e0643923](https://linux-hardware.org/?probe=44e0643923) | Jun 03, 2022 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [27301ce2e8](https://linux-hardware.org/?probe=27301ce2e8) | Jun 03, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [54fb76191c](https://linux-hardware.org/?probe=54fb76191c) | Jun 03, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [605cbc489f](https://linux-hardware.org/?probe=605cbc489f) | Jun 03, 2022 |
| Acer          | Aspire A515-43              | [a8c04eea72](https://linux-hardware.org/?probe=a8c04eea72) | Jun 03, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [562348dd07](https://linux-hardware.org/?probe=562348dd07) | Jun 03, 2022 |
| Toshiba       | Satellite L850-1D5          | [c8a260ef80](https://linux-hardware.org/?probe=c8a260ef80) | Jun 03, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [f1f4aec562](https://linux-hardware.org/?probe=f1f4aec562) | Jun 02, 2022 |
| ASUSTek       | N53SV                       | [d793b451f6](https://linux-hardware.org/?probe=d793b451f6) | Jun 02, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [9299688b01](https://linux-hardware.org/?probe=9299688b01) | Jun 02, 2022 |
| Dell          | Latitude E7470              | [f9a9090c54](https://linux-hardware.org/?probe=f9a9090c54) | Jun 02, 2022 |
| Dell          | Latitude 7390               | [0c7c9778aa](https://linux-hardware.org/?probe=0c7c9778aa) | Jun 02, 2022 |
| Dell          | Latitude E6540              | [de2e1727bc](https://linux-hardware.org/?probe=de2e1727bc) | Jun 01, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | [491a4105d8](https://linux-hardware.org/?probe=491a4105d8) | Jun 01, 2022 |
| Dell          | Latitude E7240              | [e3c9cca7e1](https://linux-hardware.org/?probe=e3c9cca7e1) | Jun 01, 2022 |
| Acer          | Aspire ES1-572              | [6f6e6c038a](https://linux-hardware.org/?probe=6f6e6c038a) | Jun 01, 2022 |
| Lenovo        | ThinkPad T410 2537HN3       | [e373330c8b](https://linux-hardware.org/?probe=e373330c8b) | Jun 01, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 D... | [57f540db26](https://linux-hardware.org/?probe=57f540db26) | Jun 01, 2022 |
| Dell          | Inspiron 13 5310            | [70eccb19d4](https://linux-hardware.org/?probe=70eccb19d4) | Jun 01, 2022 |
| Dell          | Inspiron 5537               | [506d3fb361](https://linux-hardware.org/?probe=506d3fb361) | Jun 01, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [d0dbd3d75e](https://linux-hardware.org/?probe=d0dbd3d75e) | Jun 01, 2022 |
| Dell          | G7 7700                     | [25e22bc243](https://linux-hardware.org/?probe=25e22bc243) | May 31, 2022 |
| Lenovo        | V14-IIL 82C4                | [871738fea2](https://linux-hardware.org/?probe=871738fea2) | May 31, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [ed28d49715](https://linux-hardware.org/?probe=ed28d49715) | May 30, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [ce6b717155](https://linux-hardware.org/?probe=ce6b717155) | May 30, 2022 |
| HP            | Laptop 14-dq2xxx            | [14f581788f](https://linux-hardware.org/?probe=14f581788f) | May 30, 2022 |
| Acer          | Aspire A515-45              | [72b7fc79d4](https://linux-hardware.org/?probe=72b7fc79d4) | May 29, 2022 |
| Dell          | Vostro V130                 | [abefbba5b8](https://linux-hardware.org/?probe=abefbba5b8) | May 29, 2022 |
| Apple         | MacBookPro9,1               | [6fe2c4a416](https://linux-hardware.org/?probe=6fe2c4a416) | May 29, 2022 |
| MSI           | GF63 Thin 10SCXR            | [0d556408f3](https://linux-hardware.org/?probe=0d556408f3) | May 29, 2022 |
| HP            | OMEN by Laptop 15z-en100    | [35e3478a5d](https://linux-hardware.org/?probe=35e3478a5d) | May 28, 2022 |
| Medion        | X6816                       | [6d7996894c](https://linux-hardware.org/?probe=6d7996894c) | May 28, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [7ae101b473](https://linux-hardware.org/?probe=7ae101b473) | May 28, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [469ed3f68b](https://linux-hardware.org/?probe=469ed3f68b) | May 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [96bc0699c3](https://linux-hardware.org/?probe=96bc0699c3) | May 28, 2022 |
| Dell          | Inspiron 5566               | [88c420d481](https://linux-hardware.org/?probe=88c420d481) | May 28, 2022 |
| Toshiba       | IS 1413G                    | [c7a5f5eef3](https://linux-hardware.org/?probe=c7a5f5eef3) | May 28, 2022 |
| MSI           | MS-7D52                     | [f70c160542](https://linux-hardware.org/?probe=f70c160542) | May 28, 2022 |
| ASUSTek       | S400CA                      | [dadda333d2](https://linux-hardware.org/?probe=dadda333d2) | May 28, 2022 |
| PC Special... | NH5x_7xDCx_DDx              | [bd70d45ed2](https://linux-hardware.org/?probe=bd70d45ed2) | May 28, 2022 |
| Acer          | Nitro AN515-42              | [a2f2dc2eee](https://linux-hardware.org/?probe=a2f2dc2eee) | May 27, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [65bccd9c04](https://linux-hardware.org/?probe=65bccd9c04) | May 27, 2022 |
| Dell          | Vostro 5402                 | [323fc36eb6](https://linux-hardware.org/?probe=323fc36eb6) | May 27, 2022 |
| Toshiba       | QOSMIO X770                 | [8f7d0ba9f9](https://linux-hardware.org/?probe=8f7d0ba9f9) | May 27, 2022 |
| HP            | 255 G6 Notebook PC          | [8746b1aa23](https://linux-hardware.org/?probe=8746b1aa23) | May 27, 2022 |
| Dell          | Precision 5530              | [2ecf3390bf](https://linux-hardware.org/?probe=2ecf3390bf) | May 27, 2022 |
| Acer          | Aspire A315-57G             | [d0400f8d02](https://linux-hardware.org/?probe=d0400f8d02) | May 26, 2022 |
| Fujitsu       | CELSIUS H730                | [6f0b24d450](https://linux-hardware.org/?probe=6f0b24d450) | May 26, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [ab2cd65153](https://linux-hardware.org/?probe=ab2cd65153) | May 26, 2022 |
| System76      | Galago Pro                  | [3baddb9faa](https://linux-hardware.org/?probe=3baddb9faa) | May 26, 2022 |
| Dell          | Inspiron 3721               | [d4af21adb8](https://linux-hardware.org/?probe=d4af21adb8) | May 25, 2022 |
| A-DATA Tec... | XENIA 15                    | [1d7941d921](https://linux-hardware.org/?probe=1d7941d921) | May 25, 2022 |
| Lenovo        | ThinkPad X220 4286CTO       | [4c0d37687e](https://linux-hardware.org/?probe=4c0d37687e) | May 25, 2022 |
| Toshiba       | Satellite P850              | [9ec49310ff](https://linux-hardware.org/?probe=9ec49310ff) | May 25, 2022 |
| Dell          | Inspiron 7501               | [81f3b14e0a](https://linux-hardware.org/?probe=81f3b14e0a) | May 25, 2022 |
| Apple         | MacBookPro14,3              | [ca090207b8](https://linux-hardware.org/?probe=ca090207b8) | May 25, 2022 |
| Monster       | TULPAR T5 V14.1             | [647e502881](https://linux-hardware.org/?probe=647e502881) | May 25, 2022 |
| Monster       | TULPAR T5 V14.1             | [0db0bd7aa8](https://linux-hardware.org/?probe=0db0bd7aa8) | May 25, 2022 |
| ASUSTek       | G551JM                      | [3db2e28ef2](https://linux-hardware.org/?probe=3db2e28ef2) | May 24, 2022 |
| Toshiba       | IS 1413G                    | [a34eaa3e4a](https://linux-hardware.org/?probe=a34eaa3e4a) | May 24, 2022 |
| Dell          | Precision 5550              | [6b17026494](https://linux-hardware.org/?probe=6b17026494) | May 24, 2022 |
| Toshiba       | IS 1413G                    | [e6e080d6e0](https://linux-hardware.org/?probe=e6e080d6e0) | May 24, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [a59234d081](https://linux-hardware.org/?probe=a59234d081) | May 24, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [bf692d5408](https://linux-hardware.org/?probe=bf692d5408) | May 23, 2022 |
| Acer          | Swift SF314-54              | [39f85b46d7](https://linux-hardware.org/?probe=39f85b46d7) | May 23, 2022 |
| Dell          | XPS 15 7590                 | [b5f49ae2e9](https://linux-hardware.org/?probe=b5f49ae2e9) | May 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [f2e32c336d](https://linux-hardware.org/?probe=f2e32c336d) | May 23, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [7fa4ca7312](https://linux-hardware.org/?probe=7fa4ca7312) | May 23, 2022 |
| Acer          | TravelMate 7750G            | [3ff0c1c7f2](https://linux-hardware.org/?probe=3ff0c1c7f2) | May 23, 2022 |
| Acer          | TravelMate 7750G            | [80bfe5a0c6](https://linux-hardware.org/?probe=80bfe5a0c6) | May 23, 2022 |
| Apple         | MacBookPro11,1              | [1d4f3a60c0](https://linux-hardware.org/?probe=1d4f3a60c0) | May 23, 2022 |
| ASUSTek       | X505BA                      | [685c1f7378](https://linux-hardware.org/?probe=685c1f7378) | May 22, 2022 |
| Apple         | MacBookAir7,2               | [b620a51628](https://linux-hardware.org/?probe=b620a51628) | May 22, 2022 |
| Lenovo        | ThinkPad T480 20L5S00F00    | [7a1f70c8aa](https://linux-hardware.org/?probe=7a1f70c8aa) | May 22, 2022 |
| Dell          | G3 3500                     | [49f86cc226](https://linux-hardware.org/?probe=49f86cc226) | May 22, 2022 |
| Intel Clie... | LAPKC71F                    | [1f67896c5c](https://linux-hardware.org/?probe=1f67896c5c) | May 22, 2022 |
| MSI           | Katana GF76 12UGS           | [06cb917381](https://linux-hardware.org/?probe=06cb917381) | May 22, 2022 |
| MSI           | Katana GF76 12UGS           | [22776216d6](https://linux-hardware.org/?probe=22776216d6) | May 22, 2022 |
| Google        | Lulu                        | [e7a0842114](https://linux-hardware.org/?probe=e7a0842114) | May 21, 2022 |
| MSI           | Modern 14 A10M              | [97a0996658](https://linux-hardware.org/?probe=97a0996658) | May 21, 2022 |
| HP            | Pavilion Notebook           | [1cd571d585](https://linux-hardware.org/?probe=1cd571d585) | May 21, 2022 |
| ASUSTek       | X510UR                      | [40b1695a67](https://linux-hardware.org/?probe=40b1695a67) | May 21, 2022 |
| ASUSTek       | X510UR                      | [e7cea85f09](https://linux-hardware.org/?probe=e7cea85f09) | May 21, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [bc911a9c04](https://linux-hardware.org/?probe=bc911a9c04) | May 21, 2022 |
| MSI           | Katana GF76 12UGS           | [cd50fa44c3](https://linux-hardware.org/?probe=cd50fa44c3) | May 21, 2022 |
| MSI           | Katana GF76 12UGS           | [556940f73e](https://linux-hardware.org/?probe=556940f73e) | May 21, 2022 |
| MSI           | Katana GF76 12UGS           | [fbea498a36](https://linux-hardware.org/?probe=fbea498a36) | May 21, 2022 |
| PC Special... | NP5x_NP6x_NP7xPNK_PNH_PN... | [e002072665](https://linux-hardware.org/?probe=e002072665) | May 21, 2022 |
| MSI           | MS-7D52                     | [1144b23f51](https://linux-hardware.org/?probe=1144b23f51) | May 21, 2022 |
| HP            | EliteBook 8570w             | [3f21c66d5c](https://linux-hardware.org/?probe=3f21c66d5c) | May 20, 2022 |
| Lenovo        | G40-30 80FY                 | [4280810a31](https://linux-hardware.org/?probe=4280810a31) | May 20, 2022 |
| Intel Clie... | LAPKC71F                    | [a227af798c](https://linux-hardware.org/?probe=a227af798c) | May 20, 2022 |
| System76      | Oryx Pro                    | [d705be052a](https://linux-hardware.org/?probe=d705be052a) | May 20, 2022 |
| Dell          | Inspiron 5555               | [35c2610913](https://linux-hardware.org/?probe=35c2610913) | May 20, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [2320338e52](https://linux-hardware.org/?probe=2320338e52) | May 19, 2022 |
| Dell          | XPS 15 9570                 | [ba19473e18](https://linux-hardware.org/?probe=ba19473e18) | May 19, 2022 |
| Gigabyte      | AERO 15 KC                  | [5ebc19bd4c](https://linux-hardware.org/?probe=5ebc19bd4c) | May 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [c9a82e1be0](https://linux-hardware.org/?probe=c9a82e1be0) | May 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [8ef2235464](https://linux-hardware.org/?probe=8ef2235464) | May 17, 2022 |
| System76      | Oryx Pro                    | [b68edfe15c](https://linux-hardware.org/?probe=b68edfe15c) | May 17, 2022 |
| Samsung       | 550XCJ/550XCR               | [5bc959890b](https://linux-hardware.org/?probe=5bc959890b) | May 17, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [e4bf8d23b8](https://linux-hardware.org/?probe=e4bf8d23b8) | May 17, 2022 |
| HUAWEI        | HN-WX9X                     | [f5ade437dc](https://linux-hardware.org/?probe=f5ade437dc) | May 17, 2022 |
| HP            | Laptop 14-dk1xxx            | [77a8cae8a0](https://linux-hardware.org/?probe=77a8cae8a0) | May 17, 2022 |
| ASUSTek       | G73Jh                       | [2d96e5ecba](https://linux-hardware.org/?probe=2d96e5ecba) | May 17, 2022 |
| Toshiba       | Satellite L50D-C            | [f06e254906](https://linux-hardware.org/?probe=f06e254906) | May 17, 2022 |
| Alienware     | 18                          | [7aa82b2786](https://linux-hardware.org/?probe=7aa82b2786) | May 17, 2022 |
| Acer          | Aspire 7560G                | [d3d9aa988f](https://linux-hardware.org/?probe=d3d9aa988f) | May 16, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [eb5345a5c6](https://linux-hardware.org/?probe=eb5345a5c6) | May 16, 2022 |
| Google        | Lulu                        | [c402204a03](https://linux-hardware.org/?probe=c402204a03) | May 16, 2022 |
| Fujitsu       | LIFEBOOK T5010              | [e0aab70a85](https://linux-hardware.org/?probe=e0aab70a85) | May 16, 2022 |
| Infinix       | INBook X1 Pro               | [bb99e2b6ad](https://linux-hardware.org/?probe=bb99e2b6ad) | May 16, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [3a369eed6d](https://linux-hardware.org/?probe=3a369eed6d) | May 16, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [a8fffad424](https://linux-hardware.org/?probe=a8fffad424) | May 16, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [b1afeba24a](https://linux-hardware.org/?probe=b1afeba24a) | May 16, 2022 |
| Apple         | MacBookPro16,2              | [ceb6a7e5a3](https://linux-hardware.org/?probe=ceb6a7e5a3) | May 16, 2022 |
| Apple         | MacBookPro16,2              | [5c4ebc223f](https://linux-hardware.org/?probe=5c4ebc223f) | May 16, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [3ecda9477c](https://linux-hardware.org/?probe=3ecda9477c) | May 16, 2022 |
| Apple         | MacBookPro14,1              | [2d4d81086f](https://linux-hardware.org/?probe=2d4d81086f) | May 15, 2022 |
| Acer          | TravelMate P249-G2-MG       | [e6f35b116a](https://linux-hardware.org/?probe=e6f35b116a) | May 15, 2022 |
| Lenovo        | Y520-15IKBM 80YY            | [67b9691645](https://linux-hardware.org/?probe=67b9691645) | May 15, 2022 |
| Dell          | Vostro 5471                 | [62e934492d](https://linux-hardware.org/?probe=62e934492d) | May 15, 2022 |
| Dell          | XPS 15 9510                 | [653725bdde](https://linux-hardware.org/?probe=653725bdde) | May 15, 2022 |
| Dell          | XPS 15 9560                 | [04f0e074cb](https://linux-hardware.org/?probe=04f0e074cb) | May 14, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [7a2fd723d6](https://linux-hardware.org/?probe=7a2fd723d6) | May 14, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [98db0dde2a](https://linux-hardware.org/?probe=98db0dde2a) | May 13, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [66e43801f0](https://linux-hardware.org/?probe=66e43801f0) | May 13, 2022 |
| Google        | Lulu                        | [8d7f1657d0](https://linux-hardware.org/?probe=8d7f1657d0) | May 13, 2022 |
| Acer          | Swift SF314-54              | [a31c36956a](https://linux-hardware.org/?probe=a31c36956a) | May 13, 2022 |
| HP            | Pavilion Notebook           | [44952d0fff](https://linux-hardware.org/?probe=44952d0fff) | May 13, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [30bb58501e](https://linux-hardware.org/?probe=30bb58501e) | May 13, 2022 |
| Apple         | MacBookPro5,2               | [0a3017f333](https://linux-hardware.org/?probe=0a3017f333) | May 13, 2022 |
| Acer          | Nitro AN515-44              | [fe8e3837f4](https://linux-hardware.org/?probe=fe8e3837f4) | May 12, 2022 |
| System76      | Pangolin                    | [0f05fa93a8](https://linux-hardware.org/?probe=0f05fa93a8) | May 12, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [ea75711bf8](https://linux-hardware.org/?probe=ea75711bf8) | May 12, 2022 |
| Apple         | MacBookAir7,2               | [114ef2756f](https://linux-hardware.org/?probe=114ef2756f) | May 12, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [915b95cae4](https://linux-hardware.org/?probe=915b95cae4) | May 11, 2022 |
| ASUSTek       | G750JM                      | [1bcf5cc7ea](https://linux-hardware.org/?probe=1bcf5cc7ea) | May 11, 2022 |
| Samsung       | 550XCJ/550XCR               | [2dd9e88806](https://linux-hardware.org/?probe=2dd9e88806) | May 11, 2022 |
| Google        | Cyan                        | [cec3bd0a88](https://linux-hardware.org/?probe=cec3bd0a88) | May 11, 2022 |
| HP            | ZBook Studio G7 Mobile W... | [4f25a82453](https://linux-hardware.org/?probe=4f25a82453) | May 11, 2022 |
| Apple         | MacBook5,2                  | [0913ac4c8e](https://linux-hardware.org/?probe=0913ac4c8e) | May 11, 2022 |
| System76      | Pangolin                    | [da80a33b86](https://linux-hardware.org/?probe=da80a33b86) | May 11, 2022 |
| Dell          | G15 5511                    | [17b75bcced](https://linux-hardware.org/?probe=17b75bcced) | May 10, 2022 |
| Dell          | XPS 13 9305                 | [0066686d1d](https://linux-hardware.org/?probe=0066686d1d) | May 10, 2022 |
| Dell          | XPS 13 9310                 | [cae0934838](https://linux-hardware.org/?probe=cae0934838) | May 10, 2022 |
| HP            | EliteBook 2730p             | [d4c5b7824d](https://linux-hardware.org/?probe=d4c5b7824d) | May 10, 2022 |
| HP            | 15 Notebook PC              | [d88f833b65](https://linux-hardware.org/?probe=d88f833b65) | May 10, 2022 |
| HP            | EliteBook 8570w             | [840087bbed](https://linux-hardware.org/?probe=840087bbed) | May 09, 2022 |
| HP            | EliteBook 8570w             | [d9779b1c50](https://linux-hardware.org/?probe=d9779b1c50) | May 09, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [badd8c8562](https://linux-hardware.org/?probe=badd8c8562) | May 09, 2022 |
| HP            | Laptop 15-dy1xxx            | [fd022c446e](https://linux-hardware.org/?probe=fd022c446e) | May 09, 2022 |
| TUXEDO        | Unknown                     | [20f46751c2](https://linux-hardware.org/?probe=20f46751c2) | May 08, 2022 |
| TUXEDO        | Unknown                     | [c1df33620d](https://linux-hardware.org/?probe=c1df33620d) | May 08, 2022 |
| MSI           | Modern 15 A10RAS            | [3e844bb07a](https://linux-hardware.org/?probe=3e844bb07a) | May 08, 2022 |
| Lenovo        | ThinkPad T480 20L6S8H100    | [5eefaba8d3](https://linux-hardware.org/?probe=5eefaba8d3) | May 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [dcdc07525d](https://linux-hardware.org/?probe=dcdc07525d) | May 08, 2022 |
| Apple         | MacBookAir6,2               | [1e1f4caa54](https://linux-hardware.org/?probe=1e1f4caa54) | May 08, 2022 |
| Samsung       | 800G5M/800G5W               | [057ea02fdb](https://linux-hardware.org/?probe=057ea02fdb) | May 08, 2022 |
| Lenovo        | ThinkPad T480 20L6S8H100    | [892d07e5cf](https://linux-hardware.org/?probe=892d07e5cf) | May 08, 2022 |
| Lenovo        | Legion 5 17ITH6H 82JM       | [451c9ea765](https://linux-hardware.org/?probe=451c9ea765) | May 08, 2022 |
| ASUSTek       | E200HA                      | [ba413ad853](https://linux-hardware.org/?probe=ba413ad853) | May 08, 2022 |
| MSI           | GS63 7RD                    | [eff12e3973](https://linux-hardware.org/?probe=eff12e3973) | May 08, 2022 |
| HP            | Pavilion 15                 | [a18593bb5b](https://linux-hardware.org/?probe=a18593bb5b) | May 07, 2022 |
| Google        | Lulu                        | [18ecc4a6e7](https://linux-hardware.org/?probe=18ecc4a6e7) | May 07, 2022 |
| Dell          | Inspiron 5515               | [aa0534d7af](https://linux-hardware.org/?probe=aa0534d7af) | May 07, 2022 |
| Acer          | Aspire E1-570               | [53ddeaa413](https://linux-hardware.org/?probe=53ddeaa413) | May 07, 2022 |
| ASUSTek       | E200HA                      | [6fc7c6f086](https://linux-hardware.org/?probe=6fc7c6f086) | May 07, 2022 |
| Google        | Peppy                       | [03dc670128](https://linux-hardware.org/?probe=03dc670128) | May 06, 2022 |
| HP            | ProBook 450 G4              | [1332984f5d](https://linux-hardware.org/?probe=1332984f5d) | May 06, 2022 |
| Lenovo        | ThinkPad Twist 33472YU      | [710c086b29](https://linux-hardware.org/?probe=710c086b29) | May 06, 2022 |
| Lenovo        | ThinkPad Twist 33472YU      | [76fb8bb966](https://linux-hardware.org/?probe=76fb8bb966) | May 06, 2022 |
| Dell          | XPS 13 9300                 | [080b4f2667](https://linux-hardware.org/?probe=080b4f2667) | May 06, 2022 |
| Lenovo        | G50-80 80E5                 | [8ecadc1bad](https://linux-hardware.org/?probe=8ecadc1bad) | May 05, 2022 |
| HP            | Pavilion Notebook           | [af36cfb1a8](https://linux-hardware.org/?probe=af36cfb1a8) | May 05, 2022 |
| Acer          | Aspire V5-431               | [04db0db85f](https://linux-hardware.org/?probe=04db0db85f) | May 05, 2022 |
| Razer         | Blade 14 - RZ09-0370        | [fa323515aa](https://linux-hardware.org/?probe=fa323515aa) | May 05, 2022 |
| Dell          | Inspiron 1750               | [1c70ba9e33](https://linux-hardware.org/?probe=1c70ba9e33) | May 05, 2022 |
| Dell          | Latitude E5440              | [a505dc0b3c](https://linux-hardware.org/?probe=a505dc0b3c) | May 05, 2022 |
| ASUSTek       | GL552VX                     | [d153ef27fa](https://linux-hardware.org/?probe=d153ef27fa) | May 04, 2022 |
| Gigabyte      | P65                         | [0bbc07114a](https://linux-hardware.org/?probe=0bbc07114a) | May 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [a9f5b77476](https://linux-hardware.org/?probe=a9f5b77476) | May 04, 2022 |
| Acer          | Aspire A515-45              | [e5f3e5b086](https://linux-hardware.org/?probe=e5f3e5b086) | May 04, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [8bfd6ecc71](https://linux-hardware.org/?probe=8bfd6ecc71) | May 04, 2022 |
| HP            | Pavilion Laptop 15-cs1xx... | [ca91daf662](https://linux-hardware.org/?probe=ca91daf662) | May 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [720d11c11f](https://linux-hardware.org/?probe=720d11c11f) | May 04, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5a8fc607c4](https://linux-hardware.org/?probe=5a8fc607c4) | May 04, 2022 |
| Dell          | Inspiron 3583               | [f5e954ea5e](https://linux-hardware.org/?probe=f5e954ea5e) | May 04, 2022 |
| HP            | Pavilion 13 x360 PC         | [5de9e1d61f](https://linux-hardware.org/?probe=5de9e1d61f) | May 04, 2022 |
| ASUSTek       | X540SAA                     | [9943699a6b](https://linux-hardware.org/?probe=9943699a6b) | May 04, 2022 |
| Acer          | Aspire F5-573G              | [2136362d58](https://linux-hardware.org/?probe=2136362d58) | May 03, 2022 |
| HP            | Laptop 17-ca3xxx            | [373f22a70f](https://linux-hardware.org/?probe=373f22a70f) | May 03, 2022 |
| HP            | Laptop 17-ca3xxx            | [91a367d874](https://linux-hardware.org/?probe=91a367d874) | May 03, 2022 |
| HP            | ENVY dv6                    | [23ad3290c2](https://linux-hardware.org/?probe=23ad3290c2) | May 03, 2022 |
| Apple         | MacBookAir6,2               | [0f8065fda6](https://linux-hardware.org/?probe=0f8065fda6) | May 03, 2022 |
| ASUSTek       | GL552JX                     | [c91f42212d](https://linux-hardware.org/?probe=c91f42212d) | May 03, 2022 |
| ASUSTek       | ROG Strix G713RC_G713RC     | [2ce25fb058](https://linux-hardware.org/?probe=2ce25fb058) | May 03, 2022 |
| Dell          | Inspiron 3583               | [c47758f125](https://linux-hardware.org/?probe=c47758f125) | May 03, 2022 |
| Lenovo        | IdeaPad Slim 7 14ITL05 8... | [4b44c67cde](https://linux-hardware.org/?probe=4b44c67cde) | May 02, 2022 |
| Toshiba       | PORTEGE R830                | [8daebf6110](https://linux-hardware.org/?probe=8daebf6110) | May 02, 2022 |
| Dell          | Latitude E6440              | [d2ab063048](https://linux-hardware.org/?probe=d2ab063048) | May 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [58ff4a1984](https://linux-hardware.org/?probe=58ff4a1984) | May 02, 2022 |
| Toshiba       | Satellite L755              | [6c38249bc4](https://linux-hardware.org/?probe=6c38249bc4) | May 02, 2022 |
| Framework     | Laptop                      | [0d35134041](https://linux-hardware.org/?probe=0d35134041) | May 02, 2022 |
| Acer          | Aspire A515-45              | [8cf5364699](https://linux-hardware.org/?probe=8cf5364699) | May 02, 2022 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [02872ac9a8](https://linux-hardware.org/?probe=02872ac9a8) | May 02, 2022 |
| HP            | EliteBook 850 G3            | [ab86c0118b](https://linux-hardware.org/?probe=ab86c0118b) | May 02, 2022 |
| MSI           | GS65 Stealth 8SG            | [05f80b3e70](https://linux-hardware.org/?probe=05f80b3e70) | May 02, 2022 |
| System76      | Oryx Pro                    | [96251b761b](https://linux-hardware.org/?probe=96251b761b) | May 02, 2022 |
| Acer          | Aspire V5-573P              | [b64d1453d5](https://linux-hardware.org/?probe=b64d1453d5) | May 02, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [332445f774](https://linux-hardware.org/?probe=332445f774) | May 02, 2022 |
| MSI           | GP76 Leopard 11UG           | [dcea7cd8c0](https://linux-hardware.org/?probe=dcea7cd8c0) | May 02, 2022 |
| Dell          | Latitude E5570              | [372feb146c](https://linux-hardware.org/?probe=372feb146c) | May 02, 2022 |
| Apple         | MacBookPro12,1              | [5f68858e66](https://linux-hardware.org/?probe=5f68858e66) | May 01, 2022 |
| Acer          | Aspire 7750G                | [abd7ed0c5c](https://linux-hardware.org/?probe=abd7ed0c5c) | May 01, 2022 |
| LG Electro... | P430-G.BC41P1               | [527905ca3b](https://linux-hardware.org/?probe=527905ca3b) | May 01, 2022 |
| Apple         | MacBookPro4,1               | [be68c0201a](https://linux-hardware.org/?probe=be68c0201a) | May 01, 2022 |
| Apple         | MacBookPro7,1               | [ac3f2c5c61](https://linux-hardware.org/?probe=ac3f2c5c61) | May 01, 2022 |
| Apple         | MacBookPro4,1               | [83a8bbb313](https://linux-hardware.org/?probe=83a8bbb313) | May 01, 2022 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [48afcac3f0](https://linux-hardware.org/?probe=48afcac3f0) | May 01, 2022 |
| HP            | EliteBook 8440p             | [89a959efc4](https://linux-hardware.org/?probe=89a959efc4) | May 01, 2022 |
| HP            | ProBook 455 G7              | [88fcea9210](https://linux-hardware.org/?probe=88fcea9210) | Apr 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [48d3759522](https://linux-hardware.org/?probe=48d3759522) | Apr 30, 2022 |
| Apple         | MacBookPro8,1               | [8826e1d451](https://linux-hardware.org/?probe=8826e1d451) | Apr 30, 2022 |
| Toshiba       | Satellite L10W-B-101        | [8383d306f3](https://linux-hardware.org/?probe=8383d306f3) | Apr 30, 2022 |
| Dell          | XPS 13 9343                 | [b48ccc106e](https://linux-hardware.org/?probe=b48ccc106e) | Apr 30, 2022 |
| Toshiba       | IS 1413G                    | [8074a86bc7](https://linux-hardware.org/?probe=8074a86bc7) | Apr 30, 2022 |
| Dell          | XPS 15 9510                 | [b92517268e](https://linux-hardware.org/?probe=b92517268e) | Apr 30, 2022 |
| ASUSTek       | G55VW                       | [6bd8a1b04a](https://linux-hardware.org/?probe=6bd8a1b04a) | Apr 29, 2022 |
| Dell          | Inspiron 3542               | [19f5e16bce](https://linux-hardware.org/?probe=19f5e16bce) | Apr 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [61bb949815](https://linux-hardware.org/?probe=61bb949815) | Apr 29, 2022 |
| Dell          | G5 5500                     | [c6064853ad](https://linux-hardware.org/?probe=c6064853ad) | Apr 29, 2022 |
| Lenovo        | ThinkPad T480 20L50004UK    | [34015c4874](https://linux-hardware.org/?probe=34015c4874) | Apr 29, 2022 |
| ASUSTek       | X540SAA                     | [6c8e397ca3](https://linux-hardware.org/?probe=6c8e397ca3) | Apr 29, 2022 |
| System76      | Oryx Pro                    | [cf999d4581](https://linux-hardware.org/?probe=cf999d4581) | Apr 29, 2022 |
| Dell          | Inspiron 5547               | [a5d8e73a23](https://linux-hardware.org/?probe=a5d8e73a23) | Apr 28, 2022 |
| Dell          | Inspiron 5547               | [be4ab0fd27](https://linux-hardware.org/?probe=be4ab0fd27) | Apr 28, 2022 |
| Toshiba       | IS 1413G                    | [995f77010e](https://linux-hardware.org/?probe=995f77010e) | Apr 28, 2022 |
| Toshiba       | IS 1413G                    | [e2293170b3](https://linux-hardware.org/?probe=e2293170b3) | Apr 28, 2022 |
| Lenovo        | ThinkPad T431s 20ACS03P0... | [3c0878aee3](https://linux-hardware.org/?probe=3c0878aee3) | Apr 28, 2022 |
| System76      | Oryx Pro                    | [ae46ece731](https://linux-hardware.org/?probe=ae46ece731) | Apr 28, 2022 |
| HP            | Pavilion 15                 | [fee7e96d70](https://linux-hardware.org/?probe=fee7e96d70) | Apr 28, 2022 |
| Toshiba       | IS 1413G                    | [a63dc69025](https://linux-hardware.org/?probe=a63dc69025) | Apr 28, 2022 |
| HP            | Stream Laptop 14-ds0xxx     | [59a8e467c6](https://linux-hardware.org/?probe=59a8e467c6) | Apr 28, 2022 |
| Apple         | MacBookPro10,2              | [2d79aab0aa](https://linux-hardware.org/?probe=2d79aab0aa) | Apr 28, 2022 |
| ASUSTek       | K40IN                       | [ab6a95da52](https://linux-hardware.org/?probe=ab6a95da52) | Apr 28, 2022 |
| HP            | Pavilion 13 x360 PC         | [d48ed77abc](https://linux-hardware.org/?probe=d48ed77abc) | Apr 28, 2022 |
| Dell          | Inspiron 5566               | [695d362d8f](https://linux-hardware.org/?probe=695d362d8f) | Apr 27, 2022 |
| ASUSTek       | FX503VM                     | [c227966510](https://linux-hardware.org/?probe=c227966510) | Apr 27, 2022 |
| ASUSTek       | FX503VM                     | [1275aa643d](https://linux-hardware.org/?probe=1275aa643d) | Apr 27, 2022 |
| HP            | ENVY Laptop 14-eb0xxx       | [495a74c914](https://linux-hardware.org/?probe=495a74c914) | Apr 27, 2022 |
| Dell          | XPS 13 9310                 | [d394f4e0d9](https://linux-hardware.org/?probe=d394f4e0d9) | Apr 27, 2022 |
| HUAWEI        | HVY-WXX9                    | [824ccc1317](https://linux-hardware.org/?probe=824ccc1317) | Apr 27, 2022 |
| HP            | Pavilion 13 x360 PC         | [3e5933fe0d](https://linux-hardware.org/?probe=3e5933fe0d) | Apr 27, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [e51ff27a5a](https://linux-hardware.org/?probe=e51ff27a5a) | Apr 27, 2022 |
| Dell          | Vostro 15 3515              | [7c99d7d4c5](https://linux-hardware.org/?probe=7c99d7d4c5) | Apr 27, 2022 |
| Lenovo        | ThinkPad T480 20L6SJN400    | [294a5ef80c](https://linux-hardware.org/?probe=294a5ef80c) | Apr 27, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [863612cc05](https://linux-hardware.org/?probe=863612cc05) | Apr 27, 2022 |
| Purism        | Librem 15 v3                | [d2a13c9d0a](https://linux-hardware.org/?probe=d2a13c9d0a) | Apr 27, 2022 |
| Toshiba       | Satellite C55t-C            | [1fe2032839](https://linux-hardware.org/?probe=1fe2032839) | Apr 27, 2022 |
| Toshiba       | Satellite C55t-C            | [cabf0c7464](https://linux-hardware.org/?probe=cabf0c7464) | Apr 27, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [b7ac79ff8f](https://linux-hardware.org/?probe=b7ac79ff8f) | Apr 27, 2022 |
| MSI           | GS66 Stealth 10UG           | [77b699045a](https://linux-hardware.org/?probe=77b699045a) | Apr 27, 2022 |
| Dell          | XPS 13 9305                 | [edf60be002](https://linux-hardware.org/?probe=edf60be002) | Apr 26, 2022 |
| Acer          | Aspire E1-570               | [1621e22812](https://linux-hardware.org/?probe=1621e22812) | Apr 26, 2022 |
| Acer          | Swift SF316-51              | [fe42983639](https://linux-hardware.org/?probe=fe42983639) | Apr 26, 2022 |
| MSI           | GF63 Thin 10SC              | [bc3cbdbc1f](https://linux-hardware.org/?probe=bc3cbdbc1f) | Apr 26, 2022 |
| Acer          | TravelMate P249-G2-MG       | [2e0bd790c6](https://linux-hardware.org/?probe=2e0bd790c6) | Apr 26, 2022 |
| ASUSTek       | X455LD                      | [9f98b410f6](https://linux-hardware.org/?probe=9f98b410f6) | Apr 26, 2022 |
| Dell          | Inspiron 3442               | [d4b7580074](https://linux-hardware.org/?probe=d4b7580074) | Apr 26, 2022 |
| Dell          | Inspiron 3442               | [d994ff2a13](https://linux-hardware.org/?probe=d994ff2a13) | Apr 26, 2022 |
| Unknown       | Unknown                     | [885f468161](https://linux-hardware.org/?probe=885f468161) | Apr 26, 2022 |
| Acer          | Aspire A315-41              | [a42b1cda2c](https://linux-hardware.org/?probe=a42b1cda2c) | Apr 26, 2022 |
| ASUSTek       | X555LF                      | [0aa3a88c0c](https://linux-hardware.org/?probe=0aa3a88c0c) | Apr 25, 2022 |
| HP            | ENVY Laptop 17-ch0xxx       | [256f703e7e](https://linux-hardware.org/?probe=256f703e7e) | Apr 25, 2022 |
| Acer          | Nitro AN515-53              | [8a96f457bb](https://linux-hardware.org/?probe=8a96f457bb) | Apr 25, 2022 |
| MSI           | Katana GF76 11UD            | [2e4a211c66](https://linux-hardware.org/?probe=2e4a211c66) | Apr 24, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [743177a467](https://linux-hardware.org/?probe=743177a467) | Apr 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [803959fe3c](https://linux-hardware.org/?probe=803959fe3c) | Apr 24, 2022 |
| Dell          | Inspiron 5559               | [e9676d63f9](https://linux-hardware.org/?probe=e9676d63f9) | Apr 24, 2022 |
| ASUSTek       | X450LCP                     | [a2ed4903be](https://linux-hardware.org/?probe=a2ed4903be) | Apr 23, 2022 |
| Acer          | Aspire 1410                 | [0399a90ade](https://linux-hardware.org/?probe=0399a90ade) | Apr 23, 2022 |
| Apple         | MacBookPro6,1               | [e73885a94d](https://linux-hardware.org/?probe=e73885a94d) | Apr 23, 2022 |
| ASUSTek       | UX32VD                      | [6f956cd55c](https://linux-hardware.org/?probe=6f956cd55c) | Apr 23, 2022 |
| Apple         | MacBookPro10,2              | [477b1e873f](https://linux-hardware.org/?probe=477b1e873f) | Apr 23, 2022 |
| Toshiba       | Satellite L50D-B            | [f283519d44](https://linux-hardware.org/?probe=f283519d44) | Apr 22, 2022 |
| ASUSTek       | GL552JX                     | [dae470212d](https://linux-hardware.org/?probe=dae470212d) | Apr 22, 2022 |
| ASUSTek       | X541UJ                      | [4043c70a42](https://linux-hardware.org/?probe=4043c70a42) | Apr 22, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [2c48c81559](https://linux-hardware.org/?probe=2c48c81559) | Apr 22, 2022 |
| Apple         | MacBookPro10,2              | [9936062b3c](https://linux-hardware.org/?probe=9936062b3c) | Apr 22, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Pop!_OS 20.04 | 1145      | 26.78%  |
| Pop!_OS 21.04 | 955       | 22.34%  |
| Pop!_OS 20.10 | 856       | 20.02%  |
| Pop!_OS 22.04 | 674       | 15.77%  |
| Pop!_OS 21.10 | 598       | 13.99%  |
| Pop!_OS 19.10 | 30        | 0.7%    |
| Pop!_OS 18.04 | 7         | 0.16%   |
| Pop!_OS 19.04 | 6         | 0.14%   |
| Pop!_OS 18.10 | 4         | 0.09%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Pop!_OS | 4056      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.11.0-7620-generic      | 441       | 9.76%   |
| 5.8.0-7630-generic       | 381       | 8.43%   |
| 5.4.0-7634-generic       | 346       | 7.66%   |
| 5.13.0-7614-generic      | 262       | 5.8%    |
| 5.4.0-7642-generic       | 256       | 5.67%   |
| 5.8.0-7642-generic       | 242       | 5.36%   |
| 5.17.5-76051705-generic  | 239       | 5.29%   |
| 5.11.0-7614-generic      | 227       | 5.03%   |
| 5.13.0-7620-generic      | 217       | 4.8%    |
| 5.19.0-76051900-generic  | 185       | 4.1%    |
| 5.15.15-76051515-generic | 154       | 3.41%   |
| 5.16.11-76051611-generic | 138       | 3.06%   |
| 5.11.0-7612-generic      | 127       | 2.81%   |
| 5.15.5-76051505-generic  | 122       | 2.7%    |
| 5.18.10-76051810-generic | 109       | 2.41%   |
| 5.8.0-7625-generic       | 105       | 2.32%   |
| 5.17.15-76051715-generic | 104       | 2.3%    |
| 5.11.0-7633-generic      | 99        | 2.19%   |
| 5.15.8-76051508-generic  | 98        | 2.17%   |
| 5.16.19-76051619-generic | 95        | 2.1%    |
| 5.16.15-76051615-generic | 91        | 2.01%   |
| 5.4.0-7626-generic       | 84        | 1.86%   |
| 5.15.11-76051511-generic | 59        | 1.31%   |
| 5.15.23-76051523-generic | 56        | 1.24%   |
| 5.4.0-7625-generic       | 44        | 0.97%   |
| 5.4.0-7629-generic       | 35        | 0.77%   |
| 5.3.0-7625-generic       | 10        | 0.22%   |
| 5.3.0-7648-generic       | 6         | 0.13%   |
| 5.11.0-051100-generic    | 6         | 0.13%   |
| 5.3.0-7642-generic       | 4         | 0.09%   |
| 5.3.0-7629-generic       | 4         | 0.09%   |
| 5.3.0-20-generic         | 4         | 0.09%   |
| 5.7.1-050701-generic     | 3         | 0.07%   |
| 4.18.0-16-generic        | 3         | 0.07%   |
| 5.9.12-xanmod1           | 2         | 0.04%   |
| 5.8.9-050809-generic     | 2         | 0.04%   |
| 5.8.6-xanmod1            | 2         | 0.04%   |
| 5.8.11-050811-generic    | 2         | 0.04%   |
| 5.8.1-050801-generic     | 2         | 0.04%   |
| 5.7.15-050715-generic    | 2         | 0.04%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 872       | 19.76%  |
| 5.4.0   | 744       | 16.86%  |
| 5.8.0   | 698       | 15.81%  |
| 5.13.0  | 466       | 10.56%  |
| 5.17.5  | 242       | 5.48%   |
| 5.19.0  | 186       | 4.21%   |
| 5.15.15 | 154       | 3.49%   |
| 5.16.11 | 138       | 3.13%   |
| 5.15.5  | 122       | 2.76%   |
| 5.18.10 | 109       | 2.47%   |
| 5.17.15 | 104       | 2.36%   |
| 5.15.8  | 98        | 2.22%   |
| 5.16.19 | 95        | 2.15%   |
| 5.16.15 | 91        | 2.06%   |
| 5.15.11 | 59        | 1.34%   |
| 5.15.23 | 56        | 1.27%   |
| 5.3.0   | 32        | 0.72%   |
| 5.0.0   | 6         | 0.14%   |
| 4.18.0  | 6         | 0.14%   |
| 5.7.0   | 4         | 0.09%   |
| 5.8.6   | 3         | 0.07%   |
| 5.8.11  | 3         | 0.07%   |
| 5.7.1   | 3         | 0.07%   |
| 5.15.0  | 3         | 0.07%   |
| 5.14.0  | 3         | 0.07%   |
| 5.12.14 | 3         | 0.07%   |
| 5.10.0  | 3         | 0.07%   |
| 6.0.0   | 2         | 0.05%   |
| 5.9.12  | 2         | 0.05%   |
| 5.8.9   | 2         | 0.05%   |
| 5.8.1   | 2         | 0.05%   |
| 5.7.15  | 2         | 0.05%   |
| 5.6.7   | 2         | 0.05%   |
| 5.6.16  | 2         | 0.05%   |
| 5.15.4  | 2         | 0.05%   |
| 5.14.10 | 2         | 0.05%   |
| 5.13.4  | 2         | 0.05%   |
| 5.13.13 | 2         | 0.05%   |
| 5.13.12 | 2         | 0.05%   |
| 5.12.12 | 2         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 878       | 20.02%  |
| 5.4     | 745       | 16.99%  |
| 5.8     | 712       | 16.24%  |
| 5.15    | 487       | 11.11%  |
| 5.13    | 477       | 10.88%  |
| 5.17    | 345       | 7.87%   |
| 5.16    | 322       | 7.34%   |
| 5.19    | 187       | 4.26%   |
| 5.18    | 113       | 2.58%   |
| 5.3     | 32        | 0.73%   |
| 5.10    | 18        | 0.41%   |
| 5.12    | 13        | 0.3%    |
| 5.7     | 11        | 0.25%   |
| 5.14    | 11        | 0.25%   |
| 5.9     | 9         | 0.21%   |
| 5.6     | 7         | 0.16%   |
| 4.18    | 7         | 0.16%   |
| 5.0     | 6         | 0.14%   |
| 6.0     | 2         | 0.05%   |
| 4.15    | 2         | 0.05%   |
| 4.9     | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 4056      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 3919      | 96.03%  |
| KDE5            | 36        | 0.88%   |
| Unknown         | 35        | 0.86%   |
| KDE             | 25        | 0.61%   |
| X-Cinnamon      | 15        | 0.37%   |
| GNOME Flashback | 10        | 0.25%   |
| XFCE            | 9         | 0.22%   |
| MATE            | 8         | 0.2%    |
| LXQt            | 8         | 0.2%    |
| Cinnamon        | 6         | 0.15%   |
| Unity           | 4         | 0.1%    |
| Budgie          | 4         | 0.1%    |
| Deepin          | 1         | 0.02%   |
| awesome         | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 3934      | 96.54%  |
| Wayland | 120       | 2.94%   |
| Unknown | 14        | 0.34%   |
| Tty     | 7         | 0.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 3141      | 76.7%   |
| GDM     | 769       | 18.78%  |
| GDM3    | 173       | 4.22%   |
| SDDM    | 6         | 0.15%   |
| TDM     | 5         | 0.12%   |
| LightDM | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 2341      | 57.36%  |
| pt_BR   | 313       | 7.67%   |
| en_GB   | 290       | 7.11%   |
| de_DE   | 170       | 4.17%   |
| C       | 101       | 2.47%   |
| en_AU   | 88        | 2.16%   |
| fr_FR   | 85        | 2.08%   |
| es_ES   | 84        | 2.06%   |
| en_CA   | 78        | 1.91%   |
| it_IT   | 75        | 1.84%   |
| ru_RU   | 59        | 1.45%   |
| Unknown | 46        | 1.13%   |
| pt_PT   | 38        | 0.93%   |
| pl_PL   | 36        | 0.88%   |
| sv_SE   | 28        | 0.69%   |
| en_IN   | 25        | 0.61%   |
| nl_NL   | 17        | 0.42%   |
| en_ZA   | 16        | 0.39%   |
| nb_NO   | 14        | 0.34%   |
| es_MX   | 14        | 0.34%   |
| fi_FI   | 11        | 0.27%   |
| tr_TR   | 10        | 0.25%   |
| hr_HR   | 8         | 0.2%    |
| fr_CA   | 8         | 0.2%    |
| es_AR   | 8         | 0.2%    |
| en_NZ   | 8         | 0.2%    |
| en_DK   | 8         | 0.2%    |
| hu_HU   | 7         | 0.17%   |
| da_DK   | 7         | 0.17%   |
| ro_RO   | 6         | 0.15%   |
| cs_CZ   | 6         | 0.15%   |
| sk_SK   | 5         | 0.12%   |
| es_CL   | 5         | 0.12%   |
| de_CH   | 5         | 0.12%   |
| zh_CN   | 4         | 0.1%    |
| nl_BE   | 4         | 0.1%    |
| es_CO   | 4         | 0.1%    |
| en_IE   | 4         | 0.1%    |
| zh_TW   | 3         | 0.07%   |
| es_PE   | 3         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 2864      | 69.5%   |
| EFI  | 1257      | 30.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 3898      | 95.82%  |
| Btrfs   | 89        | 2.19%   |
| Overlay | 57        | 1.4%    |
| Xfs     | 17        | 0.42%   |
| Unknown | 7         | 0.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 3114      | 76.12%  |
| GPT     | 883       | 21.58%  |
| MBR     | 94        | 2.3%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3966      | 97.56%  |
| Yes       | 99        | 2.44%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3708      | 90.97%  |
| Yes       | 368       | 9.03%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 782       | 19.28%  |
| Dell                   | 733       | 18.07%  |
| Hewlett-Packard        | 541       | 13.34%  |
| ASUSTek Computer       | 468       | 11.54%  |
| Acer                   | 328       | 8.09%   |
| Apple                  | 223       | 5.5%    |
| System76               | 151       | 3.72%   |
| MSI                    | 138       | 3.4%    |
| Toshiba                | 86        | 2.12%   |
| Samsung Electronics    | 74        | 1.82%   |
| HUAWEI                 | 49        | 1.21%   |
| Sony                   | 43        | 1.06%   |
| Notebook               | 40        | 0.99%   |
| Alienware              | 30        | 0.74%   |
| Google                 | 29        | 0.71%   |
| Positivo               | 23        | 0.57%   |
| Fujitsu                | 23        | 0.57%   |
| Razer                  | 18        | 0.44%   |
| PC Specialist          | 15        | 0.37%   |
| Timi                   | 13        | 0.32%   |
| Gigabyte Technology    | 13        | 0.32%   |
| TUXEDO                 | 11        | 0.27%   |
| Medion                 | 11        | 0.27%   |
| LG Electronics         | 11        | 0.27%   |
| Packard Bell           | 9         | 0.22%   |
| GPU Company            | 9         | 0.22%   |
| Framework              | 9         | 0.22%   |
| Unknown                | 9         | 0.22%   |
| Eluktronics            | 7         | 0.17%   |
| Teclast                | 6         | 0.15%   |
| Panasonic              | 6         | 0.15%   |
| Gateway                | 6         | 0.15%   |
| Avell High Performance | 6         | 0.15%   |
| Intel                  | 5         | 0.12%   |
| Chuwi                  | 5         | 0.12%   |
| SLIMBOOK               | 4         | 0.1%    |
| Schenker               | 4         | 0.1%    |
| Quanta                 | 4         | 0.1%    |
| MOTILE                 | 4         | 0.1%    |
| HASEE Computer         | 4         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| System76 Oryx Pro                         | 38        | 0.94%   |
| System76 Lemur Pro                        | 29        | 0.71%   |
| Dell XPS 15 7590                          | 27        | 0.67%   |
| Apple MacBookPro9,2                       | 21        | 0.52%   |
| Unknown                                   | 20        | 0.49%   |
| System76 Galago Pro                       | 19        | 0.47%   |
| HP Pavilion Notebook                      | 19        | 0.47%   |
| Dell XPS 15 9500                          | 19        | 0.47%   |
| System76 Gazelle                          | 17        | 0.42%   |
| System76 Darter Pro                       | 16        | 0.39%   |
| Apple MacBookPro8,1                       | 16        | 0.39%   |
| HP Pavilion 15                            | 14        | 0.35%   |
| HP Notebook                               | 14        | 0.35%   |
| Dell XPS 15 9560                          | 14        | 0.35%   |
| HP Pavilion dv6                           | 13        | 0.32%   |
| Apple MacBookPro12,1                      | 13        | 0.32%   |
| Dell XPS 15 9570                          | 12        | 0.3%    |
| Dell Latitude E6420                       | 12        | 0.3%    |
| Apple MacBookAir7,2                       | 12        | 0.3%    |
| Lenovo IdeaPad S145-15API 81V7            | 11        | 0.27%   |
| Dell XPS 17 9700                          | 11        | 0.27%   |
| Dell XPS 13 9380                          | 11        | 0.27%   |
| Apple MacBookPro7,1                       | 11        | 0.27%   |
| Apple MacBookPro5,5                       | 11        | 0.27%   |
| Apple MacBookAir6,2                       | 11        | 0.27%   |
| Dell Inspiron N5110                       | 10        | 0.25%   |
| ASUS TUF Gaming FX505DT_FX505DT           | 10        | 0.25%   |
| Acer Aspire E5-575G                       | 10        | 0.25%   |
| Samsung 340XAA/350XAA/550XAA              | 9         | 0.22%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QVCTO1WW | 9         | 0.22%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY      | 9         | 0.22%   |
| HP Pavilion Laptop 15-cw1xxx              | 9         | 0.22%   |
| Framework Laptop                          | 9         | 0.22%   |
| Dell Latitude E7470                       | 9         | 0.22%   |
| Dell Latitude E7240                       | 9         | 0.22%   |
| Dell Inspiron 3542                        | 9         | 0.22%   |
| Acer Aspire A315-42                       | 9         | 0.22%   |
| Lenovo IdeaPad 330-15IKB 81FE             | 8         | 0.2%    |
| HP Pavilion g6                            | 8         | 0.2%    |
| HP EliteBook 840 G1                       | 8         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 391       | 9.64%   |
| Dell Inspiron      | 244       | 6.02%   |
| Acer Aspire        | 230       | 5.67%   |
| Lenovo IdeaPad     | 214       | 5.28%   |
| Dell Latitude      | 175       | 4.31%   |
| Dell XPS           | 159       | 3.92%   |
| HP Pavilion        | 138       | 3.4%    |
| HP EliteBook       | 84        | 2.07%   |
| HP Laptop          | 76        | 1.87%   |
| Toshiba Satellite  | 74        | 1.82%   |
| ASUS ROG           | 67        | 1.65%   |
| ASUS VivoBook      | 63        | 1.55%   |
| HP ProBook         | 62        | 1.53%   |
| Lenovo Legion      | 55        | 1.36%   |
| Dell Precision     | 48        | 1.18%   |
| Dell Vostro        | 44        | 1.08%   |
| Acer Nitro         | 40        | 0.99%   |
| System76 Oryx      | 38        | 0.94%   |
| System76 Lemur     | 32        | 0.79%   |
| ASUS ASUS          | 31        | 0.76%   |
| ASUS TUF           | 29        | 0.71%   |
| Apple MacBookPro9  | 28        | 0.69%   |
| HP ENVY            | 26        | 0.64%   |
| Apple MacBookPro11 | 26        | 0.64%   |
| HP OMEN            | 25        | 0.62%   |
| Acer Swift         | 25        | 0.62%   |
| Apple MacBookPro8  | 23        | 0.57%   |
| System76 Galago    | 22        | 0.54%   |
| ASUS ZenBook       | 22        | 0.54%   |
| Apple MacBookPro5  | 20        | 0.49%   |
| Unknown            | 20        | 0.49%   |
| System76 Gazelle   | 19        | 0.47%   |
| Lenovo ThinkBook   | 19        | 0.47%   |
| Razer Blade        | 18        | 0.44%   |
| Fujitsu LIFEBOOK   | 17        | 0.42%   |
| System76 Darter    | 16        | 0.39%   |
| Lenovo Yoga        | 16        | 0.39%   |
| HP ZBook           | 14        | 0.35%   |
| HP Notebook        | 14        | 0.35%   |
| HP Compaq          | 14        | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 545       | 13.44%  |
| 2020    | 498       | 12.28%  |
| 2018    | 406       | 10.01%  |
| 2021    | 361       | 8.9%    |
| 2012    | 304       | 7.5%    |
| 2013    | 270       | 6.66%   |
| 2017    | 265       | 6.53%   |
| 2011    | 259       | 6.39%   |
| 2015    | 248       | 6.11%   |
| 2016    | 219       | 5.4%    |
| 2014    | 208       | 5.13%   |
| 2010    | 169       | 4.17%   |
| 2009    | 105       | 2.59%   |
| 2008    | 97        | 2.39%   |
| 2022    | 56        | 1.38%   |
| 2007    | 33        | 0.81%   |
| 2006    | 9         | 0.22%   |
| Unknown | 2         | 0.05%   |
| 2005    | 1         | 0.02%   |
| 2004    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 4056      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 4053      | 99.93%  |
| Enabled  | 3         | 0.07%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3937      | 97.07%  |
| Yes  | 119       | 2.93%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1200      | 29.35%  |
| 16.01-24.0  | 915       | 22.38%  |
| 8.01-16.0   | 755       | 18.46%  |
| 3.01-4.0    | 641       | 15.68%  |
| 32.01-64.0  | 354       | 8.66%   |
| 64.01-256.0 | 80        | 1.96%   |
| 1.01-2.0    | 66        | 1.61%   |
| 24.01-32.0  | 47        | 1.15%   |
| 2.01-3.0    | 31        | 0.76%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 1444      | 32.85%  |
| 1.01-2.0   | 1241      | 28.23%  |
| 3.01-4.0   | 780       | 17.74%  |
| 4.01-8.0   | 732       | 16.65%  |
| 8.01-16.0  | 165       | 3.75%   |
| 16.01-24.0 | 18        | 0.41%   |
| 0.51-1.0   | 10        | 0.23%   |
| 24.01-32.0 | 5         | 0.11%   |
| 0.01-0.5   | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2844      | 68.98%  |
| 2      | 1095      | 26.56%  |
| 3      | 138       | 3.35%   |
| 0      | 20        | 0.49%   |
| 4      | 18        | 0.44%   |
| 5      | 6         | 0.15%   |
| 7      | 1         | 0.02%   |
| 6      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2869      | 70.53%  |
| Yes       | 1199      | 29.47%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3286      | 80.6%   |
| No        | 791       | 19.4%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4012      | 98.84%  |
| No        | 47        | 1.16%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3424      | 83.63%  |
| No        | 670       | 16.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 1086      | 26.66%  |
| Brazil       | 437       | 10.73%  |
| Germany      | 247       | 6.06%   |
| UK           | 178       | 4.37%   |
| India        | 176       | 4.32%   |
| Canada       | 146       | 3.58%   |
| France       | 122       | 2.99%   |
| Italy        | 113       | 2.77%   |
| Australia    | 97        | 2.38%   |
| Netherlands  | 84        | 2.06%   |
| Russia       | 76        | 1.87%   |
| Sweden       | 70        | 1.72%   |
| Spain        | 62        | 1.52%   |
| Poland       | 60        | 1.47%   |
| Mexico       | 60        | 1.47%   |
| Portugal     | 57        | 1.4%    |
| Romania      | 50        | 1.23%   |
| Switzerland  | 43        | 1.06%   |
| South Africa | 41        | 1.01%   |
| Norway       | 41        | 1.01%   |
| Turkey       | 33        | 0.81%   |
| Greece       | 32        | 0.79%   |
| Belgium      | 32        | 0.79%   |
| Philippines  | 31        | 0.76%   |
| Finland      | 30        | 0.74%   |
| Argentina    | 30        | 0.74%   |
| Indonesia    | 28        | 0.69%   |
| Denmark      | 28        | 0.69%   |
| Austria      | 28        | 0.69%   |
| New Zealand  | 25        | 0.61%   |
| Croatia      | 22        | 0.54%   |
| Chile        | 21        | 0.52%   |
| Malaysia     | 19        | 0.47%   |
| Colombia     | 19        | 0.47%   |
| Vietnam      | 17        | 0.42%   |
| Hungary      | 17        | 0.42%   |
| Czechia      | 17        | 0.42%   |
| Ukraine      | 16        | 0.39%   |
| Ireland      | 16        | 0.39%   |
| Bulgaria     | 16        | 0.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 48        | 1.13%   |
| Brisbane       | 26        | 0.61%   |
| Bengaluru      | 26        | 0.61%   |
| Sydney         | 24        | 0.57%   |
| Rio de Janeiro | 22        | 0.52%   |
| Paris          | 22        | 0.52%   |
| Milan          | 21        | 0.5%    |
| Dallas         | 21        | 0.5%    |
| Bucharest      | 20        | 0.47%   |
| Vienna         | 19        | 0.45%   |
| Moscow         | 19        | 0.45%   |
| London         | 19        | 0.45%   |
| Melbourne      | 18        | 0.42%   |
| Zagreb         | 17        | 0.4%    |
| New York       | 17        | 0.4%    |
| Athens         | 17        | 0.4%    |
| Madrid         | 16        | 0.38%   |
| Berlin         | 16        | 0.38%   |
| Amsterdam      | 16        | 0.38%   |
| Warsaw         | 15        | 0.35%   |
| Johannesburg   | 15        | 0.35%   |
| Stockholm      | 14        | 0.33%   |
| Rome           | 14        | 0.33%   |
| Mexico City    | 14        | 0.33%   |
| Los Angeles    | 14        | 0.33%   |
| Helsinki       | 14        | 0.33%   |
| Zurich         | 13        | 0.31%   |
| Toronto        | 13        | 0.31%   |
| Oslo           | 13        | 0.31%   |
| Istanbul       | 13        | 0.31%   |
| Fortaleza      | 13        | 0.31%   |
| Brasília      | 13        | 0.31%   |
| Auckland       | 13        | 0.31%   |
| St Petersburg  | 12        | 0.28%   |
| Sofia          | 12        | 0.28%   |
| Hyderabad      | 12        | 0.28%   |
| Chicago        | 12        | 0.28%   |
| Buenos Aires   | 12        | 0.28%   |
| Brooklyn       | 12        | 0.28%   |
| Singapore      | 11        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 940       | 1257   | 17.98%  |
| WDC                            | 565       | 643    | 10.81%  |
| Seagate                        | 537       | 631    | 10.27%  |
| SanDisk                        | 369       | 479    | 7.06%   |
| Toshiba                        | 351       | 411    | 6.71%   |
| Kingston                       | 289       | 343    | 5.53%   |
| Unknown                        | 248       | 299    | 4.74%   |
| SK hynix                       | 244       | 311    | 4.67%   |
| Crucial                        | 183       | 214    | 3.5%    |
| Intel                          | 163       | 201    | 3.12%   |
| HGST                           | 161       | 186    | 3.08%   |
| Micron Technology              | 124       | 137    | 2.37%   |
| Apple                          | 105       | 112    | 2.01%   |
| Hitachi                        | 88        | 95     | 1.68%   |
| A-DATA Technology              | 79        | 95     | 1.51%   |
| Phison                         | 70        | 87     | 1.34%   |
| LITEON                         | 39        | 44     | 0.75%   |
| PNY                            | 38        | 42     | 0.73%   |
| China                          | 38        | 42     | 0.73%   |
| Silicon Motion                 | 35        | 42     | 0.67%   |
| Transcend                      | 30        | 34     | 0.57%   |
| KIOXIA                         | 28        | 34     | 0.54%   |
| Micron/Crucial Technology      | 26        | 36     | 0.5%    |
| LITEONIT                       | 26        | 33     | 0.5%    |
| ADATA Technology               | 21        | 30     | 0.4%    |
| Fujitsu                        | 18        | 19     | 0.34%   |
| Team                           | 17        | 21     | 0.33%   |
| SPCC                           | 15        | 16     | 0.29%   |
| KingSpec                       | 14        | 15     | 0.27%   |
| JMicron Technology             | 14        | 20     | 0.27%   |
| Union Memory (Shenzhen)        | 12        | 15     | 0.23%   |
| Solid State Storage Technology | 12        | 15     | 0.23%   |
| Patriot                        | 12        | 12     | 0.23%   |
| OCZ                            | 12        | 12     | 0.23%   |
| Corsair                        | 12        | 14     | 0.23%   |
| Hewlett-Packard                | 11        | 13     | 0.21%   |
| Lexar                          | 9         | 9      | 0.17%   |
| XPG                            | 8         | 9      | 0.15%   |
| UMIS                           | 8         | 8      | 0.15%   |
| Realtek Semiconductor          | 8         | 8      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB     | 90        | 1.65%   |
| Samsung NVMe SSD Drive 512GB       | 80        | 1.46%   |
| Kingston SA400S37240G 240GB SSD    | 75        | 1.37%   |
| HGST HTS721010A9E630 1TB           | 68        | 1.24%   |
| Samsung NVMe SSD Drive 1TB         | 64        | 1.17%   |
| Unknown MMC Card  64GB             | 62        | 1.13%   |
| SK hynix NVMe SSD Drive 512GB      | 59        | 1.08%   |
| Samsung NVMe SSD Drive 256GB       | 57        | 1.04%   |
| Toshiba MQ01ABD100 1TB             | 52        | 0.95%   |
| Samsung NVMe SSD Drive 500GB       | 52        | 0.95%   |
| SanDisk NVMe SSD Drive 512GB       | 51        | 0.93%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 50        | 0.91%   |
| Intel NVMe SSD Drive 512GB         | 47        | 0.86%   |
| Unknown MMC Card  32GB             | 43        | 0.79%   |
| Toshiba MQ04ABF100 1TB             | 42        | 0.77%   |
| Samsung NVMe SSD Drive 1024GB      | 40        | 0.73%   |
| WDC WD10SPZX-24Z10 1TB             | 37        | 0.68%   |
| SanDisk NVMe SSD Drive 1TB         | 36        | 0.66%   |
| Seagate ST9500325AS 500GB          | 34        | 0.62%   |
| SanDisk NVMe SSD Drive 256GB       | 34        | 0.62%   |
| Samsung SSD 860 EVO 500GB          | 32        | 0.59%   |
| SK hynix NVMe SSD Drive 1024GB     | 31        | 0.57%   |
| WDC WD10SPZX-21Z10T0 1TB           | 30        | 0.55%   |
| Seagate ST1000LM049-2GH172 1TB     | 30        | 0.55%   |
| SK hynix NVMe SSD Drive 256GB      | 29        | 0.53%   |
| Toshiba NVMe SSD Drive 512GB       | 28        | 0.51%   |
| Seagate ST500LT012-1DG142 500GB    | 28        | 0.51%   |
| SanDisk NVMe SSD Drive 500GB       | 28        | 0.51%   |
| Samsung SSD 850 EVO 250GB          | 28        | 0.51%   |
| Kingston SA400S37480G 480GB SSD    | 27        | 0.49%   |
| Crucial CT500MX500SSD1 500GB       | 27        | 0.49%   |
| Samsung NVMe SSD Drive 2TB         | 26        | 0.48%   |
| Micron NVMe SSD Drive 512GB        | 26        | 0.48%   |
| Kingston SA400S37120G 120GB SSD    | 26        | 0.48%   |
| HGST HTS541010A9E680 1TB           | 26        | 0.48%   |
| Unknown MMC Card  128GB            | 25        | 0.46%   |
| Samsung SSD 860 EVO 1TB            | 25        | 0.46%   |
| Samsung SSD 850 EVO 500GB          | 23        | 0.42%   |
| Samsung NVMe SSD Drive 250GB       | 23        | 0.42%   |
| Intel NVMe SSD Drive 1024GB        | 23        | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 513       | 591    | 35.72%  |
| WDC                 | 355       | 387    | 24.72%  |
| Toshiba             | 221       | 248    | 15.39%  |
| HGST                | 161       | 186    | 11.21%  |
| Hitachi             | 88        | 95     | 6.13%   |
| Samsung Electronics | 28        | 29     | 1.95%   |
| Unknown             | 22        | 24     | 1.53%   |
| Fujitsu             | 18        | 19     | 1.25%   |
| Apple               | 15        | 15     | 1.04%   |
| JMicron Technology  | 2         | 5      | 0.14%   |
| Intenso             | 2         | 2      | 0.14%   |
| ASMT                | 2         | 3      | 0.14%   |
| USB3.0              | 1         | 1      | 0.07%   |
| SATAFIRM            | 1         | 1      | 0.07%   |
| SABRENT             | 1         | 2      | 0.07%   |
| RSH-339             | 1         | 1      | 0.07%   |
| PHD 3.0             | 1         | 1      | 0.07%   |
| Inateck             | 1         | 1      | 0.07%   |
| HGST HDN            | 1         | 1      | 0.07%   |
| DAS                 | 1         | 4      | 0.07%   |
| Asm                 | 1         | 1      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 405       | 517    | 22.24%  |
| Kingston            | 222       | 247    | 12.19%  |
| SanDisk             | 188       | 227    | 10.32%  |
| Crucial             | 169       | 200    | 9.28%   |
| WDC                 | 115       | 140    | 6.32%   |
| Apple               | 75        | 79     | 4.12%   |
| A-DATA Technology   | 56        | 66     | 3.08%   |
| SK hynix            | 47        | 54     | 2.58%   |
| Micron Technology   | 47        | 50     | 2.58%   |
| Toshiba             | 44        | 54     | 2.42%   |
| PNY                 | 38        | 42     | 2.09%   |
| LITEON              | 37        | 42     | 2.03%   |
| Intel               | 37        | 39     | 2.03%   |
| China               | 37        | 41     | 2.03%   |
| Transcend           | 29        | 33     | 1.59%   |
| LITEONIT            | 26        | 33     | 1.43%   |
| SPCC                | 15        | 16     | 0.82%   |
| Seagate             | 14        | 15     | 0.77%   |
| KingSpec            | 13        | 14     | 0.71%   |
| Patriot             | 12        | 12     | 0.66%   |
| OCZ                 | 12        | 12     | 0.66%   |
| Team                | 11        | 15     | 0.6%    |
| Corsair             | 9         | 10     | 0.49%   |
| Lexar               | 8         | 8      | 0.44%   |
| Hewlett-Packard     | 8         | 10     | 0.44%   |
| Netac               | 6         | 6      | 0.33%   |
| KingDian            | 6         | 7      | 0.33%   |
| Dogfish             | 6         | 8      | 0.33%   |
| BHT                 | 6         | 6      | 0.33%   |
| Apacer              | 6         | 8      | 0.33%   |
| TO Exter            | 5         | 5      | 0.27%   |
| Plextor             | 5         | 7      | 0.27%   |
| GOODRAM             | 5         | 6      | 0.27%   |
| Mushkin             | 4         | 4      | 0.22%   |
| Maxtor              | 4         | 4      | 0.22%   |
| Gigabyte Technology | 4         | 6      | 0.22%   |
| ASMT                | 4         | 4      | 0.22%   |
| Unknown             | 3         | 3      | 0.16%   |
| PNY USB             | 3         | 3      | 0.16%   |
| Phison              | 3         | 3      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1690      | 2137   | 34.09%  |
| NVMe    | 1604      | 2243   | 32.36%  |
| HDD     | 1394      | 1617   | 28.12%  |
| MMC     | 200       | 242    | 4.03%   |
| Unknown | 69        | 88     | 1.39%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2704      | 3634   | 57.8%   |
| NVMe | 1597      | 2225   | 34.14%  |
| MMC  | 200       | 242    | 4.28%   |
| SAS  | 177       | 226    | 3.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1954      | 2474   | 64.38%  |
| 0.51-1.0   | 976       | 1149   | 32.16%  |
| 1.01-2.0   | 93        | 118    | 3.06%   |
| 4.01-10.0  | 5         | 5      | 0.16%   |
| 3.01-4.0   | 3         | 3      | 0.1%    |
| 2.01-3.0   | 2         | 2      | 0.07%   |
| 10.01-20.0 | 2         | 3      | 0.07%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1424      | 34.09%  |
| 251-500        | 1185      | 28.37%  |
| 501-1000       | 740       | 17.72%  |
| 1001-2000      | 276       | 6.61%   |
| 51-100         | 217       | 5.2%    |
| 21-50          | 110       | 2.63%   |
| 1-20           | 97        | 2.32%   |
| 2001-3000      | 58        | 1.39%   |
| More than 3000 | 43        | 1.03%   |
| Unknown        | 27        | 0.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1795      | 41.02%  |
| 21-50          | 950       | 21.71%  |
| 51-100         | 552       | 12.61%  |
| 101-250        | 551       | 12.59%  |
| 251-500        | 271       | 6.19%   |
| 501-1000       | 150       | 3.43%   |
| 1001-2000      | 57        | 1.3%    |
| Unknown        | 27        | 0.62%   |
| More than 3000 | 13        | 0.3%    |
| 2001-3000      | 10        | 0.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| HGST HTS725050A7E630 500GB               | 5         | 8      | 5.1%    |
| Seagate ST1000LM035-1RK172 1TB           | 4         | 4      | 4.08%   |
| HGST HTS721010A9E630 1TB                 | 4         | 4      | 4.08%   |
| Seagate ST500LT012-1DG142 500GB          | 3         | 3      | 3.06%   |
| Seagate ST1000LX015-1U7172 1TB           | 3         | 3      | 3.06%   |
| Hitachi HTS545050A7E380 500GB            | 3         | 5      | 3.06%   |
| HGST HTS541010A9E680 1TB                 | 3         | 3      | 3.06%   |
| WDC WD10JPCX-24UE4T0 1TB                 | 2         | 2      | 2.04%   |
| Seagate ST9500325AS 500GB                | 2         | 3      | 2.04%   |
| Seagate ST500LT012-9WS142 500GB          | 2         | 2      | 2.04%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 2         | 2      | 2.04%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 2         | 2      | 2.04%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD      | 2         | 2      | 2.04%   |
| Kingston SUV400S37120G 120GB SSD         | 2         | 2      | 2.04%   |
| Crucial CT1000P1SSD8 1TB                 | 2         | 2      | 2.04%   |
| WDC WD5000LPCX-60VHAT0 500GB             | 1         | 1      | 1.02%   |
| WDC WD5000LPCX-21VHAT0 500GB             | 1         | 1      | 1.02%   |
| WDC WD5000BPVT-22HXZT3 500GB             | 1         | 1      | 1.02%   |
| WDC WD5000BPVT-08HXZT3 500GB             | 1         | 1      | 1.02%   |
| WDC WD2500BEVT-22A23T0 250GB             | 1         | 1      | 1.02%   |
| WDC WD1600BJKT-75F4T0 160GB              | 1         | 1      | 1.02%   |
| WDC WD10SPZX-75Z10T1 1TB                 | 1         | 1      | 1.02%   |
| WDC WD10SPZX-24Z10 1TB                   | 1         | 1      | 1.02%   |
| WDC WD10SPCX-24HWST1 1TB                 | 1         | 1      | 1.02%   |
| WDC WD10JPVX-75JC3T0 1TB                 | 1         | 1      | 1.02%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD | 1         | 2      | 1.02%   |
| Toshiba MQ02ABD100H 1TB                  | 1         | 1      | 1.02%   |
| Toshiba MQ01ACF050 500GB                 | 1         | 1      | 1.02%   |
| Toshiba MQ01ABD100 1TB                   | 1         | 1      | 1.02%   |
| Toshiba MQ01ABD032 320GB                 | 1         | 1      | 1.02%   |
| Toshiba MK7559GSXP 752GB                 | 1         | 1      | 1.02%   |
| Toshiba MK5059GSXP 500GB                 | 1         | 1      | 1.02%   |
| Toshiba MK2035GSS 200GB                  | 1         | 1      | 1.02%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD  | 1         | 1      | 1.02%   |
| Team TM8FP4004T 4TB                      | 1         | 1      | 1.02%   |
| SK hynix SC210 mSATA 256GB SSD           | 1         | 2      | 1.02%   |
| SK hynix PC711 HFS001TDE9X073N 1024GB    | 1         | 1      | 1.02%   |
| SK hynix HFS512G39TND-N210A 512GB SSD    | 1         | 1      | 1.02%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB  | 1         | 1      | 1.02%   |
| Seagate ST9750420AS 752GB                | 1         | 1      | 1.02%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 24        | 25     | 24.49%  |
| WDC                 | 12        | 12     | 12.24%  |
| HGST                | 12        | 15     | 12.24%  |
| Toshiba             | 9         | 10     | 9.18%   |
| Hitachi             | 6         | 8      | 6.12%   |
| Samsung Electronics | 5         | 5      | 5.1%    |
| Crucial             | 5         | 5      | 5.1%    |
| SK hynix            | 4         | 5      | 4.08%   |
| Micron Technology   | 4         | 4      | 4.08%   |
| Kingston            | 4         | 4      | 4.08%   |
| A-DATA Technology   | 4         | 4      | 4.08%   |
| Intel               | 3         | 3      | 3.06%   |
| SanDisk             | 2         | 2      | 2.04%   |
| Team                | 1         | 1      | 1.02%   |
| Lexar               | 1         | 1      | 1.02%   |
| Leven               | 1         | 1      | 1.02%   |
| China               | 1         | 1      | 1.02%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 24        | 25     | 39.34%  |
| WDC     | 12        | 12     | 19.67%  |
| HGST    | 12        | 15     | 19.67%  |
| Toshiba | 7         | 7      | 11.48%  |
| Hitachi | 6         | 8      | 9.84%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 61        | 67     | 62.24%  |
| SSD  | 25        | 27     | 25.51%  |
| NVMe | 12        | 12     | 12.24%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics HM321HI 320GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3168      | 4915   | 74.79%  |
| Works    | 969       | 1305   | 22.88%  |
| Malfunc  | 98        | 106    | 2.31%   |
| Failed   | 1         | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2789      | 55.21%  |
| Samsung Electronics              | 591       | 11.7%   |
| AMD                              | 518       | 10.25%  |
| SanDisk                          | 271       | 5.36%   |
| SK hynix                         | 196       | 3.88%   |
| Toshiba America Info Systems     | 96        | 1.9%    |
| Micron Technology                | 77        | 1.52%   |
| Phison Electronics               | 73        | 1.44%   |
| Kingston Technology Company      | 67        | 1.33%   |
| Nvidia                           | 66        | 1.31%   |
| ADATA Technology                 | 46        | 0.91%   |
| Silicon Motion                   | 42        | 0.83%   |
| Micron/Crucial Technology        | 36        | 0.71%   |
| KIOXIA                           | 30        | 0.59%   |
| Solid State Storage Technology   | 27        | 0.53%   |
| Union Memory (Shenzhen)          | 26        | 0.51%   |
| Realtek Semiconductor            | 16        | 0.32%   |
| Apple                            | 15        | 0.3%    |
| Marvell Technology Group         | 14        | 0.28%   |
| Seagate Technology               | 11        | 0.22%   |
| Silicon Integrated Systems [SiS] | 8         | 0.16%   |
| Shenzhen Longsys Electronics     | 7         | 0.14%   |
| Lite-On Technology               | 7         | 0.14%   |
| Lenovo                           | 6         | 0.12%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.08%   |
| JMicron Technology               | 4         | 0.08%   |
| ASMedia Technology               | 3         | 0.06%   |
| Yangtze Memory Technologies      | 1         | 0.02%   |
| Unknown                          | 1         | 0.02%   |
| Silicon Image                    | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| Enmotus                          | 1         | 0.02%   |
| Biwin Storage Technology         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 489       | 9.25%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 348       | 6.58%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 335       | 6.34%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 301       | 5.69%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 268       | 5.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 235       | 4.45%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 214       | 4.05%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 177       | 3.35%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 142       | 2.69%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 120       | 2.27%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 101       | 1.91%   |
| Intel Volume Management Device NVMe RAID Controller                            | 90        | 1.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 90        | 1.7%    |
| Samsung NVMe SSD Controller 980                                                | 86        | 1.63%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 84        | 1.59%   |
| Micron Non-Volatile memory controller                                          | 77        | 1.46%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 75        | 1.42%   |
| Intel SSD 660P Series                                                          | 75        | 1.42%   |
| Intel Comet Lake SATA AHCI Controller                                          | 72        | 1.36%   |
| SK hynix Gold P31 SSD                                                          | 71        | 1.34%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 71        | 1.34%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 70        | 1.32%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 62        | 1.17%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 57        | 1.08%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 49        | 0.93%   |
| SanDisk Non-Volatile memory controller                                         | 47        | 0.89%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 46        | 0.87%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 44        | 0.83%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 42        | 0.79%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 42        | 0.79%   |
| SK hynix Non-Volatile memory controller                                        | 41        | 0.78%   |
| Phison E12 NVMe Controller                                                     | 40        | 0.76%   |
| Nvidia MCP79 AHCI Controller                                                   | 38        | 0.72%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 36        | 0.68%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 36        | 0.68%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 36        | 0.68%   |
| Intel Tiger Lake-LP SATA Controller                                            | 34        | 0.64%   |
| Samsung Electronics SATA controller                                            | 33        | 0.62%   |
| ADATA Non-Volatile memory controller                                           | 32        | 0.61%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 29        | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2952      | 58.2%   |
| NVMe | 1597      | 31.49%  |
| RAID | 378       | 7.45%   |
| IDE  | 145       | 2.86%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 3323      | 81.93%  |
| AMD    | 733       | 18.07%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz             | 103       | 2.54%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 87        | 2.14%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 82        | 2.02%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 71        | 1.75%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 67        | 1.65%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 61        | 1.5%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 61        | 1.5%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 58        | 1.43%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 57        | 1.4%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 57        | 1.4%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 57        | 1.4%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 55        | 1.36%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 49        | 1.21%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 48        | 1.18%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 46        | 1.13%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 45        | 1.11%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 43        | 1.06%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 43        | 1.06%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 42        | 1.03%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 39        | 0.96%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 38        | 0.94%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 36        | 0.89%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 35        | 0.86%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 35        | 0.86%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 34        | 0.84%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 32        | 0.79%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 31        | 0.76%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 31        | 0.76%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 30        | 0.74%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 30        | 0.74%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 29        | 0.71%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 27        | 0.67%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 27        | 0.67%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 27        | 0.67%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 26        | 0.64%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 25        | 0.62%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 25        | 0.62%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 25        | 0.62%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 24        | 0.59%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 23        | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 1244      | 30.67%  |
| Intel Core i5           | 1057      | 26.06%  |
| Intel Core i3           | 267       | 6.58%   |
| Other                   | 258       | 6.36%   |
| AMD Ryzen 5             | 205       | 5.05%   |
| AMD Ryzen 7             | 191       | 4.71%   |
| Intel Core 2 Duo        | 152       | 3.75%   |
| Intel Celeron           | 132       | 3.25%   |
| Intel Pentium           | 52        | 1.28%   |
| AMD Ryzen 3             | 50        | 1.23%   |
| Intel Core i9           | 48        | 1.18%   |
| AMD Ryzen 9             | 46        | 1.13%   |
| AMD A6                  | 46        | 1.13%   |
| Intel Pentium Dual-Core | 29        | 0.71%   |
| AMD A8                  | 29        | 0.71%   |
| AMD A10                 | 25        | 0.62%   |
| AMD Ryzen 7 PRO         | 22        | 0.54%   |
| AMD A4                  | 22        | 0.54%   |
| Intel Atom              | 19        | 0.47%   |
| Intel Core 2            | 15        | 0.37%   |
| Intel Pentium Dual      | 13        | 0.32%   |
| Intel Genuine           | 12        | 0.3%    |
| Intel Core m3           | 12        | 0.3%    |
| Intel Xeon              | 10        | 0.25%   |
| AMD Athlon              | 10        | 0.25%   |
| AMD E1                  | 9         | 0.22%   |
| AMD E                   | 8         | 0.2%    |
| AMD E2                  | 7         | 0.17%   |
| AMD Turion 64 X2 Mobile | 6         | 0.15%   |
| AMD Ryzen 5 PRO         | 6         | 0.15%   |
| AMD FX                  | 6         | 0.15%   |
| AMD A12                 | 6         | 0.15%   |
| Intel Core M            | 4         | 0.1%    |
| Intel Celeron Dual-Core | 4         | 0.1%    |
| AMD C-60                | 4         | 0.1%    |
| Intel Pentium Silver    | 3         | 0.07%   |
| Intel Core m5           | 3         | 0.07%   |
| AMD Athlon X2           | 3         | 0.07%   |
| AMD V120                | 2         | 0.05%   |
| AMD PRO A10             | 2         | 0.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1821      | 44.9%   |
| 4      | 1426      | 35.16%  |
| 6      | 408       | 10.06%  |
| 8      | 348       | 8.58%   |
| 1      | 21        | 0.52%   |
| 14     | 15        | 0.37%   |
| 12     | 9         | 0.22%   |
| 10     | 5         | 0.12%   |
| 16     | 1         | 0.02%   |
| 7      | 1         | 0.02%   |
| 5      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4056      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 3374      | 83.14%  |
| 1      | 684       | 16.86%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4049      | 99.83%  |
| Unknown        | 7         | 0.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2570      | 61.84%  |
| 0x906ea    | 140       | 3.37%   |
| 0x806ea    | 98        | 2.36%   |
| 0x306a9    | 95        | 2.29%   |
| 0x806ec    | 90        | 2.17%   |
| 0x206a7    | 87        | 2.09%   |
| 0x406e3    | 80        | 1.92%   |
| 0x40651    | 74        | 1.78%   |
| 0x806c1    | 71        | 1.71%   |
| 0xa0652    | 65        | 1.56%   |
| 0x806e9    | 55        | 1.32%   |
| 0x306c3    | 54        | 1.3%    |
| 0x906e9    | 50        | 1.2%    |
| 0x08108102 | 42        | 1.01%   |
| 0x306d4    | 35        | 0.84%   |
| 0x0a50000c | 33        | 0.79%   |
| 0x806eb    | 31        | 0.75%   |
| 0x506e3    | 31        | 0.75%   |
| 0x1067a    | 30        | 0.72%   |
| 0x806d1    | 29        | 0.7%    |
| 0x906ed    | 26        | 0.63%   |
| 0x08600106 | 25        | 0.6%    |
| 0x08108109 | 24        | 0.58%   |
| 0x20655    | 21        | 0.51%   |
| 0x08600104 | 19        | 0.46%   |
| 0x706e5    | 18        | 0.43%   |
| 0x08600103 | 17        | 0.41%   |
| 0x06006705 | 17        | 0.41%   |
| 0x0810100b | 15        | 0.36%   |
| 0x08608103 | 13        | 0.31%   |
| 0x706a1    | 12        | 0.29%   |
| 0x40661    | 11        | 0.26%   |
| 0x10676    | 11        | 0.26%   |
| 0xa0660    | 9         | 0.22%   |
| 0x906a3    | 9         | 0.22%   |
| 0x07030105 | 9         | 0.22%   |
| 0x08600102 | 8         | 0.19%   |
| 0x06001119 | 8         | 0.19%   |
| 0x406c4    | 7         | 0.17%   |
| 0x0a404101 | 7         | 0.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 994       | 24.49%  |
| Haswell          | 373       | 9.19%   |
| SandyBridge      | 305       | 7.51%   |
| IvyBridge        | 302       | 7.44%   |
| Skylake          | 240       | 5.91%   |
| Zen+             | 168       | 4.14%   |
| Penryn           | 164       | 4.04%   |
| CometLake        | 164       | 4.04%   |
| TigerLake        | 163       | 4.02%   |
| Zen 2            | 154       | 3.79%   |
| Broadwell        | 141       | 3.47%   |
| Westmere         | 125       | 3.08%   |
| Unknown          | 111       | 2.73%   |
| Zen 3            | 104       | 2.56%   |
| Icelake          | 77        | 1.9%    |
| Silvermont       | 68        | 1.68%   |
| Core             | 67        | 1.65%   |
| Excavator        | 58        | 1.43%   |
| Zen              | 43        | 1.06%   |
| Goldmont plus    | 41        | 1.01%   |
| Puma             | 35        | 0.86%   |
| Piledriver       | 30        | 0.74%   |
| Bobcat           | 21        | 0.52%   |
| Goldmont         | 20        | 0.49%   |
| Nehalem          | 15        | 0.37%   |
| Steamroller      | 12        | 0.3%    |
| K10 Llano        | 12        | 0.3%    |
| Jaguar           | 12        | 0.3%    |
| K8 Hammer        | 11        | 0.27%   |
| Alderlake Hybrid | 9         | 0.22%   |
| K10              | 8         | 0.2%    |
| K8 & K10 hybrid  | 7         | 0.17%   |
| Bonnell          | 4         | 0.1%    |
| Tremont          | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3002      | 55.41%  |
| Nvidia                           | 1474      | 27.21%  |
| AMD                              | 935       | 17.26%  |
| Silicon Integrated Systems [SiS] | 6         | 0.11%   |
| S3 Graphics                      | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 286       | 5.16%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 277       | 5%      |
| Intel 3rd Gen Core processor Graphics Controller                                         | 275       | 4.96%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 211       | 3.81%   |
| Intel UHD Graphics 620                                                                   | 172       | 3.1%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 169       | 3.05%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 153       | 2.76%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 146       | 2.63%   |
| AMD Renoir                                                                               | 145       | 2.62%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 135       | 2.44%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 129       | 2.33%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 120       | 2.16%   |
| Intel HD Graphics 620                                                                    | 119       | 2.15%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 107       | 1.93%   |
| Intel HD Graphics 630                                                                    | 105       | 1.89%   |
| Intel HD Graphics 5500                                                                   | 102       | 1.84%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 101       | 1.82%   |
| Intel Core Processor Integrated Graphics Controller                                      | 94        | 1.7%    |
| AMD Cezanne                                                                              | 93        | 1.68%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 76        | 1.37%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 73        | 1.32%   |
| Intel HD Graphics 530                                                                    | 62        | 1.12%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 58        | 1.05%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 58        | 1.05%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 57        | 1.03%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 50        | 0.9%    |
| Nvidia GP108M [GeForce MX150]                                                            | 49        | 0.88%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 48        | 0.87%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 46        | 0.83%   |
| AMD Lucienne                                                                             | 46        | 0.83%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 45        | 0.81%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 44        | 0.79%   |
| Nvidia TU117M                                                                            | 43        | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 42        | 0.76%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 41        | 0.74%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 40        | 0.72%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 38        | 0.69%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 34        | 0.61%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 32        | 0.58%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 31        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 1836      | 44.97%  |
| Intel + Nvidia  | 1016      | 24.88%  |
| 1 x AMD         | 538       | 13.18%  |
| 1 x Nvidia      | 281       | 6.88%   |
| AMD + Nvidia    | 160       | 3.92%   |
| Intel + AMD     | 158       | 3.87%   |
| 2 x AMD         | 80        | 1.96%   |
| 2 x Nvidia      | 7         | 0.17%   |
| 1 x SiS         | 6         | 0.15%   |
| 1 x S3 Graphics | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2792      | 68.21%  |
| Proprietary | 1181      | 28.85%  |
| Unknown     | 120       | 2.93%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2975      | 72.1%   |
| 1.01-2.0   | 313       | 7.59%   |
| 3.01-4.0   | 301       | 7.3%    |
| 5.01-6.0   | 169       | 4.1%    |
| 0.01-0.5   | 149       | 3.61%   |
| 7.01-8.0   | 96        | 2.33%   |
| 0.51-1.0   | 84        | 2.04%   |
| 2.01-3.0   | 29        | 0.7%    |
| 8.01-16.0  | 10        | 0.24%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 854       | 18.14%  |
| LG Display              | 683       | 14.51%  |
| Chimei Innolux          | 682       | 14.49%  |
| BOE                     | 584       | 12.4%   |
| Samsung Electronics     | 444       | 9.43%   |
| Apple                   | 188       | 3.99%   |
| Sharp                   | 177       | 3.76%   |
| Goldstar                | 144       | 3.06%   |
| Dell                    | 137       | 2.91%   |
| PANDA                   | 114       | 2.42%   |
| Chi Mei Optoelectronics | 77        | 1.64%   |
| Lenovo                  | 59        | 1.25%   |
| AOC                     | 51        | 1.08%   |
| Acer                    | 47        | 1%      |
| Hewlett-Packard         | 46        | 0.98%   |
| BenQ                    | 39        | 0.83%   |
| Philips                 | 36        | 0.76%   |
| InfoVision              | 33        | 0.7%    |
| Ancor Communications    | 27        | 0.57%   |
| ASUSTek Computer        | 22        | 0.47%   |
| CSO                     | 21        | 0.45%   |
| ViewSonic               | 16        | 0.34%   |
| LG Philips              | 13        | 0.28%   |
| Sony                    | 12        | 0.25%   |
| Vizio                   | 10        | 0.21%   |
| TMX                     | 10        | 0.21%   |
| InnoLux Display         | 10        | 0.21%   |
| Panasonic               | 9         | 0.19%   |
| Sceptre Tech            | 8         | 0.17%   |
| Iiyama                  | 8         | 0.17%   |
| Toshiba                 | 7         | 0.15%   |
| JDI                     | 7         | 0.15%   |
| Vestel Elektronik       | 5         | 0.11%   |
| LGD                     | 4         | 0.08%   |
| HannStar                | 4         | 0.08%   |
| Eizo                    | 4         | 0.08%   |
| CPT                     | 4         | 0.08%   |
| Viotek                  | 3         | 0.06%   |
| TCL                     | 3         | 0.06%   |
| SGT                     | 3         | 0.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 52        | 1.09%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 43        | 0.9%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 38        | 0.8%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 38        | 0.8%    |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 33        | 0.69%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 33        | 0.69%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 32        | 0.67%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 31        | 0.65%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch              | 24        | 0.5%    |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch           | 24        | 0.5%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 23        | 0.48%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch     | 22        | 0.46%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch      | 21        | 0.44%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 21        | 0.44%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 21        | 0.44%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 20        | 0.42%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch            | 20        | 0.42%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                  | 19        | 0.4%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 19        | 0.4%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 18        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch          | 18        | 0.38%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 18        | 0.38%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch           | 17        | 0.36%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 17        | 0.36%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 16        | 0.34%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 15        | 0.32%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                   | 15        | 0.32%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 15        | 0.32%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch             | 15        | 0.32%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                   | 14        | 0.29%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch            | 14        | 0.29%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                    | 14        | 0.29%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 14        | 0.29%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch      | 13        | 0.27%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch              | 13        | 0.27%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 13        | 0.27%   |
| AU Optronics LCD Monitor AUO82ED 1920x1080 344x193mm 15.5-inch            | 13        | 0.27%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch             | 13        | 0.27%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                         | 12        | 0.25%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch          | 12        | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2066      | 46.85%  |
| 1366x768 (WXGA)    | 1172      | 26.58%  |
| 3840x2160 (4K)     | 225       | 5.1%    |
| 1600x900 (HD+)     | 196       | 4.44%   |
| 2560x1440 (QHD)    | 133       | 3.02%   |
| 1280x800 (WXGA)    | 111       | 2.52%   |
| 1440x900 (WXGA+)   | 79        | 1.79%   |
| 1920x1200 (WUXGA)  | 78        | 1.77%   |
| 2560x1600          | 54        | 1.22%   |
| 2880x1800          | 42        | 0.95%   |
| 2560x1080          | 39        | 0.88%   |
| 3840x2400          | 26        | 0.59%   |
| 1680x1050 (WSXGA+) | 26        | 0.59%   |
| 3440x1440          | 25        | 0.57%   |
| 2160x1440          | 16        | 0.36%   |
| 3200x1800 (QHD+)   | 15        | 0.34%   |
| 1360x768           | 15        | 0.34%   |
| 1920x540           | 12        | 0.27%   |
| 2256x1504          | 11        | 0.25%   |
| 3000x2000          | 10        | 0.23%   |
| 1280x1024 (SXGA)   | 9         | 0.2%    |
| 3840x1080          | 8         | 0.18%   |
| Unknown            | 6         | 0.14%   |
| 3456x2160          | 4         | 0.09%   |
| 3200x2000          | 4         | 0.09%   |
| 3840x1600          | 2         | 0.05%   |
| 3840x1200          | 2         | 0.05%   |
| 3840x1100          | 2         | 0.05%   |
| 3072x1920          | 2         | 0.05%   |
| 2560x1700          | 2         | 0.05%   |
| 2288x1287          | 2         | 0.05%   |
| 1680x945           | 2         | 0.05%   |
| 1024x768 (XGA)     | 2         | 0.05%   |
| 1024x600           | 2         | 0.05%   |
| 7680x2160          | 1         | 0.02%   |
| 5120x1080          | 1         | 0.02%   |
| 3280x1080          | 1         | 0.02%   |
| 2400x1600          | 1         | 0.02%   |
| 2304x1440          | 1         | 0.02%   |
| 2048x1152          | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 2008      | 42.69%  |
| 13      | 723       | 15.37%  |
| 14      | 522       | 11.1%   |
| 17      | 354       | 7.53%   |
| 27      | 158       | 3.36%   |
| 24      | 135       | 2.87%   |
| 23      | 115       | 2.44%   |
| 12      | 102       | 2.17%   |
| 21      | 87        | 1.85%   |
| 31      | 72        | 1.53%   |
| 11      | 58        | 1.23%   |
| 34      | 55        | 1.17%   |
| 16      | 50        | 1.06%   |
| 18      | 44        | 0.94%   |
| Unknown | 35        | 0.74%   |
| 19      | 22        | 0.47%   |
| 32      | 17        | 0.36%   |
| 20      | 17        | 0.36%   |
| 84      | 15        | 0.32%   |
| 72      | 11        | 0.23%   |
| 22      | 11        | 0.23%   |
| 40      | 10        | 0.21%   |
| 54      | 9         | 0.19%   |
| 48      | 9         | 0.19%   |
| 25      | 7         | 0.15%   |
| 52      | 5         | 0.11%   |
| 28      | 5         | 0.11%   |
| 26      | 5         | 0.11%   |
| 10      | 5         | 0.11%   |
| 65      | 4         | 0.09%   |
| 49      | 4         | 0.09%   |
| 46      | 4         | 0.09%   |
| 39      | 4         | 0.09%   |
| 33      | 4         | 0.09%   |
| 37      | 3         | 0.06%   |
| 35      | 3         | 0.06%   |
| 29      | 3         | 0.06%   |
| 47      | 2         | 0.04%   |
| 99      | 1         | 0.02%   |
| 69      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 2880      | 61.63%  |
| 201-300        | 512       | 10.96%  |
| 351-400        | 430       | 9.2%    |
| 501-600        | 373       | 7.98%   |
| 401-500        | 176       | 3.77%   |
| 601-700        | 102       | 2.18%   |
| 701-800        | 75        | 1.6%    |
| 1001-1500      | 40        | 0.86%   |
| Unknown        | 35        | 0.75%   |
| 1501-2000      | 27        | 0.58%   |
| 801-900        | 18        | 0.39%   |
| 901-1000       | 3         | 0.06%   |
| More than 2000 | 1         | 0.02%   |
| 101-200        | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 3494      | 85.57%  |
| 16/10   | 426       | 10.43%  |
| 21/9    | 65        | 1.59%   |
| 3/2     | 46        | 1.13%   |
| Unknown | 21        | 0.51%   |
| 5/4     | 11        | 0.27%   |
| 32/9    | 8         | 0.2%    |
| 4/3     | 6         | 0.15%   |
| 3.40    | 2         | 0.05%   |
| 6/5     | 1         | 0.02%   |
| 3.73    | 1         | 0.02%   |
| 3.20    | 1         | 0.02%   |
| 0.62    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 2020      | 43.02%  |
| 81-90          | 1006      | 21.43%  |
| 121-130        | 335       | 7.14%   |
| 201-250        | 288       | 6.13%   |
| 71-80          | 240       | 5.11%   |
| 301-350        | 162       | 3.45%   |
| 351-500        | 149       | 3.17%   |
| 61-70          | 96        | 2.04%   |
| 151-200        | 61        | 1.3%    |
| 51-60          | 60        | 1.28%   |
| More than 1000 | 54        | 1.15%   |
| 251-300        | 49        | 1.04%   |
| 141-150        | 45        | 0.96%   |
| Unknown        | 35        | 0.75%   |
| 111-120        | 34        | 0.72%   |
| 501-1000       | 34        | 0.72%   |
| 131-140        | 17        | 0.36%   |
| 41-50          | 5         | 0.11%   |
| 91-100         | 4         | 0.09%   |
| 1-40           | 1         | 0.02%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 2018      | 43.87%  |
| 101-120       | 1326      | 28.83%  |
| 51-100        | 641       | 13.93%  |
| 161-240       | 321       | 6.98%   |
| More than 240 | 199       | 4.33%   |
| 1-50          | 60        | 1.3%    |
| Unknown       | 35        | 0.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 3212      | 77.49%  |
| 2     | 707       | 17.06%  |
| 0     | 145       | 3.5%    |
| 3     | 76        | 1.83%   |
| 4     | 5         | 0.12%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2228      | 33.7%   |
| Intel                             | 2167      | 32.77%  |
| Qualcomm Atheros                  | 957       | 14.47%  |
| Broadcom                          | 460       | 6.96%   |
| Broadcom Limited                  | 125       | 1.89%   |
| MediaTek                          | 84        | 1.27%   |
| Marvell Technology Group          | 57        | 0.86%   |
| Ralink                            | 48        | 0.73%   |
| Nvidia                            | 47        | 0.71%   |
| TP-Link                           | 45        | 0.68%   |
| ASIX Electronics                  | 38        | 0.57%   |
| Ralink Technology                 | 35        | 0.53%   |
| Samsung Electronics               | 32        | 0.48%   |
| DisplayLink                       | 23        | 0.35%   |
| Dell                              | 22        | 0.33%   |
| Ericsson Business Mobile Networks | 20        | 0.3%    |
| Lenovo                            | 18        | 0.27%   |
| Sierra Wireless                   | 17        | 0.26%   |
| Xiaomi                            | 14        | 0.21%   |
| Qualcomm                          | 14        | 0.21%   |
| JMicron Technology                | 14        | 0.21%   |
| Hewlett-Packard                   | 12        | 0.18%   |
| Google                            | 12        | 0.18%   |
| ASUSTek Computer                  | 11        | 0.17%   |
| NetGear                           | 10        | 0.15%   |
| OnePlus Technology (Shenzhen)     | 9         | 0.14%   |
| Huawei Technologies               | 9         | 0.14%   |
| Silicon Integrated Systems [SiS]  | 8         | 0.12%   |
| Motorola PCS                      | 7         | 0.11%   |
| D-Link                            | 7         | 0.11%   |
| Apple                             | 6         | 0.09%   |
| OPPO Electronics                  | 5         | 0.08%   |
| Microsoft                         | 4         | 0.06%   |
| Linksys                           | 4         | 0.06%   |
| Qualcomm Atheros Communications   | 3         | 0.05%   |
| FIBOCOM                           | 3         | 0.05%   |
| Edimax Technology                 | 3         | 0.05%   |
| U-Blox                            | 2         | 0.03%   |
| T & A Mobile Phones               | 2         | 0.03%   |
| LSI                               | 2         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1452      | 18.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 377       | 4.85%   |
| Intel Wi-Fi 6 AX200                                               | 276       | 3.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 213       | 2.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 164       | 2.11%   |
| Intel Wireless 8265 / 8275                                        | 161       | 2.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 160       | 2.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 146       | 1.88%   |
| Intel Wireless 7260                                               | 144       | 1.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 141       | 1.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 141       | 1.81%   |
| Intel Wireless 7265                                               | 127       | 1.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 123       | 1.58%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 123       | 1.58%   |
| Intel Wi-Fi 6 AX201                                               | 122       | 1.57%   |
| Intel Wireless 8260                                               | 102       | 1.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 99        | 1.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 99        | 1.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 95        | 1.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 94        | 1.21%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 93        | 1.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 75        | 0.96%   |
| Broadcom BCM43142 802.11b/g/n                                     | 72        | 0.93%   |
| Intel Wireless 3165                                               | 66        | 0.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 62        | 0.8%    |
| Broadcom BCM4331 802.11a/b/g/n                                    | 54        | 0.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 54        | 0.69%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 51        | 0.66%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 51        | 0.66%   |
| Intel Ethernet Connection I218-LM                                 | 49        | 0.63%   |
| Intel Wireless 3160                                               | 48        | 0.62%   |
| Intel Ethernet Connection (4) I219-LM                             | 48        | 0.62%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 48        | 0.62%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 47        | 0.6%    |
| Intel Ethernet Connection I219-LM                                 | 46        | 0.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 45        | 0.58%   |
| Intel Wireless-AC 9260                                            | 44        | 0.57%   |
| Intel Centrino Ultimate-N 6300                                    | 43        | 0.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 40        | 0.51%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 38        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2087      | 49.37%  |
| Qualcomm Atheros                      | 798       | 18.88%  |
| Realtek Semiconductor                 | 547       | 12.94%  |
| Broadcom                              | 390       | 9.23%   |
| Broadcom Limited                      | 99        | 2.34%   |
| MediaTek                              | 80        | 1.89%   |
| Ralink                                | 48        | 1.14%   |
| TP-Link                               | 40        | 0.95%   |
| Ralink Technology                     | 35        | 0.83%   |
| Dell                                  | 19        | 0.45%   |
| Sierra Wireless                       | 17        | 0.4%    |
| Qualcomm                              | 11        | 0.26%   |
| NetGear                               | 9         | 0.21%   |
| ASUSTek Computer                      | 9         | 0.21%   |
| D-Link                                | 7         | 0.17%   |
| Hewlett-Packard                       | 4         | 0.09%   |
| Qualcomm Atheros Communications       | 3         | 0.07%   |
| Microsoft                             | 3         | 0.07%   |
| FIBOCOM                               | 3         | 0.07%   |
| Edimax Technology                     | 3         | 0.07%   |
| Ericsson Business Mobile Networks     | 2         | 0.05%   |
| D-Link System                         | 2         | 0.05%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.05%   |
| Wilocity                              | 1         | 0.02%   |
| Sitecom Europe                        | 1         | 0.02%   |
| Samsung Electronics                   | 1         | 0.02%   |
| Philips (or NXP)                      | 1         | 0.02%   |
| Ovislink                              | 1         | 0.02%   |
| Micro Star International              | 1         | 0.02%   |
| Linksys                               | 1         | 0.02%   |
| Chu Yuen Enterprise                   | 1         | 0.02%   |
| Arduino SA                            | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 276       | 6.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 213       | 5%      |
| Intel Wireless 8265 / 8275                                     | 161       | 3.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 146       | 3.43%   |
| Intel Wireless 7260                                            | 144       | 3.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 141       | 3.31%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 141       | 3.31%   |
| Intel Wireless 7265                                            | 127       | 2.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 123       | 2.89%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 123       | 2.89%   |
| Intel Wi-Fi 6 AX201                                            | 122       | 2.87%   |
| Intel Wireless 8260                                            | 102       | 2.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 99        | 2.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 99        | 2.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 95        | 2.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 94        | 2.21%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 93        | 2.19%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 75        | 1.76%   |
| Broadcom BCM43142 802.11b/g/n                                  | 72        | 1.69%   |
| Intel Wireless 3165                                            | 66        | 1.55%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 62        | 1.46%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 54        | 1.27%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 54        | 1.27%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 51        | 1.2%    |
| Intel Wireless 3160                                            | 48        | 1.13%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 48        | 1.13%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 47        | 1.1%    |
| Intel Wireless-AC 9260                                         | 44        | 1.03%   |
| Intel Centrino Ultimate-N 6300                                 | 43        | 1.01%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 40        | 0.94%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 38        | 0.89%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 38        | 0.89%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 37        | 0.87%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 35        | 0.82%   |
| Intel Centrino Advanced-N 6235                                 | 35        | 0.82%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 34        | 0.8%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 32        | 0.75%   |
| Realtek 802.11ac NIC                                           | 31        | 0.73%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 30        | 0.7%    |
| Intel Centrino Wireless-N 2230                                 | 28        | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2036      | 59.29%  |
| Intel                            | 630       | 18.35%  |
| Qualcomm Atheros                 | 254       | 7.4%    |
| Broadcom                         | 157       | 4.57%   |
| Marvell Technology Group         | 57        | 1.66%   |
| Nvidia                           | 47        | 1.37%   |
| ASIX Electronics                 | 38        | 1.11%   |
| Samsung Electronics              | 31        | 0.9%    |
| Broadcom Limited                 | 30        | 0.87%   |
| DisplayLink                      | 23        | 0.67%   |
| Lenovo                           | 18        | 0.52%   |
| Xiaomi                           | 14        | 0.41%   |
| JMicron Technology               | 14        | 0.41%   |
| Google                           | 12        | 0.35%   |
| Silicon Integrated Systems [SiS] | 8         | 0.23%   |
| OnePlus Technology (Shenzhen)    | 8         | 0.23%   |
| Huawei Technologies              | 7         | 0.2%    |
| TP-Link                          | 5         | 0.15%   |
| OPPO Electronics                 | 5         | 0.15%   |
| Motorola PCS                     | 5         | 0.15%   |
| Apple                            | 5         | 0.15%   |
| Qualcomm                         | 3         | 0.09%   |
| MediaTek                         | 3         | 0.09%   |
| Linksys                          | 3         | 0.09%   |
| T & A Mobile Phones              | 2         | 0.06%   |
| LSI                              | 2         | 0.06%   |
| LG Electronics                   | 2         | 0.06%   |
| ICS Advent                       | 2         | 0.06%   |
| Hewlett-Packard                  | 2         | 0.06%   |
| ASUSTek Computer                 | 2         | 0.06%   |
| Aquantia                         | 2         | 0.06%   |
| Research In Motion               | 1         | 0.03%   |
| NTmore                           | 1         | 0.03%   |
| NetGear                          | 1         | 0.03%   |
| Microsoft                        | 1         | 0.03%   |
| Foxconn / Hon Hai                | 1         | 0.03%   |
| Cypress Semiconductor            | 1         | 0.03%   |
| Attansic Technology              | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1452      | 41.8%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 377       | 10.85%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 164       | 4.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 160       | 4.61%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 51        | 1.47%   |
| Intel Ethernet Connection I218-LM                                 | 49        | 1.41%   |
| Intel Ethernet Connection (4) I219-LM                             | 48        | 1.38%   |
| Intel Ethernet Connection I219-LM                                 | 46        | 1.32%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 45        | 1.3%    |
| Intel Ethernet Connection I217-LM                                 | 38        | 1.09%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 35        | 1.01%   |
| Nvidia MCP79 Ethernet                                             | 34        | 0.98%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 31        | 0.89%   |
| Intel Ethernet Connection (3) I218-LM                             | 31        | 0.89%   |
| ASIX AX88179 Gigabit Ethernet                                     | 30        | 0.86%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 28        | 0.81%   |
| Intel 82577LM Gigabit Network Connection                          | 28        | 0.81%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 26        | 0.75%   |
| Intel Ethernet Connection (4) I219-V                              | 25        | 0.72%   |
| Intel Ethernet Connection (7) I219-LM                             | 24        | 0.69%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 23        | 0.66%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 22        | 0.63%   |
| Realtek RTL8125 2.5GbE Controller                                 | 19        | 0.55%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 18        | 0.52%   |
| Intel Ethernet Connection (7) I219-V                              | 18        | 0.52%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 17        | 0.49%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 17        | 0.49%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 16        | 0.46%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 16        | 0.46%   |
| Intel 82567LM Gigabit Network Connection                          | 16        | 0.46%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 16        | 0.46%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 16        | 0.46%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 15        | 0.43%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 15        | 0.43%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 14        | 0.4%    |
| Intel Ethernet Connection I219-V                                  | 14        | 0.4%    |
| Intel Ethernet Connection (6) I219-V                              | 14        | 0.4%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 13        | 0.37%   |
| Intel Ethernet Connection (2) I219-LM                             | 13        | 0.37%   |
| Intel Ethernet Connection (13) I219-V                             | 13        | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4016      | 54.7%   |
| Ethernet | 3279      | 44.66%  |
| Modem    | 35        | 0.48%   |
| Unknown  | 12        | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3406      | 78.72%  |
| Ethernet | 921       | 21.28%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 3006      | 74.06%  |
| 1     | 1000      | 24.64%  |
| 3     | 27        | 0.67%   |
| 0     | 26        | 0.64%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3315      | 80.79%  |
| Yes  | 788       | 19.21%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1740      | 50.45%  |
| Qualcomm Atheros Communications | 349       | 10.12%  |
| Realtek Semiconductor           | 275       | 7.97%   |
| Apple                           | 205       | 5.94%   |
| IMC Networks                    | 182       | 5.28%   |
| Broadcom                        | 178       | 5.16%   |
| Lite-On Technology              | 173       | 5.02%   |
| Foxconn / Hon Hai               | 94        | 2.73%   |
| Dell                            | 59        | 1.71%   |
| Cambridge Silicon Radio         | 34        | 0.99%   |
| Ralink                          | 27        | 0.78%   |
| Toshiba                         | 26        | 0.75%   |
| Realtek                         | 25        | 0.72%   |
| Hewlett-Packard                 | 24        | 0.7%    |
| ASUSTek Computer                | 14        | 0.41%   |
| Foxconn International           | 10        | 0.29%   |
| Ralink Technology               | 7         | 0.2%    |
| Alps Electric                   | 7         | 0.2%    |
| Askey Computer                  | 4         | 0.12%   |
| USI                             | 3         | 0.09%   |
| Qcom                            | 3         | 0.09%   |
| Unknown                         | 2         | 0.06%   |
| Taiyo Yuden                     | 2         | 0.06%   |
| Opticis                         | 2         | 0.06%   |
| SINO WEALTH                     | 1         | 0.03%   |
| Fujitsu                         | 1         | 0.03%   |
| Dynex                           | 1         | 0.03%   |
| Creative Technology             | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 635       | 18.41%  |
| Intel AX201 Bluetooth                               | 328       | 9.51%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 298       | 8.64%   |
| Intel AX200 Bluetooth                               | 272       | 7.88%   |
| Qualcomm Atheros  Bluetooth Device                  | 192       | 5.57%   |
| Realtek Bluetooth Radio                             | 169       | 4.9%    |
| Apple Bluetooth Host Controller                     | 113       | 3.28%   |
| Realtek  Bluetooth 4.2 Adapter                      | 81        | 2.35%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 69        | 2%      |
| Apple Bluetooth USB Host Controller                 | 64        | 1.86%   |
| IMC Networks Bluetooth Radio                        | 56        | 1.62%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 54        | 1.57%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 44        | 1.28%   |
| IMC Networks Wireless_Device                        | 44        | 1.28%   |
| Foxconn / Hon Hai Bluetooth Device                  | 42        | 1.22%   |
| IMC Networks Bluetooth Device                       | 41        | 1.19%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 40        | 1.16%   |
| Lite-On Bluetooth Device                            | 39        | 1.13%   |
| Intel AX210 Bluetooth                               | 38        | 1.1%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 36        | 1.04%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 34        | 0.99%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 33        | 0.96%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 32        | 0.93%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 31        | 0.9%    |
| Intel Wireless-AC 3168 Bluetooth                    | 30        | 0.87%   |
| Broadcom BCM2045B (BDC-2.1)                         | 28        | 0.81%   |
| Ralink RT3290 Bluetooth                             | 27        | 0.78%   |
| Realtek Bluetooth Radio                             | 25        | 0.72%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 24        | 0.7%    |
| Dell DW375 Bluetooth Module                         | 22        | 0.64%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 19        | 0.55%   |
| Lite-On Atheros AR3012 Bluetooth                    | 18        | 0.52%   |
| Apple Bluetooth HCI                                 | 17        | 0.49%   |
| Intel Bluetooth Device                              | 15        | 0.43%   |
| HP Broadcom 2070 Bluetooth Combo                    | 15        | 0.43%   |
| Foxconn / Hon Hai Wireless_Device                   | 15        | 0.43%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 15        | 0.43%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 14        | 0.41%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 13        | 0.38%   |
| Lite-On Wireless_Device                             | 13        | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3241      | 61.25%  |
| Nvidia                               | 917       | 17.33%  |
| AMD                                  | 801       | 15.14%  |
| C-Media Electronics                  | 42        | 0.79%   |
| Realtek Semiconductor                | 34        | 0.64%   |
| Logitech                             | 30        | 0.57%   |
| Lenovo                               | 17        | 0.32%   |
| JMTek                                | 17        | 0.32%   |
| GN Netcom                            | 16        | 0.3%    |
| Texas Instruments                    | 13        | 0.25%   |
| Kingston Technology                  | 12        | 0.23%   |
| Apple                                | 12        | 0.23%   |
| Silicon Integrated Systems [SiS]     | 8         | 0.15%   |
| Razer USA                            | 8         | 0.15%   |
| Corsair                              | 8         | 0.15%   |
| SteelSeries ApS                      | 7         | 0.13%   |
| Sony                                 | 7         | 0.13%   |
| Plantronics                          | 7         | 0.13%   |
| Hewlett-Packard                      | 6         | 0.11%   |
| Sennheiser Communications            | 5         | 0.09%   |
| Generalplus Technology               | 5         | 0.09%   |
| Focusrite-Novation                   | 4         | 0.08%   |
| Creative Technology                  | 4         | 0.08%   |
| Tenx Technology                      | 3         | 0.06%   |
| Samson Technologies                  | 3         | 0.06%   |
| No brand                             | 3         | 0.06%   |
| Yamaha                               | 2         | 0.04%   |
| XMOS                                 | 2         | 0.04%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.04%   |
| TerraTec Electronic                  | 2         | 0.04%   |
| Pioneer DJ                           | 2         | 0.04%   |
| GYROCOM C&C                          | 2         | 0.04%   |
| FiiO Electronics Technology          | 2         | 0.04%   |
| Blue Microphones                     | 2         | 0.04%   |
| AudioQuest                           | 2         | 0.04%   |
| ASUSTek Computer                     | 2         | 0.04%   |
| Astro Gaming                         | 2         | 0.04%   |
| Vestax                               | 1         | 0.02%   |
| Vault                                | 1         | 0.02%   |
| Trust                                | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 513       | 8.04%   |
| Intel Sunrise Point-LP HD Audio                                            | 474       | 7.42%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 343       | 5.37%   |
| Intel Cannon Lake PCH cAVS                                                 | 309       | 4.84%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 262       | 4.1%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 219       | 3.43%   |
| Intel 8 Series HD Audio Controller                                         | 212       | 3.32%   |
| Intel Haswell-ULT HD Audio Controller                                      | 210       | 3.29%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 186       | 2.91%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 164       | 2.57%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 163       | 2.55%   |
| Intel Comet Lake PCH cAVS                                                  | 150       | 2.35%   |
| Intel Broadwell-U Audio Controller                                         | 141       | 2.21%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 140       | 2.19%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 136       | 2.13%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 134       | 2.1%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 134       | 2.1%    |
| Intel Comet Lake PCH-LP cAVS                                               | 122       | 1.91%   |
| Intel CM238 HD Audio Controller                                            | 117       | 1.83%   |
| Nvidia TU106 High Definition Audio Controller                              | 116       | 1.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 115       | 1.8%    |
| AMD FCH Azalia Controller                                                  | 111       | 1.74%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 103       | 1.61%   |
| Nvidia GP107GL High Definition Audio Controller                            | 86        | 1.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 77        | 1.21%   |
| AMD Kabini HDMI/DP Audio                                                   | 64        | 1%      |
| Intel Tiger Lake-H HD Audio Controller                                     | 63        | 0.99%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 58        | 0.91%   |
| Nvidia GA106 High Definition Audio Controller                              | 57        | 0.89%   |
| Nvidia GP106 High Definition Audio Controller                              | 56        | 0.88%   |
| Nvidia GA104 High Definition Audio Controller                              | 53        | 0.83%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 50        | 0.78%   |
| Nvidia TU116 High Definition Audio Controller                              | 47        | 0.74%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 45        | 0.7%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 41        | 0.64%   |
| AMD High Definition Audio Controller                                       | 41        | 0.64%   |
| Nvidia MCP79 High Definition Audio                                         | 38        | 0.6%    |
| Nvidia GK107 HDMI Audio Controller                                         | 38        | 0.6%    |
| Nvidia GF108 High Definition Audio Controller                              | 37        | 0.58%   |
| Realtek Semiconductor USB Audio                                            | 32        | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 367       | 28.78%  |
| SK hynix            | 288       | 22.59%  |
| Micron Technology   | 166       | 13.02%  |
| Kingston            | 108       | 8.47%   |
| Crucial             | 69        | 5.41%   |
| Unknown             | 46        | 3.61%   |
| A-DATA Technology   | 30        | 2.35%   |
| Smart               | 27        | 2.12%   |
| Ramaxel Technology  | 22        | 1.73%   |
| Corsair             | 19        | 1.49%   |
| Elpida              | 17        | 1.33%   |
| Goldkey             | 16        | 1.25%   |
| Neo Forza           | 14        | 1.1%    |
| G.Skill             | 12        | 0.94%   |
| Unknown (ABCD)      | 9         | 0.71%   |
| Smart Brazil        | 9         | 0.71%   |
| Teikon              | 6         | 0.47%   |
| Unknown             | 6         | 0.47%   |
| Team                | 5         | 0.39%   |
| Apacer              | 5         | 0.39%   |
| Nanya Technology    | 4         | 0.31%   |
| Patriot             | 3         | 0.24%   |
| High Bridge         | 3         | 0.24%   |
| Avant               | 3         | 0.24%   |
| Timetec             | 2         | 0.16%   |
| PNY                 | 2         | 0.16%   |
| GSkill              | 2         | 0.16%   |
| Goodram             | 2         | 0.16%   |
| Unknown (8A02)      | 1         | 0.08%   |
| Unknown (898F)      | 1         | 0.08%   |
| Silicon Power       | 1         | 0.08%   |
| RZX                 | 1         | 0.08%   |
| PUSKILL             | 1         | 0.08%   |
| Multilaser          | 1         | 0.08%   |
| Magnum Tech         | 1         | 0.08%   |
| Lenovo              | 1         | 0.08%   |
| Hewlett-Packard     | 1         | 0.08%   |
| Gold Key            | 1         | 0.08%   |
| CSX                 | 1         | 0.08%   |
| ChangXin Memory     | 1         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 32        | 2.39%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 25        | 1.87%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 22        | 1.64%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 18        | 1.35%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 16        | 1.2%    |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 16        | 1.2%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 15        | 1.12%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 15        | 1.12%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 14        | 1.05%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 14        | 1.05%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 12        | 0.9%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 11        | 0.82%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 0.82%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 0.82%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 10        | 0.75%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 10        | 0.75%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 10        | 0.75%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 9         | 0.67%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 9         | 0.67%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 9         | 0.67%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 9         | 0.67%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 9         | 0.67%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.6%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 8         | 0.6%    |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 8         | 0.6%    |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 8         | 0.6%    |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 8         | 0.6%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 8         | 0.6%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB SODIMM DDR4 3200MT/s          | 8         | 0.6%    |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 8         | 0.6%    |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 7         | 0.52%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 7         | 0.52%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 7         | 0.52%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 7         | 0.52%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 7         | 0.52%   |
| Neo Forza RAM NMSO432F82-3200E 32GB SODIMM DDR4 3200MT/s         | 7         | 0.52%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 6         | 0.45%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s     | 6         | 0.45%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 6         | 0.45%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 6         | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 703       | 66.45%  |
| DDR3    | 216       | 20.42%  |
| LPDDR4  | 54        | 5.1%    |
| LPDDR3  | 53        | 5.01%   |
| DDR2    | 9         | 0.85%   |
| Unknown | 8         | 0.76%   |
| DDR5    | 6         | 0.57%   |
| LPDDR5  | 5         | 0.47%   |
| SDRAM   | 4         | 0.38%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 926       | 85.98%  |
| Row Of Chips | 136       | 12.63%  |
| Chip         | 11        | 1.02%   |
| DIMM         | 3         | 0.28%   |
| Unknown      | 1         | 0.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 512       | 44.1%   |
| 4096  | 304       | 26.18%  |
| 16384 | 223       | 19.21%  |
| 2048  | 61        | 5.25%   |
| 32768 | 55        | 4.74%   |
| 1024  | 6         | 0.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 357       | 30.86%  |
| 3200    | 243       | 21%     |
| 1600    | 177       | 15.3%   |
| 2400    | 117       | 10.11%  |
| 2133    | 75        | 6.48%   |
| 4267    | 24        | 2.07%   |
| 1334    | 24        | 2.07%   |
| 3266    | 22        | 1.9%    |
| 1333    | 20        | 1.73%   |
| 8400    | 16        | 1.38%   |
| 1867    | 15        | 1.3%    |
| 4800    | 9         | 0.78%   |
| 4266    | 9         | 0.78%   |
| 800     | 8         | 0.69%   |
| 6400    | 6         | 0.52%   |
| 3733    | 6         | 0.52%   |
| 1067    | 6         | 0.52%   |
| 1866    | 5         | 0.43%   |
| 667     | 4         | 0.35%   |
| 2933    | 3         | 0.26%   |
| Unknown | 3         | 0.26%   |
| 4199    | 2         | 0.17%   |
| 2048    | 2         | 0.17%   |
| 3466    | 1         | 0.09%   |
| 3333    | 1         | 0.09%   |
| 3000    | 1         | 0.09%   |
| 1066    | 1         | 0.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 6         | 31.58%  |
| Seiko Epson         | 5         | 26.32%  |
| Canon               | 3         | 15.79%  |
| Brother Industries  | 3         | 15.79%  |
| Samsung Electronics | 1         | 5.26%   |
| MIIIW               | 1         | 5.26%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Seiko Epson WF-3520 Series      | 1         | 5.26%   |
| Seiko Epson L4150 Series        | 1         | 5.26%   |
| Seiko Epson L3110 Series        | 1         | 5.26%   |
| Seiko Epson L132 Series         | 1         | 5.26%   |
| Seiko Epson ET-3750 Series      | 1         | 5.26%   |
| Samsung M2020 Series            | 1         | 5.26%   |
| MIIIW MW Keyboard Air Mini      | 1         | 5.26%   |
| HP Ink Tank Wireless 410 series | 1         | 5.26%   |
| HP ENVY Photo 7800 series       | 1         | 5.26%   |
| HP ENVY 4520 series             | 1         | 5.26%   |
| HP Deskjet 3050 J610 series     | 1         | 5.26%   |
| HP Deskjet 2540 series          | 1         | 5.26%   |
| HP Deskjet 2050 J510            | 1         | 5.26%   |
| Canon GX7000 series             | 1         | 5.26%   |
| Canon G4010 series              | 1         | 5.26%   |
| Canon E400 series               | 1         | 5.26%   |
| Brother HL-L2320D series        | 1         | 5.26%   |
| Brother HL-3170CDW series       | 1         | 5.26%   |
| Brother HL-2270DW Laser Printer | 1         | 5.26%   |

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
| Chicony Electronics                    | 877       | 24.31%  |
| IMC Networks                           | 390       | 10.81%  |
| Microdia                               | 367       | 10.17%  |
| Acer                                   | 361       | 10.01%  |
| Realtek Semiconductor                  | 302       | 8.37%   |
| Sunplus Innovation Technology          | 210       | 5.82%   |
| Quanta                                 | 174       | 4.82%   |
| Apple                                  | 156       | 4.32%   |
| Cheng Uei Precision Industry (Foxlink) | 130       | 3.6%    |
| Suyin                                  | 115       | 3.19%   |
| Syntek                                 | 90        | 2.5%    |
| Lite-On Technology                     | 72        | 2%      |
| Silicon Motion                         | 54        | 1.5%    |
| Logitech                               | 47        | 1.3%    |
| Luxvisions Innotech Limited            | 40        | 1.11%   |
| Ricoh                                  | 36        | 1%      |
| Alcor Micro                            | 27        | 0.75%   |
| Samsung Electronics                    | 20        | 0.55%   |
| ALi                                    | 11        | 0.3%    |
| DigiTech                               | 10        | 0.28%   |
| Sonix Technology                       | 9         | 0.25%   |
| Primax Electronics                     | 9         | 0.25%   |
| Importek                               | 9         | 0.25%   |
| SunplusIT                              | 8         | 0.22%   |
| Microsoft                              | 8         | 0.22%   |
| Lenovo                                 | 7         | 0.19%   |
| Z-Star Microelectronics                | 6         | 0.17%   |
| OmniVision Technologies                | 5         | 0.14%   |
| Intel                                  | 5         | 0.14%   |
| Generalplus Technology                 | 5         | 0.14%   |
| Unknown                                | 4         | 0.11%   |
| Foxconn / Hon Hai                      | 4         | 0.11%   |
| Razer USA                              | 3         | 0.08%   |
| MacroSilicon                           | 3         | 0.08%   |
| AVerMedia Technologies                 | 3         | 0.08%   |
| Sunplus Technology                     | 2         | 0.06%   |
| Mustek Systems                         | 2         | 0.06%   |
| LG Electronics                         | 2         | 0.06%   |
| KYE Systems (Mouse Systems)            | 2         | 0.06%   |
| icSpring                               | 2         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD           | 197       | 5.43%   |
| Chicony Integrated Camera               | 160       | 4.41%   |
| IMC Networks USB2.0 HD UVC WebCam       | 121       | 3.34%   |
| Chicony HD WebCam                       | 121       | 3.34%   |
| Realtek Integrated_Webcam_HD            | 119       | 3.28%   |
| IMC Networks Integrated Camera          | 111       | 3.06%   |
| Chicony USB2.0 Camera                   | 82        | 2.26%   |
| Acer BisonCam,NB Pro                    | 80        | 2.21%   |
| Acer Integrated Camera                  | 67        | 1.85%   |
| Sunplus Integrated_Webcam_HD            | 62        | 1.71%   |
| Syntek Integrated Camera                | 54        | 1.49%   |
| Apple FaceTime HD Camera                | 52        | 1.43%   |
| Apple Built-in iSight                   | 51        | 1.41%   |
| Acer HD Webcam                          | 45        | 1.24%   |
| Quanta HD User Facing                   | 43        | 1.19%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 42        | 1.16%   |
| Acer BisonCam, NB Pro                   | 37        | 1.02%   |
| Chicony USB 2.0 Camera                  | 36        | 0.99%   |
| Apple iPhone5/5C/5S/6                   | 33        | 0.91%   |
| Quanta HD Webcam                        | 31        | 0.85%   |
| Chicony TOSHIBA Web Camera - HD         | 30        | 0.83%   |
| Sunplus HD WebCam                       | 29        | 0.8%    |
| Microdia Integrated Webcam              | 29        | 0.8%    |
| Lite-On Integrated Camera               | 29        | 0.8%    |
| Chicony USB2.0 HD UVC WebCam            | 27        | 0.74%   |
| Chicony Integrated Camera (1280x720@30) | 27        | 0.74%   |
| Microdia Laptop_Integrated_Webcam_HD    | 25        | 0.69%   |
| Chicony USB2.0 VGA UVC WebCam           | 24        | 0.66%   |
| Acer SunplusIT Integrated Camera        | 24        | 0.66%   |
| Chicony HD User Facing                  | 23        | 0.63%   |
| Realtek USB Camera                      | 22        | 0.61%   |
| Quanta VGA WebCam                       | 21        | 0.58%   |
| Chicony HP Wide Vision HD Camera        | 20        | 0.55%   |
| Chicony HP HD Camera                    | 20        | 0.55%   |
| Acer EasyCamera                         | 20        | 0.55%   |
| Sunplus ASUS USB2.0 Webcam              | 19        | 0.52%   |
| Realtek Integrated Webcam HD            | 19        | 0.52%   |
| Quanta HP TrueVision HD Camera          | 19        | 0.52%   |
| Chicony HP HD Webcam                    | 19        | 0.52%   |
| Chicony EasyCamera                      | 19        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 214       | 30.79%  |
| Validity Sensors           | 211       | 30.36%  |
| Shenzhen Goodix Technology | 128       | 18.42%  |
| Upek                       | 41        | 5.9%    |
| Elan Microelectronics      | 35        | 5.04%   |
| LighTuning Technology      | 32        | 4.6%    |
| AuthenTec                  | 23        | 3.31%   |
| STMicroelectronics         | 7         | 1.01%   |
| HOLTEK                     | 2         | 0.29%   |
| Samsung Electronics        | 1         | 0.14%   |
| DigitalPersona             | 1         | 0.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 64        | 9.21%   |
| Unknown                                                                    | 63        | 9.06%   |
| Shenzhen Goodix  Fingerprint Device                                        | 60        | 8.63%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 49        | 7.05%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 41        | 5.9%    |
| Shenzhen Goodix FingerPrint                                                | 41        | 5.9%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 38        | 5.47%   |
| Elan ELAN:Fingerprint                                                      | 30        | 4.32%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 28        | 4.03%   |
| Shenzhen Goodix Fingerprint Reader                                         | 27        | 3.88%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 19        | 2.73%   |
| Validity Sensors VFS491                                                    | 18        | 2.59%   |
| Synaptics WBDI Device                                                      | 18        | 2.59%   |
| Validity Sensors Synaptics WBDI                                            | 17        | 2.45%   |
| Validity Sensors Fingerprint scanner                                       | 16        | 2.3%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 16        | 2.3%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 15        | 2.16%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 14        | 2.01%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 12        | 1.73%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 9         | 1.29%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 9         | 1.29%   |
| Synaptics  WBDI                                                            | 8         | 1.15%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 8         | 1.15%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 7         | 1.01%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 1.01%   |
| AuthenTec AES2810                                                          | 7         | 1.01%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 0.86%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 0.72%   |
| Elan ELAN:ARM-M4                                                           | 5         | 0.72%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 0.72%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 0.58%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 0.58%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 3         | 0.43%   |
| Upek TCS5B Fingerprint sensor                                              | 3         | 0.43%   |
| AuthenTec AES1600                                                          | 3         | 0.43%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.29%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.29%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.29%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.29%   |
| HOLTEK FocalTech Fingerprint Device                                        | 2         | 0.29%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 126       | 46.32%  |
| Alcor Micro               | 73        | 26.84%  |
| Upek                      | 28        | 10.29%  |
| O2 Micro                  | 21        | 7.72%   |
| Lenovo                    | 16        | 5.88%   |
| Aladdin Knowledge Systems | 2         | 0.74%   |
| SCM Microsystems          | 1         | 0.37%   |
| OmniKey                   | 1         | 0.37%   |
| Giesecke & Devrient       | 1         | 0.37%   |
| Gemalto (was Gemplus)     | 1         | 0.37%   |
| Clay Logic                | 1         | 0.37%   |
| Advanced Card Systems     | 1         | 0.37%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 73        | 26.84%  |
| Broadcom BCM5880 Secure Applications Processor                               | 41        | 15.07%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 35        | 12.87%  |
| Broadcom 5880                                                                | 35        | 12.87%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 28        | 10.29%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 17        | 6.25%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 5.88%   |
| Broadcom 58200                                                               | 13        | 4.78%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.47%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.74%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.74%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.37%   |
| OmniKey CardMan 4321                                                         | 1         | 0.37%   |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.37%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.37%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.37%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.37%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2575      | 62.44%  |
| 1     | 1216      | 29.49%  |
| 2     | 287       | 6.96%   |
| 3     | 40        | 0.97%   |
| 4     | 5         | 0.12%   |
| 5     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 677       | 36.2%   |
| Chipcard                 | 265       | 14.17%  |
| Multimedia controller    | 251       | 13.42%  |
| Net/wireless             | 232       | 12.41%  |
| Graphics card            | 215       | 11.5%   |
| Bluetooth                | 63        | 3.37%   |
| Storage                  | 35        | 1.87%   |
| Camera                   | 30        | 1.6%    |
| Net/ethernet             | 25        | 1.34%   |
| Sound                    | 21        | 1.12%   |
| Card reader              | 14        | 0.75%   |
| Communication controller | 13        | 0.7%    |
| Network                  | 8         | 0.43%   |
| Modem                    | 8         | 0.43%   |
| Storage/ide              | 5         | 0.27%   |
| Storage/nvme             | 2         | 0.11%   |
| Flash memory             | 2         | 0.11%   |
| Firewire controller      | 2         | 0.11%   |
| Unclassified device      | 1         | 0.05%   |
| Dvb card                 | 1         | 0.05%   |


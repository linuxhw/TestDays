Pop!_OS 22.04 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Pop!_OS 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 936

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
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [4dd83a1b80](https://linux-hardware.org/?probe=4dd83a1b80) | Sep 16, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [b0e6601fbf](https://linux-hardware.org/?probe=b0e6601fbf) | Sep 16, 2022 |
| ASUSTek       | N550LF                      | [73f2edfe65](https://linux-hardware.org/?probe=73f2edfe65) | Sep 16, 2022 |
| Apple         | MacBookPro5,4               | [9cc24963d4](https://linux-hardware.org/?probe=9cc24963d4) | Sep 16, 2022 |
| Apple         | MacBookPro5,4               | [6d28bb81ce](https://linux-hardware.org/?probe=6d28bb81ce) | Sep 16, 2022 |
| Toshiba       | Satellite C55t-C            | [9c45d5a042](https://linux-hardware.org/?probe=9c45d5a042) | Sep 16, 2022 |
| Dell          | XPS 13 9380                 | [6d94f648e4](https://linux-hardware.org/?probe=6d94f648e4) | Sep 16, 2022 |
| GPD           | MicroPC                     | [dadac68a23](https://linux-hardware.org/?probe=dadac68a23) | Sep 15, 2022 |
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
| Lenovo        | ThinkPad L512 44444WG       | [06da05d12b](https://linux-hardware.org/?probe=06da05d12b) | Aug 03, 2022 |
| MSI           | GF63 Thin 11UD              | [bf4a2c0e11](https://linux-hardware.org/?probe=bf4a2c0e11) | Aug 03, 2022 |
| MSI           | GF63 Thin 11UD              | [f31ac48621](https://linux-hardware.org/?probe=f31ac48621) | Aug 03, 2022 |
| Dell          | Inspiron N5040              | [2da4d2a843](https://linux-hardware.org/?probe=2da4d2a843) | Aug 03, 2022 |
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
| Acer          | Swift SF314-51              | [f9a61fd8ad](https://linux-hardware.org/?probe=f9a61fd8ad) | Jul 31, 2022 |
| Acer          | Swift SF314-43              | [36659d2410](https://linux-hardware.org/?probe=36659d2410) | Jul 30, 2022 |
| Toshiba       | Satellite C75D-C            | [f4a9c3bc7f](https://linux-hardware.org/?probe=f4a9c3bc7f) | Jul 30, 2022 |
| Toshiba       | Satellite C75D-C            | [f017593574](https://linux-hardware.org/?probe=f017593574) | Jul 30, 2022 |
| Dell          | Vostro 15 3515              | [74b9e88d97](https://linux-hardware.org/?probe=74b9e88d97) | Jul 30, 2022 |
| Intel Clie... | LAPKC71F                    | [0783ac445f](https://linux-hardware.org/?probe=0783ac445f) | Jul 30, 2022 |
| Lenovo        | ThinkPad P53 20QN003TUS     | [bf8e504209](https://linux-hardware.org/?probe=bf8e504209) | Jul 30, 2022 |
| PC Special... | NS50MU                      | [b5dd220296](https://linux-hardware.org/?probe=b5dd220296) | Jul 29, 2022 |
| Positivo      | C4128E-S                    | [a06c799159](https://linux-hardware.org/?probe=a06c799159) | Jul 29, 2022 |
| Lenovo        | ThinkPad P53 20QN003TUS     | [cf54e60bf1](https://linux-hardware.org/?probe=cf54e60bf1) | Jul 29, 2022 |
| GPU Compan... | GWTN141-10                  | [e392f0348d](https://linux-hardware.org/?probe=e392f0348d) | Jul 29, 2022 |
| GPU Compan... | GWTN141-10                  | [dea75365be](https://linux-hardware.org/?probe=dea75365be) | Jul 29, 2022 |
| HP            | Pavilion 13 x360 PC         | [a5220ea2c0](https://linux-hardware.org/?probe=a5220ea2c0) | Jul 28, 2022 |
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
| MSI           | Pulse GL66 12UEK            | [9bffffd652](https://linux-hardware.org/?probe=9bffffd652) | Jun 20, 2022 |
| MSI           | Pulse GL66 12UEK            | [a8d859700b](https://linux-hardware.org/?probe=a8d859700b) | Jun 20, 2022 |
| HP            | ZBook 15 G3                 | [8c6f371222](https://linux-hardware.org/?probe=8c6f371222) | Jun 19, 2022 |
| ASUSTek       | N550JV                      | [d1d647724c](https://linux-hardware.org/?probe=d1d647724c) | Jun 19, 2022 |
| Apple         | MacBookPro11,1              | [b88b88ba84](https://linux-hardware.org/?probe=b88b88ba84) | Jun 19, 2022 |
| Apple         | MacBookPro11,1              | [ec132b0ba5](https://linux-hardware.org/?probe=ec132b0ba5) | Jun 19, 2022 |
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
| Acer          | Nitro AN515-42              | [a2f2dc2eee](https://linux-hardware.org/?probe=a2f2dc2eee) | May 27, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [65bccd9c04](https://linux-hardware.org/?probe=65bccd9c04) | May 27, 2022 |
| Dell          | Vostro 5402                 | [323fc36eb6](https://linux-hardware.org/?probe=323fc36eb6) | May 27, 2022 |
| Toshiba       | QOSMIO X770                 | [8f7d0ba9f9](https://linux-hardware.org/?probe=8f7d0ba9f9) | May 27, 2022 |
| Dell          | Precision 5530              | [2ecf3390bf](https://linux-hardware.org/?probe=2ecf3390bf) | May 27, 2022 |
| Acer          | Aspire A315-57G             | [d0400f8d02](https://linux-hardware.org/?probe=d0400f8d02) | May 26, 2022 |
| Fujitsu       | CELSIUS H730                | [6f0b24d450](https://linux-hardware.org/?probe=6f0b24d450) | May 26, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [ab2cd65153](https://linux-hardware.org/?probe=ab2cd65153) | May 26, 2022 |
| Dell          | Inspiron 3721               | [d4af21adb8](https://linux-hardware.org/?probe=d4af21adb8) | May 25, 2022 |
| A-DATA Tec... | XENIA 15                    | [1d7941d921](https://linux-hardware.org/?probe=1d7941d921) | May 25, 2022 |
| Lenovo        | ThinkPad X220 4286CTO       | [4c0d37687e](https://linux-hardware.org/?probe=4c0d37687e) | May 25, 2022 |
| Toshiba       | Satellite P850              | [9ec49310ff](https://linux-hardware.org/?probe=9ec49310ff) | May 25, 2022 |
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
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [f2e32c336d](https://linux-hardware.org/?probe=f2e32c336d) | May 23, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [7fa4ca7312](https://linux-hardware.org/?probe=7fa4ca7312) | May 23, 2022 |
| Acer          | TravelMate 7750G            | [3ff0c1c7f2](https://linux-hardware.org/?probe=3ff0c1c7f2) | May 23, 2022 |
| Acer          | TravelMate 7750G            | [80bfe5a0c6](https://linux-hardware.org/?probe=80bfe5a0c6) | May 23, 2022 |
| Apple         | MacBookPro11,1              | [1d4f3a60c0](https://linux-hardware.org/?probe=1d4f3a60c0) | May 23, 2022 |
| ASUSTek       | X505BA                      | [685c1f7378](https://linux-hardware.org/?probe=685c1f7378) | May 22, 2022 |
| Lenovo        | ThinkPad T480 20L5S00F00    | [7a1f70c8aa](https://linux-hardware.org/?probe=7a1f70c8aa) | May 22, 2022 |
| Dell          | G3 3500                     | [49f86cc226](https://linux-hardware.org/?probe=49f86cc226) | May 22, 2022 |
| Google        | Lulu                        | [e7a0842114](https://linux-hardware.org/?probe=e7a0842114) | May 21, 2022 |
| MSI           | Modern 14 A10M              | [97a0996658](https://linux-hardware.org/?probe=97a0996658) | May 21, 2022 |
| HP            | Pavilion Notebook           | [1cd571d585](https://linux-hardware.org/?probe=1cd571d585) | May 21, 2022 |
| ASUSTek       | X510UR                      | [40b1695a67](https://linux-hardware.org/?probe=40b1695a67) | May 21, 2022 |
| ASUSTek       | X510UR                      | [e7cea85f09](https://linux-hardware.org/?probe=e7cea85f09) | May 21, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [bc911a9c04](https://linux-hardware.org/?probe=bc911a9c04) | May 21, 2022 |
| PC Special... | NP5x_NP6x_NP7xPNK_PNH_PN... | [e002072665](https://linux-hardware.org/?probe=e002072665) | May 21, 2022 |
| HP            | EliteBook 8570w             | [3f21c66d5c](https://linux-hardware.org/?probe=3f21c66d5c) | May 20, 2022 |
| Lenovo        | G40-30 80FY                 | [4280810a31](https://linux-hardware.org/?probe=4280810a31) | May 20, 2022 |
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
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [3a369eed6d](https://linux-hardware.org/?probe=3a369eed6d) | May 16, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [a8fffad424](https://linux-hardware.org/?probe=a8fffad424) | May 16, 2022 |
| Apple         | MacBookPro16,2              | [ceb6a7e5a3](https://linux-hardware.org/?probe=ceb6a7e5a3) | May 16, 2022 |
| Apple         | MacBookPro16,2              | [5c4ebc223f](https://linux-hardware.org/?probe=5c4ebc223f) | May 16, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [3ecda9477c](https://linux-hardware.org/?probe=3ecda9477c) | May 16, 2022 |
| Apple         | MacBookPro14,1              | [2d4d81086f](https://linux-hardware.org/?probe=2d4d81086f) | May 15, 2022 |
| Acer          | TravelMate P249-G2-MG       | [e6f35b116a](https://linux-hardware.org/?probe=e6f35b116a) | May 15, 2022 |
| Dell          | Vostro 5471                 | [62e934492d](https://linux-hardware.org/?probe=62e934492d) | May 15, 2022 |
| Dell          | XPS 15 9510                 | [653725bdde](https://linux-hardware.org/?probe=653725bdde) | May 15, 2022 |
| Dell          | XPS 15 9560                 | [04f0e074cb](https://linux-hardware.org/?probe=04f0e074cb) | May 14, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [7a2fd723d6](https://linux-hardware.org/?probe=7a2fd723d6) | May 14, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [98db0dde2a](https://linux-hardware.org/?probe=98db0dde2a) | May 13, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [66e43801f0](https://linux-hardware.org/?probe=66e43801f0) | May 13, 2022 |
| Google        | Lulu                        | [8d7f1657d0](https://linux-hardware.org/?probe=8d7f1657d0) | May 13, 2022 |
| Acer          | Swift SF314-54              | [a31c36956a](https://linux-hardware.org/?probe=a31c36956a) | May 13, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [30bb58501e](https://linux-hardware.org/?probe=30bb58501e) | May 13, 2022 |
| Apple         | MacBookPro5,2               | [0a3017f333](https://linux-hardware.org/?probe=0a3017f333) | May 13, 2022 |
| Acer          | Nitro AN515-44              | [fe8e3837f4](https://linux-hardware.org/?probe=fe8e3837f4) | May 12, 2022 |
| System76      | Pangolin                    | [0f05fa93a8](https://linux-hardware.org/?probe=0f05fa93a8) | May 12, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [ea75711bf8](https://linux-hardware.org/?probe=ea75711bf8) | May 12, 2022 |
| Apple         | MacBookAir7,2               | [114ef2756f](https://linux-hardware.org/?probe=114ef2756f) | May 12, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [915b95cae4](https://linux-hardware.org/?probe=915b95cae4) | May 11, 2022 |
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
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [a9f5b77476](https://linux-hardware.org/?probe=a9f5b77476) | May 04, 2022 |
| Acer          | Aspire A515-45              | [e5f3e5b086](https://linux-hardware.org/?probe=e5f3e5b086) | May 04, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [8bfd6ecc71](https://linux-hardware.org/?probe=8bfd6ecc71) | May 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [720d11c11f](https://linux-hardware.org/?probe=720d11c11f) | May 04, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5a8fc607c4](https://linux-hardware.org/?probe=5a8fc607c4) | May 04, 2022 |
| Dell          | Inspiron 3583               | [f5e954ea5e](https://linux-hardware.org/?probe=f5e954ea5e) | May 04, 2022 |
| HP            | Pavilion 13 x360 PC         | [5de9e1d61f](https://linux-hardware.org/?probe=5de9e1d61f) | May 04, 2022 |
| ASUSTek       | X540SAA                     | [9943699a6b](https://linux-hardware.org/?probe=9943699a6b) | May 04, 2022 |
| Acer          | Aspire F5-573G              | [2136362d58](https://linux-hardware.org/?probe=2136362d58) | May 03, 2022 |
| HP            | Laptop 17-ca3xxx            | [373f22a70f](https://linux-hardware.org/?probe=373f22a70f) | May 03, 2022 |
| HP            | Laptop 17-ca3xxx            | [91a367d874](https://linux-hardware.org/?probe=91a367d874) | May 03, 2022 |
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
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [863612cc05](https://linux-hardware.org/?probe=863612cc05) | Apr 27, 2022 |
| Purism        | Librem 15 v3                | [d2a13c9d0a](https://linux-hardware.org/?probe=d2a13c9d0a) | Apr 27, 2022 |
| Toshiba       | Satellite C55t-C            | [1fe2032839](https://linux-hardware.org/?probe=1fe2032839) | Apr 27, 2022 |
| Toshiba       | Satellite C55t-C            | [cabf0c7464](https://linux-hardware.org/?probe=cabf0c7464) | Apr 27, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [b7ac79ff8f](https://linux-hardware.org/?probe=b7ac79ff8f) | Apr 27, 2022 |
| MSI           | GS66 Stealth 10UG           | [77b699045a](https://linux-hardware.org/?probe=77b699045a) | Apr 27, 2022 |
| Acer          | Aspire E1-570               | [1621e22812](https://linux-hardware.org/?probe=1621e22812) | Apr 26, 2022 |
| Acer          | Swift SF316-51              | [fe42983639](https://linux-hardware.org/?probe=fe42983639) | Apr 26, 2022 |
| Acer          | TravelMate P249-G2-MG       | [2e0bd790c6](https://linux-hardware.org/?probe=2e0bd790c6) | Apr 26, 2022 |
| Dell          | Inspiron 3442               | [d4b7580074](https://linux-hardware.org/?probe=d4b7580074) | Apr 26, 2022 |
| Dell          | Inspiron 3442               | [d994ff2a13](https://linux-hardware.org/?probe=d994ff2a13) | Apr 26, 2022 |
| Unknown       | Unknown                     | [885f468161](https://linux-hardware.org/?probe=885f468161) | Apr 26, 2022 |
| ASUSTek       | X555LF                      | [0aa3a88c0c](https://linux-hardware.org/?probe=0aa3a88c0c) | Apr 25, 2022 |
| Dell          | XPS 13 9360                 | [ffb9cf10be](https://linux-hardware.org/?probe=ffb9cf10be) | Apr 20, 2022 |
| Dell          | XPS 13 9360                 | [f174d4ced7](https://linux-hardware.org/?probe=f174d4ced7) | Apr 20, 2022 |
| Toshiba       | IS 1413G                    | [1b3267b605](https://linux-hardware.org/?probe=1b3267b605) | Apr 18, 2022 |
| Dell          | Latitude 5590               | [ade3f33fb9](https://linux-hardware.org/?probe=ade3f33fb9) | Apr 16, 2022 |
| Dell          | Latitude 5590               | [1638db9ad7](https://linux-hardware.org/?probe=1638db9ad7) | Apr 13, 2022 |
| Dell          | Latitude E7270              | [79cc908dcc](https://linux-hardware.org/?probe=79cc908dcc) | Apr 08, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS_22.04/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                              | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| 5.17.5-76051705-generic              | 222       | 31.4%   |
| 5.19.0-76051900-generic              | 185       | 26.17%  |
| 5.18.10-76051810-generic             | 107       | 15.13%  |
| 5.17.15-76051715-generic             | 103       | 14.57%  |
| 5.16.19-76051619-generic             | 70        | 9.9%    |
| 5.17.5-051705-generic                | 2         | 0.28%   |
| 5.16.15-76051615-generic             | 2         | 0.28%   |
| 6.0.0-060000rc7-generic              | 1         | 0.14%   |
| 6.0.0-060000rc1daily20220820-generic | 1         | 0.14%   |
| 5.19.3-051903-generic                | 1         | 0.14%   |
| 5.19.12-xanmod1                      | 1         | 0.14%   |
| 5.19.0-rc1+                          | 1         | 0.14%   |
| 5.18.6-xanmod1                       | 1         | 0.14%   |
| 5.18.4-xanmod1                       | 1         | 0.14%   |
| 5.18.16-xanmod1                      | 1         | 0.14%   |
| 5.18.0-051800rc1-generic             | 1         | 0.14%   |
| 5.17.7-051707-generic                | 1         | 0.14%   |
| 5.17.6-051706-generic                | 1         | 0.14%   |
| 5.17.5-tkg-bmq                       | 1         | 0.14%   |
| 5.17.2-xanmod1                       | 1         | 0.14%   |
| 5.17.0-051700-generic                | 1         | 0.14%   |
| 5.16.11-76051611-generic             | 1         | 0.14%   |
| 5.15.0-46-generic                    | 1         | 0.14%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17.5  | 225       | 31.82%  |
| 5.19.0  | 186       | 26.31%  |
| 5.18.10 | 107       | 15.13%  |
| 5.17.15 | 103       | 14.57%  |
| 5.16.19 | 70        | 9.9%    |
| 6.0.0   | 2         | 0.28%   |
| 5.16.15 | 2         | 0.28%   |
| 5.19.3  | 1         | 0.14%   |
| 5.19.12 | 1         | 0.14%   |
| 5.18.6  | 1         | 0.14%   |
| 5.18.4  | 1         | 0.14%   |
| 5.18.16 | 1         | 0.14%   |
| 5.18.0  | 1         | 0.14%   |
| 5.17.7  | 1         | 0.14%   |
| 5.17.6  | 1         | 0.14%   |
| 5.17.2  | 1         | 0.14%   |
| 5.17.0  | 1         | 0.14%   |
| 5.16.11 | 1         | 0.14%   |
| 5.15.0  | 1         | 0.14%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17    | 326       | 46.57%  |
| 5.19    | 187       | 26.71%  |
| 5.18    | 111       | 15.86%  |
| 5.16    | 73        | 10.43%  |
| 6.0     | 2         | 0.29%   |
| 5.15    | 1         | 0.14%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 674       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 655       | 96.89%  |
| KDE5            | 8         | 1.18%   |
| Unknown         | 6         | 0.89%   |
| X-Cinnamon      | 2         | 0.3%    |
| GNOME Flashback | 2         | 0.3%    |
| XFCE            | 1         | 0.15%   |
| Unity           | 1         | 0.15%   |
| LXQt            | 1         | 0.15%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 642       | 94.69%  |
| Wayland | 29        | 4.28%   |
| Unknown | 5         | 0.74%   |
| Tty     | 2         | 0.29%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 511       | 75.15%  |
| GDM3    | 167       | 24.56%  |
| GDM     | 2         | 0.29%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 414       | 61.15%  |
| en_GB   | 41        | 6.06%   |
| pt_BR   | 40        | 5.91%   |
| de_DE   | 24        | 3.55%   |
| en_AU   | 21        | 3.1%    |
| C       | 14        | 2.07%   |
| it_IT   | 13        | 1.92%   |
| fr_FR   | 13        | 1.92%   |
| ru_RU   | 9         | 1.33%   |
| en_CA   | 9         | 1.33%   |
| es_ES   | 8         | 1.18%   |
| pl_PL   | 6         | 0.89%   |
| sv_SE   | 5         | 0.74%   |
| nb_NO   | 5         | 0.74%   |
| pt_PT   | 4         | 0.59%   |
| de_CH   | 4         | 0.59%   |
| Unknown | 4         | 0.59%   |
| es_MX   | 3         | 0.44%   |
| es_CO   | 3         | 0.44%   |
| en_NZ   | 3         | 0.44%   |
| en_IN   | 3         | 0.44%   |
| en_IE   | 3         | 0.44%   |
| nl_NL   | 2         | 0.3%    |
| fr_CA   | 2         | 0.3%    |
| es_CL   | 2         | 0.3%    |
| es_AR   | 2         | 0.3%    |
| en_ZA   | 2         | 0.3%    |
| en_DK   | 2         | 0.3%    |
| da_DK   | 2         | 0.3%    |
| sr_RS   | 1         | 0.15%   |
| ro_RO   | 1         | 0.15%   |
| hr_HR   | 1         | 0.15%   |
| fr_CH   | 1         | 0.15%   |
| fr_BE   | 1         | 0.15%   |
| fi_FI   | 1         | 0.15%   |
| es_UY   | 1         | 0.15%   |
| es_HN   | 1         | 0.15%   |
| es_GT   | 1         | 0.15%   |
| es_BO   | 1         | 0.15%   |
| en_SG   | 1         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 519       | 76.44%  |
| EFI  | 160       | 23.56%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 643       | 95.12%  |
| Btrfs   | 23        | 3.4%    |
| Overlay | 7         | 1.04%   |
| Xfs     | 3         | 0.44%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 506       | 74.41%  |
| GPT     | 162       | 23.82%  |
| MBR     | 12        | 1.76%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 654       | 96.89%  |
| Yes       | 21        | 3.11%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 616       | 90.86%  |
| Yes       | 62        | 9.14%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 133       | 19.73%  |
| Dell                 | 123       | 18.25%  |
| ASUSTek Computer     | 92        | 13.65%  |
| Hewlett-Packard      | 73        | 10.83%  |
| Acer                 | 51        | 7.57%   |
| Apple                | 47        | 6.97%   |
| MSI                  | 29        | 4.3%    |
| System76             | 22        | 3.26%   |
| Toshiba              | 16        | 2.37%   |
| Samsung Electronics  | 12        | 1.78%   |
| HUAWEI               | 12        | 1.78%   |
| GPU Company          | 6         | 0.89%   |
| Notebook             | 4         | 0.59%   |
| Google               | 4         | 0.59%   |
| Fujitsu              | 4         | 0.59%   |
| Sony                 | 3         | 0.45%   |
| Gigabyte Technology  | 3         | 0.45%   |
| Framework            | 3         | 0.45%   |
| Alienware            | 3         | 0.45%   |
| TUXEDO               | 2         | 0.3%    |
| Timi                 | 2         | 0.3%    |
| Razer                | 2         | 0.3%    |
| PC Specialist        | 2         | 0.3%    |
| Panasonic            | 2         | 0.3%    |
| Medion               | 2         | 0.3%    |
| HONOR                | 2         | 0.3%    |
| Semp Toshiba         | 1         | 0.15%   |
| Schenker             | 1         | 0.15%   |
| Quanta               | 1         | 0.15%   |
| Purism               | 1         | 0.15%   |
| Positivo             | 1         | 0.15%   |
| Pegatron             | 1         | 0.15%   |
| OriginPC             | 1         | 0.15%   |
| Monster              | 1         | 0.15%   |
| LG Electronics       | 1         | 0.15%   |
| Itronix              | 1         | 0.15%   |
| Intel Client Systems | 1         | 0.15%   |
| GPD                  | 1         | 0.15%   |
| Gateway              | 1         | 0.15%   |
| Eluktronics          | 1         | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| System76 Oryx Pro                    | 9         | 1.34%   |
| Apple MacBookAir7,2                  | 5         | 0.74%   |
| Lenovo IdeaPad S145-15API 81V7       | 4         | 0.59%   |
| Dell XPS 15 9520                     | 4         | 0.59%   |
| Apple MacBookPro9,2                  | 4         | 0.59%   |
| Apple MacBookAir6,2                  | 4         | 0.59%   |
| Unknown                              | 4         | 0.59%   |
| System76 Lemur Pro                   | 3         | 0.45%   |
| System76 Galago Pro                  | 3         | 0.45%   |
| System76 Darter Pro                  | 3         | 0.45%   |
| MSI Prestige 15 A10SC                | 3         | 0.45%   |
| HP Pavilion Notebook                 | 3         | 0.45%   |
| HP OMEN Laptop 15-en0xxx             | 3         | 0.45%   |
| HP Dev One Notebook PC               | 3         | 0.45%   |
| GPU Company GWTN141-10               | 3         | 0.45%   |
| GPU Company GWTC116-2                | 3         | 0.45%   |
| Framework Laptop                     | 3         | 0.45%   |
| Dell XPS 13 9305                     | 3         | 0.45%   |
| Dell Latitude E7240                  | 3         | 0.45%   |
| Dell Inspiron 5547                   | 3         | 0.45%   |
| Apple MacBookPro7,1                  | 3         | 0.45%   |
| Acer Aspire A515-45                  | 3         | 0.45%   |
| Toshiba Satellite C55t-C             | 2         | 0.3%    |
| System76 Pangolin                    | 2         | 0.3%    |
| Samsung 760XDA                       | 2         | 0.3%    |
| MSI Katana GF76 11UD                 | 2         | 0.3%    |
| MSI GF63 Thin 11UD                   | 2         | 0.3%    |
| Lenovo V14-IIL 82C4                  | 2         | 0.3%    |
| Lenovo ThinkPad E14 Gen 4 21ECS00000 | 2         | 0.3%    |
| Lenovo Legion Y530-15ICH 81FV        | 2         | 0.3%    |
| Lenovo Legion 7 16ITHg6 82K6         | 2         | 0.3%    |
| Lenovo Legion 5 15IMH05H 81Y6        | 2         | 0.3%    |
| Lenovo Legion 5 15ACH6H 82JU         | 2         | 0.3%    |
| Lenovo Legion 5 15ACH6 82JW          | 2         | 0.3%    |
| Lenovo IdeaPad 5 Pro 16ARH7 82SN     | 2         | 0.3%    |
| Lenovo IdeaPad 3 15ALC6 82MF         | 2         | 0.3%    |
| HUAWEI KPL-W0X                       | 2         | 0.3%    |
| HUAWEI HN-WX9X                       | 2         | 0.3%    |
| HP Pavilion 15                       | 2         | 0.3%    |
| HP Pavilion 13 x360 PC               | 2         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 60        | 8.9%    |
| Acer Aspire        | 35        | 5.19%   |
| Dell Inspiron      | 34        | 5.04%   |
| Lenovo IdeaPad     | 31        | 4.6%    |
| Dell Latitude      | 30        | 4.45%   |
| Dell XPS           | 26        | 3.86%   |
| ASUS ROG           | 20        | 2.97%   |
| Lenovo Legion      | 18        | 2.67%   |
| HP Pavilion        | 16        | 2.37%   |
| Toshiba Satellite  | 13        | 1.93%   |
| HP Laptop          | 13        | 1.93%   |
| Dell Precision     | 13        | 1.93%   |
| HP EliteBook       | 12        | 1.78%   |
| Dell Vostro        | 12        | 1.78%   |
| System76 Oryx      | 9         | 1.34%   |
| HP ProBook         | 9         | 1.34%   |
| ASUS VivoBook      | 9         | 1.34%   |
| HP OMEN            | 7         | 1.04%   |
| ASUS ASUS          | 7         | 1.04%   |
| Lenovo ThinkBook   | 6         | 0.89%   |
| ASUS Zenbook       | 6         | 0.89%   |
| Apple MacBookPro11 | 6         | 0.89%   |
| Acer Swift         | 6         | 0.89%   |
| Acer Nitro         | 6         | 0.89%   |
| MSI Prestige       | 5         | 0.74%   |
| Apple MacBookPro9  | 5         | 0.74%   |
| Apple MacBookAir7  | 5         | 0.74%   |
| System76 Galago    | 4         | 0.59%   |
| MSI Katana         | 4         | 0.59%   |
| MSI GF63           | 4         | 0.59%   |
| HP ZBook           | 4         | 0.59%   |
| Apple MacBookAir6  | 4         | 0.59%   |
| Apple MacBook5     | 4         | 0.59%   |
| Unknown            | 4         | 0.59%   |
| System76 Lemur     | 3         | 0.45%   |
| System76 Darter    | 3         | 0.45%   |
| MSI Modern         | 3         | 0.45%   |
| Lenovo Yoga        | 3         | 0.45%   |
| HP ENVY            | 3         | 0.45%   |
| HP Dev             | 3         | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 118       | 17.51%  |
| 2020 | 84        | 12.46%  |
| 2019 | 58        | 8.61%   |
| 2018 | 57        | 8.46%   |
| 2022 | 51        | 7.57%   |
| 2013 | 48        | 7.12%   |
| 2016 | 40        | 5.93%   |
| 2015 | 36        | 5.34%   |
| 2012 | 36        | 5.34%   |
| 2017 | 34        | 5.04%   |
| 2014 | 34        | 5.04%   |
| 2011 | 32        | 4.75%   |
| 2009 | 21        | 3.12%   |
| 2010 | 20        | 2.97%   |
| 2008 | 3         | 0.45%   |
| 2007 | 2         | 0.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 674       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 674       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 654       | 97.03%  |
| Yes  | 20        | 2.97%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 189       | 27.92%  |
| 16.01-24.0  | 175       | 25.85%  |
| 8.01-16.0   | 131       | 19.35%  |
| 3.01-4.0    | 84        | 12.41%  |
| 32.01-64.0  | 67        | 9.9%    |
| 64.01-256.0 | 17        | 2.51%   |
| 24.01-32.0  | 10        | 1.48%   |
| 1.01-2.0    | 3         | 0.44%   |
| 2.01-3.0    | 1         | 0.15%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 257       | 36.4%   |
| 4.01-8.0   | 157       | 22.24%  |
| 3.01-4.0   | 154       | 21.81%  |
| 1.01-2.0   | 96        | 13.6%   |
| 8.01-16.0  | 37        | 5.24%   |
| 16.01-24.0 | 5         | 0.71%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 486       | 71.89%  |
| 2      | 165       | 24.41%  |
| 3      | 23        | 3.4%    |
| 7      | 1         | 0.15%   |
| 0      | 1         | 0.15%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 519       | 77%     |
| Yes       | 155       | 23%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 524       | 77.4%   |
| No        | 153       | 22.6%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 673       | 99.85%  |
| No        | 1         | 0.15%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 584       | 86.14%  |
| No        | 94        | 13.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 183       | 26.99%  |
| Brazil      | 64        | 9.44%   |
| Germany     | 42        | 6.19%   |
| India       | 29        | 4.28%   |
| Canada      | 26        | 3.83%   |
| UK          | 25        | 3.69%   |
| Australia   | 25        | 3.69%   |
| Italy       | 21        | 3.1%    |
| France      | 19        | 2.8%    |
| Russia      | 18        | 2.65%   |
| Norway      | 12        | 1.77%   |
| Netherlands | 11        | 1.62%   |
| Sweden      | 10        | 1.47%   |
| Mexico      | 10        | 1.47%   |
| Switzerland | 9         | 1.33%   |
| Spain       | 8         | 1.18%   |
| Poland      | 8         | 1.18%   |
| Romania     | 7         | 1.03%   |
| New Zealand | 7         | 1.03%   |
| Argentina   | 7         | 1.03%   |
| Portugal    | 6         | 0.88%   |
| Philippines | 6         | 0.88%   |
| Greece      | 6         | 0.88%   |
| Colombia    | 6         | 0.88%   |
| Belgium     | 6         | 0.88%   |
| Turkey      | 5         | 0.74%   |
| Chile       | 5         | 0.74%   |
| Serbia      | 4         | 0.59%   |
| Malaysia    | 4         | 0.59%   |
| Finland     | 4         | 0.59%   |
| Egypt       | 4         | 0.59%   |
| Denmark     | 4         | 0.59%   |
| Bulgaria    | 4         | 0.59%   |
| Austria     | 4         | 0.59%   |
| Vietnam     | 3         | 0.44%   |
| Thailand    | 3         | 0.44%   |
| Singapore   | 3         | 0.44%   |
| Morocco     | 3         | 0.44%   |
| Ireland     | 3         | 0.44%   |
| Hungary     | 3         | 0.44%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Brisbane       | 10        | 1.45%   |
| Oslo           | 6         | 0.87%   |
| Melbourne      | 6         | 0.87%   |
| Rio de Janeiro | 5         | 0.73%   |
| Mumbai         | 5         | 0.73%   |
| Moscow         | 5         | 0.73%   |
| Berlin         | 5         | 0.73%   |
| Bengaluru      | 5         | 0.73%   |
| Zurich         | 4         | 0.58%   |
| Sydney         | 4         | 0.58%   |
| Stockholm      | 4         | 0.58%   |
| St Petersburg  | 4         | 0.58%   |
| Sao Paulo      | 4         | 0.58%   |
| Paris          | 4         | 0.58%   |
| Munich         | 4         | 0.58%   |
| Istanbul       | 4         | 0.58%   |
| Bucharest      | 4         | 0.58%   |
| Warsaw         | 3         | 0.44%   |
| Sofia          | 3         | 0.44%   |
| Singapore      | 3         | 0.44%   |
| San Diego      | 3         | 0.44%   |
| Rome           | 3         | 0.44%   |
| Ribeirao Preto | 3         | 0.44%   |
| Milan          | 3         | 0.44%   |
| Mannheim       | 3         | 0.44%   |
| Madrid         | 3         | 0.44%   |
| London         | 3         | 0.44%   |
| Helsinki       | 3         | 0.44%   |
| Durham         | 3         | 0.44%   |
| Denver         | 3         | 0.44%   |
| Calgary        | 3         | 0.44%   |
| Budapest       | 3         | 0.44%   |
| Auckland       | 3         | 0.44%   |
| Winnipeg       | 2         | 0.29%   |
| Vitória       | 2         | 0.29%   |
| Vienna         | 2         | 0.29%   |
| Victoria       | 2         | 0.29%   |
| Vancouver      | 2         | 0.29%   |
| Turin          | 2         | 0.29%   |
| Tunis          | 2         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 163       | 195    | 19.11%  |
| WDC                            | 71        | 77     | 8.32%   |
| SanDisk                        | 70        | 86     | 8.21%   |
| Seagate                        | 61        | 68     | 7.15%   |
| SK hynix                       | 53        | 56     | 6.21%   |
| Toshiba                        | 51        | 58     | 5.98%   |
| Kingston                       | 49        | 58     | 5.74%   |
| Crucial                        | 29        | 29     | 3.4%    |
| Micron Technology              | 28        | 31     | 3.28%   |
| Apple                          | 25        | 28     | 2.93%   |
| Unknown                        | 24        | 26     | 2.81%   |
| HGST                           | 24        | 25     | 2.81%   |
| Intel                          | 23        | 24     | 2.7%    |
| Phison                         | 18        | 20     | 2.11%   |
| Hitachi                        | 10        | 12     | 1.17%   |
| A-DATA Technology              | 9         | 10     | 1.06%   |
| Silicon Motion                 | 8         | 8      | 0.94%   |
| PNY                            | 8         | 9      | 0.94%   |
| KIOXIA                         | 8         | 8      | 0.94%   |
| LITEON                         | 6         | 6      | 0.7%    |
| KingSpec                       | 6         | 7      | 0.7%    |
| Union Memory (Shenzhen)        | 5         | 7      | 0.59%   |
| Micron/Crucial Technology      | 5         | 6      | 0.59%   |
| LITEONIT                       | 5         | 6      | 0.59%   |
| China                          | 5         | 5      | 0.59%   |
| ADATA Technology               | 5         | 5      | 0.59%   |
| Team                           | 4         | 4      | 0.47%   |
| Solid State Storage Technology | 4         | 4      | 0.47%   |
| Intenso                        | 4         | 4      | 0.47%   |
| W800S                          | 3         | 5      | 0.35%   |
| MyDigitalSSD                   | 3         | 3      | 0.35%   |
| Fujitsu                        | 3         | 3      | 0.35%   |
| Unknown                        | 3         | 4      | 0.35%   |
| SSSTC                          | 2         | 2      | 0.23%   |
| SPCC                           | 2         | 2      | 0.23%   |
| ROG                            | 2         | 2      | 0.23%   |
| Netac                          | 2         | 2      | 0.23%   |
| MAXIO Technology (Hangzhou)    | 2         | 2      | 0.23%   |
| Lexar                          | 2         | 2      | 0.23%   |
| HS-SSD-C100                    | 2         | 3      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB       | 17        | 1.91%   |
| Kingston SA400S37240G 240GB SSD    | 14        | 1.57%   |
| SK hynix NVMe SSD Drive 512GB      | 13        | 1.46%   |
| SanDisk NVMe SSD Drive 1TB         | 12        | 1.35%   |
| Seagate ST1000LM035-1RK172 1TB     | 10        | 1.12%   |
| Samsung NVMe SSD Drive 1TB         | 10        | 1.12%   |
| SK hynix NVMe SSD Drive 1024GB     | 9         | 1.01%   |
| Samsung NVMe SSD Drive 500GB       | 9         | 1.01%   |
| Samsung NVMe SSD Drive 256GB       | 9         | 1.01%   |
| SanDisk NVMe SSD Drive 512GB       | 8         | 0.9%    |
| SanDisk NVMe SSD Drive 256GB       | 8         | 0.9%    |
| Samsung NVMe SSD Drive 2TB         | 8         | 0.9%    |
| Samsung NVMe SSD Drive 1024GB      | 8         | 0.9%    |
| HGST HTS721010A9E630 1TB           | 8         | 0.9%    |
| Toshiba MQ04ABF100 1TB             | 7         | 0.78%   |
| Samsung SSD 850 EVO 500GB          | 7         | 0.78%   |
| Micron NVMe SSD Drive 512GB        | 7         | 0.78%   |
| Kingston NVMe SSD Drive 512GB      | 7         | 0.78%   |
| WDC WD10SPZX-24Z10 1TB             | 6         | 0.67%   |
| Toshiba MQ01ABD100 1TB             | 6         | 0.67%   |
| Seagate ST1000LM049-2GH172 1TB     | 6         | 0.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 6         | 0.67%   |
| Kingston SA400S37120G 120GB SSD    | 6         | 0.67%   |
| SK hynix NVMe SSD Drive 256GB      | 5         | 0.56%   |
| SanDisk NVMe SSD Drive 500GB       | 5         | 0.56%   |
| SanDisk NVMe SSD Drive 1024GB      | 5         | 0.56%   |
| Samsung SSD 970 EVO Plus 1TB       | 5         | 0.56%   |
| Samsung NVMe SSD Drive 250GB       | 5         | 0.56%   |
| Kingston SA400S37480G 480GB SSD    | 5         | 0.56%   |
| Intel NVMe SSD Drive 512GB         | 5         | 0.56%   |
| Crucial CT240BX500SSD1 240GB       | 5         | 0.56%   |
| Crucial CT1000MX500SSD1 1TB        | 5         | 0.56%   |
| Unknown MMC Card  128GB            | 4         | 0.45%   |
| Toshiba MQ01ACF050 500GB           | 4         | 0.45%   |
| Seagate ST2000LM007-1R8174 2TB     | 4         | 0.45%   |
| Samsung SSD 860 QVO 1TB            | 4         | 0.45%   |
| Samsung SSD 860 EVO 500GB          | 4         | 0.45%   |
| Kingston OM8PCP3512F-AI1 512GB     | 4         | 0.45%   |
| HGST HTS725050A7E630 500GB         | 4         | 0.45%   |
| HGST HTS541010A9E680 1TB           | 4         | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 59        | 66     | 31.72%  |
| WDC                 | 43        | 48     | 23.12%  |
| Toshiba             | 34        | 38     | 18.28%  |
| HGST                | 24        | 25     | 12.9%   |
| Hitachi             | 10        | 12     | 5.38%   |
| Unknown             | 3         | 3      | 1.61%   |
| Samsung Electronics | 3         | 3      | 1.61%   |
| Fujitsu             | 3         | 3      | 1.61%   |
| Apple               | 2         | 2      | 1.08%   |
| USB3.0              | 1         | 1      | 0.54%   |
| SATAFIRM            | 1         | 1      | 0.54%   |
| Intenso             | 1         | 1      | 0.54%   |
| HGST HDN            | 1         | 1      | 0.54%   |
| Asm                 | 1         | 1      | 0.54%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 59        | 63     | 22.18%  |
| Kingston            | 34        | 35     | 12.78%  |
| SanDisk             | 28        | 32     | 10.53%  |
| Crucial             | 24        | 24     | 9.02%   |
| Apple               | 18        | 20     | 6.77%   |
| WDC                 | 11        | 12     | 4.14%   |
| PNY                 | 8         | 9      | 3.01%   |
| SK hynix            | 7         | 7      | 2.63%   |
| Toshiba             | 6         | 6      | 2.26%   |
| LITEON              | 6         | 6      | 2.26%   |
| KingSpec            | 6         | 7      | 2.26%   |
| Micron Technology   | 5         | 5      | 1.88%   |
| LITEONIT            | 5         | 6      | 1.88%   |
| China               | 5         | 5      | 1.88%   |
| A-DATA Technology   | 4         | 5      | 1.5%    |
| MyDigitalSSD        | 3         | 3      | 1.13%   |
| Intel               | 3         | 3      | 1.13%   |
| SPCC                | 2         | 2      | 0.75%   |
| Intenso             | 2         | 2      | 0.75%   |
| Apacer              | 2         | 4      | 0.75%   |
| W800S               | 1         | 1      | 0.38%   |
| TwinMOS             | 1         | 1      | 0.38%   |
| TrekStor            | 1         | 1      | 0.38%   |
| Transcend           | 1         | 1      | 0.38%   |
| Teutons             | 1         | 1      | 0.38%   |
| Ramaxel Technology  | 1         | 1      | 0.38%   |
| Radeon              | 1         | 1      | 0.38%   |
| PUSKILL             | 1         | 1      | 0.38%   |
| PNY USB             | 1         | 1      | 0.38%   |
| Phison              | 1         | 1      | 0.38%   |
| Patriot             | 1         | 1      | 0.38%   |
| OWC                 | 1         | 1      | 0.38%   |
| Netac               | 1         | 1      | 0.38%   |
| Lexar               | 1         | 1      | 0.38%   |
| Leven               | 1         | 1      | 0.38%   |
| KingFast            | 1         | 1      | 0.38%   |
| KingDian            | 1         | 1      | 0.38%   |
| KINGBANK            | 1         | 1      | 0.38%   |
| Inland              | 1         | 1      | 0.38%   |
| HS-SSD-C100         | 1         | 1      | 0.38%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 335       | 429    | 41.82%  |
| SSD     | 248       | 284    | 30.96%  |
| HDD     | 181       | 205    | 22.6%   |
| MMC     | 22        | 24     | 2.75%   |
| Unknown | 15        | 19     | 1.87%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 385       | 478    | 50%     |
| NVMe | 334       | 427    | 43.38%  |
| SAS  | 29        | 32     | 3.77%   |
| MMC  | 22        | 24     | 2.86%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 271       | 321    | 64.37%  |
| 0.51-1.0   | 132       | 146    | 31.35%  |
| 1.01-2.0   | 15        | 19     | 3.56%   |
| 3.01-4.0   | 2         | 2      | 0.48%   |
| 4.01-10.0  | 1         | 1      | 0.24%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 223       | 32.7%   |
| 251-500        | 211       | 30.94%  |
| 501-1000       | 136       | 19.94%  |
| 1001-2000      | 41        | 6.01%   |
| 51-100         | 19        | 2.79%   |
| 21-50          | 15        | 2.2%    |
| 2001-3000      | 12        | 1.76%   |
| 1-20           | 12        | 1.76%   |
| More than 3000 | 9         | 1.32%   |
| Unknown        | 4         | 0.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 238       | 33.95%  |
| 21-50          | 176       | 25.11%  |
| 101-250        | 102       | 14.55%  |
| 51-100         | 93        | 13.27%  |
| 251-500        | 53        | 7.56%   |
| 501-1000       | 26        | 3.71%   |
| 1001-2000      | 7         | 1%      |
| Unknown        | 4         | 0.57%   |
| More than 3000 | 2         | 0.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| HGST HTS725050A7E630 500GB                          | 2         | 3      | 12.5%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD            | 1         | 1      | 6.25%   |
| Toshiba MQ01ACF050 500GB                            | 1         | 1      | 6.25%   |
| Team TM8FP4004T 4TB                                 | 1         | 1      | 6.25%   |
| SK hynix PC711 HFS001TDE9X073N 1024GB               | 1         | 1      | 6.25%   |
| Seagate ST9320325AS 320GB                           | 1         | 1      | 6.25%   |
| Seagate ST500LM030-2E717D 500GB                     | 1         | 1      | 6.25%   |
| Seagate ST1000LX015-1U7172 1TB                      | 1         | 1      | 6.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 6.25%   |
| Samsung Electronics SSD 850 EVO 500GB               | 1         | 1      | 6.25%   |
| Micron Technology MTFDDAK256MAY-1AH1ZABHA 256GB SSD | 1         | 1      | 6.25%   |
| Lexar 1TB SSD                                       | 1         | 1      | 6.25%   |
| Leven JAJS600M256C 256GB                            | 1         | 1      | 6.25%   |
| Hitachi HTS545050A7E380 500GB                       | 1         | 3      | 6.25%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 25%     |
| HGST                | 3         | 4      | 18.75%  |
| Toshiba             | 2         | 2      | 12.5%   |
| Team                | 1         | 1      | 6.25%   |
| SK hynix            | 1         | 1      | 6.25%   |
| Samsung Electronics | 1         | 1      | 6.25%   |
| Micron Technology   | 1         | 1      | 6.25%   |
| Lexar               | 1         | 1      | 6.25%   |
| Leven               | 1         | 1      | 6.25%   |
| Hitachi             | 1         | 3      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 44.44%  |
| HGST    | 3         | 4      | 33.33%  |
| Toshiba | 1         | 1      | 11.11%  |
| Hitachi | 1         | 3      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 12     | 56.25%  |
| SSD  | 4         | 4      | 25%     |
| NVMe | 3         | 3      | 18.75%  |

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
| Detected | 519       | 718    | 72.79%  |
| Works    | 177       | 223    | 24.82%  |
| Malfunc  | 16        | 19     | 2.24%   |
| Failed   | 1         | 1      | 0.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 409       | 46.48%  |
| Samsung Electronics            | 120       | 13.64%  |
| AMD                            | 96        | 10.91%  |
| SanDisk                        | 57        | 6.48%   |
| SK hynix                       | 46        | 5.23%   |
| Micron Technology              | 22        | 2.5%    |
| Phison Electronics             | 19        | 2.16%   |
| Kingston Technology Company    | 15        | 1.7%    |
| Nvidia                         | 14        | 1.59%   |
| Toshiba America Info Systems   | 13        | 1.48%   |
| Silicon Motion                 | 10        | 1.14%   |
| ADATA Technology               | 10        | 1.14%   |
| Micron/Crucial Technology      | 9         | 1.02%   |
| KIOXIA                         | 7         | 0.8%    |
| Union Memory (Shenzhen)        | 6         | 0.68%   |
| Solid State Storage Technology | 6         | 0.68%   |
| Apple                          | 5         | 0.57%   |
| Shenzhen Longsys Electronics   | 4         | 0.45%   |
| Marvell Technology Group       | 4         | 0.45%   |
| Realtek Semiconductor          | 2         | 0.23%   |
| MAXIO Technology (Hangzhou)    | 2         | 0.23%   |
| Yangtze Memory Technologies    | 1         | 0.11%   |
| Unknown                        | 1         | 0.11%   |
| Seagate Technology             | 1         | 0.11%   |
| Lite-On Technology             | 1         | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 91        | 9.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 53        | 5.78%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 46        | 5.02%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 41        | 4.47%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 37        | 4.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 29        | 3.16%   |
| SK hynix Gold P31 SSD                                                          | 28        | 3.05%   |
| Intel Volume Management Device NVMe RAID Controller                            | 28        | 3.05%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 26        | 2.84%   |
| Samsung NVMe SSD Controller 980                                                | 25        | 2.73%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 23        | 2.51%   |
| Micron Non-Volatile memory controller                                          | 22        | 2.4%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 20        | 2.18%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 19        | 2.07%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 19        | 2.07%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 18        | 1.96%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 17        | 1.85%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 17        | 1.85%   |
| SanDisk Non-Volatile memory controller                                         | 14        | 1.53%   |
| SK hynix Non-Volatile memory controller                                        | 11        | 1.2%    |
| Intel SSD 660P Series                                                          | 11        | 1.2%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 10        | 1.09%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 10        | 1.09%   |
| Samsung Electronics SATA controller                                            | 10        | 1.09%   |
| Intel Tiger Lake-LP SATA Controller                                            | 10        | 1.09%   |
| Intel Comet Lake SATA AHCI Controller                                          | 10        | 1.09%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 10        | 1.09%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 9         | 0.98%   |
| Phison E12 NVMe Controller                                                     | 9         | 0.98%   |
| Kingston Company Company Non-Volatile memory controller                        | 9         | 0.98%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 9         | 0.98%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 9         | 0.98%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 9         | 0.98%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 8         | 0.87%   |
| Nvidia MCP79 AHCI Controller                                                   | 8         | 0.87%   |
| ADATA Non-Volatile memory controller                                           | 8         | 0.87%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 7         | 0.76%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 7         | 0.76%   |
| Solid State Storage Non-Volatile memory controller                             | 6         | 0.65%   |
| Phison PS5013 E13 NVMe Controller                                              | 6         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 449       | 51.67%  |
| NVMe | 333       | 38.32%  |
| RAID | 67        | 7.71%   |
| IDE  | 20        | 2.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 515       | 76.41%  |
| AMD    | 159       | 23.59%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 21        | 3.11%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 18        | 2.67%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 13        | 1.93%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 12        | 1.78%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 12        | 1.78%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 11        | 1.63%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 10        | 1.48%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 10        | 1.48%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 10        | 1.48%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 9         | 1.33%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 8         | 1.19%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 8         | 1.19%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 8         | 1.19%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 8         | 1.19%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 7         | 1.04%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 7         | 1.04%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 7         | 1.04%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 6         | 0.89%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 0.89%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 6         | 0.89%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 6         | 0.89%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 6         | 0.89%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 6         | 0.89%   |
| Intel 12th Gen Core i7-12700H                 | 6         | 0.89%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 6         | 0.89%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 0.74%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 0.74%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 5         | 0.74%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 0.74%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 5         | 0.74%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 0.74%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 5         | 0.74%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics    | 5         | 0.74%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 5         | 0.74%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 5         | 0.74%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 4         | 0.59%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 4         | 0.59%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 4         | 0.59%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 0.59%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 4         | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 175       | 25.96%  |
| Intel Core i5           | 151       | 22.4%   |
| Other                   | 89        | 13.2%   |
| AMD Ryzen 7             | 50        | 7.42%   |
| AMD Ryzen 5             | 46        | 6.82%   |
| Intel Core i3           | 40        | 5.93%   |
| Intel Core 2 Duo        | 23        | 3.41%   |
| Intel Celeron           | 18        | 2.67%   |
| AMD Ryzen 9             | 12        | 1.78%   |
| Intel Pentium           | 9         | 1.34%   |
| AMD Ryzen 7 PRO         | 8         | 1.19%   |
| AMD Ryzen 3             | 8         | 1.19%   |
| AMD A6                  | 7         | 1.04%   |
| AMD A10                 | 7         | 1.04%   |
| AMD A8                  | 6         | 0.89%   |
| Intel Core i9           | 5         | 0.74%   |
| Intel Pentium Dual-Core | 3         | 0.45%   |
| AMD Ryzen 5 PRO         | 2         | 0.3%    |
| AMD Athlon              | 2         | 0.3%    |
| Intel Xeon              | 1         | 0.15%   |
| Intel Pentium Gold      | 1         | 0.15%   |
| Intel Genuine           | 1         | 0.15%   |
| Intel Core m3           | 1         | 0.15%   |
| Intel Atom              | 1         | 0.15%   |
| AMD Turion II           | 1         | 0.15%   |
| AMD Turion 64 X2 Mobile | 1         | 0.15%   |
| AMD Phenom II           | 1         | 0.15%   |
| AMD E2                  | 1         | 0.15%   |
| AMD E                   | 1         | 0.15%   |
| AMD Athlon X2           | 1         | 0.15%   |
| AMD A4                  | 1         | 0.15%   |
| AMD A12                 | 1         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 256       | 37.98%  |
| 4      | 228       | 33.83%  |
| 8      | 101       | 14.99%  |
| 6      | 69        | 10.24%  |
| 14     | 12        | 1.78%   |
| 12     | 5         | 0.74%   |
| 1      | 2         | 0.3%    |
| 10     | 1         | 0.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 674       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 586       | 86.94%  |
| 1      | 88        | 13.06%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 674       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 495       | 72.69%  |
| 0x806d1    | 15        | 2.2%    |
| 0x0a50000c | 15        | 2.2%    |
| 0x806c1    | 14        | 2.06%   |
| 0x806ec    | 12        | 1.76%   |
| 0xa0652    | 10        | 1.47%   |
| 0x806ea    | 10        | 1.47%   |
| 0x306a9    | 10        | 1.47%   |
| 0x906a3    | 7         | 1.03%   |
| 0x406e3    | 7         | 1.03%   |
| 0x0a404101 | 7         | 1.03%   |
| 0x906ea    | 6         | 0.88%   |
| 0x706e5    | 5         | 0.73%   |
| 0x40651    | 5         | 0.73%   |
| 0x306c3    | 5         | 0.73%   |
| 0x08608103 | 5         | 0.73%   |
| 0x906e9    | 4         | 0.59%   |
| 0x806e9    | 4         | 0.59%   |
| 0x506e3    | 4         | 0.59%   |
| 0x08600106 | 4         | 0.59%   |
| 0x08600104 | 4         | 0.59%   |
| 0x08108109 | 4         | 0.59%   |
| 0x306d4    | 3         | 0.44%   |
| 0x206a7    | 3         | 0.44%   |
| 0x1067a    | 3         | 0.44%   |
| 0x08600103 | 3         | 0.44%   |
| 0xa0660    | 2         | 0.29%   |
| 0x806eb    | 2         | 0.29%   |
| 0x806c2    | 2         | 0.29%   |
| 0x706a8    | 2         | 0.29%   |
| 0x0810100b | 2         | 0.29%   |
| 0x906c0    | 1         | 0.15%   |
| 0x906a4    | 1         | 0.15%   |
| 0x30678    | 1         | 0.15%   |
| 0x08108102 | 1         | 0.15%   |
| 0x08101007 | 1         | 0.15%   |
| 0x07030105 | 1         | 0.15%   |
| 0x06006705 | 1         | 0.15%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 125       | 18.49%  |
| Haswell          | 63        | 9.32%   |
| Unknown          | 60        | 8.88%   |
| IvyBridge        | 43        | 6.36%   |
| Zen 3            | 40        | 5.92%   |
| TigerLake        | 40        | 5.92%   |
| SandyBridge      | 39        | 5.77%   |
| Skylake          | 33        | 4.88%   |
| IceLake          | 29        | 4.29%   |
| CometLake        | 29        | 4.29%   |
| Broadwell        | 26        | 3.85%   |
| Zen+             | 25        | 3.7%    |
| Zen 2            | 25        | 3.7%    |
| Penryn           | 25        | 3.7%    |
| Westmere         | 13        | 1.92%   |
| Silvermont       | 8         | 1.18%   |
| Excavator        | 8         | 1.18%   |
| Puma             | 7         | 1.04%   |
| Alderlake Hybrid | 7         | 1.04%   |
| Goldmont plus    | 6         | 0.89%   |
| Zen              | 5         | 0.74%   |
| Piledriver       | 5         | 0.74%   |
| K10 Llano        | 4         | 0.59%   |
| Steamroller      | 2         | 0.3%    |
| K8 Hammer        | 2         | 0.3%    |
| K10              | 2         | 0.3%    |
| Tremont          | 1         | 0.15%   |
| Nehalem          | 1         | 0.15%   |
| Goldmont         | 1         | 0.15%   |
| Core             | 1         | 0.15%   |
| Bobcat           | 1         | 0.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 465       | 51.78%  |
| Nvidia | 252       | 28.06%  |
| AMD    | 181       | 20.16%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 39        | 4.27%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 37        | 4.05%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 35        | 3.83%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 34        | 3.72%   |
| AMD Cezanne                                                                           | 32        | 3.5%    |
| AMD Renoir                                                                            | 25        | 2.74%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 25        | 2.74%   |
| Intel UHD Graphics 620                                                                | 24        | 2.63%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 24        | 2.63%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 22        | 2.41%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 22        | 2.41%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 22        | 2.41%   |
| AMD Lucienne                                                                          | 21        | 2.3%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 20        | 2.19%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 19        | 2.08%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 19        | 2.08%   |
| Intel HD Graphics 620                                                                 | 19        | 2.08%   |
| Intel HD Graphics 5500                                                                | 19        | 2.08%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 18        | 1.97%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 17        | 1.86%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 15        | 1.64%   |
| Intel HD Graphics 630                                                                 | 13        | 1.42%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 12        | 1.31%   |
| AMD Rembrandt [Radeon 680M]                                                           | 12        | 1.31%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                       | 11        | 1.2%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 10        | 1.09%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 10        | 1.09%   |
| Intel Core Processor Integrated Graphics Controller                                   | 10        | 1.09%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 9         | 0.98%   |
| Intel HD Graphics 530                                                                 | 9         | 0.98%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 9         | 0.98%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 8         | 0.88%   |
| Nvidia TU117M                                                                         | 8         | 0.88%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 7         | 0.77%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 7         | 0.77%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                   | 7         | 0.77%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 6         | 0.66%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 6         | 0.66%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 6         | 0.66%   |
| Nvidia C79 [GeForce 9400M]                                                            | 5         | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 291       | 42.98%  |
| Intel + Nvidia | 158       | 23.34%  |
| 1 x AMD        | 104       | 15.36%  |
| AMD + Nvidia   | 47        | 6.94%   |
| 1 x Nvidia     | 46        | 6.79%   |
| Intel + AMD    | 17        | 2.51%   |
| 2 x AMD        | 13        | 1.92%   |
| 2 x Nvidia     | 1         | 0.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 465       | 68.58%  |
| Proprietary | 201       | 29.65%  |
| Unknown     | 12        | 1.77%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 584       | 85.76%  |
| 3.01-4.0   | 22        | 3.23%   |
| 0.01-0.5   | 21        | 3.08%   |
| 1.01-2.0   | 18        | 2.64%   |
| 7.01-8.0   | 16        | 2.35%   |
| 5.01-6.0   | 10        | 1.47%   |
| 0.51-1.0   | 5         | 0.73%   |
| 2.01-3.0   | 3         | 0.44%   |
| 8.01-16.0  | 2         | 0.29%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 162       | 20.43%  |
| BOE                     | 119       | 15.01%  |
| Chimei Innolux          | 110       | 13.87%  |
| LG Display              | 109       | 13.75%  |
| Samsung Electronics     | 60        | 7.57%   |
| Apple                   | 39        | 4.92%   |
| Dell                    | 30        | 3.78%   |
| Sharp                   | 24        | 3.03%   |
| Goldstar                | 24        | 3.03%   |
| PANDA                   | 19        | 2.4%    |
| Lenovo                  | 9         | 1.13%   |
| InfoVision              | 8         | 1.01%   |
| CSO                     | 8         | 1.01%   |
| Acer                    | 8         | 1.01%   |
| Hewlett-Packard         | 6         | 0.76%   |
| Chi Mei Optoelectronics | 6         | 0.76%   |
| AOC                     | 6         | 0.76%   |
| ASUSTek Computer        | 5         | 0.63%   |
| TMX                     | 3         | 0.38%   |
| Philips                 | 3         | 0.38%   |
| Iiyama                  | 3         | 0.38%   |
| Vizio                   | 2         | 0.25%   |
| ViewSonic               | 2         | 0.25%   |
| Vestel Elektronik       | 2         | 0.25%   |
| TCL                     | 2         | 0.25%   |
| JDI                     | 2         | 0.25%   |
| BenQ                    | 2         | 0.25%   |
| Unknown                 | 1         | 0.13%   |
| Toshiba                 | 1         | 0.13%   |
| STA                     | 1         | 0.13%   |
| Sony                    | 1         | 0.13%   |
| SGT                     | 1         | 0.13%   |
| Sceptre Tech            | 1         | 0.13%   |
| SAC                     | 1         | 0.13%   |
| Panasonic               | 1         | 0.13%   |
| ONN                     | 1         | 0.13%   |
| MSI                     | 1         | 0.13%   |
| LG Electronics          | 1         | 0.13%   |
| KDC                     | 1         | 0.13%   |
| JXC                     | 1         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 9         | 1.12%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 7         | 0.87%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 7         | 0.87%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 6         | 0.75%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 6         | 0.75%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 5         | 0.62%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 5         | 0.62%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 5         | 0.62%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 5         | 0.62%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 5         | 0.62%   |
| BOE LCD Monitor BOE08DF 1920x1080 344x194mm 15.5-inch                | 5         | 0.62%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch       | 5         | 0.62%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                 | 5         | 0.62%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch | 4         | 0.5%    |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 4         | 0.5%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 4         | 0.5%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 4         | 0.5%    |
| Chimei Innolux LCD Monitor CMN1408 1920x1080 309x173mm 13.9-inch     | 4         | 0.5%    |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch       | 4         | 0.5%    |
| AU Optronics LCD Monitor AUO82ED 1920x1080 344x193mm 15.5-inch       | 4         | 0.5%    |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch       | 4         | 0.5%    |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch        | 4         | 0.5%    |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch        | 4         | 0.5%    |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch              | 3         | 0.37%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch | 3         | 0.37%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch              | 3         | 0.37%   |
| PANDA LCD Monitor NCP002B 1920x1080 309x174mm 14.0-inch              | 3         | 0.37%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch          | 3         | 0.37%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 3         | 0.37%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 3         | 0.37%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch         | 3         | 0.37%   |
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                    | 3         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15E5 1920x1080 344x193mm 15.5-inch     | 3         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch     | 3         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch      | 3         | 0.37%   |
| Chimei Innolux LCD Monitor CMN1540 2560x1440 344x193mm 15.5-inch     | 3         | 0.37%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch     | 3         | 0.37%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 3         | 0.37%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch     | 3         | 0.37%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                | 3         | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 355       | 47.27%  |
| 1366x768 (WXGA)    | 174       | 23.17%  |
| 1600x900 (HD+)     | 33        | 4.39%   |
| 3840x2160 (4K)     | 31        | 4.13%   |
| 2560x1440 (QHD)    | 29        | 3.86%   |
| 1920x1200 (WUXGA)  | 24        | 3.2%    |
| 2560x1600          | 22        | 2.93%   |
| 1440x900 (WXGA+)   | 15        | 2%      |
| 1280x800 (WXGA)    | 13        | 1.73%   |
| 2880x1800          | 11        | 1.46%   |
| 3440x1440          | 8         | 1.07%   |
| 2560x1080          | 5         | 0.67%   |
| 3840x2400          | 4         | 0.53%   |
| 2256x1504          | 3         | 0.4%    |
| 2160x1440          | 3         | 0.4%    |
| 3456x2160          | 2         | 0.27%   |
| 3200x2000          | 2         | 0.27%   |
| 3000x2000          | 2         | 0.27%   |
| 1920x540           | 2         | 0.27%   |
| 1360x768           | 2         | 0.27%   |
| 1280x1024 (SXGA)   | 2         | 0.27%   |
| 3840x1200          | 1         | 0.13%   |
| 3840x1100          | 1         | 0.13%   |
| 3840x1080          | 1         | 0.13%   |
| 3200x1800 (QHD+)   | 1         | 0.13%   |
| 1920x1280          | 1         | 0.13%   |
| 1680x1050 (WSXGA+) | 1         | 0.13%   |
| 1280x720 (HD)      | 1         | 0.13%   |
| 1280x1080          | 1         | 0.13%   |
| Unknown            | 1         | 0.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 319       | 40.23%  |
| 13      | 144       | 18.16%  |
| 14      | 89        | 11.22%  |
| 17      | 56        | 7.06%   |
| 27      | 26        | 3.28%   |
| 24      | 25        | 3.15%   |
| 16      | 18        | 2.27%   |
| 12      | 18        | 2.27%   |
| 23      | 17        | 2.14%   |
| 31      | 12        | 1.51%   |
| 21      | 12        | 1.51%   |
| 34      | 11        | 1.39%   |
| 11      | 8         | 1.01%   |
| 32      | 6         | 0.76%   |
| 18      | 4         | 0.5%    |
| 84      | 3         | 0.38%   |
| 20      | 3         | 0.38%   |
| 19      | 3         | 0.38%   |
| Unknown | 3         | 0.38%   |
| 54      | 2         | 0.25%   |
| 49      | 2         | 0.25%   |
| 35      | 2         | 0.25%   |
| 28      | 2         | 0.25%   |
| 22      | 2         | 0.25%   |
| 72      | 1         | 0.13%   |
| 48      | 1         | 0.13%   |
| 43      | 1         | 0.13%   |
| 40      | 1         | 0.13%   |
| 37      | 1         | 0.13%   |
| 29      | 1         | 0.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 491       | 62.23%  |
| 201-300     | 98        | 12.42%  |
| 351-400     | 63        | 7.98%   |
| 501-600     | 61        | 7.73%   |
| 401-500     | 22        | 2.79%   |
| 601-700     | 20        | 2.53%   |
| 701-800     | 17        | 2.15%   |
| 1001-1500   | 6         | 0.76%   |
| 801-900     | 4         | 0.51%   |
| 1501-2000   | 4         | 0.51%   |
| Unknown     | 3         | 0.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 573       | 81.97%  |
| 16/10   | 96        | 13.73%  |
| 21/9    | 14        | 2%      |
| 3/2     | 10        | 1.43%   |
| 5/4     | 2         | 0.29%   |
| 32/9    | 1         | 0.14%   |
| 3.40    | 1         | 0.14%   |
| 3.20    | 1         | 0.14%   |
| Unknown | 1         | 0.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 320       | 40.4%   |
| 81-90          | 181       | 22.85%  |
| 121-130        | 55        | 6.94%   |
| 71-80          | 51        | 6.44%   |
| 201-250        | 41        | 5.18%   |
| 351-500        | 32        | 4.04%   |
| 301-350        | 26        | 3.28%   |
| 61-70          | 17        | 2.15%   |
| 111-120        | 16        | 2.02%   |
| 151-200        | 12        | 1.52%   |
| 251-300        | 11        | 1.39%   |
| 51-60          | 9         | 1.14%   |
| More than 1000 | 8         | 1.01%   |
| 141-150        | 4         | 0.51%   |
| 501-1000       | 4         | 0.51%   |
| Unknown        | 3         | 0.38%   |
| 131-140        | 1         | 0.13%   |
| 91-100         | 1         | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 363       | 46.48%  |
| 101-120       | 205       | 26.25%  |
| 51-100        | 98        | 12.55%  |
| 161-240       | 74        | 9.48%   |
| More than 240 | 31        | 3.97%   |
| 1-50          | 7         | 0.9%    |
| Unknown       | 3         | 0.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 530       | 77.71%  |
| 2     | 118       | 17.3%   |
| 3     | 17        | 2.49%   |
| 0     | 17        | 2.49%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 379       | 34.8%   |
| Intel                                 | 342       | 31.4%   |
| Qualcomm Atheros                      | 146       | 13.41%  |
| Broadcom                              | 67        | 6.15%   |
| MediaTek                              | 36        | 3.31%   |
| Broadcom Limited                      | 28        | 2.57%   |
| TP-Link                               | 10        | 0.92%   |
| Samsung Electronics                   | 9         | 0.83%   |
| Nvidia                                | 8         | 0.73%   |
| ASIX Electronics                      | 8         | 0.73%   |
| Marvell Technology Group              | 6         | 0.55%   |
| Dell                                  | 6         | 0.55%   |
| Ralink                                | 5         | 0.46%   |
| DisplayLink                           | 5         | 0.46%   |
| NetGear                               | 3         | 0.28%   |
| Hewlett-Packard                       | 3         | 0.28%   |
| Xiaomi                                | 2         | 0.18%   |
| Sierra Wireless                       | 2         | 0.18%   |
| Ralink Technology                     | 2         | 0.18%   |
| Qualcomm                              | 2         | 0.18%   |
| OPPO Electronics                      | 2         | 0.18%   |
| OnePlus Technology (Shenzhen)         | 2         | 0.18%   |
| JMicron Technology                    | 2         | 0.18%   |
| Ericsson Business Mobile Networks     | 2         | 0.18%   |
| ASUSTek Computer                      | 2         | 0.18%   |
| Apple                                 | 2         | 0.18%   |
| U-Blox                                | 1         | 0.09%   |
| Qualcomm Atheros Communications       | 1         | 0.09%   |
| Motorola PCS                          | 1         | 0.09%   |
| Lenovo                                | 1         | 0.09%   |
| Huawei Technologies                   | 1         | 0.09%   |
| FIBOCOM                               | 1         | 0.09%   |
| Arduino SA                            | 1         | 0.09%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 251       | 19.55%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 44        | 3.43%   |
| Intel Wi-Fi 6 AX200                                               | 42        | 3.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 33        | 2.57%   |
| Intel Wireless 8265 / 8275                                        | 30        | 2.34%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 28        | 2.18%   |
| Intel Wi-Fi 6 AX201                                               | 28        | 2.18%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 24        | 1.87%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 24        | 1.87%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 23        | 1.79%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 23        | 1.79%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 23        | 1.79%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 22        | 1.71%   |
| Intel Wireless 7265                                               | 21        | 1.64%   |
| Intel Wireless 7260                                               | 21        | 1.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 21        | 1.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 18        | 1.4%    |
| Intel Wireless 8260                                               | 17        | 1.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 16        | 1.25%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 16        | 1.25%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 14        | 1.09%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 14        | 1.09%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 14        | 1.09%   |
| Broadcom BCM43142 802.11b/g/n                                     | 12        | 0.93%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 11        | 0.86%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 11        | 0.86%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 11        | 0.86%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 11        | 0.86%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 9         | 0.7%    |
| Intel Wireless-AC 9260                                            | 9         | 0.7%    |
| Intel Ethernet Connection I219-LM                                 | 9         | 0.7%    |
| Intel Ethernet Connection I217-LM                                 | 9         | 0.7%    |
| Broadcom BCM4331 802.11a/b/g/n                                    | 9         | 0.7%    |
| Realtek RTL8125 2.5GbE Controller                                 | 8         | 0.62%   |
| Realtek Realtek Network controller                                | 8         | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 8         | 0.62%   |
| Intel Ethernet Connection (4) I219-LM                             | 8         | 0.62%   |
| Intel Centrino Advanced-N 6235                                    | 8         | 0.62%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 8         | 0.62%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 8         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 331       | 46.42%  |
| Qualcomm Atheros                      | 127       | 17.81%  |
| Realtek Semiconductor                 | 102       | 14.31%  |
| Broadcom                              | 57        | 7.99%   |
| MediaTek                              | 35        | 4.91%   |
| Broadcom Limited                      | 26        | 3.65%   |
| TP-Link                               | 9         | 1.26%   |
| Dell                                  | 6         | 0.84%   |
| Ralink                                | 5         | 0.7%    |
| NetGear                               | 3         | 0.42%   |
| Sierra Wireless                       | 2         | 0.28%   |
| Ralink Technology                     | 2         | 0.28%   |
| Qualcomm                              | 2         | 0.28%   |
| Qualcomm Atheros Communications       | 1         | 0.14%   |
| Hewlett-Packard                       | 1         | 0.14%   |
| FIBOCOM                               | 1         | 0.14%   |
| ASUSTek Computer                      | 1         | 0.14%   |
| Arduino SA                            | 1         | 0.14%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 42        | 5.83%   |
| Intel Wireless 8265 / 8275                                     | 30        | 4.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 28        | 3.89%   |
| Intel Wi-Fi 6 AX201                                            | 28        | 3.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 24        | 3.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 24        | 3.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 23        | 3.19%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 23        | 3.19%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 23        | 3.19%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 22        | 3.06%   |
| Intel Wireless 7265                                            | 21        | 2.92%   |
| Intel Wireless 7260                                            | 21        | 2.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 18        | 2.5%    |
| Intel Wireless 8260                                            | 17        | 2.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 16        | 2.22%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 16        | 2.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 14        | 1.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 14        | 1.94%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 14        | 1.94%   |
| Broadcom BCM43142 802.11b/g/n                                  | 12        | 1.67%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 11        | 1.53%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 11        | 1.53%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 11        | 1.53%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 11        | 1.53%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 9         | 1.25%   |
| Intel Wireless-AC 9260                                         | 9         | 1.25%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 9         | 1.25%   |
| Realtek Realtek Network controller                             | 8         | 1.11%   |
| Intel Centrino Advanced-N 6235                                 | 8         | 1.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 8         | 1.11%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 8         | 1.11%   |
| MediaTek WLAN controller                                       | 7         | 0.97%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 6         | 0.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 6         | 0.83%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 6         | 0.83%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 6         | 0.83%   |
| Intel Centrino Ultimate-N 6300                                 | 6         | 0.83%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 6         | 0.83%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 5         | 0.69%   |
| Realtek 802.11n WLAN Adapter                                   | 4         | 0.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 337       | 61.38%  |
| Intel                         | 100       | 18.21%  |
| Qualcomm Atheros              | 33        | 6.01%   |
| Broadcom                      | 25        | 4.55%   |
| Samsung Electronics           | 9         | 1.64%   |
| Nvidia                        | 8         | 1.46%   |
| ASIX Electronics              | 8         | 1.46%   |
| Marvell Technology Group      | 6         | 1.09%   |
| DisplayLink                   | 5         | 0.91%   |
| Xiaomi                        | 2         | 0.36%   |
| OPPO Electronics              | 2         | 0.36%   |
| OnePlus Technology (Shenzhen) | 2         | 0.36%   |
| JMicron Technology            | 2         | 0.36%   |
| Broadcom Limited              | 2         | 0.36%   |
| Apple                         | 2         | 0.36%   |
| TP-Link                       | 1         | 0.18%   |
| Motorola PCS                  | 1         | 0.18%   |
| Lenovo                        | 1         | 0.18%   |
| Huawei Technologies           | 1         | 0.18%   |
| Hewlett-Packard               | 1         | 0.18%   |
| ASUSTek Computer              | 1         | 0.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 251       | 45.06%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 44        | 7.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 33        | 5.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 21        | 3.77%   |
| Intel Ethernet Connection I219-LM                                 | 9         | 1.62%   |
| Intel Ethernet Connection I217-LM                                 | 9         | 1.62%   |
| Realtek RTL8125 2.5GbE Controller                                 | 8         | 1.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 8         | 1.44%   |
| Intel Ethernet Connection (4) I219-LM                             | 8         | 1.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 7         | 1.26%   |
| Nvidia MCP79 Ethernet                                             | 7         | 1.26%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 7         | 1.26%   |
| ASIX AX88179 Gigabit Ethernet                                     | 7         | 1.26%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 6         | 1.08%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 1.08%   |
| Intel Ethernet Connection (3) I218-LM                             | 6         | 1.08%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 0.9%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 4         | 0.72%   |
| Intel Ethernet Controller I225-V                                  | 4         | 0.72%   |
| Intel Ethernet Connection (6) I219-LM                             | 4         | 0.72%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 4         | 0.72%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 4         | 0.72%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.54%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.54%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.54%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.54%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 0.54%   |
| Intel Ethernet Connection (13) I219-V                             | 3         | 0.54%   |
| DisplayLink Dell Universal Dock D6000                             | 3         | 0.54%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 3         | 0.54%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 0.54%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.36%   |
| Realtek Realtek Ethernet controller                               | 2         | 0.36%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 0.36%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.36%   |
| OPPO RMX2117                                                      | 2         | 0.36%   |
| OnePlus (Shenzhen) OnePlus                                        | 2         | 0.36%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.36%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 674       | 56.03%  |
| Ethernet | 522       | 43.39%  |
| Modem    | 5         | 0.42%   |
| Unknown  | 2         | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 560       | 79.43%  |
| Ethernet | 145       | 20.57%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 481       | 71.36%  |
| 1     | 186       | 27.6%   |
| 0     | 4         | 0.59%   |
| 3     | 3         | 0.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 482       | 70.99%  |
| Yes  | 197       | 29.01%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 293       | 50%     |
| Qualcomm Atheros Communications | 57        | 9.73%   |
| Realtek Semiconductor           | 48        | 8.19%   |
| Apple                           | 42        | 7.17%   |
| IMC Networks                    | 41        | 7%      |
| Lite-On Technology              | 27        | 4.61%   |
| Foxconn / Hon Hai               | 22        | 3.75%   |
| Broadcom                        | 22        | 3.75%   |
| Dell                            | 7         | 1.19%   |
| Toshiba                         | 5         | 0.85%   |
| Realtek                         | 5         | 0.85%   |
| Hewlett-Packard                 | 3         | 0.51%   |
| Cambridge Silicon Radio         | 3         | 0.51%   |
| Ralink                          | 2         | 0.34%   |
| Opticis                         | 2         | 0.34%   |
| Foxconn International           | 2         | 0.34%   |
| USI                             | 1         | 0.17%   |
| Taiyo Yuden                     | 1         | 0.17%   |
| Ralink Technology               | 1         | 0.17%   |
| Fujitsu                         | 1         | 0.17%   |
| ASUSTek Computer                | 1         | 0.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 91        | 15.53%  |
| Intel AX201 Bluetooth                               | 74        | 12.63%  |
| Intel AX200 Bluetooth                               | 41        | 7%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 39        | 6.66%   |
| Realtek Bluetooth Radio                             | 36        | 6.14%   |
| Qualcomm Atheros  Bluetooth Device                  | 31        | 5.29%   |
| Apple Bluetooth USB Host Controller                 | 19        | 3.24%   |
| Apple Bluetooth Host Controller                     | 19        | 3.24%   |
| IMC Networks Wireless_Device                        | 18        | 3.07%   |
| Intel Bluetooth Device                              | 13        | 2.22%   |
| Intel AX210 Bluetooth                               | 11        | 1.88%   |
| IMC Networks Bluetooth Device                       | 11        | 1.88%   |
| Realtek  Bluetooth 4.2 Adapter                      | 10        | 1.71%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 10        | 1.71%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 9         | 1.54%   |
| Foxconn / Hon Hai Wireless_Device                   | 9         | 1.54%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 8         | 1.37%   |
| Foxconn / Hon Hai Bluetooth Device                  | 8         | 1.37%   |
| Lite-On Wireless_Device                             | 6         | 1.02%   |
| Realtek Bluetooth Radio                             | 5         | 0.85%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 5         | 0.85%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 0.85%   |
| Lite-On Bluetooth Device                            | 5         | 0.85%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 5         | 0.85%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 4         | 0.68%   |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 0.68%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 4         | 0.68%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 3         | 0.51%   |
| Lite-On Bluetooth Radio                             | 3         | 0.51%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 0.51%   |
| IMC Networks Bluetooth USB Host Controller          | 3         | 0.51%   |
| IMC Networks Bluetooth Radio                        | 3         | 0.51%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 0.51%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 3         | 0.51%   |
| Broadcom BCM20702A0                                 | 3         | 0.51%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 0.51%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 0.51%   |
| Toshiba BCM43142A0                                  | 2         | 0.34%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 0.34%   |
| Ralink RT3290 Bluetooth                             | 2         | 0.34%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 501       | 56.36%  |
| AMD                                  | 168       | 18.9%   |
| Nvidia                               | 156       | 17.55%  |
| GN Netcom                            | 6         | 0.67%   |
| C-Media Electronics                  | 6         | 0.67%   |
| Texas Instruments                    | 4         | 0.45%   |
| Sony                                 | 4         | 0.45%   |
| Kingston Technology                  | 4         | 0.45%   |
| Apple                                | 4         | 0.45%   |
| SteelSeries ApS                      | 3         | 0.34%   |
| Realtek Semiconductor                | 3         | 0.34%   |
| Logitech                             | 3         | 0.34%   |
| Lenovo                               | 3         | 0.34%   |
| Hewlett-Packard                      | 3         | 0.34%   |
| Sennheiser Communications            | 2         | 0.22%   |
| Plantronics                          | 2         | 0.22%   |
| Focusrite-Novation                   | 2         | 0.22%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.11%   |
| TerraTec Electronic                  | 1         | 0.11%   |
| Samson Technologies                  | 1         | 0.11%   |
| Razer USA                            | 1         | 0.11%   |
| Pioneer DJ                           | 1         | 0.11%   |
| No brand                             | 1         | 0.11%   |
| Midiplus                             | 1         | 0.11%   |
| JMTek                                | 1         | 0.11%   |
| iConnectivity                        | 1         | 0.11%   |
| Generalplus Technology               | 1         | 0.11%   |
| Corsair                              | 1         | 0.11%   |
| Audio-Technica                       | 1         | 0.11%   |
| ASUSTek Computer                     | 1         | 0.11%   |
| Astro Gaming                         | 1         | 0.11%   |
| Antlion Audio                        | 1         | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 125       | 11.36%  |
| Intel Sunrise Point-LP HD Audio                                            | 68        | 6.18%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 64        | 5.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 49        | 4.45%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 40        | 3.64%   |
| Intel Haswell-ULT HD Audio Controller                                      | 35        | 3.18%   |
| Intel 8 Series HD Audio Controller                                         | 34        | 3.09%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 33        | 3%      |
| Intel Tiger Lake-H HD Audio Controller                                     | 29        | 2.64%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 28        | 2.55%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 26        | 2.36%   |
| Intel Broadwell-U Audio Controller                                         | 26        | 2.36%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 26        | 2.36%   |
| Intel Comet Lake PCH cAVS                                                  | 25        | 2.27%   |
| Intel Cannon Lake PCH cAVS                                                 | 25        | 2.27%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 21        | 1.91%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 20        | 1.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 20        | 1.82%   |
| Nvidia GA106 High Definition Audio Controller                              | 19        | 1.73%   |
| Intel Comet Lake PCH-LP cAVS                                               | 19        | 1.73%   |
| Nvidia GA104 High Definition Audio Controller                              | 18        | 1.64%   |
| Intel CM238 HD Audio Controller                                            | 18        | 1.64%   |
| AMD FCH Azalia Controller                                                  | 18        | 1.64%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 17        | 1.55%   |
| Nvidia TU106 High Definition Audio Controller                              | 14        | 1.27%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 14        | 1.27%   |
| Nvidia Audio device                                                        | 11        | 1%      |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 11        | 1%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 11        | 1%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 10        | 0.91%   |
| AMD Kabini HDMI/DP Audio                                                   | 10        | 0.91%   |
| Nvidia MCP79 High Definition Audio                                         | 9         | 0.82%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9         | 0.82%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 9         | 0.82%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 8         | 0.73%   |
| Nvidia TU116 High Definition Audio Controller                              | 7         | 0.64%   |
| Nvidia TU104 HD Audio Controller                                           | 6         | 0.55%   |
| Nvidia GP106 High Definition Audio Controller                              | 6         | 0.55%   |
| Nvidia GK107 HDMI Audio Controller                                         | 6         | 0.55%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 6         | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 71        | 30.47%  |
| SK hynix            | 54        | 23.18%  |
| Micron Technology   | 35        | 15.02%  |
| Kingston            | 11        | 4.72%   |
| Crucial             | 10        | 4.29%   |
| Unknown             | 6         | 2.58%   |
| Smart               | 6         | 2.58%   |
| Unknown             | 5         | 2.15%   |
| A-DATA Technology   | 4         | 1.72%   |
| Team                | 3         | 1.29%   |
| Neo Forza           | 3         | 1.29%   |
| Goldkey             | 3         | 1.29%   |
| G.Skill             | 3         | 1.29%   |
| Ramaxel Technology  | 2         | 0.86%   |
| PNY                 | 2         | 0.86%   |
| GSkill              | 2         | 0.86%   |
| Elpida              | 2         | 0.86%   |
| Avant               | 2         | 0.86%   |
| Unknown (ABCD)      | 1         | 0.43%   |
| Unknown (8A02)      | 1         | 0.43%   |
| Timetec             | 1         | 0.43%   |
| Teikon              | 1         | 0.43%   |
| Smart Brazil        | 1         | 0.43%   |
| Nanya Technology    | 1         | 0.43%   |
| Gold Key            | 1         | 0.43%   |
| Corsair             | 1         | 0.43%   |
| Apacer              | 1         | 0.43%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 2.85%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 2.44%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 2.44%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 2.03%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 5         | 2.03%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 5         | 2.03%   |
| Unknown                                                          | 5         | 2.03%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 4         | 1.63%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 1.63%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 1.22%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 3         | 1.22%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 3         | 1.22%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 3         | 1.22%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 1.22%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 3         | 1.22%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 1.22%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.22%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 2         | 0.81%   |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s            | 2         | 0.81%   |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s            | 2         | 0.81%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.81%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.81%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 0.81%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.81%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.81%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.81%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.81%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 2         | 0.81%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 0.81%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 0.81%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 0.81%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 0.81%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s            | 2         | 0.81%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 2         | 0.81%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 2         | 0.81%   |
| Neo Forza RAM NMSO416E82-3200E 16GB SODIMM DDR4 3200MT/s         | 2         | 0.81%   |
| Micron RAM MT62F1G32D4DR-031 WT 4GB Row Of Chips LPDDR5 6400MT/s | 2         | 0.81%   |
| Micron RAM Module 16GB SODIMM DDR4 3200MT/s                      | 2         | 0.81%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 0.81%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 2         | 0.81%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 122       | 62.24%  |
| DDR3    | 32        | 16.33%  |
| LPDDR4  | 15        | 7.65%   |
| LPDDR3  | 9         | 4.59%   |
| LPDDR5  | 5         | 2.55%   |
| DDR5    | 4         | 2.04%   |
| Unknown | 4         | 2.04%   |
| SDRAM   | 3         | 1.53%   |
| DDR2    | 2         | 1.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 161       | 79.7%   |
| Row Of Chips | 39        | 19.31%  |
| Chip         | 2         | 0.99%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 96        | 45.5%   |
| 4096  | 52        | 24.64%  |
| 16384 | 35        | 16.59%  |
| 32768 | 14        | 6.64%   |
| 2048  | 14        | 6.64%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 70        | 33.18%  |
| 2667  | 43        | 20.38%  |
| 1600  | 23        | 10.9%   |
| 2400  | 13        | 6.16%   |
| 2133  | 13        | 6.16%   |
| 4267  | 8         | 3.79%   |
| 4800  | 7         | 3.32%   |
| 6400  | 6         | 2.84%   |
| 8400  | 5         | 2.37%   |
| 1333  | 5         | 2.37%   |
| 3266  | 3         | 1.42%   |
| 1867  | 3         | 1.42%   |
| 4266  | 2         | 0.95%   |
| 3733  | 2         | 0.95%   |
| 2048  | 2         | 0.95%   |
| 1334  | 2         | 0.95%   |
| 800   | 2         | 0.95%   |
| 4199  | 1         | 0.47%   |
| 1067  | 1         | 0.47%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 50%     |
| Canon           | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| HP Ink Tank Wireless 410 series | 1         | 50%     |
| Canon E400 series               | 1         | 50%     |

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
| Chicony Electronics                    | 137       | 22.39%  |
| Acer                                   | 73        | 11.93%  |
| Microdia                               | 65        | 10.62%  |
| IMC Networks                           | 59        | 9.64%   |
| Realtek Semiconductor                  | 50        | 8.17%   |
| Quanta                                 | 37        | 6.05%   |
| Sunplus Innovation Technology          | 36        | 5.88%   |
| Apple                                  | 28        | 4.58%   |
| Cheng Uei Precision Industry (Foxlink) | 17        | 2.78%   |
| Syntek                                 | 16        | 2.61%   |
| Suyin                                  | 16        | 2.61%   |
| Lite-On Technology                     | 12        | 1.96%   |
| Luxvisions Innotech Limited            | 9         | 1.47%   |
| Logitech                               | 8         | 1.31%   |
| Silicon Motion                         | 7         | 1.14%   |
| SunplusIT                              | 6         | 0.98%   |
| Sonix Technology                       | 5         | 0.82%   |
| Samsung Electronics                    | 5         | 0.82%   |
| Z-Star Microelectronics                | 3         | 0.49%   |
| Razer USA                              | 3         | 0.49%   |
| Microsoft                              | 3         | 0.49%   |
| Generalplus Technology                 | 3         | 0.49%   |
| Alcor Micro                            | 3         | 0.49%   |
| Ricoh                                  | 2         | 0.33%   |
| Primax Electronics                     | 2         | 0.33%   |
| SJ-180517-N                            | 1         | 0.16%   |
| Oculus VR                              | 1         | 0.16%   |
| LG Electronics                         | 1         | 0.16%   |
| KYE Systems (Mouse Systems)            | 1         | 0.16%   |
| Importek                               | 1         | 0.16%   |
| eMPIA Technology                       | 1         | 0.16%   |
| AVerMedia Technologies                 | 1         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                    | 31        | 5.04%   |
| Chicony Integrated Camera                        | 31        | 5.04%   |
| Realtek Integrated_Webcam_HD                     | 22        | 3.58%   |
| IMC Networks USB2.0 HD UVC WebCam                | 20        | 3.25%   |
| Syntek Integrated Camera                         | 14        | 2.28%   |
| Chicony HD WebCam                                | 14        | 2.28%   |
| Acer Integrated Camera                           | 14        | 2.28%   |
| IMC Networks Integrated Camera                   | 13        | 2.11%   |
| Acer HD Webcam                                   | 13        | 2.11%   |
| Acer BisonCam,NB Pro                             | 12        | 1.95%   |
| Sunplus Integrated_Webcam_HD                     | 11        | 1.79%   |
| Quanta HD User Facing                            | 9         | 1.46%   |
| Chicony USB2.0 VGA UVC WebCam                    | 9         | 1.46%   |
| Microdia Integrated Webcam                       | 8         | 1.3%    |
| Chicony USB2.0 Camera                            | 8         | 1.3%    |
| Apple FaceTime HD Camera                         | 8         | 1.3%    |
| Apple Built-in iSight                            | 8         | 1.3%    |
| Quanta HP HD Camera                              | 7         | 1.14%   |
| Apple iPhone5/5C/5S/6                            | 7         | 1.14%   |
| Lite-On Integrated Camera                        | 6         | 0.98%   |
| Chicony USB 2.0 Camera                           | 6         | 0.98%   |
| Chicony TOSHIBA Web Camera - HD                  | 6         | 0.98%   |
| Suyin 1.3M HD WebCam                             | 5         | 0.81%   |
| Sonix USB2.0 HD UVC WebCam                       | 5         | 0.81%   |
| Samsung Galaxy A5 (MTP)                          | 5         | 0.81%   |
| Chicony Integrated Camera (1280x720@30)          | 5         | 0.81%   |
| Chicony HD User Facing                           | 5         | 0.81%   |
| Acer SunplusIT Integrated Camera                 | 5         | 0.81%   |
| Suyin HP Truevision HD                           | 4         | 0.65%   |
| Realtek USB2.0 HD UVC WebCam                     | 4         | 0.65%   |
| Quanta HP TrueVision HD Camera                   | 4         | 0.65%   |
| Quanta HD Webcam                                 | 4         | 0.65%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 4         | 0.65%   |
| IMC Networks USB2.0 UVC HD Webcam                | 4         | 0.65%   |
| Chicony USB2.0 HD UVC WebCam                     | 4         | 0.65%   |
| Chicony ThinkPad T490 Webcam                     | 4         | 0.65%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 4         | 0.65%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera | 4         | 0.65%   |
| Acer Lenovo EasyCamera                           | 4         | 0.65%   |
| Acer BisonCam, NB Pro                            | 4         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 44        | 40.74%  |
| Validity Sensors           | 25        | 23.15%  |
| Shenzhen Goodix Technology | 24        | 22.22%  |
| LighTuning Technology      | 6         | 5.56%   |
| Upek                       | 3         | 2.78%   |
| HOLTEK                     | 2         | 1.85%   |
| Elan Microelectronics      | 2         | 1.85%   |
| AuthenTec                  | 2         | 1.85%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                        | 14        | 12.96%  |
| Unknown                                                    | 13        | 12.04%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 11        | 10.19%  |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 7         | 6.48%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 6         | 5.56%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 5         | 4.63%   |
| Synaptics WBDI Device                                      | 5         | 4.63%   |
| Shenzhen Goodix Fingerprint Reader                         | 5         | 4.63%   |
| Shenzhen Goodix FingerPrint                                | 5         | 4.63%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 4         | 3.7%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 4         | 3.7%    |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 4         | 3.7%    |
| Validity Sensors Synaptics WBDI                            | 3         | 2.78%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 3         | 2.78%   |
| Validity Sensors VFS491                                    | 2         | 1.85%   |
| Validity Sensors Fingerprint scanner                       | 2         | 1.85%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 2         | 1.85%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 2         | 1.85%   |
| HOLTEK FocalTech Fingerprint Device                        | 2         | 1.85%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor          | 1         | 0.93%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 0.93%   |
| Validity Sensors Swipe Fingerprint Sensor                  | 1         | 0.93%   |
| Synaptics  WBDI                                            | 1         | 0.93%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.93%   |
| Elan ELAN:Fingerprint                                      | 1         | 0.93%   |
| Elan ELAN:ARM-M4                                           | 1         | 0.93%   |
| AuthenTec AES2810                                          | 1         | 0.93%   |
| AuthenTec AES2550 Fingerprint Sensor                       | 1         | 0.93%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 23        | 52.27%  |
| Alcor Micro | 12        | 27.27%  |
| O2 Micro    | 3         | 6.82%   |
| Upek        | 2         | 4.55%   |
| Lenovo      | 2         | 4.55%   |
| OmniKey     | 1         | 2.27%   |
| Clay Logic  | 1         | 2.27%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 12        | 27.27%  |
| Broadcom 5880                                                                | 8         | 18.18%  |
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 15.91%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 9.09%   |
| Broadcom 58200                                                               | 4         | 9.09%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 4.55%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 4.55%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 4.55%   |
| OmniKey CardMan 4321                                                         | 1         | 2.27%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 2.27%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 2.27%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 393       | 57.62%  |
| 1     | 226       | 33.14%  |
| 2     | 51        | 7.48%   |
| 3     | 11        | 1.61%   |
| 4     | 1         | 0.15%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 101       | 28.69%  |
| Multimedia controller    | 63        | 17.9%   |
| Net/wireless             | 44        | 12.5%   |
| Chipcard                 | 41        | 11.65%  |
| Graphics card            | 39        | 11.08%  |
| Bluetooth                | 28        | 7.95%   |
| Camera                   | 9         | 2.56%   |
| Sound                    | 6         | 1.7%    |
| Storage                  | 4         | 1.14%   |
| Network                  | 4         | 1.14%   |
| Net/ethernet             | 4         | 1.14%   |
| Communication controller | 3         | 0.85%   |
| Storage/ide              | 2         | 0.57%   |
| Modem                    | 2         | 0.57%   |
| Card reader              | 2         | 0.57%   |


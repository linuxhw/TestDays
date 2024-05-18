Linux in Taiwan - Tested Hardware & Statistics (Desktops)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Taiwan.

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

Total: 409

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Huanan        | X99-TF V3.0 JX              | [bb51640f19](https://linux-hardware.org/?probe=bb51640f19) | Apr 21, 2024 |
| ASUSTek       | H170M-PLUS                  | [36ed031c7f](https://linux-hardware.org/?probe=36ed031c7f) | Apr 17, 2024 |
| ASUSTek       | WS C422 PRO_SE              | [f4279202a4](https://linux-hardware.org/?probe=f4279202a4) | Apr 12, 2024 |
| Lenovo        | 36C5 SDK0L77767 WIN 3423... | [79cb6ea23b](https://linux-hardware.org/?probe=79cb6ea23b) | Apr 10, 2024 |
| Gigabyte      | GA-H61TN-SI                 | [3f6b496eb7](https://linux-hardware.org/?probe=3f6b496eb7) | Apr 02, 2024 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | [d1554bd2c0](https://linux-hardware.org/?probe=d1554bd2c0) | Apr 01, 2024 |
| JGINYUE       | X99M-PLUS D4 V3.1           | [e44ab52f45](https://linux-hardware.org/?probe=e44ab52f45) | Mar 29, 2024 |
| ASUSTek       | PRIME B560M-K               | [75a6f1b690](https://linux-hardware.org/?probe=75a6f1b690) | Mar 29, 2024 |
| Gigabyte      | GA-770TA-UD3                | [2b6ed8b07a](https://linux-hardware.org/?probe=2b6ed8b07a) | Mar 26, 2024 |
| Gigabyte      | GA-770TA-UD3                | [04474844f0](https://linux-hardware.org/?probe=04474844f0) | Mar 26, 2024 |
| ASRock        | X300M-STX                   | [41f3f09405](https://linux-hardware.org/?probe=41f3f09405) | Mar 23, 2024 |
| JGINYUE       | X99 TITANIUM D3             | [4ba18d3790](https://linux-hardware.org/?probe=4ba18d3790) | Mar 22, 2024 |
| ASUSTek       | Pro WS X570-ACE             | [fe713b8d04](https://linux-hardware.org/?probe=fe713b8d04) | Mar 21, 2024 |
| MSI           | H110M PRO-VD                | [29f63e63c9](https://linux-hardware.org/?probe=29f63e63c9) | Mar 16, 2024 |
| EBN           | MA1N                        | [03917cfce5](https://linux-hardware.org/?probe=03917cfce5) | Mar 06, 2024 |
| OEM           | B85 JHS359                  | [30c44600e2](https://linux-hardware.org/?probe=30c44600e2) | Mar 06, 2024 |
| Huanan        | B85                         | [22ee4d4c6d](https://linux-hardware.org/?probe=22ee4d4c6d) | Mar 05, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | [a4297d40d4](https://linux-hardware.org/?probe=a4297d40d4) | Feb 13, 2024 |
| Centerm       | C92                         | [5b7b85d16b](https://linux-hardware.org/?probe=5b7b85d16b) | Feb 03, 2024 |
| EBN           | MA1N                        | [302ea43954](https://linux-hardware.org/?probe=302ea43954) | Feb 01, 2024 |
| Gigabyte      | B460 AORUS PRO AC           | [276a0b5785](https://linux-hardware.org/?probe=276a0b5785) | Jan 19, 2024 |
| Unknown       | Unknown                     | [1c86716af5](https://linux-hardware.org/?probe=1c86716af5) | Jan 15, 2024 |
| Unknown       | Unknown                     | [5e8d8eb89f](https://linux-hardware.org/?probe=5e8d8eb89f) | Jan 15, 2024 |
| Gigabyte      | X670E AORUS MASTER          | [537c95bdae](https://linux-hardware.org/?probe=537c95bdae) | Jan 11, 2024 |
| Gigabyte      | Z77M-D3H                    | [d20dfe448d](https://linux-hardware.org/?probe=d20dfe448d) | Jan 06, 2024 |
| ASRock        | X300M-STX                   | [a9f024df00](https://linux-hardware.org/?probe=a9f024df00) | Jan 03, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | [ca2b52b64f](https://linux-hardware.org/?probe=ca2b52b64f) | Dec 31, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [da58685854](https://linux-hardware.org/?probe=da58685854) | Dec 25, 2023 |
| Gigabyte      | G1.Sniper B5-CF             | [9d3fa026ff](https://linux-hardware.org/?probe=9d3fa026ff) | Dec 25, 2023 |
| ASUSTek       | D500MD                      | [21870febdd](https://linux-hardware.org/?probe=21870febdd) | Dec 25, 2023 |
| HP            | 21D0                        | [733191fd29](https://linux-hardware.org/?probe=733191fd29) | Dec 24, 2023 |
| Gigabyte      | B660I AORUS PRO DDR4        | [f9552f9e38](https://linux-hardware.org/?probe=f9552f9e38) | Dec 21, 2023 |
| Dell          | 0101XX A00                  | [13751aa80b](https://linux-hardware.org/?probe=13751aa80b) | Dec 21, 2023 |
| HP            | 8061                        | [9700867e8c](https://linux-hardware.org/?probe=9700867e8c) | Dec 13, 2023 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [6ed556a0a1](https://linux-hardware.org/?probe=6ed556a0a1) | Dec 03, 2023 |
| HP            | 8061                        | [8f86201dfb](https://linux-hardware.org/?probe=8f86201dfb) | Dec 01, 2023 |
| HP            | 83E2                        | [b580eaa5fa](https://linux-hardware.org/?probe=b580eaa5fa) | Nov 27, 2023 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [15c6e07487](https://linux-hardware.org/?probe=15c6e07487) | Nov 27, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [84b3b5a3a1](https://linux-hardware.org/?probe=84b3b5a3a1) | Nov 25, 2023 |
| HP            | 21D0                        | [3e85a284ec](https://linux-hardware.org/?probe=3e85a284ec) | Nov 23, 2023 |
| ASRock        | B660M-STX                   | [883a70813a](https://linux-hardware.org/?probe=883a70813a) | Nov 19, 2023 |
| Acer          | EG43LMK                     | [bc1ab38f8f](https://linux-hardware.org/?probe=bc1ab38f8f) | Nov 18, 2023 |
| ASUSTek       | W580/SYS                    | [31a696a5bc](https://linux-hardware.org/?probe=31a696a5bc) | Nov 14, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [61b583fe07](https://linux-hardware.org/?probe=61b583fe07) | Nov 12, 2023 |
| Unknown       | ADL-N Prod                  | [c3e54c030c](https://linux-hardware.org/?probe=c3e54c030c) | Nov 08, 2023 |
| Unknown       | ADL-N Prod                  | [023eb019ba](https://linux-hardware.org/?probe=023eb019ba) | Nov 08, 2023 |
| ASRock        | H97M Anniversary            | [6c66e3862d](https://linux-hardware.org/?probe=6c66e3862d) | Nov 01, 2023 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [39f8a7c959](https://linux-hardware.org/?probe=39f8a7c959) | Nov 01, 2023 |
| ASUSTek       | PRIME B360M-C               | [874efda598](https://linux-hardware.org/?probe=874efda598) | Oct 31, 2023 |
| ASUSTek       | PRIME B360M-C               | [16da68741a](https://linux-hardware.org/?probe=16da68741a) | Oct 31, 2023 |
| ASUSTek       | P5E Deluxe                  | [5601096ffc](https://linux-hardware.org/?probe=5601096ffc) | Oct 29, 2023 |
| Gigabyte      | GA-770TA-UD3                | [f1a5d466cd](https://linux-hardware.org/?probe=f1a5d466cd) | Oct 29, 2023 |
| ASUSTek       | H81M-E                      | [1cd579935b](https://linux-hardware.org/?probe=1cd579935b) | Oct 27, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [d49188de1a](https://linux-hardware.org/?probe=d49188de1a) | Oct 26, 2023 |
| Gigabyte      | GA-770TA-UD3                | [6944656466](https://linux-hardware.org/?probe=6944656466) | Oct 26, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [bb6c63a5b3](https://linux-hardware.org/?probe=bb6c63a5b3) | Oct 26, 2023 |
| Dell          | 097YXY A00                  | [31dc22d5af](https://linux-hardware.org/?probe=31dc22d5af) | Oct 24, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [3130876407](https://linux-hardware.org/?probe=3130876407) | Oct 17, 2023 |
| Acer          | EG31M P01-A0                | [1e500b6b4a](https://linux-hardware.org/?probe=1e500b6b4a) | Oct 17, 2023 |
| ONDA          | H110CD3 VER1.01             | [df23b03be3](https://linux-hardware.org/?probe=df23b03be3) | Oct 15, 2023 |
| HP            | 802F                        | [ed3a09f912](https://linux-hardware.org/?probe=ed3a09f912) | Oct 12, 2023 |
| MSI           | PRO H610M-G DDR4            | [c698bae21a](https://linux-hardware.org/?probe=c698bae21a) | Oct 12, 2023 |
| MSI           | PRO H610M-G DDR4            | [167f75f814](https://linux-hardware.org/?probe=167f75f814) | Oct 12, 2023 |
| HP            | 802F                        | [c2b0f9720e](https://linux-hardware.org/?probe=c2b0f9720e) | Oct 12, 2023 |
| ASUSTek       | P5Q3 DELUXE                 | [29bb46e198](https://linux-hardware.org/?probe=29bb46e198) | Oct 12, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [a5904a1aeb](https://linux-hardware.org/?probe=a5904a1aeb) | Oct 07, 2023 |
| Dell          | 00010C A00                  | [40d7defca4](https://linux-hardware.org/?probe=40d7defca4) | Sep 23, 2023 |
| Centerm       | C92                         | [022344ea10](https://linux-hardware.org/?probe=022344ea10) | Sep 22, 2023 |
| Acer          | Revo RN86                   | [315559ee42](https://linux-hardware.org/?probe=315559ee42) | Sep 21, 2023 |
| ASUSTek       | Z170-P D3                   | [fad69be075](https://linux-hardware.org/?probe=fad69be075) | Sep 12, 2023 |
| MSI           | MS-B0A81                    | [2c4cc9e78f](https://linux-hardware.org/?probe=2c4cc9e78f) | Sep 05, 2023 |
| Gigabyte      | GA-770TA-UD3                | [6bd78c519f](https://linux-hardware.org/?probe=6bd78c519f) | Aug 25, 2023 |
| ASUSTek       | M11AD                       | [a107c7eb20](https://linux-hardware.org/?probe=a107c7eb20) | Aug 25, 2023 |
| Acer          | Predator G3610              | [008082be63](https://linux-hardware.org/?probe=008082be63) | Aug 19, 2023 |
| Acer          | Predator G3610              | [d362c81682](https://linux-hardware.org/?probe=d362c81682) | Aug 19, 2023 |
| ASUSTek       | BM6875_BM6675_BP6375        | [0a2cdad4c1](https://linux-hardware.org/?probe=0a2cdad4c1) | Aug 15, 2023 |
| Gigabyte      | B550M K                     | [139e314619](https://linux-hardware.org/?probe=139e314619) | Jul 31, 2023 |
| Dell          | 00010C A00                  | [71eca6ee4c](https://linux-hardware.org/?probe=71eca6ee4c) | Jul 20, 2023 |
| Altos         | BrainSphere P10 F7          | [8608df7a38](https://linux-hardware.org/?probe=8608df7a38) | Jul 20, 2023 |
| AAEON         | GENE-CML5 V1.0              | [4120e07431](https://linux-hardware.org/?probe=4120e07431) | Jul 19, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [62238aaf82](https://linux-hardware.org/?probe=62238aaf82) | Jul 17, 2023 |
| Acer          | Aspire TC-895 V:1.0         | [bc805d82a7](https://linux-hardware.org/?probe=bc805d82a7) | Jul 13, 2023 |
| ASUSTek       | PRIME B660M-K D4            | [36b6c49552](https://linux-hardware.org/?probe=36b6c49552) | Jul 09, 2023 |
| ASUSTek       | PRIME B660M-K D4            | [ffa5984711](https://linux-hardware.org/?probe=ffa5984711) | Jul 09, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [e5d4d7b4a7](https://linux-hardware.org/?probe=e5d4d7b4a7) | Jul 06, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [f15cf1d31b](https://linux-hardware.org/?probe=f15cf1d31b) | Jul 02, 2023 |
| Intel         | X99                         | [81dbd5c4f0](https://linux-hardware.org/?probe=81dbd5c4f0) | Jul 01, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | [e72c8358c4](https://linux-hardware.org/?probe=e72c8358c4) | Jun 22, 2023 |
| ASRock        | X370 Killer SLI             | [10939cb152](https://linux-hardware.org/?probe=10939cb152) | Jun 20, 2023 |
| ASUSTek       | PRIME B650M-A WIFI          | [2734ce8c5d](https://linux-hardware.org/?probe=2734ce8c5d) | Jun 16, 2023 |
| MSI           | B250M MORTAR ARCTIC         | [5e0e6586b7](https://linux-hardware.org/?probe=5e0e6586b7) | Jun 11, 2023 |
| MSI           | H97 GAMING 3                | [f9c0a669c5](https://linux-hardware.org/?probe=f9c0a669c5) | Jun 02, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [fc4e2630c0](https://linux-hardware.org/?probe=fc4e2630c0) | Jun 01, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [f02c7845e5](https://linux-hardware.org/?probe=f02c7845e5) | Jun 01, 2023 |
| Acer          | Aspire TC-895 V:1.0         | [936b06e11f](https://linux-hardware.org/?probe=936b06e11f) | May 25, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [2adc02040e](https://linux-hardware.org/?probe=2adc02040e) | May 21, 2023 |
| Win elemen... | M600                        | [4c5d685663](https://linux-hardware.org/?probe=4c5d685663) | May 21, 2023 |
| Win elemen... | M600                        | [84de4a3207](https://linux-hardware.org/?probe=84de4a3207) | May 20, 2023 |
| Unknown       | Unknown                     | [661a7cf306](https://linux-hardware.org/?probe=661a7cf306) | May 11, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [867e98f955](https://linux-hardware.org/?probe=867e98f955) | May 05, 2023 |
| MSI           | H55M-P31                    | [386b720202](https://linux-hardware.org/?probe=386b720202) | May 04, 2023 |
| Acer          | Veriton M2630G V:1.0        | [7ffa9c83d7](https://linux-hardware.org/?probe=7ffa9c83d7) | May 03, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | [e5051f5355](https://linux-hardware.org/?probe=e5051f5355) | May 02, 2023 |
| HP            | 83E2                        | [f10d975821](https://linux-hardware.org/?probe=f10d975821) | Apr 26, 2023 |
| ASRock        | X300M-STX                   | [4a8d662bee](https://linux-hardware.org/?probe=4a8d662bee) | Apr 25, 2023 |
| Gigabyte      | H81N                        | [5729c6c6a9](https://linux-hardware.org/?probe=5729c6c6a9) | Apr 20, 2023 |
| Acer          | Predator G3610              | [3d1841fa41](https://linux-hardware.org/?probe=3d1841fa41) | Apr 17, 2023 |
| Acer          | EG43LMK                     | [78b389b848](https://linux-hardware.org/?probe=78b389b848) | Apr 15, 2023 |
| Acer          | Predator G3610              | [d49e4d680c](https://linux-hardware.org/?probe=d49e4d680c) | Apr 14, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [ad8009e647](https://linux-hardware.org/?probe=ad8009e647) | Apr 11, 2023 |
| Win elemen... | M600                        | [7723a03558](https://linux-hardware.org/?probe=7723a03558) | Apr 10, 2023 |
| Win elemen... | M600                        | [e20927ec15](https://linux-hardware.org/?probe=e20927ec15) | Apr 10, 2023 |
| Gigabyte      | F2A78M-DS2                  | [0528b2df2b](https://linux-hardware.org/?probe=0528b2df2b) | Apr 01, 2023 |
| Unknown       | Unknown                     | [8f1561c37b](https://linux-hardware.org/?probe=8f1561c37b) | Mar 28, 2023 |
| ASRock        | N68-GS4/USB3 FX             | [b846b11174](https://linux-hardware.org/?probe=b846b11174) | Mar 25, 2023 |
| ASUSTek       | H110M-K D3                  | [24a568ad05](https://linux-hardware.org/?probe=24a568ad05) | Mar 25, 2023 |
| MSI           | H55M-P31                    | [07a5228600](https://linux-hardware.org/?probe=07a5228600) | Mar 25, 2023 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [b03324de35](https://linux-hardware.org/?probe=b03324de35) | Mar 24, 2023 |
| Gigabyte      | B75N                        | [8a16ffed3b](https://linux-hardware.org/?probe=8a16ffed3b) | Mar 21, 2023 |
| ASUSTek       | TUF Gaming H470-PRO         | [7d1cd9aded](https://linux-hardware.org/?probe=7d1cd9aded) | Mar 20, 2023 |
| OEM           | B85 JHS359                  | [1d5d7e95fc](https://linux-hardware.org/?probe=1d5d7e95fc) | Mar 16, 2023 |
| Gigabyte      | G31M-ES2L                   | [f5535f53dc](https://linux-hardware.org/?probe=f5535f53dc) | Mar 08, 2023 |
| ASUSTek       | H81M-E                      | [fc1a09013d](https://linux-hardware.org/?probe=fc1a09013d) | Mar 05, 2023 |
| MSI           | MEG X670E ACE               | [ee356bc253](https://linux-hardware.org/?probe=ee356bc253) | Mar 02, 2023 |
| ASRock        | X300M-STX                   | [061edbf583](https://linux-hardware.org/?probe=061edbf583) | Mar 01, 2023 |
| ASRock        | X300M-STX                   | [97a1558878](https://linux-hardware.org/?probe=97a1558878) | Feb 25, 2023 |
| Maxtang       | EHL30 V1.0                  | [4d133c615c](https://linux-hardware.org/?probe=4d133c615c) | Feb 10, 2023 |
| ASRockRack    | X570D4U                     | [bb2c98768e](https://linux-hardware.org/?probe=bb2c98768e) | Feb 10, 2023 |
| Gigabyte      | Z170-HD3P-CF                | [7f895dc97f](https://linux-hardware.org/?probe=7f895dc97f) | Feb 04, 2023 |
| Gigabyte      | Z170-HD3P-CF                | [9e9deedf0d](https://linux-hardware.org/?probe=9e9deedf0d) | Jan 31, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | [65e298b3ee](https://linux-hardware.org/?probe=65e298b3ee) | Jan 27, 2023 |
| Gigabyte      | H81N                        | [e7cf6a4216](https://linux-hardware.org/?probe=e7cf6a4216) | Jan 27, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | [5c55d923ff](https://linux-hardware.org/?probe=5c55d923ff) | Jan 26, 2023 |
| Acer          | Aspire XC-105               | [8192fe90a8](https://linux-hardware.org/?probe=8192fe90a8) | Jan 19, 2023 |
| Acer          | FMCP7A-ION-LE               | [84a2abec03](https://linux-hardware.org/?probe=84a2abec03) | Jan 07, 2023 |
| Unknown       | Unknown                     | [34b6109940](https://linux-hardware.org/?probe=34b6109940) | Dec 29, 2022 |
| ASUSTek       | PRIME H510M-K               | [9b1f8e9a10](https://linux-hardware.org/?probe=9b1f8e9a10) | Dec 18, 2022 |
| ASUSTek       | CM1530                      | [3990cff263](https://linux-hardware.org/?probe=3990cff263) | Dec 06, 2022 |
| Dell          | 0NNFGG A00                  | [b955357ccc](https://linux-hardware.org/?probe=b955357ccc) | Dec 05, 2022 |
| Gigabyte      | Z370M DS3H-CF               | [580b716020](https://linux-hardware.org/?probe=580b716020) | Dec 03, 2022 |
| ASUSTek       | Z97-K                       | [52aaeb537b](https://linux-hardware.org/?probe=52aaeb537b) | Dec 03, 2022 |
| ASRock        | X300M-STX                   | [97ceee65f3](https://linux-hardware.org/?probe=97ceee65f3) | Dec 01, 2022 |
| ASRock        | X300M-STX                   | [5b7f983a24](https://linux-hardware.org/?probe=5b7f983a24) | Dec 01, 2022 |
| ASRock        | X300M-STX                   | [42ddb2463e](https://linux-hardware.org/?probe=42ddb2463e) | Dec 01, 2022 |
| Dell          | 0XJ5V0 A03                  | [b954e4c174](https://linux-hardware.org/?probe=b954e4c174) | Nov 30, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING     | [aea7b4c016](https://linux-hardware.org/?probe=aea7b4c016) | Nov 23, 2022 |
| Gigabyte      | Z490 AORUS PRO AX           | [abe3da973c](https://linux-hardware.org/?probe=abe3da973c) | Nov 19, 2022 |
| Intel         | Burnside                    | [5db283bd1f](https://linux-hardware.org/?probe=5db283bd1f) | Nov 17, 2022 |
| ASRock        | A320M-HDV R4.0              | [7764c0fea2](https://linux-hardware.org/?probe=7764c0fea2) | Nov 15, 2022 |
| MSI           | A320M PRO-VH                | [70ba1bf558](https://linux-hardware.org/?probe=70ba1bf558) | Nov 08, 2022 |
| ASUSTek       | P5Q3 DELUXE                 | [a25c84e8f1](https://linux-hardware.org/?probe=a25c84e8f1) | Oct 25, 2022 |
| MSI           | A320M PRO-VH                | [5f1aeaf170](https://linux-hardware.org/?probe=5f1aeaf170) | Oct 22, 2022 |
| HP            | 1589                        | [a6be3ee931](https://linux-hardware.org/?probe=a6be3ee931) | Oct 17, 2022 |
| HP            | 1589                        | [c36aa260eb](https://linux-hardware.org/?probe=c36aa260eb) | Oct 17, 2022 |
| ASUSTek       | X99-A/USB                   | [11fc608e0a](https://linux-hardware.org/?probe=11fc608e0a) | Oct 10, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [5c45d7b1bf](https://linux-hardware.org/?probe=5c45d7b1bf) | Oct 09, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [0d7188c951](https://linux-hardware.org/?probe=0d7188c951) | Oct 03, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [dbe024bea9](https://linux-hardware.org/?probe=dbe024bea9) | Sep 16, 2022 |
| DNI           | SNDTP-1513N 5508015890      | [9570ee789c](https://linux-hardware.org/?probe=9570ee789c) | Aug 30, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [96a87ada26](https://linux-hardware.org/?probe=96a87ada26) | Aug 26, 2022 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [aaf726faa0](https://linux-hardware.org/?probe=aaf726faa0) | Aug 20, 2022 |
| ASRock        | B550M-ITX/ac                | [8898e9247d](https://linux-hardware.org/?probe=8898e9247d) | Aug 11, 2022 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | [2d41c9a29f](https://linux-hardware.org/?probe=2d41c9a29f) | Aug 08, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [21d06392bc](https://linux-hardware.org/?probe=21d06392bc) | Aug 06, 2022 |
| Gigabyte      | B550M DS3H                  | [69188053f5](https://linux-hardware.org/?probe=69188053f5) | Aug 02, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [6f083e1754](https://linux-hardware.org/?probe=6f083e1754) | Jul 27, 2022 |
| Gigabyte      | H310MSTX-HD3-CF             | [13e7ed20e1](https://linux-hardware.org/?probe=13e7ed20e1) | Jul 27, 2022 |
| BESSTAR Te... | HM90                        | [cb4da5b649](https://linux-hardware.org/?probe=cb4da5b649) | Jul 23, 2022 |
| BESSTAR Te... | HM90                        | [380230bbf6](https://linux-hardware.org/?probe=380230bbf6) | Jul 22, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [d88edfec1f](https://linux-hardware.org/?probe=d88edfec1f) | Jul 20, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [f32b12f921](https://linux-hardware.org/?probe=f32b12f921) | Jul 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [11fc460e29](https://linux-hardware.org/?probe=11fc460e29) | Jul 13, 2022 |
| MSI           | H81M-P33                    | [e523b324e6](https://linux-hardware.org/?probe=e523b324e6) | Jul 11, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [32e2995911](https://linux-hardware.org/?probe=32e2995911) | Jun 30, 2022 |
| MSI           | H81M-P33                    | [1a0e20ab20](https://linux-hardware.org/?probe=1a0e20ab20) | Jun 29, 2022 |
| MSI           | H81M-P33                    | [e25d17a838](https://linux-hardware.org/?probe=e25d17a838) | Jun 25, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [39cc29c976](https://linux-hardware.org/?probe=39cc29c976) | Jun 23, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [d610c245f8](https://linux-hardware.org/?probe=d610c245f8) | Jun 22, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [73c4749082](https://linux-hardware.org/?probe=73c4749082) | Jun 10, 2022 |
| Gigabyte      | B460 AORUS PRO AC           | [2966cd34b8](https://linux-hardware.org/?probe=2966cd34b8) | May 31, 2022 |
| MSI           | B150M BAZOOKA               | [b8ec3bee43](https://linux-hardware.org/?probe=b8ec3bee43) | May 22, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2c8abb0fed](https://linux-hardware.org/?probe=2c8abb0fed) | May 12, 2022 |
| Ruckus Wir... | SCG-100                     | [781560aa15](https://linux-hardware.org/?probe=781560aa15) | May 09, 2022 |
| ASUSTek       | Pro WS C621-64L SAGE-10G... | [4ebf4d9cc8](https://linux-hardware.org/?probe=4ebf4d9cc8) | May 09, 2022 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [288bb26592](https://linux-hardware.org/?probe=288bb26592) | Apr 27, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [6af9cfacd0](https://linux-hardware.org/?probe=6af9cfacd0) | Apr 23, 2022 |
| Dell          | Precision 3260              | [70a8481a89](https://linux-hardware.org/?probe=70a8481a89) | Apr 19, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [9d2aeecf05](https://linux-hardware.org/?probe=9d2aeecf05) | Apr 15, 2022 |
| Gigabyte      | B75M-D3H                    | [79aee125b7](https://linux-hardware.org/?probe=79aee125b7) | Apr 05, 2022 |
| ASUSTek       | M3A78-EMH HDMI              | [4462ffed73](https://linux-hardware.org/?probe=4462ffed73) | Apr 01, 2022 |
| Gigabyte      | EP31-DS3L                   | [7a4dfc156e](https://linux-hardware.org/?probe=7a4dfc156e) | Mar 28, 2022 |
| Gigabyte      | X570S AERO G                | [97cfd592c5](https://linux-hardware.org/?probe=97cfd592c5) | Mar 22, 2022 |
| ASUSTek       | P8H77-M PRO                 | [f7ee97d348](https://linux-hardware.org/?probe=f7ee97d348) | Mar 16, 2022 |
| ASRock        | X300M-STX                   | [5b18945822](https://linux-hardware.org/?probe=5b18945822) | Mar 15, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [8d52e31d86](https://linux-hardware.org/?probe=8d52e31d86) | Mar 09, 2022 |
| ASRock        | A300M-STX                   | [d9c28765e7](https://linux-hardware.org/?probe=d9c28765e7) | Mar 03, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [c11d937631](https://linux-hardware.org/?probe=c11d937631) | Feb 23, 2022 |
| ASUSTek       | B75M-PLUS                   | [c408f72a53](https://linux-hardware.org/?probe=c408f72a53) | Feb 23, 2022 |
| ASRock        | H81M-ITX                    | [bf52168e79](https://linux-hardware.org/?probe=bf52168e79) | Feb 14, 2022 |
| ASUSTek       | CM6630_CM6730_CM6830        | [bb588fd423](https://linux-hardware.org/?probe=bb588fd423) | Feb 07, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | [589137e95b](https://linux-hardware.org/?probe=589137e95b) | Feb 02, 2022 |
| ASUSTek       | P5P41T/USB3                 | [f45dc3454a](https://linux-hardware.org/?probe=f45dc3454a) | Jan 25, 2022 |
| ASUSTek       | P5P41T/USB3                 | [105593cece](https://linux-hardware.org/?probe=105593cece) | Jan 23, 2022 |
| ASUSTek       | P5P41T/USB3                 | [8db65bef56](https://linux-hardware.org/?probe=8db65bef56) | Jan 20, 2022 |
| Acer          | Aspire M3970                | [e10ce7d132](https://linux-hardware.org/?probe=e10ce7d132) | Dec 31, 2021 |
| ASUSTek       | Pro WS X570-ACE             | [cbb5305dc7](https://linux-hardware.org/?probe=cbb5305dc7) | Dec 30, 2021 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [8eec04fc92](https://linux-hardware.org/?probe=8eec04fc92) | Dec 29, 2021 |
| DFI           | HD330-Q87CR                 | [000e53fce1](https://linux-hardware.org/?probe=000e53fce1) | Dec 28, 2021 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [f8a6ac527d](https://linux-hardware.org/?probe=f8a6ac527d) | Dec 27, 2021 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [85bcddc2e5](https://linux-hardware.org/?probe=85bcddc2e5) | Dec 27, 2021 |
| Huanan        | B85                         | [d2b55c013c](https://linux-hardware.org/?probe=d2b55c013c) | Dec 07, 2021 |
| Acer          | EG43LMK                     | [28e31230a4](https://linux-hardware.org/?probe=28e31230a4) | Nov 28, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [8fb57be688](https://linux-hardware.org/?probe=8fb57be688) | Nov 22, 2021 |
| MSI           | PRO Z690-A DDR4             | [ae15f235e1](https://linux-hardware.org/?probe=ae15f235e1) | Nov 20, 2021 |
| ASRock        | G41C-VS                     | [e4a0a0c2c1](https://linux-hardware.org/?probe=e4a0a0c2c1) | Nov 19, 2021 |
| MSI           | MPG B560I GAMING EDGE WI... | [edc27953c6](https://linux-hardware.org/?probe=edc27953c6) | Oct 28, 2021 |
| eMachines     | EMCP73VT-PM                 | [6fe6c2d416](https://linux-hardware.org/?probe=6fe6c2d416) | Oct 27, 2021 |
| ASUSTek       | PRIME B350M-A               | [f20f2bfc32](https://linux-hardware.org/?probe=f20f2bfc32) | Oct 26, 2021 |
| eMachines     | EMCP73VT-PM                 | [22fd625209](https://linux-hardware.org/?probe=22fd625209) | Oct 26, 2021 |
| PANSHI        | B85-S1 V1.0                 | [963f2f28d4](https://linux-hardware.org/?probe=963f2f28d4) | Oct 24, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [09e3d5da46](https://linux-hardware.org/?probe=09e3d5da46) | Oct 21, 2021 |
| HP            | 84FD 10                     | [fb32fc7215](https://linux-hardware.org/?probe=fb32fc7215) | Oct 14, 2021 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [caeaeaddf2](https://linux-hardware.org/?probe=caeaeaddf2) | Oct 12, 2021 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [eef22ec3df](https://linux-hardware.org/?probe=eef22ec3df) | Oct 10, 2021 |
| HP            | 21D0                        | [4fccb60381](https://linux-hardware.org/?probe=4fccb60381) | Oct 08, 2021 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | [4b370353e4](https://linux-hardware.org/?probe=4b370353e4) | Sep 29, 2021 |
| Gigabyte      | H81M-H                      | [b961548815](https://linux-hardware.org/?probe=b961548815) | Sep 26, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [7114ee3f72](https://linux-hardware.org/?probe=7114ee3f72) | Sep 13, 2021 |
| Lenovo        | ThinkCentre M58 7627AA9     | [e5bedff47d](https://linux-hardware.org/?probe=e5bedff47d) | Aug 29, 2021 |
| HP            | 802E                        | [3ee51e8a56](https://linux-hardware.org/?probe=3ee51e8a56) | Aug 25, 2021 |
| ASUSTek       | H61-PLUS                    | [806118d8b3](https://linux-hardware.org/?probe=806118d8b3) | Aug 22, 2021 |
| Gigabyte      | Z97MX-Gaming 5              | [51947c0182](https://linux-hardware.org/?probe=51947c0182) | Aug 07, 2021 |
| Gigabyte      | H110M-H-CF                  | [37ac6809ad](https://linux-hardware.org/?probe=37ac6809ad) | Jul 31, 2021 |
| MSI           | B250M MORTAR                | [6c6e37fbfe](https://linux-hardware.org/?probe=6c6e37fbfe) | Jul 31, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [a8c5113f4c](https://linux-hardware.org/?probe=a8c5113f4c) | Jul 06, 2021 |
| Gigabyte      | H67MA-UD2H-B3               | [e014f9e41f](https://linux-hardware.org/?probe=e014f9e41f) | Jul 05, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [d90a6deaeb](https://linux-hardware.org/?probe=d90a6deaeb) | Jun 27, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [0e6ca5f944](https://linux-hardware.org/?probe=0e6ca5f944) | Jun 27, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [42090bac96](https://linux-hardware.org/?probe=42090bac96) | Jun 27, 2021 |
| ASUSTek       | BM6AD_BM1AD_BP1AD           | [cf9f5ab2b6](https://linux-hardware.org/?probe=cf9f5ab2b6) | Jun 23, 2021 |
| ASUSTek       | P8Z77-V LX                  | [98be9faa06](https://linux-hardware.org/?probe=98be9faa06) | Jun 21, 2021 |
| Supermicro    | C9Z490-PGW                  | [9b89e87202](https://linux-hardware.org/?probe=9b89e87202) | Jun 15, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [18b2fc7e21](https://linux-hardware.org/?probe=18b2fc7e21) | Jun 15, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [db99ef3085](https://linux-hardware.org/?probe=db99ef3085) | Jun 14, 2021 |
| Intel         | SHARKBAY                    | [2b38485e94](https://linux-hardware.org/?probe=2b38485e94) | Jun 13, 2021 |
| Dell          | 05GD68 A00                  | [b87ca56da6](https://linux-hardware.org/?probe=b87ca56da6) | Jun 11, 2021 |
| ASUSTek       | P5P41T/USB3                 | [be02c1622c](https://linux-hardware.org/?probe=be02c1622c) | Jun 06, 2021 |
| ASUSTek       | P8Z77-V DELUXE              | [ba117fef7e](https://linux-hardware.org/?probe=ba117fef7e) | May 31, 2021 |
| ASUSTek       | P5P41T/USB3                 | [e7eca73b93](https://linux-hardware.org/?probe=e7eca73b93) | May 30, 2021 |
| Dell          | 0RY206                      | [f02982ff12](https://linux-hardware.org/?probe=f02982ff12) | May 29, 2021 |
| ASRock        | H310M-ITX/ac                | [839b20476a](https://linux-hardware.org/?probe=839b20476a) | May 29, 2021 |
| ASRock        | X300M-STX                   | [6b0f0cd327](https://linux-hardware.org/?probe=6b0f0cd327) | May 27, 2021 |
| Gigabyte      | Z390 UD                     | [bbc8131c67](https://linux-hardware.org/?probe=bbc8131c67) | May 05, 2021 |
| Lenovo        | MAHOBAY                     | [6928edc4c3](https://linux-hardware.org/?probe=6928edc4c3) | Apr 30, 2021 |
| ASRock        | H55M/USB3                   | [8041f40ea2](https://linux-hardware.org/?probe=8041f40ea2) | Apr 22, 2021 |
| ASUSTek       | P8Z68-V LX                  | [060122f540](https://linux-hardware.org/?probe=060122f540) | Apr 19, 2021 |
| HP            | 0AECh D                     | [4e2517cb92](https://linux-hardware.org/?probe=4e2517cb92) | Apr 17, 2021 |
| ASUSTek       | P8Z68-V LX                  | [f67c224c2d](https://linux-hardware.org/?probe=f67c224c2d) | Apr 17, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [3dcec36efc](https://linux-hardware.org/?probe=3dcec36efc) | Mar 24, 2021 |
| Acer          | M1930                       | [ecd09c75f9](https://linux-hardware.org/?probe=ecd09c75f9) | Mar 23, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | [6fed85f2b6](https://linux-hardware.org/?probe=6fed85f2b6) | Mar 21, 2021 |
| Acer          | Veriton L4630G V:1.0        | [d5413884e0](https://linux-hardware.org/?probe=d5413884e0) | Feb 15, 2021 |
| Gigabyte      | B75M-D3H                    | [626560cf30](https://linux-hardware.org/?probe=626560cf30) | Feb 04, 2021 |
| ASRock        | HM87-MXM                    | [95efd1e9a2](https://linux-hardware.org/?probe=95efd1e9a2) | Feb 04, 2021 |
| Acer          | IPIMB-AR                    | [eb7a1feeff](https://linux-hardware.org/?probe=eb7a1feeff) | Jan 25, 2021 |
| MSI           | 760GM-P23                   | [8fdb02babb](https://linux-hardware.org/?probe=8fdb02babb) | Jan 24, 2021 |
| MSI           | 760GM-P23                   | [9ebcac45bd](https://linux-hardware.org/?probe=9ebcac45bd) | Jan 24, 2021 |
| ASUSTek       | TUF Gaming A520M-PLUS       | [ac56dd5c89](https://linux-hardware.org/?probe=ac56dd5c89) | Jan 23, 2021 |
| Gigabyte      | Z97MX-Gaming 5              | [1deb2b04c5](https://linux-hardware.org/?probe=1deb2b04c5) | Jan 21, 2021 |
| ASRock        | X300M-STX                   | [b690109a78](https://linux-hardware.org/?probe=b690109a78) | Jan 16, 2021 |
| Gigabyte      | G31M-ES2L                   | [7ade5574be](https://linux-hardware.org/?probe=7ade5574be) | Jan 14, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [e5dc6589db](https://linux-hardware.org/?probe=e5dc6589db) | Jan 05, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [1effa5938b](https://linux-hardware.org/?probe=1effa5938b) | Dec 31, 2020 |
| ASUSTek       | P5P41T/USB3                 | [f8f8546b66](https://linux-hardware.org/?probe=f8f8546b66) | Dec 28, 2020 |
| Gigabyte      | H310M H                     | [dfa5c13a96](https://linux-hardware.org/?probe=dfa5c13a96) | Dec 22, 2020 |
| MSI           | AM1M                        | [e7e7d1e0cc](https://linux-hardware.org/?probe=e7e7d1e0cc) | Dec 21, 2020 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [fb4b7a114e](https://linux-hardware.org/?probe=fb4b7a114e) | Dec 14, 2020 |
| Gigabyte      | H87-HD3                     | [55f095e43d](https://linux-hardware.org/?probe=55f095e43d) | Dec 13, 2020 |
| Gigabyte      | EP43-S3L                    | [7c9b5cd232](https://linux-hardware.org/?probe=7c9b5cd232) | Nov 28, 2020 |
| Gigabyte      | EP43-S3L                    | [218d68cc94](https://linux-hardware.org/?probe=218d68cc94) | Nov 27, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [799008f314](https://linux-hardware.org/?probe=799008f314) | Nov 26, 2020 |
| Gigabyte      | EP43-S3L                    | [c91fdcd723](https://linux-hardware.org/?probe=c91fdcd723) | Nov 26, 2020 |
| ASUSTek       | GR8 II-K                    | [dce0e65158](https://linux-hardware.org/?probe=dce0e65158) | Nov 24, 2020 |
| ASUSTek       | H97-PRO                     | [df130b5488](https://linux-hardware.org/?probe=df130b5488) | Nov 23, 2020 |
| Gigabyte      | AB350M-Gaming 3-CF          | [8b7818376f](https://linux-hardware.org/?probe=8b7818376f) | Nov 18, 2020 |
| Gigabyte      | AB350M-Gaming 3-CF          | [3d64c2bcc8](https://linux-hardware.org/?probe=3d64c2bcc8) | Nov 17, 2020 |
| ASUSTek       | PRIME B250M-K               | [35bc246b54](https://linux-hardware.org/?probe=35bc246b54) | Nov 13, 2020 |
| ASRock        | HM87-MXM                    | [d47723e369](https://linux-hardware.org/?probe=d47723e369) | Nov 03, 2020 |
| Unknown       | Unknown                     | [3ed3ea4f60](https://linux-hardware.org/?probe=3ed3ea4f60) | Oct 29, 2020 |
| Unknown       | Unknown                     | [c80fe9e03a](https://linux-hardware.org/?probe=c80fe9e03a) | Oct 29, 2020 |
| Gigabyte      | B85M-D2V                    | [1f2b50c872](https://linux-hardware.org/?probe=1f2b50c872) | Oct 24, 2020 |
| Gigabyte      | B75M-D3H                    | [352ce3d09c](https://linux-hardware.org/?probe=352ce3d09c) | Oct 16, 2020 |
| ASUSTek       | K30AM-J_A_F_K31AM-J         | [8de90e5004](https://linux-hardware.org/?probe=8de90e5004) | Oct 12, 2020 |
| MSI           | B450M-A PRO MAX             | [3712afebf5](https://linux-hardware.org/?probe=3712afebf5) | Oct 09, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [605fe21a48](https://linux-hardware.org/?probe=605fe21a48) | Oct 03, 2020 |
| ASUSTek       | M4A785D-M PRO               | [c8033471fb](https://linux-hardware.org/?probe=c8033471fb) | Oct 01, 2020 |
| HP            | 339A                        | [84f1e1735f](https://linux-hardware.org/?probe=84f1e1735f) | Sep 19, 2020 |
| Dell          | 0RY206                      | [40e7b0cafb](https://linux-hardware.org/?probe=40e7b0cafb) | Sep 05, 2020 |
| ASUSTek       | B85M-K                      | [8fe74ac1ad](https://linux-hardware.org/?probe=8fe74ac1ad) | Sep 04, 2020 |
| Unknown       | Unknown                     | [e5e9a43e32](https://linux-hardware.org/?probe=e5e9a43e32) | Sep 04, 2020 |
| NEXCOM        | SKLD4-P1                    | [23c5f53c73](https://linux-hardware.org/?probe=23c5f53c73) | Sep 03, 2020 |
| NEXCOM        | SKLD4-P1                    | [e27e3df3f3](https://linux-hardware.org/?probe=e27e3df3f3) | Sep 03, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [26c3ba8ef4](https://linux-hardware.org/?probe=26c3ba8ef4) | Sep 03, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [066c04a858](https://linux-hardware.org/?probe=066c04a858) | Sep 02, 2020 |
| MSI           | B450M-A PRO MAX             | [e46d6617a9](https://linux-hardware.org/?probe=e46d6617a9) | Aug 28, 2020 |
| Lenovo        | 7Z74                        | [84586c4db2](https://linux-hardware.org/?probe=84586c4db2) | Aug 27, 2020 |
| ASUSTek       | B85M-K                      | [9fd11c530f](https://linux-hardware.org/?probe=9fd11c530f) | Aug 21, 2020 |
| Gigabyte      | H170-Gaming 3               | [b4bad24684](https://linux-hardware.org/?probe=b4bad24684) | Aug 21, 2020 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [67cf1d26af](https://linux-hardware.org/?probe=67cf1d26af) | Aug 12, 2020 |
| Lenovo        | 0B98401 WIN                 | [20cb7c14f8](https://linux-hardware.org/?probe=20cb7c14f8) | Jul 10, 2020 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [e012c28e4a](https://linux-hardware.org/?probe=e012c28e4a) | Jul 06, 2020 |
| Gigabyte      | B75M-D3H                    | [925fdfd7c7](https://linux-hardware.org/?probe=925fdfd7c7) | Jun 16, 2020 |
| Dell          | 0RY206                      | [648bdee6ec](https://linux-hardware.org/?probe=648bdee6ec) | May 29, 2020 |
| Gigabyte      | G31M-ES2L                   | [9c2d3cb657](https://linux-hardware.org/?probe=9c2d3cb657) | May 24, 2020 |
| ASRock        | N68-GS4/USB3 FX             | [baefccea96](https://linux-hardware.org/?probe=baefccea96) | May 22, 2020 |
| Gigabyte      | B85M-D2V                    | [ec5da680aa](https://linux-hardware.org/?probe=ec5da680aa) | May 16, 2020 |
| Gigabyte      | B75M-D3H                    | [1069d9adc6](https://linux-hardware.org/?probe=1069d9adc6) | May 10, 2020 |
| Accton        | SAU5041                     | [b1efc2e064](https://linux-hardware.org/?probe=b1efc2e064) | May 07, 2020 |
| ASUSTek       | P8H77-V LE                  | [5ef719f7d8](https://linux-hardware.org/?probe=5ef719f7d8) | May 06, 2020 |
| Gigabyte      | B75M-D3H                    | [235c047618](https://linux-hardware.org/?probe=235c047618) | May 04, 2020 |
| ASUSTek       | P5Q                         | [c6681e044f](https://linux-hardware.org/?probe=c6681e044f) | May 02, 2020 |
| ASUSTek       | P5Q                         | [e620caac82](https://linux-hardware.org/?probe=e620caac82) | May 02, 2020 |
| Lenovo        | 0B98401 WIN                 | [e818900359](https://linux-hardware.org/?probe=e818900359) | May 01, 2020 |
| Lenovo        | 0B98401 WIN                 | [ef970e6611](https://linux-hardware.org/?probe=ef970e6611) | Apr 30, 2020 |
| Gigabyte      | H77M-D3H                    | [b34b605dda](https://linux-hardware.org/?probe=b34b605dda) | Apr 30, 2020 |
| Gigabyte      | B75M-D3H                    | [530e0b1725](https://linux-hardware.org/?probe=530e0b1725) | Apr 24, 2020 |
| MSI           | B450M MORTAR TITANIUM       | [a90f89123d](https://linux-hardware.org/?probe=a90f89123d) | Apr 20, 2020 |
| Accton        | SAU5041                     | [c23eb2c1bb](https://linux-hardware.org/?probe=c23eb2c1bb) | Apr 13, 2020 |
| Unknown       | Unknown                     | [c3983e6074](https://linux-hardware.org/?probe=c3983e6074) | Mar 31, 2020 |
| Unknown       | Unknown                     | [df51a87843](https://linux-hardware.org/?probe=df51a87843) | Mar 31, 2020 |
| MSI           | B450M MORTAR TITANIUM       | [5568d1765b](https://linux-hardware.org/?probe=5568d1765b) | Mar 30, 2020 |
| MSI           | MEG X299 CREATION           | [8112942b50](https://linux-hardware.org/?probe=8112942b50) | Mar 26, 2020 |
| Gigabyte      | Z77-D3H                     | [0a6d8786dc](https://linux-hardware.org/?probe=0a6d8786dc) | Mar 22, 2020 |
| Gigabyte      | Z77-D3H                     | [0b49d54fce](https://linux-hardware.org/?probe=0b49d54fce) | Mar 20, 2020 |
| ASUSTek       | D340MC-C                    | [e1396240d9](https://linux-hardware.org/?probe=e1396240d9) | Mar 19, 2020 |
| ASUSTek       | D840MB                      | [c2599225a3](https://linux-hardware.org/?probe=c2599225a3) | Mar 11, 2020 |
| Lenovo        | Board                       | [81650f1328](https://linux-hardware.org/?probe=81650f1328) | Mar 03, 2020 |
| MSI           | MEG X299 CREATION           | [dc2b1917fc](https://linux-hardware.org/?probe=dc2b1917fc) | Mar 02, 2020 |
| ASRock        | A300M-STX                   | [fed0334ebb](https://linux-hardware.org/?probe=fed0334ebb) | Feb 25, 2020 |
| Gigabyte      | B360 M AORUS PRO-CF         | [8b8bf9eb3c](https://linux-hardware.org/?probe=8b8bf9eb3c) | Feb 05, 2020 |
| Gigabyte      | Z68A-D3H-B3                 | [ec012fce91](https://linux-hardware.org/?probe=ec012fce91) | Jan 30, 2020 |
| ASUSTek       | M5A78L-M LE/USB3            | [871b431e0b](https://linux-hardware.org/?probe=871b431e0b) | Jan 23, 2020 |
| Gigabyte      | P55A-UD4                    | [0765c0e746](https://linux-hardware.org/?probe=0765c0e746) | Jan 23, 2020 |
| ASUSTek       | P8H61-M LX PLUS             | [e1061f8758](https://linux-hardware.org/?probe=e1061f8758) | Jan 17, 2020 |
| Dell          | 0TP412                      | [92059b060a](https://linux-hardware.org/?probe=92059b060a) | Jan 15, 2020 |
| ASUSTek       | Z87-PRO                     | [4c444b85d5](https://linux-hardware.org/?probe=4c444b85d5) | Jan 11, 2020 |
| Foxconn       | 2ADA                        | [161e031506](https://linux-hardware.org/?probe=161e031506) | Jan 11, 2020 |
| MSI           | K9N6PGM2-V2                 | [93e77f9dc3](https://linux-hardware.org/?probe=93e77f9dc3) | Dec 26, 2019 |
| MSI           | K9N6PGM2-V2                 | [7cac7cc3cc](https://linux-hardware.org/?probe=7cac7cc3cc) | Dec 26, 2019 |
| Foxconn       | 2ADA                        | [61f3387aaa](https://linux-hardware.org/?probe=61f3387aaa) | Dec 19, 2019 |
| Acer          | M1930                       | [6f798ab348](https://linux-hardware.org/?probe=6f798ab348) | Dec 16, 2019 |
| ASRock        | 960GC-GS FX                 | [3e7a8d31ef](https://linux-hardware.org/?probe=3e7a8d31ef) | Dec 03, 2019 |
| ASUSTek       | P8Z77-V LX                  | [9f10e816c5](https://linux-hardware.org/?probe=9f10e816c5) | Nov 21, 2019 |
| ASUSTek       | P8Z77-V LX                  | [ad60feb203](https://linux-hardware.org/?probe=ad60feb203) | Nov 21, 2019 |
| MSI           | P45 Platinum                | [178de664ca](https://linux-hardware.org/?probe=178de664ca) | Oct 28, 2019 |
| Lenovo        | ThinkCentre M58 7627AA9     | [4ca1d19d3a](https://linux-hardware.org/?probe=4ca1d19d3a) | Oct 18, 2019 |
| MSI           | K9N6PGM2-V2                 | [8dd08d1a97](https://linux-hardware.org/?probe=8dd08d1a97) | Oct 09, 2019 |
| ASUSTek       | M5A78L-M/USB3               | [0a39f948fd](https://linux-hardware.org/?probe=0a39f948fd) | Sep 29, 2019 |
| ASRock        | H81M-ITX                    | [ce10f2cbfe](https://linux-hardware.org/?probe=ce10f2cbfe) | Sep 26, 2019 |
| ASRock        | H81M-ITX                    | [aed359375a](https://linux-hardware.org/?probe=aed359375a) | Sep 26, 2019 |
| MSI           | X399 SLI PLUS               | [b281f9ca55](https://linux-hardware.org/?probe=b281f9ca55) | Sep 15, 2019 |
| MSI           | X399 SLI PLUS               | [130f51b891](https://linux-hardware.org/?probe=130f51b891) | Sep 11, 2019 |
| MSI           | X399 SLI PLUS               | [8da6642033](https://linux-hardware.org/?probe=8da6642033) | Sep 11, 2019 |
| ASRock        | H81M-VG4 R2.0               | [a6a357de21](https://linux-hardware.org/?probe=a6a357de21) | Aug 08, 2019 |
| Gigabyte      | EX58-UD3R                   | [f5c15b4975](https://linux-hardware.org/?probe=f5c15b4975) | Aug 01, 2019 |
| ASUSTek       | P7H55-M/USB3                | [517d2f4be4](https://linux-hardware.org/?probe=517d2f4be4) | Jul 31, 2019 |
| Gigabyte      | MZGLKCH-SI                  | [0f78f0b23e](https://linux-hardware.org/?probe=0f78f0b23e) | Jul 24, 2019 |
| Unknown       | Unknown                     | [55981af24a](https://linux-hardware.org/?probe=55981af24a) | Jul 17, 2019 |
| Unknown       | Unknown                     | [efe95ef406](https://linux-hardware.org/?probe=efe95ef406) | Jul 17, 2019 |
| Unknown       | Unknown                     | [e8900d6721](https://linux-hardware.org/?probe=e8900d6721) | Jul 15, 2019 |
| Acer          | Veriton M4630G V:1.0        | [087f924e20](https://linux-hardware.org/?probe=087f924e20) | Jul 15, 2019 |
| Unknown       | Unknown                     | [e58e143a7f](https://linux-hardware.org/?probe=e58e143a7f) | Jul 15, 2019 |
| Acer          | Veriton M4630G V:1.0        | [683b87be0f](https://linux-hardware.org/?probe=683b87be0f) | Jul 15, 2019 |
| Acer          | Veriton M4630G V:1.0        | [43db5dc346](https://linux-hardware.org/?probe=43db5dc346) | Jul 15, 2019 |
| Unknown       | Unknown                     | [4124a2b6aa](https://linux-hardware.org/?probe=4124a2b6aa) | Jul 12, 2019 |
| ASUSTek       | Z170-DELUXE                 | [093c4071fd](https://linux-hardware.org/?probe=093c4071fd) | Jul 10, 2019 |
| Unknown       | Unknown                     | [25b6099cd2](https://linux-hardware.org/?probe=25b6099cd2) | Jul 09, 2019 |
| Unknown       | Unknown                     | [c9ae4d965c](https://linux-hardware.org/?probe=c9ae4d965c) | Jul 09, 2019 |
| Unknown       | Unknown                     | [1e3ba128f6](https://linux-hardware.org/?probe=1e3ba128f6) | Jul 08, 2019 |
| ASUSTek       | M5A78L-M LE/USB3            | [44650751a9](https://linux-hardware.org/?probe=44650751a9) | Jul 04, 2019 |
| Gigabyte      | B450M GAMING                | [154fbbffd3](https://linux-hardware.org/?probe=154fbbffd3) | Jul 04, 2019 |
| Gigabyte      | G1.Sniper Z97               | [7552a8cb4c](https://linux-hardware.org/?probe=7552a8cb4c) | Jun 20, 2019 |
| Gigabyte      | GA-M56S-S3                  | [21fb8f59a4](https://linux-hardware.org/?probe=21fb8f59a4) | Jun 07, 2019 |
| Gigabyte      | Z370P D3-CF                 | [a210ba04d3](https://linux-hardware.org/?probe=a210ba04d3) | Jun 04, 2019 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [d2e0085e5f](https://linux-hardware.org/?probe=d2e0085e5f) | Jun 04, 2019 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [f96a5f5393](https://linux-hardware.org/?probe=f96a5f5393) | Jun 04, 2019 |
| ASUSTek       | WS X299 PRO                 | [510ae49df2](https://linux-hardware.org/?probe=510ae49df2) | May 22, 2019 |
| Acer          | Veriton M6620G v1.0         | [4f1a9afa27](https://linux-hardware.org/?probe=4f1a9afa27) | May 21, 2019 |
| Gigabyte      | Z170M-HERO-CF               | [0d7f7b5382](https://linux-hardware.org/?probe=0d7f7b5382) | Apr 28, 2019 |
| Acer          | Veriton M6620G v1.0         | [d5403368f6](https://linux-hardware.org/?probe=d5403368f6) | Apr 28, 2019 |
| Acer          | Veriton M6620G v1.0         | [1c42aae9b4](https://linux-hardware.org/?probe=1c42aae9b4) | Apr 27, 2019 |
| Gigabyte      | G41M-Combo                  | [f70f72098a](https://linux-hardware.org/?probe=f70f72098a) | Apr 21, 2019 |
| ASRock        | 960GC-GS FX                 | [2ab4402059](https://linux-hardware.org/?probe=2ab4402059) | Apr 13, 2019 |
| MSI           | Z68MA-G45                   | [c3e718dfec](https://linux-hardware.org/?probe=c3e718dfec) | Apr 09, 2019 |
| HP            | ProLiant ML150 Gen9         | [d9b1ec3c37](https://linux-hardware.org/?probe=d9b1ec3c37) | Apr 09, 2019 |
| HP            | ProLiant ML150 Gen9         | [d61584bf4e](https://linux-hardware.org/?probe=d61584bf4e) | Apr 09, 2019 |
| ASRock        | 960GC-GS FX                 | [925ee04320](https://linux-hardware.org/?probe=925ee04320) | Apr 07, 2019 |
| ASUSTek       | BM1AF_BP1AF_BM6AF           | [dcf80c3fe6](https://linux-hardware.org/?probe=dcf80c3fe6) | Apr 03, 2019 |
| Gigabyte      | F2A88X-D3H                  | [d9a29354a7](https://linux-hardware.org/?probe=d9a29354a7) | Feb 19, 2019 |
| Gigabyte      | F2A88X-D3H                  | [a3a29982fd](https://linux-hardware.org/?probe=a3a29982fd) | Feb 19, 2019 |
| ASRock        | H310M-ITX/ac                | [0ae0ba17de](https://linux-hardware.org/?probe=0ae0ba17de) | Feb 02, 2019 |
| Gigabyte      | H87M-D3H                    | [dd3cc86ec3](https://linux-hardware.org/?probe=dd3cc86ec3) | Jan 29, 2019 |
| ASRock        | H310M-ITX/ac                | [899220711e](https://linux-hardware.org/?probe=899220711e) | Jan 25, 2019 |
| Gigabyte      | H87M-D3H                    | [90a29cddfa](https://linux-hardware.org/?probe=90a29cddfa) | Dec 21, 2018 |
| ASRock        | H310M-STX/COM               | [d350550408](https://linux-hardware.org/?probe=d350550408) | Dec 07, 2018 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [3eaee61f5f](https://linux-hardware.org/?probe=3eaee61f5f) | Nov 29, 2018 |
| Gigabyte      | H310 D3                     | [eb95ee1f27](https://linux-hardware.org/?probe=eb95ee1f27) | Nov 20, 2018 |
| MSI           | FM2-A75MA-E35               | [d4730289c0](https://linux-hardware.org/?probe=d4730289c0) | Nov 12, 2018 |
| ASUSTek       | P8H67                       | [821e6f68ce](https://linux-hardware.org/?probe=821e6f68ce) | Sep 17, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 18.04       | 50       | 16.13%  |
| Ubuntu 20.04       | 38       | 12.26%  |
| Ubuntu 22.04       | 24       | 7.74%   |
| Debian 11          | 10       | 3.23%   |
| Arch Rolling       | 10       | 3.23%   |
| OpenMandriva 4.2   | 9        | 2.9%    |
| Linux Mint 20.3    | 7        | 2.26%   |
| OpenMandriva 23.01 | 6        | 1.94%   |
| Xubuntu 20.04      | 5        | 1.61%   |
| Xubuntu 18.04      | 5        | 1.61%   |
| OpenMandriva 4.3   | 5        | 1.61%   |
| OpenMandriva 23.03 | 5        | 1.61%   |
| Fedora 39          | 5        | 1.61%   |
| Pop!_OS 20.04      | 4        | 1.29%   |
| Fedora 38          | 4        | 1.29%   |
| Fedora 37          | 4        | 1.29%   |
| Debian 12          | 4        | 1.29%   |
| Ubuntu 21.10       | 3        | 0.97%   |
| Ubuntu 19.04       | 3        | 0.97%   |
| Kubuntu 20.04      | 3        | 0.97%   |
| Zorin 16           | 2        | 0.65%   |
| Ubuntu 23.10       | 2        | 0.65%   |
| Ubuntu 23.04       | 2        | 0.65%   |
| Ubuntu 22.10       | 2        | 0.65%   |
| Ubuntu 20.10       | 2        | 0.65%   |
| Ubuntu 19.10       | 2        | 0.65%   |
| Ubuntu 18.10       | 2        | 0.65%   |
| Ubuntu 16.04       | 2        | 0.65%   |
| ROSA R11           | 2        | 0.65%   |
| openSUSE Leap-15.0 | 2        | 0.65%   |
| OpenMandriva 4.90  | 2        | 0.65%   |
| OpenMandriva 24.01 | 2        | 0.65%   |
| OpenMandriva 23.11 | 2        | 0.65%   |
| OpenMandriva 23.10 | 2        | 0.65%   |
| OpenMandriva 23.08 | 2        | 0.65%   |
| Manjaro 23.0.0     | 2        | 0.65%   |
| Linux Mint 21.2    | 2        | 0.65%   |
| Linux Mint 20.2    | 2        | 0.65%   |
| KDE neon 20.04     | 2        | 0.65%   |
| Kali 2023.3        | 2        | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 130      | 43.62%  |
| OpenMandriva  | 30       | 10.07%  |
| Fedora        | 19       | 6.38%   |
| Debian        | 17       | 5.7%    |
| Linux Mint    | 16       | 5.37%   |
| Xubuntu       | 13       | 4.36%   |
| Arch          | 11       | 3.69%   |
| Manjaro       | 8        | 2.68%   |
| Pop!_OS       | 6        | 2.01%   |
| Kubuntu       | 5        | 1.68%   |
| Kali          | 5        | 1.68%   |
| Endless       | 4        | 1.34%   |
| Zorin         | 3        | 1.01%   |
| Ubuntu MATE   | 3        | 1.01%   |
| ROSA          | 3        | 1.01%   |
| openSUSE      | 3        | 1.01%   |
| Gentoo        | 3        | 1.01%   |
| NixOS         | 2        | 0.67%   |
| Lubuntu       | 2        | 0.67%   |
| KDE neon      | 2        | 0.67%   |
| Clear Linux   | 2        | 0.67%   |
| CentOS        | 2        | 0.67%   |
| Ubuntu Unity  | 1        | 0.34%   |
| Ubuntu Budgie | 1        | 0.34%   |
| OpenEuler     | 1        | 0.34%   |
| Mageia        | 1        | 0.34%   |
| Lilidog       | 1        | 0.34%   |
| Garuda Linux  | 1        | 0.34%   |
| EndeavourOS   | 1        | 0.34%   |
| BlackPanther  | 1        | 0.34%   |
| ArcoLinux     | 1        | 0.34%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.14-desktop-1omv4002 | 7        | 2.08%   |
| 6.1.1-desktop-1omv2290   | 6        | 1.78%   |
| 6.6.2-desktop-1omv2390   | 5        | 1.48%   |
| 5.4.0-42-generic         | 5        | 1.48%   |
| 5.16.7-desktop-1omv4003  | 5        | 1.48%   |
| 6.2.6-desktop-1omv2390   | 4        | 1.19%   |
| 5.8.0-50-generic         | 4        | 1.19%   |
| 5.4.0-45-generic         | 4        | 1.19%   |
| 5.4.0-28-generic         | 4        | 1.19%   |
| 6.5.0-27-generic         | 3        | 0.89%   |
| 5.4.0-58-generic         | 3        | 0.89%   |
| 5.19.0-46-generic        | 3        | 0.89%   |
| 5.11.0-27-generic        | 3        | 0.89%   |
| 5.0.0-37-generic         | 3        | 0.89%   |
| 5.0.0-23-generic         | 3        | 0.89%   |
| 4.15.0-66-generic        | 3        | 0.89%   |
| 4.15.0-29-generic        | 3        | 0.89%   |
| 6.5.5-desktop-1omv2390   | 2        | 0.59%   |
| 6.4.11-desktop-1omv2390  | 2        | 0.59%   |
| 6.2.0-35-generic         | 2        | 0.59%   |
| 5.8.0-55-generic         | 2        | 0.59%   |
| 5.8.0-43-generic         | 2        | 0.59%   |
| 5.8.0-38-generic         | 2        | 0.59%   |
| 5.5.0-kali2-amd64        | 2        | 0.59%   |
| 5.4.0-81-generic         | 2        | 0.59%   |
| 5.4.0-80-generic         | 2        | 0.59%   |
| 5.4.0-77-generic         | 2        | 0.59%   |
| 5.4.0-66-generic         | 2        | 0.59%   |
| 5.4.0-54-generic         | 2        | 0.59%   |
| 5.4.0-53-generic         | 2        | 0.59%   |
| 5.4.0-48-generic         | 2        | 0.59%   |
| 5.4.0-122-generic        | 2        | 0.59%   |
| 5.3.0-40-generic         | 2        | 0.59%   |
| 5.3.0-28-generic         | 2        | 0.59%   |
| 5.19.0-38-generic        | 2        | 0.59%   |
| 5.18.12-desktop-3omv4090 | 2        | 0.59%   |
| 5.15.83-1-pve            | 2        | 0.59%   |
| 5.15.0-91-generic        | 2        | 0.59%   |
| 5.15.0-53-generic        | 2        | 0.59%   |
| 5.15.0-52-generic        | 2        | 0.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 54       | 17.03%  |
| 4.15.0  | 27       | 8.52%   |
| 5.15.0  | 18       | 5.68%   |
| 5.8.0   | 13       | 4.1%    |
| 6.5.0   | 11       | 3.47%   |
| 5.11.0  | 11       | 3.47%   |
| 5.0.0   | 11       | 3.47%   |
| 4.18.0  | 10       | 3.15%   |
| 6.2.0   | 9        | 2.84%   |
| 5.3.0   | 9        | 2.84%   |
| 5.19.0  | 9        | 2.84%   |
| 5.13.0  | 8        | 2.52%   |
| 5.10.14 | 7        | 2.21%   |
| 6.6.2   | 6        | 1.89%   |
| 6.1.1   | 6        | 1.89%   |
| 6.1.0   | 5        | 1.58%   |
| 5.16.7  | 5        | 1.58%   |
| 5.10.0  | 5        | 1.58%   |
| 6.2.6   | 4        | 1.26%   |
| 6.5.5   | 2        | 0.63%   |
| 6.4.11  | 2        | 0.63%   |
| 6.4.0   | 2        | 0.63%   |
| 6.2.2   | 2        | 0.63%   |
| 6.2.12  | 2        | 0.63%   |
| 5.5.0   | 2        | 0.63%   |
| 5.18.12 | 2        | 0.63%   |
| 5.15.83 | 2        | 0.63%   |
| 5.15.23 | 2        | 0.63%   |
| 5.11.12 | 2        | 0.63%   |
| 4.19.57 | 2        | 0.63%   |
| 4.19.0  | 2        | 0.63%   |
| 4.12.14 | 2        | 0.63%   |
| 6.7.9   | 1        | 0.32%   |
| 6.7.10  | 1        | 0.32%   |
| 6.6.9   | 1        | 0.32%   |
| 6.6.8   | 1        | 0.32%   |
| 6.6.7   | 1        | 0.32%   |
| 6.6.22  | 1        | 0.32%   |
| 6.6.1   | 1        | 0.32%   |
| 6.5.9   | 1        | 0.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 54       | 17.14%  |
| 5.15    | 27       | 8.57%   |
| 4.15    | 27       | 8.57%   |
| 6.2     | 21       | 6.67%   |
| 6.5     | 19       | 6.03%   |
| 5.10    | 17       | 5.4%    |
| 5.8     | 15       | 4.76%   |
| 6.1     | 14       | 4.44%   |
| 5.11    | 14       | 4.44%   |
| 5.0     | 12       | 3.81%   |
| 6.6     | 11       | 3.49%   |
| 4.18    | 11       | 3.49%   |
| 5.19    | 10       | 3.17%   |
| 5.3     | 9        | 2.86%   |
| 5.13    | 8        | 2.54%   |
| 5.16    | 7        | 2.22%   |
| 6.0     | 6        | 1.9%    |
| 6.4     | 5        | 1.59%   |
| 6.3     | 4        | 1.27%   |
| 4.19    | 4        | 1.27%   |
| 5.5     | 3        | 0.95%   |
| 5.18    | 3        | 0.95%   |
| 6.7     | 2        | 0.63%   |
| 4.12    | 2        | 0.63%   |
| 5.9     | 1        | 0.32%   |
| 5.7     | 1        | 0.32%   |
| 5.17    | 1        | 0.32%   |
| 5.14    | 1        | 0.32%   |
| 5.12    | 1        | 0.32%   |
| 5.1     | 1        | 0.32%   |
| 4.9     | 1        | 0.32%   |
| 4.4     | 1        | 0.32%   |
| 4.14    | 1        | 0.32%   |
| 3.10    | 1        | 0.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 287      | 97.62%  |
| i686    | 6        | 2.04%   |
| riscv64 | 1        | 0.34%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| GNOME            | 137      | 45.67%  |
| Unknown          | 54       | 18%     |
| KDE5             | 50       | 16.67%  |
| XFCE             | 19       | 6.33%   |
| X-Cinnamon       | 8        | 2.67%   |
| LXQt             | 6        | 2%      |
| Cinnamon         | 6        | 2%      |
| MATE             | 5        | 1.67%   |
| KDE              | 4        | 1.33%   |
| LXDE             | 2        | 0.67%   |
| Hyprland         | 2        | 0.67%   |
| Unity            | 1        | 0.33%   |
| lightdm-xsession | 1        | 0.33%   |
| KDE4             | 1        | 0.33%   |
| i3               | 1        | 0.33%   |
| GNOME Classic    | 1        | 0.33%   |
| Deepin           | 1        | 0.33%   |
| Budgie           | 1        | 0.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 208      | 67.31%  |
| Wayland | 62       | 20.06%  |
| Unknown | 29       | 9.39%   |
| Tty     | 10       | 3.24%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 133      | 44.33%  |
| SDDM    | 50       | 16.67%  |
| GDM     | 48       | 16%     |
| GDM3    | 40       | 13.33%  |
| LightDM | 19       | 6.33%   |
| TDM     | 8        | 2.67%   |
| KDM     | 2        | 0.67%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 122      | 40.53%  |
| zh_TW      | 107      | 35.55%  |
| Unknown    | 48       | 15.95%  |
| C          | 7        | 2.33%   |
| zh_CN      | 4        | 1.33%   |
| zh_HK      | 2        | 0.66%   |
| en_HK      | 2        | 0.66%   |
| en_GB      | 2        | 0.66%   |
| lzh_TW     | 1        | 0.33%   |
| it_IT      | 1        | 0.33%   |
| es_ES      | 1        | 0.33%   |
| en_US.UTF8 | 1        | 0.33%   |
| en_SG      | 1        | 0.33%   |
| en_PH      | 1        | 0.33%   |
| en_AU      | 1        | 0.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 163      | 54.15%  |
| BIOS | 138      | 45.85%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 204      | 68.23%  |
| Btrfs   | 33       | 11.04%  |
| Overlay | 21       | 7.02%   |
| Tmpfs   | 15       | 5.02%   |
| Xfs     | 14       | 4.68%   |
| Unknown | 7        | 2.34%   |
| Ext2    | 3        | 1%      |
| Rootfs  | 1        | 0.33%   |
| Ext3    | 1        | 0.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 150      | 50%     |
| Unknown | 124      | 41.33%  |
| MBR     | 26       | 8.67%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 229      | 76.59%  |
| Yes       | 70       | 23.41%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 171      | 56.62%  |
| Yes       | 131      | 43.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 93       | 31.63%  |
| Gigabyte Technology | 68       | 23.13%  |
| MSI                 | 26       | 8.84%   |
| ASRock              | 23       | 7.82%   |
| Acer                | 17       | 5.78%   |
| Dell                | 11       | 3.74%   |
| Hewlett-Packard     | 10       | 3.4%    |
| Unknown             | 10       | 3.4%    |
| Lenovo              | 8        | 2.72%   |
| Intel               | 3        | 1.02%   |
| JGINYUE             | 2        | 0.68%   |
| Huanan              | 2        | 0.68%   |
| EBN                 | 2        | 0.68%   |
| Win element         | 1        | 0.34%   |
| Supermicro          | 1        | 0.34%   |
| Ruckus Wireless     | 1        | 0.34%   |
| PANSHI              | 1        | 0.34%   |
| ONDA                | 1        | 0.34%   |
| OEM                 | 1        | 0.34%   |
| NEXCOM              | 1        | 0.34%   |
| Maxtang             | 1        | 0.34%   |
| Foxconn             | 1        | 0.34%   |
| eMachines           | 1        | 0.34%   |
| DNI                 | 1        | 0.34%   |
| DFI                 | 1        | 0.34%   |
| Centerm             | 1        | 0.34%   |
| BESSTAR Tech        | 1        | 0.34%   |
| ASRockRack          | 1        | 0.34%   |
| Apple               | 1        | 0.34%   |
| Altos               | 1        | 0.34%   |
| Accton              | 1        | 0.34%   |
| AAEON               | 1        | 0.34%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown                        | 10       | 3.4%    |
| ASUS All Series                | 7        | 2.38%   |
| Gigabyte B75M-D3H              | 4        | 1.36%   |
| Gigabyte B550I AORUS PRO AX    | 4        | 1.36%   |
| ASUS M5A78L-M/USB3             | 4        | 1.36%   |
| ASRock X300M-STX               | 4        | 1.36%   |
| Lenovo ThinkCentre M58 7627AA9 | 3        | 1.02%   |
| Dell Inspiron 531s             | 3        | 1.02%   |
| ASUS TUF Gaming B550M-PLUS     | 3        | 1.02%   |
| ASUS Pro WS X570-ACE           | 3        | 1.02%   |
| ASUS CM6630_CM6730_CM6830      | 3        | 1.02%   |
| Acer Veriton L480              | 3        | 1.02%   |
| MSI MS-7C52                    | 2        | 0.68%   |
| MSI MS-7A69                    | 2        | 0.68%   |
| Gigabyte Z97MX-Gaming 5        | 2        | 0.68%   |
| Gigabyte H81N                  | 2        | 0.68%   |
| Gigabyte G31M-ES2L             | 2        | 0.68%   |
| Gigabyte B85M-D2V              | 2        | 0.68%   |
| ASUS ROG STRIX B350-F GAMING   | 2        | 0.68%   |
| ASUS PRIME B660M-A WIFI D4     | 2        | 0.68%   |
| ASUS P8Z77-V LX                | 2        | 0.68%   |
| ASRock N68-GS4/USB3 FX         | 2        | 0.68%   |
| ASRock H310M-ITX/ac            | 2        | 0.68%   |
| ASRock A300M-STX               | 2        | 0.68%   |
| ASRock 960GC-GS FX             | 2        | 0.68%   |
| Win element M600               | 1        | 0.34%   |
| Supermicro C9Z490-PGW          | 1        | 0.34%   |
| Ruckus Wireless SCG-100        | 1        | 0.34%   |
| PANSHI B85-S1 V1.0             | 1        | 0.34%   |
| ONDA H110CD3                   | 1        | 0.34%   |
| OEM B85 JHS359                 | 1        | 0.34%   |
| NEXCOM SKLD4-P1                | 1        | 0.34%   |
| MSI PRO ADL-U Cubi 5 (MS-B0A8) | 1        | 0.34%   |
| MSI MS-7D69                    | 1        | 0.34%   |
| MSI MS-7D25                    | 1        | 0.34%   |
| MSI MS-7D19                    | 1        | 0.34%   |
| MSI MS-7D08                    | 1        | 0.34%   |
| MSI MS-7C95                    | 1        | 0.34%   |
| MSI MS-7C06                    | 1        | 0.34%   |
| MSI MS-7B89                    | 1        | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS TUF              | 12       | 4.08%   |
| ASUS ROG              | 12       | 4.08%   |
| ASUS PRIME            | 11       | 3.74%   |
| Unknown               | 10       | 3.4%    |
| Acer Aspire           | 8        | 2.72%   |
| ASUS All              | 7        | 2.38%   |
| ASUS M5A78L-M         | 6        | 2.04%   |
| Acer Veriton          | 6        | 2.04%   |
| Dell Inspiron         | 5        | 1.7%    |
| ASUS Pro              | 5        | 1.7%    |
| Gigabyte B75M-D3H     | 4        | 1.36%   |
| Gigabyte B550I        | 4        | 1.36%   |
| ASRock X300M-STX      | 4        | 1.36%   |
| Lenovo ThinkCentre    | 3        | 1.02%   |
| Dell OptiPlex         | 3        | 1.02%   |
| ASUS P8Z77-V          | 3        | 1.02%   |
| ASUS CM6630           | 3        | 1.02%   |
| MSI MS-7C52           | 2        | 0.68%   |
| MSI MS-7A69           | 2        | 0.68%   |
| Lenovo IdeaCentre     | 2        | 0.68%   |
| HP Z240               | 2        | 0.68%   |
| HP ProDesk            | 2        | 0.68%   |
| Gigabyte Z97MX-Gaming | 2        | 0.68%   |
| Gigabyte X570S        | 2        | 0.68%   |
| Gigabyte H81N         | 2        | 0.68%   |
| Gigabyte G31M-ES2L    | 2        | 0.68%   |
| Gigabyte G1.Sniper    | 2        | 0.68%   |
| Gigabyte B85M-D2V     | 2        | 0.68%   |
| Gigabyte B550M        | 2        | 0.68%   |
| Gigabyte B360         | 2        | 0.68%   |
| Dell Precision        | 2        | 0.68%   |
| ASUS WS               | 2        | 0.68%   |
| ASUS P8H61-M          | 2        | 0.68%   |
| ASUS ASUSPRO          | 2        | 0.68%   |
| ASRock N68-GS4        | 2        | 0.68%   |
| ASRock H310M-ITX      | 2        | 0.68%   |
| ASRock A300M-STX      | 2        | 0.68%   |
| ASRock 960GC-GS       | 2        | 0.68%   |
| Win element M600      | 1        | 0.34%   |
| Supermicro C9Z490-PGW | 1        | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2020    | 37       | 12.59%  |
| 2018    | 30       | 10.2%   |
| 2021    | 24       | 8.16%   |
| 2013    | 24       | 8.16%   |
| 2012    | 24       | 8.16%   |
| 2014    | 23       | 7.82%   |
| 2022    | 22       | 7.48%   |
| 2011    | 17       | 5.78%   |
| 2009    | 15       | 5.1%    |
| 2016    | 13       | 4.42%   |
| 2019    | 12       | 4.08%   |
| 2017    | 12       | 4.08%   |
| 2015    | 11       | 3.74%   |
| 2008    | 10       | 3.4%    |
| 2010    | 8        | 2.72%   |
| 2023    | 6        | 2.04%   |
| 2007    | 4        | 1.36%   |
| 2024    | 1        | 0.34%   |
| Unknown | 1        | 0.34%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 294      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 285      | 96.61%  |
| Enabled  | 10       | 3.39%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 294      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 68       | 22.74%  |
| 32.01-64.0      | 56       | 18.73%  |
| 4.01-8.0        | 44       | 14.72%  |
| 3.01-4.0        | 44       | 14.72%  |
| 8.01-16.0       | 44       | 14.72%  |
| 64.01-256.0     | 25       | 8.36%   |
| 24.01-32.0      | 10       | 3.34%   |
| 1.01-2.0        | 6        | 2.01%   |
| More than 256.0 | 2        | 0.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 112      | 34.57%  |
| 2.01-3.0   | 74       | 22.84%  |
| 4.01-8.0   | 50       | 15.43%  |
| 3.01-4.0   | 45       | 13.89%  |
| 8.01-16.0  | 19       | 5.86%   |
| 0.51-1.0   | 11       | 3.4%    |
| 0.01-0.5   | 4        | 1.23%   |
| 32.01-64.0 | 3        | 0.93%   |
| 24.01-32.0 | 3        | 0.93%   |
| 16.01-24.0 | 3        | 0.93%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 116      | 38.41%  |
| 2      | 92       | 30.46%  |
| 3      | 47       | 15.56%  |
| 4      | 20       | 6.62%   |
| 5      | 12       | 3.97%   |
| 0      | 7        | 2.32%   |
| 6      | 4        | 1.32%   |
| 7      | 2        | 0.66%   |
| 14     | 1        | 0.33%   |
| 9      | 1        | 0.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 206      | 69.59%  |
| Yes       | 90       | 30.41%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 292      | 99.32%  |
| No        | 2        | 0.68%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 163      | 54.7%   |
| Yes       | 135      | 45.3%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 194      | 64.45%  |
| Yes       | 107      | 35.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Taiwan  | 294      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Taipei            | 86       | 28.2%   |
| New Taipei        | 58       | 19.02%  |
| Taichung          | 26       | 8.52%   |
| Hsinchu           | 26       | 8.52%   |
| Taoyuan District  | 22       | 7.21%   |
| Kaohsiung City    | 19       | 6.23%   |
| Tainan City       | 15       | 4.92%   |
| Hsinchu County    | 6        | 1.97%   |
| Chang-hua         | 5        | 1.64%   |
| Keelung           | 4        | 1.31%   |
| Miaoli            | 3        | 0.98%   |
| Zhudong           | 2        | 0.66%   |
| Yilan             | 2        | 0.66%   |
| Nantou City       | 2        | 0.66%   |
| Kanzijiao         | 2        | 0.66%   |
| Chiayi City       | 2        | 0.66%   |
| Baitang           | 2        | 0.66%   |
| Zhongli District  | 1        | 0.33%   |
| Yangmei District  | 1        | 0.33%   |
| Xinzhuang         | 1        | 0.33%   |
| Xindian           | 1        | 0.33%   |
| Xiatayou          | 1        | 0.33%   |
| Taoyuan City      | 1        | 0.33%   |
| Taitung           | 1        | 0.33%   |
| Taishan           | 1        | 0.33%   |
| Taichung City     | 1        | 0.33%   |
| Sanchong District | 1        | 0.33%   |
| Neihu District    | 1        | 0.33%   |
| Magong            | 1        | 0.33%   |
| Longtan District  | 1        | 0.33%   |
| Hualien City      | 1        | 0.33%   |
| Fongshan District | 1        | 0.33%   |
| Dawan             | 1        | 0.33%   |
| Daan              | 1        | 0.33%   |
| Chongde           | 1        | 0.33%   |
| Chiayi            | 1        | 0.33%   |
| Beimiao           | 1        | 0.33%   |
| Banqiao           | 1        | 0.33%   |
| Baiyu             | 1        | 0.33%   |
| Aquan             | 1        | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 84       | 142    | 15.38%  |
| WDC                         | 82       | 125    | 15.02%  |
| Toshiba                     | 46       | 63     | 8.42%   |
| Crucial                     | 35       | 44     | 6.41%   |
| Intel                       | 27       | 39     | 4.95%   |
| Hitachi                     | 23       | 27     | 4.21%   |
| A-DATA Technology           | 21       | 24     | 3.85%   |
| Samsung Electronics         | 20       | 24     | 3.66%   |
| Kingston                    | 18       | 23     | 3.3%    |
| Transcend                   | 15       | 16     | 2.75%   |
| Unknown                     | 14       | 18     | 2.56%   |
| SanDisk                     | 14       | 21     | 2.56%   |
| Apacer                      | 9        | 12     | 1.65%   |
| Plextor                     | 7        | 8      | 1.28%   |
| Micron/Crucial Technology   | 7        | 10     | 1.28%   |
| ANACOMDA                    | 7        | 10     | 1.28%   |
| SPCC                        | 6        | 7      | 1.1%    |
| Silicon Motion              | 6        | 6      | 1.1%    |
| Micron Technology           | 5        | 5      | 0.92%   |
| PNY                         | 4        | 7      | 0.73%   |
| Phison Electronics          | 4        | 5      | 0.73%   |
| Patriot                     | 4        | 4      | 0.73%   |
| Lite-On                     | 4        | 4      | 0.73%   |
| KLEVV                       | 4        | 6      | 0.73%   |
| ADATA Technology            | 4        | 6      | 0.73%   |
| Unknown                     | 4        | 4      | 0.73%   |
| XPG                         | 3        | 4      | 0.55%   |
| Team                        | 3        | 4      | 0.55%   |
| SK hynix                    | 3        | 3      | 0.55%   |
| Phison                      | 3        | 4      | 0.55%   |
| Maxtor                      | 3        | 3      | 0.55%   |
| MAXIO Technology (Hangzhou) | 3        | 3      | 0.55%   |
| KIOXIA                      | 3        | 3      | 0.55%   |
| HGST                        | 3        | 5      | 0.55%   |
| Fujitsu                     | 3        | 4      | 0.55%   |
| China                       | 3        | 3      | 0.55%   |
| TOPMORE                     | 2        | 2      | 0.37%   |
| OCZ                         | 2        | 2      | 0.37%   |
| Leven                       | 2        | 2      | 0.37%   |
| Kingston Technology Company | 2        | 3      | 0.37%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB                                          | 15       | 2.51%   |
| Toshiba DT01ACA200 2TB                                          | 12       | 2.01%   |
| Crucial CT500MX500SSD1 500GB                                    | 12       | 2.01%   |
| Seagate ST2000DM008-2FR102 2TB                                  | 8        | 1.34%   |
| Crucial CT1000MX500SSD1 1TB                                     | 8        | 1.34%   |
| Seagate ST500DM002-1BD142 500GB                                 | 6        | 1%      |
| Seagate ST3500418AS 500GB                                       | 6        | 1%      |
| Toshiba MQ01ABD032 320GB                                        | 5        | 0.84%   |
| WDC WDS250G1B0B-00AS40 250GB SSD                                | 4        | 0.67%   |
| WDC WDS100T2B0C-00PXH0 1TB                                      | 4        | 0.67%   |
| WDC WD10EZEX-75WN4A1 1TB                                        | 4        | 0.67%   |
| Seagate ST2000DM001-1CH164 2TB                                  | 4        | 0.67%   |
| Seagate ST1000DM010-2EP102 1TB                                  | 4        | 0.67%   |
| Seagate ST1000DM003-1SB102 1TB                                  | 4        | 0.67%   |
| Seagate ST1000DM003-1ER162 1TB                                  | 4        | 0.67%   |
| SanDisk NVMe SSD Drive 500GB                                    | 4        | 0.67%   |
| Patriot Burst 120GB SSD                                         | 4        | 0.67%   |
| Kingston SA400S37480G 480GB SSD                                 | 4        | 0.67%   |
| Hitachi HDT721010SLA360 1TB                                     | 4        | 0.67%   |
| A-DATA SU800 512GB SSD                                          | 4        | 0.67%   |
| A-DATA SU800 256GB SSD                                          | 4        | 0.67%   |
| Unknown                                                         | 4        | 0.67%   |
| WDC WD6402AAEX-00Z3A0 640GB                                     | 3        | 0.5%    |
| WDC WD3200AAKS-00L9A0 320GB                                     | 3        | 0.5%    |
| WDC WD1600AAJS-08L7A0 160GB                                     | 3        | 0.5%    |
| WDC WD10EZEX-08WN4A0 1TB                                        | 3        | 0.5%    |
| Unknown SD/MMC/MS PRO 128GB                                     | 3        | 0.5%    |
| Unknown 004G60  4GB                                             | 3        | 0.5%    |
| Silicon Motion NVMe SSD Drive 512GB                             | 3        | 0.5%    |
| Seagate ST750LX003-1AC154 752GB                                 | 3        | 0.5%    |
| Seagate ST3320613AS 320GB                                       | 3        | 0.5%    |
| SanDisk NVMe SSD Drive 1TB                                      | 3        | 0.5%    |
| PNY CS3030 2TB SSD                                              | 3        | 0.5%    |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                             | 3        | 0.5%    |
| Micron/Crucial NVMe SSD Drive 1TB                               | 3        | 0.5%    |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 256GB              | 3        | 0.5%    |
| Apacer AS2280P4 256GB                                           | 3        | 0.5%    |
| Apacer 256GB SATA Flash Drive SSD                               | 3        | 0.5%    |
| ANACOMDA TT 256GB SSD                                           | 3        | 0.5%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 1TB | 3        | 0.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 83       | 139    | 36.89%  |
| WDC                 | 62       | 95     | 27.56%  |
| Toshiba             | 44       | 61     | 19.56%  |
| Hitachi             | 23       | 27     | 10.22%  |
| Unknown             | 4        | 5      | 1.78%   |
| Maxtor              | 3        | 3      | 1.33%   |
| HGST                | 3        | 5      | 1.33%   |
| Samsung Electronics | 2        | 3      | 0.89%   |
| Fujitsu             | 1        | 2      | 0.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Crucial             | 33       | 41     | 18.03%  |
| A-DATA Technology   | 17       | 20     | 9.29%   |
| Intel               | 15       | 22     | 8.2%    |
| Transcend           | 14       | 15     | 7.65%   |
| WDC                 | 12       | 17     | 6.56%   |
| Kingston            | 11       | 13     | 6.01%   |
| ANACOMDA            | 7        | 10     | 3.83%   |
| Plextor             | 6        | 7      | 3.28%   |
| Apacer              | 6        | 8      | 3.28%   |
| SPCC                | 5        | 6      | 2.73%   |
| SanDisk             | 5        | 6      | 2.73%   |
| Samsung Electronics | 5        | 5      | 2.73%   |
| Patriot             | 4        | 4      | 2.19%   |
| KLEVV               | 4        | 6      | 2.19%   |
| Micron Technology   | 3        | 3      | 1.64%   |
| China               | 3        | 3      | 1.64%   |
| Toshiba             | 2        | 2      | 1.09%   |
| Team                | 2        | 3      | 1.09%   |
| OCZ                 | 2        | 2      | 1.09%   |
| Leven               | 2        | 2      | 1.09%   |
| Gigastone           | 2        | 2      | 1.09%   |
| Fujitsu             | 2        | 2      | 1.09%   |
| ASMT                | 2        | 2      | 1.09%   |
| ZHITAI              | 1        | 1      | 0.55%   |
| Wintec              | 1        | 1      | 0.55%   |
| Unknown             | 1        | 1      | 0.55%   |
| T-FORCE             | 1        | 1      | 0.55%   |
| Sony                | 1        | 1      | 0.55%   |
| SCY                 | 1        | 1      | 0.55%   |
| Pioneer             | 1        | 1      | 0.55%   |
| OCZ-VECT            | 1        | 1      | 0.55%   |
| OCZ-REVODRIVE       | 1        | 4      | 0.55%   |
| MemoCom             | 1        | 2      | 0.55%   |
| LITEONIT            | 1        | 1      | 0.55%   |
| Lite-On             | 1        | 1      | 0.55%   |
| Hewlett-Packard     | 1        | 1      | 0.55%   |
| FORESEE             | 1        | 2      | 0.55%   |
| EZLINK              | 1        | 1      | 0.55%   |
| AXIOMTEK            | 1        | 1      | 0.55%   |
| ATP                 | 1        | 1      | 0.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 178      | 340    | 40.45%  |
| SSD     | 144      | 226    | 32.73%  |
| NVMe    | 106      | 166    | 24.09%  |
| Unknown | 7        | 9      | 1.59%   |
| MMC     | 5        | 5      | 1.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 247      | 542    | 65.69%  |
| NVMe | 105      | 165    | 27.93%  |
| SAS  | 19       | 34     | 5.05%   |
| MMC  | 5        | 5      | 1.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 170      | 292    | 47.35%  |
| 0.51-1.0   | 106      | 148    | 29.53%  |
| 1.01-2.0   | 44       | 68     | 12.26%  |
| 3.01-4.0   | 18       | 28     | 5.01%   |
| 2.01-3.0   | 10       | 12     | 2.79%   |
| 4.01-10.0  | 9        | 16     | 2.51%   |
| 10.01-20.0 | 2        | 2      | 0.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 70       | 22.22%  |
| 251-500        | 52       | 16.51%  |
| 1001-2000      | 40       | 12.7%   |
| 501-1000       | 37       | 11.75%  |
| More than 3000 | 25       | 7.94%   |
| 2001-3000      | 24       | 7.62%   |
| 51-100         | 22       | 6.98%   |
| 1-20           | 17       | 5.4%    |
| 21-50          | 15       | 4.76%   |
| Unknown        | 13       | 4.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 114      | 35.63%  |
| 21-50          | 42       | 13.13%  |
| 51-100         | 40       | 12.5%   |
| 101-250        | 39       | 12.19%  |
| 251-500        | 20       | 6.25%   |
| 501-1000       | 19       | 5.94%   |
| 1001-2000      | 18       | 5.63%   |
| Unknown        | 13       | 4.06%   |
| More than 3000 | 9        | 2.81%   |
| 2001-3000      | 6        | 1.88%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Intel SSDPEKKW256G7 256GB           | 2        | 3      | 6.25%   |
| Hitachi HDT721010SLA360 1TB         | 2        | 2      | 6.25%   |
| WDC WDS100T2B0C-00PXH0 1TB          | 1        | 1      | 3.13%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 1        | 1      | 3.13%   |
| WDC WD5000AAKX-001CA0 500GB         | 1        | 1      | 3.13%   |
| WDC WD5000AADS-00L4B1 500GB         | 1        | 1      | 3.13%   |
| WDC WD3200AAKS-00L9A0 320GB         | 1        | 1      | 3.13%   |
| WDC WD20EARX-00PASB0 2TB            | 1        | 1      | 3.13%   |
| WDC WD20EARS-00MVWB0 2TB            | 1        | 1      | 3.13%   |
| WDC WD10EFRX-68JCSN0 1TB            | 1        | 1      | 3.13%   |
| WDC WD10EALS-00Z8A0 1TB             | 1        | 1      | 3.13%   |
| WDC WD1002FAEX-00Z3A0 1TB           | 1        | 1      | 3.13%   |
| Transcend TS64GSSD340 64GB          | 1        | 1      | 3.13%   |
| Seagate ST500LM000-1EJ162 500GB     | 1        | 1      | 3.13%   |
| Seagate ST4000DX001-1CE168 4TB      | 1        | 2      | 3.13%   |
| Seagate ST3500418AS 500GB           | 1        | 1      | 3.13%   |
| Seagate ST3500410SV 500GB           | 1        | 1      | 3.13%   |
| Seagate ST3160811AS 160GB           | 1        | 1      | 3.13%   |
| Seagate ST2000VN000-1H3164 2TB      | 1        | 2      | 3.13%   |
| SanDisk SDSSDX240GG25 240GB         | 1        | 1      | 3.13%   |
| Samsung Electronics HM321HI 320GB   | 1        | 2      | 3.13%   |
| Plextor PX-128M6Pro 128GB SSD       | 1        | 1      | 3.13%   |
| LITEONIT E200-080 80GB SSD          | 1        | 1      | 3.13%   |
| KLEVV SSD NEO N500 240GB            | 1        | 1      | 3.13%   |
| Kingston SV300S37A60G 64GB SSD      | 1        | 1      | 3.13%   |
| Intel SSDSC2BB016T7 2TB             | 1        | 1      | 3.13%   |
| Hitachi HDS723020BLA642 2TB         | 1        | 2      | 3.13%   |
| Fujitsu F500S-480GB SSD             | 1        | 1      | 3.13%   |
| Crucial CT275MX300SSD4 275GB        | 1        | 1      | 3.13%   |
| A-DATA Technology IMSS332-960GB SSD | 1        | 1      | 3.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 10       | 10     | 31.25%  |
| Seagate             | 6        | 8      | 18.75%  |
| Intel               | 3        | 4      | 9.38%   |
| Hitachi             | 3        | 4      | 9.38%   |
| Transcend           | 1        | 1      | 3.13%   |
| SanDisk             | 1        | 1      | 3.13%   |
| Samsung Electronics | 1        | 2      | 3.13%   |
| Plextor             | 1        | 1      | 3.13%   |
| LITEONIT            | 1        | 1      | 3.13%   |
| KLEVV               | 1        | 1      | 3.13%   |
| Kingston            | 1        | 1      | 3.13%   |
| Fujitsu             | 1        | 1      | 3.13%   |
| Crucial             | 1        | 1      | 3.13%   |
| A-DATA Technology   | 1        | 1      | 3.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 9        | 9      | 47.37%  |
| Seagate             | 6        | 8      | 31.58%  |
| Hitachi             | 3        | 4      | 15.79%  |
| Samsung Electronics | 1        | 2      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 17       | 23     | 56.67%  |
| SSD  | 10       | 10     | 33.33%  |
| NVMe | 3        | 4      | 10%     |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 168      | 418    | 51.38%  |
| Works    | 130      | 291    | 39.76%  |
| Malfunc  | 29       | 37     | 8.87%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 206      | 47.58%  |
| AMD                            | 75       | 17.32%  |
| SanDisk                        | 19       | 4.39%   |
| Phison Electronics             | 16       | 3.7%    |
| ASMedia Technology             | 16       | 3.7%    |
| Samsung Electronics            | 13       | 3%      |
| Micron/Crucial Technology      | 10       | 2.31%   |
| Nvidia                         | 9        | 2.08%   |
| ADATA Technology               | 9        | 2.08%   |
| Silicon Motion                 | 8        | 1.85%   |
| Kingston Technology Company    | 8        | 1.85%   |
| Marvell Technology Group       | 6        | 1.39%   |
| MAXIO Technology (Hangzhou)    | 5        | 1.15%   |
| JMicron Technology             | 4        | 0.92%   |
| SK hynix                       | 3        | 0.69%   |
| Lite-On Technology             | 3        | 0.69%   |
| KIOXIA                         | 3        | 0.69%   |
| Solidigm                       | 2        | 0.46%   |
| Solid State Storage Technology | 2        | 0.46%   |
| Realtek Semiconductor          | 2        | 0.46%   |
| Micron Technology              | 2        | 0.46%   |
| LSI Logic / Symbios Logic      | 2        | 0.46%   |
| Biwin Storage Technology       | 2        | 0.46%   |
| Yangtze Memory Technologies    | 1        | 0.23%   |
| Silicon Image                  | 1        | 0.23%   |
| Shenzhen Longsys Electronics   | 1        | 0.23%   |
| Seagate Technology             | 1        | 0.23%   |
| Integrated Technology Express  | 1        | 0.23%   |
| INNOGRIT                       | 1        | 0.23%   |
| Innodisk                       | 1        | 0.23%   |
| Broadcom / LSI                 | 1        | 0.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 39       | 7.36%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 29       | 5.47%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 15       | 2.83%   |
| AMD 500 Series Chipset SATA Controller                                                  | 15       | 2.83%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 14       | 2.64%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 14       | 2.64%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 13       | 2.45%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 13       | 2.45%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 12       | 2.26%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 11       | 2.08%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 11       | 2.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 10       | 1.89%   |
| Intel SATA Controller [RAID mode]                                                       | 9        | 1.7%    |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 8        | 1.51%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 8        | 1.51%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 8        | 1.51%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 8        | 1.51%   |
| AMD 400 Series Chipset SATA Controller                                                  | 8        | 1.51%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7        | 1.32%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 7        | 1.32%   |
| Nvidia MCP61 SATA Controller                                                            | 6        | 1.13%   |
| Nvidia MCP61 IDE                                                                        | 6        | 1.13%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 6        | 1.13%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 6        | 1.13%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6        | 1.13%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 6        | 1.13%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 5        | 0.94%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 5        | 0.94%   |
| Phison E12 NVMe Controller                                                              | 5        | 0.94%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                        | 5        | 0.94%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 5        | 0.94%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 5        | 0.94%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 5        | 0.94%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 0.94%   |
| AMD 600 Series Chipset SATA Controller                                                  | 5        | 0.94%   |
| AMD 300 Series Chipset SATA Controller                                                  | 5        | 0.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 0.75%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 0.75%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 4        | 0.75%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 4        | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 238      | 55.61%  |
| NVMe | 105      | 24.53%  |
| IDE  | 62       | 14.49%  |
| RAID | 19       | 4.44%   |
| SAS  | 3        | 0.7%    |
| SCSI | 1        | 0.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor        | Desktops | Percent |
|---------------|----------|---------|
| Intel         | 209      | 71.09%  |
| AMD           | 84       | 28.57%  |
| sifive,u74-mc | 1        | 0.34%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-2400 CPU @ 3.10GHz            | 5        | 1.67%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 5        | 1.67%   |
| Intel 12th Gen Core i7-12700                | 5        | 1.67%   |
| AMD Ryzen 5 3600 6-Core Processor           | 5        | 1.67%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 4        | 1.34%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 4        | 1.34%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 4        | 1.34%   |
| Intel Xeon CPU E3-1231 v3 @ 3.40GHz         | 3        | 1%      |
| Intel Pentium CPU G840 @ 2.80GHz            | 3        | 1%      |
| Intel Core i7-6700 CPU @ 3.40GHz            | 3        | 1%      |
| Intel Core i7-4790K CPU @ 4.00GHz           | 3        | 1%      |
| Intel Core i7-10700 CPU @ 2.90GHz           | 3        | 1%      |
| Intel Core i5-6500 CPU @ 3.20GHz            | 3        | 1%      |
| Intel Core i3-8100 CPU @ 3.60GHz            | 3        | 1%      |
| Intel Core i3-6100 CPU @ 3.70GHz            | 3        | 1%      |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 3        | 1%      |
| Intel Celeron J4105 CPU @ 1.50GHz           | 3        | 1%      |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 3        | 1%      |
| AMD Ryzen 9 5900X 12-Core Processor         | 3        | 1%      |
| AMD Ryzen 5 PRO 4650G with Radeon Graphics  | 3        | 1%      |
| AMD Ryzen 5 5600X 6-Core Processor          | 3        | 1%      |
| AMD Ryzen 5 5600G with Radeon Graphics      | 3        | 1%      |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 3        | 1%      |
| AMD FX-6300 Six-Core Processor              | 3        | 1%      |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz         | 2        | 0.67%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 2        | 0.67%   |
| Intel Pentium Gold G5500 CPU @ 3.80GHz      | 2        | 0.67%   |
| Intel N97                                   | 2        | 0.67%   |
| Intel N100                                  | 2        | 0.67%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 2        | 0.67%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 2        | 0.67%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 0.67%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 2        | 0.67%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 2        | 0.67%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 2        | 0.67%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 2        | 0.67%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 0.67%   |
| Intel Core i5-4670T CPU @ 2.30GHz           | 2        | 0.67%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 0.67%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 0.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 48       | 16.05%  |
| Intel Core i7           | 36       | 12.04%  |
| Intel Core i3           | 28       | 9.36%   |
| Other                   | 26       | 8.7%    |
| AMD Ryzen 5             | 23       | 7.69%   |
| Intel Xeon              | 22       | 7.36%   |
| AMD Ryzen 7             | 15       | 5.02%   |
| Intel Celeron           | 13       | 4.35%   |
| AMD Ryzen 9             | 12       | 4.01%   |
| Intel Core 2 Quad       | 11       | 3.68%   |
| Intel Pentium           | 10       | 3.34%   |
| AMD FX                  | 8        | 2.68%   |
| Intel Core 2 Duo        | 5        | 1.67%   |
| Intel Pentium Gold      | 4        | 1.34%   |
| Intel Pentium Dual-Core | 4        | 1.34%   |
| AMD Ryzen 5 PRO         | 4        | 1.34%   |
| AMD Athlon 64 X2        | 4        | 1.34%   |
| Intel Genuine           | 3        | 1%      |
| Intel Core i9           | 3        | 1%      |
| AMD Phenom II X4        | 3        | 1%      |
| AMD Athlon II X4        | 2        | 0.67%   |
| AMD Athlon II X2        | 2        | 0.67%   |
| AMD A8                  | 2        | 0.67%   |
| Intel Pentium Silver    | 1        | 0.33%   |
| Intel Atom              | 1        | 0.33%   |
| AMD Sempron             | 1        | 0.33%   |
| AMD Ryzen Threadripper  | 1        | 0.33%   |
| AMD Ryzen 7 PRO         | 1        | 0.33%   |
| AMD Ryzen 3             | 1        | 0.33%   |
| AMD Phenom II X6        | 1        | 0.33%   |
| AMD Phenom II X2        | 1        | 0.33%   |
| AMD Athlon              | 1        | 0.33%   |
| AMD A4                  | 1        | 0.33%   |
| AMD A10                 | 1        | 0.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 117      | 39.26%  |
| 2       | 67       | 22.48%  |
| 6       | 43       | 14.43%  |
| 8       | 31       | 10.4%   |
| 12      | 17       | 5.7%    |
| 16      | 9        | 3.02%   |
| 3       | 3        | 1.01%   |
| 28      | 2        | 0.67%   |
| 24      | 2        | 0.67%   |
| 48      | 1        | 0.34%   |
| 44      | 1        | 0.34%   |
| 22      | 1        | 0.34%   |
| 18      | 1        | 0.34%   |
| 14      | 1        | 0.34%   |
| 10      | 1        | 0.34%   |
| Unknown | 1        | 0.34%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 287      | 97.62%  |
| 2       | 6        | 2.04%   |
| Unknown | 1        | 0.34%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 172      | 57.72%  |
| 1       | 125      | 41.95%  |
| Unknown | 1        | 0.34%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 288      | 97.63%  |
| Unknown        | 7        | 2.37%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 92       | 29.77%  |
| 0x306c3    | 27       | 8.74%   |
| 0x306a9    | 17       | 5.5%    |
| 0x206a7    | 14       | 4.53%   |
| 0x506e3    | 10       | 3.24%   |
| 0x08701021 | 9        | 2.91%   |
| 0x1067a    | 8        | 2.59%   |
| 0x906ea    | 7        | 2.27%   |
| 0x906eb    | 6        | 1.94%   |
| 0x06000852 | 5        | 1.62%   |
| 0x90672    | 4        | 1.29%   |
| 0x706a1    | 4        | 1.29%   |
| 0x10676    | 4        | 1.29%   |
| 0xa0655    | 3        | 0.97%   |
| 0xa0653    | 3        | 0.97%   |
| 0x10677    | 3        | 0.97%   |
| 0x0a601203 | 3        | 0.97%   |
| 0x0a50000d | 3        | 0.97%   |
| 0x0a201009 | 3        | 0.97%   |
| 0x0810100b | 3        | 0.97%   |
| 0x08001138 | 3        | 0.97%   |
| 0x010000c8 | 3        | 0.97%   |
| 0xa0671    | 2        | 0.65%   |
| 0x906ed    | 2        | 0.65%   |
| 0x6fb      | 2        | 0.65%   |
| 0x50654    | 2        | 0.65%   |
| 0x406f1    | 2        | 0.65%   |
| 0x306f2    | 2        | 0.65%   |
| 0x306e4    | 2        | 0.65%   |
| 0x206c2    | 2        | 0.65%   |
| 0x106e5    | 2        | 0.65%   |
| 0x0a50000c | 2        | 0.65%   |
| 0x0a20120a | 2        | 0.65%   |
| 0x0a20102b | 2        | 0.65%   |
| 0x0a201016 | 2        | 0.65%   |
| 0x08600106 | 2        | 0.65%   |
| 0x08101016 | 2        | 0.65%   |
| 0x0800820d | 2        | 0.65%   |
| 0x0800820b | 2        | 0.65%   |
| 0x06001119 | 2        | 0.65%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 41       | 13.9%   |
| KabyLake         | 29       | 9.83%   |
| IvyBridge        | 22       | 7.46%   |
| Skylake          | 20       | 6.78%   |
| Penryn           | 19       | 6.44%   |
| Zen 3            | 18       | 6.1%    |
| Zen 2            | 18       | 6.1%    |
| SandyBridge      | 18       | 6.1%    |
| Unknown          | 17       | 5.76%   |
| Zen              | 10       | 3.39%   |
| K10              | 10       | 3.39%   |
| CometLake        | 10       | 3.39%   |
| Alderlake Hybrid | 10       | 3.39%   |
| Piledriver       | 9        | 3.05%   |
| Zen+             | 6        | 2.03%   |
| Icelake          | 5        | 1.69%   |
| Broadwell        | 5        | 1.69%   |
| Westmere         | 4        | 1.36%   |
| K8 Hammer        | 4        | 1.36%   |
| Goldmont plus    | 4        | 1.36%   |
| Nehalem          | 3        | 1.02%   |
| Tremont          | 2        | 0.68%   |
| Silvermont       | 2        | 0.68%   |
| Jaguar           | 2        | 0.68%   |
| Core             | 2        | 0.68%   |
| Steamroller      | 1        | 0.34%   |
| Gracemont        | 1        | 0.34%   |
| Goldmont         | 1        | 0.34%   |
| Bulldozer        | 1        | 0.34%   |
| Bonnell          | 1        | 0.34%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 126      | 40.51%  |
| Intel                      | 116      | 37.3%   |
| AMD                        | 64       | 20.58%  |
| ASPEED Technology          | 3        | 0.96%   |
| Matrox Electronics Systems | 2        | 0.64%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 18       | 5.64%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 14       | 4.39%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 10       | 3.13%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 9        | 2.82%   |
| Nvidia GK208B [GeForce GT 710]                                              | 8        | 2.51%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 8        | 2.51%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 8        | 2.51%   |
| Intel HD Graphics 530                                                       | 7        | 2.19%   |
| Intel AlderLake-S GT1                                                       | 7        | 2.19%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 7        | 2.19%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 6        | 1.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6        | 1.88%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 5        | 1.57%   |
| AMD RS780L [Radeon 3000]                                                    | 5        | 1.57%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 5        | 1.57%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5        | 1.57%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 5        | 1.57%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 4        | 1.25%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 4        | 1.25%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 4        | 1.25%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 4        | 1.25%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 4        | 1.25%   |
| Intel Alder Lake-N [UHD Graphics]                                           | 4        | 1.25%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 4        | 1.25%   |
| AMD Raphael                                                                 | 4        | 1.25%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 4        | 1.25%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 3        | 0.94%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 0.94%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 0.94%   |
| Nvidia GF108 [GeForce GT 630]                                               | 3        | 0.94%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 3        | 0.94%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 3        | 0.94%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 3        | 0.94%   |
| ASPEED Technology ASPEED Graphics Family                                    | 3        | 0.94%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 0.63%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 0.63%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 0.63%   |
| Nvidia GP107GL [Quadro P600]                                                | 2        | 0.63%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 0.63%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 113      | 38.05%  |
| 1 x Intel      | 103      | 34.68%  |
| 1 x AMD        | 56       | 18.86%  |
| Intel + Nvidia | 9        | 3.03%   |
| AMD + Nvidia   | 4        | 1.35%   |
| Other          | 3        | 1.01%   |
| 2 x AMD        | 2        | 0.67%   |
| 1 x Matrox     | 2        | 0.67%   |
| 1 x ASPEED     | 2        | 0.67%   |
| 2 x Nvidia     | 1        | 0.34%   |
| Intel + AMD    | 1        | 0.34%   |
| AMD + ASPEED   | 1        | 0.34%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 210      | 69.77%  |
| Proprietary | 68       | 22.59%  |
| Unknown     | 23       | 7.64%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 150      | 49.18%  |
| 1.01-2.0   | 36       | 11.8%   |
| 0.01-0.5   | 28       | 9.18%   |
| 0.51-1.0   | 26       | 8.52%   |
| 3.01-4.0   | 22       | 7.21%   |
| 5.01-6.0   | 17       | 5.57%   |
| 7.01-8.0   | 10       | 3.28%   |
| 8.01-16.0  | 10       | 3.28%   |
| 2.01-3.0   | 3        | 0.98%   |
| 16.01-24.0 | 3        | 0.98%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Ancor Communications | 37       | 12.46%  |
| Acer                 | 34       | 11.45%  |
| BenQ                 | 32       | 10.77%  |
| ViewSonic            | 24       | 8.08%   |
| Dell                 | 18       | 6.06%   |
| ASUSTek Computer     | 17       | 5.72%   |
| Goldstar             | 16       | 5.39%   |
| AOC                  | 15       | 5.05%   |
| Samsung Electronics  | 12       | 4.04%   |
| Philips              | 12       | 4.04%   |
| NEX                  | 7        | 2.36%   |
| Hewlett-Packard      | 7        | 2.36%   |
| Eizo                 | 7        | 2.36%   |
| Gigabyte Technology  | 6        | 2.02%   |
| Unknown              | 5        | 1.68%   |
| Envision Peripherals | 5        | 1.68%   |
| LG Electronics       | 4        | 1.35%   |
| Vizio                | 3        | 1.01%   |
| Unknown              | 3        | 1.01%   |
| Wacom                | 2        | 0.67%   |
| Unknown (XXX)        | 2        | 0.67%   |
| Sony                 | 2        | 0.67%   |
| MSI                  | 2        | 0.67%   |
| KTC                  | 2        | 0.67%   |
| AUS                  | 2        | 0.67%   |
| ___                  | 1        | 0.34%   |
| VIZ                  | 1        | 0.34%   |
| Toshiba              | 1        | 0.34%   |
| Tatung               | 1        | 0.34%   |
| SMP                  | 1        | 0.34%   |
| PFH                  | 1        | 0.34%   |
| NEC Computers        | 1        | 0.34%   |
| KEB                  | 1        | 0.34%   |
| ITE                  | 1        | 0.34%   |
| INS                  | 1        | 0.34%   |
| HWL                  | 1        | 0.34%   |
| HKC                  | 1        | 0.34%   |
| GLE                  | 1        | 0.34%   |
| Denver               | 1        | 0.34%   |
| Compal               | 1        | 0.34%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| ViewSonic VX2718-2KPC VSCB73A 2560x1440 598x336mm 27.0-inch           | 7        | 2.32%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 5        | 1.66%   |
| Samsung Electronics SyncMaster SAM03C2 1680x1050 459x296mm 21.5-inch  | 4        | 1.32%   |
| Gigabyte Technology GS32QC GBT3212 2560x1440 709x403mm 32.1-inch      | 4        | 1.32%   |
| Acer KA220HQ ACR0467 1920x1080 477x268mm 21.5-inch                    | 4        | 1.32%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 3        | 0.99%   |
| BenQ GC2870 BNQ78DD 1920x1080 621x341mm 27.9-inch                     | 3        | 0.99%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 3        | 0.99%   |
| Ancor Communications ASUS VS207 ACI20F2 1600x900 432x240mm 19.5-inch  | 3        | 0.99%   |
| Ancor Communications ASUS VH228 ACI22FC 1920x1080 477x268mm 21.5-inch | 3        | 0.99%   |
| Acer V226HQL ACR0335 1920x1080 477x268mm 21.5-inch                    | 3        | 0.99%   |
| Unknown                                                               | 3        | 0.99%   |
| Wacom Cintiq 13HD WAC1040 1920x1080 293x165mm 13.2-inch               | 2        | 0.66%   |
| ViewSonic VX2476 Series VSCD332 1920x1080 527x296mm 23.8-inch         | 2        | 0.66%   |
| ViewSonic VA916 Series VSC7C20 1280x1024 376x301mm 19.0-inch          | 2        | 0.66%   |
| ViewSonic VA2246 SERIES VSC6F2E 1920x1080 477x268mm 21.5-inch         | 2        | 0.66%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 2        | 0.66%   |
| Unknown LCD Monitor Kingston Technology 43 TV 1920x1080               | 2        | 0.66%   |
| Philips PHL BDM4350 PHL08FA 3840x2160 953x543mm 43.2-inch             | 2        | 0.66%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 2        | 0.66%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                     | 2        | 0.66%   |
| KTC 43 TV KTC4300 1920x1080 953x543mm 43.2-inch                       | 2        | 0.66%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch             | 2        | 0.66%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2        | 0.66%   |
| Envision Peripherals LED H963wLs ENV1963 1366x768 410x230mm 18.5-inch | 2        | 0.66%   |
| Envision Peripherals LCD2271W ENV2271 1920x1080 476x268mm 21.5-inch   | 2        | 0.66%   |
| BenQ GW2470 BNQ78D9 1920x1080 527x296mm 23.8-inch                     | 2        | 0.66%   |
| BenQ GW2450H BNQ78C1 1920x1080 531x298mm 24.0-inch                    | 2        | 0.66%   |
| BenQ GW2280 BNQ78E8 1920x1080 476x268mm 21.5-inch                     | 2        | 0.66%   |
| BenQ GL2450H BNQ78A6 1920x1080 531x298mm 24.0-inch                    | 2        | 0.66%   |
| BenQ EW2775ZH BNQ7944 1920x1080 598x336mm 27.0-inch                   | 2        | 0.66%   |
| BenQ EW2730V BNQ7931 1920x1080 597x336mm 27.0-inch                    | 2        | 0.66%   |
| ASUSTek Computer VA27EHE AUS27D2 1920x1080 598x336mm 27.0-inch        | 2        | 0.66%   |
| ASUSTek Computer VA24E AUS24D1 1920x1080 527x296mm 23.8-inch          | 2        | 0.66%   |
| AOC 2260WG5 AOC2260 1920x1080 477x268mm 21.5-inch                     | 2        | 0.66%   |
| Ancor Communications ASUS VX239 ACI23E1 1920x1080 509x286mm 23.0-inch | 2        | 0.66%   |
| Ancor Communications ASUS VW247 ACI2496 1920x1080 531x299mm 24.0-inch | 2        | 0.66%   |
| Ancor Communications ASUS VW193S ACI19D4 1440x900 410x260mm 19.1-inch | 2        | 0.66%   |
| Ancor Communications ASUS VS229 ACI22C2 1920x1080 477x268mm 21.5-inch | 2        | 0.66%   |
| Ancor Communications ASUS VS197 ACI19F2 1366x768 410x230mm 18.5-inch  | 2        | 0.66%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 158      | 56.43%  |
| 2560x1440 (QHD)    | 28       | 10%     |
| 3840x2160 (4K)     | 20       | 7.14%   |
| 1366x768 (WXGA)    | 16       | 5.71%   |
| 1280x1024 (SXGA)   | 10       | 3.57%   |
| 1680x1050 (WSXGA+) | 9        | 3.21%   |
| 2560x1080          | 8        | 2.86%   |
| 1920x1200 (WUXGA)  | 7        | 2.5%    |
| 1600x900 (HD+)     | 7        | 2.5%    |
| 1440x900 (WXGA+)   | 6        | 2.14%   |
| 3840x1080          | 2        | 0.71%   |
| 3440x1440          | 2        | 0.71%   |
| 1024x768 (XGA)     | 2        | 0.71%   |
| Unknown            | 2        | 0.71%   |
| 1920x540           | 1        | 0.36%   |
| 1600x1200          | 1        | 0.36%   |
| 1360x768           | 1        | 0.36%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 52       | 17.63%  |
| 27      | 50       | 16.95%  |
| 24      | 42       | 14.24%  |
| Unknown | 35       | 11.86%  |
| 23      | 29       | 9.83%   |
| 19      | 20       | 6.78%   |
| 31      | 11       | 3.73%   |
| 18      | 9        | 3.05%   |
| 34      | 7        | 2.37%   |
| 22      | 6        | 2.03%   |
| 15      | 6        | 2.03%   |
| 43      | 4        | 1.36%   |
| 32      | 4        | 1.36%   |
| 20      | 3        | 1.02%   |
| 54      | 2        | 0.68%   |
| 17      | 2        | 0.68%   |
| 13      | 2        | 0.68%   |
| 84      | 1        | 0.34%   |
| 69      | 1        | 0.34%   |
| 65      | 1        | 0.34%   |
| 49      | 1        | 0.34%   |
| 48      | 1        | 0.34%   |
| 46      | 1        | 0.34%   |
| 42      | 1        | 0.34%   |
| 41      | 1        | 0.34%   |
| 40      | 1        | 0.34%   |
| 26      | 1        | 0.34%   |
| 25      | 1        | 0.34%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 110      | 38.06%  |
| 401-500     | 82       | 28.37%  |
| Unknown     | 35       | 12.11%  |
| 601-700     | 19       | 6.57%   |
| 701-800     | 11       | 3.81%   |
| 351-400     | 7        | 2.42%   |
| 301-350     | 7        | 2.42%   |
| 1001-1500   | 6        | 2.08%   |
| 901-1000    | 6        | 2.08%   |
| 201-300     | 3        | 1.04%   |
| 1501-2000   | 2        | 0.69%   |
| 801-900     | 1        | 0.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 192      | 69.57%  |
| Unknown | 34       | 12.32%  |
| 16/10   | 26       | 9.42%   |
| 5/4     | 9        | 3.26%   |
| 21/9    | 7        | 2.54%   |
| 4/3     | 3        | 1.09%   |
| 32/9    | 3        | 1.09%   |
| 6/5     | 1        | 0.36%   |
| 3/2     | 1        | 0.36%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 102      | 34.81%  |
| 301-350        | 51       | 17.41%  |
| 151-200        | 39       | 13.31%  |
| Unknown        | 35       | 11.95%  |
| 351-500        | 22       | 7.51%   |
| 141-150        | 11       | 3.75%   |
| 251-300        | 10       | 3.41%   |
| 501-1000       | 10       | 3.41%   |
| More than 1000 | 5        | 1.71%   |
| 101-110        | 4        | 1.37%   |
| 71-80          | 2        | 0.68%   |
| 121-130        | 1        | 0.34%   |
| 111-120        | 1        | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 165      | 57.89%  |
| 101-120 | 68       | 23.86%  |
| Unknown | 35       | 12.28%  |
| 121-160 | 9        | 3.16%   |
| 161-240 | 5        | 1.75%   |
| 1-50    | 3        | 1.05%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 246      | 82.27%  |
| 0     | 28       | 9.36%   |
| 2     | 23       | 7.69%   |
| 3     | 2        | 0.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 173      | 40.14%  |
| Intel                                  | 138      | 32.02%  |
| Qualcomm Atheros                       | 17       | 3.94%   |
| Ralink Technology                      | 12       | 2.78%   |
| MediaTek                               | 12       | 2.78%   |
| Aquantia                               | 11       | 2.55%   |
| Broadcom                               | 9        | 2.09%   |
| Edimax Technology                      | 7        | 1.62%   |
| ASUSTek Computer                       | 6        | 1.39%   |
| TP-Link                                | 5        | 1.16%   |
| Nvidia                                 | 5        | 1.16%   |
| Marvell Technology Group               | 5        | 1.16%   |
| HTC (High Tech Computer)               | 4        | 0.93%   |
| Samsung Electronics                    | 2        | 0.46%   |
| Ralink                                 | 2        | 0.46%   |
| ZyXEL Communications                   | 1        | 0.23%   |
| Winbond Electronics                    | 1        | 0.23%   |
| SparkFun                               | 1        | 0.23%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.23%   |
| Senao                                  | 1        | 0.23%   |
| Qualcomm Atheros Communications        | 1        | 0.23%   |
| Prolific Technology                    | 1        | 0.23%   |
| OPPO Electronics                       | 1        | 0.23%   |
| Microsoft                              | 1        | 0.23%   |
| Mercucys                               | 1        | 0.23%   |
| Mellanox Technologies                  | 1        | 0.23%   |
| IBM                                    | 1        | 0.23%   |
| Huawei Technologies                    | 1        | 0.23%   |
| Google                                 | 1        | 0.23%   |
| D-Link System                          | 1        | 0.23%   |
| D-Link                                 | 1        | 0.23%   |
| BUFFALO                                | 1        | 0.23%   |
| ASIX Electronics                       | 1        | 0.23%   |
| Arduino SA                             | 1        | 0.23%   |
| Apple                                  | 1        | 0.23%   |
| American Megatrends                    | 1        | 0.23%   |
| Accton Technology                      | 1        | 0.23%   |
| 3Com                                   | 1        | 0.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                           | Desktops | Percent |
|---------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller          | 138      | 27.66%  |
| Intel I211 Gigabit Network Connection                                           | 21       | 4.21%   |
| Realtek RTL8125 2.5GbE Controller                                               | 19       | 3.81%   |
| Intel Ethernet Controller I225-V                                                | 19       | 3.81%   |
| Intel Wi-Fi 6 AX200                                                             | 17       | 3.41%   |
| Intel Ethernet Connection (7) I219-V                                            | 9        | 1.8%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                | 9        | 1.8%    |
| Ralink MT7601U Wireless Adapter                                                 | 8        | 1.6%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                       | 8        | 1.6%    |
| Intel I210 Gigabit Network Connection                                           | 8        | 1.6%    |
| Intel Ethernet Connection (2) I219-V                                            | 8        | 1.6%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                         | 6        | 1.2%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                         | 6        | 1.2%    |
| Intel Ethernet Connection I217-V                                                | 6        | 1.2%    |
| Intel Alder Lake-S PCH CNVi WiFi                                                | 6        | 1.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                           | 6        | 1.2%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                      | 5        | 1%      |
| Intel Ethernet Connection (17) I219-V                                           | 5        | 1%      |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G]  | 5        | 1%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                             | 4        | 0.8%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                       | 4        | 0.8%    |
| Intel Ethernet Connection I217-LM                                               | 4        | 0.8%    |
| Intel Ethernet Connection (7) I219-LM                                           | 4        | 0.8%    |
| HTC (High Tech Computer) Desire HD (modem mode)                                 | 4        | 0.8%    |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                  | 4        | 0.8%    |
| Aquantia AQtion AQC113CS NBase-T/IEEE 802.3an Ethernet Controller [Antigua 10G] | 4        | 0.8%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                 | 3        | 0.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                 | 3        | 0.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                        | 3        | 0.6%    |
| Realtek RTL8152 Fast Ethernet Adapter                                           | 3        | 0.6%    |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller               | 3        | 0.6%    |
| Nvidia MCP61 Ethernet                                                           | 3        | 0.6%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                   | 3        | 0.6%    |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                         | 3        | 0.6%    |
| Intel Ethernet Controller I226-V                                                | 3        | 0.6%    |
| Intel Ethernet Connection (14) I219-V                                           | 3        | 0.6%    |
| Intel Comet Lake PCH CNVi WiFi                                                  | 3        | 0.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                                 | 3        | 0.6%    |
| Intel 82574L Gigabit Network Connection                                         | 3        | 0.6%    |
| ASUS 802.11ac NIC                                                               | 3        | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 64       | 45.07%  |
| Realtek Semiconductor           | 22       | 15.49%  |
| Ralink Technology               | 12       | 8.45%   |
| MediaTek                        | 10       | 7.04%   |
| Edimax Technology               | 7        | 4.93%   |
| ASUSTek Computer                | 6        | 4.23%   |
| Broadcom                        | 4        | 2.82%   |
| TP-Link                         | 3        | 2.11%   |
| Qualcomm Atheros                | 3        | 2.11%   |
| Ralink                          | 2        | 1.41%   |
| ZyXEL Communications            | 1        | 0.7%    |
| Senao                           | 1        | 0.7%    |
| Qualcomm Atheros Communications | 1        | 0.7%    |
| Microsoft                       | 1        | 0.7%    |
| Mercucys                        | 1        | 0.7%    |
| D-Link System                   | 1        | 0.7%    |
| D-Link                          | 1        | 0.7%    |
| BUFFALO                         | 1        | 0.7%    |
| Accton Technology               | 1        | 0.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 17       | 11.72%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 9        | 6.21%   |
| Ralink MT7601U Wireless Adapter                                | 8        | 5.52%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 8        | 5.52%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 6        | 4.14%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 6        | 4.14%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 6        | 4.14%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 5        | 3.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 4        | 2.76%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 4        | 2.76%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3        | 2.07%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3        | 2.07%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 3        | 2.07%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 3        | 2.07%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3        | 2.07%   |
| ASUS 802.11ac NIC                                              | 3        | 2.07%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 2        | 1.38%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2        | 1.38%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 2        | 1.38%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 2        | 1.38%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter              | 2        | 1.38%   |
| Intel Wireless 8265 / 8275                                     | 2        | 1.38%   |
| Intel Wireless 3165                                            | 2        | 1.38%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2        | 1.38%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 2        | 1.38%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]   | 1        | 0.69%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 1        | 0.69%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 1        | 0.69%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1        | 0.69%   |
| Senao 802.11 n WLAN                                            | 1        | 0.69%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 1        | 0.69%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                         | 1        | 0.69%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1        | 0.69%   |
| Realtek 802.11ac NIC                                           | 1        | 0.69%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1        | 0.69%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1        | 0.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1        | 0.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1        | 0.69%   |
| Qualcomm Atheros AR9271 802.11n                                | 1        | 0.69%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1        | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 162      | 48.94%  |
| Intel                                  | 108      | 32.63%  |
| Qualcomm Atheros                       | 14       | 4.23%   |
| Aquantia                               | 11       | 3.32%   |
| Broadcom                               | 6        | 1.81%   |
| Nvidia                                 | 5        | 1.51%   |
| Marvell Technology Group               | 5        | 1.51%   |
| HTC (High Tech Computer)               | 4        | 1.21%   |
| TP-Link                                | 2        | 0.6%    |
| Samsung Electronics                    | 2        | 0.6%    |
| MediaTek                               | 2        | 0.6%    |
| Sony Ericsson Mobile Communications AB | 1        | 0.3%    |
| OPPO Electronics                       | 1        | 0.3%    |
| Mellanox Technologies                  | 1        | 0.3%    |
| IBM                                    | 1        | 0.3%    |
| Huawei Technologies                    | 1        | 0.3%    |
| Google                                 | 1        | 0.3%    |
| ASIX Electronics                       | 1        | 0.3%    |
| Apple                                  | 1        | 0.3%    |
| American Megatrends                    | 1        | 0.3%    |
| 3Com                                   | 1        | 0.3%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                           | Desktops | Percent |
|---------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller          | 138      | 39.43%  |
| Intel I211 Gigabit Network Connection                                           | 21       | 6%      |
| Realtek RTL8125 2.5GbE Controller                                               | 19       | 5.43%   |
| Intel Ethernet Controller I225-V                                                | 19       | 5.43%   |
| Intel Ethernet Connection (7) I219-V                                            | 9        | 2.57%   |
| Intel I210 Gigabit Network Connection                                           | 8        | 2.29%   |
| Intel Ethernet Connection (2) I219-V                                            | 8        | 2.29%   |
| Intel Ethernet Connection I217-V                                                | 6        | 1.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                           | 6        | 1.71%   |
| Intel Ethernet Connection (17) I219-V                                           | 5        | 1.43%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G]  | 5        | 1.43%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                       | 4        | 1.14%   |
| Intel Ethernet Connection I217-LM                                               | 4        | 1.14%   |
| Intel Ethernet Connection (7) I219-LM                                           | 4        | 1.14%   |
| HTC (High Tech Computer) Desire HD (modem mode)                                 | 4        | 1.14%   |
| Aquantia AQtion AQC113CS NBase-T/IEEE 802.3an Ethernet Controller [Antigua 10G] | 4        | 1.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                        | 3        | 0.86%   |
| Realtek RTL8152 Fast Ethernet Adapter                                           | 3        | 0.86%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller               | 3        | 0.86%   |
| Nvidia MCP61 Ethernet                                                           | 3        | 0.86%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                         | 3        | 0.86%   |
| Intel Ethernet Controller I226-V                                                | 3        | 0.86%   |
| Intel Ethernet Connection (14) I219-V                                           | 3        | 0.86%   |
| Intel 82574L Gigabit Network Connection                                         | 3        | 0.86%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]               | 3        | 0.86%   |
| Samsung Galaxy series, misc. (tethering mode)                                   | 2        | 0.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                           | 2        | 0.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                        | 2        | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                   | 2        | 0.57%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                        | 2        | 0.57%   |
| MediaTek RMX3085                                                                | 2        | 0.57%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                         | 2        | 0.57%   |
| Intel I350 Gigabit Network Connection                                           | 2        | 0.57%   |
| Intel Ethernet Connection (2) I219-LM                                           | 2        | 0.57%   |
| Intel Ethernet Connection (2) I218-V                                            | 2        | 0.57%   |
| Intel Ethernet Connection (17) I219-LM                                          | 2        | 0.57%   |
| Intel Ethernet Connection (11) I219-V                                           | 2        | 0.57%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                            | 2        | 0.57%   |
| Intel 82579V Gigabit Network Connection                                         | 2        | 0.57%   |
| TP-Link USB 10/100 LAN                                                          | 1        | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 290      | 67.6%   |
| WiFi     | 135      | 31.47%  |
| Modem    | 4        | 0.93%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 231      | 76.74%  |
| WiFi     | 70       | 23.26%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 154      | 52.03%  |
| 2     | 108      | 36.49%  |
| 3     | 18       | 6.08%   |
| 0     | 9        | 3.04%   |
| 4     | 4        | 1.35%   |
| 6     | 2        | 0.68%   |
| 10    | 1        | 0.34%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 251      | 83.95%  |
| Yes  | 48       | 16.05%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 61       | 57.01%  |
| Cambridge Silicon Radio         | 18       | 16.82%  |
| MediaTek                        | 9        | 8.41%   |
| Realtek Semiconductor           | 5        | 4.67%   |
| IMC Networks                    | 3        | 2.8%    |
| Broadcom                        | 3        | 2.8%    |
| ASUSTek Computer                | 3        | 2.8%    |
| Apple                           | 2        | 1.87%   |
| TP-Link                         | 1        | 0.93%   |
| Ralink                          | 1        | 0.93%   |
| Qualcomm Atheros Communications | 1        | 0.93%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 18       | 16.82%  |
| Intel AX200 Bluetooth                                 | 17       | 15.89%  |
| Intel AX201 Bluetooth                                 | 10       | 9.35%   |
| MediaTek Wireless_Device                              | 9        | 8.41%   |
| Intel Wireless-AC 3168 Bluetooth                      | 9        | 8.41%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 6        | 5.61%   |
| Intel AX210 Bluetooth                                 | 6        | 5.61%   |
| Realtek Bluetooth Radio                               | 5        | 4.67%   |
| Intel Bluetooth wireless interface                    | 5        | 4.67%   |
| Intel Bluetooth Device                                | 3        | 2.8%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 3        | 2.8%    |
| Intel AX211 Bluetooth                                 | 2        | 1.87%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 2        | 1.87%   |
| ASUS Bluetooth Radio                                  | 2        | 1.87%   |
| TP-Link UB500 Adapter                                 | 1        | 0.93%   |
| Ralink RT3290 Bluetooth                               | 1        | 0.93%   |
| Qualcomm Atheros  Bluetooth Device                    | 1        | 0.93%   |
| IMC Networks Bluetooth Radio                          | 1        | 0.93%   |
| IMC Networks Bluetooth Device                         | 1        | 0.93%   |
| IMC Networks BCM20702A0                               | 1        | 0.93%   |
| Broadcom BCM2045 Bluetooth                            | 1        | 0.93%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 0.93%   |
| Apple Bluetooth USB Host Controller                   | 1        | 0.93%   |
| Apple Bluetooth Host Controller                       | 1        | 0.93%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 202      | 43.16%  |
| Nvidia                               | 119      | 25.43%  |
| AMD                                  | 95       | 20.3%   |
| C-Media Electronics                  | 7        | 1.5%    |
| Logitech                             | 4        | 0.85%   |
| ASUSTek Computer                     | 4        | 0.85%   |
| JMTek                                | 3        | 0.64%   |
| Generalplus Technology               | 3        | 0.64%   |
| XMOS                                 | 2        | 0.43%   |
| Texas Instruments                    | 2        | 0.43%   |
| SAVITECH                             | 2        | 0.43%   |
| Micro Star International             | 2        | 0.43%   |
| KORG                                 | 2        | 0.43%   |
| Focusrite-Novation                   | 2        | 0.43%   |
| Audio-Technica                       | 2        | 0.43%   |
| ZOOM                                 | 1        | 0.21%   |
| Yamaha                               | 1        | 0.21%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.21%   |
| Sony                                 | 1        | 0.21%   |
| Realtek Semiconductor                | 1        | 0.21%   |
| OPPO Electronics                     | 1        | 0.21%   |
| Novra/IDC/Wegener                    | 1        | 0.21%   |
| Microdia                             | 1        | 0.21%   |
| Harman                               | 1        | 0.21%   |
| GN Netcom                            | 1        | 0.21%   |
| Giga-Byte Technology                 | 1        | 0.21%   |
| Elite Silicon                        | 1        | 0.21%   |
| EDIFIER                              | 1        | 0.21%   |
| Dell                                 | 1        | 0.21%   |
| Creative Technology                  | 1        | 0.21%   |
| Creative Labs                        | 1        | 0.21%   |
| 2.4G Composite Device                | 1        | 0.21%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 32       | 5.95%   |
| AMD Starship/Matisse HD Audio Controller                                   | 24       | 4.46%   |
| AMD Family 17h/19h HD Audio Controller                                     | 22       | 4.09%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 21       | 3.9%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 19       | 3.53%   |
| Intel Cannon Lake PCH cAVS                                                 | 18       | 3.35%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 17       | 3.16%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 16       | 2.97%   |
| Nvidia GP106 High Definition Audio Controller                              | 14       | 2.6%    |
| Intel Alder Lake-S HD Audio Controller                                     | 14       | 2.6%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 14       | 2.6%    |
| Intel 200 Series PCH HD Audio                                              | 13       | 2.42%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 11       | 2.04%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 10       | 1.86%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10       | 1.86%   |
| Nvidia GP108 High Definition Audio Controller                              | 9        | 1.67%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 9        | 1.67%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 9        | 1.67%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 8        | 1.49%   |
| Nvidia GP107GL High Definition Audio Controller                            | 7        | 1.3%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 7        | 1.3%    |
| Nvidia MCP61 High Definition Audio                                         | 6        | 1.12%   |
| Nvidia GF116 High Definition Audio Controller                              | 6        | 1.12%   |
| Nvidia GA102 High Definition Audio Controller                              | 6        | 1.12%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 6        | 1.12%   |
| Nvidia TU116 High Definition Audio Controller                              | 5        | 0.93%   |
| Nvidia GF108 High Definition Audio Controller                              | 5        | 0.93%   |
| Nvidia GA106 High Definition Audio Controller                              | 5        | 0.93%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 5        | 0.93%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 5        | 0.93%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5        | 0.93%   |
| AMD FCH Azalia Controller                                                  | 5        | 0.93%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5        | 0.93%   |
| Nvidia GP104 High Definition Audio Controller                              | 4        | 0.74%   |
| Nvidia GM206 High Definition Audio Controller                              | 4        | 0.74%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4        | 0.74%   |
| Nvidia GA104 High Definition Audio Controller                              | 4        | 0.74%   |
| Intel Comet Lake PCH-V cAVS                                                | 4        | 0.74%   |
| Intel Comet Lake PCH cAVS                                                  | 4        | 0.74%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4        | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 36       | 18.65%  |
| Crucial             | 33       | 17.1%   |
| Transcend           | 20       | 10.36%  |
| Unknown             | 19       | 9.84%   |
| A-DATA Technology   | 17       | 8.81%   |
| Samsung Electronics | 15       | 7.77%   |
| SK hynix            | 11       | 5.7%    |
| Micron Technology   | 11       | 5.7%    |
| G.Skill             | 4        | 2.07%   |
| Unknown             | 4        | 2.07%   |
| Unifosa             | 3        | 1.55%   |
| Team                | 3        | 1.55%   |
| Silicon Power       | 3        | 1.55%   |
| Patriot             | 2        | 1.04%   |
| KLEVV               | 2        | 1.04%   |
| ASint Technology    | 2        | 1.04%   |
| Apacer              | 2        | 1.04%   |
| V-Color             | 1        | 0.52%   |
| UMAX                | 1        | 0.52%   |
| Ramaxel Technology  | 1        | 0.52%   |
| GLOWAY              | 1        | 0.52%   |
| CUSO                | 1        | 0.52%   |
| Corsair             | 1        | 0.52%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s       | 4        | 1.94%   |
| Unknown                                                   | 4        | 1.94%   |
| Transcend RAM TS1GLK64V6H 8GB DIMM DDR3 1600MT/s          | 3        | 1.46%   |
| Transcend RAM Module 4GB DIMM DDR3 1600MT/s               | 3        | 1.46%   |
| A-DATA RAM Module 4096MB SODIMM DDR4 2400MT/s             | 3        | 1.46%   |
| A-DATA RAM DDR4 3000 2OZ 8GB DIMM DDR4 3000MT/s           | 3        | 1.46%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                  | 2        | 0.97%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1600MT/s         | 2        | 0.97%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s       | 2        | 0.97%   |
| SK hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2667MT/s      | 2        | 0.97%   |
| Silicon Power RAM SP008GBLTU160N02 8GB DIMM DDR3 1600MT/s | 2        | 0.97%   |
| Samsung RAM M393A2G40DB1-CRC 16GB DIMM DDR4 2400MT/s      | 2        | 0.97%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s    | 2        | 0.97%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s       | 2        | 0.97%   |
| Kingston RAM 99U5471-037.A00LF 8GB DIMM DDR3 1600MT/s     | 2        | 0.97%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s     | 2        | 0.97%   |
| Crucial RAM CT8G4SFS8266.M8FE 8GB SODIMM DDR4 2667MT/s    | 2        | 0.97%   |
| Crucial RAM CT8G4DFS8266.M8FD 8GB DIMM DDR4 3600MT/s      | 2        | 0.97%   |
| Crucial RAM BL16G36C16U4W.M16FE1 16GB DIMM DDR4 3733MT/s  | 2        | 0.97%   |
| A-DATA RAM Module 4GB DIMM DDR3 1333MT/s                  | 2        | 0.97%   |
| V-Color RAM TD4G8C11-H11 4GB DIMM DDR3 1600MT/s           | 1        | 0.49%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                 | 1        | 0.49%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                 | 1        | 0.49%   |
| Unknown RAM Module 8GB DIMM 667MT/s                       | 1        | 0.49%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s              | 1        | 0.49%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                   | 1        | 0.49%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                 | 1        | 0.49%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                 | 1        | 0.49%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                      | 1        | 0.49%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                   | 1        | 0.49%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 1        | 0.49%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                  | 1        | 0.49%   |
| Unknown RAM Module 2GB DIMM 800MT/s                       | 1        | 0.49%   |
| Unknown RAM Module 2GB DIMM 667MT/s                       | 1        | 0.49%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                      | 1        | 0.49%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s               | 1        | 0.49%   |
| Unknown RAM Module 1GB DIMM 533MT/s                       | 1        | 0.49%   |
| Unknown RAM Module 16GB SODIMM DDR4 2400MT/s              | 1        | 0.49%   |
| Unknown RAM Module 16384MB SODIMM DDR4 2400MT/s           | 1        | 0.49%   |
| Unknown RAM Module 16384MB DIMM DDR4 2133MT/s             | 1        | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 98       | 56.98%  |
| DDR3    | 45       | 26.16%  |
| Unknown | 10       | 5.81%   |
| DDR5    | 8        | 4.65%   |
| DDR2    | 6        | 3.49%   |
| SDRAM   | 4        | 2.33%   |
| DDR     | 1        | 0.58%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 148      | 86.05%  |
| SODIMM | 24       | 13.95%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 65       | 35.91%  |
| 16384 | 51       | 28.18%  |
| 4096  | 28       | 15.47%  |
| 32768 | 18       | 9.94%   |
| 2048  | 16       | 8.84%   |
| 1024  | 2        | 1.1%    |
| 65536 | 1        | 0.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 37       | 19.58%  |
| 3200  | 34       | 17.99%  |
| 2667  | 16       | 8.47%   |
| 2400  | 13       | 6.88%   |
| 2133  | 12       | 6.35%   |
| 1333  | 12       | 6.35%   |
| 3600  | 8        | 4.23%   |
| 800   | 6        | 3.17%   |
| 3733  | 5        | 2.65%   |
| 3000  | 5        | 2.65%   |
| 4800  | 4        | 2.12%   |
| 2933  | 4        | 2.12%   |
| 6000  | 3        | 1.59%   |
| 667   | 3        | 1.59%   |
| 4000  | 2        | 1.06%   |
| 3866  | 2        | 1.06%   |
| 3800  | 2        | 1.06%   |
| 3466  | 2        | 1.06%   |
| 3400  | 2        | 1.06%   |
| 2666  | 2        | 1.06%   |
| 1066  | 2        | 1.06%   |
| 5800  | 1        | 0.53%   |
| 5200  | 1        | 0.53%   |
| 4333  | 1        | 0.53%   |
| 3134  | 1        | 0.53%   |
| 2866  | 1        | 0.53%   |
| 2448  | 1        | 0.53%   |
| 2000  | 1        | 0.53%   |
| 1867  | 1        | 0.53%   |
| 1800  | 1        | 0.53%   |
| 1632  | 1        | 0.53%   |
| 1334  | 1        | 0.53%   |
| 533   | 1        | 0.53%   |
| 400   | 1        | 0.53%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 3        | 60%     |
| Seiko Epson         | 1        | 20%     |
| Prolific Technology | 1        | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seiko Epson XP-240 Series        | 1        | 20%     |
| Prolific PL2305 Parallel Port    | 1        | 20%     |
| HP LaserJet Professional P1102w  | 1        | 20%     |
| HP LaserJet Professional P 1102w | 1        | 20%     |
| HP LaserJet 1020                 | 1        | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 15       | 57.69%  |
| Sunplus Innovation Technology | 2        | 7.69%   |
| Microdia                      | 2        | 7.69%   |
| Generalplus Technology        | 2        | 7.69%   |
| Samsung Electronics           | 1        | 3.85%   |
| KYE Systems (Mouse Systems)   | 1        | 3.85%   |
| eMeet                         | 1        | 3.85%   |
| Apple                         | 1        | 3.85%   |
| A4Tech                        | 1        | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Logitech Webcam C270                            | 5        | 19.23%  |
| Logitech Webcam C120                            | 3        | 11.54%  |
| Logitech Webcam C930e                           | 2        | 7.69%   |
| Sunplus HanChen Wise Camera                     | 1        | 3.85%   |
| Sunplus ezcap U3 capture-04                     | 1        | 3.85%   |
| Samsung Galaxy series, misc. (MTP mode)         | 1        | 3.85%   |
| Microdia USB 2.0 Camera                         | 1        | 3.85%   |
| Microdia Integrated Camera                      | 1        | 3.85%   |
| Logitech Webcam C170                            | 1        | 3.85%   |
| Logitech QuickCam Sphere                        | 1        | 3.85%   |
| Logitech QuickCam Home                          | 1        | 3.85%   |
| Logitech QuickCam E 3500                        | 1        | 3.85%   |
| Logitech HD Pro Webcam C920                     | 1        | 3.85%   |
| KYE Systems (Mouse Systems) Genius WideCam F100 | 1        | 3.85%   |
| Generalplus CAMERA - UVC                        | 1        | 3.85%   |
| Generalplus 808 Camera                          | 1        | 3.85%   |
| eMeet HD Webcam C960                            | 1        | 3.85%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                 | 1        | 3.85%   |
| A4Tech FHD 1080P PC Camera                      | 1        | 3.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 242      | 80.67%  |
| 1     | 47       | 15.67%  |
| 2     | 5        | 1.67%   |
| 3     | 3        | 1%      |
| 5     | 2        | 0.67%   |
| 4     | 1        | 0.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 24       | 35.82%  |
| Net/wireless             | 12       | 17.91%  |
| Unassigned class         | 10       | 14.93%  |
| Communication controller | 7        | 10.45%  |
| Card reader              | 3        | 4.48%   |
| Storage/raid             | 2        | 2.99%   |
| Sound                    | 2        | 2.99%   |
| Net/ethernet             | 2        | 2.99%   |
| Bluetooth                | 2        | 2.99%   |
| Network                  | 1        | 1.49%   |
| Multimedia controller    | 1        | 1.49%   |
| Camera                   | 1        | 1.49%   |


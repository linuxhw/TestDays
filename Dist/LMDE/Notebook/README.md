LMDE - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------

A project to collect tested hardware configurations for LMDE.

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

Total: 455

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Pavilion 17                 | [1efb06e77e](https://linux-hardware.org/?probe=1efb06e77e) | Jul 01, 2022 |
| HP            | Compaq 15                   | [fb14abab4d](https://linux-hardware.org/?probe=fb14abab4d) | Jun 30, 2022 |
| Framework     | Laptop                      | [8a44001ebb](https://linux-hardware.org/?probe=8a44001ebb) | Jun 30, 2022 |
| Framework     | Laptop                      | [61a6480a38](https://linux-hardware.org/?probe=61a6480a38) | Jun 30, 2022 |
| Dell          | Inspiron 5370               | [e848f3258c](https://linux-hardware.org/?probe=e848f3258c) | Jun 26, 2022 |
| Unknown       | Unknown                     | [a8b7e4a9fe](https://linux-hardware.org/?probe=a8b7e4a9fe) | Jun 26, 2022 |
| HP            | Laptop 15z-ef2xxx           | [f54df47fa0](https://linux-hardware.org/?probe=f54df47fa0) | Jun 25, 2022 |
| Dell          | Inspiron 3505               | [1eaa95f069](https://linux-hardware.org/?probe=1eaa95f069) | Jun 24, 2022 |
| HP            | Laptop 15z-ef2xxx           | [64e65ab80b](https://linux-hardware.org/?probe=64e65ab80b) | Jun 24, 2022 |
| HP            | Laptop 15z-ef2xxx           | [879d7a231f](https://linux-hardware.org/?probe=879d7a231f) | Jun 24, 2022 |
| Lenovo        | ThinkPad T450 20BUS0QT04    | [0c96d2bc24](https://linux-hardware.org/?probe=0c96d2bc24) | Jun 24, 2022 |
| HP            | Laptop 15-bw0xx             | [a55d01829f](https://linux-hardware.org/?probe=a55d01829f) | Jun 23, 2022 |
| HP            | EliteBook 8730w             | [14135356d6](https://linux-hardware.org/?probe=14135356d6) | Jun 20, 2022 |
| MSI           | U180                        | [7aa374e07e](https://linux-hardware.org/?probe=7aa374e07e) | Jun 20, 2022 |
| Acer          | Aspire 5930                 | [348ec06fd0](https://linux-hardware.org/?probe=348ec06fd0) | Jun 18, 2022 |
| ASUSTek       | 1005P                       | [4bd178fe29](https://linux-hardware.org/?probe=4bd178fe29) | Jun 14, 2022 |
| Apple         | MacBookPro14,1              | [88294cb5aa](https://linux-hardware.org/?probe=88294cb5aa) | Jun 12, 2022 |
| Apple         | MacBookPro14,1              | [281724432e](https://linux-hardware.org/?probe=281724432e) | Jun 12, 2022 |
| Acer          | Aspire One 522              | [7f4af0143d](https://linux-hardware.org/?probe=7f4af0143d) | Jun 11, 2022 |
| Apple         | MacBookAir6,1               | [f0883ab59b](https://linux-hardware.org/?probe=f0883ab59b) | Jun 10, 2022 |
| HP            | 255 G5 Notebook PC          | [519a18864f](https://linux-hardware.org/?probe=519a18864f) | Jun 09, 2022 |
| Sony          | SVE1713Y1RB                 | [4a1bc35dda](https://linux-hardware.org/?probe=4a1bc35dda) | Jun 09, 2022 |
| Lenovo        | Z50-70 20354                | [57582f68b6](https://linux-hardware.org/?probe=57582f68b6) | Jun 08, 2022 |
| Multilaser    | PC150                       | [ee0a35cc62](https://linux-hardware.org/?probe=ee0a35cc62) | Jun 08, 2022 |
| Lenovo        | Z50-70 20354                | [870233669c](https://linux-hardware.org/?probe=870233669c) | Jun 07, 2022 |
| Alienware     | 14                          | [7dabcbc673](https://linux-hardware.org/?probe=7dabcbc673) | Jun 07, 2022 |
| Acer          | Swift SF515-51T             | [1d0b1a1c50](https://linux-hardware.org/?probe=1d0b1a1c50) | May 31, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [0e59a69b8d](https://linux-hardware.org/?probe=0e59a69b8d) | May 30, 2022 |
| HP            | Laptop 14-cf3xxx            | [9e4cd6dab4](https://linux-hardware.org/?probe=9e4cd6dab4) | May 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [67aa7158d3](https://linux-hardware.org/?probe=67aa7158d3) | May 24, 2022 |
| HP            | Laptop 14-df0xxx            | [94992083bc](https://linux-hardware.org/?probe=94992083bc) | May 24, 2022 |
| Acer          | Aspire One 522              | [0ac567a5cf](https://linux-hardware.org/?probe=0ac567a5cf) | May 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [48c8683aa8](https://linux-hardware.org/?probe=48c8683aa8) | May 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [8d30966279](https://linux-hardware.org/?probe=8d30966279) | May 20, 2022 |
| HP            | ZBook Fury 17.3 inch G8 ... | [8757941b52](https://linux-hardware.org/?probe=8757941b52) | May 17, 2022 |
| Acer          | Aspire V3-571G              | [91700e1cb8](https://linux-hardware.org/?probe=91700e1cb8) | May 16, 2022 |
| Dell          | XPS 13 9305                 | [e9310a7ede](https://linux-hardware.org/?probe=e9310a7ede) | May 15, 2022 |
| Dell          | XPS 13 9305                 | [3f8becd67d](https://linux-hardware.org/?probe=3f8becd67d) | May 15, 2022 |
| Dell          | Inspiron 5566               | [d01652f69f](https://linux-hardware.org/?probe=d01652f69f) | May 15, 2022 |
| Dell          | Inspiron 5559               | [4b0c466a88](https://linux-hardware.org/?probe=4b0c466a88) | May 15, 2022 |
| Howard Com... | R7X                         | [bc6d6a31eb](https://linux-hardware.org/?probe=bc6d6a31eb) | May 13, 2022 |
| HP            | Notebook                    | [200c1dabff](https://linux-hardware.org/?probe=200c1dabff) | May 09, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [0d64940271](https://linux-hardware.org/?probe=0d64940271) | May 09, 2022 |
| HP            | ENVY 17                     | [a503de2c1f](https://linux-hardware.org/?probe=a503de2c1f) | May 08, 2022 |
| Apple         | MacBookAir7,2               | [54815db142](https://linux-hardware.org/?probe=54815db142) | May 07, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | [57e085245c](https://linux-hardware.org/?probe=57e085245c) | May 07, 2022 |
| Philco        | 10D                         | [d2f71d99cd](https://linux-hardware.org/?probe=d2f71d99cd) | May 05, 2022 |
| Philco        | 10D                         | [9882f4ca80](https://linux-hardware.org/?probe=9882f4ca80) | May 05, 2022 |
| Acer          | Aspire E1-532               | [a7305e2070](https://linux-hardware.org/?probe=a7305e2070) | May 04, 2022 |
| Lenovo        | ThinkPad T480 20L6S1RN00    | [eb55b73c5a](https://linux-hardware.org/?probe=eb55b73c5a) | May 03, 2022 |
| Toshiba       | Satellite M55               | [9d5733c6fc](https://linux-hardware.org/?probe=9d5733c6fc) | May 02, 2022 |
| HP            | Presario C500 (GF581UA#A... | [0e01914db4](https://linux-hardware.org/?probe=0e01914db4) | Apr 30, 2022 |
| HP            | EliteBook 840 G1            | [53bceed0aa](https://linux-hardware.org/?probe=53bceed0aa) | Apr 29, 2022 |
| Acer          | AOD270                      | [d0fae524f9](https://linux-hardware.org/?probe=d0fae524f9) | Apr 29, 2022 |
| Acer          | AOD270                      | [44d897bc15](https://linux-hardware.org/?probe=44d897bc15) | Apr 29, 2022 |
| Acer          | Aspire E5-553G              | [00a648bda6](https://linux-hardware.org/?probe=00a648bda6) | Apr 28, 2022 |
| Acer          | Aspire E5-553G              | [4646f6cd23](https://linux-hardware.org/?probe=4646f6cd23) | Apr 28, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [ff8e46a260](https://linux-hardware.org/?probe=ff8e46a260) | Apr 27, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [0a6534997e](https://linux-hardware.org/?probe=0a6534997e) | Apr 27, 2022 |
| Apple         | MacBookPro14,1              | [ce4f3d8ec8](https://linux-hardware.org/?probe=ce4f3d8ec8) | Apr 24, 2022 |
| Acer          | AOD270                      | [b53cedd40c](https://linux-hardware.org/?probe=b53cedd40c) | Apr 23, 2022 |
| Dixonsxp      | Unknown                     | [65e40dacf4](https://linux-hardware.org/?probe=65e40dacf4) | Apr 20, 2022 |
| Toshiba       | Satellite L455              | [7f0bad47af](https://linux-hardware.org/?probe=7f0bad47af) | Apr 19, 2022 |
| Toshiba       | Satellite L455              | [3a0c54144d](https://linux-hardware.org/?probe=3a0c54144d) | Apr 19, 2022 |
| Dell          | 0X574R                      | [6da5c2339f](https://linux-hardware.org/?probe=6da5c2339f) | Apr 18, 2022 |
| HP            | 14                          | [71f296bd93](https://linux-hardware.org/?probe=71f296bd93) | Apr 17, 2022 |
| Dell          | Latitude 3410               | [78396d572c](https://linux-hardware.org/?probe=78396d572c) | Apr 15, 2022 |
| ASUSTek       | N61Jv                       | [959c5f2238](https://linux-hardware.org/?probe=959c5f2238) | Apr 14, 2022 |
| Acer          | AOA110                      | [cba10fc182](https://linux-hardware.org/?probe=cba10fc182) | Apr 13, 2022 |
| Howard Com... | R7X                         | [e0f3701b1b](https://linux-hardware.org/?probe=e0f3701b1b) | Apr 12, 2022 |
| Lenovo        | ThinkPad W541 20EGS24J00    | [6fbd04d8fd](https://linux-hardware.org/?probe=6fbd04d8fd) | Apr 11, 2022 |
| Howard Com... | R7X                         | [5885bbaa90](https://linux-hardware.org/?probe=5885bbaa90) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | [5b1a24bf51](https://linux-hardware.org/?probe=5b1a24bf51) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | [b2adbbe7d0](https://linux-hardware.org/?probe=b2adbbe7d0) | Apr 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [4d5998459b](https://linux-hardware.org/?probe=4d5998459b) | Apr 09, 2022 |
| HP            | Presario C500 (RY512EA#A... | [4ef049d490](https://linux-hardware.org/?probe=4ef049d490) | Apr 09, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | [613d6e7d3c](https://linux-hardware.org/?probe=613d6e7d3c) | Apr 07, 2022 |
| Dell          | Latitude 5511               | [2cb0a3e451](https://linux-hardware.org/?probe=2cb0a3e451) | Apr 06, 2022 |
| Dell          | Precision 7520              | [7404842400](https://linux-hardware.org/?probe=7404842400) | Apr 05, 2022 |
| LincPlus      | LINNCPLUS P1                | [22406313dc](https://linux-hardware.org/?probe=22406313dc) | Apr 02, 2022 |
| Toshiba       | Satellite L455              | [699e7d272d](https://linux-hardware.org/?probe=699e7d272d) | Apr 02, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [387b77f172](https://linux-hardware.org/?probe=387b77f172) | Apr 01, 2022 |
| ASUSTek       | 901                         | [d118ee90d5](https://linux-hardware.org/?probe=d118ee90d5) | Apr 01, 2022 |
| HP            | ProBook 6570b               | [0609df27fa](https://linux-hardware.org/?probe=0609df27fa) | Mar 31, 2022 |
| Lenovo        | IdeaPad S110 20126          | [9113320f2f](https://linux-hardware.org/?probe=9113320f2f) | Mar 31, 2022 |
| Lenovo        | IdeaPad S110 20126          | [d02cab0935](https://linux-hardware.org/?probe=d02cab0935) | Mar 30, 2022 |
| Packard Be... | DOT S                       | [85e7386152](https://linux-hardware.org/?probe=85e7386152) | Mar 28, 2022 |
| Packard Be... | DOT S                       | [edef12b9d5](https://linux-hardware.org/?probe=edef12b9d5) | Mar 28, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [b2e70b8251](https://linux-hardware.org/?probe=b2e70b8251) | Mar 28, 2022 |
| Dell          | Latitude E6400              | [01815a09bb](https://linux-hardware.org/?probe=01815a09bb) | Mar 27, 2022 |
| Dell          | Latitude D620               | [172cd26e35](https://linux-hardware.org/?probe=172cd26e35) | Mar 26, 2022 |
| Toshiba       | Satellite L455              | [90334cf68d](https://linux-hardware.org/?probe=90334cf68d) | Mar 26, 2022 |
| Dell          | Precision M4400             | [5172327d82](https://linux-hardware.org/?probe=5172327d82) | Mar 25, 2022 |
| Medion        | E6220                       | [e739ef27a1](https://linux-hardware.org/?probe=e739ef27a1) | Mar 24, 2022 |
| HP            | ProBook 6465b               | [2e1792442b](https://linux-hardware.org/?probe=2e1792442b) | Mar 24, 2022 |
| HP            | ProBook 6465b               | [51a296abf8](https://linux-hardware.org/?probe=51a296abf8) | Mar 24, 2022 |
| Acer          | Aspire 7745G                | [3f4c13ee47](https://linux-hardware.org/?probe=3f4c13ee47) | Mar 23, 2022 |
| HP            | 255 G7 Notebook PC          | [f8561c65dc](https://linux-hardware.org/?probe=f8561c65dc) | Mar 21, 2022 |
| Acer          | TravelMate 420              | [13cae0e399](https://linux-hardware.org/?probe=13cae0e399) | Mar 14, 2022 |
| Lenovo        | IdeaPad Z470                | [b1ca65b3e0](https://linux-hardware.org/?probe=b1ca65b3e0) | Mar 08, 2022 |
| ASUSTek       | X101CH                      | [486f5c28ad](https://linux-hardware.org/?probe=486f5c28ad) | Mar 07, 2022 |
| Dell          | Latitude D620               | [d4e50f40f3](https://linux-hardware.org/?probe=d4e50f40f3) | Mar 06, 2022 |
| HP            | ENVY 6                      | [23f60a7428](https://linux-hardware.org/?probe=23f60a7428) | Mar 02, 2022 |
| Lenovo        | IdeaPad Z470                | [d163816373](https://linux-hardware.org/?probe=d163816373) | Mar 02, 2022 |
| ASUSTek       | UX490UAR                    | [6b6c4bd7b7](https://linux-hardware.org/?probe=6b6c4bd7b7) | Feb 28, 2022 |
| ASUSTek       | UX490UAR                    | [544979fc4f](https://linux-hardware.org/?probe=544979fc4f) | Feb 27, 2022 |
| Fujitsu Si... | LIFEBOOK S7020              | [4bd308dadf](https://linux-hardware.org/?probe=4bd308dadf) | Feb 26, 2022 |
| Fujitsu Si... | LIFEBOOK S7020              | [ec2491adc1](https://linux-hardware.org/?probe=ec2491adc1) | Feb 26, 2022 |
| Acer          | Swift SF315-52              | [74009233c2](https://linux-hardware.org/?probe=74009233c2) | Feb 19, 2022 |
| Lenovo        | ThinkPad W541 20EGS24J00    | [e2ab1c19df](https://linux-hardware.org/?probe=e2ab1c19df) | Feb 18, 2022 |
| HP            | Laptop 14-bs0xx             | [2b5b67148b](https://linux-hardware.org/?probe=2b5b67148b) | Feb 18, 2022 |
| EVOO          | EVC141-12                   | [25710a76b8](https://linux-hardware.org/?probe=25710a76b8) | Feb 18, 2022 |
| Samsung       | NC210/NC110                 | [bf2672168d](https://linux-hardware.org/?probe=bf2672168d) | Feb 14, 2022 |
| Samsung       | NC210/NC110                 | [bcbb1884aa](https://linux-hardware.org/?probe=bcbb1884aa) | Feb 13, 2022 |
| ASUSTek       | X101CH                      | [82661c6a9b](https://linux-hardware.org/?probe=82661c6a9b) | Feb 12, 2022 |
| ASUSTek       | 901                         | [27a497fdf8](https://linux-hardware.org/?probe=27a497fdf8) | Feb 04, 2022 |
| Acer          | Aspire 3820                 | [e6091c93a9](https://linux-hardware.org/?probe=e6091c93a9) | Feb 02, 2022 |
| Toshiba       | Satellite A200              | [9086ec49b6](https://linux-hardware.org/?probe=9086ec49b6) | Jan 21, 2022 |
| LG Electro... | A530-T.BE76P1               | [9fdbf19ebf](https://linux-hardware.org/?probe=9fdbf19ebf) | Jan 09, 2022 |
| Google        | Falco                       | [f450676688](https://linux-hardware.org/?probe=f450676688) | Jan 09, 2022 |
| Packard Be... | EasyNote TE69BM             | [526fc1b476](https://linux-hardware.org/?probe=526fc1b476) | Jan 05, 2022 |
| LG Electro... | E500-S.AP17B                | [675eb28882](https://linux-hardware.org/?probe=675eb28882) | Jan 05, 2022 |
| LG Electro... | E500-S.AP17B                | [203577c78f](https://linux-hardware.org/?probe=203577c78f) | Jan 05, 2022 |
| Dell          | System Inspiron N7110       | [41e93113b5](https://linux-hardware.org/?probe=41e93113b5) | Jan 05, 2022 |
| Dell          | System Inspiron N7110       | [c977f6d6af](https://linux-hardware.org/?probe=c977f6d6af) | Jan 05, 2022 |
| ASUSTek       | K46CA                       | [61978f9418](https://linux-hardware.org/?probe=61978f9418) | Jan 04, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [9d4bddea4d](https://linux-hardware.org/?probe=9d4bddea4d) | Jan 03, 2022 |
| Advent        | Monza T100                  | [7355d1ae53](https://linux-hardware.org/?probe=7355d1ae53) | Dec 23, 2021 |
| Acer          | Aspire V5-573G              | [4c03d73b65](https://linux-hardware.org/?probe=4c03d73b65) | Dec 18, 2021 |
| HP            | Pavilion 14                 | [be9e6368e4](https://linux-hardware.org/?probe=be9e6368e4) | Dec 17, 2021 |
| Acer          | Aspire 3820                 | [b2f24124da](https://linux-hardware.org/?probe=b2f24124da) | Dec 14, 2021 |
| Acer          | Aspire 3820                 | [c4ed088328](https://linux-hardware.org/?probe=c4ed088328) | Dec 14, 2021 |
| Sony          | VPCP116KG                   | [237c9f66e1](https://linux-hardware.org/?probe=237c9f66e1) | Dec 13, 2021 |
| Fujitsu       | STYLISTIC Q550              | [e5d7b73e7f](https://linux-hardware.org/?probe=e5d7b73e7f) | Dec 12, 2021 |
| Fujitsu       | STYLISTIC Q550              | [8138236f20](https://linux-hardware.org/?probe=8138236f20) | Dec 12, 2021 |
| Lenovo        | G40-30 80FY                 | [43ff865e00](https://linux-hardware.org/?probe=43ff865e00) | Nov 28, 2021 |
| HP            | Pavilion dv6                | [5300296119](https://linux-hardware.org/?probe=5300296119) | Nov 27, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [bb0a461d82](https://linux-hardware.org/?probe=bb0a461d82) | Nov 21, 2021 |
| Lenovo        | G50-45 80E3                 | [024686087f](https://linux-hardware.org/?probe=024686087f) | Nov 20, 2021 |
| Samsung       | 305U1A                      | [c602ad4903](https://linux-hardware.org/?probe=c602ad4903) | Nov 18, 2021 |
| Acer          | Aspire 3000                 | [86d2f89f59](https://linux-hardware.org/?probe=86d2f89f59) | Nov 12, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | [688e4047ce](https://linux-hardware.org/?probe=688e4047ce) | Nov 11, 2021 |
| Acer          | Aspire 3000                 | [dad287d5a1](https://linux-hardware.org/?probe=dad287d5a1) | Nov 11, 2021 |
| Toshiba       | Satellite L50-C             | [5a9ebbcad0](https://linux-hardware.org/?probe=5a9ebbcad0) | Nov 09, 2021 |
| Acer          | Aspire E5-411               | [0155c64e23](https://linux-hardware.org/?probe=0155c64e23) | Nov 04, 2021 |
| Acer          | Aspire E5-411               | [63287ab4e6](https://linux-hardware.org/?probe=63287ab4e6) | Nov 02, 2021 |
| Dell          | Latitude D630               | [ac9f57ab8f](https://linux-hardware.org/?probe=ac9f57ab8f) | Nov 02, 2021 |
| TUXEDO        | BC1510 1710                 | [90be7d16be](https://linux-hardware.org/?probe=90be7d16be) | Oct 24, 2021 |
| TUXEDO        | BC1510 1710                 | [49b52175c5](https://linux-hardware.org/?probe=49b52175c5) | Oct 24, 2021 |
| Acer          | Aspire A315-55G             | [5b965ea234](https://linux-hardware.org/?probe=5b965ea234) | Oct 17, 2021 |
| Acer          | Aspire A315-55G             | [3a5976d4eb](https://linux-hardware.org/?probe=3a5976d4eb) | Oct 17, 2021 |
| Acer          | Swift SF515-51T             | [203a3b399d](https://linux-hardware.org/?probe=203a3b399d) | Oct 13, 2021 |
| Medion        | P6670 MD99960               | [eaa186d207](https://linux-hardware.org/?probe=eaa186d207) | Oct 12, 2021 |
| Medion        | P6670 MD99960               | [d42f345fc5](https://linux-hardware.org/?probe=d42f345fc5) | Oct 12, 2021 |
| HP            | 520                         | [4aea2d24b1](https://linux-hardware.org/?probe=4aea2d24b1) | Oct 10, 2021 |
| Dell          | Precision M2800             | [b046a9dfe3](https://linux-hardware.org/?probe=b046a9dfe3) | Oct 08, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | [6e927dafdd](https://linux-hardware.org/?probe=6e927dafdd) | Sep 28, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | [ccccaee5bb](https://linux-hardware.org/?probe=ccccaee5bb) | Sep 28, 2021 |
| Apple         | MacBookPro5,4               | [633c289440](https://linux-hardware.org/?probe=633c289440) | Sep 28, 2021 |
| Apple         | MacBookPro5,4               | [a6d07be7c9](https://linux-hardware.org/?probe=a6d07be7c9) | Sep 27, 2021 |
| Apple         | MacBookPro5,4               | [d5625a9406](https://linux-hardware.org/?probe=d5625a9406) | Sep 24, 2021 |
| Sony          | VPCS131FM                   | [b5bba0e07f](https://linux-hardware.org/?probe=b5bba0e07f) | Sep 22, 2021 |
| Sony          | VPCS131FM                   | [54923e2372](https://linux-hardware.org/?probe=54923e2372) | Sep 22, 2021 |
| Qbex          | UDPAIOQBEX01                | [34c385cfe4](https://linux-hardware.org/?probe=34c385cfe4) | Sep 13, 2021 |
| Acer          | Aspire 4320                 | [fae514c059](https://linux-hardware.org/?probe=fae514c059) | Sep 12, 2021 |
| IBM           | ThinkPad T41 23737JY        | [86cf78a3cf](https://linux-hardware.org/?probe=86cf78a3cf) | Sep 09, 2021 |
| HP            | 250 G2                      | [64f9cfdbab](https://linux-hardware.org/?probe=64f9cfdbab) | Sep 09, 2021 |
| HP            | 250 G2                      | [4fb0a2eab3](https://linux-hardware.org/?probe=4fb0a2eab3) | Sep 09, 2021 |
| Acer          | Aspire A315-31              | [10052076e0](https://linux-hardware.org/?probe=10052076e0) | Sep 09, 2021 |
| Acer          | Aspire A315-31              | [8a0df29327](https://linux-hardware.org/?probe=8a0df29327) | Sep 09, 2021 |
| LG Electro... | A530-T.BE76P1               | [844d7b2492](https://linux-hardware.org/?probe=844d7b2492) | Sep 09, 2021 |
| Matsushita... | CF-19DDGZXVM                | [6f54a42d76](https://linux-hardware.org/?probe=6f54a42d76) | Sep 08, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | [fdb725803b](https://linux-hardware.org/?probe=fdb725803b) | Sep 01, 2021 |
| Lenovo        | Yoga 2 11 20428             | [52474e968d](https://linux-hardware.org/?probe=52474e968d) | Sep 01, 2021 |
| Lenovo        | Yoga 2 11 20428             | [c4e6145a5f](https://linux-hardware.org/?probe=c4e6145a5f) | Sep 01, 2021 |
| Dell          | XPS M1330                   | [9dbd1f4ad9](https://linux-hardware.org/?probe=9dbd1f4ad9) | Aug 28, 2021 |
| ASUSTek       | 1201HA                      | [eadb8752c9](https://linux-hardware.org/?probe=eadb8752c9) | Aug 28, 2021 |
| HP            | Pavilion dv2000 (RD665EA... | [3b6dfaf6db](https://linux-hardware.org/?probe=3b6dfaf6db) | Aug 25, 2021 |
| Fujitsu       | LIFEBOOK A556/G             | [7706314dbc](https://linux-hardware.org/?probe=7706314dbc) | Aug 24, 2021 |
| Itautec       | W7655                       | [82b2d38326](https://linux-hardware.org/?probe=82b2d38326) | Aug 24, 2021 |
| Itautec       | W7655                       | [5952ec3a0f](https://linux-hardware.org/?probe=5952ec3a0f) | Aug 24, 2021 |
| HP            | 14                          | [e6bbdc5a92](https://linux-hardware.org/?probe=e6bbdc5a92) | Aug 24, 2021 |
| ASUSTek       | M51Sn                       | [5acb8c28ad](https://linux-hardware.org/?probe=5acb8c28ad) | Aug 21, 2021 |
| Packard Be... | EasyNote_NJ66               | [03c09865f3](https://linux-hardware.org/?probe=03c09865f3) | Aug 19, 2021 |
| ASUSTek       | N550JV                      | [f56a2bd3fa](https://linux-hardware.org/?probe=f56a2bd3fa) | Aug 14, 2021 |
| Toshiba       | Satellite M100              | [8dff0ec788](https://linux-hardware.org/?probe=8dff0ec788) | Aug 10, 2021 |
| Toshiba       | Satellite M100              | [06e766539d](https://linux-hardware.org/?probe=06e766539d) | Aug 10, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | [8648635717](https://linux-hardware.org/?probe=8648635717) | Aug 07, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | [16bec20604](https://linux-hardware.org/?probe=16bec20604) | Aug 06, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | [dec7f65882](https://linux-hardware.org/?probe=dec7f65882) | Aug 06, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | [53ee243536](https://linux-hardware.org/?probe=53ee243536) | Aug 01, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | [eafe3a403f](https://linux-hardware.org/?probe=eafe3a403f) | Jul 30, 2021 |
| Toshiba       | Satellite L855              | [354b3bf7c6](https://linux-hardware.org/?probe=354b3bf7c6) | Jul 30, 2021 |
| ASUSTek       | 1201NL                      | [1ff8ed5a66](https://linux-hardware.org/?probe=1ff8ed5a66) | Jul 29, 2021 |
| ASUSTek       | 1201NL                      | [78fb5dfca9](https://linux-hardware.org/?probe=78fb5dfca9) | Jul 29, 2021 |
| HP            | EliteBook 8470p             | [5ea0d9d644](https://linux-hardware.org/?probe=5ea0d9d644) | Jul 29, 2021 |
| Dell          | Inspiron 15-3567            | [19a4054ab4](https://linux-hardware.org/?probe=19a4054ab4) | Jul 28, 2021 |
| Dell          | Inspiron 15-3567            | [bc64d314a1](https://linux-hardware.org/?probe=bc64d314a1) | Jul 28, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [10ca362cf0](https://linux-hardware.org/?probe=10ca362cf0) | Jul 19, 2021 |
| Dell          | XPS M1330                   | [55de50364d](https://linux-hardware.org/?probe=55de50364d) | Jul 17, 2021 |
| HP            | Compaq nc6400 (RH478EA#A... | [a3f3785bc1](https://linux-hardware.org/?probe=a3f3785bc1) | Jul 15, 2021 |
| Dell          | Latitude E5520              | [9278405254](https://linux-hardware.org/?probe=9278405254) | Jul 13, 2021 |
| Fujitsu Si... | AMILO Pa 2510               | [a4303cc0cf](https://linux-hardware.org/?probe=a4303cc0cf) | Jul 12, 2021 |
| Qbex          | UDPAIOQBEX01                | [9b96573429](https://linux-hardware.org/?probe=9b96573429) | Jul 11, 2021 |
| Dell          | Inspiron 1526               | [515fc96089](https://linux-hardware.org/?probe=515fc96089) | Jul 11, 2021 |
| ASUSTek       | M6Ne                        | [ae1c7d3df6](https://linux-hardware.org/?probe=ae1c7d3df6) | Jul 11, 2021 |
| Dell          | Inspiron 7520               | [fbc1ae17b4](https://linux-hardware.org/?probe=fbc1ae17b4) | Jul 10, 2021 |
| Dell          | Inspiron 7520               | [e9bbf0622c](https://linux-hardware.org/?probe=e9bbf0622c) | Jul 10, 2021 |
| HP            | Laptop 14-df0xxx            | [ce0ac9c2fe](https://linux-hardware.org/?probe=ce0ac9c2fe) | Jul 10, 2021 |
| Samsung       | R59/R60/R61                 | [c0f5798a5b](https://linux-hardware.org/?probe=c0f5798a5b) | Jun 28, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | [f9a80b7b6b](https://linux-hardware.org/?probe=f9a80b7b6b) | Jun 28, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | [c7ddbbda0a](https://linux-hardware.org/?probe=c7ddbbda0a) | Jun 27, 2021 |
| Lenovo        | ThinkPad X100e 28762FP      | [95661d2e39](https://linux-hardware.org/?probe=95661d2e39) | Jun 27, 2021 |
| SAELITE       | ES1AU11                     | [267ea9c15e](https://linux-hardware.org/?probe=267ea9c15e) | Jun 26, 2021 |
| Acer          | Aspire 3000                 | [d0c68c57a8](https://linux-hardware.org/?probe=d0c68c57a8) | Jun 26, 2021 |
| Samsung       | RV413/RV513                 | [f6aab08062](https://linux-hardware.org/?probe=f6aab08062) | Jun 26, 2021 |
| Gateway       | M675                        | [ebdf5aa678](https://linux-hardware.org/?probe=ebdf5aa678) | Jun 25, 2021 |
| Acer          | Aspire one                  | [adae8c183d](https://linux-hardware.org/?probe=adae8c183d) | Jun 22, 2021 |
| HP            | Compaq nc6400 (RH478EA#A... | [b96ab4b06e](https://linux-hardware.org/?probe=b96ab4b06e) | Jun 18, 2021 |
| HP            | Presario R4100 (EC375UA#... | [9072bce23d](https://linux-hardware.org/?probe=9072bce23d) | Jun 17, 2021 |
| HP            | Presario R4100 (EC375UA#... | [b557ccbf94](https://linux-hardware.org/?probe=b557ccbf94) | Jun 17, 2021 |
| Dell          | Latitude E6410              | [bd3a2db03c](https://linux-hardware.org/?probe=bd3a2db03c) | Jun 16, 2021 |
| HP            | Notebook                    | [611efdde0d](https://linux-hardware.org/?probe=611efdde0d) | Jun 15, 2021 |
| ASUSTek       | X550LN                      | [67bbff8363](https://linux-hardware.org/?probe=67bbff8363) | Jun 11, 2021 |
| Gateway       | LT40                        | [fe2551cb8b](https://linux-hardware.org/?probe=fe2551cb8b) | Jun 11, 2021 |
| Acer          | Aspire 3000                 | [f6a944ee4a](https://linux-hardware.org/?probe=f6a944ee4a) | Jun 09, 2021 |
| Sony          | VPCEB3L1E                   | [bc3c3b537b](https://linux-hardware.org/?probe=bc3c3b537b) | Jun 06, 2021 |
| HP            | Laptop 15-dw0xxx            | [4f752689ed](https://linux-hardware.org/?probe=4f752689ed) | Jun 03, 2021 |
| Gateway       | LT40                        | [6a966fe471](https://linux-hardware.org/?probe=6a966fe471) | Jun 01, 2021 |
| ASUSTek       | X555UJ                      | [9c148a1665](https://linux-hardware.org/?probe=9c148a1665) | May 25, 2021 |
| HP            | Pavilion dv6                | [fb309a7f37](https://linux-hardware.org/?probe=fb309a7f37) | May 17, 2021 |
| Lenovo        | ThinkPad L450 20DSS00N18    | [85f3722d36](https://linux-hardware.org/?probe=85f3722d36) | May 12, 2021 |
| ASUSTek       | X550LN                      | [4f117c46f3](https://linux-hardware.org/?probe=4f117c46f3) | May 09, 2021 |
| Acer          | Aspire E5-571               | [2c91167099](https://linux-hardware.org/?probe=2c91167099) | May 07, 2021 |
| Acer          | Aspire E5-571               | [c0b2f54ba4](https://linux-hardware.org/?probe=c0b2f54ba4) | May 07, 2021 |
| HP            | 530                         | [e94b7216d1](https://linux-hardware.org/?probe=e94b7216d1) | May 06, 2021 |
| HP            | 530                         | [8e3d65488a](https://linux-hardware.org/?probe=8e3d65488a) | May 06, 2021 |
| Acer          | Aspire A515-41G             | [38e06153e9](https://linux-hardware.org/?probe=38e06153e9) | May 04, 2021 |
| Dell          | Inspiron 7520               | [3a72f19dd7](https://linux-hardware.org/?probe=3a72f19dd7) | May 01, 2021 |
| Toshiba       | dynabook Satellite J61 1... | [0b4c4a93f1](https://linux-hardware.org/?probe=0b4c4a93f1) | Apr 29, 2021 |
| Lenovo        | ThinkPad X60 1706AA7        | [34a54e1198](https://linux-hardware.org/?probe=34a54e1198) | Apr 27, 2021 |
| Lenovo        | ThinkPad SL510 28752NG      | [66346c1594](https://linux-hardware.org/?probe=66346c1594) | Apr 26, 2021 |
| Unknown       | Unknown                     | [e45a412c3d](https://linux-hardware.org/?probe=e45a412c3d) | Apr 26, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [f961a0339b](https://linux-hardware.org/?probe=f961a0339b) | Apr 22, 2021 |
| HP            | Pavilion dv7                | [662a781c83](https://linux-hardware.org/?probe=662a781c83) | Apr 22, 2021 |
| HP            | Pavilion dv7                | [edf38b6c4a](https://linux-hardware.org/?probe=edf38b6c4a) | Apr 21, 2021 |
| HP            | 255 G7 Notebook PC          | [b243c0380f](https://linux-hardware.org/?probe=b243c0380f) | Apr 21, 2021 |
| HP            | Pavilion dv7                | [0c3668cad6](https://linux-hardware.org/?probe=0c3668cad6) | Apr 19, 2021 |
| Toshiba       | NI 1403                     | [a3789d1a53](https://linux-hardware.org/?probe=a3789d1a53) | Apr 15, 2021 |
| HP            | Pavilion dv5                | [2df1512442](https://linux-hardware.org/?probe=2df1512442) | Apr 12, 2021 |
| HP            | Pavilion dv5                | [963a9c98df](https://linux-hardware.org/?probe=963a9c98df) | Apr 12, 2021 |
| ASUSTek       | X101CH                      | [c1b96ff3fa](https://linux-hardware.org/?probe=c1b96ff3fa) | Apr 04, 2021 |
| LG Electro... | X300-L.CR31B1               | [728ce1cec3](https://linux-hardware.org/?probe=728ce1cec3) | Apr 02, 2021 |
| HP            | Mini 210-1100               | [4b8539128d](https://linux-hardware.org/?probe=4b8539128d) | Apr 01, 2021 |
| HP            | Mini 210-1100               | [a2a1a61099](https://linux-hardware.org/?probe=a2a1a61099) | Apr 01, 2021 |
| LG Electro... | X300-L.CR31B1               | [2dee5439bd](https://linux-hardware.org/?probe=2dee5439bd) | Apr 01, 2021 |
| HP            | Compaq 6530b (GW688AV#AK... | [4644bc75a5](https://linux-hardware.org/?probe=4644bc75a5) | Mar 29, 2021 |
| HP            | Unknown                     | [984ec41c5f](https://linux-hardware.org/?probe=984ec41c5f) | Mar 28, 2021 |
| HP            | Unknown                     | [2f594364bb](https://linux-hardware.org/?probe=2f594364bb) | Mar 20, 2021 |
| Toshiba       | Satellite L750              | [06207199fa](https://linux-hardware.org/?probe=06207199fa) | Mar 16, 2021 |
| ASUSTek       | X542UAR                     | [4a2b4a2f3d](https://linux-hardware.org/?probe=4a2b4a2f3d) | Mar 15, 2021 |
| ASUSTek       | X542UAR                     | [824a5703c6](https://linux-hardware.org/?probe=824a5703c6) | Mar 15, 2021 |
| Sony          | VGN-FZ140E                  | [1d611ce57d](https://linux-hardware.org/?probe=1d611ce57d) | Mar 13, 2021 |
| Sony          | VGN-FZ140E                  | [3bfba9b2a3](https://linux-hardware.org/?probe=3bfba9b2a3) | Mar 13, 2021 |
| ASUSTek       | K46CA                       | [553bb797b4](https://linux-hardware.org/?probe=553bb797b4) | Mar 09, 2021 |
| HP            | EliteBook 8540w             | [8589da1141](https://linux-hardware.org/?probe=8589da1141) | Mar 06, 2021 |
| Lenovo        | ThinkPad T400 64741EG       | [1d54256d1d](https://linux-hardware.org/?probe=1d54256d1d) | Mar 04, 2021 |
| HP            | Compaq Presario CQ71        | [fba2e0f27a](https://linux-hardware.org/?probe=fba2e0f27a) | Mar 01, 2021 |
| HP            | Compaq Presario CQ71        | [65e004cebd](https://linux-hardware.org/?probe=65e004cebd) | Mar 01, 2021 |
| HP            | Compaq nx7400 (EY294ET#A... | [b253d7d3fa](https://linux-hardware.org/?probe=b253d7d3fa) | Mar 01, 2021 |
| Dell          | Inspiron 5559               | [0ca0e1f04f](https://linux-hardware.org/?probe=0ca0e1f04f) | Feb 28, 2021 |
| Dell          | Inspiron 5559               | [0dcf8f701e](https://linux-hardware.org/?probe=0dcf8f701e) | Feb 27, 2021 |
| Samsung       | NC10                        | [968b0bf5ba](https://linux-hardware.org/?probe=968b0bf5ba) | Feb 26, 2021 |
| HP            | Pavilion dv6                | [1baf6f6c70](https://linux-hardware.org/?probe=1baf6f6c70) | Feb 26, 2021 |
| Lenovo        | Y50-70 20378                | [b0a6138136](https://linux-hardware.org/?probe=b0a6138136) | Feb 25, 2021 |
| Acer          | Aspire 7750G                | [68c2e2956e](https://linux-hardware.org/?probe=68c2e2956e) | Feb 21, 2021 |
| Lenovo        | IdeaPad 330S-14AST 81F8     | [078eb9c9b9](https://linux-hardware.org/?probe=078eb9c9b9) | Feb 19, 2021 |
| Acer          | Aspire 6930ZG               | [5e2260251a](https://linux-hardware.org/?probe=5e2260251a) | Feb 19, 2021 |
| Google        | Gnawty                      | [f2d007d3b0](https://linux-hardware.org/?probe=f2d007d3b0) | Feb 16, 2021 |
| Google        | Gnawty                      | [cf74012060](https://linux-hardware.org/?probe=cf74012060) | Feb 16, 2021 |
| Google        | Gnawty                      | [802daa9713](https://linux-hardware.org/?probe=802daa9713) | Feb 16, 2021 |
| Dell          | Latitude E6520              | [132c1f74fc](https://linux-hardware.org/?probe=132c1f74fc) | Feb 14, 2021 |
| Notebook      | WID2010                     | [289d2b0685](https://linux-hardware.org/?probe=289d2b0685) | Feb 10, 2021 |
| LG Electro... | X120-G.C7VPG                | [349c20610a](https://linux-hardware.org/?probe=349c20610a) | Feb 10, 2021 |
| Dell          | Inspiron 7520               | [f4995bc45c](https://linux-hardware.org/?probe=f4995bc45c) | Feb 07, 2021 |
| HP            | EliteBook 820 G3            | [b67948603a](https://linux-hardware.org/?probe=b67948603a) | Feb 04, 2021 |
| Acer          | Aspire 5630                 | [26e90cd431](https://linux-hardware.org/?probe=26e90cd431) | Feb 02, 2021 |
| Acer          | Aspire 5630                 | [61a1c29323](https://linux-hardware.org/?probe=61a1c29323) | Feb 02, 2021 |
| Maibenben     | XiaoMai5                    | [bd1f26e401](https://linux-hardware.org/?probe=bd1f26e401) | Feb 01, 2021 |
| Toshiba       | Satellite C50-A-1DN         | [b5e359a765](https://linux-hardware.org/?probe=b5e359a765) | Jan 28, 2021 |
| Toshiba       | Satellite C50-A-1DN         | [701f078d13](https://linux-hardware.org/?probe=701f078d13) | Jan 28, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [4845dac1e6](https://linux-hardware.org/?probe=4845dac1e6) | Jan 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [f86be88365](https://linux-hardware.org/?probe=f86be88365) | Jan 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [e6066c8531](https://linux-hardware.org/?probe=e6066c8531) | Jan 26, 2021 |
| ASUSTek       | F5N                         | [5a1b1f9f7a](https://linux-hardware.org/?probe=5a1b1f9f7a) | Jan 26, 2021 |
| Sony          | SVE1511N1ESI                | [aa8a372738](https://linux-hardware.org/?probe=aa8a372738) | Jan 23, 2021 |
| Sony          | SVE1511N1ESI                | [69689785e4](https://linux-hardware.org/?probe=69689785e4) | Jan 22, 2021 |
| Matsushita... | CF-19CHB23BE                | [e9fa72450f](https://linux-hardware.org/?probe=e9fa72450f) | Jan 14, 2021 |
| Acer          | Aspire 5930                 | [0826a741c2](https://linux-hardware.org/?probe=0826a741c2) | Jan 13, 2021 |
| Acer          | Aspire 5930                 | [e9f548f926](https://linux-hardware.org/?probe=e9f548f926) | Jan 13, 2021 |
| Dell          | Inspiron 7520               | [f894e05226](https://linux-hardware.org/?probe=f894e05226) | Jan 09, 2021 |
| Acer          | AOD270                      | [89562751d7](https://linux-hardware.org/?probe=89562751d7) | Jan 08, 2021 |
| Exper         | E10IL1                      | [8a1f9ff144](https://linux-hardware.org/?probe=8a1f9ff144) | Dec 31, 2020 |
| Dell          | Precision M4800             | [10bfd0b228](https://linux-hardware.org/?probe=10bfd0b228) | Dec 27, 2020 |
| ASUSTek       | K55N                        | [e3edf30a97](https://linux-hardware.org/?probe=e3edf30a97) | Dec 26, 2020 |
| ASUSTek       | K55N                        | [d7630d7410](https://linux-hardware.org/?probe=d7630d7410) | Dec 26, 2020 |
| Apple         | MacBookPro5,5               | [95d4d575bf](https://linux-hardware.org/?probe=95d4d575bf) | Dec 26, 2020 |
| Lenovo        | ThinkPad X230 2325CN3       | [c0f1039074](https://linux-hardware.org/?probe=c0f1039074) | Dec 24, 2020 |
| Lenovo        | ThinkPad X230 2325CN3       | [5584ad5871](https://linux-hardware.org/?probe=5584ad5871) | Dec 24, 2020 |
| Dell          | Inspiron 1010               | [0b958b270d](https://linux-hardware.org/?probe=0b958b270d) | Dec 22, 2020 |
| Dell          | Inspiron 1010               | [94d64e448f](https://linux-hardware.org/?probe=94d64e448f) | Dec 21, 2020 |
| Acer          | Aspire 5735                 | [d1a973f77f](https://linux-hardware.org/?probe=d1a973f77f) | Dec 21, 2020 |
| Acer          | Aspire 5735                 | [a9ece8f5d0](https://linux-hardware.org/?probe=a9ece8f5d0) | Dec 21, 2020 |
| Lenovo        | ThinkPad T440p 20AWA1NAU... | [7f143b3e74](https://linux-hardware.org/?probe=7f143b3e74) | Dec 20, 2020 |
| Unknown       | Unknown                     | [64b25942e1](https://linux-hardware.org/?probe=64b25942e1) | Dec 20, 2020 |
| Toshiba       | NI 1403                     | [192f91ada6](https://linux-hardware.org/?probe=192f91ada6) | Dec 19, 2020 |
| Exo           | Unknown                     | [a6c445344b](https://linux-hardware.org/?probe=a6c445344b) | Dec 17, 2020 |
| Lenovo        | ThinkPad T440p 20AWA1NAU... | [1b627fe180](https://linux-hardware.org/?probe=1b627fe180) | Dec 15, 2020 |
| Acer          | Aspire one                  | [556332908d](https://linux-hardware.org/?probe=556332908d) | Dec 14, 2020 |
| HP            | Laptop 15-bw0xx             | [dc7e6d3f5d](https://linux-hardware.org/?probe=dc7e6d3f5d) | Dec 14, 2020 |
| HP            | Pavilion ze2000 (EA772AV... | [15284f8c6e](https://linux-hardware.org/?probe=15284f8c6e) | Dec 07, 2020 |
| Dell          | Precision M4600             | [690e349224](https://linux-hardware.org/?probe=690e349224) | Dec 06, 2020 |
| Dell          | Precision M4600             | [f2023ec8ae](https://linux-hardware.org/?probe=f2023ec8ae) | Dec 06, 2020 |
| Acer          | Extensa 4620                | [1bda4268f4](https://linux-hardware.org/?probe=1bda4268f4) | Dec 04, 2020 |
| Matsushita... | CF-19CHB23BE                | [a81d111827](https://linux-hardware.org/?probe=a81d111827) | Nov 25, 2020 |
| ASUSTek       | X550VX                      | [b22a35a959](https://linux-hardware.org/?probe=b22a35a959) | Nov 22, 2020 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | [18d99f9e4f](https://linux-hardware.org/?probe=18d99f9e4f) | Nov 22, 2020 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | [c17dc0982c](https://linux-hardware.org/?probe=c17dc0982c) | Nov 22, 2020 |
| Lenovo        | ThinkPad T60p 8742C4G       | [9d369e30fd](https://linux-hardware.org/?probe=9d369e30fd) | Nov 20, 2020 |
| MSI           | GT70 2PC                    | [dbac4eb570](https://linux-hardware.org/?probe=dbac4eb570) | Nov 20, 2020 |
| MSI           | GT70 2PC                    | [b070b2d112](https://linux-hardware.org/?probe=b070b2d112) | Nov 18, 2020 |
| HP            | Compaq Presario CQ60        | [c9f4c7eefd](https://linux-hardware.org/?probe=c9f4c7eefd) | Nov 16, 2020 |
| HP            | Unknown                     | [b525a6fdd2](https://linux-hardware.org/?probe=b525a6fdd2) | Nov 15, 2020 |
| ASUSTek       | N90SC                       | [219009d9ea](https://linux-hardware.org/?probe=219009d9ea) | Nov 13, 2020 |
| ASUSTek       | N90SC                       | [1b802fbae0](https://linux-hardware.org/?probe=1b802fbae0) | Nov 13, 2020 |
| HP            | Pavilion dv6000 (RV216UA... | [d07adf47aa](https://linux-hardware.org/?probe=d07adf47aa) | Nov 11, 2020 |
| Lenovo        | ThinkPad T420s 4174EK3      | [256f53a883](https://linux-hardware.org/?probe=256f53a883) | Nov 08, 2020 |
| Acer          | Aspire 5735                 | [3863a67ce4](https://linux-hardware.org/?probe=3863a67ce4) | Nov 07, 2020 |
| Acer          | Aspire 5735                 | [80c240fcef](https://linux-hardware.org/?probe=80c240fcef) | Nov 07, 2020 |
| HP            | Laptop 17-ca0xxx            | [ac476c2272](https://linux-hardware.org/?probe=ac476c2272) | Nov 05, 2020 |
| Dell          | Latitude 5400               | [014e9b7e76](https://linux-hardware.org/?probe=014e9b7e76) | Nov 04, 2020 |
| HP            | Laptop 17-ca0xxx            | [ab7e244449](https://linux-hardware.org/?probe=ab7e244449) | Nov 03, 2020 |
| HP            | Compaq 8510p                | [587f5db4a7](https://linux-hardware.org/?probe=587f5db4a7) | Nov 02, 2020 |
| Dell          | Latitude E6220              | [b3af9d8439](https://linux-hardware.org/?probe=b3af9d8439) | Oct 30, 2020 |
| Dell          | Latitude E6220              | [7df244c05f](https://linux-hardware.org/?probe=7df244c05f) | Oct 30, 2020 |
| Dell          | Inspiron 3521               | [c85f72911e](https://linux-hardware.org/?probe=c85f72911e) | Oct 29, 2020 |
| HP            | EliteBook 8470p             | [dd6fd8b99c](https://linux-hardware.org/?probe=dd6fd8b99c) | Oct 24, 2020 |
| ASUSTek       | X551MA                      | [bc2de7b987](https://linux-hardware.org/?probe=bc2de7b987) | Oct 23, 2020 |
| ASUSTek       | X551MA                      | [ad50a3e36d](https://linux-hardware.org/?probe=ad50a3e36d) | Oct 22, 2020 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [c00341fecd](https://linux-hardware.org/?probe=c00341fecd) | Oct 21, 2020 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [83c0ae72b0](https://linux-hardware.org/?probe=83c0ae72b0) | Oct 21, 2020 |
| Unknown       | Unknown                     | [f786cfb7ca](https://linux-hardware.org/?probe=f786cfb7ca) | Oct 18, 2020 |
| ASUSTek       | GL503VM                     | [a6705573f8](https://linux-hardware.org/?probe=a6705573f8) | Oct 11, 2020 |
| HP            | EliteBook 8470p             | [27fe34d7e1](https://linux-hardware.org/?probe=27fe34d7e1) | Oct 09, 2020 |
| Acer          | Aspire 5680                 | [3ef4868294](https://linux-hardware.org/?probe=3ef4868294) | Oct 07, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [0053b1ef76](https://linux-hardware.org/?probe=0053b1ef76) | Oct 07, 2020 |
| Lenovo        | B71-80 80RJ                 | [a5135ffb54](https://linux-hardware.org/?probe=a5135ffb54) | Oct 04, 2020 |
| Dell          | Latitude E6400              | [5d51e1eab7](https://linux-hardware.org/?probe=5d51e1eab7) | Oct 04, 2020 |
| Unknown       | Unknown                     | [fd16de3c7f](https://linux-hardware.org/?probe=fd16de3c7f) | Oct 03, 2020 |
| Lenovo        | B71-80 80RJ                 | [7f6ed6799f](https://linux-hardware.org/?probe=7f6ed6799f) | Oct 03, 2020 |
| Positivo      | H14CU01                     | [3a0013a489](https://linux-hardware.org/?probe=3a0013a489) | Sep 28, 2020 |
| Positivo      | H14CU01                     | [e0d8261056](https://linux-hardware.org/?probe=e0d8261056) | Sep 28, 2020 |
| Dell          | Inspiron 5566               | [a93a422684](https://linux-hardware.org/?probe=a93a422684) | Sep 23, 2020 |
| HP            | TouchSmart tm2              | [1a91d6cc06](https://linux-hardware.org/?probe=1a91d6cc06) | Sep 22, 2020 |
| ASUSTek       | GL503VM                     | [349cf8d805](https://linux-hardware.org/?probe=349cf8d805) | Sep 17, 2020 |
| Toshiba       | NI 1403                     | [d2f6023c70](https://linux-hardware.org/?probe=d2f6023c70) | Sep 17, 2020 |
| Lenovo        | V145-15AST 81MT             | [401a915579](https://linux-hardware.org/?probe=401a915579) | Sep 10, 2020 |
| Fujitsu       | LIFEBOOK A556/G             | [9484700de9](https://linux-hardware.org/?probe=9484700de9) | Sep 10, 2020 |
| MSI           | FX610                       | [61fe175928](https://linux-hardware.org/?probe=61fe175928) | Sep 04, 2020 |
| Acer          | Aspire A315-41              | [2f541fa7c6](https://linux-hardware.org/?probe=2f541fa7c6) | Aug 23, 2020 |
| HP            | EliteBook 2540p             | [682d1b7a8c](https://linux-hardware.org/?probe=682d1b7a8c) | Aug 22, 2020 |
| Acer          | Extensa 4620                | [9421ec33ce](https://linux-hardware.org/?probe=9421ec33ce) | Aug 18, 2020 |
| HP            | Laptop 15-bs0xx             | [f6678c3632](https://linux-hardware.org/?probe=f6678c3632) | Aug 17, 2020 |
| Acer          | Extensa 4620                | [a7701181d6](https://linux-hardware.org/?probe=a7701181d6) | Aug 17, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [eed0bce682](https://linux-hardware.org/?probe=eed0bce682) | Aug 14, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [532d54162a](https://linux-hardware.org/?probe=532d54162a) | Aug 14, 2020 |
| Dell          | Latitude E5430 non-vPro     | [2a8cc9f92c](https://linux-hardware.org/?probe=2a8cc9f92c) | Aug 04, 2020 |
| HP            | Laptop 15-bs0xx             | [467112cf04](https://linux-hardware.org/?probe=467112cf04) | Jul 31, 2020 |
| Positivo      | W310CZ-T                    | [0a1a913ef9](https://linux-hardware.org/?probe=0a1a913ef9) | Jul 19, 2020 |
| Acer          | Aspire 1640                 | [187a648c68](https://linux-hardware.org/?probe=187a648c68) | Jul 16, 2020 |
| Lenovo        | ThinkPad T61 6457W9X        | [ccd11debcb](https://linux-hardware.org/?probe=ccd11debcb) | Jul 11, 2020 |
| HP            | ProBook 430 G5              | [ea27ca7285](https://linux-hardware.org/?probe=ea27ca7285) | Jul 01, 2020 |
| ASUSTek       | E402SA                      | [46b87025ae](https://linux-hardware.org/?probe=46b87025ae) | Jul 01, 2020 |
| Acer          | Aspire 5750G                | [1f45c104e4](https://linux-hardware.org/?probe=1f45c104e4) | Jun 26, 2020 |
| Acer          | Aspire 5750G                | [5613253a47](https://linux-hardware.org/?probe=5613253a47) | Jun 26, 2020 |
| Dell          | Inspiron 3442               | [8c0a32e7f4](https://linux-hardware.org/?probe=8c0a32e7f4) | Jun 19, 2020 |
| Dell          | Inspiron 3442               | [8ed5aa8505](https://linux-hardware.org/?probe=8ed5aa8505) | Jun 19, 2020 |
| Lenovo        | ThinkPad X230 2325CN3       | [012f3cadc0](https://linux-hardware.org/?probe=012f3cadc0) | Jun 16, 2020 |
| ASUSTek       | K50C                        | [1d98006287](https://linux-hardware.org/?probe=1d98006287) | Jun 15, 2020 |
| ASUSTek       | K50C                        | [141d18f0ca](https://linux-hardware.org/?probe=141d18f0ca) | Jun 15, 2020 |
| HP            | 350 G2                      | [ac2b06957f](https://linux-hardware.org/?probe=ac2b06957f) | Jun 11, 2020 |
| ASUSTek       | 1005PX                      | [8d5b0aa8df](https://linux-hardware.org/?probe=8d5b0aa8df) | Jun 03, 2020 |
| Sony          | VGN-AW41MF_H                | [baf800f176](https://linux-hardware.org/?probe=baf800f176) | May 29, 2020 |
| Samsung       | RV411/RV511/E3511/S3511/... | [f4679ca184](https://linux-hardware.org/?probe=f4679ca184) | May 29, 2020 |
| HP            | EliteBook 8540w             | [4fb041418f](https://linux-hardware.org/?probe=4fb041418f) | May 29, 2020 |
| HP            | EliteBook 8540w             | [b36f5a9ddf](https://linux-hardware.org/?probe=b36f5a9ddf) | May 28, 2020 |
| ASUSTek       | K50IJ                       | [7f22ac48a8](https://linux-hardware.org/?probe=7f22ac48a8) | May 26, 2020 |
| ASUSTek       | K50IJ                       | [be86e3ea15](https://linux-hardware.org/?probe=be86e3ea15) | May 26, 2020 |
| HP            | Presario CQ61               | [28b3078708](https://linux-hardware.org/?probe=28b3078708) | May 25, 2020 |
| Acer          | Aspire 7551                 | [d9c150f3ee](https://linux-hardware.org/?probe=d9c150f3ee) | May 24, 2020 |
| Dell          | Inspiron N5110              | [e2ba0ca3f4](https://linux-hardware.org/?probe=e2ba0ca3f4) | May 22, 2020 |
| Acer          | Aspire 4830T                | [5494761310](https://linux-hardware.org/?probe=5494761310) | May 20, 2020 |
| ASUSTek       | X550LC                      | [9c46a8ee24](https://linux-hardware.org/?probe=9c46a8ee24) | May 20, 2020 |
| ASUSTek       | X550LC                      | [b7665aa8e1](https://linux-hardware.org/?probe=b7665aa8e1) | May 20, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [4d4f673fb2](https://linux-hardware.org/?probe=4d4f673fb2) | May 16, 2020 |
| HP            | EliteBook 8570p             | [4ede694438](https://linux-hardware.org/?probe=4ede694438) | May 14, 2020 |
| HP            | EliteBook 8570p             | [530b229976](https://linux-hardware.org/?probe=530b229976) | May 14, 2020 |
| Dell          | G3 3590                     | [6b37af517b](https://linux-hardware.org/?probe=6b37af517b) | May 12, 2020 |
| Toshiba       | Satellite U300              | [ef95fa82d7](https://linux-hardware.org/?probe=ef95fa82d7) | May 11, 2020 |
| HP            | G61                         | [7393752623](https://linux-hardware.org/?probe=7393752623) | May 11, 2020 |
| Dell          | Latitude E5570              | [1c8dda10a4](https://linux-hardware.org/?probe=1c8dda10a4) | May 08, 2020 |
| Dell          | Latitude E5570              | [20fc42be1b](https://linux-hardware.org/?probe=20fc42be1b) | May 06, 2020 |
| Dell          | System Inspiron N411Z       | [246dd5ce2a](https://linux-hardware.org/?probe=246dd5ce2a) | May 05, 2020 |
| Dell          | Latitude E5570              | [a1b049e54c](https://linux-hardware.org/?probe=a1b049e54c) | May 05, 2020 |
| Toshiba       | Satellite U300              | [3bd62e1a59](https://linux-hardware.org/?probe=3bd62e1a59) | May 05, 2020 |
| HP            | Laptop 15-bs2xx             | [6d47f83eac](https://linux-hardware.org/?probe=6d47f83eac) | May 02, 2020 |
| Lenovo        | E41-25 81FS                 | [154605446a](https://linux-hardware.org/?probe=154605446a) | May 02, 2020 |
| Lenovo        | E41-25 81FS                 | [e9544d771b](https://linux-hardware.org/?probe=e9544d771b) | May 02, 2020 |
| HP            | G42                         | [be1ea8571f](https://linux-hardware.org/?probe=be1ea8571f) | Apr 28, 2020 |
| Lenovo        | ThinkPad E490 20N80017RT    | [7f84d5a0f2](https://linux-hardware.org/?probe=7f84d5a0f2) | Apr 28, 2020 |
| HP            | G42                         | [8ea8320eac](https://linux-hardware.org/?probe=8ea8320eac) | Apr 27, 2020 |
| HP            | ProBook 430 G5              | [b314d76130](https://linux-hardware.org/?probe=b314d76130) | Apr 27, 2020 |
| HP            | ProBook 430 G5              | [7984248cab](https://linux-hardware.org/?probe=7984248cab) | Apr 26, 2020 |
| Acer          | Aspire E1-572               | [e64e2fe71c](https://linux-hardware.org/?probe=e64e2fe71c) | Apr 23, 2020 |
| HP            | Laptop 15-bs2xx             | [477c5d9ffa](https://linux-hardware.org/?probe=477c5d9ffa) | Apr 17, 2020 |
| Positivo      | Mobile                      | [c7cc7cd357](https://linux-hardware.org/?probe=c7cc7cd357) | Apr 17, 2020 |
| Positivo      | Mobile                      | [55b84972df](https://linux-hardware.org/?probe=55b84972df) | Apr 17, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [4d06bdc501](https://linux-hardware.org/?probe=4d06bdc501) | Apr 14, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [67167458d8](https://linux-hardware.org/?probe=67167458d8) | Apr 14, 2020 |
| Acer          | Aspire E1-572               | [941e12751c](https://linux-hardware.org/?probe=941e12751c) | Apr 14, 2020 |
| Acer          | Aspire E1-570G              | [e727c9003c](https://linux-hardware.org/?probe=e727c9003c) | Apr 10, 2020 |
| Acer          | Aspire E1-570G              | [fe1196d306](https://linux-hardware.org/?probe=fe1196d306) | Apr 09, 2020 |
| Dell          | Latitude E6510              | [5f62bf8564](https://linux-hardware.org/?probe=5f62bf8564) | Apr 07, 2020 |
| Toshiba       | Satellite P300              | [93b28f5a7c](https://linux-hardware.org/?probe=93b28f5a7c) | Apr 03, 2020 |
| ASUSTek       | ZenBook UX431FA             | [3251d5e710](https://linux-hardware.org/?probe=3251d5e710) | Apr 03, 2020 |
| Dell          | Latitude D610               | [44901c9eb2](https://linux-hardware.org/?probe=44901c9eb2) | Mar 30, 2020 |
| Dell          | Latitude D610               | [5bfecb6e64](https://linux-hardware.org/?probe=5bfecb6e64) | Mar 30, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [5c90c49af6](https://linux-hardware.org/?probe=5c90c49af6) | Mar 29, 2020 |
| Dell          | Inspiron 3543               | [5055c4067a](https://linux-hardware.org/?probe=5055c4067a) | Mar 20, 2020 |
| HP            | EliteBook 820 G3            | [b2c3317256](https://linux-hardware.org/?probe=b2c3317256) | Mar 19, 2020 |
| HP            | EliteBook 820 G3            | [2cd8614e59](https://linux-hardware.org/?probe=2cd8614e59) | Mar 17, 2020 |
| HP            | EliteBook 820 G3            | [fcb4ff46b5](https://linux-hardware.org/?probe=fcb4ff46b5) | Mar 17, 2020 |
| Lenovo        | Y50-70 20378                | [7dbce6b0fc](https://linux-hardware.org/?probe=7dbce6b0fc) | Jan 15, 2020 |
| Lenovo        | Y50-70 20378                | [11b0d93285](https://linux-hardware.org/?probe=11b0d93285) | Jan 15, 2020 |
| Dell          | Inspiron 3593               | [9f8af004d3](https://linux-hardware.org/?probe=9f8af004d3) | Nov 29, 2019 |
| Dell          | Inspiron 3593               | [7f4ce08df9](https://linux-hardware.org/?probe=7f4ce08df9) | Nov 29, 2019 |
| Dell          | Inspiron 3593               | [a6ee735c5f](https://linux-hardware.org/?probe=a6ee735c5f) | Nov 29, 2019 |
| Acer          | Aspire V3-571G              | [9be63e6a28](https://linux-hardware.org/?probe=9be63e6a28) | Jan 09, 2019 |
| HP            | Pavilion dv7                | [4480bf8ff3](https://linux-hardware.org/?probe=4480bf8ff3) | Dec 24, 2018 |
| Acer          | Aspire V3-571               | [bb8f83433e](https://linux-hardware.org/?probe=bb8f83433e) | Nov 27, 2018 |
| Acer          | Aspire V3-571               | [1136588271](https://linux-hardware.org/?probe=1136588271) | Nov 27, 2018 |
| HP            | ProBook 4510s               | [dbc607e890](https://linux-hardware.org/?probe=dbc607e890) | Sep 08, 2018 |
| Dell          | Inspiron 11-3162            | [92dcc778ac](https://linux-hardware.org/?probe=92dcc778ac) | Mar 19, 2018 |
| Sony          | VPCEB1M1R                   | [25b5c0689e](https://linux-hardware.org/?probe=25b5c0689e) | Mar 16, 2018 |
| Sony          | VPCSB3M1R                   | [155309a9eb](https://linux-hardware.org/?probe=155309a9eb) | Aug 23, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| LMDE 4 | 219       | 73.99%  |
| LMDE 5 | 68        | 22.97%  |
| LMDE 3 | 6         | 2.03%   |
| LMDE 2 | 3         | 1.01%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| LMDE | 296       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 4.19.0-8-amd64       | 27        | 8.39%   |
| 4.19.0-18-amd64      | 24        | 7.45%   |
| 4.19.0-17-amd64      | 20        | 6.21%   |
| 5.10.0-14-amd64      | 19        | 5.9%    |
| 4.19.0-9-amd64       | 18        | 5.59%   |
| 4.19.0-16-amd64      | 16        | 4.97%   |
| 5.10.0-12-amd64      | 15        | 4.66%   |
| 5.10.0-13-amd64      | 14        | 4.35%   |
| 4.19.0-8-686         | 14        | 4.35%   |
| 4.19.0-17-686        | 14        | 4.35%   |
| 4.19.0-14-amd64      | 13        | 4.04%   |
| 4.19.0-13-amd64      | 12        | 3.73%   |
| 4.19.0-16-686        | 11        | 3.42%   |
| 4.19.0-10-amd64      | 11        | 3.42%   |
| 5.10.0-15-amd64      | 10        | 3.11%   |
| 4.19.0-18-686        | 10        | 3.11%   |
| 4.19.0-12-amd64      | 10        | 3.11%   |
| 4.19.0-13-686        | 7         | 2.17%   |
| 4.19.0-11-amd64      | 6         | 1.86%   |
| 5.10.0-13-686        | 5         | 1.55%   |
| 4.19.0-12-686        | 5         | 1.55%   |
| 4.9.0-8-amd64        | 4         | 1.24%   |
| 4.19.0-19-686        | 3         | 0.93%   |
| 4.19.0-14-686        | 3         | 0.93%   |
| 5.4.0-0.bpo.4-amd64  | 2         | 0.62%   |
| 5.18.0-0.bpo.1-amd64 | 2         | 0.62%   |
| 5.16.0-0.bpo.4-amd64 | 2         | 0.62%   |
| 5.10.0-0.bpo.5-amd64 | 2         | 0.62%   |
| 3.16.0-4-amd64       | 2         | 0.62%   |
| 5.9.12-davius        | 1         | 0.31%   |
| 5.9.0-0.bpo.5-amd64  | 1         | 0.31%   |
| 5.8.0-0.bpo.2-amd64  | 1         | 0.31%   |
| 5.6.0-2-amd64        | 1         | 0.31%   |
| 5.6.0-2-686-pae      | 1         | 0.31%   |
| 5.4.44-xanmod1       | 1         | 0.31%   |
| 5.16.0-0.bpo.3-amd64 | 1         | 0.31%   |
| 5.15.0-0.bpo.3-amd64 | 1         | 0.31%   |
| 5.10.0-14-686        | 1         | 0.31%   |
| 5.10.0-0.bpo.9-amd64 | 1         | 0.31%   |
| 5.10.0-0.bpo.3-amd64 | 1         | 0.31%   |
| 4.9.0-14-amd64       | 1         | 0.31%   |
| 4.9.0-11-amd64       | 1         | 0.31%   |
| 4.19.0-9-686         | 1         | 0.31%   |
| 4.19.0-20-amd64      | 1         | 0.31%   |
| 4.19.0-20-686        | 1         | 0.31%   |
| 4.19.0-14-686-pae    | 1         | 0.31%   |
| 4.19.0-12-rt-amd64   | 1         | 0.31%   |
| 4.19.0-10-686        | 1         | 0.31%   |
| 4.19.0-0.bpo.8-amd64 | 1         | 0.31%   |
| 3.16.0-5-amd64       | 1         | 0.31%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.19.0  | 210       | 70.47%  |
| 5.10.0  | 66        | 22.15%  |
| 4.9.0   | 5         | 1.68%   |
| 5.16.0  | 3         | 1.01%   |
| 3.16.0  | 3         | 1.01%   |
| 5.6.0   | 2         | 0.67%   |
| 5.4.0   | 2         | 0.67%   |
| 5.18.0  | 2         | 0.67%   |
| 5.9.12  | 1         | 0.34%   |
| 5.9.0   | 1         | 0.34%   |
| 5.8.0   | 1         | 0.34%   |
| 5.4.44  | 1         | 0.34%   |
| 5.15.0  | 1         | 0.34%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.19    | 210       | 70.47%  |
| 5.10    | 66        | 22.15%  |
| 4.9     | 5         | 1.68%   |
| 5.4     | 3         | 1.01%   |
| 5.16    | 3         | 1.01%   |
| 3.16    | 3         | 1.01%   |
| 5.9     | 2         | 0.67%   |
| 5.6     | 2         | 0.67%   |
| 5.18    | 2         | 0.67%   |
| 5.8     | 1         | 0.34%   |
| 5.15    | 1         | 0.34%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 222       | 75%     |
| i686   | 74        | 25%     |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| X-Cinnamon | 266       | 88.37%  |
| Cinnamon   | 19        | 6.31%   |
| MATE       | 6         | 1.99%   |
| Unknown    | 6         | 1.99%   |
| XFCE       | 1         | 0.33%   |
| Trinity    | 1         | 0.33%   |
| LXDE       | 1         | 0.33%   |
| KDE        | 1         | 0.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 296       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 239       | 80.2%   |
| LightDM | 41        | 13.76%  |
| TDM     | 15        | 5.03%   |
| MDM     | 3         | 1.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 93        | 31.21%  |
| pt_BR   | 29        | 9.73%   |
| de_DE   | 27        | 9.06%   |
| ru_RU   | 19        | 6.38%   |
| en_GB   | 14        | 4.7%    |
| pl_PL   | 11        | 3.69%   |
| it_IT   | 8         | 2.68%   |
| fr_FR   | 8         | 2.68%   |
| Unknown | 8         | 2.68%   |
| es_MX   | 7         | 2.35%   |
| es_ES   | 7         | 2.35%   |
| es_AR   | 6         | 2.01%   |
| en_AU   | 6         | 2.01%   |
| en_CA   | 5         | 1.68%   |
| de_CH   | 5         | 1.68%   |
| nl_NL   | 3         | 1.01%   |
| ja_JP   | 3         | 1.01%   |
| el_GR   | 3         | 1.01%   |
| pt_PT   | 2         | 0.67%   |
| es_BO   | 2         | 0.67%   |
| en_ZA   | 2         | 0.67%   |
| en_PH   | 2         | 0.67%   |
| en_IN   | 2         | 0.67%   |
| de_AT   | 2         | 0.67%   |
| bg_BG   | 2         | 0.67%   |
| zh_CN   | 1         | 0.34%   |
| unm_US  | 1         | 0.34%   |
| uk_UA   | 1         | 0.34%   |
| tr_TR   | 1         | 0.34%   |
| sk_SK   | 1         | 0.34%   |
| ru_UA   | 1         | 0.34%   |
| nl_BE   | 1         | 0.34%   |
| nl_AW   | 1         | 0.34%   |
| ko_KR   | 1         | 0.34%   |
| it_CH   | 1         | 0.34%   |
| hu_HU   | 1         | 0.34%   |
| hr_HR   | 1         | 0.34%   |
| fr_BE   | 1         | 0.34%   |
| et_EE   | 1         | 0.34%   |
| es_PE   | 1         | 0.34%   |
| es_EC   | 1         | 0.34%   |
| es_CL   | 1         | 0.34%   |
| en_SG   | 1         | 0.34%   |
| en_NZ   | 1         | 0.34%   |
| en_IE   | 1         | 0.34%   |
| da_DK   | 1         | 0.34%   |
| ca_ES   | 1         | 0.34%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 191       | 64.09%  |
| EFI  | 107       | 35.91%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 279       | 94.26%  |
| Overlay | 5         | 1.69%   |
| Btrfs   | 5         | 1.69%   |
| Unknown | 3         | 1.01%   |
| Tmpfs   | 2         | 0.68%   |
| Xfs     | 1         | 0.34%   |
| Aufs    | 1         | 0.34%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 235       | 79.39%  |
| GPT     | 38        | 12.84%  |
| MBR     | 23        | 7.77%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 281       | 94.93%  |
| Yes       | 15        | 5.07%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 278       | 93.92%  |
| Yes       | 18        | 6.08%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Hewlett-Packard                | 69        | 23.31%  |
| Dell                           | 43        | 14.53%  |
| Acer                           | 38        | 12.84%  |
| Lenovo                         | 36        | 12.16%  |
| ASUSTek Computer               | 30        | 10.14%  |
| Toshiba                        | 11        | 3.72%   |
| Sony                           | 8         | 2.7%    |
| Samsung Electronics            | 7         | 2.36%   |
| Fujitsu Siemens                | 5         | 1.69%   |
| Apple                          | 5         | 1.69%   |
| LG Electronics                 | 4         | 1.35%   |
| Positivo                       | 3         | 1.01%   |
| Packard Bell                   | 3         | 1.01%   |
| MSI                            | 3         | 1.01%   |
| Unknown                        | 3         | 1.01%   |
| Medion                         | 2         | 0.68%   |
| Matsushita Electric Industrial | 2         | 0.68%   |
| Gateway                        | 2         | 0.68%   |
| Fujitsu                        | 2         | 0.68%   |
| TUXEDO                         | 1         | 0.34%   |
| Semp Toshiba                   | 1         | 0.34%   |
| SAELITE                        | 1         | 0.34%   |
| Qbex                           | 1         | 0.34%   |
| Philco                         | 1         | 0.34%   |
| Notebook                       | 1         | 0.34%   |
| Multilaser                     | 1         | 0.34%   |
| Maibenben                      | 1         | 0.34%   |
| LincPlus                       | 1         | 0.34%   |
| Itautec                        | 1         | 0.34%   |
| IBM                            | 1         | 0.34%   |
| Howard Computers               | 1         | 0.34%   |
| Google                         | 1         | 0.34%   |
| Framework                      | 1         | 0.34%   |
| Exper                          | 1         | 0.34%   |
| Exo                            | 1         | 0.34%   |
| EVOO                           | 1         | 0.34%   |
| Dixonsxp                       | 1         | 0.34%   |
| Alienware                      | 1         | 0.34%   |
| Advent                         | 1         | 0.34%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 8         | 2.7%    |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 3         | 1.01%   |
| Dell Latitude E6400                         | 3         | 1.01%   |
| Acer AOD270                                 | 3         | 1.01%   |
| Lenovo IdeaPad 3 15ADA05 81W1               | 2         | 0.68%   |
| HP Pavilion dv7                             | 2         | 0.68%   |
| HP Pavilion dv6                             | 2         | 0.68%   |
| HP Notebook                                 | 2         | 0.68%   |
| HP Laptop 15z-ef2xxx                        | 2         | 0.68%   |
| HP Laptop 15-bw0xx                          | 2         | 0.68%   |
| HP Laptop 14-df0xxx                         | 2         | 0.68%   |
| HP EliteBook 8540w                          | 2         | 0.68%   |
| HP 255 G7 Notebook PC                       | 2         | 0.68%   |
| HP 14                                       | 2         | 0.68%   |
| Dell Inspiron 5566                          | 2         | 0.68%   |
| Dell Inspiron 5559                          | 2         | 0.68%   |
| ASUS X101CH                                 | 2         | 0.68%   |
| Acer Aspire 5930                            | 2         | 0.68%   |
| Acer Aspire 5735                            | 2         | 0.68%   |
| Acer Aspire 3000                            | 2         | 0.68%   |
| TUXEDO BC1510 1710                          | 1         | 0.34%   |
| Toshiba Satellite U300                      | 1         | 0.34%   |
| Toshiba Satellite P300                      | 1         | 0.34%   |
| Toshiba Satellite M55                       | 1         | 0.34%   |
| Toshiba Satellite M100                      | 1         | 0.34%   |
| Toshiba Satellite L855                      | 1         | 0.34%   |
| Toshiba Satellite L750                      | 1         | 0.34%   |
| Toshiba Satellite L50-C                     | 1         | 0.34%   |
| Toshiba Satellite L455                      | 1         | 0.34%   |
| Toshiba Satellite C50-A-1DN                 | 1         | 0.34%   |
| Toshiba Satellite A200                      | 1         | 0.34%   |
| Toshiba dynabook Satellite J61 173C/5       | 1         | 0.34%   |
| Sony VPCSB3M1R                              | 1         | 0.34%   |
| Sony VPCS131FM                              | 1         | 0.34%   |
| Sony VPCP116KG                              | 1         | 0.34%   |
| Sony VPCEB1M1R                              | 1         | 0.34%   |
| Sony VGN-FZ140E                             | 1         | 0.34%   |
| Sony VGN-AW41MF_H                           | 1         | 0.34%   |
| Sony SVE1713Y1RB                            | 1         | 0.34%   |
| Sony SVE1511N1ESI                           | 1         | 0.34%   |
| Semp Toshiba NI 1403                        | 1         | 0.34%   |
| Samsung RV413/RV513                         | 1         | 0.34%   |
| Samsung R59/R60/R61                         | 1         | 0.34%   |
| Samsung NC10                                | 1         | 0.34%   |
| Samsung 305U1A                              | 1         | 0.34%   |
| SAELITE ES1AU11                             | 1         | 0.34%   |
| Qbex UDPAIOQBEX01                           | 1         | 0.34%   |
| Positivo W310CZ-T                           | 1         | 0.34%   |
| Positivo Mobile                             | 1         | 0.34%   |
| Positivo H14CU01                            | 1         | 0.34%   |
| Philco 10D                                  | 1         | 0.34%   |
| Packard Bell EasyNote_NJ66                  | 1         | 0.34%   |
| Packard Bell EasyNote TE69BM                | 1         | 0.34%   |
| Packard Bell DOT S                          | 1         | 0.34%   |
| Notebook WID2010                            | 1         | 0.34%   |
| Multilaser PC150                            | 1         | 0.34%   |
| MSI U180                                    | 1         | 0.34%   |
| MSI GT70 2PC                                | 1         | 0.34%   |
| MSI FX610                                   | 1         | 0.34%   |
| Medion P6670 MD99960                        | 1         | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Acer Aspire                                 | 30        | 10.14%  |
| Lenovo ThinkPad                             | 16        | 5.41%   |
| Dell Latitude                               | 16        | 5.41%   |
| Dell Inspiron                               | 16        | 5.41%   |
| HP Pavilion                                 | 13        | 4.39%   |
| HP Laptop                                   | 12        | 4.05%   |
| Lenovo IdeaPad                              | 11        | 3.72%   |
| Toshiba Satellite                           | 10        | 3.38%   |
| HP EliteBook                                | 8         | 2.7%    |
| Unknown                                     | 8         | 2.7%    |
| HP Compaq                                   | 7         | 2.36%   |
| HP ProBook                                  | 5         | 1.69%   |
| Dell Precision                              | 5         | 1.69%   |
| Samsung RV411                               | 3         | 1.01%   |
| HP Presario                                 | 3         | 1.01%   |
| HP 255                                      | 3         | 1.01%   |
| Fujitsu Siemens ESPRIMO                     | 3         | 1.01%   |
| ASUS VivoBook                               | 3         | 1.01%   |
| Acer AOD270                                 | 3         | 1.01%   |
| Packard Bell EasyNote                       | 2         | 0.68%   |
| HP Notebook                                 | 2         | 0.68%   |
| HP ENVY                                     | 2         | 0.68%   |
| HP 14                                       | 2         | 0.68%   |
| Dell XPS                                    | 2         | 0.68%   |
| Dell System                                 | 2         | 0.68%   |
| ASUS X101CH                                 | 2         | 0.68%   |
| Apple MacBookPro5                           | 2         | 0.68%   |
| Acer Swift                                  | 2         | 0.68%   |
| TUXEDO BC1510                               | 1         | 0.34%   |
| Toshiba dynabook                            | 1         | 0.34%   |
| Sony VPCSB3M1R                              | 1         | 0.34%   |
| Sony VPCS131FM                              | 1         | 0.34%   |
| Sony VPCP116KG                              | 1         | 0.34%   |
| Sony VPCEB1M1R                              | 1         | 0.34%   |
| Sony VGN-FZ140E                             | 1         | 0.34%   |
| Sony VGN-AW41MF                             | 1         | 0.34%   |
| Sony SVE1713Y1RB                            | 1         | 0.34%   |
| Sony SVE1511N1ESI                           | 1         | 0.34%   |
| Semp Toshiba NI                             | 1         | 0.34%   |
| Samsung RV413                               | 1         | 0.34%   |
| Samsung R59                                 | 1         | 0.34%   |
| Samsung NC10                                | 1         | 0.34%   |
| Samsung 305U1A                              | 1         | 0.34%   |
| SAELITE ES1AU11                             | 1         | 0.34%   |
| Qbex UDPAIOQBEX01                           | 1         | 0.34%   |
| Positivo W310CZ-T                           | 1         | 0.34%   |
| Positivo Mobile                             | 1         | 0.34%   |
| Positivo H14CU01                            | 1         | 0.34%   |
| Philco 10D                                  | 1         | 0.34%   |
| Packard Bell DOT                            | 1         | 0.34%   |
| Notebook WID2010                            | 1         | 0.34%   |
| Multilaser PC150                            | 1         | 0.34%   |
| MSI U180                                    | 1         | 0.34%   |
| MSI GT70                                    | 1         | 0.34%   |
| MSI FX610                                   | 1         | 0.34%   |
| Medion P6670                                | 1         | 0.34%   |
| Medion E6220                                | 1         | 0.34%   |
| Matsushita Electric Industrial CF-19DDGZXVM | 1         | 0.34%   |
| Matsushita Electric Industrial CF-19CHB23BE | 1         | 0.34%   |
| Maibenben XiaoMai5                          | 1         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2012    | 27        | 9.12%   |
| 2011    | 26        | 8.78%   |
| 2009    | 26        | 8.78%   |
| 2010    | 24        | 8.11%   |
| 2013    | 22        | 7.43%   |
| 2008    | 21        | 7.09%   |
| 2007    | 21        | 7.09%   |
| 2018    | 19        | 6.42%   |
| 2014    | 15        | 5.07%   |
| 2021    | 13        | 4.39%   |
| 2019    | 13        | 4.39%   |
| 2016    | 13        | 4.39%   |
| 2020    | 12        | 4.05%   |
| 2015    | 12        | 4.05%   |
| 2006    | 11        | 3.72%   |
| 2017    | 10        | 3.38%   |
| 2005    | 7         | 2.36%   |
| 2004    | 1         | 0.34%   |
| 2003    | 1         | 0.34%   |
| 2002    | 1         | 0.34%   |
| Unknown | 1         | 0.34%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 296       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 278       | 93.6%   |
| Enabled  | 19        | 6.4%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 295       | 99.66%  |
| Yes  | 1         | 0.34%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 89        | 29.97%  |
| 4.01-8.0    | 60        | 20.2%   |
| 2.01-3.0    | 42        | 14.14%  |
| 1.01-2.0    | 36        | 12.12%  |
| 16.01-24.0  | 30        | 10.1%   |
| 8.01-16.0   | 24        | 8.08%   |
| 0.51-1.0    | 9         | 3.03%   |
| 32.01-64.0  | 4         | 1.35%   |
| 64.01-256.0 | 2         | 0.67%   |
| 24.01-32.0  | 1         | 0.34%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 155       | 49.21%  |
| 0.51-1.0  | 62        | 19.68%  |
| 2.01-3.0  | 58        | 18.41%  |
| 3.01-4.0  | 25        | 7.94%   |
| 4.01-8.0  | 9         | 2.86%   |
| 8.01-16.0 | 3         | 0.95%   |
| 0.01-0.5  | 3         | 0.95%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 219       | 73%     |
| 2      | 65        | 21.67%  |
| 3      | 7         | 2.33%   |
| 0      | 4         | 1.33%   |
| 4      | 3         | 1%      |
| 6      | 1         | 0.33%   |
| 5      | 1         | 0.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 160       | 53.87%  |
| No        | 137       | 46.13%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 268       | 90.54%  |
| No        | 28        | 9.46%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 291       | 98.31%  |
| No        | 5         | 1.69%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 170       | 57.43%  |
| No        | 126       | 42.57%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country             | Notebooks | Percent |
|---------------------|-----------|---------|
| USA                 | 39        | 13.18%  |
| Germany             | 30        | 10.14%  |
| Brazil              | 30        | 10.14%  |
| Russia              | 21        | 7.09%   |
| UK                  | 16        | 5.41%   |
| Poland              | 13        | 4.39%   |
| France              | 10        | 3.38%   |
| Italy               | 9         | 3.04%   |
| Spain               | 8         | 2.7%    |
| Mexico              | 8         | 2.7%    |
| Canada              | 7         | 2.36%   |
| Australia           | 7         | 2.36%   |
| Ukraine             | 6         | 2.03%   |
| Switzerland         | 6         | 2.03%   |
| Netherlands         | 6         | 2.03%   |
| Bulgaria            | 6         | 2.03%   |
| Argentina           | 6         | 2.03%   |
| Austria             | 4         | 1.35%   |
| Turkey              | 3         | 1.01%   |
| Romania             | 3         | 1.01%   |
| Portugal            | 3         | 1.01%   |
| Philippines         | 3         | 1.01%   |
| Indonesia           | 3         | 1.01%   |
| India               | 3         | 1.01%   |
| Greece              | 3         | 1.01%   |
| Chile               | 3         | 1.01%   |
| Belarus             | 3         | 1.01%   |
| Bahrain             | 3         | 1.01%   |
| Tunisia             | 2         | 0.68%   |
| South Africa        | 2         | 0.68%   |
| Japan               | 2         | 0.68%   |
| China               | 2         | 0.68%   |
| Bolivia             | 2         | 0.68%   |
| Belgium             | 2         | 0.68%   |
| Venezuela           | 1         | 0.34%   |
| Trinidad and Tobago | 1         | 0.34%   |
| Sweden              | 1         | 0.34%   |
| South Korea         | 1         | 0.34%   |
| Singapore           | 1         | 0.34%   |
| Peru                | 1         | 0.34%   |
| New Zealand         | 1         | 0.34%   |
| Myanmar             | 1         | 0.34%   |
| Malaysia            | 1         | 0.34%   |
| Luxembourg          | 1         | 0.34%   |
| Lithuania           | 1         | 0.34%   |
| Kenya               | 1         | 0.34%   |
| Ireland             | 1         | 0.34%   |
| Hungary             | 1         | 0.34%   |
| Honduras            | 1         | 0.34%   |
| Estonia             | 1         | 0.34%   |
| Egypt               | 1         | 0.34%   |
| Ecuador             | 1         | 0.34%   |
| Dominican Republic  | 1         | 0.34%   |
| Denmark             | 1         | 0.34%   |
| Croatia             | 1         | 0.34%   |
| Bangladesh          | 1         | 0.34%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Sao Paulo         | 5         | 1.64%   |
| Moscow            | 4         | 1.32%   |
| Wroclaw           | 3         | 0.99%   |
| Wohlen            | 3         | 0.99%   |
| St Petersburg     | 3         | 0.99%   |
| Seville           | 3         | 0.99%   |
| Poznan            | 3         | 0.99%   |
| Manama            | 3         | 0.99%   |
| Zurich            | 2         | 0.66%   |
| Stuttgart         | 2         | 0.66%   |
| Sofia             | 2         | 0.66%   |
| Recife            | 2         | 0.66%   |
| Perth             | 2         | 0.66%   |
| Oruro             | 2         | 0.66%   |
| Nuremberg         | 2         | 0.66%   |
| Neasden           | 2         | 0.66%   |
| Minsk             | 2         | 0.66%   |
| Mannheim          | 2         | 0.66%   |
| London            | 2         | 0.66%   |
| Lisbon            | 2         | 0.66%   |
| Krakow            | 2         | 0.66%   |
| Glasgow           | 2         | 0.66%   |
| Frankfurt am Main | 2         | 0.66%   |
| Foz do Iguaçu    | 2         | 0.66%   |
| Denver            | 2         | 0.66%   |
| Cologne           | 2         | 0.66%   |
| Chelyabinsk       | 2         | 0.66%   |
| Caroline          | 2         | 0.66%   |
| Bursa             | 2         | 0.66%   |
| Berlin            | 2         | 0.66%   |
| Athens            | 2         | 0.66%   |
| Zoetermeer        | 1         | 0.33%   |
| Zhongshan         | 1         | 0.33%   |
| Zapopan           | 1         | 0.33%   |
| Zagreb            | 1         | 0.33%   |
| Zabrze            | 1         | 0.33%   |
| Yuzhno-Sakhalinsk | 1         | 0.33%   |
| Yokohama          | 1         | 0.33%   |
| Yevpatoriya       | 1         | 0.33%   |
| Yan’an          | 1         | 0.33%   |
| Wittichenau       | 1         | 0.33%   |
| Wilberforce       | 1         | 0.33%   |
| Whittier          | 1         | 0.33%   |
| Wellington        | 1         | 0.33%   |
| Voronezh          | 1         | 0.33%   |
| Voluntari         | 1         | 0.33%   |
| Vitebsk           | 1         | 0.33%   |
| Vilnius           | 1         | 0.33%   |
| Vila Matias       | 1         | 0.33%   |
| Vicosa            | 1         | 0.33%   |
| Veurne            | 1         | 0.33%   |
| Verona            | 1         | 0.33%   |
| Veghel            | 1         | 0.33%   |
| Vaslui            | 1         | 0.33%   |
| Uttoxeter         | 1         | 0.33%   |
| Uiwang            | 1         | 0.33%   |
| Turin             | 1         | 0.33%   |
| Tunis             | 1         | 0.33%   |
| Tulbagh           | 1         | 0.33%   |
| Tula              | 1         | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 58        | 64     | 16.11%  |
| Samsung Electronics            | 48        | 53     | 13.33%  |
| Seagate                        | 44        | 55     | 12.22%  |
| Toshiba                        | 26        | 28     | 7.22%   |
| Hitachi                        | 24        | 24     | 6.67%   |
| Unknown                        | 20        | 21     | 5.56%   |
| Kingston                       | 15        | 17     | 4.17%   |
| SanDisk                        | 12        | 16     | 3.33%   |
| HGST                           | 12        | 13     | 3.33%   |
| Intel                          | 9         | 9      | 2.5%    |
| Fujitsu                        | 7         | 7      | 1.94%   |
| Crucial                        | 7         | 8      | 1.94%   |
| SK hynix                       | 6         | 8      | 1.67%   |
| Micron Technology              | 5         | 6      | 1.39%   |
| China                          | 5         | 6      | 1.39%   |
| Phison                         | 4         | 5      | 1.11%   |
| Patriot                        | 4         | 5      | 1.11%   |
| Transcend                      | 3         | 4      | 0.83%   |
| KingSpec                       | 3         | 3      | 0.83%   |
| KingDian                       | 3         | 4      | 0.83%   |
| Goodram                        | 3         | 3      | 0.83%   |
| Apple                          | 3         | 6      | 0.83%   |
| PNY                            | 2         | 2      | 0.56%   |
| JMicron Technology             | 2         | 3      | 0.56%   |
| Intenso                        | 2         | 2      | 0.56%   |
| IBM/Hitachi                    | 2         | 2      | 0.56%   |
| Gigabyte Technology            | 2         | 3      | 0.56%   |
| A-DATA Technology              | 2         | 2      | 0.56%   |
| USB30                          | 1         | 2      | 0.28%   |
| Team                           | 1         | 1      | 0.28%   |
| Solid State Storage Technology | 1         | 1      | 0.28%   |
| ShiJi                          | 1         | 1      | 0.28%   |
| SABRENT                        | 1         | 1      | 0.28%   |
| Plextor                        | 1         | 1      | 0.28%   |
| Oyen                           | 1         | 1      | 0.28%   |
| ORICO                          | 1         | 1      | 0.28%   |
| Netac                          | 1         | 1      | 0.28%   |
| Mushkin                        | 1         | 1      | 0.28%   |
| Micron/Crucial Technology      | 1         | 2      | 0.28%   |
| LITEON                         | 1         | 1      | 0.28%   |
| KIOXIA                         | 1         | 2      | 0.28%   |
| Initio                         | 1         | 1      | 0.28%   |
| HUAWEI                         | 1         | 1      | 0.28%   |
| Hikvision                      | 1         | 1      | 0.28%   |
| Hewlett-Packard                | 1         | 2      | 0.28%   |
| GALAX                          | 1         | 1      | 0.28%   |
| FORESEE                        | 1         | 1      | 0.28%   |
| Drevo                          | 1         | 2      | 0.28%   |
| DAS                            | 1         | 4      | 0.28%   |
| Corsair                        | 1         | 1      | 0.28%   |
| BIWIN                          | 1         | 1      | 0.28%   |
| BHT                            | 1         | 1      | 0.28%   |
| BAITITON                       | 1         | 1      | 0.28%   |
| ASUS-PHISON                    | 1         | 2      | 0.28%   |
| Acer                           | 1         | 1      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB            | 6         | 1.64%   |
| Toshiba MQ01ABD100 1TB               | 5         | 1.37%   |
| Seagate ST500LT012-1DG142 500GB      | 5         | 1.37%   |
| Samsung SSD 860 EVO 1TB              | 5         | 1.37%   |
| Unknown MMC Card  7GB                | 4         | 1.09%   |
| Unknown MMC Card  32GB               | 4         | 1.09%   |
| Toshiba MQ01ABF050 500GB             | 4         | 1.09%   |
| Kingston SA400S37240G 240GB SSD      | 4         | 1.09%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 3         | 0.82%   |
| WDC WD3200BEVT-60ZCT1 320GB          | 3         | 0.82%   |
| Unknown SD/MMC/MS PRO 128GB          | 3         | 0.82%   |
| Seagate ST9500325AS 500GB            | 3         | 0.82%   |
| Seagate ST9250315AS 250GB            | 3         | 0.82%   |
| SanDisk NVMe SSD Drive 256GB         | 3         | 0.82%   |
| Samsung SSD 850 EVO 500GB            | 3         | 0.82%   |
| Kingston SA400S37120G 120GB SSD      | 3         | 0.82%   |
| HGST HTS545050A7E680 500GB           | 3         | 0.82%   |
| WDC WDBNCE5000PNC 500GB SSD          | 2         | 0.55%   |
| WDC WD7500BPVT-75HXZT3 752GB         | 2         | 0.55%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 2         | 0.55%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 2         | 0.55%   |
| WDC WD2500BEVT-22ZCT0 250GB          | 2         | 0.55%   |
| WDC WD1200BEVS-22UST0 120GB          | 2         | 0.55%   |
| WDC PC SN530 NVMe 256GB              | 2         | 0.55%   |
| Unknown MMC Card  4GB                | 2         | 0.55%   |
| Unknown MMC Card  16GB               | 2         | 0.55%   |
| Toshiba MQ01ABD032 320GB             | 2         | 0.55%   |
| Seagate ST9320423AS 320GB            | 2         | 0.55%   |
| Seagate ST9120821AS 120GB            | 2         | 0.55%   |
| Seagate ST320LM001 HN-M320MBB 320GB  | 2         | 0.55%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 0.55%   |
| Seagate Expansion 1TB                | 2         | 0.55%   |
| SanDisk SSD PLUS 480GB               | 2         | 0.55%   |
| Samsung SSD 860 EVO 250GB            | 2         | 0.55%   |
| Samsung SSD 850 EVO mSATA 250GB      | 2         | 0.55%   |
| Samsung PM991a NVMe 512GB            | 2         | 0.55%   |
| Phison NVMe SSD Drive 256GB          | 2         | 0.55%   |
| Micron NVMe SSD Drive 512GB          | 2         | 0.55%   |
| KingSpec MT-128 128GB                | 2         | 0.55%   |
| KingDian S280 120GB SSD              | 2         | 0.55%   |
| JMicron Tech 250GB                   | 2         | 0.55%   |
| Hitachi HTS725050A9A364 500GB        | 2         | 0.55%   |
| Hitachi HTS545032B9A300 320GB        | 2         | 0.55%   |
| Hitachi HTS543232A7A384 320GB        | 2         | 0.55%   |
| Hitachi HTS543216L9A300 160GB        | 2         | 0.55%   |
| Hitachi HTS541680J9SA00 80GB         | 2         | 0.55%   |
| HGST HTS725050A7E630 500GB           | 2         | 0.55%   |
| HGST HTS721010A9E630 1TB             | 2         | 0.55%   |
| HGST HTS545050A7E380 500GB           | 2         | 0.55%   |
| HGST HTS541010A9E680 1TB             | 2         | 0.55%   |
| Goodram SSDPR-CL100-120-G3 120GB     | 2         | 0.55%   |
| Gigabyte GP-GSTFS31120GNTD 120GB SSD | 2         | 0.55%   |
| Fujitsu MHV2080BH 80GB               | 2         | 0.55%   |
| China SATA SSD 120GB                 | 2         | 0.55%   |
| WDC WDS240G2G0B 240GB SSD            | 1         | 0.27%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.27%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1         | 0.27%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 1         | 0.27%   |
| WDC WD800BEVE-00A0HT0 80GB           | 1         | 0.27%   |
| WDC WD7500BPVT-24HXZT1 752GB         | 1         | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 48        | 54     | 28.74%  |
| Seagate             | 43        | 53     | 25.75%  |
| Hitachi             | 24        | 24     | 14.37%  |
| Toshiba             | 23        | 25     | 13.77%  |
| HGST                | 12        | 13     | 7.19%   |
| Fujitsu             | 7         | 7      | 4.19%   |
| Samsung Electronics | 4         | 4      | 2.4%    |
| Unknown             | 3         | 3      | 1.8%    |
| IBM/Hitachi         | 2         | 2      | 1.2%    |
| DAS                 | 1         | 4      | 0.6%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 36        | 41     | 27.69%  |
| Kingston            | 14        | 16     | 10.77%  |
| SanDisk             | 7         | 11     | 5.38%   |
| Crucial             | 7         | 8      | 5.38%   |
| Intel               | 6         | 6      | 4.62%   |
| WDC                 | 5         | 5      | 3.85%   |
| Patriot             | 4         | 5      | 3.08%   |
| China               | 4         | 5      | 3.08%   |
| Transcend           | 3         | 4      | 2.31%   |
| Toshiba             | 3         | 3      | 2.31%   |
| Micron Technology   | 3         | 4      | 2.31%   |
| KingDian            | 3         | 4      | 2.31%   |
| Goodram             | 3         | 3      | 2.31%   |
| SK hynix            | 2         | 3      | 1.54%   |
| PNY                 | 2         | 2      | 1.54%   |
| KingSpec            | 2         | 2      | 1.54%   |
| Gigabyte Technology | 2         | 3      | 1.54%   |
| Apple               | 2         | 2      | 1.54%   |
| A-DATA Technology   | 2         | 2      | 1.54%   |
| USB30               | 1         | 2      | 0.77%   |
| Unknown             | 1         | 1      | 0.77%   |
| Team                | 1         | 1      | 0.77%   |
| Plextor             | 1         | 1      | 0.77%   |
| ORICO               | 1         | 1      | 0.77%   |
| Netac               | 1         | 1      | 0.77%   |
| Mushkin             | 1         | 1      | 0.77%   |
| LITEON              | 1         | 1      | 0.77%   |
| Intenso             | 1         | 1      | 0.77%   |
| Hikvision           | 1         | 1      | 0.77%   |
| Hewlett-Packard     | 1         | 2      | 0.77%   |
| GALAX               | 1         | 1      | 0.77%   |
| FORESEE             | 1         | 1      | 0.77%   |
| Drevo               | 1         | 2      | 0.77%   |
| Corsair             | 1         | 1      | 0.77%   |
| BIWIN               | 1         | 1      | 0.77%   |
| BHT                 | 1         | 1      | 0.77%   |
| BAITITON            | 1         | 1      | 0.77%   |
| ASUS-PHISON         | 1         | 2      | 0.77%   |
| Acer                | 1         | 1      | 0.77%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 160       | 189    | 47.34%  |
| SSD     | 116       | 153    | 34.32%  |
| NVMe    | 35        | 43     | 10.36%  |
| MMC     | 16        | 17     | 4.73%   |
| Unknown | 11        | 13     | 3.25%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 260       | 326    | 78.79%  |
| NVMe | 34        | 42     | 10.3%   |
| SAS  | 20        | 30     | 6.06%   |
| MMC  | 16        | 17     | 4.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 223       | 277    | 81.09%  |
| 0.51-1.0   | 46        | 59     | 16.73%  |
| 1.01-2.0   | 2         | 2      | 0.73%   |
| 4.01-10.0  | 2         | 2      | 0.73%   |
| 3.01-4.0   | 1         | 1      | 0.36%   |
| 2.01-3.0   | 1         | 1      | 0.36%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 117       | 39%     |
| 251-500        | 76        | 25.33%  |
| 51-100         | 34        | 11.33%  |
| 501-1000       | 31        | 10.33%  |
| 21-50          | 15        | 5%      |
| 1001-2000      | 10        | 3.33%   |
| More than 3000 | 7         | 2.33%   |
| 1-20           | 6         | 2%      |
| 2001-3000      | 3         | 1%      |
| Unknown        | 1         | 0.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 156       | 50%     |
| 21-50          | 70        | 22.44%  |
| 101-250        | 32        | 10.26%  |
| 51-100         | 29        | 9.29%   |
| 251-500        | 8         | 2.56%   |
| 501-1000       | 7         | 2.24%   |
| 2001-3000      | 4         | 1.28%   |
| More than 3000 | 3         | 0.96%   |
| 1001-2000      | 2         | 0.64%   |
| Unknown        | 1         | 0.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD3200BEVT-26A23T0 320GB        | 1         | 1      | 7.69%   |
| Seagate STM9120817AS 120GB          | 1         | 1      | 7.69%   |
| Seagate ST9640423AS 640GB           | 1         | 1      | 7.69%   |
| Seagate ST9120821AS 120GB           | 1         | 1      | 7.69%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 1         | 1      | 7.69%   |
| Samsung Electronics MP0402H 40GB    | 1         | 1      | 7.69%   |
| Phison ES 512GB                     | 1         | 1      | 7.69%   |
| Kingston SV300S37A120G 120GB SSD    | 1         | 1      | 7.69%   |
| Intel SSDSCKKF256G8 SATA 256GB      | 1         | 1      | 7.69%   |
| Hitachi HTS547575A9E384 752GB       | 1         | 1      | 7.69%   |
| HGST HTS545050A7E680 500GB          | 1         | 1      | 7.69%   |
| Fujitsu MHZ2080BJ FFS G2 80GB       | 1         | 1      | 7.69%   |
| Crucial M4-CT256M4SSD2 256GB        | 1         | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 23.08%  |
| WDC                 | 1         | 1      | 7.69%   |
| SanDisk             | 1         | 1      | 7.69%   |
| Samsung Electronics | 1         | 1      | 7.69%   |
| Phison              | 1         | 1      | 7.69%   |
| Kingston            | 1         | 1      | 7.69%   |
| Intel               | 1         | 1      | 7.69%   |
| Hitachi             | 1         | 1      | 7.69%   |
| HGST                | 1         | 1      | 7.69%   |
| Fujitsu             | 1         | 1      | 7.69%   |
| Crucial             | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 37.5%   |
| WDC                 | 1         | 1      | 12.5%   |
| Samsung Electronics | 1         | 1      | 12.5%   |
| Hitachi             | 1         | 1      | 12.5%   |
| HGST                | 1         | 1      | 12.5%   |
| Fujitsu             | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 8      | 61.54%  |
| SSD  | 4         | 4      | 30.77%  |
| NVMe | 1         | 1      | 7.69%   |

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
| Detected | 240       | 344    | 80%     |
| Works    | 47        | 58     | 15.67%  |
| Malfunc  | 13        | 13     | 4.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 225       | 71.2%   |
| AMD                              | 43        | 13.61%  |
| SanDisk                          | 9         | 2.85%   |
| Samsung Electronics              | 9         | 2.85%   |
| Silicon Integrated Systems [SiS] | 6         | 1.9%    |
| Nvidia                           | 6         | 1.9%    |
| SK hynix                         | 4         | 1.27%   |
| Phison Electronics               | 4         | 1.27%   |
| Toshiba America Info Systems     | 2         | 0.63%   |
| Micron Technology                | 2         | 0.63%   |
| VIA Technologies                 | 1         | 0.32%   |
| Solid State Storage Technology   | 1         | 0.32%   |
| Micron/Crucial Technology        | 1         | 0.32%   |
| Marvell Technology Group         | 1         | 0.32%   |
| Kingston Technology Company      | 1         | 0.32%   |
| Apple                            | 1         | 0.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 27        | 7.4%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 21        | 5.75%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 20        | 5.48%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 18        | 4.93%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 14        | 3.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 13        | 3.56%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 12        | 3.29%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 12        | 3.29%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 12        | 3.29%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 11        | 3.01%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 11        | 3.01%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 9         | 2.47%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 9         | 2.47%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 9         | 2.47%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 9         | 2.47%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 8         | 2.19%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 6         | 1.64%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 6         | 1.64%   |
| SanDisk Non-Volatile memory controller                                                 | 5         | 1.37%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 5         | 1.37%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 4         | 1.1%    |
| Samsung NVMe SSD Controller 980                                                        | 4         | 1.1%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 4         | 1.1%    |
| Intel Volume Management Device NVMe RAID Controller                                    | 4         | 1.1%    |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                             | 4         | 1.1%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 4         | 1.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 4         | 1.1%    |
| AMD IXP SB4x0 IDE Controller                                                           | 4         | 1.1%    |
| SK hynix BC501 NVMe Solid State Drive                                                  | 3         | 0.82%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 3         | 0.82%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 3         | 0.82%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 3         | 0.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 3         | 0.82%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                 | 3         | 0.82%   |
| AMD SB600 Non-Raid-5 SATA                                                              | 3         | 0.82%   |
| AMD SB600 IDE                                                                          | 3         | 0.82%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 2         | 0.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 2         | 0.55%   |
| Phison PS5013 E13 NVMe Controller                                                      | 2         | 0.55%   |
| Phison E12 NVMe Controller                                                             | 2         | 0.55%   |
| Nvidia MCP79 AHCI Controller                                                           | 2         | 0.55%   |
| Nvidia MCP67 IDE Controller                                                            | 2         | 0.55%   |
| Nvidia MCP67 AHCI Controller                                                           | 2         | 0.55%   |
| Micron Non-Volatile memory controller                                                  | 2         | 0.55%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                        | 2         | 0.55%   |
| Intel SSD 660P Series                                                                  | 2         | 0.55%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 2         | 0.55%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                               | 2         | 0.55%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                           | 2         | 0.55%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                                 | 2         | 0.55%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 2         | 0.55%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 2         | 0.55%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 0.55%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 0.55%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 2         | 0.55%   |
| AMD IXP SB4x0 Serial ATA Controller                                                    | 2         | 0.55%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                            | 1         | 0.27%   |
| VIA VT8237A SATA 2-Port Controller                                                     | 1         | 0.27%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 1         | 0.27%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 1         | 0.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 218       | 63.01%  |
| IDE  | 74        | 21.39%  |
| NVMe | 35        | 10.12%  |
| RAID | 19        | 5.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 243       | 82.09%  |
| AMD    | 53        | 17.91%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom CPU N2600 @ 1.60GHz                | 10        | 3.38%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 6         | 2.03%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz          | 5         | 1.69%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 1.35%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 4         | 1.35%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 4         | 1.35%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 4         | 1.35%   |
| Intel Genuine CPU T2300 @ 1.66GHz             | 3         | 1.01%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.01%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 1.01%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 1.01%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 3         | 1.01%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 3         | 1.01%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 1.01%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 3         | 1.01%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 3         | 1.01%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.01%   |
| Intel Pentium M processor 2.00GHz             | 2         | 0.68%   |
| Intel Pentium M processor 1.73GHz             | 2         | 0.68%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 2         | 0.68%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 2         | 0.68%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 2         | 0.68%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 2         | 0.68%   |
| Intel Genuine CPU T2130 @ 1.86GHz             | 2         | 0.68%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.68%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 0.68%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 0.68%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.68%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.68%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 2         | 0.68%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 2         | 0.68%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 0.68%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 2         | 0.68%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 2         | 0.68%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.68%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 0.68%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.68%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 0.68%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 0.68%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 2         | 0.68%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 0.68%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 2         | 0.68%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2         | 0.68%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 2         | 0.68%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 2         | 0.68%   |
| Intel Core Duo CPU T2400 @ 1.83GHz            | 2         | 0.68%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 2         | 0.68%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz          | 2         | 0.68%   |
| Intel Core 2 CPU T5600 @ 1.83GHz              | 2         | 0.68%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 0.68%   |
| Intel Celeron CPU 900 @ 2.20GHz               | 2         | 0.68%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 2         | 0.68%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 0.68%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 0.68%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 2         | 0.68%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 0.68%   |
| AMD E2-9000e RADEON R2, 4 COMPUTE CORES 2C+2G | 2         | 0.68%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 2         | 0.68%   |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G  | 2         | 0.68%   |
| AMD 3020e with Radeon Graphics                | 2         | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 44        | 14.86%  |
| Intel Core i7                  | 38        | 12.84%  |
| Intel Core i3                  | 29        | 9.8%    |
| Intel Core 2 Duo               | 28        | 9.46%   |
| Intel Atom                     | 27        | 9.12%   |
| Intel Celeron                  | 20        | 6.76%   |
| Other                          | 13        | 4.39%   |
| Intel Pentium                  | 10        | 3.38%   |
| AMD Ryzen 5                    | 10        | 3.38%   |
| Intel Genuine                  | 8         | 2.7%    |
| Intel Pentium M                | 6         | 2.03%   |
| Intel Pentium Dual             | 6         | 2.03%   |
| Intel Core 2                   | 6         | 2.03%   |
| AMD A4                         | 5         | 1.69%   |
| Intel Pentium Dual-Core        | 4         | 1.35%   |
| AMD Ryzen 7                    | 4         | 1.35%   |
| AMD E2                         | 4         | 1.35%   |
| Intel Core Duo                 | 3         | 1.01%   |
| AMD Turion 64 X2 Mobile        | 3         | 1.01%   |
| Intel Pentium 4                | 2         | 0.68%   |
| Intel Celeron M                | 2         | 0.68%   |
| AMD Sempron                    | 2         | 0.68%   |
| AMD Mobile Sempron             | 2         | 0.68%   |
| AMD E1                         | 2         | 0.68%   |
| AMD E                          | 2         | 0.68%   |
| AMD Athlon II                  | 2         | 0.68%   |
| Intel Pentium Silver           | 1         | 0.34%   |
| Intel Mobile Pentium 4         | 1         | 0.34%   |
| Intel Core 2 Extreme           | 1         | 0.34%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.34%   |
| AMD Turion 64 Mobile           | 1         | 0.34%   |
| AMD Ryzen 3                    | 1         | 0.34%   |
| AMD Phenom II                  | 1         | 0.34%   |
| AMD C-50                       | 1         | 0.34%   |
| AMD Athlon Neo                 | 1         | 0.34%   |
| AMD Athlon 64 X2               | 1         | 0.34%   |
| AMD Athlon                     | 1         | 0.34%   |
| AMD A8                         | 1         | 0.34%   |
| AMD A6                         | 1         | 0.34%   |
| AMD A10                        | 1         | 0.34%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 194       | 65.32%  |
| 4      | 55        | 18.52%  |
| 1      | 39        | 13.13%  |
| 6      | 5         | 1.68%   |
| 8      | 4         | 1.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 296       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 165       | 55.74%  |
| 1      | 131       | 44.26%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 255       | 86.15%  |
| 32-bit         | 41        | 13.85%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 7.02%   |
| 0x206a7    | 19        | 6.35%   |
| 0x306a9    | 18        | 6.02%   |
| 0x1067a    | 18        | 6.02%   |
| 0x6fd      | 12        | 4.01%   |
| 0x40651    | 12        | 4.01%   |
| 0x30661    | 12        | 4.01%   |
| 0x406e3    | 11        | 3.68%   |
| 0x106c2    | 11        | 3.68%   |
| 0x20655    | 9         | 3.01%   |
| 0x806ea    | 8         | 2.68%   |
| 0x306c3    | 8         | 2.68%   |
| 0x06006705 | 8         | 2.68%   |
| 0x6f6      | 7         | 2.34%   |
| 0x6ec      | 7         | 2.34%   |
| 0x806c1    | 6         | 2.01%   |
| 0x20652    | 6         | 2.01%   |
| 0x10676    | 6         | 2.01%   |
| 0x6e8      | 5         | 1.67%   |
| 0x30678    | 5         | 1.67%   |
| 0x08608103 | 5         | 1.67%   |
| 0x806e9    | 4         | 1.34%   |
| 0x6d8      | 4         | 1.34%   |
| 0x506e3    | 4         | 1.34%   |
| 0x306d4    | 4         | 1.34%   |
| 0x08108102 | 4         | 1.34%   |
| 0x806ec    | 3         | 1%      |
| 0x806eb    | 3         | 1%      |
| 0x706a1    | 3         | 1%      |
| 0x106e5    | 3         | 1%      |
| 0x106ca    | 3         | 1%      |
| 0x010000c8 | 3         | 1%      |
| 0xf29      | 2         | 0.67%   |
| 0x706e5    | 2         | 0.67%   |
| 0x406c4    | 2         | 0.67%   |
| 0x406c3    | 2         | 0.67%   |
| 0x30673    | 2         | 0.67%   |
| 0x10661    | 2         | 0.67%   |
| 0x08200103 | 2         | 0.67%   |
| 0x08108109 | 2         | 0.67%   |
| 0x07030106 | 2         | 0.67%   |
| 0x07030105 | 2         | 0.67%   |
| 0x05000029 | 2         | 0.67%   |
| 0x02000032 | 2         | 0.67%   |
| 0xf24      | 1         | 0.33%   |
| 0xa0652    | 1         | 0.33%   |
| 0x906ed    | 1         | 0.33%   |
| 0x906ea    | 1         | 0.33%   |
| 0x906e9    | 1         | 0.33%   |
| 0x806d1    | 1         | 0.33%   |
| 0x706a8    | 1         | 0.33%   |
| 0x6fb      | 1         | 0.33%   |
| 0x6fa      | 1         | 0.33%   |
| 0x6d6      | 1         | 0.33%   |
| 0x695      | 1         | 0.33%   |
| 0x506c9    | 1         | 0.33%   |
| 0x20661    | 1         | 0.33%   |
| 0x08600103 | 1         | 0.33%   |
| 0x08101016 | 1         | 0.33%   |
| 0x0810100b | 1         | 0.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Penryn          | 27        | 9.12%   |
| Bonnell         | 27        | 9.12%   |
| Core            | 23        | 7.77%   |
| KabyLake        | 22        | 7.43%   |
| Haswell         | 21        | 7.09%   |
| SandyBridge     | 20        | 6.76%   |
| P6              | 18        | 6.08%   |
| IvyBridge       | 18        | 6.08%   |
| Westmere        | 15        | 5.07%   |
| Skylake         | 15        | 5.07%   |
| Silvermont      | 11        | 3.72%   |
| Excavator       | 10        | 3.38%   |
| K8 Hammer       | 9         | 3.04%   |
| Zen+            | 6         | 2.03%   |
| TigerLake       | 6         | 2.03%   |
| Broadwell       | 5         | 1.69%   |
| Unknown         | 5         | 1.69%   |
| Zen             | 4         | 1.35%   |
| Puma            | 4         | 1.35%   |
| K10             | 4         | 1.35%   |
| Goldmont plus   | 4         | 1.35%   |
| NetBurst        | 3         | 1.01%   |
| Nehalem         | 3         | 1.01%   |
| IceLake         | 3         | 1.01%   |
| Bobcat          | 3         | 1.01%   |
| K8 & K10 hybrid | 2         | 0.68%   |
| Jaguar          | 2         | 0.68%   |
| Zen 3           | 1         | 0.34%   |
| Zen 2           | 1         | 0.34%   |
| Piledriver      | 1         | 0.34%   |
| K10 Llano       | 1         | 0.34%   |
| Goldmont        | 1         | 0.34%   |
| CometLake       | 1         | 0.34%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 189       | 55.59%  |
| AMD                              | 80        | 23.53%  |
| Nvidia                           | 65        | 19.12%  |
| Silicon Integrated Systems [SiS] | 5         | 1.47%   |
| VIA Technologies                 | 1         | 0.29%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                      | Notebooks | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller              | 16        | 4.4%    |
| Intel 3rd Gen Core processor Graphics Controller                                           | 16        | 4.4%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 16        | 4.4%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                               | 14        | 3.85%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                            | 12        | 3.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                                           | 11        | 3.02%   |
| Intel Core Processor Integrated Graphics Controller                                        | 11        | 3.02%   |
| Intel Skylake GT2 [HD Graphics 520]                                                        | 10        | 2.75%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                                | 9         | 2.47%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                   | 9         | 2.47%   |
| Intel UHD Graphics 620                                                                     | 8         | 2.2%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                                 | 8         | 2.2%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                  | 8         | 2.2%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                       | 8         | 2.2%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                               | 7         | 1.92%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                                 | 6         | 1.65%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                        | 5         | 1.37%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                          | 5         | 1.37%   |
| AMD Lucienne                                                                               | 5         | 1.37%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                        | 4         | 1.1%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                  | 4         | 1.1%    |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                  | 4         | 1.1%    |
| Intel HD Graphics 530                                                                      | 4         | 1.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller   | 4         | 1.1%    |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                  | 4         | 1.1%    |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                          | 3         | 0.82%   |
| Nvidia GF108M [GeForce GT 525M]                                                            | 3         | 0.82%   |
| Nvidia G96CM [GeForce 9600M GT]                                                            | 3         | 0.82%   |
| Intel HD Graphics 5500                                                                     | 3         | 0.82%   |
| Intel GeminiLake [UHD Graphics 600]                                                        | 3         | 0.82%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                    | 3         | 0.82%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]              | 3         | 0.82%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                          | 3         | 0.82%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                   | 3         | 0.82%   |
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 2         | 0.55%   |
| Nvidia GT218M [NVS 3100M]                                                                  | 2         | 0.55%   |
| Nvidia GP108M [GeForce MX150]                                                              | 2         | 0.55%   |
| Nvidia GM108M [GeForce 940MX]                                                              | 2         | 0.55%   |
| Nvidia GM108M [GeForce 840M]                                                               | 2         | 0.55%   |
| Nvidia GM107M [GeForce GTX 960M]                                                           | 2         | 0.55%   |
| Nvidia GK107M [GeForce GT 750M]                                                            | 2         | 0.55%   |
| Nvidia GK106GLM [Quadro K2100M]                                                            | 2         | 0.55%   |
| Nvidia GF119M [NVS 4200M]                                                                  | 2         | 0.55%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                       | 2         | 0.55%   |
| Nvidia GF108GLM [Quadro 1000M]                                                             | 2         | 0.55%   |
| Nvidia G98M [Quadro NVS 160M]                                                              | 2         | 0.55%   |
| Nvidia C79 [GeForce 9400M]                                                                 | 2         | 0.55%   |
| Intel Tiger Lake UHD Graphics                                                              | 2         | 0.55%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                     | 2         | 0.55%   |
| Intel HD Graphics 620                                                                      | 2         | 0.55%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                  | 2         | 0.55%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]      | 2         | 0.55%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                   | 2         | 0.55%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                                 | 2         | 0.55%   |
| AMD RV350/M10 / RV360/M11 [Mobility Radeon 9600 (PRO) / 9700]                              | 2         | 0.55%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                                        | 2         | 0.55%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                  | 2         | 0.55%   |
| AMD RS480M [Mobility Radeon Xpress 200]                                                    | 2         | 0.55%   |
| AMD RC410M [Mobility Radeon Xpress 200M]                                                   | 2         | 0.55%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                           | 2         | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 145       | 48.99%  |
| 1 x AMD        | 66        | 22.3%   |
| 1 x Nvidia     | 33        | 11.15%  |
| Intel + Nvidia | 32        | 10.81%  |
| Intel + AMD    | 12        | 4.05%   |
| 1 x SiS        | 5         | 1.69%   |
| 2 x AMD        | 2         | 0.68%   |
| 1 x VIA        | 1         | 0.34%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 262       | 88.22%  |
| Unknown     | 23        | 7.74%   |
| Proprietary | 12        | 4.04%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 187       | 63.18%  |
| 0.01-0.5   | 57        | 19.26%  |
| 1.01-2.0   | 27        | 9.12%   |
| 0.51-1.0   | 18        | 6.08%   |
| 3.01-4.0   | 4         | 1.35%   |
| 5.01-6.0   | 2         | 0.68%   |
| 2.01-3.0   | 1         | 0.34%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 54        | 18.88%  |
| LG Display              | 42        | 14.69%  |
| Samsung Electronics     | 35        | 12.24%  |
| BOE                     | 35        | 12.24%  |
| Chimei Innolux          | 29        | 10.14%  |
| Chi Mei Optoelectronics | 12        | 4.2%    |
| LG Philips              | 11        | 3.85%   |
| HannStar                | 8         | 2.8%    |
| Goldstar                | 7         | 2.45%   |
| Apple                   | 6         | 2.1%    |
| Lenovo                  | 5         | 1.75%   |
| InfoVision              | 4         | 1.4%    |
| BenQ                    | 4         | 1.4%    |
| Sony                    | 3         | 1.05%   |
| Quanta Display          | 3         | 1.05%   |
| PANDA                   | 3         | 1.05%   |
| Dell                    | 3         | 1.05%   |
| CPT                     | 3         | 1.05%   |
| AOC                     | 2         | 0.7%    |
| Acer                    | 2         | 0.7%    |
| ViewSonic               | 1         | 0.35%   |
| Unknown                 | 1         | 0.35%   |
| TR_                     | 1         | 0.35%   |
| Sharp                   | 1         | 0.35%   |
| Seiko/Epson             | 1         | 0.35%   |
| Planar                  | 1         | 0.35%   |
| Philips                 | 1         | 0.35%   |
| Panasonic               | 1         | 0.35%   |
| MLT                     | 1         | 0.35%   |
| Insignia                | 1         | 0.35%   |
| InnoLux Display         | 1         | 0.35%   |
| Hewlett-Packard         | 1         | 0.35%   |
| DENON                   | 1         | 0.35%   |
| BLS                     | 1         | 0.35%   |
| Belinea                 | 1         | 0.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 6         | 2.07%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch              | 3         | 1.03%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 3         | 1.03%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 3         | 1.03%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 3         | 1.03%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 3         | 1.03%   |
| Chi Mei Optoelectronics LCD Monitor CMO1018 1024x600 222x125mm 10.0-inch | 3         | 1.03%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 3         | 1.03%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch            | 3         | 1.03%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 3         | 1.03%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 3         | 1.03%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 0.69%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch     | 2         | 0.69%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch     | 2         | 0.69%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 223x125mm 10.1-inch     | 2         | 0.69%   |
| Quanta Display LCD Monitor QDS0025 1024x768 304x228mm 15.0-inch          | 2         | 0.69%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 2         | 0.69%   |
| LG Philips LCD Monitor LPL0140 1440x900 304x190mm 14.1-inch              | 2         | 0.69%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                 | 2         | 0.69%   |
| HannStar HSD101PFW4A HSD03ED 1024x600 223x125mm 10.1-inch                | 2         | 0.69%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                     | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch          | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 309x174mm 14.0-inch          | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 2         | 0.69%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 2         | 0.69%   |
| Chi Mei Optoelectronics LCD Monitor CMO1558 1366x768 344x193mm 15.5-inch | 2         | 0.69%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 2         | 0.69%   |
| BOE LCD Monitor BOE072B 1920x1080 309x173mm 13.9-inch                    | 2         | 0.69%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 2         | 0.69%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 2         | 0.69%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                     | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch            | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO2174 1280x800 331x207mm 15.4-inch            | 2         | 0.69%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                   | 1         | 0.34%   |
| Unknown LCD Monitor XXX AAA                                              | 1         | 0.34%   |
| TR_ LCD Monitor TR_5511 1366x768 518x333mm 24.2-inch                     | 1         | 0.34%   |
| Sony TV SNYA301 1920x1080 1600x900mm 72.3-inch                           | 1         | 0.34%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                    | 1         | 0.34%   |
| Sony AVAMP SNYF700 1920x540                                              | 1         | 0.34%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                  | 1         | 0.34%   |
| Seiko/Epson LCD Monitor 1920x1080                                        | 1         | 0.34%   |
| Samsung Electronics SMB2230H SAM0648 1920x1080                           | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC5742 1366x768 309x174mm 14.0-inch     | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC554E 1024x600 223x125mm 10.1-inch     | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 331x207mm 15.4-inch    | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC4642 1280x800 303x190mm 14.1-inch     | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC4457 1440x900 303x190mm 14.1-inch     | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC4442 1280x800 303x190mm 14.1-inch     | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch     | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC3659 1600x900 344x194mm 15.5-inch     | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch     | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC3450 1400x1050 286x214mm 14.1-inch    | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC3445 1280x800 331x207mm 15.4-inch     | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 330x210mm 15.4-inch     | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch     | 1         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 102       | 36.3%   |
| 1920x1080 (FHD)    | 80        | 28.47%  |
| 1280x800 (WXGA)    | 30        | 10.68%  |
| 1600x900 (HD+)     | 17        | 6.05%   |
| 1024x600           | 15        | 5.34%   |
| 1440x900 (WXGA+)   | 7         | 2.49%   |
| 1920x1200 (WUXGA)  | 6         | 2.14%   |
| 3840x2160 (4K)     | 5         | 1.78%   |
| 2560x1440 (QHD)    | 2         | 0.71%   |
| 1680x1050 (WSXGA+) | 2         | 0.71%   |
| 1280x768           | 2         | 0.71%   |
| 1280x1024 (SXGA)   | 2         | 0.71%   |
| 1024x768 (XGA)     | 2         | 0.71%   |
| 3840x1080          | 1         | 0.36%   |
| 2880x1800          | 1         | 0.36%   |
| 2560x1080          | 1         | 0.36%   |
| 2256x1504          | 1         | 0.36%   |
| 1920x540           | 1         | 0.36%   |
| 1400x1050          | 1         | 0.36%   |
| 1360x768           | 1         | 0.36%   |
| 1280x720 (HD)      | 1         | 0.36%   |
| Unknown            | 1         | 0.36%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 133       | 46.5%   |
| 14      | 36        | 12.59%  |
| 13      | 31        | 10.84%  |
| 17      | 19        | 6.64%   |
| 10      | 14        | 4.9%    |
| 12      | 6         | 2.1%    |
| 11      | 6         | 2.1%    |
| 27      | 5         | 1.75%   |
| 18      | 5         | 1.75%   |
| 24      | 4         | 1.4%    |
| 23      | 4         | 1.4%    |
| 21      | 4         | 1.4%    |
| Unknown | 4         | 1.4%    |
| 72      | 3         | 1.05%   |
| 19      | 3         | 1.05%   |
| 34      | 2         | 0.7%    |
| 31      | 2         | 0.7%    |
| 8       | 2         | 0.7%    |
| 48      | 1         | 0.35%   |
| 20      | 1         | 0.35%   |
| 16      | 1         | 0.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 184       | 64.79%  |
| 201-300     | 38        | 13.38%  |
| 351-400     | 26        | 9.15%   |
| 501-600     | 11        | 3.87%   |
| 401-500     | 11        | 3.87%   |
| Unknown     | 4         | 1.41%   |
| 1501-2000   | 3         | 1.06%   |
| 701-800     | 2         | 0.7%    |
| 601-700     | 2         | 0.7%    |
| 101-200     | 2         | 0.7%    |
| 1001-1500   | 1         | 0.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 210       | 78.65%  |
| 16/10   | 45        | 16.85%  |
| 5/4     | 3         | 1.12%   |
| 4/3     | 3         | 1.12%   |
| 3/2     | 2         | 0.75%   |
| Unknown | 2         | 0.75%   |
| 32/9    | 1         | 0.37%   |
| 21/9    | 1         | 0.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 132       | 45.99%  |
| 81-90          | 58        | 20.21%  |
| 41-50          | 14        | 4.88%   |
| 121-130        | 14        | 4.88%   |
| 201-250        | 9         | 3.14%   |
| 71-80          | 8         | 2.79%   |
| 61-70          | 6         | 2.09%   |
| 51-60          | 6         | 2.09%   |
| 301-350        | 5         | 1.74%   |
| 151-200        | 5         | 1.74%   |
| 141-150        | 5         | 1.74%   |
| 131-140        | 5         | 1.74%   |
| More than 1000 | 4         | 1.39%   |
| 91-100         | 4         | 1.39%   |
| Unknown        | 4         | 1.39%   |
| 351-500        | 3         | 1.05%   |
| 1-40           | 2         | 0.7%    |
| 251-300        | 2         | 0.7%    |
| 501-1000       | 1         | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 127       | 45.04%  |
| 121-160       | 81        | 28.72%  |
| 51-100        | 55        | 19.5%   |
| 161-240       | 7         | 2.48%   |
| 1-50          | 5         | 1.77%   |
| Unknown       | 4         | 1.42%   |
| More than 240 | 3         | 1.06%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 251       | 83.95%  |
| 2     | 29        | 9.7%    |
| 0     | 18        | 6.02%   |
| 3     | 1         | 0.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 168       | 33.27%  |
| Intel                                 | 110       | 21.78%  |
| Qualcomm Atheros                      | 98        | 19.41%  |
| Broadcom                              | 48        | 9.5%    |
| Marvell Technology Group              | 13        | 2.57%   |
| Broadcom Limited                      | 11        | 2.18%   |
| Ralink                                | 7         | 1.39%   |
| Silicon Integrated Systems [SiS]      | 5         | 0.99%   |
| Samsung Electronics                   | 5         | 0.99%   |
| Nvidia                                | 5         | 0.99%   |
| JMicron Technology                    | 3         | 0.59%   |
| Ericsson Business Mobile Networks     | 3         | 0.59%   |
| Xiaomi                                | 2         | 0.4%    |
| Ralink Technology                     | 2         | 0.4%    |
| Huawei Technologies                   | 2         | 0.4%    |
| Attansic Technology                   | 2         | 0.4%    |
| AMD                                   | 2         | 0.4%    |
| ZTE WCDMA Technologies MSM            | 1         | 0.2%    |
| VIA Technologies                      | 1         | 0.2%    |
| TP-Link                               | 1         | 0.2%    |
| ST-Ericsson                           | 1         | 0.2%    |
| Sierra Wireless                       | 1         | 0.2%    |
| OnePlus Technology (Shenzhen)         | 1         | 0.2%    |
| NetGear                               | 1         | 0.2%    |
| MediaTek                              | 1         | 0.2%    |
| Manta                                 | 1         | 0.2%    |
| Linksys                               | 1         | 0.2%    |
| Lenovo                                | 1         | 0.2%    |
| Intersil                              | 1         | 0.2%    |
| Hewlett-Packard                       | 1         | 0.2%    |
| Gemtek                                | 1         | 0.2%    |
| DisplayLink                           | 1         | 0.2%    |
| Dell                                  | 1         | 0.2%    |
| Cisco Aironet Wireless Communications | 1         | 0.2%    |
| ASUSTek Computer                      | 1         | 0.2%    |
| Askey Computer                        | 1         | 0.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 82        | 13.46%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 51        | 8.37%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 20        | 3.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 15        | 2.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 14        | 2.3%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 14        | 2.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 13        | 2.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 12        | 1.97%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 1.97%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 12        | 1.97%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 9         | 1.48%   |
| Intel WiFi Link 5100                                                    | 9         | 1.48%   |
| Intel Wireless 7260                                                     | 8         | 1.31%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 1.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 7         | 1.15%   |
| Intel Wireless 8265 / 8275                                              | 6         | 0.99%   |
| Intel 82567LM Gigabit Network Connection                                | 6         | 0.99%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 5         | 0.82%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 5         | 0.82%   |
| Intel Wireless 3160                                                     | 5         | 0.82%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 0.82%   |
| Intel 82577LM Gigabit Network Connection                                | 5         | 0.82%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 4         | 0.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 0.66%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 4         | 0.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 0.66%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 4         | 0.66%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                 | 4         | 0.66%   |
| Intel Wireless 3165                                                     | 4         | 0.66%   |
| Intel Ultimate N WiFi Link 5300                                         | 4         | 0.66%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 0.66%   |
| Intel Ethernet Connection I217-LM                                       | 4         | 0.66%   |
| Intel 82573L Gigabit Ethernet Controller                                | 4         | 0.66%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 4         | 0.66%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 3         | 0.49%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.49%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 0.49%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 0.49%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 0.49%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.49%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 0.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 3         | 0.49%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 3         | 0.49%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 3         | 0.49%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 3         | 0.49%   |
| Intel Wireless 8260                                                     | 3         | 0.49%   |
| Intel Wireless 7265                                                     | 3         | 0.49%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 0.49%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 3         | 0.49%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 0.49%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 0.49%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                       | 3         | 0.49%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 3         | 0.49%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express          | 3         | 0.49%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 0.49%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 3         | 0.49%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 2         | 0.33%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet               | 2         | 0.33%   |
| Silicon Integrated Systems [SiS] AC'97 Modem Controller                 | 2         | 0.33%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 2         | 0.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 96        | 31.58%  |
| Qualcomm Atheros                      | 89        | 29.28%  |
| Realtek Semiconductor                 | 62        | 20.39%  |
| Broadcom                              | 35        | 11.51%  |
| Ralink                                | 7         | 2.3%    |
| Broadcom Limited                      | 6         | 1.97%   |
| Ralink Technology                     | 2         | 0.66%   |
| TP-Link                               | 1         | 0.33%   |
| Sierra Wireless                       | 1         | 0.33%   |
| NetGear                               | 1         | 0.33%   |
| Linksys                               | 1         | 0.33%   |
| Cisco Aironet Wireless Communications | 1         | 0.33%   |
| ASUSTek Computer                      | 1         | 0.33%   |
| Askey Computer                        | 1         | 0.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 20        | 6.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 15        | 4.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 14        | 4.52%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 14        | 4.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 13        | 4.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 12        | 3.87%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 3.87%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 12        | 3.87%   |
| Intel WiFi Link 5100                                                    | 9         | 2.9%    |
| Intel Wireless 7260                                                     | 8         | 2.58%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 2.26%   |
| Intel Wireless 8265 / 8275                                              | 6         | 1.94%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 5         | 1.61%   |
| Intel Wireless 3160                                                     | 5         | 1.61%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 1.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.29%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 4         | 1.29%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 1.29%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 4         | 1.29%   |
| Intel Wireless 3165                                                     | 4         | 1.29%   |
| Intel Ultimate N WiFi Link 5300                                         | 4         | 1.29%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 1.29%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 4         | 1.29%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.97%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 0.97%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 0.97%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 0.97%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.97%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 0.97%   |
| Intel Wireless 8260                                                     | 3         | 0.97%   |
| Intel Wireless 7265                                                     | 3         | 0.97%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 0.97%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 3         | 0.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 0.97%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 0.97%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 0.97%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 3         | 0.97%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 2         | 0.65%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 0.65%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 2         | 0.65%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 2         | 0.65%   |
| Realtek 802.11ac NIC                                                    | 2         | 0.65%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 0.65%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 0.65%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 2         | 0.65%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 0.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.65%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 0.65%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 2         | 0.65%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 0.65%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.32%   |
| Sierra Wireless MC8305 Modem                                            | 1         | 0.32%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.32%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 0.32%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 1         | 0.32%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.32%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.32%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 1         | 0.32%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 0.32%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 0.32%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 145       | 51.6%   |
| Intel                            | 46        | 16.37%  |
| Qualcomm Atheros                 | 23        | 8.19%   |
| Broadcom                         | 18        | 6.41%   |
| Marvell Technology Group         | 13        | 4.63%   |
| Silicon Integrated Systems [SiS] | 5         | 1.78%   |
| Samsung Electronics              | 5         | 1.78%   |
| Nvidia                           | 5         | 1.78%   |
| Broadcom Limited                 | 5         | 1.78%   |
| JMicron Technology               | 3         | 1.07%   |
| Xiaomi                           | 2         | 0.71%   |
| Attansic Technology              | 2         | 0.71%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.36%   |
| VIA Technologies                 | 1         | 0.36%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.36%   |
| MediaTek                         | 1         | 0.36%   |
| Lenovo                           | 1         | 0.36%   |
| Huawei Technologies              | 1         | 0.36%   |
| Hewlett-Packard                  | 1         | 0.36%   |
| Gemtek                           | 1         | 0.36%   |
| DisplayLink                      | 1         | 0.36%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 82        | 29.18%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 51        | 18.15%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 9         | 3.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7         | 2.49%   |
| Intel 82567LM Gigabit Network Connection                                       | 6         | 2.14%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 5         | 1.78%   |
| Intel 82577LM Gigabit Network Connection                                       | 5         | 1.78%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 4         | 1.42%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                        | 4         | 1.42%   |
| Intel Ethernet Connection I217-LM                                              | 4         | 1.42%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 4         | 1.42%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 3         | 1.07%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 3         | 1.07%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 3         | 1.07%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 3         | 1.07%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 3         | 1.07%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 3         | 1.07%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 3         | 1.07%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 3         | 1.07%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 2         | 0.71%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                      | 2         | 0.71%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 0.71%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2         | 0.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 0.71%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 2         | 0.71%   |
| Nvidia MCP79 Ethernet                                                          | 2         | 0.71%   |
| Nvidia MCP67 Ethernet                                                          | 2         | 0.71%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.71%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 2         | 0.71%   |
| Intel PRO/100 VE Network Connection                                            | 2         | 0.71%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.71%   |
| Intel 82566MM Gigabit Network Connection                                       | 2         | 0.71%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile           | 2         | 0.71%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 2         | 0.71%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 2         | 0.71%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 2         | 0.71%   |
| ZTE WCDMA MSM Z6201V                                                           | 1         | 0.36%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 1         | 0.36%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.36%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.36%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.36%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 1         | 0.36%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.36%   |
| OnePlus (Shenzhen) SM8150-MTP _SN:63F1CF71                                     | 1         | 0.36%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.36%   |
| MediaTek Le                                                                    | 1         | 0.36%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 1         | 0.36%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.36%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                          | 1         | 0.36%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.36%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 1         | 0.36%   |
| Lenovo ThinkPad Lan                                                            | 1         | 0.36%   |
| Intel WiMAX Connection 2400m                                                   | 1         | 0.36%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.36%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.36%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.36%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.36%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.36%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.36%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 291       | 50.52%  |
| Ethernet | 267       | 46.35%  |
| Modem    | 15        | 2.6%    |
| Unknown  | 3         | 0.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 227       | 75.92%  |
| Ethernet | 72        | 24.08%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 249       | 84.12%  |
| 1     | 40        | 13.51%  |
| 0     | 4         | 1.35%   |
| 3     | 2         | 0.68%   |
| 4     | 1         | 0.34%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 247       | 82.89%  |
| Yes  | 51        | 17.11%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 47        | 27.33%  |
| Realtek Semiconductor           | 28        | 16.28%  |
| Qualcomm Atheros Communications | 20        | 11.63%  |
| Broadcom                        | 15        | 8.72%   |
| Foxconn / Hon Hai               | 12        | 6.98%   |
| Hewlett-Packard                 | 10        | 5.81%   |
| Lite-On Technology              | 7         | 4.07%   |
| Dell                            | 7         | 4.07%   |
| IMC Networks                    | 6         | 3.49%   |
| Apple                           | 4         | 2.33%   |
| Cambridge Silicon Radio         | 3         | 1.74%   |
| ASUSTek Computer                | 3         | 1.74%   |
| Toshiba                         | 2         | 1.16%   |
| Taiyo Yuden                     | 1         | 0.58%   |
| Realtek                         | 1         | 0.58%   |
| Ralink Technology               | 1         | 0.58%   |
| Ralink                          | 1         | 0.58%   |
| Qcom                            | 1         | 0.58%   |
| Foxconn International           | 1         | 0.58%   |
| Askey Computer                  | 1         | 0.58%   |
| Alps Electric                   | 1         | 0.58%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 28        | 16.28%  |
| Realtek Bluetooth Radio                                                             | 15        | 8.72%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 11        | 6.4%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 10        | 5.81%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 7         | 4.07%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 5         | 2.91%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 5         | 2.91%   |
| Intel Bluetooth Device                                                              | 4         | 2.33%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 2.33%   |
| Dell DW375 Bluetooth Module                                                         | 4         | 2.33%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 1.74%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 3         | 1.74%   |
| Intel AX200 Bluetooth                                                               | 3         | 1.74%   |
| IMC Networks Bluetooth Device                                                       | 3         | 1.74%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 3         | 1.74%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 1.74%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 3         | 1.74%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 3         | 1.74%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 1.16%   |
| Lite-On Atheros Bluetooth                                                           | 2         | 1.16%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.16%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.16%   |
| Foxconn / Hon Hai Acer Module                                                       | 2         | 1.16%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 2         | 1.16%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 1.16%   |
| Broadcom Bluetooth                                                                  | 2         | 1.16%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 2         | 1.16%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 2         | 1.16%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 1.16%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 1.16%   |
| Apple Bluetooth Host Controller                                                     | 2         | 1.16%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.58%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.58%   |
| Taiyo Yuden Bluetooth Device(BC04-External)                                         | 1         | 0.58%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.58%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.58%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.58%   |
| Ralink CSR BS8510                                                                   | 1         | 0.58%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.58%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.58%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.58%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.58%   |
| Qcom Broadcom Bluetooth USB                                                         | 1         | 0.58%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 0.58%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.58%   |
| IMC Networks Broadcom Bluetooth 2.1                                                 | 1         | 0.58%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.58%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.58%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 1         | 0.58%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.58%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.58%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 1         | 0.58%   |
| Dell Wireless 355 Bluetooth                                                         | 1         | 0.58%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 0.58%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 0.58%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 1         | 0.58%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 1         | 0.58%   |
| ASUS Broadcom Bluetooth 2.1                                                         | 1         | 0.58%   |
| Askey Bluetooth Device                                                              | 1         | 0.58%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 0.58%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 231       | 66.96%  |
| AMD                              | 65        | 18.84%  |
| Nvidia                           | 31        | 8.99%   |
| Silicon Integrated Systems [SiS] | 6         | 1.74%   |
| Texas Instruments                | 2         | 0.58%   |
| C-Media Electronics              | 2         | 0.58%   |
| Yamaha                           | 1         | 0.29%   |
| VIA Technologies                 | 1         | 0.29%   |
| Tenx Technology                  | 1         | 0.29%   |
| Realtek Semiconductor            | 1         | 0.29%   |
| GN Netcom                        | 1         | 0.29%   |
| Generalplus Technology           | 1         | 0.29%   |
| Dell                             | 1         | 0.29%   |
| Audioengine                      | 1         | 0.29%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 36        | 8.72%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 26        | 6.3%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 23        | 5.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 22        | 5.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 18        | 4.36%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 17        | 4.12%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 16        | 3.87%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 2.91%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 2.91%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 12        | 2.91%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 10        | 2.42%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 10        | 2.42%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 10        | 2.42%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9         | 2.18%   |
| AMD High Definition Audio Controller                                                              | 9         | 2.18%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 8         | 1.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8         | 1.94%   |
| AMD FCH Azalia Controller                                                                         | 8         | 1.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 1.69%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 1.69%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 1.45%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 1.45%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 1.45%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 1.21%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 1.21%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 4         | 0.97%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 4         | 0.97%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 0.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 0.97%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 4         | 0.97%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 4         | 0.97%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 4         | 0.97%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.73%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 0.73%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 0.73%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 0.73%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 3         | 0.73%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 2         | 0.48%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.48%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.48%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.48%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.48%   |
| Nvidia Audio device                                                                               | 2         | 0.48%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.48%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.48%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 0.48%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 2         | 0.48%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 2         | 0.48%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                                              | 2         | 0.48%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 0.48%   |
| AMD IXP SB4x0 High Definition Audio Controller                                                    | 2         | 0.48%   |
| AMD IXP SB400 AC'97 Audio Controller                                                              | 2         | 0.48%   |
| Yamaha Steinberg UR22mkII                                                                         | 1         | 0.24%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.24%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 1         | 0.24%   |
| Texas Instruments PCM2702 16-bit stereo audio DAC                                                 | 1         | 0.24%   |
| Tenx Technology USB AUDIO                                                                         | 1         | 0.24%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.24%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.24%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1         | 0.24%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| SK hynix                     | 18        | 26.09%  |
| Samsung Electronics          | 15        | 21.74%  |
| Unknown                      | 9         | 13.04%  |
| Kingston                     | 8         | 11.59%  |
| Nanya Technology             | 3         | 4.35%   |
| A-DATA Technology            | 3         | 4.35%   |
| Smart                        | 2         | 2.9%    |
| Ramaxel Technology           | 2         | 2.9%    |
| Micron Technology            | 2         | 2.9%    |
| Unknown (ABCD)               | 1         | 1.45%   |
| Transcend                    | 1         | 1.45%   |
| Patriot Memory (PDP Systems) | 1         | 1.45%   |
| Patriot                      | 1         | 1.45%   |
| G.Skill                      | 1         | 1.45%   |
| Crucial                      | 1         | 1.45%   |
| Corsair                      | 1         | 1.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                    | 2         | 2.67%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                    | 2         | 2.67%   |
| Unknown RAM Module SODIMM DDR                                            | 1         | 1.33%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                              | 1         | 1.33%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                           | 1         | 1.33%   |
| Unknown RAM Module 512MB SODIMM DDR                                      | 1         | 1.33%   |
| Unknown RAM Module 4096MB SODIMM DDR3                                    | 1         | 1.33%   |
| Unknown RAM Module 2GB SODIMM DDR3                                       | 1         | 1.33%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                      | 1         | 1.33%   |
| Unknown RAM Module 2048MB SODIMM DDR3                                    | 1         | 1.33%   |
| Unknown RAM Module 1GB SODIMM DDR                                        | 1         | 1.33%   |
| Unknown RAM Module 1024MB SODIMM DDR3                                    | 1         | 1.33%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                            | 1         | 1.33%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s      | 1         | 1.33%   |
| Transcend RAM JM800QSU-2G 2GB SODIMM DDR2 975MT/s                        | 1         | 1.33%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.33%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.33%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s                          | 1         | 1.33%   |
| SK hynix RAM Module 512MB SODIMM DDR 533MT/s                             | 1         | 1.33%   |
| SK hynix RAM Module 32GB SODIMM DDR4 3200MT/s                            | 1         | 1.33%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                             | 1         | 1.33%   |
| SK hynix RAM HYMP125S64CP8-Y5 2048MB SODIMM DDR 667MT/s                  | 1         | 1.33%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 975MT/s                 | 1         | 1.33%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                   | 1         | 1.33%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                   | 1         | 1.33%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s                | 1         | 1.33%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s                | 1         | 1.33%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s                   | 1         | 1.33%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s                   | 1         | 1.33%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s                   | 1         | 1.33%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s                   | 1         | 1.33%   |
| SK hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s                | 1         | 1.33%   |
| SK hynix RAM HMP125S6EFR8C-S6 2048MB SODIMM DDR2 800MT/s                 | 1         | 1.33%   |
| SK hynix RAM HMP112S6EFR6C-S6 1024MB SODIMM DDR 800MT/s                  | 1         | 1.33%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s                | 1         | 1.33%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s                   | 1         | 1.33%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s                   | 1         | 1.33%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                              | 1         | 1.33%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s                    | 1         | 1.33%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s                    | 1         | 1.33%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s              | 1         | 1.33%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s                    | 1         | 1.33%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                    | 1         | 1.33%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                    | 1         | 1.33%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s                    | 1         | 1.33%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                    | 1         | 1.33%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s                 | 1         | 1.33%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s                 | 1         | 1.33%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s                   | 1         | 1.33%   |
| Ramaxel RAM RMSA3260MF68H9F-2666 4GB SODIMM DDR4 2400MT/s                | 1         | 1.33%   |
| Ramaxel RAM RMN1150EC48D7W-800 1024MB SODIMM DDR2 800MT/s                | 1         | 1.33%   |
| Patriot RAM PSD44G240081S 4GB SODIMM DDR4 2400MT/s                       | 1         | 1.33%   |
| Patriot Memory (PDP Systems) RAM PSD432G32002S 32GB SODIMM DDR4 3200MT/s | 1         | 1.33%   |
| Nanya RAM NT2GT64U8HD0BN-AD 2048MB SODIMM DDR2 2048MT/s                  | 1         | 1.33%   |
| Nanya RAM NT2GC64B88G0NS-CG 2GB SODIMM DDR3 1600MT/s                     | 1         | 1.33%   |
| Nanya RAM Module 1024MB SODIMM DDR 533MT/s                               | 1         | 1.33%   |
| Micron RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s                   | 1         | 1.33%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                     | 1         | 1.33%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s                         | 1         | 1.33%   |
| Kingston RAM KMKYF9-MIB 8192MB SODIMM DDR4 2400MT/s                      | 1         | 1.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 25        | 39.06%  |
| DDR3   | 24        | 37.5%   |
| DDR2   | 6         | 9.38%   |
| SDRAM  | 4         | 6.25%   |
| DDR    | 3         | 4.69%   |
| LPDDR4 | 2         | 3.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 61        | 96.83%  |
| Row Of Chips | 2         | 3.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 8192    | 26        | 37.14%  |
| 4096    | 17        | 24.29%  |
| 2048    | 15        | 21.43%  |
| 1024    | 6         | 8.57%   |
| 32768   | 2         | 2.86%   |
| 512     | 2         | 2.86%   |
| 16384   | 1         | 1.43%   |
| Unknown | 1         | 1.43%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 16        | 23.88%  |
| 2667    | 11        | 16.42%  |
| 3200    | 10        | 14.93%  |
| 2400    | 6         | 8.96%   |
| Unknown | 5         | 7.46%   |
| 1333    | 4         | 5.97%   |
| 800     | 3         | 4.48%   |
| 2048    | 2         | 2.99%   |
| 975     | 2         | 2.99%   |
| 533     | 2         | 2.99%   |
| 4267    | 1         | 1.49%   |
| 4199    | 1         | 1.49%   |
| 3266    | 1         | 1.49%   |
| 2133    | 1         | 1.49%   |
| 1200    | 1         | 1.49%   |
| 667     | 1         | 1.49%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 1         | 50%     |
| Hewlett-Packard | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Notebooks | Percent |
|----------------------------|-----------|---------|
| Seiko Epson XP-3100 Series | 1         | 50%     |
| HP DeskJet 2700 series     | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 51        | 22.47%  |
| IMC Networks                           | 22        | 9.69%   |
| Suyin                                  | 21        | 9.25%   |
| Sunplus Innovation Technology          | 19        | 8.37%   |
| Microdia                               | 19        | 8.37%   |
| Quanta                                 | 15        | 6.61%   |
| Acer                                   | 15        | 6.61%   |
| Realtek Semiconductor                  | 14        | 6.17%   |
| Silicon Motion                         | 7         | 3.08%   |
| Ricoh                                  | 6         | 2.64%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 2.64%   |
| Apple                                  | 6         | 2.64%   |
| Syntek                                 | 4         | 1.76%   |
| ALi                                    | 3         | 1.32%   |
| Z-Star Microelectronics                | 2         | 0.88%   |
| Sunplus Technology                     | 2         | 0.88%   |
| Luxvisions Innotech Limited            | 2         | 0.88%   |
| Lite-On Technology                     | 2         | 0.88%   |
| Importek                               | 2         | 0.88%   |
| Alcor Micro                            | 2         | 0.88%   |
| Samsung Electronics                    | 1         | 0.44%   |
| OmniVision Technologies                | 1         | 0.44%   |
| LG Electronics                         | 1         | 0.44%   |
| Lenovo                                 | 1         | 0.44%   |
| Intel                                  | 1         | 0.44%   |
| icSpring                               | 1         | 0.44%   |
| Generalplus Technology                 | 1         | 0.44%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                    | 9         | 3.95%   |
| Chicony Integrated Camera                        | 7         | 3.07%   |
| Quanta HP Webcam                                 | 6         | 2.63%   |
| Chicony HD Webcam                                | 6         | 2.63%   |
| Suyin HP TrueVision HD                           | 5         | 2.19%   |
| Quanta HP TrueVision HD Camera                   | 4         | 1.75%   |
| IMC Networks Integrated Camera                   | 4         | 1.75%   |
| Chicony HP Truevision HD camera                  | 4         | 1.75%   |
| Apple iPhone 5/5C/5S/6/SE                        | 4         | 1.75%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 3         | 1.32%   |
| Suyin 1.3M HD WebCam                             | 3         | 1.32%   |
| Sunplus Laptop_Integrated_Webcam_HD              | 3         | 1.32%   |
| Sunplus HP TrueVision HD Camera                  | 3         | 1.32%   |
| Realtek USB2.0 VGA UVC WebCam                    | 3         | 1.32%   |
| Realtek Integrated_Webcam_HD                     | 3         | 1.32%   |
| Microdia Integrated Webcam HD                    | 3         | 1.32%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 3         | 1.32%   |
| IMC Networks USB2.0 HD UVC WebCam                | 3         | 1.32%   |
| Chicony USB2.0 HD UVC WebCam                     | 3         | 1.32%   |
| Chicony USB 2.0 Camera                           | 3         | 1.32%   |
| Chicony 2.0M UVC Webcam / CNF7129                | 3         | 1.32%   |
| Acer Lenovo EasyCamera                           | 3         | 1.32%   |
| Syntek Sonix USB 2.0 Camera                      | 2         | 0.88%   |
| Suyin HP Webcam                                  | 2         | 0.88%   |
| Suyin HD WebCam                                  | 2         | 0.88%   |
| Suyin Acer HD Crystal Eye webcam                 | 2         | 0.88%   |
| Suyin Acer CrystalEye Webcam                     | 2         | 0.88%   |
| Sunplus Laptop Integrated WebCam HD              | 2         | 0.88%   |
| Sunplus HD WebCam                                | 2         | 0.88%   |
| Silicon Motion WebCam SCB-0385N                  | 2         | 0.88%   |
| Silicon Motion WebCam SC-0311139N                | 2         | 0.88%   |
| Silicon Motion HP Webcam-101                     | 2         | 0.88%   |
| Ricoh Sony Visual Communication Camera           | 2         | 0.88%   |
| Realtek HP Truevision HD integrated webcam       | 2         | 0.88%   |
| Quanta VGA WebCam                                | 2         | 0.88%   |
| Microdia Sonix USB 2.0 Camera                    | 2         | 0.88%   |
| IMC Networks USB 2.0 UVC VGA WebCam              | 2         | 0.88%   |
| IMC Networks Integrated Webcam                   | 2         | 0.88%   |
| IMC Networks EasyCamera                          | 2         | 0.88%   |
| Chicony TOSHIBA Web Camera - HD                  | 2         | 0.88%   |
| Chicony HD WebCam (Acer)                         | 2         | 0.88%   |
| Chicony EasyCamera                               | 2         | 0.88%   |
| Chicony 1.3M Webcam                              | 2         | 0.88%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 2         | 0.88%   |
| Apple Built-in iSight                            | 2         | 0.88%   |
| ALi Gateway Webcam                               | 2         | 0.88%   |
| Alcor Micro USB 2.0 Camera                       | 2         | 0.88%   |
| Acer USB HD Webcam                               | 2         | 0.88%   |
| Acer Integrated Camera                           | 2         | 0.88%   |
| Acer HD Webcam                                   | 2         | 0.88%   |
| Z-Star Namuga 1.3M Webcam                        | 1         | 0.44%   |
| Z-Star Lenovo EasyCamera                         | 1         | 0.44%   |
| Syntek Integrated Webcam                         | 1         | 0.44%   |
| Syntek HP Webcam                                 | 1         | 0.44%   |
| Suyin WebCam                                     | 1         | 0.44%   |
| Suyin HP TrueVision HD Integrated Webcam         | 1         | 0.44%   |
| Sunplus 1.3M WebCam                              | 1         | 0.44%   |
| Sunplus 1.3M HD WebCam                           | 1         | 0.44%   |
| Sunplus Lenovo EasyCamera                        | 1         | 0.44%   |
| Sunplus Laptop_Integrated_Webcam_FHD             | 1         | 0.44%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 14        | 42.42%  |
| AuthenTec                  | 8         | 24.24%  |
| STMicroelectronics         | 3         | 9.09%   |
| Synaptics                  | 2         | 6.06%   |
| LighTuning Technology      | 2         | 6.06%   |
| Elan Microelectronics      | 2         | 6.06%   |
| Upek                       | 1         | 3.03%   |
| Shenzhen Goodix Technology | 1         | 3.03%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 3         | 9.09%   |
| Validity Sensors VFS301 Fingerprint Reader             | 3         | 9.09%   |
| STMicroelectronics Fingerprint Reader                  | 3         | 9.09%   |
| Validity Sensors VFS491                                | 2         | 6.06%   |
| Validity Sensors VFS451 Fingerprint Reader             | 2         | 6.06%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 6.06%   |
| Elan ELAN:Fingerprint                                  | 2         | 6.06%   |
| AuthenTec Fingerprint Sensor                           | 2         | 6.06%   |
| AuthenTec AES2810                                      | 2         | 6.06%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 6.06%   |
| AuthenTec AES1600                                      | 2         | 6.06%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 3.03%   |
| Validity Sensors VFS101 Fingerprint Reader             | 1         | 3.03%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 3.03%   |
| Validity Sensors Fingerprint scanner                   | 1         | 3.03%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 3.03%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 3.03%   |
| Shenzhen Goodix  Fingerprint Device                    | 1         | 3.03%   |
| Unknown                                                | 1         | 3.03%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 13        | 72.22%  |
| O2 Micro              | 3         | 16.67%  |
| Gemalto (was Gemplus) | 1         | 5.56%   |
| Alcor Micro           | 1         | 5.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 38.89%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 16.67%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 11.11%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 5.56%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 5.56%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 5.56%   |
| Broadcom 5880                                                                | 1         | 5.56%   |
| Broadcom 58200                                                               | 1         | 5.56%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 5.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 194       | 64.88%  |
| 1     | 77        | 25.75%  |
| 2     | 20        | 6.69%   |
| 3     | 7         | 2.34%   |
| 6     | 1         | 0.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 37        | 27.01%  |
| Fingerprint reader       | 32        | 23.36%  |
| Net/wireless             | 22        | 16.06%  |
| Chipcard                 | 17        | 12.41%  |
| Multimedia controller    | 12        | 8.76%   |
| Storage                  | 6         | 4.38%   |
| Communication controller | 4         | 2.92%   |
| Flash memory             | 2         | 1.46%   |
| Sound                    | 1         | 0.73%   |
| Network                  | 1         | 0.73%   |
| Dvb card                 | 1         | 0.73%   |
| Camera                   | 1         | 0.73%   |
| Bluetooth                | 1         | 0.73%   |


Linux in Serbia - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Serbia.

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

Total: 555

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Apple         | MacBookPro6,2               | [3e154e4ccc](https://linux-hardware.org/?probe=3e154e4ccc) | Apr 28, 2023 |
| Apple         | MacBookPro6,2               | [2628c3040f](https://linux-hardware.org/?probe=2628c3040f) | Apr 28, 2023 |
| HP            | OMEN by Laptop 15-dh1xxx    | [3c104a89ef](https://linux-hardware.org/?probe=3c104a89ef) | Apr 26, 2023 |
| Dell          | Vostro 15 3510              | [81cae0ba77](https://linux-hardware.org/?probe=81cae0ba77) | Apr 26, 2023 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | [167000be9b](https://linux-hardware.org/?probe=167000be9b) | Apr 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [258a5bb354](https://linux-hardware.org/?probe=258a5bb354) | Apr 19, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [889301578c](https://linux-hardware.org/?probe=889301578c) | Apr 18, 2023 |
| Acer          | Aspire 5336                 | [ddf5053ffa](https://linux-hardware.org/?probe=ddf5053ffa) | Apr 18, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [55a12acf3a](https://linux-hardware.org/?probe=55a12acf3a) | Apr 12, 2023 |
| Lenovo        | V570 1066EDG                | [8a8a256b79](https://linux-hardware.org/?probe=8a8a256b79) | Apr 02, 2023 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | [51c7ed9156](https://linux-hardware.org/?probe=51c7ed9156) | Apr 01, 2023 |
| ASUSTek       | E200HA                      | [5dfef9c764](https://linux-hardware.org/?probe=5dfef9c764) | Mar 26, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [178936b7f4](https://linux-hardware.org/?probe=178936b7f4) | Mar 24, 2023 |
| HP            | EliteBook 2530p             | [06ad8714ea](https://linux-hardware.org/?probe=06ad8714ea) | Mar 22, 2023 |
| ASUSTek       | T300CHI                     | [371961ad53](https://linux-hardware.org/?probe=371961ad53) | Mar 19, 2023 |
| Lenovo        | G550 20023                  | [6296457407](https://linux-hardware.org/?probe=6296457407) | Mar 18, 2023 |
| Lenovo        | G550 20023                  | [f5bd764775](https://linux-hardware.org/?probe=f5bd764775) | Mar 18, 2023 |
| Lenovo        | G550 20023                  | [c356d98a54](https://linux-hardware.org/?probe=c356d98a54) | Mar 17, 2023 |
| ASUSTek       | K93SV                       | [aa66f39ad6](https://linux-hardware.org/?probe=aa66f39ad6) | Mar 13, 2023 |
| ASUSTek       | E200HA                      | [46a16afb4b](https://linux-hardware.org/?probe=46a16afb4b) | Mar 03, 2023 |
| Lenovo        | V570 1066EDG                | [deb326cc4b](https://linux-hardware.org/?probe=deb326cc4b) | Feb 26, 2023 |
| Lenovo        | V570 1066EDG                | [cc220b6122](https://linux-hardware.org/?probe=cc220b6122) | Feb 26, 2023 |
| Lenovo        | ThinkPad T495s 20QJS0GG0... | [6186149a54](https://linux-hardware.org/?probe=6186149a54) | Feb 24, 2023 |
| HONOR         | NBR-WAX9                    | [b16ea0055d](https://linux-hardware.org/?probe=b16ea0055d) | Feb 17, 2023 |
| HP            | OMEN by Laptop 17-ck1xxx    | [18f60be847](https://linux-hardware.org/?probe=18f60be847) | Feb 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2f721ad33a](https://linux-hardware.org/?probe=2f721ad33a) | Feb 10, 2023 |
| ASUSTek       | ROG Strix G733QR_G733QR     | [da12318597](https://linux-hardware.org/?probe=da12318597) | Feb 10, 2023 |
| Dell          | Inspiron 3558               | [310425ba43](https://linux-hardware.org/?probe=310425ba43) | Feb 08, 2023 |
| Lenovo        | V570 1066EDG                | [f963048c4c](https://linux-hardware.org/?probe=f963048c4c) | Feb 08, 2023 |
| Lenovo        | V570 1066EDG                | [e3ffc73e43](https://linux-hardware.org/?probe=e3ffc73e43) | Feb 06, 2023 |
| TWC           | Unknown                     | [4ea2803396](https://linux-hardware.org/?probe=4ea2803396) | Feb 06, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [fcd4f7a01a](https://linux-hardware.org/?probe=fcd4f7a01a) | Feb 06, 2023 |
| HP            | 250 G5 Notebook PC          | [d389ca29d1](https://linux-hardware.org/?probe=d389ca29d1) | Feb 06, 2023 |
| Lenovo        | V570 1066EDG                | [00714979fe](https://linux-hardware.org/?probe=00714979fe) | Feb 06, 2023 |
| Dell          | XPS 15 9550                 | [200495d065](https://linux-hardware.org/?probe=200495d065) | Feb 04, 2023 |
| Dell          | Vostro 15 3515              | [357d14774f](https://linux-hardware.org/?probe=357d14774f) | Jan 30, 2023 |
| ASUSTek       | K55A                        | [e3088b45e1](https://linux-hardware.org/?probe=e3088b45e1) | Jan 29, 2023 |
| ASUSTek       | K93SV                       | [3b4dd13d9f](https://linux-hardware.org/?probe=3b4dd13d9f) | Jan 29, 2023 |
| Toshiba       | Satellite C870-17H          | [8fe4718795](https://linux-hardware.org/?probe=8fe4718795) | Jan 28, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [d825caa85e](https://linux-hardware.org/?probe=d825caa85e) | Jan 27, 2023 |
| Dell          | Precision 3550              | [4c42615cef](https://linux-hardware.org/?probe=4c42615cef) | Jan 27, 2023 |
| HP            | Laptop 15s-eq3xxx           | [b871955b27](https://linux-hardware.org/?probe=b871955b27) | Jan 23, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [2194886c52](https://linux-hardware.org/?probe=2194886c52) | Jan 23, 2023 |
| Acer          | Aspire 5755G                | [1bf0fe4342](https://linux-hardware.org/?probe=1bf0fe4342) | Jan 22, 2023 |
| Apple         | MacBookPro5,3               | [2375f407c7](https://linux-hardware.org/?probe=2375f407c7) | Jan 22, 2023 |
| ASUSTek       | X453MA                      | [94b155d9c2](https://linux-hardware.org/?probe=94b155d9c2) | Jan 21, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [db998abdae](https://linux-hardware.org/?probe=db998abdae) | Jan 19, 2023 |
| ASUSTek       | X201EP                      | [def6593908](https://linux-hardware.org/?probe=def6593908) | Jan 16, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [a09ace045e](https://linux-hardware.org/?probe=a09ace045e) | Jan 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [295ef21c8b](https://linux-hardware.org/?probe=295ef21c8b) | Jan 15, 2023 |
| Lenovo        | IdeaPad Y570 20091          | [3538dd1b8a](https://linux-hardware.org/?probe=3538dd1b8a) | Jan 11, 2023 |
| Lenovo        | ThinkPad T430 2349JN0       | [fceb17b32c](https://linux-hardware.org/?probe=fceb17b32c) | Jan 10, 2023 |
| Lenovo        | ThinkPad T430 2349JN0       | [04a54f4c2f](https://linux-hardware.org/?probe=04a54f4c2f) | Jan 09, 2023 |
| Dell          | Inspiron 3537               | [234580243d](https://linux-hardware.org/?probe=234580243d) | Jan 08, 2023 |
| Lenovo        | ThinkPad W500 4061WFA       | [4850dba7c8](https://linux-hardware.org/?probe=4850dba7c8) | Jan 08, 2023 |
| ASUSTek       | E200HA                      | [f84fb1bab3](https://linux-hardware.org/?probe=f84fb1bab3) | Jan 08, 2023 |
| eMachines     | E725                        | [0655d63f70](https://linux-hardware.org/?probe=0655d63f70) | Jan 06, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | [1afcc520de](https://linux-hardware.org/?probe=1afcc520de) | Jan 05, 2023 |
| ASUSTek       | K52JT                       | [77abcf7aee](https://linux-hardware.org/?probe=77abcf7aee) | Jan 05, 2023 |
| HP            | 255 G8 Notebook PC          | [05209e0503](https://linux-hardware.org/?probe=05209e0503) | Dec 29, 2022 |
| HP            | Victus by Laptop 16-e1xx... | [25183d70e2](https://linux-hardware.org/?probe=25183d70e2) | Dec 29, 2022 |
| Acer          | Aspire 5741                 | [1c41b5afb0](https://linux-hardware.org/?probe=1c41b5afb0) | Dec 27, 2022 |
| HUAWEI        | CREM-WXX9                   | [a48a2f6362](https://linux-hardware.org/?probe=a48a2f6362) | Dec 24, 2022 |
| Lenovo        | Legion 7 16IAX7 82TD        | [46e5d4fe56](https://linux-hardware.org/?probe=46e5d4fe56) | Dec 20, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [e8b0c03cb9](https://linux-hardware.org/?probe=e8b0c03cb9) | Dec 15, 2022 |
| Acer          | Nitro AN517-51              | [6b5fd6a48c](https://linux-hardware.org/?probe=6b5fd6a48c) | Dec 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [937053920b](https://linux-hardware.org/?probe=937053920b) | Dec 04, 2022 |
| Dell          | Inspiron N5050              | [c6bca6efa8](https://linux-hardware.org/?probe=c6bca6efa8) | Dec 03, 2022 |
| Dell          | Inspiron N5050              | [e4c533a89b](https://linux-hardware.org/?probe=e4c533a89b) | Nov 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon 34601... | [ed678da106](https://linux-hardware.org/?probe=ed678da106) | Nov 26, 2022 |
| HP            | ProBook 445 14 inch G9 N... | [a20535bd66](https://linux-hardware.org/?probe=a20535bd66) | Nov 24, 2022 |
| HP            | Pavilion dv7                | [839266e415](https://linux-hardware.org/?probe=839266e415) | Nov 19, 2022 |
| HP            | Notebook                    | [2721a90e68](https://linux-hardware.org/?probe=2721a90e68) | Nov 19, 2022 |
| Dell          | Inspiron 3584               | [c3fde80859](https://linux-hardware.org/?probe=c3fde80859) | Nov 14, 2022 |
| Dell          | Inspiron 3584               | [c8e8add499](https://linux-hardware.org/?probe=c8e8add499) | Nov 14, 2022 |
| ASUSTek       | K93SV                       | [8511ee86ad](https://linux-hardware.org/?probe=8511ee86ad) | Nov 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [db62973b36](https://linux-hardware.org/?probe=db62973b36) | Nov 06, 2022 |
| Acer          | Aspire V3-571G              | [3d642bde4b](https://linux-hardware.org/?probe=3d642bde4b) | Nov 05, 2022 |
| Timi          | RedmiBook 14 II             | [374be77f36](https://linux-hardware.org/?probe=374be77f36) | Nov 05, 2022 |
| ASUSTek       | X751LB                      | [b9f1ea7699](https://linux-hardware.org/?probe=b9f1ea7699) | Nov 04, 2022 |
| ASUSTek       | X751LB                      | [e7334f33eb](https://linux-hardware.org/?probe=e7334f33eb) | Nov 04, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [7d6d6c3c3a](https://linux-hardware.org/?probe=7d6d6c3c3a) | Nov 04, 2022 |
| Acer          | Aspire V3-571G              | [990a38ea87](https://linux-hardware.org/?probe=990a38ea87) | Nov 01, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [491477817a](https://linux-hardware.org/?probe=491477817a) | Oct 25, 2022 |
| ASUSTek       | N750JK                      | [341d4b53b1](https://linux-hardware.org/?probe=341d4b53b1) | Oct 20, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [d928c22430](https://linux-hardware.org/?probe=d928c22430) | Oct 14, 2022 |
| MSI           | GP66 Leopard 10UG           | [c2082a042d](https://linux-hardware.org/?probe=c2082a042d) | Oct 06, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [b07d3b7b7f](https://linux-hardware.org/?probe=b07d3b7b7f) | Oct 05, 2022 |
| Lenovo        | B50-45 20388                | [c5f81be3fd](https://linux-hardware.org/?probe=c5f81be3fd) | Oct 02, 2022 |
| Lenovo        | V570 1066EDG                | [8e2439c590](https://linux-hardware.org/?probe=8e2439c590) | Oct 01, 2022 |
| Dell          | Precision M4800             | [d4142adadc](https://linux-hardware.org/?probe=d4142adadc) | Sep 29, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [d06b40ddf1](https://linux-hardware.org/?probe=d06b40ddf1) | Sep 29, 2022 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [9fbedd972e](https://linux-hardware.org/?probe=9fbedd972e) | Sep 24, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X1S... | [6e943a4d35](https://linux-hardware.org/?probe=6e943a4d35) | Sep 23, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [641ad27b06](https://linux-hardware.org/?probe=641ad27b06) | Sep 22, 2022 |
| HP            | ProBook 6560b               | [743f401352](https://linux-hardware.org/?probe=743f401352) | Sep 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [d0d43b3cc5](https://linux-hardware.org/?probe=d0d43b3cc5) | Sep 14, 2022 |
| Dell          | Inspiron N5050              | [131f5046db](https://linux-hardware.org/?probe=131f5046db) | Sep 11, 2022 |
| Apple         | MacBookPro8,2               | [a30032ef92](https://linux-hardware.org/?probe=a30032ef92) | Sep 11, 2022 |
| Apple         | MacBookPro8,2               | [0645f03606](https://linux-hardware.org/?probe=0645f03606) | Sep 11, 2022 |
| LG Electro... | 17Z990-R.AAS8U1             | [2df5aeabed](https://linux-hardware.org/?probe=2df5aeabed) | Sep 08, 2022 |
| Dell          | Inspiron 3593               | [fd6ab0c9e5](https://linux-hardware.org/?probe=fd6ab0c9e5) | Sep 07, 2022 |
| ASUSTek       | Zenbook UX5400EA_UX5400E... | [6ce8accfb1](https://linux-hardware.org/?probe=6ce8accfb1) | Sep 04, 2022 |
| Apple         | MacBookPro5,1               | [beec88b95c](https://linux-hardware.org/?probe=beec88b95c) | Sep 04, 2022 |
| Apple         | MacBookPro5,1               | [4c90105342](https://linux-hardware.org/?probe=4c90105342) | Sep 01, 2022 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [e3c7cd81e8](https://linux-hardware.org/?probe=e3c7cd81e8) | Aug 27, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [f945f778b2](https://linux-hardware.org/?probe=f945f778b2) | Aug 26, 2022 |
| Apple         | MacBookPro5,1               | [6efab17b42](https://linux-hardware.org/?probe=6efab17b42) | Aug 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | [255a1cdf9a](https://linux-hardware.org/?probe=255a1cdf9a) | Aug 24, 2022 |
| ASUSTek       | X542BA                      | [7e86736ebc](https://linux-hardware.org/?probe=7e86736ebc) | Aug 21, 2022 |
| ASUSTek       | K54C                        | [e10b52270f](https://linux-hardware.org/?probe=e10b52270f) | Aug 17, 2022 |
| Dell          | Inspiron 3521               | [ebf974be3e](https://linux-hardware.org/?probe=ebf974be3e) | Aug 13, 2022 |
| Dell          | Inspiron 3521               | [6dd71dbcf3](https://linux-hardware.org/?probe=6dd71dbcf3) | Aug 12, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [fa9cdcd977](https://linux-hardware.org/?probe=fa9cdcd977) | Aug 12, 2022 |
| Apple         | MacBookPro5,1               | [ab09f2f44b](https://linux-hardware.org/?probe=ab09f2f44b) | Aug 11, 2022 |
| Sony          | VPCZ12M9E                   | [75f1c2f156](https://linux-hardware.org/?probe=75f1c2f156) | Aug 02, 2022 |
| Sony          | VPCEE23FX                   | [b4108910d3](https://linux-hardware.org/?probe=b4108910d3) | Jul 25, 2022 |
| Acer          | Nitro AN515-55              | [b121274e4f](https://linux-hardware.org/?probe=b121274e4f) | Jul 23, 2022 |
| Apple         | MacBookPro5,1               | [4bae560f04](https://linux-hardware.org/?probe=4bae560f04) | Jul 22, 2022 |
| Apple         | MacBookPro5,1               | [8a81341ecd](https://linux-hardware.org/?probe=8a81341ecd) | Jul 18, 2022 |
| HP            | Compaq nx7300 (RU373ES#A... | [3004f1d2b9](https://linux-hardware.org/?probe=3004f1d2b9) | Jul 16, 2022 |
| Gigabyte      | AERO 17 KC                  | [b6398b12e2](https://linux-hardware.org/?probe=b6398b12e2) | Jul 13, 2022 |
| Lenovo        | ThinkPad X280 20KES8D400    | [fdc339a6b0](https://linux-hardware.org/?probe=fdc339a6b0) | Jul 09, 2022 |
| Lenovo        | ThinkPad X280 20KES8D400    | [7d2b04b0ce](https://linux-hardware.org/?probe=7d2b04b0ce) | Jul 09, 2022 |
| Dell          | Vostro 15 3515              | [c6e9a42a66](https://linux-hardware.org/?probe=c6e9a42a66) | Jul 08, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [c01cf9f7fc](https://linux-hardware.org/?probe=c01cf9f7fc) | Jul 05, 2022 |
| HP            | 250 G4                      | [3d629889b2](https://linux-hardware.org/?probe=3d629889b2) | Jul 05, 2022 |
| HP            | 250 G4                      | [e19f8a8485](https://linux-hardware.org/?probe=e19f8a8485) | Jul 05, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | [be7fd47ea1](https://linux-hardware.org/?probe=be7fd47ea1) | Jul 04, 2022 |
| Timi          | TM1613                      | [6d3f245289](https://linux-hardware.org/?probe=6d3f245289) | Jul 04, 2022 |
| Timi          | TM1613                      | [38d9919cfd](https://linux-hardware.org/?probe=38d9919cfd) | Jul 03, 2022 |
| Dell          | Inspiron 3593               | [5b091180ec](https://linux-hardware.org/?probe=5b091180ec) | Jun 28, 2022 |
| Lenovo        | ThinkPad T560 20FJS1KE00    | [f0cd91b4d2](https://linux-hardware.org/?probe=f0cd91b4d2) | Jun 21, 2022 |
| Lenovo        | Unknown                     | [cd2f32d91c](https://linux-hardware.org/?probe=cd2f32d91c) | Jun 16, 2022 |
| HP            | Pavilion Notebook           | [06c982ad14](https://linux-hardware.org/?probe=06c982ad14) | Jun 16, 2022 |
| Lenovo        | ThinkPad T60 2007FUG        | [2c1a306677](https://linux-hardware.org/?probe=2c1a306677) | Jun 16, 2022 |
| ASUSTek       | K55VD                       | [7fa5d36a45](https://linux-hardware.org/?probe=7fa5d36a45) | Jun 04, 2022 |
| HP            | ProBook 470 G1              | [ef73457d51](https://linux-hardware.org/?probe=ef73457d51) | May 31, 2022 |
| Lenovo        | ThinkPad T490 20N2000LMZ    | [9ebff03a43](https://linux-hardware.org/?probe=9ebff03a43) | May 26, 2022 |
| Lenovo        | ThinkPad T490 20N2000LMZ    | [cc80808aea](https://linux-hardware.org/?probe=cc80808aea) | May 26, 2022 |
| Lenovo        | ThinkPad T61 6463Y3W        | [065aa2538b](https://linux-hardware.org/?probe=065aa2538b) | May 18, 2022 |
| HP            | Laptop 15-db1xxx            | [f6262ce7f2](https://linux-hardware.org/?probe=f6262ce7f2) | May 12, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [e90b6752ba](https://linux-hardware.org/?probe=e90b6752ba) | May 12, 2022 |
| HP            | ProBook 450 G2              | [2c2a15aab2](https://linux-hardware.org/?probe=2c2a15aab2) | May 12, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [d18df271fd](https://linux-hardware.org/?probe=d18df271fd) | May 09, 2022 |
| Medion        | X781X/X782X                 | [fbe630f91c](https://linux-hardware.org/?probe=fbe630f91c) | May 07, 2022 |
| Lenovo        | IdeaPad Z370                | [be37f3c962](https://linux-hardware.org/?probe=be37f3c962) | May 04, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [633bddd44b](https://linux-hardware.org/?probe=633bddd44b) | Apr 30, 2022 |
| Acer          | Nitro AN517-51              | [81d7fd8d2e](https://linux-hardware.org/?probe=81d7fd8d2e) | Apr 30, 2022 |
| Dell          | Latitude 7280               | [e64ba65609](https://linux-hardware.org/?probe=e64ba65609) | Apr 22, 2022 |
| Lenovo        | Unknown                     | [6e1760aed0](https://linux-hardware.org/?probe=6e1760aed0) | Apr 17, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [b888c78ed6](https://linux-hardware.org/?probe=b888c78ed6) | Apr 12, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [45dad76f04](https://linux-hardware.org/?probe=45dad76f04) | Apr 12, 2022 |
| HP            | Notebook                    | [4ffd4d11a5](https://linux-hardware.org/?probe=4ffd4d11a5) | Apr 09, 2022 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [0dbb9e7eb0](https://linux-hardware.org/?probe=0dbb9e7eb0) | Apr 09, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [950a436db3](https://linux-hardware.org/?probe=950a436db3) | Apr 06, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [906de71a65](https://linux-hardware.org/?probe=906de71a65) | Apr 02, 2022 |
| Lenovo        | V330-15IKB 81AX             | [8a881c75f4](https://linux-hardware.org/?probe=8a881c75f4) | Mar 29, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [5eb56f360e](https://linux-hardware.org/?probe=5eb56f360e) | Mar 29, 2022 |
| Fujitsu       | LIFEBOOK AH531              | [f92c8b77dc](https://linux-hardware.org/?probe=f92c8b77dc) | Mar 25, 2022 |
| Fujitsu Si... | AMILO Li3710                | [ab84e23108](https://linux-hardware.org/?probe=ab84e23108) | Mar 24, 2022 |
| Dell          | Inspiron 3542               | [6a8c31fa33](https://linux-hardware.org/?probe=6a8c31fa33) | Mar 21, 2022 |
| Apple         | MacBookPro8,1               | [f55145f34a](https://linux-hardware.org/?probe=f55145f34a) | Mar 16, 2022 |
| Toshiba       | Satellite C870-17H          | [0169bf05d7](https://linux-hardware.org/?probe=0169bf05d7) | Mar 10, 2022 |
| Fujitsu Si... | AMILO Li3710                | [7a4a682f45](https://linux-hardware.org/?probe=7a4a682f45) | Mar 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [2c44722344](https://linux-hardware.org/?probe=2c44722344) | Mar 03, 2022 |
| ASUSTek       | E200HA                      | [69ec87e43a](https://linux-hardware.org/?probe=69ec87e43a) | Mar 02, 2022 |
| HP            | Laptop 15s-fq0xxx           | [9acf95b26b](https://linux-hardware.org/?probe=9acf95b26b) | Feb 28, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [03a49e64cf](https://linux-hardware.org/?probe=03a49e64cf) | Feb 28, 2022 |
| Gigabyte      | AERO 17 KC                  | [08b488b969](https://linux-hardware.org/?probe=08b488b969) | Feb 27, 2022 |
| Dell          | Latitude 7490               | [003b6b4a95](https://linux-hardware.org/?probe=003b6b4a95) | Feb 21, 2022 |
| Dell          | Inspiron 3581               | [0ae0e53b53](https://linux-hardware.org/?probe=0ae0e53b53) | Feb 20, 2022 |
| HP            | Notebook                    | [a1f9f76ed0](https://linux-hardware.org/?probe=a1f9f76ed0) | Feb 19, 2022 |
| Toshiba       | Satellite C55-A             | [19133950aa](https://linux-hardware.org/?probe=19133950aa) | Feb 15, 2022 |
| ASUSTek       | X55A                        | [c6b17158ac](https://linux-hardware.org/?probe=c6b17158ac) | Feb 14, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X1S... | [4f80537faf](https://linux-hardware.org/?probe=4f80537faf) | Feb 06, 2022 |
| Toshiba       | Satellite C55-C             | [379d3b37b1](https://linux-hardware.org/?probe=379d3b37b1) | Feb 05, 2022 |
| BenQ          | Joybook Lite U121           | [28f254dd8d](https://linux-hardware.org/?probe=28f254dd8d) | Feb 02, 2022 |
| Dell          | Vostro 3500                 | [729abacd12](https://linux-hardware.org/?probe=729abacd12) | Feb 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [5e9f8a1c0d](https://linux-hardware.org/?probe=5e9f8a1c0d) | Jan 29, 2022 |
| Dell          | Latitude E6510              | [efc619cc61](https://linux-hardware.org/?probe=efc619cc61) | Jan 28, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [37ec4f5294](https://linux-hardware.org/?probe=37ec4f5294) | Jan 25, 2022 |
| ASUSTek       | E200HA                      | [2c53d21746](https://linux-hardware.org/?probe=2c53d21746) | Jan 22, 2022 |
| ASUSTek       | E200HA                      | [02be439ac8](https://linux-hardware.org/?probe=02be439ac8) | Jan 22, 2022 |
| HP            | EliteBook 1050 G1           | [1bb5cb826f](https://linux-hardware.org/?probe=1bb5cb826f) | Jan 19, 2022 |
| TWC           | Unknown                     | [85a8fd2cf1](https://linux-hardware.org/?probe=85a8fd2cf1) | Jan 18, 2022 |
| TWC           | Unknown                     | [d4cc69cea7](https://linux-hardware.org/?probe=d4cc69cea7) | Jan 16, 2022 |
| Fujitsu       | LIFEBOOK A3510              | [b673072fbb](https://linux-hardware.org/?probe=b673072fbb) | Jan 11, 2022 |
| Dell          | Vostro 5402                 | [f586d10ee6](https://linux-hardware.org/?probe=f586d10ee6) | Jan 05, 2022 |
| MSI           | GT70 2PC                    | [61a5023d6a](https://linux-hardware.org/?probe=61a5023d6a) | Jan 03, 2022 |
| Dell          | Latitude 7490               | [2d6469644a](https://linux-hardware.org/?probe=2d6469644a) | Jan 02, 2022 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | [afb7fa66f5](https://linux-hardware.org/?probe=afb7fa66f5) | Dec 30, 2021 |
| Dell          | Latitude 7490               | [4e350048ed](https://linux-hardware.org/?probe=4e350048ed) | Dec 27, 2021 |
| Fujitsu Si... | AMILO Li3710                | [183a47572f](https://linux-hardware.org/?probe=183a47572f) | Dec 27, 2021 |
| ASUSTek       | X580VD                      | [fe350107e3](https://linux-hardware.org/?probe=fe350107e3) | Dec 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | [74591e1700](https://linux-hardware.org/?probe=74591e1700) | Dec 12, 2021 |
| Toshiba       | Satellite Pro L650          | [fd40a9d639](https://linux-hardware.org/?probe=fd40a9d639) | Dec 07, 2021 |
| HP            | Laptop 15s-eq1xxx           | [a61a3df5f9](https://linux-hardware.org/?probe=a61a3df5f9) | Dec 04, 2021 |
| Dell          | Vostro 3500                 | [3df309c91c](https://linux-hardware.org/?probe=3df309c91c) | Dec 03, 2021 |
| Fujitsu Si... | AMILO Li3910                | [6f355c1c73](https://linux-hardware.org/?probe=6f355c1c73) | Dec 01, 2021 |
| HP            | Laptop 14-ck0xxx            | [60a074698a](https://linux-hardware.org/?probe=60a074698a) | Dec 01, 2021 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [440d34a6b0](https://linux-hardware.org/?probe=440d34a6b0) | Nov 28, 2021 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [bb7b625409](https://linux-hardware.org/?probe=bb7b625409) | Nov 28, 2021 |
| ASUSTek       | N53SN                       | [67d66feb3e](https://linux-hardware.org/?probe=67d66feb3e) | Nov 20, 2021 |
| Acer          | Aspire ES1-533              | [14a4c57e27](https://linux-hardware.org/?probe=14a4c57e27) | Nov 05, 2021 |
| Lenovo        | G500 20236                  | [7708d61566](https://linux-hardware.org/?probe=7708d61566) | Nov 05, 2021 |
| eMachines     | eME440                      | [1427ebffb0](https://linux-hardware.org/?probe=1427ebffb0) | Oct 29, 2021 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | [f8024b89d4](https://linux-hardware.org/?probe=f8024b89d4) | Oct 28, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [d180cf6efc](https://linux-hardware.org/?probe=d180cf6efc) | Oct 23, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X1S... | [cb8bcc4d2d](https://linux-hardware.org/?probe=cb8bcc4d2d) | Oct 22, 2021 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | [a99866abc1](https://linux-hardware.org/?probe=a99866abc1) | Oct 21, 2021 |
| HP            | EliteBook 840 G3            | [650c91f4db](https://linux-hardware.org/?probe=650c91f4db) | Oct 18, 2021 |
| HP            | EliteBook 840 G3            | [5e28e542c2](https://linux-hardware.org/?probe=5e28e542c2) | Oct 17, 2021 |
| Dell          | Inspiron 3520               | [7eafd054fc](https://linux-hardware.org/?probe=7eafd054fc) | Oct 17, 2021 |
| HP            | Laptop 15s-eq2xxx           | [2e7ac4731f](https://linux-hardware.org/?probe=2e7ac4731f) | Oct 16, 2021 |
| Lenovo        | G555 0873                   | [a38f52851a](https://linux-hardware.org/?probe=a38f52851a) | Oct 05, 2021 |
| ASUSTek       | 1005PE                      | [bd2044749b](https://linux-hardware.org/?probe=bd2044749b) | Sep 22, 2021 |
| Acer          | Aspire V3-571G              | [b9fcdffa50](https://linux-hardware.org/?probe=b9fcdffa50) | Sep 22, 2021 |
| ASUSTek       | 1005PE                      | [02ccb36302](https://linux-hardware.org/?probe=02ccb36302) | Sep 21, 2021 |
| ASUSTek       | 1005PE                      | [081e791398](https://linux-hardware.org/?probe=081e791398) | Sep 19, 2021 |
| Toshiba       | Satellite C55-B             | [59a0efda89](https://linux-hardware.org/?probe=59a0efda89) | Sep 18, 2021 |
| ASUSTek       | 1005PE                      | [a3adf0356c](https://linux-hardware.org/?probe=a3adf0356c) | Sep 18, 2021 |
| Acer          | Aspire V3-571G              | [cedbbde363](https://linux-hardware.org/?probe=cedbbde363) | Sep 13, 2021 |
| Lenovo        | G500 20236                  | [f77883b614](https://linux-hardware.org/?probe=f77883b614) | Sep 07, 2021 |
| HP            | ProBook 4730s               | [36834479ab](https://linux-hardware.org/?probe=36834479ab) | Sep 03, 2021 |
| Apple         | MacBookPro8,1               | [da332ba09e](https://linux-hardware.org/?probe=da332ba09e) | Sep 01, 2021 |
| Dell          | Inspiron 3537               | [cad80329d8](https://linux-hardware.org/?probe=cad80329d8) | Aug 31, 2021 |
| Lenovo        | G500 20236                  | [60f43f8815](https://linux-hardware.org/?probe=60f43f8815) | Aug 29, 2021 |
| Dell          | Inspiron 5593               | [ebac51e403](https://linux-hardware.org/?probe=ebac51e403) | Aug 28, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [62c96ffa5b](https://linux-hardware.org/?probe=62c96ffa5b) | Aug 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [516b9ff2ed](https://linux-hardware.org/?probe=516b9ff2ed) | Aug 25, 2021 |
| Dell          | Inspiron 7520               | [056e1c0825](https://linux-hardware.org/?probe=056e1c0825) | Aug 21, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [79051f2400](https://linux-hardware.org/?probe=79051f2400) | Aug 19, 2021 |
| HP            | EliteBook 840 G5            | [4c196e1abd](https://linux-hardware.org/?probe=4c196e1abd) | Aug 18, 2021 |
| HP            | G62                         | [b6eeeba9d1](https://linux-hardware.org/?probe=b6eeeba9d1) | Aug 15, 2021 |
| HP            | G62                         | [4adea9bed4](https://linux-hardware.org/?probe=4adea9bed4) | Aug 14, 2021 |
| HP            | Pavilion g6                 | [df95184640](https://linux-hardware.org/?probe=df95184640) | Aug 02, 2021 |
| HP            | Pavilion g6                 | [0e0aaaac98](https://linux-hardware.org/?probe=0e0aaaac98) | Aug 02, 2021 |
| Toshiba       | Satellite Pro L650          | [10e8624257](https://linux-hardware.org/?probe=10e8624257) | Jul 27, 2021 |
| Toshiba       | Satellite C55-B             | [c703c827c6](https://linux-hardware.org/?probe=c703c827c6) | Jul 21, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b44e9be41b](https://linux-hardware.org/?probe=b44e9be41b) | Jul 19, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [56faa89619](https://linux-hardware.org/?probe=56faa89619) | Jul 16, 2021 |
| Lenovo        | V330-15IKB 81AX             | [70128f07ea](https://linux-hardware.org/?probe=70128f07ea) | Jul 13, 2021 |
| HP            | Compaq nx7400 (RU429EA#A... | [ce0542775b](https://linux-hardware.org/?probe=ce0542775b) | Jun 22, 2021 |
| Lenovo        | ThinkPad X201 Tablet 298... | [d04705eaef](https://linux-hardware.org/?probe=d04705eaef) | Jun 20, 2021 |
| ASUSTek       | G551JK                      | [aace05a48f](https://linux-hardware.org/?probe=aace05a48f) | Jun 17, 2021 |
| ASUSTek       | G551JK                      | [2947ae8fc2](https://linux-hardware.org/?probe=2947ae8fc2) | Jun 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [80b26a6c37](https://linux-hardware.org/?probe=80b26a6c37) | Jun 16, 2021 |
| Dell          | Inspiron 15-3567            | [8487e42c1e](https://linux-hardware.org/?probe=8487e42c1e) | Jun 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [18fd922adc](https://linux-hardware.org/?probe=18fd922adc) | Jun 10, 2021 |
| Dell          | Latitude 5520               | [45b3e7c2af](https://linux-hardware.org/?probe=45b3e7c2af) | Jun 06, 2021 |
| Dell          | Vostro 5402                 | [ec4c7c0192](https://linux-hardware.org/?probe=ec4c7c0192) | Jun 04, 2021 |
| MSI           | CR500                       | [76d2d77034](https://linux-hardware.org/?probe=76d2d77034) | Jun 03, 2021 |
| MSI           | CR500                       | [93f6fd0ae4](https://linux-hardware.org/?probe=93f6fd0ae4) | Jun 02, 2021 |
| MSI           | CR500                       | [b1d00d1444](https://linux-hardware.org/?probe=b1d00d1444) | May 30, 2021 |
| HP            | Notebook                    | [f60121b761](https://linux-hardware.org/?probe=f60121b761) | May 30, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [f794ea73e4](https://linux-hardware.org/?probe=f794ea73e4) | May 28, 2021 |
| Apple         | MacBookPro1,1               | [cc14c7fa2e](https://linux-hardware.org/?probe=cc14c7fa2e) | May 16, 2021 |
| HP            | ProBook 4530s               | [3d5a77511e](https://linux-hardware.org/?probe=3d5a77511e) | May 12, 2021 |
| Dell          | Vostro 5402                 | [03aa94f52f](https://linux-hardware.org/?probe=03aa94f52f) | May 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [b57920ccda](https://linux-hardware.org/?probe=b57920ccda) | May 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [19bf5a98df](https://linux-hardware.org/?probe=19bf5a98df) | May 10, 2021 |
| ASUSTek       | K53E                        | [314e6bbbd2](https://linux-hardware.org/?probe=314e6bbbd2) | May 04, 2021 |
| ASUSTek       | K53E                        | [9a34eba18a](https://linux-hardware.org/?probe=9a34eba18a) | May 03, 2021 |
| Fujitsu Si... | AMILO Pi 2512               | [bc0294a996](https://linux-hardware.org/?probe=bc0294a996) | May 03, 2021 |
| HP            | EliteBook 2540p             | [506fb4d003](https://linux-hardware.org/?probe=506fb4d003) | May 02, 2021 |
| Lenovo        | ThinkPad T440s 20ARS3B00... | [fa546522c1](https://linux-hardware.org/?probe=fa546522c1) | May 02, 2021 |
| Medion        | P6812                       | [a45bd7fc22](https://linux-hardware.org/?probe=a45bd7fc22) | Apr 19, 2021 |
| Acer          | Aspire A315-31              | [2b821447d2](https://linux-hardware.org/?probe=2b821447d2) | Apr 14, 2021 |
| Acer          | Aspire A315-31              | [e7a7c4b64f](https://linux-hardware.org/?probe=e7a7c4b64f) | Apr 14, 2021 |
| Acer          | Aspire A315-23              | [c7a0c1bf24](https://linux-hardware.org/?probe=c7a0c1bf24) | Apr 13, 2021 |
| HP            | Pavilion 15                 | [88ca55e5af](https://linux-hardware.org/?probe=88ca55e5af) | Apr 08, 2021 |
| Acer          | Aspire A515-51G             | [97f260c7d5](https://linux-hardware.org/?probe=97f260c7d5) | Mar 31, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [084a69a05a](https://linux-hardware.org/?probe=084a69a05a) | Mar 30, 2021 |
| Dell          | G5 5587                     | [862386a9b4](https://linux-hardware.org/?probe=862386a9b4) | Mar 27, 2021 |
| HP            | Laptop 15-db1xxx            | [59fb434d97](https://linux-hardware.org/?probe=59fb434d97) | Mar 21, 2021 |
| HP            | Laptop 15-db1xxx            | [aab4f11f05](https://linux-hardware.org/?probe=aab4f11f05) | Mar 21, 2021 |
| Dell          | Inspiron 3542               | [517406f8b6](https://linux-hardware.org/?probe=517406f8b6) | Mar 21, 2021 |
| HP            | ZBook 15 G3                 | [4ab4d49018](https://linux-hardware.org/?probe=4ab4d49018) | Mar 17, 2021 |
| HP            | Laptop 15-da1xxx            | [ed4ddd6238](https://linux-hardware.org/?probe=ed4ddd6238) | Mar 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [640a0a3857](https://linux-hardware.org/?probe=640a0a3857) | Mar 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [66de852009](https://linux-hardware.org/?probe=66de852009) | Mar 11, 2021 |
| Acer          | Aspire 5742G                | [659f9d690c](https://linux-hardware.org/?probe=659f9d690c) | Mar 10, 2021 |
| Dell          | Latitude E6320              | [a69653a323](https://linux-hardware.org/?probe=a69653a323) | Mar 08, 2021 |
| Acer          | Aspire 5735                 | [cde827bd2e](https://linux-hardware.org/?probe=cde827bd2e) | Mar 07, 2021 |
| Acer          | Aspire 5735                 | [9730b9273d](https://linux-hardware.org/?probe=9730b9273d) | Mar 07, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [7d5313fdad](https://linux-hardware.org/?probe=7d5313fdad) | Mar 06, 2021 |
| Toshiba       | Satellite L20               | [875478a51a](https://linux-hardware.org/?probe=875478a51a) | Mar 06, 2021 |
| HP            | ProBook 650 G1              | [e21aaf16e3](https://linux-hardware.org/?probe=e21aaf16e3) | Mar 03, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [a94321f4aa](https://linux-hardware.org/?probe=a94321f4aa) | Feb 27, 2021 |
| Dell          | Inspiron 7520               | [4611155200](https://linux-hardware.org/?probe=4611155200) | Feb 20, 2021 |
| HP            | ProBook 470 G3              | [12ef122267](https://linux-hardware.org/?probe=12ef122267) | Feb 19, 2021 |
| Dell          | Inspiron 3542               | [d77d8a8749](https://linux-hardware.org/?probe=d77d8a8749) | Feb 18, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [5843b21ecd](https://linux-hardware.org/?probe=5843b21ecd) | Feb 14, 2021 |
| HP            | ProBook 650 G1              | [2dcb1a408a](https://linux-hardware.org/?probe=2dcb1a408a) | Feb 13, 2021 |
| HP            | ProBook 650 G1              | [1d63d4f78d](https://linux-hardware.org/?probe=1d63d4f78d) | Feb 10, 2021 |
| Dell          | Latitude E5470              | [ac140ada48](https://linux-hardware.org/?probe=ac140ada48) | Feb 09, 2021 |
| Lenovo        | IdeaPad Y570 20091          | [e80a31db39](https://linux-hardware.org/?probe=e80a31db39) | Feb 03, 2021 |
| Dell          | Latitude E5470              | [72db68119a](https://linux-hardware.org/?probe=72db68119a) | Jan 27, 2021 |
| Dell          | Latitude E6430              | [b7f8906f0f](https://linux-hardware.org/?probe=b7f8906f0f) | Jan 27, 2021 |
| Lenovo        | IdeaPad Y570 20091          | [68fdde328b](https://linux-hardware.org/?probe=68fdde328b) | Jan 27, 2021 |
| HP            | EliteBook 8560p             | [875db98e08](https://linux-hardware.org/?probe=875db98e08) | Jan 23, 2021 |
| Acer          | Aspire 5736Z                | [6bb8df4de2](https://linux-hardware.org/?probe=6bb8df4de2) | Jan 21, 2021 |
| Lenovo        | Legion Y7000 2019 PG0 81... | [9f77ea6e17](https://linux-hardware.org/?probe=9f77ea6e17) | Jan 14, 2021 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [ab2decc440](https://linux-hardware.org/?probe=ab2decc440) | Jan 12, 2021 |
| Lenovo        | ThinkPad R400 2786W1L       | [5335da910d](https://linux-hardware.org/?probe=5335da910d) | Jan 10, 2021 |
| Lenovo        | ThinkPad R400 2786W1L       | [c7fbffcc09](https://linux-hardware.org/?probe=c7fbffcc09) | Jan 10, 2021 |
| Packard Be... | EasyNote TS11HR             | [ab603b2fe8](https://linux-hardware.org/?probe=ab603b2fe8) | Jan 06, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [7e0f5ef3ce](https://linux-hardware.org/?probe=7e0f5ef3ce) | Jan 04, 2021 |
| Toshiba       | Satellite C650              | [da33e577bf](https://linux-hardware.org/?probe=da33e577bf) | Jan 02, 2021 |
| Packard Be... | EasyNote TS11HR             | [343249d2da](https://linux-hardware.org/?probe=343249d2da) | Jan 02, 2021 |
| Toshiba       | Satellite C650              | [3ccf619144](https://linux-hardware.org/?probe=3ccf619144) | Dec 31, 2020 |
| ASUSTek       | X541NA                      | [ce08535027](https://linux-hardware.org/?probe=ce08535027) | Dec 25, 2020 |
| ASUSTek       | X541NA                      | [a026c30d04](https://linux-hardware.org/?probe=a026c30d04) | Dec 25, 2020 |
| HP            | Laptop 15-db0xxx            | [87ecbeb3f9](https://linux-hardware.org/?probe=87ecbeb3f9) | Dec 22, 2020 |
| Lenovo        | V330-15IKB 81AX             | [7bbfaa08a2](https://linux-hardware.org/?probe=7bbfaa08a2) | Dec 19, 2020 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [a3f26b77de](https://linux-hardware.org/?probe=a3f26b77de) | Dec 17, 2020 |
| Acer          | Aspire A315-31              | [3d19374493](https://linux-hardware.org/?probe=3d19374493) | Dec 17, 2020 |
| Dell          | XPS 13 9380                 | [1eae71a2dd](https://linux-hardware.org/?probe=1eae71a2dd) | Dec 14, 2020 |
| Acer          | Aspire A315-31              | [630a5fce15](https://linux-hardware.org/?probe=630a5fce15) | Dec 11, 2020 |
| Acer          | Aspire A715-75G             | [9c6b3be687](https://linux-hardware.org/?probe=9c6b3be687) | Dec 10, 2020 |
| Acer          | Aspire A717-71G             | [f355a859fe](https://linux-hardware.org/?probe=f355a859fe) | Dec 05, 2020 |
| Acer          | Aspire A717-71G             | [e0144299e5](https://linux-hardware.org/?probe=e0144299e5) | Dec 05, 2020 |
| Acer          | Aspire A715-75G             | [4d6f15896a](https://linux-hardware.org/?probe=4d6f15896a) | Dec 01, 2020 |
| Acer          | Aspire A715-75G             | [cea1efd2f4](https://linux-hardware.org/?probe=cea1efd2f4) | Dec 01, 2020 |
| Acer          | Aspire ES1-533              | [e20dc3c4e4](https://linux-hardware.org/?probe=e20dc3c4e4) | Nov 26, 2020 |
| Acer          | Aspire ES1-533              | [1ff481eb22](https://linux-hardware.org/?probe=1ff481eb22) | Nov 26, 2020 |
| Lenovo        | V15-ADA 82C7                | [c25d3746ee](https://linux-hardware.org/?probe=c25d3746ee) | Nov 24, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [b59cef94de](https://linux-hardware.org/?probe=b59cef94de) | Nov 22, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [cb540754ed](https://linux-hardware.org/?probe=cb540754ed) | Nov 22, 2020 |
| MSI           | CR610                       | [8e7bf69342](https://linux-hardware.org/?probe=8e7bf69342) | Nov 22, 2020 |
| MSI           | CR610                       | [ba50d62533](https://linux-hardware.org/?probe=ba50d62533) | Nov 22, 2020 |
| Dell          | Inspiron 3541               | [f10a3f7947](https://linux-hardware.org/?probe=f10a3f7947) | Nov 21, 2020 |
| Dell          | Inspiron 3541               | [28a2250b7c](https://linux-hardware.org/?probe=28a2250b7c) | Nov 21, 2020 |
| Lenovo        | V130-14IGM 81HM             | [e282aa9ff3](https://linux-hardware.org/?probe=e282aa9ff3) | Nov 20, 2020 |
| Lenovo        | V15-ADA 82C7                | [aa224b81ef](https://linux-hardware.org/?probe=aa224b81ef) | Nov 18, 2020 |
| HP            | Laptop 15-da0xxx            | [2cc03df5d0](https://linux-hardware.org/?probe=2cc03df5d0) | Nov 16, 2020 |
| HP            | Pavilion Notebook           | [c68070f9b3](https://linux-hardware.org/?probe=c68070f9b3) | Nov 10, 2020 |
| HP            | Pavilion Notebook           | [99e25d58ad](https://linux-hardware.org/?probe=99e25d58ad) | Nov 10, 2020 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [9555e785bb](https://linux-hardware.org/?probe=9555e785bb) | Nov 09, 2020 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [0de6c928a4](https://linux-hardware.org/?probe=0de6c928a4) | Nov 09, 2020 |
| Lenovo        | V130-14IGM 81HM             | [23fd9c7140](https://linux-hardware.org/?probe=23fd9c7140) | Nov 09, 2020 |
| Dell          | Inspiron 1720               | [d2018981ad](https://linux-hardware.org/?probe=d2018981ad) | Nov 05, 2020 |
| Lenovo        | V330-15IKB 81AX             | [c6872a9a60](https://linux-hardware.org/?probe=c6872a9a60) | Nov 03, 2020 |
| ASUSTek       | X541NA                      | [a3067761af](https://linux-hardware.org/?probe=a3067761af) | Oct 18, 2020 |
| ASUSTek       | X541NA                      | [baf94800b6](https://linux-hardware.org/?probe=baf94800b6) | Oct 18, 2020 |
| Lenovo        | 3000 N200 0769BNG           | [233a47535c](https://linux-hardware.org/?probe=233a47535c) | Oct 15, 2020 |
| ASUSTek       | TUF Gaming FA506II_FA506... | [9356879a60](https://linux-hardware.org/?probe=9356879a60) | Oct 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [4ccef20bb6](https://linux-hardware.org/?probe=4ccef20bb6) | Oct 13, 2020 |
| Lenovo        | 3000 N200 0769BNG           | [8ea03b6d29](https://linux-hardware.org/?probe=8ea03b6d29) | Oct 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [43c0586dbe](https://linux-hardware.org/?probe=43c0586dbe) | Oct 12, 2020 |
| Acer          | Aspire A315-31              | [00686fcd7b](https://linux-hardware.org/?probe=00686fcd7b) | Oct 12, 2020 |
| Dell          | Latitude E5470              | [a1ae53e261](https://linux-hardware.org/?probe=a1ae53e261) | Oct 06, 2020 |
| Acer          | Aspire A515-55              | [d88d774f7f](https://linux-hardware.org/?probe=d88d774f7f) | Oct 05, 2020 |
| Lenovo        | B50-45 20388                | [c25c3ef2d8](https://linux-hardware.org/?probe=c25c3ef2d8) | Oct 05, 2020 |
| Lenovo        | B50-45 20388                | [e3d174f961](https://linux-hardware.org/?probe=e3d174f961) | Oct 05, 2020 |
| Lenovo        | V330-15IKB 81AX             | [cb2c394f1a](https://linux-hardware.org/?probe=cb2c394f1a) | Oct 02, 2020 |
| HP            | Notebook                    | [9fcfc67d9c](https://linux-hardware.org/?probe=9fcfc67d9c) | Sep 29, 2020 |
| Lenovo        | V330-15IKB 81AX             | [1734ca75eb](https://linux-hardware.org/?probe=1734ca75eb) | Sep 29, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0KK0... | [d231920967](https://linux-hardware.org/?probe=d231920967) | Sep 28, 2020 |
| HP            | 355 G2                      | [07981744ab](https://linux-hardware.org/?probe=07981744ab) | Sep 27, 2020 |
| HP            | 355 G2                      | [08e4ab3c53](https://linux-hardware.org/?probe=08e4ab3c53) | Sep 26, 2020 |
| Lenovo        | V330-15IKB 81AX             | [a34c376304](https://linux-hardware.org/?probe=a34c376304) | Sep 18, 2020 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [20c5e9395d](https://linux-hardware.org/?probe=20c5e9395d) | Sep 16, 2020 |
| Toshiba       | QOSMIO F50                  | [b60fe2f9e5](https://linux-hardware.org/?probe=b60fe2f9e5) | Sep 16, 2020 |
| HP            | Laptop 17-by2xxx            | [d3fcaecf43](https://linux-hardware.org/?probe=d3fcaecf43) | Sep 12, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [eea494974a](https://linux-hardware.org/?probe=eea494974a) | Sep 11, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [00956078a0](https://linux-hardware.org/?probe=00956078a0) | Sep 03, 2020 |
| Acer          | AOA150                      | [d7397a31d7](https://linux-hardware.org/?probe=d7397a31d7) | Aug 31, 2020 |
| Dell          | Inspiron 3593               | [2c97a34461](https://linux-hardware.org/?probe=2c97a34461) | Aug 20, 2020 |
| HP            | 530 Notebook PC(GU327AA#... | [55d79e4d6a](https://linux-hardware.org/?probe=55d79e4d6a) | Aug 17, 2020 |
| HP            | 530 Notebook PC(GU327AA#... | [19b6cecfad](https://linux-hardware.org/?probe=19b6cecfad) | Aug 17, 2020 |
| Lenovo        | ThinkPad T480 20L6S43212    | [e408e4045b](https://linux-hardware.org/?probe=e408e4045b) | Aug 16, 2020 |
| Dell          | Inspiron 5577               | [f10ef91563](https://linux-hardware.org/?probe=f10ef91563) | Aug 06, 2020 |
| MSI           | CR500                       | [a347574891](https://linux-hardware.org/?probe=a347574891) | Aug 03, 2020 |
| MSI           | CR500                       | [21b1264f8c](https://linux-hardware.org/?probe=21b1264f8c) | Aug 03, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [a2dd413553](https://linux-hardware.org/?probe=a2dd413553) | Jul 26, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [e1073052d4](https://linux-hardware.org/?probe=e1073052d4) | Jul 26, 2020 |
| HP            | ProBook 450 G1              | [8db5efa1fc](https://linux-hardware.org/?probe=8db5efa1fc) | Jul 22, 2020 |
| Acer          | Aspire A315-42              | [b5aacd7b39](https://linux-hardware.org/?probe=b5aacd7b39) | Jul 12, 2020 |
| Acer          | Aspire A315-42              | [88afcfbe5b](https://linux-hardware.org/?probe=88afcfbe5b) | Jul 11, 2020 |
| Lenovo        | V110-15AST 80TD             | [6a86c949a2](https://linux-hardware.org/?probe=6a86c949a2) | Jul 10, 2020 |
| Acer          | Aspire A315-31              | [3ab4bed99e](https://linux-hardware.org/?probe=3ab4bed99e) | Jul 05, 2020 |
| Acer          | Aspire E1-531               | [7baad79bd7](https://linux-hardware.org/?probe=7baad79bd7) | Jul 04, 2020 |
| Lenovo        | V110-15AST 80TD             | [16211b52a1](https://linux-hardware.org/?probe=16211b52a1) | Jun 25, 2020 |
| Sony          | VPCZ21X9E                   | [72e4be4ea5](https://linux-hardware.org/?probe=72e4be4ea5) | Jun 12, 2020 |
| Sony          | VPCZ21X9E                   | [26affa7385](https://linux-hardware.org/?probe=26affa7385) | Jun 12, 2020 |
| Apple         | MacBook5,1                  | [099f5faf14](https://linux-hardware.org/?probe=099f5faf14) | Jun 02, 2020 |
| ASUSTek       | N550JX                      | [99693da42c](https://linux-hardware.org/?probe=99693da42c) | May 31, 2020 |
| Dell          | Inspiron 5559               | [3eee5b1f3d](https://linux-hardware.org/?probe=3eee5b1f3d) | May 31, 2020 |
| HP            | 250 G5 Notebook PC          | [1a72632c64](https://linux-hardware.org/?probe=1a72632c64) | May 27, 2020 |
| Lenovo        | V330-15IKB 81AX             | [c4087d6c6a](https://linux-hardware.org/?probe=c4087d6c6a) | May 21, 2020 |
| ASUSTek       | K50AB                       | [96ccf326a8](https://linux-hardware.org/?probe=96ccf326a8) | May 19, 2020 |
| Dell          | Inspiron N5010              | [f1e4f13c21](https://linux-hardware.org/?probe=f1e4f13c21) | May 18, 2020 |
| Lenovo        | V310-15ISK 80SY             | [a608769eb0](https://linux-hardware.org/?probe=a608769eb0) | May 15, 2020 |
| Lenovo        | ThinkPad T460 20FNS0KT00    | [92e676e189](https://linux-hardware.org/?probe=92e676e189) | May 15, 2020 |
| Lenovo        | ThinkPad T460 20FNS0KT00    | [b7fd9a70e0](https://linux-hardware.org/?probe=b7fd9a70e0) | May 15, 2020 |
| ASUSTek       | G551JK                      | [1d29493d79](https://linux-hardware.org/?probe=1d29493d79) | May 14, 2020 |
| ASUSTek       | G551JK                      | [2aa55f08d0](https://linux-hardware.org/?probe=2aa55f08d0) | May 14, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [03ba757adf](https://linux-hardware.org/?probe=03ba757adf) | May 13, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [dadd9d2790](https://linux-hardware.org/?probe=dadd9d2790) | May 12, 2020 |
| HP            | ZBook 15 G3                 | [3474070eb8](https://linux-hardware.org/?probe=3474070eb8) | May 10, 2020 |
| Lenovo        | G50-30 80G0                 | [4ac3289ec9](https://linux-hardware.org/?probe=4ac3289ec9) | May 09, 2020 |
| ASUSTek       | K54C                        | [3188c4843a](https://linux-hardware.org/?probe=3188c4843a) | May 08, 2020 |
| Dell          | Inspiron 5567               | [099e174bf4](https://linux-hardware.org/?probe=099e174bf4) | May 07, 2020 |
| Lenovo        | ThinkPad L470 20J5S4RS00    | [b646e36068](https://linux-hardware.org/?probe=b646e36068) | May 04, 2020 |
| Dell          | Inspiron 3537               | [a26c6f5812](https://linux-hardware.org/?probe=a26c6f5812) | Apr 21, 2020 |
| HP            | 250 G5 Notebook PC          | [01f3f0f185](https://linux-hardware.org/?probe=01f3f0f185) | Apr 14, 2020 |
| Lenovo        | ThinkPad E560 20EV003EMS    | [0b978ac786](https://linux-hardware.org/?probe=0b978ac786) | Apr 14, 2020 |
| HP            | ZBook 15 G3                 | [16ee557e51](https://linux-hardware.org/?probe=16ee557e51) | Apr 12, 2020 |
| HP            | Mini 110-3100               | [a32c0db8bb](https://linux-hardware.org/?probe=a32c0db8bb) | Apr 11, 2020 |
| Acer          | Aspire 7520G                | [d5bc992097](https://linux-hardware.org/?probe=d5bc992097) | Apr 04, 2020 |
| Toshiba       | TECRA Z50-A                 | [889a5aa1a6](https://linux-hardware.org/?probe=889a5aa1a6) | Apr 02, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [cb84e8c9af](https://linux-hardware.org/?probe=cb84e8c9af) | Mar 23, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [8670fa919e](https://linux-hardware.org/?probe=8670fa919e) | Mar 23, 2020 |
| ASUSTek       | X541NC                      | [63b197a2c0](https://linux-hardware.org/?probe=63b197a2c0) | Mar 21, 2020 |
| Fujitsu Si... | AMILO Li3710                | [11ebf93798](https://linux-hardware.org/?probe=11ebf93798) | Mar 18, 2020 |
| Lenovo        | Yoga 300-11IBR 80M1         | [b19ba42878](https://linux-hardware.org/?probe=b19ba42878) | Mar 17, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [334884c294](https://linux-hardware.org/?probe=334884c294) | Mar 10, 2020 |
| HP            | 250 G1                      | [7a7e2dfcee](https://linux-hardware.org/?probe=7a7e2dfcee) | Mar 10, 2020 |
| HP            | 250 G4                      | [d8b2caab0f](https://linux-hardware.org/?probe=d8b2caab0f) | Mar 08, 2020 |
| Acer          | Aspire A315-41              | [5870ecc433](https://linux-hardware.org/?probe=5870ecc433) | Mar 08, 2020 |
| Acer          | Aspire E3-112               | [62041aa7fa](https://linux-hardware.org/?probe=62041aa7fa) | Mar 08, 2020 |
| Lenovo        | ThinkPad T500 2056W2J       | [1923e28174](https://linux-hardware.org/?probe=1923e28174) | Mar 05, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [bda2f29230](https://linux-hardware.org/?probe=bda2f29230) | Feb 24, 2020 |
| Fujitsu       | LIFEBOOK AH530              | [5d93dd0911](https://linux-hardware.org/?probe=5d93dd0911) | Feb 20, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [eb55029938](https://linux-hardware.org/?probe=eb55029938) | Feb 18, 2020 |
| ASUSTek       | X551MA                      | [530fb26de2](https://linux-hardware.org/?probe=530fb26de2) | Feb 16, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [4d942fa22c](https://linux-hardware.org/?probe=4d942fa22c) | Feb 10, 2020 |
| ASUSTek       | X541UVK                     | [9e44db3513](https://linux-hardware.org/?probe=9e44db3513) | Feb 06, 2020 |
| Lenovo        | G505 20240                  | [3208a023bf](https://linux-hardware.org/?probe=3208a023bf) | Feb 04, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [91bdd7eccf](https://linux-hardware.org/?probe=91bdd7eccf) | Feb 01, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a4a64dfa74](https://linux-hardware.org/?probe=a4a64dfa74) | Feb 01, 2020 |
| Acer          | Aspire E1-530               | [0e64af354b](https://linux-hardware.org/?probe=0e64af354b) | Jan 30, 2020 |
| Acer          | Swift SF314-56              | [303332d310](https://linux-hardware.org/?probe=303332d310) | Jan 29, 2020 |
| Toshiba       | Satellite C50-B             | [06c487df1d](https://linux-hardware.org/?probe=06c487df1d) | Jan 28, 2020 |
| Acer          | Aspire A315-31              | [b482e7ef86](https://linux-hardware.org/?probe=b482e7ef86) | Jan 25, 2020 |
| Lenovo        | ThinkPad T520 42406AG       | [7de4fdce8d](https://linux-hardware.org/?probe=7de4fdce8d) | Jan 23, 2020 |
| Lenovo        | V330-15IKB 81AX             | [b0d2c5611e](https://linux-hardware.org/?probe=b0d2c5611e) | Jan 22, 2020 |
| HP            | Compaq nc6320 (RU381ES#A... | [d3a7e386ae](https://linux-hardware.org/?probe=d3a7e386ae) | Jan 16, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [84bf577e7d](https://linux-hardware.org/?probe=84bf577e7d) | Jan 16, 2020 |
| Acer          | Aspire A315-31              | [36dcda44ba](https://linux-hardware.org/?probe=36dcda44ba) | Jan 15, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [cc4a9ba559](https://linux-hardware.org/?probe=cc4a9ba559) | Jan 15, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [72f2c4c12a](https://linux-hardware.org/?probe=72f2c4c12a) | Jan 15, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b5d63aec77](https://linux-hardware.org/?probe=b5d63aec77) | Jan 15, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [7d389b1fcb](https://linux-hardware.org/?probe=7d389b1fcb) | Jan 15, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | [b2c0da1b44](https://linux-hardware.org/?probe=b2c0da1b44) | Jan 12, 2020 |
| HP            | ProBook 650 G1              | [224d2a830f](https://linux-hardware.org/?probe=224d2a830f) | Jan 08, 2020 |
| ASUSTek       | X55A                        | [3482727e9f](https://linux-hardware.org/?probe=3482727e9f) | Jan 03, 2020 |
| Lenovo        | ThinkPad P50 20EQS1AC00     | [0767220809](https://linux-hardware.org/?probe=0767220809) | Jan 03, 2020 |
| Dell          | Inspiron 3558               | [63be3850f8](https://linux-hardware.org/?probe=63be3850f8) | Dec 31, 2019 |
| Acer          | Aspire A315-51              | [fb858f1586](https://linux-hardware.org/?probe=fb858f1586) | Dec 30, 2019 |
| Acer          | Aspire A315-51              | [0dfa591b1c](https://linux-hardware.org/?probe=0dfa591b1c) | Dec 30, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [dfac3d950c](https://linux-hardware.org/?probe=dfac3d950c) | Dec 29, 2019 |
| Samsung       | N250P/N145P                 | [708195d4f1](https://linux-hardware.org/?probe=708195d4f1) | Dec 27, 2019 |
| Toshiba       | Satellite C850-1H6          | [a0ffb29c6c](https://linux-hardware.org/?probe=a0ffb29c6c) | Dec 18, 2019 |
| HP            | ProBook 640 G1              | [0813940da0](https://linux-hardware.org/?probe=0813940da0) | Dec 09, 2019 |
| Lenovo        | IdeaPad L340-15API 81LW     | [3193d44169](https://linux-hardware.org/?probe=3193d44169) | Dec 04, 2019 |
| ASUSTek       | X550MJ                      | [3fde87c7b4](https://linux-hardware.org/?probe=3fde87c7b4) | Dec 04, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [8a33af729e](https://linux-hardware.org/?probe=8a33af729e) | Dec 03, 2019 |
| Acer          | Aspire A315-51              | [77affe222c](https://linux-hardware.org/?probe=77affe222c) | Nov 16, 2019 |
| HP            | Notebook                    | [8df47391f9](https://linux-hardware.org/?probe=8df47391f9) | Nov 15, 2019 |
| Acer          | Aspire A315-31              | [3812d4729c](https://linux-hardware.org/?probe=3812d4729c) | Nov 14, 2019 |
| HP            | Notebook                    | [fe0316d8bb](https://linux-hardware.org/?probe=fe0316d8bb) | Nov 14, 2019 |
| Lenovo        | ThinkPad T420s 4174BB2      | [53037be14e](https://linux-hardware.org/?probe=53037be14e) | Nov 03, 2019 |
| Lenovo        | ThinkPad Edge E330 33544... | [c27afaa8d2](https://linux-hardware.org/?probe=c27afaa8d2) | Oct 20, 2019 |
| Acer          | Aspire 5350                 | [bfca910110](https://linux-hardware.org/?probe=bfca910110) | Oct 20, 2019 |
| Lenovo        | ThinkPad Edge E330 33544... | [0e391bc5f7](https://linux-hardware.org/?probe=0e391bc5f7) | Oct 20, 2019 |
| HP            | ProBook 650 G1              | [4886df0de1](https://linux-hardware.org/?probe=4886df0de1) | Oct 20, 2019 |
| Acer          | Aspire 5350                 | [6c1a1b4cd5](https://linux-hardware.org/?probe=6c1a1b4cd5) | Oct 19, 2019 |
| Dell          | Latitude 5580               | [e2d5fd3182](https://linux-hardware.org/?probe=e2d5fd3182) | Oct 18, 2019 |
| Dell          | Latitude 5580               | [fbb2c68803](https://linux-hardware.org/?probe=fbb2c68803) | Oct 18, 2019 |
| Dell          | Latitude 5580               | [4ba29dd71c](https://linux-hardware.org/?probe=4ba29dd71c) | Oct 18, 2019 |
| Acer          | Aspire A315-31              | [2ab608ac7e](https://linux-hardware.org/?probe=2ab608ac7e) | Oct 13, 2019 |
| HP            | Pavilion Notebook           | [dffd6ce6cb](https://linux-hardware.org/?probe=dffd6ce6cb) | Oct 13, 2019 |
| Lenovo        | IdeaPad S540-14API 81NH     | [d0671b5d7f](https://linux-hardware.org/?probe=d0671b5d7f) | Oct 12, 2019 |
| Acer          | Aspire A717-71G             | [4bad7bd17c](https://linux-hardware.org/?probe=4bad7bd17c) | Sep 21, 2019 |
| Lenovo        | ThinkPad T520 42406AG       | [3e835a3fea](https://linux-hardware.org/?probe=3e835a3fea) | Sep 15, 2019 |
| Razer         | Blade                       | [da397f901b](https://linux-hardware.org/?probe=da397f901b) | Sep 10, 2019 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [655aa5059b](https://linux-hardware.org/?probe=655aa5059b) | Sep 04, 2019 |
| HP            | Laptop 15-ra0xx             | [2e41137334](https://linux-hardware.org/?probe=2e41137334) | Sep 03, 2019 |
| HP            | Laptop 15-ra0xx             | [8aadf9c34a](https://linux-hardware.org/?probe=8aadf9c34a) | Sep 02, 2019 |
| HP            | Laptop 15-ra0xx             | [96e535cece](https://linux-hardware.org/?probe=96e535cece) | Sep 02, 2019 |
| Acer          | Aspire A315-31              | [9d8698e977](https://linux-hardware.org/?probe=9d8698e977) | Aug 28, 2019 |
| Acer          | Aspire A315-31              | [95dba17d9a](https://linux-hardware.org/?probe=95dba17d9a) | Aug 17, 2019 |
| Dell          | Precision 7730              | [b9281326d7](https://linux-hardware.org/?probe=b9281326d7) | Jul 25, 2019 |
| ASUSTek       | X201EP                      | [a1a1f1965a](https://linux-hardware.org/?probe=a1a1f1965a) | Jul 22, 2019 |
| Dell          | Latitude E5440              | [f40c3d18fb](https://linux-hardware.org/?probe=f40c3d18fb) | Jul 19, 2019 |
| Lenovo        | ThinkPad P51 20HHS04800     | [4013dc5bc1](https://linux-hardware.org/?probe=4013dc5bc1) | Jul 16, 2019 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [1613715663](https://linux-hardware.org/?probe=1613715663) | Jul 15, 2019 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [62ebee4d1f](https://linux-hardware.org/?probe=62ebee4d1f) | Jul 15, 2019 |
| ASUSTek       | X541NA                      | [5fdb751780](https://linux-hardware.org/?probe=5fdb751780) | Jul 11, 2019 |
| ASUSTek       | X541NA                      | [8676bfc466](https://linux-hardware.org/?probe=8676bfc466) | Jul 11, 2019 |
| HP            | Laptop 15-ra0xx             | [f28399b983](https://linux-hardware.org/?probe=f28399b983) | Jul 09, 2019 |
| Toshiba       | Satellite L755              | [e2413cea5d](https://linux-hardware.org/?probe=e2413cea5d) | Jul 06, 2019 |
| HP            | 250 G6 Notebook PC          | [7d8551e612](https://linux-hardware.org/?probe=7d8551e612) | Jun 29, 2019 |
| Lenovo        | G500 20236                  | [4faa6112c3](https://linux-hardware.org/?probe=4faa6112c3) | Jun 28, 2019 |
| HP            | Laptop 15-db0xxx            | [df6f074dbd](https://linux-hardware.org/?probe=df6f074dbd) | Jun 11, 2019 |
| IBM           | ThinkPad R52p 1847W5R       | [1dc1d8e6f2](https://linux-hardware.org/?probe=1dc1d8e6f2) | Jun 09, 2019 |
| HP            | Unknown                     | [cf3a7ad203](https://linux-hardware.org/?probe=cf3a7ad203) | Jun 05, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | [f1a85fe5ba](https://linux-hardware.org/?probe=f1a85fe5ba) | Jun 05, 2019 |
| HP            | Pavilion Notebook           | [ad610739b6](https://linux-hardware.org/?probe=ad610739b6) | Jun 01, 2019 |
| HP            | Pavilion Notebook           | [476f3cfb4a](https://linux-hardware.org/?probe=476f3cfb4a) | May 26, 2019 |
| Acer          | Aspire A717-71G             | [882e32aaf7](https://linux-hardware.org/?probe=882e32aaf7) | May 21, 2019 |
| Dell          | Inspiron 5567               | [29fadee02e](https://linux-hardware.org/?probe=29fadee02e) | May 19, 2019 |
| Lenovo        | V330-15IKB 81AX             | [8f1cfe4955](https://linux-hardware.org/?probe=8f1cfe4955) | May 17, 2019 |
| HP            | 250 G1                      | [4550b3fdf6](https://linux-hardware.org/?probe=4550b3fdf6) | May 17, 2019 |
| HP            | 250 G1                      | [7dda48b144](https://linux-hardware.org/?probe=7dda48b144) | May 17, 2019 |
| ASUSTek       | X541SA                      | [dff8b29714](https://linux-hardware.org/?probe=dff8b29714) | May 10, 2019 |
| ASUSTek       | X541SA                      | [308cc99aee](https://linux-hardware.org/?probe=308cc99aee) | May 10, 2019 |
| ASUSTek       | X541SA                      | [f03f0840fb](https://linux-hardware.org/?probe=f03f0840fb) | May 10, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [8195906a99](https://linux-hardware.org/?probe=8195906a99) | May 06, 2019 |
| Acer          | Aspire E1-530               | [e5658355fa](https://linux-hardware.org/?probe=e5658355fa) | May 03, 2019 |
| LG Electro... | LW70-JJKG                   | [76f306de39](https://linux-hardware.org/?probe=76f306de39) | Apr 27, 2019 |
| Dell          | G3 3779                     | [8407de048a](https://linux-hardware.org/?probe=8407de048a) | Apr 26, 2019 |
| Acer          | Aspire A717-71G             | [7385402cb8](https://linux-hardware.org/?probe=7385402cb8) | Apr 25, 2019 |
| ASUSTek       | X541NC                      | [50aeeec380](https://linux-hardware.org/?probe=50aeeec380) | Apr 19, 2019 |
| ASUSTek       | X541NC                      | [5278c50f95](https://linux-hardware.org/?probe=5278c50f95) | Apr 13, 2019 |
| Fujitsu Si... | AMILO PRO V3515             | [1d96b8f60d](https://linux-hardware.org/?probe=1d96b8f60d) | Apr 11, 2019 |
| ASUSTek       | X541NA                      | [b94a9e24c1](https://linux-hardware.org/?probe=b94a9e24c1) | Apr 07, 2019 |
| Toshiba       | Satellite C870-17H          | [dc2ce35421](https://linux-hardware.org/?probe=dc2ce35421) | Apr 06, 2019 |
| Acer          | Aspire A717-71G             | [600ac82384](https://linux-hardware.org/?probe=600ac82384) | Mar 30, 2019 |
| Acer          | Aspire 6935                 | [d8a5d80999](https://linux-hardware.org/?probe=d8a5d80999) | Mar 23, 2019 |
| Dell          | Inspiron N5110              | [5137b5b274](https://linux-hardware.org/?probe=5137b5b274) | Mar 21, 2019 |
| HP            | Pavilion dv5                | [3f857e2920](https://linux-hardware.org/?probe=3f857e2920) | Mar 18, 2019 |
| ASUSTek       | X550MD                      | [4e37ad043d](https://linux-hardware.org/?probe=4e37ad043d) | Mar 14, 2019 |
| Sony          | VGN-FE31Z                   | [860dcaf74d](https://linux-hardware.org/?probe=860dcaf74d) | Feb 16, 2019 |
| Dell          | Precision M4600             | [6f6a52607b](https://linux-hardware.org/?probe=6f6a52607b) | Feb 14, 2019 |
| ASUSTek       | X540LA                      | [03ab6a3cd8](https://linux-hardware.org/?probe=03ab6a3cd8) | Feb 11, 2019 |
| Acer          | Aspire A315-21              | [b28972ad25](https://linux-hardware.org/?probe=b28972ad25) | Feb 10, 2019 |
| MSI           | MS-16Y1                     | [a676d0126f](https://linux-hardware.org/?probe=a676d0126f) | Feb 07, 2019 |
| ASUSTek       | X540LA                      | [a7cb02a6fb](https://linux-hardware.org/?probe=a7cb02a6fb) | Feb 02, 2019 |
| ASUSTek       | X540LA                      | [18752af5af](https://linux-hardware.org/?probe=18752af5af) | Jan 31, 2019 |
| ASUSTek       | X540LA                      | [dea612f99d](https://linux-hardware.org/?probe=dea612f99d) | Jan 31, 2019 |
| ASUSTek       | X541NA                      | [d66eb82eac](https://linux-hardware.org/?probe=d66eb82eac) | Jan 23, 2019 |
| ASUSTek       | K55DR                       | [13a17add51](https://linux-hardware.org/?probe=13a17add51) | Jan 22, 2019 |
| Acer          | Aspire ES1-532G             | [af17a54207](https://linux-hardware.org/?probe=af17a54207) | Jan 12, 2019 |
| ASUSTek       | X541NA                      | [53fba97f8a](https://linux-hardware.org/?probe=53fba97f8a) | Jan 04, 2019 |
| ASUSTek       | X541NA                      | [a0cb966487](https://linux-hardware.org/?probe=a0cb966487) | Jan 04, 2019 |
| Acer          | Aspire A717-71G             | [c3edad77d8](https://linux-hardware.org/?probe=c3edad77d8) | Dec 24, 2018 |
| Acer          | Aspire A315-21              | [9289091c83](https://linux-hardware.org/?probe=9289091c83) | Nov 28, 2018 |
| Acer          | Aspire A717-71G             | [3c22bb7c43](https://linux-hardware.org/?probe=3c22bb7c43) | Nov 04, 2018 |
| Acer          | Aspire A717-71G             | [65968eaade](https://linux-hardware.org/?probe=65968eaade) | Nov 01, 2018 |
| HP            | 15                          | [a6c00a0fde](https://linux-hardware.org/?probe=a6c00a0fde) | Jul 08, 2018 |
| HP            | 250 G5 Notebook PC          | [24f9e4ee20](https://linux-hardware.org/?probe=24f9e4ee20) | Jun 24, 2018 |
| HP            | Pavilion dv7                | [566fa1aed1](https://linux-hardware.org/?probe=566fa1aed1) | Feb 24, 2018 |
| HP            | ProBook 650 G1              | [b0a5c81710](https://linux-hardware.org/?probe=b0a5c81710) | Jan 24, 2018 |
| HP            | 250 G5 Notebook PC          | [c939de9629](https://linux-hardware.org/?probe=c939de9629) | Dec 17, 2017 |
| Toshiba       | Satellite C50-A-1G3         | [4d2b35494b](https://linux-hardware.org/?probe=4d2b35494b) | Dec 16, 2017 |
| HP            | 15                          | [93985df093](https://linux-hardware.org/?probe=93985df093) | Sep 26, 2017 |
| Dell          | Inspiron 7520               | [3b5516e47b](https://linux-hardware.org/?probe=3b5516e47b) | Aug 27, 2017 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | [5ab0f522c2](https://linux-hardware.org/?probe=5ab0f522c2) | Aug 19, 2017 |
| Lenovo        | G560 20042                  | [6f5d9b39bb](https://linux-hardware.org/?probe=6f5d9b39bb) | May 09, 2017 |
| ASUSTek       | K55VD                       | [5fecb30529](https://linux-hardware.org/?probe=5fecb30529) | Jan 08, 2017 |
| ASUSTek       | K55VD                       | [f9af076683](https://linux-hardware.org/?probe=f9af076683) | Jan 07, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Serbia/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 43        | 10.51%  |
| Ubuntu 18.04                 | 29        | 7.09%   |
| Ubuntu 22.04                 | 21        | 5.13%   |
| OpenMandriva 4.3             | 11        | 2.69%   |
| Zorin 15                     | 9         | 2.2%    |
| BlackPanther 18.1            | 9         | 2.2%    |
| ROSA R11                     | 8         | 1.96%   |
| Pop!_OS 22.04                | 8         | 1.96%   |
| Arch                         | 8         | 1.96%   |
| Ubuntu 19.10                 | 7         | 1.71%   |
| OpenMandriva 23.01           | 7         | 1.71%   |
| Linux Mint 19.3              | 7         | 1.71%   |
| OpenMandriva 4.2             | 6         | 1.47%   |
| Linux Mint 20.3              | 6         | 1.47%   |
| Fedora 37                    | 6         | 1.47%   |
| Zorin 16                     | 5         | 1.22%   |
| Ubuntu 21.10                 | 5         | 1.22%   |
| Ubuntu 18.10                 | 5         | 1.22%   |
| ROSA R10                     | 5         | 1.22%   |
| KDE neon 20.04               | 5         | 1.22%   |
| ROSA R11.1                   | 4         | 0.98%   |
| Pop!_OS 21.04                | 4         | 0.98%   |
| openSUSE Tumbleweed-XXXXXXXX | 4         | 0.98%   |
| Linux Mint 21.1              | 4         | 0.98%   |
| Fedora 34                    | 4         | 0.98%   |
| ArcoLinux Rolling            | 4         | 0.98%   |
| Arch Rolling                 | 4         | 0.98%   |
| Xubuntu 20.04                | 3         | 0.73%   |
| Ubuntu 21.04                 | 3         | 0.73%   |
| Ubuntu 19.04                 | 3         | 0.73%   |
| ROSA R9                      | 3         | 0.73%   |
| ROSA 12.2                    | 3         | 0.73%   |
| MX 21                        | 3         | 0.73%   |
| Manjaro                      | 3         | 0.73%   |
| Linux Mint 21                | 3         | 0.73%   |
| Linux Mint 20.2              | 3         | 0.73%   |
| Linux Mint 20.1              | 3         | 0.73%   |
| Kubuntu 22.04                | 3         | 0.73%   |
| KDE neon 18.04               | 3         | 0.73%   |
| Fedora 36                    | 3         | 0.73%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 120       | 31.75%  |
| Endless       | 31        | 8.2%    |
| OpenMandriva  | 26        | 6.88%   |
| Linux Mint    | 26        | 6.88%   |
| ROSA          | 22        | 5.82%   |
| Fedora        | 21        | 5.56%   |
| Pop!_OS       | 16        | 4.23%   |
| Zorin         | 15        | 3.97%   |
| Manjaro       | 12        | 3.17%   |
| Arch          | 12        | 3.17%   |
| BlackPanther  | 10        | 2.65%   |
| KDE neon      | 8         | 2.12%   |
| Kubuntu       | 7         | 1.85%   |
| Xubuntu       | 6         | 1.59%   |
| openSUSE      | 5         | 1.32%   |
| Kali          | 5         | 1.32%   |
| ArcoLinux     | 4         | 1.06%   |
| Ubuntu MATE   | 3         | 0.79%   |
| MX            | 3         | 0.79%   |
| Lubuntu       | 3         | 0.79%   |
| Elementary    | 3         | 0.79%   |
| EndeavourOS   | 2         | 0.53%   |
| Debian        | 2         | 0.53%   |
| Void Linux    | 1         | 0.26%   |
| UbuntuDDE     | 1         | 0.26%   |
| Ubuntu Unity  | 1         | 0.26%   |
| Ubuntu Budgie | 1         | 0.26%   |
| Slackware     | 1         | 0.26%   |
| Peppermint    | 1         | 0.26%   |
| Nobara        | 1         | 0.26%   |
| LMDE          | 1         | 0.26%   |
| Linux Lite    | 1         | 0.26%   |
| GNOME OS      | 1         | 0.26%   |
| Generic       | 1         | 0.26%   |
| Garuda Linux  | 1         | 0.26%   |
| Devuan        | 1         | 0.26%   |
| Deepin        | 1         | 0.26%   |
| Clear Linux   | 1         | 0.26%   |
| CentOS        | 1         | 0.26%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003            | 11        | 2.51%   |
| 6.1.1-desktop-1omv2290             | 7         | 1.59%   |
| 5.8.0-14-generic                   | 7         | 1.59%   |
| 4.18.16-desktop-1bP                | 7         | 1.59%   |
| 5.3.0-40-generic                   | 6         | 1.37%   |
| 5.15.0-48-generic                  | 6         | 1.37%   |
| 5.10.14-desktop-1omv4002           | 6         | 1.37%   |
| 4.18.0-15-generic                  | 6         | 1.37%   |
| 5.15.0-56-generic                  | 5         | 1.14%   |
| 5.15.0-46-generic                  | 5         | 1.14%   |
| 5.11.0-27-generic                  | 5         | 1.14%   |
| 5.4.0-47-generic                   | 4         | 0.91%   |
| 5.4.0-42-generic                   | 4         | 0.91%   |
| 5.3.0-23-generic                   | 4         | 0.91%   |
| 5.15.0-58-generic                  | 4         | 0.91%   |
| 5.15.0-52-generic                  | 4         | 0.91%   |
| 4.18.0-25-generic                  | 4         | 0.91%   |
| 4.18.0-12-generic                  | 4         | 0.91%   |
| 4.15.0-15-generic                  | 4         | 0.91%   |
| 5.4.0-58-generic                   | 3         | 0.68%   |
| 5.4.0-52-generic                   | 3         | 0.68%   |
| 5.4.0-48-generic                   | 3         | 0.68%   |
| 5.4.0-19-generic                   | 3         | 0.68%   |
| 5.3.0-51-generic                   | 3         | 0.68%   |
| 5.3.0-29-generic                   | 3         | 0.68%   |
| 5.3.0-28-generic                   | 3         | 0.68%   |
| 5.15.0-40-generic                  | 3         | 0.68%   |
| 5.13.0-30-generic                  | 3         | 0.68%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 3         | 0.68%   |
| 5.0.0-31-generic                   | 3         | 0.68%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 3         | 0.68%   |
| 4.18.0-10-generic                  | 3         | 0.68%   |
| 4.15.0-desktop-45.1rosa-x86_64     | 3         | 0.68%   |
| 6.1.9-200.fc37.x86_64              | 2         | 0.46%   |
| 6.0.12-76060006-generic            | 2         | 0.46%   |
| 5.8.11-1-MANJARO                   | 2         | 0.46%   |
| 5.8.0-55-generic                   | 2         | 0.46%   |
| 5.8.0-48-generic                   | 2         | 0.46%   |
| 5.8.0-33-generic                   | 2         | 0.46%   |
| 5.6.14-desktop-2bP                 | 2         | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 54        | 13.01%  |
| 5.15.0  | 36        | 8.67%   |
| 4.15.0  | 29        | 6.99%   |
| 5.3.0   | 27        | 6.51%   |
| 4.18.0  | 22        | 5.3%    |
| 5.8.0   | 21        | 5.06%   |
| 5.11.0  | 21        | 5.06%   |
| 5.13.0  | 17        | 4.1%    |
| 5.0.0   | 17        | 4.1%    |
| 5.16.7  | 11        | 2.65%   |
| 6.1.1   | 8         | 1.93%   |
| 5.19.0  | 8         | 1.93%   |
| 5.10.0  | 7         | 1.69%   |
| 4.18.16 | 7         | 1.69%   |
| 5.10.14 | 6         | 1.45%   |
| 4.9.20  | 4         | 0.96%   |
| 5.8.11  | 3         | 0.72%   |
| 5.10.74 | 3         | 0.72%   |
| 6.2.9   | 2         | 0.48%   |
| 6.1.9   | 2         | 0.48%   |
| 6.1.8   | 2         | 0.48%   |
| 6.1.7   | 2         | 0.48%   |
| 6.0.12  | 2         | 0.48%   |
| 6.0.10  | 2         | 0.48%   |
| 5.6.14  | 2         | 0.48%   |
| 5.19.7  | 2         | 0.48%   |
| 5.18.10 | 2         | 0.48%   |
| 5.17.0  | 2         | 0.48%   |
| 5.16.0  | 2         | 0.48%   |
| 5.15.11 | 2         | 0.48%   |
| 5.12.9  | 2         | 0.48%   |
| 4.9.76  | 2         | 0.48%   |
| 4.13.0  | 2         | 0.48%   |
| 6.2.3   | 1         | 0.24%   |
| 6.1.21  | 1         | 0.24%   |
| 6.1.10  | 1         | 0.24%   |
| 6.1.0   | 1         | 0.24%   |
| 6.0.9   | 1         | 0.24%   |
| 6.0.8   | 1         | 0.24%   |
| 6.0.6   | 1         | 0.24%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 63        | 15.33%  |
| 5.15    | 46        | 11.19%  |
| 4.18    | 29        | 7.06%   |
| 4.15    | 29        | 7.06%   |
| 5.3     | 28        | 6.81%   |
| 5.11    | 27        | 6.57%   |
| 5.8     | 25        | 6.08%   |
| 5.10    | 21        | 5.11%   |
| 5.13    | 19        | 4.62%   |
| 5.0     | 19        | 4.62%   |
| 6.1     | 17        | 4.14%   |
| 5.16    | 15        | 3.65%   |
| 5.19    | 14        | 3.41%   |
| 4.9     | 11        | 2.68%   |
| 6.0     | 10        | 2.43%   |
| 5.18    | 5         | 1.22%   |
| 5.12    | 5         | 1.22%   |
| 5.6     | 4         | 0.97%   |
| 5.17    | 4         | 0.97%   |
| 6.2     | 3         | 0.73%   |
| 5.9     | 2         | 0.49%   |
| 5.7     | 2         | 0.49%   |
| 5.1     | 2         | 0.49%   |
| 4.19    | 2         | 0.49%   |
| 4.13    | 2         | 0.49%   |
| 4.1     | 2         | 0.49%   |
| 5.5     | 1         | 0.24%   |
| 5.14    | 1         | 0.24%   |
| 4.17    | 1         | 0.24%   |
| 4.12    | 1         | 0.24%   |
| 4.10    | 1         | 0.24%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 352       | 96.17%  |
| i686   | 14        | 3.83%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 158       | 41.04%  |
| KDE5            | 69        | 17.92%  |
| Unknown         | 55        | 14.29%  |
| XFCE            | 32        | 8.31%   |
| X-Cinnamon      | 20        | 5.19%   |
| KDE4            | 11        | 2.86%   |
| MATE            | 6         | 1.56%   |
| KDE             | 6         | 1.56%   |
| i3              | 6         | 1.56%   |
| Cinnamon        | 6         | 1.56%   |
| LXQt            | 4         | 1.04%   |
| Pantheon        | 3         | 0.78%   |
| qtile           | 2         | 0.52%   |
| Deepin          | 2         | 0.52%   |
| Unity           | 1         | 0.26%   |
| LXDE            | 1         | 0.26%   |
| GNOME Flashback | 1         | 0.26%   |
| DWM             | 1         | 0.26%   |
| Budgie          | 1         | 0.26%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 298       | 78.42%  |
| Wayland | 46        | 12.11%  |
| Unknown | 31        | 8.16%   |
| Tty     | 5         | 1.32%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 190       | 50.26%  |
| SDDM    | 62        | 16.4%   |
| GDM     | 37        | 9.79%   |
| GDM3    | 35        | 9.26%   |
| LightDM | 31        | 8.2%    |
| KDM     | 12        | 3.17%   |
| TDM     | 9         | 2.38%   |
| XDM     | 1         | 0.26%   |
| Ly      | 1         | 0.26%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 254       | 65.63%  |
| Unknown     | 75        | 19.38%  |
| sr_RS       | 18        | 4.65%   |
| sr_RS@latin | 13        | 3.36%   |
| en_GB       | 10        | 2.58%   |
| C           | 5         | 1.29%   |
| ru_RU       | 3         | 0.78%   |
| hu_HU       | 3         | 0.78%   |
| de_DE       | 3         | 0.78%   |
| hr_HR       | 1         | 0.26%   |
| en_IE       | 1         | 0.26%   |
| en_AU       | 1         | 0.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 206       | 55.38%  |
| BIOS | 166       | 44.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 286       | 75.66%  |
| Overlay | 39        | 10.32%  |
| Unknown | 26        | 6.88%   |
| Btrfs   | 22        | 5.82%   |
| Zfs     | 2         | 0.53%   |
| Tmpfs   | 2         | 0.53%   |
| Xfs     | 1         | 0.26%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 198       | 52.52%  |
| GPT     | 120       | 31.83%  |
| MBR     | 59        | 15.65%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 323       | 87.3%   |
| Yes       | 47        | 12.7%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 275       | 73.92%  |
| Yes       | 97        | 26.08%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 98        | 26.92%  |
| Hewlett-Packard     | 64        | 17.58%  |
| ASUSTek Computer    | 57        | 15.66%  |
| Dell                | 50        | 13.74%  |
| Acer                | 36        | 9.89%   |
| Toshiba             | 13        | 3.57%   |
| Apple               | 8         | 2.2%    |
| MSI                 | 6         | 1.65%   |
| Fujitsu Siemens     | 6         | 1.65%   |
| Sony                | 4         | 1.1%    |
| Fujitsu             | 3         | 0.82%   |
| Timi                | 2         | 0.55%   |
| Samsung Electronics | 2         | 0.55%   |
| Medion              | 2         | 0.55%   |
| LG Electronics      | 2         | 0.55%   |
| HUAWEI              | 2         | 0.55%   |
| eMachines           | 2         | 0.55%   |
| TWC                 | 1         | 0.27%   |
| Razer               | 1         | 0.27%   |
| Packard Bell        | 1         | 0.27%   |
| IBM                 | 1         | 0.27%   |
| HONOR               | 1         | 0.27%   |
| Gigabyte Technology | 1         | 0.27%   |
| BenQ                | 1         | 0.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Acer Aspire A315-31                        | 6         | 1.65%   |
| HP Notebook                                | 5         | 1.37%   |
| Lenovo V330-15IKB 81AX                     | 4         | 1.1%    |
| Lenovo IdeaPad 5 14ARE05 81YM              | 3         | 0.82%   |
| Lenovo IdeaPad 330-15IKB 81DE              | 3         | 0.82%   |
| Lenovo IdeaPad 3 15IIL05 81WE              | 3         | 0.82%   |
| HP 250 G5 Notebook PC                      | 3         | 0.82%   |
| Dell Inspiron 3593                         | 3         | 0.82%   |
| ASUS X541NA                                | 3         | 0.82%   |
| Unknown                                    | 3         | 0.82%   |
| MSI CR500                                  | 2         | 0.55%   |
| Lenovo Legion Y530-15ICH 81FV              | 2         | 0.55%   |
| Lenovo IdeaPad S540-14API 81NH             | 2         | 0.55%   |
| Lenovo IdeaPad L340-15API 81LW             | 2         | 0.55%   |
| Lenovo IdeaPad 5 14ALC05 82LM              | 2         | 0.55%   |
| Lenovo IdeaPad 110-15IBR 80T7              | 2         | 0.55%   |
| Lenovo G500 20236                          | 2         | 0.55%   |
| Lenovo B50-45 20388                        | 2         | 0.55%   |
| HP Pavilion Notebook                       | 2         | 0.55%   |
| HP Pavilion dv7                            | 2         | 0.55%   |
| HP Laptop 15-ra0xx                         | 2         | 0.55%   |
| HP Laptop 15-db1xxx                        | 2         | 0.55%   |
| HP Laptop 15-db0xxx                        | 2         | 0.55%   |
| HP G62                                     | 2         | 0.55%   |
| Fujitsu Siemens AMILO Li3710               | 2         | 0.55%   |
| Dell Vostro 3500                           | 2         | 0.55%   |
| Dell Vostro 15 3515                        | 2         | 0.55%   |
| Dell Latitude E5470                        | 2         | 0.55%   |
| Dell Latitude 7490                         | 2         | 0.55%   |
| Dell Inspiron 3558                         | 2         | 0.55%   |
| Dell Inspiron 3542                         | 2         | 0.55%   |
| Dell Inspiron 3537                         | 2         | 0.55%   |
| ASUS X55A                                  | 2         | 0.55%   |
| ASUS X541NC                                | 2         | 0.55%   |
| ASUS VivoBook_ASUSLaptop X580GD_N580GD     | 2         | 0.55%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X543MA | 2         | 0.55%   |
| ASUS K54C                                  | 2         | 0.55%   |
| Apple MacBookPro8,1                        | 2         | 0.55%   |
| Acer Aspire V3-571G                        | 2         | 0.55%   |
| Acer Aspire A315-51                        | 2         | 0.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo IdeaPad        | 35        | 9.62%   |
| Lenovo ThinkPad       | 33        | 9.07%   |
| Acer Aspire           | 32        | 8.79%   |
| Dell Inspiron         | 25        | 6.87%   |
| ASUS VivoBook         | 16        | 4.4%    |
| HP Laptop             | 14        | 3.85%   |
| Toshiba Satellite     | 11        | 3.02%   |
| Dell Latitude         | 11        | 3.02%   |
| HP ProBook            | 10        | 2.75%   |
| HP Pavilion           | 8         | 2.2%    |
| Lenovo Legion         | 6         | 1.65%   |
| HP EliteBook          | 6         | 1.65%   |
| HP 250                | 6         | 1.65%   |
| Dell Vostro           | 6         | 1.65%   |
| HP Notebook           | 5         | 1.37%   |
| Fujitsu Siemens AMILO | 5         | 1.37%   |
| Lenovo V330-15IKB     | 4         | 1.1%    |
| Dell Precision        | 4         | 1.1%    |
| Lenovo ThinkBook      | 3         | 0.82%   |
| HP Compaq             | 3         | 0.82%   |
| Fujitsu LIFEBOOK      | 3         | 0.82%   |
| ASUS ZenBook          | 3         | 0.82%   |
| ASUS X541NA           | 3         | 0.82%   |
| Apple MacBookPro8     | 3         | 0.82%   |
| Unknown               | 3         | 0.82%   |
| MSI CR500             | 2         | 0.55%   |
| Lenovo G500           | 2         | 0.55%   |
| Lenovo B50-45         | 2         | 0.55%   |
| HP OMEN               | 2         | 0.55%   |
| HP G62                | 2         | 0.55%   |
| Dell XPS              | 2         | 0.55%   |
| ASUS X55A             | 2         | 0.55%   |
| ASUS X541NC           | 2         | 0.55%   |
| ASUS TUF              | 2         | 0.55%   |
| ASUS K54C             | 2         | 0.55%   |
| Apple MacBookPro5     | 2         | 0.55%   |
| Acer Nitro            | 2         | 0.55%   |
| Toshiba TECRA         | 1         | 0.27%   |
| Toshiba QOSMIO        | 1         | 0.27%   |
| Timi TM1613           | 1         | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 40        | 10.99%  |
| 2020 | 35        | 9.62%   |
| 2019 | 32        | 8.79%   |
| 2011 | 31        | 8.52%   |
| 2017 | 30        | 8.24%   |
| 2016 | 27        | 7.42%   |
| 2012 | 23        | 6.32%   |
| 2013 | 22        | 6.04%   |
| 2010 | 21        | 5.77%   |
| 2014 | 18        | 4.95%   |
| 2021 | 17        | 4.67%   |
| 2015 | 16        | 4.4%    |
| 2008 | 16        | 4.4%    |
| 2009 | 11        | 3.02%   |
| 2022 | 10        | 2.75%   |
| 2007 | 7         | 1.92%   |
| 2006 | 6         | 1.65%   |
| 2005 | 2         | 0.55%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 364       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 335       | 90.54%  |
| Enabled  | 35        | 9.46%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 364       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 110       | 29.57%  |
| 4.01-8.0    | 96        | 25.81%  |
| 8.01-16.0   | 67        | 18.01%  |
| 16.01-24.0  | 50        | 13.44%  |
| 1.01-2.0    | 19        | 5.11%   |
| 32.01-64.0  | 14        | 3.76%   |
| 2.01-3.0    | 10        | 2.69%   |
| 24.01-32.0  | 4         | 1.08%   |
| 64.01-256.0 | 1         | 0.27%   |
| 0.51-1.0    | 1         | 0.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 144       | 35.38%  |
| 2.01-3.0   | 94        | 23.1%   |
| 3.01-4.0   | 55        | 13.51%  |
| 0.51-1.0   | 50        | 12.29%  |
| 4.01-8.0   | 45        | 11.06%  |
| 8.01-16.0  | 17        | 4.18%   |
| 16.01-24.0 | 1         | 0.25%   |
| 0.01-0.5   | 1         | 0.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 285       | 76%     |
| 2      | 75        | 20%     |
| 0      | 8         | 2.13%   |
| 3      | 7         | 1.87%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 213       | 57.88%  |
| Yes       | 155       | 42.12%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 313       | 85.99%  |
| No        | 51        | 14.01%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 364       | 99.73%  |
| No        | 1         | 0.27%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 298       | 80.98%  |
| No        | 70        | 19.02%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Serbia  | 364       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Belgrade          | 231       | 59.23%  |
| Novi Sad          | 39        | 10%     |
| Niš              | 24        | 6.15%   |
| Subotica          | 7         | 1.79%   |
| Zrenjanin         | 5         | 1.28%   |
| Leskovac          | 5         | 1.28%   |
| Savski Venac      | 4         | 1.03%   |
| Pančevo          | 4         | 1.03%   |
| Novi Belgrade     | 4         | 1.03%   |
| Senta             | 3         | 0.77%   |
| Novi Karlovci     | 3         | 0.77%   |
| Lozovik           | 3         | 0.77%   |
| Kovin             | 3         | 0.77%   |
| Jagodina          | 3         | 0.77%   |
| Backa Topola      | 3         | 0.77%   |
| Varvarin          | 2         | 0.51%   |
| Trstenik          | 2         | 0.51%   |
| Sabac             | 2         | 0.51%   |
| Mladenovac        | 2         | 0.51%   |
| Lazarevac         | 2         | 0.51%   |
| Kragujevac        | 2         | 0.51%   |
| Branicevo         | 2         | 0.51%   |
| Bor               | 2         | 0.51%   |
| Becej             | 2         | 0.51%   |
| Vranje            | 1         | 0.26%   |
| Valjevo           | 1         | 0.26%   |
| Užice            | 1         | 0.26%   |
| UÅ¾ice          | 1         | 0.26%   |
| Stara Pazova      | 1         | 0.26%   |
| Sremska Mitrovica | 1         | 0.26%   |
| Semlin            | 1         | 0.26%   |
| Ruma              | 1         | 0.26%   |
| Ripanj            | 1         | 0.26%   |
| Pukovac           | 1         | 0.26%   |
| Požarevac        | 1         | 0.26%   |
| Pirot             | 1         | 0.26%   |
| Palanka           | 1         | 0.26%   |
| Novi Knezevac     | 1         | 0.26%   |
| New Belgrade      | 1         | 0.26%   |
| Kruševac         | 1         | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 58        | 82     | 13.62%  |
| Seagate                     | 53        | 63     | 12.44%  |
| Samsung Electronics         | 53        | 65     | 12.44%  |
| Toshiba                     | 50        | 64     | 11.74%  |
| Kingston                    | 27        | 31     | 6.34%   |
| SK hynix                    | 21        | 25     | 4.93%   |
| Hitachi                     | 20        | 21     | 4.69%   |
| SanDisk                     | 17        | 24     | 3.99%   |
| Intel                       | 17        | 26     | 3.99%   |
| Micron Technology           | 15        | 17     | 3.52%   |
| HGST                        | 13        | 22     | 3.05%   |
| Unknown                     | 11        | 15     | 2.58%   |
| Patriot                     | 10        | 13     | 2.35%   |
| SPCC                        | 7         | 11     | 1.64%   |
| KIOXIA                      | 5         | 6      | 1.17%   |
| Fujitsu                     | 5         | 5      | 1.17%   |
| A-DATA Technology           | 5         | 5      | 1.17%   |
| Gigabyte Technology         | 4         | 4      | 0.94%   |
| GeIL                        | 4         | 4      | 0.94%   |
| Transcend                   | 3         | 3      | 0.7%    |
| Crucial                     | 3         | 5      | 0.7%    |
| Union Memory                | 2         | 2      | 0.47%   |
| Phison                      | 2         | 3      | 0.47%   |
| LITEON                      | 2         | 3      | 0.47%   |
| Kingston Technology Company | 2         | 2      | 0.47%   |
| Biostar                     | 2         | 2      | 0.47%   |
| AMD                         | 2         | 2      | 0.47%   |
| Unknown                     | 2         | 2      | 0.47%   |
| Verbatim                    | 1         | 1      | 0.23%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.23%   |
| SSSTC                       | 1         | 1      | 0.23%   |
| Solid State Storage         | 1         | 1      | 0.23%   |
| Realtek Semiconductor       | 1         | 4      | 0.23%   |
| PNY                         | 1         | 1      | 0.23%   |
| Netac                       | 1         | 1      | 0.23%   |
| JMicron Technology          | 1         | 1      | 0.23%   |
| IBM/Hitachi                 | 1         | 1      | 0.23%   |
| HUAWEI                      | 1         | 1      | 0.23%   |
| ADATA Technology            | 1         | 1      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 970GB        | 18        | 4.17%   |
| Toshiba MQ01ABF050 500GB                | 13        | 3.01%   |
| Seagate ST500LT012-1DG142 500GB         | 8         | 1.85%   |
| Kingston SA400S37240G 240GB SSD         | 7         | 1.62%   |
| Toshiba MQ04ABF100 1TB                  | 5         | 1.16%   |
| Toshiba MQ01ABD100 1TB                  | 5         | 1.16%   |
| Seagate ST500LT012-9WS142 500GB         | 5         | 1.16%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 5         | 1.16%   |
| Samsung NVMe SSD Drive 256GB            | 5         | 1.16%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB    | 4         | 0.93%   |
| Samsung MZALQ512HALU-000L2 512GB        | 4         | 0.93%   |
| Kingston SA400S37480G 480GB SSD         | 4         | 0.93%   |
| Kingston SA400S37120G 120GB SSD         | 4         | 0.93%   |
| Hitachi HTS545050A7E380 500GB           | 4         | 0.93%   |
| WDC WD5000LPCX-24VHAT0 500GB            | 3         | 0.69%   |
| WDC WD3200BEVT-22ZCT0 320GB             | 3         | 0.69%   |
| SK hynix NVMe SSD Drive 256GB           | 3         | 0.69%   |
| SanDisk NVMe SSD Drive 256GB            | 3         | 0.69%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD     | 3         | 0.69%   |
| Kingston RBUSC180DS37256GJ 256GB SSD    | 3         | 0.69%   |
| Hitachi HTS545032B9A300 320GB           | 3         | 0.69%   |
| HGST HTS721010A9E630 1TB                | 3         | 0.69%   |
| HGST HTS545050A7E680 500GB              | 3         | 0.69%   |
| GeIL R3_128GB                           | 3         | 0.69%   |
| WDC WD5000LPVX-75V0TT0 500GB            | 2         | 0.46%   |
| WDC WD5000LPCX-80VHAT1 500GB            | 2         | 0.46%   |
| WDC WD5000LPCX-60VHAT0 500GB            | 2         | 0.46%   |
| WDC WD3200BEVT-22A23T0 320GB            | 2         | 0.46%   |
| WDC WD2500BEVS-22UST0 250GB             | 2         | 0.46%   |
| WDC WD1200BEVS-22UST0 120GB             | 2         | 0.46%   |
| WDC WD10SPZX-24Z10 1TB                  | 2         | 0.46%   |
| WDC WD10SPZX-21Z10T0 1TB                | 2         | 0.46%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB    | 2         | 0.46%   |
| Unknown MMC Card  64GB                  | 2         | 0.46%   |
| Unknown MMC Card  32GB                  | 2         | 0.46%   |
| Union Memory UMIS RPJTJ512MEE1OWX 512GB | 2         | 0.46%   |
| Toshiba NVMe SSD Drive 512GB            | 2         | 0.46%   |
| Toshiba NVMe SSD Drive 256GB            | 2         | 0.46%   |
| Toshiba MQ01ABD050 500GB                | 2         | 0.46%   |
| Toshiba MK1637GSX 160GB                 | 2         | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 53        | 63     | 29.28%  |
| WDC                 | 44        | 66     | 24.31%  |
| Toshiba             | 42        | 53     | 23.2%   |
| Hitachi             | 20        | 21     | 11.05%  |
| HGST                | 13        | 22     | 7.18%   |
| Fujitsu             | 5         | 5      | 2.76%   |
| Unknown             | 1         | 1      | 0.55%   |
| Samsung Electronics | 1         | 2      | 0.55%   |
| JMicron Technology  | 1         | 1      | 0.55%   |
| IBM/Hitachi         | 1         | 1      | 0.55%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 26        | 32     | 21.31%  |
| Kingston            | 24        | 27     | 19.67%  |
| Patriot             | 10        | 13     | 8.2%    |
| SanDisk             | 8         | 12     | 6.56%   |
| SPCC                | 7         | 11     | 5.74%   |
| Micron Technology   | 5         | 5      | 4.1%    |
| Intel               | 5         | 6      | 4.1%    |
| Toshiba             | 4         | 5      | 3.28%   |
| GeIL                | 4         | 4      | 3.28%   |
| A-DATA Technology   | 4         | 4      | 3.28%   |
| WDC                 | 3         | 4      | 2.46%   |
| Transcend           | 3         | 3      | 2.46%   |
| SK hynix            | 3         | 3      | 2.46%   |
| Crucial             | 3         | 5      | 2.46%   |
| LITEON              | 2         | 3      | 1.64%   |
| Gigabyte Technology | 2         | 2      | 1.64%   |
| Biostar             | 2         | 2      | 1.64%   |
| AMD                 | 2         | 2      | 1.64%   |
| Verbatim            | 1         | 1      | 0.82%   |
| SSSTC               | 1         | 1      | 0.82%   |
| PNY                 | 1         | 1      | 0.82%   |
| Netac               | 1         | 1      | 0.82%   |
| Unknown             | 1         | 1      | 0.82%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 181       | 235    | 43.83%  |
| SSD     | 113       | 148    | 27.36%  |
| NVMe    | 108       | 143    | 26.15%  |
| MMC     | 10        | 14     | 2.42%   |
| Unknown | 1         | 1      | 0.24%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 262       | 379    | 68.05%  |
| NVMe | 108       | 143    | 28.05%  |
| MMC  | 10        | 14     | 2.6%    |
| SAS  | 5         | 5      | 1.3%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 208       | 274    | 73.76%  |
| 0.51-1.0   | 70        | 98     | 24.82%  |
| 1.01-2.0   | 4         | 11     | 1.42%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 113       | 28.61%  |
| 101-250        | 110       | 27.85%  |
| 501-1000       | 49        | 12.41%  |
| 1-20           | 39        | 9.87%   |
| 51-100         | 27        | 6.84%   |
| 21-50          | 20        | 5.06%   |
| Unknown        | 15        | 3.8%    |
| 1001-2000      | 12        | 3.04%   |
| 2001-3000      | 8         | 2.03%   |
| More than 3000 | 2         | 0.51%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 162       | 39.9%   |
| 21-50     | 77        | 18.97%  |
| 101-250   | 59        | 14.53%  |
| 51-100    | 50        | 12.32%  |
| 251-500   | 27        | 6.65%   |
| Unknown   | 15        | 3.69%   |
| 501-1000  | 11        | 2.71%   |
| 1001-2000 | 5         | 1.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Notebooks | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABF050 500GB                | 3         | 3      | 10%     |
| Seagate ST1000LM035-1RK172 970GB        | 2         | 2      | 6.67%   |
| Hitachi HTS545050A7E380 500GB           | 2         | 2      | 6.67%   |
| HGST HTS725050A7E630 500GB              | 2         | 6      | 6.67%   |
| WDC WD5000BEVT-24A0RT0 500GB            | 1         | 1      | 3.33%   |
| WDC WD3200BEVT-22ZCT0 320GB             | 1         | 1      | 3.33%   |
| Toshiba MQ01ABD032 320GB                | 1         | 1      | 3.33%   |
| Toshiba MK5061GSYN 500GB                | 1         | 1      | 3.33%   |
| Toshiba MK1652GSX 160GB                 | 1         | 1      | 3.33%   |
| Toshiba MK1637GSX 160GB                 | 1         | 1      | 3.33%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD | 1         | 1      | 3.33%   |
| SPCC Solid State DiskB27 32GB           | 1         | 1      | 3.33%   |
| Seagate ST980813AS 80GB                 | 1         | 1      | 3.33%   |
| Seagate ST9250827AS 250GB               | 1         | 1      | 3.33%   |
| Seagate ST9120822AS 120GB               | 1         | 1      | 3.33%   |
| Seagate ST750LM022 HN-M750MBB 752GB     | 1         | 1      | 3.33%   |
| Seagate ST500LT012-9WS142 500GB         | 1         | 1      | 3.33%   |
| Seagate ST500LT012-1DG142 500GB         | 1         | 2      | 3.33%   |
| Samsung Electronics HM120JI 120GB       | 1         | 2      | 3.33%   |
| Kingston SA400S37480G 480GB SSD         | 1         | 1      | 3.33%   |
| Hitachi HTS722080K9A300 80GB            | 1         | 1      | 3.33%   |
| Hitachi HTS541612J9SA00 120GB           | 1         | 1      | 3.33%   |
| HGST HTS721010A9E630 1TB                | 1         | 2      | 3.33%   |
| Fujitsu MHZ2160BH G1 160GB              | 1         | 1      | 3.33%   |
| Fujitsu MHW2160BH PL 160GB              | 1         | 1      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 8         | 8      | 26.67%  |
| Seagate             | 8         | 9      | 26.67%  |
| Hitachi             | 4         | 4      | 13.33%  |
| HGST                | 3         | 8      | 10%     |
| WDC                 | 2         | 2      | 6.67%   |
| Fujitsu             | 2         | 2      | 6.67%   |
| SPCC                | 1         | 1      | 3.33%   |
| Samsung Electronics | 1         | 2      | 3.33%   |
| Kingston            | 1         | 1      | 3.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 9      | 29.63%  |
| Toshiba             | 7         | 7      | 25.93%  |
| Hitachi             | 4         | 4      | 14.81%  |
| HGST                | 3         | 8      | 11.11%  |
| WDC                 | 2         | 2      | 7.41%   |
| Fujitsu             | 2         | 2      | 7.41%   |
| Samsung Electronics | 1         | 2      | 3.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 27        | 34     | 90%     |
| SSD  | 3         | 3      | 10%     |

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
| Detected | 210       | 334    | 55.41%  |
| Works    | 139       | 170    | 36.68%  |
| Malfunc  | 30        | 37     | 7.92%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 271       | 62.59%  |
| AMD                            | 47        | 10.85%  |
| Samsung Electronics            | 31        | 7.16%   |
| SanDisk                        | 20        | 4.62%   |
| SK hynix                       | 18        | 4.16%   |
| Micron Technology              | 10        | 2.31%   |
| Nvidia                         | 6         | 1.39%   |
| Toshiba America Info Systems   | 5         | 1.15%   |
| KIOXIA                         | 5         | 1.15%   |
| Kingston Technology Company    | 5         | 1.15%   |
| Phison Electronics             | 4         | 0.92%   |
| Union Memory (Shenzhen)        | 3         | 0.69%   |
| ADATA Technology               | 2         | 0.46%   |
| VIA Technologies               | 1         | 0.23%   |
| Solid State Storage Technology | 1         | 0.23%   |
| Silicon Image                  | 1         | 0.23%   |
| Realtek Semiconductor          | 1         | 0.23%   |
| JMicron Technology             | 1         | 0.23%   |
| ASMedia Technology             | 1         | 0.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 38        | 8.15%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 32        | 6.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 27        | 5.79%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 26        | 5.58%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 21        | 4.51%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 13        | 2.79%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 12        | 2.58%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 12        | 2.58%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 12        | 2.58%   |
| Samsung NVMe SSD Controller 980                                                  | 10        | 2.15%   |
| Micron NVMe Storage Controller                                                   | 10        | 2.15%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 10        | 2.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 9         | 1.93%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 9         | 1.93%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 9         | 1.93%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 9         | 1.93%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 8         | 1.72%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 8         | 1.72%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 7         | 1.5%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 7         | 1.5%    |
| SK hynix BC511                                                                   | 6         | 1.29%   |
| SanDisk NVMe Controller                                                          | 6         | 1.29%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 6         | 1.29%   |
| Intel Volume Management Device NVMe RAID Controller                              | 6         | 1.29%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 1.29%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 6         | 1.29%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 6         | 1.29%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 5         | 1.07%   |
| Nvidia MCP79 AHCI Controller                                                     | 5         | 1.07%   |
| Intel Tiger Lake-LP SATA Controller                                              | 5         | 1.07%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 5         | 1.07%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 5         | 1.07%   |
| SK hynix Non-Volatile memory controller                                          | 4         | 0.86%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 4         | 0.86%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 4         | 0.86%   |
| Intel SSD 660P Series                                                            | 4         | 0.86%   |
| Intel Non-Volatile memory controller                                             | 4         | 0.86%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 4         | 0.86%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 0.86%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 3         | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 279       | 61.73%  |
| NVMe | 112       | 24.78%  |
| IDE  | 31        | 6.86%   |
| RAID | 30        | 6.64%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 297       | 81.59%  |
| AMD    | 67        | 18.41%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 8         | 2.2%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 7         | 1.92%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 6         | 1.65%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 6         | 1.65%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 6         | 1.65%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 5         | 1.37%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 1.37%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 5         | 1.37%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.37%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 5         | 1.37%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 5         | 1.37%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 1.37%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 4         | 1.1%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 4         | 1.1%    |
| Intel Core i3-7020U CPU @ 2.30GHz             | 4         | 1.1%    |
| Intel Celeron CPU N3060 @ 1.60GHz             | 4         | 1.1%    |
| Intel Celeron CPU 1000M @ 1.80GHz             | 4         | 1.1%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 1.1%    |
| AMD Ryzen 5 4500U with Radeon Graphics        | 4         | 1.1%    |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 4         | 1.1%    |
| Intel Pentium M processor 1.86GHz             | 3         | 0.82%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 3         | 0.82%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 0.82%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 0.82%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 3         | 0.82%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 0.82%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 3         | 0.82%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 0.82%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 3         | 0.82%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 3         | 0.82%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 3         | 0.82%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 3         | 0.82%   |
| Intel Core 2 CPU T5600 @ 1.83GHz              | 3         | 0.82%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 3         | 0.82%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 0.82%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 0.82%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 3         | 0.82%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 3         | 0.82%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics   | 3         | 0.82%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 2         | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 73        | 20.05%  |
| Intel Core i5           | 67        | 18.41%  |
| Intel Core i3           | 38        | 10.44%  |
| Intel Celeron           | 33        | 9.07%   |
| Intel Pentium           | 28        | 7.69%   |
| AMD Ryzen 5             | 24        | 6.59%   |
| Intel Core 2 Duo        | 17        | 4.67%   |
| Other                   | 15        | 4.12%   |
| AMD Ryzen 7             | 14        | 3.85%   |
| Intel Atom              | 7         | 1.92%   |
| Intel Core 2            | 4         | 1.1%    |
| AMD Ryzen 3             | 4         | 1.1%    |
| AMD A8                  | 4         | 1.1%    |
| Intel Pentium M         | 3         | 0.82%   |
| Intel Pentium Dual-Core | 3         | 0.82%   |
| Intel Pentium Dual      | 3         | 0.82%   |
| Intel Pentium Silver    | 2         | 0.55%   |
| Intel Genuine           | 2         | 0.55%   |
| AMD Ryzen 9             | 2         | 0.55%   |
| AMD Phenom II           | 2         | 0.55%   |
| AMD Athlon X2           | 2         | 0.55%   |
| AMD Athlon II Dual-Core | 2         | 0.55%   |
| AMD Athlon II           | 2         | 0.55%   |
| AMD A4                  | 2         | 0.55%   |
| Intel Pentium Gold      | 1         | 0.27%   |
| Intel Core M            | 1         | 0.27%   |
| Intel Core Duo          | 1         | 0.27%   |
| Intel Celeron M         | 1         | 0.27%   |
| AMD V120                | 1         | 0.27%   |
| AMD Turion 64 X2 Mobile | 1         | 0.27%   |
| AMD Ryzen 7 PRO         | 1         | 0.27%   |
| AMD Ryzen 5 PRO         | 1         | 0.27%   |
| AMD E2                  | 1         | 0.27%   |
| AMD E1                  | 1         | 0.27%   |
| AMD A6                  | 1         | 0.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 184       | 50.55%  |
| 4      | 126       | 34.62%  |
| 6      | 25        | 6.87%   |
| 1      | 15        | 4.12%   |
| 8      | 11        | 3.02%   |
| 14     | 2         | 0.55%   |
| 16     | 1         | 0.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 364       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 239       | 65.66%  |
| 1      | 125       | 34.34%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 345       | 94.52%  |
| Unknown        | 11        | 3.01%   |
| 32-bit         | 9         | 2.47%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 59        | 15.61%  |
| 0x206a7    | 32        | 8.47%   |
| 0x306a9    | 18        | 4.76%   |
| 0x406e3    | 17        | 4.5%    |
| 0x806ea    | 16        | 4.23%   |
| 0x506c9    | 12        | 3.17%   |
| 0x906ea    | 10        | 2.65%   |
| 0x706e5    | 10        | 2.65%   |
| 0x1067a    | 10        | 2.65%   |
| 0x806e9    | 9         | 2.38%   |
| 0x306d4    | 9         | 2.38%   |
| 0x806ec    | 8         | 2.12%   |
| 0x40651    | 8         | 2.12%   |
| 0x806c1    | 7         | 1.85%   |
| 0x6fd      | 7         | 1.85%   |
| 0x306c3    | 7         | 1.85%   |
| 0x08108102 | 7         | 1.85%   |
| 0x906e9    | 6         | 1.59%   |
| 0x806eb    | 6         | 1.59%   |
| 0x506e3    | 6         | 1.59%   |
| 0x406c4    | 6         | 1.59%   |
| 0x30678    | 6         | 1.59%   |
| 0x08600106 | 6         | 1.59%   |
| 0x08108109 | 6         | 1.59%   |
| 0xa0652    | 5         | 1.32%   |
| 0x20655    | 5         | 1.32%   |
| 0x10676    | 5         | 1.32%   |
| 0x08608103 | 5         | 1.32%   |
| 0x20652    | 4         | 1.06%   |
| 0x0a50000c | 4         | 1.06%   |
| 0x706a8    | 3         | 0.79%   |
| 0x706a1    | 3         | 0.79%   |
| 0x6d8      | 3         | 0.79%   |
| 0x406c3    | 3         | 0.79%   |
| 0x30673    | 3         | 0.79%   |
| 0x106ca    | 3         | 0.79%   |
| 0x0810100b | 3         | 0.79%   |
| 0x07030104 | 3         | 0.79%   |
| 0x010000c8 | 3         | 0.79%   |
| 0x906a3    | 2         | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 60        | 16.48%  |
| SandyBridge      | 37        | 10.16%  |
| Skylake          | 24        | 6.59%   |
| IvyBridge        | 20        | 5.49%   |
| Haswell          | 20        | 5.49%   |
| Silvermont       | 19        | 5.22%   |
| Zen+             | 15        | 4.12%   |
| Penryn           | 15        | 4.12%   |
| Core             | 14        | 3.85%   |
| Westmere         | 13        | 3.57%   |
| Goldmont         | 13        | 3.57%   |
| IceLake          | 12        | 3.3%    |
| Broadwell        | 12        | 3.3%    |
| TigerLake        | 11        | 3.02%   |
| Zen 2            | 10        | 2.75%   |
| Unknown          | 8         | 2.2%    |
| Zen 3            | 7         | 1.92%   |
| Zen              | 7         | 1.92%   |
| P6               | 7         | 1.92%   |
| K10              | 7         | 1.92%   |
| Goldmont plus    | 6         | 1.65%   |
| CometLake        | 6         | 1.65%   |
| Bonnell          | 5         | 1.37%   |
| Puma             | 4         | 1.1%    |
| Excavator        | 3         | 0.82%   |
| Alderlake Hybrid | 3         | 0.82%   |
| Piledriver       | 2         | 0.55%   |
| K8 & K10 hybrid  | 2         | 0.55%   |
| K8 Hammer        | 1         | 0.27%   |
| Jaguar           | 1         | 0.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 267       | 56.09%  |
| Nvidia           | 104       | 21.85%  |
| AMD              | 104       | 21.85%  |
| VIA Technologies | 1         | 0.21%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 34        | 6.87%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 20        | 4.04%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 16        | 3.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 16        | 3.23%   |
| Intel UHD Graphics 620                                                                   | 12        | 2.42%   |
| Intel HD Graphics 620                                                                    | 12        | 2.42%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 2.42%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 11        | 2.22%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 11        | 2.22%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 10        | 2.02%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 2.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 10        | 2.02%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 10        | 2.02%   |
| AMD Renoir                                                                               | 10        | 2.02%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 1.82%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 9         | 1.82%   |
| Intel HD Graphics 5500                                                                   | 9         | 1.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 1.82%   |
| Intel HD Graphics 500                                                                    | 8         | 1.62%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 1.62%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 8         | 1.62%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 7         | 1.41%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 7         | 1.41%   |
| AMD Lucienne                                                                             | 7         | 1.41%   |
| Intel HD Graphics 530                                                                    | 6         | 1.21%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 6         | 1.21%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 1.01%   |
| Intel HD Graphics 630                                                                    | 5         | 1.01%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 1.01%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 5         | 1.01%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5         | 1.01%   |
| Nvidia GP108M [GeForce MX230]                                                            | 4         | 0.81%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 0.81%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 4         | 0.81%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 0.81%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 0.81%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.61%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 0.61%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 3         | 0.61%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 164       | 44.81%  |
| Intel + Nvidia | 78        | 21.31%  |
| 1 x AMD        | 62        | 16.94%  |
| Intel + AMD    | 27        | 7.38%   |
| 1 x Nvidia     | 17        | 4.64%   |
| 2 x AMD        | 8         | 2.19%   |
| AMD + Nvidia   | 7         | 1.91%   |
| 2 x Nvidia     | 2         | 0.55%   |
| 1 x VIA        | 1         | 0.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 312       | 84.32%  |
| Proprietary | 47        | 12.7%   |
| Unknown     | 11        | 2.97%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 211       | 55.97%  |
| 1.01-2.0   | 63        | 16.71%  |
| 0.01-0.5   | 55        | 14.59%  |
| 3.01-4.0   | 27        | 7.16%   |
| 0.51-1.0   | 20        | 5.31%   |
| 7.01-8.0   | 1         | 0.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 81        | 19.71%  |
| BOE                     | 65        | 15.82%  |
| LG Display              | 63        | 15.33%  |
| Chimei Innolux          | 51        | 12.41%  |
| Samsung Electronics     | 39        | 9.49%   |
| Dell                    | 13        | 3.16%   |
| Lenovo                  | 12        | 2.92%   |
| Chi Mei Optoelectronics | 12        | 2.92%   |
| PANDA                   | 8         | 1.95%   |
| Apple                   | 8         | 1.95%   |
| Sharp                   | 7         | 1.7%    |
| Philips                 | 5         | 1.22%   |
| LG Philips              | 5         | 1.22%   |
| Hewlett-Packard         | 5         | 1.22%   |
| Sony                    | 4         | 0.97%   |
| Goldstar                | 4         | 0.97%   |
| CPT                     | 4         | 0.97%   |
| Toshiba                 | 3         | 0.73%   |
| InfoVision              | 3         | 0.73%   |
| BenQ                    | 3         | 0.73%   |
| Unknown                 | 2         | 0.49%   |
| AOC                     | 2         | 0.49%   |
| ViewSonic               | 1         | 0.24%   |
| SKY                     | 1         | 0.24%   |
| Seiko/Epson             | 1         | 0.24%   |
| LPL                     | 1         | 0.24%   |
| InnoLux Display         | 1         | 0.24%   |
| Iiyama                  | 1         | 0.24%   |
| Hitachi                 | 1         | 0.24%   |
| HannStar                | 1         | 0.24%   |
| CSO                     | 1         | 0.24%   |
| CHD                     | 1         | 0.24%   |
| ASUSTek Computer        | 1         | 0.24%   |
| Ancor Communications    | 1         | 0.24%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 17        | 4.1%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 10        | 2.41%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 8         | 1.93%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 7         | 1.69%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 5         | 1.2%    |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 5         | 1.2%    |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 4         | 0.96%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                 | 4         | 0.96%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 4         | 0.96%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch  | 3         | 0.72%   |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch | 3         | 0.72%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 3         | 0.72%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch         | 3         | 0.72%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 3         | 0.72%   |
| Dell P2417H DELA0DC 1920x1080 527x296mm 23.8-inch                     | 3         | 0.72%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 0.72%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch       | 3         | 0.72%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch      | 3         | 0.72%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 3         | 0.72%   |
| BOE LCD Monitor BOE07A3 1920x1080 344x193mm 15.5-inch                 | 3         | 0.72%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                  | 3         | 0.72%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 3         | 0.72%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch         | 3         | 0.72%   |
| Sony LCD SNY06FA 1600x900 291x164mm 13.2-inch                         | 2         | 0.48%   |
| Sharp LQ173M1JW04 SHP14E1 1920x1080 382x215mm 17.3-inch               | 2         | 0.48%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 2         | 0.48%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch | 2         | 0.48%   |
| PANDA LCD Monitor NCP006E 1920x1080 344x194mm 15.5-inch               | 2         | 0.48%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch          | 2         | 0.48%   |
| LG Display LCD Monitor LGD0519 1920x1080 344x194mm 15.5-inch          | 2         | 0.48%   |
| LG Display LCD Monitor LGD0484 1366x768 344x194mm 15.5-inch           | 2         | 0.48%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 0.48%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch           | 2         | 0.48%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch           | 2         | 0.48%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 2         | 0.48%   |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                  | 2         | 0.48%   |
| Dell U2412M DELA079 1920x1200 518x324mm 24.1-inch                     | 2         | 0.48%   |
| CPT LCD Monitor CPT14BF 1366x768 344x193mm 15.5-inch                  | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch      | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15E5 1920x1080 344x193mm 15.5-inch      | 2         | 0.48%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 178       | 46.35%  |
| 1366x768 (WXGA)    | 127       | 33.07%  |
| 1280x800 (WXGA)    | 14        | 3.65%   |
| 1600x900 (HD+)     | 12        | 3.13%   |
| 3840x2160 (4K)     | 7         | 1.82%   |
| 1440x900 (WXGA+)   | 7         | 1.82%   |
| 2560x1440 (QHD)    | 6         | 1.56%   |
| 1920x1200 (WUXGA)  | 4         | 1.04%   |
| 1360x768           | 4         | 1.04%   |
| 2880x1800          | 3         | 0.78%   |
| 2560x1600          | 3         | 0.78%   |
| 1680x1050 (WSXGA+) | 3         | 0.78%   |
| 1024x600           | 3         | 0.78%   |
| 1280x1024 (SXGA)   | 2         | 0.52%   |
| 1024x768 (XGA)     | 2         | 0.52%   |
| Unknown            | 2         | 0.52%   |
| 3360x1200          | 1         | 0.26%   |
| 3280x1080          | 1         | 0.26%   |
| 2520x1680          | 1         | 0.26%   |
| 2160x1350          | 1         | 0.26%   |
| 1920x540           | 1         | 0.26%   |
| 1680x945           | 1         | 0.26%   |
| 1400x1050          | 1         | 0.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 232       | 56.59%  |
| 13      | 32        | 7.8%    |
| 14      | 29        | 7.07%   |
| 17      | 26        | 6.34%   |
| 24      | 18        | 4.39%   |
| 23      | 14        | 3.41%   |
| 12      | 8         | 1.95%   |
| 21      | 7         | 1.71%   |
| Unknown | 7         | 1.71%   |
| 31      | 5         | 1.22%   |
| 27      | 5         | 1.22%   |
| 11      | 5         | 1.22%   |
| 16      | 4         | 0.98%   |
| 72      | 3         | 0.73%   |
| 40      | 2         | 0.49%   |
| 18      | 2         | 0.49%   |
| 10      | 2         | 0.49%   |
| 84      | 1         | 0.24%   |
| 54      | 1         | 0.24%   |
| 46      | 1         | 0.24%   |
| 43      | 1         | 0.24%   |
| 32      | 1         | 0.24%   |
| 26      | 1         | 0.24%   |
| 20      | 1         | 0.24%   |
| 19      | 1         | 0.24%   |
| 8       | 1         | 0.24%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 281       | 68.7%   |
| 501-600     | 37        | 9.05%   |
| 351-400     | 30        | 7.33%   |
| 201-300     | 27        | 6.6%    |
| 401-500     | 11        | 2.69%   |
| Unknown     | 7         | 1.71%   |
| 601-700     | 5         | 1.22%   |
| 1501-2000   | 4         | 0.98%   |
| 801-900     | 2         | 0.49%   |
| 1001-1500   | 2         | 0.49%   |
| 701-800     | 1         | 0.24%   |
| 101-200     | 1         | 0.24%   |
| 901-1000    | 1         | 0.24%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 316       | 88.02%  |
| 16/10   | 31        | 8.64%   |
| 4/3     | 4         | 1.11%   |
| Unknown | 4         | 1.11%   |
| 3/2     | 3         | 0.84%   |
| 5/4     | 1         | 0.28%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 233       | 56.83%  |
| 81-90          | 51        | 12.44%  |
| 201-250        | 34        | 8.29%   |
| 121-130        | 25        | 6.1%    |
| 71-80          | 10        | 2.44%   |
| 61-70          | 7         | 1.71%   |
| Unknown        | 7         | 1.71%   |
| 351-500        | 6         | 1.46%   |
| 301-350        | 6         | 1.46%   |
| More than 1000 | 5         | 1.22%   |
| 51-60          | 5         | 1.22%   |
| 251-300        | 4         | 0.98%   |
| 501-1000       | 4         | 0.98%   |
| 151-200        | 3         | 0.73%   |
| 111-120        | 3         | 0.73%   |
| 41-50          | 2         | 0.49%   |
| 141-150        | 2         | 0.49%   |
| 1-40           | 1         | 0.24%   |
| 131-140        | 1         | 0.24%   |
| 91-100         | 1         | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 169       | 42.46%  |
| 101-120       | 135       | 33.92%  |
| 51-100        | 62        | 15.58%  |
| 161-240       | 15        | 3.77%   |
| Unknown       | 7         | 1.76%   |
| More than 240 | 5         | 1.26%   |
| 1-50          | 5         | 1.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 299       | 79.95%  |
| 2     | 60        | 16.04%  |
| 0     | 9         | 2.41%   |
| 3     | 6         | 1.6%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 215       | 35.77%  |
| Intel                             | 160       | 26.62%  |
| Qualcomm Atheros                  | 109       | 18.14%  |
| Broadcom                          | 46        | 7.65%   |
| Broadcom Limited                  | 10        | 1.66%   |
| Ralink                            | 9         | 1.5%    |
| MediaTek                          | 7         | 1.16%   |
| Nvidia                            | 6         | 1%      |
| Marvell Technology Group          | 5         | 0.83%   |
| Ralink Technology                 | 4         | 0.67%   |
| Ericsson Business Mobile Networks | 4         | 0.67%   |
| Dell                              | 4         | 0.67%   |
| Sierra Wireless                   | 3         | 0.5%    |
| Huawei Technologies               | 3         | 0.5%    |
| ZTE WCDMA Technologies MSM        | 2         | 0.33%   |
| TP-Link                           | 2         | 0.33%   |
| Qualcomm Atheros Communications   | 2         | 0.33%   |
| JMicron Technology                | 2         | 0.33%   |
| Xiaomi                            | 1         | 0.17%   |
| VIA Technologies                  | 1         | 0.17%   |
| Samsung Electronics               | 1         | 0.17%   |
| Linksys                           | 1         | 0.17%   |
| IMC Networks                      | 1         | 0.17%   |
| D-Link                            | 1         | 0.17%   |
| Arduino SA                        | 1         | 0.17%   |
| Apple                             | 1         | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 127       | 17.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 60        | 8.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 29        | 4.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 20        | 2.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 18        | 2.53%   |
| Intel Wireless 8265 / 8275                                              | 16        | 2.25%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 13        | 1.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 12        | 1.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 12        | 1.69%   |
| Broadcom BCM43142 802.11b/g/n                                           | 12        | 1.69%   |
| Intel Wireless 8260                                                     | 11        | 1.55%   |
| Intel Wireless 7260                                                     | 10        | 1.41%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 10        | 1.41%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 8         | 1.13%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 8         | 1.13%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 1.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 8         | 1.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 0.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 0.98%   |
| Intel Wireless 3165                                                     | 7         | 0.98%   |
| Intel Wi-Fi 6 AX200                                                     | 7         | 0.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 0.98%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 6         | 0.84%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 0.84%   |
| Intel Wi-Fi 6 AX201                                                     | 6         | 0.84%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 0.84%   |
| Intel Ethernet Connection I219-LM                                       | 6         | 0.84%   |
| Intel Ethernet Connection (4) I219-LM                                   | 6         | 0.84%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 6         | 0.84%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 0.7%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 5         | 0.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 5         | 0.7%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 5         | 0.7%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 0.7%    |
| Nvidia MCP79 Ethernet                                                   | 5         | 0.7%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 0.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 0.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 4         | 0.56%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 4         | 0.56%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 4         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 152       | 40.11%  |
| Qualcomm Atheros                | 95        | 25.07%  |
| Realtek Semiconductor           | 61        | 16.09%  |
| Broadcom                        | 35        | 9.23%   |
| Ralink                          | 9         | 2.37%   |
| MediaTek                        | 7         | 1.85%   |
| Ralink Technology               | 4         | 1.06%   |
| Sierra Wireless                 | 3         | 0.79%   |
| Dell                            | 3         | 0.79%   |
| Broadcom Limited                | 3         | 0.79%   |
| TP-Link                         | 2         | 0.53%   |
| Qualcomm Atheros Communications | 2         | 0.53%   |
| Linksys                         | 1         | 0.26%   |
| IMC Networks                    | 1         | 0.26%   |
| D-Link                          | 1         | 0.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 29        | 7.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 20        | 5.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 18        | 4.74%   |
| Intel Wireless 8265 / 8275                                              | 16        | 4.21%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 13        | 3.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 12        | 3.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 12        | 3.16%   |
| Broadcom BCM43142 802.11b/g/n                                           | 12        | 3.16%   |
| Intel Wireless 8260                                                     | 11        | 2.89%   |
| Intel Wireless 7260                                                     | 10        | 2.63%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 10        | 2.63%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 8         | 2.11%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 8         | 2.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 2.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 1.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 1.84%   |
| Intel Wireless 3165                                                     | 7         | 1.84%   |
| Intel Wi-Fi 6 AX200                                                     | 7         | 1.84%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 1.84%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 1.58%   |
| Intel Wi-Fi 6 AX201                                                     | 6         | 1.58%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 1.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 1.32%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.32%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 5         | 1.32%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 5         | 1.32%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 1.32%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 1.32%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 1.32%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 4         | 1.05%   |
| Intel Wireless 3160                                                     | 4         | 1.05%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 4         | 1.05%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 1.05%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.79%   |
| Intel Wireless 7265                                                     | 3         | 0.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 0.79%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 0.79%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 0.79%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 0.79%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                    | 3         | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 195       | 61.51%  |
| Intel                      | 56        | 17.67%  |
| Qualcomm Atheros           | 23        | 7.26%   |
| Broadcom                   | 17        | 5.36%   |
| Broadcom Limited           | 7         | 2.21%   |
| Nvidia                     | 6         | 1.89%   |
| Marvell Technology Group   | 5         | 1.58%   |
| ZTE WCDMA Technologies MSM | 2         | 0.63%   |
| JMicron Technology         | 2         | 0.63%   |
| Xiaomi                     | 1         | 0.32%   |
| VIA Technologies           | 1         | 0.32%   |
| Huawei Technologies        | 1         | 0.32%   |
| Apple                      | 1         | 0.32%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 127       | 39.69%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 60        | 18.75%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 2.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 1.88%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 1.88%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 1.88%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 6         | 1.88%   |
| Nvidia MCP79 Ethernet                                             | 5         | 1.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.25%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 4         | 1.25%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.25%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.94%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.94%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 3         | 0.94%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.94%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.94%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.94%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 0.94%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 3         | 0.94%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.63%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.63%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 0.63%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.63%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.63%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.63%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.63%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.63%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 0.63%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 2         | 0.63%   |
| ZTE WCDMA MSM ZTE BLADE A530                                      | 1         | 0.31%   |
| ZTE WCDMA MSM DEMO Mobile Boardband                               | 1         | 0.31%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.31%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.31%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.31%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.31%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.31%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.31%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.31%   |
| Nvidia MCP67 Ethernet                                             | 1         | 0.31%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 364       | 52.91%  |
| Ethernet | 313       | 45.49%  |
| Modem    | 11        | 1.6%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 305       | 79.02%  |
| Ethernet | 81        | 20.98%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 302       | 82.74%  |
| 1     | 62        | 16.99%  |
| 3     | 1         | 0.27%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 360       | 98.63%  |
| Yes  | 5         | 1.37%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 109       | 36.58%  |
| Realtek Semiconductor           | 47        | 15.77%  |
| Qualcomm Atheros Communications | 36        | 12.08%  |
| Lite-On Technology              | 22        | 7.38%   |
| IMC Networks                    | 19        | 6.38%   |
| Broadcom                        | 18        | 6.04%   |
| Foxconn / Hon Hai               | 11        | 3.69%   |
| Apple                           | 7         | 2.35%   |
| Toshiba                         | 6         | 2.01%   |
| Hewlett-Packard                 | 5         | 1.68%   |
| Ralink                          | 3         | 1.01%   |
| Foxconn International           | 3         | 1.01%   |
| Dell                            | 3         | 1.01%   |
| USI                             | 2         | 0.67%   |
| Ralink Technology               | 2         | 0.67%   |
| Cambridge Silicon Radio         | 2         | 0.67%   |
| Realtek                         | 1         | 0.34%   |
| Askey Computer                  | 1         | 0.34%   |
| Alps Electric                   | 1         | 0.34%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 49        | 16.44%  |
| Realtek Bluetooth Radio                            | 27        | 9.06%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 24        | 8.05%   |
| Qualcomm Atheros  Bluetooth Device                 | 22        | 7.38%   |
| Intel AX201 Bluetooth                              | 13        | 4.36%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth         | 12        | 4.03%   |
| Realtek  Bluetooth 4.2 Adapter                     | 11        | 3.69%   |
| Intel AX200 Bluetooth                              | 7         | 2.35%   |
| IMC Networks Bluetooth Radio                       | 7         | 2.35%   |
| Lite-On Bluetooth Device                           | 6         | 2.01%   |
| Apple Bluetooth Host Controller                    | 6         | 2.01%   |
| Qualcomm Atheros AR3011 Bluetooth                  | 5         | 1.68%   |
| Realtek RTL8821A Bluetooth                         | 4         | 1.34%   |
| Qualcomm Atheros AR9462 Bluetooth                  | 4         | 1.34%   |
| Intel Centrino Bluetooth Wireless Transceiver      | 4         | 1.34%   |
| IMC Networks Wireless_Device                       | 4         | 1.34%   |
| Foxconn / Hon Hai Bluetooth Device                 | 4         | 1.34%   |
| Broadcom BCM43142A0 Bluetooth 4.0                  | 4         | 1.34%   |
| Realtek RTL8723B Bluetooth                         | 3         | 1.01%   |
| Ralink RT3290 Bluetooth                            | 3         | 1.01%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0              | 3         | 1.01%   |
| Intel Wireless-AC 3168 Bluetooth                   | 3         | 1.01%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter   | 3         | 1.01%   |
| IMC Networks Bluetooth Device                      | 3         | 1.01%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter  | 3         | 1.01%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]      | 3         | 1.01%   |
| Foxconn International BCM43142A0 Bluetooth module  | 3         | 1.01%   |
| Foxconn / Hon Hai Wireless_Device                  | 3         | 1.01%   |
| Dell DW375 Bluetooth Module                        | 3         | 1.01%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 3         | 1.01%   |
| USI Bluetooth Module BCM92070                      | 2         | 0.67%   |
| Toshiba Bluetooth Device                           | 2         | 0.67%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter            | 2         | 0.67%   |
| Qualcomm Atheros AR3012 Bluetooth                  | 2         | 0.67%   |
| Lite-On Atheros AR3012 Bluetooth                   | 2         | 0.67%   |
| Intel Wireless-AC 9260 Bluetooth Adapter           | 2         | 0.67%   |
| Intel Bluetooth Device                             | 2         | 0.67%   |
| Intel AX210 Bluetooth                              | 2         | 0.67%   |
| HP Broadcom 2070 Bluetooth Combo                   | 2         | 0.67%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device    | 2         | 0.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 289       | 68.32%  |
| AMD                 | 73        | 17.26%  |
| Nvidia              | 50        | 11.82%  |
| Logitech            | 2         | 0.47%   |
| GN Netcom           | 2         | 0.47%   |
| VIA Technologies    | 1         | 0.24%   |
| Native Instruments  | 1         | 0.24%   |
| Kingston Technology | 1         | 0.24%   |
| Hewlett-Packard     | 1         | 0.24%   |
| Focusrite-Novation  | 1         | 0.24%   |
| C-Media Electronics | 1         | 0.24%   |
| Apple               | 1         | 0.24%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 47        | 9.11%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 44        | 8.53%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 30        | 5.81%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 27        | 5.23%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 22        | 4.26%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 21        | 4.07%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 14        | 2.71%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 13        | 2.52%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 13        | 2.52%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 12        | 2.33%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 12        | 2.33%   |
| Intel Cannon Lake PCH cAVS                                                                        | 12        | 2.33%   |
| Intel Broadwell-U Audio Controller                                                                | 12        | 2.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 11        | 2.13%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 11        | 2.13%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 11        | 2.13%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 1.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 10        | 1.94%   |
| Intel 8 Series HD Audio Controller                                                                | 10        | 1.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 1.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 9         | 1.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 9         | 1.74%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 9         | 1.74%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 8         | 1.55%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 1.36%   |
| AMD FCH Azalia Controller                                                                         | 7         | 1.36%   |
| Intel Comet Lake PCH cAVS                                                                         | 6         | 1.16%   |
| Intel CM238 HD Audio Controller                                                                   | 6         | 1.16%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 1.16%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 1.16%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6         | 1.16%   |
| Nvidia MCP79 High Definition Audio                                                                | 5         | 0.97%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 0.97%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 5         | 0.97%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 5         | 0.97%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 0.97%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 0.78%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 0.58%   |
| AMD High Definition Audio Controller                                                              | 3         | 0.58%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 64        | 26.12%  |
| SK hynix            | 57        | 23.27%  |
| Micron Technology   | 35        | 14.29%  |
| Kingston            | 31        | 12.65%  |
| Unknown             | 17        | 6.94%   |
| Ramaxel Technology  | 11        | 4.49%   |
| Transcend           | 7         | 2.86%   |
| Elpida              | 5         | 2.04%   |
| Patriot             | 3         | 1.22%   |
| Crucial             | 3         | 1.22%   |
| Corsair             | 2         | 0.82%   |
| A-DATA Technology   | 2         | 0.82%   |
| SHARETRONIC         | 1         | 0.41%   |
| PNY                 | 1         | 0.41%   |
| Nanya Technology    | 1         | 0.41%   |
| CSX                 | 1         | 0.41%   |
| Apacer              | 1         | 0.41%   |
| AMD                 | 1         | 0.41%   |
| 48spaces            | 1         | 0.41%   |
| Unknown             | 1         | 0.41%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 6         | 2.26%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s      | 5         | 1.88%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 5         | 1.88%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s        | 5         | 1.88%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s      | 4         | 1.5%    |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 4         | 1.5%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s       | 4         | 1.5%    |
| Micron RAM 4ATF51264HZ-2G6E! 4GB SODIMM DDR4 2400MT/s       | 4         | 1.5%    |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s     | 4         | 1.5%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 3         | 1.13%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 3         | 1.13%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 3         | 1.13%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s       | 3         | 1.13%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s       | 3         | 1.13%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s       | 3         | 1.13%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s       | 3         | 1.13%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 3         | 1.13%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s        | 3         | 1.13%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s        | 3         | 1.13%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s       | 3         | 1.13%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                  | 2         | 0.75%   |
| Unknown RAM Module 1024MB SODIMM DDR                        | 2         | 0.75%   |
| Transcend RAM JM3200HSG-8G 8GB SODIMM DDR4 3200MT/s         | 2         | 0.75%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 2048MT/s      | 2         | 0.75%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 2         | 0.75%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 2         | 0.75%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s      | 2         | 0.75%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s      | 2         | 0.75%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s      | 2         | 0.75%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s      | 2         | 0.75%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 2         | 0.75%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 2         | 0.75%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s      | 2         | 0.75%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s       | 2         | 0.75%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s       | 2         | 0.75%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s       | 2         | 0.75%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s       | 2         | 0.75%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s       | 2         | 0.75%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s       | 2         | 0.75%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s | 2         | 0.75%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 93        | 47.69%  |
| DDR3    | 66        | 33.85%  |
| DDR2    | 12        | 6.15%   |
| LPDDR4  | 7         | 3.59%   |
| SDRAM   | 6         | 3.08%   |
| DDR5    | 3         | 1.54%   |
| Unknown | 3         | 1.54%   |
| LPDDR3  | 2         | 1.03%   |
| DDR     | 2         | 1.03%   |
| LPDDR5  | 1         | 0.51%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 178       | 91.28%  |
| Row Of Chips | 14        | 7.18%   |
| Chip         | 3         | 1.54%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 75        | 35.38%  |
| 4096  | 74        | 34.91%  |
| 2048  | 35        | 16.51%  |
| 16384 | 16        | 7.55%   |
| 1024  | 9         | 4.25%   |
| 32768 | 2         | 0.94%   |
| 512   | 1         | 0.47%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 47        | 21.66%  |
| 2667    | 45        | 20.74%  |
| 3200    | 41        | 18.89%  |
| 2400    | 16        | 7.37%   |
| 1334    | 12        | 5.53%   |
| 1067    | 8         | 3.69%   |
| 2133    | 7         | 3.23%   |
| 667     | 7         | 3.23%   |
| Unknown | 6         | 2.76%   |
| 1333    | 4         | 1.84%   |
| 4800    | 3         | 1.38%   |
| 4199    | 3         | 1.38%   |
| 3266    | 3         | 1.38%   |
| 2048    | 3         | 1.38%   |
| 800     | 3         | 1.38%   |
| 4267    | 2         | 0.92%   |
| 975     | 2         | 0.92%   |
| 533     | 2         | 0.92%   |
| 6400    | 1         | 0.46%   |
| 2933    | 1         | 0.46%   |
| 1066    | 1         | 0.46%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 5         | 50%     |
| Canon                 | 2         | 20%     |
| Seiko Epson           | 1         | 10%     |
| Samsung Electronics   | 1         | 10%     |
| Lexmark International | 1         | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| HP LaserJet 1018                      | 2         | 20%     |
| Seiko Epson L365 Series               | 1         | 10%     |
| Samsung M2070 Series                  | 1         | 10%     |
| Lexmark International Lexmark MS312dn | 1         | 10%     |
| HP LaserJet M14-M17                   | 1         | 10%     |
| HP LaserJet 1020                      | 1         | 10%     |
| HP DeskJet 845c                       | 1         | 10%     |
| Canon LBP6030w/6018w                  | 1         | 10%     |
| Canon iP7200 series                   | 1         | 10%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 4         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 2         | 50%     |
| Canon CanoScan LIDE 25  | 1         | 25%     |
| Canon CanoScan LiDE 210 | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 91        | 27.16%  |
| IMC Networks                           | 49        | 14.63%  |
| Realtek Semiconductor                  | 31        | 9.25%   |
| Microdia                               | 23        | 6.87%   |
| Quanta                                 | 20        | 5.97%   |
| Cheng Uei Precision Industry (Foxlink) | 17        | 5.07%   |
| Suyin                                  | 16        | 4.78%   |
| Sunplus Innovation Technology          | 16        | 4.78%   |
| Acer                                   | 15        | 4.48%   |
| Syntek                                 | 12        | 3.58%   |
| Bison Electronics                      | 8         | 2.39%   |
| Apple                                  | 8         | 2.39%   |
| Lite-On Technology                     | 7         | 2.09%   |
| Silicon Motion                         | 3         | 0.9%    |
| Importek                               | 3         | 0.9%    |
| Alcor Micro                            | 3         | 0.9%    |
| Luxvisions Innotech Limited            | 2         | 0.6%    |
| Lenovo                                 | 2         | 0.6%    |
| ALi                                    | 2         | 0.6%    |
| Samsung Electronics                    | 1         | 0.3%    |
| Ricoh                                  | 1         | 0.3%    |
| OmniVision Technologies                | 1         | 0.3%    |
| Logitech                               | 1         | 0.3%    |
| KYE Systems (Mouse Systems)            | 1         | 0.3%    |
| Generalplus Technology                 | 1         | 0.3%    |
| DigiTech                               | 1         | 0.3%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 22        | 6.55%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 19        | 5.65%   |
| Realtek Integrated_Webcam_HD                                   | 11        | 3.27%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 10        | 2.98%   |
| Microdia Integrated_Webcam_HD                                  | 9         | 2.68%   |
| Syntek Integrated Camera                                       | 8         | 2.38%   |
| Sunplus Integrated_Webcam_HD                                   | 7         | 2.08%   |
| IMC Networks Integrated Camera                                 | 7         | 2.08%   |
| Acer Integrated Camera                                         | 7         | 2.08%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 5         | 1.49%   |
| Quanta VGA WebCam                                              | 5         | 1.49%   |
| Quanta HD WebCam                                               | 5         | 1.49%   |
| Chicony TOSHIBA Web Camera - HD                                | 5         | 1.49%   |
| Chicony Integrated Camera (1280x720@30)                        | 5         | 1.49%   |
| Chicony HP Webcam                                              | 5         | 1.49%   |
| Chicony EasyCamera                                             | 5         | 1.49%   |
| Syntek EasyCamera                                              | 4         | 1.19%   |
| Realtek USB Camera                                             | 4         | 1.19%   |
| Realtek Lenovo EasyCamera                                      | 4         | 1.19%   |
| Quanta HP TrueVision HD Camera                                 | 4         | 1.19%   |
| Microdia Integrated Webcam                                     | 4         | 1.19%   |
| IMC Networks EasyCamera                                        | 4         | 1.19%   |
| Chicony VGA Webcam                                             | 4         | 1.19%   |
| Chicony HD WebCam                                              | 4         | 1.19%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 4         | 1.19%   |
| Apple Built-in iSight                                          | 4         | 1.19%   |
| Sunplus Asus Webcam                                            | 3         | 0.89%   |
| Realtek Integrated Webcam HD                                   | 3         | 0.89%   |
| Chicony USB 2.0 Camera                                         | 3         | 0.89%   |
| Chicony HP Truevision HD                                       | 3         | 0.89%   |
| Chicony HD User Facing                                         | 3         | 0.89%   |
| Chicony 1.3M HD WebCam                                         | 3         | 0.89%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 3         | 0.89%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 3         | 0.89%   |
| Apple FaceTime HD Camera                                       | 3         | 0.89%   |
| Acer Lenovo EasyCamera                                         | 3         | 0.89%   |
| Acer BisonCam, NB Pro                                          | 3         | 0.89%   |
| Suyin Integrated_Webcam_HD                                     | 2         | 0.6%    |
| Suyin Acer CrystalEye Webcam                                   | 2         | 0.6%    |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)    | 2         | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 21        | 36.21%  |
| Synaptics                  | 12        | 20.69%  |
| Shenzhen Goodix Technology | 10        | 17.24%  |
| AuthenTec                  | 6         | 10.34%  |
| Upek                       | 3         | 5.17%   |
| Elan Microelectronics      | 3         | 5.17%   |
| LighTuning Technology      | 2         | 3.45%   |
| STMicroelectronics         | 1         | 1.72%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 8         | 13.79%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 10.34%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 8.62%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 5         | 8.62%   |
| Synaptics  WBDI                                                            | 4         | 6.9%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 5.17%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 3.45%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 3.45%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 3.45%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 3.45%   |
| Synaptics WBDI                                                             | 2         | 3.45%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 3.45%   |
| Elan ELAN:Fingerprint                                                      | 2         | 3.45%   |
| AuthenTec AES2810                                                          | 2         | 3.45%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.72%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 1.72%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 1.72%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.72%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 1.72%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 1.72%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.72%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.72%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 1.72%   |
| Elan ELAN:ARM-M4                                                           | 1         | 1.72%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.72%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 10        | 34.48%  |
| Alcor Micro               | 9         | 31.03%  |
| Upek                      | 2         | 6.9%    |
| OmniKey                   | 2         | 6.9%    |
| O2 Micro                  | 2         | 6.9%    |
| Lenovo                    | 2         | 6.9%    |
| Gemalto (was Gemplus)     | 1         | 3.45%   |
| Fujitsu Siemens Computers | 1         | 3.45%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 9         | 31.03%  |
| Broadcom BCM5880 Secure Applications Processor             | 4         | 13.79%  |
| Broadcom 5880                                              | 4         | 13.79%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 2         | 6.9%    |
| O2 Micro OZ776 CCID Smartcard Reader                       | 2         | 6.9%    |
| Lenovo Integrated Smart Card Reader                        | 2         | 6.9%    |
| Broadcom 58200                                             | 2         | 6.9%    |
| OmniKey CardMan 4321                                       | 1         | 3.45%   |
| OmniKey 3x21 Smart Card Reader                             | 1         | 3.45%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader          | 1         | 3.45%   |
| Fujitsu Siemens Computers SmartCard Reader 2A              | 1         | 3.45%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 239       | 63.23%  |
| 1     | 108       | 28.57%  |
| 2     | 24        | 6.35%   |
| 3     | 4         | 1.06%   |
| 4     | 2         | 0.53%   |
| 8     | 1         | 0.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 58        | 33.33%  |
| Graphics card            | 42        | 24.14%  |
| Chipcard                 | 26        | 14.94%  |
| Net/wireless             | 17        | 9.77%   |
| Multimedia controller    | 8         | 4.6%    |
| Bluetooth                | 6         | 3.45%   |
| Communication controller | 5         | 2.87%   |
| Camera                   | 4         | 2.3%    |
| Sound                    | 2         | 1.15%   |
| Net/ethernet             | 2         | 1.15%   |
| Card reader              | 2         | 1.15%   |
| Storage                  | 1         | 0.57%   |
| Modem                    | 1         | 0.57%   |


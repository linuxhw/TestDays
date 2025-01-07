Linux in Egypt - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Egypt.

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

Total: 726

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Panasonic     | CF-31SBLEB1M                | [c01282e1c8](https://linux-hardware.org/?probe=c01282e1c8) | Dec 27, 2024 |
| Panasonic     | CF-31SBLEB1M                | [b1be038c76](https://linux-hardware.org/?probe=b1be038c76) | Dec 27, 2024 |
| Dell          | XPS 15 9500                 | [985a70079c](https://linux-hardware.org/?probe=985a70079c) | Dec 26, 2024 |
| Dell          | XPS 15 9500                 | [6beec071ad](https://linux-hardware.org/?probe=6beec071ad) | Dec 25, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [729549a358](https://linux-hardware.org/?probe=729549a358) | Dec 25, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [fe9e479afd](https://linux-hardware.org/?probe=fe9e479afd) | Dec 21, 2024 |
| Toshiba       | Satellite L50-B             | [44d23fe380](https://linux-hardware.org/?probe=44d23fe380) | Dec 14, 2024 |
| Dell          | Inspiron 5405               | [3bbbe8e729](https://linux-hardware.org/?probe=3bbbe8e729) | Dec 13, 2024 |
| HP            | Laptop 15-dw3xxx            | [6b8ce5850b](https://linux-hardware.org/?probe=6b8ce5850b) | Dec 12, 2024 |
| Dell          | Latitude 5430               | [da4238a565](https://linux-hardware.org/?probe=da4238a565) | Dec 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [b83929cc27](https://linux-hardware.org/?probe=b83929cc27) | Dec 02, 2024 |
| HUAWEI        | NBLK-WAX9X                  | [2f6d2fe7e2](https://linux-hardware.org/?probe=2f6d2fe7e2) | Dec 01, 2024 |
| Alienware     | 17                          | [feba90fb9d](https://linux-hardware.org/?probe=feba90fb9d) | Nov 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [82cdcbb4ca](https://linux-hardware.org/?probe=82cdcbb4ca) | Nov 29, 2024 |
| Dell          | Precision M4800             | [c97548d58c](https://linux-hardware.org/?probe=c97548d58c) | Nov 28, 2024 |
| Dell          | Precision M4800             | [8cddfc2c38](https://linux-hardware.org/?probe=8cddfc2c38) | Nov 28, 2024 |
| Dell          | Precision M4800             | [932bc22167](https://linux-hardware.org/?probe=932bc22167) | Nov 28, 2024 |
| ASUSTek       | X553MA                      | [68441310db](https://linux-hardware.org/?probe=68441310db) | Nov 20, 2024 |
| ASUSTek       | X553MA                      | [43952ac7ef](https://linux-hardware.org/?probe=43952ac7ef) | Nov 20, 2024 |
| Toshiba       | Satellite C55D-B            | [7c3fb96c09](https://linux-hardware.org/?probe=7c3fb96c09) | Nov 18, 2024 |
| HP            | EliteBook 845 G8 Noteboo... | [cbaa46528f](https://linux-hardware.org/?probe=cbaa46528f) | Nov 10, 2024 |
| HP            | EliteBook 845 G8 Noteboo... | [765457bf04](https://linux-hardware.org/?probe=765457bf04) | Nov 09, 2024 |
| HP            | ProBook 450 G4              | [bbe42e4f22](https://linux-hardware.org/?probe=bbe42e4f22) | Nov 04, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [dde9b2b53c](https://linux-hardware.org/?probe=dde9b2b53c) | Nov 04, 2024 |
| HP            | 250 G7 Notebook PC          | [a3e0d131dc](https://linux-hardware.org/?probe=a3e0d131dc) | Nov 01, 2024 |
| Lenovo        | ThinkPad T460s 20F9001DU... | [02bcf148cc](https://linux-hardware.org/?probe=02bcf148cc) | Oct 31, 2024 |
| Apple         | MacBookPro13,1              | [a4cea0834a](https://linux-hardware.org/?probe=a4cea0834a) | Oct 29, 2024 |
| Dell          | G15 5515                    | [e1bfa90d78](https://linux-hardware.org/?probe=e1bfa90d78) | Oct 28, 2024 |
| Lenovo        | Legion Y540-15IRH 81SX      | [4c16301925](https://linux-hardware.org/?probe=4c16301925) | Oct 27, 2024 |
| HP            | ProBook 450 G4              | [e519e7e92e](https://linux-hardware.org/?probe=e519e7e92e) | Oct 15, 2024 |
| HP            | EliteBook 2730p             | [d19cdc0aa3](https://linux-hardware.org/?probe=d19cdc0aa3) | Oct 14, 2024 |
| HP            | EliteBook 2730p             | [77f96f6424](https://linux-hardware.org/?probe=77f96f6424) | Oct 14, 2024 |
| Dell          | G15 5515                    | [13906ffd4a](https://linux-hardware.org/?probe=13906ffd4a) | Oct 13, 2024 |
| Dell          | G15 5515                    | [876d624fba](https://linux-hardware.org/?probe=876d624fba) | Oct 13, 2024 |
| Dell          | Precision 7530              | [ca12dbc1be](https://linux-hardware.org/?probe=ca12dbc1be) | Oct 11, 2024 |
| Dell          | G15 5520                    | [0d6ad139c2](https://linux-hardware.org/?probe=0d6ad139c2) | Oct 11, 2024 |
| Dell          | Precision 7530              | [c386366ce5](https://linux-hardware.org/?probe=c386366ce5) | Oct 10, 2024 |
| HP            | Laptop 15-dw3xxx            | [5188f7bee3](https://linux-hardware.org/?probe=5188f7bee3) | Oct 09, 2024 |
| Dell          | Precision M4800             | [87e17e0353](https://linux-hardware.org/?probe=87e17e0353) | Oct 09, 2024 |
| Lenovo        | IdeaPad 1 15IAU7 82QD       | [70445ed733](https://linux-hardware.org/?probe=70445ed733) | Oct 09, 2024 |
| Lenovo        | IdeaPad 1 15IAU7 82QD       | [267a889e66](https://linux-hardware.org/?probe=267a889e66) | Oct 07, 2024 |
| HP            | EliteBook 745 G6            | [00186bd746](https://linux-hardware.org/?probe=00186bd746) | Oct 04, 2024 |
| Lenovo        | LOQ 15IAX9 83GS             | [ae376b3f78](https://linux-hardware.org/?probe=ae376b3f78) | Oct 02, 2024 |
| HP            | OMEN by Laptop 15-dc1xxx    | [5fca760834](https://linux-hardware.org/?probe=5fca760834) | Oct 02, 2024 |
| Lenovo        | LOQ 15IAX9 83GS             | [c05357e589](https://linux-hardware.org/?probe=c05357e589) | Oct 02, 2024 |
| HP            | ProBook 450 G4              | [74d843a3ff](https://linux-hardware.org/?probe=74d843a3ff) | Oct 01, 2024 |
| Lenovo        | Legion Y545 81Q6            | [451563b4fb](https://linux-hardware.org/?probe=451563b4fb) | Oct 01, 2024 |
| HP            | ProBook 450 G4              | [15151ed93a](https://linux-hardware.org/?probe=15151ed93a) | Sep 28, 2024 |
| Sony          | SVE15126CAB                 | [f60413658c](https://linux-hardware.org/?probe=f60413658c) | Sep 28, 2024 |
| HP            | EliteBook 745 G3            | [f8be1ee994](https://linux-hardware.org/?probe=f8be1ee994) | Sep 22, 2024 |
| HP            | ZBook 15 G6                 | [edda518320](https://linux-hardware.org/?probe=edda518320) | Sep 17, 2024 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | [75f181c794](https://linux-hardware.org/?probe=75f181c794) | Sep 17, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | [e9442ac0ef](https://linux-hardware.org/?probe=e9442ac0ef) | Sep 13, 2024 |
| Lenovo        | ThinkPad T460s 20F9001DU... | [cbd5c6f4d1](https://linux-hardware.org/?probe=cbd5c6f4d1) | Sep 11, 2024 |
| Dell          | Precision M6500             | [f33e0f389f](https://linux-hardware.org/?probe=f33e0f389f) | Sep 10, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | [f12c5f1a0e](https://linux-hardware.org/?probe=f12c5f1a0e) | Sep 07, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [558e2441f3](https://linux-hardware.org/?probe=558e2441f3) | Sep 07, 2024 |
| Dell          | Precision M6500             | [d38f4f3a0d](https://linux-hardware.org/?probe=d38f4f3a0d) | Sep 04, 2024 |
| HP            | ProBook x360 11 G1 EE       | [c191463e94](https://linux-hardware.org/?probe=c191463e94) | Sep 03, 2024 |
| HUAWEI        | BOHB-WAX9                   | [7fd01bbf58](https://linux-hardware.org/?probe=7fd01bbf58) | Sep 03, 2024 |
| Lenovo        | ThinkPad T460s 20F9001DU... | [9fbc883284](https://linux-hardware.org/?probe=9fbc883284) | Sep 03, 2024 |
| MiTAC         | 9525                        | [dae6039353](https://linux-hardware.org/?probe=dae6039353) | Sep 01, 2024 |
| HP            | EliteBook 840 G2            | [70206460b9](https://linux-hardware.org/?probe=70206460b9) | Aug 31, 2024 |
| HP            | ZBook 14 G2                 | [7f0dc8a5ee](https://linux-hardware.org/?probe=7f0dc8a5ee) | Aug 30, 2024 |
| HP            | ZBook 14 G2                 | [0afb138cf7](https://linux-hardware.org/?probe=0afb138cf7) | Aug 30, 2024 |
| Samsung       | RV420/RV520/RV720/E3530/... | [4a96c956a3](https://linux-hardware.org/?probe=4a96c956a3) | Aug 25, 2024 |
| Lenovo        | B550 20053                  | [d7a362e8ae](https://linux-hardware.org/?probe=d7a362e8ae) | Aug 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [8ef075cdc6](https://linux-hardware.org/?probe=8ef075cdc6) | Aug 24, 2024 |
| Samsung       | RV420/RV520/RV720/E3530/... | [7e292e87db](https://linux-hardware.org/?probe=7e292e87db) | Aug 21, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [e06d0034c0](https://linux-hardware.org/?probe=e06d0034c0) | Aug 20, 2024 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [5af8f48189](https://linux-hardware.org/?probe=5af8f48189) | Aug 19, 2024 |
| MiTAC         | 9525                        | [1c218ead51](https://linux-hardware.org/?probe=1c218ead51) | Aug 17, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [625bb8784e](https://linux-hardware.org/?probe=625bb8784e) | Aug 15, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [19095098a9](https://linux-hardware.org/?probe=19095098a9) | Aug 15, 2024 |
| Toshiba       | Satellite C55D-B            | [abeade75bf](https://linux-hardware.org/?probe=abeade75bf) | Aug 07, 2024 |
| Toshiba       | Satellite C55D-B            | [32fc2acd15](https://linux-hardware.org/?probe=32fc2acd15) | Aug 06, 2024 |
| Dell          | Inspiron 5520               | [2b509a59ee](https://linux-hardware.org/?probe=2b509a59ee) | Aug 05, 2024 |
| HP            | Pavilion Laptop 15-cs3xx... | [694cfee657](https://linux-hardware.org/?probe=694cfee657) | Aug 03, 2024 |
| Dell          | Inspiron 5520               | [f9c0a1fd98](https://linux-hardware.org/?probe=f9c0a1fd98) | Aug 03, 2024 |
| Dell          | Inspiron 5520               | [96341f34a7](https://linux-hardware.org/?probe=96341f34a7) | Aug 03, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [15d899f5d6](https://linux-hardware.org/?probe=15d899f5d6) | Aug 01, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [3070972064](https://linux-hardware.org/?probe=3070972064) | Jul 30, 2024 |
| Toshiba       | Satellite C655D             | [e81fee8a6c](https://linux-hardware.org/?probe=e81fee8a6c) | Jul 29, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | [3141d6b0c5](https://linux-hardware.org/?probe=3141d6b0c5) | Jul 28, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | [e3fc443c3c](https://linux-hardware.org/?probe=e3fc443c3c) | Jul 28, 2024 |
| HP            | Pavilion 17                 | [059579abe8](https://linux-hardware.org/?probe=059579abe8) | Jul 25, 2024 |
| HP            | Notebook                    | [a1f1e83afe](https://linux-hardware.org/?probe=a1f1e83afe) | Jul 23, 2024 |
| HP            | 250 G7 Notebook PC          | [154385f06a](https://linux-hardware.org/?probe=154385f06a) | Jul 23, 2024 |
| HP            | Notebook                    | [1df59c0265](https://linux-hardware.org/?probe=1df59c0265) | Jul 23, 2024 |
| HP            | ProBook 450 G3              | [2bac99deff](https://linux-hardware.org/?probe=2bac99deff) | Jul 21, 2024 |
| Dell          | Inspiron 7577               | [414b4921b3](https://linux-hardware.org/?probe=414b4921b3) | Jul 21, 2024 |
| Dell          | Inspiron 7577               | [5cc826a584](https://linux-hardware.org/?probe=5cc826a584) | Jul 21, 2024 |
| Dell          | Inspiron 7577               | [1757077236](https://linux-hardware.org/?probe=1757077236) | Jul 21, 2024 |
| HP            | Pavilion Laptop 15-cs3xx... | [000b9c52ac](https://linux-hardware.org/?probe=000b9c52ac) | Jul 20, 2024 |
| Toshiba       | Satellite C850-C010         | [903cf22463](https://linux-hardware.org/?probe=903cf22463) | Jul 20, 2024 |
| Toshiba       | Satellite C850-C010         | [94ab3f5efb](https://linux-hardware.org/?probe=94ab3f5efb) | Jul 20, 2024 |
| Dell          | Latitude E6230              | [49a877be66](https://linux-hardware.org/?probe=49a877be66) | Jul 17, 2024 |
| Dell          | Latitude E6230              | [804f26874d](https://linux-hardware.org/?probe=804f26874d) | Jul 17, 2024 |
| Toshiba       | Satellite C870-D7K          | [448a44a1ec](https://linux-hardware.org/?probe=448a44a1ec) | Jul 14, 2024 |
| HP            | 250 G7 Notebook PC          | [38b439c526](https://linux-hardware.org/?probe=38b439c526) | Jul 06, 2024 |
| Dell          | Latitude E5520              | [c9c6c2b869](https://linux-hardware.org/?probe=c9c6c2b869) | Jul 04, 2024 |
| Dell          | Latitude 7480               | [b496b8fd50](https://linux-hardware.org/?probe=b496b8fd50) | Jul 02, 2024 |
| Dell          | Latitude 7480               | [a3c6aac33a](https://linux-hardware.org/?probe=a3c6aac33a) | Jul 02, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [4a6c68bf6a](https://linux-hardware.org/?probe=4a6c68bf6a) | Jun 28, 2024 |
| Lenovo        | V14-IIL 82C4                | [09ef0acf45](https://linux-hardware.org/?probe=09ef0acf45) | Jun 23, 2024 |
| HP            | Victus by Laptop 16-d1xx... | [25f65c8ddd](https://linux-hardware.org/?probe=25f65c8ddd) | Jun 20, 2024 |
| HP            | 350 G1                      | [26da241c3b](https://linux-hardware.org/?probe=26da241c3b) | Jun 15, 2024 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [3ece85e84e](https://linux-hardware.org/?probe=3ece85e84e) | Jun 04, 2024 |
| Dell          | Latitude E6410              | [ab1f6d2cd0](https://linux-hardware.org/?probe=ab1f6d2cd0) | Jun 03, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [e611c9b374](https://linux-hardware.org/?probe=e611c9b374) | Jun 02, 2024 |
| Dell          | Latitude 5495               | [4af3b4124d](https://linux-hardware.org/?probe=4af3b4124d) | Jun 02, 2024 |
| Dell          | Latitude 5495               | [ce25c22ac7](https://linux-hardware.org/?probe=ce25c22ac7) | Jun 02, 2024 |
| Dell          | Latitude 3520               | [63f78aa5ba](https://linux-hardware.org/?probe=63f78aa5ba) | May 24, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [ea24258471](https://linux-hardware.org/?probe=ea24258471) | May 22, 2024 |
| Acer          | Aspire A515-45G             | [2e3cf7fe5c](https://linux-hardware.org/?probe=2e3cf7fe5c) | May 18, 2024 |
| Lenovo        | ThinkPad P50 20EQS3B327     | [1d0eb1521b](https://linux-hardware.org/?probe=1d0eb1521b) | May 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [77f3080542](https://linux-hardware.org/?probe=77f3080542) | May 15, 2024 |
| Sony          | SVE1512D1RB                 | [07bdd1d315](https://linux-hardware.org/?probe=07bdd1d315) | May 12, 2024 |
| HP            | EliteBook 8560p             | [9f23553e6a](https://linux-hardware.org/?probe=9f23553e6a) | May 12, 2024 |
| Toshiba       | Satellite C55D-B            | [916a3269bb](https://linux-hardware.org/?probe=916a3269bb) | May 11, 2024 |
| Dell          | Latitude E5520              | [1c27a2760d](https://linux-hardware.org/?probe=1c27a2760d) | May 08, 2024 |
| HP            | ZBook 15 G3                 | [8fbd2e21a7](https://linux-hardware.org/?probe=8fbd2e21a7) | May 08, 2024 |
| HP            | EliteBook 745 G3            | [7eae46245c](https://linux-hardware.org/?probe=7eae46245c) | May 06, 2024 |
| Dell          | G15 5511                    | [8bb70e4a24](https://linux-hardware.org/?probe=8bb70e4a24) | May 04, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [0839696375](https://linux-hardware.org/?probe=0839696375) | May 04, 2024 |
| Dell          | Latitude E5520              | [0c2c1716be](https://linux-hardware.org/?probe=0c2c1716be) | May 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [06046f8679](https://linux-hardware.org/?probe=06046f8679) | Apr 30, 2024 |
| HP            | ZBook 15                    | [b5181afe2b](https://linux-hardware.org/?probe=b5181afe2b) | Apr 25, 2024 |
| HP            | Pavilion Notebook           | [0ed4e3a757](https://linux-hardware.org/?probe=0ed4e3a757) | Apr 24, 2024 |
| HP            | ProBook 645 G4              | [5e0b981c4f](https://linux-hardware.org/?probe=5e0b981c4f) | Apr 20, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [8f4cd3f89d](https://linux-hardware.org/?probe=8f4cd3f89d) | Apr 19, 2024 |
| Toshiba       | Satellite C55D-B            | [0d2ecb9207](https://linux-hardware.org/?probe=0d2ecb9207) | Apr 17, 2024 |
| Lenovo        | B590 20206                  | [e99c52e2f5](https://linux-hardware.org/?probe=e99c52e2f5) | Apr 16, 2024 |
| HP            | Pavilion 15                 | [e7d5a8c55a](https://linux-hardware.org/?probe=e7d5a8c55a) | Apr 14, 2024 |
| Dell          | Inspiron N5010              | [e820d6337a](https://linux-hardware.org/?probe=e820d6337a) | Apr 11, 2024 |
| HP            | ZBook 15 G5                 | [d8a1d4fd64](https://linux-hardware.org/?probe=d8a1d4fd64) | Apr 10, 2024 |
| Dell          | Inspiron N5010              | [7fe3c3fa19](https://linux-hardware.org/?probe=7fe3c3fa19) | Apr 09, 2024 |
| Dell          | G15 5511                    | [3493d65893](https://linux-hardware.org/?probe=3493d65893) | Apr 06, 2024 |
| Dell          | G15 5511                    | [98ba745e2f](https://linux-hardware.org/?probe=98ba745e2f) | Apr 06, 2024 |
| MSI           | Modern 14 B5M               | [0862e9e806](https://linux-hardware.org/?probe=0862e9e806) | Apr 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [21c028b980](https://linux-hardware.org/?probe=21c028b980) | Apr 02, 2024 |
| Apple         | MacBook10,1                 | [2da6005f10](https://linux-hardware.org/?probe=2da6005f10) | Apr 01, 2024 |
| Apple         | MacBook10,1                 | [36d6f74236](https://linux-hardware.org/?probe=36d6f74236) | Apr 01, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [900e722a10](https://linux-hardware.org/?probe=900e722a10) | Apr 01, 2024 |
| Dell          | Latitude E6540              | [cb66e3c3d1](https://linux-hardware.org/?probe=cb66e3c3d1) | Mar 26, 2024 |
| Lenovo        | ThinkPad E480 20KN0082AD    | [db9cb980a5](https://linux-hardware.org/?probe=db9cb980a5) | Mar 25, 2024 |
| HP            | Laptop 15-bs1xx             | [f341009f68](https://linux-hardware.org/?probe=f341009f68) | Mar 19, 2024 |
| HP            | Laptop 15-bs1xx             | [585d283a71](https://linux-hardware.org/?probe=585d283a71) | Mar 15, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [7a99f5e6bc](https://linux-hardware.org/?probe=7a99f5e6bc) | Mar 13, 2024 |
| Lenovo        | Legion Y540-15IRH 81SX      | [13aa71b72d](https://linux-hardware.org/?probe=13aa71b72d) | Mar 07, 2024 |
| HP            | ZBook 17 G3                 | [e69ebcea87](https://linux-hardware.org/?probe=e69ebcea87) | Mar 06, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [1446f9eae8](https://linux-hardware.org/?probe=1446f9eae8) | Mar 05, 2024 |
| Apple         | MacBookPro5,3               | [20e198611e](https://linux-hardware.org/?probe=20e198611e) | Mar 02, 2024 |
| HP            | ProBook 640 G2              | [70cfce9afd](https://linux-hardware.org/?probe=70cfce9afd) | Feb 28, 2024 |
| HUAWEI        | NBD-WXX9                    | [a3e7bc047a](https://linux-hardware.org/?probe=a3e7bc047a) | Feb 27, 2024 |
| HP            | ZBook 17 G3                 | [9b0019e8dd](https://linux-hardware.org/?probe=9b0019e8dd) | Feb 23, 2024 |
| HP            | 250 G8 Notebook PC          | [7ed42ddb2a](https://linux-hardware.org/?probe=7ed42ddb2a) | Feb 19, 2024 |
| HP            | 250 G8 Notebook PC          | [6e7ac3ec7e](https://linux-hardware.org/?probe=6e7ac3ec7e) | Feb 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [4bfbb106d2](https://linux-hardware.org/?probe=4bfbb106d2) | Feb 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [96859b01b7](https://linux-hardware.org/?probe=96859b01b7) | Feb 17, 2024 |
| Toshiba       | Satellite C660              | [6e9a9b6226](https://linux-hardware.org/?probe=6e9a9b6226) | Feb 17, 2024 |
| Toshiba       | Satellite C660              | [336464e94f](https://linux-hardware.org/?probe=336464e94f) | Feb 16, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [c1504decd1](https://linux-hardware.org/?probe=c1504decd1) | Feb 15, 2024 |
| HP            | ProBook 450 G4              | [25a3c438a1](https://linux-hardware.org/?probe=25a3c438a1) | Feb 13, 2024 |
| HP            | 215 G1                      | [52df684d4c](https://linux-hardware.org/?probe=52df684d4c) | Feb 05, 2024 |
| HP            | 215 G1                      | [c992749b63](https://linux-hardware.org/?probe=c992749b63) | Feb 05, 2024 |
| Acer          | Aspire A515-45G             | [4012edd9e1](https://linux-hardware.org/?probe=4012edd9e1) | Feb 04, 2024 |
| HUAWEI        | BOHB-WAX9                   | [8de0a1db50](https://linux-hardware.org/?probe=8de0a1db50) | Feb 04, 2024 |
| HUAWEI        | BOHB-WAX9                   | [e58ba87da3](https://linux-hardware.org/?probe=e58ba87da3) | Feb 04, 2024 |
| HP            | ZBook 15 G2                 | [2fe30cca38](https://linux-hardware.org/?probe=2fe30cca38) | Feb 03, 2024 |
| Dell          | Latitude 3420               | [15de060676](https://linux-hardware.org/?probe=15de060676) | Feb 02, 2024 |
| Dell          | Latitude E6420              | [ff73a45b61](https://linux-hardware.org/?probe=ff73a45b61) | Feb 01, 2024 |
| Dell          | Inspiron 5521               | [e9f2d87f0f](https://linux-hardware.org/?probe=e9f2d87f0f) | Jan 26, 2024 |
| Dell          | Inspiron 5521               | [1c9b6b485d](https://linux-hardware.org/?probe=1c9b6b485d) | Jan 26, 2024 |
| HP            | ProBook 645 G4              | [af6ac91f2a](https://linux-hardware.org/?probe=af6ac91f2a) | Jan 25, 2024 |
| HP            | Laptop 14-cf1xxx            | [b26a65cafd](https://linux-hardware.org/?probe=b26a65cafd) | Jan 16, 2024 |
| Acer          | Predator G9-592             | [67dd34e639](https://linux-hardware.org/?probe=67dd34e639) | Jan 16, 2024 |
| Acer          | Aspire A515-45G             | [9f83faffad](https://linux-hardware.org/?probe=9f83faffad) | Jan 14, 2024 |
| HP            | Victus by Gaming Laptop ... | [feaf3edd58](https://linux-hardware.org/?probe=feaf3edd58) | Jan 10, 2024 |
| Dell          | Inspiron 3593               | [e82da0cd29](https://linux-hardware.org/?probe=e82da0cd29) | Jan 05, 2024 |
| HP            | ZBook 15 G5                 | [7d1279f3ef](https://linux-hardware.org/?probe=7d1279f3ef) | Jan 04, 2024 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [7378a1bdb4](https://linux-hardware.org/?probe=7378a1bdb4) | Dec 27, 2023 |
| HP            | G62                         | [434b8aa389](https://linux-hardware.org/?probe=434b8aa389) | Dec 25, 2023 |
| Acer          | Predator PH317-53           | [fcc1b4896e](https://linux-hardware.org/?probe=fcc1b4896e) | Dec 25, 2023 |
| Acer          | Extensa 2519                | [29bc812d6d](https://linux-hardware.org/?probe=29bc812d6d) | Dec 23, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [1fff6e8409](https://linux-hardware.org/?probe=1fff6e8409) | Dec 20, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [5574b0048b](https://linux-hardware.org/?probe=5574b0048b) | Dec 16, 2023 |
| Dell          | Precision 5540              | [ff22e47089](https://linux-hardware.org/?probe=ff22e47089) | Dec 16, 2023 |
| Dell          | Latitude 5430               | [c105b5162b](https://linux-hardware.org/?probe=c105b5162b) | Dec 05, 2023 |
| Dell          | Latitude 5430               | [ed7195f601](https://linux-hardware.org/?probe=ed7195f601) | Dec 05, 2023 |
| Lenovo        | Legion 5 15ITH6H 82JH       | [fe13325e26](https://linux-hardware.org/?probe=fe13325e26) | Dec 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [a63677b9e1](https://linux-hardware.org/?probe=a63677b9e1) | Dec 03, 2023 |
| Acer          | Nitro AN515-58              | [eb52097d1b](https://linux-hardware.org/?probe=eb52097d1b) | Nov 29, 2023 |
| HP            | Laptop 15-bs0xx             | [beba27b952](https://linux-hardware.org/?probe=beba27b952) | Nov 28, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [ce1806eec5](https://linux-hardware.org/?probe=ce1806eec5) | Nov 26, 2023 |
| HP            | Laptop 15-bs0xx             | [e9bfd98ad2](https://linux-hardware.org/?probe=e9bfd98ad2) | Nov 26, 2023 |
| HP            | Unknown                     | [74afdb551a](https://linux-hardware.org/?probe=74afdb551a) | Nov 26, 2023 |
| HP            | Unknown                     | [6d4bc0aed6](https://linux-hardware.org/?probe=6d4bc0aed6) | Nov 26, 2023 |
| HP            | ProBook 450 G7              | [6e903b92f6](https://linux-hardware.org/?probe=6e903b92f6) | Nov 26, 2023 |
| Dell          | Inspiron 5537               | [ea362b85cf](https://linux-hardware.org/?probe=ea362b85cf) | Nov 25, 2023 |
| HP            | ProBook 450 G7              | [30edbbd6f0](https://linux-hardware.org/?probe=30edbbd6f0) | Nov 23, 2023 |
| Acer          | Nitro AN515-58              | [193588412a](https://linux-hardware.org/?probe=193588412a) | Nov 23, 2023 |
| Dell          | Latitude E5430 non-vPro     | [d277e32193](https://linux-hardware.org/?probe=d277e32193) | Nov 20, 2023 |
| HP            | ProBook 11 G2               | [72e5f7b707](https://linux-hardware.org/?probe=72e5f7b707) | Nov 19, 2023 |
| Acer          | Nitro AN515-58              | [29dc31d4de](https://linux-hardware.org/?probe=29dc31d4de) | Nov 16, 2023 |
| Acer          | Nitro AN515-58              | [b612f7a489](https://linux-hardware.org/?probe=b612f7a489) | Nov 16, 2023 |
| Dell          | Latitude E5430 non-vPro     | [3843b68ba8](https://linux-hardware.org/?probe=3843b68ba8) | Nov 15, 2023 |
| Acer          | Predator PH315-53           | [476a922e2f](https://linux-hardware.org/?probe=476a922e2f) | Nov 02, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [6efacfa5c8](https://linux-hardware.org/?probe=6efacfa5c8) | Nov 01, 2023 |
| Sony          | SVS15116GAB                 | [03634a7731](https://linux-hardware.org/?probe=03634a7731) | Oct 30, 2023 |
| Dell          | Latitude 5530               | [70ffc0b609](https://linux-hardware.org/?probe=70ffc0b609) | Oct 23, 2023 |
| Dell          | Latitude E5570              | [3c4a0eb291](https://linux-hardware.org/?probe=3c4a0eb291) | Oct 23, 2023 |
| Dell          | Precision M4800             | [1538f5153d](https://linux-hardware.org/?probe=1538f5153d) | Oct 19, 2023 |
| Dell          | Precision M4800             | [03012f2d54](https://linux-hardware.org/?probe=03012f2d54) | Oct 19, 2023 |
| Acer          | Nitro AN515-52              | [6ec1b6d812](https://linux-hardware.org/?probe=6ec1b6d812) | Oct 13, 2023 |
| Acer          | Nitro AN515-52              | [25433b6adb](https://linux-hardware.org/?probe=25433b6adb) | Oct 13, 2023 |
| Dell          | Precision 5530              | [2c19c2e063](https://linux-hardware.org/?probe=2c19c2e063) | Oct 12, 2023 |
| Lenovo        | ThinkPad T530 23594LU       | [b18b8f45a4](https://linux-hardware.org/?probe=b18b8f45a4) | Oct 11, 2023 |
| Dell          | Latitude E6520              | [cb7181f79f](https://linux-hardware.org/?probe=cb7181f79f) | Oct 05, 2023 |
| HP            | EliteBook 745 G3            | [a9e2c9b64e](https://linux-hardware.org/?probe=a9e2c9b64e) | Oct 03, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | [4fc3b1e588](https://linux-hardware.org/?probe=4fc3b1e588) | Oct 01, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | [01d6d4f3c4](https://linux-hardware.org/?probe=01d6d4f3c4) | Oct 01, 2023 |
| Dell          | Inspiron N5010              | [fe6b9d4c65](https://linux-hardware.org/?probe=fe6b9d4c65) | Oct 01, 2023 |
| HP            | EliteBook 745 G3            | [5cae9ddf98](https://linux-hardware.org/?probe=5cae9ddf98) | Sep 30, 2023 |
| HP            | EliteBook 745 G3            | [700c901144](https://linux-hardware.org/?probe=700c901144) | Sep 30, 2023 |
| HP            | EliteBook 745 G3            | [16f4068970](https://linux-hardware.org/?probe=16f4068970) | Sep 30, 2023 |
| Dell          | Latitude E6530              | [5fc5673815](https://linux-hardware.org/?probe=5fc5673815) | Sep 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | [ba269d8c4a](https://linux-hardware.org/?probe=ba269d8c4a) | Sep 29, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [c62002acdf](https://linux-hardware.org/?probe=c62002acdf) | Sep 25, 2023 |
| Dell          | Latitude E6520              | [734076d709](https://linux-hardware.org/?probe=734076d709) | Sep 23, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [966f802eb6](https://linux-hardware.org/?probe=966f802eb6) | Sep 21, 2023 |
| Toshiba       | PORTEGE M750                | [1c3442d87f](https://linux-hardware.org/?probe=1c3442d87f) | Sep 14, 2023 |
| HP            | ProBook 645 G1              | [ced1631b20](https://linux-hardware.org/?probe=ced1631b20) | Sep 11, 2023 |
| HP            | ProBook 645 G1              | [e78c297114](https://linux-hardware.org/?probe=e78c297114) | Sep 10, 2023 |
| ASUSTek       | TP500LN                     | [d90f472bcf](https://linux-hardware.org/?probe=d90f472bcf) | Sep 09, 2023 |
| MSI           | Modern 14 B11MOU            | [239c2bbc02](https://linux-hardware.org/?probe=239c2bbc02) | Sep 02, 2023 |
| HP            | Laptop 15-da1xxx            | [ad844f1a8c](https://linux-hardware.org/?probe=ad844f1a8c) | Aug 30, 2023 |
| HP            | Laptop 15-da1xxx            | [0c279f8cf0](https://linux-hardware.org/?probe=0c279f8cf0) | Aug 30, 2023 |
| HP            | 350 G1                      | [1e317e5a51](https://linux-hardware.org/?probe=1e317e5a51) | Aug 30, 2023 |
| HP            | 350 G1                      | [d800790bce](https://linux-hardware.org/?probe=d800790bce) | Aug 28, 2023 |
| HP            | EliteBook 8440p             | [89e74082d8](https://linux-hardware.org/?probe=89e74082d8) | Aug 23, 2023 |
| Acer          | Aspire 5750G                | [205a407b60](https://linux-hardware.org/?probe=205a407b60) | Aug 21, 2023 |
| HP            | G62                         | [778c1c04b9](https://linux-hardware.org/?probe=778c1c04b9) | Aug 19, 2023 |
| Dell          | Inspiron 5570               | [3771669b84](https://linux-hardware.org/?probe=3771669b84) | Aug 10, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [d3999a626a](https://linux-hardware.org/?probe=d3999a626a) | Aug 07, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [32c2f39f3a](https://linux-hardware.org/?probe=32c2f39f3a) | Aug 06, 2023 |
| Dell          | Inspiron 3558               | [5331913f13](https://linux-hardware.org/?probe=5331913f13) | Aug 04, 2023 |
| Toshiba       | Satellite C855D             | [4835e837bd](https://linux-hardware.org/?probe=4835e837bd) | Aug 03, 2023 |
| HP            | ProBook 6475b               | [c3cfc235fe](https://linux-hardware.org/?probe=c3cfc235fe) | Aug 01, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [ad721ddbad](https://linux-hardware.org/?probe=ad721ddbad) | Jul 31, 2023 |
| Dell          | Vostro 15 3515              | [08990a8da3](https://linux-hardware.org/?probe=08990a8da3) | Jul 28, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [8abec746f7](https://linux-hardware.org/?probe=8abec746f7) | Jul 19, 2023 |
| Dell          | Inspiron N4050              | [42ddc0425b](https://linux-hardware.org/?probe=42ddc0425b) | Jul 19, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [8e533f69a9](https://linux-hardware.org/?probe=8e533f69a9) | Jul 19, 2023 |
| Fujitsu Si... | LIFEBOOK E8310              | [0093aba5fd](https://linux-hardware.org/?probe=0093aba5fd) | Jul 16, 2023 |
| HP            | Unknown                     | [e36ee407e4](https://linux-hardware.org/?probe=e36ee407e4) | Jul 12, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [5d4cb4e73a](https://linux-hardware.org/?probe=5d4cb4e73a) | Jul 03, 2023 |
| HP            | Laptop 15-dw3xxx            | [3fe182f682](https://linux-hardware.org/?probe=3fe182f682) | Jul 02, 2023 |
| HP            | Laptop 15-dw3xxx            | [587f8b6b83](https://linux-hardware.org/?probe=587f8b6b83) | Jul 01, 2023 |
| Razer         | Blade 16 - RZ09-0483        | [9f1f9757a2](https://linux-hardware.org/?probe=9f1f9757a2) | Jun 25, 2023 |
| Razer         | Blade 16 - RZ09-0483        | [7d8f0212e9](https://linux-hardware.org/?probe=7d8f0212e9) | Jun 24, 2023 |
| HP            | EliteBook 8540w             | [6d8c00ff02](https://linux-hardware.org/?probe=6d8c00ff02) | Jun 23, 2023 |
| HP            | EliteBook 8540w             | [1c1a2724f4](https://linux-hardware.org/?probe=1c1a2724f4) | Jun 23, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [d4da1625e2](https://linux-hardware.org/?probe=d4da1625e2) | Jun 12, 2023 |
| Lenovo        | G580 ChiefRiver Platform    | [ac48eeb92c](https://linux-hardware.org/?probe=ac48eeb92c) | Jun 10, 2023 |
| Lenovo        | G580 ChiefRiver Platform    | [ade15528d8](https://linux-hardware.org/?probe=ade15528d8) | Jun 10, 2023 |
| Lenovo        | Yoga 500-14ISK 80R5         | [2b1a1d3e39](https://linux-hardware.org/?probe=2b1a1d3e39) | Jun 07, 2023 |
| Lenovo        | Yoga 500-14ISK 80R5         | [3308d91565](https://linux-hardware.org/?probe=3308d91565) | Jun 07, 2023 |
| Dell          | Vostro 15 3515              | [8a69d6c123](https://linux-hardware.org/?probe=8a69d6c123) | Jun 01, 2023 |
| Dell          | Vostro 15 3515              | [ecfe7565f4](https://linux-hardware.org/?probe=ecfe7565f4) | Jun 01, 2023 |
| Dell          | Vostro 15 3515              | [2fadb86df4](https://linux-hardware.org/?probe=2fadb86df4) | May 27, 2023 |
| HP            | EliteBook 8440p             | [cbcea9cc58](https://linux-hardware.org/?probe=cbcea9cc58) | May 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [dedcc1bb3f](https://linux-hardware.org/?probe=dedcc1bb3f) | May 22, 2023 |
| Dell          | Inspiron N4050              | [ec1357e74e](https://linux-hardware.org/?probe=ec1357e74e) | May 20, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [7ab850285a](https://linux-hardware.org/?probe=7ab850285a) | May 14, 2023 |
| Lenovo        | V14-IIL 82C4                | [3ff6a3dac0](https://linux-hardware.org/?probe=3ff6a3dac0) | May 06, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [483415e8cb](https://linux-hardware.org/?probe=483415e8cb) | May 05, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [3ab78594e3](https://linux-hardware.org/?probe=3ab78594e3) | May 02, 2023 |
| HP            | Unknown                     | [475eb33956](https://linux-hardware.org/?probe=475eb33956) | May 01, 2023 |
| Lenovo        | ThinkPad X220 429044U       | [1bf66ba9be](https://linux-hardware.org/?probe=1bf66ba9be) | Apr 26, 2023 |
| HP            | EliteBook 2730p             | [51c0fadfdb](https://linux-hardware.org/?probe=51c0fadfdb) | Apr 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [7d3b6ba1a3](https://linux-hardware.org/?probe=7d3b6ba1a3) | Apr 25, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [43aae4850b](https://linux-hardware.org/?probe=43aae4850b) | Apr 23, 2023 |
| HP            | Notebook                    | [36788985ec](https://linux-hardware.org/?probe=36788985ec) | Apr 20, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [b1c04430cc](https://linux-hardware.org/?probe=b1c04430cc) | Apr 19, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [b2873d15a0](https://linux-hardware.org/?probe=b2873d15a0) | Apr 19, 2023 |
| HP            | Notebook                    | [072fc2bf12](https://linux-hardware.org/?probe=072fc2bf12) | Apr 19, 2023 |
| HP            | Laptop 15s-eq2xxx           | [6fae9a24fb](https://linux-hardware.org/?probe=6fae9a24fb) | Apr 19, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [c33ef2ceeb](https://linux-hardware.org/?probe=c33ef2ceeb) | Apr 11, 2023 |
| HP            | Laptop 15-bs0xx             | [c73108de7b](https://linux-hardware.org/?probe=c73108de7b) | Apr 06, 2023 |
| Dell          | Latitude 7350               | [9bdfad0684](https://linux-hardware.org/?probe=9bdfad0684) | Apr 06, 2023 |
| Lenovo        | ThinkPad T530 23594LU       | [9de89fee19](https://linux-hardware.org/?probe=9de89fee19) | Apr 01, 2023 |
| Dell          | Vostro 15 3515              | [7b4a51d5e3](https://linux-hardware.org/?probe=7b4a51d5e3) | Mar 29, 2023 |
| Dell          | Latitude 7350               | [de44a7d43c](https://linux-hardware.org/?probe=de44a7d43c) | Mar 28, 2023 |
| HP            | Compaq 610                  | [dc9383200e](https://linux-hardware.org/?probe=dc9383200e) | Mar 28, 2023 |
| Dell          | Latitude 7350               | [8ef24a8281](https://linux-hardware.org/?probe=8ef24a8281) | Mar 28, 2023 |
| Dell          | Latitude E6430              | [912e5e8577](https://linux-hardware.org/?probe=912e5e8577) | Mar 26, 2023 |
| Dell          | Latitude E6430              | [237dabb566](https://linux-hardware.org/?probe=237dabb566) | Mar 26, 2023 |
| HP            | 250 G4                      | [e0ff721413](https://linux-hardware.org/?probe=e0ff721413) | Mar 23, 2023 |
| Lenovo        | S20-30 20421                | [3c1dd3564d](https://linux-hardware.org/?probe=3c1dd3564d) | Mar 19, 2023 |
| Dell          | G5 5500                     | [f9b3b5d852](https://linux-hardware.org/?probe=f9b3b5d852) | Mar 19, 2023 |
| Dell          | G3 3579                     | [e548fa074e](https://linux-hardware.org/?probe=e548fa074e) | Mar 14, 2023 |
| Dell          | Inspiron N4050              | [3b1827fe4f](https://linux-hardware.org/?probe=3b1827fe4f) | Mar 13, 2023 |
| HUAWEI        | BOD-WXX9                    | [74452c1274](https://linux-hardware.org/?probe=74452c1274) | Mar 13, 2023 |
| Dell          | Latitude 5420               | [948cbeda59](https://linux-hardware.org/?probe=948cbeda59) | Feb 23, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [8043264215](https://linux-hardware.org/?probe=8043264215) | Feb 16, 2023 |
| HP            | ProBook 450 G3              | [9d060a9cc6](https://linux-hardware.org/?probe=9d060a9cc6) | Feb 15, 2023 |
| HP            | ProBook 450 G3              | [0cbe95253a](https://linux-hardware.org/?probe=0cbe95253a) | Feb 15, 2023 |
| Dell          | G3 3579                     | [4721b18608](https://linux-hardware.org/?probe=4721b18608) | Feb 09, 2023 |
| HP            | Compaq Presario CQ61        | [df4d59acd5](https://linux-hardware.org/?probe=df4d59acd5) | Feb 07, 2023 |
| Fujitsu Si... | LIFEBOOK E8310              | [bc685693a6](https://linux-hardware.org/?probe=bc685693a6) | Jan 30, 2023 |
| Dell          | Inspiron 3580               | [e049beb54a](https://linux-hardware.org/?probe=e049beb54a) | Jan 28, 2023 |
| Lenovo        | Z51-70 80K6                 | [c083024afa](https://linux-hardware.org/?probe=c083024afa) | Jan 25, 2023 |
| Dell          | G15 5511                    | [cea8996d31](https://linux-hardware.org/?probe=cea8996d31) | Jan 23, 2023 |
| Dell          | Latitude 5580               | [9cfd456bd4](https://linux-hardware.org/?probe=9cfd456bd4) | Jan 22, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7b36d7e8eb](https://linux-hardware.org/?probe=7b36d7e8eb) | Jan 17, 2023 |
| Acer          | Nitro AN515-55              | [58db914ce7](https://linux-hardware.org/?probe=58db914ce7) | Jan 14, 2023 |
| Acer          | Nitro AN515-55              | [85969e813b](https://linux-hardware.org/?probe=85969e813b) | Jan 13, 2023 |
| HP            | Laptop 15-bs0xx             | [3cd650450c](https://linux-hardware.org/?probe=3cd650450c) | Jan 12, 2023 |
| Dell          | Inspiron N4050              | [9464593531](https://linux-hardware.org/?probe=9464593531) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [eab4c8b296](https://linux-hardware.org/?probe=eab4c8b296) | Jan 06, 2023 |
| Lenovo        | Z51-70 80K6                 | [7fff20462c](https://linux-hardware.org/?probe=7fff20462c) | Jan 03, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [7474151c7e](https://linux-hardware.org/?probe=7474151c7e) | Jan 01, 2023 |
| HP            | Pavilion 15                 | [956866bbdd](https://linux-hardware.org/?probe=956866bbdd) | Dec 29, 2022 |
| HP            | Laptop 15-bs0xx             | [3d50b74a6b](https://linux-hardware.org/?probe=3d50b74a6b) | Dec 23, 2022 |
| Apple         | MacBookAir7,2               | [00e62a7231](https://linux-hardware.org/?probe=00e62a7231) | Dec 23, 2022 |
| Dell          | Latitude E7470              | [2894205731](https://linux-hardware.org/?probe=2894205731) | Dec 19, 2022 |
| Dell          | Latitude 5580               | [c8b402d4df](https://linux-hardware.org/?probe=c8b402d4df) | Dec 18, 2022 |
| Dell          | Latitude 5580               | [b45e1798cc](https://linux-hardware.org/?probe=b45e1798cc) | Dec 18, 2022 |
| HP            | 15                          | [95f40991cc](https://linux-hardware.org/?probe=95f40991cc) | Dec 18, 2022 |
| HP            | EliteBook 840 G5            | [2c57417bdf](https://linux-hardware.org/?probe=2c57417bdf) | Dec 16, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [52a8f66027](https://linux-hardware.org/?probe=52a8f66027) | Dec 10, 2022 |
| Lenovo        | Z50-70 20354                | [07bf98d8f7](https://linux-hardware.org/?probe=07bf98d8f7) | Dec 07, 2022 |
| HP            | Laptop 15s-eq2xxx           | [686afd3c20](https://linux-hardware.org/?probe=686afd3c20) | Dec 02, 2022 |
| HP            | EliteBook 745 G3            | [6c7a9e7fe5](https://linux-hardware.org/?probe=6c7a9e7fe5) | Nov 25, 2022 |
| HP            | ENVY m6                     | [cb48bbdcc1](https://linux-hardware.org/?probe=cb48bbdcc1) | Nov 25, 2022 |
| HP            | EliteBook 820 G4            | [d4ed3112e5](https://linux-hardware.org/?probe=d4ed3112e5) | Nov 21, 2022 |
| HP            | EliteBook 820 G4            | [c565a2d0fc](https://linux-hardware.org/?probe=c565a2d0fc) | Nov 21, 2022 |
| Lenovo        | Legion 5 15ARH7H 82RD       | [cba7abe277](https://linux-hardware.org/?probe=cba7abe277) | Nov 20, 2022 |
| Dell          | Inspiron 3593               | [f5c9f5e8e1](https://linux-hardware.org/?probe=f5c9f5e8e1) | Nov 19, 2022 |
| Lenovo        | IdeaPad Z470                | [bc0980a6df](https://linux-hardware.org/?probe=bc0980a6df) | Nov 16, 2022 |
| Hampoo        | Cherry Trail CR             | [ae8d0b2d8e](https://linux-hardware.org/?probe=ae8d0b2d8e) | Nov 13, 2022 |
| Dell          | Latitude D630               | [ef49631a3c](https://linux-hardware.org/?probe=ef49631a3c) | Nov 12, 2022 |
| Samsung       | 275E4E/275E5E               | [0eba8cf68e](https://linux-hardware.org/?probe=0eba8cf68e) | Nov 09, 2022 |
| Dell          | Precision 5520              | [a96e7097e1](https://linux-hardware.org/?probe=a96e7097e1) | Nov 03, 2022 |
| MSI           | Summit E13FlipEvo A12MT     | [8575548418](https://linux-hardware.org/?probe=8575548418) | Oct 28, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [38c23f070a](https://linux-hardware.org/?probe=38c23f070a) | Oct 27, 2022 |
| Dell          | Latitude E7270              | [7c249e55c8](https://linux-hardware.org/?probe=7c249e55c8) | Oct 27, 2022 |
| HP            | Notebook                    | [d713217453](https://linux-hardware.org/?probe=d713217453) | Oct 23, 2022 |
| HP            | Notebook                    | [ef9adb0e8a](https://linux-hardware.org/?probe=ef9adb0e8a) | Oct 22, 2022 |
| HP            | EliteBook 755 G5            | [b1550ee8e1](https://linux-hardware.org/?probe=b1550ee8e1) | Oct 22, 2022 |
| Dell          | G15 5510                    | [1286ecf9dd](https://linux-hardware.org/?probe=1286ecf9dd) | Oct 18, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [a360479032](https://linux-hardware.org/?probe=a360479032) | Oct 15, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [72e2c65863](https://linux-hardware.org/?probe=72e2c65863) | Oct 13, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [792528e3b2](https://linux-hardware.org/?probe=792528e3b2) | Oct 10, 2022 |
| Dell          | Inspiron 3521               | [f6e7e1585c](https://linux-hardware.org/?probe=f6e7e1585c) | Oct 10, 2022 |
| Dell          | Inspiron 3521               | [0b225367b8](https://linux-hardware.org/?probe=0b225367b8) | Oct 08, 2022 |
| Sony          | VPCEH3LFX                   | [fbb59e09fc](https://linux-hardware.org/?probe=fbb59e09fc) | Oct 07, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [f02e3f9e3b](https://linux-hardware.org/?probe=f02e3f9e3b) | Oct 04, 2022 |
| HP            | ENVY m6                     | [5c828496a7](https://linux-hardware.org/?probe=5c828496a7) | Oct 04, 2022 |
| HP            | Notebook                    | [a30c1af9a5](https://linux-hardware.org/?probe=a30c1af9a5) | Sep 30, 2022 |
| ASUSTek       | ROG Strix G531GW_G531GW     | [113f7431d5](https://linux-hardware.org/?probe=113f7431d5) | Sep 28, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [cf8fefa8b5](https://linux-hardware.org/?probe=cf8fefa8b5) | Sep 28, 2022 |
| ASUSTek       | ROG Strix G531GW_G531GW     | [d0f2ed977a](https://linux-hardware.org/?probe=d0f2ed977a) | Sep 28, 2022 |
| Dell          | Inspiron N5110              | [eff6424aa4](https://linux-hardware.org/?probe=eff6424aa4) | Sep 26, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [3f9e2bb677](https://linux-hardware.org/?probe=3f9e2bb677) | Sep 23, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [10103bf87f](https://linux-hardware.org/?probe=10103bf87f) | Sep 23, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [56bff32d34](https://linux-hardware.org/?probe=56bff32d34) | Sep 21, 2022 |
| Dell          | Latitude 3540               | [7e56d744b7](https://linux-hardware.org/?probe=7e56d744b7) | Sep 21, 2022 |
| Dell          | Latitude 3540               | [0216f52b36](https://linux-hardware.org/?probe=0216f52b36) | Sep 21, 2022 |
| Lenovo        | ThinkPad Edge 0578JJG       | [fef4bc54eb](https://linux-hardware.org/?probe=fef4bc54eb) | Sep 20, 2022 |
| Lenovo        | ThinkPad Edge 0578JJG       | [db6bdb0dbd](https://linux-hardware.org/?probe=db6bdb0dbd) | Sep 20, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [e91328a3c2](https://linux-hardware.org/?probe=e91328a3c2) | Sep 20, 2022 |
| Dell          | Inspiron 5521               | [085558878e](https://linux-hardware.org/?probe=085558878e) | Sep 20, 2022 |
| Samsung       | Lumpy                       | [9c1fd4f253](https://linux-hardware.org/?probe=9c1fd4f253) | Sep 18, 2022 |
| Samsung       | Lumpy                       | [1ea9c40a42](https://linux-hardware.org/?probe=1ea9c40a42) | Sep 15, 2022 |
| ASUSTek       | X555LD                      | [12d6e02796](https://linux-hardware.org/?probe=12d6e02796) | Sep 15, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0356a8d7a1](https://linux-hardware.org/?probe=0356a8d7a1) | Sep 05, 2022 |
| HP            | Pavilion 15                 | [ed8a48954e](https://linux-hardware.org/?probe=ed8a48954e) | Sep 04, 2022 |
| Dell          | G15 5510                    | [fbcdd4d274](https://linux-hardware.org/?probe=fbcdd4d274) | Sep 03, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [93980a32fc](https://linux-hardware.org/?probe=93980a32fc) | Sep 02, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [e5545fc36a](https://linux-hardware.org/?probe=e5545fc36a) | Aug 30, 2022 |
| HP            | EliteBook 8560w             | [0ea43b9010](https://linux-hardware.org/?probe=0ea43b9010) | Aug 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [77a2156c5a](https://linux-hardware.org/?probe=77a2156c5a) | Aug 21, 2022 |
| HP            | ProBook 655 G1              | [e37e59a165](https://linux-hardware.org/?probe=e37e59a165) | Aug 20, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [78ff8418f9](https://linux-hardware.org/?probe=78ff8418f9) | Aug 17, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [c62eb0135b](https://linux-hardware.org/?probe=c62eb0135b) | Aug 15, 2022 |
| HP            | EliteBook 8560w             | [86b3f33331](https://linux-hardware.org/?probe=86b3f33331) | Aug 14, 2022 |
| HP            | EliteBook 8560w             | [4ea7538e24](https://linux-hardware.org/?probe=4ea7538e24) | Aug 14, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e97781a7cc](https://linux-hardware.org/?probe=e97781a7cc) | Aug 11, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [abe7afa30f](https://linux-hardware.org/?probe=abe7afa30f) | Aug 09, 2022 |
| Lenovo        | V15-ADA 82C7                | [5b7d298ca6](https://linux-hardware.org/?probe=5b7d298ca6) | Aug 08, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [e0403fe18f](https://linux-hardware.org/?probe=e0403fe18f) | Aug 08, 2022 |
| Toshiba       | NB250                       | [e320782bcf](https://linux-hardware.org/?probe=e320782bcf) | Jul 30, 2022 |
| HP            | G62                         | [dd114592c4](https://linux-hardware.org/?probe=dd114592c4) | Jul 27, 2022 |
| MSI           | MS-14Y1                     | [782beac866](https://linux-hardware.org/?probe=782beac866) | Jul 18, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [5510f2d904](https://linux-hardware.org/?probe=5510f2d904) | Jul 18, 2022 |
| Panasonic     | FZG1-3                      | [753cc1d311](https://linux-hardware.org/?probe=753cc1d311) | Jul 10, 2022 |
| Panasonic     | FZG1-3                      | [01d4651376](https://linux-hardware.org/?probe=01d4651376) | Jul 10, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [1f42376321](https://linux-hardware.org/?probe=1f42376321) | Jul 09, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [977cf239f9](https://linux-hardware.org/?probe=977cf239f9) | Jul 08, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [b1d77e2a01](https://linux-hardware.org/?probe=b1d77e2a01) | Jul 05, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [8e2249c595](https://linux-hardware.org/?probe=8e2249c595) | Jul 05, 2022 |
| HP            | EliteBook 840 G4            | [342facf96e](https://linux-hardware.org/?probe=342facf96e) | Jul 04, 2022 |
| HP            | Pavilion 15                 | [e35e3b2e52](https://linux-hardware.org/?probe=e35e3b2e52) | Jul 01, 2022 |
| HP            | Pavilion 15                 | [f76f8dff7a](https://linux-hardware.org/?probe=f76f8dff7a) | Jun 30, 2022 |
| HP            | ProBook 645 G1              | [1157ee7e3a](https://linux-hardware.org/?probe=1157ee7e3a) | Jun 21, 2022 |
| ASUSTek       | X555LJ                      | [ee2a9b3c87](https://linux-hardware.org/?probe=ee2a9b3c87) | Jun 20, 2022 |
| Dell          | G5 5587                     | [9f2ca6b48b](https://linux-hardware.org/?probe=9f2ca6b48b) | Jun 18, 2022 |
| Lenovo        | B40-80 80F6                 | [7449f0f8d2](https://linux-hardware.org/?probe=7449f0f8d2) | Jun 13, 2022 |
| HP            | ProBook 445 G7              | [f41d413820](https://linux-hardware.org/?probe=f41d413820) | Jun 13, 2022 |
| ASUSTek       | X553MA                      | [1794b92b61](https://linux-hardware.org/?probe=1794b92b61) | Jun 12, 2022 |
| Dell          | Latitude E6410              | [184348232a](https://linux-hardware.org/?probe=184348232a) | Jun 11, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [9a3948a7e8](https://linux-hardware.org/?probe=9a3948a7e8) | May 23, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [2e520c1e13](https://linux-hardware.org/?probe=2e520c1e13) | May 23, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [9be915450d](https://linux-hardware.org/?probe=9be915450d) | May 23, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [4058369652](https://linux-hardware.org/?probe=4058369652) | May 21, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [bd33528d52](https://linux-hardware.org/?probe=bd33528d52) | May 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f512156dc8](https://linux-hardware.org/?probe=f512156dc8) | May 16, 2022 |
| HP            | Pavilion 15                 | [a18593bb5b](https://linux-hardware.org/?probe=a18593bb5b) | May 07, 2022 |
| Dell          | Inspiron N4050              | [6d8f615203](https://linux-hardware.org/?probe=6d8f615203) | Apr 30, 2022 |
| Dell          | Inspiron N5110              | [fb1248d6be](https://linux-hardware.org/?probe=fb1248d6be) | Apr 29, 2022 |
| HP            | Pavilion 15                 | [fee7e96d70](https://linux-hardware.org/?probe=fee7e96d70) | Apr 28, 2022 |
| Fujitsu       | FMVA06004                   | [4c63e1bcc2](https://linux-hardware.org/?probe=4c63e1bcc2) | Apr 25, 2022 |
| Dell          | Latitude 3440               | [a0c0358f78](https://linux-hardware.org/?probe=a0c0358f78) | Apr 24, 2022 |
| HP            | Laptop 15-bs0xx             | [a1636896d9](https://linux-hardware.org/?probe=a1636896d9) | Apr 22, 2022 |
| HP            | Laptop 15-bs0xx             | [03481a94b3](https://linux-hardware.org/?probe=03481a94b3) | Apr 22, 2022 |
| HP            | 15                          | [3253e0fc56](https://linux-hardware.org/?probe=3253e0fc56) | Apr 21, 2022 |
| Sony          | SVT1121B2EW                 | [dd43f45353](https://linux-hardware.org/?probe=dd43f45353) | Apr 21, 2022 |
| Dell          | Inspiron 7577               | [6843f2bcfe](https://linux-hardware.org/?probe=6843f2bcfe) | Apr 20, 2022 |
| Alienware     | 17                          | [b9b420077c](https://linux-hardware.org/?probe=b9b420077c) | Apr 14, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [fecdd237a4](https://linux-hardware.org/?probe=fecdd237a4) | Apr 11, 2022 |
| Lenovo        | Flex 2-14 20404             | [4368114931](https://linux-hardware.org/?probe=4368114931) | Apr 04, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [f93e8f46c2](https://linux-hardware.org/?probe=f93e8f46c2) | Apr 01, 2022 |
| HP            | Laptop 15-bs0xx             | [bd875807ce](https://linux-hardware.org/?probe=bd875807ce) | Mar 26, 2022 |
| HP            | Laptop 15-bs0xx             | [96f9ba743f](https://linux-hardware.org/?probe=96f9ba743f) | Mar 25, 2022 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [55a2911462](https://linux-hardware.org/?probe=55a2911462) | Mar 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [e4b8a2cc11](https://linux-hardware.org/?probe=e4b8a2cc11) | Mar 23, 2022 |
| HP            | Notebook                    | [4cc8a23994](https://linux-hardware.org/?probe=4cc8a23994) | Mar 22, 2022 |
| HP            | Notebook                    | [cb2c910f05](https://linux-hardware.org/?probe=cb2c910f05) | Mar 22, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [64baae5b88](https://linux-hardware.org/?probe=64baae5b88) | Mar 22, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [99dc5cde41](https://linux-hardware.org/?probe=99dc5cde41) | Mar 20, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d74cd69ff9](https://linux-hardware.org/?probe=d74cd69ff9) | Mar 20, 2022 |
| HP            | Pavilion 15                 | [0f3cb22c3d](https://linux-hardware.org/?probe=0f3cb22c3d) | Mar 20, 2022 |
| HP            | G62                         | [5a5a9ce935](https://linux-hardware.org/?probe=5a5a9ce935) | Mar 20, 2022 |
| HP            | ENVY dv6                    | [39ff0aa86d](https://linux-hardware.org/?probe=39ff0aa86d) | Mar 17, 2022 |
| Dell          | Latitude 3410               | [d21a10beb4](https://linux-hardware.org/?probe=d21a10beb4) | Mar 10, 2022 |
| Acer          | Aspire ES1-331              | [cbba045d50](https://linux-hardware.org/?probe=cbba045d50) | Mar 05, 2022 |
| HP            | Pavilion Notebook           | [57bb50b654](https://linux-hardware.org/?probe=57bb50b654) | Feb 27, 2022 |
| Dell          | Venue 10 Pro 5056           | [faf162367f](https://linux-hardware.org/?probe=faf162367f) | Feb 25, 2022 |
| HP            | Laptop 15-db0xxx            | [732784f9ec](https://linux-hardware.org/?probe=732784f9ec) | Feb 25, 2022 |
| HP            | EliteBook 745 G3            | [2c3ac58820](https://linux-hardware.org/?probe=2c3ac58820) | Feb 25, 2022 |
| HP            | EliteBook 745 G3            | [eed2589bd2](https://linux-hardware.org/?probe=eed2589bd2) | Feb 25, 2022 |
| HP            | ENVY dv6                    | [6d07aead9f](https://linux-hardware.org/?probe=6d07aead9f) | Feb 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c907453bf5](https://linux-hardware.org/?probe=c907453bf5) | Feb 18, 2022 |
| Dell          | G3 3500                     | [0010596573](https://linux-hardware.org/?probe=0010596573) | Feb 10, 2022 |
| Dell          | Latitude E6540              | [9129341c42](https://linux-hardware.org/?probe=9129341c42) | Jan 24, 2022 |
| HP            | ProBook 445 G7              | [bceca55120](https://linux-hardware.org/?probe=bceca55120) | Jan 23, 2022 |
| Sony          | SVF15328CXB                 | [d55d8f394d](https://linux-hardware.org/?probe=d55d8f394d) | Jan 21, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [dfbb7c034f](https://linux-hardware.org/?probe=dfbb7c034f) | Jan 20, 2022 |
| HP            | 250 G7 Notebook PC          | [6da1d84e76](https://linux-hardware.org/?probe=6da1d84e76) | Jan 16, 2022 |
| Dell          | Inspiron N5010              | [4edc707b67](https://linux-hardware.org/?probe=4edc707b67) | Jan 14, 2022 |
| HP            | EliteBook 8440p             | [b70942532f](https://linux-hardware.org/?probe=b70942532f) | Jan 04, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [00f8c9d649](https://linux-hardware.org/?probe=00f8c9d649) | Jan 02, 2022 |
| HP            | EliteBook 8440p             | [bda1b240c9](https://linux-hardware.org/?probe=bda1b240c9) | Dec 28, 2021 |
| Dell          | G15 5510                    | [1209f0844f](https://linux-hardware.org/?probe=1209f0844f) | Dec 20, 2021 |
| Dell          | G15 5510                    | [e5039b3b7d](https://linux-hardware.org/?probe=e5039b3b7d) | Dec 18, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [f8dc028352](https://linux-hardware.org/?probe=f8dc028352) | Dec 08, 2021 |
| HP            | Compaq CQ58                 | [dd578dae69](https://linux-hardware.org/?probe=dd578dae69) | Dec 05, 2021 |
| HP            | Compaq CQ58                 | [d15350584d](https://linux-hardware.org/?probe=d15350584d) | Dec 05, 2021 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [d6acd43784](https://linux-hardware.org/?probe=d6acd43784) | Nov 25, 2021 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [e820cb3456](https://linux-hardware.org/?probe=e820cb3456) | Nov 25, 2021 |
| HP            | ProBook 470 G3              | [49f973804a](https://linux-hardware.org/?probe=49f973804a) | Nov 13, 2021 |
| Dell          | Latitude 5420               | [973018da2b](https://linux-hardware.org/?probe=973018da2b) | Nov 08, 2021 |
| Dell          | Inspiron 3537               | [eacb69d71e](https://linux-hardware.org/?probe=eacb69d71e) | Nov 05, 2021 |
| Lenovo        | ThinkPad E14 20RAS0CM00     | [a35aaaeb6d](https://linux-hardware.org/?probe=a35aaaeb6d) | Oct 31, 2021 |
| HP            | 255 G7 Notebook PC          | [e8781db5ab](https://linux-hardware.org/?probe=e8781db5ab) | Oct 31, 2021 |
| HP            | 255 G7 Notebook PC          | [e1978d5164](https://linux-hardware.org/?probe=e1978d5164) | Oct 31, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [08d287d2e2](https://linux-hardware.org/?probe=08d287d2e2) | Oct 30, 2021 |
| HP            | ProBook 6460b               | [317c62df4b](https://linux-hardware.org/?probe=317c62df4b) | Oct 23, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [85036968bb](https://linux-hardware.org/?probe=85036968bb) | Oct 20, 2021 |
| HP            | ProBook 450 G7              | [2db5d6dc7c](https://linux-hardware.org/?probe=2db5d6dc7c) | Oct 20, 2021 |
| HP            | ProBook 450 G7              | [1faf3f28e5](https://linux-hardware.org/?probe=1faf3f28e5) | Oct 20, 2021 |
| Dell          | Inspiron 3521               | [831fff897a](https://linux-hardware.org/?probe=831fff897a) | Oct 15, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d69772c626](https://linux-hardware.org/?probe=d69772c626) | Oct 14, 2021 |
| Lenovo        | ThinkPad E15 20RD0086ED     | [2db7f4be45](https://linux-hardware.org/?probe=2db7f4be45) | Oct 13, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [e8ae6d00a2](https://linux-hardware.org/?probe=e8ae6d00a2) | Oct 12, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [d0fb953c7e](https://linux-hardware.org/?probe=d0fb953c7e) | Oct 11, 2021 |
| HP            | ProBook 645 G1              | [102902cf2b](https://linux-hardware.org/?probe=102902cf2b) | Oct 10, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [51d51a675d](https://linux-hardware.org/?probe=51d51a675d) | Oct 10, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [f8d957d29f](https://linux-hardware.org/?probe=f8d957d29f) | Oct 09, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [6c5495590b](https://linux-hardware.org/?probe=6c5495590b) | Oct 08, 2021 |
| Hampoo        | Cherry Trail CR             | [b95391e679](https://linux-hardware.org/?probe=b95391e679) | Oct 03, 2021 |
| Hampoo        | Cherry Trail CR             | [61c4dc2ac2](https://linux-hardware.org/?probe=61c4dc2ac2) | Oct 03, 2021 |
| ASUSTek       | N501JW                      | [0e37d3409d](https://linux-hardware.org/?probe=0e37d3409d) | Oct 01, 2021 |
| Dell          | Inspiron 5584               | [48b4af3338](https://linux-hardware.org/?probe=48b4af3338) | Sep 01, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [d2e64a8d57](https://linux-hardware.org/?probe=d2e64a8d57) | Aug 08, 2021 |
| HP            | Compaq 2510p                | [ea3c7d2fe2](https://linux-hardware.org/?probe=ea3c7d2fe2) | Aug 07, 2021 |
| HP            | Compaq 2510p                | [31449a4b42](https://linux-hardware.org/?probe=31449a4b42) | Aug 07, 2021 |
| Packard Be... | EasyNote LX                 | [125ad979fe](https://linux-hardware.org/?probe=125ad979fe) | Aug 06, 2021 |
| Dell          | G3 3579                     | [4f7539c771](https://linux-hardware.org/?probe=4f7539c771) | Jul 30, 2021 |
| Dell          | Inspiron 1564               | [08fc5f3b99](https://linux-hardware.org/?probe=08fc5f3b99) | Jul 27, 2021 |
| Dell          | Inspiron 5570               | [b07887acc1](https://linux-hardware.org/?probe=b07887acc1) | Jul 18, 2021 |
| Lenovo        | G510 20238                  | [428dcd6503](https://linux-hardware.org/?probe=428dcd6503) | Jul 07, 2021 |
| Dell          | G3 3579                     | [97c520db01](https://linux-hardware.org/?probe=97c520db01) | Jul 04, 2021 |
| ASUSTek       | X200MA                      | [c9edeec38a](https://linux-hardware.org/?probe=c9edeec38a) | Jun 26, 2021 |
| Dell          | Inspiron 1545               | [8c7ef2bc15](https://linux-hardware.org/?probe=8c7ef2bc15) | Jun 20, 2021 |
| Dell          | Inspiron 1545               | [4c397b8b70](https://linux-hardware.org/?probe=4c397b8b70) | Jun 20, 2021 |
| HP            | Pro x2 612 G1 Tablet        | [05dbeca379](https://linux-hardware.org/?probe=05dbeca379) | Jun 17, 2021 |
| HP            | Pro x2 612 G1 Tablet        | [f685842bb1](https://linux-hardware.org/?probe=f685842bb1) | Jun 16, 2021 |
| HP            | Pro x2 612 G1 Tablet        | [696a1c9564](https://linux-hardware.org/?probe=696a1c9564) | Jun 13, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [e57c2fb16d](https://linux-hardware.org/?probe=e57c2fb16d) | May 30, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [976e39384a](https://linux-hardware.org/?probe=976e39384a) | May 30, 2021 |
| HP            | ProBook 645 G1              | [a92458c2db](https://linux-hardware.org/?probe=a92458c2db) | May 26, 2021 |
| Fujitsu       | LIFEBOOK S752               | [6ae217a5a8](https://linux-hardware.org/?probe=6ae217a5a8) | May 21, 2021 |
| Dell          | G5 5587                     | [fae808ae7d](https://linux-hardware.org/?probe=fae808ae7d) | May 02, 2021 |
| HP            | Notebook                    | [872a5f9112](https://linux-hardware.org/?probe=872a5f9112) | Apr 18, 2021 |
| Hampoo        | Cherry Trail CR             | [101c47c9a2](https://linux-hardware.org/?probe=101c47c9a2) | Apr 17, 2021 |
| Fujitsu Si... | AMILO Li1705                | [3200f41cf0](https://linux-hardware.org/?probe=3200f41cf0) | Apr 13, 2021 |
| HP            | 15                          | [27bcfc6f15](https://linux-hardware.org/?probe=27bcfc6f15) | Apr 10, 2021 |
| HP            | 15                          | [aebfb75282](https://linux-hardware.org/?probe=aebfb75282) | Apr 10, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [2c17afdb0a](https://linux-hardware.org/?probe=2c17afdb0a) | Apr 08, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [820db16b30](https://linux-hardware.org/?probe=820db16b30) | Apr 08, 2021 |
| Dell          | Inspiron 3580               | [fcb5ccbc6c](https://linux-hardware.org/?probe=fcb5ccbc6c) | Apr 08, 2021 |
| Dell          | Inspiron 7577               | [a3ecba2a79](https://linux-hardware.org/?probe=a3ecba2a79) | Apr 06, 2021 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [bb1ef328b0](https://linux-hardware.org/?probe=bb1ef328b0) | Mar 30, 2021 |
| HP            | Unknown                     | [984ec41c5f](https://linux-hardware.org/?probe=984ec41c5f) | Mar 28, 2021 |
| HP            | Pavilion dv6                | [ecb76b364b](https://linux-hardware.org/?probe=ecb76b364b) | Mar 20, 2021 |
| Lenovo        | ThinkPad X250 20CM003WMS    | [9dbe8f6250](https://linux-hardware.org/?probe=9dbe8f6250) | Mar 12, 2021 |
| TECNO         | WinPad 10A                  | [e96bf0a4fa](https://linux-hardware.org/?probe=e96bf0a4fa) | Mar 08, 2021 |
| Lenovo        | AILZx                       | [b0c93e5b27](https://linux-hardware.org/?probe=b0c93e5b27) | Mar 07, 2021 |
| Lenovo        | AILZx                       | [d06410a1dd](https://linux-hardware.org/?probe=d06410a1dd) | Mar 04, 2021 |
| Lenovo        | AILZx                       | [cf1bc93ffd](https://linux-hardware.org/?probe=cf1bc93ffd) | Mar 04, 2021 |
| Lenovo        | G50-80 80E5                 | [5ba97fc0d2](https://linux-hardware.org/?probe=5ba97fc0d2) | Mar 03, 2021 |
| HP            | EliteBook 8470p             | [586d9baf41](https://linux-hardware.org/?probe=586d9baf41) | Feb 25, 2021 |
| HP            | EliteBook 8470p             | [f22c5da52d](https://linux-hardware.org/?probe=f22c5da52d) | Feb 25, 2021 |
| Dell          | Inspiron 5570               | [4fd5f831b6](https://linux-hardware.org/?probe=4fd5f831b6) | Feb 22, 2021 |
| Dell          | Latitude XT3                | [2335b761fb](https://linux-hardware.org/?probe=2335b761fb) | Feb 16, 2021 |
| HP            | 250 G3                      | [67cb272c8e](https://linux-hardware.org/?probe=67cb272c8e) | Feb 14, 2021 |
| Dell          | Latitude XT3                | [94f5a1f396](https://linux-hardware.org/?probe=94f5a1f396) | Feb 13, 2021 |
| HP            | Laptop 15-da1xxx            | [6472781079](https://linux-hardware.org/?probe=6472781079) | Feb 09, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [fdfa43b360](https://linux-hardware.org/?probe=fdfa43b360) | Feb 01, 2021 |
| HP            | ProBook 450 G7              | [7e3a962336](https://linux-hardware.org/?probe=7e3a962336) | Jan 31, 2021 |
| Lenovo        | G50-80 80E5                 | [9072c5e554](https://linux-hardware.org/?probe=9072c5e554) | Jan 29, 2021 |
| HP            | Pavilion dv6                | [55752483ef](https://linux-hardware.org/?probe=55752483ef) | Jan 25, 2021 |
| Lenovo        | ThinkPad T580 20LAS09100    | [92d071729f](https://linux-hardware.org/?probe=92d071729f) | Jan 22, 2021 |
| HP            | Laptop 15-da1xxx            | [e596928019](https://linux-hardware.org/?probe=e596928019) | Jan 22, 2021 |
| HP            | Laptop 15-da1xxx            | [8b2119a584](https://linux-hardware.org/?probe=8b2119a584) | Jan 22, 2021 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [bdfeee2839](https://linux-hardware.org/?probe=bdfeee2839) | Jan 21, 2021 |
| Dell          | G3 3590                     | [27fb9a0695](https://linux-hardware.org/?probe=27fb9a0695) | Jan 12, 2021 |
| HP            | Pavilion dv6                | [dbf279a62e](https://linux-hardware.org/?probe=dbf279a62e) | Jan 07, 2021 |
| HP            | Pavilion dv6                | [f14ce7c7c0](https://linux-hardware.org/?probe=f14ce7c7c0) | Jan 07, 2021 |
| Dell          | Inspiron 5520               | [a8f7f002a3](https://linux-hardware.org/?probe=a8f7f002a3) | Jan 06, 2021 |
| Dell          | Inspiron 7577               | [09ee69f73b](https://linux-hardware.org/?probe=09ee69f73b) | Jan 05, 2021 |
| HP            | ZBook 15 G2                 | [062d9c02f6](https://linux-hardware.org/?probe=062d9c02f6) | Jan 03, 2021 |
| HP            | Pavilion dv6                | [d18c93f636](https://linux-hardware.org/?probe=d18c93f636) | Dec 31, 2020 |
| HP            | Pavilion dv6                | [0a288440a6](https://linux-hardware.org/?probe=0a288440a6) | Dec 31, 2020 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [1262d56db8](https://linux-hardware.org/?probe=1262d56db8) | Dec 30, 2020 |
| Dell          | Latitude E6400              | [9f5ac2d658](https://linux-hardware.org/?probe=9f5ac2d658) | Dec 30, 2020 |
| Toshiba       | Satellite C660              | [054d224782](https://linux-hardware.org/?probe=054d224782) | Dec 25, 2020 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [7038da6d94](https://linux-hardware.org/?probe=7038da6d94) | Dec 25, 2020 |
| Apple         | MacBookPro5,3               | [29542ce3fc](https://linux-hardware.org/?probe=29542ce3fc) | Dec 23, 2020 |
| Lenovo        | ThinkPad E15 20RD001HAD     | [4f6e684aa1](https://linux-hardware.org/?probe=4f6e684aa1) | Dec 22, 2020 |
| HP            | Pavilion g6                 | [172d4abbd7](https://linux-hardware.org/?probe=172d4abbd7) | Dec 19, 2020 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [9d4e1e6361](https://linux-hardware.org/?probe=9d4e1e6361) | Dec 17, 2020 |
| HP            | ProBook 4540s               | [a35b479f53](https://linux-hardware.org/?probe=a35b479f53) | Dec 09, 2020 |
| HP            | ZBook 15                    | [f7f246578a](https://linux-hardware.org/?probe=f7f246578a) | Dec 07, 2020 |
| ASUSTek       | X455LD                      | [9e5d7995ce](https://linux-hardware.org/?probe=9e5d7995ce) | Dec 03, 2020 |
| Lenovo        | ThinkPad T580 20LAS09100    | [d5a8abcbc5](https://linux-hardware.org/?probe=d5a8abcbc5) | Dec 01, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [c9204a3c7d](https://linux-hardware.org/?probe=c9204a3c7d) | Nov 22, 2020 |
| Fujitsu       | LIFEBOOK S752               | [db7eb29112](https://linux-hardware.org/?probe=db7eb29112) | Nov 22, 2020 |
| I-Life Dig... | ZED AIR 2                   | [74f5e7c221](https://linux-hardware.org/?probe=74f5e7c221) | Nov 20, 2020 |
| I-Life Dig... | ZED AIR 2                   | [04802ac1cb](https://linux-hardware.org/?probe=04802ac1cb) | Nov 20, 2020 |
| HP            | ZBook 15                    | [9adafc3a81](https://linux-hardware.org/?probe=9adafc3a81) | Nov 19, 2020 |
| Dell          | Inspiron 7577               | [c09f7df61e](https://linux-hardware.org/?probe=c09f7df61e) | Nov 18, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [630b92e4d0](https://linux-hardware.org/?probe=630b92e4d0) | Nov 18, 2020 |
| HP            | EliteBook 2570p             | [3d005c24b6](https://linux-hardware.org/?probe=3d005c24b6) | Nov 17, 2020 |
| HP            | ProBook 450 G7              | [907aebb56a](https://linux-hardware.org/?probe=907aebb56a) | Nov 16, 2020 |
| HP            | EliteBook 745 G3            | [ec87278338](https://linux-hardware.org/?probe=ec87278338) | Nov 14, 2020 |
| HP            | EliteBook 850 G1            | [0b7205d523](https://linux-hardware.org/?probe=0b7205d523) | Nov 13, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [cee12c5d76](https://linux-hardware.org/?probe=cee12c5d76) | Nov 09, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b5aff9926a](https://linux-hardware.org/?probe=b5aff9926a) | Nov 09, 2020 |
| HP            | Pavilion g6                 | [a1e12ac11a](https://linux-hardware.org/?probe=a1e12ac11a) | Nov 07, 2020 |
| HP            | Pavilion g6                 | [c9fef7b025](https://linux-hardware.org/?probe=c9fef7b025) | Nov 07, 2020 |
| Dell          | Latitude 3590               | [6a285d94b7](https://linux-hardware.org/?probe=6a285d94b7) | Nov 02, 2020 |
| Dell          | Latitude E5570              | [ba5361df9e](https://linux-hardware.org/?probe=ba5361df9e) | Oct 29, 2020 |
| Dell          | G5 5587                     | [14789ef506](https://linux-hardware.org/?probe=14789ef506) | Oct 27, 2020 |
| Dell          | G5 5587                     | [414f6ca570](https://linux-hardware.org/?probe=414f6ca570) | Oct 27, 2020 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [3810f22dfc](https://linux-hardware.org/?probe=3810f22dfc) | Oct 23, 2020 |
| Dell          | Inspiron 5570               | [b7c7ae8b8b](https://linux-hardware.org/?probe=b7c7ae8b8b) | Oct 17, 2020 |
| HP            | Laptop 15-da1xxx            | [8e58300f1c](https://linux-hardware.org/?probe=8e58300f1c) | Oct 17, 2020 |
| HP            | ProBook 450 G7              | [e6c4e6ff27](https://linux-hardware.org/?probe=e6c4e6ff27) | Oct 15, 2020 |
| Lenovo        | Legion Y540-15IRH 81SX      | [59bbdc5626](https://linux-hardware.org/?probe=59bbdc5626) | Oct 14, 2020 |
| HP            | ProBook 450 G7              | [1722d6f45f](https://linux-hardware.org/?probe=1722d6f45f) | Oct 13, 2020 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | [9a361154cb](https://linux-hardware.org/?probe=9a361154cb) | Oct 11, 2020 |
| HP            | EliteBook 840 G1            | [8d775d0fba](https://linux-hardware.org/?probe=8d775d0fba) | Oct 07, 2020 |
| HP            | EliteBook 840 G1            | [0f22425e10](https://linux-hardware.org/?probe=0f22425e10) | Oct 07, 2020 |
| Lenovo        | IdeaPad 530S-15IKB 81EV     | [68e8da08fa](https://linux-hardware.org/?probe=68e8da08fa) | Oct 06, 2020 |
| HP            | ProBook 645 G1              | [6a95a69346](https://linux-hardware.org/?probe=6a95a69346) | Oct 04, 2020 |
| HP            | ProBook 645 G1              | [fc81852ffb](https://linux-hardware.org/?probe=fc81852ffb) | Oct 04, 2020 |
| ASUSTek       | G53SW                       | [cb9eb22047](https://linux-hardware.org/?probe=cb9eb22047) | Oct 02, 2020 |
| HP            | Laptop 15-da1xxx            | [6e17f92f25](https://linux-hardware.org/?probe=6e17f92f25) | Sep 30, 2020 |
| HP            | Laptop 15-da1xxx            | [839f278908](https://linux-hardware.org/?probe=839f278908) | Sep 30, 2020 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [e22e757c8c](https://linux-hardware.org/?probe=e22e757c8c) | Sep 23, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [105d229822](https://linux-hardware.org/?probe=105d229822) | Sep 17, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [4d46200fc3](https://linux-hardware.org/?probe=4d46200fc3) | Sep 17, 2020 |
| ASUSTek       | X580VN                      | [cdd3998e5d](https://linux-hardware.org/?probe=cdd3998e5d) | Sep 12, 2020 |
| ASUSTek       | X580VN                      | [02de9a38ac](https://linux-hardware.org/?probe=02de9a38ac) | Sep 12, 2020 |
| HP            | ProBook 645 G1              | [0a888dfc64](https://linux-hardware.org/?probe=0a888dfc64) | Sep 12, 2020 |
| HP            | ZBook 15 G2                 | [29083832b1](https://linux-hardware.org/?probe=29083832b1) | Aug 22, 2020 |
| HP            | EliteBook 725 G2            | [f9f5c68624](https://linux-hardware.org/?probe=f9f5c68624) | Aug 22, 2020 |
| Dell          | Inspiron 3543               | [82f88ee681](https://linux-hardware.org/?probe=82f88ee681) | Aug 09, 2020 |
| Dell          | G5 5587                     | [ff9bde0012](https://linux-hardware.org/?probe=ff9bde0012) | Aug 06, 2020 |
| Dell          | G5 5587                     | [0f1718b1a5](https://linux-hardware.org/?probe=0f1718b1a5) | Aug 03, 2020 |
| HP            | EliteBook 745 G3            | [0107343e87](https://linux-hardware.org/?probe=0107343e87) | Aug 02, 2020 |
| Dell          | Latitude 7400               | [bb45d9a55f](https://linux-hardware.org/?probe=bb45d9a55f) | Jul 31, 2020 |
| Dell          | Inspiron 7577               | [3ed23397a7](https://linux-hardware.org/?probe=3ed23397a7) | Jul 30, 2020 |
| HP            | ZBook 15 G3                 | [5bd1b54d12](https://linux-hardware.org/?probe=5bd1b54d12) | Jul 28, 2020 |
| Dell          | Inspiron 3593               | [51ed8b0103](https://linux-hardware.org/?probe=51ed8b0103) | Jul 28, 2020 |
| Lenovo        | ThinkPad E420 1141D7G       | [f599cd92cd](https://linux-hardware.org/?probe=f599cd92cd) | Jul 27, 2020 |
| HP            | ZBook 15 G3                 | [81dd1b462b](https://linux-hardware.org/?probe=81dd1b462b) | Jul 26, 2020 |
| Lenovo        | ThinkPad E580 20KS0008AD    | [5e0f6c1dce](https://linux-hardware.org/?probe=5e0f6c1dce) | Jul 26, 2020 |
| Lenovo        | ThinkPad E420 1141D7G       | [f24dee8f72](https://linux-hardware.org/?probe=f24dee8f72) | Jul 24, 2020 |
| HP            | EliteBook 850 G5            | [56cf19c251](https://linux-hardware.org/?probe=56cf19c251) | Jul 18, 2020 |
| Dell          | Inspiron 5570               | [3d66bcb580](https://linux-hardware.org/?probe=3d66bcb580) | Jul 15, 2020 |
| HP            | EliteBook 840 G2            | [a2a8e9d267](https://linux-hardware.org/?probe=a2a8e9d267) | Jul 13, 2020 |
| Dell          | Inspiron 1525               | [754b2de717](https://linux-hardware.org/?probe=754b2de717) | Jun 27, 2020 |
| Lenovo        | G555 0873                   | [6a79c9f57b](https://linux-hardware.org/?probe=6a79c9f57b) | Jun 26, 2020 |
| Dell          | Inspiron 5559               | [3b7aa38697](https://linux-hardware.org/?probe=3b7aa38697) | Jun 24, 2020 |
| Dell          | Inspiron 5559               | [bf6cda0ab3](https://linux-hardware.org/?probe=bf6cda0ab3) | Jun 24, 2020 |
| Lenovo        | Y50-70 20378                | [f9ef75ee84](https://linux-hardware.org/?probe=f9ef75ee84) | Jun 23, 2020 |
| Dell          | Inspiron 5559               | [bd3ec8d031](https://linux-hardware.org/?probe=bd3ec8d031) | Jun 23, 2020 |
| Dell          | Inspiron 5559               | [bb181efab0](https://linux-hardware.org/?probe=bb181efab0) | Jun 22, 2020 |
| Dell          | Inspiron 5559               | [5cad704188](https://linux-hardware.org/?probe=5cad704188) | Jun 22, 2020 |
| Lenovo        | ThinkPad E480 20KN0082AD    | [f8743f8e7c](https://linux-hardware.org/?probe=f8743f8e7c) | Jun 03, 2020 |
| Acer          | Aspire 5253                 | [7951613e3c](https://linux-hardware.org/?probe=7951613e3c) | Jun 02, 2020 |
| Lenovo        | Z50-70 20354                | [474b3dc645](https://linux-hardware.org/?probe=474b3dc645) | Jun 01, 2020 |
| HP            | G60                         | [36393e3df7](https://linux-hardware.org/?probe=36393e3df7) | May 30, 2020 |
| Dell          | Latitude E5570              | [52fe4fa81d](https://linux-hardware.org/?probe=52fe4fa81d) | May 27, 2020 |
| Packard Be... | EasyNote TJ75               | [3e4f50b818](https://linux-hardware.org/?probe=3e4f50b818) | May 18, 2020 |
| Lenovo        | G555 0873                   | [80cd03a651](https://linux-hardware.org/?probe=80cd03a651) | May 17, 2020 |
| Lenovo        | G555 0873                   | [0c8aa224f6](https://linux-hardware.org/?probe=0c8aa224f6) | May 17, 2020 |
| Lenovo        | G50-70 20351                | [49f0886269](https://linux-hardware.org/?probe=49f0886269) | May 15, 2020 |
| Lenovo        | G50-70 20351                | [261ecd7cd3](https://linux-hardware.org/?probe=261ecd7cd3) | May 15, 2020 |
| HP            | Pavilion g4                 | [d72a853f70](https://linux-hardware.org/?probe=d72a853f70) | May 15, 2020 |
| MSI           | GS65 Stealth Thin 8RE       | [567c197788](https://linux-hardware.org/?probe=567c197788) | May 14, 2020 |
| HP            | ProBook 450 G1              | [d2f086da96](https://linux-hardware.org/?probe=d2f086da96) | May 13, 2020 |
| Dell          | G3 3579                     | [1391477c00](https://linux-hardware.org/?probe=1391477c00) | May 11, 2020 |
| Dell          | G3 3779                     | [8adf43a503](https://linux-hardware.org/?probe=8adf43a503) | May 05, 2020 |
| Dell          | Inspiron 3521               | [bdb886a73d](https://linux-hardware.org/?probe=bdb886a73d) | May 05, 2020 |
| HP            | Pavilion g4                 | [8dec145194](https://linux-hardware.org/?probe=8dec145194) | May 05, 2020 |
| Toshiba       | Satellite L850-A894         | [4cff22692a](https://linux-hardware.org/?probe=4cff22692a) | Apr 26, 2020 |
| Toshiba       | Satellite L850-A894         | [c6bd4ae874](https://linux-hardware.org/?probe=c6bd4ae874) | Apr 26, 2020 |
| Dell          | Inspiron 5583               | [73ad84a03c](https://linux-hardware.org/?probe=73ad84a03c) | Apr 22, 2020 |
| Dell          | G5 5587                     | [56485e9db4](https://linux-hardware.org/?probe=56485e9db4) | Apr 22, 2020 |
| Toshiba       | Satellite A300              | [cb33489db5](https://linux-hardware.org/?probe=cb33489db5) | Apr 18, 2020 |
| Toshiba       | Satellite A300              | [e39b380b81](https://linux-hardware.org/?probe=e39b380b81) | Apr 18, 2020 |
| Dell          | Inspiron 3543               | [165bdbdf8b](https://linux-hardware.org/?probe=165bdbdf8b) | Apr 09, 2020 |
| Acer          | Aspire E5-475G              | [a8a037650e](https://linux-hardware.org/?probe=a8a037650e) | Apr 05, 2020 |
| Toshiba       | Satellite C850D-B810        | [bfa7a5b4b3](https://linux-hardware.org/?probe=bfa7a5b4b3) | Apr 04, 2020 |
| Toshiba       | Satellite C850D-B810        | [d911f2bb34](https://linux-hardware.org/?probe=d911f2bb34) | Apr 04, 2020 |
| HP            | Pavilion dv6                | [5a16417e7b](https://linux-hardware.org/?probe=5a16417e7b) | Apr 04, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [c6657af4bd](https://linux-hardware.org/?probe=c6657af4bd) | Mar 29, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [2645325565](https://linux-hardware.org/?probe=2645325565) | Mar 29, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [b90d909930](https://linux-hardware.org/?probe=b90d909930) | Mar 28, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [3aa7a0e126](https://linux-hardware.org/?probe=3aa7a0e126) | Mar 27, 2020 |
| HP            | Pavilion dv7                | [6f801c5209](https://linux-hardware.org/?probe=6f801c5209) | Mar 20, 2020 |
| Dell          | Inspiron 3593               | [f7f247e8c5](https://linux-hardware.org/?probe=f7f247e8c5) | Mar 19, 2020 |
| Lenovo        | ThinkPad SL410 0616A44      | [2c3f83610d](https://linux-hardware.org/?probe=2c3f83610d) | Mar 04, 2020 |
| Lenovo        | Y50-70 20378                | [d4389ea7a1](https://linux-hardware.org/?probe=d4389ea7a1) | Feb 23, 2020 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [435f7d1017](https://linux-hardware.org/?probe=435f7d1017) | Feb 21, 2020 |
| Dell          | Inspiron N4050              | [9808803a9a](https://linux-hardware.org/?probe=9808803a9a) | Feb 07, 2020 |
| Dell          | Inspiron N4050              | [bd16699d67](https://linux-hardware.org/?probe=bd16699d67) | Feb 07, 2020 |
| Dell          | Inspiron 5570               | [101d794bd2](https://linux-hardware.org/?probe=101d794bd2) | Jan 30, 2020 |
| Dell          | Inspiron N5110              | [975cffd2a7](https://linux-hardware.org/?probe=975cffd2a7) | Jan 17, 2020 |
| Dell          | Inspiron N5110              | [d08a0ed65d](https://linux-hardware.org/?probe=d08a0ed65d) | Jan 16, 2020 |
| Lenovo        | ThinkPad E590 20NB0002AD    | [0fc61e3795](https://linux-hardware.org/?probe=0fc61e3795) | Jan 13, 2020 |
| HP            | EliteBook 745 G4            | [99937a33e7](https://linux-hardware.org/?probe=99937a33e7) | Jan 05, 2020 |
| ASUSTek       | X540UA                      | [714b86d8a5](https://linux-hardware.org/?probe=714b86d8a5) | Dec 31, 2019 |
| Dell          | Inspiron 5570               | [92a06ce5da](https://linux-hardware.org/?probe=92a06ce5da) | Dec 31, 2019 |
| HP            | Pavilion dv7                | [9091bfdcb2](https://linux-hardware.org/?probe=9091bfdcb2) | Dec 13, 2019 |
| Dell          | Inspiron 15-3567            | [ddc251a8e0](https://linux-hardware.org/?probe=ddc251a8e0) | Dec 07, 2019 |
| Dell          | Inspiron 3542               | [38da710325](https://linux-hardware.org/?probe=38da710325) | Dec 01, 2019 |
| Lenovo        | IdeaPad Z510 20287          | [19294a1943](https://linux-hardware.org/?probe=19294a1943) | Nov 29, 2019 |
| Dell          | Inspiron 15-3567            | [ba36a0ae04](https://linux-hardware.org/?probe=ba36a0ae04) | Nov 27, 2019 |
| Dell          | Inspiron 15-3567            | [a93aff23bf](https://linux-hardware.org/?probe=a93aff23bf) | Nov 24, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [8f75febf6c](https://linux-hardware.org/?probe=8f75febf6c) | Nov 23, 2019 |
| HP            | Pavilion dv7                | [0261873b10](https://linux-hardware.org/?probe=0261873b10) | Nov 22, 2019 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [3054eabefb](https://linux-hardware.org/?probe=3054eabefb) | Nov 20, 2019 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [62081db5d0](https://linux-hardware.org/?probe=62081db5d0) | Nov 20, 2019 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [6ed324d188](https://linux-hardware.org/?probe=6ed324d188) | Nov 20, 2019 |
| HP            | Pavilion dv7                | [ab5fc8d0ac](https://linux-hardware.org/?probe=ab5fc8d0ac) | Nov 15, 2019 |
| Dell          | Inspiron 3543               | [5d228450e9](https://linux-hardware.org/?probe=5d228450e9) | Nov 11, 2019 |
| HP            | Pavilion dv7                | [41305d675a](https://linux-hardware.org/?probe=41305d675a) | Nov 09, 2019 |
| HP            | Pavilion dv7                | [6031485dd2](https://linux-hardware.org/?probe=6031485dd2) | Nov 08, 2019 |
| Lenovo        | ThinkPad T420 4178CXG       | [70105ff0ab](https://linux-hardware.org/?probe=70105ff0ab) | Nov 03, 2019 |
| Lenovo        | ThinkPad L460 20FVS0ER00    | [713a72e731](https://linux-hardware.org/?probe=713a72e731) | Oct 31, 2019 |
| HP            | ProBook 450 G4              | [e11bd3882e](https://linux-hardware.org/?probe=e11bd3882e) | Oct 22, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [677874b570](https://linux-hardware.org/?probe=677874b570) | Oct 18, 2019 |
| HP            | ProBook 450 G2              | [d8532c559a](https://linux-hardware.org/?probe=d8532c559a) | Sep 18, 2019 |
| Dell          | Inspiron N5010              | [fb490db7bf](https://linux-hardware.org/?probe=fb490db7bf) | Sep 09, 2019 |
| Dell          | Inspiron N5010              | [993460ba08](https://linux-hardware.org/?probe=993460ba08) | Sep 09, 2019 |
| MSI           | GL62 7QF                    | [4d0dbc5874](https://linux-hardware.org/?probe=4d0dbc5874) | Aug 30, 2019 |
| MSI           | GL62 7QF                    | [e508053ff2](https://linux-hardware.org/?probe=e508053ff2) | Aug 29, 2019 |
| Dell          | G3 3579                     | [ddcae43a95](https://linux-hardware.org/?probe=ddcae43a95) | Aug 24, 2019 |
| Dell          | Latitude E6440              | [c9fc484b61](https://linux-hardware.org/?probe=c9fc484b61) | Aug 20, 2019 |
| Dell          | Latitude E6440              | [f153be7930](https://linux-hardware.org/?probe=f153be7930) | Aug 20, 2019 |
| HP            | Pavilion dv7                | [d2006e7a87](https://linux-hardware.org/?probe=d2006e7a87) | Jul 27, 2019 |
| Toshiba       | Satellite C850-B341         | [acd80fad4b](https://linux-hardware.org/?probe=acd80fad4b) | Jul 20, 2019 |
| Acer          | Aspire A315-21              | [ea1580c609](https://linux-hardware.org/?probe=ea1580c609) | Jul 01, 2019 |
| Dell          | Inspiron 5559               | [4cbf20a7cf](https://linux-hardware.org/?probe=4cbf20a7cf) | Jun 18, 2019 |
| Lenovo        | ThinkPad T410 2522N18       | [9ab11256e2](https://linux-hardware.org/?probe=9ab11256e2) | Jun 16, 2019 |
| Acer          | Aspire E5-576G              | [119e4e5705](https://linux-hardware.org/?probe=119e4e5705) | Jun 06, 2019 |
| Lenovo        | Yoga 300-11IBY 80M0         | [0d944086c2](https://linux-hardware.org/?probe=0d944086c2) | Jun 04, 2019 |
| HP            | Laptop 15-bs1xx             | [47b56cee05](https://linux-hardware.org/?probe=47b56cee05) | May 25, 2019 |
| HP            | EliteBook 840 G1            | [fb72c7a17e](https://linux-hardware.org/?probe=fb72c7a17e) | May 22, 2019 |
| HP            | EliteBook 840 G1            | [8cc7613eb4](https://linux-hardware.org/?probe=8cc7613eb4) | May 22, 2019 |
| Dell          | Inspiron 3576               | [e86a5c4340](https://linux-hardware.org/?probe=e86a5c4340) | Apr 12, 2019 |
| HP            | ProBook 450 G2              | [ed27c8b4b2](https://linux-hardware.org/?probe=ed27c8b4b2) | Feb 23, 2019 |
| Lenovo        | Legion Y530-15ICH 81FV      | [d1e0440b23](https://linux-hardware.org/?probe=d1e0440b23) | Jan 30, 2019 |
| Dell          | Inspiron 7520               | [4362c41db3](https://linux-hardware.org/?probe=4362c41db3) | Nov 17, 2018 |
| Dell          | Inspiron 7520               | [461541bb3a](https://linux-hardware.org/?probe=461541bb3a) | Nov 17, 2018 |
| Dell          | Latitude E5470              | [f54e62ab63](https://linux-hardware.org/?probe=f54e62ab63) | Nov 11, 2018 |
| Dell          | Latitude E5470              | [496335b114](https://linux-hardware.org/?probe=496335b114) | Nov 10, 2018 |
| Dell          | Latitude E5470              | [3c869c46e5](https://linux-hardware.org/?probe=3c869c46e5) | Nov 08, 2018 |
| Toshiba       | Satellite L50-A661          | [fad34d33ee](https://linux-hardware.org/?probe=fad34d33ee) | Apr 22, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Egypt/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 63        | 12.07%  |
| Ubuntu 22.04       | 54        | 10.34%  |
| Ubuntu 18.04       | 34        | 6.51%   |
| Fedora 40          | 18        | 3.45%   |
| Arch Rolling       | 18        | 3.45%   |
| Zorin 17           | 15        | 2.87%   |
| Zorin 16           | 11        | 2.11%   |
| Pop!_OS 22.04      | 11        | 2.11%   |
| Ubuntu 24.04       | 10        | 1.92%   |
| Fedora 38          | 10        | 1.92%   |
| ArcoLinux Rolling  | 10        | 1.92%   |
| Ubuntu 19.10       | 9         | 1.72%   |
| OpenMandriva 4.3   | 8         | 1.53%   |
| Zorin 15           | 7         | 1.34%   |
| Ubuntu 20.10       | 7         | 1.34%   |
| Fedora 39          | 7         | 1.34%   |
| Debian 12          | 7         | 1.34%   |
| Ubuntu 22.10       | 6         | 1.15%   |
| Fedora 36          | 6         | 1.15%   |
| Pop!_OS 20.10      | 5         | 0.96%   |
| Kali 2023.3        | 5         | 0.96%   |
| Fedora 41          | 5         | 0.96%   |
| Ubuntu 23.10       | 4         | 0.77%   |
| Ubuntu 23.04       | 4         | 0.77%   |
| Ubuntu 21.10       | 4         | 0.77%   |
| Manjaro            | 4         | 0.77%   |
| Linux Mint 20.3    | 4         | 0.77%   |
| Linux Mint 19.3    | 4         | 0.77%   |
| Fedora 37          | 4         | 0.77%   |
| Fedora 34          | 4         | 0.77%   |
| Arch               | 4         | 0.77%   |
| Ubuntu 21.04       | 3         | 0.57%   |
| Pop!_OS 20.04      | 3         | 0.57%   |
| OpenMandriva 23.03 | 3         | 0.57%   |
| MX 23              | 3         | 0.57%   |
| Linux Mint 21.2    | 3         | 0.57%   |
| Linux Mint 21      | 3         | 0.57%   |
| Linux Mint 20.1    | 3         | 0.57%   |
| Linux Mint 19      | 3         | 0.57%   |
| Kubuntu 20.04      | 3         | 0.57%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 200       | 39.6%   |
| Fedora        | 62        | 12.28%  |
| Zorin         | 33        | 6.53%   |
| Linux Mint    | 25        | 4.95%   |
| Kali          | 22        | 4.36%   |
| Arch          | 22        | 4.36%   |
| Pop!_OS       | 20        | 3.96%   |
| OpenMandriva  | 18        | 3.56%   |
| Manjaro       | 12        | 2.38%   |
| Debian        | 12        | 2.38%   |
| ArcoLinux     | 10        | 1.98%   |
| Kubuntu       | 9         | 1.78%   |
| Endless       | 9         | 1.78%   |
| Parrot        | 5         | 0.99%   |
| MX            | 5         | 0.99%   |
| KDE neon      | 4         | 0.79%   |
| ROSA          | 3         | 0.59%   |
| Nobara        | 3         | 0.59%   |
| Elementary    | 3         | 0.59%   |
| Xero          | 2         | 0.4%    |
| Ubuntu Unity  | 2         | 0.4%    |
| RHEL          | 2         | 0.4%    |
| openSUSE      | 2         | 0.4%    |
| Lubuntu       | 2         | 0.4%    |
| EndeavourOS   | 2         | 0.4%    |
| Clear Linux   | 2         | 0.4%    |
| ALT Linux     | 2         | 0.4%    |
| Xubuntu       | 1         | 0.2%    |
| Ubuntu Budgie | 1         | 0.2%    |
| Rocky Linux   | 1         | 0.2%    |
| Q4OS          | 1         | 0.2%    |
| Peppermint    | 1         | 0.2%    |
| NixOS         | 1         | 0.2%    |
| LMDE          | 1         | 0.2%    |
| Gentoo        | 1         | 0.2%    |
| CentOS        | 1         | 0.2%    |
| blendOS       | 1         | 0.2%    |
| BlackPanther  | 1         | 0.2%    |
| Alpine        | 1         | 0.2%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.4.0-42-generic        | 13        | 2.35%   |
| 5.16.7-desktop-1omv4003 | 7         | 1.26%   |
| 5.4.0-58-generic        | 6         | 1.08%   |
| 6.5.0-kali3-amd64       | 5         | 0.9%    |
| 5.15.0-47-generic       | 5         | 0.9%    |
| 6.8.5-301.fc40.x86_64   | 4         | 0.72%   |
| 6.8.0-49-generic        | 4         | 0.72%   |
| 6.8.0-45-generic        | 4         | 0.72%   |
| 6.5.0-35-generic        | 4         | 0.72%   |
| 6.2.6-desktop-1omv2390  | 4         | 0.72%   |
| 6.2.0-26-generic        | 4         | 0.72%   |
| 6.1.0-23-amd64          | 4         | 0.72%   |
| 5.8.0-7630-generic      | 4         | 0.72%   |
| 5.8.0-48-generic        | 4         | 0.72%   |
| 5.4.0-48-generic        | 4         | 0.72%   |
| 5.4.0-29-generic        | 4         | 0.72%   |
| 5.19.0-76051900-generic | 4         | 0.72%   |
| 5.0.0-32-generic        | 4         | 0.72%   |
| 6.9.3-76060903-generic  | 3         | 0.54%   |
| 6.8.9-300.fc40.x86_64   | 3         | 0.54%   |
| 6.8.0-40-generic        | 3         | 0.54%   |
| 6.6.9-amd64             | 3         | 0.54%   |
| 6.5.0-kali1-amd64       | 3         | 0.54%   |
| 6.5.0-44-generic        | 3         | 0.54%   |
| 6.5.0-41-generic        | 3         | 0.54%   |
| 6.5.0-28-generic        | 3         | 0.54%   |
| 6.5.0-13parrot1-amd64   | 3         | 0.54%   |
| 6.2.0-33-generic        | 3         | 0.54%   |
| 5.8.0-43-generic        | 3         | 0.54%   |
| 5.8.0-41-generic        | 3         | 0.54%   |
| 5.4.0-56-generic        | 3         | 0.54%   |
| 5.3.0-51-generic        | 3         | 0.54%   |
| 5.3.0-18-generic        | 3         | 0.54%   |
| 5.19.0-41-generic       | 3         | 0.54%   |
| 5.19.0-38-generic       | 3         | 0.54%   |
| 5.15.0-56-generic       | 3         | 0.54%   |
| 5.15.0-52-generic       | 3         | 0.54%   |
| 5.15.0-50-generic       | 3         | 0.54%   |
| 5.15.0-48-generic       | 3         | 0.54%   |
| 5.15.0-40-generic       | 3         | 0.54%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 58        | 10.9%   |
| 5.15.0  | 45        | 8.46%   |
| 6.5.0   | 41        | 7.71%   |
| 5.3.0   | 24        | 4.51%   |
| 5.8.0   | 23        | 4.32%   |
| 6.8.0   | 19        | 3.57%   |
| 5.19.0  | 19        | 3.57%   |
| 4.15.0  | 19        | 3.57%   |
| 6.2.0   | 15        | 2.82%   |
| 5.13.0  | 14        | 2.63%   |
| 5.0.0   | 14        | 2.63%   |
| 5.11.0  | 13        | 2.44%   |
| 6.1.0   | 9         | 1.69%   |
| 5.10.0  | 9         | 1.69%   |
| 4.18.0  | 8         | 1.5%    |
| 5.16.7  | 7         | 1.32%   |
| 6.6.9   | 5         | 0.94%   |
| 6.2.6   | 5         | 0.94%   |
| 6.9.3   | 4         | 0.75%   |
| 6.8.9   | 4         | 0.75%   |
| 6.8.5   | 4         | 0.75%   |
| 5.14.0  | 4         | 0.75%   |
| 6.8.11  | 3         | 0.56%   |
| 6.4.11  | 3         | 0.56%   |
| 6.11.5  | 3         | 0.56%   |
| 6.10.11 | 3         | 0.56%   |
| 6.0.0   | 3         | 0.56%   |
| 5.17.5  | 3         | 0.56%   |
| 6.8.12  | 2         | 0.38%   |
| 6.7.10  | 2         | 0.38%   |
| 6.6.2   | 2         | 0.38%   |
| 6.6.16  | 2         | 0.38%   |
| 6.6.13  | 2         | 0.38%   |
| 6.6.10  | 2         | 0.38%   |
| 6.5.5   | 2         | 0.38%   |
| 6.4.8   | 2         | 0.38%   |
| 6.2.11  | 2         | 0.38%   |
| 6.11.4  | 2         | 0.38%   |
| 6.11.0  | 2         | 0.38%   |
| 6.10.7  | 2         | 0.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 63        | 12%     |
| 5.15    | 51        | 9.71%   |
| 6.5     | 46        | 8.76%   |
| 6.8     | 36        | 6.86%   |
| 6.2     | 26        | 4.95%   |
| 5.8     | 26        | 4.95%   |
| 5.3     | 26        | 4.95%   |
| 5.19    | 22        | 4.19%   |
| 5.10    | 19        | 3.62%   |
| 4.15    | 19        | 3.62%   |
| 6.6     | 18        | 3.43%   |
| 5.13    | 15        | 2.86%   |
| 5.11    | 15        | 2.86%   |
| 6.1     | 14        | 2.67%   |
| 5.16    | 14        | 2.67%   |
| 5.0     | 14        | 2.67%   |
| 6.11    | 12        | 2.29%   |
| 6.4     | 11        | 2.1%    |
| 6.10    | 10        | 1.9%    |
| 4.18    | 9         | 1.71%   |
| 6.0     | 8         | 1.52%   |
| 6.9     | 7         | 1.33%   |
| 5.17    | 7         | 1.33%   |
| 6.3     | 6         | 1.14%   |
| 5.18    | 6         | 1.14%   |
| 6.7     | 5         | 0.95%   |
| 5.14    | 5         | 0.95%   |
| 6.12    | 3         | 0.57%   |
| 5.12    | 3         | 0.57%   |
| 5.6     | 2         | 0.38%   |
| 4.19    | 2         | 0.38%   |
| 5.9     | 1         | 0.19%   |
| 5.7     | 1         | 0.19%   |
| 5.5     | 1         | 0.19%   |
| 4.9     | 1         | 0.19%   |
| 4.16    | 1         | 0.19%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 480       | 98.97%  |
| i686   | 5         | 1.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 310       | 61.39%  |
| KDE5            | 51        | 10.1%   |
| Unknown         | 41        | 8.12%   |
| XFCE            | 40        | 7.92%   |
| X-Cinnamon      | 22        | 4.36%   |
| KDE6            | 12        | 2.38%   |
| MATE            | 7         | 1.39%   |
| Cinnamon        | 3         | 0.59%   |
| Unity           | 2         | 0.4%    |
| Pantheon        | 2         | 0.4%    |
| KDE4            | 2         | 0.4%    |
| KDE             | 2         | 0.4%    |
| Sway            | 1         | 0.2%    |
| qtile           | 1         | 0.2%    |
| LXQt            | 1         | 0.2%    |
| LXDE            | 1         | 0.2%    |
| i3              | 1         | 0.2%    |
| Hyprland        | 1         | 0.2%    |
| GNOME Flashback | 1         | 0.2%    |
| GNOME Classic   | 1         | 0.2%    |
| Enlightenment   | 1         | 0.2%    |
| Endless:GNOME   | 1         | 0.2%    |
| Budgie          | 1         | 0.2%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 316       | 63.2%   |
| Wayland | 154       | 30.8%   |
| Unknown | 25        | 5%      |
| Tty     | 5         | 1%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 258       | 51.7%   |
| GDM3    | 85        | 17.03%  |
| SDDM    | 55        | 11.02%  |
| GDM     | 55        | 11.02%  |
| LightDM | 35        | 7.01%   |
| TDM     | 6         | 1.2%    |
| KDM     | 2         | 0.4%    |
| XDM     | 1         | 0.2%    |
| LY-DM   | 1         | 0.2%    |
| GREETD  | 1         | 0.2%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 408       | 82.26%  |
| Unknown     | 32        | 6.45%   |
| en_GB       | 21        | 4.23%   |
| C           | 17        | 3.43%   |
| ar_EG       | 9         | 1.81%   |
| ru_RU       | 2         | 0.4%    |
| en_ZA       | 2         | 0.4%    |
| POSIX       | 1         | 0.2%    |
| fr_FR       | 1         | 0.2%    |
| en_US.UFT-8 | 1         | 0.2%    |
| de_DE       | 1         | 0.2%    |
| C.UTF8      | 1         | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 277       | 55.96%  |
| EFI  | 218       | 44.04%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 352       | 70.97%  |
| Btrfs   | 65        | 13.1%   |
| Tmpfs   | 37        | 7.46%   |
| Overlay | 18        | 3.63%   |
| Unknown | 11        | 2.22%   |
| Xfs     | 7         | 1.41%   |
| Zfs     | 2         | 0.4%    |
| Ext3    | 2         | 0.4%    |
| Ext2    | 2         | 0.4%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 269       | 54.56%  |
| GPT     | 181       | 36.71%  |
| MBR     | 43        | 8.72%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 440       | 89.07%  |
| Yes       | 54        | 10.93%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 293       | 59.43%  |
| Yes       | 200       | 40.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 144       | 29.69%  |
| Dell                        | 125       | 25.77%  |
| Lenovo                      | 103       | 21.24%  |
| ASUSTek Computer            | 40        | 8.25%   |
| Toshiba                     | 15        | 3.09%   |
| Acer                        | 15        | 3.09%   |
| Sony                        | 6         | 1.24%   |
| MSI                         | 6         | 1.24%   |
| HUAWEI                      | 5         | 1.03%   |
| Apple                       | 5         | 1.03%   |
| Samsung Electronics         | 4         | 0.82%   |
| Hampoo                      | 3         | 0.62%   |
| Panasonic                   | 2         | 0.41%   |
| Packard Bell                | 2         | 0.41%   |
| Fujitsu Siemens             | 2         | 0.41%   |
| Fujitsu                     | 2         | 0.41%   |
| Alienware                   | 2         | 0.41%   |
| TECNO                       | 1         | 0.21%   |
| Razer                       | 1         | 0.21%   |
| MiTAC                       | 1         | 0.21%   |
| I-Life Digital Technologies | 1         | 0.21%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lenovo IdeaPad 520-15IKB 81BF            | 7         | 1.44%   |
| HP Notebook                              | 6         | 1.24%   |
| HP EliteBook 745 G3                      | 6         | 1.24%   |
| Dell Inspiron 5570                       | 6         | 1.24%   |
| HP ProBook 450 G7                        | 5         | 1.03%   |
| Dell Inspiron 7577                       | 5         | 1.03%   |
| Dell G3 3579                             | 5         | 1.03%   |
| ASUS VivoBook_ASUSLaptop X1605VA_X1605VA | 5         | 1.03%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK    | 4         | 0.82%   |
| Lenovo IdeaPad 330-15IKB 81DE            | 4         | 0.82%   |
| Lenovo IdeaPad 330-15AST 81D6            | 4         | 0.82%   |
| HP ProBook 645 G1                        | 4         | 0.82%   |
| HP Pavilion 15                           | 4         | 0.82%   |
| HP Laptop 15-da1xxx                      | 4         | 0.82%   |
| Dell Inspiron N5010                      | 4         | 0.82%   |
| Dell Inspiron 3593                       | 4         | 0.82%   |
| Dell G5 5587                             | 4         | 0.82%   |
| Lenovo Legion Y540-15IRH 81SX            | 3         | 0.62%   |
| Lenovo Legion 5 15IMH05H 81Y6            | 3         | 0.62%   |
| Lenovo IdeaPad 320-15IKB 81BT            | 3         | 0.62%   |
| Lenovo IdeaPad 310-15IKB 80TV            | 3         | 0.62%   |
| HP ZBook 15 G2                           | 3         | 0.62%   |
| HP Pavilion dv6                          | 3         | 0.62%   |
| HP Laptop 15-bs0xx                       | 3         | 0.62%   |
| HP EliteBook 8440p                       | 3         | 0.62%   |
| HP 250 G7 Notebook PC                    | 3         | 0.62%   |
| HP 15                                    | 3         | 0.62%   |
| Hampoo Cherry Trail CR                   | 3         | 0.62%   |
| Dell Precision M4800                     | 3         | 0.62%   |
| Dell Latitude E5570                      | 3         | 0.62%   |
| Dell Inspiron N5110                      | 3         | 0.62%   |
| Dell Inspiron 3521                       | 3         | 0.62%   |
| Dell G15 5511                            | 3         | 0.62%   |
| Dell G15 5510                            | 3         | 0.62%   |
| Unknown                                  | 3         | 0.62%   |
| Toshiba Satellite C660                   | 2         | 0.41%   |
| Lenovo Z50-70 20354                      | 2         | 0.41%   |
| Lenovo Y50-70 20378                      | 2         | 0.41%   |
| Lenovo V14-IIL 82C4                      | 2         | 0.41%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2      | 2         | 0.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 52        | 10.72%  |
| Lenovo IdeaPad        | 45        | 9.28%   |
| Dell Latitude         | 39        | 8.04%   |
| HP EliteBook          | 30        | 6.19%   |
| HP ProBook            | 28        | 5.77%   |
| HP Pavilion           | 23        | 4.74%   |
| Lenovo ThinkPad       | 20        | 4.12%   |
| ASUS VivoBook         | 17        | 3.51%   |
| HP Laptop             | 14        | 2.89%   |
| Toshiba Satellite     | 13        | 2.68%   |
| Lenovo Legion         | 12        | 2.47%   |
| HP ZBook              | 12        | 2.47%   |
| Dell G15              | 9         | 1.86%   |
| Dell Precision        | 8         | 1.65%   |
| Dell G3               | 8         | 1.65%   |
| Acer Aspire           | 8         | 1.65%   |
| HP Notebook           | 6         | 1.24%   |
| HP 250                | 6         | 1.24%   |
| ASUS ASUS             | 6         | 1.24%   |
| Dell G5               | 5         | 1.03%   |
| HP Compaq             | 4         | 0.82%   |
| ASUS ROG              | 4         | 0.82%   |
| Lenovo Yoga           | 3         | 0.62%   |
| HP OMEN               | 3         | 0.62%   |
| HP 15                 | 3         | 0.62%   |
| Hampoo Cherry         | 3         | 0.62%   |
| Acer Predator         | 3         | 0.62%   |
| Acer Nitro            | 3         | 0.62%   |
| Unknown               | 3         | 0.62%   |
| Packard Bell EasyNote | 2         | 0.41%   |
| MSI Modern            | 2         | 0.41%   |
| Lenovo Z50-70         | 2         | 0.41%   |
| Lenovo Y50-70         | 2         | 0.41%   |
| Lenovo V14-IIL        | 2         | 0.41%   |
| Lenovo G555           | 2         | 0.41%   |
| HUAWEI BOHB-WAX9      | 2         | 0.41%   |
| HP Victus             | 2         | 0.41%   |
| HP G62                | 2         | 0.41%   |
| HP ENVY               | 2         | 0.41%   |
| HP 350                | 2         | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 55        | 11.34%  |
| 2017 | 46        | 9.48%   |
| 2019 | 39        | 8.04%   |
| 2014 | 37        | 7.63%   |
| 2013 | 36        | 7.42%   |
| 2012 | 36        | 7.42%   |
| 2021 | 35        | 7.22%   |
| 2015 | 34        | 7.01%   |
| 2016 | 31        | 6.39%   |
| 2020 | 28        | 5.77%   |
| 2011 | 28        | 5.77%   |
| 2022 | 25        | 5.15%   |
| 2010 | 23        | 4.74%   |
| 2008 | 12        | 2.47%   |
| 2009 | 11        | 2.27%   |
| 2023 | 4         | 0.82%   |
| 2007 | 4         | 0.82%   |
| 2024 | 1         | 0.21%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 485       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 451       | 92.8%   |
| Enabled  | 35        | 7.2%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 484       | 99.79%  |
| Yes  | 1         | 0.21%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 160       | 32.79%  |
| 16.01-24.0  | 105       | 21.52%  |
| 3.01-4.0    | 85        | 17.42%  |
| 8.01-16.0   | 76        | 15.57%  |
| 32.01-64.0  | 23        | 4.71%   |
| 1.01-2.0    | 15        | 3.07%   |
| 24.01-32.0  | 12        | 2.46%   |
| 2.01-3.0    | 9         | 1.84%   |
| 64.01-256.0 | 2         | 0.41%   |
| 0.51-1.0    | 1         | 0.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 166       | 31.32%  |
| 1.01-2.0   | 138       | 26.04%  |
| 4.01-8.0   | 109       | 20.57%  |
| 3.01-4.0   | 87        | 16.42%  |
| 8.01-16.0  | 16        | 3.02%   |
| 0.51-1.0   | 9         | 1.7%    |
| 16.01-24.0 | 3         | 0.57%   |
| 32.01-64.0 | 1         | 0.19%   |
| 0.01-0.5   | 1         | 0.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 303       | 61.21%  |
| 2      | 179       | 36.16%  |
| 3      | 10        | 2.02%   |
| 4      | 2         | 0.4%    |
| 6      | 1         | 0.2%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 304       | 62.17%  |
| Yes       | 185       | 37.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 423       | 87.22%  |
| No        | 62        | 12.78%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 479       | 98.76%  |
| No        | 6         | 1.24%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 412       | 83.91%  |
| No        | 79        | 16.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Egypt   | 485       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Cairo                 | 258       | 48.77%  |
| Alexandria            | 66        | 12.48%  |
| Giza                  | 42        | 7.94%   |
| Al Mansurah           | 16        | 3.02%   |
| Tanta                 | 14        | 2.65%   |
| Qina                  | 7         | 1.32%   |
| Bani Suwayf           | 6         | 1.13%   |
| Assiut                | 6         | 1.13%   |
| Zagazig               | 5         | 0.95%   |
| Hurghada              | 5         | 0.95%   |
| Banha                 | 5         | 0.95%   |
| Suez                  | 4         | 0.76%   |
| Minya                 | 4         | 0.76%   |
| Ismailia              | 4         | 0.76%   |
| Damietta              | 4         | 0.76%   |
| Awsim                 | 4         | 0.76%   |
| Aswan                 | 4         | 0.76%   |
| New Cairo             | 3         | 0.57%   |
| Helwan                | 3         | 0.57%   |
| Damanhur              | 3         | 0.57%   |
| Al Qahirah al Jadidah | 3         | 0.57%   |
| Al Ma`adi             | 3         | 0.57%   |
| Al 'Ashir min Ramadan | 3         | 0.57%   |
| Talkha                | 2         | 0.38%   |
| Tala                  | 2         | 0.38%   |
| Sohag                 | 2         | 0.38%   |
| Sharqia               | 2         | 0.38%   |
| Port Said             | 2         | 0.38%   |
| Madinat as Sadat      | 2         | 0.38%   |
| Kafr ash Shaykh       | 2         | 0.38%   |
| Edfu                  | 2         | 0.38%   |
| Al Mahallah al Kubra  | 2         | 0.38%   |
| Al Fayyum             | 2         | 0.38%   |
| Zefta                 | 1         | 0.19%   |
| Tukh                  | 1         | 0.19%   |
| Smouha                | 1         | 0.19%   |
| Shirbin               | 1         | 0.19%   |
| Samannud              | 1         | 0.19%   |
| Rosetta               | 1         | 0.19%   |
| Qalyubia              | 1         | 0.19%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate                        | 107       | 123    | 16.21%  |
| WDC                            | 101       | 131    | 15.3%   |
| Toshiba                        | 83        | 104    | 12.58%  |
| Samsung Electronics            | 64        | 84     | 9.7%    |
| Kingston                       | 37        | 44     | 5.61%   |
| Crucial                        | 26        | 29     | 3.94%   |
| Sandisk                        | 25        | 28     | 3.79%   |
| Unknown                        | 24        | 30     | 3.64%   |
| SK hynix                       | 24        | 29     | 3.64%   |
| Micron Technology              | 22        | 27     | 3.33%   |
| Hitachi                        | 21        | 26     | 3.18%   |
| HGST                           | 21        | 25     | 3.18%   |
| Intel                          | 19        | 19     | 2.88%   |
| Micron/Crucial Technology      | 11        | 11     | 1.67%   |
| HS-SSD-C100                    | 10        | 14     | 1.52%   |
| Kingston Technology Company    | 5         | 5      | 0.76%   |
| TwinMOS                        | 4         | 6      | 0.61%   |
| LITEONIT                       | 4         | 5      | 0.61%   |
| LITEON                         | 4         | 6      | 0.61%   |
| KIOXIA                         | 4         | 5      | 0.61%   |
| JMicron Technology             | 4         | 5      | 0.61%   |
| Apple                          | 4         | 6      | 0.61%   |
| A-DATA Technology              | 4         | 4      | 0.61%   |
| Transcend                      | 2         | 2      | 0.3%    |
| Solid State Storage Technology | 2         | 2      | 0.3%    |
| Silicon Motion                 | 2         | 2      | 0.3%    |
| KingSpec                       | 2         | 2      | 0.3%    |
| HS-SSD-E100                    | 2         | 2      | 0.3%    |
| China                          | 2         | 2      | 0.3%    |
| YMTC                           | 1         | 1      | 0.15%   |
| Yangtze Memory Technologies    | 1         | 1      | 0.15%   |
| ValueTech                      | 1         | 1      | 0.15%   |
| Value                          | 1         | 1      | 0.15%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.15%   |
| Union Memory                   | 1         | 1      | 0.15%   |
| UMIS                           | 1         | 1      | 0.15%   |
| Team                           | 1         | 1      | 0.15%   |
| Shenzhen Longsys Electronics   | 1         | 1      | 0.15%   |
| Phison Electronics             | 1         | 1      | 0.15%   |
| Phison                         | 1         | 1      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 48        | 7.13%   |
| Toshiba MQ04ABF100 1TB                              | 20        | 2.97%   |
| Toshiba MQ01ABD100 1TB                              | 13        | 1.93%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 11        | 1.63%   |
| Seagate ST2000LM007-1R8174 2TB                      | 10        | 1.49%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB               | 9         | 1.34%   |
| Kingston SA400S37480G 480GB SSD                     | 9         | 1.34%   |
| Kingston SA400S37240G 240GB SSD                     | 9         | 1.34%   |
| Intel SSDPEKNU512GZ 512GB                           | 8         | 1.19%   |
| WDC WD10SPZX-24Z10 1TB                              | 7         | 1.04%   |
| Crucial CT480BX500SSD1 480GB                        | 7         | 1.04%   |
| Crucial CT240BX500SSD1 240GB                        | 7         | 1.04%   |
| WDC WD10JPVX-60JC3T1 1TB                            | 6         | 0.89%   |
| Seagate ST500LT012-1DG142 500GB                     | 6         | 0.89%   |
| Samsung NVMe SSD Drive 256GB                        | 6         | 0.89%   |
| Kingston SA400S37120G 120GB SSD                     | 6         | 0.89%   |
| WDC WD10SPZX-60Z10T0 1TB                            | 5         | 0.74%   |
| Unknown MMC Card  64GB                              | 5         | 0.74%   |
| Unknown MMC Card  32GB                              | 5         | 0.74%   |
| Toshiba MQ01ABF050 500GB                            | 5         | 0.74%   |
| Seagate ST750LM022 HN-M750MBB 752GB                 | 5         | 0.74%   |
| HGST HTS725050A7E630 500GB                          | 5         | 0.74%   |
| HGST HTS541010A9E680 1TB                            | 5         | 0.74%   |
| WDC WD10SPZX-75Z10T1 1TB                            | 4         | 0.59%   |
| WDC WD10JPCX-24UE4T0 1TB                            | 4         | 0.59%   |
| Toshiba MK3275GSX 320GB                             | 4         | 0.59%   |
| SK hynix SC311 SATA 256GB SSD                       | 4         | 0.59%   |
| Seagate ST1000LM049-2GH172 1TB                      | 4         | 0.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 4         | 0.59%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB    | 4         | 0.59%   |
| HS-SSD-C100 SSD 240G                                | 4         | 0.59%   |
| HS-SSD-C100 120G                                    | 4         | 0.59%   |
| Hitachi HTS547575A9E384 752GB                       | 4         | 0.59%   |
| HGST HTS545050A7E680 500GB                          | 4         | 0.59%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 3         | 0.45%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                    | 3         | 0.45%   |
| WDC WD10SPZX-00Z10T0 1TB                            | 3         | 0.45%   |
| Unknown SD/MMC/MS PRO 128GB                         | 3         | 0.45%   |
| Toshiba NVMe SSD Drive 256GB                        | 3         | 0.45%   |
| Toshiba MQ01ACF032 320GB                            | 3         | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 107       | 123    | 33.65%  |
| WDC                 | 88        | 116    | 27.67%  |
| Toshiba             | 72        | 90     | 22.64%  |
| Hitachi             | 21        | 26     | 6.6%    |
| HGST                | 21        | 25     | 6.6%    |
| Unknown             | 3         | 3      | 0.94%   |
| Samsung Electronics | 2         | 3      | 0.63%   |
| JMicron Technology  | 2         | 2      | 0.63%   |
| Fujitsu             | 1         | 1      | 0.31%   |
| Apple               | 1         | 1      | 0.31%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 32        | 39     | 20.25%  |
| Samsung Electronics | 27        | 30     | 17.09%  |
| Crucial             | 22        | 25     | 13.92%  |
| SanDisk             | 11        | 13     | 6.96%   |
| WDC                 | 8         | 10     | 5.06%   |
| SK hynix            | 8         | 8      | 5.06%   |
| Micron Technology   | 8         | 11     | 5.06%   |
| Intel               | 6         | 6      | 3.8%    |
| Toshiba             | 5         | 7      | 3.16%   |
| TwinMOS             | 4         | 6      | 2.53%   |
| LITEONIT            | 4         | 5      | 2.53%   |
| LITEON              | 4         | 6      | 2.53%   |
| HS-SSD-C100         | 4         | 6      | 2.53%   |
| Transcend           | 2         | 2      | 1.27%   |
| KingSpec            | 2         | 2      | 1.27%   |
| China               | 2         | 2      | 1.27%   |
| Value               | 1         | 1      | 0.63%   |
| Team                | 1         | 1      | 0.63%   |
| Maxtor              | 1         | 1      | 0.63%   |
| Lexar               | 1         | 1      | 0.63%   |
| KingFast            | 1         | 1      | 0.63%   |
| HEYGATE             | 1         | 1      | 0.63%   |
| CARLSTEIN           | 1         | 1      | 0.63%   |
| Apple               | 1         | 1      | 0.63%   |
| A-DATA Technology   | 1         | 1      | 0.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 307       | 390    | 48.35%  |
| SSD     | 149       | 187    | 23.46%  |
| NVMe    | 145       | 180    | 22.83%  |
| MMC     | 18        | 23     | 2.83%   |
| Unknown | 16        | 18     | 2.52%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 389       | 582    | 69.09%  |
| NVMe | 145       | 180    | 25.75%  |
| MMC  | 18        | 23     | 3.2%    |
| SAS  | 11        | 13     | 1.95%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 245       | 327    | 54.93%  |
| 0.51-1.0   | 183       | 232    | 41.03%  |
| 1.01-2.0   | 18        | 18     | 4.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 141       | 27.81%  |
| 251-500        | 124       | 24.46%  |
| 501-1000       | 78        | 15.38%  |
| 51-100         | 51        | 10.06%  |
| 1001-2000      | 44        | 8.68%   |
| 21-50          | 31        | 6.11%   |
| 1-20           | 21        | 4.14%   |
| Unknown        | 8         | 1.58%   |
| 2001-3000      | 5         | 0.99%   |
| More than 3000 | 4         | 0.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 176       | 33.59%  |
| 21-50          | 110       | 20.99%  |
| 101-250        | 81        | 15.46%  |
| 51-100         | 70        | 13.36%  |
| 251-500        | 37        | 7.06%   |
| 501-1000       | 31        | 5.92%   |
| Unknown        | 8         | 1.53%   |
| 1001-2000      | 7         | 1.34%   |
| 2001-3000      | 3         | 0.57%   |
| More than 3000 | 1         | 0.19%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 3         | 4      | 6.52%   |
| SK hynix HFS128G39TND-N210A 128GB SSD               | 2         | 2      | 4.35%   |
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 1      | 2.17%   |
| WDC WD5000LPVX-60V0TT0 500GB                        | 1         | 1      | 2.17%   |
| WDC WD5000BPVT-24HXZT3 500GB                        | 1         | 1      | 2.17%   |
| WDC WD5000BPVT-22HXZT3 500GB                        | 1         | 2      | 2.17%   |
| WDC WD3200BUDT-63DPZY0 320GB                        | 1         | 1      | 2.17%   |
| WDC WD3200BEKT-60V5T1 320GB                         | 1         | 3      | 2.17%   |
| WDC WD20SPZX-75UA7T0 2TB                            | 1         | 1      | 2.17%   |
| WDC WD10SPZX-60Z10T0 1TB                            | 1         | 1      | 2.17%   |
| WDC WD10SPCX-24HWST1 1TB                            | 1         | 1      | 2.17%   |
| TwinMOS SSD 128GB                                   | 1         | 1      | 2.17%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD            | 1         | 1      | 2.17%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 2      | 2.17%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 2      | 2.17%   |
| Toshiba MK3275GSX 320GB                             | 1         | 1      | 2.17%   |
| Seagate ST95005620AS 500GB                          | 1         | 2      | 2.17%   |
| Seagate ST9320328CS 320GB                           | 1         | 2      | 2.17%   |
| Seagate ST500VT000-1DK142 500GB                     | 1         | 1      | 2.17%   |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 1      | 2.17%   |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 1      | 2.17%   |
| Seagate ST2000LM015-2E81 2TB                        | 1         | 1      | 2.17%   |
| Seagate ST1000LM049-2GH172 1TB                      | 1         | 1      | 2.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 2.17%   |
| Samsung Electronics SSD 870 EVO 500GB               | 1         | 1      | 2.17%   |
| Samsung Electronics HM321HI 320GB                   | 1         | 1      | 2.17%   |
| Micron Technology MTFDDAV512TBN-1AR15ABHA 512GB SSD | 1         | 1      | 2.17%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 2.17%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 2      | 2.17%   |
| Intel SSDSC2BF180A5H REF 180GB                      | 1         | 1      | 2.17%   |
| Intel SSDSC2BF180A4H 180GB                          | 1         | 1      | 2.17%   |
| Hitachi HTS725032A9A364 320GB                       | 1         | 1      | 2.17%   |
| Hitachi HTS723225L9A360 250GB                       | 1         | 1      | 2.17%   |
| Hitachi HTS545050A7E380 500GB                       | 1         | 1      | 2.17%   |
| Hitachi HTS545032B9SA02 320GB                       | 1         | 1      | 2.17%   |
| Hitachi HTS543232A7A384 320GB                       | 1         | 1      | 2.17%   |
| Hitachi HTS543225L9A300 250GB                       | 1         | 1      | 2.17%   |
| HGST HTS725050A7E630 500GB                          | 1         | 1      | 2.17%   |
| HGST HTS545050A7E380 500GB                          | 1         | 4      | 2.17%   |
| HGST HTS541010A9E680 1TB                            | 1         | 1      | 2.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 14     | 23.91%  |
| WDC                 | 9         | 12     | 19.57%  |
| Hitachi             | 6         | 6      | 13.04%  |
| Toshiba             | 4         | 6      | 8.7%    |
| Micron Technology   | 3         | 4      | 6.52%   |
| HGST                | 3         | 6      | 6.52%   |
| SK hynix            | 2         | 2      | 4.35%   |
| Samsung Electronics | 2         | 2      | 4.35%   |
| Intel               | 2         | 2      | 4.35%   |
| A-DATA Technology   | 2         | 2      | 4.35%   |
| TwinMOS             | 1         | 1      | 2.17%   |
| Apple               | 1         | 1      | 2.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 14     | 32.35%  |
| WDC                 | 9         | 12     | 26.47%  |
| Hitachi             | 6         | 6      | 17.65%  |
| Toshiba             | 3         | 5      | 8.82%   |
| HGST                | 3         | 6      | 8.82%   |
| Samsung Electronics | 1         | 1      | 2.94%   |
| Apple               | 1         | 1      | 2.94%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 34        | 45     | 73.91%  |
| SSD  | 10        | 11     | 21.74%  |
| NVMe | 2         | 2      | 4.35%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Notebooks | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Toshiba MK3265GSXV 320GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 322       | 522    | 62.65%  |
| Works    | 146       | 217    | 28.4%   |
| Malfunc  | 45        | 58     | 8.75%   |
| Failed   | 1         | 1      | 0.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 381       | 65.24%  |
| AMD                            | 55        | 9.42%   |
| Samsung Electronics            | 40        | 6.85%   |
| SanDisk                        | 19        | 3.25%   |
| SK hynix                       | 16        | 2.74%   |
| Micron/Crucial Technology      | 15        | 2.57%   |
| Micron Technology              | 14        | 2.4%    |
| Kingston Technology Company    | 10        | 1.71%   |
| Toshiba America Info Systems   | 8         | 1.37%   |
| KIOXIA                         | 4         | 0.68%   |
| ADATA Technology               | 4         | 0.68%   |
| Union Memory (Shenzhen)        | 3         | 0.51%   |
| Yangtze Memory Technologies    | 2         | 0.34%   |
| Solid State Storage Technology | 2         | 0.34%   |
| Silicon Motion                 | 2         | 0.34%   |
| Shenzhen Longsys Electronics   | 2         | 0.34%   |
| Phison Electronics             | 2         | 0.34%   |
| Nvidia                         | 2         | 0.34%   |
| Apple                          | 2         | 0.34%   |
| VIA Technologies               | 1         | 0.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 57        | 9.3%    |
| AMD FCH SATA Controller [AHCI mode]                                              | 49        | 7.99%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 44        | 7.18%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 28        | 4.57%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 28        | 4.57%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 27        | 4.4%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 26        | 4.24%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 22        | 3.59%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 20        | 3.26%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 13        | 2.12%   |
| Intel Volume Management Device NVMe RAID Controller                              | 13        | 2.12%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 12        | 1.96%   |
| Intel Comet Lake SATA AHCI Controller                                            | 12        | 1.96%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 12        | 1.96%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 12        | 1.96%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 11        | 1.79%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 10        | 1.63%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 9         | 1.47%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 9         | 1.47%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 8         | 1.31%   |
| Micron 2210 NVMe SSD [Cobain]                                                    | 7         | 1.14%   |
| Intel Tiger Lake-LP SATA Controller                                              | 7         | 1.14%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 7         | 1.14%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 7         | 1.14%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 6         | 0.98%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation            | 6         | 0.98%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 5         | 0.82%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 5         | 0.82%   |
| Micron 3400 NVMe SSD [Hendrix]                                                   | 5         | 0.82%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 5         | 0.82%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 5         | 0.82%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 5         | 0.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 5         | 0.82%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)              | 4         | 0.65%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 4         | 0.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 4         | 0.65%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 4         | 0.65%   |
| Intel Tiger Lake SATA AHCI Controller                                            | 4         | 0.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 0.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 4         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 366       | 61.51%  |
| NVMe | 147       | 24.71%  |
| RAID | 65        | 10.92%  |
| IDE  | 17        | 2.86%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 412       | 84.95%  |
| AMD    | 73        | 15.05%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz            | 17        | 3.51%   |
| Intel Core i7-8750H CPU @ 2.20GHz            | 15        | 3.09%   |
| Intel Core i7-9750H CPU @ 2.60GHz            | 11        | 2.27%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz           | 9         | 1.86%   |
| Intel Core i7-10750H CPU @ 2.60GHz           | 9         | 1.86%   |
| Intel Core i5-8250U CPU @ 1.60GHz            | 8         | 1.65%   |
| Intel Core i7-8565U CPU @ 1.80GHz            | 7         | 1.44%   |
| Intel Core i7-7500U CPU @ 2.70GHz            | 7         | 1.44%   |
| Intel Core i7-6500U CPU @ 2.50GHz            | 6         | 1.24%   |
| Intel Core i5-7200U CPU @ 2.50GHz            | 6         | 1.24%   |
| Intel Core i5-5200U CPU @ 2.20GHz            | 6         | 1.24%   |
| Intel Core i5-4200U CPU @ 1.60GHz            | 6         | 1.24%   |
| Intel 12th Gen Core i7-12700H                | 6         | 1.24%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz           | 5         | 1.03%   |
| Intel Core i7-4510U CPU @ 2.00GHz            | 5         | 1.03%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz           | 5         | 1.03%   |
| Intel Core i7-10510U CPU @ 1.80GHz           | 5         | 1.03%   |
| Intel Core i5-6200U CPU @ 2.30GHz            | 5         | 1.03%   |
| Intel Core i5-4210U CPU @ 1.70GHz            | 5         | 1.03%   |
| Intel Core i5-3320M CPU @ 2.60GHz            | 5         | 1.03%   |
| Intel Core i5-3210M CPU @ 2.50GHz            | 5         | 1.03%   |
| Intel Core i5-2520M CPU @ 2.50GHz            | 5         | 1.03%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz      | 5         | 1.03%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz      | 5         | 1.03%   |
| AMD Ryzen 5 5600H with Radeon Graphics       | 5         | 1.03%   |
| AMD PRO A10-8700B R6, 10 Compute Cores 4C+6G | 5         | 1.03%   |
| Intel Core i7-5500U CPU @ 2.40GHz            | 4         | 0.82%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz           | 4         | 0.82%   |
| Intel Core i7-2630QM CPU @ 2.00GHz           | 4         | 0.82%   |
| Intel Core i5-8265U CPU @ 1.60GHz            | 4         | 0.82%   |
| Intel Core i5-6300U CPU @ 2.40GHz            | 4         | 0.82%   |
| Intel Core i5-5300U CPU @ 2.30GHz            | 4         | 0.82%   |
| Intel Core i5-3230M CPU @ 2.60GHz            | 4         | 0.82%   |
| Intel Core i5-2450M CPU @ 2.50GHz            | 4         | 0.82%   |
| Intel Core i5-2430M CPU @ 2.40GHz            | 4         | 0.82%   |
| Intel Core i5-2410M CPU @ 2.30GHz            | 4         | 0.82%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz           | 4         | 0.82%   |
| Intel Core i3-3217U CPU @ 1.80GHz            | 4         | 0.82%   |
| Intel Core i3-10110U CPU @ 2.10GHz           | 4         | 0.82%   |
| Intel 13th Gen Core i7-13700H                | 4         | 0.82%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 156       | 32.16%  |
| Intel Core i5           | 122       | 25.15%  |
| Other                   | 45        | 9.28%   |
| Intel Core i3           | 42        | 8.66%   |
| Intel Core 2 Duo        | 17        | 3.51%   |
| AMD Ryzen 7             | 16        | 3.3%    |
| Intel Celeron           | 13        | 2.68%   |
| AMD Ryzen 5             | 10        | 2.06%   |
| Intel Pentium           | 7         | 1.44%   |
| AMD A6                  | 7         | 1.44%   |
| Intel Atom              | 6         | 1.24%   |
| AMD PRO A10             | 6         | 1.24%   |
| AMD E2                  | 6         | 1.24%   |
| AMD A4                  | 4         | 0.82%   |
| AMD Ryzen 9             | 3         | 0.62%   |
| AMD Ryzen 7 PRO         | 3         | 0.62%   |
| AMD Ryzen 5 PRO         | 3         | 0.62%   |
| AMD E1                  | 3         | 0.62%   |
| AMD A8                  | 3         | 0.62%   |
| Intel Pentium Dual-Core | 2         | 0.41%   |
| AMD Athlon II Dual-Core | 2         | 0.41%   |
| AMD A10                 | 2         | 0.41%   |
| Intel Genuine           | 1         | 0.21%   |
| Intel Core M            | 1         | 0.21%   |
| Intel Core i9           | 1         | 0.21%   |
| Intel Celeron Dual-Core | 1         | 0.21%   |
| AMD PRO A8              | 1         | 0.21%   |
| AMD E                   | 1         | 0.21%   |
| AMD Athlon II           | 1         | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 241       | 49.69%  |
| 4      | 142       | 29.28%  |
| 6      | 51        | 10.52%  |
| 8      | 23        | 4.74%   |
| 14     | 11        | 2.27%   |
| 10     | 7         | 1.44%   |
| 1      | 5         | 1.03%   |
| 12     | 4         | 0.82%   |
| 24     | 1         | 0.21%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 485       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 402       | 82.72%  |
| 1      | 84        | 17.28%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 478       | 98.35%  |
| Unknown        | 7         | 1.44%   |
| 32-bit         | 1         | 0.21%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 236       | 47.29%  |
| 0x206a7    | 22        | 4.41%   |
| 0x40651    | 18        | 3.61%   |
| 0x806ea    | 17        | 3.41%   |
| 0x306a9    | 16        | 3.21%   |
| 0x306d4    | 15        | 3.01%   |
| 0x906ea    | 14        | 2.81%   |
| 0x806e9    | 14        | 2.81%   |
| 0x306c3    | 14        | 2.81%   |
| 0x806ec    | 11        | 2.2%    |
| 0x906e9    | 9         | 1.8%    |
| 0x406e3    | 9         | 1.8%    |
| 0x1067a    | 8         | 1.6%    |
| 0xa0652    | 6         | 1.2%    |
| 0x20655    | 6         | 1.2%    |
| 0x806c1    | 5         | 1%      |
| 0x6fd      | 5         | 1%      |
| 0x30678    | 5         | 1%      |
| 0x706e5    | 4         | 0.8%    |
| 0x406c3    | 4         | 0.8%    |
| 0x20652    | 4         | 0.8%    |
| 0x06006705 | 4         | 0.8%    |
| 0x06006704 | 4         | 0.8%    |
| 0x0600111f | 4         | 0.8%    |
| 0x806eb    | 3         | 0.6%    |
| 0x0a50000c | 3         | 0.6%    |
| 0x06001119 | 3         | 0.6%    |
| 0x906a4    | 2         | 0.4%    |
| 0x906a3    | 2         | 0.4%    |
| 0x806d1    | 2         | 0.4%    |
| 0x506e3    | 2         | 0.4%    |
| 0x106e5    | 2         | 0.4%    |
| 0x10676    | 2         | 0.4%    |
| 0x0600611a | 2         | 0.4%    |
| 0x06006110 | 2         | 0.4%    |
| 0x90672    | 1         | 0.2%    |
| 0x706a1    | 1         | 0.2%    |
| 0x6e8      | 1         | 0.2%    |
| 0x506c9    | 1         | 0.2%    |
| 0x406c4    | 1         | 0.2%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 117       | 24.12%  |
| Haswell          | 48        | 9.9%    |
| SandyBridge      | 34        | 7.01%   |
| IvyBridge        | 31        | 6.39%   |
| Skylake          | 30        | 6.19%   |
| Broadwell        | 22        | 4.54%   |
| Westmere         | 19        | 3.92%   |
| Excavator        | 16        | 3.3%    |
| Alderlake Hybrid | 16        | 3.3%    |
| IceLake          | 15        | 3.09%   |
| CometLake        | 15        | 3.09%   |
| Unknown          | 15        | 3.09%   |
| TigerLake        | 14        | 2.89%   |
| Silvermont       | 14        | 2.89%   |
| Zen 3            | 13        | 2.68%   |
| Penryn           | 13        | 2.68%   |
| Piledriver       | 8         | 1.65%   |
| Core             | 7         | 1.44%   |
| Zen 2            | 6         | 1.24%   |
| Zen+             | 5         | 1.03%   |
| Zen              | 5         | 1.03%   |
| Bobcat           | 4         | 0.82%   |
| Puma             | 3         | 0.62%   |
| Nehalem          | 3         | 0.62%   |
| K10              | 3         | 0.62%   |
| Jaguar           | 2         | 0.41%   |
| Goldmont plus    | 2         | 0.41%   |
| Goldmont         | 2         | 0.41%   |
| Steamroller      | 1         | 0.21%   |
| P6               | 1         | 0.21%   |
| Bonnell          | 1         | 0.21%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 375       | 52.89%  |
| Nvidia           | 180       | 25.39%  |
| AMD              | 153       | 21.58%  |
| VIA Technologies | 1         | 0.14%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 29        | 4.03%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 28        | 3.89%   |
| Intel UHD Graphics 620                                                                   | 27        | 3.76%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 27        | 3.76%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 25        | 3.48%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 21        | 2.92%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 21        | 2.92%   |
| Intel HD Graphics 620                                                                    | 19        | 2.64%   |
| Intel HD Graphics 5500                                                                   | 19        | 2.64%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 18        | 2.5%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 15        | 2.09%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 13        | 1.81%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 13        | 1.81%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 13        | 1.81%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 12        | 1.67%   |
| Intel HD Graphics 630                                                                    | 12        | 1.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 12        | 1.67%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 1.53%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 11        | 1.53%   |
| Nvidia GP108M [GeForce MX150]                                                            | 10        | 1.39%   |
| Nvidia GM108M [GeForce MX130]                                                            | 10        | 1.39%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 10        | 1.39%   |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 1.39%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 9         | 1.25%   |
| Intel HD Graphics 530                                                                    | 8         | 1.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 1.11%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 8         | 1.11%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 7         | 0.97%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 7         | 0.97%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 7         | 0.97%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 7         | 0.97%   |
| Nvidia GM108M [GeForce 840M]                                                             | 6         | 0.83%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 6         | 0.83%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 6         | 0.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 0.83%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 6         | 0.83%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 0.83%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 0.7%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 5         | 0.7%    |
| Nvidia GK208M [GeForce GT 740M]                                                          | 5         | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 168       | 34.36%  |
| Intel + Nvidia | 142       | 29.04%  |
| 1 x AMD        | 68        | 13.91%  |
| Intel + AMD    | 66        | 13.5%   |
| 1 x Nvidia     | 23        | 4.7%    |
| AMD + Nvidia   | 13        | 2.66%   |
| 2 x AMD        | 5         | 1.02%   |
| 2 x Intel      | 2         | 0.41%   |
| 2 x Nvidia     | 1         | 0.2%    |
| 1 x VIA        | 1         | 0.2%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 388       | 78.54%  |
| Proprietary | 93        | 18.83%  |
| Unknown     | 13        | 2.63%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 317       | 63.53%  |
| 1.01-2.0   | 58        | 11.62%  |
| 3.01-4.0   | 47        | 9.42%   |
| 0.01-0.5   | 36        | 7.21%   |
| 0.51-1.0   | 27        | 5.41%   |
| 5.01-6.0   | 10        | 2%      |
| 8.01-16.0  | 2         | 0.4%    |
| 7.01-8.0   | 1         | 0.2%    |
| 2.01-3.0   | 1         | 0.2%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 91        | 17.77%  |
| BOE                     | 90        | 17.58%  |
| Chimei Innolux          | 89        | 17.38%  |
| LG Display              | 86        | 16.8%   |
| Samsung Electronics     | 57        | 11.13%  |
| Chi Mei Optoelectronics | 19        | 3.71%   |
| Sharp                   | 10        | 1.95%   |
| PANDA                   | 10        | 1.95%   |
| Lenovo                  | 8         | 1.56%   |
| InfoVision              | 8         | 1.56%   |
| Dell                    | 8         | 1.56%   |
| Apple                   | 5         | 0.98%   |
| Unknown                 | 4         | 0.78%   |
| Hewlett-Packard         | 3         | 0.59%   |
| Goldstar                | 3         | 0.59%   |
| Philips                 | 2         | 0.39%   |
| InnoLux Display         | 2         | 0.39%   |
| HKC                     | 2         | 0.39%   |
| CSO                     | 2         | 0.39%   |
| Toshiba                 | 1         | 0.2%    |
| TMX                     | 1         | 0.2%    |
| Panasonic               | 1         | 0.2%    |
| NEC Computers           | 1         | 0.2%    |
| NCS                     | 1         | 0.2%    |
| LG Philips              | 1         | 0.2%    |
| KDC                     | 1         | 0.2%    |
| HJW                     | 1         | 0.2%    |
| CSW                     | 1         | 0.2%    |
| CPT                     | 1         | 0.2%    |
| BenQ                    | 1         | 0.2%    |
| ASUSTek Computer        | 1         | 0.2%    |
| Unknown                 | 1         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 10        | 1.95%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch         | 8         | 1.56%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 8         | 1.56%   |
| Chimei Innolux LCD Monitor CMN1618 1920x1200 344x215mm 16.0-inch     | 6         | 1.17%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 6         | 1.17%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch      | 6         | 1.17%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 5         | 0.97%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                | 5         | 0.97%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 4         | 0.78%   |
| Lenovo LCD Monitor LEN40A0 1366x768 309x174mm 14.0-inch              | 4         | 0.78%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 4         | 0.78%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 4         | 0.78%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 4         | 0.78%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch     | 4         | 0.78%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                | 4         | 0.78%   |
| BOE LCD Monitor BOE07B0 1920x1080 344x194mm 15.5-inch                | 4         | 0.78%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 4         | 0.78%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch       | 4         | 0.78%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch        | 4         | 0.78%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 4         | 0.78%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 3         | 0.58%   |
| Samsung Electronics LCD Monitor SEC3151 1366x768 344x194mm 15.5-inch | 3         | 0.58%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch | 3         | 0.58%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch | 3         | 0.58%   |
| PANDA LCD Monitor NCP005F 1920x1080 344x194mm 15.5-inch              | 3         | 0.58%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch         | 3         | 0.58%   |
| LG Display LCD Monitor LGD0484 1366x768 344x194mm 15.5-inch          | 3         | 0.58%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch         | 3         | 0.58%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 3         | 0.58%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 3         | 0.58%   |
| Chimei Innolux LCD Monitor CMN15C2 1920x1080 344x194mm 15.5-inch     | 3         | 0.58%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch      | 3         | 0.58%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 3         | 0.58%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch      | 3         | 0.58%   |
| BOE LCD Monitor BOE06C6 1920x1080 344x194mm 15.5-inch                | 3         | 0.58%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                | 3         | 0.58%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch        | 3         | 0.58%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch        | 3         | 0.58%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch        | 3         | 0.58%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 3         | 0.58%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 217       | 43.31%  |
| 1366x768 (WXGA)    | 204       | 40.72%  |
| 1920x1200 (WUXGA)  | 15        | 2.99%   |
| 1600x900 (HD+)     | 13        | 2.59%   |
| 1280x800 (WXGA)    | 10        | 2%      |
| 3840x2160 (4K)     | 8         | 1.6%    |
| 1440x900 (WXGA+)   | 7         | 1.4%    |
| 2560x1440 (QHD)    | 6         | 1.2%    |
| 1680x1050 (WSXGA+) | 5         | 1%      |
| 2288x1287          | 3         | 0.6%    |
| 1280x1024 (SXGA)   | 3         | 0.6%    |
| 2880x1800          | 2         | 0.4%    |
| 2560x1600          | 2         | 0.4%    |
| 3840x2400          | 1         | 0.2%    |
| 3200x1800 (QHD+)   | 1         | 0.2%    |
| 2880x1620          | 1         | 0.2%    |
| 2304x1440          | 1         | 0.2%    |
| 1280x960           | 1         | 0.2%    |
| 1024x600           | 1         | 0.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 321       | 62.82%  |
| 14      | 62        | 12.13%  |
| 13      | 36        | 7.05%   |
| 12      | 14        | 2.74%   |
| 17      | 13        | 2.54%   |
| 16      | 11        | 2.15%   |
| 24      | 7         | 1.37%   |
| 23      | 7         | 1.37%   |
| 22      | 5         | 0.98%   |
| 11      | 5         | 0.98%   |
| 31      | 4         | 0.78%   |
| 27      | 4         | 0.78%   |
| 18      | 4         | 0.78%   |
| 142     | 3         | 0.59%   |
| 19      | 3         | 0.59%   |
| Unknown | 3         | 0.59%   |
| 21      | 2         | 0.39%   |
| 58      | 1         | 0.2%    |
| 54      | 1         | 0.2%    |
| 42      | 1         | 0.2%    |
| 40      | 1         | 0.2%    |
| 37      | 1         | 0.2%    |
| 20      | 1         | 0.2%    |
| 10      | 1         | 0.2%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 419       | 82.48%  |
| 201-300        | 28        | 5.51%   |
| 501-600        | 18        | 3.54%   |
| 351-400        | 15        | 2.95%   |
| 401-500        | 13        | 2.56%   |
| 601-700        | 4         | 0.79%   |
| More than 2000 | 3         | 0.59%   |
| Unknown        | 3         | 0.59%   |
| 801-900        | 2         | 0.39%   |
| 1001-1500      | 2         | 0.39%   |
| 901-1000       | 1         | 0.2%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 435       | 89.88%  |
| 16/10   | 39        | 8.06%   |
| 5/4     | 3         | 0.62%   |
| 1.00    | 3         | 0.62%   |
| Unknown | 3         | 0.62%   |
| 4/3     | 1         | 0.21%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 319       | 62.43%  |
| 81-90          | 91        | 17.81%  |
| 201-250        | 18        | 3.52%   |
| 61-70          | 13        | 2.54%   |
| 111-120        | 10        | 1.96%   |
| 121-130        | 9         | 1.76%   |
| 71-80          | 7         | 1.37%   |
| More than 1000 | 5         | 0.98%   |
| 51-60          | 5         | 0.98%   |
| 151-200        | 5         | 0.98%   |
| 141-150        | 5         | 0.98%   |
| 351-500        | 4         | 0.78%   |
| 301-350        | 4         | 0.78%   |
| 91-100         | 4         | 0.78%   |
| 251-300        | 3         | 0.59%   |
| 501-1000       | 3         | 0.59%   |
| Unknown        | 3         | 0.59%   |
| 131-140        | 2         | 0.39%   |
| 41-50          | 1         | 0.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 229       | 44.99%  |
| 101-120       | 192       | 37.72%  |
| 51-100        | 58        | 11.39%  |
| 161-240       | 14        | 2.75%   |
| More than 240 | 7         | 1.38%   |
| 1-50          | 6         | 1.18%   |
| Unknown       | 3         | 0.59%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 436       | 88.44%  |
| 2     | 44        | 8.92%   |
| 0     | 11        | 2.23%   |
| 3     | 2         | 0.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 319       | 39.73%  |
| Intel                             | 235       | 29.27%  |
| Qualcomm Atheros                  | 101       | 12.58%  |
| Broadcom                          | 63        | 7.85%   |
| MediaTek                          | 21        | 2.62%   |
| Ralink                            | 11        | 1.37%   |
| Ralink Technology                 | 10        | 1.25%   |
| Broadcom Limited                  | 10        | 1.25%   |
| Samsung Electronics               | 4         | 0.5%    |
| Marvell Technology Group          | 4         | 0.5%    |
| Huawei Technologies               | 4         | 0.5%    |
| Xiaomi                            | 3         | 0.37%   |
| TP-Link                           | 3         | 0.37%   |
| Sierra Wireless                   | 2         | 0.25%   |
| Nvidia                            | 2         | 0.25%   |
| Dell                              | 2         | 0.25%   |
| ASIX Electronics                  | 2         | 0.25%   |
| VIA Technologies                  | 1         | 0.12%   |
| Qualcomm                          | 1         | 0.12%   |
| JMicron Technology                | 1         | 0.12%   |
| Hewlett-Packard                   | 1         | 0.12%   |
| Ericsson Business Mobile Networks | 1         | 0.12%   |
| D-Link                            | 1         | 0.12%   |
| Belkin Components                 | 1         | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 192       | 20.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 100       | 10.55%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 35        | 3.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 22        | 2.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 20        | 2.11%   |
| Intel Wireless 8265 / 8275                                             | 18        | 1.9%    |
| Broadcom BCM43142 802.11b/g/n                                          | 18        | 1.9%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 16        | 1.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 16        | 1.69%   |
| Intel Wireless 8260                                                    | 16        | 1.69%   |
| Intel Wireless 7265                                                    | 16        | 1.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 15        | 1.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 14        | 1.48%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 14        | 1.48%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 14        | 1.48%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 13        | 1.37%   |
| Intel Wireless 7260                                                    | 12        | 1.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 12        | 1.27%   |
| Intel Ethernet Connection I217-LM                                      | 10        | 1.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 9         | 0.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 9         | 0.95%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 9         | 0.95%   |
| Intel Wi-Fi 6 AX201                                                    | 9         | 0.95%   |
| Intel Wi-Fi 6 AX200                                                    | 9         | 0.95%   |
| Broadcom BCM43228 802.11a/b/g/n                                        | 9         | 0.95%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 8         | 0.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 8         | 0.84%   |
| Intel Wireless 3160                                                    | 8         | 0.84%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 8         | 0.84%   |
| Intel 82577LM Gigabit Network Connection                               | 8         | 0.84%   |
| Intel Ethernet Connection (16) I219-LM                                 | 7         | 0.74%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 7         | 0.74%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                       | 7         | 0.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 6         | 0.63%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 6         | 0.63%   |
| Ralink MT7601U Wireless Adapter                                        | 6         | 0.63%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                      | 6         | 0.63%   |
| Intel Ethernet Connection I219-LM                                      | 6         | 0.63%   |
| Intel Ethernet Connection (2) I219-LM                                  | 6         | 0.63%   |
| Intel Centrino Advanced-N 6235                                         | 6         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 222       | 43.96%  |
| Qualcomm Atheros      | 91        | 18.02%  |
| Realtek Semiconductor | 82        | 16.24%  |
| Broadcom              | 52        | 10.3%   |
| MediaTek              | 19        | 3.76%   |
| Ralink                | 11        | 2.18%   |
| Ralink Technology     | 10        | 1.98%   |
| Broadcom Limited      | 9         | 1.78%   |
| TP-Link               | 2         | 0.4%    |
| Sierra Wireless       | 2         | 0.4%    |
| Dell                  | 2         | 0.4%    |
| Qualcomm              | 1         | 0.2%    |
| D-Link                | 1         | 0.2%    |
| Belkin Components     | 1         | 0.2%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 35        | 6.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 22        | 4.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 20        | 3.94%   |
| Intel Wireless 8265 / 8275                                     | 18        | 3.54%   |
| Broadcom BCM43142 802.11b/g/n                                  | 18        | 3.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 16        | 3.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 16        | 3.15%   |
| Intel Wireless 8260                                            | 16        | 3.15%   |
| Intel Wireless 7265                                            | 16        | 3.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 14        | 2.76%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 14        | 2.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 14        | 2.76%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 13        | 2.56%   |
| Intel Wireless 7260                                            | 12        | 2.36%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 12        | 2.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 9         | 1.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 9         | 1.77%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 9         | 1.77%   |
| Intel Wi-Fi 6 AX201                                            | 9         | 1.77%   |
| Intel Wi-Fi 6 AX200                                            | 9         | 1.77%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 9         | 1.77%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 8         | 1.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 8         | 1.57%   |
| Intel Wireless 3160                                            | 8         | 1.57%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 8         | 1.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 7         | 1.38%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 6         | 1.18%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 6         | 1.18%   |
| Ralink MT7601U Wireless Adapter                                | 6         | 1.18%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter              | 6         | 1.18%   |
| Intel Centrino Advanced-N 6235                                 | 6         | 1.18%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 5         | 0.98%   |
| Intel Wireless 3165                                            | 5         | 0.98%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 4         | 0.79%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 4         | 0.79%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 4         | 0.79%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 4         | 0.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 0.79%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 4         | 0.79%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 299       | 69.37%  |
| Intel                    | 81        | 18.79%  |
| Qualcomm Atheros         | 17        | 3.94%   |
| Broadcom                 | 15        | 3.48%   |
| Marvell Technology Group | 4         | 0.93%   |
| Xiaomi                   | 3         | 0.7%    |
| Nvidia                   | 2         | 0.46%   |
| MediaTek                 | 2         | 0.46%   |
| Huawei Technologies      | 2         | 0.46%   |
| ASIX Electronics         | 2         | 0.46%   |
| VIA Technologies         | 1         | 0.23%   |
| TP-Link                  | 1         | 0.23%   |
| JMicron Technology       | 1         | 0.23%   |
| Broadcom Limited         | 1         | 0.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 192       | 44.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 100       | 23.15%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 15        | 3.47%   |
| Intel Ethernet Connection I217-LM                                      | 10        | 2.31%   |
| Intel 82577LM Gigabit Network Connection                               | 8         | 1.85%   |
| Intel Ethernet Connection (16) I219-LM                                 | 7         | 1.62%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                       | 7         | 1.62%   |
| Intel Ethernet Connection I219-LM                                      | 6         | 1.39%   |
| Intel Ethernet Connection (2) I219-LM                                  | 6         | 1.39%   |
| Intel Ethernet Connection (4) I219-LM                                  | 5         | 1.16%   |
| Realtek Killer E2600 GbE Controller                                    | 4         | 0.93%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 4         | 0.93%   |
| Intel Ethernet Connection I218-LM                                      | 4         | 0.93%   |
| Intel Ethernet Connection (7) I219-LM                                  | 4         | 0.93%   |
| Intel Ethernet Connection (3) I218-LM                                  | 4         | 0.93%   |
| Intel 82567LM Gigabit Network Connection                               | 4         | 0.93%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 3         | 0.69%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 0.69%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 0.46%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 0.46%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2         | 0.46%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 2         | 0.46%   |
| Nvidia MCP79 Ethernet                                                  | 2         | 0.46%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 2         | 0.46%   |
| Intel Ethernet Connection (13) I219-V                                  | 2         | 0.46%   |
| Intel 82579V Gigabit Network Connection                                | 2         | 0.46%   |
| Intel 82566MM Gigabit Network Connection                               | 2         | 0.46%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 2         | 0.46%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1         | 0.23%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 0.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 0.23%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.23%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 0.23%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 1         | 0.23%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.23%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                          | 1         | 0.23%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 1         | 0.23%   |
| MediaTek Infinix SMART 5                                               | 1         | 0.23%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 0.23%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                   | 1         | 0.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 479       | 52.7%   |
| Ethernet | 422       | 46.42%  |
| Modem    | 8         | 0.88%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 408       | 82.09%  |
| Ethernet | 89        | 17.91%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 411       | 84.74%  |
| 1     | 66        | 13.61%  |
| 0     | 5         | 1.03%   |
| 3     | 3         | 0.62%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 482       | 99.18%  |
| Yes  | 4         | 0.82%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 180       | 43.48%  |
| Qualcomm Atheros Communications | 58        | 14.01%  |
| Realtek Semiconductor           | 56        | 13.53%  |
| Broadcom                        | 29        | 7%      |
| IMC Networks                    | 21        | 5.07%   |
| Lite-On Technology              | 11        | 2.66%   |
| Hewlett-Packard                 | 11        | 2.66%   |
| Toshiba                         | 10        | 2.42%   |
| Foxconn / Hon Hai               | 10        | 2.42%   |
| Ralink                          | 8         | 1.93%   |
| Dell                            | 7         | 1.69%   |
| Cambridge Silicon Radio         | 3         | 0.72%   |
| MediaTek                        | 2         | 0.48%   |
| Foxconn International           | 2         | 0.48%   |
| Apple                           | 2         | 0.48%   |
| Taiyo Yuden                     | 1         | 0.24%   |
| Realtek                         | 1         | 0.24%   |
| Ralink Technology               | 1         | 0.24%   |
| Edimax Technology               | 1         | 0.24%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 77        | 18.6%   |
| Intel AX201 Bluetooth                               | 41        | 9.9%    |
| Qualcomm Atheros  Bluetooth Device                  | 40        | 9.66%   |
| Realtek Bluetooth Radio                             | 33        | 7.97%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 30        | 7.25%   |
| IMC Networks Wireless_Device                        | 14        | 3.38%   |
| Realtek  Bluetooth 4.2 Adapter                      | 10        | 2.42%   |
| Ralink RT3290 Bluetooth                             | 8         | 1.93%   |
| Intel AX200 Bluetooth                               | 8         | 1.93%   |
| HP Broadcom 2070 Bluetooth Combo                    | 8         | 1.93%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 7         | 1.69%   |
| Intel AX211 Bluetooth                               | 7         | 1.69%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 7         | 1.69%   |
| Realtek RTL8821A Bluetooth                          | 6         | 1.45%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 6         | 1.45%   |
| Broadcom HP Portable Bumble Bee                     | 6         | 1.45%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 5         | 1.21%   |
| Realtek RTL8723B Bluetooth                          | 4         | 0.97%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 0.97%   |
| IMC Networks Bluetooth Radio                        | 4         | 0.97%   |
| Dell Wireless 365 Bluetooth                         | 4         | 0.97%   |
| Toshiba RT Bluetooth Radio                          | 3         | 0.72%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 0.72%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 0.72%   |
| Lite-On Bluetooth Device                            | 3         | 0.72%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 0.72%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 0.72%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 0.72%   |
| Dell DW375 Bluetooth Module                         | 3         | 0.72%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 0.72%   |
| Broadcom HP Portable SoftSailing                    | 3         | 0.72%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 3         | 0.72%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 0.72%   |
| Toshiba Integrated Bluetooth HCI                    | 2         | 0.48%   |
| Toshiba Askey Bluetooth Module                      | 2         | 0.48%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 0.48%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.48%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 2         | 0.48%   |
| Lite-On Wireless_Device                             | 2         | 0.48%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 403       | 66.39%  |
| Nvidia                 | 104       | 17.13%  |
| AMD                    | 88        | 14.5%   |
| ASUSTek Computer       | 3         | 0.49%   |
| JMTek                  | 2         | 0.33%   |
| Conexant Systems       | 2         | 0.33%   |
| VIA Technologies       | 1         | 0.16%   |
| Texas Instruments      | 1         | 0.16%   |
| Logitech               | 1         | 0.16%   |
| Generalplus Technology | 1         | 0.16%   |
| C-Media Electronics    | 1         | 0.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 70        | 9.54%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 36        | 4.9%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 35        | 4.77%   |
| Intel Cannon Lake PCH cAVS                                                 | 33        | 4.5%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 30        | 4.09%   |
| Intel 8 Series HD Audio Controller                                         | 27        | 3.68%   |
| Intel Haswell-ULT HD Audio Controller                                      | 25        | 3.41%   |
| Intel Broadwell-U Audio Controller                                         | 22        | 3%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 22        | 3%      |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 21        | 2.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 21        | 2.86%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 18        | 2.45%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 18        | 2.45%   |
| AMD FCH Azalia Controller                                                  | 17        | 2.32%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 16        | 2.18%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 16        | 2.18%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 16        | 2.18%   |
| Nvidia GP107GL High Definition Audio Controller                            | 15        | 2.04%   |
| Intel Comet Lake PCH cAVS                                                  | 15        | 2.04%   |
| Nvidia GA107 High Definition Audio Controller                              | 14        | 1.91%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 14        | 1.91%   |
| Intel Comet Lake PCH-LP cAVS                                               | 12        | 1.63%   |
| Intel CM238 HD Audio Controller                                            | 12        | 1.63%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 12        | 1.63%   |
| AMD Kabini HDMI/DP Audio                                                   | 12        | 1.63%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 11        | 1.5%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 11        | 1.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 10        | 1.36%   |
| AMD High Definition Audio Controller                                       | 9         | 1.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8         | 1.09%   |
| AMD Trinity HDMI Audio Controller                                          | 8         | 1.09%   |
| Nvidia TU116 High Definition Audio Controller                              | 7         | 0.95%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 7         | 0.95%   |
| Nvidia TU106 High Definition Audio Controller                              | 6         | 0.82%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 6         | 0.82%   |
| Nvidia GF119 HDMI Audio Controller                                         | 5         | 0.68%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 0.54%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4         | 0.54%   |
| Nvidia GK106 HDMI Audio Controller                                         | 4         | 0.54%   |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 90        | 32.26%  |
| SK hynix            | 70        | 25.09%  |
| Micron Technology   | 45        | 16.13%  |
| Crucial             | 23        | 8.24%   |
| Kingston            | 16        | 5.73%   |
| Ramaxel Technology  | 12        | 4.3%    |
| Unknown             | 6         | 2.15%   |
| Elpida              | 5         | 1.79%   |
| Nanya Technology    | 4         | 1.43%   |
| Team                | 2         | 0.72%   |
| Unknown             | 2         | 0.72%   |
| Unknown (ABCD)      | 1         | 0.36%   |
| Lexar Co Limited    | 1         | 0.36%   |
| G.Skill             | 1         | 0.36%   |
| Axiom               | 1         | 0.36%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 7         | 2.43%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s     | 6         | 2.08%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s    | 5         | 1.74%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s     | 5         | 1.74%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 4         | 1.39%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s    | 4         | 1.39%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s     | 4         | 1.39%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s    | 4         | 1.39%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s | 3         | 1.04%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s    | 3         | 1.04%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 3         | 1.04%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 3         | 1.04%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s     | 3         | 1.04%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 3         | 1.04%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s     | 3         | 1.04%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s  | 3         | 1.04%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s    | 3         | 1.04%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s    | 3         | 1.04%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s     | 3         | 1.04%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s     | 3         | 1.04%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s      | 3         | 1.04%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s     | 3         | 1.04%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4GB SODIMM DDR4 2133MT/s     | 3         | 1.04%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s      | 3         | 1.04%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s      | 3         | 1.04%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 2667MT/s    | 2         | 0.69%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s    | 2         | 0.69%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 2         | 0.69%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s   | 2         | 0.69%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s              | 2         | 0.69%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s     | 2         | 0.69%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s     | 2         | 0.69%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s     | 2         | 0.69%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 0.69%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 0.69%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s     | 2         | 0.69%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 2         | 0.69%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s    | 2         | 0.69%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s     | 2         | 0.69%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s     | 2         | 0.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 134       | 59.29%  |
| DDR3    | 72        | 31.86%  |
| SDRAM   | 5         | 2.21%   |
| DDR5    | 5         | 2.21%   |
| LPDDR4  | 4         | 1.77%   |
| LPDDR3  | 2         | 0.88%   |
| LPDDR5  | 1         | 0.44%   |
| DDR2    | 1         | 0.44%   |
| DDR     | 1         | 0.44%   |
| Unknown | 1         | 0.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 214       | 96.83%  |
| Row Of Chips | 5         | 2.26%   |
| DIMM         | 1         | 0.45%   |
| Chip         | 1         | 0.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 98        | 39.52%  |
| 4096  | 66        | 26.61%  |
| 16384 | 58        | 23.39%  |
| 2048  | 21        | 8.47%   |
| 32768 | 2         | 0.81%   |
| 1024  | 2         | 0.81%   |
| 512   | 1         | 0.4%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 72        | 29.27%  |
| 1600    | 52        | 21.14%  |
| 3200    | 50        | 20.33%  |
| 1334    | 14        | 5.69%   |
| 2400    | 13        | 5.28%   |
| 2133    | 11        | 4.47%   |
| 1333    | 8         | 3.25%   |
| 4800    | 5         | 2.03%   |
| 4199    | 3         | 1.22%   |
| 1866    | 3         | 1.22%   |
| 8400    | 2         | 0.81%   |
| 3266    | 2         | 0.81%   |
| 2048    | 2         | 0.81%   |
| 1867    | 2         | 0.81%   |
| 800     | 2         | 0.81%   |
| Unknown | 2         | 0.81%   |
| 6400    | 1         | 0.41%   |
| 4266    | 1         | 0.41%   |
| 667     | 1         | 0.41%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 2         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| HP LaserJet 1018 | 1         | 50%     |
| HP Deskjet 1510  | 1         | 50%     |

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
| Chicony Electronics                    | 102       | 23.02%  |
| Microdia                               | 60        | 13.54%  |
| IMC Networks                           | 46        | 10.38%  |
| Realtek Semiconductor                  | 38        | 8.58%   |
| Cheng Uei Precision Industry (Foxlink) | 38        | 8.58%   |
| Sunplus Innovation Technology          | 29        | 6.55%   |
| Lite-On Technology                     | 23        | 5.19%   |
| Bison Electronics                      | 20        | 4.51%   |
| Quanta                                 | 15        | 3.39%   |
| Suyin                                  | 13        | 2.93%   |
| Acer                                   | 12        | 2.71%   |
| Syntek                                 | 9         | 2.03%   |
| Silicon Motion                         | 9         | 2.03%   |
| Sonix Technology                       | 6         | 1.35%   |
| Apple                                  | 5         | 1.13%   |
| Luxvisions Innotech Limited            | 4         | 0.9%    |
| Lenovo                                 | 2         | 0.45%   |
| ShineTech                              | 1         | 0.23%   |
| OmniVision Technologies                | 1         | 0.23%   |
| Microsoft                              | 1         | 0.23%   |
| MacroSilicon                           | 1         | 0.23%   |
| Jieli Technology                       | 1         | 0.23%   |
| Intel                                  | 1         | 0.23%   |
| Genesys Logic                          | 1         | 0.23%   |
| Foxconn / Hon Hai                      | 1         | 0.23%   |
| eMPIA Technology                       | 1         | 0.23%   |
| ALi                                    | 1         | 0.23%   |
| Alcor Micro                            | 1         | 0.23%   |
| Unknown                                | 1         | 0.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                              | 34        | 7.66%   |
| Realtek Integrated_Webcam_HD                                               | 17        | 3.83%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 14        | 3.15%   |
| IMC Networks Integrated Camera                                             | 13        | 2.93%   |
| Chicony EasyCamera                                                         | 13        | 2.93%   |
| Chicony Integrated Camera                                                  | 12        | 2.7%    |
| Chicony HP HD Camera                                                       | 11        | 2.48%   |
| Sunplus Integrated_Webcam_HD                                               | 9         | 2.03%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 9         | 2.03%   |
| Lite-On HP HD Webcam                                                       | 8         | 1.8%    |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 8         | 1.8%    |
| Suyin HP Truevision HD                                                     | 7         | 1.58%   |
| Chicony HP TrueVision HD Camera                                            | 7         | 1.58%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 7         | 1.58%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 7         | 1.58%   |
| Realtek Integrated Webcam HD                                               | 6         | 1.35%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 6         | 1.35%   |
| Lite-On HP HD Camera                                                       | 6         | 1.35%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                           | 6         | 1.35%   |
| Syntek Integrated Camera                                                   | 5         | 1.13%   |
| Lite-On Integrated Camera                                                  | 5         | 1.13%   |
| Bison Lenovo EasyCamera                                                    | 5         | 1.13%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 4         | 0.9%    |
| Realtek Integrated Webcam                                                  | 4         | 0.9%    |
| Realtek EasyCamera                                                         | 4         | 0.9%    |
| Microdia Dell Laptop Integrated Webcam HD                                  | 4         | 0.9%    |
| Microdia 1.3 MPixel Integrated Webcam                                      | 4         | 0.9%    |
| IMC Networks EasyCamera                                                    | 4         | 0.9%    |
| Chicony USB2.0 VGA UVC WebCam                                              | 4         | 0.9%    |
| Chicony TOSHIBA Web Camera - HD                                            | 4         | 0.9%    |
| Chicony HP HD Webcam                                                       | 4         | 0.9%    |
| Bison EasyCamera                                                           | 4         | 0.9%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                                         | 4         | 0.9%    |
| Acer Lenovo EasyCamera                                                     | 4         | 0.9%    |
| Acer HP TrueVision HD                                                      | 4         | 0.9%    |
| Syntek EasyCamera                                                          | 3         | 0.68%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 3         | 0.68%   |
| Sunplus Dell HD Webcam                                                     | 3         | 0.68%   |
| Quanta HP TrueVision HD Camera                                             | 3         | 0.68%   |
| Quanta HD User Facing                                                      | 3         | 0.68%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 46        | 54.76%  |
| Synaptics                          | 16        | 19.05%  |
| Shenzhen Goodix Technology         | 9         | 10.71%  |
| AuthenTec                          | 6         | 7.14%   |
| Upek                               | 5         | 5.95%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 1.19%   |
| Elan Microelectronics              | 1         | 1.19%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 22        | 26.19%  |
| Validity Sensors Fingerprint scanner                                       | 6         | 7.14%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 5.95%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 5.95%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 4.76%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 4.76%   |
| Synaptics  WBDI                                                            | 4         | 4.76%   |
| Shenzhen Goodix  Fingerprint Device                                        | 4         | 4.76%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 4.76%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 3.57%   |
| AuthenTec AES2810                                                          | 3         | 3.57%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 2.38%   |
| Validity Sensors VFS491                                                    | 2         | 2.38%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 2.38%   |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 2.38%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 1.19%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 1.19%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 1.19%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 1.19%   |
| Synaptics UWP WBDI Device                                                  | 1         | 1.19%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 1.19%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.19%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 1.19%   |
| Elan ELAN:ARM-M4                                                           | 1         | 1.19%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 1.19%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.19%   |
| AuthenTec AES1600                                                          | 1         | 1.19%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 27        | 79.41%  |
| Alcor Micro | 4         | 11.76%  |
| O2 Micro    | 2         | 5.88%   |
| Lenovo      | 1         | 2.94%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 11        | 32.35%  |
| Broadcom 5880                                                                | 9         | 26.47%  |
| Broadcom 58200                                                               | 4         | 11.76%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 11.76%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 8.82%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 5.88%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 2.94%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 284       | 56.69%  |
| 1     | 171       | 34.13%  |
| 2     | 41        | 8.18%   |
| 3     | 4         | 0.8%    |
| 4     | 1         | 0.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 83        | 32.17%  |
| Graphics card            | 72        | 27.91%  |
| Chipcard                 | 30        | 11.63%  |
| Net/wireless             | 27        | 10.47%  |
| Multimedia controller    | 12        | 4.65%   |
| Bluetooth                | 11        | 4.26%   |
| Storage                  | 5         | 1.94%   |
| Net/ethernet             | 5         | 1.94%   |
| Sound                    | 3         | 1.16%   |
| Communication controller | 3         | 1.16%   |
| Camera                   | 3         | 1.16%   |
| Wireless                 | 1         | 0.39%   |
| Storage/ide              | 1         | 0.39%   |
| Network                  | 1         | 0.39%   |
| Card reader              | 1         | 0.39%   |


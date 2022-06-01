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

Total: 229

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.17.5-76051705-generic  | 108       | 58.06%  |
| 5.16.19-76051619-generic | 69        | 37.1%   |
| 5.17.5-051705-generic    | 2         | 1.08%   |
| 5.16.15-76051615-generic | 2         | 1.08%   |
| 5.18.0-051800rc1-generic | 1         | 0.54%   |
| 5.17.7-051707-generic    | 1         | 0.54%   |
| 5.17.6-051706-generic    | 1         | 0.54%   |
| 5.17.2-xanmod1           | 1         | 0.54%   |
| 5.17.0-051700-generic    | 1         | 0.54%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17.5  | 110       | 59.14%  |
| 5.16.19 | 69        | 37.1%   |
| 5.16.15 | 2         | 1.08%   |
| 5.18.0  | 1         | 0.54%   |
| 5.17.7  | 1         | 0.54%   |
| 5.17.6  | 1         | 0.54%   |
| 5.17.2  | 1         | 0.54%   |
| 5.17.0  | 1         | 0.54%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17    | 114       | 61.29%  |
| 5.16    | 71        | 38.17%  |
| 5.18    | 1         | 0.54%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 182       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 181       | 98.91%  |
| GNOME Flashback | 1         | 0.55%   |
| Unknown         | 1         | 0.55%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 175       | 95.63%  |
| Wayland | 7         | 3.83%   |
| Unknown | 1         | 0.55%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 137       | 75.27%  |
| GDM3    | 44        | 24.18%  |
| GDM     | 1         | 0.55%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 114       | 62.3%   |
| en_GB   | 13        | 7.1%    |
| pt_BR   | 12        | 6.56%   |
| fr_FR   | 9         | 4.92%   |
| de_DE   | 6         | 3.28%   |
| pl_PL   | 3         | 1.64%   |
| it_IT   | 3         | 1.64%   |
| en_AU   | 3         | 1.64%   |
| pt_PT   | 2         | 1.09%   |
| es_ES   | 2         | 1.09%   |
| en_NZ   | 2         | 1.09%   |
| de_CH   | 2         | 1.09%   |
| sv_SE   | 1         | 0.55%   |
| ru_RU   | 1         | 0.55%   |
| nb_NO   | 1         | 0.55%   |
| fr_BE   | 1         | 0.55%   |
| es_GT   | 1         | 0.55%   |
| es_AR   | 1         | 0.55%   |
| en_ZA   | 1         | 0.55%   |
| en_SG   | 1         | 0.55%   |
| en_PH   | 1         | 0.55%   |
| en_IN   | 1         | 0.55%   |
| en_CA   | 1         | 0.55%   |
| Unknown | 1         | 0.55%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 138       | 75.82%  |
| EFI  | 44        | 24.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Ext4  | 175       | 96.15%  |
| Btrfs | 6         | 3.3%    |
| Xfs   | 1         | 0.55%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 137       | 74.86%  |
| GPT     | 43        | 23.5%   |
| MBR     | 3         | 1.64%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 176       | 96.7%   |
| Yes       | 6         | 3.3%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 169       | 92.35%  |
| Yes       | 14        | 7.65%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 37        | 20.33%  |
| Lenovo              | 30        | 16.48%  |
| Hewlett-Packard     | 22        | 12.09%  |
| ASUSTek Computer    | 21        | 11.54%  |
| Apple               | 14        | 7.69%   |
| Acer                | 14        | 7.69%   |
| Toshiba             | 7         | 3.85%   |
| MSI                 | 7         | 3.85%   |
| System76            | 5         | 2.75%   |
| Google              | 4         | 2.2%    |
| Samsung Electronics | 3         | 1.65%   |
| HUAWEI              | 3         | 1.65%   |
| Fujitsu             | 2         | 1.1%    |
| TUXEDO              | 1         | 0.55%   |
| Semp Toshiba        | 1         | 0.55%   |
| Razer               | 1         | 0.55%   |
| Purism              | 1         | 0.55%   |
| PC Specialist       | 1         | 0.55%   |
| Monster             | 1         | 0.55%   |
| Medion              | 1         | 0.55%   |
| LG Electronics      | 1         | 0.55%   |
| Gigabyte Technology | 1         | 0.55%   |
| Framework           | 1         | 0.55%   |
| Alienware           | 1         | 0.55%   |
| A-DATA Technology   | 1         | 0.55%   |
| Unknown             | 1         | 0.55%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| System76 Oryx Pro                           | 4         | 2.2%    |
| HP Pavilion Notebook                        | 2         | 1.1%    |
| HP OMEN Laptop 15-en0xxx                    | 2         | 1.1%    |
| Google Lulu                                 | 2         | 1.1%    |
| Dell XPS 15 9510                            | 2         | 1.1%    |
| Dell XPS 13 9310                            | 2         | 1.1%    |
| Dell Inspiron 5566                          | 2         | 1.1%    |
| Apple MacBookAir6,2                         | 2         | 1.1%    |
| Acer Aspire A515-45                         | 2         | 1.1%    |
| Unknown                                     | 2         | 1.1%    |
| Toshiba Satellite P850                      | 1         | 0.55%   |
| Toshiba Satellite L755                      | 1         | 0.55%   |
| Toshiba Satellite L50D-C                    | 1         | 0.55%   |
| Toshiba Satellite L10W-B-101                | 1         | 0.55%   |
| Toshiba Satellite C55t-C                    | 1         | 0.55%   |
| Toshiba QOSMIO X770                         | 1         | 0.55%   |
| Toshiba PORTEGE R830                        | 1         | 0.55%   |
| System76 Pangolin                           | 1         | 0.55%   |
| Semp Toshiba IS 1413G                       | 1         | 0.55%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 1         | 0.55%   |
| Samsung 800G5M/800G5W                       | 1         | 0.55%   |
| Samsung 550XCJ/550XCR                       | 1         | 0.55%   |
| Razer Blade 14 - RZ09-0370                  | 1         | 0.55%   |
| Purism Librem 15 v3                         | 1         | 0.55%   |
| PC Specialist NP5x_NP6x_NP7xPNK_PNH_PNJ     | 1         | 0.55%   |
| MSI Modern 15 A10RAS                        | 1         | 0.55%   |
| MSI Modern 14 A10M                          | 1         | 0.55%   |
| MSI GS66 Stealth 10UG                       | 1         | 0.55%   |
| MSI GS65 Stealth 8SG                        | 1         | 0.55%   |
| MSI GS63 7RD                                | 1         | 0.55%   |
| MSI GP76 Leopard 11UG                       | 1         | 0.55%   |
| MSI GF63 Thin 10SCXR                        | 1         | 0.55%   |
| Monster TULPAR T5 V14.1                     | 1         | 0.55%   |
| Medion X6816                                | 1         | 0.55%   |
| LG P430-G.BC41P1                            | 1         | 0.55%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 D 82NJ        | 1         | 0.55%   |
| Lenovo V14-IIL 82C4                         | 1         | 0.55%   |
| Lenovo ThinkPad X220 4286CTO                | 1         | 0.55%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD001XUS    | 1         | 0.55%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BSCTO1WW    | 1         | 0.55%   |
| Lenovo ThinkPad Twist 33472YU               | 1         | 0.55%   |
| Lenovo ThinkPad T480 20L6S8H100             | 1         | 0.55%   |
| Lenovo ThinkPad T480 20L5S00F00             | 1         | 0.55%   |
| Lenovo ThinkPad T480 20L50004UK             | 1         | 0.55%   |
| Lenovo ThinkPad T431s 20ACS03P00            | 1         | 0.55%   |
| Lenovo ThinkPad T410 2537HN3                | 1         | 0.55%   |
| Lenovo ThinkPad T14s Gen 1 20UJ001CMX       | 1         | 0.55%   |
| Lenovo ThinkPad T14 Gen 1 20UD003RPB        | 1         | 0.55%   |
| Lenovo ThinkPad T14 Gen 1 20S00057GE        | 1         | 0.55%   |
| Lenovo ThinkPad L15 Gen 2 20X4S68100        | 1         | 0.55%   |
| Lenovo ThinkPad L13 Yoga Gen 2a 21AES01A00  | 1         | 0.55%   |
| Lenovo ThinkPad E14 Gen 4 21ECS00000        | 1         | 0.55%   |
| Lenovo ThinkPad E14 Gen 3 20Y7004ETX        | 1         | 0.55%   |
| Lenovo Legion 7 16ITHg6 82K6                | 1         | 0.55%   |
| Lenovo Legion 5 17ITH6H 82JM                | 1         | 0.55%   |
| Lenovo Legion 5 15IMH05H 81Y6               | 1         | 0.55%   |
| Lenovo IdeaPad Y700-17ISK 80Q0              | 1         | 0.55%   |
| Lenovo IdeaPad S340-15API 81NC              | 1         | 0.55%   |
| Lenovo IdeaPad S145-15API 81V7              | 1         | 0.55%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY        | 1         | 0.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 16        | 8.79%   |
| Dell Inspiron      | 12        | 6.59%   |
| Dell XPS           | 10        | 5.49%   |
| Acer Aspire        | 9         | 4.95%   |
| Lenovo IdeaPad     | 7         | 3.85%   |
| Toshiba Satellite  | 5         | 2.75%   |
| Dell Latitude      | 5         | 2.75%   |
| ASUS ROG           | 5         | 2.75%   |
| System76 Oryx      | 4         | 2.2%    |
| HP Pavilion        | 4         | 2.2%    |
| HP Laptop          | 4         | 2.2%    |
| HP EliteBook       | 4         | 2.2%    |
| Dell Vostro        | 4         | 2.2%    |
| Lenovo Legion      | 3         | 1.65%   |
| HP ProBook         | 3         | 1.65%   |
| HP OMEN            | 3         | 1.65%   |
| MSI Modern         | 2         | 1.1%    |
| Google Lulu        | 2         | 1.1%    |
| Dell Precision     | 2         | 1.1%    |
| ASUS VivoBook      | 2         | 1.1%    |
| Apple MacBookPro14 | 2         | 1.1%    |
| Apple MacBookAir6  | 2         | 1.1%    |
| Acer TravelMate    | 2         | 1.1%    |
| Acer Nitro         | 2         | 1.1%    |
| Unknown            | 2         | 1.1%    |
| Toshiba QOSMIO     | 1         | 0.55%   |
| Toshiba PORTEGE    | 1         | 0.55%   |
| System76 Pangolin  | 1         | 0.55%   |
| Semp Toshiba IS    | 1         | 0.55%   |
| Samsung RV411      | 1         | 0.55%   |
| Samsung 800G5M     | 1         | 0.55%   |
| Samsung 550XCJ     | 1         | 0.55%   |
| Razer Blade        | 1         | 0.55%   |
| Purism Librem      | 1         | 0.55%   |
| PC Specialist NP5x | 1         | 0.55%   |
| MSI GS66           | 1         | 0.55%   |
| MSI GS65           | 1         | 0.55%   |
| MSI GS63           | 1         | 0.55%   |
| MSI GP76           | 1         | 0.55%   |
| MSI GF63           | 1         | 0.55%   |
| Monster TULPAR     | 1         | 0.55%   |
| Medion X6816       | 1         | 0.55%   |
| LG P430-G.BC41P1   | 1         | 0.55%   |
| Lenovo Yoga        | 1         | 0.55%   |
| Lenovo V14-IIL     | 1         | 0.55%   |
| Lenovo G50-80      | 1         | 0.55%   |
| Lenovo G40-30      | 1         | 0.55%   |
| HUAWEI NBLB-WAX9N  | 1         | 0.55%   |
| HUAWEI HVY-WXX9    | 1         | 0.55%   |
| HUAWEI HN-WX9X     | 1         | 0.55%   |
| HP ZBook           | 1         | 0.55%   |
| HP Victus          | 1         | 0.55%   |
| HP ENVY            | 1         | 0.55%   |
| HP 15              | 1         | 0.55%   |
| Google Peppy       | 1         | 0.55%   |
| Google Cyan        | 1         | 0.55%   |
| Gigabyte AERO      | 1         | 0.55%   |
| Fujitsu LIFEBOOK   | 1         | 0.55%   |
| Fujitsu CELSIUS    | 1         | 0.55%   |
| Framework Laptop   | 1         | 0.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 34        | 18.68%  |
| 2021 | 31        | 17.03%  |
| 2019 | 15        | 8.24%   |
| 2018 | 13        | 7.14%   |
| 2016 | 13        | 7.14%   |
| 2017 | 12        | 6.59%   |
| 2014 | 11        | 6.04%   |
| 2011 | 11        | 6.04%   |
| 2013 | 10        | 5.49%   |
| 2015 | 9         | 4.95%   |
| 2009 | 7         | 3.85%   |
| 2012 | 6         | 3.3%    |
| 2022 | 5         | 2.75%   |
| 2010 | 4         | 2.2%    |
| 2008 | 1         | 0.55%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 182       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 182       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 174       | 95.6%   |
| Yes  | 8         | 4.4%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 58        | 31.87%  |
| 16.01-24.0  | 40        | 21.98%  |
| 8.01-16.0   | 33        | 18.13%  |
| 3.01-4.0    | 28        | 15.38%  |
| 32.01-64.0  | 17        | 9.34%   |
| 64.01-256.0 | 5         | 2.75%   |
| 1.01-2.0    | 1         | 0.55%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 65        | 34.95%  |
| 4.01-8.0   | 41        | 22.04%  |
| 3.01-4.0   | 38        | 20.43%  |
| 1.01-2.0   | 36        | 19.35%  |
| 8.01-16.0  | 4         | 2.15%   |
| 16.01-24.0 | 2         | 1.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 126       | 69.23%  |
| 2      | 51        | 28.02%  |
| 3      | 4         | 2.2%    |
| 0      | 1         | 0.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 141       | 77.47%  |
| Yes       | 41        | 22.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 137       | 75.27%  |
| No        | 45        | 24.73%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 180       | 98.9%   |
| No        | 2         | 1.1%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 157       | 85.79%  |
| No        | 26        | 14.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country               | Notebooks | Percent |
|-----------------------|-----------|---------|
| USA                   | 48        | 26.37%  |
| Brazil                | 20        | 10.99%  |
| Germany               | 12        | 6.59%   |
| India                 | 10        | 5.49%   |
| France                | 9         | 4.95%   |
| UK                    | 8         | 4.4%    |
| Australia             | 6         | 3.3%    |
| Canada                | 5         | 2.75%   |
| Sweden                | 3         | 1.65%   |
| Russia                | 3         | 1.65%   |
| Poland                | 3         | 1.65%   |
| New Zealand           | 3         | 1.65%   |
| Italy                 | 3         | 1.65%   |
| Argentina             | 3         | 1.65%   |
| Turkey                | 2         | 1.1%    |
| Switzerland           | 2         | 1.1%    |
| Spain                 | 2         | 1.1%    |
| Romania               | 2         | 1.1%    |
| Portugal              | 2         | 1.1%    |
| Philippines           | 2         | 1.1%    |
| Panama                | 2         | 1.1%    |
| Norway                | 2         | 1.1%    |
| Netherlands           | 2         | 1.1%    |
| Mexico                | 2         | 1.1%    |
| Malaysia              | 2         | 1.1%    |
| Hungary               | 2         | 1.1%    |
| Vietnam               | 1         | 0.55%   |
| Venezuela             | 1         | 0.55%   |
| Thailand              | 1         | 0.55%   |
| South Africa          | 1         | 0.55%   |
| Slovenia              | 1         | 0.55%   |
| Singapore             | 1         | 0.55%   |
| Saudi Arabia          | 1         | 0.55%   |
| Republic of the Congo | 1         | 0.55%   |
| Peru                  | 1         | 0.55%   |
| Morocco               | 1         | 0.55%   |
| Latvia                | 1         | 0.55%   |
| Japan                 | 1         | 0.55%   |
| Indonesia             | 1         | 0.55%   |
| Hong Kong             | 1         | 0.55%   |
| Guatemala             | 1         | 0.55%   |
| Greece                | 1         | 0.55%   |
| Finland               | 1         | 0.55%   |
| Egypt                 | 1         | 0.55%   |
| Czechia               | 1         | 0.55%   |
| Croatia               | 1         | 0.55%   |
| Bulgaria              | 1         | 0.55%   |
| Belgium               | 1         | 0.55%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Sao Paulo                 | 3         | 1.62%   |
| Melbourne                 | 3         | 1.62%   |
| Warsaw                    | 2         | 1.08%   |
| Tallahassee               | 2         | 1.08%   |
| Sydney                    | 2         | 1.08%   |
| Rio de Janeiro            | 2         | 1.08%   |
| Quezon City               | 2         | 1.08%   |
| Panama City               | 2         | 1.08%   |
| Mumbai                    | 2         | 1.08%   |
| Mendoza                   | 2         | 1.08%   |
| Itatiba                   | 2         | 1.08%   |
| Istanbul                  | 2         | 1.08%   |
| Durham                    | 2         | 1.08%   |
| Catunda                   | 2         | 1.08%   |
| Budapest                  | 2         | 1.08%   |
| Bengaluru                 | 2         | 1.08%   |
| Bamberg                   | 2         | 1.08%   |
| Zurich                    | 1         | 0.54%   |
| Zagreb                    | 1         | 0.54%   |
| Yogyakarta                | 1         | 0.54%   |
| Winnipeg                  | 1         | 0.54%   |
| Visakhapatnam             | 1         | 0.54%   |
| Vila Velha                | 1         | 0.54%   |
| Vaihingen an der Enz      | 1         | 0.54%   |
| Uhldingen-Muhlhofen       | 1         | 0.54%   |
| Turin                     | 1         | 0.54%   |
| Truckee                   | 1         | 0.54%   |
| Todmorden                 | 1         | 0.54%   |
| Timișoara                | 1         | 0.54%   |
| The Hague                 | 1         | 0.54%   |
| Tauranga                  | 1         | 0.54%   |
| Tangier                   | 1         | 0.54%   |
| Stuttgart                 | 1         | 0.54%   |
| Sturgeon Bay              | 1         | 0.54%   |
| Stockport                 | 1         | 0.54%   |
| Stockholm                 | 1         | 0.54%   |
| Staten Island             | 1         | 0.54%   |
| Stanmore                  | 1         | 0.54%   |
| Springfield               | 1         | 0.54%   |
| Somerset                  | 1         | 0.54%   |
| Sittingbourne             | 1         | 0.54%   |
| Singapore                 | 1         | 0.54%   |
| Siebnen                   | 1         | 0.54%   |
| Seattle                   | 1         | 0.54%   |
| Saratov                   | 1         | 0.54%   |
| Sao Sebastiao do Paraiso  | 1         | 0.54%   |
| Sao Carlos                | 1         | 0.54%   |
| Santa Rosa                | 1         | 0.54%   |
| Sandton                   | 1         | 0.54%   |
| San Miguel                | 1         | 0.54%   |
| San Jose                  | 1         | 0.54%   |
| San Francisco             | 1         | 0.54%   |
| San Diego                 | 1         | 0.54%   |
| San Antonio               | 1         | 0.54%   |
| Saint-Hilaire-sur-Benaize | 1         | 0.54%   |
| Saint-Denis               | 1         | 0.54%   |
| Riyadh                    | 1         | 0.54%   |
| Riverview                 | 1         | 0.54%   |
| Riga                      | 1         | 0.54%   |
| Remscheid                 | 1         | 0.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 41        | 46     | 17.98%  |
| WDC                         | 24        | 26     | 10.53%  |
| SanDisk                     | 17        | 19     | 7.46%   |
| Seagate                     | 15        | 17     | 6.58%   |
| Toshiba                     | 13        | 15     | 5.7%    |
| SK Hynix                    | 12        | 12     | 5.26%   |
| Unknown                     | 10        | 12     | 4.39%   |
| Kingston                    | 10        | 11     | 4.39%   |
| Micron Technology           | 9         | 9      | 3.95%   |
| Apple                       | 9         | 10     | 3.95%   |
| HGST                        | 7         | 7      | 3.07%   |
| Intel                       | 6         | 6      | 2.63%   |
| Crucial                     | 6         | 6      | 2.63%   |
| A-DATA Technology           | 6         | 7      | 2.63%   |
| PNY                         | 5         | 5      | 2.19%   |
| Silicon Motion              | 4         | 4      | 1.75%   |
| Phison                      | 4         | 4      | 1.75%   |
| Hitachi                     | 4         | 4      | 1.75%   |
| ADATA Technology            | 4         | 4      | 1.75%   |
| MyDigitalSSD                | 3         | 3      | 1.32%   |
| KIOXIA                      | 3         | 3      | 1.32%   |
| Union Memory (Shenzhen)     | 2         | 3      | 0.88%   |
| KingSpec                    | 2         | 2      | 0.88%   |
| YMTC                        | 1         | 1      | 0.44%   |
| USB3.0                      | 1         | 1      | 0.44%   |
| Team                        | 1         | 1      | 0.44%   |
| Ramaxel Technology          | 1         | 1      | 0.44%   |
| PNY USB                     | 1         | 1      | 0.44%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.44%   |
| LITEONIT                    | 1         | 1      | 0.44%   |
| Lexar                       | 1         | 1      | 0.44%   |
| KINGBANK                    | 1         | 1      | 0.44%   |
| Fujitsu                     | 1         | 1      | 0.44%   |
| Apacer                      | 1         | 1      | 0.44%   |
| Aarvex                      | 1         | 1      | 0.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| SK Hynix NVMe SSD Drive 512GB        | 6         | 2.56%   |
| Samsung NVMe SSD Drive 512GB         | 4         | 1.71%   |
| ADATA NVMe SSD Drive 256GB           | 4         | 1.71%   |
| Unknown MMC Card  32GB               | 3         | 1.28%   |
| SK Hynix NVMe SSD Drive 1024GB       | 3         | 1.28%   |
| Seagate ST1000LM049-2GH172 1TB       | 3         | 1.28%   |
| Sandisk NVMe SSD Drive 512GB         | 3         | 1.28%   |
| Sandisk NVMe SSD Drive 1TB           | 3         | 1.28%   |
| Samsung SSD 850 EVO 500GB            | 3         | 1.28%   |
| Samsung NVMe SSD Drive 2TB           | 3         | 1.28%   |
| Samsung NVMe SSD Drive 256GB         | 3         | 1.28%   |
| Samsung NVMe SSD Drive 1024GB        | 3         | 1.28%   |
| PNY CS900 240GB SSD                  | 3         | 1.28%   |
| Unknown MMC Card  128GB              | 2         | 0.85%   |
| Toshiba MQ04ABF100 1TB               | 2         | 0.85%   |
| Toshiba MQ01ABD100 1TB               | 2         | 0.85%   |
| Seagate ST9320325AS 320GB            | 2         | 0.85%   |
| Seagate ST2000LM007-1R8174 2TB       | 2         | 0.85%   |
| Seagate ST1000LM048-2E7172 1TB       | 2         | 0.85%   |
| SanDisk SSD PLUS 240 GB              | 2         | 0.85%   |
| Samsung SSD 970 EVO Plus 1TB         | 2         | 0.85%   |
| Samsung NVMe SSD Drive 1TB           | 2         | 0.85%   |
| Samsung MZVLB1T0HBLR-000L7 1TB       | 2         | 0.85%   |
| MyDigitalSSD SB M2 SSD 240GB         | 2         | 0.85%   |
| Micron NVMe SSD Drive 512GB          | 2         | 0.85%   |
| Kingston SA400S37240G 240GB SSD      | 2         | 0.85%   |
| Kingston SA400S37120G 120GB SSD      | 2         | 0.85%   |
| Intel SSDPEKKW256G7 256GB            | 2         | 0.85%   |
| HGST HTS721010A9E630 1TB             | 2         | 0.85%   |
| Crucial CT1000BX500SSD1 1TB          | 2         | 0.85%   |
| Apple SSD SM0512G 500GB              | 2         | 0.85%   |
| YMTC PC005 512GB                     | 1         | 0.43%   |
| WDC WDS250G2B0B-00YS70 250GB SSD     | 1         | 0.43%   |
| WDC WDS240G2G0C-00AJM0 240GB         | 1         | 0.43%   |
| WDC WDS240G1G0B-00RC30 240GB SSD     | 1         | 0.43%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1         | 0.43%   |
| WDC WDS100T2B0C-00PXH0 1TB           | 1         | 0.43%   |
| WDC WDBNCE0010PNC 1TB SSD            | 1         | 0.43%   |
| WDC WD800BEVS-07RST0 80GB            | 1         | 0.43%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 0.43%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 1         | 0.43%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 1         | 0.43%   |
| WDC WD5000BPVT-22HXZT3 500GB         | 1         | 0.43%   |
| WDC WD5000BEVT-60A0RT0 500GB         | 1         | 0.43%   |
| WDC WD2500LPLX-00ZNTT0 250GB         | 1         | 0.43%   |
| WDC WD10SPZX-35Z10T0 1TB             | 1         | 0.43%   |
| WDC WD10SPZX-24Z10 1TB               | 1         | 0.43%   |
| WDC WD10SPZX-17Z10T1 1TB             | 1         | 0.43%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.43%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.43%   |
| WDC WD Green 2.5 1000GB              | 1         | 0.43%   |
| WDC WD easystore 240GB               | 1         | 0.43%   |
| WDC PC SN730 SDBPNTY-1T00-1032 1TB   | 1         | 0.43%   |
| WDC PC SN720 SDAPNTW-512G-1006 512GB | 1         | 0.43%   |
| WDC PC SN530 SDBPNPZ-512G-1014 512GB | 1         | 0.43%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB | 1         | 0.43%   |
| USB3.0 Super Speed 240GB             | 1         | 0.43%   |
| Unknown SE32G  32GB                  | 1         | 0.43%   |
| Unknown NVMe SSD Drive 1024GB        | 1         | 0.43%   |
| Unknown MMC Card  7GB                | 1         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 17     | 30.61%  |
| WDC                 | 12        | 14     | 24.49%  |
| Toshiba             | 8         | 10     | 16.33%  |
| HGST                | 7         | 7      | 14.29%  |
| Hitachi             | 4         | 4      | 8.16%   |
| Samsung Electronics | 1         | 1      | 2.04%   |
| Fujitsu             | 1         | 1      | 2.04%   |
| Apple               | 1         | 1      | 2.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 14     | 19.44%  |
| SanDisk             | 10        | 11     | 13.89%  |
| Kingston            | 7         | 7      | 9.72%   |
| Apple               | 6         | 6      | 8.33%   |
| WDC                 | 5         | 5      | 6.94%   |
| PNY                 | 5         | 5      | 6.94%   |
| Crucial             | 5         | 5      | 6.94%   |
| MyDigitalSSD        | 3         | 3      | 4.17%   |
| A-DATA Technology   | 3         | 4      | 4.17%   |
| Micron Technology   | 2         | 2      | 2.78%   |
| KingSpec            | 2         | 2      | 2.78%   |
| USB3.0              | 1         | 1      | 1.39%   |
| Toshiba             | 1         | 1      | 1.39%   |
| Ramaxel Technology  | 1         | 1      | 1.39%   |
| PNY USB             | 1         | 1      | 1.39%   |
| LITEONIT            | 1         | 1      | 1.39%   |
| Lexar               | 1         | 1      | 1.39%   |
| KINGBANK            | 1         | 1      | 1.39%   |
| Intel               | 1         | 1      | 1.39%   |
| Apacer              | 1         | 1      | 1.39%   |
| Aarvex              | 1         | 1      | 1.39%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 86        | 106    | 40.38%  |
| SSD     | 70        | 74     | 32.86%  |
| HDD     | 47        | 55     | 22.07%  |
| MMC     | 9         | 11     | 4.23%   |
| Unknown | 1         | 1      | 0.47%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 106       | 125    | 51.21%  |
| NVMe | 86        | 105    | 41.55%  |
| MMC  | 9         | 11     | 4.35%   |
| SAS  | 6         | 6      | 2.9%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 80        | 91     | 69.57%  |
| 0.51-1.0   | 30        | 33     | 26.09%  |
| 1.01-2.0   | 5         | 5      | 4.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 60        | 32.79%  |
| 251-500        | 57        | 31.15%  |
| 501-1000       | 40        | 21.86%  |
| 1001-2000      | 10        | 5.46%   |
| 51-100         | 7         | 3.83%   |
| 21-50          | 5         | 2.73%   |
| 2001-3000      | 2         | 1.09%   |
| More than 3000 | 1         | 0.55%   |
| Unknown        | 1         | 0.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 58        | 31.35%  |
| 21-50     | 51        | 27.57%  |
| 101-250   | 28        | 15.14%  |
| 51-100    | 24        | 12.97%  |
| 251-500   | 17        | 9.19%   |
| 501-1000  | 4         | 2.16%   |
| 1001-2000 | 2         | 1.08%   |
| Unknown   | 1         | 0.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Toshiba MQ01ACF050 500GB           | 1         | 1      | 25%     |
| Seagate ST9320325AS 320GB          | 1         | 1      | 25%     |
| Seagate ST500LM030-2E717D 500GB    | 1         | 1      | 25%     |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 75%     |
| Toshiba | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 75%     |
| Toshiba | 1         | 1      | 25%     |

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
| Detected | 139       | 187    | 73.94%  |
| Works    | 45        | 56     | 23.94%  |
| Malfunc  | 4         | 4      | 2.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 109       | 47.39%  |
| Samsung Electronics          | 30        | 13.04%  |
| AMD                          | 22        | 9.57%   |
| SK Hynix                     | 12        | 5.22%   |
| Sandisk                      | 12        | 5.22%   |
| Micron Technology            | 7         | 3.04%   |
| ADATA Technology             | 6         | 2.61%   |
| Silicon Motion               | 5         | 2.17%   |
| Toshiba America Info Systems | 4         | 1.74%   |
| Phison Electronics           | 4         | 1.74%   |
| Nvidia                       | 4         | 1.74%   |
| KIOXIA                       | 3         | 1.3%    |
| Union Memory (Shenzhen)      | 2         | 0.87%   |
| Kingston Technology Company  | 2         | 0.87%   |
| Apple                        | 2         | 0.87%   |
| Yangtze Memory Technologies  | 1         | 0.43%   |
| Unknown                      | 1         | 0.43%   |
| Realtek Semiconductor        | 1         | 0.43%   |
| Micron/Crucial Technology    | 1         | 0.43%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.43%   |
| Marvell Technology Group     | 1         | 0.43%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 22        | 9.28%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 17        | 7.17%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 11        | 4.64%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 10        | 4.22%   |
| SK Hynix Gold P31 SSD                                                            | 9         | 3.8%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 9         | 3.8%    |
| Intel Volume Management Device NVMe RAID Controller                              | 8         | 3.38%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 8         | 3.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 8         | 3.38%   |
| Micron Non-Volatile memory controller                                            | 7         | 2.95%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 7         | 2.95%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 7         | 2.95%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 5         | 2.11%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 5         | 2.11%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 5         | 2.11%   |
| ADATA Non-Volatile memory controller                                             | 5         | 2.11%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 4         | 1.69%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 1.69%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 1.69%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 1.69%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 3         | 1.27%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 1.27%   |
| Samsung Electronics SATA controller                                              | 3         | 1.27%   |
| Nvidia MCP79 AHCI Controller                                                     | 3         | 1.27%   |
| KIOXIA Non-Volatile memory controller                                            | 3         | 1.27%   |
| Intel SSD 660P Series                                                            | 3         | 1.27%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 3         | 1.27%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 0.84%   |
| SK Hynix BC511                                                                   | 2         | 0.84%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 0.84%   |
| Phison E12 NVMe Controller                                                       | 2         | 0.84%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 2         | 0.84%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 2         | 0.84%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 0.84%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 0.84%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 0.84%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 0.84%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 0.84%   |
| Yangtze Memory Non-Volatile memory controller                                    | 1         | 0.42%   |
| Unknown Non-Volatile memory controller                                           | 1         | 0.42%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 0.42%   |
| Union Memory (Shenzhen) AM630 PCIe 4.0 x4 NVMe SSD Controller                    | 1         | 0.42%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.42%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 1         | 0.42%   |
| SK Hynix Non-Volatile memory controller                                          | 1         | 0.42%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 0.42%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.42%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.42%   |
| Sandisk Non-Volatile memory controller                                           | 1         | 0.42%   |
| Samsung Apple PCIe SSD                                                           | 1         | 0.42%   |
| Realtek Realtek Non-Volatile memory controller                                   | 1         | 0.42%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 0.42%   |
| Phison E18 PCIe4 NVMe Controller                                                 | 1         | 0.42%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 1         | 0.42%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 1         | 0.42%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1001                                     | 1         | 0.42%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                       | 1         | 0.42%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1         | 0.42%   |
| Kingston Company A2000 NVMe SSD                                                  | 1         | 0.42%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 1         | 0.42%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 116       | 51.1%   |
| NVMe | 86        | 37.89%  |
| RAID | 20        | 8.81%   |
| IDE  | 5         | 2.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 141       | 77.47%  |
| AMD    | 41        | 22.53%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 9         | 4.95%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 2.2%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 4         | 2.2%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 2.2%    |
| AMD Ryzen 7 5700U with Radeon Graphics        | 4         | 2.2%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.65%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 1.65%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 3         | 1.65%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 1.65%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 3         | 1.65%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 1.65%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 1.65%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.65%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 3         | 1.65%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.1%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 1.1%    |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 1.1%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.1%    |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 2         | 1.1%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.1%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.1%    |
| Intel Core i5-10300H CPU @ 2.50GHz            | 2         | 1.1%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.1%    |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 2         | 1.1%    |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.1%    |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2         | 1.1%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 1.1%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 1.1%    |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 2         | 1.1%    |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 2         | 1.1%    |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 1.1%    |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 1.1%    |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 1.1%    |
| AMD Ryzen 3 3250U with Radeon Graphics        | 2         | 1.1%    |
| AMD A6-7310 APU with AMD Radeon R4 Graphics   | 2         | 1.1%    |
| Intel Pentium CPU P6100 @ 2.00GHz             | 1         | 0.55%   |
| Intel Pentium CPU 987 @ 1.50GHz               | 1         | 0.55%   |
| Intel Pentium CPU 2117U @ 1.80GHz             | 1         | 0.55%   |
| Intel Core i9-10885H CPU @ 2.40GHz            | 1         | 0.55%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.55%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 0.55%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 0.55%   |
| Intel Core i7-7920HQ CPU @ 3.10GHz            | 1         | 0.55%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.55%   |
| Intel Core i7-5650U CPU @ 2.20GHz             | 1         | 0.55%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz            | 1         | 0.55%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 0.55%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 1         | 0.55%   |
| Intel Core i7-4750HQ CPU @ 2.00GHz            | 1         | 0.55%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 0.55%   |
| Intel Core i7-4650U CPU @ 1.70GHz             | 1         | 0.55%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 0.55%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 0.55%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 0.55%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 0.55%   |
| Intel Core i7-3687U CPU @ 2.10GHz             | 1         | 0.55%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 0.55%   |
| Intel Core i7-3615QM CPU @ 2.30GHz            | 1         | 0.55%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 0.55%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 53        | 29.12%  |
| Intel Core i5    | 32        | 17.58%  |
| Other            | 21        | 11.54%  |
| Intel Core i3    | 16        | 8.79%   |
| AMD Ryzen 7      | 12        | 6.59%   |
| AMD Ryzen 5      | 11        | 6.04%   |
| Intel Core 2 Duo | 9         | 4.95%   |
| Intel Celeron    | 6         | 3.3%    |
| AMD Ryzen 9      | 5         | 2.75%   |
| AMD A8           | 4         | 2.2%    |
| Intel Pentium    | 3         | 1.65%   |
| AMD Ryzen 7 PRO  | 3         | 1.65%   |
| AMD Ryzen 3      | 2         | 1.1%    |
| AMD A6           | 2         | 1.1%    |
| Intel Core i9    | 1         | 0.55%   |
| Intel Atom       | 1         | 0.55%   |
| AMD Ryzen 5 PRO  | 1         | 0.55%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 66        | 36.26%  |
| 2      | 66        | 36.26%  |
| 8      | 33        | 18.13%  |
| 6      | 16        | 8.79%   |
| 14     | 1         | 0.55%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 182       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 152       | 83.52%  |
| 1      | 30        | 16.48%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 182       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 132       | 72.53%  |
| 0x806ec    | 5         | 2.75%   |
| 0x806d1    | 5         | 2.75%   |
| 0x806e9    | 3         | 1.65%   |
| 0x706e5    | 3         | 1.65%   |
| 0x40651    | 3         | 1.65%   |
| 0x0a50000c | 3         | 1.65%   |
| 0x08600106 | 3         | 1.65%   |
| 0xa0652    | 2         | 1.1%    |
| 0x906e9    | 2         | 1.1%    |
| 0x806ea    | 2         | 1.1%    |
| 0x806c2    | 2         | 1.1%    |
| 0x506e3    | 2         | 1.1%    |
| 0x406e3    | 2         | 1.1%    |
| 0x906ea    | 1         | 0.55%   |
| 0x906a3    | 1         | 0.55%   |
| 0x806eb    | 1         | 0.55%   |
| 0x806c1    | 1         | 0.55%   |
| 0x306c3    | 1         | 0.55%   |
| 0x306a9    | 1         | 0.55%   |
| 0x1067a    | 1         | 0.55%   |
| 0x0a404101 | 1         | 0.55%   |
| 0x08608103 | 1         | 0.55%   |
| 0x08600104 | 1         | 0.55%   |
| 0x08600103 | 1         | 0.55%   |
| 0x08108109 | 1         | 0.55%   |
| 0x0810100b | 1         | 0.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 33        | 18.13%  |
| Haswell          | 17        | 9.34%   |
| Zen 2            | 11        | 6.04%   |
| CometLake        | 11        | 6.04%   |
| Zen 3            | 10        | 5.49%   |
| TigerLake        | 10        | 5.49%   |
| IceLake          | 10        | 5.49%   |
| Unknown          | 10        | 5.49%   |
| SandyBridge      | 9         | 4.95%   |
| Penryn           | 9         | 4.95%   |
| IvyBridge        | 9         | 4.95%   |
| Broadwell        | 9         | 4.95%   |
| Skylake          | 8         | 4.4%    |
| Zen+             | 6         | 3.3%    |
| Silvermont       | 5         | 2.75%   |
| Puma             | 5         | 2.75%   |
| Westmere         | 4         | 2.2%    |
| Zen              | 1         | 0.55%   |
| Nehalem          | 1         | 0.55%   |
| K10 Llano        | 1         | 0.55%   |
| Goldmont         | 1         | 0.55%   |
| Excavator        | 1         | 0.55%   |
| Alderlake Hybrid | 1         | 0.55%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 124       | 51.03%  |
| Nvidia | 69        | 28.4%   |
| AMD    | 50        | 20.58%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 4.84%   |
| AMD Renoir                                                                               | 11        | 4.44%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10        | 4.03%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 10        | 4.03%   |
| AMD Cezanne                                                                              | 9         | 3.63%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 7         | 2.82%   |
| Intel HD Graphics 5500                                                                   | 7         | 2.82%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 2.82%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 2.82%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 6         | 2.42%   |
| Intel UHD Graphics 620                                                                   | 6         | 2.42%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 6         | 2.42%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 2.42%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 2.42%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 2.42%   |
| Intel HD Graphics 630                                                                    | 5         | 2.02%   |
| Intel HD Graphics 620                                                                    | 5         | 2.02%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 5         | 2.02%   |
| Nvidia TU117M                                                                            | 4         | 1.61%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 1.61%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 4         | 1.61%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.61%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.61%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 1.61%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.61%   |
| AMD Lucienne                                                                             | 4         | 1.61%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 1.21%   |
| Nvidia GP108M [GeForce MX330]                                                            | 3         | 1.21%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.21%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.21%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.21%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 1.21%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 1.21%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.81%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 0.81%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 2         | 0.81%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.81%   |
| Intel HD Graphics 530                                                                    | 2         | 0.81%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 0.81%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 2         | 0.81%   |
| AMD Rembrandt [Radeon 680M]                                                              | 2         | 0.81%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 2         | 0.81%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.4%    |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.4%    |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.4%    |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                                  | 1         | 0.4%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.4%    |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 1         | 0.4%    |
| Nvidia TU104M [GeForce RTX 2080 Mobile]                                                  | 1         | 0.4%    |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.4%    |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.4%    |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.4%    |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.4%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.4%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.4%    |
| Nvidia GM108M [GeForce 930M]                                                             | 1         | 0.4%    |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 0.4%    |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.4%    |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 0.4%    |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 0.4%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 76        | 41.76%  |
| Intel + Nvidia | 42        | 23.08%  |
| 1 x AMD        | 28        | 15.38%  |
| 1 x Nvidia     | 13        | 7.14%   |
| AMD + Nvidia   | 13        | 7.14%   |
| Intel + AMD    | 5         | 2.75%   |
| 2 x AMD        | 4         | 2.2%    |
| 2 x Nvidia     | 1         | 0.55%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 122       | 66.67%  |
| Proprietary | 56        | 30.6%   |
| Unknown     | 5         | 2.73%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 147       | 80.33%  |
| 3.01-4.0   | 10        | 5.46%   |
| 7.01-8.0   | 7         | 3.83%   |
| 1.01-2.0   | 7         | 3.83%   |
| 0.01-0.5   | 5         | 2.73%   |
| 5.01-6.0   | 4         | 2.19%   |
| 0.51-1.0   | 2         | 1.09%   |
| 8.01-16.0  | 1         | 0.55%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 37        | 17.54%  |
| AU Optronics        | 35        | 16.59%  |
| Chimei Innolux      | 31        | 14.69%  |
| LG Display          | 29        | 13.74%  |
| Samsung Electronics | 16        | 7.58%   |
| Sharp               | 12        | 5.69%   |
| Apple               | 11        | 5.21%   |
| Dell                | 8         | 3.79%   |
| PANDA               | 5         | 2.37%   |
| Goldstar            | 4         | 1.9%    |
| AOC                 | 3         | 1.42%   |
| Lenovo              | 2         | 0.95%   |
| InfoVision          | 2         | 0.95%   |
| CSO                 | 2         | 0.95%   |
| Acer                | 2         | 0.95%   |
| Vizio               | 1         | 0.47%   |
| TMX                 | 1         | 0.47%   |
| TCL                 | 1         | 0.47%   |
| SGT                 | 1         | 0.47%   |
| Philips             | 1         | 0.47%   |
| MSI                 | 1         | 0.47%   |
| LG Electronics      | 1         | 0.47%   |
| KDC                 | 1         | 0.47%   |
| Iiyama              | 1         | 0.47%   |
| Eizo                | 1         | 0.47%   |
| ASUSTek Computer    | 1         | 0.47%   |
| Unknown             | 1         | 0.47%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 4         | 1.89%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.42%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch         | 3         | 1.42%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 2         | 0.94%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 2         | 0.94%   |
| Samsung Electronics LCD Monitor SDC834D 1920x1080 293x165mm 13.2-inch | 2         | 0.94%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 2         | 0.94%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch           | 2         | 0.94%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 0.94%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 2         | 0.94%   |
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                     | 2         | 0.94%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 2         | 0.94%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 340x190mm 15.3-inch       | 2         | 0.94%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 2         | 0.94%   |
| BOE LCD Monitor BOE08DF 1920x1080 344x194mm 15.5-inch                 | 2         | 0.94%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 2         | 0.94%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO4999 1920x1080 344x193mm 15.5-inch        | 2         | 0.94%   |
| Vizio D320-B1 VIZ0095 1360x768 697x392mm 31.5-inch                    | 1         | 0.47%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch               | 1         | 0.47%   |
| TCL LCD TV TCL0030 1920x1080 708x398mm 32.0-inch                      | 1         | 0.47%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 380x210mm 17.1-inch               | 1         | 0.47%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 1         | 0.47%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch               | 1         | 0.47%   |
| Sharp LCD Monitor SHP14CB 1920x1200 288x180mm 13.4-inch               | 1         | 0.47%   |
| Sharp LCD Monitor SHP14AE 1920x1080 294x165mm 13.3-inch               | 1         | 0.47%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch               | 1         | 0.47%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch               | 1         | 0.47%   |
| Sharp LCD Monitor SHP1420 1920x1080 294x165mm 13.3-inch               | 1         | 0.47%   |
| SGT HS160PC SGTA450 1920x1080 354x199mm 16.0-inch                     | 1         | 0.47%   |
| Samsung Electronics T24B350 SAM093E 1920x1080 531x299mm 24.0-inch     | 1         | 0.47%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC4641 1280x800 261x163mm 12.1-inch  | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch  | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 340x190mm 15.3-inch | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SDC544B 1600x900 309x174mm 14.0-inch  | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SDC414D 3456x2160 336x210mm 15.6-inch | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch | 1         | 0.47%   |
| Samsung Electronics CF791 SAM0DC8 3440x1440 797x333mm 34.0-inch       | 1         | 0.47%   |
| Samsung Electronics C43J89x SAM0F5B 3840x1200 1052x329mm 43.4-inch    | 1         | 0.47%   |
| Samsung Electronics C32JG5x SAM0F55 2560x1440 697x392mm 31.5-inch     | 1         | 0.47%   |
| Samsung Electronics C27JG5x SAM0F56 1920x1080 597x336mm 27.0-inch     | 1         | 0.47%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1         | 0.47%   |
| Philips 298P4 PHLC0BE 2560x1080 673x284mm 28.8-inch                   | 1         | 0.47%   |
| PANDA LCD Monitor NCP005F 1920x1080 344x194mm 15.5-inch               | 1         | 0.47%   |
| PANDA LCD Monitor NCP005D 1920x1080 381x214mm 17.2-inch               | 1         | 0.47%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 0.47%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.47%   |
| PANDA LCD Monitor NCP002B 1920x1080 309x174mm 14.0-inch               | 1         | 0.47%   |
| MSI G241 MSI3BA4 1920x1080 527x296mm 23.8-inch                        | 1         | 0.47%   |
| LG Electronics LCD Monitor M2262D                                     | 1         | 0.47%   |
| LG Display LCD Monitor LGD069B 1920x1080 344x194mm 15.5-inch          | 1         | 0.47%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch          | 1         | 0.47%   |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch          | 1         | 0.47%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch          | 1         | 0.47%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 0.47%   |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch          | 1         | 0.47%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch          | 1         | 0.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 97        | 48.02%  |
| 1366x768 (WXGA)   | 47        | 23.27%  |
| 2560x1440 (QHD)   | 9         | 4.46%   |
| 1600x900 (HD+)    | 9         | 4.46%   |
| 1920x1200 (WUXGA) | 7         | 3.47%   |
| 2560x1600         | 6         | 2.97%   |
| 1440x900 (WXGA+)  | 6         | 2.97%   |
| 3840x2160 (4K)    | 4         | 1.98%   |
| 2880x1800         | 3         | 1.49%   |
| 3440x1440         | 2         | 0.99%   |
| 1280x800 (WXGA)   | 2         | 0.99%   |
| 3840x2400         | 1         | 0.5%    |
| 3840x1200         | 1         | 0.5%    |
| 3840x1080         | 1         | 0.5%    |
| 3456x2160         | 1         | 0.5%    |
| 3200x1800 (QHD+)  | 1         | 0.5%    |
| 2560x1080         | 1         | 0.5%    |
| 2256x1504         | 1         | 0.5%    |
| 2160x1440         | 1         | 0.5%    |
| 1280x1080         | 1         | 0.5%    |
| Unknown           | 1         | 0.5%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 90        | 42.86%  |
| 13      | 35        | 16.67%  |
| 14      | 24        | 11.43%  |
| 17      | 14        | 6.67%   |
| 24      | 9         | 4.29%   |
| 27      | 7         | 3.33%   |
| 16      | 5         | 2.38%   |
| 23      | 4         | 1.9%    |
| 12      | 4         | 1.9%    |
| 11      | 4         | 1.9%    |
| 31      | 3         | 1.43%   |
| 34      | 2         | 0.95%   |
| 32      | 2         | 0.95%   |
| 21      | 2         | 0.95%   |
| 49      | 1         | 0.48%   |
| 43      | 1         | 0.48%   |
| 28      | 1         | 0.48%   |
| 22      | 1         | 0.48%   |
| Unknown | 1         | 0.48%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 128       | 60.66%  |
| 201-300     | 30        | 14.22%  |
| 501-600     | 19        | 9%      |
| 351-400     | 19        | 9%      |
| 601-700     | 5         | 2.37%   |
| 701-800     | 4         | 1.9%    |
| 401-500     | 3         | 1.42%   |
| 1001-1500   | 2         | 0.95%   |
| Unknown     | 1         | 0.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 154       | 80.63%  |
| 16/10   | 28        | 14.66%  |
| 3/2     | 3         | 1.57%   |
| 21/9    | 3         | 1.57%   |
| 32/9    | 1         | 0.52%   |
| 3.20    | 1         | 0.52%   |
| Unknown | 1         | 0.52%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 93        | 44.5%   |
| 81-90          | 42        | 20.1%   |
| 71-80          | 17        | 8.13%   |
| 201-250        | 14        | 6.7%    |
| 121-130        | 14        | 6.7%    |
| 301-350        | 7         | 3.35%   |
| 351-500        | 6         | 2.87%   |
| 61-70          | 4         | 1.91%   |
| 51-60          | 4         | 1.91%   |
| 251-300        | 3         | 1.44%   |
| 111-120        | 2         | 0.96%   |
| 501-1000       | 2         | 0.96%   |
| Unknown        | 1         | 0.48%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 98        | 46.89%  |
| 101-120       | 53        | 25.36%  |
| 51-100        | 26        | 12.44%  |
| 161-240       | 22        | 10.53%  |
| More than 240 | 8         | 3.83%   |
| 1-50          | 1         | 0.48%   |
| Unknown       | 1         | 0.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 145       | 79.23%  |
| 2     | 30        | 16.39%  |
| 0     | 5         | 2.73%   |
| 3     | 3         | 1.64%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 103       | 35.15%  |
| Intel                         | 86        | 29.35%  |
| Qualcomm Atheros              | 43        | 14.68%  |
| Broadcom                      | 17        | 5.8%    |
| MEDIATEK                      | 9         | 3.07%   |
| Broadcom Limited              | 9         | 3.07%   |
| TP-Link                       | 5         | 1.71%   |
| ASIX Electronics              | 4         | 1.37%   |
| Ralink                        | 3         | 1.02%   |
| Samsung Electronics           | 2         | 0.68%   |
| Ralink Technology             | 2         | 0.68%   |
| Nvidia                        | 2         | 0.68%   |
| NetGear                       | 2         | 0.68%   |
| Marvell Technology Group      | 2         | 0.68%   |
| OnePlus Technology (Shenzhen) | 1         | 0.34%   |
| Hewlett-Packard               | 1         | 0.34%   |
| DisplayLink                   | 1         | 0.34%   |
| Dell                          | 1         | 0.34%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 61        | 18.05%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 5.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 14        | 4.14%   |
| Intel Wi-Fi 6 AX200                                               | 12        | 3.55%   |
| Intel Wireless 8265 / 8275                                        | 9         | 2.66%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 8         | 2.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 2.07%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter     | 7         | 2.07%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 7         | 2.07%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 7         | 2.07%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 1.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 6         | 1.78%   |
| Intel Wi-Fi 6 AX201                                               | 6         | 1.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.48%   |
| Intel Wireless 7265                                               | 5         | 1.48%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 1.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.18%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 1.18%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 1.18%   |
| Intel Wireless 7260                                               | 4         | 1.18%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 1.18%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 1.18%   |
| Broadcom BCM43142 802.11b/g/n                                     | 4         | 1.18%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 3         | 0.89%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 0.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 0.89%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.89%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 3         | 0.89%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 0.89%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.59%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.59%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 0.59%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2         | 0.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.59%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.59%   |
| Intel Wireless-AC 9260                                            | 2         | 0.59%   |
| Intel Wireless 8260                                               | 2         | 0.59%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.59%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.59%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.59%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.59%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.59%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.59%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 0.59%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 2         | 0.59%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 2         | 0.59%   |
| TP-Link USB 10/100 LAN                                            | 1         | 0.3%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1         | 0.3%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1         | 0.3%    |
| TP-Link 802.11ac WLAN Adapter                                     | 1         | 0.3%    |
| TP-Link 802.11ac NIC                                              | 1         | 0.3%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.3%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.3%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.3%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1         | 0.3%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 0.3%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1         | 0.3%    |
| Realtek RTL8191SEvA Wireless LAN Controller                       | 1         | 0.3%    |
| Realtek RTL8188SU 802.11n WLAN Adapter                            | 1         | 0.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 84        | 43.75%  |
| Qualcomm Atheros      | 39        | 20.31%  |
| Realtek Semiconductor | 23        | 11.98%  |
| Broadcom              | 16        | 8.33%   |
| MEDIATEK              | 9         | 4.69%   |
| Broadcom Limited      | 9         | 4.69%   |
| TP-Link               | 4         | 2.08%   |
| Ralink                | 3         | 1.56%   |
| Ralink Technology     | 2         | 1.04%   |
| NetGear               | 2         | 1.04%   |
| Dell                  | 1         | 0.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                | 14        | 7.22%   |
| Intel Wi-Fi 6 AX200                                                       | 12        | 6.19%   |
| Intel Wireless 8265 / 8275                                                | 9         | 4.64%   |
| Intel Tiger Lake PCH CNVi WiFi                                            | 8         | 4.12%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter             | 7         | 3.61%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 7         | 3.61%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                | 7         | 3.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 6         | 3.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                | 6         | 3.09%   |
| Intel Wi-Fi 6 AX201                                                       | 6         | 3.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 5         | 2.58%   |
| Intel Wireless 7265                                                       | 5         | 2.58%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                         | 5         | 2.58%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                  | 4         | 2.06%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                          | 4         | 2.06%   |
| Intel Wireless 7260                                                       | 4         | 2.06%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                    | 4         | 2.06%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                  | 4         | 2.06%   |
| Broadcom BCM43142 802.11b/g/n                                             | 4         | 2.06%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                  | 3         | 1.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                          | 3         | 1.55%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                           | 3         | 1.55%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                    | 3         | 1.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                           | 2         | 1.03%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)            | 2         | 1.03%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)            | 2         | 1.03%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)            | 2         | 1.03%   |
| Intel Wireless-AC 9260                                                    | 2         | 1.03%   |
| Intel Wireless 8260                                                       | 2         | 1.03%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                               | 2         | 1.03%   |
| Broadcom BCM4331 802.11a/b/g/n                                            | 2         | 1.03%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                              | 1         | 0.52%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                       | 1         | 0.52%   |
| TP-Link 802.11ac WLAN Adapter                                             | 1         | 0.52%   |
| TP-Link 802.11ac NIC                                                      | 1         | 0.52%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 1         | 0.52%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                           | 1         | 0.52%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                           | 1         | 0.52%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                | 1         | 0.52%   |
| Realtek RTL8191SEvA Wireless LAN Controller                               | 1         | 0.52%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                    | 1         | 0.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                       | 1         | 0.52%   |
| Realtek RTL8188EE Wireless Network Adapter                                | 1         | 0.52%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                | 1         | 0.52%   |
| Realtek 802.11n WLAN Adapter                                              | 1         | 0.52%   |
| Realtek 802.11ac NIC                                                      | 1         | 0.52%   |
| Ralink RT5370 Wireless Adapter                                            | 1         | 0.52%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                         | 1         | 0.52%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                 | 1         | 0.52%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                 | 1         | 0.52%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                 | 1         | 0.52%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 0.52%   |
| NetGear A6210                                                             | 1         | 0.52%   |
| MEDIATEK WLAN controller                                                  | 1         | 0.52%   |
| MEDIATEK MT7922 802.11ax PCI Express Wireless Network Adapter             | 1         | 0.52%   |
| Intel Wireless 3165                                                       | 1         | 0.52%   |
| Intel Wireless 3160                                                       | 1         | 0.52%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                   | 1         | 0.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 1         | 0.52%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                           | 1         | 0.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 93        | 65.96%  |
| Intel                         | 23        | 16.31%  |
| Qualcomm Atheros              | 8         | 5.67%   |
| Broadcom                      | 4         | 2.84%   |
| ASIX Electronics              | 4         | 2.84%   |
| Samsung Electronics           | 2         | 1.42%   |
| Nvidia                        | 2         | 1.42%   |
| Marvell Technology Group      | 2         | 1.42%   |
| TP-Link                       | 1         | 0.71%   |
| OnePlus Technology (Shenzhen) | 1         | 0.71%   |
| DisplayLink                   | 1         | 0.71%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 61        | 42.96%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 12.68%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 4.93%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 2.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 2.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 2.11%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 2.11%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 1.41%   |
| Nvidia MCP79 Ethernet                                             | 2         | 1.41%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.41%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.41%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.41%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.41%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.41%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 1.41%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 1.41%   |
| TP-Link USB 10/100 LAN                                            | 1         | 0.7%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.7%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.7%    |
| Realtek Realtek Ethernet controller                               | 1         | 0.7%    |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.7%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.7%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.7%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.7%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.7%    |
| OnePlus (Shenzhen) OnePlus                                        | 1         | 0.7%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.7%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.7%    |
| Intel Ethernet Controller I225-V                                  | 1         | 0.7%    |
| Intel Ethernet controller                                         | 1         | 0.7%    |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.7%    |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.7%    |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.7%    |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.7%    |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.7%    |
| Intel Centrino Advanced-N + WiMAX 6250                            | 1         | 0.7%    |
| DisplayLink Dell Universal Dock D6000                             | 1         | 0.7%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.7%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 0.7%    |
| ASIX AX88772B Fast Ethernet Controller                            | 1         | 0.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 180       | 56.78%  |
| Ethernet | 135       | 42.59%  |
| Modem    | 1         | 0.32%   |
| Unknown  | 1         | 0.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 152       | 81.28%  |
| Ethernet | 35        | 18.72%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 122       | 67.03%  |
| 1     | 58        | 31.87%  |
| 3     | 1         | 0.55%   |
| 0     | 1         | 0.55%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 135       | 73.77%  |
| Yes  | 48        | 26.23%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 74        | 47.44%  |
| Qualcomm Atheros Communications | 18        | 11.54%  |
| Apple                           | 14        | 8.97%   |
| IMC Networks                    | 11        | 7.05%   |
| Realtek Semiconductor           | 10        | 6.41%   |
| Foxconn / Hon Hai               | 8         | 5.13%   |
| Lite-On Technology              | 6         | 3.85%   |
| Broadcom                        | 6         | 3.85%   |
| Toshiba                         | 3         | 1.92%   |
| Hewlett-Packard                 | 2         | 1.28%   |
| Realtek                         | 1         | 0.64%   |
| Ralink                          | 1         | 0.64%   |
| Foxconn International           | 1         | 0.64%   |
| Cambridge Silicon Radio         | 1         | 0.64%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 22        | 14.1%   |
| Intel Bluetooth wireless interface                  | 21        | 13.46%  |
| Qualcomm Atheros  Bluetooth Device                  | 13        | 8.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 12        | 7.69%   |
| Intel AX200 Bluetooth                               | 11        | 7.05%   |
| Apple Bluetooth USB Host Controller                 | 8         | 5.13%   |
| Realtek Bluetooth Radio                             | 6         | 3.85%   |
| IMC Networks Bluetooth Device                       | 6         | 3.85%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 2.56%   |
| Intel AX210 Bluetooth                               | 4         | 2.56%   |
| IMC Networks Wireless_Device                        | 4         | 2.56%   |
| Foxconn / Hon Hai Wireless_Device                   | 4         | 2.56%   |
| Apple Bluetooth Host Controller                     | 4         | 2.56%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 1.92%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 1.28%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 1.28%   |
| Lite-On Bluetooth Device                            | 2         | 1.28%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 1.28%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.64%   |
| Toshiba Bluetooth Radio                             | 1         | 0.64%   |
| Toshiba BCM43142A0                                  | 1         | 0.64%   |
| Realtek Bluetooth Radio                             | 1         | 0.64%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.64%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.64%   |
| Lite-On Wireless_Device                             | 1         | 0.64%   |
| Lite-On Qualcomm Atheros Bluetooth                  | 1         | 0.64%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.64%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.64%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.64%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.64%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.64%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.64%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.64%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.64%   |
| Foxconn / Hon Hai Acer Module                       | 1         | 0.64%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 0.64%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.64%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 0.64%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.64%   |
| Broadcom BCM20702A0 Bluetooth                       | 1         | 0.64%   |
| Broadcom BCM20702A0                                 | 1         | 0.64%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 0.64%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 0.64%   |
| Apple Bluetooth HCI                                 | 1         | 0.64%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 136       | 56.9%   |
| AMD                 | 45        | 18.83%  |
| Nvidia              | 43        | 17.99%  |
| Sony                | 2         | 0.84%   |
| Hewlett-Packard     | 2         | 0.84%   |
| GN Netcom           | 2         | 0.84%   |
| C-Media Electronics | 2         | 0.84%   |
| Texas Instruments   | 1         | 0.42%   |
| SteelSeries ApS     | 1         | 0.42%   |
| Lenovo              | 1         | 0.42%   |
| Kingston Technology | 1         | 0.42%   |
| JMTek               | 1         | 0.42%   |
| Apple               | 1         | 0.42%   |
| Antlion Audio       | 1         | 0.42%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 33        | 11.11%  |
| AMD Renoir Radeon High Definition Audio Controller                                                | 19        | 6.4%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 18        | 6.06%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 4.04%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 4.04%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 10        | 3.37%   |
| Intel Comet Lake PCH cAVS                                                                         | 10        | 3.37%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10        | 3.37%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 3.03%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 9         | 3.03%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 3.03%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 8         | 2.69%   |
| Nvidia Audio device                                                                               | 8         | 2.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 2.69%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 2.36%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 2.36%   |
| Intel CM238 HD Audio Controller                                                                   | 6         | 2.02%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 2.02%   |
| AMD FCH Azalia Controller                                                                         | 6         | 2.02%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 1.68%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 1.68%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 1.68%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.68%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.35%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 1.35%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.35%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 3         | 1.01%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 1.01%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 1.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.01%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.01%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.67%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.67%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.67%   |
| Hewlett-Packard USB Audio                                                                         | 2         | 0.67%   |
| GN Netcom Jabra Link 380                                                                          | 2         | 0.67%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 2         | 0.67%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                    | 2         | 0.67%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.34%   |
| SteelSeries ApS Siberia V2 Illuminated                                                            | 1         | 0.34%   |
| Sony Wireless Controller                                                                          | 1         | 0.34%   |
| Sony DualShock 4 [CUH-ZCT2x]                                                                      | 1         | 0.34%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.34%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.34%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.34%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.34%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.34%   |
| Lenovo ThinkPad Dock USB Audio                                                                    | 1         | 0.34%   |
| Kingston Technology HyperX Cloud Revolver S                                                       | 1         | 0.34%   |
| JMTek LCS USB Audio                                                                               | 1         | 0.34%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 0.34%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.34%   |
| Intel Audio device                                                                                | 1         | 0.34%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 0.34%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.34%   |
| Apple Audio Device                                                                                | 1         | 0.34%   |
| Antlion Audio Antlion Wireless Microphone                                                         | 1         | 0.34%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 0.34%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 18        | 31.58%  |
| SK Hynix            | 12        | 21.05%  |
| Micron Technology   | 6         | 10.53%  |
| Kingston            | 4         | 7.02%   |
| Unknown             | 3         | 5.26%   |
| Smart               | 3         | 5.26%   |
| Crucial             | 3         | 5.26%   |
| Neo Forza           | 2         | 3.51%   |
| Unknown (8A02)      | 1         | 1.75%   |
| Timetec             | 1         | 1.75%   |
| Corsair             | 1         | 1.75%   |
| Avant               | 1         | 1.75%   |
| A-DATA Technology   | 1         | 1.75%   |
| Unknown             | 1         | 1.75%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s           | 3         | 5%      |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 3.33%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s              | 1         | 1.67%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 1.67%   |
| Unknown RAM Module 16GB Row Of Chips LPDDR4 4267MT/s             | 1         | 1.67%   |
| Unknown (8A02) RAM 8G2400MHz 8GB SODIMM DDR4 2667MT/s            | 1         | 1.67%   |
| Timetec RAM 32NUS2R8-32G 32GB SODIMM DDR4 3200MT/s               | 1         | 1.67%   |
| Smart RAM SMS4WEC8C1K0446FCG 8GB SODIMM DDR4 3200MT/s            | 1         | 1.67%   |
| Smart RAM SG564568FG8NWKFSQR 2GB SODIMM DDR2 800MT/s             | 1         | 1.67%   |
| Smart RAM SF4641G8CKHIWDFSEG 8GB SODIMM DDR4 2133MT/s            | 1         | 1.67%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.67%   |
| SK Hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 1         | 1.67%   |
| SK Hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 1         | 1.67%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.67%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 1         | 1.67%   |
| SK Hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.67%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.67%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 1         | 1.67%   |
| SK Hynix RAM HCNNNCPMBLHR-NEE 8GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.67%   |
| SK Hynix RAM H9HCNNNCPMMLXR-NEE 8GB Row Of Chips LPDDR4 4266MT/s | 1         | 1.67%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.67%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 1         | 1.67%   |
| Samsung RAM Module 4GB SODIMM LPDDR3 2133MT/s                    | 1         | 1.67%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.67%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 1         | 1.67%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.67%   |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s        | 1         | 1.67%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.67%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.67%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.67%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.67%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 1         | 1.67%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.67%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s            | 1         | 1.67%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM 4800MT/s               | 1         | 1.67%   |
| Samsung RAM M425R1GB4BB0-CQKOD 8192MB SODIMM 4800MT/s            | 1         | 1.67%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s           | 1         | 1.67%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 1         | 1.67%   |
| Neo Forza RAM NMSO480E82-3200E 8GB SODIMM DDR4 3200MT/s          | 1         | 1.67%   |
| Neo Forza RAM NMSO416E82-3200E 16GB SODIMM DDR4 3200MT/s         | 1         | 1.67%   |
| Micron RAM MT53E1G32D4NQ-053 8GB Row Of Chips LPDDR4 3733MT/s    | 1         | 1.67%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8192MB SODIMM DDR4 3200MT/s          | 1         | 1.67%   |
| Micron RAM 4ATF51264HZ-2G6E3 4GB SODIMM DDR4 2667MT/s            | 1         | 1.67%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s            | 1         | 1.67%   |
| Micron RAM 4ATF51264HZ-2G2AZ 4GB SODIMM DDR4 2133MT/s            | 1         | 1.67%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB Row Of Chips DDR4 3200MT/s    | 1         | 1.67%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s             | 1         | 1.67%   |
| Kingston RAM KHX3200C20S4/16G 16GB SODIMM DDR4 3200MT/s          | 1         | 1.67%   |
| Kingston RAM KF3200C20S4/16G 16GB SODIMM DDR4 3200MT/s           | 1         | 1.67%   |
| Kingston RAM 9905700-097.A00G 8GB SODIMM DDR4 3200MT/s           | 1         | 1.67%   |
| Crucial RAM CT8G4SFS832A.C8FP 8GB SODIMM DDR4 3200MT/s           | 1         | 1.67%   |
| Crucial RAM CT8G4SFS8266.C8FE 8GB SODIMM DDR4 2667MT/s           | 1         | 1.67%   |
| Crucial RAM CT32G4SFD832A.C16FB 32GB SODIMM DDR4 3200MT/s        | 1         | 1.67%   |
| Corsair RAM CM4X16GF3200C22S2 16GB SODIMM DDR4 3200MT/s          | 1         | 1.67%   |
| Avant RAM J644GU44J2320NF 32GB SODIMM DDR4 3200MT/s              | 1         | 1.67%   |
| A-DATA RAM AO1P26KC8T1-BPXS 8GB SODIMM DDR4 2667MT/s             | 1         | 1.67%   |
| Unknown                                                          | 1         | 1.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 33        | 66%     |
| LPDDR4  | 6         | 12%     |
| LPDDR3  | 4         | 8%      |
| DDR3    | 4         | 8%      |
| SDRAM   | 1         | 2%      |
| DDR2    | 1         | 2%      |
| Unknown | 1         | 2%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 39        | 78%     |
| Row Of Chips | 11        | 22%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 26        | 50%     |
| 16384 | 11        | 21.15%  |
| 4096  | 9         | 17.31%  |
| 32768 | 3         | 5.77%   |
| 2048  | 3         | 5.77%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 18        | 33.33%  |
| 2667  | 13        | 24.07%  |
| 2133  | 7         | 12.96%  |
| 4267  | 4         | 7.41%   |
| 1600  | 3         | 5.56%   |
| 1333  | 2         | 3.7%    |
| 4800  | 1         | 1.85%   |
| 4266  | 1         | 1.85%   |
| 3733  | 1         | 1.85%   |
| 3266  | 1         | 1.85%   |
| 2400  | 1         | 1.85%   |
| 2048  | 1         | 1.85%   |
| 800   | 1         | 1.85%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| HP Ink Tank Wireless 410 series | 1         | 100%    |

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
| Chicony Electronics                    | 38        | 23.46%  |
| Realtek Semiconductor                  | 21        | 12.96%  |
| Microdia                               | 17        | 10.49%  |
| IMC Networks                           | 17        | 10.49%  |
| Acer                                   | 16        | 9.88%   |
| Quanta                                 | 9         | 5.56%   |
| Sunplus Innovation Technology          | 8         | 4.94%   |
| Apple                                  | 8         | 4.94%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 3.09%   |
| Syntek                                 | 4         | 2.47%   |
| Silicon Motion                         | 4         | 2.47%   |
| Suyin                                  | 3         | 1.85%   |
| Alcor Micro                            | 3         | 1.85%   |
| Samsung Electronics                    | 2         | 1.23%   |
| Luxvisions Innotech Limited            | 2         | 1.23%   |
| Z-Star Microelectronics                | 1         | 0.62%   |
| SunplusIT                              | 1         | 0.62%   |
| Sonix Technology                       | 1         | 0.62%   |
| Microsoft                              | 1         | 0.62%   |
| Logitech                               | 1         | 0.62%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                        | 13        | 7.98%   |
| Microdia Integrated_Webcam_HD                       | 10        | 6.13%   |
| Chicony Integrated Camera                           | 7         | 4.29%   |
| IMC Networks Integrated Camera                      | 6         | 3.68%   |
| Chicony HD Webcam                                   | 6         | 3.68%   |
| Acer BisonCam,NB Pro                                | 6         | 3.68%   |
| Syntek Integrated Camera                            | 4         | 2.45%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 2.45%   |
| Quanta HD User Facing                               | 3         | 1.84%   |
| Chicony USB2.0 VGA UVC WebCam                       | 3         | 1.84%   |
| Chicony TOSHIBA Web Camera - HD                     | 3         | 1.84%   |
| Apple iPhone 5/5C/5S/6/SE                           | 3         | 1.84%   |
| Apple Built-in iSight                               | 3         | 1.84%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 1.23%   |
| Sunplus 1.3M HD WebCam                              | 2         | 1.23%   |
| Silicon Motion Web Camera                           | 2         | 1.23%   |
| Samsung Galaxy A5 (MTP)                             | 2         | 1.23%   |
| Realtek Integrated Webcam HD                        | 2         | 1.23%   |
| Quanta HP HD Camera                                 | 2         | 1.23%   |
| Microdia Integrated Webcam HD                       | 2         | 1.23%   |
| Chicony HP Wide Vision HD Camera                    | 2         | 1.23%   |
| Chicony HP TrueVision HD Camera                     | 2         | 1.23%   |
| Chicony HP HD Camera                                | 2         | 1.23%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 2         | 1.23%   |
| Acer SunplusIT Integrated Camera                    | 2         | 1.23%   |
| Acer Integrated Camera                              | 2         | 1.23%   |
| Acer EasyCamera                                     | 2         | 1.23%   |
| Z-Star Sirius USB2.0 Camera                         | 1         | 0.61%   |
| Suyin HP Truevision HD                              | 1         | 0.61%   |
| Suyin HD WebCam                                     | 1         | 0.61%   |
| Suyin 1.3M HD WebCam                                | 1         | 0.61%   |
| SunplusIT USB 2.0 Camera                            | 1         | 0.61%   |
| Sunplus Laptop Integrated Webcam FHD                | 1         | 0.61%   |
| Sunplus Integrated Webcam                           | 1         | 0.61%   |
| Sunplus HD WebCam                                   | 1         | 0.61%   |
| Sunplus ASUS Webcam                                 | 1         | 0.61%   |
| Sonix USB2.0 HD UVC WebCam                          | 1         | 0.61%   |
| Silicon Motion WebCam SCB-0385N                     | 1         | 0.61%   |
| Silicon Motion 300k Pixel Camera                    | 1         | 0.61%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 0.61%   |
| Realtek USB Camera                                  | 1         | 0.61%   |
| Realtek Lenovo EasyCamera                           | 1         | 0.61%   |
| Realtek Laptop Camera                               | 1         | 0.61%   |
| Realtek HP "Truevision HD" laptop camera            | 1         | 0.61%   |
| Realtek EasyCamera                                  | 1         | 0.61%   |
| Quanta VGA WebCam                                   | 1         | 0.61%   |
| Quanta HP Wide Vision HD Camera                     | 1         | 0.61%   |
| Quanta HD Webcam                                    | 1         | 0.61%   |
| Quanta HD Camera                                    | 1         | 0.61%   |
| Microsoft LifeCam VX-2000                           | 1         | 0.61%   |
| Microdia Lenovo EasyCamera                          | 1         | 0.61%   |
| Microdia JOYACCESS JA-Webcam                        | 1         | 0.61%   |
| Microdia Integrated_Webcam_1.3M                     | 1         | 0.61%   |
| Microdia Integrated Webcam                          | 1         | 0.61%   |
| Microdia Dell Laptop Integrated Webcam HD           | 1         | 0.61%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 0.61%   |
| Luxvisions Innotech Limited HP HD Camera            | 1         | 0.61%   |
| Logitech C922 Pro Stream Webcam                     | 1         | 0.61%   |
| IMC Networks VGA UVC WebCam                         | 1         | 0.61%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 15        | 46.88%  |
| Shenzhen Goodix Technology | 8         | 25%     |
| Validity Sensors           | 4         | 12.5%   |
| Upek                       | 2         | 6.25%   |
| AuthenTec                  | 2         | 6.25%   |
| Elan Microelectronics      | 1         | 3.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 6         | 18.75%  |
| Shenzhen Goodix FingerPrint                               | 4         | 12.5%   |
| Unknown                                                   | 4         | 12.5%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 2         | 6.25%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 6.25%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 2         | 6.25%   |
| Shenzhen Goodix  Fingerprint Device                       | 2         | 6.25%   |
| Shenzhen Goodix Fingerprint Reader                        | 2         | 6.25%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor         | 1         | 3.13%   |
| Validity Sensors VFS491                                   | 1         | 3.13%   |
| Validity Sensors VFS 5011 fingerprint sensor              | 1         | 3.13%   |
| Validity Sensors Swipe Fingerprint Sensor                 | 1         | 3.13%   |
| Synaptics WBDI Device                                     | 1         | 3.13%   |
| Elan ELAN:ARM-M4                                          | 1         | 3.13%   |
| AuthenTec AES2810                                         | 1         | 3.13%   |
| AuthenTec AES2550 Fingerprint Sensor                      | 1         | 3.13%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 4         | 40%     |
| O2 Micro    | 2         | 20%     |
| Broadcom    | 2         | 20%     |
| Upek        | 1         | 10%     |
| Lenovo      | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 4         | 40%     |
| O2 Micro OZ776 CCID Smartcard Reader                       | 2         | 20%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 10%     |
| Lenovo Integrated Smart Card Reader                        | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 10%     |
| Broadcom 5880                                              | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 101       | 55.19%  |
| 1     | 62        | 33.88%  |
| 2     | 15        | 8.2%    |
| 3     | 4         | 2.19%   |
| 4     | 1         | 0.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 30        | 29.41%  |
| Bluetooth                | 18        | 17.65%  |
| Multimedia controller    | 17        | 16.67%  |
| Net/wireless             | 11        | 10.78%  |
| Graphics card            | 9         | 8.82%   |
| Chipcard                 | 9         | 8.82%   |
| Storage/ide              | 2         | 1.96%   |
| Sound                    | 1         | 0.98%   |
| Network                  | 1         | 0.98%   |
| Net/ethernet             | 1         | 0.98%   |
| Modem                    | 1         | 0.98%   |
| Communication controller | 1         | 0.98%   |
| Card reader              | 1         | 0.98%   |


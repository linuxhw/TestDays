Linux in Australia - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Australia.

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

Total: 2627

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T580 20LAS3NJ0T    | [17e848cdcf](https://linux-hardware.org/?probe=17e848cdcf) | Feb 02, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [6d6e6af46b](https://linux-hardware.org/?probe=6d6e6af46b) | Feb 02, 2024 |
| COM1          | E15-5A165-BM (9)            | [41d123782c](https://linux-hardware.org/?probe=41d123782c) | Feb 01, 2024 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [f659cc07fc](https://linux-hardware.org/?probe=f659cc07fc) | Feb 01, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [653f9c5fa5](https://linux-hardware.org/?probe=653f9c5fa5) | Feb 01, 2024 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [aaec148c06](https://linux-hardware.org/?probe=aaec148c06) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [7adc6ac4b3](https://linux-hardware.org/?probe=7adc6ac4b3) | Feb 01, 2024 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [4e6e527f34](https://linux-hardware.org/?probe=4e6e527f34) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [16a348ccd1](https://linux-hardware.org/?probe=16a348ccd1) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [fc52040fc1](https://linux-hardware.org/?probe=fc52040fc1) | Feb 01, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [f833c48d57](https://linux-hardware.org/?probe=f833c48d57) | Feb 01, 2024 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [bc7890c0fe](https://linux-hardware.org/?probe=bc7890c0fe) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [ef62bb8257](https://linux-hardware.org/?probe=ef62bb8257) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [841cef0b98](https://linux-hardware.org/?probe=841cef0b98) | Feb 01, 2024 |
| Acer          | Aspire A315-59              | [7d06efe302](https://linux-hardware.org/?probe=7d06efe302) | Jan 31, 2024 |
| HP            | ProBook 430 G8 Notebook ... | [ccf29ffd3d](https://linux-hardware.org/?probe=ccf29ffd3d) | Jan 31, 2024 |
| HP            | EliteBook Folio 9480m       | [648e9e296d](https://linux-hardware.org/?probe=648e9e296d) | Jan 30, 2024 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | [f46d220d2e](https://linux-hardware.org/?probe=f46d220d2e) | Jan 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2f6021e243](https://linux-hardware.org/?probe=2f6021e243) | Jan 28, 2024 |
| Lenovo        | ThinkPad T410 2522PT3       | [5116ee6ad3](https://linux-hardware.org/?probe=5116ee6ad3) | Jan 28, 2024 |
| Dell          | Latitude 5500               | [870e89a969](https://linux-hardware.org/?probe=870e89a969) | Jan 26, 2024 |
| ASUSTek       | X507UA                      | [ebf2dc120a](https://linux-hardware.org/?probe=ebf2dc120a) | Jan 24, 2024 |
| Dell          | Latitude 7410               | [cbb6638a4d](https://linux-hardware.org/?probe=cbb6638a4d) | Jan 24, 2024 |
| HP            | Compaq CQ45                 | [4ab36cf29f](https://linux-hardware.org/?probe=4ab36cf29f) | Jan 23, 2024 |
| Apple         | MacBookPro10,2              | [db7e0a0c8a](https://linux-hardware.org/?probe=db7e0a0c8a) | Jan 22, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [52783252de](https://linux-hardware.org/?probe=52783252de) | Jan 21, 2024 |
| Panasonic     | FZG1-4                      | [78a30df588](https://linux-hardware.org/?probe=78a30df588) | Jan 21, 2024 |
| Lenovo        | ThinkPad T480 20L6S3C100    | [ef29c6e451](https://linux-hardware.org/?probe=ef29c6e451) | Jan 20, 2024 |
| Apple         | MacBookPro12,1              | [624cf621cc](https://linux-hardware.org/?probe=624cf621cc) | Jan 18, 2024 |
| Dell          | Latitude 5500               | [eb9de73fa4](https://linux-hardware.org/?probe=eb9de73fa4) | Jan 18, 2024 |
| Dell          | Inspiron MM061              | [6415c1e543](https://linux-hardware.org/?probe=6415c1e543) | Jan 18, 2024 |
| Alienware     | 14                          | [a0109babcd](https://linux-hardware.org/?probe=a0109babcd) | Jan 18, 2024 |
| Sony          | VPCEB46FG                   | [0e2c2caced](https://linux-hardware.org/?probe=0e2c2caced) | Jan 17, 2024 |
| Dell          | Inspiron N311z              | [e4163cacc4](https://linux-hardware.org/?probe=e4163cacc4) | Jan 16, 2024 |
| Dell          | Inspiron 7570               | [bdea5ae4df](https://linux-hardware.org/?probe=bdea5ae4df) | Jan 16, 2024 |
| ASUSTek       | X580VD                      | [bf7addfd46](https://linux-hardware.org/?probe=bf7addfd46) | Jan 15, 2024 |
| HP            | Laptop 15s-du0xxx           | [530c5882b9](https://linux-hardware.org/?probe=530c5882b9) | Jan 15, 2024 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [a4234528de](https://linux-hardware.org/?probe=a4234528de) | Jan 14, 2024 |
| MSI           | GP62M 7REX                  | [23c4fd0913](https://linux-hardware.org/?probe=23c4fd0913) | Jan 14, 2024 |
| Lenovo        | Yoga Pro 7 14IRH8 82Y7      | [55b05d17b6](https://linux-hardware.org/?probe=55b05d17b6) | Jan 14, 2024 |
| HP            | Laptop 15s-du0xxx           | [75a6760096](https://linux-hardware.org/?probe=75a6760096) | Jan 12, 2024 |
| Apple         | MacBookAir7,2               | [64df689564](https://linux-hardware.org/?probe=64df689564) | Jan 11, 2024 |
| MSI           | Bravo 15 C7VEK              | [d759cfb72e](https://linux-hardware.org/?probe=d759cfb72e) | Jan 11, 2024 |
| Lenovo        | ThinkPad T480 20L6S3C100    | [c54acdce25](https://linux-hardware.org/?probe=c54acdce25) | Jan 10, 2024 |
| Acer          | TM8573T                     | [69f3a0a145](https://linux-hardware.org/?probe=69f3a0a145) | Jan 09, 2024 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | [b0ac8e8208](https://linux-hardware.org/?probe=b0ac8e8208) | Jan 09, 2024 |
| Dell          | XPS 13 9370                 | [0d909c4177](https://linux-hardware.org/?probe=0d909c4177) | Jan 08, 2024 |
| Dell          | Precision 5680              | [047734c28f](https://linux-hardware.org/?probe=047734c28f) | Jan 08, 2024 |
| Dell          | Precision 5570              | [acc6213478](https://linux-hardware.org/?probe=acc6213478) | Jan 08, 2024 |
| Dell          | Precision 5680              | [0d58e93f98](https://linux-hardware.org/?probe=0d58e93f98) | Jan 06, 2024 |
| Valve         | Jupiter                     | [3d47c0ba48](https://linux-hardware.org/?probe=3d47c0ba48) | Jan 04, 2024 |
| ASUSTek       | X705UDR                     | [02cec34b2e](https://linux-hardware.org/?probe=02cec34b2e) | Jan 04, 2024 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [a83656b1fd](https://linux-hardware.org/?probe=a83656b1fd) | Jan 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [71d03730b7](https://linux-hardware.org/?probe=71d03730b7) | Jan 03, 2024 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | [d29c58fd8a](https://linux-hardware.org/?probe=d29c58fd8a) | Jan 03, 2024 |
| Dell          | Inspiron MM061              | [34d48e27b3](https://linux-hardware.org/?probe=34d48e27b3) | Jan 03, 2024 |
| Lenovo        | ThinkBook 15-IML 20RW       | [9712812ff0](https://linux-hardware.org/?probe=9712812ff0) | Jan 03, 2024 |
| Dell          | XPS 13 9360                 | [f115f9696c](https://linux-hardware.org/?probe=f115f9696c) | Jan 02, 2024 |
| Lenovo        | ThinkPad T410 2522PT3       | [db100cd948](https://linux-hardware.org/?probe=db100cd948) | Jan 02, 2024 |
| System76      | Oryx Pro                    | [07e4e6a0a8](https://linux-hardware.org/?probe=07e4e6a0a8) | Jan 02, 2024 |
| Valve         | Jupiter                     | [b16497fbfc](https://linux-hardware.org/?probe=b16497fbfc) | Jan 01, 2024 |
| Apple         | MacBookPro10,2              | [386449d6f7](https://linux-hardware.org/?probe=386449d6f7) | Dec 31, 2023 |
| Lenovo        | ThinkPad P43s 20RHCTO1WW    | [7b1fe348e4](https://linux-hardware.org/?probe=7b1fe348e4) | Dec 31, 2023 |
| Acer          | Nitro AN16-41               | [7130d1a699](https://linux-hardware.org/?probe=7130d1a699) | Dec 31, 2023 |
| Acer          | Nitro AN16-41               | [d04c4d749f](https://linux-hardware.org/?probe=d04c4d749f) | Dec 31, 2023 |
| Metabox       | Alpha-X NH58HP              | [983844e1c8](https://linux-hardware.org/?probe=983844e1c8) | Dec 30, 2023 |
| Lenovo        | ThinkPad T480s 20L7S0060... | [485c94e992](https://linux-hardware.org/?probe=485c94e992) | Dec 29, 2023 |
| Lenovo        | ThinkBook 15-IML 20RW       | [5ef2e29839](https://linux-hardware.org/?probe=5ef2e29839) | Dec 27, 2023 |
| Apple         | MacBookAir9,1               | [22b65c12f2](https://linux-hardware.org/?probe=22b65c12f2) | Dec 26, 2023 |
| Lenovo        | ThinkPad T460 20FMS0W32L    | [55200b6aa5](https://linux-hardware.org/?probe=55200b6aa5) | Dec 26, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [3fd8513ee7](https://linux-hardware.org/?probe=3fd8513ee7) | Dec 26, 2023 |
| Apple         | MacBookAir7,2               | [2a8ca288fb](https://linux-hardware.org/?probe=2a8ca288fb) | Dec 25, 2023 |
| Panasonic     | FZG1-4                      | [f6c98a5b67](https://linux-hardware.org/?probe=f6c98a5b67) | Dec 24, 2023 |
| HP            | ENVY 15                     | [2997ffe5cf](https://linux-hardware.org/?probe=2997ffe5cf) | Dec 22, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [fa4275395f](https://linux-hardware.org/?probe=fa4275395f) | Dec 22, 2023 |
| Dell          | Precision 5680              | [b8b5bc0292](https://linux-hardware.org/?probe=b8b5bc0292) | Dec 20, 2023 |
| ASUSTek       | X553MA                      | [bc7fc2be74](https://linux-hardware.org/?probe=bc7fc2be74) | Dec 20, 2023 |
| ASUSTek       | X553MA                      | [11f3b9c9d6](https://linux-hardware.org/?probe=11f3b9c9d6) | Dec 20, 2023 |
| Dell          | XPS 15 9560                 | [1bd33b2c6b](https://linux-hardware.org/?probe=1bd33b2c6b) | Dec 18, 2023 |
| Apple         | MacBookPro12,1              | [6db91b5eb2](https://linux-hardware.org/?probe=6db91b5eb2) | Dec 18, 2023 |
| ASUSTek       | X580VD                      | [8629995933](https://linux-hardware.org/?probe=8629995933) | Dec 17, 2023 |
| Toshiba       | PORTEGE Z20t-C              | [eb941689a4](https://linux-hardware.org/?probe=eb941689a4) | Dec 17, 2023 |
| Apple         | MacBookPro10,1              | [adc736fc8d](https://linux-hardware.org/?probe=adc736fc8d) | Dec 16, 2023 |
| Lenovo        | ThinkPad Mini10 3507A31     | [b5b534e106](https://linux-hardware.org/?probe=b5b534e106) | Dec 14, 2023 |
| HP            | Laptop 15-fc0xxx            | [e49be74129](https://linux-hardware.org/?probe=e49be74129) | Dec 13, 2023 |
| Acer          | Aspire R3-131T              | [5fc8de17bb](https://linux-hardware.org/?probe=5fc8de17bb) | Dec 13, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | [625439b5a5](https://linux-hardware.org/?probe=625439b5a5) | Dec 13, 2023 |
| Lenovo        | G50-70 20351                | [d22fb3a791](https://linux-hardware.org/?probe=d22fb3a791) | Dec 11, 2023 |
| Valve         | Jupiter                     | [b78720dbf3](https://linux-hardware.org/?probe=b78720dbf3) | Dec 11, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [2aef9deafb](https://linux-hardware.org/?probe=2aef9deafb) | Dec 10, 2023 |
| HP            | ProBook 6460b               | [99fa9c84ca](https://linux-hardware.org/?probe=99fa9c84ca) | Dec 10, 2023 |
| Dell          | Inspiron 1525               | [0ee42c0440](https://linux-hardware.org/?probe=0ee42c0440) | Dec 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [afc78e9ba2](https://linux-hardware.org/?probe=afc78e9ba2) | Dec 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [a6b0055398](https://linux-hardware.org/?probe=a6b0055398) | Dec 08, 2023 |
| Lenovo        | ThinkPad Mini10 3507A31     | [1229fd52f5](https://linux-hardware.org/?probe=1229fd52f5) | Dec 08, 2023 |
| Acer          | Extensa 4210                | [4f8a82394a](https://linux-hardware.org/?probe=4f8a82394a) | Dec 07, 2023 |
| HP            | 250 G7 Notebook PC          | [bed4fa69c4](https://linux-hardware.org/?probe=bed4fa69c4) | Dec 06, 2023 |
| HP            | 250 G7 Notebook PC          | [52cdd2c7b2](https://linux-hardware.org/?probe=52cdd2c7b2) | Dec 06, 2023 |
| Dell          | Latitude E6410              | [65b6e47cf8](https://linux-hardware.org/?probe=65b6e47cf8) | Dec 04, 2023 |
| Dell          | Latitude 5520               | [5b61695af2](https://linux-hardware.org/?probe=5b61695af2) | Dec 01, 2023 |
| Lenovo        | Z50-70 20354                | [44ad415f8f](https://linux-hardware.org/?probe=44ad415f8f) | Dec 01, 2023 |
| ASUSTek       | TUF Gaming FX705DU_FX705... | [c781f63b2a](https://linux-hardware.org/?probe=c781f63b2a) | Nov 30, 2023 |
| HP            | Laptop 15s-du0xxx           | [bf583ba008](https://linux-hardware.org/?probe=bf583ba008) | Nov 29, 2023 |
| Acer          | Nitro AN515-56              | [b2dd77b768](https://linux-hardware.org/?probe=b2dd77b768) | Nov 28, 2023 |
| MSI           | GF63 Thin 10SCXR            | [20e52e5c9b](https://linux-hardware.org/?probe=20e52e5c9b) | Nov 28, 2023 |
| MSI           | GF63 Thin 10SCXR            | [09dfe90de1](https://linux-hardware.org/?probe=09dfe90de1) | Nov 28, 2023 |
| Toshiba       | PORTEGE X30-E               | [9b85473f0f](https://linux-hardware.org/?probe=9b85473f0f) | Nov 28, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [aadba04a83](https://linux-hardware.org/?probe=aadba04a83) | Nov 27, 2023 |
| Dell          | Latitude 7490               | [4d59532412](https://linux-hardware.org/?probe=4d59532412) | Nov 27, 2023 |
| HP            | 245 G6 Notebook PC          | [1256303ece](https://linux-hardware.org/?probe=1256303ece) | Nov 26, 2023 |
| HP            | 245 G6 Notebook PC          | [0b00139036](https://linux-hardware.org/?probe=0b00139036) | Nov 26, 2023 |
| HP            | Pavilion dv6                | [e09777761c](https://linux-hardware.org/?probe=e09777761c) | Nov 26, 2023 |
| Dell          | Vostro 3401                 | [3496a45338](https://linux-hardware.org/?probe=3496a45338) | Nov 25, 2023 |
| Matsushita... | CF-30FCDALAM                | [94d60b91d5](https://linux-hardware.org/?probe=94d60b91d5) | Nov 25, 2023 |
| HP            | Laptop 15s-du0xxx           | [7e541895b2](https://linux-hardware.org/?probe=7e541895b2) | Nov 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [145e6fbb42](https://linux-hardware.org/?probe=145e6fbb42) | Nov 24, 2023 |
| Valve         | Jupiter                     | [a4f7cad00f](https://linux-hardware.org/?probe=a4f7cad00f) | Nov 22, 2023 |
| Valve         | Jupiter                     | [bdb118e120](https://linux-hardware.org/?probe=bdb118e120) | Nov 22, 2023 |
| Acer          | Aspire AV15-51              | [6ca712a0bb](https://linux-hardware.org/?probe=6ca712a0bb) | Nov 22, 2023 |
| Acer          | Aspire AV15-51              | [09108a2bc4](https://linux-hardware.org/?probe=09108a2bc4) | Nov 22, 2023 |
| Acer          | Nitro AN515-56              | [9eb5267c48](https://linux-hardware.org/?probe=9eb5267c48) | Nov 22, 2023 |
| HP            | ProBook 430 G2              | [e0a3622122](https://linux-hardware.org/?probe=e0a3622122) | Nov 20, 2023 |
| Dell          | XPS 15 9560                 | [be841a1ee6](https://linux-hardware.org/?probe=be841a1ee6) | Nov 19, 2023 |
| Acer          | Nitro AN515-56              | [507f6c2a0d](https://linux-hardware.org/?probe=507f6c2a0d) | Nov 19, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [8ebb2df251](https://linux-hardware.org/?probe=8ebb2df251) | Nov 18, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | [80f392bd0d](https://linux-hardware.org/?probe=80f392bd0d) | Nov 18, 2023 |
| Dell          | Inspiron M5010              | [77b9c09532](https://linux-hardware.org/?probe=77b9c09532) | Nov 18, 2023 |
| Toshiba       | PORTEGE Z20t-B              | [052540adc3](https://linux-hardware.org/?probe=052540adc3) | Nov 18, 2023 |
| Acer          | Nitro AN515-56              | [dc208dca03](https://linux-hardware.org/?probe=dc208dca03) | Nov 18, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [fb9543ab29](https://linux-hardware.org/?probe=fb9543ab29) | Nov 17, 2023 |
| Lenovo        | ThinkPad T590 20N4S02F00    | [f61bc8d881](https://linux-hardware.org/?probe=f61bc8d881) | Nov 17, 2023 |
| Lenovo        | ThinkPad T590 20N4S02F00    | [53dd735333](https://linux-hardware.org/?probe=53dd735333) | Nov 17, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [029e25867a](https://linux-hardware.org/?probe=029e25867a) | Nov 17, 2023 |
| Lenovo        | ThinkPad E550 20DF001HAU    | [44968b500c](https://linux-hardware.org/?probe=44968b500c) | Nov 16, 2023 |
| HP            | Laptop 15s-eq2xxx           | [3f4cd8d065](https://linux-hardware.org/?probe=3f4cd8d065) | Nov 14, 2023 |
| Acer          | Nitro AN515-56              | [3ad9fc243a](https://linux-hardware.org/?probe=3ad9fc243a) | Nov 14, 2023 |
| MSI           | Katana GF66 12UC            | [bd156c9515](https://linux-hardware.org/?probe=bd156c9515) | Nov 13, 2023 |
| ASUSTek       | X580VD                      | [d0809a2221](https://linux-hardware.org/?probe=d0809a2221) | Nov 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [47d681f4e6](https://linux-hardware.org/?probe=47d681f4e6) | Nov 13, 2023 |
| COM1          | NBINF-X5-9G5                | [4e24a48715](https://linux-hardware.org/?probe=4e24a48715) | Nov 13, 2023 |
| Dell          | Inspiron 1525               | [d9b24edac8](https://linux-hardware.org/?probe=d9b24edac8) | Nov 11, 2023 |
| HP            | Pavilion g6                 | [1215d8475b](https://linux-hardware.org/?probe=1215d8475b) | Nov 11, 2023 |
| Dell          | Inspiron 1525               | [ab3577cc31](https://linux-hardware.org/?probe=ab3577cc31) | Nov 09, 2023 |
| Dell          | Precision 5520              | [1166f1d95d](https://linux-hardware.org/?probe=1166f1d95d) | Nov 08, 2023 |
| Apple         | MacBookPro13,1              | [e5ae7e8a94](https://linux-hardware.org/?probe=e5ae7e8a94) | Nov 07, 2023 |
| Dell          | G7 7700                     | [0fc7811fdd](https://linux-hardware.org/?probe=0fc7811fdd) | Nov 07, 2023 |
| Acer          | TM8573T                     | [d78cdb2bdc](https://linux-hardware.org/?probe=d78cdb2bdc) | Nov 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [94fdbbd7bd](https://linux-hardware.org/?probe=94fdbbd7bd) | Nov 06, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [231b5b8ef8](https://linux-hardware.org/?probe=231b5b8ef8) | Nov 06, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [b88b3757af](https://linux-hardware.org/?probe=b88b3757af) | Nov 06, 2023 |
| Lenovo        | ThinkPad T480 20L6S5VP3U    | [ea70f0e597](https://linux-hardware.org/?probe=ea70f0e597) | Nov 05, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [f1d00fbb93](https://linux-hardware.org/?probe=f1d00fbb93) | Nov 05, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [50306c96e2](https://linux-hardware.org/?probe=50306c96e2) | Nov 05, 2023 |
| Sony          | SVE15137CGW                 | [5d2a4746af](https://linux-hardware.org/?probe=5d2a4746af) | Nov 04, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D3S... | [6a2591b5e9](https://linux-hardware.org/?probe=6a2591b5e9) | Nov 03, 2023 |
| HP            | ZBook Power G7 Mobile Wo... | [044aa1f9b5](https://linux-hardware.org/?probe=044aa1f9b5) | Nov 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [75a224b797](https://linux-hardware.org/?probe=75a224b797) | Nov 02, 2023 |
| Valve         | Jupiter                     | [b5bd58d350](https://linux-hardware.org/?probe=b5bd58d350) | Oct 31, 2023 |
| MSI           | Creator 15 A11UE            | [e8b0c2a2b5](https://linux-hardware.org/?probe=e8b0c2a2b5) | Oct 31, 2023 |
| HP            | EliteBook 820 G3            | [e131dccf11](https://linux-hardware.org/?probe=e131dccf11) | Oct 31, 2023 |
| Lenovo        | ThinkPad T490 20N2S0QE00    | [9785ae64c0](https://linux-hardware.org/?probe=9785ae64c0) | Oct 31, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D3S... | [8730c3de9d](https://linux-hardware.org/?probe=8730c3de9d) | Oct 30, 2023 |
| Valve         | Jupiter                     | [e73e0881d6](https://linux-hardware.org/?probe=e73e0881d6) | Oct 30, 2023 |
| Dell          | Latitude 5530               | [1731342e23](https://linux-hardware.org/?probe=1731342e23) | Oct 30, 2023 |
| Dell          | XPS 15 9510                 | [ab707308db](https://linux-hardware.org/?probe=ab707308db) | Oct 30, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [649b911963](https://linux-hardware.org/?probe=649b911963) | Oct 29, 2023 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [bc2ed6322b](https://linux-hardware.org/?probe=bc2ed6322b) | Oct 29, 2023 |
| Google        | Taniks                      | [c864f19e03](https://linux-hardware.org/?probe=c864f19e03) | Oct 28, 2023 |
| Apple         | MacBookAir6,2               | [96b76fc377](https://linux-hardware.org/?probe=96b76fc377) | Oct 28, 2023 |
| Dell          | Latitude 5430               | [af33081c9b](https://linux-hardware.org/?probe=af33081c9b) | Oct 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [3bc6d6cfda](https://linux-hardware.org/?probe=3bc6d6cfda) | Oct 27, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [755d25d933](https://linux-hardware.org/?probe=755d25d933) | Oct 26, 2023 |
| HP            | EliteBook Folio 9470m       | [765f6f8003](https://linux-hardware.org/?probe=765f6f8003) | Oct 25, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [d69762902a](https://linux-hardware.org/?probe=d69762902a) | Oct 25, 2023 |
| Lenovo        | V110-15IAP 80TG             | [455780b267](https://linux-hardware.org/?probe=455780b267) | Oct 25, 2023 |
| Acer          | Aspire V3-572               | [f873d7efd9](https://linux-hardware.org/?probe=f873d7efd9) | Oct 24, 2023 |
| ASUSTek       | X541UJ                      | [833d4435d4](https://linux-hardware.org/?probe=833d4435d4) | Oct 24, 2023 |
| MSI           | GP62M 7REX                  | [5fbee8e341](https://linux-hardware.org/?probe=5fbee8e341) | Oct 24, 2023 |
| MSI           | GP62M 7REX                  | [a95ab8b563](https://linux-hardware.org/?probe=a95ab8b563) | Oct 24, 2023 |
| Apple         | MacBookAir6,2               | [f15ecd1759](https://linux-hardware.org/?probe=f15ecd1759) | Oct 24, 2023 |
| Acer          | Aspire V3-572               | [974d64f7a8](https://linux-hardware.org/?probe=974d64f7a8) | Oct 23, 2023 |
| Dell          | Latitude 5430               | [8d552380c4](https://linux-hardware.org/?probe=8d552380c4) | Oct 23, 2023 |
| Apple         | MacBookPro9,2               | [dac0aa7f70](https://linux-hardware.org/?probe=dac0aa7f70) | Oct 22, 2023 |
| Acer          | Nitro AN515-45              | [310d794691](https://linux-hardware.org/?probe=310d794691) | Oct 22, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [92d3be3fff](https://linux-hardware.org/?probe=92d3be3fff) | Oct 22, 2023 |
| HP            | ProBook 4340s               | [8746af78f7](https://linux-hardware.org/?probe=8746af78f7) | Oct 22, 2023 |
| HP            | Pavilion g6                 | [2fc9736b9e](https://linux-hardware.org/?probe=2fc9736b9e) | Oct 22, 2023 |
| HP            | Pavilion g6                 | [7514db3c84](https://linux-hardware.org/?probe=7514db3c84) | Oct 22, 2023 |
| HP            | EliteBook Folio 9470m       | [f342373f65](https://linux-hardware.org/?probe=f342373f65) | Oct 20, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [09ad44bf2e](https://linux-hardware.org/?probe=09ad44bf2e) | Oct 19, 2023 |
| Dell          | XPS 13 9360                 | [dbbedd9f06](https://linux-hardware.org/?probe=dbbedd9f06) | Oct 18, 2023 |
| Apple         | MacBookPro11,1              | [ffeb95bd95](https://linux-hardware.org/?probe=ffeb95bd95) | Oct 17, 2023 |
| Lenovo        | ThinkPad E460 20ETA05KAU    | [cf477f62d0](https://linux-hardware.org/?probe=cf477f62d0) | Oct 15, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [feaf25f8e8](https://linux-hardware.org/?probe=feaf25f8e8) | Oct 15, 2023 |
| Acer          | Aspire E1-531               | [4e585c2b99](https://linux-hardware.org/?probe=4e585c2b99) | Oct 15, 2023 |
| HUAWEI        | KLVD-WXX9                   | [9d77b16e0b](https://linux-hardware.org/?probe=9d77b16e0b) | Oct 14, 2023 |
| HP            | Laptop 15s-du4xxx           | [8bec0ea3db](https://linux-hardware.org/?probe=8bec0ea3db) | Oct 14, 2023 |
| Fujitsu       | LIFEBOOK T5010              | [f35263745a](https://linux-hardware.org/?probe=f35263745a) | Oct 14, 2023 |
| HP            | Notebook                    | [221bc048b5](https://linux-hardware.org/?probe=221bc048b5) | Oct 13, 2023 |
| Apple         | MacBookPro11,4              | [107524e9ec](https://linux-hardware.org/?probe=107524e9ec) | Oct 12, 2023 |
| Apple         | MacBookPro11,4              | [f9fee05f72](https://linux-hardware.org/?probe=f9fee05f72) | Oct 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [e6c5f903ce](https://linux-hardware.org/?probe=e6c5f903ce) | Oct 12, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | [3d389cfbfa](https://linux-hardware.org/?probe=3d389cfbfa) | Oct 11, 2023 |
| ASUSTek       | K42F                        | [0d099eb4f7](https://linux-hardware.org/?probe=0d099eb4f7) | Oct 10, 2023 |
| Acer          | Aspire A114-33              | [53a1dce896](https://linux-hardware.org/?probe=53a1dce896) | Oct 09, 2023 |
| HP            | EliteBook Folio 9470m       | [9cecfe7ba5](https://linux-hardware.org/?probe=9cecfe7ba5) | Oct 09, 2023 |
| Acer          | Nitro AN515-56              | [6a98464415](https://linux-hardware.org/?probe=6a98464415) | Oct 07, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [d8d241531e](https://linux-hardware.org/?probe=d8d241531e) | Oct 07, 2023 |
| HP            | EliteBook 8460p             | [9b6cb6738d](https://linux-hardware.org/?probe=9b6cb6738d) | Oct 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [226b534a32](https://linux-hardware.org/?probe=226b534a32) | Oct 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [dfec5c18d5](https://linux-hardware.org/?probe=dfec5c18d5) | Oct 04, 2023 |
| MSI           | PR600                       | [09fe9eb818](https://linux-hardware.org/?probe=09fe9eb818) | Oct 04, 2023 |
| Dell          | Latitude E7440              | [3cb4fc2857](https://linux-hardware.org/?probe=3cb4fc2857) | Oct 03, 2023 |
| Apple         | MacBookAir7,2               | [efcc70945c](https://linux-hardware.org/?probe=efcc70945c) | Oct 03, 2023 |
| Apple         | MacBookPro16,2              | [66ee93331d](https://linux-hardware.org/?probe=66ee93331d) | Oct 02, 2023 |
| Apple         | MacBook8,1                  | [a7374560fe](https://linux-hardware.org/?probe=a7374560fe) | Oct 02, 2023 |
| Apple         | MacBookPro8,1               | [5488654867](https://linux-hardware.org/?probe=5488654867) | Oct 02, 2023 |
| Apple         | MacBook8,1                  | [2f046de8e8](https://linux-hardware.org/?probe=2f046de8e8) | Oct 02, 2023 |
| Apple         | MacBookPro14,3              | [e26d66c131](https://linux-hardware.org/?probe=e26d66c131) | Oct 01, 2023 |
| Apple         | MacBookPro14,3              | [21f405ccbe](https://linux-hardware.org/?probe=21f405ccbe) | Oct 01, 2023 |
| Toshiba       | Satellite P750              | [6edbfaa1b1](https://linux-hardware.org/?probe=6edbfaa1b1) | Oct 01, 2023 |
| Apple         | MacBookPro14,3              | [ec90ed2076](https://linux-hardware.org/?probe=ec90ed2076) | Oct 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [c99f28b27d](https://linux-hardware.org/?probe=c99f28b27d) | Oct 01, 2023 |
| Metabox       | Prime-X X170KM              | [8ab33a8bd3](https://linux-hardware.org/?probe=8ab33a8bd3) | Sep 30, 2023 |
| Apple         | MacBookAir7,2               | [c25eeffab1](https://linux-hardware.org/?probe=c25eeffab1) | Sep 28, 2023 |
| ASUSTek       | X550CC                      | [001231c730](https://linux-hardware.org/?probe=001231c730) | Sep 28, 2023 |
| Apple         | MacBookAir6,2               | [b0c2b630a6](https://linux-hardware.org/?probe=b0c2b630a6) | Sep 28, 2023 |
| Apple         | MacBookPro15,2              | [1331a57778](https://linux-hardware.org/?probe=1331a57778) | Sep 27, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | [fed9f17a22](https://linux-hardware.org/?probe=fed9f17a22) | Sep 27, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | [0dd1b47aa0](https://linux-hardware.org/?probe=0dd1b47aa0) | Sep 27, 2023 |
| HP            | EliteBook Folio 9470m       | [78d31814cf](https://linux-hardware.org/?probe=78d31814cf) | Sep 26, 2023 |
| HP            | EliteBook Folio 9470m       | [0d7d5f0613](https://linux-hardware.org/?probe=0d7d5f0613) | Sep 26, 2023 |
| Apple         | MacBookAir5,2               | [55dec782e7](https://linux-hardware.org/?probe=55dec782e7) | Sep 25, 2023 |
| Acer          | Aspire E5-571               | [c834abf6b2](https://linux-hardware.org/?probe=c834abf6b2) | Sep 25, 2023 |
| Acer          | Aspire R3-131T              | [bf8f7a55ae](https://linux-hardware.org/?probe=bf8f7a55ae) | Sep 24, 2023 |
| Acer          | Aspire R3-131T              | [a426f4a94e](https://linux-hardware.org/?probe=a426f4a94e) | Sep 24, 2023 |
| Dell          | Inspiron 14 5420            | [ade3d11822](https://linux-hardware.org/?probe=ade3d11822) | Sep 24, 2023 |
| COM1          | NBINF-X5-9G5                | [919d36ddd8](https://linux-hardware.org/?probe=919d36ddd8) | Sep 24, 2023 |
| HP            | EliteBook Folio 9470m       | [086b0dc21a](https://linux-hardware.org/?probe=086b0dc21a) | Sep 23, 2023 |
| Panasonic     | FZG1-4                      | [bb4677655e](https://linux-hardware.org/?probe=bb4677655e) | Sep 23, 2023 |
| Apple         | MacBookPro14,1              | [8b1188ba33](https://linux-hardware.org/?probe=8b1188ba33) | Sep 22, 2023 |
| Dell          | Precision 5680              | [55deb46665](https://linux-hardware.org/?probe=55deb46665) | Sep 21, 2023 |
| HP            | Pavilion dv7                | [a879a0a88f](https://linux-hardware.org/?probe=a879a0a88f) | Sep 21, 2023 |
| Apple         | MacBookPro8,1               | [c5e9108ee7](https://linux-hardware.org/?probe=c5e9108ee7) | Sep 20, 2023 |
| Dell          | Precision 5560              | [456e9e2c78](https://linux-hardware.org/?probe=456e9e2c78) | Sep 20, 2023 |
| Dell          | Precision 5680              | [a75a75f080](https://linux-hardware.org/?probe=a75a75f080) | Sep 20, 2023 |
| HP            | EliteBook 8460p             | [7a6c8c1d0a](https://linux-hardware.org/?probe=7a6c8c1d0a) | Sep 20, 2023 |
| HP            | EliteBook 8460p             | [6f7974b0f0](https://linux-hardware.org/?probe=6f7974b0f0) | Sep 20, 2023 |
| HP            | EliteBook Folio 9470m       | [5e50efa2c4](https://linux-hardware.org/?probe=5e50efa2c4) | Sep 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [eeeb11e211](https://linux-hardware.org/?probe=eeeb11e211) | Sep 19, 2023 |
| Sony          | SVE15137CGW                 | [b454be55a2](https://linux-hardware.org/?probe=b454be55a2) | Sep 19, 2023 |
| Framework     | Laptop                      | [f379873c4b](https://linux-hardware.org/?probe=f379873c4b) | Sep 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [82e9cc2c9a](https://linux-hardware.org/?probe=82e9cc2c9a) | Sep 18, 2023 |
| HP            | EliteBook 745 G2            | [7e5ee5a990](https://linux-hardware.org/?probe=7e5ee5a990) | Sep 18, 2023 |
| Dell          | Latitude 7490               | [91a3ecf449](https://linux-hardware.org/?probe=91a3ecf449) | Sep 18, 2023 |
| Apple         | MacBookPro16,2              | [42bb973998](https://linux-hardware.org/?probe=42bb973998) | Sep 16, 2023 |
| Apple         | MacBookPro16,2              | [d5c797d43b](https://linux-hardware.org/?probe=d5c797d43b) | Sep 16, 2023 |
| Dell          | Inspiron M5010              | [c78ab23cc7](https://linux-hardware.org/?probe=c78ab23cc7) | Sep 16, 2023 |
| COM1          | NBINF-X5-9G5                | [aca0ed1105](https://linux-hardware.org/?probe=aca0ed1105) | Sep 15, 2023 |
| Dell          | XPS L322X                   | [77135f7967](https://linux-hardware.org/?probe=77135f7967) | Sep 11, 2023 |
| Dell          | Inspiron M5010              | [70147b0015](https://linux-hardware.org/?probe=70147b0015) | Sep 11, 2023 |
| Dell          | XPS L322X                   | [fdf4ba47e1](https://linux-hardware.org/?probe=fdf4ba47e1) | Sep 11, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [fac3b5ba62](https://linux-hardware.org/?probe=fac3b5ba62) | Sep 08, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | [da7303433d](https://linux-hardware.org/?probe=da7303433d) | Sep 07, 2023 |
| Valve         | Jupiter                     | [d4ca58e970](https://linux-hardware.org/?probe=d4ca58e970) | Sep 07, 2023 |
| Apple         | MacBookPro9,2               | [424ab4dc3d](https://linux-hardware.org/?probe=424ab4dc3d) | Sep 05, 2023 |
| Dell          | Latitude 7280               | [3cf6ec76b5](https://linux-hardware.org/?probe=3cf6ec76b5) | Sep 05, 2023 |
| HP            | EliteBook 840 G1            | [318d03cfad](https://linux-hardware.org/?probe=318d03cfad) | Sep 04, 2023 |
| Apple         | MacBookPro16,2              | [ae41ba8b62](https://linux-hardware.org/?probe=ae41ba8b62) | Sep 04, 2023 |
| Apple         | MacBookPro8,1               | [6cbaac077e](https://linux-hardware.org/?probe=6cbaac077e) | Sep 03, 2023 |
| Dell          | Latitude E6520              | [b53cd78958](https://linux-hardware.org/?probe=b53cd78958) | Sep 02, 2023 |
| Dell          | G15 5520                    | [796ae7cf79](https://linux-hardware.org/?probe=796ae7cf79) | Sep 02, 2023 |
| Apple         | MacBookAir6,2               | [da8d60051c](https://linux-hardware.org/?probe=da8d60051c) | Sep 02, 2023 |
| ASUSTek       | K53SD                       | [9a208331c5](https://linux-hardware.org/?probe=9a208331c5) | Sep 01, 2023 |
| Dell          | Latitude E7470              | [0580f1c293](https://linux-hardware.org/?probe=0580f1c293) | Sep 01, 2023 |
| HP            | EliteBook Folio 1040 G1     | [1c496aba4a](https://linux-hardware.org/?probe=1c496aba4a) | Sep 01, 2023 |
| Lenovo        | Legion Slim 7 16IRH8 82Y... | [ab14d9d9bb](https://linux-hardware.org/?probe=ab14d9d9bb) | Aug 31, 2023 |
| Dell          | Latitude 7340               | [d6d1df94f5](https://linux-hardware.org/?probe=d6d1df94f5) | Aug 31, 2023 |
| Apple         | MacBookPro8,1               | [a99931801d](https://linux-hardware.org/?probe=a99931801d) | Aug 31, 2023 |
| HP            | ENVY m6                     | [eea19d891e](https://linux-hardware.org/?probe=eea19d891e) | Aug 31, 2023 |
| Dell          | Latitude 7390               | [3aaefe5b81](https://linux-hardware.org/?probe=3aaefe5b81) | Aug 31, 2023 |
| Apple         | MacBookPro10,1              | [7741e9850b](https://linux-hardware.org/?probe=7741e9850b) | Aug 31, 2023 |
| Apple         | MacBookPro15,2              | [a93751de6d](https://linux-hardware.org/?probe=a93751de6d) | Aug 30, 2023 |
| Apple         | MacBookPro16,2              | [9782f69f43](https://linux-hardware.org/?probe=9782f69f43) | Aug 30, 2023 |
| HP            | 250 G7 Notebook PC          | [1964cb4738](https://linux-hardware.org/?probe=1964cb4738) | Aug 30, 2023 |
| HP            | 250 G7 Notebook PC          | [7176f2933c](https://linux-hardware.org/?probe=7176f2933c) | Aug 30, 2023 |
| Acer          | Aspire E1-572               | [77cdb6f4a4](https://linux-hardware.org/?probe=77cdb6f4a4) | Aug 30, 2023 |
| ASUSTek       | P552LA                      | [6eca0a231c](https://linux-hardware.org/?probe=6eca0a231c) | Aug 30, 2023 |
| Dell          | Latitude 3350               | [4fa556a69f](https://linux-hardware.org/?probe=4fa556a69f) | Aug 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [dc4910965c](https://linux-hardware.org/?probe=dc4910965c) | Aug 29, 2023 |
| Apple         | MacBookPro8,1               | [43db739186](https://linux-hardware.org/?probe=43db739186) | Aug 29, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [4c46f7ae80](https://linux-hardware.org/?probe=4c46f7ae80) | Aug 28, 2023 |
| Dell          | Latitude 14 Rugged (5404... | [c96c172d03](https://linux-hardware.org/?probe=c96c172d03) | Aug 27, 2023 |
| HP            | Compaq 6710b (GE822PA#AB... | [134d0685ff](https://linux-hardware.org/?probe=134d0685ff) | Aug 26, 2023 |
| Acer          | Predator G9-793             | [531f857477](https://linux-hardware.org/?probe=531f857477) | Aug 26, 2023 |
| HP            | ProBook 450 15.6 inch G1... | [973d7867a4](https://linux-hardware.org/?probe=973d7867a4) | Aug 26, 2023 |
| Dell          | XPS 17 9700                 | [93fec269da](https://linux-hardware.org/?probe=93fec269da) | Aug 25, 2023 |
| Dell          | Vostro 2520                 | [96018ae096](https://linux-hardware.org/?probe=96018ae096) | Aug 24, 2023 |
| Lenovo        | ThinkPad R61 7732NDG        | [b0d510a7ad](https://linux-hardware.org/?probe=b0d510a7ad) | Aug 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [5a6247f9b2](https://linux-hardware.org/?probe=5a6247f9b2) | Aug 24, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [68d3bc88e4](https://linux-hardware.org/?probe=68d3bc88e4) | Aug 23, 2023 |
| HP            | Pavilion dv6                | [38fbd02f14](https://linux-hardware.org/?probe=38fbd02f14) | Aug 23, 2023 |
| Fujitsu       | S6420                       | [044d4185b7](https://linux-hardware.org/?probe=044d4185b7) | Aug 22, 2023 |
| Apple         | MacBookPro9,2               | [a8a1e5df49](https://linux-hardware.org/?probe=a8a1e5df49) | Aug 21, 2023 |
| Kogan         | KAL14N360PA                 | [527a0d3cba](https://linux-hardware.org/?probe=527a0d3cba) | Aug 20, 2023 |
| Kogan         | KAL14N360PA                 | [b7cecb1518](https://linux-hardware.org/?probe=b7cecb1518) | Aug 20, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | [b42f885e14](https://linux-hardware.org/?probe=b42f885e14) | Aug 18, 2023 |
| Toshiba       | Satellite L550              | [4c331017e2](https://linux-hardware.org/?probe=4c331017e2) | Aug 18, 2023 |
| Acer          | Aspire 5755G                | [720c3bfa88](https://linux-hardware.org/?probe=720c3bfa88) | Aug 18, 2023 |
| Acer          | Aspire E5-571               | [8a924c30e6](https://linux-hardware.org/?probe=8a924c30e6) | Aug 17, 2023 |
| MSI           | GS60 6QE                    | [3372d46d8c](https://linux-hardware.org/?probe=3372d46d8c) | Aug 16, 2023 |
| Google        | Phaser360                   | [3c248cc2c8](https://linux-hardware.org/?probe=3c248cc2c8) | Aug 16, 2023 |
| Dell          | Precision 5520              | [0516c33229](https://linux-hardware.org/?probe=0516c33229) | Aug 16, 2023 |
| Dell          | Precision 5520              | [b9a35fa791](https://linux-hardware.org/?probe=b9a35fa791) | Aug 16, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | [6242833326](https://linux-hardware.org/?probe=6242833326) | Aug 15, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | [22252eb1d9](https://linux-hardware.org/?probe=22252eb1d9) | Aug 15, 2023 |
| HP            | Notebook                    | [f32b596c87](https://linux-hardware.org/?probe=f32b596c87) | Aug 14, 2023 |
| Apple         | MacBookPro5,5               | [dc696b572c](https://linux-hardware.org/?probe=dc696b572c) | Aug 14, 2023 |
| Apple         | MacBookPro11,1              | [11b8c16b30](https://linux-hardware.org/?probe=11b8c16b30) | Aug 14, 2023 |
| Apple         | MacBookPro5,5               | [5d7e68e3ae](https://linux-hardware.org/?probe=5d7e68e3ae) | Aug 14, 2023 |
| Dell          | Latitude E7470              | [99518b81f7](https://linux-hardware.org/?probe=99518b81f7) | Aug 13, 2023 |
| HP            | ProBook 6450b               | [8862a40143](https://linux-hardware.org/?probe=8862a40143) | Aug 13, 2023 |
| Dell          | Latitude E6410              | [8ed9952374](https://linux-hardware.org/?probe=8ed9952374) | Aug 13, 2023 |
| Dell          | Inspiron M5010              | [dd2538ba1a](https://linux-hardware.org/?probe=dd2538ba1a) | Aug 13, 2023 |
| Panasonic     | CF-19ADNAXDA                | [d96cf2b13c](https://linux-hardware.org/?probe=d96cf2b13c) | Aug 12, 2023 |
| Dell          | G7 7790                     | [b5062f0928](https://linux-hardware.org/?probe=b5062f0928) | Aug 12, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [359d84713c](https://linux-hardware.org/?probe=359d84713c) | Aug 11, 2023 |
| Acer          | TMP255-M                    | [0b1adaea4e](https://linux-hardware.org/?probe=0b1adaea4e) | Aug 11, 2023 |
| Leader        | SC404PRO                    | [6f24ee5e0c](https://linux-hardware.org/?probe=6f24ee5e0c) | Aug 11, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [2f64f3ee9a](https://linux-hardware.org/?probe=2f64f3ee9a) | Aug 10, 2023 |
| Dell          | Inspiron M5010              | [be4ad618b4](https://linux-hardware.org/?probe=be4ad618b4) | Aug 09, 2023 |
| Apple         | MacBookPro15,2              | [68e26bb5d3](https://linux-hardware.org/?probe=68e26bb5d3) | Aug 09, 2023 |
| Dell          | Vostro 5581                 | [b4495daa07](https://linux-hardware.org/?probe=b4495daa07) | Aug 08, 2023 |
| Apple         | MacBookPro8,1               | [e8524b0045](https://linux-hardware.org/?probe=e8524b0045) | Aug 08, 2023 |
| HP            | Laptop 14-cm0xxx            | [ffd0be48c6](https://linux-hardware.org/?probe=ffd0be48c6) | Aug 08, 2023 |
| Dell          | XPS 13 9350                 | [fb1aaeae43](https://linux-hardware.org/?probe=fb1aaeae43) | Aug 07, 2023 |
| Dell          | Inspiron 5770               | [d6a978f124](https://linux-hardware.org/?probe=d6a978f124) | Aug 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [f2d72fe710](https://linux-hardware.org/?probe=f2d72fe710) | Aug 07, 2023 |
| Acer          | Aspire 5750G                | [3b589d53bc](https://linux-hardware.org/?probe=3b589d53bc) | Aug 06, 2023 |
| MSI           | P65 Creator 8RE             | [853567f156](https://linux-hardware.org/?probe=853567f156) | Aug 06, 2023 |
| MSI           | P65 Creator 8RE             | [f26344a920](https://linux-hardware.org/?probe=f26344a920) | Aug 05, 2023 |
| Dell          | Latitude E6220              | [636392b4bf](https://linux-hardware.org/?probe=636392b4bf) | Aug 05, 2023 |
| Acer          | AS E5-523G                  | [b37e833d1e](https://linux-hardware.org/?probe=b37e833d1e) | Aug 05, 2023 |
| Acer          | Aspire 8943G                | [fedb43e298](https://linux-hardware.org/?probe=fedb43e298) | Aug 04, 2023 |
| Lenovo        | ThinkPad T480s 20L8S84H0... | [d64e9809fa](https://linux-hardware.org/?probe=d64e9809fa) | Aug 04, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [c96666b80d](https://linux-hardware.org/?probe=c96666b80d) | Aug 03, 2023 |
| Apple         | MacBookPro11,3              | [1eb6fd9620](https://linux-hardware.org/?probe=1eb6fd9620) | Aug 02, 2023 |
| Dell          | Inspiron M5010              | [8608f29a0f](https://linux-hardware.org/?probe=8608f29a0f) | Jul 30, 2023 |
| Lenovo        | ThinkBook 13x G2 IAP 21A... | [bc18b4b7ed](https://linux-hardware.org/?probe=bc18b4b7ed) | Jul 29, 2023 |
| Lenovo        | ThinkBook 13x G2 IAP 21A... | [9b4b9b9d59](https://linux-hardware.org/?probe=9b4b9b9d59) | Jul 29, 2023 |
| Toshiba       | PORTEGE X30-E               | [c610464fb5](https://linux-hardware.org/?probe=c610464fb5) | Jul 27, 2023 |
| Acer          | TMP255-M                    | [25d376a674](https://linux-hardware.org/?probe=25d376a674) | Jul 26, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [0059745bdf](https://linux-hardware.org/?probe=0059745bdf) | Jul 25, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [90beff8e65](https://linux-hardware.org/?probe=90beff8e65) | Jul 25, 2023 |
| Acer          | TMP255-M                    | [c4bfc82a98](https://linux-hardware.org/?probe=c4bfc82a98) | Jul 24, 2023 |
| Acer          | TMP255-M                    | [7a57ee89af](https://linux-hardware.org/?probe=7a57ee89af) | Jul 24, 2023 |
| Dell          | Latitude 5410               | [29261ea2bb](https://linux-hardware.org/?probe=29261ea2bb) | Jul 24, 2023 |
| MSI           | Cyborg 15 A13VE             | [edf7b092ec](https://linux-hardware.org/?probe=edf7b092ec) | Jul 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | [35d95135f4](https://linux-hardware.org/?probe=35d95135f4) | Jul 23, 2023 |
| MSI           | Cyborg 15 A13VE             | [421c2ff6b0](https://linux-hardware.org/?probe=421c2ff6b0) | Jul 23, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | [a3350e1d80](https://linux-hardware.org/?probe=a3350e1d80) | Jul 23, 2023 |
| HP            | ZBook Studio G3             | [bcfc5b64f4](https://linux-hardware.org/?probe=bcfc5b64f4) | Jul 23, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [f525252834](https://linux-hardware.org/?probe=f525252834) | Jul 23, 2023 |
| MSI           | MEGA BOOK GX620             | [184ec8dfc2](https://linux-hardware.org/?probe=184ec8dfc2) | Jul 22, 2023 |
| Dell          | Latitude E6430s             | [8e74e2a524](https://linux-hardware.org/?probe=8e74e2a524) | Jul 22, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [fa4def4ece](https://linux-hardware.org/?probe=fa4def4ece) | Jul 21, 2023 |
| Apple         | MacBookPro14,3              | [e24c8a224e](https://linux-hardware.org/?probe=e24c8a224e) | Jul 21, 2023 |
| Toshiba       | Satellite L750              | [662f89dcc3](https://linux-hardware.org/?probe=662f89dcc3) | Jul 20, 2023 |
| HP            | 250 G5 Notebook PC          | [572537c287](https://linux-hardware.org/?probe=572537c287) | Jul 19, 2023 |
| ASRock        | Z77 Performance             | [585aaad9ad](https://linux-hardware.org/?probe=585aaad9ad) | Jul 18, 2023 |
| Toshiba       | Satellite L850              | [afdd53cd2f](https://linux-hardware.org/?probe=afdd53cd2f) | Jul 18, 2023 |
| Toshiba       | Satellite L850              | [23c31a7c87](https://linux-hardware.org/?probe=23c31a7c87) | Jul 17, 2023 |
| Lenovo        | ThinkPad X13s Gen 1 21BY... | [1a0f8c842b](https://linux-hardware.org/?probe=1a0f8c842b) | Jul 16, 2023 |
| Dell          | G5 5505                     | [ba144013b3](https://linux-hardware.org/?probe=ba144013b3) | Jul 15, 2023 |
| MSI           | Stealth 16Studio A13VG      | [ab3683571a](https://linux-hardware.org/?probe=ab3683571a) | Jul 13, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [706f24ffe5](https://linux-hardware.org/?probe=706f24ffe5) | Jul 12, 2023 |
| ASUSTek       | Zephyrus M GM501GM          | [72454f0f8e](https://linux-hardware.org/?probe=72454f0f8e) | Jul 11, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [38f91b870c](https://linux-hardware.org/?probe=38f91b870c) | Jul 11, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [e0c7ec0cbc](https://linux-hardware.org/?probe=e0c7ec0cbc) | Jul 11, 2023 |
| HP            | 250 G2                      | [7fd1832150](https://linux-hardware.org/?probe=7fd1832150) | Jul 11, 2023 |
| HP            | 250 G2                      | [738b04c947](https://linux-hardware.org/?probe=738b04c947) | Jul 11, 2023 |
| ASUSTek       | ZenBook UX431FA             | [09edc8f932](https://linux-hardware.org/?probe=09edc8f932) | Jul 11, 2023 |
| Acer          | ConceptD CN315-71P          | [a211dd78de](https://linux-hardware.org/?probe=a211dd78de) | Jul 09, 2023 |
| Toshiba       | PORTEGE Z30-C               | [f9d1d19d05](https://linux-hardware.org/?probe=f9d1d19d05) | Jul 09, 2023 |
| MSI           | Stealth 16Studio A13VG      | [e16527e244](https://linux-hardware.org/?probe=e16527e244) | Jul 09, 2023 |
| Acer          | Aspire One 753              | [f47888ce55](https://linux-hardware.org/?probe=f47888ce55) | Jul 08, 2023 |
| Acer          | Aspire One 753              | [9f56cc566d](https://linux-hardware.org/?probe=9f56cc566d) | Jul 08, 2023 |
| Toshiba       | PORTEGE X30-E               | [d68e9cd764](https://linux-hardware.org/?probe=d68e9cd764) | Jul 06, 2023 |
| ASUSTek       | G750JZA                     | [fb2477dd61](https://linux-hardware.org/?probe=fb2477dd61) | Jul 06, 2023 |
| HP            | ProBook 4540s               | [cccf56865c](https://linux-hardware.org/?probe=cccf56865c) | Jul 06, 2023 |
| Acer          | TravelMate 8572T            | [67f4a2af7e](https://linux-hardware.org/?probe=67f4a2af7e) | Jul 05, 2023 |
| Lenovo        | ThinkPad P50 20EQS48H00     | [7f64164b64](https://linux-hardware.org/?probe=7f64164b64) | Jul 04, 2023 |
| Apple         | MacBookPro9,2               | [f7a7db0702](https://linux-hardware.org/?probe=f7a7db0702) | Jul 04, 2023 |
| ASUSTek       | G750JZA                     | [72fc73822c](https://linux-hardware.org/?probe=72fc73822c) | Jul 04, 2023 |
| Dell          | Latitude 5420               | [dedd6c842c](https://linux-hardware.org/?probe=dedd6c842c) | Jul 04, 2023 |
| Dell          | Latitude 5420               | [dfe3274d7e](https://linux-hardware.org/?probe=dfe3274d7e) | Jul 03, 2023 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | [4586b855ca](https://linux-hardware.org/?probe=4586b855ca) | Jul 02, 2023 |
| Gigabyte      | Q2532N                      | [4560685060](https://linux-hardware.org/?probe=4560685060) | Jul 02, 2023 |
| Acer          | TravelMate 8572T            | [a73fd92e21](https://linux-hardware.org/?probe=a73fd92e21) | Jun 30, 2023 |
| ASRock        | Z77 Performance             | [a678dc9605](https://linux-hardware.org/?probe=a678dc9605) | Jun 29, 2023 |
| Acer          | TravelMate B113             | [04738ce824](https://linux-hardware.org/?probe=04738ce824) | Jun 29, 2023 |
| Acer          | TravelMate B113             | [9cfe4d5036](https://linux-hardware.org/?probe=9cfe4d5036) | Jun 29, 2023 |
| Unknown       | Unknown                     | [d358089f32](https://linux-hardware.org/?probe=d358089f32) | Jun 29, 2023 |
| Acer          | Aspire xxxx                 | [67e8606837](https://linux-hardware.org/?probe=67e8606837) | Jun 29, 2023 |
| HP            | Pavilion dv6                | [7fe9e439c0](https://linux-hardware.org/?probe=7fe9e439c0) | Jun 28, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [ba0db6c3e9](https://linux-hardware.org/?probe=ba0db6c3e9) | Jun 28, 2023 |
| ASUSTek       | ZenBook Pro 15 UX550GEX_... | [56eef68e89](https://linux-hardware.org/?probe=56eef68e89) | Jun 28, 2023 |
| Lenovo        | ThinkPad X230 2325CW1       | [70cbf738e8](https://linux-hardware.org/?probe=70cbf738e8) | Jun 27, 2023 |
| Apple         | MacBookPro11,1              | [06a581d65d](https://linux-hardware.org/?probe=06a581d65d) | Jun 25, 2023 |
| Apple         | MacBookPro11,1              | [a105b6264f](https://linux-hardware.org/?probe=a105b6264f) | Jun 25, 2023 |
| Toshiba       | Satellite L550              | [321ec36f85](https://linux-hardware.org/?probe=321ec36f85) | Jun 25, 2023 |
| ASUSTek       | X550LA                      | [225516996c](https://linux-hardware.org/?probe=225516996c) | Jun 25, 2023 |
| HP            | Laptop 15-db0xxx            | [79979ceac7](https://linux-hardware.org/?probe=79979ceac7) | Jun 25, 2023 |
| Acer          | Aspire A315-22              | [5e2e395efd](https://linux-hardware.org/?probe=5e2e395efd) | Jun 24, 2023 |
| HP            | EliteBook 830 G5            | [2b61a56610](https://linux-hardware.org/?probe=2b61a56610) | Jun 24, 2023 |
| System76      | Oryx Pro                    | [eaa4d8e105](https://linux-hardware.org/?probe=eaa4d8e105) | Jun 24, 2023 |
| ASUSTek       | X550LC                      | [30369c12e1](https://linux-hardware.org/?probe=30369c12e1) | Jun 24, 2023 |
| Lenovo        | ThinkPad T460s 20FAS0NF0... | [f2e368a70d](https://linux-hardware.org/?probe=f2e368a70d) | Jun 23, 2023 |
| HP            | Pavilion dv6                | [fa9045c36f](https://linux-hardware.org/?probe=fa9045c36f) | Jun 22, 2023 |
| ASUSTek       | X550LA                      | [9b58f1abd3](https://linux-hardware.org/?probe=9b58f1abd3) | Jun 20, 2023 |
| COM1          | NBINF-X5-9G5                | [fe2f1cfef6](https://linux-hardware.org/?probe=fe2f1cfef6) | Jun 19, 2023 |
| HP            | EliteBook 8760w             | [ac41230354](https://linux-hardware.org/?probe=ac41230354) | Jun 18, 2023 |
| Dell          | Latitude E7440              | [60d14fe6ab](https://linux-hardware.org/?probe=60d14fe6ab) | Jun 18, 2023 |
| Alienware     | M14xR2                      | [2eb0cc2d0e](https://linux-hardware.org/?probe=2eb0cc2d0e) | Jun 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [26b4c05332](https://linux-hardware.org/?probe=26b4c05332) | Jun 17, 2023 |
| Acer          | Aspire A315-510P            | [d1be914db1](https://linux-hardware.org/?probe=d1be914db1) | Jun 17, 2023 |
| Dell          | XPS 13 9360                 | [852d16ee14](https://linux-hardware.org/?probe=852d16ee14) | Jun 16, 2023 |
| Dell          | XPS 15 9550                 | [b7faea4be3](https://linux-hardware.org/?probe=b7faea4be3) | Jun 16, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [99cc4bf84b](https://linux-hardware.org/?probe=99cc4bf84b) | Jun 16, 2023 |
| HP            | Pavilion dv6                | [55c83ec890](https://linux-hardware.org/?probe=55c83ec890) | Jun 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [f7049b2256](https://linux-hardware.org/?probe=f7049b2256) | Jun 15, 2023 |
| Dell          | Inspiron M5010              | [33541731e3](https://linux-hardware.org/?probe=33541731e3) | Jun 14, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [b2eb89c4fd](https://linux-hardware.org/?probe=b2eb89c4fd) | Jun 13, 2023 |
| Acer          | Aspire A315-510P            | [705ad3c316](https://linux-hardware.org/?probe=705ad3c316) | Jun 12, 2023 |
| NEC Comput... | VERSA P91 series            | [7a4183e095](https://linux-hardware.org/?probe=7a4183e095) | Jun 12, 2023 |
| NEC Comput... | VERSA P91 series            | [2051db7014](https://linux-hardware.org/?probe=2051db7014) | Jun 12, 2023 |
| COM1          | NBINF-X5-9G5                | [755841cee1](https://linux-hardware.org/?probe=755841cee1) | Jun 11, 2023 |
| MSI           | GS60 6QE                    | [e04ff9df40](https://linux-hardware.org/?probe=e04ff9df40) | Jun 10, 2023 |
| Toshiba       | PORTEGE Z10t-A              | [4a0712b322](https://linux-hardware.org/?probe=4a0712b322) | Jun 10, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [5d21e64704](https://linux-hardware.org/?probe=5d21e64704) | Jun 10, 2023 |
| IT Channel... | N8xEJEK                     | [51a7e3f5b4](https://linux-hardware.org/?probe=51a7e3f5b4) | Jun 10, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [ee9c6252ae](https://linux-hardware.org/?probe=ee9c6252ae) | Jun 07, 2023 |
| Apple         | MacBookPro14,1              | [b0435761df](https://linux-hardware.org/?probe=b0435761df) | Jun 07, 2023 |
| Apple         | MacBookPro14,1              | [a76212cc40](https://linux-hardware.org/?probe=a76212cc40) | Jun 07, 2023 |
| Apple         | MacBookAir4,2               | [afc9f50009](https://linux-hardware.org/?probe=afc9f50009) | Jun 05, 2023 |
| MSI           | GS60 6QE                    | [65ea70f7fa](https://linux-hardware.org/?probe=65ea70f7fa) | Jun 03, 2023 |
| Acer          | TravelMate 8572T            | [46920007ed](https://linux-hardware.org/?probe=46920007ed) | Jun 03, 2023 |
| Toshiba       | Satellite P870              | [559a48c91b](https://linux-hardware.org/?probe=559a48c91b) | Jun 01, 2023 |
| Dell          | XPS 15 9570                 | [6d7803788d](https://linux-hardware.org/?probe=6d7803788d) | Jun 01, 2023 |
| Intel Clie... | LAPRC710                    | [ef0d589f75](https://linux-hardware.org/?probe=ef0d589f75) | May 31, 2023 |
| Acer          | Predator G9-793             | [26ea66d872](https://linux-hardware.org/?probe=26ea66d872) | May 31, 2023 |
| Acer          | E5-551G-871W                | [8034a1ee0b](https://linux-hardware.org/?probe=8034a1ee0b) | May 30, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [c75d4298dc](https://linux-hardware.org/?probe=c75d4298dc) | May 30, 2023 |
| Toshiba       | Satellite C665              | [c6149a6430](https://linux-hardware.org/?probe=c6149a6430) | May 30, 2023 |
| Toshiba       | Satellite P870              | [2b57ca6d62](https://linux-hardware.org/?probe=2b57ca6d62) | May 29, 2023 |
| Valve         | Jupiter                     | [e6e97426e3](https://linux-hardware.org/?probe=e6e97426e3) | May 29, 2023 |
| HP            | EliteBook 840 G1            | [c256cd6942](https://linux-hardware.org/?probe=c256cd6942) | May 28, 2023 |
| Apple         | MacBookPro10,2              | [34d96aa1df](https://linux-hardware.org/?probe=34d96aa1df) | May 28, 2023 |
| Lenovo        | IdeaPad 3 14ABA7 82RM       | [d83ee3fda2](https://linux-hardware.org/?probe=d83ee3fda2) | May 28, 2023 |
| Acer          | Aspire A315-22              | [18a13174aa](https://linux-hardware.org/?probe=18a13174aa) | May 27, 2023 |
| Lenovo        | ThinkPad W541 20EGS1AR00    | [b7f46e7180](https://linux-hardware.org/?probe=b7f46e7180) | May 27, 2023 |
| Dell          | Latitude 5430               | [e8b9199229](https://linux-hardware.org/?probe=e8b9199229) | May 26, 2023 |
| Lenovo        | ThinkPad W541 20EGS1AR00    | [a5301f505d](https://linux-hardware.org/?probe=a5301f505d) | May 25, 2023 |
| Apple         | MacBookPro8,1               | [585b85e476](https://linux-hardware.org/?probe=585b85e476) | May 23, 2023 |
| Dell          | Latitude 7280               | [215bef2144](https://linux-hardware.org/?probe=215bef2144) | May 23, 2023 |
| Apple         | MacBookPro8,1               | [ca5f5ee7bf](https://linux-hardware.org/?probe=ca5f5ee7bf) | May 23, 2023 |
| Acer          | Aspire A515-56              | [dfb369a8d2](https://linux-hardware.org/?probe=dfb369a8d2) | May 22, 2023 |
| COM1          | NBINF-X5-9G5                | [33aa60eaa2](https://linux-hardware.org/?probe=33aa60eaa2) | May 22, 2023 |
| COM1          | NBINF-X5-9G5                | [8d8c13c10c](https://linux-hardware.org/?probe=8d8c13c10c) | May 22, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [b0fac119c2](https://linux-hardware.org/?probe=b0fac119c2) | May 22, 2023 |
| ASUSTek       | K56CA                       | [6ae76c1553](https://linux-hardware.org/?probe=6ae76c1553) | May 21, 2023 |
| MSI           | VR601                       | [7f9381407d](https://linux-hardware.org/?probe=7f9381407d) | May 19, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [4a9869b7a6](https://linux-hardware.org/?probe=4a9869b7a6) | May 19, 2023 |
| Apple         | MacBookAir7,2               | [337509e694](https://linux-hardware.org/?probe=337509e694) | May 19, 2023 |
| ASUSTek       | Zephyrus M GM501GM          | [bf1eed0e60](https://linux-hardware.org/?probe=bf1eed0e60) | May 18, 2023 |
| HP            | Pavilion 15                 | [fd87e57fc3](https://linux-hardware.org/?probe=fd87e57fc3) | May 18, 2023 |
| Dell          | Vostro V131                 | [e20ddd5bca](https://linux-hardware.org/?probe=e20ddd5bca) | May 18, 2023 |
| Dell          | Vostro V131                 | [7714e1784a](https://linux-hardware.org/?probe=7714e1784a) | May 18, 2023 |
| HP            | Notebook                    | [8d3bd6a690](https://linux-hardware.org/?probe=8d3bd6a690) | May 17, 2023 |
| Acer          | Predator G9-793             | [1739ea2f45](https://linux-hardware.org/?probe=1739ea2f45) | May 17, 2023 |
| MSI           | Summit E14FlipEvo A13MT     | [60e19220b9](https://linux-hardware.org/?probe=60e19220b9) | May 15, 2023 |
| ASUSTek       | ZenBook S UX391UA           | [fe36fee27a](https://linux-hardware.org/?probe=fe36fee27a) | May 14, 2023 |
| Acer          | Aspire ES1-531              | [56cdac831f](https://linux-hardware.org/?probe=56cdac831f) | May 13, 2023 |
| Gigabyte      | P34V7                       | [90e6e5d5d9](https://linux-hardware.org/?probe=90e6e5d5d9) | May 13, 2023 |
| Unknown       | Unknown                     | [3fbabd3df0](https://linux-hardware.org/?probe=3fbabd3df0) | May 11, 2023 |
| Acer          | Predator G9-793             | [95595808a8](https://linux-hardware.org/?probe=95595808a8) | May 11, 2023 |
| Toshiba       | Satellite M60               | [91437556e8](https://linux-hardware.org/?probe=91437556e8) | May 09, 2023 |
| Toshiba       | Satellite M60               | [39b2bcd3a5](https://linux-hardware.org/?probe=39b2bcd3a5) | May 09, 2023 |
| Dell          | Inspiron N5010              | [5dd91a589b](https://linux-hardware.org/?probe=5dd91a589b) | May 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [503204d798](https://linux-hardware.org/?probe=503204d798) | May 09, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [def28849c6](https://linux-hardware.org/?probe=def28849c6) | May 08, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [f23fb5cca0](https://linux-hardware.org/?probe=f23fb5cca0) | May 08, 2023 |
| Apple         | MacBook4,1                  | [3daf4fbc68](https://linux-hardware.org/?probe=3daf4fbc68) | May 07, 2023 |
| Dell          | Inspiron N5010              | [2a418b4e97](https://linux-hardware.org/?probe=2a418b4e97) | May 07, 2023 |
| Lenovo        | Mixx-700-12ISK 80QL         | [14bc666ec3](https://linux-hardware.org/?probe=14bc666ec3) | May 06, 2023 |
| Toshiba       | PORTEGE Z30t-A              | [18cc14eee0](https://linux-hardware.org/?probe=18cc14eee0) | May 05, 2023 |
| System76      | Oryx Pro                    | [cae9fadc38](https://linux-hardware.org/?probe=cae9fadc38) | May 04, 2023 |
| Acer          | Predator G9-793             | [b3bd1a1031](https://linux-hardware.org/?probe=b3bd1a1031) | May 03, 2023 |
| Intel Clie... | LAPRC510                    | [40c181b615](https://linux-hardware.org/?probe=40c181b615) | May 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [925b5748b9](https://linux-hardware.org/?probe=925b5748b9) | May 01, 2023 |
| Lenovo        | ThinkPad X260 20F5002NAU    | [7fcb72c132](https://linux-hardware.org/?probe=7fcb72c132) | May 01, 2023 |
| ASUSTek       | X501A1                      | [66b02cc148](https://linux-hardware.org/?probe=66b02cc148) | Apr 30, 2023 |
| HP            | Laptop 15s-eq2xxx           | [7a86bdd993](https://linux-hardware.org/?probe=7a86bdd993) | Apr 30, 2023 |
| HP            | Laptop 15s-eq2xxx           | [6206b317f2](https://linux-hardware.org/?probe=6206b317f2) | Apr 30, 2023 |
| Acer          | ConceptD CN315-71P          | [3cc902ff5c](https://linux-hardware.org/?probe=3cc902ff5c) | Apr 28, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [73141c5006](https://linux-hardware.org/?probe=73141c5006) | Apr 27, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [0cb164ac2f](https://linux-hardware.org/?probe=0cb164ac2f) | Apr 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3f44947226](https://linux-hardware.org/?probe=3f44947226) | Apr 27, 2023 |
| HP            | Laptop 15s-eq2xxx           | [198fa6162e](https://linux-hardware.org/?probe=198fa6162e) | Apr 27, 2023 |
| ASUSTek       | X550CA                      | [a63293fe36](https://linux-hardware.org/?probe=a63293fe36) | Apr 26, 2023 |
| Dell          | Inspiron 5548               | [42908a7ab7](https://linux-hardware.org/?probe=42908a7ab7) | Apr 25, 2023 |
| Dell          | System XPS L702X            | [d1aa167e90](https://linux-hardware.org/?probe=d1aa167e90) | Apr 25, 2023 |
| Acer          | E5-551G-871W                | [2730a30d89](https://linux-hardware.org/?probe=2730a30d89) | Apr 25, 2023 |
| MSI           | GE72VR 6RF                  | [89cb17ee72](https://linux-hardware.org/?probe=89cb17ee72) | Apr 25, 2023 |
| Dell          | Precision 5520              | [4d1dd8b673](https://linux-hardware.org/?probe=4d1dd8b673) | Apr 23, 2023 |
| Valve         | Jupiter                     | [b5be7aa6ff](https://linux-hardware.org/?probe=b5be7aa6ff) | Apr 21, 2023 |
| Acer          | Predator G9-793             | [664d6de816](https://linux-hardware.org/?probe=664d6de816) | Apr 20, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | [8daf9af9b5](https://linux-hardware.org/?probe=8daf9af9b5) | Apr 20, 2023 |
| Acer          | Aspire 5733Z                | [de205c8c62](https://linux-hardware.org/?probe=de205c8c62) | Apr 19, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | [7da02a75b5](https://linux-hardware.org/?probe=7da02a75b5) | Apr 18, 2023 |
| Toshiba       | Satellite E45-B             | [ec0bb6bfc6](https://linux-hardware.org/?probe=ec0bb6bfc6) | Apr 17, 2023 |
| Dell          | Inspiron 13-5378            | [bcb18ae818](https://linux-hardware.org/?probe=bcb18ae818) | Apr 17, 2023 |
| HP            | Pavilion dv6                | [fc41269cf8](https://linux-hardware.org/?probe=fc41269cf8) | Apr 16, 2023 |
| Dell          | Latitude 5420               | [03247dc98c](https://linux-hardware.org/?probe=03247dc98c) | Apr 16, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [71e03c5459](https://linux-hardware.org/?probe=71e03c5459) | Apr 15, 2023 |
| Apple         | MacBookPro7,1               | [3470b35550](https://linux-hardware.org/?probe=3470b35550) | Apr 15, 2023 |
| Toshiba       | QOSMIO F750                 | [590801670a](https://linux-hardware.org/?probe=590801670a) | Apr 15, 2023 |
| Toshiba       | Satellite L850              | [dc9e77bd65](https://linux-hardware.org/?probe=dc9e77bd65) | Apr 14, 2023 |
| Dell          | Latitude E6540              | [61ab891b01](https://linux-hardware.org/?probe=61ab891b01) | Apr 13, 2023 |
| Dell          | Vostro 7590                 | [f759d8ab72](https://linux-hardware.org/?probe=f759d8ab72) | Apr 13, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [8e641b5fd5](https://linux-hardware.org/?probe=8e641b5fd5) | Apr 13, 2023 |
| Acer          | Aspire 5720Z                | [1ac7eb0d0c](https://linux-hardware.org/?probe=1ac7eb0d0c) | Apr 13, 2023 |
| Acer          | TM6495T                     | [435ae018a2](https://linux-hardware.org/?probe=435ae018a2) | Apr 11, 2023 |
| Lenovo        | ThinkPad E460 20ETA05KAU    | [a8090f51bc](https://linux-hardware.org/?probe=a8090f51bc) | Apr 09, 2023 |
| Dell          | Inspiron 1720               | [a2e3b07f6b](https://linux-hardware.org/?probe=a2e3b07f6b) | Apr 09, 2023 |
| Dell          | Latitude E5470              | [3e49e9c541](https://linux-hardware.org/?probe=3e49e9c541) | Apr 08, 2023 |
| Apple         | MacBookAir7,2               | [5aad90904c](https://linux-hardware.org/?probe=5aad90904c) | Apr 07, 2023 |
| Acer          | TravelMate 8572T            | [04f50662d8](https://linux-hardware.org/?probe=04f50662d8) | Apr 07, 2023 |
| Toshiba       | Satellite P70-A             | [6ffb7a79ef](https://linux-hardware.org/?probe=6ffb7a79ef) | Apr 06, 2023 |
| HP            | Pavilion dv6                | [be695e2cd4](https://linux-hardware.org/?probe=be695e2cd4) | Apr 06, 2023 |
| HP            | ZBook 17 G2                 | [258f32d502](https://linux-hardware.org/?probe=258f32d502) | Apr 05, 2023 |
| HUAWEI        | MACHD-WXX9                  | [7e5be74f0b](https://linux-hardware.org/?probe=7e5be74f0b) | Apr 05, 2023 |
| Apple         | MacBookPro10,1              | [473a8c1d7b](https://linux-hardware.org/?probe=473a8c1d7b) | Apr 05, 2023 |
| HP            | Notebook                    | [50c03e608d](https://linux-hardware.org/?probe=50c03e608d) | Apr 05, 2023 |
| Apple         | MacBookPro10,1              | [56079f49e3](https://linux-hardware.org/?probe=56079f49e3) | Apr 04, 2023 |
| Apple         | MacBookPro8,1               | [4ef5210167](https://linux-hardware.org/?probe=4ef5210167) | Apr 04, 2023 |
| HP            | EliteBook Folio 1040 G3     | [9e25dfd6bb](https://linux-hardware.org/?probe=9e25dfd6bb) | Apr 02, 2023 |
| HP            | ProBook 650 G2              | [89622c73d1](https://linux-hardware.org/?probe=89622c73d1) | Apr 02, 2023 |
| Dell          | XPS 15 9570                 | [7beef34820](https://linux-hardware.org/?probe=7beef34820) | Apr 01, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [2a881cc01e](https://linux-hardware.org/?probe=2a881cc01e) | Apr 01, 2023 |
| HP            | ProBook 450 G5              | [89dfecad7e](https://linux-hardware.org/?probe=89dfecad7e) | Mar 30, 2023 |
| Dell          | XPS 15 9570                 | [8d0c93e1a8](https://linux-hardware.org/?probe=8d0c93e1a8) | Mar 30, 2023 |
| Dell          | Precision 5550              | [c7244f1e31](https://linux-hardware.org/?probe=c7244f1e31) | Mar 30, 2023 |
| Dell          | G3 3590                     | [f61ce9bb82](https://linux-hardware.org/?probe=f61ce9bb82) | Mar 28, 2023 |
| MSI           | Delta 15 A5EFK              | [6f4e3ec28b](https://linux-hardware.org/?probe=6f4e3ec28b) | Mar 28, 2023 |
| MSI           | Delta 15 A5EFK              | [9dd1b67b2f](https://linux-hardware.org/?probe=9dd1b67b2f) | Mar 28, 2023 |
| HUAWEI        | NBD-WXX9                    | [8060aec150](https://linux-hardware.org/?probe=8060aec150) | Mar 25, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [9edd5002f0](https://linux-hardware.org/?probe=9edd5002f0) | Mar 24, 2023 |
| HP            | ProBook 470 G5              | [1672158957](https://linux-hardware.org/?probe=1672158957) | Mar 24, 2023 |
| HP            | ProBook 470 G5              | [383b333f72](https://linux-hardware.org/?probe=383b333f72) | Mar 24, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [fc1c184c05](https://linux-hardware.org/?probe=fc1c184c05) | Mar 23, 2023 |
| Acer          | ConceptD CN315-71P          | [14b71e7a26](https://linux-hardware.org/?probe=14b71e7a26) | Mar 22, 2023 |
| HP            | EliteBook 8470p             | [61025e6e8b](https://linux-hardware.org/?probe=61025e6e8b) | Mar 22, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [80d1a2d67d](https://linux-hardware.org/?probe=80d1a2d67d) | Mar 22, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [eb718edb23](https://linux-hardware.org/?probe=eb718edb23) | Mar 22, 2023 |
| Dell          | Latitude E6520              | [857fdb4095](https://linux-hardware.org/?probe=857fdb4095) | Mar 21, 2023 |
| Dell          | Inspiron 5559               | [6f98b39459](https://linux-hardware.org/?probe=6f98b39459) | Mar 21, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [786fded1ce](https://linux-hardware.org/?probe=786fded1ce) | Mar 17, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [49bb337156](https://linux-hardware.org/?probe=49bb337156) | Mar 17, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [d762fe2bf3](https://linux-hardware.org/?probe=d762fe2bf3) | Mar 17, 2023 |
| Valve         | Jupiter                     | [8f51ab644e](https://linux-hardware.org/?probe=8f51ab644e) | Mar 17, 2023 |
| Dell          | G3 3590                     | [9ef42643d8](https://linux-hardware.org/?probe=9ef42643d8) | Mar 16, 2023 |
| HP            | ProBook 430 G8 Notebook ... | [ca6ab3c197](https://linux-hardware.org/?probe=ca6ab3c197) | Mar 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [684375b9a0](https://linux-hardware.org/?probe=684375b9a0) | Mar 16, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [787dfaa7d4](https://linux-hardware.org/?probe=787dfaa7d4) | Mar 15, 2023 |
| Acer          | Swift SFX14-41G             | [59478f318e](https://linux-hardware.org/?probe=59478f318e) | Mar 14, 2023 |
| Dell          | XPS 13 9360                 | [954055245e](https://linux-hardware.org/?probe=954055245e) | Mar 14, 2023 |
| Dell          | Inspiron M5010              | [0a5d0c9169](https://linux-hardware.org/?probe=0a5d0c9169) | Mar 14, 2023 |
| Acer          | Aspire E5-511               | [5343f73c67](https://linux-hardware.org/?probe=5343f73c67) | Mar 13, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [b5d8bdc57d](https://linux-hardware.org/?probe=b5d8bdc57d) | Mar 12, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [4525fa2931](https://linux-hardware.org/?probe=4525fa2931) | Mar 12, 2023 |
| Lenovo        | ThinkPad E590 20NBA000AU    | [47bfd44610](https://linux-hardware.org/?probe=47bfd44610) | Mar 12, 2023 |
| Maibenben     | P748                        | [a44d1bb8e4](https://linux-hardware.org/?probe=a44d1bb8e4) | Mar 11, 2023 |
| Dell          | XPS 15 9570                 | [9d14bee09f](https://linux-hardware.org/?probe=9d14bee09f) | Mar 10, 2023 |
| HP            | Laptop 15-db0xxx            | [ded87de736](https://linux-hardware.org/?probe=ded87de736) | Mar 09, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [54ad36532c](https://linux-hardware.org/?probe=54ad36532c) | Mar 07, 2023 |
| HP            | Stream Laptop 11-ah1XX      | [61e3840465](https://linux-hardware.org/?probe=61e3840465) | Mar 07, 2023 |
| HP            | Compaq Presario C700        | [fe1c136403](https://linux-hardware.org/?probe=fe1c136403) | Mar 06, 2023 |
| HP            | Compaq Presario C700        | [0b29805ec8](https://linux-hardware.org/?probe=0b29805ec8) | Mar 06, 2023 |
| HP            | ENVY 17                     | [ce2278a2e4](https://linux-hardware.org/?probe=ce2278a2e4) | Mar 05, 2023 |
| Google        | Ultima                      | [5e42f67839](https://linux-hardware.org/?probe=5e42f67839) | Mar 04, 2023 |
| Valve         | Jupiter                     | [65a9e7ef52](https://linux-hardware.org/?probe=65a9e7ef52) | Mar 04, 2023 |
| HP            | Pavilion Notebook           | [906cb4b50a](https://linux-hardware.org/?probe=906cb4b50a) | Mar 03, 2023 |
| Lenovo        | V14-ADA 82C6                | [f043beec18](https://linux-hardware.org/?probe=f043beec18) | Mar 03, 2023 |
| HP            | Pavilion Notebook           | [2173dea5df](https://linux-hardware.org/?probe=2173dea5df) | Mar 02, 2023 |
| Toshiba       | TECRA Z50-C                 | [c30ead38bd](https://linux-hardware.org/?probe=c30ead38bd) | Mar 02, 2023 |
| Apple         | MacBookPro14,3              | [6f952b4c9b](https://linux-hardware.org/?probe=6f952b4c9b) | Mar 01, 2023 |
| Intel Clie... | LAPRC510                    | [925c24b3db](https://linux-hardware.org/?probe=925c24b3db) | Feb 28, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [021853dafb](https://linux-hardware.org/?probe=021853dafb) | Feb 28, 2023 |
| Intel Clie... | LAPRC510                    | [6d9a8edb0c](https://linux-hardware.org/?probe=6d9a8edb0c) | Feb 28, 2023 |
| Apple         | MacBookPro10,1              | [816a4eb27e](https://linux-hardware.org/?probe=816a4eb27e) | Feb 26, 2023 |
| HP            | Notebook                    | [4a72575c17](https://linux-hardware.org/?probe=4a72575c17) | Feb 25, 2023 |
| Toshiba       | Satellite C850              | [99d4efbb52](https://linux-hardware.org/?probe=99d4efbb52) | Feb 25, 2023 |
| Apple         | MacBookAir7,2               | [72e11db1c0](https://linux-hardware.org/?probe=72e11db1c0) | Feb 24, 2023 |
| MSI           | Vector GP66 12UEO           | [9b6bf9479e](https://linux-hardware.org/?probe=9b6bf9479e) | Feb 24, 2023 |
| HUAWEI        | NBD-WXX9                    | [ea2663126f](https://linux-hardware.org/?probe=ea2663126f) | Feb 24, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [fa9427d71f](https://linux-hardware.org/?probe=fa9427d71f) | Feb 22, 2023 |
| Lenovo        | ThinkPad X131e 3367AH5      | [3c1cec4c1c](https://linux-hardware.org/?probe=3c1cec4c1c) | Feb 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [8110c575e9](https://linux-hardware.org/?probe=8110c575e9) | Feb 22, 2023 |
| Acer          | TravelMate 8572T            | [20d7321f8f](https://linux-hardware.org/?probe=20d7321f8f) | Feb 21, 2023 |
| Dell          | Latitude 5430               | [69fd82c453](https://linux-hardware.org/?probe=69fd82c453) | Feb 21, 2023 |
| Dell          | Latitude E6430              | [42750c43b5](https://linux-hardware.org/?probe=42750c43b5) | Feb 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [d4663db4e0](https://linux-hardware.org/?probe=d4663db4e0) | Feb 19, 2023 |
| HP            | 250 G5 Notebook PC          | [ca676dc566](https://linux-hardware.org/?probe=ca676dc566) | Feb 19, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [9b0ecbd3c7](https://linux-hardware.org/?probe=9b0ecbd3c7) | Feb 19, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [cc44156b99](https://linux-hardware.org/?probe=cc44156b99) | Feb 17, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [bc234d0b32](https://linux-hardware.org/?probe=bc234d0b32) | Feb 17, 2023 |
| Toshiba       | Satellite P750              | [6f5f99b514](https://linux-hardware.org/?probe=6f5f99b514) | Feb 16, 2023 |
| HUAWEI        | NBD-WXX9                    | [8f5697ea3a](https://linux-hardware.org/?probe=8f5697ea3a) | Feb 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [1a20fdd090](https://linux-hardware.org/?probe=1a20fdd090) | Feb 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [3384ced1ca](https://linux-hardware.org/?probe=3384ced1ca) | Feb 14, 2023 |
| MSI           | Vector GP66 12UEO           | [040bddeff8](https://linux-hardware.org/?probe=040bddeff8) | Feb 14, 2023 |
| HP            | Compaq nc6400 (RM741PA#A... | [d556bf453d](https://linux-hardware.org/?probe=d556bf453d) | Feb 13, 2023 |
| ASUSTek       | K45VS                       | [faf4fc0251](https://linux-hardware.org/?probe=faf4fc0251) | Feb 12, 2023 |
| HP            | 250 G5 Notebook PC          | [72b0ba099a](https://linux-hardware.org/?probe=72b0ba099a) | Feb 11, 2023 |
| Acer          | Aspire One 753              | [b3ef912b35](https://linux-hardware.org/?probe=b3ef912b35) | Feb 10, 2023 |
| Dell          | G15 5520                    | [121b06f3cc](https://linux-hardware.org/?probe=121b06f3cc) | Feb 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [e3ea6ad8da](https://linux-hardware.org/?probe=e3ea6ad8da) | Feb 10, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [b79b2f3f75](https://linux-hardware.org/?probe=b79b2f3f75) | Feb 09, 2023 |
| Dell          | G15 5520                    | [7f4d36cea1](https://linux-hardware.org/?probe=7f4d36cea1) | Feb 08, 2023 |
| Alienware     | m15 R7                      | [254ab40fcf](https://linux-hardware.org/?probe=254ab40fcf) | Feb 07, 2023 |
| HP            | Laptop 15s-eq2xxx           | [4a647dd6b9](https://linux-hardware.org/?probe=4a647dd6b9) | Feb 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [8b26ec07a6](https://linux-hardware.org/?probe=8b26ec07a6) | Feb 07, 2023 |
| Acer          | Aspire E3-111               | [a7c14e51ff](https://linux-hardware.org/?probe=a7c14e51ff) | Feb 06, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a0fc4f78ea](https://linux-hardware.org/?probe=a0fc4f78ea) | Feb 05, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [5a7ae4b151](https://linux-hardware.org/?probe=5a7ae4b151) | Feb 05, 2023 |
| HUAWEI        | NBD-WXX9                    | [0eb4367fb4](https://linux-hardware.org/?probe=0eb4367fb4) | Feb 04, 2023 |
| ASUSTek       | X550LC                      | [f22682c35f](https://linux-hardware.org/?probe=f22682c35f) | Feb 04, 2023 |
| Toshiba       | Satellite P500              | [78ebd7c272](https://linux-hardware.org/?probe=78ebd7c272) | Feb 04, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [13bdc2b06c](https://linux-hardware.org/?probe=13bdc2b06c) | Feb 03, 2023 |
| Toshiba       | Satellite C660              | [9cabffbc86](https://linux-hardware.org/?probe=9cabffbc86) | Feb 03, 2023 |
| HUAWEI        | NBD-WXX9                    | [17b77b89e5](https://linux-hardware.org/?probe=17b77b89e5) | Feb 03, 2023 |
| Lenovo        | ThinkPad T420s 4173CTO      | [232ff7a382](https://linux-hardware.org/?probe=232ff7a382) | Feb 02, 2023 |
| HP            | 250 G5 Notebook PC          | [687b1ec2d7](https://linux-hardware.org/?probe=687b1ec2d7) | Feb 02, 2023 |
| Dell          | Latitude E6520              | [548b13cd43](https://linux-hardware.org/?probe=548b13cd43) | Feb 02, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [465114aa14](https://linux-hardware.org/?probe=465114aa14) | Feb 01, 2023 |
| Acer          | Predator PH315-52           | [b1c77eb9c7](https://linux-hardware.org/?probe=b1c77eb9c7) | Jan 31, 2023 |
| ASUSTek       | X550LC                      | [4c50999862](https://linux-hardware.org/?probe=4c50999862) | Jan 30, 2023 |
| ASUSTek       | X550LC                      | [41d606bbe8](https://linux-hardware.org/?probe=41d606bbe8) | Jan 30, 2023 |
| Dell          | Inspiron 5770               | [b5612c2501](https://linux-hardware.org/?probe=b5612c2501) | Jan 29, 2023 |
| Dell          | Latitude 5400               | [80651273e4](https://linux-hardware.org/?probe=80651273e4) | Jan 29, 2023 |
| Dell          | Latitude 5400               | [eb97e73f08](https://linux-hardware.org/?probe=eb97e73f08) | Jan 29, 2023 |
| Apple         | MacBook8,1                  | [02cd28549c](https://linux-hardware.org/?probe=02cd28549c) | Jan 27, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 D... | [d2a46bd14a](https://linux-hardware.org/?probe=d2a46bd14a) | Jan 26, 2023 |
| Apple         | MacBook5,1                  | [b7759508d9](https://linux-hardware.org/?probe=b7759508d9) | Jan 26, 2023 |
| Apple         | MacBook5,1                  | [72f2c3fddc](https://linux-hardware.org/?probe=72f2c3fddc) | Jan 26, 2023 |
| Panasonic     | FZ55-2                      | [dd9ddb12b6](https://linux-hardware.org/?probe=dd9ddb12b6) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [26abf66da5](https://linux-hardware.org/?probe=26abf66da5) | Jan 25, 2023 |
| Acer          | Aspire A315-22              | [7c048a8058](https://linux-hardware.org/?probe=7c048a8058) | Jan 24, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [c2226035ce](https://linux-hardware.org/?probe=c2226035ce) | Jan 24, 2023 |
| Alienware     | 15 R4                       | [8833335118](https://linux-hardware.org/?probe=8833335118) | Jan 23, 2023 |
| Dell          | XPS 13 9350                 | [223ab1f016](https://linux-hardware.org/?probe=223ab1f016) | Jan 22, 2023 |
| Lenovo        | ThinkPad X250 20CLS2JV01    | [932148f478](https://linux-hardware.org/?probe=932148f478) | Jan 21, 2023 |
| Dell          | XPS 9315                    | [9dfb19b7c1](https://linux-hardware.org/?probe=9dfb19b7c1) | Jan 21, 2023 |
| Dell          | Latitude 5300               | [e8c4218110](https://linux-hardware.org/?probe=e8c4218110) | Jan 21, 2023 |
| Apple         | MacBookPro11,3              | [28b4d041ad](https://linux-hardware.org/?probe=28b4d041ad) | Jan 20, 2023 |
| Apple         | MacBookAir7,2               | [ead0a07135](https://linux-hardware.org/?probe=ead0a07135) | Jan 20, 2023 |
| Apple         | MacBookAir5,2               | [03e73c44b7](https://linux-hardware.org/?probe=03e73c44b7) | Jan 20, 2023 |
| Apple         | MacBookPro14,3              | [82a49878eb](https://linux-hardware.org/?probe=82a49878eb) | Jan 19, 2023 |
| Dell          | XPS 15 7590                 | [9a7659a260](https://linux-hardware.org/?probe=9a7659a260) | Jan 18, 2023 |
| Dell          | Precision 3561              | [9528d74be6](https://linux-hardware.org/?probe=9528d74be6) | Jan 18, 2023 |
| Dell          | Precision 3561              | [5f23addbde](https://linux-hardware.org/?probe=5f23addbde) | Jan 18, 2023 |
| Lenovo        | ThinkPad X230 2325CW1       | [44a8ae0b56](https://linux-hardware.org/?probe=44a8ae0b56) | Jan 17, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [a80f36a4eb](https://linux-hardware.org/?probe=a80f36a4eb) | Jan 16, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [f0b2886993](https://linux-hardware.org/?probe=f0b2886993) | Jan 15, 2023 |
| Acer          | Aspire R3-131T              | [268413b274](https://linux-hardware.org/?probe=268413b274) | Jan 15, 2023 |
| Valve         | Jupiter                     | [8830efc64d](https://linux-hardware.org/?probe=8830efc64d) | Jan 15, 2023 |
| HP            | Laptop 14s-dk0xxx           | [6efb68b8da](https://linux-hardware.org/?probe=6efb68b8da) | Jan 14, 2023 |
| Lenovo        | V14-IIL 82C4                | [3837db6f8a](https://linux-hardware.org/?probe=3837db6f8a) | Jan 13, 2023 |
| Intel Clie... | LAPBC510                    | [493f0e9608](https://linux-hardware.org/?probe=493f0e9608) | Jan 13, 2023 |
| Dell          | Latitude 5300               | [148745c883](https://linux-hardware.org/?probe=148745c883) | Jan 13, 2023 |
| Intel Clie... | LAPBC510                    | [ac0b81bf2e](https://linux-hardware.org/?probe=ac0b81bf2e) | Jan 13, 2023 |
| Acer          | Predator PH315-52           | [c6a710b940](https://linux-hardware.org/?probe=c6a710b940) | Jan 13, 2023 |
| Dell          | Inspiron 5770               | [7435d85aca](https://linux-hardware.org/?probe=7435d85aca) | Jan 12, 2023 |
| Dell          | XPS 17 9700                 | [09f6a754d6](https://linux-hardware.org/?probe=09f6a754d6) | Jan 12, 2023 |
| Acer          | Swift SF514-54T             | [98a18475e8](https://linux-hardware.org/?probe=98a18475e8) | Jan 11, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [511306775e](https://linux-hardware.org/?probe=511306775e) | Jan 11, 2023 |
| Dell          | Inspiron 3543               | [c7c7419fd5](https://linux-hardware.org/?probe=c7c7419fd5) | Jan 10, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [17dc10d7bb](https://linux-hardware.org/?probe=17dc10d7bb) | Jan 10, 2023 |
| Lenovo        | ThinkPad T430s 2356AF9      | [eca34fb600](https://linux-hardware.org/?probe=eca34fb600) | Jan 09, 2023 |
| Dell          | XPS 13 9333                 | [f291c4d057](https://linux-hardware.org/?probe=f291c4d057) | Jan 09, 2023 |
| HP            | EliteBook Folio 9470m       | [1c4f7f2f2a](https://linux-hardware.org/?probe=1c4f7f2f2a) | Jan 09, 2023 |
| Dell          | Latitude 7280               | [931dcfb8be](https://linux-hardware.org/?probe=931dcfb8be) | Jan 08, 2023 |
| Dell          | Latitude E7450              | [635ef7be4a](https://linux-hardware.org/?probe=635ef7be4a) | Jan 08, 2023 |
| Lenovo        | ThinkPad W530 2463B87       | [5ac9828d4c](https://linux-hardware.org/?probe=5ac9828d4c) | Jan 08, 2023 |
| Acer          | Predator G9-793             | [5256ec6943](https://linux-hardware.org/?probe=5256ec6943) | Jan 07, 2023 |
| Apple         | MacBookPro12,1              | [67f40c78ec](https://linux-hardware.org/?probe=67f40c78ec) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | [58f2e834d8](https://linux-hardware.org/?probe=58f2e834d8) | Jan 06, 2023 |
| GPU Compan... | GWTN156-2BK                 | [263354b92e](https://linux-hardware.org/?probe=263354b92e) | Jan 06, 2023 |
| Dell          | Precision M4700             | [414d8c4701](https://linux-hardware.org/?probe=414d8c4701) | Jan 06, 2023 |
| GPU Compan... | GWTN156-2BK                 | [99bf8fff2f](https://linux-hardware.org/?probe=99bf8fff2f) | Jan 06, 2023 |
| GPU Compan... | GWTN156-2BK                 | [d9fa2355b0](https://linux-hardware.org/?probe=d9fa2355b0) | Jan 05, 2023 |
| HP            | Laptop 15s-fq1xxx           | [488e1f656c](https://linux-hardware.org/?probe=488e1f656c) | Jan 03, 2023 |
| HP            | Laptop 15s-fq1xxx           | [d0ac402ed9](https://linux-hardware.org/?probe=d0ac402ed9) | Jan 03, 2023 |
| HP            | Pavilion                    | [466e855af1](https://linux-hardware.org/?probe=466e855af1) | Jan 03, 2023 |
| Lenovo        | ThinkPad X260 20F5005NAU    | [3f68b8438c](https://linux-hardware.org/?probe=3f68b8438c) | Jan 02, 2023 |
| HP            | EliteBook 2760p             | [91741e63eb](https://linux-hardware.org/?probe=91741e63eb) | Jan 01, 2023 |
| HP            | EliteBook 2760p             | [6ac462efda](https://linux-hardware.org/?probe=6ac462efda) | Jan 01, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [cf40d3f30c](https://linux-hardware.org/?probe=cf40d3f30c) | Dec 31, 2022 |
| Apple         | MacBookAir7,2               | [8b84042dc6](https://linux-hardware.org/?probe=8b84042dc6) | Dec 30, 2022 |
| Apple         | MacBookAir7,2               | [dae09ec15f](https://linux-hardware.org/?probe=dae09ec15f) | Dec 30, 2022 |
| Dell          | XPS 15 9570                 | [cc31efb32d](https://linux-hardware.org/?probe=cc31efb32d) | Dec 30, 2022 |
| ASUSTek       | X555UJ                      | [f4ba8643aa](https://linux-hardware.org/?probe=f4ba8643aa) | Dec 30, 2022 |
| AMI           | F3C2                        | [ed7d4a2a13](https://linux-hardware.org/?probe=ed7d4a2a13) | Dec 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1cf63ef1ad](https://linux-hardware.org/?probe=1cf63ef1ad) | Dec 28, 2022 |
| Acer          | Aspire 5742G                | [f58bb411b8](https://linux-hardware.org/?probe=f58bb411b8) | Dec 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [d1f63174e4](https://linux-hardware.org/?probe=d1f63174e4) | Dec 28, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | [70d10e91fb](https://linux-hardware.org/?probe=70d10e91fb) | Dec 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [6eaa690ff2](https://linux-hardware.org/?probe=6eaa690ff2) | Dec 28, 2022 |
| Toshiba       | PORTEGE Z30-C               | [03dad182bb](https://linux-hardware.org/?probe=03dad182bb) | Dec 28, 2022 |
| MSI           | Raider GE77HX 12UGS         | [9f7185ccd7](https://linux-hardware.org/?probe=9f7185ccd7) | Dec 27, 2022 |
| MSI           | GP62M 7REX                  | [f49c90b8dc](https://linux-hardware.org/?probe=f49c90b8dc) | Dec 25, 2022 |
| Dell          | Latitude E6520              | [33a51c934d](https://linux-hardware.org/?probe=33a51c934d) | Dec 25, 2022 |
| MSI           | GS60 6QE                    | [aa2f6b0f24](https://linux-hardware.org/?probe=aa2f6b0f24) | Dec 24, 2022 |
| Toshiba       | Satellite C50D-C            | [5f2debe594](https://linux-hardware.org/?probe=5f2debe594) | Dec 23, 2022 |
| Lenovo        | ThinkPad X260 20F5005NAU    | [5f75bb423d](https://linux-hardware.org/?probe=5f75bb423d) | Dec 23, 2022 |
| Lenovo        | ThinkPad X260 20F5005NAU    | [844f589d20](https://linux-hardware.org/?probe=844f589d20) | Dec 22, 2022 |
| Acer          | Nitro AN515-52              | [4732443b9e](https://linux-hardware.org/?probe=4732443b9e) | Dec 22, 2022 |
| Acer          | Nitro AN515-52              | [354b048898](https://linux-hardware.org/?probe=354b048898) | Dec 21, 2022 |
| HP            | Pavilion dv6                | [8b0f82599c](https://linux-hardware.org/?probe=8b0f82599c) | Dec 20, 2022 |
| HUAWEI        | NBD-WXX9                    | [1fec8c22dc](https://linux-hardware.org/?probe=1fec8c22dc) | Dec 20, 2022 |
| HUAWEI        | NBD-WXX9                    | [b0a4a9919c](https://linux-hardware.org/?probe=b0a4a9919c) | Dec 18, 2022 |
| ASUSTek       | X550LD                      | [2960bdb195](https://linux-hardware.org/?probe=2960bdb195) | Dec 16, 2022 |
| Apple         | MacBookPro14,2              | [702a622854](https://linux-hardware.org/?probe=702a622854) | Dec 14, 2022 |
| Apple         | MacBookAir7,2               | [b1386d66d5](https://linux-hardware.org/?probe=b1386d66d5) | Dec 13, 2022 |
| Kogan         | KAL11C250SB                 | [e7ad1c21ad](https://linux-hardware.org/?probe=e7ad1c21ad) | Dec 13, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [265ba7b252](https://linux-hardware.org/?probe=265ba7b252) | Dec 13, 2022 |
| Dell          | XPS L521X                   | [c69c906797](https://linux-hardware.org/?probe=c69c906797) | Dec 12, 2022 |
| ASUSTek       | K56CB                       | [94b056f1f4](https://linux-hardware.org/?probe=94b056f1f4) | Dec 12, 2022 |
| Acer          | Aspire A515-45              | [26f5bfeb45](https://linux-hardware.org/?probe=26f5bfeb45) | Dec 09, 2022 |
| HP            | Laptop 15-db0xxx            | [b0de030271](https://linux-hardware.org/?probe=b0de030271) | Dec 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [b5f311cc8f](https://linux-hardware.org/?probe=b5f311cc8f) | Dec 07, 2022 |
| Dell          | G15 5511                    | [999ed53283](https://linux-hardware.org/?probe=999ed53283) | Dec 05, 2022 |
| Apple         | MacBookPro15,1              | [36732e2602](https://linux-hardware.org/?probe=36732e2602) | Dec 05, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [c458ba13c3](https://linux-hardware.org/?probe=c458ba13c3) | Dec 05, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [bd9f0dc967](https://linux-hardware.org/?probe=bd9f0dc967) | Dec 05, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [fb96bd56ad](https://linux-hardware.org/?probe=fb96bd56ad) | Dec 04, 2022 |
| Unknown       | Unknown                     | [54c6593c53](https://linux-hardware.org/?probe=54c6593c53) | Dec 03, 2022 |
| Unknown       | Unknown                     | [7668b4d9a2](https://linux-hardware.org/?probe=7668b4d9a2) | Dec 03, 2022 |
| Apple         | MacBookPro8,1               | [af40c4e286](https://linux-hardware.org/?probe=af40c4e286) | Dec 03, 2022 |
| Acer          | ConceptD CN315-71P          | [370356b4a8](https://linux-hardware.org/?probe=370356b4a8) | Dec 02, 2022 |
| Acer          | ConceptD CN315-71P          | [bbdfc25e56](https://linux-hardware.org/?probe=bbdfc25e56) | Dec 02, 2022 |
| Intel Clie... | LAPBC510                    | [e903f5edea](https://linux-hardware.org/?probe=e903f5edea) | Dec 02, 2022 |
| Lenovo        | ThinkPad T420 4236GY3       | [63dd78fcec](https://linux-hardware.org/?probe=63dd78fcec) | Dec 02, 2022 |
| Dell          | XPS 13 9310                 | [ca1fab4db1](https://linux-hardware.org/?probe=ca1fab4db1) | Dec 02, 2022 |
| Dell          | XPS 13 9310                 | [2adab1a5b2](https://linux-hardware.org/?probe=2adab1a5b2) | Dec 02, 2022 |
| AMI           | Intel                       | [3e2e312c6e](https://linux-hardware.org/?probe=3e2e312c6e) | Nov 29, 2022 |
| Razer         | Blade                       | [de6f0ebcad](https://linux-hardware.org/?probe=de6f0ebcad) | Nov 28, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [3433fd5db6](https://linux-hardware.org/?probe=3433fd5db6) | Nov 28, 2022 |
| Apple         | MacBookAir6,2               | [ed4692d2a7](https://linux-hardware.org/?probe=ed4692d2a7) | Nov 28, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [ea6f1fc82e](https://linux-hardware.org/?probe=ea6f1fc82e) | Nov 28, 2022 |
| Dell          | XPS 15 9500                 | [f149afb5d1](https://linux-hardware.org/?probe=f149afb5d1) | Nov 28, 2022 |
| Intel Clie... | LAPBC510                    | [f58ff7b6fa](https://linux-hardware.org/?probe=f58ff7b6fa) | Nov 27, 2022 |
| Dell          | Latitude E7440              | [3709af0366](https://linux-hardware.org/?probe=3709af0366) | Nov 27, 2022 |
| Apple         | MacBookPro15,2              | [446ef54cb5](https://linux-hardware.org/?probe=446ef54cb5) | Nov 26, 2022 |
| Apple         | MacBookAir8,1               | [6656b4e315](https://linux-hardware.org/?probe=6656b4e315) | Nov 26, 2022 |
| Kogan         | KAL11C250SB                 | [9ca4f71bb9](https://linux-hardware.org/?probe=9ca4f71bb9) | Nov 26, 2022 |
| Razer         | Blade Pro                   | [dabfd64904](https://linux-hardware.org/?probe=dabfd64904) | Nov 25, 2022 |
| MSI           | GS60 6QE                    | [80d61ee685](https://linux-hardware.org/?probe=80d61ee685) | Nov 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [16f086de33](https://linux-hardware.org/?probe=16f086de33) | Nov 25, 2022 |
| Acer          | Aspire R3-131T              | [5395a2556c](https://linux-hardware.org/?probe=5395a2556c) | Nov 24, 2022 |
| Acer          | ConceptD CN315-71P          | [db3ccac179](https://linux-hardware.org/?probe=db3ccac179) | Nov 23, 2022 |
| Apple         | MacBookPro5,1               | [62c77a0e63](https://linux-hardware.org/?probe=62c77a0e63) | Nov 23, 2022 |
| Apple         | MacBookPro5,1               | [06c02ff303](https://linux-hardware.org/?probe=06c02ff303) | Nov 21, 2022 |
| Lenovo        | ThinkPad X240 20AMA0LTAU    | [54ce03d1f1](https://linux-hardware.org/?probe=54ce03d1f1) | Nov 20, 2022 |
| Samsung       | RC410/RC510/RC710           | [06a337fda3](https://linux-hardware.org/?probe=06a337fda3) | Nov 20, 2022 |
| Samsung       | RC410/RC510/RC710           | [965d9d2f5c](https://linux-hardware.org/?probe=965d9d2f5c) | Nov 20, 2022 |
| MSI           | GP62M 7REX                  | [2125546b68](https://linux-hardware.org/?probe=2125546b68) | Nov 19, 2022 |
| MSI           | GP62M 7REX                  | [6ea684de8c](https://linux-hardware.org/?probe=6ea684de8c) | Nov 19, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [2cb56b8c63](https://linux-hardware.org/?probe=2cb56b8c63) | Nov 17, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [2d0fb1c5d1](https://linux-hardware.org/?probe=2d0fb1c5d1) | Nov 16, 2022 |
| AMI           | Intel                       | [ac36a02403](https://linux-hardware.org/?probe=ac36a02403) | Nov 16, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [66737bb1cc](https://linux-hardware.org/?probe=66737bb1cc) | Nov 15, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [ccbda507a9](https://linux-hardware.org/?probe=ccbda507a9) | Nov 14, 2022 |
| ASUSTek       | X550CC                      | [d37b8f7bbd](https://linux-hardware.org/?probe=d37b8f7bbd) | Nov 13, 2022 |
| Acer          | ConceptD CN315-71P          | [2d3a3f4ac8](https://linux-hardware.org/?probe=2d3a3f4ac8) | Nov 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [57368a1129](https://linux-hardware.org/?probe=57368a1129) | Nov 12, 2022 |
| Apple         | MacBook9,1                  | [755a70132f](https://linux-hardware.org/?probe=755a70132f) | Nov 12, 2022 |
| Apple         | MacBook9,1                  | [4371465097](https://linux-hardware.org/?probe=4371465097) | Nov 12, 2022 |
| HP            | Pavilion Notebook           | [1d6ae45d45](https://linux-hardware.org/?probe=1d6ae45d45) | Nov 11, 2022 |
| MSI           | GS60 6QE                    | [a571dc503c](https://linux-hardware.org/?probe=a571dc503c) | Nov 11, 2022 |
| Toshiba       | TECRA A40-D                 | [ab2d9e2712](https://linux-hardware.org/?probe=ab2d9e2712) | Nov 11, 2022 |
| Acer          | Aspire A315-22              | [cde0b24cde](https://linux-hardware.org/?probe=cde0b24cde) | Nov 10, 2022 |
| Lenovo        | ThinkPad T420 4180PEM       | [ad4d7f338d](https://linux-hardware.org/?probe=ad4d7f338d) | Nov 09, 2022 |
| HP            | ProBook 640 G1              | [3189f08179](https://linux-hardware.org/?probe=3189f08179) | Nov 09, 2022 |
| HP            | Pavilion Notebook           | [a7de751ce8](https://linux-hardware.org/?probe=a7de751ce8) | Nov 09, 2022 |
| Dell          | XPS 13 9310                 | [5f358af327](https://linux-hardware.org/?probe=5f358af327) | Nov 08, 2022 |
| MSI           | GS60 6QE                    | [c843b1ff5e](https://linux-hardware.org/?probe=c843b1ff5e) | Nov 08, 2022 |
| ASUSTek       | K53E                        | [07d6d01b99](https://linux-hardware.org/?probe=07d6d01b99) | Nov 06, 2022 |
| Dell          | Latitude E6430              | [fcd82d5966](https://linux-hardware.org/?probe=fcd82d5966) | Nov 06, 2022 |
| Toshiba       | Satellite L500              | [0d6bb9cde0](https://linux-hardware.org/?probe=0d6bb9cde0) | Nov 05, 2022 |
| Toshiba       | Satellite L500              | [3d7692d178](https://linux-hardware.org/?probe=3d7692d178) | Nov 05, 2022 |
| MSI           | Katana GF76 12UC            | [3cb05bdb95](https://linux-hardware.org/?probe=3cb05bdb95) | Nov 04, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [c39a19fa2f](https://linux-hardware.org/?probe=c39a19fa2f) | Nov 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [cc28dc5c8b](https://linux-hardware.org/?probe=cc28dc5c8b) | Nov 04, 2022 |
| HP            | Pavilion Notebook           | [a8f3260004](https://linux-hardware.org/?probe=a8f3260004) | Nov 04, 2022 |
| HP            | Pavilion Notebook           | [e24f2a2f57](https://linux-hardware.org/?probe=e24f2a2f57) | Nov 03, 2022 |
| ASUSTek       | 1005HA                      | [1d386943d6](https://linux-hardware.org/?probe=1d386943d6) | Nov 02, 2022 |
| HP            | Pavilion Notebook           | [9fef9a6a8a](https://linux-hardware.org/?probe=9fef9a6a8a) | Nov 02, 2022 |
| Cube          | i18-BL                      | [725100a829](https://linux-hardware.org/?probe=725100a829) | Nov 02, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [fefe8e5d04](https://linux-hardware.org/?probe=fefe8e5d04) | Nov 01, 2022 |
| HP            | Notebook                    | [27d097b522](https://linux-hardware.org/?probe=27d097b522) | Nov 01, 2022 |
| Acer          | Aspire 3000                 | [02693e03ca](https://linux-hardware.org/?probe=02693e03ca) | Nov 01, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [df949b6e10](https://linux-hardware.org/?probe=df949b6e10) | Nov 01, 2022 |
| ASUSTek       | X501A                       | [d5a34df414](https://linux-hardware.org/?probe=d5a34df414) | Nov 01, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [c3ea4065c4](https://linux-hardware.org/?probe=c3ea4065c4) | Oct 29, 2022 |
| ASUSTek       | U50Vg                       | [5f2997ec95](https://linux-hardware.org/?probe=5f2997ec95) | Oct 28, 2022 |
| HP            | ProBook 640 G1              | [b096155d39](https://linux-hardware.org/?probe=b096155d39) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [73d5bfb13a](https://linux-hardware.org/?probe=73d5bfb13a) | Oct 27, 2022 |
| Apple         | MacBookAir6,2               | [cca0d420fe](https://linux-hardware.org/?probe=cca0d420fe) | Oct 27, 2022 |
| HP            | G71                         | [3223e2fcc8](https://linux-hardware.org/?probe=3223e2fcc8) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [7290786792](https://linux-hardware.org/?probe=7290786792) | Oct 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [4ffd604fea](https://linux-hardware.org/?probe=4ffd604fea) | Oct 25, 2022 |
| Apple         | MacBookAir7,2               | [6f72d6443c](https://linux-hardware.org/?probe=6f72d6443c) | Oct 23, 2022 |
| Apple         | MacBookAir6,2               | [edd13bcc76](https://linux-hardware.org/?probe=edd13bcc76) | Oct 23, 2022 |
| Notebook      | W650EH                      | [6bb1a8b1f1](https://linux-hardware.org/?probe=6bb1a8b1f1) | Oct 23, 2022 |
| Purism        | Librem 13 v2                | [5296ed1e19](https://linux-hardware.org/?probe=5296ed1e19) | Oct 21, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [cb901021a7](https://linux-hardware.org/?probe=cb901021a7) | Oct 21, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [63751816bc](https://linux-hardware.org/?probe=63751816bc) | Oct 21, 2022 |
| HP            | Pavilion Notebook           | [31d7e67080](https://linux-hardware.org/?probe=31d7e67080) | Oct 21, 2022 |
| Acer          | Aspire 5600                 | [202a7e570e](https://linux-hardware.org/?probe=202a7e570e) | Oct 20, 2022 |
| Lenovo        | ThinkPad T410 2522PT3       | [2cd92a7da8](https://linux-hardware.org/?probe=2cd92a7da8) | Oct 19, 2022 |
| HUAWEI        | MACHD-WXX9                  | [5086e64fed](https://linux-hardware.org/?probe=5086e64fed) | Oct 19, 2022 |
| Dell          | Inspiron M5010              | [026a7a8cd3](https://linux-hardware.org/?probe=026a7a8cd3) | Oct 18, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [926d661756](https://linux-hardware.org/?probe=926d661756) | Oct 17, 2022 |
| HP            | G71                         | [46b6033e1e](https://linux-hardware.org/?probe=46b6033e1e) | Oct 17, 2022 |
| HP            | Pavilion Notebook           | [50c44df4fb](https://linux-hardware.org/?probe=50c44df4fb) | Oct 17, 2022 |
| Dell          | Inspiron 1545               | [d9928a4ee9](https://linux-hardware.org/?probe=d9928a4ee9) | Oct 16, 2022 |
| System76      | Galago Pro                  | [ec92c5a918](https://linux-hardware.org/?probe=ec92c5a918) | Oct 14, 2022 |
| HUAWEI        | MACHD-WXX9                  | [5f0c4b3acb](https://linux-hardware.org/?probe=5f0c4b3acb) | Oct 13, 2022 |
| Apple         | MacBookPro15,2              | [705e4f406a](https://linux-hardware.org/?probe=705e4f406a) | Oct 13, 2022 |
| HP            | EliteBook 8540p             | [cd65876f22](https://linux-hardware.org/?probe=cd65876f22) | Oct 12, 2022 |
| Apple         | MacBookPro15,2              | [56fc798c2e](https://linux-hardware.org/?probe=56fc798c2e) | Oct 11, 2022 |
| Acer          | Aspire A315-22              | [07870a3cde](https://linux-hardware.org/?probe=07870a3cde) | Oct 11, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [1ae81569dd](https://linux-hardware.org/?probe=1ae81569dd) | Oct 11, 2022 |
| Dell          | Inspiron 16 5620            | [72151cd0e8](https://linux-hardware.org/?probe=72151cd0e8) | Oct 10, 2022 |
| Gigabyte      | P34V7                       | [c1423fce9e](https://linux-hardware.org/?probe=c1423fce9e) | Oct 10, 2022 |
| System76      | Galago Pro                  | [28e36afa26](https://linux-hardware.org/?probe=28e36afa26) | Oct 10, 2022 |
| HP            | ProBook 470 G5              | [a7b96649da](https://linux-hardware.org/?probe=a7b96649da) | Oct 09, 2022 |
| Panasonic     | CF-19-8                     | [439e2c8122](https://linux-hardware.org/?probe=439e2c8122) | Oct 09, 2022 |
| Panasonic     | CF-19-8                     | [bc5820629b](https://linux-hardware.org/?probe=bc5820629b) | Oct 09, 2022 |
| Dell          | XPS 15 9510                 | [6b62586012](https://linux-hardware.org/?probe=6b62586012) | Oct 09, 2022 |
| Apple         | MacBookAir7,2               | [e26911cff6](https://linux-hardware.org/?probe=e26911cff6) | Oct 08, 2022 |
| HP            | Presario V4000 (EQ608PA#... | [f462d80b2a](https://linux-hardware.org/?probe=f462d80b2a) | Oct 06, 2022 |
| Dell          | XPS 15 9510                 | [99f16967b2](https://linux-hardware.org/?probe=99f16967b2) | Oct 05, 2022 |
| Gigabyte      | AORUS 7 SB                  | [444224d1e0](https://linux-hardware.org/?probe=444224d1e0) | Oct 04, 2022 |
| Acer          | TravelMate 8572T            | [6abaaf4aa6](https://linux-hardware.org/?probe=6abaaf4aa6) | Oct 03, 2022 |
| Dell          | Inspiron 15 7510            | [521636075a](https://linux-hardware.org/?probe=521636075a) | Oct 02, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [c555fbbf75](https://linux-hardware.org/?probe=c555fbbf75) | Oct 01, 2022 |
| HP            | ProBook 450 G4              | [9c6340e585](https://linux-hardware.org/?probe=9c6340e585) | Oct 01, 2022 |
| Toshiba       | PORTEGE Z10t-A              | [1aa913c010](https://linux-hardware.org/?probe=1aa913c010) | Oct 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [025a55eab7](https://linux-hardware.org/?probe=025a55eab7) | Sep 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [875b1df312](https://linux-hardware.org/?probe=875b1df312) | Sep 30, 2022 |
| Acer          | TravelMate 8572T            | [927bf01e34](https://linux-hardware.org/?probe=927bf01e34) | Sep 30, 2022 |
| Gigabyte      | AORUS 17 YE5                | [54b271c3fd](https://linux-hardware.org/?probe=54b271c3fd) | Sep 30, 2022 |
| Acer          | Aspire 5742G                | [354a9c2bc2](https://linux-hardware.org/?probe=354a9c2bc2) | Sep 29, 2022 |
| Dell          | Inspiron 7347               | [ac3079df8c](https://linux-hardware.org/?probe=ac3079df8c) | Sep 29, 2022 |
| Dell          | Inspiron 7347               | [144cad649c](https://linux-hardware.org/?probe=144cad649c) | Sep 29, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [fbc4f29134](https://linux-hardware.org/?probe=fbc4f29134) | Sep 28, 2022 |
| HP            | EliteBook 8770w             | [e5ec559da4](https://linux-hardware.org/?probe=e5ec559da4) | Sep 28, 2022 |
| Dell          | Latitude E7450              | [daeb4afb69](https://linux-hardware.org/?probe=daeb4afb69) | Sep 28, 2022 |
| Gigabyte      | P34V7                       | [27b9651432](https://linux-hardware.org/?probe=27b9651432) | Sep 27, 2022 |
| ASUSTek       | TUF Gaming FX505DV          | [2154b531c9](https://linux-hardware.org/?probe=2154b531c9) | Sep 26, 2022 |
| System76      | Galago Pro                  | [6b2de473b7](https://linux-hardware.org/?probe=6b2de473b7) | Sep 26, 2022 |
| Gigabyte      | AORUS 7 SB                  | [3e8222ad7c](https://linux-hardware.org/?probe=3e8222ad7c) | Sep 26, 2022 |
| ASUSTek       | TUF Gaming FX505DV          | [6b3be4af70](https://linux-hardware.org/?probe=6b3be4af70) | Sep 26, 2022 |
| Dell          | G15 5511                    | [f960f38940](https://linux-hardware.org/?probe=f960f38940) | Sep 26, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [6c0c9c0037](https://linux-hardware.org/?probe=6c0c9c0037) | Sep 25, 2022 |
| Apple         | MacBookAir7,2               | [93dd525100](https://linux-hardware.org/?probe=93dd525100) | Sep 25, 2022 |
| HP            | Pavilion dv6                | [ae43d0bbce](https://linux-hardware.org/?probe=ae43d0bbce) | Sep 24, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [24b2810c64](https://linux-hardware.org/?probe=24b2810c64) | Sep 24, 2022 |
| Acer          | TMP645-M                    | [83b27c389c](https://linux-hardware.org/?probe=83b27c389c) | Sep 23, 2022 |
| Dell          | Precision 7760              | [f47fe0314b](https://linux-hardware.org/?probe=f47fe0314b) | Sep 23, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [accc831d30](https://linux-hardware.org/?probe=accc831d30) | Sep 23, 2022 |
| Lenovo        | ThinkPad E595 20NFA000AU    | [a01352810a](https://linux-hardware.org/?probe=a01352810a) | Sep 22, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen2... | [87a3d977b1](https://linux-hardware.org/?probe=87a3d977b1) | Sep 22, 2022 |
| Apple         | MacBookPro8,1               | [d97b8fc0ed](https://linux-hardware.org/?probe=d97b8fc0ed) | Sep 21, 2022 |
| Apple         | MacBookPro10,2              | [ecc3b7e71d](https://linux-hardware.org/?probe=ecc3b7e71d) | Sep 19, 2022 |
| ASUSTek       | 1005HA                      | [3b5d6a5b1d](https://linux-hardware.org/?probe=3b5d6a5b1d) | Sep 18, 2022 |
| ASUSTek       | 1005HA                      | [3b1ce0471e](https://linux-hardware.org/?probe=3b1ce0471e) | Sep 18, 2022 |
| Lenovo        | V310-15ISK 80SY             | [fbd66d36f4](https://linux-hardware.org/?probe=fbd66d36f4) | Sep 14, 2022 |
| Apple         | MacBookAir7,2               | [03ba2808d7](https://linux-hardware.org/?probe=03ba2808d7) | Sep 13, 2022 |
| Acer          | Aspire A315-42              | [6121dfd67d](https://linux-hardware.org/?probe=6121dfd67d) | Sep 13, 2022 |
| HP            | ENVY 15                     | [fdb07294df](https://linux-hardware.org/?probe=fdb07294df) | Sep 13, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [d477c1084d](https://linux-hardware.org/?probe=d477c1084d) | Sep 10, 2022 |
| Acer          | Aspire A315-22              | [82058771f7](https://linux-hardware.org/?probe=82058771f7) | Sep 09, 2022 |
| Dell          | Latitude E7470              | [4a2f647549](https://linux-hardware.org/?probe=4a2f647549) | Sep 08, 2022 |
| Acer          | Aspire A315-22              | [49d54ac5c5](https://linux-hardware.org/?probe=49d54ac5c5) | Sep 07, 2022 |
| ASUSTek       | K55VD                       | [c1ca471555](https://linux-hardware.org/?probe=c1ca471555) | Sep 06, 2022 |
| HP            | Pavilion dv6500             | [c37bace401](https://linux-hardware.org/?probe=c37bace401) | Sep 05, 2022 |
| Dell          | XPS 13 9350                 | [dc37712dfc](https://linux-hardware.org/?probe=dc37712dfc) | Sep 02, 2022 |
| Lenovo        | Z50-70 20354                | [8ac8531142](https://linux-hardware.org/?probe=8ac8531142) | Sep 01, 2022 |
| Toshiba       | Satellite C850              | [6cf6d8fca8](https://linux-hardware.org/?probe=6cf6d8fca8) | Sep 01, 2022 |
| ASUSTek       | X550CC                      | [21f3eb8b1d](https://linux-hardware.org/?probe=21f3eb8b1d) | Sep 01, 2022 |
| Lenovo        | Z50-70 20354                | [6e245e4c63](https://linux-hardware.org/?probe=6e245e4c63) | Sep 01, 2022 |
| HP            | Notebook                    | [ee135c3930](https://linux-hardware.org/?probe=ee135c3930) | Aug 31, 2022 |
| Toshiba       | Satellite C850              | [5d7cb36794](https://linux-hardware.org/?probe=5d7cb36794) | Aug 31, 2022 |
| HP            | EliteBook 830 G6            | [897046248f](https://linux-hardware.org/?probe=897046248f) | Aug 30, 2022 |
| Lenovo        | V14-ADA 82C6                | [ce25a77e25](https://linux-hardware.org/?probe=ce25a77e25) | Aug 29, 2022 |
| HP            | EW7-I7D22875GR1             | [307b75624e](https://linux-hardware.org/?probe=307b75624e) | Aug 29, 2022 |
| Toshiba       | Satellite L850              | [fe1480794c](https://linux-hardware.org/?probe=fe1480794c) | Aug 29, 2022 |
| IT Channel... | NH5xAx                      | [66573b4b48](https://linux-hardware.org/?probe=66573b4b48) | Aug 28, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [f30320f76e](https://linux-hardware.org/?probe=f30320f76e) | Aug 27, 2022 |
| Acer          | Aspire V5-531               | [75b841b0b8](https://linux-hardware.org/?probe=75b841b0b8) | Aug 26, 2022 |
| HP            | Laptop 15-da1xxx            | [51e23209a4](https://linux-hardware.org/?probe=51e23209a4) | Aug 26, 2022 |
| Dell          | Latitude 5300               | [f336b3aeaf](https://linux-hardware.org/?probe=f336b3aeaf) | Aug 26, 2022 |
| Lenovo        | Yoga S940-14IWL 81Q7        | [416e5db831](https://linux-hardware.org/?probe=416e5db831) | Aug 26, 2022 |
| Acer          | Aspire V5-531               | [4ae228e219](https://linux-hardware.org/?probe=4ae228e219) | Aug 25, 2022 |
| Dell          | XPS 13 7390                 | [d609bf3253](https://linux-hardware.org/?probe=d609bf3253) | Aug 24, 2022 |
| Alienware     | 15 R4                       | [f53260e0c2](https://linux-hardware.org/?probe=f53260e0c2) | Aug 23, 2022 |
| Dell          | Inspiron 5770               | [49314a1dfe](https://linux-hardware.org/?probe=49314a1dfe) | Aug 23, 2022 |
| Apple         | MacBook9,1                  | [a6726b8439](https://linux-hardware.org/?probe=a6726b8439) | Aug 22, 2022 |
| Apple         | MacBook9,1                  | [aff9259c2c](https://linux-hardware.org/?probe=aff9259c2c) | Aug 22, 2022 |
| Samsung       | 550P5C/550P7C               | [75f94f8fa5](https://linux-hardware.org/?probe=75f94f8fa5) | Aug 21, 2022 |
| Samsung       | 550P5C/550P7C               | [c369daf6b0](https://linux-hardware.org/?probe=c369daf6b0) | Aug 21, 2022 |
| ASUSTek       | X756UAK                     | [6db3b2a7bc](https://linux-hardware.org/?probe=6db3b2a7bc) | Aug 20, 2022 |
| Dell          | G3 3779                     | [a2b721ca15](https://linux-hardware.org/?probe=a2b721ca15) | Aug 19, 2022 |
| Dell          | XPS 15 9530                 | [9e6a3e80b4](https://linux-hardware.org/?probe=9e6a3e80b4) | Aug 19, 2022 |
| Dell          | Inspiron M5010              | [266f9fc41d](https://linux-hardware.org/?probe=266f9fc41d) | Aug 19, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e500790878](https://linux-hardware.org/?probe=e500790878) | Aug 18, 2022 |
| Lenovo        | ThinkPad T480s 20L70044A... | [f90559618b](https://linux-hardware.org/?probe=f90559618b) | Aug 17, 2022 |
| HP            | EliteBook 8460p             | [26f646cca0](https://linux-hardware.org/?probe=26f646cca0) | Aug 17, 2022 |
| HP            | EliteBook 8460p             | [98b5311ef6](https://linux-hardware.org/?probe=98b5311ef6) | Aug 17, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | [e32eeecfaa](https://linux-hardware.org/?probe=e32eeecfaa) | Aug 15, 2022 |
| Apple         | MacBookAir6,2               | [2c210a5825](https://linux-hardware.org/?probe=2c210a5825) | Aug 14, 2022 |
| Toshiba       | Satellite L500              | [0d58c17039](https://linux-hardware.org/?probe=0d58c17039) | Aug 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [26c131aca1](https://linux-hardware.org/?probe=26c131aca1) | Aug 13, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | [662f0801b7](https://linux-hardware.org/?probe=662f0801b7) | Aug 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [166edbd7db](https://linux-hardware.org/?probe=166edbd7db) | Aug 12, 2022 |
| Dell          | Latitude 6430U              | [d21ca8c2e6](https://linux-hardware.org/?probe=d21ca8c2e6) | Aug 11, 2022 |
| HP            | ProBook 430 G5              | [72a09e7b69](https://linux-hardware.org/?probe=72a09e7b69) | Aug 05, 2022 |
| Lenovo        | XiaoXinPro 16 ARH7 82SN     | [abaec227ae](https://linux-hardware.org/?probe=abaec227ae) | Aug 05, 2022 |
| Lenovo        | XiaoXinPro 16 ARH7 82SN     | [a1effa04c3](https://linux-hardware.org/?probe=a1effa04c3) | Aug 05, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [209cd4bc66](https://linux-hardware.org/?probe=209cd4bc66) | Aug 05, 2022 |
| Acer          | Nitro AN515-52              | [8b737740c3](https://linux-hardware.org/?probe=8b737740c3) | Aug 05, 2022 |
| Acer          | Aspire A515-55              | [3ef0714d78](https://linux-hardware.org/?probe=3ef0714d78) | Aug 04, 2022 |
| Toshiba       | Satellite Pro L670          | [302749341d](https://linux-hardware.org/?probe=302749341d) | Aug 03, 2022 |
| Dell          | XPS 9320                    | [9b24b29553](https://linux-hardware.org/?probe=9b24b29553) | Aug 03, 2022 |
| Toshiba       | Satellite Pro L670          | [e6189ba78c](https://linux-hardware.org/?probe=e6189ba78c) | Aug 02, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 8... | [a67d881d6f](https://linux-hardware.org/?probe=a67d881d6f) | Aug 02, 2022 |
| HP            | EliteBook 2570p             | [b352b7e051](https://linux-hardware.org/?probe=b352b7e051) | Aug 02, 2022 |
| Apple         | MacBook9,1                  | [77687a9bac](https://linux-hardware.org/?probe=77687a9bac) | Aug 02, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [370b872aa5](https://linux-hardware.org/?probe=370b872aa5) | Aug 01, 2022 |
| Acer          | ConceptD CN315-71P          | [c7ed484a1f](https://linux-hardware.org/?probe=c7ed484a1f) | Jul 30, 2022 |
| Dell          | Inspiron M5010              | [bd4cf45b33](https://linux-hardware.org/?probe=bd4cf45b33) | Jul 30, 2022 |
| Acer          | Aspire 5742G                | [e42501aacb](https://linux-hardware.org/?probe=e42501aacb) | Jul 28, 2022 |
| ASUSTek       | X555YA                      | [ddd00fbeea](https://linux-hardware.org/?probe=ddd00fbeea) | Jul 28, 2022 |
| Dell          | Latitude E7250              | [26a8591f1d](https://linux-hardware.org/?probe=26a8591f1d) | Jul 27, 2022 |
| HP            | Laptop 17-cp0xxx            | [761563e485](https://linux-hardware.org/?probe=761563e485) | Jul 27, 2022 |
| Apple         | MacBookAir7,2               | [5e7b9f2b14](https://linux-hardware.org/?probe=5e7b9f2b14) | Jul 26, 2022 |
| Dell          | Latitude 3400               | [3412e8deac](https://linux-hardware.org/?probe=3412e8deac) | Jul 26, 2022 |
| Lenovo        | G570 4334                   | [e4c223e83e](https://linux-hardware.org/?probe=e4c223e83e) | Jul 25, 2022 |
| Apple         | MacBookAir6,1               | [ede7f6cdae](https://linux-hardware.org/?probe=ede7f6cdae) | Jul 23, 2022 |
| Acer          | Nitro AN515-55              | [85f2ffe45a](https://linux-hardware.org/?probe=85f2ffe45a) | Jul 22, 2022 |
| Acer          | ConceptD CN315-71P          | [2723b19c18](https://linux-hardware.org/?probe=2723b19c18) | Jul 22, 2022 |
| Google        | Peppy                       | [3bfdae8e5e](https://linux-hardware.org/?probe=3bfdae8e5e) | Jul 21, 2022 |
| Acer          | Aspire One 753              | [eff74923d7](https://linux-hardware.org/?probe=eff74923d7) | Jul 21, 2022 |
| Dell          | Latitude 5430               | [f02c4072c1](https://linux-hardware.org/?probe=f02c4072c1) | Jul 21, 2022 |
| Acer          | Aspire R3-131T              | [c3722806fe](https://linux-hardware.org/?probe=c3722806fe) | Jul 21, 2022 |
| Apple         | MacBookPro9,2               | [add1e46d7e](https://linux-hardware.org/?probe=add1e46d7e) | Jul 20, 2022 |
| Dell          | Inspiron MM061              | [2360c35ac1](https://linux-hardware.org/?probe=2360c35ac1) | Jul 20, 2022 |
| Dell          | Inspiron MM061              | [5cb9487776](https://linux-hardware.org/?probe=5cb9487776) | Jul 20, 2022 |
| Dell          | Inspiron 1545               | [b0e3b75c3b](https://linux-hardware.org/?probe=b0e3b75c3b) | Jul 19, 2022 |
| Acer          | TravelMate 8572T            | [54e7b50fc7](https://linux-hardware.org/?probe=54e7b50fc7) | Jul 18, 2022 |
| Alienware     | x17 R1                      | [9fc2d6416d](https://linux-hardware.org/?probe=9fc2d6416d) | Jul 16, 2022 |
| Apple         | MacBookAir7,2               | [a1a565d211](https://linux-hardware.org/?probe=a1a565d211) | Jul 16, 2022 |
| HP            | Spectre 13-SMB Pro Ultra... | [5fd8a1dcf4](https://linux-hardware.org/?probe=5fd8a1dcf4) | Jul 15, 2022 |
| Acer          | ConceptD CN315-71P          | [de83d4ef43](https://linux-hardware.org/?probe=de83d4ef43) | Jul 15, 2022 |
| Acer          | ConceptD CN315-71P          | [01e6c30eff](https://linux-hardware.org/?probe=01e6c30eff) | Jul 15, 2022 |
| Dell          | Inspiron 16 Plus 7620       | [73be4f7864](https://linux-hardware.org/?probe=73be4f7864) | Jul 14, 2022 |
| Acer          | Nitro AN515-56              | [2418745195](https://linux-hardware.org/?probe=2418745195) | Jul 14, 2022 |
| Dell          | Inspiron M5010              | [56be64f444](https://linux-hardware.org/?probe=56be64f444) | Jul 14, 2022 |
| ASUSTek       | GL702ZC                     | [755f571a3e](https://linux-hardware.org/?probe=755f571a3e) | Jul 14, 2022 |
| Dell          | XPS 13 9360                 | [ef3bc84295](https://linux-hardware.org/?probe=ef3bc84295) | Jul 13, 2022 |
| Acer          | Aspire R3-131T              | [4126a95603](https://linux-hardware.org/?probe=4126a95603) | Jul 13, 2022 |
| Apple         | MacBook9,1                  | [0ce6078768](https://linux-hardware.org/?probe=0ce6078768) | Jul 12, 2022 |
| Apple         | MacBookPro10,2              | [facbace782](https://linux-hardware.org/?probe=facbace782) | Jul 12, 2022 |
| Acer          | Aspire 1830T                | [d2ff08ade8](https://linux-hardware.org/?probe=d2ff08ade8) | Jul 10, 2022 |
| HP            | EliteBook 8470p             | [c048bb9697](https://linux-hardware.org/?probe=c048bb9697) | Jul 09, 2022 |
| Apple         | MacBookPro9,2               | [663a6c9413](https://linux-hardware.org/?probe=663a6c9413) | Jul 08, 2022 |
| Acer          | Aspire R3-131T              | [749a597089](https://linux-hardware.org/?probe=749a597089) | Jul 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | [e34a9c3166](https://linux-hardware.org/?probe=e34a9c3166) | Jul 08, 2022 |
| HP            | EliteBook 850 G1            | [1a2485b399](https://linux-hardware.org/?probe=1a2485b399) | Jul 06, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [ce6d3ec137](https://linux-hardware.org/?probe=ce6d3ec137) | Jul 06, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [e24a6dd845](https://linux-hardware.org/?probe=e24a6dd845) | Jul 05, 2022 |
| HP            | EliteBook 840 G6            | [d6dccd6ed7](https://linux-hardware.org/?probe=d6dccd6ed7) | Jul 05, 2022 |
| HUAWEI        | KLVD-WXX9                   | [422a12c217](https://linux-hardware.org/?probe=422a12c217) | Jul 05, 2022 |
| HP            | Pavilion g6                 | [0cd693879d](https://linux-hardware.org/?probe=0cd693879d) | Jul 05, 2022 |
| Acer          | ConceptD CN315-71P          | [76d6073818](https://linux-hardware.org/?probe=76d6073818) | Jul 05, 2022 |
| Dell          | Precision M4700             | [48cbbf8dd2](https://linux-hardware.org/?probe=48cbbf8dd2) | Jul 05, 2022 |
| Acer          | Aspire R3-131T              | [748f42be21](https://linux-hardware.org/?probe=748f42be21) | Jul 05, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Australia/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 201       | 11.13%  |
| Ubuntu 22.04       | 90        | 4.98%   |
| Ubuntu 18.04       | 82        | 4.54%   |
| Pop!_OS 22.04      | 69        | 3.82%   |
| Arch Rolling       | 40        | 2.21%   |
| Debian 11          | 38        | 2.1%    |
| Zorin 16           | 32        | 1.77%   |
| KDE neon 20.04     | 31        | 1.72%   |
| Linux Mint 20.2    | 30        | 1.66%   |
| Fedora 36          | 29        | 1.61%   |
| Linux Mint 20.3    | 28        | 1.55%   |
| Pop!_OS 21.04      | 27        | 1.5%    |
| Fedora 38          | 27        | 1.5%    |
| Pop!_OS 20.04      | 25        | 1.38%   |
| OpenMandriva 4.3   | 25        | 1.38%   |
| Fedora 37          | 25        | 1.38%   |
| Manjaro            | 24        | 1.33%   |
| Arch               | 24        | 1.33%   |
| ArcoLinux Rolling  | 23        | 1.27%   |
| Linux Mint 20      | 22        | 1.22%   |
| Ubuntu 20.10       | 21        | 1.16%   |
| OpenMandriva 4.2   | 20        | 1.11%   |
| Linux Mint 21.1    | 20        | 1.11%   |
| Linux Mint 20.1    | 20        | 1.11%   |
| Pop!_OS 20.10      | 19        | 1.05%   |
| Debian 12          | 19        | 1.05%   |
| Ubuntu 23.04       | 18        | 1%      |
| Ubuntu 21.10       | 18        | 1%      |
| Ubuntu 19.04       | 18        | 1%      |
| Ubuntu 19.10       | 17        | 0.94%   |
| Linux Mint 21.2    | 17        | 0.94%   |
| Zorin 15           | 16        | 0.89%   |
| Fedora 33          | 16        | 0.89%   |
| Fedora 39          | 15        | 0.83%   |
| Fedora 35          | 15        | 0.83%   |
| Ubuntu 21.04       | 14        | 0.78%   |
| KDE neon 22.04     | 14        | 0.78%   |
| Xubuntu 18.04      | 13        | 0.72%   |
| Ubuntu 22.10       | 13        | 0.72%   |
| OpenMandriva 23.03 | 13        | 0.72%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 476       | 28.18%  |
| Linux Mint    | 159       | 9.41%   |
| Pop!_OS       | 142       | 8.41%   |
| Fedora        | 135       | 7.99%   |
| OpenMandriva  | 92        | 5.45%   |
| Debian        | 75        | 4.44%   |
| Arch          | 62        | 3.67%   |
| Zorin         | 57        | 3.37%   |
| Manjaro       | 52        | 3.08%   |
| KDE neon      | 48        | 2.84%   |
| Kubuntu       | 39        | 2.31%   |
| Xubuntu       | 36        | 2.13%   |
| Kali          | 31        | 1.84%   |
| Elementary    | 25        | 1.48%   |
| ArcoLinux     | 23        | 1.36%   |
| Gentoo        | 17        | 1.01%   |
| openSUSE      | 15        | 0.89%   |
| SteamOS       | 14        | 0.83%   |
| Clear Linux   | 14        | 0.83%   |
| MX            | 12        | 0.71%   |
| Lubuntu       | 12        | 0.71%   |
| Endless       | 12        | 0.71%   |
| Ubuntu Unity  | 11        | 0.65%   |
| EndeavourOS   | 11        | 0.65%   |
| ROSA          | 10        | 0.59%   |
| LMDE          | 10        | 0.59%   |
| Ubuntu MATE   | 9         | 0.53%   |
| Parrot        | 8         | 0.47%   |
| Ubuntu Budgie | 6         | 0.36%   |
| LinuxFX       | 6         | 0.36%   |
| BlackPanther  | 6         | 0.36%   |
| Xero          | 4         | 0.24%   |
| Reborn OS     | 4         | 0.24%   |
| Nobara        | 4         | 0.24%   |
| TUXEDO OS     | 3         | 0.18%   |
| Solus         | 3         | 0.18%   |
| Oracle Linux  | 3         | 0.18%   |
| Void Linux    | 2         | 0.12%   |
| RHEL          | 2         | 0.12%   |
| PureOS        | 2         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 33        | 1.63%   |
| 5.16.7-desktop-1omv4003  | 24        | 1.19%   |
| 5.10.14-desktop-1omv4002 | 20        | 0.99%   |
| 5.4.0-58-generic         | 18        | 0.89%   |
| 5.15.0-56-generic        | 16        | 0.79%   |
| 5.4.0-26-generic         | 15        | 0.74%   |
| 5.4.0-40-generic         | 14        | 0.69%   |
| 5.11.0-7620-generic      | 14        | 0.69%   |
| 6.2.6-desktop-1omv2390   | 13        | 0.64%   |
| 6.2.6-76060206-generic   | 13        | 0.64%   |
| 5.4.0-29-generic         | 13        | 0.64%   |
| 5.4.0-48-generic         | 12        | 0.59%   |
| 5.17.5-76051705-generic  | 12        | 0.59%   |
| 5.15.0-58-generic        | 12        | 0.59%   |
| 5.11.0-38-generic        | 12        | 0.59%   |
| 6.2.0-20-generic         | 11        | 0.54%   |
| 5.11.0-37-generic        | 11        | 0.54%   |
| 5.11.0-27-generic        | 11        | 0.54%   |
| 6.1.1-desktop-1omv2290   | 10        | 0.5%    |
| 5.4.0-52-generic         | 10        | 0.5%    |
| 6.2.0-26-generic         | 9         | 0.45%   |
| 5.8.0-63-generic         | 9         | 0.45%   |
| 5.4.0-81-generic         | 9         | 0.45%   |
| 5.4.0-74-generic         | 9         | 0.45%   |
| 5.3.0-40-generic         | 9         | 0.45%   |
| 6.5.0-14-generic         | 8         | 0.4%    |
| 5.8.0-7630-generic       | 8         | 0.4%    |
| 5.8.0-59-generic         | 8         | 0.4%    |
| 5.4.0-7634-generic       | 8         | 0.4%    |
| 5.4.0-65-generic         | 8         | 0.4%    |
| 5.4.0-54-generic         | 8         | 0.4%    |
| 5.3.0-28-generic         | 8         | 0.4%    |
| 5.19.0-46-generic        | 8         | 0.4%    |
| 5.19.0-38-generic        | 8         | 0.4%    |
| 5.15.0-52-generic        | 8         | 0.4%    |
| 5.15.0-46-generic        | 8         | 0.4%    |
| 5.13.0-7620-generic      | 8         | 0.4%    |
| 5.13.0-40-generic        | 8         | 0.4%    |
| 5.11.0-40-generic        | 8         | 0.4%    |
| 5.0.0-13-generic         | 8         | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 272       | 14.45%  |
| 5.15.0  | 139       | 7.39%   |
| 5.11.0  | 101       | 5.37%   |
| 5.13.0  | 85        | 4.52%   |
| 5.8.0   | 84        | 4.46%   |
| 4.15.0  | 70        | 3.72%   |
| 6.2.0   | 58        | 3.08%   |
| 5.19.0  | 57        | 3.03%   |
| 5.3.0   | 52        | 2.76%   |
| 5.10.0  | 51        | 2.71%   |
| 5.0.0   | 41        | 2.18%   |
| 4.18.0  | 31        | 1.65%   |
| 6.5.0   | 28        | 1.49%   |
| 6.2.6   | 26        | 1.38%   |
| 6.1.0   | 25        | 1.33%   |
| 5.16.7  | 25        | 1.33%   |
| 5.10.14 | 20        | 1.06%   |
| 5.17.5  | 18        | 0.96%   |
| 6.1.1   | 14        | 0.74%   |
| 6.0.0   | 14        | 0.74%   |
| 6.0.12  | 11        | 0.58%   |
| 5.18.0  | 11        | 0.58%   |
| 4.19.0  | 11        | 0.58%   |
| 6.5.6   | 10        | 0.53%   |
| 6.4.11  | 9         | 0.48%   |
| 6.6.10  | 8         | 0.43%   |
| 5.18.10 | 8         | 0.43%   |
| 6.5.5   | 7         | 0.37%   |
| 6.4.6   | 7         | 0.37%   |
| 6.0.9   | 7         | 0.37%   |
| 6.0.7   | 7         | 0.37%   |
| 5.14.0  | 7         | 0.37%   |
| 6.6.6   | 6         | 0.32%   |
| 6.4.10  | 6         | 0.32%   |
| 6.4.0   | 6         | 0.32%   |
| 5.18.12 | 6         | 0.32%   |
| 5.17.15 | 6         | 0.32%   |
| 6.2.9   | 5         | 0.27%   |
| 6.1.52  | 5         | 0.27%   |
| 6.1.11  | 5         | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 296       | 16.04%  |
| 5.15    | 178       | 9.65%   |
| 5.11    | 115       | 6.23%   |
| 6.2     | 103       | 5.58%   |
| 5.8     | 101       | 5.47%   |
| 5.13    | 99        | 5.37%   |
| 5.10    | 95        | 5.15%   |
| 6.1     | 77        | 4.17%   |
| 5.19    | 73        | 3.96%   |
| 4.15    | 70        | 3.79%   |
| 6.5     | 59        | 3.2%    |
| 5.16    | 58        | 3.14%   |
| 5.3     | 56        | 3.04%   |
| 6.0     | 54        | 2.93%   |
| 6.4     | 45        | 2.44%   |
| 5.0     | 45        | 2.44%   |
| 5.17    | 39        | 2.11%   |
| 5.18    | 38        | 2.06%   |
| 4.18    | 36        | 1.95%   |
| 6.6     | 35        | 1.9%    |
| 6.3     | 24        | 1.3%    |
| 5.6     | 19        | 1.03%   |
| 5.14    | 18        | 0.98%   |
| 5.9     | 17        | 0.92%   |
| 5.12    | 15        | 0.81%   |
| 4.19    | 14        | 0.76%   |
| 5.5     | 12        | 0.65%   |
| 5.7     | 11        | 0.6%    |
| 4.9     | 11        | 0.6%    |
| 6.7     | 6         | 0.33%   |
| 5.2     | 5         | 0.27%   |
| 4.4     | 5         | 0.27%   |
| 4.1     | 3         | 0.16%   |
| 5.1     | 2         | 0.11%   |
| 4.8     | 2         | 0.11%   |
| 4.20    | 2         | 0.11%   |
| 3.16    | 2         | 0.11%   |
| 3.10    | 2         | 0.11%   |
| 4.14    | 1         | 0.05%   |
| 4.13    | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 1548      | 97.6%   |
| i686    | 33        | 2.08%   |
| aarch64 | 3         | 0.19%   |
| i586    | 2         | 0.13%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 765       | 45.19%  |
| KDE5            | 294       | 17.37%  |
| Unknown         | 150       | 8.86%   |
| X-Cinnamon      | 139       | 8.21%   |
| XFCE            | 131       | 7.74%   |
| MATE            | 37        | 2.19%   |
| KDE             | 32        | 1.89%   |
| Cinnamon        | 26        | 1.54%   |
| Pantheon        | 23        | 1.36%   |
| i3              | 15        | 0.89%   |
| Unity           | 13        | 0.77%   |
| LXQt            | 11        | 0.65%   |
| LXDE            | 10        | 0.59%   |
| Budgie          | 9         | 0.53%   |
| KDE4            | 8         | 0.47%   |
| Deepin          | 6         | 0.35%   |
| Hyprland        | 3         | 0.18%   |
| BunsenLabs      | 3         | 0.18%   |
| awesome         | 3         | 0.18%   |
| Openbox         | 2         | 0.12%   |
| GNOME Flashback | 2         | 0.12%   |
| GNOME Classic   | 2         | 0.12%   |
| sway            | 1         | 0.06%   |
| qtile-default   | 1         | 0.06%   |
| qtile           | 1         | 0.06%   |
| LeftWM          | 1         | 0.06%   |
| icewm           | 1         | 0.06%   |
| herbstluftwm    | 1         | 0.06%   |
| dwm             | 1         | 0.06%   |
| dusk            | 1         | 0.06%   |
| bspwm           | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1218      | 73.95%  |
| Wayland | 311       | 18.88%  |
| Unknown | 85        | 5.16%   |
| Tty     | 32        | 1.94%   |
| Web     | 1         | 0.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 834       | 50.03%  |
| SDDM    | 235       | 14.1%   |
| GDM     | 188       | 11.28%  |
| GDM3    | 183       | 10.98%  |
| LightDM | 174       | 10.44%  |
| TDM     | 39        | 2.34%   |
| KDM     | 8         | 0.48%   |
| SLiM    | 2         | 0.12%   |
| LXDM    | 2         | 0.12%   |
| XDM     | 1         | 0.06%   |
| GREETD  | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang         | Notebooks | Percent |
|--------------|-----------|---------|
| en_AU        | 1162      | 70.3%   |
| en_US        | 265       | 16.03%  |
| Unknown      | 135       | 8.17%   |
| C            | 43        | 2.6%    |
| en_GB        | 31        | 1.88%   |
| C.UTF8       | 4         | 0.24%   |
| zh_CN        | 1         | 0.06%   |
| ru_RU        | 1         | 0.06%   |
| POSIX        | 1         | 0.06%   |
| it_IT        | 1         | 0.06%   |
| fr_FR        | 1         | 0.06%   |
| es_ES        | 1         | 0.06%   |
| en_ZA        | 1         | 0.06%   |
| en_IN        | 1         | 0.06%   |
| en_GB.UTF-12 | 1         | 0.06%   |
| en_DK        | 1         | 0.06%   |
| en_CA        | 1         | 0.06%   |
| en_AU.UFT-8  | 1         | 0.06%   |
| de_DE        | 1         | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 834       | 51.07%  |
| BIOS | 799       | 48.93%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1215      | 74.09%  |
| Btrfs   | 184       | 11.22%  |
| Overlay | 101       | 6.16%   |
| Tmpfs   | 49        | 2.99%   |
| Unknown | 39        | 2.38%   |
| Xfs     | 21        | 1.28%   |
| Zfs     | 19        | 1.16%   |
| Ext2    | 5         | 0.3%    |
| XXXXXXX | 3         | 0.18%   |
| Ext3    | 3         | 0.18%   |
| F2fs    | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 875       | 53.55%  |
| GPT     | 614       | 37.58%  |
| MBR     | 145       | 8.87%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1435      | 88.91%  |
| Yes       | 179       | 11.09%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1259      | 77.76%  |
| Yes       | 360       | 22.24%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Hewlett-Packard                | 276       | 17.42%  |
| Dell                           | 273       | 17.23%  |
| Lenovo                         | 272       | 17.17%  |
| ASUSTek Computer               | 153       | 9.66%   |
| Acer                           | 141       | 8.9%    |
| Apple                          | 122       | 7.7%    |
| Toshiba                        | 108       | 6.82%   |
| MSI                            | 41        | 2.59%   |
| Alienware                      | 17        | 1.07%   |
| Samsung Electronics            | 16        | 1.01%   |
| Sony                           | 12        | 0.76%   |
| Valve                          | 11        | 0.69%   |
| Notebook                       | 10        | 0.63%   |
| Gigabyte Technology            | 10        | 0.63%   |
| Panasonic                      | 9         | 0.57%   |
| Timi                           | 8         | 0.51%   |
| Metabox                        | 8         | 0.51%   |
| IT Channel Pty                 | 7         | 0.44%   |
| HUAWEI                         | 7         | 0.44%   |
| Framework                      | 7         | 0.44%   |
| Unknown                        | 7         | 0.44%   |
| Razer                          | 6         | 0.38%   |
| Google                         | 6         | 0.38%   |
| System76                       | 5         | 0.32%   |
| Intel Client Systems           | 5         | 0.32%   |
| AMI                            | 4         | 0.25%   |
| Medion                         | 3         | 0.19%   |
| LG Electronics                 | 3         | 0.19%   |
| Kogan                          | 3         | 0.19%   |
| Fujitsu                        | 3         | 0.19%   |
| COM1                           | 3         | 0.19%   |
| Purism                         | 2         | 0.13%   |
| Pine Microsystems              | 2         | 0.13%   |
| Matsushita Electric Industrial | 2         | 0.13%   |
| LEADER                         | 2         | 0.13%   |
| IBM                            | 2         | 0.13%   |
| Star Labs                      | 1         | 0.06%   |
| Pendo Industries               | 1         | 0.06%   |
| ONE-NETBOOK TECHNOLOGY         | 1         | 0.06%   |
| One Education                  | 1         | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| HP Pavilion dv6                        | 18        | 1.14%   |
| HP Notebook                            | 14        | 0.88%   |
| HP Pavilion g6                         | 13        | 0.82%   |
| Apple MacBookAir7,2                    | 12        | 0.76%   |
| Valve Jupiter                          | 11        | 0.69%   |
| Apple MacBookPro9,2                    | 10        | 0.63%   |
| Apple MacBookPro8,1                    | 10        | 0.63%   |
| Apple MacBookPro10,1                   | 10        | 0.63%   |
| Unknown                                | 10        | 0.63%   |
| HP Pavilion 15                         | 9         | 0.57%   |
| Dell XPS 13 9360                       | 8         | 0.51%   |
| Dell XPS 15 9570                       | 7         | 0.44%   |
| Dell XPS 15 9560                       | 7         | 0.44%   |
| Toshiba Satellite L850                 | 6         | 0.38%   |
| Lenovo ThinkPad T470s W10DG 20JTS0HT00 | 6         | 0.38%   |
| Apple MacBookPro11,1                   | 6         | 0.38%   |
| Acer ConceptD CN315-71P                | 6         | 0.38%   |
| Toshiba Satellite P750                 | 5         | 0.32%   |
| Dell XPS 13 9370                       | 5         | 0.32%   |
| Dell Latitude E7450                    | 5         | 0.32%   |
| Apple MacBookPro12,1                   | 5         | 0.32%   |
| Apple MacBookPro10,2                   | 5         | 0.32%   |
| Apple MacBookAir6,2                    | 5         | 0.32%   |
| Acer Aspire A315-22                    | 5         | 0.32%   |
| Acer Aspire 5750G                      | 5         | 0.32%   |
| Toshiba Satellite L750                 | 4         | 0.25%   |
| Toshiba Satellite L500                 | 4         | 0.25%   |
| Toshiba Satellite L50-A                | 4         | 0.25%   |
| Toshiba Satellite C660                 | 4         | 0.25%   |
| Lenovo IdeaPad 1 14IGL05 81VU          | 4         | 0.25%   |
| Lenovo G50-45 80E3                     | 4         | 0.25%   |
| HP ProBook 430 G2                      | 4         | 0.25%   |
| HP Pavilion Notebook                   | 4         | 0.25%   |
| HP Pavilion dv7                        | 4         | 0.25%   |
| HP Laptop 15s-eq2xxx                   | 4         | 0.25%   |
| HP Laptop 15-db0xxx                    | 4         | 0.25%   |
| HP ENVY 17                             | 4         | 0.25%   |
| HP EliteBook Folio 9470m               | 4         | 0.25%   |
| HP EliteBook 8460p                     | 4         | 0.25%   |
| Dell XPS 17 9700                       | 4         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 172       | 10.86%  |
| Acer Aspire        | 97        | 6.12%   |
| Dell Latitude      | 92        | 5.81%   |
| Toshiba Satellite  | 84        | 5.3%    |
| HP Pavilion        | 71        | 4.48%   |
| Dell XPS           | 64        | 4.04%   |
| Dell Inspiron      | 60        | 3.79%   |
| HP EliteBook       | 53        | 3.35%   |
| Lenovo IdeaPad     | 51        | 3.22%   |
| HP ProBook         | 36        | 2.27%   |
| HP Laptop          | 29        | 1.83%   |
| Dell Precision     | 26        | 1.64%   |
| ASUS ZenBook       | 19        | 1.2%    |
| ASUS VivoBook      | 17        | 1.07%   |
| Lenovo Yoga        | 15        | 0.95%   |
| HP ENVY            | 15        | 0.95%   |
| Apple MacBookPro10 | 15        | 0.95%   |
| Toshiba PORTEGE    | 14        | 0.88%   |
| HP Notebook        | 14        | 0.88%   |
| ASUS ROG           | 12        | 0.76%   |
| Apple MacBookAir7  | 12        | 0.76%   |
| Valve Jupiter      | 11        | 0.69%   |
| Apple MacBookPro9  | 11        | 0.69%   |
| Apple MacBookPro11 | 11        | 0.69%   |
| Acer Swift         | 11        | 0.69%   |
| HP 250             | 10        | 0.63%   |
| Apple MacBookPro8  | 10        | 0.63%   |
| Acer Nitro         | 10        | 0.63%   |
| Unknown            | 10        | 0.63%   |
| HP ZBook           | 9         | 0.57%   |
| Dell Vostro        | 9         | 0.57%   |
| ASUS TUF           | 9         | 0.57%   |
| HP Compaq          | 8         | 0.51%   |
| Apple MacBookAir6  | 8         | 0.51%   |
| Toshiba TECRA      | 7         | 0.44%   |
| Lenovo Legion      | 7         | 0.44%   |
| HP OMEN            | 7         | 0.44%   |
| Framework Laptop   | 7         | 0.44%   |
| Razer Blade        | 6         | 0.38%   |
| Dell G3            | 6         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 142       | 8.96%   |
| 2012    | 133       | 8.4%    |
| 2020    | 129       | 8.14%   |
| 2011    | 124       | 7.83%   |
| 2018    | 119       | 7.51%   |
| 2013    | 114       | 7.2%    |
| 2021    | 111       | 7.01%   |
| 2014    | 101       | 6.38%   |
| 2016    | 92        | 5.81%   |
| 2015    | 91        | 5.74%   |
| 2017    | 90        | 5.68%   |
| 2010    | 84        | 5.3%    |
| 2022    | 67        | 4.23%   |
| 2008    | 58        | 3.66%   |
| 2009    | 42        | 2.65%   |
| 2007    | 38        | 2.4%    |
| 2023    | 31        | 1.96%   |
| 2006    | 6         | 0.38%   |
| 2005    | 6         | 0.38%   |
| Unknown | 5         | 0.32%   |
| 2003    | 1         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1584      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1437      | 89.81%  |
| Enabled  | 163       | 10.19%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1572      | 99.24%  |
| Yes  | 12        | 0.76%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 453       | 28.24%  |
| 16.01-24.0  | 335       | 20.89%  |
| 3.01-4.0    | 316       | 19.7%   |
| 8.01-16.0   | 245       | 15.27%  |
| 32.01-64.0  | 141       | 8.79%   |
| 1.01-2.0    | 55        | 3.43%   |
| 64.01-256.0 | 25        | 1.56%   |
| 24.01-32.0  | 14        | 0.87%   |
| 2.01-3.0    | 12        | 0.75%   |
| 0.51-1.0    | 4         | 0.25%   |
| 0.01-0.5    | 4         | 0.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 593       | 32.49%  |
| 2.01-3.0   | 513       | 28.11%  |
| 4.01-8.0   | 263       | 14.41%  |
| 3.01-4.0   | 241       | 13.21%  |
| 0.51-1.0   | 96        | 5.26%   |
| 8.01-16.0  | 87        | 4.77%   |
| 0.01-0.5   | 16        | 0.88%   |
| 16.01-24.0 | 10        | 0.55%   |
| 24.01-32.0 | 3         | 0.16%   |
| 0          | 2         | 0.11%   |
| 32.01-64.0 | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1163      | 70.61%  |
| 2      | 387       | 23.5%   |
| 3      | 64        | 3.89%   |
| 0      | 17        | 1.03%   |
| 4      | 12        | 0.73%   |
| 5      | 2         | 0.12%   |
| 8      | 1         | 0.06%   |
| 7      | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1044      | 65.33%  |
| Yes       | 554       | 34.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1276      | 80.25%  |
| No        | 314       | 19.75%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1555      | 97.98%  |
| No        | 32        | 2.02%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1263      | 78.45%  |
| No        | 347       | 21.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Australia | 1584      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Sydney         | 434       | 25.65%  |
| Melbourne      | 376       | 22.22%  |
| Brisbane       | 267       | 15.78%  |
| Perth          | 129       | 7.62%   |
| Adelaide       | 103       | 6.09%   |
| Canberra       | 32        | 1.89%   |
| Hobart         | 20        | 1.18%   |
| Launceston     | 11        | 0.65%   |
| Gold Coast     | 10        | 0.59%   |
| Richmond       | 8         | 0.47%   |
| Central Coast  | 7         | 0.41%   |
| Woolloongabba  | 6         | 0.35%   |
| Southport      | 6         | 0.35%   |
| Leinster       | 6         | 0.35%   |
| Geelong        | 6         | 0.35%   |
| Wollongong     | 5         | 0.3%    |
| Parramatta     | 5         | 0.3%    |
| Newcastle      | 5         | 0.3%    |
| Mitcham        | 5         | 0.3%    |
| Alexandria     | 5         | 0.3%    |
| West End       | 4         | 0.24%   |
| Wahroonga      | 4         | 0.24%   |
| Traralgon      | 4         | 0.24%   |
| Townsville     | 4         | 0.24%   |
| Point Cook     | 4         | 0.24%   |
| Nyngan         | 4         | 0.24%   |
| Mandurah       | 4         | 0.24%   |
| Geraldton      | 4         | 0.24%   |
| Ballarat       | 4         | 0.24%   |
| Artarmon       | 4         | 0.24%   |
| Warragul       | 3         | 0.18%   |
| Surry Hills    | 3         | 0.18%   |
| Spring Field   | 3         | 0.18%   |
| Parkdale       | 3         | 0.18%   |
| Mount Waverley | 3         | 0.18%   |
| Hawthorn       | 3         | 0.18%   |
| Doncaster      | 3         | 0.18%   |
| Clifton Hill   | 3         | 0.18%   |
| Campbellfield  | 3         | 0.18%   |
| Brighton       | 3         | 0.18%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 357       | 472    | 17.92%  |
| WDC                          | 207       | 291    | 10.39%  |
| Seagate                      | 202       | 321    | 10.14%  |
| Toshiba                      | 164       | 236    | 8.23%   |
| SanDisk                      | 112       | 146    | 5.62%   |
| Unknown                      | 100       | 129    | 5.02%   |
| SK hynix                     | 80        | 102    | 4.02%   |
| Intel                        | 80        | 124    | 4.02%   |
| Crucial                      | 76        | 101    | 3.82%   |
| Apple                        | 76        | 103    | 3.82%   |
| Kingston                     | 74        | 93     | 3.71%   |
| Hitachi                      | 67        | 81     | 3.36%   |
| Micron Technology            | 59        | 74     | 2.96%   |
| HGST                         | 50        | 68     | 2.51%   |
| KIOXIA                       | 22        | 24     | 1.1%    |
| Phison Electronics           | 16        | 21     | 0.8%    |
| Fujitsu                      | 16        | 21     | 0.8%    |
| Phison                       | 15        | 22     | 0.75%   |
| A-DATA Technology            | 13        | 19     | 0.65%   |
| LITEON                       | 12        | 18     | 0.6%    |
| Micron/Crucial Technology    | 11        | 12     | 0.55%   |
| LITEONIT                     | 11        | 13     | 0.55%   |
| ASMT                         | 11        | 13     | 0.55%   |
| Kingston Technology Company  | 9         | 11     | 0.45%   |
| Unknown                      | 9         | 10     | 0.45%   |
| JMicron Technology           | 8         | 13     | 0.4%    |
| SPCC                         | 7         | 10     | 0.35%   |
| Transcend                    | 6         | 8      | 0.3%    |
| OCZ                          | 6         | 8      | 0.3%    |
| KingSpec                     | 6         | 9      | 0.3%    |
| China                        | 5         | 5      | 0.25%   |
| Patriot                      | 4         | 6      | 0.2%    |
| LaCie                        | 4         | 8      | 0.2%    |
| XPG                          | 3         | 3      | 0.15%   |
| Shenzhen Longsys Electronics | 3         | 3      | 0.15%   |
| Realtek                      | 3         | 3      | 0.15%   |
| OWC                          | 3         | 10     | 0.15%   |
| Lite-On                      | 3         | 3      | 0.15%   |
| Gigabyte Technology          | 3         | 6      | 0.15%   |
| ADATA Technology             | 3         | 10     | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                             | 22        | 1.06%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 22        | 1.06%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 20        | 0.96%   |
| Toshiba MQ01ABD100 1TB                             | 18        | 0.87%   |
| Seagate ST500LT012-1DG142 500GB                    | 16        | 0.77%   |
| Seagate Expansion 1TB                              | 16        | 0.77%   |
| SanDisk NVMe SSD Drive 512GB                       | 15        | 0.72%   |
| Seagate ST1000LM035-1RK172 1TB                     | 14        | 0.67%   |
| Samsung SSD 860 EVO 500GB                          | 14        | 0.67%   |
| Unknown MMC Card  128GB                            | 13        | 0.63%   |
| Toshiba MQ01ABF050 500GB                           | 13        | 0.63%   |
| Samsung NVMe SSD Drive 512GB                       | 13        | 0.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 13        | 0.63%   |
| HGST HTS721010A9E630 1TB                           | 13        | 0.63%   |
| Apple SSD SM0128G 121GB                            | 13        | 0.63%   |
| Unknown MMC Card  32GB                             | 12        | 0.58%   |
| Kingston SA400S37240G 240GB SSD                    | 12        | 0.58%   |
| Samsung SSD 850 EVO 250GB                          | 11        | 0.53%   |
| HGST HTS545050A7E680 500GB                         | 11        | 0.53%   |
| Crucial CT500MX500SSD1 500GB                       | 11        | 0.53%   |
| Seagate ST9500325AS 500GB                          | 10        | 0.48%   |
| Samsung SSD 850 EVO 500GB                          | 10        | 0.48%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 10        | 0.48%   |
| Crucial CT1000MX500SSD1 1TB                        | 10        | 0.48%   |
| Crucial CT1000BX500SSD1 1TB                        | 10        | 0.48%   |
| Toshiba MQ04ABF100 1TB                             | 9         | 0.43%   |
| Toshiba MQ01ABD075 752GB                           | 9         | 0.43%   |
| SK hynix NVMe SSD Drive 256GB                      | 9         | 0.43%   |
| Seagate ST2000LM007-1R8174 2TB                     | 9         | 0.43%   |
| Samsung SSD 870 EVO 500GB                          | 9         | 0.43%   |
| Samsung SSD 860 EVO 1TB                            | 9         | 0.43%   |
| Hitachi HTS547575A9E384 752GB                      | 9         | 0.43%   |
| Unknown                                            | 9         | 0.43%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 8         | 0.38%   |
| WDC WD5000LPVX-22V0TT0 500GB                       | 8         | 0.38%   |
| Unknown MMC Card  16GB                             | 8         | 0.38%   |
| Toshiba NVMe SSD Drive 512GB                       | 8         | 0.38%   |
| SanDisk NVMe SSD Drive 256GB                       | 8         | 0.38%   |
| Phison PS5013 E13 NVMe Controller 256GB            | 8         | 0.38%   |
| Intel NVMe SSD Drive 512GB                         | 8         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 196       | 312    | 32.08%  |
| WDC                 | 134       | 190    | 21.93%  |
| Toshiba             | 98        | 150    | 16.04%  |
| Hitachi             | 67        | 81     | 10.97%  |
| HGST                | 50        | 68     | 8.18%   |
| Fujitsu             | 16        | 21     | 2.62%   |
| Samsung Electronics | 12        | 15     | 1.96%   |
| Unknown             | 7         | 7      | 1.15%   |
| JMicron Technology  | 7         | 11     | 1.15%   |
| Apple               | 5         | 6      | 0.82%   |
| LaCie               | 4         | 7      | 0.65%   |
| ASMT                | 3         | 5      | 0.49%   |
| TO Exter            | 2         | 2      | 0.33%   |
| KESU                | 2         | 2      | 0.33%   |
| HGST HUS            | 2         | 2      | 0.33%   |
| External            | 2         | 2      | 0.33%   |
| USB3.0              | 1         | 1      | 0.16%   |
| USB                 | 1         | 2      | 0.16%   |
| IBM/Hitachi         | 1         | 1      | 0.16%   |
| AAPL                | 1         | 1      | 0.16%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 177       | 220    | 28.41%  |
| Crucial             | 63        | 86     | 10.11%  |
| SanDisk             | 56        | 70     | 8.99%   |
| Apple               | 52        | 61     | 8.35%   |
| Kingston            | 49        | 61     | 7.87%   |
| WDC                 | 35        | 47     | 5.62%   |
| SK hynix            | 26        | 32     | 4.17%   |
| Toshiba             | 25        | 35     | 4.01%   |
| Intel               | 25        | 49     | 4.01%   |
| Micron Technology   | 18        | 19     | 2.89%   |
| LITEONIT            | 11        | 13     | 1.77%   |
| LITEON              | 11        | 17     | 1.77%   |
| SPCC                | 7         | 10     | 1.12%   |
| A-DATA Technology   | 7         | 9      | 1.12%   |
| Transcend           | 6         | 8      | 0.96%   |
| OCZ                 | 6         | 8      | 0.96%   |
| KingSpec            | 6         | 9      | 0.96%   |
| China               | 5         | 5      | 0.8%    |
| Patriot             | 4         | 6      | 0.64%   |
| Seagate             | 3         | 4      | 0.48%   |
| OWC                 | 3         | 10     | 0.48%   |
| Plextor             | 2         | 6      | 0.32%   |
| Gigabyte Technology | 2         | 2      | 0.32%   |
| FORESEE             | 2         | 2      | 0.32%   |
| WDC WDS2            | 1         | 1      | 0.16%   |
| T-CREATE            | 1         | 1      | 0.16%   |
| SAMSWEET            | 1         | 1      | 0.16%   |
| PNY CS90            | 1         | 1      | 0.16%   |
| PNY                 | 1         | 1      | 0.16%   |
| Mushkin             | 1         | 1      | 0.16%   |
| LT                  | 1         | 1      | 0.16%   |
| Leven               | 1         | 1      | 0.16%   |
| Kston               | 1         | 1      | 0.16%   |
| Kingmax             | 1         | 1      | 0.16%   |
| KingFast            | 1         | 1      | 0.16%   |
| KingDian            | 1         | 1      | 0.16%   |
| INDMEM              | 1         | 1      | 0.16%   |
| HS-SSD-E100         | 1         | 1      | 0.16%   |
| Hewlett-Packard     | 1         | 1      | 0.16%   |
| Drevo               | 1         | 1      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 589       | 812    | 31.53%  |
| NVMe    | 580       | 857    | 31.05%  |
| HDD     | 569       | 886    | 30.46%  |
| MMC     | 97        | 124    | 5.19%   |
| Unknown | 33        | 35     | 1.77%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1021      | 1571   | 56.41%  |
| NVMe | 580       | 852    | 32.04%  |
| SAS  | 112       | 167    | 6.19%   |
| MMC  | 97        | 124    | 5.36%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 759       | 1096   | 65.77%  |
| 0.51-1.0   | 323       | 471    | 27.99%  |
| 1.01-2.0   | 50        | 93     | 4.33%   |
| 3.01-4.0   | 12        | 20     | 1.04%   |
| 4.01-10.0  | 9         | 16     | 0.78%   |
| 10.01-20.0 | 1         | 2      | 0.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 460       | 26.84%  |
| 251-500        | 421       | 24.56%  |
| 501-1000       | 277       | 16.16%  |
| 1-20           | 144       | 8.4%    |
| 1001-2000      | 117       | 6.83%   |
| 51-100         | 116       | 6.77%   |
| More than 3000 | 56        | 3.27%   |
| 21-50          | 44        | 2.57%   |
| Unknown        | 43        | 2.51%   |
| 2001-3000      | 36        | 2.1%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 731       | 40.41%  |
| 21-50          | 358       | 19.79%  |
| 51-100         | 205       | 11.33%  |
| 101-250        | 194       | 10.72%  |
| 251-500        | 132       | 7.3%    |
| 501-1000       | 79        | 4.37%   |
| Unknown        | 43        | 2.38%   |
| 1001-2000      | 37        | 2.05%   |
| More than 3000 | 14        | 0.77%   |
| 2001-3000      | 14        | 0.77%   |
| 0              | 2         | 0.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Notebooks | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 4      | 3.3%    |
| HGST HTS545050A7E680 500GB              | 3         | 4      | 3.3%    |
| Toshiba MQ01ABF050 500GB                | 2         | 2      | 2.2%    |
| Seagate ST9500325AS 500GB               | 2         | 2      | 2.2%    |
| Seagate ST500LT012-1DG142 500GB         | 2         | 2      | 2.2%    |
| Seagate ST500LM021-1KJ152 500GB         | 2         | 2      | 2.2%    |
| Micron Technology 1100 SATA 256GB SSD   | 2         | 2      | 2.2%    |
| Kingston RBU-SNS8350DES3128GP 128GB SSD | 2         | 2      | 2.2%    |
| Hitachi HTS547564A9E384 640GB           | 2         | 2      | 2.2%    |
| WDC WD6400BEVT-22A0RT0 640GB            | 1         | 2      | 1.1%    |
| WDC WD5000LPVX-22V0TT0 500GB            | 1         | 2      | 1.1%    |
| WDC WD5000BEVT-60ZAT1 500GB             | 1         | 3      | 1.1%    |
| WDC WD40EFRX-68N32N0 4TB                | 1         | 1      | 1.1%    |
| WDC WD3200BPVT-22ZEST0 320GB            | 1         | 1      | 1.1%    |
| WDC WD3200BEVT-75ZCT0 320GB             | 1         | 1      | 1.1%    |
| WDC WD2500BEVT-35A23T0 250GB            | 1         | 1      | 1.1%    |
| WDC WD20 EARS-00J2GB0 2TB               | 1         | 1      | 1.1%    |
| WDC WD10SPZX-21Z10T0 1TB                | 1         | 2      | 1.1%    |
| WDC WD10JPVX-22JC3T0 1TB                | 1         | 2      | 1.1%    |
| WDC WD Blue SA510 M.2 2280 1000GB       | 1         | 1      | 1.1%    |
| Transcend TS256GSSD230S 256GB           | 1         | 1      | 1.1%    |
| Toshiba THNSNK128GCS8 SATA 128GB SSD    | 1         | 1      | 1.1%    |
| Toshiba MQ01ACF032 320GB                | 1         | 1      | 1.1%    |
| Toshiba MQ01ABD100 1TB                  | 1         | 1      | 1.1%    |
| Toshiba MQ01ABD050 500GB                | 1         | 1      | 1.1%    |
| Toshiba MK5065GSX 500GB                 | 1         | 1      | 1.1%    |
| Toshiba MK5055GSX 500GB                 | 1         | 5      | 1.1%    |
| Toshiba MK3265GSX 320GB                 | 1         | 1      | 1.1%    |
| SK hynix SC308 SATA 256GB SSD           | 1         | 1      | 1.1%    |
| Seagate ST9500423AS 500GB               | 1         | 2      | 1.1%    |
| Seagate ST9500325ASG 500GB              | 1         | 1      | 1.1%    |
| Seagate ST9320423AS 320GB               | 1         | 2      | 1.1%    |
| Seagate ST9250410AS 250GB               | 1         | 1      | 1.1%    |
| Seagate ST9250315AS 250GB               | 1         | 1      | 1.1%    |
| Seagate ST9160821AS 160GB               | 1         | 5      | 1.1%    |
| Seagate ST9160310AS 160GB               | 1         | 1      | 1.1%    |
| Seagate ST500LT012-9WS142 500GB         | 1         | 2      | 1.1%    |
| Seagate ST500LM000-1EJ162 500GB         | 1         | 2      | 1.1%    |
| Seagate ST320LT012-9WS14C 320GB         | 1         | 1      | 1.1%    |
| Seagate ST320LT007-9ZV142 320GB         | 1         | 1      | 1.1%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                   | Notebooks | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Seagate                  | 21        | 30     | 23.08%  |
| Hitachi                  | 12        | 12     | 13.19%  |
| WDC                      | 11        | 17     | 12.09%  |
| Toshiba                  | 9         | 13     | 9.89%   |
| Samsung Electronics      | 6         | 6      | 6.59%   |
| HGST                     | 6         | 7      | 6.59%   |
| Fujitsu                  | 5         | 5      | 5.49%   |
| SanDisk                  | 4         | 4      | 4.4%    |
| Micron Technology        | 4         | 4      | 4.4%    |
| Kingston                 | 3         | 3      | 3.3%    |
| Intel                    | 2         | 3      | 2.2%    |
| Crucial                  | 2         | 2      | 2.2%    |
| Transcend                | 1         | 1      | 1.1%    |
| SK hynix                 | 1         | 1      | 1.1%    |
| KingSpec                 | 1         | 3      | 1.1%    |
| Biwin Storage Technology | 1         | 1      | 1.1%    |
| Apple                    | 1         | 1      | 1.1%    |
| A-DATA Technology        | 1         | 1      | 1.1%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 30     | 33.33%  |
| Hitachi             | 12        | 12     | 19.05%  |
| WDC                 | 10        | 16     | 15.87%  |
| Toshiba             | 8         | 12     | 12.7%   |
| HGST                | 6         | 7      | 9.52%   |
| Fujitsu             | 5         | 5      | 7.94%   |
| Samsung Electronics | 1         | 1      | 1.59%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 62        | 83     | 68.89%  |
| SSD  | 24        | 27     | 26.67%  |
| NVMe | 4         | 4      | 4.44%   |

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
| Detected | 1005      | 1698   | 59.93%  |
| Works    | 583       | 902    | 34.76%  |
| Malfunc  | 89        | 114    | 5.31%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1085      | 58.24%  |
| Samsung Electronics                     | 203       | 10.9%   |
| AMD                                     | 145       | 7.78%   |
| SanDisk                                 | 94        | 5.05%   |
| SK hynix                                | 54        | 2.9%    |
| Toshiba America Info Systems            | 41        | 2.2%    |
| Micron Technology                       | 41        | 2.2%    |
| Kingston Technology Company             | 34        | 1.83%   |
| Phison Electronics                      | 33        | 1.77%   |
| Micron/Crucial Technology               | 25        | 1.34%   |
| KIOXIA                                  | 20        | 1.07%   |
| Apple                                   | 18        | 0.97%   |
| Nvidia                                  | 16        | 0.86%   |
| ADATA Technology                        | 11        | 0.59%   |
| Marvell Technology Group                | 9         | 0.48%   |
| Solid State Storage Technology          | 5         | 0.27%   |
| Silicon Motion                          | 5         | 0.27%   |
| Lite-On Technology                      | 4         | 0.21%   |
| Shenzhen Longsys Electronics            | 3         | 0.16%   |
| Union Memory (Shenzhen)                 | 2         | 0.11%   |
| Silicon Integrated Systems [SiS]        | 2         | 0.11%   |
| Realtek Semiconductor                   | 2         | 0.11%   |
| O2 Micro                                | 2         | 0.11%   |
| Lenovo                                  | 2         | 0.11%   |
| ULi Electronics                         | 1         | 0.05%   |
| Solidigm                                | 1         | 0.05%   |
| Shenzhen Unionmemory Information System | 1         | 0.05%   |
| MAXIO Technology (Hangzhou)             | 1         | 0.05%   |
| JMicron Technology                      | 1         | 0.05%   |
| Biwin Storage Technology                | 1         | 0.05%   |
| ASMedia Technology                      | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 131       | 6.61%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 129       | 6.51%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 111       | 5.6%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 110       | 5.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 102       | 5.15%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 95        | 4.79%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 60        | 3.03%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 57        | 2.88%   |
| Intel Volume Management Device NVMe RAID Controller                              | 52        | 2.62%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 52        | 2.62%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 44        | 2.22%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 42        | 2.12%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 37        | 1.87%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 33        | 1.66%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 27        | 1.36%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 26        | 1.31%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 25        | 1.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 24        | 1.21%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 23        | 1.16%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 22        | 1.11%   |
| Intel SSD 660P Series                                                            | 20        | 1.01%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                       | 19        | 0.96%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 19        | 0.96%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 18        | 0.91%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 18        | 0.91%   |
| Intel Tiger Lake-LP SATA Controller                                              | 17        | 0.86%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 17        | 0.86%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 15        | 0.76%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 15        | 0.76%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 14        | 0.71%   |
| Phison E12 NVMe Controller                                                       | 14        | 0.71%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                      | 13        | 0.66%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 13        | 0.66%   |
| Intel Comet Lake SATA AHCI Controller                                            | 13        | 0.66%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 13        | 0.66%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 12        | 0.61%   |
| Apple ANS2 NVMe Controller                                                       | 12        | 0.61%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 11        | 0.55%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 11        | 0.55%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                 | 11        | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1054      | 55.56%  |
| NVMe | 583       | 30.73%  |
| RAID | 170       | 8.96%   |
| IDE  | 90        | 4.74%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1344      | 84.85%  |
| AMD    | 237       | 14.96%  |
| ARM    | 3         | 0.19%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz       | 35        | 2.21%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 30        | 1.89%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 24        | 1.51%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 23        | 1.45%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 23        | 1.45%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 22        | 1.39%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 20        | 1.26%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 20        | 1.26%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 20        | 1.26%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 19        | 1.2%    |
| Intel Core i7-8750H CPU @ 2.20GHz       | 18        | 1.13%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 18        | 1.13%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 17        | 1.07%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 17        | 1.07%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 17        | 1.07%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 17        | 1.07%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 16        | 1.01%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 15        | 0.95%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 15        | 0.95%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 15        | 0.95%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 14        | 0.88%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 14        | 0.88%   |
| Intel Core i7-3610QM CPU @ 2.30GHz      | 14        | 0.88%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 13        | 0.82%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 13        | 0.82%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 12        | 0.76%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 12        | 0.76%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz    | 12        | 0.76%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 11        | 0.69%   |
| Intel Core i7-4510U CPU @ 2.00GHz       | 11        | 0.69%   |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 11        | 0.69%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz       | 11        | 0.69%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 11        | 0.69%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 11        | 0.69%   |
| AMD Custom APU 0405                     | 11        | 0.69%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 10        | 0.63%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 10        | 0.63%   |
| Intel 12th Gen Core i7-12700H           | 10        | 0.63%   |
| Intel Core i7-3740QM CPU @ 2.70GHz      | 9         | 0.57%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 9         | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 511       | 32.24%  |
| Intel Core i5           | 395       | 24.92%  |
| Other                   | 160       | 10.09%  |
| Intel Core 2 Duo        | 68        | 4.29%   |
| Intel Core i3           | 63        | 3.97%   |
| Intel Celeron           | 62        | 3.91%   |
| AMD Ryzen 7             | 50        | 3.15%   |
| AMD Ryzen 5             | 40        | 2.52%   |
| Intel Pentium           | 29        | 1.83%   |
| AMD A6                  | 22        | 1.39%   |
| AMD A4                  | 22        | 1.39%   |
| Intel Atom              | 15        | 0.95%   |
| AMD Ryzen 7 PRO         | 11        | 0.69%   |
| AMD E2                  | 10        | 0.63%   |
| AMD Ryzen 9             | 9         | 0.57%   |
| Intel Core i9           | 8         | 0.5%    |
| Intel Core 2            | 8         | 0.5%    |
| AMD A8                  | 8         | 0.5%    |
| AMD A10                 | 8         | 0.5%    |
| Intel Pentium Dual-Core | 7         | 0.44%   |
| Intel Core M            | 7         | 0.44%   |
| AMD E1                  | 7         | 0.44%   |
| Intel Genuine           | 6         | 0.38%   |
| Intel Xeon              | 5         | 0.32%   |
| Intel Pentium Dual      | 5         | 0.32%   |
| Intel Core m3           | 5         | 0.32%   |
| AMD Ryzen 3             | 5         | 0.32%   |
| Intel Celeron Dual-Core | 4         | 0.25%   |
| AMD E                   | 4         | 0.25%   |
| Intel Pentium M         | 3         | 0.19%   |
| Intel Core m7           | 3         | 0.19%   |
| Intel Celeron M         | 3         | 0.19%   |
| AMD Ryzen 5 PRO         | 3         | 0.19%   |
| Intel Core Duo          | 2         | 0.13%   |
| AMD V120                | 2         | 0.13%   |
| AMD FX                  | 2         | 0.13%   |
| AMD A12                 | 2         | 0.13%   |
| Intel Mobile Pentium 4  | 1         | 0.06%   |
| Intel Core m5           | 1         | 0.06%   |
| AMD V140                | 1         | 0.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 752       | 47.41%  |
| 4      | 529       | 33.35%  |
| 6      | 128       | 8.07%   |
| 8      | 87        | 5.49%   |
| 1      | 34        | 2.14%   |
| 14     | 21        | 1.32%   |
| 10     | 19        | 1.2%    |
| 12     | 12        | 0.76%   |
| 16     | 2         | 0.13%   |
| 24     | 1         | 0.06%   |
| 5      | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1582      | 99.87%  |
| 2      | 2         | 0.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1261      | 79.51%  |
| 1      | 322       | 20.3%   |
| 4      | 2         | 0.13%   |
| 8      | 1         | 0.06%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1554      | 97.61%  |
| 32-bit         | 19        | 1.19%   |
| Unknown        | 17        | 1.07%   |
| 64-bit         | 2         | 0.13%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 586       | 35.15%  |
| 0x206a7    | 95        | 5.7%    |
| 0x306a9    | 84        | 5.04%   |
| 0x406e3    | 52        | 3.12%   |
| 0x40651    | 52        | 3.12%   |
| 0x906ea    | 51        | 3.06%   |
| 0x306d4    | 44        | 2.64%   |
| 0x806ec    | 42        | 2.52%   |
| 0x1067a    | 42        | 2.52%   |
| 0x20655    | 39        | 2.34%   |
| 0x806ea    | 38        | 2.28%   |
| 0x806c1    | 35        | 2.1%    |
| 0x306c3    | 35        | 2.1%    |
| 0x806e9    | 32        | 1.92%   |
| 0x906e9    | 22        | 1.32%   |
| 0xa0652    | 21        | 1.26%   |
| 0x20652    | 20        | 1.2%    |
| 0x0a50000c | 19        | 1.14%   |
| 0x06006705 | 19        | 1.14%   |
| 0x806eb    | 16        | 0.96%   |
| 0x30678    | 15        | 0.9%    |
| 0x07030105 | 15        | 0.9%    |
| 0x906a3    | 13        | 0.78%   |
| 0x706e5    | 13        | 0.78%   |
| 0x506e3    | 13        | 0.78%   |
| 0x806d1    | 12        | 0.72%   |
| 0x0700010f | 12        | 0.72%   |
| 0x106e5    | 11        | 0.66%   |
| 0x10676    | 11        | 0.66%   |
| 0x08108102 | 10        | 0.6%    |
| 0x406c4    | 9         | 0.54%   |
| 0x406c3    | 9         | 0.54%   |
| 0x08108109 | 9         | 0.54%   |
| 0x6fd      | 8         | 0.48%   |
| 0x906a4    | 7         | 0.42%   |
| 0x08600106 | 7         | 0.42%   |
| 0x08600103 | 7         | 0.42%   |
| 0x06001119 | 7         | 0.42%   |
| 0x6f6      | 6         | 0.36%   |
| 0x506c9    | 6         | 0.36%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 297       | 18.73%  |
| IvyBridge        | 142       | 8.95%   |
| Haswell          | 134       | 8.45%   |
| SandyBridge      | 131       | 8.26%   |
| Skylake          | 107       | 6.75%   |
| Westmere         | 72        | 4.54%   |
| Penryn           | 69        | 4.35%   |
| Broadwell        | 66        | 4.16%   |
| Unknown          | 65        | 4.1%    |
| TigerLake        | 57        | 3.59%   |
| CometLake        | 41        | 2.59%   |
| Alderlake Hybrid | 40        | 2.52%   |
| IceLake          | 39        | 2.46%   |
| Silvermont       | 38        | 2.4%    |
| Zen 3            | 34        | 2.14%   |
| Excavator        | 33        | 2.08%   |
| Core             | 27        | 1.7%    |
| Zen+             | 24        | 1.51%   |
| Zen 2            | 24        | 1.51%   |
| Puma             | 20        | 1.26%   |
| Goldmont plus    | 16        | 1.01%   |
| Jaguar           | 14        | 0.88%   |
| P6               | 13        | 0.82%   |
| Nehalem          | 13        | 0.82%   |
| Zen              | 12        | 0.76%   |
| Piledriver       | 10        | 0.63%   |
| Goldmont         | 9         | 0.57%   |
| Bonnell          | 8         | 0.5%    |
| K10 Llano        | 7         | 0.44%   |
| K10              | 6         | 0.38%   |
| Steamroller      | 5         | 0.32%   |
| Bobcat           | 5         | 0.32%   |
| Tremont          | 3         | 0.19%   |
| K8 & K10 hybrid  | 2         | 0.13%   |
| NetBurst         | 1         | 0.06%   |
| K8 Hammer        | 1         | 0.06%   |
| Gracemont        | 1         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1192      | 58.17%  |
| Nvidia                           | 500       | 24.4%   |
| AMD                              | 353       | 17.23%  |
| Silicon Integrated Systems [SiS] | 2         | 0.1%    |
| Neomagic                         | 2         | 0.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 124       | 5.84%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 116       | 5.46%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 79        | 3.72%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 76        | 3.58%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 67        | 3.15%   |
| Intel UHD Graphics 620                                                                   | 63        | 2.97%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 54        | 2.54%   |
| Intel Core Processor Integrated Graphics Controller                                      | 50        | 2.35%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 48        | 2.26%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 42        | 1.98%   |
| Intel HD Graphics 5500                                                                   | 41        | 1.93%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 37        | 1.74%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 35        | 1.65%   |
| Intel HD Graphics 620                                                                    | 33        | 1.55%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 30        | 1.41%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 29        | 1.37%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 28        | 1.32%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 28        | 1.32%   |
| Intel HD Graphics 630                                                                    | 25        | 1.18%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 25        | 1.18%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 23        | 1.08%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 22        | 1.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 21        | 0.99%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 20        | 0.94%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 19        | 0.89%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 18        | 0.85%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 18        | 0.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 17        | 0.8%    |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 17        | 0.8%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 16        | 0.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 16        | 0.75%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 16        | 0.75%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 16        | 0.75%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 15        | 0.71%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 15        | 0.71%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 15        | 0.71%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 15        | 0.71%   |
| Intel HD Graphics 530                                                                    | 15        | 0.71%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 14        | 0.66%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 13        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 763       | 47.87%  |
| Intel + Nvidia           | 356       | 22.33%  |
| 1 x AMD                  | 207       | 12.99%  |
| 1 x Nvidia               | 103       | 6.46%   |
| Intel + AMD              | 61        | 3.83%   |
| 2 x AMD                  | 45        | 2.82%   |
| AMD + Nvidia             | 40        | 2.51%   |
| 2 x Intel                | 8         | 0.5%    |
| Other                    | 3         | 0.19%   |
| 1 x SiS                  | 2         | 0.13%   |
| 1 x Neomagic             | 2         | 0.13%   |
| Intel + AMD + 1 x Nvidia | 2         | 0.13%   |
| 2 x Nvidia               | 1         | 0.06%   |
| Intel + 2 x Nvidia       | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1330      | 81.9%   |
| Proprietary | 248       | 15.27%  |
| Unknown     | 46        | 2.83%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1071      | 65.3%   |
| 1.01-2.0   | 164       | 10%     |
| 0.01-0.5   | 156       | 9.51%   |
| 3.01-4.0   | 97        | 5.91%   |
| 0.51-1.0   | 89        | 5.43%   |
| 5.01-6.0   | 30        | 1.83%   |
| 7.01-8.0   | 20        | 1.22%   |
| 2.01-3.0   | 8         | 0.49%   |
| 8.01-16.0  | 5         | 0.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 374       | 20.26%  |
| LG Display              | 252       | 13.65%  |
| Chimei Innolux          | 191       | 10.35%  |
| Samsung Electronics     | 178       | 9.64%   |
| BOE                     | 167       | 9.05%   |
| Apple                   | 119       | 6.45%   |
| Sharp                   | 77        | 4.17%   |
| Dell                    | 56        | 3.03%   |
| Chi Mei Optoelectronics | 45        | 2.44%   |
| Lenovo                  | 34        | 1.84%   |
| Goldstar                | 28        | 1.52%   |
| Acer                    | 28        | 1.52%   |
| PANDA                   | 26        | 1.41%   |
| Philips                 | 24        | 1.3%    |
| Hewlett-Packard         | 24        | 1.3%    |
| BenQ                    | 22        | 1.19%   |
| Sony                    | 13        | 0.7%    |
| AOC                     | 12        | 0.65%   |
| ViewSonic               | 11        | 0.6%    |
| Valve                   | 11        | 0.6%    |
| InfoVision              | 10        | 0.54%   |
| Unknown                 | 8         | 0.43%   |
| CSO                     | 8         | 0.43%   |
| Ancor Communications    | 8         | 0.43%   |
| LG Philips              | 7         | 0.38%   |
| Toshiba                 | 6         | 0.33%   |
| Panasonic               | 6         | 0.33%   |
| CPT                     | 6         | 0.33%   |
| LGD                     | 5         | 0.27%   |
| Hitachi                 | 5         | 0.27%   |
| GKK                     | 5         | 0.27%   |
| SAC                     | 4         | 0.22%   |
| Kogan                   | 4         | 0.22%   |
| HannStar                | 4         | 0.22%   |
| GDH                     | 4         | 0.22%   |
| eMachines               | 4         | 0.22%   |
| ASUSTek Computer        | 4         | 0.22%   |
| ___                     | 3         | 0.16%   |
| InnoLux Display         | 3         | 0.16%   |
| Unknown (XXX)           | 2         | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 19        | 1.01%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 17        | 0.9%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 12        | 0.64%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 11        | 0.58%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 11        | 0.58%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 11        | 0.58%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 10        | 0.53%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 10        | 0.53%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                     | 10        | 0.53%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 9         | 0.48%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                     | 9         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 8         | 0.42%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 8         | 0.42%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch           | 8         | 0.42%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                  | 7         | 0.37%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 7         | 0.37%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 7         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 7         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 7         | 0.37%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 7         | 0.37%   |
| BOE LCD Monitor BOE07CE 1366x768 344x193mm 15.5-inch                     | 7         | 0.37%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 7         | 0.37%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 7         | 0.37%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 7         | 0.37%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 6         | 0.32%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 6         | 0.32%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 6         | 0.32%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 6         | 0.32%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 6         | 0.32%   |
| Chimei Innolux LCD Monitor CMN1514 1920x1080 344x193mm 15.5-inch         | 6         | 0.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO1100 1366x768 256x144mm 11.6-inch | 6         | 0.32%   |
| BOE LCD Monitor BOE07CB 1920x1080 344x193mm 15.5-inch                    | 6         | 0.32%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 6         | 0.32%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 6         | 0.32%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch           | 6         | 0.32%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 6         | 0.32%   |
| Apple Color LCD APPA01B 1440x900 286x179mm 13.3-inch                     | 6         | 0.32%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                     | 6         | 0.32%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 5         | 0.27%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 5         | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 660       | 38.08%  |
| 1366x768 (WXGA)    | 508       | 29.31%  |
| 3840x2160 (4K)     | 102       | 5.89%   |
| 1280x800 (WXGA)    | 73        | 4.21%   |
| 1600x900 (HD+)     | 55        | 3.17%   |
| 1440x900 (WXGA+)   | 44        | 2.54%   |
| 2560x1440 (QHD)    | 40        | 2.31%   |
| 1920x1200 (WUXGA)  | 39        | 2.25%   |
| 2560x1600          | 38        | 2.19%   |
| 2880x1800          | 28        | 1.62%   |
| 3840x2400          | 15        | 0.87%   |
| 1680x1050 (WSXGA+) | 15        | 0.87%   |
| 3440x1440          | 13        | 0.75%   |
| 800x1280           | 11        | 0.63%   |
| 3200x1800 (QHD+)   | 9         | 0.52%   |
| 1360x768           | 7         | 0.4%    |
| 1280x1024 (SXGA)   | 7         | 0.4%    |
| 3200x2000          | 6         | 0.35%   |
| 1024x600           | 6         | 0.35%   |
| 3840x1080          | 5         | 0.29%   |
| 3072x1920          | 5         | 0.29%   |
| 2256x1504          | 5         | 0.29%   |
| Unknown            | 5         | 0.29%   |
| 2240x1400          | 4         | 0.23%   |
| 2160x1440          | 4         | 0.23%   |
| 2304x1440          | 3         | 0.17%   |
| 5760x2160          | 2         | 0.12%   |
| 3840x1600          | 2         | 0.12%   |
| 3840x1100          | 2         | 0.12%   |
| 3456x2160          | 2         | 0.12%   |
| 3286x1080          | 2         | 0.12%   |
| 2560x1080          | 2         | 0.12%   |
| 2288x1287          | 2         | 0.12%   |
| 1920x540           | 2         | 0.12%   |
| 1680x945           | 2         | 0.12%   |
| 1280x720 (HD)      | 2         | 0.12%   |
| 1024x768 (XGA)     | 2         | 0.12%   |
| 3000x2000          | 1         | 0.06%   |
| 2880x1620          | 1         | 0.06%   |
| 2726x768           | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 713       | 38.52%  |
| 13      | 281       | 15.18%  |
| 14      | 203       | 10.97%  |
| 17      | 108       | 5.83%   |
| 27      | 78        | 4.21%   |
| 24      | 62        | 3.35%   |
| 12      | 51        | 2.76%   |
| 23      | 45        | 2.43%   |
| 11      | 45        | 2.43%   |
| 21      | 36        | 1.94%   |
| 16      | 31        | 1.67%   |
| Unknown | 28        | 1.51%   |
| 31      | 26        | 1.4%    |
| 72      | 12        | 0.65%   |
| 18      | 12        | 0.65%   |
| 34      | 11        | 0.59%   |
| 7       | 11        | 0.59%   |
| 84      | 10        | 0.54%   |
| 19      | 10        | 0.54%   |
| 40      | 8         | 0.43%   |
| 22      | 8         | 0.43%   |
| 10      | 8         | 0.43%   |
| 52      | 7         | 0.38%   |
| 20      | 6         | 0.32%   |
| 54      | 4         | 0.22%   |
| 48      | 4         | 0.22%   |
| 37      | 4         | 0.22%   |
| 86      | 3         | 0.16%   |
| 35      | 3         | 0.16%   |
| 32      | 3         | 0.16%   |
| 142     | 2         | 0.11%   |
| 49      | 2         | 0.11%   |
| 46      | 2         | 0.11%   |
| 42      | 2         | 0.11%   |
| 25      | 2         | 0.11%   |
| 8       | 2         | 0.11%   |
| 78      | 1         | 0.05%   |
| 63      | 1         | 0.05%   |
| 55      | 1         | 0.05%   |
| 38      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 1022      | 55.82%  |
| 201-300        | 284       | 15.51%  |
| 501-600        | 158       | 8.63%   |
| 351-400        | 138       | 7.54%   |
| 401-500        | 65        | 3.55%   |
| 601-700        | 40        | 2.18%   |
| Unknown        | 28        | 1.53%   |
| 1001-1500      | 24        | 1.31%   |
| 1501-2000      | 23        | 1.26%   |
| 801-900        | 16        | 0.87%   |
| 701-800        | 16        | 0.87%   |
| 1-100          | 11        | 0.6%    |
| More than 2000 | 2         | 0.11%   |
| 101-200        | 2         | 0.11%   |
| 901-1000       | 2         | 0.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1262      | 78.14%  |
| 16/10   | 262       | 16.22%  |
| Unknown | 20        | 1.24%   |
| 21/9    | 17        | 1.05%   |
| 3/2     | 16        | 0.99%   |
| 0.67    | 11        | 0.68%   |
| 5/4     | 8         | 0.5%    |
| 32/9    | 7         | 0.43%   |
| 4/3     | 3         | 0.19%   |
| 0.56    | 3         | 0.19%   |
| 3.40    | 2         | 0.12%   |
| 1.00    | 2         | 0.12%   |
| 6/5     | 1         | 0.06%   |
| 0.62    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 707       | 38.32%  |
| 81-90          | 357       | 19.35%  |
| 71-80          | 127       | 6.88%   |
| 201-250        | 120       | 6.5%    |
| 121-130        | 91        | 4.93%   |
| 301-350        | 78        | 4.23%   |
| 61-70          | 47        | 2.55%   |
| 51-60          | 47        | 2.55%   |
| 351-500        | 44        | 2.38%   |
| More than 1000 | 40        | 2.17%   |
| 111-120        | 34        | 1.84%   |
| 151-200        | 29        | 1.57%   |
| Unknown        | 28        | 1.52%   |
| 501-1000       | 24        | 1.3%    |
| 251-300        | 17        | 0.92%   |
| 131-140        | 15        | 0.81%   |
| 1-40           | 13        | 0.7%    |
| 141-150        | 12        | 0.65%   |
| 41-50          | 9         | 0.49%   |
| 91-100         | 6         | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 641       | 35.69%  |
| 101-120       | 527       | 29.34%  |
| 51-100        | 287       | 15.98%  |
| 161-240       | 177       | 9.86%   |
| More than 240 | 100       | 5.57%   |
| 1-50          | 36        | 2%      |
| Unknown       | 28        | 1.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1280      | 77.62%  |
| 2     | 275       | 16.68%  |
| 0     | 49        | 2.97%   |
| 3     | 40        | 2.43%   |
| 4     | 5         | 0.3%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 864       | 33.44%  |
| Realtek Semiconductor             | 788       | 30.5%   |
| Qualcomm Atheros                  | 333       | 12.89%  |
| Broadcom                          | 196       | 7.59%   |
| Broadcom Limited                  | 64        | 2.48%   |
| MediaTek                          | 36        | 1.39%   |
| Sierra Wireless                   | 28        | 1.08%   |
| Ralink                            | 28        | 1.08%   |
| Marvell Technology Group          | 22        | 0.85%   |
| DisplayLink                       | 19        | 0.74%   |
| Samsung Electronics               | 17        | 0.66%   |
| Dell                              | 15        | 0.58%   |
| Hewlett-Packard                   | 13        | 0.5%    |
| Huawei Technologies               | 12        | 0.46%   |
| Apple                             | 12        | 0.46%   |
| Lenovo                            | 11        | 0.43%   |
| Nvidia                            | 10        | 0.39%   |
| NetGear                           | 10        | 0.39%   |
| TP-Link                           | 9         | 0.35%   |
| Ralink Technology                 | 9         | 0.35%   |
| ASIX Electronics                  | 9         | 0.35%   |
| ZTE WCDMA Technologies MSM        | 8         | 0.31%   |
| Qualcomm                          | 8         | 0.31%   |
| Edimax Technology                 | 7         | 0.27%   |
| OPPO Electronics                  | 6         | 0.23%   |
| JMicron Technology                | 4         | 0.15%   |
| Google                            | 4         | 0.15%   |
| Ericsson Business Mobile Networks | 4         | 0.15%   |
| ASUSTek Computer                  | 4         | 0.15%   |
| Xiaomi                            | 3         | 0.12%   |
| Motorola PCS                      | 3         | 0.12%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.08%   |
| Qualcomm Atheros Communications   | 2         | 0.08%   |
| Microsoft                         | 2         | 0.08%   |
| ICS Advent                        | 2         | 0.08%   |
| Dresden Elektronik                | 2         | 0.08%   |
| D-Link                            | 2         | 0.08%   |
| Arduino SA                        | 2         | 0.08%   |
| Wilocity                          | 1         | 0.04%   |
| ULi Electronics                   | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 460       | 14.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 129       | 4.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 99        | 3.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 70        | 2.26%   |
| Intel Wireless 8260                                                    | 63        | 2.03%   |
| Intel Wi-Fi 6 AX200                                                    | 62        | 2%      |
| Intel Wireless 8265 / 8275                                             | 59        | 1.9%    |
| Intel Wireless 7260                                                    | 51        | 1.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 50        | 1.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 50        | 1.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 50        | 1.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 47        | 1.52%   |
| Intel Wi-Fi 6 AX201                                                    | 44        | 1.42%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 42        | 1.35%   |
| Intel Ethernet Connection I219-LM                                      | 39        | 1.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 38        | 1.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 38        | 1.23%   |
| Intel Wireless 3165                                                    | 37        | 1.19%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 36        | 1.16%   |
| Intel Centrino Ultimate-N 6300                                         | 35        | 1.13%   |
| Intel Wireless 7265                                                    | 32        | 1.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 30        | 0.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 29        | 0.94%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 29        | 0.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 27        | 0.87%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 27        | 0.87%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 27        | 0.87%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 25        | 0.81%   |
| Intel Ethernet Connection (4) I219-LM                                  | 25        | 0.81%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 25        | 0.81%   |
| Intel Wireless 3160                                                    | 22        | 0.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 21        | 0.68%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 21        | 0.68%   |
| Intel 82577LM Gigabit Network Connection                               | 21        | 0.68%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 21        | 0.68%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 19        | 0.61%   |
| Intel Ethernet Connection I218-LM                                      | 18        | 0.58%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 18        | 0.58%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 18        | 0.58%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 17        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 839       | 50.51%  |
| Qualcomm Atheros                | 280       | 16.86%  |
| Realtek Semiconductor           | 177       | 10.66%  |
| Broadcom                        | 155       | 9.33%   |
| Broadcom Limited                | 53        | 3.19%   |
| MediaTek                        | 35        | 2.11%   |
| Sierra Wireless                 | 28        | 1.69%   |
| Ralink                          | 28        | 1.69%   |
| NetGear                         | 10        | 0.6%    |
| Dell                            | 10        | 0.6%    |
| Ralink Technology               | 9         | 0.54%   |
| TP-Link                         | 8         | 0.48%   |
| Qualcomm                        | 7         | 0.42%   |
| Edimax Technology               | 7         | 0.42%   |
| Hewlett-Packard                 | 4         | 0.24%   |
| ASUSTek Computer                | 4         | 0.24%   |
| Qualcomm Atheros Communications | 2         | 0.12%   |
| D-Link                          | 2         | 0.12%   |
| Xiaomi                          | 1         | 0.06%   |
| Wilocity                        | 1         | 0.06%   |
| Belkin Components               | 1         | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                                     | 63        | 3.77%   |
| Intel Wi-Fi 6 AX200                                                     | 62        | 3.71%   |
| Intel Wireless 8265 / 8275                                              | 59        | 3.54%   |
| Intel Wireless 7260                                                     | 51        | 3.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 50        | 3%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 50        | 3%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 50        | 3%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 47        | 2.82%   |
| Intel Wi-Fi 6 AX201                                                     | 44        | 2.64%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 42        | 2.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 38        | 2.28%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 38        | 2.28%   |
| Intel Wireless 3165                                                     | 37        | 2.22%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 36        | 2.16%   |
| Intel Centrino Ultimate-N 6300                                          | 35        | 2.1%    |
| Intel Wireless 7265                                                     | 32        | 1.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 30        | 1.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 29        | 1.74%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 29        | 1.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 27        | 1.62%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 27        | 1.62%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter    | 27        | 1.62%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 25        | 1.5%    |
| Broadcom BCM4331 802.11a/b/g/n                                          | 25        | 1.5%    |
| Intel Wireless 3160                                                     | 22        | 1.32%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 21        | 1.26%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 19        | 1.14%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 18        | 1.08%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 17        | 1.02%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 17        | 1.02%   |
| Intel Centrino Advanced-N 6235                                          | 16        | 0.96%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 15        | 0.9%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 15        | 0.9%    |
| Intel Centrino Advanced-N 6200                                          | 15        | 0.9%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 14        | 0.84%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 14        | 0.84%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 13        | 0.78%   |
| Intel WiFi Link 5100                                                    | 13        | 0.78%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 13        | 0.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 709       | 52.02%  |
| Intel                            | 312       | 22.89%  |
| Qualcomm Atheros                 | 99        | 7.26%   |
| Broadcom                         | 86        | 6.31%   |
| Marvell Technology Group         | 22        | 1.61%   |
| DisplayLink                      | 19        | 1.39%   |
| Samsung Electronics              | 17        | 1.25%   |
| Apple                            | 12        | 0.88%   |
| Lenovo                           | 11        | 0.81%   |
| Broadcom Limited                 | 11        | 0.81%   |
| Nvidia                           | 10        | 0.73%   |
| Huawei Technologies              | 9         | 0.66%   |
| ASIX Electronics                 | 9         | 0.66%   |
| ZTE WCDMA Technologies MSM       | 8         | 0.59%   |
| OPPO Electronics                 | 6         | 0.44%   |
| JMicron Technology               | 4         | 0.29%   |
| Google                           | 4         | 0.29%   |
| Hewlett-Packard                  | 3         | 0.22%   |
| Xiaomi                           | 2         | 0.15%   |
| Silicon Integrated Systems [SiS] | 2         | 0.15%   |
| Microsoft                        | 2         | 0.15%   |
| ICS Advent                       | 2         | 0.15%   |
| T & A Mobile Phones              | 1         | 0.07%   |
| Qualcomm                         | 1         | 0.07%   |
| Motorola PCS                     | 1         | 0.07%   |
| Attansic Technology              | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 460       | 33.12%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 129       | 9.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 99        | 7.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 70        | 5.04%   |
| Intel Ethernet Connection I219-LM                                      | 39        | 2.81%   |
| Intel Ethernet Connection (4) I219-LM                                  | 25        | 1.8%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 21        | 1.51%   |
| Intel 82577LM Gigabit Network Connection                               | 21        | 1.51%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 21        | 1.51%   |
| Intel Ethernet Connection I218-LM                                      | 18        | 1.3%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 18        | 1.3%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 13        | 0.94%   |
| Intel Ethernet Connection (3) I218-LM                                  | 13        | 0.94%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 12        | 0.86%   |
| Intel Ethernet Connection (4) I219-V                                   | 12        | 0.86%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 12        | 0.86%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 10        | 0.72%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 10        | 0.72%   |
| Intel Ethernet Connection I219-V                                       | 10        | 0.72%   |
| Intel 82567LM Gigabit Network Connection                               | 10        | 0.72%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 10        | 0.72%   |
| Realtek Killer E2600 GbE Controller                                    | 9         | 0.65%   |
| Intel Ethernet Connection I217-LM                                      | 9         | 0.65%   |
| Realtek RTL8125 2.5GbE Controller                                      | 8         | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 8         | 0.58%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 8         | 0.58%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 8         | 0.58%   |
| Intel Ethernet Connection (6) I219-V                                   | 8         | 0.58%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 8         | 0.58%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 7         | 0.5%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 7         | 0.5%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 7         | 0.5%    |
| ASIX AX88179 Gigabit Ethernet                                          | 7         | 0.5%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 6         | 0.43%   |
| OPPO SM8350-IDP _SN:361A1B3C                                           | 6         | 0.43%   |
| Nvidia MCP79 Ethernet                                                  | 6         | 0.43%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 6         | 0.43%   |
| Intel Ethernet Connection (7) I219-LM                                  | 6         | 0.43%   |
| Intel Ethernet Connection (13) I219-V                                  | 6         | 0.43%   |
| Intel Ethernet Connection (10) I219-V                                  | 6         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1555      | 54.28%  |
| Ethernet | 1269      | 44.29%  |
| Modem    | 36        | 1.26%   |
| Unknown  | 5         | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1292      | 77.88%  |
| Ethernet | 367       | 22.12%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1136      | 71.49%  |
| 1     | 427       | 26.87%  |
| 0     | 14        | 0.88%   |
| 3     | 12        | 0.76%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1379      | 85.65%  |
| Yes  | 231       | 14.35%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 634       | 49.61%  |
| Qualcomm Atheros Communications | 103       | 8.06%   |
| Apple                           | 101       | 7.9%    |
| Broadcom                        | 75        | 5.87%   |
| Realtek Semiconductor           | 73        | 5.71%   |
| IMC Networks                    | 59        | 4.62%   |
| Foxconn / Hon Hai               | 50        | 3.91%   |
| Lite-On Technology              | 45        | 3.52%   |
| Toshiba                         | 37        | 2.9%    |
| Hewlett-Packard                 | 22        | 1.72%   |
| Dell                            | 18        | 1.41%   |
| Ralink                          | 15        | 1.17%   |
| Cambridge Silicon Radio         | 10        | 0.78%   |
| Alps Electric                   | 8         | 0.63%   |
| Realtek                         | 6         | 0.47%   |
| ASUSTek Computer                | 6         | 0.47%   |
| Ralink Technology               | 4         | 0.31%   |
| MediaTek                        | 4         | 0.31%   |
| USI                             | 3         | 0.23%   |
| Micro Star International        | 2         | 0.16%   |
| Taiyo Yuden                     | 1         | 0.08%   |
| Opticis                         | 1         | 0.08%   |
| Belkin Components               | 1         | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 246       | 19.25%  |
| Intel AX201 Bluetooth                               | 126       | 9.86%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 77        | 6.03%   |
| Intel AX200 Bluetooth                               | 62        | 4.85%   |
| Apple Bluetooth Host Controller                     | 55        | 4.3%    |
| Intel Bluetooth Device                              | 50        | 3.91%   |
| Realtek Bluetooth Radio                             | 42        | 3.29%   |
| Qualcomm Atheros  Bluetooth Device                  | 40        | 3.13%   |
| Apple Bluetooth USB Host Controller                 | 36        | 2.82%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 25        | 1.96%   |
| IMC Networks Bluetooth Radio                        | 24        | 1.88%   |
| Realtek  Bluetooth 4.2 Adapter                      | 23        | 1.8%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 22        | 1.72%   |
| Intel AX210 Bluetooth                               | 22        | 1.72%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 21        | 1.64%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 19        | 1.49%   |
| Foxconn / Hon Hai Bluetooth Device                  | 18        | 1.41%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 16        | 1.25%   |
| Broadcom BCM2045B (BDC-2.1)                         | 16        | 1.25%   |
| Ralink RT3290 Bluetooth                             | 15        | 1.17%   |
| Lite-On Atheros AR3012 Bluetooth                    | 15        | 1.17%   |
| IMC Networks Wireless_Device                        | 15        | 1.17%   |
| Toshiba Bluetooth Device                            | 13        | 1.02%   |
| HP Broadcom 2070 Bluetooth Combo                    | 13        | 1.02%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 11        | 0.86%   |
| Intel Wireless-AC 3168 Bluetooth                    | 11        | 0.86%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 10        | 0.78%   |
| Lite-On Bluetooth Device                            | 9         | 0.7%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 9         | 0.7%    |
| Foxconn / Hon Hai Wireless_Device                   | 9         | 0.7%    |
| Toshiba Integrated Bluetooth HCI                    | 8         | 0.63%   |
| Broadcom HP Portable SoftSailing                    | 8         | 0.63%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 8         | 0.63%   |
| Dell BCM20702A0 Bluetooth Module                    | 7         | 0.55%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 7         | 0.55%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 0.55%   |
| Realtek Bluetooth Radio                             | 6         | 0.47%   |
| Dell DW375 Bluetooth Module                         | 6         | 0.47%   |
| Broadcom BCM20702A0                                 | 6         | 0.47%   |
| IMC Networks Bluetooth                              | 5         | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1312      | 63.54%  |
| AMD                                          | 293       | 14.19%  |
| Nvidia                                       | 285       | 13.8%   |
| Realtek Semiconductor                        | 22        | 1.07%   |
| Apple                                        | 12        | 0.58%   |
| GN Netcom                                    | 11        | 0.53%   |
| Razer USA                                    | 9         | 0.44%   |
| Lenovo                                       | 9         | 0.44%   |
| Generalplus Technology                       | 9         | 0.44%   |
| C-Media Electronics                          | 9         | 0.44%   |
| Logitech                                     | 7         | 0.34%   |
| Kingston Technology                          | 6         | 0.29%   |
| Creative Technology                          | 6         | 0.29%   |
| Hewlett-Packard                              | 5         | 0.24%   |
| Texas Instruments                            | 4         | 0.19%   |
| Plantronics                                  | 4         | 0.19%   |
| JMTek                                        | 4         | 0.19%   |
| OPPO Electronics                             | 3         | 0.15%   |
| Native Instruments                           | 3         | 0.15%   |
| Microsoft                                    | 3         | 0.15%   |
| Corsair                                      | 3         | 0.15%   |
| Thermaltake                                  | 2         | 0.1%    |
| SteelSeries ApS                              | 2         | 0.1%    |
| Silicon Integrated Systems [SiS]             | 2         | 0.1%    |
| Sennheiser Communications                    | 2         | 0.1%    |
| Samsung Electronics                          | 2         | 0.1%    |
| Micro Star International                     | 2         | 0.1%    |
| M-Audio                                      | 2         | 0.1%    |
| Dell                                         | 2         | 0.1%    |
| Conexant Systems                             | 2         | 0.1%    |
| Chicony Electronics                          | 2         | 0.1%    |
| Blue Microphones                             | 2         | 0.1%    |
| Antlion Audio                                | 2         | 0.1%    |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.05%   |
| ZOOM                                         | 1         | 0.05%   |
| XMOS                                         | 1         | 0.05%   |
| ULi Electronics                              | 1         | 0.05%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.05%   |
| Spreadtrum Communications                    | 1         | 0.05%   |
| Sony                                         | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 193       | 7.84%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 156       | 6.33%   |
| AMD Family 17h/19h HD Audio Controller                                     | 120       | 4.87%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 116       | 4.71%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 85        | 3.45%   |
| Intel 8 Series HD Audio Controller                                         | 79        | 3.21%   |
| Intel Haswell-ULT HD Audio Controller                                      | 78        | 3.17%   |
| Intel Cannon Lake PCH cAVS                                                 | 73        | 2.96%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 66        | 2.68%   |
| Intel Broadwell-U Audio Controller                                         | 66        | 2.68%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 59        | 2.4%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 57        | 2.31%   |
| AMD FCH Azalia Controller                                                  | 57        | 2.31%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 55        | 2.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 48        | 1.95%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 47        | 1.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 45        | 1.83%   |
| Intel Comet Lake PCH cAVS                                                  | 39        | 1.58%   |
| AMD Kabini HDMI/DP Audio                                                   | 39        | 1.58%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 35        | 1.42%   |
| Intel Comet Lake PCH-LP cAVS                                               | 35        | 1.42%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 33        | 1.34%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 33        | 1.34%   |
| Intel CM238 HD Audio Controller                                            | 30        | 1.22%   |
| Nvidia GF108 High Definition Audio Controller                              | 28        | 1.14%   |
| AMD High Definition Audio Controller                                       | 28        | 1.14%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 26        | 1.06%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 25        | 1.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 25        | 1.02%   |
| Nvidia GK107 HDMI Audio Controller                                         | 24        | 0.97%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 23        | 0.93%   |
| Nvidia Audio device                                                        | 22        | 0.89%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 21        | 0.85%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 20        | 0.81%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 20        | 0.81%   |
| Realtek Semiconductor USB Audio                                            | 19        | 0.77%   |
| Nvidia TU116 High Definition Audio Controller                              | 19        | 0.77%   |
| Nvidia TU106 High Definition Audio Controller                              | 19        | 0.77%   |
| Nvidia GP107GL High Definition Audio Controller                            | 17        | 0.69%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 16        | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 295       | 31.55%  |
| SK hynix                   | 233       | 24.92%  |
| Micron Technology          | 133       | 14.22%  |
| Kingston                   | 77        | 8.24%   |
| Crucial                    | 47        | 5.03%   |
| Unknown                    | 32        | 3.42%   |
| Elpida                     | 25        | 2.67%   |
| Ramaxel Technology         | 12        | 1.28%   |
| Corsair                    | 12        | 1.28%   |
| Team                       | 10        | 1.07%   |
| Nanya Technology           | 10        | 1.07%   |
| A-DATA Technology          | 8         | 0.86%   |
| G.Skill                    | 6         | 0.64%   |
| Unknown                    | 6         | 0.64%   |
| Apacer                     | 4         | 0.43%   |
| Silicon Power              | 3         | 0.32%   |
| Unknown (ABCD)             | 2         | 0.21%   |
| Transcend                  | 2         | 0.21%   |
| Toshiba                    | 2         | 0.21%   |
| Smart                      | 2         | 0.21%   |
| Patriot                    | 2         | 0.21%   |
| Unknown (0x89AD)           | 1         | 0.11%   |
| Unknown (0x873E)           | 1         | 0.11%   |
| Qimonda                    | 1         | 0.11%   |
| pqi                        | 1         | 0.11%   |
| Netlist                    | 1         | 0.11%   |
| Neo Forza                  | 1         | 0.11%   |
| GSkill                     | 1         | 0.11%   |
| ff                         | 1         | 0.11%   |
| Avant                      | 1         | 0.11%   |
| ASint Technology           | 1         | 0.11%   |
| Anucell Technology Holding | 1         | 0.11%   |
| 4ea5                       | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 19        | 1.92%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 15        | 1.51%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 14        | 1.41%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 13        | 1.31%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 12        | 1.21%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 12        | 1.21%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 11        | 1.11%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 11        | 1.11%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 10        | 1.01%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 9         | 0.91%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 9         | 0.91%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 8         | 0.81%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 8         | 0.81%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 7         | 0.71%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s             | 7         | 0.71%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 7         | 0.71%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 7         | 0.71%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 7         | 0.71%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 7         | 0.71%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 7         | 0.71%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 6         | 0.6%    |
| SK hynix RAM H9HCNNNCPMALHR-NEE 8GB Row Of Chips LPDDR4 4800MT/s    | 6         | 0.6%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 6         | 0.6%    |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s       | 6         | 0.6%    |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                | 6         | 0.6%    |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s               | 6         | 0.6%    |
| Unknown                                                             | 6         | 0.6%    |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 5         | 0.5%    |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 5         | 0.5%    |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                        | 5         | 0.5%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 5         | 0.5%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 5         | 0.5%    |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s              | 5         | 0.5%    |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 5         | 0.5%    |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 5         | 0.5%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 5         | 0.5%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 5         | 0.5%    |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s              | 5         | 0.5%    |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s               | 5         | 0.5%    |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s               | 5         | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 343       | 42.56%  |
| DDR3    | 303       | 37.59%  |
| LPDDR3  | 50        | 6.2%    |
| LPDDR4  | 31        | 3.85%   |
| DDR2    | 27        | 3.35%   |
| LPDDR5  | 20        | 2.48%   |
| DDR5    | 16        | 1.99%   |
| SDRAM   | 10        | 1.24%   |
| Unknown | 3         | 0.37%   |
| DDR     | 2         | 0.25%   |
| DRAM    | 1         | 0.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 699       | 86.62%  |
| Row Of Chips | 94        | 11.65%  |
| Chip         | 10        | 1.24%   |
| Unknown      | 3         | 0.37%   |
| DIMM         | 1         | 0.12%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 343       | 39.79%  |
| 4096  | 232       | 26.91%  |
| 16384 | 147       | 17.05%  |
| 2048  | 91        | 10.56%  |
| 32768 | 31        | 3.6%    |
| 1024  | 12        | 1.39%   |
| 512   | 4         | 0.46%   |
| 1536  | 1         | 0.12%   |
| 256   | 1         | 0.12%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 213       | 24.54%  |
| 2667    | 175       | 20.16%  |
| 3200    | 132       | 15.21%  |
| 1334    | 57        | 6.57%   |
| 2133    | 51        | 5.88%   |
| 2400    | 46        | 5.3%    |
| 1333    | 26        | 3%      |
| 6400    | 20        | 2.3%    |
| 1867    | 20        | 2.3%    |
| 4800    | 19        | 2.19%   |
| 1067    | 18        | 2.07%   |
| 667     | 13        | 1.5%    |
| Unknown | 13        | 1.5%    |
| 4267    | 11        | 1.27%   |
| 4266    | 8         | 0.92%   |
| 8400    | 7         | 0.81%   |
| 3266    | 7         | 0.81%   |
| 1066    | 7         | 0.81%   |
| 800     | 6         | 0.69%   |
| 2048    | 4         | 0.46%   |
| 5600    | 3         | 0.35%   |
| 4199    | 3         | 0.35%   |
| 533     | 3         | 0.35%   |
| 3733    | 2         | 0.23%   |
| 975     | 2         | 0.23%   |
| 1776    | 1         | 0.12%   |
| 1639    | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 6         | 46.15%  |
| Hewlett-Packard     | 3         | 23.08%  |
| Canon               | 2         | 15.38%  |
| Samsung Electronics | 1         | 7.69%   |
| Dymo-CoStar         | 1         | 7.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Canon TS3100 series              | 2         | 14.29%  |
| Brother HL-1110 series           | 2         | 14.29%  |
| Samsung ML-1865                  | 1         | 7.14%   |
| HP LaserJet Pro M201dw           | 1         | 7.14%   |
| HP ENVY Inspire 7900 series      | 1         | 7.14%   |
| HP DeskJet 2300 series           | 1         | 7.14%   |
| Dymo-CoStar DYMO LabelWriter 4XL | 1         | 7.14%   |
| Brother Printer                  | 1         | 7.14%   |
| Brother MFC-1810                 | 1         | 7.14%   |
| Brother HL-2240D series          | 1         | 7.14%   |
| Brother HL-2140 series           | 1         | 7.14%   |
| Brother HL-1210W series          | 1         | 7.14%   |

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


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 373       | 25.92%  |
| Microdia                               | 132       | 9.17%   |
| Realtek Semiconductor                  | 117       | 8.13%   |
| IMC Networks                           | 115       | 7.99%   |
| Sunplus Innovation Technology          | 106       | 7.37%   |
| Apple                                  | 86        | 5.98%   |
| Quanta                                 | 63        | 4.38%   |
| Bison Electronics                      | 60        | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) | 56        | 3.89%   |
| Suyin                                  | 52        | 3.61%   |
| Acer                                   | 42        | 2.92%   |
| Logitech                               | 37        | 2.57%   |
| Lite-On Technology                     | 24        | 1.67%   |
| Syntek                                 | 21        | 1.46%   |
| Luxvisions Innotech Limited            | 19        | 1.32%   |
| Silicon Motion                         | 13        | 0.9%    |
| Samsung Electronics                    | 13        | 0.9%    |
| Importek                               | 12        | 0.83%   |
| Sonix Technology                       | 11        | 0.76%   |
| Ricoh                                  | 11        | 0.76%   |
| Alcor Micro                            | 9         | 0.63%   |
| Primax Electronics                     | 7         | 0.49%   |
| Lenovo                                 | 7         | 0.49%   |
| OmniVision Technologies                | 5         | 0.35%   |
| Razer USA                              | 4         | 0.28%   |
| Magic Control Technology               | 4         | 0.28%   |
| DigiTech                               | 4         | 0.28%   |
| ALi                                    | 4         | 0.28%   |
| Z-Star Microelectronics                | 3         | 0.21%   |
| USB Camera                             | 3         | 0.21%   |
| LG Electronics                         | 3         | 0.21%   |
| SunplusIT                              | 2         | 0.14%   |
| OPPO Electronics                       | 2         | 0.14%   |
| Microsoft                              | 2         | 0.14%   |
| Genesys Logic                          | 2         | 0.14%   |
| GEMBIRD                                | 2         | 0.14%   |
| Tobii Technology AB                    | 1         | 0.07%   |
| Sunplus Technology                     | 1         | 0.07%   |
| Solid Year                             | 1         | 0.07%   |
| Mimaki Engineering                     | 1         | 0.07%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 73        | 5%      |
| Chicony Integrated Camera                               | 70        | 4.79%   |
| Realtek Integrated_Webcam_HD                            | 40        | 2.74%   |
| Chicony HD Webcam                                       | 35        | 2.4%    |
| Sunplus Integrated_Webcam_HD                            | 32        | 2.19%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 31        | 2.12%   |
| Chicony TOSHIBA Web Camera - HD                         | 27        | 1.85%   |
| IMC Networks Integrated Camera                          | 25        | 1.71%   |
| Apple FaceTime HD Camera (Built-in)                     | 25        | 1.71%   |
| Realtek USB Camera                                      | 20        | 1.37%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                      | 20        | 1.37%   |
| Apple FaceTime HD Camera                                | 19        | 1.3%    |
| Apple Built-in iSight                                   | 19        | 1.3%    |
| Chicony HP TrueVision HD Camera                         | 18        | 1.23%   |
| Chicony HP TrueVision HD                                | 17        | 1.16%   |
| Chicony HD User Facing                                  | 16        | 1.1%    |
| Bison Integrated Camera                                 | 16        | 1.1%    |
| Sunplus HD WebCam                                       | 14        | 0.96%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 14        | 0.96%   |
| Syntek Integrated Camera                                | 13        | 0.89%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 13        | 0.89%   |
| Suyin HP Truevision HD                                  | 12        | 0.82%   |
| Chicony USB 2.0 Camera                                  | 12        | 0.82%   |
| Chicony HP HD Camera                                    | 12        | 0.82%   |
| Quanta HP TrueVision HD Camera                          | 11        | 0.75%   |
| Quanta HD User Facing                                   | 11        | 0.75%   |
| Lite-On Integrated Camera                               | 11        | 0.75%   |
| Chicony USB2.0 Camera                                   | 11        | 0.75%   |
| Chicony CNF9055 Toshiba Webcam                          | 11        | 0.75%   |
| Acer Integrated Camera                                  | 11        | 0.75%   |
| Microdia Integrated Webcam                              | 10        | 0.68%   |
| Chicony Integrated Camera (1280x720@30)                 | 10        | 0.68%   |
| Quanta HP Webcam                                        | 9         | 0.62%   |
| Chicony TOSHIBA Web Camera - FHD                        | 9         | 0.62%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera     | 9         | 0.62%   |
| Acer SunplusIT Integrated Camera                        | 9         | 0.62%   |
| Quanta HD Webcam                                        | 8         | 0.55%   |
| Logitech Webcam C270                                    | 8         | 0.55%   |
| Chicony VGA WebCam                                      | 8         | 0.55%   |
| Sonix USB2.0 FHD UVC WebCam                             | 7         | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 137       | 43.77%  |
| Synaptics                          | 64        | 20.45%  |
| Shenzhen Goodix Technology         | 35        | 11.18%  |
| LighTuning Technology              | 22        | 7.03%   |
| AuthenTec                          | 18        | 5.75%   |
| Upek                               | 14        | 4.47%   |
| Elan Microelectronics              | 14        | 4.47%   |
| STMicroelectronics                 | 7         | 2.24%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.32%   |
| Focal-systems.Corp                 | 1         | 0.32%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 29        | 9.27%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 28        | 8.95%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 14        | 4.47%   |
| Shenzhen Goodix  FingerPrint Device                                        | 13        | 4.15%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 13        | 4.15%   |
| Validity Sensors VFS491                                                    | 12        | 3.83%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 12        | 3.83%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 12        | 3.83%   |
| Validity Sensors Fingerprint scanner                                       | 12        | 3.83%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 11        | 3.51%   |
| Shenzhen Goodix Fingerprint Reader                                         | 11        | 3.51%   |
| Shenzhen Goodix FingerPrint                                                | 11        | 3.51%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 10        | 3.19%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 2.88%   |
| Validity Sensors VFS Fingerprint sensor                                    | 8         | 2.56%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 2.24%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 2.24%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 2.24%   |
| Elan ELAN:Fingerprint                                                      | 7         | 2.24%   |
| Elan ELAN:ARM-M4                                                           | 7         | 2.24%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 2.24%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.92%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 1.92%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 1.6%    |
| Synaptics WBDI Device                                                      | 5         | 1.6%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 1.28%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 1.28%   |
| AuthenTec AES1600                                                          | 4         | 1.28%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 0.96%   |
| Synaptics  WBDI                                                            | 3         | 0.96%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 0.96%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.96%   |
| Synaptics UWP WBDI Device                                                  | 2         | 0.64%   |
| Synaptics UWP WBDI                                                         | 2         | 0.64%   |
| Synaptics TouchPad                                                         | 2         | 0.64%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 0.64%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.64%   |
| AuthenTec AES2810                                                          | 2         | 0.64%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.64%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.32%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 41        | 62.12%  |
| Alcor Micro           | 14        | 21.21%  |
| Upek                  | 4         | 6.06%   |
| Lenovo                | 3         | 4.55%   |
| O2 Micro              | 2         | 3.03%   |
| Gemalto (was Gemplus) | 1         | 1.52%   |
| Advanced Card Systems | 1         | 1.52%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 18        | 27.27%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 14        | 21.21%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 12.12%  |
| Broadcom 58200                                                               | 8         | 12.12%  |
| Broadcom 5880                                                                | 7         | 10.61%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 6.06%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 4.55%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 3.03%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 1.52%   |
| Advanced Card Systems ACR122U                                                | 1         | 1.52%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 959       | 58.09%  |
| 1     | 562       | 34.04%  |
| 2     | 108       | 6.54%   |
| 3     | 15        | 0.91%   |
| 4     | 6         | 0.36%   |
| 5     | 1         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 310       | 38.41%  |
| Graphics card            | 171       | 21.19%  |
| Net/wireless             | 72        | 8.92%   |
| Multimedia controller    | 63        | 7.81%   |
| Chipcard                 | 60        | 7.43%   |
| Bluetooth                | 27        | 3.35%   |
| Camera                   | 25        | 3.1%    |
| Storage                  | 17        | 2.11%   |
| Net/ethernet             | 17        | 2.11%   |
| Communication controller | 14        | 1.73%   |
| Modem                    | 10        | 1.24%   |
| Sound                    | 8         | 0.99%   |
| Card reader              | 8         | 0.99%   |
| Video                    | 1         | 0.12%   |
| Unassigned class         | 1         | 0.12%   |
| Storage/ide              | 1         | 0.12%   |
| Storage/ata              | 1         | 0.12%   |
| Flash memory             | 1         | 0.12%   |


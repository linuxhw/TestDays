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

Total: 8273

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Pavilion g6                 | [795109303b](https://linux-hardware.org/?probe=795109303b) | Feb 02, 2024 |
| Dell          | G7 7588                     | [fdc746ce61](https://linux-hardware.org/?probe=fdc746ce61) | Feb 02, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [6d6e6af46b](https://linux-hardware.org/?probe=6d6e6af46b) | Feb 02, 2024 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [f659cc07fc](https://linux-hardware.org/?probe=f659cc07fc) | Feb 01, 2024 |
| Lenovo        | ThinkPad T480 20L50011US    | [bb6dd71048](https://linux-hardware.org/?probe=bb6dd71048) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [7adc6ac4b3](https://linux-hardware.org/?probe=7adc6ac4b3) | Feb 01, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [e94976b6d9](https://linux-hardware.org/?probe=e94976b6d9) | Feb 01, 2024 |
| Samsung       | 750XFH                      | [47d573ccf5](https://linux-hardware.org/?probe=47d573ccf5) | Feb 01, 2024 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [4e6e527f34](https://linux-hardware.org/?probe=4e6e527f34) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [16a348ccd1](https://linux-hardware.org/?probe=16a348ccd1) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [fc52040fc1](https://linux-hardware.org/?probe=fc52040fc1) | Feb 01, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [f833c48d57](https://linux-hardware.org/?probe=f833c48d57) | Feb 01, 2024 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [bc7890c0fe](https://linux-hardware.org/?probe=bc7890c0fe) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [ef62bb8257](https://linux-hardware.org/?probe=ef62bb8257) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [841cef0b98](https://linux-hardware.org/?probe=841cef0b98) | Feb 01, 2024 |
| HP            | Pavilion dv6                | [9d58677c2a](https://linux-hardware.org/?probe=9d58677c2a) | Feb 01, 2024 |
| ASUSTek       | X556UQK                     | [970dc5b87d](https://linux-hardware.org/?probe=970dc5b87d) | Jan 31, 2024 |
| Lenovo        | V330-14ARR 81B1             | [5dcee96cdb](https://linux-hardware.org/?probe=5dcee96cdb) | Jan 31, 2024 |
| Hot Pepper... | HPPMC10                     | [1bfdadd09f](https://linux-hardware.org/?probe=1bfdadd09f) | Jan 30, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [0b6e8d1e4b](https://linux-hardware.org/?probe=0b6e8d1e4b) | Jan 30, 2024 |
| Apple         | MacBook9,1                  | [e81979cbdf](https://linux-hardware.org/?probe=e81979cbdf) | Jan 29, 2024 |
| HP            | ProBook 4540s               | [ba6e31a8d3](https://linux-hardware.org/?probe=ba6e31a8d3) | Jan 29, 2024 |
| Acer          | Nitro AN515-58              | [dda1c0dfa9](https://linux-hardware.org/?probe=dda1c0dfa9) | Jan 29, 2024 |
| HP            | Laptop 15s-eq2xxx           | [0bba02c4c8](https://linux-hardware.org/?probe=0bba02c4c8) | Jan 29, 2024 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [9fcbf2b096](https://linux-hardware.org/?probe=9fcbf2b096) | Jan 29, 2024 |
| Dell          | Inspiron 3558               | [c347f95f5e](https://linux-hardware.org/?probe=c347f95f5e) | Jan 28, 2024 |
| ASUSTek       | X541UJ                      | [14f153b6c9](https://linux-hardware.org/?probe=14f153b6c9) | Jan 28, 2024 |
| HP            | Laptop 15-db0xxx            | [077619fc48](https://linux-hardware.org/?probe=077619fc48) | Jan 27, 2024 |
| Acer          | Aspire 6530G                | [cd71356945](https://linux-hardware.org/?probe=cd71356945) | Jan 26, 2024 |
| Lenovo        | ThinkPad T420 4236Y54       | [43bf0c55e8](https://linux-hardware.org/?probe=43bf0c55e8) | Jan 26, 2024 |
| MSI           | GF65 Thin 9SEXR             | [5be9da4fbd](https://linux-hardware.org/?probe=5be9da4fbd) | Jan 26, 2024 |
| Lenovo        | G460 0677                   | [d4624cb524](https://linux-hardware.org/?probe=d4624cb524) | Jan 26, 2024 |
| Dell          | XPS 15 9570                 | [4b9ba374ee](https://linux-hardware.org/?probe=4b9ba374ee) | Jan 25, 2024 |
| Acer          | Aspire VX5-591G             | [3e5671c66a](https://linux-hardware.org/?probe=3e5671c66a) | Jan 24, 2024 |
| MSI           | P65 Creator 9SE             | [863ad9098e](https://linux-hardware.org/?probe=863ad9098e) | Jan 24, 2024 |
| HP            | ProBook 4530s               | [db169567f6](https://linux-hardware.org/?probe=db169567f6) | Jan 24, 2024 |
| Toshiba       | Satellite C55-C             | [3f59e64e0e](https://linux-hardware.org/?probe=3f59e64e0e) | Jan 24, 2024 |
| System76      | Oryx Pro                    | [cb490beb63](https://linux-hardware.org/?probe=cb490beb63) | Jan 24, 2024 |
| Acer          | Nitro AN515-58              | [d195c1f908](https://linux-hardware.org/?probe=d195c1f908) | Jan 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [3bc0546f62](https://linux-hardware.org/?probe=3bc0546f62) | Jan 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [95692e9f04](https://linux-hardware.org/?probe=95692e9f04) | Jan 23, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [5d754d0510](https://linux-hardware.org/?probe=5d754d0510) | Jan 23, 2024 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [2f77e5be01](https://linux-hardware.org/?probe=2f77e5be01) | Jan 22, 2024 |
| Dell          | Inspiron 5490               | [e879f5dd00](https://linux-hardware.org/?probe=e879f5dd00) | Jan 22, 2024 |
| HP            | Laptop 14-fq1xxx            | [dcb0ce6ffa](https://linux-hardware.org/?probe=dcb0ce6ffa) | Jan 22, 2024 |
| HP            | Notebook                    | [efbf2736f3](https://linux-hardware.org/?probe=efbf2736f3) | Jan 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [9fd92c9632](https://linux-hardware.org/?probe=9fd92c9632) | Jan 20, 2024 |
| Acer          | Nitro AN515-57              | [e9423fb2cd](https://linux-hardware.org/?probe=e9423fb2cd) | Jan 19, 2024 |
| HP            | ProBook 450 G1              | [09fe6e6426](https://linux-hardware.org/?probe=09fe6e6426) | Jan 19, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [35c8f1855d](https://linux-hardware.org/?probe=35c8f1855d) | Jan 19, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [e555a2c32c](https://linux-hardware.org/?probe=e555a2c32c) | Jan 19, 2024 |
| HP            | ENVY TS 15                  | [4d83b8cef9](https://linux-hardware.org/?probe=4d83b8cef9) | Jan 19, 2024 |
| ASUSTek       | N55SL                       | [a6c913a5e2](https://linux-hardware.org/?probe=a6c913a5e2) | Jan 19, 2024 |
| Lenovo        | ThinkPad P52s 20LCS1H100    | [9efd333805](https://linux-hardware.org/?probe=9efd333805) | Jan 18, 2024 |
| Apple         | MacBookAir6,2               | [8f90ab1bfb](https://linux-hardware.org/?probe=8f90ab1bfb) | Jan 18, 2024 |
| Acer          | Swift SFX14-41G             | [612d6f9b0e](https://linux-hardware.org/?probe=612d6f9b0e) | Jan 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [048d450a50](https://linux-hardware.org/?probe=048d450a50) | Jan 17, 2024 |
| Lenovo        | ThinkPad T420 4236Y54       | [1364b82d7c](https://linux-hardware.org/?probe=1364b82d7c) | Jan 17, 2024 |
| HP            | EliteBook 840 G3            | [0b16d083fa](https://linux-hardware.org/?probe=0b16d083fa) | Jan 17, 2024 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [dd442d6fef](https://linux-hardware.org/?probe=dd442d6fef) | Jan 17, 2024 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | [3cdf937732](https://linux-hardware.org/?probe=3cdf937732) | Jan 17, 2024 |
| Compaq        | 430                         | [a8dc50fedd](https://linux-hardware.org/?probe=a8dc50fedd) | Jan 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [d124634554](https://linux-hardware.org/?probe=d124634554) | Jan 15, 2024 |
| Acer          | Swift SF315-52G             | [b1df864ab5](https://linux-hardware.org/?probe=b1df864ab5) | Jan 15, 2024 |
| ASUSTek       | X550JK                      | [1e70a82b32](https://linux-hardware.org/?probe=1e70a82b32) | Jan 15, 2024 |
| System76      | Pangolin                    | [bb8766a339](https://linux-hardware.org/?probe=bb8766a339) | Jan 15, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [6ede7a7cc8](https://linux-hardware.org/?probe=6ede7a7cc8) | Jan 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [19467f2a4d](https://linux-hardware.org/?probe=19467f2a4d) | Jan 14, 2024 |
| Acer          | Aspire 5560                 | [fcc49083ec](https://linux-hardware.org/?probe=fcc49083ec) | Jan 14, 2024 |
| Lenovo        | Legion Y740-15IRHg 81UH     | [f1b5487574](https://linux-hardware.org/?probe=f1b5487574) | Jan 13, 2024 |
| Samsung       | 550XED                      | [a9cdc1201c](https://linux-hardware.org/?probe=a9cdc1201c) | Jan 13, 2024 |
| HP            | EliteBook 840 G5            | [60f88b1f3f](https://linux-hardware.org/?probe=60f88b1f3f) | Jan 13, 2024 |
| HP            | Victus by Laptop 16-d0xx... | [3d70c9ce2f](https://linux-hardware.org/?probe=3d70c9ce2f) | Jan 13, 2024 |
| Dell          | Inspiron 5447               | [12ec54ffaf](https://linux-hardware.org/?probe=12ec54ffaf) | Jan 12, 2024 |
| Lenovo        | ThinkPad X260 20F5S4A901    | [75e671c163](https://linux-hardware.org/?probe=75e671c163) | Jan 12, 2024 |
| System76      | Adder WS                    | [94120ee028](https://linux-hardware.org/?probe=94120ee028) | Jan 11, 2024 |
| Lenovo        | ThinkPad P16v Gen 1 21FC... | [9066b38bfc](https://linux-hardware.org/?probe=9066b38bfc) | Jan 11, 2024 |
| Acer          | Swift SF314-54              | [c947abcab4](https://linux-hardware.org/?probe=c947abcab4) | Jan 11, 2024 |
| ASUSTek       | G73Jh                       | [9f34698cbf](https://linux-hardware.org/?probe=9f34698cbf) | Jan 11, 2024 |
| Dell          | Latitude E7240              | [5661525290](https://linux-hardware.org/?probe=5661525290) | Jan 11, 2024 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | [5e75e6b11a](https://linux-hardware.org/?probe=5e75e6b11a) | Jan 10, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [6462a9e611](https://linux-hardware.org/?probe=6462a9e611) | Jan 10, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [145f213442](https://linux-hardware.org/?probe=145f213442) | Jan 10, 2024 |
| ASUSTek       | N55SL                       | [b2c935edc3](https://linux-hardware.org/?probe=b2c935edc3) | Jan 10, 2024 |
| ASUSTek       | X550JK                      | [53f8040dbd](https://linux-hardware.org/?probe=53f8040dbd) | Jan 10, 2024 |
| Dell          | Precision 7510              | [8902e4fb7f](https://linux-hardware.org/?probe=8902e4fb7f) | Jan 10, 2024 |
| Lenovo        | ThinkPad S5-S540 20B3002... | [374798f039](https://linux-hardware.org/?probe=374798f039) | Jan 09, 2024 |
| Unknown       | Unknown                     | [76fb94009e](https://linux-hardware.org/?probe=76fb94009e) | Jan 09, 2024 |
| Acer          | Aspire A715-51G             | [d4a9b3c259](https://linux-hardware.org/?probe=d4a9b3c259) | Jan 09, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [b85af627bb](https://linux-hardware.org/?probe=b85af627bb) | Jan 09, 2024 |
| Dell          | Precision 5480              | [17ef519eb9](https://linux-hardware.org/?probe=17ef519eb9) | Jan 09, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [8107ad3adc](https://linux-hardware.org/?probe=8107ad3adc) | Jan 09, 2024 |
| Dell          | Precision 5560              | [947f10a53a](https://linux-hardware.org/?probe=947f10a53a) | Jan 09, 2024 |
| Apple         | MacBookPro11,4              | [a0e28b82f1](https://linux-hardware.org/?probe=a0e28b82f1) | Jan 08, 2024 |
| MSI           | P65 Creator 9SE             | [33a2ceb954](https://linux-hardware.org/?probe=33a2ceb954) | Jan 08, 2024 |
| Dell          | Vostro 5402                 | [4c1d546ae0](https://linux-hardware.org/?probe=4c1d546ae0) | Jan 08, 2024 |
| Lenovo        | ThinkPad X220 4291RD2       | [dc1b40ea6f](https://linux-hardware.org/?probe=dc1b40ea6f) | Jan 08, 2024 |
| Lenovo        | Y50-70 20378                | [1bd4e00b2a](https://linux-hardware.org/?probe=1bd4e00b2a) | Jan 08, 2024 |
| Lenovo        | IdeaPad 330S-15IKB D 81F... | [2068373a62](https://linux-hardware.org/?probe=2068373a62) | Jan 08, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | [e2b86aade4](https://linux-hardware.org/?probe=e2b86aade4) | Jan 07, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | [e9337be795](https://linux-hardware.org/?probe=e9337be795) | Jan 07, 2024 |
| HUAWEI        | CREM-WXX9                   | [29104c358b](https://linux-hardware.org/?probe=29104c358b) | Jan 07, 2024 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [040fa6a049](https://linux-hardware.org/?probe=040fa6a049) | Jan 07, 2024 |
| HP            | EliteBook 850 G6            | [605ea399c5](https://linux-hardware.org/?probe=605ea399c5) | Jan 07, 2024 |
| Apple         | MacBookPro8,1               | [cdc7802fc3](https://linux-hardware.org/?probe=cdc7802fc3) | Jan 07, 2024 |
| HP            | OMEN by Laptop 17-cb1xxx    | [8363cb44ef](https://linux-hardware.org/?probe=8363cb44ef) | Jan 06, 2024 |
| Apple         | MacBookPro11,1              | [fcf858ac50](https://linux-hardware.org/?probe=fcf858ac50) | Jan 06, 2024 |
| Apple         | MacBookPro11,1              | [a10fc58132](https://linux-hardware.org/?probe=a10fc58132) | Jan 06, 2024 |
| Dell          | XPS 15 9570                 | [8ca8b318eb](https://linux-hardware.org/?probe=8ca8b318eb) | Jan 06, 2024 |
| Lenovo        | ThinkPad X390 20Q1S7RB00    | [cfcb27d0b7](https://linux-hardware.org/?probe=cfcb27d0b7) | Jan 06, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [ae18260ba9](https://linux-hardware.org/?probe=ae18260ba9) | Jan 06, 2024 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [4572d32ab9](https://linux-hardware.org/?probe=4572d32ab9) | Jan 06, 2024 |
| Apple         | MacBookPro8,1               | [a620a3be8d](https://linux-hardware.org/?probe=a620a3be8d) | Jan 06, 2024 |
| Dell          | Latitude 3420               | [39d522ead5](https://linux-hardware.org/?probe=39d522ead5) | Jan 05, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [4c5cb3c1d4](https://linux-hardware.org/?probe=4c5cb3c1d4) | Jan 05, 2024 |
| Unknown       | Unknown                     | [d135277737](https://linux-hardware.org/?probe=d135277737) | Jan 05, 2024 |
| HP            | 83E9                        | [5794eaa509](https://linux-hardware.org/?probe=5794eaa509) | Jan 05, 2024 |
| HP            | 83E9                        | [ca6565530d](https://linux-hardware.org/?probe=ca6565530d) | Jan 05, 2024 |
| Unknown       | Unknown                     | [5e7209bd1a](https://linux-hardware.org/?probe=5e7209bd1a) | Jan 05, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 82Y... | [41a278e922](https://linux-hardware.org/?probe=41a278e922) | Jan 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [1973735eec](https://linux-hardware.org/?probe=1973735eec) | Jan 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [b1484cba42](https://linux-hardware.org/?probe=b1484cba42) | Jan 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [cb3946a0b0](https://linux-hardware.org/?probe=cb3946a0b0) | Jan 04, 2024 |
| Apple         | MacBookPro8,1               | [1593858ec2](https://linux-hardware.org/?probe=1593858ec2) | Jan 04, 2024 |
| Dell          | Latitude E5270              | [c0a4dbd80f](https://linux-hardware.org/?probe=c0a4dbd80f) | Jan 03, 2024 |
| Dell          | Vostro 3500                 | [70cf9e639e](https://linux-hardware.org/?probe=70cf9e639e) | Jan 03, 2024 |
| Lenovo        | Z50-75 80EC                 | [0e5397d3f1](https://linux-hardware.org/?probe=0e5397d3f1) | Jan 03, 2024 |
| HP            | OMEN by Laptop 15-dh0xxx    | [cd96de915f](https://linux-hardware.org/?probe=cd96de915f) | Jan 03, 2024 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | [d29c58fd8a](https://linux-hardware.org/?probe=d29c58fd8a) | Jan 03, 2024 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [95995dd66f](https://linux-hardware.org/?probe=95995dd66f) | Jan 03, 2024 |
| Lenovo        | ThinkPad T490 20RYS06R00    | [8fe843e69b](https://linux-hardware.org/?probe=8fe843e69b) | Jan 02, 2024 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | [09d807a864](https://linux-hardware.org/?probe=09d807a864) | Jan 02, 2024 |
| Acer          | SF314-71-50E8               | [b74d7acff4](https://linux-hardware.org/?probe=b74d7acff4) | Jan 02, 2024 |
| ASUSTek       | G75VX                       | [7f8494ffcf](https://linux-hardware.org/?probe=7f8494ffcf) | Jan 02, 2024 |
| Dell          | Latitude 5540               | [96e1aad010](https://linux-hardware.org/?probe=96e1aad010) | Jan 02, 2024 |
| System76      | Oryx Pro                    | [07e4e6a0a8](https://linux-hardware.org/?probe=07e4e6a0a8) | Jan 02, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [14df5ebb53](https://linux-hardware.org/?probe=14df5ebb53) | Jan 02, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [00ee13cdb6](https://linux-hardware.org/?probe=00ee13cdb6) | Jan 01, 2024 |
| Apple         | MacBookPro7,1               | [9181cf5581](https://linux-hardware.org/?probe=9181cf5581) | Jan 01, 2024 |
| MSI           | P65 Creator 9SE             | [2e5c1a6b06](https://linux-hardware.org/?probe=2e5c1a6b06) | Jan 01, 2024 |
| Lenovo        | ThinkPad P50 20EQS3YS00     | [34294e5b8b](https://linux-hardware.org/?probe=34294e5b8b) | Dec 31, 2023 |
| Apple         | MacBookPro10,2              | [386449d6f7](https://linux-hardware.org/?probe=386449d6f7) | Dec 31, 2023 |
| Dell          | Latitude 7480               | [9872ef6241](https://linux-hardware.org/?probe=9872ef6241) | Dec 31, 2023 |
| Dell          | Latitude 7480               | [527544c2de](https://linux-hardware.org/?probe=527544c2de) | Dec 31, 2023 |
| Google        | Delbin                      | [51a51a978d](https://linux-hardware.org/?probe=51a51a978d) | Dec 31, 2023 |
| Lenovo        | Y50-70 20378                | [ff5e2959f8](https://linux-hardware.org/?probe=ff5e2959f8) | Dec 31, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [b94c50cb10](https://linux-hardware.org/?probe=b94c50cb10) | Dec 30, 2023 |
| Acer          | Nitro AN515-58              | [a0039ef79d](https://linux-hardware.org/?probe=a0039ef79d) | Dec 30, 2023 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | [f48ada0e7b](https://linux-hardware.org/?probe=f48ada0e7b) | Dec 30, 2023 |
| Metabox       | Alpha-X NH58HP              | [983844e1c8](https://linux-hardware.org/?probe=983844e1c8) | Dec 30, 2023 |
| Acer          | SF314-71-50E8               | [a2704f17ea](https://linux-hardware.org/?probe=a2704f17ea) | Dec 29, 2023 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [bbe4e7af60](https://linux-hardware.org/?probe=bbe4e7af60) | Dec 29, 2023 |
| Lenovo        | B490 37722KP                | [194971e987](https://linux-hardware.org/?probe=194971e987) | Dec 29, 2023 |
| Lenovo        | ThinkPad L590 20Q8S0QB00    | [21c14a621b](https://linux-hardware.org/?probe=21c14a621b) | Dec 29, 2023 |
| ASUSTek       | G73Jh                       | [05dc836501](https://linux-hardware.org/?probe=05dc836501) | Dec 28, 2023 |
| Notebook      | NL40_50CU                   | [a91c55ef9f](https://linux-hardware.org/?probe=a91c55ef9f) | Dec 28, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [2e6989112a](https://linux-hardware.org/?probe=2e6989112a) | Dec 28, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603ZU... | [0f8be1187e](https://linux-hardware.org/?probe=0f8be1187e) | Dec 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a5c652bcef](https://linux-hardware.org/?probe=a5c652bcef) | Dec 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [02799d9fc9](https://linux-hardware.org/?probe=02799d9fc9) | Dec 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [341b25443b](https://linux-hardware.org/?probe=341b25443b) | Dec 28, 2023 |
| ASUSTek       | K75VM                       | [4f1fddffba](https://linux-hardware.org/?probe=4f1fddffba) | Dec 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [f2e13b11bd](https://linux-hardware.org/?probe=f2e13b11bd) | Dec 27, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [2eb4d57b39](https://linux-hardware.org/?probe=2eb4d57b39) | Dec 27, 2023 |
| Acer          | Swift SFX14-41G             | [72e733aa23](https://linux-hardware.org/?probe=72e733aa23) | Dec 27, 2023 |
| Acer          | Predator PHN16-71           | [f7d4fcd885](https://linux-hardware.org/?probe=f7d4fcd885) | Dec 27, 2023 |
| Acer          | Predator PHN16-71           | [865ecc4a8b](https://linux-hardware.org/?probe=865ecc4a8b) | Dec 27, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [8017d1c054](https://linux-hardware.org/?probe=8017d1c054) | Dec 27, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [db50c73272](https://linux-hardware.org/?probe=db50c73272) | Dec 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [34060a7062](https://linux-hardware.org/?probe=34060a7062) | Dec 26, 2023 |
| Dell          | Latitude E6520              | [634e14ff4c](https://linux-hardware.org/?probe=634e14ff4c) | Dec 25, 2023 |
| MicroByte     | ezbook                      | [a03eec4fc7](https://linux-hardware.org/?probe=a03eec4fc7) | Dec 25, 2023 |
| HP            | EliteBook 840 G5            | [f385a26e94](https://linux-hardware.org/?probe=f385a26e94) | Dec 25, 2023 |
| HP            | EliteBook 840 G5            | [744adae48d](https://linux-hardware.org/?probe=744adae48d) | Dec 25, 2023 |
| HP            | 255 G8 Notebook PC          | [1f14807c5e](https://linux-hardware.org/?probe=1f14807c5e) | Dec 25, 2023 |
| Lenovo        | ThinkPad T540p 20BFS0620... | [5cceadde0c](https://linux-hardware.org/?probe=5cceadde0c) | Dec 25, 2023 |
| PC Special... | N150CU                      | [5697f18262](https://linux-hardware.org/?probe=5697f18262) | Dec 24, 2023 |
| PC Special... | GK7NP5R                     | [1d97edcad7](https://linux-hardware.org/?probe=1d97edcad7) | Dec 23, 2023 |
| System76      | Serval WS                   | [92d124a8aa](https://linux-hardware.org/?probe=92d124a8aa) | Dec 23, 2023 |
| System76      | Gazelle                     | [6671df79bd](https://linux-hardware.org/?probe=6671df79bd) | Dec 23, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [f5f4795192](https://linux-hardware.org/?probe=f5f4795192) | Dec 22, 2023 |
| Dell          | Latitude E6430s             | [2b580a7725](https://linux-hardware.org/?probe=2b580a7725) | Dec 21, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [1e223a9ea1](https://linux-hardware.org/?probe=1e223a9ea1) | Dec 21, 2023 |
| DEXP          | Atlas M15-I3W302            | [176dd6f77a](https://linux-hardware.org/?probe=176dd6f77a) | Dec 20, 2023 |
| Acer          | Aspire VN7-591G             | [9a3cef62bc](https://linux-hardware.org/?probe=9a3cef62bc) | Dec 20, 2023 |
| HUAWEI        | KLVD-WXX9                   | [ff06842733](https://linux-hardware.org/?probe=ff06842733) | Dec 20, 2023 |
| Dell          | Precision 5680              | [b8b5bc0292](https://linux-hardware.org/?probe=b8b5bc0292) | Dec 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [00b16e835d](https://linux-hardware.org/?probe=00b16e835d) | Dec 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [0b6e9c4c26](https://linux-hardware.org/?probe=0b6e9c4c26) | Dec 20, 2023 |
| Apple         | MacBookPro8,1               | [24ff90d774](https://linux-hardware.org/?probe=24ff90d774) | Dec 20, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [a7044c8c2a](https://linux-hardware.org/?probe=a7044c8c2a) | Dec 19, 2023 |
| HUAWEI        | KLVD-WXX9                   | [5eca78aa43](https://linux-hardware.org/?probe=5eca78aa43) | Dec 19, 2023 |
| Dell          | Latitude E5270              | [c25a5b1bc7](https://linux-hardware.org/?probe=c25a5b1bc7) | Dec 19, 2023 |
| System76      | Pangolin                    | [a0cf57c6d1](https://linux-hardware.org/?probe=a0cf57c6d1) | Dec 19, 2023 |
| HP            | Dev One Notebook PC         | [b10cd89445](https://linux-hardware.org/?probe=b10cd89445) | Dec 19, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [e7ed0c7c8a](https://linux-hardware.org/?probe=e7ed0c7c8a) | Dec 18, 2023 |
| HP            | Dev One Notebook PC         | [3c5fc22ea0](https://linux-hardware.org/?probe=3c5fc22ea0) | Dec 17, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [f8cfc75a8a](https://linux-hardware.org/?probe=f8cfc75a8a) | Dec 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [6e359357d4](https://linux-hardware.org/?probe=6e359357d4) | Dec 17, 2023 |
| HP            | ProBook 4535s               | [80aa5bd12b](https://linux-hardware.org/?probe=80aa5bd12b) | Dec 17, 2023 |
| Dell          | Latitude E7450              | [f429af38c1](https://linux-hardware.org/?probe=f429af38c1) | Dec 17, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | [801f62b573](https://linux-hardware.org/?probe=801f62b573) | Dec 17, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | [d16bd87505](https://linux-hardware.org/?probe=d16bd87505) | Dec 17, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | [7f32922e8f](https://linux-hardware.org/?probe=7f32922e8f) | Dec 17, 2023 |
| Dell          | Latitude 5290 2-in-1        | [b90524a691](https://linux-hardware.org/?probe=b90524a691) | Dec 16, 2023 |
| Dell          | Inspiron 14 5420            | [ef0c78ce49](https://linux-hardware.org/?probe=ef0c78ce49) | Dec 16, 2023 |
| Dell          | XPS 15 9530                 | [c35aa056cf](https://linux-hardware.org/?probe=c35aa056cf) | Dec 16, 2023 |
| Apple         | MacBookAir7,2               | [d227968843](https://linux-hardware.org/?probe=d227968843) | Dec 16, 2023 |
| Toshiba       | TECRA Z50-A                 | [8717000b31](https://linux-hardware.org/?probe=8717000b31) | Dec 16, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [10f1017f04](https://linux-hardware.org/?probe=10f1017f04) | Dec 16, 2023 |
| realme        | RMNBXXXX                    | [c5e74761c7](https://linux-hardware.org/?probe=c5e74761c7) | Dec 15, 2023 |
| HP            | Laptop 15s-eq0xxx           | [cee2ad1e7c](https://linux-hardware.org/?probe=cee2ad1e7c) | Dec 15, 2023 |
| Toshiba       | IS 1413G                    | [09d89c7989](https://linux-hardware.org/?probe=09d89c7989) | Dec 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [4919d10355](https://linux-hardware.org/?probe=4919d10355) | Dec 14, 2023 |
| Samsung       | 300E5E/300E4E/300E5V/300... | [e7d5f85bea](https://linux-hardware.org/?probe=e7d5f85bea) | Dec 13, 2023 |
| Acer          | Swift SF314-57              | [5a796a43bd](https://linux-hardware.org/?probe=5a796a43bd) | Dec 12, 2023 |
| Apple         | MacBookPro11,1              | [539d1d09fe](https://linux-hardware.org/?probe=539d1d09fe) | Dec 11, 2023 |
| System76      | Lemur Pro                   | [05062ae2dd](https://linux-hardware.org/?probe=05062ae2dd) | Dec 10, 2023 |
| MSI           | GT72VR 6RD                  | [832dd09409](https://linux-hardware.org/?probe=832dd09409) | Dec 10, 2023 |
| MSI           | GT72VR 6RD                  | [b17b809ccf](https://linux-hardware.org/?probe=b17b809ccf) | Dec 10, 2023 |
| Acer          | Aspire A515-57              | [1adc377142](https://linux-hardware.org/?probe=1adc377142) | Dec 10, 2023 |
| ASUSTek       | X542URR                     | [3e42bedcd3](https://linux-hardware.org/?probe=3e42bedcd3) | Dec 10, 2023 |
| ASUSTek       | X550JK                      | [06e9cf1c8d](https://linux-hardware.org/?probe=06e9cf1c8d) | Dec 10, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [296e90c442](https://linux-hardware.org/?probe=296e90c442) | Dec 09, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [cea0431bcb](https://linux-hardware.org/?probe=cea0431bcb) | Dec 09, 2023 |
| Razer         | Blade                       | [bf9ad5f7df](https://linux-hardware.org/?probe=bf9ad5f7df) | Dec 09, 2023 |
| HP            | ZBook Firefly 15 inch G8... | [e7d15edec4](https://linux-hardware.org/?probe=e7d15edec4) | Dec 09, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [7fdc3ff8fd](https://linux-hardware.org/?probe=7fdc3ff8fd) | Dec 08, 2023 |
| ASUSTek       | G53SX                       | [6d01f19f82](https://linux-hardware.org/?probe=6d01f19f82) | Dec 08, 2023 |
| MSI           | GP66 Leopard 11UG           | [944218c6ec](https://linux-hardware.org/?probe=944218c6ec) | Dec 08, 2023 |
| Dell          | Inspiron 1525               | [0ee42c0440](https://linux-hardware.org/?probe=0ee42c0440) | Dec 08, 2023 |
| MSI           | GP66 Leopard 11UG           | [2499101d89](https://linux-hardware.org/?probe=2499101d89) | Dec 08, 2023 |
| Lenovo        | ThinkPad T460s 20FAS30D0... | [87477ed836](https://linux-hardware.org/?probe=87477ed836) | Dec 07, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [13080ba71b](https://linux-hardware.org/?probe=13080ba71b) | Dec 07, 2023 |
| HP            | EliteBook 845 14 inch G9... | [0d809d54ad](https://linux-hardware.org/?probe=0d809d54ad) | Dec 06, 2023 |
| HP            | ProBook 640 G5              | [419da197bb](https://linux-hardware.org/?probe=419da197bb) | Dec 05, 2023 |
| HP            | ProBook 640 G5              | [745d537d97](https://linux-hardware.org/?probe=745d537d97) | Dec 05, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | [48a8d668d9](https://linux-hardware.org/?probe=48a8d668d9) | Dec 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [2ace6b74e5](https://linux-hardware.org/?probe=2ace6b74e5) | Dec 04, 2023 |
| Lenovo        | G400 20235                  | [b3bc756e27](https://linux-hardware.org/?probe=b3bc756e27) | Dec 04, 2023 |
| Lenovo        | G400 20235                  | [9af224bc40](https://linux-hardware.org/?probe=9af224bc40) | Dec 04, 2023 |
| Acer          | Aspire A515-44G             | [7e41d52591](https://linux-hardware.org/?probe=7e41d52591) | Dec 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [a63677b9e1](https://linux-hardware.org/?probe=a63677b9e1) | Dec 03, 2023 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [1b6b67ba62](https://linux-hardware.org/?probe=1b6b67ba62) | Dec 03, 2023 |
| MSI           | Modern 14 B4MW              | [69c3f996db](https://linux-hardware.org/?probe=69c3f996db) | Dec 02, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [5568b58564](https://linux-hardware.org/?probe=5568b58564) | Dec 02, 2023 |
| Dell          | Latitude E7240              | [e5ac912c4c](https://linux-hardware.org/?probe=e5ac912c4c) | Dec 02, 2023 |
| Notebook      | NJ50_70CU                   | [613d0fb4a0](https://linux-hardware.org/?probe=613d0fb4a0) | Dec 01, 2023 |
| Dell          | XPS 15 9560                 | [17577fa161](https://linux-hardware.org/?probe=17577fa161) | Dec 01, 2023 |
| Dell          | Latitude E6420              | [ebd186f423](https://linux-hardware.org/?probe=ebd186f423) | Dec 01, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [ea481bfb9d](https://linux-hardware.org/?probe=ea481bfb9d) | Dec 01, 2023 |
| HP            | 15 Notebook PC              | [b431f0a398](https://linux-hardware.org/?probe=b431f0a398) | Dec 01, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [863d4d2b8f](https://linux-hardware.org/?probe=863d4d2b8f) | Nov 30, 2023 |
| ASUSTek       | Zenbook UX6404VI_UX6404V... | [e52dad2488](https://linux-hardware.org/?probe=e52dad2488) | Nov 30, 2023 |
| Acer          | Aspire A314-22              | [d91455d676](https://linux-hardware.org/?probe=d91455d676) | Nov 30, 2023 |
| Apple         | MacBookPro11,1              | [21a183f050](https://linux-hardware.org/?probe=21a183f050) | Nov 30, 2023 |
| HP            | Victus by Gaming Laptop ... | [2f5a407d09](https://linux-hardware.org/?probe=2f5a407d09) | Nov 29, 2023 |
| Dell          | Latitude 5420               | [56ad64e87a](https://linux-hardware.org/?probe=56ad64e87a) | Nov 29, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603ZI... | [f7d5f758c6](https://linux-hardware.org/?probe=f7d5f758c6) | Nov 29, 2023 |
| Dell          | Precision 3550              | [935b0dba56](https://linux-hardware.org/?probe=935b0dba56) | Nov 28, 2023 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [3531e02313](https://linux-hardware.org/?probe=3531e02313) | Nov 27, 2023 |
| Dell          | Precision M4700             | [e63ddd94ec](https://linux-hardware.org/?probe=e63ddd94ec) | Nov 27, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [abbb97fea2](https://linux-hardware.org/?probe=abbb97fea2) | Nov 27, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | [0bc55c4101](https://linux-hardware.org/?probe=0bc55c4101) | Nov 27, 2023 |
| Apple         | MacBookPro8,1               | [b305057bc5](https://linux-hardware.org/?probe=b305057bc5) | Nov 27, 2023 |
| ASUSTek       | GL553VW                     | [dba63ed53c](https://linux-hardware.org/?probe=dba63ed53c) | Nov 26, 2023 |
| HP            | ProBook 4540s               | [6f65f2ceeb](https://linux-hardware.org/?probe=6f65f2ceeb) | Nov 26, 2023 |
| HP            | Pavilion 14                 | [af5d0c670a](https://linux-hardware.org/?probe=af5d0c670a) | Nov 26, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [6007599bc5](https://linux-hardware.org/?probe=6007599bc5) | Nov 25, 2023 |
| Casper        | NIRVANA NOTEBOOK            | [a2fbff15e7](https://linux-hardware.org/?probe=a2fbff15e7) | Nov 25, 2023 |
| HP            | Laptop 15-fc0xxx            | [6f3cf47d7d](https://linux-hardware.org/?probe=6f3cf47d7d) | Nov 25, 2023 |
| Dell          | Studio XPS 1640             | [3b9a32eb3f](https://linux-hardware.org/?probe=3b9a32eb3f) | Nov 24, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | [4515ea6be6](https://linux-hardware.org/?probe=4515ea6be6) | Nov 24, 2023 |
| HP            | EliteBook 840 G5            | [4e7c1f967f](https://linux-hardware.org/?probe=4e7c1f967f) | Nov 24, 2023 |
| HP            | EliteBook 840 G5            | [a886bd351a](https://linux-hardware.org/?probe=a886bd351a) | Nov 24, 2023 |
| HP            | EliteBook 840 G5            | [386171f14d](https://linux-hardware.org/?probe=386171f14d) | Nov 24, 2023 |
| HP            | EliteBook 840 G5            | [ac1dfd9609](https://linux-hardware.org/?probe=ac1dfd9609) | Nov 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [2c505c0b1e](https://linux-hardware.org/?probe=2c505c0b1e) | Nov 24, 2023 |
| Acer          | Swift SF314-41              | [23f539995b](https://linux-hardware.org/?probe=23f539995b) | Nov 24, 2023 |
| Dell          | Inspiron 1750               | [4d256b493c](https://linux-hardware.org/?probe=4d256b493c) | Nov 23, 2023 |
| Casper        | NIRVANA NOTEBOOK            | [2127112b3a](https://linux-hardware.org/?probe=2127112b3a) | Nov 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [8416c7e558](https://linux-hardware.org/?probe=8416c7e558) | Nov 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [9aada56395](https://linux-hardware.org/?probe=9aada56395) | Nov 23, 2023 |
| Acer          | Aspire 5733                 | [7b6e215012](https://linux-hardware.org/?probe=7b6e215012) | Nov 22, 2023 |
| Acer          | Aspire A515-51              | [b8a36c00e8](https://linux-hardware.org/?probe=b8a36c00e8) | Nov 22, 2023 |
| Dell          | XPS 15 9530                 | [2720b6f6d4](https://linux-hardware.org/?probe=2720b6f6d4) | Nov 22, 2023 |
| MSI           | Prestige 15 A10SC           | [e1abb4721b](https://linux-hardware.org/?probe=e1abb4721b) | Nov 21, 2023 |
| Dell          | Inspiron 5547               | [d679a12a36](https://linux-hardware.org/?probe=d679a12a36) | Nov 21, 2023 |
| MSI           | Stealth 16Studio A13VG      | [03d7d46dd0](https://linux-hardware.org/?probe=03d7d46dd0) | Nov 21, 2023 |
| Samsung       | RC530/RC730                 | [8d328f4394](https://linux-hardware.org/?probe=8d328f4394) | Nov 21, 2023 |
| Acer          | Aspire 5733                 | [348094cd98](https://linux-hardware.org/?probe=348094cd98) | Nov 21, 2023 |
| Lenovo        | ThinkPad Helix 3701CTO      | [f200cae4b1](https://linux-hardware.org/?probe=f200cae4b1) | Nov 20, 2023 |
| Lenovo        | ThinkPad E520 11437UG       | [422931d9a6](https://linux-hardware.org/?probe=422931d9a6) | Nov 19, 2023 |
| Dell          | Latitude E6330              | [3c6e547f2a](https://linux-hardware.org/?probe=3c6e547f2a) | Nov 19, 2023 |
| Notebook      | NS5x_NS7xPU                 | [7e047fc166](https://linux-hardware.org/?probe=7e047fc166) | Nov 19, 2023 |
| MSI           | GE76 Raider 11UE            | [9d0a216d82](https://linux-hardware.org/?probe=9d0a216d82) | Nov 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [91f7d584f3](https://linux-hardware.org/?probe=91f7d584f3) | Nov 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [ef77e621d0](https://linux-hardware.org/?probe=ef77e621d0) | Nov 19, 2023 |
| MSI           | Cyborg 15 A12VF             | [fc41df67a4](https://linux-hardware.org/?probe=fc41df67a4) | Nov 19, 2023 |
| HP            | Victus by Gaming Laptop ... | [d086db0563](https://linux-hardware.org/?probe=d086db0563) | Nov 18, 2023 |
| Dell          | XPS 13 7390                 | [4735287055](https://linux-hardware.org/?probe=4735287055) | Nov 18, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [c7b3d39644](https://linux-hardware.org/?probe=c7b3d39644) | Nov 17, 2023 |
| HP            | 250 G8 Notebook PC          | [a6d12193c7](https://linux-hardware.org/?probe=a6d12193c7) | Nov 17, 2023 |
| Dell          | Precision 5680              | [a2957d2ece](https://linux-hardware.org/?probe=a2957d2ece) | Nov 16, 2023 |
| Dell          | Precision 5680              | [2c6c6027a6](https://linux-hardware.org/?probe=2c6c6027a6) | Nov 16, 2023 |
| MSI           | Katana GF66 11UE            | [07a03ff43b](https://linux-hardware.org/?probe=07a03ff43b) | Nov 16, 2023 |
| Lenovo        | ThinkPad E550 20DF001HAU    | [44968b500c](https://linux-hardware.org/?probe=44968b500c) | Nov 16, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [fade86e55e](https://linux-hardware.org/?probe=fade86e55e) | Nov 16, 2023 |
| Apple         | MacBookPro8,1               | [68dbf5814b](https://linux-hardware.org/?probe=68dbf5814b) | Nov 15, 2023 |
| Notebook      | PA70Hx                      | [14799f850b](https://linux-hardware.org/?probe=14799f850b) | Nov 15, 2023 |
| HP            | ProBook 4540s               | [48705484f5](https://linux-hardware.org/?probe=48705484f5) | Nov 15, 2023 |
| Dell          | XPS 9320                    | [f0435ea4b7](https://linux-hardware.org/?probe=f0435ea4b7) | Nov 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [386519f50c](https://linux-hardware.org/?probe=386519f50c) | Nov 15, 2023 |
| Acer          | Aspire V3-471G              | [f027c1d470](https://linux-hardware.org/?probe=f027c1d470) | Nov 14, 2023 |
| Dell          | XPS 15 7590                 | [da50e3550f](https://linux-hardware.org/?probe=da50e3550f) | Nov 14, 2023 |
| HP            | ProBook 4540s               | [f8e4ef7043](https://linux-hardware.org/?probe=f8e4ef7043) | Nov 14, 2023 |
| MSI           | Cyborg 15 A12VF             | [3cd966cd6a](https://linux-hardware.org/?probe=3cd966cd6a) | Nov 14, 2023 |
| System76      | Adder WS                    | [7135955eda](https://linux-hardware.org/?probe=7135955eda) | Nov 13, 2023 |
| ASUSTek       | X55U                        | [04a09add31](https://linux-hardware.org/?probe=04a09add31) | Nov 13, 2023 |
| Dell          | Precision 7720              | [1f358e68ee](https://linux-hardware.org/?probe=1f358e68ee) | Nov 13, 2023 |
| Dell          | Precision 7720              | [facdc5c2a4](https://linux-hardware.org/?probe=facdc5c2a4) | Nov 13, 2023 |
| MSI           | GT70                        | [e2c0bb5bfe](https://linux-hardware.org/?probe=e2c0bb5bfe) | Nov 13, 2023 |
| HP            | Laptop 14-dq2xxx            | [e384b513f0](https://linux-hardware.org/?probe=e384b513f0) | Nov 13, 2023 |
| Unknown       | Unknown                     | [f9ee628d93](https://linux-hardware.org/?probe=f9ee628d93) | Nov 13, 2023 |
| System76      | Lemur Pro                   | [35e6e1214c](https://linux-hardware.org/?probe=35e6e1214c) | Nov 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [b9ad1f18d8](https://linux-hardware.org/?probe=b9ad1f18d8) | Nov 12, 2023 |
| MSI           | Delta 15 A5EFK              | [091eaf746f](https://linux-hardware.org/?probe=091eaf746f) | Nov 12, 2023 |
| Google        | Edgar                       | [838bd73737](https://linux-hardware.org/?probe=838bd73737) | Nov 12, 2023 |
| Google        | Edgar                       | [42f8059f62](https://linux-hardware.org/?probe=42f8059f62) | Nov 11, 2023 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | [1946d2a10c](https://linux-hardware.org/?probe=1946d2a10c) | Nov 11, 2023 |
| HP            | G42                         | [8a331f427d](https://linux-hardware.org/?probe=8a331f427d) | Nov 11, 2023 |
| Dell          | Inspiron 1525               | [d9b24edac8](https://linux-hardware.org/?probe=d9b24edac8) | Nov 11, 2023 |
| Dell          | Latitude E5420              | [ac31e56717](https://linux-hardware.org/?probe=ac31e56717) | Nov 11, 2023 |
| Notebook      | PA70Hx                      | [f22d74d5eb](https://linux-hardware.org/?probe=f22d74d5eb) | Nov 11, 2023 |
| HP            | Pavilion g7                 | [f963761c30](https://linux-hardware.org/?probe=f963761c30) | Nov 10, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | [0cacf99f8a](https://linux-hardware.org/?probe=0cacf99f8a) | Nov 09, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [93d7b2bcdc](https://linux-hardware.org/?probe=93d7b2bcdc) | Nov 09, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [0bb1ba6267](https://linux-hardware.org/?probe=0bb1ba6267) | Nov 09, 2023 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | [03b4295585](https://linux-hardware.org/?probe=03b4295585) | Nov 09, 2023 |
| Dell          | Inspiron 1525               | [ab3577cc31](https://linux-hardware.org/?probe=ab3577cc31) | Nov 09, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [b221326a48](https://linux-hardware.org/?probe=b221326a48) | Nov 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [c048c3b791](https://linux-hardware.org/?probe=c048c3b791) | Nov 09, 2023 |
| HP            | G42                         | [f440217af5](https://linux-hardware.org/?probe=f440217af5) | Nov 09, 2023 |
| Dell          | Precision 5520              | [1166f1d95d](https://linux-hardware.org/?probe=1166f1d95d) | Nov 08, 2023 |
| Dell          | Latitude E7270              | [0410c1ba06](https://linux-hardware.org/?probe=0410c1ba06) | Nov 08, 2023 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [d2ce7f8ca6](https://linux-hardware.org/?probe=d2ce7f8ca6) | Nov 08, 2023 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [e4f3bd771d](https://linux-hardware.org/?probe=e4f3bd771d) | Nov 08, 2023 |
| HONOR         | NBR-WAX9                    | [173692c48a](https://linux-hardware.org/?probe=173692c48a) | Nov 08, 2023 |
| Acer          | Aspire A517-51              | [9b0700130f](https://linux-hardware.org/?probe=9b0700130f) | Nov 08, 2023 |
| System76      | Lemur Pro                   | [92d1345459](https://linux-hardware.org/?probe=92d1345459) | Nov 07, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [c28217d1ed](https://linux-hardware.org/?probe=c28217d1ed) | Nov 07, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [41fd02095e](https://linux-hardware.org/?probe=41fd02095e) | Nov 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [9755c6bf31](https://linux-hardware.org/?probe=9755c6bf31) | Nov 06, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [c2ae66ef2b](https://linux-hardware.org/?probe=c2ae66ef2b) | Nov 06, 2023 |
| Dell          | Vostro 5402                 | [2716ef5f71](https://linux-hardware.org/?probe=2716ef5f71) | Nov 06, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [7cc876dcfa](https://linux-hardware.org/?probe=7cc876dcfa) | Nov 06, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [290be8911e](https://linux-hardware.org/?probe=290be8911e) | Nov 06, 2023 |
| Acer          | Aspire 5750G                | [a782c6c087](https://linux-hardware.org/?probe=a782c6c087) | Nov 05, 2023 |
| Lenovo        | IdeaPad 330-17ICH 81FL      | [e25bb48957](https://linux-hardware.org/?probe=e25bb48957) | Nov 05, 2023 |
| MSI           | Cyborg 15 A12VF             | [be39067306](https://linux-hardware.org/?probe=be39067306) | Nov 05, 2023 |
| ASUSTek       | G53SX                       | [7834b537a1](https://linux-hardware.org/?probe=7834b537a1) | Nov 05, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [f1d00fbb93](https://linux-hardware.org/?probe=f1d00fbb93) | Nov 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [1db5fee13c](https://linux-hardware.org/?probe=1db5fee13c) | Nov 05, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [50306c96e2](https://linux-hardware.org/?probe=50306c96e2) | Nov 05, 2023 |
| Google        | Taeko                       | [d148b001d9](https://linux-hardware.org/?probe=d148b001d9) | Nov 05, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [279f1b8b4f](https://linux-hardware.org/?probe=279f1b8b4f) | Nov 05, 2023 |
| System76      | Lemur Pro                   | [dacc229f22](https://linux-hardware.org/?probe=dacc229f22) | Nov 04, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [cfdf343144](https://linux-hardware.org/?probe=cfdf343144) | Nov 04, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [237bd5cfb2](https://linux-hardware.org/?probe=237bd5cfb2) | Nov 04, 2023 |
| System76      | Lemur Pro                   | [80b1ef75d6](https://linux-hardware.org/?probe=80b1ef75d6) | Nov 04, 2023 |
| System76      | Oryx Pro                    | [ea89273272](https://linux-hardware.org/?probe=ea89273272) | Nov 04, 2023 |
| HP            | 655                         | [8cf9aa61c7](https://linux-hardware.org/?probe=8cf9aa61c7) | Nov 04, 2023 |
| Apple         | MacBookAir6,2               | [f8507f333d](https://linux-hardware.org/?probe=f8507f333d) | Nov 04, 2023 |
| MSI           | Bravo 15 C7VE               | [5db0e7314a](https://linux-hardware.org/?probe=5db0e7314a) | Nov 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [972ef88623](https://linux-hardware.org/?probe=972ef88623) | Nov 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [927b50091e](https://linux-hardware.org/?probe=927b50091e) | Nov 04, 2023 |
| System76      | Oryx Pro                    | [1704acc89b](https://linux-hardware.org/?probe=1704acc89b) | Nov 03, 2023 |
| Lenovo        | ThinkPad T420s 417032U      | [76247c39f4](https://linux-hardware.org/?probe=76247c39f4) | Nov 03, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [3a8d337535](https://linux-hardware.org/?probe=3a8d337535) | Nov 03, 2023 |
| HP            | ProBook 6450b               | [75ad2cf5f8](https://linux-hardware.org/?probe=75ad2cf5f8) | Nov 02, 2023 |
| MSI           | Prestige 14Evo A11M         | [12414485a5](https://linux-hardware.org/?probe=12414485a5) | Nov 02, 2023 |
| Apple         | MacBookPro14,1              | [7d93bb6f25](https://linux-hardware.org/?probe=7d93bb6f25) | Nov 02, 2023 |
| ASUSTek       | N550JV                      | [200e3255d9](https://linux-hardware.org/?probe=200e3255d9) | Nov 02, 2023 |
| ASUSTek       | N550JV                      | [43a84b57f0](https://linux-hardware.org/?probe=43a84b57f0) | Nov 01, 2023 |
| Lenovo        | ThinkPad T480 20L6S68T00    | [dba91e5612](https://linux-hardware.org/?probe=dba91e5612) | Nov 01, 2023 |
| HP            | ENVY 15                     | [74dae44745](https://linux-hardware.org/?probe=74dae44745) | Nov 01, 2023 |
| Lenovo        | ThinkPad X260 20F5A28AUK    | [c1e44a55c8](https://linux-hardware.org/?probe=c1e44a55c8) | Nov 01, 2023 |
| Lenovo        | ThinkPad X260 20F5A28AUK    | [84ca0a285d](https://linux-hardware.org/?probe=84ca0a285d) | Nov 01, 2023 |
| Dell          | XPS 15 9520                 | [6b6da0ca4a](https://linux-hardware.org/?probe=6b6da0ca4a) | Nov 01, 2023 |
| System76      | Lemur Pro                   | [847ae1ea8d](https://linux-hardware.org/?probe=847ae1ea8d) | Nov 01, 2023 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [643c7ccd9b](https://linux-hardware.org/?probe=643c7ccd9b) | Nov 01, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [f08e4e21a0](https://linux-hardware.org/?probe=f08e4e21a0) | Nov 01, 2023 |
| HUAWEI        | CREF-XX                     | [a10aa3c3e5](https://linux-hardware.org/?probe=a10aa3c3e5) | Oct 31, 2023 |
| MSI           | GP66 Leopard 11UG           | [cb013304f5](https://linux-hardware.org/?probe=cb013304f5) | Oct 31, 2023 |
| MSI           | GP66 Leopard 11UG           | [d6ac483e43](https://linux-hardware.org/?probe=d6ac483e43) | Oct 31, 2023 |
| Lenovo        | G50-80 80E5                 | [ee528fce07](https://linux-hardware.org/?probe=ee528fce07) | Oct 31, 2023 |
| Lenovo        | G50-80 80E5                 | [4e0042e20c](https://linux-hardware.org/?probe=4e0042e20c) | Oct 31, 2023 |
| Acer          | Aspire E5-553G              | [7c76f143a4](https://linux-hardware.org/?probe=7c76f143a4) | Oct 31, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [56f24de5ff](https://linux-hardware.org/?probe=56f24de5ff) | Oct 30, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [81a7cabe4f](https://linux-hardware.org/?probe=81a7cabe4f) | Oct 30, 2023 |
| HP            | Dev One Notebook PC         | [d5ace42b13](https://linux-hardware.org/?probe=d5ace42b13) | Oct 30, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [d51c491524](https://linux-hardware.org/?probe=d51c491524) | Oct 30, 2023 |
| Apple         | MacBookAir6,2               | [65f24e332a](https://linux-hardware.org/?probe=65f24e332a) | Oct 30, 2023 |
| System76      | Adder WS                    | [57478f4561](https://linux-hardware.org/?probe=57478f4561) | Oct 30, 2023 |
| System76      | Adder WS                    | [a10fcac3f4](https://linux-hardware.org/?probe=a10fcac3f4) | Oct 30, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [5863bd6189](https://linux-hardware.org/?probe=5863bd6189) | Oct 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [7301c9b3df](https://linux-hardware.org/?probe=7301c9b3df) | Oct 29, 2023 |
| Apple         | MacBookPro5,5               | [2815a5477f](https://linux-hardware.org/?probe=2815a5477f) | Oct 29, 2023 |
| SLIMBOOK      | TITAN                       | [8697e4de09](https://linux-hardware.org/?probe=8697e4de09) | Oct 29, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [c90dd43290](https://linux-hardware.org/?probe=c90dd43290) | Oct 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [d621a72336](https://linux-hardware.org/?probe=d621a72336) | Oct 28, 2023 |
| Lenovo        | ThinkPad T480 20L6S68T00    | [57e3abc23d](https://linux-hardware.org/?probe=57e3abc23d) | Oct 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [0f9adbc34d](https://linux-hardware.org/?probe=0f9adbc34d) | Oct 28, 2023 |
| Maibenben     | MaiBook X series            | [63e0cb487a](https://linux-hardware.org/?probe=63e0cb487a) | Oct 28, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [e08a8fa43b](https://linux-hardware.org/?probe=e08a8fa43b) | Oct 28, 2023 |
| Apple         | MacBookAir6,2               | [96b76fc377](https://linux-hardware.org/?probe=96b76fc377) | Oct 28, 2023 |
| Lenovo        | Z50-70 20354                | [2e5ee0032d](https://linux-hardware.org/?probe=2e5ee0032d) | Oct 27, 2023 |
| System76      | Lemur Pro                   | [e5b2c76907](https://linux-hardware.org/?probe=e5b2c76907) | Oct 27, 2023 |
| Samsung       | 550XCJ/550XCR               | [9d34ff8710](https://linux-hardware.org/?probe=9d34ff8710) | Oct 27, 2023 |
| System76      | Darter Pro                  | [9dcbc85a23](https://linux-hardware.org/?probe=9dcbc85a23) | Oct 27, 2023 |
| HP            | OMEN LAPTOP - 15-EK0013D... | [0c582fd597](https://linux-hardware.org/?probe=0c582fd597) | Oct 27, 2023 |
| Acer          | Aspire A315-42G             | [114e1e6d66](https://linux-hardware.org/?probe=114e1e6d66) | Oct 27, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [f0641b8822](https://linux-hardware.org/?probe=f0641b8822) | Oct 26, 2023 |
| Haier         | U1520SD                     | [3de6c48f15](https://linux-hardware.org/?probe=3de6c48f15) | Oct 26, 2023 |
| Dell          | Latitude E6530              | [ec57b86fe6](https://linux-hardware.org/?probe=ec57b86fe6) | Oct 26, 2023 |
| Acer          | Aspire VN7-793G             | [e4a7d4f368](https://linux-hardware.org/?probe=e4a7d4f368) | Oct 26, 2023 |
| Panasonic     | CF-31SBM08DM                | [820f042ba6](https://linux-hardware.org/?probe=820f042ba6) | Oct 26, 2023 |
| Haier         | U1520SD                     | [25229c3d32](https://linux-hardware.org/?probe=25229c3d32) | Oct 25, 2023 |
| Dell          | Inspiron 3442               | [7fc2a154e5](https://linux-hardware.org/?probe=7fc2a154e5) | Oct 25, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [9a4561dabf](https://linux-hardware.org/?probe=9a4561dabf) | Oct 25, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [ecde45a506](https://linux-hardware.org/?probe=ecde45a506) | Oct 24, 2023 |
| Apple         | MacBookAir6,2               | [f15ecd1759](https://linux-hardware.org/?probe=f15ecd1759) | Oct 24, 2023 |
| Dell          | Latitude E7240              | [6fead70e93](https://linux-hardware.org/?probe=6fead70e93) | Oct 23, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [47fdb21256](https://linux-hardware.org/?probe=47fdb21256) | Oct 23, 2023 |
| Dell          | XPS 13 9370                 | [7e9d761b35](https://linux-hardware.org/?probe=7e9d761b35) | Oct 23, 2023 |
| MSI           | Sword 15 A11UD              | [d07a7c777c](https://linux-hardware.org/?probe=d07a7c777c) | Oct 23, 2023 |
| HP            | EliteBook 820 G3            | [73c1b49eab](https://linux-hardware.org/?probe=73c1b49eab) | Oct 23, 2023 |
| HP            | EliteBook 820 G3            | [b6169d3a96](https://linux-hardware.org/?probe=b6169d3a96) | Oct 23, 2023 |
| ASUSTek       | G750JW                      | [9bafdb8250](https://linux-hardware.org/?probe=9bafdb8250) | Oct 22, 2023 |
| Dell          | Latitude 5520               | [f5664b02d2](https://linux-hardware.org/?probe=f5664b02d2) | Oct 22, 2023 |
| Toshiba       | Satellite C70D-B            | [7f1637fdb9](https://linux-hardware.org/?probe=7f1637fdb9) | Oct 22, 2023 |
| ASUSTek       | G53SX                       | [d19756d24b](https://linux-hardware.org/?probe=d19756d24b) | Oct 22, 2023 |
| Acer          | Aspire A315-23              | [14ed4adf6c](https://linux-hardware.org/?probe=14ed4adf6c) | Oct 22, 2023 |
| EUROCOM       | Tornado F5                  | [3056eeecf5](https://linux-hardware.org/?probe=3056eeecf5) | Oct 21, 2023 |
| ASUSTek       | N551JK                      | [010dd78352](https://linux-hardware.org/?probe=010dd78352) | Oct 21, 2023 |
| EUROCOM       | Tornado F5                  | [25b7095754](https://linux-hardware.org/?probe=25b7095754) | Oct 21, 2023 |
| MSI           | Cyborg 15 A12VF             | [b1a3bf1a75](https://linux-hardware.org/?probe=b1a3bf1a75) | Oct 21, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [97d1264314](https://linux-hardware.org/?probe=97d1264314) | Oct 21, 2023 |
| HONOR         | NBR-WAX9                    | [5966a36809](https://linux-hardware.org/?probe=5966a36809) | Oct 21, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a2756e1d2b](https://linux-hardware.org/?probe=a2756e1d2b) | Oct 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [148be53a91](https://linux-hardware.org/?probe=148be53a91) | Oct 20, 2023 |
| Toshiba       | Satellite C70D-B            | [793d71f1d2](https://linux-hardware.org/?probe=793d71f1d2) | Oct 20, 2023 |
| Lenovo        | Y50-70 20378                | [e51b067a88](https://linux-hardware.org/?probe=e51b067a88) | Oct 20, 2023 |
| Acer          | Swift SFX14-51G             | [2adde1171a](https://linux-hardware.org/?probe=2adde1171a) | Oct 20, 2023 |
| ASUSTek       | X551MA                      | [6ee41b351a](https://linux-hardware.org/?probe=6ee41b351a) | Oct 20, 2023 |
| Acer          | Aspire 5253                 | [871f28b131](https://linux-hardware.org/?probe=871f28b131) | Oct 20, 2023 |
| Dell          | Latitude 5520               | [281fdb7e86](https://linux-hardware.org/?probe=281fdb7e86) | Oct 20, 2023 |
| HP            | Pavilion 17                 | [36613b2f1f](https://linux-hardware.org/?probe=36613b2f1f) | Oct 19, 2023 |
| MSI           | Cyborg 15 A12VF             | [7fab57f39a](https://linux-hardware.org/?probe=7fab57f39a) | Oct 19, 2023 |
| Acer          | Aspire VN7-591G             | [7148bf6db9](https://linux-hardware.org/?probe=7148bf6db9) | Oct 19, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [4312e9a007](https://linux-hardware.org/?probe=4312e9a007) | Oct 19, 2023 |
| Acer          | Aspire VN7-591G             | [9cbbb0364b](https://linux-hardware.org/?probe=9cbbb0364b) | Oct 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [2f2d05a226](https://linux-hardware.org/?probe=2f2d05a226) | Oct 19, 2023 |
| HP            | Pavilion Laptop 15t-eg30... | [b2cba37968](https://linux-hardware.org/?probe=b2cba37968) | Oct 19, 2023 |
| Lenovo        | Legion R7000P APH8 82Y9     | [cd80438b02](https://linux-hardware.org/?probe=cd80438b02) | Oct 19, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [315376a82a](https://linux-hardware.org/?probe=315376a82a) | Oct 18, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [52e7bc3407](https://linux-hardware.org/?probe=52e7bc3407) | Oct 18, 2023 |
| System76      | Gazelle                     | [061012cdb0](https://linux-hardware.org/?probe=061012cdb0) | Oct 17, 2023 |
| Apple         | MacBookPro11,1              | [ffeb95bd95](https://linux-hardware.org/?probe=ffeb95bd95) | Oct 17, 2023 |
| HP            | 250 G4                      | [a45d8a13df](https://linux-hardware.org/?probe=a45d8a13df) | Oct 16, 2023 |
| HP            | Laptop 15-dw4xxx            | [44ba7f4015](https://linux-hardware.org/?probe=44ba7f4015) | Oct 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [471a6f3119](https://linux-hardware.org/?probe=471a6f3119) | Oct 16, 2023 |
| ASUSTek       | N551ZU                      | [e56a6c7957](https://linux-hardware.org/?probe=e56a6c7957) | Oct 16, 2023 |
| HP            | ProBook 4730s               | [42a7295a49](https://linux-hardware.org/?probe=42a7295a49) | Oct 15, 2023 |
| MECHREVO      | WUJIE14 PRO                 | [40cfeec2b2](https://linux-hardware.org/?probe=40cfeec2b2) | Oct 15, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | [7a732e8a25](https://linux-hardware.org/?probe=7a732e8a25) | Oct 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [22b5b65e16](https://linux-hardware.org/?probe=22b5b65e16) | Oct 15, 2023 |
| System76      | Lemur Pro                   | [f969d7a459](https://linux-hardware.org/?probe=f969d7a459) | Oct 15, 2023 |
| Acer          | Aspire A314-23P             | [142bc36a3f](https://linux-hardware.org/?probe=142bc36a3f) | Oct 14, 2023 |
| Notebook      | P9XXEN_EF_ED                | [89eae06fc2](https://linux-hardware.org/?probe=89eae06fc2) | Oct 13, 2023 |
| Acer          | Aspire E1-571               | [94754c98ce](https://linux-hardware.org/?probe=94754c98ce) | Oct 12, 2023 |
| Apple         | MacBookPro11,4              | [107524e9ec](https://linux-hardware.org/?probe=107524e9ec) | Oct 12, 2023 |
| Apple         | MacBookPro11,4              | [f9fee05f72](https://linux-hardware.org/?probe=f9fee05f72) | Oct 12, 2023 |
| Dell          | Inspiron 16 7610            | [ee849775df](https://linux-hardware.org/?probe=ee849775df) | Oct 12, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [c815acfae8](https://linux-hardware.org/?probe=c815acfae8) | Oct 11, 2023 |
| Gateway       | NE570                       | [533fec5226](https://linux-hardware.org/?probe=533fec5226) | Oct 11, 2023 |
| Acer          | Predator PH315-54           | [552e952ebe](https://linux-hardware.org/?probe=552e952ebe) | Oct 11, 2023 |
| Acer          | Aspire A515-44G             | [58d145f207](https://linux-hardware.org/?probe=58d145f207) | Oct 11, 2023 |
| HP            | Pavilion Sleekbook 15 PC    | [7d7f268cec](https://linux-hardware.org/?probe=7d7f268cec) | Oct 11, 2023 |
| Dell          | Inspiron 15 3525            | [66bd7ea744](https://linux-hardware.org/?probe=66bd7ea744) | Oct 10, 2023 |
| Lenovo        | ThinkPad P1 20MES05502      | [869264ad64](https://linux-hardware.org/?probe=869264ad64) | Oct 10, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | [5d606c8b1c](https://linux-hardware.org/?probe=5d606c8b1c) | Oct 10, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [6591296a12](https://linux-hardware.org/?probe=6591296a12) | Oct 10, 2023 |
| Gigabyte      | AORUS 17H BXF               | [4fcbae7a75](https://linux-hardware.org/?probe=4fcbae7a75) | Oct 10, 2023 |
| System76      | Darter Pro                  | [71e1a67b2a](https://linux-hardware.org/?probe=71e1a67b2a) | Oct 10, 2023 |
| Razer         | Blade                       | [22de5dfe50](https://linux-hardware.org/?probe=22de5dfe50) | Oct 09, 2023 |
| Gigabyte      | AERO 15 Classic-SA          | [420f5d5de9](https://linux-hardware.org/?probe=420f5d5de9) | Oct 09, 2023 |
| Lenovo        | ThinkPad P1 Gen 6 21FV00... | [c0a093d7d2](https://linux-hardware.org/?probe=c0a093d7d2) | Oct 08, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [63cbb26f44](https://linux-hardware.org/?probe=63cbb26f44) | Oct 08, 2023 |
| Dell          | Inspiron 7375               | [3b54f5530b](https://linux-hardware.org/?probe=3b54f5530b) | Oct 08, 2023 |
| System76      | Serval WS                   | [509cc872ee](https://linux-hardware.org/?probe=509cc872ee) | Oct 07, 2023 |
| Alienware     | m15 R7                      | [7bd2b6300f](https://linux-hardware.org/?probe=7bd2b6300f) | Oct 07, 2023 |
| HP            | EliteBook 850 G3            | [f773c3004e](https://linux-hardware.org/?probe=f773c3004e) | Oct 07, 2023 |
| HP            | ProBook 6450b               | [70e33902c1](https://linux-hardware.org/?probe=70e33902c1) | Oct 07, 2023 |
| HP            | ProBook 6450b               | [ddd8417a28](https://linux-hardware.org/?probe=ddd8417a28) | Oct 07, 2023 |
| MSI           | GE62 2QF                    | [cd73adb01d](https://linux-hardware.org/?probe=cd73adb01d) | Oct 07, 2023 |
| HP            | Laptop 15-db1xxx            | [687a37a00f](https://linux-hardware.org/?probe=687a37a00f) | Oct 06, 2023 |
| Dell          | XPS 15 7590                 | [f4c0266602](https://linux-hardware.org/?probe=f4c0266602) | Oct 06, 2023 |
| Dell          | XPS 15 7590                 | [8978850a77](https://linux-hardware.org/?probe=8978850a77) | Oct 06, 2023 |
| System76      | Serval WS                   | [f8e3cd9fd0](https://linux-hardware.org/?probe=f8e3cd9fd0) | Oct 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [b6caf35101](https://linux-hardware.org/?probe=b6caf35101) | Oct 05, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [3e6f44ce5c](https://linux-hardware.org/?probe=3e6f44ce5c) | Oct 05, 2023 |
| Google        | Morphius                    | [735ed70d9c](https://linux-hardware.org/?probe=735ed70d9c) | Oct 05, 2023 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | [34ff66e3a9](https://linux-hardware.org/?probe=34ff66e3a9) | Oct 05, 2023 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | [314a6f2edf](https://linux-hardware.org/?probe=314a6f2edf) | Oct 05, 2023 |
| Dell          | Inspiron 5490               | [5ab40107ce](https://linux-hardware.org/?probe=5ab40107ce) | Oct 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [234f939987](https://linux-hardware.org/?probe=234f939987) | Oct 04, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [8f0fc826ae](https://linux-hardware.org/?probe=8f0fc826ae) | Oct 04, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | [1dcdef2d17](https://linux-hardware.org/?probe=1dcdef2d17) | Oct 04, 2023 |
| Dell          | Latitude 7400               | [bd6eee3b51](https://linux-hardware.org/?probe=bd6eee3b51) | Oct 03, 2023 |
| Apple         | MacBookAir6,2               | [23c850d9d3](https://linux-hardware.org/?probe=23c850d9d3) | Oct 03, 2023 |
| Apple         | MacBookAir7,2               | [efcc70945c](https://linux-hardware.org/?probe=efcc70945c) | Oct 03, 2023 |
| Lenovo        | ThinkPad W540 20BG001EUK    | [6d78bda800](https://linux-hardware.org/?probe=6d78bda800) | Oct 02, 2023 |
| MSI           | GF65 Thin 9SEXR             | [1d315fb87d](https://linux-hardware.org/?probe=1d315fb87d) | Oct 02, 2023 |
| Dell          | Inspiron 5437               | [a348906862](https://linux-hardware.org/?probe=a348906862) | Oct 02, 2023 |
| Dell          | Inspiron 3543               | [1c681f7a14](https://linux-hardware.org/?probe=1c681f7a14) | Oct 02, 2023 |
| ASUSTek       | G74Sx                       | [2e57173dd9](https://linux-hardware.org/?probe=2e57173dd9) | Oct 02, 2023 |
| System76      | Lemur Pro                   | [8486fb3080](https://linux-hardware.org/?probe=8486fb3080) | Oct 02, 2023 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [3bb0e0c792](https://linux-hardware.org/?probe=3bb0e0c792) | Oct 01, 2023 |
| Lenovo        | ThinkPad W540 20BG001EUK    | [55f747d352](https://linux-hardware.org/?probe=55f747d352) | Oct 01, 2023 |
| HP            | 250 G4                      | [30947c6039](https://linux-hardware.org/?probe=30947c6039) | Oct 01, 2023 |
| MSI           | Cyborg 15 A12VF             | [5f76307503](https://linux-hardware.org/?probe=5f76307503) | Oct 01, 2023 |
| Dell          | Latitude E7440              | [8e74ff2f99](https://linux-hardware.org/?probe=8e74ff2f99) | Oct 01, 2023 |
| HP            | ProBook 440 G4              | [810959ffa7](https://linux-hardware.org/?probe=810959ffa7) | Oct 01, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [6c314cd812](https://linux-hardware.org/?probe=6c314cd812) | Oct 01, 2023 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | [12d98aba86](https://linux-hardware.org/?probe=12d98aba86) | Oct 01, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | [8fabc36e1c](https://linux-hardware.org/?probe=8fabc36e1c) | Oct 01, 2023 |
| Apple         | MacBookPro7,1               | [c69ebf2472](https://linux-hardware.org/?probe=c69ebf2472) | Oct 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [59dcd18330](https://linux-hardware.org/?probe=59dcd18330) | Sep 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [a6d0762090](https://linux-hardware.org/?probe=a6d0762090) | Sep 30, 2023 |
| HP            | Pro Tablet 608 G1           | [14fcb9ce4b](https://linux-hardware.org/?probe=14fcb9ce4b) | Sep 30, 2023 |
| HP            | Pro Tablet 608 G1           | [ab84386c83](https://linux-hardware.org/?probe=ab84386c83) | Sep 30, 2023 |
| Positivo      | C14CR01                     | [11b171838d](https://linux-hardware.org/?probe=11b171838d) | Sep 29, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [55b44bb456](https://linux-hardware.org/?probe=55b44bb456) | Sep 29, 2023 |
| System76      | Darter Pro                  | [d8b78103d5](https://linux-hardware.org/?probe=d8b78103d5) | Sep 29, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | [fb1c2503cf](https://linux-hardware.org/?probe=fb1c2503cf) | Sep 29, 2023 |
| Acer          | Aspire E5-575G              | [109490039d](https://linux-hardware.org/?probe=109490039d) | Sep 29, 2023 |
| MSI           | Cyborg 15 A12VF             | [960cd34617](https://linux-hardware.org/?probe=960cd34617) | Sep 29, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [e23bfd302c](https://linux-hardware.org/?probe=e23bfd302c) | Sep 28, 2023 |
| Toshiba       | Satellite P775              | [7269165fd9](https://linux-hardware.org/?probe=7269165fd9) | Sep 28, 2023 |
| Apple         | MacBookAir6,2               | [b0c2b630a6](https://linux-hardware.org/?probe=b0c2b630a6) | Sep 28, 2023 |
| System76      | Oryx Pro                    | [f06316545d](https://linux-hardware.org/?probe=f06316545d) | Sep 28, 2023 |
| Acer          | Aspire VN7-791G             | [0cfe515d00](https://linux-hardware.org/?probe=0cfe515d00) | Sep 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [7c13a64c8a](https://linux-hardware.org/?probe=7c13a64c8a) | Sep 27, 2023 |
| Dell          | Latitude 5480               | [8dd1695b2c](https://linux-hardware.org/?probe=8dd1695b2c) | Sep 27, 2023 |
| System76      | Lemur Pro                   | [6013ab7f8a](https://linux-hardware.org/?probe=6013ab7f8a) | Sep 27, 2023 |
| Dell          | Latitude E7440              | [9e117fe599](https://linux-hardware.org/?probe=9e117fe599) | Sep 27, 2023 |
| HONOR         | NBR-WAX9                    | [68556b1e09](https://linux-hardware.org/?probe=68556b1e09) | Sep 27, 2023 |
| HONOR         | NBR-WAX9                    | [056de6b9b3](https://linux-hardware.org/?probe=056de6b9b3) | Sep 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [d9665a6ffd](https://linux-hardware.org/?probe=d9665a6ffd) | Sep 27, 2023 |
| Apple         | MacBookAir7,2               | [f9f08875e1](https://linux-hardware.org/?probe=f9f08875e1) | Sep 26, 2023 |
| MSI           | Summit E13FlipEvo A12MT     | [5fa9f0dde2](https://linux-hardware.org/?probe=5fa9f0dde2) | Sep 26, 2023 |
| HUAWEI        | NbDE-WXX9                   | [b3990570ee](https://linux-hardware.org/?probe=b3990570ee) | Sep 25, 2023 |
| HP            | 250 G4                      | [6e475cbb1f](https://linux-hardware.org/?probe=6e475cbb1f) | Sep 25, 2023 |
| HP            | 250 G4                      | [9543354fea](https://linux-hardware.org/?probe=9543354fea) | Sep 25, 2023 |
| Acer          | Swift SFX14-41G             | [ae755aa7e3](https://linux-hardware.org/?probe=ae755aa7e3) | Sep 25, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [cb2b1325cc](https://linux-hardware.org/?probe=cb2b1325cc) | Sep 25, 2023 |
| MSI           | Cyborg 15 A12VF             | [f934062b23](https://linux-hardware.org/?probe=f934062b23) | Sep 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [7d18eb441e](https://linux-hardware.org/?probe=7d18eb441e) | Sep 24, 2023 |
| Fujitsu       | LIFEBOOK A557               | [e66c8c9ca7](https://linux-hardware.org/?probe=e66c8c9ca7) | Sep 24, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [dfe5d4faaa](https://linux-hardware.org/?probe=dfe5d4faaa) | Sep 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [8318fdeb5b](https://linux-hardware.org/?probe=8318fdeb5b) | Sep 24, 2023 |
| Dell          | System XPS L502X            | [22d93fe76c](https://linux-hardware.org/?probe=22d93fe76c) | Sep 24, 2023 |
| MSI           | Cyborg 15 A12VF             | [7aa2ea2853](https://linux-hardware.org/?probe=7aa2ea2853) | Sep 24, 2023 |
| Dell          | System XPS L502X            | [a1d4f683c1](https://linux-hardware.org/?probe=a1d4f683c1) | Sep 24, 2023 |
| Acer          | Swift SFX14-41G             | [7980181fcb](https://linux-hardware.org/?probe=7980181fcb) | Sep 24, 2023 |
| Dell          | XPS 15 9520                 | [b358b656c6](https://linux-hardware.org/?probe=b358b656c6) | Sep 24, 2023 |
| Toshiba       | TECRA X40-E                 | [280f949acc](https://linux-hardware.org/?probe=280f949acc) | Sep 24, 2023 |
| HP            | 250 G4                      | [5290896e7d](https://linux-hardware.org/?probe=5290896e7d) | Sep 23, 2023 |
| System76      | Gazelle                     | [2e31a65d58](https://linux-hardware.org/?probe=2e31a65d58) | Sep 23, 2023 |
| HP            | Laptop 15-db1xxx            | [8b16720f22](https://linux-hardware.org/?probe=8b16720f22) | Sep 23, 2023 |
| Dell          | Vostro 5481                 | [c416e12adb](https://linux-hardware.org/?probe=c416e12adb) | Sep 22, 2023 |
| ASUSTek       | ROG Strix G814JZ_G814JZ     | [2a6c2ef738](https://linux-hardware.org/?probe=2a6c2ef738) | Sep 22, 2023 |
| HP            | EliteBook 725 G4            | [1ef194c5fd](https://linux-hardware.org/?probe=1ef194c5fd) | Sep 22, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | [726a5f4cf5](https://linux-hardware.org/?probe=726a5f4cf5) | Sep 22, 2023 |
| HUAWEI        | KPL-W0X                     | [3154e03d3f](https://linux-hardware.org/?probe=3154e03d3f) | Sep 22, 2023 |
| HP            | Laptop 15-db1xxx            | [504ed03ead](https://linux-hardware.org/?probe=504ed03ead) | Sep 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [1d9ae81bf1](https://linux-hardware.org/?probe=1d9ae81bf1) | Sep 22, 2023 |
| Notebook      | NH50_70RH                   | [57070abf3c](https://linux-hardware.org/?probe=57070abf3c) | Sep 21, 2023 |
| System76      | Darter Pro                  | [3266f46a3b](https://linux-hardware.org/?probe=3266f46a3b) | Sep 20, 2023 |
| Dell          | Precision 5680              | [a75a75f080](https://linux-hardware.org/?probe=a75a75f080) | Sep 20, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [a97463154d](https://linux-hardware.org/?probe=a97463154d) | Sep 20, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [cbc4ec2df0](https://linux-hardware.org/?probe=cbc4ec2df0) | Sep 20, 2023 |
| Apple         | MacBookPro8,1               | [43edd5f49f](https://linux-hardware.org/?probe=43edd5f49f) | Sep 20, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [a8b35a2b8f](https://linux-hardware.org/?probe=a8b35a2b8f) | Sep 19, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [8adb5c3a12](https://linux-hardware.org/?probe=8adb5c3a12) | Sep 19, 2023 |
| Framework     | Laptop                      | [f379873c4b](https://linux-hardware.org/?probe=f379873c4b) | Sep 19, 2023 |
| HP            | Pavilion 15                 | [eb15fe383c](https://linux-hardware.org/?probe=eb15fe383c) | Sep 18, 2023 |
| HP            | Pavilion 15                 | [fb86634643](https://linux-hardware.org/?probe=fb86634643) | Sep 18, 2023 |
| HP            | Dev One Notebook PC         | [2606a8d1c1](https://linux-hardware.org/?probe=2606a8d1c1) | Sep 17, 2023 |
| HONOR         | BMH-WCX9                    | [96a8945a17](https://linux-hardware.org/?probe=96a8945a17) | Sep 17, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [797e19424f](https://linux-hardware.org/?probe=797e19424f) | Sep 16, 2023 |
| Notebook      | NV4XMB,ME,MZ                | [35bc7480cb](https://linux-hardware.org/?probe=35bc7480cb) | Sep 15, 2023 |
| Unknown       | Unknown                     | [ae1fde8210](https://linux-hardware.org/?probe=ae1fde8210) | Sep 15, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | [98dbf213e7](https://linux-hardware.org/?probe=98dbf213e7) | Sep 15, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [5150bae6bd](https://linux-hardware.org/?probe=5150bae6bd) | Sep 15, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [175e57d54f](https://linux-hardware.org/?probe=175e57d54f) | Sep 15, 2023 |
| Digibras      | CL341                       | [a358f5d40c](https://linux-hardware.org/?probe=a358f5d40c) | Sep 15, 2023 |
| Lenovo        | Slim Pro 9 14IRP8 83BV      | [bc86928972](https://linux-hardware.org/?probe=bc86928972) | Sep 15, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | [4f6e19f508](https://linux-hardware.org/?probe=4f6e19f508) | Sep 14, 2023 |
| ASUSTek       | X556URK                     | [0996de9eac](https://linux-hardware.org/?probe=0996de9eac) | Sep 14, 2023 |
| Dell          | Latitude 7440               | [cd8e3aa6ed](https://linux-hardware.org/?probe=cd8e3aa6ed) | Sep 14, 2023 |
| realme        | RMNBXXXX                    | [7f93463d6a](https://linux-hardware.org/?probe=7f93463d6a) | Sep 14, 2023 |
| realme        | RMNBXXXX                    | [a635ea5599](https://linux-hardware.org/?probe=a635ea5599) | Sep 14, 2023 |
| Toshiba       | Satellite L735              | [fee724f874](https://linux-hardware.org/?probe=fee724f874) | Sep 14, 2023 |
| System76      | Pangolin                    | [c3803d0977](https://linux-hardware.org/?probe=c3803d0977) | Sep 13, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [ef5a6433f3](https://linux-hardware.org/?probe=ef5a6433f3) | Sep 13, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | [df7945af41](https://linux-hardware.org/?probe=df7945af41) | Sep 13, 2023 |
| Apple         | MacBookPro9,2               | [c159157024](https://linux-hardware.org/?probe=c159157024) | Sep 13, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [03e666ab42](https://linux-hardware.org/?probe=03e666ab42) | Sep 12, 2023 |
| MSI           | Stealth 15M B12UE           | [9a23215875](https://linux-hardware.org/?probe=9a23215875) | Sep 11, 2023 |
| Schenker      | XMG NEO (TGL/M21)           | [8f9ada75e9](https://linux-hardware.org/?probe=8f9ada75e9) | Sep 11, 2023 |
| Dell          | Latitude E7250              | [44983ff513](https://linux-hardware.org/?probe=44983ff513) | Sep 11, 2023 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [1b2d76894b](https://linux-hardware.org/?probe=1b2d76894b) | Sep 10, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [a9caf49f0e](https://linux-hardware.org/?probe=a9caf49f0e) | Sep 09, 2023 |
| Lenovo        | V720-14 80Y1                | [ec869beffd](https://linux-hardware.org/?probe=ec869beffd) | Sep 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [5fc227a0e8](https://linux-hardware.org/?probe=5fc227a0e8) | Sep 08, 2023 |
| Dell          | Vostro 5502                 | [a131efa36e](https://linux-hardware.org/?probe=a131efa36e) | Sep 08, 2023 |
| HP            | Laptop 14-dk0xxx            | [57b82728d8](https://linux-hardware.org/?probe=57b82728d8) | Sep 08, 2023 |
| HP            | EliteBook 745 G5            | [05d61b5c23](https://linux-hardware.org/?probe=05d61b5c23) | Sep 08, 2023 |
| MSI           | P65 Creator 8RD             | [3eab920cfc](https://linux-hardware.org/?probe=3eab920cfc) | Sep 07, 2023 |
| HP            | Laptop 15-dy2xxx            | [eae373ebd4](https://linux-hardware.org/?probe=eae373ebd4) | Sep 07, 2023 |
| MSI           | Alpha 15 A3DDK              | [9a87dfb80b](https://linux-hardware.org/?probe=9a87dfb80b) | Sep 07, 2023 |
| HP            | EliteBook 8760w             | [d061b57b29](https://linux-hardware.org/?probe=d061b57b29) | Sep 07, 2023 |
| Alienware     | m15 R7                      | [9e6b80bbf2](https://linux-hardware.org/?probe=9e6b80bbf2) | Sep 07, 2023 |
| Apple         | MacBookPro11,3              | [bfdd099826](https://linux-hardware.org/?probe=bfdd099826) | Sep 06, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [0692b6f878](https://linux-hardware.org/?probe=0692b6f878) | Sep 06, 2023 |
| Acer          | Swift SFX14-41G             | [611bb4fe1a](https://linux-hardware.org/?probe=611bb4fe1a) | Sep 06, 2023 |
| Acer          | Swift SFX14-41G             | [38f9d1abd9](https://linux-hardware.org/?probe=38f9d1abd9) | Sep 05, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | [27575898fe](https://linux-hardware.org/?probe=27575898fe) | Sep 05, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [dda5b7f9c9](https://linux-hardware.org/?probe=dda5b7f9c9) | Sep 05, 2023 |
| Dell          | Inspiron 14 5420            | [70d0d79f77](https://linux-hardware.org/?probe=70d0d79f77) | Sep 05, 2023 |
| Apple         | MacBookPro10,1              | [11c016fb1b](https://linux-hardware.org/?probe=11c016fb1b) | Sep 05, 2023 |
| Dell          | Latitude E5430 non-vPro     | [ee1a881e82](https://linux-hardware.org/?probe=ee1a881e82) | Sep 04, 2023 |
| System76      | Lemur Pro                   | [9ea11da090](https://linux-hardware.org/?probe=9ea11da090) | Sep 04, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | [68e90ee0cb](https://linux-hardware.org/?probe=68e90ee0cb) | Sep 04, 2023 |
| ASUSTek       | K53E                        | [5604fe515d](https://linux-hardware.org/?probe=5604fe515d) | Sep 04, 2023 |
| Dell          | XPS 17 9700                 | [e758c8955e](https://linux-hardware.org/?probe=e758c8955e) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [2ddf0c5c61](https://linux-hardware.org/?probe=2ddf0c5c61) | Sep 03, 2023 |
| HP            | 240 G8 Notebook PC          | [092ae0b34d](https://linux-hardware.org/?probe=092ae0b34d) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [f2f5e496f1](https://linux-hardware.org/?probe=f2f5e496f1) | Sep 02, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [515e1f4bce](https://linux-hardware.org/?probe=515e1f4bce) | Sep 02, 2023 |
| Apple         | MacBookAir3,2               | [5ee8cbf433](https://linux-hardware.org/?probe=5ee8cbf433) | Sep 02, 2023 |
| Schenker      | VIA 15 Pro                  | [4a31ab4d2b](https://linux-hardware.org/?probe=4a31ab4d2b) | Sep 02, 2023 |
| Apple         | MacBookAir6,2               | [da8d60051c](https://linux-hardware.org/?probe=da8d60051c) | Sep 02, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [87e1726495](https://linux-hardware.org/?probe=87e1726495) | Sep 01, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [e73e853358](https://linux-hardware.org/?probe=e73e853358) | Sep 01, 2023 |
| ASUSTek       | N550JV                      | [b2effdc956](https://linux-hardware.org/?probe=b2effdc956) | Sep 01, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [2433535726](https://linux-hardware.org/?probe=2433535726) | Sep 01, 2023 |
| Dell          | Inspiron 5558               | [77c6379594](https://linux-hardware.org/?probe=77c6379594) | Sep 01, 2023 |
| Acer          | Swift SFX14-41G             | [67f553625a](https://linux-hardware.org/?probe=67f553625a) | Sep 01, 2023 |
| Dell          | Latitude E7470              | [0580f1c293](https://linux-hardware.org/?probe=0580f1c293) | Sep 01, 2023 |
| Lenovo        | ThinkPad T450 20BUS0B000    | [1213d3bf46](https://linux-hardware.org/?probe=1213d3bf46) | Aug 31, 2023 |
| Acer          | Aspire E5-551G              | [628d865373](https://linux-hardware.org/?probe=628d865373) | Aug 31, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [3b890e064f](https://linux-hardware.org/?probe=3b890e064f) | Aug 31, 2023 |
| Acer          | Nitro AN515-55              | [6c5da44516](https://linux-hardware.org/?probe=6c5da44516) | Aug 31, 2023 |
| Google        | Kefka                       | [284517c2b3](https://linux-hardware.org/?probe=284517c2b3) | Aug 31, 2023 |
| Lenovo        | ThinkPad W520 427637U       | [5f995c7c48](https://linux-hardware.org/?probe=5f995c7c48) | Aug 30, 2023 |
| Apple         | MacBookPro5,5               | [641243c308](https://linux-hardware.org/?probe=641243c308) | Aug 30, 2023 |
| Lenovo        | G50-80 80E5                 | [5ba6fd6ca3](https://linux-hardware.org/?probe=5ba6fd6ca3) | Aug 30, 2023 |
| Google        | Kefka                       | [a018ae3fb5](https://linux-hardware.org/?probe=a018ae3fb5) | Aug 30, 2023 |
| Acer          | Aspire E5-571               | [500ef94276](https://linux-hardware.org/?probe=500ef94276) | Aug 29, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [90a72df8ef](https://linux-hardware.org/?probe=90a72df8ef) | Aug 29, 2023 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [4904c007c7](https://linux-hardware.org/?probe=4904c007c7) | Aug 29, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [ba9dd7a62d](https://linux-hardware.org/?probe=ba9dd7a62d) | Aug 29, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [f1b8efb723](https://linux-hardware.org/?probe=f1b8efb723) | Aug 29, 2023 |
| ASUSTek       | ROG Strix G634JZ_G634JZ     | [481b37b0fc](https://linux-hardware.org/?probe=481b37b0fc) | Aug 29, 2023 |
| Dell          | Latitude 5330               | [7e63575d10](https://linux-hardware.org/?probe=7e63575d10) | Aug 29, 2023 |
| Lenovo        | ThinkPad T430s 2356CU8      | [2f669d797f](https://linux-hardware.org/?probe=2f669d797f) | Aug 29, 2023 |
| Lenovo        | ThinkPad T430s 2356CU8      | [39f2feeed5](https://linux-hardware.org/?probe=39f2feeed5) | Aug 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHC... | [de65d63e10](https://linux-hardware.org/?probe=de65d63e10) | Aug 28, 2023 |
| Lenovo        | Legion 5 15IMH 82CF         | [4d8ac47399](https://linux-hardware.org/?probe=4d8ac47399) | Aug 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHC... | [dc9a79314c](https://linux-hardware.org/?probe=dc9a79314c) | Aug 28, 2023 |
| Dell          | XPS 15 7590                 | [ef97f75590](https://linux-hardware.org/?probe=ef97f75590) | Aug 28, 2023 |
| Dell          | Precision 5510              | [c6d08d9c28](https://linux-hardware.org/?probe=c6d08d9c28) | Aug 27, 2023 |
| HP            | EliteBook 865 16 inch G9... | [b07775a194](https://linux-hardware.org/?probe=b07775a194) | Aug 27, 2023 |
| HP            | 250 G7 Notebook PC          | [c4be1d7e95](https://linux-hardware.org/?probe=c4be1d7e95) | Aug 27, 2023 |
| Lenovo        | ThinkPad T460 20FMS05K05    | [747e8d4f6a](https://linux-hardware.org/?probe=747e8d4f6a) | Aug 27, 2023 |
| Dell          | Precision M4600             | [b7fca4d2f9](https://linux-hardware.org/?probe=b7fca4d2f9) | Aug 27, 2023 |
| Apple         | MacBookPro8,2               | [9e0b5b0b7e](https://linux-hardware.org/?probe=9e0b5b0b7e) | Aug 26, 2023 |
| Dell          | Precision M6800             | [6aa5f8e441](https://linux-hardware.org/?probe=6aa5f8e441) | Aug 26, 2023 |
| HP            | ProBook 4730s               | [32f610b810](https://linux-hardware.org/?probe=32f610b810) | Aug 26, 2023 |
| Google        | Kasumi                      | [9af5f77257](https://linux-hardware.org/?probe=9af5f77257) | Aug 25, 2023 |
| System76      | Gazelle                     | [b3fb438915](https://linux-hardware.org/?probe=b3fb438915) | Aug 25, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | [e2e304c9eb](https://linux-hardware.org/?probe=e2e304c9eb) | Aug 25, 2023 |
| HP            | EliteBook 865 16 inch G9... | [34fc2a5f83](https://linux-hardware.org/?probe=34fc2a5f83) | Aug 24, 2023 |
| Dell          | Latitude E7240              | [cb61859037](https://linux-hardware.org/?probe=cb61859037) | Aug 24, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [6cf9db7da7](https://linux-hardware.org/?probe=6cf9db7da7) | Aug 24, 2023 |
| Dell          | Latitude 7430               | [7daf0301c5](https://linux-hardware.org/?probe=7daf0301c5) | Aug 24, 2023 |
| Toshiba       | Satellite L655              | [18df557333](https://linux-hardware.org/?probe=18df557333) | Aug 24, 2023 |
| HP            | Pavilion Notebook           | [b0ca2ee250](https://linux-hardware.org/?probe=b0ca2ee250) | Aug 23, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | [50f079ae44](https://linux-hardware.org/?probe=50f079ae44) | Aug 23, 2023 |
| Dell          | XPS 13 9310                 | [6f0e38b5e8](https://linux-hardware.org/?probe=6f0e38b5e8) | Aug 23, 2023 |
| Samsung       | 750TDA                      | [7b1ec96afa](https://linux-hardware.org/?probe=7b1ec96afa) | Aug 23, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | [4cd19df49e](https://linux-hardware.org/?probe=4cd19df49e) | Aug 23, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2RV0... | [e8d2c8e1d5](https://linux-hardware.org/?probe=e8d2c8e1d5) | Aug 22, 2023 |
| System76      | Darter Pro                  | [a244cb8283](https://linux-hardware.org/?probe=a244cb8283) | Aug 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | [fdd24243bf](https://linux-hardware.org/?probe=fdd24243bf) | Aug 22, 2023 |
| Acer          | Aspire A715-75G             | [54794fb9e8](https://linux-hardware.org/?probe=54794fb9e8) | Aug 22, 2023 |
| HP            | ProBook 4730s               | [5b4d88bc67](https://linux-hardware.org/?probe=5b4d88bc67) | Aug 21, 2023 |
| Samsung       | 270E5G/270E5U               | [930d312c36](https://linux-hardware.org/?probe=930d312c36) | Aug 21, 2023 |
| Samsung       | 270E5G/270E5U               | [2bc8c24081](https://linux-hardware.org/?probe=2bc8c24081) | Aug 21, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [b66d308d42](https://linux-hardware.org/?probe=b66d308d42) | Aug 21, 2023 |
| MSI           | Modern 15 A5M               | [f9742049fc](https://linux-hardware.org/?probe=f9742049fc) | Aug 20, 2023 |
| System76      | Oryx Pro                    | [b7e0bd11e5](https://linux-hardware.org/?probe=b7e0bd11e5) | Aug 20, 2023 |
| Dell          | Precision 5520              | [42587aac96](https://linux-hardware.org/?probe=42587aac96) | Aug 20, 2023 |
| Dell          | Precision 5520              | [bec735d800](https://linux-hardware.org/?probe=bec735d800) | Aug 20, 2023 |
| System76      | Kudu Pro                    | [0fc481c5fc](https://linux-hardware.org/?probe=0fc481c5fc) | Aug 20, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR    | [5d063a6e59](https://linux-hardware.org/?probe=5d063a6e59) | Aug 19, 2023 |
| Lenovo        | B490 377224P                | [0e516ea22b](https://linux-hardware.org/?probe=0e516ea22b) | Aug 19, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [a1ab007f7f](https://linux-hardware.org/?probe=a1ab007f7f) | Aug 18, 2023 |
| ASUSTek       | U38N                        | [0e0f709353](https://linux-hardware.org/?probe=0e0f709353) | Aug 17, 2023 |
| HP            | EliteBook 850 G3            | [a6a7224d63](https://linux-hardware.org/?probe=a6a7224d63) | Aug 17, 2023 |
| Dell          | XPS 13 9310                 | [680fae2274](https://linux-hardware.org/?probe=680fae2274) | Aug 17, 2023 |
| ASUSTek       | Vivobook Go E1404FA_E140... | [43fd1aad67](https://linux-hardware.org/?probe=43fd1aad67) | Aug 17, 2023 |
| System76      | Lemur Pro                   | [af3b387574](https://linux-hardware.org/?probe=af3b387574) | Aug 16, 2023 |
| Acer          | Aspire 5750                 | [ec4afb1917](https://linux-hardware.org/?probe=ec4afb1917) | Aug 16, 2023 |
| A-DATA Tec... | XENIA 14                    | [59faf4a458](https://linux-hardware.org/?probe=59faf4a458) | Aug 15, 2023 |
| A-DATA Tec... | XENIA 14                    | [537cce8a8e](https://linux-hardware.org/?probe=537cce8a8e) | Aug 15, 2023 |
| HP            | Laptop 15s-eq2xxx           | [c2cfa9bd7a](https://linux-hardware.org/?probe=c2cfa9bd7a) | Aug 15, 2023 |
| Apple         | MacBookAir6,2               | [431ac1b880](https://linux-hardware.org/?probe=431ac1b880) | Aug 15, 2023 |
| Dell          | XPS 15 9570                 | [ce22773504](https://linux-hardware.org/?probe=ce22773504) | Aug 15, 2023 |
| System76      | Galago Pro                  | [54348f9c55](https://linux-hardware.org/?probe=54348f9c55) | Aug 14, 2023 |
| Apple         | MacBookPro9,2               | [61ff7ac5f1](https://linux-hardware.org/?probe=61ff7ac5f1) | Aug 14, 2023 |
| Apple         | MacBookPro16,1              | [18b513f5f0](https://linux-hardware.org/?probe=18b513f5f0) | Aug 14, 2023 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | [1f27d0f994](https://linux-hardware.org/?probe=1f27d0f994) | Aug 14, 2023 |
| HP            | ProBook 4540s               | [84dbf6b759](https://linux-hardware.org/?probe=84dbf6b759) | Aug 13, 2023 |
| Dell          | Inspiron 3542               | [ae586a02aa](https://linux-hardware.org/?probe=ae586a02aa) | Aug 13, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [823e276406](https://linux-hardware.org/?probe=823e276406) | Aug 13, 2023 |
| GPU Compan... | GWNR71517                   | [a38cee5cc9](https://linux-hardware.org/?probe=a38cee5cc9) | Aug 12, 2023 |
| Acer          | Aspire ES1-520              | [a47415983e](https://linux-hardware.org/?probe=a47415983e) | Aug 12, 2023 |
| Lenovo        | ThinkPad L13 20R3CTO1WW     | [6ac135c81c](https://linux-hardware.org/?probe=6ac135c81c) | Aug 12, 2023 |
| ASUSTek       | K53TK                       | [db9f130ade](https://linux-hardware.org/?probe=db9f130ade) | Aug 12, 2023 |
| Dell          | G7 7588                     | [48faf46c2c](https://linux-hardware.org/?probe=48faf46c2c) | Aug 12, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | [f46a14b981](https://linux-hardware.org/?probe=f46a14b981) | Aug 12, 2023 |
| HP            | EliteBook 820 G3            | [544810db31](https://linux-hardware.org/?probe=544810db31) | Aug 12, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [0d45e9e048](https://linux-hardware.org/?probe=0d45e9e048) | Aug 12, 2023 |
| Dell          | Precision M4600             | [f97367efac](https://linux-hardware.org/?probe=f97367efac) | Aug 11, 2023 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | [361e073b5c](https://linux-hardware.org/?probe=361e073b5c) | Aug 11, 2023 |
| Acer          | Nitro AN715-51              | [ea972c8686](https://linux-hardware.org/?probe=ea972c8686) | Aug 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [e22f71b79d](https://linux-hardware.org/?probe=e22f71b79d) | Aug 11, 2023 |
| ASUSTek       | X751LD                      | [e98d8d116d](https://linux-hardware.org/?probe=e98d8d116d) | Aug 10, 2023 |
| Apple         | MacBookAir5,2               | [7f91d6f9d8](https://linux-hardware.org/?probe=7f91d6f9d8) | Aug 10, 2023 |
| Acer          | Nitro AN517-55              | [b77ff095f8](https://linux-hardware.org/?probe=b77ff095f8) | Aug 09, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [6415840d5b](https://linux-hardware.org/?probe=6415840d5b) | Aug 09, 2023 |
| HP            | ProBook 4330s               | [5c854bed9f](https://linux-hardware.org/?probe=5c854bed9f) | Aug 09, 2023 |
| HP            | ProBook 4330s               | [d23ce497d2](https://linux-hardware.org/?probe=d23ce497d2) | Aug 09, 2023 |
| System76      | Darter Pro                  | [5162d61c01](https://linux-hardware.org/?probe=5162d61c01) | Aug 09, 2023 |
| MSI           | Cyborg 15 A12VF             | [b041192310](https://linux-hardware.org/?probe=b041192310) | Aug 09, 2023 |
| Alienware     | 14                          | [192b13997d](https://linux-hardware.org/?probe=192b13997d) | Aug 09, 2023 |
| HP            | Victus by 15.6 inch Gami... | [67f88ab571](https://linux-hardware.org/?probe=67f88ab571) | Aug 08, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | [afa081b440](https://linux-hardware.org/?probe=afa081b440) | Aug 08, 2023 |
| Acer          | Ferrari One 200             | [be688aa584](https://linux-hardware.org/?probe=be688aa584) | Aug 08, 2023 |
| Apple         | MacBookPro10,1              | [00b169d241](https://linux-hardware.org/?probe=00b169d241) | Aug 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [ec7a911951](https://linux-hardware.org/?probe=ec7a911951) | Aug 08, 2023 |
| Apple         | MacBookPro11,3              | [c415fd317b](https://linux-hardware.org/?probe=c415fd317b) | Aug 08, 2023 |
| Apple         | MacBookPro10,1              | [5e0c7f7bfc](https://linux-hardware.org/?probe=5e0c7f7bfc) | Aug 08, 2023 |
| Acer          | Aspire A715-75G             | [57f1225daf](https://linux-hardware.org/?probe=57f1225daf) | Aug 08, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [088a8fad47](https://linux-hardware.org/?probe=088a8fad47) | Aug 08, 2023 |
| System76      | Oryx Pro                    | [c5b97761d3](https://linux-hardware.org/?probe=c5b97761d3) | Aug 07, 2023 |
| MSI           | Cyborg 15 A12VF             | [5fe9a17769](https://linux-hardware.org/?probe=5fe9a17769) | Aug 07, 2023 |
| MSI           | GP72 7RDX                   | [43eb53850c](https://linux-hardware.org/?probe=43eb53850c) | Aug 06, 2023 |
| Clevo         | W150HRM                     | [1ddcfcbecc](https://linux-hardware.org/?probe=1ddcfcbecc) | Aug 06, 2023 |
| Apple         | MacBookPro9,2               | [16936ef482](https://linux-hardware.org/?probe=16936ef482) | Aug 06, 2023 |
| MSI           | GP72 7RDX                   | [6d2bc8aa9e](https://linux-hardware.org/?probe=6d2bc8aa9e) | Aug 06, 2023 |
| Timi          | RedmiBook Pro 15S           | [576241bbd4](https://linux-hardware.org/?probe=576241bbd4) | Aug 06, 2023 |
| Notebook      | 1745                        | [3561a5dbbe](https://linux-hardware.org/?probe=3561a5dbbe) | Aug 06, 2023 |
| HP            | Pavilion dm4                | [521b8518ed](https://linux-hardware.org/?probe=521b8518ed) | Aug 06, 2023 |
| Dell          | Latitude 5430               | [f63444b0be](https://linux-hardware.org/?probe=f63444b0be) | Aug 05, 2023 |
| Apple         | MacBookPro11,2              | [32f8bbeff7](https://linux-hardware.org/?probe=32f8bbeff7) | Aug 05, 2023 |
| MSI           | Modern 15 A5M               | [a4a6f81455](https://linux-hardware.org/?probe=a4a6f81455) | Aug 05, 2023 |
| MSI           | Modern 15 A5M               | [ef010c9d51](https://linux-hardware.org/?probe=ef010c9d51) | Aug 05, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [7d17fc9ff6](https://linux-hardware.org/?probe=7d17fc9ff6) | Aug 05, 2023 |
| Lenovo        | V15 G3 ABA 82TV             | [0147060507](https://linux-hardware.org/?probe=0147060507) | Aug 04, 2023 |
| HP            | ProBook 650 G1              | [286cc8b0dd](https://linux-hardware.org/?probe=286cc8b0dd) | Aug 04, 2023 |
| Lenovo        | ThinkPad W541 20EGS0GY0R    | [4d618e08b3](https://linux-hardware.org/?probe=4d618e08b3) | Aug 03, 2023 |
| System76      | Bonobo WS                   | [64ba21a272](https://linux-hardware.org/?probe=64ba21a272) | Aug 03, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D6C... | [a97312771e](https://linux-hardware.org/?probe=a97312771e) | Aug 03, 2023 |
| Dell          | XPS 13 9370                 | [cf49ff3004](https://linux-hardware.org/?probe=cf49ff3004) | Aug 03, 2023 |
| Dell          | Latitude E7240              | [ec5ec88e59](https://linux-hardware.org/?probe=ec5ec88e59) | Aug 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [99ccd043cb](https://linux-hardware.org/?probe=99ccd043cb) | Aug 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [d4e267a214](https://linux-hardware.org/?probe=d4e267a214) | Aug 02, 2023 |
| HP            | ProBook 650 G4              | [d041df173b](https://linux-hardware.org/?probe=d041df173b) | Aug 02, 2023 |
| Apple         | MacBookPro11,3              | [1eb6fd9620](https://linux-hardware.org/?probe=1eb6fd9620) | Aug 02, 2023 |
| Apple         | MacBookPro7,1               | [0a3c5e5c4d](https://linux-hardware.org/?probe=0a3c5e5c4d) | Aug 02, 2023 |
| Apple         | MacBookPro7,1               | [9f852ea211](https://linux-hardware.org/?probe=9f852ea211) | Aug 02, 2023 |
| ASUSTek       | GL502VSK                    | [0ed7feaa05](https://linux-hardware.org/?probe=0ed7feaa05) | Aug 01, 2023 |
| Lenovo        | Legion 5 15ARH7 82RE        | [e1a79e094e](https://linux-hardware.org/?probe=e1a79e094e) | Aug 01, 2023 |
| Dell          | Inspiron 5567               | [d252fa93be](https://linux-hardware.org/?probe=d252fa93be) | Aug 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [9fbfc590ad](https://linux-hardware.org/?probe=9fbfc590ad) | Aug 01, 2023 |
| Dell          | Latitude 3500               | [df5211a816](https://linux-hardware.org/?probe=df5211a816) | Aug 01, 2023 |
| Dell          | Latitude 5490               | [e24a9f877c](https://linux-hardware.org/?probe=e24a9f877c) | Aug 01, 2023 |
| System76      | Lemur Pro                   | [1ba844bc69](https://linux-hardware.org/?probe=1ba844bc69) | Aug 01, 2023 |
| System76      | Lemur Pro                   | [e019d33faf](https://linux-hardware.org/?probe=e019d33faf) | Aug 01, 2023 |
| MSI           | Katana GF66 12UC            | [d590bcd619](https://linux-hardware.org/?probe=d590bcd619) | Jul 31, 2023 |
| ASUSTek       | K95VM                       | [1ec08c4cf9](https://linux-hardware.org/?probe=1ec08c4cf9) | Jul 30, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [60cfcb00e9](https://linux-hardware.org/?probe=60cfcb00e9) | Jul 30, 2023 |
| Dell          | Latitude E7440              | [7509a5f756](https://linux-hardware.org/?probe=7509a5f756) | Jul 30, 2023 |
| System76      | Darter Pro                  | [0220d19f38](https://linux-hardware.org/?probe=0220d19f38) | Jul 30, 2023 |
| Dell          | Latitude E7240              | [b794bcdde6](https://linux-hardware.org/?probe=b794bcdde6) | Jul 29, 2023 |
| HP            | Pavilion 11 x360 PC         | [d693783e7a](https://linux-hardware.org/?probe=d693783e7a) | Jul 29, 2023 |
| Unknown       | Unknown                     | [73836c0a75](https://linux-hardware.org/?probe=73836c0a75) | Jul 29, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [59f0eb6b57](https://linux-hardware.org/?probe=59f0eb6b57) | Jul 28, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [cb2f78abf0](https://linux-hardware.org/?probe=cb2f78abf0) | Jul 28, 2023 |
| Dell          | Precision 3550              | [0ecac77f90](https://linux-hardware.org/?probe=0ecac77f90) | Jul 28, 2023 |
| Dell          | Precision 3550              | [95ae018833](https://linux-hardware.org/?probe=95ae018833) | Jul 28, 2023 |
| System76      | Oryx Pro                    | [0ad8c1d8a7](https://linux-hardware.org/?probe=0ad8c1d8a7) | Jul 28, 2023 |
| Acer          | Aspire A315-42G             | [0e3aa83494](https://linux-hardware.org/?probe=0e3aa83494) | Jul 28, 2023 |
| HP            | EliteBook 840 G3            | [5a1f6f3395](https://linux-hardware.org/?probe=5a1f6f3395) | Jul 27, 2023 |
| Dell          | G15 5520                    | [7a5b503737](https://linux-hardware.org/?probe=7a5b503737) | Jul 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [4152e1f98e](https://linux-hardware.org/?probe=4152e1f98e) | Jul 27, 2023 |
| Dell          | Latitude E7440              | [619c6e4b99](https://linux-hardware.org/?probe=619c6e4b99) | Jul 27, 2023 |
| Samsung       | 300E5M/300E5L               | [23b23d59aa](https://linux-hardware.org/?probe=23b23d59aa) | Jul 27, 2023 |
| HP            | Dev One Notebook PC         | [b54bb52258](https://linux-hardware.org/?probe=b54bb52258) | Jul 27, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [9920824f1f](https://linux-hardware.org/?probe=9920824f1f) | Jul 27, 2023 |
| Acer          | Nitro AN515-55              | [00e9bb8973](https://linux-hardware.org/?probe=00e9bb8973) | Jul 26, 2023 |
| Dell          | Inspiron 5548               | [22b2519a90](https://linux-hardware.org/?probe=22b2519a90) | Jul 26, 2023 |
| Acer          | Aspire A515-56              | [7e0e30c1cf](https://linux-hardware.org/?probe=7e0e30c1cf) | Jul 26, 2023 |
| Dell          | Inspiron 5548               | [b583a1fbee](https://linux-hardware.org/?probe=b583a1fbee) | Jul 26, 2023 |
| Dell          | Inspiron 5548               | [3d3696e8fa](https://linux-hardware.org/?probe=3d3696e8fa) | Jul 25, 2023 |
| HP            | Laptop 14-bs0xx             | [e074ee90be](https://linux-hardware.org/?probe=e074ee90be) | Jul 25, 2023 |
| MSI           | GF63 Thin 10SCXR            | [b34b7fa5fb](https://linux-hardware.org/?probe=b34b7fa5fb) | Jul 25, 2023 |
| Dell          | Inspiron 5490               | [25f155c61a](https://linux-hardware.org/?probe=25f155c61a) | Jul 24, 2023 |
| Dell          | Inspiron 5490               | [6b80b41fee](https://linux-hardware.org/?probe=6b80b41fee) | Jul 24, 2023 |
| Dell          | XPS 15 7590                 | [fa64a82283](https://linux-hardware.org/?probe=fa64a82283) | Jul 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [88cfdb061d](https://linux-hardware.org/?probe=88cfdb061d) | Jul 24, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [61c84247e6](https://linux-hardware.org/?probe=61c84247e6) | Jul 24, 2023 |
| Apple         | MacBookAir4,2               | [e220379405](https://linux-hardware.org/?probe=e220379405) | Jul 24, 2023 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | [53bab7ac5e](https://linux-hardware.org/?probe=53bab7ac5e) | Jul 24, 2023 |
| Apple         | MacBookPro5,5               | [b2b0895194](https://linux-hardware.org/?probe=b2b0895194) | Jul 24, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [3d8ec4447b](https://linux-hardware.org/?probe=3d8ec4447b) | Jul 24, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [fe2ff0c21f](https://linux-hardware.org/?probe=fe2ff0c21f) | Jul 23, 2023 |
| Apple         | MacBookPro8,1               | [2cd0946aba](https://linux-hardware.org/?probe=2cd0946aba) | Jul 23, 2023 |
| Sony          | SVF1521A6EW                 | [3c39100c6f](https://linux-hardware.org/?probe=3c39100c6f) | Jul 23, 2023 |
| PC Special... | Standard                    | [992aec5bb8](https://linux-hardware.org/?probe=992aec5bb8) | Jul 23, 2023 |
| HP            | ZBook Studio G3             | [bcfc5b64f4](https://linux-hardware.org/?probe=bcfc5b64f4) | Jul 23, 2023 |
| Google        | Snappy                      | [a3e6774e43](https://linux-hardware.org/?probe=a3e6774e43) | Jul 23, 2023 |
| Dell          | Latitude 3500               | [0755576e96](https://linux-hardware.org/?probe=0755576e96) | Jul 22, 2023 |
| Dell          | Latitude E6430s             | [8e74e2a524](https://linux-hardware.org/?probe=8e74e2a524) | Jul 22, 2023 |
| Dell          | Vostro 3560                 | [05acc63d53](https://linux-hardware.org/?probe=05acc63d53) | Jul 22, 2023 |
| Dell          | Latitude 5410               | [82217114b4](https://linux-hardware.org/?probe=82217114b4) | Jul 21, 2023 |
| Dell          | Latitude 5520               | [070380568b](https://linux-hardware.org/?probe=070380568b) | Jul 21, 2023 |
| LG Electro... | S425-G.BC31P1               | [2f54821f3f](https://linux-hardware.org/?probe=2f54821f3f) | Jul 21, 2023 |
| Dell          | Precision 7530              | [0d2e753768](https://linux-hardware.org/?probe=0d2e753768) | Jul 20, 2023 |
| Acer          | Aspire A515-52              | [243f0a8cab](https://linux-hardware.org/?probe=243f0a8cab) | Jul 20, 2023 |
| Acer          | Aspire A515-52              | [f310abe0bb](https://linux-hardware.org/?probe=f310abe0bb) | Jul 20, 2023 |
| HP            | Pavilion Plus Laptop 14-... | [937715a75f](https://linux-hardware.org/?probe=937715a75f) | Jul 20, 2023 |
| Dell          | Latitude E5270              | [9ea13fdc27](https://linux-hardware.org/?probe=9ea13fdc27) | Jul 20, 2023 |
| HP            | Laptop 15-da0xxx            | [6e17b916ee](https://linux-hardware.org/?probe=6e17b916ee) | Jul 20, 2023 |
| Acer          | Extensa 5635ZG              | [337f0cec05](https://linux-hardware.org/?probe=337f0cec05) | Jul 20, 2023 |
| Toshiba       | Satellite L750              | [662f89dcc3](https://linux-hardware.org/?probe=662f89dcc3) | Jul 20, 2023 |
| Dell          | XPS 13 9360                 | [ac1a8eea0e](https://linux-hardware.org/?probe=ac1a8eea0e) | Jul 19, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [35944db669](https://linux-hardware.org/?probe=35944db669) | Jul 19, 2023 |
| Schenker      | XMG NEO (CML/E20)           | [9f99e57705](https://linux-hardware.org/?probe=9f99e57705) | Jul 19, 2023 |
| ASUSTek       | K53E                        | [7fddec038e](https://linux-hardware.org/?probe=7fddec038e) | Jul 19, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [8cb16d19aa](https://linux-hardware.org/?probe=8cb16d19aa) | Jul 19, 2023 |
| Notebook      | NH5x_7xDPx                  | [098f2f58c7](https://linux-hardware.org/?probe=098f2f58c7) | Jul 18, 2023 |
| Apple         | MacBookPro16,1              | [dd5d384a71](https://linux-hardware.org/?probe=dd5d384a71) | Jul 18, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | [f5dc246f7c](https://linux-hardware.org/?probe=f5dc246f7c) | Jul 18, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | [abec03689c](https://linux-hardware.org/?probe=abec03689c) | Jul 18, 2023 |
| ASRock        | Z77 Performance             | [585aaad9ad](https://linux-hardware.org/?probe=585aaad9ad) | Jul 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [1cffa4bad9](https://linux-hardware.org/?probe=1cffa4bad9) | Jul 18, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [cdaad6fa25](https://linux-hardware.org/?probe=cdaad6fa25) | Jul 18, 2023 |
| HP            | 635                         | [500e11147e](https://linux-hardware.org/?probe=500e11147e) | Jul 18, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [1426cda0a7](https://linux-hardware.org/?probe=1426cda0a7) | Jul 17, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [c7a062709f](https://linux-hardware.org/?probe=c7a062709f) | Jul 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [86f515ebce](https://linux-hardware.org/?probe=86f515ebce) | Jul 17, 2023 |
| HUAWEI        | KLVC-WXX9                   | [0427f16143](https://linux-hardware.org/?probe=0427f16143) | Jul 17, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [0bbd5c68bb](https://linux-hardware.org/?probe=0bbd5c68bb) | Jul 17, 2023 |
| Dell          | Precision M6800             | [8ddd80db6c](https://linux-hardware.org/?probe=8ddd80db6c) | Jul 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [4abe81669a](https://linux-hardware.org/?probe=4abe81669a) | Jul 17, 2023 |
| Lenovo        | ThinkPad X390 20Q1S67S00    | [be43004463](https://linux-hardware.org/?probe=be43004463) | Jul 17, 2023 |
| System76      | Serval WS                   | [a916a92726](https://linux-hardware.org/?probe=a916a92726) | Jul 17, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [55a5100039](https://linux-hardware.org/?probe=55a5100039) | Jul 16, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [ad8f031cb2](https://linux-hardware.org/?probe=ad8f031cb2) | Jul 16, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [51128412d5](https://linux-hardware.org/?probe=51128412d5) | Jul 16, 2023 |
| Lenovo        | Legion Slim 7 16IRH8 82Y... | [437209972c](https://linux-hardware.org/?probe=437209972c) | Jul 15, 2023 |
| Lenovo        | ThinkPad T480 20L5S1S000    | [91dbb2c969](https://linux-hardware.org/?probe=91dbb2c969) | Jul 15, 2023 |
| Dell          | G15 5510                    | [28b7a732f2](https://linux-hardware.org/?probe=28b7a732f2) | Jul 15, 2023 |
| System76      | Pangolin                    | [486df7ead2](https://linux-hardware.org/?probe=486df7ead2) | Jul 14, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [0498e27f41](https://linux-hardware.org/?probe=0498e27f41) | Jul 14, 2023 |
| HP            | ENVY 15                     | [5cfb9d33bd](https://linux-hardware.org/?probe=5cfb9d33bd) | Jul 14, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [21fc63e4dd](https://linux-hardware.org/?probe=21fc63e4dd) | Jul 14, 2023 |
| MSI           | GF63 Thin 10SC              | [d017610254](https://linux-hardware.org/?probe=d017610254) | Jul 14, 2023 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [e53c63af42](https://linux-hardware.org/?probe=e53c63af42) | Jul 14, 2023 |
| Lenovo        | ThinkPad T530 23943J8       | [fb022ada73](https://linux-hardware.org/?probe=fb022ada73) | Jul 14, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e84bf83ac1](https://linux-hardware.org/?probe=e84bf83ac1) | Jul 13, 2023 |
| HP            | Compaq CQ58                 | [78977dd4de](https://linux-hardware.org/?probe=78977dd4de) | Jul 13, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [7ef2028b06](https://linux-hardware.org/?probe=7ef2028b06) | Jul 13, 2023 |
| Acer          | Aspire E5-576G              | [0856b48ae7](https://linux-hardware.org/?probe=0856b48ae7) | Jul 13, 2023 |
| Acer          | Swift SF314-42              | [c82bb58705](https://linux-hardware.org/?probe=c82bb58705) | Jul 13, 2023 |
| Lenovo        | ThinkPad P53s 20N6001UUS    | [5a675551df](https://linux-hardware.org/?probe=5a675551df) | Jul 13, 2023 |
| Dell          | G3 3590                     | [089bfa3da7](https://linux-hardware.org/?probe=089bfa3da7) | Jul 13, 2023 |
| Apple         | MacBookPro8,1               | [d4910e3f43](https://linux-hardware.org/?probe=d4910e3f43) | Jul 13, 2023 |
| Acer          | Swift SF314-42              | [7a9624e7cc](https://linux-hardware.org/?probe=7a9624e7cc) | Jul 12, 2023 |
| Acer          | Swift SF314-58G             | [795625662c](https://linux-hardware.org/?probe=795625662c) | Jul 12, 2023 |
| Acer          | Swift SF314-58G             | [c01b74af46](https://linux-hardware.org/?probe=c01b74af46) | Jul 12, 2023 |
| Timi          | Xiaomi NoteBook Pro         | [618c0c975b](https://linux-hardware.org/?probe=618c0c975b) | Jul 12, 2023 |
| HP            | Laptop 17-cp0xxx            | [801537f1d4](https://linux-hardware.org/?probe=801537f1d4) | Jul 12, 2023 |
| Apple         | MacBookPro6,2               | [20e2180dc1](https://linux-hardware.org/?probe=20e2180dc1) | Jul 12, 2023 |
| MSI           | Cyborg 15 A12VF             | [2c4a8d9d63](https://linux-hardware.org/?probe=2c4a8d9d63) | Jul 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS01A0... | [54e51170a1](https://linux-hardware.org/?probe=54e51170a1) | Jul 11, 2023 |
| Apple         | MacBookAir3,2               | [cbfc272e87](https://linux-hardware.org/?probe=cbfc272e87) | Jul 11, 2023 |
| HP            | EliteBook 850 G6            | [556ef4473f](https://linux-hardware.org/?probe=556ef4473f) | Jul 11, 2023 |
| HP            | EliteBook 840 G6            | [a61e80c022](https://linux-hardware.org/?probe=a61e80c022) | Jul 11, 2023 |
| Apple         | MacBookAir7,2               | [1453f984c9](https://linux-hardware.org/?probe=1453f984c9) | Jul 11, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [5a7dbc5d7c](https://linux-hardware.org/?probe=5a7dbc5d7c) | Jul 10, 2023 |
| Apple         | MacBookPro6,2               | [293ddc3253](https://linux-hardware.org/?probe=293ddc3253) | Jul 10, 2023 |
| Notebook      | NP5x_NP6x_NP7xRNJ_RNH       | [7663e77bff](https://linux-hardware.org/?probe=7663e77bff) | Jul 09, 2023 |
| Notebook      | P7xxTM1                     | [81c163ed4a](https://linux-hardware.org/?probe=81c163ed4a) | Jul 09, 2023 |
| HP            | Laptop 14s-fq0xxx           | [92feea0533](https://linux-hardware.org/?probe=92feea0533) | Jul 08, 2023 |
| HP            | Laptop 14s-fq0xxx           | [2287c62944](https://linux-hardware.org/?probe=2287c62944) | Jul 08, 2023 |
| Toshiba       | IS 1413G                    | [cf96aafbc0](https://linux-hardware.org/?probe=cf96aafbc0) | Jul 08, 2023 |
| Apple         | MacBookPro11,1              | [1f88a40c05](https://linux-hardware.org/?probe=1f88a40c05) | Jul 08, 2023 |
| Apple         | MacBookPro11,1              | [e1f22afb69](https://linux-hardware.org/?probe=e1f22afb69) | Jul 08, 2023 |
| MSI           | Cyborg 15 A12VF             | [a34d0d8290](https://linux-hardware.org/?probe=a34d0d8290) | Jul 08, 2023 |
| Dell          | Inspiron 5565               | [d1df053096](https://linux-hardware.org/?probe=d1df053096) | Jul 08, 2023 |
| Acer          | Nitro AN515-57              | [12e3f9ecc7](https://linux-hardware.org/?probe=12e3f9ecc7) | Jul 07, 2023 |
| ASUSTek       | N55SL                       | [1223d8b536](https://linux-hardware.org/?probe=1223d8b536) | Jul 07, 2023 |
| MSI           | GS66 Stealth 10SE           | [e689bf355c](https://linux-hardware.org/?probe=e689bf355c) | Jul 07, 2023 |
| Panasonic     | FZ55-1                      | [4d12f02737](https://linux-hardware.org/?probe=4d12f02737) | Jul 07, 2023 |
| Dell          | Inspiron 3501               | [e657049abf](https://linux-hardware.org/?probe=e657049abf) | Jul 06, 2023 |
| Toshiba       | IS 1413G                    | [f2a99b72dc](https://linux-hardware.org/?probe=f2a99b72dc) | Jul 06, 2023 |
| Acer          | Predator PT515-51           | [9971e8a3da](https://linux-hardware.org/?probe=9971e8a3da) | Jul 05, 2023 |
| HP            | Laptop 15-da0xxx            | [f634e3942a](https://linux-hardware.org/?probe=f634e3942a) | Jul 05, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | [46e6f4b081](https://linux-hardware.org/?probe=46e6f4b081) | Jul 05, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | [6bf093ef61](https://linux-hardware.org/?probe=6bf093ef61) | Jul 05, 2023 |
| Dell          | XPS 17 9720                 | [a99946b8f0](https://linux-hardware.org/?probe=a99946b8f0) | Jul 04, 2023 |
| HP            | OMEN by Laptop 17-cb1xxx    | [dbf87e0eec](https://linux-hardware.org/?probe=dbf87e0eec) | Jul 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [09dffdde54](https://linux-hardware.org/?probe=09dffdde54) | Jul 04, 2023 |
| MSI           | Cyborg 15 A12VF             | [156f923a72](https://linux-hardware.org/?probe=156f923a72) | Jul 04, 2023 |
| Acer          | Aspire E1-470G              | [db4125a1c5](https://linux-hardware.org/?probe=db4125a1c5) | Jul 04, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [dda9b242fd](https://linux-hardware.org/?probe=dda9b242fd) | Jul 03, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [e8ff92b585](https://linux-hardware.org/?probe=e8ff92b585) | Jul 03, 2023 |
| Acer          | Aspire A515-52              | [3861c91dd4](https://linux-hardware.org/?probe=3861c91dd4) | Jul 02, 2023 |
| Acer          | Aspire A515-52              | [ab8898b9f3](https://linux-hardware.org/?probe=ab8898b9f3) | Jul 02, 2023 |
| Apple         | MacBookPro12,1              | [f89bdd4374](https://linux-hardware.org/?probe=f89bdd4374) | Jul 02, 2023 |
| Dell          | Precision 7510              | [46b90e25b0](https://linux-hardware.org/?probe=46b90e25b0) | Jul 02, 2023 |
| MSI           | GT72VR 6RD                  | [ea6887d031](https://linux-hardware.org/?probe=ea6887d031) | Jul 01, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [6ee8b4e949](https://linux-hardware.org/?probe=6ee8b4e949) | Jul 01, 2023 |
| Dell          | Latitude 3500               | [8293ebc591](https://linux-hardware.org/?probe=8293ebc591) | Jul 01, 2023 |
| Toshiba       | IS 1413G                    | [b95a7c049a](https://linux-hardware.org/?probe=b95a7c049a) | Jun 30, 2023 |
| Teclast       | F7 Plus                     | [cebd3b027c](https://linux-hardware.org/?probe=cebd3b027c) | Jun 30, 2023 |
| Dell          | XPS 13 9370                 | [ec4bf131f5](https://linux-hardware.org/?probe=ec4bf131f5) | Jun 30, 2023 |
| Positivo      | Mobile                      | [fdaaf6915b](https://linux-hardware.org/?probe=fdaaf6915b) | Jun 30, 2023 |
| MSI           | GS65 Stealth 9SD            | [568380fd59](https://linux-hardware.org/?probe=568380fd59) | Jun 30, 2023 |
| MSI           | GS65 Stealth 9SD            | [54013b2dfd](https://linux-hardware.org/?probe=54013b2dfd) | Jun 30, 2023 |
| Positivo      | H14CU02                     | [d50e6fbbdc](https://linux-hardware.org/?probe=d50e6fbbdc) | Jun 29, 2023 |
| ASRock        | Z77 Performance             | [a678dc9605](https://linux-hardware.org/?probe=a678dc9605) | Jun 29, 2023 |
| MSI           | Vector GP76 12UH            | [b7035d78a6](https://linux-hardware.org/?probe=b7035d78a6) | Jun 29, 2023 |
| MSI           | GE70 2PL                    | [e5354b6cb4](https://linux-hardware.org/?probe=e5354b6cb4) | Jun 28, 2023 |
| Acer          | Aspire A315-21              | [4bf524cd80](https://linux-hardware.org/?probe=4bf524cd80) | Jun 27, 2023 |
| Acer          | Aspire E1-571               | [894f8583ea](https://linux-hardware.org/?probe=894f8583ea) | Jun 27, 2023 |
| Dell          | Vostro 15 3510              | [adb3a3de68](https://linux-hardware.org/?probe=adb3a3de68) | Jun 27, 2023 |
| Dell          | Precision M6800             | [b0fe737883](https://linux-hardware.org/?probe=b0fe737883) | Jun 27, 2023 |
| Toshiba       | IS 1413G                    | [882bd512a2](https://linux-hardware.org/?probe=882bd512a2) | Jun 27, 2023 |
| ASUSTek       | X550JX                      | [80770014b8](https://linux-hardware.org/?probe=80770014b8) | Jun 27, 2023 |
| Dell          | Inspiron 3583               | [e1e76b3d77](https://linux-hardware.org/?probe=e1e76b3d77) | Jun 27, 2023 |
| HUAWEI        | KLVL-WXXW                   | [5454a08ba6](https://linux-hardware.org/?probe=5454a08ba6) | Jun 26, 2023 |
| Lenovo        | ThinkPad P53 20QQS34C04     | [3019d7a733](https://linux-hardware.org/?probe=3019d7a733) | Jun 26, 2023 |
| Apple         | MacBookAir6,1               | [6b44c8513d](https://linux-hardware.org/?probe=6b44c8513d) | Jun 26, 2023 |
| Dell          | Precision M6800             | [4e6c5423b1](https://linux-hardware.org/?probe=4e6c5423b1) | Jun 25, 2023 |
| Dell          | Precision M6800             | [feb0adfd99](https://linux-hardware.org/?probe=feb0adfd99) | Jun 25, 2023 |
| HP            | Notebook                    | [ea00ce6c5b](https://linux-hardware.org/?probe=ea00ce6c5b) | Jun 25, 2023 |
| Sony          | VPCEA23FB                   | [b9a835920f](https://linux-hardware.org/?probe=b9a835920f) | Jun 25, 2023 |
| Sony          | VPCEA23FB                   | [c462c4c75e](https://linux-hardware.org/?probe=c462c4c75e) | Jun 25, 2023 |
| HP            | ENVY NOTEBOOK PC            | [8bd62ffdf1](https://linux-hardware.org/?probe=8bd62ffdf1) | Jun 25, 2023 |
| Acer          | Swift SF314-512             | [12f361cd8c](https://linux-hardware.org/?probe=12f361cd8c) | Jun 24, 2023 |
| System76      | Oryx Pro                    | [eaa4d8e105](https://linux-hardware.org/?probe=eaa4d8e105) | Jun 24, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [737204f453](https://linux-hardware.org/?probe=737204f453) | Jun 24, 2023 |
| MSI           | Cyborg 15 A12VF             | [703e12843e](https://linux-hardware.org/?probe=703e12843e) | Jun 23, 2023 |
| HP            | Laptop 15-dw2xxx            | [7f41e23d3a](https://linux-hardware.org/?probe=7f41e23d3a) | Jun 23, 2023 |
| HP            | Laptop 15-dw2xxx            | [79ec1a7b3f](https://linux-hardware.org/?probe=79ec1a7b3f) | Jun 23, 2023 |
| Dell          | XPS 15 9500                 | [36dc72c683](https://linux-hardware.org/?probe=36dc72c683) | Jun 23, 2023 |
| ASUSTek       | X751LD                      | [c7be73b6ca](https://linux-hardware.org/?probe=c7be73b6ca) | Jun 23, 2023 |
| ASUSTek       | X751LD                      | [346bbb0b47](https://linux-hardware.org/?probe=346bbb0b47) | Jun 23, 2023 |
| MSI           | Alpha 15 A3DDK              | [410b20161b](https://linux-hardware.org/?probe=410b20161b) | Jun 23, 2023 |
| Dell          | Inspiron 3501               | [e8db86e014](https://linux-hardware.org/?probe=e8db86e014) | Jun 22, 2023 |
| ASUSTek       | X551MA                      | [5b2b7d4a7f](https://linux-hardware.org/?probe=5b2b7d4a7f) | Jun 22, 2023 |
| Dell          | Inspiron 3583               | [170d1f4f0b](https://linux-hardware.org/?probe=170d1f4f0b) | Jun 22, 2023 |
| HP            | Notebook                    | [35b8a2a187](https://linux-hardware.org/?probe=35b8a2a187) | Jun 22, 2023 |
| Lenovo        | B5400 80B6QB0               | [6885fc56aa](https://linux-hardware.org/?probe=6885fc56aa) | Jun 22, 2023 |
| Dell          | Inspiron 5567               | [8634954b1c](https://linux-hardware.org/?probe=8634954b1c) | Jun 22, 2023 |
| Acer          | Aspire A515-52              | [43ee82258d](https://linux-hardware.org/?probe=43ee82258d) | Jun 21, 2023 |
| Dell          | System Inspiron N4110       | [ebaceedccf](https://linux-hardware.org/?probe=ebaceedccf) | Jun 21, 2023 |
| Lenovo        | ThinkPad T480 20L6S3H102    | [4a8bd602ff](https://linux-hardware.org/?probe=4a8bd602ff) | Jun 21, 2023 |
| Dell          | System Inspiron N4110       | [a168f45822](https://linux-hardware.org/?probe=a168f45822) | Jun 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [b255195205](https://linux-hardware.org/?probe=b255195205) | Jun 21, 2023 |
| Acer          | Aspire A515-52              | [b2d464d2bc](https://linux-hardware.org/?probe=b2d464d2bc) | Jun 21, 2023 |
| Toshiba       | IS 1413G                    | [14296e98e7](https://linux-hardware.org/?probe=14296e98e7) | Jun 21, 2023 |
| Dell          | Latitude E7240              | [f8b3fce80b](https://linux-hardware.org/?probe=f8b3fce80b) | Jun 21, 2023 |

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
| Pop!_OS 22.04 | 2309      | 38.96%  |
| Pop!_OS 20.04 | 1153      | 19.46%  |
| Pop!_OS 21.04 | 960       | 16.2%   |
| Pop!_OS 20.10 | 857       | 14.46%  |
| Pop!_OS 21.10 | 600       | 10.12%  |
| Pop!_OS 19.10 | 30        | 0.51%   |
| Pop!_OS 18.04 | 7         | 0.12%   |
| Pop!_OS 19.04 | 6         | 0.1%    |
| Pop!_OS 18.10 | 4         | 0.07%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Pop!_OS | 5660      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 6.2.6-76060206-generic   | 471       | 7.37%   |
| 5.11.0-7620-generic      | 443       | 6.93%   |
| 5.8.0-7630-generic       | 381       | 5.96%   |
| 5.4.0-7634-generic       | 346       | 5.41%   |
| 5.19.0-76051900-generic  | 274       | 4.29%   |
| 6.0.12-76060006-generic  | 266       | 4.16%   |
| 5.13.0-7614-generic      | 262       | 4.1%    |
| 5.4.0-7642-generic       | 256       | 4.01%   |
| 5.17.5-76051705-generic  | 253       | 3.96%   |
| 5.8.0-7642-generic       | 242       | 3.79%   |
| 5.11.0-7614-generic      | 228       | 3.57%   |
| 5.13.0-7620-generic      | 218       | 3.41%   |
| 6.4.6-76060406-generic   | 186       | 2.91%   |
| 6.0.6-76060006-generic   | 164       | 2.57%   |
| 6.5.6-76060506-generic   | 158       | 2.47%   |
| 5.15.15-76051515-generic | 154       | 2.41%   |
| 5.16.11-76051611-generic | 139       | 2.17%   |
| 5.11.0-7612-generic      | 128       | 2%      |
| 5.15.5-76051505-generic  | 123       | 1.92%   |
| 5.18.10-76051810-generic | 122       | 1.91%   |
| 6.6.6-76060606-generic   | 121       | 1.89%   |
| 5.17.15-76051715-generic | 106       | 1.66%   |
| 5.8.0-7625-generic       | 105       | 1.64%   |
| 5.11.0-7633-generic      | 99        | 1.55%   |
| 5.16.19-76051619-generic | 98        | 1.53%   |
| 5.15.8-76051508-generic  | 98        | 1.53%   |
| 5.16.15-76051615-generic | 92        | 1.44%   |
| 5.4.0-7626-generic       | 84        | 1.31%   |
| 6.2.0-76060200-generic   | 77        | 1.2%    |
| 6.5.4-76060504-generic   | 65        | 1.02%   |
| 5.15.11-76051511-generic | 63        | 0.99%   |
| 6.0.2-76060002-generic   | 59        | 0.92%   |
| 5.15.23-76051523-generic | 56        | 0.88%   |
| 6.1.11-76060111-generic  | 54        | 0.84%   |
| 5.4.0-7625-generic       | 44        | 0.69%   |
| 5.4.0-7629-generic       | 35        | 0.55%   |
| 6.0.3-76060003-generic   | 24        | 0.38%   |
| 6.6.10-76060610-generic  | 21        | 0.33%   |
| 5.19.16-76051916-generic | 21        | 0.33%   |
| 5.3.0-7625-generic       | 10        | 0.16%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 876       | 13.93%  |
| 5.4.0   | 744       | 11.83%  |
| 5.8.0   | 698       | 11.1%   |
| 6.2.6   | 472       | 7.51%   |
| 5.13.0  | 467       | 7.43%   |
| 5.19.0  | 277       | 4.41%   |
| 6.0.12  | 272       | 4.33%   |
| 5.17.5  | 256       | 4.07%   |
| 6.4.6   | 186       | 2.96%   |
| 6.0.6   | 164       | 2.61%   |
| 6.5.6   | 158       | 2.51%   |
| 5.15.15 | 154       | 2.45%   |
| 5.16.11 | 139       | 2.21%   |
| 5.15.5  | 123       | 1.96%   |
| 5.18.10 | 122       | 1.94%   |
| 6.6.6   | 121       | 1.92%   |
| 5.17.15 | 106       | 1.69%   |
| 5.16.19 | 98        | 1.56%   |
| 5.15.8  | 98        | 1.56%   |
| 5.16.15 | 92        | 1.46%   |
| 6.2.0   | 77        | 1.22%   |
| 6.5.4   | 65        | 1.03%   |
| 5.15.11 | 63        | 1%      |
| 6.0.2   | 60        | 0.95%   |
| 5.15.23 | 56        | 0.89%   |
| 6.1.11  | 54        | 0.86%   |
| 5.3.0   | 32        | 0.51%   |
| 6.0.3   | 24        | 0.38%   |
| 6.6.10  | 21        | 0.33%   |
| 5.19.16 | 21        | 0.33%   |
| 5.0.0   | 6         | 0.1%    |
| 4.18.0  | 6         | 0.1%    |
| 5.15.0  | 5         | 0.08%   |
| 5.7.0   | 4         | 0.06%   |
| 6.5.7   | 3         | 0.05%   |
| 5.8.6   | 3         | 0.05%   |
| 5.8.11  | 3         | 0.05%   |
| 5.7.1   | 3         | 0.05%   |
| 5.14.0  | 3         | 0.05%   |
| 5.12.14 | 3         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 882       | 14.16%  |
| 5.4     | 745       | 11.96%  |
| 5.8     | 712       | 11.43%  |
| 6.2     | 550       | 8.83%   |
| 6.0     | 505       | 8.11%   |
| 5.15    | 495       | 7.95%   |
| 5.13    | 478       | 7.68%   |
| 5.17    | 362       | 5.81%   |
| 5.16    | 327       | 5.25%   |
| 5.19    | 300       | 4.82%   |
| 6.5     | 229       | 3.68%   |
| 6.4     | 190       | 3.05%   |
| 6.6     | 142       | 2.28%   |
| 5.18    | 126       | 2.02%   |
| 6.1     | 61        | 0.98%   |
| 5.3     | 32        | 0.51%   |
| 5.10    | 18        | 0.29%   |
| 5.12    | 13        | 0.21%   |
| 5.7     | 11        | 0.18%   |
| 5.14    | 11        | 0.18%   |
| 5.9     | 9         | 0.14%   |
| 6.3     | 7         | 0.11%   |
| 5.6     | 7         | 0.11%   |
| 4.18    | 7         | 0.11%   |
| 5.0     | 6         | 0.1%    |
| 4.15    | 2         | 0.03%   |
| 4.9     | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 5660      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 5483      | 96.43%  |
| KDE5            | 48        | 0.84%   |
| Unknown         | 47        | 0.83%   |
| KDE             | 25        | 0.44%   |
| X-Cinnamon      | 20        | 0.35%   |
| GNOME Flashback | 13        | 0.23%   |
| XFCE            | 9         | 0.16%   |
| MATE            | 9         | 0.16%   |
| LXQt            | 9         | 0.16%   |
| Cinnamon        | 8         | 0.14%   |
| Unity           | 7         | 0.12%   |
| Budgie          | 4         | 0.07%   |
| awesome         | 2         | 0.04%   |
| i3              | 1         | 0.02%   |
| Deepin          | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 5457      | 95.87%  |
| Wayland | 205       | 3.6%    |
| Unknown | 22        | 0.39%   |
| Tty     | 8         | 0.14%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 4242      | 74.04%  |
| GDM     | 776       | 13.55%  |
| GDM3    | 695       | 12.13%  |
| SDDM    | 9         | 0.16%   |
| TDM     | 5         | 0.09%   |
| LightDM | 2         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 3271      | 57.4%   |
| pt_BR   | 404       | 7.09%   |
| en_GB   | 398       | 6.98%   |
| de_DE   | 243       | 4.26%   |
| C       | 158       | 2.77%   |
| en_AU   | 123       | 2.16%   |
| fr_FR   | 118       | 2.07%   |
| it_IT   | 115       | 2.02%   |
| es_ES   | 109       | 1.91%   |
| en_CA   | 106       | 1.86%   |
| ru_RU   | 78        | 1.37%   |
| Unknown | 59        | 1.04%   |
| pl_PL   | 53        | 0.93%   |
| pt_PT   | 50        | 0.88%   |
| sv_SE   | 34        | 0.6%    |
| en_IN   | 34        | 0.6%    |
| nb_NO   | 25        | 0.44%   |
| nl_NL   | 23        | 0.4%    |
| tr_TR   | 22        | 0.39%   |
| es_MX   | 20        | 0.35%   |
| en_ZA   | 20        | 0.35%   |
| fi_FI   | 19        | 0.33%   |
| en_NZ   | 17        | 0.3%    |
| cs_CZ   | 13        | 0.23%   |
| fr_CA   | 12        | 0.21%   |
| es_AR   | 12        | 0.21%   |
| en_IE   | 11        | 0.19%   |
| en_DK   | 11        | 0.19%   |
| hu_HU   | 10        | 0.18%   |
| da_DK   | 10        | 0.18%   |
| de_CH   | 9         | 0.16%   |
| hr_HR   | 8         | 0.14%   |
| es_CL   | 8         | 0.14%   |
| sk_SK   | 7         | 0.12%   |
| ro_RO   | 6         | 0.11%   |
| es_CO   | 6         | 0.11%   |
| zh_CN   | 5         | 0.09%   |
| nl_BE   | 5         | 0.09%   |
| en_IL   | 5         | 0.09%   |
| de_AT   | 5         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 3982      | 69.28%  |
| EFI  | 1766      | 30.72%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 5423      | 95.44%  |
| Btrfs   | 141       | 2.48%   |
| Overlay | 90        | 1.58%   |
| Xfs     | 20        | 0.35%   |
| Unknown | 7         | 0.12%   |
| Zfs     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 4202      | 73.49%  |
| GPT     | 1393      | 24.36%  |
| MBR     | 123       | 2.15%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 5526      | 97.32%  |
| Yes       | 152       | 2.68%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 5139      | 90.35%  |
| Yes       | 549       | 9.65%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 1139      | 20.12%  |
| Dell                   | 968       | 17.1%   |
| Hewlett-Packard        | 787       | 13.9%   |
| ASUSTek Computer       | 657       | 11.61%  |
| Acer                   | 440       | 7.77%   |
| Apple                  | 336       | 5.94%   |
| System76               | 205       | 3.62%   |
| MSI                    | 190       | 3.36%   |
| Toshiba                | 109       | 1.93%   |
| Samsung Electronics    | 99        | 1.75%   |
| HUAWEI                 | 68        | 1.2%    |
| Notebook               | 54        | 0.95%   |
| Sony                   | 50        | 0.88%   |
| Google                 | 46        | 0.81%   |
| Alienware              | 42        | 0.74%   |
| Positivo               | 30        | 0.53%   |
| Fujitsu                | 30        | 0.53%   |
| Razer                  | 27        | 0.48%   |
| Gigabyte Technology    | 20        | 0.35%   |
| Timi                   | 19        | 0.34%   |
| PC Specialist          | 18        | 0.32%   |
| Unknown                | 18        | 0.32%   |
| Framework              | 15        | 0.27%   |
| TUXEDO                 | 14        | 0.25%   |
| LG Electronics         | 13        | 0.23%   |
| GPU Company            | 13        | 0.23%   |
| Medion                 | 12        | 0.21%   |
| Packard Bell           | 11        | 0.19%   |
| Avell High Performance | 11        | 0.19%   |
| Teclast                | 7         | 0.12%   |
| Schenker               | 7         | 0.12%   |
| Panasonic              | 7         | 0.12%   |
| HONOR                  | 7         | 0.12%   |
| Gateway                | 7         | 0.12%   |
| Eluktronics            | 7         | 0.12%   |
| Clevo                  | 7         | 0.12%   |
| Intel                  | 6         | 0.11%   |
| SLIMBOOK               | 5         | 0.09%   |
| Chuwi                  | 5         | 0.09%   |
| Quanta                 | 4         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| System76 Oryx Pro               | 48        | 0.85%   |
| System76 Lemur Pro              | 41        | 0.72%   |
| Dell XPS 15 7590                | 34        | 0.6%    |
| Unknown                         | 33        | 0.58%   |
| System76 Gazelle                | 29        | 0.51%   |
| Apple MacBookPro9,2             | 27        | 0.48%   |
| Apple MacBookPro8,1             | 27        | 0.48%   |
| System76 Galago Pro             | 23        | 0.41%   |
| Apple MacBookPro12,1            | 23        | 0.41%   |
| Dell XPS 15 9500                | 22        | 0.39%   |
| Apple MacBookAir7,2             | 22        | 0.39%   |
| System76 Darter Pro             | 21        | 0.37%   |
| HP Notebook                     | 21        | 0.37%   |
| HP Pavilion Notebook            | 20        | 0.35%   |
| Apple MacBookAir6,2             | 20        | 0.35%   |
| HP Pavilion 15                  | 18        | 0.32%   |
| Dell XPS 15 9570                | 17        | 0.3%    |
| HP Pavilion dv6                 | 16        | 0.28%   |
| Dell XPS 15 9560                | 16        | 0.28%   |
| Apple MacBookPro7,1             | 16        | 0.28%   |
| Dell Latitude E6420             | 15        | 0.27%   |
| Lenovo IdeaPad S145-15API 81V7  | 14        | 0.25%   |
| Apple MacBookPro5,5             | 14        | 0.25%   |
| HP Dev One Notebook PC          | 13        | 0.23%   |
| Apple MacBookPro11,3            | 13        | 0.23%   |
| Apple MacBookPro11,1            | 13        | 0.23%   |
| Lenovo IdeaPad 330-15IKB 81FE   | 12        | 0.21%   |
| HP Pavilion g6                  | 12        | 0.21%   |
| Dell XPS 17 9700                | 12        | 0.21%   |
| Dell Latitude E7240             | 12        | 0.21%   |
| Acer Aspire E5-575G             | 12        | 0.21%   |
| System76 Pangolin               | 11        | 0.19%   |
| Lenovo IdeaPad 330-15IKB 81DE   | 11        | 0.19%   |
| HP Pavilion Laptop 15-cw1xxx    | 11        | 0.19%   |
| Framework Laptop                | 11        | 0.19%   |
| Dell XPS 13 9380                | 11        | 0.19%   |
| Dell XPS 13 9370                | 11        | 0.19%   |
| ASUS TUF Gaming FX505DT_FX505DT | 11        | 0.19%   |
| Apple MacBookPro10,1            | 11        | 0.19%   |
| Apple MacBook5,1                | 11        | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 557       | 9.84%   |
| Lenovo IdeaPad     | 308       | 5.44%   |
| Dell Inspiron      | 304       | 5.37%   |
| Acer Aspire        | 294       | 5.19%   |
| Dell Latitude      | 239       | 4.22%   |
| Dell XPS           | 207       | 3.66%   |
| HP Pavilion        | 181       | 3.2%    |
| HP EliteBook       | 122       | 2.16%   |
| HP Laptop          | 115       | 2.03%   |
| ASUS VivoBook      | 114       | 2.01%   |
| ASUS ROG           | 100       | 1.77%   |
| Toshiba Satellite  | 93        | 1.64%   |
| Lenovo Legion      | 90        | 1.59%   |
| HP ProBook         | 90        | 1.59%   |
| Dell Precision     | 73        | 1.29%   |
| ASUS ASUS          | 58        | 1.02%   |
| Acer Nitro         | 55        | 0.97%   |
| Dell Vostro        | 54        | 0.95%   |
| System76 Oryx      | 48        | 0.85%   |
| Apple MacBookPro11 | 45        | 0.8%    |
| Acer Swift         | 45        | 0.8%    |
| System76 Lemur     | 44        | 0.78%   |
| ASUS ZenBook       | 38        | 0.67%   |
| HP ENVY            | 37        | 0.65%   |
| Apple MacBookPro8  | 36        | 0.64%   |
| HP OMEN            | 35        | 0.62%   |
| Apple MacBookPro9  | 34        | 0.6%    |
| HP ZBook           | 33        | 0.58%   |
| ASUS TUF           | 33        | 0.58%   |
| Unknown            | 33        | 0.58%   |
| System76 Gazelle   | 31        | 0.55%   |
| Lenovo ThinkBook   | 29        | 0.51%   |
| Apple MacBookPro5  | 28        | 0.49%   |
| Razer Blade        | 27        | 0.48%   |
| Lenovo Yoga        | 27        | 0.48%   |
| System76 Galago    | 26        | 0.46%   |
| Fujitsu LIFEBOOK   | 23        | 0.41%   |
| Apple MacBookPro12 | 23        | 0.41%   |
| Apple MacBookAir7  | 23        | 0.41%   |
| Apple MacBookAir6  | 23        | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 669       | 11.82%  |
| 2020    | 645       | 11.4%   |
| 2021    | 598       | 10.57%  |
| 2018    | 522       | 9.22%   |
| 2012    | 394       | 6.96%   |
| 2013    | 374       | 6.61%   |
| 2017    | 342       | 6.04%   |
| 2011    | 341       | 6.02%   |
| 2015    | 305       | 5.39%   |
| 2016    | 283       | 5%      |
| 2014    | 280       | 4.95%   |
| 2022    | 269       | 4.75%   |
| 2010    | 206       | 3.64%   |
| 2008    | 134       | 2.37%   |
| 2009    | 129       | 2.28%   |
| 2023    | 93        | 1.64%   |
| 2007    | 61        | 1.08%   |
| 2006    | 10        | 0.18%   |
| Unknown | 3         | 0.05%   |
| 2005    | 1         | 0.02%   |
| 2004    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 5660      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 5657      | 99.95%  |
| Enabled  | 3         | 0.05%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 5482      | 96.86%  |
| Yes  | 178       | 3.14%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1654      | 28.97%  |
| 16.01-24.0  | 1291      | 22.61%  |
| 8.01-16.0   | 1063      | 18.62%  |
| 3.01-4.0    | 820       | 14.36%  |
| 32.01-64.0  | 565       | 9.89%   |
| 64.01-256.0 | 125       | 2.19%   |
| 24.01-32.0  | 83        | 1.45%   |
| 1.01-2.0    | 73        | 1.28%   |
| 2.01-3.0    | 36        | 0.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 1845      | 29.86%  |
| 4.01-8.0   | 1390      | 22.5%   |
| 1.01-2.0   | 1345      | 21.77%  |
| 3.01-4.0   | 1167      | 18.89%  |
| 8.01-16.0  | 354       | 5.73%   |
| 16.01-24.0 | 50        | 0.81%   |
| 24.01-32.0 | 14        | 0.23%   |
| 0.51-1.0   | 12        | 0.19%   |
| 32.01-64.0 | 1         | 0.02%   |
| 0.01-0.5   | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4022      | 69.83%  |
| 2      | 1487      | 25.82%  |
| 3      | 186       | 3.23%   |
| 0      | 30        | 0.52%   |
| 4      | 26        | 0.45%   |
| 5      | 7         | 0.12%   |
| 7      | 1         | 0.02%   |
| 6      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4142      | 72.96%  |
| Yes       | 1535      | 27.04%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4479      | 78.66%  |
| No        | 1215      | 21.34%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5593      | 98.76%  |
| No        | 70        | 1.24%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4798      | 84.04%  |
| No        | 911       | 15.96%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 1505      | 26.46%  |
| Brazil       | 564       | 9.92%   |
| Germany      | 349       | 6.14%   |
| UK           | 253       | 4.45%   |
| India        | 236       | 4.15%   |
| Canada       | 206       | 3.62%   |
| Italy        | 186       | 3.27%   |
| France       | 169       | 2.97%   |
| Australia    | 142       | 2.5%    |
| Netherlands  | 116       | 2.04%   |
| Russia       | 107       | 1.88%   |
| Spain        | 97        | 1.71%   |
| Sweden       | 93        | 1.64%   |
| Poland       | 91        | 1.6%    |
| Portugal     | 82        | 1.44%   |
| Mexico       | 80        | 1.41%   |
| Norway       | 61        | 1.07%   |
| Romania      | 59        | 1.04%   |
| Turkey       | 57        | 1%      |
| Switzerland  | 53        | 0.93%   |
| South Africa | 49        | 0.86%   |
| Indonesia    | 49        | 0.86%   |
| Philippines  | 47        | 0.83%   |
| Finland      | 44        | 0.77%   |
| Denmark      | 43        | 0.76%   |
| Czechia      | 42        | 0.74%   |
| Belgium      | 40        | 0.7%    |
| Greece       | 39        | 0.69%   |
| Argentina    | 39        | 0.69%   |
| New Zealand  | 38        | 0.67%   |
| Austria      | 36        | 0.63%   |
| Chile        | 31        | 0.55%   |
| Hungary      | 26        | 0.46%   |
| Croatia      | 26        | 0.46%   |
| Bulgaria     | 26        | 0.46%   |
| Serbia       | 24        | 0.42%   |
| Ireland      | 24        | 0.42%   |
| Malaysia     | 23        | 0.4%    |
| Colombia     | 22        | 0.39%   |
| Vietnam      | 21        | 0.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 65        | 1.09%   |
| Bengaluru      | 37        | 0.62%   |
| Melbourne      | 35        | 0.59%   |
| Sydney         | 34        | 0.57%   |
| Milan          | 33        | 0.55%   |
| Brisbane       | 32        | 0.54%   |
| Rio de Janeiro | 29        | 0.49%   |
| New York       | 29        | 0.49%   |
| Warsaw         | 27        | 0.45%   |
| Dallas         | 27        | 0.45%   |
| Paris          | 26        | 0.44%   |
| Moscow         | 26        | 0.44%   |
| Helsinki       | 26        | 0.44%   |
| Vienna         | 25        | 0.42%   |
| Madrid         | 25        | 0.42%   |
| London         | 25        | 0.42%   |
| Berlin         | 25        | 0.42%   |
| Istanbul       | 23        | 0.39%   |
| Bucharest      | 23        | 0.39%   |
| Amsterdam      | 23        | 0.39%   |
| Oslo           | 22        | 0.37%   |
| Chicago        | 22        | 0.37%   |
| Athens         | 22        | 0.37%   |
| Rome           | 21        | 0.35%   |
| Los Angeles    | 20        | 0.34%   |
| Auckland       | 20        | 0.34%   |
| Stockholm      | 19        | 0.32%   |
| Sofia          | 19        | 0.32%   |
| Johannesburg   | 18        | 0.3%    |
| Denver         | 18        | 0.3%    |
| Zagreb         | 17        | 0.29%   |
| Toronto        | 17        | 0.29%   |
| St Petersburg  | 17        | 0.29%   |
| Prague         | 17        | 0.29%   |
| Mexico City    | 17        | 0.29%   |
| Lisbon         | 17        | 0.29%   |
| Fortaleza      | 17        | 0.29%   |
| Singapore      | 16        | 0.27%   |
| Calgary        | 16        | 0.27%   |
| Brasília      | 16        | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 1332      | 1814   | 18.31%  |
| WDC                            | 738       | 854    | 10.14%  |
| Seagate                        | 667       | 789    | 9.17%   |
| Sandisk                        | 548       | 711    | 7.53%   |
| Toshiba                        | 448       | 534    | 6.16%   |
| Kingston                       | 390       | 464    | 5.36%   |
| SK hynix                       | 357       | 453    | 4.91%   |
| Unknown                        | 324       | 395    | 4.45%   |
| Crucial                        | 249       | 294    | 3.42%   |
| Intel                          | 243       | 298    | 3.34%   |
| Micron Technology              | 229       | 260    | 3.15%   |
| HGST                           | 196       | 228    | 2.69%   |
| Apple                          | 170       | 185    | 2.34%   |
| Hitachi                        | 109       | 120    | 1.5%    |
| A-DATA Technology              | 102       | 125    | 1.4%    |
| Phison                         | 80        | 98     | 1.1%    |
| KIOXIA                         | 71        | 81     | 0.98%   |
| China                          | 63        | 73     | 0.87%   |
| Micron/Crucial Technology      | 55        | 71     | 0.76%   |
| PNY                            | 54        | 65     | 0.74%   |
| Silicon Motion                 | 47        | 58     | 0.65%   |
| LITEON                         | 45        | 52     | 0.62%   |
| Transcend                      | 41        | 46     | 0.56%   |
| LITEONIT                       | 32        | 48     | 0.44%   |
| Phison Electronics             | 27        | 30     | 0.37%   |
| ADATA Technology               | 26        | 35     | 0.36%   |
| Team                           | 22        | 26     | 0.3%    |
| SPCC                           | 22        | 23     | 0.3%    |
| Kingston Technology Company    | 22        | 23     | 0.3%    |
| JMicron Technology             | 21        | 28     | 0.29%   |
| KingSpec                       | 19        | 21     | 0.26%   |
| Fujitsu                        | 19        | 20     | 0.26%   |
| Unknown                        | 18        | 22     | 0.25%   |
| Solid State Storage Technology | 17        | 20     | 0.23%   |
| Union Memory (Shenzhen)        | 16        | 20     | 0.22%   |
| Patriot                        | 16        | 19     | 0.22%   |
| Netac                          | 16        | 20     | 0.22%   |
| Intenso                        | 15        | 21     | 0.21%   |
| Hewlett-Packard                | 15        | 17     | 0.21%   |
| ASMT                           | 15        | 17     | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                     | 113       | 1.48%   |
| Kingston SA400S37240G 240GB SSD                    | 98        | 1.29%   |
| Samsung NVMe SSD Drive 512GB                       | 80        | 1.05%   |
| HGST HTS721010A9E630 1TB                           | 80        | 1.05%   |
| Unknown MMC Card  64GB                             | 74        | 0.97%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 69        | 0.91%   |
| Toshiba MQ01ABD100 1TB                             | 66        | 0.87%   |
| Samsung NVMe SSD Drive 1TB                         | 64        | 0.84%   |
| Unknown MMC Card  32GB                             | 59        | 0.77%   |
| SK hynix NVMe SSD Drive 512GB                      | 59        | 0.77%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 58        | 0.76%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 57        | 0.75%   |
| Toshiba MQ04ABF100 1TB                             | 55        | 0.72%   |
| SanDisk NVMe SSD Drive 512GB                       | 55        | 0.72%   |
| Samsung NVMe SSD Drive 500GB                       | 52        | 0.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 47        | 0.62%   |
| Intel NVMe SSD Drive 512GB                         | 47        | 0.62%   |
| SanDisk NVMe SSD Drive 1TB                         | 44        | 0.58%   |
| WDC WD10SPZX-24Z10 1TB                             | 43        | 0.56%   |
| Samsung NVMe SSD Drive 1024GB                      | 40        | 0.53%   |
| Seagate ST9500325AS 500GB                          | 39        | 0.51%   |
| Kingston SA400S37480G 480GB SSD                    | 39        | 0.51%   |
| Seagate ST1000LM049-2GH172 1TB                     | 38        | 0.5%    |
| Samsung SSD 860 EVO 500GB                          | 37        | 0.49%   |
| SanDisk NVMe SSD Drive 256GB                       | 36        | 0.47%   |
| Seagate ST500LT012-1DG142 500GB                    | 35        | 0.46%   |
| Crucial CT500MX500SSD1 500GB                       | 34        | 0.45%   |
| Crucial CT240BX500SSD1 240GB                       | 34        | 0.45%   |
| WDC WD10SPZX-21Z10T0 1TB                           | 33        | 0.43%   |
| Unknown MMC Card  128GB                            | 33        | 0.43%   |
| Samsung SSD 850 EVO 250GB                          | 33        | 0.43%   |
| SK hynix NVMe SSD Drive 1024GB                     | 31        | 0.41%   |
| Kingston SA400S37120G 120GB SSD                    | 31        | 0.41%   |
| HGST HTS541010A9E680 1TB                           | 31        | 0.41%   |
| Apple SSD SM0128G 121GB                            | 31        | 0.41%   |
| SK hynix NVMe SSD Drive 256GB                      | 29        | 0.38%   |
| SanDisk NVMe SSD Drive 500GB                       | 29        | 0.38%   |
| Toshiba NVMe SSD Drive 512GB                       | 28        | 0.37%   |
| Seagate Expansion 1TB                              | 28        | 0.37%   |
| Samsung SSD 970 EVO Plus 1TB                       | 28        | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 639       | 744    | 35.58%  |
| WDC                 | 437       | 487    | 24.33%  |
| Toshiba             | 279       | 318    | 15.53%  |
| HGST                | 196       | 228    | 10.91%  |
| Hitachi             | 109       | 120    | 6.07%   |
| Samsung Electronics | 34        | 35     | 1.89%   |
| Unknown             | 27        | 29     | 1.5%    |
| Fujitsu             | 19        | 20     | 1.06%   |
| Apple               | 16        | 18     | 0.89%   |
| JMicron Technology  | 14        | 20     | 0.78%   |
| TO Exter            | 6         | 6      | 0.33%   |
| External            | 5         | 5      | 0.28%   |
| StoreJet            | 3         | 3      | 0.17%   |
| Intenso             | 3         | 7      | 0.17%   |
| ASMT                | 2         | 4      | 0.11%   |
| SABRENT             | 1         | 2      | 0.06%   |
| RSH-339             | 1         | 1      | 0.06%   |
| MaxDigital          | 1         | 1      | 0.06%   |
| Inateck             | 1         | 1      | 0.06%   |
| HGST HDN            | 1         | 1      | 0.06%   |
| DAS                 | 1         | 4      | 0.06%   |
| Asm                 | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 510       | 670    | 21.08%  |
| Kingston            | 296       | 337    | 12.24%  |
| SanDisk             | 242       | 298    | 10%     |
| Crucial             | 229       | 274    | 9.47%   |
| WDC                 | 152       | 189    | 6.28%   |
| Apple               | 131       | 140    | 5.42%   |
| A-DATA Technology   | 67        | 79     | 2.77%   |
| Micron Technology   | 65        | 71     | 2.69%   |
| China               | 63        | 73     | 2.6%    |
| SK hynix            | 62        | 71     | 2.56%   |
| Toshiba             | 56        | 67     | 2.32%   |
| PNY                 | 52        | 63     | 2.15%   |
| Intel               | 46        | 50     | 1.9%    |
| LITEON              | 41        | 48     | 1.69%   |
| Transcend           | 38        | 43     | 1.57%   |
| LITEONIT            | 32        | 48     | 1.32%   |
| SPCC                | 20        | 21     | 0.83%   |
| KingSpec            | 19        | 21     | 0.79%   |
| Patriot             | 15        | 18     | 0.62%   |
| Team                | 14        | 18     | 0.58%   |
| Seagate             | 14        | 15     | 0.58%   |
| OCZ                 | 13        | 13     | 0.54%   |
| Netac               | 13        | 16     | 0.54%   |
| Hewlett-Packard     | 12        | 14     | 0.5%    |
| Lexar               | 11        | 12     | 0.45%   |
| Corsair             | 11        | 12     | 0.45%   |
| Intenso             | 9         | 10     | 0.37%   |
| Dogfish             | 8         | 12     | 0.33%   |
| Apacer              | 8         | 13     | 0.33%   |
| KingDian            | 7         | 8      | 0.29%   |
| SABRENT             | 6         | 7      | 0.25%   |
| GOODRAM             | 6         | 7      | 0.25%   |
| BHT                 | 6         | 6      | 0.25%   |
| ASMT                | 6         | 6      | 0.25%   |
| Plextor             | 5         | 7      | 0.21%   |
| Mushkin             | 5         | 6      | 0.21%   |
| KIOXIA-EXCERIA      | 5         | 5      | 0.21%   |
| Gigabyte Technology | 5         | 7      | 0.21%   |
| Teclast             | 4         | 4      | 0.17%   |
| Maxtor              | 4         | 4      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 2494      | 3499   | 36.47%  |
| SSD     | 2240      | 2902   | 32.76%  |
| HDD     | 1737      | 2055   | 25.4%   |
| MMC     | 270       | 329    | 3.95%   |
| Unknown | 97        | 124    | 1.42%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3469      | 4745   | 53.43%  |
| NVMe | 2492      | 3492   | 38.38%  |
| MMC  | 270       | 329    | 4.16%   |
| SAS  | 262       | 343    | 4.04%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2515      | 3245   | 63.96%  |
| 0.51-1.0   | 1272      | 1525   | 32.35%  |
| 1.01-2.0   | 121       | 149    | 3.08%   |
| 4.01-10.0  | 13        | 22     | 0.33%   |
| 3.01-4.0   | 5         | 5      | 0.13%   |
| 2.01-3.0   | 5         | 9      | 0.13%   |
| 10.01-20.0 | 1         | 2      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1940      | 33.16%  |
| 251-500        | 1661      | 28.39%  |
| 501-1000       | 1096      | 18.74%  |
| 1001-2000      | 399       | 6.82%   |
| 51-100         | 276       | 4.72%   |
| 1-20           | 137       | 2.34%   |
| 21-50          | 131       | 2.24%   |
| 2001-3000      | 93        | 1.59%   |
| More than 3000 | 78        | 1.33%   |
| Unknown        | 39        | 0.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 2319      | 37.75%  |
| 21-50          | 1372      | 22.33%  |
| 101-250        | 818       | 13.32%  |
| 51-100         | 802       | 13.06%  |
| 251-500        | 440       | 7.16%   |
| 501-1000       | 231       | 3.76%   |
| 1001-2000      | 80        | 1.3%    |
| Unknown        | 39        | 0.63%   |
| More than 3000 | 24        | 0.39%   |
| 2001-3000      | 18        | 0.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB        | 5         | 5      | 3.65%   |
| HGST HTS725050A7E630 500GB            | 5         | 8      | 3.65%   |
| Seagate ST1000LX015-1U7172 1TB        | 4         | 4      | 2.92%   |
| HGST HTS721010A9E630 1TB              | 4         | 4      | 2.92%   |
| HGST HTS541010A9E680 1TB              | 4         | 4      | 2.92%   |
| SK hynix PC711 HFS001TDE9X073N 1TB    | 3         | 3      | 2.19%   |
| Seagate ST500LT012-9WS142 500GB       | 3         | 3      | 2.19%   |
| Seagate ST500LT012-1DG142 500GB       | 3         | 3      | 2.19%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 3         | 3      | 2.19%   |
| Hitachi HTS545050A7E380 500GB         | 3         | 5      | 2.19%   |
| WDC WD10JPCX-24UE4T0 1TB              | 2         | 2      | 1.46%   |
| Toshiba MK7559GSXP 752GB              | 2         | 2      | 1.46%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 2         | 2      | 1.46%   |
| Seagate ST9500325AS 500GB             | 2         | 3      | 1.46%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 2         | 2      | 1.46%   |
| Seagate ST1000LM049-2GH172 1TB        | 2         | 2      | 1.46%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD   | 2         | 2      | 1.46%   |
| Kingston SUV400S37120G 120GB SSD      | 2         | 2      | 1.46%   |
| Crucial CT525MX300SSD1 528GB          | 2         | 2      | 1.46%   |
| Crucial CT1000P1SSD8 1TB              | 2         | 2      | 1.46%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD      | 1         | 1      | 0.73%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 0.73%   |
| WDC WDS100T2B0B-00YS70 1TB SSD        | 1         | 1      | 0.73%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 1      | 0.73%   |
| WDC WD5000LPCX-60VHAT0 500GB          | 1         | 1      | 0.73%   |
| WDC WD5000LPCX-21VHAT0 500GB          | 1         | 1      | 0.73%   |
| WDC WD5000BPVT-22HXZT3 500GB          | 1         | 1      | 0.73%   |
| WDC WD5000BPVT-08HXZT3 500GB          | 1         | 1      | 0.73%   |
| WDC WD3200BEKX-75B7WT0 320GB          | 1         | 1      | 0.73%   |
| WDC WD3200BEKT-60PVMT0 320GB          | 1         | 1      | 0.73%   |
| WDC WD2500BEVT-22A23T0 250GB          | 1         | 1      | 0.73%   |
| WDC WD1600BJKT-75F4T0 160GB           | 1         | 1      | 0.73%   |
| WDC WD10SPZX-75Z10T1 1TB              | 1         | 1      | 0.73%   |
| WDC WD10SPZX-24Z10T0 1TB              | 1         | 1      | 0.73%   |
| WDC WD10SPZX-24Z10 1TB                | 1         | 1      | 0.73%   |
| WDC WD10SPZX-22Z10T0 1TB              | 1         | 1      | 0.73%   |
| WDC WD10SPZX-16Z10T0 1TB              | 1         | 1      | 0.73%   |
| WDC WD10SPCX-24HWST1 1TB              | 1         | 1      | 0.73%   |
| WDC WD10JPVX-75JC3T0 1TB              | 1         | 1      | 0.73%   |
| WDC WD10JPVX-60JC3T1 1TB              | 1         | 1      | 0.73%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 30     | 21.17%  |
| WDC                 | 24        | 24     | 17.52%  |
| HGST                | 15        | 18     | 10.95%  |
| Toshiba             | 13        | 14     | 9.49%   |
| SK hynix            | 10        | 12     | 7.3%    |
| Samsung Electronics | 8         | 8      | 5.84%   |
| Hitachi             | 6         | 8      | 4.38%   |
| Crucial             | 6         | 6      | 4.38%   |
| Kingston            | 5         | 5      | 3.65%   |
| A-DATA Technology   | 5         | 5      | 3.65%   |
| Micron Technology   | 4         | 4      | 2.92%   |
| Intel               | 4         | 4      | 2.92%   |
| SanDisk             | 2         | 2      | 1.46%   |
| Team                | 1         | 1      | 0.73%   |
| Silicon Motion      | 1         | 1      | 0.73%   |
| LITEON              | 1         | 1      | 0.73%   |
| Lexar               | 1         | 1      | 0.73%   |
| Leven               | 1         | 1      | 0.73%   |
| China               | 1         | 1      | 0.73%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 29        | 30     | 36.25%  |
| WDC     | 20        | 20     | 25%     |
| HGST    | 15        | 18     | 18.75%  |
| Toshiba | 10        | 10     | 12.5%   |
| Hitachi | 6         | 8      | 7.5%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 80        | 86     | 58.39%  |
| SSD  | 34        | 37     | 24.82%  |
| NVMe | 23        | 23     | 16.79%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics HM321HI 320GB | 1         | 1      | 50%     |
| Intenso JAJP600M1TB               | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 50%     |
| Intenso             | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 4315      | 6777   | 72.78%  |
| Works    | 1475      | 1984   | 24.88%  |
| Malfunc  | 137       | 146    | 2.31%   |
| Failed   | 2         | 2      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 3691      | 51.83%  |
| Samsung Electronics                     | 912       | 12.81%  |
| AMD                                     | 694       | 9.75%   |
| SanDisk                                 | 443       | 6.22%   |
| SK hynix                                | 294       | 4.13%   |
| Micron Technology                       | 164       | 2.3%    |
| Toshiba America Info Systems            | 127       | 1.78%   |
| Kingston Technology Company             | 115       | 1.61%   |
| Phison Electronics                      | 112       | 1.57%   |
| Nvidia                                  | 86        | 1.21%   |
| KIOXIA                                  | 70        | 0.98%   |
| Micron/Crucial Technology               | 69        | 0.97%   |
| ADATA Technology                        | 62        | 0.87%   |
| Silicon Motion                          | 59        | 0.83%   |
| Solid State Storage Technology          | 45        | 0.63%   |
| Union Memory (Shenzhen)                 | 31        | 0.44%   |
| Marvell Technology Group                | 24        | 0.34%   |
| Apple                                   | 23        | 0.32%   |
| Realtek Semiconductor                   | 20        | 0.28%   |
| Seagate Technology                      | 12        | 0.17%   |
| Shenzhen Longsys Electronics            | 11        | 0.15%   |
| Silicon Integrated Systems [SiS]        | 8         | 0.11%   |
| Lite-On Technology                      | 8         | 0.11%   |
| MAXIO Technology (Hangzhou)             | 7         | 0.1%    |
| Lenovo                                  | 6         | 0.08%   |
| JMicron Technology                      | 4         | 0.06%   |
| ASMedia Technology                      | 4         | 0.06%   |
| Yangtze Memory Technologies             | 3         | 0.04%   |
| Solidigm                                | 3         | 0.04%   |
| INNOGRIT                                | 3         | 0.04%   |
| Transcend                               | 2         | 0.03%   |
| Netac Technology                        | 2         | 0.03%   |
| Silicon Image                           | 1         | 0.01%   |
| Shenzhen Unionmemory Information System | 1         | 0.01%   |
| OCZ Technology Group                    | 1         | 0.01%   |
| O2 Micro                                | 1         | 0.01%   |
| Hosin Global Electronics                | 1         | 0.01%   |
| Enmotus                                 | 1         | 0.01%   |
| Biwin Storage Technology                | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 659       | 8.84%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 456       | 6.12%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 441       | 5.92%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 367       | 4.92%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 342       | 4.59%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 314       | 4.21%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 266       | 3.57%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 214       | 2.87%   |
| Intel Volume Management Device NVMe RAID Controller                            | 192       | 2.58%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 170       | 2.28%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 160       | 2.15%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 150       | 2.01%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 139       | 1.87%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 130       | 1.74%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 116       | 1.56%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 109       | 1.46%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 105       | 1.41%   |
| Intel SSD 660P Series                                                          | 104       | 1.4%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 102       | 1.37%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 102       | 1.37%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 97        | 1.3%    |
| Intel Comet Lake SATA AHCI Controller                                          | 94        | 1.26%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 84        | 1.13%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 73        | 0.98%   |
| Phison E12 NVMe Controller                                                     | 58        | 0.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 55        | 0.74%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 54        | 0.72%   |
| Intel Tiger Lake-LP SATA Controller                                            | 54        | 0.72%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 54        | 0.72%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 53        | 0.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 53        | 0.71%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 52        | 0.7%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 51        | 0.68%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 50        | 0.67%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 50        | 0.67%   |
| Nvidia MCP79 AHCI Controller                                                   | 49        | 0.66%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 45        | 0.6%    |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 43        | 0.58%   |
| SK hynix BC511 NVMe SSD                                                        | 38        | 0.51%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 37        | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 3879      | 54.56%  |
| NVMe | 2489      | 35.01%  |
| RAID | 573       | 8.06%   |
| IDE  | 168       | 2.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 4556      | 80.49%  |
| AMD    | 1104      | 19.51%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz             | 139       | 2.45%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 110       | 1.94%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 104       | 1.84%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 99        | 1.75%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 97        | 1.71%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 87        | 1.54%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 82        | 1.45%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 80        | 1.41%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 78        | 1.38%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 78        | 1.38%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 69        | 1.22%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 68        | 1.2%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 67        | 1.18%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 67        | 1.18%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 61        | 1.08%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 61        | 1.08%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 56        | 0.99%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 52        | 0.92%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 51        | 0.9%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 50        | 0.88%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 49        | 0.87%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 48        | 0.85%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 46        | 0.81%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 43        | 0.76%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 42        | 0.74%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 41        | 0.72%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 40        | 0.71%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 40        | 0.71%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 39        | 0.69%   |
| Intel 12th Gen Core i7-12700H                 | 39        | 0.69%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 39        | 0.69%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 38        | 0.67%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 38        | 0.67%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 37        | 0.65%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 36        | 0.64%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 35        | 0.62%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 34        | 0.6%    |
| AMD Ryzen 5 4500U with Radeon Graphics        | 33        | 0.58%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 32        | 0.57%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 32        | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 1614      | 28.52%  |
| Intel Core i5           | 1410      | 24.91%  |
| Other                   | 573       | 10.12%  |
| Intel Core i3           | 343       | 6.06%   |
| AMD Ryzen 7             | 318       | 5.62%   |
| AMD Ryzen 5             | 312       | 5.51%   |
| Intel Core 2 Duo        | 187       | 3.3%    |
| Intel Celeron           | 183       | 3.23%   |
| AMD Ryzen 9             | 71        | 1.25%   |
| AMD Ryzen 3             | 63        | 1.11%   |
| Intel Pentium           | 62        | 1.1%    |
| Intel Core i9           | 53        | 0.94%   |
| AMD A6                  | 53        | 0.94%   |
| AMD Ryzen 7 PRO         | 49        | 0.87%   |
| AMD A8                  | 41        | 0.72%   |
| AMD A10                 | 35        | 0.62%   |
| Intel Pentium Dual-Core | 34        | 0.6%    |
| AMD A4                  | 26        | 0.46%   |
| Intel Atom              | 20        | 0.35%   |
| Intel Core 2            | 17        | 0.3%    |
| Intel Xeon              | 15        | 0.27%   |
| Intel Pentium Dual      | 14        | 0.25%   |
| AMD E1                  | 14        | 0.25%   |
| Intel Genuine           | 13        | 0.23%   |
| Intel Core m3           | 13        | 0.23%   |
| AMD Ryzen 5 PRO         | 13        | 0.23%   |
| AMD Athlon              | 13        | 0.23%   |
| AMD E                   | 12        | 0.21%   |
| AMD E2                  | 10        | 0.18%   |
| Intel Pentium Silver    | 8         | 0.14%   |
| AMD FX                  | 8         | 0.14%   |
| AMD A12                 | 7         | 0.12%   |
| Intel Core M            | 6         | 0.11%   |
| AMD Turion 64 X2 Mobile | 6         | 0.11%   |
| Intel Core m5           | 5         | 0.09%   |
| AMD Athlon X2           | 5         | 0.09%   |
| Intel Celeron Dual-Core | 4         | 0.07%   |
| AMD C-60                | 4         | 0.07%   |
| AMD Phenom II           | 3         | 0.05%   |
| AMD V120                | 2         | 0.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2351      | 41.54%  |
| 4      | 1943      | 34.33%  |
| 6      | 588       | 10.39%  |
| 8      | 559       | 9.88%   |
| 14     | 85        | 1.5%    |
| 12     | 44        | 0.78%   |
| 10     | 41        | 0.72%   |
| 1      | 26        | 0.46%   |
| 16     | 12        | 0.21%   |
| 24     | 8         | 0.14%   |
| 7      | 1         | 0.02%   |
| 5      | 1         | 0.02%   |
| 3      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 5660      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 4789      | 84.55%  |
| 1      | 875       | 15.45%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 5653      | 99.88%  |
| Unknown        | 7         | 0.12%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 3911      | 67.48%  |
| 0x906ea    | 152       | 2.62%   |
| 0x806ea    | 108       | 1.86%   |
| 0x306a9    | 101       | 1.74%   |
| 0x806ec    | 98        | 1.69%   |
| 0x806c1    | 94        | 1.62%   |
| 0x206a7    | 92        | 1.59%   |
| 0x406e3    | 86        | 1.48%   |
| 0x40651    | 80        | 1.38%   |
| 0xa0652    | 75        | 1.29%   |
| 0x806e9    | 62        | 1.07%   |
| 0x0a50000c | 60        | 1.04%   |
| 0x306c3    | 57        | 0.98%   |
| 0x906e9    | 53        | 0.91%   |
| 0x08108102 | 48        | 0.83%   |
| 0x306d4    | 40        | 0.69%   |
| 0x08600106 | 40        | 0.69%   |
| 0x806d1    | 37        | 0.64%   |
| 0x1067a    | 35        | 0.6%    |
| 0x806eb    | 34        | 0.59%   |
| 0x506e3    | 34        | 0.59%   |
| 0x08108109 | 32        | 0.55%   |
| 0x906ed    | 28        | 0.48%   |
| 0x08608103 | 28        | 0.48%   |
| 0x906a3    | 25        | 0.43%   |
| 0x08600104 | 25        | 0.43%   |
| 0x20655    | 22        | 0.38%   |
| 0x706e5    | 20        | 0.35%   |
| 0x08600103 | 20        | 0.35%   |
| 0x06006705 | 18        | 0.31%   |
| 0x0810100b | 16        | 0.28%   |
| 0x0a404102 | 15        | 0.26%   |
| 0x706a1    | 13        | 0.22%   |
| 0x0a50000d | 13        | 0.22%   |
| 0x0a404101 | 13        | 0.22%   |
| 0x40661    | 11        | 0.19%   |
| 0x10676    | 11        | 0.19%   |
| 0x07030105 | 10        | 0.17%   |
| 0xa0660    | 9         | 0.16%   |
| 0x906a4    | 9         | 0.16%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1295      | 22.84%  |
| Haswell          | 497       | 8.77%   |
| SandyBridge      | 399       | 7.04%   |
| IvyBridge        | 371       | 6.54%   |
| Unknown          | 327       | 5.77%   |
| Skylake          | 319       | 5.63%   |
| TigerLake        | 262       | 4.62%   |
| Zen+             | 220       | 3.88%   |
| CometLake        | 213       | 3.76%   |
| Broadwell        | 205       | 3.62%   |
| Penryn           | 202       | 3.56%   |
| Zen 3            | 201       | 3.55%   |
| Zen 2            | 200       | 3.53%   |
| Westmere         | 155       | 2.73%   |
| IceLake          | 110       | 1.94%   |
| Alderlake Hybrid | 92        | 1.62%   |
| Silvermont       | 88        | 1.55%   |
| Core             | 75        | 1.32%   |
| Excavator        | 73        | 1.29%   |
| Goldmont plus    | 66        | 1.16%   |
| Zen              | 58        | 1.02%   |
| Puma             | 45        | 0.79%   |
| Piledriver       | 38        | 0.67%   |
| Bobcat           | 28        | 0.49%   |
| Goldmont         | 25        | 0.44%   |
| Nehalem          | 18        | 0.32%   |
| Steamroller      | 17        | 0.3%    |
| K10 Llano        | 17        | 0.3%    |
| Jaguar           | 15        | 0.26%   |
| K8 Hammer        | 12        | 0.21%   |
| K8 & K10 hybrid  | 9         | 0.16%   |
| K10              | 9         | 0.16%   |
| Bonnell          | 4         | 0.07%   |
| Tremont          | 3         | 0.05%   |
| Gracemont        | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4150      | 54.81%  |
| Nvidia                           | 2051      | 27.09%  |
| AMD                              | 1363      | 18%     |
| Silicon Integrated Systems [SiS] | 6         | 0.08%   |
| S3 Graphics                      | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 361       | 4.66%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 357       | 4.61%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 341       | 4.4%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 267       | 3.45%   |
| Intel UHD Graphics 620                                                                   | 246       | 3.18%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 245       | 3.16%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 220       | 2.84%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 200       | 2.58%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 190       | 2.45%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 190       | 2.45%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 174       | 2.25%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 173       | 2.23%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 169       | 2.18%   |
| Intel HD Graphics 620                                                                    | 163       | 2.1%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 161       | 2.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 144       | 1.86%   |
| Intel HD Graphics 5500                                                                   | 143       | 1.85%   |
| Intel HD Graphics 630                                                                    | 127       | 1.64%   |
| Intel Core Processor Integrated Graphics Controller                                      | 120       | 1.55%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 98        | 1.26%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 97        | 1.25%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 87        | 1.12%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 85        | 1.1%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 84        | 1.08%   |
| AMD Lucienne                                                                             | 82        | 1.06%   |
| Intel HD Graphics 530                                                                    | 75        | 0.97%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 72        | 0.93%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 69        | 0.89%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 63        | 0.81%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 61        | 0.79%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 60        | 0.77%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 59        | 0.76%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 57        | 0.74%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 57        | 0.74%   |
| Nvidia GP108M [GeForce MX150]                                                            | 56        | 0.72%   |
| AMD Rembrandt [Radeon 680M]                                                              | 56        | 0.72%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 55        | 0.71%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 53        | 0.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 52        | 0.67%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 48        | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 2545      | 44.66%  |
| Intel + Nvidia     | 1403      | 24.62%  |
| 1 x AMD            | 784       | 13.76%  |
| 1 x Nvidia         | 362       | 6.35%   |
| AMD + Nvidia       | 261       | 4.58%   |
| Intel + AMD        | 208       | 3.65%   |
| 2 x AMD            | 113       | 1.98%   |
| 2 x Nvidia         | 10        | 0.18%   |
| 1 x SiS            | 6         | 0.11%   |
| Other              | 3         | 0.05%   |
| Intel + 2 x Nvidia | 2         | 0.04%   |
| 2 x Intel          | 1         | 0.02%   |
| 1 x S3 Graphics    | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 3957      | 69.18%  |
| Proprietary | 1624      | 28.39%  |
| Unknown     | 139       | 2.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 4402      | 76.48%  |
| 1.01-2.0   | 352       | 6.12%   |
| 3.01-4.0   | 322       | 5.59%   |
| 0.01-0.5   | 238       | 4.13%   |
| 5.01-6.0   | 191       | 3.32%   |
| 7.01-8.0   | 111       | 1.93%   |
| 0.51-1.0   | 97        | 1.69%   |
| 2.01-3.0   | 29        | 0.5%    |
| 8.01-16.0  | 14        | 0.24%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1165      | 17.68%  |
| Chimei Innolux          | 959       | 14.55%  |
| LG Display              | 891       | 13.52%  |
| BOE                     | 889       | 13.49%  |
| Samsung Electronics     | 589       | 8.94%   |
| Apple                   | 283       | 4.29%   |
| Sharp                   | 241       | 3.66%   |
| Dell                    | 202       | 3.07%   |
| Goldstar                | 197       | 2.99%   |
| PANDA                   | 158       | 2.4%    |
| Chi Mei Optoelectronics | 103       | 1.56%   |
| Lenovo                  | 92        | 1.4%    |
| Acer                    | 68        | 1.03%   |
| AOC                     | 67        | 1.02%   |
| Hewlett-Packard         | 64        | 0.97%   |
| InfoVision              | 62        | 0.94%   |
| Philips                 | 53        | 0.8%    |
| BenQ                    | 48        | 0.73%   |
| CSO                     | 42        | 0.64%   |
| ASUSTek Computer        | 35        | 0.53%   |
| Ancor Communications    | 35        | 0.53%   |
| ViewSonic               | 23        | 0.35%   |
| TMX                     | 17        | 0.26%   |
| Iiyama                  | 16        | 0.24%   |
| Sony                    | 14        | 0.21%   |
| Panasonic               | 14        | 0.21%   |
| LG Philips              | 14        | 0.21%   |
| Vizio                   | 11        | 0.17%   |
| MSI                     | 10        | 0.15%   |
| InnoLux Display         | 10        | 0.15%   |
| Toshiba                 | 9         | 0.14%   |
| Sceptre Tech            | 9         | 0.14%   |
| JDI                     | 8         | 0.12%   |
| Vestel Elektronik       | 7         | 0.11%   |
| Hitachi                 | 6         | 0.09%   |
| RTK                     | 5         | 0.08%   |
| NEC Computers           | 5         | 0.08%   |
| LGD                     | 5         | 0.08%   |
| HUAWEI                  | 5         | 0.08%   |
| HKC                     | 5         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 64        | 0.96%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 58        | 0.87%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 52        | 0.78%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 51        | 0.77%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 50        | 0.75%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 47        | 0.71%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 43        | 0.65%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 39        | 0.59%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 34        | 0.51%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 32        | 0.48%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch              | 30        | 0.45%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 30        | 0.45%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 29        | 0.44%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch           | 27        | 0.41%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch     | 26        | 0.39%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 26        | 0.39%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 24        | 0.36%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                  | 24        | 0.36%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 24        | 0.36%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 24        | 0.36%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 23        | 0.35%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 22        | 0.33%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 22        | 0.33%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 21        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch          | 20        | 0.3%    |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 19        | 0.29%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                    | 19        | 0.29%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                      | 19        | 0.29%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                   | 18        | 0.27%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch           | 18        | 0.27%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 18        | 0.27%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                      | 18        | 0.27%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 17        | 0.26%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                   | 17        | 0.26%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch              | 17        | 0.26%   |
| Chimei Innolux LCD Monitor CMN1408 1920x1080 309x173mm 13.9-inch          | 17        | 0.26%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch             | 17        | 0.26%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                   | 16        | 0.24%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch              | 16        | 0.24%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                      | 16        | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2925      | 47.38%  |
| 1366x768 (WXGA)    | 1505      | 24.38%  |
| 3840x2160 (4K)     | 316       | 5.12%   |
| 1600x900 (HD+)     | 242       | 3.92%   |
| 2560x1440 (QHD)    | 222       | 3.6%    |
| 1280x800 (WXGA)    | 145       | 2.35%   |
| 1920x1200 (WUXGA)  | 136       | 2.2%    |
| 1440x900 (WXGA+)   | 111       | 1.8%    |
| 2560x1600          | 106       | 1.72%   |
| 2880x1800          | 80        | 1.3%    |
| 2560x1080          | 53        | 0.86%   |
| 3840x2400          | 40        | 0.65%   |
| 3440x1440          | 39        | 0.63%   |
| 1680x1050 (WSXGA+) | 37        | 0.6%    |
| 2160x1440          | 22        | 0.36%   |
| 3200x1800 (QHD+)   | 20        | 0.32%   |
| 1360x768           | 18        | 0.29%   |
| 2256x1504          | 16        | 0.26%   |
| 1280x1024 (SXGA)   | 16        | 0.26%   |
| 3072x1920          | 15        | 0.24%   |
| 1920x540           | 13        | 0.21%   |
| 3840x1080          | 11        | 0.18%   |
| 3000x2000          | 10        | 0.16%   |
| 3456x2160          | 7         | 0.11%   |
| 3200x2000          | 7         | 0.11%   |
| Unknown            | 6         | 0.1%    |
| 3840x1100          | 4         | 0.06%   |
| 2304x1440          | 4         | 0.06%   |
| 2240x1400          | 4         | 0.06%   |
| 1920x1280          | 4         | 0.06%   |
| 2880x1620          | 3         | 0.05%   |
| 2560x1700          | 3         | 0.05%   |
| 2520x1680          | 3         | 0.05%   |
| 1680x945           | 3         | 0.05%   |
| 1280x720 (HD)      | 3         | 0.05%   |
| 800x1280           | 2         | 0.03%   |
| 3840x1600          | 2         | 0.03%   |
| 3840x1200          | 2         | 0.03%   |
| 2288x1287          | 2         | 0.03%   |
| 1920x515           | 2         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 2730      | 41.49%  |
| 13      | 1005      | 15.27%  |
| 14      | 759       | 11.53%  |
| 17      | 468       | 7.11%   |
| 27      | 233       | 3.54%   |
| 24      | 194       | 2.95%   |
| 23      | 159       | 2.42%   |
| 16      | 139       | 2.11%   |
| 12      | 135       | 2.05%   |
| 21      | 129       | 1.96%   |
| 31      | 99        | 1.5%    |
| 34      | 79        | 1.2%    |
| 11      | 79        | 1.2%    |
| 18      | 55        | 0.84%   |
| Unknown | 44        | 0.67%   |
| 19      | 36        | 0.55%   |
| 32      | 24        | 0.36%   |
| 40      | 23        | 0.35%   |
| 84      | 22        | 0.33%   |
| 22      | 19        | 0.29%   |
| 20      | 19        | 0.29%   |
| 72      | 15        | 0.23%   |
| 54      | 13        | 0.2%    |
| 48      | 11        | 0.17%   |
| 25      | 9         | 0.14%   |
| 26      | 8         | 0.12%   |
| 52      | 7         | 0.11%   |
| 28      | 7         | 0.11%   |
| 35      | 6         | 0.09%   |
| 46      | 5         | 0.08%   |
| 39      | 5         | 0.08%   |
| 33      | 5         | 0.08%   |
| 29      | 5         | 0.08%   |
| 10      | 5         | 0.08%   |
| 49      | 4         | 0.06%   |
| 65      | 3         | 0.05%   |
| 37      | 3         | 0.05%   |
| 74      | 2         | 0.03%   |
| 47      | 2         | 0.03%   |
| 42      | 2         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 4045      | 61.91%  |
| 201-300        | 710       | 10.87%  |
| 351-400        | 567       | 8.68%   |
| 501-600        | 537       | 8.22%   |
| 401-500        | 246       | 3.76%   |
| 601-700        | 142       | 2.17%   |
| 701-800        | 109       | 1.67%   |
| 1001-1500      | 49        | 0.75%   |
| Unknown        | 44        | 0.67%   |
| 1501-2000      | 41        | 0.63%   |
| 801-900        | 34        | 0.52%   |
| 901-1000       | 5         | 0.08%   |
| 101-200        | 2         | 0.03%   |
| 1-100          | 2         | 0.03%   |
| More than 2000 | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 4813      | 83.81%  |
| 16/10   | 694       | 12.08%  |
| 21/9    | 95        | 1.65%   |
| 3/2     | 66        | 1.15%   |
| Unknown | 23        | 0.4%    |
| 5/4     | 19        | 0.33%   |
| 32/9    | 12        | 0.21%   |
| 4/3     | 8         | 0.14%   |
| 3.40    | 4         | 0.07%   |
| 6/5     | 2         | 0.03%   |
| 3.73    | 2         | 0.03%   |
| 3.20    | 1         | 0.02%   |
| 0.67    | 1         | 0.02%   |
| 0.63    | 1         | 0.02%   |
| 0.62    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 2723      | 41.46%  |
| 81-90          | 1423      | 21.67%  |
| 121-130        | 437       | 6.65%   |
| 201-250        | 420       | 6.39%   |
| 71-80          | 329       | 5.01%   |
| 301-350        | 240       | 3.65%   |
| 351-500        | 213       | 3.24%   |
| 111-120        | 130       | 1.98%   |
| 61-70          | 128       | 1.95%   |
| 151-200        | 86        | 1.31%   |
| 51-60          | 83        | 1.26%   |
| More than 1000 | 74        | 1.13%   |
| 251-300        | 61        | 0.93%   |
| 141-150        | 59        | 0.9%    |
| 501-1000       | 54        | 0.82%   |
| Unknown        | 44        | 0.67%   |
| 131-140        | 38        | 0.58%   |
| 91-100         | 17        | 0.26%   |
| 41-50          | 5         | 0.08%   |
| 1-40           | 4         | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 2863      | 44.48%  |
| 101-120       | 1745      | 27.11%  |
| 51-100        | 885       | 13.75%  |
| 161-240       | 529       | 8.22%   |
| More than 240 | 289       | 4.49%   |
| 1-50          | 81        | 1.26%   |
| Unknown       | 44        | 0.68%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 4492      | 77.45%  |
| 2     | 999       | 17.22%  |
| 0     | 181       | 3.12%   |
| 3     | 121       | 2.09%   |
| 4     | 7         | 0.12%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 3093      | 33.96%  |
| Intel                                 | 3024      | 33.2%   |
| Qualcomm Atheros                      | 1197      | 13.14%  |
| Broadcom                              | 610       | 6.7%    |
| MediaTek                              | 182       | 2%      |
| Broadcom Limited                      | 179       | 1.97%   |
| Marvell Technology Group              | 69        | 0.76%   |
| ASIX Electronics                      | 69        | 0.76%   |
| Ralink                                | 64        | 0.7%    |
| Nvidia                                | 59        | 0.65%   |
| TP-Link                               | 53        | 0.58%   |
| Ralink Technology                     | 46        | 0.51%   |
| Samsung Electronics                   | 44        | 0.48%   |
| DisplayLink                           | 34        | 0.37%   |
| Dell                                  | 32        | 0.35%   |
| Qualcomm                              | 28        | 0.31%   |
| Lenovo                                | 28        | 0.31%   |
| Xiaomi                                | 26        | 0.29%   |
| Sierra Wireless                       | 26        | 0.29%   |
| Ericsson Business Mobile Networks     | 23        | 0.25%   |
| JMicron Technology                    | 21        | 0.23%   |
| Hewlett-Packard                       | 17        | 0.19%   |
| Google                                | 17        | 0.19%   |
| ASUSTek Computer                      | 17        | 0.19%   |
| OnePlus Technology (Shenzhen)         | 12        | 0.13%   |
| NetGear                               | 12        | 0.13%   |
| OPPO Electronics                      | 11        | 0.12%   |
| Huawei Technologies                   | 11        | 0.12%   |
| Motorola PCS                          | 10        | 0.11%   |
| D-Link                                | 9         | 0.1%    |
| Silicon Integrated Systems [SiS]      | 8         | 0.09%   |
| Linksys                               | 6         | 0.07%   |
| Edimax Technology                     | 6         | 0.07%   |
| Apple                                 | 6         | 0.07%   |
| Qualcomm Atheros Communications       | 5         | 0.05%   |
| Microsoft                             | 5         | 0.05%   |
| Fibocom                               | 5         | 0.05%   |
| Arduino SA                            | 4         | 0.04%   |
| ICS Advent                            | 3         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1969      | 18.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 462       | 4.3%    |
| Intel Wi-Fi 6 AX200                                                    | 374       | 3.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 264       | 2.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 250       | 2.33%   |
| Intel Wireless 8265 / 8275                                             | 232       | 2.16%   |
| Intel Wi-Fi 6 AX201                                                    | 199       | 1.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 192       | 1.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 182       | 1.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 182       | 1.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 179       | 1.67%   |
| Intel Wireless 7260                                                    | 178       | 1.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 175       | 1.63%   |
| Intel Wireless 7265                                                    | 161       | 1.5%    |
| Intel Comet Lake PCH CNVi WiFi                                         | 158       | 1.47%   |
| Intel Wireless 8260                                                    | 146       | 1.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 144       | 1.34%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 132       | 1.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 128       | 1.19%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 116       | 1.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 114       | 1.06%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 113       | 1.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 112       | 1.04%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 98        | 0.91%   |
| Broadcom BCM43142 802.11b/g/n                                          | 89        | 0.83%   |
| Intel Ethernet Connection (4) I219-LM                                  | 79        | 0.74%   |
| Intel Wireless 3165                                                    | 77        | 0.72%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 77        | 0.72%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 73        | 0.68%   |
| Intel Ethernet Connection I219-LM                                      | 72        | 0.67%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 70        | 0.65%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 66        | 0.61%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 65        | 0.61%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 64        | 0.6%    |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 64        | 0.6%    |
| Intel Wireless 3160                                                    | 61        | 0.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 59        | 0.55%   |
| Intel Ethernet Connection I218-LM                                      | 59        | 0.55%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 57        | 0.53%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 57        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2919      | 49.51%  |
| Qualcomm Atheros                      | 1002      | 16.99%  |
| Realtek Semiconductor                 | 814       | 13.81%  |
| Broadcom                              | 522       | 8.85%   |
| MediaTek                              | 178       | 3.02%   |
| Broadcom Limited                      | 145       | 2.46%   |
| Ralink                                | 64        | 1.09%   |
| TP-Link                               | 46        | 0.78%   |
| Ralink Technology                     | 46        | 0.78%   |
| Dell                                  | 27        | 0.46%   |
| Sierra Wireless                       | 26        | 0.44%   |
| Qualcomm                              | 24        | 0.41%   |
| ASUSTek Computer                      | 14        | 0.24%   |
| NetGear                               | 11        | 0.19%   |
| D-Link                                | 9         | 0.15%   |
| Hewlett-Packard                       | 7         | 0.12%   |
| Edimax Technology                     | 6         | 0.1%    |
| Qualcomm Atheros Communications       | 5         | 0.08%   |
| Fibocom                               | 5         | 0.08%   |
| Microsoft                             | 4         | 0.07%   |
| Linksys                               | 3         | 0.05%   |
| Ericsson Business Mobile Networks     | 3         | 0.05%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.05%   |
| D-Link System                         | 2         | 0.03%   |
| ZyDAS                                 | 1         | 0.02%   |
| Wilocity                              | 1         | 0.02%   |
| Sitecom Europe                        | 1         | 0.02%   |
| Samsung Electronics                   | 1         | 0.02%   |
| Philips (or NXP)                      | 1         | 0.02%   |
| Ovislink                              | 1         | 0.02%   |
| Micro Star International              | 1         | 0.02%   |
| Chu Yuen Enterprise                   | 1         | 0.02%   |
| AVM                                   | 1         | 0.02%   |
| Arduino SA                            | 1         | 0.02%   |
| Accton Technology                     | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 374       | 6.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 264       | 4.45%   |
| Intel Wireless 8265 / 8275                                           | 232       | 3.91%   |
| Intel Wi-Fi 6 AX201                                                  | 199       | 3.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 182       | 3.07%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 182       | 3.07%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 179       | 3.02%   |
| Intel Wireless 7260                                                  | 178       | 3%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 175       | 2.95%   |
| Intel Wireless 7265                                                  | 161       | 2.71%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 158       | 2.66%   |
| Intel Wireless 8260                                                  | 146       | 2.46%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 144       | 2.43%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 132       | 2.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 128       | 2.16%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 116       | 1.96%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 114       | 1.92%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 113       | 1.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 112       | 1.89%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 98        | 1.65%   |
| Broadcom BCM43142 802.11b/g/n                                        | 89        | 1.5%    |
| Intel Wireless 3165                                                  | 77        | 1.3%    |
| Intel Tiger Lake PCH CNVi WiFi                                       | 77        | 1.3%    |
| Broadcom BCM4331 802.11a/b/g/n                                       | 73        | 1.23%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 66        | 1.11%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 65        | 1.1%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 64        | 1.08%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 64        | 1.08%   |
| Intel Wireless 3160                                                  | 61        | 1.03%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 59        | 0.99%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 57        | 0.96%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 57        | 0.96%   |
| Intel Centrino Ultimate-N 6300                                       | 54        | 0.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 52        | 0.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 50        | 0.84%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 47        | 0.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 46        | 0.78%   |
| Intel Centrino Advanced-N 6235                                       | 45        | 0.76%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 43        | 0.72%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 38        | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2780      | 59.22%  |
| Intel                                  | 896       | 19.09%  |
| Qualcomm Atheros                       | 313       | 6.67%   |
| Broadcom                               | 207       | 4.41%   |
| Marvell Technology Group               | 69        | 1.47%   |
| ASIX Electronics                       | 69        | 1.47%   |
| Nvidia                                 | 59        | 1.26%   |
| Samsung Electronics                    | 43        | 0.92%   |
| Broadcom Limited                       | 38        | 0.81%   |
| DisplayLink                            | 34        | 0.72%   |
| Lenovo                                 | 28        | 0.6%    |
| Xiaomi                                 | 26        | 0.55%   |
| JMicron Technology                     | 21        | 0.45%   |
| Google                                 | 17        | 0.36%   |
| OPPO Electronics                       | 11        | 0.23%   |
| OnePlus Technology (Shenzhen)          | 11        | 0.23%   |
| Silicon Integrated Systems [SiS]       | 8         | 0.17%   |
| Huawei Technologies                    | 8         | 0.17%   |
| TP-Link                                | 7         | 0.15%   |
| Motorola PCS                           | 7         | 0.15%   |
| Apple                                  | 5         | 0.11%   |
| Qualcomm                               | 4         | 0.09%   |
| Hewlett-Packard                        | 4         | 0.09%   |
| MediaTek                               | 3         | 0.06%   |
| Linksys                                | 3         | 0.06%   |
| ICS Advent                             | 3         | 0.06%   |
| ASUSTek Computer                       | 3         | 0.06%   |
| T & A Mobile Phones                    | 2         | 0.04%   |
| LSI                                    | 2         | 0.04%   |
| LG Electronics                         | 2         | 0.04%   |
| Aquantia                               | 2         | 0.04%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.02%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.02%   |
| Research In Motion                     | 1         | 0.02%   |
| NTmore                                 | 1         | 0.02%   |
| NetGear                                | 1         | 0.02%   |
| Microsoft                              | 1         | 0.02%   |
| Foxconn / Hon Hai                      | 1         | 0.02%   |
| Cypress Semiconductor                  | 1         | 0.02%   |
| Attansic Technology                    | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1969      | 41.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 462       | 9.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 250       | 5.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 192       | 4.04%   |
| Intel Ethernet Connection (4) I219-LM                                  | 79        | 1.66%   |
| Intel Ethernet Connection I219-LM                                      | 72        | 1.52%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 70        | 1.47%   |
| Intel Ethernet Connection I218-LM                                      | 59        | 1.24%   |
| ASIX AX88179 Gigabit Ethernet                                          | 56        | 1.18%   |
| Intel Ethernet Connection I217-LM                                      | 55        | 1.16%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 54        | 1.14%   |
| Realtek RTL8125 2.5GbE Controller                                      | 48        | 1.01%   |
| Nvidia MCP79 Ethernet                                                  | 45        | 0.95%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 44        | 0.93%   |
| Intel Ethernet Connection (3) I218-LM                                  | 43        | 0.9%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 38        | 0.8%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 36        | 0.76%   |
| Realtek Killer E2600 GbE Controller                                    | 35        | 0.74%   |
| Intel Ethernet Connection (4) I219-V                                   | 35        | 0.74%   |
| Intel 82577LM Gigabit Network Connection                               | 33        | 0.69%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 32        | 0.67%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 30        | 0.63%   |
| Intel Ethernet Connection (7) I219-LM                                  | 29        | 0.61%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 26        | 0.55%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 25        | 0.53%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 23        | 0.48%   |
| Intel Ethernet Connection (6) I219-V                                   | 23        | 0.48%   |
| Intel Ethernet Connection (13) I219-V                                  | 23        | 0.48%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 22        | 0.46%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 22        | 0.46%   |
| Intel Ethernet Connection I219-V                                       | 22        | 0.46%   |
| Intel Ethernet Connection (7) I219-V                                   | 22        | 0.46%   |
| Intel 82567LM Gigabit Network Connection                               | 22        | 0.46%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 22        | 0.46%   |
| Intel Ethernet Connection (2) I219-LM                                  | 21        | 0.44%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 20        | 0.42%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 20        | 0.42%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 20        | 0.42%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 19        | 0.4%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 19        | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 5596      | 55.31%  |
| Ethernet | 4465      | 44.13%  |
| Modem    | 43        | 0.43%   |
| Unknown  | 13        | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4759      | 78.92%  |
| Ethernet | 1271      | 21.08%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 4055      | 71.59%  |
| 1     | 1530      | 27.01%  |
| 0     | 44        | 0.78%   |
| 3     | 35        | 0.62%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4444      | 77.33%  |
| Yes  | 1303      | 22.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2472      | 51.1%   |
| Qualcomm Atheros Communications | 454       | 9.38%   |
| Realtek Semiconductor           | 437       | 9.03%   |
| Apple                           | 301       | 6.22%   |
| IMC Networks                    | 261       | 5.39%   |
| Lite-On Technology              | 215       | 4.44%   |
| Broadcom                        | 205       | 4.24%   |
| Foxconn / Hon Hai               | 163       | 3.37%   |
| Dell                            | 71        | 1.47%   |
| Cambridge Silicon Radio         | 45        | 0.93%   |
| Realtek                         | 34        | 0.7%    |
| Ralink                          | 33        | 0.68%   |
| Toshiba                         | 32        | 0.66%   |
| Hewlett-Packard                 | 30        | 0.62%   |
| ASUSTek Computer                | 17        | 0.35%   |
| Foxconn International           | 12        | 0.25%   |
| MediaTek                        | 10        | 0.21%   |
| Ralink Technology               | 8         | 0.17%   |
| Alps Electric                   | 7         | 0.14%   |
| USI                             | 4         | 0.08%   |
| Smart Modular Technologies      | 4         | 0.08%   |
| Askey Computer                  | 4         | 0.08%   |
| Taiyo Yuden                     | 3         | 0.06%   |
| Qcom                            | 3         | 0.06%   |
| Opticis                         | 3         | 0.06%   |
| TP-Link                         | 2         | 0.04%   |
| Fujitsu                         | 2         | 0.04%   |
| SINO WEALTH                     | 1         | 0.02%   |
| Micro Star International        | 1         | 0.02%   |
| Integrated System Solution      | 1         | 0.02%   |
| Dynex                           | 1         | 0.02%   |
| Creative Technology             | 1         | 0.02%   |
| Actions                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 830       | 17.15%  |
| Intel AX201 Bluetooth                               | 505       | 10.43%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 385       | 7.95%   |
| Intel AX200 Bluetooth                               | 367       | 7.58%   |
| Realtek Bluetooth Radio                             | 288       | 5.95%   |
| Qualcomm Atheros  Bluetooth Device                  | 253       | 5.23%   |
| Apple Bluetooth Host Controller                     | 175       | 3.62%   |
| Intel Bluetooth Device                              | 157       | 3.24%   |
| Realtek  Bluetooth 4.2 Adapter                      | 111       | 2.29%   |
| Apple Bluetooth USB Host Controller                 | 91        | 1.88%   |
| IMC Networks Bluetooth Radio                        | 80        | 1.65%   |
| IMC Networks Wireless_Device                        | 79        | 1.63%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 78        | 1.61%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 71        | 1.47%   |
| Intel AX210 Bluetooth                               | 62        | 1.28%   |
| Foxconn / Hon Hai Bluetooth Device                  | 60        | 1.24%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 55        | 1.14%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 51        | 1.05%   |
| IMC Networks Bluetooth Device                       | 50        | 1.03%   |
| Lite-On Bluetooth Device                            | 49        | 1.01%   |
| Foxconn / Hon Hai Wireless_Device                   | 48        | 0.99%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 46        | 0.95%   |
| Intel Wireless-AC 3168 Bluetooth                    | 46        | 0.95%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 45        | 0.93%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 43        | 0.89%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 41        | 0.85%   |
| Broadcom BCM2045B (BDC-2.1)                         | 37        | 0.76%   |
| Realtek Bluetooth Radio                             | 34        | 0.7%    |
| Ralink RT3290 Bluetooth                             | 33        | 0.68%   |
| Dell DW375 Bluetooth Module                         | 27        | 0.56%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 26        | 0.54%   |
| Lite-On Atheros AR3012 Bluetooth                    | 24        | 0.5%    |
| Lite-On Wireless_Device                             | 23        | 0.48%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 20        | 0.41%   |
| Apple Bluetooth HCI                                 | 20        | 0.41%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 19        | 0.39%   |
| HP Broadcom 2070 Bluetooth Combo                    | 19        | 0.39%   |
| Dell BCM20702A0 Bluetooth Module                    | 17        | 0.35%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 17        | 0.35%   |
| Foxconn / Hon Hai BCM20702A0                        | 16        | 0.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 4449      | 59.77%  |
| Nvidia                                          | 1304      | 17.52%  |
| AMD                                             | 1192      | 16.01%  |
| C-Media Electronics                             | 60        | 0.81%   |
| Logitech                                        | 49        | 0.66%   |
| Realtek Semiconductor                           | 45        | 0.6%    |
| Lenovo                                          | 30        | 0.4%    |
| GN Netcom                                       | 26        | 0.35%   |
| JMTek                                           | 25        | 0.34%   |
| Kingston Technology                             | 19        | 0.26%   |
| Generalplus Technology                          | 18        | 0.24%   |
| Apple                                           | 18        | 0.24%   |
| Texas Instruments                               | 16        | 0.21%   |
| Sony                                            | 12        | 0.16%   |
| Razer USA                                       | 12        | 0.16%   |
| Plantronics                                     | 12        | 0.16%   |
| Corsair                                         | 12        | 0.16%   |
| Hewlett-Packard                                 | 11        | 0.15%   |
| SteelSeries ApS                                 | 9         | 0.12%   |
| Silicon Integrated Systems [SiS]                | 8         | 0.11%   |
| Focusrite-Novation                              | 8         | 0.11%   |
| Sennheiser Communications                       | 6         | 0.08%   |
| FiiO Electronics Technology                     | 6         | 0.08%   |
| Creative Technology                             | 5         | 0.07%   |
| ASUSTek Computer                                | 5         | 0.07%   |
| Samson Technologies                             | 4         | 0.05%   |
| Yamaha                                          | 3         | 0.04%   |
| TerraTec Electronic                             | 3         | 0.04%   |
| Tenx Technology                                 | 3         | 0.04%   |
| No brand                                        | 3         | 0.04%   |
| GYROCOM C&C                                     | 3         | 0.04%   |
| DSEA A/S                                        | 3         | 0.04%   |
| Dell                                            | 3         | 0.04%   |
| Blue Microphones                                | 3         | 0.04%   |
| XMOS                                            | 2         | 0.03%   |
| Turtle Beach                                    | 2         | 0.03%   |
| Thesycon Systemsoftware & Consulting            | 2         | 0.03%   |
| Pioneer DJ                                      | 2         | 0.03%   |
| Licensed by Sony Computer Entertainment America | 2         | 0.03%   |
| CMX Systems                                     | 2         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 814       | 9%      |
| Intel Sunrise Point-LP HD Audio                                            | 654       | 7.23%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 422       | 4.67%   |
| Intel Cannon Lake PCH cAVS                                                 | 389       | 4.3%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 371       | 4.1%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 346       | 3.83%   |
| Intel 8 Series HD Audio Controller                                         | 269       | 2.97%   |
| Intel Haswell-ULT HD Audio Controller                                      | 267       | 2.95%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 262       | 2.9%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 244       | 2.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 231       | 2.55%   |
| Intel Broadwell-U Audio Controller                                         | 205       | 2.27%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 197       | 2.18%   |
| Intel Comet Lake PCH cAVS                                                  | 194       | 2.14%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 176       | 1.95%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 173       | 1.91%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 169       | 1.87%   |
| Intel Comet Lake PCH-LP cAVS                                               | 164       | 1.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 162       | 1.79%   |
| Nvidia TU106 High Definition Audio Controller                              | 147       | 1.63%   |
| AMD FCH Azalia Controller                                                  | 146       | 1.61%   |
| Intel CM238 HD Audio Controller                                            | 143       | 1.58%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 139       | 1.54%   |
| Nvidia Audio device                                                        | 125       | 1.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 119       | 1.32%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 103       | 1.14%   |
| Nvidia GA106 High Definition Audio Controller                              | 99        | 1.09%   |
| Nvidia GP107GL High Definition Audio Controller                            | 98        | 1.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 96        | 1.06%   |
| Nvidia GA104 High Definition Audio Controller                              | 90        | 1%      |
| AMD Kabini HDMI/DP Audio                                                   | 85        | 0.94%   |
| Nvidia GP106 High Definition Audio Controller                              | 75        | 0.83%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 72        | 0.8%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 66        | 0.73%   |
| Nvidia TU116 High Definition Audio Controller                              | 64        | 0.71%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 64        | 0.71%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 59        | 0.65%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 58        | 0.64%   |
| Nvidia GK107 HDMI Audio Controller                                         | 52        | 0.57%   |
| Nvidia GF108 High Definition Audio Controller                              | 50        | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 564       | 29.12%  |
| SK hynix                                | 449       | 23.18%  |
| Micron Technology                       | 268       | 13.84%  |
| Kingston                                | 155       | 8%      |
| Crucial                                 | 104       | 5.37%   |
| Unknown                                 | 60        | 3.1%    |
| A-DATA Technology                       | 41        | 2.12%   |
| Smart                                   | 34        | 1.76%   |
| Ramaxel Technology                      | 33        | 1.7%    |
| Corsair                                 | 30        | 1.55%   |
| Goldkey                                 | 22        | 1.14%   |
| Elpida                                  | 22        | 1.14%   |
| Neo Forza                               | 20        | 1.03%   |
| Unknown                                 | 19        | 0.98%   |
| G.Skill                                 | 18        | 0.93%   |
| Unknown (ABCD)                          | 12        | 0.62%   |
| Team                                    | 10        | 0.52%   |
| Smart Brazil                            | 10        | 0.52%   |
| Teikon                                  | 7         | 0.36%   |
| Nanya Technology                        | 6         | 0.31%   |
| Apacer                                  | 5         | 0.26%   |
| PNY                                     | 4         | 0.21%   |
| Transcend                               | 3         | 0.15%   |
| Timetec                                 | 3         | 0.15%   |
| Patriot                                 | 3         | 0.15%   |
| High Bridge                             | 3         | 0.15%   |
| GSkill                                  | 3         | 0.15%   |
| ChangXin Memory                         | 3         | 0.15%   |
| Avant                                   | 3         | 0.15%   |
| GOODRAM                                 | 2         | 0.1%    |
| Gold Key                                | 2         | 0.1%    |
| CSX                                     | 2         | 0.1%    |
| Wilk                                    | 1         | 0.05%   |
| Unknown (8A02)                          | 1         | 0.05%   |
| Unknown (898F)                          | 1         | 0.05%   |
| Unknown (0x0CAB)                        | 1         | 0.05%   |
| Unknown (09B6)                          | 1         | 0.05%   |
| Unknown (09A4)                          | 1         | 0.05%   |
| Silicon Power Computer & Communications | 1         | 0.05%   |
| Silicon Power                           | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 50        | 2.46%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 32        | 1.58%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 30        | 1.48%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 25        | 1.23%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 23        | 1.13%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 21        | 1.03%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 19        | 0.94%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 19        | 0.94%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 19        | 0.94%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 19        | 0.94%   |
| Unknown                                                             | 19        | 0.94%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 17        | 0.84%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 17        | 0.84%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 16        | 0.79%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 15        | 0.74%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 15        | 0.74%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 14        | 0.69%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 14        | 0.69%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 14        | 0.69%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 14        | 0.69%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 14        | 0.69%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 13        | 0.64%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 13        | 0.64%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s                | 13        | 0.64%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 12        | 0.59%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 12        | 0.59%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 12        | 0.59%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 12        | 0.59%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 12        | 0.59%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 11        | 0.54%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 11        | 0.54%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 11        | 0.54%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s              | 11        | 0.54%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s               | 11        | 0.54%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 10        | 0.49%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s             | 10        | 0.49%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 10        | 0.49%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 10        | 0.49%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 10        | 0.49%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s        | 10        | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1053      | 64.84%  |
| DDR3    | 297       | 18.29%  |
| LPDDR4  | 85        | 5.23%   |
| LPDDR3  | 68        | 4.19%   |
| DDR5    | 64        | 3.94%   |
| LPDDR5  | 38        | 2.34%   |
| DDR2    | 10        | 0.62%   |
| SDRAM   | 5         | 0.31%   |
| Unknown | 4         | 0.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1415      | 85.65%  |
| Row Of Chips | 216       | 13.08%  |
| Chip         | 13        | 0.79%   |
| DIMM         | 4         | 0.24%   |
| Unknown      | 4         | 0.24%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 796       | 44.9%   |
| 4096  | 403       | 22.73%  |
| 16384 | 378       | 21.32%  |
| 32768 | 100       | 5.64%   |
| 2048  | 85        | 4.79%   |
| 1024  | 11        | 0.62%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 482       | 27.37%  |
| 3200    | 447       | 25.38%  |
| 1600    | 239       | 13.57%  |
| 2400    | 148       | 8.4%    |
| 2133    | 100       | 5.68%   |
| 4800    | 51        | 2.9%    |
| 4267    | 42        | 2.39%   |
| 6400    | 37        | 2.1%    |
| 1334    | 32        | 1.82%   |
| 3266    | 30        | 1.7%    |
| 1867    | 24        | 1.36%   |
| 1333    | 22        | 1.25%   |
| 8400    | 19        | 1.08%   |
| 4266    | 14        | 0.8%    |
| 5600    | 13        | 0.74%   |
| 1067    | 12        | 0.68%   |
| 800     | 9         | 0.51%   |
| 3733    | 8         | 0.45%   |
| 1866    | 5         | 0.28%   |
| 2933    | 4         | 0.23%   |
| 667     | 4         | 0.23%   |
| 4199    | 3         | 0.17%   |
| Unknown | 3         | 0.17%   |
| 3000    | 2         | 0.11%   |
| 2048    | 2         | 0.11%   |
| 1066    | 2         | 0.11%   |
| 5500    | 1         | 0.06%   |
| 5200    | 1         | 0.06%   |
| 3466    | 1         | 0.06%   |
| 3400    | 1         | 0.06%   |
| 3333    | 1         | 0.06%   |
| 1200    | 1         | 0.06%   |
| 666     | 1         | 0.06%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 9         | 30%     |
| Seiko Epson         | 6         | 20%     |
| Canon               | 5         | 16.67%  |
| Brother Industries  | 4         | 13.33%  |
| Samsung Electronics | 2         | 6.67%   |
| Xerox               | 1         | 3.33%   |
| MIIIW               | 1         | 3.33%   |
| ICS Advent          | 1         | 3.33%   |
| Dymo-CoStar         | 1         | 3.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Samsung M2020 Series            | 2         | 6.67%   |
| Canon PIXMA MX920 Series        | 2         | 6.67%   |
| Xerox B215                      | 1         | 3.33%   |
| Seiko Epson WF-3520 Series      | 1         | 3.33%   |
| Seiko Epson L6160 Series        | 1         | 3.33%   |
| Seiko Epson L382 Series         | 1         | 3.33%   |
| Seiko Epson L3110 Series        | 1         | 3.33%   |
| Seiko Epson L132 Series         | 1         | 3.33%   |
| Seiko Epson ET-2700 Series      | 1         | 3.33%   |
| MIIIW MW Keyboard Air Mini      | 1         | 3.33%   |
| ICS Advent Parallel Adapter     | 1         | 3.33%   |
| HP OfficeJet 3830 series        | 1         | 3.33%   |
| HP Ink Tank Wireless 410 series | 1         | 3.33%   |
| HP ENVY Photo 7800 series       | 1         | 3.33%   |
| HP ENVY 4520 series             | 1         | 3.33%   |
| HP DeskJet Plus 4100 series     | 1         | 3.33%   |
| HP Deskjet 3050 J610 series     | 1         | 3.33%   |
| HP Deskjet 2540 series          | 1         | 3.33%   |
| HP Deskjet 2050 J510            | 1         | 3.33%   |
| HP Color LaserJet CP2025dn      | 1         | 3.33%   |
| Dymo-CoStar LabelWriter 450     | 1         | 3.33%   |
| Canon GX7000 series             | 1         | 3.33%   |
| Canon G4010 series              | 1         | 3.33%   |
| Canon E400 series               | 1         | 3.33%   |
| Brother HL-L2370DW series       | 1         | 3.33%   |
| Brother HL-L2320D series        | 1         | 3.33%   |
| Brother HL-3170CDW series       | 1         | 3.33%   |
| Brother HL-2270DW Laser Printer | 1         | 3.33%   |

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
| Chicony Electronics                    | 1195      | 23.54%  |
| IMC Networks                           | 551       | 10.86%  |
| Microdia                               | 495       | 9.75%   |
| Realtek Semiconductor                  | 411       | 8.1%    |
| Bison Electronics                      | 370       | 7.29%   |
| Sunplus Innovation Technology          | 280       | 5.52%   |
| Quanta                                 | 268       | 5.28%   |
| Apple                                  | 224       | 4.41%   |
| Cheng Uei Precision Industry (Foxlink) | 171       | 3.37%   |
| Acer                                   | 156       | 3.07%   |
| Suyin                                  | 130       | 2.56%   |
| Syntek                                 | 128       | 2.52%   |
| Lite-On Technology                     | 106       | 2.09%   |
| Luxvisions Innotech Limited            | 90        | 1.77%   |
| Silicon Motion                         | 71        | 1.4%    |
| Logitech                               | 66        | 1.3%    |
| Ricoh                                  | 39        | 0.77%   |
| Alcor Micro                            | 37        | 0.73%   |
| Sonix Technology                       | 35        | 0.69%   |
| Samsung Electronics                    | 30        | 0.59%   |
| SunplusIT                              | 17        | 0.33%   |
| ALi                                    | 15        | 0.3%    |
| Primax Electronics                     | 13        | 0.26%   |
| Z-Star Microelectronics                | 11        | 0.22%   |
| Microsoft                              | 11        | 0.22%   |
| Lenovo                                 | 11        | 0.22%   |
| Importek                               | 11        | 0.22%   |
| DigiTech                               | 10        | 0.2%    |
| Intel                                  | 8         | 0.16%   |
| OmniVision Technologies                | 7         | 0.14%   |
| Generalplus Technology                 | 7         | 0.14%   |
| USB Camera                             | 6         | 0.12%   |
| ShineTech                              | 5         | 0.1%    |
| Razer USA                              | 5         | 0.1%    |
| AVerMedia Technologies                 | 5         | 0.1%    |
| 8SSC21K12273V1SR33X2817                | 5         | 0.1%    |
| Tobii Technology AB                    | 4         | 0.08%   |
| MacroSilicon                           | 4         | 0.08%   |
| Foxconn / Hon Hai                      | 4         | 0.08%   |
| 8SSC20F27114V1SR0BK1X4S                | 4         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 267       | 5.24%   |
| Chicony Integrated Camera                           | 245       | 4.8%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 178       | 3.49%   |
| Realtek Integrated_Webcam_HD                        | 171       | 3.35%   |
| Chicony HD WebCam                                   | 165       | 3.24%   |
| IMC Networks Integrated Camera                      | 154       | 3.02%   |
| Bison BisonCam,NB Pro                               | 113       | 2.22%   |
| Chicony USB2.0 Camera                               | 101       | 1.98%   |
| Sunplus Integrated_Webcam_HD                        | 81        | 1.59%   |
| Syntek Integrated Camera                            | 80        | 1.57%   |
| Bison Integrated Camera                             | 80        | 1.57%   |
| Apple Built-in iSight                               | 72        | 1.41%   |
| Apple FaceTime HD Camera                            | 71        | 1.39%   |
| Quanta HD User Facing                               | 60        | 1.18%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 57        | 1.12%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 49        | 0.96%   |
| Realtek USB Camera                                  | 44        | 0.86%   |
| Lite-On Integrated Camera                           | 43        | 0.84%   |
| Chicony USB 2.0 Camera                              | 42        | 0.82%   |
| Chicony HP HD Camera                                | 39        | 0.76%   |
| Microdia Integrated Webcam                          | 38        | 0.75%   |
| Chicony HD User Facing                              | 37        | 0.73%   |
| Chicony Integrated Camera (1280x720@30)             | 36        | 0.71%   |
| Acer SunplusIT Integrated Camera                    | 36        | 0.71%   |
| Sunplus Asus Webcam                                 | 35        | 0.69%   |
| Quanta HD Webcam                                    | 35        | 0.69%   |
| Microdia Laptop_Integrated_Webcam_HD                | 34        | 0.67%   |
| Chicony TOSHIBA Web Camera - HD                     | 34        | 0.67%   |
| Sunplus HD WebCam                                   | 33        | 0.65%   |
| Quanta HP TrueVision HD Camera                      | 33        | 0.65%   |
| Acer HD Webcam                                      | 33        | 0.65%   |
| Chicony USB2.0 HD UVC WebCam                        | 32        | 0.63%   |
| Bison HD Webcam                                     | 32        | 0.63%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 31        | 0.61%   |
| Chicony USB2.0 VGA UVC WebCam                       | 30        | 0.59%   |
| Chicony HP TrueVision HD Camera                     | 30        | 0.59%   |
| Realtek Integrated Webcam                           | 29        | 0.57%   |
| Chicony HP Wide Vision HD Camera                    | 29        | 0.57%   |
| Acer BisonCam, NB Pro                               | 29        | 0.57%   |
| Samsung Galaxy series, misc. (MTP mode)             | 27        | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 312       | 31.71%  |
| Validity Sensors                   | 297       | 30.18%  |
| Shenzhen Goodix Technology         | 169       | 17.17%  |
| Upek                               | 55        | 5.59%   |
| Elan Microelectronics              | 55        | 5.59%   |
| LighTuning Technology              | 42        | 4.27%   |
| AuthenTec                          | 29        | 2.95%   |
| STMicroelectronics                 | 7         | 0.71%   |
| Realtek USB2.0 Finger Print Bridge | 7         | 0.71%   |
| Focal-systems.Corp                 | 5         | 0.51%   |
| HOLTEK                             | 4         | 0.41%   |
| Samsung Electronics                | 1         | 0.1%    |
| DigitalPersona                     | 1         | 0.1%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 97        | 9.86%   |
| Shenzhen Goodix  Fingerprint Device                                        | 84        | 8.54%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 68        | 6.91%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 60        | 6.1%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 50        | 5.08%   |
| Shenzhen Goodix FingerPrint                                                | 50        | 5.08%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 42        | 4.27%   |
| Elan ELAN:Fingerprint                                                      | 39        | 3.96%   |
| Shenzhen Goodix Fingerprint Reader                                         | 35        | 3.56%   |
| Synaptics TouchPad                                                         | 27        | 2.74%   |
| Validity Sensors Synaptics WBDI                                            | 23        | 2.34%   |
| Synaptics WBDI Device                                                      | 23        | 2.34%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 22        | 2.24%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 22        | 2.24%   |
| Validity Sensors VFS491                                                    | 21        | 2.13%   |
| Validity Sensors Fingerprint scanner                                       | 21        | 2.13%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 21        | 2.13%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 20        | 2.03%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 20        | 2.03%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 18        | 1.83%   |
| Unknown                                                                    | 17        | 1.73%   |
| Elan ELAN:ARM-M4                                                           | 16        | 1.63%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 15        | 1.52%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 15        | 1.52%   |
| Synaptics Fingerprint reader [HP G6]                                       | 13        | 1.32%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 12        | 1.22%   |
| Synaptics  WBDI                                                            | 11        | 1.12%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 10        | 1.02%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 10        | 1.02%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 0.91%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 8         | 0.81%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 0.71%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 7         | 0.71%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 0.71%   |
| AuthenTec AES2810                                                          | 7         | 0.71%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 0.71%   |
| Validity Sensors VFS Fingerprint sensor                                    | 6         | 0.61%   |
| Synaptics UWP WBDI Device                                                  | 6         | 0.61%   |
| Upek TCS5B Fingerprint sensor                                              | 5         | 0.51%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 5         | 0.51%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 177       | 49.3%   |
| Alcor Micro               | 99        | 27.58%  |
| Upek                      | 29        | 8.08%   |
| O2 Micro                  | 27        | 7.52%   |
| Lenovo                    | 18        | 5.01%   |
| Gemalto (was Gemplus)     | 2         | 0.56%   |
| Aladdin Knowledge Systems | 2         | 0.56%   |
| SCM Microsystems          | 1         | 0.28%   |
| OmniKey                   | 1         | 0.28%   |
| Giesecke & Devrient       | 1         | 0.28%   |
| Clay Logic                | 1         | 0.28%   |
| Advanced Card Systems     | 1         | 0.28%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 99        | 27.58%  |
| Broadcom BCM5880 Secure Applications Processor                               | 50        | 13.93%  |
| Broadcom 5880                                                                | 47        | 13.09%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 42        | 11.7%   |
| Broadcom 58200                                                               | 35        | 9.75%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 29        | 8.08%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 23        | 6.41%   |
| Lenovo Integrated Smart Card Reader                                          | 18        | 5.01%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.11%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 3         | 0.84%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.56%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.28%   |
| OmniKey CardMan 4321                                                         | 1         | 0.28%   |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.28%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.28%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.28%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.28%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.28%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 3527      | 61.12%  |
| 1     | 1775      | 30.76%  |
| 2     | 408       | 7.07%   |
| 3     | 52        | 0.9%    |
| 4     | 7         | 0.12%   |
| 6     | 1         | 0.02%   |
| 5     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 960       | 35.6%   |
| Multimedia controller    | 374       | 13.87%  |
| Chipcard                 | 349       | 12.94%  |
| Graphics card            | 337       | 12.5%   |
| Net/wireless             | 310       | 11.49%  |
| Bluetooth                | 94        | 3.49%   |
| Camera                   | 82        | 3.04%   |
| Storage                  | 43        | 1.59%   |
| Net/ethernet             | 35        | 1.3%    |
| Sound                    | 32        | 1.19%   |
| Card reader              | 21        | 0.78%   |
| Communication controller | 18        | 0.67%   |
| Network                  | 14        | 0.52%   |
| Modem                    | 14        | 0.52%   |
| Storage/ide              | 5         | 0.19%   |
| Storage/nvme             | 3         | 0.11%   |
| Flash memory             | 2         | 0.07%   |
| Firewire controller      | 2         | 0.07%   |
| Unclassified device      | 1         | 0.04%   |
| Dvb card                 | 1         | 0.04%   |


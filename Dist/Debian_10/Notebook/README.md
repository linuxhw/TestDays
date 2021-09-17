Debian 10 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Debian 10.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=debian-10

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [232a307a5b](https://linux-hardware.org/?probe=232a307a5b) | Sep 14, 2021 |
| Lenovo        | ThinkPad T590 20N4000BFR    | [834ddc5e6a](https://linux-hardware.org/?probe=834ddc5e6a) | Sep 13, 2021 |
| Intel         | Intel powered classmate ... | [15cb9c7764](https://linux-hardware.org/?probe=15cb9c7764) | Sep 12, 2021 |
| Dell          | Inspiron 5420               | [bc80b42442](https://linux-hardware.org/?probe=bc80b42442) | Sep 12, 2021 |
| Lenovo        | QIWY3                       | [9da123bf89](https://linux-hardware.org/?probe=9da123bf89) | Sep 09, 2021 |
| Lenovo        | QIWY3                       | [552b695b27](https://linux-hardware.org/?probe=552b695b27) | Sep 09, 2021 |
| GTZS          | Unknown                     | [e5d931aaf8](https://linux-hardware.org/?probe=e5d931aaf8) | Sep 06, 2021 |
| HP            | ProBook 6460b               | [7d379f011c](https://linux-hardware.org/?probe=7d379f011c) | Sep 04, 2021 |
| Lenovo        | ThinkPad R60 9462A45        | [5850a811e3](https://linux-hardware.org/?probe=5850a811e3) | Sep 01, 2021 |
| HP            | 250 G4 Notebook PC          | [2cf6464047](https://linux-hardware.org/?probe=2cf6464047) | Aug 31, 2021 |
| HP            | EliteBook 850 G5            | [68149f9864](https://linux-hardware.org/?probe=68149f9864) | Aug 30, 2021 |
| Dell          | Studio XPS 1640             | [f0765cb8c8](https://linux-hardware.org/?probe=f0765cb8c8) | Aug 28, 2021 |
| Dell          | Studio XPS 1640             | [1e772e0237](https://linux-hardware.org/?probe=1e772e0237) | Aug 28, 2021 |
| Lenovo        | ThinkPad X220 429044C       | [20057996af](https://linux-hardware.org/?probe=20057996af) | Aug 27, 2021 |
| Acer          | TravelMate 7750G            | [8d3d35021f](https://linux-hardware.org/?probe=8d3d35021f) | Aug 27, 2021 |
| Itautec       | Infoway w7535               | [f7d8a66820](https://linux-hardware.org/?probe=f7d8a66820) | Aug 27, 2021 |
| Lenovo        | ThinkPad X260 20F5S3J00D    | [eeb6586c28](https://linux-hardware.org/?probe=eeb6586c28) | Aug 26, 2021 |
| ASUSTek       | P751JA                      | [0ba110ae45](https://linux-hardware.org/?probe=0ba110ae45) | Aug 25, 2021 |
| HP            | ProBook 6460b               | [c8226af22c](https://linux-hardware.org/?probe=c8226af22c) | Aug 25, 2021 |
| TQ-Group      | TQMxE39S                    | [69363368e2](https://linux-hardware.org/?probe=69363368e2) | Aug 23, 2021 |
| Unknown       | Unknown                     | [4a85a76b94](https://linux-hardware.org/?probe=4a85a76b94) | Aug 21, 2021 |
| Toshiba       | Satellite C55D-B            | [3aa4e38d51](https://linux-hardware.org/?probe=3aa4e38d51) | Aug 21, 2021 |
| Itautec       | Infoway w7535               | [ea3f721976](https://linux-hardware.org/?probe=ea3f721976) | Aug 21, 2021 |
| Acer          | Aspire S5-371               | [5e3fcc0daa](https://linux-hardware.org/?probe=5e3fcc0daa) | Aug 21, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [e4ab15ad86](https://linux-hardware.org/?probe=e4ab15ad86) | Aug 16, 2021 |
| ASUSTek       | N550JV                      | [631e697061](https://linux-hardware.org/?probe=631e697061) | Aug 13, 2021 |
| ASUSTek       | N550JV                      | [191ce05579](https://linux-hardware.org/?probe=191ce05579) | Aug 13, 2021 |
| Apple         | MacBookPro9,2               | [10a9ce514b](https://linux-hardware.org/?probe=10a9ce514b) | Aug 11, 2021 |
| Apple         | MacBookPro9,2               | [4a08b4bc9c](https://linux-hardware.org/?probe=4a08b4bc9c) | Aug 11, 2021 |
| Google        | Careena                     | [a715f6f37f](https://linux-hardware.org/?probe=a715f6f37f) | Aug 10, 2021 |
| HP            | Pavilion Notebook           | [f8742367c3](https://linux-hardware.org/?probe=f8742367c3) | Aug 10, 2021 |
| HP            | Pavilion Notebook           | [7401df03e4](https://linux-hardware.org/?probe=7401df03e4) | Aug 09, 2021 |
| Gateway       | MD7811U                     | [fdd99ed1fe](https://linux-hardware.org/?probe=fdd99ed1fe) | Aug 09, 2021 |
| Gateway       | MD7811U                     | [07d8dcb0ff](https://linux-hardware.org/?probe=07d8dcb0ff) | Aug 08, 2021 |
| DNS           | 101                         | [83fc7e7928](https://linux-hardware.org/?probe=83fc7e7928) | Aug 08, 2021 |
| Lenovo        | ThinkPad T480s 20L7002AU... | [d19a600e79](https://linux-hardware.org/?probe=d19a600e79) | Aug 07, 2021 |
| ASUSTek       | N56VZ                       | [4080b39f00](https://linux-hardware.org/?probe=4080b39f00) | Aug 07, 2021 |
| Sony          | VPCS110FL                   | [2227fd7ae7](https://linux-hardware.org/?probe=2227fd7ae7) | Aug 07, 2021 |
| Sony          | VPCS110FL                   | [1741c7d3db](https://linux-hardware.org/?probe=1741c7d3db) | Aug 07, 2021 |
| Apple         | MacBookPro9,2               | [f4e31f03fb](https://linux-hardware.org/?probe=f4e31f03fb) | Aug 07, 2021 |
| Dell          | G3 3590                     | [16bdb588e1](https://linux-hardware.org/?probe=16bdb588e1) | Aug 05, 2021 |
| Dell          | G3 3590                     | [01a9560f9c](https://linux-hardware.org/?probe=01a9560f9c) | Aug 05, 2021 |
| Dell          | Precision 3530              | [f2fb6b98ea](https://linux-hardware.org/?probe=f2fb6b98ea) | Aug 03, 2021 |
| Lenovo        | ThinkPad R60 9462A45        | [95aacb86f6](https://linux-hardware.org/?probe=95aacb86f6) | Jul 31, 2021 |
| Lenovo        | ThinkPad T490 20N2002AUS    | [557f9a87fa](https://linux-hardware.org/?probe=557f9a87fa) | Jul 30, 2021 |
| MSI           | U210/U210 Light             | [98d5949e01](https://linux-hardware.org/?probe=98d5949e01) | Jul 29, 2021 |
| ASUSTek       | X205TA                      | [37efd6fc5e](https://linux-hardware.org/?probe=37efd6fc5e) | Jul 26, 2021 |
| Lenovo        | B51-35 80LH                 | [662fffc9d2](https://linux-hardware.org/?probe=662fffc9d2) | Jul 25, 2021 |
| Lenovo        | B51-35 80LH                 | [bdaceebba4](https://linux-hardware.org/?probe=bdaceebba4) | Jul 25, 2021 |
| Lenovo        | ThinkPad X250 20CLS1G70A    | [7330b29e94](https://linux-hardware.org/?probe=7330b29e94) | Jul 25, 2021 |
| Lenovo        | ThinkPad X250 20CLS1G70A    | [1a104c4440](https://linux-hardware.org/?probe=1a104c4440) | Jul 25, 2021 |
| Acer          | AO725                       | [4e27f519f7](https://linux-hardware.org/?probe=4e27f519f7) | Jul 25, 2021 |
| Dell          | Vostro 1500                 | [f78b977663](https://linux-hardware.org/?probe=f78b977663) | Jul 25, 2021 |
| Lenovo        | ThinkPad L390 20NRCTO1WW    | [0d77ee3e3d](https://linux-hardware.org/?probe=0d77ee3e3d) | Jul 22, 2021 |
| Acer          | Aspire A715-72G             | [d977beba9e](https://linux-hardware.org/?probe=d977beba9e) | Jul 22, 2021 |
| Toshiba       | Satellite M70               | [ffe4b92da3](https://linux-hardware.org/?probe=ffe4b92da3) | Jul 21, 2021 |
| ASUSTek       | TUF Gaming FX506LU_FX506... | [a347415235](https://linux-hardware.org/?probe=a347415235) | Jul 19, 2021 |
| Unknown       | Unknown                     | [69cc932202](https://linux-hardware.org/?probe=69cc932202) | Jul 17, 2021 |
| MSI           | GF65 Thin 10UE              | [0a875bd8bb](https://linux-hardware.org/?probe=0a875bd8bb) | Jul 15, 2021 |
| Dell          | Latitude E6420              | [e2e96ce9d8](https://linux-hardware.org/?probe=e2e96ce9d8) | Jul 14, 2021 |
| Dell          | Latitude E6420              | [eb1224a5ff](https://linux-hardware.org/?probe=eb1224a5ff) | Jul 14, 2021 |
| Acer          | Swift SF114-33              | [7aa338a8dc](https://linux-hardware.org/?probe=7aa338a8dc) | Jul 12, 2021 |
| One Educat... | Infinity:One                | [2f6016cb80](https://linux-hardware.org/?probe=2f6016cb80) | Jul 12, 2021 |
| HP            | ProBook 6460b               | [094d8f1435](https://linux-hardware.org/?probe=094d8f1435) | Jul 10, 2021 |
| ASUSTek       | K56CB                       | [112f34cf11](https://linux-hardware.org/?probe=112f34cf11) | Jul 09, 2021 |
| HP            | Spectre Laptop 13-af0xx     | [bfef4cded0](https://linux-hardware.org/?probe=bfef4cded0) | Jul 09, 2021 |
| Acer          | E1-510                      | [b1b6133207](https://linux-hardware.org/?probe=b1b6133207) | Jul 08, 2021 |
| Dell          | Latitude E6420              | [4facd06f69](https://linux-hardware.org/?probe=4facd06f69) | Jul 08, 2021 |
| Lenovo        | ThinkPad R60 9462A45        | [541bb57585](https://linux-hardware.org/?probe=541bb57585) | Jul 07, 2021 |
| ASUSTek       | VivoBook S14 X411UF         | [f5a3e8f307](https://linux-hardware.org/?probe=f5a3e8f307) | Jul 06, 2021 |
| Lenovo        | ThinkPad L590 20Q7CTO1WW    | [ec305ddc45](https://linux-hardware.org/?probe=ec305ddc45) | Jul 05, 2021 |
| Lenovo        | B50-10 80QR                 | [56044931dc](https://linux-hardware.org/?probe=56044931dc) | Jul 04, 2021 |
| Dell          | Latitude E6430              | [0c6585a784](https://linux-hardware.org/?probe=0c6585a784) | Jun 30, 2021 |
| Dell          | Inspiron 3421               | [1900fb77ec](https://linux-hardware.org/?probe=1900fb77ec) | Jun 29, 2021 |
| Lenovo        | ThinkPad E15 20RD0011GE     | [d4a28fa40a](https://linux-hardware.org/?probe=d4a28fa40a) | Jun 27, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [fc58981ecd](https://linux-hardware.org/?probe=fc58981ecd) | Jun 27, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [bce9c74edb](https://linux-hardware.org/?probe=bce9c74edb) | Jun 27, 2021 |
| Unknown       | Unknown                     | [25dc027ef1](https://linux-hardware.org/?probe=25dc027ef1) | Jun 26, 2021 |
| Lenovo        | ThinkPad X230 23252EG       | [77c68fb077](https://linux-hardware.org/?probe=77c68fb077) | Jun 23, 2021 |
| HP            | EliteBook 830 G7 Noteboo... | [0240acc863](https://linux-hardware.org/?probe=0240acc863) | Jun 22, 2021 |
| HP            | EliteBook 830 G7 Noteboo... | [f64428c049](https://linux-hardware.org/?probe=f64428c049) | Jun 22, 2021 |
| Dell          | Latitude 7480               | [28d1d17f13](https://linux-hardware.org/?probe=28d1d17f13) | Jun 22, 2021 |
| Dell          | Latitude E6430              | [f0afba2500](https://linux-hardware.org/?probe=f0afba2500) | Jun 21, 2021 |
| Timi          | TM1612                      | [c4fb55cbfd](https://linux-hardware.org/?probe=c4fb55cbfd) | Jun 21, 2021 |
| Lenovo        | B50-10 80QR                 | [3da8d18204](https://linux-hardware.org/?probe=3da8d18204) | Jun 20, 2021 |
| Lenovo        | B50-10 80QR                 | [847e763107](https://linux-hardware.org/?probe=847e763107) | Jun 20, 2021 |
| Timi          | TM1612                      | [dcb999a722](https://linux-hardware.org/?probe=dcb999a722) | Jun 20, 2021 |
| HP            | ProBook 6460b               | [dacf1e8349](https://linux-hardware.org/?probe=dacf1e8349) | Jun 20, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [3518f65e84](https://linux-hardware.org/?probe=3518f65e84) | Jun 18, 2021 |
| Dell          | Latitude 5420               | [1356be4391](https://linux-hardware.org/?probe=1356be4391) | Jun 18, 2021 |
| VIT           | P2400                       | [295d4d5a47](https://linux-hardware.org/?probe=295d4d5a47) | Jun 17, 2021 |
| Fujitsu       | LIFEBOOK BH531              | [688d9f583e](https://linux-hardware.org/?probe=688d9f583e) | Jun 16, 2021 |
| Sony          | VGN-FW21L                   | [fe6647a4b1](https://linux-hardware.org/?probe=fe6647a4b1) | Jun 15, 2021 |
| Sony          | VGN-FW21E                   | [f46b41cd2f](https://linux-hardware.org/?probe=f46b41cd2f) | Jun 15, 2021 |
| Dell          | XPS 13 9310                 | [278fd058ed](https://linux-hardware.org/?probe=278fd058ed) | Jun 14, 2021 |
| HP            | Laptop 15s-fq2xxx           | [b592b452fe](https://linux-hardware.org/?probe=b592b452fe) | Jun 12, 2021 |
| IBM           | ThinkPad T42 23736YG        | [fbf7c66f92](https://linux-hardware.org/?probe=fbf7c66f92) | Jun 12, 2021 |
| HP            | Compaq Presario CQ71        | [37a87224fb](https://linux-hardware.org/?probe=37a87224fb) | Jun 12, 2021 |
| Dell          | Latitude E7440              | [3f4df169bd](https://linux-hardware.org/?probe=3f4df169bd) | Jun 11, 2021 |
| Dell          | Latitude E7440              | [961681623f](https://linux-hardware.org/?probe=961681623f) | Jun 11, 2021 |
| Dell          | Inspiron 1525               | [511a525213](https://linux-hardware.org/?probe=511a525213) | Jun 11, 2021 |
| HP            | ProBook 450 G6              | [e081b13666](https://linux-hardware.org/?probe=e081b13666) | Jun 09, 2021 |
| HP            | ProBook 450 G6              | [e3efe71b23](https://linux-hardware.org/?probe=e3efe71b23) | Jun 09, 2021 |
| HP            | Laptop 15-dw0xxx            | [95fdac8e1c](https://linux-hardware.org/?probe=95fdac8e1c) | Jun 08, 2021 |
| Lenovo        | ThinkPad E590 20NB001AGE    | [21cab94898](https://linux-hardware.org/?probe=21cab94898) | Jun 08, 2021 |
| HP            | EliteBook 820 G1            | [6fbdebda43](https://linux-hardware.org/?probe=6fbdebda43) | Jun 06, 2021 |
| Acer          | Aspire 5750G                | [45b5e8d8ae](https://linux-hardware.org/?probe=45b5e8d8ae) | Jun 06, 2021 |
| Acer          | Aspire 5750G                | [f0574d82e1](https://linux-hardware.org/?probe=f0574d82e1) | Jun 06, 2021 |
| Dell          | Inspiron 5577               | [188fcc64df](https://linux-hardware.org/?probe=188fcc64df) | Jun 06, 2021 |
| Timi          | TM1612                      | [902746e81d](https://linux-hardware.org/?probe=902746e81d) | Jun 06, 2021 |
| Dell          | Latitude C810               | [f379321c88](https://linux-hardware.org/?probe=f379321c88) | Jun 05, 2021 |
| Dell          | Latitude E5470              | [5b65572d25](https://linux-hardware.org/?probe=5b65572d25) | Jun 05, 2021 |
| Timi          | TM1612                      | [14f8479e7c](https://linux-hardware.org/?probe=14f8479e7c) | Jun 05, 2021 |
| Timi          | TM1612                      | [40318f2d95](https://linux-hardware.org/?probe=40318f2d95) | Jun 05, 2021 |
| Dell          | Latitude C810               | [23e6f5572a](https://linux-hardware.org/?probe=23e6f5572a) | Jun 04, 2021 |
| Toshiba       | TECRA M4                    | [3ac511cc5f](https://linux-hardware.org/?probe=3ac511cc5f) | Jun 03, 2021 |
| Dell          | Inspiron 3501               | [3e23b17d66](https://linux-hardware.org/?probe=3e23b17d66) | Jun 01, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [1505924642](https://linux-hardware.org/?probe=1505924642) | Jun 01, 2021 |
| Lenovo        | ThinkPad T430s 2356GBG      | [e67f4b0fd4](https://linux-hardware.org/?probe=e67f4b0fd4) | May 31, 2021 |
| HP            | EliteBook 830 G7 Noteboo... | [b7ec4606a3](https://linux-hardware.org/?probe=b7ec4606a3) | May 31, 2021 |
| HP            | 250 G7 Notebook PC          | [035b3cdc60](https://linux-hardware.org/?probe=035b3cdc60) | May 31, 2021 |
| HP            | 250 G7 Notebook PC          | [e9148788a7](https://linux-hardware.org/?probe=e9148788a7) | May 30, 2021 |
| Fujitsu       | LIFEBOOK BH531              | [93d4456b05](https://linux-hardware.org/?probe=93d4456b05) | May 29, 2021 |
| HP            | 250 G7 Notebook PC          | [0dbfbd4c06](https://linux-hardware.org/?probe=0dbfbd4c06) | May 27, 2021 |
| ASUSTek       | X450LN                      | [9157df68c1](https://linux-hardware.org/?probe=9157df68c1) | May 27, 2021 |
| HP            | Laptop 15s-fq2xxx           | [72287f1bb4](https://linux-hardware.org/?probe=72287f1bb4) | May 25, 2021 |
| HP            | Laptop 15s-fq2xxx           | [f4713dbdb0](https://linux-hardware.org/?probe=f4713dbdb0) | May 25, 2021 |
| ASUSTek       | X450LN                      | [aa8e32e484](https://linux-hardware.org/?probe=aa8e32e484) | May 25, 2021 |
| ASUSTek       | K52F                        | [92db46133f](https://linux-hardware.org/?probe=92db46133f) | May 24, 2021 |
| ASUSTek       | X553SA                      | [c470382d2a](https://linux-hardware.org/?probe=c470382d2a) | May 24, 2021 |
| ASUSTek       | X553SA                      | [31d6a914fd](https://linux-hardware.org/?probe=31d6a914fd) | May 24, 2021 |
| Acer          | Aspire 5750G                | [b420f25ed4](https://linux-hardware.org/?probe=b420f25ed4) | May 23, 2021 |
| Apple         | MacBook5,2                  | [cc0fa80e46](https://linux-hardware.org/?probe=cc0fa80e46) | May 21, 2021 |
| Dell          | Inspiron 7460               | [b766b75906](https://linux-hardware.org/?probe=b766b75906) | May 21, 2021 |
| Toshiba       | Satellite C660              | [60eb674c8f](https://linux-hardware.org/?probe=60eb674c8f) | May 19, 2021 |
| HP            | ProBook 6460b               | [06bc21db81](https://linux-hardware.org/?probe=06bc21db81) | May 18, 2021 |
| LG Electro... | A410-K.BE43P1               | [48978860b6](https://linux-hardware.org/?probe=48978860b6) | May 15, 2021 |
| Acer          | Swift SF114-33              | [e2d8f58e1e](https://linux-hardware.org/?probe=e2d8f58e1e) | May 11, 2021 |
| HP            | ProBook 6460b               | [f91f877043](https://linux-hardware.org/?probe=f91f877043) | May 11, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [2196430972](https://linux-hardware.org/?probe=2196430972) | May 09, 2021 |
| HP            | ProBook 6460b               | [0322df5146](https://linux-hardware.org/?probe=0322df5146) | May 09, 2021 |
| HP            | OMEN by HP Laptop 15-dc1... | [5a99a3a590](https://linux-hardware.org/?probe=5a99a3a590) | May 08, 2021 |
| Acer          | Swift SF114-33              | [a6ed80ed47](https://linux-hardware.org/?probe=a6ed80ed47) | May 08, 2021 |
| Lenovo        | G50-80 80E5                 | [d4b9ffef0a](https://linux-hardware.org/?probe=d4b9ffef0a) | May 06, 2021 |
| Lenovo        | G570 4334                   | [f16304ca03](https://linux-hardware.org/?probe=f16304ca03) | May 04, 2021 |
| Lenovo        | G570 4334                   | [8eca6b6f79](https://linux-hardware.org/?probe=8eca6b6f79) | May 04, 2021 |
| ASUSTek       | N56VM                       | [b08edb12bf](https://linux-hardware.org/?probe=b08edb12bf) | May 04, 2021 |
| ASUSTek       | N56VM                       | [c387fd3d02](https://linux-hardware.org/?probe=c387fd3d02) | May 04, 2021 |
| HP            | Laptop 15-bs0xx             | [57540cdfa4](https://linux-hardware.org/?probe=57540cdfa4) | May 03, 2021 |
| HP            | 2133                        | [e81cac058d](https://linux-hardware.org/?probe=e81cac058d) | May 03, 2021 |
| HP            | ProBook 6460b               | [5b705fff57](https://linux-hardware.org/?probe=5b705fff57) | May 02, 2021 |
| Lenovo        | G570 4334                   | [cf33577cbd](https://linux-hardware.org/?probe=cf33577cbd) | May 02, 2021 |
| Lenovo        | G570 4334                   | [bef0f33897](https://linux-hardware.org/?probe=bef0f33897) | May 02, 2021 |
| LG Electro... | 15ND530-GX30K               | [9d700ce0b6](https://linux-hardware.org/?probe=9d700ce0b6) | Apr 30, 2021 |
| HP            | EliteBook Folio 1040 G1     | [81557b6c6c](https://linux-hardware.org/?probe=81557b6c6c) | Apr 29, 2021 |
| Dell          | Latitude E5270              | [7344ffb994](https://linux-hardware.org/?probe=7344ffb994) | Apr 29, 2021 |
| HP            | 2133                        | [fd8d7a6a94](https://linux-hardware.org/?probe=fd8d7a6a94) | Apr 29, 2021 |
| Toshiba       | Satellite C50-A-K9K         | [f31812125b](https://linux-hardware.org/?probe=f31812125b) | Apr 28, 2021 |
| Dell          | Precision M4400             | [f7616a8e34](https://linux-hardware.org/?probe=f7616a8e34) | Apr 28, 2021 |
| Dell          | Latitude 2120               | [5bfebbf71d](https://linux-hardware.org/?probe=5bfebbf71d) | Apr 28, 2021 |
| Dell          | Latitude D830               | [ddc172ef71](https://linux-hardware.org/?probe=ddc172ef71) | Apr 28, 2021 |
| Toshiba       | Satellite L505D             | [db2deee6fc](https://linux-hardware.org/?probe=db2deee6fc) | Apr 28, 2021 |
| Dell          | Precision M4600             | [f11bc44848](https://linux-hardware.org/?probe=f11bc44848) | Apr 28, 2021 |
| Toshiba       | Satellite Click W35Dt-A     | [7f18f2f6e4](https://linux-hardware.org/?probe=7f18f2f6e4) | Apr 28, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | [004380d8f4](https://linux-hardware.org/?probe=004380d8f4) | Apr 27, 2021 |
| Acer          | Aspire A515-51G             | [bbd69fd1b9](https://linux-hardware.org/?probe=bbd69fd1b9) | Apr 27, 2021 |
| Dell          | Latitude E6420              | [7dbd1d34b7](https://linux-hardware.org/?probe=7dbd1d34b7) | Apr 27, 2021 |
| HP            | ProBook 6460b               | [ee71283e78](https://linux-hardware.org/?probe=ee71283e78) | Apr 27, 2021 |
| TQ-Group      | TQMxE39S                    | [f70e13fdba](https://linux-hardware.org/?probe=f70e13fdba) | Apr 26, 2021 |
| ASUSTek       | ROG Strix G531GV_G531GV     | [4dfa28cef5](https://linux-hardware.org/?probe=4dfa28cef5) | Apr 25, 2021 |
| HP            | ENVY TS 15                  | [7ee12f0f12](https://linux-hardware.org/?probe=7ee12f0f12) | Apr 24, 2021 |
| HP            | ENVY TS 15                  | [1e93ee4ada](https://linux-hardware.org/?probe=1e93ee4ada) | Apr 23, 2021 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [eb3e5cf436](https://linux-hardware.org/?probe=eb3e5cf436) | Apr 22, 2021 |
| TQ-Group      | TQMxE39S                    | [0d550b5fcf](https://linux-hardware.org/?probe=0d550b5fcf) | Apr 21, 2021 |
| HP            | Compaq CQ58                 | [cf2de362ba](https://linux-hardware.org/?probe=cf2de362ba) | Apr 20, 2021 |
| ASUSTek       | N501VW                      | [3a70b17a13](https://linux-hardware.org/?probe=3a70b17a13) | Apr 19, 2021 |
| ASUSTek       | N501VW                      | [58b2490001](https://linux-hardware.org/?probe=58b2490001) | Apr 19, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | [f8a3bc6b1d](https://linux-hardware.org/?probe=f8a3bc6b1d) | Apr 19, 2021 |
| Fujitsu       | LIFEBOOK BH531              | [2fa4c2d1ef](https://linux-hardware.org/?probe=2fa4c2d1ef) | Apr 18, 2021 |
| Apple         | MacBook4,1                  | [c81b5705ce](https://linux-hardware.org/?probe=c81b5705ce) | Apr 17, 2021 |
| Sony          | VPCM120AL                   | [e15b3dcfa3](https://linux-hardware.org/?probe=e15b3dcfa3) | Apr 16, 2021 |
| Fujitsu       | LIFEBOOK S761               | [0115b1d779](https://linux-hardware.org/?probe=0115b1d779) | Apr 16, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [66de8410b3](https://linux-hardware.org/?probe=66de8410b3) | Apr 16, 2021 |
| Acer          | Aspire F5-573               | [82de91c65b](https://linux-hardware.org/?probe=82de91c65b) | Apr 15, 2021 |
| HP            | Stream Notebook PC 13       | [0bf3f6f761](https://linux-hardware.org/?probe=0bf3f6f761) | Apr 15, 2021 |
| Google        | Chell                       | [a570a864bb](https://linux-hardware.org/?probe=a570a864bb) | Apr 14, 2021 |
| Google        | Chell                       | [ef62c9f5d3](https://linux-hardware.org/?probe=ef62c9f5d3) | Apr 14, 2021 |
| Lenovo        | ThinkPad T450s 20BWS2KM0... | [127928c404](https://linux-hardware.org/?probe=127928c404) | Apr 13, 2021 |
| Dell          | Inspiron 5566               | [3f063b636f](https://linux-hardware.org/?probe=3f063b636f) | Apr 13, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [80eb7bbfd6](https://linux-hardware.org/?probe=80eb7bbfd6) | Apr 12, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [a6f88dd316](https://linux-hardware.org/?probe=a6f88dd316) | Apr 11, 2021 |
| Acer          | Aspire V3-771               | [e6c39f5551](https://linux-hardware.org/?probe=e6c39f5551) | Apr 11, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | [c9da6a52cb](https://linux-hardware.org/?probe=c9da6a52cb) | Apr 11, 2021 |
| Dell          | Latitude E7440              | [f5329e62a2](https://linux-hardware.org/?probe=f5329e62a2) | Apr 10, 2021 |
| Sony          | VGN-FW31ZJ                  | [b1bc398f58](https://linux-hardware.org/?probe=b1bc398f58) | Apr 10, 2021 |
| Sony          | VGN-FW31ZJ                  | [67c8da18d0](https://linux-hardware.org/?probe=67c8da18d0) | Apr 10, 2021 |
| Acer          | Nitro AN515-42              | [4c7acbbbc1](https://linux-hardware.org/?probe=4c7acbbbc1) | Apr 10, 2021 |
| Acer          | Aspire V5-571G              | [bc54b9763a](https://linux-hardware.org/?probe=bc54b9763a) | Apr 08, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [adb7fbfc0d](https://linux-hardware.org/?probe=adb7fbfc0d) | Apr 08, 2021 |
| Toshiba       | Satellite M505D             | [2711ae5eca](https://linux-hardware.org/?probe=2711ae5eca) | Apr 07, 2021 |
| HP            | ENVY Notebook               | [83a0078309](https://linux-hardware.org/?probe=83a0078309) | Apr 06, 2021 |
| Lenovo        | ThinkPad T460 20FMS0X022    | [02ce254082](https://linux-hardware.org/?probe=02ce254082) | Apr 06, 2021 |
| Sony          | VGN-FW31ZJ                  | [fdf9b819fb](https://linux-hardware.org/?probe=fdf9b819fb) | Apr 05, 2021 |
| Sony          | VGN-FW31ZJ                  | [9de66e685f](https://linux-hardware.org/?probe=9de66e685f) | Apr 05, 2021 |
| Apple         | MacBook4,1                  | [298dadfff9](https://linux-hardware.org/?probe=298dadfff9) | Apr 05, 2021 |
| HP            | EliteBook 2170p             | [c45b758d6c](https://linux-hardware.org/?probe=c45b758d6c) | Apr 04, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | [8e270876a9](https://linux-hardware.org/?probe=8e270876a9) | Apr 03, 2021 |
| Apple         | MacBook4,1                  | [6edccc53b3](https://linux-hardware.org/?probe=6edccc53b3) | Apr 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [11a0cd56e5](https://linux-hardware.org/?probe=11a0cd56e5) | Apr 02, 2021 |
| ASUSTek       | U32U                        | [2842f61fc9](https://linux-hardware.org/?probe=2842f61fc9) | Apr 02, 2021 |
| Lenovo        | ThinkPad L390 20NRCTO1WW    | [09ae9c9787](https://linux-hardware.org/?probe=09ae9c9787) | Mar 31, 2021 |
| Apple         | MacBook4,1                  | [f430c60495](https://linux-hardware.org/?probe=f430c60495) | Mar 31, 2021 |
| Apple         | MacBook4,1                  | [74bbc27867](https://linux-hardware.org/?probe=74bbc27867) | Mar 31, 2021 |
| Acer          | Aspire A315-53              | [4e040e7a0e](https://linux-hardware.org/?probe=4e040e7a0e) | Mar 30, 2021 |
| Medion        | Akoya P7818                 | [137cba154e](https://linux-hardware.org/?probe=137cba154e) | Mar 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [3c1d98dce9](https://linux-hardware.org/?probe=3c1d98dce9) | Mar 29, 2021 |
| Dell          | Latitude 3400               | [e1cab5dc75](https://linux-hardware.org/?probe=e1cab5dc75) | Mar 29, 2021 |
| ASUSTek       | X550VX                      | [8ca6d8ba59](https://linux-hardware.org/?probe=8ca6d8ba59) | Mar 28, 2021 |
| Notebook      | NJ5x_NJ7xLU                 | [4d0b64cd52](https://linux-hardware.org/?probe=4d0b64cd52) | Mar 27, 2021 |
| Acer          | AOD255                      | [8b63787da8](https://linux-hardware.org/?probe=8b63787da8) | Mar 27, 2021 |
| Acer          | AOD255                      | [0bf011c9bf](https://linux-hardware.org/?probe=0bf011c9bf) | Mar 27, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [6dccadd611](https://linux-hardware.org/?probe=6dccadd611) | Mar 26, 2021 |
| Positivo      | Sinatra                     | [6bc774a94f](https://linux-hardware.org/?probe=6bc774a94f) | Mar 25, 2021 |
| Positivo      | Sinatra                     | [a9045ef086](https://linux-hardware.org/?probe=a9045ef086) | Mar 25, 2021 |
| HP            | ProBook 4520s               | [d94784890e](https://linux-hardware.org/?probe=d94784890e) | Mar 22, 2021 |
| HP            | EliteBook 8460p             | [991778f7f8](https://linux-hardware.org/?probe=991778f7f8) | Mar 22, 2021 |
| Unknown       | MS-N034                     | [cdae6abd0c](https://linux-hardware.org/?probe=cdae6abd0c) | Mar 21, 2021 |
| Sony          | VPCEH2F1E                   | [bebb08c44b](https://linux-hardware.org/?probe=bebb08c44b) | Mar 21, 2021 |
| Acer          | Aspire 5750G                | [82fb28dfec](https://linux-hardware.org/?probe=82fb28dfec) | Mar 19, 2021 |
| HP            | Pavilion g6                 | [997f939dc8](https://linux-hardware.org/?probe=997f939dc8) | Mar 18, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [b379414d3c](https://linux-hardware.org/?probe=b379414d3c) | Mar 18, 2021 |
| Dell          | Inspiron 5770               | [5ff61b6654](https://linux-hardware.org/?probe=5ff61b6654) | Mar 18, 2021 |
| DNS           | DNSNB                       | [52e82c78c3](https://linux-hardware.org/?probe=52e82c78c3) | Mar 18, 2021 |
| Lenovo        | G580 20150                  | [5732d94a88](https://linux-hardware.org/?probe=5732d94a88) | Mar 17, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [1f6ee03f00](https://linux-hardware.org/?probe=1f6ee03f00) | Mar 17, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [abfe8f3adb](https://linux-hardware.org/?probe=abfe8f3adb) | Mar 17, 2021 |
| Toshiba       | PORTEGE Z930                | [c0444e41ce](https://linux-hardware.org/?probe=c0444e41ce) | Mar 17, 2021 |
| Dell          | Inspiron 5558               | [437ce713e9](https://linux-hardware.org/?probe=437ce713e9) | Mar 16, 2021 |
| Dell          | Inspiron 5558               | [5af2be25f4](https://linux-hardware.org/?probe=5af2be25f4) | Mar 16, 2021 |
| Acer          | Extensa 5635                | [5bf0144cd3](https://linux-hardware.org/?probe=5bf0144cd3) | Mar 15, 2021 |
| Lenovo        | ThinkPad 11e 20DAS0PS00     | [85555153ea](https://linux-hardware.org/?probe=85555153ea) | Mar 15, 2021 |
| Fujitsu       | FMVA05007                   | [707f6a3ea5](https://linux-hardware.org/?probe=707f6a3ea5) | Mar 14, 2021 |
| Lenovo        | ThinkPad X201 3249CTO       | [5461951b34](https://linux-hardware.org/?probe=5461951b34) | Mar 14, 2021 |
| HP            | EliteBook 820 G1            | [0cfc5a07d2](https://linux-hardware.org/?probe=0cfc5a07d2) | Mar 09, 2021 |
| Lenovo        | ThinkPad T400 2768BM2       | [b9aea0e95e](https://linux-hardware.org/?probe=b9aea0e95e) | Mar 08, 2021 |
| Lenovo        | ThinkPad T400 2768BM2       | [906ea1b277](https://linux-hardware.org/?probe=906ea1b277) | Mar 08, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | [09ff2814ff](https://linux-hardware.org/?probe=09ff2814ff) | Mar 08, 2021 |
| Medion        | P861X                       | [f163e14733](https://linux-hardware.org/?probe=f163e14733) | Mar 07, 2021 |
| Dell          | Vostro 5481                 | [f914e0d1b3](https://linux-hardware.org/?probe=f914e0d1b3) | Mar 07, 2021 |
| HP            | Notebook                    | [a12fa51807](https://linux-hardware.org/?probe=a12fa51807) | Mar 05, 2021 |
| HP            | ProBook 430 G6              | [5ed6cc994b](https://linux-hardware.org/?probe=5ed6cc994b) | Mar 05, 2021 |
| Dell          | Inspiron 1525               | [92c198acb8](https://linux-hardware.org/?probe=92c198acb8) | Mar 05, 2021 |
| Sony          | VPCEG15FB                   | [c23aee4449](https://linux-hardware.org/?probe=c23aee4449) | Mar 05, 2021 |
| Packard Be... | EasyNote TE11HC             | [53a440907b](https://linux-hardware.org/?probe=53a440907b) | Mar 04, 2021 |
| Medion        | P861X                       | [6b6562c621](https://linux-hardware.org/?probe=6b6562c621) | Mar 04, 2021 |
| Medion        | P861X                       | [4aa0d8855b](https://linux-hardware.org/?probe=4aa0d8855b) | Mar 04, 2021 |
| HP            | ProBook 450 G5              | [ea8530ffe4](https://linux-hardware.org/?probe=ea8530ffe4) | Mar 03, 2021 |
| MSI           | P65 Creator 9SD             | [8cabd1eaa2](https://linux-hardware.org/?probe=8cabd1eaa2) | Mar 03, 2021 |
| MSI           | P65 Creator 9SD             | [217f63acba](https://linux-hardware.org/?probe=217f63acba) | Mar 03, 2021 |
| Sony          | VPCEG15FB                   | [6d895891b9](https://linux-hardware.org/?probe=6d895891b9) | Mar 01, 2021 |
| Sony          | VPCEG15FB                   | [45318e0495](https://linux-hardware.org/?probe=45318e0495) | Feb 28, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [d589c2b2c9](https://linux-hardware.org/?probe=d589c2b2c9) | Feb 27, 2021 |
| Dell          | Latitude E7250              | [3900450df8](https://linux-hardware.org/?probe=3900450df8) | Feb 27, 2021 |
| Medion        | P861X                       | [b2b7b32fe1](https://linux-hardware.org/?probe=b2b7b32fe1) | Feb 26, 2021 |
| Medion        | P861X                       | [ef45a1774d](https://linux-hardware.org/?probe=ef45a1774d) | Feb 26, 2021 |
| HP            | ProBook 4540s               | [9ab78f21ad](https://linux-hardware.org/?probe=9ab78f21ad) | Feb 26, 2021 |
| HP            | ProBook 4540s               | [dd4d88de48](https://linux-hardware.org/?probe=dd4d88de48) | Feb 26, 2021 |
| HP            | ProBook 450 G5              | [cf1f5f9e74](https://linux-hardware.org/?probe=cf1f5f9e74) | Feb 25, 2021 |
| Samsung       | 450R4E/450R5E/450R4V/450... | [15dbf9fad6](https://linux-hardware.org/?probe=15dbf9fad6) | Feb 23, 2021 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [9924631e4c](https://linux-hardware.org/?probe=9924631e4c) | Feb 23, 2021 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [fb1f894d4f](https://linux-hardware.org/?probe=fb1f894d4f) | Feb 22, 2021 |
| ASUSTek       | X502CA                      | [6d275cd9c1](https://linux-hardware.org/?probe=6d275cd9c1) | Feb 22, 2021 |
| Toshiba       | PORTEGE Z30-A               | [a882768f72](https://linux-hardware.org/?probe=a882768f72) | Feb 21, 2021 |
| Sony          | VGN-NW270F                  | [87b755412e](https://linux-hardware.org/?probe=87b755412e) | Feb 19, 2021 |
| Sony          | VGN-NW270F                  | [8d0bcb0740](https://linux-hardware.org/?probe=8d0bcb0740) | Feb 19, 2021 |
| ASUSTek       | X550CA                      | [6989572274](https://linux-hardware.org/?probe=6989572274) | Feb 18, 2021 |
| Dell          | Precision 7530              | [0abb5fcc9e](https://linux-hardware.org/?probe=0abb5fcc9e) | Feb 18, 2021 |
| AWOW          | AK41                        | [4b7c8d520f](https://linux-hardware.org/?probe=4b7c8d520f) | Feb 18, 2021 |
| ASUSTek       | M3N                         | [473966e549](https://linux-hardware.org/?probe=473966e549) | Feb 17, 2021 |
| ASUSTek       | M3N                         | [aa9d5e9820](https://linux-hardware.org/?probe=aa9d5e9820) | Feb 17, 2021 |
| Dell          | Latitude 3400               | [38dbd98cd4](https://linux-hardware.org/?probe=38dbd98cd4) | Feb 15, 2021 |
| Dell          | Inspiron 1545               | [d753427b09](https://linux-hardware.org/?probe=d753427b09) | Feb 15, 2021 |
| Dell          | Latitude 7410               | [ff54e08073](https://linux-hardware.org/?probe=ff54e08073) | Feb 15, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3UX0... | [f21b611e4c](https://linux-hardware.org/?probe=f21b611e4c) | Feb 14, 2021 |
| Samsung       | R540/R580/R780/SA41/E452    | [2fbfd3fb39](https://linux-hardware.org/?probe=2fbfd3fb39) | Feb 13, 2021 |
| ASUSTek       | X540LJ                      | [a175c9e1fa](https://linux-hardware.org/?probe=a175c9e1fa) | Feb 12, 2021 |
| Compaq        | Presario CQ-31              | [1f32780fe6](https://linux-hardware.org/?probe=1f32780fe6) | Feb 10, 2021 |
| ASUSTek       | X502CA                      | [d180e4c8a5](https://linux-hardware.org/?probe=d180e4c8a5) | Feb 10, 2021 |
| Unknown       | Unknown                     | [ab37cb3ea9](https://linux-hardware.org/?probe=ab37cb3ea9) | Feb 10, 2021 |
| Apple         | MacBookAir4,2               | [1f79c0af85](https://linux-hardware.org/?probe=1f79c0af85) | Feb 09, 2021 |
| NEC Comput... | PC-VY12FBHEW                | [e507fdbcf5](https://linux-hardware.org/?probe=e507fdbcf5) | Feb 08, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [f58cfe253f](https://linux-hardware.org/?probe=f58cfe253f) | Feb 07, 2021 |
| HP            | ProBook 6460b               | [1591c890ac](https://linux-hardware.org/?probe=1591c890ac) | Feb 07, 2021 |
| Lenovo        | ThinkPad W510 4389W1B       | [ec27151293](https://linux-hardware.org/?probe=ec27151293) | Feb 06, 2021 |
| Lenovo        | ThinkPad W540 20BG0011US    | [8c37963ac0](https://linux-hardware.org/?probe=8c37963ac0) | Feb 06, 2021 |
| Acer          | AO722                       | [24cb20b715](https://linux-hardware.org/?probe=24cb20b715) | Feb 04, 2021 |
| Lenovo        | ThinkPad L470 20J4003WGE    | [6738439de9](https://linux-hardware.org/?probe=6738439de9) | Feb 04, 2021 |
| Acer          | Swift SF313-52G             | [2967386924](https://linux-hardware.org/?probe=2967386924) | Feb 03, 2021 |
| HP            | EliteBook 8560p             | [758cca4c76](https://linux-hardware.org/?probe=758cca4c76) | Feb 03, 2021 |
| TQ-Group      | TQMxE39S                    | [29e62e5a47](https://linux-hardware.org/?probe=29e62e5a47) | Feb 02, 2021 |
| Lenovo        | ThinkPad P72 20MBCTO1WW     | [b877012ac5](https://linux-hardware.org/?probe=b877012ac5) | Feb 02, 2021 |
| Lenovo        | ThinkPad P72 20MBCTO1WW     | [a147d69ec6](https://linux-hardware.org/?probe=a147d69ec6) | Feb 02, 2021 |
| Unknown       | Unknown                     | [01a4eafbb6](https://linux-hardware.org/?probe=01a4eafbb6) | Feb 02, 2021 |
| Unknown       | Unknown                     | [9cc5c245d0](https://linux-hardware.org/?probe=9cc5c245d0) | Feb 02, 2021 |
| TQ-Group      | TQMxE39S                    | [3ba32b937a](https://linux-hardware.org/?probe=3ba32b937a) | Feb 01, 2021 |
| Dell          | Inspiron 3476               | [29d2ce51a0](https://linux-hardware.org/?probe=29d2ce51a0) | Feb 01, 2021 |
| Dell          | Inspiron 3476               | [6571492610](https://linux-hardware.org/?probe=6571492610) | Jan 31, 2021 |
| Lenovo        | ThinkPad P72 20MBCTO1WW     | [acb14f3921](https://linux-hardware.org/?probe=acb14f3921) | Jan 31, 2021 |
| HP            | ZBook 15 G2                 | [cebba8a2a8](https://linux-hardware.org/?probe=cebba8a2a8) | Jan 30, 2021 |
| Toshiba       | PORTEGE Z30-E               | [34fed11e38](https://linux-hardware.org/?probe=34fed11e38) | Jan 29, 2021 |
| Lenovo        | ThinkPad T430 2349W2P       | [58c2f66dd6](https://linux-hardware.org/?probe=58c2f66dd6) | Jan 26, 2021 |
| Samsung       | 530XBB                      | [d26d07411e](https://linux-hardware.org/?probe=d26d07411e) | Jan 26, 2021 |
| Samsung       | 530XBB                      | [cfe518bb71](https://linux-hardware.org/?probe=cfe518bb71) | Jan 26, 2021 |
| Dell          | Inspiron 5759               | [9e0d8f1e09](https://linux-hardware.org/?probe=9e0d8f1e09) | Jan 25, 2021 |
| HP            | Pavilion Sleekbook 15 PC    | [ea06fcd265](https://linux-hardware.org/?probe=ea06fcd265) | Jan 23, 2021 |
| HP            | Pavilion Sleekbook 15 PC    | [8730d258c7](https://linux-hardware.org/?probe=8730d258c7) | Jan 23, 2021 |
| Dell          | Latitude 5590               | [14a9a52de5](https://linux-hardware.org/?probe=14a9a52de5) | Jan 23, 2021 |
| Dell          | XPS L321X                   | [3473b7b95b](https://linux-hardware.org/?probe=3473b7b95b) | Jan 23, 2021 |
| Dell          | Latitude 5500               | [4334424504](https://linux-hardware.org/?probe=4334424504) | Jan 22, 2021 |
| HP            | 14                          | [7c1ff6f4a8](https://linux-hardware.org/?probe=7c1ff6f4a8) | Jan 22, 2021 |
| Dell          | Inspiron 5759               | [6e8ab4a0a6](https://linux-hardware.org/?probe=6e8ab4a0a6) | Jan 22, 2021 |
| Dell          | Inspiron 5759               | [2e5d1a8ae1](https://linux-hardware.org/?probe=2e5d1a8ae1) | Jan 22, 2021 |
| ASUSTek       | ROG Strix G731GT_G731GT     | [fa99318483](https://linux-hardware.org/?probe=fa99318483) | Jan 21, 2021 |
| Fujitsu       | LIFEBOOK T936               | [50c2127f6c](https://linux-hardware.org/?probe=50c2127f6c) | Jan 20, 2021 |
| Dell          | Latitude E7250              | [d42f7cb3fa](https://linux-hardware.org/?probe=d42f7cb3fa) | Jan 20, 2021 |
| Lenovo        | ThinkPad E590 20NB0012RT    | [784b99a6ce](https://linux-hardware.org/?probe=784b99a6ce) | Jan 20, 2021 |
| HP            | ProBook 4430s               | [3257de56a2](https://linux-hardware.org/?probe=3257de56a2) | Jan 19, 2021 |
| HP            | 2000                        | [2519b222b7](https://linux-hardware.org/?probe=2519b222b7) | Jan 19, 2021 |
| Acer          | Nitro AN515-42              | [2e43134d4d](https://linux-hardware.org/?probe=2e43134d4d) | Jan 18, 2021 |
| HP            | ProBook 4430s               | [7d8c32fade](https://linux-hardware.org/?probe=7d8c32fade) | Jan 18, 2021 |
| HP            | ProBook 4430s               | [42a80e4278](https://linux-hardware.org/?probe=42a80e4278) | Jan 18, 2021 |
| HP            | ProBook 4430s               | [d04aa71783](https://linux-hardware.org/?probe=d04aa71783) | Jan 18, 2021 |
| Dell          | Inspiron 5758               | [4f86ee832f](https://linux-hardware.org/?probe=4f86ee832f) | Jan 17, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [c5676ad337](https://linux-hardware.org/?probe=c5676ad337) | Jan 17, 2021 |
| HP            | Pavilion g4                 | [daf6ec798d](https://linux-hardware.org/?probe=daf6ec798d) | Jan 16, 2021 |
| Acer          | Aspire E1-571G              | [051b3d5b1b](https://linux-hardware.org/?probe=051b3d5b1b) | Jan 16, 2021 |
| Dell          | Vostro 5581                 | [b706435c71](https://linux-hardware.org/?probe=b706435c71) | Jan 15, 2021 |
| HP            | Pavilion g4                 | [e25bba2671](https://linux-hardware.org/?probe=e25bba2671) | Jan 15, 2021 |
| Dell          | XPS 13 9370                 | [c473e50c22](https://linux-hardware.org/?probe=c473e50c22) | Jan 15, 2021 |
| HP            | Pavilion g4                 | [8a3ec7530f](https://linux-hardware.org/?probe=8a3ec7530f) | Jan 15, 2021 |
| Acer          | AOD260                      | [2e870327a5](https://linux-hardware.org/?probe=2e870327a5) | Jan 14, 2021 |
| OEM           | I42IL1                      | [5bcf596d04](https://linux-hardware.org/?probe=5bcf596d04) | Jan 13, 2021 |
| OEM           | I42IL1                      | [eec557e8a3](https://linux-hardware.org/?probe=eec557e8a3) | Jan 13, 2021 |
| Acer          | Aspire 5733                 | [f8a533c52e](https://linux-hardware.org/?probe=f8a533c52e) | Jan 13, 2021 |
| Acer          | Aspire 5500                 | [0c32c44824](https://linux-hardware.org/?probe=0c32c44824) | Jan 13, 2021 |
| Lenovo        | Y50-70 20378                | [bd8a498830](https://linux-hardware.org/?probe=bd8a498830) | Jan 13, 2021 |
| HP            | Pavilion g4                 | [ca2648fcd9](https://linux-hardware.org/?probe=ca2648fcd9) | Jan 13, 2021 |
| HP            | EliteBook 840 G4            | [2e35accad4](https://linux-hardware.org/?probe=2e35accad4) | Jan 12, 2021 |
| Hampoo        | C3W6_AP108_4GB Reserved     | [d033697e79](https://linux-hardware.org/?probe=d033697e79) | Jan 12, 2021 |
| Hampoo        | C3W6_AP108_4GB Reserved     | [6173e9c6e9](https://linux-hardware.org/?probe=6173e9c6e9) | Jan 12, 2021 |
| HP            | Compaq Presario CQ40        | [e2f6812ec3](https://linux-hardware.org/?probe=e2f6812ec3) | Jan 12, 2021 |
| ASUSTek       | 1005HA                      | [fad7f0bc8b](https://linux-hardware.org/?probe=fad7f0bc8b) | Jan 11, 2021 |
| Lenovo        | IdeaPad 5-14ARE05 81YH      | [49eb50f6ed](https://linux-hardware.org/?probe=49eb50f6ed) | Jan 10, 2021 |
| Dell          | Latitude E7250              | [be98a2e801](https://linux-hardware.org/?probe=be98a2e801) | Jan 10, 2021 |
| Dell          | Inspiron 5759               | [e3f73f49d7](https://linux-hardware.org/?probe=e3f73f49d7) | Jan 09, 2021 |
| Dell          | Inspiron MM061              | [3e50fa5e32](https://linux-hardware.org/?probe=3e50fa5e32) | Jan 09, 2021 |
| HP            | ProBook 450 G5              | [64d6bacec9](https://linux-hardware.org/?probe=64d6bacec9) | Jan 08, 2021 |
| Dell          | Inspiron 5759               | [0aa13edd6e](https://linux-hardware.org/?probe=0aa13edd6e) | Jan 08, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | [ffeb181a7f](https://linux-hardware.org/?probe=ffeb181a7f) | Jan 08, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | [5b2eb10b23](https://linux-hardware.org/?probe=5b2eb10b23) | Jan 08, 2021 |
| Dell          | Inspiron 15-3567            | [b04793329d](https://linux-hardware.org/?probe=b04793329d) | Jan 08, 2021 |
| Unknown       | Unknown                     | [87022fc325](https://linux-hardware.org/?probe=87022fc325) | Jan 08, 2021 |
| HP            | ProBook 450 G5              | [71ed7c7a79](https://linux-hardware.org/?probe=71ed7c7a79) | Jan 07, 2021 |
| HP            | ProBook 450 G5              | [1d06bfe495](https://linux-hardware.org/?probe=1d06bfe495) | Jan 07, 2021 |
| Dell          | Inspiron 15-3567            | [c7858d53bd](https://linux-hardware.org/?probe=c7858d53bd) | Jan 07, 2021 |
| Dell          | XPS 13 9310                 | [30421146e3](https://linux-hardware.org/?probe=30421146e3) | Jan 06, 2021 |
| ASUSTek       | K72Dr                       | [a19348d5c3](https://linux-hardware.org/?probe=a19348d5c3) | Jan 06, 2021 |
| Dell          | Vostro 5568                 | [0aafa8d5ad](https://linux-hardware.org/?probe=0aafa8d5ad) | Jan 04, 2021 |
| Dell          | Latitude E7250              | [dd8a0c1b99](https://linux-hardware.org/?probe=dd8a0c1b99) | Jan 04, 2021 |
| Dell          | Vostro 5568                 | [24a223a939](https://linux-hardware.org/?probe=24a223a939) | Jan 04, 2021 |
| Lenovo        | G470 4328                   | [1e6d2c2fa7](https://linux-hardware.org/?probe=1e6d2c2fa7) | Jan 03, 2021 |
| Lenovo        | ThinkPad X220 4291G26       | [dd6162be7e](https://linux-hardware.org/?probe=dd6162be7e) | Jan 03, 2021 |
| Lenovo        | ThinkPad X220 4291G26       | [d4a21bf0b4](https://linux-hardware.org/?probe=d4a21bf0b4) | Jan 03, 2021 |
| HP            | Laptop 15-bs0xx             | [96280026fb](https://linux-hardware.org/?probe=96280026fb) | Jan 03, 2021 |
| MSI           | GE60 2PL                    | [b8ce59aa6d](https://linux-hardware.org/?probe=b8ce59aa6d) | Jan 02, 2021 |
| Lenovo        | ThinkPad T400 6475WJE       | [3a031a442a](https://linux-hardware.org/?probe=3a031a442a) | Dec 30, 2020 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | [70d4988c38](https://linux-hardware.org/?probe=70d4988c38) | Dec 30, 2020 |
| HP            | 15 Notebook PC              | [1516d5001c](https://linux-hardware.org/?probe=1516d5001c) | Dec 30, 2020 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [84d1c38593](https://linux-hardware.org/?probe=84d1c38593) | Dec 29, 2020 |
| Lenovo        | ThinkPad T510 4384GEG       | [c474fe92ae](https://linux-hardware.org/?probe=c474fe92ae) | Dec 28, 2020 |
| Lenovo        | ThinkPad T450s 20BWS0130... | [0d147e3e19](https://linux-hardware.org/?probe=0d147e3e19) | Dec 28, 2020 |
| Acer          | Aspire E5-575G              | [0ecf1d8c7a](https://linux-hardware.org/?probe=0ecf1d8c7a) | Dec 27, 2020 |
| Lenovo        | ThinkPad T510 4384GEG       | [8131aa0117](https://linux-hardware.org/?probe=8131aa0117) | Dec 27, 2020 |
| Lenovo        | G470 4328                   | [e146dc2fa6](https://linux-hardware.org/?probe=e146dc2fa6) | Dec 27, 2020 |
| Lenovo        | G470 4328                   | [a590a273ae](https://linux-hardware.org/?probe=a590a273ae) | Dec 27, 2020 |
| HP            | EliteBook 2530p             | [a86252d9a4](https://linux-hardware.org/?probe=a86252d9a4) | Dec 26, 2020 |
| Toshiba       | QOSMIO X500                 | [721a4df615](https://linux-hardware.org/?probe=721a4df615) | Dec 25, 2020 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | [1d66647923](https://linux-hardware.org/?probe=1d66647923) | Dec 25, 2020 |
| Toshiba       | QOSMIO X500                 | [97da5221b4](https://linux-hardware.org/?probe=97da5221b4) | Dec 25, 2020 |
| Lenovo        | ThinkPad T460 20FMS08Q1B    | [97f9380c82](https://linux-hardware.org/?probe=97f9380c82) | Dec 24, 2020 |
| Samsung       | 700T1C                      | [0f8a8671f2](https://linux-hardware.org/?probe=0f8a8671f2) | Dec 24, 2020 |
| Acer          | Aspire E1-522               | [f6e709b997](https://linux-hardware.org/?probe=f6e709b997) | Dec 24, 2020 |
| HP            | Laptop 15-bs0xx             | [ec5fac5f1d](https://linux-hardware.org/?probe=ec5fac5f1d) | Dec 24, 2020 |
| Razer         | Blade Stealth               | [95a291be2f](https://linux-hardware.org/?probe=95a291be2f) | Dec 24, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [41f994ec7a](https://linux-hardware.org/?probe=41f994ec7a) | Dec 23, 2020 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [f6164f5e30](https://linux-hardware.org/?probe=f6164f5e30) | Dec 23, 2020 |
| HP            | 15                          | [fb0dc2a746](https://linux-hardware.org/?probe=fb0dc2a746) | Dec 22, 2020 |
| Unknown       | Unknown                     | [fede086cb3](https://linux-hardware.org/?probe=fede086cb3) | Dec 21, 2020 |
| HP            | EliteBook 2530p             | [1b75d84b36](https://linux-hardware.org/?probe=1b75d84b36) | Dec 21, 2020 |
| Unknown       | Unknown                     | [c595a3f1df](https://linux-hardware.org/?probe=c595a3f1df) | Dec 20, 2020 |
| Lenovo        | ThinkPad T490s 20NX001PM... | [af7d2d4eb5](https://linux-hardware.org/?probe=af7d2d4eb5) | Dec 20, 2020 |
| Dell          | Vostro 3500                 | [087f314510](https://linux-hardware.org/?probe=087f314510) | Dec 20, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7877a13441](https://linux-hardware.org/?probe=7877a13441) | Dec 20, 2020 |
| LG Electro... | 17Z990-R.AAS8U1             | [2041c116d0](https://linux-hardware.org/?probe=2041c116d0) | Dec 19, 2020 |
| ASUSTek       | U47A                        | [aedbc963d2](https://linux-hardware.org/?probe=aedbc963d2) | Dec 19, 2020 |
| Lenovo        | IdeaPad Y560                | [c5c8b0a320](https://linux-hardware.org/?probe=c5c8b0a320) | Dec 19, 2020 |
| Lenovo        | G50-80 80E5                 | [8cbf5e0e76](https://linux-hardware.org/?probe=8cbf5e0e76) | Dec 19, 2020 |
| Lenovo        | IdeaPad Y560                | [1a68fc4e19](https://linux-hardware.org/?probe=1a68fc4e19) | Dec 19, 2020 |
| Dell          | Latitude 5410               | [b53a7b8fb2](https://linux-hardware.org/?probe=b53a7b8fb2) | Dec 18, 2020 |
| ASUSTek       | ZenBook Pro Duo UX581LV_... | [d33dee579a](https://linux-hardware.org/?probe=d33dee579a) | Dec 18, 2020 |
| Dell          | Latitude 5410               | [916db21f7f](https://linux-hardware.org/?probe=916db21f7f) | Dec 18, 2020 |
| Lenovo        | Y50-70 20378                | [5774f5c238](https://linux-hardware.org/?probe=5774f5c238) | Dec 16, 2020 |
| Toshiba       | TECRA R840                  | [731c5ca5c0](https://linux-hardware.org/?probe=731c5ca5c0) | Dec 16, 2020 |
| HKC           | N14DC                       | [9d7b0e9f25](https://linux-hardware.org/?probe=9d7b0e9f25) | Dec 16, 2020 |
| HKC           | N14DC                       | [13773e90fb](https://linux-hardware.org/?probe=13773e90fb) | Dec 16, 2020 |
| HASEE Comp... | PF4WN2F                     | [9855617493](https://linux-hardware.org/?probe=9855617493) | Dec 15, 2020 |
| Lenovo        | ThinkPad T460s 20FAS3KA0... | [df948532a2](https://linux-hardware.org/?probe=df948532a2) | Dec 14, 2020 |
| Lenovo        | G50-80 80E5                 | [6c2a460153](https://linux-hardware.org/?probe=6c2a460153) | Dec 13, 2020 |
| Lenovo        | ThinkPad T500 20828YG       | [d89c8f909d](https://linux-hardware.org/?probe=d89c8f909d) | Dec 12, 2020 |
| Lenovo        | ThinkPad E590 20NB0012RT    | [372fdf9c03](https://linux-hardware.org/?probe=372fdf9c03) | Dec 12, 2020 |
| HP            | Laptop 17-by0xxx            | [0d9769c8f9](https://linux-hardware.org/?probe=0d9769c8f9) | Dec 11, 2020 |
| HP            | Laptop 17-by0xxx            | [7ebb00e08b](https://linux-hardware.org/?probe=7ebb00e08b) | Dec 10, 2020 |
| Acer          | Aspire SW5-011              | [612ef7c91d](https://linux-hardware.org/?probe=612ef7c91d) | Dec 09, 2020 |
| Acer          | Aspire E5-575G              | [7c88c8eb8e](https://linux-hardware.org/?probe=7c88c8eb8e) | Dec 09, 2020 |
| Dell          | Inspiron 5468               | [abc26c7422](https://linux-hardware.org/?probe=abc26c7422) | Dec 09, 2020 |
| Acer          | Aspire E1-571G              | [561c205338](https://linux-hardware.org/?probe=561c205338) | Dec 08, 2020 |
| ASUSTek       | U36SD                       | [6c4da274f4](https://linux-hardware.org/?probe=6c4da274f4) | Dec 08, 2020 |
| ASUSTek       | U36SD                       | [8044a5aefc](https://linux-hardware.org/?probe=8044a5aefc) | Dec 08, 2020 |
| TUXEDO        | BC1510 1710                 | [62db77e43b](https://linux-hardware.org/?probe=62db77e43b) | Dec 08, 2020 |
| Lenovo        | ThinkPad T490 20N2000FIX    | [ddb7050747](https://linux-hardware.org/?probe=ddb7050747) | Dec 08, 2020 |
| Dell          | Latitude 3450               | [a3b5d0a699](https://linux-hardware.org/?probe=a3b5d0a699) | Dec 07, 2020 |
| ASUSTek       | X550CA                      | [b9335cdc7d](https://linux-hardware.org/?probe=b9335cdc7d) | Dec 06, 2020 |
| HP            | ProBook 4330s               | [22a64b85be](https://linux-hardware.org/?probe=22a64b85be) | Dec 06, 2020 |
| ASUSTek       | X555UJ                      | [188414bc01](https://linux-hardware.org/?probe=188414bc01) | Dec 05, 2020 |
| Acer          | Nitro AN515-51              | [018f6ee8e7](https://linux-hardware.org/?probe=018f6ee8e7) | Dec 04, 2020 |
| Dell          | Latitude E7470              | [a508e0ea38](https://linux-hardware.org/?probe=a508e0ea38) | Dec 04, 2020 |
| Dell          | Latitude E7470              | [22f9cd851d](https://linux-hardware.org/?probe=22f9cd851d) | Dec 04, 2020 |
| Lenovo        | IdeaPad Z400 20201          | [9f4318e1fa](https://linux-hardware.org/?probe=9f4318e1fa) | Dec 03, 2020 |
| Lenovo        | K2450 20243                 | [33409ba105](https://linux-hardware.org/?probe=33409ba105) | Dec 03, 2020 |
| HP            | ProBook 4330s               | [d7d25ffae4](https://linux-hardware.org/?probe=d7d25ffae4) | Dec 03, 2020 |
| ASUSTek       | X540LJ                      | [b3a5455685](https://linux-hardware.org/?probe=b3a5455685) | Dec 02, 2020 |
| Lenovo        | K2450 20243                 | [5c14a1c448](https://linux-hardware.org/?probe=5c14a1c448) | Dec 02, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [483fc6afa3](https://linux-hardware.org/?probe=483fc6afa3) | Dec 02, 2020 |
| HP            | 2000                        | [27fed77b24](https://linux-hardware.org/?probe=27fed77b24) | Dec 02, 2020 |
| HP            | Laptop 15-ra0xx             | [b4b9f9d397](https://linux-hardware.org/?probe=b4b9f9d397) | Dec 02, 2020 |
| HP            | Laptop 15-ra0xx             | [4a0f3ebf74](https://linux-hardware.org/?probe=4a0f3ebf74) | Dec 02, 2020 |
| Acer          | Aspire SW5-014              | [c5a45fdd73](https://linux-hardware.org/?probe=c5a45fdd73) | Dec 01, 2020 |
| HP            | Compaq nc4400 (EY605EA)     | [24cb6d0d7d](https://linux-hardware.org/?probe=24cb6d0d7d) | Nov 30, 2020 |
| Acer          | Predator G5-793             | [ae170a3127](https://linux-hardware.org/?probe=ae170a3127) | Nov 30, 2020 |
| HP            | Pavilion Notebook           | [52711fb75c](https://linux-hardware.org/?probe=52711fb75c) | Nov 29, 2020 |
| Lenovo        | ThinkPad T420 4236S3C       | [7a61b58c47](https://linux-hardware.org/?probe=7a61b58c47) | Nov 29, 2020 |
| HP            | Pavilion Notebook           | [4b3484d5dc](https://linux-hardware.org/?probe=4b3484d5dc) | Nov 29, 2020 |
| Dell          | Vostro 5490                 | [24dae188aa](https://linux-hardware.org/?probe=24dae188aa) | Nov 29, 2020 |
| ASUSTek       | S551LN                      | [0ecda2cfde](https://linux-hardware.org/?probe=0ecda2cfde) | Nov 28, 2020 |
| Dell          | Precision M6800             | [44d8478dde](https://linux-hardware.org/?probe=44d8478dde) | Nov 28, 2020 |
| Dell          | Inspiron 5575               | [269f2e1ac1](https://linux-hardware.org/?probe=269f2e1ac1) | Nov 27, 2020 |
| Lenovo        | ThinkPad T470 20HE0055IT    | [8b24f7ba55](https://linux-hardware.org/?probe=8b24f7ba55) | Nov 27, 2020 |
| ASUSTek       | P751JA                      | [4ab430fbe8](https://linux-hardware.org/?probe=4ab430fbe8) | Nov 27, 2020 |
| ASUSTek       | P751JA                      | [0ed58c84dc](https://linux-hardware.org/?probe=0ed58c84dc) | Nov 27, 2020 |
| Dell          | XPS 13 9360                 | [3f73c1ef56](https://linux-hardware.org/?probe=3f73c1ef56) | Nov 27, 2020 |
| Lenovo        | ThinkPad T420 4180AG3       | [9755a34429](https://linux-hardware.org/?probe=9755a34429) | Nov 27, 2020 |
| Acer          | AO722                       | [c94a10cc9f](https://linux-hardware.org/?probe=c94a10cc9f) | Nov 26, 2020 |
| Acer          | AO722                       | [2cd94435a2](https://linux-hardware.org/?probe=2cd94435a2) | Nov 26, 2020 |
| Lenovo        | ThinkPad T420 4180AG3       | [8661dfb757](https://linux-hardware.org/?probe=8661dfb757) | Nov 26, 2020 |
| HP            | ENVY 14 SPECTRE             | [d2fdd9e4a1](https://linux-hardware.org/?probe=d2fdd9e4a1) | Nov 25, 2020 |
| Acer          | Aspire SW5-011              | [1a272e1a91](https://linux-hardware.org/?probe=1a272e1a91) | Nov 24, 2020 |
| Lenovo        | ThinkPad T500 20828YG       | [814797bb7b](https://linux-hardware.org/?probe=814797bb7b) | Nov 24, 2020 |
| Lenovo        | ThinkPad T500 20828YG       | [a45fc859a5](https://linux-hardware.org/?probe=a45fc859a5) | Nov 24, 2020 |
| Dell          | Studio 1737                 | [d2d9b5de2c](https://linux-hardware.org/?probe=d2d9b5de2c) | Nov 24, 2020 |
| ASUSTek       | S551LN                      | [c059520c33](https://linux-hardware.org/?probe=c059520c33) | Nov 23, 2020 |
| Dell          | Studio 1737                 | [047b815e96](https://linux-hardware.org/?probe=047b815e96) | Nov 23, 2020 |
| Dell          | Studio 1737                 | [c5e6461593](https://linux-hardware.org/?probe=c5e6461593) | Nov 23, 2020 |
| Lenovo        | IdeaPad Y470 0855           | [76c42f7133](https://linux-hardware.org/?probe=76c42f7133) | Nov 22, 2020 |
| Lenovo        | ThinkPad X240 20AM0012UK    | [36ef2f5173](https://linux-hardware.org/?probe=36ef2f5173) | Nov 22, 2020 |
| Dell          | Inspiron 1750               | [612608a41f](https://linux-hardware.org/?probe=612608a41f) | Nov 21, 2020 |
| Dell          | Latitude E7450              | [d1a21c867e](https://linux-hardware.org/?probe=d1a21c867e) | Nov 20, 2020 |
| HP            | ProBook 440 G6              | [3bf08d722f](https://linux-hardware.org/?probe=3bf08d722f) | Nov 20, 2020 |
| HP            | ProBook 440 G6              | [ce48688759](https://linux-hardware.org/?probe=ce48688759) | Nov 20, 2020 |
| Lenovo        | ThinkPad E590 20NB0012RT    | [2589050e7f](https://linux-hardware.org/?probe=2589050e7f) | Nov 20, 2020 |
| Acer          | TMP453-MG                   | [78f12b69b1](https://linux-hardware.org/?probe=78f12b69b1) | Nov 20, 2020 |
| Lenovo        | ThinkPad T430 2349V4B       | [989a5dd973](https://linux-hardware.org/?probe=989a5dd973) | Nov 20, 2020 |
| Lenovo        | ThinkPad E590 20NB0012RT    | [3f0b7e56fd](https://linux-hardware.org/?probe=3f0b7e56fd) | Nov 19, 2020 |
| Acer          | Aspire E5-573G              | [4349229de0](https://linux-hardware.org/?probe=4349229de0) | Nov 19, 2020 |
| MSI           | GS43VR 7RE                  | [8747674074](https://linux-hardware.org/?probe=8747674074) | Nov 19, 2020 |
| Lenovo        | ThinkPad X240 20AM0012UK    | [cdde05e888](https://linux-hardware.org/?probe=cdde05e888) | Nov 19, 2020 |
| AMI           | Intel                       | [9c441fe3fe](https://linux-hardware.org/?probe=9c441fe3fe) | Nov 19, 2020 |
| ASUSTek       | X405UA                      | [e27b62e8d8](https://linux-hardware.org/?probe=e27b62e8d8) | Nov 19, 2020 |
| HP            | Laptop 15-bs0xx             | [1119089279](https://linux-hardware.org/?probe=1119089279) | Nov 19, 2020 |
| Lenovo        | K2450 20243                 | [4d44042257](https://linux-hardware.org/?probe=4d44042257) | Nov 19, 2020 |
| HP            | ENVY 17                     | [bf909911a4](https://linux-hardware.org/?probe=bf909911a4) | Nov 18, 2020 |
| HP            | Spectre 13 Ultrabook        | [a86f00c084](https://linux-hardware.org/?probe=a86f00c084) | Nov 18, 2020 |
| Dell          | Inspiron 5458               | [b3dfa8268c](https://linux-hardware.org/?probe=b3dfa8268c) | Nov 17, 2020 |
| Lenovo        | ThinkPad E14 20RAS0D800     | [917538201a](https://linux-hardware.org/?probe=917538201a) | Nov 16, 2020 |
| Acer          | TMP453-MG                   | [2199a23729](https://linux-hardware.org/?probe=2199a23729) | Nov 16, 2020 |
| Lenovo        | ThinkPad T420 4236S3C       | [19f2fc978a](https://linux-hardware.org/?probe=19f2fc978a) | Nov 15, 2020 |
| HP            | Pavilion dv5                | [5f998846eb](https://linux-hardware.org/?probe=5f998846eb) | Nov 15, 2020 |
| Acer          | Aspire V5-132               | [166921ade6](https://linux-hardware.org/?probe=166921ade6) | Nov 13, 2020 |
| HP            | EliteBook 820 G1            | [6f2db7955a](https://linux-hardware.org/?probe=6f2db7955a) | Nov 12, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [b2a9b6016f](https://linux-hardware.org/?probe=b2a9b6016f) | Nov 12, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [bff1d5b08f](https://linux-hardware.org/?probe=bff1d5b08f) | Nov 12, 2020 |
| HP            | Laptop 15s-fq0xxx           | [7c89e8677b](https://linux-hardware.org/?probe=7c89e8677b) | Nov 12, 2020 |
| HP            | Laptop 15s-fq0xxx           | [e996126e7f](https://linux-hardware.org/?probe=e996126e7f) | Nov 12, 2020 |
| Alienware     | M14xR1                      | [b09cb4d7f0](https://linux-hardware.org/?probe=b09cb4d7f0) | Nov 12, 2020 |
| ASUSTek       | X555YI                      | [2092b326b1](https://linux-hardware.org/?probe=2092b326b1) | Nov 11, 2020 |
| Lenovo        | IdeaPad L340-17API 81LY     | [2e00b39df5](https://linux-hardware.org/?probe=2e00b39df5) | Nov 11, 2020 |
| Dell          | Inspiron 5593               | [56bad4dbd3](https://linux-hardware.org/?probe=56bad4dbd3) | Nov 10, 2020 |
| Unknown       | Unknown                     | [f69e448774](https://linux-hardware.org/?probe=f69e448774) | Nov 10, 2020 |
| Toshiba       | Satellite C55-C             | [7e51e0b053](https://linux-hardware.org/?probe=7e51e0b053) | Nov 09, 2020 |
| Acer          | TMP453-MG                   | [7d50c687e4](https://linux-hardware.org/?probe=7d50c687e4) | Nov 08, 2020 |
| HP            | EliteBook Folio 1040 G1     | [fbe8776f75](https://linux-hardware.org/?probe=fbe8776f75) | Nov 08, 2020 |
| HP            | EliteBook Folio 1040 G1     | [d8a6f3824f](https://linux-hardware.org/?probe=d8a6f3824f) | Nov 08, 2020 |
| Apple         | MacBookPro10,1              | [de48058cc4](https://linux-hardware.org/?probe=de48058cc4) | Nov 07, 2020 |
| Dell          | Inspiron 5370               | [a7ffc4fdf0](https://linux-hardware.org/?probe=a7ffc4fdf0) | Nov 07, 2020 |
| Acer          | TMP453-MG                   | [1d55620e4d](https://linux-hardware.org/?probe=1d55620e4d) | Nov 05, 2020 |
| Dell          | Latitude E6530              | [46ebf29e8a](https://linux-hardware.org/?probe=46ebf29e8a) | Nov 03, 2020 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [4b34114e72](https://linux-hardware.org/?probe=4b34114e72) | Nov 03, 2020 |
| DataLogic     | U50SI                       | [d49f5970f4](https://linux-hardware.org/?probe=d49f5970f4) | Nov 02, 2020 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [54079a5e32](https://linux-hardware.org/?probe=54079a5e32) | Nov 02, 2020 |
| Samsung       | 940Z5L                      | [82a5d79b0f](https://linux-hardware.org/?probe=82a5d79b0f) | Nov 01, 2020 |
| Unknown       | Unknown                     | [a98cf1ca14](https://linux-hardware.org/?probe=a98cf1ca14) | Oct 31, 2020 |
| Dell          | Latitude E6530              | [620044198e](https://linux-hardware.org/?probe=620044198e) | Oct 31, 2020 |
| Packard Be... | EasyNote TE11HC             | [ed0818d3b2](https://linux-hardware.org/?probe=ed0818d3b2) | Oct 30, 2020 |
| Dell          | Inspiron 7520               | [a91074b57a](https://linux-hardware.org/?probe=a91074b57a) | Oct 29, 2020 |
| Lenovo        | E31-80 80MX                 | [d56dacea36](https://linux-hardware.org/?probe=d56dacea36) | Oct 29, 2020 |
| Unknown       | LapBook Pro                 | [1c33f10570](https://linux-hardware.org/?probe=1c33f10570) | Oct 28, 2020 |
| Positivo B... | VJFE42F11X-XXXXXX           | [6febf84141](https://linux-hardware.org/?probe=6febf84141) | Oct 28, 2020 |
| Dell          | Inspiron N5110              | [a74340225d](https://linux-hardware.org/?probe=a74340225d) | Oct 27, 2020 |
| HP            | ProBook 450 G7              | [d0857726ae](https://linux-hardware.org/?probe=d0857726ae) | Oct 27, 2020 |
| Sony          | SVE14122CXW                 | [c399c9b6e1](https://linux-hardware.org/?probe=c399c9b6e1) | Oct 27, 2020 |
| Acer          | Aspire 5250                 | [6cf22de87a](https://linux-hardware.org/?probe=6cf22de87a) | Oct 26, 2020 |
| Samsung       | 300V3Z/300V4Z/300V5Z/200... | [e9ff5b55dc](https://linux-hardware.org/?probe=e9ff5b55dc) | Oct 25, 2020 |
| Lenovo        | IdeaPad S340-14API 81NB     | [ac21cb55bf](https://linux-hardware.org/?probe=ac21cb55bf) | Oct 23, 2020 |
| Lenovo        | B50-50 80S2                 | [098d0c417d](https://linux-hardware.org/?probe=098d0c417d) | Oct 23, 2020 |
| Apple         | MacBookAir7,2               | [5b033684f7](https://linux-hardware.org/?probe=5b033684f7) | Oct 22, 2020 |
| Dell          | Latitude E5520              | [2a250b5803](https://linux-hardware.org/?probe=2a250b5803) | Oct 22, 2020 |
| ASUSTek       | X45C                        | [20cb6e4a37](https://linux-hardware.org/?probe=20cb6e4a37) | Oct 22, 2020 |
| Dell          | Latitude 7400               | [fbe3992713](https://linux-hardware.org/?probe=fbe3992713) | Oct 22, 2020 |
| Lenovo        | IdeaPad L340-17API 81LY     | [982e283d23](https://linux-hardware.org/?probe=982e283d23) | Oct 22, 2020 |
| Apple         | MacBookAir7,2               | [9569430cd1](https://linux-hardware.org/?probe=9569430cd1) | Oct 22, 2020 |
| Lenovo        | ThinkPad X13 Gen 1 20T20... | [a45cbea600](https://linux-hardware.org/?probe=a45cbea600) | Oct 21, 2020 |
| HP            | OMEN by HP Laptop           | [6bba0d34d9](https://linux-hardware.org/?probe=6bba0d34d9) | Oct 21, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [8b528f1d9d](https://linux-hardware.org/?probe=8b528f1d9d) | Oct 21, 2020 |
| Dell          | XPS 13 9360                 | [f5425945c2](https://linux-hardware.org/?probe=f5425945c2) | Oct 21, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [71e64e6440](https://linux-hardware.org/?probe=71e64e6440) | Oct 20, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [1ebdcf1f2f](https://linux-hardware.org/?probe=1ebdcf1f2f) | Oct 20, 2020 |
| Apple         | MacBookAir7,2               | [4fcbaab79c](https://linux-hardware.org/?probe=4fcbaab79c) | Oct 20, 2020 |
| HP            | EliteBook 6930p             | [b5fbfcf0a5](https://linux-hardware.org/?probe=b5fbfcf0a5) | Oct 19, 2020 |
| HP            | EliteBook 6930p             | [fe166def1e](https://linux-hardware.org/?probe=fe166def1e) | Oct 19, 2020 |
| Dell          | Inspiron 5570               | [225dbd1e07](https://linux-hardware.org/?probe=225dbd1e07) | Oct 19, 2020 |
| HP            | Mini 210-2000               | [0a83b3e845](https://linux-hardware.org/?probe=0a83b3e845) | Oct 18, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [341bd94c9a](https://linux-hardware.org/?probe=341bd94c9a) | Oct 17, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [816b92a100](https://linux-hardware.org/?probe=816b92a100) | Oct 16, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [06fba260a1](https://linux-hardware.org/?probe=06fba260a1) | Oct 16, 2020 |
| Dell          | Inspiron 5505               | [5dac15d30a](https://linux-hardware.org/?probe=5dac15d30a) | Oct 16, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [83acd207c5](https://linux-hardware.org/?probe=83acd207c5) | Oct 16, 2020 |
| Samsung       | RV409/RV509/RV709           | [81c0bf9823](https://linux-hardware.org/?probe=81c0bf9823) | Oct 15, 2020 |
| Alienware     | 17 R4                       | [2fe13da62c](https://linux-hardware.org/?probe=2fe13da62c) | Oct 15, 2020 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [a0292a1315](https://linux-hardware.org/?probe=a0292a1315) | Oct 15, 2020 |
| HP            | EliteBook 2540p             | [7768f6fe36](https://linux-hardware.org/?probe=7768f6fe36) | Oct 14, 2020 |
| Dell          | Inspiron N5110              | [d95238f805](https://linux-hardware.org/?probe=d95238f805) | Oct 14, 2020 |
| Alienware     | 17 R4                       | [9b2f19cc3c](https://linux-hardware.org/?probe=9b2f19cc3c) | Oct 14, 2020 |
| Samsung       | N248P                       | [74486c5431](https://linux-hardware.org/?probe=74486c5431) | Oct 14, 2020 |
| Lenovo        | ThinkPad T520 4243GE9       | [d4a560f987](https://linux-hardware.org/?probe=d4a560f987) | Oct 14, 2020 |
| HP            | ProBook 640 G1              | [e9b2b31708](https://linux-hardware.org/?probe=e9b2b31708) | Oct 13, 2020 |
| Lenovo        | ThinkPad X220 4291B66       | [0428020229](https://linux-hardware.org/?probe=0428020229) | Oct 11, 2020 |
| ASUSTek       | S551LN                      | [e5096beea3](https://linux-hardware.org/?probe=e5096beea3) | Oct 11, 2020 |
| HP            | Pavilion Notebook           | [6cfa593625](https://linux-hardware.org/?probe=6cfa593625) | Oct 11, 2020 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [9bf6f0ba43](https://linux-hardware.org/?probe=9bf6f0ba43) | Oct 09, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [65ead373b6](https://linux-hardware.org/?probe=65ead373b6) | Oct 07, 2020 |
| Samsung       | RV411/RV511/E3511/S3511/... | [318f21861c](https://linux-hardware.org/?probe=318f21861c) | Oct 06, 2020 |
| Dell          | XPS 13 9350                 | [706d160916](https://linux-hardware.org/?probe=706d160916) | Oct 06, 2020 |
| Dell          | Latitude 7490               | [f4d8a0e5e9](https://linux-hardware.org/?probe=f4d8a0e5e9) | Oct 06, 2020 |
| Dell          | Latitude E5530 non-vPro     | [86aa78e5af](https://linux-hardware.org/?probe=86aa78e5af) | Oct 05, 2020 |
| Dell          | Latitude E5530 non-vPro     | [c535d537e1](https://linux-hardware.org/?probe=c535d537e1) | Oct 05, 2020 |
| Dell          | Inspiron 5547               | [14ee547f91](https://linux-hardware.org/?probe=14ee547f91) | Oct 04, 2020 |
| Sony          | VPCYB3V1E                   | [f116097e48](https://linux-hardware.org/?probe=f116097e48) | Oct 02, 2020 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | [ceb25a15f1](https://linux-hardware.org/?probe=ceb25a15f1) | Oct 02, 2020 |
| Lenovo        | IdeaPad 3 17ARE05 81W5      | [e5c4b71e07](https://linux-hardware.org/?probe=e5c4b71e07) | Oct 01, 2020 |
| PC Special... | N150CU                      | [d6855993c3](https://linux-hardware.org/?probe=d6855993c3) | Oct 01, 2020 |
| PC Special... | N150CU                      | [226b0d2359](https://linux-hardware.org/?probe=226b0d2359) | Oct 01, 2020 |
| Dell          | XPS 13 9350                 | [fbaa514a8e](https://linux-hardware.org/?probe=fbaa514a8e) | Sep 29, 2020 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [d5cec6d5ee](https://linux-hardware.org/?probe=d5cec6d5ee) | Sep 29, 2020 |
| Lenovo        | ThinkPad X60s 1703Y1F       | [556ce7876f](https://linux-hardware.org/?probe=556ce7876f) | Sep 28, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [c4d11b04b5](https://linux-hardware.org/?probe=c4d11b04b5) | Sep 28, 2020 |
| ASUSTek       | N551JW                      | [bbe5800595](https://linux-hardware.org/?probe=bbe5800595) | Sep 27, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [eb4f96855e](https://linux-hardware.org/?probe=eb4f96855e) | Sep 27, 2020 |
| HP            | Stream Notebook PC 13       | [de7c2cac49](https://linux-hardware.org/?probe=de7c2cac49) | Sep 26, 2020 |
| HP            | Stream Notebook PC 13       | [780ac6fb5f](https://linux-hardware.org/?probe=780ac6fb5f) | Sep 26, 2020 |
| RM            | RM NOTEBOOK 310             | [eaeb27c7f2](https://linux-hardware.org/?probe=eaeb27c7f2) | Sep 26, 2020 |
| Lenovo        | ThinkPad X250 20CLS3KU00    | [249a4394d3](https://linux-hardware.org/?probe=249a4394d3) | Sep 25, 2020 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [e0efe47cb6](https://linux-hardware.org/?probe=e0efe47cb6) | Sep 25, 2020 |
| HP            | EliteBook 850 G5            | [86422636a2](https://linux-hardware.org/?probe=86422636a2) | Sep 25, 2020 |
| Lenovo        | ThinkPad T440p 20AWS17N0... | [ce767919ed](https://linux-hardware.org/?probe=ce767919ed) | Sep 24, 2020 |
| ASUSTek       | S551LN                      | [422ea2594e](https://linux-hardware.org/?probe=422ea2594e) | Sep 23, 2020 |
| HP            | Compaq 6730b (KE717AV)      | [ed83dc94c7](https://linux-hardware.org/?probe=ed83dc94c7) | Sep 22, 2020 |
| Lenovo        | G570 20079                  | [66c60e019d](https://linux-hardware.org/?probe=66c60e019d) | Sep 20, 2020 |
| Lenovo        | ThinkPad T420 4236PRG       | [642718e912](https://linux-hardware.org/?probe=642718e912) | Sep 20, 2020 |
| HP            | Laptop 15-bs1xx             | [711a85f008](https://linux-hardware.org/?probe=711a85f008) | Sep 19, 2020 |
| Lenovo        | IdeaPad S340-15API 81NC     | [e1ee591923](https://linux-hardware.org/?probe=e1ee591923) | Sep 18, 2020 |
| Lenovo        | IdeaPad S340-15API 81NC     | [e416b806d6](https://linux-hardware.org/?probe=e416b806d6) | Sep 18, 2020 |
| Dell          | Inspiron 5520               | [bfcd20dbac](https://linux-hardware.org/?probe=bfcd20dbac) | Sep 18, 2020 |
| Dell          | Inspiron 5520               | [422e9fa4b7](https://linux-hardware.org/?probe=422e9fa4b7) | Sep 18, 2020 |
| Dell          | Vostro 5490                 | [7eb157ff10](https://linux-hardware.org/?probe=7eb157ff10) | Sep 16, 2020 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [1fa7cd3dc7](https://linux-hardware.org/?probe=1fa7cd3dc7) | Sep 16, 2020 |
| Dell          | Latitude 5400               | [623e6b93ad](https://linux-hardware.org/?probe=623e6b93ad) | Sep 15, 2020 |
| Acer          | Swift SF514-53T             | [faed7578a5](https://linux-hardware.org/?probe=faed7578a5) | Sep 13, 2020 |
| Dell          | Inspiron 15-3552            | [9bdc5d239e](https://linux-hardware.org/?probe=9bdc5d239e) | Sep 13, 2020 |
| HP            | G70                         | [198fd94bda](https://linux-hardware.org/?probe=198fd94bda) | Sep 13, 2020 |
| Dell          | Vostro 3560                 | [f94ad2f27d](https://linux-hardware.org/?probe=f94ad2f27d) | Sep 12, 2020 |
| Dell          | Latitude E5410              | [49fba5e9d5](https://linux-hardware.org/?probe=49fba5e9d5) | Sep 11, 2020 |
| HP            | ProBook 4540s               | [c11c25601e](https://linux-hardware.org/?probe=c11c25601e) | Sep 09, 2020 |
| Acer          | AOA110                      | [25dbe990da](https://linux-hardware.org/?probe=25dbe990da) | Sep 09, 2020 |
| Dell          | Inspiron 7559               | [b7918f8374](https://linux-hardware.org/?probe=b7918f8374) | Sep 09, 2020 |
| Acer          | Aspire E5-575               | [31e588485d](https://linux-hardware.org/?probe=31e588485d) | Sep 09, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [cab06cdbd7](https://linux-hardware.org/?probe=cab06cdbd7) | Sep 07, 2020 |
| Toshiba       | Satellite Pro C650          | [61966b1615](https://linux-hardware.org/?probe=61966b1615) | Sep 07, 2020 |
| Dell          | Latitude E6430              | [ce95e87e90](https://linux-hardware.org/?probe=ce95e87e90) | Sep 06, 2020 |
| HP            | ProBook 455 G2              | [cf202aa137](https://linux-hardware.org/?probe=cf202aa137) | Sep 06, 2020 |
| Apple         | MacBookPro11,3              | [db5ed9c7cc](https://linux-hardware.org/?probe=db5ed9c7cc) | Sep 06, 2020 |
| Apple         | MacBookPro11,3              | [2301ba312c](https://linux-hardware.org/?probe=2301ba312c) | Sep 06, 2020 |
| Acer          | Aspire E5-575G              | [71698fa8ea](https://linux-hardware.org/?probe=71698fa8ea) | Sep 05, 2020 |
| Lenovo        | G50-45 80E3                 | [7ab663d793](https://linux-hardware.org/?probe=7ab663d793) | Sep 05, 2020 |
| Dell          | Latitude E7440              | [0db3907088](https://linux-hardware.org/?probe=0db3907088) | Sep 05, 2020 |
| Dell          | Latitude 3400               | [e1a6c8dd9b](https://linux-hardware.org/?probe=e1a6c8dd9b) | Sep 04, 2020 |
| LG Electro... | 15ND530-GX30K               | [8f8a5ce10c](https://linux-hardware.org/?probe=8f8a5ce10c) | Sep 04, 2020 |
| Acer          | Aspire ES1-523              | [e335200dd8](https://linux-hardware.org/?probe=e335200dd8) | Sep 04, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [a06e93e3e9](https://linux-hardware.org/?probe=a06e93e3e9) | Sep 04, 2020 |
| ASUSTek       | K46CB                       | [480238b24f](https://linux-hardware.org/?probe=480238b24f) | Sep 04, 2020 |
| ASUSTek       | TUF Gaming FX705DY_FX705... | [4ba6b10a45](https://linux-hardware.org/?probe=4ba6b10a45) | Sep 03, 2020 |
| Dell          | Latitude E5410              | [1b695e8489](https://linux-hardware.org/?probe=1b695e8489) | Sep 03, 2020 |
| Dell          | XPS 13 9360                 | [9c3c496bce](https://linux-hardware.org/?probe=9c3c496bce) | Sep 03, 2020 |
| Dell          | XPS 13 9360                 | [db1c5c4a5a](https://linux-hardware.org/?probe=db1c5c4a5a) | Sep 03, 2020 |
| Acer          | Aspire V5-123               | [1f3a3c5de7](https://linux-hardware.org/?probe=1f3a3c5de7) | Sep 03, 2020 |
| Lenovo        | ThinkPad 13 20GJCTO1WW      | [141b121f2b](https://linux-hardware.org/?probe=141b121f2b) | Sep 02, 2020 |
| Dell          | Latitude E6220              | [4dbb344e4e](https://linux-hardware.org/?probe=4dbb344e4e) | Sep 02, 2020 |
| Dell          | Latitude E6220              | [4a7fb29d5b](https://linux-hardware.org/?probe=4a7fb29d5b) | Sep 02, 2020 |
| Notebook      | NJ50_70CU                   | [a724f1dd51](https://linux-hardware.org/?probe=a724f1dd51) | Sep 01, 2020 |
| HP            | Pavilion g4                 | [cf281b97df](https://linux-hardware.org/?probe=cf281b97df) | Aug 31, 2020 |
| Acer          | Swift SF114-33              | [5e853f5521](https://linux-hardware.org/?probe=5e853f5521) | Aug 31, 2020 |
| Toshiba       | Satellite L50-C             | [fe2976451d](https://linux-hardware.org/?probe=fe2976451d) | Aug 31, 2020 |
| HP            | Pavilion g4                 | [4ae31fc59f](https://linux-hardware.org/?probe=4ae31fc59f) | Aug 30, 2020 |
| Acer          | Swift SF114-33              | [57bdfdb823](https://linux-hardware.org/?probe=57bdfdb823) | Aug 28, 2020 |
| HP            | EliteBook 6930p             | [65a2b8d0f8](https://linux-hardware.org/?probe=65a2b8d0f8) | Aug 28, 2020 |
| Purism        | Librem 13 v2                | [23cd34d2f6](https://linux-hardware.org/?probe=23cd34d2f6) | Aug 27, 2020 |
| Acer          | Aspire E5-576G              | [ed12456986](https://linux-hardware.org/?probe=ed12456986) | Aug 27, 2020 |
| Dell          | Inspiron 1501               | [05a7b7bd45](https://linux-hardware.org/?probe=05a7b7bd45) | Aug 26, 2020 |
| Positivo      | MOBILE                      | [e663178667](https://linux-hardware.org/?probe=e663178667) | Aug 26, 2020 |
| HP            | Laptop 15s-fq1xxx           | [f58e055469](https://linux-hardware.org/?probe=f58e055469) | Aug 25, 2020 |
| HP            | Laptop 15s-fq1xxx           | [d19c11c74a](https://linux-hardware.org/?probe=d19c11c74a) | Aug 25, 2020 |
| Acer          | Aspire M5-481T              | [90f4c78581](https://linux-hardware.org/?probe=90f4c78581) | Aug 24, 2020 |
| HP            | 255 G5 Notebook PC          | [ed158ae1be](https://linux-hardware.org/?probe=ed158ae1be) | Aug 24, 2020 |
| HP            | 255 G5 Notebook PC          | [0f68fffc51](https://linux-hardware.org/?probe=0f68fffc51) | Aug 24, 2020 |
| Lenovo        | ThinkPad P72 20MBCTO1WW     | [09fa3f2ed9](https://linux-hardware.org/?probe=09fa3f2ed9) | Aug 23, 2020 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [2febbb27a0](https://linux-hardware.org/?probe=2febbb27a0) | Aug 23, 2020 |
| Lenovo        | ThinkPad X230 23252S4       | [5fe0becd60](https://linux-hardware.org/?probe=5fe0becd60) | Aug 22, 2020 |
| Dell          | Inspiron 5468               | [34784a5c7f](https://linux-hardware.org/?probe=34784a5c7f) | Aug 22, 2020 |
| HP            | Pavilion Laptop 14-bf0xx    | [7ac7953d76](https://linux-hardware.org/?probe=7ac7953d76) | Aug 22, 2020 |
| Positivo      | WCBT1013                    | [444b588762](https://linux-hardware.org/?probe=444b588762) | Aug 21, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [7b4fcb3693](https://linux-hardware.org/?probe=7b4fcb3693) | Aug 21, 2020 |
| Acer          | Aspire 2920                 | [a6e4cf0707](https://linux-hardware.org/?probe=a6e4cf0707) | Aug 20, 2020 |
| HP            | ENVY 17                     | [e7362b7565](https://linux-hardware.org/?probe=e7362b7565) | Aug 19, 2020 |
| HP            | ENVY 17                     | [73738aea3d](https://linux-hardware.org/?probe=73738aea3d) | Aug 19, 2020 |
| Samsung       | RV411/RV511/E3511/S3511/... | [f08d3d413f](https://linux-hardware.org/?probe=f08d3d413f) | Aug 18, 2020 |
| Acer          | Swift SF114-33              | [3f770a739d](https://linux-hardware.org/?probe=3f770a739d) | Aug 18, 2020 |
| Acer          | Swift SF114-33              | [19d3840414](https://linux-hardware.org/?probe=19d3840414) | Aug 17, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [a0a3771b15](https://linux-hardware.org/?probe=a0a3771b15) | Aug 17, 2020 |
| HP            | EliteBook 2570p             | [68b54a8e19](https://linux-hardware.org/?probe=68b54a8e19) | Aug 16, 2020 |
| Alienware     | 17 R4                       | [c1a871b29b](https://linux-hardware.org/?probe=c1a871b29b) | Aug 14, 2020 |
| Acer          | Nitro AN515-54              | [a16386e839](https://linux-hardware.org/?probe=a16386e839) | Aug 14, 2020 |
| Acer          | Aspire A315-21              | [7f105e6362](https://linux-hardware.org/?probe=7f105e6362) | Aug 13, 2020 |
| HP            | Pavilion dm1                | [60fa55c570](https://linux-hardware.org/?probe=60fa55c570) | Aug 12, 2020 |
| HP            | Pavilion dm1                | [dc90ba192e](https://linux-hardware.org/?probe=dc90ba192e) | Aug 12, 2020 |
| Dell          | Vostro 3460                 | [0aae36acb0](https://linux-hardware.org/?probe=0aae36acb0) | Aug 12, 2020 |
| Acer          | Aspire A315-21              | [783c39539a](https://linux-hardware.org/?probe=783c39539a) | Aug 12, 2020 |
| Lenovo        | ThinkPad X280 20KES30A00    | [c471cf1073](https://linux-hardware.org/?probe=c471cf1073) | Aug 12, 2020 |
| ASUSTek       | X102BA                      | [e0a50dc1dc](https://linux-hardware.org/?probe=e0a50dc1dc) | Aug 11, 2020 |
| ASUSTek       | X102BA                      | [54626aa013](https://linux-hardware.org/?probe=54626aa013) | Aug 11, 2020 |
| Dell          | Inspiron 5468               | [2132db1417](https://linux-hardware.org/?probe=2132db1417) | Aug 10, 2020 |
| Samsung       | 305E4A/305E5A/305E7A        | [d4e7055335](https://linux-hardware.org/?probe=d4e7055335) | Aug 09, 2020 |
| Dell          | Vostro 5490                 | [7a1a00cd34](https://linux-hardware.org/?probe=7a1a00cd34) | Aug 09, 2020 |
| Dell          | Vostro 5490                 | [f06297f752](https://linux-hardware.org/?probe=f06297f752) | Aug 09, 2020 |
| Dell          | Latitude 3500               | [09838e5e6d](https://linux-hardware.org/?probe=09838e5e6d) | Aug 08, 2020 |
| Dell          | Latitude 5400               | [a38ed67ed8](https://linux-hardware.org/?probe=a38ed67ed8) | Aug 06, 2020 |
| HP            | Presario CQ57               | [0e5ac44846](https://linux-hardware.org/?probe=0e5ac44846) | Aug 05, 2020 |
| HP            | Notebook                    | [daf982706c](https://linux-hardware.org/?probe=daf982706c) | Aug 02, 2020 |
| HP            | Notebook                    | [1b3e005f48](https://linux-hardware.org/?probe=1b3e005f48) | Aug 02, 2020 |
| Acer          | Swift SF314-51              | [ff4068d40b](https://linux-hardware.org/?probe=ff4068d40b) | Jul 31, 2020 |
| Dell          | Inspiron 5468               | [6921a88aa4](https://linux-hardware.org/?probe=6921a88aa4) | Jul 31, 2020 |
| Dell          | Inspiron 1545               | [0bf0dfa454](https://linux-hardware.org/?probe=0bf0dfa454) | Jul 30, 2020 |
| ASUSTek       | G60JX                       | [a79df141d9](https://linux-hardware.org/?probe=a79df141d9) | Jul 30, 2020 |
| ASUSTek       | N46VM                       | [d5866f9f0f](https://linux-hardware.org/?probe=d5866f9f0f) | Jul 30, 2020 |
| Sony          | VPCEH40EB                   | [34776d5a70](https://linux-hardware.org/?probe=34776d5a70) | Jul 28, 2020 |
| Dell          | XPS L502X                   | [2d4d18566a](https://linux-hardware.org/?probe=2d4d18566a) | Jul 28, 2020 |
| Dell          | XPS L502X                   | [8bb4b95768](https://linux-hardware.org/?probe=8bb4b95768) | Jul 28, 2020 |
| Notebook      | P95_96_97Ex,Rx              | [4a873d937e](https://linux-hardware.org/?probe=4a873d937e) | Jul 28, 2020 |
| Notebook      | P95_96_97Ex,Rx              | [856a372491](https://linux-hardware.org/?probe=856a372491) | Jul 28, 2020 |
| ASUSTek       | N46VM                       | [b9abcbb0ca](https://linux-hardware.org/?probe=b9abcbb0ca) | Jul 27, 2020 |
| ASUSTek       | N46VM                       | [864b3c0808](https://linux-hardware.org/?probe=864b3c0808) | Jul 27, 2020 |
| Samsung       | RV411/RV511/E3511/S3511/... | [3c7f1069f2](https://linux-hardware.org/?probe=3c7f1069f2) | Jul 27, 2020 |
| Positivo      | MOBILE                      | [c1befdddd7](https://linux-hardware.org/?probe=c1befdddd7) | Jul 27, 2020 |
| Positivo      | MOBILE                      | [005647bf65](https://linux-hardware.org/?probe=005647bf65) | Jul 27, 2020 |
| Dell          | Inspiron 1545               | [b3d4ad3d50](https://linux-hardware.org/?probe=b3d4ad3d50) | Jul 26, 2020 |
| HP            | Pavilion dm1                | [db3461a440](https://linux-hardware.org/?probe=db3461a440) | Jul 25, 2020 |
| Dell          | Inspiron 5448               | [2fe1b79c13](https://linux-hardware.org/?probe=2fe1b79c13) | Jul 25, 2020 |
| Dell          | Inspiron 5448               | [288a68e67a](https://linux-hardware.org/?probe=288a68e67a) | Jul 25, 2020 |
| Acer          | Aspire A515-51G             | [9742c8d37b](https://linux-hardware.org/?probe=9742c8d37b) | Jul 25, 2020 |
| ASUSTek       | X550LB                      | [21f4f262c0](https://linux-hardware.org/?probe=21f4f262c0) | Jul 25, 2020 |
| Dell          | Inspiron 5468               | [5c465b448e](https://linux-hardware.org/?probe=5c465b448e) | Jul 24, 2020 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [d123128722](https://linux-hardware.org/?probe=d123128722) | Jul 24, 2020 |
| Acer          | Aspire A515-51              | [11869b0f59](https://linux-hardware.org/?probe=11869b0f59) | Jul 24, 2020 |
| ASUSTek       | X45C                        | [4f6a928ff4](https://linux-hardware.org/?probe=4f6a928ff4) | Jul 24, 2020 |
| Lenovo        | ThinkPad X230 23252EG       | [2617c14fa9](https://linux-hardware.org/?probe=2617c14fa9) | Jul 24, 2020 |
| Dell          | Inspiron 3576               | [1ba8aea989](https://linux-hardware.org/?probe=1ba8aea989) | Jul 24, 2020 |
| Acer          | Aspire E5-571               | [725d9e6ae5](https://linux-hardware.org/?probe=725d9e6ae5) | Jul 24, 2020 |
| Lenovo        | G50-80 80R0                 | [6982206a08](https://linux-hardware.org/?probe=6982206a08) | Jul 24, 2020 |
| Positivo      | POSITIVO MASTER N130i       | [7eba72f41a](https://linux-hardware.org/?probe=7eba72f41a) | Jul 24, 2020 |
| Lenovo        | ThinkPad X230 23252EG       | [16ae7ff56d](https://linux-hardware.org/?probe=16ae7ff56d) | Jul 23, 2020 |
| Toshiba       | Satellite L300              | [c298ec6fd5](https://linux-hardware.org/?probe=c298ec6fd5) | Jul 23, 2020 |
| Toshiba       | PORTEGE Z30-E               | [a388a3c3af](https://linux-hardware.org/?probe=a388a3c3af) | Jul 23, 2020 |
| HP            | EliteBook 840 G3            | [8b28c1e0d0](https://linux-hardware.org/?probe=8b28c1e0d0) | Jul 23, 2020 |
| Dell          | Vostro 3350                 | [9e18467afc](https://linux-hardware.org/?probe=9e18467afc) | Jul 23, 2020 |
| Lenovo        | IdeaPad 3 17ARE05 81W5      | [30350cb1a7](https://linux-hardware.org/?probe=30350cb1a7) | Jul 21, 2020 |
| Toshiba       | Satellite L300              | [1aae41a0a1](https://linux-hardware.org/?probe=1aae41a0a1) | Jul 21, 2020 |
| Dell          | Vostro 5490                 | [6c43634839](https://linux-hardware.org/?probe=6c43634839) | Jul 20, 2020 |
| Dell          | Vostro 5490                 | [c52426ce99](https://linux-hardware.org/?probe=c52426ce99) | Jul 19, 2020 |
| HP            | Pavilion dm1                | [84fc871f29](https://linux-hardware.org/?probe=84fc871f29) | Jul 18, 2020 |
| HP            | Pavilion dm1                | [ccc4a944e8](https://linux-hardware.org/?probe=ccc4a944e8) | Jul 18, 2020 |
| Dell          | Latitude 5501               | [c53b828170](https://linux-hardware.org/?probe=c53b828170) | Jul 17, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [ad524a6470](https://linux-hardware.org/?probe=ad524a6470) | Jul 17, 2020 |
| Dell          | Latitude 5501               | [4b7b954a2a](https://linux-hardware.org/?probe=4b7b954a2a) | Jul 16, 2020 |
| Dell          | Latitude 5501               | [8ed8b8225c](https://linux-hardware.org/?probe=8ed8b8225c) | Jul 16, 2020 |
| ASUSTek       | N56JN                       | [43c91be0b3](https://linux-hardware.org/?probe=43c91be0b3) | Jul 16, 2020 |
| Dell          | Inspiron 7570               | [c9ee97997e](https://linux-hardware.org/?probe=c9ee97997e) | Jul 15, 2020 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | [498a1fee5c](https://linux-hardware.org/?probe=498a1fee5c) | Jul 14, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [f545576ae9](https://linux-hardware.org/?probe=f545576ae9) | Jul 14, 2020 |
| Lenovo        | V340-17IWL 81RG             | [49816db41b](https://linux-hardware.org/?probe=49816db41b) | Jul 13, 2020 |
| HP            | 255 G5 Notebook PC          | [cac2fc0f88](https://linux-hardware.org/?probe=cac2fc0f88) | Jul 13, 2020 |
| HP            | 255 G5 Notebook PC          | [61f3040321](https://linux-hardware.org/?probe=61f3040321) | Jul 13, 2020 |
| Intel         | Intel powered classmate ... | [1ffa275c8b](https://linux-hardware.org/?probe=1ffa275c8b) | Jul 12, 2020 |
| Intel         | Skylake Platform            | [e9db11a33a](https://linux-hardware.org/?probe=e9db11a33a) | Jul 11, 2020 |
| HP            | Mini 110-3100               | [2bb9ccfa16](https://linux-hardware.org/?probe=2bb9ccfa16) | Jul 11, 2020 |
| Intel         | Intel powered classmate ... | [49442bdbca](https://linux-hardware.org/?probe=49442bdbca) | Jul 11, 2020 |
| Dell          | Latitude 3500               | [6f040bffc3](https://linux-hardware.org/?probe=6f040bffc3) | Jul 11, 2020 |
| MSI           | GE62 7RE                    | [40d868800a](https://linux-hardware.org/?probe=40d868800a) | Jul 09, 2020 |
| Dell          | Inspiron 1545               | [9642ef551e](https://linux-hardware.org/?probe=9642ef551e) | Jul 08, 2020 |
| Panasonic     | CF-52PGNBX2M                | [b9dadcb0e0](https://linux-hardware.org/?probe=b9dadcb0e0) | Jul 08, 2020 |
| Panasonic     | CF-52PGNBX2M                | [3b388e6d69](https://linux-hardware.org/?probe=3b388e6d69) | Jul 08, 2020 |
| Dell          | Latitude E5520              | [ab997ac1d8](https://linux-hardware.org/?probe=ab997ac1d8) | Jul 06, 2020 |
| Apple         | MacBookPro11,3              | [c4b1d78638](https://linux-hardware.org/?probe=c4b1d78638) | Jul 06, 2020 |
| Lenovo        | ThinkPad X395 20NL000YCD    | [8ce881d65e](https://linux-hardware.org/?probe=8ce881d65e) | Jul 06, 2020 |
| Acer          | Aspire 7520                 | [d2d6a3d4e6](https://linux-hardware.org/?probe=d2d6a3d4e6) | Jul 06, 2020 |
| PC Special... | N150CU                      | [940e89b2ae](https://linux-hardware.org/?probe=940e89b2ae) | Jul 05, 2020 |
| HP            | 250 G6 Notebook PC          | [4e7c532c73](https://linux-hardware.org/?probe=4e7c532c73) | Jul 04, 2020 |
| HP            | 250 G6 Notebook PC          | [b7b5367edf](https://linux-hardware.org/?probe=b7b5367edf) | Jul 04, 2020 |
| PC Special... | N150CU                      | [6f7e0f4a22](https://linux-hardware.org/?probe=6f7e0f4a22) | Jul 04, 2020 |
| Dell          | Latitude 5490               | [43f9885380](https://linux-hardware.org/?probe=43f9885380) | Jul 04, 2020 |
| Dell          | Latitude 5490               | [71db2718e5](https://linux-hardware.org/?probe=71db2718e5) | Jul 04, 2020 |
| Lenovo        | ThinkPad T400 6474D88       | [8af87c450e](https://linux-hardware.org/?probe=8af87c450e) | Jul 03, 2020 |
| Fujitsu       | LIFEBOOK BH531              | [2484e68205](https://linux-hardware.org/?probe=2484e68205) | Jul 03, 2020 |
| Lenovo        | ThinkPad T450 20BUS3V100    | [b7c6aa8db3](https://linux-hardware.org/?probe=b7c6aa8db3) | Jul 01, 2020 |
| Lenovo        | ThinkPad T450 20BUS3V100    | [f77bec6055](https://linux-hardware.org/?probe=f77bec6055) | Jul 01, 2020 |
| ASUSTek       | G752VS                      | [c65813bd9f](https://linux-hardware.org/?probe=c65813bd9f) | Jul 01, 2020 |
| HP            | Pavilion Laptop 14-bf0xx    | [b303c4d3e2](https://linux-hardware.org/?probe=b303c4d3e2) | Jun 30, 2020 |
| HP            | EliteBook 840 G1            | [75a2e58b47](https://linux-hardware.org/?probe=75a2e58b47) | Jun 30, 2020 |
| Lenovo        | G40-30 80FY                 | [2e7c3657fb](https://linux-hardware.org/?probe=2e7c3657fb) | Jun 30, 2020 |
| Dell          | Inspiron N5050              | [d2e2ff8989](https://linux-hardware.org/?probe=d2e2ff8989) | Jun 29, 2020 |
| Compal        | PBL20                       | [7fe621b0fd](https://linux-hardware.org/?probe=7fe621b0fd) | Jun 29, 2020 |
| Lenovo        | ThinkPad L390 20NR001FRT    | [b9cca93b51](https://linux-hardware.org/?probe=b9cca93b51) | Jun 29, 2020 |
| Acer          | TravelMate P2410-G2-M       | [00677918db](https://linux-hardware.org/?probe=00677918db) | Jun 29, 2020 |
| ASUSTek       | G752VS                      | [9e1c907a01](https://linux-hardware.org/?probe=9e1c907a01) | Jun 28, 2020 |
| Lenovo        | G40-30 80FY                 | [157e79f788](https://linux-hardware.org/?probe=157e79f788) | Jun 28, 2020 |
| Lenovo        | G40-30 80FY                 | [5cfcbbb4a4](https://linux-hardware.org/?probe=5cfcbbb4a4) | Jun 28, 2020 |
| ASUSTek       | X540LA                      | [df995fd6b3](https://linux-hardware.org/?probe=df995fd6b3) | Jun 27, 2020 |
| Corporativ... | LX4SI                       | [3a15f8865d](https://linux-hardware.org/?probe=3a15f8865d) | Jun 26, 2020 |
| Lenovo        | Y50-70 20378                | [f01e0dbd89](https://linux-hardware.org/?probe=f01e0dbd89) | Jun 26, 2020 |
| MSI           | MS-7A37                     | [a2ad72232d](https://linux-hardware.org/?probe=a2ad72232d) | Jun 25, 2020 |
| HP            | ZBook 15                    | [ac608e1d37](https://linux-hardware.org/?probe=ac608e1d37) | Jun 25, 2020 |
| Lenovo        | IdeaPad Z500 20202          | [dc66cb5caf](https://linux-hardware.org/?probe=dc66cb5caf) | Jun 25, 2020 |
| Corporativ... | LX4SI                       | [f9e67e8a5f](https://linux-hardware.org/?probe=f9e67e8a5f) | Jun 25, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | [97f55dc573](https://linux-hardware.org/?probe=97f55dc573) | Jun 24, 2020 |
| Dell          | Inspiron 5481               | [1075dca72a](https://linux-hardware.org/?probe=1075dca72a) | Jun 24, 2020 |
| Lenovo        | ThinkPad T410 2522K4U       | [b9a9a86df6](https://linux-hardware.org/?probe=b9a9a86df6) | Jun 23, 2020 |
| Lenovo        | IdeaPad 3 17ARE05 81W5      | [f48bfbd65a](https://linux-hardware.org/?probe=f48bfbd65a) | Jun 22, 2020 |
| Dell          | Latitude 3500               | [85c2c3879c](https://linux-hardware.org/?probe=85c2c3879c) | Jun 22, 2020 |
| Acer          | AOD255E                     | [1ff694ea71](https://linux-hardware.org/?probe=1ff694ea71) | Jun 20, 2020 |
| Lenovo        | B320-14IKB 81CC             | [1d4b7aa7e6](https://linux-hardware.org/?probe=1d4b7aa7e6) | Jun 19, 2020 |
| Dell          | Vostro 3550                 | [1eff0f87ed](https://linux-hardware.org/?probe=1eff0f87ed) | Jun 19, 2020 |
| Samsung       | 305E4A/305E5A/305E7A        | [9aaf7632b6](https://linux-hardware.org/?probe=9aaf7632b6) | Jun 17, 2020 |
| Samsung       | 305E4A/305E5A/305E7A        | [9a6aa97f03](https://linux-hardware.org/?probe=9a6aa97f03) | Jun 17, 2020 |
| Dell          | Vostro 3550                 | [093e631bfb](https://linux-hardware.org/?probe=093e631bfb) | Jun 17, 2020 |
| Dell          | Vostro 3550                 | [2e79d90fcf](https://linux-hardware.org/?probe=2e79d90fcf) | Jun 17, 2020 |
| Lenovo        | B320-14IKB 81CC             | [52bf2d5f61](https://linux-hardware.org/?probe=52bf2d5f61) | Jun 16, 2020 |
| HP            | G62                         | [ee5b5b6cd3](https://linux-hardware.org/?probe=ee5b5b6cd3) | Jun 15, 2020 |
| Sony          | PCG-GRZ10(I)                | [185fd8341c](https://linux-hardware.org/?probe=185fd8341c) | Jun 14, 2020 |
| Dell          | Latitude E6430              | [97304444b6](https://linux-hardware.org/?probe=97304444b6) | Jun 14, 2020 |
| ASUSTek       | N56JN                       | [3f30010f53](https://linux-hardware.org/?probe=3f30010f53) | Jun 14, 2020 |
| eMachines     | E725                        | [e619c97412](https://linux-hardware.org/?probe=e619c97412) | Jun 13, 2020 |
| HP            | Stream Notebook PC 13       | [9dce53774f](https://linux-hardware.org/?probe=9dce53774f) | Jun 13, 2020 |
| Acer          | Aspire E5-575G              | [80eaa52f0f](https://linux-hardware.org/?probe=80eaa52f0f) | Jun 10, 2020 |
| Dell          | Inspiron 7559               | [1e7f6e42a3](https://linux-hardware.org/?probe=1e7f6e42a3) | Jun 10, 2020 |
| Lenovo        | ThinkPad T410 2537G98       | [50bf756f5e](https://linux-hardware.org/?probe=50bf756f5e) | Jun 10, 2020 |
| Dell          | Latitude 7490               | [6bf81ba8f3](https://linux-hardware.org/?probe=6bf81ba8f3) | Jun 10, 2020 |
| HP            | EliteBook 8470p             | [df84bbbc37](https://linux-hardware.org/?probe=df84bbbc37) | Jun 09, 2020 |
| HP            | Pavilion Laptop 15-ck0xx    | [b9e284df2c](https://linux-hardware.org/?probe=b9e284df2c) | Jun 09, 2020 |
| HP            | Pavilion Laptop 15-ck0xx    | [2b1b019bdd](https://linux-hardware.org/?probe=2b1b019bdd) | Jun 09, 2020 |
| Acer          | Aspire E5-573G              | [c2f8aca460](https://linux-hardware.org/?probe=c2f8aca460) | Jun 06, 2020 |
| HP            | ProBook 4540s               | [b28f2f3b8a](https://linux-hardware.org/?probe=b28f2f3b8a) | Jun 05, 2020 |
| HP            | Presario CQ56               | [4eed3fc6f6](https://linux-hardware.org/?probe=4eed3fc6f6) | Jun 05, 2020 |
| Dell          | Precision M6700             | [0934059263](https://linux-hardware.org/?probe=0934059263) | Jun 04, 2020 |
| Dell          | Latitude E6400              | [5e1e738d70](https://linux-hardware.org/?probe=5e1e738d70) | Jun 04, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [e276372880](https://linux-hardware.org/?probe=e276372880) | Jun 03, 2020 |
| HP            | Presario CQ43               | [30478f743c](https://linux-hardware.org/?probe=30478f743c) | Jun 03, 2020 |
| Lenovo        | IdeaPad U430p 20269         | [1431224dcf](https://linux-hardware.org/?probe=1431224dcf) | Jun 03, 2020 |
| ASUSTek       | K55VD                       | [6976a25d72](https://linux-hardware.org/?probe=6976a25d72) | Jun 01, 2020 |
| Lenovo        | ThinkPad X240 20AMS70D00    | [02e0881f6f](https://linux-hardware.org/?probe=02e0881f6f) | Jun 01, 2020 |
| Lenovo        | IdeaPad U430p 20269         | [bf8b7ed090](https://linux-hardware.org/?probe=bf8b7ed090) | Jun 01, 2020 |
| Lenovo        | Z50-70 20354                | [474b3dc645](https://linux-hardware.org/?probe=474b3dc645) | Jun 01, 2020 |
| HDC High D... | CB14T332                    | [1d7a164cca](https://linux-hardware.org/?probe=1d7a164cca) | May 30, 2020 |
| HP            | EliteBook 1050 G1           | [0c3a677cbd](https://linux-hardware.org/?probe=0c3a677cbd) | May 29, 2020 |
| HP            | EliteBook 1050 G1           | [c0f352e66c](https://linux-hardware.org/?probe=c0f352e66c) | May 29, 2020 |
| Dell          | Inspiron N5050              | [50d2e1431b](https://linux-hardware.org/?probe=50d2e1431b) | May 29, 2020 |
| Dell          | Inspiron N5050              | [a0ad1f624b](https://linux-hardware.org/?probe=a0ad1f624b) | May 29, 2020 |
| HP            | EliteBook 8470p             | [33a171506d](https://linux-hardware.org/?probe=33a171506d) | May 29, 2020 |
| Dell          | Latitude E7240              | [6289a0fd13](https://linux-hardware.org/?probe=6289a0fd13) | May 28, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X420... | [9a867c7a5b](https://linux-hardware.org/?probe=9a867c7a5b) | May 28, 2020 |
| Dell          | Latitude E7450              | [c3eab25bca](https://linux-hardware.org/?probe=c3eab25bca) | May 28, 2020 |
| Lenovo        | ThinkPad X200 74598Y7       | [4552172a72](https://linux-hardware.org/?probe=4552172a72) | May 28, 2020 |
| Acer          | Swift SF315-52              | [e86fd64c2e](https://linux-hardware.org/?probe=e86fd64c2e) | May 28, 2020 |
| Samsung       | N150P/N210P/N220P           | [2a2f1b6680](https://linux-hardware.org/?probe=2a2f1b6680) | May 27, 2020 |
| HP            | Laptop 17-ca0xxx            | [beffbd7414](https://linux-hardware.org/?probe=beffbd7414) | May 27, 2020 |
| HP            | Laptop 17-ca0xxx            | [529c6d5874](https://linux-hardware.org/?probe=529c6d5874) | May 27, 2020 |
| Lenovo        | ThinkPad T400 6475VYS       | [9cb845c34a](https://linux-hardware.org/?probe=9cb845c34a) | May 26, 2020 |
| Samsung       | RF510/RF410/RF710           | [1dbe669cde](https://linux-hardware.org/?probe=1dbe669cde) | May 26, 2020 |
| HP            | Laptop 17-ca0xxx            | [5260e229e1](https://linux-hardware.org/?probe=5260e229e1) | May 26, 2020 |
| HP            | Pavilion g6                 | [7b98176319](https://linux-hardware.org/?probe=7b98176319) | May 25, 2020 |
| Lenovo        | ThinkPad X240 20AMS3AE04    | [9db223bd10](https://linux-hardware.org/?probe=9db223bd10) | May 25, 2020 |
| Lenovo        | ThinkPad X220 4290LE6       | [1cf252b77b](https://linux-hardware.org/?probe=1cf252b77b) | May 25, 2020 |
| Dell          | Precision 3540              | [ea309d9030](https://linux-hardware.org/?probe=ea309d9030) | May 25, 2020 |
| Lenovo        | ThinkPad X230 2306CTO       | [e63080ca59](https://linux-hardware.org/?probe=e63080ca59) | May 25, 2020 |
| ASUSTek       | U47A                        | [37e6fd89f0](https://linux-hardware.org/?probe=37e6fd89f0) | May 25, 2020 |
| Toshiba       | Satellite S55-B             | [35990b670d](https://linux-hardware.org/?probe=35990b670d) | May 25, 2020 |
| Dell          | Inspiron 7559               | [f3bc867078](https://linux-hardware.org/?probe=f3bc867078) | May 24, 2020 |
| Dell          | Latitude E4310              | [584a3a44b6](https://linux-hardware.org/?probe=584a3a44b6) | May 23, 2020 |
| ASUSTek       | UX550VE                     | [f872407ca5](https://linux-hardware.org/?probe=f872407ca5) | May 23, 2020 |
| Apple         | MacBookPro11,3              | [73c797ec11](https://linux-hardware.org/?probe=73c797ec11) | May 22, 2020 |
| Dell          | Inspiron 3458               | [47147cf457](https://linux-hardware.org/?probe=47147cf457) | May 22, 2020 |
| Lenovo        | ThinkPad E470 20H1A029SG    | [6afaed7f7f](https://linux-hardware.org/?probe=6afaed7f7f) | May 21, 2020 |
| Dell          | Precision M6700             | [ee975c603d](https://linux-hardware.org/?probe=ee975c603d) | May 21, 2020 |
| Acer          | Aspire one                  | [7b19bc975f](https://linux-hardware.org/?probe=7b19bc975f) | May 20, 2020 |
| Samsung       | RF510/RF410/RF710           | [71168a0c26](https://linux-hardware.org/?probe=71168a0c26) | May 20, 2020 |
| Dell          | Latitude E6410              | [4e98eb67c5](https://linux-hardware.org/?probe=4e98eb67c5) | May 19, 2020 |
| HP            | Stream Notebook PC 13       | [9179ef8e4a](https://linux-hardware.org/?probe=9179ef8e4a) | May 16, 2020 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [bccec7c3d1](https://linux-hardware.org/?probe=bccec7c3d1) | May 16, 2020 |
| HP            | EliteBook 830 G5            | [5570800f48](https://linux-hardware.org/?probe=5570800f48) | May 16, 2020 |
| Lenovo        | ThinkPad T520 424329U       | [bf1c52908b](https://linux-hardware.org/?probe=bf1c52908b) | May 16, 2020 |
| Lenovo        | V340-17IWL 81RG             | [44587fea11](https://linux-hardware.org/?probe=44587fea11) | May 15, 2020 |
| Lenovo        | IdeaPad U430p 20269         | [813b1e9a84](https://linux-hardware.org/?probe=813b1e9a84) | May 13, 2020 |
| HP            | Stream Notebook PC 13       | [24159d4d0e](https://linux-hardware.org/?probe=24159d4d0e) | May 12, 2020 |
| HP            | Stream Notebook PC 13       | [de358d97e6](https://linux-hardware.org/?probe=de358d97e6) | May 12, 2020 |
| Lenovo        | IdeaPad U430p 20269         | [96f4f783ca](https://linux-hardware.org/?probe=96f4f783ca) | May 12, 2020 |
| Dell          | Latitude E4310              | [b6426acbc9](https://linux-hardware.org/?probe=b6426acbc9) | May 12, 2020 |
| Dell          | Latitude E5500              | [dab666e1a8](https://linux-hardware.org/?probe=dab666e1a8) | May 12, 2020 |
| Lenovo        | ThinkPad E480 20KN003WUS    | [eed9f07004](https://linux-hardware.org/?probe=eed9f07004) | May 09, 2020 |
| Dell          | Inspiron 7559               | [14935c4a3b](https://linux-hardware.org/?probe=14935c4a3b) | May 08, 2020 |
| Dell          | Precision M4600             | [7060267281](https://linux-hardware.org/?probe=7060267281) | May 08, 2020 |
| Dell          | XPS 13 9360                 | [a82e794c17](https://linux-hardware.org/?probe=a82e794c17) | May 08, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [25d620d966](https://linux-hardware.org/?probe=25d620d966) | May 07, 2020 |
| Dell          | XPS 13 9360                 | [e1e8c2ec1d](https://linux-hardware.org/?probe=e1e8c2ec1d) | May 07, 2020 |
| Unknown       | MEDION                      | [5bf3f2a081](https://linux-hardware.org/?probe=5bf3f2a081) | May 07, 2020 |
| Unknown       | MEDION                      | [052c842aeb](https://linux-hardware.org/?probe=052c842aeb) | May 07, 2020 |
| Unknown       | MEDION                      | [b3586664a1](https://linux-hardware.org/?probe=b3586664a1) | May 07, 2020 |
| Dell          | XPS 13 9360                 | [0e83966a88](https://linux-hardware.org/?probe=0e83966a88) | May 07, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [6f82171699](https://linux-hardware.org/?probe=6f82171699) | May 06, 2020 |
| Notebook      | N130BU                      | [a82966c663](https://linux-hardware.org/?probe=a82966c663) | May 05, 2020 |
| Dell          | XPS 13 9360                 | [e7abeaa740](https://linux-hardware.org/?probe=e7abeaa740) | May 05, 2020 |
| Dell          | Precision M6700             | [83ca19b998](https://linux-hardware.org/?probe=83ca19b998) | May 02, 2020 |
| Lenovo        | ThinkPad T420 4180M8P       | [572c07437c](https://linux-hardware.org/?probe=572c07437c) | May 02, 2020 |
| Lenovo        | ThinkPad T420 4180M8P       | [c0c3c80557](https://linux-hardware.org/?probe=c0c3c80557) | May 01, 2020 |
| Lenovo        | ThinkPad T420 4180M8P       | [0a6d1bef79](https://linux-hardware.org/?probe=0a6d1bef79) | May 01, 2020 |
| HP            | EliteBook 830 G5            | [60aac7debe](https://linux-hardware.org/?probe=60aac7debe) | May 01, 2020 |
| Lenovo        | ThinkPad T495s 20QKS01E0... | [00c41547c3](https://linux-hardware.org/?probe=00c41547c3) | May 01, 2020 |
| Lenovo        | ThinkPad T420 4180M8P       | [4c718b0f7f](https://linux-hardware.org/?probe=4c718b0f7f) | May 01, 2020 |
| Lenovo        | ThinkPad T420 4180M8P       | [ec4e03bc46](https://linux-hardware.org/?probe=ec4e03bc46) | May 01, 2020 |
| Lenovo        | ThinkPad T420 4180M8P       | [15b0f60139](https://linux-hardware.org/?probe=15b0f60139) | May 01, 2020 |
| Acer          | Aspire A717-72G             | [c1d0901a2d](https://linux-hardware.org/?probe=c1d0901a2d) | May 01, 2020 |
| Acer          | Aspire A717-72G             | [d99f776939](https://linux-hardware.org/?probe=d99f776939) | May 01, 2020 |
| Dell          | Inspiron 3542               | [341f819d57](https://linux-hardware.org/?probe=341f819d57) | Apr 30, 2020 |
| Dell          | Inspiron 3542               | [f7fbef2f76](https://linux-hardware.org/?probe=f7fbef2f76) | Apr 30, 2020 |
| Dell          | Precision 5520              | [af304cccc5](https://linux-hardware.org/?probe=af304cccc5) | Apr 30, 2020 |
| Dell          | Precision 5520              | [38b67c7277](https://linux-hardware.org/?probe=38b67c7277) | Apr 30, 2020 |
| Lenovo        | IdeaPad U430p 20269         | [00fe28a0d0](https://linux-hardware.org/?probe=00fe28a0d0) | Apr 30, 2020 |
| Lenovo        | IdeaPad U430p 20269         | [57a0592afd](https://linux-hardware.org/?probe=57a0592afd) | Apr 30, 2020 |
| Lenovo        | IdeaPad U430p 20269         | [689865b9bf](https://linux-hardware.org/?probe=689865b9bf) | Apr 30, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [a6ae1c89e0](https://linux-hardware.org/?probe=a6ae1c89e0) | Apr 29, 2020 |
| Google        | Chell                       | [7fd39aaf40](https://linux-hardware.org/?probe=7fd39aaf40) | Apr 28, 2020 |
| Dell          | XPS 13 9360                 | [3a9685af82](https://linux-hardware.org/?probe=3a9685af82) | Apr 28, 2020 |
| Toshiba       | Satellite L515              | [c411228b1a](https://linux-hardware.org/?probe=c411228b1a) | Apr 28, 2020 |
| Samsung       | RF510/RF410/RF710           | [6cb8f7029e](https://linux-hardware.org/?probe=6cb8f7029e) | Apr 28, 2020 |
| Samsung       | RF510/RF410/RF710           | [a59c2a0386](https://linux-hardware.org/?probe=a59c2a0386) | Apr 28, 2020 |
| HP            | EliteBook 840 G1            | [b77a2c1bdc](https://linux-hardware.org/?probe=b77a2c1bdc) | Apr 27, 2020 |
| Unknown       | Unknown                     | [aea41bbbc1](https://linux-hardware.org/?probe=aea41bbbc1) | Apr 27, 2020 |
| Unknown       | Unknown                     | [5b415ad69a](https://linux-hardware.org/?probe=5b415ad69a) | Apr 27, 2020 |
| Unknown       | Unknown                     | [204c6dc56b](https://linux-hardware.org/?probe=204c6dc56b) | Apr 27, 2020 |
| ASUSTek       | M3N                         | [59b41381ed](https://linux-hardware.org/?probe=59b41381ed) | Apr 27, 2020 |
| Samsung       | RF510/RF410/RF710           | [a35a432774](https://linux-hardware.org/?probe=a35a432774) | Apr 27, 2020 |
| Dell          | Precision M6600             | [832a43b8f0](https://linux-hardware.org/?probe=832a43b8f0) | Apr 27, 2020 |
| Dell          | Latitude E6410              | [125cc5d7fd](https://linux-hardware.org/?probe=125cc5d7fd) | Apr 26, 2020 |
| Dell          | Inspiron 7559               | [b2252b3ed9](https://linux-hardware.org/?probe=b2252b3ed9) | Apr 26, 2020 |
| Fujitsu Si... | AMILO Pa 2510               | [2babee9700](https://linux-hardware.org/?probe=2babee9700) | Apr 25, 2020 |
| HP            | 2000                        | [fc08298c38](https://linux-hardware.org/?probe=fc08298c38) | Apr 25, 2020 |
| Lenovo        | ThinkPad W700 2752RZ2       | [4e720bb073](https://linux-hardware.org/?probe=4e720bb073) | Apr 25, 2020 |
| Lenovo        | ThinkPad W700 2752RZ2       | [b146fe7bdc](https://linux-hardware.org/?probe=b146fe7bdc) | Apr 25, 2020 |
| HP            | 2000                        | [2a044beeef](https://linux-hardware.org/?probe=2a044beeef) | Apr 25, 2020 |
| HP            | 2000                        | [1a2556870f](https://linux-hardware.org/?probe=1a2556870f) | Apr 25, 2020 |
| Lenovo        | Z50-75 80EC                 | [b11f0bc564](https://linux-hardware.org/?probe=b11f0bc564) | Apr 24, 2020 |
| Lenovo        | Z50-75 80EC                 | [d0c2315fe8](https://linux-hardware.org/?probe=d0c2315fe8) | Apr 24, 2020 |
| Lenovo        | Z50-75 80EC                 | [51cb74b6fe](https://linux-hardware.org/?probe=51cb74b6fe) | Apr 24, 2020 |
| ASUSTek       | M3N                         | [884b817668](https://linux-hardware.org/?probe=884b817668) | Apr 24, 2020 |
| Dell          | Inspiron 7559               | [1ddf2238b0](https://linux-hardware.org/?probe=1ddf2238b0) | Apr 24, 2020 |
| HP            | ProBook 645 G1              | [72e7302ac3](https://linux-hardware.org/?probe=72e7302ac3) | Apr 24, 2020 |
| Dell          | Precision M6600             | [e06525cd0b](https://linux-hardware.org/?probe=e06525cd0b) | Apr 23, 2020 |
| Dell          | Vostro 3478                 | [65a16b0f00](https://linux-hardware.org/?probe=65a16b0f00) | Apr 22, 2020 |
| Samsung       | RF510/RF410/RF710           | [8f349ab3e2](https://linux-hardware.org/?probe=8f349ab3e2) | Apr 22, 2020 |
| Lenovo        | ThinkPad L390 20NRCTO1WW    | [1bdf8cd0d9](https://linux-hardware.org/?probe=1bdf8cd0d9) | Apr 21, 2020 |
| Sony          | VGN-NR220E                  | [2bfcf51ff2](https://linux-hardware.org/?probe=2bfcf51ff2) | Apr 21, 2020 |
| Samsung       | RF510/RF410/RF710           | [bbeb62f526](https://linux-hardware.org/?probe=bbeb62f526) | Apr 20, 2020 |
| Dell          | Precision M6600             | [7036f11334](https://linux-hardware.org/?probe=7036f11334) | Apr 20, 2020 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [6bce8819c3](https://linux-hardware.org/?probe=6bce8819c3) | Apr 18, 2020 |
| ASUSTek       | X453SA                      | [ce1bd3affc](https://linux-hardware.org/?probe=ce1bd3affc) | Apr 18, 2020 |
| MSI           | GF62 7RE                    | [e6a9c83150](https://linux-hardware.org/?probe=e6a9c83150) | Apr 17, 2020 |
| Dell          | Inspiron 15-3552            | [2c8c6a6c8f](https://linux-hardware.org/?probe=2c8c6a6c8f) | Apr 17, 2020 |
| Dell          | Inspiron 1545               | [7ffb660f6c](https://linux-hardware.org/?probe=7ffb660f6c) | Apr 16, 2020 |
| Dell          | Inspiron 3481               | [3dd685ea1d](https://linux-hardware.org/?probe=3dd685ea1d) | Apr 16, 2020 |
| SLIMBOOK      | PROX14                      | [2f82f89270](https://linux-hardware.org/?probe=2f82f89270) | Apr 15, 2020 |
| Unknown       | Unknown                     | [da5860d1f0](https://linux-hardware.org/?probe=da5860d1f0) | Apr 14, 2020 |
| Unknown       | Unknown                     | [73343e4dc7](https://linux-hardware.org/?probe=73343e4dc7) | Apr 14, 2020 |
| Unknown       | Unknown                     | [1294897678](https://linux-hardware.org/?probe=1294897678) | Apr 14, 2020 |
| Unknown       | Unknown                     | [a94d05fa09](https://linux-hardware.org/?probe=a94d05fa09) | Apr 14, 2020 |
| HP            | EliteBook 8470p             | [e560953c4f](https://linux-hardware.org/?probe=e560953c4f) | Apr 14, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [02d576419f](https://linux-hardware.org/?probe=02d576419f) | Apr 14, 2020 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [749907f50c](https://linux-hardware.org/?probe=749907f50c) | Apr 14, 2020 |
| Lenovo        | ThinkPad X230 23259H1       | [df25e927f2](https://linux-hardware.org/?probe=df25e927f2) | Apr 13, 2020 |
| Acer          | Aspire 5735                 | [a3cd93e55c](https://linux-hardware.org/?probe=a3cd93e55c) | Apr 13, 2020 |
| Acer          | Aspire 5735                 | [ba27bfef0e](https://linux-hardware.org/?probe=ba27bfef0e) | Apr 13, 2020 |
| Acer          | Aspire 5735                 | [630e9989f0](https://linux-hardware.org/?probe=630e9989f0) | Apr 13, 2020 |
| Acer          | Aspire 5735                 | [61ea559994](https://linux-hardware.org/?probe=61ea559994) | Apr 13, 2020 |
| Lenovo        | ThinkBook 14-IML 20RV       | [e454a0b006](https://linux-hardware.org/?probe=e454a0b006) | Apr 13, 2020 |
| Dell          | Latitude E7240              | [b8c364e7d9](https://linux-hardware.org/?probe=b8c364e7d9) | Apr 12, 2020 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [4c9b9feddb](https://linux-hardware.org/?probe=4c9b9feddb) | Apr 12, 2020 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [cc276e39dd](https://linux-hardware.org/?probe=cc276e39dd) | Apr 12, 2020 |
| IBM           | ThinkPad T42 2373FWG        | [2bd3af38ce](https://linux-hardware.org/?probe=2bd3af38ce) | Apr 12, 2020 |
| Dell          | Latitude E5520              | [94f3454e55](https://linux-hardware.org/?probe=94f3454e55) | Apr 11, 2020 |
| Intel         | HURONRIVER                  | [f4f3b1e202](https://linux-hardware.org/?probe=f4f3b1e202) | Apr 11, 2020 |
| Acer          | Aspire E5-575               | [c51238bbe1](https://linux-hardware.org/?probe=c51238bbe1) | Apr 11, 2020 |
| Intel         | HURONRIVER                  | [575055af48](https://linux-hardware.org/?probe=575055af48) | Apr 10, 2020 |
| Unknown       | Unknown                     | [347c0aa3a3](https://linux-hardware.org/?probe=347c0aa3a3) | Apr 10, 2020 |
| Acer          | Aspire E5-575               | [e421f3a586](https://linux-hardware.org/?probe=e421f3a586) | Apr 10, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [f8798c2513](https://linux-hardware.org/?probe=f8798c2513) | Apr 09, 2020 |
| HP            | Presario CQ57               | [cee44eff4d](https://linux-hardware.org/?probe=cee44eff4d) | Apr 09, 2020 |
| HP            | Presario CQ57               | [e8dcf9600a](https://linux-hardware.org/?probe=e8dcf9600a) | Apr 08, 2020 |
| Lenovo        | ThinkPad T495s 20QKS01E0... | [c59d43a13b](https://linux-hardware.org/?probe=c59d43a13b) | Apr 08, 2020 |
| HP            | ProBook 470 G1              | [f440b0000d](https://linux-hardware.org/?probe=f440b0000d) | Apr 07, 2020 |
| HP            | ProBook 4710s               | [56f533f0f5](https://linux-hardware.org/?probe=56f533f0f5) | Apr 07, 2020 |
| ASUSTek       | 901                         | [4d95b9352d](https://linux-hardware.org/?probe=4d95b9352d) | Apr 07, 2020 |
| Lenovo        | ThinkPad X230 2324EW3       | [894c13d376](https://linux-hardware.org/?probe=894c13d376) | Apr 06, 2020 |
| HP            | Pavilion dv6                | [be26df391a](https://linux-hardware.org/?probe=be26df391a) | Apr 06, 2020 |
| Lenovo        | Yoga 2 11 20332             | [bbd3b573e1](https://linux-hardware.org/?probe=bbd3b573e1) | Apr 05, 2020 |
| Lenovo        | Yoga 2 11 20332             | [51c0fd8c5c](https://linux-hardware.org/?probe=51c0fd8c5c) | Apr 05, 2020 |
| HP            | Pavilion dv6                | [d0c6c442ea](https://linux-hardware.org/?probe=d0c6c442ea) | Apr 05, 2020 |
| Acer          | Nitro AN515-54              | [828d77e100](https://linux-hardware.org/?probe=828d77e100) | Apr 03, 2020 |
| Dell          | Precision 5530              | [02f6d9c432](https://linux-hardware.org/?probe=02f6d9c432) | Apr 02, 2020 |
| Dell          | Precision 5530              | [06208a4919](https://linux-hardware.org/?probe=06208a4919) | Apr 02, 2020 |
| Lenovo        | G550 2958                   | [aaaecc38c5](https://linux-hardware.org/?probe=aaaecc38c5) | Apr 02, 2020 |
| HP            | Laptop 15-da0xxx            | [1c548a6689](https://linux-hardware.org/?probe=1c548a6689) | Apr 01, 2020 |
| Dell          | Latitude E6230              | [b764b681bf](https://linux-hardware.org/?probe=b764b681bf) | Mar 31, 2020 |
| MSI           | GE70 2PC                    | [fd8b99e529](https://linux-hardware.org/?probe=fd8b99e529) | Mar 31, 2020 |
| Lenovo        | ThinkPad T410 2518F5U       | [00c57c11f2](https://linux-hardware.org/?probe=00c57c11f2) | Mar 30, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [6fa4e7d2e1](https://linux-hardware.org/?probe=6fa4e7d2e1) | Mar 30, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [69123c2512](https://linux-hardware.org/?probe=69123c2512) | Mar 30, 2020 |
| Dell          | XPS 13 9360                 | [925d4ca955](https://linux-hardware.org/?probe=925d4ca955) | Mar 29, 2020 |
| HP            | Pavilion dv1000 (PW923EA... | [fb937794c7](https://linux-hardware.org/?probe=fb937794c7) | Mar 28, 2020 |
| ASUSTek       | BU201LA                     | [e7400380e1](https://linux-hardware.org/?probe=e7400380e1) | Mar 28, 2020 |
| ASUSTek       | UX305FA                     | [59595a94c5](https://linux-hardware.org/?probe=59595a94c5) | Mar 26, 2020 |
| ASUSTek       | N55SF                       | [1787c065c7](https://linux-hardware.org/?probe=1787c065c7) | Mar 25, 2020 |
| ASUSTek       | X540SC                      | [dba0303a15](https://linux-hardware.org/?probe=dba0303a15) | Mar 23, 2020 |
| ASUSTek       | X540SC                      | [eefee76844](https://linux-hardware.org/?probe=eefee76844) | Mar 23, 2020 |
| HP            | Pavilion 15                 | [df1d0ba2d5](https://linux-hardware.org/?probe=df1d0ba2d5) | Mar 21, 2020 |
| HP            | Pavilion 15                 | [7b13854145](https://linux-hardware.org/?probe=7b13854145) | Mar 21, 2020 |
| Lenovo        | ThinkPad E480 20KN003WUS    | [94291f4b03](https://linux-hardware.org/?probe=94291f4b03) | Mar 21, 2020 |
| HP            | EliteBook 820 G1            | [94df64418a](https://linux-hardware.org/?probe=94df64418a) | Mar 21, 2020 |
| Unknown       | MEDION                      | [2f45c85c86](https://linux-hardware.org/?probe=2f45c85c86) | Mar 19, 2020 |
| Lenovo        | ThinkPad T510 4384G47       | [490e474ee7](https://linux-hardware.org/?probe=490e474ee7) | Mar 18, 2020 |
| Acer          | Aspire E5-521               | [3090aa7bb7](https://linux-hardware.org/?probe=3090aa7bb7) | Mar 18, 2020 |
| ASUSTek       | BU201LA                     | [ca91d7623b](https://linux-hardware.org/?probe=ca91d7623b) | Mar 16, 2020 |
| HP            | EliteBook 840 G6            | [f7db97fb08](https://linux-hardware.org/?probe=f7db97fb08) | Mar 15, 2020 |
| HP            | EliteBook 8560w             | [829a283daf](https://linux-hardware.org/?probe=829a283daf) | Mar 14, 2020 |
| Dell          | Inspiron 5570               | [e1dbe6bcbc](https://linux-hardware.org/?probe=e1dbe6bcbc) | Mar 14, 2020 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [fc2e5d7e80](https://linux-hardware.org/?probe=fc2e5d7e80) | Mar 14, 2020 |
| Lenovo        | ThinkPad E480 20KN004TBM    | [13768f8615](https://linux-hardware.org/?probe=13768f8615) | Mar 14, 2020 |
| Acer          | Aspire ES1-572              | [6ce6365443](https://linux-hardware.org/?probe=6ce6365443) | Mar 12, 2020 |
| HP            | ProBook 4510s               | [764886854e](https://linux-hardware.org/?probe=764886854e) | Mar 11, 2020 |
| HP            | ProBook 4510s               | [2645f47439](https://linux-hardware.org/?probe=2645f47439) | Mar 11, 2020 |
| Lenovo        | ThinkPad E480 20KN003WUS    | [b4ff3aebd5](https://linux-hardware.org/?probe=b4ff3aebd5) | Mar 11, 2020 |
| Positivo      | WCBT1013                    | [43da2eb4fa](https://linux-hardware.org/?probe=43da2eb4fa) | Mar 10, 2020 |
| Acer          | Aspire A315-51              | [edffa0baae](https://linux-hardware.org/?probe=edffa0baae) | Mar 09, 2020 |
| Acer          | Aspire A315-51              | [c846f4d57c](https://linux-hardware.org/?probe=c846f4d57c) | Mar 09, 2020 |
| Lenovo        | ThinkPad E480 20KN003WUS    | [def51cd96d](https://linux-hardware.org/?probe=def51cd96d) | Mar 08, 2020 |
| Acer          | Aspire 5742G                | [58a2dc5f80](https://linux-hardware.org/?probe=58a2dc5f80) | Mar 07, 2020 |
| Acer          | Aspire 5742G                | [acc24a33d8](https://linux-hardware.org/?probe=acc24a33d8) | Mar 07, 2020 |
| Acer          | Aspire 5742G                | [bb76bb0340](https://linux-hardware.org/?probe=bb76bb0340) | Mar 07, 2020 |
| Acer          | Aspire 5742G                | [d10edc7ae1](https://linux-hardware.org/?probe=d10edc7ae1) | Mar 07, 2020 |
| HP            | Laptop 15-da0xxx            | [4e3b47129c](https://linux-hardware.org/?probe=4e3b47129c) | Mar 05, 2020 |
| HP            | Laptop 15-da0xxx            | [b9eba4c95f](https://linux-hardware.org/?probe=b9eba4c95f) | Mar 05, 2020 |
| Lenovo        | ThinkPad X250 20CM001XGE    | [5b0eae5adc](https://linux-hardware.org/?probe=5b0eae5adc) | Mar 04, 2020 |
| HP            | Laptop 15-da0xxx            | [6cca7bf62c](https://linux-hardware.org/?probe=6cca7bf62c) | Mar 04, 2020 |
| HP            | ProBook 450 G6              | [fa42605126](https://linux-hardware.org/?probe=fa42605126) | Mar 03, 2020 |
| Lenovo        | V330-15IKB 81AX             | [ff630b19d5](https://linux-hardware.org/?probe=ff630b19d5) | Mar 01, 2020 |
| Thomson       | NEO14A-4BK64                | [b6f52f6b44](https://linux-hardware.org/?probe=b6f52f6b44) | Mar 01, 2020 |
| HP            | 350 G2                      | [bcc1a033a3](https://linux-hardware.org/?probe=bcc1a033a3) | Mar 01, 2020 |
| Thomson       | NEO14A-4BK64                | [3b5fa0f5bf](https://linux-hardware.org/?probe=3b5fa0f5bf) | Mar 01, 2020 |
| Thomson       | NEO14A-4BK64                | [96c2e03fae](https://linux-hardware.org/?probe=96c2e03fae) | Mar 01, 2020 |
| Lenovo        | V330-15IKB 81AX             | [d00c8f85c9](https://linux-hardware.org/?probe=d00c8f85c9) | Feb 29, 2020 |
| Lenovo        | V330-15IKB 81AX             | [0a2c0af439](https://linux-hardware.org/?probe=0a2c0af439) | Feb 28, 2020 |
| Lenovo        | V330-15IKB 81AX             | [d248f568d2](https://linux-hardware.org/?probe=d248f568d2) | Feb 28, 2020 |
| Lenovo        | ThinkPad W520 42844YS       | [9e345a31d7](https://linux-hardware.org/?probe=9e345a31d7) | Feb 27, 2020 |
| Lenovo        | ThinkPad X270 20K5S0R100    | [50bddb4fd0](https://linux-hardware.org/?probe=50bddb4fd0) | Feb 26, 2020 |
| Unknown       | Unknown                     | [108b23846e](https://linux-hardware.org/?probe=108b23846e) | Feb 24, 2020 |
| Dell          | Latitude E7450              | [76fdce1617](https://linux-hardware.org/?probe=76fdce1617) | Feb 22, 2020 |
| Toshiba       | Satellite A500              | [f9f3ea50f1](https://linux-hardware.org/?probe=f9f3ea50f1) | Feb 21, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0VK0... | [2ae929e678](https://linux-hardware.org/?probe=2ae929e678) | Feb 21, 2020 |
| Packard Be... | DOT S                       | [ef2c3a6924](https://linux-hardware.org/?probe=ef2c3a6924) | Feb 19, 2020 |
| ASUSTek       | UX303LA                     | [9881c222f2](https://linux-hardware.org/?probe=9881c222f2) | Feb 18, 2020 |
| ASUSTek       | UX303LA                     | [0d5af7f1a4](https://linux-hardware.org/?probe=0d5af7f1a4) | Feb 18, 2020 |
| Dell          | Latitude 5500               | [3a7f8e19f1](https://linux-hardware.org/?probe=3a7f8e19f1) | Feb 17, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [d3980912e7](https://linux-hardware.org/?probe=d3980912e7) | Feb 16, 2020 |
| HP            | 350 G2                      | [55e9f4b13f](https://linux-hardware.org/?probe=55e9f4b13f) | Feb 16, 2020 |
| HP            | 350 G2                      | [4ac3841f56](https://linux-hardware.org/?probe=4ac3841f56) | Feb 16, 2020 |
| Dell          | Latitude E7470              | [a66d13e7f0](https://linux-hardware.org/?probe=a66d13e7f0) | Feb 15, 2020 |
| Dell          | Latitude 7400               | [fd71dd29c7](https://linux-hardware.org/?probe=fd71dd29c7) | Feb 13, 2020 |
| ASUSTek       | K52F                        | [9dde03d12c](https://linux-hardware.org/?probe=9dde03d12c) | Feb 13, 2020 |
| Acer          | Aspire E1-531               | [702e69a7a6](https://linux-hardware.org/?probe=702e69a7a6) | Feb 12, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [7b2e159804](https://linux-hardware.org/?probe=7b2e159804) | Feb 12, 2020 |
| Lenovo        | ThinkPad T490s 20NX000EM... | [7773f702ab](https://linux-hardware.org/?probe=7773f702ab) | Feb 10, 2020 |
| ASUSTek       | K42Jr                       | [220523e2dd](https://linux-hardware.org/?probe=220523e2dd) | Feb 09, 2020 |
| HP            | ProBook 650 G1              | [0d25cd8e11](https://linux-hardware.org/?probe=0d25cd8e11) | Feb 08, 2020 |
| ASUSTek       | T100TAR                     | [b2ad180602](https://linux-hardware.org/?probe=b2ad180602) | Feb 08, 2020 |
| ASUSTek       | X301A1                      | [cc909dfcee](https://linux-hardware.org/?probe=cc909dfcee) | Feb 08, 2020 |
| HP            | EliteBook 820 G1            | [d913e4b376](https://linux-hardware.org/?probe=d913e4b376) | Feb 08, 2020 |
| HP            | ProBook 6570b               | [a15139afdb](https://linux-hardware.org/?probe=a15139afdb) | Feb 07, 2020 |
| Dell          | Latitude 7490               | [84de010704](https://linux-hardware.org/?probe=84de010704) | Feb 07, 2020 |
| Sony          | VPCEB11FM                   | [9094b452b0](https://linux-hardware.org/?probe=9094b452b0) | Feb 07, 2020 |
| Lenovo        | Yoga 2 Pro 20266            | [3036f629b3](https://linux-hardware.org/?probe=3036f629b3) | Feb 06, 2020 |
| Acer          | Aspire E5-571               | [35c5646f7a](https://linux-hardware.org/?probe=35c5646f7a) | Feb 06, 2020 |
| Acer          | Aspire E5-571               | [00b272b639](https://linux-hardware.org/?probe=00b272b639) | Feb 06, 2020 |
| Acer          | Aspire E5-571               | [26283f93ce](https://linux-hardware.org/?probe=26283f93ce) | Feb 06, 2020 |
| Acer          | Aspire E5-571               | [afc0a67e40](https://linux-hardware.org/?probe=afc0a67e40) | Feb 06, 2020 |
| Sony          | VPCEB11FM                   | [41291d091b](https://linux-hardware.org/?probe=41291d091b) | Feb 06, 2020 |
| Acer          | Aspire E5-571               | [ca579e3df3](https://linux-hardware.org/?probe=ca579e3df3) | Feb 06, 2020 |
| Lenovo        | ThinkPad T495s 20QKS01E0... | [4e0546e702](https://linux-hardware.org/?probe=4e0546e702) | Feb 06, 2020 |
| Acer          | Aspire E5-571               | [bea5172578](https://linux-hardware.org/?probe=bea5172578) | Feb 06, 2020 |
| Acer          | Aspire E5-571               | [56b40d8872](https://linux-hardware.org/?probe=56b40d8872) | Feb 06, 2020 |
| Acer          | Aspire E5-571               | [e4e6b2ff99](https://linux-hardware.org/?probe=e4e6b2ff99) | Feb 06, 2020 |
| Sony          | VPCEB11FM                   | [beb33b8e5f](https://linux-hardware.org/?probe=beb33b8e5f) | Feb 06, 2020 |
| Dell          | Latitude E4310              | [116a5459eb](https://linux-hardware.org/?probe=116a5459eb) | Feb 04, 2020 |
| HP            | ZBook 14u G5                | [b4e79c454b](https://linux-hardware.org/?probe=b4e79c454b) | Feb 04, 2020 |
| HP            | EliteBook 840 G6            | [cca65a037e](https://linux-hardware.org/?probe=cca65a037e) | Feb 04, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [97b5418b6d](https://linux-hardware.org/?probe=97b5418b6d) | Feb 03, 2020 |
| ASUSTek       | X301A1                      | [3b495f3518](https://linux-hardware.org/?probe=3b495f3518) | Feb 02, 2020 |
| Acer          | Aspire A517-51G             | [f307bd3350](https://linux-hardware.org/?probe=f307bd3350) | Feb 02, 2020 |
| Timi          | TM1701                      | [921a36a46c](https://linux-hardware.org/?probe=921a36a46c) | Jan 31, 2020 |
| Acer          | Aspire V3-331               | [6f85285677](https://linux-hardware.org/?probe=6f85285677) | Jan 28, 2020 |
| HP            | Laptop 15-db0xxx            | [03731a6e89](https://linux-hardware.org/?probe=03731a6e89) | Jan 28, 2020 |
| Acer          | Aspire V3-331               | [ceea29c7dc](https://linux-hardware.org/?probe=ceea29c7dc) | Jan 27, 2020 |
| Lenovo        | ThinkPad T440s 20AQ005NU... | [55d9286a1b](https://linux-hardware.org/?probe=55d9286a1b) | Jan 27, 2020 |
| ASUSTek       | 1000HE                      | [cb377c5739](https://linux-hardware.org/?probe=cb377c5739) | Jan 26, 2020 |
| Acer          | Aspire V3-331               | [ab37d08927](https://linux-hardware.org/?probe=ab37d08927) | Jan 26, 2020 |
| Sony          | VPCEB1S1E                   | [eee6e3b375](https://linux-hardware.org/?probe=eee6e3b375) | Jan 26, 2020 |
| Dell          | Latitude E7450              | [97d838db7d](https://linux-hardware.org/?probe=97d838db7d) | Jan 26, 2020 |
| Dell          | Latitude E7450              | [62308c2ebc](https://linux-hardware.org/?probe=62308c2ebc) | Jan 26, 2020 |
| Dell          | Latitude 5580               | [a8d3170890](https://linux-hardware.org/?probe=a8d3170890) | Jan 25, 2020 |
| Acer          | ES1-512                     | [30e9eaaee7](https://linux-hardware.org/?probe=30e9eaaee7) | Jan 25, 2020 |
| Dell          | Inspiron 5567               | [c2537a9af8](https://linux-hardware.org/?probe=c2537a9af8) | Jan 24, 2020 |
| HP            | Pavilion Notebook           | [b58bacd094](https://linux-hardware.org/?probe=b58bacd094) | Jan 24, 2020 |
| Acer          | Aspire 4738Z                | [f6d23a2b44](https://linux-hardware.org/?probe=f6d23a2b44) | Jan 24, 2020 |
| HP            | ZBook 14u G5                | [4820759d86](https://linux-hardware.org/?probe=4820759d86) | Jan 21, 2020 |
| Lenovo        | ThinkPad P53 20QN0006GE     | [9d430acc9e](https://linux-hardware.org/?probe=9d430acc9e) | Jan 20, 2020 |
| Lenovo        | ThinkPad P53 20QN0006GE     | [93aeb8379a](https://linux-hardware.org/?probe=93aeb8379a) | Jan 20, 2020 |
| Lenovo        | ThinkPad P53 20QN0006GE     | [ad77143a11](https://linux-hardware.org/?probe=ad77143a11) | Jan 20, 2020 |
| Dell          | Inspiron 5567               | [fa4385b265](https://linux-hardware.org/?probe=fa4385b265) | Jan 20, 2020 |
| Alienware     | 17 R5                       | [6276dbc8cf](https://linux-hardware.org/?probe=6276dbc8cf) | Jan 18, 2020 |
| Alienware     | 17 R5                       | [9c7bf6009b](https://linux-hardware.org/?probe=9c7bf6009b) | Jan 18, 2020 |
| Sony          | VGN-NS190J                  | [4ed6ccc4e4](https://linux-hardware.org/?probe=4ed6ccc4e4) | Jan 18, 2020 |
| Lenovo        | ThinkPad L412 0585W28       | [8ba74bb2b0](https://linux-hardware.org/?probe=8ba74bb2b0) | Jan 13, 2020 |
| Lenovo        | ThinkPad X230 23259H1       | [338bcd8cd1](https://linux-hardware.org/?probe=338bcd8cd1) | Jan 13, 2020 |
| ASUSTek       | K54C                        | [f67601f0fa](https://linux-hardware.org/?probe=f67601f0fa) | Jan 12, 2020 |
| ASUSTek       | K54C                        | [fd26fcc58a](https://linux-hardware.org/?probe=fd26fcc58a) | Jan 11, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [94b406a65f](https://linux-hardware.org/?probe=94b406a65f) | Jan 09, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [cf5b83db0d](https://linux-hardware.org/?probe=cf5b83db0d) | Jan 08, 2020 |
| Lenovo        | ThinkPad X230 2325WNX       | [7f0b053417](https://linux-hardware.org/?probe=7f0b053417) | Jan 05, 2020 |
| ASUSTek       | K46CB                       | [45b756e92d](https://linux-hardware.org/?probe=45b756e92d) | Jan 04, 2020 |
| ASUSTek       | K46CB                       | [1a25890709](https://linux-hardware.org/?probe=1a25890709) | Jan 04, 2020 |
| Dell          | Latitude 5500               | [84e2b9bc59](https://linux-hardware.org/?probe=84e2b9bc59) | Jan 03, 2020 |
| Dell          | Latitude 5500               | [0d946e75f9](https://linux-hardware.org/?probe=0d946e75f9) | Jan 03, 2020 |
| Dell          | Latitude 5500               | [e4d87650c6](https://linux-hardware.org/?probe=e4d87650c6) | Jan 03, 2020 |
| Dell          | Latitude 5500               | [32ba40cd41](https://linux-hardware.org/?probe=32ba40cd41) | Jan 03, 2020 |
| Dell          | Latitude 5500               | [28f28acfa7](https://linux-hardware.org/?probe=28f28acfa7) | Jan 03, 2020 |
| Dell          | Latitude 5500               | [be70af9da7](https://linux-hardware.org/?probe=be70af9da7) | Jan 03, 2020 |
| Notebook      | N150ZU                      | [3e3a208ead](https://linux-hardware.org/?probe=3e3a208ead) | Jan 03, 2020 |
| Acer          | Aspire 5250                 | [5a211b776b](https://linux-hardware.org/?probe=5a211b776b) | Jan 03, 2020 |
| Acer          | Aspire 5250                 | [67d73a0b2e](https://linux-hardware.org/?probe=67d73a0b2e) | Jan 03, 2020 |
| Dell          | Vostro 3560                 | [704c22f5ee](https://linux-hardware.org/?probe=704c22f5ee) | Jan 02, 2020 |
| Samsung       | 305E4A/305E5A/305E7A        | [eea7a5432d](https://linux-hardware.org/?probe=eea7a5432d) | Dec 31, 2019 |
| Dell          | Latitude E4310              | [e487d4f0a0](https://linux-hardware.org/?probe=e487d4f0a0) | Dec 31, 2019 |
| Apple         | MacBook2,1                  | [af0dd12a8b](https://linux-hardware.org/?probe=af0dd12a8b) | Dec 29, 2019 |
| Acer          | Aspire V3-331               | [182049fe77](https://linux-hardware.org/?probe=182049fe77) | Dec 28, 2019 |
| Lenovo        | E41-25 81FS                 | [e0f719aeb9](https://linux-hardware.org/?probe=e0f719aeb9) | Dec 25, 2019 |
| Lenovo        | ThinkPad E480 20KN005CRT    | [f4826c3a2a](https://linux-hardware.org/?probe=f4826c3a2a) | Dec 25, 2019 |
| Acer          | Aspire 5738                 | [c2904e1345](https://linux-hardware.org/?probe=c2904e1345) | Dec 23, 2019 |
| Acer          | ES1-512                     | [74719c2872](https://linux-hardware.org/?probe=74719c2872) | Dec 23, 2019 |
| Lenovo        | V340-17IWL 81RG             | [3df2fcfb89](https://linux-hardware.org/?probe=3df2fcfb89) | Dec 20, 2019 |
| Toshiba       | Satellite S55-B             | [a2d5f0ed15](https://linux-hardware.org/?probe=a2d5f0ed15) | Dec 19, 2019 |
| Toshiba       | Satellite S55-B             | [6affc21696](https://linux-hardware.org/?probe=6affc21696) | Dec 19, 2019 |
| Dell          | Inspiron 5593               | [5d6ddb0705](https://linux-hardware.org/?probe=5d6ddb0705) | Dec 17, 2019 |
| Lenovo        | Legion Y9000X 2020 81TH     | [dbca41493b](https://linux-hardware.org/?probe=dbca41493b) | Dec 16, 2019 |
| ASUSTek       | 900                         | [df4fa2d486](https://linux-hardware.org/?probe=df4fa2d486) | Dec 16, 2019 |
| ASUSTek       | 701                         | [6eedb1a52a](https://linux-hardware.org/?probe=6eedb1a52a) | Dec 16, 2019 |
| Toshiba       | Satellite PRO C50-A-154     | [ad34d3f9ad](https://linux-hardware.org/?probe=ad34d3f9ad) | Dec 15, 2019 |
| Toshiba       | Satellite PRO C50-A-154     | [3cf30b9dac](https://linux-hardware.org/?probe=3cf30b9dac) | Dec 15, 2019 |
| Toshiba       | Satellite PRO C50-A-154     | [8ee0ae1ac9](https://linux-hardware.org/?probe=8ee0ae1ac9) | Dec 15, 2019 |
| HP            | ProBook 650 G5              | [e3e622278c](https://linux-hardware.org/?probe=e3e622278c) | Dec 14, 2019 |
| HP            | ZBook 15u G5                | [8c143ca02e](https://linux-hardware.org/?probe=8c143ca02e) | Dec 13, 2019 |
| HP            | ZBook 15u G5                | [dbba10b168](https://linux-hardware.org/?probe=dbba10b168) | Dec 13, 2019 |
| HP            | ZBook 15u G5                | [0d1d3b9979](https://linux-hardware.org/?probe=0d1d3b9979) | Dec 13, 2019 |
| HP            | ZBook 15u G5                | [b270d1815f](https://linux-hardware.org/?probe=b270d1815f) | Dec 13, 2019 |
| ASUSTek       | X540LJ                      | [81f8804034](https://linux-hardware.org/?probe=81f8804034) | Dec 13, 2019 |
| Acer          | Extensa 5620                | [3d881d6e68](https://linux-hardware.org/?probe=3d881d6e68) | Dec 13, 2019 |
| Dell          | Inspiron 5593               | [200ceab170](https://linux-hardware.org/?probe=200ceab170) | Dec 12, 2019 |
| Dell          | Inspiron 5593               | [90b19af55f](https://linux-hardware.org/?probe=90b19af55f) | Dec 12, 2019 |
| Dell          | Inspiron 5593               | [c852f3c822](https://linux-hardware.org/?probe=c852f3c822) | Dec 12, 2019 |
| Medion        | E4251 MD61554               | [7e86f1b5e7](https://linux-hardware.org/?probe=7e86f1b5e7) | Dec 10, 2019 |
| Lenovo        | Legion Y9000X 2020 81TH     | [626a3add4b](https://linux-hardware.org/?probe=626a3add4b) | Dec 09, 2019 |
| Notebook      | W9x0LU                      | [0d8faf0ad0](https://linux-hardware.org/?probe=0d8faf0ad0) | Dec 08, 2019 |
| Lenovo        | ThinkPad T430 23492A2       | [b826ddd907](https://linux-hardware.org/?probe=b826ddd907) | Dec 03, 2019 |
| ASUSTek       | K52Je                       | [4750f467b4](https://linux-hardware.org/?probe=4750f467b4) | Dec 03, 2019 |
| Acer          | Aspire ES1-524              | [af870ddf65](https://linux-hardware.org/?probe=af870ddf65) | Dec 02, 2019 |
| HP            | EliteBook 850 G5            | [ff5c12bc07](https://linux-hardware.org/?probe=ff5c12bc07) | Dec 02, 2019 |
| Dell          | Latitude E5450              | [9d71909e26](https://linux-hardware.org/?probe=9d71909e26) | Dec 02, 2019 |
| Acer          | Extensa 5620                | [81d06997d4](https://linux-hardware.org/?probe=81d06997d4) | Nov 30, 2019 |
| Toshiba       | Satellite S855              | [08e66c8158](https://linux-hardware.org/?probe=08e66c8158) | Nov 28, 2019 |
| Toshiba       | Satellite S855              | [ec1db39849](https://linux-hardware.org/?probe=ec1db39849) | Nov 27, 2019 |
| ASUSTek       | X406UAR                     | [a1d52e4665](https://linux-hardware.org/?probe=a1d52e4665) | Nov 25, 2019 |
| Acer          | Aspire A515-52G             | [0804d7107b](https://linux-hardware.org/?probe=0804d7107b) | Nov 24, 2019 |
| Notebook      | W9x0LU                      | [1ba7ad09aa](https://linux-hardware.org/?probe=1ba7ad09aa) | Nov 24, 2019 |
| HP            | Split 13 x2 Detachable P... | [080aeedb47](https://linux-hardware.org/?probe=080aeedb47) | Nov 22, 2019 |
| Intel         | W7645                       | [6a6005d7d3](https://linux-hardware.org/?probe=6a6005d7d3) | Nov 20, 2019 |
| Lenovo        | ThinkPad E570 20H6S05D00    | [6f165c6a0e](https://linux-hardware.org/?probe=6f165c6a0e) | Nov 20, 2019 |
| Dell          | Latitude E5520              | [6e6b64d799](https://linux-hardware.org/?probe=6e6b64d799) | Nov 18, 2019 |
| Lenovo        | ThinkPad Edge E320 12983... | [a8d9e5ef41](https://linux-hardware.org/?probe=a8d9e5ef41) | Nov 16, 2019 |
| ASUSTek       | M80TA                       | [0ca0fc90d3](https://linux-hardware.org/?probe=0ca0fc90d3) | Nov 13, 2019 |
| ASUSTek       | M80TA                       | [0d85c8e42d](https://linux-hardware.org/?probe=0d85c8e42d) | Nov 13, 2019 |
| ASUSTek       | X406UAR                     | [9174d1eba4](https://linux-hardware.org/?probe=9174d1eba4) | Nov 11, 2019 |
| Purism        | Librem 15 v3                | [8200c0dcd0](https://linux-hardware.org/?probe=8200c0dcd0) | Nov 11, 2019 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [f56a385db9](https://linux-hardware.org/?probe=f56a385db9) | Nov 10, 2019 |
| Lenovo        | ThinkPad X201 3680F7G       | [32ded3ae85](https://linux-hardware.org/?probe=32ded3ae85) | Nov 08, 2019 |
| Acer          | Aspire 5738                 | [96bf39717a](https://linux-hardware.org/?probe=96bf39717a) | Nov 03, 2019 |
| Lenovo        | ThinkPad X390 20Q1S27L01    | [0441eab782](https://linux-hardware.org/?probe=0441eab782) | Nov 03, 2019 |
| Notebook      | W9x0LU                      | [3994d698da](https://linux-hardware.org/?probe=3994d698da) | Nov 02, 2019 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [0806e2a6d8](https://linux-hardware.org/?probe=0806e2a6d8) | Nov 01, 2019 |
| Panasonic     | CF-31SBM61DM                | [55e0cbbc35](https://linux-hardware.org/?probe=55e0cbbc35) | Oct 26, 2019 |
| HP            | 630                         | [99ab4364d4](https://linux-hardware.org/?probe=99ab4364d4) | Oct 26, 2019 |
| Dell          | Inspiron 3576               | [ca85cb68a2](https://linux-hardware.org/?probe=ca85cb68a2) | Oct 22, 2019 |
| Dell          | Inspiron 3576               | [627372b8b8](https://linux-hardware.org/?probe=627372b8b8) | Oct 21, 2019 |
| Dell          | Latitude 3500               | [3b2d9cd728](https://linux-hardware.org/?probe=3b2d9cd728) | Oct 20, 2019 |
| Samsung       | R780/R778                   | [6fa6b07e97](https://linux-hardware.org/?probe=6fa6b07e97) | Oct 19, 2019 |
| HP            | Notebook                    | [cec70bf357](https://linux-hardware.org/?probe=cec70bf357) | Oct 18, 2019 |
| Acer          | Aspire 5738                 | [8bc986a445](https://linux-hardware.org/?probe=8bc986a445) | Oct 15, 2019 |
| Acer          | Aspire 5738                 | [4d8f062003](https://linux-hardware.org/?probe=4d8f062003) | Oct 15, 2019 |
| Acer          | Aspire 5738                 | [9f09cae0a1](https://linux-hardware.org/?probe=9f09cae0a1) | Oct 15, 2019 |
| Acer          | Aspire 5738                 | [acfe84eebd](https://linux-hardware.org/?probe=acfe84eebd) | Oct 12, 2019 |
| HP            | Pavilion Laptop 15-cs2xx... | [fd3e0640b7](https://linux-hardware.org/?probe=fd3e0640b7) | Oct 05, 2019 |
| HP            | Pavilion Laptop 15-cs2xx... | [918bb5aabb](https://linux-hardware.org/?probe=918bb5aabb) | Oct 05, 2019 |
| Acer          | Aspire V3-772G              | [9cbde1e6e7](https://linux-hardware.org/?probe=9cbde1e6e7) | Oct 04, 2019 |
| ASUSTek       | UX550VE                     | [8bd52cd8f7](https://linux-hardware.org/?probe=8bd52cd8f7) | Oct 01, 2019 |
| ASUSTek       | X540LA                      | [297d35f1b7](https://linux-hardware.org/?probe=297d35f1b7) | Sep 29, 2019 |
| Dell          | Precision 5530              | [d4186f5067](https://linux-hardware.org/?probe=d4186f5067) | Sep 20, 2019 |
| Apple         | MacBook7,1                  | [ccc4e248db](https://linux-hardware.org/?probe=ccc4e248db) | Sep 20, 2019 |
| Dell          | Precision 5530              | [3ac79e9d3c](https://linux-hardware.org/?probe=3ac79e9d3c) | Sep 20, 2019 |
| Dell          | Precision 5530              | [e23f4aa994](https://linux-hardware.org/?probe=e23f4aa994) | Sep 20, 2019 |
| Acer          | Extensa 4620                | [ad2d03638a](https://linux-hardware.org/?probe=ad2d03638a) | Sep 19, 2019 |
| Acer          | Extensa 4620                | [53b18ab3fc](https://linux-hardware.org/?probe=53b18ab3fc) | Sep 19, 2019 |
| Acer          | Extensa 4620                | [8af03e5647](https://linux-hardware.org/?probe=8af03e5647) | Sep 19, 2019 |
| Samsung       | NC208/NC108                 | [a99fe6de20](https://linux-hardware.org/?probe=a99fe6de20) | Sep 16, 2019 |
| HP            | Unknown                     | [0fdd28110e](https://linux-hardware.org/?probe=0fdd28110e) | Sep 16, 2019 |
| HP            | Unknown                     | [2dc0a92626](https://linux-hardware.org/?probe=2dc0a92626) | Sep 16, 2019 |
| Acer          | Aspire V3-331               | [62c417b8a4](https://linux-hardware.org/?probe=62c417b8a4) | Sep 14, 2019 |
| Acer          | Aspire V3-331               | [eb31e485a1](https://linux-hardware.org/?probe=eb31e485a1) | Sep 14, 2019 |
| Acer          | Aspire V3-331               | [cdf5e8ce04](https://linux-hardware.org/?probe=cdf5e8ce04) | Sep 14, 2019 |
| Acer          | Aspire V3-331               | [c83b4321c8](https://linux-hardware.org/?probe=c83b4321c8) | Sep 13, 2019 |
| Acer          | Extensa 5620                | [2ee51e8201](https://linux-hardware.org/?probe=2ee51e8201) | Sep 13, 2019 |
| MSI           | GE72 7RD                    | [4eff8cfbba](https://linux-hardware.org/?probe=4eff8cfbba) | Sep 13, 2019 |
| Acer          | Aspire 5738                 | [25229e75ae](https://linux-hardware.org/?probe=25229e75ae) | Sep 10, 2019 |
| Lenovo        | ThinkPad A485 20MVS06F00    | [b9165d8ee1](https://linux-hardware.org/?probe=b9165d8ee1) | Sep 01, 2019 |
| Lenovo        | ThinkPad A485 20MVS06F00    | [65e6d04980](https://linux-hardware.org/?probe=65e6d04980) | Aug 27, 2019 |
| Apple         | MacBookPro7,1               | [0933543fa4](https://linux-hardware.org/?probe=0933543fa4) | Aug 21, 2019 |
| Acer          | Aspire V3-331               | [3c3cbd8f36](https://linux-hardware.org/?probe=3c3cbd8f36) | Aug 18, 2019 |
| Acer          | Aspire V3-331               | [7e4c5a5433](https://linux-hardware.org/?probe=7e4c5a5433) | Aug 18, 2019 |
| Apple         | MacBookPro7,1               | [4ee78b3e9b](https://linux-hardware.org/?probe=4ee78b3e9b) | Aug 17, 2019 |
| Apple         | MacBookPro7,1               | [561df892c7](https://linux-hardware.org/?probe=561df892c7) | Aug 17, 2019 |
| Acer          | Aspire V3-331               | [b9b8afcb55](https://linux-hardware.org/?probe=b9b8afcb55) | Aug 16, 2019 |
| Acer          | Aspire V3-331               | [8a92a65c2e](https://linux-hardware.org/?probe=8a92a65c2e) | Aug 16, 2019 |
| Acer          | Aspire V3-331               | [d7fd0f3a13](https://linux-hardware.org/?probe=d7fd0f3a13) | Aug 14, 2019 |
| Acer          | Aspire V3-331               | [d30a2ad389](https://linux-hardware.org/?probe=d30a2ad389) | Aug 14, 2019 |
| Acer          | Aspire V3-331               | [e83cfe55e3](https://linux-hardware.org/?probe=e83cfe55e3) | Aug 14, 2019 |
| Acer          | Aspire V3-331               | [3d1b234e42](https://linux-hardware.org/?probe=3d1b234e42) | Aug 13, 2019 |
| Acer          | Aspire V3-331               | [39d74113ef](https://linux-hardware.org/?probe=39d74113ef) | Aug 13, 2019 |
| Acer          | Aspire V3-331               | [1f593f0982](https://linux-hardware.org/?probe=1f593f0982) | Aug 13, 2019 |
| GPD           | MicroPC                     | [19516bca1b](https://linux-hardware.org/?probe=19516bca1b) | Aug 07, 2019 |
| Dell          | Inspiron 11 - 3147          | [d73954cb96](https://linux-hardware.org/?probe=d73954cb96) | Jul 30, 2019 |
| Dell          | Latitude 3379               | [112eb80a9e](https://linux-hardware.org/?probe=112eb80a9e) | Jul 26, 2019 |
| Lenovo        | ThinkPad A485 20MVS06F00    | [7ccac31d71](https://linux-hardware.org/?probe=7ccac31d71) | Jul 23, 2019 |
| Acer          | Aspire E1-531               | [f28d18f3e9](https://linux-hardware.org/?probe=f28d18f3e9) | Jul 18, 2019 |
| HP            | ProBook 455R G6             | [0d375562bd](https://linux-hardware.org/?probe=0d375562bd) | Jul 17, 2019 |
| HP            | ProBook 455R G6             | [12d1faa353](https://linux-hardware.org/?probe=12d1faa353) | Jul 17, 2019 |
| Dell          | Inspiron 15-3567            | [75fa8fbc3f](https://linux-hardware.org/?probe=75fa8fbc3f) | Jul 11, 2019 |
| Lenovo        | ThinkPad X201 Tablet 309... | [23e3956f4a](https://linux-hardware.org/?probe=23e3956f4a) | Jun 13, 2019 |
| Notebook      | P7xxTM1                     | [3cfc602d81](https://linux-hardware.org/?probe=3cfc602d81) | Jun 13, 2019 |
| Notebook      | P7xxTM1                     | [1dd51f23ea](https://linux-hardware.org/?probe=1dd51f23ea) | Jun 13, 2019 |
| Dell          | Inspiron 5421               | [d8db450d73](https://linux-hardware.org/?probe=d8db450d73) | Jun 07, 2019 |
| ASUSTek       | S551LN                      | [f59445db15](https://linux-hardware.org/?probe=f59445db15) | Jun 01, 2019 |
| HP            | ProBook 645 G4              | [f2f88aaa9d](https://linux-hardware.org/?probe=f2f88aaa9d) | May 24, 2019 |
| HP            | ProBook 645 G4              | [049bd45822](https://linux-hardware.org/?probe=049bd45822) | May 24, 2019 |
| Lenovo        | IdeaPad Z580                | [2723c698f1](https://linux-hardware.org/?probe=2723c698f1) | May 12, 2019 |
| ViewSonic     | ViewBook                    | [65ce936a8c](https://linux-hardware.org/?probe=65ce936a8c) | May 11, 2019 |
| ViewSonic     | ViewBook                    | [8a9bbac187](https://linux-hardware.org/?probe=8a9bbac187) | May 05, 2019 |
| Samsung       | RF511/RF411/RF711           | [32cbae5d42](https://linux-hardware.org/?probe=32cbae5d42) | May 02, 2019 |
| Samsung       | RF511/RF411/RF711           | [bf222ad6cf](https://linux-hardware.org/?probe=bf222ad6cf) | May 02, 2019 |
| Lenovo        | IdeaPad Z580                | [4d85db18f1](https://linux-hardware.org/?probe=4d85db18f1) | May 01, 2019 |
| HP            | Pavilion dv7                | [d6fa98bc42](https://linux-hardware.org/?probe=d6fa98bc42) | Apr 25, 2019 |
| HP            | Pavilion dv7                | [a386980478](https://linux-hardware.org/?probe=a386980478) | Apr 07, 2019 |
| Timi          | TM1701                      | [324d19c465](https://linux-hardware.org/?probe=324d19c465) | Mar 27, 2019 |
| Dell          | Inspiron 5558               | [9a6142ccdd](https://linux-hardware.org/?probe=9a6142ccdd) | Mar 26, 2019 |
| Dell          | Inspiron 7520               | [3be6bab654](https://linux-hardware.org/?probe=3be6bab654) | Mar 25, 2019 |
| Dell          | Inspiron 7520               | [fe09d19c40](https://linux-hardware.org/?probe=fe09d19c40) | Mar 25, 2019 |
| Lenovo        | ThinkPad T430 2349U2B       | [ab4d794a5e](https://linux-hardware.org/?probe=ab4d794a5e) | Mar 23, 2019 |
| Lenovo        | ThinkPad X230 2325AEG       | [2b8bcfe576](https://linux-hardware.org/?probe=2b8bcfe576) | Feb 19, 2019 |
| HP            | 15                          | [30a42ae5dc](https://linux-hardware.org/?probe=30a42ae5dc) | Feb 13, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 4.19.0-9-amd64       | 84        | 9.89%   |
| 4.19.0-6-amd64       | 79        | 9.31%   |
| 4.19.0-8-amd64       | 68        | 8.01%   |
| 4.19.0-13-amd64      | 68        | 8.01%   |
| 4.19.0-10-amd64      | 50        | 5.89%   |
| 4.19.0-16-amd64      | 48        | 5.65%   |
| 4.19.0-12-amd64      | 47        | 5.54%   |
| 4.19.0-14-amd64      | 40        | 4.71%   |
| 4.19.0-17-amd64      | 30        | 3.53%   |
| 4.19.0-11-amd64      | 22        | 2.59%   |
| 4.19.0-5-amd64       | 17        | 2%      |
| 5.8.0-0.bpo.2-amd64  | 13        | 1.53%   |
| 5.10.0-0.bpo.3-amd64 | 11        | 1.3%    |
| 5.7.0-0.bpo.2-amd64  | 9         | 1.06%   |
| 5.4.0-4-amd64        | 9         | 1.06%   |
| 5.8.0-3-amd64        | 7         | 0.82%   |
| 5.6.0-2-amd64        | 7         | 0.82%   |
| 5.6.0-0.bpo.2-amd64  | 7         | 0.82%   |
| 5.9.0-0.bpo.5-amd64  | 6         | 0.71%   |
| 5.8.0-2-amd64        | 6         | 0.71%   |
| 5.7.0-1-amd64        | 6         | 0.71%   |
| 5.4.0-0.bpo.2-amd64  | 6         | 0.71%   |
| 5.10.0-0.bpo.7-amd64 | 6         | 0.71%   |
| 5.10.0-0.bpo.5-amd64 | 6         | 0.71%   |
| 4.19.0-6-686-pae     | 6         | 0.71%   |
| 4.19.0-16-686-pae    | 6         | 0.71%   |
| 5.9.0-4-amd64        | 5         | 0.59%   |
| 5.5.0-0.bpo.2-amd64  | 5         | 0.59%   |
| 5.4.0-3-amd64        | 5         | 0.59%   |
| 5.4.0-0.bpo.4-amd64  | 5         | 0.59%   |
| 4.19.0-8-686         | 5         | 0.59%   |
| 4.19.0-4-amd64       | 5         | 0.59%   |
| 4.19.0-13-686-pae    | 5         | 0.59%   |
| 5.9.0-1-amd64        | 4         | 0.47%   |
| 5.9.0-0.bpo.2-amd64  | 4         | 0.47%   |
| 5.10.0-5mx-amd64     | 4         | 0.47%   |
| 4.19.0-9-686         | 4         | 0.47%   |
| 5.9.0-5-amd64        | 3         | 0.35%   |
| 5.8.0-1-amd64        | 3         | 0.35%   |
| 5.4.0-2-amd64        | 3         | 0.35%   |
| 5.3.0-2-amd64        | 3         | 0.35%   |
| 5.3.0-0.bpo.2-amd64  | 3         | 0.35%   |
| 4.19.0-8-686-pae     | 3         | 0.35%   |
| 4.19.0-16-686        | 3         | 0.35%   |
| 4.19.0-13-686        | 3         | 0.35%   |
| 4.19.0-10-686-pae    | 3         | 0.35%   |
| 5.9.0-3-amd64        | 2         | 0.24%   |
| 5.7.0-3-amd64        | 2         | 0.24%   |
| 5.7.0-2-amd64        | 2         | 0.24%   |
| 5.5.0-2-amd64        | 2         | 0.24%   |
| 5.3.5-64             | 2         | 0.24%   |
| 5.2.0-3-amd64        | 2         | 0.24%   |
| 5.2.0-2-rt-amd64     | 2         | 0.24%   |
| 5.2.0-2-amd64        | 2         | 0.24%   |
| 5.2.0-0.bpo.2-amd64  | 2         | 0.24%   |
| 4.19.0-2-amd64       | 2         | 0.24%   |
| 4.19.0-17-686-pae    | 2         | 0.24%   |
| 4.19.0-15-amd64      | 2         | 0.24%   |
| 4.19.0-14-686-pae    | 2         | 0.24%   |
| 5.9.14-xanmod1       | 1         | 0.12%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version   | Notebooks | Percent |
|-----------|-----------|---------|
| 4.19.0    | 571       | 71.38%  |
| 5.4.0     | 34        | 4.25%   |
| 5.10.0    | 33        | 4.13%   |
| 5.8.0     | 30        | 3.75%   |
| 5.9.0     | 24        | 3%      |
| 5.7.0     | 20        | 2.5%    |
| 5.6.0     | 16        | 2%      |
| 5.5.0     | 10        | 1.25%   |
| 5.2.0     | 9         | 1.13%   |
| 5.3.0     | 8         | 1%      |
| 4.9.0     | 3         | 0.38%   |
| 5.3.5     | 2         | 0.25%   |
| 5.0.0     | 2         | 0.25%   |
| 5.9.14    | 1         | 0.13%   |
| 5.9.11    | 1         | 0.13%   |
| 5.8.2     | 1         | 0.13%   |
| 5.8.16    | 1         | 0.13%   |
| 5.7.13    | 1         | 0.13%   |
| 5.6.8     | 1         | 0.13%   |
| 5.6.2     | 1         | 0.13%   |
| 5.6.17    | 1         | 0.13%   |
| 5.6.10    | 1         | 0.13%   |
| 5.5.19    | 1         | 0.13%   |
| 5.5.13    | 1         | 0.13%   |
| 5.4.75    | 1         | 0.13%   |
| 5.4.65    | 1         | 0.13%   |
| 5.4.35    | 1         | 0.13%   |
| 5.4.28    | 1         | 0.13%   |
| 5.4.2     | 1         | 0.13%   |
| 5.4.17    | 1         | 0.13%   |
| 5.4.16    | 1         | 0.13%   |
| 5.4.13    | 1         | 0.13%   |
| 5.4.119   | 1         | 0.13%   |
| 5.4.104.1 | 1         | 0.13%   |
| 5.3.18    | 1         | 0.13%   |
| 5.2.8     | 1         | 0.13%   |
| 5.2.5     | 1         | 0.13%   |
| 5.2.21    | 1         | 0.13%   |
| 5.2.17    | 1         | 0.13%   |
| 5.2.15    | 1         | 0.13%   |
| 5.13.0    | 1         | 0.13%   |
| 5.12.0    | 1         | 0.13%   |
| 5.1.3     | 1         | 0.13%   |
| 4.9.218   | 1         | 0.13%   |
| 4.9.168   | 1         | 0.13%   |
| 4.20.0    | 1         | 0.13%   |
| 4.19.71   | 1         | 0.13%   |
| 4.19.67   | 1         | 0.13%   |
| 4.19.194  | 1         | 0.13%   |
| 3.10.72   | 1         | 0.13%   |
| 3.10.54   | 1         | 0.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.19    | 573       | 71.89%  |
| 5.4     | 42        | 5.27%   |
| 5.10    | 33        | 4.14%   |
| 5.8     | 32        | 4.02%   |
| 5.9     | 26        | 3.26%   |
| 5.7     | 21        | 2.63%   |
| 5.6     | 19        | 2.38%   |
| 5.2     | 14        | 1.76%   |
| 5.5     | 12        | 1.51%   |
| 5.3     | 11        | 1.38%   |
| 4.9     | 5         | 0.63%   |
| 5.0     | 2         | 0.25%   |
| 3.10    | 2         | 0.25%   |
| 5.4.104 | 1         | 0.13%   |
| 5.13    | 1         | 0.13%   |
| 5.12    | 1         | 0.13%   |
| 5.1     | 1         | 0.13%   |
| 4.20    | 1         | 0.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 722       | 93.64%  |
| i686    | 46        | 5.97%   |
| armv7l  | 2         | 0.26%   |
| aarch64 | 1         | 0.13%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 223       | 28.3%   |
| XFCE             | 146       | 18.53%  |
| Unknown          | 101       | 12.82%  |
| KDE              | 75        | 9.52%   |
| KDE5             | 66        | 8.38%   |
| MATE             | 48        | 6.09%   |
| X-Cinnamon       | 30        | 3.81%   |
| LXDE             | 28        | 3.55%   |
| Cinnamon         | 28        | 3.55%   |
| i3               | 14        | 1.78%   |
| LXQt             | 8         | 1.02%   |
| Budgie           | 6         | 0.76%   |
| lightdm-xsession | 4         | 0.51%   |
| Trinity          | 3         | 0.38%   |
| ICEWM            | 1         | 0.13%   |
| i3-gaps          | 1         | 0.13%   |
| GNOME Flashback  | 1         | 0.13%   |
| GNOME Classic    | 1         | 0.13%   |
| Enlightenment    | 1         | 0.13%   |
| DWM              | 1         | 0.13%   |
| default          | 1         | 0.13%   |
| awesome          | 1         | 0.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 596       | 76.02%  |
| Wayland | 127       | 16.2%   |
| Tty     | 37        | 4.72%   |
| Unknown | 24        | 3.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 376       | 48.02%  |
| GDM     | 134       | 17.11%  |
| TDM     | 130       | 16.6%   |
| SDDM    | 83        | 10.6%   |
| LightDM | 42        | 5.36%   |
| XDM     | 5         | 0.64%   |
| GDM3    | 5         | 0.64%   |
| SLiM    | 3         | 0.38%   |
| NODM    | 3         | 0.38%   |
| WDM     | 1         | 0.13%   |
| KDM     | 1         | 0.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 234       | 29.89%  |
| Unknown     | 111       | 14.18%  |
| pt_BR       | 56        | 7.15%   |
| de_DE       | 53        | 6.77%   |
| fr_FR       | 38        | 4.85%   |
| ru_RU       | 37        | 4.73%   |
| it_IT       | 26        | 3.32%   |
| en_GB       | 25        | 3.19%   |
| es_ES       | 21        | 2.68%   |
| es_MX       | 13        | 1.66%   |
| pl_PL       | 12        | 1.53%   |
| es_CL       | 12        | 1.53%   |
| en_CA       | 12        | 1.53%   |
| C           | 11        | 1.4%    |
| pt_PT       | 9         | 1.15%   |
| en_IN       | 8         | 1.02%   |
| de_CH       | 7         | 0.89%   |
| ru_UA       | 6         | 0.77%   |
| en_IE       | 6         | 0.77%   |
| es_AR       | 5         | 0.64%   |
| da_DK       | 5         | 0.64%   |
| cs_CZ       | 5         | 0.64%   |
| zh_CN       | 4         | 0.51%   |
| fi_FI       | 4         | 0.51%   |
| es_VE       | 4         | 0.51%   |
| es_CO       | 4         | 0.51%   |
| en_ZA       | 4         | 0.51%   |
| en_NZ       | 4         | 0.51%   |
| en_AU       | 4         | 0.51%   |
| sk_SK       | 3         | 0.38%   |
| hu_HU       | 3         | 0.38%   |
| fr_CH       | 3         | 0.38%   |
| es_CR       | 3         | 0.38%   |
| sv_SE       | 2         | 0.26%   |
| nl_NL       | 2         | 0.26%   |
| nl_BE       | 2         | 0.26%   |
| ko_KR       | 2         | 0.26%   |
| ja_JP       | 2         | 0.26%   |
| el_GR       | 2         | 0.26%   |
| de_AT       | 2         | 0.26%   |
| uk_UA       | 1         | 0.13%   |
| tr_TR       | 1         | 0.13%   |
| ro_RO       | 1         | 0.13%   |
| lt_LT       | 1         | 0.13%   |
| it_CH       | 1         | 0.13%   |
| hr_HR       | 1         | 0.13%   |
| fr_CA       | 1         | 0.13%   |
| es_PE       | 1         | 0.13%   |
| es_HN       | 1         | 0.13%   |
| es_EC       | 1         | 0.13%   |
| es_BO       | 1         | 0.13%   |
| en_US.utf-8 | 1         | 0.13%   |
| en_PH       | 1         | 0.13%   |
| en_NG       | 1         | 0.13%   |
| en_HK       | 1         | 0.13%   |
| en_DK       | 1         | 0.13%   |
| ca_ES       | 1         | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 507       | 65.08%  |
| EFI  | 272       | 34.92%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 712       | 92.11%  |
| Unknown | 19        | 2.46%   |
| Btrfs   | 17        | 2.2%    |
| Overlay | 7         | 0.91%   |
| Xfs     | 5         | 0.65%   |
| Ext2    | 5         | 0.65%   |
| Rootfs  | 3         | 0.39%   |
| Ext3    | 3         | 0.39%   |
| Zfs     | 1         | 0.13%   |
| Tmpfs   | 1         | 0.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 369       | 47.37%  |
| GPT     | 256       | 32.86%  |
| MBR     | 154       | 19.77%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 687       | 88.65%  |
| Yes       | 88        | 11.35%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 592       | 76.39%  |
| Yes       | 183       | 23.61%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Lenovo                     | 180       | 23.35%  |
| Dell                       | 146       | 18.94%  |
| Hewlett-Packard            | 128       | 16.6%   |
| Acer                       | 79        | 10.25%  |
| ASUSTek Computer           | 74        | 9.6%    |
| Toshiba                    | 22        | 2.85%   |
| Samsung Electronics        | 18        | 2.33%   |
| Sony                       | 16        | 2.08%   |
| Unknown                    | 13        | 1.69%   |
| Apple                      | 12        | 1.56%   |
| MSI                        | 10        | 1.3%    |
| Notebook                   | 7         | 0.91%   |
| Positivo                   | 5         | 0.65%   |
| Intel                      | 4         | 0.52%   |
| Fujitsu                    | 4         | 0.52%   |
| Alienware                  | 4         | 0.52%   |
| Timi                       | 3         | 0.39%   |
| Medion                     | 3         | 0.39%   |
| TQ-Group                   | 2         | 0.26%   |
| Purism                     | 2         | 0.26%   |
| Panasonic                  | 2         | 0.26%   |
| Packard Bell               | 2         | 0.26%   |
| LG Electronics             | 2         | 0.26%   |
| IBM                        | 2         | 0.26%   |
| Google                     | 2         | 0.26%   |
| DNS                        | 2         | 0.26%   |
| VIT                        | 1         | 0.13%   |
| ViewSonic                  | 1         | 0.13%   |
| TUXEDO                     | 1         | 0.13%   |
| SLIMBOOK                   | 1         | 0.13%   |
| RM                         | 1         | 0.13%   |
| Razer                      | 1         | 0.13%   |
| Positivo Bahia - VAIO      | 1         | 0.13%   |
| Pine Microsystems          | 1         | 0.13%   |
| PC Specialist              | 1         | 0.13%   |
| One Education              | 1         | 0.13%   |
| OEM                        | 1         | 0.13%   |
| NEC Computers              | 1         | 0.13%   |
| Itautec                    | 1         | 0.13%   |
| HKC                        | 1         | 0.13%   |
| HDC High Designed Computer | 1         | 0.13%   |
| HASEE Computer             | 1         | 0.13%   |
| GTZS                       | 1         | 0.13%   |
| GPD                        | 1         | 0.13%   |
| Gateway                    | 1         | 0.13%   |
| Fujitsu Siemens            | 1         | 0.13%   |
| eMachines                  | 1         | 0.13%   |
| DataLogic                  | 1         | 0.13%   |
| Corporativo Lanix          | 1         | 0.13%   |
| Compaq                     | 1         | 0.13%   |
| Compal                     | 1         | 0.13%   |
| AWOW                       | 1         | 0.13%   |
| AMI                        | 1         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 15        | 1.95%   |
| HP Pavilion Notebook                     | 4         | 0.52%   |
| Dell XPS 13 9360                         | 4         | 0.52%   |
| Lenovo ThinkPad E480 20KN003WUS          | 3         | 0.39%   |
| Lenovo IdeaPad 330-15IKB 81FE            | 3         | 0.39%   |
| Lenovo IdeaPad 110-15IBR 80T7            | 3         | 0.39%   |
| HP Stream Notebook PC 13                 | 3         | 0.39%   |
| HP ProBook 4540s                         | 3         | 0.39%   |
| HP Pavilion g4                           | 3         | 0.39%   |
| HP Notebook                              | 3         | 0.39%   |
| HP EliteBook 850 G5                      | 3         | 0.39%   |
| HP 2000                                  | 3         | 0.39%   |
| Dell Precision 5530                      | 3         | 0.39%   |
| Dell Latitude E7450                      | 3         | 0.39%   |
| Dell Latitude E6430                      | 3         | 0.39%   |
| Dell Latitude E5520                      | 3         | 0.39%   |
| Dell Latitude 5500                       | 3         | 0.39%   |
| Dell Inspiron 1545                       | 3         | 0.39%   |
| Apple MacBookPro11,3                     | 3         | 0.39%   |
| Acer Aspire E5-575G                      | 3         | 0.39%   |
| TQ-Group TQMxE39S                        | 2         | 0.26%   |
| Timi TM1701                              | 2         | 0.26%   |
| Samsung 305E4A/305E5A/305E7A             | 2         | 0.26%   |
| Positivo MOBILE                          | 2         | 0.26%   |
| Lenovo Y50-70 20378                      | 2         | 0.26%   |
| Lenovo V340-17IWL 81RG                   | 2         | 0.26%   |
| Lenovo ThinkPad X230 23252EG             | 2         | 0.26%   |
| Lenovo ThinkPad X1 Carbon 7th 20QDCTO1WW | 2         | 0.26%   |
| Lenovo Legion Y530-15ICH-1060 81LB       | 2         | 0.26%   |
| Lenovo Legion Y530-15ICH 81FV            | 2         | 0.26%   |
| Lenovo IdeaPad 330S-15IKB 81F5           | 2         | 0.26%   |
| Intel Intel powered classmate PC         | 2         | 0.26%   |
| HP ProBook 6460b                         | 2         | 0.26%   |
| HP ProBook 450 G6                        | 2         | 0.26%   |
| HP Presario CQ57                         | 2         | 0.26%   |
| HP Pavilion g6                           | 2         | 0.26%   |
| HP Laptop 15-bs0xx                       | 2         | 0.26%   |
| HP EliteBook 840 G1                      | 2         | 0.26%   |
| HP EliteBook 830 G7 Notebook PC          | 2         | 0.26%   |
| HP EliteBook 820 G1                      | 2         | 0.26%   |
| HP EliteBook 6930p                       | 2         | 0.26%   |
| HP 250 G7 Notebook PC                    | 2         | 0.26%   |
| HP 15                                    | 2         | 0.26%   |
| Dell XPS 13 9310                         | 2         | 0.26%   |
| Dell Vostro 3560                         | 2         | 0.26%   |
| Dell Vostro 3550                         | 2         | 0.26%   |
| Dell Precision M4600                     | 2         | 0.26%   |
| Dell Latitude E7470                      | 2         | 0.26%   |
| Dell Latitude E7440                      | 2         | 0.26%   |
| Dell Latitude E7250                      | 2         | 0.26%   |
| Dell Latitude E7240                      | 2         | 0.26%   |
| Dell Latitude E6420                      | 2         | 0.26%   |
| Dell Latitude 7490                       | 2         | 0.26%   |
| Dell Latitude 7400                       | 2         | 0.26%   |
| Dell Inspiron N5050                      | 2         | 0.26%   |
| Dell Inspiron 7559                       | 2         | 0.26%   |
| Dell Inspiron 7520                       | 2         | 0.26%   |
| Dell Inspiron 5570                       | 2         | 0.26%   |
| Dell Inspiron 5567                       | 2         | 0.26%   |
| Dell Inspiron 5558                       | 2         | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 112       | 14.53%  |
| Dell Latitude      | 54        | 7%      |
| Dell Inspiron      | 54        | 7%      |
| Acer Aspire        | 52        | 6.74%   |
| Lenovo IdeaPad     | 35        | 4.54%   |
| HP EliteBook       | 26        | 3.37%   |
| HP ProBook         | 24        | 3.11%   |
| HP Pavilion        | 20        | 2.59%   |
| Toshiba Satellite  | 16        | 2.08%   |
| Unknown            | 15        | 1.95%   |
| Dell Precision     | 13        | 1.69%   |
| Dell Vostro        | 12        | 1.56%   |
| HP Laptop          | 11        | 1.43%   |
| Dell XPS           | 10        | 1.3%    |
| ASUS VivoBook      | 9         | 1.17%   |
| Acer Swift         | 6         | 0.78%   |
| Lenovo Legion      | 5         | 0.65%   |
| HP Compaq          | 5         | 0.65%   |
| HP ZBook           | 4         | 0.52%   |
| HP Presario        | 4         | 0.52%   |
| HP ENVY            | 4         | 0.52%   |
| HP 250             | 4         | 0.52%   |
| Acer Nitro         | 4         | 0.52%   |
| Acer Extensa       | 4         | 0.52%   |
| Toshiba PORTEGE    | 3         | 0.39%   |
| HP Stream          | 3         | 0.39%   |
| HP Notebook        | 3         | 0.39%   |
| HP 2000            | 3         | 0.39%   |
| HP 15              | 3         | 0.39%   |
| Fujitsu LIFEBOOK   | 3         | 0.39%   |
| Apple MacBookPro11 | 3         | 0.39%   |
| Alienware 17       | 3         | 0.39%   |
| TQ-Group TQMxE39S  | 2         | 0.26%   |
| Toshiba TECRA      | 2         | 0.26%   |
| Timi TM1701        | 2         | 0.26%   |
| Samsung 305E4A     | 2         | 0.26%   |
| Purism Librem      | 2         | 0.26%   |
| Positivo MOBILE    | 2         | 0.26%   |
| Lenovo Yoga        | 2         | 0.26%   |
| Lenovo Y50-70      | 2         | 0.26%   |
| Lenovo V340-17IWL  | 2         | 0.26%   |
| Lenovo ThinkBook   | 2         | 0.26%   |
| Lenovo G570        | 2         | 0.26%   |
| Lenovo G50-80      | 2         | 0.26%   |
| Intel Intel        | 2         | 0.26%   |
| IBM ThinkPad       | 2         | 0.26%   |
| HP OMEN            | 2         | 0.26%   |
| HP Mini            | 2         | 0.26%   |
| Dell Studio        | 2         | 0.26%   |
| ASUS ZenBook       | 2         | 0.26%   |
| ASUS X450LN        | 2         | 0.26%   |
| ASUS X406UAR       | 2         | 0.26%   |
| ASUS UX550VE       | 2         | 0.26%   |
| ASUS TUF           | 2         | 0.26%   |
| ASUS S551LN        | 2         | 0.26%   |
| ASUS ROG           | 2         | 0.26%   |
| ASUS K52F          | 2         | 0.26%   |
| ASUS K46CB         | 2         | 0.26%   |
| Acer TravelMate    | 2         | 0.26%   |
| Acer AO722         | 2         | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 131       | 16.99%  |
| 2020    | 96        | 12.45%  |
| 2018    | 88        | 11.41%  |
| 2013    | 56        | 7.26%   |
| 2011    | 55        | 7.13%   |
| 2012    | 54        | 7%      |
| 2017    | 50        | 6.49%   |
| 2015    | 44        | 5.71%   |
| 2014    | 40        | 5.19%   |
| 2009    | 36        | 4.67%   |
| 2010    | 35        | 4.54%   |
| 2016    | 32        | 4.15%   |
| 2008    | 18        | 2.33%   |
| 2021    | 15        | 1.95%   |
| 2007    | 7         | 0.91%   |
| Unknown | 5         | 0.65%   |
| 2006    | 3         | 0.39%   |
| 2005    | 3         | 0.39%   |
| 2004    | 1         | 0.13%   |
| 2003    | 1         | 0.13%   |
| 2002    | 1         | 0.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 771       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 737       | 95.47%  |
| Enabled  | 35        | 4.53%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 766       | 99.22%  |
| Yes  | 6         | 0.78%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 196       | 25.19%  |
| 3.01-4.0   | 163       | 20.95%  |
| 8.01-16.0  | 155       | 19.92%  |
| 16.01-24.0 | 135       | 17.35%  |
| 1.01-2.0   | 52        | 6.68%   |
| 32.01-64.0 | 36        | 4.63%   |
| 2.01-3.0   | 17        | 2.19%   |
| 0.51-1.0   | 11        | 1.41%   |
| 24.01-32.0 | 7         | 0.9%    |
| 0.01-0.5   | 5         | 0.64%   |
| Unknown    | 1         | 0.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 279       | 33.74%  |
| 2.01-3.0   | 205       | 24.79%  |
| 4.01-8.0   | 116       | 14.03%  |
| 3.01-4.0   | 95        | 11.49%  |
| 0.51-1.0   | 76        | 9.19%   |
| 8.01-16.0  | 31        | 3.75%   |
| 0.01-0.5   | 19        | 2.3%    |
| 16.01-24.0 | 3         | 0.36%   |
| Unknown    | 3         | 0.36%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 563       | 71.99%  |
| 2      | 183       | 23.4%   |
| 3      | 30        | 3.84%   |
| 4      | 2         | 0.26%   |
| 0      | 2         | 0.26%   |
| 7      | 1         | 0.13%   |
| 5      | 1         | 0.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 476       | 61.58%  |
| Yes       | 297       | 38.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 685       | 88.73%  |
| No        | 87        | 11.27%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 751       | 97.28%  |
| No        | 21        | 2.72%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 562       | 72.42%  |
| No        | 214       | 27.58%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 92        | 11.89%  |
| Brazil       | 76        | 9.82%   |
| Germany      | 71        | 9.17%   |
| Russia       | 59        | 7.62%   |
| France       | 56        | 7.24%   |
| Italy        | 40        | 5.17%   |
| Spain        | 33        | 4.26%   |
| Switzerland  | 23        | 2.97%   |
| Ukraine      | 18        | 2.33%   |
| Poland       | 17        | 2.2%    |
| Portugal     | 16        | 2.07%   |
| Mexico       | 15        | 1.94%   |
| Chile        | 15        | 1.94%   |
| UK           | 14        | 1.81%   |
| India        | 13        | 1.68%   |
| Canada       | 13        | 1.68%   |
| Netherlands  | 10        | 1.29%   |
| Greece       | 10        | 1.29%   |
| Hungary      | 9         | 1.16%   |
| China        | 8         | 1.03%   |
| Argentina    | 8         | 1.03%   |
| Ireland      | 7         | 0.9%    |
| Denmark      | 7         | 0.9%    |
| Czechia      | 7         | 0.9%    |
| New Zealand  | 6         | 0.78%   |
| Finland      | 6         | 0.78%   |
| Belgium      | 6         | 0.78%   |
| Vietnam      | 5         | 0.65%   |
| Venezuela    | 5         | 0.65%   |
| Turkey       | 5         | 0.65%   |
| Thailand     | 5         | 0.65%   |
| Sweden       | 5         | 0.65%   |
| Romania      | 5         | 0.65%   |
| Norway       | 5         | 0.65%   |
| Indonesia    | 5         | 0.65%   |
| Colombia     | 5         | 0.65%   |
| Australia    | 5         | 0.65%   |
| South Africa | 4         | 0.52%   |
| Slovakia     | 4         | 0.52%   |
| Bulgaria     | 4         | 0.52%   |
| Tunisia      | 3         | 0.39%   |
| Peru         | 3         | 0.39%   |
| Belarus      | 3         | 0.39%   |
| Austria      | 3         | 0.39%   |
| South Korea  | 2         | 0.26%   |
| Lithuania    | 2         | 0.26%   |
| Latvia       | 2         | 0.26%   |
| Kazakhstan   | 2         | 0.26%   |
| Japan        | 2         | 0.26%   |
| Iran         | 2         | 0.26%   |
| Guatemala    | 2         | 0.26%   |
| El Salvador  | 2         | 0.26%   |
| Croatia      | 2         | 0.26%   |
| Costa Rica   | 2         | 0.26%   |
| Slovenia     | 1         | 0.13%   |
| Singapore    | 1         | 0.13%   |
| Puerto Rico  | 1         | 0.13%   |
| Philippines  | 1         | 0.13%   |
| Nigeria      | 1         | 0.13%   |
| Nepal        | 1         | 0.13%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| St Petersburg         | 16        | 1.99%   |
| Moscow                | 13        | 1.61%   |
| São Paulo            | 10        | 1.24%   |
| Madrid                | 8         | 0.99%   |
| Berlin                | 8         | 0.99%   |
| Paris                 | 7         | 0.87%   |
| Milan                 | 7         | 0.87%   |
| Zurich                | 6         | 0.74%   |
| Wooster               | 6         | 0.74%   |
| Santiago              | 6         | 0.74%   |
| Rome                  | 6         | 0.74%   |
| Mesa                  | 6         | 0.74%   |
| Hamburg               | 6         | 0.74%   |
| Belo Horizonte        | 6         | 0.74%   |
| Athens                | 6         | 0.74%   |
| Rio de Janeiro        | 5         | 0.62%   |
| New York              | 5         | 0.62%   |
| Lisbon                | 5         | 0.62%   |
| Helsinki              | 5         | 0.62%   |
| Curitiba              | 5         | 0.62%   |
| Budapest              | 5         | 0.62%   |
| Warsaw                | 4         | 0.5%    |
| Sofia                 | 4         | 0.5%    |
| Prague                | 4         | 0.5%    |
| Naas                  | 4         | 0.5%    |
| Brasília             | 4         | 0.5%    |
| Amsterdam             | 4         | 0.5%    |
| Vogue                 | 3         | 0.37%   |
| Vienna                | 3         | 0.37%   |
| Valencia              | 3         | 0.37%   |
| Thessaloniki          | 3         | 0.37%   |
| Salvador              | 3         | 0.37%   |
| Porto Alegre          | 3         | 0.37%   |
| Porto                 | 3         | 0.37%   |
| Mumbai                | 3         | 0.37%   |
| Mexico City           | 3         | 0.37%   |
| Lima                  | 3         | 0.37%   |
| Kyiv                  | 3         | 0.37%   |
| Johannesburg          | 3         | 0.37%   |
| Dublin                | 3         | 0.37%   |
| Cologne               | 3         | 0.37%   |
| Bucharest             | 3         | 0.37%   |
| Bengaluru             | 3         | 0.37%   |
| Auckland              | 3         | 0.37%   |
| Zagreb                | 2         | 0.25%   |
| Yssingeaux            | 2         | 0.25%   |
| Yekaterinburg         | 2         | 0.25%   |
| Windsor               | 2         | 0.25%   |
| Wilderness Rim        | 2         | 0.25%   |
| Voronezh              | 2         | 0.25%   |
| Vernon                | 2         | 0.25%   |
| Vasylkiv              | 2         | 0.25%   |
| Uerikon               | 2         | 0.25%   |
| Turin                 | 2         | 0.25%   |
| Tunis                 | 2         | 0.25%   |
| Tomsk                 | 2         | 0.25%   |
| Therwil               | 2         | 0.25%   |
| São José dos Campos | 2         | 0.25%   |
| Stuttgart             | 2         | 0.25%   |
| St Louis              | 2         | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 142       | 169    | 14.48%  |
| WDC                       | 137       | 154    | 13.97%  |
| Seagate                   | 129       | 164    | 13.15%  |
| Toshiba                   | 87        | 101    | 8.87%   |
| Unknown                   | 60        | 81     | 6.12%   |
| SanDisk                   | 57        | 63     | 5.81%   |
| Kingston                  | 56        | 64     | 5.71%   |
| Crucial                   | 44        | 53     | 4.49%   |
| Hitachi                   | 39        | 43     | 3.98%   |
| SK Hynix                  | 28        | 37     | 2.85%   |
| HGST                      | 26        | 29     | 2.65%   |
| Intel                     | 16        | 17     | 1.63%   |
| A-DATA Technology         | 14        | 17     | 1.43%   |
| Micron Technology         | 13        | 14     | 1.33%   |
| Fujitsu                   | 9         | 10     | 0.92%   |
| Transcend                 | 6         | 6      | 0.61%   |
| OCZ                       | 6         | 7      | 0.61%   |
| LDLC                      | 6         | 6      | 0.61%   |
| Team                      | 5         | 6      | 0.51%   |
| Silicon Motion            | 5         | 5      | 0.51%   |
| Phison                    | 5         | 8      | 0.51%   |
| Patriot                   | 5         | 7      | 0.51%   |
| Micron/Crucial Technology | 5         | 5      | 0.51%   |
| LITEON                    | 5         | 5      | 0.51%   |
| Intenso                   | 5         | 7      | 0.51%   |
| China                     | 5         | 5      | 0.51%   |
| Apple                     | 5         | 5      | 0.51%   |
| PNY                       | 4         | 6      | 0.41%   |
| KingSpec                  | 3         | 3      | 0.31%   |
| KingDian                  | 3         | 3      | 0.31%   |
| Hewlett-Packard           | 3         | 3      | 0.31%   |
| Super Talent              | 2         | 3      | 0.2%    |
| LITEONIT                  | 2         | 2      | 0.2%    |
| KIOXIA                    | 2         | 2      | 0.2%    |
| KingFast                  | 2         | 2      | 0.2%    |
| JMicron                   | 2         | 2      | 0.2%    |
| GOODRAM                   | 2         | 2      | 0.2%    |
| Gigabyte Technology       | 2         | 2      | 0.2%    |
| BIWIN                     | 2         | 2      | 0.2%    |
| ASMT                      | 2         | 8      | 0.2%    |
| AMD                       | 2         | 2      | 0.2%    |
| XPG                       | 1         | 4      | 0.1%    |
| Union Memory              | 1         | 1      | 0.1%    |
| TurXun                    | 1         | 1      | 0.1%    |
| TO Exter                  | 1         | 1      | 0.1%    |
| TAMMUZ                    | 1         | 2      | 0.1%    |
| SPCC                      | 1         | 1      | 0.1%    |
| SNR-ML                    | 1         | 1      | 0.1%    |
| Smartbuy                  | 1         | 1      | 0.1%    |
| SILICONMOTION             | 1         | 1      | 0.1%    |
| QNAP                      | 1         | 2      | 0.1%    |
| PLEXTOR                   | 1         | 1      | 0.1%    |
| Phison Electronics        | 1         | 1      | 0.1%    |
| PHD 3.0                   | 1         | 1      | 0.1%    |
| PALIT                     | 1         | 1      | 0.1%    |
| ORICO                     | 1         | 1      | 0.1%    |
| Leven                     | 1         | 1      | 0.1%    |
| Lenovo                    | 1         | 1      | 0.1%    |
| Kingchuxing               | 1         | 1      | 0.1%    |
| HUAWEI                    | 1         | 1      | 0.1%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB        | 17        | 1.7%    |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 17        | 1.7%    |
| Kingston SA400S37240G 240GB SSD       | 17        | 1.7%    |
| Toshiba MQ01ABD100 1TB                | 15        | 1.5%    |
| HGST HTS721010A9E630 1TB              | 15        | 1.5%    |
| Unknown MMC Card  32GB                | 11        | 1.1%    |
| Crucial CT500MX500SSD1 500GB          | 11        | 1.1%    |
| Samsung SSD 850 EVO 250GB             | 10        | 1%      |
| Unknown MMC Card  64GB                | 9         | 0.9%    |
| Kingston SA400S37120G 120GB SSD       | 9         | 0.9%    |
| WDC WD10SPZX-21Z10T0 1TB              | 8         | 0.8%    |
| Seagate ST500LT012-1DG142 500GB       | 8         | 0.8%    |
| Seagate ST500LM012 HN-M500MBB 500GB   | 8         | 0.8%    |
| Toshiba MQ04ABF100 1TB                | 6         | 0.6%    |
| Toshiba MQ01ABF050 500GB              | 6         | 0.6%    |
| Seagate ST9500325AS 500GB             | 6         | 0.6%    |
| SanDisk SSD PLUS 240GB                | 6         | 0.6%    |
| Samsung SSD 860 EVO 250GB             | 6         | 0.6%    |
| Crucial CT240BX500SSD1 240GB          | 6         | 0.6%    |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 5         | 0.5%    |
| WDC WD10SPZX-24Z10 1TB                | 5         | 0.5%    |
| WDC PC SN730 SDBQNTY-512G-1001 512GB  | 5         | 0.5%    |
| Toshiba NVMe SSD Drive 256GB          | 5         | 0.5%    |
| Seagate ST2000LM015-2E8174 2TB        | 5         | 0.5%    |
| Seagate ST1000LM049-2GH172 1TB        | 5         | 0.5%    |
| Samsung SSD 860 EVO 500GB             | 5         | 0.5%    |
| Samsung NVMe SSD Drive 256GB          | 5         | 0.5%    |
| Samsung MZVLB512HBJQ-000L7 512GB      | 5         | 0.5%    |
| Kingston SA400S37480G 480GB SSD       | 5         | 0.5%    |
| Hitachi HTS547550A9E384 500GB         | 5         | 0.5%    |
| WDC WD5000LPVX-22V0TT0 500GB          | 4         | 0.4%    |
| WDC WD5000LPCX-21VHAT0 500GB          | 4         | 0.4%    |
| WDC WD10JPVX-22JC3T0 1TB              | 4         | 0.4%    |
| WDC WD10JPCX-24UE4T0 1TB              | 4         | 0.4%    |
| SK Hynix HFS256G39TND-N210A 256GB SSD | 4         | 0.4%    |
| Seagate ST9250315AS 250GB             | 4         | 0.4%    |
| Seagate ST500LT012-9WS142 500GB       | 4         | 0.4%    |
| Seagate ST1000LM048-2E7172 1TB        | 4         | 0.4%    |
| Seagate Expansion+ 1TB                | 4         | 0.4%    |
| SanDisk SSD PLUS 120GB                | 4         | 0.4%    |
| Samsung SSD 860 QVO 1TB               | 4         | 0.4%    |
| Samsung NVMe SSD Drive 512GB          | 4         | 0.4%    |
| Phison NVMe SSD Drive 1024GB          | 4         | 0.4%    |
| Patriot Burst 240GB SSD               | 4         | 0.4%    |
| Micron/Crucial NVMe SSD Drive 500GB   | 4         | 0.4%    |
| Kingston SUV400S37240G 240GB SSD      | 4         | 0.4%    |
| WDC WD5000LPCX-24VHAT0 500GB          | 3         | 0.3%    |
| WDC WD10SPZX-24Z10T0 1TB              | 3         | 0.3%    |
| WDC PC SN720 SDAQNTW-512G-1001 512GB  | 3         | 0.3%    |
| WDC PC SN520 SDAPMUW-512G-1101 512GB  | 3         | 0.3%    |
| Unknown MMC Card  2GB                 | 3         | 0.3%    |
| Unknown MMC Card  16GB                | 3         | 0.3%    |
| Toshiba MQ01ACF050 500GB              | 3         | 0.3%    |
| Toshiba MQ01ABD050 500GB              | 3         | 0.3%    |
| SK Hynix HCG8e  64GB                  | 3         | 0.3%    |
| SK Hynix HBG4e  32GB                  | 3         | 0.3%    |
| Seagate ST9500420AS 500GB             | 3         | 0.3%    |
| Seagate ST2000LX001-1RG174 2TB        | 3         | 0.3%    |
| SanDisk SSD U100 24GB                 | 3         | 0.3%    |
| SanDisk SDSSDA120G 120GB              | 3         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 125       | 158    | 33.42%  |
| WDC                 | 95        | 104    | 25.4%   |
| Toshiba             | 58        | 65     | 15.51%  |
| Hitachi             | 39        | 43     | 10.43%  |
| HGST                | 26        | 29     | 6.95%   |
| Samsung Electronics | 11        | 11     | 2.94%   |
| Fujitsu             | 9         | 10     | 2.41%   |
| Unknown             | 2         | 2      | 0.53%   |
| Intenso             | 2         | 2      | 0.53%   |
| TO Exter            | 1         | 1      | 0.27%   |
| SILICONMOTION       | 1         | 1      | 0.27%   |
| QNAP                | 1         | 2      | 0.27%   |
| PHD 3.0             | 1         | 1      | 0.27%   |
| Hewlett-Packard     | 1         | 1      | 0.27%   |
| ASMT                | 1         | 7      | 0.27%   |
| Apple               | 1         | 1      | 0.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 88        | 100    | 23.66%  |
| Kingston            | 49        | 57     | 13.17%  |
| SanDisk             | 45        | 50     | 12.1%   |
| Crucial             | 44        | 53     | 11.83%  |
| WDC                 | 19        | 23     | 5.11%   |
| A-DATA Technology   | 12        | 15     | 3.23%   |
| SK Hynix            | 10        | 11     | 2.69%   |
| Micron Technology   | 10        | 11     | 2.69%   |
| Intel               | 7         | 8      | 1.88%   |
| Toshiba             | 6         | 7      | 1.61%   |
| OCZ                 | 6         | 7      | 1.61%   |
| Transcend           | 5         | 5      | 1.34%   |
| Team                | 5         | 6      | 1.34%   |
| Patriot             | 5         | 7      | 1.34%   |
| LITEON              | 5         | 5      | 1.34%   |
| LDLC                | 5         | 5      | 1.34%   |
| China               | 5         | 5      | 1.34%   |
| Apple               | 4         | 4      | 1.08%   |
| PNY                 | 3         | 5      | 0.81%   |
| KingSpec            | 3         | 3      | 0.81%   |
| KingDian            | 3         | 3      | 0.81%   |
| Seagate             | 2         | 2      | 0.54%   |
| LITEONIT            | 2         | 2      | 0.54%   |
| Intenso             | 2         | 3      | 0.54%   |
| Hewlett-Packard     | 2         | 2      | 0.54%   |
| GOODRAM             | 2         | 2      | 0.54%   |
| Gigabyte Technology | 2         | 2      | 0.54%   |
| BIWIN               | 2         | 2      | 0.54%   |
| AMD                 | 2         | 2      | 0.54%   |
| TurXun              | 1         | 1      | 0.27%   |
| TAMMUZ              | 1         | 2      | 0.27%   |
| SPCC                | 1         | 1      | 0.27%   |
| SNR-ML              | 1         | 1      | 0.27%   |
| Smartbuy            | 1         | 1      | 0.27%   |
| PLEXTOR             | 1         | 1      | 0.27%   |
| PALIT               | 1         | 1      | 0.27%   |
| ORICO               | 1         | 1      | 0.27%   |
| Leven               | 1         | 1      | 0.27%   |
| Lenovo              | 1         | 1      | 0.27%   |
| Kingchuxing         | 1         | 1      | 0.27%   |
| JMicron             | 1         | 1      | 0.27%   |
| Dogfish             | 1         | 3      | 0.27%   |
| CIE                 | 1         | 1      | 0.27%   |
| ASUS-PHISON         | 1         | 1      | 0.27%   |
| ASUS-JM             | 1         | 1      | 0.27%   |
| ASMT                | 1         | 1      | 0.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 361       | 438    | 38.32%  |
| SSD     | 350       | 427    | 37.15%  |
| NVMe    | 151       | 195    | 16.03%  |
| MMC     | 64        | 85     | 6.79%   |
| Unknown | 16        | 20     | 1.7%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 633       | 840    | 72.01%  |
| NVMe | 151       | 195    | 17.18%  |
| MMC  | 64        | 85     | 7.28%   |
| SAS  | 31        | 45     | 3.53%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 474       | 589    | 68.2%   |
| 0.51-1.0   | 198       | 238    | 28.49%  |
| 1.01-2.0   | 17        | 24     | 2.45%   |
| 4.01-10.0  | 4         | 12     | 0.58%   |
| 3.01-4.0   | 2         | 2      | 0.29%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 266       | 33.54%  |
| 251-500        | 187       | 23.58%  |
| 501-1000       | 114       | 14.38%  |
| 51-100         | 75        | 9.46%   |
| 1001-2000      | 47        | 5.93%   |
| 21-50          | 33        | 4.16%   |
| Unknown        | 33        | 4.16%   |
| 1-20           | 16        | 2.02%   |
| 2001-3000      | 12        | 1.51%   |
| More than 3000 | 10        | 1.26%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 255       | 30.8%   |
| 21-50          | 155       | 18.72%  |
| 101-250        | 150       | 18.12%  |
| 51-100         | 107       | 12.92%  |
| 251-500        | 67        | 8.09%   |
| 501-1000       | 40        | 4.83%   |
| Unknown        | 33        | 3.99%   |
| 1001-2000      | 14        | 1.69%   |
| More than 3000 | 3         | 0.36%   |
| 2001-3000      | 3         | 0.36%   |
| 0              | 1         | 0.12%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                         | 3         | 3      | 3.75%   |
| Seagate ST1000LM035-1RK172 1TB                 | 3         | 3      | 3.75%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 3         | 4      | 3.75%   |
| Toshiba MQ01ACF050 500GB                       | 2         | 2      | 2.5%    |
| Seagate ST9250315AS 250GB                      | 2         | 2      | 2.5%    |
| Seagate ST500LT012-9WS142 500GB                | 2         | 2      | 2.5%    |
| Hitachi HTS547550A9E384 500GB                  | 2         | 2      | 2.5%    |
| WDC WDS120G2G0A-00JH30 120GB SSD               | 1         | 1      | 1.25%   |
| WDC WD7500BPVX-22JC3T0 752GB                   | 1         | 1      | 1.25%   |
| WDC WD7500BPKT-75PK4T0 752GB                   | 1         | 1      | 1.25%   |
| WDC WD3200BPVT-00JJ5T0 320GB                   | 1         | 1      | 1.25%   |
| WDC WD3200BEVT-22A23T0 320GB                   | 1         | 1      | 1.25%   |
| WDC WD10JUCT-63CYNY0 1TB                       | 1         | 1      | 1.25%   |
| Toshiba MQ04ABF100 1TB                         | 1         | 1      | 1.25%   |
| Toshiba MQ01ABF050H 500GB                      | 1         | 1      | 1.25%   |
| Toshiba MQ01ABF050 500GB                       | 1         | 1      | 1.25%   |
| Toshiba MK3259GSXP 320GB                       | 1         | 1      | 1.25%   |
| Toshiba MK1637GSX 160GB                        | 1         | 1      | 1.25%   |
| Team L5 LITE SSD 60GB                          | 1         | 1      | 1.25%   |
| SK Hynix SC311 SATA 256GB SSD                  | 1         | 1      | 1.25%   |
| SK Hynix HFS256G39MND-2300A 256GB SSD          | 1         | 1      | 1.25%   |
| Seagate ST9808210A 80GB                        | 1         | 1      | 1.25%   |
| Seagate ST9500420AS 500GB                      | 1         | 1      | 1.25%   |
| Seagate ST9500325AS 500GB                      | 1         | 1      | 1.25%   |
| Seagate ST9320325AS 320GB                      | 1         | 1      | 1.25%   |
| Seagate ST9160412AS 160GB                      | 1         | 1      | 1.25%   |
| Seagate ST9120822AS 120GB                      | 1         | 1      | 1.25%   |
| Seagate ST500LM021-1KJ152 500GB                | 1         | 1      | 1.25%   |
| Seagate ST500LM000-SSHD-8GB                    | 1         | 1      | 1.25%   |
| Seagate ST320LT020-9YG142 320GB                | 1         | 1      | 1.25%   |
| Seagate ST320LT007-9ZV142 320GB                | 1         | 1      | 1.25%   |
| SanDisk SSD PLUS 240GB                         | 1         | 1      | 1.25%   |
| SanDisk SDSSDX240GG25 240GB                    | 1         | 1      | 1.25%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD            | 1         | 1      | 1.25%   |
| SanDisk SD8SN8U-128G-1006 128GB SSD            | 1         | 1      | 1.25%   |
| Samsung Electronics SSD 860 EVO 500GB          | 1         | 1      | 1.25%   |
| Samsung Electronics SSD 840 PRO Series 256GB   | 1         | 1      | 1.25%   |
| Samsung Electronics HM251HI 250GB              | 1         | 1      | 1.25%   |
| Samsung Electronics HM160HI 160GB              | 1         | 1      | 1.25%   |
| Samsung Electronics HM120JC 120GB              | 1         | 1      | 1.25%   |
| Samsung Electronics HM080HI 80GB               | 1         | 1      | 1.25%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 1.25%   |
| Kingston SA400S37240G 240GB SSD                | 1         | 1      | 1.25%   |
| Kingston SA400S37120G 120GB SSD                | 1         | 2      | 1.25%   |
| KingSpec Q-90 90GB SSD                         | 1         | 1      | 1.25%   |
| KingDian S200 60GB                             | 1         | 1      | 1.25%   |
| Intel SSDSC2KF256H6 SATA 256GB                 | 1         | 1      | 1.25%   |
| Hitachi HTS727550A9E364 500GB                  | 1         | 1      | 1.25%   |
| Hitachi HTS725050A9A364 500GB                  | 1         | 1      | 1.25%   |
| Hitachi HTS721080G9SA00 80GB                   | 1         | 1      | 1.25%   |
| Hitachi HTS547575A9E384 752GB                  | 1         | 1      | 1.25%   |
| Hitachi HTS545050B9A300 500GB                  | 1         | 1      | 1.25%   |
| Hitachi HTS545025B9SA02 250GB                  | 1         | 1      | 1.25%   |
| Hitachi HTS545016B9A300 160GB                  | 1         | 1      | 1.25%   |
| Hitachi HTS543232A7A384 320GB                  | 1         | 1      | 1.25%   |
| Hitachi HTS543216L9SA00 160GB                  | 1         | 1      | 1.25%   |
| Hitachi HTS543216L9A300 160GB                  | 1         | 1      | 1.25%   |
| Hitachi HTS542512K9A300 120GB                  | 1         | 1      | 1.25%   |
| Hitachi HTS541680J9SA00 80GB                   | 1         | 1      | 1.25%   |
| Hitachi HTS541040G9AT00 37GB                   | 1         | 1      | 1.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 21     | 25%     |
| Hitachi             | 16        | 16     | 20%     |
| Toshiba             | 10        | 10     | 12.5%   |
| WDC                 | 6         | 6      | 7.5%    |
| Samsung Electronics | 6         | 6      | 7.5%    |
| SanDisk             | 4         | 4      | 5%      |
| Fujitsu             | 4         | 4      | 5%      |
| SK Hynix            | 2         | 2      | 2.5%    |
| Kingston            | 2         | 3      | 2.5%    |
| A-DATA Technology   | 2         | 2      | 2.5%    |
| Team                | 1         | 1      | 1.25%   |
| Micron Technology   | 1         | 1      | 1.25%   |
| KingSpec            | 1         | 1      | 1.25%   |
| KingDian            | 1         | 1      | 1.25%   |
| Intel               | 1         | 1      | 1.25%   |
| HGST                | 1         | 1      | 1.25%   |
| Crucial             | 1         | 1      | 1.25%   |
| Apple               | 1         | 1      | 1.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 21     | 33.33%  |
| Hitachi             | 16        | 16     | 26.67%  |
| Toshiba             | 10        | 10     | 16.67%  |
| WDC                 | 5         | 5      | 8.33%   |
| Samsung Electronics | 4         | 4      | 6.67%   |
| Fujitsu             | 4         | 4      | 6.67%   |
| HGST                | 1         | 1      | 1.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 58        | 61     | 74.36%  |
| SSD  | 20        | 21     | 25.64%  |

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
| Detected | 421       | 659    | 50%     |
| Works    | 343       | 424    | 40.74%  |
| Malfunc  | 78        | 82     | 9.26%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 615       | 73.48%  |
| AMD                              | 60        | 7.17%   |
| Samsung Electronics              | 51        | 6.09%   |
| Sandisk                          | 30        | 3.58%   |
| Toshiba America Info Systems     | 22        | 2.63%   |
| SK Hynix                         | 12        | 1.43%   |
| Phison Electronics               | 7         | 0.84%   |
| Kingston Technology Company      | 7         | 0.84%   |
| Silicon Motion                   | 6         | 0.72%   |
| Micron/Crucial Technology        | 5         | 0.6%    |
| Nvidia                           | 4         | 0.48%   |
| ADATA Technology                 | 4         | 0.48%   |
| Silicon Integrated Systems [SiS] | 3         | 0.36%   |
| Micron Technology                | 3         | 0.36%   |
| KIOXIA                           | 3         | 0.36%   |
| VIA Technologies                 | 1         | 0.12%   |
| Union Memory (Shenzhen)          | 1         | 0.12%   |
| Silicon Image                    | 1         | 0.12%   |
| Shenzhen Longsys Electronics     | 1         | 0.12%   |
| Adaptec                          | 1         | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 104       | 11.78%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 74        | 8.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 60        | 6.8%    |
| AMD FCH SATA Controller [AHCI mode]                                                    | 46        | 5.21%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 45        | 5.1%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 40        | 4.53%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 33        | 3.74%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 30        | 3.4%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 29        | 3.28%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 22        | 2.49%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 22        | 2.49%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 20        | 2.27%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 17        | 1.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 16        | 1.81%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 15        | 1.7%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 13        | 1.47%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 12        | 1.36%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 11        | 1.25%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller       | 10        | 1.13%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 10        | 1.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 10        | 1.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 10        | 1.13%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 9         | 1.02%   |
| Samsung NVMe SSD Controller 980                                                        | 8         | 0.91%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 7         | 0.79%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 7         | 0.79%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 6         | 0.68%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 6         | 0.68%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 6         | 0.68%   |
| Sandisk PC SN520 NVMe SSD                                                              | 6         | 0.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 6         | 0.68%   |
| Phison E12 NVMe Controller                                                             | 6         | 0.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 6         | 0.68%   |
| SK Hynix BC501 NVMe Solid State Drive                                                  | 5         | 0.57%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                        | 5         | 0.57%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 5         | 0.57%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 5         | 0.57%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 5         | 0.57%   |
| SK Hynix Non-Volatile memory controller                                                | 4         | 0.45%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 4         | 0.45%   |
| Sandisk WD Blue SN550 NVMe SSD                                                         | 4         | 0.45%   |
| Intel SSD 660P Series                                                                  | 4         | 0.45%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 4         | 0.45%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 4         | 0.45%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 4         | 0.45%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                 | 4         | 0.45%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                                 | 4         | 0.45%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 4         | 0.45%   |
| AMD SB600 Non-Raid-5 SATA                                                              | 4         | 0.45%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 3         | 0.34%   |
| SK Hynix BC511                                                                         | 3         | 0.34%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 3         | 0.34%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 3         | 0.34%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 3         | 0.34%   |
| Micron Non-Volatile memory controller                                                  | 3         | 0.34%   |
| KIOXIA Non-Volatile memory controller                                                  | 3         | 0.34%   |
| Kingston Company Company Non-Volatile memory controller                                | 3         | 0.34%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 3         | 0.34%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 3         | 0.34%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 3         | 0.34%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 603       | 69.95%  |
| NVMe | 152       | 17.63%  |
| IDE  | 61        | 7.08%   |
| RAID | 45        | 5.22%   |
| SCSI | 1         | 0.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 699       | 90.54%  |
| AMD          | 69        | 8.94%   |
| ARM          | 3         | 0.39%   |
| CentaurHauls | 1         | 0.13%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz    | 27        | 3.49%   |
| Intel Core i7-8550U CPU @ 1.80GHz    | 26        | 3.36%   |
| Intel Core i7-8565U CPU @ 1.80GHz    | 22        | 2.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz    | 20        | 2.59%   |
| Intel Core i7-7500U CPU @ 2.70GHz    | 13        | 1.68%   |
| Intel Core i5-8265U CPU @ 1.60GHz    | 13        | 1.68%   |
| Intel Core i5-3320M CPU @ 2.60GHz    | 13        | 1.68%   |
| Intel Core i5-2520M CPU @ 2.50GHz    | 13        | 1.68%   |
| Intel Core i5-6200U CPU @ 2.30GHz    | 11        | 1.42%   |
| Intel Core i5-2410M CPU @ 2.30GHz    | 11        | 1.42%   |
| Intel Core i5-6300U CPU @ 2.40GHz    | 10        | 1.29%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz   | 9         | 1.16%   |
| Intel Core i7-10510U CPU @ 1.80GHz   | 8         | 1.03%   |
| Intel Core i3-3110M CPU @ 2.40GHz    | 8         | 1.03%   |
| Intel Core i7-9750H CPU @ 2.60GHz    | 7         | 0.91%   |
| Intel Core i7-8750H CPU @ 2.20GHz    | 7         | 0.91%   |
| Intel Core i7-8665U CPU @ 1.90GHz    | 7         | 0.91%   |
| Intel Core i5-5300U CPU @ 2.30GHz    | 7         | 0.91%   |
| Intel Core i5-5200U CPU @ 2.20GHz    | 7         | 0.91%   |
| Intel Core i5-3230M CPU @ 2.60GHz    | 7         | 0.91%   |
| Intel Core i5-3210M CPU @ 2.50GHz    | 7         | 0.91%   |
| Intel Celeron CPU N3060 @ 1.60GHz    | 7         | 0.91%   |
| Intel Atom CPU N455 @ 1.66GHz        | 7         | 0.91%   |
| Intel Core i7-6500U CPU @ 2.50GHz    | 6         | 0.78%   |
| Intel Core i7-5600U CPU @ 2.60GHz    | 6         | 0.78%   |
| Intel Core i7-2640M CPU @ 2.80GHz    | 6         | 0.78%   |
| Intel Core i5-4210U CPU @ 1.70GHz    | 6         | 0.78%   |
| Intel Celeron CPU N3050 @ 1.60GHz    | 6         | 0.78%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz   | 5         | 0.65%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz   | 5         | 0.65%   |
| Intel Core i5-4300U CPU @ 1.90GHz    | 5         | 0.65%   |
| Intel Core i5-10210U CPU @ 1.60GHz   | 5         | 0.65%   |
| Intel Core i3-6006U CPU @ 2.00GHz    | 5         | 0.65%   |
| Intel Core i3-5005U CPU @ 2.00GHz    | 5         | 0.65%   |
| Intel Pentium CPU N3700 @ 1.60GHz    | 4         | 0.52%   |
| Intel Core i7-8650U CPU @ 1.90GHz    | 4         | 0.52%   |
| Intel Core i7-5500U CPU @ 2.40GHz    | 4         | 0.52%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz   | 4         | 0.52%   |
| Intel Core i7-4510U CPU @ 2.00GHz    | 4         | 0.52%   |
| Intel Core i7-4500U CPU @ 1.80GHz    | 4         | 0.52%   |
| Intel Core i7-3630QM CPU @ 2.40GHz   | 4         | 0.52%   |
| Intel Core i7-3520M CPU @ 2.90GHz    | 4         | 0.52%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz    | 4         | 0.52%   |
| Intel Core i5 CPU M 520 @ 2.40GHz    | 4         | 0.52%   |
| Intel Core i3-4005U CPU @ 1.70GHz    | 4         | 0.52%   |
| Intel Core i3-3120M CPU @ 2.50GHz    | 4         | 0.52%   |
| Intel Core i3-2370M CPU @ 2.40GHz    | 4         | 0.52%   |
| Intel Core i3-2350M CPU @ 2.30GHz    | 4         | 0.52%   |
| Intel Core i3-2330M CPU @ 2.20GHz    | 4         | 0.52%   |
| Intel Core i3-2310M CPU @ 2.10GHz    | 4         | 0.52%   |
| Intel Core i3-10110U CPU @ 2.10GHz   | 4         | 0.52%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz | 4         | 0.52%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz | 4         | 0.52%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz | 4         | 0.52%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz | 4         | 0.52%   |
| Intel Celeron N4000 CPU @ 1.10GHz    | 4         | 0.52%   |
| Intel Celeron CPU N2840 @ 2.16GHz    | 4         | 0.52%   |
| Intel Celeron CPU B800 @ 1.50GHz     | 4         | 0.52%   |
| Intel Atom CPU N450 @ 1.66GHz        | 4         | 0.52%   |
| Intel Atom CPU N270 @ 1.60GHz        | 4         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 227       | 29.37%  |
| Intel Core i7                  | 216       | 27.94%  |
| Intel Core i3                  | 75        | 9.7%    |
| Intel Celeron                  | 42        | 5.43%   |
| Intel Core 2 Duo               | 39        | 5.05%   |
| Intel Atom                     | 33        | 4.27%   |
| Intel Pentium                  | 17        | 2.2%    |
| Intel Pentium Dual             | 10        | 1.29%   |
| Other                          | 8         | 1.03%   |
| Intel Pentium M                | 8         | 1.03%   |
| AMD Ryzen 5                    | 8         | 1.03%   |
| Intel Pentium Dual-Core        | 7         | 0.91%   |
| AMD A8                         | 7         | 0.91%   |
| AMD A4                         | 7         | 0.91%   |
| AMD Ryzen 7 PRO                | 6         | 0.78%   |
| AMD E                          | 6         | 0.78%   |
| AMD A6                         | 6         | 0.78%   |
| Intel Core 2                   | 5         | 0.65%   |
| Intel Celeron Dual-Core        | 4         | 0.52%   |
| AMD Ryzen 7                    | 4         | 0.52%   |
| AMD Ryzen 3                    | 4         | 0.52%   |
| AMD E1                         | 4         | 0.52%   |
| AMD Turion 64 X2 Mobile        | 3         | 0.39%   |
| Intel Pentium Silver           | 2         | 0.26%   |
| Intel Core i9                  | 2         | 0.26%   |
| Intel Celeron M                | 2         | 0.26%   |
| ARM ARMv7                      | 2         | 0.26%   |
| AMD E2                         | 2         | 0.26%   |
| Intel Pentium III              | 1         | 0.13%   |
| Intel Pentium 4                | 1         | 0.13%   |
| Intel Genuine                  | 1         | 0.13%   |
| Intel Core m7                  | 1         | 0.13%   |
| Intel Core m3                  | 1         | 0.13%   |
| Intel Core Duo                 | 1         | 0.13%   |
| CentaurHauls VIA C7            | 1         | 0.13%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.13%   |
| AMD Ryzen 5 PRO                | 1         | 0.13%   |
| AMD Phenom II                  | 1         | 0.13%   |
| AMD FX                         | 1         | 0.13%   |
| AMD C-70                       | 1         | 0.13%   |
| AMD C-60                       | 1         | 0.13%   |
| AMD C-50                       | 1         | 0.13%   |
| AMD Athlon Neo                 | 1         | 0.13%   |
| AMD Athlon II Dual-Core        | 1         | 0.13%   |
| AMD A10                        | 1         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 453       | 58.68%  |
| 4      | 257       | 33.29%  |
| 1      | 33        | 4.27%   |
| 6      | 22        | 2.85%   |
| 8      | 6         | 0.78%   |
| 3      | 1         | 0.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 770       | 99.87%  |
| 2      | 1         | 0.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 565       | 73.09%  |
| 1      | 208       | 26.91%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 729       | 94.55%  |
| Unknown        | 21        | 2.72%   |
| 32-bit         | 20        | 2.59%   |
| 64-bit         | 1         | 0.13%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 304       | 38.34%  |
| 0x206a7    | 50        | 6.31%   |
| 0x806ec    | 38        | 4.79%   |
| 0x306a9    | 38        | 4.79%   |
| 0x806ea    | 30        | 3.78%   |
| 0x1067a    | 30        | 3.78%   |
| 0x306d4    | 23        | 2.9%    |
| 0x40651    | 20        | 2.52%   |
| 0x306c3    | 18        | 2.27%   |
| 0x806e9    | 17        | 2.14%   |
| 0x406e3    | 17        | 2.14%   |
| 0x906ea    | 14        | 1.77%   |
| 0x20655    | 13        | 1.64%   |
| 0x6fd      | 11        | 1.39%   |
| 0x30678    | 11        | 1.39%   |
| 0x106ca    | 10        | 1.26%   |
| 0x806eb    | 9         | 1.13%   |
| 0x406c3    | 9         | 1.13%   |
| 0x20652    | 9         | 1.13%   |
| 0x906e9    | 7         | 0.88%   |
| 0x706e5    | 7         | 0.88%   |
| 0x406c4    | 7         | 0.88%   |
| 0x08108102 | 7         | 0.88%   |
| 0x05000119 | 7         | 0.88%   |
| 0x706a1    | 5         | 0.63%   |
| 0x6d8      | 5         | 0.63%   |
| 0x506e3    | 5         | 0.63%   |
| 0x07030105 | 5         | 0.63%   |
| 0x906ed    | 4         | 0.5%    |
| 0x106c2    | 4         | 0.5%    |
| 0x10676    | 4         | 0.5%    |
| 0x6f6      | 3         | 0.38%   |
| 0x506ca    | 3         | 0.38%   |
| 0x106e5    | 3         | 0.38%   |
| 0x0810100b | 3         | 0.38%   |
| 0x03000027 | 3         | 0.38%   |
| 0xa0652    | 2         | 0.25%   |
| 0x806c1    | 2         | 0.25%   |
| 0x706a8    | 2         | 0.25%   |
| 0x6d6      | 2         | 0.25%   |
| 0x30673    | 2         | 0.25%   |
| 0x08600102 | 2         | 0.25%   |
| 0x0700010b | 2         | 0.25%   |
| 0x06006704 | 2         | 0.25%   |
| 0x06003106 | 2         | 0.25%   |
| 0x05000101 | 2         | 0.25%   |
| 0xa0660    | 1         | 0.13%   |
| 0x906ec    | 1         | 0.13%   |
| 0x6fb      | 1         | 0.13%   |
| 0x6fa      | 1         | 0.13%   |
| 0x6ec      | 1         | 0.13%   |
| 0x6e8      | 1         | 0.13%   |
| 0x6b1      | 1         | 0.13%   |
| 0x695      | 1         | 0.13%   |
| 0x506c9    | 1         | 0.13%   |
| 0x30661    | 1         | 0.13%   |
| 0x08600106 | 1         | 0.13%   |
| 0x08600103 | 1         | 0.13%   |
| 0x08108109 | 1         | 0.13%   |
| 0x08101007 | 1         | 0.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 208       | 26.91%  |
| SandyBridge     | 79        | 10.22%  |
| IvyBridge       | 69        | 8.93%   |
| Haswell         | 63        | 8.15%   |
| Skylake         | 45        | 5.82%   |
| Penryn          | 45        | 5.82%   |
| Silvermont      | 36        | 4.66%   |
| Broadwell       | 32        | 4.14%   |
| Westmere        | 30        | 3.88%   |
| Core            | 21        | 2.72%   |
| Bonnell         | 21        | 2.72%   |
| P6              | 13        | 1.68%   |
| Zen+            | 12        | 1.55%   |
| Bobcat          | 12        | 1.55%   |
| Puma            | 9         | 1.16%   |
| Goldmont plus   | 9         | 1.16%   |
| Zen             | 8         | 1.03%   |
| IceLake         | 8         | 1.03%   |
| Goldmont        | 6         | 0.78%   |
| Nehalem         | 5         | 0.65%   |
| Jaguar          | 5         | 0.65%   |
| CometLake       | 5         | 0.65%   |
| TigerLake       | 4         | 0.52%   |
| K8 Hammer       | 4         | 0.52%   |
| K10 Llano       | 4         | 0.52%   |
| Excavator       | 4         | 0.52%   |
| Unknown         | 4         | 0.52%   |
| Zen 2           | 3         | 0.39%   |
| Steamroller     | 3         | 0.39%   |
| Piledriver      | 2         | 0.26%   |
| K10             | 2         | 0.26%   |
| NetBurst        | 1         | 0.13%   |
| K8 & K10 hybrid | 1         | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 639       | 65.67%  |
| Nvidia                           | 189       | 19.42%  |
| AMD                              | 141       | 14.49%  |
| Silicon Integrated Systems [SiS] | 3         | 0.31%   |
| VIA Technologies                 | 1         | 0.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 73        | 7.28%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 66        | 6.58%   |
| Intel UHD Graphics 620                                                                   | 62        | 6.18%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 45        | 4.49%   |
| Intel HD Graphics 620                                                                    | 37        | 3.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 36        | 3.59%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 34        | 3.39%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 33        | 3.29%   |
| Intel HD Graphics 5500                                                                   | 29        | 2.89%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 23        | 2.29%   |
| Intel Core Processor Integrated Graphics Controller                                      | 22        | 2.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 21        | 2.09%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 21        | 2.09%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 19        | 1.89%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 15        | 1.5%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 15        | 1.5%    |
| Intel HD Graphics 630                                                                    | 13        | 1.3%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 12        | 1.2%    |
| AMD Picasso                                                                              | 12        | 1.2%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 10        | 1%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 10        | 1%      |
| Nvidia GP108M [GeForce MX150]                                                            | 9         | 0.9%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 9         | 0.9%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 9         | 0.9%    |
| Nvidia GM108M [GeForce 840M]                                                             | 7         | 0.7%    |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 7         | 0.7%    |
| Nvidia GK208BM [GeForce 920M]                                                            | 7         | 0.7%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 7         | 0.7%    |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 7         | 0.7%    |
| Intel HD Graphics 530                                                                    | 7         | 0.7%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 0.7%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 7         | 0.7%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 7         | 0.7%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 7         | 0.7%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 7         | 0.7%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 6         | 0.6%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 6         | 0.6%    |
| Intel HD Graphics 500                                                                    | 6         | 0.6%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 5         | 0.5%    |
| Intel Iris Plus Graphics G7                                                              | 5         | 0.5%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 5         | 0.5%    |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 5         | 0.5%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 4         | 0.4%    |
| Nvidia GP108M [GeForce MX250]                                                            | 4         | 0.4%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 4         | 0.4%    |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 4         | 0.4%    |
| Nvidia GK208M [GeForce GT 740M]                                                          | 4         | 0.4%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 0.4%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 4         | 0.4%    |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 4         | 0.4%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 0.4%    |
| AMD Wrestler [Radeon HD 6320]                                                            | 4         | 0.4%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 0.4%    |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 4         | 0.4%    |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 3         | 0.3%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.3%    |
| Nvidia GT218M [NVS 3100M]                                                                | 3         | 0.3%    |
| Nvidia GP108M [GeForce MX230]                                                            | 3         | 0.3%    |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 0.3%    |
| Nvidia GM108M [GeForce 940M]                                                             | 3         | 0.3%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 436       | 56.19%  |
| Intel + Nvidia     | 149       | 19.2%   |
| 1 x AMD            | 84        | 10.82%  |
| Intel + AMD        | 50        | 6.44%   |
| 1 x Nvidia         | 38        | 4.9%    |
| 2 x AMD            | 7         | 0.9%    |
| Other              | 5         | 0.64%   |
| 1 x SiS            | 3         | 0.39%   |
| Intel + 2 x Nvidia | 2         | 0.26%   |
| 2 x Nvidia         | 1         | 0.13%   |
| 1 x VIA            | 1         | 0.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 693       | 89.07%  |
| Proprietary | 63        | 8.1%    |
| Unknown     | 22        | 2.83%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 649       | 83.21%  |
| 0.01-0.5   | 43        | 5.51%   |
| 1.01-2.0   | 42        | 5.38%   |
| 0.51-1.0   | 23        | 2.95%   |
| 3.01-4.0   | 14        | 1.79%   |
| 7.01-8.0   | 4         | 0.51%   |
| 5.01-6.0   | 4         | 0.51%   |
| 2.01-3.0   | 1         | 0.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 188       | 21.32%  |
| LG Display              | 136       | 15.42%  |
| BOE                     | 106       | 12.02%  |
| Samsung Electronics     | 100       | 11.34%  |
| Chimei Innolux          | 96        | 10.88%  |
| Dell                    | 34        | 3.85%   |
| Lenovo                  | 26        | 2.95%   |
| Goldstar                | 21        | 2.38%   |
| Chi Mei Optoelectronics | 21        | 2.38%   |
| Sharp                   | 14        | 1.59%   |
| Hewlett-Packard         | 12        | 1.36%   |
| Apple                   | 12        | 1.36%   |
| InfoVision              | 11        | 1.25%   |
| Iiyama                  | 11        | 1.25%   |
| Philips                 | 8         | 0.91%   |
| PANDA                   | 8         | 0.91%   |
| AOC                     | 8         | 0.91%   |
| Sony                    | 6         | 0.68%   |
| LG Philips              | 6         | 0.68%   |
| Ancor Communications    | 6         | 0.68%   |
| Acer                    | 6         | 0.68%   |
| HannStar                | 5         | 0.57%   |
| BenQ                    | 4         | 0.45%   |
| LGD                     | 3         | 0.34%   |
| CPT                     | 3         | 0.34%   |
| Quanta Display          | 2         | 0.23%   |
| InnoLux Display         | 2         | 0.23%   |
| Eizo                    | 2         | 0.23%   |
| Xiaomi                  | 1         | 0.11%   |
| Wacom                   | 1         | 0.11%   |
| Vizio                   | 1         | 0.11%   |
| ViewSonic               | 1         | 0.11%   |
| Unknown (XXX)           | 1         | 0.11%   |
| Unknown                 | 1         | 0.11%   |
| SKY                     | 1         | 0.11%   |
| Seiko/Epson             | 1         | 0.11%   |
| RTK                     | 1         | 0.11%   |
| PVT                     | 1         | 0.11%   |
| Panasonic               | 1         | 0.11%   |
| NEC Computers           | 1         | 0.11%   |
| MSI                     | 1         | 0.11%   |
| Monoprice               | 1         | 0.11%   |
| Medion                  | 1         | 0.11%   |
| LOE                     | 1         | 0.11%   |
| Lenovo Group Limited    | 1         | 0.11%   |
| KDC                     | 1         | 0.11%   |
| Higer                   | 1         | 0.11%   |
| Fujitsu Siemens         | 1         | 0.11%   |
| FOX                     | 1         | 0.11%   |
| CSO                     | 1         | 0.11%   |
| CMN                     | 1         | 0.11%   |
| CHI                     | 1         | 0.11%   |
| ASUSTek Computer        | 1         | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch           | 10        | 1.12%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 8         | 0.89%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 7         | 0.78%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 6         | 0.67%   |
| Goldstar LG ULTRAWIDE GSM59F1 1920x1080 580x240mm 24.7-inch              | 6         | 0.67%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 6         | 0.67%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 6         | 0.67%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 6         | 0.67%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 5         | 0.56%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 5         | 0.56%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 5         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 5         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 5         | 0.56%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch           | 5         | 0.56%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 4         | 0.45%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 4         | 0.45%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                 | 4         | 0.45%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch                  | 4         | 0.45%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 4         | 0.45%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch          | 4         | 0.45%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 4         | 0.45%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch            | 4         | 0.45%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 220x130mm 10.1-inch            | 4         | 0.45%   |
| AU Optronics LCD Monitor AUO47EC 1366x768 344x193mm 15.5-inch            | 4         | 0.45%   |
| AU Optronics LCD Monitor AUO423D 1920x1080 309x173mm 13.9-inch           | 4         | 0.45%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x193mm 15.5-inch           | 4         | 0.45%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                  | 3         | 0.34%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 3         | 0.34%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch     | 3         | 0.34%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch     | 3         | 0.34%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch    | 3         | 0.34%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 3         | 0.34%   |
| LG Display LCD Monitor LGD02D9 1920x1080 350x190mm 15.7-inch             | 3         | 0.34%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 3         | 0.34%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 3         | 0.34%   |
| InfoVision LCD Monitor IVO04E3 1366x768 277x156mm 12.5-inch              | 3         | 0.34%   |
| InfoVision LCD Monitor IVO03F4 1920x1200 263x164mm 12.2-inch             | 3         | 0.34%   |
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                        | 3         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15D3 1920x1080 344x193mm 15.5-inch         | 3         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 3         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 350x190mm 15.7-inch          | 3         | 0.34%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch         | 3         | 0.34%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 3         | 0.34%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 3         | 0.34%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A4 1366x768 344x194mm 15.5-inch | 3         | 0.34%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 3         | 0.34%   |
| BOE LCD Monitor BOE0869 1920x1080 344x194mm 15.5-inch                    | 3         | 0.34%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 340x190mm 15.3-inch            | 3         | 0.34%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch           | 3         | 0.34%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 340x190mm 15.3-inch            | 3         | 0.34%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch            | 3         | 0.34%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 3         | 0.34%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 3         | 0.34%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch           | 3         | 0.34%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 3         | 0.34%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch            | 3         | 0.34%   |
| AU Optronics LCD Monitor 1920x1080                                       | 3         | 0.34%   |
| Acer V276HL ACR032F 1920x1080 598x336mm 27.0-inch                        | 3         | 0.34%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                  | 2         | 0.22%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 2         | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 314       | 37.97%  |
| 1366x768 (WXGA)    | 299       | 36.15%  |
| 1600x900 (HD+)     | 41        | 4.96%   |
| 1280x800 (WXGA)    | 32        | 3.87%   |
| 3840x2160 (4K)     | 20        | 2.42%   |
| 2560x1440 (QHD)    | 17        | 2.06%   |
| 1920x1200 (WUXGA)  | 16        | 1.93%   |
| 1024x600           | 16        | 1.93%   |
| 1440x900 (WXGA+)   | 13        | 1.57%   |
| 1280x1024 (SXGA)   | 10        | 1.21%   |
| 2560x1080          | 8         | 0.97%   |
| 1680x1050 (WSXGA+) | 7         | 0.85%   |
| 1360x768           | 6         | 0.73%   |
| 3200x1800 (QHD+)   | 5         | 0.6%    |
| 2880x1800          | 4         | 0.48%   |
| 3440x1440          | 3         | 0.36%   |
| 1600x1200          | 2         | 0.24%   |
| 1024x768 (XGA)     | 2         | 0.24%   |
| Unknown            | 2         | 0.24%   |
| 7680x2160          | 1         | 0.12%   |
| 640x480            | 1         | 0.12%   |
| 3840x1100          | 1         | 0.12%   |
| 2880x1920          | 1         | 0.12%   |
| 2560x1600          | 1         | 0.12%   |
| 2256x1504          | 1         | 0.12%   |
| 1800x1440          | 1         | 0.12%   |
| 1680x945           | 1         | 0.12%   |
| 1280x768           | 1         | 0.12%   |
| 1280x720 (HD)      | 1         | 0.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 329       | 37.43%  |
| 13      | 129       | 14.68%  |
| 14      | 117       | 13.31%  |
| 17      | 56        | 6.37%   |
| 12      | 44        | 5.01%   |
| 24      | 30        | 3.41%   |
| 23      | 28        | 3.19%   |
| 27      | 23        | 2.62%   |
| 21      | 20        | 2.28%   |
| 11      | 15        | 1.71%   |
| 10      | 15        | 1.71%   |
| Unknown | 15        | 1.71%   |
| 34      | 11        | 1.25%   |
| 18      | 9         | 1.02%   |
| 19      | 7         | 0.8%    |
| 25      | 4         | 0.46%   |
| 72      | 3         | 0.34%   |
| 31      | 3         | 0.34%   |
| 22      | 3         | 0.34%   |
| 20      | 3         | 0.34%   |
| 54      | 2         | 0.23%   |
| 40      | 2         | 0.23%   |
| 16      | 2         | 0.23%   |
| 8       | 2         | 0.23%   |
| 49      | 1         | 0.11%   |
| 43      | 1         | 0.11%   |
| 39      | 1         | 0.11%   |
| 29      | 1         | 0.11%   |
| 28      | 1         | 0.11%   |
| 26      | 1         | 0.11%   |
| 9       | 1         | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 508       | 58.46%  |
| 201-300     | 132       | 15.19%  |
| 501-600     | 81        | 9.32%   |
| 351-400     | 65        | 7.48%   |
| 401-500     | 37        | 4.26%   |
| Unknown     | 15        | 1.73%   |
| 701-800     | 11        | 1.27%   |
| 601-700     | 7         | 0.81%   |
| 801-900     | 3         | 0.35%   |
| 1501-2000   | 3         | 0.35%   |
| 101-200     | 3         | 0.35%   |
| 1001-1500   | 3         | 0.35%   |
| 901-1000    | 1         | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 667       | 85.62%  |
| 16/10   | 66        | 8.47%   |
| 21/9    | 11        | 1.41%   |
| 5/4     | 10        | 1.28%   |
| Unknown | 10        | 1.28%   |
| 4/3     | 7         | 0.9%    |
| 3/2     | 7         | 0.9%    |
| 3.40    | 1         | 0.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 327       | 37.2%   |
| 81-90          | 194       | 22.07%  |
| 201-250        | 63        | 7.17%   |
| 71-80          | 54        | 6.14%   |
| 121-130        | 44        | 5.01%   |
| 61-70          | 43        | 4.89%   |
| 301-350        | 24        | 2.73%   |
| 151-200        | 19        | 2.16%   |
| 51-60          | 16        | 1.82%   |
| 351-500        | 16        | 1.82%   |
| 41-50          | 15        | 1.71%   |
| Unknown        | 15        | 1.71%   |
| 251-300        | 13        | 1.48%   |
| 141-150        | 13        | 1.48%   |
| 131-140        | 7         | 0.8%    |
| More than 1000 | 6         | 0.68%   |
| 501-1000       | 4         | 0.46%   |
| 1-40           | 3         | 0.34%   |
| 91-100         | 3         | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 318       | 37.06%  |
| 121-160       | 308       | 35.9%   |
| 51-100        | 143       | 16.67%  |
| 161-240       | 49        | 5.71%   |
| More than 240 | 16        | 1.86%   |
| Unknown       | 15        | 1.75%   |
| 1-50          | 9         | 1.05%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 628       | 79.8%   |
| 2     | 130       | 16.52%  |
| 3     | 16        | 2.03%   |
| 0     | 13        | 1.65%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 398       | 31.94%  |
| Realtek Semiconductor             | 376       | 30.18%  |
| Qualcomm Atheros                  | 243       | 19.5%   |
| Broadcom                          | 71        | 5.7%    |
| Marvell Technology Group          | 26        | 2.09%   |
| Broadcom Limited                  | 19        | 1.52%   |
| Ralink                            | 14        | 1.12%   |
| JMicron Technology                | 11        | 0.88%   |
| TP-Link                           | 8         | 0.64%   |
| Lenovo                            | 7         | 0.56%   |
| Huawei Technologies               | 7         | 0.56%   |
| Ericsson Business Mobile Networks | 6         | 0.48%   |
| Sierra Wireless                   | 5         | 0.4%    |
| Ralink Technology                 | 5         | 0.4%    |
| Dell                              | 5         | 0.4%    |
| ASIX Electronics                  | 5         | 0.4%    |
| Qualcomm Atheros Communications   | 4         | 0.32%   |
| Fibocom                           | 4         | 0.32%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.24%   |
| Samsung Electronics               | 3         | 0.24%   |
| Nvidia                            | 3         | 0.24%   |
| Hewlett-Packard                   | 3         | 0.24%   |
| Xiaomi                            | 2         | 0.16%   |
| Toshiba                           | 2         | 0.16%   |
| DisplayLink                       | 2         | 0.16%   |
| Cypress Semiconductor             | 2         | 0.16%   |
| ZyXEL Communications              | 1         | 0.08%   |
| Spreadtrum Communications         | 1         | 0.08%   |
| Qualcomm                          | 1         | 0.08%   |
| NetGear                           | 1         | 0.08%   |
| Motorola PCS                      | 1         | 0.08%   |
| MEDIATEK                          | 1         | 0.08%   |
| LSI                               | 1         | 0.08%   |
| HTC (High Tech Computer)          | 1         | 0.08%   |
| Foxconn / Hon Hai                 | 1         | 0.08%   |
| Edimax Technology                 | 1         | 0.08%   |
| D-Link System                     | 1         | 0.08%   |
| 3Com                              | 1         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 228       | 14.77%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 95        | 6.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 46        | 2.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 43        | 2.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 41        | 2.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 40        | 2.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 37        | 2.4%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 36        | 2.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 32        | 2.07%   |
| Intel Wireless 8265 / 8275                                              | 32        | 2.07%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 31        | 2.01%   |
| Intel Wireless 7260                                                     | 30        | 1.94%   |
| Intel Wireless 7265                                                     | 27        | 1.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 20        | 1.3%    |
| Intel Wi-Fi 6 AX200                                                     | 20        | 1.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 17        | 1.1%    |
| Intel Wireless-AC 9260                                                  | 17        | 1.1%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 17        | 1.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 17        | 1.1%    |
| Intel Wireless 8260                                                     | 15        | 0.97%   |
| Intel Wireless 3165                                                     | 14        | 0.91%   |
| Intel Ethernet Connection (3) I218-LM                                   | 14        | 0.91%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 12        | 0.78%   |
| Intel Wireless 3160                                                     | 12        | 0.78%   |
| Intel WiFi Link 5100                                                    | 12        | 0.78%   |
| Intel Ethernet Connection I219-LM                                       | 12        | 0.78%   |
| Intel Ethernet Connection I218-LM                                       | 12        | 0.78%   |
| Intel Ethernet Connection (6) I219-V                                    | 12        | 0.78%   |
| Intel Ethernet Connection (4) I219-LM                                   | 12        | 0.78%   |
| Intel 82577LM Gigabit Network Connection                                | 12        | 0.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 11        | 0.71%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 11        | 0.71%   |
| Intel 82567LM Gigabit Network Connection                                | 11        | 0.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 10        | 0.65%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 10        | 0.65%   |
| Intel Centrino Ultimate-N 6300                                          | 10        | 0.65%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 9         | 0.58%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 9         | 0.58%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 9         | 0.58%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 8         | 0.52%   |
| Intel Ethernet Connection (6) I219-LM                                   | 8         | 0.52%   |
| Intel Ethernet Connection (4) I219-V                                    | 8         | 0.52%   |
| Intel Centrino Advanced-N 6200                                          | 8         | 0.52%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 8         | 0.52%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 0.45%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 7         | 0.45%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 7         | 0.45%   |
| Intel Ethernet Connection I217-LM                                       | 7         | 0.45%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 7         | 0.45%   |
| Intel Centrino Advanced-N 6235                                          | 7         | 0.45%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 7         | 0.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 0.39%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 6         | 0.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 6         | 0.39%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 6         | 0.39%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 0.39%   |
| Intel Centrino Wireless-N 2230                                          | 6         | 0.39%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 6         | 0.39%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 377       | 47.96%  |
| Qualcomm Atheros                | 216       | 27.48%  |
| Realtek Semiconductor           | 87        | 11.07%  |
| Broadcom                        | 51        | 6.49%   |
| Ralink                          | 14        | 1.78%   |
| Broadcom Limited                | 9         | 1.15%   |
| TP-Link                         | 6         | 0.76%   |
| Sierra Wireless                 | 5         | 0.64%   |
| Ralink Technology               | 5         | 0.64%   |
| Qualcomm Atheros Communications | 4         | 0.51%   |
| Dell                            | 3         | 0.38%   |
| Fibocom                         | 2         | 0.25%   |
| ZyXEL Communications            | 1         | 0.13%   |
| Qualcomm                        | 1         | 0.13%   |
| NetGear                         | 1         | 0.13%   |
| MEDIATEK                        | 1         | 0.13%   |
| Hewlett-Packard                 | 1         | 0.13%   |
| Edimax Technology               | 1         | 0.13%   |
| D-Link System                   | 1         | 0.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 46        | 5.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 41        | 5.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 40        | 5.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 37        | 4.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 36        | 4.55%   |
| Intel Wireless 8265 / 8275                                              | 32        | 4.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 31        | 3.92%   |
| Intel Wireless 7260                                                     | 30        | 3.79%   |
| Intel Wireless 7265                                                     | 27        | 3.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 20        | 2.53%   |
| Intel Wi-Fi 6 AX200                                                     | 20        | 2.53%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 17        | 2.15%   |
| Intel Wireless-AC 9260                                                  | 17        | 2.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 17        | 2.15%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 17        | 2.15%   |
| Intel Wireless 8260                                                     | 15        | 1.9%    |
| Intel Wireless 3165                                                     | 14        | 1.77%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 1.52%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 12        | 1.52%   |
| Intel Wireless 3160                                                     | 12        | 1.52%   |
| Intel WiFi Link 5100                                                    | 12        | 1.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 11        | 1.39%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 11        | 1.39%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 10        | 1.26%   |
| Intel Centrino Ultimate-N 6300                                          | 10        | 1.26%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 9         | 1.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 9         | 1.14%   |
| Intel Centrino Advanced-N 6200                                          | 8         | 1.01%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 8         | 1.01%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 0.88%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 7         | 0.88%   |
| Intel Centrino Advanced-N 6235                                          | 7         | 0.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 0.76%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 0.76%   |
| Intel Centrino Wireless-N 2230                                          | 6         | 0.76%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 6         | 0.76%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 0.76%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 5         | 0.63%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 5         | 0.63%   |
| Intel Ultimate N WiFi Link 5300                                         | 5         | 0.63%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 5         | 0.63%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 4         | 0.51%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 4         | 0.51%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 4         | 0.51%   |
| Qualcomm Atheros AR9271 802.11n                                         | 4         | 0.51%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 4         | 0.51%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 4         | 0.51%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 0.51%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 4         | 0.51%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 0.51%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                           | 4         | 0.51%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 3         | 0.38%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.38%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 3         | 0.38%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 3         | 0.38%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 0.38%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 3         | 0.38%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 2         | 0.25%   |
| Sierra Wireless EM7345 4G LTE                                           | 2         | 0.25%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 2         | 0.25%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 352       | 49.37%  |
| Intel                            | 185       | 25.95%  |
| Qualcomm Atheros                 | 61        | 8.56%   |
| Broadcom                         | 29        | 4.07%   |
| Marvell Technology Group         | 26        | 3.65%   |
| JMicron Technology               | 11        | 1.54%   |
| Broadcom Limited                 | 10        | 1.4%    |
| Lenovo                           | 7         | 0.98%   |
| ASIX Electronics                 | 5         | 0.7%    |
| Huawei Technologies              | 4         | 0.56%   |
| Silicon Integrated Systems [SiS] | 3         | 0.42%   |
| Samsung Electronics              | 3         | 0.42%   |
| Nvidia                           | 3         | 0.42%   |
| Xiaomi                           | 2         | 0.28%   |
| TP-Link                          | 2         | 0.28%   |
| DisplayLink                      | 2         | 0.28%   |
| Cypress Semiconductor            | 2         | 0.28%   |
| Spreadtrum Communications        | 1         | 0.14%   |
| HTC (High Tech Computer)         | 1         | 0.14%   |
| Hewlett-Packard                  | 1         | 0.14%   |
| Foxconn / Hon Hai                | 1         | 0.14%   |
| Fibocom                          | 1         | 0.14%   |
| 3Com                             | 1         | 0.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 228       | 31.4%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 95        | 13.09%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 43        | 5.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 32        | 4.41%   |
| Intel Ethernet Connection (3) I218-LM                                          | 14        | 1.93%   |
| Intel Ethernet Connection I219-LM                                              | 12        | 1.65%   |
| Intel Ethernet Connection I218-LM                                              | 12        | 1.65%   |
| Intel Ethernet Connection (6) I219-V                                           | 12        | 1.65%   |
| Intel Ethernet Connection (4) I219-LM                                          | 12        | 1.65%   |
| Intel 82577LM Gigabit Network Connection                                       | 12        | 1.65%   |
| Intel 82567LM Gigabit Network Connection                                       | 11        | 1.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 10        | 1.38%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 9         | 1.24%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 8         | 1.1%    |
| Intel Ethernet Connection (6) I219-LM                                          | 8         | 1.1%    |
| Intel Ethernet Connection (4) I219-V                                           | 8         | 1.1%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 7         | 0.96%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 7         | 0.96%   |
| Intel Ethernet Connection I217-LM                                              | 7         | 0.96%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 7         | 0.96%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 6         | 0.83%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 6         | 0.83%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 6         | 0.83%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 5         | 0.69%   |
| Intel 82579V Gigabit Network Connection                                        | 5         | 0.69%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 4         | 0.55%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 4         | 0.55%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 4         | 0.55%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 4         | 0.55%   |
| Intel Ethernet Connection (7) I219-LM                                          | 4         | 0.55%   |
| Intel Ethernet Connection (10) I219-V                                          | 4         | 0.55%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 4         | 0.55%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 4         | 0.55%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 3         | 0.41%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 3         | 0.41%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 3         | 0.41%   |
| Intel Ethernet Connection I218-V                                               | 3         | 0.41%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 3         | 0.41%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 3         | 0.41%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 3         | 0.41%   |
| TP-Link USB 10/100/1000 LAN                                                    | 2         | 0.28%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 0.28%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 0.28%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2         | 0.28%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 2         | 0.28%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.28%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 2         | 0.28%   |
| Nvidia MCP79 Ethernet                                                          | 2         | 0.28%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 2         | 0.28%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 2         | 0.28%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                        | 2         | 0.28%   |
| Lenovo USB-C Dock Ethernet                                                     | 2         | 0.28%   |
| Intel I210 Gigabit Network Connection                                          | 2         | 0.28%   |
| Intel Ethernet Connection I219-V                                               | 2         | 0.28%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.28%   |
| Intel Ethernet Connection (10) I219-LM                                         | 2         | 0.28%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                             | 2         | 0.28%   |
| Huawei MRD-LX1F                                                                | 2         | 0.28%   |
| Cypress K38231_03                                                              | 2         | 0.28%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 2         | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 752       | 51.4%   |
| Ethernet | 684       | 46.75%  |
| Modem    | 25        | 1.71%   |
| Unknown  | 2         | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 644       | 55.81%  |
| Ethernet | 507       | 43.93%  |
| Modem    | 3         | 0.26%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 632       | 81.76%  |
| 1     | 120       | 15.52%  |
| 0     | 13        | 1.68%   |
| 3     | 7         | 0.91%   |
| 5     | 1         | 0.13%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 736       | 94.85%  |
| Yes  | 40        | 5.15%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 250       | 44.09%  |
| Qualcomm Atheros Communications | 83        | 14.64%  |
| Realtek Semiconductor           | 48        | 8.47%   |
| Broadcom                        | 44        | 7.76%   |
| Lite-On Technology              | 31        | 5.47%   |
| IMC Networks                    | 20        | 3.53%   |
| Foxconn / Hon Hai               | 19        | 3.35%   |
| Dell                            | 15        | 2.65%   |
| Hewlett-Packard                 | 13        | 2.29%   |
| Apple                           | 12        | 2.12%   |
| Toshiba                         | 8         | 1.41%   |
| Cambridge Silicon Radio         | 5         | 0.88%   |
| Ralink                          | 4         | 0.71%   |
| ASUSTek Computer                | 4         | 0.71%   |
| Alps Electric                   | 3         | 0.53%   |
| Foxconn International           | 2         | 0.35%   |
| Unknown                         | 1         | 0.18%   |
| Realtek                         | 1         | 0.18%   |
| Ralink Technology               | 1         | 0.18%   |
| Fujitsu                         | 1         | 0.18%   |
| Chicony Electronics             | 1         | 0.18%   |
| Askey Computer                  | 1         | 0.18%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 80        | 14.06%  |
| Intel Bluetooth Device                                                              | 74        | 13.01%  |
| Qualcomm Atheros  Bluetooth Device                                                  | 47        | 8.26%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 45        | 7.91%   |
| Realtek Bluetooth Radio                                                             | 25        | 4.39%   |
| Intel AX200 Bluetooth                                                               | 16        | 2.81%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 15        | 2.64%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 14        | 2.46%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 13        | 2.28%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 13        | 2.28%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 12        | 2.11%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 11        | 1.93%   |
| IMC Networks Bluetooth Device                                                       | 10        | 1.76%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 9         | 1.58%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 9         | 1.58%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 9         | 1.58%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 8         | 1.41%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 8         | 1.41%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 7         | 1.23%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 7         | 1.23%   |
| Dell DW375 Bluetooth Module                                                         | 7         | 1.23%   |
| Apple Bluetooth Host Controller                                                     | 6         | 1.05%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 5         | 0.88%   |
| Qualcomm Atheros Bluetooth                                                          | 5         | 0.88%   |
| IMC Networks Bluetooth Radio                                                        | 5         | 0.88%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 5         | 0.88%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 5         | 0.88%   |
| Toshiba Bluetooth Device                                                            | 4         | 0.7%    |
| Realtek RTL8821A Bluetooth                                                          | 4         | 0.7%    |
| Ralink RT3290 Bluetooth                                                             | 4         | 0.7%    |
| Lite-On Bluetooth Device                                                            | 4         | 0.7%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 4         | 0.7%    |
| Broadcom BCM2070 Bluetooth Device                                                   | 4         | 0.7%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 3         | 0.53%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 0.53%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 3         | 0.53%   |
| Dell Wireless 365 Bluetooth                                                         | 3         | 0.53%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 3         | 0.53%   |
| Toshiba Askey for                                                                   | 2         | 0.35%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 0.35%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 2         | 0.35%   |
| Lite-On Atheros Bluetooth                                                           | 2         | 0.35%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 2         | 0.35%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011]                              | 2         | 0.35%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 2         | 0.35%   |
| Foxconn / Hon Hai Acer Module                                                       | 2         | 0.35%   |
| Dell Wireless 355 Bluetooth                                                         | 2         | 0.35%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 2         | 0.35%   |
| Broadcom HP Portable Bumble Bee                                                     | 2         | 0.35%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 0.35%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 2         | 0.35%   |
| Broadcom BCM2045 Bluetooth                                                          | 2         | 0.35%   |
| ASUS Broadcom Bluetooth 2.1                                                         | 2         | 0.35%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 2         | 0.35%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 0.35%   |
| Apple Bluetooth HCI                                                                 | 2         | 0.35%   |
| Unknown Bluetooth Device                                                            | 1         | 0.18%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.18%   |
| Toshiba BCM43142A0                                                                  | 1         | 0.18%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.18%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 681       | 74.34%  |
| AMD                              | 91        | 9.93%   |
| Nvidia                           | 80        | 8.73%   |
| C-Media Electronics              | 10        | 1.09%   |
| Logitech                         | 7         | 0.76%   |
| Lenovo                           | 7         | 0.76%   |
| Realtek Semiconductor            | 5         | 0.55%   |
| Texas Instruments                | 4         | 0.44%   |
| Silicon Integrated Systems [SiS] | 3         | 0.33%   |
| Razer USA                        | 2         | 0.22%   |
| JMTek                            | 2         | 0.22%   |
| Focusrite-Novation               | 2         | 0.22%   |
| XMOS                             | 1         | 0.11%   |
| VIA Technologies                 | 1         | 0.11%   |
| Veho                             | 1         | 0.11%   |
| SmartlinkTechnology              | 1         | 0.11%   |
| QinHeng Electronics              | 1         | 0.11%   |
| Native Instruments               | 1         | 0.11%   |
| Microsoft                        | 1         | 0.11%   |
| M-Audio                          | 1         | 0.11%   |
| Ketron                           | 1         | 0.11%   |
| Huawei Technologies              | 1         | 0.11%   |
| Hewlett-Packard                  | 1         | 0.11%   |
| Guillemot                        | 1         | 0.11%   |
| GN Netcom                        | 1         | 0.11%   |
| ESS Technology                   | 1         | 0.11%   |
| Earth Computer Technologies      | 1         | 0.11%   |
| Dell                             | 1         | 0.11%   |
| Conrad Electronic SE             | 1         | 0.11%   |
| Blue Microphones                 | 1         | 0.11%   |
| BEHRINGER International          | 1         | 0.11%   |
| ASUSTek Computer                 | 1         | 0.11%   |
| Arturia                          | 1         | 0.11%   |
| AKAI Professional M.I.           | 1         | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 138       | 12.91%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 80        | 7.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 68        | 6.36%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 47        | 4.4%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 45        | 4.21%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 37        | 3.46%   |
| Intel 8 Series HD Audio Controller                                                                | 37        | 3.46%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 35        | 3.27%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 32        | 2.99%   |
| Intel Broadwell-U Audio Controller                                                                | 32        | 2.99%   |
| AMD FCH Azalia Controller                                                                         | 28        | 2.62%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 26        | 2.43%   |
| Intel Cannon Lake PCH cAVS                                                                        | 26        | 2.43%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 26        | 2.43%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 22        | 2.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 20        | 1.87%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 20        | 1.87%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 19        | 1.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 17        | 1.59%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 15        | 1.4%    |
| Intel CM238 HD Audio Controller                                                                   | 14        | 1.31%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 14        | 1.31%   |
| AMD Kabini HDMI/DP Audio                                                                          | 14        | 1.31%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 11        | 1.03%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 10        | 0.94%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 9         | 0.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 9         | 0.84%   |
| AMD Wrestler HDMI Audio                                                                           | 9         | 0.84%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 8         | 0.75%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 8         | 0.75%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 7         | 0.65%   |
| Nvidia High Definition Audio Controller                                                           | 6         | 0.56%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 6         | 0.56%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 6         | 0.56%   |
| Realtek Semiconductor USB Audio                                                                   | 5         | 0.47%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 5         | 0.47%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 5         | 0.47%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 0.37%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 0.37%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 4         | 0.37%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 4         | 0.37%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 0.37%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 0.37%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 4         | 0.37%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 4         | 0.37%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 4         | 0.37%   |
| AMD High Definition Audio Controller                                                              | 4         | 0.37%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 4         | 0.37%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 3         | 0.28%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 0.28%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.28%   |
| C-Media Electronics USB Advanced Audio Device                                                     | 3         | 0.28%   |
| C-Media Electronics CM108 Audio Controller                                                        | 3         | 0.28%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 3         | 0.28%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 0.28%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 3         | 0.28%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 0.28%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 0.28%   |
| Texas Instruments PCM2912A Audio Codec                                                            | 2         | 0.19%   |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 0.19%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 139       | 24.65%  |
| Samsung Electronics | 137       | 24.29%  |
| Micron Technology   | 63        | 11.17%  |
| Kingston            | 51        | 9.04%   |
| Unknown             | 50        | 8.87%   |
| Ramaxel Technology  | 20        | 3.55%   |
| Elpida              | 18        | 3.19%   |
| Crucial             | 16        | 2.84%   |
| A-DATA Technology   | 13        | 2.3%    |
| Smart               | 10        | 1.77%   |
| Nanya Technology    | 10        | 1.77%   |
| Teikon              | 6         | 1.06%   |
| Corsair             | 6         | 1.06%   |
| Unknown (ABCD)      | 4         | 0.71%   |
| Transcend           | 3         | 0.53%   |
| Apacer              | 3         | 0.53%   |
| Silicon Power       | 2         | 0.35%   |
| G.Skill             | 2         | 0.35%   |
| 48spaces            | 2         | 0.35%   |
| Unknown (8C97)      | 1         | 0.18%   |
| SMART Brazil        | 1         | 0.18%   |
| Qimonda             | 1         | 0.18%   |
| PNY                 | 1         | 0.18%   |
| HT Micron           | 1         | 0.18%   |
| GOODRAM             | 1         | 0.18%   |
| Avant               | 1         | 0.18%   |
| Atermiter           | 1         | 0.18%   |
| AMD                 | 1         | 0.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 10        | 1.65%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 10        | 1.65%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 9         | 1.49%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 1.16%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 1.16%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 7         | 1.16%   |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s             | 6         | 0.99%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 6         | 0.99%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.99%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.99%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.99%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s         | 6         | 0.99%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 5         | 0.83%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.83%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 5         | 0.83%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 5         | 0.83%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 4         | 0.66%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 0.66%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 4         | 0.66%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16384MB SODIMM DDR4 2667MT/s       | 4         | 0.66%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 4         | 0.66%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                  | 4         | 0.66%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 2667MT/s         | 4         | 0.66%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 4         | 0.66%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 0.66%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.66%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.66%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                           | 3         | 0.5%    |
| SK Hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s          | 3         | 0.5%    |
| SK Hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 3         | 0.5%    |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.5%    |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 3         | 0.5%    |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 3         | 0.5%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.5%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.5%    |
| Micron RAM 8KTF51264HZ-1G6N1 4096MB SODIMM DDR3 1600MT/s         | 3         | 0.5%    |
| Micron RAM 8ATF1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s          | 3         | 0.5%    |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 3         | 0.5%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 0.5%    |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 3         | 0.5%    |
| Kingston RAM 99U5428-040.A01LF 4GB SODIMM DDR3 1334MT/s          | 3         | 0.5%    |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 3         | 0.5%    |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4096MB SODIMM DDR3 1334MT/s         | 3         | 0.5%    |
| Unknown RAM Module 512MB SODIMM DDR2 400MT/s                     | 2         | 0.33%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 2         | 0.33%   |
| Unknown RAM Module 2048MB SODIMM DDR3                            | 2         | 0.33%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 2         | 0.33%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 2         | 0.33%   |
| Unknown RAM Module 1024MB SODIMM DDR3 1066MT/s                   | 2         | 0.33%   |
| Unknown RAM Module 1024MB SODIMM DDR                             | 2         | 0.33%   |
| Teikon RAM TMT251S6CFR8C-PBHC 4GB SODIMM DDR3 1600MT/s           | 2         | 0.33%   |
| Smart RAM SH564128FH8NZQNSCG 4096MB SODIMM DDR3 1600MT/s         | 2         | 0.33%   |
| Smart RAM SH564128FH8NZPHSCG 4GB SODIMM DDR3 1333MT/s            | 2         | 0.33%   |
| SK Hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 2         | 0.33%   |
| SK Hynix RAM Module 16384MB SODIMM DDR4 3200MT/s                 | 2         | 0.33%   |
| SK Hynix RAM Module 16384MB SODIMM DDR4 2667MT/s                 | 2         | 0.33%   |
| SK Hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 800MT/s         | 2         | 0.33%   |
| SK Hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR2 800MT/s            | 2         | 0.33%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.33%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 209       | 44.19%  |
| DDR4    | 171       | 36.15%  |
| DDR2    | 42        | 8.88%   |
| LPDDR4  | 15        | 3.17%   |
| SDRAM   | 13        | 2.75%   |
| LPDDR3  | 12        | 2.54%   |
| Unknown | 5         | 1.06%   |
| DRAM    | 3         | 0.63%   |
| DDR     | 2         | 0.42%   |
| RAM     | 1         | 0.21%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 448       | 95.32%  |
| Row Of Chips | 15        | 3.19%   |
| Unknown      | 4         | 0.85%   |
| Chip         | 3         | 0.64%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 174       | 32.95%  |
| 8192  | 162       | 30.68%  |
| 2048  | 94        | 17.8%   |
| 16384 | 51        | 9.66%   |
| 1024  | 35        | 6.63%   |
| 512   | 7         | 1.33%   |
| 256   | 3         | 0.57%   |
| 32768 | 1         | 0.19%   |
| 128   | 1         | 0.19%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 146       | 27.92%  |
| 2667    | 116       | 22.18%  |
| 2400    | 42        | 8.03%   |
| 1334    | 36        | 6.88%   |
| 2133    | 34        | 6.5%    |
| 1333    | 24        | 4.59%   |
| Unknown | 21        | 4.02%   |
| 3200    | 19        | 3.63%   |
| 667     | 17        | 3.25%   |
| 800     | 12        | 2.29%   |
| 1067    | 11        | 2.1%    |
| 975     | 8         | 1.53%   |
| 533     | 6         | 1.15%   |
| 2048    | 5         | 0.96%   |
| 1066    | 5         | 0.96%   |
| 4199    | 4         | 0.76%   |
| 3266    | 4         | 0.76%   |
| 1867    | 4         | 0.76%   |
| 400     | 4         | 0.76%   |
| 1776    | 2         | 0.38%   |
| 4267    | 1         | 0.19%   |
| 933     | 1         | 0.19%   |
| 333     | 1         | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 57.14%  |
| STMicroelectronics  | 1         | 14.29%  |
| Samsung Electronics | 1         | 14.29%  |
| Kyocera             | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 12.5%   |
| Samsung CLX-3300 Series                                   | 1         | 12.5%   |
| Kyocera ECOSYS P2335d                                     | 1         | 12.5%   |
| HP OfficeJet 3830 series                                  | 1         | 12.5%   |
| HP LaserJet P1102                                         | 1         | 12.5%   |
| HP LaserJet 1020                                          | 1         | 12.5%   |
| HP EWS UPD                                                | 1         | 12.5%   |
| HP Deskjet 2540 series                                    | 1         | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Notebooks | Percent |
|----------------|-----------|---------|
| Mustek Systems | 1         | 50%     |
| Canon          | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                       | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Mustek Systems SNAPSCAN e22 | 1         | 50%     |
| Canon CanoScan LiDE 110     | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 175       | 25.96%  |
| Realtek Semiconductor                  | 74        | 10.98%  |
| Microdia                               | 62        | 9.2%    |
| Sunplus Innovation Technology          | 60        | 8.9%    |
| Acer                                   | 57        | 8.46%   |
| IMC Networks                           | 54        | 8.01%   |
| Suyin                                  | 28        | 4.15%   |
| Lite-On Technology                     | 19        | 2.82%   |
| Silicon Motion                         | 18        | 2.67%   |
| Quanta                                 | 17        | 2.52%   |
| Cheng Uei Precision Industry (Foxlink) | 17        | 2.52%   |
| Lenovo                                 | 10        | 1.48%   |
| Apple                                  | 10        | 1.48%   |
| Syntek                                 | 9         | 1.34%   |
| Ricoh                                  | 9         | 1.34%   |
| Alcor Micro                            | 9         | 1.34%   |
| Logitech                               | 8         | 1.19%   |
| Samsung Electronics                    | 5         | 0.74%   |
| Primax Electronics                     | 5         | 0.74%   |
| ALi                                    | 4         | 0.59%   |
| Z-Star Microelectronics                | 3         | 0.45%   |
| Tobii Technology AB                    | 2         | 0.3%    |
| Luxvisions Innotech Limited            | 2         | 0.3%    |
| Importek                               | 2         | 0.3%    |
| Genesys Logic                          | 2         | 0.3%    |
| GEMBIRD                                | 2         | 0.3%    |
| Xiongmai                               | 1         | 0.15%   |
| Sunplus Technology                     | 1         | 0.15%   |
| Spreadtrum Communications              | 1         | 0.15%   |
| OmniVision Technologies                | 1         | 0.15%   |
| Microsoft                              | 1         | 0.15%   |
| icSpring                               | 1         | 0.15%   |
| Generalplus Technology                 | 1         | 0.15%   |
| Fitipower Integrated Technology        | 1         | 0.15%   |
| eMPIA Technology                       | 1         | 0.15%   |
| DigiTech                               | 1         | 0.15%   |
| Aveo Technology                        | 1         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                            | 32        | 4.71%   |
| Chicony Integrated Camera                               | 31        | 4.57%   |
| Chicony HD WebCam                                       | 21        | 3.09%   |
| IMC Networks Integrated Camera                          | 20        | 2.95%   |
| Sunplus Integrated_Webcam_HD                            | 16        | 2.36%   |
| Acer Integrated Camera                                  | 16        | 2.36%   |
| Microdia Integrated_Webcam_HD                           | 14        | 2.06%   |
| Acer Lenovo EasyCamera                                  | 13        | 1.91%   |
| Sunplus HD WebCam                                       | 11        | 1.62%   |
| Lite-On Integrated Camera                               | 11        | 1.62%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 11        | 1.62%   |
| Acer SunplusIT Integrated Camera                        | 10        | 1.47%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 9         | 1.33%   |
| Microdia Integrated Webcam                              | 9         | 1.33%   |
| Chicony HP HD Camera                                    | 9         | 1.33%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 7         | 1.03%   |
| Chicony EasyCamera                                      | 7         | 1.03%   |
| Sunplus Asus Webcam                                     | 6         | 0.88%   |
| Realtek Integrated Webcam                               | 6         | 0.88%   |
| Lenovo Integrated Webcam [R5U877]                       | 6         | 0.88%   |
| Sunplus Laptop_Integrated_Webcam_FHD                    | 5         | 0.74%   |
| Samsung Galaxy A5 (MTP)                                 | 5         | 0.74%   |
| Realtek USB2.0 HD UVC WebCam                            | 5         | 0.74%   |
| Realtek HD WebCam                                       | 5         | 0.74%   |
| Quanta HP HD Camera                                     | 5         | 0.74%   |
| Lite-On HP HD Camera                                    | 5         | 0.74%   |
| Chicony USB2.0 HD UVC WebCam                            | 5         | 0.74%   |
| Chicony USB2.0 Camera                                   | 5         | 0.74%   |
| Chicony HP TrueVision HD Camera                         | 5         | 0.74%   |
| Chicony HP HD Webcam                                    | 5         | 0.74%   |
| Suyin Integrated_Webcam_HD                              | 4         | 0.59%   |
| Suyin HP TrueVision HD Integrated Webcam                | 4         | 0.59%   |
| Suyin HP Truevision HD                                  | 4         | 0.59%   |
| Sunplus Laptop Integrated WebCam HD                     | 4         | 0.59%   |
| Sunplus HP HD Webcam [Fixed]                            | 4         | 0.59%   |
| Ricoh Sony Vaio Integrated Webcam                       | 4         | 0.59%   |
| Realtek USB2.0 VGA UVC WebCam                           | 4         | 0.59%   |
| Realtek EasyCamera                                      | 4         | 0.59%   |
| Primax HP HD Webcam [Fixed]                             | 4         | 0.59%   |
| Microdia Integrated_Webcam_FHD                          | 4         | 0.59%   |
| IMC Networks USB Camera                                 | 4         | 0.59%   |
| Chicony Lenovo Integrated Camera (0.3MP)                | 4         | 0.59%   |
| Chicony Lenovo EasyCamera                               | 4         | 0.59%   |
| Chicony HP Truevision HD                                | 4         | 0.59%   |
| Chicony HD User Facing                                  | 4         | 0.59%   |
| Chicony 2.0M UVC Webcam / CNF7129                       | 4         | 0.59%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 4         | 0.59%   |
| Apple iPhone 5/5C/5S/6/SE                               | 4         | 0.59%   |
| Alcor Micro HD WebCam                                   | 4         | 0.59%   |
| Acer ThinkPad Integrated Camera                         | 4         | 0.59%   |
| Syntek Lenovo EasyCamera                                | 3         | 0.44%   |
| Silicon Motion WebCam SCB-1100N                         | 3         | 0.44%   |
| Silicon Motion WebCam SCB-0385N                         | 3         | 0.44%   |
| Realtek Integrated Webcam_HD                            | 3         | 0.44%   |
| Quanta HP TrueVision HD Camera                          | 3         | 0.44%   |
| Microdia Integrated Webcam HD                           | 3         | 0.44%   |
| Microdia HP Webcam                                      | 3         | 0.44%   |
| Lenovo Integrated Webcam                                | 3         | 0.44%   |
| Chicony WebCam                                          | 3         | 0.44%   |
| Chicony VGA WebCam                                      | 3         | 0.44%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 54        | 36.49%  |
| Synaptics                  | 43        | 29.05%  |
| AuthenTec                  | 16        | 10.81%  |
| Upek                       | 10        | 6.76%   |
| Shenzhen Goodix Technology | 9         | 6.08%   |
| Elan Microelectronics      | 7         | 4.73%   |
| LighTuning Technology      | 4         | 2.7%    |
| Goodix                     | 2         | 1.35%   |
| STMicroelectronics         | 1         | 0.68%   |
| Samsung Electronics        | 1         | 0.68%   |
| Microsoft                  | 1         | 0.68%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 19        | 12.84%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 12        | 8.11%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 11        | 7.43%   |
| AuthenTec AES2810                                                          | 10        | 6.76%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 9         | 6.08%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 9         | 6.08%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 6.08%   |
| Elan ELAN:Fingerprint                                                      | 7         | 4.73%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 4.05%   |
| Shenzhen Goodix  FingerPrint Device                                        | 5         | 3.38%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 2.7%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 2.7%    |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 2.7%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 2.7%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 2.03%   |
| Synaptics  WBDI                                                            | 3         | 2.03%   |
| Unknown                                                                    | 3         | 2.03%   |
| Validity Sensors VFS491                                                    | 2         | 1.35%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 1.35%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.35%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.35%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 1.35%   |
| Goodix FingerPrint                                                         | 2         | 1.35%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.35%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 1.35%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.68%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.68%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.68%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.68%   |
| Synaptics WBDI Device                                                      | 1         | 0.68%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.68%   |
| Samsung Fingerprint Device                                                 | 1         | 0.68%   |
| Microsoft Fingerprint Reader                                               | 1         | 0.68%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.68%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.68%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 34        | 48.57%  |
| Alcor Micro           | 20        | 28.57%  |
| Lenovo                | 6         | 8.57%   |
| Upek                  | 4         | 5.71%   |
| O2 Micro              | 4         | 5.71%   |
| Gemalto (was Gemplus) | 1         | 1.43%   |
| Clay Logic            | 1         | 1.43%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 20        | 28.57%  |
| Broadcom BCM5880 Secure Applications Processor                               | 13        | 18.57%  |
| Broadcom 5880                                                                | 10        | 14.29%  |
| Lenovo Integrated Smart Card Reader                                          | 6         | 8.57%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 8.57%   |
| Broadcom 58200                                                               | 5         | 7.14%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 5.71%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 5.71%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.43%   |
| Clay Logic Nitrokey Start                                                    | 1         | 1.43%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 458       | 57.97%  |
| 1     | 248       | 31.39%  |
| 2     | 69        | 8.73%   |
| 3     | 12        | 1.52%   |
| 4     | 3         | 0.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 147       | 35.17%  |
| Graphics card            | 79        | 18.9%   |
| Chipcard                 | 64        | 15.31%  |
| Net/wireless             | 42        | 10.05%  |
| Bluetooth                | 19        | 4.55%   |
| Multimedia controller    | 17        | 4.07%   |
| Storage                  | 12        | 2.87%   |
| Camera                   | 12        | 2.87%   |
| Card reader              | 9         | 2.15%   |
| Sound                    | 5         | 1.2%    |
| Net/ethernet             | 4         | 0.96%   |
| Communication controller | 4         | 0.96%   |
| Network                  | 1         | 0.24%   |
| Modem                    | 1         | 0.24%   |
| Flash memory             | 1         | 0.24%   |
| Firewire controller      | 1         | 0.24%   |


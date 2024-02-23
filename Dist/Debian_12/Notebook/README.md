Debian 12 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Debian 12.

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

Total: 1819

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad E595 20NF0005IX    | [171aaf5d57](https://linux-hardware.org/?probe=171aaf5d57) | Feb 02, 2024 |
| Lenovo        | ThinkPad E595 20NF0005IX    | [c834e4941b](https://linux-hardware.org/?probe=c834e4941b) | Feb 02, 2024 |
| ASUSTek       | N56VZ                       | [2209fe1372](https://linux-hardware.org/?probe=2209fe1372) | Feb 02, 2024 |
| MSI           | Raider GE68HX 13VF          | [72ac680d91](https://linux-hardware.org/?probe=72ac680d91) | Feb 02, 2024 |
| HP            | EliteBook 2570p             | [59778f5513](https://linux-hardware.org/?probe=59778f5513) | Feb 02, 2024 |
| Apple         | MacBookAir7,2               | [632421d681](https://linux-hardware.org/?probe=632421d681) | Feb 01, 2024 |
| ASUSTek       | K54C                        | [59e4e733f0](https://linux-hardware.org/?probe=59e4e733f0) | Feb 01, 2024 |
| Acer          | Aspire 7740                 | [a329ef6c37](https://linux-hardware.org/?probe=a329ef6c37) | Feb 01, 2024 |
| Lenovo        | V17 G4 IRU 83A2             | [f33e772962](https://linux-hardware.org/?probe=f33e772962) | Feb 01, 2024 |
| Acer          | Aspire A515-56              | [5599d65127](https://linux-hardware.org/?probe=5599d65127) | Feb 01, 2024 |
| HP            | Pavilion Notebook           | [397f03250d](https://linux-hardware.org/?probe=397f03250d) | Feb 01, 2024 |
| Panasonic     | CF-54-2                     | [7758f322a6](https://linux-hardware.org/?probe=7758f322a6) | Feb 01, 2024 |
| HP            | Pavilion dv4                | [09400a55bb](https://linux-hardware.org/?probe=09400a55bb) | Feb 01, 2024 |
| Lenovo        | Flex 2-14 20404             | [b2d8a38af3](https://linux-hardware.org/?probe=b2d8a38af3) | Feb 01, 2024 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [7f20bd79c9](https://linux-hardware.org/?probe=7f20bd79c9) | Jan 31, 2024 |
| Unknown       | Unknown                     | [13b20f5383](https://linux-hardware.org/?probe=13b20f5383) | Jan 31, 2024 |
| HP            | EliteBook 2570p             | [7d98ca3c90](https://linux-hardware.org/?probe=7d98ca3c90) | Jan 31, 2024 |
| HP            | ProBook 4510s               | [2982cc0a30](https://linux-hardware.org/?probe=2982cc0a30) | Jan 31, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | [d743247f69](https://linux-hardware.org/?probe=d743247f69) | Jan 31, 2024 |
| Lenovo        | Yoga 900-13ISK 80MK         | [c5e686c940](https://linux-hardware.org/?probe=c5e686c940) | Jan 30, 2024 |
| Apple         | MacBookPro9,1               | [741671df2c](https://linux-hardware.org/?probe=741671df2c) | Jan 30, 2024 |
| OriginPC      | EVO16-S                     | [6d96755039](https://linux-hardware.org/?probe=6d96755039) | Jan 30, 2024 |
| Medion        | E15423                      | [2d39a42a0a](https://linux-hardware.org/?probe=2d39a42a0a) | Jan 29, 2024 |
| Dell          | XPS 9315                    | [c705e51d0e](https://linux-hardware.org/?probe=c705e51d0e) | Jan 29, 2024 |
| HUAWEI        | KPRC-WX0                    | [dea81917ae](https://linux-hardware.org/?probe=dea81917ae) | Jan 29, 2024 |
| Acer          | Aspire A315-58              | [c1af8d7ca2](https://linux-hardware.org/?probe=c1af8d7ca2) | Jan 29, 2024 |
| Dell          | XPS 9315                    | [9beaeed93b](https://linux-hardware.org/?probe=9beaeed93b) | Jan 29, 2024 |
| Apple         | MacBookPro5,4               | [c16bc8a6c2](https://linux-hardware.org/?probe=c16bc8a6c2) | Jan 29, 2024 |
| Lenovo        | IdeaPad P585 20181          | [d54756c11a](https://linux-hardware.org/?probe=d54756c11a) | Jan 28, 2024 |
| Lenovo        | ThinkPad T480 20L6S4T80H    | [cb5f6705aa](https://linux-hardware.org/?probe=cb5f6705aa) | Jan 28, 2024 |
| Dell          | G3 3590                     | [7fb3fcb32c](https://linux-hardware.org/?probe=7fb3fcb32c) | Jan 28, 2024 |
| HP            | Laptop 15z-ef3xxx           | [bde6b1bdd9](https://linux-hardware.org/?probe=bde6b1bdd9) | Jan 28, 2024 |
| Lenovo        | ThinkPad T490 20N3S5GP12    | [b0cc2bbbed](https://linux-hardware.org/?probe=b0cc2bbbed) | Jan 28, 2024 |
| Medion        | Akoya P7628                 | [77cd29bced](https://linux-hardware.org/?probe=77cd29bced) | Jan 27, 2024 |
| LG Electro... | 17Z90P-K.AA78A1             | [7280098d0c](https://linux-hardware.org/?probe=7280098d0c) | Jan 27, 2024 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [4b4af4b9b4](https://linux-hardware.org/?probe=4b4af4b9b4) | Jan 26, 2024 |
| Lenovo        | ThinkPad T530 2394EN6       | [4110faba77](https://linux-hardware.org/?probe=4110faba77) | Jan 26, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | [7423289dfa](https://linux-hardware.org/?probe=7423289dfa) | Jan 26, 2024 |
| HP            | 15                          | [4bce029b1f](https://linux-hardware.org/?probe=4bce029b1f) | Jan 26, 2024 |
| HP            | Victus by Gaming Laptop ... | [313cd1cfba](https://linux-hardware.org/?probe=313cd1cfba) | Jan 26, 2024 |
| HP            | EliteBook 850 G7 Noteboo... | [7f749dfabf](https://linux-hardware.org/?probe=7f749dfabf) | Jan 26, 2024 |
| HP            | Victus by Gaming Laptop ... | [9a3ff54cf8](https://linux-hardware.org/?probe=9a3ff54cf8) | Jan 26, 2024 |
| HP            | Spectre Notebook            | [e98f815ca2](https://linux-hardware.org/?probe=e98f815ca2) | Jan 26, 2024 |
| Dell          | Latitude D620               | [d46bb1fc6b](https://linux-hardware.org/?probe=d46bb1fc6b) | Jan 25, 2024 |
| Google        | Bobba360                    | [a4c97c836d](https://linux-hardware.org/?probe=a4c97c836d) | Jan 25, 2024 |
| HP            | ProBook 645 G4              | [af6ac91f2a](https://linux-hardware.org/?probe=af6ac91f2a) | Jan 25, 2024 |
| Google        | Bobba360                    | [0b03c9a8f7](https://linux-hardware.org/?probe=0b03c9a8f7) | Jan 24, 2024 |
| Dell          | Vostro1710                  | [1fc84171b5](https://linux-hardware.org/?probe=1fc84171b5) | Jan 24, 2024 |
| HP            | Pavilion dv9500             | [a2f58c7d83](https://linux-hardware.org/?probe=a2f58c7d83) | Jan 24, 2024 |
| HP            | Pavilion dv9500             | [6311362acc](https://linux-hardware.org/?probe=6311362acc) | Jan 24, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21HD0... | [ff7b63a668](https://linux-hardware.org/?probe=ff7b63a668) | Jan 23, 2024 |
| Dell          | XPS 13 9360                 | [cf5a6036e8](https://linux-hardware.org/?probe=cf5a6036e8) | Jan 23, 2024 |
| HP            | EliteBook 855 G8 Noteboo... | [c22fff0afb](https://linux-hardware.org/?probe=c22fff0afb) | Jan 23, 2024 |
| Acer          | Aspire E5-575G              | [1523773c75](https://linux-hardware.org/?probe=1523773c75) | Jan 23, 2024 |
| HP            | 15                          | [7728ab654b](https://linux-hardware.org/?probe=7728ab654b) | Jan 23, 2024 |
| Novatech      | C141EK3-CI3TX               | [72b4b6b3ff](https://linux-hardware.org/?probe=72b4b6b3ff) | Jan 23, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [7039b3ef95](https://linux-hardware.org/?probe=7039b3ef95) | Jan 23, 2024 |
| Lenovo        | ThinkPad X220 4290W4H       | [067daab9fb](https://linux-hardware.org/?probe=067daab9fb) | Jan 23, 2024 |
| Unknown       | Unknown                     | [b35ba11b64](https://linux-hardware.org/?probe=b35ba11b64) | Jan 22, 2024 |
| Dell          | G3 3579                     | [994425af24](https://linux-hardware.org/?probe=994425af24) | Jan 22, 2024 |
| HP            | Pavilion g4                 | [1edc58a524](https://linux-hardware.org/?probe=1edc58a524) | Jan 22, 2024 |
| Acer          | Swift SF314-511             | [69ce4e086f](https://linux-hardware.org/?probe=69ce4e086f) | Jan 22, 2024 |
| HP            | Pavilion g4                 | [ecddd3e100](https://linux-hardware.org/?probe=ecddd3e100) | Jan 21, 2024 |
| HP            | ProBook 4740s               | [681810a3c1](https://linux-hardware.org/?probe=681810a3c1) | Jan 21, 2024 |
| Lenovo        | ThinkPad T490 20N3SA9100    | [02efe357c0](https://linux-hardware.org/?probe=02efe357c0) | Jan 21, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [53887e0fb9](https://linux-hardware.org/?probe=53887e0fb9) | Jan 21, 2024 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [5df8be927b](https://linux-hardware.org/?probe=5df8be927b) | Jan 20, 2024 |
| Acer          | Aspire 3050                 | [7231400f5d](https://linux-hardware.org/?probe=7231400f5d) | Jan 20, 2024 |
| Dell          | Inspiron 3583               | [e47c76af02](https://linux-hardware.org/?probe=e47c76af02) | Jan 20, 2024 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [fa6a332180](https://linux-hardware.org/?probe=fa6a332180) | Jan 20, 2024 |
| Apple         | MacBookAir7,2               | [336ae86aff](https://linux-hardware.org/?probe=336ae86aff) | Jan 20, 2024 |
| Apple         | MacBookAir7,2               | [e0591611fa](https://linux-hardware.org/?probe=e0591611fa) | Jan 20, 2024 |
| Apple         | MacBookPro11,3              | [f129b719a5](https://linux-hardware.org/?probe=f129b719a5) | Jan 20, 2024 |
| Panasonic     | CF-31ATAAX1M                | [f9cc94a1c9](https://linux-hardware.org/?probe=f9cc94a1c9) | Jan 19, 2024 |
| Google        | Reks                        | [03f2d33169](https://linux-hardware.org/?probe=03f2d33169) | Jan 19, 2024 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [c5644b867a](https://linux-hardware.org/?probe=c5644b867a) | Jan 19, 2024 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [20e88d4383](https://linux-hardware.org/?probe=20e88d4383) | Jan 19, 2024 |
| Acer          | Aspire A515-43              | [2c2f4e8e3b](https://linux-hardware.org/?probe=2c2f4e8e3b) | Jan 19, 2024 |
| Medion        | S4216                       | [74fd2044d5](https://linux-hardware.org/?probe=74fd2044d5) | Jan 19, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [9226bd619b](https://linux-hardware.org/?probe=9226bd619b) | Jan 19, 2024 |
| GTZS          | Unknown                     | [6b926d1595](https://linux-hardware.org/?probe=6b926d1595) | Jan 19, 2024 |
| Lenovo        | ThinkPad X230 23205XG       | [384ae6ddfb](https://linux-hardware.org/?probe=384ae6ddfb) | Jan 19, 2024 |
| Lenovo        | IdeaPad S410p 20296         | [cd1e18703e](https://linux-hardware.org/?probe=cd1e18703e) | Jan 19, 2024 |
| HP            | Laptop 14-dq1xxx            | [048c8842d1](https://linux-hardware.org/?probe=048c8842d1) | Jan 19, 2024 |
| Lenovo        | IdeaPad S410p 20296         | [f07c9d75f0](https://linux-hardware.org/?probe=f07c9d75f0) | Jan 18, 2024 |
| Fujitsu       | LIFEBOOK P771               | [47367bff01](https://linux-hardware.org/?probe=47367bff01) | Jan 18, 2024 |
| Apple         | MacBookPro6,2               | [d39ea787aa](https://linux-hardware.org/?probe=d39ea787aa) | Jan 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [187a8a84af](https://linux-hardware.org/?probe=187a8a84af) | Jan 18, 2024 |
| Lenovo        | G50-45 80E3                 | [7fa6be7205](https://linux-hardware.org/?probe=7fa6be7205) | Jan 18, 2024 |
| Medion        | Crawler E30e                | [537214d414](https://linux-hardware.org/?probe=537214d414) | Jan 18, 2024 |
| Medion        | Crawler E30e                | [76c56f06b5](https://linux-hardware.org/?probe=76c56f06b5) | Jan 18, 2024 |
| Lenovo        | G500 20236                  | [a0fdd98d15](https://linux-hardware.org/?probe=a0fdd98d15) | Jan 18, 2024 |
| Dell          | Inspiron N5010              | [d19deae8ea](https://linux-hardware.org/?probe=d19deae8ea) | Jan 18, 2024 |
| Dell          | Latitude E6540              | [5f657f15c8](https://linux-hardware.org/?probe=5f657f15c8) | Jan 17, 2024 |
| ASUSTek       | K53U                        | [04cc25d38b](https://linux-hardware.org/?probe=04cc25d38b) | Jan 17, 2024 |
| Aquarius      | NS585                       | [21185900ad](https://linux-hardware.org/?probe=21185900ad) | Jan 17, 2024 |
| Monster       | ABRA A5 V16.6               | [181ed8314a](https://linux-hardware.org/?probe=181ed8314a) | Jan 17, 2024 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [acda9d9537](https://linux-hardware.org/?probe=acda9d9537) | Jan 17, 2024 |
| Dell          | Latitude E6400              | [acde30b0c9](https://linux-hardware.org/?probe=acde30b0c9) | Jan 17, 2024 |
| ASUSTek       | N501VW                      | [958a5f9a29](https://linux-hardware.org/?probe=958a5f9a29) | Jan 16, 2024 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [bfbba978c3](https://linux-hardware.org/?probe=bfbba978c3) | Jan 16, 2024 |
| Lenovo        | ThinkPad T490 20N3S5XF01    | [cf4a861856](https://linux-hardware.org/?probe=cf4a861856) | Jan 16, 2024 |
| Toshiba       | Satellite L40               | [f5e9dbe1c8](https://linux-hardware.org/?probe=f5e9dbe1c8) | Jan 16, 2024 |
| HP            | Laptop 15-da1xxx            | [cd726b3a5a](https://linux-hardware.org/?probe=cd726b3a5a) | Jan 15, 2024 |
| Dell          | XPS 15 9530                 | [61ade3f6d3](https://linux-hardware.org/?probe=61ade3f6d3) | Jan 15, 2024 |
| HP            | ProBook 450 15.6 inch G1... | [54ed51acbb](https://linux-hardware.org/?probe=54ed51acbb) | Jan 15, 2024 |
| Clevo         | M815P                       | [3ee9aaa992](https://linux-hardware.org/?probe=3ee9aaa992) | Jan 15, 2024 |
| Clevo         | M815P                       | [398ddcd746](https://linux-hardware.org/?probe=398ddcd746) | Jan 15, 2024 |
| Acer          | Swift SFX14-41G             | [947678b939](https://linux-hardware.org/?probe=947678b939) | Jan 15, 2024 |
| COIN COMPU... | LUM580                      | [e9f6bacb29](https://linux-hardware.org/?probe=e9f6bacb29) | Jan 15, 2024 |
| HP            | Laptop 15s-du0xxx           | [530c5882b9](https://linux-hardware.org/?probe=530c5882b9) | Jan 15, 2024 |
| Lenovo        | ThinkPad X230 Tablet 343... | [b1804aa7bc](https://linux-hardware.org/?probe=b1804aa7bc) | Jan 15, 2024 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [bdbb97ace1](https://linux-hardware.org/?probe=bdbb97ace1) | Jan 14, 2024 |
| Acer          | Aspire A515-43              | [9bec25152a](https://linux-hardware.org/?probe=9bec25152a) | Jan 14, 2024 |
| Apple         | MacBookPro11,1              | [e865dbe75e](https://linux-hardware.org/?probe=e865dbe75e) | Jan 14, 2024 |
| Samsung       | R780                        | [68eae1df45](https://linux-hardware.org/?probe=68eae1df45) | Jan 14, 2024 |
| Lenovo        | ThinkPad X280 20KESAC100    | [888ed5a8d8](https://linux-hardware.org/?probe=888ed5a8d8) | Jan 14, 2024 |
| Lenovo        | ThinkPad T520 42406AG       | [df565d9a02](https://linux-hardware.org/?probe=df565d9a02) | Jan 14, 2024 |
| HUAWEI        | BOD-WXX9                    | [9000ce06e8](https://linux-hardware.org/?probe=9000ce06e8) | Jan 14, 2024 |
| Acer          | TravelMate P259-G2-M        | [24d3ae9a88](https://linux-hardware.org/?probe=24d3ae9a88) | Jan 14, 2024 |
| Positivo      | Mobile                      | [750ee7ae05](https://linux-hardware.org/?probe=750ee7ae05) | Jan 14, 2024 |
| Lenovo        | Yoga Pro 7 14IRH8 82Y7      | [55b05d17b6](https://linux-hardware.org/?probe=55b05d17b6) | Jan 14, 2024 |
| ASUSTek       | X556UQK                     | [151b6ad9fb](https://linux-hardware.org/?probe=151b6ad9fb) | Jan 13, 2024 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [6b6751dc04](https://linux-hardware.org/?probe=6b6751dc04) | Jan 13, 2024 |
| Lenovo        | ThinkPad X220 4291QQ1       | [ad00b0ae02](https://linux-hardware.org/?probe=ad00b0ae02) | Jan 13, 2024 |
| TUXEDO        | Pulse 14 Gen3               | [5e82c88e53](https://linux-hardware.org/?probe=5e82c88e53) | Jan 12, 2024 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [91a1cfb426](https://linux-hardware.org/?probe=91a1cfb426) | Jan 12, 2024 |
| HP            | ZBook 15                    | [390b667998](https://linux-hardware.org/?probe=390b667998) | Jan 12, 2024 |
| Apple         | MacBookAir7,2               | [191e908130](https://linux-hardware.org/?probe=191e908130) | Jan 12, 2024 |
| Apple         | MacBookAir7,2               | [3d1d09a8cb](https://linux-hardware.org/?probe=3d1d09a8cb) | Jan 12, 2024 |
| Dell          | Precision 3581              | [07c4e8e9b5](https://linux-hardware.org/?probe=07c4e8e9b5) | Jan 12, 2024 |
| Dell          | Precision 7560              | [c540ef8073](https://linux-hardware.org/?probe=c540ef8073) | Jan 12, 2024 |
| HP            | ZBook 15                    | [5649070333](https://linux-hardware.org/?probe=5649070333) | Jan 12, 2024 |
| MSI           | Alpha 17 C7VG               | [586cfee5f8](https://linux-hardware.org/?probe=586cfee5f8) | Jan 12, 2024 |
| Dell          | Inspiron 3593               | [60b15cb73b](https://linux-hardware.org/?probe=60b15cb73b) | Jan 12, 2024 |
| Acer          | Aspire 3050                 | [ed5a4cc94d](https://linux-hardware.org/?probe=ed5a4cc94d) | Jan 12, 2024 |
| Apple         | MacBookPro8,2               | [1637fa5ff8](https://linux-hardware.org/?probe=1637fa5ff8) | Jan 12, 2024 |
| Apple         | MacBookPro8,2               | [5990a6e929](https://linux-hardware.org/?probe=5990a6e929) | Jan 12, 2024 |
| HP            | Laptop 15s-du0xxx           | [75a6760096](https://linux-hardware.org/?probe=75a6760096) | Jan 12, 2024 |
| Dell          | XPS 13 9310                 | [5c6de2d4a2](https://linux-hardware.org/?probe=5c6de2d4a2) | Jan 11, 2024 |
| Pegatron      | C15B                        | [168aedbfba](https://linux-hardware.org/?probe=168aedbfba) | Jan 11, 2024 |
| Lenovo        | Yoga 900-13ISK 80MK         | [d1201e3b8f](https://linux-hardware.org/?probe=d1201e3b8f) | Jan 11, 2024 |
| Dell          | Latitude 7490               | [51cfb0b7ec](https://linux-hardware.org/?probe=51cfb0b7ec) | Jan 11, 2024 |
| Apple         | MacBookPro5,5               | [38c0ed167d](https://linux-hardware.org/?probe=38c0ed167d) | Jan 11, 2024 |
| Razer         | Blade Stealth               | [a8c542db2c](https://linux-hardware.org/?probe=a8c542db2c) | Jan 11, 2024 |
| HP            | EliteBook 745 G6            | [e7c4951a31](https://linux-hardware.org/?probe=e7c4951a31) | Jan 10, 2024 |
| HUAWEI        | KLVF-XX                     | [133633238b](https://linux-hardware.org/?probe=133633238b) | Jan 10, 2024 |
| Dell          | Latitude 5490               | [aa516822e2](https://linux-hardware.org/?probe=aa516822e2) | Jan 10, 2024 |
| Sony          | VPCSA2CFX                   | [d408905e99](https://linux-hardware.org/?probe=d408905e99) | Jan 10, 2024 |
| Dell          | Latitude E6520              | [08e48552ea](https://linux-hardware.org/?probe=08e48552ea) | Jan 10, 2024 |
| Dell          | Latitude 5440               | [6ab5039217](https://linux-hardware.org/?probe=6ab5039217) | Jan 09, 2024 |
| Aquarius      | NS585                       | [ad17f295fa](https://linux-hardware.org/?probe=ad17f295fa) | Jan 09, 2024 |
| Aquarius      | NS585                       | [c74d9cb486](https://linux-hardware.org/?probe=c74d9cb486) | Jan 09, 2024 |
| Aquarius      | NS585                       | [8710764b3b](https://linux-hardware.org/?probe=8710764b3b) | Jan 09, 2024 |
| Aquarius      | NS585                       | [23ec56d03f](https://linux-hardware.org/?probe=23ec56d03f) | Jan 09, 2024 |
| Aquarius      | NS585                       | [a9250fd152](https://linux-hardware.org/?probe=a9250fd152) | Jan 09, 2024 |
| Aquarius      | NS585                       | [f3090f70d2](https://linux-hardware.org/?probe=f3090f70d2) | Jan 09, 2024 |
| Aquarius      | NS585                       | [a167167f54](https://linux-hardware.org/?probe=a167167f54) | Jan 09, 2024 |
| Aquarius      | NS585                       | [0d67b1f360](https://linux-hardware.org/?probe=0d67b1f360) | Jan 09, 2024 |
| Sony          | VPCSA2CFX                   | [1f326a66b0](https://linux-hardware.org/?probe=1f326a66b0) | Jan 09, 2024 |
| Google        | Blooguard                   | [18f4177827](https://linux-hardware.org/?probe=18f4177827) | Jan 09, 2024 |
| Lenovo        | ThinkPad X260 20F5S6V200    | [421cb02ac3](https://linux-hardware.org/?probe=421cb02ac3) | Jan 08, 2024 |
| ASUSTek       | K42JK                       | [458158ebaf](https://linux-hardware.org/?probe=458158ebaf) | Jan 08, 2024 |
| HP            | Laptop 15-db0xxx            | [5de015033e](https://linux-hardware.org/?probe=5de015033e) | Jan 08, 2024 |
| Google        | Cave                        | [197a15aab2](https://linux-hardware.org/?probe=197a15aab2) | Jan 08, 2024 |
| Toshiba       | Satellite C55-C             | [1c4c7bfa99](https://linux-hardware.org/?probe=1c4c7bfa99) | Jan 08, 2024 |
| Dell          | Precision 5680              | [047734c28f](https://linux-hardware.org/?probe=047734c28f) | Jan 08, 2024 |
| HP            | Laptop 15-db0xxx            | [f9da9135c7](https://linux-hardware.org/?probe=f9da9135c7) | Jan 08, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [8d2846dc8e](https://linux-hardware.org/?probe=8d2846dc8e) | Jan 08, 2024 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [45b99e2412](https://linux-hardware.org/?probe=45b99e2412) | Jan 08, 2024 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | [41c3c041a9](https://linux-hardware.org/?probe=41c3c041a9) | Jan 07, 2024 |
| Sony          | SVF1521H1EW                 | [f73763fd0c](https://linux-hardware.org/?probe=f73763fd0c) | Jan 06, 2024 |
| Gateway       | NV57H                       | [65a76b3627](https://linux-hardware.org/?probe=65a76b3627) | Jan 06, 2024 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [ddc660cbfb](https://linux-hardware.org/?probe=ddc660cbfb) | Jan 06, 2024 |
| Apple         | MacBookAir4,2               | [0f70d0e831](https://linux-hardware.org/?probe=0f70d0e831) | Jan 06, 2024 |
| HUAWEI        | HKFG-XX                     | [a90398b4f6](https://linux-hardware.org/?probe=a90398b4f6) | Jan 06, 2024 |
| TUXEDO        | Aura 14 Gen3                | [eade03882d](https://linux-hardware.org/?probe=eade03882d) | Jan 06, 2024 |
| Dell          | Precision 5680              | [0d58e93f98](https://linux-hardware.org/?probe=0d58e93f98) | Jan 06, 2024 |
| Dynabook      | Satellite Pro C40-G-109     | [0247395541](https://linux-hardware.org/?probe=0247395541) | Jan 05, 2024 |
| Dell          | XPS 15 9570                 | [090d0eae61](https://linux-hardware.org/?probe=090d0eae61) | Jan 05, 2024 |
| HP            | Pavilion dv7                | [2ecfa94f3b](https://linux-hardware.org/?probe=2ecfa94f3b) | Jan 05, 2024 |
| Thomson       | N17V3C8WH512                | [37fa4a2a98](https://linux-hardware.org/?probe=37fa4a2a98) | Jan 05, 2024 |
| HP            | EliteBook 6930p             | [868c32afaa](https://linux-hardware.org/?probe=868c32afaa) | Jan 05, 2024 |
| Lenovo        | 14w Gen 2 82N9              | [0f5b96cfff](https://linux-hardware.org/?probe=0f5b96cfff) | Jan 05, 2024 |
| ASUSTek       | P553UJ                      | [6e0de808da](https://linux-hardware.org/?probe=6e0de808da) | Jan 05, 2024 |
| HP            | EliteBook 745 G3            | [ac230e7d9a](https://linux-hardware.org/?probe=ac230e7d9a) | Jan 04, 2024 |
| HP            | EliteBook 745 G3            | [c5209d0e41](https://linux-hardware.org/?probe=c5209d0e41) | Jan 04, 2024 |
| HP            | Mini 210-1000               | [ddd4183f45](https://linux-hardware.org/?probe=ddd4183f45) | Jan 04, 2024 |
| HP            | Mini 210-1000               | [65f80ec87f](https://linux-hardware.org/?probe=65f80ec87f) | Jan 04, 2024 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | [761431c40c](https://linux-hardware.org/?probe=761431c40c) | Jan 04, 2024 |
| Toshiba       | PORTEGE R30-A               | [8830dd30d3](https://linux-hardware.org/?probe=8830dd30d3) | Jan 04, 2024 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [fbf70c614e](https://linux-hardware.org/?probe=fbf70c614e) | Jan 03, 2024 |
| HP            | Pavilion g6                 | [f1a54c438d](https://linux-hardware.org/?probe=f1a54c438d) | Jan 03, 2024 |
| ASUSTek       | 1015CX                      | [55d418530d](https://linux-hardware.org/?probe=55d418530d) | Jan 03, 2024 |
| HP            | Pavilion g6                 | [254ad76cac](https://linux-hardware.org/?probe=254ad76cac) | Jan 03, 2024 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | [f845df595a](https://linux-hardware.org/?probe=f845df595a) | Jan 03, 2024 |
| HP            | EliteBook 645 14 inch G1... | [c828174b3c](https://linux-hardware.org/?probe=c828174b3c) | Jan 03, 2024 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [a24e1e9937](https://linux-hardware.org/?probe=a24e1e9937) | Jan 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [d139ce529e](https://linux-hardware.org/?probe=d139ce529e) | Jan 03, 2024 |
| Lenovo        | ThinkBook 15-IML 20RW       | [9712812ff0](https://linux-hardware.org/?probe=9712812ff0) | Jan 03, 2024 |
| Acer          | Nitro AN515-52              | [b789e33c24](https://linux-hardware.org/?probe=b789e33c24) | Jan 03, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21E3C... | [f490c2378e](https://linux-hardware.org/?probe=f490c2378e) | Jan 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [473cff2d66](https://linux-hardware.org/?probe=473cff2d66) | Jan 02, 2024 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [7c849a7e11](https://linux-hardware.org/?probe=7c849a7e11) | Jan 02, 2024 |
| HP            | EliteBook 2570p             | [5299a026ab](https://linux-hardware.org/?probe=5299a026ab) | Jan 02, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [a333274a33](https://linux-hardware.org/?probe=a333274a33) | Jan 02, 2024 |
| HP            | Laptop 14s-dy5xxx           | [4c531fb260](https://linux-hardware.org/?probe=4c531fb260) | Jan 02, 2024 |
| Lenovo        | G505 20240                  | [ff10a3ab7d](https://linux-hardware.org/?probe=ff10a3ab7d) | Jan 02, 2024 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [5570fbf22f](https://linux-hardware.org/?probe=5570fbf22f) | Jan 02, 2024 |
| HP            | Laptop 15-db0xxx            | [dc302f3b3e](https://linux-hardware.org/?probe=dc302f3b3e) | Jan 02, 2024 |
| Dell          | XPS 13 9380                 | [d290e010eb](https://linux-hardware.org/?probe=d290e010eb) | Jan 02, 2024 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [197c876252](https://linux-hardware.org/?probe=197c876252) | Jan 02, 2024 |
| HP            | Pavilion 15                 | [277c4aa7d6](https://linux-hardware.org/?probe=277c4aa7d6) | Jan 02, 2024 |
| TUXEDO        | N8xxEZ                      | [4eb785f281](https://linux-hardware.org/?probe=4eb785f281) | Jan 01, 2024 |
| Lenovo        | G400s 20244                 | [29ab65f09e](https://linux-hardware.org/?probe=29ab65f09e) | Jan 01, 2024 |
| Lenovo        | G400s 20244                 | [3afdb557c8](https://linux-hardware.org/?probe=3afdb557c8) | Jan 01, 2024 |
| Dell          | Vostro 3405                 | [78db308528](https://linux-hardware.org/?probe=78db308528) | Jan 01, 2024 |
| Lenovo        | ThinkPad T430 23426QU       | [70bbf55180](https://linux-hardware.org/?probe=70bbf55180) | Dec 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K540... | [70c84eadc0](https://linux-hardware.org/?probe=70c84eadc0) | Dec 31, 2023 |
| Lenovo        | ThinkPad T420 4178AFU       | [8fb51545f7](https://linux-hardware.org/?probe=8fb51545f7) | Dec 31, 2023 |
| HP            | Laptop 15s-fq5xxx           | [b5bf7051ef](https://linux-hardware.org/?probe=b5bf7051ef) | Dec 31, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [49a4d9cad0](https://linux-hardware.org/?probe=49a4d9cad0) | Dec 31, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [942c025f11](https://linux-hardware.org/?probe=942c025f11) | Dec 31, 2023 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | [4f95b9d510](https://linux-hardware.org/?probe=4f95b9d510) | Dec 30, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E1T    | [f96a0610cb](https://linux-hardware.org/?probe=f96a0610cb) | Dec 30, 2023 |
| ASUSTek       | X751LJ                      | [0ebf64067f](https://linux-hardware.org/?probe=0ebf64067f) | Dec 30, 2023 |
| HP            | Pavilion Plus Laptop 14-... | [c6751f4e51](https://linux-hardware.org/?probe=c6751f4e51) | Dec 30, 2023 |
| HP            | Laptop 15-dy2xxx            | [c10327a38f](https://linux-hardware.org/?probe=c10327a38f) | Dec 29, 2023 |
| Acer          | Aspire A115-31              | [01aeb12545](https://linux-hardware.org/?probe=01aeb12545) | Dec 29, 2023 |
| Lenovo        | ThinkBook 16p Gen 4 21J8    | [afd9883450](https://linux-hardware.org/?probe=afd9883450) | Dec 29, 2023 |
| HP            | ProBook 650 G1              | [c7383a1237](https://linux-hardware.org/?probe=c7383a1237) | Dec 29, 2023 |
| HP            | ProBook 650 G1              | [cc8196ebec](https://linux-hardware.org/?probe=cc8196ebec) | Dec 29, 2023 |
| Toshiba       | Satellite C50D-A-138        | [cfb74314e2](https://linux-hardware.org/?probe=cfb74314e2) | Dec 29, 2023 |
| HP            | ProBook 655 G2              | [50589e94ba](https://linux-hardware.org/?probe=50589e94ba) | Dec 29, 2023 |
| ASUSTek       | K53BE                       | [23efadbf2f](https://linux-hardware.org/?probe=23efadbf2f) | Dec 29, 2023 |
| HP            | ProBook 655 G2              | [71ef8433cc](https://linux-hardware.org/?probe=71ef8433cc) | Dec 29, 2023 |
| Lenovo        | ThinkPad X230 2325V2Y       | [791788fbbc](https://linux-hardware.org/?probe=791788fbbc) | Dec 29, 2023 |
| Lenovo        | ThinkPad X230 2325V2Y       | [4861953728](https://linux-hardware.org/?probe=4861953728) | Dec 29, 2023 |
| Lenovo        | ThinkPad X230 2325V2Y       | [650d02f634](https://linux-hardware.org/?probe=650d02f634) | Dec 29, 2023 |
| Lenovo        | ThinkPad X230 2325V2Y       | [0a2d1d5688](https://linux-hardware.org/?probe=0a2d1d5688) | Dec 29, 2023 |
| Lenovo        | ThinkPad X230 2325V2Y       | [3d0513bb6c](https://linux-hardware.org/?probe=3d0513bb6c) | Dec 29, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [690962312c](https://linux-hardware.org/?probe=690962312c) | Dec 29, 2023 |
| Lenovo        | 3000 N500 42333GS           | [523a81b813](https://linux-hardware.org/?probe=523a81b813) | Dec 29, 2023 |
| COIN COMPU... | LUM580                      | [6a8246b500](https://linux-hardware.org/?probe=6a8246b500) | Dec 28, 2023 |
| MACHENIKE     | T58-V                       | [bbcdf32afc](https://linux-hardware.org/?probe=bbcdf32afc) | Dec 28, 2023 |
| Lenovo        | ThinkPad X230 2325V2Y       | [76b6ceb6cf](https://linux-hardware.org/?probe=76b6ceb6cf) | Dec 28, 2023 |
| Lenovo        | ThinkPad X230 2325V2Y       | [32b6e45042](https://linux-hardware.org/?probe=32b6e45042) | Dec 28, 2023 |
| Lenovo        | ThinkPad L540 20AUS0N200    | [e94a7fb094](https://linux-hardware.org/?probe=e94a7fb094) | Dec 28, 2023 |
| Lenovo        | ThinkPad L540 20AV0031FR    | [96e1e4403d](https://linux-hardware.org/?probe=96e1e4403d) | Dec 28, 2023 |
| Lenovo        | ThinkPad X230 2325V2Y       | [98b0838eb2](https://linux-hardware.org/?probe=98b0838eb2) | Dec 28, 2023 |
| Lenovo        | ThinkPad X230 2325V2Y       | [4eb0a16723](https://linux-hardware.org/?probe=4eb0a16723) | Dec 28, 2023 |
| Lenovo        | ThinkPad T440s 20ARS0J60... | [0f46c7112d](https://linux-hardware.org/?probe=0f46c7112d) | Dec 28, 2023 |
| Google        | Lillipup                    | [e8ac3dc206](https://linux-hardware.org/?probe=e8ac3dc206) | Dec 28, 2023 |
| ASUSTek       | K73SV                       | [2a36715319](https://linux-hardware.org/?probe=2a36715319) | Dec 28, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E1T    | [1948c445d8](https://linux-hardware.org/?probe=1948c445d8) | Dec 27, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [40c72fd8c2](https://linux-hardware.org/?probe=40c72fd8c2) | Dec 27, 2023 |
| Lenovo        | ThinkBook 15-IML 20RW       | [5ef2e29839](https://linux-hardware.org/?probe=5ef2e29839) | Dec 27, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [6d222bdbcb](https://linux-hardware.org/?probe=6d222bdbcb) | Dec 27, 2023 |
| Lenovo        | ThinkPad L530 2475A61       | [990d8dce86](https://linux-hardware.org/?probe=990d8dce86) | Dec 27, 2023 |
| HP            | ProBook 650 G1              | [e623c937a6](https://linux-hardware.org/?probe=e623c937a6) | Dec 27, 2023 |
| HP            | ProBook 650 G1              | [f6c6dba166](https://linux-hardware.org/?probe=f6c6dba166) | Dec 27, 2023 |
| HP            | ProBook 650 G2              | [705f4fa6fd](https://linux-hardware.org/?probe=705f4fa6fd) | Dec 27, 2023 |
| HP            | ProBook 450 G3              | [9435700f28](https://linux-hardware.org/?probe=9435700f28) | Dec 27, 2023 |
| HP            | ProBook 650 G2              | [06264d7b71](https://linux-hardware.org/?probe=06264d7b71) | Dec 27, 2023 |
| HP            | ProBook 650 G2              | [09c41915d8](https://linux-hardware.org/?probe=09c41915d8) | Dec 27, 2023 |
| HP            | ProBook 650 G2              | [a89881fc3b](https://linux-hardware.org/?probe=a89881fc3b) | Dec 27, 2023 |
| HP            | ProBook 650 G2              | [b18f714a89](https://linux-hardware.org/?probe=b18f714a89) | Dec 27, 2023 |
| HP            | ProBook 450 G3              | [2424999ad8](https://linux-hardware.org/?probe=2424999ad8) | Dec 27, 2023 |
| HP            | ProBook 650 G1              | [1126414dff](https://linux-hardware.org/?probe=1126414dff) | Dec 27, 2023 |
| HP            | ProBook 450 G3              | [2ddc54287d](https://linux-hardware.org/?probe=2ddc54287d) | Dec 27, 2023 |
| Dell          | Latitude E6430              | [a5ce676225](https://linux-hardware.org/?probe=a5ce676225) | Dec 27, 2023 |
| Lenovo        | ThinkPad X220 4290B52       | [f4ec8bd5f1](https://linux-hardware.org/?probe=f4ec8bd5f1) | Dec 27, 2023 |
| Lenovo        | ThinkPad T16 Gen 2 21K7C... | [5a76629311](https://linux-hardware.org/?probe=5a76629311) | Dec 26, 2023 |
| HP            | ProBook 450 G3              | [1e952ed878](https://linux-hardware.org/?probe=1e952ed878) | Dec 26, 2023 |
| HP            | ENVY Notebook               | [6ffaa62d3d](https://linux-hardware.org/?probe=6ffaa62d3d) | Dec 26, 2023 |
| Lenovo        | ThinkPad P51 20HH0016GE     | [27f368f0df](https://linux-hardware.org/?probe=27f368f0df) | Dec 26, 2023 |
| Acer          | Aspire A314-22              | [83c0e37ece](https://linux-hardware.org/?probe=83c0e37ece) | Dec 25, 2023 |
| Lenovo        | ThinkPad T490s 20NYS5HM0... | [b30f25ba57](https://linux-hardware.org/?probe=b30f25ba57) | Dec 25, 2023 |
| Samsung       | NC210/NC110                 | [cba7a81460](https://linux-hardware.org/?probe=cba7a81460) | Dec 25, 2023 |
| Samsung       | NC210/NC110                 | [5820853b65](https://linux-hardware.org/?probe=5820853b65) | Dec 24, 2023 |
| HP            | Pavilion dv6                | [e9120b7c4e](https://linux-hardware.org/?probe=e9120b7c4e) | Dec 24, 2023 |
| HP            | Pavilion dv6                | [b3b2c1f621](https://linux-hardware.org/?probe=b3b2c1f621) | Dec 24, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [8e4881d45c](https://linux-hardware.org/?probe=8e4881d45c) | Dec 24, 2023 |
| HP            | Laptop 14-dk0xxx            | [0762c25f51](https://linux-hardware.org/?probe=0762c25f51) | Dec 24, 2023 |
| Toshiba       | Satellite C55-C             | [abd0319296](https://linux-hardware.org/?probe=abd0319296) | Dec 24, 2023 |
| Toshiba       | Satellite C55-C             | [256b476a15](https://linux-hardware.org/?probe=256b476a15) | Dec 24, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [9eff3f535e](https://linux-hardware.org/?probe=9eff3f535e) | Dec 24, 2023 |
| HUAWEI        | KLVD-WXX9                   | [ee7b7ce7cc](https://linux-hardware.org/?probe=ee7b7ce7cc) | Dec 24, 2023 |
| Toshiba       | Satellite A205              | [c3680bfd29](https://linux-hardware.org/?probe=c3680bfd29) | Dec 24, 2023 |
| HP            | Pavilion g7                 | [bbe3fb1914](https://linux-hardware.org/?probe=bbe3fb1914) | Dec 24, 2023 |
| IBM           | ThinkPad R50e 1842QDU       | [32a349ab97](https://linux-hardware.org/?probe=32a349ab97) | Dec 23, 2023 |
| Lenovo        | ThinkPad T420 4178AFU       | [c2681f33cc](https://linux-hardware.org/?probe=c2681f33cc) | Dec 23, 2023 |
| HP            | ProBook 655 G2              | [033325e722](https://linux-hardware.org/?probe=033325e722) | Dec 23, 2023 |
| AVITA         | NS14A6                      | [adf732b1b6](https://linux-hardware.org/?probe=adf732b1b6) | Dec 23, 2023 |
| Lenovo        | ThinkPad T480 20L5000BGE    | [8753b04999](https://linux-hardware.org/?probe=8753b04999) | Dec 23, 2023 |
| Google        | Reks                        | [52375a57c5](https://linux-hardware.org/?probe=52375a57c5) | Dec 22, 2023 |
| HP            | EliteBook 850 G3            | [5e8dc79e2c](https://linux-hardware.org/?probe=5e8dc79e2c) | Dec 22, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [a11f0a948c](https://linux-hardware.org/?probe=a11f0a948c) | Dec 22, 2023 |
| Irbis         | NB264                       | [8821679765](https://linux-hardware.org/?probe=8821679765) | Dec 22, 2023 |
| HP            | ENVY 15                     | [2997ffe5cf](https://linux-hardware.org/?probe=2997ffe5cf) | Dec 22, 2023 |
| Dell          | Inspiron 15 3515            | [cdff1cf322](https://linux-hardware.org/?probe=cdff1cf322) | Dec 22, 2023 |
| HP            | ENVY Notebook               | [ca2e6f9061](https://linux-hardware.org/?probe=ca2e6f9061) | Dec 22, 2023 |
| HP            | EliteBook 830 G5            | [aa3d919a29](https://linux-hardware.org/?probe=aa3d919a29) | Dec 22, 2023 |
| HONOR         | HYM-WXX                     | [1c225a853e](https://linux-hardware.org/?probe=1c225a853e) | Dec 21, 2023 |
| Lenovo        | ThinkPad T490 20N3S5GP12    | [093906d110](https://linux-hardware.org/?probe=093906d110) | Dec 21, 2023 |
| HP            | EliteBook 650 15.6 inch ... | [2e9f8a97e5](https://linux-hardware.org/?probe=2e9f8a97e5) | Dec 21, 2023 |
| Google        | Reks                        | [9a6f15c5d9](https://linux-hardware.org/?probe=9a6f15c5d9) | Dec 21, 2023 |
| Acer          | Swift SF314-54              | [edc5223b9b](https://linux-hardware.org/?probe=edc5223b9b) | Dec 21, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [1c3113c9b9](https://linux-hardware.org/?probe=1c3113c9b9) | Dec 20, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [2785a8b9c6](https://linux-hardware.org/?probe=2785a8b9c6) | Dec 20, 2023 |
| Apple         | MacBookAir6,2               | [ef17f12758](https://linux-hardware.org/?probe=ef17f12758) | Dec 20, 2023 |
| HP            | ENVY m6                     | [237331a1ba](https://linux-hardware.org/?probe=237331a1ba) | Dec 20, 2023 |
| Dell          | G7 7790                     | [bcc6b4046b](https://linux-hardware.org/?probe=bcc6b4046b) | Dec 19, 2023 |
| DellInc.      | Venue 8 Pro 5830            | [d6408a26a1](https://linux-hardware.org/?probe=d6408a26a1) | Dec 19, 2023 |
| HP            | ZBook Firefly 15 G7 Mobi... | [020e3af833](https://linux-hardware.org/?probe=020e3af833) | Dec 18, 2023 |
| Gigabyte      | AORUS 17H BXF               | [ad8b646e5c](https://linux-hardware.org/?probe=ad8b646e5c) | Dec 18, 2023 |
| Dell          | Vostro 15 3515              | [baf5b47a47](https://linux-hardware.org/?probe=baf5b47a47) | Dec 18, 2023 |
| Acer          | Swift SF314-71              | [5a5f20e49a](https://linux-hardware.org/?probe=5a5f20e49a) | Dec 18, 2023 |
| Apple         | MacBookPro13,2              | [dd9d263269](https://linux-hardware.org/?probe=dd9d263269) | Dec 18, 2023 |
| HP            | 15 Notebook PC              | [1293ea8b65](https://linux-hardware.org/?probe=1293ea8b65) | Dec 18, 2023 |
| HUAWEI        | BOHB-WAX9                   | [94757e986e](https://linux-hardware.org/?probe=94757e986e) | Dec 18, 2023 |
| Panasonic     | FZ-M1CCA17E3                | [87024c17b5](https://linux-hardware.org/?probe=87024c17b5) | Dec 17, 2023 |
| Panasonic     | FZ-M1CCA17E3                | [8f2a76eb09](https://linux-hardware.org/?probe=8f2a76eb09) | Dec 17, 2023 |
| Medion        | BEAST X30                   | [cec06735ba](https://linux-hardware.org/?probe=cec06735ba) | Dec 17, 2023 |
| Acer          | Swift SF314-43              | [7ff498fc83](https://linux-hardware.org/?probe=7ff498fc83) | Dec 17, 2023 |
| HP            | Compaq 6730s                | [628e8cf362](https://linux-hardware.org/?probe=628e8cf362) | Dec 17, 2023 |
| HP            | Compaq 6730s                | [774f3d4feb](https://linux-hardware.org/?probe=774f3d4feb) | Dec 17, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [b212e62ef7](https://linux-hardware.org/?probe=b212e62ef7) | Dec 17, 2023 |
| Samsung       | 760XDA                      | [53ab21d486](https://linux-hardware.org/?probe=53ab21d486) | Dec 17, 2023 |
| Packard Be... | EasyNote TE11HC             | [a155267edc](https://linux-hardware.org/?probe=a155267edc) | Dec 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [7162b25b98](https://linux-hardware.org/?probe=7162b25b98) | Dec 16, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [5f19b6ce4f](https://linux-hardware.org/?probe=5f19b6ce4f) | Dec 16, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [314b3b98d7](https://linux-hardware.org/?probe=314b3b98d7) | Dec 16, 2023 |
| Dell          | Vostro 5490                 | [ca117be9d4](https://linux-hardware.org/?probe=ca117be9d4) | Dec 16, 2023 |
| Lenovo        | ThinkPad P1 20MDS02BGE      | [65eb962233](https://linux-hardware.org/?probe=65eb962233) | Dec 15, 2023 |
| HP            | EliteBook 745 G3            | [ec4a48125c](https://linux-hardware.org/?probe=ec4a48125c) | Dec 15, 2023 |
| HP            | EliteBook 745 G3            | [d43271b873](https://linux-hardware.org/?probe=d43271b873) | Dec 15, 2023 |
| Medion        | Akoya E7226                 | [a8677e8420](https://linux-hardware.org/?probe=a8677e8420) | Dec 15, 2023 |
| Medion        | Akoya E7226                 | [059918d809](https://linux-hardware.org/?probe=059918d809) | Dec 15, 2023 |
| ASUSTek       | ROG Strix G713QE_G713QE     | [b4bcda5523](https://linux-hardware.org/?probe=b4bcda5523) | Dec 15, 2023 |
| ASUSTek       | ROG Strix G713QE_G713QE     | [de24d459c5](https://linux-hardware.org/?probe=de24d459c5) | Dec 14, 2023 |
| Apple         | MacBookAir7,2               | [09a184f2e4](https://linux-hardware.org/?probe=09a184f2e4) | Dec 14, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7232... | [d9de3edb6b](https://linux-hardware.org/?probe=d9de3edb6b) | Dec 14, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7232... | [84f162f88f](https://linux-hardware.org/?probe=84f162f88f) | Dec 14, 2023 |
| Dell          | XPS 15 9570                 | [67a32f0dd0](https://linux-hardware.org/?probe=67a32f0dd0) | Dec 14, 2023 |
| Dell          | XPS 15 9570                 | [283dc2dab5](https://linux-hardware.org/?probe=283dc2dab5) | Dec 14, 2023 |
| Dell          | Inspiron 7560               | [83034fb404](https://linux-hardware.org/?probe=83034fb404) | Dec 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [d2b1e67451](https://linux-hardware.org/?probe=d2b1e67451) | Dec 14, 2023 |
| Apple         | MacBookAir7,2               | [05c8fb1ded](https://linux-hardware.org/?probe=05c8fb1ded) | Dec 13, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [c4e3486e91](https://linux-hardware.org/?probe=c4e3486e91) | Dec 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [68e68f1683](https://linux-hardware.org/?probe=68e68f1683) | Dec 13, 2023 |
| Acer          | Aspire R3-131T              | [5fc8de17bb](https://linux-hardware.org/?probe=5fc8de17bb) | Dec 13, 2023 |
| Lenovo        | G50-45 80E3                 | [cfa115323d](https://linux-hardware.org/?probe=cfa115323d) | Dec 13, 2023 |
| Dell          | Latitude 5424 Rugged        | [ce56e420fc](https://linux-hardware.org/?probe=ce56e420fc) | Dec 13, 2023 |
| ASUSTek       | X556UQK                     | [1ac3287ee1](https://linux-hardware.org/?probe=1ac3287ee1) | Dec 13, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | [e28730f84d](https://linux-hardware.org/?probe=e28730f84d) | Dec 12, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | [f90b33b7d5](https://linux-hardware.org/?probe=f90b33b7d5) | Dec 12, 2023 |
| HP            | EliteBook 830 G7 Noteboo... | [774925ed25](https://linux-hardware.org/?probe=774925ed25) | Dec 12, 2023 |
| Lenovo        | ThinkPad X13 Gen 4 21J3C... | [e99a0bd1db](https://linux-hardware.org/?probe=e99a0bd1db) | Dec 12, 2023 |
| Positivo      | H14BT58                     | [74530bb40a](https://linux-hardware.org/?probe=74530bb40a) | Dec 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [53ee047174](https://linux-hardware.org/?probe=53ee047174) | Dec 12, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [756283ec58](https://linux-hardware.org/?probe=756283ec58) | Dec 12, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [c258c213e6](https://linux-hardware.org/?probe=c258c213e6) | Dec 12, 2023 |
| HP            | EliteBook 830 G5            | [a4bdf16134](https://linux-hardware.org/?probe=a4bdf16134) | Dec 12, 2023 |
| HP            | ProBook 455 G7              | [1bec383138](https://linux-hardware.org/?probe=1bec383138) | Dec 11, 2023 |
| Unknown       | Unknown                     | [79c6d70468](https://linux-hardware.org/?probe=79c6d70468) | Dec 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [0d7abecf9b](https://linux-hardware.org/?probe=0d7abecf9b) | Dec 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [3dcb225ff4](https://linux-hardware.org/?probe=3dcb225ff4) | Dec 11, 2023 |
| HP            | Laptop 15-fd0xxx            | [f5b7104728](https://linux-hardware.org/?probe=f5b7104728) | Dec 11, 2023 |
| HP            | Laptop 14s-dy5xxx           | [bfe021294b](https://linux-hardware.org/?probe=bfe021294b) | Dec 11, 2023 |
| Google        | Electro                     | [503645df79](https://linux-hardware.org/?probe=503645df79) | Dec 11, 2023 |
| HP            | ProBook 450 G3              | [57a80d9d1b](https://linux-hardware.org/?probe=57a80d9d1b) | Dec 11, 2023 |
| Dell          | XPS 13 9370                 | [201fa157d6](https://linux-hardware.org/?probe=201fa157d6) | Dec 10, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [324e195003](https://linux-hardware.org/?probe=324e195003) | Dec 10, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [f60e90cfd0](https://linux-hardware.org/?probe=f60e90cfd0) | Dec 10, 2023 |
| Fujitsu Si... | LIFEBOOK S7110              | [bb7ea992e6](https://linux-hardware.org/?probe=bb7ea992e6) | Dec 09, 2023 |
| Lenovo        | ThinkPad T530 242922G       | [2b8062d3cc](https://linux-hardware.org/?probe=2b8062d3cc) | Dec 09, 2023 |
| Dell          | Latitude E7240              | [93f24d2411](https://linux-hardware.org/?probe=93f24d2411) | Dec 09, 2023 |
| HP            | EliteBook 830 G5            | [b2743fd826](https://linux-hardware.org/?probe=b2743fd826) | Dec 09, 2023 |
| Apple         | MacBookPro12,1              | [9d633902a0](https://linux-hardware.org/?probe=9d633902a0) | Dec 09, 2023 |
| HP            | Laptop 15-da0xxx            | [4106c6dbcf](https://linux-hardware.org/?probe=4106c6dbcf) | Dec 09, 2023 |
| ASUSTek       | X507UB                      | [f1a1ea60e6](https://linux-hardware.org/?probe=f1a1ea60e6) | Dec 09, 2023 |
| Dell          | Precision 3550              | [a3be7ab761](https://linux-hardware.org/?probe=a3be7ab761) | Dec 09, 2023 |
| Dell          | Vostro 15 3515              | [0257ed619f](https://linux-hardware.org/?probe=0257ed619f) | Dec 08, 2023 |
| Toshiba       | Satellite L50-A-19P         | [cd3314169e](https://linux-hardware.org/?probe=cd3314169e) | Dec 08, 2023 |
| HP            | EliteBook 840 G6            | [b53080f09f](https://linux-hardware.org/?probe=b53080f09f) | Dec 08, 2023 |
| HONOR         | HYM-WXX                     | [b008f53987](https://linux-hardware.org/?probe=b008f53987) | Dec 08, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1502CBA    | [b46d0490b6](https://linux-hardware.org/?probe=b46d0490b6) | Dec 08, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [ba71538aed](https://linux-hardware.org/?probe=ba71538aed) | Dec 08, 2023 |
| ASUSTek       | Zenbook UX5401EA_UX5401E... | [0e2900b443](https://linux-hardware.org/?probe=0e2900b443) | Dec 08, 2023 |
| Lenovo        | ThinkPad X250 20CLS8C000    | [bff5eac6db](https://linux-hardware.org/?probe=bff5eac6db) | Dec 08, 2023 |
| Lenovo        | ThinkPad Mini10 3507A31     | [1229fd52f5](https://linux-hardware.org/?probe=1229fd52f5) | Dec 08, 2023 |
| HP            | G62                         | [c2f10412aa](https://linux-hardware.org/?probe=c2f10412aa) | Dec 07, 2023 |
| HP            | EliteBook 8470p             | [c723bcc62a](https://linux-hardware.org/?probe=c723bcc62a) | Dec 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [e7fabdedad](https://linux-hardware.org/?probe=e7fabdedad) | Dec 07, 2023 |
| Acer          | Extensa 4210                | [4f8a82394a](https://linux-hardware.org/?probe=4f8a82394a) | Dec 07, 2023 |
| Aquarius      | NS585                       | [b6b0a78cfa](https://linux-hardware.org/?probe=b6b0a78cfa) | Dec 07, 2023 |
| MSI           | Prestige 15 A10SC           | [b1c3e47458](https://linux-hardware.org/?probe=b1c3e47458) | Dec 07, 2023 |
| Dell          | Precision 7550              | [11f63c8ba3](https://linux-hardware.org/?probe=11f63c8ba3) | Dec 07, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [256fbd42a6](https://linux-hardware.org/?probe=256fbd42a6) | Dec 06, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | [280a9a93e6](https://linux-hardware.org/?probe=280a9a93e6) | Dec 06, 2023 |
| Dell          | Inspiron 1545               | [d54ba07f49](https://linux-hardware.org/?probe=d54ba07f49) | Dec 06, 2023 |
| HP            | ENVY Notebook               | [26a4295a68](https://linux-hardware.org/?probe=26a4295a68) | Dec 06, 2023 |
| Acer          | Aspire A314-22              | [ce624b95df](https://linux-hardware.org/?probe=ce624b95df) | Dec 05, 2023 |
| ASUSTek       | P553UJ                      | [e5ed994bf9](https://linux-hardware.org/?probe=e5ed994bf9) | Dec 05, 2023 |
| Lenovo        | IdeaPad 300-14ISK 80Q6      | [68784031ca](https://linux-hardware.org/?probe=68784031ca) | Dec 05, 2023 |
| HP            | EliteBook 840 G1            | [1b39d673f8](https://linux-hardware.org/?probe=1b39d673f8) | Dec 05, 2023 |
| HUAWEI        | BOD-WXX9                    | [da8437565a](https://linux-hardware.org/?probe=da8437565a) | Dec 04, 2023 |
| Dell          | Inspiron 5567               | [03fe12170c](https://linux-hardware.org/?probe=03fe12170c) | Dec 04, 2023 |
| Dell          | Inspiron 16 Plus 7620       | [969efab4b8](https://linux-hardware.org/?probe=969efab4b8) | Dec 04, 2023 |
| Acer          | Extensa 215-55              | [87616f0d71](https://linux-hardware.org/?probe=87616f0d71) | Dec 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [3f26c37883](https://linux-hardware.org/?probe=3f26c37883) | Dec 04, 2023 |
| Lenovo        | ThinkPad T450 20BUS3L502    | [592eb925fd](https://linux-hardware.org/?probe=592eb925fd) | Dec 04, 2023 |
| Lenovo        | ThinkPad T480 20L5S2J200    | [75603d3c20](https://linux-hardware.org/?probe=75603d3c20) | Dec 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [7afcab06a4](https://linux-hardware.org/?probe=7afcab06a4) | Dec 04, 2023 |
| HUAWEI        | BOD-WXX9                    | [961b00cfbe](https://linux-hardware.org/?probe=961b00cfbe) | Dec 04, 2023 |
| Samsung       | R530/R730/R540              | [7c16c8b9ac](https://linux-hardware.org/?probe=7c16c8b9ac) | Dec 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [bbd413d34b](https://linux-hardware.org/?probe=bbd413d34b) | Dec 03, 2023 |
| Lenovo        | V14-IIL 82C4                | [848e0dbd37](https://linux-hardware.org/?probe=848e0dbd37) | Dec 03, 2023 |
| Acer          | Aspire A315-24P             | [b8af3ee6d5](https://linux-hardware.org/?probe=b8af3ee6d5) | Dec 03, 2023 |
| Acer          | Unknown                     | [6555dd06ac](https://linux-hardware.org/?probe=6555dd06ac) | Dec 03, 2023 |
| Acer          | Aspire A315-24P             | [67efae847f](https://linux-hardware.org/?probe=67efae847f) | Dec 03, 2023 |
| Timi          | Mi Laptop Pro 15            | [41ef064705](https://linux-hardware.org/?probe=41ef064705) | Dec 03, 2023 |
| Timi          | Mi Laptop Pro 15            | [b14a847625](https://linux-hardware.org/?probe=b14a847625) | Dec 03, 2023 |
| Dell          | Precision M4800             | [ff01ff15f9](https://linux-hardware.org/?probe=ff01ff15f9) | Dec 03, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [744c430aa7](https://linux-hardware.org/?probe=744c430aa7) | Dec 02, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [1462381824](https://linux-hardware.org/?probe=1462381824) | Dec 02, 2023 |
| Apple         | MacBookPro12,1              | [138a63b91b](https://linux-hardware.org/?probe=138a63b91b) | Dec 02, 2023 |
| Lenovo        | Flex 2-14 20404             | [f366381075](https://linux-hardware.org/?probe=f366381075) | Dec 02, 2023 |
| Lenovo        | ThinkPad X220 4291OL3       | [d07f89fdd6](https://linux-hardware.org/?probe=d07f89fdd6) | Dec 02, 2023 |
| Dell          | Latitude 7440               | [b4179d70c3](https://linux-hardware.org/?probe=b4179d70c3) | Dec 01, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [d4a1f56f8d](https://linux-hardware.org/?probe=d4a1f56f8d) | Dec 01, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [fc30a356f0](https://linux-hardware.org/?probe=fc30a356f0) | Dec 01, 2023 |
| Toshiba       | Satellite L775              | [da7cc192f7](https://linux-hardware.org/?probe=da7cc192f7) | Dec 01, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [f17a1eb208](https://linux-hardware.org/?probe=f17a1eb208) | Dec 01, 2023 |
| Lenovo        | ThinkPad L14 Gen 4 21H1C... | [7590036270](https://linux-hardware.org/?probe=7590036270) | Dec 01, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [a828388299](https://linux-hardware.org/?probe=a828388299) | Nov 30, 2023 |
| Dell          | Inspiron 5570               | [6642e4462f](https://linux-hardware.org/?probe=6642e4462f) | Nov 30, 2023 |
| Lenovo        | ThinkPad T590 20N5S56P00    | [352fffb7a9](https://linux-hardware.org/?probe=352fffb7a9) | Nov 30, 2023 |
| Toshiba       | Satellite L455D             | [d08710e3d3](https://linux-hardware.org/?probe=d08710e3d3) | Nov 29, 2023 |
| Samsung       | RC530/RC730                 | [01aee620f1](https://linux-hardware.org/?probe=01aee620f1) | Nov 29, 2023 |
| HP            | Laptop 15s-du0xxx           | [bf583ba008](https://linux-hardware.org/?probe=bf583ba008) | Nov 29, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [ef2a2ab2a9](https://linux-hardware.org/?probe=ef2a2ab2a9) | Nov 29, 2023 |
| ASUSTek       | M50Vc                       | [0eba431c7a](https://linux-hardware.org/?probe=0eba431c7a) | Nov 29, 2023 |
| Acer          | Nitro AN515-55              | [6865be0fd7](https://linux-hardware.org/?probe=6865be0fd7) | Nov 29, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [414132dc07](https://linux-hardware.org/?probe=414132dc07) | Nov 29, 2023 |
| Lenovo        | ThinkPad T520 4243VU3       | [6cbaf1893d](https://linux-hardware.org/?probe=6cbaf1893d) | Nov 29, 2023 |
| Dell          | Precision 7560              | [035f0d6f41](https://linux-hardware.org/?probe=035f0d6f41) | Nov 29, 2023 |
| HP            | ProBook 450 G3              | [0d6a4cd900](https://linux-hardware.org/?probe=0d6a4cd900) | Nov 28, 2023 |
| HP            | Victus by Gaming Laptop ... | [b01d99f799](https://linux-hardware.org/?probe=b01d99f799) | Nov 28, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | [6b10244910](https://linux-hardware.org/?probe=6b10244910) | Nov 28, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [413049d0f4](https://linux-hardware.org/?probe=413049d0f4) | Nov 28, 2023 |
| HP            | ZBook 15 G6                 | [1f87fc5fca](https://linux-hardware.org/?probe=1f87fc5fca) | Nov 28, 2023 |
| ASUSTek       | F52Q                        | [705aa34dce](https://linux-hardware.org/?probe=705aa34dce) | Nov 27, 2023 |
| ASUSTek       | F52Q                        | [569db41ca1](https://linux-hardware.org/?probe=569db41ca1) | Nov 27, 2023 |
| Lenovo        | ThinkPad T490 20N3S2YS00    | [635d73bd44](https://linux-hardware.org/?probe=635d73bd44) | Nov 27, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [2715c8329f](https://linux-hardware.org/?probe=2715c8329f) | Nov 27, 2023 |
| Google        | Terra                       | [b21072bf0e](https://linux-hardware.org/?probe=b21072bf0e) | Nov 27, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [97e207d679](https://linux-hardware.org/?probe=97e207d679) | Nov 27, 2023 |
| Acer          | Aspire A515-56              | [419daf1e57](https://linux-hardware.org/?probe=419daf1e57) | Nov 27, 2023 |
| Lenovo        | ThinkPad X200 7458PN6       | [e37f4ef1d4](https://linux-hardware.org/?probe=e37f4ef1d4) | Nov 27, 2023 |
| HUAWEI        | BOM-WXX9                    | [13c14b2399](https://linux-hardware.org/?probe=13c14b2399) | Nov 27, 2023 |
| Lenovo        | Legion 7 15IMH05 81YT       | [f18c7cb67b](https://linux-hardware.org/?probe=f18c7cb67b) | Nov 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [332eec50ca](https://linux-hardware.org/?probe=332eec50ca) | Nov 26, 2023 |
| Apple         | MacBook5,1                  | [9e05915f77](https://linux-hardware.org/?probe=9e05915f77) | Nov 26, 2023 |
| Apple         | MacBook5,1                  | [ff1af2d7d2](https://linux-hardware.org/?probe=ff1af2d7d2) | Nov 26, 2023 |
| HP            | Laptop 15-dy2xxx            | [484699c792](https://linux-hardware.org/?probe=484699c792) | Nov 26, 2023 |
| Acer          | Swift SF314-42              | [bebbc2f6c4](https://linux-hardware.org/?probe=bebbc2f6c4) | Nov 25, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [0f05f2568e](https://linux-hardware.org/?probe=0f05f2568e) | Nov 25, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [8cba28d4a5](https://linux-hardware.org/?probe=8cba28d4a5) | Nov 25, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [1e4a3ed089](https://linux-hardware.org/?probe=1e4a3ed089) | Nov 25, 2023 |
| HP            | EliteBook 735 G6            | [a0480513dd](https://linux-hardware.org/?probe=a0480513dd) | Nov 25, 2023 |
| HP            | EliteBook 2570p             | [e01ac99a92](https://linux-hardware.org/?probe=e01ac99a92) | Nov 25, 2023 |
| HP            | Laptop 15s-du0xxx           | [7e541895b2](https://linux-hardware.org/?probe=7e541895b2) | Nov 25, 2023 |
| HP            | Compaq 6730b (NB027EA#AK... | [3b3bf03eee](https://linux-hardware.org/?probe=3b3bf03eee) | Nov 25, 2023 |
| HP            | EliteBook 865 16 inch G9... | [9620d48b2f](https://linux-hardware.org/?probe=9620d48b2f) | Nov 25, 2023 |
| Dell          | Latitude 3510               | [0ebe37e56d](https://linux-hardware.org/?probe=0ebe37e56d) | Nov 25, 2023 |
| Lenovo        | V14-IIL 82C4                | [eb4379efae](https://linux-hardware.org/?probe=eb4379efae) | Nov 24, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [4b725b7022](https://linux-hardware.org/?probe=4b725b7022) | Nov 24, 2023 |
| Lenovo        | IdeaPad Y500 20193          | [9a8395f2ac](https://linux-hardware.org/?probe=9a8395f2ac) | Nov 24, 2023 |
| HUAWEI        | NBD-WXX9                    | [59a3d34f64](https://linux-hardware.org/?probe=59a3d34f64) | Nov 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [499c7927dd](https://linux-hardware.org/?probe=499c7927dd) | Nov 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [9102327ebf](https://linux-hardware.org/?probe=9102327ebf) | Nov 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [1e5ad7dda0](https://linux-hardware.org/?probe=1e5ad7dda0) | Nov 23, 2023 |
| Samsung       | 270E5J/2570EJ               | [d6ab9c6df5](https://linux-hardware.org/?probe=d6ab9c6df5) | Nov 23, 2023 |
| Lenovo        | ThinkPad T460 20FMS57C00    | [adabeb3e91](https://linux-hardware.org/?probe=adabeb3e91) | Nov 23, 2023 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [b6496b25f7](https://linux-hardware.org/?probe=b6496b25f7) | Nov 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [be47adc197](https://linux-hardware.org/?probe=be47adc197) | Nov 23, 2023 |
| Google        | Edgar                       | [12d8e1b6af](https://linux-hardware.org/?probe=12d8e1b6af) | Nov 22, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [0337023dbe](https://linux-hardware.org/?probe=0337023dbe) | Nov 22, 2023 |
| HP            | Laptop 15-dw1xxx            | [d05f324edf](https://linux-hardware.org/?probe=d05f324edf) | Nov 22, 2023 |
| Dell          | Precision M4600             | [864f0c5cfe](https://linux-hardware.org/?probe=864f0c5cfe) | Nov 22, 2023 |
| Lenovo        | ThinkPad P52 20MAS21905     | [ada7aab2dd](https://linux-hardware.org/?probe=ada7aab2dd) | Nov 22, 2023 |
| Lenovo        | G500 20236                  | [43a399828f](https://linux-hardware.org/?probe=43a399828f) | Nov 22, 2023 |
| Lenovo        | G500 20236                  | [b72fbdf43a](https://linux-hardware.org/?probe=b72fbdf43a) | Nov 22, 2023 |
| Dell          | Latitude E6400              | [adb43d89ab](https://linux-hardware.org/?probe=adb43d89ab) | Nov 22, 2023 |
| Dell          | Latitude 7440               | [fa13937043](https://linux-hardware.org/?probe=fa13937043) | Nov 22, 2023 |
| Dell          | Latitude E6400              | [96e98f8c80](https://linux-hardware.org/?probe=96e98f8c80) | Nov 22, 2023 |
| HP            | G62                         | [de2f290631](https://linux-hardware.org/?probe=de2f290631) | Nov 20, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [7c6999858f](https://linux-hardware.org/?probe=7c6999858f) | Nov 20, 2023 |
| Dell          | Latitude 5401               | [b3698296b0](https://linux-hardware.org/?probe=b3698296b0) | Nov 20, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [a090e73dbf](https://linux-hardware.org/?probe=a090e73dbf) | Nov 20, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | [e0d3e7cba3](https://linux-hardware.org/?probe=e0d3e7cba3) | Nov 19, 2023 |
| Lenovo        | G510 20238                  | [2567713f24](https://linux-hardware.org/?probe=2567713f24) | Nov 19, 2023 |
| Dell          | XPS 15 7590                 | [a40bc78bcf](https://linux-hardware.org/?probe=a40bc78bcf) | Nov 19, 2023 |
| Toshiba       | QOSMIO X70-A                | [4173fd74a2](https://linux-hardware.org/?probe=4173fd74a2) | Nov 19, 2023 |
| IBM           | ThinkPad T42 2374GB1        | [455a2c937b](https://linux-hardware.org/?probe=455a2c937b) | Nov 19, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [ebfe063207](https://linux-hardware.org/?probe=ebfe063207) | Nov 19, 2023 |
| HP            | ProBook 650 G1              | [80d502e7c1](https://linux-hardware.org/?probe=80d502e7c1) | Nov 19, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | [65f7027c84](https://linux-hardware.org/?probe=65f7027c84) | Nov 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [08f1313c20](https://linux-hardware.org/?probe=08f1313c20) | Nov 19, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [8ebb2df251](https://linux-hardware.org/?probe=8ebb2df251) | Nov 18, 2023 |
| MSI           | N6105                       | [647e6d71a4](https://linux-hardware.org/?probe=647e6d71a4) | Nov 18, 2023 |
| HP            | Laptop 15-da0xxx            | [666f76f4e9](https://linux-hardware.org/?probe=666f76f4e9) | Nov 18, 2023 |
| HP            | Stream Notebook             | [5d318f7956](https://linux-hardware.org/?probe=5d318f7956) | Nov 18, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [0fcb08b949](https://linux-hardware.org/?probe=0fcb08b949) | Nov 18, 2023 |
| Toshiba       | Satellite L300              | [416018ed84](https://linux-hardware.org/?probe=416018ed84) | Nov 17, 2023 |
| Irbis         | NB120                       | [a90949861b](https://linux-hardware.org/?probe=a90949861b) | Nov 17, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [c8af1c096b](https://linux-hardware.org/?probe=c8af1c096b) | Nov 17, 2023 |
| Samsung       | N102SP/N100SP/N101SP        | [be914025c2](https://linux-hardware.org/?probe=be914025c2) | Nov 17, 2023 |
| MSI           | GS65 Stealth 9SD            | [b0eba2e921](https://linux-hardware.org/?probe=b0eba2e921) | Nov 16, 2023 |
| Schenker      | VIA 15 Pro                  | [604f785353](https://linux-hardware.org/?probe=604f785353) | Nov 16, 2023 |
| Acer          | Aspire V3-771               | [5b38f976c4](https://linux-hardware.org/?probe=5b38f976c4) | Nov 16, 2023 |
| MSI           | GS65 Stealth 9SD            | [0331447937](https://linux-hardware.org/?probe=0331447937) | Nov 16, 2023 |
| Dell          | Latitude 5530               | [4490ae8afe](https://linux-hardware.org/?probe=4490ae8afe) | Nov 16, 2023 |
| Lenovo        | G50-70 20351                | [7f136c3e39](https://linux-hardware.org/?probe=7f136c3e39) | Nov 16, 2023 |
| Acer          | Aspire A315-42              | [a21066a759](https://linux-hardware.org/?probe=a21066a759) | Nov 15, 2023 |
| Acer          | Aspire E1-572               | [c7c8df77be](https://linux-hardware.org/?probe=c7c8df77be) | Nov 15, 2023 |
| HP            | Laptop 15-da0xxx            | [3f0b4a0bfe](https://linux-hardware.org/?probe=3f0b4a0bfe) | Nov 15, 2023 |
| Acer          | Aspire E5-576G              | [694833562c](https://linux-hardware.org/?probe=694833562c) | Nov 15, 2023 |
| HP            | Pavilion dv6                | [a7404738ed](https://linux-hardware.org/?probe=a7404738ed) | Nov 15, 2023 |
| Lenovo        | XiaoXinPro 16 IRH8 83AQ     | [1eb15d0477](https://linux-hardware.org/?probe=1eb15d0477) | Nov 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [98dd1a4a4f](https://linux-hardware.org/?probe=98dd1a4a4f) | Nov 15, 2023 |
| Dell          | Inspiron 1545               | [fd459af24b](https://linux-hardware.org/?probe=fd459af24b) | Nov 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [049356e4bc](https://linux-hardware.org/?probe=049356e4bc) | Nov 15, 2023 |
| MSI           | Thin GF63 12HW              | [bdac7a70aa](https://linux-hardware.org/?probe=bdac7a70aa) | Nov 14, 2023 |
| Acer          | Extensa 2540                | [22e65d0a5b](https://linux-hardware.org/?probe=22e65d0a5b) | Nov 14, 2023 |
| Acer          | Aspire A315-42              | [42d05f19a2](https://linux-hardware.org/?probe=42d05f19a2) | Nov 13, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | [137d579104](https://linux-hardware.org/?probe=137d579104) | Nov 13, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | [aacc7d1f61](https://linux-hardware.org/?probe=aacc7d1f61) | Nov 13, 2023 |
| Acer          | Aspire ES1-521              | [429add2d41](https://linux-hardware.org/?probe=429add2d41) | Nov 13, 2023 |
| HP            | Presario CQ57               | [0d4999d483](https://linux-hardware.org/?probe=0d4999d483) | Nov 13, 2023 |
| HP            | Laptop 15-dy2xxx            | [189c917237](https://linux-hardware.org/?probe=189c917237) | Nov 13, 2023 |
| HP            | ZBook 15 G2                 | [960b3732b0](https://linux-hardware.org/?probe=960b3732b0) | Nov 13, 2023 |
| Toshiba       | Satellite L40               | [0d2accfed1](https://linux-hardware.org/?probe=0d2accfed1) | Nov 13, 2023 |
| Apple         | MacBookPro16,2              | [bbc6a54b40](https://linux-hardware.org/?probe=bbc6a54b40) | Nov 12, 2023 |
| Lenovo        | ThinkPad Edge E535 32607... | [f5bea4eb8b](https://linux-hardware.org/?probe=f5bea4eb8b) | Nov 12, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [929afc7ae1](https://linux-hardware.org/?probe=929afc7ae1) | Nov 12, 2023 |
| HUAWEI        | BOM-WXX9                    | [d3fd2f491d](https://linux-hardware.org/?probe=d3fd2f491d) | Nov 12, 2023 |
| HP            | 15                          | [dbd704fdbb](https://linux-hardware.org/?probe=dbd704fdbb) | Nov 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [daab2f9dc6](https://linux-hardware.org/?probe=daab2f9dc6) | Nov 11, 2023 |
| Lenovo        | ThinkBook 13s G4 IAP 21A... | [e713ed7256](https://linux-hardware.org/?probe=e713ed7256) | Nov 11, 2023 |
| Lenovo        | ThinkPad L15 Gen 2a 20X8... | [4bf49cfb42](https://linux-hardware.org/?probe=4bf49cfb42) | Nov 11, 2023 |
| Timi          | Mi NoteBook Pro             | [f08c831e30](https://linux-hardware.org/?probe=f08c831e30) | Nov 11, 2023 |
| Apple         | MacBookPro8,1               | [3da6dfb4b3](https://linux-hardware.org/?probe=3da6dfb4b3) | Nov 11, 2023 |
| Lenovo        | IdeaPad Y500 20193          | [de5f1aa77e](https://linux-hardware.org/?probe=de5f1aa77e) | Nov 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [f4dc3b24c4](https://linux-hardware.org/?probe=f4dc3b24c4) | Nov 11, 2023 |
| HP            | Stream Notebook             | [f93159b053](https://linux-hardware.org/?probe=f93159b053) | Nov 11, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [b88ecdebac](https://linux-hardware.org/?probe=b88ecdebac) | Nov 10, 2023 |
| Dell          | Latitude E5430 non-vPro     | [518492850b](https://linux-hardware.org/?probe=518492850b) | Nov 10, 2023 |
| HP            | ProBook 4510s               | [9b83dea197](https://linux-hardware.org/?probe=9b83dea197) | Nov 10, 2023 |
| Aquarius      | NS585                       | [0f0c55bda1](https://linux-hardware.org/?probe=0f0c55bda1) | Nov 10, 2023 |
| Acer          | Aspire A315-23              | [95ea718240](https://linux-hardware.org/?probe=95ea718240) | Nov 10, 2023 |
| Lenovo        | ThinkPad T420 4180AZ8       | [089405c957](https://linux-hardware.org/?probe=089405c957) | Nov 09, 2023 |
| Apple         | MacBook2,1                  | [448165ceca](https://linux-hardware.org/?probe=448165ceca) | Nov 09, 2023 |
| ASUSTek       | S400CA                      | [0e5628865a](https://linux-hardware.org/?probe=0e5628865a) | Nov 09, 2023 |
| ASUSTek       | Vivobook Go E1504GA_E150... | [50b3f888e9](https://linux-hardware.org/?probe=50b3f888e9) | Nov 09, 2023 |
| ASUSTek       | Vivobook Go E1504GA_E150... | [a2c63a08f3](https://linux-hardware.org/?probe=a2c63a08f3) | Nov 09, 2023 |
| Acer          | Aspire A515-47              | [50a18dd494](https://linux-hardware.org/?probe=50a18dd494) | Nov 09, 2023 |
| Dell          | Latitude 5420               | [efa8caa859](https://linux-hardware.org/?probe=efa8caa859) | Nov 09, 2023 |
| Dell          | Latitude E5430 non-vPro     | [39e2c7584e](https://linux-hardware.org/?probe=39e2c7584e) | Nov 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [46458a043d](https://linux-hardware.org/?probe=46458a043d) | Nov 08, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [52b0129f48](https://linux-hardware.org/?probe=52b0129f48) | Nov 08, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [b05a5bff97](https://linux-hardware.org/?probe=b05a5bff97) | Nov 08, 2023 |
| MACHENIKE     | L16P                        | [c8e67672f3](https://linux-hardware.org/?probe=c8e67672f3) | Nov 08, 2023 |
| Samsung       | 767XCL                      | [beba8edd4f](https://linux-hardware.org/?probe=beba8edd4f) | Nov 08, 2023 |
| Apple         | MacBook5,1                  | [ed339d2cbb](https://linux-hardware.org/?probe=ed339d2cbb) | Nov 08, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [0fceea6321](https://linux-hardware.org/?probe=0fceea6321) | Nov 08, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [b111aacb49](https://linux-hardware.org/?probe=b111aacb49) | Nov 08, 2023 |
| Acer          | Aspire A515-43              | [6e215a4ade](https://linux-hardware.org/?probe=6e215a4ade) | Nov 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [54b91fa265](https://linux-hardware.org/?probe=54b91fa265) | Nov 08, 2023 |
| Dell          | Latitude 5414               | [ad924833a5](https://linux-hardware.org/?probe=ad924833a5) | Nov 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [696f32a866](https://linux-hardware.org/?probe=696f32a866) | Nov 08, 2023 |
| Apple         | MacBook5,2                  | [24a63b1a77](https://linux-hardware.org/?probe=24a63b1a77) | Nov 07, 2023 |
| Apple         | MacBookAir7,1               | [dcbc2d171e](https://linux-hardware.org/?probe=dcbc2d171e) | Nov 07, 2023 |
| Aquarius      | NS585                       | [a5b5734657](https://linux-hardware.org/?probe=a5b5734657) | Nov 07, 2023 |
| Aquarius      | NS585                       | [d9d5e97f89](https://linux-hardware.org/?probe=d9d5e97f89) | Nov 07, 2023 |
| Unknown       | Unknown                     | [988072756b](https://linux-hardware.org/?probe=988072756b) | Nov 07, 2023 |
| Aquarius      | NS585                       | [83a4894072](https://linux-hardware.org/?probe=83a4894072) | Nov 07, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [1d557ddec8](https://linux-hardware.org/?probe=1d557ddec8) | Nov 07, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [beca8ba507](https://linux-hardware.org/?probe=beca8ba507) | Nov 07, 2023 |
| ASUSTek       | X200CA                      | [a982252e30](https://linux-hardware.org/?probe=a982252e30) | Nov 07, 2023 |
| Lenovo        | ThinkPad T430 23475H2       | [3dcdf3830e](https://linux-hardware.org/?probe=3dcdf3830e) | Nov 07, 2023 |
| HP            | Pavilion Notebook           | [8cf5696a9e](https://linux-hardware.org/?probe=8cf5696a9e) | Nov 07, 2023 |
| MSI           | Modern 15 A10M              | [e1120cd270](https://linux-hardware.org/?probe=e1120cd270) | Nov 06, 2023 |
| HP            | EliteBook 8460p             | [cc6b66c576](https://linux-hardware.org/?probe=cc6b66c576) | Nov 06, 2023 |
| Aquarius      | NS585                       | [ddc8256647](https://linux-hardware.org/?probe=ddc8256647) | Nov 06, 2023 |
| Aquarius      | NS585                       | [2f4e49837d](https://linux-hardware.org/?probe=2f4e49837d) | Nov 06, 2023 |
| Aquarius      | NS585                       | [4fea63336a](https://linux-hardware.org/?probe=4fea63336a) | Nov 06, 2023 |
| HP            | 250 G7 Notebook PC          | [a2ad36d26c](https://linux-hardware.org/?probe=a2ad36d26c) | Nov 06, 2023 |
| Toshiba       | TECRA R950                  | [864877692e](https://linux-hardware.org/?probe=864877692e) | Nov 05, 2023 |
| ASUSTek       | X541NA                      | [f0399efc08](https://linux-hardware.org/?probe=f0399efc08) | Nov 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [92ed6d25c3](https://linux-hardware.org/?probe=92ed6d25c3) | Nov 05, 2023 |
| HP            | Mini 210-3000               | [8b55a876a9](https://linux-hardware.org/?probe=8b55a876a9) | Nov 05, 2023 |
| Google        | Nami                        | [19c94b9484](https://linux-hardware.org/?probe=19c94b9484) | Nov 05, 2023 |
| HP            | Laptop 15-bw0xx             | [7d9395e4a7](https://linux-hardware.org/?probe=7d9395e4a7) | Nov 05, 2023 |
| HP            | EliteBook 840 G3            | [1bb894cf19](https://linux-hardware.org/?probe=1bb894cf19) | Nov 04, 2023 |
| HP            | Pavilion dv7                | [6a44cc2c3c](https://linux-hardware.org/?probe=6a44cc2c3c) | Nov 04, 2023 |
| Google        | Bluebird                    | [55dbc11653](https://linux-hardware.org/?probe=55dbc11653) | Nov 04, 2023 |
| Google        | Bluebird                    | [9e12130a28](https://linux-hardware.org/?probe=9e12130a28) | Nov 04, 2023 |
| HP            | OMEN by Laptop 17-ck1xxx    | [bea6a6babf](https://linux-hardware.org/?probe=bea6a6babf) | Nov 04, 2023 |
| Lenovo        | ThinkPad T530 2429F27       | [0767db36fe](https://linux-hardware.org/?probe=0767db36fe) | Nov 04, 2023 |
| Dell          | Precision 7560              | [54a8deb305](https://linux-hardware.org/?probe=54a8deb305) | Nov 04, 2023 |
| ASUSTek       | X551CA                      | [20bee22e0a](https://linux-hardware.org/?probe=20bee22e0a) | Nov 03, 2023 |
| Dell          | Latitude E6420              | [43ccf36bf0](https://linux-hardware.org/?probe=43ccf36bf0) | Nov 03, 2023 |
| Google        | Enguarde                    | [bc6a541eb9](https://linux-hardware.org/?probe=bc6a541eb9) | Nov 03, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [8b855ce4f4](https://linux-hardware.org/?probe=8b855ce4f4) | Nov 03, 2023 |
| Lenovo        | G500s 20245                 | [c4aa915297](https://linux-hardware.org/?probe=c4aa915297) | Nov 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1bdfa38b3e](https://linux-hardware.org/?probe=1bdfa38b3e) | Nov 03, 2023 |
| Lenovo        | IdeaPad Y500 20193          | [f96f6e6127](https://linux-hardware.org/?probe=f96f6e6127) | Nov 03, 2023 |
| ASUSTek       | X205TA                      | [b29e9ebfbe](https://linux-hardware.org/?probe=b29e9ebfbe) | Nov 03, 2023 |
| HP            | 250 G7 Notebook PC          | [1889111d8a](https://linux-hardware.org/?probe=1889111d8a) | Nov 03, 2023 |
| ASUSTek       | G750JX                      | [9493bec7e6](https://linux-hardware.org/?probe=9493bec7e6) | Nov 02, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [7c06ac2664](https://linux-hardware.org/?probe=7c06ac2664) | Nov 02, 2023 |
| Google        | Nasher360                   | [0d1cc1b584](https://linux-hardware.org/?probe=0d1cc1b584) | Nov 02, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [df4f43ca44](https://linux-hardware.org/?probe=df4f43ca44) | Nov 01, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [bb5bbc3e51](https://linux-hardware.org/?probe=bb5bbc3e51) | Nov 01, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [ac563e5542](https://linux-hardware.org/?probe=ac563e5542) | Nov 01, 2023 |
| HP            | Laptop 15s-eq1xxx           | [075049b538](https://linux-hardware.org/?probe=075049b538) | Nov 01, 2023 |
| Dell          | Precision M4700             | [1d7e76c1d9](https://linux-hardware.org/?probe=1d7e76c1d9) | Nov 01, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [317aadad91](https://linux-hardware.org/?probe=317aadad91) | Nov 01, 2023 |
| Dell          | Vostro 5590                 | [300630cf8c](https://linux-hardware.org/?probe=300630cf8c) | Nov 01, 2023 |
| Dell          | Latitude 5480               | [1bf5aeba87](https://linux-hardware.org/?probe=1bf5aeba87) | Nov 01, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [2bdd27dc18](https://linux-hardware.org/?probe=2bdd27dc18) | Oct 31, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [cb35a8d8f6](https://linux-hardware.org/?probe=cb35a8d8f6) | Oct 31, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [4ebd30711e](https://linux-hardware.org/?probe=4ebd30711e) | Oct 31, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [a664733aaf](https://linux-hardware.org/?probe=a664733aaf) | Oct 31, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [72131fb5de](https://linux-hardware.org/?probe=72131fb5de) | Oct 31, 2023 |
| VANT          | MOOVE3-15                   | [5fc04a6d0a](https://linux-hardware.org/?probe=5fc04a6d0a) | Oct 31, 2023 |
| Apple         | MacBookPro9,1               | [8f7c5b801b](https://linux-hardware.org/?probe=8f7c5b801b) | Oct 31, 2023 |
| Apple         | MacBookPro9,1               | [4e15275faa](https://linux-hardware.org/?probe=4e15275faa) | Oct 31, 2023 |
| HP            | Victus by Gaming Laptop ... | [0f4fa9169b](https://linux-hardware.org/?probe=0f4fa9169b) | Oct 31, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C10... | [2f63bfb399](https://linux-hardware.org/?probe=2f63bfb399) | Oct 31, 2023 |
| VANT          | MOOVE3-15                   | [7e12621e6d](https://linux-hardware.org/?probe=7e12621e6d) | Oct 31, 2023 |
| Timi          | RedmiBook Pro 14S           | [780e721e24](https://linux-hardware.org/?probe=780e721e24) | Oct 30, 2023 |
| Lenovo        | ThinkPad X260 VB6R77903H    | [c4baf8a67b](https://linux-hardware.org/?probe=c4baf8a67b) | Oct 30, 2023 |
| THUNDEROBO... | 911AirD                     | [698adeeba7](https://linux-hardware.org/?probe=698adeeba7) | Oct 30, 2023 |
| Dell          | XPS 15 9520                 | [0fb7ced892](https://linux-hardware.org/?probe=0fb7ced892) | Oct 30, 2023 |
| Google        | Blooguard                   | [cd817fb666](https://linux-hardware.org/?probe=cd817fb666) | Oct 30, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [995b159589](https://linux-hardware.org/?probe=995b159589) | Oct 30, 2023 |
| Gigabyte      | A5 X1                       | [981be88a61](https://linux-hardware.org/?probe=981be88a61) | Oct 30, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [4aceca5660](https://linux-hardware.org/?probe=4aceca5660) | Oct 28, 2023 |
| Acer          | Aspire 4752                 | [ce321700bc](https://linux-hardware.org/?probe=ce321700bc) | Oct 28, 2023 |
| Lenovo        | ThinkPad T15g Gen 2i 20Y... | [dcd6988b7a](https://linux-hardware.org/?probe=dcd6988b7a) | Oct 28, 2023 |
| TELECOMITA... | M7x0S                       | [feabc7e111](https://linux-hardware.org/?probe=feabc7e111) | Oct 28, 2023 |
| MSI           | WS63 7RK                    | [dcfa2c2f75](https://linux-hardware.org/?probe=dcfa2c2f75) | Oct 27, 2023 |
| Lenovo        | ThinkPad X230 2325SDE       | [cbdbd4a156](https://linux-hardware.org/?probe=cbdbd4a156) | Oct 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [d8bfe77d00](https://linux-hardware.org/?probe=d8bfe77d00) | Oct 27, 2023 |
| Lenovo        | ThinkPad T470 20HES0FW00    | [198bee98eb](https://linux-hardware.org/?probe=198bee98eb) | Oct 27, 2023 |
| Lenovo        | G50-70 20351                | [39e2fb6be6](https://linux-hardware.org/?probe=39e2fb6be6) | Oct 27, 2023 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [bdf8012e05](https://linux-hardware.org/?probe=bdf8012e05) | Oct 27, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [67b966e75c](https://linux-hardware.org/?probe=67b966e75c) | Oct 27, 2023 |
| Google        | Enguarde                    | [074b44ce16](https://linux-hardware.org/?probe=074b44ce16) | Oct 26, 2023 |
| Acer          | Aspire 5750G                | [afe742ceca](https://linux-hardware.org/?probe=afe742ceca) | Oct 26, 2023 |
| Dell          | Latitude 5414               | [78fb4f9907](https://linux-hardware.org/?probe=78fb4f9907) | Oct 26, 2023 |
| Medion        | Unknown                     | [ffcdfb3003](https://linux-hardware.org/?probe=ffcdfb3003) | Oct 26, 2023 |
| HP            | ProBook 4530s               | [b86df6ad72](https://linux-hardware.org/?probe=b86df6ad72) | Oct 26, 2023 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [cc3370083d](https://linux-hardware.org/?probe=cc3370083d) | Oct 26, 2023 |
| Exo           | Smart Serie R               | [d68b300ca7](https://linux-hardware.org/?probe=d68b300ca7) | Oct 26, 2023 |
| Toshiba       | Satellite L455D             | [29337c2310](https://linux-hardware.org/?probe=29337c2310) | Oct 26, 2023 |
| HUAWEI        | KLVL-WXXW                   | [303c4197c7](https://linux-hardware.org/?probe=303c4197c7) | Oct 26, 2023 |
| HP            | Compaq 15                   | [83fab35dec](https://linux-hardware.org/?probe=83fab35dec) | Oct 26, 2023 |
| Dell          | Latitude 5414               | [692b53f9d9](https://linux-hardware.org/?probe=692b53f9d9) | Oct 26, 2023 |
| HP            | Compaq 15                   | [41ada9e77d](https://linux-hardware.org/?probe=41ada9e77d) | Oct 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [bfe12f37dc](https://linux-hardware.org/?probe=bfe12f37dc) | Oct 25, 2023 |
| Acer          | Aspire 5750G                | [b726b22da1](https://linux-hardware.org/?probe=b726b22da1) | Oct 25, 2023 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [c66ebc8e70](https://linux-hardware.org/?probe=c66ebc8e70) | Oct 25, 2023 |
| Google        | Reks                        | [d397eae4e5](https://linux-hardware.org/?probe=d397eae4e5) | Oct 25, 2023 |
| Acer          | Aspire ES1-521              | [2df6fb3e2a](https://linux-hardware.org/?probe=2df6fb3e2a) | Oct 25, 2023 |
| MSI           | Katana GF76 11SC            | [b1a5449e72](https://linux-hardware.org/?probe=b1a5449e72) | Oct 25, 2023 |
| HP            | Victus by Gaming Laptop ... | [71a22f4706](https://linux-hardware.org/?probe=71a22f4706) | Oct 25, 2023 |
| HP            | Laptop 15-dw3xxx            | [8994962017](https://linux-hardware.org/?probe=8994962017) | Oct 25, 2023 |
| Lenovo        | ThinkPad T480 20L6S29D00    | [b270ca3670](https://linux-hardware.org/?probe=b270ca3670) | Oct 24, 2023 |
| Lenovo        | ThinkPad T440p 20AWS18U0... | [1406d2f4d5](https://linux-hardware.org/?probe=1406d2f4d5) | Oct 24, 2023 |
| Medion        | Unknown                     | [fa168b5e75](https://linux-hardware.org/?probe=fa168b5e75) | Oct 24, 2023 |
| Lenovo        | ThinkPad T440p 20AWS18U0... | [56fa067caa](https://linux-hardware.org/?probe=56fa067caa) | Oct 24, 2023 |
| HP            | EliteBook 8740w             | [3669a01d21](https://linux-hardware.org/?probe=3669a01d21) | Oct 24, 2023 |
| Notebook      | P7xxDM(-G)                  | [bb211b2fb4](https://linux-hardware.org/?probe=bb211b2fb4) | Oct 24, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | [dd704a643f](https://linux-hardware.org/?probe=dd704a643f) | Oct 24, 2023 |
| Acer          | Aspire 7750G                | [91006bdfa7](https://linux-hardware.org/?probe=91006bdfa7) | Oct 24, 2023 |
| Alienware     | m15 R6                      | [c6711f7b02](https://linux-hardware.org/?probe=c6711f7b02) | Oct 24, 2023 |
| ASUSTek       | G551JX                      | [db16c87fe8](https://linux-hardware.org/?probe=db16c87fe8) | Oct 24, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [8754714bce](https://linux-hardware.org/?probe=8754714bce) | Oct 23, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [f4375f7115](https://linux-hardware.org/?probe=f4375f7115) | Oct 23, 2023 |
| Aquarius      | NS585                       | [3c793ad14b](https://linux-hardware.org/?probe=3c793ad14b) | Oct 23, 2023 |
| Aquarius      | NS585                       | [9e7366fb3a](https://linux-hardware.org/?probe=9e7366fb3a) | Oct 23, 2023 |
| Dell          | XPS 9315                    | [c03a4ad29d](https://linux-hardware.org/?probe=c03a4ad29d) | Oct 23, 2023 |
| Timi          | Mi NoteBook Pro             | [470eb40837](https://linux-hardware.org/?probe=470eb40837) | Oct 23, 2023 |
| Acer          | Aspire E5-573               | [d83f4bf9ad](https://linux-hardware.org/?probe=d83f4bf9ad) | Oct 23, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1WH0... | [4d383aebdc](https://linux-hardware.org/?probe=4d383aebdc) | Oct 23, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1WH0... | [4cb151fdfe](https://linux-hardware.org/?probe=4cb151fdfe) | Oct 23, 2023 |
| Dell          | XPS 13 9300                 | [9d7ecc567c](https://linux-hardware.org/?probe=9d7ecc567c) | Oct 23, 2023 |
| Dell          | Precision 3571              | [a2ba806246](https://linux-hardware.org/?probe=a2ba806246) | Oct 22, 2023 |
| Dell          | Precision 3571              | [efedaee27d](https://linux-hardware.org/?probe=efedaee27d) | Oct 22, 2023 |
| Dell          | Inspiron 6000               | [be4108e195](https://linux-hardware.org/?probe=be4108e195) | Oct 22, 2023 |
| Dell          | XPS 15 9560                 | [c2c4d81d07](https://linux-hardware.org/?probe=c2c4d81d07) | Oct 22, 2023 |
| GPU Compan... | GWTC51427                   | [69b6cd7a6f](https://linux-hardware.org/?probe=69b6cd7a6f) | Oct 22, 2023 |
| Acer          | Swift SF314-42              | [e19b58f8be](https://linux-hardware.org/?probe=e19b58f8be) | Oct 21, 2023 |
| Lenovo        | V130-15IGM 81HL             | [fc8d54a39c](https://linux-hardware.org/?probe=fc8d54a39c) | Oct 21, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [5e57624ceb](https://linux-hardware.org/?probe=5e57624ceb) | Oct 21, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [f30ccc13f5](https://linux-hardware.org/?probe=f30ccc13f5) | Oct 21, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [d9a8c7946e](https://linux-hardware.org/?probe=d9a8c7946e) | Oct 20, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [5cac857cd9](https://linux-hardware.org/?probe=5cac857cd9) | Oct 20, 2023 |
| Lenovo        | V15-IIL 82C5                | [50f6d4cb01](https://linux-hardware.org/?probe=50f6d4cb01) | Oct 20, 2023 |
| MSI           | Alpha 17 B5EEK              | [125e76df80](https://linux-hardware.org/?probe=125e76df80) | Oct 20, 2023 |
| MSI           | Alpha 17 B5EEK              | [3a5c553fcb](https://linux-hardware.org/?probe=3a5c553fcb) | Oct 20, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [2147efec4e](https://linux-hardware.org/?probe=2147efec4e) | Oct 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JK0... | [f35c9d006e](https://linux-hardware.org/?probe=f35c9d006e) | Oct 20, 2023 |
| Lenovo        | ThinkPad T470 20HES4VB00    | [423a16c64a](https://linux-hardware.org/?probe=423a16c64a) | Oct 20, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | [64929e25f7](https://linux-hardware.org/?probe=64929e25f7) | Oct 20, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | [da8f06a8e0](https://linux-hardware.org/?probe=da8f06a8e0) | Oct 19, 2023 |
| HP            | Laptop 15s-eq2xxx           | [9c9781a7ee](https://linux-hardware.org/?probe=9c9781a7ee) | Oct 19, 2023 |
| Dell          | XPS 13 9380                 | [a108313537](https://linux-hardware.org/?probe=a108313537) | Oct 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a8e2b482f4](https://linux-hardware.org/?probe=a8e2b482f4) | Oct 19, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [81bfadb2d9](https://linux-hardware.org/?probe=81bfadb2d9) | Oct 18, 2023 |
| Dell          | Precision 7560              | [847d5dfd06](https://linux-hardware.org/?probe=847d5dfd06) | Oct 18, 2023 |
| Acer          | Aspire 5920G                | [5921ebc3f7](https://linux-hardware.org/?probe=5921ebc3f7) | Oct 18, 2023 |
| Acer          | Aspire 5920G                | [b6619c64fd](https://linux-hardware.org/?probe=b6619c64fd) | Oct 18, 2023 |
| Dell          | Latitude E6420              | [f703c6bd74](https://linux-hardware.org/?probe=f703c6bd74) | Oct 17, 2023 |
| Dell          | Latitude E6430              | [54d411b12d](https://linux-hardware.org/?probe=54d411b12d) | Oct 17, 2023 |
| Google        | Reks                        | [1053eb8fee](https://linux-hardware.org/?probe=1053eb8fee) | Oct 17, 2023 |
| Google        | Reks                        | [84b42b74a0](https://linux-hardware.org/?probe=84b42b74a0) | Oct 17, 2023 |
| HP            | ProBook 645 G1              | [d1eeca057f](https://linux-hardware.org/?probe=d1eeca057f) | Oct 17, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [f9a0ba2cba](https://linux-hardware.org/?probe=f9a0ba2cba) | Oct 17, 2023 |
| Unknown       | Unknown                     | [f776cdb186](https://linux-hardware.org/?probe=f776cdb186) | Oct 17, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [902d95cec2](https://linux-hardware.org/?probe=902d95cec2) | Oct 17, 2023 |
| HP            | EliteBook 820 G2            | [14f5dbdc5a](https://linux-hardware.org/?probe=14f5dbdc5a) | Oct 17, 2023 |
| Acer          | Aspire V3-771               | [e56b3d3602](https://linux-hardware.org/?probe=e56b3d3602) | Oct 17, 2023 |
| Acer          | Aspire 7750G                | [6c7f890049](https://linux-hardware.org/?probe=6c7f890049) | Oct 17, 2023 |
| Acer          | Aspire A515-54              | [a89d6c8f24](https://linux-hardware.org/?probe=a89d6c8f24) | Oct 17, 2023 |
| Dell          | Precision 7560              | [5d9dd29a22](https://linux-hardware.org/?probe=5d9dd29a22) | Oct 17, 2023 |
| Google        | Reks                        | [7610580a91](https://linux-hardware.org/?probe=7610580a91) | Oct 16, 2023 |
| HP            | Laptop 15-fd0xxx            | [0e6cc9fc48](https://linux-hardware.org/?probe=0e6cc9fc48) | Oct 16, 2023 |
| Acer          | Aspire 7750G                | [2a2d5e2425](https://linux-hardware.org/?probe=2a2d5e2425) | Oct 16, 2023 |
| ASUSTek       | 1015PN                      | [b6cbd56a75](https://linux-hardware.org/?probe=b6cbd56a75) | Oct 16, 2023 |
| Apple         | MacBookPro8,1               | [abfce57204](https://linux-hardware.org/?probe=abfce57204) | Oct 16, 2023 |
| Lenovo        | ThinkPad E565 20EY000XUK    | [b7cf6113c4](https://linux-hardware.org/?probe=b7cf6113c4) | Oct 16, 2023 |
| HUAWEI        | HVY-WXX9                    | [57e0cf4149](https://linux-hardware.org/?probe=57e0cf4149) | Oct 16, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [2408be3605](https://linux-hardware.org/?probe=2408be3605) | Oct 16, 2023 |
| MSI           | GF63 Thin 11SC              | [1072e8d802](https://linux-hardware.org/?probe=1072e8d802) | Oct 16, 2023 |
| HP            | 250 G8 Notebook PC          | [38c84587d8](https://linux-hardware.org/?probe=38c84587d8) | Oct 16, 2023 |
| Apple         | MacBookAir4,1               | [f63091b76b](https://linux-hardware.org/?probe=f63091b76b) | Oct 16, 2023 |
| Lenovo        | ThinkPad P16v Gen 1 21FC... | [33ce923fc9](https://linux-hardware.org/?probe=33ce923fc9) | Oct 15, 2023 |
| Apple         | MacBookPro6,2               | [1df7e29365](https://linux-hardware.org/?probe=1df7e29365) | Oct 15, 2023 |
| Lenovo        | G50-70 20351                | [bdd8aeaf43](https://linux-hardware.org/?probe=bdd8aeaf43) | Oct 14, 2023 |
| HP            | Victus by Laptop 16-d1xx... | [50ebc1407b](https://linux-hardware.org/?probe=50ebc1407b) | Oct 14, 2023 |
| Dell          | Inspiron 3501               | [a1ada382fa](https://linux-hardware.org/?probe=a1ada382fa) | Oct 14, 2023 |
| Dell          | Latitude 5400               | [26c8a94f7f](https://linux-hardware.org/?probe=26c8a94f7f) | Oct 14, 2023 |
| Fujitsu       | LIFEBOOK T5010              | [f35263745a](https://linux-hardware.org/?probe=f35263745a) | Oct 14, 2023 |
| Dell          | Latitude 5414               | [2984ae5140](https://linux-hardware.org/?probe=2984ae5140) | Oct 14, 2023 |
| Google        | Reks                        | [066e8305fe](https://linux-hardware.org/?probe=066e8305fe) | Oct 13, 2023 |
| Google        | Reks                        | [acb8eb7f44](https://linux-hardware.org/?probe=acb8eb7f44) | Oct 13, 2023 |
| Google        | Reks                        | [707eb71f31](https://linux-hardware.org/?probe=707eb71f31) | Oct 13, 2023 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [94e6d9d3cb](https://linux-hardware.org/?probe=94e6d9d3cb) | Oct 13, 2023 |
| Google        | Reks                        | [4bc10c8b6b](https://linux-hardware.org/?probe=4bc10c8b6b) | Oct 13, 2023 |
| Lenovo        | V17 G4 IRU 83A2             | [5298e96c35](https://linux-hardware.org/?probe=5298e96c35) | Oct 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [7ee4351584](https://linux-hardware.org/?probe=7ee4351584) | Oct 13, 2023 |
| Apple         | MacBookPro9,2               | [27b7cf72ac](https://linux-hardware.org/?probe=27b7cf72ac) | Oct 13, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [02c3723dae](https://linux-hardware.org/?probe=02c3723dae) | Oct 12, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [d874291459](https://linux-hardware.org/?probe=d874291459) | Oct 12, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [b53da36041](https://linux-hardware.org/?probe=b53da36041) | Oct 12, 2023 |
| Google        | Reks                        | [20f8a11067](https://linux-hardware.org/?probe=20f8a11067) | Oct 12, 2023 |
| Google        | Reks                        | [4e35f7ebe4](https://linux-hardware.org/?probe=4e35f7ebe4) | Oct 12, 2023 |
| Google        | Reks                        | [41c6c948bb](https://linux-hardware.org/?probe=41c6c948bb) | Oct 12, 2023 |
| ASUSTek       | X541UJ                      | [c061e67481](https://linux-hardware.org/?probe=c061e67481) | Oct 12, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [24adbfd09a](https://linux-hardware.org/?probe=24adbfd09a) | Oct 11, 2023 |
| Google        | Reks                        | [1854f5e2fb](https://linux-hardware.org/?probe=1854f5e2fb) | Oct 11, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [9de2f282f8](https://linux-hardware.org/?probe=9de2f282f8) | Oct 11, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [dc4ce65d14](https://linux-hardware.org/?probe=dc4ce65d14) | Oct 11, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [c26fe51dd5](https://linux-hardware.org/?probe=c26fe51dd5) | Oct 11, 2023 |
| Google        | Reks                        | [f9857342ec](https://linux-hardware.org/?probe=f9857342ec) | Oct 11, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [4a0728b60c](https://linux-hardware.org/?probe=4a0728b60c) | Oct 11, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [63c9bedd9d](https://linux-hardware.org/?probe=63c9bedd9d) | Oct 11, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [77fe4b27cf](https://linux-hardware.org/?probe=77fe4b27cf) | Oct 11, 2023 |
| Google        | Reks                        | [9b2d9c0f7c](https://linux-hardware.org/?probe=9b2d9c0f7c) | Oct 11, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [a735df7685](https://linux-hardware.org/?probe=a735df7685) | Oct 11, 2023 |
| Google        | Reks                        | [e78d454248](https://linux-hardware.org/?probe=e78d454248) | Oct 11, 2023 |
| Google        | Reks                        | [e7c6590991](https://linux-hardware.org/?probe=e7c6590991) | Oct 11, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [627ce99f24](https://linux-hardware.org/?probe=627ce99f24) | Oct 11, 2023 |
| Google        | Reks                        | [cc53305ade](https://linux-hardware.org/?probe=cc53305ade) | Oct 11, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [d957b0375b](https://linux-hardware.org/?probe=d957b0375b) | Oct 11, 2023 |
| Google        | Reks                        | [286fdb3692](https://linux-hardware.org/?probe=286fdb3692) | Oct 11, 2023 |
| ASUSTek       | X541UJ                      | [0cb7dbb73b](https://linux-hardware.org/?probe=0cb7dbb73b) | Oct 11, 2023 |
| HP            | Laptop 15-fc0xxx            | [670b2194c0](https://linux-hardware.org/?probe=670b2194c0) | Oct 11, 2023 |
| Prestigio     | Visconte Quad 3GK           | [5ffdb7e479](https://linux-hardware.org/?probe=5ffdb7e479) | Oct 11, 2023 |
| Google        | Reks                        | [4bd21164ba](https://linux-hardware.org/?probe=4bd21164ba) | Oct 10, 2023 |
| Google        | Reks                        | [e574b981ae](https://linux-hardware.org/?probe=e574b981ae) | Oct 10, 2023 |
| Google        | Reks                        | [5d44d0021b](https://linux-hardware.org/?probe=5d44d0021b) | Oct 10, 2023 |
| Google        | Reks                        | [a4300f1369](https://linux-hardware.org/?probe=a4300f1369) | Oct 10, 2023 |
| Google        | Reks                        | [9b338e1cfb](https://linux-hardware.org/?probe=9b338e1cfb) | Oct 10, 2023 |
| Google        | Reks                        | [8c2146eff1](https://linux-hardware.org/?probe=8c2146eff1) | Oct 10, 2023 |
| Google        | Reks                        | [2d878f9b40](https://linux-hardware.org/?probe=2d878f9b40) | Oct 10, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [8ca2bf7fc9](https://linux-hardware.org/?probe=8ca2bf7fc9) | Oct 10, 2023 |
| Google        | Reks                        | [b206e1538b](https://linux-hardware.org/?probe=b206e1538b) | Oct 10, 2023 |
| Google        | Reks                        | [3cf1a391be](https://linux-hardware.org/?probe=3cf1a391be) | Oct 10, 2023 |
| Google        | Reks                        | [d694213be1](https://linux-hardware.org/?probe=d694213be1) | Oct 10, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [f91905858e](https://linux-hardware.org/?probe=f91905858e) | Oct 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [c1c56db09e](https://linux-hardware.org/?probe=c1c56db09e) | Oct 10, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [f95efe1e80](https://linux-hardware.org/?probe=f95efe1e80) | Oct 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [b3635689de](https://linux-hardware.org/?probe=b3635689de) | Oct 09, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [6d2a6c2a6f](https://linux-hardware.org/?probe=6d2a6c2a6f) | Oct 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [3c54fe835e](https://linux-hardware.org/?probe=3c54fe835e) | Oct 09, 2023 |
| MSI           | Katana GF66 11UG            | [0816e0912b](https://linux-hardware.org/?probe=0816e0912b) | Oct 09, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [a41b75e081](https://linux-hardware.org/?probe=a41b75e081) | Oct 09, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [ac6149e371](https://linux-hardware.org/?probe=ac6149e371) | Oct 08, 2023 |
| TUXEDO        | InfinityBook S 14 v5        | [7ad7f14fea](https://linux-hardware.org/?probe=7ad7f14fea) | Oct 08, 2023 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [91f26dd2c7](https://linux-hardware.org/?probe=91f26dd2c7) | Oct 08, 2023 |
| Acer          | Swift SF314-56G             | [2696a8d9c0](https://linux-hardware.org/?probe=2696a8d9c0) | Oct 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [8678e7aace](https://linux-hardware.org/?probe=8678e7aace) | Oct 08, 2023 |
| AXDIA Inte... | MYBOOK PRO 14 SE            | [344ed10ccd](https://linux-hardware.org/?probe=344ed10ccd) | Oct 07, 2023 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [a830045a2a](https://linux-hardware.org/?probe=a830045a2a) | Oct 07, 2023 |
| ASUSTek       | T100TAS                     | [f6a5a046b6](https://linux-hardware.org/?probe=f6a5a046b6) | Oct 07, 2023 |
| ASUSTek       | T100TAS                     | [c7e6160070](https://linux-hardware.org/?probe=c7e6160070) | Oct 07, 2023 |
| HP            | ENVY Laptop 13-aq0xxx       | [45be4f4f29](https://linux-hardware.org/?probe=45be4f4f29) | Oct 07, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [37eeaf5771](https://linux-hardware.org/?probe=37eeaf5771) | Oct 06, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [275c59d0de](https://linux-hardware.org/?probe=275c59d0de) | Oct 06, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [212dd29010](https://linux-hardware.org/?probe=212dd29010) | Oct 06, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [5928c10f4a](https://linux-hardware.org/?probe=5928c10f4a) | Oct 06, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [3bc146338b](https://linux-hardware.org/?probe=3bc146338b) | Oct 06, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [82b7f17c90](https://linux-hardware.org/?probe=82b7f17c90) | Oct 06, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [5f740996ed](https://linux-hardware.org/?probe=5f740996ed) | Oct 06, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [64ffddf53c](https://linux-hardware.org/?probe=64ffddf53c) | Oct 06, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [26bb748122](https://linux-hardware.org/?probe=26bb748122) | Oct 06, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [a9fb0ad7d5](https://linux-hardware.org/?probe=a9fb0ad7d5) | Oct 06, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [5f9cd4dfbe](https://linux-hardware.org/?probe=5f9cd4dfbe) | Oct 06, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [7f948138a8](https://linux-hardware.org/?probe=7f948138a8) | Oct 06, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [9b11272e7a](https://linux-hardware.org/?probe=9b11272e7a) | Oct 06, 2023 |
| Direkt-Tek    | DTLAPY116-1                 | [aaa295fa26](https://linux-hardware.org/?probe=aaa295fa26) | Oct 06, 2023 |
| Dell          | Latitude 7275               | [f1892c721d](https://linux-hardware.org/?probe=f1892c721d) | Oct 06, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [1c741fc115](https://linux-hardware.org/?probe=1c741fc115) | Oct 06, 2023 |
| Apple         | MacBookPro12,1              | [50fc69b25f](https://linux-hardware.org/?probe=50fc69b25f) | Oct 06, 2023 |
| HP            | ZBook 14 G2                 | [e1b3f48f3c](https://linux-hardware.org/?probe=e1b3f48f3c) | Oct 05, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [fc37084670](https://linux-hardware.org/?probe=fc37084670) | Oct 05, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [763ef47e79](https://linux-hardware.org/?probe=763ef47e79) | Oct 05, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [1edb630be1](https://linux-hardware.org/?probe=1edb630be1) | Oct 05, 2023 |
| Dell          | Vostro 3490                 | [83f825d43e](https://linux-hardware.org/?probe=83f825d43e) | Oct 05, 2023 |
| Dell          | Latitude 7290               | [8822662fb7](https://linux-hardware.org/?probe=8822662fb7) | Oct 05, 2023 |
| Acer          | Aspire V5-531               | [555d578f86](https://linux-hardware.org/?probe=555d578f86) | Oct 05, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [8ba8fa3184](https://linux-hardware.org/?probe=8ba8fa3184) | Oct 05, 2023 |
| Acer          | Aspire A317-54              | [12732988d1](https://linux-hardware.org/?probe=12732988d1) | Oct 05, 2023 |
| HP            | EliteBook 735 G6            | [94ac6e4439](https://linux-hardware.org/?probe=94ac6e4439) | Oct 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [258d726766](https://linux-hardware.org/?probe=258d726766) | Oct 04, 2023 |
| Lenovo        | ThinkPad P51 20HJS0RE02     | [892c35359f](https://linux-hardware.org/?probe=892c35359f) | Oct 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [03949619e9](https://linux-hardware.org/?probe=03949619e9) | Oct 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [627e882ad2](https://linux-hardware.org/?probe=627e882ad2) | Oct 04, 2023 |
| HP            | ZBook 17 G4                 | [ead2e4611e](https://linux-hardware.org/?probe=ead2e4611e) | Oct 04, 2023 |
| Acer          | Swift SF314-43              | [36d6c2e275](https://linux-hardware.org/?probe=36d6c2e275) | Oct 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [82820de211](https://linux-hardware.org/?probe=82820de211) | Oct 03, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [e80a668fc3](https://linux-hardware.org/?probe=e80a668fc3) | Oct 03, 2023 |
| Acer          | Aspire V5-531               | [b6a9eaaec5](https://linux-hardware.org/?probe=b6a9eaaec5) | Oct 03, 2023 |
| Notebook      | W65_67SJ                    | [4de813ee21](https://linux-hardware.org/?probe=4de813ee21) | Oct 03, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [48ee75db0b](https://linux-hardware.org/?probe=48ee75db0b) | Oct 03, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [9c6c3cf92b](https://linux-hardware.org/?probe=9c6c3cf92b) | Oct 03, 2023 |
| Toshiba       | Satellite P75-A             | [10da36f2b7](https://linux-hardware.org/?probe=10da36f2b7) | Oct 03, 2023 |
| Lenovo        | ThinkPad E580 20KS003WUS    | [5aed5aaa9b](https://linux-hardware.org/?probe=5aed5aaa9b) | Oct 03, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JNC... | [fc95f3feef](https://linux-hardware.org/?probe=fc95f3feef) | Oct 03, 2023 |
| Lenovo        | ThinkPad T450 20BUA007SG    | [85af04a1cc](https://linux-hardware.org/?probe=85af04a1cc) | Oct 03, 2023 |
| Acer          | TravelMate P414-51          | [520fe0b494](https://linux-hardware.org/?probe=520fe0b494) | Oct 03, 2023 |
| Acer          | Swift SF314-56G             | [15b613a264](https://linux-hardware.org/?probe=15b613a264) | Oct 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [3a8b2b229a](https://linux-hardware.org/?probe=3a8b2b229a) | Oct 03, 2023 |
| Dell          | Wyse 5470                   | [301b504179](https://linux-hardware.org/?probe=301b504179) | Oct 03, 2023 |
| Google        | Reks                        | [00fe240f8b](https://linux-hardware.org/?probe=00fe240f8b) | Oct 02, 2023 |
| Google        | Reks                        | [c4dc39039e](https://linux-hardware.org/?probe=c4dc39039e) | Oct 02, 2023 |
| Google        | Reks                        | [0d9a805f5a](https://linux-hardware.org/?probe=0d9a805f5a) | Oct 02, 2023 |
| Google        | Reks                        | [22c6ac7ba8](https://linux-hardware.org/?probe=22c6ac7ba8) | Oct 02, 2023 |
| Google        | Reks                        | [0db25d0a2f](https://linux-hardware.org/?probe=0db25d0a2f) | Oct 02, 2023 |
| Lenovo        | ThinkPad T480 20L6S5LF00    | [9637400928](https://linux-hardware.org/?probe=9637400928) | Oct 02, 2023 |
| Compaq        | 420                         | [b327579e60](https://linux-hardware.org/?probe=b327579e60) | Oct 02, 2023 |
| VALE          | Notebook Classic C140       | [0516711124](https://linux-hardware.org/?probe=0516711124) | Oct 02, 2023 |
| Google        | Treeya                      | [b2251358a1](https://linux-hardware.org/?probe=b2251358a1) | Oct 02, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [cc181da4e1](https://linux-hardware.org/?probe=cc181da4e1) | Oct 02, 2023 |
| MSI           | GF63 Thin 9SC               | [3670f5ea70](https://linux-hardware.org/?probe=3670f5ea70) | Oct 02, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [f35e389d78](https://linux-hardware.org/?probe=f35e389d78) | Oct 02, 2023 |
| IX1401        | Unknown                     | [8014a1028b](https://linux-hardware.org/?probe=8014a1028b) | Oct 02, 2023 |
| Dell          | Inspiron 5570               | [93e66c7d47](https://linux-hardware.org/?probe=93e66c7d47) | Oct 02, 2023 |
| HP            | Presario CQ57               | [e83f052dc8](https://linux-hardware.org/?probe=e83f052dc8) | Oct 01, 2023 |
| Lenovo        | ThinkPad T480 20L6SA5Q2V    | [d9262b2225](https://linux-hardware.org/?probe=d9262b2225) | Oct 01, 2023 |
| Acer          | Aspire E1-571               | [2e7aba6432](https://linux-hardware.org/?probe=2e7aba6432) | Oct 01, 2023 |
| Acer          | AOA150                      | [969a729098](https://linux-hardware.org/?probe=969a729098) | Oct 01, 2023 |
| Apple         | MacBook4,1                  | [d17d6d2b70](https://linux-hardware.org/?probe=d17d6d2b70) | Oct 01, 2023 |
| HP            | Pavilion Laptop 15t-eg30... | [ed7bf5aee1](https://linux-hardware.org/?probe=ed7bf5aee1) | Oct 01, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [83d91ea2fe](https://linux-hardware.org/?probe=83d91ea2fe) | Sep 30, 2023 |
| Lenovo        | ThinkPad X260 VB6R77903H    | [e7dad368d2](https://linux-hardware.org/?probe=e7dad368d2) | Sep 30, 2023 |
| Lenovo        | ThinkPad X260 VB6R77903H    | [de3079ae33](https://linux-hardware.org/?probe=de3079ae33) | Sep 30, 2023 |
| IX1401        | Unknown                     | [c77c1d010e](https://linux-hardware.org/?probe=c77c1d010e) | Sep 30, 2023 |
| HP            | Pavilion dv5                | [0b1da8643f](https://linux-hardware.org/?probe=0b1da8643f) | Sep 30, 2023 |
| Alienware     | m15 R4                      | [a67899ed06](https://linux-hardware.org/?probe=a67899ed06) | Sep 30, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6555        | [703170e428](https://linux-hardware.org/?probe=703170e428) | Sep 30, 2023 |
| HP            | Notebook                    | [193ec8deb3](https://linux-hardware.org/?probe=193ec8deb3) | Sep 30, 2023 |
| HP            | Pavilion dv9000 (GA359UA... | [cea70d5f75](https://linux-hardware.org/?probe=cea70d5f75) | Sep 29, 2023 |
| Dell          | Inspiron 5570               | [0e12b69b96](https://linux-hardware.org/?probe=0e12b69b96) | Sep 29, 2023 |
| Lenovo        | ThinkPad T500 22439AG       | [e5a2cd9816](https://linux-hardware.org/?probe=e5a2cd9816) | Sep 29, 2023 |
| Lenovo        | ThinkPad E490 20N8000SRT    | [274b3b5210](https://linux-hardware.org/?probe=274b3b5210) | Sep 28, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | [c61d70bcfa](https://linux-hardware.org/?probe=c61d70bcfa) | Sep 28, 2023 |
| Lenovo        | IdeaPad Slim 5 16ABR8 82... | [1fcc841148](https://linux-hardware.org/?probe=1fcc841148) | Sep 28, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | [be49c167d0](https://linux-hardware.org/?probe=be49c167d0) | Sep 28, 2023 |
| Apple         | MacBookAir7,2               | [c25eeffab1](https://linux-hardware.org/?probe=c25eeffab1) | Sep 28, 2023 |
| Acer          | Acadia V1.35                | [c2074b2535](https://linux-hardware.org/?probe=c2074b2535) | Sep 28, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [3cb2bdba37](https://linux-hardware.org/?probe=3cb2bdba37) | Sep 27, 2023 |
| EUROCOM       | RACER 2.0                   | [4351733d37](https://linux-hardware.org/?probe=4351733d37) | Sep 27, 2023 |
| HP            | ElitePad 1000 G2            | [2668770971](https://linux-hardware.org/?probe=2668770971) | Sep 27, 2023 |
| Fujitsu       | LIFEBOOK E4512              | [08b39b38bd](https://linux-hardware.org/?probe=08b39b38bd) | Sep 27, 2023 |
| ASUSTek       | K50IJ                       | [8556633dad](https://linux-hardware.org/?probe=8556633dad) | Sep 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [1317c1f1a9](https://linux-hardware.org/?probe=1317c1f1a9) | Sep 27, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [1a472d3072](https://linux-hardware.org/?probe=1a472d3072) | Sep 27, 2023 |
| Dell          | Latitude E6530              | [40cdcd2545](https://linux-hardware.org/?probe=40cdcd2545) | Sep 27, 2023 |
| Acer          | Aspire 5951G                | [cae145acab](https://linux-hardware.org/?probe=cae145acab) | Sep 26, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [d406193722](https://linux-hardware.org/?probe=d406193722) | Sep 26, 2023 |
| Dell          | XPS 9315                    | [6fa1beb451](https://linux-hardware.org/?probe=6fa1beb451) | Sep 26, 2023 |
| Lenovo        | ThinkPad T420 4236EV9       | [d621ecd81f](https://linux-hardware.org/?probe=d621ecd81f) | Sep 26, 2023 |
| Aquarius      | NS585                       | [ce1c1d6e56](https://linux-hardware.org/?probe=ce1c1d6e56) | Sep 26, 2023 |
| Acer          | Aspire A515-47              | [3c1e418bf0](https://linux-hardware.org/?probe=3c1e418bf0) | Sep 26, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [9e9ff26362](https://linux-hardware.org/?probe=9e9ff26362) | Sep 26, 2023 |
| Acer          | Aspire A515-56              | [b047457fd1](https://linux-hardware.org/?probe=b047457fd1) | Sep 25, 2023 |
| Dell          | XPS 15 9560                 | [a524453c71](https://linux-hardware.org/?probe=a524453c71) | Sep 25, 2023 |
| Lenovo        | G710 20252                  | [d7926809d7](https://linux-hardware.org/?probe=d7926809d7) | Sep 25, 2023 |
| HP            | Presario CQ43               | [c206dc84ad](https://linux-hardware.org/?probe=c206dc84ad) | Sep 25, 2023 |
| Aquarius      | NS585                       | [e901467e39](https://linux-hardware.org/?probe=e901467e39) | Sep 25, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [ab332c2dcb](https://linux-hardware.org/?probe=ab332c2dcb) | Sep 25, 2023 |
| Acer          | Aspire 5951G                | [4c50b8e9b0](https://linux-hardware.org/?probe=4c50b8e9b0) | Sep 25, 2023 |
| Lenovo        | ThinkPad T440s 20ARS0CN0... | [9c0b702e21](https://linux-hardware.org/?probe=9c0b702e21) | Sep 24, 2023 |
| Dell          | Latitude 5420               | [0e22f551b9](https://linux-hardware.org/?probe=0e22f551b9) | Sep 24, 2023 |
| HP            | 250 G8 Notebook PC          | [6b3c3ce703](https://linux-hardware.org/?probe=6b3c3ce703) | Sep 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [42309ddc8c](https://linux-hardware.org/?probe=42309ddc8c) | Sep 23, 2023 |
| HP            | 250 G8 Notebook PC          | [e2dd7767f0](https://linux-hardware.org/?probe=e2dd7767f0) | Sep 23, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [574c2193bb](https://linux-hardware.org/?probe=574c2193bb) | Sep 23, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21B90... | [e273beb83a](https://linux-hardware.org/?probe=e273beb83a) | Sep 22, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [ad1b8126d2](https://linux-hardware.org/?probe=ad1b8126d2) | Sep 22, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21B90... | [0d786ffd74](https://linux-hardware.org/?probe=0d786ffd74) | Sep 22, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [c14178c7fa](https://linux-hardware.org/?probe=c14178c7fa) | Sep 22, 2023 |
| Samsung       | R505                        | [8aef37cda9](https://linux-hardware.org/?probe=8aef37cda9) | Sep 22, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [4bf358cd4f](https://linux-hardware.org/?probe=4bf358cd4f) | Sep 22, 2023 |
| HP            | EliteBook 840 G3            | [b6379ef77c](https://linux-hardware.org/?probe=b6379ef77c) | Sep 22, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [ea491d194f](https://linux-hardware.org/?probe=ea491d194f) | Sep 21, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [e33bb92eb6](https://linux-hardware.org/?probe=e33bb92eb6) | Sep 21, 2023 |
| Lenovo        | V14 G3 IAP 82TS             | [2528381c0e](https://linux-hardware.org/?probe=2528381c0e) | Sep 21, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [f9430fd075](https://linux-hardware.org/?probe=f9430fd075) | Sep 21, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [e337cc85e5](https://linux-hardware.org/?probe=e337cc85e5) | Sep 20, 2023 |
| Acer          | Aspire E1-531               | [f0173f0458](https://linux-hardware.org/?probe=f0173f0458) | Sep 20, 2023 |
| Lenovo        | ThinkPad L390 20NRCTO1WW    | [228d31bf59](https://linux-hardware.org/?probe=228d31bf59) | Sep 20, 2023 |
| Dell          | XPS 13 9300                 | [49bb68e979](https://linux-hardware.org/?probe=49bb68e979) | Sep 20, 2023 |
| HP            | ProBook 450 G1              | [4e5ae95013](https://linux-hardware.org/?probe=4e5ae95013) | Sep 20, 2023 |
| ASUSTek       | X556UQ                      | [c34d9b9514](https://linux-hardware.org/?probe=c34d9b9514) | Sep 20, 2023 |
| ASUSTek       | X556UQ                      | [7ec3567855](https://linux-hardware.org/?probe=7ec3567855) | Sep 20, 2023 |
| ASUSTek       | X556UQ                      | [676dd13401](https://linux-hardware.org/?probe=676dd13401) | Sep 20, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [5662d8f95c](https://linux-hardware.org/?probe=5662d8f95c) | Sep 20, 2023 |
| HP            | Laptop 15-bs0xx             | [963330511d](https://linux-hardware.org/?probe=963330511d) | Sep 19, 2023 |
| Notebook      | P7xxDM3(-G)                 | [b302c7b008](https://linux-hardware.org/?probe=b302c7b008) | Sep 19, 2023 |
| Lenovo        | ThinkPad X61s 7666Y2X       | [177e40808d](https://linux-hardware.org/?probe=177e40808d) | Sep 19, 2023 |
| Notebook      | P7xxDM3(-G)                 | [ec386099b2](https://linux-hardware.org/?probe=ec386099b2) | Sep 19, 2023 |
| HP            | Laptop 17-cp0xxx            | [05e3350e1f](https://linux-hardware.org/?probe=05e3350e1f) | Sep 19, 2023 |
| Dell          | XPS 13 9360                 | [149f246bd7](https://linux-hardware.org/?probe=149f246bd7) | Sep 19, 2023 |
| Acer          | Aspire A515-56              | [db16273e72](https://linux-hardware.org/?probe=db16273e72) | Sep 19, 2023 |
| Intel Clie... | LAPBC710                    | [af446fcb4d](https://linux-hardware.org/?probe=af446fcb4d) | Sep 19, 2023 |
| Intel Clie... | LAPBC710                    | [eae124fa61](https://linux-hardware.org/?probe=eae124fa61) | Sep 19, 2023 |
| HP            | Laptop 15-bs0xx             | [5f8df7dfcb](https://linux-hardware.org/?probe=5f8df7dfcb) | Sep 19, 2023 |
| Dell          | Latitude E6430              | [d83d7bbfa8](https://linux-hardware.org/?probe=d83d7bbfa8) | Sep 18, 2023 |
| HP            | 15                          | [b016d5ee79](https://linux-hardware.org/?probe=b016d5ee79) | Sep 18, 2023 |
| Aquarius      | NS585                       | [6ac8bd5909](https://linux-hardware.org/?probe=6ac8bd5909) | Sep 18, 2023 |
| HP            | Mini 110-1000               | [dda4d7a910](https://linux-hardware.org/?probe=dda4d7a910) | Sep 18, 2023 |
| HP            | Mini 110-1000               | [ee2d142228](https://linux-hardware.org/?probe=ee2d142228) | Sep 18, 2023 |
| HP            | Compaq Mini 311-1100        | [8bdfb6307c](https://linux-hardware.org/?probe=8bdfb6307c) | Sep 17, 2023 |
| HP            | Laptop 15-dw3xxx            | [f84a480b09](https://linux-hardware.org/?probe=f84a480b09) | Sep 17, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [cda370cdc3](https://linux-hardware.org/?probe=cda370cdc3) | Sep 16, 2023 |
| ASUSTek       | ASUSPRO P5440FA_P5440FA     | [b7c1a0a0a0](https://linux-hardware.org/?probe=b7c1a0a0a0) | Sep 16, 2023 |
| Apple         | MacBookPro8,1               | [c3791ba730](https://linux-hardware.org/?probe=c3791ba730) | Sep 16, 2023 |
| Lenovo        | ThinkPad X201 3249CTO       | [f5884967d0](https://linux-hardware.org/?probe=f5884967d0) | Sep 16, 2023 |
| Dell          | Latitude E5570              | [fd5ba4aa5a](https://linux-hardware.org/?probe=fd5ba4aa5a) | Sep 15, 2023 |
| Dell          | Precision 5570              | [8b3c21b110](https://linux-hardware.org/?probe=8b3c21b110) | Sep 15, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STC... | [66b29aeb1d](https://linux-hardware.org/?probe=66b29aeb1d) | Sep 15, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | [eaa723190d](https://linux-hardware.org/?probe=eaa723190d) | Sep 15, 2023 |
| ASUSTek       | X507UB                      | [ca19710375](https://linux-hardware.org/?probe=ca19710375) | Sep 15, 2023 |
| ASUSTek       | X751LN                      | [77ecc965aa](https://linux-hardware.org/?probe=77ecc965aa) | Sep 14, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0ffb2a765f](https://linux-hardware.org/?probe=0ffb2a765f) | Sep 14, 2023 |
| Toshiba       | PORTEGE Z830                | [a3e1ac295c](https://linux-hardware.org/?probe=a3e1ac295c) | Sep 14, 2023 |
| ASUSTek       | P553UJ                      | [3463413300](https://linux-hardware.org/?probe=3463413300) | Sep 14, 2023 |
| Toshiba       | PORTEGE Z830                | [6f4c4a4120](https://linux-hardware.org/?probe=6f4c4a4120) | Sep 14, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [d27fa5404b](https://linux-hardware.org/?probe=d27fa5404b) | Sep 14, 2023 |
| Dell          | Latitude 5440               | [93a296a628](https://linux-hardware.org/?probe=93a296a628) | Sep 14, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [033eca4030](https://linux-hardware.org/?probe=033eca4030) | Sep 14, 2023 |
| HP            | 245 G7 Notebook PC          | [ab68dea087](https://linux-hardware.org/?probe=ab68dea087) | Sep 14, 2023 |
| HP            | ProBook 6570b               | [fc5c01d215](https://linux-hardware.org/?probe=fc5c01d215) | Sep 14, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [0cdeaab8be](https://linux-hardware.org/?probe=0cdeaab8be) | Sep 13, 2023 |
| MSI           | GS66 Stealth 11UG           | [304abac74b](https://linux-hardware.org/?probe=304abac74b) | Sep 13, 2023 |
| HP            | Stream Notebook PC 11       | [f4c5ae4297](https://linux-hardware.org/?probe=f4c5ae4297) | Sep 13, 2023 |
| Acer          | AOA150                      | [bc32c4814d](https://linux-hardware.org/?probe=bc32c4814d) | Sep 13, 2023 |
| Lenovo        | ThinkPad X230 232036U       | [58ec12094c](https://linux-hardware.org/?probe=58ec12094c) | Sep 13, 2023 |
| Google        | Cave                        | [74c8e00b23](https://linux-hardware.org/?probe=74c8e00b23) | Sep 13, 2023 |
| Dell          | Latitude E6430              | [79cf77c6ba](https://linux-hardware.org/?probe=79cf77c6ba) | Sep 12, 2023 |
| Dell          | Latitude E7470              | [4f2094dfef](https://linux-hardware.org/?probe=4f2094dfef) | Sep 12, 2023 |
| Toshiba       | Satellite L640              | [ac5a264fea](https://linux-hardware.org/?probe=ac5a264fea) | Sep 12, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian_12/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 6.1.0-13-amd64          | 308       | 21%     |
| 6.1.0-9-amd64           | 174       | 11.86%  |
| 6.1.0-10-amd64          | 173       | 11.79%  |
| 6.1.0-12-amd64          | 122       | 8.32%   |
| 6.1.0-17-amd64          | 114       | 7.77%   |
| 6.1.0-11-amd64          | 106       | 7.23%   |
| 6.1.0-16-amd64          | 86        | 5.86%   |
| 6.1.0-4-amd64           | 60        | 4.09%   |
| 6.1.0-7-amd64           | 50        | 3.41%   |
| 6.1.0-15-amd64          | 47        | 3.2%    |
| 6.1.0-6-amd64           | 28        | 1.91%   |
| 6.1.0-5-amd64           | 21        | 1.43%   |
| 6.1.0-3-amd64           | 20        | 1.36%   |
| 6.5.0-0.deb12.4-amd64   | 13        | 0.89%   |
| 6.4.0-0.deb12.2-amd64   | 12        | 0.82%   |
| 6.1.0-8-amd64           | 8         | 0.55%   |
| 6.1.0-14-amd64          | 7         | 0.48%   |
| 6.5.0-0.deb12.1-amd64   | 6         | 0.41%   |
| 6.1.0-10-686-pae        | 6         | 0.41%   |
| 6.2.16-3-pve            | 5         | 0.34%   |
| 6.1.0-12-686-pae        | 4         | 0.27%   |
| 6.0.0-2-amd64           | 3         | 0.2%    |
| 6.6.12-1-liquorix-amd64 | 2         | 0.14%   |
| 6.6.0-chrultrabook      | 2         | 0.14%   |
| 6.5.11-x64v3-xanmod1    | 2         | 0.14%   |
| 6.4.3-1-liquorix-amd64  | 2         | 0.14%   |
| 6.4.0-1mx-ahs-amd64     | 2         | 0.14%   |
| 6.4.0-1-amd64           | 2         | 0.14%   |
| 6.3.0-2mx-ahs-amd64     | 2         | 0.14%   |
| 6.2.16-6-pve            | 2         | 0.14%   |
| 6.1.0-9-686-pae         | 2         | 0.14%   |
| 6.1.0-7-rt-amd64        | 2         | 0.14%   |
| 6.1.0-13-686-pae        | 2         | 0.14%   |
| 6.0.0-6-amd64           | 2         | 0.14%   |
| 6.0.0-0.deb11.6-amd64   | 2         | 0.14%   |
| 5.10.0-23-amd64         | 2         | 0.14%   |
| 5.10.0-21-amd64         | 2         | 0.14%   |
| 6.7.2-3-liquorix-amd64  | 1         | 0.07%   |
| 6.6.9-amd64             | 1         | 0.07%   |
| 6.6.13-x64v2-xanmod1    | 1         | 0.07%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1.0   | 1282      | 91.83%  |
| 6.5.0   | 24        | 1.72%   |
| 6.4.0   | 18        | 1.29%   |
| 6.2.16  | 10        | 0.72%   |
| 6.0.0   | 8         | 0.57%   |
| 5.10.0  | 7         | 0.5%    |
| 6.3.0   | 5         | 0.36%   |
| 6.6.0   | 3         | 0.21%   |
| 6.6.12  | 2         | 0.14%   |
| 6.5.11  | 2         | 0.14%   |
| 6.4.3   | 2         | 0.14%   |
| 6.4.2   | 2         | 0.14%   |
| 6.1.69  | 2         | 0.14%   |
| 6.1.38  | 2         | 0.14%   |
| 6.1.11  | 2         | 0.14%   |
| 6.7.2   | 1         | 0.07%   |
| 6.6.9   | 1         | 0.07%   |
| 6.6.13  | 1         | 0.07%   |
| 6.6.11  | 1         | 0.07%   |
| 6.6.10  | 1         | 0.07%   |
| 6.5.5   | 1         | 0.07%   |
| 6.5.4   | 1         | 0.07%   |
| 6.5.3   | 1         | 0.07%   |
| 6.5.10  | 1         | 0.07%   |
| 6.4.9   | 1         | 0.07%   |
| 6.4.7   | 1         | 0.07%   |
| 6.4.12  | 1         | 0.07%   |
| 6.3.9   | 1         | 0.07%   |
| 6.3.8   | 1         | 0.07%   |
| 6.3.10  | 1         | 0.07%   |
| 6.2.8   | 1         | 0.07%   |
| 6.2.11  | 1         | 0.07%   |
| 6.1.63  | 1         | 0.07%   |
| 6.1.52  | 1         | 0.07%   |
| 6.1.48  | 1         | 0.07%   |
| 6.1.42  | 1         | 0.07%   |
| 6.1.12  | 1         | 0.07%   |
| 5.19.0  | 1         | 0.07%   |
| 5.16.0  | 1         | 0.07%   |
| 5.15.95 | 1         | 0.07%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 1292      | 92.68%  |
| 6.5     | 30        | 2.15%   |
| 6.4     | 24        | 1.72%   |
| 6.2     | 12        | 0.86%   |
| 6.6     | 9         | 0.65%   |
| 6.3     | 8         | 0.57%   |
| 6.0     | 8         | 0.57%   |
| 5.10    | 7         | 0.5%    |
| 6.7     | 1         | 0.07%   |
| 5.19    | 1         | 0.07%   |
| 5.16    | 1         | 0.07%   |
| 5.15    | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 1357      | 98.19%  |
| i686    | 22        | 1.59%   |
| aarch64 | 2         | 0.14%   |
| armv7l  | 1         | 0.07%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 517       | 36.88%  |
| KDE5              | 307       | 21.9%   |
| Unknown           | 203       | 14.48%  |
| XFCE              | 134       | 9.56%   |
| X-Cinnamon        | 83        | 5.92%   |
| MATE              | 48        | 3.42%   |
| LXDE              | 19        | 1.36%   |
| LXQt              | 18        | 1.28%   |
| i3                | 18        | 1.28%   |
| Cinnamon          | 11        | 0.78%   |
| GNOME Flashback   | 9         | 0.64%   |
| GNOME Classic     | 5         | 0.36%   |
| Budgie            | 5         | 0.36%   |
| lightdm-xsession  | 3         | 0.21%   |
| KDE               | 3         | 0.21%   |
| Enlightenment     | 3         | 0.21%   |
| Trinity           | 2         | 0.14%   |
| sway              | 2         | 0.14%   |
| awesome           | 2         | 0.14%   |
| xmonad            | 1         | 0.07%   |
| x-session-manager | 1         | 0.07%   |
| Unity             | 1         | 0.07%   |
| qtile             | 1         | 0.07%   |
| Pantheon          | 1         | 0.07%   |
| icewm             | 1         | 0.07%   |
| dwm               | 1         | 0.07%   |
| Deepin            | 1         | 0.07%   |
| BunsenLabs        | 1         | 0.07%   |
| bspwm             | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 601       | 42.68%  |
| Wayland | 580       | 41.19%  |
| Unknown | 173       | 12.29%  |
| Tty     | 53        | 3.76%   |
| Web     | 1         | 0.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Unknown       | 494       | 35.34%  |
| GDM3          | 430       | 30.76%  |
| LightDM       | 234       | 16.74%  |
| SDDM          | 218       | 15.59%  |
| GDM           | 6         | 0.43%   |
| LXDM          | 4         | 0.29%   |
| GREETD        | 4         | 0.29%   |
| Ly            | 2         | 0.14%   |
| XDM           | 1         | 0.07%   |
| WDM           | 1         | 0.07%   |
| TDM           | 1         | 0.07%   |
| SLiM          | 1         | 0.07%   |
| NODM          | 1         | 0.07%   |
| DARKDM_ON_TTY | 1         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 541       | 38.81%  |
| ru_RU   | 113       | 8.11%   |
| Unknown | 109       | 7.82%   |
| fr_FR   | 101       | 7.25%   |
| de_DE   | 90        | 6.46%   |
| en_GB   | 80        | 5.74%   |
| es_ES   | 36        | 2.58%   |
| pt_BR   | 35        | 2.51%   |
| it_IT   | 35        | 2.51%   |
| en_CA   | 21        | 1.51%   |
| sv_SE   | 19        | 1.36%   |
| pl_PL   | 18        | 1.29%   |
| en_IN   | 18        | 1.29%   |
| en_AU   | 17        | 1.22%   |
| zh_CN   | 12        | 0.86%   |
| C       | 12        | 0.86%   |
| es_MX   | 10        | 0.72%   |
| hu_HU   | 8         | 0.57%   |
| es_CL   | 7         | 0.5%    |
| tr_TR   | 6         | 0.43%   |
| en_IE   | 6         | 0.43%   |
| zh_TW   | 5         | 0.36%   |
| nl_NL   | 5         | 0.36%   |
| de_CH   | 5         | 0.36%   |
| de_AT   | 5         | 0.36%   |
| cs_CZ   | 5         | 0.36%   |
| ca_ES   | 5         | 0.36%   |
| pt_PT   | 4         | 0.29%   |
| fi_FI   | 4         | 0.29%   |
| es_VE   | 3         | 0.22%   |
| es_CO   | 3         | 0.22%   |
| es_AR   | 3         | 0.22%   |
| en_NZ   | 3         | 0.22%   |
| da_DK   | 3         | 0.22%   |
| be_BY   | 3         | 0.22%   |
| sk_SK   | 2         | 0.14%   |
| nn_NO   | 2         | 0.14%   |
| nb_NO   | 2         | 0.14%   |
| ko_KR   | 2         | 0.14%   |
| hr_HR   | 2         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 875       | 63.09%  |
| BIOS | 512       | 36.91%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1054      | 75.77%  |
| Overlay | 221       | 15.89%  |
| Btrfs   | 66        | 4.74%   |
| Tmpfs   | 29        | 2.08%   |
| Xfs     | 11        | 0.79%   |
| Zfs     | 7         | 0.5%    |
| Ext3    | 2         | 0.14%   |
| Jfs     | 1         | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 903       | 65.01%  |
| Unknown | 295       | 21.24%  |
| MBR     | 191       | 13.75%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1271      | 91.24%  |
| Yes       | 122       | 8.76%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1013      | 72.77%  |
| Yes       | 379       | 27.23%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 371       | 26.85%  |
| Hewlett-Packard        | 226       | 16.35%  |
| Dell                   | 161       | 11.65%  |
| ASUSTek Computer       | 124       | 8.97%   |
| Acer                   | 100       | 7.24%   |
| Google                 | 74        | 5.35%   |
| Apple                  | 52        | 3.76%   |
| Aquarius               | 36        | 2.6%    |
| MSI                    | 28        | 2.03%   |
| HUAWEI                 | 22        | 1.59%   |
| Toshiba                | 20        | 1.45%   |
| Samsung Electronics    | 20        | 1.45%   |
| Unknown                | 11        | 0.8%    |
| Sony                   | 9         | 0.65%   |
| Medion                 | 8         | 0.58%   |
| Framework              | 8         | 0.58%   |
| HONOR                  | 7         | 0.51%   |
| Fujitsu                | 7         | 0.51%   |
| TUXEDO                 | 5         | 0.36%   |
| Timi                   | 5         | 0.36%   |
| Notebook               | 5         | 0.36%   |
| eMachines              | 4         | 0.29%   |
| Alienware              | 4         | 0.29%   |
| Positivo               | 3         | 0.22%   |
| Panasonic              | 3         | 0.22%   |
| LG Electronics         | 3         | 0.22%   |
| IBM                    | 3         | 0.22%   |
| GPU Company            | 3         | 0.22%   |
| VALE                   | 2         | 0.14%   |
| THUNDEROBOT            | 2         | 0.14%   |
| Schenker               | 2         | 0.14%   |
| Razer                  | 2         | 0.14%   |
| PC Specialist          | 2         | 0.14%   |
| Packard Bell           | 2         | 0.14%   |
| MACHENIKE              | 2         | 0.14%   |
| Gigabyte Technology    | 2         | 0.14%   |
| Fujitsu Siemens        | 2         | 0.14%   |
| Avell High Performance | 2         | 0.14%   |
| win element            | 1         | 0.07%   |
| VANT                   | 1         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Google Reks                            | 36        | 2.6%    |
| Aquarius NS585                         | 36        | 2.6%    |
| Lenovo ThinkPad E475 20H40006US        | 22        | 1.59%   |
| Unknown                                | 17        | 1.23%   |
| Google Enguarde                        | 16        | 1.16%   |
| Apple MacBookAir7,2                    | 13        | 0.94%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US  | 10        | 0.72%   |
| Lenovo ThinkPad X230 2325V2Y           | 8         | 0.58%   |
| HP ProBook 650 G1                      | 6         | 0.43%   |
| Acer Aspire A515-56                    | 6         | 0.43%   |
| HP ProBook 650 G2                      | 5         | 0.36%   |
| HP ProBook 450 G3                      | 5         | 0.36%   |
| Framework Laptop (13th Gen Intel Core) | 5         | 0.36%   |
| Lenovo ThinkPad L14 Gen 2 20X1004CMX   | 4         | 0.29%   |
| HP Pavilion Notebook                   | 4         | 0.29%   |
| HP Pavilion dv6                        | 4         | 0.29%   |
| HP Laptop 15s-eq2xxx                   | 4         | 0.29%   |
| HP EliteBook 845 G8 Notebook PC        | 4         | 0.29%   |
| HP EliteBook 840 G3                    | 4         | 0.29%   |
| HP EliteBook 2570p                     | 4         | 0.29%   |
| Dell XPS 9315                          | 4         | 0.29%   |
| Dell XPS 15 9570                       | 4         | 0.29%   |
| Dell Precision 5570                    | 4         | 0.29%   |
| Apple MacBookPro12,1                   | 4         | 0.29%   |
| Lenovo Yoga Pro 7 14ARP8 83AU          | 3         | 0.22%   |
| Lenovo IdeaPad 3 15ALC6 82KU           | 3         | 0.22%   |
| HUAWEI BOHK-WAX9X                      | 3         | 0.22%   |
| HUAWEI BOHB-WAX9                       | 3         | 0.22%   |
| HONOR NMH-WCX9                         | 3         | 0.22%   |
| HP Victus by Gaming Laptop 15-fb0xxx   | 3         | 0.22%   |
| HP ProBook 655 G2                      | 3         | 0.22%   |
| HP Presario CQ57                       | 3         | 0.22%   |
| HP Pavilion Aero Laptop 13-be0xxx      | 3         | 0.22%   |
| HP Laptop 15-db0xxx                    | 3         | 0.22%   |
| HP EliteBook 840 G5                    | 3         | 0.22%   |
| HP EliteBook 830 G5                    | 3         | 0.22%   |
| HP EliteBook 745 G3                    | 3         | 0.22%   |
| Dell XPS 15 9560                       | 3         | 0.22%   |
| Dell XPS 13 9380                       | 3         | 0.22%   |
| Dell XPS 13 9370                       | 3         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 249       | 18.02%  |
| Acer Aspire       | 65        | 4.7%    |
| Dell Latitude     | 60        | 4.34%   |
| Lenovo IdeaPad    | 52        | 3.76%   |
| HP EliteBook      | 48        | 3.47%   |
| HP ProBook        | 43        | 3.11%   |
| ASUS VivoBook     | 41        | 2.97%   |
| HP Pavilion       | 36        | 2.6%    |
| Google Reks       | 36        | 2.6%    |
| Aquarius NS585    | 36        | 2.6%    |
| HP Laptop         | 33        | 2.39%   |
| Dell XPS          | 33        | 2.39%   |
| Dell Inspiron     | 29        | 2.1%    |
| Dell Precision    | 17        | 1.23%   |
| Unknown           | 17        | 1.23%   |
| Toshiba Satellite | 16        | 1.16%   |
| Google Enguarde   | 16        | 1.16%   |
| Lenovo Yoga       | 15        | 1.09%   |
| Apple MacBookAir7 | 15        | 1.09%   |
| ASUS ZenBook      | 14        | 1.01%   |
| ASUS ASUS         | 12        | 0.87%   |
| Lenovo Legion     | 11        | 0.8%    |
| Dell Vostro       | 11        | 0.8%    |
| Lenovo ThinkBook  | 10        | 0.72%   |
| HP ZBook          | 10        | 0.72%   |
| Acer Swift        | 10        | 0.72%   |
| Acer Nitro        | 9         | 0.65%   |
| HP Victus         | 8         | 0.58%   |
| HP OMEN           | 8         | 0.58%   |
| Framework Laptop  | 8         | 0.58%   |
| Fujitsu LIFEBOOK  | 7         | 0.51%   |
| Acer TravelMate   | 7         | 0.51%   |
| ASUS ROG          | 6         | 0.43%   |
| HP ENVY           | 5         | 0.36%   |
| HP 250            | 5         | 0.36%   |
| Acer Extensa      | 5         | 0.36%   |
| MSI Prestige      | 4         | 0.29%   |
| Lenovo V15        | 4         | 0.29%   |
| HP Presario       | 4         | 0.29%   |
| HP Compaq         | 4         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 184       | 13.31%  |
| 2019    | 159       | 11.51%  |
| 2022    | 149       | 10.78%  |
| 2023    | 127       | 9.19%   |
| 2020    | 118       | 8.54%   |
| 2018    | 85        | 6.15%   |
| 2013    | 70        | 5.07%   |
| 2012    | 70        | 5.07%   |
| 2017    | 65        | 4.7%    |
| 2011    | 64        | 4.63%   |
| 2016    | 58        | 4.2%    |
| 2015    | 47        | 3.4%    |
| 2008    | 44        | 3.18%   |
| 2014    | 41        | 2.97%   |
| 2009    | 32        | 2.32%   |
| 2010    | 31        | 2.24%   |
| 2007    | 25        | 1.81%   |
| 2005    | 5         | 0.36%   |
| 2006    | 3         | 0.22%   |
| Unknown | 3         | 0.22%   |
| 2004    | 2         | 0.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1382      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1227      | 88.46%  |
| Enabled  | 160       | 11.54%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1304      | 94.36%  |
| Yes  | 78        | 5.64%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 398       | 28.65%  |
| 16.01-24.0  | 264       | 19.01%  |
| 8.01-16.0   | 246       | 17.71%  |
| 3.01-4.0    | 241       | 17.35%  |
| 32.01-64.0  | 128       | 9.22%   |
| 1.01-2.0    | 35        | 2.52%   |
| 64.01-256.0 | 29        | 2.09%   |
| 24.01-32.0  | 22        | 1.58%   |
| 2.01-3.0    | 19        | 1.37%   |
| 0.51-1.0    | 5         | 0.36%   |
| 0.01-0.5    | 2         | 0.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 397       | 27.53%  |
| 2.01-3.0   | 345       | 23.93%  |
| 4.01-8.0   | 276       | 19.14%  |
| 3.01-4.0   | 216       | 14.98%  |
| 0.51-1.0   | 104       | 7.21%   |
| 8.01-16.0  | 76        | 5.27%   |
| 0.01-0.5   | 15        | 1.04%   |
| 16.01-24.0 | 7         | 0.49%   |
| 24.01-32.0 | 5         | 0.35%   |
| 32.01-64.0 | 1         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1075      | 77.17%  |
| 2      | 271       | 19.45%  |
| 3      | 35        | 2.51%   |
| 4      | 6         | 0.43%   |
| 0      | 6         | 0.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1099      | 79.29%  |
| Yes       | 287       | 20.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1024      | 73.99%  |
| No        | 360       | 26.01%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1352      | 97.83%  |
| No        | 30        | 2.17%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1173      | 84.69%  |
| No        | 212       | 15.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 275       | 19.81%  |
| Russia      | 139       | 10.01%  |
| Germany     | 129       | 9.29%   |
| France      | 116       | 8.36%   |
| Italy       | 65        | 4.68%   |
| Brazil      | 54        | 3.89%   |
| Spain       | 53        | 3.82%   |
| UK          | 42        | 3.03%   |
| Poland      | 41        | 2.95%   |
| Sweden      | 35        | 2.52%   |
| Canada      | 34        | 2.45%   |
| Netherlands | 24        | 1.73%   |
| India       | 22        | 1.59%   |
| China       | 20        | 1.44%   |
| Australia   | 19        | 1.37%   |
| Turkey      | 18        | 1.3%    |
| Mexico      | 16        | 1.15%   |
| Switzerland | 15        | 1.08%   |
| Czechia     | 15        | 1.08%   |
| Austria     | 15        | 1.08%   |
| Portugal    | 11        | 0.79%   |
| Hungary     | 11        | 0.79%   |
| Chile       | 11        | 0.79%   |
| Romania     | 10        | 0.72%   |
| Belgium     | 9         | 0.65%   |
| Norway      | 8         | 0.58%   |
| Indonesia   | 8         | 0.58%   |
| Greece      | 8         | 0.58%   |
| Finland     | 8         | 0.58%   |
| Colombia    | 8         | 0.58%   |
| Ukraine     | 7         | 0.5%    |
| Costa Rica  | 7         | 0.5%    |
| Belarus     | 6         | 0.43%   |
| Venezuela   | 5         | 0.36%   |
| Denmark     | 5         | 0.36%   |
| Bulgaria    | 5         | 0.36%   |
| Argentina   | 5         | 0.36%   |
| Vietnam     | 4         | 0.29%   |
| UAE         | 4         | 0.29%   |
| Taiwan      | 4         | 0.29%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Bangor            | 109       | 7.67%   |
| Voronezh          | 60        | 4.22%   |
| Moscow            | 31        | 2.18%   |
| Roubaix           | 30        | 2.11%   |
| Paris             | 18        | 1.27%   |
| Saltsjoe-Boo      | 13        | 0.91%   |
| Milan             | 13        | 0.91%   |
| Berlin            | 12        | 0.84%   |
| Toronto           | 10        | 0.7%    |
| St Petersburg     | 9         | 0.63%   |
| Vienna            | 8         | 0.56%   |
| Perm              | 8         | 0.56%   |
| Sydney            | 7         | 0.49%   |
| Mesa              | 7         | 0.49%   |
| Madrid            | 7         | 0.49%   |
| Budapest          | 7         | 0.49%   |
| Amsterdam         | 7         | 0.49%   |
| Shanghai          | 6         | 0.42%   |
| Istanbul          | 6         | 0.42%   |
| Hamburg           | 6         | 0.42%   |
| Dublin            | 6         | 0.42%   |
| Wroclaw           | 5         | 0.35%   |
| Warsaw            | 5         | 0.35%   |
| Stockholm         | 5         | 0.35%   |
| Seville           | 5         | 0.35%   |
| Santiago          | 5         | 0.35%   |
| Prague            | 5         | 0.35%   |
| Portland          | 5         | 0.35%   |
| Milano            | 5         | 0.35%   |
| Melbourne         | 5         | 0.35%   |
| Lisbon            | 5         | 0.35%   |
| Leipzig           | 5         | 0.35%   |
| Frankfurt am Main | 5         | 0.35%   |
| Fortaleza         | 5         | 0.35%   |
| Brasília         | 5         | 0.35%   |
| Bengaluru         | 5         | 0.35%   |
| Singapore         | 4         | 0.28%   |
| San José         | 4         | 0.28%   |
| Samara            | 4         | 0.28%   |
| Rome              | 4         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 307       | 374    | 18.34%  |
| WDC                         | 153       | 169    | 9.14%   |
| Unknown                     | 114       | 132    | 6.81%   |
| SanDisk                     | 109       | 127    | 6.51%   |
| Kingston                    | 99        | 107    | 5.91%   |
| SK hynix                    | 93        | 100    | 5.56%   |
| Seagate                     | 83        | 94     | 4.96%   |
| Toshiba                     | 75        | 82     | 4.48%   |
| Micron Technology           | 69        | 75     | 4.12%   |
| Crucial                     | 57        | 65     | 3.41%   |
| A-DATA Technology           | 57        | 86     | 3.41%   |
| Intel                       | 56        | 68     | 3.35%   |
| HGST                        | 30        | 31     | 1.79%   |
| Apple                       | 28        | 31     | 1.67%   |
| KIOXIA                      | 27        | 31     | 1.61%   |
| Hitachi                     | 25        | 27     | 1.49%   |
| Unknown                     | 24        | 26     | 1.43%   |
| China                       | 14        | 18     | 0.84%   |
| Kingston Technology Company | 11        | 12     | 0.66%   |
| Intenso                     | 11        | 13     | 0.66%   |
| SPCC                        | 10        | 14     | 0.6%    |
| Silicon Motion              | 10        | 11     | 0.6%    |
| Phison                      | 10        | 10     | 0.6%    |
| JMicron Technology          | 10        | 10     | 0.6%    |
| SSSTC                       | 9         | 11     | 0.54%   |
| Phison Electronics          | 9         | 11     | 0.54%   |
| Fujitsu                     | 8         | 8      | 0.48%   |
| Patriot                     | 7         | 7      | 0.42%   |
| Netac                       | 7         | 7      | 0.42%   |
| UMIS                        | 6         | 6      | 0.36%   |
| Transcend                   | 6         | 6      | 0.36%   |
| MAXIO Technology (Hangzhou) | 6         | 6      | 0.36%   |
| ADATA Technology            | 6         | 6      | 0.36%   |
| Team                        | 5         | 5      | 0.3%    |
| Micron/Crucial Technology   | 5         | 5      | 0.3%    |
| LITEON                      | 5         | 6      | 0.3%    |
| KIOXIA-EXCERIA              | 5         | 5      | 0.3%    |
| YMTC                        | 4         | 5      | 0.24%   |
| Realtek Semiconductor       | 4         | 4      | 0.24%   |
| Realtek                     | 4         | 4      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| A-DATA SU800 512GB SSD                             | 36        | 2.08%   |
| Kingston SA400S37120G 120GB SSD                    | 28        | 1.62%   |
| Unknown                                            | 24        | 1.39%   |
| Unknown DF4016  16GB                               | 23        | 1.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 21        | 1.21%   |
| Kingston SA400S37480G 480GB SSD                    | 12        | 0.69%   |
| Kingston SA400S37240G 240GB SSD                    | 12        | 0.69%   |
| Crucial CT500MX500SSD1 500GB                       | 12        | 0.69%   |
| Unknown MMC Card  64GB                             | 11        | 0.64%   |
| SanDisk NVMe SSD Drive 512GB                       | 11        | 0.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 11        | 0.64%   |
| Apple SSD SM0128G 121GB                            | 11        | 0.64%   |
| Seagate ST1000LM035-1RK172 1TB                     | 10        | 0.58%   |
| SanDisk NVMe SSD Drive 1TB                         | 10        | 0.58%   |
| Intel SSDPEKNU512GZ 512GB                          | 10        | 0.58%   |
| Unknown AGND3R  16GB                               | 9         | 0.52%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB   | 9         | 0.52%   |
| Samsung SSD 980 1TB                                | 9         | 0.52%   |
| Micron 2450_MTFDKBA512TFK 512GB                    | 9         | 0.52%   |
| WDC WD5000LPLX-60ZNTT1 500GB                       | 8         | 0.46%   |
| Toshiba MQ01ABF050 500GB                           | 8         | 0.46%   |
| Seagate ST9500325AS 500GB                          | 8         | 0.46%   |
| Micron 2400_MTFDKBA512QFM 512GB                    | 8         | 0.46%   |
| HGST HTS721010A9E630 1TB                           | 8         | 0.46%   |
| Unknown HAG2e  16GB                                | 7         | 0.4%    |
| Toshiba XG6 NVMe SSD Controller 256GB              | 7         | 0.4%    |
| Toshiba MQ04ABF100 1TB                             | 7         | 0.4%    |
| SanDisk SD8SN8U128G1001 128GB SSD                  | 7         | 0.4%    |
| SanDisk NVMe SSD Drive 500GB                       | 7         | 0.4%    |
| Samsung SSD 970 EVO Plus 1TB                       | 7         | 0.4%    |
| Samsung SSD 870 EVO 500GB                          | 7         | 0.4%    |
| Samsung SSD 860 EVO 500GB                          | 7         | 0.4%    |
| WDC WD10SPZX-21Z10T0 1TB                           | 6         | 0.35%   |
| Toshiba MQ01ABD100 1TB                             | 6         | 0.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 6         | 0.35%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB               | 6         | 0.35%   |
| Samsung SSD 860 EVO 250GB                          | 6         | 0.35%   |
| Samsung MZVLQ512HBLU-00BH1 512GB                   | 6         | 0.35%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                   | 5         | 0.29%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 5         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 79        | 88     | 28.52%  |
| WDC                 | 75        | 79     | 27.08%  |
| Toshiba             | 39        | 42     | 14.08%  |
| HGST                | 30        | 31     | 10.83%  |
| Hitachi             | 25        | 27     | 9.03%   |
| Fujitsu             | 8         | 8      | 2.89%   |
| Samsung Electronics | 6         | 6      | 2.17%   |
| JMicron Technology  | 4         | 4      | 1.44%   |
| Unknown             | 3         | 3      | 1.08%   |
| TO Exter            | 2         | 3      | 0.72%   |
| WALRAM              | 1         | 1      | 0.36%   |
| SYMTEC              | 1         | 1      | 0.36%   |
| LaCie               | 1         | 1      | 0.36%   |
| ASMT                | 1         | 1      | 0.36%   |
| Apple               | 1         | 1      | 0.36%   |
| Unknown             | 1         | 1      | 0.36%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 91        | 106    | 17.3%   |
| Kingston            | 74        | 80     | 14.07%  |
| A-DATA Technology   | 49        | 76     | 9.32%   |
| SanDisk             | 45        | 59     | 8.56%   |
| Crucial             | 42        | 47     | 7.98%   |
| WDC                 | 25        | 27     | 4.75%   |
| Apple               | 21        | 21     | 3.99%   |
| SK hynix            | 16        | 16     | 3.04%   |
| China               | 14        | 18     | 2.66%   |
| Micron Technology   | 12        | 14     | 2.28%   |
| Toshiba             | 11        | 12     | 2.09%   |
| Intenso             | 11        | 13     | 2.09%   |
| Intel               | 10        | 11     | 1.9%    |
| SPCC                | 7         | 11     | 1.33%   |
| Netac               | 7         | 7      | 1.33%   |
| Patriot             | 5         | 5      | 0.95%   |
| Transcend           | 4         | 4      | 0.76%   |
| LITEON              | 4         | 5      | 0.76%   |
| KIOXIA-EXCERIA      | 4         | 4      | 0.76%   |
| Wibtek              | 3         | 3      | 0.57%   |
| Hewlett-Packard     | 3         | 4      | 0.57%   |
| GOODRAM             | 3         | 4      | 0.57%   |
| Zheino              | 2         | 2      | 0.38%   |
| Team                | 2         | 2      | 0.38%   |
| SABRENT             | 2         | 2      | 0.38%   |
| PNY                 | 2         | 2      | 0.38%   |
| Plextor             | 2         | 2      | 0.38%   |
| Pioneer             | 2         | 2      | 0.38%   |
| ORIGIN              | 2         | 2      | 0.38%   |
| OCZ                 | 2         | 2      | 0.38%   |
| LITEONIT            | 2         | 3      | 0.38%   |
| Lexar               | 2         | 2      | 0.38%   |
| INNOVATION IT       | 2         | 3      | 0.38%   |
| Gigabyte Technology | 2         | 2      | 0.38%   |
| Fanxiang            | 2         | 3      | 0.38%   |
| Dogfish             | 2         | 2      | 0.38%   |
| AMD                 | 2         | 2      | 0.38%   |
| Unknown             | 2         | 2      | 0.38%   |
| XrayDisk            | 1         | 1      | 0.19%   |
| Wodposit            | 1         | 1      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 672       | 835    | 42.18%  |
| SSD     | 495       | 617    | 31.07%  |
| HDD     | 274       | 297    | 17.2%   |
| MMC     | 134       | 154    | 8.41%   |
| Unknown | 18        | 20     | 1.13%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 697       | 884    | 44.97%  |
| NVMe | 671       | 829    | 43.29%  |
| MMC  | 134       | 154    | 8.65%   |
| SAS  | 48        | 56     | 3.1%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 516       | 616    | 68.07%  |
| 0.51-1.0   | 209       | 262    | 27.57%  |
| 1.01-2.0   | 27        | 30     | 3.56%   |
| 3.01-4.0   | 3         | 3      | 0.4%    |
| 4.01-10.0  | 3         | 3      | 0.4%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 388       | 27.48%  |
| 101-250        | 363       | 25.71%  |
| 501-1000       | 205       | 14.52%  |
| Unknown        | 119       | 8.43%   |
| 1-20           | 113       | 8%      |
| 1001-2000      | 88        | 6.23%   |
| 51-100         | 72        | 5.1%    |
| 21-50          | 34        | 2.41%   |
| More than 3000 | 15        | 1.06%   |
| 2001-3000      | 15        | 1.06%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 592       | 41.11%  |
| 21-50          | 205       | 14.24%  |
| 101-250        | 180       | 12.5%   |
| 51-100         | 171       | 11.88%  |
| Unknown        | 119       | 8.26%   |
| 251-500        | 95        | 6.6%    |
| 501-1000       | 48        | 3.33%   |
| 1001-2000      | 25        | 1.74%   |
| 2001-3000      | 3         | 0.21%   |
| More than 3000 | 2         | 0.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| HGST HTS725050A7E630 500GB                          | 4         | 4      | 3.77%   |
| Toshiba MQ01ABD100 1TB                              | 3         | 3      | 2.83%   |
| SK hynix PC711 HFS512GDE9X073N 512GB                | 3         | 3      | 2.83%   |
| SK hynix HFS128G39TND-N210A 128GB SSD               | 3         | 3      | 2.83%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                | 3         | 3      | 2.83%   |
| Seagate ST9500325AS 500GB                           | 3         | 3      | 2.83%   |
| WDC WD5000LPLX-60ZNTT1 500GB                        | 2         | 2      | 1.89%   |
| Samsung Electronics SSD 870 EVO 500GB               | 2         | 2      | 1.89%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 2         | 2      | 1.89%   |
| Kingston SV300S37A120G 120GB SSD                    | 2         | 2      | 1.89%   |
| HGST HTS725032A7E630 320GB                          | 2         | 2      | 1.89%   |
| HGST HTS545050A7E680 500GB                          | 2         | 2      | 1.89%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 1      | 0.94%   |
| WDC WD6400BPVT-22HXZT3 640GB                        | 1         | 1      | 0.94%   |
| WDC WD5000LPVT-08G33T1 500GB                        | 1         | 1      | 0.94%   |
| WDC WD5000LPCX-00VHAT0 500GB                        | 1         | 1      | 0.94%   |
| WDC WD400UE-22HCT0 40GB                             | 1         | 1      | 0.94%   |
| WDC WD3200BPVT-80ZEST0 320GB                        | 1         | 1      | 0.94%   |
| WDC WD3200BPVT-75ZEST0 320GB                        | 1         | 1      | 0.94%   |
| WDC WD3200BEVT-80A0RT0 320GB                        | 1         | 1      | 0.94%   |
| WDC WD3200BEVT-00A0RT0 320GB                        | 1         | 1      | 0.94%   |
| WDC WD2500BEVT-22A23T0 250GB                        | 1         | 1      | 0.94%   |
| WDC WD1600BEVT-60A23T0 160GB                        | 1         | 1      | 0.94%   |
| WDC WD10SPZX-60Z10T0 1TB                            | 1         | 1      | 0.94%   |
| WDC WD Blue SA510 2.5 1000GB SSD                    | 1         | 1      | 0.94%   |
| Toshiba MQ01ACF032 320GB                            | 1         | 1      | 0.94%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 1      | 0.94%   |
| Toshiba MK6475GSX 640GB                             | 1         | 1      | 0.94%   |
| Toshiba MK3259GSXP 320GB                            | 1         | 1      | 0.94%   |
| SK hynix SH920 2.5 7MM 128GB SSD                    | 1         | 1      | 0.94%   |
| SK hynix HFS256G39TND-N210A 256GB SSD               | 1         | 1      | 0.94%   |
| SK hynix HFS128G3BTND-N210A 128GB SSD               | 1         | 1      | 0.94%   |
| ShiJi 1TB                                           | 1         | 3      | 0.94%   |
| Seagate ST9320325AS 320GB                           | 1         | 1      | 0.94%   |
| Seagate ST9250827AS 250GB                           | 1         | 1      | 0.94%   |
| Seagate ST9250414ASG 250GB                          | 1         | 1      | 0.94%   |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 1      | 0.94%   |
| Seagate ST500LM021-1KJ152 500GB                     | 1         | 1      | 0.94%   |
| Seagate ST320LT007-9ZV142 320GB                     | 1         | 1      | 0.94%   |
| Seagate ST320LM001 HN-M320MBB 320GB                 | 1         | 1      | 0.94%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 15        | 15     | 14.15%  |
| HGST                | 14        | 14     | 13.21%  |
| SK hynix            | 12        | 12     | 11.32%  |
| Seagate             | 12        | 12     | 11.32%  |
| Samsung Electronics | 10        | 11     | 9.43%   |
| Intel               | 8         | 8      | 7.55%   |
| Toshiba             | 7         | 7      | 6.6%    |
| Hitachi             | 7         | 9      | 6.6%    |
| SanDisk             | 4         | 4      | 3.77%   |
| Micron Technology   | 4         | 4      | 3.77%   |
| Kingston            | 4         | 4      | 3.77%   |
| Kimtigo             | 2         | 2      | 1.89%   |
| Crucial             | 2         | 2      | 1.89%   |
| ShiJi               | 1         | 3      | 0.94%   |
| LITEON              | 1         | 1      | 0.94%   |
| JMicron Technology  | 1         | 1      | 0.94%   |
| HECTRON             | 1         | 1      | 0.94%   |
| Dogfish             | 1         | 1      | 0.94%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 14        | 14     | 25.45%  |
| WDC                 | 13        | 13     | 23.64%  |
| Seagate             | 12        | 12     | 21.82%  |
| Toshiba             | 7         | 7      | 12.73%  |
| Hitachi             | 7         | 9      | 12.73%  |
| Samsung Electronics | 1         | 1      | 1.82%   |
| JMicron Technology  | 1         | 1      | 1.82%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 55        | 57     | 51.89%  |
| SSD  | 36        | 36     | 33.96%  |
| NVMe | 15        | 18     | 14.15%  |

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
| Works    | 876       | 1138   | 59.39%  |
| Detected | 495       | 674    | 33.56%  |
| Malfunc  | 104       | 111    | 7.05%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 756       | 46.81%  |
| Samsung Electronics                     | 224       | 13.87%  |
| AMD                                     | 155       | 9.6%    |
| SanDisk                                 | 115       | 7.12%   |
| SK hynix                                | 74        | 4.58%   |
| Micron Technology                       | 58        | 3.59%   |
| Kingston Technology Company             | 35        | 2.17%   |
| Toshiba America Info Systems            | 28        | 1.73%   |
| KIOXIA                                  | 25        | 1.55%   |
| Phison Electronics                      | 24        | 1.49%   |
| Micron/Crucial Technology               | 22        | 1.36%   |
| Silicon Motion                          | 15        | 0.93%   |
| ADATA Technology                        | 14        | 0.87%   |
| Nvidia                                  | 13        | 0.8%    |
| MAXIO Technology (Hangzhou)             | 10        | 0.62%   |
| Union Memory (Shenzhen)                 | 8         | 0.5%    |
| Solid State Storage Technology          | 8         | 0.5%    |
| Realtek Semiconductor                   | 6         | 0.37%   |
| Apple                                   | 5         | 0.31%   |
| Yangtze Memory Technologies             | 4         | 0.25%   |
| Seagate Technology                      | 3         | 0.19%   |
| Transcend                               | 2         | 0.12%   |
| Marvell Technology Group                | 2         | 0.12%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.06%   |
| Shenzhen Unionmemory Information System | 1         | 0.06%   |
| ShenZhen TIGO Semiconductor             | 1         | 0.06%   |
| Shenzhen Longsys Electronics            | 1         | 0.06%   |
| Lite-On Technology                      | 1         | 0.06%   |
| Jiangsu Huacun Elec.                    | 1         | 0.06%   |
| INNOGRIT                                | 1         | 0.06%   |
| Biwin Storage Technology                | 1         | 0.06%   |
| ASMedia Technology                      | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 138       | 8.11%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 95        | 5.58%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 73        | 4.29%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 68        | 4%      |
| Intel Volume Management Device NVMe RAID Controller                            | 66        | 3.88%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 62        | 3.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 52        | 3.06%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 49        | 2.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 49        | 2.88%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 39        | 2.29%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 36        | 2.12%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 35        | 2.06%   |
| Intel Tiger Lake-LP SATA Controller                                            | 31        | 1.82%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 30        | 1.76%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 27        | 1.59%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 26        | 1.53%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 26        | 1.53%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 22        | 1.29%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 21        | 1.23%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 20        | 1.18%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 20        | 1.18%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 19        | 1.12%   |
| Intel Comet Lake SATA AHCI Controller                                          | 18        | 1.06%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 18        | 1.06%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 16        | 0.94%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 16        | 0.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 15        | 0.88%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 14        | 0.82%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 14        | 0.82%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 14        | 0.82%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 13        | 0.76%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                     | 13        | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 13        | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 13        | 0.76%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 12        | 0.71%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 12        | 0.71%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 12        | 0.71%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 11        | 0.65%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 11        | 0.65%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 11        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 787       | 48.28%  |
| NVMe | 667       | 40.92%  |
| RAID | 128       | 7.85%   |
| IDE  | 48        | 2.94%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 1079      | 78.08%  |
| AMD          | 299       | 21.64%  |
| ARM          | 2         | 0.14%   |
| CentaurHauls | 1         | 0.07%   |
| Unknown      | 1         | 0.07%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N3060 @ 1.60GHz             | 38        | 2.75%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 38        | 2.75%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 36        | 2.6%    |
| Intel 12th Gen Core i5-1235U                  | 22        | 1.59%   |
| AMD PRO A6-9500B R5, 6 COMPUTE CORES 2C+4G    | 22        | 1.59%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 19        | 1.37%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 17        | 1.23%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 17        | 1.23%   |
| Intel 12th Gen Core i7-12700H                 | 16        | 1.16%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 15        | 1.08%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 15        | 1.08%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 14        | 1.01%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 14        | 1.01%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 14        | 1.01%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 14        | 1.01%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 14        | 1.01%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 14        | 1.01%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 13        | 0.94%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 13        | 0.94%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 13        | 0.94%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 12        | 0.87%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 12        | 0.87%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 12        | 0.87%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 11        | 0.79%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 11        | 0.79%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 11        | 0.79%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 11        | 0.79%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 11        | 0.79%   |
| Intel Celeron CPU 3865U @ 1.80GHz             | 11        | 0.79%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 11        | 0.79%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 10        | 0.72%   |
| Intel 12th Gen Core i7-1255U                  | 10        | 0.72%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 10        | 0.72%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 9         | 0.65%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 9         | 0.65%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 9         | 0.65%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 9         | 0.65%   |
| AMD Ryzen 7 5825U with Radeon Graphics        | 8         | 0.58%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 7         | 0.51%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 7         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Other                          | 285       | 20.59%  |
| Intel Core i5                  | 265       | 19.15%  |
| Intel Core i7                  | 209       | 15.1%   |
| Intel Celeron                  | 119       | 8.6%    |
| Intel Core i3                  | 103       | 7.44%   |
| AMD Ryzen 5                    | 74        | 5.35%   |
| AMD Ryzen 7                    | 73        | 5.27%   |
| Intel Core 2 Duo               | 42        | 3.03%   |
| AMD Ryzen 7 PRO                | 28        | 2.02%   |
| Intel Pentium                  | 24        | 1.73%   |
| Intel Atom                     | 23        | 1.66%   |
| AMD Ryzen 3                    | 14        | 1.01%   |
| AMD Ryzen 9                    | 12        | 0.87%   |
| AMD Ryzen 5 PRO                | 12        | 0.87%   |
| AMD E                          | 10        | 0.72%   |
| Intel Pentium Dual-Core        | 8         | 0.58%   |
| AMD A6                         | 7         | 0.51%   |
| AMD PRO A10                    | 6         | 0.43%   |
| Intel Pentium Silver           | 5         | 0.36%   |
| Intel Pentium M                | 5         | 0.36%   |
| Intel Core 2                   | 5         | 0.36%   |
| AMD E1                         | 5         | 0.36%   |
| Intel Xeon                     | 4         | 0.29%   |
| Intel Genuine                  | 4         | 0.29%   |
| AMD A8                         | 4         | 0.29%   |
| AMD A4                         | 4         | 0.29%   |
| Intel Pentium Dual             | 3         | 0.22%   |
| Intel Core i9                  | 3         | 0.22%   |
| Intel Celeron M                | 3         | 0.22%   |
| AMD E2                         | 3         | 0.22%   |
| AMD Athlon II                  | 3         | 0.22%   |
| AMD Athlon                     | 3         | 0.22%   |
| Intel Core m5                  | 2         | 0.14%   |
| AMD Turion 64 X2 Mobile        | 2         | 0.14%   |
| AMD A10                        | 2         | 0.14%   |
| Intel Pentium Gold             | 1         | 0.07%   |
| Intel Core m3                  | 1         | 0.07%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.07%   |
| AMD Sempron                    | 1         | 0.07%   |
| AMD Ryzen 3 PRO                | 1         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 559       | 40.45%  |
| 4      | 405       | 29.31%  |
| 8      | 123       | 8.9%    |
| 6      | 112       | 8.1%    |
| 10     | 58        | 4.2%    |
| 1      | 45        | 3.26%   |
| 14     | 37        | 2.68%   |
| 12     | 35        | 2.53%   |
| 16     | 4         | 0.29%   |
| 24     | 2         | 0.14%   |
| 5      | 2         | 0.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1382      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1051      | 75.88%  |
| 1      | 334       | 24.12%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1367      | 98.91%  |
| 32-bit         | 13        | 0.94%   |
| 64-bit         | 1         | 0.07%   |
| Unknown        | 1         | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 401       | 28.64%  |
| 0x806c1    | 62        | 4.43%   |
| 0x306a9    | 47        | 3.36%   |
| 0x406c4    | 41        | 2.93%   |
| 0x906a4    | 40        | 2.86%   |
| 0x206a7    | 40        | 2.86%   |
| 0x906a3    | 39        | 2.79%   |
| 0x406e3    | 38        | 2.71%   |
| 0x906eb    | 36        | 2.57%   |
| 0x806ec    | 35        | 2.5%    |
| 0x806e9    | 33        | 2.36%   |
| 0x806ea    | 29        | 2.07%   |
| 0x1067a    | 29        | 2.07%   |
| 0x08108109 | 29        | 2.07%   |
| 0x306d4    | 28        | 2%      |
| 0x306c3    | 28        | 2%      |
| 0x30678    | 28        | 2%      |
| 0x0a50000d | 26        | 1.86%   |
| 0x0600611a | 26        | 1.86%   |
| 0x0a50000c | 24        | 1.71%   |
| 0x40651    | 21        | 1.5%    |
| 0xb06a2    | 20        | 1.43%   |
| 0x906ea    | 19        | 1.36%   |
| 0x08608103 | 18        | 1.29%   |
| 0x706a8    | 17        | 1.21%   |
| 0x20655    | 14        | 1%      |
| 0x806d1    | 13        | 0.93%   |
| 0x0a404102 | 13        | 0.93%   |
| 0xb06a3    | 11        | 0.79%   |
| 0x08600106 | 11        | 0.79%   |
| 0xa0652    | 9         | 0.64%   |
| 0x906e9    | 9         | 0.64%   |
| 0x6fd      | 9         | 0.64%   |
| 0x506e3    | 8         | 0.57%   |
| 0x06006705 | 8         | 0.57%   |
| 0x706e5    | 7         | 0.5%    |
| 0x10676    | 7         | 0.5%    |
| 0x806eb    | 6         | 0.43%   |
| 0x0a704103 | 6         | 0.43%   |
| 0x08608104 | 6         | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 247       | 17.83%  |
| Alderlake Hybrid | 118       | 8.52%   |
| Unknown          | 110       | 7.94%   |
| TigerLake        | 89        | 6.43%   |
| Silvermont       | 81        | 5.85%   |
| Zen 3            | 74        | 5.34%   |
| IvyBridge        | 72        | 5.2%    |
| Skylake          | 69        | 4.98%   |
| Haswell          | 68        | 4.91%   |
| SandyBridge      | 64        | 4.62%   |
| Penryn           | 44        | 3.18%   |
| Zen+             | 42        | 3.03%   |
| Excavator        | 39        | 2.82%   |
| Broadwell        | 35        | 2.53%   |
| Zen 2            | 29        | 2.09%   |
| Westmere         | 28        | 2.02%   |
| Icelake          | 28        | 2.02%   |
| Goldmont plus    | 27        | 1.95%   |
| CometLake        | 21        | 1.52%   |
| Core             | 20        | 1.44%   |
| Bobcat           | 15        | 1.08%   |
| Bonnell          | 13        | 0.94%   |
| Goldmont         | 9         | 0.65%   |
| P6               | 8         | 0.58%   |
| Jaguar           | 7         | 0.51%   |
| Zen              | 5         | 0.36%   |
| Piledriver       | 5         | 0.36%   |
| Puma             | 4         | 0.29%   |
| K8 Hammer        | 3         | 0.22%   |
| K10              | 3         | 0.22%   |
| Tremont          | 2         | 0.14%   |
| Nehalem          | 2         | 0.14%   |
| K8 & K10 hybrid  | 2         | 0.14%   |
| K10 Llano        | 1         | 0.07%   |
| Gracemont        | 1         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1014      | 60.11%  |
| AMD                              | 351       | 20.81%  |
| Nvidia                           | 320       | 18.97%  |
| Zhaoxin                          | 1         | 0.06%   |
| Silicon Integrated Systems [SiS] | 1         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 77        | 4.46%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 70        | 4.06%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 59        | 3.42%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 50        | 2.9%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 49        | 2.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 47        | 2.72%   |
| Intel UHD Graphics 620                                                                   | 46        | 2.67%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 45        | 2.61%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 39        | 2.26%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 37        | 2.14%   |
| AMD Lucienne                                                                             | 37        | 2.14%   |
| Intel HD Graphics 620                                                                    | 36        | 2.09%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 36        | 2.09%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 34        | 1.97%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 33        | 1.91%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 32        | 1.86%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 31        | 1.8%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 29        | 1.68%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 29        | 1.68%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 29        | 1.68%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 27        | 1.57%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 27        | 1.57%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 27        | 1.57%   |
| AMD Barcelo                                                                              | 24        | 1.39%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 23        | 1.33%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 23        | 1.33%   |
| Intel Core Processor Integrated Graphics Controller                                      | 21        | 1.22%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 20        | 1.16%   |
| AMD Rembrandt [Radeon 680M]                                                              | 19        | 1.1%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 17        | 0.99%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 15        | 0.87%   |
| Intel HD Graphics 6000                                                                   | 15        | 0.87%   |
| Intel HD Graphics 610                                                                    | 13        | 0.75%   |
| Intel HD Graphics 5500                                                                   | 13        | 0.75%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 12        | 0.7%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 12        | 0.7%    |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 12        | 0.7%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 11        | 0.64%   |
| Intel HD Graphics 630                                                                    | 11        | 0.64%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 10        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 717       | 51.73%  |
| 1 x AMD        | 258       | 18.61%  |
| Intel + Nvidia | 229       | 16.52%  |
| 1 x Nvidia     | 52        | 3.75%   |
| AMD + Nvidia   | 40        | 2.89%   |
| Intel + AMD    | 36        | 2.6%    |
| 2 x Intel      | 29        | 2.09%   |
| 2 x AMD        | 17        | 1.23%   |
| Other          | 5         | 0.36%   |
| 2 x Nvidia     | 1         | 0.07%   |
| 1 x Zhaoxin    | 1         | 0.07%   |
| 1 x SiS        | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1164      | 83.86%  |
| Proprietary | 119       | 8.57%   |
| Unknown     | 105       | 7.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1029      | 74.08%  |
| 0.01-0.5   | 147       | 10.58%  |
| 1.01-2.0   | 73        | 5.26%   |
| 3.01-4.0   | 56        | 4.03%   |
| 0.51-1.0   | 49        | 3.53%   |
| 5.01-6.0   | 16        | 1.15%   |
| 7.01-8.0   | 13        | 0.94%   |
| 2.01-3.0   | 3         | 0.22%   |
| 16.01-24.0 | 1         | 0.07%   |
| 8.01-16.0  | 1         | 0.07%   |
| 0          | 1         | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 310       | 20.82%  |
| BOE                     | 268       | 18%     |
| Chimei Innolux          | 202       | 13.57%  |
| LG Display              | 155       | 10.41%  |
| Samsung Electronics     | 121       | 8.13%   |
| Apple                   | 50        | 3.36%   |
| Sharp                   | 39        | 2.62%   |
| Dell                    | 37        | 2.48%   |
| PANDA                   | 35        | 2.35%   |
| InfoVision              | 32        | 2.15%   |
| Lenovo                  | 26        | 1.75%   |
| Goldstar                | 22        | 1.48%   |
| Chi Mei Optoelectronics | 19        | 1.28%   |
| CSO                     | 16        | 1.07%   |
| Philips                 | 15        | 1.01%   |
| Hewlett-Packard         | 15        | 1.01%   |
| LG Philips              | 12        | 0.81%   |
| BenQ                    | 12        | 0.81%   |
| AOC                     | 12        | 0.81%   |
| Acer                    | 9         | 0.6%    |
| Iiyama                  | 8         | 0.54%   |
| ASUSTek Computer        | 8         | 0.54%   |
| ViewSonic               | 5         | 0.34%   |
| Ancor Communications    | 4         | 0.27%   |
| HKC                     | 3         | 0.2%    |
| HannStar                | 3         | 0.2%    |
| Vizio                   | 2         | 0.13%   |
| Toshiba                 | 2         | 0.13%   |
| TMX                     | 2         | 0.13%   |
| Sony                    | 2         | 0.13%   |
| NEC Computers           | 2         | 0.13%   |
| MSI                     | 2         | 0.13%   |
| Mi                      | 2         | 0.13%   |
| InnoLux Display         | 2         | 0.13%   |
| CPT                     | 2         | 0.13%   |
| BOE Technology Group    | 2         | 0.13%   |
| ZLX                     | 1         | 0.07%   |
| Xiaomi                  | 1         | 0.07%   |
| VIE                     | 1         | 0.07%   |
| Valve                   | 1         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                  | 29        | 1.93%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                  | 22        | 1.47%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 20        | 1.33%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 14        | 0.93%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 12        | 0.8%    |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 11        | 0.73%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 10        | 0.67%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 9         | 0.6%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 8         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 7         | 0.47%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 7         | 0.47%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 7         | 0.47%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 7         | 0.47%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 7         | 0.47%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 6         | 0.4%    |
| InfoVision LCD Monitor IVO048E 1366x768 256x144mm 11.6-inch           | 6         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch       | 6         | 0.4%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 6         | 0.4%    |
| AU Optronics LCD Monitor AUO80ED 1920x1080 344x193mm 15.5-inch        | 6         | 0.4%    |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 6         | 0.4%    |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 5         | 0.33%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 5         | 0.33%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 5         | 0.33%   |
| InfoVision LCD Monitor IVO0533 1366x768 293x165mm 13.2-inch           | 5         | 0.33%   |
| Chimei Innolux LCD Monitor CMN153B 1920x1080 344x193mm 15.5-inch      | 5         | 0.33%   |
| BOE LCD Monitor BOE0BCA 2256x1504 285x190mm 13.5-inch                 | 5         | 0.33%   |
| BOE LCD Monitor BOE08D5 1920x1080 344x194mm 15.5-inch                 | 5         | 0.33%   |
| BOE LCD Monitor BOE06CF 1366x768 277x156mm 12.5-inch                  | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO499F 1920x1080 344x194mm 15.5-inch        | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch         | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch         | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 5         | 0.33%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 5         | 0.33%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 4         | 0.27%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch  | 4         | 0.27%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 4         | 0.27%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 4         | 0.27%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 4         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 4         | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 654       | 46.22%  |
| 1366x768 (WXGA)    | 346       | 24.45%  |
| 1920x1200 (WUXGA)  | 68        | 4.81%   |
| 2560x1440 (QHD)    | 46        | 3.25%   |
| 1600x900 (HD+)     | 46        | 3.25%   |
| 3840x2160 (4K)     | 40        | 2.83%   |
| 1280x800 (WXGA)    | 33        | 2.33%   |
| 1440x900 (WXGA+)   | 32        | 2.26%   |
| 2560x1600          | 27        | 1.91%   |
| 2880x1800          | 18        | 1.27%   |
| 3840x2400          | 15        | 1.06%   |
| 1680x1050 (WSXGA+) | 12        | 0.85%   |
| 1024x600           | 9         | 0.64%   |
| 3440x1440          | 8         | 0.57%   |
| 2256x1504          | 8         | 0.57%   |
| 3200x2000          | 5         | 0.35%   |
| 3200x1800 (QHD+)   | 5         | 0.35%   |
| 2560x1080          | 5         | 0.35%   |
| 3072x1920          | 4         | 0.28%   |
| 2160x1440          | 4         | 0.28%   |
| 1600x1200          | 4         | 0.28%   |
| 1920x540           | 3         | 0.21%   |
| 1280x1024 (SXGA)   | 3         | 0.21%   |
| 3456x2160          | 2         | 0.14%   |
| 3000x2000          | 2         | 0.14%   |
| 2880x1620          | 2         | 0.14%   |
| Unknown            | 2         | 0.14%   |
| 800x1280           | 1         | 0.07%   |
| 4480x1600          | 1         | 0.07%   |
| 3840x1600          | 1         | 0.07%   |
| 3840x1100          | 1         | 0.07%   |
| 2966x900           | 1         | 0.07%   |
| 2520x1680          | 1         | 0.07%   |
| 2240x1400          | 1         | 0.07%   |
| 1600x2560          | 1         | 0.07%   |
| 1400x1050          | 1         | 0.07%   |
| 1360x768           | 1         | 0.07%   |
| 1024x768 (XGA)     | 1         | 0.07%   |
| 1024x576           | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 523       | 35.15%  |
| 13      | 261       | 17.54%  |
| 14      | 214       | 14.38%  |
| 11      | 82        | 5.51%   |
| 17      | 73        | 4.91%   |
| 12      | 52        | 3.49%   |
| 24      | 50        | 3.36%   |
| 16      | 48        | 3.23%   |
| 27      | 46        | 3.09%   |
| 23      | 28        | 1.88%   |
| 21      | 23        | 1.55%   |
| 31      | 13        | 0.87%   |
| 34      | 9         | 0.6%    |
| 10      | 9         | 0.6%    |
| Unknown | 9         | 0.6%    |
| 19      | 7         | 0.47%   |
| 18      | 7         | 0.47%   |
| 22      | 6         | 0.4%    |
| 20      | 5         | 0.34%   |
| 28      | 3         | 0.2%    |
| 8       | 3         | 0.2%    |
| 72      | 2         | 0.13%   |
| 32      | 2         | 0.13%   |
| 29      | 2         | 0.13%   |
| 25      | 2         | 0.13%   |
| 86      | 1         | 0.07%   |
| 69      | 1         | 0.07%   |
| 48      | 1         | 0.07%   |
| 41      | 1         | 0.07%   |
| 40      | 1         | 0.07%   |
| 37      | 1         | 0.07%   |
| 35      | 1         | 0.07%   |
| 33      | 1         | 0.07%   |
| 7       | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 898       | 60.68%  |
| 201-300     | 271       | 18.31%  |
| 501-600     | 119       | 8.04%   |
| 351-400     | 93        | 6.28%   |
| 401-500     | 45        | 3.04%   |
| 601-700     | 20        | 1.35%   |
| 701-800     | 12        | 0.81%   |
| Unknown     | 9         | 0.61%   |
| 801-900     | 3         | 0.2%    |
| 1501-2000   | 3         | 0.2%    |
| 101-200     | 3         | 0.2%    |
| 1001-1500   | 2         | 0.14%   |
| 901-1000    | 1         | 0.07%   |
| 1-100       | 1         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1081      | 80.13%  |
| 16/10   | 218       | 16.16%  |
| 3/2     | 18        | 1.33%   |
| 21/9    | 12        | 0.89%   |
| Unknown | 7         | 0.52%   |
| 4/3     | 5         | 0.37%   |
| 5/4     | 3         | 0.22%   |
| 3.40    | 1         | 0.07%   |
| 2.65    | 1         | 0.07%   |
| 0.67    | 1         | 0.07%   |
| 0.58    | 1         | 0.07%   |
| 0.56    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 529       | 35.6%   |
| 81-90          | 380       | 25.57%  |
| 71-80          | 85        | 5.72%   |
| 51-60          | 83        | 5.59%   |
| 201-250        | 82        | 5.52%   |
| 121-130        | 65        | 4.37%   |
| 61-70          | 52        | 3.5%    |
| 301-350        | 47        | 3.16%   |
| 111-120        | 41        | 2.76%   |
| 351-500        | 29        | 1.95%   |
| 251-300        | 19        | 1.28%   |
| 151-200        | 19        | 1.28%   |
| 41-50          | 9         | 0.61%   |
| 131-140        | 9         | 0.61%   |
| 91-100         | 9         | 0.61%   |
| Unknown        | 9         | 0.61%   |
| 141-150        | 7         | 0.47%   |
| More than 1000 | 5         | 0.34%   |
| 1-40           | 4         | 0.27%   |
| 501-1000       | 3         | 0.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 732       | 50%     |
| 101-120       | 323       | 22.06%  |
| 51-100        | 175       | 11.95%  |
| 161-240       | 158       | 10.79%  |
| More than 240 | 59        | 4.03%   |
| Unknown       | 9         | 0.61%   |
| 1-50          | 8         | 0.55%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1105      | 79.21%  |
| 2     | 185       | 13.26%  |
| 0     | 83        | 5.95%   |
| 3     | 21        | 1.51%   |
| 4     | 1         | 0.07%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 794       | 37.29%  |
| Realtek Semiconductor             | 666       | 31.28%  |
| Qualcomm Atheros                  | 208       | 9.77%   |
| Broadcom                          | 110       | 5.17%   |
| MediaTek                          | 82        | 3.85%   |
| Broadcom Limited                  | 32        | 1.5%    |
| Qualcomm                          | 29        | 1.36%   |
| ASIX Electronics                  | 24        | 1.13%   |
| Marvell Technology Group          | 18        | 0.85%   |
| TP-Link                           | 14        | 0.66%   |
| Ericsson Business Mobile Networks | 13        | 0.61%   |
| Xiaomi                            | 12        | 0.56%   |
| Nvidia                            | 12        | 0.56%   |
| Sierra Wireless                   | 11        | 0.52%   |
| Ralink Technology                 | 11        | 0.52%   |
| Samsung Electronics               | 10        | 0.47%   |
| Ralink                            | 9         | 0.42%   |
| Lenovo                            | 9         | 0.42%   |
| Hewlett-Packard                   | 7         | 0.33%   |
| Google                            | 7         | 0.33%   |
| DisplayLink                       | 6         | 0.28%   |
| JMicron Technology                | 4         | 0.19%   |
| Dell                              | 4         | 0.19%   |
| Huawei Technologies               | 3         | 0.14%   |
| Fibocom                           | 3         | 0.14%   |
| D-Link                            | 3         | 0.14%   |
| OPPO Electronics                  | 2         | 0.09%   |
| NetGear                           | 2         | 0.09%   |
| Microsoft                         | 2         | 0.09%   |
| Microchip Technology              | 2         | 0.09%   |
| Linksys                           | 2         | 0.09%   |
| Attansic Technology               | 2         | 0.09%   |
| ASUSTek Computer                  | 2         | 0.09%   |
| Wacom                             | 1         | 0.05%   |
| U-Blox                            | 1         | 0.05%   |
| Spreadtrum Communications         | 1         | 0.05%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.05%   |
| Quectel Wireless Solutions        | 1         | 0.05%   |
| Qualcomm Atheros Communications   | 1         | 0.05%   |
| QinHeng Electronics               | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 417       | 16.31%  |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 76        | 2.97%   |
| Intel Wireless 8265 / 8275                                             | 71        | 2.78%   |
| Intel Wireless 7265                                                    | 70        | 2.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 69        | 2.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 68        | 2.66%   |
| Intel Wi-Fi 6 AX201                                                    | 64        | 2.5%    |
| Intel Wi-Fi 6 AX200                                                    | 55        | 2.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 55        | 2.15%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 54        | 2.11%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 52        | 2.03%   |
| Intel Wireless 7260                                                    | 50        | 1.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 45        | 1.76%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 43        | 1.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 41        | 1.6%    |
| Intel Wireless 8260                                                    | 35        | 1.37%   |
| Intel Ethernet Connection (4) I219-LM                                  | 35        | 1.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 31        | 1.21%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 29        | 1.13%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 28        | 1.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 28        | 1.1%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 25        | 0.98%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 23        | 0.9%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 22        | 0.86%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 22        | 0.86%   |
| Intel Ethernet Connection (4) I219-V                                   | 22        | 0.86%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 22        | 0.86%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 20        | 0.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 20        | 0.78%   |
| ASIX AX88179 Gigabit Ethernet                                          | 20        | 0.78%   |
| Intel Ethernet Connection I219-LM                                      | 19        | 0.74%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 18        | 0.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 18        | 0.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 17        | 0.67%   |
| Intel Ethernet Connection (16) I219-V                                  | 17        | 0.67%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 17        | 0.67%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 16        | 0.63%   |
| Intel Wireless 3165                                                    | 14        | 0.55%   |
| Intel Ethernet Connection I219-V                                       | 14        | 0.55%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 13        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 746       | 52.83%  |
| Realtek Semiconductor             | 200       | 14.16%  |
| Qualcomm Atheros                  | 179       | 12.68%  |
| Broadcom                          | 91        | 6.44%   |
| MediaTek                          | 80        | 5.67%   |
| Broadcom Limited                  | 28        | 1.98%   |
| Qualcomm                          | 24        | 1.7%    |
| TP-Link                           | 12        | 0.85%   |
| Sierra Wireless                   | 11        | 0.78%   |
| Ralink Technology                 | 11        | 0.78%   |
| Ralink                            | 9         | 0.64%   |
| Fibocom                           | 3         | 0.21%   |
| D-Link                            | 3         | 0.21%   |
| NetGear                           | 2         | 0.14%   |
| Microsoft                         | 2         | 0.14%   |
| Linksys                           | 2         | 0.14%   |
| ASUSTek Computer                  | 2         | 0.14%   |
| Wacom                             | 1         | 0.07%   |
| Quectel Wireless Solutions        | 1         | 0.07%   |
| Qualcomm Atheros Communications   | 1         | 0.07%   |
| Hewlett-Packard                   | 1         | 0.07%   |
| Ericsson Business Mobile Networks | 1         | 0.07%   |
| Dell                              | 1         | 0.07%   |
| D-Link System                     | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P PCH CNVi WiFi                                     | 76        | 5.36%   |
| Intel Wireless 8265 / 8275                                           | 71        | 5.01%   |
| Intel Wireless 7265                                                  | 70        | 4.94%   |
| Intel Wi-Fi 6 AX201                                                  | 64        | 4.52%   |
| Intel Wi-Fi 6 AX200                                                  | 55        | 3.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 54        | 3.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 52        | 3.67%   |
| Intel Wireless 7260                                                  | 50        | 3.53%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 45        | 3.18%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 43        | 3.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 41        | 2.89%   |
| Intel Wireless 8260                                                  | 35        | 2.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 31        | 2.19%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 29        | 2.05%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 28        | 1.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 28        | 1.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 25        | 1.76%   |
| Qualcomm QCNFA765 Wireless Network Adapter                           | 23        | 1.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 22        | 1.55%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 22        | 1.55%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 22        | 1.55%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 20        | 1.41%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 20        | 1.41%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 18        | 1.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 18        | 1.27%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 17        | 1.2%    |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 17        | 1.2%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 16        | 1.13%   |
| Intel Wireless 3165                                                  | 14        | 0.99%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 13        | 0.92%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 12        | 0.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 11        | 0.78%   |
| Intel Gemini Lake PCH CNVi WiFi                                      | 11        | 0.78%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 10        | 0.71%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                    | 9         | 0.64%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 9         | 0.64%   |
| Broadcom BCM43142 802.11b/g/n                                        | 9         | 0.64%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 8         | 0.56%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 8         | 0.56%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 8         | 0.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 572       | 52.62%  |
| Intel                            | 299       | 27.51%  |
| Qualcomm Atheros                 | 49        | 4.51%   |
| Broadcom                         | 36        | 3.31%   |
| ASIX Electronics                 | 24        | 2.21%   |
| Marvell Technology Group         | 18        | 1.66%   |
| Xiaomi                           | 12        | 1.1%    |
| Nvidia                           | 12        | 1.1%    |
| Samsung Electronics              | 10        | 0.92%   |
| Lenovo                           | 9         | 0.83%   |
| Google                           | 7         | 0.64%   |
| DisplayLink                      | 6         | 0.55%   |
| Qualcomm                         | 5         | 0.46%   |
| JMicron Technology               | 4         | 0.37%   |
| Broadcom Limited                 | 4         | 0.37%   |
| Hewlett-Packard                  | 3         | 0.28%   |
| TP-Link                          | 2         | 0.18%   |
| OPPO Electronics                 | 2         | 0.18%   |
| Microchip Technology             | 2         | 0.18%   |
| MediaTek                         | 2         | 0.18%   |
| Huawei Technologies              | 2         | 0.18%   |
| Attansic Technology              | 2         | 0.18%   |
| Spreadtrum Communications        | 1         | 0.09%   |
| Silicon Integrated Systems [SiS] | 1         | 0.09%   |
| QinHeng Electronics              | 1         | 0.09%   |
| Cypress Semiconductor            | 1         | 0.09%   |
| Apple                            | 1         | 0.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 417       | 37.67%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 69        | 6.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 68        | 6.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 55        | 4.97%   |
| Intel Ethernet Connection (4) I219-LM                                  | 35        | 3.16%   |
| Intel Ethernet Connection (4) I219-V                                   | 22        | 1.99%   |
| ASIX AX88179 Gigabit Ethernet                                          | 20        | 1.81%   |
| Intel Ethernet Connection I219-LM                                      | 19        | 1.72%   |
| Intel Ethernet Connection (16) I219-V                                  | 17        | 1.54%   |
| Intel Ethernet Connection I219-V                                       | 14        | 1.26%   |
| Intel Ethernet Connection I217-V                                       | 12        | 1.08%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 11        | 0.99%   |
| Intel Ethernet Connection I218-LM                                      | 11        | 0.99%   |
| Intel Ethernet Connection I217-LM                                      | 10        | 0.9%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 9         | 0.81%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 9         | 0.81%   |
| Realtek RTL8125 2.5GbE Controller                                      | 9         | 0.81%   |
| Nvidia MCP79 Ethernet                                                  | 9         | 0.81%   |
| Intel Ethernet Connection (13) I219-V                                  | 9         | 0.81%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 8         | 0.72%   |
| Realtek Killer E2600 GbE Controller                                    | 8         | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 8         | 0.72%   |
| Intel Ethernet Connection (6) I219-LM                                  | 8         | 0.72%   |
| Intel Ethernet Connection (16) I219-LM                                 | 8         | 0.72%   |
| Intel 82567LM Gigabit Network Connection                               | 8         | 0.72%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 8         | 0.72%   |
| Intel Ethernet Connection (3) I218-LM                                  | 7         | 0.63%   |
| Intel Ethernet Connection (13) I219-LM                                 | 7         | 0.63%   |
| Intel 82577LM Gigabit Network Connection                               | 7         | 0.63%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 7         | 0.63%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 6         | 0.54%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 5         | 0.45%   |
| Intel Ethernet Connection (6) I219-V                                   | 5         | 0.45%   |
| Intel Ethernet Connection (5) I219-LM                                  | 5         | 0.45%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 4         | 0.36%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 4         | 0.36%   |
| Intel Ethernet Connection (2) I219-LM                                  | 4         | 0.36%   |
| Intel 82579V Gigabit Network Connection                                | 4         | 0.36%   |
| DisplayLink Dell Universal Dock D6000                                  | 4         | 0.36%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 3         | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1353      | 56.26%  |
| Ethernet | 1020      | 42.41%  |
| Modem    | 30        | 1.25%   |
| Unknown  | 2         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1074      | 72.47%  |
| Ethernet | 408       | 27.53%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 902       | 65.22%  |
| 1     | 450       | 32.54%  |
| 0     | 22        | 1.59%   |
| 3     | 9         | 0.65%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1006      | 72.01%  |
| Yes  | 391       | 27.99%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 641       | 54.23%  |
| Realtek Semiconductor           | 121       | 10.24%  |
| Qualcomm Atheros Communications | 84        | 7.11%   |
| IMC Networks                    | 64        | 5.41%   |
| Foxconn / Hon Hai               | 50        | 4.23%   |
| Broadcom                        | 49        | 4.15%   |
| Apple                           | 45        | 3.81%   |
| Lite-On Technology              | 35        | 2.96%   |
| Dell                            | 16        | 1.35%   |
| Hewlett-Packard                 | 13        | 1.1%    |
| Realtek                         | 12        | 1.02%   |
| USI                             | 11        | 0.93%   |
| Cambridge Silicon Radio         | 9         | 0.76%   |
| MediaTek                        | 8         | 0.68%   |
| Toshiba                         | 7         | 0.59%   |
| Foxconn International           | 3         | 0.25%   |
| Ralink Technology               | 2         | 0.17%   |
| Micro Star International        | 2         | 0.17%   |
| ASUSTek Computer                | 2         | 0.17%   |
| Alps Electric                   | 2         | 0.17%   |
| TP-Link                         | 1         | 0.08%   |
| Taiyo Yuden                     | 1         | 0.08%   |
| Ralink                          | 1         | 0.08%   |
| Opticis                         | 1         | 0.08%   |
| Fujitsu                         | 1         | 0.08%   |
| Chicony Electronics             | 1         | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 229       | 19.37%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 120       | 10.15%  |
| Intel AX201 Bluetooth                               | 106       | 8.97%   |
| Realtek Bluetooth Radio                             | 100       | 8.46%   |
| Intel Bluetooth Device                              | 81        | 6.85%   |
| Intel AX200 Bluetooth                               | 53        | 4.48%   |
| Qualcomm Atheros  Bluetooth Device                  | 45        | 3.81%   |
| IMC Networks Wireless_Device                        | 35        | 2.96%   |
| Intel AX210 Bluetooth                               | 21        | 1.78%   |
| Foxconn / Hon Hai Wireless_Device                   | 21        | 1.78%   |
| Foxconn / Hon Hai Bluetooth Device                  | 21        | 1.78%   |
| Apple Bluetooth USB Host Controller                 | 21        | 1.78%   |
| Apple Bluetooth Host Controller                     | 18        | 1.52%   |
| Realtek  Bluetooth 4.2 Adapter                      | 16        | 1.35%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 15        | 1.27%   |
| Lite-On Wireless_Device                             | 15        | 1.27%   |
| IMC Networks Bluetooth Radio                        | 15        | 1.27%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 14        | 1.18%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 13        | 1.1%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 13        | 1.1%    |
| Realtek Bluetooth Radio                             | 12        | 1.02%   |
| USI Bluetooth Device                                | 11        | 0.93%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 11        | 0.93%   |
| Broadcom BCM2045B (BDC-2.1)                         | 10        | 0.85%   |
| Lite-On Bluetooth Device                            | 9         | 0.76%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 9         | 0.76%   |
| MediaTek Wireless_Device                            | 8         | 0.68%   |
| IMC Networks Bluetooth Device                       | 8         | 0.68%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 7         | 0.59%   |
| Intel Wireless-AC 3168 Bluetooth                    | 7         | 0.59%   |
| HP Broadcom 2070 Bluetooth Combo                    | 6         | 0.51%   |
| Dell BCM20702A0 Bluetooth Module                    | 6         | 0.51%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 0.42%   |
| Broadcom HP Portable SoftSailing                    | 5         | 0.42%   |
| Broadcom HP Portable Bumble Bee                     | 5         | 0.42%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 4         | 0.34%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 4         | 0.34%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 3         | 0.25%   |
| Qualcomm Atheros Bluetooth                          | 3         | 0.25%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 0.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1055      | 63.75%  |
| AMD                              | 319       | 19.27%  |
| Nvidia                           | 182       | 11%     |
| C-Media Electronics              | 13        | 0.79%   |
| Lenovo                           | 12        | 0.73%   |
| Realtek Semiconductor            | 9         | 0.54%   |
| Logitech                         | 9         | 0.54%   |
| JMTek                            | 6         | 0.36%   |
| Hewlett-Packard                  | 6         | 0.36%   |
| GN Netcom                        | 4         | 0.24%   |
| SteelSeries ApS                  | 3         | 0.18%   |
| Yamaha                           | 2         | 0.12%   |
| Texas Instruments                | 2         | 0.12%   |
| Kingston Technology              | 2         | 0.12%   |
| Generalplus Technology           | 2         | 0.12%   |
| Focusrite-Novation               | 2         | 0.12%   |
| Creative Technology              | 2         | 0.12%   |
| CMX Systems                      | 2         | 0.12%   |
| ASUSTek Computer                 | 2         | 0.12%   |
| Apple                            | 2         | 0.12%   |
| Zhaoxin                          | 1         | 0.06%   |
| Unknown                          | 1         | 0.06%   |
| Thomann                          | 1         | 0.06%   |
| Silicon Integrated Systems [SiS] | 1         | 0.06%   |
| Samson Technologies              | 1         | 0.06%   |
| RODE Microphones                 | 1         | 0.06%   |
| Plantronics                      | 1         | 0.06%   |
| Phoenix Audio Technologies       | 1         | 0.06%   |
| OPPO Electronics                 | 1         | 0.06%   |
| Microchip Technology             | 1         | 0.06%   |
| Fujitsu                          | 1         | 0.06%   |
| Cambridge Silicon Radio          | 1         | 0.06%   |
| Bose                             | 1         | 0.06%   |
| Beyerdynamic                     | 1         | 0.06%   |
| bestechnic                       | 1         | 0.06%   |
| Audient                          | 1         | 0.06%   |
| Astro Gaming                     | 1         | 0.06%   |
| AlfaPlus Semiconductor           | 1         | 0.06%   |
| Unknown                          | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 211       | 10.39%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 150       | 7.39%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 127       | 6.25%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 90        | 4.43%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 89        | 4.38%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 81        | 3.99%   |
| Intel Cannon Lake PCH cAVS                                                                        | 72        | 3.55%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 55        | 2.71%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 46        | 2.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 44        | 2.17%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 42        | 2.07%   |
| AMD Kabini HDMI/DP Audio                                                                          | 40        | 1.97%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 38        | 1.87%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 38        | 1.87%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 35        | 1.72%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 35        | 1.72%   |
| Intel Broadwell-U Audio Controller                                                                | 35        | 1.72%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 34        | 1.67%   |
| Nvidia Audio device                                                                               | 33        | 1.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 32        | 1.58%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 32        | 1.58%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 30        | 1.48%   |
| Intel 8 Series HD Audio Controller                                                                | 30        | 1.48%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 29        | 1.43%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 29        | 1.43%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 27        | 1.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 27        | 1.33%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 22        | 1.08%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 21        | 1.03%   |
| AMD FCH Azalia Controller                                                                         | 21        | 1.03%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 19        | 0.94%   |
| Intel Comet Lake PCH cAVS                                                                         | 18        | 0.89%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 16        | 0.79%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 15        | 0.74%   |
| Intel CM238 HD Audio Controller                                                                   | 14        | 0.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 14        | 0.69%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 13        | 0.64%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 13        | 0.64%   |
| AMD Wrestler HDMI Audio                                                                           | 13        | 0.64%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 12        | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 405       | 31.57%  |
| SK hynix                                | 267       | 20.81%  |
| Micron Technology                       | 173       | 13.48%  |
| Crucial                                 | 103       | 8.03%   |
| Unknown                                 | 68        | 5.3%    |
| Kingston                                | 66        | 5.14%   |
| Ramaxel Technology                      | 28        | 2.18%   |
| Elpida                                  | 26        | 2.03%   |
| A-DATA Technology                       | 18        | 1.4%    |
| Corsair                                 | 16        | 1.25%   |
| Unknown                                 | 13        | 1.01%   |
| Unknown (ABCD)                          | 11        | 0.86%   |
| Nanya Technology                        | 10        | 0.78%   |
| Smart                                   | 8         | 0.62%   |
| 4ea5                                    | 8         | 0.62%   |
| ff                                      | 7         | 0.55%   |
| Team                                    | 6         | 0.47%   |
| G.Skill                                 | 6         | 0.47%   |
| Transcend                               | 4         | 0.31%   |
| Teikon                                  | 4         | 0.31%   |
| Patriot                                 | 4         | 0.31%   |
| ASint Technology                        | 4         | 0.31%   |
| Timetec                                 | 3         | 0.23%   |
| Silicon Power Computer & Communications | 2         | 0.16%   |
| Qimonda                                 | 2         | 0.16%   |
| fef5                                    | 2         | 0.16%   |
| 2B0B00000000                            | 2         | 0.16%   |
| Vasekey                                 | 1         | 0.08%   |
| Unknown (8AF1)                          | 1         | 0.08%   |
| Unknown (0x0BEC)                        | 1         | 0.08%   |
| Unknown (06CE)                          | 1         | 0.08%   |
| Toshiba                                 | 1         | 0.08%   |
| PKI/Kingston                            | 1         | 0.08%   |
| PKI                                     | 1         | 0.08%   |
| Neo Forza                               | 1         | 0.08%   |
| King Tiger                              | 1         | 0.08%   |
| Goldkey                                 | 1         | 0.08%   |
| Axiom                                   | 1         | 0.08%   |
| Asgard                                  | 1         | 0.08%   |
| ad8a                                    | 1         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s             | 38        | 2.82%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s                     | 36        | 2.67%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 25        | 1.85%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 20        | 1.48%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s               | 16        | 1.19%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 15        | 1.11%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s               | 15        | 1.11%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s              | 13        | 0.96%   |
| Unknown                                                             | 13        | 0.96%   |
| Samsung RAM M471A5143SB1-CRC 4GB SODIMM DDR4 2400MT/s               | 12        | 0.89%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 12        | 0.89%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s              | 11        | 0.82%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 11        | 0.82%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 11        | 0.82%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s               | 11        | 0.82%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 10        | 0.74%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 10        | 0.74%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 10        | 0.74%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s                | 10        | 0.74%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                         | 9         | 0.67%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 9         | 0.67%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 9         | 0.67%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 9         | 0.67%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 9         | 0.67%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 9         | 0.67%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s                | 9         | 0.67%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 8         | 0.59%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 8         | 0.59%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 7         | 0.52%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 7         | 0.52%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 7         | 0.52%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 7         | 0.52%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s              | 7         | 0.52%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 7         | 0.52%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 7         | 0.52%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 7         | 0.52%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 6         | 0.45%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                        | 6         | 0.45%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 6         | 0.45%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                | 6         | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 539       | 49.49%  |
| DDR3    | 269       | 24.7%   |
| LPDDR3  | 65        | 5.97%   |
| LPDDR4  | 63        | 5.79%   |
| LPDDR5  | 47        | 4.32%   |
| DDR5    | 42        | 3.86%   |
| DDR2    | 35        | 3.21%   |
| SDRAM   | 14        | 1.29%   |
| Unknown | 8         | 0.73%   |
| DDR     | 6         | 0.55%   |
| DRAM    | 1         | 0.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 902       | 81.7%   |
| Row Of Chips | 137       | 12.41%  |
| Unknown      | 52        | 4.71%   |
| Chip         | 7         | 0.63%   |
| DIMM         | 6         | 0.54%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 485       | 40.86%  |
| 4096  | 283       | 23.84%  |
| 16384 | 167       | 14.07%  |
| 2048  | 165       | 13.9%   |
| 1024  | 42        | 3.54%   |
| 32768 | 39        | 3.29%   |
| 512   | 3         | 0.25%   |
| 256   | 2         | 0.17%   |
| 1536  | 1         | 0.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 279       | 24.11%  |
| 2667    | 210       | 18.15%  |
| 1600    | 172       | 14.87%  |
| 2400    | 86        | 7.43%   |
| 2133    | 54        | 4.67%   |
| 1867    | 51        | 4.41%   |
| 6400    | 44        | 3.8%    |
| 1334    | 43        | 3.72%   |
| 4800    | 31        | 2.68%   |
| 1333    | 27        | 2.33%   |
| 4267    | 25        | 2.16%   |
| Unknown | 19        | 1.64%   |
| 1067    | 17        | 1.47%   |
| 800     | 17        | 1.47%   |
| 3266    | 11        | 0.95%   |
| 667     | 11        | 0.95%   |
| 5600    | 10        | 0.86%   |
| 4266    | 8         | 0.69%   |
| 4199    | 7         | 0.61%   |
| 1066    | 7         | 0.61%   |
| 975     | 6         | 0.52%   |
| 8400    | 4         | 0.35%   |
| 533     | 4         | 0.35%   |
| 7500    | 3         | 0.26%   |
| 2048    | 3         | 0.26%   |
| 7400    | 1         | 0.09%   |
| 3733    | 1         | 0.09%   |
| 2933    | 1         | 0.09%   |
| 2800    | 1         | 0.09%   |
| 2666    | 1         | 0.09%   |
| 666     | 1         | 0.09%   |
| 400     | 1         | 0.09%   |
| 333     | 1         | 0.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 4         | 40%     |
| Brother Industries    | 3         | 30%     |
| Lexmark International | 1         | 10%     |
| Dymo-CoStar           | 1         | 10%     |
| Canon                 | 1         | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Lexmark International E260dn     | 1         | 9.09%   |
| HP Printing Support              | 1         | 9.09%   |
| HP Officejet 4500 G510g-m        | 1         | 9.09%   |
| HP LaserJet 1018                 | 1         | 9.09%   |
| HP DeskJet 2700 series           | 1         | 9.09%   |
| Dymo-CoStar DYMO XTL             | 1         | 9.09%   |
| Dymo-CoStar DYMO LabelWriter 4XL | 1         | 9.09%   |
| Canon LiDE 400                   | 1         | 9.09%   |
| Brother HL-L2340D series         | 1         | 9.09%   |
| Brother HL-2240D series          | 1         | 9.09%   |
| Brother DCP-7010                 | 1         | 9.09%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Canon       | 2         | 66.67%  |
| Seiko Epson | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X800 [Perfection 4990 PHOTO] | 1         | 33.33%  |
| Canon CanoScan LiDE 210                     | 1         | 33.33%  |
| Canon CanoScan LiDE 110                     | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 305       | 24.36%  |
| Quanta                                 | 132       | 10.54%  |
| IMC Networks                           | 116       | 9.27%   |
| Microdia                               | 92        | 7.35%   |
| Acer                                   | 83        | 6.63%   |
| Realtek Semiconductor                  | 67        | 5.35%   |
| Bison Electronics                      | 65        | 5.19%   |
| Sunplus Innovation Technology          | 57        | 4.55%   |
| Luxvisions Innotech Limited            | 48        | 3.83%   |
| Cheng Uei Precision Industry (Foxlink) | 42        | 3.35%   |
| Lite-On Technology                     | 35        | 2.8%    |
| Apple                                  | 33        | 2.64%   |
| Syntek                                 | 31        | 2.48%   |
| Suyin                                  | 19        | 1.52%   |
| Sonix Technology                       | 19        | 1.52%   |
| Silicon Motion                         | 11        | 0.88%   |
| Logitech                               | 11        | 0.88%   |
| Alcor Micro                            | 9         | 0.72%   |
| Lenovo                                 | 8         | 0.64%   |
| Ricoh                                  | 6         | 0.48%   |
| Z-Star Microelectronics                | 5         | 0.4%    |
| USB Camera                             | 5         | 0.4%    |
| SunplusIT                              | 5         | 0.4%    |
| Microsoft                              | 5         | 0.4%    |
| ShineTech                              | 3         | 0.24%   |
| Samsung Electronics                    | 3         | 0.24%   |
| Primax Electronics                     | 3         | 0.24%   |
| Importek                               | 3         | 0.24%   |
| 8SSC21D67422V1SR3AV5KW1                | 3         | 0.24%   |
| OmniVision Technologies                | 2         | 0.16%   |
| Jieli Technology                       | 2         | 0.16%   |
| BKX-210918                             | 2         | 0.16%   |
| ALi                                    | 2         | 0.16%   |
| Y Media                                | 1         | 0.08%   |
| USB Camera CS                          | 1         | 0.08%   |
| Tenveo                                 | 1         | 0.08%   |
| Sony Electronics                       | 1         | 0.08%   |
| SN0002                                 | 1         | 0.08%   |
| SHENZHEN AONI ELECTRONIC               | 1         | 0.08%   |
| Ruision                                | 1         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 108       | 8.56%   |
| Quanta Chromebook HD Camera                         | 49        | 3.88%   |
| Microdia Integrated_Webcam_HD                       | 45        | 3.57%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 39        | 3.09%   |
| IMC Networks Integrated Camera                      | 38        | 3.01%   |
| Acer BisonCam, NB Pro                               | 37        | 2.93%   |
| Syntek Integrated Camera                            | 25        | 1.98%   |
| Realtek Integrated_Webcam_HD                        | 25        | 1.98%   |
| Chicony HP HD Camera                                | 22        | 1.74%   |
| Bison Integrated Camera                             | 20        | 1.58%   |
| Sunplus Integrated_Webcam_HD                        | 18        | 1.43%   |
| Chicony HD WebCam                                   | 18        | 1.43%   |
| Quanta HD User Facing                               | 16        | 1.27%   |
| Chicony HD User Facing                              | 16        | 1.27%   |
| Acer Integrated Camera                              | 16        | 1.27%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 14        | 1.11%   |
| Lite-On Integrated Camera                           | 13        | 1.03%   |
| Acer SunplusIT Integrated Camera                    | 13        | 1.03%   |
| Sonix USB2.0 HD UVC WebCam                          | 12        | 0.95%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 12        | 0.95%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 12        | 0.95%   |
| Quanta HP TrueVision HD Camera                      | 11        | 0.87%   |
| Lite-On HP HD Camera                                | 10        | 0.79%   |
| Chicony USB2.0 Camera                               | 10        | 0.79%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 10        | 0.79%   |
| Realtek USB Camera                                  | 9         | 0.71%   |
| Quanta ACER HD User Facing                          | 9         | 0.71%   |
| Chicony Integrated Camera (1280x720@30)             | 9         | 0.71%   |
| Chicony HP Wide Vision HD Camera                    | 9         | 0.71%   |
| Quanta ov9734_techfront_camera                      | 8         | 0.63%   |
| Quanta HP Wide Vision HD Camera                     | 8         | 0.63%   |
| Chicony HP Truevision HD                            | 8         | 0.63%   |
| Apple Built-in iSight                               | 8         | 0.63%   |
| Acer Integrated RGB Camera                          | 8         | 0.63%   |
| Quanta HP HD Camera                                 | 7         | 0.55%   |
| Luxvisions Innotech Limited HP HD Camera            | 7         | 0.55%   |
| Apple FaceTime HD Camera                            | 7         | 0.55%   |
| Realtek Integrated Webcam                           | 6         | 0.48%   |
| Microdia USB 2.0 Camera                             | 6         | 0.48%   |
| Microdia Integrated_Webcam_FHD                      | 6         | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 84        | 34.01%  |
| Validity Sensors                   | 76        | 30.77%  |
| Shenzhen Goodix Technology         | 32        | 12.96%  |
| Elan Microelectronics              | 15        | 6.07%   |
| Upek                               | 12        | 4.86%   |
| AuthenTec                          | 11        | 4.45%   |
| LighTuning Technology              | 6         | 2.43%   |
| STMicroelectronics                 | 4         | 1.62%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 1.21%   |
| DigitalPersona                     | 2         | 0.81%   |
| HOLTEK                             | 1         | 0.4%    |
| Focal-systems.Corp                 | 1         | 0.4%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 32        | 12.96%  |
| Shenzhen Goodix  Fingerprint Device                                        | 25        | 10.12%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 22        | 8.91%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 19        | 7.69%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 14        | 5.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 11        | 4.45%   |
| Synaptics UWP WBDI Device                                                  | 10        | 4.05%   |
| Elan ELAN:ARM-M4                                                           | 10        | 4.05%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 9         | 3.64%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 3.64%   |
| Validity Sensors VFS491                                                    | 6         | 2.43%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 6         | 2.43%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 5         | 2.02%   |
| Elan ELAN:Fingerprint                                                      | 5         | 2.02%   |
| AuthenTec AES2810                                                          | 5         | 2.02%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 1.62%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 1.62%   |
| STMicroelectronics Fingerprint Reader                                      | 4         | 1.62%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 1.62%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 1.62%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.21%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 1.21%   |
| Synaptics Fingerprint reader [HP G6]                                       | 3         | 1.21%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 1.21%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 1.21%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 1.21%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 0.81%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.81%   |
| DigitalPersona Fingerprint Reader                                          | 2         | 0.81%   |
| Unknown                                                                    | 2         | 0.81%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.4%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.4%    |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.4%    |
| Synaptics WBDI Device                                                      | 1         | 0.4%    |
| Synaptics UWP WBDI                                                         | 1         | 0.4%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.4%    |
| LighTuning Fingerprint Reader                                              | 1         | 0.4%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.4%    |
| HOLTEK FocalTech Fingerprint Device                                        | 1         | 0.4%    |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 1         | 0.4%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 47        | 45.19%  |
| Broadcom              | 40        | 38.46%  |
| Upek                  | 5         | 4.81%   |
| Lenovo                | 5         | 4.81%   |
| Yubico.com            | 3         | 2.88%   |
| O2 Micro              | 3         | 2.88%   |
| Gemalto (was Gemplus) | 1         | 0.96%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 46        | 44.23%  |
| Broadcom 58200                                                               | 14        | 13.46%  |
| Broadcom 5880                                                                | 11        | 10.58%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 7.69%   |
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 6.73%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 4.81%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 4.81%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.92%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 1.92%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 0.96%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.96%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.96%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.96%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 755       | 53.89%  |
| 1     | 514       | 36.69%  |
| 2     | 111       | 7.92%   |
| 3     | 16        | 1.14%   |
| 4     | 4         | 0.29%   |
| 5     | 1         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 244       | 31.61%  |
| Graphics card            | 210       | 27.2%   |
| Chipcard                 | 92        | 11.92%  |
| Camera                   | 67        | 8.68%   |
| Multimedia controller    | 54        | 6.99%   |
| Net/wireless             | 51        | 6.61%   |
| Card reader              | 11        | 1.42%   |
| Bluetooth                | 11        | 1.42%   |
| Modem                    | 8         | 1.04%   |
| Storage                  | 7         | 0.91%   |
| Sound                    | 5         | 0.65%   |
| Communication controller | 4         | 0.52%   |
| Wireless                 | 3         | 0.39%   |
| Network                  | 2         | 0.26%   |
| Unassigned class         | 1         | 0.13%   |
| Net/ethernet             | 1         | 0.13%   |
| Flash memory             | 1         | 0.13%   |


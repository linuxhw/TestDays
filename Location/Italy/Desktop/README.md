Linux in Italy - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------

A project to collect tested hardware configurations for Linux in Italy.

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

Total: 4291

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME H610M-E D4            | [8985b86479](https://linux-hardware.org/?probe=8985b86479) | Oct 01, 2023 |
| MSI           | B450-A PRO MAX              | [6ee0910511](https://linux-hardware.org/?probe=6ee0910511) | Sep 30, 2023 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [c93af00811](https://linux-hardware.org/?probe=c93af00811) | Sep 30, 2023 |
| ASUSTek       | CG8480                      | [dc174e8f73](https://linux-hardware.org/?probe=dc174e8f73) | Sep 30, 2023 |
| MSI           | P67A-C43                    | [22492f6d47](https://linux-hardware.org/?probe=22492f6d47) | Sep 30, 2023 |
| ASRock        | 4Core1600-GLAN              | [aefbc14017](https://linux-hardware.org/?probe=aefbc14017) | Sep 30, 2023 |
| Acer          | Nitro N50-610               | [a91f602e4a](https://linux-hardware.org/?probe=a91f602e4a) | Sep 29, 2023 |
| GEEKOM        | Mini IT 8                   | [fc5d6092da](https://linux-hardware.org/?probe=fc5d6092da) | Sep 29, 2023 |
| MSI           | A320M-A PRO MAX             | [4aa521a31f](https://linux-hardware.org/?probe=4aa521a31f) | Sep 29, 2023 |
| ASUSTek       | H81M-E                      | [0137140cae](https://linux-hardware.org/?probe=0137140cae) | Sep 28, 2023 |
| ASUSTek       | PRIME B450M-A               | [6bce0e41d9](https://linux-hardware.org/?probe=6bce0e41d9) | Sep 28, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [8f35ffb248](https://linux-hardware.org/?probe=8f35ffb248) | Sep 28, 2023 |
| MSI           | H310M PRO-VD                | [67e14c1b2d](https://linux-hardware.org/?probe=67e14c1b2d) | Sep 28, 2023 |
| HP            | 0AA8h                       | [7c8c8fbb40](https://linux-hardware.org/?probe=7c8c8fbb40) | Sep 28, 2023 |
| HP            | 843C                        | [4af4a9e798](https://linux-hardware.org/?probe=4af4a9e798) | Sep 28, 2023 |
| Intel         | H61                         | [f41171114f](https://linux-hardware.org/?probe=f41171114f) | Sep 28, 2023 |
| MSI           | MPG Z490M GAMING EDGE WI... | [23150c5bd3](https://linux-hardware.org/?probe=23150c5bd3) | Sep 27, 2023 |
| Unknown       | Unknown                     | [2bf5f64c14](https://linux-hardware.org/?probe=2bf5f64c14) | Sep 27, 2023 |
| MSI           | A320M-A PRO MAX             | [f6c6bfc3fe](https://linux-hardware.org/?probe=f6c6bfc3fe) | Sep 27, 2023 |
| Gigabyte      | B450M DS3H-CF               | [812b06784e](https://linux-hardware.org/?probe=812b06784e) | Sep 27, 2023 |
| YANYU         | H17SL                       | [5966ae64d0](https://linux-hardware.org/?probe=5966ae64d0) | Sep 26, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [0a5cc18946](https://linux-hardware.org/?probe=0a5cc18946) | Sep 26, 2023 |
| ASUSTek       | M5A97 R2.0                  | [275018a17e](https://linux-hardware.org/?probe=275018a17e) | Sep 26, 2023 |
| Foxconn       | 2ABF                        | [2be1547618](https://linux-hardware.org/?probe=2be1547618) | Sep 26, 2023 |
| ASUSTek       | P9D WS                      | [fd2133400d](https://linux-hardware.org/?probe=fd2133400d) | Sep 25, 2023 |
| MSI           | MPG Z490M GAMING EDGE WI... | [a6ef2b5028](https://linux-hardware.org/?probe=a6ef2b5028) | Sep 25, 2023 |
| Dell          | 0200DY A02                  | [0ecd2d60b4](https://linux-hardware.org/?probe=0ecd2d60b4) | Sep 25, 2023 |
| Dell          | 0773VG A02                  | [83390c3986](https://linux-hardware.org/?probe=83390c3986) | Sep 25, 2023 |
| Acer          | H11H4-AI V:1.0              | [971f03180e](https://linux-hardware.org/?probe=971f03180e) | Sep 24, 2023 |
| ASUSTek       | H81M-E                      | [6d3f4579cd](https://linux-hardware.org/?probe=6d3f4579cd) | Sep 24, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [c80ba0c0f7](https://linux-hardware.org/?probe=c80ba0c0f7) | Sep 24, 2023 |
| Foxconn       | H67MP-S/-V/H67MP            | [67b0050938](https://linux-hardware.org/?probe=67b0050938) | Sep 24, 2023 |
| HP            | 18E7                        | [6257920a37](https://linux-hardware.org/?probe=6257920a37) | Sep 24, 2023 |
| Dell          | 0WR7PY A01                  | [64e4102978](https://linux-hardware.org/?probe=64e4102978) | Sep 23, 2023 |
| Shuttle       | XS36V                       | [dbcb5658e4](https://linux-hardware.org/?probe=dbcb5658e4) | Sep 23, 2023 |
| ASUSTek       | PRIME Z370-P                | [fb3ade25c0](https://linux-hardware.org/?probe=fb3ade25c0) | Sep 22, 2023 |
| MSI           | Boston                      | [a9fe9241ec](https://linux-hardware.org/?probe=a9fe9241ec) | Sep 21, 2023 |
| MSI           | A88XM-E45                   | [99b5c7c976](https://linux-hardware.org/?probe=99b5c7c976) | Sep 21, 2023 |
| ASRock        | H310M-HDV                   | [0ac59e2ff6](https://linux-hardware.org/?probe=0ac59e2ff6) | Sep 21, 2023 |
| HP            | 2ADC                        | [b4794f247b](https://linux-hardware.org/?probe=b4794f247b) | Sep 21, 2023 |
| HP            | 2ADC                        | [7e9eb06b31](https://linux-hardware.org/?probe=7e9eb06b31) | Sep 21, 2023 |
| Gigabyte      | B450M DS3H-CF               | [f65b051dc9](https://linux-hardware.org/?probe=f65b051dc9) | Sep 20, 2023 |
| Acer          | EG43M                       | [77e78183b9](https://linux-hardware.org/?probe=77e78183b9) | Sep 20, 2023 |
| Huanan        | X99-F8 V2.0                 | [f832424d90](https://linux-hardware.org/?probe=f832424d90) | Sep 19, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [7273c8eb2e](https://linux-hardware.org/?probe=7273c8eb2e) | Sep 19, 2023 |
| ASRock        | B450 Steel Legend           | [b294855348](https://linux-hardware.org/?probe=b294855348) | Sep 19, 2023 |
| ASUSTek       | PRIME B365M-A               | [8922ced8ec](https://linux-hardware.org/?probe=8922ced8ec) | Sep 18, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [9a7a68b69f](https://linux-hardware.org/?probe=9a7a68b69f) | Sep 18, 2023 |
| Dell          | 0PTTT9 A01                  | [35248efbaf](https://linux-hardware.org/?probe=35248efbaf) | Sep 18, 2023 |
| Unknown       | Unknown                     | [faa59f7ab3](https://linux-hardware.org/?probe=faa59f7ab3) | Sep 18, 2023 |
| MSI           | MPG Z590 GAMING FORCE       | [0ac4289831](https://linux-hardware.org/?probe=0ac4289831) | Sep 18, 2023 |
| HC Technol... | HCAR5000-MI                 | [eb9e6551ac](https://linux-hardware.org/?probe=eb9e6551ac) | Sep 17, 2023 |
| HC Technol... | HCAR5000-MI                 | [f3a4ce70fb](https://linux-hardware.org/?probe=f3a4ce70fb) | Sep 17, 2023 |
| ASUSTek       | CM1740                      | [96b9168216](https://linux-hardware.org/?probe=96b9168216) | Sep 16, 2023 |
| ASUSTek       | ROG Maximus Z790 APEX       | [76d354fede](https://linux-hardware.org/?probe=76d354fede) | Sep 16, 2023 |
| ASUSTek       | ROG Maximus Z790 APEX       | [ae35c7426c](https://linux-hardware.org/?probe=ae35c7426c) | Sep 16, 2023 |
| Gigabyte      | B450M DS3H-CF               | [27d7589428](https://linux-hardware.org/?probe=27d7589428) | Sep 15, 2023 |
| Foxconn       | H67MP-S/-V/H67MP            | [9df835f343](https://linux-hardware.org/?probe=9df835f343) | Sep 14, 2023 |
| ASUSTek       | P8Z77-V LX                  | [103e7031fe](https://linux-hardware.org/?probe=103e7031fe) | Sep 14, 2023 |
| Intel         | DH67CL AAG10212-210         | [21932b1004](https://linux-hardware.org/?probe=21932b1004) | Sep 14, 2023 |
| ASUSTek       | P8P67-M PRO                 | [799a135aca](https://linux-hardware.org/?probe=799a135aca) | Sep 14, 2023 |
| Unknown       | Unknown                     | [be3cf24114](https://linux-hardware.org/?probe=be3cf24114) | Sep 13, 2023 |
| ASUSTek       | P8Z77-V LX                  | [7cea54ec70](https://linux-hardware.org/?probe=7cea54ec70) | Sep 13, 2023 |
| Intel         | X79                         | [e9a4f4dc51](https://linux-hardware.org/?probe=e9a4f4dc51) | Sep 13, 2023 |
| ASRock        | H97 Anniversary             | [37014ea895](https://linux-hardware.org/?probe=37014ea895) | Sep 13, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | [4dcd4e8234](https://linux-hardware.org/?probe=4dcd4e8234) | Sep 13, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | [cbfa4c2641](https://linux-hardware.org/?probe=cbfa4c2641) | Sep 13, 2023 |
| ASUSTek       | P8H61-M LX2 R2.0            | [8b55f7f82a](https://linux-hardware.org/?probe=8b55f7f82a) | Sep 13, 2023 |
| ASRock        | H410M-HVS                   | [483bbfcc92](https://linux-hardware.org/?probe=483bbfcc92) | Sep 13, 2023 |
| AZW           | MINI S 10                   | [5cd0efea8b](https://linux-hardware.org/?probe=5cd0efea8b) | Sep 12, 2023 |
| Dell          | 0G254H A00                  | [b41d69b7e2](https://linux-hardware.org/?probe=b41d69b7e2) | Sep 12, 2023 |
| HP            | 18E7                        | [a553a173be](https://linux-hardware.org/?probe=a553a173be) | Sep 11, 2023 |
| Cincoze       | DX-1000.01.001              | [561f581c95](https://linux-hardware.org/?probe=561f581c95) | Sep 11, 2023 |
| ASUSTek       | H110M-A/M.2                 | [e186172ee4](https://linux-hardware.org/?probe=e186172ee4) | Sep 10, 2023 |
| Acer          | Veriton M2631 V:1.0         | [ec947814d1](https://linux-hardware.org/?probe=ec947814d1) | Sep 10, 2023 |
| MSI           | B450M GAMING PLUS           | [5bf280924d](https://linux-hardware.org/?probe=5bf280924d) | Sep 09, 2023 |
| ASUSTek       | P8B75-M                     | [d64063efa5](https://linux-hardware.org/?probe=d64063efa5) | Sep 09, 2023 |
| MSI           | Boston                      | [865959d898](https://linux-hardware.org/?probe=865959d898) | Sep 08, 2023 |
| ASUSTek       | P8P67-M PRO                 | [6ec67cd2f1](https://linux-hardware.org/?probe=6ec67cd2f1) | Sep 08, 2023 |
| Acer          | Veriton M2632G V:1.0        | [a0363f72e3](https://linux-hardware.org/?probe=a0363f72e3) | Sep 08, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [c06ee9858a](https://linux-hardware.org/?probe=c06ee9858a) | Sep 08, 2023 |
| ASUSTek       | P5K-VM                      | [9b8cb6e3f6](https://linux-hardware.org/?probe=9b8cb6e3f6) | Sep 07, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [36a4c33de8](https://linux-hardware.org/?probe=36a4c33de8) | Sep 07, 2023 |
| Unknown       | Unknown                     | [b0fccd6eb5](https://linux-hardware.org/?probe=b0fccd6eb5) | Sep 07, 2023 |
| ASRock        | 775Dual-VSTA                | [05af667eb0](https://linux-hardware.org/?probe=05af667eb0) | Sep 07, 2023 |
| ASUSTek       | SABERTOOTH P67              | [002bdcd34d](https://linux-hardware.org/?probe=002bdcd34d) | Sep 07, 2023 |
| ASRock        | Z97M OC Formula             | [1f2c20e8cf](https://linux-hardware.org/?probe=1f2c20e8cf) | Sep 06, 2023 |
| Unknown       | Unknown                     | [7fd153d869](https://linux-hardware.org/?probe=7fd153d869) | Sep 06, 2023 |
| Unknown       | Unknown                     | [6508e8eeb8](https://linux-hardware.org/?probe=6508e8eeb8) | Sep 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [c404211007](https://linux-hardware.org/?probe=c404211007) | Sep 05, 2023 |
| Dell          | 0PTTT9 A01                  | [2c7accd18e](https://linux-hardware.org/?probe=2c7accd18e) | Sep 05, 2023 |
| ASRock        | 970 Extreme4                | [4196acbe15](https://linux-hardware.org/?probe=4196acbe15) | Sep 05, 2023 |
| MSI           | Boston                      | [5e1b8aa70b](https://linux-hardware.org/?probe=5e1b8aa70b) | Sep 04, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | [a9321ea88e](https://linux-hardware.org/?probe=a9321ea88e) | Sep 04, 2023 |
| MSI           | Boston                      | [5ad763345c](https://linux-hardware.org/?probe=5ad763345c) | Sep 04, 2023 |
| Intel         | DG41RQ AAE54511-203         | [46aeab1365](https://linux-hardware.org/?probe=46aeab1365) | Sep 04, 2023 |
| Dell          | 0773VG A00                  | [426a2f4142](https://linux-hardware.org/?probe=426a2f4142) | Sep 04, 2023 |
| AZW           | MINI S 10                   | [54967a6b36](https://linux-hardware.org/?probe=54967a6b36) | Sep 04, 2023 |
| ASRock        | Z790 Taichi Carrara         | [80f9f3915b](https://linux-hardware.org/?probe=80f9f3915b) | Sep 04, 2023 |
| HP            | 1825                        | [ea5da3d446](https://linux-hardware.org/?probe=ea5da3d446) | Sep 03, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [5590e2e8d6](https://linux-hardware.org/?probe=5590e2e8d6) | Sep 02, 2023 |
| Shenzhen M... | F6BFC                       | [4b8aead223](https://linux-hardware.org/?probe=4b8aead223) | Sep 01, 2023 |
| Intel         | DP67DE AAG10217-300         | [4d0db0b964](https://linux-hardware.org/?probe=4d0db0b964) | Sep 01, 2023 |
| HP            | 89B5 A                      | [3b6a46c308](https://linux-hardware.org/?probe=3b6a46c308) | Sep 01, 2023 |
| Gigabyte      | B450M DS3H-CF               | [7940f23184](https://linux-hardware.org/?probe=7940f23184) | Sep 01, 2023 |
| HP            | 1632                        | [a36b07aeda](https://linux-hardware.org/?probe=a36b07aeda) | Sep 01, 2023 |
| ASUSTek       | P5Q SE                      | [288078e39e](https://linux-hardware.org/?probe=288078e39e) | Sep 01, 2023 |
| Intel         | X79M-S                      | [a6952c68e4](https://linux-hardware.org/?probe=a6952c68e4) | Sep 01, 2023 |
| Gigabyte      | M5NM1AI-GB                  | [2b2efe00dd](https://linux-hardware.org/?probe=2b2efe00dd) | Sep 01, 2023 |
| HP            | 1632                        | [13de11f1ff](https://linux-hardware.org/?probe=13de11f1ff) | Sep 01, 2023 |
| ASUSTek       | M4A87TD EVO                 | [32a123fc5d](https://linux-hardware.org/?probe=32a123fc5d) | Aug 31, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [578f5e581e](https://linux-hardware.org/?probe=578f5e581e) | Aug 31, 2023 |
| MSI           | A88X-G41 PC Mate            | [13724b9cc2](https://linux-hardware.org/?probe=13724b9cc2) | Aug 31, 2023 |
| MSI           | A320M PRO-E                 | [92c4032614](https://linux-hardware.org/?probe=92c4032614) | Aug 31, 2023 |
| ASRock        | Q1900B-ITX                  | [875427cd72](https://linux-hardware.org/?probe=875427cd72) | Aug 31, 2023 |
| ASUSTek       | P8B75-M                     | [4f8c86072b](https://linux-hardware.org/?probe=4f8c86072b) | Aug 31, 2023 |
| Gigabyte      | X570S AERO G                | [f367356391](https://linux-hardware.org/?probe=f367356391) | Aug 30, 2023 |
| HP            | 82B4                        | [28155e6336](https://linux-hardware.org/?probe=28155e6336) | Aug 30, 2023 |
| ASUSTek       | A8N32-SLI-Deluxe            | [26c288c533](https://linux-hardware.org/?probe=26c288c533) | Aug 30, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [f040a85f2f](https://linux-hardware.org/?probe=f040a85f2f) | Aug 30, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [1fd98a124f](https://linux-hardware.org/?probe=1fd98a124f) | Aug 29, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [7674d12aa5](https://linux-hardware.org/?probe=7674d12aa5) | Aug 28, 2023 |
| HP            | 21D0                        | [8978dfd3bf](https://linux-hardware.org/?probe=8978dfd3bf) | Aug 28, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [17136ed242](https://linux-hardware.org/?probe=17136ed242) | Aug 28, 2023 |
| Gigabyte      | H410M S2H V3                | [c772f3df30](https://linux-hardware.org/?probe=c772f3df30) | Aug 28, 2023 |
| ASUSTek       | PRIME B450M-A               | [b4411a9169](https://linux-hardware.org/?probe=b4411a9169) | Aug 27, 2023 |
| ASRock        | Z490M-ITX/ac                | [d3a4f92f62](https://linux-hardware.org/?probe=d3a4f92f62) | Aug 27, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [b7020427e0](https://linux-hardware.org/?probe=b7020427e0) | Aug 27, 2023 |
| ASUSTek       | PRIME X370-PRO              | [95d23ba555](https://linux-hardware.org/?probe=95d23ba555) | Aug 27, 2023 |
| MSI           | H310M PRO-VD PLUS           | [2a25ad0be2](https://linux-hardware.org/?probe=2a25ad0be2) | Aug 27, 2023 |
| ASUSTek       | H110M-K                     | [9cf3912874](https://linux-hardware.org/?probe=9cf3912874) | Aug 26, 2023 |
| ASRock        | 775Dual-VSTA                | [8d36dd0fbb](https://linux-hardware.org/?probe=8d36dd0fbb) | Aug 25, 2023 |
| HP            | 21F5 0A                     | [812718f3e7](https://linux-hardware.org/?probe=812718f3e7) | Aug 25, 2023 |
| Pegatron      | EVANS                       | [1b32c5d271](https://linux-hardware.org/?probe=1b32c5d271) | Aug 24, 2023 |
| Lenovo        | 3141 SDK0J40697 WIN 3305... | [088ba21947](https://linux-hardware.org/?probe=088ba21947) | Aug 24, 2023 |
| MSI           | MAG Z390M MORTAR            | [91de6baf4d](https://linux-hardware.org/?probe=91de6baf4d) | Aug 24, 2023 |
| Pegatron      | 2AD5                        | [fcb0ac31fe](https://linux-hardware.org/?probe=fcb0ac31fe) | Aug 23, 2023 |
| Acer          | Predator G3610              | [04153b05c7](https://linux-hardware.org/?probe=04153b05c7) | Aug 22, 2023 |
| ASUSTek       | PRIME B550M-A               | [df5037fab5](https://linux-hardware.org/?probe=df5037fab5) | Aug 22, 2023 |
| Acer          | Predator PO3-630            | [b7c9c3e0c4](https://linux-hardware.org/?probe=b7c9c3e0c4) | Aug 22, 2023 |
| HP            | 3048h                       | [959637abde](https://linux-hardware.org/?probe=959637abde) | Aug 21, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | [49289df595](https://linux-hardware.org/?probe=49289df595) | Aug 20, 2023 |
| HP            | 2B52                        | [ed7526d18f](https://linux-hardware.org/?probe=ed7526d18f) | Aug 20, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [04efd4ddec](https://linux-hardware.org/?probe=04efd4ddec) | Aug 20, 2023 |
| ASRock        | 970 Extreme4                | [4cec633c85](https://linux-hardware.org/?probe=4cec633c85) | Aug 20, 2023 |
| ASUSTek       | CM6870                      | [05507d2151](https://linux-hardware.org/?probe=05507d2151) | Aug 20, 2023 |
| ASUSTek       | CM6870                      | [b91ffcb2be](https://linux-hardware.org/?probe=b91ffcb2be) | Aug 20, 2023 |
| Gigabyte      | B75M-D2V                    | [8c805fa379](https://linux-hardware.org/?probe=8c805fa379) | Aug 20, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [825225e1c4](https://linux-hardware.org/?probe=825225e1c4) | Aug 19, 2023 |
| Dell          | 0P03DX A04                  | [be211c5305](https://linux-hardware.org/?probe=be211c5305) | Aug 18, 2023 |
| Intel         | X79M-S                      | [d79895d82c](https://linux-hardware.org/?probe=d79895d82c) | Aug 17, 2023 |
| MSI           | Z87 MPOWER MAX              | [6bda9908df](https://linux-hardware.org/?probe=6bda9908df) | Aug 16, 2023 |
| MSI           | Z170A GAMING M9 ACK         | [1ff9bff198](https://linux-hardware.org/?probe=1ff9bff198) | Aug 15, 2023 |
| Pegatron      | Benicia                     | [0ab394fa9e](https://linux-hardware.org/?probe=0ab394fa9e) | Aug 15, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [780b9a9e3a](https://linux-hardware.org/?probe=780b9a9e3a) | Aug 15, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [bf753b0310](https://linux-hardware.org/?probe=bf753b0310) | Aug 14, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [0be611b499](https://linux-hardware.org/?probe=0be611b499) | Aug 14, 2023 |
| ASUSTek       | PRO B460M-C                 | [a4a49de960](https://linux-hardware.org/?probe=a4a49de960) | Aug 13, 2023 |
| HP            | 8055                        | [a4c4208546](https://linux-hardware.org/?probe=a4c4208546) | Aug 13, 2023 |
| HP            | 3031h                       | [2f9084013a](https://linux-hardware.org/?probe=2f9084013a) | Aug 13, 2023 |
| Gigabyte      | B450M DS3H-CF               | [b232e62577](https://linux-hardware.org/?probe=b232e62577) | Aug 13, 2023 |
| ASUSTek       | PRIME A520M-E               | [92f4e14369](https://linux-hardware.org/?probe=92f4e14369) | Aug 11, 2023 |
| MSI           | Boston                      | [62ad275a7d](https://linux-hardware.org/?probe=62ad275a7d) | Aug 11, 2023 |
| MSI           | Boston                      | [a34a89c083](https://linux-hardware.org/?probe=a34a89c083) | Aug 11, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | [d4b93affe2](https://linux-hardware.org/?probe=d4b93affe2) | Aug 11, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | [7a8e32eb89](https://linux-hardware.org/?probe=7a8e32eb89) | Aug 11, 2023 |
| Gigabyte      | B250-HD3P-CF                | [b347883be2](https://linux-hardware.org/?probe=b347883be2) | Aug 11, 2023 |
| Fujitsu Si... | G31T-M2 V3.02               | [1c32da7aed](https://linux-hardware.org/?probe=1c32da7aed) | Aug 10, 2023 |
| Dell          | 0JP3NX A01                  | [a9c4812d66](https://linux-hardware.org/?probe=a9c4812d66) | Aug 09, 2023 |
| ASUSTek       | M5A97 PLUS                  | [0c755e3349](https://linux-hardware.org/?probe=0c755e3349) | Aug 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6abad99081](https://linux-hardware.org/?probe=6abad99081) | Aug 08, 2023 |
| Intel         | X79M-S                      | [8250cad3d6](https://linux-hardware.org/?probe=8250cad3d6) | Aug 08, 2023 |
| Gigabyte      | Z370P D3-CF                 | [ed5ccc8efb](https://linux-hardware.org/?probe=ed5ccc8efb) | Aug 08, 2023 |
| MSI           | Z170A GAMING M9 ACK         | [8839aa58c4](https://linux-hardware.org/?probe=8839aa58c4) | Aug 08, 2023 |
| AZW           | U59                         | [d7b7b7641b](https://linux-hardware.org/?probe=d7b7b7641b) | Aug 07, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [31c3da5150](https://linux-hardware.org/?probe=31c3da5150) | Aug 07, 2023 |
| ASUSTek       | P5GDC                       | [82fefe395d](https://linux-hardware.org/?probe=82fefe395d) | Aug 06, 2023 |
| MSI           | PRO H610M-B DDR4            | [1b3c788790](https://linux-hardware.org/?probe=1b3c788790) | Aug 06, 2023 |
| Pegatron      | IPMMB-MQ1                   | [70c450c395](https://linux-hardware.org/?probe=70c450c395) | Aug 06, 2023 |
| ASUSTek       | Z97-K                       | [5ca4ca286b](https://linux-hardware.org/?probe=5ca4ca286b) | Aug 05, 2023 |
| Acer          | Veriton M2632G V:1.0        | [b66051af86](https://linux-hardware.org/?probe=b66051af86) | Aug 04, 2023 |
| Pegatron      | 2A94h                       | [9d5490fb82](https://linux-hardware.org/?probe=9d5490fb82) | Aug 04, 2023 |
| ASUSTek       | H81M-K                      | [d946977ec8](https://linux-hardware.org/?probe=d946977ec8) | Aug 04, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [e0b5eb8809](https://linux-hardware.org/?probe=e0b5eb8809) | Aug 04, 2023 |
| MSI           | PRO Z790-P WIFI             | [8f3eaca764](https://linux-hardware.org/?probe=8f3eaca764) | Aug 03, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [986cf08dc9](https://linux-hardware.org/?probe=986cf08dc9) | Aug 03, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [da8d764a97](https://linux-hardware.org/?probe=da8d764a97) | Aug 03, 2023 |
| Intel         | X79M-S                      | [5a4d94f325](https://linux-hardware.org/?probe=5a4d94f325) | Aug 02, 2023 |
| ASRock        | Z170 Gaming K4              | [2c10cb0378](https://linux-hardware.org/?probe=2c10cb0378) | Aug 02, 2023 |
| ASRock        | 775Dual-VSTA                | [7241233996](https://linux-hardware.org/?probe=7241233996) | Aug 02, 2023 |
| ASRock        | B365M-HDV                   | [994853ef26](https://linux-hardware.org/?probe=994853ef26) | Aug 01, 2023 |
| Intel         | X79                         | [051316466a](https://linux-hardware.org/?probe=051316466a) | Aug 01, 2023 |
| ASUSTek       | Z87-A                       | [603bee8812](https://linux-hardware.org/?probe=603bee8812) | Aug 01, 2023 |
| ASUSTek       | Z87-A                       | [64bc1caf41](https://linux-hardware.org/?probe=64bc1caf41) | Aug 01, 2023 |
| MSI           | PRO Z690-A                  | [19f4cb0c69](https://linux-hardware.org/?probe=19f4cb0c69) | Jul 31, 2023 |
| Gigabyte      | B85M-D3H                    | [9ddb5c2ea3](https://linux-hardware.org/?probe=9ddb5c2ea3) | Jul 31, 2023 |
| ASUSTek       | Z170-PRO                    | [ac4682042f](https://linux-hardware.org/?probe=ac4682042f) | Jul 30, 2023 |
| Gigabyte      | GA-MA78GM-S2H               | [37e282ff80](https://linux-hardware.org/?probe=37e282ff80) | Jul 30, 2023 |
| HP            | 3048h                       | [cd83e4a73a](https://linux-hardware.org/?probe=cd83e4a73a) | Jul 29, 2023 |
| HP            | 3048h                       | [56918c8bad](https://linux-hardware.org/?probe=56918c8bad) | Jul 29, 2023 |
| ASRock        | A620M-HDV/M.2+              | [ea91ff9db6](https://linux-hardware.org/?probe=ea91ff9db6) | Jul 28, 2023 |
| MSI           | PRO Z690-A                  | [f1a5d69727](https://linux-hardware.org/?probe=f1a5d69727) | Jul 28, 2023 |
| MSI           | MS-B1831                    | [35f0e625f1](https://linux-hardware.org/?probe=35f0e625f1) | Jul 27, 2023 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | [d32fa8840b](https://linux-hardware.org/?probe=d32fa8840b) | Jul 27, 2023 |
| ASUSTek       | LEUCITE3                    | [bb2046286f](https://linux-hardware.org/?probe=bb2046286f) | Jul 26, 2023 |
| ASUSTek       | LEUCITE3                    | [6ced09890f](https://linux-hardware.org/?probe=6ced09890f) | Jul 26, 2023 |
| ASUSTek       | P6X58D PREMIUM              | [0a84eeb8e2](https://linux-hardware.org/?probe=0a84eeb8e2) | Jul 26, 2023 |
| Phoenix Co... | PSB514 A11                  | [9791c84b0d](https://linux-hardware.org/?probe=9791c84b0d) | Jul 25, 2023 |
| Phoenix Co... | PSB514 A11                  | [8e271c334d](https://linux-hardware.org/?probe=8e271c334d) | Jul 24, 2023 |
| Intel         | X79                         | [8037a9fc0e](https://linux-hardware.org/?probe=8037a9fc0e) | Jul 24, 2023 |
| MSI           | B450M-A PRO MAX             | [5d16b13584](https://linux-hardware.org/?probe=5d16b13584) | Jul 24, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [ae4343c245](https://linux-hardware.org/?probe=ae4343c245) | Jul 23, 2023 |
| Gigabyte      | B550M DS3H                  | [04982390e0](https://linux-hardware.org/?probe=04982390e0) | Jul 23, 2023 |
| Gigabyte      | B550M DS3H                  | [b13bb2310f](https://linux-hardware.org/?probe=b13bb2310f) | Jul 23, 2023 |
| ASUSTek       | CG8480                      | [2b839ca54f](https://linux-hardware.org/?probe=2b839ca54f) | Jul 23, 2023 |
| ASRock        | B250M Pro4                  | [9ce9a989dd](https://linux-hardware.org/?probe=9ce9a989dd) | Jul 23, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [0e830a2330](https://linux-hardware.org/?probe=0e830a2330) | Jul 23, 2023 |
| ASRock        | B250M Pro4                  | [23d73ededd](https://linux-hardware.org/?probe=23d73ededd) | Jul 23, 2023 |
| MSI           | B450 TOMAHAWK               | [bda4392623](https://linux-hardware.org/?probe=bda4392623) | Jul 22, 2023 |
| ASUSTek       | ROG STRIX Z790-I GAMING ... | [625e829a7e](https://linux-hardware.org/?probe=625e829a7e) | Jul 22, 2023 |
| ASUSTek       | PRIME Z590-P                | [02903e0210](https://linux-hardware.org/?probe=02903e0210) | Jul 22, 2023 |
| ASRock        | 960GC-GS FX                 | [187cbf1010](https://linux-hardware.org/?probe=187cbf1010) | Jul 21, 2023 |
| Acer          | MCP7A                       | [06afe36113](https://linux-hardware.org/?probe=06afe36113) | Jul 18, 2023 |
| Dell          | 0WMJ54 A01                  | [032a11c2a5](https://linux-hardware.org/?probe=032a11c2a5) | Jul 18, 2023 |
| HP            | 18E7                        | [bddd22fb18](https://linux-hardware.org/?probe=bddd22fb18) | Jul 18, 2023 |
| AMI           | Intel                       | [fb562a8b94](https://linux-hardware.org/?probe=fb562a8b94) | Jul 18, 2023 |
| AMI           | Intel                       | [52cb51f3c6](https://linux-hardware.org/?probe=52cb51f3c6) | Jul 18, 2023 |
| MSI           | B450M-A PRO MAX             | [4c8b8b5a8a](https://linux-hardware.org/?probe=4c8b8b5a8a) | Jul 18, 2023 |
| HP            | 3048h                       | [ad7b0d8c8d](https://linux-hardware.org/?probe=ad7b0d8c8d) | Jul 17, 2023 |
| MSI           | PRO B650-P WIFI             | [65afe9f74b](https://linux-hardware.org/?probe=65afe9f74b) | Jul 16, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [6087b16809](https://linux-hardware.org/?probe=6087b16809) | Jul 15, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [dd63c138ad](https://linux-hardware.org/?probe=dd63c138ad) | Jul 15, 2023 |
| ASRock        | A320M-HDV R4.0              | [8df4f1a098](https://linux-hardware.org/?probe=8df4f1a098) | Jul 14, 2023 |
| MSI           | B450M-A PRO MAX             | [9ec51bc7eb](https://linux-hardware.org/?probe=9ec51bc7eb) | Jul 14, 2023 |
| Acer          | Aspire TC-380               | [94f5f10ff2](https://linux-hardware.org/?probe=94f5f10ff2) | Jul 14, 2023 |
| MSI           | H510I PRO WIFI              | [23fef6418b](https://linux-hardware.org/?probe=23fef6418b) | Jul 13, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [6c08fefa24](https://linux-hardware.org/?probe=6c08fefa24) | Jul 13, 2023 |
| ASUSTek       | K8V-X                       | [7562568efe](https://linux-hardware.org/?probe=7562568efe) | Jul 13, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [cd3de89b97](https://linux-hardware.org/?probe=cd3de89b97) | Jul 12, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [40281279ab](https://linux-hardware.org/?probe=40281279ab) | Jul 12, 2023 |
| ASUSTek       | PRIME H610M-R D4            | [f7e7c29964](https://linux-hardware.org/?probe=f7e7c29964) | Jul 12, 2023 |
| Acer          | EG31M R01-B1                | [dbc5e1d5db](https://linux-hardware.org/?probe=dbc5e1d5db) | Jul 11, 2023 |
| Acer          | EG31M R01-B1                | [12f533494b](https://linux-hardware.org/?probe=12f533494b) | Jul 11, 2023 |
| HP            | 89D8 SMVB                   | [68ee3dff51](https://linux-hardware.org/?probe=68ee3dff51) | Jul 11, 2023 |
| MSI           | A320M-A PRO                 | [1a540134de](https://linux-hardware.org/?probe=1a540134de) | Jul 11, 2023 |
| ASRock        | A75 Extreme6                | [1c0eb1b3ea](https://linux-hardware.org/?probe=1c0eb1b3ea) | Jul 10, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [b7d5b7b224](https://linux-hardware.org/?probe=b7d5b7b224) | Jul 10, 2023 |
| Shenzhen M... | F7BAA                       | [29c15fc4d2](https://linux-hardware.org/?probe=29c15fc4d2) | Jul 10, 2023 |
| MSI           | B550-A PRO                  | [483109bdd9](https://linux-hardware.org/?probe=483109bdd9) | Jul 09, 2023 |
| MSI           | PRO B650-P WIFI             | [7d98a62bcc](https://linux-hardware.org/?probe=7d98a62bcc) | Jul 09, 2023 |
| ASUSTek       | ROG STRIX Z790-I GAMING ... | [a1b896bd04](https://linux-hardware.org/?probe=a1b896bd04) | Jul 09, 2023 |
| HP            | 82A1                        | [2db1718d8f](https://linux-hardware.org/?probe=2db1718d8f) | Jul 08, 2023 |
| ASUSTek       | PRIME Z390-P                | [018447554a](https://linux-hardware.org/?probe=018447554a) | Jul 08, 2023 |
| Shenzhen M... | F7BAA                       | [aa3a981cb3](https://linux-hardware.org/?probe=aa3a981cb3) | Jul 08, 2023 |
| HP            | 82A1                        | [1bab189e8d](https://linux-hardware.org/?probe=1bab189e8d) | Jul 08, 2023 |
| MSI           | B550-A PRO                  | [9c6ce21357](https://linux-hardware.org/?probe=9c6ce21357) | Jul 07, 2023 |
| Gigabyte      | H170-HD3-CF                 | [f2203ae88e](https://linux-hardware.org/?probe=f2203ae88e) | Jul 07, 2023 |
| Gigabyte      | H170-HD3-CF                 | [e2adf09ecf](https://linux-hardware.org/?probe=e2adf09ecf) | Jul 07, 2023 |
| Acer          | Aspire TC-885 V:1.1         | [a2dc9efa21](https://linux-hardware.org/?probe=a2dc9efa21) | Jul 06, 2023 |
| HP            | 82FE 11                     | [fcac934bde](https://linux-hardware.org/?probe=fcac934bde) | Jul 06, 2023 |
| ASRock        | H510M-HDV R2.0              | [2cb98a7961](https://linux-hardware.org/?probe=2cb98a7961) | Jul 06, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | [79bd04036c](https://linux-hardware.org/?probe=79bd04036c) | Jul 05, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [44140c28bb](https://linux-hardware.org/?probe=44140c28bb) | Jul 05, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [a4b93f17c2](https://linux-hardware.org/?probe=a4b93f17c2) | Jul 05, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [5699e37170](https://linux-hardware.org/?probe=5699e37170) | Jul 04, 2023 |
| ADLINK Tec... | ABX-5600 A1                 | [db376a9857](https://linux-hardware.org/?probe=db376a9857) | Jul 04, 2023 |
| Chuwi         | RZBOX                       | [78bdc20fe8](https://linux-hardware.org/?probe=78bdc20fe8) | Jul 03, 2023 |
| ADLINK Tec... | ABX-5600 A1                 | [46dbe425b5](https://linux-hardware.org/?probe=46dbe425b5) | Jul 03, 2023 |
| Dell          | 0D24M8 A01                  | [8ad2509708](https://linux-hardware.org/?probe=8ad2509708) | Jul 03, 2023 |
| MSI           | Z170A KRAIT GAMING          | [4bede9ff31](https://linux-hardware.org/?probe=4bede9ff31) | Jul 03, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [349ff94e9f](https://linux-hardware.org/?probe=349ff94e9f) | Jul 02, 2023 |
| ASRock        | B450 Pro4                   | [304cab93f1](https://linux-hardware.org/?probe=304cab93f1) | Jul 02, 2023 |
| Cincoze       | DX-1000.01.001              | [696453bbab](https://linux-hardware.org/?probe=696453bbab) | Jul 02, 2023 |
| MSI           | Boston                      | [39a458d562](https://linux-hardware.org/?probe=39a458d562) | Jul 01, 2023 |
| Unknown       | Unknown                     | [1b8105097a](https://linux-hardware.org/?probe=1b8105097a) | Jul 01, 2023 |
| ASUSTek       | PRIME Z590-P                | [fb7e164f62](https://linux-hardware.org/?probe=fb7e164f62) | Jul 01, 2023 |
| ASUSTek       | PRIME Z590-P                | [2774be84e6](https://linux-hardware.org/?probe=2774be84e6) | Jul 01, 2023 |
| Gigabyte      | Z490 VISION D               | [97ebc05877](https://linux-hardware.org/?probe=97ebc05877) | Jul 01, 2023 |
| Unknown       | Unknown                     | [53eedfaac9](https://linux-hardware.org/?probe=53eedfaac9) | Jul 01, 2023 |
| Gigabyte      | Z490 VISION D               | [06d9033522](https://linux-hardware.org/?probe=06d9033522) | Jul 01, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [d42cdc8551](https://linux-hardware.org/?probe=d42cdc8551) | Jun 30, 2023 |
| ASRock        | 775Dual-VSTA                | [7ddc95bb2f](https://linux-hardware.org/?probe=7ddc95bb2f) | Jun 30, 2023 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | [4ad54ee28d](https://linux-hardware.org/?probe=4ad54ee28d) | Jun 29, 2023 |
| ASUSTek       | F2A85-M PRO                 | [a7617c12c5](https://linux-hardware.org/?probe=a7617c12c5) | Jun 28, 2023 |
| Dell          | 0XJ5V0 A03                  | [a1595a590c](https://linux-hardware.org/?probe=a1595a590c) | Jun 28, 2023 |
| ASUSTek       | PRIME Z370M-PLUS II         | [1114cf7328](https://linux-hardware.org/?probe=1114cf7328) | Jun 28, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [0251f7e1ab](https://linux-hardware.org/?probe=0251f7e1ab) | Jun 27, 2023 |
| MSI           | B250M PRO-VH                | [cb47380993](https://linux-hardware.org/?probe=cb47380993) | Jun 27, 2023 |
| MSI           | X570-A PRO                  | [f664b455eb](https://linux-hardware.org/?probe=f664b455eb) | Jun 26, 2023 |
| ASUSTek       | B85M-G                      | [5a9f85740e](https://linux-hardware.org/?probe=5a9f85740e) | Jun 26, 2023 |
| ASUSTek       | H110M-K                     | [8a0a603eef](https://linux-hardware.org/?probe=8a0a603eef) | Jun 26, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | [aab1616d0e](https://linux-hardware.org/?probe=aab1616d0e) | Jun 25, 2023 |
| HP            | 8437                        | [477b6d5623](https://linux-hardware.org/?probe=477b6d5623) | Jun 24, 2023 |
| ASUSTek       | P5SD2-VM                    | [d91441b98b](https://linux-hardware.org/?probe=d91441b98b) | Jun 24, 2023 |
| MSI           | MS-7360                     | [9a0d46b069](https://linux-hardware.org/?probe=9a0d46b069) | Jun 23, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [2fb45a65c8](https://linux-hardware.org/?probe=2fb45a65c8) | Jun 23, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [ae8e0ef85b](https://linux-hardware.org/?probe=ae8e0ef85b) | Jun 23, 2023 |
| Intel         | X79                         | [8c50d3b5e8](https://linux-hardware.org/?probe=8c50d3b5e8) | Jun 20, 2023 |
| AMI           | Intel                       | [94c1b63cc6](https://linux-hardware.org/?probe=94c1b63cc6) | Jun 20, 2023 |
| ASUSTek       | P8H61-M LX                  | [35de204113](https://linux-hardware.org/?probe=35de204113) | Jun 19, 2023 |
| Acer          | Aspire TC-780               | [7412881615](https://linux-hardware.org/?probe=7412881615) | Jun 18, 2023 |
| ASUSTek       | P8H61-M LX                  | [fe3b7abf1d](https://linux-hardware.org/?probe=fe3b7abf1d) | Jun 17, 2023 |
| MSI           | Boston                      | [8bc41737a5](https://linux-hardware.org/?probe=8bc41737a5) | Jun 17, 2023 |
| ASUSTek       | P8H61-M LX                  | [23b64edd39](https://linux-hardware.org/?probe=23b64edd39) | Jun 17, 2023 |
| ASUSTek       | P5B-Deluxe                  | [4dae4ff7c6](https://linux-hardware.org/?probe=4dae4ff7c6) | Jun 16, 2023 |
| Unknown       | Unknown                     | [e6ac28ac73](https://linux-hardware.org/?probe=e6ac28ac73) | Jun 14, 2023 |
| Unknown       | Unknown                     | [ca27fe4c19](https://linux-hardware.org/?probe=ca27fe4c19) | Jun 14, 2023 |
| Chuwi         | RZBOX                       | [11bb40ef32](https://linux-hardware.org/?probe=11bb40ef32) | Jun 13, 2023 |
| HP            | 18E7                        | [1be1b42bb4](https://linux-hardware.org/?probe=1be1b42bb4) | Jun 13, 2023 |
| HP            | 18E7                        | [cbf4019da2](https://linux-hardware.org/?probe=cbf4019da2) | Jun 13, 2023 |
| ASUSTek       | H110M-A                     | [d9cd48b67d](https://linux-hardware.org/?probe=d9cd48b67d) | Jun 12, 2023 |
| Lenovo        | 103D SDK0Q40112 WIN 3305... | [5c2eef3678](https://linux-hardware.org/?probe=5c2eef3678) | Jun 12, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [373e36422d](https://linux-hardware.org/?probe=373e36422d) | Jun 12, 2023 |
| ASUSTek       | PRIME H270-PLUS             | [017c7fd564](https://linux-hardware.org/?probe=017c7fd564) | Jun 11, 2023 |
| Chuwi         | RZBOX                       | [e31b33ae5e](https://linux-hardware.org/?probe=e31b33ae5e) | Jun 11, 2023 |
| MSI           | H81I                        | [c7c19346a2](https://linux-hardware.org/?probe=c7c19346a2) | Jun 09, 2023 |
| HP            | 09E0h                       | [b6bb01441c](https://linux-hardware.org/?probe=b6bb01441c) | Jun 09, 2023 |
| HP            | 2B35                        | [5921b94b60](https://linux-hardware.org/?probe=5921b94b60) | Jun 09, 2023 |
| MSI           | X470 GAMING PLUS            | [eea4cea0e0](https://linux-hardware.org/?probe=eea4cea0e0) | Jun 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [35c7fcb130](https://linux-hardware.org/?probe=35c7fcb130) | Jun 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [f4e1a7a712](https://linux-hardware.org/?probe=f4e1a7a712) | Jun 08, 2023 |
| Lenovo        | 317C SDK0J40700 WIN 3258... | [d5d7ffe9df](https://linux-hardware.org/?probe=d5d7ffe9df) | Jun 08, 2023 |
| HP            | 1905                        | [0617f4e698](https://linux-hardware.org/?probe=0617f4e698) | Jun 07, 2023 |
| Lenovo        | 317C SDK0J40700 WIN 3258... | [23b41d16db](https://linux-hardware.org/?probe=23b41d16db) | Jun 06, 2023 |
| Chuwi         | RZBOX                       | [f395c0f429](https://linux-hardware.org/?probe=f395c0f429) | Jun 06, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d288737b23](https://linux-hardware.org/?probe=d288737b23) | Jun 05, 2023 |
| MSI           | B360M PRO-VH                | [8d150fb2b0](https://linux-hardware.org/?probe=8d150fb2b0) | Jun 05, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [cc575f0073](https://linux-hardware.org/?probe=cc575f0073) | Jun 05, 2023 |
| Unknown       | Unknown                     | [292269611c](https://linux-hardware.org/?probe=292269611c) | Jun 05, 2023 |
| MSI           | Boston                      | [9f5efc29ad](https://linux-hardware.org/?probe=9f5efc29ad) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [3af6e03b1c](https://linux-hardware.org/?probe=3af6e03b1c) | Jun 04, 2023 |
| Gigabyte      | B450M DS3H-CF               | [4b162cac99](https://linux-hardware.org/?probe=4b162cac99) | Jun 04, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [70e5950511](https://linux-hardware.org/?probe=70e5950511) | Jun 04, 2023 |
| ASRock        | A320M-HDV R4.0              | [f472cba5a6](https://linux-hardware.org/?probe=f472cba5a6) | Jun 04, 2023 |
| MSI           | MAG B550M MORTAR            | [3d911ac9c9](https://linux-hardware.org/?probe=3d911ac9c9) | Jun 03, 2023 |
| ASRock        | B365 Pro4                   | [35fff15a30](https://linux-hardware.org/?probe=35fff15a30) | Jun 02, 2023 |
| ASRock        | B365 Pro4                   | [54fcb811b8](https://linux-hardware.org/?probe=54fcb811b8) | Jun 02, 2023 |
| Gigabyte      | B550M DS3H                  | [a8f8239e40](https://linux-hardware.org/?probe=a8f8239e40) | Jun 02, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [5430a83fca](https://linux-hardware.org/?probe=5430a83fca) | Jun 01, 2023 |
| HP            | 18E7                        | [a3f557389e](https://linux-hardware.org/?probe=a3f557389e) | Jun 01, 2023 |
| ASRock        | H310M-HDV                   | [3dc5138ecd](https://linux-hardware.org/?probe=3dc5138ecd) | Jun 01, 2023 |
| Fujitsu Si... | D2740-A2 S26361-D2740-A2    | [165491db1f](https://linux-hardware.org/?probe=165491db1f) | Jun 01, 2023 |
| Gigabyte      | B550M DS3H                  | [df7287f2c8](https://linux-hardware.org/?probe=df7287f2c8) | Jun 01, 2023 |
| ASRock        | X370 Pro4                   | [aaeac4c226](https://linux-hardware.org/?probe=aaeac4c226) | Jun 01, 2023 |
| MSI           | H110M PRO-VH PLUS           | [cfabc605f7](https://linux-hardware.org/?probe=cfabc605f7) | Jun 01, 2023 |
| Acer          | WG43M                       | [cdd78e1cac](https://linux-hardware.org/?probe=cdd78e1cac) | May 31, 2023 |
| ASRock        | H81M-HDS R2.0               | [810f6b35ea](https://linux-hardware.org/?probe=810f6b35ea) | May 31, 2023 |
| ASUSTek       | P9X79                       | [c677ff5b2d](https://linux-hardware.org/?probe=c677ff5b2d) | May 31, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [de30e713bf](https://linux-hardware.org/?probe=de30e713bf) | May 30, 2023 |
| ASUSTek       | P5KPL-AM                    | [48359795cc](https://linux-hardware.org/?probe=48359795cc) | May 30, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [4679a6e565](https://linux-hardware.org/?probe=4679a6e565) | May 29, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [ec89dcb694](https://linux-hardware.org/?probe=ec89dcb694) | May 29, 2023 |
| Gigabyte      | B450M DS3H-CF               | [cc8e36e75a](https://linux-hardware.org/?probe=cc8e36e75a) | May 26, 2023 |
| ASRock        | 990FX Extreme4              | [8c61dd5381](https://linux-hardware.org/?probe=8c61dd5381) | May 26, 2023 |
| ASUSTek       | P7P55-M                     | [a8fd95ce79](https://linux-hardware.org/?probe=a8fd95ce79) | May 25, 2023 |
| ASUSTek       | PRIME H270-PRO              | [2a14c05edc](https://linux-hardware.org/?probe=2a14c05edc) | May 25, 2023 |
| HPE           | ProLiant MicroServer Gen... | [530b841978](https://linux-hardware.org/?probe=530b841978) | May 25, 2023 |
| MSI           | X99A GAMING PRO CARBON      | [4c9595e6ea](https://linux-hardware.org/?probe=4c9595e6ea) | May 24, 2023 |
| ASUSTek       | PRIME B350M-A               | [174a3139c4](https://linux-hardware.org/?probe=174a3139c4) | May 24, 2023 |
| ASRock        | AB350M Pro4                 | [9f7d80df58](https://linux-hardware.org/?probe=9f7d80df58) | May 23, 2023 |
| BESSTAR Te... | UM350                       | [e177bb8db5](https://linux-hardware.org/?probe=e177bb8db5) | May 23, 2023 |
| MSI           | B550-A PRO                  | [1ec3710265](https://linux-hardware.org/?probe=1ec3710265) | May 23, 2023 |
| MSI           | X99A GAMING PRO CARBON      | [d0312b1a56](https://linux-hardware.org/?probe=d0312b1a56) | May 23, 2023 |
| HP            | 2AF3                        | [e70a1c12fb](https://linux-hardware.org/?probe=e70a1c12fb) | May 22, 2023 |
| Unknown       | Unknown                     | [9cc7b8d0a8](https://linux-hardware.org/?probe=9cc7b8d0a8) | May 22, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [a8e6f277e2](https://linux-hardware.org/?probe=a8e6f277e2) | May 22, 2023 |
| ASRock        | 775Dual-VSTA                | [2eb8cdff34](https://linux-hardware.org/?probe=2eb8cdff34) | May 21, 2023 |
| MSI           | PRO B760-P WIFI DDR4        | [c8c091e2d8](https://linux-hardware.org/?probe=c8c091e2d8) | May 21, 2023 |
| HP            | 8437                        | [d41a0c8439](https://linux-hardware.org/?probe=d41a0c8439) | May 20, 2023 |
| HP            | 8437                        | [ceacc79bf6](https://linux-hardware.org/?probe=ceacc79bf6) | May 19, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [76a17acffb](https://linux-hardware.org/?probe=76a17acffb) | May 19, 2023 |
| Dell          | 0D881F A06                  | [2d5184956b](https://linux-hardware.org/?probe=2d5184956b) | May 18, 2023 |
| ASUSTek       | P5B                         | [9d815bcd44](https://linux-hardware.org/?probe=9d815bcd44) | May 18, 2023 |
| ASUSTek       | P5B                         | [70be41e795](https://linux-hardware.org/?probe=70be41e795) | May 18, 2023 |
| ASUSTek       | PRIME Z270-A                | [790c5137ba](https://linux-hardware.org/?probe=790c5137ba) | May 18, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [bb4c9d6b4c](https://linux-hardware.org/?probe=bb4c9d6b4c) | May 17, 2023 |
| HP            | 3048h                       | [9e65995057](https://linux-hardware.org/?probe=9e65995057) | May 17, 2023 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | [7f3487434e](https://linux-hardware.org/?probe=7f3487434e) | May 17, 2023 |
| HP            | 09F8h                       | [380bbcda71](https://linux-hardware.org/?probe=380bbcda71) | May 17, 2023 |
| Lenovo        | 317E SDK0J40700 WIN 3258... | [281042ebf0](https://linux-hardware.org/?probe=281042ebf0) | May 17, 2023 |
| HP            | 18E5                        | [5e25e2156a](https://linux-hardware.org/?probe=5e25e2156a) | May 16, 2023 |
| Dell          | 0D24M8 A01                  | [4dcf0cf794](https://linux-hardware.org/?probe=4dcf0cf794) | May 16, 2023 |
| ASUSTek       | PRIME B650-PLUS             | [212936564d](https://linux-hardware.org/?probe=212936564d) | May 16, 2023 |
| MSI           | MS-7369                     | [4a083f89af](https://linux-hardware.org/?probe=4a083f89af) | May 16, 2023 |
| Lenovo        | SHARKBAY NOK                | [16308738b3](https://linux-hardware.org/?probe=16308738b3) | May 15, 2023 |
| BESSTAR Te... | UM350                       | [fafdf532fb](https://linux-hardware.org/?probe=fafdf532fb) | May 15, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [0495c4f485](https://linux-hardware.org/?probe=0495c4f485) | May 14, 2023 |
| Gigabyte      | A520M DS3H                  | [e053d0d304](https://linux-hardware.org/?probe=e053d0d304) | May 13, 2023 |
| ASRock        | 775Dual-VSTA                | [4e603c1756](https://linux-hardware.org/?probe=4e603c1756) | May 12, 2023 |
| ASRock        | 775Dual-VSTA                | [5379481e09](https://linux-hardware.org/?probe=5379481e09) | May 12, 2023 |
| HP            | 1998                        | [b806151d9f](https://linux-hardware.org/?probe=b806151d9f) | May 12, 2023 |
| Gigabyte      | Z87X-OC-CF                  | [068ef24174](https://linux-hardware.org/?probe=068ef24174) | May 12, 2023 |
| ASUSTek       | PRO B460M-C                 | [80892a273c](https://linux-hardware.org/?probe=80892a273c) | May 11, 2023 |
| MSI           | B150M PRO-VDH               | [59efd46e1c](https://linux-hardware.org/?probe=59efd46e1c) | May 11, 2023 |
| ASRock        | Z370 Extreme4               | [bdd9bcedf5](https://linux-hardware.org/?probe=bdd9bcedf5) | May 11, 2023 |
| Gigabyte      | B550 GAMING X V2            | [4d4946eec9](https://linux-hardware.org/?probe=4d4946eec9) | May 11, 2023 |
| HP            | 2ADE                        | [ef4aa64bd5](https://linux-hardware.org/?probe=ef4aa64bd5) | May 10, 2023 |
| Gigabyte      | B550 GAMING X V2            | [666c071a8b](https://linux-hardware.org/?probe=666c071a8b) | May 09, 2023 |
| ASRock        | H61M-DGS                    | [0b1518261e](https://linux-hardware.org/?probe=0b1518261e) | May 09, 2023 |
| ASUSTek       | M32CD4-K                    | [0bca52bcc5](https://linux-hardware.org/?probe=0bca52bcc5) | May 09, 2023 |
| HP            | 2ADE                        | [bb8ee11580](https://linux-hardware.org/?probe=bb8ee11580) | May 08, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [3b4eb54186](https://linux-hardware.org/?probe=3b4eb54186) | May 08, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [ecfcb0cab6](https://linux-hardware.org/?probe=ecfcb0cab6) | May 07, 2023 |
| ASRock        | H61M-DGS                    | [96cfd64792](https://linux-hardware.org/?probe=96cfd64792) | May 07, 2023 |
| MSI           | X570-A PRO                  | [46894747b1](https://linux-hardware.org/?probe=46894747b1) | May 05, 2023 |
| MSI           | X570-A PRO                  | [2723e21a6e](https://linux-hardware.org/?probe=2723e21a6e) | May 05, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [f8d80b7cf0](https://linux-hardware.org/?probe=f8d80b7cf0) | May 03, 2023 |
| Gigabyte      | Z170X-Gaming 3              | [50f922927f](https://linux-hardware.org/?probe=50f922927f) | May 03, 2023 |
| Unknown       | 1.0                         | [5f99ebeed7](https://linux-hardware.org/?probe=5f99ebeed7) | May 02, 2023 |
| ASUSTek       | ROG STRIX X299-E GAMING     | [553a101cf8](https://linux-hardware.org/?probe=553a101cf8) | May 02, 2023 |
| Acer          | H11H4-AI V:1.0              | [12d9338aba](https://linux-hardware.org/?probe=12d9338aba) | May 02, 2023 |
| Acer          | H11H4-AI V:1.0              | [eaa909b055](https://linux-hardware.org/?probe=eaa909b055) | May 02, 2023 |
| ASRock        | G41M-GS                     | [0824a9c571](https://linux-hardware.org/?probe=0824a9c571) | May 01, 2023 |
| Dell          | 0WR7PY A01                  | [dfe07c7749](https://linux-hardware.org/?probe=dfe07c7749) | May 01, 2023 |
| ASRock        | H61M-DGS                    | [f395109c45](https://linux-hardware.org/?probe=f395109c45) | May 01, 2023 |
| Pegatron      | 2A94                        | [7dcdfa9b9f](https://linux-hardware.org/?probe=7dcdfa9b9f) | May 01, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [d02d21f47a](https://linux-hardware.org/?probe=d02d21f47a) | May 01, 2023 |
| ASRock        | 970 Pro3 R2.0               | [26681d2879](https://linux-hardware.org/?probe=26681d2879) | May 01, 2023 |
| ASRock        | 970 Pro3 R2.0               | [577b5e8f51](https://linux-hardware.org/?probe=577b5e8f51) | May 01, 2023 |
| MSI           | 760GM-P23                   | [4ac55a6bbe](https://linux-hardware.org/?probe=4ac55a6bbe) | Apr 30, 2023 |
| Dell          | 0GXM1W A02                  | [7dcb847a6c](https://linux-hardware.org/?probe=7dcb847a6c) | Apr 30, 2023 |
| ASRock        | H61M-HVS                    | [77f87da085](https://linux-hardware.org/?probe=77f87da085) | Apr 29, 2023 |
| Dell          | 0WR7PY A01                  | [e585f66f17](https://linux-hardware.org/?probe=e585f66f17) | Apr 29, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | [4801547d54](https://linux-hardware.org/?probe=4801547d54) | Apr 29, 2023 |
| ASUSTek       | Z97-P                       | [8ea78b28f1](https://linux-hardware.org/?probe=8ea78b28f1) | Apr 29, 2023 |
| HP            | 1998                        | [6f816ac95a](https://linux-hardware.org/?probe=6f816ac95a) | Apr 29, 2023 |
| HP            | 339A                        | [4f9a0b2661](https://linux-hardware.org/?probe=4f9a0b2661) | Apr 28, 2023 |
| Unknown       | RS780-SB700                 | [94f2408a63](https://linux-hardware.org/?probe=94f2408a63) | Apr 28, 2023 |
| Unknown       | RS780-SB700                 | [76c36882d9](https://linux-hardware.org/?probe=76c36882d9) | Apr 28, 2023 |
| MSI           | X470 GAMING PLUS            | [a5d42a7b78](https://linux-hardware.org/?probe=a5d42a7b78) | Apr 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [98ed5e9a2e](https://linux-hardware.org/?probe=98ed5e9a2e) | Apr 25, 2023 |
| Gigabyte      | 945GCM-S2L                  | [405bcbb43c](https://linux-hardware.org/?probe=405bcbb43c) | Apr 25, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [b144f1aa54](https://linux-hardware.org/?probe=b144f1aa54) | Apr 24, 2023 |
| Dell          | 0R790T A00                  | [7ca2bb8871](https://linux-hardware.org/?probe=7ca2bb8871) | Apr 24, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [34278ef67e](https://linux-hardware.org/?probe=34278ef67e) | Apr 24, 2023 |
| ASUSTek       | PRO B460M-C                 | [2ea3950e19](https://linux-hardware.org/?probe=2ea3950e19) | Apr 24, 2023 |
| ASRock        | H61M-DGS                    | [154380c27c](https://linux-hardware.org/?probe=154380c27c) | Apr 24, 2023 |
| MSI           | B460M PRO-VDH               | [f7709c23a1](https://linux-hardware.org/?probe=f7709c23a1) | Apr 24, 2023 |
| MSI           | Z390-A PRO                  | [74cf7ef6e5](https://linux-hardware.org/?probe=74cf7ef6e5) | Apr 23, 2023 |
| AMI           | Intel                       | [62d06b215e](https://linux-hardware.org/?probe=62d06b215e) | Apr 23, 2023 |
| ASRock        | Z77 Pro3                    | [2f4b412834](https://linux-hardware.org/?probe=2f4b412834) | Apr 22, 2023 |
| ASUSTek       | ET1602                      | [637fb8c9ce](https://linux-hardware.org/?probe=637fb8c9ce) | Apr 22, 2023 |
| MSI           | B360M BAZOOKA               | [46516c6f3a](https://linux-hardware.org/?probe=46516c6f3a) | Apr 22, 2023 |
| ASRock        | H61M/U3S3                   | [8fd7aea5ea](https://linux-hardware.org/?probe=8fd7aea5ea) | Apr 22, 2023 |
| HP            | 82F2 A01                    | [fbcf679bae](https://linux-hardware.org/?probe=fbcf679bae) | Apr 21, 2023 |
| ELSKY         | M219F-6C                    | [5f41223856](https://linux-hardware.org/?probe=5f41223856) | Apr 21, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [f7ca0a552d](https://linux-hardware.org/?probe=f7ca0a552d) | Apr 20, 2023 |
| ASUSTek       | CG8270                      | [3f390ff38e](https://linux-hardware.org/?probe=3f390ff38e) | Apr 20, 2023 |
| ASUSTek       | CG8270                      | [a4f54ca55b](https://linux-hardware.org/?probe=a4f54ca55b) | Apr 20, 2023 |
| ASUSTek       | P5G41T-M LX                 | [b830d8001e](https://linux-hardware.org/?probe=b830d8001e) | Apr 19, 2023 |
| Gigabyte      | Z68X-UD7-B3                 | [175cfb374b](https://linux-hardware.org/?probe=175cfb374b) | Apr 18, 2023 |
| HP            | 18E9                        | [8c36235f13](https://linux-hardware.org/?probe=8c36235f13) | Apr 18, 2023 |
| MSI           | Z87M GAMING                 | [9552ef2174](https://linux-hardware.org/?probe=9552ef2174) | Apr 17, 2023 |
| MSI           | PRO B660-A DDR4             | [b274726abd](https://linux-hardware.org/?probe=b274726abd) | Apr 17, 2023 |
| ASRock        | N3700-ITX                   | [849679b442](https://linux-hardware.org/?probe=849679b442) | Apr 17, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [9df377aaf2](https://linux-hardware.org/?probe=9df377aaf2) | Apr 17, 2023 |
| ASUSTek       | PRIME H370M-PLUS            | [0a544df503](https://linux-hardware.org/?probe=0a544df503) | Apr 17, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [5109f5c8d9](https://linux-hardware.org/?probe=5109f5c8d9) | Apr 17, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [67ce5b3ab1](https://linux-hardware.org/?probe=67ce5b3ab1) | Apr 16, 2023 |
| MSI           | H310M PRO-VD PLUS           | [bff38bc725](https://linux-hardware.org/?probe=bff38bc725) | Apr 16, 2023 |
| ASRock        | N68-GS4 FX                  | [19a6cddfe0](https://linux-hardware.org/?probe=19a6cddfe0) | Apr 16, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [4375bd0fb6](https://linux-hardware.org/?probe=4375bd0fb6) | Apr 16, 2023 |
| ASUSTek       | P5E Deluxe                  | [ce0a1adc22](https://linux-hardware.org/?probe=ce0a1adc22) | Apr 16, 2023 |
| ASUSTek       | PRIME A320M-K               | [2eb96e4d6e](https://linux-hardware.org/?probe=2eb96e4d6e) | Apr 16, 2023 |
| ASUSTek       | PRIME A320M-K               | [7d34909c86](https://linux-hardware.org/?probe=7d34909c86) | Apr 16, 2023 |
| ASUSTek       | Z87-A                       | [3e96076874](https://linux-hardware.org/?probe=3e96076874) | Apr 15, 2023 |
| ASRock        | H61M-DGS                    | [506ba2605a](https://linux-hardware.org/?probe=506ba2605a) | Apr 15, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | [e17175b9ac](https://linux-hardware.org/?probe=e17175b9ac) | Apr 15, 2023 |
| MSI           | 970A-G45                    | [8f62fd1fb1](https://linux-hardware.org/?probe=8f62fd1fb1) | Apr 15, 2023 |
| MSI           | H310M PRO-VD PLUS           | [9f6209111c](https://linux-hardware.org/?probe=9f6209111c) | Apr 14, 2023 |
| Cincoze       | DX-1000.01.001              | [fa2c48478a](https://linux-hardware.org/?probe=fa2c48478a) | Apr 13, 2023 |
| ASUSTek       | PRIME A320M-K               | [bbc081e43e](https://linux-hardware.org/?probe=bbc081e43e) | Apr 13, 2023 |
| ASUSTek       | PRIME A320M-K               | [a59a28162e](https://linux-hardware.org/?probe=a59a28162e) | Apr 13, 2023 |
| Acer          | Veriton K8-680G V:1.0       | [9ab3fc183a](https://linux-hardware.org/?probe=9ab3fc183a) | Apr 13, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [ea50bc5d28](https://linux-hardware.org/?probe=ea50bc5d28) | Apr 13, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [8e05a5e529](https://linux-hardware.org/?probe=8e05a5e529) | Apr 13, 2023 |
| ASRock        | H410M-HVS                   | [23371691ec](https://linux-hardware.org/?probe=23371691ec) | Apr 12, 2023 |
| Acer          | Veriton K8-680G V:1.0       | [214038993e](https://linux-hardware.org/?probe=214038993e) | Apr 12, 2023 |
| ASUSTek       | M4A87TD EVO                 | [695de52123](https://linux-hardware.org/?probe=695de52123) | Apr 12, 2023 |
| ASUSTek       | B85M-G                      | [27bfaf568a](https://linux-hardware.org/?probe=27bfaf568a) | Apr 12, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [46eba03bed](https://linux-hardware.org/?probe=46eba03bed) | Apr 12, 2023 |
| MSI           | B450M-A PRO MAX             | [07353da9f6](https://linux-hardware.org/?probe=07353da9f6) | Apr 11, 2023 |
| Acer          | H57M01                      | [c62231ca98](https://linux-hardware.org/?probe=c62231ca98) | Apr 11, 2023 |
| MSI           | MEG X570 UNIFY              | [02d670e0db](https://linux-hardware.org/?probe=02d670e0db) | Apr 11, 2023 |
| Acer          | Aspire TC-780               | [ce8b386e5b](https://linux-hardware.org/?probe=ce8b386e5b) | Apr 11, 2023 |
| MSI           | H310M PRO-VD                | [498c52e62e](https://linux-hardware.org/?probe=498c52e62e) | Apr 10, 2023 |
| ASRock        | Q1900M                      | [6ff7177033](https://linux-hardware.org/?probe=6ff7177033) | Apr 09, 2023 |
| ASUSTek       | P7P55D-E                    | [1f8dc6aa3d](https://linux-hardware.org/?probe=1f8dc6aa3d) | Apr 09, 2023 |
| ASUSTek       | P7P55D-E                    | [ff595db737](https://linux-hardware.org/?probe=ff595db737) | Apr 09, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [621eb9522f](https://linux-hardware.org/?probe=621eb9522f) | Apr 09, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [6aae769b7a](https://linux-hardware.org/?probe=6aae769b7a) | Apr 09, 2023 |
| MSI           | B450M GAMING PLUS           | [cb57237789](https://linux-hardware.org/?probe=cb57237789) | Apr 08, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [e657bedde3](https://linux-hardware.org/?probe=e657bedde3) | Apr 08, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [bd1dc31213](https://linux-hardware.org/?probe=bd1dc31213) | Apr 07, 2023 |
| Gigabyte      | B75M-D3H                    | [bf0c0bb982](https://linux-hardware.org/?probe=bf0c0bb982) | Apr 07, 2023 |
| Dell          | 096JG8 A01                  | [9f5a3611b8](https://linux-hardware.org/?probe=9f5a3611b8) | Apr 07, 2023 |
| ASUSTek       | P8Z77-V LX                  | [241572fcea](https://linux-hardware.org/?probe=241572fcea) | Apr 07, 2023 |
| MSI           | B450M GAMING PLUS           | [51d2c2c17d](https://linux-hardware.org/?probe=51d2c2c17d) | Apr 06, 2023 |
| Dell          | 0GXM1W A02                  | [3fae5e4d5c](https://linux-hardware.org/?probe=3fae5e4d5c) | Apr 05, 2023 |
| Gigabyte      | H97-HD3                     | [caf5563d44](https://linux-hardware.org/?probe=caf5563d44) | Apr 05, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [0e7d453676](https://linux-hardware.org/?probe=0e7d453676) | Apr 05, 2023 |
| MSI           | 2A9C                        | [7a007c46d0](https://linux-hardware.org/?probe=7a007c46d0) | Apr 05, 2023 |
| ASUSTek       | PRIME Z370M-PLUS II         | [9fc5c6f8a7](https://linux-hardware.org/?probe=9fc5c6f8a7) | Apr 05, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [45bcedba86](https://linux-hardware.org/?probe=45bcedba86) | Apr 05, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [f08ea6ee04](https://linux-hardware.org/?probe=f08ea6ee04) | Apr 04, 2023 |
| ASUSTek       | P8Z77-V LX2                 | [250b63078d](https://linux-hardware.org/?probe=250b63078d) | Apr 04, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [f637374c21](https://linux-hardware.org/?probe=f637374c21) | Apr 03, 2023 |
| ASRock        | H61M-DGS                    | [e05fcde338](https://linux-hardware.org/?probe=e05fcde338) | Apr 03, 2023 |
| MSI           | Boston                      | [5a875def3f](https://linux-hardware.org/?probe=5a875def3f) | Apr 02, 2023 |
| ASUSTek       | P8Z77-V PRO                 | [b4207e264f](https://linux-hardware.org/?probe=b4207e264f) | Apr 02, 2023 |
| ASUSTek       | B150M-K D3                  | [08df6b50be](https://linux-hardware.org/?probe=08df6b50be) | Apr 02, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | [217bb72a30](https://linux-hardware.org/?probe=217bb72a30) | Apr 01, 2023 |
| ASUSTek       | PRIME Z490-P                | [bbbfbb2dfc](https://linux-hardware.org/?probe=bbbfbb2dfc) | Apr 01, 2023 |
| Intel         | DB75EN AAG39650-303         | [50d4a766a6](https://linux-hardware.org/?probe=50d4a766a6) | Apr 01, 2023 |
| Acer          | H11H4-AI V:1.0              | [d5337ce0e3](https://linux-hardware.org/?probe=d5337ce0e3) | Apr 01, 2023 |
| Acer          | WG43M                       | [77cb0bf517](https://linux-hardware.org/?probe=77cb0bf517) | Apr 01, 2023 |
| MSI           | X570-A PRO                  | [3093c50d3d](https://linux-hardware.org/?probe=3093c50d3d) | Mar 31, 2023 |
| MSI           | B550-A PRO                  | [f243351def](https://linux-hardware.org/?probe=f243351def) | Mar 31, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [871b458080](https://linux-hardware.org/?probe=871b458080) | Mar 31, 2023 |
| Gigabyte      | Z390 M-CF                   | [6bce2b9bc3](https://linux-hardware.org/?probe=6bce2b9bc3) | Mar 31, 2023 |
| DFI           | LP UT X58                   | [cd706d90d3](https://linux-hardware.org/?probe=cd706d90d3) | Mar 30, 2023 |
| Packard Be... | FIH57                       | [f1336c6cc4](https://linux-hardware.org/?probe=f1336c6cc4) | Mar 30, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [4ccaa78b43](https://linux-hardware.org/?probe=4ccaa78b43) | Mar 30, 2023 |
| ASUSTek       | H110M-R                     | [3c641024ba](https://linux-hardware.org/?probe=3c641024ba) | Mar 30, 2023 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | [e772d0e916](https://linux-hardware.org/?probe=e772d0e916) | Mar 29, 2023 |
| AZW           | U59                         | [3776cd7fb3](https://linux-hardware.org/?probe=3776cd7fb3) | Mar 29, 2023 |
| AZW           | U59                         | [f7958b8f39](https://linux-hardware.org/?probe=f7958b8f39) | Mar 29, 2023 |
| HP            | 3646h                       | [b173e99a5a](https://linux-hardware.org/?probe=b173e99a5a) | Mar 29, 2023 |
| ASUSTek       | P8Z77-V LX2                 | [23256b54cf](https://linux-hardware.org/?probe=23256b54cf) | Mar 29, 2023 |
| Acer          | H11H4-AI V:1.0              | [4266c0287d](https://linux-hardware.org/?probe=4266c0287d) | Mar 29, 2023 |
| MSI           | X570-A PRO                  | [0921fd9096](https://linux-hardware.org/?probe=0921fd9096) | Mar 28, 2023 |
| MSI           | B450-A PRO MAX              | [f3ebf80a3d](https://linux-hardware.org/?probe=f3ebf80a3d) | Mar 28, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | [5ac9dd16da](https://linux-hardware.org/?probe=5ac9dd16da) | Mar 28, 2023 |
| HP            | 18E6                        | [a406dc2463](https://linux-hardware.org/?probe=a406dc2463) | Mar 27, 2023 |
| ASUSTek       | X79-DELUXE                  | [da016d15c7](https://linux-hardware.org/?probe=da016d15c7) | Mar 27, 2023 |
| Unknown       | Unknown                     | [6f77d9be36](https://linux-hardware.org/?probe=6f77d9be36) | Mar 26, 2023 |
| Shenzhen M... | HX90G                       | [fb3f1be00d](https://linux-hardware.org/?probe=fb3f1be00d) | Mar 26, 2023 |
| MSI           | B550-A PRO                  | [eddf5a759a](https://linux-hardware.org/?probe=eddf5a759a) | Mar 26, 2023 |
| ASRock        | H61M-DGS                    | [76fc7291a6](https://linux-hardware.org/?probe=76fc7291a6) | Mar 26, 2023 |
| Acer          | Veriton M2631 V:1.0         | [4a4f12631a](https://linux-hardware.org/?probe=4a4f12631a) | Mar 26, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [c7e347798a](https://linux-hardware.org/?probe=c7e347798a) | Mar 26, 2023 |
| ASUSTek       | STRIX Z270I GAMING          | [4253088a92](https://linux-hardware.org/?probe=4253088a92) | Mar 25, 2023 |
| MSI           | Z170A PC MATE               | [ad4b4f6a8f](https://linux-hardware.org/?probe=ad4b4f6a8f) | Mar 25, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | [bf5cc186ea](https://linux-hardware.org/?probe=bf5cc186ea) | Mar 25, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [518cef7fe4](https://linux-hardware.org/?probe=518cef7fe4) | Mar 24, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [dc56fbfedb](https://linux-hardware.org/?probe=dc56fbfedb) | Mar 24, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [67d60d55e4](https://linux-hardware.org/?probe=67d60d55e4) | Mar 24, 2023 |
| ASUSTek       | P8P67 PRO                   | [7ed577df49](https://linux-hardware.org/?probe=7ed577df49) | Mar 23, 2023 |
| MSI           | Z590-A PRO                  | [ad6a144db9](https://linux-hardware.org/?probe=ad6a144db9) | Mar 23, 2023 |
| Lenovo        | SDK0F82993 WIN              | [fbff3ec47c](https://linux-hardware.org/?probe=fbff3ec47c) | Mar 23, 2023 |
| Gigabyte      | H81M-S2PV                   | [ac856abadc](https://linux-hardware.org/?probe=ac856abadc) | Mar 21, 2023 |
| ASRock        | B550M Pro4                  | [de1c89d1b0](https://linux-hardware.org/?probe=de1c89d1b0) | Mar 21, 2023 |
| Dell          | 0D441T A03                  | [926d18b722](https://linux-hardware.org/?probe=926d18b722) | Mar 20, 2023 |
| Acer          | Veriton M4610G              | [fed7efcecb](https://linux-hardware.org/?probe=fed7efcecb) | Mar 20, 2023 |
| Techvision    | TVI7309X B0                 | [67b681a703](https://linux-hardware.org/?probe=67b681a703) | Mar 20, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [42290142fb](https://linux-hardware.org/?probe=42290142fb) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [3500d84a8e](https://linux-hardware.org/?probe=3500d84a8e) | Mar 19, 2023 |
| ASRock        | H61M-DGS                    | [2b86166550](https://linux-hardware.org/?probe=2b86166550) | Mar 19, 2023 |
| Gigabyte      | 970A-DS3P                   | [727e5c46b7](https://linux-hardware.org/?probe=727e5c46b7) | Mar 18, 2023 |
| MSI           | H55M-P31                    | [e95e62df99](https://linux-hardware.org/?probe=e95e62df99) | Mar 18, 2023 |
| HP            | 18E7                        | [9f4d303ffa](https://linux-hardware.org/?probe=9f4d303ffa) | Mar 18, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [b346ffbe8e](https://linux-hardware.org/?probe=b346ffbe8e) | Mar 18, 2023 |
| ASUSTek       | TUF B350M-PLUS GAMING       | [be6db6cc62](https://linux-hardware.org/?probe=be6db6cc62) | Mar 17, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [7298c4b04b](https://linux-hardware.org/?probe=7298c4b04b) | Mar 17, 2023 |
| AMI           | Intel                       | [491d2cca9d](https://linux-hardware.org/?probe=491d2cca9d) | Mar 17, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [794bc239ab](https://linux-hardware.org/?probe=794bc239ab) | Mar 17, 2023 |
| MSI           | B550-A PRO                  | [730eec29f4](https://linux-hardware.org/?probe=730eec29f4) | Mar 16, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [37f8d341e3](https://linux-hardware.org/?probe=37f8d341e3) | Mar 14, 2023 |
| ASUSTek       | H61M-K                      | [783ff991d4](https://linux-hardware.org/?probe=783ff991d4) | Mar 14, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [ce69431d69](https://linux-hardware.org/?probe=ce69431d69) | Mar 14, 2023 |
| ASUSTek       | Rampage V EXTREME           | [e186537a7e](https://linux-hardware.org/?probe=e186537a7e) | Mar 14, 2023 |
| HP            | 18E7                        | [2042edf904](https://linux-hardware.org/?probe=2042edf904) | Mar 12, 2023 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | [a7105953c2](https://linux-hardware.org/?probe=a7105953c2) | Mar 12, 2023 |
| MSI           | P55-CD53                    | [d492118b16](https://linux-hardware.org/?probe=d492118b16) | Mar 12, 2023 |
| ASRock        | B460M Pro4                  | [50e790583a](https://linux-hardware.org/?probe=50e790583a) | Mar 12, 2023 |
| ASRock        | B450 Pro4                   | [4dd7be5be9](https://linux-hardware.org/?probe=4dd7be5be9) | Mar 12, 2023 |
| ASRock        | B450 Pro4                   | [ce0343a044](https://linux-hardware.org/?probe=ce0343a044) | Mar 12, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [17431ae177](https://linux-hardware.org/?probe=17431ae177) | Mar 12, 2023 |
| Dell          | 0P03DX A04                  | [e1c38bafaa](https://linux-hardware.org/?probe=e1c38bafaa) | Mar 11, 2023 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | [b7de8d093d](https://linux-hardware.org/?probe=b7de8d093d) | Mar 11, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [278b9e10a7](https://linux-hardware.org/?probe=278b9e10a7) | Mar 11, 2023 |
| Dell          | 0HY9JP A00                  | [caaa97e4ba](https://linux-hardware.org/?probe=caaa97e4ba) | Mar 11, 2023 |
| MSI           | Z590-A PRO                  | [c0c43b3296](https://linux-hardware.org/?probe=c0c43b3296) | Mar 11, 2023 |
| Acer          | Aspire TC-380               | [563bd52487](https://linux-hardware.org/?probe=563bd52487) | Mar 10, 2023 |
| ASRock        | H410M-HVS                   | [689186d7de](https://linux-hardware.org/?probe=689186d7de) | Mar 10, 2023 |
| MSI           | B550-A PRO                  | [493a2b9df6](https://linux-hardware.org/?probe=493a2b9df6) | Mar 10, 2023 |
| Gigabyte      | Z370N WIFI-CF               | [0fb1309bff](https://linux-hardware.org/?probe=0fb1309bff) | Mar 10, 2023 |
| HP            | 2B35                        | [ddb4d051ab](https://linux-hardware.org/?probe=ddb4d051ab) | Mar 09, 2023 |
| HP            | 2B35                        | [83f9096b77](https://linux-hardware.org/?probe=83f9096b77) | Mar 09, 2023 |
| MSI           | 970A-G46                    | [322eb2bdf0](https://linux-hardware.org/?probe=322eb2bdf0) | Mar 09, 2023 |
| Acer          | Veriton M480                | [8cd45e8525](https://linux-hardware.org/?probe=8cd45e8525) | Mar 09, 2023 |
| ASRock        | H61M-ITX                    | [ab7e81c6ca](https://linux-hardware.org/?probe=ab7e81c6ca) | Mar 09, 2023 |
| HP            | 8433 11                     | [95f33803c0](https://linux-hardware.org/?probe=95f33803c0) | Mar 08, 2023 |
| ASRock        | 970 Performance             | [c018d98ddc](https://linux-hardware.org/?probe=c018d98ddc) | Mar 08, 2023 |
| ASUSTek       | H81T                        | [c17251dbd9](https://linux-hardware.org/?probe=c17251dbd9) | Mar 08, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [3629efc5a5](https://linux-hardware.org/?probe=3629efc5a5) | Mar 08, 2023 |
| Gigabyte      | A320M-S2H-CF                | [00ddbf4ad1](https://linux-hardware.org/?probe=00ddbf4ad1) | Mar 07, 2023 |
| Acer          | Veriton X4610G              | [7f5cb2ac6a](https://linux-hardware.org/?probe=7f5cb2ac6a) | Mar 07, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [ced1079ce2](https://linux-hardware.org/?probe=ced1079ce2) | Mar 07, 2023 |
| Lenovo        | MAHOBAY                     | [e4e709f69a](https://linux-hardware.org/?probe=e4e709f69a) | Mar 07, 2023 |
| Acer          | H11H4-AI V:1.0              | [ff1a57749f](https://linux-hardware.org/?probe=ff1a57749f) | Mar 07, 2023 |
| Acer          | H11H4-AI V:1.0              | [37f7cabb58](https://linux-hardware.org/?probe=37f7cabb58) | Mar 07, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [ad0dbd5503](https://linux-hardware.org/?probe=ad0dbd5503) | Mar 06, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [0f36c1b0f7](https://linux-hardware.org/?probe=0f36c1b0f7) | Mar 06, 2023 |
| ASRock        | G31M-S                      | [69f88597a5](https://linux-hardware.org/?probe=69f88597a5) | Mar 05, 2023 |
| ASUSTek       | PRIME A320I-K               | [88e6308c0a](https://linux-hardware.org/?probe=88e6308c0a) | Mar 05, 2023 |
| AZW           | U59                         | [7711289a77](https://linux-hardware.org/?probe=7711289a77) | Mar 05, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [109fa85017](https://linux-hardware.org/?probe=109fa85017) | Mar 05, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [0d99cfc372](https://linux-hardware.org/?probe=0d99cfc372) | Mar 05, 2023 |
| MSI           | B450M MORTAR MAX            | [f8eea076e5](https://linux-hardware.org/?probe=f8eea076e5) | Mar 05, 2023 |
| HP            | 3397                        | [5250af801f](https://linux-hardware.org/?probe=5250af801f) | Mar 04, 2023 |
| ASUSTek       | P8H67                       | [99008935e9](https://linux-hardware.org/?probe=99008935e9) | Mar 04, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [860f53436b](https://linux-hardware.org/?probe=860f53436b) | Mar 03, 2023 |
| Gigabyte      | X570S AERO G                | [7e85150e30](https://linux-hardware.org/?probe=7e85150e30) | Mar 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [bdfb7a4647](https://linux-hardware.org/?probe=bdfb7a4647) | Mar 03, 2023 |
| AMI           | Intel                       | [b6d932a0ed](https://linux-hardware.org/?probe=b6d932a0ed) | Mar 02, 2023 |
| ASRock        | B365 Pro4                   | [16875fc443](https://linux-hardware.org/?probe=16875fc443) | Mar 02, 2023 |
| ASUSTek       | TUF Gaming H470-PRO         | [14a44a0392](https://linux-hardware.org/?probe=14a44a0392) | Mar 02, 2023 |
| Acer          | FIH57                       | [3f9c79675c](https://linux-hardware.org/?probe=3f9c79675c) | Mar 01, 2023 |
| HP            | 3396                        | [2da0f889cb](https://linux-hardware.org/?probe=2da0f889cb) | Mar 01, 2023 |
| ASUSTek       | SABERTOOTH P67              | [fa7df5da3b](https://linux-hardware.org/?probe=fa7df5da3b) | Mar 01, 2023 |
| ASUSTek       | BT6130                      | [dabd3e0232](https://linux-hardware.org/?probe=dabd3e0232) | Mar 01, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [4e701d495f](https://linux-hardware.org/?probe=4e701d495f) | Mar 01, 2023 |
| ASUSTek       | BT6130                      | [db5b346bd5](https://linux-hardware.org/?probe=db5b346bd5) | Feb 28, 2023 |
| Fujitsu       | D2990-A3 S26361-D2990-A3    | [6f1de5f17c](https://linux-hardware.org/?probe=6f1de5f17c) | Feb 28, 2023 |
| ASUSTek       | BT6130                      | [3549cfad14](https://linux-hardware.org/?probe=3549cfad14) | Feb 27, 2023 |
| ASUSTek       | M4N68T-M-V2                 | [051b66987e](https://linux-hardware.org/?probe=051b66987e) | Feb 27, 2023 |
| Cincoze       | DX-1000.01.001              | [64496d4ab7](https://linux-hardware.org/?probe=64496d4ab7) | Feb 27, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [580db05e08](https://linux-hardware.org/?probe=580db05e08) | Feb 27, 2023 |
| Cincoze       | DX-1000.01.001              | [7923f1dc21](https://linux-hardware.org/?probe=7923f1dc21) | Feb 26, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [310a65baea](https://linux-hardware.org/?probe=310a65baea) | Feb 26, 2023 |
| ASRock        | G41C-GS                     | [6a698dda57](https://linux-hardware.org/?probe=6a698dda57) | Feb 26, 2023 |
| ASUSTek       | PRIME X370-PRO              | [aaa112feae](https://linux-hardware.org/?probe=aaa112feae) | Feb 26, 2023 |
| Gigabyte      | B250M-D3H-CF                | [de180bd339](https://linux-hardware.org/?probe=de180bd339) | Feb 25, 2023 |
| ASUSTek       | PRIME H610M-R D4            | [3f2e38e322](https://linux-hardware.org/?probe=3f2e38e322) | Feb 25, 2023 |
| Gigabyte      | Z77MX-D3H                   | [bfd1042a82](https://linux-hardware.org/?probe=bfd1042a82) | Feb 25, 2023 |
| Unknown       | 1.0                         | [69594c956a](https://linux-hardware.org/?probe=69594c956a) | Feb 25, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d8b9174fba](https://linux-hardware.org/?probe=d8b9174fba) | Feb 25, 2023 |
| Unknown       | 1.0                         | [bab30a1ac1](https://linux-hardware.org/?probe=bab30a1ac1) | Feb 24, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [ccff1403b0](https://linux-hardware.org/?probe=ccff1403b0) | Feb 24, 2023 |
| ASRock        | Q1900-ITX                   | [4ed48d952c](https://linux-hardware.org/?probe=4ed48d952c) | Feb 24, 2023 |
| ASRock        | Q1900-ITX                   | [874cbd6e13](https://linux-hardware.org/?probe=874cbd6e13) | Feb 24, 2023 |
| ASUSTek       | M4A77T/USB3                 | [6bf574175a](https://linux-hardware.org/?probe=6bf574175a) | Feb 24, 2023 |
| ASRock        | H81M-DGS R2.0               | [2645328f34](https://linux-hardware.org/?probe=2645328f34) | Feb 23, 2023 |
| MSI           | X58 Pro                     | [22509b3e42](https://linux-hardware.org/?probe=22509b3e42) | Feb 23, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [d93c7d5661](https://linux-hardware.org/?probe=d93c7d5661) | Feb 23, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [7cdbd101a4](https://linux-hardware.org/?probe=7cdbd101a4) | Feb 23, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [576a0fc8f5](https://linux-hardware.org/?probe=576a0fc8f5) | Feb 23, 2023 |
| ASUSTek       | LEONITE                     | [2739b3325c](https://linux-hardware.org/?probe=2739b3325c) | Feb 23, 2023 |
| ASUSTek       | P5QL-E                      | [52c9ec67bf](https://linux-hardware.org/?probe=52c9ec67bf) | Feb 23, 2023 |
| ASRock        | B660M Pro RS                | [13560ab66d](https://linux-hardware.org/?probe=13560ab66d) | Feb 22, 2023 |
| ASUSTek       | PRIME H610M-R D4            | [2993295e62](https://linux-hardware.org/?probe=2993295e62) | Feb 22, 2023 |
| ASUSTek       | PRIME H610M-R D4            | [c23f2f53ed](https://linux-hardware.org/?probe=c23f2f53ed) | Feb 21, 2023 |
| Acer          | FIH57                       | [294e04e054](https://linux-hardware.org/?probe=294e04e054) | Feb 21, 2023 |
| VXL           | M6V90AI-VL                  | [935d6b4b24](https://linux-hardware.org/?probe=935d6b4b24) | Feb 21, 2023 |
| ASUSTek       | PRIME Z390-P                | [d81ff5358a](https://linux-hardware.org/?probe=d81ff5358a) | Feb 20, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [656629ffba](https://linux-hardware.org/?probe=656629ffba) | Feb 20, 2023 |
| ASUSTek       | H170-PRO                    | [011dc701c1](https://linux-hardware.org/?probe=011dc701c1) | Feb 20, 2023 |
| ASUSTek       | H81M-PLUS                   | [796ba78b54](https://linux-hardware.org/?probe=796ba78b54) | Feb 20, 2023 |
| ASRock        | 960GC-GS FX                 | [39718b8983](https://linux-hardware.org/?probe=39718b8983) | Feb 20, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [accbe9322f](https://linux-hardware.org/?probe=accbe9322f) | Feb 20, 2023 |
| Packard Be... | IMEDIA S3810                | [472db03bf8](https://linux-hardware.org/?probe=472db03bf8) | Feb 20, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [737c043ed7](https://linux-hardware.org/?probe=737c043ed7) | Feb 20, 2023 |
| Gigabyte      | B560M DS3H                  | [72891de86c](https://linux-hardware.org/?probe=72891de86c) | Feb 20, 2023 |
| ASUSTek       | H81M-PLUS                   | [86f16da5e8](https://linux-hardware.org/?probe=86f16da5e8) | Feb 19, 2023 |
| ASUSTek       | BT6130                      | [470ceee356](https://linux-hardware.org/?probe=470ceee356) | Feb 19, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [2af589c6e9](https://linux-hardware.org/?probe=2af589c6e9) | Feb 19, 2023 |
| Pegatron      | 2AB6                        | [537c2d1b64](https://linux-hardware.org/?probe=537c2d1b64) | Feb 18, 2023 |
| Dell          | 0X9M3X A04                  | [9b13a670c5](https://linux-hardware.org/?probe=9b13a670c5) | Feb 18, 2023 |
| ASUSTek       | PRIME A320M-K               | [105ea39c82](https://linux-hardware.org/?probe=105ea39c82) | Feb 18, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [a62c4f0fcd](https://linux-hardware.org/?probe=a62c4f0fcd) | Feb 18, 2023 |
| MSI           | Z170A KRAIT GAMING          | [27dcbbe1d7](https://linux-hardware.org/?probe=27dcbbe1d7) | Feb 18, 2023 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [0428793835](https://linux-hardware.org/?probe=0428793835) | Feb 18, 2023 |
| ASUSTek       | Rampage Formula             | [61fd1aefee](https://linux-hardware.org/?probe=61fd1aefee) | Feb 17, 2023 |
| ASUSTek       | P8Z77-V                     | [f8dca6a264](https://linux-hardware.org/?probe=f8dca6a264) | Feb 17, 2023 |
| HP            | 2820h                       | [552bdc9930](https://linux-hardware.org/?probe=552bdc9930) | Feb 17, 2023 |
| HP            | 1495                        | [6bc4b54027](https://linux-hardware.org/?probe=6bc4b54027) | Feb 16, 2023 |
| MSI           | Z97-G45 GAMING              | [c6a7d3a755](https://linux-hardware.org/?probe=c6a7d3a755) | Feb 16, 2023 |
| ASRock        | Q1900M                      | [2fc7d5968a](https://linux-hardware.org/?probe=2fc7d5968a) | Feb 16, 2023 |
| ASUSTek       | P5K                         | [7767ce777f](https://linux-hardware.org/?probe=7767ce777f) | Feb 16, 2023 |
| Gigabyte      | H270M-D3H-CF                | [7a58ceb644](https://linux-hardware.org/?probe=7a58ceb644) | Feb 15, 2023 |
| ASUSTek       | BT6130                      | [b0693958a6](https://linux-hardware.org/?probe=b0693958a6) | Feb 15, 2023 |
| Acer          | Veriton X2610G              | [22c65bbb88](https://linux-hardware.org/?probe=22c65bbb88) | Feb 15, 2023 |
| Supermicro    | X10DRG-Q                    | [5af331bc84](https://linux-hardware.org/?probe=5af331bc84) | Feb 15, 2023 |
| HP            | 3396                        | [fbff77d7cc](https://linux-hardware.org/?probe=fbff77d7cc) | Feb 14, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | [49f47896e6](https://linux-hardware.org/?probe=49f47896e6) | Feb 14, 2023 |
| HP            | 18E7                        | [b81cc64550](https://linux-hardware.org/?probe=b81cc64550) | Feb 14, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [34ad4bac16](https://linux-hardware.org/?probe=34ad4bac16) | Feb 13, 2023 |
| ASUSTek       | BT6130                      | [db3b191eb2](https://linux-hardware.org/?probe=db3b191eb2) | Feb 13, 2023 |
| ASUSTek       | M5A78L-M LX3                | [c7374801ac](https://linux-hardware.org/?probe=c7374801ac) | Feb 13, 2023 |
| ASUSTek       | H81M-K                      | [6fe888ea28](https://linux-hardware.org/?probe=6fe888ea28) | Feb 13, 2023 |
| ASRock        | Z370M Pro4                  | [6dfaa1ed56](https://linux-hardware.org/?probe=6dfaa1ed56) | Feb 12, 2023 |
| ASUSTek       | F2A55-M LK2                 | [01ab687841](https://linux-hardware.org/?probe=01ab687841) | Feb 12, 2023 |
| Gigabyte      | Z370 HD3P-CF                | [86ca7a4821](https://linux-hardware.org/?probe=86ca7a4821) | Feb 11, 2023 |
| HP            | 3031h                       | [f9a0848388](https://linux-hardware.org/?probe=f9a0848388) | Feb 11, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [2d776f8810](https://linux-hardware.org/?probe=2d776f8810) | Feb 11, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [7b6a31ec69](https://linux-hardware.org/?probe=7b6a31ec69) | Feb 11, 2023 |
| ASUSTek       | P5K                         | [9f8790812d](https://linux-hardware.org/?probe=9f8790812d) | Feb 11, 2023 |
| Lenovo        | 3098 SDK0J40705 WIN         | [6ada8eb627](https://linux-hardware.org/?probe=6ada8eb627) | Feb 10, 2023 |
| ASRock        | Z170 Extreme6+              | [9b9b84473b](https://linux-hardware.org/?probe=9b9b84473b) | Feb 10, 2023 |
| Intel         | JSL MRD                     | [5a876c1bb0](https://linux-hardware.org/?probe=5a876c1bb0) | Feb 10, 2023 |
| ASUSTek       | M4N78                       | [34ddf02a41](https://linux-hardware.org/?probe=34ddf02a41) | Feb 10, 2023 |
| HP            | 843C                        | [02ddbb64e8](https://linux-hardware.org/?probe=02ddbb64e8) | Feb 09, 2023 |
| MSI           | 2A9C                        | [1332640fbd](https://linux-hardware.org/?probe=1332640fbd) | Feb 09, 2023 |
| Gigabyte      | GA-MA78GM-S2H               | [bbaa8165e4](https://linux-hardware.org/?probe=bbaa8165e4) | Feb 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [69c30e6f7b](https://linux-hardware.org/?probe=69c30e6f7b) | Feb 08, 2023 |
| Dell          | 0Y5FXV A00                  | [692b7eab6b](https://linux-hardware.org/?probe=692b7eab6b) | Feb 08, 2023 |
| ASUSTek       | SABERTOOTH P67              | [1fdf18a3ed](https://linux-hardware.org/?probe=1fdf18a3ed) | Feb 08, 2023 |
| ASRock        | H310M-STX                   | [faadf8b29c](https://linux-hardware.org/?probe=faadf8b29c) | Feb 08, 2023 |
| MSI           | Z390-A PRO                  | [de25a58c23](https://linux-hardware.org/?probe=de25a58c23) | Feb 07, 2023 |
| MSI           | B550-A PRO                  | [cc856dafad](https://linux-hardware.org/?probe=cc856dafad) | Feb 07, 2023 |
| ASUSTek       | Rampage IV EXTREME          | [9a94af0f8a](https://linux-hardware.org/?probe=9a94af0f8a) | Feb 07, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [43c3e4d160](https://linux-hardware.org/?probe=43c3e4d160) | Feb 06, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [00006691a6](https://linux-hardware.org/?probe=00006691a6) | Feb 05, 2023 |
| Acer          | WG43M                       | [e463181f54](https://linux-hardware.org/?probe=e463181f54) | Feb 05, 2023 |
| MSI           | MS-7309                     | [46995d58eb](https://linux-hardware.org/?probe=46995d58eb) | Feb 05, 2023 |
| Intel         | DH55TC AAE70932-301         | [350458a94e](https://linux-hardware.org/?probe=350458a94e) | Feb 05, 2023 |
| HP            | 3397                        | [ea72001991](https://linux-hardware.org/?probe=ea72001991) | Feb 05, 2023 |
| ASRock        | 775Dual-VSTA                | [945a366595](https://linux-hardware.org/?probe=945a366595) | Feb 05, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [944149e350](https://linux-hardware.org/?probe=944149e350) | Feb 04, 2023 |
| MSI           | B550-A PRO                  | [55e2abbd96](https://linux-hardware.org/?probe=55e2abbd96) | Feb 04, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | [91a070c2aa](https://linux-hardware.org/?probe=91a070c2aa) | Feb 03, 2023 |
| Intel         | H61                         | [21fd40e0a1](https://linux-hardware.org/?probe=21fd40e0a1) | Feb 03, 2023 |
| MSI           | B550-A PRO                  | [dc4a285d49](https://linux-hardware.org/?probe=dc4a285d49) | Feb 03, 2023 |
| ASUSTek       | P5GDC                       | [6dbac14e8b](https://linux-hardware.org/?probe=6dbac14e8b) | Feb 03, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [fd8c9d9ccf](https://linux-hardware.org/?probe=fd8c9d9ccf) | Feb 03, 2023 |
| HP            | 834F                        | [394eb5f9cc](https://linux-hardware.org/?probe=394eb5f9cc) | Feb 02, 2023 |
| HP            | 834F                        | [9a4a1839d3](https://linux-hardware.org/?probe=9a4a1839d3) | Feb 02, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [1ca0a608f9](https://linux-hardware.org/?probe=1ca0a608f9) | Feb 02, 2023 |
| Acer          | Veriton M2631 V:1.0         | [28e1975b51](https://linux-hardware.org/?probe=28e1975b51) | Feb 02, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [09430385c6](https://linux-hardware.org/?probe=09430385c6) | Feb 02, 2023 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | [b792043acd](https://linux-hardware.org/?probe=b792043acd) | Feb 01, 2023 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | [48bccd4f38](https://linux-hardware.org/?probe=48bccd4f38) | Feb 01, 2023 |
| Pegatron      | 2A94                        | [58961a542f](https://linux-hardware.org/?probe=58961a542f) | Feb 01, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [f4e30fc177](https://linux-hardware.org/?probe=f4e30fc177) | Jan 31, 2023 |
| ASUSTek       | P5QL PRO                    | [77cc2bd640](https://linux-hardware.org/?probe=77cc2bd640) | Jan 31, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [3c8b3f4e7d](https://linux-hardware.org/?probe=3c8b3f4e7d) | Jan 30, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [3bdb934f29](https://linux-hardware.org/?probe=3bdb934f29) | Jan 30, 2023 |
| Intel         | B75                         | [6597bed6da](https://linux-hardware.org/?probe=6597bed6da) | Jan 29, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [e5f6f546d4](https://linux-hardware.org/?probe=e5f6f546d4) | Jan 29, 2023 |
| ASRock        | B460M Pro4                  | [7af163f694](https://linux-hardware.org/?probe=7af163f694) | Jan 29, 2023 |
| MSI           | P55-CD53                    | [7c46f17179](https://linux-hardware.org/?probe=7c46f17179) | Jan 29, 2023 |
| ASRock        | H610M-HVS                   | [2774d547be](https://linux-hardware.org/?probe=2774d547be) | Jan 29, 2023 |
| ASRock        | B460M Pro4                  | [37c0fb77f5](https://linux-hardware.org/?probe=37c0fb77f5) | Jan 29, 2023 |
| ASUSTek       | F2A55-M LK2                 | [8bf2fa8d9b](https://linux-hardware.org/?probe=8bf2fa8d9b) | Jan 28, 2023 |
| Dell          | 0HD5W2 A00                  | [890cad48c3](https://linux-hardware.org/?probe=890cad48c3) | Jan 28, 2023 |
| Gigabyte      | B450M DS3H-CF               | [8f6ea9ffff](https://linux-hardware.org/?probe=8f6ea9ffff) | Jan 28, 2023 |
| ASUSTek       | H110M-K                     | [73b3f84699](https://linux-hardware.org/?probe=73b3f84699) | Jan 28, 2023 |
| ASUSTek       | H61M-K                      | [312e07a824](https://linux-hardware.org/?probe=312e07a824) | Jan 28, 2023 |
| ASRock        | H61M-DGS                    | [825e70e660](https://linux-hardware.org/?probe=825e70e660) | Jan 27, 2023 |
| ASUSTek       | PRIME A320M-K               | [6f449734a9](https://linux-hardware.org/?probe=6f449734a9) | Jan 26, 2023 |
| Gigabyte      | Z370P D3-CF                 | [90f37ac742](https://linux-hardware.org/?probe=90f37ac742) | Jan 26, 2023 |
| Gigabyte      | Z370P D3-CF                 | [e524d7c4d9](https://linux-hardware.org/?probe=e524d7c4d9) | Jan 26, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [01e47b07a8](https://linux-hardware.org/?probe=01e47b07a8) | Jan 26, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [4ae098906f](https://linux-hardware.org/?probe=4ae098906f) | Jan 26, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [8128876a22](https://linux-hardware.org/?probe=8128876a22) | Jan 26, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [c216d513a0](https://linux-hardware.org/?probe=c216d513a0) | Jan 25, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [06b972165b](https://linux-hardware.org/?probe=06b972165b) | Jan 25, 2023 |
| ASRock        | H61M-DGS                    | [5672937ec6](https://linux-hardware.org/?probe=5672937ec6) | Jan 25, 2023 |
| ASUSTek       | PRIME B560M-A               | [78a1bfaac7](https://linux-hardware.org/?probe=78a1bfaac7) | Jan 25, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [596316a81c](https://linux-hardware.org/?probe=596316a81c) | Jan 25, 2023 |
| ASUSTek       | B150M-A/M.2                 | [edb16eafc7](https://linux-hardware.org/?probe=edb16eafc7) | Jan 25, 2023 |
| MSI           | Z390-A PRO                  | [28c31b639b](https://linux-hardware.org/?probe=28c31b639b) | Jan 25, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [3e1520340a](https://linux-hardware.org/?probe=3e1520340a) | Jan 25, 2023 |
| MSI           | Boston                      | [456d7782ad](https://linux-hardware.org/?probe=456d7782ad) | Jan 24, 2023 |
| MSI           | P55-CD53                    | [7c3a675f94](https://linux-hardware.org/?probe=7c3a675f94) | Jan 24, 2023 |
| ASRock        | Z87 Pro3                    | [0ab0dbb821](https://linux-hardware.org/?probe=0ab0dbb821) | Jan 23, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [996a0567b6](https://linux-hardware.org/?probe=996a0567b6) | Jan 23, 2023 |
| Packard Be... | EG43M                       | [92810508a2](https://linux-hardware.org/?probe=92810508a2) | Jan 23, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [d0f4730f71](https://linux-hardware.org/?probe=d0f4730f71) | Jan 23, 2023 |
| T-bao         | MINI PC V1.0                | [6d1c897198](https://linux-hardware.org/?probe=6d1c897198) | Jan 23, 2023 |
| ASRock        | H61M                        | [f5b1db73f7](https://linux-hardware.org/?probe=f5b1db73f7) | Jan 22, 2023 |
| HP            | 8433 11                     | [a5c598c4c5](https://linux-hardware.org/?probe=a5c598c4c5) | Jan 22, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [b919144e1c](https://linux-hardware.org/?probe=b919144e1c) | Jan 22, 2023 |
| ASRock        | G31M-S                      | [dbf8922f3a](https://linux-hardware.org/?probe=dbf8922f3a) | Jan 22, 2023 |
| MSI           | Boston                      | [34413408ce](https://linux-hardware.org/?probe=34413408ce) | Jan 22, 2023 |
| Dell          | 0YXT71 A02                  | [5d3b4c4823](https://linux-hardware.org/?probe=5d3b4c4823) | Jan 22, 2023 |
| ASUSTek       | P5KPL-AM EPU                | [0aa5260ed0](https://linux-hardware.org/?probe=0aa5260ed0) | Jan 22, 2023 |
| ASUSTek       | P5KPL-AM EPU                | [7389389089](https://linux-hardware.org/?probe=7389389089) | Jan 22, 2023 |
| ASRock        | X370 Pro4                   | [6a8cc962ad](https://linux-hardware.org/?probe=6a8cc962ad) | Jan 22, 2023 |
| ASRock        | B365 Pro4                   | [44fa1b3713](https://linux-hardware.org/?probe=44fa1b3713) | Jan 22, 2023 |
| Lenovo        | ThinkCentre M57e 7066W57    | [3ddcdbb616](https://linux-hardware.org/?probe=3ddcdbb616) | Jan 22, 2023 |
| Gigabyte      | Z77MX-D3H                   | [2142d5e771](https://linux-hardware.org/?probe=2142d5e771) | Jan 22, 2023 |
| Gigabyte      | Z77MX-D3H                   | [80d8c352b9](https://linux-hardware.org/?probe=80d8c352b9) | Jan 22, 2023 |
| HP            | 1497                        | [5f7e021023](https://linux-hardware.org/?probe=5f7e021023) | Jan 22, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [0bf19053f1](https://linux-hardware.org/?probe=0bf19053f1) | Jan 21, 2023 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [9229e3b2ae](https://linux-hardware.org/?probe=9229e3b2ae) | Jan 21, 2023 |
| ASUSTek       | P5KPL-AM EPU                | [62dc562b9e](https://linux-hardware.org/?probe=62dc562b9e) | Jan 21, 2023 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | [eb57bb7cd7](https://linux-hardware.org/?probe=eb57bb7cd7) | Jan 21, 2023 |
| ASUSTek       | H170I-PLUS D3               | [b8d373b07e](https://linux-hardware.org/?probe=b8d373b07e) | Jan 21, 2023 |
| ASRock        | H61M-VG3                    | [c9d6e1cbb1](https://linux-hardware.org/?probe=c9d6e1cbb1) | Jan 21, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [3432d7c1f5](https://linux-hardware.org/?probe=3432d7c1f5) | Jan 20, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [2e73bc84e7](https://linux-hardware.org/?probe=2e73bc84e7) | Jan 20, 2023 |
| ASUSTek       | P7P55D-E                    | [6bc203c6fd](https://linux-hardware.org/?probe=6bc203c6fd) | Jan 19, 2023 |
| ASUSTek       | Z77-A                       | [10081492a7](https://linux-hardware.org/?probe=10081492a7) | Jan 19, 2023 |
| ASUSTek       | PRIME H610M-R D4            | [2e54ccac4d](https://linux-hardware.org/?probe=2e54ccac4d) | Jan 19, 2023 |
| ASUSTek       | PRIME H610M-R D4            | [763f4cb45f](https://linux-hardware.org/?probe=763f4cb45f) | Jan 18, 2023 |
| ASUSTek       | PRIME A320M-K               | [dcf9186db1](https://linux-hardware.org/?probe=dcf9186db1) | Jan 18, 2023 |
| ASRock        | G31M-S                      | [d3aa4e7eea](https://linux-hardware.org/?probe=d3aa4e7eea) | Jan 18, 2023 |
| MSI           | Z170A GAMING M7             | [d58a30b560](https://linux-hardware.org/?probe=d58a30b560) | Jan 18, 2023 |
| MSI           | B150M PRO-VDH               | [4e8759fda2](https://linux-hardware.org/?probe=4e8759fda2) | Jan 18, 2023 |
| ASRock        | Z170 Gaming K4              | [44a3d49ef1](https://linux-hardware.org/?probe=44a3d49ef1) | Jan 18, 2023 |
| MSI           | B150M PRO-VDH               | [d1310959ea](https://linux-hardware.org/?probe=d1310959ea) | Jan 17, 2023 |
| Lenovo        | ThinkStation C20 4263BA7    | [52c1a6c197](https://linux-hardware.org/?probe=52c1a6c197) | Jan 17, 2023 |
| Gigabyte      | B450M DS3H-CF               | [b9f958e5c4](https://linux-hardware.org/?probe=b9f958e5c4) | Jan 17, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [d78fd14781](https://linux-hardware.org/?probe=d78fd14781) | Jan 17, 2023 |
| Unknown       | T3 MRD                      | [df73fafeb7](https://linux-hardware.org/?probe=df73fafeb7) | Jan 17, 2023 |
| ASUSTek       | Rampage IV EXTREME          | [4d4b18a5b3](https://linux-hardware.org/?probe=4d4b18a5b3) | Jan 16, 2023 |
| ASUSTek       | PRIME B460M-A               | [25cbbcfc98](https://linux-hardware.org/?probe=25cbbcfc98) | Jan 16, 2023 |
| ASUSTek       | P5Q PRO TURBO               | [1dd0101330](https://linux-hardware.org/?probe=1dd0101330) | Jan 16, 2023 |
| Dell          | 0WMJ54 A01                  | [fece850cae](https://linux-hardware.org/?probe=fece850cae) | Jan 15, 2023 |
| Gigabyte      | Z97X-Gaming G1              | [58c875e5d5](https://linux-hardware.org/?probe=58c875e5d5) | Jan 15, 2023 |
| Gigabyte      | Z370P D3-CF                 | [084cfebfdb](https://linux-hardware.org/?probe=084cfebfdb) | Jan 15, 2023 |
| Gigabyte      | Z370P D3-CF                 | [f8c56a73c0](https://linux-hardware.org/?probe=f8c56a73c0) | Jan 15, 2023 |
| Gigabyte      | X570S AERO G                | [d30e9b41ef](https://linux-hardware.org/?probe=d30e9b41ef) | Jan 15, 2023 |
| Gigabyte      | X570S AERO G                | [a265db8e50](https://linux-hardware.org/?probe=a265db8e50) | Jan 15, 2023 |
| ASUSTek       | TUF Gaming H470-PRO         | [6d67c981b3](https://linux-hardware.org/?probe=6d67c981b3) | Jan 15, 2023 |
| ASRock        | 775Dual-VSTA                | [7b8818c038](https://linux-hardware.org/?probe=7b8818c038) | Jan 15, 2023 |
| ASRock        | 775Dual-VSTA                | [74dfb9a261](https://linux-hardware.org/?probe=74dfb9a261) | Jan 15, 2023 |
| Lenovo        | SDK0F82993 WIN              | [48f294dfb4](https://linux-hardware.org/?probe=48f294dfb4) | Jan 15, 2023 |
| Pegatron      | 2AD5                        | [d41fde4498](https://linux-hardware.org/?probe=d41fde4498) | Jan 15, 2023 |
| Dell          | 0D24M8 A01                  | [d4cc07d2d2](https://linux-hardware.org/?probe=d4cc07d2d2) | Jan 14, 2023 |
| HP            | 8753                        | [5cdf3ef632](https://linux-hardware.org/?probe=5cdf3ef632) | Jan 14, 2023 |
| MSI           | Z370 GAMING PRO CARBON      | [05f1e26e96](https://linux-hardware.org/?probe=05f1e26e96) | Jan 13, 2023 |
| Dell          | 0WG261                      | [c994d9e8ee](https://linux-hardware.org/?probe=c994d9e8ee) | Jan 13, 2023 |
| ASUSTek       | H110M-R                     | [1318c97f67](https://linux-hardware.org/?probe=1318c97f67) | Jan 13, 2023 |
| ASUSTek       | H110M-R                     | [a86e03551c](https://linux-hardware.org/?probe=a86e03551c) | Jan 13, 2023 |
| Dell          | 0WG261                      | [5d1fe40a1f](https://linux-hardware.org/?probe=5d1fe40a1f) | Jan 13, 2023 |
| ASUSTek       | P8Z77-V LX2                 | [64808b5735](https://linux-hardware.org/?probe=64808b5735) | Jan 12, 2023 |
| Pegatron      | 2ACF                        | [611b2fb2a3](https://linux-hardware.org/?probe=611b2fb2a3) | Jan 12, 2023 |
| AOpen         | D1007 0BBA                  | [63a1413fa3](https://linux-hardware.org/?probe=63a1413fa3) | Jan 12, 2023 |
| Gigabyte      | Z790 AERO G                 | [0d6b77da1a](https://linux-hardware.org/?probe=0d6b77da1a) | Jan 11, 2023 |
| ASUSTek       | PRIME B360M-A               | [75584dc48c](https://linux-hardware.org/?probe=75584dc48c) | Jan 11, 2023 |
| Acer          | Veriton X2640G V:1.0        | [0daf81fe54](https://linux-hardware.org/?probe=0daf81fe54) | Jan 11, 2023 |
| HP            | 8767 A                      | [7b2c61c215](https://linux-hardware.org/?probe=7b2c61c215) | Jan 11, 2023 |
| ASUSTek       | BT6130                      | [53c9ec0145](https://linux-hardware.org/?probe=53c9ec0145) | Jan 10, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | [71f6d7912a](https://linux-hardware.org/?probe=71f6d7912a) | Jan 10, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [0d0a198245](https://linux-hardware.org/?probe=0d0a198245) | Jan 10, 2023 |
| ASRockRack    | EPC602D8A                   | [2d1d53f993](https://linux-hardware.org/?probe=2d1d53f993) | Jan 10, 2023 |
| MSI           | B450M MORTAR MAX            | [36530dbc41](https://linux-hardware.org/?probe=36530dbc41) | Jan 10, 2023 |
| MSI           | H310M PRO-D                 | [1ba0a170aa](https://linux-hardware.org/?probe=1ba0a170aa) | Jan 09, 2023 |
| MSI           | MS-7378                     | [965cd11e84](https://linux-hardware.org/?probe=965cd11e84) | Jan 09, 2023 |
| MSI           | Z77A-GD65                   | [f4b0c86cfa](https://linux-hardware.org/?probe=f4b0c86cfa) | Jan 09, 2023 |
| MSI           | MAG B550M MORTAR            | [1549344aef](https://linux-hardware.org/?probe=1549344aef) | Jan 09, 2023 |
| ASRock        | H87 Performance             | [8e1b7a9033](https://linux-hardware.org/?probe=8e1b7a9033) | Jan 09, 2023 |
| MSI           | H310M PRO-D                 | [e5a8783118](https://linux-hardware.org/?probe=e5a8783118) | Jan 09, 2023 |
| ASRock        | 980DE3/U3S3                 | [92d7b143d8](https://linux-hardware.org/?probe=92d7b143d8) | Jan 09, 2023 |
| ASRock        | X370 Gaming K4              | [0ed2f96ba8](https://linux-hardware.org/?probe=0ed2f96ba8) | Jan 09, 2023 |
| ASUSTek       | M5A97 R2.0                  | [ca7597c4fb](https://linux-hardware.org/?probe=ca7597c4fb) | Jan 08, 2023 |
| Gigabyte      | 990XA-UD3                   | [1c85ed2f4b](https://linux-hardware.org/?probe=1c85ed2f4b) | Jan 08, 2023 |
| Gigabyte      | A520M S2H                   | [a303af0bcf](https://linux-hardware.org/?probe=a303af0bcf) | Jan 08, 2023 |
| Gigabyte      | X570S AERO G                | [75def9e004](https://linux-hardware.org/?probe=75def9e004) | Jan 07, 2023 |
| Acer          | Veriton N2620G              | [6345424cff](https://linux-hardware.org/?probe=6345424cff) | Jan 07, 2023 |
| Gigabyte      | X570S AERO G                | [c5a401b596](https://linux-hardware.org/?probe=c5a401b596) | Jan 07, 2023 |
| ASRock        | Q1900-ITX                   | [ac7df499e8](https://linux-hardware.org/?probe=ac7df499e8) | Jan 07, 2023 |
| HP            | 8399                        | [eccd5189f5](https://linux-hardware.org/?probe=eccd5189f5) | Jan 07, 2023 |
| HP            | 89D8 SMVB                   | [dac20769fc](https://linux-hardware.org/?probe=dac20769fc) | Jan 07, 2023 |
| Acer          | Veriton M2631G V:1.0        | [ebbcc0dda8](https://linux-hardware.org/?probe=ebbcc0dda8) | Jan 07, 2023 |
| HP            | ProLiant MicroServer        | [4bdffcda7f](https://linux-hardware.org/?probe=4bdffcda7f) | Jan 07, 2023 |
| Intel         | DH61DL AAG14066-205         | [81431f1578](https://linux-hardware.org/?probe=81431f1578) | Jan 06, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [ce4648337e](https://linux-hardware.org/?probe=ce4648337e) | Jan 05, 2023 |
| Acer          | Veriton M2631G V:1.0        | [ddeffc27a7](https://linux-hardware.org/?probe=ddeffc27a7) | Jan 05, 2023 |
| Gigabyte      | B560M DS3H                  | [667c8405f0](https://linux-hardware.org/?probe=667c8405f0) | Jan 05, 2023 |
| ASRock        | H410M-HVS                   | [922db531b3](https://linux-hardware.org/?probe=922db531b3) | Jan 05, 2023 |
| Intel         | B75                         | [bb046d2540](https://linux-hardware.org/?probe=bb046d2540) | Jan 04, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [7655f77ada](https://linux-hardware.org/?probe=7655f77ada) | Jan 04, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [0e9393e884](https://linux-hardware.org/?probe=0e9393e884) | Jan 03, 2023 |
| ASRock        | N68C-S UCC                  | [31dfc11401](https://linux-hardware.org/?probe=31dfc11401) | Jan 03, 2023 |
| ASRock        | N68C-S UCC                  | [1497921a99](https://linux-hardware.org/?probe=1497921a99) | Jan 03, 2023 |
| Dell          | 0VHWTR A02                  | [0d9d6203e1](https://linux-hardware.org/?probe=0d9d6203e1) | Jan 03, 2023 |
| ASRock        | H77M                        | [b7f415926b](https://linux-hardware.org/?probe=b7f415926b) | Jan 03, 2023 |
| ASRock        | H77M                        | [82c399688f](https://linux-hardware.org/?probe=82c399688f) | Jan 03, 2023 |
| ASRock        | FM2A55M-VG3+                | [741f0d79a1](https://linux-hardware.org/?probe=741f0d79a1) | Jan 03, 2023 |
| Pegatron      | Benicia                     | [008e5d125e](https://linux-hardware.org/?probe=008e5d125e) | Jan 03, 2023 |
| Pegatron      | Benicia                     | [0d47a13713](https://linux-hardware.org/?probe=0d47a13713) | Jan 03, 2023 |
| Pegatron      | Benicia                     | [25466113c1](https://linux-hardware.org/?probe=25466113c1) | Jan 02, 2023 |
| MSI           | H310M PRO-D                 | [27482bbe30](https://linux-hardware.org/?probe=27482bbe30) | Jan 02, 2023 |
| Dell          | 0RF703                      | [66180b5fdf](https://linux-hardware.org/?probe=66180b5fdf) | Jan 02, 2023 |
| MSI           | B250M PRO-VD                | [d94e8b5637](https://linux-hardware.org/?probe=d94e8b5637) | Jan 02, 2023 |
| ASRock        | B450 Steel Legend           | [b953257b12](https://linux-hardware.org/?probe=b953257b12) | Jan 01, 2023 |
| ASUSTek       | P5GD2-VM                    | [13ccd15493](https://linux-hardware.org/?probe=13ccd15493) | Jan 01, 2023 |
| Intel         | DH61DL AAG14066-205         | [8f923bc065](https://linux-hardware.org/?probe=8f923bc065) | Jan 01, 2023 |
| HP            | 82B4                        | [4e2d86906f](https://linux-hardware.org/?probe=4e2d86906f) | Jan 01, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [afdda0ad31](https://linux-hardware.org/?probe=afdda0ad31) | Dec 31, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [3659d7377d](https://linux-hardware.org/?probe=3659d7377d) | Dec 31, 2022 |
| BESSTAR Te... | C-J34 Pro                   | [1b54a52c3c](https://linux-hardware.org/?probe=1b54a52c3c) | Dec 30, 2022 |
| ASUSTek       | H81M-A                      | [10f0b28589](https://linux-hardware.org/?probe=10f0b28589) | Dec 29, 2022 |
| HP            | 0AE8h                       | [b23a6da065](https://linux-hardware.org/?probe=b23a6da065) | Dec 29, 2022 |
| MSI           | Z390-A PRO                  | [3a3375e173](https://linux-hardware.org/?probe=3a3375e173) | Dec 29, 2022 |
| HP            | 8399                        | [8a4ef9ab88](https://linux-hardware.org/?probe=8a4ef9ab88) | Dec 29, 2022 |
| ASUSTek       | H110M-K                     | [4dab06b05f](https://linux-hardware.org/?probe=4dab06b05f) | Dec 29, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | [d0969c6a4c](https://linux-hardware.org/?probe=d0969c6a4c) | Dec 28, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | [8a4dce4662](https://linux-hardware.org/?probe=8a4dce4662) | Dec 28, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6297565fda](https://linux-hardware.org/?probe=6297565fda) | Dec 28, 2022 |
| Pegatron      | 2AB6                        | [742c9ebcca](https://linux-hardware.org/?probe=742c9ebcca) | Dec 28, 2022 |
| Pegatron      | 2AB6                        | [9e95c7e7c7](https://linux-hardware.org/?probe=9e95c7e7c7) | Dec 28, 2022 |
| ASUSTek       | P8Z77-V PRO                 | [79427500b5](https://linux-hardware.org/?probe=79427500b5) | Dec 28, 2022 |
| ASRock        | 4CoreDual-SATA2             | [05ae1afd3f](https://linux-hardware.org/?probe=05ae1afd3f) | Dec 28, 2022 |
| HP            | 0AE8h                       | [c1bd1ff073](https://linux-hardware.org/?probe=c1bd1ff073) | Dec 27, 2022 |
| Unknown       | Unknown                     | [ccce0caf7e](https://linux-hardware.org/?probe=ccce0caf7e) | Dec 27, 2022 |
| MSI           | Z270 GAMING PRO CARBON      | [f422489705](https://linux-hardware.org/?probe=f422489705) | Dec 27, 2022 |
| Dell          | 0PTTT9 A01                  | [78512365ca](https://linux-hardware.org/?probe=78512365ca) | Dec 26, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [bc68280036](https://linux-hardware.org/?probe=bc68280036) | Dec 26, 2022 |
| ASUSTek       | B85M-E/DASH                 | [b2acfa6e70](https://linux-hardware.org/?probe=b2acfa6e70) | Dec 26, 2022 |
| ASUSTek       | B85M-E/DASH                 | [59e6ec4132](https://linux-hardware.org/?probe=59e6ec4132) | Dec 26, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [5ce1ea886f](https://linux-hardware.org/?probe=5ce1ea886f) | Dec 26, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [f56ea263a2](https://linux-hardware.org/?probe=f56ea263a2) | Dec 26, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [7e46b9fd5b](https://linux-hardware.org/?probe=7e46b9fd5b) | Dec 26, 2022 |
| MSI           | Boston                      | [5ffbd4e9a5](https://linux-hardware.org/?probe=5ffbd4e9a5) | Dec 25, 2022 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [384d09ccdb](https://linux-hardware.org/?probe=384d09ccdb) | Dec 25, 2022 |
| Dell          | 0DN075                      | [9fd08be389](https://linux-hardware.org/?probe=9fd08be389) | Dec 25, 2022 |
| ASRock        | N3700-ITX                   | [dc3f0d5062](https://linux-hardware.org/?probe=dc3f0d5062) | Dec 25, 2022 |
| AMI           | Cherry Trail FFD            | [7070bf387d](https://linux-hardware.org/?probe=7070bf387d) | Dec 24, 2022 |
| HP            | ProLiant MicroServer        | [b95892f2dc](https://linux-hardware.org/?probe=b95892f2dc) | Dec 24, 2022 |
| Foxconn       | 2AA9                        | [07650be639](https://linux-hardware.org/?probe=07650be639) | Dec 24, 2022 |
| ASRock        | B450 Pro4                   | [70ff83271a](https://linux-hardware.org/?probe=70ff83271a) | Dec 24, 2022 |
| ASRock        | X570 Steel Legend           | [7b79249b18](https://linux-hardware.org/?probe=7b79249b18) | Dec 23, 2022 |
| ASUSTek       | M5A78L/USB3                 | [348c431775](https://linux-hardware.org/?probe=348c431775) | Dec 23, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [568df9daf7](https://linux-hardware.org/?probe=568df9daf7) | Dec 23, 2022 |
| Lenovo        | ThinkCentre M71e 3129C3G    | [cb9f99f1cf](https://linux-hardware.org/?probe=cb9f99f1cf) | Dec 23, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [9e19c2db67](https://linux-hardware.org/?probe=9e19c2db67) | Dec 23, 2022 |
| ASRock        | FM2A88M-HD+                 | [18b83ae613](https://linux-hardware.org/?probe=18b83ae613) | Dec 22, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [ec808658f8](https://linux-hardware.org/?probe=ec808658f8) | Dec 22, 2022 |
| Acer          | Aspire M3920                | [803cd5d8f9](https://linux-hardware.org/?probe=803cd5d8f9) | Dec 22, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [fc162d4cb2](https://linux-hardware.org/?probe=fc162d4cb2) | Dec 21, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [1cdb02c6db](https://linux-hardware.org/?probe=1cdb02c6db) | Dec 21, 2022 |
| HP            | 8906 SMVB                   | [c7b2f48d96](https://linux-hardware.org/?probe=c7b2f48d96) | Dec 20, 2022 |
| ASUSTek       | PRIME A320M-K               | [3b38fc673c](https://linux-hardware.org/?probe=3b38fc673c) | Dec 19, 2022 |
| Gigabyte      | 970-GAMING                  | [cf93a75cf0](https://linux-hardware.org/?probe=cf93a75cf0) | Dec 19, 2022 |
| MSI           | X470 GAMING PLUS            | [44cdfa03bf](https://linux-hardware.org/?probe=44cdfa03bf) | Dec 19, 2022 |
| Gigabyte      | B75M-D3H                    | [ad506ad64e](https://linux-hardware.org/?probe=ad506ad64e) | Dec 19, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [87907abff7](https://linux-hardware.org/?probe=87907abff7) | Dec 19, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [831f650b05](https://linux-hardware.org/?probe=831f650b05) | Dec 19, 2022 |
| HP            | 18E7                        | [9f601a9f1a](https://linux-hardware.org/?probe=9f601a9f1a) | Dec 19, 2022 |
| MSI           | B250M PRO-VDH               | [14ea50f3b2](https://linux-hardware.org/?probe=14ea50f3b2) | Dec 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | [2d046f9339](https://linux-hardware.org/?probe=2d046f9339) | Dec 18, 2022 |
| Intel         | H55                         | [a5033f178f](https://linux-hardware.org/?probe=a5033f178f) | Dec 18, 2022 |
| ASUSTek       | P7H55D-M EVO                | [1e294ecd38](https://linux-hardware.org/?probe=1e294ecd38) | Dec 18, 2022 |
| ASUSTek       | F1A55-M LE                  | [c2db38b403](https://linux-hardware.org/?probe=c2db38b403) | Dec 17, 2022 |
| ASUSTek       | P8H77-M LE                  | [d9eba2d52f](https://linux-hardware.org/?probe=d9eba2d52f) | Dec 17, 2022 |
| MSI           | MS-B1711                    | [a5b142e258](https://linux-hardware.org/?probe=a5b142e258) | Dec 17, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [90912f0bba](https://linux-hardware.org/?probe=90912f0bba) | Dec 16, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [25ba267a65](https://linux-hardware.org/?probe=25ba267a65) | Dec 16, 2022 |
| Acer          | Veriton X2631G V:1.0        | [14d39a67c2](https://linux-hardware.org/?probe=14d39a67c2) | Dec 16, 2022 |
| Acer          | Veriton X2631G V:1.0        | [fc99e84afd](https://linux-hardware.org/?probe=fc99e84afd) | Dec 16, 2022 |
| MSI           | AM1I                        | [0ebd00e848](https://linux-hardware.org/?probe=0ebd00e848) | Dec 16, 2022 |
| MSI           | AM1I                        | [97dfa5ebf8](https://linux-hardware.org/?probe=97dfa5ebf8) | Dec 16, 2022 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | [1d1a225cde](https://linux-hardware.org/?probe=1d1a225cde) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [587fac961e](https://linux-hardware.org/?probe=587fac961e) | Dec 15, 2022 |
| Dell          | 0XJ8C4 A00                  | [c7ce3d7180](https://linux-hardware.org/?probe=c7ce3d7180) | Dec 14, 2022 |
| Dell          | 0XJ8C4 A00                  | [b136ecfff3](https://linux-hardware.org/?probe=b136ecfff3) | Dec 14, 2022 |
| HP            | 843C                        | [e647aa1207](https://linux-hardware.org/?probe=e647aa1207) | Dec 14, 2022 |
| HP            | 2AF7                        | [089612dee6](https://linux-hardware.org/?probe=089612dee6) | Dec 14, 2022 |
| ASRock        | B450M-HDV R4.0              | [b4d843d4c2](https://linux-hardware.org/?probe=b4d843d4c2) | Dec 14, 2022 |
| HP            | 2AF7                        | [2c6c08c8b8](https://linux-hardware.org/?probe=2c6c08c8b8) | Dec 14, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [39d58ec9aa](https://linux-hardware.org/?probe=39d58ec9aa) | Dec 13, 2022 |
| Intel         | DB75EN AAG39650-400         | [72b3306c33](https://linux-hardware.org/?probe=72b3306c33) | Dec 13, 2022 |
| Foxconn       | 2ABF                        | [48f3c01650](https://linux-hardware.org/?probe=48f3c01650) | Dec 12, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [3d835ed57d](https://linux-hardware.org/?probe=3d835ed57d) | Dec 12, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [c62c8e69b0](https://linux-hardware.org/?probe=c62c8e69b0) | Dec 12, 2022 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [9a73e431ee](https://linux-hardware.org/?probe=9a73e431ee) | Dec 12, 2022 |
| ASUSTek       | PRIME B450M-K               | [2212bad256](https://linux-hardware.org/?probe=2212bad256) | Dec 12, 2022 |
| ASUSTek       | PRIME B450M-K               | [20cb7a525a](https://linux-hardware.org/?probe=20cb7a525a) | Dec 12, 2022 |
| ASUSTek       | LEUCITE3                    | [b29a792d69](https://linux-hardware.org/?probe=b29a792d69) | Dec 12, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [c5501c208c](https://linux-hardware.org/?probe=c5501c208c) | Dec 11, 2022 |
| MSI           | Boston                      | [4cc25e826f](https://linux-hardware.org/?probe=4cc25e826f) | Dec 11, 2022 |
| Unknown       | T3 MRD                      | [c2cb5ad16b](https://linux-hardware.org/?probe=c2cb5ad16b) | Dec 11, 2022 |
| Gigabyte      | X570S AERO G                | [118d4ebca0](https://linux-hardware.org/?probe=118d4ebca0) | Dec 11, 2022 |
| Intel         | DB75EN AAG39650-400         | [01decbbb6d](https://linux-hardware.org/?probe=01decbbb6d) | Dec 10, 2022 |
| ASUSTek       | PRIME X570-P                | [6b00f35a38](https://linux-hardware.org/?probe=6b00f35a38) | Dec 10, 2022 |
| Lenovo        | SHARKBAY NOK                | [746c717d34](https://linux-hardware.org/?probe=746c717d34) | Dec 10, 2022 |
| Unknown       | Unknown                     | [41ff90c88a](https://linux-hardware.org/?probe=41ff90c88a) | Dec 09, 2022 |
| ASRock        | 970 Extreme3 R2.0           | [d52b5053b2](https://linux-hardware.org/?probe=d52b5053b2) | Dec 09, 2022 |
| Acer          | Veriton N2620G              | [2c4bd5a093](https://linux-hardware.org/?probe=2c4bd5a093) | Dec 08, 2022 |
| Dell          | 0RM5DR A00                  | [cd67b584bb](https://linux-hardware.org/?probe=cd67b584bb) | Dec 07, 2022 |
| ASRock        | H410M-HVS                   | [a8aa92bfed](https://linux-hardware.org/?probe=a8aa92bfed) | Dec 07, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [768329e263](https://linux-hardware.org/?probe=768329e263) | Dec 07, 2022 |
| ASRock        | Z170 Extreme7+              | [15f86800ee](https://linux-hardware.org/?probe=15f86800ee) | Dec 07, 2022 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [9d8dee4e41](https://linux-hardware.org/?probe=9d8dee4e41) | Dec 07, 2022 |
| MAXSUN        | MS-TZZ A320M.2-VH           | [c3fc86b5d4](https://linux-hardware.org/?probe=c3fc86b5d4) | Dec 06, 2022 |
| ASRock        | A320M-DGS                   | [fd3597e4bf](https://linux-hardware.org/?probe=fd3597e4bf) | Dec 06, 2022 |
| HP            | 843C                        | [278cbd2708](https://linux-hardware.org/?probe=278cbd2708) | Dec 06, 2022 |
| Gigabyte      | Z370P D3-CF                 | [13ac8bc162](https://linux-hardware.org/?probe=13ac8bc162) | Dec 06, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [664d064b07](https://linux-hardware.org/?probe=664d064b07) | Dec 06, 2022 |
| HP            | 0A64h                       | [58658d8b61](https://linux-hardware.org/?probe=58658d8b61) | Dec 06, 2022 |
| MSI           | MS-B1711                    | [1fbaa02605](https://linux-hardware.org/?probe=1fbaa02605) | Dec 05, 2022 |
| MSI           | Boston                      | [fd25ac3a2e](https://linux-hardware.org/?probe=fd25ac3a2e) | Dec 05, 2022 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [d0230b5c69](https://linux-hardware.org/?probe=d0230b5c69) | Dec 05, 2022 |
| Acer          | Aspire TC-885 V:1.1         | [73d037e031](https://linux-hardware.org/?probe=73d037e031) | Dec 05, 2022 |
| MSI           | B450M BAZOOKA PLUS          | [dc890ad363](https://linux-hardware.org/?probe=dc890ad363) | Dec 03, 2022 |
| ASUSTek       | PRIME A320M-K               | [84bc78ebb6](https://linux-hardware.org/?probe=84bc78ebb6) | Dec 03, 2022 |
| Acer          | Aspire X3950                | [96044c1932](https://linux-hardware.org/?probe=96044c1932) | Dec 03, 2022 |
| MSI           | B450M BAZOOKA PLUS          | [a087ddb18f](https://linux-hardware.org/?probe=a087ddb18f) | Dec 03, 2022 |
| Pegatron      | 2ACF                        | [f2d1d7fb3d](https://linux-hardware.org/?probe=f2d1d7fb3d) | Dec 03, 2022 |
| MSI           | X99S SLI PLUS               | [03a2e66a94](https://linux-hardware.org/?probe=03a2e66a94) | Dec 03, 2022 |
| ASUSTek       | PRIME A320M-K               | [7d42d3210f](https://linux-hardware.org/?probe=7d42d3210f) | Dec 03, 2022 |
| HP            | 2B52                        | [e2e8bdd4f6](https://linux-hardware.org/?probe=e2e8bdd4f6) | Dec 03, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [dc233f857f](https://linux-hardware.org/?probe=dc233f857f) | Dec 03, 2022 |
| Gigabyte      | B75M-D2V                    | [ee17f7d657](https://linux-hardware.org/?probe=ee17f7d657) | Dec 02, 2022 |
| MSI           | Z170A GAMING M3             | [e4fd5dfa0e](https://linux-hardware.org/?probe=e4fd5dfa0e) | Dec 01, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [f8a7663037](https://linux-hardware.org/?probe=f8a7663037) | Dec 01, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Italy/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 381      | 12.45%  |
| Ubuntu 18.04                 | 242      | 7.91%   |
| Ubuntu 22.04                 | 151      | 4.93%   |
| OpenMandriva 4.2             | 106      | 3.46%   |
| OpenMandriva 4.3             | 83       | 2.71%   |
| Arch Rolling                 | 77       | 2.52%   |
| Debian 11                    | 64       | 2.09%   |
| Linux Mint 21.1              | 58       | 1.9%    |
| Ubuntu 20.10                 | 51       | 1.67%   |
| Ubuntu 19.04                 | 47       | 1.54%   |
| Ubuntu 22.10                 | 45       | 1.47%   |
| OpenMandriva 23.01           | 45       | 1.47%   |
| KDE neon 20.04               | 43       | 1.41%   |
| Fedora 36                    | 43       | 1.41%   |
| Zorin 16                     | 42       | 1.37%   |
| Ubuntu 19.10                 | 42       | 1.37%   |
| Linux Mint 20.3              | 41       | 1.34%   |
| Xubuntu 20.04                | 37       | 1.21%   |
| Manjaro                      | 37       | 1.21%   |
| Arch                         | 36       | 1.18%   |
| Pop!_OS 22.04                | 35       | 1.14%   |
| Xubuntu 18.04                | 34       | 1.11%   |
| Linux Mint 21                | 34       | 1.11%   |
| OpenMandriva 23.03           | 33       | 1.08%   |
| ROSA R10                     | 32       | 1.05%   |
| Ubuntu 21.10                 | 31       | 1.01%   |
| Ubuntu 21.04                 | 31       | 1.01%   |
| Debian 10                    | 31       | 1.01%   |
| Fedora 38                    | 27       | 0.88%   |
| Linux Mint 19.3              | 26       | 0.85%   |
| Kubuntu 20.04                | 26       | 0.85%   |
| EndeavourOS Rolling          | 26       | 0.85%   |
| Ubuntu 18.10                 | 24       | 0.78%   |
| Linux Mint 20.2              | 23       | 0.75%   |
| Linux Mint 20.1              | 22       | 0.72%   |
| Linux Mint 20                | 22       | 0.72%   |
| openSUSE Tumbleweed-XXXXXXXX | 21       | 0.69%   |
| Kubuntu 22.04                | 21       | 0.69%   |
| Fedora 37                    | 21       | 0.69%   |
| Zorin 15                     | 20       | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 1021     | 35.48%  |
| OpenMandriva  | 311      | 10.81%  |
| Linux Mint    | 237      | 8.23%   |
| Fedora        | 145      | 5.04%   |
| Debian        | 133      | 4.62%   |
| Xubuntu       | 111      | 3.86%   |
| Arch          | 110      | 3.82%   |
| ROSA          | 93       | 3.23%   |
| Manjaro       | 83       | 2.88%   |
| Pop!_OS       | 80       | 2.78%   |
| Kubuntu       | 72       | 2.5%    |
| KDE neon      | 69       | 2.4%    |
| Zorin         | 66       | 2.29%   |
| Ubuntu MATE   | 33       | 1.15%   |
| EndeavourOS   | 30       | 1.04%   |
| Lubuntu       | 29       | 1.01%   |
| openSUSE      | 27       | 0.94%   |
| Ubuntu Unity  | 19       | 0.66%   |
| Elementary    | 16       | 0.56%   |
| BlackPanther  | 15       | 0.52%   |
| Clear Linux   | 14       | 0.49%   |
| ArcoLinux     | 14       | 0.49%   |
| LMDE          | 13       | 0.45%   |
| Gentoo        | 11       | 0.38%   |
| MX            | 10       | 0.35%   |
| Garuda Linux  | 10       | 0.35%   |
| Endless       | 10       | 0.35%   |
| Peppermint    | 9        | 0.31%   |
| Ubuntu Studio | 7        | 0.24%   |
| Nobara        | 7        | 0.24%   |
| Slackware     | 5        | 0.17%   |
| Kali          | 5        | 0.17%   |
| Xero          | 4        | 0.14%   |
| Q4OS          | 4        | 0.14%   |
| LinuxFX       | 4        | 0.14%   |
| CentOS        | 4        | 0.14%   |
| Rocky Linux   | 3        | 0.1%    |
| Parrot        | 3        | 0.1%    |
| NixOS         | 3        | 0.1%    |
| blendOS       | 3        | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002        | 104      | 3.03%   |
| 5.16.7-desktop-1omv4003         | 80       | 2.33%   |
| 5.15.0-52-generic               | 58       | 1.69%   |
| 5.4.0-42-generic                | 52       | 1.51%   |
| 5.15.0-56-generic               | 46       | 1.34%   |
| 5.4.0-52-generic                | 43       | 1.25%   |
| 6.1.1-desktop-1omv2290          | 37       | 1.08%   |
| 6.2.6-desktop-1omv2390          | 34       | 0.99%   |
| 5.15.0-47-generic               | 33       | 0.96%   |
| 5.4.0-58-generic                | 25       | 0.73%   |
| 5.15.0-58-generic               | 25       | 0.73%   |
| 5.4.0-48-generic                | 24       | 0.7%    |
| 5.3.0-46-generic                | 23       | 0.67%   |
| 5.3.0-40-generic                | 23       | 0.67%   |
| 5.4.0-56-generic                | 22       | 0.64%   |
| 5.4.0-29-generic                | 21       | 0.61%   |
| 5.4.0-26-generic                | 21       | 0.61%   |
| 5.15.0-46-generic               | 21       | 0.61%   |
| 5.4.0-54-generic                | 20       | 0.58%   |
| 5.4.0-40-generic                | 19       | 0.55%   |
| 6.4.11-desktop-1omv2390         | 18       | 0.52%   |
| 5.4.0-28-generic                | 18       | 0.52%   |
| 5.11.0-38-generic               | 18       | 0.52%   |
| 5.0.0-32-generic                | 18       | 0.52%   |
| 5.8.0-59-generic                | 16       | 0.47%   |
| 5.4.0-37-generic                | 16       | 0.47%   |
| 5.15.0-60-generic               | 16       | 0.47%   |
| 5.15.0-43-generic               | 16       | 0.47%   |
| 5.8.0-41-generic                | 15       | 0.44%   |
| 5.4.0-65-generic                | 15       | 0.44%   |
| 5.4.0-33-generic                | 15       | 0.44%   |
| 5.3.0-42-generic                | 15       | 0.44%   |
| 5.19.0-35-generic               | 15       | 0.44%   |
| 4.18.16-desktop-1bP             | 15       | 0.44%   |
| 5.4.0-47-generic                | 14       | 0.41%   |
| 5.4.0-31-generic                | 14       | 0.41%   |
| 5.19.0-23-generic               | 14       | 0.41%   |
| 5.10.0-19-amd64                 | 14       | 0.41%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 14       | 0.41%   |
| 4.18.0-25-generic               | 14       | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 520      | 16.44%  |
| 5.15.0  | 325      | 10.28%  |
| 4.15.0  | 209      | 6.61%   |
| 5.8.0   | 162      | 5.12%   |
| 5.3.0   | 140      | 4.43%   |
| 5.11.0  | 115      | 3.64%   |
| 5.19.0  | 112      | 3.54%   |
| 5.10.14 | 105      | 3.32%   |
| 5.0.0   | 99       | 3.13%   |
| 5.13.0  | 84       | 2.66%   |
| 5.16.7  | 81       | 2.56%   |
| 5.10.0  | 73       | 2.31%   |
| 4.18.0  | 65       | 2.06%   |
| 6.2.6   | 42       | 1.33%   |
| 6.1.1   | 42       | 1.33%   |
| 6.2.0   | 38       | 1.2%    |
| 4.19.0  | 30       | 0.95%   |
| 6.0.2   | 27       | 0.85%   |
| 6.4.11  | 25       | 0.79%   |
| 6.1.0   | 18       | 0.57%   |
| 4.9.60  | 18       | 0.57%   |
| 4.9.20  | 17       | 0.54%   |
| 4.18.16 | 16       | 0.51%   |
| 5.19.6  | 15       | 0.47%   |
| 6.0.6   | 14       | 0.44%   |
| 5.19.16 | 13       | 0.41%   |
| 6.0.10  | 12       | 0.38%   |
| 4.4.0   | 11       | 0.35%   |
| 6.0.12  | 10       | 0.32%   |
| 5.17.5  | 10       | 0.32%   |
| 5.18.12 | 9        | 0.28%   |
| 6.1.4   | 8        | 0.25%   |
| 6.0.0   | 8        | 0.25%   |
| 5.12.4  | 8        | 0.25%   |
| 6.2.9   | 7        | 0.22%   |
| 6.1.8   | 7        | 0.22%   |
| 6.0.9   | 7        | 0.22%   |
| 6.0.8   | 7        | 0.22%   |
| 6.0.7   | 7        | 0.22%   |
| 6.0.5   | 7        | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 547      | 17.5%   |
| 5.15    | 383      | 12.26%  |
| 4.15    | 210      | 6.72%   |
| 5.10    | 207      | 6.62%   |
| 5.8     | 186      | 5.95%   |
| 5.19    | 172      | 5.5%    |
| 5.3     | 145      | 4.64%   |
| 5.11    | 134      | 4.29%   |
| 6.2     | 120      | 3.84%   |
| 6.1     | 111      | 3.55%   |
| 5.16    | 111      | 3.55%   |
| 6.0     | 103      | 3.3%    |
| 5.0     | 102      | 3.26%   |
| 5.13    | 93       | 2.98%   |
| 4.18    | 85       | 2.72%   |
| 6.4     | 66       | 2.11%   |
| 4.9     | 55       | 1.76%   |
| 4.19    | 40       | 1.28%   |
| 5.9     | 32       | 1.02%   |
| 6.3     | 29       | 0.93%   |
| 5.17    | 29       | 0.93%   |
| 5.18    | 28       | 0.9%    |
| 5.6     | 20       | 0.64%   |
| 5.12    | 20       | 0.64%   |
| 5.14    | 19       | 0.61%   |
| 5.7     | 18       | 0.58%   |
| 6.5     | 11       | 0.35%   |
| 4.4     | 11       | 0.35%   |
| 4.1     | 10       | 0.32%   |
| 5.5     | 9        | 0.29%   |
| 4.13    | 5        | 0.16%   |
| 5.1     | 2        | 0.06%   |
| 4.20    | 2        | 0.06%   |
| 6.6     | 1        | 0.03%   |
| 5.2     | 1        | 0.03%   |
| 4.8     | 1        | 0.03%   |
| 4.7     | 1        | 0.03%   |
| 4.17    | 1        | 0.03%   |
| 4.14    | 1        | 0.03%   |
| 4.12    | 1        | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 2657     | 96.09%  |
| i686    | 107      | 3.87%   |
| ppc64le | 1        | 0.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| GNOME            | 1131     | 39%     |
| KDE5             | 590      | 20.34%  |
| Unknown          | 376      | 12.97%  |
| XFCE             | 217      | 7.48%   |
| X-Cinnamon       | 200      | 6.9%    |
| MATE             | 94       | 3.24%   |
| KDE              | 61       | 2.1%    |
| KDE4             | 57       | 1.97%   |
| LXQt             | 42       | 1.45%   |
| Cinnamon         | 23       | 0.79%   |
| LXDE             | 21       | 0.72%   |
| Unity            | 19       | 0.66%   |
| Pantheon         | 15       | 0.52%   |
| GNOME Flashback  | 11       | 0.38%   |
| GNOME Classic    | 8        | 0.28%   |
| i3               | 5        | 0.17%   |
| Deepin           | 5        | 0.17%   |
| Budgie           | 5        | 0.17%   |
| Trinity          | 4        | 0.14%   |
| lightdm-xsession | 4        | 0.14%   |
| Hyprland         | 3        | 0.1%    |
| openbox          | 2        | 0.07%   |
| sway             | 1        | 0.03%   |
| onyx:GNOME       | 1        | 0.03%   |
| Lubuntu          | 1        | 0.03%   |
| icewm            | 1        | 0.03%   |
| herbstluftwm     | 1        | 0.03%   |
| FVWM             | 1        | 0.03%   |
| bspwm            | 1        | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 2236     | 78.18%  |
| Wayland | 380      | 13.29%  |
| Unknown | 190      | 6.64%   |
| Tty     | 54       | 1.89%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1376     | 47.45%  |
| SDDM    | 558      | 19.24%  |
| GDM3    | 317      | 10.93%  |
| LightDM | 280      | 9.66%   |
| GDM     | 236      | 8.14%   |
| TDM     | 62       | 2.14%   |
| KDM     | 59       | 2.03%   |
| XDM     | 7        | 0.24%   |
| GREETD  | 3        | 0.1%    |
| NODM    | 1        | 0.03%   |
| LXDM    | 1        | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| it_IT       | 1828     | 64.25%  |
| en_US       | 489      | 17.19%  |
| Unknown     | 390      | 13.71%  |
| en_GB       | 50       | 1.76%   |
| C           | 49       | 1.72%   |
| fr_FR       | 5        | 0.18%   |
| de_DE       | 5        | 0.18%   |
| it_CH       | 4        | 0.14%   |
| ru_RU       | 3        | 0.11%   |
| en_IE       | 3        | 0.11%   |
| de_AT       | 3        | 0.11%   |
| POSIX       | 2        | 0.07%   |
| it_IT@euro  | 2        | 0.07%   |
| de_IT       | 2        | 0.07%   |
| sc_IT       | 1        | 0.04%   |
| it_ITutf8   | 1        | 0.04%   |
| it          | 1        | 0.04%   |
| hu_HU       | 1        | 0.04%   |
| fr_CH       | 1        | 0.04%   |
| es_MX       | 1        | 0.04%   |
| es_ES       | 1        | 0.04%   |
| en_US.ASCII | 1        | 0.04%   |
| en_AG       | 1        | 0.04%   |
| Default     | 1        | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1753     | 61.88%  |
| EFI  | 1080     | 38.12%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 2102     | 73.52%  |
| Overlay | 329      | 11.51%  |
| Btrfs   | 185      | 6.47%   |
| Unknown | 117      | 4.09%   |
| Tmpfs   | 53       | 1.85%   |
| Xfs     | 37       | 1.29%   |
| Zfs     | 11       | 0.38%   |
| Ext3    | 10       | 0.35%   |
| Ext2    | 7        | 0.24%   |
| F2fs    | 4        | 0.14%   |
| Aufs    | 3        | 0.1%    |
| XXXX    | 1        | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1459     | 51%     |
| GPT     | 981      | 34.29%  |
| MBR     | 421      | 14.72%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2216     | 77.62%  |
| Yes       | 639      | 22.38%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1646     | 57.96%  |
| Yes       | 1194     | 42.04%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 867      | 31.39%  |
| MSI                                  | 346      | 12.53%  |
| ASRock                               | 338      | 12.24%  |
| Gigabyte Technology                  | 264      | 9.56%   |
| Hewlett-Packard                      | 218      | 7.89%   |
| Dell                                 | 132      | 4.78%   |
| Acer                                 | 112      | 4.06%   |
| Lenovo                               | 85       | 3.08%   |
| Intel                                | 60       | 2.17%   |
| Pegatron                             | 45       | 1.63%   |
| Unknown                              | 41       | 1.48%   |
| Fujitsu                              | 39       | 1.41%   |
| Packard Bell                         | 26       | 0.94%   |
| Foxconn                              | 24       | 0.87%   |
| Fujitsu Siemens                      | 14       | 0.51%   |
| AMI                                  | 12       | 0.43%   |
| AZW                                  | 11       | 0.4%    |
| Supermicro                           | 10       | 0.36%   |
| BESSTAR Tech                         | 10       | 0.36%   |
| Biostar                              | 8        | 0.29%   |
| ABIT                                 | 6        | 0.22%   |
| TYAN Computer                        | 5        | 0.18%   |
| Sapphire                             | 5        | 0.18%   |
| IBM                                  | 5        | 0.18%   |
| Apple                                | 5        | 0.18%   |
| Wistron                              | 4        | 0.14%   |
| NEC Computers                        | 4        | 0.14%   |
| Chuwi                                | 4        | 0.14%   |
| YANYU                                | 3        | 0.11%   |
| Shuttle                              | 3        | 0.11%   |
| Shenzhen Meigao Electronic Equipment | 3        | 0.11%   |
| Huanan                               | 3        | 0.11%   |
| Gateway                              | 3        | 0.11%   |
| ECS                                  | 3        | 0.11%   |
| Alienware                            | 3        | 0.11%   |
| Proline                              | 2        | 0.07%   |
| OEM                                  | 2        | 0.07%   |
| LattePanda                           | 2        | 0.07%   |
| eMachines                            | 2        | 0.07%   |
| American Megatrends                  | 2        | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 80       | 2.9%    |
| Unknown                          | 42       | 1.52%   |
| MSI MS-7C37                      | 17       | 0.62%   |
| Dell OptiPlex 7010               | 17       | 0.62%   |
| ASUS PRIME A320M-K               | 17       | 0.62%   |
| MSI MS-7C56                      | 15       | 0.54%   |
| MSI MS-7B86                      | 14       | 0.51%   |
| Gigabyte B450M DS3H              | 11       | 0.4%    |
| MSI MS-7B79                      | 10       | 0.36%   |
| HP Compaq Elite 8300 SFF         | 10       | 0.36%   |
| MSI MS-7C52                      | 9        | 0.33%   |
| ASUS TUF Gaming X570-PLUS        | 9        | 0.33%   |
| ASRock Q1900M                    | 9        | 0.33%   |
| MSI MS-7C02                      | 8        | 0.29%   |
| HP ProDesk 600 G1 SFF            | 8        | 0.29%   |
| ASUS ROG STRIX B550-F GAMING     | 8        | 0.29%   |
| Supermicro H8DM8-2               | 7        | 0.25%   |
| HP Compaq 8200 Elite SFF PC      | 7        | 0.25%   |
| Gigabyte X570 AORUS ELITE        | 7        | 0.25%   |
| Dell OptiPlex 3020               | 7        | 0.25%   |
| ASUS TUF Gaming B550-PLUS        | 7        | 0.25%   |
| ASUS PRIME B450-PLUS             | 7        | 0.25%   |
| ASUS P5KPL-SE                    | 7        | 0.25%   |
| ASUS P5KPL-AM SE                 | 7        | 0.25%   |
| ASRock N68C-S UCC                | 7        | 0.25%   |
| MSI MS-7C91                      | 6        | 0.22%   |
| MSI MS-7758                      | 6        | 0.22%   |
| Dell OptiPlex 780                | 6        | 0.22%   |
| Dell OptiPlex 390                | 6        | 0.22%   |
| ASUS P5K                         | 6        | 0.22%   |
| ASUS M5A97 R2.0                  | 6        | 0.22%   |
| ASUS H110M-K                     | 6        | 0.22%   |
| ASRock B450M-HDV R4.0            | 6        | 0.22%   |
| ASRock 960GC-GS FX               | 6        | 0.22%   |
| MSI MS-7B89                      | 5        | 0.18%   |
| MSI MS-7817                      | 5        | 0.18%   |
| MSI MS-7721                      | 5        | 0.18%   |
| MSI MS-7693                      | 5        | 0.18%   |
| HP Compaq 6000 Pro MT PC         | 5        | 0.18%   |
| Gigabyte X470 AORUS ULTRA GAMING | 5        | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS PRIME          | 131      | 4.74%   |
| HP Compaq           | 88       | 3.19%   |
| Dell OptiPlex       | 82       | 2.97%   |
| ASUS All            | 80       | 2.9%    |
| ASUS ROG            | 60       | 2.17%   |
| Acer Aspire         | 59       | 2.14%   |
| ASUS TUF            | 54       | 1.96%   |
| Lenovo ThinkCentre  | 48       | 1.74%   |
| Unknown             | 42       | 1.52%   |
| Acer Veriton        | 37       | 1.34%   |
| Fujitsu ESPRIMO     | 35       | 1.27%   |
| HP ProDesk          | 24       | 0.87%   |
| ASUS P8H61-M        | 24       | 0.87%   |
| Dell Precision      | 22       | 0.8%    |
| HP Pavilion         | 20       | 0.72%   |
| Gigabyte X570       | 19       | 0.69%   |
| Packard Bell IMEDIA | 18       | 0.65%   |
| MSI MS-7C37         | 17       | 0.62%   |
| HP EliteDesk        | 17       | 0.62%   |
| MSI MS-7C56         | 15       | 0.54%   |
| ASUS P5KPL-AM       | 15       | 0.54%   |
| ASUS M5A97          | 15       | 0.54%   |
| MSI MS-7B86         | 14       | 0.51%   |
| Lenovo IdeaCentre   | 13       | 0.47%   |
| Gigabyte B450M      | 13       | 0.47%   |
| Gigabyte B450       | 13       | 0.47%   |
| ASUS P8Z77-V        | 12       | 0.43%   |
| ASUS P5Q            | 12       | 0.43%   |
| ASUS P5K            | 12       | 0.43%   |
| ASUS M5A78L-M       | 11       | 0.4%    |
| ASRock B450         | 11       | 0.4%    |
| MSI MS-7B79         | 10       | 0.36%   |
| Lenovo ThinkStation | 10       | 0.36%   |
| Gigabyte Z390       | 10       | 0.36%   |
| ASRock 970          | 10       | 0.36%   |
| Pegatron Pro        | 9        | 0.33%   |
| MSI MS-7C52         | 9        | 0.33%   |
| ASUS SABERTOOTH     | 9        | 0.33%   |
| ASUS P8P67          | 9        | 0.33%   |
| ASUS P6T            | 9        | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 250      | 9.05%   |
| 2013    | 222      | 8.04%   |
| 2012    | 222      | 8.04%   |
| 2009    | 206      | 7.46%   |
| 2011    | 192      | 6.95%   |
| 2019    | 186      | 6.73%   |
| 2008    | 183      | 6.63%   |
| 2014    | 174      | 6.3%    |
| 2020    | 169      | 6.12%   |
| 2010    | 153      | 5.54%   |
| 2017    | 144      | 5.21%   |
| 2015    | 127      | 4.6%    |
| 2007    | 127      | 4.6%    |
| 2016    | 113      | 4.09%   |
| 2021    | 96       | 3.48%   |
| 2006    | 74       | 2.68%   |
| 2022    | 45       | 1.63%   |
| 2005    | 44       | 1.59%   |
| 2023    | 14       | 0.51%   |
| 2004    | 11       | 0.4%    |
| 2003    | 4        | 0.14%   |
| Unknown | 3        | 0.11%   |
| 2001    | 2        | 0.07%   |
| 2002    | 1        | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 2762     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 2702     | 97.55%  |
| Enabled  | 68       | 2.45%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2762     | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 624      | 22.19%  |
| 8.01-16.0       | 590      | 20.98%  |
| 3.01-4.0        | 536      | 19.06%  |
| 4.01-8.0        | 433      | 15.4%   |
| 32.01-64.0      | 291      | 10.35%  |
| 1.01-2.0        | 137      | 4.87%   |
| 64.01-256.0     | 78       | 2.77%   |
| 24.01-32.0      | 53       | 1.88%   |
| 2.01-3.0        | 42       | 1.49%   |
| 0.51-1.0        | 24       | 0.85%   |
| More than 256.0 | 2        | 0.07%   |
| 0.01-0.5        | 2        | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 1244     | 40.25%  |
| 2.01-3.0   | 727      | 23.52%  |
| 3.01-4.0   | 351      | 11.36%  |
| 4.01-8.0   | 337      | 10.9%   |
| 0.51-1.0   | 282      | 9.12%   |
| 8.01-16.0  | 90       | 2.91%   |
| 0.01-0.5   | 38       | 1.23%   |
| 16.01-24.0 | 15       | 0.49%   |
| 24.01-32.0 | 5        | 0.16%   |
| 32.01-64.0 | 1        | 0.03%   |
| Unknown    | 1        | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 1096     | 37.82%  |
| 2       | 857      | 29.57%  |
| 3       | 484      | 16.7%   |
| 4       | 230      | 7.94%   |
| 5       | 108      | 3.73%   |
| 6       | 52       | 1.79%   |
| 0       | 30       | 1.04%   |
| 7       | 17       | 0.59%   |
| 8       | 11       | 0.38%   |
| 10      | 4        | 0.14%   |
| 9       | 4        | 0.14%   |
| 12      | 3        | 0.1%    |
| 13      | 1        | 0.03%   |
| Unknown | 1        | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1644     | 58.74%  |
| No        | 1155     | 41.26%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2744     | 99.35%  |
| No        | 18       | 0.65%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1584     | 56.51%  |
| Yes       | 1219     | 43.49%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2036     | 72.15%  |
| Yes       | 786      | 27.85%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Italy   | 2762     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Milan                 | 337      | 10.61%  |
| Rome                  | 315      | 9.92%   |
| Turin                 | 98       | 3.08%   |
| Bologna               | 84       | 2.64%   |
| Naples                | 62       | 1.95%   |
| Florence              | 58       | 1.83%   |
| Genoa                 | 51       | 1.61%   |
| Rho                   | 34       | 1.07%   |
| Palermo               | 34       | 1.07%   |
| Padova                | 34       | 1.07%   |
| Milano                | 32       | 1.01%   |
| Verona                | 28       | 0.88%   |
| Venice                | 23       | 0.72%   |
| Catania               | 22       | 0.69%   |
| Brescia               | 22       | 0.69%   |
| Trieste               | 19       | 0.6%    |
| Pescara               | 19       | 0.6%    |
| Reggio Emilia         | 18       | 0.57%   |
| Cagliari              | 18       | 0.57%   |
| Bari                  | 18       | 0.57%   |
| Pisa                  | 17       | 0.54%   |
| Parma                 | 17       | 0.54%   |
| Capriate San Gervasio | 16       | 0.5%    |
| Bergamo               | 15       | 0.47%   |
| Monza                 | 14       | 0.44%   |
| Trento                | 13       | 0.41%   |
| Sesto San Giovanni    | 13       | 0.41%   |
| Vicenza               | 12       | 0.38%   |
| Casalecchio di Reno   | 12       | 0.38%   |
| Taranto               | 11       | 0.35%   |
| Perugia               | 11       | 0.35%   |
| Modena                | 11       | 0.35%   |
| Como                  | 11       | 0.35%   |
| Lucca                 | 10       | 0.31%   |
| Udine                 | 9        | 0.28%   |
| Treviso               | 9        | 0.28%   |
| Sesto Fiorentino      | 8        | 0.25%   |
| Mestre                | 8        | 0.25%   |
| Forlì                | 8        | 0.25%   |
| Salerno               | 7        | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 1006     | 1697   | 19.98%  |
| WDC                         | 905      | 1540   | 17.97%  |
| Samsung Electronics         | 726      | 1158   | 14.42%  |
| Kingston                    | 375      | 535    | 7.45%   |
| Crucial                     | 327      | 447    | 6.49%   |
| Toshiba                     | 242      | 392    | 4.81%   |
| Maxtor                      | 188      | 259    | 3.73%   |
| SanDisk                     | 177      | 261    | 3.51%   |
| Hitachi                     | 169      | 226    | 3.36%   |
| Unknown                     | 69       | 96     | 1.37%   |
| Phison                      | 63       | 97     | 1.25%   |
| China                       | 48       | 56     | 0.95%   |
| SPCC                        | 40       | 49     | 0.79%   |
| HGST                        | 38       | 60     | 0.75%   |
| Micron/Crucial Technology   | 35       | 46     | 0.69%   |
| Intenso                     | 30       | 43     | 0.6%    |
| Intel                       | 30       | 41     | 0.6%    |
| Corsair                     | 29       | 45     | 0.58%   |
| Phison Electronics          | 27       | 36     | 0.54%   |
| Micron Technology           | 26       | 28     | 0.52%   |
| A-DATA Technology           | 26       | 37     | 0.52%   |
| OCZ                         | 23       | 28     | 0.46%   |
| PNY                         | 22       | 31     | 0.44%   |
| Transcend                   | 20       | 26     | 0.4%    |
| KingDian                    | 19       | 20     | 0.38%   |
| SK hynix                    | 18       | 19     | 0.36%   |
| Silicon Motion              | 16       | 26     | 0.32%   |
| Patriot                     | 15       | 20     | 0.3%    |
| Lexar                       | 14       | 18     | 0.28%   |
| Drevo                       | 13       | 14     | 0.26%   |
| Kingston Technology Company | 11       | 16     | 0.22%   |
| JMicron Technology          | 10       | 11     | 0.2%    |
| Team                        | 9        | 20     | 0.18%   |
| SABRENT                     | 9        | 9      | 0.18%   |
| GOODRAM                     | 9        | 16     | 0.18%   |
| Fujitsu                     | 9        | 10     | 0.18%   |
| XPG                         | 8        | 8      | 0.16%   |
| TCSUNBOW                    | 8        | 9      | 0.16%   |
| Fanxiang                    | 8        | 10     | 0.16%   |
| ASMT                        | 8        | 8      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 113      | 1.94%   |
| Kingston SA400S37240G 240GB SSD                     | 110      | 1.89%   |
| Samsung SSD 860 EVO 500GB                           | 80       | 1.37%   |
| Samsung SSD 850 EVO 250GB                           | 77       | 1.32%   |
| Seagate ST1000DM010-2EP102 1TB                      | 74       | 1.27%   |
| Crucial CT500MX500SSD1 500GB                        | 74       | 1.27%   |
| Toshiba DT01ACA100 1TB                              | 64       | 1.1%    |
| Seagate ST2000DM008-2FR102 2TB                      | 58       | 1%      |
| Kingston SA400S37480G 480GB SSD                     | 57       | 0.98%   |
| Seagate ST3500418AS 500GB                           | 50       | 0.86%   |
| Samsung SSD 850 EVO 500GB                           | 45       | 0.77%   |
| Samsung SSD 860 EVO 250GB                           | 43       | 0.74%   |
| Kingston SA400S37120G 120GB SSD                     | 41       | 0.7%    |
| Crucial CT1000MX500SSD1 1TB                         | 40       | 0.69%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 39       | 0.67%   |
| Seagate ST31000528AS 1TB                            | 38       | 0.65%   |
| Seagate ST1000DM003-1ER162 1TB                      | 38       | 0.65%   |
| Seagate ST1000DM003-1CH162 1TB                      | 38       | 0.65%   |
| Crucial CT240BX500SSD1 240GB                        | 38       | 0.65%   |
| Seagate ST2000DM001-1ER164 2TB                      | 34       | 0.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 30       | 0.52%   |
| Kingston SV300S37A120G 120GB SSD                    | 30       | 0.52%   |
| Crucial CT480BX500SSD1 480GB                        | 30       | 0.52%   |
| Toshiba DT01ACA050 500GB                            | 29       | 0.5%    |
| Seagate ST1000DM003-1SB10C 1TB                      | 27       | 0.46%   |
| Phison Sabrent 256GB                                | 27       | 0.46%   |
| Seagate ST3500413AS 500GB                           | 26       | 0.45%   |
| Samsung NVMe SSD Drive 500GB                        | 26       | 0.45%   |
| Unknown SD/MMC/MS PRO 128GB                         | 25       | 0.43%   |
| Seagate M3 Portable 1TB                             | 24       | 0.41%   |
| Maxtor STM3250310AS 250GB                           | 24       | 0.41%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 23       | 0.39%   |
| Toshiba DT01ACA200 2TB                              | 23       | 0.39%   |
| Samsung SSD 840 EVO 250GB                           | 23       | 0.39%   |
| Seagate ST2000DM006-2DM164 2TB                      | 22       | 0.38%   |
| Seagate ST1000DM003-9YN162 1TB                      | 22       | 0.38%   |
| Seagate Expansion 1TB                               | 22       | 0.38%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 21       | 0.36%   |
| Seagate ST4000DM004-2CV104 4TB                      | 21       | 0.36%   |
| Seagate ST1000DM003-1SB102 1TB                      | 20       | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 986      | 1649   | 37.71%  |
| WDC                 | 831      | 1397   | 31.78%  |
| Toshiba             | 212      | 344    | 8.11%   |
| Maxtor              | 188      | 259    | 7.19%   |
| Hitachi             | 169      | 226    | 6.46%   |
| Samsung Electronics | 103      | 129    | 3.94%   |
| HGST                | 38       | 60     | 1.45%   |
| Unknown             | 32       | 41     | 1.22%   |
| Fujitsu             | 9        | 10     | 0.34%   |
| SABRENT             | 8        | 8      | 0.31%   |
| Apple               | 5        | 5      | 0.19%   |
| USB3.0              | 3        | 4      | 0.11%   |
| Hewlett-Packard     | 3        | 4      | 0.11%   |
| External            | 3        | 3      | 0.11%   |
| ASMT                | 3        | 3      | 0.11%   |
| WD MediaMax         | 2        | 2      | 0.08%   |
| Initio              | 2        | 2      | 0.08%   |
| IBM/Hitachi         | 2        | 2      | 0.08%   |
| HGST HTS            | 2        | 2      | 0.08%   |
| USB 3.0             | 1        | 2      | 0.04%   |
| USB                 | 1        | 1      | 0.04%   |
| SSK                 | 1        | 1      | 0.04%   |
| QUANTUM             | 1        | 1      | 0.04%   |
| Promise             | 1        | 1      | 0.04%   |
| PI-041              | 1        | 1      | 0.04%   |
| MARVELL             | 1        | 2      | 0.04%   |
| LaCie               | 1        | 2      | 0.04%   |
| Intenso             | 1        | 3      | 0.04%   |
| HPE                 | 1        | 1      | 0.04%   |
| FC-1307             | 1        | 2      | 0.04%   |
| Config              | 1        | 1      | 0.04%   |
| China               | 1        | 1      | 0.04%   |
| ASMT109x            | 1        | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 465      | 701    | 26.24%  |
| Kingston            | 345      | 494    | 19.47%  |
| Crucial             | 285      | 389    | 16.08%  |
| SanDisk             | 133      | 204    | 7.51%   |
| WDC                 | 69       | 97     | 3.89%   |
| China               | 47       | 55     | 2.65%   |
| SPCC                | 35       | 44     | 1.98%   |
| Toshiba             | 27       | 36     | 1.52%   |
| Intenso             | 27       | 37     | 1.52%   |
| Corsair             | 23       | 37     | 1.3%    |
| OCZ                 | 22       | 27     | 1.24%   |
| A-DATA Technology   | 22       | 33     | 1.24%   |
| PNY                 | 21       | 30     | 1.19%   |
| KingDian            | 19       | 20     | 1.07%   |
| Transcend           | 18       | 24     | 1.02%   |
| Patriot             | 15       | 20     | 0.85%   |
| Intel               | 13       | 19     | 0.73%   |
| Micron Technology   | 12       | 13     | 0.68%   |
| Drevo               | 11       | 11     | 0.62%   |
| GOODRAM             | 9        | 16     | 0.51%   |
| Team                | 8        | 19     | 0.45%   |
| TCSUNBOW            | 8        | 9      | 0.45%   |
| Lexar               | 8        | 11     | 0.45%   |
| Dogfish             | 7        | 10     | 0.4%    |
| Unknown             | 6        | 7      | 0.34%   |
| LITEONIT            | 6        | 6      | 0.34%   |
| Verbatim            | 5        | 5      | 0.28%   |
| TO Exter            | 5        | 5      | 0.28%   |
| SK hynix            | 5        | 5      | 0.28%   |
| JMicron Technology  | 5        | 6      | 0.28%   |
| BAITITON            | 5        | 5      | 0.28%   |
| ASMT                | 5        | 5      | 0.28%   |
| Plextor             | 4        | 8      | 0.23%   |
| LITEON              | 4        | 5      | 0.23%   |
| Fanxiang            | 4        | 6      | 0.23%   |
| Apacer              | 4        | 4      | 0.23%   |
| Unknown             | 4        | 4      | 0.23%   |
| Netac               | 3        | 3      | 0.17%   |
| KIOXIA-EXCERIA      | 3        | 3      | 0.17%   |
| KingSpec            | 3        | 4      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1999     | 4170   | 48.19%  |
| SSD     | 1469     | 2508   | 35.41%  |
| NVMe    | 569      | 903    | 13.72%  |
| Unknown | 85       | 122    | 2.05%   |
| MMC     | 26       | 31     | 0.63%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 2552     | 6537   | 76.52%  |
| NVMe | 569      | 896    | 17.06%  |
| SAS  | 188      | 270    | 5.64%   |
| MMC  | 26       | 31     | 0.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| 0.01-0.5        | 2087     | 3987   | 57.18%  |
| 0.51-1.0        | 967      | 1615   | 26.49%  |
| 1.01-2.0        | 330      | 584    | 9.04%   |
| 3.01-4.0        | 102      | 186    | 2.79%   |
| 2.01-3.0        | 102      | 174    | 2.79%   |
| 4.01-10.0       | 54       | 116    | 1.48%   |
| 10.01-20.0      | 7        | 15     | 0.19%   |
| More than 100.0 | 1        | 1      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 691      | 22.95%  |
| 251-500        | 499      | 16.57%  |
| 501-1000       | 407      | 13.52%  |
| 1001-2000      | 333      | 11.06%  |
| 1-20           | 274      | 9.1%    |
| More than 3000 | 225      | 7.47%   |
| 51-100         | 214      | 7.11%   |
| 2001-3000      | 155      | 5.15%   |
| 21-50          | 111      | 3.69%   |
| Unknown        | 101      | 3.35%   |
| 0              | 1        | 0.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1147     | 37.08%  |
| 21-50          | 422      | 13.64%  |
| 101-250        | 315      | 10.18%  |
| 51-100         | 297      | 9.6%    |
| 501-1000       | 249      | 8.05%   |
| 251-500        | 245      | 7.92%   |
| 1001-2000      | 165      | 5.33%   |
| Unknown        | 101      | 3.27%   |
| More than 3000 | 90       | 2.91%   |
| 2001-3000      | 61       | 1.97%   |
| 0              | 1        | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB  | 21       | 24     | 5.19%   |
| Seagate ST3500418AS 500GB        | 11       | 15     | 2.72%   |
| Maxtor STM3250310AS 250GB        | 8        | 9      | 1.98%   |
| Maxtor STM3320820AS 320GB        | 5        | 5      | 1.23%   |
| WDC WD40EFRX-68N32N0 4TB         | 4        | 5      | 0.99%   |
| Unknown MM0500EANCR 500GB        | 4        | 9      | 0.99%   |
| Seagate ST31500341AS 1TB         | 4        | 4      | 0.99%   |
| Seagate ST31000528AS 1TB         | 4        | 7      | 0.99%   |
| SanDisk SSD PLUS 480GB           | 4        | 5      | 0.99%   |
| Samsung Electronics HD103UJ 1TB  | 4        | 4      | 0.99%   |
| WDC WD20EFRX-68EUZN0 2TB         | 3        | 4      | 0.74%   |
| Toshiba DT01ACA100 1TB           | 3        | 3      | 0.74%   |
| Toshiba DT01ACA050 500GB         | 3        | 3      | 0.74%   |
| Seagate ST9500325AS 500GB        | 3        | 3      | 0.74%   |
| Seagate ST3500413AS 500GB        | 3        | 5      | 0.74%   |
| Seagate ST3500320AS 500GB        | 3        | 3      | 0.74%   |
| Seagate ST3250310AS 250GB        | 3        | 3      | 0.74%   |
| Seagate ST2000DM001-1ER164 2TB   | 3        | 7      | 0.74%   |
| Seagate ST1000DM003-1ER162 1TB   | 3        | 3      | 0.74%   |
| Maxtor 6Y080L0 82GB              | 3        | 3      | 0.74%   |
| Kingston SA400S37240G 240GB SSD  | 3        | 3      | 0.74%   |
| Hitachi HDS721010CLA332 1TB      | 3        | 3      | 0.74%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 2        | 2      | 0.49%   |
| WDC WD5000LPCX-24C6HT0 500GB     | 2        | 2      | 0.49%   |
| WDC WD5000AADS-00S9B0 500GB      | 2        | 2      | 0.49%   |
| WDC WD40PURZ-85TTDY0 4TB         | 2        | 2      | 0.49%   |
| WDC WD30EFRX-68EUZN0 3TB         | 2        | 2      | 0.49%   |
| WDC WD10EZEX-60WN4A0 1TB         | 2        | 3      | 0.49%   |
| WDC WD10EZEX-60M2NA0 1TB         | 2        | 2      | 0.49%   |
| WDC WD10EADS-00M2B0 1TB          | 2        | 2      | 0.49%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 2        | 2      | 0.49%   |
| Toshiba MK2035GSS 200GB          | 2        | 2      | 0.49%   |
| Seagate ST9500530NS 500GB        | 2        | 3      | 0.49%   |
| Seagate ST6000AS0002-1N917X 6TB  | 2        | 5      | 0.49%   |
| Seagate ST3500620AS 500GB        | 2        | 2      | 0.49%   |
| Seagate ST3320620AS 320GB        | 2        | 3      | 0.49%   |
| Seagate ST3320613AS 320GB        | 2        | 3      | 0.49%   |
| Seagate ST3250820AS 250GB        | 2        | 3      | 0.49%   |
| Seagate ST3250318AS 250GB        | 2        | 2      | 0.49%   |
| Seagate ST2000DM006-2DM164 2TB   | 2        | 2      | 0.49%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 117      | 160    | 30.23%  |
| WDC                 | 95       | 119    | 24.55%  |
| Maxtor              | 39       | 48     | 10.08%  |
| Hitachi             | 30       | 33     | 7.75%   |
| Samsung Electronics | 28       | 31     | 7.24%   |
| Toshiba             | 15       | 15     | 3.88%   |
| Kingston            | 12       | 12     | 3.1%    |
| Crucial             | 10       | 10     | 2.58%   |
| HGST                | 7        | 8      | 1.81%   |
| SanDisk             | 5        | 6      | 1.29%   |
| Unknown             | 4        | 9      | 1.03%   |
| OCZ                 | 3        | 3      | 0.78%   |
| Micron Technology   | 2        | 2      | 0.52%   |
| Intenso             | 2        | 3      | 0.52%   |
| Corsair             | 2        | 3      | 0.52%   |
| ASMT                | 2        | 2      | 0.52%   |
| WD MediaMax         | 1        | 1      | 0.26%   |
| USB3.0              | 1        | 1      | 0.26%   |
| TCSUNBOW            | 1        | 1      | 0.26%   |
| SK hynix            | 1        | 1      | 0.26%   |
| QUANTUM             | 1        | 1      | 0.26%   |
| LITEONIT            | 1        | 1      | 0.26%   |
| GSemi               | 1        | 1      | 0.26%   |
| Fujitsu             | 1        | 1      | 0.26%   |
| Emtec               | 1        | 1      | 0.26%   |
| Drevo               | 1        | 1      | 0.26%   |
| CT1000P1            | 1        | 2      | 0.26%   |
| BAITITON            | 1        | 1      | 0.26%   |
| Apacer              | 1        | 1      | 0.26%   |
| A-DATA Technology   | 1        | 1      | 0.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 117      | 160    | 36%     |
| WDC                 | 91       | 112    | 28%     |
| Maxtor              | 39       | 48     | 12%     |
| Hitachi             | 30       | 33     | 9.23%   |
| Samsung Electronics | 17       | 18     | 5.23%   |
| Toshiba             | 15       | 15     | 4.62%   |
| HGST                | 7        | 8      | 2.15%   |
| Unknown             | 4        | 9      | 1.23%   |
| WD MediaMax         | 1        | 1      | 0.31%   |
| USB3.0              | 1        | 1      | 0.31%   |
| QUANTUM             | 1        | 1      | 0.31%   |
| Fujitsu             | 1        | 1      | 0.31%   |
| ASMT                | 1        | 1      | 0.31%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 295      | 408    | 82.4%   |
| SSD  | 56       | 63     | 15.64%  |
| NVMe | 7        | 8      | 1.96%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB | 2        | 3      | 33.33%  |
| Seagate STM3250318AS 250GB      | 1        | 1      | 16.67%  |
| Seagate ST9500420AS 500GB       | 1        | 1      | 16.67%  |
| Hitachi HTS725050A7E630 500GB   | 1        | 1      | 16.67%  |
| Hitachi HTS543216L9A300 160GB   | 1        | 1      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 5      | 66.67%  |
| Hitachi | 2        | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 1666     | 4448   | 53.07%  |
| Works    | 1125     | 2800   | 35.84%  |
| Malfunc  | 342      | 479    | 10.9%   |
| Failed   | 6        | 7      | 0.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1819     | 47.22%  |
| AMD                              | 747      | 19.39%  |
| Samsung Electronics              | 234      | 6.07%   |
| ASMedia Technology               | 143      | 3.71%   |
| JMicron Technology               | 136      | 3.53%   |
| Marvell Technology Group         | 125      | 3.25%   |
| Nvidia                           | 123      | 3.19%   |
| Phison Electronics               | 97       | 2.52%   |
| Micron/Crucial Technology        | 78       | 2.02%   |
| SanDisk                          | 75       | 1.95%   |
| VIA Technologies                 | 52       | 1.35%   |
| Kingston Technology Company      | 44       | 1.14%   |
| Silicon Motion                   | 22       | 0.57%   |
| Micron Technology                | 16       | 0.42%   |
| Adaptec                          | 16       | 0.42%   |
| MAXIO Technology (Hangzhou)      | 13       | 0.34%   |
| ADATA Technology                 | 13       | 0.34%   |
| Toshiba America Info Systems     | 11       | 0.29%   |
| SK hynix                         | 11       | 0.29%   |
| Silicon Image                    | 11       | 0.29%   |
| Silicon Integrated Systems [SiS] | 9        | 0.23%   |
| LSI Logic / Symbios Logic        | 8        | 0.21%   |
| Broadcom / LSI                   | 8        | 0.21%   |
| Realtek Semiconductor            | 7        | 0.18%   |
| Shenzhen Longsys Electronics     | 5        | 0.13%   |
| KIOXIA                           | 4        | 0.1%    |
| Seagate Technology               | 3        | 0.08%   |
| Promise Technology               | 3        | 0.08%   |
| Integrated Technology Express    | 3        | 0.08%   |
| HighPoint Technologies           | 3        | 0.08%   |
| Broadcom                         | 3        | 0.08%   |
| ULi Electronics                  | 2        | 0.05%   |
| INNOGRIT                         | 2        | 0.05%   |
| Swissbit                         | 1        | 0.03%   |
| Solid State Storage Technology   | 1        | 0.03%   |
| OCZ Technology Group             | 1        | 0.03%   |
| Lite-On IT Corp. / Plextor       | 1        | 0.03%   |
| Initio                           | 1        | 0.03%   |
| Biwin Storage Technology         | 1        | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 414      | 8.31%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 194      | 3.9%    |
| AMD 400 Series Chipset SATA Controller                                                  | 161      | 3.23%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 157      | 3.15%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 140      | 2.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 135      | 2.71%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 133      | 2.67%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 132      | 2.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 129      | 2.59%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 125      | 2.51%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 118      | 2.37%   |
| Intel SATA Controller [RAID mode]                                                       | 114      | 2.29%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 110      | 2.21%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 95       | 1.91%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 84       | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 79       | 1.59%   |
| AMD 500 Series Chipset SATA Controller                                                  | 74       | 1.49%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 73       | 1.47%   |
| Phison E12 NVMe Controller                                                              | 65       | 1.31%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 62       | 1.24%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 62       | 1.24%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 61       | 1.22%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 53       | 1.06%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 50       | 1%      |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 50       | 1%      |
| Nvidia MCP61 SATA Controller                                                            | 49       | 0.98%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 43       | 0.86%   |
| Nvidia MCP61 IDE                                                                        | 42       | 0.84%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 41       | 0.82%   |
| Samsung NVMe SSD Controller 980                                                         | 41       | 0.82%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 38       | 0.76%   |
| AMD FCH SATA Controller D                                                               | 38       | 0.76%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 37       | 0.74%   |
| JMicron JMB368 IDE controller                                                           | 36       | 0.72%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 36       | 0.72%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 36       | 0.72%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 35       | 0.7%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 34       | 0.68%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 34       | 0.68%   |
| AMD 300 Series Chipset SATA Controller                                                  | 33       | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1998     | 53.34%  |
| IDE  | 926      | 24.72%  |
| NVMe | 575      | 15.35%  |
| RAID | 226      | 6.03%   |
| SCSI | 11       | 0.29%   |
| SAS  | 10       | 0.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 1908     | 69.08%  |
| AMD                      | 851      | 30.81%  |
| CentaurHauls             | 2        | 0.07%   |
| PowerNV C1P9S01 REV 1.01 | 1        | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 52       | 1.87%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 45       | 1.62%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 41       | 1.48%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 37       | 1.33%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 33       | 1.19%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 30       | 1.08%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 30       | 1.08%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 27       | 0.97%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 27       | 0.97%   |
| Intel Pentium 4 CPU 3.00GHz                 | 23       | 0.83%   |
| AMD FX-8350 Eight-Core Processor            | 23       | 0.83%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 22       | 0.79%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 21       | 0.76%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 21       | 0.76%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 21       | 0.76%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 20       | 0.72%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 19       | 0.68%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 19       | 0.68%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 19       | 0.68%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 19       | 0.68%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 18       | 0.65%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 18       | 0.65%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 18       | 0.65%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 18       | 0.65%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 18       | 0.65%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 18       | 0.65%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 18       | 0.65%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 17       | 0.61%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 17       | 0.61%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 16       | 0.58%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 16       | 0.58%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 16       | 0.58%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 16       | 0.58%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 16       | 0.58%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 16       | 0.58%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 16       | 0.58%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 16       | 0.58%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 16       | 0.58%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 15       | 0.54%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 15       | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 503      | 18.13%  |
| Intel Core i7           | 372      | 13.41%  |
| AMD Ryzen 5             | 196      | 7.07%   |
| Intel Core i3           | 191      | 6.89%   |
| AMD Ryzen 7             | 138      | 4.97%   |
| Intel Core 2 Quad       | 109      | 3.93%   |
| Intel Core 2 Duo        | 109      | 3.93%   |
| Intel Celeron           | 100      | 3.6%    |
| Intel Xeon              | 90       | 3.24%   |
| Intel Pentium Dual-Core | 77       | 2.78%   |
| Intel Pentium           | 76       | 2.74%   |
| AMD FX                  | 73       | 2.63%   |
| Intel Pentium 4         | 62       | 2.24%   |
| Other                   | 58       | 2.09%   |
| AMD Ryzen 9             | 57       | 2.05%   |
| AMD Athlon 64 X2        | 48       | 1.73%   |
| Intel Core 2            | 41       | 1.48%   |
| AMD Ryzen 3             | 40       | 1.44%   |
| Intel Pentium Dual      | 35       | 1.26%   |
| AMD Phenom II X4        | 33       | 1.19%   |
| Intel Atom              | 32       | 1.15%   |
| AMD A8                  | 28       | 1.01%   |
| Intel Core i9           | 26       | 0.94%   |
| Intel Pentium D         | 24       | 0.87%   |
| AMD Phenom II X6        | 21       | 0.76%   |
| AMD Sempron             | 20       | 0.72%   |
| AMD A10                 | 20       | 0.72%   |
| AMD Athlon II X2        | 19       | 0.68%   |
| AMD Phenom              | 16       | 0.58%   |
| AMD Athlon II X4        | 16       | 0.58%   |
| AMD A6                  | 14       | 0.5%    |
| AMD A4                  | 14       | 0.5%    |
| AMD Athlon 64           | 13       | 0.47%   |
| AMD Athlon              | 12       | 0.43%   |
| AMD Six-Core Opteron    | 11       | 0.4%    |
| AMD Athlon II X3        | 11       | 0.4%    |
| AMD Athlon X4           | 8        | 0.29%   |
| AMD Ryzen Threadripper  | 6        | 0.22%   |
| AMD Ryzen 5 PRO         | 5        | 0.18%   |
| Intel Pentium Gold      | 4        | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 1150     | 41.47%  |
| 2       | 762      | 27.48%  |
| 6       | 338      | 12.19%  |
| 8       | 236      | 8.51%   |
| 1       | 134      | 4.83%   |
| 12      | 60       | 2.16%   |
| 3       | 36       | 1.3%    |
| 16      | 26       | 0.94%   |
| 10      | 18       | 0.65%   |
| 24      | 6        | 0.22%   |
| 14      | 2        | 0.07%   |
| 5       | 2        | 0.07%   |
| 64      | 1        | 0.04%   |
| 28      | 1        | 0.04%   |
| Unknown | 1        | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 2725     | 98.66%  |
| 2      | 37       | 1.34%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 1454     | 52.53%  |
| 2       | 1309     | 47.29%  |
| 4       | 2        | 0.07%   |
| 12      | 1        | 0.04%   |
| 8       | 1        | 0.04%   |
| Unknown | 1        | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 2720     | 98.27%  |
| Unknown        | 26       | 0.94%   |
| 32-bit         | 22       | 0.79%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 708      | 24.39%  |
| 0x306c3    | 205      | 7.06%   |
| 0x206a7    | 148      | 5.1%    |
| 0x1067a    | 147      | 5.06%   |
| 0x306a9    | 139      | 4.79%   |
| 0x506e3    | 95       | 3.27%   |
| 0x08701021 | 92       | 3.17%   |
| 0x906e9    | 74       | 2.55%   |
| 0x6fb      | 56       | 1.93%   |
| 0x906ea    | 55       | 1.89%   |
| 0x0800820d | 42       | 1.45%   |
| 0x010000c8 | 41       | 1.41%   |
| 0x6fd      | 37       | 1.27%   |
| 0x06000852 | 35       | 1.21%   |
| 0x906ed    | 32       | 1.1%    |
| 0x08108109 | 31       | 1.07%   |
| 0x106e5    | 30       | 1.03%   |
| 0x10676    | 30       | 1.03%   |
| 0x6f6      | 27       | 0.93%   |
| 0x08701013 | 27       | 0.93%   |
| 0x06001119 | 26       | 0.9%    |
| 0x0a201016 | 25       | 0.86%   |
| 0xa0653    | 23       | 0.79%   |
| 0xa0655    | 22       | 0.76%   |
| 0x20655    | 22       | 0.76%   |
| 0x106a5    | 22       | 0.76%   |
| 0x08001138 | 22       | 0.76%   |
| 0x0a50000c | 21       | 0.72%   |
| 0x20652    | 19       | 0.65%   |
| 0x10677    | 19       | 0.65%   |
| 0xa0671    | 18       | 0.62%   |
| 0x0a50000d | 18       | 0.62%   |
| 0xf43      | 17       | 0.59%   |
| 0x03000027 | 17       | 0.59%   |
| 0x30678    | 16       | 0.55%   |
| 0x906eb    | 15       | 0.52%   |
| 0x306f2    | 15       | 0.52%   |
| 0x08101016 | 15       | 0.52%   |
| 0x010000dc | 15       | 0.52%   |
| 0xf49      | 14       | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 280      | 10.08%  |
| KabyLake         | 252      | 9.07%   |
| Penryn           | 233      | 8.39%   |
| SandyBridge      | 206      | 7.42%   |
| IvyBridge        | 184      | 6.63%   |
| Core             | 159      | 5.73%   |
| Zen 2            | 154      | 5.55%   |
| K10              | 149      | 5.37%   |
| Skylake          | 131      | 4.72%   |
| Zen 3            | 106      | 3.82%   |
| NetBurst         | 93       | 3.35%   |
| Zen+             | 92       | 3.31%   |
| Piledriver       | 92       | 3.31%   |
| Zen              | 90       | 3.24%   |
| K8 Hammer        | 75       | 2.7%    |
| CometLake        | 73       | 2.63%   |
| Nehalem          | 71       | 2.56%   |
| Westmere         | 62       | 2.23%   |
| Silvermont       | 51       | 1.84%   |
| Unknown          | 32       | 1.15%   |
| Alderlake Hybrid | 22       | 0.79%   |
| K10 Llano        | 21       | 0.76%   |
| Steamroller      | 20       | 0.72%   |
| Goldmont plus    | 20       | 0.72%   |
| Goldmont         | 19       | 0.68%   |
| Bonnell          | 17       | 0.61%   |
| Icelake          | 16       | 0.58%   |
| Excavator        | 16       | 0.58%   |
| Bulldozer        | 12       | 0.43%   |
| Jaguar           | 8        | 0.29%   |
| Puma             | 6        | 0.22%   |
| Tremont          | 5        | 0.18%   |
| Bobcat           | 5        | 0.18%   |
| Gracemont        | 2        | 0.07%   |
| Broadwell        | 2        | 0.07%   |
| K6               | 1        | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 1192     | 41.13%  |
| AMD                                          | 864      | 29.81%  |
| Intel                                        | 808      | 27.88%  |
| VIA Technologies                             | 11       | 0.38%   |
| Matrox Electronics Systems                   | 7        | 0.24%   |
| Silicon Integrated Systems [SiS]             | 6        | 0.21%   |
| ASPEED Technology                            | 5        | 0.17%   |
| XGI Technology (eXtreme Graphics Innovation) | 3        | 0.1%    |
| S3 Graphics                                  | 1        | 0.03%   |
| ATI Technologies                             | 1        | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 111      | 3.7%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 102      | 3.4%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 91       | 3.03%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 82       | 2.73%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 72       | 2.4%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 64       | 2.13%   |
| Nvidia GT218 [GeForce 210]                                                               | 62       | 2.07%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 59       | 1.97%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 44       | 1.47%   |
| Intel HD Graphics 530                                                                    | 43       | 1.43%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 39       | 1.3%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 39       | 1.3%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 39       | 1.3%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 38       | 1.27%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 38       | 1.27%   |
| Intel HD Graphics 630                                                                    | 37       | 1.23%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 37       | 1.23%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 36       | 1.2%    |
| Nvidia GF119 [GeForce GT 610]                                                            | 32       | 1.07%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 32       | 1.07%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 31       | 1.03%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 29       | 0.97%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 29       | 0.97%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 27       | 0.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 26       | 0.87%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 25       | 0.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 23       | 0.77%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 23       | 0.77%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 23       | 0.77%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 22       | 0.73%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 21       | 0.7%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 21       | 0.7%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 21       | 0.7%    |
| Intel Core Processor Integrated Graphics Controller                                      | 20       | 0.67%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 19       | 0.63%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                                      | 19       | 0.63%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 19       | 0.63%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 19       | 0.63%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 18       | 0.6%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 18       | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 1127     | 40.45%  |
| 1 x AMD              | 765      | 27.46%  |
| 1 x Intel            | 724      | 25.99%  |
| 2 x AMD              | 58       | 2.08%   |
| Intel + Nvidia       | 27       | 0.97%   |
| AMD + Nvidia         | 27       | 0.97%   |
| 1 x VIA              | 11       | 0.39%   |
| Intel + AMD          | 11       | 0.39%   |
| 2 x Nvidia           | 7        | 0.25%   |
| 1 x SiS              | 6        | 0.22%   |
| 1 x ASPEED           | 4        | 0.14%   |
| Other                | 3        | 0.11%   |
| 1 x XGI              | 3        | 0.11%   |
| Nvidia + Matrox      | 3        | 0.11%   |
| 1 x Matrox           | 3        | 0.11%   |
| 3 x AMD              | 1        | 0.04%   |
| 2 x Intel            | 1        | 0.04%   |
| 2 x AMD + 1 x Nvidia | 1        | 0.04%   |
| 1 x S3 Graphics      | 1        | 0.04%   |
| Nvidia + ASPEED      | 1        | 0.04%   |
| Intel + 2 x AMD      | 1        | 0.04%   |
| AMD + Matrox         | 1        | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 2112     | 74.52%  |
| Proprietary | 622      | 21.95%  |
| Unknown     | 100      | 3.53%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1113     | 38.61%  |
| 1.01-2.0   | 438      | 15.19%  |
| 0.01-0.5   | 381      | 13.22%  |
| 0.51-1.0   | 374      | 12.97%  |
| 3.01-4.0   | 208      | 7.21%   |
| 7.01-8.0   | 175      | 6.07%   |
| 5.01-6.0   | 107      | 3.71%   |
| 8.01-16.0  | 47       | 1.63%   |
| 2.01-3.0   | 38       | 1.32%   |
| 4.01-5.0   | 1        | 0.03%   |
| 16.01-24.0 | 1        | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 577      | 20.34%  |
| Hewlett-Packard      | 299      | 10.54%  |
| Goldstar             | 268      | 9.45%   |
| Philips              | 261      | 9.2%    |
| Ancor Communications | 234      | 8.25%   |
| Acer                 | 206      | 7.26%   |
| BenQ                 | 128      | 4.51%   |
| Dell                 | 124      | 4.37%   |
| AOC                  | 106      | 3.74%   |
| Lenovo               | 47       | 1.66%   |
| Unknown              | 39       | 1.37%   |
| Sony                 | 39       | 1.37%   |
| HannStar             | 39       | 1.37%   |
| LG Electronics       | 38       | 1.34%   |
| ASUSTek Computer     | 35       | 1.23%   |
| MSI                  | 21       | 0.74%   |
| Fujitsu Siemens      | 19       | 0.67%   |
| Eizo                 | 17       | 0.6%    |
| Packard Bell         | 13       | 0.46%   |
| NEC Computers        | 13       | 0.46%   |
| Mi                   | 10       | 0.35%   |
| Belinea              | 10       | 0.35%   |
| Sharp                | 9        | 0.32%   |
| HPN                  | 9        | 0.32%   |
| ViewSonic            | 8        | 0.28%   |
| Vestel Elektronik    | 8        | 0.28%   |
| Panasonic            | 8        | 0.28%   |
| MiTAC                | 8        | 0.28%   |
| Iiyama               | 8        | 0.28%   |
| CVT                  | 8        | 0.28%   |
| QBell                | 7        | 0.25%   |
| OEM                  | 7        | 0.25%   |
| HKC                  | 7        | 0.25%   |
| RTK                  | 6        | 0.21%   |
| Lenovo Group Limited | 6        | 0.21%   |
| HannStar Display     | 6        | 0.21%   |
| ___                  | 5        | 0.18%   |
| Microstep            | 5        | 0.18%   |
| Hyundai ImageQuest   | 5        | 0.18%   |
| Compaq Computer      | 5        | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 30       | 1%      |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 19       | 0.63%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 19       | 0.63%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 15       | 0.5%    |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 13       | 0.43%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                   | 13       | 0.43%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch             | 13       | 0.43%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 12       | 0.4%    |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 12       | 0.4%    |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 12       | 0.4%    |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                       | 12       | 0.4%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 11       | 0.37%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 477x268mm 21.5-inch     | 10       | 0.33%   |
| AOC 27B2 AOC2702 1920x1080 598x336mm 27.0-inch                        | 10       | 0.33%   |
| Acer X223W ACR000D 1680x1050 474x296mm 22.0-inch                      | 10       | 0.33%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch               | 9        | 0.3%    |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch            | 9        | 0.3%    |
| Hewlett-Packard 27f HPN354A 1920x1080 598x336mm 27.0-inch             | 9        | 0.3%    |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 9        | 0.3%    |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch | 9        | 0.3%    |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch    | 8        | 0.27%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch  | 8        | 0.27%   |
| Samsung Electronics C27F390 SAM0D33 1920x1080 598x336mm 27.0-inch     | 8        | 0.27%   |
| Hewlett-Packard 27fw HPN354B 1920x1080 598x336mm 27.0-inch            | 8        | 0.27%   |
| Hewlett-Packard 22w HPN342E 1920x1080 476x268mm 21.5-inch             | 8        | 0.27%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 8        | 0.27%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 8        | 0.27%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                | 8        | 0.27%   |
| Ancor Communications VE228 ACI22FA 1920x1080 531x299mm 24.0-inch      | 8        | 0.27%   |
| Acer K222HQL ACR03E1 1920x1080 477x268mm 21.5-inch                    | 8        | 0.27%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 7        | 0.23%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 7        | 0.23%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 7        | 0.23%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                    | 7        | 0.23%   |
| Hewlett-Packard 27f HPN354C 1920x1080 598x336mm 27.0-inch             | 7        | 0.23%   |
| Hewlett-Packard 24w HPN3431 1920x1080 527x296mm 23.8-inch             | 7        | 0.23%   |
| Dell 2009W DEL4042 1680x1050 433x271mm 20.1-inch                      | 7        | 0.23%   |
| BenQ GW2280 BNQ78E8 1920x1080 476x268mm 21.5-inch                     | 7        | 0.23%   |
| AOC 24V2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 7        | 0.23%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 7        | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1329     | 47.6%   |
| 1280x1024 (SXGA)   | 300      | 10.74%  |
| 3840x2160 (4K)     | 189      | 6.77%   |
| 1680x1050 (WSXGA+) | 178      | 6.38%   |
| 1440x900 (WXGA+)   | 160      | 5.73%   |
| 2560x1440 (QHD)    | 144      | 5.16%   |
| 1366x768 (WXGA)    | 69       | 2.47%   |
| 1360x768           | 59       | 2.11%   |
| Unknown            | 56       | 2.01%   |
| 1920x1200 (WUXGA)  | 47       | 1.68%   |
| 1600x900 (HD+)     | 46       | 1.65%   |
| 2560x1080          | 37       | 1.33%   |
| 1024x768 (XGA)     | 31       | 1.11%   |
| 3840x1080          | 28       | 1%      |
| 3440x1440          | 25       | 0.9%    |
| 1600x1200          | 13       | 0.47%   |
| 1920x540           | 12       | 0.43%   |
| 1280x720 (HD)      | 11       | 0.39%   |
| 1280x768           | 5        | 0.18%   |
| 4480x1440          | 4        | 0.14%   |
| 2560x1600          | 4        | 0.14%   |
| 3840x1600          | 3        | 0.11%   |
| 3200x1080          | 3        | 0.11%   |
| 2288x1287          | 3        | 0.11%   |
| 8960x2160          | 2        | 0.07%   |
| 5760x1080          | 2        | 0.07%   |
| 5120x1440          | 2        | 0.07%   |
| 2640x1024          | 2        | 0.07%   |
| 2304x1024          | 2        | 0.07%   |
| 2048x1152          | 2        | 0.07%   |
| 1818x1022          | 2        | 0.07%   |
| 6784x2160          | 1        | 0.04%   |
| 5760x2160          | 1        | 0.04%   |
| 5520x2160          | 1        | 0.04%   |
| 4480x1080          | 1        | 0.04%   |
| 4093x4093          | 1        | 0.04%   |
| 3968x1152          | 1        | 0.04%   |
| 3840x1920          | 1        | 0.04%   |
| 3840x1200          | 1        | 0.04%   |
| 3520x1080          | 1        | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 378      | 13.24%  |
| 24      | 365      | 12.78%  |
| 27      | 358      | 12.54%  |
| Unknown | 326      | 11.42%  |
| 23      | 272      | 9.53%   |
| 19      | 254      | 8.9%    |
| 17      | 143      | 5.01%   |
| 18      | 122      | 4.27%   |
| 20      | 99       | 3.47%   |
| 22      | 98       | 3.43%   |
| 31      | 67       | 2.35%   |
| 34      | 61       | 2.14%   |
| 15      | 51       | 1.79%   |
| 40      | 34       | 1.19%   |
| 54      | 28       | 0.98%   |
| 72      | 26       | 0.91%   |
| 84      | 24       | 0.84%   |
| 25      | 17       | 0.6%    |
| 32      | 16       | 0.56%   |
| 28      | 12       | 0.42%   |
| 52      | 9        | 0.32%   |
| 48      | 8        | 0.28%   |
| 42      | 8        | 0.28%   |
| 46      | 6        | 0.21%   |
| 36      | 6        | 0.21%   |
| 39      | 5        | 0.18%   |
| 37      | 5        | 0.18%   |
| 29      | 5        | 0.18%   |
| 12      | 5        | 0.18%   |
| 65      | 4        | 0.14%   |
| 33      | 4        | 0.14%   |
| 26      | 4        | 0.14%   |
| 142     | 3        | 0.11%   |
| 75      | 3        | 0.11%   |
| 60      | 3        | 0.11%   |
| 50      | 3        | 0.11%   |
| 43      | 3        | 0.11%   |
| 16      | 3        | 0.11%   |
| 14      | 3        | 0.11%   |
| 59      | 2        | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 932      | 33.37%  |
| 401-500        | 792      | 28.36%  |
| Unknown        | 326      | 11.67%  |
| 301-350        | 191      | 6.84%   |
| 351-400        | 160      | 5.73%   |
| 601-700        | 114      | 4.08%   |
| 701-800        | 86       | 3.08%   |
| 1001-1500      | 67       | 2.4%    |
| 1501-2000      | 55       | 1.97%   |
| 801-900        | 46       | 1.65%   |
| 901-1000       | 11       | 0.39%   |
| 201-300        | 9        | 0.32%   |
| More than 2000 | 3        | 0.11%   |
| 101-200        | 1        | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1611     | 59.53%  |
| 16/10   | 374      | 13.82%  |
| 5/4     | 287      | 10.61%  |
| Unknown | 278      | 10.27%  |
| 4/3     | 66       | 2.44%   |
| 21/9    | 62       | 2.29%   |
| 6/5     | 9        | 0.33%   |
| 3/2     | 9        | 0.33%   |
| 32/9    | 6        | 0.22%   |
| 1.00    | 3        | 0.11%   |
| 2.65    | 1        | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 900      | 32.11%  |
| 151-200        | 488      | 17.41%  |
| 301-350        | 363      | 12.95%  |
| Unknown        | 326      | 11.63%  |
| 141-150        | 210      | 7.49%   |
| 351-500        | 152      | 5.42%   |
| More than 1000 | 112      | 4%      |
| 251-300        | 109      | 3.89%   |
| 501-1000       | 78       | 2.78%   |
| 101-110        | 49       | 1.75%   |
| 71-80          | 7        | 0.25%   |
| 131-140        | 4        | 0.14%   |
| 91-100         | 2        | 0.07%   |
| 81-90          | 1        | 0.04%   |
| 1-40           | 1        | 0.04%   |
| 111-120        | 1        | 0.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 1690     | 62.11%  |
| 101-120       | 502      | 18.45%  |
| Unknown       | 326      | 11.98%  |
| 1-50          | 102      | 3.75%   |
| 121-160       | 73       | 2.68%   |
| 161-240       | 27       | 0.99%   |
| More than 240 | 1        | 0.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2339     | 83.24%  |
| 2     | 326      | 11.6%   |
| 0     | 110      | 3.91%   |
| 3     | 35       | 1.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 1694     | 42.83%  |
| Intel                                 | 1020     | 25.79%  |
| Qualcomm Atheros                      | 252      | 6.37%   |
| Broadcom                              | 109      | 2.76%   |
| Nvidia                                | 99       | 2.5%    |
| TP-Link                               | 98       | 2.48%   |
| Ralink Technology                     | 88       | 2.23%   |
| Marvell Technology Group              | 67       | 1.69%   |
| Ralink                                | 46       | 1.16%   |
| Qualcomm Atheros Communications       | 41       | 1.04%   |
| D-Link System                         | 37       | 0.94%   |
| Broadcom Limited                      | 36       | 0.91%   |
| D-Link                                | 31       | 0.78%   |
| VIA Technologies                      | 29       | 0.73%   |
| Huawei Technologies                   | 26       | 0.66%   |
| MediaTek                              | 25       | 0.63%   |
| Sitecom Europe                        | 24       | 0.61%   |
| Xiaomi                                | 22       | 0.56%   |
| Samsung Electronics                   | 22       | 0.56%   |
| NetGear                               | 21       | 0.53%   |
| ASUSTek Computer                      | 18       | 0.46%   |
| Microsoft                             | 15       | 0.38%   |
| ASIX Electronics                      | 12       | 0.3%    |
| Gemtek                                | 9        | 0.23%   |
| Belkin Components                     | 8        | 0.2%    |
| Aquantia                              | 8        | 0.2%    |
| Silicon Integrated Systems [SiS]      | 7        | 0.18%   |
| OPPO Electronics                      | 6        | 0.15%   |
| DisplayLink                           | 6        | 0.15%   |
| AVM                                   | 6        | 0.15%   |
| 3Com                                  | 6        | 0.15%   |
| Linksys                               | 5        | 0.13%   |
| ZTE WCDMA Technologies MSM            | 4        | 0.1%    |
| OnePlus Technology (Shenzhen)         | 3        | 0.08%   |
| Motorola                              | 3        | 0.08%   |
| Microchip Technology                  | 3        | 0.08%   |
| Google                                | 3        | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3        | 0.08%   |
| ZyDAS                                 | 2        | 0.05%   |
| Smart Link                            | 2        | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1349     | 30.49%  |
| Intel Ethernet Connection (2) I219-V                              | 118      | 2.67%   |
| Intel I211 Gigabit Network Connection                             | 114      | 2.58%   |
| Intel Wi-Fi 6 AX200                                               | 108      | 2.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 101      | 2.28%   |
| Realtek RTL8125 2.5GbE Controller                                 | 85       | 1.92%   |
| Intel 82579V Gigabit Network Connection                           | 70       | 1.58%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 54       | 1.22%   |
| Intel Ethernet Controller I225-V                                  | 54       | 1.22%   |
| Intel Ethernet Connection I217-LM                                 | 47       | 1.06%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 45       | 1.02%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 43       | 0.97%   |
| Intel Ethernet Connection (7) I219-V                              | 42       | 0.95%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 39       | 0.88%   |
| Realtek 802.11ac NIC                                              | 39       | 0.88%   |
| Nvidia MCP61 Ethernet                                             | 39       | 0.88%   |
| Qualcomm Atheros AR9271 802.11n                                   | 38       | 0.86%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 37       | 0.84%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 37       | 0.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 35       | 0.79%   |
| Intel Wireless 7265                                               | 35       | 0.79%   |
| Intel Ethernet Connection I217-V                                  | 34       | 0.77%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 32       | 0.72%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 30       | 0.68%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 28       | 0.63%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 25       | 0.56%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 25       | 0.56%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 25       | 0.56%   |
| Ralink MT7601U Wireless Adapter                                   | 25       | 0.56%   |
| Intel Wireless-AC 9260                                            | 24       | 0.54%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 24       | 0.54%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 23       | 0.52%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 20       | 0.45%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 20       | 0.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 19       | 0.43%   |
| Intel Ethernet Connection (2) I218-V                              | 19       | 0.43%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 18       | 0.41%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 18       | 0.41%   |
| Nvidia MCP77 Ethernet                                             | 17       | 0.38%   |
| Intel Wireless 3165                                               | 17       | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 346      | 26.37%  |
| Intel                                 | 324      | 24.7%   |
| Qualcomm Atheros                      | 129      | 9.83%   |
| TP-Link                               | 93       | 7.09%   |
| Ralink Technology                     | 88       | 6.71%   |
| Ralink                                | 46       | 3.51%   |
| Broadcom                              | 43       | 3.28%   |
| Qualcomm Atheros Communications       | 41       | 3.13%   |
| D-Link                                | 31       | 2.36%   |
| D-Link System                         | 29       | 2.21%   |
| Sitecom Europe                        | 24       | 1.83%   |
| NetGear                               | 20       | 1.52%   |
| MediaTek                              | 18       | 1.37%   |
| ASUSTek Computer                      | 17       | 1.3%    |
| Microsoft                             | 14       | 1.07%   |
| Gemtek                                | 9        | 0.69%   |
| Belkin Components                     | 8        | 0.61%   |
| Broadcom Limited                      | 6        | 0.46%   |
| AVM                                   | 6        | 0.46%   |
| Linksys                               | 5        | 0.38%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3        | 0.23%   |
| ZyDAS                                 | 2        | 0.15%   |
| Edimax Technology                     | 2        | 0.15%   |
| ZyXEL Communications                  | 1        | 0.08%   |
| Wilocity                              | 1        | 0.08%   |
| Wacom                                 | 1        | 0.08%   |
| Sierra Wireless                       | 1        | 0.08%   |
| Samsung Electronics                   | 1        | 0.08%   |
| Fiberline                             | 1        | 0.08%   |
| Accton Technology                     | 1        | 0.08%   |
| AboCom Systems                        | 1        | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                        | 108      | 8.13%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                         | 39       | 2.94%   |
| Realtek 802.11ac NIC                                                       | 39       | 2.94%   |
| Qualcomm Atheros AR9271 802.11n                                            | 38       | 2.86%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 37       | 2.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 35       | 2.64%   |
| Intel Wireless 7265                                                        | 35       | 2.64%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                | 28       | 2.11%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                            | 25       | 1.88%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                     | 25       | 1.88%   |
| Ralink MT7601U Wireless Adapter                                            | 25       | 1.88%   |
| Intel Wireless-AC 9260                                                     | 24       | 1.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 24       | 1.81%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 20       | 1.51%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                 | 18       | 1.36%   |
| Intel Wireless 3165                                                        | 17       | 1.28%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                         | 17       | 1.28%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 16       | 1.2%    |
| Ralink RT5370 Wireless Adapter                                             | 15       | 1.13%   |
| Ralink RT2501/RT2573 Wireless Adapter                                      | 15       | 1.13%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                           | 15       | 1.13%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                         | 15       | 1.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 14       | 1.05%   |
| Intel Wireless 7260                                                        | 14       | 1.05%   |
| Intel Comet Lake PCH CNVi WiFi                                             | 14       | 1.05%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                   | 13       | 0.98%   |
| Ralink RT2870/RT3070 Wireless Adapter                                      | 13       | 0.98%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 12       | 0.9%    |
| Intel Tiger Lake PCH CNVi WiFi                                             | 12       | 0.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                            | 12       | 0.9%    |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 12       | 0.9%    |
| TP-Link 802.11ac WLAN Adapter                                              | 11       | 0.83%   |
| Realtek RTL8187 Wireless Adapter                                           | 11       | 0.83%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                  | 11       | 0.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 11       | 0.83%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]         | 11       | 0.83%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                      | 10       | 0.75%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 10       | 0.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 10       | 0.75%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                    | 9        | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 1570     | 52.33%  |
| Intel                             | 839      | 27.97%  |
| Qualcomm Atheros                  | 144      | 4.8%    |
| Nvidia                            | 99       | 3.3%    |
| Broadcom                          | 68       | 2.27%   |
| Marvell Technology Group          | 67       | 2.23%   |
| Broadcom Limited                  | 30       | 1%      |
| VIA Technologies                  | 27       | 0.9%    |
| Huawei Technologies               | 24       | 0.8%    |
| Xiaomi                            | 22       | 0.73%   |
| Samsung Electronics               | 21       | 0.7%    |
| ASIX Electronics                  | 12       | 0.4%    |
| D-Link System                     | 8        | 0.27%   |
| Aquantia                          | 8        | 0.27%   |
| Silicon Integrated Systems [SiS]  | 7        | 0.23%   |
| MediaTek                          | 7        | 0.23%   |
| OPPO Electronics                  | 6        | 0.2%    |
| DisplayLink                       | 6        | 0.2%    |
| 3Com                              | 6        | 0.2%    |
| TP-Link                           | 5        | 0.17%   |
| ZTE WCDMA Technologies MSM        | 4        | 0.13%   |
| Google                            | 3        | 0.1%    |
| Qualcomm                          | 2        | 0.07%   |
| OnePlus Technology (Shenzhen)     | 2        | 0.07%   |
| Motorola PCS                      | 2        | 0.07%   |
| ULi Electronics                   | 1        | 0.03%   |
| Tehuti Networks                   | 1        | 0.03%   |
| SysKonnect                        | 1        | 0.03%   |
| Sundance Technology Inc / IC Plus | 1        | 0.03%   |
| NetGear                           | 1        | 0.03%   |
| LG Electronics                    | 1        | 0.03%   |
| JMicron Technology                | 1        | 0.03%   |
| HTC (High Tech Computer)          | 1        | 0.03%   |
| HMD Global                        | 1        | 0.03%   |
| Compal Electronics                | 1        | 0.03%   |
| ASUSTek Computer                  | 1        | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1349     | 44.04%  |
| Intel Ethernet Connection (2) I219-V                              | 118      | 3.85%   |
| Intel I211 Gigabit Network Connection                             | 114      | 3.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 101      | 3.3%    |
| Realtek RTL8125 2.5GbE Controller                                 | 85       | 2.78%   |
| Intel 82579V Gigabit Network Connection                           | 70       | 2.29%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 54       | 1.76%   |
| Intel Ethernet Controller I225-V                                  | 54       | 1.76%   |
| Intel Ethernet Connection I217-LM                                 | 47       | 1.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 45       | 1.47%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 43       | 1.4%    |
| Intel Ethernet Connection (7) I219-V                              | 42       | 1.37%   |
| Nvidia MCP61 Ethernet                                             | 39       | 1.27%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 37       | 1.21%   |
| Intel Ethernet Connection I217-V                                  | 34       | 1.11%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 32       | 1.04%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 30       | 0.98%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 25       | 0.82%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 23       | 0.75%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 20       | 0.65%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 19       | 0.62%   |
| Intel Ethernet Connection (2) I218-V                              | 19       | 0.62%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 18       | 0.59%   |
| Nvidia MCP77 Ethernet                                             | 17       | 0.56%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 16       | 0.52%   |
| Nvidia MCP73 Ethernet                                             | 15       | 0.49%   |
| Intel 82578DM Gigabit Network Connection                          | 15       | 0.49%   |
| Intel 82578DC Gigabit Network Connection                          | 15       | 0.49%   |
| Intel 82574L Gigabit Network Connection                           | 15       | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 14       | 0.46%   |
| Intel Ethernet Connection (2) I219-LM                             | 14       | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 13       | 0.42%   |
| Intel NM10/ICH7 Family LAN Controller                             | 13       | 0.42%   |
| Huawei JKM-LX1                                                    | 13       | 0.42%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 12       | 0.39%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 12       | 0.39%   |
| Intel I210 Gigabit Network Connection                             | 12       | 0.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11       | 0.36%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 11       | 0.36%   |
| Intel 82567V-2 Gigabit Network Connection                         | 11       | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2743     | 68.71%  |
| WiFi     | 1216     | 30.46%  |
| Modem    | 29       | 0.73%   |
| Unknown  | 4        | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2114     | 74.78%  |
| WiFi     | 712      | 25.19%  |
| Unknown  | 1        | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1873     | 67.35%  |
| 2     | 793      | 28.51%  |
| 3     | 87       | 3.13%   |
| 0     | 15       | 0.54%   |
| 4     | 6        | 0.22%   |
| 5     | 3        | 0.11%   |
| 12    | 2        | 0.07%   |
| 6     | 2        | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2619     | 94.01%  |
| Yes  | 167      | 5.99%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 292      | 36.32%  |
| Cambridge Silicon Radio         | 215      | 26.74%  |
| Realtek Semiconductor           | 86       | 10.7%   |
| Broadcom                        | 50       | 6.22%   |
| ASUSTek Computer                | 45       | 5.6%    |
| Qualcomm Atheros Communications | 23       | 2.86%   |
| IMC Networks                    | 14       | 1.74%   |
| MediaTek                        | 13       | 1.62%   |
| Apple                           | 13       | 1.62%   |
| TP-Link                         | 11       | 1.37%   |
| Integrated System Solution      | 8        | 1%      |
| Belkin Components               | 5        | 0.62%   |
| Lite-On Technology              | 4        | 0.5%    |
| Sitecom Europe                  | 3        | 0.37%   |
| Realtek                         | 3        | 0.37%   |
| SINO WEALTH                     | 2        | 0.25%   |
| Foxconn / Hon Hai               | 2        | 0.25%   |
| D-Link System                   | 2        | 0.25%   |
| Conwise Technology              | 2        | 0.25%   |
| Accel Semiconductor             | 2        | 0.25%   |
| Logitech                        | 1        | 0.12%   |
| ISSC                            | 1        | 0.12%   |
| HTC (High Tech Computer)        | 1        | 0.12%   |
| Hewlett-Packard                 | 1        | 0.12%   |
| Fujitsu Siemens Computers       | 1        | 0.12%   |
| Fujitsu                         | 1        | 0.12%   |
| Dell                            | 1        | 0.12%   |
| D-Link                          | 1        | 0.12%   |
| 3Com                            | 1        | 0.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 215      | 26.71%  |
| Intel AX200 Bluetooth                                 | 95       | 11.8%   |
| Intel Bluetooth wireless interface                    | 70       | 8.7%    |
| Realtek Bluetooth Radio                               | 64       | 7.95%   |
| Intel AX201 Bluetooth                                 | 37       | 4.6%    |
| Intel Wireless-AC 3168 Bluetooth                      | 25       | 3.11%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 22       | 2.73%   |
| Realtek  Bluetooth 4.2 Adapter                        | 20       | 2.48%   |
| Intel AX210 Bluetooth                                 | 19       | 2.36%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 19       | 2.36%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 16       | 1.99%   |
| Broadcom BCM2045 Bluetooth                            | 15       | 1.86%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 14       | 1.74%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 14       | 1.74%   |
| MediaTek Wireless_Device                              | 13       | 1.61%   |
| TP-Link UB5A Adapter                                  | 11       | 1.37%   |
| Apple Bluetooth Host Controller                       | 10       | 1.24%   |
| IMC Networks Bluetooth Device                         | 7        | 0.87%   |
| ASUS BCM20702A0                                       | 7        | 0.87%   |
| Qualcomm Atheros  Bluetooth Device                    | 6        | 0.75%   |
| Intel Bluetooth Device                                | 6        | 0.75%   |
| ASUS Qualcomm Bluetooth 4.1                           | 6        | 0.75%   |
| ASUS Bluetooth Radio                                  | 6        | 0.75%   |
| ASUS Bluetooth Adapter                                | 6        | 0.75%   |
| IMC Networks Bluetooth Radio                          | 5        | 0.62%   |
| Lite-On Bluetooth Device                              | 4        | 0.5%    |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 4        | 0.5%    |
| Integrated System Solution Bluetooth Device           | 4        | 0.5%    |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter      | 4        | 0.5%    |
| Realtek Bluetooth Radio                               | 3        | 0.37%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 3        | 0.37%   |
| Broadcom BCM2035 Bluetooth dongle                     | 3        | 0.37%   |
| Belkin Components F8T012 Bluetooth Adapter            | 3        | 0.37%   |
| ASUS Bluetooth Device                                 | 3        | 0.37%   |
| SINO WEALTH RK Bluetooth Keyboard                     | 2        | 0.25%   |
| Realtek RTL8821A Bluetooth                            | 2        | 0.25%   |
| D-Link System DBT-122 Bluetooth                       | 2        | 0.25%   |
| Conwise CW6622                                        | 2        | 0.25%   |
| Broadcom Bluetooth 3.0 Device                         | 2        | 0.25%   |
| Apple Bluetooth HCI                                   | 2        | 0.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 1775     | 39.1%   |
| Nvidia                                       | 1078     | 23.74%  |
| AMD                                          | 1060     | 23.35%  |
| C-Media Electronics                          | 138      | 3.04%   |
| Creative Labs                                | 57       | 1.26%   |
| Logitech                                     | 39       | 0.86%   |
| VIA Technologies                             | 36       | 0.79%   |
| Razer USA                                    | 21       | 0.46%   |
| Focusrite-Novation                           | 17       | 0.37%   |
| JMTek                                        | 16       | 0.35%   |
| Texas Instruments                            | 15       | 0.33%   |
| Creative Technology                          | 15       | 0.33%   |
| Micro Star International                     | 13       | 0.29%   |
| ASUSTek Computer                             | 13       | 0.29%   |
| M-Audio                                      | 12       | 0.26%   |
| Kingston Technology                          | 12       | 0.26%   |
| Generalplus Technology                       | 11       | 0.24%   |
| Tenx Technology                              | 10       | 0.22%   |
| Silicon Integrated Systems [SiS]             | 9        | 0.2%    |
| GN Netcom                                    | 9        | 0.2%    |
| BEHRINGER International                      | 9        | 0.2%    |
| Samson Technologies                          | 8        | 0.18%   |
| Trust                                        | 7        | 0.15%   |
| Thesycon Systemsoftware & Consulting         | 7        | 0.15%   |
| Ensoniq                                      | 7        | 0.15%   |
| Dell                                         | 7        | 0.15%   |
| Plantronics                                  | 6        | 0.13%   |
| Microsoft                                    | 6        | 0.13%   |
| Corsair                                      | 6        | 0.13%   |
| SAVITECH                                     | 5        | 0.11%   |
| Hewlett-Packard                              | 5        | 0.11%   |
| Yamaha                                       | 4        | 0.09%   |
| Sony                                         | 4        | 0.09%   |
| Realtek Semiconductor                        | 4        | 0.09%   |
| Cambridge Silicon Radio                      | 4        | 0.09%   |
| Zoran Co. Personal Media Division (Nogatech) | 3        | 0.07%   |
| XMOS                                         | 3        | 0.07%   |
| SteelSeries ApS                              | 3        | 0.07%   |
| Sennheiser Communications                    | 3        | 0.07%   |
| KTMicro                                      | 3        | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 206      | 4%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 202      | 3.92%   |
| AMD Starship/Matisse HD Audio Controller                                          | 202      | 3.92%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 179      | 3.47%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 170      | 3.3%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 146      | 2.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 145      | 2.81%   |
| AMD Family 17h/19h HD Audio Controller                                            | 129      | 2.5%    |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 126      | 2.45%   |
| Intel 200 Series PCH HD Audio                                                     | 123      | 2.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 116      | 2.25%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 109      | 2.12%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 106      | 2.06%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 98       | 1.9%    |
| Nvidia GP107GL High Definition Audio Controller                                   | 94       | 1.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 92       | 1.79%   |
| Intel Cannon Lake PCH cAVS                                                        | 91       | 1.77%   |
| Nvidia High Definition Audio Controller                                           | 88       | 1.71%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 85       | 1.65%   |
| AMD FCH Azalia Controller                                                         | 85       | 1.65%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 65       | 1.26%   |
| Nvidia GP106 High Definition Audio Controller                                     | 63       | 1.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 61       | 1.18%   |
| Nvidia GF108 High Definition Audio Controller                                     | 60       | 1.16%   |
| Nvidia GF119 HDMI Audio Controller                                                | 56       | 1.09%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 55       | 1.07%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 54       | 1.05%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 53       | 1.03%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 51       | 0.99%   |
| Nvidia TU116 High Definition Audio Controller                                     | 50       | 0.97%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 50       | 0.97%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 50       | 0.97%   |
| Nvidia MCP61 High Definition Audio                                                | 47       | 0.91%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 47       | 0.91%   |
| AMD Navi 10 HDMI Audio                                                            | 45       | 0.87%   |
| Nvidia GP108 High Definition Audio Controller                                     | 43       | 0.83%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 42       | 0.82%   |
| Nvidia GK107 HDMI Audio Controller                                                | 36       | 0.7%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 36       | 0.7%    |
| Nvidia GP104 High Definition Audio Controller                                     | 35       | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 311      | 18.65%  |
| Unknown                      | 258      | 15.47%  |
| Corsair                      | 254      | 15.23%  |
| Crucial                      | 179      | 10.73%  |
| Samsung Electronics          | 149      | 8.93%   |
| SK hynix                     | 119      | 7.13%   |
| G.Skill                      | 88       | 5.28%   |
| Micron Technology            | 79       | 4.74%   |
| Team                         | 29       | 1.74%   |
| A-DATA Technology            | 27       | 1.62%   |
| Patriot                      | 26       | 1.56%   |
| Ramaxel Technology           | 17       | 1.02%   |
| Nanya Technology             | 17       | 1.02%   |
| Unknown                      | 17       | 1.02%   |
| Unknown (ABCD)               | 16       | 0.96%   |
| Elpida                       | 13       | 0.78%   |
| Transcend                    | 9        | 0.54%   |
| Unifosa                      | 6        | 0.36%   |
| ASint Technology             | 6        | 0.36%   |
| Patriot Memory (PDP Systems) | 4        | 0.24%   |
| GOODRAM                      | 4        | 0.24%   |
| Unknown (AB)                 | 3        | 0.18%   |
| Hewlett-Packard              | 3        | 0.18%   |
| GeIL                         | 3        | 0.18%   |
| Silicon Power                | 2        | 0.12%   |
| Qimonda                      | 2        | 0.12%   |
| PUSKILL                      | 2        | 0.12%   |
| PLEXHD                       | 2        | 0.12%   |
| Netac                        | 2        | 0.12%   |
| CSX                          | 2        | 0.12%   |
| A Force                      | 2        | 0.12%   |
| Wodposit                     | 1        | 0.06%   |
| V-Color                      | 1        | 0.06%   |
| Unknown (0x0E9D)             | 1        | 0.06%   |
| TwinMOS                      | 1        | 0.06%   |
| Toshiba                      | 1        | 0.06%   |
| Thermaltake                  | 1        | 0.06%   |
| KomputerBay                  | 1        | 0.06%   |
| Kllisre                      | 1        | 0.06%   |
| Kingmax                      | 1        | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 37       | 1.99%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s          | 21       | 1.13%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 20       | 1.07%   |
| Unknown                                                        | 17       | 0.91%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM LPDDR4 2400MT/s | 16       | 0.86%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s           | 14       | 0.75%   |
| Unknown RAM Module 4096MB DIMM DDR2 266MT/s                    | 13       | 0.7%    |
| Unknown RAM Module 2048MB DIMM SDRAM                           | 13       | 0.7%    |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s          | 13       | 0.7%    |
| Unknown RAM Module 2GB DIMM SDRAM                              | 12       | 0.64%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s            | 11       | 0.59%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s           | 10       | 0.54%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 9        | 0.48%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s            | 9        | 0.48%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s             | 9        | 0.48%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s         | 9        | 0.48%   |
| Crucial RAM BL8G36C16U4B.M8FE1 8GB DIMM DDR4 3733MT/s          | 9        | 0.48%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1800MT/s            | 9        | 0.48%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 8        | 0.43%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s            | 8        | 0.43%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s            | 8        | 0.43%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s         | 8        | 0.43%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s            | 7        | 0.38%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3266MT/s            | 7        | 0.38%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 7        | 0.38%   |
| Kingston RAM KHX2133C14/8G 8192MB DIMM DDR4 2400MT/s           | 7        | 0.38%   |
| Kingston RAM 99U5471-020.A00LF 4096MB DIMM DDR3 1600MT/s       | 7        | 0.38%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s         | 7        | 0.38%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 6        | 0.32%   |
| Unknown RAM Module 512MB DIMM SDRAM                            | 6        | 0.32%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                        | 6        | 0.32%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                    | 6        | 0.32%   |
| Unknown RAM Module 1024MB DIMM                                 | 6        | 0.32%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s             | 6        | 0.32%   |
| Team RAM TEAMGROUP-UD4-2400 4GB DIMM DDR4 2400MT/s             | 6        | 0.32%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                     | 6        | 0.32%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s            | 6        | 0.32%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s            | 6        | 0.32%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s              | 6        | 0.32%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s            | 6        | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 644      | 43.05%  |
| DDR3    | 487      | 32.55%  |
| DDR2    | 136      | 9.09%   |
| SDRAM   | 97       | 6.48%   |
| Unknown | 67       | 4.48%   |
| DDR     | 24       | 1.6%    |
| LPDDR4  | 19       | 1.27%   |
| DDR5    | 16       | 1.07%   |
| LPDDR3  | 5        | 0.33%   |
| DRAM    | 1        | 0.07%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 1355     | 93.84%  |
| SODIMM       | 83       | 5.75%   |
| FB-DIMM      | 4        | 0.28%   |
| Row Of Chips | 2        | 0.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 583      | 35.92%  |
| 4096  | 386      | 23.78%  |
| 2048  | 287      | 17.68%  |
| 16384 | 202      | 12.45%  |
| 1024  | 92       | 5.67%   |
| 32768 | 46       | 2.83%   |
| 512   | 20       | 1.23%   |
| 256   | 4        | 0.25%   |
| 3072  | 2        | 0.12%   |
| 32    | 1        | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 274      | 16.67%  |
| 1333    | 177      | 10.77%  |
| 3600    | 130      | 7.91%   |
| 3200    | 128      | 7.79%   |
| 2400    | 100      | 6.08%   |
| 800     | 80       | 4.87%   |
| 2667    | 70       | 4.26%   |
| 2133    | 50       | 3.04%   |
| Unknown | 48       | 2.92%   |
| 667     | 46       | 2.8%    |
| 1867    | 44       | 2.68%   |
| 3400    | 35       | 2.13%   |
| 3000    | 34       | 2.07%   |
| 1800    | 33       | 2.01%   |
| 2933    | 32       | 1.95%   |
| 3733    | 22       | 1.34%   |
| 3533    | 22       | 1.34%   |
| 1866    | 22       | 1.34%   |
| 1066    | 22       | 1.34%   |
| 3666    | 21       | 1.28%   |
| 2666    | 16       | 0.97%   |
| 3800    | 15       | 0.91%   |
| 266     | 15       | 0.91%   |
| 400     | 14       | 0.85%   |
| 1334    | 13       | 0.79%   |
| 3266    | 11       | 0.67%   |
| 533     | 11       | 0.67%   |
| 2800    | 9        | 0.55%   |
| 4800    | 8        | 0.49%   |
| 2000    | 8        | 0.49%   |
| 333     | 7        | 0.43%   |
| 3500    | 6        | 0.36%   |
| 3466    | 6        | 0.36%   |
| 2048    | 6        | 0.36%   |
| 49926   | 5        | 0.3%    |
| 3866    | 5        | 0.3%    |
| 1639    | 5        | 0.3%    |
| 1400    | 5        | 0.3%    |
| 1067    | 5        | 0.3%    |
| 52217   | 4        | 0.24%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 88       | 38.77%  |
| Samsung Electronics   | 34       | 14.98%  |
| Canon                 | 31       | 13.66%  |
| Seiko Epson           | 28       | 12.33%  |
| Brother Industries    | 25       | 11.01%  |
| Lexmark International | 4        | 1.76%   |
| Xerox                 | 3        | 1.32%   |
| Prolific Technology   | 2        | 0.88%   |
| Oki Data              | 2        | 0.88%   |
| Dymo-CoStar           | 2        | 0.88%   |
| Toshiba TEC           | 1        | 0.44%   |
| STMicroelectronics    | 1        | 0.44%   |
| Sato                  | 1        | 0.44%   |
| Ricoh                 | 1        | 0.44%   |
| QinHeng Electronics   | 1        | 0.44%   |
| Pantum                | 1        | 0.44%   |
| Kyocera               | 1        | 0.44%   |
| Apple                 | 1        | 0.44%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung M2020 Series                                                  | 9        | 3.96%   |
| Seiko Epson WF-2510 Series                                            | 7        | 3.08%   |
| HP OfficeJet 6950                                                     | 7        | 3.08%   |
| HP Deskjet 2050 J510                                                  | 6        | 2.64%   |
| Canon LiDE 400                                                        | 5        | 2.2%    |
| Seiko Epson Printer                                                   | 4        | 1.76%   |
| Samsung ML-216x Series Laser Printer                                  | 4        | 1.76%   |
| Samsung M267x 287x Series                                             | 4        | 1.76%   |
| HP LaserJet 1018                                                      | 4        | 1.76%   |
| HP ENVY 4520 series                                                   | 4        | 1.76%   |
| Canon PIXMA MG3600 Series                                             | 4        | 1.76%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 3        | 1.32%   |
| Samsung M2070 Series                                                  | 3        | 1.32%   |
| Samsung Composite Device                                              | 3        | 1.32%   |
| HP LaserJet Professional P 1102w                                      | 3        | 1.32%   |
| HP LaserJet P1102                                                     | 3        | 1.32%   |
| HP LaserJet P1005                                                     | 3        | 1.32%   |
| HP ENVY 5000 series                                                   | 3        | 1.32%   |
| HP Deskjet F4500 series                                               | 3        | 1.32%   |
| HP Deskjet 3050A                                                      | 3        | 1.32%   |
| Brother MFC-L2700DW                                                   | 3        | 1.32%   |
| Brother DCP-1610W                                                     | 3        | 1.32%   |
| Seiko Epson ET-2820 Series                                            | 2        | 0.88%   |
| Samsung ML-1660 Series                                                | 2        | 0.88%   |
| Samsung ML-1640 Series Laser Printer                                  | 2        | 0.88%   |
| Prolific PL2305 Parallel Port                                         | 2        | 0.88%   |
| Oki Data USB Device                                                   | 2        | 0.88%   |
| Lexmark International InkJet Color Printer                            | 2        | 0.88%   |
| HP OfficeJet 5200 series                                              | 2        | 0.88%   |
| HP Officejet 4630 series                                              | 2        | 0.88%   |
| HP Officejet 4500 G510n-z                                             | 2        | 0.88%   |
| HP Officejet 2620 series                                              | 2        | 0.88%   |
| HP LaserJet Pro M12a                                                  | 2        | 0.88%   |
| HP LaserJet 1200                                                      | 2        | 0.88%   |
| HP DeskJet F4200 series                                               | 2        | 0.88%   |
| HP Deskjet 3520 series                                                | 2        | 0.88%   |
| HP DeskJet 2130 series                                                | 2        | 0.88%   |
| Canon PIXMA MX920 Series                                              | 2        | 0.88%   |
| Canon PIXMA MG2500 Series                                             | 2        | 0.88%   |
| Canon LiDE 300                                                        | 2        | 0.88%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 36       | 55.38%  |
| Seiko Epson        | 16       | 24.62%  |
| Hewlett-Packard    | 7        | 10.77%  |
| Mustek Systems     | 4        | 6.15%   |
| Ultima Electronics | 1        | 1.54%   |
| Plustek            | 1        | 1.54%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 110                                                               | 7        | 10.77%  |
| Canon CanoScan LiDE 210                                                               | 6        | 9.23%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 4        | 6.15%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 3        | 4.62%   |
| Canon CanoScan LiDE 60                                                                | 3        | 4.62%   |
| Canon CanoScan LiDE 120                                                               | 3        | 4.62%   |
| Canon CanoScan LiDE 100                                                               | 3        | 4.62%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 2        | 3.08%   |
| Seiko Epson GT-7700U [Perfection 1240U]                                               | 2        | 3.08%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 2        | 3.08%   |
| HP Scanjet 200                                                                        | 2        | 3.08%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 2        | 3.08%   |
| Canon CanoScan LiDE 220                                                               | 2        | 3.08%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1        | 1.54%   |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                                           | 1        | 1.54%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 1        | 1.54%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 1        | 1.54%   |
| Seiko Epson GT-F700 [Perfection V350]                                                 | 1        | 1.54%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1        | 1.54%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 1        | 1.54%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 1        | 1.54%   |
| Seiko Epson GT-7600UF [Perfection 1200U/1200U Photo]                                  | 1        | 1.54%   |
| Seiko Epson GT-6600U [Perfection 610]                                                 | 1        | 1.54%   |
| Plustek 600DPI USB Scanner                                                            | 1        | 1.54%   |
| Mustek Systems SNAPSCAN e22                                                           | 1        | 1.54%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO                                            | 1        | 1.54%   |
| HP ScanJet 3800c                                                                      | 1        | 1.54%   |
| HP ScanJet 3400cse                                                                    | 1        | 1.54%   |
| HP ScanJet 2400c                                                                      | 1        | 1.54%   |
| HP PSC 1200                                                                           | 1        | 1.54%   |
| HP HP4470C                                                                            | 1        | 1.54%   |
| Canon CanoScan LiDE 90                                                                | 1        | 1.54%   |
| Canon CanoScan LiDE 700F                                                              | 1        | 1.54%   |
| Canon CanoScan LiDE 600F                                                              | 1        | 1.54%   |
| Canon CanoScan LIDE 25                                                                | 1        | 1.54%   |
| Canon CanoScan 4200F                                                                  | 1        | 1.54%   |
| Canon CanoScan 3000/3000F/3000ex                                                      | 1        | 1.54%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 186      | 33.39%  |
| Microdia                      | 66       | 11.85%  |
| Microsoft                     | 59       | 10.59%  |
| Sunplus Innovation Technology | 26       | 4.67%   |
| ARC International             | 20       | 3.59%   |
| Trust                         | 16       | 2.87%   |
| Samsung Electronics           | 13       | 2.33%   |
| Chicony Electronics           | 13       | 2.33%   |
| Realtek Semiconductor         | 11       | 1.97%   |
| Generalplus Technology        | 11       | 1.97%   |
| KYE Systems (Mouse Systems)   | 10       | 1.8%    |
| Cubeternet                    | 9        | 1.62%   |
| Apple                         | 9        | 1.62%   |
| Z-Star Microelectronics       | 7        | 1.26%   |
| GEMBIRD                       | 7        | 1.26%   |
| webcamvendor                  | 6        | 1.08%   |
| WaveRider Communications      | 6        | 1.08%   |
| Huawei Technologies           | 6        | 1.08%   |
| Sunplus IT                    | 5        | 0.9%    |
| IMC Networks                  | 4        | 0.72%   |
| Aveo Technology               | 4        | 0.72%   |
| SunplusIT                     | 3        | 0.54%   |
| Sonix Technology              | 3        | 0.54%   |
| Silicon Motion                | 3        | 0.54%   |
| MacroSilicon                  | 3        | 0.54%   |
| Jieli Technology              | 3        | 0.54%   |
| Hewlett-Packard               | 3        | 0.54%   |
| Genesys Logic                 | 3        | 0.54%   |
| Creative Technology           | 3        | 0.54%   |
| Arkmicro Technologies         | 3        | 0.54%   |
| Xiongmai                      | 2        | 0.36%   |
| Unknown                       | 2        | 0.36%   |
| Novatel Wireless              | 2        | 0.36%   |
| LG Electronics                | 2        | 0.36%   |
| Hopewin Electronic Material   | 2        | 0.36%   |
| Alcorlink                     | 2        | 0.36%   |
| TerraTec Electronic           | 1        | 0.18%   |
| Syntek                        | 1        | 0.18%   |
| Suyin                         | 1        | 0.18%   |
| Sunplus Technology            | 1        | 0.18%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Logitech Webcam C270                       | 51       | 9.12%   |
| Microsoft LifeCam HD-3000                  | 27       | 4.83%   |
| Logitech Webcam C170                       | 24       | 4.29%   |
| Logitech HD Pro Webcam C920                | 24       | 4.29%   |
| ARC International Camera                   | 20       | 3.58%   |
| Microdia Webcam Vitade AF                  | 17       | 3.04%   |
| Samsung Galaxy series, misc. (MTP mode)    | 13       | 2.33%   |
| Microdia Camera                            | 13       | 2.33%   |
| Logitech Webcam C310                       | 13       | 2.33%   |
| Microdia USB 2.0 Camera                    | 10       | 1.79%   |
| Microdia Sonix USB 2.0 Camera              | 10       | 1.79%   |
| Sunplus Aukey-PC-LM1E Camera               | 9        | 1.61%   |
| Logitech HD Webcam C525                    | 8        | 1.43%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR         | 8        | 1.43%   |
| Logitech QuickCam Pro 9000                 | 7        | 1.25%   |
| webcamvendor webcamproduct                 | 6        | 1.07%   |
| WaveRider USB Live camera                  | 6        | 1.07%   |
| Microsoft LifeCam VX-2000                  | 6        | 1.07%   |
| Microdia Integrated Camera                 | 6        | 1.07%   |
| Logitech HD Webcam C910                    | 6        | 1.07%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera | 6        | 1.07%   |
| Huawei HiCamera                            | 6        | 1.07%   |
| Generalplus CAMERA - UVC                   | 6        | 1.07%   |
| Trust WB-6250X Webcam                      | 5        | 0.89%   |
| Sunplus IT AUKEY PC-LM1 USB Camera         | 5        | 0.89%   |
| Sunplus Integrated_Webcam_HD               | 5        | 0.89%   |
| Microsoft LifeCam VX-5000                  | 5        | 0.89%   |
| Logitech C922 Pro Stream Webcam            | 5        | 0.89%   |
| GEMBIRD USB2.0 PC CAMERA                   | 5        | 0.89%   |
| Trust Webcam                               | 4        | 0.72%   |
| Trust 17676 Webcam                         | 4        | 0.72%   |
| Sunplus HD 720P webcam                     | 4        | 0.72%   |
| Microsoft LifeCam VX-800                   | 4        | 0.72%   |
| Microsoft LifeCam HD-5000                  | 4        | 0.72%   |
| Microsoft LifeCam Cinema                   | 4        | 0.72%   |
| Logitech Webcam C200                       | 4        | 0.72%   |
| Logitech StreamCam                         | 4        | 0.72%   |
| Logitech QuickCam E 3500                   | 4        | 0.72%   |
| Realtek USB Camera                         | 3        | 0.54%   |
| Microsoft LifeCam VX-700                   | 3        | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| Dell      | 1        | 50%     |
| AuthenTec | 1        | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Dell MS819 Wired Mouse With Fingerprint Reader | 1        | 50%     |
| AuthenTec Fingerprint Sensor                   | 1        | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Advanced Card Systems     | 18       | 36%     |
| BIT4ID                    | 8        | 16%     |
| Realtek Semiconductor     | 5        | 10%     |
| SCM Microsystems          | 4        | 8%      |
| Gemalto (was Gemplus)     | 4        | 8%      |
| Clay Logic                | 3        | 6%      |
| Alcor Micro               | 3        | 6%      |
| OmniKey                   | 2        | 4%      |
| Reiner SCT Kartensysteme  | 1        | 2%      |
| Microchip Technology      | 1        | 2%      |
| Fujitsu Siemens Computers | 1        | 2%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Advanced Card Systems ACR38 SmartCard Reader                               | 14       | 27.45%  |
| BIT4ID miniLector EVO                                                      | 7        | 13.73%  |
| Realtek Semiconductor Smart Card Reader Interface                          | 5        | 9.8%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 4        | 7.84%   |
| Advanced Card Systems ACR122U                                              | 4        | 7.84%   |
| Clay Logic Nitrokey Pro                                                    | 3        | 5.88%   |
| Alcor Micro Watchdata W 1981                                               | 2        | 3.92%   |
| SCM Microsystems uTrust 3700 F CL Reader                                   | 1        | 1.96%   |
| SCM Microsystems SCR35xx Smart Card Reader                                 | 1        | 1.96%   |
| SCM Microsystems SCR335 SmartCard Reader                                   | 1        | 1.96%   |
| SCM Microsystems Identiv SmartOS Reader                                    | 1        | 1.96%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 1.96%   |
| OmniKey CardMan 3021 / 3121                                                | 1        | 1.96%   |
| OmniKey 3x21 Smart Card Reader                                             | 1        | 1.96%   |
| Microchip Technology SMSC USX101x Reader                                   | 1        | 1.96%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                              | 1        | 1.96%   |
| BIT4ID miniLector AIR NFC v3                                               | 1        | 1.96%   |
| Alcor Micro AU9540 Smartcard Reader                                        | 1        | 1.96%   |
| Advanced Card Systems ACR1281 1S Dual Reader                               | 1        | 1.96%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 2407     | 85.05%  |
| 1     | 371      | 13.11%  |
| 2     | 40       | 1.41%   |
| 3     | 7        | 0.25%   |
| 5     | 3        | 0.11%   |
| 4     | 2        | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 150      | 32.12%  |
| Net/wireless             | 122      | 26.12%  |
| Communication controller | 45       | 9.64%   |
| Chipcard                 | 33       | 7.07%   |
| Unassigned class         | 27       | 5.78%   |
| Sound                    | 15       | 3.21%   |
| Camera                   | 12       | 2.57%   |
| Multimedia controller    | 11       | 2.36%   |
| Card reader              | 10       | 2.14%   |
| Storage/raid             | 7        | 1.5%    |
| Modem                    | 6        | 1.28%   |
| Network                  | 5        | 1.07%   |
| Net/ethernet             | 5        | 1.07%   |
| Firewire controller      | 5        | 1.07%   |
| Bluetooth                | 4        | 0.86%   |
| Dvb card                 | 3        | 0.64%   |
| Video                    | 2        | 0.43%   |
| Tv card                  | 2        | 0.43%   |
| Storage/ide              | 2        | 0.43%   |
| Fingerprint reader       | 1        | 0.21%   |


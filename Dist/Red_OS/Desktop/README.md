Red OS - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Red OS.

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

Total: 529

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | B150M-C                     | [c37140281a](https://linux-hardware.org/?probe=c37140281a) | Dec 30, 2025 |
| Gigabyte      | H110M-S2H-CF                | [56fb39017b](https://linux-hardware.org/?probe=56fb39017b) | Dec 29, 2025 |
| MSI           | MAG B660M BAZOOKA DDR4      | [893fe08a71](https://linux-hardware.org/?probe=893fe08a71) | Nov 28, 2025 |
| MTR           | HN-469579.025 V1.0          | [c20b1f9918](https://linux-hardware.org/?probe=c20b1f9918) | Nov 26, 2025 |
| Gigabyte      | H410M H V2                  | [7bf0d747c3](https://linux-hardware.org/?probe=7bf0d747c3) | Nov 25, 2025 |
| Unknown       | Unknown                     | [864d58b3ee](https://linux-hardware.org/?probe=864d58b3ee) | Nov 24, 2025 |
| ASUSTek       | PRIME H370M-PLUS            | [0bca14114b](https://linux-hardware.org/?probe=0bca14114b) | Nov 18, 2025 |
| DIO           | I610M4C Ver:                | [d574bef7e6](https://linux-hardware.org/?probe=d574bef7e6) | Nov 17, 2025 |
| Gigabyte      | H410M S2H V2                | [ce64fa159b](https://linux-hardware.org/?probe=ce64fa159b) | Nov 12, 2025 |
| MSI           | A520M-A PRO                 | [2264628cc1](https://linux-hardware.org/?probe=2264628cc1) | Nov 07, 2025 |
| ICL           | H410SB                      | [f56fd2d182](https://linux-hardware.org/?probe=f56fd2d182) | Oct 30, 2025 |
| HomeNET       | B660I-D Chipset             | [017c148d72](https://linux-hardware.org/?probe=017c148d72) | Oct 28, 2025 |
| Gigabyte      | H410M H V2                  | [4078a09585](https://linux-hardware.org/?probe=4078a09585) | Oct 21, 2025 |
| HP            | 86E9 A                      | [be341f0c37](https://linux-hardware.org/?probe=be341f0c37) | Oct 17, 2025 |
| MSI           | H81M-P33                    | [131fb86792](https://linux-hardware.org/?probe=131fb86792) | Oct 16, 2025 |
| Gigabyte      | H410M H V3                  | [f37bb7d0ed](https://linux-hardware.org/?probe=f37bb7d0ed) | Oct 16, 2025 |
| Gigabyte      | B450M H                     | [7ec39ced72](https://linux-hardware.org/?probe=7ec39ced72) | Sep 30, 2025 |
| Intel         | HM65 Ver:5.4                | [d9e6b0d7ee](https://linux-hardware.org/?probe=d9e6b0d7ee) | Sep 24, 2025 |
| MSI           | Z77A-G45 Thunderbolt        | [28c6c6c453](https://linux-hardware.org/?probe=28c6c6c453) | Sep 18, 2025 |
| MTR           | HN-X730 V1.0                | [63e6468416](https://linux-hardware.org/?probe=63e6468416) | Sep 16, 2025 |
| Graviton      | DMB-H510-MCA01              | [929f4f29c9](https://linux-hardware.org/?probe=929f4f29c9) | Sep 15, 2025 |
| Intel         | DH61BF AAG81311-101         | [ca0411f0a9](https://linux-hardware.org/?probe=ca0411f0a9) | Sep 12, 2025 |
| Intel         | DH61BF AAG81311-101         | [2e2afd1d90](https://linux-hardware.org/?probe=2e2afd1d90) | Sep 12, 2025 |
| INTECH PRO    | H6104D4G V2.0               | [cc7600dd9c](https://linux-hardware.org/?probe=cc7600dd9c) | Sep 11, 2025 |
| AZW           | GK mini                     | [01f739f5dc](https://linux-hardware.org/?probe=01f739f5dc) | Sep 04, 2025 |
| Graviton      | DMB-A620-MCA01              | [80dc13b375](https://linux-hardware.org/?probe=80dc13b375) | Sep 02, 2025 |
| Graviton      | DMB-A620-MCA01              | [64ac1947fc](https://linux-hardware.org/?probe=64ac1947fc) | Sep 02, 2025 |
| Graviton      | DMB-H610-MCA01              | [5f42ea1439](https://linux-hardware.org/?probe=5f42ea1439) | Sep 02, 2025 |
| AZW           | MINI S                      | [ee448ad0fb](https://linux-hardware.org/?probe=ee448ad0fb) | Aug 28, 2025 |
| ASUSTek       | B75M-A                      | [f316f01599](https://linux-hardware.org/?probe=f316f01599) | Aug 25, 2025 |
| MSI           | Z77A-G45 Thunderbolt        | [ed55333293](https://linux-hardware.org/?probe=ed55333293) | Aug 21, 2025 |
| Aquarius      | AQB560M                     | [da256febc7](https://linux-hardware.org/?probe=da256febc7) | Aug 14, 2025 |
| ASUSTek       | H110M-A D3                  | [54a4120a63](https://linux-hardware.org/?probe=54a4120a63) | Aug 13, 2025 |
| MSI           | PRO H510M-B ll              | [54c67a1f03](https://linux-hardware.org/?probe=54c67a1f03) | Aug 07, 2025 |
| Gigabyte      | B550M DS3H                  | [0019415ecf](https://linux-hardware.org/?probe=0019415ecf) | Aug 07, 2025 |
| MSI           | G41M-P28                    | [43214a8103](https://linux-hardware.org/?probe=43214a8103) | Aug 07, 2025 |
| MSI           | PRO B650-S WIFI             | [8d8aa4cf7b](https://linux-hardware.org/?probe=8d8aa4cf7b) | Aug 06, 2025 |
| ASUSTek       | PRIME Z890-P WIFI           | [08c81e10fe](https://linux-hardware.org/?probe=08c81e10fe) | Jul 31, 2025 |
| ASUSTek       | P8B75-M LX PLUS             | [6822a51741](https://linux-hardware.org/?probe=6822a51741) | Jul 31, 2025 |
| HP            | 2B5E                        | [09af2456e8](https://linux-hardware.org/?probe=09af2456e8) | Jul 29, 2025 |
| Gigabyte      | B760M DS3H DDR4             | [49f61f5d5b](https://linux-hardware.org/?probe=49f61f5d5b) | Jul 21, 2025 |
| Intel         | B75 V1.6B                   | [d33e360896](https://linux-hardware.org/?probe=d33e360896) | Jul 07, 2025 |
| Gigabyte      | B75M-D3V                    | [579acf5833](https://linux-hardware.org/?probe=579acf5833) | Jul 04, 2025 |
| Intel         | B75 V1.6B                   | [aa3e9afee7](https://linux-hardware.org/?probe=aa3e9afee7) | Jun 30, 2025 |
| ASUSTek       | PRIME Z890-P WIFI           | [484a864d5a](https://linux-hardware.org/?probe=484a864d5a) | Jun 29, 2025 |
| ASUSTek       | PRIME H510M-K               | [2fdedd70b1](https://linux-hardware.org/?probe=2fdedd70b1) | Jun 26, 2025 |
| ASUSTek       | PRIME H770-PLUS D4          | [b8837c1cff](https://linux-hardware.org/?probe=b8837c1cff) | Jun 26, 2025 |
| Lenovo        | BRASWELL SDK0J40706 WIN ... | [4b3035c591](https://linux-hardware.org/?probe=4b3035c591) | Jun 18, 2025 |
| Gigabyte      | B365M DS3H                  | [82cabf8850](https://linux-hardware.org/?probe=82cabf8850) | Jun 17, 2025 |
| Gigabyte      | B365M D3H-RD-CF             | [b74c48e0b5](https://linux-hardware.org/?probe=b74c48e0b5) | Jun 17, 2025 |
| Gigabyte      | P55A-UD3                    | [bb2f808156](https://linux-hardware.org/?probe=bb2f808156) | Jun 17, 2025 |
| Intel         | DH61CR AAG14064-203         | [6122aad4c5](https://linux-hardware.org/?probe=6122aad4c5) | Jun 06, 2025 |
| Gigabyte      | B365M DS3H                  | [c09dd86b3c](https://linux-hardware.org/?probe=c09dd86b3c) | Jun 02, 2025 |
| ASUSTek       | P5KC                        | [e19ec310ce](https://linux-hardware.org/?probe=e19ec310ce) | May 30, 2025 |
| Intel         | DH61BF AAG81311-101         | [05106390af](https://linux-hardware.org/?probe=05106390af) | May 29, 2025 |
| Gigabyte      | B760M DS3H DDR4             | [174fa9a723](https://linux-hardware.org/?probe=174fa9a723) | May 29, 2025 |
| Gigabyte      | B450 AORUS ELITE V2         | [05b3b44652](https://linux-hardware.org/?probe=05b3b44652) | May 29, 2025 |
| MSI           | MEG X570 UNIFY              | [0d90dee018](https://linux-hardware.org/?probe=0d90dee018) | May 29, 2025 |
| Gigabyte      | H610M S2H V2 DDR4           | [798240aced](https://linux-hardware.org/?probe=798240aced) | May 29, 2025 |
| ASUSTek       | PRIME H610M-R D4            | [380d9fb585](https://linux-hardware.org/?probe=380d9fb585) | May 29, 2025 |
| Aquarius      | AQB560M                     | [2eb1be89d1](https://linux-hardware.org/?probe=2eb1be89d1) | May 20, 2025 |
| Unknown       | Unknown                     | [9e0e1d60fa](https://linux-hardware.org/?probe=9e0e1d60fa) | May 14, 2025 |
| Gigabyte      | H310M S2H x.x               | [f5dd08f865](https://linux-hardware.org/?probe=f5dd08f865) | May 05, 2025 |
| MSI           | G31M3-F V2                  | [0682a12e4c](https://linux-hardware.org/?probe=0682a12e4c) | May 05, 2025 |
| Pegatron      | E60                         | [3905de17f0](https://linux-hardware.org/?probe=3905de17f0) | May 02, 2025 |
| HP            | 0AECh D                     | [f4502445d6](https://linux-hardware.org/?probe=f4502445d6) | May 01, 2025 |
| ASUSTek       | P5GC-VM                     | [a9b4d64ad0](https://linux-hardware.org/?probe=a9b4d64ad0) | Apr 25, 2025 |
| ASUSTek       | P5GC-VM                     | [ed742e683d](https://linux-hardware.org/?probe=ed742e683d) | Apr 25, 2025 |
| ASUSTek       | P5GC-VM                     | [08e85e1b3a](https://linux-hardware.org/?probe=08e85e1b3a) | Apr 25, 2025 |
| ASUSTek       | P5GC-VM                     | [b00d718d98](https://linux-hardware.org/?probe=b00d718d98) | Apr 25, 2025 |
| ASUSTek       | P5GC-VM                     | [b63d2b0d8c](https://linux-hardware.org/?probe=b63d2b0d8c) | Apr 25, 2025 |
| ASUSTek       | P5GC-VM                     | [8c8a96b69e](https://linux-hardware.org/?probe=8c8a96b69e) | Apr 25, 2025 |
| ASUSTek       | P5GC-VM                     | [6d24b61234](https://linux-hardware.org/?probe=6d24b61234) | Apr 25, 2025 |
| ASUSTek       | P8H77-V                     | [62bf1d31f9](https://linux-hardware.org/?probe=62bf1d31f9) | Apr 22, 2025 |
| ASUSTek       | Pro H610T D4                | [6f7d2f61b1](https://linux-hardware.org/?probe=6f7d2f61b1) | Apr 22, 2025 |
| HP            | 0AECh D                     | [4ad90b3488](https://linux-hardware.org/?probe=4ad90b3488) | Apr 21, 2025 |
| ASUSTek       | P5GC-VM                     | [170d92633a](https://linux-hardware.org/?probe=170d92633a) | Apr 21, 2025 |
| ASUSTek       | P5GC-VM                     | [80f52cea9a](https://linux-hardware.org/?probe=80f52cea9a) | Apr 21, 2025 |
| HP            | 0AECh D                     | [95ee884da6](https://linux-hardware.org/?probe=95ee884da6) | Apr 21, 2025 |
| MSI           | H510M PRO-E                 | [aeab3d15df](https://linux-hardware.org/?probe=aeab3d15df) | Apr 18, 2025 |
| HP            | 0AECh D                     | [b5e71ee7d8](https://linux-hardware.org/?probe=b5e71ee7d8) | Apr 17, 2025 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [7decd8127c](https://linux-hardware.org/?probe=7decd8127c) | Apr 16, 2025 |
| ICL           | H410SB                      | [6c91babe95](https://linux-hardware.org/?probe=6c91babe95) | Apr 15, 2025 |
| ASUSTek       | PRIME A620M-K               | [768b8c3537](https://linux-hardware.org/?probe=768b8c3537) | Mar 31, 2025 |
| ASUSTek       | P5G41TD-M PRO               | [f83d64645b](https://linux-hardware.org/?probe=f83d64645b) | Mar 27, 2025 |
| Unknown       | SKYBAY                      | [7071732f58](https://linux-hardware.org/?probe=7071732f58) | Mar 27, 2025 |
| ASUSTek       | P8H61                       | [5ac8ad5b49](https://linux-hardware.org/?probe=5ac8ad5b49) | Mar 26, 2025 |
| ASUSTek       | PRIME H510T2/CSM            | [301260ed92](https://linux-hardware.org/?probe=301260ed92) | Mar 24, 2025 |
| Gigabyte      | B85M-D2V                    | [f1b9111335](https://linux-hardware.org/?probe=f1b9111335) | Mar 20, 2025 |
| MSI           | MAG B660M BAZOOKA DDR4      | [f009256f20](https://linux-hardware.org/?probe=f009256f20) | Mar 20, 2025 |
| ASUSTek       | X99-DELUXE                  | [d46b2e294f](https://linux-hardware.org/?probe=d46b2e294f) | Mar 18, 2025 |
| ASUSTek       | PRIME H610M-R D4            | [768bcd38af](https://linux-hardware.org/?probe=768bcd38af) | Mar 18, 2025 |
| ASUSTek       | PRIME H610M-R D4            | [da5a3958c5](https://linux-hardware.org/?probe=da5a3958c5) | Mar 17, 2025 |
| ASRock        | H61M-GS                     | [207c6df6e8](https://linux-hardware.org/?probe=207c6df6e8) | Mar 14, 2025 |
| Lenovo        | 36C8 SDK0J40679 WIN 3273... | [98fb0ef530](https://linux-hardware.org/?probe=98fb0ef530) | Mar 13, 2025 |
| ASRock        | H310CM-HDV                  | [563b637206](https://linux-hardware.org/?probe=563b637206) | Mar 13, 2025 |
| ASUSTek       | PRIME B360-PLUS             | [193de808c1](https://linux-hardware.org/?probe=193de808c1) | Mar 12, 2025 |
| ASUSTek       | PRIME B360-PLUS             | [ad8430b630](https://linux-hardware.org/?probe=ad8430b630) | Mar 11, 2025 |
| Unknown       | B760RU001                   | [f5d8231c0d](https://linux-hardware.org/?probe=f5d8231c0d) | Mar 11, 2025 |
| LIFE TECH     | Intel H510U PRO Ver:TYT-... | [f05669d3b5](https://linux-hardware.org/?probe=f05669d3b5) | Mar 10, 2025 |
| ASUSTek       | P8H61                       | [ce67070905](https://linux-hardware.org/?probe=ce67070905) | Mar 08, 2025 |
| Gigabyte      | AB350M-DS3H V2-CF           | [294b5368ec](https://linux-hardware.org/?probe=294b5368ec) | Mar 04, 2025 |
| INFERIT       | INFPC                       | [ce4c46cb8d](https://linux-hardware.org/?probe=ce4c46cb8d) | Feb 27, 2025 |
| ASUSTek       | PRIME H510M-R               | [340fdc0f60](https://linux-hardware.org/?probe=340fdc0f60) | Feb 26, 2025 |
| MSI           | G41M-P33 Combo              | [20f742cd29](https://linux-hardware.org/?probe=20f742cd29) | Feb 24, 2025 |
| ASUSTek       | H61M-K                      | [9d50c8a7e2](https://linux-hardware.org/?probe=9d50c8a7e2) | Feb 24, 2025 |
| ASUSTek       | P5GC-MX/1333                | [5e3d95759a](https://linux-hardware.org/?probe=5e3d95759a) | Feb 24, 2025 |
| ASUSTek       | H61M-K                      | [54ff3390d2](https://linux-hardware.org/?probe=54ff3390d2) | Feb 24, 2025 |
| ASUSTek       | P5GC-MX/1333                | [0ec7aef2c7](https://linux-hardware.org/?probe=0ec7aef2c7) | Feb 24, 2025 |
| ASRock        | H61M-DGS                    | [5ac582c568](https://linux-hardware.org/?probe=5ac582c568) | Feb 24, 2025 |
| ASRock        | A75M-HVS                    | [871e1d6506](https://linux-hardware.org/?probe=871e1d6506) | Feb 24, 2025 |
| ASRock        | G41M-VS3                    | [fe7ba9a100](https://linux-hardware.org/?probe=fe7ba9a100) | Feb 24, 2025 |
| ASUSTek       | H61M-K                      | [63c76f4af3](https://linux-hardware.org/?probe=63c76f4af3) | Feb 24, 2025 |
| ASUSTek       | H61M-K                      | [f8e505c602](https://linux-hardware.org/?probe=f8e505c602) | Feb 24, 2025 |
| Gigabyte      | H61M-S2PV                   | [eb5a5beb3f](https://linux-hardware.org/?probe=eb5a5beb3f) | Feb 24, 2025 |
| Intel         | DH61CR AAG14064-203         | [ad4bf81f52](https://linux-hardware.org/?probe=ad4bf81f52) | Feb 24, 2025 |
| MSI           | H61I-E35                    | [437614c6ae](https://linux-hardware.org/?probe=437614c6ae) | Feb 20, 2025 |
| MSI           | H61I-E35                    | [e93b5cc21b](https://linux-hardware.org/?probe=e93b5cc21b) | Feb 20, 2025 |
| MSI           | H61I-E35                    | [f4b0faf686](https://linux-hardware.org/?probe=f4b0faf686) | Feb 17, 2025 |
| ASUSTek       | H81M-K                      | [e0cfb07ee5](https://linux-hardware.org/?probe=e0cfb07ee5) | Feb 17, 2025 |
| ASUSTek       | H81M2                       | [363b301a46](https://linux-hardware.org/?probe=363b301a46) | Feb 13, 2025 |
| ASUSTek       | B75M-PLUS                   | [1e78f897f5](https://linux-hardware.org/?probe=1e78f897f5) | Feb 04, 2025 |
| DEPO Compu... | DPH410S                     | [8bdb2f820e](https://linux-hardware.org/?probe=8bdb2f820e) | Feb 03, 2025 |
| DEPO Compu... | DPH410S                     | [67e933b407](https://linux-hardware.org/?probe=67e933b407) | Jan 31, 2025 |
| Lenovo        | 1052 NOK                    | [0d678a0987](https://linux-hardware.org/?probe=0d678a0987) | Jan 27, 2025 |
| Gigabyte      | B365M DS3H                  | [7ee602da75](https://linux-hardware.org/?probe=7ee602da75) | Jan 27, 2025 |
| Graviton      | DMB-Q670-TMI01              | [f20205b981](https://linux-hardware.org/?probe=f20205b981) | Jan 23, 2025 |
| Aquarius      | AQB760MIs1                  | [49af56f2a0](https://linux-hardware.org/?probe=49af56f2a0) | Jan 22, 2025 |
| Aquarius      | AQB760MIs1                  | [706605aec8](https://linux-hardware.org/?probe=706605aec8) | Jan 22, 2025 |
| ASUSTek       | P5G41T-M LX2/GB             | [a70c1e9b8d](https://linux-hardware.org/?probe=a70c1e9b8d) | Jan 21, 2025 |
| ASUSTek       | H81M2                       | [f6ecfb6bec](https://linux-hardware.org/?probe=f6ecfb6bec) | Jan 21, 2025 |
| ASUSTek       | H81M2                       | [446fb0fc3b](https://linux-hardware.org/?probe=446fb0fc3b) | Jan 21, 2025 |
| Gigabyte      | Z77X-UD5H                   | [cab3f4e86d](https://linux-hardware.org/?probe=cab3f4e86d) | Jan 17, 2025 |
| ASUSTek       | PRIME H610T2-CSM D4         | [143e6c1fdd](https://linux-hardware.org/?probe=143e6c1fdd) | Jan 17, 2025 |
| Gigabyte      | AB350M-DS3H V2-CF           | [ddd3981011](https://linux-hardware.org/?probe=ddd3981011) | Jan 17, 2025 |
| Unknown       | Unknown                     | [45f50f357c](https://linux-hardware.org/?probe=45f50f357c) | Jan 16, 2025 |
| Gigabyte      | AB350M-DS3H V2-CF           | [4f315f84a0](https://linux-hardware.org/?probe=4f315f84a0) | Jan 16, 2025 |
| HP            | 8626                        | [5a47ed16e3](https://linux-hardware.org/?probe=5a47ed16e3) | Jan 15, 2025 |
| Gigabyte      | B560 HD3                    | [7555560a0a](https://linux-hardware.org/?probe=7555560a0a) | Jan 15, 2025 |
| HP            | 8626                        | [2927d9db71](https://linux-hardware.org/?probe=2927d9db71) | Jan 14, 2025 |
| Dell          | 0WMJ54 A01                  | [59a5688b5d](https://linux-hardware.org/?probe=59a5688b5d) | Jan 14, 2025 |
| HP            | 2179                        | [c614e03a53](https://linux-hardware.org/?probe=c614e03a53) | Jan 13, 2025 |
| MSI           | PRO H510M-B                 | [71e95bf28d](https://linux-hardware.org/?probe=71e95bf28d) | Jan 13, 2025 |
| MSI           | PRO H510M-B                 | [399b2f672f](https://linux-hardware.org/?probe=399b2f672f) | Jan 13, 2025 |
| MSI           | PRO H510M-B                 | [5e38bac77f](https://linux-hardware.org/?probe=5e38bac77f) | Jan 13, 2025 |
| ECS           | 671T-M                      | [4979f70139](https://linux-hardware.org/?probe=4979f70139) | Jan 09, 2025 |
| Graviton      | DMB-Q670-TMI01              | [c609b9c45c](https://linux-hardware.org/?probe=c609b9c45c) | Dec 26, 2024 |
| Graviton      | DMB-Q670-TMI01              | [425c41687c](https://linux-hardware.org/?probe=425c41687c) | Dec 26, 2024 |
| Gigabyte      | H110M-S2H-CF                | [89c03187e1](https://linux-hardware.org/?probe=89c03187e1) | Dec 19, 2024 |
| Gigabyte      | A620M H                     | [bef78fc714](https://linux-hardware.org/?probe=bef78fc714) | Dec 19, 2024 |
| Gigabyte      | A620M H                     | [a48a1efcc8](https://linux-hardware.org/?probe=a48a1efcc8) | Dec 18, 2024 |
| Intel         | DH61BF AAG81311-101         | [4d21569356](https://linux-hardware.org/?probe=4d21569356) | Dec 18, 2024 |
| Gigabyte      | H510M H                     | [a49d561fb0](https://linux-hardware.org/?probe=a49d561fb0) | Dec 15, 2024 |
| BESHTAU       | Q670D5RU002 V1.0            | [59e2adb673](https://linux-hardware.org/?probe=59e2adb673) | Dec 13, 2024 |
| Gigabyte      | A520M S2H                   | [5fc4416068](https://linux-hardware.org/?probe=5fc4416068) | Dec 13, 2024 |
| Intel         | DH61CR AAG14064-203         | [2acdad4c78](https://linux-hardware.org/?probe=2acdad4c78) | Dec 12, 2024 |
| DEPO Compu... | DPH410S                     | [a986fc28d0](https://linux-hardware.org/?probe=a986fc28d0) | Dec 11, 2024 |
| ASUSTek       | PRIME B360M-C               | [5110e95caf](https://linux-hardware.org/?probe=5110e95caf) | Dec 10, 2024 |
| ASUSTek       | PRIME B360M-C               | [b08f5fe789](https://linux-hardware.org/?probe=b08f5fe789) | Dec 10, 2024 |
| Intel         | DH61CR AAG14064-203         | [c4751390a8](https://linux-hardware.org/?probe=c4751390a8) | Dec 09, 2024 |
| ECS           | H81H3-M4                    | [bc47715809](https://linux-hardware.org/?probe=bc47715809) | Dec 06, 2024 |
| INFERIT       | IFMBH510MKPR G10a           | [48fdaa7cd0](https://linux-hardware.org/?probe=48fdaa7cd0) | Dec 04, 2024 |
| Kraftway      | KWH510                      | [1f385fb7ae](https://linux-hardware.org/?probe=1f385fb7ae) | Dec 04, 2024 |
| Gigabyte      | A520M S2H                   | [1f167af92b](https://linux-hardware.org/?probe=1f167af92b) | Nov 28, 2024 |
| Gigabyte      | A520M S2H                   | [08a50a8073](https://linux-hardware.org/?probe=08a50a8073) | Nov 28, 2024 |
| MSI           | B250M PRO-VDH               | [95c02414bb](https://linux-hardware.org/?probe=95c02414bb) | Nov 27, 2024 |
| Dell          | 0VNM11 A01                  | [40eccd6be6](https://linux-hardware.org/?probe=40eccd6be6) | Nov 26, 2024 |
| Supermicro    | X10DRiB                     | [b00821a487](https://linux-hardware.org/?probe=b00821a487) | Nov 25, 2024 |
| Gigabyte      | B365M DS3H                  | [8690967d76](https://linux-hardware.org/?probe=8690967d76) | Nov 13, 2024 |
| Gigabyte      | B365M D3H-CF                | [a5838abf59](https://linux-hardware.org/?probe=a5838abf59) | Nov 12, 2024 |
| BESHTAU       | H610RU001 V1.0              | [50a3234041](https://linux-hardware.org/?probe=50a3234041) | Nov 12, 2024 |
| ASUSTek       | P8H67-M PRO                 | [c694929d4d](https://linux-hardware.org/?probe=c694929d4d) | Nov 11, 2024 |
| ASUSTek       | H61M-K                      | [caea237027](https://linux-hardware.org/?probe=caea237027) | Nov 11, 2024 |
| ASUSTek       | B85M-G                      | [8057418501](https://linux-hardware.org/?probe=8057418501) | Nov 11, 2024 |
| Gigabyte      | H81M-S2VP                   | [30e754b191](https://linux-hardware.org/?probe=30e754b191) | Nov 11, 2024 |
| Gigabyte      | F2A55M-S1                   | [b1994169b0](https://linux-hardware.org/?probe=b1994169b0) | Nov 11, 2024 |
| Gigabyte      | H81M-S2VP                   | [0bd4b5605c](https://linux-hardware.org/?probe=0bd4b5605c) | Nov 11, 2024 |
| Gigabyte      | F2A55M-S1                   | [44d2040a89](https://linux-hardware.org/?probe=44d2040a89) | Nov 11, 2024 |
| MSI           | A520M-A PRO                 | [d5bdcf81dd](https://linux-hardware.org/?probe=d5bdcf81dd) | Nov 11, 2024 |
| ASRock        | H610M-HVS                   | [b304feae94](https://linux-hardware.org/?probe=b304feae94) | Nov 07, 2024 |
| Gigabyte      | H55M-UD2H                   | [961478c114](https://linux-hardware.org/?probe=961478c114) | Nov 07, 2024 |
| ASRock        | H310CM-DVS                  | [a1ad62188e](https://linux-hardware.org/?probe=a1ad62188e) | Nov 07, 2024 |
| MSI           | B360M PRO-VDH               | [7991e1acba](https://linux-hardware.org/?probe=7991e1acba) | Nov 02, 2024 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [e2785d8d28](https://linux-hardware.org/?probe=e2785d8d28) | Oct 21, 2024 |
| Aquarius      | AQH310CM                    | [cf03695b5e](https://linux-hardware.org/?probe=cf03695b5e) | Oct 18, 2024 |
| Gigabyte      | B75M-D3V                    | [3360dc0f64](https://linux-hardware.org/?probe=3360dc0f64) | Oct 08, 2024 |
| ASRock        | H310CM-HDV/M.2              | [797e92230b](https://linux-hardware.org/?probe=797e92230b) | Oct 04, 2024 |
| Dell          | 0KYWH7 A03                  | [c029d50cdd](https://linux-hardware.org/?probe=c029d50cdd) | Oct 02, 2024 |
| Dell          | 0V4W66 A00                  | [fbe88e537a](https://linux-hardware.org/?probe=fbe88e537a) | Sep 30, 2024 |
| Huanan        | X99-BD4 V1.34               | [9ff89a88f1](https://linux-hardware.org/?probe=9ff89a88f1) | Aug 25, 2024 |
| Acer          | Aspire XC-885 V:1.1         | [09f000529a](https://linux-hardware.org/?probe=09f000529a) | Aug 22, 2024 |
| MSI           | H310M PRO-VDH               | [1e0b767085](https://linux-hardware.org/?probe=1e0b767085) | Aug 22, 2024 |
| ICL           | H410SB                      | [05b3ed6993](https://linux-hardware.org/?probe=05b3ed6993) | Aug 16, 2024 |
| Huanan        | X99-BD4 V1.34               | [d62a8cb955](https://linux-hardware.org/?probe=d62a8cb955) | Aug 09, 2024 |
| Intel         | DH61BF AAG81311-101         | [b9ef99ffd8](https://linux-hardware.org/?probe=b9ef99ffd8) | Jul 29, 2024 |
| ASUSTek       | PRIME H510M-R               | [8bbda40ace](https://linux-hardware.org/?probe=8bbda40ace) | Jul 29, 2024 |
| Gigabyte      | B365M DS3H                  | [785322816c](https://linux-hardware.org/?probe=785322816c) | Jul 29, 2024 |
| Gigabyte      | B360HD3                     | [1cd46b9994](https://linux-hardware.org/?probe=1cd46b9994) | Jul 29, 2024 |
| Aquarius      | AQH410T                     | [f30b737c64](https://linux-hardware.org/?probe=f30b737c64) | Jul 25, 2024 |
| HP            | 8599                        | [5571e112b3](https://linux-hardware.org/?probe=5571e112b3) | Jul 23, 2024 |
| MSI           | B450M MORTAR MAX            | [2a0cbaac64](https://linux-hardware.org/?probe=2a0cbaac64) | Jul 20, 2024 |
| Foxconn       | M61PMV FAB                  | [4c63ed31bc](https://linux-hardware.org/?probe=4c63ed31bc) | Jul 14, 2024 |
| Foxconn       | M61PMV FAB                  | [8fba56f752](https://linux-hardware.org/?probe=8fba56f752) | Jul 12, 2024 |
| HP            | 3396                        | [c4cd06b045](https://linux-hardware.org/?probe=c4cd06b045) | Jul 08, 2024 |
| HP            | 18E6                        | [0201e189b7](https://linux-hardware.org/?probe=0201e189b7) | Jul 02, 2024 |
| Lenovo        | 3111 NOK                    | [8a4da42802](https://linux-hardware.org/?probe=8a4da42802) | Jul 02, 2024 |
| ASUSTek       | B85M-G                      | [9618ac190c](https://linux-hardware.org/?probe=9618ac190c) | Jun 28, 2024 |
| ASRock        | H610M-HVS                   | [44957c7ccb](https://linux-hardware.org/?probe=44957c7ccb) | Jun 26, 2024 |
| ASUSTek       | B150M-K                     | [fac6b0f586](https://linux-hardware.org/?probe=fac6b0f586) | Jun 19, 2024 |
| ASUSTek       | B150M-K                     | [326710cc69](https://linux-hardware.org/?probe=326710cc69) | Jun 19, 2024 |
| MSI           | H61M-P31                    | [d0742079a6](https://linux-hardware.org/?probe=d0742079a6) | May 31, 2024 |
| Intel         | DH61BF AAG81311-101         | [210077e8dc](https://linux-hardware.org/?probe=210077e8dc) | May 31, 2024 |
| Gigabyte      | GA-880GMA-UD2H              | [2cb7e34625](https://linux-hardware.org/?probe=2cb7e34625) | May 17, 2024 |
| MSI           | PRO H610M-E DDR4            | [a415f46a9e](https://linux-hardware.org/?probe=a415f46a9e) | May 07, 2024 |
| MSI           | PRO H610M-E DDR4            | [e4adc14010](https://linux-hardware.org/?probe=e4adc14010) | May 06, 2024 |
| ASRock        | H610M-HVS                   | [bb1b76d77f](https://linux-hardware.org/?probe=bb1b76d77f) | Apr 10, 2024 |
| ASUSTek       | H110-PLUS                   | [f9d667563c](https://linux-hardware.org/?probe=f9d667563c) | Apr 10, 2024 |
| Gigabyte      | B75M-D3V                    | [606efbdac3](https://linux-hardware.org/?probe=606efbdac3) | Apr 10, 2024 |
| Gigabyte      | B75M-D3V                    | [af364f4b61](https://linux-hardware.org/?probe=af364f4b61) | Apr 09, 2024 |
| Gigabyte      | B75M-D3V                    | [2c9d3860d1](https://linux-hardware.org/?probe=2c9d3860d1) | Apr 05, 2024 |
| ASRock        | H610M-HVS                   | [0fe84d2ae2](https://linux-hardware.org/?probe=0fe84d2ae2) | Apr 05, 2024 |
| Foxconn       | 2ABF                        | [1948e2f590](https://linux-hardware.org/?probe=1948e2f590) | Mar 28, 2024 |
| MSI           | MAG B760M MORTAR            | [a7d3ac796f](https://linux-hardware.org/?probe=a7d3ac796f) | Mar 24, 2024 |
| Gigabyte      | A520M K V2                  | [bb5ad21304](https://linux-hardware.org/?probe=bb5ad21304) | Mar 24, 2024 |
| Gigabyte      | H510M S2H V2                | [cbfecba3df](https://linux-hardware.org/?probe=cbfecba3df) | Mar 20, 2024 |
| Gigabyte      | H510M S2H V2                | [f9d491fb3a](https://linux-hardware.org/?probe=f9d491fb3a) | Mar 20, 2024 |
| ASUSTek       | PRIME H310M-R R2.0          | [6c0a847cf4](https://linux-hardware.org/?probe=6c0a847cf4) | Mar 20, 2024 |
| Gigabyte      | H310M H                     | [041eca17dc](https://linux-hardware.org/?probe=041eca17dc) | Mar 20, 2024 |
| ASUSTek       | P8H61-M LX3 R2.0            | [21877754a0](https://linux-hardware.org/?probe=21877754a0) | Mar 20, 2024 |
| HP            | 198E                        | [dfdd44b32d](https://linux-hardware.org/?probe=dfdd44b32d) | Mar 20, 2024 |
| ASUSTek       | PRIME B360-PLUS             | [286fb4ec0a](https://linux-hardware.org/?probe=286fb4ec0a) | Mar 20, 2024 |
| Unknown       | T360D11                     | [8dc0de16f8](https://linux-hardware.org/?probe=8dc0de16f8) | Mar 20, 2024 |
| HP            | 2B43                        | [365885e742](https://linux-hardware.org/?probe=365885e742) | Mar 20, 2024 |
| Acer          | Aspire XC-885 V:1.1         | [ec2b946862](https://linux-hardware.org/?probe=ec2b946862) | Mar 20, 2024 |
| Gigabyte      | B75M-D3V                    | [4a7f8b6b79](https://linux-hardware.org/?probe=4a7f8b6b79) | Mar 15, 2024 |
| ASRock        | H610M-HVS                   | [3189e4304b](https://linux-hardware.org/?probe=3189e4304b) | Mar 13, 2024 |
| 3Logic Gro... | AMUR DMB-H310-MCA01         | [3b98bf5ca7](https://linux-hardware.org/?probe=3b98bf5ca7) | Mar 11, 2024 |
| INTECH PRO    | H510-M2 v5.0                | [6afefbab74](https://linux-hardware.org/?probe=6afefbab74) | Mar 11, 2024 |
| ASUSTek       | PRIME B360M-D               | [7d2950146c](https://linux-hardware.org/?probe=7d2950146c) | Mar 09, 2024 |
| MSI           | H61I-E35                    | [dbc777c090](https://linux-hardware.org/?probe=dbc777c090) | Mar 07, 2024 |
| MSI           | H61I-E35                    | [d9c1e6f02c](https://linux-hardware.org/?probe=d9c1e6f02c) | Feb 29, 2024 |
| MSI           | H61I-E35                    | [7c13263839](https://linux-hardware.org/?probe=7c13263839) | Feb 29, 2024 |
| MSI           | H61I-E35                    | [b389d340cc](https://linux-hardware.org/?probe=b389d340cc) | Feb 29, 2024 |
| MSI           | H61I-E35                    | [42d07a20da](https://linux-hardware.org/?probe=42d07a20da) | Feb 29, 2024 |
| MSI           | H61I-E35                    | [be3349f314](https://linux-hardware.org/?probe=be3349f314) | Feb 29, 2024 |
| Gigabyte      | H510M H                     | [e3f138dca5](https://linux-hardware.org/?probe=e3f138dca5) | Feb 28, 2024 |
| Gigabyte      | H510M H                     | [3f8d7911a8](https://linux-hardware.org/?probe=3f8d7911a8) | Feb 28, 2024 |
| Unknown       | T610D11-ALD                 | [5015ded00e](https://linux-hardware.org/?probe=5015ded00e) | Feb 22, 2024 |
| Unknown       | TA320 Series                | [df96f8b57d](https://linux-hardware.org/?probe=df96f8b57d) | Feb 16, 2024 |
| ASUSTek       | PRIME H510T2/CSM            | [6b8f0a0684](https://linux-hardware.org/?probe=6b8f0a0684) | Feb 09, 2024 |
| Gigabyte      | B760M DS3H DDR4             | [672b95fe29](https://linux-hardware.org/?probe=672b95fe29) | Feb 08, 2024 |
| Gigabyte      | B365M H                     | [ac7a22a8f4](https://linux-hardware.org/?probe=ac7a22a8f4) | Jan 30, 2024 |
| Unknown       | T360D11                     | [4f06f14ee6](https://linux-hardware.org/?probe=4f06f14ee6) | Jan 30, 2024 |
| Gigabyte      | B360HD3                     | [7a7e6d1518](https://linux-hardware.org/?probe=7a7e6d1518) | Jan 30, 2024 |
| Gigabyte      | B75M-D3V                    | [5628f77cd1](https://linux-hardware.org/?probe=5628f77cd1) | Jan 30, 2024 |
| ASUSTek       | X99-E WS                    | [92cb95eaef](https://linux-hardware.org/?probe=92cb95eaef) | Jan 25, 2024 |
| ASRock        | B365M-ITX/ac                | [1a48a2a936](https://linux-hardware.org/?probe=1a48a2a936) | Jan 24, 2024 |
| ASRock        | B365M-ITX/ac                | [e7719cba1d](https://linux-hardware.org/?probe=e7719cba1d) | Jan 24, 2024 |
| ASRock        | B365M-ITX/ac                | [b2abf616b0](https://linux-hardware.org/?probe=b2abf616b0) | Jan 24, 2024 |
| HP            | 3399                        | [5126e6fb32](https://linux-hardware.org/?probe=5126e6fb32) | Jan 23, 2024 |
| Foxconn       | 2ABF                        | [4983fd3ab4](https://linux-hardware.org/?probe=4983fd3ab4) | Jan 22, 2024 |
| ASRock        | B365M-ITX/ac                | [45d94979a5](https://linux-hardware.org/?probe=45d94979a5) | Jan 19, 2024 |
| MSI           | PRO H610M-E DDR4            | [66e82c879d](https://linux-hardware.org/?probe=66e82c879d) | Jan 19, 2024 |
| MSI           | PRO H610M-E DDR4            | [af8a99bcf3](https://linux-hardware.org/?probe=af8a99bcf3) | Jan 19, 2024 |
| ASRock        | H81M-VG4 R2.0               | [f13e1664ba](https://linux-hardware.org/?probe=f13e1664ba) | Jan 12, 2024 |
| BESHTAU       | B560RU V51                  | [dec20966d4](https://linux-hardware.org/?probe=dec20966d4) | Jan 11, 2024 |
| ASUSTek       | H97M-E                      | [090fcf5a52](https://linux-hardware.org/?probe=090fcf5a52) | Dec 21, 2023 |
| Lenovo        | ThinkCentre A70 7099L8G     | [9720608634](https://linux-hardware.org/?probe=9720608634) | Dec 20, 2023 |
| ASUSTek       | PRIME B360M-K               | [d52ec68e39](https://linux-hardware.org/?probe=d52ec68e39) | Dec 18, 2023 |
| Biostar       | H610MH                      | [6a0d454360](https://linux-hardware.org/?probe=6a0d454360) | Dec 18, 2023 |
| MSI           | A320M-A PRO                 | [0542ba556a](https://linux-hardware.org/?probe=0542ba556a) | Dec 10, 2023 |
| ASRock        | B365M-ITX/ac                | [01d47685dd](https://linux-hardware.org/?probe=01d47685dd) | Dec 06, 2023 |
| Gigabyte      | A320M-S2H-CF                | [ae4263fce1](https://linux-hardware.org/?probe=ae4263fce1) | Nov 28, 2023 |
| Gigabyte      | H410M S2H V2                | [07a85d20b8](https://linux-hardware.org/?probe=07a85d20b8) | Nov 27, 2023 |
| ASUSTek       | P8H61 PRO                   | [f5ae04b987](https://linux-hardware.org/?probe=f5ae04b987) | Nov 22, 2023 |
| Dell          | 0MGK50 A02                  | [44cca29f66](https://linux-hardware.org/?probe=44cca29f66) | Nov 21, 2023 |
| ASUSTek       | P8H61 PRO                   | [e029a02461](https://linux-hardware.org/?probe=e029a02461) | Nov 21, 2023 |
| ASUSTek       | P8H61 PRO                   | [966108e5dc](https://linux-hardware.org/?probe=966108e5dc) | Nov 21, 2023 |
| Gigabyte      | PH67A-D3-B3                 | [b95aa31de0](https://linux-hardware.org/?probe=b95aa31de0) | Nov 21, 2023 |
| Gigabyte      | H61M-S1                     | [5b55e90cd2](https://linux-hardware.org/?probe=5b55e90cd2) | Nov 20, 2023 |
| ASUSTek       | Z87-A                       | [ef419190cb](https://linux-hardware.org/?probe=ef419190cb) | Nov 20, 2023 |
| Gigabyte      | H270-HD3-CF                 | [c492bd0c05](https://linux-hardware.org/?probe=c492bd0c05) | Nov 20, 2023 |
| Gigabyte      | A320M-S2H-CF                | [05b1279d72](https://linux-hardware.org/?probe=05b1279d72) | Nov 20, 2023 |
| Gigabyte      | H270-HD3-CF                 | [d203bd1f2e](https://linux-hardware.org/?probe=d203bd1f2e) | Nov 20, 2023 |
| ASUSTek       | PRIME B350M-K               | [3fb45b3fae](https://linux-hardware.org/?probe=3fb45b3fae) | Nov 20, 2023 |
| ASUSTek       | PRIME B350M-K               | [1e85870bb4](https://linux-hardware.org/?probe=1e85870bb4) | Nov 20, 2023 |
| Gigabyte      | A320M-S2H-CF                | [d97ba119eb](https://linux-hardware.org/?probe=d97ba119eb) | Nov 20, 2023 |
| Unknown       | TA320 Series                | [2ba015f4da](https://linux-hardware.org/?probe=2ba015f4da) | Nov 20, 2023 |
| ASRock        | B365M-ITX/ac                | [d9aef8d62e](https://linux-hardware.org/?probe=d9aef8d62e) | Nov 20, 2023 |
| ONDA          | H410D4 IPC                  | [5ace66c92d](https://linux-hardware.org/?probe=5ace66c92d) | Nov 20, 2023 |
| BESHTAU       | B560RU V51                  | [188829d0c2](https://linux-hardware.org/?probe=188829d0c2) | Nov 20, 2023 |
| ICL           | H410SB-TM2                  | [d63641c6e3](https://linux-hardware.org/?probe=d63641c6e3) | Nov 17, 2023 |
| Gigabyte      | B75M-D3V                    | [2ca3738c72](https://linux-hardware.org/?probe=2ca3738c72) | Nov 17, 2023 |
| ASRock        | H81M-DG4                    | [089b0f3839](https://linux-hardware.org/?probe=089b0f3839) | Nov 17, 2023 |
| ASRock        | B365M Pro4-F                | [cc09f89cd0](https://linux-hardware.org/?probe=cc09f89cd0) | Nov 09, 2023 |
| ASRock        | B365M Pro4-F                | [17ec369170](https://linux-hardware.org/?probe=17ec369170) | Nov 09, 2023 |
| Gigabyte      | A320M-H-CF                  | [290c167538](https://linux-hardware.org/?probe=290c167538) | Nov 08, 2023 |
| Gigabyte      | B75M-D3V                    | [c6d1fc4965](https://linux-hardware.org/?probe=c6d1fc4965) | Oct 31, 2023 |
| Gigabyte      | H510M H                     | [d89e17690d](https://linux-hardware.org/?probe=d89e17690d) | Oct 31, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [893389d935](https://linux-hardware.org/?probe=893389d935) | Oct 25, 2023 |
| Lenovo        | 1052 SDK0J40697 WIN 3305... | [9bf87234d6](https://linux-hardware.org/?probe=9bf87234d6) | Oct 23, 2023 |
| Lenovo        | 1052 SDK0J40697 WIN 3305... | [d1f56e838d](https://linux-hardware.org/?probe=d1f56e838d) | Oct 23, 2023 |
| MSI           | A320M-A PRO                 | [6290cec60c](https://linux-hardware.org/?probe=6290cec60c) | Oct 20, 2023 |
| MSI           | A320M-A PRO                 | [287fa14302](https://linux-hardware.org/?probe=287fa14302) | Oct 20, 2023 |
| Gigabyte      | B75M-D3V                    | [0fd9732532](https://linux-hardware.org/?probe=0fd9732532) | Oct 19, 2023 |
| Unknown       | Unknown                     | [9947f3f38b](https://linux-hardware.org/?probe=9947f3f38b) | Oct 17, 2023 |
| ASRock        | H510M-HVS R2.0              | [83c36787ea](https://linux-hardware.org/?probe=83c36787ea) | Oct 17, 2023 |
| ASUSTek       | P8Z77-V LX                  | [6457a793cd](https://linux-hardware.org/?probe=6457a793cd) | Oct 14, 2023 |
| Lenovo        | 3752 NOK                    | [e3eda8aae7](https://linux-hardware.org/?probe=e3eda8aae7) | Oct 10, 2023 |
| Lenovo        | 3752 NOK                    | [5e3d37b336](https://linux-hardware.org/?probe=5e3d37b336) | Oct 05, 2023 |
| Gigabyte      | H61M-DS2H                   | [f3e31ed154](https://linux-hardware.org/?probe=f3e31ed154) | Sep 22, 2023 |
| Unknown       | DMB-A520-MCA01              | [a959513e7c](https://linux-hardware.org/?probe=a959513e7c) | Sep 18, 2023 |
| Gigabyte      | H110M-H-CF                  | [5eadb71ae4](https://linux-hardware.org/?probe=5eadb71ae4) | Sep 15, 2023 |
| ASRock        | H510M-HVS R2.0              | [018a3b8abe](https://linux-hardware.org/?probe=018a3b8abe) | Sep 08, 2023 |
| MSI           | MS-B0A41                    | [c93409061c](https://linux-hardware.org/?probe=c93409061c) | Sep 06, 2023 |
| DEPO Compu... | DPH410S                     | [88076446b3](https://linux-hardware.org/?probe=88076446b3) | Aug 18, 2023 |
| DEPO Compu... | DPH410S                     | [201a0612e4](https://linux-hardware.org/?probe=201a0612e4) | Aug 18, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS II    | [fb99152b24](https://linux-hardware.org/?probe=fb99152b24) | Aug 10, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS II    | [5aeb5ebcbf](https://linux-hardware.org/?probe=5aeb5ebcbf) | Aug 09, 2023 |
| Gigabyte      | B360HD3                     | [4dc4fb1691](https://linux-hardware.org/?probe=4dc4fb1691) | Aug 08, 2023 |
| Gigabyte      | B360HD3                     | [b297b777be](https://linux-hardware.org/?probe=b297b777be) | Jul 25, 2023 |
| Biostar       | H610MH                      | [ba1951d1fa](https://linux-hardware.org/?probe=ba1951d1fa) | Jun 19, 2023 |
| ASRock        | A320M-HDV R4.0              | [2a3c6cf0ab](https://linux-hardware.org/?probe=2a3c6cf0ab) | Jun 14, 2023 |
| Gigabyte      | H510M H                     | [337e4a106e](https://linux-hardware.org/?probe=337e4a106e) | Jun 13, 2023 |
| Dell          | 0VNM11 A01                  | [df3c87a033](https://linux-hardware.org/?probe=df3c87a033) | Jun 02, 2023 |
| Dell          | 0VNM11 A01                  | [308b943182](https://linux-hardware.org/?probe=308b943182) | Jun 01, 2023 |
| Gigabyte      | B450 GAMING X               | [b92d2128ad](https://linux-hardware.org/?probe=b92d2128ad) | Jun 01, 2023 |
| Gigabyte      | B560M D3H                   | [8579e0281a](https://linux-hardware.org/?probe=8579e0281a) | May 30, 2023 |
| HP            | 83F0                        | [77cfad8631](https://linux-hardware.org/?probe=77cfad8631) | May 26, 2023 |
| Gigabyte      | A320M-S2H-CF                | [a98cdfee26](https://linux-hardware.org/?probe=a98cdfee26) | May 25, 2023 |
| Gigabyte      | Z77-DS3H                    | [1e1fb2110f](https://linux-hardware.org/?probe=1e1fb2110f) | May 24, 2023 |
| MSI           | H510M-A PRO                 | [c5f452ea28](https://linux-hardware.org/?probe=c5f452ea28) | May 18, 2023 |
| Aquarius      | AQH410T                     | [aeeb40c393](https://linux-hardware.org/?probe=aeeb40c393) | May 04, 2023 |
| Unknown       | Unknown                     | [3522381ca7](https://linux-hardware.org/?probe=3522381ca7) | May 02, 2023 |
| Unknown       | Unknown                     | [4ec0da1442](https://linux-hardware.org/?probe=4ec0da1442) | May 02, 2023 |
| MSI           | A520M PRO                   | [6d37fb0e46](https://linux-hardware.org/?probe=6d37fb0e46) | May 02, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [41d545e4d7](https://linux-hardware.org/?probe=41d545e4d7) | Apr 28, 2023 |
| ASRock        | B365M-ITX/ac                | [e4c8218911](https://linux-hardware.org/?probe=e4c8218911) | Apr 27, 2023 |
| Gigabyte      | B365M H                     | [aca220e594](https://linux-hardware.org/?probe=aca220e594) | Apr 22, 2023 |
| Gigabyte      | H310M S2H x.x               | [eec2055c19](https://linux-hardware.org/?probe=eec2055c19) | Apr 20, 2023 |
| Intel         | DH61BF AAG81311-101         | [a9329736fb](https://linux-hardware.org/?probe=a9329736fb) | Apr 19, 2023 |
| Gigabyte      | H61M-S1                     | [e2ed275252](https://linux-hardware.org/?probe=e2ed275252) | Apr 19, 2023 |
| Gigabyte      | H61M-S1                     | [a6aaf5f17a](https://linux-hardware.org/?probe=a6aaf5f17a) | Apr 19, 2023 |
| MSI           | G41M-P33 Combo              | [d2623477d9](https://linux-hardware.org/?probe=d2623477d9) | Apr 10, 2023 |
| Intel         | D945GNT AAC96315-405        | [cdfdfbcda4](https://linux-hardware.org/?probe=cdfdfbcda4) | Apr 07, 2023 |
| Intel         | DH61BF AAG81311-101         | [49921908d1](https://linux-hardware.org/?probe=49921908d1) | Apr 06, 2023 |
| MSI           | PRO Z790-A WIFI             | [5fd883493a](https://linux-hardware.org/?probe=5fd883493a) | Apr 03, 2023 |
| MSI           | G41M-P33 Combo              | [44b5c81131](https://linux-hardware.org/?probe=44b5c81131) | Apr 03, 2023 |
| Quanta        | 2AC5 100                    | [7f253a82dc](https://linux-hardware.org/?probe=7f253a82dc) | Mar 31, 2023 |
| MSI           | G31TM-P21                   | [7404d94ca4](https://linux-hardware.org/?probe=7404d94ca4) | Mar 31, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [3ad3c5e45c](https://linux-hardware.org/?probe=3ad3c5e45c) | Mar 30, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [8400d48ed0](https://linux-hardware.org/?probe=8400d48ed0) | Mar 29, 2023 |
| MSI           | G41M-P33 Combo              | [ea8ce90ed5](https://linux-hardware.org/?probe=ea8ce90ed5) | Mar 27, 2023 |
| HP            | 0AA4h                       | [a77b084eba](https://linux-hardware.org/?probe=a77b084eba) | Mar 25, 2023 |
| Intel         | D945GNT AAC96315-405        | [fcc7a18f89](https://linux-hardware.org/?probe=fcc7a18f89) | Mar 24, 2023 |
| DEPO Compu... | MS-7846                     | [baaaef2394](https://linux-hardware.org/?probe=baaaef2394) | Mar 22, 2023 |
| Intel         | D945GNT AAC96315-405        | [58c99c07a6](https://linux-hardware.org/?probe=58c99c07a6) | Mar 17, 2023 |
| Biostar       | H610MH                      | [6b367d747d](https://linux-hardware.org/?probe=6b367d747d) | Mar 16, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [9e172b266b](https://linux-hardware.org/?probe=9e172b266b) | Mar 16, 2023 |
| HP            | 0B4Ch D                     | [a26dff699b](https://linux-hardware.org/?probe=a26dff699b) | Mar 14, 2023 |
| ASRock        | H61M-DGS                    | [47b6690dc8](https://linux-hardware.org/?probe=47b6690dc8) | Mar 13, 2023 |
| ASRock        | H61M-DGS                    | [7c7bdc15fe](https://linux-hardware.org/?probe=7c7bdc15fe) | Mar 13, 2023 |
| Gigabyte      | B560M AORUS PRO             | [9442ced293](https://linux-hardware.org/?probe=9442ced293) | Mar 09, 2023 |
| HP            | 8599                        | [2b9bd0b4a7](https://linux-hardware.org/?probe=2b9bd0b4a7) | Mar 07, 2023 |
| ASUSTek       | P5GC-MX/1333                | [ccb99906a8](https://linux-hardware.org/?probe=ccb99906a8) | Mar 06, 2023 |
| MSI           | G41M-P33 Combo              | [a78a4114e6](https://linux-hardware.org/?probe=a78a4114e6) | Mar 06, 2023 |
| ASRock        | H61M-DGS                    | [388d4b38c1](https://linux-hardware.org/?probe=388d4b38c1) | Mar 06, 2023 |
| ASUSTek       | P5GC-MX/1333                | [6d97e48a7e](https://linux-hardware.org/?probe=6d97e48a7e) | Mar 06, 2023 |
| ASRock        | H61M-DGS                    | [8741c0e2f1](https://linux-hardware.org/?probe=8741c0e2f1) | Mar 06, 2023 |
| ASUSTek       | PRIME B560M-K               | [9e1f0243d7](https://linux-hardware.org/?probe=9e1f0243d7) | Mar 06, 2023 |
| Intel         | D945GNT AAC96315-405        | [0d02616013](https://linux-hardware.org/?probe=0d02616013) | Mar 03, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [2485632618](https://linux-hardware.org/?probe=2485632618) | Mar 02, 2023 |
| ASRock        | H510M-HVS R2.0              | [9acee9d7d4](https://linux-hardware.org/?probe=9acee9d7d4) | Mar 02, 2023 |
| Aquarius      | AQB560M                     | [fedd6483cd](https://linux-hardware.org/?probe=fedd6483cd) | Mar 01, 2023 |
| Aquarius      | AQB560M                     | [ee0c530562](https://linux-hardware.org/?probe=ee0c530562) | Feb 28, 2023 |
| Foxconn       | 2ABF                        | [d6eb6b4839](https://linux-hardware.org/?probe=d6eb6b4839) | Feb 28, 2023 |
| Gigabyte      | B365M H                     | [dbb3e73c89](https://linux-hardware.org/?probe=dbb3e73c89) | Feb 27, 2023 |
| Intel         | DH61CR AAG14064-204         | [f511e61852](https://linux-hardware.org/?probe=f511e61852) | Feb 21, 2023 |
| Lenovo        | ThinkCentre M91p 4524PL4    | [5cda5522e8](https://linux-hardware.org/?probe=5cda5522e8) | Feb 21, 2023 |
| Intel         | DH61CR AAG14064-204         | [eec6e2f905](https://linux-hardware.org/?probe=eec6e2f905) | Feb 21, 2023 |
| HP            | 18E7                        | [2c779d2395](https://linux-hardware.org/?probe=2c779d2395) | Feb 17, 2023 |
| iRU           | v1.0                        | [9d70818485](https://linux-hardware.org/?probe=9d70818485) | Feb 17, 2023 |
| ICL           | H410SB                      | [e994f10643](https://linux-hardware.org/?probe=e994f10643) | Feb 14, 2023 |
| MSI           | PRO B660M-E DDR4            | [aab30259f8](https://linux-hardware.org/?probe=aab30259f8) | Feb 13, 2023 |
| Gigabyte      | B560M DS3H V2               | [2512d8d9ab](https://linux-hardware.org/?probe=2512d8d9ab) | Feb 10, 2023 |
| MSI           | H510M-A PRO                 | [dea6a1a077](https://linux-hardware.org/?probe=dea6a1a077) | Feb 09, 2023 |
| Gigabyte      | B365M DS3H                  | [4bc9beae71](https://linux-hardware.org/?probe=4bc9beae71) | Feb 07, 2023 |
| Gigabyte      | M61SME-S2                   | [395b6fa893](https://linux-hardware.org/?probe=395b6fa893) | Feb 06, 2023 |
| Lenovo        | 3708 NOK                    | [b306f4c9dc](https://linux-hardware.org/?probe=b306f4c9dc) | Feb 06, 2023 |
| Compal        | DIP00                       | [fc6de899ba](https://linux-hardware.org/?probe=fc6de899ba) | Feb 06, 2023 |
| ASRock        | H61M-VG4                    | [b2fec94855](https://linux-hardware.org/?probe=b2fec94855) | Feb 05, 2023 |
| HP            | 8599                        | [3ffedfbc62](https://linux-hardware.org/?probe=3ffedfbc62) | Jan 31, 2023 |
| HP            | 8599                        | [759d3a0829](https://linux-hardware.org/?probe=759d3a0829) | Jan 31, 2023 |
| Gigabyte      | B365M H                     | [89d336f0b7](https://linux-hardware.org/?probe=89d336f0b7) | Jan 30, 2023 |
| DEPO Compu... | DPH410S                     | [d380c83ebf](https://linux-hardware.org/?probe=d380c83ebf) | Jan 28, 2023 |
| ASUSTek       | H81M-K                      | [13f23afb38](https://linux-hardware.org/?probe=13f23afb38) | Jan 27, 2023 |
| Aquarius      | AQB560M                     | [1187e4d240](https://linux-hardware.org/?probe=1187e4d240) | Jan 27, 2023 |
| Lenovo        | ThinkCentre M70e 0851RZ3    | [23b8d711f4](https://linux-hardware.org/?probe=23b8d711f4) | Jan 25, 2023 |
| MSI           | PRO H610M-E DDR4            | [8a06b2350d](https://linux-hardware.org/?probe=8a06b2350d) | Jan 25, 2023 |
| MSI           | PRO H610M-E DDR4            | [d5c4129361](https://linux-hardware.org/?probe=d5c4129361) | Jan 23, 2023 |
| HP            | 18E4                        | [9a62a59c37](https://linux-hardware.org/?probe=9a62a59c37) | Jan 20, 2023 |
| ASUSTek       | PRIME B460M-K               | [86d4a0e87c](https://linux-hardware.org/?probe=86d4a0e87c) | Jan 20, 2023 |
| Gigabyte      | B360HD3                     | [cbd81c917f](https://linux-hardware.org/?probe=cbd81c917f) | Jan 20, 2023 |
| Gigabyte      | H610M S2H DDR4              | [4e77673e60](https://linux-hardware.org/?probe=4e77673e60) | Jan 19, 2023 |
| MSI           | PRO H610M-E DDR4            | [3f185b85f5](https://linux-hardware.org/?probe=3f185b85f5) | Jan 18, 2023 |
| ASUSTek       | H81M-K                      | [1e6f35ceff](https://linux-hardware.org/?probe=1e6f35ceff) | Jan 18, 2023 |
| Gigabyte      | B360HD3                     | [3fb3939014](https://linux-hardware.org/?probe=3fb3939014) | Jan 18, 2023 |
| Gigabyte      | B360HD3                     | [8b992a1d50](https://linux-hardware.org/?probe=8b992a1d50) | Jan 17, 2023 |
| ASUSTek       | H81M-K                      | [a4ee55fea9](https://linux-hardware.org/?probe=a4ee55fea9) | Jan 17, 2023 |
| Unknown       | T310D11                     | [acce0e1df1](https://linux-hardware.org/?probe=acce0e1df1) | Jan 16, 2023 |
| Gigabyte      | B360HD3                     | [6c3f234091](https://linux-hardware.org/?probe=6c3f234091) | Jan 11, 2023 |
| ASUSTek       | H81M-K                      | [2e985853be](https://linux-hardware.org/?probe=2e985853be) | Jan 11, 2023 |
| ASUSTek       | PRIME H610M-K D4            | [31ecdfb704](https://linux-hardware.org/?probe=31ecdfb704) | Jan 11, 2023 |
| ASUSTek       | PRIME B365M-A               | [4f9477b846](https://linux-hardware.org/?probe=4f9477b846) | Jan 08, 2023 |
| ASUSTek       | M5A78L-M LX V2              | [f040219e23](https://linux-hardware.org/?probe=f040219e23) | Dec 26, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | [b5ff4bd9d6](https://linux-hardware.org/?probe=b5ff4bd9d6) | Dec 26, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | [f5f35c12a4](https://linux-hardware.org/?probe=f5f35c12a4) | Dec 23, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | [686b84facc](https://linux-hardware.org/?probe=686b84facc) | Dec 23, 2022 |
| DEPO Compu... | DPH410S                     | [0ba02e46fa](https://linux-hardware.org/?probe=0ba02e46fa) | Dec 22, 2022 |
| MSI           | B450-A PRO MAX              | [8ea27950b9](https://linux-hardware.org/?probe=8ea27950b9) | Dec 21, 2022 |
| Gigabyte      | M61SME-S2                   | [8babc33ab6](https://linux-hardware.org/?probe=8babc33ab6) | Dec 17, 2022 |
| MSI           | B450-A PRO MAX              | [257ccc50d8](https://linux-hardware.org/?probe=257ccc50d8) | Dec 15, 2022 |
| Colorful T... | H610M-K M.2 V20             | [795e44f6f2](https://linux-hardware.org/?probe=795e44f6f2) | Dec 15, 2022 |
| Gigabyte      | H110M-S2-CF                 | [af9afd9f4b](https://linux-hardware.org/?probe=af9afd9f4b) | Dec 14, 2022 |
| ASUSTek       | PB62                        | [fb3796ceea](https://linux-hardware.org/?probe=fb3796ceea) | Dec 12, 2022 |
| ASUSTek       | PB62                        | [4d4a5fcc93](https://linux-hardware.org/?probe=4d4a5fcc93) | Dec 12, 2022 |
| Gigabyte      | B365M DS3H                  | [89e51f2eaa](https://linux-hardware.org/?probe=89e51f2eaa) | Dec 09, 2022 |
| ASUSTek       | P7H55-M                     | [aaa5171bd6](https://linux-hardware.org/?probe=aaa5171bd6) | Dec 06, 2022 |
| ASRock        | H510M-HVS R2.0              | [4309758f8f](https://linux-hardware.org/?probe=4309758f8f) | Dec 02, 2022 |
| Gigabyte      | B365M DS3H                  | [4b9ee0ef6a](https://linux-hardware.org/?probe=4b9ee0ef6a) | Nov 28, 2022 |
| Gigabyte      | H410M S2H V3                | [8882bfe4f8](https://linux-hardware.org/?probe=8882bfe4f8) | Nov 28, 2022 |
| Gigabyte      | X570S UD                    | [381b3c892d](https://linux-hardware.org/?probe=381b3c892d) | Nov 25, 2022 |
| ASUSTek       | PRIME Z590-P                | [7d6cf8c81f](https://linux-hardware.org/?probe=7d6cf8c81f) | Nov 24, 2022 |
| Gigabyte      | B365M DS3H                  | [e48d26b26f](https://linux-hardware.org/?probe=e48d26b26f) | Nov 21, 2022 |
| ASRock        | P43Twins1600                | [1db44f50c4](https://linux-hardware.org/?probe=1db44f50c4) | Nov 18, 2022 |
| ASRock        | H310CM-DVS                  | [23194fe7d9](https://linux-hardware.org/?probe=23194fe7d9) | Nov 16, 2022 |
| HP            | 2179                        | [3407225f33](https://linux-hardware.org/?probe=3407225f33) | Nov 14, 2022 |
| ASRock        | H310CM-DVS                  | [86932d2426](https://linux-hardware.org/?probe=86932d2426) | Nov 14, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | [ef983bc60e](https://linux-hardware.org/?probe=ef983bc60e) | Nov 11, 2022 |
| ASRock        | H61M-VG4                    | [63f5fe9444](https://linux-hardware.org/?probe=63f5fe9444) | Nov 04, 2022 |
| Gigabyte      | A520M DS3H                  | [8fe13e2165](https://linux-hardware.org/?probe=8fe13e2165) | Nov 02, 2022 |
| ASRock        | H510M-HVS R2.0              | [562f466f8d](https://linux-hardware.org/?probe=562f466f8d) | Nov 02, 2022 |
| ASRock        | B450M Pro4                  | [38b68c6946](https://linux-hardware.org/?probe=38b68c6946) | Nov 02, 2022 |
| ASRock        | H510M-HVS R2.0              | [b68271c648](https://linux-hardware.org/?probe=b68271c648) | Nov 02, 2022 |
| Gigabyte      | B450M H                     | [06bbc75ef0](https://linux-hardware.org/?probe=06bbc75ef0) | Nov 01, 2022 |
| MSI           | 0A90                        | [47fa407c02](https://linux-hardware.org/?probe=47fa407c02) | Nov 01, 2022 |
| Gigabyte      | B560M H                     | [00766db60b](https://linux-hardware.org/?probe=00766db60b) | Oct 28, 2022 |
| MSI           | 0A90                        | [a15ab9db5e](https://linux-hardware.org/?probe=a15ab9db5e) | Oct 28, 2022 |
| Gigabyte      | GA-880GM-D2H                | [cacdacb3ad](https://linux-hardware.org/?probe=cacdacb3ad) | Oct 28, 2022 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | [9c429fe90c](https://linux-hardware.org/?probe=9c429fe90c) | Oct 27, 2022 |
| ASUSTek       | H81M-K                      | [92dbe47379](https://linux-hardware.org/?probe=92dbe47379) | Oct 25, 2022 |
| ASUSTek       | H81M-K                      | [247782b262](https://linux-hardware.org/?probe=247782b262) | Oct 25, 2022 |
| Lenovo        | 3708 NOK                    | [f48f731517](https://linux-hardware.org/?probe=f48f731517) | Oct 21, 2022 |
| Gigabyte      | B360HD3                     | [bbbdee0883](https://linux-hardware.org/?probe=bbbdee0883) | Oct 21, 2022 |
| Gigabyte      | B75M-D3V                    | [71c9391b8b](https://linux-hardware.org/?probe=71c9391b8b) | Oct 21, 2022 |
| Gigabyte      | H510M S2H                   | [e75a8830af](https://linux-hardware.org/?probe=e75a8830af) | Oct 19, 2022 |
| Gigabyte      | H510M S2H                   | [b8303261ad](https://linux-hardware.org/?probe=b8303261ad) | Oct 18, 2022 |
| ASUSTek       | H81M-K                      | [c6958291bd](https://linux-hardware.org/?probe=c6958291bd) | Oct 14, 2022 |
| HP            | 1495                        | [b1523ff4a6](https://linux-hardware.org/?probe=b1523ff4a6) | Oct 13, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | [087d1975e1](https://linux-hardware.org/?probe=087d1975e1) | Oct 12, 2022 |
| ASUSTek       | B150M-C                     | [1d936352ea](https://linux-hardware.org/?probe=1d936352ea) | Oct 10, 2022 |
| Gigabyte      | H110M-S2-CF                 | [e799b41d70](https://linux-hardware.org/?probe=e799b41d70) | Oct 09, 2022 |
| MSI           | H55M-E33                    | [95423ecdbe](https://linux-hardware.org/?probe=95423ecdbe) | Oct 07, 2022 |
| ASRock        | B460M Pro4                  | [9fd01561ce](https://linux-hardware.org/?probe=9fd01561ce) | Oct 07, 2022 |
| ASRock        | B460M Pro4                  | [4c0bb83f01](https://linux-hardware.org/?probe=4c0bb83f01) | Oct 07, 2022 |
| MSI           | H55M-E33                    | [7af53a4dee](https://linux-hardware.org/?probe=7af53a4dee) | Oct 06, 2022 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | [b90de94f3d](https://linux-hardware.org/?probe=b90de94f3d) | Oct 05, 2022 |
| ASRock        | B360M-HDV                   | [fad5a877f5](https://linux-hardware.org/?probe=fad5a877f5) | Sep 30, 2022 |
| RDW           | MB-B450M V.1                | [8c3a565d43](https://linux-hardware.org/?probe=8c3a565d43) | Sep 26, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [1748378749](https://linux-hardware.org/?probe=1748378749) | Sep 22, 2022 |
| Gigabyte      | B75M-D3V                    | [3888b56318](https://linux-hardware.org/?probe=3888b56318) | Sep 22, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [66a228f8c5](https://linux-hardware.org/?probe=66a228f8c5) | Sep 21, 2022 |
| Gigabyte      | H110M-S2-CF                 | [fd03d25b78](https://linux-hardware.org/?probe=fd03d25b78) | Sep 15, 2022 |
| ECS           | H510H6-M7                   | [1275257180](https://linux-hardware.org/?probe=1275257180) | Sep 14, 2022 |
| Unknown       | Unknown                     | [40c1fd4544](https://linux-hardware.org/?probe=40c1fd4544) | Sep 05, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [04b62ac6e3](https://linux-hardware.org/?probe=04b62ac6e3) | Sep 04, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [a60315c259](https://linux-hardware.org/?probe=a60315c259) | Sep 04, 2022 |
| ASRock        | N68-VS3 FX                  | [b4c043c208](https://linux-hardware.org/?probe=b4c043c208) | Sep 01, 2022 |
| ASRock        | B365M Pro4-F                | [3b519201e2](https://linux-hardware.org/?probe=3b519201e2) | Aug 22, 2022 |
| Gigabyte      | X58-USB3                    | [5119bcb630](https://linux-hardware.org/?probe=5119bcb630) | Aug 19, 2022 |
| ASRock        | H110M-DVS R2.0              | [c02a953cda](https://linux-hardware.org/?probe=c02a953cda) | Aug 01, 2022 |
| Gigabyte      | B365M DS3H                  | [14f73b6a3a](https://linux-hardware.org/?probe=14f73b6a3a) | Aug 01, 2022 |
| Dell          | 040DDP A00                  | [5375c9c059](https://linux-hardware.org/?probe=5375c9c059) | Jul 26, 2022 |
| DEPO Compu... | DPH310T                     | [7cc031e93b](https://linux-hardware.org/?probe=7cc031e93b) | Jul 22, 2022 |
| DEPO Compu... | DPH310T                     | [946610c122](https://linux-hardware.org/?probe=946610c122) | Jul 22, 2022 |
| DEPO Compu... | DPH310T                     | [fbff39be7e](https://linux-hardware.org/?probe=fbff39be7e) | Jul 22, 2022 |
| DEPO Compu... | DPH310T                     | [0076bf5efc](https://linux-hardware.org/?probe=0076bf5efc) | Jul 22, 2022 |
| Gigabyte      | 970A-D3                     | [f2ae77cc0c](https://linux-hardware.org/?probe=f2ae77cc0c) | Jul 17, 2022 |
| ASUSTek       | M2N68-AM Plus               | [d85cded80a](https://linux-hardware.org/?probe=d85cded80a) | Jun 20, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | [28e8a1e19c](https://linux-hardware.org/?probe=28e8a1e19c) | Jun 07, 2022 |
| ASUSTek       | H81M-K                      | [df5b1991e1](https://linux-hardware.org/?probe=df5b1991e1) | Jun 07, 2022 |
| HP            | 0B4Ch D                     | [8ea7efbf2e](https://linux-hardware.org/?probe=8ea7efbf2e) | Jun 07, 2022 |
| MSI           | A520M PRO                   | [3eb8006c14](https://linux-hardware.org/?probe=3eb8006c14) | May 26, 2022 |
| MSI           | A520M PRO                   | [9766bbe4c0](https://linux-hardware.org/?probe=9766bbe4c0) | May 25, 2022 |
| ASRock        | B365M Pro4-F                | [b3b2ee08af](https://linux-hardware.org/?probe=b3b2ee08af) | May 23, 2022 |
| MSI           | H510TI-S01                  | [efe42ef07a](https://linux-hardware.org/?probe=efe42ef07a) | May 19, 2022 |
| Gigabyte      | B365M H                     | [e405d209d4](https://linux-hardware.org/?probe=e405d209d4) | May 11, 2022 |
| ASUSTek       | H81M-K                      | [66bb3248d5](https://linux-hardware.org/?probe=66bb3248d5) | May 11, 2022 |
| ASRock        | B560 Pro4                   | [1c3459c038](https://linux-hardware.org/?probe=1c3459c038) | Apr 19, 2022 |
| Gigabyte      | B75M-D3V                    | [d648ac5ab2](https://linux-hardware.org/?probe=d648ac5ab2) | Apr 01, 2022 |
| Gigabyte      | B75M-D2V                    | [7b4861c8af](https://linux-hardware.org/?probe=7b4861c8af) | Apr 01, 2022 |
| Gigabyte      | H410M H V3                  | [9d86d8119a](https://linux-hardware.org/?probe=9d86d8119a) | Apr 01, 2022 |
| Gigabyte      | B75M-D2V                    | [b8ff95c0f1](https://linux-hardware.org/?probe=b8ff95c0f1) | Mar 30, 2022 |
| ASUSTek       | H110-PLUS                   | [5074891336](https://linux-hardware.org/?probe=5074891336) | Mar 09, 2022 |
| Aquarius      | AQH410T                     | [f02c2d0259](https://linux-hardware.org/?probe=f02c2d0259) | Mar 02, 2022 |
| Aquarius      | AQB560M                     | [091fa6d697](https://linux-hardware.org/?probe=091fa6d697) | Mar 01, 2022 |
| Gigabyte      | B560M DS3H                  | [9db1aef186](https://linux-hardware.org/?probe=9db1aef186) | Feb 18, 2022 |
| ASUSTek       | PRIME H510M-K               | [c1f9ad0faf](https://linux-hardware.org/?probe=c1f9ad0faf) | Feb 01, 2022 |
| Gigabyte      | B75M-D3V                    | [14d2075383](https://linux-hardware.org/?probe=14d2075383) | Jan 31, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | [38ddf02b60](https://linux-hardware.org/?probe=38ddf02b60) | Jan 31, 2022 |
| Gigabyte      | B365M DS3H                  | [36db0c9260](https://linux-hardware.org/?probe=36db0c9260) | Jan 17, 2022 |
| Aquarius      | AQB560M                     | [ff20437ae0](https://linux-hardware.org/?probe=ff20437ae0) | Nov 25, 2021 |
| Aquarius      | AQB560M                     | [4656a05904](https://linux-hardware.org/?probe=4656a05904) | Nov 22, 2021 |
| Gigabyte      | B75M-D2V                    | [ef54320d4b](https://linux-hardware.org/?probe=ef54320d4b) | Oct 19, 2021 |
| Gigabyte      | B560M DS3H                  | [5a071f96dd](https://linux-hardware.org/?probe=5a071f96dd) | Oct 19, 2021 |
| ASRock        | H470M-HDV                   | [ba7bdac2dd](https://linux-hardware.org/?probe=ba7bdac2dd) | Sep 04, 2021 |
| Gigabyte      | H110M-M2-CF                 | [54a20af366](https://linux-hardware.org/?probe=54a20af366) | Aug 27, 2021 |
| ASUSTek       | H110-PLUS                   | [11e1a45e67](https://linux-hardware.org/?probe=11e1a45e67) | Jun 03, 2021 |
| Gigabyte      | B365M DS3H                  | [7b4a0634ef](https://linux-hardware.org/?probe=7b4a0634ef) | Apr 26, 2021 |
| ASUSTek       | H110M-PLUS                  | [b779fb9e40](https://linux-hardware.org/?probe=b779fb9e40) | Apr 09, 2021 |
| ASUSTek       | P8H61-I LX R2.0             | [6e0321d64f](https://linux-hardware.org/?probe=6e0321d64f) | Apr 08, 2021 |
| Gigabyte      | B365M DS3H                  | [d151197565](https://linux-hardware.org/?probe=d151197565) | Mar 26, 2021 |
| ASUSTek       | H81M-K                      | [a61243addd](https://linux-hardware.org/?probe=a61243addd) | Mar 26, 2021 |
| ASUSTek       | H110M-K                     | [30e7a27178](https://linux-hardware.org/?probe=30e7a27178) | Mar 22, 2021 |
| ASUSTek       | H110M-K                     | [da0a735a9f](https://linux-hardware.org/?probe=da0a735a9f) | Mar 18, 2021 |
| ASUSTek       | H81M-K                      | [5898a71c25](https://linux-hardware.org/?probe=5898a71c25) | Nov 03, 2020 |
| Gigabyte      | B360M DS3H                  | [12f125beba](https://linux-hardware.org/?probe=12f125beba) | Jan 16, 2020 |
| Gigabyte      | B360M DS3H                  | [c88331017f](https://linux-hardware.org/?probe=c88331017f) | Jan 16, 2020 |
| ASUSTek       | H81M-K                      | [24adf26804](https://linux-hardware.org/?probe=24adf26804) | Jan 13, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Red_OS/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Red OS 7.3   | 226      | 54.07%  |
| Red OS 8.0   | 76       | 18.18%  |
| Red OS 7.3.1 | 54       | 12.92%  |
| Red OS 7.3.2 | 52       | 12.44%  |
| Red OS 7.2   | 9        | 2.15%   |
| Red OS 8.0.2 | 1        | 0.24%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Red OS | 400      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Desktops | Percent |
|-------------------------|----------|---------|
| 6.1.52-1.el7.3.x86_64   | 69       | 15.75%  |
| 5.15.10-1.el7.x86_64    | 31       | 7.08%   |
| 5.10.29-1.el7.x86_64    | 28       | 6.39%   |
| 5.15.87-1.el7.3.x86_64  | 26       | 5.94%   |
| 5.14.9-1.el7.x86_64     | 25       | 5.71%   |
| 6.6.51-1.red80.x86_64   | 23       | 5.25%   |
| 6.12.21-1.red80.x86_64  | 22       | 5.02%   |
| 5.15.35-5.el7.3.x86_64  | 21       | 4.79%   |
| 6.1.110-1.el7.3.x86_64  | 20       | 4.57%   |
| 5.15.72-1.el7.3.x86_64  | 19       | 4.34%   |
| 6.1.128-2.el7.3.x86_64  | 13       | 2.97%   |
| 6.6.6-1.red80.x86_64    | 12       | 2.74%   |
| 5.15.78-2.el7.3.x86_64  | 11       | 2.51%   |
| 5.15.35-1.el7.3.x86_64  | 10       | 2.28%   |
| 6.6.76-1.red80.x86_64   | 9        | 2.05%   |
| 6.12.37-1.red80.x86_64  | 9        | 2.05%   |
| 6.1.44-1.el7.3.x86_64   | 9        | 2.05%   |
| 5.15.131-1.el7.3.x86_64 | 9        | 2.05%   |
| 5.10.29-3.el7.x86_64    | 8        | 1.83%   |
| 5.15.35-4.el7.3.x86_64  | 7        | 1.6%    |
| 4.19.79-1.el7.x86_64    | 7        | 1.6%    |
| 6.1.94-1.el7.3.x86_64   | 6        | 1.37%   |
| 6.1.20-2.el7.3.x86_64   | 5        | 1.14%   |
| 5.15.167-1.el7.3.x86_64 | 5        | 1.14%   |
| 6.1.148-1.el7.3.x86_64  | 4        | 0.91%   |
| 6.12.56-1.red80.x86_64  | 3        | 0.68%   |
| 6.1.38-2.el7.3.x86_64   | 3        | 0.68%   |
| 6.1.143-1.el7.3.x86_64  | 3        | 0.68%   |
| 5.15.125-1.el7.3.x86_64 | 3        | 0.68%   |
| 5.15.10-3.el7.x86_64    | 3        | 0.68%   |
| 5.15.10-2.el7.x86_64    | 3        | 0.68%   |
| 6.6.34-1.red80.x86_64   | 2        | 0.46%   |
| 6.6.26-1.red80.x86_64   | 2        | 0.46%   |
| 6.1.52-1.red80.x86_64   | 1        | 0.23%   |
| 6.1.158-1.el7.3.x86_64  | 1        | 0.23%   |
| 6.1.11-1.el7.3.x86_64   | 1        | 0.23%   |
| 5.10.24-3.el7.x86_64    | 1        | 0.23%   |
| 5.10.24-2.el7.x86_64    | 1        | 0.23%   |
| 5.10.1-1.el7.x86_64     | 1        | 0.23%   |
| 4.19.56-2.el7.x86_64    | 1        | 0.23%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 6.1.52   | 70       | 16.09%  |
| 5.15.10  | 37       | 8.51%   |
| 5.10.29  | 36       | 8.28%   |
| 5.15.35  | 35       | 8.05%   |
| 5.15.87  | 26       | 5.98%   |
| 5.14.9   | 25       | 5.75%   |
| 6.6.51   | 23       | 5.29%   |
| 6.12.21  | 22       | 5.06%   |
| 6.1.110  | 20       | 4.6%    |
| 5.15.72  | 19       | 4.37%   |
| 6.1.128  | 13       | 2.99%   |
| 6.6.6    | 12       | 2.76%   |
| 5.15.78  | 11       | 2.53%   |
| 6.6.76   | 9        | 2.07%   |
| 6.12.37  | 9        | 2.07%   |
| 6.1.44   | 9        | 2.07%   |
| 5.15.131 | 9        | 2.07%   |
| 4.19.79  | 7        | 1.61%   |
| 6.1.94   | 6        | 1.38%   |
| 6.1.20   | 5        | 1.15%   |
| 5.15.167 | 5        | 1.15%   |
| 6.1.148  | 4        | 0.92%   |
| 6.12.56  | 3        | 0.69%   |
| 6.1.38   | 3        | 0.69%   |
| 6.1.143  | 3        | 0.69%   |
| 5.15.125 | 3        | 0.69%   |
| 6.6.34   | 2        | 0.46%   |
| 6.6.26   | 2        | 0.46%   |
| 5.10.24  | 2        | 0.46%   |
| 6.1.158  | 1        | 0.23%   |
| 6.1.11   | 1        | 0.23%   |
| 5.10.1   | 1        | 0.23%   |
| 4.19.56  | 1        | 0.23%   |
| 4.19.204 | 1        | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.1     | 133      | 31.82%  |
| 5.15    | 133      | 31.82%  |
| 6.6     | 47       | 11.24%  |
| 5.10    | 39       | 9.33%   |
| 6.12    | 32       | 7.66%   |
| 5.14    | 25       | 5.98%   |
| 4.19    | 9        | 2.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 400      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| MATE       | 316      | 77.07%  |
| Cinnamon   | 37       | 9.02%   |
| KDE5       | 33       | 8.05%   |
| X-Cinnamon | 10       | 2.44%   |
| GNOME      | 7        | 1.71%   |
| Unknown    | 6        | 1.46%   |
| i3         | 1        | 0.24%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 326      | 80.3%   |
| Tty     | 61       | 15.02%  |
| Wayland | 17       | 4.19%   |
| Unknown | 2        | 0.49%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM     | 345      | 85.19%  |
| SDDM    | 36       | 8.89%   |
| LightDM | 12       | 2.96%   |
| Unknown | 12       | 2.96%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| ru_RU   | 304      | 74.69%  |
| Unknown | 95       | 23.34%  |
| en_US   | 7        | 1.72%   |
| pl_PL   | 1        | 0.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 273      | 67.08%  |
| BIOS | 134      | 32.92%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 392      | 97.51%  |
| Btrfs   | 8        | 1.99%   |
| Xfs     | 1        | 0.25%   |
| Unknown | 1        | 0.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 285      | 70.54%  |
| MBR     | 110      | 27.23%  |
| Unknown | 9        | 2.23%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 379      | 93.12%  |
| Yes       | 28       | 6.88%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 328      | 81.59%  |
| Yes       | 74       | 18.41%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 93       | 23.25%  |
| ASUSTek Computer    | 90       | 22.5%   |
| MSI                 | 45       | 11.25%  |
| ASRock              | 38       | 9.5%    |
| Hewlett-Packard     | 19       | 4.75%   |
| Unknown             | 15       | 3.75%   |
| Lenovo              | 12       | 3%      |
| Aquarius            | 12       | 3%      |
| Intel               | 11       | 2.75%   |
| DEPO Computers      | 10       | 2.5%    |
| Dell                | 7        | 1.75%   |
| ICL                 | 5        | 1.25%   |
| Graviton            | 5        | 1.25%   |
| Foxconn             | 4        | 1%      |
| BESHTAU             | 4        | 1%      |
| ECS                 | 3        | 0.75%   |
| Biostar             | 3        | 0.75%   |
| MTR                 | 2        | 0.5%    |
| INTECH PRO          | 2        | 0.5%    |
| INFERIT             | 2        | 0.5%    |
| AZW                 | 2        | 0.5%    |
| Acer                | 2        | 0.5%    |
| Supermicro          | 1        | 0.25%   |
| RDW                 | 1        | 0.25%   |
| Quanta              | 1        | 0.25%   |
| Pegatron            | 1        | 0.25%   |
| ONDA                | 1        | 0.25%   |
| LIFE TECH           | 1        | 0.25%   |
| Kraftway            | 1        | 0.25%   |
| iRU                 | 1        | 0.25%   |
| Huanan              | 1        | 0.25%   |
| HomeNET             | 1        | 0.25%   |
| DIO                 | 1        | 0.25%   |
| Compal              | 1        | 0.25%   |
| Colorful Technology | 1        | 0.25%   |
| 3Logic Group        | 1        | 0.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| Unknown                    | 15       | 3.75%   |
| ASUS P5GC-VM               | 9        | 2.25%   |
| ASUS All Series            | 9        | 2.25%   |
| MSI MS-7677                | 6        | 1.5%    |
| Gigabyte B365M DS3H        | 6        | 1.5%    |
| DEPO Computers DPH410S     | 5        | 1.25%   |
| ASUS H61M-K                | 5        | 1.25%   |
| ASRock H510M-HVS R2.0      | 5        | 1.25%   |
| ASRock B365M-ITX/ac        | 5        | 1.25%   |
| ICL RAY B102               | 4        | 1%      |
| Gigabyte H510M H           | 4        | 1%      |
| DEPO Computers DPH310T     | 4        | 1%      |
| ASUS PRIME H510T2/CSM      | 4        | 1%      |
| ASRock H61M-DGS            | 4        | 1%      |
| MSI MS-7E05                | 3        | 0.75%   |
| MSI MS-7D48                | 3        | 0.75%   |
| MSI MS-7D14                | 3        | 0.75%   |
| MSI MS-7C51                | 3        | 0.75%   |
| Intel DH61BF AAG81311-101  | 3        | 0.75%   |
| Intel D945GNT AAC96315-405 | 3        | 0.75%   |
| Gigabyte H110M-S2          | 3        | 0.75%   |
| Gigabyte B760M DS3H DDR4   | 3        | 0.75%   |
| Gigabyte B75M-D3V          | 3        | 0.75%   |
| Gigabyte A320M-S2H         | 3        | 0.75%   |
| Biostar H610MH             | 3        | 0.75%   |
| ASUS PRIME H310M-R R2.0    | 3        | 0.75%   |
| ASUS P5GC-MX/1333          | 3        | 0.75%   |
| ASRock H610M-HVS           | 3        | 0.75%   |
| Aquarius P30 K44 R53       | 3        | 0.75%   |
| MSI MS-7D22                | 2        | 0.5%    |
| MSI MS-7C96                | 2        | 0.5%    |
| MSI MS-7592                | 2        | 0.5%    |
| MSI MS-7529                | 2        | 0.5%    |
| Intel DH61CR AAG14064-203  | 2        | 0.5%    |
| HP ProOne 400 G1 AiO       | 2        | 0.5%    |
| HP ProDesk 400 G6 MT       | 2        | 0.5%    |
| Graviton D15i              | 2        | 0.5%    |
| Gigabyte H81M-S2VP         | 2        | 0.5%    |
| Gigabyte H510M S2H V2      | 2        | 0.5%    |
| Gigabyte H410M S2H V2      | 2        | 0.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 29       | 7.25%   |
| Unknown                | 15       | 3.75%   |
| Gigabyte B365M         | 10       | 2.5%    |
| ASUS P5GC-VM           | 9        | 2.25%   |
| ASUS All               | 9        | 2.25%   |
| Gigabyte H510M         | 7        | 1.75%   |
| Dell OptiPlex          | 7        | 1.75%   |
| MSI MS-7677            | 6        | 1.5%    |
| Lenovo ThinkCentre     | 6        | 1.5%    |
| HP ProDesk             | 6        | 1.5%    |
| Gigabyte H410M         | 6        | 1.5%    |
| ICL RAY                | 5        | 1.25%   |
| Gigabyte B560M         | 5        | 1.25%   |
| DEPO Computers DPH410S | 5        | 1.25%   |
| ASUS H61M-K            | 5        | 1.25%   |
| ASRock H510M-HVS       | 5        | 1.25%   |
| ASRock B365M-ITX       | 5        | 1.25%   |
| HP Compaq              | 4        | 1%      |
| Gigabyte A520M         | 4        | 1%      |
| Gigabyte A320M-S2H     | 4        | 1%      |
| DEPO Computers DPH310T | 4        | 1%      |
| ASUS P8H61             | 4        | 1%      |
| ASRock H61M-DGS        | 4        | 1%      |
| Aquarius P30           | 4        | 1%      |
| MSI MS-7E05            | 3        | 0.75%   |
| MSI MS-7D48            | 3        | 0.75%   |
| MSI MS-7D14            | 3        | 0.75%   |
| MSI MS-7C51            | 3        | 0.75%   |
| Intel DH61CR           | 3        | 0.75%   |
| Intel DH61BF           | 3        | 0.75%   |
| Intel D945GNT          | 3        | 0.75%   |
| Gigabyte H310M         | 3        | 0.75%   |
| Gigabyte H110M-S2      | 3        | 0.75%   |
| Gigabyte B760M         | 3        | 0.75%   |
| Gigabyte B75M-D3V      | 3        | 0.75%   |
| Gigabyte B550          | 3        | 0.75%   |
| Gigabyte B450          | 3        | 0.75%   |
| Biostar H610MH         | 3        | 0.75%   |
| ASUS P5GC-MX           | 3        | 0.75%   |
| ASRock H610M-HVS       | 3        | 0.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 71       | 17.75%  |
| 2022 | 39       | 9.75%   |
| 2019 | 37       | 9.25%   |
| 2018 | 30       | 7.5%    |
| 2012 | 26       | 6.5%    |
| 2011 | 26       | 6.5%    |
| 2023 | 24       | 6%      |
| 2020 | 24       | 6%      |
| 2013 | 24       | 6%      |
| 2007 | 17       | 4.25%   |
| 2016 | 13       | 3.25%   |
| 2014 | 13       | 3.25%   |
| 2024 | 11       | 2.75%   |
| 2010 | 11       | 2.75%   |
| 2017 | 9        | 2.25%   |
| 2009 | 9        | 2.25%   |
| 2015 | 8        | 2%      |
| 2025 | 3        | 0.75%   |
| 2006 | 3        | 0.75%   |
| 2008 | 2        | 0.5%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 400      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 393      | 98.25%  |
| Enabled  | 7        | 1.75%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 400      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 134      | 33.33%  |
| 16.01-24.0  | 102      | 25.37%  |
| 3.01-4.0    | 71       | 17.66%  |
| 8.01-16.0   | 49       | 12.19%  |
| 32.01-64.0  | 15       | 3.73%   |
| 1.01-2.0    | 8        | 1.99%   |
| 24.01-32.0  | 7        | 1.74%   |
| 2.01-3.0    | 7        | 1.74%   |
| 64.01-256.0 | 7        | 1.74%   |
| 0.51-1.0    | 1        | 0.25%   |
| Unknown     | 1        | 0.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 155      | 36.21%  |
| 2.01-3.0  | 103      | 24.07%  |
| 4.01-8.0  | 60       | 14.02%  |
| 3.01-4.0  | 51       | 11.92%  |
| 0.51-1.0  | 37       | 8.64%   |
| 8.01-16.0 | 18       | 4.21%   |
| 0.01-0.5  | 3        | 0.7%    |
| Unknown   | 1        | 0.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 281      | 68.54%  |
| 2      | 93       | 22.68%  |
| 3      | 21       | 5.12%   |
| 4      | 11       | 2.68%   |
| 5      | 2        | 0.49%   |
| 8      | 1        | 0.24%   |
| 6      | 1        | 0.24%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 277      | 68.73%  |
| Yes       | 126      | 31.27%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 399      | 99.75%  |
| No        | 1        | 0.25%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 309      | 76.67%  |
| Yes       | 94       | 23.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 327      | 80.74%  |
| Yes       | 78       | 19.26%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Russia  | 397      | 99.25%  |
| Ukraine | 2        | 0.5%    |
| Poland  | 1        | 0.25%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Moscow            | 94       | 22.98%  |
| Salekhard         | 37       | 9.05%   |
| Murom             | 35       | 8.56%   |
| Novy Urengoy      | 22       | 5.38%   |
| St Petersburg     | 15       | 3.67%   |
| Perm              | 13       | 3.18%   |
| Zima              | 10       | 2.44%   |
| Yekaterinburg     | 10       | 2.44%   |
| Polazna           | 9        | 2.2%    |
| Stavropol         | 8        | 1.96%   |
| Volgograd         | 7        | 1.71%   |
| Labytnangi        | 7        | 1.71%   |
| Krasnodar         | 6        | 1.47%   |
| Barnaul           | 5        | 1.22%   |
| Vladimir          | 4        | 0.98%   |
| Kurgan            | 4        | 0.98%   |
| Zheleznodorozhnyy | 3        | 0.73%   |
| Yuzhno-Sakhalinsk | 3        | 0.73%   |
| Tver              | 3        | 0.73%   |
| Rostov-on-Don     | 3        | 0.73%   |
| Novosibirsk       | 3        | 0.73%   |
| Novorossiysk      | 3        | 0.73%   |
| Muromskiy         | 3        | 0.73%   |
| Lipetsk           | 3        | 0.73%   |
| Khabarovsk        | 3        | 0.73%   |
| Kaluga            | 3        | 0.73%   |
| Chelyabinsk       | 3        | 0.73%   |
| Bryansk           | 3        | 0.73%   |
| Balashikha        | 3        | 0.73%   |
| Zhukovskiy        | 2        | 0.49%   |
| Vladikavkaz       | 2        | 0.49%   |
| Veliky Novgorod   | 2        | 0.49%   |
| Ulyanovsk         | 2        | 0.49%   |
| Ufa               | 2        | 0.49%   |
| Tomsk             | 2        | 0.49%   |
| Surgut            | 2        | 0.49%   |
| Sevastopol        | 2        | 0.49%   |
| Pushkino          | 2        | 0.49%   |
| Penza             | 2        | 0.49%   |
| Orenburg          | 2        | 0.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Seagate                      | 95       | 133    | 17.15%  |
| WDC                          | 69       | 86     | 12.45%  |
| Toshiba                      | 56       | 79     | 10.11%  |
| Samsung Electronics          | 36       | 46     | 6.5%    |
| Kingston                     | 36       | 40     | 6.5%    |
| A-DATA Technology            | 36       | 41     | 6.5%    |
| Hitachi                      | 18       | 19     | 3.25%   |
| Apacer                       | 18       | 21     | 3.25%   |
| KingSpec                     | 14       | 15     | 2.53%   |
| Foxline                      | 12       | 12     | 2.17%   |
| ExeGate                      | 12       | 14     | 2.17%   |
| SPCC                         | 11       | 13     | 1.99%   |
| Crucial                      | 9        | 13     | 1.62%   |
| SanDisk                      | 8        | 12     | 1.44%   |
| China                        | 8        | 9      | 1.44%   |
| AGI                          | 8        | 8      | 1.44%   |
| Patriot                      | 7        | 7      | 1.26%   |
| Netac                        | 7        | 7      | 1.26%   |
| Intel                        | 7        | 7      | 1.26%   |
| Silicon Motion               | 6        | 7      | 1.08%   |
| Phison                       | 6        | 6      | 1.08%   |
| AMD                          | 5        | 5      | 0.9%    |
| Smartbuy                     | 4        | 4      | 0.72%   |
| Qumo                         | 4        | 4      | 0.72%   |
| GOODRAM                      | 4        | 4      | 0.72%   |
| HGST                         | 3        | 3      | 0.54%   |
| Hewlett-Packard              | 3        | 3      | 0.54%   |
| Shenzhen Longsys Electronics | 2        | 2      | 0.36%   |
| Plextor                      | 2        | 2      | 0.36%   |
| MSI                          | 2        | 2      | 0.36%   |
| KIOXIA-EXCERIA               | 2        | 2      | 0.36%   |
| KIOXIA                       | 2        | 2      | 0.36%   |
| Kingston Technology Company  | 2        | 3      | 0.36%   |
| HYDRA                        | 2        | 2      | 0.36%   |
| Hikvision                    | 2        | 2      | 0.36%   |
| Gigabyte Technology          | 2        | 2      | 0.36%   |
| Digma                        | 2        | 2      | 0.36%   |
| BR                           | 2        | 2      | 0.36%   |
| BaseTech                     | 2        | 2      | 0.36%   |
| Unknown                      | 2        | 2      | 0.36%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Toshiba HDWD110 1TB                  | 19       | 3.26%   |
| Seagate ST500DM002-1BD142 500GB      | 15       | 2.58%   |
| Seagate ST1000DM010-2EP102 1TB       | 14       | 2.41%   |
| Toshiba DT01ACA100 1TB               | 12       | 2.06%   |
| Kingston SA400S37240G 240GB SSD      | 11       | 1.89%   |
| A-DATA SX6000PNP 256GB               | 11       | 1.89%   |
| Kingston SA400S37480G 480GB SSD      | 8        | 1.37%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 7        | 1.2%    |
| SPCC Solid State Disk 256GB          | 7        | 1.2%    |
| Seagate ST1000DM003-1ER162 1TB       | 7        | 1.2%    |
| Toshiba HDWL110 1TB                  | 6        | 1.03%   |
| Seagate ST3160811AS 160GB            | 6        | 1.03%   |
| Apacer AS2280P4 256GB                | 6        | 1.03%   |
| Toshiba DT01ACA050 500GB             | 5        | 0.86%   |
| Seagate ST1000LM049-2GH172 1TB       | 5        | 0.86%   |
| Samsung SSD 860 EVO 250GB            | 5        | 0.86%   |
| KingSpec P3-256 256GB SSD            | 5        | 0.86%   |
| Crucial CT240BX500SSD1 240GB         | 5        | 0.86%   |
| Apacer AS340 240GB SSD               | 5        | 0.86%   |
| Seagate ST1000DM010-2DM162 1TB       | 4        | 0.69%   |
| Patriot Burst Elite 240GB SSD        | 4        | 0.69%   |
| Kingston SA400S37120G 120GB SSD      | 4        | 0.69%   |
| A-DATA SX6000PNP 512GB               | 4        | 0.69%   |
| WDC WD5000AAKX-60U6AA0 500GB         | 3        | 0.52%   |
| WDC WD2500AAJS-22VTA0 250GB          | 3        | 0.52%   |
| WDC WD10EZEX-00BBHA0 1TB             | 3        | 0.52%   |
| WDC WD Blue SA510 2.5 500GB          | 3        | 0.52%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB | 3        | 0.52%   |
| Toshiba HDWD105 500GB                | 3        | 0.52%   |
| Seagate ST3500413AS 500GB            | 3        | 0.52%   |
| Samsung SSD 980 PRO 500GB            | 3        | 0.52%   |
| Samsung SSD 970 EVO Plus 1TB         | 3        | 0.52%   |
| Samsung SSD 870 EVO 500GB            | 3        | 0.52%   |
| Samsung SSD 870 EVO 250GB            | 3        | 0.52%   |
| Hitachi HDS721616PLA380 160GB        | 3        | 0.52%   |
| Hitachi HDP725025GLA380 250GB        | 3        | 0.52%   |
| Foxline FLSSD240X5SE 240GB           | 3        | 0.52%   |
| AGI AGI512G16AI198 512GB             | 3        | 0.52%   |
| A-DATA SU650 240GB SSD               | 3        | 0.52%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 2        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 94       | 132    | 41.05%  |
| Toshiba             | 54       | 76     | 23.58%  |
| WDC                 | 50       | 62     | 21.83%  |
| Hitachi             | 18       | 19     | 7.86%   |
| Samsung Electronics | 6        | 7      | 2.62%   |
| HGST                | 3        | 3      | 1.31%   |
| USB                 | 1        | 1      | 0.44%   |
| JetFlash            | 1        | 1      | 0.44%   |
| External            | 1        | 1      | 0.44%   |
| ACASIS              | 1        | 1      | 0.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 29       | 31     | 14.43%  |
| WDC                 | 17       | 19     | 8.46%   |
| Samsung Electronics | 17       | 19     | 8.46%   |
| A-DATA Technology   | 13       | 13     | 6.47%   |
| KingSpec            | 11       | 12     | 5.47%   |
| SPCC                | 9        | 11     | 4.48%   |
| ExeGate             | 9        | 10     | 4.48%   |
| Foxline             | 8        | 8      | 3.98%   |
| China               | 8        | 9      | 3.98%   |
| Apacer              | 8        | 9      | 3.98%   |
| Crucial             | 7        | 11     | 3.48%   |
| SanDisk             | 6        | 10     | 2.99%   |
| Patriot             | 6        | 6      | 2.99%   |
| Intel               | 6        | 6      | 2.99%   |
| Smartbuy            | 4        | 4      | 1.99%   |
| Qumo                | 4        | 4      | 1.99%   |
| Netac               | 3        | 3      | 1.49%   |
| GOODRAM             | 3        | 3      | 1.49%   |
| AGI                 | 3        | 3      | 1.49%   |
| Toshiba             | 2        | 3      | 1%      |
| Plextor             | 2        | 2      | 1%      |
| KIOXIA-EXCERIA      | 2        | 2      | 1%      |
| HYDRA               | 2        | 2      | 1%      |
| Gigabyte Technology | 2        | 2      | 1%      |
| Digma               | 2        | 2      | 1%      |
| Verbatim            | 1        | 1      | 0.5%    |
| Transcend           | 1        | 1      | 0.5%    |
| TESLA               | 1        | 2      | 0.5%    |
| Seagate             | 1        | 1      | 0.5%    |
| OSCOO               | 1        | 1      | 0.5%    |
| Micron Technology   | 1        | 1      | 0.5%    |
| KingFast            | 1        | 1      | 0.5%    |
| HS-SSD-E100         | 1        | 1      | 0.5%    |
| Hewlett-Packard     | 1        | 1      | 0.5%    |
| GeIL                | 1        | 2      | 0.5%    |
| G537N               | 1        | 1      | 0.5%    |
| DEXP                | 1        | 1      | 0.5%    |
| Dahua               | 1        | 1      | 0.5%    |
| Colorful            | 1        | 1      | 0.5%    |
| BESHTAU             | 1        | 1      | 0.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 207      | 303    | 40.19%  |
| SSD  | 186      | 224    | 36.12%  |
| NVMe | 121      | 147    | 23.5%   |
| MMC  | 1        | 1      | 0.19%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 321      | 514    | 70.86%  |
| NVMe | 121      | 147    | 26.71%  |
| SAS  | 10       | 13     | 2.21%   |
| MMC  | 1        | 1      | 0.22%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 239      | 311    | 61.92%  |
| 0.51-1.0   | 126      | 186    | 32.64%  |
| 1.01-2.0   | 11       | 16     | 2.85%   |
| 3.01-4.0   | 6        | 8      | 1.55%   |
| 2.01-3.0   | 2        | 2      | 0.52%   |
| 4.01-10.0  | 2        | 4      | 0.52%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 149      | 35.9%   |
| 251-500        | 118      | 28.43%  |
| 501-1000       | 77       | 18.55%  |
| 1001-2000      | 35       | 8.43%   |
| 51-100         | 16       | 3.86%   |
| 2001-3000      | 8        | 1.93%   |
| More than 3000 | 6        | 1.45%   |
| 21-50          | 3        | 0.72%   |
| Unknown        | 3        | 0.72%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 167      | 39.39%  |
| 21-50          | 126      | 29.72%  |
| 101-250        | 43       | 10.14%  |
| 51-100         | 35       | 8.25%   |
| 251-500        | 26       | 6.13%   |
| 501-1000       | 14       | 3.3%    |
| 1001-2000      | 5        | 1.18%   |
| 2001-3000      | 3        | 0.71%   |
| Unknown        | 3        | 0.71%   |
| More than 3000 | 2        | 0.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB  | 9        | 10     | 12.16%  |
| WDC WDS240G2G0A-00JH30 240GB SSD | 3        | 3      | 4.05%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 2        | 2      | 2.7%    |
| Toshiba MK2565GSX 250GB          | 2        | 2      | 2.7%    |
| Seagate ST3500413AS 500GB        | 2        | 2      | 2.7%    |
| Seagate ST3160811AS 160GB        | 2        | 2      | 2.7%    |
| Seagate ST1000DM010-2EP102 1TB   | 2        | 6      | 2.7%    |
| Hitachi HDS723015BLA642 1TB      | 2        | 2      | 2.7%    |
| Hitachi HDS721616PLA380 160GB    | 2        | 2      | 2.7%    |
| Hitachi HDP725025GLA380 250GB    | 2        | 2      | 2.7%    |
| WDC WDS120G2G0A-00JH30 120GB SSD | 1        | 1      | 1.35%   |
| WDC WD7500BPVT-00HXZT3 752GB     | 1        | 1      | 1.35%   |
| WDC WD5000AAVS-00ZTB0 500GB      | 1        | 1      | 1.35%   |
| WDC WD5000AAKS-00V1A0 500GB      | 1        | 2      | 1.35%   |
| WDC WD5000AAKS-00D2B0 500GB      | 1        | 1      | 1.35%   |
| WDC WD3201ABYS-01B9A0 320GB      | 1        | 1      | 1.35%   |
| WDC WD3200AAKX-001CA0 320GB      | 1        | 1      | 1.35%   |
| WDC WD2500AAJS-22VTA0 250GB      | 1        | 1      | 1.35%   |
| WDC WD1600AAJS-00B4A0 160GB      | 1        | 1      | 1.35%   |
| WDC WD10EZEX-75ZF5A0 1TB         | 1        | 2      | 1.35%   |
| WDC WD10EZEX-00WN4A0 1TB         | 1        | 1      | 1.35%   |
| WDC WD10EZEX-00BN5A0 1TB         | 1        | 1      | 1.35%   |
| WDC WD10EARS-00Y5B1 1TB          | 1        | 1      | 1.35%   |
| WDC WD10EALX-009BA0 1TB          | 1        | 1      | 1.35%   |
| WDC WD1003FBYX-01Y7B0 1TB        | 1        | 1      | 1.35%   |
| WDC WD1001FALS-00J7B1 1TB        | 1        | 1      | 1.35%   |
| WDC WD Blue SA510 2.5 500GB      | 1        | 1      | 1.35%   |
| Transcend TS256GSSD230S 256GB    | 1        | 1      | 1.35%   |
| Toshiba MK6475GSX 640GB          | 1        | 1      | 1.35%   |
| Toshiba HDWD110 1TB              | 1        | 2      | 1.35%   |
| SPCC M.2 PCIe SSD 512GB          | 1        | 1      | 1.35%   |
| Seagate ST9500423AS 500GB        | 1        | 1      | 1.35%   |
| Seagate ST500LM021-1KJ152 500GB  | 1        | 1      | 1.35%   |
| Seagate ST500DM005 HD502HJ 500GB | 1        | 1      | 1.35%   |
| Seagate ST380817AS 80GB          | 1        | 1      | 1.35%   |
| Seagate ST3250823AS 250GB        | 1        | 1      | 1.35%   |
| Seagate ST3250318AS 250GB        | 1        | 2      | 1.35%   |
| Seagate ST3120026A 120GB         | 1        | 1      | 1.35%   |
| Seagate ST31000524NS 1TB         | 1        | 1      | 1.35%   |
| Seagate ST31000524AS 1TB         | 1        | 1      | 1.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 26       | 32     | 35.14%  |
| WDC                 | 22       | 24     | 29.73%  |
| Hitachi             | 11       | 11     | 14.86%  |
| Toshiba             | 4        | 5      | 5.41%   |
| Samsung Electronics | 4        | 4      | 5.41%   |
| Transcend           | 1        | 1      | 1.35%   |
| SPCC                | 1        | 1      | 1.35%   |
| Kingston            | 1        | 1      | 1.35%   |
| Hikvision           | 1        | 1      | 1.35%   |
| HGST                | 1        | 1      | 1.35%   |
| ExeGate             | 1        | 1      | 1.35%   |
| A-DATA Technology   | 1        | 1      | 1.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 26       | 32     | 41.94%  |
| WDC                 | 17       | 19     | 27.42%  |
| Hitachi             | 11       | 11     | 17.74%  |
| Toshiba             | 4        | 5      | 6.45%   |
| Samsung Electronics | 3        | 3      | 4.84%   |
| HGST                | 1        | 1      | 1.61%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 58       | 71     | 82.86%  |
| SSD  | 8        | 8      | 11.43%  |
| NVMe | 4        | 4      | 5.71%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST31000528AS 1TB          | 1        | 1      | 33.33%  |
| Seagate ST250LT012-9WS141 250GB   | 1        | 2      | 33.33%  |
| A-DATA Technology SX6000PNP 512GB | 1        | 3      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| Seagate           | 2        | 3      | 66.67%  |
| A-DATA Technology | 1        | 3      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 345      | 545    | 79.13%  |
| Malfunc  | 70       | 83     | 16.06%  |
| Detected | 18       | 41     | 4.13%   |
| Failed   | 3        | 6      | 0.69%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 337      | 62.18%  |
| AMD                              | 55       | 10.15%  |
| Phison Electronics               | 24       | 4.43%   |
| Silicon Motion                   | 21       | 3.87%   |
| Realtek Semiconductor            | 17       | 3.14%   |
| Samsung Electronics              | 16       | 2.95%   |
| ADATA Technology                 | 13       | 2.4%    |
| Kingston Technology Company      | 9        | 1.66%   |
| MAXIO Technology (Hangzhou)      | 8        | 1.48%   |
| Sandisk                          | 6        | 1.11%   |
| Nvidia                           | 5        | 0.92%   |
| JMicron Technology               | 5        | 0.92%   |
| ASMedia Technology               | 4        | 0.74%   |
| Shenzhen Longsys Electronics     | 3        | 0.55%   |
| Netac Technology                 | 3        | 0.55%   |
| Marvell Technology Group         | 3        | 0.55%   |
| VIA Technologies                 | 2        | 0.37%   |
| Micron/Crucial Technology        | 2        | 0.37%   |
| YEESTOR Microelectronics         | 1        | 0.18%   |
| Toshiba America Info Systems     | 1        | 0.18%   |
| SK hynix                         | 1        | 0.18%   |
| Silicon Integrated Systems [SiS] | 1        | 0.18%   |
| ShenZhen TIGO Semiconductor      | 1        | 0.18%   |
| LSI Logic / Symbios Logic        | 1        | 0.18%   |
| KIOXIA                           | 1        | 0.18%   |
| Integrated Technology Express    | 1        | 0.18%   |
| INNOGRIT                         | 1        | 0.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 57       | 8.98%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 36       | 5.67%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 34       | 5.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 30       | 4.72%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 27       | 4.25%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 26       | 4.09%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 24       | 3.78%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 23       | 3.62%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 20       | 3.15%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 20       | 3.15%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 18       | 2.83%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 18       | 2.83%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 16       | 2.52%   |
| AMD 500 Series Chipset SATA Controller                                                  | 16       | 2.52%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 12       | 1.89%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 12       | 1.89%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 12       | 1.89%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                       | 11       | 1.73%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 10       | 1.57%   |
| Intel SATA Controller [RAID mode]                                                       | 9        | 1.42%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 9        | 1.42%   |
| AMD 400 Series Chipset SATA Controller                                                  | 9        | 1.42%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 7        | 1.1%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 7        | 1.1%    |
| ADATA XPG GAMMIXS1 1L, XPG GAMMIX S5, LEGEND 710 / 740, SWORDFISH NVMe SSD (DRAM-less)  | 6        | 0.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5        | 0.79%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 5        | 0.79%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 5        | 0.79%   |
| AMD 300 Series Chipset SATA Controller                                                  | 5        | 0.79%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 4        | 0.63%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                                       | 4        | 0.63%   |
| Nvidia MCP61 SATA Controller                                                            | 4        | 0.63%   |
| Nvidia MCP61 IDE                                                                        | 4        | 0.63%   |
| JMicron JMB368 IDE controller                                                           | 4        | 0.63%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 4        | 0.63%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                                   | 3        | 0.47%   |
| Phison PS5015-E15 PCIe3 NVMe Controller (DRAM-less)                                     | 3        | 0.47%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1602 (DRAM-less)                                | 3        | 0.47%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3        | 0.47%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 3        | 0.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 335      | 62.27%  |
| NVMe | 121      | 22.49%  |
| IDE  | 63       | 11.71%  |
| RAID | 18       | 3.35%   |
| SCSI | 1        | 0.19%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 340      | 85%     |
| AMD    | 60       | 15%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-10400 CPU @ 2.90GHz           | 24       | 5.99%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 23       | 5.74%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 20       | 4.99%   |
| Intel 12th Gen Core i5-12400                | 15       | 3.74%   |
| Intel 12th Gen Core i3-12100                | 14       | 3.49%   |
| Intel Core i3-10105 CPU @ 3.70GHz           | 10       | 2.49%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 8        | 2%      |
| Intel Core i5-3470 CPU @ 3.20GHz            | 8        | 2%      |
| Intel Core i3-2120 CPU @ 3.30GHz            | 6        | 1.5%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 6        | 1.5%    |
| Intel Core i3-8100 CPU @ 3.60GHz            | 5        | 1.25%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 5        | 1.25%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 5        | 1.25%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 4        | 1%      |
| Intel Core i7-2600 CPU @ 3.40GHz            | 4        | 1%      |
| Intel Core i5-8400 CPU @ 2.80GHz            | 4        | 1%      |
| Intel Core i5-6500 CPU @ 3.20GHz            | 4        | 1%      |
| Intel Core i5-2400 CPU @ 3.10GHz            | 4        | 1%      |
| Intel Core i5-10500 CPU @ 3.10GHz           | 4        | 1%      |
| Intel 11th Gen Core i7-11700 @ 2.50GHz      | 4        | 1%      |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 4        | 1%      |
| AMD Ryzen 5 PRO 4650G with Radeon Graphics  | 4        | 1%      |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 3        | 0.75%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 3        | 0.75%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 3        | 0.75%   |
| Intel Pentium CPU G4500 @ 3.50GHz           | 3        | 0.75%   |
| Intel Pentium 4 CPU 3.06GHz                 | 3        | 0.75%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 0.75%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 3        | 0.75%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 3        | 0.75%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3        | 0.75%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3        | 0.75%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 3        | 0.75%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 3        | 0.75%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 3        | 0.75%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 3        | 0.75%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 3        | 0.75%   |
| Intel 12th Gen Core i5-12500                | 3        | 0.75%   |
| Intel 12th Gen Core i5-12400F               | 3        | 0.75%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 3        | 0.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 112      | 27.93%  |
| Intel Core i3           | 68       | 16.96%  |
| Other                   | 55       | 13.72%  |
| Intel Core i7           | 22       | 5.49%   |
| AMD Ryzen 5             | 19       | 4.74%   |
| Intel Pentium           | 17       | 4.24%   |
| Intel Pentium Gold      | 16       | 3.99%   |
| Intel Celeron           | 13       | 3.24%   |
| Intel Core 2 Duo        | 12       | 2.99%   |
| AMD Ryzen 3             | 8        | 2%      |
| AMD Ryzen 7             | 7        | 1.75%   |
| Intel Xeon              | 6        | 1.5%    |
| Intel Pentium Dual      | 6        | 1.5%    |
| Intel Pentium Dual-Core | 5        | 1.25%   |
| AMD Ryzen 5 PRO         | 5        | 1.25%   |
| AMD A6                  | 5        | 1.25%   |
| AMD Ryzen 9             | 4        | 1%      |
| Intel Pentium 4         | 3        | 0.75%   |
| Intel Core 2 Quad       | 3        | 0.75%   |
| AMD FX                  | 3        | 0.75%   |
| AMD Athlon II X2        | 3        | 0.75%   |
| AMD Ryzen 7 PRO         | 2        | 0.5%    |
| AMD Athlon              | 2        | 0.5%    |
| Intel Genuine           | 1        | 0.25%   |
| Intel Core 2            | 1        | 0.25%   |
| Intel Core              | 1        | 0.25%   |
| AMD Phenom              | 1        | 0.25%   |
| AMD Athlon II X4        | 1        | 0.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 155      | 38.65%  |
| 6      | 109      | 27.18%  |
| 2      | 94       | 23.44%  |
| 8      | 22       | 5.49%   |
| 1      | 9        | 2.24%   |
| 12     | 5        | 1.25%   |
| 20     | 2        | 0.5%    |
| 16     | 2        | 0.5%    |
| 14     | 1        | 0.25%   |
| 10     | 1        | 0.25%   |
| 3      | 1        | 0.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 398      | 99.5%   |
| 2      | 2        | 0.5%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 237      | 59.25%  |
| 1      | 163      | 40.75%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 399      | 99.75%  |
| Unknown        | 1        | 0.25%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 75       | 18.47%  |
| 0xa0653    | 61       | 15.02%  |
| 0x306a9    | 27       | 6.65%   |
| 0x906ea    | 26       | 6.4%    |
| 0x90675    | 24       | 5.91%   |
| 0x306c3    | 21       | 5.17%   |
| 0x206a7    | 20       | 4.93%   |
| 0x1067a    | 14       | 3.45%   |
| 0x906ed    | 13       | 3.2%    |
| 0x506e3    | 10       | 2.46%   |
| 0xa0671    | 9        | 2.22%   |
| 0x906eb    | 8        | 1.97%   |
| 0x6fd      | 8        | 1.97%   |
| 0x906e9    | 7        | 1.72%   |
| 0x08600106 | 6        | 1.48%   |
| 0xa0655    | 5        | 1.23%   |
| 0x08108109 | 5        | 1.23%   |
| 0x0a50000d | 4        | 0.99%   |
| 0x0a50000c | 4        | 0.99%   |
| 0x08101016 | 4        | 0.99%   |
| 0xf49      | 3        | 0.74%   |
| 0x706a8    | 3        | 0.74%   |
| 0x106e5    | 3        | 0.74%   |
| 0x0810100b | 3        | 0.74%   |
| 0xb06f5    | 2        | 0.49%   |
| 0x90672    | 2        | 0.49%   |
| 0x6fb      | 2        | 0.49%   |
| 0x08701021 | 2        | 0.49%   |
| 0x08701013 | 2        | 0.49%   |
| 0x08001138 | 2        | 0.49%   |
| 0x06006118 | 2        | 0.49%   |
| 0x06001119 | 2        | 0.49%   |
| 0x0600063e | 2        | 0.49%   |
| 0x010000c8 | 2        | 0.49%   |
| 0xb06f2    | 1        | 0.25%   |
| 0xa0654    | 1        | 0.25%   |
| 0xa0652    | 1        | 0.25%   |
| 0x6f6      | 1        | 0.25%   |
| 0x406c3    | 1        | 0.25%   |
| 0x306f2    | 1        | 0.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| CometLake        | 74       | 18.5%   |
| KabyLake         | 65       | 16.25%  |
| Alderlake Hybrid | 41       | 10.25%  |
| IvyBridge        | 33       | 8.25%   |
| Haswell          | 27       | 6.75%   |
| SandyBridge      | 25       | 6.25%   |
| Penryn           | 16       | 4%      |
| Zen 3            | 15       | 3.75%   |
| Skylake          | 14       | 3.5%    |
| Core             | 13       | 3.25%   |
| Zen 2            | 11       | 2.75%   |
| Zen+             | 9        | 2.25%   |
| Zen              | 9        | 2.25%   |
| Unknown          | 9        | 2.25%   |
| Icelake          | 8        | 2%      |
| K10              | 5        | 1.25%   |
| Nehalem          | 4        | 1%      |
| Westmere         | 3        | 0.75%   |
| Piledriver       | 3        | 0.75%   |
| NetBurst         | 3        | 0.75%   |
| Goldmont plus    | 3        | 0.75%   |
| Excavator        | 2        | 0.5%    |
| Bulldozer        | 2        | 0.5%    |
| Silvermont       | 1        | 0.25%   |
| Lunarlake Hybrid | 1        | 0.25%   |
| K10 Llano        | 1        | 0.25%   |
| Gracemont        | 1        | 0.25%   |
| Goldmont         | 1        | 0.25%   |
| Broadwell        | 1        | 0.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 279      | 67.23%  |
| Nvidia                           | 68       | 16.39%  |
| AMD                              | 64       | 15.42%  |
| ATI Technologies                 | 2        | 0.48%   |
| Silicon Integrated Systems [SiS] | 1        | 0.24%   |
| ASPEED Technology                | 1        | 0.24%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 64       | 15.38%  |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 34       | 8.17%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 30       | 7.21%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 22       | 5.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 19       | 4.57%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 17       | 4.09%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 15       | 3.61%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 12       | 2.88%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                       | 10       | 2.4%    |
| Nvidia GT218 [GeForce 210]                                                  | 9        | 2.16%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 9        | 2.16%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 8        | 1.92%   |
| Nvidia GK208B [GeForce GT 710]                                              | 7        | 1.68%   |
| Intel Alder Lake-S GT1 [UHD Graphics 770]                                   | 7        | 1.68%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 7        | 1.68%   |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                     | 6        | 1.44%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 6        | 1.44%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 6        | 1.44%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 4        | 0.96%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 4        | 0.96%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 4        | 0.96%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 3        | 0.72%   |
| Intel CometLake-S GT1 [UHD Graphics 610]                                    | 3        | 0.72%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 3        | 0.72%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                          | 3        | 0.72%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                       | 2        | 0.48%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 2        | 0.48%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 0.48%   |
| Nvidia GK107GL [Quadro K420]                                                | 2        | 0.48%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 2        | 0.48%   |
| Nvidia GK104 [GeForce GTX 670]                                              | 2        | 0.48%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 0.48%   |
| Nvidia GF108GL [Quadro 600]                                                 | 2        | 0.48%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 2        | 0.48%   |
| Intel Alder Lake-N [UHD Graphics]                                           | 2        | 0.48%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 0.48%   |
| ATI Technologies Wani [Radeon R5/R6/R7 Graphics]                            | 2        | 0.48%   |
| AMD RS880 [Radeon HD 4250]                                                  | 2        | 0.48%   |
| AMD Park [Mobility Radeon HD 5430]                                          | 2        | 0.48%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 0.48%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 266      | 66.33%  |
| 1 x AMD        | 63       | 15.71%  |
| 1 x Nvidia     | 61       | 15.21%  |
| Intel + Nvidia | 6        | 1.5%    |
| 2 x AMD        | 1        | 0.25%   |
| 1 x SiS        | 1        | 0.25%   |
| Intel + AMD    | 1        | 0.25%   |
| 1 x ASPEED     | 1        | 0.25%   |
| AMD + Nvidia   | 1        | 0.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 338      | 83.87%  |
| Unknown     | 44       | 10.92%  |
| Proprietary | 21       | 5.21%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 294      | 73.32%  |
| 0.01-0.5   | 32       | 7.98%   |
| 0.51-1.0   | 30       | 7.48%   |
| 1.01-2.0   | 29       | 7.23%   |
| 7.01-8.0   | 6        | 1.5%    |
| 3.01-4.0   | 6        | 1.5%    |
| 8.01-16.0  | 2        | 0.5%    |
| 5.01-6.0   | 1        | 0.25%   |
| 2.01-3.0   | 1        | 0.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Philips              | 60       | 15.67%  |
| Samsung Electronics  | 58       | 15.14%  |
| Acer                 | 29       | 7.57%   |
| AOC                  | 27       | 7.05%   |
| ViewSonic            | 24       | 6.27%   |
| Goldstar             | 24       | 6.27%   |
| Dell                 | 21       | 5.48%   |
| Hewlett-Packard      | 20       | 5.22%   |
| BenQ                 | 18       | 4.7%    |
| SGT                  | 11       | 2.87%   |
| ASUSTek Computer     | 9        | 2.35%   |
| RTK                  | 7        | 1.83%   |
| NEC Computers        | 5        | 1.31%   |
| Lenovo               | 5        | 1.31%   |
| Ancor Communications | 5        | 1.31%   |
| VIE                  | 4        | 1.04%   |
| Daewoo               | 4        | 1.04%   |
| Sony                 | 3        | 0.78%   |
| OOO                  | 3        | 0.78%   |
| Iiyama               | 3        | 0.78%   |
| CHD                  | 3        | 0.78%   |
| BOE                  | 3        | 0.78%   |
| XYM                  | 2        | 0.52%   |
| VSD                  | 2        | 0.52%   |
| TR_                  | 2        | 0.52%   |
| SKM                  | 2        | 0.52%   |
| Mi                   | 2        | 0.52%   |
| IPS                  | 2        | 0.52%   |
| HUAWEI               | 2        | 0.52%   |
| CHR                  | 2        | 0.52%   |
| XYK                  | 1        | 0.26%   |
| STD                  | 1        | 0.26%   |
| SAC                  | 1        | 0.26%   |
| Rubin                | 1        | 0.26%   |
| Packard Bell         | 1        | 0.26%   |
| MSI                  | 1        | 0.26%   |
| MHH                  | 1        | 0.26%   |
| MER                  | 1        | 0.26%   |
| MCT                  | 1        | 0.26%   |
| JRY                  | 1        | 0.26%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 28       | 6.98%   |
| Samsung Electronics SyncMaster SAM036E 1280x1024 376x301mm 19.0-inch  | 13       | 3.24%   |
| SGT XY238 SGT2386 1920x1080 530x290mm 23.8-inch                       | 9        | 2.24%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 340x270mm 17.1-inch  | 7        | 1.75%   |
| Philips 226VL PHLC081 1920x1080 480x268mm 21.6-inch                   | 7        | 1.75%   |
| ViewSonic VA2719-2K VSC6B34 2560x1440 597x336mm 27.0-inch             | 6        | 1.5%    |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 6        | 1.5%    |
| Acer SA240Y ACR057F 1920x1080 527x296mm 23.8-inch                     | 5        | 1.25%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch     | 4        | 1%      |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 4        | 1%      |
| ViewSonic VA2465 SERIES VSCB730 1920x1080 521x293mm 23.5-inch         | 3        | 0.75%   |
| ViewSonic VA2046 SERIES VSC6D2E 1600x900 432x240mm 19.5-inch          | 3        | 0.75%   |
| VIE J2475FFHD VIE1919 1920x1080 520x310mm 23.8-inch                   | 3        | 0.75%   |
| Samsung Electronics S20D300 SAM0BDB 1366x768 432x240mm 19.5-inch      | 3        | 0.75%   |
| RTK HDMI RTK2732 2560x1440 597x336mm 27.0-inch                        | 3        | 0.75%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 3        | 0.75%   |
| Philips PHL 240V5 PHLC10A 1920x1080 527x296mm 23.8-inch               | 3        | 0.75%   |
| Goldstar E2042 GSM4ED7 1600x900 443x249mm 20.0-inch                   | 3        | 0.75%   |
| Daewoo HDMI DWE2100 1280x1024 476x268mm 21.5-inch                     | 3        | 0.75%   |
| ASUSTek Computer VA24E AUS24D1 1920x1080 527x296mm 23.8-inch          | 3        | 0.75%   |
| VSD HDMI VSD2360 1920x1080 522x293mm 23.6-inch                        | 2        | 0.5%    |
| ViewSonic VA2407 Series VSC8C31 1920x1080 521x293mm 23.5-inch         | 2        | 0.5%    |
| TR_ LCD Monitor TR_5511 1920x1080 519x324mm 24.1-inch                 | 2        | 0.5%    |
| SKM T24 Air SKM9322 1920x1080 519x324mm 24.1-inch                     | 2        | 0.5%    |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 2        | 0.5%    |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch  | 2        | 0.5%    |
| Samsung Electronics SA300/SA350 SAM0794 1920x1080 521x293mm 23.5-inch | 2        | 0.5%    |
| Samsung Electronics S24B300 SAM08B4 1920x1080 521x293mm 23.5-inch     | 2        | 0.5%    |
| Samsung Electronics S24B300 SAM08B2 1920x1080 531x299mm 24.0-inch     | 2        | 0.5%    |
| Samsung Electronics S22E200 SAM0C6D 1920x1080 477x268mm 21.5-inch     | 2        | 0.5%    |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 2        | 0.5%    |
| Samsung Electronics C27R50x SAM0F9D 1920x1080 598x336mm 27.0-inch     | 2        | 0.5%    |
| RTK HDMI RTK2380 1920x1080 530x290mm 23.8-inch                        | 2        | 0.5%    |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch               | 2        | 0.5%    |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 2        | 0.5%    |
| OOO HDMI OOO2380 1920x1080 526x296mm 23.8-inch                        | 2        | 0.5%    |
| NEC Computers PA241W NEC67CE 1920x1200 518x324mm 24.1-inch            | 2        | 0.5%    |
| Iiyama PL2492H IVM612F 1920x1080 527x296mm 23.8-inch                  | 2        | 0.5%    |
| Goldstar HDR WFHD GSM5BA0 2560x1080 798x334mm 34.1-inch               | 2        | 0.5%    |
| Dell U2412M DELA079 1920x1200 518x324mm 24.1-inch                     | 2        | 0.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 217      | 61.82%  |
| 1280x1024 (SXGA)   | 49       | 13.96%  |
| 2560x1440 (QHD)    | 25       | 7.12%   |
| 1600x900 (HD+)     | 14       | 3.99%   |
| 1920x1200 (WUXGA)  | 13       | 3.7%    |
| 3840x2160 (4K)     | 9        | 2.56%   |
| 1366x768 (WXGA)    | 8        | 2.28%   |
| 2560x1080          | 3        | 0.85%   |
| 3440x1440          | 2        | 0.57%   |
| 1680x1050 (WSXGA+) | 2        | 0.57%   |
| 1600x1200          | 2        | 0.57%   |
| 1440x900 (WXGA+)   | 2        | 0.57%   |
| 3840x2560          | 1        | 0.28%   |
| 2160x1440          | 1        | 0.28%   |
| 1360x768           | 1        | 0.28%   |
| 1280x960           | 1        | 0.28%   |
| 1024x768 (XGA)     | 1        | 0.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 88       | 22.8%   |
| 23      | 84       | 21.76%  |
| 21      | 56       | 14.51%  |
| 27      | 46       | 11.92%  |
| 19      | 37       | 9.59%   |
| 17      | 20       | 5.18%   |
| 20      | 13       | 3.37%   |
| 32      | 7        | 1.81%   |
| 31      | 7        | 1.81%   |
| 18      | 6        | 1.55%   |
| 34      | 5        | 1.3%    |
| 22      | 3        | 0.78%   |
| 15      | 3        | 0.78%   |
| 28      | 2        | 0.52%   |
| 25      | 2        | 0.52%   |
| Unknown | 2        | 0.52%   |
| 63      | 1        | 0.26%   |
| 57      | 1        | 0.26%   |
| 54      | 1        | 0.26%   |
| 49      | 1        | 0.26%   |
| 46      | 1        | 0.26%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 193      | 53.91%  |
| 401-500     | 83       | 23.18%  |
| 351-400     | 33       | 9.22%   |
| 301-350     | 21       | 5.87%   |
| 701-800     | 12       | 3.35%   |
| 601-700     | 9        | 2.51%   |
| 1001-1500   | 5        | 1.4%    |
| Unknown     | 2        | 0.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 259      | 74.86%  |
| 5/4   | 49       | 14.16%  |
| 16/10 | 27       | 7.8%    |
| 21/9  | 5        | 1.45%   |
| 4/3   | 4        | 1.16%   |
| 32/9  | 1        | 0.29%   |
| 3/2   | 1        | 0.29%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 174      | 47.15%  |
| 151-200        | 70       | 18.97%  |
| 301-350        | 46       | 12.47%  |
| 251-300        | 23       | 6.23%   |
| 141-150        | 23       | 6.23%   |
| 351-500        | 21       | 5.69%   |
| More than 1000 | 3        | 0.81%   |
| 101-110        | 3        | 0.81%   |
| 131-140        | 2        | 0.54%   |
| 501-1000       | 2        | 0.54%   |
| Unknown        | 2        | 0.54%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 271      | 76.77%  |
| 101-120 | 73       | 20.68%  |
| 1-50    | 4        | 1.13%   |
| 161-240 | 2        | 0.57%   |
| Unknown | 2        | 0.57%   |
| 121-160 | 1        | 0.28%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 298      | 72.51%  |
| 2     | 56       | 13.63%  |
| 0     | 56       | 13.63%  |
| 4     | 1        | 0.24%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 298      | 62.08%  |
| Intel                                  | 109      | 22.71%  |
| Qualcomm Atheros                       | 21       | 4.38%   |
| Broadcom                               | 7        | 1.46%   |
| Nvidia                                 | 5        | 1.04%   |
| TP-Link                                | 4        | 0.83%   |
| Ralink Technology                      | 4        | 0.83%   |
| Ralink                                 | 4        | 0.83%   |
| MediaTek                               | 4        | 0.83%   |
| Mercucys                               | 3        | 0.63%   |
| D-Link                                 | 3        | 0.63%   |
| Xiaomi                                 | 2        | 0.42%   |
| Samsung Electronics                    | 2        | 0.42%   |
| VIA Technologies                       | 1        | 0.21%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.21%   |
| Silicon Integrated Systems [SiS]       | 1        | 0.21%   |
| Qualcomm Atheros Communications        | 1        | 0.21%   |
| Qualcomm                               | 1        | 0.21%   |
| OPPO Electronics                       | 1        | 0.21%   |
| Metrologic Instruments                 | 1        | 0.21%   |
| Marvell Technology Group               | 1        | 0.21%   |
| Linksys                                | 1        | 0.21%   |
| Huawei Technologies                    | 1        | 0.21%   |
| Google                                 | 1        | 0.21%   |
| Edimax Technology                      | 1        | 0.21%   |
| ASIX Electronics                       | 1        | 0.21%   |
| 802.11g Adapter [Linksys WUSB54GC v3]  | 1        | 0.21%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 259      | 48.41%  |
| Realtek RTL8125 2.5GbE Controller                                      | 22       | 4.11%   |
| Intel Ethernet Connection (2) I219-V                                   | 14       | 2.62%   |
| Intel Ethernet Connection (14) I219-V                                  | 12       | 2.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 11       | 2.06%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 10       | 1.87%   |
| Intel Ethernet Controller I225-V                                       | 10       | 1.87%   |
| Intel Ethernet Connection (17) I219-V                                  | 7        | 1.31%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 7        | 1.31%   |
| Intel Wi-Fi 6 AX200                                                    | 6        | 1.12%   |
| Intel Ethernet Connection (17) I219-LM                                 | 6        | 1.12%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 5        | 0.93%   |
| Realtek 802.11ac NIC                                                   | 5        | 0.93%   |
| Intel Wireless 3165                                                    | 5        | 0.93%   |
| Intel Ethernet Connection (7) I219-V                                   | 5        | 0.93%   |
| Intel Ethernet Connection (12) I219-V                                  | 5        | 0.93%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 5        | 0.93%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4        | 0.75%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 4        | 0.75%   |
| Ralink MT7601U Wireless Adapter                                        | 4        | 0.75%   |
| Nvidia MCP61 Ethernet                                                  | 4        | 0.75%   |
| Intel Wireless 7265                                                    | 4        | 0.75%   |
| Intel NM10/ICH7 Family LAN Controller                                  | 4        | 0.75%   |
| Intel I211 Gigabit Network Connection                                  | 4        | 0.75%   |
| Intel 82579V Gigabit Network Connection                                | 4        | 0.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4        | 0.75%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 3        | 0.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3        | 0.56%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                             | 3        | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3        | 0.56%   |
| Mercucys 802.11n NIC                                                   | 3        | 0.56%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 3        | 0.56%   |
| Intel I210 Gigabit Network Connection                                  | 3        | 0.56%   |
| Intel Ethernet Connection I217-LM                                      | 3        | 0.56%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2        | 0.37%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 2        | 0.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 2        | 0.37%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 2        | 0.37%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 2        | 0.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 2        | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 36       | 36.36%  |
| Intel                                 | 35       | 35.35%  |
| Broadcom                              | 5        | 5.05%   |
| Ralink Technology                     | 4        | 4.04%   |
| Ralink                                | 4        | 4.04%   |
| TP-Link                               | 3        | 3.03%   |
| Mercucys                              | 3        | 3.03%   |
| D-Link                                | 3        | 3.03%   |
| Qualcomm Atheros Communications       | 1        | 1.01%   |
| Qualcomm Atheros                      | 1        | 1.01%   |
| MediaTek                              | 1        | 1.01%   |
| Linksys                               | 1        | 1.01%   |
| Edimax Technology                     | 1        | 1.01%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 1.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 11       | 11.11%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 7        | 7.07%   |
| Intel Wi-Fi 6 AX200                                             | 6        | 6.06%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 5        | 5.05%   |
| Realtek 802.11ac NIC                                            | 5        | 5.05%   |
| Intel Wireless 3165                                             | 5        | 5.05%   |
| Ralink MT7601U Wireless Adapter                                 | 4        | 4.04%   |
| Intel Wireless 7265                                             | 4        | 4.04%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                          | 3        | 3.03%   |
| Mercucys 802.11n NIC                                            | 3        | 3.03%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]       | 3        | 3.03%   |
| Intel Alder Lake-S PCH CNVi WiFi                                | 3        | 3.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter        | 2        | 2.02%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                 | 2        | 2.02%   |
| Realtek RTL8188EE Wireless Network Adapter                      | 2        | 2.02%   |
| Intel Wireless 7260                                             | 2        | 2.02%   |
| Intel Tiger Lake PCH CNVi WiFi                                  | 2        | 2.02%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter    | 2        | 2.02%   |
| Broadcom BCM43228 802.11a/b/g/n                                 | 2        | 2.02%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                     | 1        | 1.01%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                             | 1        | 1.01%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]      | 1        | 1.01%   |
| Realtek RTL88x2bu [AC1200 Techkey]                              | 1        | 1.01%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller     | 1        | 1.01%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter        | 1        | 1.01%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                      | 1        | 1.01%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                 | 1        | 1.01%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)       | 1        | 1.01%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                       | 1        | 1.01%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                       | 1        | 1.01%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                       | 1        | 1.01%   |
| Ralink RT2561/RT61 802.11g PCI                                  | 1        | 1.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter      | 1        | 1.01%   |
| Qualcomm Atheros AR9271 802.11n                                 | 1        | 1.01%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                         | 1        | 1.01%   |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                       | 1        | 1.01%   |
| Intel Wireless 8265 / 8275                                      | 1        | 1.01%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                 | 1        | 1.01%   |
| Intel 700 Series Chipset CNVi WiFi                              | 1        | 1.01%   |
| Edimax EW-7822ULC 802.11ac Wireless Adapter [Realtek RTL8812AU] | 1        | 1.01%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 287      | 68.17%  |
| Intel                                  | 90       | 21.38%  |
| Qualcomm Atheros                       | 20       | 4.75%   |
| Nvidia                                 | 5        | 1.19%   |
| MediaTek                               | 3        | 0.71%   |
| Xiaomi                                 | 2        | 0.48%   |
| Samsung Electronics                    | 2        | 0.48%   |
| Broadcom                               | 2        | 0.48%   |
| VIA Technologies                       | 1        | 0.24%   |
| TP-Link                                | 1        | 0.24%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.24%   |
| Silicon Integrated Systems [SiS]       | 1        | 0.24%   |
| Qualcomm                               | 1        | 0.24%   |
| OPPO Electronics                       | 1        | 0.24%   |
| Marvell Technology Group               | 1        | 0.24%   |
| Huawei Technologies                    | 1        | 0.24%   |
| Google                                 | 1        | 0.24%   |
| ASIX Electronics                       | 1        | 0.24%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 259      | 59.54%  |
| Realtek RTL8125 2.5GbE Controller                                      | 22       | 5.06%   |
| Intel Ethernet Connection (2) I219-V                                   | 14       | 3.22%   |
| Intel Ethernet Connection (14) I219-V                                  | 12       | 2.76%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 10       | 2.3%    |
| Intel Ethernet Controller I225-V                                       | 10       | 2.3%    |
| Intel Ethernet Connection (17) I219-V                                  | 7        | 1.61%   |
| Intel Ethernet Connection (17) I219-LM                                 | 6        | 1.38%   |
| Intel Ethernet Connection (7) I219-V                                   | 5        | 1.15%   |
| Intel Ethernet Connection (12) I219-V                                  | 5        | 1.15%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4        | 0.92%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 4        | 0.92%   |
| Nvidia MCP61 Ethernet                                                  | 4        | 0.92%   |
| Intel NM10/ICH7 Family LAN Controller                                  | 4        | 0.92%   |
| Intel I211 Gigabit Network Connection                                  | 4        | 0.92%   |
| Intel 82579V Gigabit Network Connection                                | 4        | 0.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4        | 0.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3        | 0.69%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                             | 3        | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3        | 0.69%   |
| Intel I210 Gigabit Network Connection                                  | 3        | 0.69%   |
| Intel Ethernet Connection I217-LM                                      | 3        | 0.69%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2        | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 2        | 0.46%   |
| MediaTek Infinix HOT 50i                                               | 2        | 0.46%   |
| Intel Ethernet Connection (14) I219-LM                                 | 2        | 0.46%   |
| Intel Ethernet Connection (10) I219-V                                  | 2        | 0.46%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 2        | 0.46%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2        | 0.46%   |
| VIA VT6105/VT6106S [Rhine-III]                                         | 1        | 0.23%   |
| TP-Link USB 10/100 LAN                                                 | 1        | 0.23%   |
| Sony Ericsson Mobile AB H8266                                          | 1        | 0.23%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1        | 0.23%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1        | 0.23%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1        | 0.23%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1        | 0.23%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1        | 0.23%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1        | 0.23%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1        | 0.23%   |
| Qualcomm Nokia X30 5G                                                  | 1        | 0.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 400      | 80.97%  |
| WiFi     | 93       | 18.83%  |
| Modem    | 1        | 0.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 381      | 94.07%  |
| WiFi     | 24       | 5.93%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 314      | 78.3%   |
| 2     | 83       | 20.7%   |
| 3     | 3        | 0.75%   |
| 4     | 1        | 0.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 393      | 97.76%  |
| Yes  | 9        | 2.24%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 36       | 46.15%  |
| Realtek Semiconductor           | 21       | 26.92%  |
| Cambridge Silicon Radio         | 5        | 6.41%   |
| Broadcom                        | 4        | 5.13%   |
| TP-Link                         | 3        | 3.85%   |
| IMC Networks                    | 3        | 3.85%   |
| ASUSTek Computer                | 2        | 2.56%   |
| Qualcomm Atheros Communications | 1        | 1.28%   |
| MediaTek                        | 1        | 1.28%   |
| Actions                         | 1        | 1.28%   |
| Unknown                         | 1        | 1.28%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Realtek Bluetooth Radio                               | 15       | 19.23%  |
| Intel Bluetooth wireless interface                    | 13       | 16.67%  |
| Intel Wireless-AC 3168 Bluetooth                      | 7        | 8.97%   |
| Intel AX200 Bluetooth                                 | 5        | 6.41%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 5        | 6.41%   |
| Realtek Bluetooth 5.3 Radio                           | 4        | 5.13%   |
| Intel AX201 Bluetooth                                 | 4        | 5.13%   |
| TP-Link TP-T@- UB500 Adapter                          | 3        | 3.85%   |
| Intel Bluetooth Device                                | 3        | 3.85%   |
| Intel AX210 Bluetooth                                 | 3        | 3.85%   |
| IMC Networks Bluetooth Radio                          | 2        | 2.56%   |
| Broadcom HP Portable Bumble Bee                       | 2        | 2.56%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1        | 1.28%   |
| Realtek 802.11ac WLAN Adapter                         | 1        | 1.28%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 1        | 1.28%   |
| MediaTek Wireless_Device                              | 1        | 1.28%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1        | 1.28%   |
| IMC Networks Wireless_Device                          | 1        | 1.28%   |
| Broadcom HP Bluetooth Module                          | 1        | 1.28%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter      | 1        | 1.28%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1        | 1.28%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 1.28%   |
| Actions general adapter                               | 1        | 1.28%   |
| Unknown                                               | 1        | 1.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 337      | 65.18%  |
| AMD                                          | 77       | 14.89%  |
| Nvidia                                       | 62       | 11.99%  |
| Texas Instruments                            | 6        | 1.16%   |
| C-Media Electronics                          | 6        | 1.16%   |
| Logitech                                     | 4        | 0.77%   |
| Razer USA                                    | 2        | 0.39%   |
| JMTek                                        | 2        | 0.39%   |
| Hewlett-Packard                              | 2        | 0.39%   |
| Generalplus Technology                       | 2        | 0.39%   |
| Creative Technology                          | 2        | 0.39%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.19%   |
| Weltrend Semiconductor                       | 1        | 0.19%   |
| Telink                                       | 1        | 0.19%   |
| Silicon Integrated Systems [SiS]             | 1        | 0.19%   |
| Samson Technologies                          | 1        | 0.19%   |
| Lenovo                                       | 1        | 0.19%   |
| KTMicro                                      | 1        | 0.19%   |
| Jieli Technology                             | 1        | 0.19%   |
| iCreate Technologies                         | 1        | 0.19%   |
| FiiO Electronics Technology                  | 1        | 0.19%   |
| DSEA A/S                                     | 1        | 0.19%   |
| DisplayLink                                  | 1        | 0.19%   |
| Audient                                      | 1        | 0.19%   |
| ASUSTek Computer                             | 1        | 0.19%   |
| Unknown                                      | 1        | 0.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Smart Sound Technology (SST) Audio Controller                        | 48       | 8.32%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 43       | 7.45%   |
| Intel 200 Series PCH HD Audio                                              | 38       | 6.59%   |
| Intel Alder Lake-S HD Audio Controller                                     | 34       | 5.89%   |
| AMD Ryzen HD Audio Controller                                              | 33       | 5.72%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 26       | 4.51%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 24       | 4.16%   |
| Intel Cannon Lake PCH cAVS                                                 | 23       | 3.99%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 18       | 3.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 17       | 2.95%   |
| Intel Comet Lake PCH-V cAVS                                                | 17       | 2.95%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 17       | 2.95%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 15       | 2.6%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 12       | 2.08%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 11       | 1.91%   |
| Nvidia High Definition Audio Controller                                    | 10       | 1.73%   |
| Intel Raptor Lake High Definition Audio Controller                         | 9        | 1.56%   |
| AMD Starship/Matisse HD Audio Controller                                   | 9        | 1.56%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 8        | 1.39%   |
| Intel Comet Lake PCH cAVS                                                  | 8        | 1.39%   |
| Texas Instruments PCM2902 Audio Codec                                      | 6        | 1.04%   |
| Nvidia GK107 HDMI Audio Controller                                         | 6        | 1.04%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 6        | 1.04%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5        | 0.87%   |
| Nvidia MCP61 High Definition Audio                                         | 4        | 0.69%   |
| Nvidia GF108 High Definition Audio Controller                              | 4        | 0.69%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 4        | 0.69%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4        | 0.69%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4        | 0.69%   |
| Nvidia TU116 High Definition Audio Controller                              | 3        | 0.52%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3        | 0.52%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 0.52%   |
| Nvidia GK104 HDMI Audio Controller                                         | 3        | 0.52%   |
| Nvidia GF119 HDMI Audio Controller                                         | 3        | 0.52%   |
| Nvidia GA106 High Definition Audio Controller                              | 3        | 0.52%   |
| Logitech 960 Headset                                                       | 3        | 0.52%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3        | 0.52%   |
| AMD Radeon High Definition Audio Controller                                | 3        | 0.52%   |
| AMD FCH Azalia Controller                                                  | 3        | 0.52%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3        | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Kingston                                | 59       | 13.95%  |
| Crucial                                 | 58       | 13.71%  |
| Unknown                                 | 53       | 12.53%  |
| Samsung Electronics                     | 36       | 8.51%   |
| Foxline                                 | 26       | 6.15%   |
| Apacer                                  | 20       | 4.73%   |
| AMD                                     | 20       | 4.73%   |
| A-DATA Technology                       | 20       | 4.73%   |
| Patriot                                 | 17       | 4.02%   |
| SK hynix                                | 15       | 3.55%   |
| Micron Technology                       | 11       | 2.6%    |
| Unknown                                 | 10       | 2.36%   |
| KingSpec                                | 7        | 1.65%   |
| Unknown (0x7FFF)                        | 4        | 0.95%   |
| Unknown (0x0080)                        | 4        | 0.95%   |
| Corsair                                 | 4        | 0.95%   |
| Unknown (89F7)                          | 3        | 0.71%   |
| Ramaxel Technology                      | 3        | 0.71%   |
| Netac                                   | 3        | 0.71%   |
| Neo Forza                               | 3        | 0.71%   |
| G.Skill                                 | 3        | 0.71%   |
| Elpida                                  | 3        | 0.71%   |
| Unknown (ABCD)                          | 2        | 0.47%   |
| Silicon Power Computer & Communications | 2        | 0.47%   |
| Silicon Power                           | 2        | 0.47%   |
| Shenzhen Micro Innovation Industry      | 2        | 0.47%   |
| Qumo                                    | 2        | 0.47%   |
| Nanya Technology                        | 2        | 0.47%   |
| KingTiger                               | 2        | 0.47%   |
| HomeNet                                 | 2        | 0.47%   |
| GOODRAM                                 | 2        | 0.47%   |
| Gold Key                                | 2        | 0.47%   |
| Wilk                                    | 1        | 0.24%   |
| Unknown (8AD6)                          | 1        | 0.24%   |
| Unknown (0x0E54)                        | 1        | 0.24%   |
| Unknown (0x0E2A)                        | 1        | 0.24%   |
| Unknown (0x0BF7)                        | 1        | 0.24%   |
| Unknown (0x0B7A)                        | 1        | 0.24%   |
| Unknown (0B7A)                          | 1        | 0.24%   |
| Transcend                               | 1        | 0.24%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Unknown                                                           | 10       | 2.25%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                          | 9        | 2.02%   |
| Foxline RAM FL2666D4U19-8G 8GB DIMM DDR4 2667MT/s                 | 8        | 1.8%    |
| Unknown RAM Module 1GB DIMM DDR2 333MT/s                          | 7        | 1.57%   |
| AMD RAM R748G2606U2S 8GB DIMM DDR4 3200MT/s                       | 6        | 1.35%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                         | 5        | 1.12%   |
| Unknown RAM Module 2GB DIMM SDRAM                                 | 5        | 1.12%   |
| Patriot RAM PSD44G266681 4GB DIMM DDR4 2667MT/s                   | 5        | 1.12%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s             | 5        | 1.12%   |
| Foxline RAM FL2666D4S19-8G 8GB SODIMM DDR4 2667MT/s               | 5        | 1.12%   |
| Crucial RAM CT8G4DFS8266.M8FD 8GB DIMM DDR4 3600MT/s              | 5        | 1.12%   |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s                         | 4        | 0.9%    |
| Kingston RAM 99U5474-026.A00LF 4GB DIMM DDR3 1333MT/s             | 4        | 0.9%    |
| KingSpec RAM KS2666D4P12008G 8GB DIMM DDR4 2667MT/s               | 4        | 0.9%    |
| Apacer RAM D12.2755BS.001 16GB DIMM DDR4 3200MT/s                 | 4        | 0.9%    |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                         | 3        | 0.67%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                         | 3        | 0.67%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                              | 3        | 0.67%   |
| Samsung RAM M378A1K43EB2-CWE 8GB DIMM DDR4 3200MT/s               | 3        | 0.67%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s                   | 3        | 0.67%   |
| Neo Forza RAM NMUD480E82-2666E 8GB DIMM DDR4 2667MT/s             | 3        | 0.67%   |
| Kingston RAM KF552C40-16 16GB DIMM DDR5 5400MT/s                  | 3        | 0.67%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s             | 3        | 0.67%   |
| Crucial RAM CT8G4DFS824A.C8FDD1 8GB DIMM DDR4 3200MT/s            | 3        | 0.67%   |
| Crucial RAM CT8G4DFRA32A.M8FR 8GB DIMM DDR4 3533MT/s              | 3        | 0.67%   |
| A-DATA RAM Module 8GB DIMM DDR4 2667MT/s                          | 3        | 0.67%   |
| A-DATA RAM DDR4 3200 16GB DIMM DDR4 3600MT/s                      | 3        | 0.67%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                         | 2        | 0.45%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                              | 2        | 0.45%   |
| Unknown RAM Module 4GB DIMM                                       | 2        | 0.45%   |
| Unknown RAM Module 1GB DIMM SDRAM                                 | 2        | 0.45%   |
| Unknown RAM Module 1GB DIMM DDR2 266MT/s                          | 2        | 0.45%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s    | 2        | 0.45%   |
| Unknown (0x7FFF) RAM GRAVITON 8G4-USDM01 8GB SODIMM DDR4 3200MT/s | 2        | 0.45%   |
| SK hynix RAM HMT451U6MFR8C-PB 4GB DIMM DDR3                       | 2        | 0.45%   |
| Samsung RAM Module 8GB DIMM DDR4 2667MT/s                         | 2        | 0.45%   |
| Samsung RAM Module 1GB DIMM DDR2 533MT/s                          | 2        | 0.45%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s               | 2        | 0.45%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3266MT/s               | 2        | 0.45%   |
| Patriot RAM PSD48G240082 8GB DIMM DDR4 2400MT/s                   | 2        | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 242      | 61.89%  |
| DDR3    | 86       | 21.99%  |
| SDRAM   | 18       | 4.6%    |
| DDR2    | 18       | 4.6%    |
| DDR5    | 11       | 2.81%   |
| Unknown | 11       | 2.81%   |
| LPDDR4  | 3        | 0.77%   |
| DDR     | 2        | 0.51%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 331      | 85.75%  |
| SODIMM | 54       | 13.99%  |
| RIMM   | 1        | 0.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 189      | 45.54%  |
| 4096  | 96       | 23.13%  |
| 16384 | 54       | 13.01%  |
| 2048  | 45       | 10.84%  |
| 1024  | 18       | 4.34%   |
| 32768 | 12       | 2.89%   |
| 512   | 1        | 0.24%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 2667    | 93       | 22.68%  |
| 3200    | 72       | 17.56%  |
| 1600    | 44       | 10.73%  |
| 1333    | 44       | 10.73%  |
| 2400    | 26       | 6.34%   |
| 2133    | 14       | 3.41%   |
| 3600    | 12       | 2.93%   |
| 333     | 11       | 2.68%   |
| 2666    | 9        | 2.2%    |
| Unknown | 8        | 1.95%   |
| 800     | 7        | 1.71%   |
| 4800    | 6        | 1.46%   |
| 2933    | 5        | 1.22%   |
| 2800    | 4        | 0.98%   |
| 5400    | 3        | 0.73%   |
| 4000    | 3        | 0.73%   |
| 3533    | 3        | 0.73%   |
| 2934    | 3        | 0.73%   |
| 1866    | 3        | 0.73%   |
| 1800    | 3        | 0.73%   |
| 1066    | 3        | 0.73%   |
| 667     | 3        | 0.73%   |
| 533     | 3        | 0.73%   |
| 5600    | 2        | 0.49%   |
| 3800    | 2        | 0.49%   |
| 3334    | 2        | 0.49%   |
| 3333    | 2        | 0.49%   |
| 3266    | 2        | 0.49%   |
| 2733    | 2        | 0.49%   |
| 266     | 2        | 0.49%   |
| 8400    | 1        | 0.24%   |
| 3733    | 1        | 0.24%   |
| 3466    | 1        | 0.24%   |
| 3066    | 1        | 0.24%   |
| 3000    | 1        | 0.24%   |
| 2866    | 1        | 0.24%   |
| 2734    | 1        | 0.24%   |
| 2187    | 1        | 0.24%   |
| 2134    | 1        | 0.24%   |
| 2000    | 1        | 0.24%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Hewlett-Packard        | 9        | 32.14%  |
| Canon                  | 7        | 25%     |
| Pantum                 | 4        | 14.29%  |
| STMicroelectronics     | 1        | 3.57%   |
| Seiko Epson            | 1        | 3.57%   |
| Samsung Electronics    | 1        | 3.57%   |
| Kyocera                | 1        | 3.57%   |
| Intermec Technologies  | 1        | 3.57%   |
| Custom Engineering SPA | 1        | 3.57%   |
| CACTUS                 | 1        | 3.57%   |
| Brother Industries     | 1        | 3.57%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Canon LBP6030/6030B/6018L                                 | 2        | 7.14%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1        | 3.57%   |
| Seiko Epson M1100 Series                                  | 1        | 3.57%   |
| Samsung SCX-4300 Series                                   | 1        | 3.57%   |
| Pantum P3300DN series                                     | 1        | 3.57%   |
| Pantum P3010DW series                                     | 1        | 3.57%   |
| Pantum BM5100FDW series                                   | 1        | 3.57%   |
| Pantum BM5100ADN series                                   | 1        | 3.57%   |
| Kyocera FS-1040                                           | 1        | 3.57%   |
| Intermec PC23                                             | 1        | 3.57%   |
| HP LaserJet P2055 series                                  | 1        | 3.57%   |
| HP LaserJet P2035                                         | 1        | 3.57%   |
| HP LaserJet P1005                                         | 1        | 3.57%   |
| HP LaserJet M203-M206                                     | 1        | 3.57%   |
| HP LaserJet M14-M17                                       | 1        | 3.57%   |
| HP LaserJet M109-M112                                     | 1        | 3.57%   |
| HP LaserJet 1010                                          | 1        | 3.57%   |
| HP HP LaserJet Pro M428-M429                              | 1        | 3.57%   |
| HP Designjet T1200 PostScript                             | 1        | 3.57%   |
| Custom Engineering SPA VKP80200dpi                        | 1        | 3.57%   |
| Canon MF450 Series                                        | 1        | 3.57%   |
| Canon MF440 Series                                        | 1        | 3.57%   |
| Canon MF410 Series                                        | 1        | 3.57%   |
| Canon LiDE 300                                            | 1        | 3.57%   |
| Canon I-SENSYS MF4550d                                    | 1        | 3.57%   |
| CACTUS CS-LP1120                                          | 1        | 3.57%   |
| Brother HL-L2360D series                                  | 1        | 3.57%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 3        | 75%     |
| Hewlett-Packard | 1        | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 110 | 2        | 50%     |
| HP ScanJet Pro 2000 s2  | 1        | 25%     |
| Canon CanoScan LIDE 25  | 1        | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| SunplusIT                              | 14       | 16.87%  |
| Realtek Semiconductor                  | 9        | 10.84%  |
| Microdia                               | 9        | 10.84%  |
| Sunplus Innovation Technology          | 8        | 9.64%   |
| Logitech                               | 8        | 9.64%   |
| Alcor Micro                            | 7        | 8.43%   |
| Chicony Electronics                    | 4        | 4.82%   |
| lihappe8                               | 2        | 2.41%   |
| KYE Systems (Mouse Systems)            | 2        | 2.41%   |
| icSpring                               | 2        | 2.41%   |
| Creative Technology                    | 2        | 2.41%   |
| Apple                                  | 2        | 2.41%   |
| Web Camera                             | 1        | 1.2%    |
| WaveRider Communications               | 1        | 1.2%    |
| Sunplus IT                             | 1        | 1.2%    |
| QuickShot                              | 1        | 1.2%    |
| Novatek Microelectronics               | 1        | 1.2%    |
| Mimaki Engineering                     | 1        | 1.2%    |
| Microsoft                              | 1        | 1.2%    |
| Magic Control Technology               | 1        | 1.2%    |
| MacroSilicon                           | 1        | 1.2%    |
| Hopewin Electronic Material            | 1        | 1.2%    |
| Cheng Uei Precision Industry (Foxlink) | 1        | 1.2%    |
| Arkmicro Technologies                  | 1        | 1.2%    |
| AlcorMicroCorp                         | 1        | 1.2%    |
| A4Tech                                 | 1        | 1.2%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| SunplusIT USB Camera                                                 | 13       | 15.66%  |
| Microdia Camera                                                      | 9        | 10.84%  |
| Alcor Micro USB 2.0 PC Camera                                        | 6        | 7.23%   |
| Sunplus USB Microphone                                               | 4        | 4.82%   |
| Realtek 1080p Camera                                                 | 4        | 4.82%   |
| Realtek USB Camera                                                   | 3        | 3.61%   |
| Logitech Webcam C270                                                 | 3        | 3.61%   |
| Logitech HD Webcam C615                                              | 3        | 3.61%   |
| lihappe8 USB 2.0 Camera                                              | 2        | 2.41%   |
| icSpring camera                                                      | 2        | 2.41%   |
| Chicony HP High Definition 1MP Webcam                                | 2        | 2.41%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                      | 2        | 2.41%   |
| Web Camera Web Camera                                                | 1        | 1.2%    |
| WaveRider USB Camera                                                 | 1        | 1.2%    |
| SunplusIT SPCA2650 AV Camera                                         | 1        | 1.2%    |
| Sunplus IT AUKEY PC-LM1 USB Camera                                   | 1        | 1.2%    |
| Sunplus Integrated_Webcam_5M                                         | 1        | 1.2%    |
| Sunplus Hy-Usb2.0-2*MIC                                              | 1        | 1.2%    |
| Sunplus FULL HD webcam                                               | 1        | 1.2%    |
| Sunplus 2-USB 2.0 Camera                                             | 1        | 1.2%    |
| Realtek Thronmax Stream Go Pro Webcam                                | 1        | 1.2%    |
| Realtek HP 2.0MP High Definition Webcam                              | 1        | 1.2%    |
| QuickShot USB 2.0 PC Camera                                          | 1        | 1.2%    |
| Novatek HP High Definition 2MP Webcam                                | 1        | 1.2%    |
| Mimaki Engineering SHUNCCM                                           | 1        | 1.2%    |
| Microsoft LifeCam Studio                                             | 1        | 1.2%    |
| Magic Control JVA14-Capture                                          | 1        | 1.2%    |
| Logitech Webcam C310                                                 | 1        | 1.2%    |
| Logitech B525 HD Webcam                                              | 1        | 1.2%    |
| KYE Systems (Mouse Systems) Genius Webcam                            | 1        | 1.2%    |
| KYE Systems (Mouse Systems) FaceCam 1000X                            | 1        | 1.2%    |
| Hopewin Electronic Material Integrated Camera                        | 1        | 1.2%    |
| Creative VF0530 Live! Cam Chat IM                                    | 1        | 1.2%    |
| Creative Live! Cam inPerson HD VF0720                                | 1        | 1.2%    |
| Chicony HP 0.3MP Webcam                                              | 1        | 1.2%    |
| Chicony CNF8050 Webcam                                               | 1        | 1.2%    |
| Cheng Uei Precision Industry (Foxlink) HP High Definition 1MP Webcam | 1        | 1.2%    |
| Arkmicro USB2.0 PC CAMERA                                            | 1        | 1.2%    |
| AlcorMicroCorp SHUNCCM                                               | 1        | 1.2%    |
| Alcor Micro USB FHD Camera                                           | 1        | 1.2%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Focal-systems.Corp | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Focal-systems.Corp FT9201Fingerprint. | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Aktiv                     | 7        | 58.33%  |
| Aladdin R.D.              | 3        | 25%     |
| Aladdin Knowledge Systems | 2        | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Aktiv Rutoken lite                    | 7        | 58.33%  |
| Aladdin R.D. JaCarta                  | 2        | 16.67%  |
| Aladdin Knowledge Systems Token JC    | 2        | 16.67%  |
| Aladdin R.D. Smart card reader JCR721 | 1        | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 332      | 81.98%  |
| 1     | 67       | 16.54%  |
| 2     | 3        | 0.74%   |
| 3     | 2        | 0.49%   |
| 4     | 1        | 0.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 49       | 59.76%  |
| Net/wireless             | 12       | 14.63%  |
| Communication controller | 5        | 6.1%    |
| Chipcard                 | 5        | 6.1%    |
| Unassigned class         | 4        | 4.88%   |
| Net/ethernet             | 3        | 3.66%   |
| Sound                    | 1        | 1.22%   |
| Multimedia controller    | 1        | 1.22%   |
| Fingerprint reader       | 1        | 1.22%   |
| Bluetooth                | 1        | 1.22%   |


Linux in Portugal - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Portugal.

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

Total: 600

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | B550M AORUS ELITE           | [a8f54f681a](https://linux-hardware.org/?probe=a8f54f681a) | Feb 01, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [1a9e67408e](https://linux-hardware.org/?probe=1a9e67408e) | Jan 28, 2023 |
| Acer          | RS740DVF                    | [6aaeb06f9a](https://linux-hardware.org/?probe=6aaeb06f9a) | Jan 26, 2023 |
| Pegatron      | Narra6                      | [ac9462ee8e](https://linux-hardware.org/?probe=ac9462ee8e) | Jan 20, 2023 |
| HP            | ProLiant MicroServer Gen... | [cd6cedc906](https://linux-hardware.org/?probe=cd6cedc906) | Jan 17, 2023 |
| ASUSTek       | Benicia                     | [c0441ff1e5](https://linux-hardware.org/?probe=c0441ff1e5) | Jan 17, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [60a0157a51](https://linux-hardware.org/?probe=60a0157a51) | Jan 16, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [7c62282370](https://linux-hardware.org/?probe=7c62282370) | Jan 12, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [71c61d98b9](https://linux-hardware.org/?probe=71c61d98b9) | Jan 10, 2023 |
| MSI           | B350 KRAIT GAMING           | [d27b435baf](https://linux-hardware.org/?probe=d27b435baf) | Jan 10, 2023 |
| ASRock        | A320M-HDV R3.0              | [cb970f09e6](https://linux-hardware.org/?probe=cb970f09e6) | Jan 09, 2023 |
| HP            | 0AA4h                       | [8d177b0b8d](https://linux-hardware.org/?probe=8d177b0b8d) | Jan 09, 2023 |
| MSI           | H97 GAMING 3                | [39ec0d3441](https://linux-hardware.org/?probe=39ec0d3441) | Jan 09, 2023 |
| ASUSTek       | P8Z77-V LX                  | [bdc427771d](https://linux-hardware.org/?probe=bdc427771d) | Jan 08, 2023 |
| HP            | 83EE                        | [cb43945233](https://linux-hardware.org/?probe=cb43945233) | Jan 07, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [aff5a2ce85](https://linux-hardware.org/?probe=aff5a2ce85) | Jan 07, 2023 |
| Gigabyte      | H81M-S1                     | [db0e909d27](https://linux-hardware.org/?probe=db0e909d27) | Jan 06, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [eefb2d0334](https://linux-hardware.org/?probe=eefb2d0334) | Jan 03, 2023 |
| Gigabyte      | Z77P-D3                     | [76d75de6ac](https://linux-hardware.org/?probe=76d75de6ac) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [bbd09c7b2c](https://linux-hardware.org/?probe=bbd09c7b2c) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [013b1e7816](https://linux-hardware.org/?probe=013b1e7816) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [34528f04fe](https://linux-hardware.org/?probe=34528f04fe) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [7295ec02b5](https://linux-hardware.org/?probe=7295ec02b5) | Dec 31, 2022 |
| ASUSTek       | PRIME B550M-A               | [2161cbc9a0](https://linux-hardware.org/?probe=2161cbc9a0) | Dec 31, 2022 |
| ASUSTek       | Benicia                     | [9d307c5f2f](https://linux-hardware.org/?probe=9d307c5f2f) | Dec 31, 2022 |
| ASUSTek       | Benicia                     | [bc835cbca9](https://linux-hardware.org/?probe=bc835cbca9) | Dec 31, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [76e9829e66](https://linux-hardware.org/?probe=76e9829e66) | Dec 30, 2022 |
| ASUSTek       | B85M-GAMER                  | [ded2e7e4e6](https://linux-hardware.org/?probe=ded2e7e4e6) | Dec 26, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [b181e9e5a3](https://linux-hardware.org/?probe=b181e9e5a3) | Dec 26, 2022 |
| MSI           | B350 KRAIT GAMING           | [896aebf101](https://linux-hardware.org/?probe=896aebf101) | Dec 25, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [82f8802857](https://linux-hardware.org/?probe=82f8802857) | Dec 24, 2022 |
| HP            | 0980h                       | [d54665c87c](https://linux-hardware.org/?probe=d54665c87c) | Dec 21, 2022 |
| MSI           | H81M-P33                    | [5d91d96949](https://linux-hardware.org/?probe=5d91d96949) | Dec 20, 2022 |
| HP            | 0980h                       | [3faf0c7996](https://linux-hardware.org/?probe=3faf0c7996) | Dec 20, 2022 |
| Foxconn       | 2ABF                        | [10e579b77e](https://linux-hardware.org/?probe=10e579b77e) | Dec 18, 2022 |
| Dell          | 03V7GF A01                  | [3847c61b81](https://linux-hardware.org/?probe=3847c61b81) | Dec 17, 2022 |
| Dell          | 03V7GF A01                  | [e491b54a3c](https://linux-hardware.org/?probe=e491b54a3c) | Dec 17, 2022 |
| Unknown       | Unknown                     | [988a2e80c0](https://linux-hardware.org/?probe=988a2e80c0) | Dec 17, 2022 |
| Gigabyte      | H57M-USB3                   | [d4812cfdb6](https://linux-hardware.org/?probe=d4812cfdb6) | Dec 13, 2022 |
| Dell          | 0MY171 A00                  | [055bc4ea78](https://linux-hardware.org/?probe=055bc4ea78) | Dec 13, 2022 |
| Gigabyte      | H57M-USB3                   | [c48aaf8b29](https://linux-hardware.org/?probe=c48aaf8b29) | Dec 12, 2022 |
| ASRock        | G31M-GS                     | [2e1fc34b39](https://linux-hardware.org/?probe=2e1fc34b39) | Dec 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [d83227cce9](https://linux-hardware.org/?probe=d83227cce9) | Dec 10, 2022 |
| ASUSTek       | P5Q DELUXE                  | [1519fb3a87](https://linux-hardware.org/?probe=1519fb3a87) | Dec 06, 2022 |
| MSI           | Z490-A PRO                  | [34157244aa](https://linux-hardware.org/?probe=34157244aa) | Dec 05, 2022 |
| Packard Be... | FIH57                       | [a98f4adbab](https://linux-hardware.org/?probe=a98f4adbab) | Dec 05, 2022 |
| Gigabyte      | GA-MA785GT-UD3H             | [5ab13c42b3](https://linux-hardware.org/?probe=5ab13c42b3) | Dec 03, 2022 |
| Gigabyte      | GA-MA785GT-UD3H             | [b3ab0684c5](https://linux-hardware.org/?probe=b3ab0684c5) | Dec 03, 2022 |
| ASUSTek       | PRIME B360M-A               | [e28a13071a](https://linux-hardware.org/?probe=e28a13071a) | Dec 02, 2022 |
| ASUSTek       | PRIME B360M-A               | [44a7c01e06](https://linux-hardware.org/?probe=44a7c01e06) | Dec 02, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [a6a71120f2](https://linux-hardware.org/?probe=a6a71120f2) | Nov 30, 2022 |
| ASUSTek       | Benicia                     | [e5468e4258](https://linux-hardware.org/?probe=e5468e4258) | Nov 30, 2022 |
| HP            | 18E7                        | [5a5c2667a5](https://linux-hardware.org/?probe=5a5c2667a5) | Nov 26, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [ccf106edce](https://linux-hardware.org/?probe=ccf106edce) | Nov 24, 2022 |
| Gigabyte      | EG41MF-US2H                 | [07ac3ace2c](https://linux-hardware.org/?probe=07ac3ace2c) | Nov 24, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [99fc338b3e](https://linux-hardware.org/?probe=99fc338b3e) | Nov 23, 2022 |
| MSI           | 990FXA-GD65                 | [8e134485ce](https://linux-hardware.org/?probe=8e134485ce) | Nov 22, 2022 |
| MSI           | 990FXA-GD65                 | [d41acd5075](https://linux-hardware.org/?probe=d41acd5075) | Nov 20, 2022 |
| ASRock        | B550 Extreme4               | [7fba8e38dc](https://linux-hardware.org/?probe=7fba8e38dc) | Nov 20, 2022 |
| ASUSTek       | B85M-E                      | [2455b541f5](https://linux-hardware.org/?probe=2455b541f5) | Nov 16, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [2c896d28a8](https://linux-hardware.org/?probe=2c896d28a8) | Nov 13, 2022 |
| ASUSTek       | B85M-GAMER                  | [112508759b](https://linux-hardware.org/?probe=112508759b) | Nov 13, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [dc1c83bed5](https://linux-hardware.org/?probe=dc1c83bed5) | Nov 11, 2022 |
| ASUSTek       | PRIME B360M-A               | [c46dd8d9b6](https://linux-hardware.org/?probe=c46dd8d9b6) | Nov 01, 2022 |
| Pegatron      | TRUCKEE                     | [2a6fe2bcd1](https://linux-hardware.org/?probe=2a6fe2bcd1) | Oct 28, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [fe9ec739e2](https://linux-hardware.org/?probe=fe9ec739e2) | Oct 24, 2022 |
| HP            | 805D                        | [ece9f05ea6](https://linux-hardware.org/?probe=ece9f05ea6) | Oct 14, 2022 |
| HP            | 805D                        | [f10271c447](https://linux-hardware.org/?probe=f10271c447) | Oct 14, 2022 |
| ASRock        | 970M Pro3                   | [ca8ac557b3](https://linux-hardware.org/?probe=ca8ac557b3) | Oct 14, 2022 |
| ASRock        | 970M Pro3                   | [9eaf0bffca](https://linux-hardware.org/?probe=9eaf0bffca) | Oct 09, 2022 |
| MSI           | B550-A PRO                  | [be6a0fda35](https://linux-hardware.org/?probe=be6a0fda35) | Oct 08, 2022 |
| ASRock        | 970M Pro3                   | [76d2eeb1d0](https://linux-hardware.org/?probe=76d2eeb1d0) | Oct 07, 2022 |
| ASUSTek       | PRIME H410M-E               | [abe6a3fde2](https://linux-hardware.org/?probe=abe6a3fde2) | Oct 06, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [a055ed4d2c](https://linux-hardware.org/?probe=a055ed4d2c) | Oct 03, 2022 |
| ASUSTek       | PRIME H510M-K               | [5bdf95fbdc](https://linux-hardware.org/?probe=5bdf95fbdc) | Oct 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [9fff405744](https://linux-hardware.org/?probe=9fff405744) | Sep 26, 2022 |
| Gigabyte      | B550 GAMING X V2            | [34035b63b6](https://linux-hardware.org/?probe=34035b63b6) | Sep 25, 2022 |
| ASRock        | B550 Pro4                   | [a1009d700e](https://linux-hardware.org/?probe=a1009d700e) | Sep 21, 2022 |
| ASUSTek       | PRIME A320M-K               | [70a7e5cad3](https://linux-hardware.org/?probe=70a7e5cad3) | Sep 20, 2022 |
| MSI           | Z77A-G45                    | [b5a8d40602](https://linux-hardware.org/?probe=b5a8d40602) | Sep 18, 2022 |
| ASUSTek       | P5L-VM 1394                 | [a7931f2026](https://linux-hardware.org/?probe=a7931f2026) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [038f57c2d8](https://linux-hardware.org/?probe=038f57c2d8) | Sep 06, 2022 |
| ASUSTek       | PRIME H510M-K               | [6fa51d2c4e](https://linux-hardware.org/?probe=6fa51d2c4e) | Aug 31, 2022 |
| OEM           | Intel H81                   | [4b45e6dc61](https://linux-hardware.org/?probe=4b45e6dc61) | Aug 31, 2022 |
| ASUSTek       | Benicia                     | [08f930384d](https://linux-hardware.org/?probe=08f930384d) | Aug 25, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | [ba3fb2513f](https://linux-hardware.org/?probe=ba3fb2513f) | Aug 21, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | [7ee8720a43](https://linux-hardware.org/?probe=7ee8720a43) | Aug 21, 2022 |
| MSI           | Z370 PC PRO                 | [9131aa23c4](https://linux-hardware.org/?probe=9131aa23c4) | Aug 20, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [ed1f055157](https://linux-hardware.org/?probe=ed1f055157) | Aug 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [764eaea2ba](https://linux-hardware.org/?probe=764eaea2ba) | Aug 19, 2022 |
| MSI           | B85M-E45                    | [cb991c0789](https://linux-hardware.org/?probe=cb991c0789) | Aug 17, 2022 |
| ASUSTek       | Basswood                    | [26e4efad3f](https://linux-hardware.org/?probe=26e4efad3f) | Aug 14, 2022 |
| ASRock        | H410M-HVS                   | [4d1acc8488](https://linux-hardware.org/?probe=4d1acc8488) | Aug 11, 2022 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | [48b0dfdee0](https://linux-hardware.org/?probe=48b0dfdee0) | Aug 10, 2022 |
| ASUSTek       | P8Z77-V                     | [18935d4aff](https://linux-hardware.org/?probe=18935d4aff) | Aug 07, 2022 |
| ASUSTek       | P8H67                       | [508b0275e3](https://linux-hardware.org/?probe=508b0275e3) | Aug 02, 2022 |
| Gigabyte      | H110M-Gaming3-CF            | [99a140d79b](https://linux-hardware.org/?probe=99a140d79b) | Aug 01, 2022 |
| ASUSTek       | P5G41C-M LX                 | [4e30dc6361](https://linux-hardware.org/?probe=4e30dc6361) | Jul 31, 2022 |
| Gigabyte      | B450M DS3H-CF               | [ea83758651](https://linux-hardware.org/?probe=ea83758651) | Jul 30, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [0c310749f1](https://linux-hardware.org/?probe=0c310749f1) | Jul 26, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [ae71cae955](https://linux-hardware.org/?probe=ae71cae955) | Jul 25, 2022 |
| ASUSTek       | PRIME H570M-PLUS            | [b3dbd37276](https://linux-hardware.org/?probe=b3dbd37276) | Jul 22, 2022 |
| MSI           | A78M-E45 V2                 | [c5007c5729](https://linux-hardware.org/?probe=c5007c5729) | Jul 22, 2022 |
| ASUSTek       | P8Z77-V                     | [bb9f40d075](https://linux-hardware.org/?probe=bb9f40d075) | Jul 18, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [e1313016ee](https://linux-hardware.org/?probe=e1313016ee) | Jul 17, 2022 |
| ASUSTek       | EX-A320M-GAMING             | [68884b1723](https://linux-hardware.org/?probe=68884b1723) | Jul 17, 2022 |
| Acer          | FMCP7AM                     | [f2fc2e98c3](https://linux-hardware.org/?probe=f2fc2e98c3) | Jul 10, 2022 |
| Lenovo        | SHARKBAY NOK                | [15088a414c](https://linux-hardware.org/?probe=15088a414c) | Jul 03, 2022 |
| MSI           | B450M BAZOOKA V2            | [bded0a2071](https://linux-hardware.org/?probe=bded0a2071) | Jul 03, 2022 |
| HP            | 8169                        | [18c6ea7678](https://linux-hardware.org/?probe=18c6ea7678) | Jul 01, 2022 |
| HP            | 8169                        | [c479baadc1](https://linux-hardware.org/?probe=c479baadc1) | Jul 01, 2022 |
| MSI           | A78M-E45 V2                 | [e4cd6586b4](https://linux-hardware.org/?probe=e4cd6586b4) | Jun 26, 2022 |
| Gigabyte      | H310M H                     | [90038bfa8e](https://linux-hardware.org/?probe=90038bfa8e) | Jun 22, 2022 |
| MSI           | A78M-E45 V2                 | [97b9d51036](https://linux-hardware.org/?probe=97b9d51036) | Jun 20, 2022 |
| MSI           | B85M-E45                    | [58c2ff96e3](https://linux-hardware.org/?probe=58c2ff96e3) | Jun 17, 2022 |
| MSI           | A78M-E45 V2                 | [86394fa5df](https://linux-hardware.org/?probe=86394fa5df) | Jun 16, 2022 |
| MSI           | A78M-E45 V2                 | [a2d26ab800](https://linux-hardware.org/?probe=a2d26ab800) | Jun 14, 2022 |
| ASUSTek       | AT5IONT-I                   | [70438d549d](https://linux-hardware.org/?probe=70438d549d) | Jun 14, 2022 |
| ASUSTek       | AT5IONT-I                   | [56abd525d8](https://linux-hardware.org/?probe=56abd525d8) | Jun 14, 2022 |
| MSI           | B460M-A PRO                 | [c858bede94](https://linux-hardware.org/?probe=c858bede94) | Jun 05, 2022 |
| Dell          | 05XGC8 A01                  | [2a1316250b](https://linux-hardware.org/?probe=2a1316250b) | Jun 05, 2022 |
| MSI           | MAG B550M BAZOOKA           | [9399a639c8](https://linux-hardware.org/?probe=9399a639c8) | May 29, 2022 |
| MSI           | MAG B550M BAZOOKA           | [42b16ce834](https://linux-hardware.org/?probe=42b16ce834) | May 28, 2022 |
| MSI           | MAG B550M BAZOOKA           | [4620e51e7b](https://linux-hardware.org/?probe=4620e51e7b) | May 28, 2022 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | [ccf347729e](https://linux-hardware.org/?probe=ccf347729e) | May 19, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [93b08c2d75](https://linux-hardware.org/?probe=93b08c2d75) | May 19, 2022 |
| ASUSTek       | Maximus IV Extreme          | [08dedbb3cb](https://linux-hardware.org/?probe=08dedbb3cb) | May 18, 2022 |
| Dell          | 0HN7XN A00                  | [6fba9a10da](https://linux-hardware.org/?probe=6fba9a10da) | May 18, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [a83bed6668](https://linux-hardware.org/?probe=a83bed6668) | May 16, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [a2ae5d95dd](https://linux-hardware.org/?probe=a2ae5d95dd) | May 15, 2022 |
| ASRockRack    | X399D8A-2T                  | [f1d2fbc435](https://linux-hardware.org/?probe=f1d2fbc435) | May 12, 2022 |
| Gigabyte      | Z77P-D3                     | [40de59e6f7](https://linux-hardware.org/?probe=40de59e6f7) | May 10, 2022 |
| ASUSTek       | PRIME B360M-A               | [c589ad9143](https://linux-hardware.org/?probe=c589ad9143) | May 07, 2022 |
| ASUSTek       | M4A78LT-M                   | [2a10a13430](https://linux-hardware.org/?probe=2a10a13430) | May 06, 2022 |
| ASRock        | Z77 Pro3                    | [050aee0a5f](https://linux-hardware.org/?probe=050aee0a5f) | May 03, 2022 |
| MSI           | MS-7053                     | [6de132b805](https://linux-hardware.org/?probe=6de132b805) | May 02, 2022 |
| ASUSTek       | PRIME B360M-A               | [519ed87066](https://linux-hardware.org/?probe=519ed87066) | Apr 29, 2022 |
| ASUSTek       | PRIME B360M-A               | [c46a1d595b](https://linux-hardware.org/?probe=c46a1d595b) | Apr 29, 2022 |
| HP            | 8719                        | [7e0ae3d91f](https://linux-hardware.org/?probe=7e0ae3d91f) | Apr 22, 2022 |
| ASUSTek       | P5G41T-M LX3                | [a21dad9ee4](https://linux-hardware.org/?probe=a21dad9ee4) | Apr 20, 2022 |
| Gigabyte      | B550 GAMING X V2            | [278c76b54f](https://linux-hardware.org/?probe=278c76b54f) | Apr 18, 2022 |
| Gigabyte      | B550 GAMING X V2            | [5f49d4d7d8](https://linux-hardware.org/?probe=5f49d4d7d8) | Apr 14, 2022 |
| ASUSTek       | P5G41T-M LX                 | [db8350499d](https://linux-hardware.org/?probe=db8350499d) | Apr 09, 2022 |
| Gigabyte      | B550 GAMING X V2            | [9493efcabe](https://linux-hardware.org/?probe=9493efcabe) | Apr 03, 2022 |
| Gigabyte      | G31M-ES2L                   | [90a8431fc2](https://linux-hardware.org/?probe=90a8431fc2) | Mar 22, 2022 |
| Gigabyte      | A520M H                     | [46b8c80485](https://linux-hardware.org/?probe=46b8c80485) | Mar 17, 2022 |
| ASUSTek       | B85M-E                      | [36c1044633](https://linux-hardware.org/?probe=36c1044633) | Mar 16, 2022 |
| Gigabyte      | A520M H                     | [483e47645c](https://linux-hardware.org/?probe=483e47645c) | Mar 16, 2022 |
| ASUSTek       | PRIME H510M-K               | [8a97b4f2d3](https://linux-hardware.org/?probe=8a97b4f2d3) | Mar 09, 2022 |
| HP            | 0A54h                       | [2dfc948414](https://linux-hardware.org/?probe=2dfc948414) | Mar 08, 2022 |
| Gigabyte      | G31M-S2L                    | [dd40993d97](https://linux-hardware.org/?probe=dd40993d97) | Mar 03, 2022 |
| HP            | 3396                        | [f952a8f044](https://linux-hardware.org/?probe=f952a8f044) | Mar 01, 2022 |
| MSI           | B85M-E45                    | [42fba9424e](https://linux-hardware.org/?probe=42fba9424e) | Feb 27, 2022 |
| Minix         | NEO Z83-4 V1.1              | [8aa7469422](https://linux-hardware.org/?probe=8aa7469422) | Feb 27, 2022 |
| Biostar       | H81MHV3                     | [3fd07aef04](https://linux-hardware.org/?probe=3fd07aef04) | Feb 25, 2022 |
| ASUSTek       | PRIME X570-P                | [eacd6c646c](https://linux-hardware.org/?probe=eacd6c646c) | Feb 22, 2022 |
| IBM           | 819046G                     | [54b0798b76](https://linux-hardware.org/?probe=54b0798b76) | Feb 22, 2022 |
| ASUSTek       | P5VDC-X                     | [40943e3ee0](https://linux-hardware.org/?probe=40943e3ee0) | Feb 22, 2022 |
| HP            | 83F3                        | [9421f4385a](https://linux-hardware.org/?probe=9421f4385a) | Feb 18, 2022 |
| ASUSTek       | ROG STRIX B560-F GAMING ... | [f7ee45924c](https://linux-hardware.org/?probe=f7ee45924c) | Feb 17, 2022 |
| ASRock        | B550M Pro4                  | [b39fbbaec6](https://linux-hardware.org/?probe=b39fbbaec6) | Feb 16, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [8f1ce82db7](https://linux-hardware.org/?probe=8f1ce82db7) | Feb 15, 2022 |
| MSI           | MS-7053                     | [2ee97bf0a8](https://linux-hardware.org/?probe=2ee97bf0a8) | Feb 13, 2022 |
| MSI           | H61M-P20                    | [81b315b229](https://linux-hardware.org/?probe=81b315b229) | Feb 09, 2022 |
| MSI           | B85M-E45                    | [3653d29a0a](https://linux-hardware.org/?probe=3653d29a0a) | Feb 07, 2022 |
| Foxconn       | H67M-S/H67M-V/H67           | [a3f3367577](https://linux-hardware.org/?probe=a3f3367577) | Feb 02, 2022 |
| ASUSTek       | P5K3L-ASUS-S1-P5G35         | [f9e7838b90](https://linux-hardware.org/?probe=f9e7838b90) | Jan 31, 2022 |
| Foxconn       | nT-i1000 Series PCB         | [72374dc22c](https://linux-hardware.org/?probe=72374dc22c) | Jan 26, 2022 |
| Foxconn       | nT-i1000 Series PCB         | [78cdf0490a](https://linux-hardware.org/?probe=78cdf0490a) | Jan 26, 2022 |
| Gigabyte      | H110M-Gaming3-CF            | [5b23faaf76](https://linux-hardware.org/?probe=5b23faaf76) | Jan 22, 2022 |
| Gigabyte      | H110M-Gaming3-CF            | [3791490565](https://linux-hardware.org/?probe=3791490565) | Jan 22, 2022 |
| Lenovo        | 313C SDK0J40697 WIN 3305... | [6cad862612](https://linux-hardware.org/?probe=6cad862612) | Jan 21, 2022 |
| MSI           | MS-7053                     | [8844db2984](https://linux-hardware.org/?probe=8844db2984) | Jan 13, 2022 |
| ASUSTek       | P5K PRO                     | [9338817523](https://linux-hardware.org/?probe=9338817523) | Jan 13, 2022 |
| ASUSTek       | V-P7H55E                    | [7fc2d44a4a](https://linux-hardware.org/?probe=7fc2d44a4a) | Jan 11, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [409de37ae4](https://linux-hardware.org/?probe=409de37ae4) | Jan 09, 2022 |
| Gigabyte      | P41T-D3P                    | [1c94714d99](https://linux-hardware.org/?probe=1c94714d99) | Jan 01, 2022 |
| Google        | Sion                        | [08215c86b6](https://linux-hardware.org/?probe=08215c86b6) | Dec 31, 2021 |
| ASUSTek       | A_F_K31AN                   | [4bd56c7243](https://linux-hardware.org/?probe=4bd56c7243) | Dec 29, 2021 |
| RKM           | Cherry Trail CR             | [907cacf8cc](https://linux-hardware.org/?probe=907cacf8cc) | Dec 29, 2021 |
| Huanan        | X79-8D VAA31                | [79be6da608](https://linux-hardware.org/?probe=79be6da608) | Dec 26, 2021 |
| HP            | 1998                        | [fffadbe1cf](https://linux-hardware.org/?probe=fffadbe1cf) | Dec 25, 2021 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | [855061aa1a](https://linux-hardware.org/?probe=855061aa1a) | Dec 18, 2021 |
| MSI           | MS-7053                     | [3e9330e811](https://linux-hardware.org/?probe=3e9330e811) | Dec 18, 2021 |
| MSI           | MS-7053                     | [b32db3cd18](https://linux-hardware.org/?probe=b32db3cd18) | Dec 18, 2021 |
| Gigabyte      | B550 AORUS ELITE            | [830b8475ac](https://linux-hardware.org/?probe=830b8475ac) | Dec 15, 2021 |
| ASUSTek       | PRIME X570-P                | [1812d44a36](https://linux-hardware.org/?probe=1812d44a36) | Dec 12, 2021 |
| Gigabyte      | B550M AORUS PRO             | [d1e767dfde](https://linux-hardware.org/?probe=d1e767dfde) | Dec 11, 2021 |
| ASUSTek       | P5G41T-M LX                 | [8b03acc524](https://linux-hardware.org/?probe=8b03acc524) | Dec 11, 2021 |
| Pegatron      | Benicia                     | [d50daedc5d](https://linux-hardware.org/?probe=d50daedc5d) | Nov 26, 2021 |
| ASUSTek       | P8Z77-V PRO                 | [22f1f5326e](https://linux-hardware.org/?probe=22f1f5326e) | Nov 21, 2021 |
| Biostar       | FX9830M                     | [f845fe2694](https://linux-hardware.org/?probe=f845fe2694) | Nov 19, 2021 |
| Gigabyte      | G31M-ES2L                   | [f30f49d634](https://linux-hardware.org/?probe=f30f49d634) | Nov 16, 2021 |
| Gigabyte      | G31M-ES2L                   | [fccd73da9d](https://linux-hardware.org/?probe=fccd73da9d) | Nov 12, 2021 |
| Dell          | 0HD5W2 A00                  | [d4c15ae33a](https://linux-hardware.org/?probe=d4c15ae33a) | Nov 08, 2021 |
| Minix         | NEO Z83-4 V1.1              | [c7b52e35cf](https://linux-hardware.org/?probe=c7b52e35cf) | Nov 08, 2021 |
| ASUSTek       | H87M-PLUS                   | [72e74c86fb](https://linux-hardware.org/?probe=72e74c86fb) | Nov 04, 2021 |
| ASUSTek       | H87M-PLUS                   | [bbb4e58192](https://linux-hardware.org/?probe=bbb4e58192) | Nov 04, 2021 |
| ASUSTek       | P5LD2-SE                    | [4f817c0167](https://linux-hardware.org/?probe=4f817c0167) | Nov 03, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [b643635a41](https://linux-hardware.org/?probe=b643635a41) | Nov 02, 2021 |
| ASUSTek       | P5LD2-SE                    | [8ba60d9634](https://linux-hardware.org/?probe=8ba60d9634) | Nov 01, 2021 |
| MSI           | P55-CD53                    | [d342f4e0a4](https://linux-hardware.org/?probe=d342f4e0a4) | Oct 29, 2021 |
| ASUSTek       | A_F_K31AN                   | [ebd51400e3](https://linux-hardware.org/?probe=ebd51400e3) | Oct 25, 2021 |
| ASUSTek       | B85M-E                      | [7a6479dc2d](https://linux-hardware.org/?probe=7a6479dc2d) | Oct 23, 2021 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [7313df4bd9](https://linux-hardware.org/?probe=7313df4bd9) | Oct 17, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | [005e2591e8](https://linux-hardware.org/?probe=005e2591e8) | Oct 17, 2021 |
| ASUSTek       | PRIME H510M-K               | [2ee0e02dca](https://linux-hardware.org/?probe=2ee0e02dca) | Oct 08, 2021 |
| ASUSTek       | H81M-A                      | [b73e4dc969](https://linux-hardware.org/?probe=b73e4dc969) | Oct 07, 2021 |
| ASUSTek       | PRIME H510M-K               | [cc60b4cc30](https://linux-hardware.org/?probe=cc60b4cc30) | Oct 07, 2021 |
| ASUSTek       | PRIME H510M-K               | [dae39c15c9](https://linux-hardware.org/?probe=dae39c15c9) | Oct 06, 2021 |
| MSI           | MPG B550 GAMING PLUS        | [eeae519a3e](https://linux-hardware.org/?probe=eeae519a3e) | Oct 04, 2021 |
| ASRock        | B450M Pro4                  | [a198e8517a](https://linux-hardware.org/?probe=a198e8517a) | Oct 01, 2021 |
| ASUSTek       | P5KC                        | [c6c9f72f10](https://linux-hardware.org/?probe=c6c9f72f10) | Sep 29, 2021 |
| ASUSTek       | M4N68T-M                    | [adaee7ea4e](https://linux-hardware.org/?probe=adaee7ea4e) | Sep 28, 2021 |
| ASUSTek       | PRIME H510M-K               | [c11c48b5d6](https://linux-hardware.org/?probe=c11c48b5d6) | Sep 24, 2021 |
| ASUSTek       | PRIME H510M-K               | [66900d1009](https://linux-hardware.org/?probe=66900d1009) | Sep 24, 2021 |
| ASUSTek       | PRIME X570-P                | [d8d6573dea](https://linux-hardware.org/?probe=d8d6573dea) | Sep 23, 2021 |
| Shuttle       | NC03U                       | [c5f76c4400](https://linux-hardware.org/?probe=c5f76c4400) | Sep 22, 2021 |
| Foxconn       | A74ML-K                     | [b7a9a59c77](https://linux-hardware.org/?probe=b7a9a59c77) | Sep 19, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [a7a8c2cead](https://linux-hardware.org/?probe=a7a8c2cead) | Sep 18, 2021 |
| Biostar       | A68MHE                      | [8a2cdafa86](https://linux-hardware.org/?probe=8a2cdafa86) | Sep 18, 2021 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | [82058974d9](https://linux-hardware.org/?probe=82058974d9) | Sep 17, 2021 |
| Libretrend    | LT1000                      | [781fa86fea](https://linux-hardware.org/?probe=781fa86fea) | Sep 17, 2021 |
| ASUSTek       | H81M-PLUS                   | [e8ac4691b0](https://linux-hardware.org/?probe=e8ac4691b0) | Sep 16, 2021 |
| ASRock        | X570M Pro4                  | [297bbaf6a4](https://linux-hardware.org/?probe=297bbaf6a4) | Sep 14, 2021 |
| Acer          | Elena                       | [c05122b62f](https://linux-hardware.org/?probe=c05122b62f) | Sep 14, 2021 |
| ASUSTek       | B85M-E                      | [1ef0a151b1](https://linux-hardware.org/?probe=1ef0a151b1) | Sep 12, 2021 |
| ASUSTek       | ROG CROSSHAIR VI EXTREME    | [4404093ccf](https://linux-hardware.org/?probe=4404093ccf) | Sep 12, 2021 |
| MSI           | B350 TOMAHAWK ARCTIC        | [b92b2f815b](https://linux-hardware.org/?probe=b92b2f815b) | Sep 07, 2021 |
| ASUSTek       | P5L8L-SE                    | [32e39bbd4f](https://linux-hardware.org/?probe=32e39bbd4f) | Sep 02, 2021 |
| ASUSTek       | P5Q DELUXE                  | [243dba3b27](https://linux-hardware.org/?probe=243dba3b27) | Sep 02, 2021 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [ca0e00bc0f](https://linux-hardware.org/?probe=ca0e00bc0f) | Sep 01, 2021 |
| ASRock        | N68-VS3 FX                  | [450ffd830c](https://linux-hardware.org/?probe=450ffd830c) | Sep 01, 2021 |
| ASUSTek       | P8H67                       | [73edbfaf52](https://linux-hardware.org/?probe=73edbfaf52) | Sep 01, 2021 |
| ASUSTek       | P8H67                       | [cefaaa7f19](https://linux-hardware.org/?probe=cefaaa7f19) | Sep 01, 2021 |
| ASRock        | 760GM-HDV                   | [7b2322353d](https://linux-hardware.org/?probe=7b2322353d) | Aug 29, 2021 |
| Unknown       | 1.0                         | [5e638360a8](https://linux-hardware.org/?probe=5e638360a8) | Aug 24, 2021 |
| ECS           | Livermore8                  | [a86f5a7745](https://linux-hardware.org/?probe=a86f5a7745) | Aug 18, 2021 |
| Unknown       | Unknown                     | [65ebd0006e](https://linux-hardware.org/?probe=65ebd0006e) | Aug 16, 2021 |
| ASUSTek       | P5P43TD PRO                 | [0576757382](https://linux-hardware.org/?probe=0576757382) | Aug 08, 2021 |
| Biostar       | A68MHE                      | [160e00a244](https://linux-hardware.org/?probe=160e00a244) | Aug 04, 2021 |
| Foxconn       | G41MXE/G41MXE-K             | [a6df82ec75](https://linux-hardware.org/?probe=a6df82ec75) | Jul 30, 2021 |
| Foxconn       | G41MXE/G41MXE-K             | [b33ddef912](https://linux-hardware.org/?probe=b33ddef912) | Jul 30, 2021 |
| HP            | ProLiant ML350 G5           | [189789f8d5](https://linux-hardware.org/?probe=189789f8d5) | Jul 23, 2021 |
| Intel         | DH61WW AAG23116-206         | [bdd8ae093d](https://linux-hardware.org/?probe=bdd8ae093d) | Jul 21, 2021 |
| Dell          | 04MFRM A02                  | [9d92f05e1c](https://linux-hardware.org/?probe=9d92f05e1c) | Jul 17, 2021 |
| Dell          | 04MFRM A02                  | [2b2a31a2f9](https://linux-hardware.org/?probe=2b2a31a2f9) | Jul 17, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | [1056457127](https://linux-hardware.org/?probe=1056457127) | Jul 17, 2021 |
| ASUSTek       | Crosshair IV Formula        | [4004b6bcb6](https://linux-hardware.org/?probe=4004b6bcb6) | Jul 16, 2021 |
| ASUSTek       | Crosshair IV Formula        | [1a9dfe2f20](https://linux-hardware.org/?probe=1a9dfe2f20) | Jul 16, 2021 |
| Gigabyte      | H110-D3A-CF                 | [e2a2b5ba07](https://linux-hardware.org/?probe=e2a2b5ba07) | Jul 13, 2021 |
| Gigabyte      | B365M HD3                   | [e663cfd24c](https://linux-hardware.org/?probe=e663cfd24c) | Jul 10, 2021 |
| ASRock        | N68-VS3 FX                  | [3bde956fe7](https://linux-hardware.org/?probe=3bde956fe7) | Jul 08, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [119260db14](https://linux-hardware.org/?probe=119260db14) | Jul 05, 2021 |
| ASUSTek       | P8H67-V                     | [66b161d8d5](https://linux-hardware.org/?probe=66b161d8d5) | Jul 02, 2021 |
| HP            | ProLiant ML350 G5           | [bc362bd630](https://linux-hardware.org/?probe=bc362bd630) | Jun 30, 2021 |
| ASRock        | H370M-ITX/ac                | [a6c720d609](https://linux-hardware.org/?probe=a6c720d609) | Jun 29, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [d2a4ffa502](https://linux-hardware.org/?probe=d2a4ffa502) | Jun 26, 2021 |
| MSI           | Z590-A PRO                  | [d6df0a85b4](https://linux-hardware.org/?probe=d6df0a85b4) | Jun 12, 2021 |
| MSI           | Z590-A PRO                  | [c7295eb580](https://linux-hardware.org/?probe=c7295eb580) | Jun 12, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | [d19e5c9398](https://linux-hardware.org/?probe=d19e5c9398) | Jun 11, 2021 |
| MSI           | B250 PC MATE                | [efa385c98c](https://linux-hardware.org/?probe=efa385c98c) | Jun 11, 2021 |
| ASUSTek       | D425MC                      | [aa893a2c50](https://linux-hardware.org/?probe=aa893a2c50) | Jun 10, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [599b4af4cf](https://linux-hardware.org/?probe=599b4af4cf) | Jun 06, 2021 |
| ASUSTek       | D425MC                      | [fc261e7b44](https://linux-hardware.org/?probe=fc261e7b44) | Jun 06, 2021 |
| Gigabyte      | Z77P-D3                     | [6a2bb03dcb](https://linux-hardware.org/?probe=6a2bb03dcb) | Jun 02, 2021 |
| ASUSTek       | D425MC                      | [d78ca41229](https://linux-hardware.org/?probe=d78ca41229) | Jun 01, 2021 |
| Gigabyte      | G41MT-S2                    | [5efbefcaa5](https://linux-hardware.org/?probe=5efbefcaa5) | May 30, 2021 |
| MSI           | Z490-A PRO                  | [654c105561](https://linux-hardware.org/?probe=654c105561) | May 28, 2021 |
| ASUSTek       | H110M-R                     | [62b22bfb20](https://linux-hardware.org/?probe=62b22bfb20) | May 26, 2021 |
| HP            | 3397                        | [ee57980b90](https://linux-hardware.org/?probe=ee57980b90) | May 25, 2021 |
| HP            | 1497                        | [7fa5ad3e42](https://linux-hardware.org/?probe=7fa5ad3e42) | May 25, 2021 |
| ASUSTek       | Z97-A                       | [0767c99abb](https://linux-hardware.org/?probe=0767c99abb) | May 19, 2021 |
| MSI           | B450 GAMING PRO CARBON M... | [0548f9650b](https://linux-hardware.org/?probe=0548f9650b) | May 18, 2021 |
| MSI           | H270M BAZOOKA               | [c2fdd4a7da](https://linux-hardware.org/?probe=c2fdd4a7da) | May 06, 2021 |
| ASUSTek       | P5S-MX SE                   | [2853189089](https://linux-hardware.org/?probe=2853189089) | May 01, 2021 |
| ASUSTek       | P5S-MX SE                   | [0d40576169](https://linux-hardware.org/?probe=0d40576169) | Apr 27, 2021 |
| NEC Comput... | PALOMAR                     | [3eebff8fad](https://linux-hardware.org/?probe=3eebff8fad) | Apr 16, 2021 |
| ASUSTek       | P9X79                       | [e9636d21ef](https://linux-hardware.org/?probe=e9636d21ef) | Apr 15, 2021 |
| MSI           | MPG Z390 GAMING PRO CARB... | [f0a9a9b376](https://linux-hardware.org/?probe=f0a9a9b376) | Apr 15, 2021 |
| ASUSTek       | PRIME X570-PRO              | [0f16d1f407](https://linux-hardware.org/?probe=0f16d1f407) | Apr 15, 2021 |
| MSI           | 760GA-P43                   | [f836b01395](https://linux-hardware.org/?probe=f836b01395) | Apr 14, 2021 |
| ASUSTek       | P5KC                        | [b9b6d74f4e](https://linux-hardware.org/?probe=b9b6d74f4e) | Apr 13, 2021 |
| Dell          | 0FH884                      | [93acc58efb](https://linux-hardware.org/?probe=93acc58efb) | Apr 10, 2021 |
| NEC Comput... | PALOMAR                     | [69d2761186](https://linux-hardware.org/?probe=69d2761186) | Apr 09, 2021 |
| ASUSTek       | P5KC                        | [2147d0b585](https://linux-hardware.org/?probe=2147d0b585) | Apr 08, 2021 |
| Gigabyte      | Z97X-Gaming 3               | [3a66ababd9](https://linux-hardware.org/?probe=3a66ababd9) | Apr 08, 2021 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [9b436e3e3c](https://linux-hardware.org/?probe=9b436e3e3c) | Apr 07, 2021 |
| Dell          | 0G261D A00                  | [8b417f82c5](https://linux-hardware.org/?probe=8b417f82c5) | Apr 06, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [ed7761776f](https://linux-hardware.org/?probe=ed7761776f) | Apr 02, 2021 |
| ASUSTek       | PRIME B450M-A II            | [292671b8bb](https://linux-hardware.org/?probe=292671b8bb) | Mar 26, 2021 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | [25b48fc578](https://linux-hardware.org/?probe=25b48fc578) | Mar 26, 2021 |
| ASUSTek       | P8H67-M LE                  | [d85cd54281](https://linux-hardware.org/?probe=d85cd54281) | Mar 21, 2021 |
| Gigabyte      | G41M-Combo                  | [b5838dd904](https://linux-hardware.org/?probe=b5838dd904) | Mar 20, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [d699973a80](https://linux-hardware.org/?probe=d699973a80) | Mar 15, 2021 |
| Pegatron      | 2A94h                       | [3b44f86cb2](https://linux-hardware.org/?probe=3b44f86cb2) | Mar 14, 2021 |
| ASRock        | A520M-HDV                   | [53bee57a08](https://linux-hardware.org/?probe=53bee57a08) | Mar 14, 2021 |
| MSI           | X470 GAMING PRO             | [d80b4b42b5](https://linux-hardware.org/?probe=d80b4b42b5) | Mar 10, 2021 |
| ASUSTek       | P5G41T-M LE                 | [a4382b583f](https://linux-hardware.org/?probe=a4382b583f) | Mar 09, 2021 |
| Gigabyte      | GA-MA785GT-UD3H             | [aeb9dde634](https://linux-hardware.org/?probe=aeb9dde634) | Mar 09, 2021 |
| Acer          | FMCP7AM                     | [0f4686671e](https://linux-hardware.org/?probe=0f4686671e) | Mar 05, 2021 |
| ASUSTek       | A_F_K31DA_K31DAG_K20DA      | [84d8d1fd23](https://linux-hardware.org/?probe=84d8d1fd23) | Mar 03, 2021 |
| Gigabyte      | GA-MA785GT-UD3H             | [f2186654a5](https://linux-hardware.org/?probe=f2186654a5) | Mar 03, 2021 |
| HP            | 3646h                       | [ae2d7f8ca8](https://linux-hardware.org/?probe=ae2d7f8ca8) | Mar 02, 2021 |
| Dell          | 0FH884                      | [e8894d16b4](https://linux-hardware.org/?probe=e8894d16b4) | Mar 02, 2021 |
| HP            | 08B8h                       | [c6f567409e](https://linux-hardware.org/?probe=c6f567409e) | Mar 02, 2021 |
| Acer          | FMCP7AM                     | [e73467285a](https://linux-hardware.org/?probe=e73467285a) | Mar 01, 2021 |
| Dell          | 0FH884                      | [3f73f703ea](https://linux-hardware.org/?probe=3f73f703ea) | Feb 25, 2021 |
| Dell          | 0FH884                      | [9ef7d7ac26](https://linux-hardware.org/?probe=9ef7d7ac26) | Feb 24, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [e0b5fd0d0f](https://linux-hardware.org/?probe=e0b5fd0d0f) | Feb 22, 2021 |
| BCM           | RX965Q                      | [889ee09398](https://linux-hardware.org/?probe=889ee09398) | Feb 21, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | [a4096f684a](https://linux-hardware.org/?probe=a4096f684a) | Feb 21, 2021 |
| Lenovo        | MAHOBAY NOK                 | [517098f97e](https://linux-hardware.org/?probe=517098f97e) | Feb 19, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [aadae3018a](https://linux-hardware.org/?probe=aadae3018a) | Feb 19, 2021 |
| ASRock        | AB350M Pro4                 | [427b038f6c](https://linux-hardware.org/?probe=427b038f6c) | Feb 16, 2021 |
| MSI           | MS-7145                     | [9339e94272](https://linux-hardware.org/?probe=9339e94272) | Feb 15, 2021 |
| ASRock        | J3455M                      | [3858448941](https://linux-hardware.org/?probe=3858448941) | Feb 15, 2021 |
| ASUSTek       | P8H61-M LE R2.0             | [5e21989251](https://linux-hardware.org/?probe=5e21989251) | Feb 14, 2021 |
| HP            | 2B36                        | [822dd71f17](https://linux-hardware.org/?probe=822dd71f17) | Feb 14, 2021 |
| Acer          | Aspire X1900                | [15ea004f33](https://linux-hardware.org/?probe=15ea004f33) | Feb 14, 2021 |
| MSI           | 890FXA-GD70                 | [ea6af67da0](https://linux-hardware.org/?probe=ea6af67da0) | Feb 13, 2021 |
| MSI           | G41M-P43 Combo              | [9854e43724](https://linux-hardware.org/?probe=9854e43724) | Feb 11, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [039362868b](https://linux-hardware.org/?probe=039362868b) | Feb 03, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [4c1fa69861](https://linux-hardware.org/?probe=4c1fa69861) | Feb 03, 2021 |
| MSI           | B360 GAMING PLUS            | [f409735b4a](https://linux-hardware.org/?probe=f409735b4a) | Feb 01, 2021 |
| ASRock        | AB350M Pro4                 | [f82376b2fc](https://linux-hardware.org/?probe=f82376b2fc) | Feb 01, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [159f94f03e](https://linux-hardware.org/?probe=159f94f03e) | Jan 29, 2021 |
| Dell          | 0GU083 A00                  | [b56844119d](https://linux-hardware.org/?probe=b56844119d) | Jan 29, 2021 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [273c518e4f](https://linux-hardware.org/?probe=273c518e4f) | Jan 28, 2021 |
| ASUSTek       | PRIME B350M-A               | [511b309049](https://linux-hardware.org/?probe=511b309049) | Jan 27, 2021 |
| MSI           | A320M PRO-VD/S              | [b0c09b63f4](https://linux-hardware.org/?probe=b0c09b63f4) | Jan 18, 2021 |
| MSI           | A320M PRO-VD/S              | [48710cf657](https://linux-hardware.org/?probe=48710cf657) | Jan 18, 2021 |
| ASUSTek       | P5SD2-VM                    | [9847d231eb](https://linux-hardware.org/?probe=9847d231eb) | Jan 14, 2021 |
| ASUSTek       | P5SD2-VM                    | [ee830fe216](https://linux-hardware.org/?probe=ee830fe216) | Jan 12, 2021 |
| ASUSTek       | P5G41T-M LX                 | [4db19bc22f](https://linux-hardware.org/?probe=4db19bc22f) | Jan 09, 2021 |
| HP            | 3397                        | [4c8e59bc44](https://linux-hardware.org/?probe=4c8e59bc44) | Jan 09, 2021 |
| HP            | Asterope                    | [9d863bfc8f](https://linux-hardware.org/?probe=9d863bfc8f) | Jan 08, 2021 |
| ASRock        | 775Dual-VSTA                | [e45a885545](https://linux-hardware.org/?probe=e45a885545) | Jan 03, 2021 |
| ASUSTek       | H87M-E                      | [d5d1562a32](https://linux-hardware.org/?probe=d5d1562a32) | Jan 01, 2021 |
| ASUSTek       | H87M-E                      | [b4a1983b91](https://linux-hardware.org/?probe=b4a1983b91) | Dec 27, 2020 |
| ASUSTek       | ROG CROSSHAIR VI HERO       | [660a038a14](https://linux-hardware.org/?probe=660a038a14) | Dec 23, 2020 |
| Dell          | 0RF703                      | [6f883fe6f5](https://linux-hardware.org/?probe=6f883fe6f5) | Dec 20, 2020 |
| ASUSTek       | PRIME B450-PLUS             | [609543807e](https://linux-hardware.org/?probe=609543807e) | Dec 19, 2020 |
| Gigabyte      | P75-D3                      | [e50b2ea863](https://linux-hardware.org/?probe=e50b2ea863) | Dec 16, 2020 |
| ASUSTek       | B150M PRO GAMING            | [50e588847b](https://linux-hardware.org/?probe=50e588847b) | Dec 16, 2020 |
| HP            | 3031h                       | [b1c4657359](https://linux-hardware.org/?probe=b1c4657359) | Dec 16, 2020 |
| ASUSTek       | H87M-E                      | [ba189ceaa2](https://linux-hardware.org/?probe=ba189ceaa2) | Dec 14, 2020 |
| Intel         | D865GSA AAD53275-204        | [1decb62bf9](https://linux-hardware.org/?probe=1decb62bf9) | Dec 13, 2020 |
| Intel         | D865GSA AAD53275-204        | [b94183234b](https://linux-hardware.org/?probe=b94183234b) | Dec 13, 2020 |
| MSI           | X470 GAMING PRO             | [b910c55313](https://linux-hardware.org/?probe=b910c55313) | Dec 01, 2020 |
| ASUSTek       | D425MC                      | [a2a7090e43](https://linux-hardware.org/?probe=a2a7090e43) | Nov 23, 2020 |
| MSI           | 990FXA GAMING               | [c67dd69ea3](https://linux-hardware.org/?probe=c67dd69ea3) | Nov 21, 2020 |
| MSI           | 990FXA GAMING               | [7b6ef87411](https://linux-hardware.org/?probe=7b6ef87411) | Nov 21, 2020 |
| ASUSTek       | STRIX B250G GAMING          | [3914e82da0](https://linux-hardware.org/?probe=3914e82da0) | Nov 14, 2020 |
| Gigabyte      | B550 AORUS ELITE            | [65b64eedcc](https://linux-hardware.org/?probe=65b64eedcc) | Nov 13, 2020 |
| Gigabyte      | F2A68HM-DS2                 | [a255bdcfbc](https://linux-hardware.org/?probe=a255bdcfbc) | Nov 12, 2020 |
| ASUSTek       | D425MC                      | [50665babae](https://linux-hardware.org/?probe=50665babae) | Nov 09, 2020 |
| ASUSTek       | STRIX B250G GAMING          | [4abd6c9e42](https://linux-hardware.org/?probe=4abd6c9e42) | Nov 08, 2020 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [0e4becb647](https://linux-hardware.org/?probe=0e4becb647) | Nov 06, 2020 |
| MSI           | G41M-P43 Combo              | [1d92dd04a2](https://linux-hardware.org/?probe=1d92dd04a2) | Oct 30, 2020 |
| ASUSTek       | P5G41T-M LE                 | [5d0df96501](https://linux-hardware.org/?probe=5d0df96501) | Oct 29, 2020 |
| ASUSTek       | P5G41T-M LE                 | [e4af11643b](https://linux-hardware.org/?probe=e4af11643b) | Oct 29, 2020 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [20acead566](https://linux-hardware.org/?probe=20acead566) | Oct 26, 2020 |
| ASUSTek       | PRIME B450-PLUS             | [4b14ad2894](https://linux-hardware.org/?probe=4b14ad2894) | Oct 25, 2020 |
| ASUSTek       | P5G41T-M LX2/GB             | [8136a41002](https://linux-hardware.org/?probe=8136a41002) | Oct 24, 2020 |
| ASUSTek       | P8P67                       | [17105ed101](https://linux-hardware.org/?probe=17105ed101) | Oct 23, 2020 |
| ASUSTek       | B85M-E                      | [b6190da277](https://linux-hardware.org/?probe=b6190da277) | Oct 23, 2020 |
| ASUSTek       | H110M-K                     | [08c91cec4d](https://linux-hardware.org/?probe=08c91cec4d) | Oct 21, 2020 |
| Fujitsu       | D2679-B1 S26361-D2679-Bx... | [b2c4383da1](https://linux-hardware.org/?probe=b2c4383da1) | Oct 20, 2020 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [12fab28ee5](https://linux-hardware.org/?probe=12fab28ee5) | Oct 14, 2020 |
| ASUSTek       | P5LD2-SE                    | [53e64ff105](https://linux-hardware.org/?probe=53e64ff105) | Oct 12, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [bfe6259c0c](https://linux-hardware.org/?probe=bfe6259c0c) | Oct 12, 2020 |
| ASUSTek       | Salmon                      | [1a9191eedc](https://linux-hardware.org/?probe=1a9191eedc) | Oct 12, 2020 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [19ef25af06](https://linux-hardware.org/?probe=19ef25af06) | Oct 09, 2020 |
| ASUSTek       | P5G41C-M LX                 | [d8d853d435](https://linux-hardware.org/?probe=d8d853d435) | Oct 09, 2020 |
| ASUSTek       | P8Z77-V LK                  | [490b10c9b5](https://linux-hardware.org/?probe=490b10c9b5) | Oct 03, 2020 |
| ASUSTek       | P9X79                       | [0cca3e59e7](https://linux-hardware.org/?probe=0cca3e59e7) | Oct 02, 2020 |
| MSI           | B350 PC MATE                | [fb4c90c999](https://linux-hardware.org/?probe=fb4c90c999) | Oct 02, 2020 |
| Foxconn       | 2ACA                        | [d1ca27b882](https://linux-hardware.org/?probe=d1ca27b882) | Oct 02, 2020 |
| ASUSTek       | Salmon                      | [67ec1c9e21](https://linux-hardware.org/?probe=67ec1c9e21) | Sep 30, 2020 |
| MSI           | B450M MORTAR                | [eb4023b66b](https://linux-hardware.org/?probe=eb4023b66b) | Sep 29, 2020 |
| MSI           | B150M MORTAR                | [1919443ef9](https://linux-hardware.org/?probe=1919443ef9) | Sep 29, 2020 |
| ASUSTek       | PRIME A320M-K               | [aa8ff9653f](https://linux-hardware.org/?probe=aa8ff9653f) | Sep 28, 2020 |
| Medion        | MS-7728                     | [27aa2e9b05](https://linux-hardware.org/?probe=27aa2e9b05) | Sep 28, 2020 |
| MSI           | B350M BAZOOKA               | [bc99ab4879](https://linux-hardware.org/?probe=bc99ab4879) | Sep 28, 2020 |
| ASUSTek       | P8H61-M LX                  | [f6ce95194c](https://linux-hardware.org/?probe=f6ce95194c) | Sep 27, 2020 |
| ASRock        | 775Dual-VSTA                | [40ed4cc83b](https://linux-hardware.org/?probe=40ed4cc83b) | Sep 24, 2020 |
| Gigabyte      | B550 AORUS ELITE            | [1abfd8ee8e](https://linux-hardware.org/?probe=1abfd8ee8e) | Sep 23, 2020 |
| ASUSTek       | Z97-A                       | [caef8bbdd2](https://linux-hardware.org/?probe=caef8bbdd2) | Sep 23, 2020 |
| ASRock        | X399 Taichi                 | [785a16d818](https://linux-hardware.org/?probe=785a16d818) | Sep 18, 2020 |
| ASUSTek       | P5GC-MX/1333                | [dc4566d1a7](https://linux-hardware.org/?probe=dc4566d1a7) | Sep 16, 2020 |
| Gigabyte      | B550 AORUS ELITE            | [deaed50282](https://linux-hardware.org/?probe=deaed50282) | Sep 04, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [24077cd964](https://linux-hardware.org/?probe=24077cd964) | Sep 03, 2020 |
| ASUSTek       | M4A88TD-M EVO               | [b084c1b4b6](https://linux-hardware.org/?probe=b084c1b4b6) | Aug 29, 2020 |
| ASUSTek       | Maximus VIII RANGER         | [6fbe8eb952](https://linux-hardware.org/?probe=6fbe8eb952) | Aug 29, 2020 |
| Foxconn       | 2ACA                        | [3293f910eb](https://linux-hardware.org/?probe=3293f910eb) | Aug 26, 2020 |
| Foxconn       | 2ACA                        | [20eb163379](https://linux-hardware.org/?probe=20eb163379) | Aug 26, 2020 |
| Gigabyte      | G31M-ES2L                   | [ed4a78cd06](https://linux-hardware.org/?probe=ed4a78cd06) | Aug 24, 2020 |
| Gigabyte      | EP45C-DS3R                  | [3baa06afa2](https://linux-hardware.org/?probe=3baa06afa2) | Aug 24, 2020 |
| ASUSTek       | P8H61-M LX                  | [dcc65ae2a7](https://linux-hardware.org/?probe=dcc65ae2a7) | Aug 23, 2020 |
| ASUSTek       | B85M-E                      | [cb8240a746](https://linux-hardware.org/?probe=cb8240a746) | Aug 21, 2020 |
| ASUSTek       | P5KPL-AM IN/GB              | [004f0c4c8d](https://linux-hardware.org/?probe=004f0c4c8d) | Aug 19, 2020 |
| Gigabyte      | B75M-D3V                    | [a8a68b1821](https://linux-hardware.org/?probe=a8a68b1821) | Aug 10, 2020 |
| MSI           | G41M-P43 Combo              | [312331a2e9](https://linux-hardware.org/?probe=312331a2e9) | Aug 10, 2020 |
| ASRock        | B450M Pro4-F                | [bd00a821fd](https://linux-hardware.org/?probe=bd00a821fd) | Aug 07, 2020 |
| ASUSTek       | H87M-PLUS                   | [82f189206f](https://linux-hardware.org/?probe=82f189206f) | Aug 03, 2020 |
| ASUSTek       | PRIME B350-PLUS             | [fff6cf2563](https://linux-hardware.org/?probe=fff6cf2563) | Aug 02, 2020 |
| ASRock        | 775Dual-VSTA                | [a2ad60fd2b](https://linux-hardware.org/?probe=a2ad60fd2b) | Aug 01, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [b981971204](https://linux-hardware.org/?probe=b981971204) | Aug 01, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [2195cd2a66](https://linux-hardware.org/?probe=2195cd2a66) | Aug 01, 2020 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [5e834a1db4](https://linux-hardware.org/?probe=5e834a1db4) | Jul 26, 2020 |
| ASUSTek       | B85M-E                      | [d745653595](https://linux-hardware.org/?probe=d745653595) | Jul 25, 2020 |
| MSI           | H81M-E33                    | [2ea88d42b6](https://linux-hardware.org/?probe=2ea88d42b6) | Jul 24, 2020 |
| Intel         | H81                         | [cd0d9e970b](https://linux-hardware.org/?probe=cd0d9e970b) | Jul 24, 2020 |
| ASUSTek       | P5VD2-MX                    | [b145b99009](https://linux-hardware.org/?probe=b145b99009) | Jul 24, 2020 |
| MSI           | B450 TOMAHAWK               | [b76c563f0f](https://linux-hardware.org/?probe=b76c563f0f) | Jul 24, 2020 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [9f64ca3b62](https://linux-hardware.org/?probe=9f64ca3b62) | Jul 24, 2020 |
| ASUSTek       | H110M-K                     | [8aeea51ed4](https://linux-hardware.org/?probe=8aeea51ed4) | Jul 24, 2020 |
| ASUSTek       | B85M-E                      | [256e33e5db](https://linux-hardware.org/?probe=256e33e5db) | Jul 24, 2020 |
| Gigabyte      | B450M DS3H-CF               | [df67dac45a](https://linux-hardware.org/?probe=df67dac45a) | Jul 23, 2020 |
| ASUSTek       | PRIME Z390-P                | [fcea9afdb8](https://linux-hardware.org/?probe=fcea9afdb8) | Jul 18, 2020 |
| Apple         | Mac-F4208DC8 PVT            | [ed3275a3ef](https://linux-hardware.org/?probe=ed3275a3ef) | Jul 13, 2020 |
| ASUSTek       | P8H61-M                     | [a96a1f0249](https://linux-hardware.org/?probe=a96a1f0249) | Jul 08, 2020 |
| Apple         | Mac-F4208DC8 PVT            | [b5a22259cb](https://linux-hardware.org/?probe=b5a22259cb) | Jul 06, 2020 |
| Apple         | Mac-F4208DC8 PVT            | [3194e779dc](https://linux-hardware.org/?probe=3194e779dc) | Jul 05, 2020 |
| Acer          | Aspire M3910                | [574212361b](https://linux-hardware.org/?probe=574212361b) | Jun 28, 2020 |
| ASRock        | AB350M Pro4                 | [14e2fc82a2](https://linux-hardware.org/?probe=14e2fc82a2) | Jun 25, 2020 |
| Dell          | 09WH54 A00                  | [5c11bd4168](https://linux-hardware.org/?probe=5c11bd4168) | Jun 21, 2020 |
| Lenovo        | 313C SDK0J40697 WIN 3305... | [edab290676](https://linux-hardware.org/?probe=edab290676) | Jun 20, 2020 |
| ASUSTek       | H110M-K                     | [4d9b1b16c1](https://linux-hardware.org/?probe=4d9b1b16c1) | Jun 16, 2020 |
| HP            | 0A60h                       | [51cea91fd2](https://linux-hardware.org/?probe=51cea91fd2) | Jun 13, 2020 |
| ASRock        | 775Dual-VSTA                | [0e5ac5a0bf](https://linux-hardware.org/?probe=0e5ac5a0bf) | Jun 12, 2020 |
| HP            | 8436                        | [a714970832](https://linux-hardware.org/?probe=a714970832) | Jun 11, 2020 |
| HP            | 843B                        | [dddd13622f](https://linux-hardware.org/?probe=dddd13622f) | Jun 10, 2020 |
| MSI           | G41M-P26                    | [01089d258b](https://linux-hardware.org/?probe=01089d258b) | Jun 09, 2020 |
| ASUSTek       | H110M-K                     | [e87bd7a1e6](https://linux-hardware.org/?probe=e87bd7a1e6) | Jun 09, 2020 |
| ASRock        | 775Dual-VSTA                | [a4f3841c00](https://linux-hardware.org/?probe=a4f3841c00) | May 29, 2020 |
| Gigabyte      | B75M-D3H                    | [2e9b2bd361](https://linux-hardware.org/?probe=2e9b2bd361) | May 26, 2020 |
| ASUSTek       | PRIME A320M-K               | [2b0f0312d9](https://linux-hardware.org/?probe=2b0f0312d9) | May 20, 2020 |
| HP            | 0A54h                       | [0eb9ef0dd8](https://linux-hardware.org/?probe=0eb9ef0dd8) | May 18, 2020 |
| HP            | 0A54h                       | [c6dfcc177a](https://linux-hardware.org/?probe=c6dfcc177a) | May 17, 2020 |
| MSI           | B150M BAZOOKA PLUS          | [6042465eaf](https://linux-hardware.org/?probe=6042465eaf) | May 10, 2020 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [b03c78fe4f](https://linux-hardware.org/?probe=b03c78fe4f) | May 09, 2020 |
| HP            | 3397                        | [3e224cf71e](https://linux-hardware.org/?probe=3e224cf71e) | May 07, 2020 |
| ASRock        | 775Dual-VSTA                | [3fe70d9fdd](https://linux-hardware.org/?probe=3fe70d9fdd) | May 06, 2020 |
| HP            | 8436                        | [cca70af9c6](https://linux-hardware.org/?probe=cca70af9c6) | May 05, 2020 |
| Acer          | Aspire X1900                | [8504ed80cb](https://linux-hardware.org/?probe=8504ed80cb) | May 05, 2020 |
| ASUSTek       | P8H61-M LX R2.0             | [7e0d4adca9](https://linux-hardware.org/?probe=7e0d4adca9) | May 04, 2020 |
| MSI           | 970A SLI Krait Edition      | [019e7deab8](https://linux-hardware.org/?probe=019e7deab8) | May 02, 2020 |
| HP            | 0AE8h C                     | [94f0b85b34](https://linux-hardware.org/?probe=94f0b85b34) | May 01, 2020 |
| ASRock        | 775Dual-VSTA                | [8fa9935547](https://linux-hardware.org/?probe=8fa9935547) | Apr 27, 2020 |
| Gigabyte      | B75M-D3V                    | [997cebc492](https://linux-hardware.org/?probe=997cebc492) | Apr 26, 2020 |
| Gigabyte      | B75M-D3V                    | [0001f7367a](https://linux-hardware.org/?probe=0001f7367a) | Apr 25, 2020 |
| Intel         | H81                         | [20f12251b6](https://linux-hardware.org/?probe=20f12251b6) | Apr 24, 2020 |
| ECS           | Nettle2                     | [ababaf523c](https://linux-hardware.org/?probe=ababaf523c) | Apr 19, 2020 |
| ASUSTek       | P8H61-M LX R2.0             | [4389b84dc5](https://linux-hardware.org/?probe=4389b84dc5) | Apr 16, 2020 |
| ASUSTek       | P5LD2-SE                    | [6d04e1a950](https://linux-hardware.org/?probe=6d04e1a950) | Apr 13, 2020 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [b70c50223a](https://linux-hardware.org/?probe=b70c50223a) | Apr 13, 2020 |
| MSI           | AMETHYST-M                  | [d42d07bebb](https://linux-hardware.org/?probe=d42d07bebb) | Apr 13, 2020 |
| ASUSTek       | Z97-PRO GAMER               | [8ceac6a75e](https://linux-hardware.org/?probe=8ceac6a75e) | Apr 13, 2020 |
| ASUSTek       | Z97-PRO GAMER               | [6b51a788d2](https://linux-hardware.org/?probe=6b51a788d2) | Apr 13, 2020 |
| MSI           | AMETHYST-M                  | [7c3997226d](https://linux-hardware.org/?probe=7c3997226d) | Apr 12, 2020 |
| ASUSTek       | M5A78L-M LX3                | [946ccde46f](https://linux-hardware.org/?probe=946ccde46f) | Apr 11, 2020 |
| Dell          | 0D28YY A00                  | [df89132283](https://linux-hardware.org/?probe=df89132283) | Apr 07, 2020 |
| Dell          | 0D28YY A00                  | [b87bc42bd0](https://linux-hardware.org/?probe=b87bc42bd0) | Apr 07, 2020 |
| Gigabyte      | B450M S2H                   | [1d19709a92](https://linux-hardware.org/?probe=1d19709a92) | Apr 07, 2020 |
| eMachines     | EMCP73M                     | [7ff7403af5](https://linux-hardware.org/?probe=7ff7403af5) | Apr 05, 2020 |
| ASUSTek       | P5LD2-SE                    | [21301abfd3](https://linux-hardware.org/?probe=21301abfd3) | Apr 03, 2020 |
| ASUSTek       | H97M-PLUS                   | [f33249c23f](https://linux-hardware.org/?probe=f33249c23f) | Apr 02, 2020 |
| ASUSTek       | A88X-PLUS                   | [eca8e2e768](https://linux-hardware.org/?probe=eca8e2e768) | Apr 02, 2020 |
| Dell          | 0D28YY A00                  | [616bad5cf3](https://linux-hardware.org/?probe=616bad5cf3) | Apr 01, 2020 |
| Gigabyte      | H310M H x.x                 | [b162dadd40](https://linux-hardware.org/?probe=b162dadd40) | Apr 01, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [6ec95a666d](https://linux-hardware.org/?probe=6ec95a666d) | Apr 01, 2020 |
| MSI           | MS-7341 10                  | [05450f5d8f](https://linux-hardware.org/?probe=05450f5d8f) | Mar 26, 2020 |
| MSI           | MS-7341 10                  | [98321d452d](https://linux-hardware.org/?probe=98321d452d) | Mar 21, 2020 |
| Acer          | RS740DVF                    | [93b6fee4e0](https://linux-hardware.org/?probe=93b6fee4e0) | Mar 12, 2020 |
| Acer          | RS740DVF                    | [be9d829372](https://linux-hardware.org/?probe=be9d829372) | Mar 11, 2020 |
| ASUSTek       | Z97-A                       | [40aef28c8a](https://linux-hardware.org/?probe=40aef28c8a) | Mar 08, 2020 |
| ASUSTek       | P5Q SE/R                    | [e7178ba8e7](https://linux-hardware.org/?probe=e7178ba8e7) | Mar 06, 2020 |
| AMI           | Cherry Trail CR             | [7f33611531](https://linux-hardware.org/?probe=7f33611531) | Mar 06, 2020 |
| AMI           | Cherry Trail CR             | [6ba8797a59](https://linux-hardware.org/?probe=6ba8797a59) | Mar 06, 2020 |
| Gigabyte      | H310M H x.x                 | [e5d85d26dd](https://linux-hardware.org/?probe=e5d85d26dd) | Mar 05, 2020 |
| ASRock        | B450M-HDV R4.0              | [e302ca148e](https://linux-hardware.org/?probe=e302ca148e) | Mar 05, 2020 |
| Acer          | RS740DVF                    | [aeb499b9d4](https://linux-hardware.org/?probe=aeb499b9d4) | Mar 04, 2020 |
| ASUSTek       | P5QL-ASUS-SE                | [b822a2ccbc](https://linux-hardware.org/?probe=b822a2ccbc) | Mar 02, 2020 |
| ASUSTek       | M3N-H/HDMI                  | [4b08896af8](https://linux-hardware.org/?probe=4b08896af8) | Mar 01, 2020 |
| ASUSTek       | P5G41T-M LX                 | [900ebfc65f](https://linux-hardware.org/?probe=900ebfc65f) | Mar 01, 2020 |
| MSI           | 970A GAMING PRO CARBON      | [84a38bd601](https://linux-hardware.org/?probe=84a38bd601) | Mar 01, 2020 |
| ASUSTek       | P5G41T-M LX                 | [f29225f74c](https://linux-hardware.org/?probe=f29225f74c) | Feb 24, 2020 |
| Medion        | MS-7366                     | [63d7b30a5a](https://linux-hardware.org/?probe=63d7b30a5a) | Feb 23, 2020 |
| Medion        | MS-7366                     | [ca03901ede](https://linux-hardware.org/?probe=ca03901ede) | Feb 23, 2020 |
| ASUSTek       | P5G41T-M LX                 | [e60551ae18](https://linux-hardware.org/?probe=e60551ae18) | Feb 22, 2020 |
| HP            | 2B36                        | [9e63f29da5](https://linux-hardware.org/?probe=9e63f29da5) | Feb 17, 2020 |
| Gigabyte      | G1.Sniper B6-CF             | [34bc4e6ef8](https://linux-hardware.org/?probe=34bc4e6ef8) | Feb 07, 2020 |
| Gigabyte      | G1.Sniper B6-CF             | [dcb876e046](https://linux-hardware.org/?probe=dcb876e046) | Feb 07, 2020 |
| ASUSTek       | P5LD2-VM                    | [3b118987fd](https://linux-hardware.org/?probe=3b118987fd) | Feb 03, 2020 |
| ASUSTek       | P5LD2-VM                    | [7eb3d3f57c](https://linux-hardware.org/?probe=7eb3d3f57c) | Jan 27, 2020 |
| HP            | 843B                        | [603aa1061c](https://linux-hardware.org/?probe=603aa1061c) | Jan 26, 2020 |
| HP            | 843B                        | [3673691cb2](https://linux-hardware.org/?probe=3673691cb2) | Jan 24, 2020 |
| HP            | 843B                        | [19231872c2](https://linux-hardware.org/?probe=19231872c2) | Jan 24, 2020 |
| Gigabyte      | B450M S2H                   | [ce8c8e3437](https://linux-hardware.org/?probe=ce8c8e3437) | Jan 19, 2020 |
| ASRock        | N68C-GS FX                  | [ed869b8762](https://linux-hardware.org/?probe=ed869b8762) | Jan 16, 2020 |
| ASRock        | N68-GS4/USB3 FX R2.0        | [1a903c9d61](https://linux-hardware.org/?probe=1a903c9d61) | Jan 14, 2020 |
| Huanan        | X79 VAA1                    | [bf970865ee](https://linux-hardware.org/?probe=bf970865ee) | Jan 13, 2020 |
| Dell          | 0GU083 A00                  | [f0711f3888](https://linux-hardware.org/?probe=f0711f3888) | Jan 10, 2020 |
| ASUSTek       | P5K SE/EPU                  | [5ee0f1db4c](https://linux-hardware.org/?probe=5ee0f1db4c) | Dec 19, 2019 |
| ASUSTek       | P5K SE/EPU                  | [9761122ab6](https://linux-hardware.org/?probe=9761122ab6) | Dec 17, 2019 |
| ASUSTek       | PRIME B250M-A               | [ae2fce57b5](https://linux-hardware.org/?probe=ae2fce57b5) | Dec 15, 2019 |
| Gigabyte      | B450M S2H                   | [65309beec0](https://linux-hardware.org/?probe=65309beec0) | Dec 09, 2019 |
| Gigabyte      | B450M S2H                   | [69cdd45ef3](https://linux-hardware.org/?probe=69cdd45ef3) | Dec 07, 2019 |
| Gigabyte      | B450M S2H                   | [985f0a93d2](https://linux-hardware.org/?probe=985f0a93d2) | Dec 07, 2019 |
| ASRock        | ConRoe945G-DVI              | [984156a325](https://linux-hardware.org/?probe=984156a325) | Dec 05, 2019 |
| ASUSTek       | P5KPL-AM SE                 | [e62db6e4e2](https://linux-hardware.org/?probe=e62db6e4e2) | Dec 02, 2019 |
| ASUSTek       | PRIME B250M-A               | [636cf95a59](https://linux-hardware.org/?probe=636cf95a59) | Nov 28, 2019 |
| Gigabyte      | B450M S2H                   | [e08baa017d](https://linux-hardware.org/?probe=e08baa017d) | Nov 23, 2019 |
| MSI           | 760GA-P43                   | [8e365df17f](https://linux-hardware.org/?probe=8e365df17f) | Nov 23, 2019 |
| Gigabyte      | G31M-ES2L                   | [0a1bc31c2a](https://linux-hardware.org/?probe=0a1bc31c2a) | Nov 19, 2019 |
| MSI           | B360M PRO-VDH               | [f83d0a812d](https://linux-hardware.org/?probe=f83d0a812d) | Nov 15, 2019 |
| Gigabyte      | AX370M-Gaming 3-CF          | [1679a050fb](https://linux-hardware.org/?probe=1679a050fb) | Nov 15, 2019 |
| Gigabyte      | AX370M-Gaming 3-CF          | [7850ee9963](https://linux-hardware.org/?probe=7850ee9963) | Nov 14, 2019 |
| ASUSTek       | P7H55-M                     | [376e73248b](https://linux-hardware.org/?probe=376e73248b) | Nov 10, 2019 |
| ASUSTek       | P7H55-M                     | [79e7d0b350](https://linux-hardware.org/?probe=79e7d0b350) | Nov 10, 2019 |
| Gigabyte      | B450M S2H                   | [b90be9510c](https://linux-hardware.org/?probe=b90be9510c) | Nov 07, 2019 |
| ASUSTek       | PRIME B250M-A               | [eb9fc83248](https://linux-hardware.org/?probe=eb9fc83248) | Nov 04, 2019 |
| ASUSTek       | PRIME B250M-A               | [1300445d89](https://linux-hardware.org/?probe=1300445d89) | Nov 03, 2019 |
| ASUSTek       | P5P43TD PRO                 | [b56c2b2e60](https://linux-hardware.org/?probe=b56c2b2e60) | Nov 02, 2019 |
| Dell          | 0KWVT8 A02                  | [6ed3187d7a](https://linux-hardware.org/?probe=6ed3187d7a) | Nov 01, 2019 |
| Intel         | D945GCZ AAC99321-502        | [9939882441](https://linux-hardware.org/?probe=9939882441) | Oct 15, 2019 |
| Intel         | D945GCZ AAC99321-502        | [7062600603](https://linux-hardware.org/?probe=7062600603) | Oct 15, 2019 |
| eMachines     | EL1850                      | [0ab5268867](https://linux-hardware.org/?probe=0ab5268867) | Oct 12, 2019 |
| GIADA         | SHARKBAY JHS688             | [51a3f3bf52](https://linux-hardware.org/?probe=51a3f3bf52) | Oct 07, 2019 |
| Unknown       | Unknown                     | [3a75852dac](https://linux-hardware.org/?probe=3a75852dac) | Oct 05, 2019 |
| Acer          | GRS400M                     | [1d3dc49b0a](https://linux-hardware.org/?probe=1d3dc49b0a) | Sep 29, 2019 |
| ASUSTek       | Z170-A                      | [8a875af2b7](https://linux-hardware.org/?probe=8a875af2b7) | Sep 28, 2019 |
| Acer          | GRS400M                     | [e510d98ae4](https://linux-hardware.org/?probe=e510d98ae4) | Sep 22, 2019 |
| Acer          | GRS400M                     | [213156ffb7](https://linux-hardware.org/?probe=213156ffb7) | Sep 22, 2019 |
| Gigabyte      | F2A68HM-DS2                 | [b2450355f1](https://linux-hardware.org/?probe=b2450355f1) | Sep 22, 2019 |
| HP            | 18E4                        | [169718ec5d](https://linux-hardware.org/?probe=169718ec5d) | Sep 20, 2019 |
| Gigabyte      | G31M-ES2L                   | [1e6cb16b41](https://linux-hardware.org/?probe=1e6cb16b41) | Sep 16, 2019 |
| ASUSTek       | P8H67-V                     | [b0c20b14d8](https://linux-hardware.org/?probe=b0c20b14d8) | Sep 13, 2019 |
| Gigabyte      | G31M-ES2L                   | [bb555c11ae](https://linux-hardware.org/?probe=bb555c11ae) | Sep 11, 2019 |
| ASUSTek       | M4A78 PRO                   | [85dbb03610](https://linux-hardware.org/?probe=85dbb03610) | Sep 02, 2019 |
| ASUSTek       | P8H67-M PRO                 | [e287f6207b](https://linux-hardware.org/?probe=e287f6207b) | Aug 28, 2019 |
| Intel         | D33217CK G76541-301         | [11b398d3ef](https://linux-hardware.org/?probe=11b398d3ef) | Aug 20, 2019 |
| MSI           | B360M PRO-VDH               | [2d45947160](https://linux-hardware.org/?probe=2d45947160) | Aug 09, 2019 |
| Gigabyte      | B75M-D3V                    | [eaac8d48ee](https://linux-hardware.org/?probe=eaac8d48ee) | Jul 29, 2019 |
| Gigabyte      | 970A-UD3P                   | [8cdd8ffe23](https://linux-hardware.org/?probe=8cdd8ffe23) | Jul 26, 2019 |
| Gigabyte      | 970A-UD3P                   | [69d1517ba1](https://linux-hardware.org/?probe=69d1517ba1) | Jul 26, 2019 |
| ASUSTek       | PRIME B250M-A               | [7f1f084a4f](https://linux-hardware.org/?probe=7f1f084a4f) | Jul 22, 2019 |
| Acer          | Aspire X1900                | [3c153b6c2a](https://linux-hardware.org/?probe=3c153b6c2a) | Jul 01, 2019 |
| ASUSTek       | PRIME B250M-A               | [26bcd3b325](https://linux-hardware.org/?probe=26bcd3b325) | Jun 27, 2019 |
| MSI           | Z68A-GD80                   | [c63ed488ad](https://linux-hardware.org/?probe=c63ed488ad) | Jun 21, 2019 |
| MSI           | Z68A-GD80                   | [ef06e84cda](https://linux-hardware.org/?probe=ef06e84cda) | Jun 20, 2019 |
| Gigabyte      | Z97-HD3                     | [5bb09aeb32](https://linux-hardware.org/?probe=5bb09aeb32) | Jun 19, 2019 |
| Dell          | 03NVJ6 A02                  | [160c2de51f](https://linux-hardware.org/?probe=160c2de51f) | Jun 17, 2019 |
| MSI           | B75A-G41                    | [0a593d376a](https://linux-hardware.org/?probe=0a593d376a) | Jun 16, 2019 |
| Gigabyte      | 8I915P-D                    | [1012bd5a43](https://linux-hardware.org/?probe=1012bd5a43) | Jun 16, 2019 |
| Gigabyte      | 8I915P-D                    | [770fa46180](https://linux-hardware.org/?probe=770fa46180) | Jun 16, 2019 |
| Gigabyte      | X58A-UD7                    | [a72ee8fc63](https://linux-hardware.org/?probe=a72ee8fc63) | Jun 11, 2019 |
| ASRock        | 970 Extreme4                | [0fa01e4d66](https://linux-hardware.org/?probe=0fa01e4d66) | Jun 06, 2019 |
| OEM           | EIRD-SAM                    | [db87d8567e](https://linux-hardware.org/?probe=db87d8567e) | May 30, 2019 |
| HP            | 1494                        | [25810f9dc3](https://linux-hardware.org/?probe=25810f9dc3) | May 28, 2019 |
| ASUSTek       | PRIME B250M-A               | [6555e3060d](https://linux-hardware.org/?probe=6555e3060d) | May 26, 2019 |
| Gigabyte      | H55M-S2H                    | [7d62e5bc34](https://linux-hardware.org/?probe=7d62e5bc34) | May 21, 2019 |
| ASUSTek       | PRIME B250M-A               | [a595e6c0f8](https://linux-hardware.org/?probe=a595e6c0f8) | May 19, 2019 |
| ASUSTek       | P5B-VM                      | [79d120d78a](https://linux-hardware.org/?probe=79d120d78a) | May 18, 2019 |
| ASUSTek       | PRIME B250M-A               | [5c5bd85a88](https://linux-hardware.org/?probe=5c5bd85a88) | May 15, 2019 |
| ASUSTek       | PRIME B250M-A               | [eea01b0dc4](https://linux-hardware.org/?probe=eea01b0dc4) | May 15, 2019 |
| ASUSTek       | PRIME B250M-A               | [b0e6f5b516](https://linux-hardware.org/?probe=b0e6f5b516) | May 14, 2019 |
| eMachines     | EMCP73M                     | [d2994e2fad](https://linux-hardware.org/?probe=d2994e2fad) | Apr 23, 2019 |
| ASUSTek       | H81-GAMER                   | [9145f41194](https://linux-hardware.org/?probe=9145f41194) | Apr 22, 2019 |
| ASUSTek       | H110M-K                     | [73b13633f2](https://linux-hardware.org/?probe=73b13633f2) | Apr 19, 2019 |
| Acer          | FMP55                       | [8c28446a53](https://linux-hardware.org/?probe=8c28446a53) | Apr 19, 2019 |
| ASUSTek       | B85M-G                      | [658bcf12c4](https://linux-hardware.org/?probe=658bcf12c4) | Apr 15, 2019 |
| Foxconn       | G31MXP FAB:1.1              | [84ae7d38dd](https://linux-hardware.org/?probe=84ae7d38dd) | Apr 14, 2019 |
| ASUSTek       | Benicia                     | [1f8cda3921](https://linux-hardware.org/?probe=1f8cda3921) | Apr 09, 2019 |
| ASUSTek       | Benicia                     | [b1615f3369](https://linux-hardware.org/?probe=b1615f3369) | Apr 09, 2019 |
| HP            | ProLiant ML310e Gen8        | [6ffa42170b](https://linux-hardware.org/?probe=6ffa42170b) | Mar 30, 2019 |
| HP            | 1494                        | [44ac651021](https://linux-hardware.org/?probe=44ac651021) | Mar 28, 2019 |
| ASUSTek       | PRIME B250M-A               | [2f6bc6be29](https://linux-hardware.org/?probe=2f6bc6be29) | Mar 28, 2019 |
| Gigabyte      | G1.Sniper B6-CF             | [c20b184fc3](https://linux-hardware.org/?probe=c20b184fc3) | Mar 27, 2019 |
| ASRock        | 970 Extreme4                | [e2e8bb29ea](https://linux-hardware.org/?probe=e2e8bb29ea) | Mar 22, 2019 |
| Intel         | D2500HN AAG81480-500        | [18f900cb5b](https://linux-hardware.org/?probe=18f900cb5b) | Mar 04, 2019 |
| MSI           | H81M-E33                    | [920d422115](https://linux-hardware.org/?probe=920d422115) | Feb 06, 2019 |
| HP            | 843B                        | [5ffb1194b1](https://linux-hardware.org/?probe=5ffb1194b1) | Jan 30, 2019 |
| MSI           | H310M PRO-VD                | [33c6c6f3a6](https://linux-hardware.org/?probe=33c6c6f3a6) | Jan 14, 2019 |
| ASRock        | Q1900B-ITX                  | [18ca69190b](https://linux-hardware.org/?probe=18ca69190b) | Jan 07, 2019 |
| ABIT          | F-I90HD                     | [b158a21c8f](https://linux-hardware.org/?probe=b158a21c8f) | Dec 22, 2018 |
| Gigabyte      | H55M-S2H                    | [34831e35fd](https://linux-hardware.org/?probe=34831e35fd) | Dec 18, 2018 |
| ASUSTek       | M5A97 R2.0                  | [89b0446385](https://linux-hardware.org/?probe=89b0446385) | Dec 14, 2018 |
| HP            | 3031h                       | [0c08eee650](https://linux-hardware.org/?probe=0c08eee650) | Dec 12, 2018 |
| HP            | 3031h                       | [2c22bfe429](https://linux-hardware.org/?probe=2c22bfe429) | Dec 12, 2018 |
| ASUSTek       | H110M-K                     | [5169edc36e](https://linux-hardware.org/?probe=5169edc36e) | Dec 12, 2018 |
| HP            | 3646h                       | [d930f87402](https://linux-hardware.org/?probe=d930f87402) | Dec 11, 2018 |
| ASUSTek       | P5G41T-M LX2/GB             | [fe5f95f298](https://linux-hardware.org/?probe=fe5f95f298) | Nov 14, 2018 |
| Gigabyte      | GA-MA785GMT-UD2H            | [ca9cd7920f](https://linux-hardware.org/?probe=ca9cd7920f) | Oct 24, 2018 |
| Gigabyte      | GA-MA785GMT-UD2H            | [edc37ce67e](https://linux-hardware.org/?probe=edc37ce67e) | Oct 24, 2018 |
| ASUSTek       | M5A78L LE                   | [762df5fa40](https://linux-hardware.org/?probe=762df5fa40) | Oct 22, 2018 |
| ASUSTek       | PRIME B350-PLUS             | [e2d2b150a5](https://linux-hardware.org/?probe=e2d2b150a5) | Sep 26, 2018 |
| Foxconn       | NT-A2400&NT-A3500 FAB       | [491d157b81](https://linux-hardware.org/?probe=491d157b81) | Jun 03, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Portugal/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 59       | 13.66%  |
| Ubuntu 18.04                 | 49       | 11.34%  |
| Ubuntu 22.04                 | 14       | 3.24%   |
| OpenMandriva 4.2             | 14       | 3.24%   |
| OpenMandriva 4.3             | 13       | 3.01%   |
| Debian 11                    | 13       | 3.01%   |
| Linux Mint 20                | 10       | 2.31%   |
| Linux Mint 19.3              | 10       | 2.31%   |
| ArcoLinux Rolling            | 9        | 2.08%   |
| Ubuntu 21.04                 | 8        | 1.85%   |
| Ubuntu 19.10                 | 7        | 1.62%   |
| Pop!_OS 22.04                | 7        | 1.62%   |
| Pop!_OS 20.04                | 7        | 1.62%   |
| Manjaro                      | 7        | 1.62%   |
| Zorin 16                     | 6        | 1.39%   |
| Linux Mint 20.2              | 6        | 1.39%   |
| Fedora 31                    | 6        | 1.39%   |
| Ubuntu 20.10                 | 5        | 1.16%   |
| Pop!_OS 21.04                | 5        | 1.16%   |
| openSUSE Tumbleweed-XXXXXXXX | 5        | 1.16%   |
| Linux Mint 20.1              | 5        | 1.16%   |
| Fedora 36                    | 5        | 1.16%   |
| Arch Rolling                 | 5        | 1.16%   |
| Zorin 15                     | 4        | 0.93%   |
| Xubuntu 20.04                | 4        | 0.93%   |
| Xubuntu 18.04                | 4        | 0.93%   |
| Pop!_OS 21.10                | 4        | 0.93%   |
| OpenMandriva 4.50            | 4        | 0.93%   |
| Linux Mint 20.3              | 4        | 0.93%   |
| Fedora 32                    | 4        | 0.93%   |
| Debian 10                    | 4        | 0.93%   |
| Ubuntu Unity 16.04           | 3        | 0.69%   |
| Ubuntu 19.04                 | 3        | 0.69%   |
| ROSA R11.1                   | 3        | 0.69%   |
| OpenMandriva 23.01           | 3        | 0.69%   |
| Manjaro 20.1                 | 3        | 0.69%   |
| Linux Mint 19.1              | 3        | 0.69%   |
| KDE neon 20.04               | 3        | 0.69%   |
| Fedora 37                    | 3        | 0.69%   |
| Debian 9                     | 3        | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 147      | 36.03%  |
| Linux Mint    | 44       | 10.78%  |
| OpenMandriva  | 34       | 8.33%   |
| Pop!_OS       | 23       | 5.64%   |
| Debian        | 21       | 5.15%   |
| Fedora        | 20       | 4.9%    |
| Manjaro       | 17       | 4.17%   |
| Zorin         | 11       | 2.7%    |
| Xubuntu       | 9        | 2.21%   |
| ArcoLinux     | 9        | 2.21%   |
| ROSA          | 8        | 1.96%   |
| Endless       | 7        | 1.72%   |
| Arch          | 7        | 1.72%   |
| openSUSE      | 6        | 1.47%   |
| Kubuntu       | 6        | 1.47%   |
| Ubuntu Unity  | 3        | 0.74%   |
| Ubuntu MATE   | 3        | 0.74%   |
| KDE neon      | 3        | 0.74%   |
| UbuntuDDE     | 2        | 0.49%   |
| Ubuntu Budgie | 2        | 0.49%   |
| Slackware     | 2        | 0.49%   |
| LMDE          | 2        | 0.49%   |
| EndeavourOS   | 2        | 0.49%   |
| Elementary    | 2        | 0.49%   |
| Clear Linux   | 2        | 0.49%   |
| CentOS        | 2        | 0.49%   |
| BigLinux      | 2        | 0.49%   |
| Xero          | 1        | 0.25%   |
| SteamOS       | 1        | 0.25%   |
| Solus         | 1        | 0.25%   |
| Rocky Linux   | 1        | 0.25%   |
| Puppy         | 1        | 0.25%   |
| Peppermint    | 1        | 0.25%   |
| Nobara        | 1        | 0.25%   |
| Lubuntu       | 1        | 0.25%   |
| Gentoo        | 1        | 0.25%   |
| Feren OS      | 1        | 0.25%   |
| BlackPanther  | 1        | 0.25%   |
| Alpine        | 1        | 0.25%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Desktops | Percent |
|----------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002         | 14       | 2.87%   |
| 5.4.0-42-generic                 | 13       | 2.67%   |
| 5.16.7-desktop-1omv4003          | 11       | 2.26%   |
| 5.15.0-56-generic                | 6        | 1.23%   |
| 5.8.0-43-generic                 | 5        | 1.03%   |
| 5.4.0-58-generic                 | 5        | 1.03%   |
| 5.4.0-48-generic                 | 5        | 1.03%   |
| 5.4.0-26-generic                 | 5        | 1.03%   |
| 5.10.0-8-amd64                   | 5        | 1.03%   |
| 5.8.0-48-generic                 | 4        | 0.82%   |
| 5.8.0-44-generic                 | 4        | 0.82%   |
| 5.4.0-77-generic                 | 4        | 0.82%   |
| 5.4.0-52-generic                 | 4        | 0.82%   |
| 5.19.0-76051900-generic          | 4        | 0.82%   |
| 5.15.0-57-generic                | 4        | 0.82%   |
| 5.13.0-7614-generic              | 4        | 0.82%   |
| 6.0.6-76060006-generic           | 3        | 0.62%   |
| 5.4.0-7634-generic               | 3        | 0.62%   |
| 5.4.0-40-generic                 | 3        | 0.62%   |
| 5.4.0-37-generic                 | 3        | 0.62%   |
| 5.4.0-29-generic                 | 3        | 0.62%   |
| 5.4.0-28-generic                 | 3        | 0.62%   |
| 5.3.0-51-generic                 | 3        | 0.62%   |
| 5.3.0-46-generic                 | 3        | 0.62%   |
| 5.3.0-40-generic                 | 3        | 0.62%   |
| 5.15.0-58-generic                | 3        | 0.62%   |
| 5.15.0-48-generic                | 3        | 0.62%   |
| 5.15.0-46-generic                | 3        | 0.62%   |
| 5.15.0-43-generic                | 3        | 0.62%   |
| 5.15.0-40-generic                | 3        | 0.62%   |
| 5.13.0-28-generic                | 3        | 0.62%   |
| 5.11.0-38-generic                | 3        | 0.62%   |
| 5.11.0-34-generic                | 3        | 0.62%   |
| 5.0.0-37-generic                 | 3        | 0.62%   |
| 5.0.0-23-generic                 | 3        | 0.62%   |
| 4.9.155-nrj-desktop-1rosa-x86_64 | 3        | 0.62%   |
| 4.18.0-17-generic                | 3        | 0.62%   |
| 4.15.0-55-generic                | 3        | 0.62%   |
| 4.15.0-51-generic                | 3        | 0.62%   |
| 4.15.0-42-generic                | 3        | 0.62%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 77       | 17.07%  |
| 4.15.0  | 40       | 8.87%   |
| 5.15.0  | 32       | 7.1%    |
| 5.8.0   | 28       | 6.21%   |
| 5.3.0   | 25       | 5.54%   |
| 5.11.0  | 22       | 4.88%   |
| 5.13.0  | 17       | 3.77%   |
| 5.0.0   | 16       | 3.55%   |
| 5.10.14 | 14       | 3.1%    |
| 4.18.0  | 13       | 2.88%   |
| 5.16.7  | 11       | 2.44%   |
| 5.10.0  | 10       | 2.22%   |
| 5.19.0  | 6        | 1.33%   |
| 6.0.9   | 5        | 1.11%   |
| 4.19.0  | 5        | 1.11%   |
| 5.15.7  | 4        | 0.89%   |
| 5.11.12 | 4        | 0.89%   |
| 4.9.155 | 4        | 0.89%   |
| 6.1.1   | 3        | 0.67%   |
| 6.0.6   | 3        | 0.67%   |
| 5.13.19 | 3        | 0.67%   |
| 6.1.4   | 2        | 0.44%   |
| 6.0.7   | 2        | 0.44%   |
| 5.8.6   | 2        | 0.44%   |
| 5.8.12  | 2        | 0.44%   |
| 5.7.10  | 2        | 0.44%   |
| 5.7.0   | 2        | 0.44%   |
| 5.6.10  | 2        | 0.44%   |
| 5.19.12 | 2        | 0.44%   |
| 5.18.16 | 2        | 0.44%   |
| 5.12.4  | 2        | 0.44%   |
| 5.10.74 | 2        | 0.44%   |
| 4.10.0  | 2        | 0.44%   |
| 6.0.8   | 1        | 0.22%   |
| 6.0.14  | 1        | 0.22%   |
| 6.0.12  | 1        | 0.22%   |
| 6.0.11  | 1        | 0.22%   |
| 5.9.6   | 1        | 0.22%   |
| 5.9.16  | 1        | 0.22%   |
| 5.9.15  | 1        | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 83       | 18.78%  |
| 5.15    | 44       | 9.95%   |
| 4.15    | 41       | 9.28%   |
| 5.8     | 35       | 7.92%   |
| 5.10    | 28       | 6.33%   |
| 5.11    | 27       | 6.11%   |
| 5.3     | 25       | 5.66%   |
| 5.13    | 24       | 5.43%   |
| 5.0     | 16       | 3.62%   |
| 4.18    | 16       | 3.62%   |
| 5.16    | 15       | 3.39%   |
| 5.19    | 13       | 2.94%   |
| 6.0     | 12       | 2.71%   |
| 4.9     | 8        | 1.81%   |
| 5.18    | 7        | 1.58%   |
| 5.7     | 6        | 1.36%   |
| 4.19    | 6        | 1.36%   |
| 6.1     | 5        | 1.13%   |
| 5.9     | 5        | 1.13%   |
| 5.14    | 5        | 1.13%   |
| 5.12    | 5        | 1.13%   |
| 5.6     | 3        | 0.68%   |
| 5.5     | 3        | 0.68%   |
| 5.17    | 3        | 0.68%   |
| 4.10    | 2        | 0.45%   |
| 5.2     | 1        | 0.23%   |
| 5.1     | 1        | 0.23%   |
| 4.4     | 1        | 0.23%   |
| 4.12    | 1        | 0.23%   |
| 2.6     | 1        | 0.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 373      | 95.89%  |
| i686   | 16       | 4.11%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 169      | 41.02%  |
| Unknown         | 70       | 16.99%  |
| KDE5            | 59       | 14.32%  |
| XFCE            | 36       | 8.74%   |
| X-Cinnamon      | 31       | 7.52%   |
| KDE             | 11       | 2.67%   |
| MATE            | 8        | 1.94%   |
| Budgie          | 5        | 1.21%   |
| Cinnamon        | 4        | 0.97%   |
| awesome         | 4        | 0.97%   |
| Unity           | 3        | 0.73%   |
| Pantheon        | 3        | 0.73%   |
| KDE4            | 3        | 0.73%   |
| Deepin          | 2        | 0.49%   |
| LXQt            | 1        | 0.24%   |
| LeftWM          | 1        | 0.24%   |
| i3              | 1        | 0.24%   |
| GNOME Flashback | 1        | 0.24%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 308      | 77.19%  |
| Wayland | 43       | 10.78%  |
| Unknown | 43       | 10.78%  |
| Tty     | 5        | 1.25%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 235      | 58.31%  |
| SDDM    | 52       | 12.9%   |
| GDM3    | 33       | 8.19%   |
| GDM     | 33       | 8.19%   |
| LightDM | 32       | 7.94%   |
| TDM     | 14       | 3.47%   |
| KDM     | 3        | 0.74%   |
| XDM     | 1        | 0.25%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| pt_PT   | 180      | 44.55%  |
| en_US   | 116      | 28.71%  |
| Unknown | 64       | 15.84%  |
| en_GB   | 16       | 3.96%   |
| C       | 7        | 1.73%   |
| pt_BR   | 5        | 1.24%   |
| fr_FR   | 4        | 0.99%   |
| sv_SE   | 3        | 0.74%   |
| ru_RU   | 3        | 0.74%   |
| es_ES   | 2        | 0.5%    |
| en_CA   | 2        | 0.5%    |
| de_DE   | 2        | 0.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 282      | 70.5%   |
| EFI  | 118      | 29.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 299      | 75.13%  |
| Overlay | 36       | 9.05%   |
| Btrfs   | 29       | 7.29%   |
| Unknown | 22       | 5.53%   |
| Xfs     | 8        | 2.01%   |
| Zfs     | 2        | 0.5%    |
| F2fs    | 1        | 0.25%   |
| Aufs    | 1        | 0.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 255      | 63.28%  |
| GPT     | 95       | 23.57%  |
| MBR     | 53       | 13.15%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 331      | 83.59%  |
| Yes       | 65       | 16.41%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 273      | 68.42%  |
| Yes       | 126      | 31.58%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 142      | 36.5%   |
| MSI                 | 52       | 13.37%  |
| Gigabyte Technology | 52       | 13.37%  |
| Hewlett-Packard     | 33       | 8.48%   |
| ASRock              | 26       | 6.68%   |
| Dell                | 15       | 3.86%   |
| Acer                | 9        | 2.31%   |
| Foxconn             | 8        | 2.06%   |
| Intel               | 6        | 1.54%   |
| Fujitsu             | 5        | 1.29%   |
| Pegatron            | 4        | 1.03%   |
| Lenovo              | 4        | 1.03%   |
| Unknown             | 4        | 1.03%   |
| eMachines           | 3        | 0.77%   |
| Biostar             | 3        | 0.77%   |
| OEM                 | 2        | 0.51%   |
| Minix               | 2        | 0.51%   |
| Medion              | 2        | 0.51%   |
| Huanan              | 2        | 0.51%   |
| ECS                 | 2        | 0.51%   |
| Shuttle             | 1        | 0.26%   |
| RKM                 | 1        | 0.26%   |
| Packard Bell        | 1        | 0.26%   |
| NEC Computers       | 1        | 0.26%   |
| Libretrend          | 1        | 0.26%   |
| IBM                 | 1        | 0.26%   |
| Google              | 1        | 0.26%   |
| GIADA               | 1        | 0.26%   |
| BCM                 | 1        | 0.26%   |
| ASRockRack          | 1        | 0.26%   |
| Apple               | 1        | 0.26%   |
| AMI                 | 1        | 0.26%   |
| ABIT                | 1        | 0.26%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| ASUS All Series                    | 13       | 3.34%   |
| MSI MS-7817                        | 5        | 1.29%   |
| ASUS P5G41T-M LX                   | 4        | 1.03%   |
| ASUS H110M-K                       | 4        | 1.03%   |
| Unknown                            | 4        | 1.03%   |
| HP Compaq Elite 8300 SFF           | 3        | 0.77%   |
| Gigabyte GA-78LMT-USB3 6.0         | 3        | 0.77%   |
| Gigabyte B550 AORUS ELITE          | 3        | 0.77%   |
| ASUS PRIME H510M-K                 | 3        | 0.77%   |
| ASUS PRIME A320M-K                 | 3        | 0.77%   |
| ASUS M5A78L-M/USB3                 | 3        | 0.77%   |
| MSI MS-7C75                        | 2        | 0.51%   |
| MSI MS-7C37                        | 2        | 0.51%   |
| MSI MS-7A38                        | 2        | 0.51%   |
| MSI MS-7A34                        | 2        | 0.51%   |
| MSI MS-7640                        | 2        | 0.51%   |
| MSI MS-7592                        | 2        | 0.51%   |
| Minix Z83-4                        | 2        | 0.51%   |
| HP Compaq dc7900 Small Form Factor | 2        | 0.51%   |
| HP Compaq dc7700 Small Form Factor | 2        | 0.51%   |
| HP Compaq 8000 Elite SFF PC        | 2        | 0.51%   |
| Gigabyte H55M-S2H                  | 2        | 0.51%   |
| Gigabyte H110M-Gaming 3            | 2        | 0.51%   |
| Gigabyte G31M-ES2L                 | 2        | 0.51%   |
| Gigabyte B550 GAMING X V2          | 2        | 0.51%   |
| Gigabyte B450M DS3H                | 2        | 0.51%   |
| Gigabyte B450 AORUS ELITE          | 2        | 0.51%   |
| eMachines EL1830                   | 2        | 0.51%   |
| Dell Precision WorkStation 490     | 2        | 0.51%   |
| ASUS SABERTOOTH 990FX R2.0         | 2        | 0.51%   |
| ASUS ROG STRIX X470-F GAMING       | 2        | 0.51%   |
| ASUS PRIME B450-PLUS               | 2        | 0.51%   |
| ASUS PRIME B350-PLUS               | 2        | 0.51%   |
| ASUS P9X79                         | 2        | 0.51%   |
| ASUS P8H67-V                       | 2        | 0.51%   |
| ASUS P8H67                         | 2        | 0.51%   |
| ASUS P5Q DELUXE                    | 2        | 0.51%   |
| ASUS P5P43TD PRO                   | 2        | 0.51%   |
| ASUS P5LD2-SE                      | 2        | 0.51%   |
| ASUS P5G41T-M LX2/GB               | 2        | 0.51%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 22       | 5.66%   |
| HP Compaq              | 15       | 3.86%   |
| ASUS All               | 13       | 3.34%   |
| Dell OptiPlex          | 10       | 2.57%   |
| ASUS ROG               | 9        | 2.31%   |
| ASUS P5G41T-M          | 9        | 2.31%   |
| Acer Aspire            | 8        | 2.06%   |
| HP ProDesk             | 6        | 1.54%   |
| Gigabyte B550          | 6        | 1.54%   |
| MSI MS-7817            | 5        | 1.29%   |
| ASUS TUF               | 5        | 1.29%   |
| Dell Precision         | 4        | 1.03%   |
| ASUS P8Z77-V           | 4        | 1.03%   |
| ASUS P8H61-M           | 4        | 1.03%   |
| ASUS M5A78L-M          | 4        | 1.03%   |
| ASUS H110M-K           | 4        | 1.03%   |
| Unknown                | 4        | 1.03%   |
| Lenovo ThinkCentre     | 3        | 0.77%   |
| HP ProLiant            | 3        | 0.77%   |
| HP Pavilion            | 3        | 0.77%   |
| Gigabyte GA-78LMT-USB3 | 3        | 0.77%   |
| Gigabyte B450M         | 3        | 0.77%   |
| Fujitsu ESPRIMO        | 3        | 0.77%   |
| ASUS P5Q               | 3        | 0.77%   |
| ASUS P5KPL-AM          | 3        | 0.77%   |
| ASUS A                 | 3        | 0.77%   |
| MSI MS-7C75            | 2        | 0.51%   |
| MSI MS-7C37            | 2        | 0.51%   |
| MSI MS-7A38            | 2        | 0.51%   |
| MSI MS-7A34            | 2        | 0.51%   |
| MSI MS-7640            | 2        | 0.51%   |
| MSI MS-7592            | 2        | 0.51%   |
| Minix Z83-4            | 2        | 0.51%   |
| Gigabyte H55M-S2H      | 2        | 0.51%   |
| Gigabyte H310M         | 2        | 0.51%   |
| Gigabyte H110M-Gaming  | 2        | 0.51%   |
| Gigabyte G31M-ES2L     | 2        | 0.51%   |
| Gigabyte B550M         | 2        | 0.51%   |
| Gigabyte B450          | 2        | 0.51%   |
| Fujitsu PRIMERGY       | 2        | 0.51%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 41       | 10.54%  |
| 2012 | 37       | 9.51%   |
| 2020 | 32       | 8.23%   |
| 2009 | 31       | 7.97%   |
| 2010 | 30       | 7.71%   |
| 2011 | 23       | 5.91%   |
| 2008 | 21       | 5.4%    |
| 2019 | 20       | 5.14%   |
| 2014 | 20       | 5.14%   |
| 2017 | 19       | 4.88%   |
| 2016 | 19       | 4.88%   |
| 2006 | 19       | 4.88%   |
| 2013 | 18       | 4.63%   |
| 2015 | 16       | 4.11%   |
| 2021 | 15       | 3.86%   |
| 2007 | 14       | 3.6%    |
| 2005 | 7        | 1.8%    |
| 2022 | 3        | 0.77%   |
| 2004 | 3        | 0.77%   |
| 2003 | 1        | 0.26%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 389      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 383      | 97.46%  |
| Enabled  | 10       | 2.54%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 387      | 99.49%  |
| Yes  | 2        | 0.51%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 93       | 23.08%  |
| 16.01-24.0  | 89       | 22.08%  |
| 8.01-16.0   | 73       | 18.11%  |
| 4.01-8.0    | 52       | 12.9%   |
| 32.01-64.0  | 45       | 11.17%  |
| 1.01-2.0    | 20       | 4.96%   |
| 2.01-3.0    | 13       | 3.23%   |
| 64.01-256.0 | 10       | 2.48%   |
| 24.01-32.0  | 7        | 1.74%   |
| 0.51-1.0    | 1        | 0.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 169      | 38.67%  |
| 2.01-3.0   | 87       | 19.91%  |
| 4.01-8.0   | 69       | 15.79%  |
| 3.01-4.0   | 45       | 10.3%   |
| 0.51-1.0   | 33       | 7.55%   |
| 8.01-16.0  | 20       | 4.58%   |
| 0.01-0.5   | 6        | 1.37%   |
| 24.01-32.0 | 3        | 0.69%   |
| 16.01-24.0 | 3        | 0.69%   |
| 32.01-64.0 | 1        | 0.23%   |
| Unknown    | 1        | 0.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 153      | 37.97%  |
| 2      | 127      | 31.51%  |
| 3      | 62       | 15.38%  |
| 4      | 34       | 8.44%   |
| 5      | 9        | 2.23%   |
| 0      | 7        | 1.74%   |
| 6      | 6        | 1.49%   |
| 10     | 2        | 0.5%    |
| 7      | 2        | 0.5%    |
| 8      | 1        | 0.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 211      | 53.83%  |
| Yes       | 181      | 46.17%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 388      | 99.74%  |
| No        | 1        | 0.26%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 254      | 63.98%  |
| Yes       | 143      | 36.02%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 317      | 79.85%  |
| Yes       | 80       | 20.15%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| Portugal | 389      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Lisbon                  | 89       | 21.87%  |
| Porto                   | 30       | 7.37%   |
| Braga                   | 13       | 3.19%   |
| Leiria                  | 11       | 2.7%    |
| Coimbra                 | 10       | 2.46%   |
| Setúbal                | 8        | 1.97%   |
| Aveiro                  | 8        | 1.97%   |
| Faro                    | 7        | 1.72%   |
| Amadora                 | 7        | 1.72%   |
| Vila Nova de Gaia       | 6        | 1.47%   |
| Portimao                | 6        | 1.47%   |
| Amora                   | 6        | 1.47%   |
| Torres Vedras           | 5        | 1.23%   |
| Povoa de Santa Iria     | 5        | 1.23%   |
| Evora                   | 5        | 1.23%   |
| Sintra                  | 4        | 0.98%   |
| Sao Domingos de Rana    | 4        | 0.98%   |
| Quinta Do Conde         | 4        | 0.98%   |
| Mafra                   | 4        | 0.98%   |
| Guimaraes               | 4        | 0.98%   |
| Vila do Conde           | 3        | 0.74%   |
| Trofa                   | 3        | 0.74%   |
| Senhora da Hora         | 3        | 0.74%   |
| Ponta Delgada           | 3        | 0.74%   |
| Montijo                 | 3        | 0.74%   |
| Matosinhos Municipality | 3        | 0.74%   |
| Loures                  | 3        | 0.74%   |
| Covilha                 | 3        | 0.74%   |
| Chaves                  | 3        | 0.74%   |
| Cascais                 | 3        | 0.74%   |
| Barreiro                | 3        | 0.74%   |
| Baixa da Banheira       | 3        | 0.74%   |
| Azeitao                 | 3        | 0.74%   |
| Viseu                   | 2        | 0.49%   |
| Vila Nova de Famalicao  | 2        | 0.49%   |
| Vila Caiz               | 2        | 0.49%   |
| Tomar                   | 2        | 0.49%   |
| Seia                    | 2        | 0.49%   |
| Sao Joao da Madeira     | 2        | 0.49%   |
| Ramada                  | 2        | 0.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| WDC                          | 136      | 242    | 19.37%  |
| Seagate                      | 112      | 169    | 15.95%  |
| Samsung Electronics          | 99       | 156    | 14.1%   |
| Kingston                     | 81       | 117    | 11.54%  |
| Toshiba                      | 51       | 88     | 7.26%   |
| Hitachi                      | 33       | 41     | 4.7%    |
| Crucial                      | 31       | 42     | 4.42%   |
| SanDisk                      | 18       | 23     | 2.56%   |
| Maxtor                       | 17       | 24     | 2.42%   |
| Unknown                      | 9        | 11     | 1.28%   |
| PNY                          | 8        | 12     | 1.14%   |
| BlueRay                      | 8        | 8      | 1.14%   |
| Phison                       | 7        | 13     | 1%      |
| GOODRAM                      | 7        | 9      | 1%      |
| KIOXIA-EXCERIA               | 6        | 7      | 0.85%   |
| Intel                        | 5        | 7      | 0.71%   |
| Hewlett-Packard              | 5        | 6      | 0.71%   |
| KIOXIA                       | 4        | 6      | 0.57%   |
| HGST                         | 4        | 9      | 0.57%   |
| ExcelStor                    | 4        | 4      | 0.57%   |
| China                        | 4        | 4      | 0.57%   |
| Phison Electronics           | 3        | 4      | 0.43%   |
| Fujitsu                      | 3        | 3      | 0.43%   |
| A-DATA Technology            | 3        | 3      | 0.43%   |
| XPG                          | 2        | 3      | 0.28%   |
| Vaseky                       | 2        | 2      | 0.28%   |
| SK hynix                     | 2        | 2      | 0.28%   |
| S3+                          | 2        | 2      | 0.28%   |
| OCZ                          | 2        | 2      | 0.28%   |
| Micron/Crucial Technology    | 2        | 3      | 0.28%   |
| KingDian                     | 2        | 5      | 0.28%   |
| Gigabyte Technology          | 2        | 2      | 0.28%   |
| Emtec                        | 2        | 2      | 0.28%   |
| 2-Power                      | 2        | 3      | 0.28%   |
| Zheino                       | 1        | 2      | 0.14%   |
| Transcend                    | 1        | 1      | 0.14%   |
| Team                         | 1        | 1      | 0.14%   |
| T-FORCE                      | 1        | 2      | 0.14%   |
| Shenzhen Longsys Electronics | 1        | 2      | 0.14%   |
| S3SSDE25                     | 1        | 1      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 21       | 2.67%   |
| Seagate ST1000DM010-2EP102 1TB                      | 14       | 1.78%   |
| Kingston SA400S37120G 120GB SSD                     | 11       | 1.4%    |
| Seagate ST3500418AS 500GB                           | 10       | 1.27%   |
| Kingston SV300S37A240G 240GB SSD                    | 9        | 1.15%   |
| Samsung SSD 850 EVO 250GB                           | 8        | 1.02%   |
| Toshiba HDWD110 1TB                                 | 7        | 0.89%   |
| Kingston SV300S37A120G 120GB SSD                    | 7        | 0.89%   |
| Kingston SUV400S37120G 120GB SSD                    | 7        | 0.89%   |
| Seagate ST2000DM008-2FR102 2TB                      | 6        | 0.76%   |
| Samsung SSD 860 EVO 500GB                           | 5        | 0.64%   |
| Samsung SSD 840 EVO 250GB                           | 5        | 0.64%   |
| Samsung HD161HJ 160GB                               | 5        | 0.64%   |
| Samsung HD103UJ 1TB                                 | 5        | 0.64%   |
| Kingston SA400S37480G 480GB SSD                     | 5        | 0.64%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 4        | 0.51%   |
| WDC WD3200AAJS-00L7A0 320GB                         | 4        | 0.51%   |
| WDC WD20EARX-00PASB0 2TB                            | 4        | 0.51%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 4        | 0.51%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 4        | 0.51%   |
| Toshiba DT01ACA100 1TB                              | 4        | 0.51%   |
| Toshiba DT01ACA050 500GB                            | 4        | 0.51%   |
| Seagate ST3250820AS 250GB                           | 4        | 0.51%   |
| Samsung SSD 840 Series 120GB                        | 4        | 0.51%   |
| Samsung NVMe SSD Drive 500GB                        | 4        | 0.51%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 4        | 0.51%   |
| Samsung HD502IJ 500GB                               | 4        | 0.51%   |
| Samsung HD502HJ 500GB                               | 4        | 0.51%   |
| Samsung HD252HJ 250GB                               | 4        | 0.51%   |
| Samsung HD160JJ 160GB                               | 4        | 0.51%   |
| Samsung HD103SJ 1TB                                 | 4        | 0.51%   |
| Maxtor 6L200M0 208GB                                | 4        | 0.51%   |
| Kingston SA400S37960G 960GB SSD                     | 4        | 0.51%   |
| Hitachi HDP725050GLA360 500GB                       | 4        | 0.51%   |
| Crucial CT500MX500SSD1 500GB                        | 4        | 0.51%   |
| Crucial CT240BX500SSD1 240GB                        | 4        | 0.51%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 3        | 0.38%   |
| WDC WD5000AAKX-60U6AA0 500GB                        | 3        | 0.38%   |
| WDC WD20EZRX-00D8PB0 2TB                            | 3        | 0.38%   |
| WDC WD10EZEX-00KUWA0 1TB                            | 3        | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 117      | 200    | 31.12%  |
| Seagate             | 109      | 166    | 28.99%  |
| Toshiba             | 44       | 73     | 11.7%   |
| Samsung Electronics | 43       | 64     | 11.44%  |
| Hitachi             | 33       | 41     | 8.78%   |
| Maxtor              | 16       | 23     | 4.26%   |
| HGST                | 4        | 9      | 1.06%   |
| ExcelStor           | 4        | 4      | 1.06%   |
| Fujitsu             | 2        | 2      | 0.53%   |
| Unknown             | 1        | 1      | 0.27%   |
| Quantum             | 1        | 1      | 0.27%   |
| Hewlett-Packard     | 1        | 2      | 0.27%   |
| ASMedia             | 1        | 2      | 0.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 76       | 105    | 30.16%  |
| Samsung Electronics | 42       | 66     | 16.67%  |
| Crucial             | 29       | 40     | 11.51%  |
| WDC                 | 18       | 33     | 7.14%   |
| SanDisk             | 13       | 16     | 5.16%   |
| Toshiba             | 7        | 12     | 2.78%   |
| BlueRay             | 6        | 6      | 2.38%   |
| PNY                 | 5        | 8      | 1.98%   |
| GOODRAM             | 5        | 7      | 1.98%   |
| Unknown             | 4        | 4      | 1.59%   |
| Hewlett-Packard     | 4        | 4      | 1.59%   |
| China               | 4        | 4      | 1.59%   |
| Intel               | 3        | 4      | 1.19%   |
| A-DATA Technology   | 3        | 3      | 1.19%   |
| Vaseky              | 2        | 2      | 0.79%   |
| SK hynix            | 2        | 2      | 0.79%   |
| S3+                 | 2        | 2      | 0.79%   |
| OCZ                 | 2        | 2      | 0.79%   |
| KIOXIA-EXCERIA      | 2        | 2      | 0.79%   |
| KingDian            | 2        | 5      | 0.79%   |
| Gigabyte Technology | 2        | 2      | 0.79%   |
| Emtec               | 2        | 2      | 0.79%   |
| 2-Power             | 2        | 3      | 0.79%   |
| Zheino              | 1        | 2      | 0.4%    |
| Transcend           | 1        | 1      | 0.4%    |
| Team                | 1        | 1      | 0.4%    |
| Seagate             | 1        | 1      | 0.4%    |
| Patriot             | 1        | 1      | 0.4%    |
| Mushkin             | 1        | 1      | 0.4%    |
| Micron Technology   | 1        | 1      | 0.4%    |
| Maxtor              | 1        | 1      | 0.4%    |
| LITEON              | 1        | 1      | 0.4%    |
| JMicron Technology  | 1        | 1      | 0.4%    |
| INNOVATION IT       | 1        | 1      | 0.4%    |
| INDMEM              | 1        | 1      | 0.4%    |
| Fujitsu             | 1        | 1      | 0.4%    |
| Faspeed             | 1        | 1      | 0.4%    |
| BAITITON            | 1        | 1      | 0.4%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 279      | 588    | 49.03%  |
| SSD     | 209      | 350    | 36.73%  |
| NVMe    | 67       | 108    | 11.78%  |
| Unknown | 10       | 11     | 1.76%   |
| MMC     | 4        | 4      | 0.7%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 356      | 925    | 80.18%  |
| NVMe | 67       | 108    | 15.09%  |
| SAS  | 17       | 24     | 3.83%   |
| MMC  | 4        | 4      | 0.9%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 303      | 603    | 60.97%  |
| 0.51-1.0   | 123      | 223    | 24.75%  |
| 1.01-2.0   | 38       | 61     | 7.65%   |
| 4.01-10.0  | 13       | 19     | 2.62%   |
| 2.01-3.0   | 12       | 16     | 2.41%   |
| 3.01-4.0   | 6        | 11     | 1.21%   |
| 10.01-20.0 | 1        | 4      | 0.2%    |
| 0          | 1        | 1      | 0.2%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 112      | 26.73%  |
| 251-500        | 76       | 18.14%  |
| 501-1000       | 50       | 11.93%  |
| 1001-2000      | 35       | 8.35%   |
| 51-100         | 34       | 8.11%   |
| 1-20           | 32       | 7.64%   |
| More than 3000 | 29       | 6.92%   |
| 2001-3000      | 22       | 5.25%   |
| 21-50          | 16       | 3.82%   |
| Unknown        | 13       | 3.1%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 169      | 39.21%  |
| 21-50          | 63       | 14.62%  |
| 51-100         | 43       | 9.98%   |
| 101-250        | 41       | 9.51%   |
| 501-1000       | 30       | 6.96%   |
| 251-500        | 28       | 6.5%    |
| 1001-2000      | 25       | 5.8%    |
| Unknown        | 13       | 3.02%   |
| 2001-3000      | 10       | 2.32%   |
| More than 3000 | 9        | 2.09%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| Seagate ST3500418AS 500GB                | 3        | 3      | 4.92%   |
| WDC WD800JD-60LSA0 80GB                  | 2        | 2      | 3.28%   |
| WDC WD3200AAJS-00L7A0 320GB              | 2        | 2      | 3.28%   |
| Toshiba MK2552GSX 250GB                  | 2        | 2      | 3.28%   |
| Samsung Electronics HD252HJ 250GB        | 2        | 2      | 3.28%   |
| WDC WD6400AADS-00M2B0 640GB              | 1        | 1      | 1.64%   |
| WDC WD5000LPCX-60VHAT0 500GB             | 1        | 1      | 1.64%   |
| WDC WD5000BPVT-22HXZT1 500GB             | 1        | 1      | 1.64%   |
| WDC WD5000AZRX-00A3KB0 500GB             | 1        | 1      | 1.64%   |
| WDC WD5000AAKS-00V1A0 500GB              | 1        | 1      | 1.64%   |
| WDC WD5000AAKS-00A7B0 500GB              | 1        | 4      | 1.64%   |
| WDC WD40EFRX-68WT0N0 4TB                 | 1        | 2      | 1.64%   |
| WDC WD3200AAJS-00B4A0 320GB              | 1        | 1      | 1.64%   |
| WDC WD30EZRS-11J99B1 3TB                 | 1        | 1      | 1.64%   |
| WDC WD2500JS-40TGB0 250GB                | 1        | 1      | 1.64%   |
| WDC WD20EARS-00MVWB0 2TB                 | 1        | 1      | 1.64%   |
| WDC WD10EZRZ-00Z5HB0 1TB                 | 1        | 1      | 1.64%   |
| WDC WD10EZEX-00BN5A0 1TB                 | 1        | 1      | 1.64%   |
| WDC WD10EAVS-00D7B1 1TB                  | 1        | 1      | 1.64%   |
| WDC WD10EARS-00Y5B1 1TB                  | 1        | 1      | 1.64%   |
| WDC WD10EADS-11M2B1 1TB                  | 1        | 1      | 1.64%   |
| WDC WD1002FBYS-02A6B0 1TB                | 1        | 1      | 1.64%   |
| WDC WD1001FALS-00J7B0 1TB                | 1        | 4      | 1.64%   |
| Unknown FM-25S2S-60GBP2 64GB SSD         | 1        | 1      | 1.64%   |
| Toshiba MK3252GSX 320GB                  | 1        | 2      | 1.64%   |
| SK hynix SH920 2.5 7MM 512GB SSD         | 1        | 1      | 1.64%   |
| Seagate ST9500325AS 500GB                | 1        | 1      | 1.64%   |
| Seagate ST9250827AS 250GB                | 1        | 1      | 1.64%   |
| Seagate ST500DM002-1BD142 500GB          | 1        | 1      | 1.64%   |
| Seagate ST480HM000-1G5162 480GB          | 1        | 1      | 1.64%   |
| Seagate ST3320820AS 320GB                | 1        | 1      | 1.64%   |
| Seagate ST3250820AS 250GB                | 1        | 1      | 1.64%   |
| Seagate ST3160812AS 160GB                | 1        | 1      | 1.64%   |
| Seagate ST2000DM001-9YN164 2TB           | 1        | 1      | 1.64%   |
| Samsung Electronics SSD 840 Series 120GB | 1        | 2      | 1.64%   |
| Samsung Electronics HD501LJ 500GB        | 1        | 1      | 1.64%   |
| Samsung Electronics HD161HJ 160GB        | 1        | 1      | 1.64%   |
| Samsung Electronics HD103SI 1TB          | 1        | 1      | 1.64%   |
| Patriot Burst Elite 120GB SSD            | 1        | 1      | 1.64%   |
| Maxtor STM3320820AS 320GB                | 1        | 2      | 1.64%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 22       | 29     | 37.93%  |
| Seagate             | 9        | 11     | 15.52%  |
| Hitachi             | 6        | 6      | 10.34%  |
| Samsung Electronics | 5        | 7      | 8.62%   |
| Maxtor              | 4        | 7      | 6.9%    |
| Toshiba             | 3        | 4      | 5.17%   |
| Kingston            | 2        | 2      | 3.45%   |
| Crucial             | 2        | 2      | 3.45%   |
| Unknown             | 1        | 1      | 1.72%   |
| SK hynix            | 1        | 1      | 1.72%   |
| Patriot             | 1        | 1      | 1.72%   |
| KingDian            | 1        | 2      | 1.72%   |
| China               | 1        | 1      | 1.72%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 22       | 29     | 45.83%  |
| Seagate             | 9        | 11     | 18.75%  |
| Hitachi             | 6        | 6      | 12.5%   |
| Samsung Electronics | 4        | 5      | 8.33%   |
| Maxtor              | 4        | 7      | 8.33%   |
| Toshiba             | 3        | 4      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 44       | 62     | 81.48%  |
| SSD  | 10       | 12     | 18.52%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate ST3750640NS 752GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 271      | 737    | 62.16%  |
| Works    | 113      | 249    | 25.92%  |
| Malfunc  | 51       | 74     | 11.7%   |
| Failed   | 1        | 1      | 0.23%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 250      | 47.98%  |
| AMD                              | 115      | 22.07%  |
| Samsung Electronics              | 24       | 4.61%   |
| JMicron Technology               | 19       | 3.65%   |
| Phison Electronics               | 14       | 2.69%   |
| ASMedia Technology               | 14       | 2.69%   |
| VIA Technologies                 | 13       | 2.5%    |
| SanDisk                          | 12       | 2.3%    |
| Nvidia                           | 12       | 2.3%    |
| Marvell Technology Group         | 11       | 2.11%   |
| KIOXIA                           | 8        | 1.54%   |
| Kingston Technology Company      | 7        | 1.34%   |
| Silicon Integrated Systems [SiS] | 3        | 0.58%   |
| Shenzhen Longsys Electronics     | 3        | 0.58%   |
| Micron/Crucial Technology        | 3        | 0.58%   |
| LSI Logic / Symbios Logic        | 3        | 0.58%   |
| ADATA Technology                 | 3        | 0.58%   |
| Adaptec                          | 2        | 0.38%   |
| ULi Electronics                  | 1        | 0.19%   |
| Toshiba America Info Systems     | 1        | 0.19%   |
| Realtek Semiconductor            | 1        | 0.19%   |
| Micron Technology                | 1        | 0.19%   |
| Hewlett-Packard                  | 1        | 0.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 53       | 7.57%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 41       | 5.86%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 35       | 5%      |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 25       | 3.57%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 21       | 3%      |
| AMD 500 Series Chipset SATA Controller                                                  | 21       | 3%      |
| AMD 400 Series Chipset SATA Controller                                                  | 21       | 3%      |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 20       | 2.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 17       | 2.43%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 16       | 2.29%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 16       | 2.29%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 14       | 2%      |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 13       | 1.86%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 12       | 1.71%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 12       | 1.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 12       | 1.71%   |
| Phison E12 NVMe Controller                                                              | 11       | 1.57%   |
| Intel SATA Controller [RAID mode]                                                       | 11       | 1.57%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 11       | 1.57%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 10       | 1.43%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 9        | 1.29%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 9        | 1.29%   |
| AMD 300 Series Chipset SATA Controller                                                  | 9        | 1.29%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 7        | 1%      |
| VIA VT6415 PATA IDE Host Controller                                                     | 6        | 0.86%   |
| Nvidia MCP61 SATA Controller                                                            | 6        | 0.86%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 6        | 0.86%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 6        | 0.86%   |
| AMD FCH SATA Controller D                                                               | 6        | 0.86%   |
| KIOXIA NVMe SSD                                                                         | 5        | 0.71%   |
| JMicron JMB368 IDE controller                                                           | 5        | 0.71%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 5        | 0.71%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 5        | 0.71%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 5        | 0.71%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 5        | 0.71%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 4        | 0.57%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 0.57%   |
| Nvidia MCP61 IDE                                                                        | 4        | 0.57%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 4        | 0.57%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 4        | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 266      | 51.55%  |
| IDE  | 153      | 29.65%  |
| NVMe | 68       | 13.18%  |
| RAID | 25       | 4.84%   |
| SCSI | 3        | 0.58%   |
| SAS  | 1        | 0.19%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 268      | 68.89%  |
| AMD    | 121      | 31.11%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 7        | 1.79%   |
| AMD Ryzen 5 3600 6-Core Processor           | 7        | 1.79%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 7        | 1.79%   |
| Intel Pentium 4 CPU 3.00GHz                 | 6        | 1.53%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 6        | 1.53%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 6        | 1.53%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 6        | 1.53%   |
| AMD FX-8320 Eight-Core Processor            | 6        | 1.53%   |
| AMD FX-6300 Six-Core Processor              | 6        | 1.53%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 5        | 1.28%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 5        | 1.28%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 5        | 1.28%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 5        | 1.28%   |
| Intel Pentium D CPU 3.00GHz                 | 4        | 1.02%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 4        | 1.02%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 4        | 1.02%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 4        | 1.02%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 3        | 0.77%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 3        | 0.77%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 3        | 0.77%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 3        | 0.77%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3        | 0.77%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 3        | 0.77%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 3        | 0.77%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 3        | 0.77%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 3        | 0.77%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 3        | 0.77%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 3        | 0.77%   |
| Intel Core 2 Duo CPU E8600 @ 3.33GHz        | 3        | 0.77%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 3        | 0.77%   |
| Intel Core 2 CPU 6300 @ 1.86GHz             | 3        | 0.77%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 3        | 0.77%   |
| Intel 11th Gen Core i5-11600 @ 2.80GHz      | 3        | 0.77%   |
| AMD Ryzen 7 5800X3D 8-Core Processor        | 3        | 0.77%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 3        | 0.77%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 3        | 0.77%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 3        | 0.77%   |
| AMD FX-8350 Eight-Core Processor            | 3        | 0.77%   |
| Intel Xeon CPU X3470 @ 2.93GHz              | 2        | 0.51%   |
| Intel Xeon CPU E5345 @ 2.33GHz              | 2        | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 62       | 15.86%  |
| Intel Core i7           | 37       | 9.46%   |
| AMD Ryzen 5             | 36       | 9.21%   |
| Intel Core i3           | 25       | 6.39%   |
| AMD FX                  | 25       | 6.39%   |
| Intel Xeon              | 21       | 5.37%   |
| Intel Core 2 Quad       | 21       | 5.37%   |
| AMD Ryzen 7             | 21       | 5.37%   |
| Intel Pentium Dual-Core | 15       | 3.84%   |
| Intel Core 2 Duo        | 14       | 3.58%   |
| Intel Pentium 4         | 13       | 3.32%   |
| Intel Pentium           | 11       | 2.81%   |
| Intel Core 2            | 10       | 2.56%   |
| Other                   | 9        | 2.3%    |
| Intel Celeron           | 9        | 2.3%    |
| Intel Atom              | 7        | 1.79%   |
| Intel Pentium D         | 6        | 1.53%   |
| Intel Pentium Dual      | 5        | 1.28%   |
| AMD Ryzen 3             | 5        | 1.28%   |
| AMD A10                 | 4        | 1.02%   |
| AMD Athlon II X3        | 3        | 0.77%   |
| AMD Athlon II X2        | 3        | 0.77%   |
| AMD Athlon 64           | 3        | 0.77%   |
| Intel Pentium Gold      | 2        | 0.51%   |
| Intel Core i9           | 2        | 0.51%   |
| AMD Ryzen Threadripper  | 2        | 0.51%   |
| AMD Ryzen 9             | 2        | 0.51%   |
| AMD E                   | 2        | 0.51%   |
| AMD Athlon              | 2        | 0.51%   |
| AMD A6                  | 2        | 0.51%   |
| Intel Pentium Silver    | 1        | 0.26%   |
| Intel Genuine           | 1        | 0.26%   |
| AMD Sempron             | 1        | 0.26%   |
| AMD Ryzen 7 PRO         | 1        | 0.26%   |
| AMD Phenom II X6        | 1        | 0.26%   |
| AMD Phenom II X4        | 1        | 0.26%   |
| AMD Phenom II X3        | 1        | 0.26%   |
| AMD Phenom              | 1        | 0.26%   |
| AMD Athlon Dual Core    | 1        | 0.26%   |
| AMD Athlon 64 X2        | 1        | 0.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 152      | 38.78%  |
| 2       | 111      | 28.32%  |
| 6       | 50       | 12.76%  |
| 8       | 33       | 8.42%   |
| 1       | 23       | 5.87%   |
| 3       | 13       | 3.32%   |
| 16      | 3        | 0.77%   |
| 12      | 3        | 0.77%   |
| 10      | 2        | 0.51%   |
| 24      | 1        | 0.26%   |
| Unknown | 1        | 0.26%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 383      | 98.46%  |
| 2      | 6        | 1.54%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 199      | 50.9%   |
| 2       | 191      | 48.85%  |
| Unknown | 1        | 0.26%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 375      | 94.94%  |
| Unknown        | 15       | 3.8%    |
| 32-bit         | 4        | 1.01%   |
| 64-bit         | 1        | 0.25%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 100      | 24.39%  |
| 0x1067a    | 28       | 6.83%   |
| 0x306c3    | 22       | 5.37%   |
| 0x206a7    | 21       | 5.12%   |
| 0x306a9    | 20       | 4.88%   |
| 0x06000852 | 15       | 3.66%   |
| 0x506e3    | 14       | 3.41%   |
| 0x08701021 | 12       | 2.93%   |
| 0x906ea    | 11       | 2.68%   |
| 0x0800820d | 11       | 2.68%   |
| 0x6fb      | 10       | 2.44%   |
| 0x906e9    | 8        | 1.95%   |
| 0x10676    | 6        | 1.46%   |
| 0x106e5    | 5        | 1.22%   |
| 0x10677    | 5        | 1.22%   |
| 0xf43      | 4        | 0.98%   |
| 0xf41      | 4        | 0.98%   |
| 0xa0671    | 4        | 0.98%   |
| 0xa0655    | 4        | 0.98%   |
| 0x6fd      | 4        | 0.98%   |
| 0x6f6      | 4        | 0.98%   |
| 0x6f2      | 4        | 0.98%   |
| 0x010000c8 | 4        | 0.98%   |
| 0xf65      | 3        | 0.73%   |
| 0x906eb    | 3        | 0.73%   |
| 0x406c4    | 3        | 0.73%   |
| 0x30678    | 3        | 0.73%   |
| 0x206d7    | 3        | 0.73%   |
| 0x08101016 | 3        | 0.73%   |
| 0x06000822 | 3        | 0.73%   |
| 0xf64      | 2        | 0.49%   |
| 0xf62      | 2        | 0.49%   |
| 0xf4a      | 2        | 0.49%   |
| 0xf34      | 2        | 0.49%   |
| 0x906ec    | 2        | 0.49%   |
| 0x6f7      | 2        | 0.49%   |
| 0x30661    | 2        | 0.49%   |
| 0x20652    | 2        | 0.49%   |
| 0x0a20120a | 2        | 0.49%   |
| 0x0a201205 | 2        | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Penryn           | 46       | 11.76%  |
| Haswell          | 34       | 8.7%    |
| KabyLake         | 30       | 7.67%   |
| Core             | 30       | 7.67%   |
| SandyBridge      | 24       | 6.14%   |
| Piledriver       | 23       | 5.88%   |
| IvyBridge        | 22       | 5.63%   |
| NetBurst         | 21       | 5.37%   |
| Zen 2            | 20       | 5.12%   |
| Skylake          | 20       | 5.12%   |
| Zen+             | 19       | 4.86%   |
| Zen              | 16       | 4.09%   |
| Zen 3            | 14       | 3.58%   |
| K10              | 12       | 3.07%   |
| Silvermont       | 8        | 2.05%   |
| CometLake        | 8        | 2.05%   |
| Nehalem          | 7        | 1.79%   |
| Westmere         | 5        | 1.28%   |
| K8 Hammer        | 5        | 1.28%   |
| Icelake          | 4        | 1.02%   |
| Excavator        | 4        | 1.02%   |
| Unknown          | 4        | 1.02%   |
| Steamroller      | 3        | 0.77%   |
| Bulldozer        | 3        | 0.77%   |
| Bonnell          | 3        | 0.77%   |
| Bobcat           | 2        | 0.51%   |
| Puma             | 1        | 0.26%   |
| Goldmont plus    | 1        | 0.26%   |
| Goldmont         | 1        | 0.26%   |
| Alderlake Hybrid | 1        | 0.26%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Nvidia                           | 149      | 35.9%   |
| AMD                              | 137      | 33.01%  |
| Intel                            | 124      | 29.88%  |
| Silicon Integrated Systems [SiS] | 2        | 0.48%   |
| Matrox Electronics Systems       | 2        | 0.48%   |
| ASPEED Technology                | 1        | 0.24%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 26       | 6.07%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 18       | 4.21%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 15       | 3.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 15       | 3.5%    |
| Nvidia GT218 [GeForce 210]                                                               | 11       | 2.57%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 11       | 2.57%   |
| Intel HD Graphics 530                                                                    | 10       | 2.34%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 10       | 2.34%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10       | 2.34%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 7        | 1.64%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 7        | 1.64%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 6        | 1.4%    |
| Nvidia GM204 [GeForce GTX 970]                                                           | 5        | 1.17%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5        | 1.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5        | 1.17%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 5        | 1.17%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5        | 1.17%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 5        | 1.17%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 4        | 0.93%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 4        | 0.93%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 4        | 0.93%   |
| AMD RS780L [Radeon 3000]                                                                 | 4        | 0.93%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 4        | 0.93%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 4        | 0.93%   |
| AMD Caicos PRO [Radeon HD 7450]                                                          | 4        | 0.93%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 3        | 0.7%    |
| Nvidia GT216 [GeForce 315]                                                               | 3        | 0.7%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 3        | 0.7%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 3        | 0.7%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 3        | 0.7%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 3        | 0.7%    |
| Nvidia GK106 [GeForce GTX 660]                                                           | 3        | 0.7%    |
| Nvidia GF119 [GeForce GT 610]                                                            | 3        | 0.7%    |
| Nvidia GF108 [GeForce GT 730]                                                            | 3        | 0.7%    |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                                        | 3        | 0.7%    |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 3        | 0.7%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3        | 0.7%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3        | 0.7%    |
| AMD RV730 PRO [Radeon HD 4650]                                                           | 3        | 0.7%    |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 3        | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 142      | 35.86%  |
| 1 x AMD         | 127      | 32.07%  |
| 1 x Intel       | 109      | 27.53%  |
| 2 x AMD         | 7        | 1.77%   |
| 2 x Nvidia      | 2        | 0.51%   |
| 1 x SiS         | 2        | 0.51%   |
| AMD + Nvidia    | 2        | 0.51%   |
| Nvidia + Matrox | 1        | 0.25%   |
| Nvidia + ASPEED | 1        | 0.25%   |
| 1 x Matrox      | 1        | 0.25%   |
| Intel + Nvidia  | 1        | 0.25%   |
| Intel + AMD     | 1        | 0.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 291      | 73.48%  |
| Proprietary | 87       | 21.97%  |
| Unknown     | 18       | 4.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 173      | 42.82%  |
| 0.01-0.5   | 54       | 13.37%  |
| 1.01-2.0   | 52       | 12.87%  |
| 0.51-1.0   | 50       | 12.38%  |
| 3.01-4.0   | 34       | 8.42%   |
| 7.01-8.0   | 25       | 6.19%   |
| 8.01-16.0  | 7        | 1.73%   |
| 5.01-6.0   | 6        | 1.49%   |
| 2.01-3.0   | 3        | 0.74%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 77       | 18.83%  |
| Goldstar             | 67       | 16.38%  |
| Hewlett-Packard      | 52       | 12.71%  |
| Ancor Communications | 51       | 12.47%  |
| Dell                 | 20       | 4.89%   |
| AOC                  | 18       | 4.4%    |
| BenQ                 | 16       | 3.91%   |
| Philips              | 13       | 3.18%   |
| ASUSTek Computer     | 10       | 2.44%   |
| LG Electronics       | 9        | 2.2%    |
| Acer                 | 9        | 2.2%    |
| Sony                 | 8        | 1.96%   |
| Unknown              | 7        | 1.71%   |
| Lenovo               | 6        | 1.47%   |
| Fujitsu Siemens      | 4        | 0.98%   |
| ViewSonic            | 3        | 0.73%   |
| HPN                  | 3        | 0.73%   |
| Apple                | 3        | 0.73%   |
| ___                  | 2        | 0.49%   |
| Vestel Elektronik    | 2        | 0.49%   |
| Mi                   | 2        | 0.49%   |
| Gigabyte Technology  | 2        | 0.49%   |
| AVX                  | 2        | 0.49%   |
| AUS                  | 2        | 0.49%   |
| Vestel               | 1        | 0.24%   |
| Toshiba              | 1        | 0.24%   |
| TEO                  | 1        | 0.24%   |
| TCL                  | 1        | 0.24%   |
| Targa Visionary      | 1        | 0.24%   |
| TAR                  | 1        | 0.24%   |
| RTK                  | 1        | 0.24%   |
| NEC Computers        | 1        | 0.24%   |
| MSI                  | 1        | 0.24%   |
| Lenovo Group Limited | 1        | 0.24%   |
| KOC                  | 1        | 0.24%   |
| Iiyama               | 1        | 0.24%   |
| IBM                  | 1        | 0.24%   |
| HXF                  | 1        | 0.24%   |
| HUAWEI               | 1        | 0.24%   |
| HJW                  | 1        | 0.24%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                | 4        | 0.92%   |
| Ancor Communications VX238 ACI23C1 1920x1080 510x290mm 23.1-inch      | 4        | 0.92%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 4        | 0.92%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 3        | 0.69%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 3        | 0.69%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch | 3        | 0.69%   |
| Goldstar M227WD GSM56D5 1920x1080 480x270mm 21.7-inch                 | 3        | 0.69%   |
| Goldstar L1919S GSM4AF0 1280x1024 376x301mm 19.0-inch                 | 3        | 0.69%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 3        | 0.69%   |
| Goldstar FULL HD GSM5AB9 1920x1080 480x270mm 21.7-inch                | 3        | 0.69%   |
| BenQ GW2480 BNQ78E7 1920x1080 530x300mm 24.0-inch                     | 3        | 0.69%   |
| Ancor Communications VX228 ACI22C1 1920x1080 476x268mm 21.5-inch      | 3        | 0.69%   |
| Ancor Communications VE228 ACI22FA 1920x1080 477x268mm 21.5-inch      | 3        | 0.69%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch | 3        | 0.69%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 520x290mm 23.4-inch | 3        | 0.69%   |
| Ancor Communications ASUS VS197 ACI19F2 1366x768 410x230mm 18.5-inch  | 3        | 0.69%   |
| Acer KA270H ACR0522 1920x1080 598x336mm 27.0-inch                     | 3        | 0.69%   |
| ___ LCDTV16 ___0101 1360x768                                          | 2        | 0.46%   |
| Vestel Elektronik 50FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 2        | 0.46%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 2        | 0.46%   |
| Sony SDM-HX73 SNY2870 1280x1024 338x270mm 17.0-inch                   | 2        | 0.46%   |
| Sony SDM-HS93 SNY1190 1280x1024 357x286mm 18.0-inch                   | 2        | 0.46%   |
| Samsung Electronics SyncMaster SAM03F0 1680x1050 470x300mm 22.0-inch  | 2        | 0.46%   |
| Samsung Electronics SyncMaster SAM037A 1680x1050 433x271mm 20.1-inch  | 2        | 0.46%   |
| Samsung Electronics SyncMaster SAM0301 1680x1050 459x296mm 21.5-inch  | 2        | 0.46%   |
| Samsung Electronics SyncMaster SAM0230 1280x1024 376x301mm 19.0-inch  | 2        | 0.46%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch      | 2        | 0.46%   |
| Samsung Electronics LCD Monitor SyncMaster 1440x900                   | 2        | 0.46%   |
| Samsung Electronics LCD Monitor SAM0992 1920x1080 890x500mm 40.2-inch | 2        | 0.46%   |
| Philips 170S PHL082B 1280x1024 338x270mm 17.0-inch                    | 2        | 0.46%   |
| Philips 170S PHL081E 1280x1024 338x270mm 17.0-inch                    | 2        | 0.46%   |
| Lenovo Q24i-10 LEN65F3 1920x1080 527x296mm 23.8-inch                  | 2        | 0.46%   |
| Hewlett-Packard w2408 HWP26CF 1920x1200 518x324mm 24.1-inch           | 2        | 0.46%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch            | 2        | 0.46%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch          | 2        | 0.46%   |
| Hewlett-Packard L1950 HWP26E7 1280x1024 380x300mm 19.1-inch           | 2        | 0.46%   |
| Hewlett-Packard L1706 HWP265C 1280x1024 337x270mm 17.0-inch           | 2        | 0.46%   |
| Hewlett-Packard Compaq WF1907 HWP26A4 1440x900 408x255mm 18.9-inch    | 2        | 0.46%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch             | 2        | 0.46%   |
| Hewlett-Packard 23xw HWP318B 1920x1080 509x286mm 23.0-inch            | 2        | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 179      | 44.42%  |
| 1280x1024 (SXGA)   | 58       | 14.39%  |
| 3840x2160 (4K)     | 35       | 8.68%   |
| 1680x1050 (WSXGA+) | 21       | 5.21%   |
| 1440x900 (WXGA+)   | 19       | 4.71%   |
| 2560x1440 (QHD)    | 18       | 4.47%   |
| 1366x768 (WXGA)    | 16       | 3.97%   |
| 1600x900 (HD+)     | 10       | 2.48%   |
| 1920x1200 (WUXGA)  | 9        | 2.23%   |
| 1360x768           | 7        | 1.74%   |
| Unknown            | 7        | 1.74%   |
| 2560x1080          | 4        | 0.99%   |
| 1024x768 (XGA)     | 4        | 0.99%   |
| 3840x1080          | 3        | 0.74%   |
| 3440x1440          | 3        | 0.74%   |
| 1152x864           | 3        | 0.74%   |
| 4480x1600          | 1        | 0.25%   |
| 3360x1080          | 1        | 0.25%   |
| 3360x1050          | 1        | 0.25%   |
| 2944x1080          | 1        | 0.25%   |
| 2560x2520          | 1        | 0.25%   |
| 1920x540           | 1        | 0.25%   |
| 1400x1050          | 1        | 0.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 61       | 14.84%  |
| 24      | 52       | 12.65%  |
| 23      | 45       | 10.95%  |
| Unknown | 44       | 10.71%  |
| 27      | 36       | 8.76%   |
| 19      | 36       | 8.76%   |
| 17      | 30       | 7.3%    |
| 18      | 23       | 5.6%    |
| 20      | 15       | 3.65%   |
| 15      | 11       | 2.68%   |
| 31      | 10       | 2.43%   |
| 22      | 8        | 1.95%   |
| 84      | 7        | 1.7%    |
| 54      | 5        | 1.22%   |
| 34      | 5        | 1.22%   |
| 72      | 3        | 0.73%   |
| 33      | 3        | 0.73%   |
| 32      | 3        | 0.73%   |
| 46      | 2        | 0.49%   |
| 40      | 2        | 0.49%   |
| 28      | 2        | 0.49%   |
| 25      | 2        | 0.49%   |
| 58      | 1        | 0.24%   |
| 48      | 1        | 0.24%   |
| 42      | 1        | 0.24%   |
| 39      | 1        | 0.24%   |
| 26      | 1        | 0.24%   |
| 16      | 1        | 0.24%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 122      | 30.5%   |
| 401-500     | 118      | 29.5%   |
| Unknown     | 44       | 11%     |
| 301-350     | 42       | 10.5%   |
| 351-400     | 23       | 5.75%   |
| 601-700     | 17       | 4.25%   |
| 701-800     | 11       | 2.75%   |
| 1501-2000   | 10       | 2.5%    |
| 1001-1500   | 9        | 2.25%   |
| 801-900     | 3        | 0.75%   |
| 901-1000    | 1        | 0.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 227      | 59.11%  |
| 5/4     | 49       | 12.76%  |
| 16/10   | 41       | 10.68%  |
| Unknown | 40       | 10.42%  |
| 4/3     | 14       | 3.65%   |
| 21/9    | 6        | 1.56%   |
| 6/5     | 3        | 0.78%   |
| 3/2     | 3        | 0.78%   |
| 32/9    | 1        | 0.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 142      | 35.15%  |
| 151-200        | 63       | 15.59%  |
| 141-150        | 49       | 12.13%  |
| Unknown        | 44       | 10.89%  |
| 301-350        | 37       | 9.16%   |
| 351-500        | 21       | 5.2%    |
| More than 1000 | 17       | 4.21%   |
| 251-300        | 13       | 3.22%   |
| 111-120        | 6        | 1.49%   |
| 501-1000       | 6        | 1.49%   |
| 101-110        | 5        | 1.24%   |
| 131-140        | 1        | 0.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 238      | 61.5%   |
| 101-120 | 77       | 19.9%   |
| Unknown | 44       | 11.37%  |
| 1-50    | 12       | 3.1%    |
| 121-160 | 12       | 3.1%    |
| 161-240 | 4        | 1.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 313      | 78.05%  |
| 2     | 54       | 13.47%  |
| 0     | 27       | 6.73%   |
| 3     | 6        | 1.5%    |
| 4     | 1        | 0.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 243      | 46.82%  |
| Intel                            | 109      | 21%     |
| Qualcomm Atheros                 | 50       | 9.63%   |
| TP-Link                          | 16       | 3.08%   |
| Broadcom                         | 15       | 2.89%   |
| Qualcomm Atheros Communications  | 13       | 2.5%    |
| Nvidia                           | 12       | 2.31%   |
| Ralink Technology                | 8        | 1.54%   |
| Marvell Technology Group         | 6        | 1.16%   |
| VIA Technologies                 | 5        | 0.96%   |
| D-Link                           | 5        | 0.96%   |
| Silicon Integrated Systems [SiS] | 3        | 0.58%   |
| Samsung Electronics              | 3        | 0.58%   |
| Ralink                           | 3        | 0.58%   |
| Edimax Technology                | 3        | 0.58%   |
| Broadcom Limited                 | 3        | 0.58%   |
| ASUSTek Computer                 | 3        | 0.58%   |
| D-Link System                    | 2        | 0.39%   |
| ADMtek                           | 2        | 0.39%   |
| Accton Technology                | 2        | 0.39%   |
| TRENDnet                         | 1        | 0.19%   |
| Smart Link                       | 1        | 0.19%   |
| Sitecom Europe                   | 1        | 0.19%   |
| Motorola                         | 1        | 0.19%   |
| Microsoft                        | 1        | 0.19%   |
| Mellanox Technologies            | 1        | 0.19%   |
| MediaTek                         | 1        | 0.19%   |
| Linksys                          | 1        | 0.19%   |
| Dresden Elektronik               | 1        | 0.19%   |
| dog hunter                       | 1        | 0.19%   |
| Belkin Components                | 1        | 0.19%   |
| ASIX Electronics                 | 1        | 0.19%   |
| Apple                            | 1        | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 202      | 35.07%  |
| Intel I211 Gigabit Network Connection                             | 15       | 2.6%    |
| Realtek RTL8125 2.5GbE Controller                                 | 14       | 2.43%   |
| Qualcomm Atheros AR9271 802.11n                                   | 11       | 1.91%   |
| Intel Ethernet Connection (2) I219-V                              | 9        | 1.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9        | 1.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8        | 1.39%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 7        | 1.22%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7        | 1.22%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 7        | 1.22%   |
| Intel Ethernet Connection (2) I218-V                              | 7        | 1.22%   |
| Intel 82579V Gigabit Network Connection                           | 7        | 1.22%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 6        | 1.04%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 6        | 1.04%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 6        | 1.04%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6        | 1.04%   |
| Nvidia MCP61 Ethernet                                             | 6        | 1.04%   |
| Intel Wi-Fi 6 AX200                                               | 6        | 1.04%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 6        | 1.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5        | 0.87%   |
| Ralink MT7601U Wireless Adapter                                   | 5        | 0.87%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 5        | 0.87%   |
| Intel Ethernet Connection (7) I219-V                              | 5        | 0.87%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 4        | 0.69%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 4        | 0.69%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 4        | 0.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4        | 0.69%   |
| Intel Wireless 7265                                               | 4        | 0.69%   |
| Intel Ethernet Connection I217-LM                                 | 4        | 0.69%   |
| Intel Ethernet Connection (2) I219-LM                             | 4        | 0.69%   |
| Intel Ethernet Connection (14) I219-V                             | 4        | 0.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4        | 0.69%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 4        | 0.69%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 0.52%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 0.52%   |
| Nvidia MCP73 Ethernet                                             | 3        | 0.52%   |
| Intel Ethernet Controller I225-V                                  | 3        | 0.52%   |
| Intel 82566DM Gigabit Network Connection                          | 3        | 0.52%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 3        | 0.52%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 2        | 0.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 38       | 26.03%  |
| Qualcomm Atheros                | 24       | 16.44%  |
| Intel                           | 24       | 16.44%  |
| TP-Link                         | 15       | 10.27%  |
| Qualcomm Atheros Communications | 13       | 8.9%    |
| Ralink Technology               | 8        | 5.48%   |
| D-Link                          | 5        | 3.42%   |
| Ralink                          | 3        | 2.05%   |
| Edimax Technology               | 3        | 2.05%   |
| ASUSTek Computer                | 3        | 2.05%   |
| Broadcom                        | 2        | 1.37%   |
| TRENDnet                        | 1        | 0.68%   |
| Sitecom Europe                  | 1        | 0.68%   |
| Microsoft                       | 1        | 0.68%   |
| MediaTek                        | 1        | 0.68%   |
| Linksys                         | 1        | 0.68%   |
| Broadcom Limited                | 1        | 0.68%   |
| Belkin Components               | 1        | 0.68%   |
| Accton Technology               | 1        | 0.68%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9271 802.11n                                                      | 11       | 7.48%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 7        | 4.76%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                          | 6        | 4.08%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 6        | 4.08%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                     | 6        | 4.08%   |
| Intel Wi-Fi 6 AX200                                                                  | 6        | 4.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 5        | 3.4%    |
| Ralink MT7601U Wireless Adapter                                                      | 5        | 3.4%    |
| Realtek RTL8188EE Wireless Network Adapter                                           | 4        | 2.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 4        | 2.72%   |
| Intel Wireless 7265                                                                  | 4        | 2.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 4        | 2.72%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                  | 2        | 1.36%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                         | 2        | 1.36%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                           | 2        | 1.36%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                   | 2        | 1.36%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                             | 2        | 1.36%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                      | 2        | 1.36%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                             | 2        | 1.36%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 2        | 1.36%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                     | 2        | 1.36%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                       | 2        | 1.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 2        | 1.36%   |
| Intel Wireless-AC 9260                                                               | 2        | 1.36%   |
| Intel Wireless 3160                                                                  | 2        | 1.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 2        | 1.36%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                       | 2        | 1.36%   |
| TRENDnet TEW-805UB 300Mbps+867Mbps Wireless AC Adapter [Realtek RTL8812AU]           | 1        | 0.68%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                                | 1        | 0.68%   |
| TP-Link 802.11ac WLAN Adapter                                                        | 1        | 0.68%   |
| TP-Link 802.11ac NIC                                                                 | 1        | 0.68%   |
| Sitecom Europe WL-345 Wireless USB adapter 300N X3                                   | 1        | 0.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                      | 1        | 0.68%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                  | 1        | 0.68%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                               | 1        | 0.68%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)                            | 1        | 0.68%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                | 1        | 0.68%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                              | 1        | 0.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                           | 1        | 0.68%   |
| Realtek Realtek Network controller                                                   | 1        | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 230      | 55.96%  |
| Intel                            | 99       | 24.09%  |
| Qualcomm Atheros                 | 29       | 7.06%   |
| Broadcom                         | 13       | 3.16%   |
| Nvidia                           | 12       | 2.92%   |
| Marvell Technology Group         | 6        | 1.46%   |
| VIA Technologies                 | 5        | 1.22%   |
| Silicon Integrated Systems [SiS] | 3        | 0.73%   |
| Samsung Electronics              | 3        | 0.73%   |
| D-Link System                    | 2        | 0.49%   |
| Broadcom Limited                 | 2        | 0.49%   |
| ADMtek                           | 2        | 0.49%   |
| TP-Link                          | 1        | 0.24%   |
| Mellanox Technologies            | 1        | 0.24%   |
| ASIX Electronics                 | 1        | 0.24%   |
| Apple                            | 1        | 0.24%   |
| Accton Technology                | 1        | 0.24%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 202      | 47.53%  |
| Intel I211 Gigabit Network Connection                             | 15       | 3.53%   |
| Realtek RTL8125 2.5GbE Controller                                 | 14       | 3.29%   |
| Intel Ethernet Connection (2) I219-V                              | 9        | 2.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9        | 2.12%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8        | 1.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7        | 1.65%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 7        | 1.65%   |
| Intel Ethernet Connection (2) I218-V                              | 7        | 1.65%   |
| Intel 82579V Gigabit Network Connection                           | 7        | 1.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6        | 1.41%   |
| Nvidia MCP61 Ethernet                                             | 6        | 1.41%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 6        | 1.41%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 5        | 1.18%   |
| Intel Ethernet Connection (7) I219-V                              | 5        | 1.18%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 4        | 0.94%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 4        | 0.94%   |
| Intel Ethernet Connection I217-LM                                 | 4        | 0.94%   |
| Intel Ethernet Connection (2) I219-LM                             | 4        | 0.94%   |
| Intel Ethernet Connection (14) I219-V                             | 4        | 0.94%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 4        | 0.94%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 0.71%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 0.71%   |
| Nvidia MCP73 Ethernet                                             | 3        | 0.71%   |
| Intel Ethernet Controller I225-V                                  | 3        | 0.71%   |
| Intel 82566DM Gigabit Network Connection                          | 3        | 0.71%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 3        | 0.71%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2        | 0.47%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.47%   |
| Nvidia MCP79 Ethernet                                             | 2        | 0.47%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 2        | 0.47%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 0.47%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 2        | 0.47%   |
| Intel I210 Gigabit Network Connection                             | 2        | 0.47%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.47%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.47%   |
| Intel 82578DC Gigabit Network Connection                          | 2        | 0.47%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 2        | 0.47%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.47%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 0.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 388      | 72.8%   |
| WiFi     | 141      | 26.45%  |
| Modem    | 4        | 0.75%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 306      | 75.93%  |
| WiFi     | 97       | 24.07%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 289      | 73.72%  |
| 2     | 91       | 23.21%  |
| 3     | 9        | 2.3%    |
| 5     | 2        | 0.51%   |
| 6     | 1        | 0.26%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 310      | 77.89%  |
| Yes  | 88       | 22.11%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 26       | 32.1%   |
| Intel                           | 22       | 27.16%  |
| ASUSTek Computer                | 15       | 18.52%  |
| Realtek Semiconductor           | 8        | 9.88%   |
| IMC Networks                    | 2        | 2.47%   |
| Broadcom                        | 2        | 2.47%   |
| Belkin Components               | 2        | 2.47%   |
| TP-Link                         | 1        | 1.23%   |
| Toshiba                         | 1        | 1.23%   |
| Qualcomm Atheros Communications | 1        | 1.23%   |
| Apple                           | 1        | 1.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)  | 26       | 32.1%   |
| ASUS Broadcom BCM20702A0 Bluetooth                   | 9        | 11.11%  |
| Intel AX200 Bluetooth                                | 7        | 8.64%   |
| Intel Bluetooth wireless interface                   | 6        | 7.41%   |
| Realtek Bluetooth Radio                              | 5        | 6.17%   |
| Intel Wireless-AC 3168 Bluetooth                     | 4        | 4.94%   |
| Realtek  Bluetooth 4.2 Adapter                       | 3        | 3.7%    |
| ASUS ASUS USB-BT500                                  | 3        | 3.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter             | 2        | 2.47%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)       | 2        | 2.47%   |
| Broadcom BCM20702A0 Bluetooth 4.0                    | 2        | 2.47%   |
| TP-Link TPuLink UB500 Adapter                        | 1        | 1.23%   |
| Toshiba Atheros AR3012 Bluetooth                     | 1        | 1.23%   |
| Qualcomm Atheros Bluetooth USB Host Controller       | 1        | 1.23%   |
| Intel Bluetooth Device                               | 1        | 1.23%   |
| IMC Networks Wireless_Device                         | 1        | 1.23%   |
| IMC Networks Bluetooth Device                        | 1        | 1.23%   |
| Belkin Components Bluetooth Mini Dongle              | 1        | 1.23%   |
| Belkin Components Bluetooth Device with trace filter | 1        | 1.23%   |
| ASUS Qualcomm Bluetooth 4.1                          | 1        | 1.23%   |
| ASUS Bluetooth Radio                                 | 1        | 1.23%   |
| ASUS Bluetooth Adapter                               | 1        | 1.23%   |
| Apple Bluetooth HCI                                  | 1        | 1.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 240      | 36.92%  |
| AMD                                  | 172      | 26.46%  |
| Nvidia                               | 137      | 21.08%  |
| Creative Labs                        | 19       | 2.92%   |
| C-Media Electronics                  | 15       | 2.31%   |
| Logitech                             | 9        | 1.38%   |
| Kingston Technology                  | 8        | 1.23%   |
| JMTek                                | 8        | 1.23%   |
| Razer USA                            | 5        | 0.77%   |
| Texas Instruments                    | 4        | 0.62%   |
| Silicon Integrated Systems [SiS]     | 3        | 0.46%   |
| ASUSTek Computer                     | 3        | 0.46%   |
| VIA Technologies                     | 2        | 0.31%   |
| SteelSeries ApS                      | 2        | 0.31%   |
| Focusrite-Novation                   | 2        | 0.31%   |
| WinChipHead                          | 1        | 0.15%   |
| ULi Electronics                      | 1        | 0.15%   |
| Turtle Beach                         | 1        | 0.15%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.15%   |
| Sennheiser Communications            | 1        | 0.15%   |
| Samsung Electronics                  | 1        | 0.15%   |
| Samson Technologies                  | 1        | 0.15%   |
| Realtek Semiconductor                | 1        | 0.15%   |
| Plantronics                          | 1        | 0.15%   |
| Philips (or NXP)                     | 1        | 0.15%   |
| Microchip Technology                 | 1        | 0.15%   |
| Hewlett-Packard                      | 1        | 0.15%   |
| Harman                               | 1        | 0.15%   |
| Guillemot                            | 1        | 0.15%   |
| Generalplus Technology               | 1        | 0.15%   |
| Evolution Electronics                | 1        | 0.15%   |
| EGO SYStems                          | 1        | 0.15%   |
| Corsair                              | 1        | 0.15%   |
| Blue Microphones                     | 1        | 0.15%   |
| Arturia                              | 1        | 0.15%   |
| Apple                                | 1        | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 41       | 5.56%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 35       | 4.74%   |
| AMD Starship/Matisse HD Audio Controller                                          | 30       | 4.07%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 27       | 3.66%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 26       | 3.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 23       | 3.12%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 23       | 3.12%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 20       | 2.71%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 19       | 2.57%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 17       | 2.3%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 17       | 2.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 15       | 2.03%   |
| Intel Cannon Lake PCH cAVS                                                        | 15       | 2.03%   |
| Nvidia High Definition Audio Controller                                           | 12       | 1.63%   |
| AMD Family 17h/19h HD Audio Controller                                            | 12       | 1.63%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 10       | 1.36%   |
| Intel 200 Series PCH HD Audio                                                     | 10       | 1.36%   |
| Nvidia GF108 High Definition Audio Controller                                     | 9        | 1.22%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 9        | 1.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 9        | 1.22%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 9        | 1.22%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 9        | 1.22%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 8        | 1.08%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 8        | 1.08%   |
| Nvidia GP106 High Definition Audio Controller                                     | 7        | 0.95%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 7        | 0.95%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 7        | 0.95%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 7        | 0.95%   |
| Nvidia MCP61 High Definition Audio                                                | 6        | 0.81%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 6        | 0.81%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 6        | 0.81%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 6        | 0.81%   |
| AMD Navi 10 HDMI Audio                                                            | 6        | 0.81%   |
| Nvidia GM204 High Definition Audio Controller                                     | 5        | 0.68%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 5        | 0.68%   |
| Nvidia GF119 HDMI Audio Controller                                                | 5        | 0.68%   |
| Nvidia GA104 High Definition Audio Controller                                     | 5        | 0.68%   |
| Kingston Technology HyperX 7.1 Audio                                              | 5        | 0.68%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 5        | 0.68%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                         | 5        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 43       | 23.37%  |
| Unknown             | 41       | 22.28%  |
| G.Skill             | 23       | 12.5%   |
| Crucial             | 15       | 8.15%   |
| SK hynix            | 14       | 7.61%   |
| Corsair             | 13       | 7.07%   |
| Samsung Electronics | 10       | 5.43%   |
| Team                | 5        | 2.72%   |
| Micron Technology   | 4        | 2.17%   |
| Nanya Technology    | 2        | 1.09%   |
| A-DATA Technology   | 2        | 1.09%   |
| Unknown             | 2        | 1.09%   |
| Unknown (ABCD)      | 1        | 0.54%   |
| Unifosa             | 1        | 0.54%   |
| Transcend           | 1        | 0.54%   |
| Silicon Power       | 1        | 0.54%   |
| Ramaxel Technology  | 1        | 0.54%   |
| Patriot             | 1        | 0.54%   |
| Lexar               | 1        | 0.54%   |
| Infineon            | 1        | 0.54%   |
| Elpida              | 1        | 0.54%   |
| Apacer              | 1        | 0.54%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 3        | 1.42%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s             | 3        | 1.42%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3              | 3        | 1.42%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                    | 2        | 0.95%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                    | 2        | 0.95%   |
| Unknown RAM Module 4096MB DIMM                          | 2        | 0.95%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                    | 2        | 0.95%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                 | 2        | 0.95%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 3000MT/s     | 2        | 0.95%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s       | 2        | 0.95%   |
| Kingston RAM KHX1600C10D3/8GX 8192MB DIMM DDR3 1600MT/s | 2        | 0.95%   |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1600MT/s   | 2        | 0.95%   |
| G.Skill RAM F4-2400C15-16GIS 16GB DIMM DDR4 2400MT/s    | 2        | 0.95%   |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s   | 2        | 0.95%   |
| Crucial RAM CT51264BA160B.C16F 4GB DIMM DDR3 1600MT/s   | 2        | 0.95%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s   | 2        | 0.95%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 2        | 0.95%   |
| Unknown                                                 | 2        | 0.95%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s               | 1        | 0.47%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s            | 1        | 0.47%   |
| Unknown RAM Module 512MB DIMM 533MT/s                   | 1        | 0.47%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s               | 1        | 0.47%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                | 1        | 0.47%   |
| Unknown RAM Module 4GB DIMM 667MT/s                     | 1        | 0.47%   |
| Unknown RAM Module 4GB DIMM 400MT/s                     | 1        | 0.47%   |
| Unknown RAM Module 4GB DIMM                             | 1        | 0.47%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                 | 1        | 0.47%   |
| Unknown RAM Module 2GB DIMM SDRAM                       | 1        | 0.47%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                | 1        | 0.47%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                | 1        | 0.47%   |
| Unknown RAM Module 2GB DIMM DDR2 400MT/s                | 1        | 0.47%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s               | 1        | 0.47%   |
| Unknown RAM Module 2GB DIMM DDR2                        | 1        | 0.47%   |
| Unknown RAM Module 2GB DIMM 800MT/s                     | 1        | 0.47%   |
| Unknown RAM Module 2GB DIMM                             | 1        | 0.47%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s            | 1        | 0.47%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s            | 1        | 0.47%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s             | 1        | 0.47%   |
| Unknown RAM Module 2048MB DIMM DDR2 533MT/s             | 1        | 0.47%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                  | 1        | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 61       | 36.09%  |
| DDR3    | 59       | 34.91%  |
| Unknown | 20       | 11.83%  |
| DDR2    | 16       | 9.47%   |
| SDRAM   | 9        | 5.33%   |
| DDR     | 3        | 1.78%   |
| LPDDR4  | 1        | 0.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 162      | 97.01%  |
| SODIMM | 5        | 2.99%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 61       | 33.33%  |
| 4096  | 46       | 25.14%  |
| 2048  | 36       | 19.67%  |
| 16384 | 22       | 12.02%  |
| 1024  | 10       | 5.46%   |
| 32768 | 5        | 2.73%   |
| 512   | 2        | 1.09%   |
| 256   | 1        | 0.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 40       | 21.28%  |
| 1333    | 25       | 13.3%   |
| 2400    | 13       | 6.91%   |
| 3200    | 12       | 6.38%   |
| Unknown | 10       | 5.32%   |
| 3600    | 8        | 4.26%   |
| 2667    | 8        | 4.26%   |
| 667     | 8        | 4.26%   |
| 2133    | 7        | 3.72%   |
| 800     | 7        | 3.72%   |
| 3000    | 5        | 2.66%   |
| 1867    | 5        | 2.66%   |
| 2666    | 4        | 2.13%   |
| 533     | 4        | 2.13%   |
| 400     | 4        | 2.13%   |
| 3400    | 3        | 1.6%    |
| 4000    | 2        | 1.06%   |
| 3800    | 2        | 1.06%   |
| 2048    | 2        | 1.06%   |
| 2000    | 2        | 1.06%   |
| 1866    | 2        | 1.06%   |
| 1800    | 2        | 1.06%   |
| 43889   | 1        | 0.53%   |
| 3866    | 1        | 0.53%   |
| 3733    | 1        | 0.53%   |
| 3466    | 1        | 0.53%   |
| 3334    | 1        | 0.53%   |
| 3066    | 1        | 0.53%   |
| 2733    | 1        | 0.53%   |
| 2465    | 1        | 0.53%   |
| 2187    | 1        | 0.53%   |
| 2134    | 1        | 0.53%   |
| 1648    | 1        | 0.53%   |
| 1067    | 1        | 0.53%   |
| 1066    | 1        | 0.53%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 15       | 68.18%  |
| Canon                 | 3        | 13.64%  |
| Brother Industries    | 2        | 9.09%   |
| Xerox                 | 1        | 4.55%   |
| Lexmark International | 1        | 4.55%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| HP Deskjet 1050 J410            | 4        | 16.67%  |
| Xerox Phaser 6000B              | 1        | 4.17%   |
| Lexmark International E120(n)   | 1        | 4.17%   |
| HP OfficeJet 5200 series        | 1        | 4.17%   |
| HP Officejet 4620 series        | 1        | 4.17%   |
| HP Officejet 4500 G510g-m       | 1        | 4.17%   |
| HP LaserJet Professional P1102w | 1        | 4.17%   |
| HP LaserJet M14-M17             | 1        | 4.17%   |
| HP ENVY 6000 series             | 1        | 4.17%   |
| HP ENVY 4520 series             | 1        | 4.17%   |
| HP DeskJet F300 series          | 1        | 4.17%   |
| HP DeskJet 930c                 | 1        | 4.17%   |
| HP DeskJet 3630 series          | 1        | 4.17%   |
| HP Deskjet 3050 J610 series     | 1        | 4.17%   |
| HP DeskJet 2700 series          | 1        | 4.17%   |
| Canon TS6300 series             | 1        | 4.17%   |
| Canon PIXMA TS6250              | 1        | 4.17%   |
| Canon PIXMA MG2900 Series       | 1        | 4.17%   |
| Canon LBP6200                   | 1        | 4.17%   |
| Brother DCP-L3550CDW series     | 1        | 4.17%   |
| Brother DCP-1610W               | 1        | 4.17%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Mustek Systems  | 4        | 44.44%  |
| Canon           | 3        | 33.33%  |
| Seiko Epson     | 1        | 11.11%  |
| Hewlett-Packard | 1        | 11.11%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Mustek Systems ScanExpress 1200 UB    | 3        | 33.33%  |
| Seiko Epson GT-X770 [Perfection V500] | 1        | 11.11%  |
| Mustek Systems BearPaw 2448 CU Pro    | 1        | 11.11%  |
| HP ScanJet 5300c/5370c                | 1        | 11.11%  |
| Canon CanoScan N670U/N676U/LiDE 20    | 1        | 11.11%  |
| Canon CanoScan LiDE 110               | 1        | 11.11%  |
| Canon CanoScan 4400F                  | 1        | 11.11%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 22       | 27.5%   |
| Microsoft                     | 13       | 16.25%  |
| Hewlett-Packard               | 8        | 10%     |
| Creative Technology           | 8        | 10%     |
| Microdia                      | 4        | 5%      |
| Samsung Electronics           | 3        | 3.75%   |
| Cubeternet                    | 3        | 3.75%   |
| Aveo Technology               | 3        | 3.75%   |
| Sunplus Innovation Technology | 2        | 2.5%    |
| Realtek Semiconductor         | 2        | 2.5%    |
| Philips (or NXP)              | 2        | 2.5%    |
| Generalplus Technology        | 2        | 2.5%    |
| Chicony Electronics           | 2        | 2.5%    |
| Z-Star Microelectronics       | 1        | 1.25%   |
| Xiaomi                        | 1        | 1.25%   |
| WaveRider Communications      | 1        | 1.25%   |
| Razer USA                     | 1        | 1.25%   |
| Huawei Technologies           | 1        | 1.25%   |
| Apple                         | 1        | 1.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Microsoft LifeCam HD-3000                     | 8        | 10%     |
| HP Webcam HD 2300                             | 6        | 7.5%    |
| Logitech Webcam C270                          | 5        | 6.25%   |
| Logitech Webcam C310                          | 4        | 5%      |
| Logitech C922 Pro Stream Webcam               | 4        | 5%      |
| Samsung Galaxy A5 (MTP)                       | 3        | 3.75%   |
| Creative Live! Cam Sync 1080p                 | 3        | 3.75%   |
| Aveo UVC camera (Bresser microscope)          | 3        | 3.75%   |
| Microsoft LifeCam VX-800                      | 2        | 2.5%    |
| Microsoft LifeCam VX-2000                     | 2        | 2.5%    |
| Microdia Sonix USB 2.0 Camera                 | 2        | 2.5%    |
| Logitech QuickCam Express                     | 2        | 2.5%    |
| Generalplus 808 Camera #9 (web-cam mode)      | 2        | 2.5%    |
| Cubeternet USB2.0 Camera                      | 2        | 2.5%    |
| Z-Star Vega USB 2.0 Camera                    | 1        | 1.25%   |
| Xiaomi Mi 10 Lite 5G                          | 1        | 1.25%   |
| WaveRider USB 2.0 Camera                      | 1        | 1.25%   |
| Sunplus HD 720P webcam                        | 1        | 1.25%   |
| Sunplus FHD Camera Microphone                 | 1        | 1.25%   |
| Realtek USB Camera                            | 1        | 1.25%   |
| Realtek NexiGo N660P FHD Webcam               | 1        | 1.25%   |
| Razer USA Razer Kiyo Pro                      | 1        | 1.25%   |
| Philips (or NXP) Webcam SPC530NC              | 1        | 1.25%   |
| Philips (or NXP) SPZ2500                      | 1        | 1.25%   |
| Microsoft LifeCam VX-700                      | 1        | 1.25%   |
| Microdia Lumina Camera - Raw                  | 1        | 1.25%   |
| Microdia Camera                               | 1        | 1.25%   |
| Logitech Webcam C925e                         | 1        | 1.25%   |
| Logitech Webcam C200                          | 1        | 1.25%   |
| Logitech Webcam C170                          | 1        | 1.25%   |
| Logitech QuickCam Pro 4000                    | 1        | 1.25%   |
| Logitech HD Webcam C910                       | 1        | 1.25%   |
| Logitech HD Webcam C525                       | 1        | 1.25%   |
| Logitech Brio 500                             | 1        | 1.25%   |
| Huawei UVC Camera                             | 1        | 1.25%   |
| HP Webcam HD 4310                             | 1        | 1.25%   |
| HP 320 FHD Webcam                             | 1        | 1.25%   |
| Cubeternet GL-UPC822 UVC WebCam               | 1        | 1.25%   |
| Creative Webcam Live! Effects                 | 1        | 1.25%   |
| Creative VF0540 Live! Cam Video IM/Video Chat | 1        | 1.25%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| AuthenTec | 2        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| AuthenTec AES1600 | 2        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Gemalto (was Gemplus) | 3        | 33.33%  |
| BIT4ID                | 2        | 22.22%  |
| Alcor Micro           | 2        | 22.22%  |
| Realtek Semiconductor | 1        | 11.11%  |
| Chicony Electronics   | 1        | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader    | 3        | 33.33%  |
| BIT4ID miniLector EVO                                | 2        | 22.22%  |
| Realtek Semiconductor Smart Card Reader Interface    | 1        | 11.11%  |
| Chicony Electronics HP Skylab USB Smartcard Keyboard | 1        | 11.11%  |
| Alcor Micro Watchdata W 1981                         | 1        | 11.11%  |
| Alcor Micro AU9540 Smartcard Reader                  | 1        | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 347      | 86.75%  |
| 1     | 46       | 11.5%   |
| 2     | 6        | 1.5%    |
| 3     | 1        | 0.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 26       | 44.07%  |
| Net/wireless             | 8        | 13.56%  |
| Chipcard                 | 7        | 11.86%  |
| Multimedia controller    | 3        | 5.08%   |
| Camera                   | 3        | 5.08%   |
| Bluetooth                | 3        | 5.08%   |
| Network                  | 2        | 3.39%   |
| Fingerprint reader       | 2        | 3.39%   |
| Sound                    | 1        | 1.69%   |
| Net/ethernet             | 1        | 1.69%   |
| Modem                    | 1        | 1.69%   |
| Communication controller | 1        | 1.69%   |
| Card reader              | 1        | 1.69%   |


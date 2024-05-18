Xero - Tested Hardware & Statistics (Desktops)
----------------------------------------------

A project to collect tested hardware configurations for Xero.

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

Total: 210

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Medion        | B360H4-EM V1.0              | [1dce3c5ac9](https://linux-hardware.org/?probe=1dce3c5ac9) | Apr 30, 2024 |
| HP            | 2B47                        | [3a165a34a7](https://linux-hardware.org/?probe=3a165a34a7) | Apr 27, 2024 |
| Dell          | 0773VG A02                  | [2db2c160ae](https://linux-hardware.org/?probe=2db2c160ae) | Apr 03, 2024 |
| HP            | 2AF7                        | [a9fd9938cd](https://linux-hardware.org/?probe=a9fd9938cd) | Apr 01, 2024 |
| Acer          | Aspire XC-603               | [68c8512ceb](https://linux-hardware.org/?probe=68c8512ceb) | Mar 09, 2024 |
| MSI           | 970 GAMING                  | [940cdd271c](https://linux-hardware.org/?probe=940cdd271c) | Mar 01, 2024 |
| ASUSTek       | P5K                         | [a93b9e89e3](https://linux-hardware.org/?probe=a93b9e89e3) | Feb 08, 2024 |
| Dell          | 06X1TJ A00                  | [f3cb8642e0](https://linux-hardware.org/?probe=f3cb8642e0) | Feb 01, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [2ca75c65d6](https://linux-hardware.org/?probe=2ca75c65d6) | Jan 26, 2024 |
| MSI           | B85M-E45                    | [641e17fe01](https://linux-hardware.org/?probe=641e17fe01) | Jan 19, 2024 |
| MSI           | B85M-E45                    | [32fd96fdd0](https://linux-hardware.org/?probe=32fd96fdd0) | Jan 19, 2024 |
| MSI           | G41M-S01                    | [373595b73a](https://linux-hardware.org/?probe=373595b73a) | Jan 16, 2024 |
| ASRock        | B450 Steel Legend           | [0afe07637c](https://linux-hardware.org/?probe=0afe07637c) | Jan 11, 2024 |
| MSI           | B85M-G43                    | [8982801bbb](https://linux-hardware.org/?probe=8982801bbb) | Jan 10, 2024 |
| ASUSTek       | PRIME B450M-A II            | [7e0a72f2d3](https://linux-hardware.org/?probe=7e0a72f2d3) | Jan 10, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [54f70ad2a1](https://linux-hardware.org/?probe=54f70ad2a1) | Jan 05, 2024 |
| Win Elemen... | M9                          | [33b3133a1c](https://linux-hardware.org/?probe=33b3133a1c) | Jan 01, 2024 |
| Win Elemen... | M9                          | [93f17e23c2](https://linux-hardware.org/?probe=93f17e23c2) | Jan 01, 2024 |
| Acer          | Aspire TC-885 V:1.1         | [19be3bdc5b](https://linux-hardware.org/?probe=19be3bdc5b) | Dec 31, 2023 |
| MSI           | B85M-G43                    | [16b0ff5ec7](https://linux-hardware.org/?probe=16b0ff5ec7) | Dec 30, 2023 |
| ASRock        | Q1900M                      | [5a28e8874e](https://linux-hardware.org/?probe=5a28e8874e) | Dec 26, 2023 |
| ASUSTek       | P8Z77-V PRO                 | [4f8558438f](https://linux-hardware.org/?probe=4f8558438f) | Dec 23, 2023 |
| Dell          | 06X1TJ A00                  | [eac468f369](https://linux-hardware.org/?probe=eac468f369) | Dec 20, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [cd04b1b3df](https://linux-hardware.org/?probe=cd04b1b3df) | Dec 17, 2023 |
| ASRock        | A620M Pro RS WiFi           | [069de62879](https://linux-hardware.org/?probe=069de62879) | Dec 13, 2023 |
| Huanan        | X99-F8                      | [8c534cb0a4](https://linux-hardware.org/?probe=8c534cb0a4) | Dec 09, 2023 |
| Huanan        | X99-F8                      | [6d1bdd1b81](https://linux-hardware.org/?probe=6d1bdd1b81) | Dec 09, 2023 |
| Dell          | 00V62H A01                  | [3a19753377](https://linux-hardware.org/?probe=3a19753377) | Dec 05, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [4d788fb96c](https://linux-hardware.org/?probe=4d788fb96c) | Dec 04, 2023 |
| Gigabyte      | B450M S2H                   | [5dcf20cb88](https://linux-hardware.org/?probe=5dcf20cb88) | Dec 04, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [c6454cb058](https://linux-hardware.org/?probe=c6454cb058) | Dec 04, 2023 |
| Gigabyte      | B450M S2H                   | [2f07094763](https://linux-hardware.org/?probe=2f07094763) | Dec 04, 2023 |
| MSI           | Z97-GD65 GAMING             | [86230be0a7](https://linux-hardware.org/?probe=86230be0a7) | Nov 27, 2023 |
| ECS           | H81H3-M3                    | [e3473e64c5](https://linux-hardware.org/?probe=e3473e64c5) | Nov 27, 2023 |
| ECS           | H81H3-M3                    | [c9b79740d2](https://linux-hardware.org/?probe=c9b79740d2) | Nov 27, 2023 |
| Gigabyte      | H81M-H                      | [bfb937c0c0](https://linux-hardware.org/?probe=bfb937c0c0) | Nov 26, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | [a18b2f2c3e](https://linux-hardware.org/?probe=a18b2f2c3e) | Nov 25, 2023 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [b9b8e57c7c](https://linux-hardware.org/?probe=b9b8e57c7c) | Nov 25, 2023 |
| ASUSTek       | PRIME A520M-K               | [83c2b87d3c](https://linux-hardware.org/?probe=83c2b87d3c) | Nov 24, 2023 |
| Gigabyte      | B450M DS3H-CF               | [56c19073cb](https://linux-hardware.org/?probe=56c19073cb) | Nov 20, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [49139037ec](https://linux-hardware.org/?probe=49139037ec) | Nov 20, 2023 |
| Dell          | 0HY9JP A02                  | [c97b664653](https://linux-hardware.org/?probe=c97b664653) | Nov 18, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [6525548dab](https://linux-hardware.org/?probe=6525548dab) | Nov 12, 2023 |
| Intel         | X99                         | [5c6225ea2d](https://linux-hardware.org/?probe=5c6225ea2d) | Nov 11, 2023 |
| ASRock        | B250M-HDV                   | [c8521456ad](https://linux-hardware.org/?probe=c8521456ad) | Nov 04, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [1da3521ff2](https://linux-hardware.org/?probe=1da3521ff2) | Nov 04, 2023 |
| ASUSTek       | PRIME H510M-D               | [d6749e3f8b](https://linux-hardware.org/?probe=d6749e3f8b) | Nov 01, 2023 |
| ASUSTek       | H170M-PLUS                  | [90b5515582](https://linux-hardware.org/?probe=90b5515582) | Oct 31, 2023 |
| Dell          | 0R849J A01                  | [3891d2fd80](https://linux-hardware.org/?probe=3891d2fd80) | Oct 31, 2023 |
| Huanan        | X99-F8                      | [0bcf4adaf6](https://linux-hardware.org/?probe=0bcf4adaf6) | Oct 31, 2023 |
| Gigabyte      | B760 AORUS ELITE AX DDR4    | [53ff42384c](https://linux-hardware.org/?probe=53ff42384c) | Oct 29, 2023 |
| Huanan        | X99-F8                      | [69329218c9](https://linux-hardware.org/?probe=69329218c9) | Oct 25, 2023 |
| ASUSTek       | H61M-K                      | [150a11b476](https://linux-hardware.org/?probe=150a11b476) | Oct 21, 2023 |
| MSI           | B85M-E45                    | [8c3f253c5e](https://linux-hardware.org/?probe=8c3f253c5e) | Oct 19, 2023 |
| Dell          | 0T568R A00                  | [ef9aa5b89c](https://linux-hardware.org/?probe=ef9aa5b89c) | Oct 14, 2023 |
| ASUSTek       | P5QD TURBO                  | [63c82d8692](https://linux-hardware.org/?probe=63c82d8692) | Oct 13, 2023 |
| Lenovo        | MAHOBAY                     | [9ced54f630](https://linux-hardware.org/?probe=9ced54f630) | Oct 01, 2023 |
| Dell          | 0MN1TX A02                  | [3f0eee5de0](https://linux-hardware.org/?probe=3f0eee5de0) | Oct 01, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [e26d1b1ae4](https://linux-hardware.org/?probe=e26d1b1ae4) | Sep 30, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [074ab86d60](https://linux-hardware.org/?probe=074ab86d60) | Sep 29, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [fee2fdb49a](https://linux-hardware.org/?probe=fee2fdb49a) | Sep 25, 2023 |
| Huanan        | X99-TF V1.1                 | [694b4ab1f2](https://linux-hardware.org/?probe=694b4ab1f2) | Sep 24, 2023 |
| HP            | 2B2C                        | [79ccf62c55](https://linux-hardware.org/?probe=79ccf62c55) | Sep 23, 2023 |
| ASRock        | A300M-STX                   | [2fc60c03c3](https://linux-hardware.org/?probe=2fc60c03c3) | Sep 22, 2023 |
| MSI           | PRO H610M-B DDR4            | [ee0a21be07](https://linux-hardware.org/?probe=ee0a21be07) | Sep 21, 2023 |
| Dell          | 0WR7PY A02                  | [5e059c90e1](https://linux-hardware.org/?probe=5e059c90e1) | Sep 21, 2023 |
| ECS           | H61H2-M2                    | [fe16b7a5a1](https://linux-hardware.org/?probe=fe16b7a5a1) | Sep 19, 2023 |
| Dell          | 0T568R A00                  | [675cec7d95](https://linux-hardware.org/?probe=675cec7d95) | Sep 17, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [eb2fcff0f3](https://linux-hardware.org/?probe=eb2fcff0f3) | Sep 16, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [c95eedf70e](https://linux-hardware.org/?probe=c95eedf70e) | Sep 16, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [966d90cbc8](https://linux-hardware.org/?probe=966d90cbc8) | Sep 14, 2023 |
| Huanan        | X99-TF V1.1                 | [a5acc6026f](https://linux-hardware.org/?probe=a5acc6026f) | Sep 14, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [a68551130a](https://linux-hardware.org/?probe=a68551130a) | Sep 13, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [3edc89267d](https://linux-hardware.org/?probe=3edc89267d) | Sep 13, 2023 |
| ASUSTek       | M5A99X EVO                  | [82125c27c9](https://linux-hardware.org/?probe=82125c27c9) | Sep 12, 2023 |
| Gigabyte      | Z790 UD                     | [bcfc38f6da](https://linux-hardware.org/?probe=bcfc38f6da) | Sep 11, 2023 |
| ASUSTek       | M5A99X EVO                  | [3bc292a4ce](https://linux-hardware.org/?probe=3bc292a4ce) | Sep 10, 2023 |
| Pegatron      | 2AB6                        | [5b2fda7ad6](https://linux-hardware.org/?probe=5b2fda7ad6) | Sep 09, 2023 |
| HP            | 2B18                        | [9c8753a19e](https://linux-hardware.org/?probe=9c8753a19e) | Sep 09, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [bb02ef5cc7](https://linux-hardware.org/?probe=bb02ef5cc7) | Sep 08, 2023 |
| HP            | 2B3C                        | [471f0f283b](https://linux-hardware.org/?probe=471f0f283b) | Sep 06, 2023 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | [b1329d0cc1](https://linux-hardware.org/?probe=b1329d0cc1) | Sep 05, 2023 |
| ASUSTek       | PRIME A320M-K               | [7263435dde](https://linux-hardware.org/?probe=7263435dde) | Sep 05, 2023 |
| ASUSTek       | PRIME X299-A II             | [80a93a9457](https://linux-hardware.org/?probe=80a93a9457) | Sep 02, 2023 |
| HP            | 18E9                        | [fd1f6decb2](https://linux-hardware.org/?probe=fd1f6decb2) | Sep 01, 2023 |
| MSI           | Z97 GAMING 7                | [ea78ba2d46](https://linux-hardware.org/?probe=ea78ba2d46) | Aug 29, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [5b896ea45c](https://linux-hardware.org/?probe=5b896ea45c) | Aug 29, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [6b6ec006aa](https://linux-hardware.org/?probe=6b6ec006aa) | Aug 28, 2023 |
| Gigabyte      | H110M-H-CF                  | [cc89933ff1](https://linux-hardware.org/?probe=cc89933ff1) | Aug 28, 2023 |
| ASUSTek       | PRIME H510M-R               | [c6614846b5](https://linux-hardware.org/?probe=c6614846b5) | Aug 28, 2023 |
| HP            | 2B18                        | [891ce74167](https://linux-hardware.org/?probe=891ce74167) | Aug 27, 2023 |
| Dell          | 06X1TJ A00                  | [450512bee1](https://linux-hardware.org/?probe=450512bee1) | Aug 27, 2023 |
| MSI           | A520M-A PRO                 | [7423f83594](https://linux-hardware.org/?probe=7423f83594) | Aug 27, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [dd4626de1b](https://linux-hardware.org/?probe=dd4626de1b) | Aug 27, 2023 |
| Gigabyte      | Z370M DS3H-CF               | [6ae200367f](https://linux-hardware.org/?probe=6ae200367f) | Aug 27, 2023 |
| Gigabyte      | Z490 GAMING X               | [ee07c69165](https://linux-hardware.org/?probe=ee07c69165) | Aug 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [17a7fc84be](https://linux-hardware.org/?probe=17a7fc84be) | Aug 26, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [d4cf1916d2](https://linux-hardware.org/?probe=d4cf1916d2) | Aug 26, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [16790cbb5f](https://linux-hardware.org/?probe=16790cbb5f) | Aug 26, 2023 |
| BESSTAR Te... | UM700                       | [bca12d1c12](https://linux-hardware.org/?probe=bca12d1c12) | Aug 24, 2023 |
| Gigabyte      | Z790 AORUS MASTER           | [202017a190](https://linux-hardware.org/?probe=202017a190) | Aug 23, 2023 |
| Win Elemen... | M9                          | [f161447dfc](https://linux-hardware.org/?probe=f161447dfc) | Aug 22, 2023 |
| Acer          | Predator PO3-630            | [b7c9c3e0c4](https://linux-hardware.org/?probe=b7c9c3e0c4) | Aug 22, 2023 |
| ASRock        | A320M-DVS R4.0              | [5a9badb376](https://linux-hardware.org/?probe=5a9badb376) | Aug 22, 2023 |
| MSI           | MEG Z390 ACE                | [5ab219fbd1](https://linux-hardware.org/?probe=5ab219fbd1) | Aug 20, 2023 |
| MSI           | H270M BAZOOKA               | [f51f1ce129](https://linux-hardware.org/?probe=f51f1ce129) | Aug 19, 2023 |
| MSI           | Z87 MPOWER MAX              | [6bda9908df](https://linux-hardware.org/?probe=6bda9908df) | Aug 16, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [11dafc79e8](https://linux-hardware.org/?probe=11dafc79e8) | Aug 15, 2023 |
| MSI           | 760GM-P33                   | [878209b83a](https://linux-hardware.org/?probe=878209b83a) | Aug 13, 2023 |
| ASUSTek       | PRIME H510M-R               | [38ab435feb](https://linux-hardware.org/?probe=38ab435feb) | Aug 08, 2023 |
| MSI           | B350 GAMING PLUS            | [951597859a](https://linux-hardware.org/?probe=951597859a) | Aug 08, 2023 |
| ASRock        | X300M-STX                   | [e642e8e489](https://linux-hardware.org/?probe=e642e8e489) | Aug 08, 2023 |
| ECS           | H61H2-CM                    | [e2b9ff65d7](https://linux-hardware.org/?probe=e2b9ff65d7) | Aug 06, 2023 |
| ASRock        | Z77 Professional            | [2f0bc369b4](https://linux-hardware.org/?probe=2f0bc369b4) | Aug 03, 2023 |
| Gigabyte      | Z490 GAMING X               | [f710ad8b96](https://linux-hardware.org/?probe=f710ad8b96) | Jul 31, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [2c6149347b](https://linux-hardware.org/?probe=2c6149347b) | Jul 30, 2023 |
| MSI           | H510M-A PRO                 | [20d5d0a3ad](https://linux-hardware.org/?probe=20d5d0a3ad) | Jul 30, 2023 |
| Intel         | B75                         | [492fa4fc25](https://linux-hardware.org/?probe=492fa4fc25) | Jul 26, 2023 |
| Lenovo        | ThinkCentre M58 3231W2Y     | [72f09cd320](https://linux-hardware.org/?probe=72f09cd320) | Jul 26, 2023 |
| ASUSTek       | PRIME X570-P                | [96f5f9ffdc](https://linux-hardware.org/?probe=96f5f9ffdc) | Jul 19, 2023 |
| ASRock        | B450 Pro4                   | [c10ecff0f6](https://linux-hardware.org/?probe=c10ecff0f6) | Jul 19, 2023 |
| ASUSTek       | PRIME X299-A II             | [54f9bd2050](https://linux-hardware.org/?probe=54f9bd2050) | Jul 18, 2023 |
| Gigabyte      | X79-UD3                     | [d688be2c92](https://linux-hardware.org/?probe=d688be2c92) | Jul 18, 2023 |
| Gigabyte      | Z490 GAMING X               | [866bc45d05](https://linux-hardware.org/?probe=866bc45d05) | Jul 18, 2023 |
| MSI           | B450M-A PRO MAX             | [4c8b8b5a8a](https://linux-hardware.org/?probe=4c8b8b5a8a) | Jul 18, 2023 |
| ASUSTek       | TUF Z270 MARK 2             | [d23b7166b1](https://linux-hardware.org/?probe=d23b7166b1) | Jul 18, 2023 |
| Gigabyte      | Z490 GAMING X               | [3c5ef629e4](https://linux-hardware.org/?probe=3c5ef629e4) | Jul 18, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [4d00148664](https://linux-hardware.org/?probe=4d00148664) | Jul 16, 2023 |
| Gigabyte      | X399 AORUS XTREME-CF        | [59bf614ae2](https://linux-hardware.org/?probe=59bf614ae2) | Jul 14, 2023 |
| MSI           | B450M-A PRO MAX             | [9ec51bc7eb](https://linux-hardware.org/?probe=9ec51bc7eb) | Jul 14, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [75d40e5a2b](https://linux-hardware.org/?probe=75d40e5a2b) | Jul 14, 2023 |
| MSI           | H510M-A PRO                 | [995e13dee9](https://linux-hardware.org/?probe=995e13dee9) | Jul 11, 2023 |
| Gigabyte      | Z490 GAMING X               | [27e600a93b](https://linux-hardware.org/?probe=27e600a93b) | Jul 07, 2023 |
| ASUSTek       | Rampage V EDITION 10        | [c945bae843](https://linux-hardware.org/?probe=c945bae843) | Jul 05, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [ca637a5884](https://linux-hardware.org/?probe=ca637a5884) | Jul 05, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [407e00921f](https://linux-hardware.org/?probe=407e00921f) | Jul 04, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [fc70411ea4](https://linux-hardware.org/?probe=fc70411ea4) | Jul 03, 2023 |
| Gigabyte      | Z490 GAMING X               | [107fe61a53](https://linux-hardware.org/?probe=107fe61a53) | Jul 02, 2023 |
| ASUSTek       | H110M-A                     | [c3118a3d89](https://linux-hardware.org/?probe=c3118a3d89) | Jun 29, 2023 |
| ASRock        | X570 Taichi                 | [895760e7db](https://linux-hardware.org/?probe=895760e7db) | Jun 27, 2023 |
| ASUSTek       | A68HM-PLUS                  | [fa162784e0](https://linux-hardware.org/?probe=fa162784e0) | Jun 24, 2023 |
| MSI           | Z77A-G41                    | [e7e4924bda](https://linux-hardware.org/?probe=e7e4924bda) | Jun 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [284344e775](https://linux-hardware.org/?probe=284344e775) | Jun 14, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [859f1b3a88](https://linux-hardware.org/?probe=859f1b3a88) | Jun 13, 2023 |
| ASUSTek       | PRIME B450M-A II            | [95bc101c80](https://linux-hardware.org/?probe=95bc101c80) | Jun 09, 2023 |
| Dell          | 00V62H A01                  | [89d6a4edd2](https://linux-hardware.org/?probe=89d6a4edd2) | May 13, 2023 |
| Unknown       | Intel X79                   | [6b1ddbd923](https://linux-hardware.org/?probe=6b1ddbd923) | May 03, 2023 |
| Biostar       | H110MHV3                    | [95b25ba480](https://linux-hardware.org/?probe=95b25ba480) | Apr 29, 2023 |
| ASUSTek       | A68HM-PLUS                  | [520ad2ca86](https://linux-hardware.org/?probe=520ad2ca86) | Mar 31, 2023 |
| HP            | 8437                        | [cdc32d8d8b](https://linux-hardware.org/?probe=cdc32d8d8b) | Mar 25, 2023 |
| HP            | 8437                        | [6fbb459a03](https://linux-hardware.org/?probe=6fbb459a03) | Mar 25, 2023 |
| ASUSTek       | A68HM-PLUS                  | [5d307f2d26](https://linux-hardware.org/?probe=5d307f2d26) | Mar 18, 2023 |
| Acer          | Aspire GX-281               | [d318df6931](https://linux-hardware.org/?probe=d318df6931) | Mar 04, 2023 |
| JINGSHA       | Unknown                     | [c8bd846b63](https://linux-hardware.org/?probe=c8bd846b63) | Feb 26, 2023 |
| Dell          | 0G3HR7 A00                  | [33723c8b80](https://linux-hardware.org/?probe=33723c8b80) | Feb 25, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [503fe663b4](https://linux-hardware.org/?probe=503fe663b4) | Feb 20, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [d76b048134](https://linux-hardware.org/?probe=d76b048134) | Feb 17, 2023 |
| HP            | 828A                        | [5f430ba8d1](https://linux-hardware.org/?probe=5f430ba8d1) | Jan 19, 2023 |
| Pegatron      | 2AF0                        | [77768feff6](https://linux-hardware.org/?probe=77768feff6) | Jan 01, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [f074ef2e7c](https://linux-hardware.org/?probe=f074ef2e7c) | Nov 15, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [711e95b72e](https://linux-hardware.org/?probe=711e95b72e) | Nov 02, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [ff0c19c661](https://linux-hardware.org/?probe=ff0c19c661) | Nov 02, 2022 |
| Gigabyte      | A320M-S2H-CF                | [bcf4fa1baf](https://linux-hardware.org/?probe=bcf4fa1baf) | Oct 18, 2022 |
| Dell          | 0GY6Y8 A02                  | [07b256f333](https://linux-hardware.org/?probe=07b256f333) | Oct 17, 2022 |
| Dell          | 0GY6Y8 A02                  | [fc1ec464bf](https://linux-hardware.org/?probe=fc1ec464bf) | Oct 17, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [bf0e112f9a](https://linux-hardware.org/?probe=bf0e112f9a) | Oct 16, 2022 |
| ASUSTek       | PRIME B250-PLUS             | [00ab764924](https://linux-hardware.org/?probe=00ab764924) | Oct 15, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [e037086b30](https://linux-hardware.org/?probe=e037086b30) | Oct 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [9931b35717](https://linux-hardware.org/?probe=9931b35717) | Sep 24, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [4c95b1bccf](https://linux-hardware.org/?probe=4c95b1bccf) | Aug 22, 2022 |
| Gigabyte      | B460M DS3H V2               | [2522ff1530](https://linux-hardware.org/?probe=2522ff1530) | Aug 13, 2022 |
| ASUSTek       | P7P55 LX                    | [8211ccc6cc](https://linux-hardware.org/?probe=8211ccc6cc) | Aug 11, 2022 |
| Unknown       | Unknown                     | [b73e5f9cbf](https://linux-hardware.org/?probe=b73e5f9cbf) | Aug 08, 2022 |
| Unknown       | Unknown                     | [f483092edf](https://linux-hardware.org/?probe=f483092edf) | Aug 07, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [a0507fae02](https://linux-hardware.org/?probe=a0507fae02) | Jul 31, 2022 |
| ASRock        | AB350 Pro4                  | [7049f819f0](https://linux-hardware.org/?probe=7049f819f0) | Jun 30, 2022 |
| HP            | 3396                        | [00782afa06](https://linux-hardware.org/?probe=00782afa06) | Jun 22, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [8109a04ffa](https://linux-hardware.org/?probe=8109a04ffa) | Jun 12, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [8a7401e54a](https://linux-hardware.org/?probe=8a7401e54a) | Jun 11, 2022 |
| Acer          | Aspire XC-886 V:2.0         | [2fe8cdaf93](https://linux-hardware.org/?probe=2fe8cdaf93) | May 31, 2022 |
| ASUSTek       | ROG Maximus X HERO          | [3ddad532a9](https://linux-hardware.org/?probe=3ddad532a9) | May 08, 2022 |
| MSI           | Z170-A PRO                  | [db5ab86328](https://linux-hardware.org/?probe=db5ab86328) | Apr 11, 2022 |
| MSI           | Z170-A PRO                  | [3bd5bb8d08](https://linux-hardware.org/?probe=3bd5bb8d08) | Apr 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [8d251b1b2a](https://linux-hardware.org/?probe=8d251b1b2a) | Apr 03, 2022 |
| HP            | 843B                        | [a88ff7cf5c](https://linux-hardware.org/?probe=a88ff7cf5c) | Mar 27, 2022 |
| Pegatron      | 2AC2                        | [d3c82e973b](https://linux-hardware.org/?probe=d3c82e973b) | Mar 25, 2022 |
| ASUSTek       | Maximus IX HERO             | [745cc1d638](https://linux-hardware.org/?probe=745cc1d638) | Mar 25, 2022 |
| ASUSTek       | Maximus IX HERO             | [8eb98db533](https://linux-hardware.org/?probe=8eb98db533) | Mar 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [13cdf54c81](https://linux-hardware.org/?probe=13cdf54c81) | Mar 21, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [639e7361ef](https://linux-hardware.org/?probe=639e7361ef) | Mar 12, 2022 |
| MSI           | Z170A PC MATE               | [181e014823](https://linux-hardware.org/?probe=181e014823) | Mar 08, 2022 |
| Gigabyte      | Z170X-UD3-CF                | [3ec7a7f643](https://linux-hardware.org/?probe=3ec7a7f643) | Mar 06, 2022 |
| ASUSTek       | P5Q PRO TURBO               | [83ca29c9c8](https://linux-hardware.org/?probe=83ca29c9c8) | Jan 28, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [230373b3ff](https://linux-hardware.org/?probe=230373b3ff) | Jan 09, 2022 |
| HP            | 1906                        | [5f8fe7cb20](https://linux-hardware.org/?probe=5f8fe7cb20) | Jan 06, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [793bfa4f40](https://linux-hardware.org/?probe=793bfa4f40) | Jan 04, 2022 |
| HP            | 2179                        | [79bac7ce1b](https://linux-hardware.org/?probe=79bac7ce1b) | Jan 01, 2022 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | [512091cd1c](https://linux-hardware.org/?probe=512091cd1c) | Dec 30, 2021 |
| HP            | 2179                        | [9b6358ce37](https://linux-hardware.org/?probe=9b6358ce37) | Dec 30, 2021 |
| ASRock        | X570 Taichi                 | [5c2c86f287](https://linux-hardware.org/?probe=5c2c86f287) | Dec 23, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [728b23aa46](https://linux-hardware.org/?probe=728b23aa46) | Nov 26, 2021 |
| ASUSTek       | PRIME A320M-K               | [9e9b6fd944](https://linux-hardware.org/?probe=9e9b6fd944) | Nov 21, 2021 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [4877535f8b](https://linux-hardware.org/?probe=4877535f8b) | Nov 03, 2021 |
| MSI           | Z370 GAMING PLUS            | [8dd5924480](https://linux-hardware.org/?probe=8dd5924480) | Oct 31, 2021 |
| Dell          | 0XC7MM A01                  | [390c5408b2](https://linux-hardware.org/?probe=390c5408b2) | Oct 05, 2021 |
| ASRock        | B450M Pro4                  | [a198e8517a](https://linux-hardware.org/?probe=a198e8517a) | Oct 01, 2021 |
| ASRock        | X570 Taichi                 | [50fd919991](https://linux-hardware.org/?probe=50fd919991) | Aug 29, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [a3c6fe4037](https://linux-hardware.org/?probe=a3c6fe4037) | Jul 24, 2021 |
| ASRock        | X570 Taichi                 | [57d19e2c3a](https://linux-hardware.org/?probe=57d19e2c3a) | May 19, 2021 |
| Acer          | FIH57                       | [9c3e383ea5](https://linux-hardware.org/?probe=9c3e383ea5) | Apr 30, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Xero Rolling | 149      | 96.75%  |
| Xero         | 5        | 3.25%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| Xero | 154      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Desktops | Percent |
|----------------------------|----------|---------|
| 6.4.12-arch1-1             | 19       | 11.11%  |
| 6.4.9-arch1-1              | 13       | 7.6%    |
| 6.6.4-arch1-1              | 12       | 7.02%   |
| 6.4.3-arch1-2              | 11       | 6.43%   |
| 6.5.9-arch2-1              | 8        | 4.68%   |
| 6.6.2-arch1-1              | 5        | 2.92%   |
| 6.4.10-arch1-1             | 4        | 2.34%   |
| 6.1.12-arch1-1             | 4        | 2.34%   |
| 6.6.1-arch1-1              | 3        | 1.75%   |
| 6.5.5-arch1-1              | 3        | 1.75%   |
| 6.6.9-arch1-1              | 2        | 1.17%   |
| 6.6.8-arch1-1              | 2        | 1.17%   |
| 6.6.3-arch1-1              | 2        | 1.17%   |
| 6.5.3-arch1-1              | 2        | 1.17%   |
| 6.4.3-arch1-1              | 2        | 1.17%   |
| 6.4.12-zen1-1-zen          | 2        | 1.17%   |
| 6.3.9-arch1-1              | 2        | 1.17%   |
| 6.2.12-arch1-1             | 2        | 1.17%   |
| 5.18.16-arch1-1            | 2        | 1.17%   |
| 5.16.15-arch1-1            | 2        | 1.17%   |
| 5.16.12-arch1-1            | 2        | 1.17%   |
| 6.7.9-zen1-1-zen           | 1        | 0.58%   |
| 6.7.6-arch1-1              | 1        | 0.58%   |
| 6.7.1-arch1-1              | 1        | 0.58%   |
| 6.7.0-arch3-1              | 1        | 0.58%   |
| 6.6.7-arch1-1              | 1        | 0.58%   |
| 6.6.4-273-tkg-bore         | 1        | 0.58%   |
| 6.6.10-arch1-1             | 1        | 0.58%   |
| 6.5.9-zen2-1-zen           | 1        | 0.58%   |
| 6.5.7-arch1-1              | 1        | 0.58%   |
| 6.5.4-arch2-1              | 1        | 0.58%   |
| 6.5.2-arch1-1              | 1        | 0.58%   |
| 6.5.2-273-tkg-bore-eevdf   | 1        | 0.58%   |
| 6.4.8-arch1-1              | 1        | 0.58%   |
| 6.4.7-zen1-1-zen           | 1        | 0.58%   |
| 6.4.7-arch1-2              | 1        | 0.58%   |
| 6.4.7-arch1-1              | 1        | 0.58%   |
| 6.4.4-hardened1-1-hardened | 1        | 0.58%   |
| 6.4.3-zen1-2-zen           | 1        | 0.58%   |
| 6.4.11-arch2-1             | 1        | 0.58%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.4.12  | 21       | 12.28%  |
| 6.4.3   | 14       | 8.19%   |
| 6.6.4   | 13       | 7.6%    |
| 6.4.9   | 13       | 7.6%    |
| 6.5.9   | 9        | 5.26%   |
| 6.6.2   | 5        | 2.92%   |
| 6.4.10  | 4        | 2.34%   |
| 6.1.12  | 4        | 2.34%   |
| 6.6.1   | 3        | 1.75%   |
| 6.5.5   | 3        | 1.75%   |
| 6.4.7   | 3        | 1.75%   |
| 6.3.9   | 3        | 1.75%   |
| 5.15.12 | 3        | 1.75%   |
| 6.6.9   | 2        | 1.17%   |
| 6.6.8   | 2        | 1.17%   |
| 6.6.3   | 2        | 1.17%   |
| 6.5.3   | 2        | 1.17%   |
| 6.5.2   | 2        | 1.17%   |
| 6.4.1   | 2        | 1.17%   |
| 6.2.12  | 2        | 1.17%   |
| 5.19.13 | 2        | 1.17%   |
| 5.18.16 | 2        | 1.17%   |
| 5.16.16 | 2        | 1.17%   |
| 5.16.15 | 2        | 1.17%   |
| 5.16.12 | 2        | 1.17%   |
| 6.7.9   | 1        | 0.58%   |
| 6.7.6   | 1        | 0.58%   |
| 6.7.1   | 1        | 0.58%   |
| 6.7.0   | 1        | 0.58%   |
| 6.6.7   | 1        | 0.58%   |
| 6.6.10  | 1        | 0.58%   |
| 6.5.7   | 1        | 0.58%   |
| 6.5.4   | 1        | 0.58%   |
| 6.4.8   | 1        | 0.58%   |
| 6.4.4   | 1        | 0.58%   |
| 6.4.11  | 1        | 0.58%   |
| 6.3.8   | 1        | 0.58%   |
| 6.3.7   | 1        | 0.58%   |
| 6.3.6   | 1        | 0.58%   |
| 6.2.8   | 1        | 0.58%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.4     | 57       | 34.55%  |
| 6.6     | 27       | 16.36%  |
| 6.5     | 18       | 10.91%  |
| 5.15    | 9        | 5.45%   |
| 5.16    | 8        | 4.85%   |
| 6.3     | 6        | 3.64%   |
| 6.2     | 6        | 3.64%   |
| 6.1     | 6        | 3.64%   |
| 5.18    | 6        | 3.64%   |
| 5.19    | 5        | 3.03%   |
| 6.7     | 4        | 2.42%   |
| 5.14    | 4        | 2.42%   |
| 6.0     | 3        | 1.82%   |
| 5.17    | 2        | 1.21%   |
| 5.13    | 2        | 1.21%   |
| 5.12    | 1        | 0.61%   |
| 5.11    | 1        | 0.61%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 154      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| KDE5  | 150      | 96.15%  |
| XFCE  | 3        | 1.92%   |
| GNOME | 3        | 1.92%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 131      | 83.97%  |
| Wayland | 23       | 14.74%  |
| Tty     | 2        | 1.28%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 134      | 84.28%  |
| Unknown | 13       | 8.18%   |
| LightDM | 9        | 5.66%   |
| GDM     | 2        | 1.26%   |
| TDM     | 1        | 0.63%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 59       | 37.58%  |
| de_DE      | 17       | 10.83%  |
| en_GB      | 9        | 5.73%   |
| ru_RU      | 7        | 4.46%   |
| pt_BR      | 7        | 4.46%   |
| fr_FR      | 7        | 4.46%   |
| it_IT      | 5        | 3.18%   |
| es_MX      | 5        | 3.18%   |
| en_CA      | 5        | 3.18%   |
| C          | 5        | 3.18%   |
| tr_TR      | 4        | 2.55%   |
| pl_PL      | 4        | 2.55%   |
| en_IN      | 4        | 2.55%   |
| de_AT      | 3        | 1.91%   |
| hu_HU      | 2        | 1.27%   |
| es_ES      | 2        | 1.27%   |
| en_AU      | 2        | 1.27%   |
| zh_HK      | 1        | 0.64%   |
| sv_SE      | 1        | 0.64%   |
| es_PE      | 1        | 0.64%   |
| es_AR      | 1        | 0.64%   |
| en_ZA      | 1        | 0.64%   |
| el_GR@euro | 1        | 0.64%   |
| el_GR      | 1        | 0.64%   |
| cs_CZ      | 1        | 0.64%   |
| bg_BG      | 1        | 0.64%   |
| ba_RU      | 1        | 0.64%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 111      | 71.61%  |
| BIOS | 44       | 28.39%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 65       | 41.14%  |
| Btrfs   | 61       | 38.61%  |
| Xfs     | 25       | 15.82%  |
| Overlay | 6        | 3.8%    |
| Nilfs2  | 1        | 0.63%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 123      | 79.35%  |
| MBR     | 19       | 12.26%  |
| Unknown | 13       | 8.39%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 99       | 62.66%  |
| Yes       | 59       | 37.34%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 85       | 55.19%  |
| Yes       | 69       | 44.81%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 49       | 31.82%  |
| MSI                 | 24       | 15.58%  |
| Gigabyte Technology | 18       | 11.69%  |
| Dell                | 13       | 8.44%   |
| Hewlett-Packard     | 12       | 7.79%   |
| ASRock              | 12       | 7.79%   |
| Acer                | 6        | 3.9%    |
| Pegatron            | 3        | 1.95%   |
| ECS                 | 3        | 1.95%   |
| Win Element         | 2        | 1.3%    |
| Lenovo              | 2        | 1.3%    |
| Intel               | 2        | 1.3%    |
| Huanan              | 2        | 1.3%    |
| Unknown             | 2        | 1.3%    |
| Medion              | 1        | 0.65%   |
| JINGSHA             | 1        | 0.65%   |
| Biostar             | 1        | 0.65%   |
| BESSTAR Tech        | 1        | 0.65%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Dell OptiPlex 9020             | 4        | 2.6%    |
| Dell OptiPlex 7010             | 4        | 2.6%    |
| MSI MS-7C37                    | 3        | 1.95%   |
| Unknown                        | 3        | 1.95%   |
| Win Element M9                 | 2        | 1.3%    |
| MSI MS-7971                    | 2        | 1.3%    |
| Dell Studio XPS 8100           | 2        | 1.3%    |
| ASUS TUF Gaming X570-PLUS      | 2        | 1.3%    |
| ASUS PRIME B450M-A II          | 2        | 1.3%    |
| ASUS PRIME A320M-K             | 2        | 1.3%    |
| Pegatron p7-1010a              | 1        | 0.65%   |
| Pegatron p6-2026               | 1        | 0.65%   |
| Pegatron 20-b010               | 1        | 0.65%   |
| MSI MS-7D22                    | 1        | 0.65%   |
| MSI MS-7C96                    | 1        | 0.65%   |
| MSI MS-7C94                    | 1        | 0.65%   |
| MSI MS-7C91                    | 1        | 0.65%   |
| MSI MS-7C52                    | 1        | 0.65%   |
| MSI MS-7B61                    | 1        | 0.65%   |
| MSI MS-7B12                    | 1        | 0.65%   |
| MSI MS-7A70                    | 1        | 0.65%   |
| MSI MS-7A34                    | 1        | 0.65%   |
| MSI MS-7916                    | 1        | 0.65%   |
| MSI MS-7845                    | 1        | 0.65%   |
| MSI MS-7823                    | 1        | 0.65%   |
| MSI MS-7817                    | 1        | 0.65%   |
| MSI MS-7815                    | 1        | 0.65%   |
| MSI MS-7758                    | 1        | 0.65%   |
| MSI MS-7693                    | 1        | 0.65%   |
| MSI MS-7623                    | 1        | 0.65%   |
| MSI MS-7592                    | 1        | 0.65%   |
| MSI Gaming                     | 1        | 0.65%   |
| Medion E63007                  | 1        | 0.65%   |
| Lenovo ThinkCentre M58 3231W2Y | 1        | 0.65%   |
| Lenovo 3302F3U                 | 1        | 0.65%   |
| Intel X99                      | 1        | 0.65%   |
| Intel B75                      | 1        | 0.65%   |
| Huanan X99-TF                  | 1        | 0.65%   |
| Huanan X99-F8                  | 1        | 0.65%   |
| HP Z230 SFF Workstation        | 1        | 0.65%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS ROG           | 15       | 9.74%   |
| ASUS TUF           | 10       | 6.49%   |
| ASUS PRIME         | 10       | 6.49%   |
| Dell OptiPlex      | 9        | 5.84%   |
| Acer Aspire        | 5        | 3.25%   |
| MSI MS-7C37        | 3        | 1.95%   |
| Dell Studio        | 3        | 1.95%   |
| Unknown            | 3        | 1.95%   |
| Win Element M9     | 2        | 1.3%    |
| MSI MS-7971        | 2        | 1.3%    |
| HP Pavilion        | 2        | 1.3%    |
| Gigabyte Z790      | 2        | 1.3%    |
| Gigabyte X570      | 2        | 1.3%    |
| Gigabyte B450M     | 2        | 1.3%    |
| ASUS M5A99X        | 2        | 1.3%    |
| ASRock B450        | 2        | 1.3%    |
| Pegatron p7-1010a  | 1        | 0.65%   |
| Pegatron p6-2026   | 1        | 0.65%   |
| Pegatron 20-b010   | 1        | 0.65%   |
| MSI MS-7D22        | 1        | 0.65%   |
| MSI MS-7C96        | 1        | 0.65%   |
| MSI MS-7C94        | 1        | 0.65%   |
| MSI MS-7C91        | 1        | 0.65%   |
| MSI MS-7C52        | 1        | 0.65%   |
| MSI MS-7B61        | 1        | 0.65%   |
| MSI MS-7B12        | 1        | 0.65%   |
| MSI MS-7A70        | 1        | 0.65%   |
| MSI MS-7A34        | 1        | 0.65%   |
| MSI MS-7916        | 1        | 0.65%   |
| MSI MS-7845        | 1        | 0.65%   |
| MSI MS-7823        | 1        | 0.65%   |
| MSI MS-7817        | 1        | 0.65%   |
| MSI MS-7815        | 1        | 0.65%   |
| MSI MS-7758        | 1        | 0.65%   |
| MSI MS-7693        | 1        | 0.65%   |
| MSI MS-7623        | 1        | 0.65%   |
| MSI MS-7592        | 1        | 0.65%   |
| MSI Gaming         | 1        | 0.65%   |
| Medion E63007      | 1        | 0.65%   |
| Lenovo ThinkCentre | 1        | 0.65%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 19       | 12.34%  |
| 2019 | 19       | 12.34%  |
| 2018 | 17       | 11.04%  |
| 2014 | 15       | 9.74%   |
| 2021 | 14       | 9.09%   |
| 2017 | 13       | 8.44%   |
| 2013 | 10       | 6.49%   |
| 2015 | 8        | 5.19%   |
| 2011 | 8        | 5.19%   |
| 2023 | 6        | 3.9%    |
| 2012 | 6        | 3.9%    |
| 2016 | 5        | 3.25%   |
| 2009 | 5        | 3.25%   |
| 2010 | 4        | 2.6%    |
| 2022 | 3        | 1.95%   |
| 2008 | 1        | 0.65%   |
| 2007 | 1        | 0.65%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 154      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 154      | 99.35%  |
| Enabled  | 1        | 0.65%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 154      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 57       | 36.77%  |
| 32.01-64.0  | 37       | 23.87%  |
| 8.01-16.0   | 25       | 16.13%  |
| 4.01-8.0    | 19       | 12.26%  |
| 3.01-4.0    | 7        | 4.52%   |
| 64.01-256.0 | 6        | 3.87%   |
| 24.01-32.0  | 4        | 2.58%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 55       | 32.35%  |
| 2.01-3.0   | 49       | 28.82%  |
| 4.01-8.0   | 27       | 15.88%  |
| 3.01-4.0   | 20       | 11.76%  |
| 8.01-16.0  | 8        | 4.71%   |
| 16.01-24.0 | 7        | 4.12%   |
| 0.51-1.0   | 2        | 1.18%   |
| 0.01-0.5   | 2        | 1.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 50       | 31.65%  |
| 2      | 44       | 27.85%  |
| 3      | 33       | 20.89%  |
| 4      | 13       | 8.23%   |
| 5      | 10       | 6.33%   |
| 6      | 4        | 2.53%   |
| 8      | 2        | 1.27%   |
| 7      | 2        | 1.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 109      | 70.32%  |
| Yes       | 46       | 29.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 153      | 99.35%  |
| No        | 1        | 0.65%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 85       | 54.49%  |
| No        | 71       | 45.51%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 83       | 53.21%  |
| Yes       | 73       | 46.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 33       | 21.15%  |
| Germany      | 17       | 10.9%   |
| Brazil       | 9        | 5.77%   |
| Russia       | 8        | 5.13%   |
| France       | 7        | 4.49%   |
| Canada       | 7        | 4.49%   |
| Poland       | 6        | 3.85%   |
| UK           | 5        | 3.21%   |
| Mexico       | 5        | 3.21%   |
| Italy        | 5        | 3.21%   |
| Turkey       | 4        | 2.56%   |
| India        | 4        | 2.56%   |
| Spain        | 3        | 1.92%   |
| Netherlands  | 3        | 1.92%   |
| Austria      | 3        | 1.92%   |
| Argentina    | 3        | 1.92%   |
| Romania      | 2        | 1.28%   |
| Pakistan     | 2        | 1.28%   |
| Hungary      | 2        | 1.28%   |
| Greece       | 2        | 1.28%   |
| Czechia      | 2        | 1.28%   |
| Bulgaria     | 2        | 1.28%   |
| Bahrain      | 2        | 1.28%   |
| Australia    | 2        | 1.28%   |
| Venezuela    | 1        | 0.64%   |
| Thailand     | 1        | 0.64%   |
| Switzerland  | 1        | 0.64%   |
| Sweden       | 1        | 0.64%   |
| South Africa | 1        | 0.64%   |
| Puerto Rico  | 1        | 0.64%   |
| Portugal     | 1        | 0.64%   |
| Philippines  | 1        | 0.64%   |
| Peru         | 1        | 0.64%   |
| Lebanon      | 1        | 0.64%   |
| Iran         | 1        | 0.64%   |
| Cyprus       | 1        | 0.64%   |
| Colombia     | 1        | 0.64%   |
| China        | 1        | 0.64%   |
| Belgium      | 1        | 0.64%   |
| Belarus      | 1        | 0.64%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Warsaw                 | 3        | 1.89%   |
| Red Lake               | 3        | 1.89%   |
| St Petersburg          | 2        | 1.26%   |
| Portland               | 2        | 1.26%   |
| Niterói               | 2        | 1.26%   |
| Mexico City            | 2        | 1.26%   |
| Krasnodar              | 2        | 1.26%   |
| Hamburg                | 2        | 1.26%   |
| Cumming                | 2        | 1.26%   |
| Braunschweig           | 2        | 1.26%   |
| Berlin                 | 2        | 1.26%   |
| Amsterdam              | 2        | 1.26%   |
| Zell am See            | 1        | 0.63%   |
| York                   | 1        | 0.63%   |
| Wroclaw                | 1        | 0.63%   |
| Wrexham                | 1        | 0.63%   |
| Wolfville              | 1        | 0.63%   |
| Wesel                  | 1        | 0.63%   |
| Wells                  | 1        | 0.63%   |
| Vredenburg             | 1        | 0.63%   |
| Voronezh               | 1        | 0.63%   |
| Valparaiso de Goias    | 1        | 0.63%   |
| Tuxtla Gutiérrez      | 1        | 0.63%   |
| Termas de Rio Hondo    | 1        | 0.63%   |
| Teresina               | 1        | 0.63%   |
| Tehran                 | 1        | 0.63%   |
| Stow                   | 1        | 0.63%   |
| St Louis               | 1        | 0.63%   |
| Springfield            | 1        | 0.63%   |
| Sonora                 | 1        | 0.63%   |
| Sofia                  | 1        | 0.63%   |
| Shanghai               | 1        | 0.63%   |
| Shadrinsk              | 1        | 0.63%   |
| Sarcelles              | 1        | 0.63%   |
| Sao Paulo              | 1        | 0.63%   |
| Santiago de Compostela | 1        | 0.63%   |
| Santa Rosa             | 1        | 0.63%   |
| Sant Boi de Llobregat  | 1        | 0.63%   |
| Sankt Florian am Inn   | 1        | 0.63%   |
| Salt Lake City         | 1        | 0.63%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| WDC                          | 51       | 71     | 15.79%  |
| Seagate                      | 49       | 70     | 15.17%  |
| Samsung Electronics          | 47       | 81     | 14.55%  |
| Sandisk                      | 24       | 32     | 7.43%   |
| Kingston                     | 21       | 26     | 6.5%    |
| Crucial                      | 16       | 24     | 4.95%   |
| Toshiba                      | 13       | 16     | 4.02%   |
| Micron/Crucial Technology    | 9        | 11     | 2.79%   |
| Unknown                      | 8        | 9      | 2.48%   |
| Phison Electronics           | 6        | 8      | 1.86%   |
| Hitachi                      | 5        | 5      | 1.55%   |
| HGST                         | 5        | 5      | 1.55%   |
| ADATA Technology             | 5        | 5      | 1.55%   |
| SK hynix                     | 4        | 5      | 1.24%   |
| China                        | 4        | 4      | 1.24%   |
| Realtek Semiconductor        | 3        | 4      | 0.93%   |
| MAXIO Technology (Hangzhou)  | 3        | 3      | 0.93%   |
| Intenso                      | 3        | 5      | 0.93%   |
| Intel                        | 3        | 5      | 0.93%   |
| A-DATA Technology            | 3        | 3      | 0.93%   |
| SPCC                         | 2        | 3      | 0.62%   |
| Silicon Motion               | 2        | 4      | 0.62%   |
| PNY                          | 2        | 2      | 0.62%   |
| Phison                       | 2        | 2      | 0.62%   |
| Mushkin                      | 2        | 2      | 0.62%   |
| Micron Technology            | 2        | 3      | 0.62%   |
| Lexar                        | 2        | 2      | 0.62%   |
| KingSpec                     | 2        | 2      | 0.62%   |
| ASMedia                      | 2        | 2      | 0.62%   |
| XrayDisk                     | 1        | 2      | 0.31%   |
| XPG                          | 1        | 1      | 0.31%   |
| Transcend                    | 1        | 1      | 0.31%   |
| Team                         | 1        | 1      | 0.31%   |
| SSK                          | 1        | 1      | 0.31%   |
| Shenzhen Longsys Electronics | 1        | 1      | 0.31%   |
| SABRENT                      | 1        | 1      | 0.31%   |
| Patriot                      | 1        | 1      | 0.31%   |
| OCZ                          | 1        | 1      | 0.31%   |
| Maxtor                       | 1        | 1      | 0.31%   |
| Maxone                       | 1        | 1      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB               | 8        | 2.17%   |
| Crucial CT500MX500SSD1 500GB                                    | 8        | 2.17%   |
| Unknown SD/MMC/MS PRO 128GB                                     | 6        | 1.63%   |
| Samsung SSD 860 EVO 500GB                                       | 6        | 1.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB              | 5        | 1.36%   |
| Kingston SA400S37960G 960GB SSD                                 | 5        | 1.36%   |
| Seagate ST2000DM006-2DM164 2TB                                  | 4        | 1.08%   |
| Seagate ST1000DM010-2EP102 1TB                                  | 4        | 1.08%   |
| Seagate ST1000DM003-1SB102 1TB                                  | 4        | 1.08%   |
| Kingston SA400S37240G 240GB SSD                                 | 4        | 1.08%   |
| WDC WD20EZBX-00AYRA0 2TB                                        | 3        | 0.81%   |
| WDC WD10EZEX-60M2NA0 1TB                                        | 3        | 0.81%   |
| Toshiba DT01ACA300 3TB                                          | 3        | 0.81%   |
| Sandisk WD Blue SN570 500GB                                     | 3        | 0.81%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB                | 3        | 0.81%   |
| Samsung SSD 850 EVO 250GB                                       | 3        | 0.81%   |
| Realtek RTS5763DL NVMe SSD Controller 256GB                     | 3        | 0.81%   |
| Phison PS5013 E13 NVMe Controller 512GB                         | 3        | 0.81%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                             | 3        | 0.81%   |
| Micron/Crucial CT2000P5PSSD8 2TB                                | 3        | 0.81%   |
| Crucial CT1000MX500SSD1 1TB                                     | 3        | 0.81%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 1TB | 3        | 0.81%   |
| WDC WD10EZEX-60WN4A0 1TB                                        | 2        | 0.54%   |
| WDC WD10EZEX-22MFCA0 1TB                                        | 2        | 0.54%   |
| WDC WD10EZEX-21WN4A0 1TB                                        | 2        | 0.54%   |
| WDC WD10EZEX-08WN4A0 1TB                                        | 2        | 0.54%   |
| Toshiba MQ01ABD100 1TB                                          | 2        | 0.54%   |
| SPCC Solid State Disk 256GB                                     | 2        | 0.54%   |
| SK hynix SHPP41-2000GM 2TB                                      | 2        | 0.54%   |
| Seagate ST500DM002-1BD142 500GB                                 | 2        | 0.54%   |
| Seagate ST3500312CS 500GB                                       | 2        | 0.54%   |
| Seagate ST250DM000-1BD141 250GB                                 | 2        | 0.54%   |
| Seagate ST2000DM008-2FR102 2TB                                  | 2        | 0.54%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                              | 2        | 0.54%   |
| Seagate ST1000DM003-1ER162 1TB                                  | 2        | 0.54%   |
| Seagate ST1000DM003-1CH162 1TB                                  | 2        | 0.54%   |
| Seagate Expansion HDD 12TB                                      | 2        | 0.54%   |
| Sandisk WD_BLACK SN770 1TB                                      | 2        | 0.54%   |
| Sandisk WD Blue SN550 NVMe SSD 2TB                              | 2        | 0.54%   |
| SanDisk NVMe SSD Drive 500GB                                    | 2        | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 49       | 70     | 35.77%  |
| WDC                 | 44       | 60     | 32.12%  |
| Toshiba             | 13       | 16     | 9.49%   |
| Unknown             | 6        | 6      | 4.38%   |
| Samsung Electronics | 6        | 6      | 4.38%   |
| Hitachi             | 5        | 5      | 3.65%   |
| HGST                | 5        | 5      | 3.65%   |
| Intenso             | 3        | 5      | 2.19%   |
| ASMedia             | 2        | 2      | 1.46%   |
| SABRENT             | 1        | 1      | 0.73%   |
| Maxtor              | 1        | 1      | 0.73%   |
| Maxone              | 1        | 1      | 0.73%   |
| JMicron Technology  | 1        | 1      | 0.73%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 24       | 33     | 22.64%  |
| Kingston            | 18       | 23     | 16.98%  |
| Crucial             | 16       | 24     | 15.09%  |
| WDC                 | 8        | 8      | 7.55%   |
| SanDisk             | 8        | 8      | 7.55%   |
| China               | 4        | 4      | 3.77%   |
| SPCC                | 2        | 3      | 1.89%   |
| PNY                 | 2        | 2      | 1.89%   |
| Mushkin             | 2        | 2      | 1.89%   |
| Lexar               | 2        | 2      | 1.89%   |
| KingSpec            | 2        | 2      | 1.89%   |
| A-DATA Technology   | 2        | 2      | 1.89%   |
| XrayDisk            | 1        | 2      | 0.94%   |
| Transcend           | 1        | 1      | 0.94%   |
| Team                | 1        | 1      | 0.94%   |
| SSK                 | 1        | 1      | 0.94%   |
| Patriot             | 1        | 1      | 0.94%   |
| OCZ                 | 1        | 1      | 0.94%   |
| Micron Technology   | 1        | 1      | 0.94%   |
| LITEONIT            | 1        | 1      | 0.94%   |
| LITEON              | 1        | 2      | 0.94%   |
| Leven               | 1        | 1      | 0.94%   |
| Hewlett-Packard     | 1        | 1      | 0.94%   |
| Gigabyte Technology | 1        | 1      | 0.94%   |
| Emtec               | 1        | 1      | 0.94%   |
| Corsair             | 1        | 1      | 0.94%   |
| ASMT                | 1        | 1      | 0.94%   |
| 2-Power             | 1        | 1      | 0.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 105      | 179    | 39.77%  |
| SSD  | 82       | 131    | 31.06%  |
| NVMe | 75       | 127    | 28.41%  |
| MMC  | 2        | 3      | 0.76%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 133      | 282    | 57.83%  |
| NVMe | 75       | 127    | 32.61%  |
| SAS  | 20       | 28     | 8.7%    |
| MMC  | 2        | 3      | 0.87%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 96       | 144    | 45.28%  |
| 0.51-1.0   | 64       | 92     | 30.19%  |
| 1.01-2.0   | 26       | 33     | 12.26%  |
| 4.01-10.0  | 9        | 15     | 4.25%   |
| 2.01-3.0   | 8        | 10     | 3.77%   |
| 3.01-4.0   | 7        | 10     | 3.3%    |
| 10.01-20.0 | 2        | 6      | 0.94%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 32       | 19.88%  |
| 251-500        | 28       | 17.39%  |
| 1001-2000      | 28       | 17.39%  |
| 101-250        | 25       | 15.53%  |
| 501-1000       | 25       | 15.53%  |
| 51-100         | 6        | 3.73%   |
| 2001-3000      | 5        | 3.11%   |
| 21-50          | 4        | 2.48%   |
| 1-20           | 4        | 2.48%   |
| Unknown        | 4        | 2.48%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 61       | 36.75%  |
| 21-50          | 24       | 14.46%  |
| 101-250        | 21       | 12.65%  |
| 51-100         | 21       | 12.65%  |
| 251-500        | 10       | 6.02%   |
| 501-1000       | 10       | 6.02%   |
| More than 3000 | 7        | 4.22%   |
| 1001-2000      | 5        | 3.01%   |
| Unknown        | 4        | 2.41%   |
| 2001-3000      | 3        | 1.81%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Seagate ST1000DM010-2EP102 1TB     | 2        | 2      | 4.44%   |
| Seagate ST1000DM003-1ER162 1TB     | 2        | 4      | 4.44%   |
| ASMedia AS2115 8TB                 | 2        | 2      | 4.44%   |
| WDC WD5000AAKX-60U6AA0 500GB       | 1        | 1      | 2.22%   |
| WDC WD3200AAJS-08L7A0 320GB        | 1        | 1      | 2.22%   |
| WDC WD20EARX-00PASB0 2TB           | 1        | 1      | 2.22%   |
| WDC WD1600AAJS-00L7A0 160GB        | 1        | 1      | 2.22%   |
| WDC WD10EZEX-60M2NA0 1TB           | 1        | 1      | 2.22%   |
| WDC WD10EZEX-08WN4A0 1TB           | 1        | 1      | 2.22%   |
| WDC WD10EADS-00M2B0 1TB            | 1        | 1      | 2.22%   |
| WDC WD1002FAEX-00Z3A0 1TB          | 1        | 2      | 2.22%   |
| Toshiba MQ01ABD100 1TB             | 1        | 1      | 2.22%   |
| Toshiba MQ01ABD050 500GB           | 1        | 1      | 2.22%   |
| Toshiba MK4058GSX 400GB            | 1        | 1      | 2.22%   |
| Seagate ST9500420AS 500GB          | 1        | 1      | 2.22%   |
| Seagate ST9500325AS 500GB          | 1        | 1      | 2.22%   |
| Seagate ST500DM009-2F110A 500GB    | 1        | 1      | 2.22%   |
| Seagate ST500DM002-1BD142 500GB    | 1        | 1      | 2.22%   |
| Seagate ST3500312CS 500GB          | 1        | 1      | 2.22%   |
| Seagate ST3320418AS 320GB          | 1        | 1      | 2.22%   |
| Seagate ST320LT012-9WS14C 320GB    | 1        | 2      | 2.22%   |
| Seagate ST31000524AS 1TB           | 1        | 1      | 2.22%   |
| Seagate ST2000VX000-1CU164 2TB     | 1        | 1      | 2.22%   |
| Seagate ST2000DM006-2DM164 2TB     | 1        | 1      | 2.22%   |
| Seagate ST2000DM001-1CH164 2TB     | 1        | 1      | 2.22%   |
| Seagate ST2000DL003-9VT166 2TB     | 1        | 1      | 2.22%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 1      | 2.22%   |
| Seagate ST1000DM003-1SB10C 1TB     | 1        | 1      | 2.22%   |
| Samsung Electronics HD103SJ 1TB    | 1        | 1      | 2.22%   |
| SABRENT Disk 1TB                   | 1        | 1      | 2.22%   |
| Maxtor STM3160215AS 160GB          | 1        | 1      | 2.22%   |
| Kingston SV300S37A120G 120GB SSD   | 1        | 1      | 2.22%   |
| Kingston SUV400S37240G 240GB SSD   | 1        | 1      | 2.22%   |
| Kingston SA400S37480G 480GB SSD    | 1        | 1      | 2.22%   |
| Hitachi HTS725050A9A364 500GB      | 1        | 1      | 2.22%   |
| Hitachi HDS721010CLA330 1TB        | 1        | 1      | 2.22%   |
| Hitachi HCP725050GLA380 500GB      | 1        | 1      | 2.22%   |
| HGST HDS724040ALE640 4TB           | 1        | 1      | 2.22%   |
| Crucial CT1050MX300SSD1 1050GB     | 1        | 1      | 2.22%   |
| Corsair Force GT 240GB SSD         | 1        | 1      | 2.22%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 18       | 21     | 40.91%  |
| WDC                 | 8        | 9      | 18.18%  |
| Kingston            | 3        | 3      | 6.82%   |
| Hitachi             | 3        | 3      | 6.82%   |
| Toshiba             | 2        | 3      | 4.55%   |
| ASMedia             | 2        | 2      | 4.55%   |
| Samsung Electronics | 1        | 1      | 2.27%   |
| SABRENT             | 1        | 1      | 2.27%   |
| Maxtor              | 1        | 1      | 2.27%   |
| HGST                | 1        | 1      | 2.27%   |
| Crucial             | 1        | 1      | 2.27%   |
| Corsair             | 1        | 1      | 2.27%   |
| China               | 1        | 1      | 2.27%   |
| ADATA Technology    | 1        | 1      | 2.27%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 18       | 21     | 48.65%  |
| WDC                 | 8        | 9      | 21.62%  |
| Hitachi             | 3        | 3      | 8.11%   |
| Toshiba             | 2        | 3      | 5.41%   |
| ASMedia             | 2        | 2      | 5.41%   |
| Samsung Electronics | 1        | 1      | 2.7%    |
| SABRENT             | 1        | 1      | 2.7%    |
| Maxtor              | 1        | 1      | 2.7%    |
| HGST                | 1        | 1      | 2.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 36       | 42     | 83.72%  |
| SSD  | 6        | 6      | 13.95%  |
| NVMe | 1        | 1      | 2.33%   |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 130      | 325    | 64.36%  |
| Malfunc  | 42       | 49     | 20.79%  |
| Detected | 30       | 66     | 14.85%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 96       | 37.21%  |
| AMD                          | 59       | 22.87%  |
| SanDisk                      | 20       | 7.75%   |
| Samsung Electronics          | 20       | 7.75%   |
| ASMedia Technology           | 14       | 5.43%   |
| Micron/Crucial Technology    | 9        | 3.49%   |
| Phison Electronics           | 8        | 3.1%    |
| ADATA Technology             | 6        | 2.33%   |
| SK hynix                     | 4        | 1.55%   |
| Realtek Semiconductor        | 4        | 1.55%   |
| Kingston Technology Company  | 4        | 1.55%   |
| MAXIO Technology (Hangzhou)  | 3        | 1.16%   |
| JMicron Technology           | 3        | 1.16%   |
| Silicon Motion               | 2        | 0.78%   |
| Micron Technology            | 2        | 0.78%   |
| VIA Technologies             | 1        | 0.39%   |
| Shenzhen Longsys Electronics | 1        | 0.39%   |
| Marvell Technology Group     | 1        | 0.39%   |
| KIOXIA                       | 1        | 0.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 37       | 12.46%  |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 14       | 4.71%   |
| AMD 400 Series Chipset SATA Controller                                         | 14       | 4.71%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 12       | 4.04%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 11       | 3.7%    |
| AMD 500 Series Chipset SATA Controller                                         | 11       | 3.7%    |
| Intel SATA Controller [RAID mode]                                              | 10       | 3.37%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 10       | 3.37%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 10       | 3.37%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 9        | 3.03%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 7        | 2.36%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 5        | 1.68%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5        | 1.68%   |
| AMD FCH SATA Controller D                                                      | 5        | 1.68%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 4        | 1.35%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 3        | 1.01%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 3        | 1.01%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 3        | 1.01%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 3        | 1.01%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3        | 1.01%   |
| Realtek RTS5762 NVMe SSD Controller                                            | 3        | 1.01%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 3        | 1.01%   |
| Phison E12 NVMe Controller                                                     | 3        | 1.01%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 3        | 1.01%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 3        | 1.01%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 3        | 1.01%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 3        | 1.01%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3        | 1.01%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3        | 1.01%   |
| AMD 300 Series Chipset SATA Controller                                         | 3        | 1.01%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 3        | 1.01%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 2        | 0.67%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                     | 2        | 0.67%   |
| SanDisk WD Black NVMe SSD                                                      | 2        | 0.67%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 2        | 0.67%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 2        | 0.67%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                      | 2        | 0.67%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 2        | 0.67%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2        | 0.67%   |
| Intel SSD 660P Series                                                          | 2        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 136      | 57.87%  |
| NVMe | 75       | 31.91%  |
| RAID | 12       | 5.11%   |
| IDE  | 12       | 5.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 95       | 61.69%  |
| AMD    | 59       | 38.31%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor          | 6        | 3.85%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 4        | 2.56%   |
| AMD Ryzen 5 3600 6-Core Processor           | 4        | 2.56%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 3        | 1.92%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 3        | 1.92%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 1.92%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 3        | 1.92%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 3        | 1.92%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 3        | 1.92%   |
| AMD Ryzen 7 5800X3D 8-Core Processor        | 3        | 1.92%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 3        | 1.92%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 3        | 1.92%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 3        | 1.92%   |
| AMD Ryzen 5 5500                            | 3        | 1.92%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 3        | 1.92%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 3        | 1.92%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 2        | 1.28%   |
| Intel N100                                  | 2        | 1.28%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 1.28%   |
| Intel Core i7 CPU 870 @ 2.93GHz             | 2        | 1.28%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 2        | 1.28%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 1.28%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 1.28%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 1.28%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 1.28%   |
| Intel 12th Gen Core i9-12900K               | 2        | 1.28%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 2        | 1.28%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 2        | 1.28%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 2        | 1.28%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1        | 0.64%   |
| Intel Xeon CPU E5-2695 v3 @ 2.30GHz         | 1        | 0.64%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz          | 1        | 0.64%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz          | 1        | 0.64%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz         | 1        | 0.64%   |
| Intel Pentium CPU J2900 @ 2.41GHz           | 1        | 0.64%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 1        | 0.64%   |
| Intel Pentium CPU G3260T @ 2.90GHz          | 1        | 0.64%   |
| Intel Genuine CPU 0000 @ 2.10GHz            | 1        | 0.64%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 0.64%   |
| Intel Core i9-10900X CPU @ 3.70GHz          | 1        | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 28       | 18.06%  |
| AMD Ryzen 5            | 28       | 18.06%  |
| Intel Core i7          | 26       | 16.77%  |
| AMD Ryzen 7            | 16       | 10.32%  |
| Intel Core i3          | 12       | 7.74%   |
| Other                  | 10       | 6.45%   |
| Intel Xeon             | 7        | 4.52%   |
| AMD FX                 | 4        | 2.58%   |
| Intel Pentium          | 3        | 1.94%   |
| AMD Ryzen 3            | 3        | 1.94%   |
| Intel Core i9          | 2        | 1.29%   |
| Intel Core 2 Quad      | 2        | 1.29%   |
| Intel Core 2 Duo       | 2        | 1.29%   |
| Intel Celeron          | 2        | 1.29%   |
| AMD Ryzen 9            | 2        | 1.29%   |
| AMD A8                 | 2        | 1.29%   |
| Intel Genuine          | 1        | 0.65%   |
| AMD Ryzen Threadripper | 1        | 0.65%   |
| AMD E1                 | 1        | 0.65%   |
| AMD Athlon II X3       | 1        | 0.65%   |
| AMD Athlon             | 1        | 0.65%   |
| AMD A4                 | 1        | 0.65%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 62       | 40%     |
| 6      | 39       | 25.16%  |
| 8      | 21       | 13.55%  |
| 2      | 17       | 10.97%  |
| 16     | 5        | 3.23%   |
| 12     | 4        | 2.58%   |
| 3      | 3        | 1.94%   |
| 10     | 2        | 1.29%   |
| 28     | 1        | 0.65%   |
| 24     | 1        | 0.65%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 152      | 98.7%   |
| 2      | 2        | 1.3%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 106      | 68.83%  |
| 1      | 48       | 31.17%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 154      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 80       | 50%     |
| 0x08701021 | 8        | 5%      |
| 0x506e3    | 5        | 3.13%   |
| 0x906ea    | 4        | 2.5%    |
| 0x0a50000c | 4        | 2.5%    |
| 0x0a201025 | 4        | 2.5%    |
| 0x0a201016 | 4        | 2.5%    |
| 0x08701030 | 4        | 2.5%    |
| 0x0800820d | 4        | 2.5%    |
| 0x306c3    | 3        | 1.88%   |
| 0x0a50000d | 3        | 1.88%   |
| 0x0a20120a | 3        | 1.88%   |
| 0x08108109 | 3        | 1.88%   |
| 0x306a9    | 2        | 1.25%   |
| 0x106e5    | 2        | 1.25%   |
| 0x0a201204 | 2        | 1.25%   |
| 0x0810100b | 2        | 1.25%   |
| 0x08001138 | 2        | 1.25%   |
| 0xa0653    | 1        | 0.63%   |
| 0x906ed    | 1        | 0.63%   |
| 0x906eb    | 1        | 0.63%   |
| 0x906e9    | 1        | 0.63%   |
| 0x306f2    | 1        | 0.63%   |
| 0x20655    | 1        | 0.63%   |
| 0x1067a    | 1        | 0.63%   |
| 0x0a601206 | 1        | 0.63%   |
| 0x0a601203 | 1        | 0.63%   |
| 0x0a50000f | 1        | 0.63%   |
| 0x08701013 | 1        | 0.63%   |
| 0x08600106 | 1        | 0.63%   |
| 0x08101013 | 1        | 0.63%   |
| 0x0700010f | 1        | 0.63%   |
| 0x0700010b | 1        | 0.63%   |
| 0x0600611a | 1        | 0.63%   |
| 0x06000852 | 1        | 0.63%   |
| 0x06000822 | 1        | 0.63%   |
| 0x0600081c | 1        | 0.63%   |
| 0x0500010d | 1        | 0.63%   |
| 0x010000c8 | 1        | 0.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 20       | 12.9%   |
| Haswell          | 20       | 12.9%   |
| KabyLake         | 17       | 10.97%  |
| Zen 2            | 14       | 9.03%   |
| Skylake          | 11       | 7.1%    |
| IvyBridge        | 11       | 7.1%    |
| Zen+             | 9        | 5.81%   |
| SandyBridge      | 7        | 4.52%   |
| Zen              | 6        | 3.87%   |
| Alderlake Hybrid | 6        | 3.87%   |
| Piledriver       | 5        | 3.23%   |
| Nehalem          | 5        | 3.23%   |
| CometLake        | 4        | 2.58%   |
| Penryn           | 3        | 1.94%   |
| Silvermont       | 2        | 1.29%   |
| Icelake          | 2        | 1.29%   |
| Gracemont        | 2        | 1.29%   |
| Core             | 2        | 1.29%   |
| Unknown          | 2        | 1.29%   |
| Westmere         | 1        | 0.65%   |
| K10              | 1        | 0.65%   |
| Jaguar           | 1        | 0.65%   |
| Goldmont plus    | 1        | 0.65%   |
| Excavator        | 1        | 0.65%   |
| Broadwell        | 1        | 0.65%   |
| Bobcat           | 1        | 0.65%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 73       | 45.06%  |
| AMD               | 57       | 35.19%  |
| Intel             | 31       | 19.14%  |
| ASPEED Technology | 1        | 0.62%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7        | 4.27%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 7        | 4.27%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 6        | 3.66%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 6        | 3.66%   |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                    | 6        | 3.66%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 5        | 3.05%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5        | 3.05%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 2.44%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 2.44%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4        | 2.44%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4        | 2.44%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 3        | 1.83%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 3        | 1.83%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 3        | 1.83%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 1.83%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 1.83%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 3        | 1.83%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 3        | 1.83%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 1.22%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 1.22%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 1.22%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 1.22%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 1.22%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 1.22%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 1.22%   |
| Nvidia GF108 [GeForce GT 730]                                               | 2        | 1.22%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 1.22%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 2        | 1.22%   |
| Nvidia AD102 [GeForce RTX 4090]                                             | 2        | 1.22%   |
| Intel Alder Lake-N [UHD Graphics]                                           | 2        | 1.22%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 1.22%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.22%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 1.22%   |
| AMD Raphael                                                                 | 2        | 1.22%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2        | 1.22%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 1.22%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 1.22%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.61%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.61%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 65       | 41.94%  |
| 1 x AMD         | 56       | 36.13%  |
| 1 x Intel       | 25       | 16.13%  |
| Intel + Nvidia  | 4        | 2.58%   |
| 2 x Nvidia      | 2        | 1.29%   |
| 2 x Intel       | 1        | 0.65%   |
| Nvidia + ASPEED | 1        | 0.65%   |
| AMD + Nvidia    | 1        | 0.65%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 117      | 75%     |
| Proprietary | 36       | 23.08%  |
| Unknown     | 3        | 1.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 40       | 25.48%  |
| 7.01-8.0   | 36       | 22.93%  |
| 1.01-2.0   | 27       | 17.2%   |
| 3.01-4.0   | 18       | 11.46%  |
| 5.01-6.0   | 11       | 7.01%   |
| 8.01-16.0  | 9        | 5.73%   |
| 0.01-0.5   | 8        | 5.1%    |
| 0.51-1.0   | 5        | 3.18%   |
| 16.01-24.0 | 2        | 1.27%   |
| 2.01-3.0   | 1        | 0.64%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 34       | 20.12%  |
| Goldstar             | 18       | 10.65%  |
| Hewlett-Packard      | 17       | 10.06%  |
| Acer                 | 12       | 7.1%    |
| Dell                 | 10       | 5.92%   |
| Ancor Communications | 10       | 5.92%   |
| Unknown              | 9        | 5.33%   |
| AOC                  | 8        | 4.73%   |
| BenQ                 | 6        | 3.55%   |
| ASUSTek Computer     | 6        | 3.55%   |
| Iiyama               | 5        | 2.96%   |
| MSI                  | 4        | 2.37%   |
| Philips              | 3        | 1.78%   |
| Lenovo               | 3        | 1.78%   |
| Gigabyte Technology  | 2        | 1.18%   |
| Fujitsu Siemens      | 2        | 1.18%   |
| Unknown              | 2        | 1.18%   |
| Yeyian               | 1        | 0.59%   |
| Westinghouse         | 1        | 0.59%   |
| Vizio                | 1        | 0.59%   |
| ViewSonic            | 1        | 0.59%   |
| UTV                  | 1        | 0.59%   |
| Sony                 | 1        | 0.59%   |
| Sceptre Tech         | 1        | 0.59%   |
| QIA                  | 1        | 0.59%   |
| Konka                | 1        | 0.59%   |
| Kogan                | 1        | 0.59%   |
| KOC                  | 1        | 0.59%   |
| JRY                  | 1        | 0.59%   |
| Idek Iiyama          | 1        | 0.59%   |
| HKC                  | 1        | 0.59%   |
| Hitachi              | 1        | 0.59%   |
| FOX                  | 1        | 0.59%   |
| Eizo                 | 1        | 0.59%   |
| BOE                  | 1        | 0.59%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch               | 8        | 4.47%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch       | 3        | 1.68%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch       | 2        | 1.12%   |
| Samsung Electronics LCD Monitor SAM0B7C 1920x1080 886x498mm 40.0-inch   | 2        | 1.12%   |
| Hewlett-Packard 2310 HWP288E 1920x1080 510x287mm 23.0-inch              | 2        | 1.12%   |
| Goldstar ULTRAWIDE GSM76FA 2560x1080 531x298mm 24.0-inch                | 2        | 1.12%   |
| Goldstar ULTRAGEAR GSM7766 2560x1440 697x392mm 31.5-inch                | 2        | 1.12%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                   | 2        | 1.12%   |
| Goldstar FULL HD GSM5BDE 1920x1080 480x270mm 21.7-inch                  | 2        | 1.12%   |
| Dell S3221QS DELD107 3840x2160 697x392mm 31.5-inch                      | 2        | 1.12%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                       | 2        | 1.12%   |
| AOC 2963 AOC2963 2560x1080 673x284mm 28.8-inch                          | 2        | 1.12%   |
| Ancor Communications ROG PG348Q ACI3433 3440x1440 798x335mm 34.1-inch   | 2        | 1.12%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch   | 2        | 1.12%   |
| Unknown                                                                 | 2        | 1.12%   |
| Yeyian YMG-4K27-01 YEY2700 3840x2160 600x330mm 27.0-inch                | 1        | 0.56%   |
| Westinghouse SK-32H640G WDE6040 1366x768 709x399mm 32.0-inch            | 1        | 0.56%   |
| Vizio E320-A1 VIZ0095 1360x768 697x392mm 31.5-inch                      | 1        | 0.56%   |
| ViewSonic VX3211 SERIES VSCF534 1920x1080 700x390mm 31.5-inch           | 1        | 0.56%   |
| UTV Monitor UTV002F 3840x2160 1872x1053mm 84.6-inch                     | 1        | 0.56%   |
| Unknown LCD Monitor SAMSUNG 1360x768                                    | 1        | 0.56%   |
| Sony LCD Monitor AVSYSTEM 1280x720                                      | 1        | 0.56%   |
| Sceptre Tech Sceptre M24 SPT09A1 1920x1080 526x296mm 23.8-inch          | 1        | 0.56%   |
| Samsung Electronics T27B300 SAM0933 1920x1080 598x336mm 27.0-inch       | 1        | 0.56%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch     | 1        | 0.56%   |
| Samsung Electronics SyncMaster SAM0524 1920x1080 477x268mm 21.5-inch    | 1        | 0.56%   |
| Samsung Electronics SyncMaster SAM0484 1920x1080 520x320mm 24.0-inch    | 1        | 0.56%   |
| Samsung Electronics SyncMaster SAM036E 1280x1024 376x301mm 19.0-inch    | 1        | 0.56%   |
| Samsung Electronics SyncMaster SAM02FE 1680x1050 433x271mm 20.1-inch    | 1        | 0.56%   |
| Samsung Electronics SMS24A350H SAM07D6 1920x1080 531x299mm 24.0-inch    | 1        | 0.56%   |
| Samsung Electronics SMB2430H SAM064E 1920x1080                          | 1        | 0.56%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch      | 1        | 0.56%   |
| Samsung Electronics SMB1930N SAM0632 1360x768 410x230mm 18.5-inch       | 1        | 0.56%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch       | 1        | 0.56%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch       | 1        | 0.56%   |
| Samsung Electronics S27E510 SAM0C5F 1920x1080 600x340mm 27.2-inch       | 1        | 0.56%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 0.56%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch       | 1        | 0.56%   |
| Samsung Electronics S22B350 SAM08D4 1920x1080 477x268mm 21.5-inch       | 1        | 0.56%   |
| Samsung Electronics Odyssey G85SB SAM72F2 3440x1440 809x354mm 34.8-inch | 1        | 0.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 76       | 46.06%  |
| 2560x1440 (QHD)    | 19       | 11.52%  |
| 3840x2160 (4K)     | 17       | 10.3%   |
| 3440x1440          | 10       | 6.06%   |
| 2288x1287          | 8        | 4.85%   |
| 2560x1080          | 6        | 3.64%   |
| 1680x1050 (WSXGA+) | 5        | 3.03%   |
| 1366x768 (WXGA)    | 4        | 2.42%   |
| 1360x768           | 4        | 2.42%   |
| 1280x1024 (SXGA)   | 4        | 2.42%   |
| 3840x1080          | 2        | 1.21%   |
| 2560x1600          | 2        | 1.21%   |
| 1600x900 (HD+)     | 2        | 1.21%   |
| 1440x900 (WXGA+)   | 2        | 1.21%   |
| 1920x540           | 1        | 0.61%   |
| 1920x1200 (WUXGA)  | 1        | 0.61%   |
| 1280x720 (HD)      | 1        | 0.61%   |
| Unknown            | 1        | 0.61%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 30       | 17.34%  |
| 27      | 28       | 16.18%  |
| 23      | 21       | 12.14%  |
| 31      | 16       | 9.25%   |
| 21      | 15       | 8.67%   |
| 34      | 11       | 6.36%   |
| 142     | 8        | 4.62%   |
| Unknown | 7        | 4.05%   |
| 28      | 4        | 2.31%   |
| 19      | 4        | 2.31%   |
| 18      | 4        | 2.31%   |
| 84      | 3        | 1.73%   |
| 22      | 3        | 1.73%   |
| 58      | 2        | 1.16%   |
| 54      | 2        | 1.16%   |
| 40      | 2        | 1.16%   |
| 29      | 2        | 1.16%   |
| 20      | 2        | 1.16%   |
| 52      | 1        | 0.58%   |
| 48      | 1        | 0.58%   |
| 39      | 1        | 0.58%   |
| 35      | 1        | 0.58%   |
| 33      | 1        | 0.58%   |
| 32      | 1        | 0.58%   |
| 26      | 1        | 0.58%   |
| 17      | 1        | 0.58%   |
| 16      | 1        | 0.58%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 70       | 41.67%  |
| 601-700        | 25       | 14.88%  |
| 401-500        | 25       | 14.88%  |
| 701-800        | 13       | 7.74%   |
| More than 2000 | 8        | 4.76%   |
| Unknown        | 7        | 4.17%   |
| 351-400        | 6        | 3.57%   |
| 1001-1500      | 6        | 3.57%   |
| 801-900        | 5        | 2.98%   |
| 1501-2000      | 3        | 1.79%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 115      | 72.33%  |
| 21/9    | 16       | 10.06%  |
| 16/10   | 9        | 5.66%   |
| 1.00    | 8        | 5.03%   |
| Unknown | 5        | 3.14%   |
| 5/4     | 4        | 2.52%   |
| 32/9    | 1        | 0.63%   |
| 3/2     | 1        | 0.63%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 58       | 34.32%  |
| 351-500        | 32       | 18.93%  |
| 301-350        | 29       | 17.16%  |
| More than 1000 | 16       | 9.47%   |
| 251-300        | 10       | 5.92%   |
| 151-200        | 9        | 5.33%   |
| Unknown        | 7        | 4.14%   |
| 501-1000       | 4        | 2.37%   |
| 141-150        | 2        | 1.18%   |
| 131-140        | 1        | 0.59%   |
| 111-120        | 1        | 0.59%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 91       | 56.52%  |
| 101-120 | 32       | 19.88%  |
| 1-50    | 17       | 10.56%  |
| 121-160 | 11       | 6.83%   |
| Unknown | 7        | 4.35%   |
| 161-240 | 3        | 1.86%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 122      | 77.71%  |
| 2     | 29       | 18.47%  |
| 3     | 3        | 1.91%   |
| 0     | 3        | 1.91%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 103      | 44.78%  |
| Intel                           | 74       | 32.17%  |
| Qualcomm Atheros                | 16       | 6.96%   |
| Broadcom                        | 7        | 3.04%   |
| MediaTek                        | 5        | 2.17%   |
| TP-Link                         | 3        | 1.3%    |
| Ralink Technology               | 3        | 1.3%    |
| Ralink                          | 3        | 1.3%    |
| Aquantia                        | 3        | 1.3%    |
| Qualcomm Atheros Communications | 2        | 0.87%   |
| Qualcomm                        | 2        | 0.87%   |
| OPPO Electronics                | 2        | 0.87%   |
| Microsoft                       | 2        | 0.87%   |
| T & A Mobile Phones             | 1        | 0.43%   |
| QinHeng Electronics             | 1        | 0.43%   |
| NetGear                         | 1        | 0.43%   |
| Broadcom Limited                | 1        | 0.43%   |
| ASUSTek Computer                | 1        | 0.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 77       | 29.17%  |
| Realtek RTL8125 2.5GbE Controller                                      | 14       | 5.3%    |
| Intel Wi-Fi 6 AX200                                                    | 11       | 4.17%   |
| Intel I211 Gigabit Network Connection                                  | 11       | 4.17%   |
| Intel Ethernet Connection (2) I219-V                                   | 9        | 3.41%   |
| Intel Ethernet Controller I225-V                                       | 8        | 3.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7        | 2.65%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 6        | 2.27%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 6        | 2.27%   |
| Intel Ethernet Connection I217-LM                                      | 5        | 1.89%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 3        | 1.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 3        | 1.14%   |
| Intel Wireless 7265                                                    | 3        | 1.14%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 3        | 1.14%   |
| Intel Ethernet Connection (7) I219-V                                   | 3        | 1.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 3        | 1.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 3        | 1.14%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 3        | 1.14%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 3        | 1.14%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                    | 2        | 0.76%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 2        | 0.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2        | 0.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2        | 0.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2        | 0.76%   |
| Qualcomm Atheros AR9271 802.11n                                        | 2        | 0.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 2        | 0.76%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                       | 2        | 0.76%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 2        | 0.76%   |
| OPPO SM8350-MTP _SN:9338D66C                                           | 2        | 0.76%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 2        | 0.76%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 2        | 0.76%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 2        | 0.76%   |
| Intel Ethernet Connection (11) I219-V                                  | 2        | 0.76%   |
| Intel CNVi: Wi-Fi                                                      | 2        | 0.76%   |
| Intel 82579V Gigabit Network Connection                                | 2        | 0.76%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 1        | 0.38%   |
| T & A Mobile Phones TCL 30 Z                                           | 1        | 0.38%   |
| Realtek RTL8821CE PCIe 802.11ac Wireless Network Controller            | 1        | 0.38%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 1        | 0.38%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                             | 1        | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 38       | 42.22%  |
| Realtek Semiconductor           | 19       | 21.11%  |
| Qualcomm Atheros                | 7        | 7.78%   |
| MediaTek                        | 5        | 5.56%   |
| Broadcom                        | 5        | 5.56%   |
| TP-Link                         | 3        | 3.33%   |
| Ralink Technology               | 3        | 3.33%   |
| Ralink                          | 3        | 3.33%   |
| Qualcomm Atheros Communications | 2        | 2.22%   |
| Microsoft                       | 2        | 2.22%   |
| NetGear                         | 1        | 1.11%   |
| Broadcom Limited                | 1        | 1.11%   |
| ASUSTek Computer                | 1        | 1.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                       | 11       | 12.09%  |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 6        | 6.59%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                 | 6        | 6.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                          | 3        | 3.3%    |
| Intel Wireless 7265                                                       | 3        | 3.3%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                   | 3        | 3.3%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 3        | 3.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                           | 3        | 3.3%    |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter              | 3        | 3.3%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                                       | 2        | 2.2%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 2        | 2.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 2        | 2.2%    |
| Qualcomm Atheros AR9271 802.11n                                           | 2        | 2.2%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                          | 2        | 2.2%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                          | 2        | 2.2%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                   | 2        | 2.2%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter             | 2        | 2.2%    |
| Intel Raptor Lake-S PCH CNVi WiFi                                         | 2        | 2.2%    |
| Intel CNVi: Wi-Fi                                                         | 2        | 2.2%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                | 1        | 1.1%    |
| Realtek RTL8821CE PCIe 802.11ac Wireless Network Controller               | 1        | 1.1%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                   | 1        | 1.1%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                | 1        | 1.1%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                           | 1        | 1.1%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                           | 1        | 1.1%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                     | 1        | 1.1%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                       | 1        | 1.1%    |
| Realtek RTL8188EE Wireless Network Adapter                                | 1        | 1.1%    |
| Realtek 802.11ac NIC                                                      | 1        | 1.1%    |
| Ralink RT5370 Wireless Adapter                                            | 1        | 1.1%    |
| Ralink RT2501/RT2573 Wireless Adapter                                     | 1        | 1.1%    |
| Ralink MT7601U Wireless Adapter                                           | 1        | 1.1%    |
| Ralink RT5392 PCIe Wireless Network Adapter                               | 1        | 1.1%    |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                    | 1        | 1.1%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                 | 1        | 1.1%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)            | 1        | 1.1%    |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1        | 1.1%    |
| Microsoft XBOX ACC                                                        | 1        | 1.1%    |
| Microsoft Xbox 360 Wireless Adapter                                       | 1        | 1.1%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter             | 1        | 1.1%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 94       | 55.95%  |
| Intel                 | 53       | 31.55%  |
| Qualcomm Atheros      | 10       | 5.95%   |
| Broadcom              | 4        | 2.38%   |
| Aquantia              | 3        | 1.79%   |
| Qualcomm              | 2        | 1.19%   |
| OPPO Electronics      | 2        | 1.19%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller            | 77       | 45.03%  |
| Realtek RTL8125 2.5GbE Controller                                                 | 14       | 8.19%   |
| Intel I211 Gigabit Network Connection                                             | 11       | 6.43%   |
| Intel Ethernet Connection (2) I219-V                                              | 9        | 5.26%   |
| Intel Ethernet Controller I225-V                                                  | 8        | 4.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                             | 7        | 4.09%   |
| Intel Ethernet Connection I217-LM                                                 | 5        | 2.92%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                         | 3        | 1.75%   |
| Intel Ethernet Connection (7) I219-V                                              | 3        | 1.75%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                   | 3        | 1.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                          | 2        | 1.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                             | 2        | 1.17%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                    | 2        | 1.17%   |
| OPPO SM8350-MTP _SN:9338D66C                                                      | 2        | 1.17%   |
| Intel Ethernet Connection (11) I219-V                                             | 2        | 1.17%   |
| Intel 82579V Gigabit Network Connection                                           | 2        | 1.17%   |
| Realtek Killer E2600 GbE Controller                                               | 1        | 0.58%   |
| Qualcomm SAMSUNG_Android                                                          | 1        | 0.58%   |
| Qualcomm Nokia G42 5G                                                             | 1        | 0.58%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                         | 1        | 0.58%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                     | 1        | 0.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                     | 1        | 0.58%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                             | 1        | 0.58%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                          | 1        | 0.58%   |
| Intel I210 Gigabit Network Connection                                             | 1        | 0.58%   |
| Intel Ethernet Connection (2) I218-V                                              | 1        | 0.58%   |
| Intel Ethernet Connection (17) I219-V                                             | 1        | 0.58%   |
| Intel Ethernet Connection (14) I219-V                                             | 1        | 0.58%   |
| Intel Ethernet Connection (10) I219-V                                             | 1        | 0.58%   |
| Intel 82567LM-3 Gigabit Network Connection                                        | 1        | 0.58%   |
| Intel 82567LF-2 Gigabit Network Connection                                        | 1        | 0.58%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                                   | 1        | 0.58%   |
| Aquantia AQtion AQC113CS NBase-T/IEEE 802.3an Ethernet Controller [Antigua 10G]   | 1        | 0.58%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G]    | 1        | 0.58%   |
| Aquantia AQC113C NBase-T/IEEE 802.3an Ethernet Controller [Marvell Scalable mGig] | 1        | 0.58%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 153      | 63.75%  |
| WiFi     | 85       | 35.42%  |
| Modem    | 2        | 0.83%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 122      | 76.25%  |
| WiFi     | 38       | 23.75%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 84       | 53.85%  |
| 2     | 62       | 39.74%  |
| 3     | 7        | 4.49%   |
| 8     | 1        | 0.64%   |
| 4     | 1        | 0.64%   |
| 0     | 1        | 0.64%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 105      | 67.31%  |
| Yes  | 51       | 32.69%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 37       | 49.33%  |
| Cambridge Silicon Radio | 12       | 16%     |
| ASUSTek Computer        | 7        | 9.33%   |
| Realtek Semiconductor   | 6        | 8%      |
| TP-Link                 | 3        | 4%      |
| MediaTek                | 2        | 2.67%   |
| Foxconn / Hon Hai       | 2        | 2.67%   |
| Broadcom                | 2        | 2.67%   |
| Apple                   | 2        | 2.67%   |
| Lite-On Technology      | 1        | 1.33%   |
| IMC Networks            | 1        | 1.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 12       | 16%     |
| Intel AX200 Bluetooth                                 | 11       | 14.67%  |
| Intel AX210 Bluetooth                                 | 6        | 8%      |
| Realtek Bluetooth Radio                               | 4        | 5.33%   |
| Intel Bluetooth wireless interface                    | 4        | 5.33%   |
| TP-Link UB500 Adapter                                 | 3        | 4%      |
| Intel Wireless-AC 3168 Bluetooth                      | 3        | 4%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 3        | 4%      |
| Intel AX211 Bluetooth                                 | 3        | 4%      |
| Intel AX201 Bluetooth                                 | 3        | 4%      |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 3        | 4%      |
| Realtek  Bluetooth 4.2 Adapter                        | 2        | 2.67%   |
| MediaTek Wireless_Device                              | 2        | 2.67%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 2        | 2.67%   |
| ASUS Bluetooth Radio                                  | 2        | 2.67%   |
| Lite-On Bluetooth Device                              | 1        | 1.33%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1        | 1.33%   |
| Intel Bluetooth Device                                | 1        | 1.33%   |
| IMC Networks Wireless_Device                          | 1        | 1.33%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter          | 1        | 1.33%   |
| Foxconn / Hon Hai Bluetooth Device                    | 1        | 1.33%   |
| Broadcom HP Portable Bumble Bee                       | 1        | 1.33%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1        | 1.33%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 1.33%   |
| ASUS ASUS USB-BT500                                   | 1        | 1.33%   |
| Apple Bluetooth USB Host Controller                   | 1        | 1.33%   |
| Apple Bluetooth Host Controller                       | 1        | 1.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 96       | 32%     |
| AMD                                          | 78       | 26%     |
| Nvidia                                       | 72       | 24%     |
| C-Media Electronics                          | 10       | 3.33%   |
| Corsair                                      | 4        | 1.33%   |
| Razer USA                                    | 3        | 1%      |
| Logitech                                     | 3        | 1%      |
| Kingston Technology                          | 3        | 1%      |
| Generalplus Technology                       | 3        | 1%      |
| ASUSTek Computer                             | 3        | 1%      |
| Zoran Co. Personal Media Division (Nogatech) | 2        | 0.67%   |
| Hewlett-Packard                              | 2        | 0.67%   |
| Elgato Systems                               | 2        | 0.67%   |
| BR25                                         | 2        | 0.67%   |
| Trust                                        | 1        | 0.33%   |
| Tenx Technology                              | 1        | 0.33%   |
| TC Electronic                                | 1        | 0.33%   |
| SteelSeries ApS                              | 1        | 0.33%   |
| Soundprese                                   | 1        | 0.33%   |
| Shenzhen Riitek Technology                   | 1        | 0.33%   |
| PreSonus Audio Electronics                   | 1        | 0.33%   |
| Plantronics                                  | 1        | 0.33%   |
| Mark of the Unicorn                          | 1        | 0.33%   |
| JMTek                                        | 1        | 0.33%   |
| JBL                                          | 1        | 0.33%   |
| GN Netcom                                    | 1        | 0.33%   |
| fifine Microphone                            | 1        | 0.33%   |
| ELMCU                                        | 1        | 0.33%   |
| Barco Display Systems                        | 1        | 0.33%   |
| Astro Gaming                                 | 1        | 0.33%   |
| Arturia                                      | 1        | 0.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 24       | 6.9%    |
| AMD Family 17h/19h HD Audio Controller                                     | 15       | 4.31%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 14       | 4.02%   |
| Intel 200 Series PCH HD Audio                                              | 12       | 3.45%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 11       | 3.16%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 10       | 2.87%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9        | 2.59%   |
| Nvidia GP104 High Definition Audio Controller                              | 9        | 2.59%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9        | 2.59%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 9        | 2.59%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 8        | 2.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7        | 2.01%   |
| Intel Cannon Lake PCH cAVS                                                 | 7        | 2.01%   |
| AMD Navi 10 HDMI Audio                                                     | 7        | 2.01%   |
| Nvidia GA104 High Definition Audio Controller                              | 6        | 1.72%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6        | 1.72%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 6        | 1.72%   |
| Nvidia TU116 High Definition Audio Controller                              | 5        | 1.44%   |
| Nvidia TU106 High Definition Audio Controller                              | 5        | 1.44%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 5        | 1.44%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5        | 1.44%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5        | 1.44%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5        | 1.44%   |
| Nvidia GP108 High Definition Audio Controller                              | 4        | 1.15%   |
| Nvidia GP106 High Definition Audio Controller                              | 4        | 1.15%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4        | 1.15%   |
| Nvidia TU104 HD Audio Controller                                           | 3        | 0.86%   |
| Nvidia GM204 High Definition Audio Controller                              | 3        | 0.86%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 0.86%   |
| Nvidia GA102 High Definition Audio Controller                              | 3        | 0.86%   |
| Intel Raptor Lake High Definition Audio Controller                         | 3        | 0.86%   |
| Intel Alder Lake-S HD Audio Controller                                     | 3        | 0.86%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 0.86%   |
| Generalplus Technology USB Audio Device                                    | 3        | 0.86%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 3        | 0.86%   |
| ASUSTek Computer USB Audio                                                 | 3        | 0.86%   |
| AMD FCH Azalia Controller                                                  | 3        | 0.86%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3        | 0.86%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3        | 0.86%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID             | 2        | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Corsair                      | 26       | 15.2%   |
| G.Skill                      | 25       | 14.62%  |
| Kingston                     | 19       | 11.11%  |
| Samsung Electronics          | 17       | 9.94%   |
| SK hynix                     | 13       | 7.6%    |
| Unknown                      | 12       | 7.02%   |
| Crucial                      | 12       | 7.02%   |
| Team                         | 8        | 4.68%   |
| Micron Technology            | 8        | 4.68%   |
| A-DATA Technology            | 4        | 2.34%   |
| Unknown                      | 3        | 1.75%   |
| Ramaxel Technology           | 2        | 1.17%   |
| Patriot Memory (PDP Systems) | 2        | 1.17%   |
| Patriot                      | 2        | 1.17%   |
| GeIL                         | 2        | 1.17%   |
| Unifosa                      | 1        | 0.58%   |
| Transcend                    | 1        | 0.58%   |
| Timetec                      | 1        | 0.58%   |
| Silicon Power                | 1        | 0.58%   |
| Reboto                       | 1        | 0.58%   |
| Ramos Technology             | 1        | 0.58%   |
| PNY                          | 1        | 0.58%   |
| Nanya Technology             | 1        | 0.58%   |
| Kllisre                      | 1        | 0.58%   |
| KingFast                     | 1        | 0.58%   |
| Juhor                        | 1        | 0.58%   |
| Heoriady                     | 1        | 0.58%   |
| Guangzhou MiaoYuanJi         | 1        | 0.58%   |
| GOODRAM                      | 1        | 0.58%   |
| Goldkey                      | 1        | 0.58%   |
| Golden Empire                | 1        | 0.58%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s    | 4        | 2.14%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 4        | 2.14%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s    | 3        | 1.6%    |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s   | 3        | 1.6%    |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s | 3        | 1.6%    |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s    | 3        | 1.6%    |
| Unknown                                                | 3        | 1.6%    |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 2        | 1.07%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s     | 2        | 1.07%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s | 2        | 1.07%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s    | 2        | 1.07%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s    | 2        | 1.07%   |
| Kingston RAM KHX2133C14/16G 16GB DIMM DDR4 2176MT/s    | 2        | 1.07%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1600MT/s    | 2        | 1.07%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s     | 2        | 1.07%   |
| G.Skill RAM F4-2666C15-4GVR 4GB DIMM DDR4 2933MT/s     | 2        | 1.07%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1800MT/s    | 2        | 1.07%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s  | 2        | 1.07%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s            | 2        | 1.07%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s              | 1        | 0.53%   |
| Unknown RAM Module 4GB DIMM SDRAM 1066MT/s             | 1        | 0.53%   |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s              | 1        | 0.53%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 1        | 0.53%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s              | 1        | 0.53%   |
| Unknown RAM Module 4GB DIMM DDR3                       | 1        | 0.53%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s               | 1        | 0.53%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 1        | 0.53%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s               | 1        | 0.53%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s              | 1        | 0.53%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s               | 1        | 0.53%   |
| Unknown RAM Module 16GB DIMM DDR4 2667MT/s             | 1        | 0.53%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s      | 1        | 0.53%   |
| Transcend RAM TS1GLK64V6H 8GB DIMM DDR3 1600MT/s       | 1        | 0.53%   |
| Timetec RAM Module 16GB SODIMM DDR4 3200MT/s           | 1        | 0.53%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3733MT/s    | 1        | 0.53%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1067MT/s     | 1        | 0.53%   |
| Team RAM Elite-1600 8GB DIMM DDR3 1600MT/s             | 1        | 0.53%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1333MT/s           | 1        | 0.53%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s   | 1        | 0.53%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s   | 1        | 0.53%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 85       | 57.05%  |
| DDR3    | 47       | 31.54%  |
| DDR5    | 6        | 4.03%   |
| SDRAM   | 4        | 2.68%   |
| DDR2    | 4        | 2.68%   |
| Unknown | 2        | 1.34%   |
| DDR     | 1        | 0.67%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 136      | 93.79%  |
| SODIMM | 9        | 6.21%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 62       | 38.75%  |
| 4096  | 40       | 25%     |
| 16384 | 36       | 22.5%   |
| 2048  | 11       | 6.88%   |
| 32768 | 10       | 6.25%   |
| 1024  | 1        | 0.63%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 26       | 15.2%   |
| 3200    | 20       | 11.7%   |
| 3600    | 15       | 8.77%   |
| 1333    | 10       | 5.85%   |
| 2667    | 9        | 5.26%   |
| 2400    | 9        | 5.26%   |
| 2133    | 9        | 5.26%   |
| 1866    | 6        | 3.51%   |
| 3733    | 5        | 2.92%   |
| 2933    | 5        | 2.92%   |
| 1800    | 5        | 2.92%   |
| 3800    | 4        | 2.34%   |
| 3000    | 4        | 2.34%   |
| 2666    | 4        | 2.34%   |
| 1867    | 4        | 2.34%   |
| 3400    | 3        | 1.75%   |
| 1066    | 3        | 1.75%   |
| 800     | 3        | 1.75%   |
| 4400    | 2        | 1.17%   |
| 2176    | 2        | 1.17%   |
| 2134    | 2        | 1.17%   |
| 2000    | 2        | 1.17%   |
| 1400    | 2        | 1.17%   |
| 7000    | 1        | 0.58%   |
| 6400    | 1        | 0.58%   |
| 6000    | 1        | 0.58%   |
| 5800    | 1        | 0.58%   |
| 5600    | 1        | 0.58%   |
| 4800    | 1        | 0.58%   |
| 4133    | 1        | 0.58%   |
| 3866    | 1        | 0.58%   |
| 3666    | 1        | 0.58%   |
| 3467    | 1        | 0.58%   |
| 3266    | 1        | 0.58%   |
| 2747    | 1        | 0.58%   |
| 1648    | 1        | 0.58%   |
| 1450    | 1        | 0.58%   |
| 1067    | 1        | 0.58%   |
| 667     | 1        | 0.58%   |
| Unknown | 1        | 0.58%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 2        | 40%     |
| Seiko Epson         | 1        | 20%     |
| Samsung Electronics | 1        | 20%     |
| Brother Industries  | 1        | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seiko Epson WF-2870 Series           | 1        | 20%     |
| Samsung ML-1640 Series Laser Printer | 1        | 20%     |
| HP LaserJet CP1525nw/x               | 1        | 20%     |
| HP Deskjet 2050 J510                 | 1        | 20%     |
| Brother HL-5250DN Printer            | 1        | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| Mustek Systems | 1        | 50%     |
| Canon          | 1        | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Mustek Systems BearPaw 2448 TA Plus | 1        | 50%     |
| Canon CanoScan LiDE 110             | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 8        | 26.67%  |
| Microdia                               | 6        | 20%     |
| Generalplus Technology                 | 3        | 10%     |
| Chicony Electronics                    | 3        | 10%     |
| Creative Technology                    | 2        | 6.67%   |
| Z-Star Microelectronics                | 1        | 3.33%   |
| Sunplus Innovation Technology          | 1        | 3.33%   |
| Samsung Electronics                    | 1        | 3.33%   |
| Panasonic (Matsushita)                 | 1        | 3.33%   |
| Microsoft                              | 1        | 3.33%   |
| Jieli Technology                       | 1        | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) | 1        | 3.33%   |
| Aveo Technology                        | 1        | 3.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Microdia Webcam Vitade AF                                            | 3        | 10%     |
| Logitech BRIO Ultra HD Webcam                                        | 2        | 6.67%   |
| Generalplus CAMERA - UVC                                             | 2        | 6.67%   |
| Creative Creative Live! Cam Sync 1080p V2                            | 2        | 6.67%   |
| Chicony HP High Definition 1MP Webcam                                | 2        | 6.67%   |
| Z-Star Vimicro USB Camera (Altair)                                   | 1        | 3.33%   |
| Sunplus Full HD webcam                                               | 1        | 3.33%   |
| Samsung Galaxy series, misc. (MTP mode)                              | 1        | 3.33%   |
| Panasonic (Matsushita) TY-CC20W                                      | 1        | 3.33%   |
| Microsoft LifeCam Cinema                                             | 1        | 3.33%   |
| Microdia USB 2.0 Camera                                              | 1        | 3.33%   |
| Microdia Camera                                                      | 1        | 3.33%   |
| Microdia ACR010 USB Webcam                                           | 1        | 3.33%   |
| Logitech Webcam Pro 9000                                             | 1        | 3.33%   |
| Logitech Webcam C930e                                                | 1        | 3.33%   |
| Logitech Webcam C600                                                 | 1        | 3.33%   |
| Logitech Portable Webcam C905                                        | 1        | 3.33%   |
| Logitech Logi Webcam C920e                                           | 1        | 3.33%   |
| Logitech HD Webcam C615                                              | 1        | 3.33%   |
| Jieli USB PHY 2.0                                                    | 1        | 3.33%   |
| Generalplus campark PC04                                             | 1        | 3.33%   |
| Chicony HP Integrated Webcam                                         | 1        | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) HP High Definition 1MP Webcam | 1        | 3.33%   |
| Aveo Camera                                                          | 1        | 3.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Elan Microelectronics | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200] | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 136      | 87.74%  |
| 1     | 19       | 12.26%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Desktops | Percent |
|--------------------|----------|---------|
| Net/wireless       | 6        | 33.33%  |
| Unassigned class   | 5        | 27.78%  |
| Graphics card      | 3        | 16.67%  |
| Bluetooth          | 3        | 16.67%  |
| Fingerprint reader | 1        | 5.56%   |


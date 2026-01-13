blendOS - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for blendOS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/blendOS/Desktop/README.md) and [notebooks](/Dist/blendOS/Notebook/README.md).

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

Total: 182

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | 0VD5HY A04                  | Desktop     | [e0c6f73d45](https://linux-hardware.org/?probe=e0c6f73d45) | Dec 16, 2025 |
| ASRock        | X670E Pro RS                | Desktop     | [844c83ad9e](https://linux-hardware.org/?probe=844c83ad9e) | Dec 14, 2025 |
| Gigabyte      | H61M-S1                     | Desktop     | [d2b8f811f2](https://linux-hardware.org/?probe=d2b8f811f2) | Oct 22, 2025 |
| ASRock        | Z170 Extreme4+              | Desktop     | [e8e5cc4050](https://linux-hardware.org/?probe=e8e5cc4050) | Oct 07, 2025 |
| LG Electro... | 16Z90Q-G.AP7BB              | Notebook    | [7ba27b35ec](https://linux-hardware.org/?probe=7ba27b35ec) | Oct 02, 2025 |
| LG Electro... | 16Z90Q-G.AP7BB              | Notebook    | [260d20352a](https://linux-hardware.org/?probe=260d20352a) | Oct 02, 2025 |
| HP            | Laptop 17-by3xxx            | Notebook    | [c964faff51](https://linux-hardware.org/?probe=c964faff51) | Sep 03, 2025 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [1a5d709338](https://linux-hardware.org/?probe=1a5d709338) | Aug 30, 2025 |
| MSI           | B550-A PRO                  | Desktop     | [12ef71f416](https://linux-hardware.org/?probe=12ef71f416) | Aug 27, 2025 |
| HP            | Pavilion x360 Convertibl... | Convertible | [b8e4285fbe](https://linux-hardware.org/?probe=b8e4285fbe) | Aug 14, 2025 |
| HP            | ProBook 640 G2              | Notebook    | [a22d2ae9d1](https://linux-hardware.org/?probe=a22d2ae9d1) | Aug 03, 2025 |
| HP            | Pavilion x360 Convertibl... | Convertible | [fe8bf5bd76](https://linux-hardware.org/?probe=fe8bf5bd76) | Jul 29, 2025 |
| PINNACLEMI... | W76OC                       | Notebook    | [cc68f30710](https://linux-hardware.org/?probe=cc68f30710) | Jul 01, 2025 |
| OriginPC      | EON17-X                     | Notebook    | [16a89d1dc3](https://linux-hardware.org/?probe=16a89d1dc3) | May 09, 2025 |
| AZW           | SER V1                      | Mini pc     | [b2ea23d819](https://linux-hardware.org/?probe=b2ea23d819) | Feb 16, 2025 |
| JINGSHA       | H61S                        | Desktop     | [173807e0a4](https://linux-hardware.org/?probe=173807e0a4) | Feb 03, 2025 |
| HP            | 0AA8h                       | Desktop     | [1d59ae0683](https://linux-hardware.org/?probe=1d59ae0683) | Feb 02, 2025 |
| Gigabyte      | H510M H                     | Desktop     | [c5249cf6d5](https://linux-hardware.org/?probe=c5249cf6d5) | Jan 28, 2025 |
| Lenovo        | G50-70 20351                | Notebook    | [82a4f5f99b](https://linux-hardware.org/?probe=82a4f5f99b) | Jan 01, 2025 |
| Apple         | MacBookPro8,2               | Notebook    | [e2f957298c](https://linux-hardware.org/?probe=e2f957298c) | Dec 17, 2024 |
| Apple         | MacBookPro8,2               | Notebook    | [504b00b57d](https://linux-hardware.org/?probe=504b00b57d) | Dec 17, 2024 |
| Apple         | MacBookPro5,1               | Notebook    | [3ba5637302](https://linux-hardware.org/?probe=3ba5637302) | Dec 07, 2024 |
| AZW           | SER V1                      | Mini pc     | [943b7a7303](https://linux-hardware.org/?probe=943b7a7303) | Nov 26, 2024 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [2424c97650](https://linux-hardware.org/?probe=2424c97650) | Sep 24, 2024 |
| Lenovo        | B51-30 80LK                 | Notebook    | [e4f72a3222](https://linux-hardware.org/?probe=e4f72a3222) | Aug 08, 2024 |
| Lenovo        | B51-30 80LK                 | Notebook    | [8003cbb98e](https://linux-hardware.org/?probe=8003cbb98e) | Aug 08, 2024 |
| MSI           | B450M-A PRO MAX II          | Desktop     | [dd3e786ebe](https://linux-hardware.org/?probe=dd3e786ebe) | Jul 15, 2024 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [5a85b71894](https://linux-hardware.org/?probe=5a85b71894) | Jun 13, 2024 |
| Alienware     | m15                         | Notebook    | [e088ad174b](https://linux-hardware.org/?probe=e088ad174b) | May 21, 2024 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [b3e1342003](https://linux-hardware.org/?probe=b3e1342003) | May 12, 2024 |
| MSI           | B550M-A PRO                 | Desktop     | [7101b53f84](https://linux-hardware.org/?probe=7101b53f84) | May 11, 2024 |
| Lenovo        | 36E7 SDK0J40700 WIN 3258... | Desktop     | [03d6226580](https://linux-hardware.org/?probe=03d6226580) | May 01, 2024 |
| Fujitsu       | LIFEBOOK U727               | Notebook    | [2d96690752](https://linux-hardware.org/?probe=2d96690752) | Apr 20, 2024 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [722d095e41](https://linux-hardware.org/?probe=722d095e41) | Apr 09, 2024 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [4f39ce99c5](https://linux-hardware.org/?probe=4f39ce99c5) | Apr 02, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e34eb800b2](https://linux-hardware.org/?probe=e34eb800b2) | Mar 29, 2024 |
| Acer          | Aspire 4752                 | Notebook    | [bb522b4ec1](https://linux-hardware.org/?probe=bb522b4ec1) | Mar 26, 2024 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [fced33a8a9](https://linux-hardware.org/?probe=fced33a8a9) | Mar 12, 2024 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [7e150a29fb](https://linux-hardware.org/?probe=7e150a29fb) | Mar 09, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [33cf50568b](https://linux-hardware.org/?probe=33cf50568b) | Mar 06, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8845023d60](https://linux-hardware.org/?probe=8845023d60) | Mar 02, 2024 |
| Chuwi         | LarkBox X                   | Mini pc     | [838f19b0f9](https://linux-hardware.org/?probe=838f19b0f9) | Feb 18, 2024 |
| ASUSTek       | H81M-C                      | Desktop     | [a13bfac287](https://linux-hardware.org/?probe=a13bfac287) | Feb 10, 2024 |
| Gigabyte      | X99P-SLI-CF                 | Desktop     | [95705bca92](https://linux-hardware.org/?probe=95705bca92) | Feb 01, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [7ad397fc57](https://linux-hardware.org/?probe=7ad397fc57) | Jan 31, 2024 |
| Hampoo        | Cherry Trail CR             | Notebook    | [1c0466fe53](https://linux-hardware.org/?probe=1c0466fe53) | Jan 25, 2024 |
| MSI           | GS66 Stealth 10SF           | Notebook    | [fc256ee1dd](https://linux-hardware.org/?probe=fc256ee1dd) | Jan 18, 2024 |
| MSI           | GS66 Stealth 10SF           | Notebook    | [57eaf4a8c1](https://linux-hardware.org/?probe=57eaf4a8c1) | Jan 18, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [ad1ac91848](https://linux-hardware.org/?probe=ad1ac91848) | Jan 15, 2024 |
| Fujitsu       | D3603-A1 S26361-D3603-A1    | Desktop     | [f6ed1d1cc4](https://linux-hardware.org/?probe=f6ed1d1cc4) | Jan 15, 2024 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [cf1d697418](https://linux-hardware.org/?probe=cf1d697418) | Jan 12, 2024 |
| ShangMai      | H                           | Notebook    | [aab28ab3ea](https://linux-hardware.org/?probe=aab28ab3ea) | Dec 27, 2023 |
| Lenovo        | ThinkPad E470 20H1004UIG    | Notebook    | [69efda7672](https://linux-hardware.org/?probe=69efda7672) | Dec 26, 2023 |
| Lenovo        | ThinkPad L470 20J5S0JM00    | Notebook    | [c8f1140dc5](https://linux-hardware.org/?probe=c8f1140dc5) | Dec 26, 2023 |
| Dell          | Inspiron 16 Plus 7630       | Notebook    | [5f798fd0e0](https://linux-hardware.org/?probe=5f798fd0e0) | Dec 26, 2023 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [c37a18c186](https://linux-hardware.org/?probe=c37a18c186) | Dec 25, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [5b7a85e9fc](https://linux-hardware.org/?probe=5b7a85e9fc) | Dec 23, 2023 |
| Lenovo        | IdeaPadFlex 15 20309        | Notebook    | [81dbec4f1a](https://linux-hardware.org/?probe=81dbec4f1a) | Dec 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [5e71510e4c](https://linux-hardware.org/?probe=5e71510e4c) | Dec 06, 2023 |
| HP            | 89E9 0100                   | All in one  | [c32fa5c4ea](https://linux-hardware.org/?probe=c32fa5c4ea) | Dec 01, 2023 |
| Microsoft     | Surface Laptop              | Tablet      | [c867b76eff](https://linux-hardware.org/?probe=c867b76eff) | Nov 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [beca2cade6](https://linux-hardware.org/?probe=beca2cade6) | Nov 26, 2023 |
| MSI           | B650 GAMING PLUS WIFI       | Desktop     | [c25e140976](https://linux-hardware.org/?probe=c25e140976) | Nov 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [f90c57452a](https://linux-hardware.org/?probe=f90c57452a) | Nov 21, 2023 |
| Samsung       | 550P5C/550P7C               | Notebook    | [b7294ed55c](https://linux-hardware.org/?probe=b7294ed55c) | Nov 20, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [ea5517388b](https://linux-hardware.org/?probe=ea5517388b) | Nov 19, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [9cdba3ee40](https://linux-hardware.org/?probe=9cdba3ee40) | Nov 12, 2023 |
| Dell          | Latitude E7250              | Notebook    | [265c13751a](https://linux-hardware.org/?probe=265c13751a) | Nov 10, 2023 |
| Samsung       | 750XEE                      | Notebook    | [8fd9a5953f](https://linux-hardware.org/?probe=8fd9a5953f) | Nov 07, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b837317e37](https://linux-hardware.org/?probe=b837317e37) | Nov 06, 2023 |
| HP            | ENVY 15                     | Notebook    | [5f301610ee](https://linux-hardware.org/?probe=5f301610ee) | Nov 06, 2023 |
| HP            | ENVY 15                     | Notebook    | [150ca6a1a0](https://linux-hardware.org/?probe=150ca6a1a0) | Nov 06, 2023 |
| Samsung       | 750XEE                      | Notebook    | [fd74ae52f8](https://linux-hardware.org/?probe=fd74ae52f8) | Nov 04, 2023 |
| Notebook      | P65_P67SA                   | Notebook    | [a8bf179e25](https://linux-hardware.org/?probe=a8bf179e25) | Nov 01, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [6ba3f1daa1](https://linux-hardware.org/?probe=6ba3f1daa1) | Oct 30, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [e2c02539ce](https://linux-hardware.org/?probe=e2c02539ce) | Oct 29, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [342218fa56](https://linux-hardware.org/?probe=342218fa56) | Oct 28, 2023 |
| HP            | Notebook                    | Notebook    | [efb9814479](https://linux-hardware.org/?probe=efb9814479) | Oct 27, 2023 |
| Toshiba       | QOSMIO X75-A                | Notebook    | [8024d2e76b](https://linux-hardware.org/?probe=8024d2e76b) | Oct 26, 2023 |
| HP            | 89E9 0100                   | All in one  | [17fde8ad64](https://linux-hardware.org/?probe=17fde8ad64) | Oct 24, 2023 |
| Alienware     | 0K9TKY A00                  | Desktop     | [a51d4611f8](https://linux-hardware.org/?probe=a51d4611f8) | Oct 23, 2023 |
| HP            | ProBook 655 G1              | Notebook    | [8e1cb99809](https://linux-hardware.org/?probe=8e1cb99809) | Oct 19, 2023 |
| HP            | ProBook 655 G1              | Notebook    | [a80cd678f2](https://linux-hardware.org/?probe=a80cd678f2) | Oct 18, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [3d308e7bb0](https://linux-hardware.org/?probe=3d308e7bb0) | Oct 16, 2023 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [1ddd96bd4e](https://linux-hardware.org/?probe=1ddd96bd4e) | Oct 15, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [b97291313f](https://linux-hardware.org/?probe=b97291313f) | Oct 10, 2023 |
| HP            | 255 G5 Notebook PC          | Notebook    | [ecb99bea0c](https://linux-hardware.org/?probe=ecb99bea0c) | Oct 07, 2023 |
| MSI           | Pulse GL66 11UGK            | Notebook    | [706d9eb214](https://linux-hardware.org/?probe=706d9eb214) | Oct 06, 2023 |
| HP            | 255 G5 Notebook PC          | Notebook    | [4f758a2ce7](https://linux-hardware.org/?probe=4f758a2ce7) | Oct 05, 2023 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [604e4a5556](https://linux-hardware.org/?probe=604e4a5556) | Oct 05, 2023 |
| MSI           | Pulse GL66 11UGK            | Notebook    | [4484122a2c](https://linux-hardware.org/?probe=4484122a2c) | Oct 05, 2023 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [73ab8f124c](https://linux-hardware.org/?probe=73ab8f124c) | Oct 03, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [6275e5c1d4](https://linux-hardware.org/?probe=6275e5c1d4) | Sep 29, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [fcb38d5424](https://linux-hardware.org/?probe=fcb38d5424) | Sep 24, 2023 |
| Dell          | 0RW199                      | Desktop     | [6fc37ef3c1](https://linux-hardware.org/?probe=6fc37ef3c1) | Sep 24, 2023 |
| Lenovo        | IdeaPad Duet 3 10IGL5 82... | Tablet      | [a6ef657fca](https://linux-hardware.org/?probe=a6ef657fca) | Sep 24, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [26f998fafb](https://linux-hardware.org/?probe=26f998fafb) | Sep 19, 2023 |
| Acer          | Veriton X4618G              | Desktop     | [a34419120b](https://linux-hardware.org/?probe=a34419120b) | Sep 19, 2023 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [93356dbebb](https://linux-hardware.org/?probe=93356dbebb) | Sep 17, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [ab8cb379a8](https://linux-hardware.org/?probe=ab8cb379a8) | Sep 17, 2023 |
| Lenovo        | IdeaPad Duet 3 10IGL5 82... | Tablet      | [7e5fc6c3eb](https://linux-hardware.org/?probe=7e5fc6c3eb) | Sep 17, 2023 |
| Dell          | Inspiron 15 5510            | Notebook    | [71a6a04c4c](https://linux-hardware.org/?probe=71a6a04c4c) | Sep 15, 2023 |
| Dell          | XPS 9320                    | Notebook    | [054584d248](https://linux-hardware.org/?probe=054584d248) | Sep 15, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | Desktop     | [b771d7b475](https://linux-hardware.org/?probe=b771d7b475) | Sep 10, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | Desktop     | [6002a35e23](https://linux-hardware.org/?probe=6002a35e23) | Sep 10, 2023 |
| Pegatron      | 2ACD                        | Desktop     | [4f61dd9a7a](https://linux-hardware.org/?probe=4f61dd9a7a) | Sep 10, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [6515c97b89](https://linux-hardware.org/?probe=6515c97b89) | Sep 05, 2023 |
| ASRock        | 970 Extreme4                | Desktop     | [4196acbe15](https://linux-hardware.org/?probe=4196acbe15) | Sep 05, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [a6d272539a](https://linux-hardware.org/?probe=a6d272539a) | Sep 03, 2023 |
| Dell          | Latitude 5410               | Notebook    | [e45d7975d2](https://linux-hardware.org/?probe=e45d7975d2) | Sep 03, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [5a388c766a](https://linux-hardware.org/?probe=5a388c766a) | Aug 23, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [205a407b60](https://linux-hardware.org/?probe=205a407b60) | Aug 21, 2023 |
| ASRock        | 970 Extreme4                | Desktop     | [4cec633c85](https://linux-hardware.org/?probe=4cec633c85) | Aug 20, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [d3aac86eac](https://linux-hardware.org/?probe=d3aac86eac) | Aug 16, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [7032d8da96](https://linux-hardware.org/?probe=7032d8da96) | Aug 16, 2023 |
| Panasonic     | CF-19ADNAXDA                | Notebook    | [d96cf2b13c](https://linux-hardware.org/?probe=d96cf2b13c) | Aug 12, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | Notebook    | [f062831bd7](https://linux-hardware.org/?probe=f062831bd7) | Aug 11, 2023 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [646d098c58](https://linux-hardware.org/?probe=646d098c58) | Aug 10, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [b8f1735d23](https://linux-hardware.org/?probe=b8f1735d23) | Aug 04, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [6a6f453881](https://linux-hardware.org/?probe=6a6f453881) | Aug 02, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [33674f8b81](https://linux-hardware.org/?probe=33674f8b81) | Aug 02, 2023 |
| ASUSTek       | Z87-A                       | Desktop     | [603bee8812](https://linux-hardware.org/?probe=603bee8812) | Aug 01, 2023 |
| ASUSTek       | Z87-A                       | Desktop     | [64bc1caf41](https://linux-hardware.org/?probe=64bc1caf41) | Aug 01, 2023 |
| Acer          | Aspire A715-71G             | Notebook    | [7f3c7327b7](https://linux-hardware.org/?probe=7f3c7327b7) | Aug 01, 2023 |
| Beelink       | Gemini X                    | Notebook    | [2846d152be](https://linux-hardware.org/?probe=2846d152be) | Jul 29, 2023 |
| MSI           | GP63 Leopard 8RE            | Notebook    | [42a81e063a](https://linux-hardware.org/?probe=42a81e063a) | Jul 28, 2023 |
| Google        | Sumo                        | Desktop     | [71a7167d22](https://linux-hardware.org/?probe=71a7167d22) | Jul 25, 2023 |
| MAXSUN        | MS-Terminator B660M VER:... | Desktop     | [5cf65783b2](https://linux-hardware.org/?probe=5cf65783b2) | Jul 25, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [9a62fe1979](https://linux-hardware.org/?probe=9a62fe1979) | Jul 22, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | Notebook    | [352cc6e31d](https://linux-hardware.org/?probe=352cc6e31d) | Jul 17, 2023 |
| Samsung       | 950XDB/951XDB/950XDY        | Notebook    | [72015ffe3b](https://linux-hardware.org/?probe=72015ffe3b) | Jul 16, 2023 |
| Supermicro    | X10DAL-i                    | Server      | [fb5e1afd45](https://linux-hardware.org/?probe=fb5e1afd45) | Jul 14, 2023 |
| ASUSTek       | G750JZA                     | Notebook    | [8a26d246e2](https://linux-hardware.org/?probe=8a26d246e2) | Jul 14, 2023 |
| Samsung       | Galaxy TabPro S             | Tablet      | [59a6da64a7](https://linux-hardware.org/?probe=59a6da64a7) | Jul 13, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [fa192badba](https://linux-hardware.org/?probe=fa192badba) | Jul 12, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [4d33bb92ce](https://linux-hardware.org/?probe=4d33bb92ce) | Jul 09, 2023 |
| HP            | Pavilion dv6                | Notebook    | [7f6c05f2d9](https://linux-hardware.org/?probe=7f6c05f2d9) | Jul 09, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [62bbadc762](https://linux-hardware.org/?probe=62bbadc762) | Jul 08, 2023 |
| Samsung       | Galaxy TabPro S             | Tablet      | [352e4ef5e5](https://linux-hardware.org/?probe=352e4ef5e5) | Jul 08, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [07ab83bef1](https://linux-hardware.org/?probe=07ab83bef1) | Jun 30, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [fcf9a0fd47](https://linux-hardware.org/?probe=fcf9a0fd47) | Jun 30, 2023 |
| Acer          | Aspire V5-471G              | Notebook    | [f82fbc50e3](https://linux-hardware.org/?probe=f82fbc50e3) | Jun 20, 2023 |
| Microsoft     | Surface Laptop              | Tablet      | [401cb6a1f1](https://linux-hardware.org/?probe=401cb6a1f1) | Jun 20, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [627203a31f](https://linux-hardware.org/?probe=627203a31f) | Jun 18, 2023 |
| MSI           | MS-16Y1                     | Notebook    | [167889509f](https://linux-hardware.org/?probe=167889509f) | Jun 18, 2023 |
| ASUSTek       | X540LA                      | Notebook    | [55316783a4](https://linux-hardware.org/?probe=55316783a4) | Jun 16, 2023 |
| ASUSTek       | X540LA                      | Notebook    | [2c1b5651ed](https://linux-hardware.org/?probe=2c1b5651ed) | Jun 15, 2023 |
| ASUSTek       | PRIME H270-PLUS             | Desktop     | [017c7fd564](https://linux-hardware.org/?probe=017c7fd564) | Jun 11, 2023 |
| HP            | Notebook                    | Notebook    | [45553d6493](https://linux-hardware.org/?probe=45553d6493) | Jun 04, 2023 |
| ASUSTek       | K53SK                       | Notebook    | [39c63c5bd1](https://linux-hardware.org/?probe=39c63c5bd1) | May 31, 2023 |
| Dell          | 0GXM1W A02                  | Desktop     | [9c252c8688](https://linux-hardware.org/?probe=9c252c8688) | May 30, 2023 |
| Lenovo        | G700 20251                  | Notebook    | [8ba2c6e5ed](https://linux-hardware.org/?probe=8ba2c6e5ed) | May 26, 2023 |
| ASUSTek       | K30BF_M32BF_A_F_K31BF_6     | Desktop     | [2c3689440a](https://linux-hardware.org/?probe=2c3689440a) | May 26, 2023 |
| Lenovo        | Yoga C740 81TC              | Convertible | [baa223162c](https://linux-hardware.org/?probe=baa223162c) | May 24, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [cb61728cb7](https://linux-hardware.org/?probe=cb61728cb7) | May 22, 2023 |
| Biostar       | NF520D3                     | Desktop     | [806beba322](https://linux-hardware.org/?probe=806beba322) | May 20, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [1dda8d01ad](https://linux-hardware.org/?probe=1dda8d01ad) | May 20, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [fe4d0a2ec3](https://linux-hardware.org/?probe=fe4d0a2ec3) | May 20, 2023 |
| Dell          | 0YXT71 A03                  | Desktop     | [b8281f77a3](https://linux-hardware.org/?probe=b8281f77a3) | May 07, 2023 |
| HP            | Elite x2 1012 G1            | Notebook    | [20dcc3e6b3](https://linux-hardware.org/?probe=20dcc3e6b3) | May 04, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [b68d1b92de](https://linux-hardware.org/?probe=b68d1b92de) | May 03, 2023 |
| Dell          | Latitude XT2                | Notebook    | [3cfd979c60](https://linux-hardware.org/?probe=3cfd979c60) | Apr 30, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [f80f9b0671](https://linux-hardware.org/?probe=f80f9b0671) | Apr 28, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [a8f4a6f058](https://linux-hardware.org/?probe=a8f4a6f058) | Apr 27, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [ac51617470](https://linux-hardware.org/?probe=ac51617470) | Apr 26, 2023 |
| Acer          | Aspire R7-571G              | Notebook    | [d4220bc210](https://linux-hardware.org/?probe=d4220bc210) | Apr 25, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [9306db1f90](https://linux-hardware.org/?probe=9306db1f90) | Apr 25, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [0cfe2b34f5](https://linux-hardware.org/?probe=0cfe2b34f5) | Apr 25, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [006b9a2b3f](https://linux-hardware.org/?probe=006b9a2b3f) | Apr 24, 2023 |
| Lenovo        | SKYBAY SDK0J40709 WIN 32... | All in one  | [f68e55cabc](https://linux-hardware.org/?probe=f68e55cabc) | Apr 24, 2023 |
| ASUSTek       | AM1M-A                      | Desktop     | [b4e51d0af3](https://linux-hardware.org/?probe=b4e51d0af3) | Apr 17, 2023 |
| ASUSTek       | AM1M-A                      | Desktop     | [a6ba0d9290](https://linux-hardware.org/?probe=a6ba0d9290) | Apr 17, 2023 |
| Lenovo        | ThinkPad T431s 20ACS0640... | Notebook    | [711d09df05](https://linux-hardware.org/?probe=711d09df05) | Apr 04, 2023 |
| Samsung       | 750XED                      | Notebook    | [be19d0454d](https://linux-hardware.org/?probe=be19d0454d) | Mar 16, 2023 |
| Dell          | Precision M4800             | Notebook    | [57c57bb353](https://linux-hardware.org/?probe=57c57bb353) | Feb 22, 2023 |
| Gigabyte      | P65                         | Notebook    | [b3d7faba21](https://linux-hardware.org/?probe=b3d7faba21) | Feb 12, 2023 |
| Gigabyte      | P65                         | Notebook    | [25d871afca](https://linux-hardware.org/?probe=25d871afca) | Feb 11, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [13bdc2b06c](https://linux-hardware.org/?probe=13bdc2b06c) | Feb 03, 2023 |
| Lenovo        | ThinkPad L580 20LW0010GE    | Notebook    | [ed7b51b8bc](https://linux-hardware.org/?probe=ed7b51b8bc) | Feb 01, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [e197bd2a4b](https://linux-hardware.org/?probe=e197bd2a4b) | Jan 30, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [e5af375b93](https://linux-hardware.org/?probe=e5af375b93) | Jan 29, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [41d67fcba8](https://linux-hardware.org/?probe=41d67fcba8) | Jan 29, 2023 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| blendOS         | 136       | 96.45%  |
| blendOS Rolling | 5         | 3.55%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| blendOS | 141       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                        | Computers | Percent |
|--------------------------------|-----------|---------|
| 6.3.9-zen1-1-zen               | 63        | 43.45%  |
| 6.5.5-zen1-1-zen               | 19        | 13.1%   |
| 6.2.12-arch1-1                 | 9         | 6.21%   |
| 6.3.6-zen1-1-zen               | 5         | 3.45%   |
| 6.3.4-arch1-1                  | 3         | 2.07%   |
| 6.2.13-arch1-1                 | 3         | 2.07%   |
| 6.1.8-zen1-1-zen               | 3         | 2.07%   |
| 6.1.8-arch1-1                  | 3         | 2.07%   |
| 6.3.5-arch1-1                  | 2         | 1.38%   |
| 6.3.2-arch1-1                  | 2         | 1.38%   |
| 6.16.4-zen1-1-zen              | 2         | 1.38%   |
| 6.12.10-zen1-1-zen             | 2         | 1.38%   |
| 6.12.1-zen1-1-zen              | 2         | 1.38%   |
| 6.9.9-zen1-1-zen               | 1         | 0.69%   |
| 6.8.7-zen1-1-zen               | 1         | 0.69%   |
| 6.4.5-arch1-1                  | 1         | 0.69%   |
| 6.4.0-Yagakimi-T2-xanmod1-1-t2 | 1         | 0.69%   |
| 6.3.7-zen1-1-zen               | 1         | 0.69%   |
| 6.3.5-zen1-1-zen               | 1         | 0.69%   |
| 6.3.3-arch1-1                  | 1         | 0.69%   |
| 6.3.1-arch1-1                  | 1         | 0.69%   |
| 6.2.8-arch1-1-t2               | 1         | 0.69%   |
| 6.2.11-arch1-1                 | 1         | 0.69%   |
| 6.17.9-zen1-1-zen              | 1         | 0.69%   |
| 6.17.3-zen2-1-zen              | 1         | 0.69%   |
| 6.16.7-zen1-1-zen              | 1         | 0.69%   |
| 6.16.3-zen1-1-zen              | 1         | 0.69%   |
| 6.16.10-zen1-1-zen             | 1         | 0.69%   |
| 6.15.9-zen1-1-zen              | 1         | 0.69%   |
| 6.15.8-zen1-2-zen              | 1         | 0.69%   |
| 6.15.8-zen1-1-zen              | 1         | 0.69%   |
| 6.15.2-zen1-1-zen              | 1         | 0.69%   |
| 6.14.5-zen1-1-zen              | 1         | 0.69%   |
| 6.13.2-zen1-1-zen              | 1         | 0.69%   |
| 6.12.4-zen1-1-zen              | 1         | 0.69%   |
| 6.10.7-zen1-1-zen              | 1         | 0.69%   |
| 6.10.3-zen1-2-zen              | 1         | 0.69%   |
| 6.1.9-zen1-1-zen               | 1         | 0.69%   |
| 6.1.12-zen1-1-zen              | 1         | 0.69%   |
| 6.1.11-zen1-1-zen              | 1         | 0.69%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.3.9   | 63        | 43.45%  |
| 6.5.5   | 19        | 13.1%   |
| 6.2.12  | 9         | 6.21%   |
| 6.1.8   | 6         | 4.14%   |
| 6.3.6   | 5         | 3.45%   |
| 6.3.5   | 3         | 2.07%   |
| 6.3.4   | 3         | 2.07%   |
| 6.2.13  | 3         | 2.07%   |
| 6.3.2   | 2         | 1.38%   |
| 6.16.4  | 2         | 1.38%   |
| 6.15.8  | 2         | 1.38%   |
| 6.12.10 | 2         | 1.38%   |
| 6.12.1  | 2         | 1.38%   |
| 6.9.9   | 1         | 0.69%   |
| 6.8.7   | 1         | 0.69%   |
| 6.4.5   | 1         | 0.69%   |
| 6.4.0   | 1         | 0.69%   |
| 6.3.7   | 1         | 0.69%   |
| 6.3.3   | 1         | 0.69%   |
| 6.3.1   | 1         | 0.69%   |
| 6.2.8   | 1         | 0.69%   |
| 6.2.11  | 1         | 0.69%   |
| 6.17.9  | 1         | 0.69%   |
| 6.17.3  | 1         | 0.69%   |
| 6.16.7  | 1         | 0.69%   |
| 6.16.3  | 1         | 0.69%   |
| 6.16.10 | 1         | 0.69%   |
| 6.15.9  | 1         | 0.69%   |
| 6.15.2  | 1         | 0.69%   |
| 6.14.5  | 1         | 0.69%   |
| 6.13.2  | 1         | 0.69%   |
| 6.12.4  | 1         | 0.69%   |
| 6.10.7  | 1         | 0.69%   |
| 6.10.3  | 1         | 0.69%   |
| 6.1.9   | 1         | 0.69%   |
| 6.1.12  | 1         | 0.69%   |
| 6.1.11  | 1         | 0.69%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.3     | 79        | 55.63%  |
| 6.5     | 19        | 13.38%  |
| 6.2     | 13        | 9.15%   |
| 6.1     | 8         | 5.63%   |
| 6.16    | 5         | 3.52%   |
| 6.12    | 5         | 3.52%   |
| 6.15    | 3         | 2.11%   |
| 6.4     | 2         | 1.41%   |
| 6.17    | 2         | 1.41%   |
| 6.10    | 2         | 1.41%   |
| 6.9     | 1         | 0.7%    |
| 6.8     | 1         | 0.7%    |
| 6.14    | 1         | 0.7%    |
| 6.13    | 1         | 0.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 141       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 84        | 59.15%  |
| KDE5          | 54        | 38.03%  |
| KDE6          | 3         | 2.11%   |
| GNOME Classic | 1         | 0.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 129       | 88.97%  |
| X11     | 14        | 9.66%   |
| Unknown | 2         | 1.38%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 136       | 96.45%  |
| GDM     | 3         | 2.13%   |
| SDDM    | 2         | 1.42%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 84        | 59.57%  |
| de_DE       | 11        | 7.8%    |
| it_IT       | 7         | 4.96%   |
| fr_FR       | 6         | 4.26%   |
| en_GB       | 6         | 4.26%   |
| es_ES       | 4         | 2.84%   |
| en_AU       | 4         | 2.84%   |
| ru_RU       | 2         | 1.42%   |
| de_CH       | 2         | 1.42%   |
| tr_TR       | 1         | 0.71%   |
| sv_SE       | 1         | 0.71%   |
| ro_RO       | 1         | 0.71%   |
| pt_BR       | 1         | 0.71%   |
| nl_NL       | 1         | 0.71%   |
| fr_HT       | 1         | 0.71%   |
| es_UY       | 1         | 0.71%   |
| es_MX       | 1         | 0.71%   |
| es_CO       | 1         | 0.71%   |
| es_CL       | 1         | 0.71%   |
| es_AR       | 1         | 0.71%   |
| en_ZA       | 1         | 0.71%   |
| en_US.UTF.8 | 1         | 0.71%   |
| en_CA       | 1         | 0.71%   |
| de_AT       | 1         | 0.71%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 137       | 97.16%  |
| EFI  | 4         | 2.84%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 116       | 82.27%  |
| Tmpfs | 16        | 11.35%  |
| Btrfs | 7         | 4.96%   |
| XXXfs | 1         | 0.71%   |
| Xfs   | 1         | 0.71%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 136       | 96.45%  |
| GPT     | 5         | 3.55%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 139       | 98.58%  |
| Yes       | 2         | 1.42%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 141       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 22        | 15.6%   |
| Hewlett-Packard     | 17        | 12.06%  |
| Dell                | 16        | 11.35%  |
| ASUSTek Computer    | 14        | 9.93%   |
| Apple               | 11        | 7.8%    |
| MSI                 | 10        | 7.09%   |
| Gigabyte Technology | 8         | 5.67%   |
| Samsung Electronics | 5         | 3.55%   |
| ASRock              | 5         | 3.55%   |
| Acer                | 5         | 3.55%   |
| Microsoft           | 2         | 1.42%   |
| Hampoo              | 2         | 1.42%   |
| Fujitsu             | 2         | 1.42%   |
| Alienware           | 2         | 1.42%   |
| Toshiba             | 1         | 0.71%   |
| Supermicro          | 1         | 0.71%   |
| ShangMai            | 1         | 0.71%   |
| PINNACLEMICRO       | 1         | 0.71%   |
| Pegatron            | 1         | 0.71%   |
| Panasonic           | 1         | 0.71%   |
| OriginPC            | 1         | 0.71%   |
| Notebook            | 1         | 0.71%   |
| MAXSUN              | 1         | 0.71%   |
| LG Electronics      | 1         | 0.71%   |
| JINGSHA             | 1         | 0.71%   |
| Intel               | 1         | 0.71%   |
| HUAWEI              | 1         | 0.71%   |
| Google              | 1         | 0.71%   |
| Fanless Mini PC     | 1         | 0.71%   |
| Chuwi               | 1         | 0.71%   |
| Biostar             | 1         | 0.71%   |
| Beelink             | 1         | 0.71%   |
| AZW                 | 1         | 0.71%   |
| Unknown             | 1         | 0.71%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Dell OptiPlex 7010                   | 4         | 2.84%   |
| Microsoft Surface Laptop             | 2         | 1.42%   |
| HP Notebook                          | 2         | 1.42%   |
| ASUS All Series                      | 2         | 1.42%   |
| Apple MacPro5,1                      | 2         | 1.42%   |
| Apple MacBookPro11,1                 | 2         | 1.42%   |
| Toshiba QOSMIO X75-A                 | 1         | 0.71%   |
| Supermicro Super Server              | 1         | 0.71%   |
| ShangMai H                           | 1         | 0.71%   |
| Samsung Galaxy TabPro S              | 1         | 0.71%   |
| Samsung 950XDB/951XDB/950XDY         | 1         | 0.71%   |
| Samsung 750XEE                       | 1         | 0.71%   |
| Samsung 750XED                       | 1         | 0.71%   |
| Samsung 550P5C/550P7C                | 1         | 0.71%   |
| PINNACLEMICRO W76OC                  | 1         | 0.71%   |
| Pegatron p7-1154                     | 1         | 0.71%   |
| Panasonic CF-19ADNAXDA               | 1         | 0.71%   |
| OriginPC EON17-X                     | 1         | 0.71%   |
| Notebook P65_P67SA                   | 1         | 0.71%   |
| MSI Pulse GL66 11UGK                 | 1         | 0.71%   |
| MSI MS-7E26                          | 1         | 0.71%   |
| MSI MS-7C56                          | 1         | 0.71%   |
| MSI MS-7C52                          | 1         | 0.71%   |
| MSI MS-7B79                          | 1         | 0.71%   |
| MSI MS-7592                          | 1         | 0.71%   |
| MSI MS-16Y1                          | 1         | 0.71%   |
| MSI MAG B550 META 5 (MS-B930)        | 1         | 0.71%   |
| MSI GS66 Stealth 10SF                | 1         | 0.71%   |
| MSI GP63 Leopard 8RE                 | 1         | 0.71%   |
| MAXSUN MS-Terminator B660M VER:H4.2G | 1         | 0.71%   |
| LG 16Z90Q-G.AP7BB                    | 1         | 0.71%   |
| Lenovo Yoga C740 81TC                | 1         | 0.71%   |
| Lenovo Yoga 9 14ITL5 82BG            | 1         | 0.71%   |
| Lenovo Yoga 2 Pro 20266              | 1         | 0.71%   |
| Lenovo ThinkPad T431s 20ACS06400     | 1         | 0.71%   |
| Lenovo ThinkPad P52 20M9CTO1WW       | 1         | 0.71%   |
| Lenovo ThinkPad L580 20LW0010GE      | 1         | 0.71%   |
| Lenovo ThinkPad L470 20J5S0JM00      | 1         | 0.71%   |
| Lenovo ThinkPad E470 20H1004UIG      | 1         | 0.71%   |
| Lenovo Legion C530-19ICB 90JX0040GE  | 1         | 0.71%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo IdeaPad         | 6         | 4.26%   |
| HP Pavilion            | 6         | 4.26%   |
| Lenovo ThinkPad        | 5         | 3.55%   |
| Dell XPS               | 4         | 2.84%   |
| Dell OptiPlex          | 4         | 2.84%   |
| Acer Aspire            | 4         | 2.84%   |
| Lenovo Yoga            | 3         | 2.13%   |
| HP ProBook             | 3         | 2.13%   |
| Dell Inspiron          | 3         | 2.13%   |
| Microsoft Surface      | 2         | 1.42%   |
| Lenovo Legion          | 2         | 1.42%   |
| HP Notebook            | 2         | 1.42%   |
| Gigabyte B550M         | 2         | 1.42%   |
| Dell Precision         | 2         | 1.42%   |
| Dell Latitude          | 2         | 1.42%   |
| ASUS TUF               | 2         | 1.42%   |
| ASUS ROG               | 2         | 1.42%   |
| ASUS PRIME             | 2         | 1.42%   |
| ASUS All               | 2         | 1.42%   |
| ASRock X670E           | 2         | 1.42%   |
| Apple MacPro5          | 2         | 1.42%   |
| Apple MacBookPro8      | 2         | 1.42%   |
| Apple MacBookPro11     | 2         | 1.42%   |
| Toshiba QOSMIO         | 1         | 0.71%   |
| Supermicro Super       | 1         | 0.71%   |
| ShangMai H             | 1         | 0.71%   |
| Samsung Galaxy         | 1         | 0.71%   |
| Samsung 950XDB         | 1         | 0.71%   |
| Samsung 750XEE         | 1         | 0.71%   |
| Samsung 750XED         | 1         | 0.71%   |
| Samsung 550P5C         | 1         | 0.71%   |
| PINNACLEMICRO W76OC    | 1         | 0.71%   |
| Pegatron p7-1154       | 1         | 0.71%   |
| Panasonic CF-19ADNAXDA | 1         | 0.71%   |
| OriginPC EON17-X       | 1         | 0.71%   |
| Notebook P65           | 1         | 0.71%   |
| MSI Pulse              | 1         | 0.71%   |
| MSI MS-7E26            | 1         | 0.71%   |
| MSI MS-7C56            | 1         | 0.71%   |
| MSI MS-7C52            | 1         | 0.71%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 13        | 9.22%   |
| 2016 | 13        | 9.22%   |
| 2013 | 13        | 9.22%   |
| 2022 | 12        | 8.51%   |
| 2019 | 12        | 8.51%   |
| 2020 | 11        | 7.8%    |
| 2011 | 11        | 7.8%    |
| 2018 | 9         | 6.38%   |
| 2014 | 9         | 6.38%   |
| 2023 | 8         | 5.67%   |
| 2012 | 7         | 4.96%   |
| 2017 | 6         | 4.26%   |
| 2015 | 6         | 4.26%   |
| 2010 | 4         | 2.84%   |
| 2009 | 4         | 2.84%   |
| 2024 | 1         | 0.71%   |
| 2008 | 1         | 0.71%   |
| 2007 | 1         | 0.71%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 76        | 53.9%   |
| Desktop     | 48        | 34.04%  |
| Tablet      | 5         | 3.55%   |
| Convertible | 5         | 3.55%   |
| Mini pc     | 3         | 2.13%   |
| All in one  | 3         | 2.13%   |
| Server      | 1         | 0.71%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 141       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 140       | 99.29%  |
| Yes  | 1         | 0.71%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 43        | 30.28%  |
| 32.01-64.0      | 25        | 17.61%  |
| 16.01-24.0      | 25        | 17.61%  |
| 8.01-16.0       | 23        | 16.2%   |
| 3.01-4.0        | 15        | 10.56%  |
| 64.01-256.0     | 6         | 4.23%   |
| 24.01-32.0      | 3         | 2.11%   |
| More than 256.0 | 1         | 0.7%    |
| 1.01-2.0        | 1         | 0.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 4.01-8.0  | 47        | 32.19%  |
| 3.01-4.0  | 42        | 28.77%  |
| 2.01-3.0  | 39        | 26.71%  |
| 1.01-2.0  | 12        | 8.22%   |
| 8.01-16.0 | 6         | 4.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 87        | 61.27%  |
| 2      | 30        | 21.13%  |
| 3      | 13        | 9.15%   |
| 4      | 7         | 4.93%   |
| 5      | 2         | 1.41%   |
| 9      | 1         | 0.7%    |
| 6      | 1         | 0.7%    |
| 0      | 1         | 0.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 107       | 75.89%  |
| Yes       | 34        | 24.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 112       | 79.43%  |
| No        | 29        | 20.57%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 122       | 86.52%  |
| No        | 19        | 13.48%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 103       | 73.05%  |
| No        | 38        | 26.95%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 36        | 25.53%  |
| Germany            | 21        | 14.89%  |
| UK                 | 8         | 5.67%   |
| Italy              | 8         | 5.67%   |
| India              | 7         | 4.96%   |
| France             | 6         | 4.26%   |
| Australia          | 5         | 3.55%   |
| Spain              | 4         | 2.84%   |
| Russia             | 3         | 2.13%   |
| Poland             | 3         | 2.13%   |
| Mexico             | 3         | 2.13%   |
| Brazil             | 3         | 2.13%   |
| Switzerland        | 2         | 1.42%   |
| Sweden             | 2         | 1.42%   |
| South Africa       | 2         | 1.42%   |
| Kenya              | 2         | 1.42%   |
| Canada             | 2         | 1.42%   |
| Belgium            | 2         | 1.42%   |
| Austria            | 2         | 1.42%   |
| Argentina          | 2         | 1.42%   |
| Uruguay            | 1         | 0.71%   |
| Turkey             | 1         | 0.71%   |
| Romania            | 1         | 0.71%   |
| Portugal           | 1         | 0.71%   |
| Palestine          | 1         | 0.71%   |
| Norway             | 1         | 0.71%   |
| Netherlands        | 1         | 0.71%   |
| Nepal              | 1         | 0.71%   |
| Namibia            | 1         | 0.71%   |
| Morocco            | 1         | 0.71%   |
| Malaysia           | 1         | 0.71%   |
| Greece             | 1         | 0.71%   |
| Egypt              | 1         | 0.71%   |
| Dominican Republic | 1         | 0.71%   |
| Czechia            | 1         | 0.71%   |
| Cyprus             | 1         | 0.71%   |
| Colombia           | 1         | 0.71%   |
| Chile              | 1         | 0.71%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| Sydney                    | 2         | 1.4%    |
| San Antonio               | 2         | 1.4%    |
| Rome                      | 2         | 1.4%    |
| Perth                     | 2         | 1.4%    |
| Nairobi                   | 2         | 1.4%    |
| Munich                    | 2         | 1.4%    |
| Kalsdorf bei Graz         | 2         | 1.4%    |
| Delhi                     | 2         | 1.4%    |
| Cape Town                 | 2         | 1.4%    |
| Birmingham                | 2         | 1.4%    |
| Berlin                    | 2         | 1.4%    |
| Bangor                    | 2         | 1.4%    |
| Würzburg                 | 1         | 0.7%    |
| Windhoek                  | 1         | 0.7%    |
| Walla Walla               | 1         | 0.7%    |
| Villepinte                | 1         | 0.7%    |
| Versailles                | 1         | 0.7%    |
| Unna                      | 1         | 0.7%    |
| Treillieres               | 1         | 0.7%    |
| The Hague                 | 1         | 0.7%    |
| The Bronx                 | 1         | 0.7%    |
| Tarnówka                 | 1         | 0.7%    |
| Tampa                     | 1         | 0.7%    |
| Sundern                   | 1         | 0.7%    |
| Stuttgart                 | 1         | 0.7%    |
| Stratford-upon-Avon       | 1         | 0.7%    |
| Stockton-on-Tees          | 1         | 0.7%    |
| Southwest Harbor          | 1         | 0.7%    |
| Somerset                  | 1         | 0.7%    |
| Skövde                   | 1         | 0.7%    |
| Skien                     | 1         | 0.7%    |
| Sete Lagoas               | 1         | 0.7%    |
| Seraing                   | 1         | 0.7%    |
| Saratov                   | 1         | 0.7%    |
| Sao Domingos de Rana      | 1         | 0.7%    |
| Santo Domingo Este        | 1         | 0.7%    |
| San Nicolás de los Garza | 1         | 0.7%    |
| Salvador Escalante        | 1         | 0.7%    |
| Saint Cloud               | 1         | 0.7%    |
| Rosny-sous-Bois           | 1         | 0.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 37        | 43     | 17.79%  |
| WDC                            | 24        | 33     | 11.54%  |
| Seagate                        | 19        | 28     | 9.13%   |
| SanDisk                        | 16        | 17     | 7.69%   |
| Unknown                        | 11        | 11     | 5.29%   |
| Crucial                        | 10        | 12     | 4.81%   |
| Kingston                       | 8         | 9      | 3.85%   |
| Toshiba                        | 7         | 8      | 3.37%   |
| SK hynix                       | 6         | 7      | 2.88%   |
| China                          | 6         | 6      | 2.88%   |
| Phison Electronics             | 5         | 7      | 2.4%    |
| Intel                          | 5         | 6      | 2.4%    |
| Hitachi                        | 5         | 6      | 2.4%    |
| Apple                          | 4         | 5      | 1.92%   |
| ADATA Technology               | 4         | 4      | 1.92%   |
| HGST                           | 3         | 4      | 1.44%   |
| SPCC                           | 2         | 3      | 0.96%   |
| Silicon Motion                 | 2         | 3      | 0.96%   |
| SD                             | 2         | 2      | 0.96%   |
| Micron/Crucial Technology      | 2         | 2      | 0.96%   |
| Micron Technology              | 2         | 3      | 0.96%   |
| LITEON                         | 2         | 2      | 0.96%   |
| Intenso                        | 2         | 2      | 0.96%   |
| Gigabyte Technology            | 2         | 2      | 0.96%   |
| T-FORCE                        | 1         | 1      | 0.48%   |
| StoreJet                       | 1         | 1      | 0.48%   |
| Solid State Storage Technology | 1         | 1      | 0.48%   |
| Patriot                        | 1         | 1      | 0.48%   |
| NT-2TB                         | 1         | 2      | 0.48%   |
| MOVESPEED                      | 1         | 1      | 0.48%   |
| MAXIO Technology (Hangzhou)    | 1         | 1      | 0.48%   |
| MAS                            | 1         | 1      | 0.48%   |
| LaCie                          | 1         | 1      | 0.48%   |
| KIOXIA                         | 1         | 1      | 0.48%   |
| Kingston Technology Company    | 1         | 1      | 0.48%   |
| KingFast                       | 1         | 1      | 0.48%   |
| INNOVATION IT                  | 1         | 1      | 0.48%   |
| HUAWEI                         | 1         | 1      | 0.48%   |
| HS-SSD-C100                    | 1         | 1      | 0.48%   |
| Hikvision                      | 1         | 1      | 0.48%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB                  | 10        | 4.46%   |
| Samsung SSD 850 EVO 500GB                                          | 4         | 1.79%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB                 | 4         | 1.79%   |
| Unknown MMC Card  64GB                                             | 3         | 1.34%   |
| Unknown MMC Card  128GB                                            | 3         | 1.34%   |
| Sandisk WD Black SN850 1TB                                         | 3         | 1.34%   |
| Crucial CT250MX500SSD1 250GB                                       | 3         | 1.34%   |
| China SSD 240GB                                                    | 3         | 1.34%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 1024GB | 3         | 1.34%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                                   | 2         | 0.89%   |
| WDC WD Blue SA510 2.5 500GB                                        | 2         | 0.89%   |
| Unknown NVMe SSD Drive 512GB                                       | 2         | 0.89%   |
| Toshiba DT01ACA100 1TB                                             | 2         | 0.89%   |
| Seagate ST1000LM035-1RK172 1TB                                     | 2         | 0.89%   |
| Seagate ST1000DM010-2EP102 1TB                                     | 2         | 0.89%   |
| Seagate ST1000DM003-1SB102 1TB                                     | 2         | 0.89%   |
| SD Ultra 3D 1TB                                                    | 2         | 0.89%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB                              | 2         | 0.89%   |
| SanDisk SSD PLUS 1000GB                                            | 2         | 0.89%   |
| Samsung SSD 850 EVO 250GB                                          | 2         | 0.89%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB               | 2         | 0.89%   |
| Phison PS5013 E13 NVMe Controller 500GB                            | 2         | 0.89%   |
| Phison E16 PCIe4 NVMe Controller 1TB                               | 2         | 0.89%   |
| Intel SSDSC2KB240G8 240GB                                          | 2         | 0.89%   |
| HGST HTS725050A7E630 500GB                                         | 2         | 0.89%   |
| Apple SSD SM0256F 256GB                                            | 2         | 0.89%   |
| WDC WDS500G2B0A-00SM50 500GB                                       | 1         | 0.45%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD                                   | 1         | 0.45%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                                     | 1         | 0.45%   |
| WDC WD80EZAZ-11TDBA0 8TB                                           | 1         | 0.45%   |
| WDC WD7500AAVS-00D7B1 752GB                                        | 1         | 0.45%   |
| WDC WD6400BPVT-22HXZT1 640GB                                       | 1         | 0.45%   |
| WDC WD6002FRYZ-01WD5B0 6TB                                         | 1         | 0.45%   |
| WDC WD5000LPCX-24C6HT0 500GB                                       | 1         | 0.45%   |
| WDC WD5000AZRX-00L4HB0 500GB                                       | 1         | 0.45%   |
| WDC WD40EFRX-68WT0N0 4TB                                           | 1         | 0.45%   |
| WDC WD4005FZBX-00K5WB0 4TB                                         | 1         | 0.45%   |
| WDC WD3200BEVT-00A0RT0 320GB                                       | 1         | 0.45%   |
| WDC WD3200AAKS-00V1A0 320GB                                        | 1         | 0.45%   |
| WDC WD3200AAJS-08L7A0 320GB                                        | 1         | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 19        | 24     | 35.85%  |
| Seagate  | 19        | 28     | 35.85%  |
| Toshiba  | 5         | 6      | 9.43%   |
| Hitachi  | 5         | 6      | 9.43%   |
| HGST     | 3         | 4      | 5.66%   |
| T-FORCE  | 1         | 1      | 1.89%   |
| External | 1         | 1      | 1.89%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 18        | 20     | 23.38%  |
| Crucial             | 10        | 12     | 12.99%  |
| WDC                 | 7         | 9      | 9.09%   |
| China               | 6         | 6      | 7.79%   |
| SanDisk             | 5         | 6      | 6.49%   |
| Kingston            | 4         | 5      | 5.19%   |
| Apple               | 3         | 3      | 3.9%    |
| SPCC                | 2         | 3      | 2.6%    |
| SD                  | 2         | 2      | 2.6%    |
| LITEON              | 2         | 2      | 2.6%    |
| Intenso             | 2         | 2      | 2.6%    |
| Intel               | 2         | 2      | 2.6%    |
| Gigabyte Technology | 2         | 2      | 2.6%    |
| StoreJet            | 1         | 1      | 1.3%    |
| SK hynix            | 1         | 1      | 1.3%    |
| Patriot             | 1         | 1      | 1.3%    |
| NT-2TB              | 1         | 2      | 1.3%    |
| MOVESPEED           | 1         | 1      | 1.3%    |
| Micron Technology   | 1         | 1      | 1.3%    |
| KingFast            | 1         | 1      | 1.3%    |
| INNOVATION IT       | 1         | 1      | 1.3%    |
| Hikvision           | 1         | 1      | 1.3%    |
| EVM                 | 1         | 1      | 1.3%    |
| AirDisk             | 1         | 1      | 1.3%    |
| A-DATA Technology   | 1         | 1      | 1.3%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 67        | 87     | 35.83%  |
| NVMe    | 62        | 77     | 33.16%  |
| HDD     | 44        | 70     | 23.53%  |
| MMC     | 8         | 8      | 4.28%   |
| Unknown | 6         | 6      | 3.21%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 95        | 155    | 54.91%  |
| NVMe | 62        | 77     | 35.84%  |
| SAS  | 8         | 8      | 4.62%   |
| MMC  | 8         | 8      | 4.62%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 63        | 81     | 52.5%   |
| 0.51-1.0   | 37        | 48     | 30.83%  |
| 1.01-2.0   | 9         | 11     | 7.5%    |
| 3.01-4.0   | 8         | 8      | 6.67%   |
| 4.01-10.0  | 2         | 8      | 1.67%   |
| 10.01-20.0 | 1         | 1      | 0.83%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 47        | 33.33%  |
| 501-1000       | 34        | 24.11%  |
| 251-500        | 29        | 20.57%  |
| 1001-2000      | 12        | 8.51%   |
| 51-100         | 7         | 4.96%   |
| More than 3000 | 5         | 3.55%   |
| 2001-3000      | 2         | 1.42%   |
| 1-20           | 2         | 1.42%   |
| Unknown        | 2         | 1.42%   |
| 21-50          | 1         | 0.71%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 54        | 37.5%   |
| 21-50          | 48        | 33.33%  |
| 51-100         | 14        | 9.72%   |
| 101-250        | 10        | 6.94%   |
| 251-500        | 8         | 5.56%   |
| 501-1000       | 5         | 3.47%   |
| More than 3000 | 2         | 1.39%   |
| Unknown        | 2         | 1.39%   |
| 1001-2000      | 1         | 0.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                    | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| WDC WD10EARS-00MVWB0 1TB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1         | 1      | 100%    |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 138       | 240    | 96.5%   |
| Works    | 4         | 7      | 2.8%    |
| Malfunc  | 1         | 1      | 0.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 82        | 45.05%  |
| AMD                            | 29        | 15.93%  |
| Samsung Electronics            | 23        | 12.64%  |
| SanDisk                        | 11        | 6.04%   |
| SK hynix                       | 5         | 2.75%   |
| Phison Electronics             | 5         | 2.75%   |
| Kingston Technology Company    | 5         | 2.75%   |
| ADATA Technology               | 4         | 2.2%    |
| Toshiba America Info Systems   | 2         | 1.1%    |
| Silicon Motion                 | 2         | 1.1%    |
| Nvidia                         | 2         | 1.1%    |
| Micron/Crucial Technology      | 2         | 1.1%    |
| Unknown                        | 2         | 1.1%    |
| Solidigm                       | 1         | 0.55%   |
| Solid State Storage Technology | 1         | 0.55%   |
| Micron Technology              | 1         | 0.55%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.55%   |
| Marvell Technology Group       | 1         | 0.55%   |
| KIOXIA                         | 1         | 0.55%   |
| HighPoint Technologies         | 1         | 0.55%   |
| Apple                          | 1         | 0.55%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 15        | 7.39%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 10        | 4.93%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 3.45%   |
| AMD 500 Series Chipset SATA Controller                                         | 7         | 3.45%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 6         | 2.96%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 6         | 2.96%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 2.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 6         | 2.96%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 1.97%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 1.97%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.97%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 1.97%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4         | 1.97%   |
| AMD 600 Series Chipset SATA Controller                                         | 4         | 1.97%   |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 1.97%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 1.48%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 3         | 1.48%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 3         | 1.48%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 1.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3         | 1.48%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 3         | 1.48%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 2         | 0.99%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                             | 2         | 0.99%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 0.99%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 2         | 0.99%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2         | 0.99%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 2         | 0.99%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 0.99%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2         | 0.99%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 0.99%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 0.99%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 2         | 0.99%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2         | 0.99%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 2         | 0.99%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 0.99%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2         | 0.99%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2         | 0.99%   |
| Unknown                                                                        | 2         | 0.99%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.49%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 1         | 0.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 100       | 53.76%  |
| NVMe | 62        | 33.33%  |
| RAID | 13        | 6.99%   |
| IDE  | 11        | 5.91%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 109       | 77.3%   |
| AMD    | 32        | 22.7%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 4         | 2.84%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 3         | 2.13%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 3         | 2.13%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3         | 2.13%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 2         | 1.42%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 1.42%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 2         | 1.42%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 2         | 1.42%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 2         | 1.42%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.42%   |
| Intel Core i5-4250U CPU @ 1.30GHz           | 2         | 1.42%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.42%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 2         | 1.42%   |
| Intel 12th Gen Core i7-1260P                | 2         | 1.42%   |
| Intel 12th Gen Core i3-1215U                | 2         | 1.42%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 1.42%   |
| AMD Ryzen 9 7950X 16-Core Processor         | 2         | 1.42%   |
| Intel Xeon CPU X5690 @ 3.47GHz              | 1         | 0.71%   |
| Intel Xeon CPU X5660 @ 2.80GHz              | 1         | 0.71%   |
| Intel Xeon CPU X3220 @ 2.40GHz              | 1         | 0.71%   |
| Intel Xeon CPU E5430 @ 2.66GHz              | 1         | 0.71%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz         | 1         | 0.71%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz         | 1         | 0.71%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 1         | 0.71%   |
| Intel Pentium Gold 7505 @ 2.00GHz           | 1         | 0.71%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 0.71%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 0.71%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 1         | 0.71%   |
| Intel N100                                  | 1         | 0.71%   |
| Intel Genuine CPU 0000 @ 2.60GHz            | 1         | 0.71%   |
| Intel Core m7-6Y75 CPU @ 1.20GHz            | 1         | 0.71%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz            | 1         | 0.71%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.71%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 0.71%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 0.71%   |
| Intel Core i7-7660U CPU @ 2.50GHz           | 1         | 0.71%   |
| Intel Core i7-6950X CPU @ 3.00GHz           | 1         | 0.71%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 1         | 0.71%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1         | 0.71%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz          | 1         | 0.71%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 31        | 21.99%  |
| Intel Core i7           | 29        | 20.57%  |
| Other                   | 18        | 12.77%  |
| AMD Ryzen 5             | 10        | 7.09%   |
| Intel Xeon              | 6         | 4.26%   |
| AMD Ryzen 7             | 6         | 4.26%   |
| Intel Celeron           | 5         | 3.55%   |
| Intel Pentium           | 4         | 2.84%   |
| Intel Core i3           | 4         | 2.84%   |
| AMD Ryzen 9             | 4         | 2.84%   |
| AMD A6                  | 4         | 2.84%   |
| Intel Core 2 Duo        | 3         | 2.13%   |
| Intel Atom              | 2         | 1.42%   |
| AMD A10                 | 2         | 1.42%   |
| Intel Pentium Silver    | 1         | 0.71%   |
| Intel Pentium Gold      | 1         | 0.71%   |
| Intel Pentium Dual-Core | 1         | 0.71%   |
| Intel Genuine           | 1         | 0.71%   |
| Intel Core m7           | 1         | 0.71%   |
| Intel Core m3           | 1         | 0.71%   |
| Intel Core 2 Quad       | 1         | 0.71%   |
| AMD Sempron             | 1         | 0.71%   |
| AMD Ryzen 3             | 1         | 0.71%   |
| AMD Phenom II X4        | 1         | 0.71%   |
| AMD FX                  | 1         | 0.71%   |
| AMD E2                  | 1         | 0.71%   |
| AMD Athlon II X2        | 1         | 0.71%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 51        | 36.17%  |
| 2      | 48        | 34.04%  |
| 6      | 21        | 14.89%  |
| 8      | 8         | 5.67%   |
| 12     | 7         | 4.96%   |
| 16     | 3         | 2.13%   |
| 10     | 2         | 1.42%   |
| 24     | 1         | 0.71%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 137       | 97.16%  |
| 2      | 4         | 2.84%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 101       | 71.63%  |
| 1      | 40        | 28.37%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 141       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 140       | 99.29%  |
| 0x06003106 | 1         | 0.71%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 20        | 14.18%  |
| Unknown       | 18        | 12.77%  |
| Haswell       | 17        | 12.06%  |
| SandyBridge   | 10        | 7.09%   |
| IvyBridge     | 10        | 7.09%   |
| Zen 3         | 7         | 4.96%   |
| TigerLake     | 7         | 4.96%   |
| Skylake       | 7         | 4.96%   |
| Silvermont    | 5         | 3.55%   |
| Penryn        | 5         | 3.55%   |
| Zen+          | 4         | 2.84%   |
| Zen 2         | 4         | 2.84%   |
| Westmere      | 3         | 2.13%   |
| Puma          | 3         | 2.13%   |
| Goldmont plus | 3         | 2.13%   |
| CometLake     | 3         | 2.13%   |
| Piledriver    | 2         | 1.42%   |
| K10           | 2         | 1.42%   |
| IceLake       | 2         | 1.42%   |
| Core          | 2         | 1.42%   |
| Broadwell     | 2         | 1.42%   |
| Zen           | 1         | 0.71%   |
| Steamroller   | 1         | 0.71%   |
| K10 Llano     | 1         | 0.71%   |
| Jaguar        | 1         | 0.71%   |
| Excavator     | 1         | 0.71%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 90        | 53.57%  |
| Nvidia | 42        | 25%     |
| AMD    | 36        | 21.43%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 5.65%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 5.08%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 2.82%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 2.82%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 4         | 2.26%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 2.26%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 2.26%   |
| AMD Raphael                                                                              | 4         | 2.26%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 2.26%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 2.26%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 1.69%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 3         | 1.69%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 1.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.69%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 3         | 1.69%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 1.69%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                                        | 3         | 1.69%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 1.13%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 1.13%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 1.13%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 2         | 1.13%   |
| Nvidia GA104 [GeForce RTX 3060]                                                          | 2         | 1.13%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 2         | 1.13%   |
| Intel Skylake-Y GT2 [HD Graphics 515]                                                    | 2         | 1.13%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.13%   |
| Intel Kaby Lake-U GT3 [Iris Plus Graphics 640]                                           | 2         | 1.13%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 2         | 1.13%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.13%   |
| Intel Alder Lake-UP3 GT1 [UHD Graphics]                                                  | 2         | 1.13%   |
| AMD Navi 33 [Radeon RX 7600/7600 XT/7600M XT/7600S/7700S / PRO W7600]                    | 2         | 1.13%   |
| AMD Navi 32 [Radeon RX 7700 XT / 7800 XT]                                                | 2         | 1.13%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900 GRE/7900M]                                  | 2         | 1.13%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 2         | 1.13%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 1.13%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.56%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1         | 0.56%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1         | 0.56%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                                  | 1         | 0.56%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 65        | 46.1%   |
| 1 x AMD        | 25        | 17.73%  |
| Intel + Nvidia | 22        | 15.6%   |
| 1 x Nvidia     | 17        | 12.06%  |
| 2 x AMD        | 7         | 4.96%   |
| Intel + AMD    | 2         | 1.42%   |
| AMD + Nvidia   | 2         | 1.42%   |
| 2 x Nvidia     | 1         | 0.71%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 116       | 82.27%  |
| Proprietary | 24        | 17.02%  |
| Unknown     | 1         | 0.71%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 133       | 93.66%  |
| 8.01-16.0  | 3         | 2.11%   |
| 7.01-8.0   | 2         | 1.41%   |
| 1.01-2.0   | 2         | 1.41%   |
| 5.01-6.0   | 1         | 0.7%    |
| 0.51-1.0   | 1         | 0.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 26        | 16.99%  |
| AU Optronics            | 15        | 9.8%    |
| Chimei Innolux          | 13        | 8.5%    |
| BOE                     | 13        | 8.5%    |
| LG Display              | 12        | 7.84%   |
| Goldstar                | 8         | 5.23%   |
| Dell                    | 8         | 5.23%   |
| Apple                   | 7         | 4.58%   |
| Acer                    | 6         | 3.92%   |
| Sharp                   | 5         | 3.27%   |
| Philips                 | 4         | 2.61%   |
| Vizio                   | 3         | 1.96%   |
| Lenovo                  | 3         | 1.96%   |
| AOC                     | 3         | 1.96%   |
| Panasonic               | 2         | 1.31%   |
| Iiyama                  | 2         | 1.31%   |
| Fujitsu Siemens         | 2         | 1.31%   |
| Ancor Communications    | 2         | 1.31%   |
| Sony                    | 1         | 0.65%   |
| SGN                     | 1         | 0.65%   |
| Sceptre Tech            | 1         | 0.65%   |
| PRI                     | 1         | 0.65%   |
| Pixio                   | 1         | 0.65%   |
| PANDA                   | 1         | 0.65%   |
| Onkyo                   | 1         | 0.65%   |
| MStar                   | 1         | 0.65%   |
| KDB                     | 1         | 0.65%   |
| InnoLux Display         | 1         | 0.65%   |
| InfoVision              | 1         | 0.65%   |
| HUAWEI                  | 1         | 0.65%   |
| Hewlett-Packard         | 1         | 0.65%   |
| CSO                     | 1         | 0.65%   |
| Chi Mei Optoelectronics | 1         | 0.65%   |
| CEN                     | 1         | 0.65%   |
| BenQ                    | 1         | 0.65%   |
| ASUSTek Computer        | 1         | 0.65%   |
| AOpen                   | 1         | 0.65%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Vizio D43f-F1 VIZ1027 1920x1080 940x529mm 42.5-inch                     | 2         | 1.3%    |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch   | 2         | 1.3%    |
| Samsung Electronics LCD Monitor SAM5448 1920x1080                       | 2         | 1.3%    |
| Panasonic VVX11F009G00 MEI96A2 1920x1080 344x193mm 15.5-inch            | 2         | 1.3%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch           | 2         | 1.3%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch          | 2         | 1.3%    |
| Acer EB321HQU C ACR0507 2560x1440 699x393mm 31.6-inch                   | 2         | 1.3%    |
| Vizio V405-G9 VIZ1033 3840x2160 1096x616mm 49.5-inch                    | 1         | 0.65%   |
| Sony TV SNYF500 1360x768                                                | 1         | 0.65%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                 | 1         | 0.65%   |
| Sharp LCD Monitor SHP1548 1920x1200 288x180mm 13.4-inch                 | 1         | 0.65%   |
| Sharp LCD Monitor SHP14AF 1920x1200 288x180mm 13.4-inch                 | 1         | 0.65%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                 | 1         | 0.65%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                 | 1         | 0.65%   |
| SGN L01N8A SGN11C0 800x1280                                             | 1         | 0.65%   |
| Sceptre Tech Sceptre K27 SPT0AA4 1920x1080 600x330mm 27.0-inch          | 1         | 0.65%   |
| Samsung Electronics U28H75x SAM0E00 3840x2160 607x345mm 27.5-inch       | 1         | 0.65%   |
| Samsung Electronics SyncMaster SAM05EB 1920x1080 597x336mm 27.0-inch    | 1         | 0.65%   |
| Samsung Electronics SyncMaster SAM05B0 1920x1080                        | 1         | 0.65%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 1         | 0.65%   |
| Samsung Electronics Odyssey G5 SAM7489 2560x1440 698x393mm 31.5-inch    | 1         | 0.65%   |
| Samsung Electronics LF27T35 SAM707F 1920x1080 598x337mm 27.0-inch       | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC4256 1600x900 382x215mm 17.3-inch    | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 254x169mm 12.0-inch   | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC314B 1600x900 344x194mm 15.5-inch    | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch    | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC424A 3200x1800 293x165mm 13.2-inch   | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch   | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SAM7129 3840x2160 950x540mm 43.0-inch   | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SAM0F09 3840x2160 1872x1053mm 84.6-inch | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 890x500mm 40.2-inch   | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 885x498mm 40.0-inch   | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1060x626mm 48.5-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SAM090B 1920x1080 1020x570mm 46.0-inch  | 1         | 0.65%   |
| Samsung Electronics F24G3xTF SAM710A 1920x1080 527x296mm 23.8-inch      | 1         | 0.65%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch       | 1         | 0.65%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 600x340mm 27.2-inch       | 1         | 0.65%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 1         | 0.65%   |
| PRI BBY LCD TV PRI0032 1360x768 700x390mm 31.5-inch                     | 1         | 0.65%   |
| Pixio SFP2702G FHD WAM2700 1920x1080 597x336mm 27.0-inch                | 1         | 0.65%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 64        | 44.14%  |
| 1366x768 (WXGA)    | 22        | 15.17%  |
| 3840x2160 (4K)     | 17        | 11.72%  |
| 2560x1440 (QHD)    | 6         | 4.14%   |
| 1680x1050 (WSXGA+) | 4         | 2.76%   |
| 1440x900 (WXGA+)   | 4         | 2.76%   |
| 3440x1440          | 3         | 2.07%   |
| 2560x1600          | 3         | 2.07%   |
| 1600x900 (HD+)     | 3         | 2.07%   |
| 1280x800 (WXGA)    | 3         | 2.07%   |
| 1280x1024 (SXGA)   | 3         | 2.07%   |
| 3200x1800 (QHD+)   | 2         | 1.38%   |
| 1920x1200 (WUXGA)  | 2         | 1.38%   |
| 1360x768           | 2         | 1.38%   |
| 800x1280           | 1         | 0.69%   |
| 2880x1800          | 1         | 0.69%   |
| 2560x1080          | 1         | 0.69%   |
| 2160x1440          | 1         | 0.69%   |
| 1920x1280          | 1         | 0.69%   |
| 1720x1440          | 1         | 0.69%   |
| 1680x945           | 1         | 0.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 38        | 24.84%  |
| 13      | 13        | 8.5%    |
| 31      | 12        | 7.84%   |
| 27      | 11        | 7.19%   |
| 14      | 10        | 6.54%   |
| 17      | 9         | 5.88%   |
| 24      | 8         | 5.23%   |
| 21      | 7         | 4.58%   |
| 23      | 5         | 3.27%   |
| 12      | 5         | 3.27%   |
| 22      | 4         | 2.61%   |
| 19      | 4         | 2.61%   |
| Unknown | 4         | 2.61%   |
| 84      | 3         | 1.96%   |
| 34      | 3         | 1.96%   |
| 16      | 3         | 1.96%   |
| 54      | 2         | 1.31%   |
| 49      | 2         | 1.31%   |
| 48      | 2         | 1.31%   |
| 74      | 1         | 0.65%   |
| 72      | 1         | 0.65%   |
| 65      | 1         | 0.65%   |
| 63      | 1         | 0.65%   |
| 52      | 1         | 0.65%   |
| 40      | 1         | 0.65%   |
| 20      | 1         | 0.65%   |
| 18      | 1         | 0.65%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 56        | 36.84%  |
| 501-600     | 23        | 15.13%  |
| 401-500     | 14        | 9.21%   |
| 201-300     | 14        | 9.21%   |
| 601-700     | 13        | 8.55%   |
| 351-400     | 10        | 6.58%   |
| 1001-1500   | 9         | 5.92%   |
| 1501-2000   | 5         | 3.29%   |
| Unknown     | 4         | 2.63%   |
| 701-800     | 3         | 1.97%   |
| 801-900     | 1         | 0.66%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 111       | 79.86%  |
| 16/10 | 19        | 13.67%  |
| 5/4   | 3         | 2.16%   |
| 21/9  | 3         | 2.16%   |
| 6/5   | 1         | 0.72%   |
| 3/2   | 1         | 0.72%   |
| 0.62  | 1         | 0.72%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 38        | 25.5%   |
| 81-90          | 17        | 11.41%  |
| 201-250        | 17        | 11.41%  |
| 351-500        | 15        | 10.07%  |
| More than 1000 | 14        | 9.4%    |
| 301-350        | 11        | 7.38%   |
| 121-130        | 7         | 4.7%    |
| 71-80          | 6         | 4.03%   |
| 151-200        | 6         | 4.03%   |
| 61-70          | 5         | 3.36%   |
| Unknown        | 4         | 2.68%   |
| 141-150        | 3         | 2.01%   |
| 111-120        | 3         | 2.01%   |
| 251-300        | 2         | 1.34%   |
| 501-1000       | 1         | 0.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 42        | 28.38%  |
| 51-100        | 39        | 26.35%  |
| 121-160       | 36        | 24.32%  |
| 1-50          | 10        | 6.76%   |
| 161-240       | 10        | 6.76%   |
| More than 240 | 7         | 4.73%   |
| Unknown       | 4         | 2.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 117       | 82.98%  |
| 2     | 14        | 9.93%   |
| 3     | 5         | 3.55%   |
| 0     | 5         | 3.55%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 74        | 33.04%  |
| Realtek Semiconductor           | 72        | 32.14%  |
| Broadcom                        | 21        | 9.38%   |
| Qualcomm Atheros                | 16        | 7.14%   |
| MediaTek                        | 5         | 2.23%   |
| Broadcom Limited                | 5         | 2.23%   |
| TP-Link                         | 4         | 1.79%   |
| Samsung Electronics             | 3         | 1.34%   |
| Ralink Technology               | 3         | 1.34%   |
| Qualcomm Atheros Communications | 2         | 0.89%   |
| Marvell Technology Group        | 2         | 0.89%   |
| Huawei Technologies             | 2         | 0.89%   |
| Google                          | 2         | 0.89%   |
| VIA Technologies                | 1         | 0.45%   |
| Shenzhen Goodix Technology      | 1         | 0.45%   |
| Ralink                          | 1         | 0.45%   |
| Nvidia                          | 1         | 0.45%   |
| Microsoft                       | 1         | 0.45%   |
| JMicron Technology              | 1         | 0.45%   |
| Hewlett-Packard                 | 1         | 0.45%   |
| Fibocom                         | 1         | 0.45%   |
| Edimax Technology               | 1         | 0.45%   |
| DisplayLink                     | 1         | 0.45%   |
| AVM                             | 1         | 0.45%   |
| ASUSTek Computer                | 1         | 0.45%   |
| Apple                           | 1         | 0.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 46        | 17.9%   |
| Realtek RTL8125 2.5GbE Controller                                      | 10        | 3.89%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 8         | 3.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7         | 2.72%   |
| Intel Wi-Fi 6 AX201                                                    | 6         | 2.33%   |
| Intel Wireless 8265 / 8275                                             | 5         | 1.95%   |
| Intel Wi-Fi 6 AX200                                                    | 5         | 1.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 4         | 1.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 4         | 1.56%   |
| Intel Wireless 7260                                                    | 4         | 1.56%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 4         | 1.56%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 4         | 1.56%   |
| Broadcom BCM43228 802.11a/b/g/n                                        | 4         | 1.56%   |
| Broadcom BCM43142 802.11b/g/n                                          | 4         | 1.56%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 1.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 3         | 1.17%   |
| Intel Wireless 7265                                                    | 3         | 1.17%   |
| Intel I211 Gigabit Network Connection                                  | 3         | 1.17%   |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 1.17%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 1.17%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 3         | 1.17%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 3         | 1.17%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 3         | 1.17%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 2         | 0.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2         | 0.78%   |
| Ralink MT7601U Wireless Adapter                                        | 2         | 0.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 2         | 0.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 2         | 0.78%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 2         | 0.78%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 2         | 0.78%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 2         | 0.78%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                      | 2         | 0.78%   |
| Intel Wireless 3165                                                    | 2         | 0.78%   |
| Intel Wireless 3160                                                    | 2         | 0.78%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 2         | 0.78%   |
| Intel Ethernet Controller I225-V                                       | 2         | 0.78%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 0.78%   |
| Intel Ethernet Connection (2) I219-V                                   | 2         | 0.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2         | 0.78%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 2         | 0.78%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 57        | 43.51%  |
| Realtek Semiconductor           | 18        | 13.74%  |
| Broadcom                        | 18        | 13.74%  |
| Qualcomm Atheros                | 11        | 8.4%    |
| MediaTek                        | 5         | 3.82%   |
| Broadcom Limited                | 5         | 3.82%   |
| TP-Link                         | 4         | 3.05%   |
| Ralink Technology               | 3         | 2.29%   |
| Qualcomm Atheros Communications | 2         | 1.53%   |
| Marvell Technology Group        | 2         | 1.53%   |
| Ralink                          | 1         | 0.76%   |
| Microsoft                       | 1         | 0.76%   |
| Fibocom                         | 1         | 0.76%   |
| Edimax Technology               | 1         | 0.76%   |
| AVM                             | 1         | 0.76%   |
| ASUSTek Computer                | 1         | 0.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                  | 6         | 4.58%   |
| Intel Wireless 8265 / 8275                                           | 5         | 3.82%   |
| Intel Wi-Fi 6 AX200                                                  | 5         | 3.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 4         | 3.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 4         | 3.05%   |
| Intel Wireless 7260                                                  | 4         | 3.05%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 4         | 3.05%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 4         | 3.05%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 4         | 3.05%   |
| Broadcom BCM43142 802.11b/g/n                                        | 4         | 3.05%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 3         | 2.29%   |
| Intel Wireless 7265                                                  | 3         | 2.29%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 3         | 2.29%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 3         | 2.29%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 3         | 2.29%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 2         | 1.53%   |
| Ralink MT7601U Wireless Adapter                                      | 2         | 1.53%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 2         | 1.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2         | 1.53%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 2         | 1.53%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 2         | 1.53%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 2         | 1.53%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                    | 2         | 1.53%   |
| Intel Wireless 3165                                                  | 2         | 1.53%   |
| Intel Wireless 3160                                                  | 2         | 1.53%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 2         | 1.53%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 2         | 1.53%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 2         | 1.53%   |
| Intel Centrino Advanced-N 6235                                       | 2         | 1.53%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 2         | 1.53%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                   | 2         | 1.53%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 1         | 0.76%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                | 1         | 0.76%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 1         | 0.76%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 1         | 0.76%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 1         | 0.76%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 1         | 0.76%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1         | 0.76%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.76%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                  | 1         | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 63        | 52.07%  |
| Intel                 | 32        | 26.45%  |
| Broadcom              | 7         | 5.79%   |
| Qualcomm Atheros      | 6         | 4.96%   |
| Samsung Electronics   | 3         | 2.48%   |
| Huawei Technologies   | 2         | 1.65%   |
| Google                | 2         | 1.65%   |
| VIA Technologies      | 1         | 0.83%   |
| Nvidia                | 1         | 0.83%   |
| JMicron Technology    | 1         | 0.83%   |
| Hewlett-Packard       | 1         | 0.83%   |
| DisplayLink           | 1         | 0.83%   |
| Apple                 | 1         | 0.83%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 46        | 36.8%   |
| Realtek RTL8125 2.5GbE Controller                                      | 10        | 8%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 8         | 6.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7         | 5.6%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 2.4%    |
| Intel I211 Gigabit Network Connection                                  | 3         | 2.4%    |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 2.4%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 2.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2         | 1.6%    |
| Intel Ethernet Controller I225-V                                       | 2         | 1.6%    |
| Intel Ethernet Connection I217-LM                                      | 2         | 1.6%    |
| Intel Ethernet Connection (2) I219-V                                   | 2         | 1.6%    |
| Intel 82574L Gigabit Network Connection                                | 2         | 1.6%    |
| Huawei E353/E3131                                                      | 2         | 1.6%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 2         | 1.6%    |
| VIA VT86C100A [Rhine]                                                  | 1         | 0.8%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.8%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.8%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.8%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 0.8%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.8%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.8%    |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.8%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 0.8%    |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller                    | 1         | 0.8%    |
| Intel I210 Gigabit Network Connection                                  | 1         | 0.8%    |
| Intel Ethernet Controller I226-K                                       | 1         | 0.8%    |
| Intel Ethernet Connection I219-V                                       | 1         | 0.8%    |
| Intel Ethernet Connection I217-V                                       | 1         | 0.8%    |
| Intel Ethernet Connection (7) I219-V                                   | 1         | 0.8%    |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 0.8%    |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 0.8%    |
| Intel Ethernet Connection (2) I218-V                                   | 1         | 0.8%    |
| Intel 82567LM Gigabit Network Connection                               | 1         | 0.8%    |
| Intel 82566DM-2 Gigabit Network Connection                             | 1         | 0.8%    |
| HP HP lt4120 Snapdragon X5 LTE                                         | 1         | 0.8%    |
| Google Pixel 9a                                                        | 1         | 0.8%    |
| Google Nexus/Pixel Device (tether)                                     | 1         | 0.8%    |
| DisplayLink Dell Universal Dock D6000                                  | 1         | 0.8%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 1         | 0.8%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 122       | 51.91%  |
| Ethernet | 112       | 47.66%  |
| Modem    | 1         | 0.43%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 81        | 57.04%  |
| Ethernet | 61        | 42.96%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 75        | 53.19%  |
| 1     | 58        | 41.13%  |
| 3     | 5         | 3.55%   |
| 0     | 2         | 1.42%   |
| 4     | 1         | 0.71%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 90        | 63.83%  |
| Yes  | 51        | 36.17%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 54        | 51.43%  |
| Apple                           | 10        | 9.52%   |
| Realtek Semiconductor           | 8         | 7.62%   |
| Qualcomm Atheros Communications | 7         | 6.67%   |
| IMC Networks                    | 5         | 4.76%   |
| Broadcom                        | 5         | 4.76%   |
| MediaTek                        | 2         | 1.9%    |
| Marvell Semiconductor           | 2         | 1.9%    |
| Lite-On Technology              | 2         | 1.9%    |
| Cambridge Silicon Radio         | 2         | 1.9%    |
| TP-Link                         | 1         | 0.95%   |
| SINO WEALTH                     | 1         | 0.95%   |
| Realtek                         | 1         | 0.95%   |
| Foxconn International           | 1         | 0.95%   |
| Foxconn / Hon Hai               | 1         | 0.95%   |
| Dell                            | 1         | 0.95%   |
| Alps Electric                   | 1         | 0.95%   |
| Actions                         | 1         | 0.95%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 17        | 16.19%  |
| Intel AX201 Bluetooth                               | 13        | 12.38%  |
| Realtek Bluetooth Radio                             | 6         | 5.71%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 4.76%   |
| Intel AX200 Bluetooth                               | 5         | 4.76%   |
| Apple Bluetooth Host Controller                     | 5         | 4.76%   |
| Intel Bluetooth Device                              | 4         | 3.81%   |
| Intel AX210 Bluetooth                               | 4         | 3.81%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 2.86%   |
| IMC Networks Bluetooth Radio                        | 3         | 2.86%   |
| Apple Bluetooth USB Host Controller                 | 3         | 2.86%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 1.9%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 1.9%    |
| MediaTek Wireless_Device                            | 2         | 1.9%    |
| Marvell Bluetooth and Wireless LAN Composite        | 2         | 1.9%    |
| Lite-On Bluetooth 4.0 [Broadcom BCM20702A0]         | 2         | 1.9%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 1.9%    |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.9%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.9%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 1.9%    |
| Broadcom HP Portable Bumble Bee                     | 2         | 1.9%    |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 1.9%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 1.9%    |
| TP-Link TP-T@- UB500 Adapter                        | 1         | 0.95%   |
| SINO WEALTH Bluetooth Keyboard                      | 1         | 0.95%   |
| Realtek Bluetooth Radio                             | 1         | 0.95%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.95%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.95%   |
| IMC Networks Wireless_Device                        | 1         | 0.95%   |
| IMC Networks Bluetooth Device                       | 1         | 0.95%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.95%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth         | 1         | 0.95%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1         | 0.95%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 0.95%   |
| Alps Electric UGTZ4 Bluetooth                       | 1         | 0.95%   |
| Actions general adapter                             | 1         | 0.95%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 103       | 52.28%  |
| AMD                    | 41        | 20.81%  |
| Nvidia                 | 34        | 17.26%  |
| C-Media Electronics    | 4         | 2.03%   |
| SteelSeries ApS        | 2         | 1.02%   |
| Logitech               | 2         | 1.02%   |
| Texas Instruments      | 1         | 0.51%   |
| SAVITECH               | 1         | 0.51%   |
| Razer USA              | 1         | 0.51%   |
| Medeli Electronics     | 1         | 0.51%   |
| M-Audio                | 1         | 0.51%   |
| Jieli Technology       | 1         | 0.51%   |
| Generalplus Technology | 1         | 0.51%   |
| Focusrite-Novation     | 1         | 0.51%   |
| Blue Microphones       | 1         | 0.51%   |
| Antlion Audio          | 1         | 0.51%   |
| AKAI Professional M.I. | 1         | 0.51%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 13        | 5.35%   |
| AMD Ryzen HD Audio Controller                                              | 13        | 5.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 10        | 4.12%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10        | 4.12%   |
| Intel Haswell-ULT HD Audio Controller                                      | 9         | 3.7%    |
| Intel 8 Series HD Audio Controller                                         | 9         | 3.7%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 2.88%   |
| Intel Cannon Lake PCH cAVS                                                 | 7         | 2.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7         | 2.88%   |
| AMD Starship/Matisse HD Audio Controller                                   | 7         | 2.88%   |
| AMD FCH Azalia Controller                                                  | 7         | 2.88%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 6         | 2.47%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 5         | 2.06%   |
| AMD Radeon High Definition Audio Controller                                | 5         | 2.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 1.65%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 4         | 1.65%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 1.65%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4         | 1.65%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 1.23%   |
| Nvidia TU106 High Definition Audio Controller                              | 3         | 1.23%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 1.23%   |
| Nvidia GP106 High Definition Audio Controller                              | 3         | 1.23%   |
| Nvidia GA104 High Definition Audio Controller                              | 3         | 1.23%   |
| Nvidia AD104 High Definition Audio Controller                              | 3         | 1.23%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 1.23%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.23%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 3         | 1.23%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 3         | 1.23%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 1.23%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3         | 1.23%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3         | 1.23%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.82%   |
| Nvidia TU104 HD Audio Controller                                           | 2         | 0.82%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.82%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 0.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 0.82%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 0.82%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2         | 0.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 0.82%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 50%     |
| Unknown             | 1         | 25%     |
| SK hynix            | 1         | 25%     |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                  | 1         | 25%     |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s     | 1         | 25%     |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s | 1         | 25%     |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s      | 1         | 25%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 3         | 75%     |
| LPDDR4 | 1         | 25%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2         | 50%     |
| Row Of Chips | 1         | 25%     |
| DIMM         | 1         | 25%     |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size | Computers | Percent |
|------|-----------|---------|
| 8192 | 3         | 75%     |
| 2048 | 1         | 25%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 2         | 50%     |
| 4267  | 1         | 25%     |
| 2667  | 1         | 25%     |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 33.33%  |
| Kyocera             | 1         | 33.33%  |
| Hewlett-Packard     | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Samsung C48x Series  | 1         | 33.33%  |
| Kyocera FS-C5150DN   | 1         | 33.33%  |
| HP Deskjet 2050 J510 | 1         | 33.33%  |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 14        | 15.91%  |
| Bison Electronics                      | 12        | 13.64%  |
| Apple                                  | 6         | 6.82%   |
| Sunplus Innovation Technology          | 5         | 5.68%   |
| Samsung Electronics                    | 5         | 5.68%   |
| Realtek Semiconductor                  | 5         | 5.68%   |
| Quanta                                 | 4         | 4.55%   |
| Microdia                               | 4         | 4.55%   |
| Logitech                               | 4         | 4.55%   |
| IMC Networks                           | 4         | 4.55%   |
| Syntek                                 | 3         | 3.41%   |
| Suyin                                  | 3         | 3.41%   |
| Luxvisions Innotech Limited            | 3         | 3.41%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.41%   |
| SunplusIT                              | 2         | 2.27%   |
| Silicon Motion                         | 2         | 2.27%   |
| Lite-On Technology                     | 2         | 2.27%   |
| YGTek                                  | 1         | 1.14%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 1.14%   |
| Microsoft                              | 1         | 1.14%   |
| Lenovo                                 | 1         | 1.14%   |
| Intel                                  | 1         | 1.14%   |
| Cubeternet                             | 1         | 1.14%   |
| Alcor Micro                            | 1         | 1.14%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung Galaxy series, misc. (MTP mode)              | 5         | 5.62%   |
| Chicony Integrated Camera                            | 3         | 3.37%   |
| Apple FaceTime HD Camera                             | 3         | 3.37%   |
| Syntek Integrated Camera                             | 2         | 2.25%   |
| SunplusIT 720p HD Camera                             | 2         | 2.25%   |
| Sunplus HD WebCam                                    | 2         | 2.25%   |
| Realtek Integrated_Webcam_HD                         | 2         | 2.25%   |
| Realtek Integrated Camera                            | 2         | 2.25%   |
| Microdia Integrated_Webcam_HD                        | 2         | 2.25%   |
| Logitech C920 PRO HD Webcam                          | 2         | 2.25%   |
| Chicony HP TrueVision HD                             | 2         | 2.25%   |
| Chicony HP HD Webcam                                 | 2         | 2.25%   |
| Bison SunplusIT Integrated Camera                    | 2         | 2.25%   |
| Bison HD Webcam                                      | 2         | 2.25%   |
| YGTek Webcam                                         | 1         | 1.12%   |
| Syntek Lenovo EasyCamera                             | 1         | 1.12%   |
| Suyin Integrated_Webcam_HD                           | 1         | 1.12%   |
| Suyin HP Webcam                                      | 1         | 1.12%   |
| Suyin 1.3M HD WebCam                                 | 1         | 1.12%   |
| Sunplus Integrated_Webcam_HD                         | 1         | 1.12%   |
| Sunplus Integrated_Webcam_FHD                        | 1         | 1.12%   |
| Sunplus 1.3M HD WebCam                               | 1         | 1.12%   |
| Silicon Motion WebCam SC-13HDL11939N                 | 1         | 1.12%   |
| Silicon Motion Lenovo EasyCamera                     | 1         | 1.12%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera      | 1         | 1.12%   |
| Realtek Intergrated Camera 5M                        | 1         | 1.12%   |
| Realtek Intergrated Camera 2M                        | 1         | 1.12%   |
| Quanta USB2.0 VGA UVC WebCam                         | 1         | 1.12%   |
| Quanta HP Wide Vision HD Camera                      | 1         | 1.12%   |
| Quanta HP TrueVision HD Camera                       | 1         | 1.12%   |
| Quanta HP 5MP Camera                                 | 1         | 1.12%   |
| Microsoft LifeCam HD-3000                            | 1         | 1.12%   |
| Microdia MSI Starcam Racer                           | 1         | 1.12%   |
| Microdia Integrated_Webcam_FHD                       | 1         | 1.12%   |
| Luxvisions Innotech Limited LGE Camera               | 1         | 1.12%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.12%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 1         | 1.12%   |
| Logitech QuickCam Pro 9000                           | 1         | 1.12%   |
| Logitech C505 HD Webcam                              | 1         | 1.12%   |
| Lite-On TOSHIBA Web Camera - FHD                     | 1         | 1.12%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 61.54%  |
| Synaptics                  | 3         | 23.08%  |
| Shenzhen Goodix Technology | 1         | 7.69%   |
| Elan Microelectronics      | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 30.77%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 15.38%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 15.38%  |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 7.69%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 7.69%   |
| Synaptics WBDI                                                             | 1         | 7.69%   |
| Shenzhen Goodix  Fingerprint Device                                        | 1         | 7.69%   |
| Elan ELAN:ARM-M4                                                           | 1         | 7.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 42.86%  |
| Cherry      | 2         | 28.57%  |
| Alcor Micro | 2         | 28.57%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Cherry SECURE BOARD 1.0                                                      | 2         | 28.57%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 28.57%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 28.57%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 94        | 66.2%   |
| 1     | 40        | 28.17%  |
| 2     | 5         | 3.52%   |
| 4     | 2         | 1.41%   |
| 3     | 1         | 0.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 16        | 25.4%   |
| Fingerprint reader       | 13        | 20.63%  |
| Net/wireless             | 10        | 15.87%  |
| Multimedia controller    | 7         | 11.11%  |
| Chipcard                 | 5         | 7.94%   |
| Unassigned class         | 3         | 4.76%   |
| Camera                   | 3         | 4.76%   |
| Communication controller | 2         | 3.17%   |
| Storage/raid             | 1         | 1.59%   |
| Net/ethernet             | 1         | 1.59%   |
| Modem                    | 1         | 1.59%   |
| Bluetooth                | 1         | 1.59%   |


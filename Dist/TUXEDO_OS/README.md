TUXEDO OS - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for TUXEDO OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/TUXEDO_OS/Desktop/README.md) and [notebooks](/Dist/TUXEDO_OS/Notebook/README.md).

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

Total: 161

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [57d4ccc05e](https://linux-hardware.org/?probe=57d4ccc05e) | Dec 21, 2023 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [c7acd610c0](https://linux-hardware.org/?probe=c7acd610c0) | Dec 20, 2023 |
| TUXEDO        | Polaris AMD Gen5            | Notebook    | [84a93dbb91](https://linux-hardware.org/?probe=84a93dbb91) | Dec 19, 2023 |
| ECS           | GeForce 8000 series         | Desktop     | [d436bb4acc](https://linux-hardware.org/?probe=d436bb4acc) | Dec 19, 2023 |
| MSI           | PRO H410M-B                 | Desktop     | [0729c86d23](https://linux-hardware.org/?probe=0729c86d23) | Dec 15, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [31426d7740](https://linux-hardware.org/?probe=31426d7740) | Dec 15, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [7e201ea559](https://linux-hardware.org/?probe=7e201ea559) | Dec 11, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [627ee4cb32](https://linux-hardware.org/?probe=627ee4cb32) | Dec 11, 2023 |
| Acer          | Swift SF314-52              | Notebook    | [ed93047829](https://linux-hardware.org/?probe=ed93047829) | Dec 01, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [936fe9e153](https://linux-hardware.org/?probe=936fe9e153) | Nov 28, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [4c071e2ab0](https://linux-hardware.org/?probe=4c071e2ab0) | Nov 27, 2023 |
| TUXEDO        | Stellaris Intel Gen5        | Notebook    | [16cc1f3183](https://linux-hardware.org/?probe=16cc1f3183) | Nov 26, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [c34bec8c5f](https://linux-hardware.org/?probe=c34bec8c5f) | Nov 21, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [3e6fcc9388](https://linux-hardware.org/?probe=3e6fcc9388) | Nov 19, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [629ca85bd5](https://linux-hardware.org/?probe=629ca85bd5) | Nov 18, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [1a6683483d](https://linux-hardware.org/?probe=1a6683483d) | Nov 18, 2023 |
| TUXEDO        | Polaris 15 AMD Gen1         | Notebook    | [a08b139fa8](https://linux-hardware.org/?probe=a08b139fa8) | Nov 12, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5f06f30bd3](https://linux-hardware.org/?probe=5f06f30bd3) | Nov 09, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [414894f4aa](https://linux-hardware.org/?probe=414894f4aa) | Nov 08, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3fb2d2a6f0](https://linux-hardware.org/?probe=3fb2d2a6f0) | Nov 06, 2023 |
| Lenovo        | ThinkPad P50 20EQS42M00     | Notebook    | [f4761a87e1](https://linux-hardware.org/?probe=f4761a87e1) | Nov 06, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [4a5e89566c](https://linux-hardware.org/?probe=4a5e89566c) | Nov 05, 2023 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | Notebook    | [0845a0ec43](https://linux-hardware.org/?probe=0845a0ec43) | Nov 03, 2023 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [ca743b4e40](https://linux-hardware.org/?probe=ca743b4e40) | Nov 01, 2023 |
| Dell          | Precision 5480              | Notebook    | [0d66f24fe1](https://linux-hardware.org/?probe=0d66f24fe1) | Oct 25, 2023 |
| Notebook      | NP5x_NP6x_NP7xHP            | Notebook    | [017d43654d](https://linux-hardware.org/?probe=017d43654d) | Oct 22, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [78df342ad3](https://linux-hardware.org/?probe=78df342ad3) | Oct 21, 2023 |
| TUXEDO        | XMG FUSION 15 (XFU15L19)    | Notebook    | [af44d01ae9](https://linux-hardware.org/?probe=af44d01ae9) | Oct 19, 2023 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [5573fff3e6](https://linux-hardware.org/?probe=5573fff3e6) | Oct 17, 2023 |
| Dell          | Latitude E6540              | Notebook    | [78c4b71781](https://linux-hardware.org/?probe=78c4b71781) | Oct 04, 2023 |
| Dell          | Latitude E6540              | Notebook    | [290b4bd42e](https://linux-hardware.org/?probe=290b4bd42e) | Oct 03, 2023 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [886b5140ec](https://linux-hardware.org/?probe=886b5140ec) | Oct 03, 2023 |
| Lenovo        | ThinkPad T490s 20NYS3Y60... | Notebook    | [294e5069a4](https://linux-hardware.org/?probe=294e5069a4) | Oct 01, 2023 |
| Lenovo        | ThinkPad T490s 20NYS3Y60... | Notebook    | [9452219aa3](https://linux-hardware.org/?probe=9452219aa3) | Oct 01, 2023 |
| MSI           | Prestige 15 A10SC           | Notebook    | [6e53cd8a65](https://linux-hardware.org/?probe=6e53cd8a65) | Sep 30, 2023 |
| Metabox       | Prime-X X170KM              | Notebook    | [8ab33a8bd3](https://linux-hardware.org/?probe=8ab33a8bd3) | Sep 30, 2023 |
| TUXEDO        | Stellaris Intel Gen5        | Notebook    | [6d981e4890](https://linux-hardware.org/?probe=6d981e4890) | Sep 29, 2023 |
| Dell          | Inspiron 14 5420            | Notebook    | [ade3d11822](https://linux-hardware.org/?probe=ade3d11822) | Sep 24, 2023 |
| Schenker      | VISION 15 E23 (SVS15E23)    | Notebook    | [d905d3589d](https://linux-hardware.org/?probe=d905d3589d) | Sep 24, 2023 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [147b087f20](https://linux-hardware.org/?probe=147b087f20) | Sep 23, 2023 |
| ASRock        | A520M-HVS                   | Desktop     | [0a29d5f7f6](https://linux-hardware.org/?probe=0a29d5f7f6) | Sep 22, 2023 |
| Chuwi         | MiniBook X                  | Notebook    | [50d0819b3b](https://linux-hardware.org/?probe=50d0819b3b) | Sep 20, 2023 |
| ASRock        | A520M-HVS                   | Desktop     | [2a7bf627ba](https://linux-hardware.org/?probe=2a7bf627ba) | Sep 19, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [a4f7b61af6](https://linux-hardware.org/?probe=a4f7b61af6) | Sep 18, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [804223592d](https://linux-hardware.org/?probe=804223592d) | Sep 17, 2023 |
| HP            | Pavilion dv5                | Notebook    | [2c55682860](https://linux-hardware.org/?probe=2c55682860) | Sep 15, 2023 |
| HP            | Pavilion dv5                | Notebook    | [8d25f8969b](https://linux-hardware.org/?probe=8d25f8969b) | Sep 15, 2023 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | Desktop     | [6d7c6c42f5](https://linux-hardware.org/?probe=6d7c6c42f5) | Sep 14, 2023 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | Desktop     | [fe64bd3017](https://linux-hardware.org/?probe=fe64bd3017) | Sep 13, 2023 |
| Lenovo        | ThinkPad P50 20EQS37F00     | Notebook    | [0eaf502e28](https://linux-hardware.org/?probe=0eaf502e28) | Sep 12, 2023 |
| TUXEDO        | Stellaris Intel Gen5        | Notebook    | [a28ff634a0](https://linux-hardware.org/?probe=a28ff634a0) | Sep 11, 2023 |
| TUXEDO        | Stellaris Intel Gen5        | Notebook    | [28283f9fcf](https://linux-hardware.org/?probe=28283f9fcf) | Sep 11, 2023 |
| HP            | ZBook 14u G5                | Notebook    | [9ff135c2a6](https://linux-hardware.org/?probe=9ff135c2a6) | Sep 09, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [abb6dcaeb2](https://linux-hardware.org/?probe=abb6dcaeb2) | Sep 09, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [1e6219cb6e](https://linux-hardware.org/?probe=1e6219cb6e) | Sep 09, 2023 |
| MSI           | MAG B560M MORTAR WIFI       | Desktop     | [376e22722b](https://linux-hardware.org/?probe=376e22722b) | Sep 05, 2023 |
| MSI           | MAG B560M MORTAR WIFI       | Desktop     | [388f380783](https://linux-hardware.org/?probe=388f380783) | Sep 02, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [c53e992822](https://linux-hardware.org/?probe=c53e992822) | Aug 26, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [679cf99998](https://linux-hardware.org/?probe=679cf99998) | Aug 19, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [cd3074537b](https://linux-hardware.org/?probe=cd3074537b) | Aug 15, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | Notebook    | [b6e2112ccb](https://linux-hardware.org/?probe=b6e2112ccb) | Aug 13, 2023 |
| Dell          | Precision 7750              | Notebook    | [cebb7f5165](https://linux-hardware.org/?probe=cebb7f5165) | Aug 06, 2023 |
| TUXEDO        | N7x0WU                      | Notebook    | [1c2cb06178](https://linux-hardware.org/?probe=1c2cb06178) | Aug 06, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [01846991de](https://linux-hardware.org/?probe=01846991de) | Aug 04, 2023 |
| TUXEDO        | XMG FUSION 15 (XFU15L19)    | Notebook    | [64e640ff2b](https://linux-hardware.org/?probe=64e640ff2b) | Aug 04, 2023 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [07d668ee3d](https://linux-hardware.org/?probe=07d668ee3d) | Aug 03, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [c6078d0836](https://linux-hardware.org/?probe=c6078d0836) | Aug 02, 2023 |
| Lenovo        | ThinkPad E580 20KS003SUS    | Notebook    | [9b8485b740](https://linux-hardware.org/?probe=9b8485b740) | Aug 01, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [fde0e0e94f](https://linux-hardware.org/?probe=fde0e0e94f) | Jul 29, 2023 |
| HP            | Notebook                    | Notebook    | [beef8e7fce](https://linux-hardware.org/?probe=beef8e7fce) | Jul 25, 2023 |
| HP            | Notebook                    | Notebook    | [4746f66332](https://linux-hardware.org/?probe=4746f66332) | Jul 23, 2023 |
| Lenovo        | ThinkPad 20JB002BUS         | Tablet      | [ac659620e6](https://linux-hardware.org/?probe=ac659620e6) | Jul 20, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [bcd1c01ad6](https://linux-hardware.org/?probe=bcd1c01ad6) | Jul 15, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [390008fe3c](https://linux-hardware.org/?probe=390008fe3c) | Jul 15, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [fd0926d15b](https://linux-hardware.org/?probe=fd0926d15b) | Jul 14, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [26fda3b894](https://linux-hardware.org/?probe=26fda3b894) | Jul 14, 2023 |
| Dell          | Latitude E6530              | Notebook    | [25cbd87821](https://linux-hardware.org/?probe=25cbd87821) | Jul 13, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [29a9ad60a6](https://linux-hardware.org/?probe=29a9ad60a6) | Jul 13, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [2015dd83cb](https://linux-hardware.org/?probe=2015dd83cb) | Jul 12, 2023 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [54ac55c49e](https://linux-hardware.org/?probe=54ac55c49e) | Jul 07, 2023 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [296474a1b1](https://linux-hardware.org/?probe=296474a1b1) | Jul 07, 2023 |
| TUXEDO        | Book XUX7 Gen13             | Notebook    | [e480e61359](https://linux-hardware.org/?probe=e480e61359) | Jul 06, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [3d599df965](https://linux-hardware.org/?probe=3d599df965) | Jul 02, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [b15b3b6025](https://linux-hardware.org/?probe=b15b3b6025) | Jun 30, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [ed4a581e3e](https://linux-hardware.org/?probe=ed4a581e3e) | Jun 28, 2023 |
| MSI           | GE75 Raider 10SF            | Notebook    | [c2a5aeb291](https://linux-hardware.org/?probe=c2a5aeb291) | Jun 28, 2023 |
| TUXEDO        | P64_HJ,HK1                  | Notebook    | [4c542d50e7](https://linux-hardware.org/?probe=4c542d50e7) | Jun 27, 2023 |
| BESSTAR Te... | X400                        | Notebook    | [8e98b345cf](https://linux-hardware.org/?probe=8e98b345cf) | Jun 26, 2023 |
| Acer          | Swift SFX14-51G             | Notebook    | [c8f3981a52](https://linux-hardware.org/?probe=c8f3981a52) | Jun 23, 2023 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [6fb60cf84a](https://linux-hardware.org/?probe=6fb60cf84a) | Jun 18, 2023 |
| ASRock        | H170M Pro4                  | Desktop     | [818c9bc358](https://linux-hardware.org/?probe=818c9bc358) | Jun 14, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS1... | Notebook    | [c47936b50c](https://linux-hardware.org/?probe=c47936b50c) | Jun 09, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [c16266c1c9](https://linux-hardware.org/?probe=c16266c1c9) | Jun 04, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [f75fb35204](https://linux-hardware.org/?probe=f75fb35204) | May 28, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [66c9773a5f](https://linux-hardware.org/?probe=66c9773a5f) | May 26, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [65cc5e45b0](https://linux-hardware.org/?probe=65cc5e45b0) | May 26, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [5acf485cbf](https://linux-hardware.org/?probe=5acf485cbf) | May 20, 2023 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | Desktop     | [7332acbb0e](https://linux-hardware.org/?probe=7332acbb0e) | May 15, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [6142fe7fbd](https://linux-hardware.org/?probe=6142fe7fbd) | May 14, 2023 |
| TUXEDO        | Polaris 15 AMD Gen1         | Notebook    | [81e75bd6e7](https://linux-hardware.org/?probe=81e75bd6e7) | May 11, 2023 |
| Lenovo        | IdeaPad N581 7505           | Notebook    | [5d340c1aa2](https://linux-hardware.org/?probe=5d340c1aa2) | May 04, 2023 |
| HP            | Pavilion dv6                | Notebook    | [be01072653](https://linux-hardware.org/?probe=be01072653) | May 03, 2023 |
| TUXEDO        | Stellaris/Polaris AMD Ge... | Notebook    | [756500f10b](https://linux-hardware.org/?probe=756500f10b) | May 03, 2023 |
| HP            | Pavilion dv6                | Notebook    | [87f0c054fa](https://linux-hardware.org/?probe=87f0c054fa) | May 03, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [58bb30861d](https://linux-hardware.org/?probe=58bb30861d) | Apr 29, 2023 |
| Dell          | Inspiron 16 5630            | Notebook    | [7bfe5bb892](https://linux-hardware.org/?probe=7bfe5bb892) | Apr 27, 2023 |
| Dell          | Latitude 7530               | Notebook    | [17140d3871](https://linux-hardware.org/?probe=17140d3871) | Apr 24, 2023 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [fd2ad16b59](https://linux-hardware.org/?probe=fd2ad16b59) | Apr 22, 2023 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [04a458482b](https://linux-hardware.org/?probe=04a458482b) | Apr 19, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [3b77631ed6](https://linux-hardware.org/?probe=3b77631ed6) | Apr 04, 2023 |
| Unknown       | Unknown                     | Notebook    | [22c0e4cdec](https://linux-hardware.org/?probe=22c0e4cdec) | Apr 02, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [aabb4d79b8](https://linux-hardware.org/?probe=aabb4d79b8) | Apr 01, 2023 |
| Lenovo        | ThinkPad T490 20N3SBU219    | Notebook    | [b8e8125150](https://linux-hardware.org/?probe=b8e8125150) | Mar 27, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [885b757cdc](https://linux-hardware.org/?probe=885b757cdc) | Mar 24, 2023 |
| HP            | 2B3E                        | All in one  | [c6dd260a92](https://linux-hardware.org/?probe=c6dd260a92) | Mar 22, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [5e01f2c134](https://linux-hardware.org/?probe=5e01f2c134) | Mar 22, 2023 |
| Gigabyte      | H81M-HD3                    | Desktop     | [8aaef31933](https://linux-hardware.org/?probe=8aaef31933) | Mar 19, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | Notebook    | [0db668b5ec](https://linux-hardware.org/?probe=0db668b5ec) | Mar 18, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [094b530ce7](https://linux-hardware.org/?probe=094b530ce7) | Mar 18, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [e7dd32b931](https://linux-hardware.org/?probe=e7dd32b931) | Mar 15, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [557a08d242](https://linux-hardware.org/?probe=557a08d242) | Mar 15, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [3fcbfecb5a](https://linux-hardware.org/?probe=3fcbfecb5a) | Mar 14, 2023 |
| Dell          | 051FJ8 A02                  | Desktop     | [4c5eee300d](https://linux-hardware.org/?probe=4c5eee300d) | Mar 13, 2023 |
| Dell          | Precision 7720              | Notebook    | [dbe0d4c5c4](https://linux-hardware.org/?probe=dbe0d4c5c4) | Mar 12, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [40a0328a5f](https://linux-hardware.org/?probe=40a0328a5f) | Mar 11, 2023 |
| TUXEDO        | XMG FUSION 15 (XFU15L19)    | Notebook    | [3cde6f345c](https://linux-hardware.org/?probe=3cde6f345c) | Mar 10, 2023 |
| ASUSTek       | TUF Gaming H470-PRO         | Desktop     | [769cd87ebd](https://linux-hardware.org/?probe=769cd87ebd) | Mar 07, 2023 |
| ASUSTek       | TUF Gaming H470-PRO         | Desktop     | [e1846f2a68](https://linux-hardware.org/?probe=e1846f2a68) | Mar 07, 2023 |
| MSI           | MAG B560M MORTAR WIFI       | Desktop     | [886aa04456](https://linux-hardware.org/?probe=886aa04456) | Mar 07, 2023 |
| Fujitsu       | LIFEBOOK U7412              | Notebook    | [980dd72471](https://linux-hardware.org/?probe=980dd72471) | Mar 06, 2023 |
| MSI           | MAG B560M MORTAR WIFI       | Desktop     | [9088ef4d11](https://linux-hardware.org/?probe=9088ef4d11) | Mar 06, 2023 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [7a21cf8349](https://linux-hardware.org/?probe=7a21cf8349) | Mar 05, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [20d14c7576](https://linux-hardware.org/?probe=20d14c7576) | Mar 04, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [01f7386d8c](https://linux-hardware.org/?probe=01f7386d8c) | Mar 02, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [d7bb021829](https://linux-hardware.org/?probe=d7bb021829) | Feb 27, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [1e1da6a575](https://linux-hardware.org/?probe=1e1da6a575) | Feb 24, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [497a8d66e5](https://linux-hardware.org/?probe=497a8d66e5) | Feb 22, 2023 |
| Dell          | Precision 7720              | Notebook    | [2f7837d5b6](https://linux-hardware.org/?probe=2f7837d5b6) | Feb 21, 2023 |
| ASRock        | Z270M-ITX/ac                | Desktop     | [4f507f4e5a](https://linux-hardware.org/?probe=4f507f4e5a) | Feb 20, 2023 |
| TUXEDO        | Stellaris/Polaris AMD Ge... | Notebook    | [ccd78843fc](https://linux-hardware.org/?probe=ccd78843fc) | Feb 16, 2023 |
| ASUSTek       | PRIME H410M-K               | Desktop     | [7cc71e6021](https://linux-hardware.org/?probe=7cc71e6021) | Feb 12, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [ed14b057dd](https://linux-hardware.org/?probe=ed14b057dd) | Feb 09, 2023 |
| HP            | 2B34                        | Desktop     | [3376fc38b3](https://linux-hardware.org/?probe=3376fc38b3) | Feb 05, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [4a2fcb6bd0](https://linux-hardware.org/?probe=4a2fcb6bd0) | Jan 31, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [e163d98802](https://linux-hardware.org/?probe=e163d98802) | Jan 28, 2023 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [fa53a29f7e](https://linux-hardware.org/?probe=fa53a29f7e) | Jan 01, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [aeb826326b](https://linux-hardware.org/?probe=aeb826326b) | Dec 20, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [731b31c845](https://linux-hardware.org/?probe=731b31c845) | Dec 02, 2022 |
| TUXEDO        | N13xWU                      | Notebook    | [55935f091d](https://linux-hardware.org/?probe=55935f091d) | Dec 01, 2022 |
| TUXEDO        | Unknown                     | Notebook    | [fd06ca029c](https://linux-hardware.org/?probe=fd06ca029c) | Nov 29, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | Notebook    | [5043f6c54e](https://linux-hardware.org/?probe=5043f6c54e) | Nov 20, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [5d82e9f6ac](https://linux-hardware.org/?probe=5d82e9f6ac) | Nov 19, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [9d20af2c30](https://linux-hardware.org/?probe=9d20af2c30) | Nov 19, 2022 |
| Lenovo        | ThinkPad X200 Tablet 745... | Notebook    | [d58eb8b2f0](https://linux-hardware.org/?probe=d58eb8b2f0) | Oct 30, 2022 |
| Lenovo        | ThinkPad X200 Tablet 745... | Notebook    | [032bc01698](https://linux-hardware.org/?probe=032bc01698) | Oct 30, 2022 |
| TUXEDO        | Unknown                     | Notebook    | [99555fc4eb](https://linux-hardware.org/?probe=99555fc4eb) | Oct 28, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [251892471f](https://linux-hardware.org/?probe=251892471f) | Oct 26, 2022 |
| ASUSTek       | BU201LAV                    | Notebook    | [9d1fe7cb6f](https://linux-hardware.org/?probe=9d1fe7cb6f) | Oct 19, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [36e033aa01](https://linux-hardware.org/?probe=36e033aa01) | Oct 09, 2022 |
| Notebook      | W65_W67RB                   | Notebook    | [dc57cb32d4](https://linux-hardware.org/?probe=dc57cb32d4) | Oct 07, 2022 |
| Acer          | TravelMate 8572T            | Notebook    | [6abaaf4aa6](https://linux-hardware.org/?probe=6abaaf4aa6) | Oct 03, 2022 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| TUXEDO OS 22.04 | 125       | 100%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| TUXEDO OS | 125       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 6.1.0-1009-tuxedo    | 17        | 12.78%  |
| 6.2.0-10018-tuxedo   | 14        | 10.53%  |
| 6.2.0-10022-tuxedo   | 13        | 9.77%   |
| 6.2.0-10007-tuxedo   | 11        | 8.27%   |
| 6.2.0-10005-tuxedo   | 11        | 8.27%   |
| 6.2.0-10011-tuxedo   | 9         | 6.77%   |
| 6.5.0-10010-tuxedo   | 8         | 6.02%   |
| 6.5.0-10008-tuxedo   | 7         | 5.26%   |
| 5.15.0-10058-tuxedo  | 7         | 5.26%   |
| 6.5.0-10006-tuxedo   | 6         | 4.51%   |
| 6.2.0-10010-tuxedo   | 6         | 4.51%   |
| 6.2.0-10027-tuxedo   | 5         | 3.76%   |
| 5.15.0-10048-tuxedo  | 4         | 3.01%   |
| 5.15.0-10053-tuxedo  | 3         | 2.26%   |
| 5.15.0-10052-tuxedo  | 3         | 2.26%   |
| 5.15.0-10057-tuxedo  | 2         | 1.5%    |
| 5.15.0-10056-tuxedo  | 2         | 1.5%    |
| 5.15.0-10050-tuxedo  | 2         | 1.5%    |
| 6.5.4-060504-generic | 1         | 0.75%   |
| 6.2.0-10014-tuxedo   | 1         | 0.75%   |
| 6.0.0-1010-oem       | 1         | 0.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2.0   | 70        | 52.63%  |
| 5.15.0  | 23        | 17.29%  |
| 6.5.0   | 21        | 15.79%  |
| 6.1.0   | 17        | 12.78%  |
| 6.5.4   | 1         | 0.75%   |
| 6.0.0   | 1         | 0.75%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2     | 70        | 52.63%  |
| 5.15    | 23        | 17.29%  |
| 6.5     | 22        | 16.54%  |
| 6.1     | 17        | 12.78%  |
| 6.0     | 1         | 0.75%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 125       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE5       | 124       | 99.2%   |
| X-Cinnamon | 1         | 0.8%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 121       | 96.03%  |
| Wayland | 5         | 3.97%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 99        | 77.95%  |
| SDDM    | 28        | 22.05%  |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| de_DE | 54        | 43.2%   |
| en_US | 30        | 24%     |
| en_GB | 9         | 7.2%    |
| pl_PL | 3         | 2.4%    |
| it_IT | 3         | 2.4%    |
| en_ZA | 3         | 2.4%    |
| en_AU | 3         | 2.4%    |
| en_AG | 3         | 2.4%    |
| pt_PT | 2         | 1.6%    |
| nb_NO | 2         | 1.6%    |
| hu_HU | 2         | 1.6%    |
| fr_FR | 2         | 1.6%    |
| pt_BR | 1         | 0.8%    |
| nl_BE | 1         | 0.8%    |
| et_EE | 1         | 0.8%    |
| es_ES | 1         | 0.8%    |
| en_IN | 1         | 0.8%    |
| en_DK | 1         | 0.8%    |
| en_CA | 1         | 0.8%    |
| de_CH | 1         | 0.8%    |
| de_AT | 1         | 0.8%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 101       | 80.16%  |
| EFI  | 25        | 19.84%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 107       | 84.92%  |
| Btrfs   | 10        | 7.94%   |
| Tmpfs   | 4         | 3.17%   |
| Overlay | 3         | 2.38%   |
| Xfs     | 2         | 1.59%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 99        | 77.95%  |
| GPT     | 26        | 20.47%  |
| MBR     | 2         | 1.57%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 120       | 95.24%  |
| Yes       | 6         | 4.76%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 117       | 92.86%  |
| Yes       | 9         | 7.14%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| TUXEDO              | 36        | 28.8%   |
| Lenovo              | 19        | 15.2%   |
| Dell                | 13        | 10.4%   |
| ASUSTek Computer    | 13        | 10.4%   |
| Hewlett-Packard     | 12        | 9.6%    |
| MSI                 | 8         | 6.4%    |
| Apple               | 5         | 4%      |
| Acer                | 4         | 3.2%    |
| ASRock              | 3         | 2.4%    |
| Notebook            | 2         | 1.6%    |
| Gigabyte Technology | 2         | 1.6%    |
| Schenker            | 1         | 0.8%    |
| Metabox             | 1         | 0.8%    |
| Fujitsu             | 1         | 0.8%    |
| Fanless Mini PC     | 1         | 0.8%    |
| ECS                 | 1         | 0.8%    |
| Chuwi               | 1         | 0.8%    |
| BESSTAR Tech        | 1         | 0.8%    |
| Unknown             | 1         | 0.8%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| TUXEDO InfinityBook S 15/17 Gen7    | 4         | 3.2%    |
| TUXEDO Stellaris Intel Gen5         | 3         | 2.4%    |
| TUXEDO InfinityBook Pro Gen7 (MK1)  | 3         | 2.4%    |
| ASUS PRIME B450-PLUS                | 3         | 2.4%    |
| Unknown                             | 3         | 2.4%    |
| TUXEDO XMG FUSION 15 (XFU15L19)     | 2         | 1.6%    |
| TUXEDO Stellaris/Polaris AMD Gen4   | 2         | 1.6%    |
| TUXEDO Pulse 15 Gen2                | 2         | 1.6%    |
| TUXEDO Pulse 15 Gen1                | 2         | 1.6%    |
| TUXEDO Polaris 15 AMD Gen1          | 2         | 1.6%    |
| TUXEDO InfinityBook Pro Gen7 (MK2)  | 2         | 1.6%    |
| TUXEDO InfinityBook Pro 14 Gen6     | 2         | 1.6%    |
| TUXEDO Aura 15 Gen2                 | 2         | 1.6%    |
| MSI MS-7D17                         | 2         | 1.6%    |
| Dell Latitude E6540                 | 2         | 1.6%    |
| Apple MacBookPro8,1                 | 2         | 1.6%    |
| TUXEDO Stellaris AMD Gen3 (CZN)     | 1         | 0.8%    |
| TUXEDO Polaris AMD Gen5             | 1         | 0.8%    |
| TUXEDO Polaris AMD Gen3 (CZN)       | 1         | 0.8%    |
| TUXEDO P64_HJ,HK1                   | 1         | 0.8%    |
| TUXEDO N7x0WU                       | 1         | 0.8%    |
| TUXEDO N13xWU                       | 1         | 0.8%    |
| TUXEDO InfinityBook S 15 Gen6       | 1         | 0.8%    |
| TUXEDO Book XUX7 Gen13              | 1         | 0.8%    |
| Schenker VISION 15 E23 (SVS15E23)   | 1         | 0.8%    |
| Notebook W65_W67RB                  | 1         | 0.8%    |
| Notebook NP5x_NP6x_NP7xHP           | 1         | 0.8%    |
| MSI Prestige 15 A10SC               | 1         | 0.8%    |
| MSI MS-7D82                         | 1         | 0.8%    |
| MSI MS-7D25                         | 1         | 0.8%    |
| MSI MS-7C37                         | 1         | 0.8%    |
| MSI MS-7B17                         | 1         | 0.8%    |
| MSI GE75 Raider 10SF                | 1         | 0.8%    |
| Metabox Prime-X X170KM              | 1         | 0.8%    |
| Lenovo Yoga S740-15IRH 81NX         | 1         | 0.8%    |
| Lenovo Yoga 530-14IKB 81EK          | 1         | 0.8%    |
| Lenovo ThinkPad X200 Tablet 7450WN9 | 1         | 0.8%    |
| Lenovo ThinkPad T490s 20NYS3Y600    | 1         | 0.8%    |
| Lenovo ThinkPad T490 20N3SBU219     | 1         | 0.8%    |
| Lenovo ThinkPad P50 20EQS42M00      | 1         | 0.8%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| TUXEDO InfinityBook | 12        | 9.6%    |
| Lenovo ThinkPad     | 9         | 7.2%    |
| TUXEDO Stellaris    | 6         | 4.8%    |
| ASUS PRIME          | 5         | 4%      |
| TUXEDO Pulse        | 4         | 3.2%    |
| TUXEDO Polaris      | 4         | 3.2%    |
| Dell Latitude       | 4         | 3.2%    |
| HP Pavilion         | 3         | 2.4%    |
| Dell Precision      | 3         | 2.4%    |
| Dell Inspiron       | 3         | 2.4%    |
| ASUS ROG            | 3         | 2.4%    |
| Unknown             | 3         | 2.4%    |
| TUXEDO XMG          | 2         | 1.6%    |
| TUXEDO Aura         | 2         | 1.6%    |
| MSI MS-7D17         | 2         | 1.6%    |
| Lenovo Yoga         | 2         | 1.6%    |
| Lenovo Legion       | 2         | 1.6%    |
| Lenovo IdeaPad      | 2         | 1.6%    |
| HP Laptop           | 2         | 1.6%    |
| HP EliteBook        | 2         | 1.6%    |
| Apple MacBookPro8   | 2         | 1.6%    |
| Acer Swift          | 2         | 1.6%    |
| TUXEDO P64          | 1         | 0.8%    |
| TUXEDO N7x0WU       | 1         | 0.8%    |
| TUXEDO N13xWU       | 1         | 0.8%    |
| TUXEDO Book         | 1         | 0.8%    |
| Schenker VISION     | 1         | 0.8%    |
| Notebook W65        | 1         | 0.8%    |
| Notebook NP5x       | 1         | 0.8%    |
| MSI Prestige        | 1         | 0.8%    |
| MSI MS-7D82         | 1         | 0.8%    |
| MSI MS-7D25         | 1         | 0.8%    |
| MSI MS-7C37         | 1         | 0.8%    |
| MSI MS-7B17         | 1         | 0.8%    |
| MSI GE75            | 1         | 0.8%    |
| Metabox Prime-X     | 1         | 0.8%    |
| Lenovo ThinkCentre  | 1         | 0.8%    |
| Lenovo ThinkBook    | 1         | 0.8%    |
| Lenovo G580         | 1         | 0.8%    |
| Lenovo G50-80       | 1         | 0.8%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2022 | 26        | 20.8%   |
| 2020 | 17        | 13.6%   |
| 2021 | 15        | 12%     |
| 2019 | 10        | 8%      |
| 2023 | 9         | 7.2%    |
| 2015 | 9         | 7.2%    |
| 2018 | 7         | 5.6%    |
| 2017 | 6         | 4.8%    |
| 2012 | 6         | 4.8%    |
| 2013 | 5         | 4%      |
| 2011 | 4         | 3.2%    |
| 2014 | 3         | 2.4%    |
| 2008 | 3         | 2.4%    |
| 2016 | 2         | 1.6%    |
| 2010 | 1         | 0.8%    |
| 2009 | 1         | 0.8%    |
| 2007 | 1         | 0.8%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 96        | 76.8%   |
| Desktop     | 25        | 20%     |
| Convertible | 2         | 1.6%    |
| Tablet      | 1         | 0.8%    |
| Mini pc     | 1         | 0.8%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 125       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 125       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 29        | 23.2%   |
| 16.01-24.0  | 26        | 20.8%   |
| 4.01-8.0    | 20        | 16%     |
| 8.01-16.0   | 20        | 16%     |
| 64.01-256.0 | 14        | 11.2%   |
| 3.01-4.0    | 10        | 8%      |
| 24.01-32.0  | 6         | 4.8%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 42        | 31.82%  |
| 2.01-3.0   | 31        | 23.48%  |
| 1.01-2.0   | 27        | 20.45%  |
| 3.01-4.0   | 18        | 13.64%  |
| 8.01-16.0  | 11        | 8.33%   |
| 16.01-24.0 | 3         | 2.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 63        | 50%     |
| 2      | 42        | 33.33%  |
| 4      | 8         | 6.35%   |
| 3      | 8         | 6.35%   |
| 5      | 3         | 2.38%   |
| 6      | 1         | 0.79%   |
| 0      | 1         | 0.79%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 98        | 78.4%   |
| Yes       | 27        | 21.6%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 104       | 83.2%   |
| No        | 21        | 16.8%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 114       | 91.2%   |
| No        | 11        | 8.8%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 104       | 82.54%  |
| No        | 22        | 17.46%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| Germany                | 60        | 48%     |
| USA                    | 15        | 12%     |
| UK                     | 5         | 4%      |
| Switzerland            | 4         | 3.2%    |
| South Africa           | 3         | 2.4%    |
| Portugal               | 3         | 2.4%    |
| Poland                 | 3         | 2.4%    |
| France                 | 3         | 2.4%    |
| Austria                | 3         | 2.4%    |
| Australia              | 3         | 2.4%    |
| Spain                  | 2         | 1.6%    |
| Norway                 | 2         | 1.6%    |
| Netherlands            | 2         | 1.6%    |
| Italy                  | 2         | 1.6%    |
| Turkey                 | 1         | 0.8%    |
| Tunisia                | 1         | 0.8%    |
| Romania                | 1         | 0.8%    |
| India                  | 1         | 0.8%    |
| Hungary                | 1         | 0.8%    |
| Estonia                | 1         | 0.8%    |
| Egypt                  | 1         | 0.8%    |
| Denmark                | 1         | 0.8%    |
| Czechia                | 1         | 0.8%    |
| Canada                 | 1         | 0.8%    |
| Bulgaria               | 1         | 0.8%    |
| Brazil                 | 1         | 0.8%    |
| Bosnia and Herzegovina | 1         | 0.8%    |
| Belgium                | 1         | 0.8%    |
| Aruba                  | 1         | 0.8%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Munich                 | 6         | 4.76%   |
| Vienna                 | 3         | 2.38%   |
| Zurich                 | 2         | 1.59%   |
| Schweinfurt            | 2         | 1.59%   |
| Nuremberg              | 2         | 1.59%   |
| Lucerne                | 2         | 1.59%   |
| Leipzig                | 2         | 1.59%   |
| Langevag               | 2         | 1.59%   |
| Kiel                   | 2         | 1.59%   |
| Johannesburg           | 2         | 1.59%   |
| Hürth                 | 2         | 1.59%   |
| Hamburg                | 2         | 1.59%   |
| Brisbane               | 2         | 1.59%   |
| Berlin                 | 2         | 1.59%   |
| Zalău                 | 1         | 0.79%   |
| Zabrze                 | 1         | 0.79%   |
| Wembley                | 1         | 0.79%   |
| Watertown              | 1         | 0.79%   |
| Warsaw                 | 1         | 0.79%   |
| Walsall                | 1         | 0.79%   |
| Venlo                  | 1         | 0.79%   |
| Vallejo                | 1         | 0.79%   |
| Ulm                    | 1         | 0.79%   |
| Teslic                 | 1         | 0.79%   |
| Tallinn                | 1         | 0.79%   |
| Stuttgart              | 1         | 0.79%   |
| Stockstadt am Main     | 1         | 0.79%   |
| Stimpfach              | 1         | 0.79%   |
| Sousse                 | 1         | 0.79%   |
| Solymar                | 1         | 0.79%   |
| Solingen               | 1         | 0.79%   |
| Sistov                 | 1         | 0.79%   |
| Seattle                | 1         | 0.79%   |
| Schwarzenberg          | 1         | 0.79%   |
| Santa Cruz de Tenerife | 1         | 0.79%   |
| Sankt Wendel           | 1         | 0.79%   |
| San Diego              | 1         | 0.79%   |
| Rio Maior              | 1         | 0.79%   |
| Reno                   | 1         | 0.79%   |
| Rennes                 | 1         | 0.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 65        | 93     | 34.57%  |
| Seagate                     | 17        | 22     | 9.04%   |
| SanDisk                     | 17        | 21     | 9.04%   |
| Kingston                    | 10        | 10     | 5.32%   |
| WDC                         | 8         | 9      | 4.26%   |
| SK hynix                    | 6         | 7      | 3.19%   |
| Hitachi                     | 6         | 9      | 3.19%   |
| Toshiba                     | 4         | 5      | 2.13%   |
| Unknown                     | 3         | 3      | 1.6%    |
| SPCC                        | 3         | 3      | 1.6%    |
| Micron/Crucial Technology   | 3         | 5      | 1.6%    |
| Micron Technology           | 3         | 4      | 1.6%    |
| Intel                       | 3         | 3      | 1.6%    |
| Phison Electronics          | 2         | 2      | 1.06%   |
| Phison                      | 2         | 4      | 1.06%   |
| Netac                       | 2         | 2      | 1.06%   |
| Kingston Technology Company | 2         | 2      | 1.06%   |
| Intenso                     | 2         | 2      | 1.06%   |
| GOODRAM                     | 2         | 2      | 1.06%   |
| Crucial                     | 2         | 2      | 1.06%   |
| Apple                       | 2         | 2      | 1.06%   |
| USB3.0                      | 1         | 1      | 0.53%   |
| Transcend                   | 1         | 1      | 0.53%   |
| Silicon Motion              | 1         | 2      | 0.53%   |
| OWC                         | 1         | 1      | 0.53%   |
| LITEONIT                    | 1         | 1      | 0.53%   |
| Lite-On Technology          | 1         | 1      | 0.53%   |
| Lenovo                      | 1         | 1      | 0.53%   |
| KIOXIA                      | 1         | 1      | 0.53%   |
| KingFast                    | 1         | 1      | 0.53%   |
| Kingchuxing                 | 1         | 1      | 0.53%   |
| HS-SSD-E100                 | 1         | 1      | 0.53%   |
| HS-SSD-E                    | 1         | 1      | 0.53%   |
| Hikvision                   | 1         | 2      | 0.53%   |
| HGST HTS                    | 1         | 1      | 0.53%   |
| HGST                        | 1         | 1      | 0.53%   |
| CT1000BX                    | 1         | 1      | 0.53%   |
| China                       | 1         | 1      | 0.53%   |
| ASMT                        | 1         | 1      | 0.53%   |
| ASMedia                     | 1         | 2      | 0.53%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 13        | 6.28%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 11        | 5.31%   |
| Samsung SSD 980 500GB                               | 9         | 4.35%   |
| Samsung SSD 980 1TB                                 | 8         | 3.86%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB    | 5         | 2.42%   |
| Samsung SSD 970 EVO Plus 1TB                        | 3         | 1.45%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 3         | 1.45%   |
| Kingston SA400S37240G 240GB SSD                     | 3         | 1.45%   |
| Seagate ST3500418AS 500GB                           | 2         | 0.97%   |
| Seagate ST1000VT001-1RE172 1TB                      | 2         | 0.97%   |
| Seagate ST1000DM010-2EP102 1TB                      | 2         | 0.97%   |
| Sandisk WD Blue SN570 1TB                           | 2         | 0.97%   |
| Sandisk WD Black SN850 1024GB                       | 2         | 0.97%   |
| SanDisk SSD PLUS 120GB                              | 2         | 0.97%   |
| SanDisk SDSSDA240G 240GB                            | 2         | 0.97%   |
| Samsung SSD 980 PRO 500GB                           | 2         | 0.97%   |
| Samsung SSD 980 PRO 2TB                             | 2         | 0.97%   |
| Samsung SSD 980 PRO 1TB                             | 2         | 0.97%   |
| Samsung SSD 860 EVO 250GB                           | 2         | 0.97%   |
| Samsung SSD 850 EVO 500GB                           | 2         | 0.97%   |
| Samsung SSD 850 EVO 1TB                             | 2         | 0.97%   |
| Intenso SSD SATAIII 512GB                           | 2         | 0.97%   |
| Hitachi HTS727550A9E364 500GB                       | 2         | 0.97%   |
| Hitachi HCS545050GLA380 500GB                       | 2         | 0.97%   |
| WDC WD80EAZZ-00BKLB0 8TB                            | 1         | 0.48%   |
| WDC WD5000AAKX-60U6AA0 500GB                        | 1         | 0.48%   |
| WDC WD3200BPVT-24JJ5T0 320GB                        | 1         | 0.48%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 1         | 0.48%   |
| WDC WD20EZRX-00D8PB0 2TB                            | 1         | 0.48%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 0.48%   |
| WDC WD10JPVX-11JC3T0 1TB                            | 1         | 0.48%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 1         | 0.48%   |
| WDC WD Elements SE SSD 2TB                          | 1         | 0.48%   |
| USB3.0 Super Speed 500GB                            | 1         | 0.48%   |
| Unknown MMC Card  64GB                              | 1         | 0.48%   |
| Unknown MMC Card  2GB                               | 1         | 0.48%   |
| Unknown MMC Card  256GB                             | 1         | 0.48%   |
| Transcend TS512GSSD230S 512GB                       | 1         | 0.48%   |
| Toshiba XG4 NVMe SSD Controller 512GB               | 1         | 0.48%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 21     | 44.44%  |
| WDC                 | 7         | 8      | 19.44%  |
| Hitachi             | 6         | 9      | 16.67%  |
| Toshiba             | 2         | 2      | 5.56%   |
| Samsung Electronics | 2         | 2      | 5.56%   |
| USB3.0              | 1         | 1      | 2.78%   |
| HGST HTS            | 1         | 1      | 2.78%   |
| HGST                | 1         | 1      | 2.78%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 17     | 28.57%  |
| Kingston            | 7         | 7      | 14.29%  |
| SanDisk             | 5         | 6      | 10.2%   |
| SPCC                | 2         | 2      | 4.08%   |
| Netac               | 2         | 2      | 4.08%   |
| Intenso             | 2         | 2      | 4.08%   |
| GOODRAM             | 2         | 2      | 4.08%   |
| Crucial             | 2         | 2      | 4.08%   |
| Apple               | 2         | 2      | 4.08%   |
| WDC                 | 1         | 1      | 2.04%   |
| Transcend           | 1         | 1      | 2.04%   |
| SK hynix            | 1         | 2      | 2.04%   |
| OWC                 | 1         | 1      | 2.04%   |
| Micron Technology   | 1         | 1      | 2.04%   |
| LITEONIT            | 1         | 1      | 2.04%   |
| CT1000BX            | 1         | 1      | 2.04%   |
| China               | 1         | 1      | 2.04%   |
| ASMT                | 1         | 1      | 2.04%   |
| Apacer              | 1         | 1      | 2.04%   |
| A-DATA Technology   | 1         | 2      | 2.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 87        | 131    | 51.18%  |
| SSD     | 41        | 55     | 24.12%  |
| HDD     | 33        | 45     | 19.41%  |
| Unknown | 5         | 6      | 2.94%   |
| MMC     | 4         | 4      | 2.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 87        | 131    | 55.41%  |
| SATA | 58        | 96     | 36.94%  |
| SAS  | 8         | 10     | 5.1%    |
| MMC  | 4         | 4      | 2.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 39        | 57     | 52%     |
| 0.51-1.0   | 28        | 34     | 37.33%  |
| 1.01-2.0   | 5         | 6      | 6.67%   |
| 4.01-10.0  | 3         | 3      | 4%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 33        | 25.98%  |
| 101-250        | 25        | 19.69%  |
| 251-500        | 23        | 18.11%  |
| 1001-2000      | 20        | 15.75%  |
| 1-20           | 7         | 5.51%   |
| 2001-3000      | 6         | 4.72%   |
| More than 3000 | 5         | 3.94%   |
| 21-50          | 3         | 2.36%   |
| 51-100         | 3         | 2.36%   |
| Unknown        | 2         | 1.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 42        | 32.31%  |
| 21-50          | 33        | 25.38%  |
| 101-250        | 16        | 12.31%  |
| 501-1000       | 11        | 8.46%   |
| 51-100         | 11        | 8.46%   |
| 251-500        | 8         | 6.15%   |
| 1001-2000      | 5         | 3.85%   |
| Unknown        | 2         | 1.54%   |
| More than 3000 | 1         | 0.77%   |
| 2001-3000      | 1         | 0.77%   |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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
| Detected | 99        | 198    | 77.34%  |
| Works    | 29        | 43     | 22.66%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 61        | 34.46%  |
| Samsung Electronics          | 54        | 30.51%  |
| AMD                          | 19        | 10.73%  |
| SanDisk                      | 12        | 6.78%   |
| SK hynix                     | 5         | 2.82%   |
| Kingston Technology Company  | 5         | 2.82%   |
| Phison Electronics           | 4         | 2.26%   |
| Micron/Crucial Technology    | 3         | 1.69%   |
| Toshiba America Info Systems | 2         | 1.13%   |
| Silicon Motion               | 2         | 1.13%   |
| Micron Technology            | 2         | 1.13%   |
| Seagate Technology           | 1         | 0.56%   |
| Nvidia                       | 1         | 0.56%   |
| Marvell Technology Group     | 1         | 0.56%   |
| Lite-On Technology           | 1         | 0.56%   |
| Lenovo                       | 1         | 0.56%   |
| KIOXIA                       | 1         | 0.56%   |
| ASMedia Technology           | 1         | 0.56%   |
| ADATA Technology             | 1         | 0.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 17        | 8.72%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 17        | 8.72%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 16        | 8.21%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 16        | 8.21%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 3.59%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 7         | 3.59%   |
| Intel Volume Management Device NVMe RAID Controller                            | 6         | 3.08%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 5         | 2.56%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 4         | 2.05%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 2.05%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 2.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 2.05%   |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 2.05%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 1.54%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.54%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 3         | 1.54%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.54%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 1.54%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 2         | 1.03%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 1.03%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 2         | 1.03%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2         | 1.03%   |
| Kingston Company NV1 NVMe SSD SM2263XT                                         | 2         | 1.03%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 1.03%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 1.03%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.03%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 1.03%   |
| AMD 500 Series Chipset SATA Controller                                         | 2         | 1.03%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 0.51%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 1         | 0.51%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 1         | 0.51%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                              | 1         | 0.51%   |
| Seagate BarraCuda Q5 NVMe SSD (DRAM-less)                                      | 1         | 0.51%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1         | 0.51%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                          | 1         | 0.51%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 1         | 0.51%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 1         | 0.51%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1         | 0.51%   |
| Phison E12 NVMe Controller                                                     | 1         | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 87        | 50.29%  |
| SATA | 71        | 41.04%  |
| RAID | 12        | 6.94%   |
| IDE  | 3         | 1.73%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 91        | 72.8%   |
| AMD    | 34        | 27.2%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 12th Gen Core i7-12700H                 | 6         | 4.8%    |
| Intel 12th Gen Core i7-1260P                  | 4         | 3.2%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 2.4%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 2.4%    |
| Intel 13th Gen Core i9-13900HX                | 3         | 2.4%    |
| Intel 11th Gen Core i7-11370H @ 3.30GHz       | 3         | 2.4%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 2.4%    |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 2         | 1.6%    |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 2         | 1.6%    |
| Intel Core i7-2620M CPU @ 2.70GHz             | 2         | 1.6%    |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 1.6%    |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 1.6%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.6%    |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2         | 1.6%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.6%    |
| Intel 12th Gen Core i7-1255U                  | 2         | 1.6%    |
| Intel 12th Gen Core i5-1240P                  | 2         | 1.6%    |
| AMD Ryzen 7 6800H with Radeon Graphics        | 2         | 1.6%    |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 1.6%    |
| AMD Ryzen 5 5600G with Radeon Graphics        | 2         | 1.6%    |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 1.6%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.6%    |
| Intel Xeon W-10855M CPU @ 2.80GHz             | 1         | 0.8%    |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 0.8%    |
| Intel Pentium CPU G3420 @ 3.20GHz             | 1         | 0.8%    |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 0.8%    |
| Intel N100                                    | 1         | 0.8%    |
| Intel Core i9-10900KF CPU @ 3.70GHz           | 1         | 0.8%    |
| Intel Core i7-8700K CPU @ 3.70GHz             | 1         | 0.8%    |
| Intel Core i7-7Y75 CPU @ 1.30GHz              | 1         | 0.8%    |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 0.8%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.8%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 0.8%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 0.8%    |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 0.8%    |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 0.8%    |
| Intel Core i7-4650U CPU @ 1.70GHz             | 1         | 0.8%    |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 0.8%    |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 0.8%    |
| Intel Core i7-10850H CPU @ 2.70GHz            | 1         | 0.8%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| Other            | 32        | 25.6%   |
| Intel Core i7    | 26        | 20.8%   |
| Intel Core i5    | 21        | 16.8%   |
| AMD Ryzen 7      | 15        | 12%     |
| AMD Ryzen 5      | 10        | 8%      |
| Intel Core i3    | 4         | 3.2%    |
| Intel Xeon       | 2         | 1.6%    |
| Intel Pentium    | 2         | 1.6%    |
| Intel Celeron    | 2         | 1.6%    |
| AMD Ryzen 9      | 2         | 1.6%    |
| AMD Ryzen 3      | 2         | 1.6%    |
| Intel Core i9    | 1         | 0.8%    |
| Intel Core 2 Duo | 1         | 0.8%    |
| AMD Turion II    | 1         | 0.8%    |
| AMD Ryzen 7 PRO  | 1         | 0.8%    |
| AMD Ryzen 5 PRO  | 1         | 0.8%    |
| AMD Phenom II X2 | 1         | 0.8%    |
| AMD A8           | 1         | 0.8%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 37        | 29.6%   |
| 6      | 23        | 18.4%   |
| 2      | 23        | 18.4%   |
| 8      | 20        | 16%     |
| 12     | 8         | 6.4%    |
| 14     | 7         | 5.6%    |
| 24     | 3         | 2.4%    |
| 10     | 3         | 2.4%    |
| 16     | 1         | 0.8%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 125       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 111       | 88.8%   |
| 1      | 14        | 11.2%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 125       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 112       | 88.19%  |
| 0x906a4    | 2         | 1.57%   |
| 0xa0653    | 1         | 0.79%   |
| 0x906ea    | 1         | 0.79%   |
| 0x906e9    | 1         | 0.79%   |
| 0x906a3    | 1         | 0.79%   |
| 0x806c1    | 1         | 0.79%   |
| 0x306d4    | 1         | 0.79%   |
| 0x0a704103 | 1         | 0.79%   |
| 0x0a704101 | 1         | 0.79%   |
| 0x0a50000d | 1         | 0.79%   |
| 0x0a50000c | 1         | 0.79%   |
| 0x08701030 | 1         | 0.79%   |
| 0x08608103 | 1         | 0.79%   |
| 0x010000c8 | 1         | 0.79%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 27        | 21.6%   |
| KabyLake         | 18        | 14.4%   |
| Zen 2            | 10        | 8%      |
| IvyBridge        | 9         | 7.2%    |
| CometLake        | 9         | 7.2%    |
| Alderlake Hybrid | 9         | 7.2%    |
| Zen 3            | 7         | 5.6%    |
| Haswell          | 7         | 5.6%    |
| Skylake          | 5         | 4%      |
| Zen+             | 4         | 3.2%    |
| TigerLake        | 4         | 3.2%    |
| SandyBridge      | 4         | 3.2%    |
| Broadwell        | 4         | 3.2%    |
| K10              | 2         | 1.6%    |
| Zen              | 1         | 0.8%    |
| Westmere         | 1         | 0.8%    |
| Puma             | 1         | 0.8%    |
| Penryn           | 1         | 0.8%    |
| Gracemont        | 1         | 0.8%    |
| Goldmont plus    | 1         | 0.8%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 81        | 48.5%   |
| Nvidia | 52        | 31.14%  |
| AMD    | 34        | 20.36%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 13        | 7.74%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 7         | 4.17%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 7         | 4.17%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 6         | 3.57%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 6         | 3.57%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 5         | 2.98%   |
| Intel UHD Graphics 620                                                      | 5         | 2.98%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 5         | 2.98%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 4         | 2.38%   |
| Intel HD Graphics 530                                                       | 4         | 2.38%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4         | 2.38%   |
| AMD Lucienne                                                                | 4         | 2.38%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3         | 1.79%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                    | 3         | 1.79%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                               | 3         | 1.79%   |
| Intel Raptor Lake-S UHD Graphics                                            | 3         | 1.79%   |
| Intel HD Graphics 630                                                       | 3         | 1.79%   |
| Intel HD Graphics 5500                                                      | 3         | 1.79%   |
| AMD Rembrandt [Radeon 680M]                                                 | 3         | 1.79%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3         | 1.79%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 2         | 1.19%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 2         | 1.19%   |
| Nvidia GF108M [GeForce GT 635M]                                             | 2         | 1.19%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 2         | 1.19%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                             | 2         | 1.19%   |
| Nvidia AD106M [GeForce RTX 4070 Max-Q / Mobile]                             | 2         | 1.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 1.19%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 1.19%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 2         | 1.19%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                      | 2         | 1.19%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 1.19%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 2         | 1.19%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                 | 2         | 1.19%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 2         | 1.19%   |
| AMD Phoenix1                                                                | 2         | 1.19%   |
| AMD Mars XTX [Radeon HD 8790M]                                              | 2         | 1.19%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                               | 1         | 0.6%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1         | 0.6%    |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1         | 0.6%    |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                     | 1         | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 49        | 38.89%  |
| Intel + Nvidia | 25        | 19.84%  |
| 1 x AMD        | 19        | 15.08%  |
| 1 x Nvidia     | 17        | 13.49%  |
| AMD + Nvidia   | 10        | 7.94%   |
| Intel + AMD    | 6         | 4.76%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 79        | 63.2%   |
| Proprietary | 45        | 36%     |
| Unknown     | 1         | 0.8%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 83        | 65.87%  |
| 5.01-6.0   | 13        | 10.32%  |
| 7.01-8.0   | 11        | 8.73%   |
| 3.01-4.0   | 8         | 6.35%   |
| 1.01-2.0   | 5         | 3.97%   |
| 8.01-16.0  | 4         | 3.17%   |
| 0.01-0.5   | 2         | 1.59%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| BOE                 | 38        | 25.33%  |
| Samsung Electronics | 18        | 12%     |
| AU Optronics        | 18        | 12%     |
| LG Display          | 8         | 5.33%   |
| Chimei Innolux      | 8         | 5.33%   |
| Acer                | 8         | 5.33%   |
| Dell                | 6         | 4%      |
| CSO                 | 6         | 4%      |
| Hewlett-Packard     | 5         | 3.33%   |
| Goldstar            | 5         | 3.33%   |
| Apple               | 5         | 3.33%   |
| BenQ                | 4         | 2.67%   |
| AOC                 | 4         | 2.67%   |
| Sharp               | 2         | 1.33%   |
| Lenovo              | 2         | 1.33%   |
| Iiyama              | 2         | 1.33%   |
| Yamaha              | 1         | 0.67%   |
| ViewSonic           | 1         | 0.67%   |
| Sony                | 1         | 0.67%   |
| SGT                 | 1         | 0.67%   |
| RTK                 | 1         | 0.67%   |
| Philips             | 1         | 0.67%   |
| PANDA               | 1         | 0.67%   |
| InfoVision          | 1         | 0.67%   |
| Fujitsu Siemens     | 1         | 0.67%   |
| Eizo                | 1         | 0.67%   |
| ASUSTek Computer    | 1         | 0.67%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                   | 5         | 3.14%   |
| BOE LCD Monitor BOE07D8 1920x1080 344x194mm 15.5-inch                   | 5         | 3.14%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                   | 4         | 2.52%   |
| BOE LCD Monitor BOE084D 1920x1080 344x193mm 15.5-inch                   | 4         | 2.52%   |
| BOE LCD Monitor BOE0AF0 2560x1600 344x215mm 16.0-inch                   | 3         | 1.89%   |
| Dell SE2419HR DELF113 1920x1080 527x296mm 23.8-inch                     | 2         | 1.26%   |
| Chimei Innolux LCD Monitor CMN15BA 1920x1080 344x194mm 15.5-inch        | 2         | 1.26%   |
| BOE LCD Monitor BOE0A3B 2560x1600 344x215mm 16.0-inch                   | 2         | 1.26%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                   | 2         | 1.26%   |
| BOE LCD Monitor BOE0747 1920x1080 345x195mm 15.6-inch                   | 2         | 1.26%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch          | 2         | 1.26%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch           | 2         | 1.26%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                  | 2         | 1.26%   |
| Acer EK240Y ACR0758 1920x1080 520x320mm 24.0-inch                       | 2         | 1.26%   |
| Yamaha RX-V473 YMH3171 1920x540                                         | 1         | 0.63%   |
| ViewSonic VX2757 VSCF931 1920x1080 598x336mm 27.0-inch                  | 1         | 0.63%   |
| Sony TV SNY4803 1920x1080 930x523mm 42.0-inch                           | 1         | 0.63%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                 | 1         | 0.63%   |
| Sharp LCD Monitor SHP143B 3840x2160 346x194mm 15.6-inch                 | 1         | 0.63%   |
| SGT HS156PC SGT9156 1920x1080 345x194mm 15.6-inch                       | 1         | 0.63%   |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch       | 1         | 0.63%   |
| Samsung Electronics SyncMaster SAM0486 1920x1080                        | 1         | 0.63%   |
| Samsung Electronics SyncMaster SAM0274 1440x900 410x257mm 19.1-inch     | 1         | 0.63%   |
| Samsung Electronics SMB1930HD SAM0708 1360x768 410x230mm 18.5-inch      | 1         | 0.63%   |
| Samsung Electronics SAMTRON STN0022 1280x1024 380x300mm 19.1-inch       | 1         | 0.63%   |
| Samsung Electronics S27C36x SAM7315 1920x1080 598x336mm 27.0-inch       | 1         | 0.63%   |
| Samsung Electronics S24R35A SAM729F 1920x1080 527x296mm 23.8-inch       | 1         | 0.63%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch       | 1         | 0.63%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch    | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch    | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 309x174mm 14.0-inch   | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch    | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC424D 2160x1440 254x169mm 12.0-inch   | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch    | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch   | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SAM0DEE 3840x2160 1872x1053mm 84.6-inch | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 480x270mm 21.7-inch   | 1         | 0.63%   |
| Samsung Electronics LC27T55 SAM701E 1920x1080 609x349mm 27.6-inch       | 1         | 0.63%   |
| Samsung Electronics C32R50x SAM7000 1920x1080 698x393mm 31.5-inch       | 1         | 0.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 68        | 47.89%  |
| 2560x1440 (QHD)    | 14        | 9.86%   |
| 1366x768 (WXGA)    | 13        | 9.15%   |
| 3840x2160 (4K)     | 8         | 5.63%   |
| 2880x1800          | 6         | 4.23%   |
| 1920x1200 (WUXGA)  | 6         | 4.23%   |
| 2560x1600          | 5         | 3.52%   |
| 1280x800 (WXGA)    | 4         | 2.82%   |
| 1600x900 (HD+)     | 3         | 2.11%   |
| 1440x900 (WXGA+)   | 3         | 2.11%   |
| 1280x1024 (SXGA)   | 2         | 1.41%   |
| 3840x1080          | 1         | 0.7%    |
| 3440x1440          | 1         | 0.7%    |
| 3200x1800 (QHD+)   | 1         | 0.7%    |
| 2560x1080          | 1         | 0.7%    |
| 2240x1400          | 1         | 0.7%    |
| 2160x1440          | 1         | 0.7%    |
| 1920x540           | 1         | 0.7%    |
| 1680x1050 (WSXGA+) | 1         | 0.7%    |
| 1360x768           | 1         | 0.7%    |
| Unknown            | 1         | 0.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 47        | 30.52%  |
| 14      | 15        | 9.74%   |
| 24      | 14        | 9.09%   |
| 27      | 13        | 8.44%   |
| 17      | 11        | 7.14%   |
| 13      | 11        | 7.14%   |
| 16      | 7         | 4.55%   |
| 12      | 5         | 3.25%   |
| 23      | 4         | 2.6%    |
| 21      | 4         | 2.6%    |
| 31      | 3         | 1.95%   |
| 20      | 3         | 1.95%   |
| Unknown | 3         | 1.95%   |
| 40      | 2         | 1.3%    |
| 22      | 2         | 1.3%    |
| 19      | 2         | 1.3%    |
| 18      | 2         | 1.3%    |
| 84      | 1         | 0.65%   |
| 60      | 1         | 0.65%   |
| 46      | 1         | 0.65%   |
| 43      | 1         | 0.65%   |
| 34      | 1         | 0.65%   |
| 33      | 1         | 0.65%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 71        | 47.65%  |
| 501-600     | 27        | 18.12%  |
| 201-300     | 13        | 8.72%   |
| 401-500     | 12        | 8.05%   |
| 351-400     | 12        | 8.05%   |
| 801-900     | 3         | 2.01%   |
| 601-700     | 3         | 2.01%   |
| Unknown     | 3         | 2.01%   |
| 1001-1500   | 2         | 1.34%   |
| 701-800     | 1         | 0.67%   |
| 1501-2000   | 1         | 0.67%   |
| 901-1000    | 1         | 0.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 100       | 75.19%  |
| 16/10   | 25        | 18.8%   |
| 5/4     | 2         | 1.5%    |
| 3/2     | 2         | 1.5%    |
| 21/9    | 2         | 1.5%    |
| 32/9    | 1         | 0.75%   |
| Unknown | 1         | 0.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 47        | 30.52%  |
| 81-90          | 23        | 14.94%  |
| 201-250        | 14        | 9.09%   |
| 301-350        | 13        | 8.44%   |
| 121-130        | 10        | 6.49%   |
| 151-200        | 8         | 5.19%   |
| 251-300        | 7         | 4.55%   |
| 111-120        | 7         | 4.55%   |
| 61-70          | 5         | 3.25%   |
| 351-500        | 5         | 3.25%   |
| 501-1000       | 4         | 2.6%    |
| 71-80          | 3         | 1.95%   |
| 141-150        | 3         | 1.95%   |
| Unknown        | 3         | 1.95%   |
| More than 1000 | 2         | 1.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 53        | 36.05%  |
| 51-100        | 33        | 22.45%  |
| 101-120       | 28        | 19.05%  |
| 161-240       | 18        | 12.24%  |
| More than 240 | 10        | 6.8%    |
| Unknown       | 3         | 2.04%   |
| 1-50          | 2         | 1.36%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 90        | 72%     |
| 2     | 28        | 22.4%   |
| 3     | 6         | 4.8%    |
| 0     | 1         | 0.8%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 88        | 42.72%  |
| Realtek Semiconductor             | 75        | 36.41%  |
| Qualcomm Atheros                  | 8         | 3.88%   |
| Broadcom                          | 6         | 2.91%   |
| Ralink Technology                 | 5         | 2.43%   |
| Broadcom Limited                  | 5         | 2.43%   |
| Huawei Technologies               | 4         | 1.94%   |
| MediaTek                          | 3         | 1.46%   |
| TP-Link                           | 2         | 0.97%   |
| DisplayLink                       | 2         | 0.97%   |
| ASIX Electronics                  | 2         | 0.97%   |
| Sierra Wireless                   | 1         | 0.49%   |
| Samsung Electronics               | 1         | 0.49%   |
| Lenovo                            | 1         | 0.49%   |
| Ericsson Business Mobile Networks | 1         | 0.49%   |
| Dell                              | 1         | 0.49%   |
| D-Link                            | 1         | 0.49%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 52        | 21.94%  |
| Intel Wi-Fi 6 AX200                                                  | 27        | 11.39%  |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 12        | 5.06%   |
| Realtek RTL8125 2.5GbE Controller                                    | 10        | 4.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 5         | 2.11%   |
| Intel Wireless 8265 / 8275                                           | 5         | 2.11%   |
| Intel Ethernet Controller I225-V                                     | 4         | 1.69%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 3         | 1.27%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 3         | 1.27%   |
| Intel Wireless 3160                                                  | 3         | 1.27%   |
| Intel Wi-Fi 6 AX201                                                  | 3         | 1.27%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 3         | 1.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 3         | 1.27%   |
| Intel 700 Series Chipset Family Wi-Fi                                | 3         | 1.27%   |
| Huawei ME936 LTE/HSDPA+ 4G modem                                     | 3         | 1.27%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                    | 3         | 1.27%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 3         | 1.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 2         | 0.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2         | 0.84%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 2         | 0.84%   |
| Realtek Killer E3000 2.5GbE Controller                               | 2         | 0.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2         | 0.84%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 2         | 0.84%   |
| Intel Wireless-AC 9260                                               | 2         | 0.84%   |
| Intel Wireless 8260                                                  | 2         | 0.84%   |
| Intel Wireless 3165                                                  | 2         | 0.84%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 2         | 0.84%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 2         | 0.84%   |
| Intel Ethernet Connection I217-LM                                    | 2         | 0.84%   |
| Intel Ethernet Connection (6) I219-LM                                | 2         | 0.84%   |
| Intel Ethernet Connection (2) I219-V                                 | 2         | 0.84%   |
| Intel Ethernet Connection (2) I219-LM                                | 2         | 0.84%   |
| Intel Centrino Advanced-N 6235                                       | 2         | 0.84%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 2         | 0.84%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 2         | 0.84%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 2         | 0.84%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 2         | 0.84%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter          | 2         | 0.84%   |
| ASIX AX88179 Gigabit Ethernet                                        | 2         | 0.84%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 1         | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 82        | 68.91%  |
| Realtek Semiconductor | 11        | 9.24%   |
| Ralink Technology     | 5         | 4.2%    |
| Qualcomm Atheros      | 5         | 4.2%    |
| Broadcom              | 5         | 4.2%    |
| Broadcom Limited      | 4         | 3.36%   |
| MediaTek              | 3         | 2.52%   |
| TP-Link               | 2         | 1.68%   |
| Sierra Wireless       | 1         | 0.84%   |
| D-Link                | 1         | 0.84%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                   | 27        | 22.69%  |
| Intel Alder Lake-P PCH CNVi WiFi                                      | 12        | 10.08%  |
| Intel Wireless 8265 / 8275                                            | 5         | 4.2%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                       | 3         | 2.52%   |
| Ralink RT2870/RT3070 Wireless Adapter                                 | 3         | 2.52%   |
| Intel Wireless 3160                                                   | 3         | 2.52%   |
| Intel Wi-Fi 6 AX201                                                   | 3         | 2.52%   |
| Intel Comet Lake PCH CNVi WiFi                                        | 3         | 2.52%   |
| Intel 700 Series Chipset Family Wi-Fi                                 | 3         | 2.52%   |
| Broadcom BCM4331 802.11a/b/g/n                                        | 3         | 2.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter              | 2         | 1.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter              | 2         | 1.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                      | 2         | 1.68%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter         | 2         | 1.68%   |
| Intel Wireless-AC 9260                                                | 2         | 1.68%   |
| Intel Wireless 8260                                                   | 2         | 1.68%   |
| Intel Wireless 3165                                                   | 2         | 1.68%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                | 2         | 1.68%   |
| Intel Raptor Lake PCH CNVi WiFi                                       | 2         | 1.68%   |
| Intel Centrino Advanced-N 6235                                        | 2         | 1.68%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                          | 2         | 1.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                              | 2         | 1.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                       | 2         | 1.68%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter  | 2         | 1.68%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter           | 2         | 1.68%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                           | 1         | 0.84%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                          | 1         | 0.84%   |
| Sierra Wireless EM7455                                                | 1         | 0.84%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                    | 1         | 0.84%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter              | 1         | 0.84%   |
| Realtek RTL8723DE Wireless Network Adapter                            | 1         | 0.84%   |
| Realtek 802.11ac NIC                                                  | 1         | 0.84%   |
| Ralink MT7601U Wireless Adapter                                       | 1         | 0.84%   |
| Ralink Airlink101 AWLL6070 802.11bgn Wireless Adapter [Ralink RT2770] | 1         | 0.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter            | 1         | 0.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)        | 1         | 0.84%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                      | 1         | 0.84%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                               | 1         | 0.84%   |
| Intel Wireless 7265                                                   | 1         | 0.84%   |
| Intel Wireless 7260                                                   | 1         | 0.84%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 71        | 64.55%  |
| Intel                 | 25        | 22.73%  |
| Broadcom              | 4         | 3.64%   |
| Qualcomm Atheros      | 3         | 2.73%   |
| DisplayLink           | 2         | 1.82%   |
| ASIX Electronics      | 2         | 1.82%   |
| Samsung Electronics   | 1         | 0.91%   |
| Lenovo                | 1         | 0.91%   |
| Broadcom Limited      | 1         | 0.91%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 52        | 46.43%  |
| Realtek RTL8125 2.5GbE Controller                                 | 10        | 8.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 4.46%   |
| Intel Ethernet Controller I225-V                                  | 4         | 3.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 2.68%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 2.68%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 1.79%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 1.79%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.79%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 1.79%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.79%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.79%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.79%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.89%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.89%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.89%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.89%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.89%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.89%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.89%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.89%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.89%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.89%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.89%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.89%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 0.89%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.89%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.89%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.89%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.89%   |
| DisplayLink UG69PD10 Docking                                      | 1         | 0.89%   |
| DisplayLink Plugable UD-3900                                      | 1         | 0.89%   |
| Broadcom NetXtreme II BCM5706 Gigabit Ethernet                    | 1         | 0.89%   |
| Broadcom Limited NetXtreme BCM57760 Gigabit Ethernet PCIe         | 1         | 0.89%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 114       | 50.89%  |
| Ethernet | 104       | 46.43%  |
| Modem    | 6         | 2.68%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 81        | 62.31%  |
| Ethernet | 49        | 37.69%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 80        | 64%     |
| 1     | 38        | 30.4%   |
| 3     | 5         | 4%      |
| 0     | 2         | 1.6%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 68        | 54.4%   |
| Yes  | 57        | 45.6%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 77        | 73.33%  |
| Realtek Semiconductor           | 7         | 6.67%   |
| Apple                           | 5         | 4.76%   |
| Foxconn / Hon Hai               | 4         | 3.81%   |
| Cambridge Silicon Radio         | 4         | 3.81%   |
| Broadcom                        | 2         | 1.9%    |
| Qualcomm Atheros Communications | 1         | 0.95%   |
| MediaTek                        | 1         | 0.95%   |
| IMC Networks                    | 1         | 0.95%   |
| Dell                            | 1         | 0.95%   |
| ASUSTek Computer                | 1         | 0.95%   |
| Unknown                         | 1         | 0.95%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                               | 26        | 24.76%  |
| Intel Bluetooth wireless interface                  | 14        | 13.33%  |
| Intel AX201 Bluetooth                               | 14        | 13.33%  |
| Intel Bluetooth Device                              | 12        | 11.43%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 3.81%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 3.81%   |
| Apple Bluetooth USB Host Controller                 | 3         | 2.86%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 1.9%    |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 1.9%    |
| Realtek 802.11ac WLAN Adapter                       | 2         | 1.9%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 1.9%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.9%    |
| Intel AX210 Bluetooth                               | 2         | 1.9%    |
| Apple Bluetooth Host Controller                     | 2         | 1.9%    |
| Realtek Bluetooth Radio                             | 1         | 0.95%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 0.95%   |
| MediaTek Wireless_Device                            | 1         | 0.95%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.95%   |
| IMC Networks Bluetooth Radio                        | 1         | 0.95%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.95%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 0.95%   |
| Foxconn / Hon Hai Bluetooth Adapter                 | 1         | 0.95%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 0.95%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 0.95%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.95%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 0.95%   |
| ASUS ASUS USB-BT500                                 | 1         | 0.95%   |
| Unknown                                             | 1         | 0.95%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 88        | 49.16%  |
| Nvidia                                 | 45        | 25.14%  |
| AMD                                    | 33        | 18.44%  |
| Razer USA                              | 2         | 1.12%   |
| Lenovo                                 | 2         | 1.12%   |
| Valve Software                         | 1         | 0.56%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.56%   |
| Logitech                               | 1         | 0.56%   |
| Kingston Technology                    | 1         | 0.56%   |
| JMTek                                  | 1         | 0.56%   |
| GN Netcom                              | 1         | 0.56%   |
| Creative Technology                    | 1         | 0.56%   |
| Creative Labs                          | 1         | 0.56%   |
| C-Media Electronics                    | 1         | 0.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 27        | 12.8%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 16        | 7.58%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 13        | 6.16%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 3.79%   |
| Nvidia TU116 High Definition Audio Controller                              | 7         | 3.32%   |
| Nvidia GA104 High Definition Audio Controller                              | 7         | 3.32%   |
| Intel Sunrise Point-LP HD Audio                                            | 7         | 3.32%   |
| Nvidia GA106 High Definition Audio Controller                              | 6         | 2.84%   |
| Nvidia TU106 High Definition Audio Controller                              | 5         | 2.37%   |
| Nvidia Audio device                                                        | 5         | 2.37%   |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 2.37%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 2.37%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 2.37%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 1.9%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 1.9%    |
| Intel Comet Lake PCH cAVS                                                  | 4         | 1.9%    |
| Intel Broadwell-U Audio Controller                                         | 4         | 1.9%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 1.9%    |
| Nvidia GP108 High Definition Audio Controller                              | 3         | 1.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 1.42%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 1.42%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 3         | 1.42%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 1.42%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 1.42%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1           | 3         | 1.42%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 1.42%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.95%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.95%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.95%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.95%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 2         | 0.95%   |
| Intel CM238 HD Audio Controller                                            | 2         | 0.95%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 0.95%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2         | 0.95%   |
| Valve Software Valve VR Radio & HMD Mic                                    | 1         | 0.47%   |
| Sony Ericsson Mobile Communications AB XQ-AU52                             | 1         | 0.47%   |
| Razer USA RC30-026902, Gaming Headset [Nari Essential, Wireless, Receiver] | 1         | 0.47%   |
| Razer USA Razer Seiren Mini                                                | 1         | 0.47%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.47%   |
| Nvidia TU102 High Definition Audio Controller                              | 1         | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 14        | 35%     |
| SK hynix            | 10        | 25%     |
| Micron Technology   | 6         | 15%     |
| Unknown             | 3         | 7.5%    |
| Unknown (ABCD)      | 1         | 2.5%    |
| Team                | 1         | 2.5%    |
| KLEVV               | 1         | 2.5%    |
| Kingston            | 1         | 2.5%    |
| Elpida              | 1         | 2.5%    |
| Crucial             | 1         | 2.5%    |
| ASint Technology    | 1         | 2.5%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s            | 4         | 9.76%   |
| Unknown                                                           | 3         | 7.32%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s            | 2         | 4.88%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s             | 2         | 4.88%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 1         | 2.44%   |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s             | 1         | 2.44%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 2.44%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 1         | 2.44%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 1         | 2.44%   |
| SK hynix RAM HMCG88AGBSA092N 32GB SODIMM DDR5 5600MT/s            | 1         | 2.44%   |
| SK hynix RAM HMCG78AGBSA092N 16GB SODIMM DDR5 5600MT/s            | 1         | 2.44%   |
| SK hynix RAM HMCG66AGBSA095N 8GB SODIMM DDR5 5600MT/s             | 1         | 2.44%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s            | 1         | 2.44%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s           | 1         | 2.44%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s            | 1         | 2.44%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s            | 1         | 2.44%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s            | 1         | 2.44%   |
| Samsung RAM Module 3GB Row Of Chips LPDDR5 6400MT/s               | 1         | 2.44%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s            | 1         | 2.44%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s            | 1         | 2.44%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s            | 1         | 2.44%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s             | 1         | 2.44%   |
| Samsung RAM M425R4GA3BB0-CQKOL 32GB SODIMM DDR5 4800MT/s          | 1         | 2.44%   |
| Micron RAM MT62F1G32D2DS-026 WT 2GB Row Of Chips LPDDR5 6400MT/s  | 1         | 2.44%   |
| Micron RAM MT52L1G32D4PG-107 8GB Chip LPDDR3 1867MT/s             | 1         | 2.44%   |
| Micron RAM Module 2GB Row Of Chips LPDDR5 6400MT/s                | 1         | 2.44%   |
| Micron RAM 8ATF2G64AZ-3G2E1 16GB DIMM DDR4 3200MT/s               | 1         | 2.44%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s              | 1         | 2.44%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s            | 1         | 2.44%   |
| KLEVV RAM KD48GU880-32A160X 8GB DIMM DDR4 2666MT/s                | 1         | 2.44%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s              | 1         | 2.44%   |
| Elpida RAM EBJ21UE8BDS0-AE-F 2048MB SODIMM DDR3 1067MT/s          | 1         | 2.44%   |
| Crucial RAM CT16G4DFRA32A.C8FE 16GB DIMM DDR4 3200MT/s            | 1         | 2.44%   |
| ASint RAM SSZ302G08-GGNHC 2GB SODIMM DDR3 1600MT/s                | 1         | 2.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 19        | 54.29%  |
| LPDDR5 | 5         | 14.29%  |
| DDR3   | 5         | 14.29%  |
| DDR5   | 4         | 11.43%  |
| LPDDR4 | 1         | 2.86%   |
| LPDDR3 | 1         | 2.86%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 25        | 71.43%  |
| Row Of Chips | 5         | 14.29%  |
| DIMM         | 4         | 11.43%  |
| Chip         | 1         | 2.86%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 13        | 34.21%  |
| 16384 | 9         | 23.68%  |
| 32768 | 7         | 18.42%  |
| 4096  | 4         | 10.53%  |
| 2048  | 4         | 10.53%  |
| 3072  | 1         | 2.63%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 12        | 32.43%  |
| 6400  | 5         | 13.51%  |
| 1600  | 4         | 10.81%  |
| 5600  | 3         | 8.11%   |
| 2667  | 3         | 8.11%   |
| 8400  | 2         | 5.41%   |
| 2400  | 2         | 5.41%   |
| 4800  | 1         | 2.7%    |
| 3733  | 1         | 2.7%    |
| 2666  | 1         | 2.7%    |
| 2133  | 1         | 2.7%    |
| 1867  | 1         | 2.7%    |
| 1067  | 1         | 2.7%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Prolific Technology | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 41        | 44.57%  |
| Bison Electronics                      | 8         | 8.7%    |
| Microdia                               | 7         | 7.61%   |
| IMC Networks                           | 4         | 4.35%   |
| Acer                                   | 4         | 4.35%   |
| Suyin                                  | 3         | 3.26%   |
| Sunplus Innovation Technology          | 3         | 3.26%   |
| Logitech                               | 3         | 3.26%   |
| Lite-On Technology                     | 3         | 3.26%   |
| Apple                                  | 3         | 3.26%   |
| Valve Software                         | 1         | 1.09%   |
| Unknown                                | 1         | 1.09%   |
| Syntek                                 | 1         | 1.09%   |
| Sony Ericsson Mobile Communications AB | 1         | 1.09%   |
| Ricoh                                  | 1         | 1.09%   |
| Realtek Semiconductor                  | 1         | 1.09%   |
| Luxvisions Innotech Limited            | 1         | 1.09%   |
| Lenovo                                 | 1         | 1.09%   |
| KYE Systems (Mouse Systems)            | 1         | 1.09%   |
| Importek                               | 1         | 1.09%   |
| HYGD-220831-A                          | 1         | 1.09%   |
| Generalplus Technology                 | 1         | 1.09%   |
| Alpha Imaging Technology               | 1         | 1.09%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony HD Webcam                                    | 12        | 13.04%  |
| Chicony FHD Webcam                                   | 9         | 9.78%   |
| Chicony USB2.0 Camera                                | 6         | 6.52%   |
| IMC Networks Integrated Camera                       | 4         | 4.35%   |
| Acer BisonCam,NB Pro                                 | 4         | 4.35%   |
| Chicony Integrated Camera                            | 3         | 3.26%   |
| Bison HD Webcam                                      | 3         | 3.26%   |
| Apple FaceTime HD Camera                             | 3         | 3.26%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 2         | 2.17%   |
| Microdia Integrated_Webcam_FHD                       | 2         | 2.17%   |
| Bison Lenovo EasyCamera                              | 2         | 2.17%   |
| Valve Software 3D Camera                             | 1         | 1.09%   |
| Unknown HD camera                                    | 1         | 1.09%   |
| Syntek Integrated Camera                             | 1         | 1.09%   |
| Suyin RGBIR Camera                                   | 1         | 1.09%   |
| Suyin Integrated_Webcam_HD                           | 1         | 1.09%   |
| Suyin HP TrueVision HD                               | 1         | 1.09%   |
| Sunplus SPCA2281 Web Camera                          | 1         | 1.09%   |
| Sunplus Integrated_Webcam_HD                         | 1         | 1.09%   |
| Sunplus Asus Webcam                                  | 1         | 1.09%   |
| Sony Ericsson Mobile AB XQ-CC54                      | 1         | 1.09%   |
| Ricoh Laptop_Integrated_Webcam_FHD                   | 1         | 1.09%   |
| Realtek Integrated Webcam                            | 1         | 1.09%   |
| Microdia Sonix USB 2.0 Camera                        | 1         | 1.09%   |
| Microdia Laptop_Integrated_Webcam_E4HD               | 1         | 1.09%   |
| Microdia Integrated_Webcam_HD                        | 1         | 1.09%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.09%   |
| Logitech HD Pro Webcam C920                          | 1         | 1.09%   |
| Logitech BRIO Ultra HD Webcam                        | 1         | 1.09%   |
| Logitech Brio 500                                    | 1         | 1.09%   |
| Lite-On Integrated Camera                            | 1         | 1.09%   |
| Lite-On HP Wide Vision HD Camera                     | 1         | 1.09%   |
| Lite-On HP Webcam                                    | 1         | 1.09%   |
| Lenovo FHD Webcam                                    | 1         | 1.09%   |
| KYE Systems (Mouse Systems) Genius Webcam            | 1         | 1.09%   |
| Importek HP Webcam                                   | 1         | 1.09%   |
| HYGD-220831-A Hy-Usb2.0-1*MIC                        | 1         | 1.09%   |
| Generalplus WEB CAM                                  | 1         | 1.09%   |
| Chicony USB2.0 HD UVC WebCam                         | 1         | 1.09%   |
| Chicony USB 2.0 Camera                               | 1         | 1.09%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Synaptics             | 11        | 55%     |
| Validity Sensors      | 7         | 35%     |
| LighTuning Technology | 2         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 15%     |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 10%     |
| Unknown                                                                    | 2         | 10%     |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 5%      |
| Validity Sensors VFS491                                                    | 1         | 5%      |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 5%      |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 5%      |
| Validity Sensors Fingerprint scanner                                       | 1         | 5%      |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 5%      |
| Synaptics WBDI                                                             | 1         | 5%      |
| Synaptics UWP WBDI                                                         | 1         | 5%      |
| Synaptics TouchPad                                                         | 1         | 5%      |
| Synaptics  WBDI                                                            | 1         | 5%      |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 5%      |
| LighTuning Fingerprint Reader                                              | 1         | 5%      |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 5%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 57.14%  |
| Alcor Micro | 3         | 42.86%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 42.86%  |
| Broadcom 58200                                                               | 2         | 28.57%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 14.29%  |
| Broadcom 5880                                                                | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 76        | 60.8%   |
| 1     | 47        | 37.6%   |
| 3     | 1         | 0.8%    |
| 2     | 1         | 0.8%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 20        | 37.74%  |
| Multimedia controller | 14        | 26.42%  |
| Chipcard              | 7         | 13.21%  |
| Graphics card         | 6         | 11.32%  |
| Net/wireless          | 3         | 5.66%   |
| Modem                 | 1         | 1.89%   |
| Card reader           | 1         | 1.89%   |
| Camera                | 1         | 1.89%   |


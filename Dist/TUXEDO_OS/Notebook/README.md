TUXEDO OS - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for TUXEDO OS.

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

Total: 130

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| TUXEDO        | Polaris AMD Gen5            | [aa5447c317](https://linux-hardware.org/?probe=aa5447c317) | Jan 01, 2024 |
| Samsung       | RC530/RC730                 | [866c256904](https://linux-hardware.org/?probe=866c256904) | Dec 30, 2023 |
| Samsung       | RC530/RC730                 | [db448e5732](https://linux-hardware.org/?probe=db448e5732) | Dec 29, 2023 |
| TUXEDO        | Polaris AMD Gen5            | [46ad5a6b29](https://linux-hardware.org/?probe=46ad5a6b29) | Dec 28, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | [54961dd296](https://linux-hardware.org/?probe=54961dd296) | Dec 25, 2023 |
| TUXEDO        | Polaris AMD Gen5            | [f63c59d851](https://linux-hardware.org/?probe=f63c59d851) | Dec 24, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [57d4ccc05e](https://linux-hardware.org/?probe=57d4ccc05e) | Dec 21, 2023 |
| TUXEDO        | Polaris AMD Gen5            | [84a93dbb91](https://linux-hardware.org/?probe=84a93dbb91) | Dec 19, 2023 |
| Apple         | MacBookAir6,2               | [31426d7740](https://linux-hardware.org/?probe=31426d7740) | Dec 15, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [627ee4cb32](https://linux-hardware.org/?probe=627ee4cb32) | Dec 11, 2023 |
| Acer          | Swift SF314-52              | [ed93047829](https://linux-hardware.org/?probe=ed93047829) | Dec 01, 2023 |
| Dell          | Inspiron 3558               | [936fe9e153](https://linux-hardware.org/?probe=936fe9e153) | Nov 28, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [4c071e2ab0](https://linux-hardware.org/?probe=4c071e2ab0) | Nov 27, 2023 |
| TUXEDO        | Stellaris Intel Gen5        | [16cc1f3183](https://linux-hardware.org/?probe=16cc1f3183) | Nov 26, 2023 |
| Acer          | Nitro AN517-55              | [c34bec8c5f](https://linux-hardware.org/?probe=c34bec8c5f) | Nov 21, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [3e6fcc9388](https://linux-hardware.org/?probe=3e6fcc9388) | Nov 19, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [629ca85bd5](https://linux-hardware.org/?probe=629ca85bd5) | Nov 18, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [1a6683483d](https://linux-hardware.org/?probe=1a6683483d) | Nov 18, 2023 |
| TUXEDO        | Polaris 15 AMD Gen1         | [a08b139fa8](https://linux-hardware.org/?probe=a08b139fa8) | Nov 12, 2023 |
| Lenovo        | ThinkPad P50 20EQS42M00     | [f4761a87e1](https://linux-hardware.org/?probe=f4761a87e1) | Nov 06, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [4a5e89566c](https://linux-hardware.org/?probe=4a5e89566c) | Nov 05, 2023 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | [0845a0ec43](https://linux-hardware.org/?probe=0845a0ec43) | Nov 03, 2023 |
| TUXEDO        | Aura 15 Gen2                | [ca743b4e40](https://linux-hardware.org/?probe=ca743b4e40) | Nov 01, 2023 |
| Dell          | Precision 5480              | [0d66f24fe1](https://linux-hardware.org/?probe=0d66f24fe1) | Oct 25, 2023 |
| Notebook      | NP5x_NP6x_NP7xHP            | [017d43654d](https://linux-hardware.org/?probe=017d43654d) | Oct 22, 2023 |
| TUXEDO        | XMG FUSION 15 (XFU15L19)    | [af44d01ae9](https://linux-hardware.org/?probe=af44d01ae9) | Oct 19, 2023 |
| Dell          | Latitude E6540              | [78c4b71781](https://linux-hardware.org/?probe=78c4b71781) | Oct 04, 2023 |
| Dell          | Latitude E6540              | [290b4bd42e](https://linux-hardware.org/?probe=290b4bd42e) | Oct 03, 2023 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [886b5140ec](https://linux-hardware.org/?probe=886b5140ec) | Oct 03, 2023 |
| Lenovo        | ThinkPad T490s 20NYS3Y60... | [294e5069a4](https://linux-hardware.org/?probe=294e5069a4) | Oct 01, 2023 |
| Lenovo        | ThinkPad T490s 20NYS3Y60... | [9452219aa3](https://linux-hardware.org/?probe=9452219aa3) | Oct 01, 2023 |
| MSI           | Prestige 15 A10SC           | [6e53cd8a65](https://linux-hardware.org/?probe=6e53cd8a65) | Sep 30, 2023 |
| Metabox       | Prime-X X170KM              | [8ab33a8bd3](https://linux-hardware.org/?probe=8ab33a8bd3) | Sep 30, 2023 |
| TUXEDO        | Stellaris Intel Gen5        | [6d981e4890](https://linux-hardware.org/?probe=6d981e4890) | Sep 29, 2023 |
| Dell          | Inspiron 14 5420            | [ade3d11822](https://linux-hardware.org/?probe=ade3d11822) | Sep 24, 2023 |
| Schenker      | VISION 15 E23 (SVS15E23)    | [d905d3589d](https://linux-hardware.org/?probe=d905d3589d) | Sep 24, 2023 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [147b087f20](https://linux-hardware.org/?probe=147b087f20) | Sep 23, 2023 |
| Chuwi         | MiniBook X                  | [50d0819b3b](https://linux-hardware.org/?probe=50d0819b3b) | Sep 20, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [a4f7b61af6](https://linux-hardware.org/?probe=a4f7b61af6) | Sep 18, 2023 |
| HP            | Laptop 15-db1xxx            | [804223592d](https://linux-hardware.org/?probe=804223592d) | Sep 17, 2023 |
| HP            | Pavilion dv5                | [2c55682860](https://linux-hardware.org/?probe=2c55682860) | Sep 15, 2023 |
| HP            | Pavilion dv5                | [8d25f8969b](https://linux-hardware.org/?probe=8d25f8969b) | Sep 15, 2023 |
| Lenovo        | ThinkPad P50 20EQS37F00     | [0eaf502e28](https://linux-hardware.org/?probe=0eaf502e28) | Sep 12, 2023 |
| TUXEDO        | Stellaris Intel Gen5        | [a28ff634a0](https://linux-hardware.org/?probe=a28ff634a0) | Sep 11, 2023 |
| TUXEDO        | Stellaris Intel Gen5        | [28283f9fcf](https://linux-hardware.org/?probe=28283f9fcf) | Sep 11, 2023 |
| HP            | ZBook 14u G5                | [9ff135c2a6](https://linux-hardware.org/?probe=9ff135c2a6) | Sep 09, 2023 |
| Apple         | MacBookPro9,2               | [abb6dcaeb2](https://linux-hardware.org/?probe=abb6dcaeb2) | Sep 09, 2023 |
| Apple         | MacBookPro9,2               | [1e6219cb6e](https://linux-hardware.org/?probe=1e6219cb6e) | Sep 09, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | [c53e992822](https://linux-hardware.org/?probe=c53e992822) | Aug 26, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | [b6e2112ccb](https://linux-hardware.org/?probe=b6e2112ccb) | Aug 13, 2023 |
| Dell          | Precision 7750              | [cebb7f5165](https://linux-hardware.org/?probe=cebb7f5165) | Aug 06, 2023 |
| TUXEDO        | N7x0WU                      | [1c2cb06178](https://linux-hardware.org/?probe=1c2cb06178) | Aug 06, 2023 |
| TUXEDO        | XMG FUSION 15 (XFU15L19)    | [64e640ff2b](https://linux-hardware.org/?probe=64e640ff2b) | Aug 04, 2023 |
| TUXEDO        | Aura 15 Gen2                | [07d668ee3d](https://linux-hardware.org/?probe=07d668ee3d) | Aug 03, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [c6078d0836](https://linux-hardware.org/?probe=c6078d0836) | Aug 02, 2023 |
| Lenovo        | ThinkPad E580 20KS003SUS    | [9b8485b740](https://linux-hardware.org/?probe=9b8485b740) | Aug 01, 2023 |
| HP            | Notebook                    | [beef8e7fce](https://linux-hardware.org/?probe=beef8e7fce) | Jul 25, 2023 |
| HP            | Notebook                    | [4746f66332](https://linux-hardware.org/?probe=4746f66332) | Jul 23, 2023 |
| Lenovo        | G580 20150                  | [bcd1c01ad6](https://linux-hardware.org/?probe=bcd1c01ad6) | Jul 15, 2023 |
| Lenovo        | G580 20150                  | [390008fe3c](https://linux-hardware.org/?probe=390008fe3c) | Jul 15, 2023 |
| HP            | Laptop 15-dw3xxx            | [fd0926d15b](https://linux-hardware.org/?probe=fd0926d15b) | Jul 14, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [26fda3b894](https://linux-hardware.org/?probe=26fda3b894) | Jul 14, 2023 |
| Dell          | Latitude E6530              | [25cbd87821](https://linux-hardware.org/?probe=25cbd87821) | Jul 13, 2023 |
| Apple         | MacBookPro8,1               | [29a9ad60a6](https://linux-hardware.org/?probe=29a9ad60a6) | Jul 13, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [2015dd83cb](https://linux-hardware.org/?probe=2015dd83cb) | Jul 12, 2023 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [54ac55c49e](https://linux-hardware.org/?probe=54ac55c49e) | Jul 07, 2023 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [296474a1b1](https://linux-hardware.org/?probe=296474a1b1) | Jul 07, 2023 |
| TUXEDO        | Book XUX7 Gen13             | [e480e61359](https://linux-hardware.org/?probe=e480e61359) | Jul 06, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [3d599df965](https://linux-hardware.org/?probe=3d599df965) | Jul 02, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [b15b3b6025](https://linux-hardware.org/?probe=b15b3b6025) | Jun 30, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [ed4a581e3e](https://linux-hardware.org/?probe=ed4a581e3e) | Jun 28, 2023 |
| MSI           | GE75 Raider 10SF            | [c2a5aeb291](https://linux-hardware.org/?probe=c2a5aeb291) | Jun 28, 2023 |
| TUXEDO        | P64_HJ,HK1                  | [4c542d50e7](https://linux-hardware.org/?probe=4c542d50e7) | Jun 27, 2023 |
| BESSTAR Te... | X400                        | [8e98b345cf](https://linux-hardware.org/?probe=8e98b345cf) | Jun 26, 2023 |
| Acer          | Swift SFX14-51G             | [c8f3981a52](https://linux-hardware.org/?probe=c8f3981a52) | Jun 23, 2023 |
| Lenovo        | Yoga S740-15IRH 81NX        | [6fb60cf84a](https://linux-hardware.org/?probe=6fb60cf84a) | Jun 18, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS1... | [c47936b50c](https://linux-hardware.org/?probe=c47936b50c) | Jun 09, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [c16266c1c9](https://linux-hardware.org/?probe=c16266c1c9) | Jun 04, 2023 |
| Apple         | MacBookAir7,2               | [f75fb35204](https://linux-hardware.org/?probe=f75fb35204) | May 28, 2023 |
| ASUSTek       | K55VJ                       | [66c9773a5f](https://linux-hardware.org/?probe=66c9773a5f) | May 26, 2023 |
| ASUSTek       | K55VJ                       | [65cc5e45b0](https://linux-hardware.org/?probe=65cc5e45b0) | May 26, 2023 |
| Lenovo        | G580 20150                  | [5acf485cbf](https://linux-hardware.org/?probe=5acf485cbf) | May 20, 2023 |
| TUXEDO        | Polaris 15 AMD Gen1         | [81e75bd6e7](https://linux-hardware.org/?probe=81e75bd6e7) | May 11, 2023 |
| Lenovo        | IdeaPad N581 7505           | [5d340c1aa2](https://linux-hardware.org/?probe=5d340c1aa2) | May 04, 2023 |
| HP            | Pavilion dv6                | [be01072653](https://linux-hardware.org/?probe=be01072653) | May 03, 2023 |
| TUXEDO        | Stellaris/Polaris AMD Ge... | [756500f10b](https://linux-hardware.org/?probe=756500f10b) | May 03, 2023 |
| HP            | Pavilion dv6                | [87f0c054fa](https://linux-hardware.org/?probe=87f0c054fa) | May 03, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [58bb30861d](https://linux-hardware.org/?probe=58bb30861d) | Apr 29, 2023 |
| Dell          | Inspiron 16 5630            | [7bfe5bb892](https://linux-hardware.org/?probe=7bfe5bb892) | Apr 27, 2023 |
| Dell          | Latitude 7530               | [17140d3871](https://linux-hardware.org/?probe=17140d3871) | Apr 24, 2023 |
| TUXEDO        | Pulse 15 Gen2               | [fd2ad16b59](https://linux-hardware.org/?probe=fd2ad16b59) | Apr 22, 2023 |
| Dell          | Vostro 3550                 | [3b77631ed6](https://linux-hardware.org/?probe=3b77631ed6) | Apr 04, 2023 |
| Unknown       | Unknown                     | [22c0e4cdec](https://linux-hardware.org/?probe=22c0e4cdec) | Apr 02, 2023 |
| Lenovo        | ThinkPad T490 20N3SBU219    | [b8e8125150](https://linux-hardware.org/?probe=b8e8125150) | Mar 27, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [885b757cdc](https://linux-hardware.org/?probe=885b757cdc) | Mar 24, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [5e01f2c134](https://linux-hardware.org/?probe=5e01f2c134) | Mar 22, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | [0db668b5ec](https://linux-hardware.org/?probe=0db668b5ec) | Mar 18, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [094b530ce7](https://linux-hardware.org/?probe=094b530ce7) | Mar 18, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [e7dd32b931](https://linux-hardware.org/?probe=e7dd32b931) | Mar 15, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [557a08d242](https://linux-hardware.org/?probe=557a08d242) | Mar 15, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [3fcbfecb5a](https://linux-hardware.org/?probe=3fcbfecb5a) | Mar 14, 2023 |
| Dell          | Precision 7720              | [dbe0d4c5c4](https://linux-hardware.org/?probe=dbe0d4c5c4) | Mar 12, 2023 |
| Dell          | Vostro 3550                 | [40a0328a5f](https://linux-hardware.org/?probe=40a0328a5f) | Mar 11, 2023 |
| TUXEDO        | XMG FUSION 15 (XFU15L19)    | [3cde6f345c](https://linux-hardware.org/?probe=3cde6f345c) | Mar 10, 2023 |
| Fujitsu       | LIFEBOOK U7412              | [980dd72471](https://linux-hardware.org/?probe=980dd72471) | Mar 06, 2023 |
| TUXEDO        | Pulse 15 Gen2               | [7a21cf8349](https://linux-hardware.org/?probe=7a21cf8349) | Mar 05, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [20d14c7576](https://linux-hardware.org/?probe=20d14c7576) | Mar 04, 2023 |
| Lenovo        | G50-80 80E5                 | [d7bb021829](https://linux-hardware.org/?probe=d7bb021829) | Feb 27, 2023 |
| Dell          | Vostro 3550                 | [1e1da6a575](https://linux-hardware.org/?probe=1e1da6a575) | Feb 24, 2023 |
| Dell          | Vostro 3550                 | [497a8d66e5](https://linux-hardware.org/?probe=497a8d66e5) | Feb 22, 2023 |
| Dell          | Precision 7720              | [2f7837d5b6](https://linux-hardware.org/?probe=2f7837d5b6) | Feb 21, 2023 |
| TUXEDO        | Stellaris/Polaris AMD Ge... | [ccd78843fc](https://linux-hardware.org/?probe=ccd78843fc) | Feb 16, 2023 |
| HP            | EliteBook 2570p             | [ed14b057dd](https://linux-hardware.org/?probe=ed14b057dd) | Feb 09, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [4a2fcb6bd0](https://linux-hardware.org/?probe=4a2fcb6bd0) | Jan 31, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [e163d98802](https://linux-hardware.org/?probe=e163d98802) | Jan 28, 2023 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [fa53a29f7e](https://linux-hardware.org/?probe=fa53a29f7e) | Jan 01, 2023 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [731b31c845](https://linux-hardware.org/?probe=731b31c845) | Dec 02, 2022 |
| TUXEDO        | N13xWU                      | [55935f091d](https://linux-hardware.org/?probe=55935f091d) | Dec 01, 2022 |
| TUXEDO        | Unknown                     | [fd06ca029c](https://linux-hardware.org/?probe=fd06ca029c) | Nov 29, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | [5043f6c54e](https://linux-hardware.org/?probe=5043f6c54e) | Nov 20, 2022 |
| HP            | EliteBook 820 G2            | [5d82e9f6ac](https://linux-hardware.org/?probe=5d82e9f6ac) | Nov 19, 2022 |
| HP            | EliteBook 820 G2            | [9d20af2c30](https://linux-hardware.org/?probe=9d20af2c30) | Nov 19, 2022 |
| Lenovo        | ThinkPad X200 Tablet 745... | [d58eb8b2f0](https://linux-hardware.org/?probe=d58eb8b2f0) | Oct 30, 2022 |
| Lenovo        | ThinkPad X200 Tablet 745... | [032bc01698](https://linux-hardware.org/?probe=032bc01698) | Oct 30, 2022 |
| TUXEDO        | Unknown                     | [99555fc4eb](https://linux-hardware.org/?probe=99555fc4eb) | Oct 28, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [251892471f](https://linux-hardware.org/?probe=251892471f) | Oct 26, 2022 |
| ASUSTek       | BU201LAV                    | [9d1fe7cb6f](https://linux-hardware.org/?probe=9d1fe7cb6f) | Oct 19, 2022 |
| Apple         | MacBookPro8,1               | [36e033aa01](https://linux-hardware.org/?probe=36e033aa01) | Oct 09, 2022 |
| Notebook      | W65_W67RB                   | [dc57cb32d4](https://linux-hardware.org/?probe=dc57cb32d4) | Oct 07, 2022 |
| Acer          | TravelMate 8572T            | [6abaaf4aa6](https://linux-hardware.org/?probe=6abaaf4aa6) | Oct 03, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| TUXEDO OS 22.04 | 99        | 100%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| TUXEDO OS | 99        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 6.1.0-1009-tuxedo    | 13        | 12.04%  |
| 6.2.0-10022-tuxedo   | 11        | 10.19%  |
| 6.2.0-10018-tuxedo   | 10        | 9.26%   |
| 6.2.0-10007-tuxedo   | 9         | 8.33%   |
| 6.2.0-10005-tuxedo   | 9         | 8.33%   |
| 6.2.0-10011-tuxedo   | 8         | 7.41%   |
| 6.5.0-10008-tuxedo   | 7         | 6.48%   |
| 6.5.0-10010-tuxedo   | 6         | 5.56%   |
| 6.2.0-10010-tuxedo   | 6         | 5.56%   |
| 6.5.0-10006-tuxedo   | 4         | 3.7%    |
| 5.15.0-10058-tuxedo  | 4         | 3.7%    |
| 5.15.0-10048-tuxedo  | 4         | 3.7%    |
| 6.2.0-10027-tuxedo   | 3         | 2.78%   |
| 5.15.0-10053-tuxedo  | 3         | 2.78%   |
| 5.15.0-10052-tuxedo  | 3         | 2.78%   |
| 5.15.0-10050-tuxedo  | 2         | 1.85%   |
| 6.5.4-060504-generic | 1         | 0.93%   |
| 6.5.0-10013-tuxedo   | 1         | 0.93%   |
| 6.2.0-10014-tuxedo   | 1         | 0.93%   |
| 6.0.0-1010-oem       | 1         | 0.93%   |
| 5.15.0-10057-tuxedo  | 1         | 0.93%   |
| 5.15.0-10056-tuxedo  | 1         | 0.93%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2.0   | 57        | 53.27%  |
| 5.15.0  | 18        | 16.82%  |
| 6.5.0   | 17        | 15.89%  |
| 6.1.0   | 13        | 12.15%  |
| 6.5.4   | 1         | 0.93%   |
| 6.0.0   | 1         | 0.93%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2     | 57        | 53.27%  |
| 6.5     | 18        | 16.82%  |
| 5.15    | 18        | 16.82%  |
| 6.1     | 13        | 12.15%  |
| 6.0     | 1         | 0.93%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 99        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| KDE5 | 99        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 98        | 98%     |
| Wayland | 2         | 2%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 76        | 75.25%  |
| SDDM    | 25        | 24.75%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| de_DE | 44        | 44.44%  |
| en_US | 25        | 25.25%  |
| en_GB | 8         | 8.08%   |
| it_IT | 3         | 3.03%   |
| en_AU | 3         | 3.03%   |
| pl_PL | 2         | 2.02%   |
| nb_NO | 2         | 2.02%   |
| hu_HU | 2         | 2.02%   |
| fr_FR | 2         | 2.02%   |
| en_AG | 2         | 2.02%   |
| pt_PT | 1         | 1.01%   |
| pt_BR | 1         | 1.01%   |
| et_EE | 1         | 1.01%   |
| es_ES | 1         | 1.01%   |
| en_ZA | 1         | 1.01%   |
| en_DK | 1         | 1.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 78        | 78%     |
| EFI  | 22        | 22%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 86        | 86.87%  |
| Btrfs   | 7         | 7.07%   |
| Tmpfs   | 4         | 4.04%   |
| Overlay | 2         | 2.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 76        | 75.25%  |
| GPT     | 23        | 22.77%  |
| MBR     | 2         | 1.98%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 96        | 96%     |
| Yes       | 4         | 4%      |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 94        | 94%     |
| Yes       | 6         | 6%      |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| TUXEDO              | 38        | 38.38%  |
| Lenovo              | 16        | 16.16%  |
| Dell                | 12        | 12.12%  |
| Hewlett-Packard     | 9         | 9.09%   |
| Apple               | 5         | 5.05%   |
| ASUSTek Computer    | 4         | 4.04%   |
| Acer                | 4         | 4.04%   |
| Notebook            | 2         | 2.02%   |
| MSI                 | 2         | 2.02%   |
| Schenker            | 1         | 1.01%   |
| Samsung Electronics | 1         | 1.01%   |
| Metabox             | 1         | 1.01%   |
| Fujitsu             | 1         | 1.01%   |
| Chuwi               | 1         | 1.01%   |
| BESSTAR Tech        | 1         | 1.01%   |
| Unknown             | 1         | 1.01%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| TUXEDO InfinityBook S 15/17 Gen7       | 4         | 4.04%   |
| TUXEDO Stellaris Intel Gen5            | 3         | 3.03%   |
| TUXEDO InfinityBook Pro Gen7 (MK1)     | 3         | 3.03%   |
| Unknown                                | 3         | 3.03%   |
| TUXEDO XMG FUSION 15 (XFU15L19)        | 2         | 2.02%   |
| TUXEDO Stellaris/Polaris AMD Gen4      | 2         | 2.02%   |
| TUXEDO Pulse 15 Gen2                   | 2         | 2.02%   |
| TUXEDO Pulse 15 Gen1                   | 2         | 2.02%   |
| TUXEDO Polaris AMD Gen5                | 2         | 2.02%   |
| TUXEDO Polaris 15 AMD Gen1             | 2         | 2.02%   |
| TUXEDO InfinityBook S 15 Gen6          | 2         | 2.02%   |
| TUXEDO InfinityBook Pro Gen7 (MK2)     | 2         | 2.02%   |
| TUXEDO InfinityBook Pro 14 Gen6        | 2         | 2.02%   |
| TUXEDO Aura 15 Gen2                    | 2         | 2.02%   |
| Dell Latitude E6540                    | 2         | 2.02%   |
| Apple MacBookPro8,1                    | 2         | 2.02%   |
| TUXEDO Stellaris AMD Gen3 (CZN)        | 1         | 1.01%   |
| TUXEDO Polaris AMD Gen3 (CZN)          | 1         | 1.01%   |
| TUXEDO P64_HJ,HK1                      | 1         | 1.01%   |
| TUXEDO N7x0WU                          | 1         | 1.01%   |
| TUXEDO N13xWU                          | 1         | 1.01%   |
| TUXEDO Book XUX7 Gen13                 | 1         | 1.01%   |
| Schenker VISION 15 E23 (SVS15E23)      | 1         | 1.01%   |
| Samsung RC530/RC730                    | 1         | 1.01%   |
| Notebook W65_W67RB                     | 1         | 1.01%   |
| Notebook NP5x_NP6x_NP7xHP              | 1         | 1.01%   |
| MSI Prestige 15 A10SC                  | 1         | 1.01%   |
| MSI GE75 Raider 10SF                   | 1         | 1.01%   |
| Metabox Prime-X X170KM                 | 1         | 1.01%   |
| Lenovo Yoga S740-15IRH 81NX            | 1         | 1.01%   |
| Lenovo ThinkPad X200 Tablet 7450WN9    | 1         | 1.01%   |
| Lenovo ThinkPad T490s 20NYS3Y600       | 1         | 1.01%   |
| Lenovo ThinkPad T490 20N3SBU219        | 1         | 1.01%   |
| Lenovo ThinkPad P50 20EQS42M00         | 1         | 1.01%   |
| Lenovo ThinkPad P50 20EQS37F00         | 1         | 1.01%   |
| Lenovo ThinkPad P14s Gen 2a 21A1S00D00 | 1         | 1.01%   |
| Lenovo ThinkPad P1 Gen 3 20TJS1W700    | 1         | 1.01%   |
| Lenovo ThinkPad E580 20KS003SUS        | 1         | 1.01%   |
| Lenovo ThinkBook 14 G2 ARE 20VF        | 1         | 1.01%   |
| Lenovo Legion 5 15IAH7H 82RB           | 1         | 1.01%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| TUXEDO InfinityBook | 13        | 13.13%  |
| Lenovo ThinkPad     | 8         | 8.08%   |
| TUXEDO Stellaris    | 6         | 6.06%   |
| TUXEDO Polaris      | 5         | 5.05%   |
| TUXEDO Pulse        | 4         | 4.04%   |
| Dell Latitude       | 4         | 4.04%   |
| Dell Precision      | 3         | 3.03%   |
| Dell Inspiron       | 3         | 3.03%   |
| Unknown             | 3         | 3.03%   |
| TUXEDO XMG          | 2         | 2.02%   |
| TUXEDO Aura         | 2         | 2.02%   |
| Lenovo Legion       | 2         | 2.02%   |
| Lenovo IdeaPad      | 2         | 2.02%   |
| HP Pavilion         | 2         | 2.02%   |
| HP Laptop           | 2         | 2.02%   |
| HP EliteBook        | 2         | 2.02%   |
| Apple MacBookPro8   | 2         | 2.02%   |
| Acer Swift          | 2         | 2.02%   |
| TUXEDO P64          | 1         | 1.01%   |
| TUXEDO N7x0WU       | 1         | 1.01%   |
| TUXEDO N13xWU       | 1         | 1.01%   |
| TUXEDO Book         | 1         | 1.01%   |
| Schenker VISION     | 1         | 1.01%   |
| Samsung RC530       | 1         | 1.01%   |
| Notebook W65        | 1         | 1.01%   |
| Notebook NP5x       | 1         | 1.01%   |
| MSI Prestige        | 1         | 1.01%   |
| MSI GE75            | 1         | 1.01%   |
| Metabox Prime-X     | 1         | 1.01%   |
| Lenovo Yoga         | 1         | 1.01%   |
| Lenovo ThinkBook    | 1         | 1.01%   |
| Lenovo G580         | 1         | 1.01%   |
| Lenovo G50-80       | 1         | 1.01%   |
| HP ZBook            | 1         | 1.01%   |
| HP OMEN             | 1         | 1.01%   |
| HP Notebook         | 1         | 1.01%   |
| Fujitsu LIFEBOOK    | 1         | 1.01%   |
| Dell Vostro         | 1         | 1.01%   |
| Dell Venue          | 1         | 1.01%   |
| Chuwi MiniBook      | 1         | 1.01%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2022 | 24        | 24.24%  |
| 2020 | 14        | 14.14%  |
| 2023 | 10        | 10.1%   |
| 2021 | 8         | 8.08%   |
| 2019 | 8         | 8.08%   |
| 2015 | 8         | 8.08%   |
| 2012 | 6         | 6.06%   |
| 2017 | 5         | 5.05%   |
| 2011 | 4         | 4.04%   |
| 2013 | 3         | 3.03%   |
| 2018 | 2         | 2.02%   |
| 2014 | 2         | 2.02%   |
| 2008 | 2         | 2.02%   |
| 2010 | 1         | 1.01%   |
| 2009 | 1         | 1.01%   |
| 2007 | 1         | 1.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 99        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 99        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 99        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 24        | 24.24%  |
| 16.01-24.0  | 19        | 19.19%  |
| 8.01-16.0   | 17        | 17.17%  |
| 4.01-8.0    | 14        | 14.14%  |
| 64.01-256.0 | 13        | 13.13%  |
| 3.01-4.0    | 6         | 6.06%   |
| 24.01-32.0  | 6         | 6.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 39        | 37.14%  |
| 2.01-3.0   | 24        | 22.86%  |
| 1.01-2.0   | 18        | 17.14%  |
| 3.01-4.0   | 13        | 12.38%  |
| 8.01-16.0  | 8         | 7.62%   |
| 16.01-24.0 | 3         | 2.86%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 58        | 58%     |
| 2      | 33        | 33%     |
| 3      | 7         | 7%      |
| 4      | 1         | 1%      |
| 0      | 1         | 1%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 82        | 82.83%  |
| Yes       | 17        | 17.17%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 82        | 82.83%  |
| No        | 17        | 17.17%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 98        | 98.99%  |
| No        | 1         | 1.01%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 89        | 89.9%   |
| No        | 10        | 10.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Notebooks | Percent |
|------------------------|-----------|---------|
| Germany                | 49        | 49.49%  |
| USA                    | 14        | 14.14%  |
| UK                     | 4         | 4.04%   |
| Switzerland            | 3         | 3.03%   |
| France                 | 3         | 3.03%   |
| Australia              | 3         | 3.03%   |
| Spain                  | 2         | 2.02%   |
| Portugal               | 2         | 2.02%   |
| Poland                 | 2         | 2.02%   |
| Norway                 | 2         | 2.02%   |
| Italy                  | 2         | 2.02%   |
| Austria                | 2         | 2.02%   |
| Turkey                 | 1         | 1.01%   |
| Tunisia                | 1         | 1.01%   |
| South Africa           | 1         | 1.01%   |
| Netherlands            | 1         | 1.01%   |
| Hungary                | 1         | 1.01%   |
| Estonia                | 1         | 1.01%   |
| Denmark                | 1         | 1.01%   |
| Czechia                | 1         | 1.01%   |
| Bulgaria               | 1         | 1.01%   |
| Brazil                 | 1         | 1.01%   |
| Bosnia and Herzegovina | 1         | 1.01%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Munich                 | 6         | 6%      |
| Vienna                 | 2         | 2%      |
| Schweinfurt            | 2         | 2%      |
| Nuremberg              | 2         | 2%      |
| Lucerne                | 2         | 2%      |
| Langevag               | 2         | 2%      |
| Kiel                   | 2         | 2%      |
| Hamburg                | 2         | 2%      |
| Duisburg               | 2         | 2%      |
| Brisbane               | 2         | 2%      |
| Berlin                 | 2         | 2%      |
| Zurich                 | 1         | 1%      |
| Zabrze                 | 1         | 1%      |
| Wembley                | 1         | 1%      |
| Watertown              | 1         | 1%      |
| Warsaw                 | 1         | 1%      |
| Walsall                | 1         | 1%      |
| Venlo                  | 1         | 1%      |
| Vallejo                | 1         | 1%      |
| Teslic                 | 1         | 1%      |
| Tallinn                | 1         | 1%      |
| Stuttgart              | 1         | 1%      |
| Stockstadt am Main     | 1         | 1%      |
| Sousse                 | 1         | 1%      |
| Solymar                | 1         | 1%      |
| Solingen               | 1         | 1%      |
| Sistov                 | 1         | 1%      |
| Seattle                | 1         | 1%      |
| Schwarzenberg          | 1         | 1%      |
| Santhià               | 1         | 1%      |
| Santa Cruz de Tenerife | 1         | 1%      |
| Sankt Wendel           | 1         | 1%      |
| San Diego              | 1         | 1%      |
| Rome                   | 1         | 1%      |
| Rio Maior              | 1         | 1%      |
| Reno                   | 1         | 1%      |
| Rennes                 | 1         | 1%      |
| Redcar                 | 1         | 1%      |
| Pruem                  | 1         | 1%      |
| Prague                 | 1         | 1%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 54        | 78     | 42.52%  |
| SanDisk                     | 11        | 13     | 8.66%   |
| Seagate                     | 9         | 9      | 7.09%   |
| Kingston                    | 7         | 7      | 5.51%   |
| Toshiba                     | 4         | 5      | 3.15%   |
| SK hynix                    | 4         | 5      | 3.15%   |
| Hitachi                     | 4         | 6      | 3.15%   |
| WDC                         | 3         | 3      | 2.36%   |
| Unknown                     | 3         | 3      | 2.36%   |
| Micron Technology           | 3         | 4      | 2.36%   |
| Intel                       | 3         | 3      | 2.36%   |
| SPCC                        | 2         | 2      | 1.57%   |
| Phison Electronics          | 2         | 2      | 1.57%   |
| Apple                       | 2         | 2      | 1.57%   |
| USB3.0                      | 1         | 1      | 0.79%   |
| Transcend                   | 1         | 1      | 0.79%   |
| Phison                      | 1         | 3      | 0.79%   |
| OWC                         | 1         | 1      | 0.79%   |
| Netac                       | 1         | 1      | 0.79%   |
| Micron/Crucial Technology   | 1         | 1      | 0.79%   |
| LITEONIT                    | 1         | 1      | 0.79%   |
| Lenovo                      | 1         | 1      | 0.79%   |
| KIOXIA                      | 1         | 1      | 0.79%   |
| Kingston Technology Company | 1         | 1      | 0.79%   |
| Kingchuxing                 | 1         | 1      | 0.79%   |
| Intenso                     | 1         | 1      | 0.79%   |
| CT1000BX                    | 1         | 1      | 0.79%   |
| Crucial                     | 1         | 1      | 0.79%   |
| ASMedia                     | 1         | 2      | 0.79%   |
| ADATA Technology            | 1         | 1      | 0.79%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 11        | 8.15%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 10        | 7.41%   |
| Samsung SSD 980 1TB                                 | 7         | 5.19%   |
| Samsung SSD 980 500GB                               | 6         | 4.44%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 2TB      | 3         | 2.22%   |
| Samsung SSD 980 PRO 1TB                             | 3         | 2.22%   |
| Samsung SSD 970 EVO Plus 1TB                        | 3         | 2.22%   |
| Kingston SA400S37240G 240GB SSD                     | 3         | 2.22%   |
| Sandisk WD Blue SN570 1TB                           | 2         | 1.48%   |
| SanDisk SDSSDA240G 240GB                            | 2         | 1.48%   |
| Samsung SSD 990 PRO 1TB                             | 2         | 1.48%   |
| Samsung SSD 980 PRO 500GB                           | 2         | 1.48%   |
| Samsung SSD 980 PRO 2TB                             | 2         | 1.48%   |
| Samsung SSD 850 EVO 1TB                             | 2         | 1.48%   |
| Hitachi HTS727550A9E364 500GB                       | 2         | 1.48%   |
| WDC WD3200BPVT-24JJ5T0 320GB                        | 1         | 0.74%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 0.74%   |
| WDC WD Elements SE SSD 2TB                          | 1         | 0.74%   |
| USB3.0 Super Speed 1TB                              | 1         | 0.74%   |
| Unknown MMC Card  64GB                              | 1         | 0.74%   |
| Unknown MMC Card  2GB                               | 1         | 0.74%   |
| Unknown MMC Card  256GB                             | 1         | 0.74%   |
| Transcend TS512GSSD230S 512GB                       | 1         | 0.74%   |
| Toshiba XG4 NVMe SSD Controller 256GB               | 1         | 0.74%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 0.74%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 0.74%   |
| Toshiba BG3 NVMe SSD Controller 256GB               | 1         | 0.74%   |
| SPCC M.2 SSD 256GB                                  | 1         | 0.74%   |
| SPCC M.2 PCIe SSD 1TB                               | 1         | 0.74%   |
| SK hynix SKHynix_HFS512GEJ4X112N 512GB              | 1         | 0.74%   |
| SK hynix SKHynix_HFS001TDE9X084N 1TB                | 1         | 0.74%   |
| SK hynix SKHynix_HFS001TDE9X081N 1024GB             | 1         | 0.74%   |
| SK hynix SC311 SATA 256GB SSD                       | 1         | 0.74%   |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 0.74%   |
| Seagate ST500LM034-2GH17A 500GB                     | 1         | 0.74%   |
| Seagate ST250LT003-9YG14C 250GB                     | 1         | 0.74%   |
| Seagate ST2000LM015-2E8174 2TB                      | 1         | 0.74%   |
| Seagate ST1000LM048-2E7172 1TB                      | 1         | 0.74%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 0.74%   |
| Seagate Expansion 2TB                               | 1         | 0.74%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 8      | 47.06%  |
| Hitachi | 4         | 6      | 23.53%  |
| WDC     | 2         | 2      | 11.76%  |
| Toshiba | 2         | 2      | 11.76%  |
| USB3.0  | 1         | 1      | 5.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 10     | 30%     |
| Kingston            | 5         | 5      | 16.67%  |
| SanDisk             | 3         | 3      | 10%     |
| Apple               | 2         | 2      | 6.67%   |
| WDC                 | 1         | 1      | 3.33%   |
| Transcend           | 1         | 1      | 3.33%   |
| SPCC                | 1         | 1      | 3.33%   |
| SK hynix            | 1         | 2      | 3.33%   |
| OWC                 | 1         | 1      | 3.33%   |
| Netac               | 1         | 1      | 3.33%   |
| Micron Technology   | 1         | 1      | 3.33%   |
| LITEONIT            | 1         | 1      | 3.33%   |
| Intenso             | 1         | 1      | 3.33%   |
| CT1000BX            | 1         | 1      | 3.33%   |
| Crucial             | 1         | 1      | 3.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 69        | 104    | 58.47%  |
| SSD     | 27        | 32     | 22.88%  |
| HDD     | 17        | 19     | 14.41%  |
| MMC     | 3         | 3      | 2.54%   |
| Unknown | 2         | 3      | 1.69%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 69        | 104    | 59.48%  |
| SATA | 38        | 47     | 32.76%  |
| SAS  | 6         | 7      | 5.17%   |
| MMC  | 3         | 3      | 2.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 26        | 31     | 57.78%  |
| 0.51-1.0   | 15        | 16     | 33.33%  |
| 1.01-2.0   | 3         | 3      | 6.67%   |
| 4.01-10.0  | 1         | 1      | 2.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 26        | 26%     |
| 101-250        | 20        | 20%     |
| 251-500        | 19        | 19%     |
| 1001-2000      | 16        | 16%     |
| 1-20           | 6         | 6%      |
| 2001-3000      | 5         | 5%      |
| More than 3000 | 3         | 3%      |
| Unknown        | 3         | 3%      |
| 21-50          | 1         | 1%      |
| 51-100         | 1         | 1%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 33        | 32.04%  |
| 21-50     | 26        | 25.24%  |
| 101-250   | 14        | 13.59%  |
| 51-100    | 9         | 8.74%   |
| 501-1000  | 8         | 7.77%   |
| 251-500   | 6         | 5.83%   |
| 1001-2000 | 4         | 3.88%   |
| Unknown   | 3         | 2.91%   |

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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 75        | 126    | 74.26%  |
| Works    | 26        | 35     | 25.74%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 47        | 35.88%  |
| Intel                        | 45        | 34.35%  |
| AMD                          | 11        | 8.4%    |
| SanDisk                      | 8         | 6.11%   |
| SK hynix                     | 3         | 2.29%   |
| Phison Electronics           | 3         | 2.29%   |
| Kingston Technology Company  | 3         | 2.29%   |
| Toshiba America Info Systems | 2         | 1.53%   |
| Micron Technology            | 2         | 1.53%   |
| Silicon Motion               | 1         | 0.76%   |
| Seagate Technology           | 1         | 0.76%   |
| Micron/Crucial Technology    | 1         | 0.76%   |
| Marvell Technology Group     | 1         | 0.76%   |
| Lenovo                       | 1         | 0.76%   |
| KIOXIA                       | 1         | 0.76%   |
| ADATA Technology             | 1         | 0.76%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 17        | 12.23%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 14        | 10.07%  |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                   | 13        | 9.35%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 10        | 7.19%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 7         | 5.04%   |
| Intel Volume Management Device NVMe RAID Controller                           | 6         | 4.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 5         | 3.6%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 4         | 2.88%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                         | 3         | 2.16%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD          | 3         | 2.16%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 3         | 2.16%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 3         | 2.16%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                          | 2         | 1.44%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 2         | 1.44%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                   | 2         | 1.44%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 2         | 1.44%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 2         | 1.44%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 2         | 1.44%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 2         | 1.44%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                          | 2         | 1.44%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                          | 1         | 0.72%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)           | 1         | 0.72%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                             | 1         | 0.72%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                 | 1         | 0.72%   |
| Seagate BarraCuda Q5 NVMe SSD (DRAM-less)                                     | 1         | 0.72%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                    | 1         | 0.72%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                         | 1         | 0.72%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                         | 1         | 0.72%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                    | 1         | 0.72%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                           | 1         | 0.72%   |
| Phison E16 PCIe4 NVMe Controller                                              | 1         | 0.72%   |
| Phison E12 NVMe Controller                                                    | 1         | 0.72%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)          | 1         | 0.72%   |
| Micron 3400 NVMe SSD [Hendrix]                                                | 1         | 0.72%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                   | 1         | 0.72%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                    | 1         | 0.72%   |
| Lenovo LENSE30256GMSP34MEAT3TA                                                | 1         | 0.72%   |
| KIOXIA NVMe SSD Controller XG8                                                | 1         | 0.72%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                 | 1         | 0.72%   |
| Kingston Company NV2 NVMe SSD SM2267XT                                        | 1         | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 69        | 53.49%  |
| SATA | 48        | 37.21%  |
| RAID | 11        | 8.53%   |
| IDE  | 1         | 0.78%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 74        | 74.75%  |
| AMD    | 25        | 25.25%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Intel 12th Gen Core i7-12700H              | 6         | 6.06%   |
| Intel 12th Gen Core i7-1260P               | 4         | 4.04%   |
| Intel Core i7-9750H CPU @ 2.60GHz          | 3         | 3.03%   |
| Intel Core i7-8550U CPU @ 1.80GHz          | 3         | 3.03%   |
| Intel 13th Gen Core i9-13900HX             | 3         | 3.03%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz    | 3         | 3.03%   |
| AMD Ryzen 7 4800H with Radeon Graphics     | 3         | 3.03%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz         | 2         | 2.02%   |
| Intel Core i7-3720QM CPU @ 2.60GHz         | 2         | 2.02%   |
| Intel Core i7-2670QM CPU @ 2.20GHz         | 2         | 2.02%   |
| Intel Core i7-2620M CPU @ 2.70GHz          | 2         | 2.02%   |
| Intel Core i5-9300H CPU @ 2.40GHz          | 2         | 2.02%   |
| Intel Core i5-8365U CPU @ 1.60GHz          | 2         | 2.02%   |
| Intel Core i5-3210M CPU @ 2.50GHz          | 2         | 2.02%   |
| Intel 12th Gen Core i7-1255U               | 2         | 2.02%   |
| Intel 12th Gen Core i5-1240P               | 2         | 2.02%   |
| AMD Ryzen 7 7840HS w/ Radeon 780M Graphics | 2         | 2.02%   |
| AMD Ryzen 7 6800H with Radeon Graphics     | 2         | 2.02%   |
| AMD Ryzen 7 5700U with Radeon Graphics     | 2         | 2.02%   |
| AMD Ryzen 5 4600H with Radeon Graphics     | 2         | 2.02%   |
| Intel Xeon W-10855M CPU @ 2.80GHz          | 1         | 1.01%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz       | 1         | 1.01%   |
| Intel Pentium CPU 2020M @ 2.40GHz          | 1         | 1.01%   |
| Intel N100                                 | 1         | 1.01%   |
| Intel Core i9-10900KF CPU @ 3.70GHz        | 1         | 1.01%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz         | 1         | 1.01%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 1         | 1.01%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz         | 1         | 1.01%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 1         | 1.01%   |
| Intel Core i7-5600U CPU @ 2.60GHz          | 1         | 1.01%   |
| Intel Core i7-5500U CPU @ 2.40GHz          | 1         | 1.01%   |
| Intel Core i7-4650U CPU @ 1.70GHz          | 1         | 1.01%   |
| Intel Core i7-3630QM CPU @ 2.40GHz         | 1         | 1.01%   |
| Intel Core i7-10850H CPU @ 2.70GHz         | 1         | 1.01%   |
| Intel Core i7-10750H CPU @ 2.60GHz         | 1         | 1.01%   |
| Intel Core i7-10710U CPU @ 1.10GHz         | 1         | 1.01%   |
| Intel Core i5-8250U CPU @ 1.60GHz          | 1         | 1.01%   |
| Intel Core i5-7200U CPU @ 2.50GHz          | 1         | 1.01%   |
| Intel Core i5-5250U CPU @ 1.60GHz          | 1         | 1.01%   |
| Intel Core i5-4300Y CPU @ 1.60GHz          | 1         | 1.01%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Other            | 29        | 29.29%  |
| Intel Core i7    | 25        | 25.25%  |
| Intel Core i5    | 13        | 13.13%  |
| AMD Ryzen 7      | 13        | 13.13%  |
| AMD Ryzen 5      | 5         | 5.05%   |
| Intel Xeon       | 2         | 2.02%   |
| AMD Ryzen 9      | 2         | 2.02%   |
| Intel Pentium    | 1         | 1.01%   |
| Intel Core i9    | 1         | 1.01%   |
| Intel Core i3    | 1         | 1.01%   |
| Intel Core 2 Duo | 1         | 1.01%   |
| Intel Celeron    | 1         | 1.01%   |
| AMD Turion II    | 1         | 1.01%   |
| AMD Ryzen 7 PRO  | 1         | 1.01%   |
| AMD Ryzen 5 PRO  | 1         | 1.01%   |
| AMD Ryzen 3      | 1         | 1.01%   |
| AMD A8           | 1         | 1.01%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 30        | 30.3%   |
| 2      | 18        | 18.18%  |
| 8      | 17        | 17.17%  |
| 6      | 13        | 13.13%  |
| 12     | 8         | 8.08%   |
| 14     | 7         | 7.07%   |
| 24     | 3         | 3.03%   |
| 10     | 3         | 3.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 99        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 92        | 92.93%  |
| 1      | 7         | 7.07%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 99        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 89        | 88.12%  |
| 0x906a4    | 2         | 1.98%   |
| 0x906ea    | 1         | 0.99%   |
| 0x906e9    | 1         | 0.99%   |
| 0x906a3    | 1         | 0.99%   |
| 0x806c1    | 1         | 0.99%   |
| 0x306d4    | 1         | 0.99%   |
| 0x0a704103 | 1         | 0.99%   |
| 0x0a704101 | 1         | 0.99%   |
| 0x0a50000c | 1         | 0.99%   |
| 0x08608103 | 1         | 0.99%   |
| 0x010000c8 | 1         | 0.99%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Unknown          | 24        | 24.24%  |
| KabyLake         | 14        | 14.14%  |
| Alderlake Hybrid | 9         | 9.09%   |
| Zen 2            | 7         | 7.07%   |
| IvyBridge        | 7         | 7.07%   |
| TigerLake        | 5         | 5.05%   |
| SandyBridge      | 5         | 5.05%   |
| Haswell          | 5         | 5.05%   |
| CometLake        | 5         | 5.05%   |
| Zen 3            | 4         | 4.04%   |
| Broadwell        | 4         | 4.04%   |
| Skylake          | 3         | 3.03%   |
| Zen+             | 2         | 2.02%   |
| Westmere         | 1         | 1.01%   |
| Puma             | 1         | 1.01%   |
| Penryn           | 1         | 1.01%   |
| K10              | 1         | 1.01%   |
| Gracemont        | 1         | 1.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 71        | 50%     |
| Nvidia | 41        | 28.87%  |
| AMD    | 30        | 21.13%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 13        | 9.15%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 7         | 4.93%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]             | 7         | 4.93%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 6         | 4.23%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 5         | 3.52%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 5         | 3.52%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 5         | 3.52%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 5         | 3.52%   |
| Intel UHD Graphics 620                                                    | 4         | 2.82%   |
| AMD Lucienne                                                              | 4         | 2.82%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                  | 3         | 2.11%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                             | 3         | 2.11%   |
| Intel Raptor Lake-S UHD Graphics                                          | 3         | 2.11%   |
| Intel HD Graphics 5500                                                    | 3         | 2.11%   |
| AMD Rembrandt [Radeon 680M]                                               | 3         | 2.11%   |
| AMD Phoenix1                                                              | 3         | 2.11%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 3         | 2.11%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 1.41%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 2         | 1.41%   |
| Nvidia GF108M [GeForce GT 635M]                                           | 2         | 1.41%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 2         | 1.41%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                           | 2         | 1.41%   |
| Nvidia AD106M [GeForce RTX 4070 Max-Q / Mobile]                           | 2         | 1.41%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 1.41%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                    | 2         | 1.41%   |
| Intel HD Graphics 630                                                     | 2         | 1.41%   |
| Intel HD Graphics 530                                                     | 2         | 1.41%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 1.41%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 2         | 1.41%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                               | 2         | 1.41%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 2         | 1.41%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 2         | 1.41%   |
| AMD Mars XTX [Radeon HD 8790M]                                            | 2         | 1.41%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                             | 1         | 0.7%    |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                   | 1         | 0.7%    |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                          | 1         | 0.7%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.7%    |
| Nvidia GM108M [GeForce 940M]                                              | 1         | 0.7%    |
| Nvidia GM107GLM [Quadro M2000M]                                           | 1         | 0.7%    |
| Nvidia GM107GLM [Quadro M1000M]                                           | 1         | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 39        | 39%     |
| Intel + Nvidia | 26        | 26%     |
| 1 x AMD        | 14        | 14%     |
| AMD + Nvidia   | 11        | 11%     |
| Intel + AMD    | 6         | 6%      |
| 1 x Nvidia     | 4         | 4%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 64        | 64.65%  |
| Proprietary | 34        | 34.34%  |
| Unknown     | 1         | 1.01%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 67        | 67%     |
| 5.01-6.0   | 12        | 12%     |
| 7.01-8.0   | 9         | 9%      |
| 3.01-4.0   | 6         | 6%      |
| 1.01-2.0   | 3         | 3%      |
| 8.01-16.0  | 2         | 2%      |
| 0.01-0.5   | 1         | 1%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 40        | 32.52%  |
| AU Optronics        | 17        | 13.82%  |
| Samsung Electronics | 10        | 8.13%   |
| LG Display          | 8         | 6.5%    |
| Chimei Innolux      | 8         | 6.5%    |
| CSO                 | 6         | 4.88%   |
| Apple               | 5         | 4.07%   |
| Hewlett-Packard     | 4         | 3.25%   |
| Goldstar            | 3         | 2.44%   |
| Dell                | 3         | 2.44%   |
| Acer                | 3         | 2.44%   |
| Sharp               | 2         | 1.63%   |
| Lenovo              | 2         | 1.63%   |
| BenQ                | 2         | 1.63%   |
| AOC                 | 2         | 1.63%   |
| Yamaha              | 1         | 0.81%   |
| Sony                | 1         | 0.81%   |
| SGT                 | 1         | 0.81%   |
| RTK                 | 1         | 0.81%   |
| PANDA               | 1         | 0.81%   |
| Iiyama              | 1         | 0.81%   |
| Fujitsu Siemens     | 1         | 0.81%   |
| ASUSTek Computer    | 1         | 0.81%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE07D8 1920x1080 344x194mm 15.5-inch                   | 6         | 4.72%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                   | 5         | 3.94%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                   | 4         | 3.15%   |
| BOE LCD Monitor BOE084D 1920x1080 344x193mm 15.5-inch                   | 4         | 3.15%   |
| BOE LCD Monitor BOE0AF0 2560x1600 344x215mm 16.0-inch                   | 3         | 2.36%   |
| Chimei Innolux LCD Monitor CMN15BA 1920x1080 344x194mm 15.5-inch        | 2         | 1.57%   |
| BOE LCD Monitor BOE0B40 2560x1440 344x194mm 15.5-inch                   | 2         | 1.57%   |
| BOE LCD Monitor BOE0A3B 2560x1600 344x215mm 16.0-inch                   | 2         | 1.57%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                   | 2         | 1.57%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                   | 2         | 1.57%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch           | 2         | 1.57%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                  | 2         | 1.57%   |
| Yamaha RX-V473 YMH3171 1920x540                                         | 1         | 0.79%   |
| Sony TV SNY4803 1920x1080 930x523mm 42.0-inch                           | 1         | 0.79%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                 | 1         | 0.79%   |
| Sharp LCD Monitor SHP143B 3840x2160 346x194mm 15.6-inch                 | 1         | 0.79%   |
| SGT HS156PC SGT9156 1920x1080 345x194mm 15.6-inch                       | 1         | 0.79%   |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch       | 1         | 0.79%   |
| Samsung Electronics SAMTRON STN0022 1280x1024 380x300mm 19.1-inch       | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch    | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch    | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch    | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch   | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch    | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch    | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 950x540mm 43.0-inch   | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SAM0DEE 3840x2160 1872x1053mm 84.6-inch | 1         | 0.79%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 1         | 0.79%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch       | 1         | 0.79%   |
| RTK Wimaxit FHD RTK5A5B 1920x1080 344x195mm 15.6-inch                   | 1         | 0.79%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                 | 1         | 0.79%   |
| LG Display LCD Monitor LGD065B 1920x1080 382x215mm 17.3-inch            | 1         | 0.79%   |
| LG Display LCD Monitor LGD0621 1920x1080 382x215mm 17.3-inch            | 1         | 0.79%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch            | 1         | 0.79%   |
| LG Display LCD Monitor LGD0545 3200x1800 293x165mm 13.2-inch            | 1         | 0.79%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch            | 1         | 0.79%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch            | 1         | 0.79%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch             | 1         | 0.79%   |
| LG Display LCD Monitor LGD0293 1366x768 321x181mm 14.5-inch             | 1         | 0.79%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                | 1         | 0.79%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 53        | 46.09%  |
| 1366x768 (WXGA)    | 13        | 11.3%   |
| 2560x1440 (QHD)    | 12        | 10.43%  |
| 3840x2160 (4K)     | 8         | 6.96%   |
| 2880x1800          | 6         | 5.22%   |
| 2560x1600          | 5         | 4.35%   |
| 1920x1200 (WUXGA)  | 4         | 3.48%   |
| 1280x800 (WXGA)    | 4         | 3.48%   |
| 1600x900 (HD+)     | 2         | 1.74%   |
| 1440x900 (WXGA+)   | 2         | 1.74%   |
| 3440x1440          | 1         | 0.87%   |
| 3200x1800 (QHD+)   | 1         | 0.87%   |
| 2240x1400          | 1         | 0.87%   |
| 1920x540           | 1         | 0.87%   |
| 1680x1050 (WSXGA+) | 1         | 0.87%   |
| 1280x1024 (SXGA)   | 1         | 0.87%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 50        | 40.32%  |
| 14      | 14        | 11.29%  |
| 17      | 10        | 8.06%   |
| 13      | 10        | 8.06%   |
| 16      | 7         | 5.65%   |
| 27      | 6         | 4.84%   |
| 24      | 6         | 4.84%   |
| 12      | 4         | 3.23%   |
| 40      | 2         | 1.61%   |
| 31      | 2         | 1.61%   |
| 22      | 2         | 1.61%   |
| 21      | 2         | 1.61%   |
| 84      | 1         | 0.81%   |
| 60      | 1         | 0.81%   |
| 43      | 1         | 0.81%   |
| 33      | 1         | 0.81%   |
| 23      | 1         | 0.81%   |
| 20      | 1         | 0.81%   |
| 19      | 1         | 0.81%   |
| 18      | 1         | 0.81%   |
| Unknown | 1         | 0.81%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 72        | 59.02%  |
| 501-600     | 12        | 9.84%   |
| 351-400     | 12        | 9.84%   |
| 201-300     | 11        | 9.02%   |
| 401-500     | 6         | 4.92%   |
| 801-900     | 2         | 1.64%   |
| 601-700     | 2         | 1.64%   |
| 701-800     | 1         | 0.82%   |
| 1501-2000   | 1         | 0.82%   |
| 1001-1500   | 1         | 0.82%   |
| 901-1000    | 1         | 0.82%   |
| Unknown     | 1         | 0.82%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 82        | 75.93%  |
| 16/10 | 22        | 20.37%  |
| 5/4   | 1         | 0.93%   |
| 32/9  | 1         | 0.93%   |
| 3/2   | 1         | 0.93%   |
| 21/9  | 1         | 0.93%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 50        | 40.32%  |
| 81-90          | 22        | 17.74%  |
| 121-130        | 10        | 8.06%   |
| 111-120        | 7         | 5.65%   |
| 301-350        | 6         | 4.84%   |
| 201-250        | 5         | 4.03%   |
| 61-70          | 4         | 3.23%   |
| 251-300        | 4         | 3.23%   |
| 151-200        | 4         | 3.23%   |
| 351-500        | 3         | 2.42%   |
| 501-1000       | 3         | 2.42%   |
| More than 1000 | 2         | 1.61%   |
| 71-80          | 2         | 1.61%   |
| 141-150        | 1         | 0.81%   |
| Unknown        | 1         | 0.81%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 53        | 43.8%   |
| 101-120       | 24        | 19.83%  |
| 161-240       | 17        | 14.05%  |
| 51-100        | 15        | 12.4%   |
| More than 240 | 10        | 8.26%   |
| 1-50          | 1         | 0.83%   |
| Unknown       | 1         | 0.83%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 71        | 71.72%  |
| 2     | 23        | 23.23%  |
| 3     | 4         | 4.04%   |
| 0     | 1         | 1.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 77        | 44.77%  |
| Realtek Semiconductor             | 58        | 33.72%  |
| Qualcomm Atheros                  | 7         | 4.07%   |
| Broadcom Limited                  | 5         | 2.91%   |
| Broadcom                          | 5         | 2.91%   |
| Ralink Technology                 | 4         | 2.33%   |
| Huawei Technologies               | 4         | 2.33%   |
| MediaTek                          | 3         | 1.74%   |
| DisplayLink                       | 2         | 1.16%   |
| ASIX Electronics                  | 2         | 1.16%   |
| TP-Link                           | 1         | 0.58%   |
| Samsung Electronics               | 1         | 0.58%   |
| Lenovo                            | 1         | 0.58%   |
| Ericsson Business Mobile Networks | 1         | 0.58%   |
| Dell                              | 1         | 0.58%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 41        | 21.03%  |
| Intel Wi-Fi 6 AX200                                                  | 24        | 12.31%  |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 12        | 6.15%   |
| Realtek RTL8125 2.5GbE Controller                                    | 8         | 4.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 5         | 2.56%   |
| Intel Wireless 8265 / 8275                                           | 4         | 2.05%   |
| Intel Wi-Fi 6 AX201                                                  | 4         | 2.05%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 3         | 1.54%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 3         | 1.54%   |
| Intel 700 Series Chipset Family Wi-Fi                                | 3         | 1.54%   |
| Huawei ME936 LTE/HSDPA+ 4G modem                                     | 3         | 1.54%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                    | 3         | 1.54%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 3         | 1.54%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 2         | 1.03%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 2         | 1.03%   |
| Realtek Killer E3000 2.5GbE Controller                               | 2         | 1.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2         | 1.03%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 2         | 1.03%   |
| Intel Wireless 8260                                                  | 2         | 1.03%   |
| Intel Wireless 3160                                                  | 2         | 1.03%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 2         | 1.03%   |
| Intel Ethernet Connection I217-LM                                    | 2         | 1.03%   |
| Intel Ethernet Connection (6) I219-LM                                | 2         | 1.03%   |
| Intel Ethernet Connection (2) I219-LM                                | 2         | 1.03%   |
| Intel Centrino Advanced-N 6235                                       | 2         | 1.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 2         | 1.03%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 2         | 1.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 2         | 1.03%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 2         | 1.03%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter          | 2         | 1.03%   |
| ASIX AX88179 Gigabit Ethernet                                        | 2         | 1.03%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 1         | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                        | 1         | 0.51%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 1         | 0.51%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1         | 0.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.51%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 1         | 0.51%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                     | 1         | 0.51%   |
| Ralink MT7601U Wireless Adapter                                      | 1         | 0.51%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 1         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 74        | 73.27%  |
| Realtek Semiconductor | 6         | 5.94%   |
| Broadcom              | 5         | 4.95%   |
| Ralink Technology     | 4         | 3.96%   |
| Qualcomm Atheros      | 4         | 3.96%   |
| Broadcom Limited      | 4         | 3.96%   |
| MediaTek              | 3         | 2.97%   |
| TP-Link               | 1         | 0.99%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 24        | 23.76%  |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 12        | 11.88%  |
| Intel Wireless 8265 / 8275                                           | 4         | 3.96%   |
| Intel Wi-Fi 6 AX201                                                  | 4         | 3.96%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 3         | 2.97%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 3         | 2.97%   |
| Intel 700 Series Chipset Family Wi-Fi                                | 3         | 2.97%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 3         | 2.97%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 2         | 1.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2         | 1.98%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 2         | 1.98%   |
| Intel Wireless 8260                                                  | 2         | 1.98%   |
| Intel Wireless 3160                                                  | 2         | 1.98%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 2         | 1.98%   |
| Intel Centrino Advanced-N 6235                                       | 2         | 1.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 2         | 1.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 2         | 1.98%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 2         | 1.98%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter          | 2         | 1.98%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 1         | 0.99%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 1         | 0.99%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1         | 0.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.99%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 1         | 0.99%   |
| Ralink MT7601U Wireless Adapter                                      | 1         | 0.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 1         | 0.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 1         | 0.99%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 1         | 0.99%   |
| Intel Wireless-AC 9260                                               | 1         | 0.99%   |
| Intel Wireless 7265                                                  | 1         | 0.99%   |
| Intel Wireless 7260                                                  | 1         | 0.99%   |
| Intel Wireless 3165                                                  | 1         | 0.99%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 1         | 0.99%   |
| Intel Ultimate N WiFi Link 5300                                      | 1         | 0.99%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 1         | 0.99%   |
| Intel CNVi: Wi-Fi                                                    | 1         | 0.99%   |
| Intel Centrino Wireless-N 130                                        | 1         | 0.99%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                        | 1         | 0.99%   |
| Intel Centrino Advanced-N 6200                                       | 1         | 0.99%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 1         | 0.99%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 58        | 66.67%  |
| Intel                 | 16        | 18.39%  |
| Qualcomm Atheros      | 3         | 3.45%   |
| Broadcom              | 3         | 3.45%   |
| DisplayLink           | 2         | 2.3%    |
| ASIX Electronics      | 2         | 2.3%    |
| Samsung Electronics   | 1         | 1.15%   |
| Lenovo                | 1         | 1.15%   |
| Broadcom Limited      | 1         | 1.15%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 41        | 46.59%  |
| Realtek RTL8125 2.5GbE Controller                                 | 8         | 9.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 5.68%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 3.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 2.27%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 2.27%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.27%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 2.27%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 2.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.27%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 2.27%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.14%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.14%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.14%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.14%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.14%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 1.14%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.14%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.14%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.14%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.14%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.14%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 1.14%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.14%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.14%   |
| DisplayLink USB3.0 5K Graphic Docking                             | 1         | 1.14%   |
| DisplayLink Plugable UD-3900                                      | 1         | 1.14%   |
| Broadcom Limited NetXtreme BCM57760 Gigabit Ethernet PCIe         | 1         | 1.14%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 98        | 52.69%  |
| Ethernet | 82        | 44.09%  |
| Modem    | 6         | 3.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 73        | 70.19%  |
| Ethernet | 31        | 29.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 72        | 72.73%  |
| 1     | 23        | 23.23%  |
| 3     | 3         | 3.03%   |
| 0     | 1         | 1.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 50        | 50.51%  |
| Yes  | 49        | 49.49%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 69        | 76.67%  |
| Apple                           | 5         | 5.56%   |
| Realtek Semiconductor           | 4         | 4.44%   |
| Foxconn / Hon Hai               | 4         | 4.44%   |
| Broadcom                        | 2         | 2.22%   |
| Qualcomm Atheros Communications | 1         | 1.11%   |
| MediaTek                        | 1         | 1.11%   |
| IMC Networks                    | 1         | 1.11%   |
| Dell                            | 1         | 1.11%   |
| Cambridge Silicon Radio         | 1         | 1.11%   |
| ASUSTek Computer                | 1         | 1.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 26        | 28.89%  |
| Intel AX200 Bluetooth                               | 24        | 26.67%  |
| Intel Bluetooth wireless interface                  | 11        | 12.22%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 3.33%   |
| Apple Bluetooth USB Host Controller                 | 3         | 3.33%   |
| Realtek Bluetooth Radio                             | 2         | 2.22%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 2.22%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 2.22%   |
| Apple Bluetooth Host Controller                     | 2         | 2.22%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.11%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.11%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 1.11%   |
| MediaTek Wireless_Device                            | 1         | 1.11%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.11%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.11%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.11%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 1.11%   |
| Foxconn / Hon Hai Bluetooth Adapter                 | 1         | 1.11%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 1.11%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 1.11%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.11%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.11%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 1.11%   |
| ASUS Bluetooth Device                               | 1         | 1.11%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 72        | 51.43%  |
| Nvidia                                 | 34        | 24.29%  |
| AMD                                    | 26        | 18.57%  |
| Lenovo                                 | 2         | 1.43%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.71%   |
| Razer USA                              | 1         | 0.71%   |
| Logitech                               | 1         | 0.71%   |
| Kingston Technology                    | 1         | 0.71%   |
| GN Netcom                              | 1         | 0.71%   |
| C-Media Electronics                    | 1         | 0.71%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 23        | 14.11%  |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 16        | 9.82%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9         | 5.52%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 4.29%   |
| Nvidia GA106 High Definition Audio Controller                              | 6         | 3.68%   |
| Nvidia GA104 High Definition Audio Controller                              | 6         | 3.68%   |
| Nvidia Audio device                                                        | 6         | 3.68%   |
| Nvidia TU116 High Definition Audio Controller                              | 5         | 3.07%   |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 3.07%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 3.07%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 2.45%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 2.45%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 2.45%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 2.45%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 2.45%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 1.84%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 1.84%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 1.84%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 1.84%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1           | 3         | 1.84%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.84%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 1.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 1.23%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 1.23%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 2         | 1.23%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.23%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 1.23%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 1.23%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.23%   |
| Sony Ericsson Mobile Communications AB XQ-AU52                             | 1         | 0.61%   |
| Razer USA RC30-026902, Gaming Headset [Nari Essential, Wireless, Receiver] | 1         | 0.61%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.61%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.61%   |
| Logitech G430 Surround Sound Gaming Headset                                | 1         | 0.61%   |
| Lenovo USB Headset                                                         | 1         | 0.61%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                               | 1         | 0.61%   |
| Kingston Technology HyperX QuadCast S                                      | 1         | 0.61%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 1         | 0.61%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 0.61%   |
| Intel Alder Lake-N HD Graphics SGPC                                        | 1         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 15        | 42.86%  |
| SK hynix            | 10        | 28.57%  |
| Micron Technology   | 4         | 11.43%  |
| Unknown             | 3         | 8.57%   |
| Team                | 1         | 2.86%   |
| Elpida              | 1         | 2.86%   |
| ASint Technology    | 1         | 2.86%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 5         | 13.89%  |
| Unknown                                                          | 3         | 8.33%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 2         | 5.56%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 5.56%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 1         | 2.78%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 2.78%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 2.78%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.78%   |
| SK hynix RAM HMCG88AGBSA092N 32GB SODIMM DDR5 5600MT/s           | 1         | 2.78%   |
| SK hynix RAM HMCG78AGBSA092N 16GB SODIMM DDR5 5600MT/s           | 1         | 2.78%   |
| SK hynix RAM HMCG66AGBSA095N 8GB SODIMM DDR5 5600MT/s            | 1         | 2.78%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 2.78%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 2.78%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 2.78%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 2.78%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 2.78%   |
| Samsung RAM Module 3GB Row Of Chips LPDDR5 6400MT/s              | 1         | 2.78%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 2.78%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 2.78%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 2.78%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.78%   |
| Samsung RAM M425R4GA3BB0-CQKOL 32GB SODIMM DDR5 4800MT/s         | 1         | 2.78%   |
| Micron RAM MT62F1G32D2DS-026 WT 2GB Row Of Chips LPDDR5 6400MT/s | 1         | 2.78%   |
| Micron RAM Module 2GB Row Of Chips LPDDR5 6400MT/s               | 1         | 2.78%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s             | 1         | 2.78%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 1         | 2.78%   |
| Elpida RAM EBJ21UE8BDS0-AE-F 2048MB SODIMM DDR3 1067MT/s         | 1         | 2.78%   |
| ASint RAM SSZ302G08-GGNHC 2GB SODIMM DDR3 1600MT/s               | 1         | 2.78%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 17        | 54.84%  |
| LPDDR5 | 5         | 16.13%  |
| DDR3   | 5         | 16.13%  |
| DDR5   | 4         | 12.9%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 26        | 83.87%  |
| Row Of Chips | 5         | 16.13%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 10        | 29.41%  |
| 32768 | 8         | 23.53%  |
| 16384 | 7         | 20.59%  |
| 4096  | 4         | 11.76%  |
| 2048  | 4         | 11.76%  |
| 3072  | 1         | 2.94%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 12        | 36.36%  |
| 6400  | 5         | 15.15%  |
| 1600  | 4         | 12.12%  |
| 5600  | 3         | 9.09%   |
| 2667  | 3         | 9.09%   |
| 8400  | 2         | 6.06%   |
| 4800  | 1         | 3.03%   |
| 2400  | 1         | 3.03%   |
| 2133  | 1         | 3.03%   |
| 1067  | 1         | 3.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 42        | 49.41%  |
| Bison Electronics             | 8         | 9.41%   |
| Microdia                      | 6         | 7.06%   |
| Acer                          | 4         | 4.71%   |
| Suyin                         | 3         | 3.53%   |
| IMC Networks                  | 3         | 3.53%   |
| Apple                         | 3         | 3.53%   |
| Sunplus Innovation Technology | 2         | 2.35%   |
| Logitech                      | 2         | 2.35%   |
| Lite-On Technology            | 2         | 2.35%   |
| Unknown                       | 1         | 1.18%   |
| Syntek                        | 1         | 1.18%   |
| Silicon Motion                | 1         | 1.18%   |
| Ricoh                         | 1         | 1.18%   |
| Realtek Semiconductor         | 1         | 1.18%   |
| Luxvisions Innotech Limited   | 1         | 1.18%   |
| Importek                      | 1         | 1.18%   |
| HYGD-220831-A                 | 1         | 1.18%   |
| Generalplus Technology        | 1         | 1.18%   |
| Alpha Imaging Technology      | 1         | 1.18%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony FHD Webcam                                   | 9         | 10.59%  |
| Chicony USB2.0 Camera                                | 7         | 8.24%   |
| Chicony HD Webcam                                    | 7         | 8.24%   |
| Chicony Integrated IR Camera                         | 6         | 7.06%   |
| Acer BisonCam,NB Pro                                 | 4         | 4.71%   |
| IMC Networks Integrated Camera                       | 3         | 3.53%   |
| Chicony Integrated Camera                            | 3         | 3.53%   |
| Bison HD Webcam                                      | 3         | 3.53%   |
| Apple FaceTime HD Camera                             | 3         | 3.53%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 2         | 2.35%   |
| Microdia Integrated_Webcam_FHD                       | 2         | 2.35%   |
| Bison Lenovo EasyCamera                              | 2         | 2.35%   |
| Unknown HD camera                                    | 1         | 1.18%   |
| Syntek Integrated Camera                             | 1         | 1.18%   |
| Suyin RGBIR Camera                                   | 1         | 1.18%   |
| Suyin Integrated_Webcam_HD                           | 1         | 1.18%   |
| Suyin HP TrueVision HD                               | 1         | 1.18%   |
| Sunplus Integrated_Webcam_HD                         | 1         | 1.18%   |
| Sunplus ASUS USB2.0 Webcam                           | 1         | 1.18%   |
| Silicon Motion WebCam SCB-1100N                      | 1         | 1.18%   |
| Ricoh Laptop_Integrated_Webcam_FHD                   | 1         | 1.18%   |
| Realtek Integrated Webcam                            | 1         | 1.18%   |
| Microdia Laptop_Integrated_Webcam_E4HD               | 1         | 1.18%   |
| Microdia Integrated_Webcam_HD                        | 1         | 1.18%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.18%   |
| Logitech BRIO Ultra HD Webcam                        | 1         | 1.18%   |
| Logitech Brio 500                                    | 1         | 1.18%   |
| Lite-On Integrated Camera                            | 1         | 1.18%   |
| Lite-On HP Webcam                                    | 1         | 1.18%   |
| Importek HP Webcam                                   | 1         | 1.18%   |
| HYGD-220831-A Hy-Usb2.0-1*MIC                        | 1         | 1.18%   |
| Generalplus WEB CAM                                  | 1         | 1.18%   |
| Chicony USB2.0 HD UVC WebCam                         | 1         | 1.18%   |
| Chicony USB 2.0 Camera                               | 1         | 1.18%   |
| Chicony ThinkPad T490 Webcam                         | 1         | 1.18%   |
| Chicony HP TrueVision HD Camera                      | 1         | 1.18%   |
| Chicony HP Truevision HD                             | 1         | 1.18%   |
| Chicony HP HD Camera                                 | 1         | 1.18%   |
| Chicony FJ Camera                                    | 1         | 1.18%   |
| Chicony ACER HD User Facing                          | 1         | 1.18%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Synaptics             | 9         | 50%     |
| Validity Sensors      | 7         | 38.89%  |
| LighTuning Technology | 2         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 16.67%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 11.11%  |
| Unknown                                                                    | 2         | 11.11%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 5.56%   |
| Validity Sensors VFS491                                                    | 1         | 5.56%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 5.56%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 5.56%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 5.56%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 5.56%   |
| Synaptics WBDI                                                             | 1         | 5.56%   |
| Synaptics TouchPad                                                         | 1         | 5.56%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 5.56%   |
| LighTuning Fingerprint Reader                                              | 1         | 5.56%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 5.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 57.14%  |
| Alcor Micro | 3         | 42.86%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
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

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 54        | 54.55%  |
| 1     | 43        | 43.43%  |
| 3     | 1         | 1.01%   |
| 2     | 1         | 1.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 18        | 36.73%  |
| Multimedia controller | 14        | 28.57%  |
| Chipcard              | 7         | 14.29%  |
| Graphics card         | 6         | 12.24%  |
| Net/wireless          | 2         | 4.08%   |
| Modem                 | 1         | 2.04%   |
| Card reader           | 1         | 2.04%   |


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

Total: 135

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Pavilion Power Laptop 15... | [8098729533](https://linux-hardware.org/?probe=8098729533) | Jan 30, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [590fcea5fe](https://linux-hardware.org/?probe=590fcea5fe) | Jan 30, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [f45683d844](https://linux-hardware.org/?probe=f45683d844) | Jan 30, 2024 |
| Acer          | Nitro AN515-47              | [521b0ef15b](https://linux-hardware.org/?probe=521b0ef15b) | Jan 13, 2024 |
| HP            | Laptop 15-bw0xx             | [9a8667ecaa](https://linux-hardware.org/?probe=9a8667ecaa) | Jan 12, 2024 |
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
| TUXEDO OS 22.04 | 103       | 100%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| TUXEDO OS | 103       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 6.1.0-1009-tuxedo    | 13        | 11.61%  |
| 6.2.0-10022-tuxedo   | 11        | 9.82%   |
| 6.2.0-10018-tuxedo   | 10        | 8.93%   |
| 6.2.0-10007-tuxedo   | 9         | 8.04%   |
| 6.2.0-10005-tuxedo   | 9         | 8.04%   |
| 6.2.0-10011-tuxedo   | 8         | 7.14%   |
| 6.5.0-10008-tuxedo   | 7         | 6.25%   |
| 6.5.0-10010-tuxedo   | 6         | 5.36%   |
| 6.2.0-10010-tuxedo   | 6         | 5.36%   |
| 6.5.0-10013-tuxedo   | 4         | 3.57%   |
| 6.5.0-10006-tuxedo   | 4         | 3.57%   |
| 5.15.0-10058-tuxedo  | 4         | 3.57%   |
| 5.15.0-10048-tuxedo  | 4         | 3.57%   |
| 6.2.0-10027-tuxedo   | 3         | 2.68%   |
| 5.15.0-10053-tuxedo  | 3         | 2.68%   |
| 5.15.0-10052-tuxedo  | 3         | 2.68%   |
| 5.15.0-10050-tuxedo  | 2         | 1.79%   |
| 6.5.4-060504-generic | 1         | 0.89%   |
| 6.5.0-1014-oem       | 1         | 0.89%   |
| 6.2.0-10014-tuxedo   | 1         | 0.89%   |
| 6.0.0-1010-oem       | 1         | 0.89%   |
| 5.15.0-10057-tuxedo  | 1         | 0.89%   |
| 5.15.0-10056-tuxedo  | 1         | 0.89%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2.0   | 57        | 51.35%  |
| 6.5.0   | 21        | 18.92%  |
| 5.15.0  | 18        | 16.22%  |
| 6.1.0   | 13        | 11.71%  |
| 6.5.4   | 1         | 0.9%    |
| 6.0.0   | 1         | 0.9%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2     | 57        | 51.35%  |
| 6.5     | 22        | 19.82%  |
| 5.15    | 18        | 16.22%  |
| 6.1     | 13        | 11.71%  |
| 6.0     | 1         | 0.9%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 103       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| KDE5 | 103       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 102       | 98.08%  |
| Wayland | 2         | 1.92%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 80        | 76.19%  |
| SDDM    | 25        | 23.81%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| de_DE | 44        | 42.72%  |
| en_US | 28        | 27.18%  |
| en_GB | 8         | 7.77%   |
| it_IT | 4         | 3.88%   |
| en_AU | 3         | 2.91%   |
| pl_PL | 2         | 1.94%   |
| nb_NO | 2         | 1.94%   |
| hu_HU | 2         | 1.94%   |
| fr_FR | 2         | 1.94%   |
| en_AG | 2         | 1.94%   |
| pt_PT | 1         | 0.97%   |
| pt_BR | 1         | 0.97%   |
| et_EE | 1         | 0.97%   |
| es_ES | 1         | 0.97%   |
| en_ZA | 1         | 0.97%   |
| en_DK | 1         | 0.97%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 82        | 78.85%  |
| EFI  | 22        | 21.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 88        | 85.44%  |
| Btrfs   | 9         | 8.74%   |
| Tmpfs   | 4         | 3.88%   |
| Overlay | 2         | 1.94%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 80        | 76.19%  |
| GPT     | 23        | 21.9%   |
| MBR     | 2         | 1.9%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 100       | 96.15%  |
| Yes       | 4         | 3.85%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 98        | 94.23%  |
| Yes       | 6         | 5.77%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| TUXEDO              | 38        | 36.89%  |
| Lenovo              | 16        | 15.53%  |
| Dell                | 12        | 11.65%  |
| Hewlett-Packard     | 11        | 10.68%  |
| ASUSTek Computer    | 5         | 4.85%   |
| Apple               | 5         | 4.85%   |
| Acer                | 5         | 4.85%   |
| Notebook            | 2         | 1.94%   |
| MSI                 | 2         | 1.94%   |
| Schenker            | 1         | 0.97%   |
| Samsung Electronics | 1         | 0.97%   |
| Metabox             | 1         | 0.97%   |
| Fujitsu             | 1         | 0.97%   |
| Chuwi               | 1         | 0.97%   |
| BESSTAR Tech        | 1         | 0.97%   |
| Unknown             | 1         | 0.97%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| TUXEDO InfinityBook S 15/17 Gen7       | 4         | 3.88%   |
| TUXEDO Stellaris Intel Gen5            | 3         | 2.91%   |
| TUXEDO InfinityBook Pro Gen7 (MK1)     | 3         | 2.91%   |
| Unknown                                | 3         | 2.91%   |
| TUXEDO XMG FUSION 15 (XFU15L19)        | 2         | 1.94%   |
| TUXEDO Stellaris/Polaris AMD Gen4      | 2         | 1.94%   |
| TUXEDO Pulse 15 Gen2                   | 2         | 1.94%   |
| TUXEDO Pulse 15 Gen1                   | 2         | 1.94%   |
| TUXEDO Polaris AMD Gen5                | 2         | 1.94%   |
| TUXEDO Polaris 15 AMD Gen1             | 2         | 1.94%   |
| TUXEDO InfinityBook S 15 Gen6          | 2         | 1.94%   |
| TUXEDO InfinityBook Pro Gen7 (MK2)     | 2         | 1.94%   |
| TUXEDO InfinityBook Pro 14 Gen6        | 2         | 1.94%   |
| TUXEDO Aura 15 Gen2                    | 2         | 1.94%   |
| Dell Latitude E6540                    | 2         | 1.94%   |
| Apple MacBookPro8,1                    | 2         | 1.94%   |
| TUXEDO Stellaris AMD Gen3 (CZN)        | 1         | 0.97%   |
| TUXEDO Polaris AMD Gen3 (CZN)          | 1         | 0.97%   |
| TUXEDO P64_HJ,HK1                      | 1         | 0.97%   |
| TUXEDO N7x0WU                          | 1         | 0.97%   |
| TUXEDO N13xWU                          | 1         | 0.97%   |
| TUXEDO Book XUX7 Gen13                 | 1         | 0.97%   |
| Schenker VISION 15 E23 (SVS15E23)      | 1         | 0.97%   |
| Samsung RC530/RC730                    | 1         | 0.97%   |
| Notebook W65_W67RB                     | 1         | 0.97%   |
| Notebook NP5x_NP6x_NP7xHP              | 1         | 0.97%   |
| MSI Prestige 15 A10SC                  | 1         | 0.97%   |
| MSI GE75 Raider 10SF                   | 1         | 0.97%   |
| Metabox Prime-X X170KM                 | 1         | 0.97%   |
| Lenovo Yoga S740-15IRH 81NX            | 1         | 0.97%   |
| Lenovo ThinkPad X200 Tablet 7450WN9    | 1         | 0.97%   |
| Lenovo ThinkPad T490s 20NYS3Y600       | 1         | 0.97%   |
| Lenovo ThinkPad T490 20N3SBU219        | 1         | 0.97%   |
| Lenovo ThinkPad P50 20EQS42M00         | 1         | 0.97%   |
| Lenovo ThinkPad P50 20EQS37F00         | 1         | 0.97%   |
| Lenovo ThinkPad P14s Gen 2a 21A1S00D00 | 1         | 0.97%   |
| Lenovo ThinkPad P1 Gen 3 20TJS1W700    | 1         | 0.97%   |
| Lenovo ThinkPad E580 20KS003SUS        | 1         | 0.97%   |
| Lenovo ThinkBook 14 G2 ARE 20VF        | 1         | 0.97%   |
| Lenovo Legion 5 15IAH7H 82RB           | 1         | 0.97%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| TUXEDO InfinityBook | 13        | 12.62%  |
| Lenovo ThinkPad     | 8         | 7.77%   |
| TUXEDO Stellaris    | 6         | 5.83%   |
| TUXEDO Polaris      | 5         | 4.85%   |
| TUXEDO Pulse        | 4         | 3.88%   |
| Dell Latitude       | 4         | 3.88%   |
| HP Pavilion         | 3         | 2.91%   |
| HP Laptop           | 3         | 2.91%   |
| Dell Precision      | 3         | 2.91%   |
| Dell Inspiron       | 3         | 2.91%   |
| Unknown             | 3         | 2.91%   |
| TUXEDO XMG          | 2         | 1.94%   |
| TUXEDO Aura         | 2         | 1.94%   |
| Lenovo Legion       | 2         | 1.94%   |
| Lenovo IdeaPad      | 2         | 1.94%   |
| HP EliteBook        | 2         | 1.94%   |
| Apple MacBookPro8   | 2         | 1.94%   |
| Acer Swift          | 2         | 1.94%   |
| Acer Nitro          | 2         | 1.94%   |
| TUXEDO P64          | 1         | 0.97%   |
| TUXEDO N7x0WU       | 1         | 0.97%   |
| TUXEDO N13xWU       | 1         | 0.97%   |
| TUXEDO Book         | 1         | 0.97%   |
| Schenker VISION     | 1         | 0.97%   |
| Samsung RC530       | 1         | 0.97%   |
| Notebook W65        | 1         | 0.97%   |
| Notebook NP5x       | 1         | 0.97%   |
| MSI Prestige        | 1         | 0.97%   |
| MSI GE75            | 1         | 0.97%   |
| Metabox Prime-X     | 1         | 0.97%   |
| Lenovo Yoga         | 1         | 0.97%   |
| Lenovo ThinkBook    | 1         | 0.97%   |
| Lenovo G580         | 1         | 0.97%   |
| Lenovo G50-80       | 1         | 0.97%   |
| HP ZBook            | 1         | 0.97%   |
| HP OMEN             | 1         | 0.97%   |
| HP Notebook         | 1         | 0.97%   |
| Fujitsu LIFEBOOK    | 1         | 0.97%   |
| Dell Vostro         | 1         | 0.97%   |
| Dell Venue          | 1         | 0.97%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2022 | 24        | 23.3%   |
| 2020 | 14        | 13.59%  |
| 2023 | 12        | 11.65%  |
| 2021 | 8         | 7.77%   |
| 2019 | 8         | 7.77%   |
| 2017 | 8         | 7.77%   |
| 2015 | 8         | 7.77%   |
| 2012 | 6         | 5.83%   |
| 2011 | 4         | 3.88%   |
| 2013 | 3         | 2.91%   |
| 2014 | 2         | 1.94%   |
| 2008 | 2         | 1.94%   |
| 2018 | 1         | 0.97%   |
| 2010 | 1         | 0.97%   |
| 2009 | 1         | 0.97%   |
| 2007 | 1         | 0.97%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 103       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 103       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 103       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 24        | 23.3%   |
| 16.01-24.0  | 21        | 20.39%  |
| 8.01-16.0   | 19        | 18.45%  |
| 4.01-8.0    | 14        | 13.59%  |
| 64.01-256.0 | 13        | 12.62%  |
| 3.01-4.0    | 6         | 5.83%   |
| 24.01-32.0  | 6         | 5.83%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 40        | 36.7%   |
| 2.01-3.0   | 24        | 22.02%  |
| 1.01-2.0   | 19        | 17.43%  |
| 3.01-4.0   | 15        | 13.76%  |
| 8.01-16.0  | 8         | 7.34%   |
| 16.01-24.0 | 3         | 2.75%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 61        | 58.65%  |
| 2      | 34        | 32.69%  |
| 3      | 7         | 6.73%   |
| 4      | 1         | 0.96%   |
| 0      | 1         | 0.96%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 85        | 82.52%  |
| Yes       | 18        | 17.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 86        | 83.5%   |
| No        | 17        | 16.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 102       | 99.03%  |
| No        | 1         | 0.97%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 93        | 90.29%  |
| No        | 10        | 9.71%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Notebooks | Percent |
|------------------------|-----------|---------|
| Germany                | 49        | 47.57%  |
| USA                    | 15        | 14.56%  |
| UK                     | 4         | 3.88%   |
| Switzerland            | 3         | 2.91%   |
| Portugal               | 3         | 2.91%   |
| Italy                  | 3         | 2.91%   |
| France                 | 3         | 2.91%   |
| Australia              | 3         | 2.91%   |
| Spain                  | 2         | 1.94%   |
| Poland                 | 2         | 1.94%   |
| Norway                 | 2         | 1.94%   |
| Brazil                 | 2         | 1.94%   |
| Austria                | 2         | 1.94%   |
| Turkey                 | 1         | 0.97%   |
| Tunisia                | 1         | 0.97%   |
| South Africa           | 1         | 0.97%   |
| Netherlands            | 1         | 0.97%   |
| Hungary                | 1         | 0.97%   |
| Estonia                | 1         | 0.97%   |
| Denmark                | 1         | 0.97%   |
| Czechia                | 1         | 0.97%   |
| Bulgaria               | 1         | 0.97%   |
| Bosnia and Herzegovina | 1         | 0.97%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Munich                 | 6         | 5.77%   |
| Vienna                 | 2         | 1.92%   |
| Schweinfurt            | 2         | 1.92%   |
| Nuremberg              | 2         | 1.92%   |
| Lucerne                | 2         | 1.92%   |
| Los Angeles            | 2         | 1.92%   |
| Langevag               | 2         | 1.92%   |
| Kiel                   | 2         | 1.92%   |
| Hamburg                | 2         | 1.92%   |
| Duisburg               | 2         | 1.92%   |
| Brisbane               | 2         | 1.92%   |
| Berlin                 | 2         | 1.92%   |
| Zurich                 | 1         | 0.96%   |
| Zabrze                 | 1         | 0.96%   |
| Wembley                | 1         | 0.96%   |
| Watertown              | 1         | 0.96%   |
| Warsaw                 | 1         | 0.96%   |
| Walsall                | 1         | 0.96%   |
| Venlo                  | 1         | 0.96%   |
| Vallejo                | 1         | 0.96%   |
| Teslic                 | 1         | 0.96%   |
| Tallinn                | 1         | 0.96%   |
| Stuttgart              | 1         | 0.96%   |
| Stockstadt am Main     | 1         | 0.96%   |
| Sousse                 | 1         | 0.96%   |
| Solymar                | 1         | 0.96%   |
| Solingen               | 1         | 0.96%   |
| Sistov                 | 1         | 0.96%   |
| Seattle                | 1         | 0.96%   |
| Schwarzenberg          | 1         | 0.96%   |
| Santhià               | 1         | 0.96%   |
| Santa Cruz de Tenerife | 1         | 0.96%   |
| Sankt Wendel           | 1         | 0.96%   |
| San Diego              | 1         | 0.96%   |
| Rome                   | 1         | 0.96%   |
| Rio Maior              | 1         | 0.96%   |
| Reno                   | 1         | 0.96%   |
| Rennes                 | 1         | 0.96%   |
| Redcar                 | 1         | 0.96%   |
| Pruem                  | 1         | 0.96%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 55        | 79     | 41.67%  |
| Sandisk                     | 11        | 13     | 8.33%   |
| Seagate                     | 9         | 9      | 6.82%   |
| Kingston                    | 7         | 7      | 5.3%    |
| Toshiba                     | 5         | 6      | 3.79%   |
| SK hynix                    | 5         | 6      | 3.79%   |
| Micron Technology           | 4         | 5      | 3.03%   |
| Hitachi                     | 4         | 6      | 3.03%   |
| WDC                         | 3         | 3      | 2.27%   |
| Unknown                     | 3         | 3      | 2.27%   |
| Intel                       | 3         | 3      | 2.27%   |
| SPCC                        | 2         | 2      | 1.52%   |
| Phison Electronics          | 2         | 2      | 1.52%   |
| Apple                       | 2         | 2      | 1.52%   |
| USB3.0                      | 1         | 1      | 0.76%   |
| Transcend                   | 1         | 1      | 0.76%   |
| Phison                      | 1         | 3      | 0.76%   |
| OWC                         | 1         | 1      | 0.76%   |
| Netac                       | 1         | 1      | 0.76%   |
| Micron/Crucial Technology   | 1         | 1      | 0.76%   |
| LITEONIT                    | 1         | 1      | 0.76%   |
| Lenovo                      | 1         | 1      | 0.76%   |
| KIOXIA                      | 1         | 1      | 0.76%   |
| Kingston Technology Company | 1         | 1      | 0.76%   |
| Kingchuxing                 | 1         | 1      | 0.76%   |
| Intenso                     | 1         | 1      | 0.76%   |
| HGST                        | 1         | 1      | 0.76%   |
| CT1000BX                    | 1         | 1      | 0.76%   |
| Crucial                     | 1         | 1      | 0.76%   |
| ASMedia                     | 1         | 2      | 0.76%   |
| ADATA Technology            | 1         | 1      | 0.76%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 11        | 7.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 10        | 7.14%   |
| Samsung SSD 980 1TB                                | 8         | 5.71%   |
| Samsung SSD 980 500GB                              | 6         | 4.29%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB   | 3         | 2.14%   |
| Samsung SSD 980 PRO 1TB                            | 3         | 2.14%   |
| Samsung SSD 970 EVO Plus 1TB                       | 3         | 2.14%   |
| Kingston SA400S37240G 240GB SSD                    | 3         | 2.14%   |
| Toshiba MQ01ABD100 1TB                             | 2         | 1.43%   |
| Sandisk WD Blue SN570 1TB                          | 2         | 1.43%   |
| SanDisk SDSSDA240G 240GB                           | 2         | 1.43%   |
| Samsung SSD 990 PRO 1TB                            | 2         | 1.43%   |
| Samsung SSD 980 PRO 500GB                          | 2         | 1.43%   |
| Samsung SSD 980 PRO 2TB                            | 2         | 1.43%   |
| Samsung SSD 850 EVO 1TB                            | 2         | 1.43%   |
| Hitachi HTS727550A9E364 500GB                      | 2         | 1.43%   |
| WDC WD3200BPVT-24JJ5T0 320GB                       | 1         | 0.71%   |
| WDC WD10JPVX-22JC3T0 1TB                           | 1         | 0.71%   |
| WDC WD Elements SE SSD 1TB                         | 1         | 0.71%   |
| USB3.0 Super Speed 500GB SSD                       | 1         | 0.71%   |
| Unknown MMC Card  64GB                             | 1         | 0.71%   |
| Unknown MMC Card  2GB                              | 1         | 0.71%   |
| Unknown MMC Card  256GB                            | 1         | 0.71%   |
| Transcend TS512GSSD230S 512GB                      | 1         | 0.71%   |
| Toshiba XG4 NVMe SSD Controller 512GB              | 1         | 0.71%   |
| Toshiba MQ01ABF050 500GB                           | 1         | 0.71%   |
| Toshiba BG3 NVMe SSD Controller 256GB              | 1         | 0.71%   |
| SPCC M.2 SSD 256GB                                 | 1         | 0.71%   |
| SPCC M.2 PCIe SSD 1TB                              | 1         | 0.71%   |
| SK hynix SKHynix_HFS512GEJ4X112N 512GB             | 1         | 0.71%   |
| SK hynix SKHynix_HFS001TDE9X084N 1024GB            | 1         | 0.71%   |
| SK hynix SKHynix_HFS001TDE9X081N 1TB               | 1         | 0.71%   |
| SK hynix SC311 SATA 256GB SSD                      | 1         | 0.71%   |
| SK hynix HFS512GEJ9X125N 512GB                     | 1         | 0.71%   |
| Seagate ST500LT012-1DG142 500GB                    | 1         | 0.71%   |
| Seagate ST500LM034-2GH17A 500GB                    | 1         | 0.71%   |
| Seagate ST250LT003-9YG14C 250GB                    | 1         | 0.71%   |
| Seagate ST2000LM015-2E8174 2TB                     | 1         | 0.71%   |
| Seagate ST1000LM048-2E7172 1TB                     | 1         | 0.71%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 1         | 0.71%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 8      | 44.44%  |
| Hitachi | 4         | 6      | 22.22%  |
| Toshiba | 3         | 3      | 16.67%  |
| WDC     | 2         | 2      | 11.11%  |
| HGST    | 1         | 1      | 5.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 10     | 29.03%  |
| Kingston            | 5         | 5      | 16.13%  |
| SanDisk             | 3         | 3      | 9.68%   |
| Apple               | 2         | 2      | 6.45%   |
| WDC                 | 1         | 1      | 3.23%   |
| USB3.0              | 1         | 1      | 3.23%   |
| Transcend           | 1         | 1      | 3.23%   |
| SPCC                | 1         | 1      | 3.23%   |
| SK hynix            | 1         | 2      | 3.23%   |
| OWC                 | 1         | 1      | 3.23%   |
| Netac               | 1         | 1      | 3.23%   |
| Micron Technology   | 1         | 1      | 3.23%   |
| LITEONIT            | 1         | 1      | 3.23%   |
| Intenso             | 1         | 1      | 3.23%   |
| CT1000BX            | 1         | 1      | 3.23%   |
| Crucial             | 1         | 1      | 3.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 72        | 107    | 59.02%  |
| SSD     | 27        | 33     | 22.13%  |
| HDD     | 18        | 20     | 14.75%  |
| MMC     | 3         | 3      | 2.46%   |
| Unknown | 2         | 3      | 1.64%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 72        | 107    | 59.5%   |
| SATA | 40        | 49     | 33.06%  |
| SAS  | 6         | 7      | 4.96%   |
| MMC  | 3         | 3      | 2.48%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 26        | 32     | 56.52%  |
| 0.51-1.0   | 17        | 18     | 36.96%  |
| 1.01-2.0   | 2         | 2      | 4.35%   |
| 4.01-10.0  | 1         | 1      | 2.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 27        | 25.96%  |
| 251-500        | 21        | 20.19%  |
| 101-250        | 21        | 20.19%  |
| 1001-2000      | 16        | 15.38%  |
| 1-20           | 6         | 5.77%   |
| 2001-3000      | 5         | 4.81%   |
| More than 3000 | 3         | 2.88%   |
| Unknown        | 3         | 2.88%   |
| 21-50          | 1         | 0.96%   |
| 51-100         | 1         | 0.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 35        | 32.71%  |
| 21-50     | 27        | 25.23%  |
| 101-250   | 15        | 14.02%  |
| 51-100    | 9         | 8.41%   |
| 501-1000  | 8         | 7.48%   |
| 251-500   | 6         | 5.61%   |
| 1001-2000 | 4         | 3.74%   |
| Unknown   | 3         | 2.8%    |

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
| Detected | 79        | 131    | 75.24%  |
| Works    | 26        | 35     | 24.76%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 48        | 35.29%  |
| Intel                        | 46        | 33.82%  |
| AMD                          | 12        | 8.82%   |
| SanDisk                      | 8         | 5.88%   |
| SK hynix                     | 4         | 2.94%   |
| Phison Electronics           | 3         | 2.21%   |
| Micron Technology            | 3         | 2.21%   |
| Kingston Technology Company  | 3         | 2.21%   |
| Toshiba America Info Systems | 2         | 1.47%   |
| Silicon Motion               | 1         | 0.74%   |
| Seagate Technology           | 1         | 0.74%   |
| Micron/Crucial Technology    | 1         | 0.74%   |
| Marvell Technology Group     | 1         | 0.74%   |
| Lenovo                       | 1         | 0.74%   |
| KIOXIA                       | 1         | 0.74%   |
| ADATA Technology             | 1         | 0.74%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 17        | 11.81%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 14        | 9.72%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                   | 14        | 9.72%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 11        | 7.64%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 7         | 4.86%   |
| Intel Volume Management Device NVMe RAID Controller                           | 6         | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 5         | 3.47%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 4         | 2.78%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                         | 3         | 2.08%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD          | 3         | 2.08%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 3         | 2.08%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 3         | 2.08%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 3         | 2.08%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                          | 2         | 1.39%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 2         | 1.39%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                   | 2         | 1.39%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 2         | 1.39%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 2         | 1.39%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 2         | 1.39%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                          | 2         | 1.39%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                          | 1         | 0.69%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)           | 1         | 0.69%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                            | 1         | 0.69%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                             | 1         | 0.69%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                 | 1         | 0.69%   |
| Seagate BarraCuda Q5 NVMe SSD (DRAM-less)                                     | 1         | 0.69%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                    | 1         | 0.69%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                         | 1         | 0.69%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                         | 1         | 0.69%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                    | 1         | 0.69%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                           | 1         | 0.69%   |
| Phison E16 PCIe4 NVMe Controller                                              | 1         | 0.69%   |
| Phison E12 NVMe Controller                                                    | 1         | 0.69%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)          | 1         | 0.69%   |
| Micron 3400 NVMe SSD [Hendrix]                                                | 1         | 0.69%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                   | 1         | 0.69%   |
| Micron 2400 NVMe SSD (DRAM-less)                                              | 1         | 0.69%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                    | 1         | 0.69%   |
| Lenovo LENSE30256GMSP34MEAT3TA                                                | 1         | 0.69%   |
| KIOXIA NVMe SSD Controller XG8                                                | 1         | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 72        | 53.73%  |
| SATA | 50        | 37.31%  |
| RAID | 11        | 8.21%   |
| IDE  | 1         | 0.75%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 75        | 72.82%  |
| AMD    | 28        | 27.18%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Intel 12th Gen Core i7-12700H              | 6         | 5.83%   |
| Intel 12th Gen Core i7-1260P               | 4         | 3.88%   |
| Intel Core i7-9750H CPU @ 2.60GHz          | 3         | 2.91%   |
| Intel Core i7-8550U CPU @ 1.80GHz          | 3         | 2.91%   |
| Intel 13th Gen Core i9-13900HX             | 3         | 2.91%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz    | 3         | 2.91%   |
| AMD Ryzen 7 4800H with Radeon Graphics     | 3         | 2.91%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 2         | 1.94%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz         | 2         | 1.94%   |
| Intel Core i7-3720QM CPU @ 2.60GHz         | 2         | 1.94%   |
| Intel Core i7-2670QM CPU @ 2.20GHz         | 2         | 1.94%   |
| Intel Core i7-2620M CPU @ 2.70GHz          | 2         | 1.94%   |
| Intel Core i5-9300H CPU @ 2.40GHz          | 2         | 1.94%   |
| Intel Core i5-8365U CPU @ 1.60GHz          | 2         | 1.94%   |
| Intel Core i5-3210M CPU @ 2.50GHz          | 2         | 1.94%   |
| Intel 12th Gen Core i7-1255U               | 2         | 1.94%   |
| Intel 12th Gen Core i5-1240P               | 2         | 1.94%   |
| AMD Ryzen 7 7840HS w/ Radeon 780M Graphics | 2         | 1.94%   |
| AMD Ryzen 7 6800H with Radeon Graphics     | 2         | 1.94%   |
| AMD Ryzen 7 5700U with Radeon Graphics     | 2         | 1.94%   |
| AMD Ryzen 5 4600H with Radeon Graphics     | 2         | 1.94%   |
| Intel Xeon W-10855M CPU @ 2.80GHz          | 1         | 0.97%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz       | 1         | 0.97%   |
| Intel Pentium CPU 2020M @ 2.40GHz          | 1         | 0.97%   |
| Intel N100                                 | 1         | 0.97%   |
| Intel Core i9-10900KF CPU @ 3.70GHz        | 1         | 0.97%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz         | 1         | 0.97%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz         | 1         | 0.97%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 1         | 0.97%   |
| Intel Core i7-5600U CPU @ 2.60GHz          | 1         | 0.97%   |
| Intel Core i7-5500U CPU @ 2.40GHz          | 1         | 0.97%   |
| Intel Core i7-4650U CPU @ 1.70GHz          | 1         | 0.97%   |
| Intel Core i7-3630QM CPU @ 2.40GHz         | 1         | 0.97%   |
| Intel Core i7-10850H CPU @ 2.70GHz         | 1         | 0.97%   |
| Intel Core i7-10750H CPU @ 2.60GHz         | 1         | 0.97%   |
| Intel Core i7-10710U CPU @ 1.10GHz         | 1         | 0.97%   |
| Intel Core i5-8250U CPU @ 1.60GHz          | 1         | 0.97%   |
| Intel Core i5-7200U CPU @ 2.50GHz          | 1         | 0.97%   |
| Intel Core i5-5250U CPU @ 1.60GHz          | 1         | 0.97%   |
| Intel Core i5-4300Y CPU @ 1.60GHz          | 1         | 0.97%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Other            | 29        | 28.16%  |
| Intel Core i7    | 26        | 25.24%  |
| AMD Ryzen 7      | 14        | 13.59%  |
| Intel Core i5    | 13        | 12.62%  |
| AMD Ryzen 5      | 6         | 5.83%   |
| Intel Xeon       | 2         | 1.94%   |
| AMD Ryzen 9      | 2         | 1.94%   |
| Intel Pentium    | 1         | 0.97%   |
| Intel Core i9    | 1         | 0.97%   |
| Intel Core i3    | 1         | 0.97%   |
| Intel Core 2 Duo | 1         | 0.97%   |
| Intel Celeron    | 1         | 0.97%   |
| AMD Turion II    | 1         | 0.97%   |
| AMD Ryzen 7 PRO  | 1         | 0.97%   |
| AMD Ryzen 5 PRO  | 1         | 0.97%   |
| AMD Ryzen 3      | 1         | 0.97%   |
| AMD A8           | 1         | 0.97%   |
| AMD A10          | 1         | 0.97%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 31        | 30.1%   |
| 2      | 19        | 18.45%  |
| 8      | 18        | 17.48%  |
| 6      | 14        | 13.59%  |
| 12     | 8         | 7.77%   |
| 14     | 7         | 6.8%    |
| 24     | 3         | 2.91%   |
| 10     | 3         | 2.91%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 103       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 96        | 93.2%   |
| 1      | 7         | 6.8%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 103       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 92        | 87.62%  |
| 0x906a4    | 2         | 1.9%    |
| 0x906ea    | 1         | 0.95%   |
| 0x906e9    | 1         | 0.95%   |
| 0x906a3    | 1         | 0.95%   |
| 0x806c1    | 1         | 0.95%   |
| 0x306d4    | 1         | 0.95%   |
| 0x0a704103 | 1         | 0.95%   |
| 0x0a704101 | 1         | 0.95%   |
| 0x0a50000c | 1         | 0.95%   |
| 0x0a404102 | 1         | 0.95%   |
| 0x08608103 | 1         | 0.95%   |
| 0x010000c8 | 1         | 0.95%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Unknown          | 26        | 25.24%  |
| KabyLake         | 15        | 14.56%  |
| Alderlake Hybrid | 9         | 8.74%   |
| Zen 2            | 7         | 6.8%    |
| IvyBridge        | 7         | 6.8%    |
| TigerLake        | 5         | 4.85%   |
| SandyBridge      | 5         | 4.85%   |
| Haswell          | 5         | 4.85%   |
| CometLake        | 5         | 4.85%   |
| Zen 3            | 4         | 3.88%   |
| Broadwell        | 4         | 3.88%   |
| Skylake          | 3         | 2.91%   |
| Zen+             | 2         | 1.94%   |
| Westmere         | 1         | 0.97%   |
| Puma             | 1         | 0.97%   |
| Penryn           | 1         | 0.97%   |
| K10              | 1         | 0.97%   |
| Gracemont        | 1         | 0.97%   |
| Excavator        | 1         | 0.97%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 72        | 48.65%  |
| Nvidia | 43        | 29.05%  |
| AMD    | 33        | 22.3%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 13        | 8.67%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 7         | 4.67%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]             | 7         | 4.67%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 6         | 4%      |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 5         | 3.33%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 5         | 3.33%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 5         | 3.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 5         | 3.33%   |
| AMD Rembrandt [Radeon 680M]                                               | 5         | 3.33%   |
| Intel UHD Graphics 620                                                    | 4         | 2.67%   |
| AMD Lucienne                                                              | 4         | 2.67%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 3         | 2%      |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                  | 3         | 2%      |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                             | 3         | 2%      |
| Intel Raptor Lake-S UHD Graphics                                          | 3         | 2%      |
| Intel HD Graphics 630                                                     | 3         | 2%      |
| Intel HD Graphics 5500                                                    | 3         | 2%      |
| AMD Phoenix1                                                              | 3         | 2%      |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 3         | 2%      |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 1.33%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 2         | 1.33%   |
| Nvidia GF108M [GeForce GT 635M]                                           | 2         | 1.33%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                           | 2         | 1.33%   |
| Nvidia AD106M [GeForce RTX 4070 Max-Q / Mobile]                           | 2         | 1.33%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 1.33%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                    | 2         | 1.33%   |
| Intel HD Graphics 530                                                     | 2         | 1.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 1.33%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 2         | 1.33%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                               | 2         | 1.33%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 2         | 1.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 2         | 1.33%   |
| AMD Mars XTX [Radeon HD 8790M]                                            | 2         | 1.33%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                             | 1         | 0.67%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                   | 1         | 0.67%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                          | 1         | 0.67%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.67%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 0.67%   |
| Nvidia GM108M [GeForce 940M]                                              | 1         | 0.67%   |
| Nvidia GM107GLM [Quadro M2000M]                                           | 1         | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 39        | 37.5%   |
| Intel + Nvidia | 27        | 25.96%  |
| 1 x AMD        | 14        | 13.46%  |
| AMD + Nvidia   | 12        | 11.54%  |
| Intel + AMD    | 6         | 5.77%   |
| 1 x Nvidia     | 4         | 3.85%   |
| 2 x AMD        | 2         | 1.92%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 66        | 64.08%  |
| Proprietary | 36        | 34.95%  |
| Unknown     | 1         | 0.97%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 70        | 67.31%  |
| 5.01-6.0   | 12        | 11.54%  |
| 7.01-8.0   | 9         | 8.65%   |
| 3.01-4.0   | 7         | 6.73%   |
| 1.01-2.0   | 3         | 2.88%   |
| 8.01-16.0  | 2         | 1.92%   |
| 0.01-0.5   | 1         | 0.96%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 43        | 33.33%  |
| AU Optronics        | 17        | 13.18%  |
| Samsung Electronics | 10        | 7.75%   |
| LG Display          | 9         | 6.98%   |
| Chimei Innolux      | 8         | 6.2%    |
| CSO                 | 6         | 4.65%   |
| Apple               | 5         | 3.88%   |
| Hewlett-Packard     | 4         | 3.1%    |
| Goldstar            | 3         | 2.33%   |
| Dell                | 3         | 2.33%   |
| Acer                | 3         | 2.33%   |
| Sharp               | 2         | 1.55%   |
| SGT                 | 2         | 1.55%   |
| Lenovo              | 2         | 1.55%   |
| BenQ                | 2         | 1.55%   |
| AOC                 | 2         | 1.55%   |
| Yamaha              | 1         | 0.78%   |
| VIE                 | 1         | 0.78%   |
| Sony                | 1         | 0.78%   |
| RTK                 | 1         | 0.78%   |
| PANDA               | 1         | 0.78%   |
| Iiyama              | 1         | 0.78%   |
| Fujitsu Siemens     | 1         | 0.78%   |
| ASUSTek Computer    | 1         | 0.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE07D8 1920x1080 344x194mm 15.5-inch                   | 6         | 4.51%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                   | 5         | 3.76%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                   | 4         | 3.01%   |
| BOE LCD Monitor BOE084D 1920x1080 344x193mm 15.5-inch                   | 4         | 3.01%   |
| BOE LCD Monitor BOE0AF0 2560x1600 344x215mm 16.0-inch                   | 3         | 2.26%   |
| Chimei Innolux LCD Monitor CMN15BA 1920x1080 344x194mm 15.5-inch        | 2         | 1.5%    |
| BOE LCD Monitor BOE0B40 2560x1440 344x194mm 15.5-inch                   | 2         | 1.5%    |
| BOE LCD Monitor BOE0A3B 2560x1600 344x215mm 16.0-inch                   | 2         | 1.5%    |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                   | 2         | 1.5%    |
| BOE LCD Monitor BOE0747 1920x1080 345x195mm 15.6-inch                   | 2         | 1.5%    |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch           | 2         | 1.5%    |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                  | 2         | 1.5%    |
| Yamaha RX-V473 YMH3171 1920x540                                         | 1         | 0.75%   |
| VIE EZCOOL EZ24 VIE2380 1920x1080 598x336mm 27.0-inch                   | 1         | 0.75%   |
| Sony TV SNY4803 1920x1080 930x523mm 42.0-inch                           | 1         | 0.75%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                 | 1         | 0.75%   |
| Sharp LCD Monitor SHP143B 3840x2160 346x194mm 15.6-inch                 | 1         | 0.75%   |
| SGT M2145J1F2281 SGT2145 1920x1080 477x268mm 21.5-inch                  | 1         | 0.75%   |
| SGT HS156PC SGT9156 1920x1080 345x194mm 15.6-inch                       | 1         | 0.75%   |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch       | 1         | 0.75%   |
| Samsung Electronics SAMTRON STN0022 1280x1024 380x300mm 19.1-inch       | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch    | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch    | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch    | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch   | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch    | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SDC4141 3840x2160 344x194mm 15.5-inch   | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 950x540mm 43.0-inch   | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SAM0DEE 3840x2160 1872x1053mm 84.6-inch | 1         | 0.75%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 1         | 0.75%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch       | 1         | 0.75%   |
| RTK Wimaxit FHD RTK5A5B 1920x1080 344x195mm 15.6-inch                   | 1         | 0.75%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                 | 1         | 0.75%   |
| LG Display LCD Monitor LGD065B 1920x1080 382x215mm 17.3-inch            | 1         | 0.75%   |
| LG Display LCD Monitor LGD0621 1920x1080 382x215mm 17.3-inch            | 1         | 0.75%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch            | 1         | 0.75%   |
| LG Display LCD Monitor LGD058C 1920x1080 344x194mm 15.5-inch            | 1         | 0.75%   |
| LG Display LCD Monitor LGD0545 3200x1800 293x165mm 13.2-inch            | 1         | 0.75%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch            | 1         | 0.75%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch            | 1         | 0.75%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 56        | 46.67%  |
| 1366x768 (WXGA)    | 14        | 11.67%  |
| 2560x1440 (QHD)    | 12        | 10%     |
| 3840x2160 (4K)     | 8         | 6.67%   |
| 2880x1800          | 6         | 5%      |
| 2560x1600          | 5         | 4.17%   |
| 1920x1200 (WUXGA)  | 5         | 4.17%   |
| 1280x800 (WXGA)    | 4         | 3.33%   |
| 1600x900 (HD+)     | 2         | 1.67%   |
| 1440x900 (WXGA+)   | 2         | 1.67%   |
| 3440x1440          | 1         | 0.83%   |
| 3200x1800 (QHD+)   | 1         | 0.83%   |
| 2240x1400          | 1         | 0.83%   |
| 1920x540           | 1         | 0.83%   |
| 1680x1050 (WSXGA+) | 1         | 0.83%   |
| 1280x1024 (SXGA)   | 1         | 0.83%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 53        | 40.77%  |
| 14      | 14        | 10.77%  |
| 17      | 10        | 7.69%   |
| 13      | 10        | 7.69%   |
| 16      | 8         | 6.15%   |
| 27      | 7         | 5.38%   |
| 24      | 6         | 4.62%   |
| 12      | 4         | 3.08%   |
| 21      | 3         | 2.31%   |
| 40      | 2         | 1.54%   |
| 31      | 2         | 1.54%   |
| 22      | 2         | 1.54%   |
| 84      | 1         | 0.77%   |
| 60      | 1         | 0.77%   |
| 43      | 1         | 0.77%   |
| 33      | 1         | 0.77%   |
| 23      | 1         | 0.77%   |
| 20      | 1         | 0.77%   |
| 19      | 1         | 0.77%   |
| 18      | 1         | 0.77%   |
| Unknown | 1         | 0.77%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 76        | 59.38%  |
| 501-600     | 13        | 10.16%  |
| 351-400     | 12        | 9.38%   |
| 201-300     | 11        | 8.59%   |
| 401-500     | 7         | 5.47%   |
| 801-900     | 2         | 1.56%   |
| 601-700     | 2         | 1.56%   |
| 701-800     | 1         | 0.78%   |
| 1501-2000   | 1         | 0.78%   |
| 1001-1500   | 1         | 0.78%   |
| 901-1000    | 1         | 0.78%   |
| Unknown     | 1         | 0.78%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 85        | 75.89%  |
| 16/10 | 23        | 20.54%  |
| 5/4   | 1         | 0.89%   |
| 32/9  | 1         | 0.89%   |
| 3/2   | 1         | 0.89%   |
| 21/9  | 1         | 0.89%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 53        | 40.77%  |
| 81-90          | 22        | 16.92%  |
| 121-130        | 10        | 7.69%   |
| 111-120        | 8         | 6.15%   |
| 301-350        | 7         | 5.38%   |
| 201-250        | 5         | 3.85%   |
| 151-200        | 5         | 3.85%   |
| 61-70          | 4         | 3.08%   |
| 251-300        | 4         | 3.08%   |
| 351-500        | 3         | 2.31%   |
| 501-1000       | 3         | 2.31%   |
| More than 1000 | 2         | 1.54%   |
| 71-80          | 2         | 1.54%   |
| 141-150        | 1         | 0.77%   |
| Unknown        | 1         | 0.77%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 56        | 44.44%  |
| 101-120       | 25        | 19.84%  |
| 161-240       | 17        | 13.49%  |
| 51-100        | 16        | 12.7%   |
| More than 240 | 10        | 7.94%   |
| 1-50          | 1         | 0.79%   |
| Unknown       | 1         | 0.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 73        | 70.87%  |
| 2     | 25        | 24.27%  |
| 3     | 4         | 3.88%   |
| 0     | 1         | 0.97%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 78        | 43.82%  |
| Realtek Semiconductor             | 62        | 34.83%  |
| Qualcomm Atheros                  | 7         | 3.93%   |
| Broadcom Limited                  | 5         | 2.81%   |
| Broadcom                          | 5         | 2.81%   |
| Ralink Technology                 | 4         | 2.25%   |
| MediaTek                          | 4         | 2.25%   |
| Huawei Technologies               | 4         | 2.25%   |
| DisplayLink                       | 2         | 1.12%   |
| ASIX Electronics                  | 2         | 1.12%   |
| TP-Link                           | 1         | 0.56%   |
| Samsung Electronics               | 1         | 0.56%   |
| Lenovo                            | 1         | 0.56%   |
| Ericsson Business Mobile Networks | 1         | 0.56%   |
| Dell                              | 1         | 0.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 44        | 21.67%  |
| Intel Wi-Fi 6 AX200                                                    | 24        | 11.82%  |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 12        | 5.91%   |
| Realtek RTL8125 2.5GbE Controller                                      | 8         | 3.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 2.46%   |
| Intel Wireless 8265 / 8275                                             | 4         | 1.97%   |
| Intel Wi-Fi 6 AX201                                                    | 4         | 1.97%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 3         | 1.48%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 3         | 1.48%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 3         | 1.48%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 3         | 1.48%   |
| Huawei ME936 LTE/HSDPA+ 4G modem                                       | 3         | 1.48%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 1.48%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 3         | 1.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 2         | 0.99%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 2         | 0.99%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2         | 0.99%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 2         | 0.99%   |
| Realtek Killer E2600 GbE Controller                                    | 2         | 0.99%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 2         | 0.99%   |
| Intel Wireless 8260                                                    | 2         | 0.99%   |
| Intel Wireless 7265                                                    | 2         | 0.99%   |
| Intel Wireless 3160                                                    | 2         | 0.99%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 2         | 0.99%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 0.99%   |
| Intel Ethernet Connection (6) I219-LM                                  | 2         | 0.99%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 0.99%   |
| Intel Centrino Advanced-N 6235                                         | 2         | 0.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 2         | 0.99%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 2         | 0.99%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 0.99%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 2         | 0.99%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter            | 2         | 0.99%   |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 0.99%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 1         | 0.49%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.49%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1         | 0.49%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 1         | 0.49%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 1         | 0.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1         | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 75        | 71.43%  |
| Realtek Semiconductor | 8         | 7.62%   |
| Broadcom              | 5         | 4.76%   |
| Ralink Technology     | 4         | 3.81%   |
| Qualcomm Atheros      | 4         | 3.81%   |
| MediaTek              | 4         | 3.81%   |
| Broadcom Limited      | 4         | 3.81%   |
| TP-Link               | 1         | 0.95%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 24        | 22.86%  |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 12        | 11.43%  |
| Intel Wireless 8265 / 8275                                           | 4         | 3.81%   |
| Intel Wi-Fi 6 AX201                                                  | 4         | 3.81%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 3         | 2.86%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 3         | 2.86%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                    | 3         | 2.86%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 3         | 2.86%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 3         | 2.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 2         | 1.9%    |
| Realtek RTL8723DE Wireless Network Adapter                           | 2         | 1.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2         | 1.9%    |
| Intel Wireless 8260                                                  | 2         | 1.9%    |
| Intel Wireless 7265                                                  | 2         | 1.9%    |
| Intel Wireless 3160                                                  | 2         | 1.9%    |
| Intel Raptor Lake PCH CNVi WiFi                                      | 2         | 1.9%    |
| Intel Centrino Advanced-N 6235                                       | 2         | 1.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 2         | 1.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 2         | 1.9%    |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 2         | 1.9%    |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter          | 2         | 1.9%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 1         | 0.95%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 1         | 0.95%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 1         | 0.95%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1         | 0.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.95%   |
| Ralink MT7601U Wireless Adapter                                      | 1         | 0.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 1         | 0.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 1         | 0.95%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 1         | 0.95%   |
| Intel Wireless 7260                                                  | 1         | 0.95%   |
| Intel Wireless 3165                                                  | 1         | 0.95%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 1         | 0.95%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 1         | 0.95%   |
| Intel Ultimate N WiFi Link 5300                                      | 1         | 0.95%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 1         | 0.95%   |
| Intel CNVi: Wi-Fi                                                    | 1         | 0.95%   |
| Intel Centrino Wireless-N 130                                        | 1         | 0.95%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                        | 1         | 0.95%   |
| Intel Centrino Advanced-N 6200                                       | 1         | 0.95%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 62        | 68.13%  |
| Intel                 | 16        | 17.58%  |
| Qualcomm Atheros      | 3         | 3.3%    |
| Broadcom              | 3         | 3.3%    |
| DisplayLink           | 2         | 2.2%    |
| ASIX Electronics      | 2         | 2.2%    |
| Samsung Electronics   | 1         | 1.1%    |
| Lenovo                | 1         | 1.1%    |
| Broadcom Limited      | 1         | 1.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 44        | 47.83%  |
| Realtek RTL8125 2.5GbE Controller                                      | 8         | 8.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 5.43%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 3.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2         | 2.17%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 2         | 2.17%   |
| Realtek Killer E2600 GbE Controller                                    | 2         | 2.17%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 2.17%   |
| Intel Ethernet Connection (6) I219-LM                                  | 2         | 2.17%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 2.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 2.17%   |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 2.17%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 1.09%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 1.09%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 1.09%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 1.09%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 1         | 1.09%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 1.09%   |
| Intel Ethernet Connection (5) I219-LM                                  | 1         | 1.09%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 1.09%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 1.09%   |
| Intel Ethernet Connection (16) I219-LM                                 | 1         | 1.09%   |
| Intel Ethernet Connection (11) I219-LM                                 | 1         | 1.09%   |
| Intel 82574L Gigabit Network Connection                                | 1         | 1.09%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 1.09%   |
| DisplayLink USB-C Triple-4K Dock                                       | 1         | 1.09%   |
| DisplayLink Plugable UD-ULTCDL                                         | 1         | 1.09%   |
| Broadcom Limited NetXtreme BCM57760 Gigabit Ethernet PCIe              | 1         | 1.09%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 102       | 52.58%  |
| Ethernet | 86        | 44.33%  |
| Modem    | 6         | 3.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 75        | 69.44%  |
| Ethernet | 33        | 30.56%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 76        | 73.79%  |
| 1     | 23        | 22.33%  |
| 3     | 3         | 2.91%   |
| 0     | 1         | 0.97%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 52        | 50.49%  |
| Yes  | 51        | 49.51%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 70        | 74.47%  |
| Realtek Semiconductor           | 5         | 5.32%   |
| Foxconn / Hon Hai               | 5         | 5.32%   |
| Apple                           | 5         | 5.32%   |
| IMC Networks                    | 2         | 2.13%   |
| Broadcom                        | 2         | 2.13%   |
| Qualcomm Atheros Communications | 1         | 1.06%   |
| MediaTek                        | 1         | 1.06%   |
| Dell                            | 1         | 1.06%   |
| Cambridge Silicon Radio         | 1         | 1.06%   |
| ASUSTek Computer                | 1         | 1.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                               | 24        | 25.53%  |
| Intel AX201 Bluetooth                               | 15        | 15.96%  |
| Intel Bluetooth Device                              | 13        | 13.83%  |
| Intel Bluetooth wireless interface                  | 12        | 12.77%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 3.19%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 3.19%   |
| Apple Bluetooth USB Host Controller                 | 3         | 3.19%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 2.13%   |
| Realtek Bluetooth Radio                             | 2         | 2.13%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 2.13%   |
| IMC Networks Bluetooth Radio                        | 2         | 2.13%   |
| Apple Bluetooth Host Controller                     | 2         | 2.13%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.06%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 1.06%   |
| MediaTek Wireless_Device                            | 1         | 1.06%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.06%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 1.06%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 1.06%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 1.06%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.06%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.06%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 1.06%   |
| ASUS ASUS USB-BT500                                 | 1         | 1.06%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 73        | 50%     |
| Nvidia                                 | 36        | 24.66%  |
| AMD                                    | 29        | 19.86%  |
| Lenovo                                 | 2         | 1.37%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.68%   |
| Razer USA                              | 1         | 0.68%   |
| Logitech                               | 1         | 0.68%   |
| Kingston Technology                    | 1         | 0.68%   |
| GN Netcom                              | 1         | 0.68%   |
| C-Media Electronics                    | 1         | 0.68%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 25        | 14.45%  |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 16        | 9.25%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9         | 5.2%    |
| Nvidia Audio device                                                        | 7         | 4.05%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 4.05%   |
| Nvidia GA106 High Definition Audio Controller                              | 6         | 3.47%   |
| Nvidia GA104 High Definition Audio Controller                              | 6         | 3.47%   |
| Nvidia TU116 High Definition Audio Controller                              | 5         | 2.89%   |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 2.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 2.89%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 2.31%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 2.31%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 2.31%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 2.31%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 2.31%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 1.73%   |
| Intel Raptor Lake High Definition Audio Controller                         | 3         | 1.73%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 1.73%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 1.73%   |
| Intel CM238 HD Audio Controller                                            | 3         | 1.73%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 1.73%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.73%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 3         | 1.73%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.16%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 1.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 1.16%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 1.16%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 2         | 1.16%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 1.16%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 1.16%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.16%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 1.16%   |
| Sony Ericsson Mobile Communications AB XQ-AU52                             | 1         | 0.58%   |
| Razer USA RC30-026902, Gaming Headset [Nari Essential, Wireless, Receiver] | 1         | 0.58%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.58%   |
| Logitech G430 Surround Sound Gaming Headset                                | 1         | 0.58%   |
| Lenovo USB Headset                                                         | 1         | 0.58%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                               | 1         | 0.58%   |
| Kingston Technology HyperX QuadCast S                                      | 1         | 0.58%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 1         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 15        | 41.67%  |
| SK hynix            | 10        | 27.78%  |
| Micron Technology   | 5         | 13.89%  |
| Unknown             | 3         | 8.33%   |
| Team                | 1         | 2.78%   |
| Elpida              | 1         | 2.78%   |
| ASint Technology    | 1         | 2.78%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 5         | 13.51%  |
| Unknown                                                          | 3         | 8.11%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 2         | 5.41%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 5.41%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 1         | 2.7%    |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 2.7%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 2.7%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.7%    |
| SK hynix RAM HMCG88AGBSA092N 32GB SODIMM 5600MT/s                | 1         | 2.7%    |
| SK hynix RAM HMCG78AGBSA092N 16GB SODIMM DDR5 5600MT/s           | 1         | 2.7%    |
| SK hynix RAM HMCG66AGBSA095N 8GB SODIMM DDR5 5600MT/s            | 1         | 2.7%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 2.7%    |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 2.7%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 2.7%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 2.7%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 2.7%    |
| Samsung RAM Module 3GB Row Of Chips LPDDR5 6400MT/s              | 1         | 2.7%    |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 2.7%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 2.7%    |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 2.7%    |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.7%    |
| Samsung RAM M425R4GA3BB0-CQKOL 32GB SODIMM DDR5 4800MT/s         | 1         | 2.7%    |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s          | 1         | 2.7%    |
| Micron RAM MT62F1G32D2DS-026 WT 2GB Row Of Chips LPDDR5 6400MT/s | 1         | 2.7%    |
| Micron RAM Module 2GB Row Of Chips LPDDR5 6400MT/s               | 1         | 2.7%    |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s             | 1         | 2.7%    |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 1         | 2.7%    |
| Elpida RAM EBJ21UE8BDS0-AE-F 2GB SODIMM DDR3 1067MT/s            | 1         | 2.7%    |
| ASint RAM SSZ302G08-GGNHC 2GB SODIMM DDR3 1600MT/s               | 1         | 2.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 17        | 53.13%  |
| LPDDR5 | 5         | 15.63%  |
| DDR5   | 5         | 15.63%  |
| DDR3   | 5         | 15.63%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 27        | 84.38%  |
| Row Of Chips | 5         | 15.63%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 11        | 31.43%  |
| 32768 | 8         | 22.86%  |
| 16384 | 7         | 20%     |
| 4096  | 4         | 11.43%  |
| 2048  | 4         | 11.43%  |
| 3072  | 1         | 2.86%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 12        | 35.29%  |
| 6400  | 5         | 14.71%  |
| 1600  | 4         | 11.76%  |
| 5600  | 3         | 8.82%   |
| 2667  | 3         | 8.82%   |
| 8400  | 2         | 5.88%   |
| 4800  | 2         | 5.88%   |
| 2400  | 1         | 2.94%   |
| 2133  | 1         | 2.94%   |
| 1067  | 1         | 2.94%   |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 43        | 48.86%  |
| Bison Electronics                      | 9         | 10.23%  |
| Microdia                               | 6         | 6.82%   |
| Suyin                                  | 3         | 3.41%   |
| IMC Networks                           | 3         | 3.41%   |
| Apple                                  | 3         | 3.41%   |
| Acer                                   | 3         | 3.41%   |
| Sunplus Innovation Technology          | 2         | 2.27%   |
| Realtek Semiconductor                  | 2         | 2.27%   |
| Logitech                               | 2         | 2.27%   |
| Lite-On Technology                     | 2         | 2.27%   |
| Unknown                                | 1         | 1.14%   |
| Syntek                                 | 1         | 1.14%   |
| Silicon Motion                         | 1         | 1.14%   |
| Ricoh                                  | 1         | 1.14%   |
| Luxvisions Innotech Limited            | 1         | 1.14%   |
| Importek                               | 1         | 1.14%   |
| HYGD-220831-A                          | 1         | 1.14%   |
| Generalplus Technology                 | 1         | 1.14%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.14%   |
| Alpha Imaging Technology               | 1         | 1.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony HD Webcam                                    | 13        | 14.77%  |
| Chicony FHD Webcam                                   | 9         | 10.23%  |
| Chicony USB2.0 Camera                                | 7         | 7.95%   |
| Bison BisonCam,NB Pro                                | 4         | 4.55%   |
| IMC Networks Integrated Camera                       | 3         | 3.41%   |
| Chicony Integrated Camera                            | 3         | 3.41%   |
| Apple FaceTime HD Camera                             | 3         | 3.41%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 2         | 2.27%   |
| Microdia Integrated_Webcam_FHD                       | 2         | 2.27%   |
| Chicony ACER HD User Facing                          | 2         | 2.27%   |
| Bison Lenovo EasyCamera                              | 2         | 2.27%   |
| Acer HD Webcam                                       | 2         | 2.27%   |
| Unknown HD camera                                    | 1         | 1.14%   |
| Syntek Integrated Camera                             | 1         | 1.14%   |
| Suyin RGBIR Camera                                   | 1         | 1.14%   |
| Suyin Integrated_Webcam_HD                           | 1         | 1.14%   |
| Suyin HP TrueVision HD                               | 1         | 1.14%   |
| Sunplus Integrated_Webcam_HD                         | 1         | 1.14%   |
| Sunplus Asus Webcam                                  | 1         | 1.14%   |
| Silicon Motion WebCam SCB-1100N                      | 1         | 1.14%   |
| Ricoh Laptop_Integrated_Webcam_FHD                   | 1         | 1.14%   |
| Realtek Integrated Webcam                            | 1         | 1.14%   |
| Realtek HP Wide Vision HD Camera                     | 1         | 1.14%   |
| Microdia Laptop_Integrated_Webcam_E4HD               | 1         | 1.14%   |
| Microdia Integrated_Webcam_HD                        | 1         | 1.14%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.14%   |
| Logitech BRIO Ultra HD Webcam                        | 1         | 1.14%   |
| Logitech Brio 500                                    | 1         | 1.14%   |
| Lite-On Integrated Camera                            | 1         | 1.14%   |
| Lite-On HP Webcam                                    | 1         | 1.14%   |
| Importek HP Webcam                                   | 1         | 1.14%   |
| HYGD-220831-A Hy-Usb2.0-1*MIC                        | 1         | 1.14%   |
| Generalplus GENERAL WEBCAM                           | 1         | 1.14%   |
| Chicony USB2.0 HD UVC WebCam                         | 1         | 1.14%   |
| Chicony USB 2.0 Camera                               | 1         | 1.14%   |
| Chicony ThinkPad T490 Webcam                         | 1         | 1.14%   |
| Chicony HP TrueVision HD Camera                      | 1         | 1.14%   |
| Chicony HP Truevision HD                             | 1         | 1.14%   |
| Chicony HP HD Camera                                 | 1         | 1.14%   |
| Chicony FJ Camera                                    | 1         | 1.14%   |

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
| 0     | 59        | 57.28%  |
| 1     | 42        | 40.78%  |
| 3     | 1         | 0.97%   |
| 2     | 1         | 0.97%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 18        | 37.5%   |
| Multimedia controller | 14        | 29.17%  |
| Chipcard              | 7         | 14.58%  |
| Graphics card         | 5         | 10.42%  |
| Net/wireless          | 2         | 4.17%   |
| Modem                 | 1         | 2.08%   |
| Card reader           | 1         | 2.08%   |


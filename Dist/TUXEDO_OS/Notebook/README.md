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

Total: 184

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Schenker      | VISION 16 Pro (L22)         | [c54f918726](https://linux-hardware.org/?probe=c54f918726) | May 08, 2024 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [bc9db74da3](https://linux-hardware.org/?probe=bc9db74da3) | May 07, 2024 |
| TUXEDO        | Sirius 16 Gen1              | [b093c73dcb](https://linux-hardware.org/?probe=b093c73dcb) | May 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [8a0a1ade7b](https://linux-hardware.org/?probe=8a0a1ade7b) | May 04, 2024 |
| ASUSTek       | N71Vn                       | [6f38bd6250](https://linux-hardware.org/?probe=6f38bd6250) | May 03, 2024 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [ad5d8cbdf2](https://linux-hardware.org/?probe=ad5d8cbdf2) | May 03, 2024 |
| TUXEDO        | Aura 15 Gen2                | [93d15c44da](https://linux-hardware.org/?probe=93d15c44da) | May 02, 2024 |
| ASUSTek       | N71Vn                       | [d5d1d55df1](https://linux-hardware.org/?probe=d5d1d55df1) | May 01, 2024 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [290ff65bc7](https://linux-hardware.org/?probe=290ff65bc7) | Apr 30, 2024 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [f6d6805396](https://linux-hardware.org/?probe=f6d6805396) | Apr 27, 2024 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [be0672ea72](https://linux-hardware.org/?probe=be0672ea72) | Apr 21, 2024 |
| HP            | ProBook 4540s               | [b13d3be380](https://linux-hardware.org/?probe=b13d3be380) | Apr 21, 2024 |
| TUXEDO        | Stellaris/Polaris AMD Ge... | [bb18adad6a](https://linux-hardware.org/?probe=bb18adad6a) | Apr 19, 2024 |
| Toshiba       | PORTEGE Z10T-A              | [8ed3e0a790](https://linux-hardware.org/?probe=8ed3e0a790) | Apr 16, 2024 |
| Dell          | Latitude 5430               | [5f23ced920](https://linux-hardware.org/?probe=5f23ced920) | Apr 16, 2024 |
| HP            | 250 G7 Notebook PC          | [714eb8d9ea](https://linux-hardware.org/?probe=714eb8d9ea) | Apr 16, 2024 |
| TUXEDO        | Sirius 16 Gen1              | [6b5703bf76](https://linux-hardware.org/?probe=6b5703bf76) | Apr 14, 2024 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [918934ed68](https://linux-hardware.org/?probe=918934ed68) | Apr 11, 2024 |
| TUXEDO        | Sirius 16 Gen1              | [d8b9d651e3](https://linux-hardware.org/?probe=d8b9d651e3) | Apr 11, 2024 |
| Apple         | MacBookPro12,1              | [0e37beebd4](https://linux-hardware.org/?probe=0e37beebd4) | Apr 05, 2024 |
| Apple         | MacBookPro12,1              | [2c20f368e3](https://linux-hardware.org/?probe=2c20f368e3) | Apr 05, 2024 |
| TUXEDO        | Polaris AMD Gen5            | [352afa7567](https://linux-hardware.org/?probe=352afa7567) | Apr 04, 2024 |
| MSI           | Vector GP78HX 13VG          | [74268fafe5](https://linux-hardware.org/?probe=74268fafe5) | Mar 31, 2024 |
| Apple         | MacBook5,1                  | [0b7838f79e](https://linux-hardware.org/?probe=0b7838f79e) | Mar 26, 2024 |
| Dell          | Latitude E6420              | [cdd8eb657a](https://linux-hardware.org/?probe=cdd8eb657a) | Mar 22, 2024 |
| Apple         | MacBookPro11,2              | [247c0bdfb3](https://linux-hardware.org/?probe=247c0bdfb3) | Mar 21, 2024 |
| HP            | Pavilion 15                 | [a9bc9facce](https://linux-hardware.org/?probe=a9bc9facce) | Mar 19, 2024 |
| HP            | Pavilion Power Laptop 15... | [8529154b4a](https://linux-hardware.org/?probe=8529154b4a) | Mar 15, 2024 |
| Lenovo        | Yoga 700-11ISK 80QE         | [a0a622a966](https://linux-hardware.org/?probe=a0a622a966) | Mar 14, 2024 |
| Dell          | Latitude 7480               | [13613ddbb8](https://linux-hardware.org/?probe=13613ddbb8) | Mar 14, 2024 |
| TUXEDO        | Pulse 15 Gen1               | [106f4fd286](https://linux-hardware.org/?probe=106f4fd286) | Mar 13, 2024 |
| MSI           | Modern 15 H B13M            | [31bba1378f](https://linux-hardware.org/?probe=31bba1378f) | Mar 11, 2024 |
| MSI           | GF75 Thin 10SC              | [a415956dc4](https://linux-hardware.org/?probe=a415956dc4) | Mar 10, 2024 |
| ASUSTek       | X555LJ                      | [72da032893](https://linux-hardware.org/?probe=72da032893) | Mar 09, 2024 |
| HP            | Pavilion g7                 | [10e05bd9bc](https://linux-hardware.org/?probe=10e05bd9bc) | Mar 08, 2024 |
| MSI           | Modern 15 H B13M            | [a1ac91ddf1](https://linux-hardware.org/?probe=a1ac91ddf1) | Mar 02, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [e809fe3bcd](https://linux-hardware.org/?probe=e809fe3bcd) | Feb 29, 2024 |
| Toshiba       | Satellite A665              | [2a3093ba09](https://linux-hardware.org/?probe=2a3093ba09) | Feb 29, 2024 |
| TUXEDO        | Sirius 16 Gen1              | [76659ee758](https://linux-hardware.org/?probe=76659ee758) | Feb 25, 2024 |
| Wortmann      | 1220595_1470122             | [8f49189b79](https://linux-hardware.org/?probe=8f49189b79) | Feb 24, 2024 |
| TUXEDO        | Sirius 16 Gen1              | [44b101b616](https://linux-hardware.org/?probe=44b101b616) | Feb 14, 2024 |
| TUXEDO        | XP1610                      | [520e2a82de](https://linux-hardware.org/?probe=520e2a82de) | Feb 12, 2024 |
| TUXEDO        | InfinityBook Pro Gen8 (M... | [d3fc4417ee](https://linux-hardware.org/?probe=d3fc4417ee) | Feb 12, 2024 |
| TUXEDO        | Unknown                     | [9e4e88d13e](https://linux-hardware.org/?probe=9e4e88d13e) | Feb 11, 2024 |
| TUXEDO        | Book XP15 / XP17 Gen12      | [e8784ff987](https://linux-hardware.org/?probe=e8784ff987) | Feb 09, 2024 |
| TUXEDO        | InfinityBook S Gen8         | [8dddfa59a5](https://linux-hardware.org/?probe=8dddfa59a5) | Feb 09, 2024 |
| HP            | Pavilion Notebook           | [81424087b4](https://linux-hardware.org/?probe=81424087b4) | Feb 06, 2024 |
| HP            | Pavilion Notebook           | [9305000cc3](https://linux-hardware.org/?probe=9305000cc3) | Feb 06, 2024 |
| HP            | 250 G3                      | [3302706a4e](https://linux-hardware.org/?probe=3302706a4e) | Feb 05, 2024 |
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
| TUXEDO OS 22.04 | 142       | 100%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| TUXEDO OS | 142       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 6.5.0-10022-tuxedo   | 17        | 11.04%  |
| 6.1.0-1009-tuxedo    | 13        | 8.44%   |
| 6.5.0-10027-tuxedo   | 12        | 7.79%   |
| 6.2.0-10022-tuxedo   | 11        | 7.14%   |
| 6.2.0-10018-tuxedo   | 10        | 6.49%   |
| 6.2.0-10005-tuxedo   | 9         | 5.84%   |
| 6.2.0-10011-tuxedo   | 8         | 5.19%   |
| 6.2.0-10007-tuxedo   | 8         | 5.19%   |
| 6.5.0-10036-tuxedo   | 7         | 4.55%   |
| 6.5.0-10008-tuxedo   | 7         | 4.55%   |
| 6.5.0-10010-tuxedo   | 6         | 3.9%    |
| 6.2.0-10010-tuxedo   | 6         | 3.9%    |
| 6.5.0-10031-tuxedo   | 5         | 3.25%   |
| 6.5.0-10013-tuxedo   | 5         | 3.25%   |
| 6.5.0-10006-tuxedo   | 5         | 3.25%   |
| 5.15.0-10058-tuxedo  | 4         | 2.6%    |
| 5.15.0-10048-tuxedo  | 4         | 2.6%    |
| 6.2.0-10027-tuxedo   | 3         | 1.95%   |
| 5.15.0-10053-tuxedo  | 3         | 1.95%   |
| 5.15.0-10052-tuxedo  | 3         | 1.95%   |
| 5.15.0-10050-tuxedo  | 2         | 1.3%    |
| 6.5.4-060504-generic | 1         | 0.65%   |
| 6.5.0-1014-oem       | 1         | 0.65%   |
| 6.2.0-10014-tuxedo   | 1         | 0.65%   |
| 6.0.0-1010-oem       | 1         | 0.65%   |
| 5.15.0-10057-tuxedo  | 1         | 0.65%   |
| 5.15.0-10056-tuxedo  | 1         | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.5.0   | 62        | 41.06%  |
| 6.2.0   | 56        | 37.09%  |
| 5.15.0  | 18        | 11.92%  |
| 6.1.0   | 13        | 8.61%   |
| 6.5.4   | 1         | 0.66%   |
| 6.0.0   | 1         | 0.66%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.5     | 63        | 41.72%  |
| 6.2     | 56        | 37.09%  |
| 5.15    | 18        | 11.92%  |
| 6.1     | 13        | 8.61%   |
| 6.0     | 1         | 0.66%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 142       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| KDE5 | 136       | 95.77%  |
| KDE6 | 6         | 4.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 136       | 94.44%  |
| Wayland | 8         | 5.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 103       | 71.53%  |
| SDDM    | 41        | 28.47%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| de_DE | 53        | 37.32%  |
| en_US | 42        | 29.58%  |
| en_GB | 13        | 9.15%   |
| it_IT | 6         | 4.23%   |
| fr_FR | 3         | 2.11%   |
| en_AU | 3         | 2.11%   |
| pt_PT | 2         | 1.41%   |
| pl_PL | 2         | 1.41%   |
| nb_NO | 2         | 1.41%   |
| hu_HU | 2         | 1.41%   |
| en_CA | 2         | 1.41%   |
| en_AG | 2         | 1.41%   |
| tr_TR | 1         | 0.7%    |
| pt_BR | 1         | 0.7%    |
| fi_FI | 1         | 0.7%    |
| et_EE | 1         | 0.7%    |
| es_ES | 1         | 0.7%    |
| en_ZA | 1         | 0.7%    |
| en_IN | 1         | 0.7%    |
| en_DK | 1         | 0.7%    |
| da_DK | 1         | 0.7%    |
| cs_CZ | 1         | 0.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 107       | 74.83%  |
| EFI  | 36        | 25.17%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 122       | 85.92%  |
| Btrfs   | 11        | 7.75%   |
| Overlay | 5         | 3.52%   |
| Tmpfs   | 4         | 2.82%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 103       | 71.53%  |
| GPT     | 38        | 26.39%  |
| MBR     | 3         | 2.08%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 136       | 95.1%   |
| Yes       | 7         | 4.9%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 134       | 93.71%  |
| Yes       | 9         | 6.29%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| TUXEDO              | 52        | 36.62%  |
| Lenovo              | 20        | 14.08%  |
| Hewlett-Packard     | 17        | 11.97%  |
| Dell                | 15        | 10.56%  |
| Apple               | 8         | 5.63%   |
| ASUSTek Computer    | 7         | 4.93%   |
| MSI                 | 5         | 3.52%   |
| Acer                | 5         | 3.52%   |
| Toshiba             | 2         | 1.41%   |
| Schenker            | 2         | 1.41%   |
| Notebook            | 2         | 1.41%   |
| Wortmann AG         | 1         | 0.7%    |
| Samsung Electronics | 1         | 0.7%    |
| Metabox             | 1         | 0.7%    |
| Fujitsu             | 1         | 0.7%    |
| Chuwi               | 1         | 0.7%    |
| BESSTAR Tech        | 1         | 0.7%    |
| Unknown             | 1         | 0.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Notebooks | Percent |
|------------------------------------|-----------|---------|
| TUXEDO Sirius 16 Gen1              | 4         | 2.82%   |
| TUXEDO InfinityBook S 15/17 Gen7   | 4         | 2.82%   |
| TUXEDO InfinityBook Pro 14 Gen6    | 4         | 2.82%   |
| Unknown                            | 4         | 2.82%   |
| TUXEDO Stellaris/Polaris AMD Gen4  | 3         | 2.11%   |
| TUXEDO Stellaris Intel Gen5        | 3         | 2.11%   |
| TUXEDO Pulse 15 Gen1               | 3         | 2.11%   |
| TUXEDO InfinityBook Pro Gen7 (MK1) | 3         | 2.11%   |
| TUXEDO Aura 15 Gen2                | 3         | 2.11%   |
| TUXEDO XMG FUSION 15 (XFU15L19)    | 2         | 1.41%   |
| TUXEDO Pulse 15 Gen2               | 2         | 1.41%   |
| TUXEDO Polaris AMD Gen5            | 2         | 1.41%   |
| TUXEDO Polaris 15 AMD Gen1         | 2         | 1.41%   |
| TUXEDO InfinityBook S 15 Gen6      | 2         | 1.41%   |
| TUXEDO InfinityBook Pro Gen7 (MK2) | 2         | 1.41%   |
| Dell Latitude E6540                | 2         | 1.41%   |
| Apple MacBookPro8,1                | 2         | 1.41%   |
| Wortmann AG 1220595_1470122        | 1         | 0.7%    |
| TUXEDO XP1610                      | 1         | 0.7%    |
| TUXEDO Stellaris AMD Gen3 (CZN)    | 1         | 0.7%    |
| TUXEDO Polaris AMD Gen3 (CZN)      | 1         | 0.7%    |
| TUXEDO P64_HJ,HK1                  | 1         | 0.7%    |
| TUXEDO N7x0WU                      | 1         | 0.7%    |
| TUXEDO N13xWU                      | 1         | 0.7%    |
| TUXEDO InfinityBook S Gen8         | 1         | 0.7%    |
| TUXEDO InfinityBook Pro Gen8 (MK1) | 1         | 0.7%    |
| TUXEDO Book XUX7 Gen13             | 1         | 0.7%    |
| TUXEDO Book XP15 / XP17 Gen12      | 1         | 0.7%    |
| Toshiba Satellite A665             | 1         | 0.7%    |
| Toshiba PORTEGE Z10T-A             | 1         | 0.7%    |
| Schenker VISION 16 Pro (L22)       | 1         | 0.7%    |
| Schenker VISION 15 E23 (SVS15E23)  | 1         | 0.7%    |
| Samsung RC530/RC730                | 1         | 0.7%    |
| Notebook W65_W67RB                 | 1         | 0.7%    |
| Notebook NP5x_NP6x_NP7xHP          | 1         | 0.7%    |
| MSI Vector GP78HX 13VG             | 1         | 0.7%    |
| MSI Prestige 15 A10SC              | 1         | 0.7%    |
| MSI Modern 15 H B13M               | 1         | 0.7%    |
| MSI GF75 Thin 10SC                 | 1         | 0.7%    |
| MSI GE75 Raider 10SF               | 1         | 0.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| TUXEDO InfinityBook | 17        | 11.97%  |
| Lenovo ThinkPad     | 10        | 7.04%   |
| TUXEDO Stellaris    | 7         | 4.93%   |
| Dell Latitude       | 7         | 4.93%   |
| HP Pavilion         | 6         | 4.23%   |
| TUXEDO Pulse        | 5         | 3.52%   |
| TUXEDO Polaris      | 5         | 3.52%   |
| TUXEDO Sirius       | 4         | 2.82%   |
| Unknown             | 4         | 2.82%   |
| TUXEDO Aura         | 3         | 2.11%   |
| HP Laptop           | 3         | 2.11%   |
| Dell Precision      | 3         | 2.11%   |
| Dell Inspiron       | 3         | 2.11%   |
| TUXEDO XMG          | 2         | 1.41%   |
| TUXEDO Book         | 2         | 1.41%   |
| Schenker VISION     | 2         | 1.41%   |
| Lenovo Yoga         | 2         | 1.41%   |
| Lenovo ThinkBook    | 2         | 1.41%   |
| Lenovo Legion       | 2         | 1.41%   |
| Lenovo IdeaPad      | 2         | 1.41%   |
| HP EliteBook        | 2         | 1.41%   |
| HP 250              | 2         | 1.41%   |
| Apple MacBookPro8   | 2         | 1.41%   |
| Acer Swift          | 2         | 1.41%   |
| Acer Nitro          | 2         | 1.41%   |
| Wortmann AG 1220595 | 1         | 0.7%    |
| TUXEDO XP1610       | 1         | 0.7%    |
| TUXEDO P64          | 1         | 0.7%    |
| TUXEDO N7x0WU       | 1         | 0.7%    |
| TUXEDO N13xWU       | 1         | 0.7%    |
| Toshiba Satellite   | 1         | 0.7%    |
| Toshiba PORTEGE     | 1         | 0.7%    |
| Samsung RC530       | 1         | 0.7%    |
| Notebook W65        | 1         | 0.7%    |
| Notebook NP5x       | 1         | 0.7%    |
| MSI Vector          | 1         | 0.7%    |
| MSI Prestige        | 1         | 0.7%    |
| MSI Modern          | 1         | 0.7%    |
| MSI GF75            | 1         | 0.7%    |
| MSI GE75            | 1         | 0.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2022 | 28        | 19.72%  |
| 2020 | 18        | 12.68%  |
| 2023 | 17        | 11.97%  |
| 2015 | 12        | 8.45%   |
| 2021 | 11        | 7.75%   |
| 2019 | 10        | 7.04%   |
| 2017 | 9         | 6.34%   |
| 2012 | 7         | 4.93%   |
| 2013 | 6         | 4.23%   |
| 2011 | 6         | 4.23%   |
| 2024 | 4         | 2.82%   |
| 2018 | 3         | 2.11%   |
| 2014 | 3         | 2.11%   |
| 2009 | 3         | 2.11%   |
| 2010 | 2         | 1.41%   |
| 2008 | 2         | 1.41%   |
| 2007 | 1         | 0.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 142       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 142       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 142       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 33        | 23.24%  |
| 16.01-24.0  | 30        | 21.13%  |
| 4.01-8.0    | 24        | 16.9%   |
| 8.01-16.0   | 22        | 15.49%  |
| 64.01-256.0 | 17        | 11.97%  |
| 3.01-4.0    | 10        | 7.04%   |
| 24.01-32.0  | 6         | 4.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 45        | 30%     |
| 2.01-3.0   | 38        | 25.33%  |
| 1.01-2.0   | 29        | 19.33%  |
| 3.01-4.0   | 22        | 14.67%  |
| 8.01-16.0  | 13        | 8.67%   |
| 16.01-24.0 | 3         | 2%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 92        | 64.34%  |
| 2      | 42        | 29.37%  |
| 3      | 7         | 4.9%    |
| 4      | 1         | 0.7%    |
| 0      | 1         | 0.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 115       | 80.99%  |
| Yes       | 27        | 19.01%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 121       | 85.21%  |
| No        | 21        | 14.79%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 141       | 99.3%   |
| No        | 1         | 0.7%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 130       | 91.55%  |
| No        | 12        | 8.45%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Notebooks | Percent |
|------------------------|-----------|---------|
| Germany                | 60        | 42.25%  |
| USA                    | 22        | 15.49%  |
| UK                     | 5         | 3.52%   |
| Italy                  | 5         | 3.52%   |
| Turkey                 | 4         | 2.82%   |
| Portugal               | 4         | 2.82%   |
| France                 | 4         | 2.82%   |
| Switzerland            | 3         | 2.11%   |
| Czechia                | 3         | 2.11%   |
| Australia              | 3         | 2.11%   |
| Spain                  | 2         | 1.41%   |
| Poland                 | 2         | 1.41%   |
| Norway                 | 2         | 1.41%   |
| Indonesia              | 2         | 1.41%   |
| Hungary                | 2         | 1.41%   |
| Denmark                | 2         | 1.41%   |
| Brazil                 | 2         | 1.41%   |
| Austria                | 2         | 1.41%   |
| Tunisia                | 1         | 0.7%    |
| South Africa           | 1         | 0.7%    |
| Slovakia               | 1         | 0.7%    |
| Romania                | 1         | 0.7%    |
| Panama                 | 1         | 0.7%    |
| Netherlands            | 1         | 0.7%    |
| India                  | 1         | 0.7%    |
| Finland                | 1         | 0.7%    |
| Estonia                | 1         | 0.7%    |
| Canada                 | 1         | 0.7%    |
| Bulgaria               | 1         | 0.7%    |
| Bosnia and Herzegovina | 1         | 0.7%    |
| Belgium                | 1         | 0.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Munich             | 7         | 4.86%   |
| Prague             | 3         | 2.08%   |
| Berlin             | 3         | 2.08%   |
| Wolfsburg          | 2         | 1.39%   |
| Vienna             | 2         | 1.39%   |
| Schweinfurt        | 2         | 1.39%   |
| Rome               | 2         | 1.39%   |
| Nuremberg          | 2         | 1.39%   |
| Lucerne            | 2         | 1.39%   |
| Los Angeles        | 2         | 1.39%   |
| Langevag           | 2         | 1.39%   |
| Kiel               | 2         | 1.39%   |
| Jakarta            | 2         | 1.39%   |
| Istanbul           | 2         | 1.39%   |
| Hamburg            | 2         | 1.39%   |
| Duisburg           | 2         | 1.39%   |
| Brisbane           | 2         | 1.39%   |
| Astoria            | 2         | 1.39%   |
| Zurich             | 1         | 0.69%   |
| Zonguldak          | 1         | 0.69%   |
| Zabrze             | 1         | 0.69%   |
| Wunstorf           | 1         | 0.69%   |
| Wembley            | 1         | 0.69%   |
| Watertown          | 1         | 0.69%   |
| Warsaw             | 1         | 0.69%   |
| Walsall            | 1         | 0.69%   |
| Venlo              | 1         | 0.69%   |
| Vallejo            | 1         | 0.69%   |
| Turin              | 1         | 0.69%   |
| Teslic             | 1         | 0.69%   |
| Tallinn            | 1         | 0.69%   |
| Stuttgart          | 1         | 0.69%   |
| Stockstadt am Main | 1         | 0.69%   |
| Sousse             | 1         | 0.69%   |
| Solymar            | 1         | 0.69%   |
| Solingen           | 1         | 0.69%   |
| Sistov             | 1         | 0.69%   |
| Sinsheim           | 1         | 0.69%   |
| Seyhan             | 1         | 0.69%   |
| Seattle            | 1         | 0.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 71        | 100    | 40.11%  |
| Sandisk                     | 14        | 16     | 7.91%   |
| Seagate                     | 11        | 12     | 6.21%   |
| Kingston                    | 10        | 10     | 5.65%   |
| Toshiba                     | 8         | 9      | 4.52%   |
| Micron Technology           | 7         | 8      | 3.95%   |
| WDC                         | 5         | 5      | 2.82%   |
| Unknown                     | 5         | 5      | 2.82%   |
| SK hynix                    | 5         | 6      | 2.82%   |
| Hitachi                     | 4         | 6      | 2.26%   |
| Apple                       | 4         | 4      | 2.26%   |
| Micron/Crucial Technology   | 3         | 3      | 1.69%   |
| Intel                       | 3         | 3      | 1.69%   |
| Crucial                     | 3         | 3      | 1.69%   |
| SPCC                        | 2         | 2      | 1.13%   |
| Phison Electronics          | 2         | 2      | 1.13%   |
| HGST                        | 2         | 3      | 1.13%   |
| USB3.0                      | 1         | 1      | 0.56%   |
| Transcend                   | 1         | 1      | 0.56%   |
| Team                        | 1         | 1      | 0.56%   |
| S3+                         | 1         | 1      | 0.56%   |
| Phison                      | 1         | 3      | 0.56%   |
| OWC                         | 1         | 1      | 0.56%   |
| Netac                       | 1         | 1      | 0.56%   |
| LITEONIT                    | 1         | 1      | 0.56%   |
| Lexar                       | 1         | 1      | 0.56%   |
| Lenovo                      | 1         | 1      | 0.56%   |
| KIOXIA                      | 1         | 1      | 0.56%   |
| Kingston Technology Company | 1         | 1      | 0.56%   |
| Kingchuxing                 | 1         | 1      | 0.56%   |
| Intenso                     | 1         | 1      | 0.56%   |
| Fanxiang                    | 1         | 1      | 0.56%   |
| CT1000BX                    | 1         | 1      | 0.56%   |
| ASMedia                     | 1         | 2      | 0.56%   |
| ADATA Technology            | 1         | 1      | 0.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 13        | 6.99%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 13        | 6.99%   |
| Samsung SSD 980 1TB                                | 11        | 5.91%   |
| Samsung SSD 980 500GB                              | 6         | 3.23%   |
| Kingston SA400S37240G 240GB SSD                    | 4         | 2.15%   |
| Sandisk WD Blue SN570 1TB                          | 3         | 1.61%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB   | 3         | 1.61%   |
| Samsung SSD 990 PRO 1TB                            | 3         | 1.61%   |
| Samsung SSD 980 PRO 1TB                            | 3         | 1.61%   |
| Samsung SSD 970 EVO Plus 1TB                       | 3         | 1.61%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                | 3         | 1.61%   |
| Toshiba MQ01ABD100 1TB                             | 2         | 1.08%   |
| SanDisk SDSSDA240G 240GB                           | 2         | 1.08%   |
| Samsung SSD 980 PRO 500GB                          | 2         | 1.08%   |
| Samsung SSD 980 PRO 2TB                            | 2         | 1.08%   |
| Samsung SSD 850 EVO 1TB                            | 2         | 1.08%   |
| Hitachi HTS727550A9E364 500GB                      | 2         | 1.08%   |
| Apple SSD SM0512G 500GB                            | 2         | 1.08%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                   | 1         | 0.54%   |
| WDC WD3200BPVT-24JJ5T0 320GB                       | 1         | 0.54%   |
| WDC WD10JPVX-22JC3T0 1TB                           | 1         | 0.54%   |
| WDC WD Elements SE SSD 1TB                         | 1         | 0.54%   |
| WDC PC SA530 SDASN8Y-256G-1006 256GB SSD           | 1         | 0.54%   |
| USB3.0 Super Speed 240GB                           | 1         | 0.54%   |
| Unknown MMC Card  64GB                             | 1         | 0.54%   |
| Unknown MMC Card  512GB                            | 1         | 0.54%   |
| Unknown MMC Card  2GB                              | 1         | 0.54%   |
| Unknown MMC Card  256GB                            | 1         | 0.54%   |
| Unknown MMC Card  249GB                            | 1         | 0.54%   |
| Transcend TS512GSSD230S 512GB                      | 1         | 0.54%   |
| Toshiba XG4 NVMe SSD Controller 512GB              | 1         | 0.54%   |
| Toshiba THNSNJ128GMCU 128GB SSD                    | 1         | 0.54%   |
| Toshiba MQ01ABF050 500GB                           | 1         | 0.54%   |
| Toshiba MK3261GSYN 320GB                           | 1         | 0.54%   |
| Toshiba KXG50ZNV512G NVMe 512GB                    | 1         | 0.54%   |
| Toshiba BG3 NVMe SSD Controller 128GB              | 1         | 0.54%   |
| Team T2531TB SSD                                   | 1         | 0.54%   |
| SPCC M.2 SSD 256GB                                 | 1         | 0.54%   |
| SPCC M.2 PCIe SSD 1TB                              | 1         | 0.54%   |
| SK hynix SKHynix_HFS512GEJ4X112N 512GB             | 1         | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 10        | 11     | 45.45%  |
| Toshiba | 4         | 4      | 18.18%  |
| Hitachi | 4         | 6      | 18.18%  |
| WDC     | 2         | 2      | 9.09%   |
| HGST    | 2         | 3      | 9.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 12     | 24.44%  |
| Kingston            | 6         | 6      | 13.33%  |
| SanDisk             | 4         | 4      | 8.89%   |
| Apple               | 4         | 4      | 8.89%   |
| WDC                 | 3         | 3      | 6.67%   |
| Crucial             | 3         | 3      | 6.67%   |
| USB3.0              | 1         | 1      | 2.22%   |
| Transcend           | 1         | 1      | 2.22%   |
| Toshiba             | 1         | 1      | 2.22%   |
| Team                | 1         | 1      | 2.22%   |
| SPCC                | 1         | 1      | 2.22%   |
| SK hynix            | 1         | 2      | 2.22%   |
| S3+                 | 1         | 1      | 2.22%   |
| OWC                 | 1         | 1      | 2.22%   |
| Netac               | 1         | 1      | 2.22%   |
| Micron Technology   | 1         | 1      | 2.22%   |
| LITEONIT            | 1         | 1      | 2.22%   |
| Lexar               | 1         | 1      | 2.22%   |
| Intenso             | 1         | 1      | 2.22%   |
| CT1000BX            | 1         | 1      | 2.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 95        | 137    | 57.58%  |
| SSD     | 41        | 47     | 24.85%  |
| HDD     | 22        | 26     | 13.33%  |
| MMC     | 5         | 5      | 3.03%   |
| Unknown | 2         | 3      | 1.21%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 95        | 137    | 57.93%  |
| SATA | 57        | 68     | 34.76%  |
| SAS  | 7         | 8      | 4.27%   |
| MMC  | 5         | 5      | 3.05%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 40        | 47     | 62.5%   |
| 0.51-1.0   | 20        | 22     | 31.25%  |
| 1.01-2.0   | 3         | 3      | 4.69%   |
| 4.01-10.0  | 1         | 1      | 1.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 35        | 24.48%  |
| 251-500        | 32        | 22.38%  |
| 101-250        | 29        | 20.28%  |
| 1001-2000      | 21        | 14.69%  |
| 1-20           | 9         | 6.29%   |
| 2001-3000      | 7         | 4.9%    |
| More than 3000 | 3         | 2.1%    |
| 51-100         | 3         | 2.1%    |
| Unknown        | 3         | 2.1%    |
| 21-50          | 1         | 0.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 48        | 32.65%  |
| 21-50     | 38        | 25.85%  |
| 101-250   | 23        | 15.65%  |
| 51-100    | 11        | 7.48%   |
| 251-500   | 10        | 6.8%    |
| 501-1000  | 10        | 6.8%    |
| 1001-2000 | 4         | 2.72%   |
| Unknown   | 3         | 2.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| WDC PC SA530 SDASN8Y-256G-1006 256GB SSD | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1         | 1      | 100%    |

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
| Detected | 104       | 167    | 72.22%  |
| Works    | 39        | 50     | 27.08%  |
| Malfunc  | 1         | 1      | 0.69%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 64        | 34.41%  |
| Intel                        | 63        | 33.87%  |
| AMD                          | 17        | 9.14%   |
| SanDisk                      | 10        | 5.38%   |
| Micron Technology            | 6         | 3.23%   |
| Kingston Technology Company  | 5         | 2.69%   |
| SK hynix                     | 4         | 2.15%   |
| Toshiba America Info Systems | 3         | 1.61%   |
| Phison Electronics           | 3         | 1.61%   |
| Micron/Crucial Technology    | 3         | 1.61%   |
| Silicon Motion               | 1         | 0.54%   |
| Seagate Technology           | 1         | 0.54%   |
| Nvidia                       | 1         | 0.54%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.54%   |
| Marvell Technology Group     | 1         | 0.54%   |
| Lenovo                       | 1         | 0.54%   |
| KIOXIA                       | 1         | 0.54%   |
| ADATA Technology             | 1         | 0.54%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller 980 (DRAM-less)                                   | 21        | 10.66%  |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 19        | 9.64%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 18        | 9.14%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 16        | 8.12%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 8         | 4.06%   |
| Intel Volume Management Device NVMe RAID Controller                           | 7         | 3.55%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 5         | 2.54%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 5         | 2.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 5         | 2.54%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                         | 4         | 2.03%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 4         | 2.03%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 4         | 2.03%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD          | 3         | 1.52%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                    | 3         | 1.52%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                   | 3         | 1.52%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)          | 3         | 1.52%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 3         | 1.52%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 3         | 1.52%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                          | 3         | 1.52%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                          | 2         | 1.02%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 2         | 1.02%   |
| Micron 3400 NVMe SSD [Hendrix]                                                | 2         | 1.02%   |
| Micron 2400 NVMe SSD (DRAM-less)                                              | 2         | 1.02%   |
| Kingston Company NV1 NVMe SSD SM2263XT (DRAM-less)                            | 2         | 1.02%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation         | 2         | 1.02%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 2         | 1.02%   |
| Intel Alder Lake-P SATA AHCI Controller                                       | 2         | 1.02%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]         | 2         | 1.02%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                          | 2         | 1.02%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                | 2         | 1.02%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                          | 1         | 0.51%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                          | 1         | 0.51%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)           | 1         | 0.51%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                            | 1         | 0.51%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                             | 1         | 0.51%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                 | 1         | 0.51%   |
| Seagate BarraCuda Q5 NVMe SSD (DRAM-less)                                     | 1         | 0.51%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                    | 1         | 0.51%   |
| Sandisk WD Black SN850X NVMe SSD                                              | 1         | 0.51%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                         | 1         | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 95        | 51.63%  |
| SATA | 73        | 39.67%  |
| RAID | 14        | 7.61%   |
| IDE  | 2         | 1.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 104       | 73.24%  |
| AMD    | 38        | 26.76%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Intel 12th Gen Core i7-12700H              | 7         | 4.93%   |
| AMD Ryzen 7 7840HS w/ Radeon 780M Graphics | 6         | 4.23%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz    | 5         | 3.52%   |
| Intel Core i7-9750H CPU @ 2.60GHz          | 4         | 2.82%   |
| Intel Core i7-8550U CPU @ 1.80GHz          | 4         | 2.82%   |
| Intel 12th Gen Core i7-1260P               | 4         | 2.82%   |
| AMD Ryzen 7 4800H with Radeon Graphics     | 4         | 2.82%   |
| Intel 13th Gen Core i9-13900HX             | 3         | 2.11%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 2         | 1.41%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz         | 2         | 1.41%   |
| Intel Core i7-3720QM CPU @ 2.60GHz         | 2         | 1.41%   |
| Intel Core i7-2670QM CPU @ 2.20GHz         | 2         | 1.41%   |
| Intel Core i7-2620M CPU @ 2.70GHz          | 2         | 1.41%   |
| Intel Core i7-10750H CPU @ 2.60GHz         | 2         | 1.41%   |
| Intel Core i5-9300H CPU @ 2.40GHz          | 2         | 1.41%   |
| Intel Core i5-8365U CPU @ 1.60GHz          | 2         | 1.41%   |
| Intel Core i5-3210M CPU @ 2.50GHz          | 2         | 1.41%   |
| Intel 13th Gen Core i7-1360P               | 2         | 1.41%   |
| Intel 12th Gen Core i7-1255U               | 2         | 1.41%   |
| Intel 12th Gen Core i5-1240P               | 2         | 1.41%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz    | 2         | 1.41%   |
| AMD Ryzen 9 6900HX with Radeon Graphics    | 2         | 1.41%   |
| AMD Ryzen 7 6800H with Radeon Graphics     | 2         | 1.41%   |
| AMD Ryzen 7 5700U with Radeon Graphics     | 2         | 1.41%   |
| AMD Ryzen 5 4600H with Radeon Graphics     | 2         | 1.41%   |
| AMD Ryzen 3 5300U with Radeon Graphics     | 2         | 1.41%   |
| Intel Xeon W-10855M CPU @ 2.80GHz          | 1         | 0.7%    |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz       | 1         | 0.7%    |
| Intel Pentium CPU 2020M @ 2.40GHz          | 1         | 0.7%    |
| Intel N100                                 | 1         | 0.7%    |
| Intel Core m5-6Y54 CPU @ 1.10GHz           | 1         | 0.7%    |
| Intel Core i9-10900KF CPU @ 3.70GHz        | 1         | 0.7%    |
| Intel Core i7-8565U CPU @ 1.80GHz          | 1         | 0.7%    |
| Intel Core i7-7820HQ CPU @ 2.90GHz         | 1         | 0.7%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz         | 1         | 0.7%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 1         | 0.7%    |
| Intel Core i7-6600U CPU @ 2.60GHz          | 1         | 0.7%    |
| Intel Core i7-5600U CPU @ 2.60GHz          | 1         | 0.7%    |
| Intel Core i7-5500U CPU @ 2.40GHz          | 1         | 0.7%    |
| Intel Core i7-4770HQ CPU @ 2.20GHz         | 1         | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Notebooks | Percent |
|-------------------|-----------|---------|
| Other             | 39        | 27.46%  |
| Intel Core i7     | 34        | 23.94%  |
| AMD Ryzen 7       | 19        | 13.38%  |
| Intel Core i5     | 17        | 11.97%  |
| AMD Ryzen 5       | 7         | 4.93%   |
| Intel Core i3     | 3         | 2.11%   |
| Intel Celeron     | 3         | 2.11%   |
| AMD Ryzen 9       | 3         | 2.11%   |
| Intel Xeon        | 2         | 1.41%   |
| Intel Core 2 Duo  | 2         | 1.41%   |
| AMD Ryzen 3       | 2         | 1.41%   |
| AMD A8            | 2         | 1.41%   |
| AMD A10           | 2         | 1.41%   |
| Intel Pentium     | 1         | 0.7%    |
| Intel Core m5     | 1         | 0.7%    |
| Intel Core i9     | 1         | 0.7%    |
| Intel Core 2 Quad | 1         | 0.7%    |
| AMD Turion II     | 1         | 0.7%    |
| AMD Ryzen 7 PRO   | 1         | 0.7%    |
| AMD Ryzen 5 PRO   | 1         | 0.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 39        | 27.46%  |
| 2      | 33        | 23.24%  |
| 8      | 25        | 17.61%  |
| 6      | 17        | 11.97%  |
| 14     | 11        | 7.75%   |
| 12     | 9         | 6.34%   |
| 10     | 4         | 2.82%   |
| 24     | 3         | 2.11%   |
| 16     | 1         | 0.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 142       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 130       | 91.55%  |
| 1      | 12        | 8.45%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 142       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 127       | 88.19%  |
| 0x0a704103 | 3         | 2.08%   |
| 0x906a4    | 2         | 1.39%   |
| 0x0a404102 | 2         | 1.39%   |
| 0x08608103 | 2         | 1.39%   |
| 0x906ea    | 1         | 0.69%   |
| 0x906e9    | 1         | 0.69%   |
| 0x906a3    | 1         | 0.69%   |
| 0x806c1    | 1         | 0.69%   |
| 0x306d4    | 1         | 0.69%   |
| 0x0a704101 | 1         | 0.69%   |
| 0x0a50000c | 1         | 0.69%   |
| 0x010000c8 | 1         | 0.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Unknown          | 37        | 26.06%  |
| KabyLake         | 18        | 12.68%  |
| Alderlake Hybrid | 11        | 7.75%   |
| Zen 2            | 9         | 6.34%   |
| TigerLake        | 8         | 5.63%   |
| IvyBridge        | 8         | 5.63%   |
| Haswell          | 7         | 4.93%   |
| CometLake        | 7         | 4.93%   |
| Broadwell        | 7         | 4.93%   |
| SandyBridge      | 6         | 4.23%   |
| Skylake          | 5         | 3.52%   |
| Zen 3            | 4         | 2.82%   |
| Penryn           | 3         | 2.11%   |
| Zen+             | 2         | 1.41%   |
| Westmere         | 2         | 1.41%   |
| Piledriver       | 2         | 1.41%   |
| Silvermont       | 1         | 0.7%    |
| Puma             | 1         | 0.7%    |
| K10              | 1         | 0.7%    |
| Gracemont        | 1         | 0.7%    |
| Goldmont plus    | 1         | 0.7%    |
| Excavator        | 1         | 0.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 99        | 50.51%  |
| Nvidia | 54        | 27.55%  |
| AMD    | 43        | 21.94%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                             | 13        | 6.4%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                         | 9         | 4.43%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 8         | 3.94%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 8         | 3.94%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 7         | 3.45%   |
| AMD Phoenix1                                                                          | 7         | 3.45%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 6         | 2.96%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                | 6         | 2.96%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 6         | 2.96%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 6         | 2.96%   |
| AMD Rembrandt [Radeon 680M]                                                           | 6         | 2.96%   |
| Intel UHD Graphics 620                                                                | 5         | 2.46%   |
| Intel HD Graphics 5500                                                                | 5         | 2.46%   |
| AMD Navi 33 [Radeon RX 7700S/7600/7600S/7600M XT/PRO W7600]                           | 5         | 2.46%   |
| AMD Lucienne                                                                          | 5         | 2.46%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                              | 4         | 1.97%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 4         | 1.97%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 3         | 1.48%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 3         | 1.48%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                                         | 3         | 1.48%   |
| Nvidia AD106M [GeForce RTX 4070 Max-Q / Mobile]                                       | 3         | 1.48%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 3         | 1.48%   |
| Intel Raptor Lake-S UHD Graphics                                                      | 3         | 1.48%   |
| Intel HD Graphics 630                                                                 | 3         | 1.48%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 3         | 1.48%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 2         | 0.99%   |
| Nvidia GF108M [GeForce GT 635M]                                                       | 2         | 0.99%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 2         | 0.99%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                       | 2         | 0.99%   |
| Intel HD Graphics 530                                                                 | 2         | 0.99%   |
| Intel Haswell-ULT Integrated Graphics Controller [HD Graphics]                        | 2         | 0.99%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 2         | 0.99%   |
| Intel Core Processor Integrated Graphics Controller                                   | 2         | 0.99%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                           | 2         | 0.99%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 2         | 0.99%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 2         | 0.99%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 2         | 0.99%   |
| AMD Mars XTX [Radeon HD 8790M]                                                        | 2         | 0.99%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                         | 1         | 0.49%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                               | 1         | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 58        | 40.56%  |
| Intel + Nvidia | 35        | 24.48%  |
| 1 x AMD        | 18        | 12.59%  |
| AMD + Nvidia   | 13        | 9.09%   |
| 2 x AMD        | 7         | 4.9%    |
| 1 x Nvidia     | 6         | 4.2%    |
| Intel + AMD    | 6         | 4.2%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 99        | 69.72%  |
| Proprietary | 42        | 29.58%  |
| Unknown     | 1         | 0.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 102       | 70.83%  |
| 7.01-8.0   | 12        | 8.33%   |
| 5.01-6.0   | 12        | 8.33%   |
| 3.01-4.0   | 8         | 5.56%   |
| 1.01-2.0   | 3         | 2.08%   |
| 8.01-16.0  | 3         | 2.08%   |
| 0.01-0.5   | 3         | 2.08%   |
| 0.51-1.0   | 1         | 0.69%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 52        | 30.06%  |
| AU Optronics        | 27        | 15.61%  |
| LG Display          | 14        | 8.09%   |
| Chimei Innolux      | 14        | 8.09%   |
| Samsung Electronics | 13        | 7.51%   |
| CSO                 | 9         | 5.2%    |
| Apple               | 8         | 4.62%   |
| Hewlett-Packard     | 4         | 2.31%   |
| AOC                 | 4         | 2.31%   |
| Lenovo              | 3         | 1.73%   |
| Goldstar            | 3         | 1.73%   |
| Dell                | 3         | 1.73%   |
| Acer                | 3         | 1.73%   |
| Sharp               | 2         | 1.16%   |
| SGT                 | 2         | 1.16%   |
| BenQ                | 2         | 1.16%   |
| Yamaha              | 1         | 0.58%   |
| VIE                 | 1         | 0.58%   |
| Sony                | 1         | 0.58%   |
| RTK                 | 1         | 0.58%   |
| PANDA               | 1         | 0.58%   |
| NEC Computers       | 1         | 0.58%   |
| Iiyama              | 1         | 0.58%   |
| HUAWEI              | 1         | 0.58%   |
| Fujitsu Siemens     | 1         | 0.58%   |
| ASUSTek Computer    | 1         | 0.58%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                   | 7         | 3.95%   |
| BOE LCD Monitor BOE07D8 1920x1080 344x194mm 15.5-inch                   | 6         | 3.39%   |
| BOE LCD Monitor BOE09E5 2560x1440 355x200mm 16.0-inch                   | 4         | 2.26%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                   | 4         | 2.26%   |
| BOE LCD Monitor BOE084D 1920x1080 344x193mm 15.5-inch                   | 4         | 2.26%   |
| BOE LCD Monitor BOE0AF0 2560x1600 344x215mm 16.0-inch                   | 3         | 1.69%   |
| BOE LCD Monitor BOE0A3B 2560x1600 344x215mm 16.0-inch                   | 3         | 1.69%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                   | 3         | 1.69%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                | 2         | 1.13%   |
| Chimei Innolux LCD Monitor CMN1733 1600x900 382x215mm 17.3-inch         | 2         | 1.13%   |
| Chimei Innolux LCD Monitor CMN1602 1920x1080 355x199mm 16.0-inch        | 2         | 1.13%   |
| Chimei Innolux LCD Monitor CMN15BA 1920x1080 344x194mm 15.5-inch        | 2         | 1.13%   |
| BOE LCD Monitor BOE0B40 2560x1440 344x194mm 15.5-inch                   | 2         | 1.13%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                   | 2         | 1.13%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                   | 2         | 1.13%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch           | 2         | 1.13%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch          | 2         | 1.13%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                  | 2         | 1.13%   |
| Yamaha RX-V473 YMH3171 1920x540                                         | 1         | 0.56%   |
| VIE ATHEN U2L 24 VIE2380 1920x1080 527x296mm 23.8-inch                  | 1         | 0.56%   |
| Sony TV SNY4803 1920x1080 930x523mm 42.0-inch                           | 1         | 0.56%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                 | 1         | 0.56%   |
| Sharp LCD Monitor SHP143B 3840x2160 346x194mm 15.6-inch                 | 1         | 0.56%   |
| SGT M2145J1F2281 SGT2145 1920x1080 477x268mm 21.5-inch                  | 1         | 0.56%   |
| SGT HS156PC SGT9156 1920x1080 345x194mm 15.6-inch                       | 1         | 0.56%   |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch       | 1         | 0.56%   |
| Samsung Electronics SAMTRON STN0022 1280x1024 380x300mm 19.1-inch       | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch    | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch    | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3641 1366x768 353x198mm 15.9-inch    | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch    | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch    | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4193 2880x1800 302x189mm 14.0-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch    | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 950x540mm 43.0-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SAM0DEE 3840x2160 1872x1053mm 84.6-inch | 1         | 0.56%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 1         | 0.56%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch       | 1         | 0.56%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 1         | 0.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 72        | 43.9%   |
| 1366x768 (WXGA)    | 20        | 12.2%   |
| 2560x1440 (QHD)    | 17        | 10.37%  |
| 2880x1800          | 11        | 6.71%   |
| 3840x2160 (4K)     | 9         | 5.49%   |
| 2560x1600          | 9         | 5.49%   |
| 1920x1200 (WUXGA)  | 5         | 3.05%   |
| 1600x900 (HD+)     | 5         | 3.05%   |
| 1280x800 (WXGA)    | 5         | 3.05%   |
| 3200x1800 (QHD+)   | 2         | 1.22%   |
| 1680x1050 (WSXGA+) | 2         | 1.22%   |
| 1440x900 (WXGA+)   | 2         | 1.22%   |
| 3840x2560          | 1         | 0.61%   |
| 3440x1440          | 1         | 0.61%   |
| 2240x1400          | 1         | 0.61%   |
| 1920x540           | 1         | 0.61%   |
| 1280x1024 (SXGA)   | 1         | 0.61%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 67        | 38.51%  |
| 14      | 19        | 10.92%  |
| 17      | 17        | 9.77%   |
| 13      | 15        | 8.62%   |
| 16      | 14        | 8.05%   |
| 27      | 8         | 4.6%    |
| 24      | 7         | 4.02%   |
| 12      | 4         | 2.3%    |
| 22      | 3         | 1.72%   |
| 21      | 3         | 1.72%   |
| 40      | 2         | 1.15%   |
| 31      | 2         | 1.15%   |
| 23      | 2         | 1.15%   |
| 11      | 2         | 1.15%   |
| 84      | 1         | 0.57%   |
| 60      | 1         | 0.57%   |
| 43      | 1         | 0.57%   |
| 33      | 1         | 0.57%   |
| 28      | 1         | 0.57%   |
| 20      | 1         | 0.57%   |
| 19      | 1         | 0.57%   |
| 18      | 1         | 0.57%   |
| Unknown | 1         | 0.57%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 97        | 56.4%   |
| 351-400     | 25        | 14.53%  |
| 501-600     | 17        | 9.88%   |
| 201-300     | 16        | 9.3%    |
| 401-500     | 8         | 4.65%   |
| 801-900     | 2         | 1.16%   |
| 601-700     | 2         | 1.16%   |
| 701-800     | 1         | 0.58%   |
| 1501-2000   | 1         | 0.58%   |
| 1001-1500   | 1         | 0.58%   |
| 901-1000    | 1         | 0.58%   |
| Unknown     | 1         | 0.58%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 116       | 74.84%  |
| 16/10 | 34        | 21.94%  |
| 3/2   | 2         | 1.29%   |
| 5/4   | 1         | 0.65%   |
| 32/9  | 1         | 0.65%   |
| 21/9  | 1         | 0.65%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 71        | 40.8%   |
| 81-90          | 30        | 17.24%  |
| 121-130        | 15        | 8.62%   |
| 111-120        | 10        | 5.75%   |
| 301-350        | 8         | 4.6%    |
| 201-250        | 7         | 4.02%   |
| 251-300        | 5         | 2.87%   |
| 151-200        | 5         | 2.87%   |
| 71-80          | 4         | 2.3%    |
| 61-70          | 4         | 2.3%    |
| 351-500        | 4         | 2.3%    |
| 501-1000       | 3         | 1.72%   |
| More than 1000 | 2         | 1.15%   |
| 51-60          | 2         | 1.15%   |
| 131-140        | 2         | 1.15%   |
| 141-150        | 1         | 0.57%   |
| Unknown        | 1         | 0.57%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 69        | 40.83%  |
| 101-120       | 34        | 20.12%  |
| 161-240       | 28        | 16.57%  |
| 51-100        | 21        | 12.43%  |
| More than 240 | 15        | 8.88%   |
| 1-50          | 1         | 0.59%   |
| Unknown       | 1         | 0.59%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 108       | 75.52%  |
| 2     | 30        | 20.98%  |
| 3     | 4         | 2.8%    |
| 0     | 1         | 0.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 107       | 42.46%  |
| Realtek Semiconductor             | 89        | 35.32%  |
| Qualcomm Atheros                  | 9         | 3.57%   |
| Broadcom                          | 9         | 3.57%   |
| Ralink Technology                 | 5         | 1.98%   |
| DisplayLink                       | 5         | 1.98%   |
| Broadcom Limited                  | 5         | 1.98%   |
| MediaTek                          | 4         | 1.59%   |
| Huawei Technologies               | 4         | 1.59%   |
| ASIX Electronics                  | 4         | 1.59%   |
| Ralink                            | 2         | 0.79%   |
| TP-Link                           | 1         | 0.4%    |
| Sierra Wireless                   | 1         | 0.4%    |
| Samsung Electronics               | 1         | 0.4%    |
| OPPO Electronics                  | 1         | 0.4%    |
| Nvidia                            | 1         | 0.4%    |
| NetGear                           | 1         | 0.4%    |
| Lenovo                            | 1         | 0.4%    |
| Ericsson Business Mobile Networks | 1         | 0.4%    |
| Dell                              | 1         | 0.4%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 60        | 21.05%  |
| Intel Wi-Fi 6 AX200                                                    | 29        | 10.18%  |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 14        | 4.91%   |
| Realtek RTL8125 2.5GbE Controller                                      | 10        | 3.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 9         | 3.16%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 7         | 2.46%   |
| Intel Wi-Fi 6 AX201                                                    | 7         | 2.46%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 6         | 2.11%   |
| Intel Wireless 8265 / 8275                                             | 5         | 1.75%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 5         | 1.75%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 4         | 1.4%    |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 4         | 1.4%    |
| Intel Comet Lake PCH CNVi WiFi                                         | 4         | 1.4%    |
| DisplayLink DL-Dock                                                    | 4         | 1.4%    |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 1.4%    |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 3         | 1.05%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 3         | 1.05%   |
| Intel Wireless 7265                                                    | 3         | 1.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 3         | 1.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 1.05%   |
| Huawei ME936 LTE/HSDPA+ 4G modem                                       | 3         | 1.05%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 1.05%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 3         | 1.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 2         | 0.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2         | 0.7%    |
| Realtek RTL8723DE Wireless Network Adapter                             | 2         | 0.7%    |
| Realtek Killer E3000 2.5GbE Controller                                 | 2         | 0.7%    |
| Realtek Killer E2600 GbE Controller                                    | 2         | 0.7%    |
| Ralink MT7601U Wireless Adapter                                        | 2         | 0.7%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 2         | 0.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 2         | 0.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 2         | 0.7%    |
| Intel Wireless 8260                                                    | 2         | 0.7%    |
| Intel Wireless 7260                                                    | 2         | 0.7%    |
| Intel Wireless 3160                                                    | 2         | 0.7%    |
| Intel Ethernet Connection I217-LM                                      | 2         | 0.7%    |
| Intel Ethernet Connection (6) I219-LM                                  | 2         | 0.7%    |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 0.7%    |
| Intel Ethernet Connection (16) I219-LM                                 | 2         | 0.7%    |
| Intel Centrino Advanced-N 6235                                         | 2         | 0.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 104       | 70.75%  |
| Realtek Semiconductor | 10        | 6.8%    |
| Broadcom              | 9         | 6.12%   |
| Qualcomm Atheros      | 6         | 4.08%   |
| Ralink Technology     | 5         | 3.4%    |
| MediaTek              | 4         | 2.72%   |
| Broadcom Limited      | 4         | 2.72%   |
| Ralink                | 2         | 1.36%   |
| TP-Link               | 1         | 0.68%   |
| Sierra Wireless       | 1         | 0.68%   |
| NetGear               | 1         | 0.68%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 29        | 19.73%  |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 14        | 9.52%   |
| Intel Wi-Fi 6 AX201                                                  | 7         | 4.76%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 6         | 4.08%   |
| Intel Wireless 8265 / 8275                                           | 5         | 3.4%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 5         | 3.4%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 4         | 2.72%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                    | 4         | 2.72%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 4         | 2.72%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 3         | 2.04%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 3         | 2.04%   |
| Intel Wireless 7265                                                  | 3         | 2.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 3         | 2.04%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 3         | 2.04%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 2         | 1.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2         | 1.36%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 2         | 1.36%   |
| Ralink MT7601U Wireless Adapter                                      | 2         | 1.36%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 2         | 1.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2         | 1.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 2         | 1.36%   |
| Intel Wireless 8260                                                  | 2         | 1.36%   |
| Intel Wireless 7260                                                  | 2         | 1.36%   |
| Intel Wireless 3160                                                  | 2         | 1.36%   |
| Intel Centrino Advanced-N 6235                                       | 2         | 1.36%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 2         | 1.36%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 2         | 1.36%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter          | 2         | 1.36%   |
| Broadcom BCM43142 802.11b/g/n                                        | 2         | 1.36%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 1         | 0.68%   |
| Sierra Wireless EM7305                                               | 1         | 0.68%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 1         | 0.68%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 1         | 0.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1         | 0.68%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 1         | 0.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 1         | 0.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 1         | 0.68%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                      | 1         | 0.68%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 1         | 0.68%   |
| Intel Wireless 3165                                                  | 1         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 89        | 67.94%  |
| Intel                 | 21        | 16.03%  |
| DisplayLink           | 5         | 3.82%   |
| Qualcomm Atheros      | 4         | 3.05%   |
| ASIX Electronics      | 4         | 3.05%   |
| Broadcom              | 3         | 2.29%   |
| Samsung Electronics   | 1         | 0.76%   |
| OPPO Electronics      | 1         | 0.76%   |
| Nvidia                | 1         | 0.76%   |
| Lenovo                | 1         | 0.76%   |
| Broadcom Limited      | 1         | 0.76%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 60        | 45.45%  |
| Realtek RTL8125 2.5GbE Controller                                      | 10        | 7.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 9         | 6.82%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 7         | 5.3%    |
| DisplayLink DL-Dock                                                    | 4         | 3.03%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 3.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 2.27%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 2.27%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 2         | 1.52%   |
| Realtek Killer E2600 GbE Controller                                    | 2         | 1.52%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 1.52%   |
| Intel Ethernet Connection (6) I219-LM                                  | 2         | 1.52%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 1.52%   |
| Intel Ethernet Connection (16) I219-LM                                 | 2         | 1.52%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.76%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.76%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 0.76%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.76%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 0.76%   |
| OPPO CPH2591                                                           | 1         | 0.76%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.76%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 1         | 0.76%   |
| Intel WiMAX Connection 2400m                                           | 1         | 0.76%   |
| Intel Ethernet Connection I218-V                                       | 1         | 0.76%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 0.76%   |
| Intel Ethernet Connection (5) I219-LM                                  | 1         | 0.76%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 0.76%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 0.76%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 0.76%   |
| Intel Ethernet Connection (11) I219-LM                                 | 1         | 0.76%   |
| Intel 82574L Gigabit Network Connection                                | 1         | 0.76%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 0.76%   |
| DisplayLink Plugable UD-3900                                           | 1         | 0.76%   |
| Broadcom Limited NetXtreme BCM57760 Gigabit Ethernet PCIe              | 1         | 0.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 141       | 52.61%  |
| Ethernet | 121       | 45.15%  |
| Modem    | 6         | 2.24%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 103       | 70.55%  |
| Ethernet | 43        | 29.45%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 104       | 73.24%  |
| 1     | 34        | 23.94%  |
| 3     | 3         | 2.11%   |
| 0     | 1         | 0.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 74        | 52.11%  |
| Yes  | 68        | 47.89%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 97        | 74.05%  |
| Apple                           | 8         | 6.11%   |
| Realtek Semiconductor           | 7         | 5.34%   |
| Foxconn / Hon Hai               | 5         | 3.82%   |
| IMC Networks                    | 3         | 2.29%   |
| Broadcom                        | 3         | 2.29%   |
| Ralink                          | 2         | 1.53%   |
| ASUSTek Computer                | 2         | 1.53%   |
| Qualcomm Atheros Communications | 1         | 0.76%   |
| MediaTek                        | 1         | 0.76%   |
| Dell                            | 1         | 0.76%   |
| Cambridge Silicon Radio         | 1         | 0.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                               | 29        | 22.14%  |
| Intel AX201 Bluetooth                               | 21        | 16.03%  |
| Intel AX211 Bluetooth                               | 16        | 12.21%  |
| Intel Bluetooth wireless interface                  | 9         | 6.87%   |
| Intel Bluetooth Device                              | 7         | 5.34%   |
| Apple Bluetooth Host Controller                     | 5         | 3.82%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 3.05%   |
| Intel AX210 Bluetooth                               | 4         | 3.05%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 2.29%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 2.29%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 2.29%   |
| Apple Bluetooth USB Host Controller                 | 3         | 2.29%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 1.53%   |
| Ralink RT3290 Bluetooth                             | 2         | 1.53%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.53%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 1.53%   |
| IMC Networks Bluetooth Radio                        | 2         | 1.53%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 1.53%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.76%   |
| Realtek Bluetooth Radio                             | 1         | 0.76%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 0.76%   |
| MediaTek Wireless_Device                            | 1         | 0.76%   |
| IMC Networks Bluetooth Device                       | 1         | 0.76%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 0.76%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 0.76%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 0.76%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 0.76%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.76%   |
| ASUS BT-253 Bluetooth Adapter                       | 1         | 0.76%   |
| ASUS ASUS USB-BT500                                 | 1         | 0.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 101       | 52.06%  |
| Nvidia                                 | 44        | 22.68%  |
| AMD                                    | 39        | 20.1%   |
| Lenovo                                 | 2         | 1.03%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.52%   |
| Razer USA                              | 1         | 0.52%   |
| Logitech                               | 1         | 0.52%   |
| Kingston Technology                    | 1         | 0.52%   |
| Huawei Technologies                    | 1         | 0.52%   |
| GN Netcom                              | 1         | 0.52%   |
| FiiO Electronics Technology            | 1         | 0.52%   |
| C-Media Electronics                    | 1         | 0.52%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 33        | 13.81%  |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 18        | 7.53%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 12        | 5.02%   |
| Nvidia GA104 High Definition Audio Controller                              | 8         | 3.35%   |
| Nvidia Audio device                                                        | 8         | 3.35%   |
| Intel Sunrise Point-LP HD Audio                                            | 8         | 3.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 3.35%   |
| Nvidia GA106 High Definition Audio Controller                              | 7         | 2.93%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 2.93%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 2.93%   |
| Intel Broadwell-U Audio Controller                                         | 7         | 2.93%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 7         | 2.93%   |
| Nvidia TU116 High Definition Audio Controller                              | 6         | 2.51%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 6         | 2.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 2.51%   |
| Intel Comet Lake PCH cAVS                                                  | 5         | 2.09%   |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 2.09%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 5         | 2.09%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 1.67%   |
| Intel Raptor Lake High Definition Audio Controller                         | 4         | 1.67%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 1.67%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 1.67%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 1.26%   |
| Intel CM238 HD Audio Controller                                            | 3         | 1.26%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 1.26%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 1.26%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.26%   |
| AMD FCH Azalia Controller                                                  | 3         | 1.26%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.84%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 0.84%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 0.84%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 0.84%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 0.84%   |
| AMD Trinity HDMI Audio Controller                                          | 2         | 0.84%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 0.84%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 0.84%   |
| Sony Ericsson Mobile Communications AB XQ-AU52                             | 1         | 0.42%   |
| Razer USA RC30-026902, Gaming Headset [Nari Essential, Wireless, Receiver] | 1         | 0.42%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.42%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 21        | 42%     |
| SK hynix            | 13        | 26%     |
| Micron Technology   | 6         | 12%     |
| Unknown             | 4         | 8%      |
| Team                | 2         | 4%      |
| Elpida              | 2         | 4%      |
| Kingston            | 1         | 2%      |
| ASint Technology    | 1         | 2%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 5         | 9.8%    |
| Unknown                                                          | 4         | 7.84%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 5.88%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 2         | 3.92%   |
| SK hynix RAM HMCG66AGBSA095N 8GB SODIMM DDR5 5600MT/s            | 2         | 3.92%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 3.92%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 3.92%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 3.92%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 2         | 3.92%   |
| Samsung RAM M425R4GA3BB0-CQKOL 32GB SODIMM DDR5 4800MT/s         | 2         | 3.92%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.96%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.96%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.96%   |
| SK hynix RAM HMCG88AGBSA092N 32GB SODIMM 5600MT/s                | 1         | 1.96%   |
| SK hynix RAM HMCG78AGBSA092N 16GB SODIMM DDR5 5600MT/s           | 1         | 1.96%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 1.96%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.96%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.96%   |
| Samsung RAM Module 4GB SODIMM DDR3 1867MT/s                      | 1         | 1.96%   |
| Samsung RAM Module 3GB Row Of Chips LPDDR5 6400MT/s              | 1         | 1.96%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.96%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.96%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 1.96%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.96%   |
| Samsung RAM M425R2GA3BB0-CWMOD 16GB SODIMM DDR5 5600MT/s         | 1         | 1.96%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s          | 1         | 1.96%   |
| Micron RAM MT62F1G32D2DS-026 WT 2GB Row Of Chips LPDDR5 6400MT/s | 1         | 1.96%   |
| Micron RAM Module 2GB Row Of Chips LPDDR5 6400MT/s               | 1         | 1.96%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.96%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s             | 1         | 1.96%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 1         | 1.96%   |
| Kingston RAM KHX1600C9S3/8G 8GB SODIMM DDR3 1600MT/s             | 1         | 1.96%   |
| Elpida RAM Module 4GB SODIMM LPDDR3 1600MT/s                     | 1         | 1.96%   |
| Elpida RAM EBJ21UE8BDS0-AE-F 2GB SODIMM DDR3 1067MT/s            | 1         | 1.96%   |
| ASint RAM SSZ302G08-GGNHC 2GB SODIMM DDR3 1600MT/s               | 1         | 1.96%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 23        | 50%     |
| DDR5    | 8         | 17.39%  |
| DDR3    | 8         | 17.39%  |
| LPDDR5  | 5         | 10.87%  |
| LPDDR3  | 1         | 2.17%   |
| Unknown | 1         | 2.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 41        | 89.13%  |
| Row Of Chips | 5         | 10.87%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 17        | 34.69%  |
| 32768 | 11        | 22.45%  |
| 16384 | 8         | 16.33%  |
| 4096  | 7         | 14.29%  |
| 2048  | 5         | 10.2%   |
| 3072  | 1         | 2.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 17        | 35.42%  |
| 1600  | 7         | 14.58%  |
| 6400  | 5         | 10.42%  |
| 5600  | 5         | 10.42%  |
| 2667  | 4         | 8.33%   |
| 4800  | 3         | 6.25%   |
| 8400  | 2         | 4.17%   |
| 2400  | 1         | 2.08%   |
| 2133  | 1         | 2.08%   |
| 1867  | 1         | 2.08%   |
| 1067  | 1         | 2.08%   |
| 1066  | 1         | 2.08%   |

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
| Chicony Electronics                    | 59        | 47.2%   |
| Bison Electronics                      | 13        | 10.4%   |
| Microdia                               | 11        | 8.8%    |
| Suyin                                  | 5         | 4%      |
| Acer                                   | 5         | 4%      |
| Sunplus Innovation Technology          | 4         | 3.2%    |
| Apple                                  | 4         | 3.2%    |
| Realtek Semiconductor                  | 3         | 2.4%    |
| Logitech                               | 3         | 2.4%    |
| IMC Networks                           | 3         | 2.4%    |
| Syntek                                 | 2         | 1.6%    |
| Lite-On Technology                     | 2         | 1.6%    |
| Unknown                                | 1         | 0.8%    |
| SunplusIT                              | 1         | 0.8%    |
| Silicon Motion                         | 1         | 0.8%    |
| Ricoh                                  | 1         | 0.8%    |
| Microsoft                              | 1         | 0.8%    |
| Luxvisions Innotech Limited            | 1         | 0.8%    |
| Importek                               | 1         | 0.8%    |
| HYGD-220831-A                          | 1         | 0.8%    |
| Generalplus Technology                 | 1         | 0.8%    |
| Cheng Uei Precision Industry (Foxlink) | 1         | 0.8%    |
| Alpha Imaging Technology               | 1         | 0.8%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony FHD Webcam                                   | 11        | 8.73%   |
| Chicony USB2.0 Camera                                | 10        | 7.94%   |
| Chicony Integrated IR Camera                         | 9         | 7.14%   |
| Chicony HD Webcam                                    | 7         | 5.56%   |
| Bison BisonCam,NB Pro                                | 7         | 5.56%   |
| Bison HD Webcam                                      | 5         | 3.97%   |
| Microdia Integrated Camera                           | 4         | 3.17%   |
| Chicony Integrated Camera                            | 4         | 3.17%   |
| Microdia Integrated_Webcam_FHD                       | 3         | 2.38%   |
| IMC Networks Integrated Camera                       | 3         | 2.38%   |
| Apple FaceTime HD Camera                             | 3         | 2.38%   |
| Acer Lenovo EasyCamera                               | 3         | 2.38%   |
| Syntek Integrated Camera                             | 2         | 1.59%   |
| Suyin HP Truevision HD                               | 2         | 1.59%   |
| Sunplus Integrated_Webcam_HD                         | 2         | 1.59%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 2         | 1.59%   |
| Chicony HP Webcam                                    | 2         | 1.59%   |
| Chicony ACER HD User Facing                          | 2         | 1.59%   |
| Unknown HD camera                                    | 1         | 0.79%   |
| Suyin RGBIR Camera                                   | 1         | 0.79%   |
| Suyin Integrated_Webcam_HD                           | 1         | 0.79%   |
| Suyin HP TrueVision HD Integrated Webcam             | 1         | 0.79%   |
| SunplusIT FHD Webcam                                 | 1         | 0.79%   |
| Sunplus Laptop_Integrated_Webcam_FHD                 | 1         | 0.79%   |
| Sunplus Asus Webcam                                  | 1         | 0.79%   |
| Silicon Motion WebCam SCB-1100N                      | 1         | 0.79%   |
| Ricoh Laptop_Integrated_Webcam_FHD                   | 1         | 0.79%   |
| Realtek Integrated Webcam                            | 1         | 0.79%   |
| Realtek HP Wide Vision HD Camera                     | 1         | 0.79%   |
| Realtek HP "Truevision HD" laptop camera             | 1         | 0.79%   |
| Microsoft MicrosoftÂ LifeCam Studio                 | 1         | 0.79%   |
| Microdia Laptop_Integrated_Webcam_E4HD               | 1         | 0.79%   |
| Microdia Integrated_Webcam_HD                        | 1         | 0.79%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 0.79%   |
| Logitech QuickCam Communicate MP/S5500               | 1         | 0.79%   |
| Logitech BRIO Ultra HD Webcam                        | 1         | 0.79%   |
| Logitech Brio 500                                    | 1         | 0.79%   |
| Lite-On Integrated Camera                            | 1         | 0.79%   |
| Lite-On HP Webcam                                    | 1         | 0.79%   |
| Importek HP Webcam                                   | 1         | 0.79%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 11        | 47.83%  |
| Validity Sensors           | 8         | 34.78%  |
| Shenzhen Goodix Technology | 2         | 8.7%    |
| LighTuning Technology      | 2         | 8.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics TouchPad                                                         | 3         | 13.04%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 13.04%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 8.7%    |
| Validity Sensors VFS491                                                    | 2         | 8.7%    |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 8.7%    |
| Unknown                                                                    | 2         | 8.7%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 4.35%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 4.35%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 4.35%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 4.35%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 4.35%   |
| Synaptics WBDI                                                             | 1         | 4.35%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 4.35%   |
| LighTuning Fingerprint Reader                                              | 1         | 4.35%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 4.35%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 6         | 66.67%  |
| Alcor Micro | 3         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 3         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 11.11%  |
| Broadcom 5880                                                                | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 84        | 59.15%  |
| 1     | 51        | 35.92%  |
| 2     | 6         | 4.23%   |
| 3     | 1         | 0.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 23        | 34.33%  |
| Multimedia controller | 18        | 26.87%  |
| Chipcard              | 9         | 13.43%  |
| Graphics card         | 7         | 10.45%  |
| Net/wireless          | 3         | 4.48%   |
| Bluetooth             | 2         | 2.99%   |
| Wireless              | 1         | 1.49%   |
| Storage               | 1         | 1.49%   |
| Sound                 | 1         | 1.49%   |
| Modem                 | 1         | 1.49%   |
| Card reader           | 1         | 1.49%   |


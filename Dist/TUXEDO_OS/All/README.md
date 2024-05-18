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

Total: 246

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Schenker      | VISION 16 Pro (L22)         | Notebook    | [c54f918726](https://linux-hardware.org/?probe=c54f918726) | May 08, 2024 |
| MSI           | PRO B760-P WIFI DDR4        | Desktop     | [35d60afe01](https://linux-hardware.org/?probe=35d60afe01) | May 07, 2024 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [bc9db74da3](https://linux-hardware.org/?probe=bc9db74da3) | May 07, 2024 |
| TUXEDO        | Sirius 16 Gen1              | Notebook    | [b093c73dcb](https://linux-hardware.org/?probe=b093c73dcb) | May 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [8a0a1ade7b](https://linux-hardware.org/?probe=8a0a1ade7b) | May 04, 2024 |
| Lenovo        | Yoga 730-13IKB 81CT         | Convertible | [789d6cf5b0](https://linux-hardware.org/?probe=789d6cf5b0) | May 03, 2024 |
| ASUSTek       | N71Vn                       | Notebook    | [6f38bd6250](https://linux-hardware.org/?probe=6f38bd6250) | May 03, 2024 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [ad5d8cbdf2](https://linux-hardware.org/?probe=ad5d8cbdf2) | May 03, 2024 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [93d15c44da](https://linux-hardware.org/?probe=93d15c44da) | May 02, 2024 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [962196d889](https://linux-hardware.org/?probe=962196d889) | May 02, 2024 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [fd5584ca3b](https://linux-hardware.org/?probe=fd5584ca3b) | May 02, 2024 |
| ASUSTek       | N71Vn                       | Notebook    | [d5d1d55df1](https://linux-hardware.org/?probe=d5d1d55df1) | May 01, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [9bb8151528](https://linux-hardware.org/?probe=9bb8151528) | May 01, 2024 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [290ff65bc7](https://linux-hardware.org/?probe=290ff65bc7) | Apr 30, 2024 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [f6d6805396](https://linux-hardware.org/?probe=f6d6805396) | Apr 27, 2024 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [be0672ea72](https://linux-hardware.org/?probe=be0672ea72) | Apr 21, 2024 |
| HP            | ProBook 4540s               | Notebook    | [b13d3be380](https://linux-hardware.org/?probe=b13d3be380) | Apr 21, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [4af30719ae](https://linux-hardware.org/?probe=4af30719ae) | Apr 19, 2024 |
| TUXEDO        | Stellaris/Polaris AMD Ge... | Notebook    | [bb18adad6a](https://linux-hardware.org/?probe=bb18adad6a) | Apr 19, 2024 |
| Toshiba       | PORTEGE Z10T-A              | Notebook    | [8ed3e0a790](https://linux-hardware.org/?probe=8ed3e0a790) | Apr 16, 2024 |
| Dell          | Latitude 5430               | Notebook    | [5f23ced920](https://linux-hardware.org/?probe=5f23ced920) | Apr 16, 2024 |
| HP            | 250 G7 Notebook PC          | Notebook    | [714eb8d9ea](https://linux-hardware.org/?probe=714eb8d9ea) | Apr 16, 2024 |
| TUXEDO        | Sirius 16 Gen1              | Notebook    | [6b5703bf76](https://linux-hardware.org/?probe=6b5703bf76) | Apr 14, 2024 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [918934ed68](https://linux-hardware.org/?probe=918934ed68) | Apr 11, 2024 |
| TUXEDO        | Sirius 16 Gen1              | Notebook    | [d8b9d651e3](https://linux-hardware.org/?probe=d8b9d651e3) | Apr 11, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [0e37beebd4](https://linux-hardware.org/?probe=0e37beebd4) | Apr 05, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [2c20f368e3](https://linux-hardware.org/?probe=2c20f368e3) | Apr 05, 2024 |
| Acer          | Aspire XC-710 V:1.1         | Desktop     | [b6e8461941](https://linux-hardware.org/?probe=b6e8461941) | Apr 05, 2024 |
| TUXEDO        | Polaris AMD Gen5            | Notebook    | [352afa7567](https://linux-hardware.org/?probe=352afa7567) | Apr 04, 2024 |
| MSI           | Vector GP78HX 13VG          | Notebook    | [74268fafe5](https://linux-hardware.org/?probe=74268fafe5) | Mar 31, 2024 |
| Apple         | MacBook5,1                  | Notebook    | [0b7838f79e](https://linux-hardware.org/?probe=0b7838f79e) | Mar 26, 2024 |
| Dell          | Latitude E6420              | Notebook    | [cdd8eb657a](https://linux-hardware.org/?probe=cdd8eb657a) | Mar 22, 2024 |
| Apple         | MacBookPro11,2              | Notebook    | [247c0bdfb3](https://linux-hardware.org/?probe=247c0bdfb3) | Mar 21, 2024 |
| Gigabyte      | Z590M GAMING X              | Desktop     | [0012e0f378](https://linux-hardware.org/?probe=0012e0f378) | Mar 20, 2024 |
| Gigabyte      | Z590M GAMING X              | Desktop     | [c04f68437c](https://linux-hardware.org/?probe=c04f68437c) | Mar 20, 2024 |
| Dell          | 0PXWHK A00                  | Desktop     | [67b3d9e0e0](https://linux-hardware.org/?probe=67b3d9e0e0) | Mar 20, 2024 |
| HP            | Pavilion 15                 | Notebook    | [a9bc9facce](https://linux-hardware.org/?probe=a9bc9facce) | Mar 19, 2024 |
| Acer          | Aspire XC-710 V:1.1         | Desktop     | [949b3c7713](https://linux-hardware.org/?probe=949b3c7713) | Mar 17, 2024 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [8529154b4a](https://linux-hardware.org/?probe=8529154b4a) | Mar 15, 2024 |
| Lenovo        | Yoga 700-11ISK 80QE         | Notebook    | [a0a622a966](https://linux-hardware.org/?probe=a0a622a966) | Mar 14, 2024 |
| Dell          | Latitude 7480               | Notebook    | [13613ddbb8](https://linux-hardware.org/?probe=13613ddbb8) | Mar 14, 2024 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [106f4fd286](https://linux-hardware.org/?probe=106f4fd286) | Mar 13, 2024 |
| ASRock        | H470M-HDV/M.2               | Desktop     | [e9c20372c1](https://linux-hardware.org/?probe=e9c20372c1) | Mar 12, 2024 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a2495ce9f0](https://linux-hardware.org/?probe=a2495ce9f0) | Mar 11, 2024 |
| MSI           | Modern 15 H B13M            | Notebook    | [31bba1378f](https://linux-hardware.org/?probe=31bba1378f) | Mar 11, 2024 |
| MSI           | GF75 Thin 10SC              | Notebook    | [a415956dc4](https://linux-hardware.org/?probe=a415956dc4) | Mar 10, 2024 |
| ASUSTek       | X555LJ                      | Notebook    | [72da032893](https://linux-hardware.org/?probe=72da032893) | Mar 09, 2024 |
| HP            | Pavilion g7                 | Notebook    | [10e05bd9bc](https://linux-hardware.org/?probe=10e05bd9bc) | Mar 08, 2024 |
| Gigabyte      | H61M-DS2                    | Desktop     | [68d8ddbe50](https://linux-hardware.org/?probe=68d8ddbe50) | Mar 04, 2024 |
| MSI           | Modern 15 H B13M            | Notebook    | [a1ac91ddf1](https://linux-hardware.org/?probe=a1ac91ddf1) | Mar 02, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [e809fe3bcd](https://linux-hardware.org/?probe=e809fe3bcd) | Feb 29, 2024 |
| Toshiba       | Satellite A665              | Notebook    | [2a3093ba09](https://linux-hardware.org/?probe=2a3093ba09) | Feb 29, 2024 |
| Intel         | NUC12WSBi5 M46425-304       | Mini pc     | [0dbdc841e7](https://linux-hardware.org/?probe=0dbdc841e7) | Feb 26, 2024 |
| TUXEDO        | Sirius 16 Gen1              | Notebook    | [76659ee758](https://linux-hardware.org/?probe=76659ee758) | Feb 25, 2024 |
| Wortmann      | 1220595_1470122             | Notebook    | [8f49189b79](https://linux-hardware.org/?probe=8f49189b79) | Feb 24, 2024 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [31c62326ca](https://linux-hardware.org/?probe=31c62326ca) | Feb 19, 2024 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [eba58b31de](https://linux-hardware.org/?probe=eba58b31de) | Feb 16, 2024 |
| TUXEDO        | Sirius 16 Gen1              | Notebook    | [44b101b616](https://linux-hardware.org/?probe=44b101b616) | Feb 14, 2024 |
| ASRock        | Z690 Extreme WiFi 6E        | Desktop     | [5889cc7c2c](https://linux-hardware.org/?probe=5889cc7c2c) | Feb 13, 2024 |
| TUXEDO        | XP1610                      | Notebook    | [520e2a82de](https://linux-hardware.org/?probe=520e2a82de) | Feb 12, 2024 |
| TUXEDO        | InfinityBook Pro Gen8 (M... | Notebook    | [d3fc4417ee](https://linux-hardware.org/?probe=d3fc4417ee) | Feb 12, 2024 |
| TUXEDO        | Unknown                     | Notebook    | [9e4e88d13e](https://linux-hardware.org/?probe=9e4e88d13e) | Feb 11, 2024 |
| TUXEDO        | Book XP15 / XP17 Gen12      | Notebook    | [e8784ff987](https://linux-hardware.org/?probe=e8784ff987) | Feb 09, 2024 |
| TUXEDO        | InfinityBook S Gen8         | Notebook    | [8dddfa59a5](https://linux-hardware.org/?probe=8dddfa59a5) | Feb 09, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [81424087b4](https://linux-hardware.org/?probe=81424087b4) | Feb 06, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [9305000cc3](https://linux-hardware.org/?probe=9305000cc3) | Feb 06, 2024 |
| HP            | 250 G3                      | Notebook    | [3302706a4e](https://linux-hardware.org/?probe=3302706a4e) | Feb 05, 2024 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [8098729533](https://linux-hardware.org/?probe=8098729533) | Jan 30, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [590fcea5fe](https://linux-hardware.org/?probe=590fcea5fe) | Jan 30, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [f45683d844](https://linux-hardware.org/?probe=f45683d844) | Jan 30, 2024 |
| HP            | 2AA7 H                      | Desktop     | [4dbc7b0fe9](https://linux-hardware.org/?probe=4dbc7b0fe9) | Jan 30, 2024 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [c766c9daaf](https://linux-hardware.org/?probe=c766c9daaf) | Jan 22, 2024 |
| HP            | ENVY x360 Convertible 13... | Convertible | [23f12deb76](https://linux-hardware.org/?probe=23f12deb76) | Jan 21, 2024 |
| HP            | ENVY x360 Convertible 13... | Convertible | [12bc62b3a4](https://linux-hardware.org/?probe=12bc62b3a4) | Jan 21, 2024 |
| BESSTAR Te... | HM80                        | Desktop     | [3d9f1350b3](https://linux-hardware.org/?probe=3d9f1350b3) | Jan 14, 2024 |
| Acer          | Nitro AN515-47              | Notebook    | [521b0ef15b](https://linux-hardware.org/?probe=521b0ef15b) | Jan 13, 2024 |
| HP            | Laptop 15-bw0xx             | Notebook    | [9a8667ecaa](https://linux-hardware.org/?probe=9a8667ecaa) | Jan 12, 2024 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [0fd7405be4](https://linux-hardware.org/?probe=0fd7405be4) | Jan 03, 2024 |
| TUXEDO        | Polaris AMD Gen5            | Notebook    | [aa5447c317](https://linux-hardware.org/?probe=aa5447c317) | Jan 01, 2024 |
| ASRock        | H170M Pro4                  | Desktop     | [27e24a6ef3](https://linux-hardware.org/?probe=27e24a6ef3) | Dec 30, 2023 |
| Samsung       | RC530/RC730                 | Notebook    | [866c256904](https://linux-hardware.org/?probe=866c256904) | Dec 30, 2023 |
| Samsung       | RC530/RC730                 | Notebook    | [db448e5732](https://linux-hardware.org/?probe=db448e5732) | Dec 29, 2023 |
| TUXEDO        | Polaris AMD Gen5            | Notebook    | [46ad5a6b29](https://linux-hardware.org/?probe=46ad5a6b29) | Dec 28, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [54961dd296](https://linux-hardware.org/?probe=54961dd296) | Dec 25, 2023 |
| TUXEDO        | Polaris AMD Gen5            | Notebook    | [f63c59d851](https://linux-hardware.org/?probe=f63c59d851) | Dec 24, 2023 |
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

![OS](./images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| TUXEDO OS 22.04 | 189       | 100%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| TUXEDO OS | 189       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 6.5.0-10022-tuxedo   | 23        | 11.27%  |
| 6.1.0-1009-tuxedo    | 17        | 8.33%   |
| 6.5.0-10027-tuxedo   | 16        | 7.84%   |
| 6.2.0-10018-tuxedo   | 14        | 6.86%   |
| 6.2.0-10022-tuxedo   | 13        | 6.37%   |
| 6.5.0-10036-tuxedo   | 11        | 5.39%   |
| 6.5.0-10013-tuxedo   | 11        | 5.39%   |
| 6.2.0-10007-tuxedo   | 11        | 5.39%   |
| 6.2.0-10005-tuxedo   | 11        | 5.39%   |
| 6.5.0-10010-tuxedo   | 10        | 4.9%    |
| 6.2.0-10011-tuxedo   | 9         | 4.41%   |
| 6.5.0-10008-tuxedo   | 7         | 3.43%   |
| 6.5.0-10006-tuxedo   | 7         | 3.43%   |
| 5.15.0-10058-tuxedo  | 7         | 3.43%   |
| 6.5.0-10031-tuxedo   | 6         | 2.94%   |
| 6.2.0-10010-tuxedo   | 6         | 2.94%   |
| 6.2.0-10027-tuxedo   | 5         | 2.45%   |
| 5.15.0-10048-tuxedo  | 4         | 1.96%   |
| 5.15.0-10053-tuxedo  | 3         | 1.47%   |
| 5.15.0-10052-tuxedo  | 3         | 1.47%   |
| 5.15.0-10057-tuxedo  | 2         | 0.98%   |
| 5.15.0-10056-tuxedo  | 2         | 0.98%   |
| 5.15.0-10050-tuxedo  | 2         | 0.98%   |
| 6.5.4-060504-generic | 1         | 0.49%   |
| 6.5.0-1014-oem       | 1         | 0.49%   |
| 6.2.0-10014-tuxedo   | 1         | 0.49%   |
| 6.0.0-1010-oem       | 1         | 0.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.5.0   | 87        | 43.72%  |
| 6.2.0   | 70        | 35.18%  |
| 5.15.0  | 23        | 11.56%  |
| 6.1.0   | 17        | 8.54%   |
| 6.5.4   | 1         | 0.5%    |
| 6.0.0   | 1         | 0.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.5     | 88        | 44.22%  |
| 6.2     | 70        | 35.18%  |
| 5.15    | 23        | 11.56%  |
| 6.1     | 17        | 8.54%   |
| 6.0     | 1         | 0.5%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 189       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE5       | 180       | 95.24%  |
| KDE6       | 8         | 4.23%   |
| X-Cinnamon | 1         | 0.53%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 178       | 93.19%  |
| Wayland | 13        | 6.81%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 144       | 75.39%  |
| SDDM    | 47        | 24.61%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| de_DE | 66        | 34.92%  |
| en_US | 57        | 30.16%  |
| en_GB | 15        | 7.94%   |
| it_IT | 8         | 4.23%   |
| fr_FR | 4         | 2.12%   |
| pt_PT | 3         | 1.59%   |
| pl_PL | 3         | 1.59%   |
| en_ZA | 3         | 1.59%   |
| en_CA | 3         | 1.59%   |
| en_AU | 3         | 1.59%   |
| en_AG | 3         | 1.59%   |
| nb_NO | 2         | 1.06%   |
| hu_HU | 2         | 1.06%   |
| en_IN | 2         | 1.06%   |
| de_CH | 2         | 1.06%   |
| de_AT | 2         | 1.06%   |
| tr_TR | 1         | 0.53%   |
| pt_BR | 1         | 0.53%   |
| nl_NL | 1         | 0.53%   |
| nl_BE | 1         | 0.53%   |
| fi_FI | 1         | 0.53%   |
| et_EE | 1         | 0.53%   |
| es_MX | 1         | 0.53%   |
| es_ES | 1         | 0.53%   |
| en_DK | 1         | 0.53%   |
| da_DK | 1         | 0.53%   |
| cs_CZ | 1         | 0.53%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 148       | 77.89%  |
| EFI  | 42        | 22.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 162       | 84.82%  |
| Btrfs   | 17        | 8.9%    |
| Overlay | 6         | 3.14%   |
| Tmpfs   | 4         | 2.09%   |
| Xfs     | 2         | 1.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 144       | 75.39%  |
| GPT     | 44        | 23.04%  |
| MBR     | 3         | 1.57%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 181       | 95.26%  |
| Yes       | 9         | 4.74%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 177       | 93.16%  |
| Yes       | 13        | 6.84%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| TUXEDO              | 52        | 27.51%  |
| Lenovo              | 25        | 13.23%  |
| Hewlett-Packard     | 23        | 12.17%  |
| ASUSTek Computer    | 18        | 9.52%   |
| Dell                | 17        | 8.99%   |
| MSI                 | 12        | 6.35%   |
| Apple               | 8         | 4.23%   |
| Gigabyte Technology | 6         | 3.17%   |
| Acer                | 6         | 3.17%   |
| ASRock              | 5         | 2.65%   |
| Toshiba             | 2         | 1.06%   |
| Schenker            | 2         | 1.06%   |
| Notebook            | 2         | 1.06%   |
| BESSTAR Tech        | 2         | 1.06%   |
| Wortmann AG         | 1         | 0.53%   |
| Samsung Electronics | 1         | 0.53%   |
| Metabox             | 1         | 0.53%   |
| Intel               | 1         | 0.53%   |
| Fujitsu             | 1         | 0.53%   |
| Fanless Mini PC     | 1         | 0.53%   |
| ECS                 | 1         | 0.53%   |
| Chuwi               | 1         | 0.53%   |
| Unknown             | 1         | 0.53%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| TUXEDO Sirius 16 Gen1              | 4         | 2.12%   |
| TUXEDO InfinityBook S 15/17 Gen7   | 4         | 2.12%   |
| TUXEDO InfinityBook Pro 14 Gen6    | 4         | 2.12%   |
| Unknown                            | 4         | 2.12%   |
| TUXEDO Stellaris/Polaris AMD Gen4  | 3         | 1.59%   |
| TUXEDO Stellaris Intel Gen5        | 3         | 1.59%   |
| TUXEDO Pulse 15 Gen1               | 3         | 1.59%   |
| TUXEDO InfinityBook Pro Gen7 (MK1) | 3         | 1.59%   |
| TUXEDO Aura 15 Gen2                | 3         | 1.59%   |
| ASUS PRIME B450-PLUS               | 3         | 1.59%   |
| TUXEDO XMG FUSION 15 (XFU15L19)    | 2         | 1.06%   |
| TUXEDO Pulse 15 Gen2               | 2         | 1.06%   |
| TUXEDO Polaris AMD Gen5            | 2         | 1.06%   |
| TUXEDO Polaris 15 AMD Gen1         | 2         | 1.06%   |
| TUXEDO InfinityBook S 15 Gen6      | 2         | 1.06%   |
| TUXEDO InfinityBook Pro Gen7 (MK2) | 2         | 1.06%   |
| MSI MS-7D17                        | 2         | 1.06%   |
| Dell Latitude E6540                | 2         | 1.06%   |
| ASUS ROG STRIX B550-I GAMING       | 2         | 1.06%   |
| Apple MacBookPro8,1                | 2         | 1.06%   |
| Wortmann AG 1220595_1470122        | 1         | 0.53%   |
| TUXEDO XP1610                      | 1         | 0.53%   |
| TUXEDO Stellaris AMD Gen3 (CZN)    | 1         | 0.53%   |
| TUXEDO Polaris AMD Gen3 (CZN)      | 1         | 0.53%   |
| TUXEDO P64_HJ,HK1                  | 1         | 0.53%   |
| TUXEDO N7x0WU                      | 1         | 0.53%   |
| TUXEDO N13xWU                      | 1         | 0.53%   |
| TUXEDO InfinityBook S Gen8         | 1         | 0.53%   |
| TUXEDO InfinityBook Pro Gen8 (MK1) | 1         | 0.53%   |
| TUXEDO Book XUX7 Gen13             | 1         | 0.53%   |
| TUXEDO Book XP15 / XP17 Gen12      | 1         | 0.53%   |
| Toshiba Satellite A665             | 1         | 0.53%   |
| Toshiba PORTEGE Z10T-A             | 1         | 0.53%   |
| Schenker VISION 16 Pro (L22)       | 1         | 0.53%   |
| Schenker VISION 15 E23 (SVS15E23)  | 1         | 0.53%   |
| Samsung RC530/RC730                | 1         | 0.53%   |
| Notebook W65_W67RB                 | 1         | 0.53%   |
| Notebook NP5x_NP6x_NP7xHP          | 1         | 0.53%   |
| MSI Vector GP78HX 13VG             | 1         | 0.53%   |
| MSI Prestige 15 A10SC              | 1         | 0.53%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| TUXEDO InfinityBook | 17        | 8.99%   |
| Lenovo ThinkPad     | 11        | 5.82%   |
| TUXEDO Stellaris    | 7         | 3.7%    |
| HP Pavilion         | 7         | 3.7%    |
| Dell Latitude       | 7         | 3.7%    |
| TUXEDO Pulse        | 5         | 2.65%   |
| TUXEDO Polaris      | 5         | 2.65%   |
| ASUS ROG            | 5         | 2.65%   |
| ASUS PRIME          | 5         | 2.65%   |
| TUXEDO Sirius       | 4         | 2.12%   |
| Lenovo Yoga         | 4         | 2.12%   |
| Dell Inspiron       | 4         | 2.12%   |
| Unknown             | 4         | 2.12%   |
| TUXEDO Aura         | 3         | 1.59%   |
| HP Laptop           | 3         | 1.59%   |
| Dell Precision      | 3         | 1.59%   |
| TUXEDO XMG          | 2         | 1.06%   |
| TUXEDO Book         | 2         | 1.06%   |
| Schenker VISION     | 2         | 1.06%   |
| MSI MS-7D17         | 2         | 1.06%   |
| Lenovo ThinkCentre  | 2         | 1.06%   |
| Lenovo ThinkBook    | 2         | 1.06%   |
| Lenovo Legion       | 2         | 1.06%   |
| Lenovo IdeaPad      | 2         | 1.06%   |
| HP ENVY             | 2         | 1.06%   |
| HP EliteBook        | 2         | 1.06%   |
| HP 250              | 2         | 1.06%   |
| Apple MacBookPro8   | 2         | 1.06%   |
| Acer Swift          | 2         | 1.06%   |
| Acer Nitro          | 2         | 1.06%   |
| Wortmann AG 1220595 | 1         | 0.53%   |
| TUXEDO XP1610       | 1         | 0.53%   |
| TUXEDO P64          | 1         | 0.53%   |
| TUXEDO N7x0WU       | 1         | 0.53%   |
| TUXEDO N13xWU       | 1         | 0.53%   |
| Toshiba Satellite   | 1         | 0.53%   |
| Toshiba PORTEGE     | 1         | 0.53%   |
| Samsung RC530       | 1         | 0.53%   |
| Notebook W65        | 1         | 0.53%   |
| Notebook NP5x       | 1         | 0.53%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2022 | 33        | 17.46%  |
| 2020 | 27        | 14.29%  |
| 2021 | 21        | 11.11%  |
| 2023 | 17        | 8.99%   |
| 2015 | 14        | 7.41%   |
| 2019 | 12        | 6.35%   |
| 2017 | 11        | 5.82%   |
| 2018 | 10        | 5.29%   |
| 2012 | 9         | 4.76%   |
| 2013 | 8         | 4.23%   |
| 2011 | 7         | 3.7%    |
| 2024 | 4         | 2.12%   |
| 2014 | 4         | 2.12%   |
| 2010 | 3         | 1.59%   |
| 2009 | 3         | 1.59%   |
| 2008 | 3         | 1.59%   |
| 2016 | 2         | 1.06%   |
| 2007 | 1         | 0.53%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 142       | 75.13%  |
| Desktop     | 39        | 20.63%  |
| Convertible | 5         | 2.65%   |
| Mini pc     | 2         | 1.06%   |
| Tablet      | 1         | 0.53%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 189       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 189       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 47        | 24.87%  |
| 16.01-24.0  | 41        | 21.69%  |
| 4.01-8.0    | 36        | 19.05%  |
| 8.01-16.0   | 26        | 13.76%  |
| 64.01-256.0 | 18        | 9.52%   |
| 3.01-4.0    | 14        | 7.41%   |
| 24.01-32.0  | 7         | 3.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 59        | 29.5%   |
| 2.01-3.0   | 51        | 25.5%   |
| 1.01-2.0   | 39        | 19.5%   |
| 3.01-4.0   | 32        | 16%     |
| 8.01-16.0  | 16        | 8%      |
| 16.01-24.0 | 3         | 1.5%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 105       | 54.97%  |
| 2      | 57        | 29.84%  |
| 4      | 10        | 5.24%   |
| 3      | 10        | 5.24%   |
| 5      | 7         | 3.66%   |
| 6      | 1         | 0.52%   |
| 0      | 1         | 0.52%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 152       | 80%     |
| Yes       | 38        | 20%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 161       | 85.19%  |
| No        | 28        | 14.81%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 173       | 91.53%  |
| No        | 16        | 8.47%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 160       | 84.21%  |
| No        | 30        | 15.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| Germany                | 74        | 39.15%  |
| USA                    | 27        | 14.29%  |
| Italy                  | 8         | 4.23%   |
| UK                     | 7         | 3.7%    |
| Switzerland            | 5         | 2.65%   |
| Portugal               | 5         | 2.65%   |
| Netherlands            | 5         | 2.65%   |
| France                 | 5         | 2.65%   |
| Turkey                 | 4         | 2.12%   |
| Austria                | 4         | 2.12%   |
| South Africa           | 3         | 1.59%   |
| Poland                 | 3         | 1.59%   |
| Czechia                | 3         | 1.59%   |
| Australia              | 3         | 1.59%   |
| Spain                  | 2         | 1.06%   |
| Romania                | 2         | 1.06%   |
| Norway                 | 2         | 1.06%   |
| Indonesia              | 2         | 1.06%   |
| India                  | 2         | 1.06%   |
| Hungary                | 2         | 1.06%   |
| Denmark                | 2         | 1.06%   |
| Canada                 | 2         | 1.06%   |
| Brazil                 | 2         | 1.06%   |
| Bosnia and Herzegovina | 2         | 1.06%   |
| Belgium                | 2         | 1.06%   |
| Tunisia                | 1         | 0.53%   |
| Thailand               | 1         | 0.53%   |
| Slovakia               | 1         | 0.53%   |
| Panama                 | 1         | 0.53%   |
| Mexico                 | 1         | 0.53%   |
| Finland                | 1         | 0.53%   |
| Estonia                | 1         | 0.53%   |
| Egypt                  | 1         | 0.53%   |
| Bulgaria               | 1         | 0.53%   |
| Aruba                  | 1         | 0.53%   |
| Argentina              | 1         | 0.53%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Munich             | 7         | 3.65%   |
| Berlin             | 4         | 2.08%   |
| Vienna             | 3         | 1.56%   |
| Prague             | 3         | 1.56%   |
| Zurich             | 2         | 1.04%   |
| Wolfsburg          | 2         | 1.04%   |
| Schweinfurt        | 2         | 1.04%   |
| Rome               | 2         | 1.04%   |
| Nuremberg          | 2         | 1.04%   |
| Lucerne            | 2         | 1.04%   |
| Los Angeles        | 2         | 1.04%   |
| Leipzig            | 2         | 1.04%   |
| Langevag           | 2         | 1.04%   |
| Kiel               | 2         | 1.04%   |
| Johannesburg       | 2         | 1.04%   |
| Jakarta            | 2         | 1.04%   |
| Istanbul           | 2         | 1.04%   |
| Hürth             | 2         | 1.04%   |
| Hamburg            | 2         | 1.04%   |
| Duisburg           | 2         | 1.04%   |
| Brisbane           | 2         | 1.04%   |
| Astoria            | 2         | 1.04%   |
| Amsterdam          | 2         | 1.04%   |
| Zonguldak          | 1         | 0.52%   |
| Zalău             | 1         | 0.52%   |
| Zabrze             | 1         | 0.52%   |
| Wunstorf           | 1         | 0.52%   |
| Wembley            | 1         | 0.52%   |
| Watertown          | 1         | 0.52%   |
| Warsaw             | 1         | 0.52%   |
| Walsall            | 1         | 0.52%   |
| Venlo              | 1         | 0.52%   |
| Vallejo            | 1         | 0.52%   |
| Ulm                | 1         | 0.52%   |
| Turin              | 1         | 0.52%   |
| Teslic             | 1         | 0.52%   |
| Temple             | 1         | 0.52%   |
| Tallinn            | 1         | 0.52%   |
| Stuttgart          | 1         | 0.52%   |
| Stockstadt am Main | 1         | 0.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 91        | 131    | 32.73%  |
| Seagate                     | 23        | 29     | 8.27%   |
| SanDisk                     | 23        | 28     | 8.27%   |
| Kingston                    | 16        | 18     | 5.76%   |
| WDC                         | 13        | 15     | 4.68%   |
| SK hynix                    | 9         | 12     | 3.24%   |
| Micron Technology           | 9         | 10     | 3.24%   |
| Toshiba                     | 8         | 9      | 2.88%   |
| Hitachi                     | 8         | 13     | 2.88%   |
| Crucial                     | 7         | 8      | 2.52%   |
| Unknown                     | 6         | 7      | 2.16%   |
| Micron/Crucial Technology   | 5         | 7      | 1.8%    |
| Phison Electronics          | 4         | 4      | 1.44%   |
| Apple                       | 4         | 4      | 1.44%   |
| SPCC                        | 3         | 3      | 1.08%   |
| Intenso                     | 3         | 4      | 1.08%   |
| Intel                       | 3         | 3      | 1.08%   |
| HGST                        | 3         | 5      | 1.08%   |
| Phison                      | 2         | 4      | 0.72%   |
| Netac                       | 2         | 2      | 0.72%   |
| KIOXIA                      | 2         | 3      | 0.72%   |
| Kingston Technology Company | 2         | 2      | 0.72%   |
| GOODRAM                     | 2         | 2      | 0.72%   |
| Fanxiang                    | 2         | 2      | 0.72%   |
| ASMT                        | 2         | 2      | 0.72%   |
| WALRAM                      | 1         | 1      | 0.36%   |
| USB3.0                      | 1         | 1      | 0.36%   |
| Transcend                   | 1         | 1      | 0.36%   |
| Team                        | 1         | 1      | 0.36%   |
| Silicon Motion              | 1         | 2      | 0.36%   |
| S3+                         | 1         | 1      | 0.36%   |
| OWC                         | 1         | 1      | 0.36%   |
| LITEONIT                    | 1         | 1      | 0.36%   |
| Lite-On Technology          | 1         | 1      | 0.36%   |
| Lexar                       | 1         | 1      | 0.36%   |
| Lenovo                      | 1         | 1      | 0.36%   |
| KingFast                    | 1         | 1      | 0.36%   |
| Kingchuxing                 | 1         | 1      | 0.36%   |
| HS-SSD-E100                 | 1         | 1      | 0.36%   |
| HS-SSD-E                    | 1         | 1      | 0.36%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 17        | 5.56%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 14        | 4.58%   |
| Samsung SSD 980 1TB                                | 13        | 4.25%   |
| Samsung SSD 980 500GB                              | 10        | 3.27%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB   | 7         | 2.29%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                | 5         | 1.63%   |
| Kingston SA400S37240G 240GB SSD                    | 5         | 1.63%   |
| Seagate ST1000DM010-2EP102 1TB                     | 4         | 1.31%   |
| Sandisk WD Blue SN570 1TB                          | 3         | 0.98%   |
| Samsung SSD 990 PRO 1TB                            | 3         | 0.98%   |
| Samsung SSD 980 PRO 1TB                            | 3         | 0.98%   |
| Samsung SSD 970 EVO Plus 1TB                       | 3         | 0.98%   |
| Samsung SSD 860 EVO 250GB                          | 3         | 0.98%   |
| Samsung SSD 850 EVO 500GB                          | 3         | 0.98%   |
| Samsung SSD 850 EVO 1TB                            | 3         | 0.98%   |
| Toshiba MQ01ABD100 1TB                             | 2         | 0.65%   |
| Seagate ST3500418AS 500GB                          | 2         | 0.65%   |
| Seagate ST1000VT001-1RE172 1TB                     | 2         | 0.65%   |
| Sandisk WD Black SN850 512GB                       | 2         | 0.65%   |
| SanDisk SSD PLUS 120GB                             | 2         | 0.65%   |
| SanDisk SDSSDA240G 240GB                           | 2         | 0.65%   |
| Samsung SSD 990 PRO 2TB                            | 2         | 0.65%   |
| Samsung SSD 980 PRO 500GB                          | 2         | 0.65%   |
| Samsung SSD 980 PRO 2TB                            | 2         | 0.65%   |
| Samsung SSD 870 EVO 2TB                            | 2         | 0.65%   |
| Samsung SSD 860 EVO 500GB                          | 2         | 0.65%   |
| Phison E16 PCIe4 NVMe Controller 1TB               | 2         | 0.65%   |
| Kingston SA400S37480G 480GB SSD                    | 2         | 0.65%   |
| Intenso SSD SATAIII 240GB                          | 2         | 0.65%   |
| Hitachi HTS727550A9E364 500GB                      | 2         | 0.65%   |
| Hitachi HCS545050GLA380 500GB                      | 2         | 0.65%   |
| Crucial CT1000MX500SSD1 1TB                        | 2         | 0.65%   |
| Crucial CT1000BX500SSD1 1TB                        | 2         | 0.65%   |
| Apple SSD SM0512G 500GB                            | 2         | 0.65%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                   | 1         | 0.33%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 1         | 0.33%   |
| WDC WD80EAZZ-00BKLB0 8TB                           | 1         | 0.33%   |
| WDC WD5000AAKX-60U6AA0 500GB                       | 1         | 0.33%   |
| WDC WD5000AAKX-08ERMA0 500GB                       | 1         | 0.33%   |
| WDC WD3200BPVT-24JJ5T0 320GB                       | 1         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 22        | 28     | 44%     |
| WDC                 | 9         | 11     | 18%     |
| Hitachi             | 8         | 13     | 16%     |
| Toshiba             | 4         | 4      | 8%      |
| HGST                | 3         | 5      | 6%      |
| Samsung Electronics | 2         | 2      | 4%      |
| Unknown             | 1         | 2      | 2%      |
| HGST HTS            | 1         | 1      | 2%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21        | 24     | 26.92%  |
| Kingston            | 10        | 12     | 12.82%  |
| SanDisk             | 7         | 9      | 8.97%   |
| Crucial             | 7         | 7      | 8.97%   |
| WDC                 | 4         | 4      | 5.13%   |
| Apple               | 4         | 4      | 5.13%   |
| SPCC                | 2         | 2      | 2.56%   |
| Netac               | 2         | 2      | 2.56%   |
| Micron Technology   | 2         | 2      | 2.56%   |
| Intenso             | 2         | 2      | 2.56%   |
| GOODRAM             | 2         | 2      | 2.56%   |
| ASMT                | 2         | 2      | 2.56%   |
| USB3.0              | 1         | 1      | 1.28%   |
| Transcend           | 1         | 1      | 1.28%   |
| Toshiba             | 1         | 1      | 1.28%   |
| Team                | 1         | 1      | 1.28%   |
| SK hynix            | 1         | 2      | 1.28%   |
| S3+                 | 1         | 1      | 1.28%   |
| OWC                 | 1         | 1      | 1.28%   |
| LITEONIT            | 1         | 1      | 1.28%   |
| Lexar               | 1         | 1      | 1.28%   |
| CT1000BX            | 1         | 1      | 1.28%   |
| China               | 1         | 1      | 1.28%   |
| Apacer              | 1         | 1      | 1.28%   |
| A-DATA Technology   | 1         | 2      | 1.28%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 127       | 190    | 50.6%   |
| SSD     | 66        | 87     | 26.29%  |
| HDD     | 45        | 66     | 17.93%  |
| Unknown | 7         | 9      | 2.79%   |
| MMC     | 6         | 6      | 2.39%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 127       | 189    | 53.81%  |
| SATA | 92        | 146    | 38.98%  |
| SAS  | 11        | 17     | 4.66%   |
| MMC  | 6         | 6      | 2.54%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 63        | 90     | 53.39%  |
| 0.51-1.0   | 40        | 44     | 33.9%   |
| 1.01-2.0   | 10        | 13     | 8.47%   |
| 4.01-10.0  | 3         | 3      | 2.54%   |
| 3.01-4.0   | 1         | 2      | 0.85%   |
| 2.01-3.0   | 1         | 1      | 0.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 49        | 25.13%  |
| 251-500        | 40        | 20.51%  |
| 101-250        | 38        | 19.49%  |
| 1001-2000      | 28        | 14.36%  |
| 2001-3000      | 10        | 5.13%   |
| 1-20           | 10        | 5.13%   |
| More than 3000 | 6         | 3.08%   |
| 51-100         | 6         | 3.08%   |
| Unknown        | 5         | 2.56%   |
| 21-50          | 3         | 1.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 62        | 31.47%  |
| 21-50          | 49        | 24.87%  |
| 101-250        | 28        | 14.21%  |
| 501-1000       | 16        | 8.12%   |
| 51-100         | 16        | 8.12%   |
| 251-500        | 14        | 7.11%   |
| 1001-2000      | 5         | 2.54%   |
| Unknown        | 5         | 2.54%   |
| More than 3000 | 1         | 0.51%   |
| 2001-3000      | 1         | 0.51%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| WDC PC SA530 SDASN8Y-256G-1006 256GB SSD | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor | Computers | Drives | Percent |
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


| Kind | Computers | Drives | Percent |
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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 146       | 293    | 75.65%  |
| Works    | 46        | 64     | 23.83%  |
| Malfunc  | 1         | 1      | 0.52%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 92        | 34.85%  |
| Samsung Electronics          | 76        | 28.79%  |
| AMD                          | 29        | 10.98%  |
| SanDisk                      | 16        | 6.06%   |
| SK hynix                     | 8         | 3.03%   |
| Kingston Technology Company  | 8         | 3.03%   |
| Micron Technology            | 7         | 2.65%   |
| Phison Electronics           | 6         | 2.27%   |
| Micron/Crucial Technology    | 5         | 1.89%   |
| Toshiba America Info Systems | 3         | 1.14%   |
| Silicon Motion               | 2         | 0.76%   |
| Nvidia                       | 2         | 0.76%   |
| KIOXIA                       | 2         | 0.76%   |
| Seagate Technology           | 1         | 0.38%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.38%   |
| Marvell Technology Group     | 1         | 0.38%   |
| Lite-On Technology           | 1         | 0.38%   |
| Lenovo                       | 1         | 0.38%   |
| INNOGRIT                     | 1         | 0.38%   |
| ASMedia Technology           | 1         | 0.38%   |
| ADATA Technology             | 1         | 0.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller 980 (DRAM-less)                                   | 27        | 9.34%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 24        | 8.3%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 22        | 7.61%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 20        | 6.92%   |
| Intel Volume Management Device NVMe RAID Controller                           | 8         | 2.77%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 8         | 2.77%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                          | 8         | 2.77%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD          | 7         | 2.42%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                         | 5         | 1.73%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)          | 5         | 1.73%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 5         | 1.73%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 5         | 1.73%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 5         | 1.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 5         | 1.73%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                          | 4         | 1.38%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                   | 4         | 1.38%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 4         | 1.38%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 4         | 1.38%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                          | 4         | 1.38%   |
| AMD 500 Series Chipset SATA Controller                                        | 4         | 1.38%   |
| AMD 400 Series Chipset SATA Controller                                        | 4         | 1.38%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                    | 3         | 1.04%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 3         | 1.04%   |
| Phison E16 PCIe4 NVMe Controller                                              | 3         | 1.04%   |
| Kingston Company NV1 NVMe SSD SM2263XT (DRAM-less)                            | 3         | 1.04%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 3         | 1.04%   |
| Intel Alder Lake-P SATA AHCI Controller                                       | 3         | 1.04%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 3         | 1.04%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                            | 2         | 0.69%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                   | 2         | 0.69%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                 | 2         | 0.69%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                    | 2         | 0.69%   |
| Phison E12 NVMe Controller                                                    | 2         | 0.69%   |
| Micron 3400 NVMe SSD [Hendrix]                                                | 2         | 0.69%   |
| Micron 2400 NVMe SSD (DRAM-less)                                              | 2         | 0.69%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                            | 2         | 0.69%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation         | 2         | 0.69%   |
| Intel SATA Controller [RAID mode]                                             | 2         | 0.69%   |
| Intel Comet Lake SATA AHCI Controller                                         | 2         | 0.69%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 2         | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 127       | 49.03%  |
| SATA | 111       | 42.86%  |
| RAID | 17        | 6.56%   |
| IDE  | 4         | 1.54%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 136       | 71.96%  |
| AMD    | 53        | 28.04%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 12th Gen Core i7-12700H                 | 7         | 3.7%    |
| AMD Ryzen 7 7840HS w/ Radeon 780M Graphics    | 6         | 3.17%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz       | 5         | 2.65%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 2.12%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 2.12%   |
| Intel 12th Gen Core i7-1260P                  | 4         | 2.12%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 4         | 2.12%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.59%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 3         | 1.59%   |
| Intel 13th Gen Core i9-13900HX                | 3         | 1.59%   |
| Intel 12th Gen Core i5-1240P                  | 3         | 1.59%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.06%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 2         | 1.06%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 2         | 1.06%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 1.06%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 2         | 1.06%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 1.06%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 1.06%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 1.06%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.06%   |
| Intel 13th Gen Core i7-1360P                  | 2         | 1.06%   |
| Intel 12th Gen Core i7-1255U                  | 2         | 1.06%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.06%   |
| AMD Ryzen 9 6900HX with Radeon Graphics       | 2         | 1.06%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 2         | 1.06%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 1.06%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 2         | 1.06%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 1.06%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 1.06%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.06%   |
| AMD Ryzen 3 5300U with Radeon Graphics        | 2         | 1.06%   |
| Intel Xeon W-10855M CPU @ 2.80GHz             | 1         | 0.53%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 0.53%   |
| Intel Pentium CPU G3420 @ 3.20GHz             | 1         | 0.53%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 0.53%   |
| Intel N100                                    | 1         | 0.53%   |
| Intel Core m5-6Y54 CPU @ 1.10GHz              | 1         | 0.53%   |
| Intel Core i9-10900KF CPU @ 3.70GHz           | 1         | 0.53%   |
| Intel Core i9-10850K CPU @ 3.60GHz            | 1         | 0.53%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 1         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Other             | 48        | 25.4%   |
| Intel Core i7     | 38        | 20.11%  |
| Intel Core i5     | 30        | 15.87%  |
| AMD Ryzen 7       | 24        | 12.7%   |
| AMD Ryzen 5       | 14        | 7.41%   |
| Intel Core i3     | 6         | 3.17%   |
| Intel Celeron     | 4         | 2.12%   |
| AMD Ryzen 3       | 4         | 2.12%   |
| AMD Ryzen 9       | 3         | 1.59%   |
| Intel Xeon        | 2         | 1.06%   |
| Intel Pentium     | 2         | 1.06%   |
| Intel Core i9     | 2         | 1.06%   |
| Intel Core 2 Duo  | 2         | 1.06%   |
| AMD A8            | 2         | 1.06%   |
| AMD A10           | 2         | 1.06%   |
| Intel Core m5     | 1         | 0.53%   |
| Intel Core 2 Quad | 1         | 0.53%   |
| AMD Turion II     | 1         | 0.53%   |
| AMD Ryzen 7 PRO   | 1         | 0.53%   |
| AMD Ryzen 5 PRO   | 1         | 0.53%   |
| AMD Phenom II X2  | 1         | 0.53%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 56        | 29.63%  |
| 2      | 39        | 20.63%  |
| 8      | 32        | 16.93%  |
| 6      | 30        | 15.87%  |
| 14     | 11        | 5.82%   |
| 12     | 11        | 5.82%   |
| 10     | 5         | 2.65%   |
| 24     | 3         | 1.59%   |
| 16     | 2         | 1.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 189       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 166       | 87.83%  |
| 1      | 23        | 12.17%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 189       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 170       | 88.54%  |
| 0x0a704103 | 3         | 1.56%   |
| 0x906a4    | 2         | 1.04%   |
| 0x0a404102 | 2         | 1.04%   |
| 0x08608103 | 2         | 1.04%   |
| 0xa0653    | 1         | 0.52%   |
| 0x906ea    | 1         | 0.52%   |
| 0x906e9    | 1         | 0.52%   |
| 0x906a3    | 1         | 0.52%   |
| 0x806c1    | 1         | 0.52%   |
| 0x306d4    | 1         | 0.52%   |
| 0x0a704101 | 1         | 0.52%   |
| 0x0a50000d | 1         | 0.52%   |
| 0x0a50000c | 1         | 0.52%   |
| 0x08701030 | 1         | 0.52%   |
| 0x08701021 | 1         | 0.52%   |
| 0x08600106 | 1         | 0.52%   |
| 0x010000c8 | 1         | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 45        | 23.81%  |
| KabyLake         | 24        | 12.7%   |
| Zen 2            | 15        | 7.94%   |
| CometLake        | 13        | 6.88%   |
| IvyBridge        | 12        | 6.35%   |
| Alderlake Hybrid | 11        | 5.82%   |
| TigerLake        | 9         | 4.76%   |
| Haswell          | 9         | 4.76%   |
| Zen 3            | 8         | 4.23%   |
| Skylake          | 8         | 4.23%   |
| Broadwell        | 7         | 3.7%    |
| SandyBridge      | 6         | 3.17%   |
| Zen+             | 4         | 2.12%   |
| Westmere         | 3         | 1.59%   |
| Penryn           | 3         | 1.59%   |
| Zen              | 2         | 1.06%   |
| Piledriver       | 2         | 1.06%   |
| K10              | 2         | 1.06%   |
| Goldmont plus    | 2         | 1.06%   |
| Silvermont       | 1         | 0.53%   |
| Puma             | 1         | 0.53%   |
| Gracemont        | 1         | 0.53%   |
| Excavator        | 1         | 0.53%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 117       | 47.95%  |
| Nvidia | 74        | 30.33%  |
| AMD    | 53        | 21.72%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 14        | 5.56%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 11        | 4.37%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 9         | 3.57%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 8         | 3.17%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 7         | 2.78%   |
| Intel UHD Graphics 620                                                      | 7         | 2.78%   |
| AMD Phoenix1                                                                | 7         | 2.78%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 6         | 2.38%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                      | 6         | 2.38%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 6         | 2.38%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6         | 2.38%   |
| AMD Rembrandt [Radeon 680M]                                                 | 6         | 2.38%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 6         | 2.38%   |
| Intel HD Graphics 5500                                                      | 5         | 1.98%   |
| AMD Navi 33 [Radeon RX 7700S/7600/7600S/7600M XT/PRO W7600]                 | 5         | 1.98%   |
| AMD Lucienne                                                                | 5         | 1.98%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                    | 4         | 1.59%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 4         | 1.59%   |
| Intel HD Graphics 630                                                       | 4         | 1.59%   |
| Intel HD Graphics 530                                                       | 4         | 1.59%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 4         | 1.59%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 3         | 1.19%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3         | 1.19%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 3         | 1.19%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                               | 3         | 1.19%   |
| Nvidia AD106M [GeForce RTX 4070 Max-Q / Mobile]                             | 3         | 1.19%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 3         | 1.19%   |
| Intel Raptor Lake-S UHD Graphics                                            | 3         | 1.19%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3         | 1.19%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 2         | 0.79%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 2         | 0.79%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2         | 0.79%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2         | 0.79%   |
| Nvidia GF108M [GeForce GT 635M]                                             | 2         | 0.79%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                  | 2         | 0.79%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                             | 2         | 0.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 0.79%   |
| Intel Haswell-ULT Integrated Graphics Controller [HD Graphics]              | 2         | 0.79%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 0.79%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2         | 0.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 75        | 39.47%  |
| Intel + Nvidia | 35        | 18.42%  |
| 1 x AMD        | 28        | 14.74%  |
| 1 x Nvidia     | 26        | 13.68%  |
| AMD + Nvidia   | 13        | 6.84%   |
| 2 x AMD        | 7         | 3.68%   |
| Intel + AMD    | 6         | 3.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 128       | 67.37%  |
| Proprietary | 60        | 31.58%  |
| Unknown     | 2         | 1.05%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 133       | 69.63%  |
| 7.01-8.0   | 18        | 9.42%   |
| 5.01-6.0   | 15        | 7.85%   |
| 3.01-4.0   | 10        | 5.24%   |
| 1.01-2.0   | 5         | 2.62%   |
| 8.01-16.0  | 5         | 2.62%   |
| 0.01-0.5   | 4         | 2.09%   |
| 0.51-1.0   | 1         | 0.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| BOE                  | 52        | 23.11%  |
| AU Optronics         | 29        | 12.89%  |
| Samsung Electronics  | 25        | 11.11%  |
| LG Display           | 14        | 6.22%   |
| Chimei Innolux       | 14        | 6.22%   |
| Dell                 | 10        | 4.44%   |
| Acer                 | 10        | 4.44%   |
| CSO                  | 9         | 4%      |
| Apple                | 8         | 3.56%   |
| Hewlett-Packard      | 7         | 3.11%   |
| Goldstar             | 7         | 3.11%   |
| AOC                  | 6         | 2.67%   |
| BenQ                 | 4         | 1.78%   |
| Lenovo               | 3         | 1.33%   |
| ASUSTek Computer     | 3         | 1.33%   |
| ViewSonic            | 2         | 0.89%   |
| Sharp                | 2         | 0.89%   |
| SGT                  | 2         | 0.89%   |
| NEC Computers        | 2         | 0.89%   |
| InfoVision           | 2         | 0.89%   |
| Iiyama               | 2         | 0.89%   |
| Ancor Communications | 2         | 0.89%   |
| Yamaha               | 1         | 0.44%   |
| VIE                  | 1         | 0.44%   |
| Sony                 | 1         | 0.44%   |
| RTK                  | 1         | 0.44%   |
| Philips              | 1         | 0.44%   |
| PANDA                | 1         | 0.44%   |
| IOD                  | 1         | 0.44%   |
| HUAWEI               | 1         | 0.44%   |
| Fujitsu Siemens      | 1         | 0.44%   |
| Eizo                 | 1         | 0.44%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch               | 7         | 2.97%   |
| BOE LCD Monitor BOE07D8 1920x1080 344x194mm 15.5-inch               | 6         | 2.54%   |
| BOE LCD Monitor BOE09E5 2560x1440 355x200mm 16.0-inch               | 4         | 1.69%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch               | 4         | 1.69%   |
| BOE LCD Monitor BOE084D 1920x1080 344x193mm 15.5-inch               | 4         | 1.69%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch   | 3         | 1.27%   |
| BOE LCD Monitor BOE0AF0 2560x1600 344x215mm 16.0-inch               | 3         | 1.27%   |
| BOE LCD Monitor BOE0A3B 2560x1600 344x215mm 16.0-inch               | 3         | 1.27%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch               | 3         | 1.27%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch            | 2         | 0.85%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch               | 2         | 0.85%   |
| Dell SE2419HR DELF113 1920x1080 530x300mm 24.0-inch                 | 2         | 0.85%   |
| Chimei Innolux LCD Monitor CMN1733 1600x900 382x215mm 17.3-inch     | 2         | 0.85%   |
| Chimei Innolux LCD Monitor CMN1602 1920x1080 355x199mm 16.0-inch    | 2         | 0.85%   |
| Chimei Innolux LCD Monitor CMN15BA 1920x1080 344x194mm 15.5-inch    | 2         | 0.85%   |
| BOE LCD Monitor BOE0B40 2560x1440 344x194mm 15.5-inch               | 2         | 0.85%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch               | 2         | 0.85%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch               | 2         | 0.85%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch      | 2         | 0.85%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch       | 2         | 0.85%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch      | 2         | 0.85%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch              | 2         | 0.85%   |
| Acer EK240Y ACR0758 1920x1080 527x296mm 23.8-inch                   | 2         | 0.85%   |
| Yamaha RX-V473 YMH3171 1920x540                                     | 1         | 0.42%   |
| ViewSonic VX2757 VSCF931 1920x1080 598x336mm 27.0-inch              | 1         | 0.42%   |
| ViewSonic VP2780 SERIES VSC9C30 3840x2160 597x336mm 27.0-inch       | 1         | 0.42%   |
| VIE ATHEN U2L 24 VIE2380 1920x1080 527x296mm 23.8-inch              | 1         | 0.42%   |
| Sony TV SNY4803 1920x1080 930x523mm 42.0-inch                       | 1         | 0.42%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch             | 1         | 0.42%   |
| Sharp LCD Monitor SHP143B 3840x2160 346x194mm 15.6-inch             | 1         | 0.42%   |
| SGT M2145J1F2281 SGT2145 1920x1080 477x268mm 21.5-inch              | 1         | 0.42%   |
| SGT HS156PC SGT9156 1920x1080 345x194mm 15.6-inch                   | 1         | 0.42%   |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch   | 1         | 0.42%   |
| Samsung Electronics SyncMaster SAM0486 1600x900                     | 1         | 0.42%   |
| Samsung Electronics SyncMaster SAM0274 1440x900 410x257mm 19.1-inch | 1         | 0.42%   |
| Samsung Electronics SMB1930HD SAM0708 1360x768 410x230mm 18.5-inch  | 1         | 0.42%   |
| Samsung Electronics SAMTRON STN0022 1280x1024 380x300mm 19.1-inch   | 1         | 0.42%   |
| Samsung Electronics S24R35A SAM729F 1920x1080 527x296mm 23.8-inch   | 1         | 0.42%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch   | 1         | 0.42%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch   | 1         | 0.42%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 100       | 46.51%  |
| 2560x1440 (QHD)    | 22        | 10.23%  |
| 1366x768 (WXGA)    | 20        | 9.3%    |
| 3840x2160 (4K)     | 12        | 5.58%   |
| 2880x1800          | 11        | 5.12%   |
| 2560x1600          | 9         | 4.19%   |
| 1920x1200 (WUXGA)  | 8         | 3.72%   |
| 1600x900 (HD+)     | 7         | 3.26%   |
| 1280x800 (WXGA)    | 5         | 2.33%   |
| 1440x900 (WXGA+)   | 4         | 1.86%   |
| 1280x1024 (SXGA)   | 3         | 1.4%    |
| 3440x1440          | 2         | 0.93%   |
| 3200x1800 (QHD+)   | 2         | 0.93%   |
| 1680x1050 (WSXGA+) | 2         | 0.93%   |
| 3840x2560          | 1         | 0.47%   |
| 3840x1080          | 1         | 0.47%   |
| 2560x1080          | 1         | 0.47%   |
| 2240x1400          | 1         | 0.47%   |
| 2160x1440          | 1         | 0.47%   |
| 1920x540           | 1         | 0.47%   |
| 1360x768           | 1         | 0.47%   |
| Unknown            | 1         | 0.47%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 67        | 29.26%  |
| 27      | 22        | 9.61%   |
| 14      | 20        | 8.73%   |
| 13      | 19        | 8.3%    |
| 24      | 18        | 7.86%   |
| 17      | 18        | 7.86%   |
| 16      | 14        | 6.11%   |
| 23      | 9         | 3.93%   |
| 21      | 6         | 2.62%   |
| 12      | 5         | 2.18%   |
| 19      | 4         | 1.75%   |
| 31      | 3         | 1.31%   |
| 22      | 3         | 1.31%   |
| 20      | 3         | 1.31%   |
| Unknown | 3         | 1.31%   |
| 40      | 2         | 0.87%   |
| 34      | 2         | 0.87%   |
| 18      | 2         | 0.87%   |
| 11      | 2         | 0.87%   |
| 84      | 1         | 0.44%   |
| 60      | 1         | 0.44%   |
| 54      | 1         | 0.44%   |
| 46      | 1         | 0.44%   |
| 43      | 1         | 0.44%   |
| 33      | 1         | 0.44%   |
| 28      | 1         | 0.44%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 99        | 44.8%   |
| 501-600     | 43        | 19.46%  |
| 351-400     | 26        | 11.76%  |
| 201-300     | 21        | 9.5%    |
| 401-500     | 16        | 7.24%   |
| 801-900     | 3         | 1.36%   |
| 601-700     | 3         | 1.36%   |
| 1001-1500   | 3         | 1.36%   |
| Unknown     | 3         | 1.36%   |
| 701-800     | 2         | 0.9%    |
| 1501-2000   | 1         | 0.45%   |
| 901-1000    | 1         | 0.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 152       | 75.25%  |
| 16/10   | 39        | 19.31%  |
| 5/4     | 3         | 1.49%   |
| 3/2     | 3         | 1.49%   |
| 21/9    | 3         | 1.49%   |
| 32/9    | 1         | 0.5%    |
| Unknown | 1         | 0.5%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 71        | 31.14%  |
| 81-90          | 31        | 13.6%   |
| 301-350        | 22        | 9.65%   |
| 201-250        | 22        | 9.65%   |
| 121-130        | 15        | 6.58%   |
| 151-200        | 11        | 4.82%   |
| 111-120        | 10        | 4.39%   |
| 251-300        | 9         | 3.95%   |
| 71-80          | 8         | 3.51%   |
| 351-500        | 7         | 3.07%   |
| 61-70          | 5         | 2.19%   |
| 501-1000       | 4         | 1.75%   |
| More than 1000 | 3         | 1.32%   |
| 141-150        | 3         | 1.32%   |
| Unknown        | 3         | 1.32%   |
| 51-60          | 2         | 0.88%   |
| 131-140        | 2         | 0.88%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 70        | 31.96%  |
| 51-100        | 50        | 22.83%  |
| 101-120       | 43        | 19.63%  |
| 161-240       | 34        | 15.53%  |
| More than 240 | 16        | 7.31%   |
| 1-50          | 3         | 1.37%   |
| Unknown       | 3         | 1.37%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 142       | 74.35%  |
| 2     | 40        | 20.94%  |
| 3     | 7         | 3.66%   |
| 0     | 2         | 1.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 133       | 41.56%  |
| Realtek Semiconductor             | 123       | 38.44%  |
| Qualcomm Atheros                  | 11        | 3.44%   |
| Broadcom                          | 10        | 3.13%   |
| Ralink Technology                 | 6         | 1.88%   |
| DisplayLink                       | 5         | 1.56%   |
| Broadcom Limited                  | 5         | 1.56%   |
| MediaTek                          | 4         | 1.25%   |
| Huawei Technologies               | 4         | 1.25%   |
| ASIX Electronics                  | 4         | 1.25%   |
| TP-Link                           | 2         | 0.63%   |
| Sierra Wireless                   | 2         | 0.63%   |
| Ralink                            | 2         | 0.63%   |
| D-Link                            | 2         | 0.63%   |
| Samsung Electronics               | 1         | 0.31%   |
| OPPO Electronics                  | 1         | 0.31%   |
| Nvidia                            | 1         | 0.31%   |
| NetGear                           | 1         | 0.31%   |
| Lenovo                            | 1         | 0.31%   |
| Ericsson Business Mobile Networks | 1         | 0.31%   |
| Dell                              | 1         | 0.31%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 81        | 22.13%  |
| Intel Wi-Fi 6 AX200                                                    | 35        | 9.56%   |
| Realtek RTL8125 2.5GbE Controller                                      | 16        | 4.37%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 15        | 4.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 11        | 3.01%   |
| Intel Wi-Fi 6 AX201                                                    | 8         | 2.19%   |
| Intel Ethernet Controller I225-V                                       | 8         | 2.19%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 7         | 1.91%   |
| Intel Wireless 8265 / 8275                                             | 7         | 1.91%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 7         | 1.91%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 6         | 1.64%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 5         | 1.37%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 5         | 1.37%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 5         | 1.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 1.09%   |
| DisplayLink DL-Dock                                                    | 4         | 1.09%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 1.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 3         | 0.82%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 3         | 0.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 3         | 0.82%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 3         | 0.82%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 3         | 0.82%   |
| Intel Wireless 7265                                                    | 3         | 0.82%   |
| Intel Wireless 3165                                                    | 3         | 0.82%   |
| Intel Wireless 3160                                                    | 3         | 0.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 3         | 0.82%   |
| Huawei ME936 LTE/HSDPA+ 4G modem                                       | 3         | 0.82%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 0.82%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 3         | 0.82%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 2         | 0.55%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 2         | 0.55%   |
| Realtek Killer E2600 GbE Controller                                    | 2         | 0.55%   |
| Ralink MT7601U Wireless Adapter                                        | 2         | 0.55%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 2         | 0.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 2         | 0.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 2         | 0.55%   |
| Intel Wireless 8260                                                    | 2         | 0.55%   |
| Intel Wireless 7260                                                    | 2         | 0.55%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 0.55%   |
| Intel Ethernet Connection (6) I219-LM                                  | 2         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 125       | 68.68%  |
| Realtek Semiconductor | 17        | 9.34%   |
| Broadcom              | 9         | 4.95%   |
| Qualcomm Atheros      | 8         | 4.4%    |
| Ralink Technology     | 6         | 3.3%    |
| MediaTek              | 4         | 2.2%    |
| Broadcom Limited      | 4         | 2.2%    |
| TP-Link               | 2         | 1.1%    |
| Sierra Wireless       | 2         | 1.1%    |
| Ralink                | 2         | 1.1%    |
| D-Link                | 2         | 1.1%    |
| NetGear               | 1         | 0.55%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 35        | 19.23%  |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 15        | 8.24%   |
| Intel Wi-Fi 6 AX201                                                  | 8         | 4.4%    |
| Intel Wireless 8265 / 8275                                           | 7         | 3.85%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 7         | 3.85%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 6         | 3.3%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 5         | 2.75%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                    | 5         | 2.75%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 5         | 2.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 3         | 1.65%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 3         | 1.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 3         | 1.65%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 3         | 1.65%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 3         | 1.65%   |
| Intel Wireless 7265                                                  | 3         | 1.65%   |
| Intel Wireless 3165                                                  | 3         | 1.65%   |
| Intel Wireless 3160                                                  | 3         | 1.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 3         | 1.65%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 3         | 1.65%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 2         | 1.1%    |
| Ralink MT7601U Wireless Adapter                                      | 2         | 1.1%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 2         | 1.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2         | 1.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 2         | 1.1%    |
| Intel Wireless 8260                                                  | 2         | 1.1%    |
| Intel Wireless 7260                                                  | 2         | 1.1%    |
| Intel Centrino Advanced-N 6235                                       | 2         | 1.1%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 2         | 1.1%    |
| Intel Cannon Lake PCH CNVi WiFi                                      | 2         | 1.1%    |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 2         | 1.1%    |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 2         | 1.1%    |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter          | 2         | 1.1%    |
| Broadcom BCM43142 802.11b/g/n                                        | 2         | 1.1%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 1         | 0.55%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 1         | 0.55%   |
| Sierra Wireless EM7455                                               | 1         | 0.55%   |
| Sierra Wireless EM7305                                               | 1         | 0.55%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 1         | 0.55%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 1         | 0.55%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 1         | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 118       | 67.05%  |
| Intel                 | 36        | 20.45%  |
| DisplayLink           | 5         | 2.84%   |
| Qualcomm Atheros      | 4         | 2.27%   |
| Broadcom              | 4         | 2.27%   |
| ASIX Electronics      | 4         | 2.27%   |
| Samsung Electronics   | 1         | 0.57%   |
| OPPO Electronics      | 1         | 0.57%   |
| Nvidia                | 1         | 0.57%   |
| Lenovo                | 1         | 0.57%   |
| Broadcom Limited      | 1         | 0.57%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 81        | 45.51%  |
| Realtek RTL8125 2.5GbE Controller                                      | 16        | 8.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 11        | 6.18%   |
| Intel Ethernet Controller I225-V                                       | 8         | 4.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 7         | 3.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 2.25%   |
| DisplayLink DL-Dock                                                    | 4         | 2.25%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 2.25%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 1.69%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 2         | 1.12%   |
| Realtek Killer E2600 GbE Controller                                    | 2         | 1.12%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 1.12%   |
| Intel Ethernet Connection (6) I219-LM                                  | 2         | 1.12%   |
| Intel Ethernet Connection (2) I219-V                                   | 2         | 1.12%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 1.12%   |
| Intel Ethernet Connection (16) I219-LM                                 | 2         | 1.12%   |
| Intel Ethernet Connection (11) I219-V                                  | 2         | 1.12%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.56%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.56%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.56%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 0.56%   |
| OPPO CPH2591                                                           | 1         | 0.56%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.56%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 1         | 0.56%   |
| Intel WiMAX Connection 2400m                                           | 1         | 0.56%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 0.56%   |
| Intel Ethernet Connection I218-V                                       | 1         | 0.56%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 0.56%   |
| Intel Ethernet Connection (7) I219-V                                   | 1         | 0.56%   |
| Intel Ethernet Connection (5) I219-LM                                  | 1         | 0.56%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 0.56%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 0.56%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 0.56%   |
| Intel Ethernet Connection (17) I219-V                                  | 1         | 0.56%   |
| Intel Ethernet Connection (11) I219-LM                                 | 1         | 0.56%   |
| Intel 82574L Gigabit Network Connection                                | 1         | 0.56%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 0.56%   |
| DisplayLink Plugable UD-3900                                           | 1         | 0.56%   |
| Broadcom NetXtreme II BCM5706 Gigabit Ethernet                         | 1         | 0.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 173       | 50.88%  |
| Ethernet | 161       | 47.35%  |
| Modem    | 6         | 1.76%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 122       | 62.89%  |
| Ethernet | 72        | 37.11%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 124       | 65.61%  |
| 1     | 57        | 30.16%  |
| 3     | 6         | 3.17%   |
| 0     | 2         | 1.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 109       | 57.37%  |
| Yes  | 81        | 42.63%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 116       | 72.05%  |
| Realtek Semiconductor           | 11        | 6.83%   |
| Apple                           | 8         | 4.97%   |
| Foxconn / Hon Hai               | 5         | 3.11%   |
| Cambridge Silicon Radio         | 4         | 2.48%   |
| Broadcom                        | 4         | 2.48%   |
| IMC Networks                    | 3         | 1.86%   |
| Ralink                          | 2         | 1.24%   |
| Qualcomm Atheros Communications | 2         | 1.24%   |
| ASUSTek Computer                | 2         | 1.24%   |
| TP-Link                         | 1         | 0.62%   |
| MediaTek                        | 1         | 0.62%   |
| Dell                            | 1         | 0.62%   |
| Unknown                         | 1         | 0.62%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                               | 33        | 20.5%   |
| Intel AX201 Bluetooth                               | 22        | 13.66%  |
| Intel AX211 Bluetooth                               | 20        | 12.42%  |
| Intel Bluetooth wireless interface                  | 12        | 7.45%   |
| Intel Bluetooth Device                              | 9         | 5.59%   |
| Intel AX210 Bluetooth                               | 6         | 3.73%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 3.11%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 3.11%   |
| Apple Bluetooth Host Controller                     | 5         | 3.11%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 2.48%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 1.86%   |
| Realtek Bluetooth Radio                             | 3         | 1.86%   |
| Realtek 802.11ac WLAN Adapter                       | 3         | 1.86%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 1.86%   |
| Apple Bluetooth USB Host Controller                 | 3         | 1.86%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 1.24%   |
| Ralink RT3290 Bluetooth                             | 2         | 1.24%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 1.24%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.24%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 1.24%   |
| IMC Networks Bluetooth Radio                        | 2         | 1.24%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 1.24%   |
| TP-Link UB500 Adapter                               | 1         | 0.62%   |
| MediaTek Wireless_Device                            | 1         | 0.62%   |
| IMC Networks Bluetooth Device                       | 1         | 0.62%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 0.62%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 0.62%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 0.62%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.62%   |
| Broadcom HP Bluethunder                             | 1         | 0.62%   |
| ASUS BT-253 Bluetooth Adapter                       | 1         | 0.62%   |
| ASUS ASUS USB-BT500                                 | 1         | 0.62%   |
| Unknown                                             | 1         | 0.62%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 132       | 49.44%  |
| Nvidia                                 | 64        | 23.97%  |
| AMD                                    | 52        | 19.48%  |
| C-Media Electronics                    | 3         | 1.12%   |
| Razer USA                              | 2         | 0.75%   |
| Lenovo                                 | 2         | 0.75%   |
| Valve Software                         | 1         | 0.37%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.37%   |
| Logitech                               | 1         | 0.37%   |
| Kingston Technology                    | 1         | 0.37%   |
| JMTek                                  | 1         | 0.37%   |
| Huawei Technologies                    | 1         | 0.37%   |
| Hewlett-Packard                        | 1         | 0.37%   |
| GN Netcom                              | 1         | 0.37%   |
| FiiO Electronics Technology            | 1         | 0.37%   |
| Creative Technology                    | 1         | 0.37%   |
| Creative Labs                          | 1         | 0.37%   |
| Corsair                                | 1         | 0.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 41        | 12.58%  |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 19        | 5.83%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 18        | 5.52%   |
| Intel Sunrise Point-LP HD Audio                                            | 11        | 3.37%   |
| Nvidia GA104 High Definition Audio Controller                              | 10        | 3.07%   |
| Nvidia TU116 High Definition Audio Controller                              | 9         | 2.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9         | 2.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9         | 2.76%   |
| Nvidia Audio device                                                        | 8         | 2.45%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 8         | 2.45%   |
| Intel Comet Lake PCH cAVS                                                  | 8         | 2.45%   |
| Nvidia GA106 High Definition Audio Controller                              | 7         | 2.15%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 2.15%   |
| Intel Broadwell-U Audio Controller                                         | 7         | 2.15%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 7         | 2.15%   |
| Nvidia TU106 High Definition Audio Controller                              | 6         | 1.84%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 6         | 1.84%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 1.84%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6         | 1.84%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 5         | 1.53%   |
| Intel Raptor Lake High Definition Audio Controller                         | 5         | 1.53%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 1.53%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 5         | 1.53%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4         | 1.23%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 1.23%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 1.23%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 1.23%   |
| Nvidia GP108 High Definition Audio Controller                              | 3         | 0.92%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 0.92%   |
| Nvidia GP104 High Definition Audio Controller                              | 3         | 0.92%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 0.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 0.92%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 3         | 0.92%   |
| Intel CM238 HD Audio Controller                                            | 3         | 0.92%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 0.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 0.92%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 0.92%   |
| AMD FCH Azalia Controller                                                  | 3         | 0.92%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.61%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 23        | 38.33%  |
| SK hynix            | 13        | 21.67%  |
| Micron Technology   | 8         | 13.33%  |
| Unknown             | 4         | 6.67%   |
| Team                | 2         | 3.33%   |
| Kingston            | 2         | 3.33%   |
| Elpida              | 2         | 3.33%   |
| Corsair             | 2         | 3.33%   |
| Unknown (ABCD)      | 1         | 1.67%   |
| KLEVV               | 1         | 1.67%   |
| Crucial             | 1         | 1.67%   |
| ASint Technology    | 1         | 1.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 5         | 8.2%    |
| Unknown                                                          | 4         | 6.56%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 4.92%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 2         | 3.28%   |
| SK hynix RAM HMCG66AGBSA095N 8GB SODIMM DDR5 5600MT/s            | 2         | 3.28%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 3.28%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 3.28%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 3.28%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 2         | 3.28%   |
| Samsung RAM M425R4GA3BB0-CQKOL 32GB SODIMM DDR5 4800MT/s         | 2         | 3.28%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 1         | 1.64%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.64%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.64%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.64%   |
| SK hynix RAM HMCG88AGBSA092N 32GB SODIMM 5600MT/s                | 1         | 1.64%   |
| SK hynix RAM HMCG78AGBSA092N 16GB SODIMM DDR5 5600MT/s           | 1         | 1.64%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 1.64%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.64%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.64%   |
| Samsung RAM Module 4GB SODIMM DDR3 1867MT/s                      | 1         | 1.64%   |
| Samsung RAM Module 3GB Row Of Chips LPDDR5 6400MT/s              | 1         | 1.64%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.64%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.64%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.64%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 1.64%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.64%   |
| Samsung RAM M425R2GA3BB0-CWMOD 16GB SODIMM DDR5 5600MT/s         | 1         | 1.64%   |
| Samsung RAM K4A8G165WC-BCWE 4GB Row Of Chips DDR4 3200MT/s       | 1         | 1.64%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s          | 1         | 1.64%   |
| Micron RAM MT62F1G32D2DS-026 WT 2GB Row Of Chips LPDDR5 6400MT/s | 1         | 1.64%   |
| Micron RAM MT52L1G32D4PG-107 8GB Chip LPDDR3 1867MT/s            | 1         | 1.64%   |
| Micron RAM Module 2GB Row Of Chips LPDDR5 6400MT/s               | 1         | 1.64%   |
| Micron RAM 8ATF2G64AZ-3G2E1 16GB DIMM DDR4 3200MT/s              | 1         | 1.64%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.64%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s             | 1         | 1.64%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 1         | 1.64%   |
| KLEVV RAM KD48GU880-32A160X 8GB DIMM DDR4 2666MT/s               | 1         | 1.64%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s             | 1         | 1.64%   |
| Kingston RAM KHX1600C9S3/8G 8GB SODIMM DDR3 1600MT/s             | 1         | 1.64%   |
| Elpida RAM Module 4GB SODIMM LPDDR3 1600MT/s                     | 1         | 1.64%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 30        | 54.55%  |
| DDR5    | 8         | 14.55%  |
| DDR3    | 8         | 14.55%  |
| LPDDR5  | 5         | 9.09%   |
| LPDDR3  | 2         | 3.64%   |
| LPDDR4  | 1         | 1.82%   |
| Unknown | 1         | 1.82%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 42        | 76.36%  |
| Row Of Chips | 6         | 10.91%  |
| DIMM         | 6         | 10.91%  |
| Chip         | 1         | 1.82%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 21        | 36.21%  |
| 32768 | 11        | 18.97%  |
| 16384 | 11        | 18.97%  |
| 4096  | 9         | 15.52%  |
| 2048  | 5         | 8.62%   |
| 3072  | 1         | 1.72%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 20        | 35.09%  |
| 1600  | 7         | 12.28%  |
| 6400  | 5         | 8.77%   |
| 5600  | 5         | 8.77%   |
| 2667  | 4         | 7.02%   |
| 4800  | 3         | 5.26%   |
| 8400  | 2         | 3.51%   |
| 3733  | 2         | 3.51%   |
| 2400  | 2         | 3.51%   |
| 1867  | 2         | 3.51%   |
| 3266  | 1         | 1.75%   |
| 2666  | 1         | 1.75%   |
| 2133  | 1         | 1.75%   |
| 1067  | 1         | 1.75%   |
| 1066  | 1         | 1.75%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Prolific Technology | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 63        | 44.37%  |
| Microdia                               | 13        | 9.15%   |
| Bison Electronics                      | 13        | 9.15%   |
| Suyin                                  | 5         | 3.52%   |
| Sunplus Innovation Technology          | 5         | 3.52%   |
| Logitech                               | 5         | 3.52%   |
| Acer                                   | 5         | 3.52%   |
| IMC Networks                           | 4         | 2.82%   |
| Apple                                  | 4         | 2.82%   |
| Realtek Semiconductor                  | 3         | 2.11%   |
| Lite-On Technology                     | 3         | 2.11%   |
| Syntek                                 | 2         | 1.41%   |
| Lenovo                                 | 2         | 1.41%   |
| Valve Software                         | 1         | 0.7%    |
| Unknown                                | 1         | 0.7%    |
| SunplusIT                              | 1         | 0.7%    |
| Sony Ericsson Mobile Communications AB | 1         | 0.7%    |
| Silicon Motion                         | 1         | 0.7%    |
| Ricoh                                  | 1         | 0.7%    |
| Microsoft                              | 1         | 0.7%    |
| Luxvisions Innotech Limited            | 1         | 0.7%    |
| KYE Systems (Mouse Systems)            | 1         | 0.7%    |
| Importek                               | 1         | 0.7%    |
| HYGD-220831-A                          | 1         | 0.7%    |
| Huawei Technologies                    | 1         | 0.7%    |
| Generalplus Technology                 | 1         | 0.7%    |
| Cheng Uei Precision Industry (Foxlink) | 1         | 0.7%    |
| Alpha Imaging Technology               | 1         | 0.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony FHD Webcam                                   | 11        | 7.69%   |
| Chicony USB2.0 Camera                                | 10        | 6.99%   |
| Chicony Integrated IR Camera                         | 9         | 6.29%   |
| Chicony HD Webcam                                    | 7         | 4.9%    |
| Bison BisonCam,NB Pro                                | 7         | 4.9%    |
| Chicony Integrated Camera                            | 5         | 3.5%    |
| Bison HD Webcam                                      | 5         | 3.5%    |
| Microdia Integrated Camera                           | 4         | 2.8%    |
| IMC Networks Integrated Camera                       | 4         | 2.8%    |
| Microdia Integrated_Webcam_FHD                       | 3         | 2.1%    |
| Apple FaceTime HD Camera                             | 3         | 2.1%    |
| Acer Lenovo EasyCamera                               | 3         | 2.1%    |
| Syntek Integrated Camera                             | 2         | 1.4%    |
| Suyin HP Truevision HD                               | 2         | 1.4%    |
| Sunplus Integrated_Webcam_HD                         | 2         | 1.4%    |
| Microdia Laptop_Integrated_Webcam_HD                 | 2         | 1.4%    |
| Chicony HP Webcam                                    | 2         | 1.4%    |
| Chicony ACER HD User Facing                          | 2         | 1.4%    |
| Valve Software 3D Camera                             | 1         | 0.7%    |
| Unknown HD camera                                    | 1         | 0.7%    |
| Suyin RGBIR Camera                                   | 1         | 0.7%    |
| Suyin Integrated_Webcam_HD                           | 1         | 0.7%    |
| Suyin HP TrueVision HD Integrated Webcam             | 1         | 0.7%    |
| SunplusIT FHD Webcam                                 | 1         | 0.7%    |
| Sunplus SPCA2281 Web Camera                          | 1         | 0.7%    |
| Sunplus Laptop_Integrated_Webcam_FHD                 | 1         | 0.7%    |
| Sunplus Asus Webcam                                  | 1         | 0.7%    |
| Sony Ericsson Mobile AB XQ-CC54                      | 1         | 0.7%    |
| Silicon Motion WebCam SCB-1100N                      | 1         | 0.7%    |
| Ricoh Laptop_Integrated_Webcam_FHD                   | 1         | 0.7%    |
| Realtek Integrated Webcam                            | 1         | 0.7%    |
| Realtek HP Wide Vision HD Camera                     | 1         | 0.7%    |
| Realtek HP "Truevision HD" laptop camera             | 1         | 0.7%    |
| Microsoft MicrosoftÂ LifeCam Studio                 | 1         | 0.7%    |
| Microdia USB 2.0 Camera                              | 1         | 0.7%    |
| Microdia Sonix USB 2.0 Camera                        | 1         | 0.7%    |
| Microdia Laptop_Integrated_Webcam_E4HD               | 1         | 0.7%    |
| Microdia Integrated_Webcam_HD                        | 1         | 0.7%    |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 0.7%    |
| Logitech QuickCam Communicate MP/S5500               | 1         | 0.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 16        | 57.14%  |
| Validity Sensors           | 8         | 28.57%  |
| Shenzhen Goodix Technology | 2         | 7.14%   |
| LighTuning Technology      | 2         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics UWP WBDI                                                         | 3         | 10.71%  |
| Synaptics TouchPad                                                         | 3         | 10.71%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 10.71%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 7.14%   |
| Validity Sensors VFS491                                                    | 2         | 7.14%   |
| Synaptics  WBDI                                                            | 2         | 7.14%   |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 7.14%   |
| Unknown                                                                    | 2         | 7.14%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 3.57%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 3.57%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.57%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 3.57%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 3.57%   |
| Synaptics WBDI                                                             | 1         | 3.57%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 3.57%   |
| LighTuning Fingerprint Reader                                              | 1         | 3.57%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 3.57%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 6         | 66.67%  |
| Alcor Micro | 3         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
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


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 120       | 63.16%  |
| 1     | 63        | 33.16%  |
| 2     | 6         | 3.16%   |
| 3     | 1         | 0.53%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 28        | 35.44%  |
| Multimedia controller | 19        | 24.05%  |
| Graphics card         | 10        | 12.66%  |
| Chipcard              | 9         | 11.39%  |
| Net/wireless          | 5         | 6.33%   |
| Bluetooth             | 2         | 2.53%   |
| Wireless              | 1         | 1.27%   |
| Storage               | 1         | 1.27%   |
| Sound                 | 1         | 1.27%   |
| Modem                 | 1         | 1.27%   |
| Card reader           | 1         | 1.27%   |
| Camera                | 1         | 1.27%   |


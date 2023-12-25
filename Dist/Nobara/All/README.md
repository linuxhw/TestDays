Nobara - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Nobara.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Nobara/Desktop/README.md) and [notebooks](/Dist/Nobara/Notebook/README.md).

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

Total: 985

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | B550-A PRO                  | Desktop     | [64a00841b2](https://linux-hardware.org/?probe=64a00841b2) | Dec 23, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [4adc5f3f81](https://linux-hardware.org/?probe=4adc5f3f81) | Dec 22, 2023 |
| Alienware     | 0P0JWX A00                  | Desktop     | [99d0e56ef1](https://linux-hardware.org/?probe=99d0e56ef1) | Dec 22, 2023 |
| HP            | 83E0                        | Desktop     | [07e6f563f9](https://linux-hardware.org/?probe=07e6f563f9) | Dec 22, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [18788fe1ea](https://linux-hardware.org/?probe=18788fe1ea) | Dec 22, 2023 |
| ASUSTek       | B85-PLUS                    | Desktop     | [58a2ef76f9](https://linux-hardware.org/?probe=58a2ef76f9) | Dec 22, 2023 |
| MSI           | B250M PRO-VD                | Desktop     | [1a4d75f062](https://linux-hardware.org/?probe=1a4d75f062) | Dec 22, 2023 |
| MSI           | H81M-E34                    | Desktop     | [4b1991c655](https://linux-hardware.org/?probe=4b1991c655) | Dec 21, 2023 |
| ASUSTek       | Pro B550M-C                 | Desktop     | [4e3b422400](https://linux-hardware.org/?probe=4e3b422400) | Dec 19, 2023 |
| MSI           | B250M PRO-VD                | Desktop     | [925bd9bbac](https://linux-hardware.org/?probe=925bd9bbac) | Dec 19, 2023 |
| ASUSTek       | Pro B550M-C                 | Desktop     | [1cd7c1b629](https://linux-hardware.org/?probe=1cd7c1b629) | Dec 19, 2023 |
| Dell          | G3 3590                     | Notebook    | [15decf2dfc](https://linux-hardware.org/?probe=15decf2dfc) | Dec 18, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [c2a8ace4dd](https://linux-hardware.org/?probe=c2a8ace4dd) | Dec 18, 2023 |
| HP            | Pavilion dv5                | Notebook    | [cf88cdfeb2](https://linux-hardware.org/?probe=cf88cdfeb2) | Dec 18, 2023 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [8a69294494](https://linux-hardware.org/?probe=8a69294494) | Dec 17, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [ec58c18087](https://linux-hardware.org/?probe=ec58c18087) | Dec 17, 2023 |
| Acer          | Aspire A515-56T             | Notebook    | [9579acc8a0](https://linux-hardware.org/?probe=9579acc8a0) | Dec 16, 2023 |
| Gigabyte      | H310M A-CF                  | Desktop     | [cdf7a1ffd4](https://linux-hardware.org/?probe=cdf7a1ffd4) | Dec 15, 2023 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [93e9419d49](https://linux-hardware.org/?probe=93e9419d49) | Dec 14, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [6855d17ce1](https://linux-hardware.org/?probe=6855d17ce1) | Dec 14, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [5d1e9e6d47](https://linux-hardware.org/?probe=5d1e9e6d47) | Dec 13, 2023 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [2c8846a637](https://linux-hardware.org/?probe=2c8846a637) | Dec 12, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [e17d6cbfa7](https://linux-hardware.org/?probe=e17d6cbfa7) | Dec 12, 2023 |
| Dell          | G7 7700                     | Notebook    | [9d4e191ab5](https://linux-hardware.org/?probe=9d4e191ab5) | Dec 12, 2023 |
| MACHINIST     | X99-K9 V2.0                 | Desktop     | [68ba082c42](https://linux-hardware.org/?probe=68ba082c42) | Dec 12, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [f49dd0f010](https://linux-hardware.org/?probe=f49dd0f010) | Dec 12, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [dc0acbdb23](https://linux-hardware.org/?probe=dc0acbdb23) | Dec 10, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [bc8d773d9d](https://linux-hardware.org/?probe=bc8d773d9d) | Dec 10, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [114391b743](https://linux-hardware.org/?probe=114391b743) | Dec 10, 2023 |
| ASRock        | X99 Professional Gaming ... | Desktop     | [46be0f459d](https://linux-hardware.org/?probe=46be0f459d) | Dec 10, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [04e25c9660](https://linux-hardware.org/?probe=04e25c9660) | Dec 10, 2023 |
| Gigabyte      | G5 GE                       | Notebook    | [e63d83327b](https://linux-hardware.org/?probe=e63d83327b) | Dec 09, 2023 |
| Dell          | Latitude 7390 2-in-1        | Convertible | [d5d6865b7d](https://linux-hardware.org/?probe=d5d6865b7d) | Dec 09, 2023 |
| AZW           | GTR V02                     | Desktop     | [ece705bc91](https://linux-hardware.org/?probe=ece705bc91) | Dec 09, 2023 |
| ONE-NETBOO... | ONEXPLAYER F1               | Tablet      | [158658e952](https://linux-hardware.org/?probe=158658e952) | Dec 08, 2023 |
| ONE-NETBOO... | ONEXPLAYER F1               | Tablet      | [3539ea142d](https://linux-hardware.org/?probe=3539ea142d) | Dec 08, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [9da65cd80e](https://linux-hardware.org/?probe=9da65cd80e) | Dec 07, 2023 |
| ASRock        | H61M-VG3                    | Desktop     | [acf5ffd938](https://linux-hardware.org/?probe=acf5ffd938) | Dec 06, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [5326fc7737](https://linux-hardware.org/?probe=5326fc7737) | Dec 06, 2023 |
| Dell          | G5 5505                     | Notebook    | [74d0a53db4](https://linux-hardware.org/?probe=74d0a53db4) | Dec 06, 2023 |
| Samsung       | 960QFG                      | Convertible | [42e5646709](https://linux-hardware.org/?probe=42e5646709) | Dec 06, 2023 |
| Exo           | Smart XQ7                   | Notebook    | [f1ebc77dfc](https://linux-hardware.org/?probe=f1ebc77dfc) | Dec 05, 2023 |
| Exo           | Smart XQ7                   | Notebook    | [3d56eb720e](https://linux-hardware.org/?probe=3d56eb720e) | Dec 05, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [110604e0da](https://linux-hardware.org/?probe=110604e0da) | Dec 05, 2023 |
| ASUSTek       | ROG Strix G814JV_G814JV     | Notebook    | [6cd3d66979](https://linux-hardware.org/?probe=6cd3d66979) | Dec 05, 2023 |
| ASRock        | H570 Steel Legend           | Desktop     | [e1478d8694](https://linux-hardware.org/?probe=e1478d8694) | Dec 03, 2023 |
| ASRock        | H570 Steel Legend           | Desktop     | [f1d29c75a0](https://linux-hardware.org/?probe=f1d29c75a0) | Dec 03, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [2787907c00](https://linux-hardware.org/?probe=2787907c00) | Dec 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [e9e31f8aaa](https://linux-hardware.org/?probe=e9e31f8aaa) | Dec 03, 2023 |
| HP            | 0B54h D                     | Desktop     | [bffc586a45](https://linux-hardware.org/?probe=bffc586a45) | Dec 02, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [4f3cfed57b](https://linux-hardware.org/?probe=4f3cfed57b) | Dec 02, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [a5997eb3f2](https://linux-hardware.org/?probe=a5997eb3f2) | Dec 02, 2023 |
| Dell          | 0FDY5C A00                  | Desktop     | [0d5166b475](https://linux-hardware.org/?probe=0d5166b475) | Dec 02, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [f86124413d](https://linux-hardware.org/?probe=f86124413d) | Dec 01, 2023 |
| Acer          | Aspire E5-473               | Notebook    | [f3b2c01ef7](https://linux-hardware.org/?probe=f3b2c01ef7) | Dec 01, 2023 |
| ASUSTek       | ZenBook UX564EH_Q528EH      | Convertible | [322ac1cb94](https://linux-hardware.org/?probe=322ac1cb94) | Dec 01, 2023 |
| Lenovo        | Yoga 9 14IRP8 83B1          | Convertible | [515d60d68e](https://linux-hardware.org/?probe=515d60d68e) | Dec 01, 2023 |
| ASRock        | H310CM-DVS                  | Desktop     | [ec402bfe2f](https://linux-hardware.org/?probe=ec402bfe2f) | Nov 30, 2023 |
| Dell          | 0FDY5C A00                  | Desktop     | [2eaa838401](https://linux-hardware.org/?probe=2eaa838401) | Nov 30, 2023 |
| Acer          | Veriton N4680G              | Desktop     | [033223b8bc](https://linux-hardware.org/?probe=033223b8bc) | Nov 30, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [6357a41a39](https://linux-hardware.org/?probe=6357a41a39) | Nov 30, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [37545bd915](https://linux-hardware.org/?probe=37545bd915) | Nov 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [d385ea9309](https://linux-hardware.org/?probe=d385ea9309) | Nov 29, 2023 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [11d3e45e2d](https://linux-hardware.org/?probe=11d3e45e2d) | Nov 29, 2023 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [d2dcb1f2da](https://linux-hardware.org/?probe=d2dcb1f2da) | Nov 29, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [b4fbd61258](https://linux-hardware.org/?probe=b4fbd61258) | Nov 28, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [e5509bd1ba](https://linux-hardware.org/?probe=e5509bd1ba) | Nov 28, 2023 |
| ASUSTek       | Maximus VIII FORMULA        | Desktop     | [a39fba5394](https://linux-hardware.org/?probe=a39fba5394) | Nov 27, 2023 |
| Google        | Kench                       | Desktop     | [efdf5874c1](https://linux-hardware.org/?probe=efdf5874c1) | Nov 27, 2023 |
| MSI           | Z170A GAMING M5             | Desktop     | [ab44413728](https://linux-hardware.org/?probe=ab44413728) | Nov 26, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [5c10f3d5a1](https://linux-hardware.org/?probe=5c10f3d5a1) | Nov 25, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [05ba5178cb](https://linux-hardware.org/?probe=05ba5178cb) | Nov 25, 2023 |
| HP            | 8054                        | Desktop     | [dfa212d5da](https://linux-hardware.org/?probe=dfa212d5da) | Nov 25, 2023 |
| Dell          | Precision 7740              | Notebook    | [50b0f0be08](https://linux-hardware.org/?probe=50b0f0be08) | Nov 25, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [0f9d912f7f](https://linux-hardware.org/?probe=0f9d912f7f) | Nov 24, 2023 |
| Dell          | Inspiron 15 3520            | Notebook    | [4f1d1d579c](https://linux-hardware.org/?probe=4f1d1d579c) | Nov 24, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [c3b398c792](https://linux-hardware.org/?probe=c3b398c792) | Nov 24, 2023 |
| ASRock        | X370 Gaming X               | Notebook    | [0c39910834](https://linux-hardware.org/?probe=0c39910834) | Nov 23, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [2ab108f743](https://linux-hardware.org/?probe=2ab108f743) | Nov 22, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [0714d466f7](https://linux-hardware.org/?probe=0714d466f7) | Nov 21, 2023 |
| Dell          | Latitude E6430              | Notebook    | [dc02cb2409](https://linux-hardware.org/?probe=dc02cb2409) | Nov 20, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [639c2b7832](https://linux-hardware.org/?probe=639c2b7832) | Nov 20, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [0d4fe4c2b9](https://linux-hardware.org/?probe=0d4fe4c2b9) | Nov 19, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | Notebook    | [1048b240d5](https://linux-hardware.org/?probe=1048b240d5) | Nov 19, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | Notebook    | [74162bf452](https://linux-hardware.org/?probe=74162bf452) | Nov 19, 2023 |
| LG Electro... | 16Z90R-G.AD75F              | Notebook    | [83d650792f](https://linux-hardware.org/?probe=83d650792f) | Nov 18, 2023 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [db393353d9](https://linux-hardware.org/?probe=db393353d9) | Nov 18, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [c00a7584bf](https://linux-hardware.org/?probe=c00a7584bf) | Nov 18, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [adf1b0c27a](https://linux-hardware.org/?probe=adf1b0c27a) | Nov 16, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [168e0af4e6](https://linux-hardware.org/?probe=168e0af4e6) | Nov 16, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [ca5d20d4a4](https://linux-hardware.org/?probe=ca5d20d4a4) | Nov 16, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [914e24f740](https://linux-hardware.org/?probe=914e24f740) | Nov 16, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Notebook    | [aca7636589](https://linux-hardware.org/?probe=aca7636589) | Nov 16, 2023 |
| MSI           | GF62 8RC                    | Notebook    | [8e186cf8b9](https://linux-hardware.org/?probe=8e186cf8b9) | Nov 16, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Notebook    | [7856865861](https://linux-hardware.org/?probe=7856865861) | Nov 16, 2023 |
| HP            | Pavilion dv9700             | Notebook    | [0b039b15e7](https://linux-hardware.org/?probe=0b039b15e7) | Nov 15, 2023 |
| HP            | Pavilion dv9700             | Notebook    | [b5e651a2bf](https://linux-hardware.org/?probe=b5e651a2bf) | Nov 15, 2023 |
| MSI           | B450M GAMING PLUS           | Desktop     | [038ffaab27](https://linux-hardware.org/?probe=038ffaab27) | Nov 13, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [f0db6bb1ae](https://linux-hardware.org/?probe=f0db6bb1ae) | Nov 11, 2023 |
| Dell          | Latitude 7390 2-in-1        | Convertible | [99fa1c416d](https://linux-hardware.org/?probe=99fa1c416d) | Nov 11, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [404f1947fd](https://linux-hardware.org/?probe=404f1947fd) | Nov 11, 2023 |
| Microsoft     | Surface Book                | Tablet      | [67575d0e41](https://linux-hardware.org/?probe=67575d0e41) | Nov 08, 2023 |
| ASUSTek       | Q504UAK                     | Convertible | [177cde7808](https://linux-hardware.org/?probe=177cde7808) | Nov 07, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [9f1e875996](https://linux-hardware.org/?probe=9f1e875996) | Nov 07, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [993c65a274](https://linux-hardware.org/?probe=993c65a274) | Nov 06, 2023 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [615e914ddd](https://linux-hardware.org/?probe=615e914ddd) | Nov 05, 2023 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [7ba5de3dfd](https://linux-hardware.org/?probe=7ba5de3dfd) | Nov 05, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [c17ad7033c](https://linux-hardware.org/?probe=c17ad7033c) | Nov 05, 2023 |
| ASRock        | X470 Taichi Ultimate        | Desktop     | [2b9b1f909c](https://linux-hardware.org/?probe=2b9b1f909c) | Nov 05, 2023 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [701314a2ff](https://linux-hardware.org/?probe=701314a2ff) | Nov 04, 2023 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | Notebook    | [12b6cd2d09](https://linux-hardware.org/?probe=12b6cd2d09) | Nov 04, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [119816ea7d](https://linux-hardware.org/?probe=119816ea7d) | Nov 04, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [6d39c4f814](https://linux-hardware.org/?probe=6d39c4f814) | Nov 03, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [e928da88d7](https://linux-hardware.org/?probe=e928da88d7) | Nov 03, 2023 |
| Dell          | Precision 7740              | Notebook    | [71b262696a](https://linux-hardware.org/?probe=71b262696a) | Nov 02, 2023 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | Notebook    | [68dd4f08d9](https://linux-hardware.org/?probe=68dd4f08d9) | Nov 02, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [72a2946c83](https://linux-hardware.org/?probe=72a2946c83) | Nov 01, 2023 |
| ONE-NETBOO... | ONE XPLAYER 1002-C          | Notebook    | [b89ceef38d](https://linux-hardware.org/?probe=b89ceef38d) | Nov 01, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [8161abddda](https://linux-hardware.org/?probe=8161abddda) | Nov 01, 2023 |
| AOpen         | iBDWMUx-MD R1.04            | Desktop     | [5b82a04d09](https://linux-hardware.org/?probe=5b82a04d09) | Oct 31, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [70e4b3b007](https://linux-hardware.org/?probe=70e4b3b007) | Oct 31, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [352bf34e3b](https://linux-hardware.org/?probe=352bf34e3b) | Oct 31, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [d9da25aaae](https://linux-hardware.org/?probe=d9da25aaae) | Oct 31, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [0eae5ed294](https://linux-hardware.org/?probe=0eae5ed294) | Oct 31, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [4254def277](https://linux-hardware.org/?probe=4254def277) | Oct 30, 2023 |
| ASUSTek       | P8H77-M                     | Desktop     | [d40277c6b4](https://linux-hardware.org/?probe=d40277c6b4) | Oct 30, 2023 |
| System76      | Gazelle                     | Notebook    | [3bc4a66a13](https://linux-hardware.org/?probe=3bc4a66a13) | Oct 29, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [9dad78d2eb](https://linux-hardware.org/?probe=9dad78d2eb) | Oct 27, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [354a804750](https://linux-hardware.org/?probe=354a804750) | Oct 27, 2023 |
| HP            | Notebook                    | Notebook    | [b6f188a1fe](https://linux-hardware.org/?probe=b6f188a1fe) | Oct 27, 2023 |
| Dell          | Latitude E5470              | Notebook    | [fbbcdd8d9f](https://linux-hardware.org/?probe=fbbcdd8d9f) | Oct 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [3d7ad8a1d6](https://linux-hardware.org/?probe=3d7ad8a1d6) | Oct 26, 2023 |
| Dell          | Latitude E5470              | Notebook    | [cac52e6eaf](https://linux-hardware.org/?probe=cac52e6eaf) | Oct 25, 2023 |
| Gigabyte      | Z77-D3H                     | Desktop     | [2355d71878](https://linux-hardware.org/?probe=2355d71878) | Oct 25, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [38cbc0d5d7](https://linux-hardware.org/?probe=38cbc0d5d7) | Oct 24, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [29adbcb90f](https://linux-hardware.org/?probe=29adbcb90f) | Oct 24, 2023 |
| ASUSTek       | GL502VSK                    | Notebook    | [5f455e693f](https://linux-hardware.org/?probe=5f455e693f) | Oct 24, 2023 |
| ASRock        | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [24cad9ca71](https://linux-hardware.org/?probe=24cad9ca71) | Oct 22, 2023 |
| Gigabyte      | H77-D3H                     | Desktop     | [2c786f10b7](https://linux-hardware.org/?probe=2c786f10b7) | Oct 22, 2023 |
| Gigabyte      | H77-D3H                     | Desktop     | [7b1e876aef](https://linux-hardware.org/?probe=7b1e876aef) | Oct 22, 2023 |
| AOpen         | iBDWMUx-MD R1.04            | Desktop     | [72d780f5f7](https://linux-hardware.org/?probe=72d780f5f7) | Oct 22, 2023 |
| MSI           | Z170A PC MATE               | Desktop     | [2f2798b05c](https://linux-hardware.org/?probe=2f2798b05c) | Oct 22, 2023 |
| Dell          | Inspiron 7375               | Notebook    | [451317bd25](https://linux-hardware.org/?probe=451317bd25) | Oct 22, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | Notebook    | [fa46708f8f](https://linux-hardware.org/?probe=fa46708f8f) | Oct 22, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [390f0188b4](https://linux-hardware.org/?probe=390f0188b4) | Oct 19, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [459dc02cda](https://linux-hardware.org/?probe=459dc02cda) | Oct 18, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [4a7b98d45e](https://linux-hardware.org/?probe=4a7b98d45e) | Oct 18, 2023 |
| MSI           | B350 PC MATE                | Desktop     | [a4661384e1](https://linux-hardware.org/?probe=a4661384e1) | Oct 17, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [fb2bf1baa8](https://linux-hardware.org/?probe=fb2bf1baa8) | Oct 16, 2023 |
| Lenovo        | ThinkPad T450 20BUS1K50X    | Notebook    | [11ccdc870b](https://linux-hardware.org/?probe=11ccdc870b) | Oct 16, 2023 |
| ASUSTek       | X541UV                      | Notebook    | [c5183a57ce](https://linux-hardware.org/?probe=c5183a57ce) | Oct 16, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [a116875c3f](https://linux-hardware.org/?probe=a116875c3f) | Oct 15, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [9f5a8c985a](https://linux-hardware.org/?probe=9f5a8c985a) | Oct 15, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [6f3a56878d](https://linux-hardware.org/?probe=6f3a56878d) | Oct 15, 2023 |
| ASRock        | X670E PG Lightning          | Desktop     | [d2e0e9fc07](https://linux-hardware.org/?probe=d2e0e9fc07) | Oct 14, 2023 |
| MSI           | GT72S 6QE                   | Notebook    | [9a2d87eb4c](https://linux-hardware.org/?probe=9a2d87eb4c) | Oct 12, 2023 |
| MSI           | GT72S 6QE                   | Notebook    | [4927bfc263](https://linux-hardware.org/?probe=4927bfc263) | Oct 12, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [dc82ec9351](https://linux-hardware.org/?probe=dc82ec9351) | Oct 11, 2023 |
| Toshiba       | Satellite C55D-C            | Notebook    | [e083a8012f](https://linux-hardware.org/?probe=e083a8012f) | Oct 11, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [1014c56a70](https://linux-hardware.org/?probe=1014c56a70) | Oct 10, 2023 |
| ASUSTek       | TUF Gaming A620M-PLUS WI... | Desktop     | [15d9d16ec9](https://linux-hardware.org/?probe=15d9d16ec9) | Oct 09, 2023 |
| Biostar       | A320MH                      | Desktop     | [9623471fc7](https://linux-hardware.org/?probe=9623471fc7) | Oct 09, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [c0e071789f](https://linux-hardware.org/?probe=c0e071789f) | Oct 09, 2023 |
| Acer          | Aspire A315-41              | Notebook    | [85d999063f](https://linux-hardware.org/?probe=85d999063f) | Oct 09, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [536b59322e](https://linux-hardware.org/?probe=536b59322e) | Oct 07, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [e087628f2a](https://linux-hardware.org/?probe=e087628f2a) | Oct 07, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [06f03211a6](https://linux-hardware.org/?probe=06f03211a6) | Oct 06, 2023 |
| Gigabyte      | B760 GAMING X DDR4          | Desktop     | [811561ec05](https://linux-hardware.org/?probe=811561ec05) | Oct 04, 2023 |
| MSI           | Modern 14 B5M               | Notebook    | [65ae20098f](https://linux-hardware.org/?probe=65ae20098f) | Oct 03, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d3e6e2aa83](https://linux-hardware.org/?probe=d3e6e2aa83) | Oct 03, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [78c54897a1](https://linux-hardware.org/?probe=78c54897a1) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [288f5f8266](https://linux-hardware.org/?probe=288f5f8266) | Sep 30, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [4bb43a39c1](https://linux-hardware.org/?probe=4bb43a39c1) | Sep 29, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81JN     | Notebook    | [747f0d45fe](https://linux-hardware.org/?probe=747f0d45fe) | Sep 28, 2023 |
| Acer          | Nitro AN515-42              | Notebook    | [dd4a3f701c](https://linux-hardware.org/?probe=dd4a3f701c) | Sep 27, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [55c34c64a6](https://linux-hardware.org/?probe=55c34c64a6) | Sep 27, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [87a3517005](https://linux-hardware.org/?probe=87a3517005) | Sep 26, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [c33d31195f](https://linux-hardware.org/?probe=c33d31195f) | Sep 26, 2023 |
| Dell          | G5 5505                     | Notebook    | [787ccf4559](https://linux-hardware.org/?probe=787ccf4559) | Sep 25, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [93b975d65b](https://linux-hardware.org/?probe=93b975d65b) | Sep 24, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LH0... | Convertible | [9b6bbb4b56](https://linux-hardware.org/?probe=9b6bbb4b56) | Sep 23, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [d21f140b5e](https://linux-hardware.org/?probe=d21f140b5e) | Sep 23, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [c40dbfbd1d](https://linux-hardware.org/?probe=c40dbfbd1d) | Sep 23, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [5043f41a8d](https://linux-hardware.org/?probe=5043f41a8d) | Sep 20, 2023 |
| AZW           | GTR V02                     | Desktop     | [2d4817f092](https://linux-hardware.org/?probe=2d4817f092) | Sep 18, 2023 |
| Dell          | G3 3579                     | Notebook    | [eff563e086](https://linux-hardware.org/?probe=eff563e086) | Sep 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [4c854cc233](https://linux-hardware.org/?probe=4c854cc233) | Sep 17, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [27763442c0](https://linux-hardware.org/?probe=27763442c0) | Sep 16, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [cd2fb41835](https://linux-hardware.org/?probe=cd2fb41835) | Sep 15, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [52f0ac41db](https://linux-hardware.org/?probe=52f0ac41db) | Sep 14, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [caf0257156](https://linux-hardware.org/?probe=caf0257156) | Sep 13, 2023 |
| Dell          | Latitude E6440              | Notebook    | [591c479a8d](https://linux-hardware.org/?probe=591c479a8d) | Sep 13, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E GENE    | Desktop     | [b9f46a8a9b](https://linux-hardware.org/?probe=b9f46a8a9b) | Sep 12, 2023 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [f818765b79](https://linux-hardware.org/?probe=f818765b79) | Sep 10, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [3857377d7a](https://linux-hardware.org/?probe=3857377d7a) | Sep 09, 2023 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [6521407977](https://linux-hardware.org/?probe=6521407977) | Sep 06, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [b395463f0e](https://linux-hardware.org/?probe=b395463f0e) | Sep 06, 2023 |
| Gigabyte      | B550M K                     | Desktop     | [95d0f9505b](https://linux-hardware.org/?probe=95d0f9505b) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [3900a91c0b](https://linux-hardware.org/?probe=3900a91c0b) | Sep 03, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [174cff0e19](https://linux-hardware.org/?probe=174cff0e19) | Sep 02, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [07a44c323f](https://linux-hardware.org/?probe=07a44c323f) | Sep 01, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [a0649549b3](https://linux-hardware.org/?probe=a0649549b3) | Sep 01, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c865cde7a2](https://linux-hardware.org/?probe=c865cde7a2) | Sep 01, 2023 |
| Lenovo        | Legion Slim 7 16IRH8 82Y... | Notebook    | [ab14d9d9bb](https://linux-hardware.org/?probe=ab14d9d9bb) | Aug 31, 2023 |
| ASRock        | Z490M Pro4                  | Desktop     | [e07d4a9c90](https://linux-hardware.org/?probe=e07d4a9c90) | Aug 30, 2023 |
| MSI           | Z170A GAMING M3             | Desktop     | [cdbff2ba81](https://linux-hardware.org/?probe=cdbff2ba81) | Aug 28, 2023 |
| Gigabyte      | H410M H                     | Desktop     | [a4fe691c36](https://linux-hardware.org/?probe=a4fe691c36) | Aug 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [0bda6b93da](https://linux-hardware.org/?probe=0bda6b93da) | Aug 27, 2023 |
| Intel         | NUC7i5BNB J31144-311        | Mini pc     | [5af1e720cc](https://linux-hardware.org/?probe=5af1e720cc) | Aug 27, 2023 |
| ASRock        | B650 PG Lightning           | Desktop     | [de1d12ec95](https://linux-hardware.org/?probe=de1d12ec95) | Aug 24, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [523acf034e](https://linux-hardware.org/?probe=523acf034e) | Aug 23, 2023 |
| ASUSTek       | G751JM                      | Notebook    | [7cdb0c52e4](https://linux-hardware.org/?probe=7cdb0c52e4) | Aug 23, 2023 |
| Acer          | Nitro AN515-56              | Notebook    | [530e70e1ab](https://linux-hardware.org/?probe=530e70e1ab) | Aug 22, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [ca9423253c](https://linux-hardware.org/?probe=ca9423253c) | Aug 21, 2023 |
| Acer          | Nitro AN515-56              | Notebook    | [45264bf6e6](https://linux-hardware.org/?probe=45264bf6e6) | Aug 20, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [0887b2e549](https://linux-hardware.org/?probe=0887b2e549) | Aug 20, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [f7d3395ffc](https://linux-hardware.org/?probe=f7d3395ffc) | Aug 18, 2023 |
| Infinix       | INBOOK X2 GEN11             | Notebook    | [f368b5bf17](https://linux-hardware.org/?probe=f368b5bf17) | Aug 18, 2023 |
| ASUSTek       | Pro B550M-C                 | Desktop     | [712bd65558](https://linux-hardware.org/?probe=712bd65558) | Aug 16, 2023 |
| Dell          | XPS 17 9730                 | Notebook    | [9c5e7cc1fb](https://linux-hardware.org/?probe=9c5e7cc1fb) | Aug 16, 2023 |
| Pegatron      | Benicia                     | Desktop     | [0ab394fa9e](https://linux-hardware.org/?probe=0ab394fa9e) | Aug 15, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [876d7e9992](https://linux-hardware.org/?probe=876d7e9992) | Aug 15, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [da3036b8e3](https://linux-hardware.org/?probe=da3036b8e3) | Aug 14, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [e9b2347b46](https://linux-hardware.org/?probe=e9b2347b46) | Aug 14, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [f9d07e4f97](https://linux-hardware.org/?probe=f9d07e4f97) | Aug 12, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [ecbc3827d1](https://linux-hardware.org/?probe=ecbc3827d1) | Aug 12, 2023 |
| Gigabyte      | G1.Sniper M3-CF             | Desktop     | [f4d0fd6811](https://linux-hardware.org/?probe=f4d0fd6811) | Aug 12, 2023 |
| Gigabyte      | G1.Sniper M3-CF             | Desktop     | [a5681e12d3](https://linux-hardware.org/?probe=a5681e12d3) | Aug 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [3a7d1d1f9b](https://linux-hardware.org/?probe=3a7d1d1f9b) | Aug 11, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E GENE    | Desktop     | [f016fa3756](https://linux-hardware.org/?probe=f016fa3756) | Aug 11, 2023 |
| Dell          | Inspiron 3180               | Notebook    | [40c31ab8e5](https://linux-hardware.org/?probe=40c31ab8e5) | Aug 11, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [d490bb32ec](https://linux-hardware.org/?probe=d490bb32ec) | Aug 10, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [fffee60e72](https://linux-hardware.org/?probe=fffee60e72) | Aug 10, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [d6b7da58e7](https://linux-hardware.org/?probe=d6b7da58e7) | Aug 08, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [d9c999ffa3](https://linux-hardware.org/?probe=d9c999ffa3) | Aug 08, 2023 |
| HP            | ENVY Laptop 16-h1xxx        | Notebook    | [101c521941](https://linux-hardware.org/?probe=101c521941) | Aug 08, 2023 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | Desktop     | [f7c7290847](https://linux-hardware.org/?probe=f7c7290847) | Aug 08, 2023 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | Desktop     | [9a0fa703d7](https://linux-hardware.org/?probe=9a0fa703d7) | Aug 07, 2023 |
| Micro Comp... | NUCXI7                      | Notebook    | [96d3ade9eb](https://linux-hardware.org/?probe=96d3ade9eb) | Aug 07, 2023 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [ec7fa20ab4](https://linux-hardware.org/?probe=ec7fa20ab4) | Aug 06, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [d9107b9cb9](https://linux-hardware.org/?probe=d9107b9cb9) | Aug 06, 2023 |
| MSI           | FM2-A55M-E33                | Desktop     | [28384fb38c](https://linux-hardware.org/?probe=28384fb38c) | Aug 06, 2023 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [5ec7de1222](https://linux-hardware.org/?probe=5ec7de1222) | Aug 06, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [ab9328165e](https://linux-hardware.org/?probe=ab9328165e) | Aug 05, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [2cb4df0aab](https://linux-hardware.org/?probe=2cb4df0aab) | Aug 04, 2023 |
| Lenovo        | ThinkPad T450 20BUS3ES0A    | Notebook    | [1038e99486](https://linux-hardware.org/?probe=1038e99486) | Aug 04, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [cd0d64a16a](https://linux-hardware.org/?probe=cd0d64a16a) | Aug 03, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [53c9161fc5](https://linux-hardware.org/?probe=53c9161fc5) | Aug 03, 2023 |
| AOpen         | iBDWMUx-MD R1.04            | Desktop     | [18dad15a33](https://linux-hardware.org/?probe=18dad15a33) | Aug 02, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [ceb7e754a1](https://linux-hardware.org/?probe=ceb7e754a1) | Aug 02, 2023 |
| ASRock        | Z170 Extreme6+              | Desktop     | [84c1a14a56](https://linux-hardware.org/?probe=84c1a14a56) | Aug 01, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [3aeae112c3](https://linux-hardware.org/?probe=3aeae112c3) | Jul 31, 2023 |
| NZXT          | N7 B650E                    | Desktop     | [38e481c3d5](https://linux-hardware.org/?probe=38e481c3d5) | Jul 29, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [513ac15990](https://linux-hardware.org/?probe=513ac15990) | Jul 28, 2023 |
| ASRock        | WRX80 Creator R2.0          | Other       | [f37cf89f5f](https://linux-hardware.org/?probe=f37cf89f5f) | Jul 28, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [23c1f6fa05](https://linux-hardware.org/?probe=23c1f6fa05) | Jul 28, 2023 |
| Dell          | Inspiron 15 3520            | Notebook    | [49cbe32874](https://linux-hardware.org/?probe=49cbe32874) | Jul 28, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [e882db39b8](https://linux-hardware.org/?probe=e882db39b8) | Jul 27, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [c9c42e4857](https://linux-hardware.org/?probe=c9c42e4857) | Jul 26, 2023 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [35f41c1327](https://linux-hardware.org/?probe=35f41c1327) | Jul 25, 2023 |
| Dell          | Inspiron 15 3520            | Notebook    | [319cb6659d](https://linux-hardware.org/?probe=319cb6659d) | Jul 24, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [567693892b](https://linux-hardware.org/?probe=567693892b) | Jul 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ca354dd42d](https://linux-hardware.org/?probe=ca354dd42d) | Jul 23, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [228ded2955](https://linux-hardware.org/?probe=228ded2955) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [5f9962eafc](https://linux-hardware.org/?probe=5f9962eafc) | Jul 21, 2023 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [2109b6ace6](https://linux-hardware.org/?probe=2109b6ace6) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [022d677eda](https://linux-hardware.org/?probe=022d677eda) | Jul 21, 2023 |
| MSI           | B450M BAZOOKA MAX WIFI      | Desktop     | [25311760a9](https://linux-hardware.org/?probe=25311760a9) | Jul 21, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [0ba223e9ae](https://linux-hardware.org/?probe=0ba223e9ae) | Jul 19, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [26313914e4](https://linux-hardware.org/?probe=26313914e4) | Jul 19, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [00bda81c25](https://linux-hardware.org/?probe=00bda81c25) | Jul 19, 2023 |
| Toshiba       | Satellite S55t-C            | Notebook    | [be8777b248](https://linux-hardware.org/?probe=be8777b248) | Jul 17, 2023 |
| ASRock        | Z170 Extreme6+              | Desktop     | [5ead4ab228](https://linux-hardware.org/?probe=5ead4ab228) | Jul 17, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [8231c1b7c0](https://linux-hardware.org/?probe=8231c1b7c0) | Jul 16, 2023 |
| Apple         | MacBookPro5,4               | Notebook    | [91f38d0ab5](https://linux-hardware.org/?probe=91f38d0ab5) | Jul 16, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [70b7e2a7f5](https://linux-hardware.org/?probe=70b7e2a7f5) | Jul 16, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [ac55f32c4e](https://linux-hardware.org/?probe=ac55f32c4e) | Jul 16, 2023 |
| ASRock        | H370 Performance            | Desktop     | [43286f18d3](https://linux-hardware.org/?probe=43286f18d3) | Jul 16, 2023 |
| HP            | 3396                        | Desktop     | [5713dca497](https://linux-hardware.org/?probe=5713dca497) | Jul 15, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [d8550d27e3](https://linux-hardware.org/?probe=d8550d27e3) | Jul 15, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [c27ff02a84](https://linux-hardware.org/?probe=c27ff02a84) | Jul 14, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [7026c5b007](https://linux-hardware.org/?probe=7026c5b007) | Jul 14, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [8e3cc576fd](https://linux-hardware.org/?probe=8e3cc576fd) | Jul 14, 2023 |
| Lenovo        | ThinkPad T470 20HES0FA03    | Notebook    | [f416cb06c2](https://linux-hardware.org/?probe=f416cb06c2) | Jul 14, 2023 |
| MSI           | PRO Z690-A WIFI             | Desktop     | [d20f9ee7a7](https://linux-hardware.org/?probe=d20f9ee7a7) | Jul 14, 2023 |
| MSI           | Z87-G45 GAMING              | Desktop     | [110a53c220](https://linux-hardware.org/?probe=110a53c220) | Jul 13, 2023 |
| MSI           | GT70 2PE                    | Notebook    | [9e49d96293](https://linux-hardware.org/?probe=9e49d96293) | Jul 13, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [e612d95542](https://linux-hardware.org/?probe=e612d95542) | Jul 12, 2023 |
| Unknown       | EA A520M-E                  | Desktop     | [184201d556](https://linux-hardware.org/?probe=184201d556) | Jul 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [0e411803b2](https://linux-hardware.org/?probe=0e411803b2) | Jul 10, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [429e4e7636](https://linux-hardware.org/?probe=429e4e7636) | Jul 10, 2023 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | Notebook    | [f273c7ffee](https://linux-hardware.org/?probe=f273c7ffee) | Jul 10, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e9e376fb10](https://linux-hardware.org/?probe=e9e376fb10) | Jul 09, 2023 |
| Acer          | Nitro N50-620               | Desktop     | [8286ddb9ae](https://linux-hardware.org/?probe=8286ddb9ae) | Jul 08, 2023 |
| Dell          | G7 7790                     | Notebook    | [a6dd0d72f7](https://linux-hardware.org/?probe=a6dd0d72f7) | Jul 06, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [f4f1e6f9ff](https://linux-hardware.org/?probe=f4f1e6f9ff) | Jul 05, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603ZM... | Notebook    | [afa2978397](https://linux-hardware.org/?probe=afa2978397) | Jul 05, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS1... | Convertible | [2be3b17236](https://linux-hardware.org/?probe=2be3b17236) | Jul 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9472db0bf4](https://linux-hardware.org/?probe=9472db0bf4) | Jul 04, 2023 |
| GPD           | G1618-03                    | Desktop     | [0cb58087bf](https://linux-hardware.org/?probe=0cb58087bf) | Jul 04, 2023 |
| Dell          | Latitude E5440              | Notebook    | [03ed0e9ebb](https://linux-hardware.org/?probe=03ed0e9ebb) | Jul 03, 2023 |
| Samsung       | 730QED                      | Convertible | [5bcec42625](https://linux-hardware.org/?probe=5bcec42625) | Jul 03, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [626416c230](https://linux-hardware.org/?probe=626416c230) | Jul 03, 2023 |
| ASUSTek       | X541SA                      | Notebook    | [be7a8d9ce0](https://linux-hardware.org/?probe=be7a8d9ce0) | Jul 02, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [ff0f73c325](https://linux-hardware.org/?probe=ff0f73c325) | Jul 02, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [e7e4a3562f](https://linux-hardware.org/?probe=e7e4a3562f) | Jul 02, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [488ebd160a](https://linux-hardware.org/?probe=488ebd160a) | Jul 02, 2023 |
| Dell          | G7 7790                     | Notebook    | [6345fbbe32](https://linux-hardware.org/?probe=6345fbbe32) | Jul 01, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [c1051d3ef0](https://linux-hardware.org/?probe=c1051d3ef0) | Jul 01, 2023 |
| ASRock        | X299 Taichi CLX             | Desktop     | [ff1f31ff36](https://linux-hardware.org/?probe=ff1f31ff36) | Jul 01, 2023 |
| ASRock        | X299 Taichi CLX             | Desktop     | [d4362fb3ca](https://linux-hardware.org/?probe=d4362fb3ca) | Jul 01, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [593959e6f3](https://linux-hardware.org/?probe=593959e6f3) | Jun 30, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E GENE    | Desktop     | [c93f4f0d0b](https://linux-hardware.org/?probe=c93f4f0d0b) | Jun 30, 2023 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | Notebook    | [bbd5ba331d](https://linux-hardware.org/?probe=bbd5ba331d) | Jun 30, 2023 |
| Lenovo        | G50-80 80L0                 | Notebook    | [9979e7a733](https://linux-hardware.org/?probe=9979e7a733) | Jun 29, 2023 |
| HP            | Elite x360 1040 14 inch ... | Convertible | [8086d33203](https://linux-hardware.org/?probe=8086d33203) | Jun 29, 2023 |
| Apple         | MacBookPro8,3               | Notebook    | [4846eae54f](https://linux-hardware.org/?probe=4846eae54f) | Jun 28, 2023 |
| Apple         | MacBookPro8,3               | Notebook    | [f5c922b6d3](https://linux-hardware.org/?probe=f5c922b6d3) | Jun 28, 2023 |
| Dell          | Inspiron 15 3520            | Notebook    | [c77b479e22](https://linux-hardware.org/?probe=c77b479e22) | Jun 27, 2023 |
| Dell          | Inspiron 14 7420 2-in-1     | Convertible | [c243b40ffb](https://linux-hardware.org/?probe=c243b40ffb) | Jun 26, 2023 |
| Lenovo        | ThinkPad A485 20MU000TUS    | Notebook    | [5e67041129](https://linux-hardware.org/?probe=5e67041129) | Jun 26, 2023 |
| Google        | Blooglet                    | Notebook    | [88fae074d1](https://linux-hardware.org/?probe=88fae074d1) | Jun 25, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | Mini pc     | [279f2cedcc](https://linux-hardware.org/?probe=279f2cedcc) | Jun 24, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [5b780b9ebd](https://linux-hardware.org/?probe=5b780b9ebd) | Jun 24, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [54d0d54490](https://linux-hardware.org/?probe=54d0d54490) | Jun 24, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | Mini pc     | [f83de9c7b9](https://linux-hardware.org/?probe=f83de9c7b9) | Jun 24, 2023 |
| ASRock        | B85M Pro4                   | Desktop     | [0ee3f7532c](https://linux-hardware.org/?probe=0ee3f7532c) | Jun 23, 2023 |
| Lenovo        | ThinkPad A485 20MU000TUS    | Notebook    | [305e202fd3](https://linux-hardware.org/?probe=305e202fd3) | Jun 22, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [379c36642b](https://linux-hardware.org/?probe=379c36642b) | Jun 22, 2023 |
| AOpen         | iBDWMUx-MD R1.04            | Desktop     | [2656caf6b8](https://linux-hardware.org/?probe=2656caf6b8) | Jun 22, 2023 |
| MSI           | H81M-E34                    | Desktop     | [ac0a9c170f](https://linux-hardware.org/?probe=ac0a9c170f) | Jun 22, 2023 |
| MSI           | H81M-E34                    | Desktop     | [666f5d0ce5](https://linux-hardware.org/?probe=666f5d0ce5) | Jun 22, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [0f5435c665](https://linux-hardware.org/?probe=0f5435c665) | Jun 22, 2023 |
| Acer          | Spin SP314-54N              | Convertible | [2805733dcd](https://linux-hardware.org/?probe=2805733dcd) | Jun 21, 2023 |
| Acer          | Spin SP314-54N              | Convertible | [370e948985](https://linux-hardware.org/?probe=370e948985) | Jun 21, 2023 |
| MSI           | GT70 2OC/2OD                | Notebook    | [d8d81f0614](https://linux-hardware.org/?probe=d8d81f0614) | Jun 20, 2023 |
| MSI           | GE75 Raider 10SE            | Notebook    | [f7a3caaef1](https://linux-hardware.org/?probe=f7a3caaef1) | Jun 20, 2023 |
| MSI           | GE75 Raider 10SE            | Notebook    | [f11d231c6a](https://linux-hardware.org/?probe=f11d231c6a) | Jun 20, 2023 |
| Timi          | A30                         | Notebook    | [34d77f385a](https://linux-hardware.org/?probe=34d77f385a) | Jun 19, 2023 |
| Lenovo        | ThinkPad A485 20MU000TUS    | Notebook    | [10cf405f89](https://linux-hardware.org/?probe=10cf405f89) | Jun 17, 2023 |
| Dell          | Precision 7510              | Notebook    | [cbbfdafd46](https://linux-hardware.org/?probe=cbbfdafd46) | Jun 17, 2023 |
| ASRock        | Z370 Gaming-ITX/ac          | Desktop     | [e05a90c6c5](https://linux-hardware.org/?probe=e05a90c6c5) | Jun 16, 2023 |
| HP            | 8054                        | Desktop     | [97a4b34236](https://linux-hardware.org/?probe=97a4b34236) | Jun 15, 2023 |
| ASRock        | X470 Master SLI             | Desktop     | [448a3cf6b1](https://linux-hardware.org/?probe=448a3cf6b1) | Jun 15, 2023 |
| ASRock        | B650E Steel Legend WiFi     | Desktop     | [3edca35793](https://linux-hardware.org/?probe=3edca35793) | Jun 14, 2023 |
| ASUSTek       | PRIME B760M-A WIFI D4       | Desktop     | [6febc3ef2e](https://linux-hardware.org/?probe=6febc3ef2e) | Jun 13, 2023 |
| Google        | Blooglet                    | Notebook    | [80ce635393](https://linux-hardware.org/?probe=80ce635393) | Jun 13, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [5d21e64704](https://linux-hardware.org/?probe=5d21e64704) | Jun 10, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [42722d78d8](https://linux-hardware.org/?probe=42722d78d8) | Jun 10, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [6491127e6e](https://linux-hardware.org/?probe=6491127e6e) | Jun 09, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [483ac7223f](https://linux-hardware.org/?probe=483ac7223f) | Jun 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [12736be80e](https://linux-hardware.org/?probe=12736be80e) | Jun 07, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [bc00b26e0a](https://linux-hardware.org/?probe=bc00b26e0a) | Jun 06, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [ee25039289](https://linux-hardware.org/?probe=ee25039289) | Jun 06, 2023 |
| Infinix       | INBook X1 Pro               | Notebook    | [c558de3b74](https://linux-hardware.org/?probe=c558de3b74) | Jun 05, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [43c70efbe7](https://linux-hardware.org/?probe=43c70efbe7) | Jun 05, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [efa9cac1df](https://linux-hardware.org/?probe=efa9cac1df) | Jun 04, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [1285aacf1b](https://linux-hardware.org/?probe=1285aacf1b) | Jun 04, 2023 |
| Intel         | NUC11PHBi7 M26151-404       | Mini pc     | [386f19f4f1](https://linux-hardware.org/?probe=386f19f4f1) | Jun 03, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [3e7ad22b6b](https://linux-hardware.org/?probe=3e7ad22b6b) | Jun 03, 2023 |
| ASUSTek       | X550JK                      | Notebook    | [ae3bf8f79c](https://linux-hardware.org/?probe=ae3bf8f79c) | Jun 03, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [9a91f8aedc](https://linux-hardware.org/?probe=9a91f8aedc) | Jun 02, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [259865e80e](https://linux-hardware.org/?probe=259865e80e) | Jun 01, 2023 |
| Alienware     | m17 R5 AMD                  | Notebook    | [f5eeb72c4d](https://linux-hardware.org/?probe=f5eeb72c4d) | May 31, 2023 |
| Samsung       | 730QED                      | Convertible | [8b5ecbd84f](https://linux-hardware.org/?probe=8b5ecbd84f) | May 31, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [54b872a39b](https://linux-hardware.org/?probe=54b872a39b) | May 31, 2023 |
| ASRock        | B650E Steel Legend WiFi     | Desktop     | [88d16bf040](https://linux-hardware.org/?probe=88d16bf040) | May 31, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0cb4af5367](https://linux-hardware.org/?probe=0cb4af5367) | May 30, 2023 |
| Lenovo        | ThinkPad T480s 20L8S06Q0... | Notebook    | [e54e204b28](https://linux-hardware.org/?probe=e54e204b28) | May 29, 2023 |
| Micro Elec... | MG-VCP2-17A3070T            | Notebook    | [9496942a44](https://linux-hardware.org/?probe=9496942a44) | May 28, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [9099d721d2](https://linux-hardware.org/?probe=9099d721d2) | May 27, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [447bbfbd40](https://linux-hardware.org/?probe=447bbfbd40) | May 27, 2023 |
| Dell          | 0J3C2F A02                  | Desktop     | [c2640c22ff](https://linux-hardware.org/?probe=c2640c22ff) | May 27, 2023 |
| HP            | 1497                        | Desktop     | [94f79f2f74](https://linux-hardware.org/?probe=94f79f2f74) | May 27, 2023 |
| HP            | 1497                        | Desktop     | [d2cca6c2a1](https://linux-hardware.org/?probe=d2cca6c2a1) | May 27, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [6bf848e58f](https://linux-hardware.org/?probe=6bf848e58f) | May 25, 2023 |
| AOpen         | iBDWMUx-MD R1.04            | Desktop     | [cc674d2878](https://linux-hardware.org/?probe=cc674d2878) | May 25, 2023 |
| ASRock        | AB350M Pro4                 | Desktop     | [1efd2eb268](https://linux-hardware.org/?probe=1efd2eb268) | May 24, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [c43cfd04ad](https://linux-hardware.org/?probe=c43cfd04ad) | May 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0aba7a98b9](https://linux-hardware.org/?probe=0aba7a98b9) | May 24, 2023 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [a5df8ea9d7](https://linux-hardware.org/?probe=a5df8ea9d7) | May 23, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [0d3bc48240](https://linux-hardware.org/?probe=0d3bc48240) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d1c4b3ee44](https://linux-hardware.org/?probe=d1c4b3ee44) | May 22, 2023 |
| Lenovo        | ThinkPad X140e 20BLS0040... | Notebook    | [1e648e8f50](https://linux-hardware.org/?probe=1e648e8f50) | May 21, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [43c5b0db78](https://linux-hardware.org/?probe=43c5b0db78) | May 20, 2023 |
| ASRock        | B650E Steel Legend WiFi     | Desktop     | [b034244bec](https://linux-hardware.org/?probe=b034244bec) | May 20, 2023 |
| langchao      | IPM41-D3                    | Desktop     | [2f659faa92](https://linux-hardware.org/?probe=2f659faa92) | May 20, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [758f0dbd4b](https://linux-hardware.org/?probe=758f0dbd4b) | May 19, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [ca0ae58640](https://linux-hardware.org/?probe=ca0ae58640) | May 18, 2023 |
| Samsung       | 730QED                      | Convertible | [7440f51d53](https://linux-hardware.org/?probe=7440f51d53) | May 18, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [fee6b2f55b](https://linux-hardware.org/?probe=fee6b2f55b) | May 17, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [dc2f3b9cdc](https://linux-hardware.org/?probe=dc2f3b9cdc) | May 17, 2023 |
| ASRock        | Z97 Pro3                    | Desktop     | [f8be8d5d2c](https://linux-hardware.org/?probe=f8be8d5d2c) | May 16, 2023 |
| HP            | Pavilion 15                 | Notebook    | [5a43663b87](https://linux-hardware.org/?probe=5a43663b87) | May 15, 2023 |
| HP            | Pavilion 15                 | Notebook    | [b298e421bb](https://linux-hardware.org/?probe=b298e421bb) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [204400bcf7](https://linux-hardware.org/?probe=204400bcf7) | May 13, 2023 |
| ASRock        | Z97 Pro3                    | Desktop     | [34b2fb40b9](https://linux-hardware.org/?probe=34b2fb40b9) | May 13, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [71f1904bc6](https://linux-hardware.org/?probe=71f1904bc6) | May 13, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [bd6f8927b4](https://linux-hardware.org/?probe=bd6f8927b4) | May 12, 2023 |
| ASUSTek       | B85-PLUS                    | Desktop     | [9346ce422f](https://linux-hardware.org/?probe=9346ce422f) | May 11, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [45c02c8b1b](https://linux-hardware.org/?probe=45c02c8b1b) | May 11, 2023 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [2b0bc04757](https://linux-hardware.org/?probe=2b0bc04757) | May 10, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [ebe0f52831](https://linux-hardware.org/?probe=ebe0f52831) | May 10, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [d2d1037c9d](https://linux-hardware.org/?probe=d2d1037c9d) | May 09, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [aa31c3dd8f](https://linux-hardware.org/?probe=aa31c3dd8f) | May 09, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [c39e7fa08d](https://linux-hardware.org/?probe=c39e7fa08d) | May 09, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [dc1db599ea](https://linux-hardware.org/?probe=dc1db599ea) | May 09, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [40d1bba9e2](https://linux-hardware.org/?probe=40d1bba9e2) | May 07, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [e2ce1c3d6c](https://linux-hardware.org/?probe=e2ce1c3d6c) | May 07, 2023 |
| Gigabyte      | P43-ES3G                    | Desktop     | [1095d1ef7f](https://linux-hardware.org/?probe=1095d1ef7f) | May 06, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [de65a79bf1](https://linux-hardware.org/?probe=de65a79bf1) | May 06, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [4b76463d57](https://linux-hardware.org/?probe=4b76463d57) | May 06, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [b0a2a0b536](https://linux-hardware.org/?probe=b0a2a0b536) | May 06, 2023 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [5c506f94e0](https://linux-hardware.org/?probe=5c506f94e0) | May 05, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [d7c37a25de](https://linux-hardware.org/?probe=d7c37a25de) | May 05, 2023 |
| Samsung       | 535U3C                      | Notebook    | [5f2e46be0a](https://linux-hardware.org/?probe=5f2e46be0a) | May 05, 2023 |
| ASUSTek       | B85-PLUS                    | Desktop     | [352e8b2616](https://linux-hardware.org/?probe=352e8b2616) | May 03, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [017222d810](https://linux-hardware.org/?probe=017222d810) | May 02, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | Notebook    | [b54238dc33](https://linux-hardware.org/?probe=b54238dc33) | May 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [62d194e85e](https://linux-hardware.org/?probe=62d194e85e) | May 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [e2acacabb3](https://linux-hardware.org/?probe=e2acacabb3) | Apr 30, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [8aa973e0f5](https://linux-hardware.org/?probe=8aa973e0f5) | Apr 30, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [9419686ec7](https://linux-hardware.org/?probe=9419686ec7) | Apr 30, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [1f61fda034](https://linux-hardware.org/?probe=1f61fda034) | Apr 30, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [b2616ea409](https://linux-hardware.org/?probe=b2616ea409) | Apr 28, 2023 |
| HP            | Unknown                     | Notebook    | [bba45b8ff0](https://linux-hardware.org/?probe=bba45b8ff0) | Apr 27, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [169e095fab](https://linux-hardware.org/?probe=169e095fab) | Apr 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c80b811f3e](https://linux-hardware.org/?probe=c80b811f3e) | Apr 27, 2023 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [072b88204c](https://linux-hardware.org/?probe=072b88204c) | Apr 26, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [f02e8339e9](https://linux-hardware.org/?probe=f02e8339e9) | Apr 25, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [8de5e39740](https://linux-hardware.org/?probe=8de5e39740) | Apr 25, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [e4064abe78](https://linux-hardware.org/?probe=e4064abe78) | Apr 24, 2023 |
| Lenovo        | ThinkPad Edge E540 20C6C... | Notebook    | [fc22fb4921](https://linux-hardware.org/?probe=fc22fb4921) | Apr 23, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [e3dc4788e7](https://linux-hardware.org/?probe=e3dc4788e7) | Apr 22, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [8db6f88fd3](https://linux-hardware.org/?probe=8db6f88fd3) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS       | Desktop     | [28631c09aa](https://linux-hardware.org/?probe=28631c09aa) | Apr 22, 2023 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [2727f5c463](https://linux-hardware.org/?probe=2727f5c463) | Apr 21, 2023 |
| Micro Elec... | MG-VCP2-17A3070T            | Notebook    | [edf0d6d941](https://linux-hardware.org/?probe=edf0d6d941) | Apr 21, 2023 |
| Apple         | MacBookPro8,3               | Notebook    | [4004491274](https://linux-hardware.org/?probe=4004491274) | Apr 21, 2023 |
| Fujitsu       | LIFEBOOK A557               | Notebook    | [712657fa81](https://linux-hardware.org/?probe=712657fa81) | Apr 20, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [47831c9091](https://linux-hardware.org/?probe=47831c9091) | Apr 18, 2023 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [c248c05349](https://linux-hardware.org/?probe=c248c05349) | Apr 18, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [28d52a565b](https://linux-hardware.org/?probe=28d52a565b) | Apr 18, 2023 |
| MSI           | Z87M GAMING                 | Desktop     | [9552ef2174](https://linux-hardware.org/?probe=9552ef2174) | Apr 17, 2023 |
| HP            | 18E7                        | Desktop     | [ef0b00cf80](https://linux-hardware.org/?probe=ef0b00cf80) | Apr 17, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [d40208e7f6](https://linux-hardware.org/?probe=d40208e7f6) | Apr 17, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [7371569bbf](https://linux-hardware.org/?probe=7371569bbf) | Apr 15, 2023 |
| Supermicro    | X10SAE                      | Server      | [4b0cfec9a7](https://linux-hardware.org/?probe=4b0cfec9a7) | Apr 15, 2023 |
| Dell          | 0KWVT8 A00                  | Desktop     | [d1084f0d90](https://linux-hardware.org/?probe=d1084f0d90) | Apr 15, 2023 |
| ASUSTek       | A68HM-K                     | Desktop     | [6419c7fb77](https://linux-hardware.org/?probe=6419c7fb77) | Apr 15, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [26db4eab1f](https://linux-hardware.org/?probe=26db4eab1f) | Apr 15, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [d49b1775be](https://linux-hardware.org/?probe=d49b1775be) | Apr 14, 2023 |
| Dell          | 0XR1GT A00                  | Desktop     | [1c8d776510](https://linux-hardware.org/?probe=1c8d776510) | Apr 13, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [2f29d1d7b8](https://linux-hardware.org/?probe=2f29d1d7b8) | Apr 13, 2023 |
| Dell          | 0XR1GT A00                  | Desktop     | [06e6f2f745](https://linux-hardware.org/?probe=06e6f2f745) | Apr 13, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [222d699e31](https://linux-hardware.org/?probe=222d699e31) | Apr 13, 2023 |
| Dell          | Vostro 7590                 | Notebook    | [f759d8ab72](https://linux-hardware.org/?probe=f759d8ab72) | Apr 13, 2023 |
| Dell          | 0KWVT8 A00                  | Desktop     | [4cea64e81b](https://linux-hardware.org/?probe=4cea64e81b) | Apr 13, 2023 |
| GEO           | GeoBook 120                 | Notebook    | [2e51a1bab5](https://linux-hardware.org/?probe=2e51a1bab5) | Apr 12, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [406c02acb0](https://linux-hardware.org/?probe=406c02acb0) | Apr 12, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [7b4e6e07cf](https://linux-hardware.org/?probe=7b4e6e07cf) | Apr 12, 2023 |
| Unknown       | ACB20                       | Notebook    | [16543ac693](https://linux-hardware.org/?probe=16543ac693) | Apr 12, 2023 |
| Unknown       | ACB20                       | Notebook    | [4c0422096b](https://linux-hardware.org/?probe=4c0422096b) | Apr 12, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [8abf9b082b](https://linux-hardware.org/?probe=8abf9b082b) | Apr 12, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [3e3a141713](https://linux-hardware.org/?probe=3e3a141713) | Apr 11, 2023 |
| HP            | 805F                        | Desktop     | [07bd1b4df7](https://linux-hardware.org/?probe=07bd1b4df7) | Apr 11, 2023 |
| HP            | 805F                        | Desktop     | [7863ff02eb](https://linux-hardware.org/?probe=7863ff02eb) | Apr 11, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [eb03b75c27](https://linux-hardware.org/?probe=eb03b75c27) | Apr 11, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [b35b8e1503](https://linux-hardware.org/?probe=b35b8e1503) | Apr 09, 2023 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [e0913458ee](https://linux-hardware.org/?probe=e0913458ee) | Apr 07, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | Desktop     | [5a044a37f7](https://linux-hardware.org/?probe=5a044a37f7) | Apr 07, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | Desktop     | [81a8d7a1fc](https://linux-hardware.org/?probe=81a8d7a1fc) | Apr 07, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [c599e701fc](https://linux-hardware.org/?probe=c599e701fc) | Apr 06, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [7aec6da94d](https://linux-hardware.org/?probe=7aec6da94d) | Apr 05, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [aa3b0a7d6f](https://linux-hardware.org/?probe=aa3b0a7d6f) | Apr 04, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [731bd99503](https://linux-hardware.org/?probe=731bd99503) | Apr 03, 2023 |
| Gigabyte      | Z77P-D3                     | Desktop     | [e97e71fc7a](https://linux-hardware.org/?probe=e97e71fc7a) | Apr 02, 2023 |
| Gigabyte      | Z77P-D3                     | Desktop     | [f96e01d74d](https://linux-hardware.org/?probe=f96e01d74d) | Apr 01, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [539137fb36](https://linux-hardware.org/?probe=539137fb36) | Apr 01, 2023 |
| Unknown       | ACB20                       | Notebook    | [6e70bacda5](https://linux-hardware.org/?probe=6e70bacda5) | Apr 01, 2023 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [4434a1266b](https://linux-hardware.org/?probe=4434a1266b) | Mar 31, 2023 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [fbef2fe274](https://linux-hardware.org/?probe=fbef2fe274) | Mar 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [d79127e48c](https://linux-hardware.org/?probe=d79127e48c) | Mar 31, 2023 |
| Intel         | X79                         | Desktop     | [c06125262b](https://linux-hardware.org/?probe=c06125262b) | Mar 31, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [f0540604bc](https://linux-hardware.org/?probe=f0540604bc) | Mar 30, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [1c575e8cb6](https://linux-hardware.org/?probe=1c575e8cb6) | Mar 30, 2023 |
| ASRock        | X470 Master SLI             | Desktop     | [e4d56ca8c8](https://linux-hardware.org/?probe=e4d56ca8c8) | Mar 28, 2023 |
| ASUSTek       | M3N78 PRO                   | Desktop     | [0f9abe9400](https://linux-hardware.org/?probe=0f9abe9400) | Mar 28, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [5242d56a0f](https://linux-hardware.org/?probe=5242d56a0f) | Mar 27, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [ebb59fa31d](https://linux-hardware.org/?probe=ebb59fa31d) | Mar 27, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [b084807397](https://linux-hardware.org/?probe=b084807397) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [bc38c5ed22](https://linux-hardware.org/?probe=bc38c5ed22) | Mar 26, 2023 |
| Gigabyte      | AERO 15 XD                  | Notebook    | [51fd5b8510](https://linux-hardware.org/?probe=51fd5b8510) | Mar 25, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [6601de8aae](https://linux-hardware.org/?probe=6601de8aae) | Mar 25, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [8e1cd2ea46](https://linux-hardware.org/?probe=8e1cd2ea46) | Mar 24, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [9240540b33](https://linux-hardware.org/?probe=9240540b33) | Mar 24, 2023 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [82a69c4ec6](https://linux-hardware.org/?probe=82a69c4ec6) | Mar 23, 2023 |
| Intel         | powered classmate PC        | Notebook    | [0d64280b6d](https://linux-hardware.org/?probe=0d64280b6d) | Mar 22, 2023 |
| ASRock        | B660M-ITX/ac                | Desktop     | [95687a223c](https://linux-hardware.org/?probe=95687a223c) | Mar 22, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [70a7fd895e](https://linux-hardware.org/?probe=70a7fd895e) | Mar 22, 2023 |
| Lenovo        | Unknown                     | Notebook    | [121f022799](https://linux-hardware.org/?probe=121f022799) | Mar 21, 2023 |
| Acer          | Extensa 2510G               | Notebook    | [1ac79f58a4](https://linux-hardware.org/?probe=1ac79f58a4) | Mar 21, 2023 |
| Dell          | 0XR1GT A00                  | Desktop     | [0912041935](https://linux-hardware.org/?probe=0912041935) | Mar 21, 2023 |
| Lenovo        | IP 5-14ALC05 82LM           | Notebook    | [5bacaa401a](https://linux-hardware.org/?probe=5bacaa401a) | Mar 21, 2023 |
| Dell          | 0XR1GT A00                  | Desktop     | [61e1c5eff9](https://linux-hardware.org/?probe=61e1c5eff9) | Mar 21, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [ca34d8e7d4](https://linux-hardware.org/?probe=ca34d8e7d4) | Mar 20, 2023 |
| Acidanther... | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [eba8868f8b](https://linux-hardware.org/?probe=eba8868f8b) | Mar 20, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [7891e82ac4](https://linux-hardware.org/?probe=7891e82ac4) | Mar 17, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [6ad4034797](https://linux-hardware.org/?probe=6ad4034797) | Mar 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [7e6ae6ba16](https://linux-hardware.org/?probe=7e6ae6ba16) | Mar 17, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [2530e262d2](https://linux-hardware.org/?probe=2530e262d2) | Mar 17, 2023 |
| ASUSTek       | X580VD                      | Notebook    | [8c4023bd5d](https://linux-hardware.org/?probe=8c4023bd5d) | Mar 16, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | Mini pc     | [ab9d7b857f](https://linux-hardware.org/?probe=ab9d7b857f) | Mar 16, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | Mini pc     | [7659c07b7c](https://linux-hardware.org/?probe=7659c07b7c) | Mar 16, 2023 |
| ASUSTek       | X580VD                      | Notebook    | [26b62abfc9](https://linux-hardware.org/?probe=26b62abfc9) | Mar 16, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [ab4a88037a](https://linux-hardware.org/?probe=ab4a88037a) | Mar 16, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [37bf97e9b3](https://linux-hardware.org/?probe=37bf97e9b3) | Mar 16, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [23e21d1440](https://linux-hardware.org/?probe=23e21d1440) | Mar 15, 2023 |
| Gigabyte      | Z77P-D3                     | Desktop     | [34ad3eb730](https://linux-hardware.org/?probe=34ad3eb730) | Mar 15, 2023 |
| Gigabyte      | Z77P-D3                     | Desktop     | [06c53ecdec](https://linux-hardware.org/?probe=06c53ecdec) | Mar 15, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [7637d41bf3](https://linux-hardware.org/?probe=7637d41bf3) | Mar 14, 2023 |
| Intel         | DB85FL AAG89861-203         | Desktop     | [e17dae3447](https://linux-hardware.org/?probe=e17dae3447) | Mar 14, 2023 |
| Intel         | DB85FL AAG89861-203         | Desktop     | [f1004a32e1](https://linux-hardware.org/?probe=f1004a32e1) | Mar 14, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [727390b14d](https://linux-hardware.org/?probe=727390b14d) | Mar 14, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [0eefdece9c](https://linux-hardware.org/?probe=0eefdece9c) | Mar 13, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [7320131972](https://linux-hardware.org/?probe=7320131972) | Mar 13, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [01bfc3e026](https://linux-hardware.org/?probe=01bfc3e026) | Mar 13, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [e41f3ed4ab](https://linux-hardware.org/?probe=e41f3ed4ab) | Mar 13, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [1ad75bea9c](https://linux-hardware.org/?probe=1ad75bea9c) | Mar 12, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [3ec784f6be](https://linux-hardware.org/?probe=3ec784f6be) | Mar 11, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | Notebook    | [9b021e4844](https://linux-hardware.org/?probe=9b021e4844) | Mar 11, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [126b4a73a2](https://linux-hardware.org/?probe=126b4a73a2) | Mar 11, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [7ba7da9138](https://linux-hardware.org/?probe=7ba7da9138) | Mar 10, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [46b213149e](https://linux-hardware.org/?probe=46b213149e) | Mar 10, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [ed7724b921](https://linux-hardware.org/?probe=ed7724b921) | Mar 10, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [6605d9e257](https://linux-hardware.org/?probe=6605d9e257) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [87eec74772](https://linux-hardware.org/?probe=87eec74772) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [38599c9b97](https://linux-hardware.org/?probe=38599c9b97) | Mar 10, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [0c14a418fb](https://linux-hardware.org/?probe=0c14a418fb) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [aa31db4d3f](https://linux-hardware.org/?probe=aa31db4d3f) | Mar 09, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [796b1ad7cb](https://linux-hardware.org/?probe=796b1ad7cb) | Mar 09, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [3629efc5a5](https://linux-hardware.org/?probe=3629efc5a5) | Mar 08, 2023 |
| HP            | ZBook 17                    | Notebook    | [e3fb994c04](https://linux-hardware.org/?probe=e3fb994c04) | Mar 08, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [15cd198548](https://linux-hardware.org/?probe=15cd198548) | Mar 07, 2023 |
| Dell          | 0773VG A01                  | Desktop     | [d954bdd915](https://linux-hardware.org/?probe=d954bdd915) | Mar 07, 2023 |
| ASRock        | H310M-HDV                   | Desktop     | [316510fe69](https://linux-hardware.org/?probe=316510fe69) | Mar 07, 2023 |
| Acer          | Aspire X1400                | Desktop     | [195337bbc6](https://linux-hardware.org/?probe=195337bbc6) | Mar 07, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [ebf75e7be8](https://linux-hardware.org/?probe=ebf75e7be8) | Mar 06, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [ef186545cb](https://linux-hardware.org/?probe=ef186545cb) | Mar 06, 2023 |
| ASUSTek       | PRIME B560M-A AC            | Desktop     | [21db48a23b](https://linux-hardware.org/?probe=21db48a23b) | Mar 06, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [6efd61c4e0](https://linux-hardware.org/?probe=6efd61c4e0) | Mar 05, 2023 |
| Dell          | Latitude 7390               | Notebook    | [892100e074](https://linux-hardware.org/?probe=892100e074) | Mar 05, 2023 |
| Acer          | Aspire VX5-591G             | Notebook    | [e5e134cc80](https://linux-hardware.org/?probe=e5e134cc80) | Mar 04, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4eb7bea837](https://linux-hardware.org/?probe=4eb7bea837) | Mar 04, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1d24df340b](https://linux-hardware.org/?probe=1d24df340b) | Mar 04, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [82994d7312](https://linux-hardware.org/?probe=82994d7312) | Mar 04, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [582bc638e0](https://linux-hardware.org/?probe=582bc638e0) | Mar 03, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [25d1509478](https://linux-hardware.org/?probe=25d1509478) | Mar 03, 2023 |
| MSI           | GP65 Leopard 9SF            | Notebook    | [45f56a0c5b](https://linux-hardware.org/?probe=45f56a0c5b) | Mar 03, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [950e36afc7](https://linux-hardware.org/?probe=950e36afc7) | Mar 03, 2023 |
| Schenker      | XMG NEO (M19, RTX 2070)     | Notebook    | [c45dbeb188](https://linux-hardware.org/?probe=c45dbeb188) | Mar 02, 2023 |
| MSI           | P65 Creator 8RD             | Notebook    | [ea8be773a9](https://linux-hardware.org/?probe=ea8be773a9) | Mar 01, 2023 |
| MSI           | P65 Creator 8RD             | Notebook    | [2b97507181](https://linux-hardware.org/?probe=2b97507181) | Mar 01, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [a3e7201f2e](https://linux-hardware.org/?probe=a3e7201f2e) | Mar 01, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [686db926da](https://linux-hardware.org/?probe=686db926da) | Mar 01, 2023 |
| MSI           | Summit E14Evo A12M          | Notebook    | [ad389112d3](https://linux-hardware.org/?probe=ad389112d3) | Mar 01, 2023 |
| MSI           | MPG Z390M GAMING EDGE AC    | Desktop     | [d0813971b9](https://linux-hardware.org/?probe=d0813971b9) | Feb 28, 2023 |
| ASRock        | B660M-ITX/ac                | Desktop     | [c2e600e445](https://linux-hardware.org/?probe=c2e600e445) | Feb 28, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [08f2d1cca5](https://linux-hardware.org/?probe=08f2d1cca5) | Feb 28, 2023 |
| ASRock        | B660M-ITX/ac                | Desktop     | [1efc15e2cc](https://linux-hardware.org/?probe=1efc15e2cc) | Feb 28, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [9c49a1748b](https://linux-hardware.org/?probe=9c49a1748b) | Feb 28, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [15318beac5](https://linux-hardware.org/?probe=15318beac5) | Feb 27, 2023 |
| MSI           | Z170A-G45 GAMING            | Desktop     | [a5496030e7](https://linux-hardware.org/?probe=a5496030e7) | Feb 27, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E EXTR... | Desktop     | [659ff1672e](https://linux-hardware.org/?probe=659ff1672e) | Feb 26, 2023 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [92f1f7d3b5](https://linux-hardware.org/?probe=92f1f7d3b5) | Feb 26, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [5d17500c5d](https://linux-hardware.org/?probe=5d17500c5d) | Feb 25, 2023 |
| MSI           | GF63 Thin 10SC              | Notebook    | [824f4eafd0](https://linux-hardware.org/?probe=824f4eafd0) | Feb 25, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [101d8d4577](https://linux-hardware.org/?probe=101d8d4577) | Feb 25, 2023 |
| Gigabyte      | AERO 15 Classic-SA          | Notebook    | [bc6078dda0](https://linux-hardware.org/?probe=bc6078dda0) | Feb 24, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [92879d708d](https://linux-hardware.org/?probe=92879d708d) | Feb 24, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [8a698df80f](https://linux-hardware.org/?probe=8a698df80f) | Feb 24, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [012415eb50](https://linux-hardware.org/?probe=012415eb50) | Feb 24, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [e1c3e1611f](https://linux-hardware.org/?probe=e1c3e1611f) | Feb 24, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [802ba906a0](https://linux-hardware.org/?probe=802ba906a0) | Feb 23, 2023 |
| Sony          | SVF1521N6EW                 | Notebook    | [41e45075c4](https://linux-hardware.org/?probe=41e45075c4) | Feb 22, 2023 |
| ASUSTek       | H97M-E                      | Desktop     | [b2ef9d5ede](https://linux-hardware.org/?probe=b2ef9d5ede) | Feb 21, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [fb4420dbc4](https://linux-hardware.org/?probe=fb4420dbc4) | Feb 20, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [737c043ed7](https://linux-hardware.org/?probe=737c043ed7) | Feb 20, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [2752a9660a](https://linux-hardware.org/?probe=2752a9660a) | Feb 19, 2023 |
| Dell          | G3 3590                     | Notebook    | [1a4fd9ed07](https://linux-hardware.org/?probe=1a4fd9ed07) | Feb 18, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [a62c4f0fcd](https://linux-hardware.org/?probe=a62c4f0fcd) | Feb 18, 2023 |
| HP            | ENVY 15                     | Notebook    | [bcdc62a706](https://linux-hardware.org/?probe=bcdc62a706) | Feb 18, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [e81d0741bb](https://linux-hardware.org/?probe=e81d0741bb) | Feb 17, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [dd63e968bd](https://linux-hardware.org/?probe=dd63e968bd) | Feb 17, 2023 |
| HP            | EliteBook Revolve 810 G1    | Notebook    | [a32189e068](https://linux-hardware.org/?probe=a32189e068) | Feb 16, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [e486b2bb46](https://linux-hardware.org/?probe=e486b2bb46) | Feb 15, 2023 |
| Dell          | 0KWVT8 A02                  | Desktop     | [486f7258a6](https://linux-hardware.org/?probe=486f7258a6) | Feb 14, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [dc91c0e32b](https://linux-hardware.org/?probe=dc91c0e32b) | Feb 14, 2023 |
| Dell          | 0KWVT8 A02                  | Desktop     | [c3d08b4f2e](https://linux-hardware.org/?probe=c3d08b4f2e) | Feb 13, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [395077145c](https://linux-hardware.org/?probe=395077145c) | Feb 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [a54bcd6d70](https://linux-hardware.org/?probe=a54bcd6d70) | Feb 13, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [b25d844a19](https://linux-hardware.org/?probe=b25d844a19) | Feb 12, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [bf986cc448](https://linux-hardware.org/?probe=bf986cc448) | Feb 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [28e98cf31f](https://linux-hardware.org/?probe=28e98cf31f) | Feb 12, 2023 |
| HP            | 17E2                        | Mini pc     | [e99d3c0a69](https://linux-hardware.org/?probe=e99d3c0a69) | Feb 12, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [74d6af0f75](https://linux-hardware.org/?probe=74d6af0f75) | Feb 11, 2023 |
| HP            | 17E2                        | Mini pc     | [ff80271dce](https://linux-hardware.org/?probe=ff80271dce) | Feb 11, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [9b95bc446b](https://linux-hardware.org/?probe=9b95bc446b) | Feb 11, 2023 |
| ASUSTek       | ROG Strix G512LI_G512LI     | Notebook    | [6c8760114a](https://linux-hardware.org/?probe=6c8760114a) | Feb 11, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [c4eb0b2a62](https://linux-hardware.org/?probe=c4eb0b2a62) | Feb 11, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [caca2e6be1](https://linux-hardware.org/?probe=caca2e6be1) | Feb 11, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [9de8235ca5](https://linux-hardware.org/?probe=9de8235ca5) | Feb 10, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [afefa761d5](https://linux-hardware.org/?probe=afefa761d5) | Feb 09, 2023 |
| MSI           | B450M BAZOOKA MAX WIFI      | Desktop     | [fdaab67fe9](https://linux-hardware.org/?probe=fdaab67fe9) | Feb 09, 2023 |
| Acer          | TravelMate P256-M           | Notebook    | [add8ce8459](https://linux-hardware.org/?probe=add8ce8459) | Feb 06, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [eece150870](https://linux-hardware.org/?probe=eece150870) | Feb 05, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [464b35f82b](https://linux-hardware.org/?probe=464b35f82b) | Feb 05, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [20086250d5](https://linux-hardware.org/?probe=20086250d5) | Feb 05, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [9905642762](https://linux-hardware.org/?probe=9905642762) | Feb 05, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [4ff2fc81bc](https://linux-hardware.org/?probe=4ff2fc81bc) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [cbac9c37ba](https://linux-hardware.org/?probe=cbac9c37ba) | Feb 04, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [0b1fbca173](https://linux-hardware.org/?probe=0b1fbca173) | Feb 03, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [8ae0d42e1a](https://linux-hardware.org/?probe=8ae0d42e1a) | Feb 03, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [513dd8e40b](https://linux-hardware.org/?probe=513dd8e40b) | Feb 03, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [5a7a0cf485](https://linux-hardware.org/?probe=5a7a0cf485) | Feb 03, 2023 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [7645e16594](https://linux-hardware.org/?probe=7645e16594) | Feb 03, 2023 |
| HP            | 834F                        | Desktop     | [394eb5f9cc](https://linux-hardware.org/?probe=394eb5f9cc) | Feb 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [c1862b275d](https://linux-hardware.org/?probe=c1862b275d) | Feb 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [1aa5d63f0c](https://linux-hardware.org/?probe=1aa5d63f0c) | Feb 01, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [7f985597d7](https://linux-hardware.org/?probe=7f985597d7) | Jan 30, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [7a35a6d886](https://linux-hardware.org/?probe=7a35a6d886) | Jan 30, 2023 |
| HP            | 8054                        | Desktop     | [36f5306e37](https://linux-hardware.org/?probe=36f5306e37) | Jan 30, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [87502e1eb2](https://linux-hardware.org/?probe=87502e1eb2) | Jan 29, 2023 |
| Lenovo        | ThinkPad T460 20FMS79000    | Notebook    | [2b397905e1](https://linux-hardware.org/?probe=2b397905e1) | Jan 29, 2023 |
| Samsung       | R520/R522/R620              | Notebook    | [8c5c4fecfe](https://linux-hardware.org/?probe=8c5c4fecfe) | Jan 28, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [1605fbe62a](https://linux-hardware.org/?probe=1605fbe62a) | Jan 28, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [95f5d0904e](https://linux-hardware.org/?probe=95f5d0904e) | Jan 26, 2023 |
| Notebook      | NP5x_NP6x_NP7xHP            | Notebook    | [3b7c64dc34](https://linux-hardware.org/?probe=3b7c64dc34) | Jan 26, 2023 |
| Monster       | ABRA A7 V12.1               | Notebook    | [1882db09fe](https://linux-hardware.org/?probe=1882db09fe) | Jan 25, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [c69db4d96f](https://linux-hardware.org/?probe=c69db4d96f) | Jan 24, 2023 |
| MSI           | Katana GF76 11UD            | Notebook    | [5a5a26c29e](https://linux-hardware.org/?probe=5a5a26c29e) | Jan 24, 2023 |
| Positivo      | N1240                       | Notebook    | [e938a6c0b0](https://linux-hardware.org/?probe=e938a6c0b0) | Jan 24, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [8cb10f3212](https://linux-hardware.org/?probe=8cb10f3212) | Jan 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [bc070879ba](https://linux-hardware.org/?probe=bc070879ba) | Jan 22, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [bc95b86800](https://linux-hardware.org/?probe=bc95b86800) | Jan 22, 2023 |
| Gigabyte      | Z77-D3H                     | Desktop     | [9035a00600](https://linux-hardware.org/?probe=9035a00600) | Jan 22, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [3eb7e4f3cf](https://linux-hardware.org/?probe=3eb7e4f3cf) | Jan 22, 2023 |
| Medion        | GUARDIAN X10                | Notebook    | [4807ed03d5](https://linux-hardware.org/?probe=4807ed03d5) | Jan 22, 2023 |
| MSI           | MPG Z390M GAMING EDGE AC    | Desktop     | [085d30a350](https://linux-hardware.org/?probe=085d30a350) | Jan 21, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [0a3fe4cb00](https://linux-hardware.org/?probe=0a3fe4cb00) | Jan 21, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [9732bb65cd](https://linux-hardware.org/?probe=9732bb65cd) | Jan 20, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | Notebook    | [844d97dd92](https://linux-hardware.org/?probe=844d97dd92) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | Desktop     | [9a70fa222c](https://linux-hardware.org/?probe=9a70fa222c) | Jan 19, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [87f11d2b18](https://linux-hardware.org/?probe=87f11d2b18) | Jan 19, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [4d52b408c2](https://linux-hardware.org/?probe=4d52b408c2) | Jan 19, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [9a0b1c62f5](https://linux-hardware.org/?probe=9a0b1c62f5) | Jan 18, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [bf838ee958](https://linux-hardware.org/?probe=bf838ee958) | Jan 18, 2023 |
| Acer          | Swift SFX14-51G             | Notebook    | [f0137b1f08](https://linux-hardware.org/?probe=f0137b1f08) | Jan 17, 2023 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [f215410f54](https://linux-hardware.org/?probe=f215410f54) | Jan 17, 2023 |
| ASUSTek       | Z97-A                       | Desktop     | [c1b01960be](https://linux-hardware.org/?probe=c1b01960be) | Jan 17, 2023 |
| MSI           | Katana GF76 11UD            | Notebook    | [dcc8c2a63b](https://linux-hardware.org/?probe=dcc8c2a63b) | Jan 17, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [b49ce7a30a](https://linux-hardware.org/?probe=b49ce7a30a) | Jan 15, 2023 |
| Lenovo        | ThinkPad P51 20HJS02H00     | Notebook    | [ab26ff36b1](https://linux-hardware.org/?probe=ab26ff36b1) | Jan 14, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [aade436557](https://linux-hardware.org/?probe=aade436557) | Jan 14, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [5b50555e06](https://linux-hardware.org/?probe=5b50555e06) | Jan 13, 2023 |
| ASUSTek       | P9X79 DELUXE                | Desktop     | [d73373e8e9](https://linux-hardware.org/?probe=d73373e8e9) | Jan 13, 2023 |
| AZW           | S3                          | Mini pc     | [0e94de97c8](https://linux-hardware.org/?probe=0e94de97c8) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [73da880450](https://linux-hardware.org/?probe=73da880450) | Jan 12, 2023 |
| Medion        | GUARDIAN X10                | Notebook    | [ef011d0700](https://linux-hardware.org/?probe=ef011d0700) | Jan 10, 2023 |
| HP            | Pavilion 15                 | Notebook    | [e60b327d4c](https://linux-hardware.org/?probe=e60b327d4c) | Jan 10, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [899e519abe](https://linux-hardware.org/?probe=899e519abe) | Jan 10, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [9f368d248b](https://linux-hardware.org/?probe=9f368d248b) | Jan 10, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [d679fb0fd0](https://linux-hardware.org/?probe=d679fb0fd0) | Jan 10, 2023 |
| MSI           | GT680R/GX680R/GT683R/GT6... | Notebook    | [0b23cb61e0](https://linux-hardware.org/?probe=0b23cb61e0) | Jan 09, 2023 |
| HP            | 8054                        | Desktop     | [d4398dee29](https://linux-hardware.org/?probe=d4398dee29) | Jan 08, 2023 |
| MSI           | MAG B560M MORTAR WIFI       | Desktop     | [33f6781ba8](https://linux-hardware.org/?probe=33f6781ba8) | Jan 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c74a6daaaa](https://linux-hardware.org/?probe=c74a6daaaa) | Jan 07, 2023 |
| ASRock        | X470 Master SLI             | Desktop     | [c138f9159c](https://linux-hardware.org/?probe=c138f9159c) | Jan 07, 2023 |
| HP            | 1497                        | Desktop     | [71550a0f21](https://linux-hardware.org/?probe=71550a0f21) | Jan 07, 2023 |
| ASRock        | H77M-ITX                    | Desktop     | [fb6cbfce9a](https://linux-hardware.org/?probe=fb6cbfce9a) | Jan 06, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [406b407b64](https://linux-hardware.org/?probe=406b407b64) | Jan 06, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [61b7c0cda0](https://linux-hardware.org/?probe=61b7c0cda0) | Jan 06, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [569f5cd751](https://linux-hardware.org/?probe=569f5cd751) | Jan 06, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [3978c4253f](https://linux-hardware.org/?probe=3978c4253f) | Jan 06, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [8c219aafe4](https://linux-hardware.org/?probe=8c219aafe4) | Jan 05, 2023 |
| ASUSTek       | G20AJ                       | Desktop     | [9be7e0b11f](https://linux-hardware.org/?probe=9be7e0b11f) | Jan 05, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [b6bf9d074f](https://linux-hardware.org/?probe=b6bf9d074f) | Jan 05, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [11d17c68b8](https://linux-hardware.org/?probe=11d17c68b8) | Jan 05, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [6f4cc6e4c7](https://linux-hardware.org/?probe=6f4cc6e4c7) | Jan 05, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [7655f77ada](https://linux-hardware.org/?probe=7655f77ada) | Jan 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [6c40dc7dd6](https://linux-hardware.org/?probe=6c40dc7dd6) | Jan 03, 2023 |
| ASRock        | X570 Phantom Gaming-ITX/... | Notebook    | [f097aa1c92](https://linux-hardware.org/?probe=f097aa1c92) | Jan 03, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [97f93aa235](https://linux-hardware.org/?probe=97f93aa235) | Dec 31, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [6d047b6620](https://linux-hardware.org/?probe=6d047b6620) | Dec 30, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [26e56628ec](https://linux-hardware.org/?probe=26e56628ec) | Dec 30, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [dc7201711c](https://linux-hardware.org/?probe=dc7201711c) | Dec 30, 2022 |
| Lenovo        | 3181 SEK0T35577 IOT 4247... | Mini pc     | [fa1b60ae23](https://linux-hardware.org/?probe=fa1b60ae23) | Dec 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [4ca2070d42](https://linux-hardware.org/?probe=4ca2070d42) | Dec 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [7ef5d874e9](https://linux-hardware.org/?probe=7ef5d874e9) | Dec 28, 2022 |
| HP            | ENVY Notebook               | Notebook    | [8c7d592182](https://linux-hardware.org/?probe=8c7d592182) | Dec 26, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [b9e4ff3fea](https://linux-hardware.org/?probe=b9e4ff3fea) | Dec 25, 2022 |
| HP            | 1589                        | Desktop     | [4769414712](https://linux-hardware.org/?probe=4769414712) | Dec 24, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [978bb114dc](https://linux-hardware.org/?probe=978bb114dc) | Dec 23, 2022 |
| Dell          | G15 5510                    | Notebook    | [86d0642973](https://linux-hardware.org/?probe=86d0642973) | Dec 20, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [353cbeb5c8](https://linux-hardware.org/?probe=353cbeb5c8) | Dec 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [03da9468fc](https://linux-hardware.org/?probe=03da9468fc) | Dec 19, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [2a1a679e03](https://linux-hardware.org/?probe=2a1a679e03) | Dec 18, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [d3517edb25](https://linux-hardware.org/?probe=d3517edb25) | Dec 17, 2022 |
| Acer          | Aspire E5-551G              | Notebook    | [56f5130537](https://linux-hardware.org/?probe=56f5130537) | Dec 17, 2022 |
| Biostar       | X470GTN                     | Desktop     | [7c067277b2](https://linux-hardware.org/?probe=7c067277b2) | Dec 17, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [3bc811ef2a](https://linux-hardware.org/?probe=3bc811ef2a) | Dec 17, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [0a2731119d](https://linux-hardware.org/?probe=0a2731119d) | Dec 16, 2022 |
| HP            | 2ABD A01                    | Desktop     | [c5c5c07485](https://linux-hardware.org/?probe=c5c5c07485) | Dec 16, 2022 |
| HP            | 2ABD A01                    | Desktop     | [c992b15fbe](https://linux-hardware.org/?probe=c992b15fbe) | Dec 16, 2022 |
| Dynabook      | PORTEGE X30L-K              | Notebook    | [6f9a9428b6](https://linux-hardware.org/?probe=6f9a9428b6) | Dec 16, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [fc8f4624a4](https://linux-hardware.org/?probe=fc8f4624a4) | Dec 16, 2022 |
| ASRock        | H310M-HDV/M.2               | Desktop     | [76dff63f5c](https://linux-hardware.org/?probe=76dff63f5c) | Dec 15, 2022 |
| Dynabook      | PORTEGE X30L-K              | Notebook    | [28c00eabe8](https://linux-hardware.org/?probe=28c00eabe8) | Dec 14, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [4378eff64f](https://linux-hardware.org/?probe=4378eff64f) | Dec 13, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [6177c6a156](https://linux-hardware.org/?probe=6177c6a156) | Dec 13, 2022 |
| MSI           | MAG B660 TOMAHAWK WIFI      | Desktop     | [1beb5ff3c4](https://linux-hardware.org/?probe=1beb5ff3c4) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [3f57fa2c71](https://linux-hardware.org/?probe=3f57fa2c71) | Dec 12, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [52f0fae7e4](https://linux-hardware.org/?probe=52f0fae7e4) | Dec 12, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [be0c42b073](https://linux-hardware.org/?probe=be0c42b073) | Dec 12, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [52a8f66027](https://linux-hardware.org/?probe=52a8f66027) | Dec 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [febce6b929](https://linux-hardware.org/?probe=febce6b929) | Dec 09, 2022 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [94b281cfa1](https://linux-hardware.org/?probe=94b281cfa1) | Dec 09, 2022 |
| Gigabyte      | H81M-H                      | Desktop     | [02ba14a443](https://linux-hardware.org/?probe=02ba14a443) | Dec 09, 2022 |
| Dell          | 0215PR A02                  | Desktop     | [b9d16b98d2](https://linux-hardware.org/?probe=b9d16b98d2) | Dec 09, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [4fd43d5aff](https://linux-hardware.org/?probe=4fd43d5aff) | Dec 09, 2022 |
| Gigabyte      | Z590I VISION D              | Desktop     | [9cc2be8747](https://linux-hardware.org/?probe=9cc2be8747) | Dec 09, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [13e9fa6c58](https://linux-hardware.org/?probe=13e9fa6c58) | Dec 09, 2022 |
| MSI           | GF615M-P33                  | Desktop     | [af4d483414](https://linux-hardware.org/?probe=af4d483414) | Dec 08, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [d7b2726838](https://linux-hardware.org/?probe=d7b2726838) | Dec 08, 2022 |
| Dynabook      | PORTEGE X30L-K              | Notebook    | [75a8aa38fc](https://linux-hardware.org/?probe=75a8aa38fc) | Dec 08, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [c9cc6de1c4](https://linux-hardware.org/?probe=c9cc6de1c4) | Dec 08, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [8973296b3b](https://linux-hardware.org/?probe=8973296b3b) | Dec 08, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [f5bd8a0e5b](https://linux-hardware.org/?probe=f5bd8a0e5b) | Dec 07, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [07bf98d8f7](https://linux-hardware.org/?probe=07bf98d8f7) | Dec 07, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [a742429421](https://linux-hardware.org/?probe=a742429421) | Dec 06, 2022 |
| HP            | Laptop 14-cm1xxx            | Notebook    | [6fbbd3608f](https://linux-hardware.org/?probe=6fbbd3608f) | Dec 06, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [e23dd27dc9](https://linux-hardware.org/?probe=e23dd27dc9) | Dec 06, 2022 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | Notebook    | [5ce6793478](https://linux-hardware.org/?probe=5ce6793478) | Dec 06, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f2025f3847](https://linux-hardware.org/?probe=f2025f3847) | Dec 04, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [69ed3a0345](https://linux-hardware.org/?probe=69ed3a0345) | Dec 02, 2022 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [1775ec9d4b](https://linux-hardware.org/?probe=1775ec9d4b) | Dec 01, 2022 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [097d1c062e](https://linux-hardware.org/?probe=097d1c062e) | Dec 01, 2022 |
| Gigabyte      | Z590I VISION D              | Desktop     | [655e907d62](https://linux-hardware.org/?probe=655e907d62) | Dec 01, 2022 |
| Intel         | X79G V2.x                   | Desktop     | [6b229554fc](https://linux-hardware.org/?probe=6b229554fc) | Nov 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [ef85b8ab38](https://linux-hardware.org/?probe=ef85b8ab38) | Nov 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [622315486c](https://linux-hardware.org/?probe=622315486c) | Nov 28, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [407b574c57](https://linux-hardware.org/?probe=407b574c57) | Nov 28, 2022 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [ae30b95cd8](https://linux-hardware.org/?probe=ae30b95cd8) | Nov 26, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [91fa73480c](https://linux-hardware.org/?probe=91fa73480c) | Nov 26, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [93576caa19](https://linux-hardware.org/?probe=93576caa19) | Nov 26, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | Notebook    | [eded61b721](https://linux-hardware.org/?probe=eded61b721) | Nov 25, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [be2f8c9fd3](https://linux-hardware.org/?probe=be2f8c9fd3) | Nov 24, 2022 |
| HP            | ProBook 445 14 inch G9 N... | Notebook    | [a20535bd66](https://linux-hardware.org/?probe=a20535bd66) | Nov 24, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Notebook    | [9324629428](https://linux-hardware.org/?probe=9324629428) | Nov 24, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Notebook    | [22a1c81a68](https://linux-hardware.org/?probe=22a1c81a68) | Nov 24, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [afea73cc2a](https://linux-hardware.org/?probe=afea73cc2a) | Nov 22, 2022 |
| Coradir       | Coradir/ES10IS5             | Notebook    | [a1fb1953ad](https://linux-hardware.org/?probe=a1fb1953ad) | Nov 22, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [6e28c07a6c](https://linux-hardware.org/?probe=6e28c07a6c) | Nov 22, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [56c9fb93ce](https://linux-hardware.org/?probe=56c9fb93ce) | Nov 22, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [1ec2520541](https://linux-hardware.org/?probe=1ec2520541) | Nov 22, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [0fd2d81cad](https://linux-hardware.org/?probe=0fd2d81cad) | Nov 22, 2022 |
| OEM           | SHARKBAY JHS695             | Desktop     | [03c915bbd9](https://linux-hardware.org/?probe=03c915bbd9) | Nov 22, 2022 |
| MSI           | GF615M-P33                  | Desktop     | [7a6be335c4](https://linux-hardware.org/?probe=7a6be335c4) | Nov 22, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [7fba8e38dc](https://linux-hardware.org/?probe=7fba8e38dc) | Nov 20, 2022 |
| Lenovo        | ThinkPad X240 20AMA0LTAU    | Notebook    | [54ce03d1f1](https://linux-hardware.org/?probe=54ce03d1f1) | Nov 20, 2022 |
| HP            | Unknown                     | Notebook    | [9b1181bc4b](https://linux-hardware.org/?probe=9b1181bc4b) | Nov 19, 2022 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [87406f0722](https://linux-hardware.org/?probe=87406f0722) | Nov 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [93ad560f52](https://linux-hardware.org/?probe=93ad560f52) | Nov 17, 2022 |
| Alienware     | 0PGRP5 A01                  | Desktop     | [2ff9360669](https://linux-hardware.org/?probe=2ff9360669) | Nov 17, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [750d7eb0d7](https://linux-hardware.org/?probe=750d7eb0d7) | Nov 16, 2022 |
| Dell          | Studio 1737                 | Notebook    | [883ac54ca7](https://linux-hardware.org/?probe=883ac54ca7) | Nov 15, 2022 |
| ZOTAC         | ZBOX-CI320NANO series Re... | Mini pc     | [ab1c46c857](https://linux-hardware.org/?probe=ab1c46c857) | Nov 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [3ee89779cd](https://linux-hardware.org/?probe=3ee89779cd) | Nov 15, 2022 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [4d4d5aa456](https://linux-hardware.org/?probe=4d4d5aa456) | Nov 15, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [978fdef2f8](https://linux-hardware.org/?probe=978fdef2f8) | Nov 13, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [b33f7744b5](https://linux-hardware.org/?probe=b33f7744b5) | Nov 13, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [9d7853c05b](https://linux-hardware.org/?probe=9d7853c05b) | Nov 13, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [d4240ae5c7](https://linux-hardware.org/?probe=d4240ae5c7) | Nov 12, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [a8023a34a0](https://linux-hardware.org/?probe=a8023a34a0) | Nov 11, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [51d6598b74](https://linux-hardware.org/?probe=51d6598b74) | Nov 11, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [70daf967f2](https://linux-hardware.org/?probe=70daf967f2) | Nov 10, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [a49a1465d3](https://linux-hardware.org/?probe=a49a1465d3) | Nov 10, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [3d53644c05](https://linux-hardware.org/?probe=3d53644c05) | Nov 08, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | Notebook    | [c6460ff904](https://linux-hardware.org/?probe=c6460ff904) | Nov 07, 2022 |
| Dell          | Studio 1737                 | Notebook    | [d286ea1b6c](https://linux-hardware.org/?probe=d286ea1b6c) | Nov 07, 2022 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [5e151ea22f](https://linux-hardware.org/?probe=5e151ea22f) | Nov 07, 2022 |
| Intel         | D33217GKE G76540-207        | Desktop     | [f90e6e931c](https://linux-hardware.org/?probe=f90e6e931c) | Nov 07, 2022 |
| Intel         | D33217GKE G76540-207        | Desktop     | [a154fd19a0](https://linux-hardware.org/?probe=a154fd19a0) | Nov 07, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [4239b9f4a9](https://linux-hardware.org/?probe=4239b9f4a9) | Nov 06, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [05529fe361](https://linux-hardware.org/?probe=05529fe361) | Nov 06, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [55d7ddf0c8](https://linux-hardware.org/?probe=55d7ddf0c8) | Nov 06, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [677dcff84a](https://linux-hardware.org/?probe=677dcff84a) | Nov 06, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [049bac8501](https://linux-hardware.org/?probe=049bac8501) | Nov 06, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [5ca257fd77](https://linux-hardware.org/?probe=5ca257fd77) | Nov 06, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Notebook    | [bd9e0be4e8](https://linux-hardware.org/?probe=bd9e0be4e8) | Nov 03, 2022 |
| ASUSTek       | GL753VD                     | Notebook    | [97e2ee4ee1](https://linux-hardware.org/?probe=97e2ee4ee1) | Nov 01, 2022 |
| HP            | Unknown                     | Notebook    | [1ca885060e](https://linux-hardware.org/?probe=1ca885060e) | Nov 01, 2022 |
| ECS           | H61H2-CM                    | Desktop     | [792ce0e34e](https://linux-hardware.org/?probe=792ce0e34e) | Oct 31, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [3a00ca53c8](https://linux-hardware.org/?probe=3a00ca53c8) | Oct 31, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [d322bb2739](https://linux-hardware.org/?probe=d322bb2739) | Oct 30, 2022 |
| Apple         | MacBookPro13,3              | Notebook    | [b028075707](https://linux-hardware.org/?probe=b028075707) | Oct 30, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [4fdbc3c415](https://linux-hardware.org/?probe=4fdbc3c415) | Oct 30, 2022 |
| ASRock        | Z77 Pro4                    | Desktop     | [5ab5790e5f](https://linux-hardware.org/?probe=5ab5790e5f) | Oct 29, 2022 |
| ASRock        | Z77 Pro4                    | Desktop     | [74cc7f147b](https://linux-hardware.org/?probe=74cc7f147b) | Oct 29, 2022 |
| HP            | 8653 A                      | Desktop     | [bc1f3b445b](https://linux-hardware.org/?probe=bc1f3b445b) | Oct 28, 2022 |
| ASRock        | X570 Taichi                 | Desktop     | [967f52e510](https://linux-hardware.org/?probe=967f52e510) | Oct 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [50a8c356f0](https://linux-hardware.org/?probe=50a8c356f0) | Oct 28, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [c25493f420](https://linux-hardware.org/?probe=c25493f420) | Oct 27, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [7e31b6af67](https://linux-hardware.org/?probe=7e31b6af67) | Oct 27, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [6823943242](https://linux-hardware.org/?probe=6823943242) | Oct 27, 2022 |
| Intel         | B75                         | Desktop     | [eb7c27f1e5](https://linux-hardware.org/?probe=eb7c27f1e5) | Oct 26, 2022 |
| HP            | 3029h                       | Desktop     | [c278953154](https://linux-hardware.org/?probe=c278953154) | Oct 25, 2022 |
| ASUSTek       | GL502VMK                    | Notebook    | [9a18ff1b13](https://linux-hardware.org/?probe=9a18ff1b13) | Oct 25, 2022 |
| Gigabyte      | Z590I VISION D              | Desktop     | [be4c6573cd](https://linux-hardware.org/?probe=be4c6573cd) | Oct 25, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c0b3f0d88e](https://linux-hardware.org/?probe=c0b3f0d88e) | Oct 24, 2022 |
| Toshiba       | Satellite L850              | Notebook    | [8bfeff52e6](https://linux-hardware.org/?probe=8bfeff52e6) | Oct 24, 2022 |
| ASUSTek       | S550CB                      | Notebook    | [a81f0ecac8](https://linux-hardware.org/?probe=a81f0ecac8) | Oct 24, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [7e40be1c82](https://linux-hardware.org/?probe=7e40be1c82) | Oct 23, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [3912d818bd](https://linux-hardware.org/?probe=3912d818bd) | Oct 23, 2022 |
| HP            | OMEN Notebook PC 15         | Notebook    | [1d5ebc92c4](https://linux-hardware.org/?probe=1d5ebc92c4) | Oct 23, 2022 |
| Gigabyte      | Z97-HD3                     | Desktop     | [f79eb0cbb0](https://linux-hardware.org/?probe=f79eb0cbb0) | Oct 23, 2022 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | Desktop     | [c3b1784ecc](https://linux-hardware.org/?probe=c3b1784ecc) | Oct 21, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [eaecfdf473](https://linux-hardware.org/?probe=eaecfdf473) | Oct 21, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [c044987599](https://linux-hardware.org/?probe=c044987599) | Oct 20, 2022 |
| HP            | EliteBook 850 G2            | Notebook    | [b6fd429ceb](https://linux-hardware.org/?probe=b6fd429ceb) | Oct 20, 2022 |
| HP            | EliteBook 850 G2            | Notebook    | [f33baf66a9](https://linux-hardware.org/?probe=f33baf66a9) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [e5a34da4a2](https://linux-hardware.org/?probe=e5a34da4a2) | Oct 19, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c901f6927c](https://linux-hardware.org/?probe=c901f6927c) | Oct 18, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | Notebook    | [829326a8e5](https://linux-hardware.org/?probe=829326a8e5) | Oct 18, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | Notebook    | [697ccec46b](https://linux-hardware.org/?probe=697ccec46b) | Oct 18, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [dfeb98414b](https://linux-hardware.org/?probe=dfeb98414b) | Oct 18, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [7f8c9d778c](https://linux-hardware.org/?probe=7f8c9d778c) | Oct 18, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [624be3f0f3](https://linux-hardware.org/?probe=624be3f0f3) | Oct 17, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [cb63aa5619](https://linux-hardware.org/?probe=cb63aa5619) | Oct 17, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [a4919afa07](https://linux-hardware.org/?probe=a4919afa07) | Oct 16, 2022 |
| Casper        | EXCALIBUR G770              | Notebook    | [7961a3ca3e](https://linux-hardware.org/?probe=7961a3ca3e) | Oct 14, 2022 |
| MSI           | Z87 XPOWER                  | Desktop     | [5e73f5004a](https://linux-hardware.org/?probe=5e73f5004a) | Oct 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [0a89e9b77e](https://linux-hardware.org/?probe=0a89e9b77e) | Oct 13, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [5f013faf39](https://linux-hardware.org/?probe=5f013faf39) | Oct 12, 2022 |
| Toshiba       | Satellite L650              | Notebook    | [89f43e5484](https://linux-hardware.org/?probe=89f43e5484) | Oct 12, 2022 |
| Toshiba       | Satellite L650              | Notebook    | [43f57daebb](https://linux-hardware.org/?probe=43f57daebb) | Oct 12, 2022 |
| MSI           | Pulse GL76 12UEK            | Notebook    | [6a2be4d08c](https://linux-hardware.org/?probe=6a2be4d08c) | Oct 12, 2022 |
| EVOO          | EG-LP10                     | Notebook    | [f8895e9483](https://linux-hardware.org/?probe=f8895e9483) | Oct 11, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [a920c57a3e](https://linux-hardware.org/?probe=a920c57a3e) | Oct 11, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [2aa595867e](https://linux-hardware.org/?probe=2aa595867e) | Oct 11, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [bd224480a9](https://linux-hardware.org/?probe=bd224480a9) | Oct 10, 2022 |
| Dell          | 0F6X5P A00                  | Desktop     | [49baafbc65](https://linux-hardware.org/?probe=49baafbc65) | Oct 10, 2022 |
| HP            | 2000                        | Notebook    | [3341a26d0c](https://linux-hardware.org/?probe=3341a26d0c) | Oct 10, 2022 |
| ASUSTek       | GL503VD                     | Notebook    | [1405b367c2](https://linux-hardware.org/?probe=1405b367c2) | Oct 09, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [94ccd99c78](https://linux-hardware.org/?probe=94ccd99c78) | Oct 09, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [2a1088b211](https://linux-hardware.org/?probe=2a1088b211) | Oct 08, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [faef78b510](https://linux-hardware.org/?probe=faef78b510) | Oct 08, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [3427421197](https://linux-hardware.org/?probe=3427421197) | Oct 08, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [05dfea29df](https://linux-hardware.org/?probe=05dfea29df) | Oct 07, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [24471f06da](https://linux-hardware.org/?probe=24471f06da) | Oct 07, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [2d464da9c8](https://linux-hardware.org/?probe=2d464da9c8) | Oct 07, 2022 |
| HP            | ZBook 17 G6                 | Notebook    | [c215e9e17e](https://linux-hardware.org/?probe=c215e9e17e) | Oct 07, 2022 |
| Dell          | Precision 5530              | Notebook    | [db48ac269b](https://linux-hardware.org/?probe=db48ac269b) | Oct 07, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [cc955e89b7](https://linux-hardware.org/?probe=cc955e89b7) | Oct 07, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [9ccbc0ed3c](https://linux-hardware.org/?probe=9ccbc0ed3c) | Oct 07, 2022 |
| HP            | 1998                        | Desktop     | [f2b9957fdd](https://linux-hardware.org/?probe=f2b9957fdd) | Oct 06, 2022 |
| KELYX ARGE... | KL9120                      | Notebook    | [faa5f13391](https://linux-hardware.org/?probe=faa5f13391) | Oct 06, 2022 |
| Positivo      | N1250                       | Notebook    | [9845103c14](https://linux-hardware.org/?probe=9845103c14) | Oct 05, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [b161553abb](https://linux-hardware.org/?probe=b161553abb) | Oct 05, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [4f4352de45](https://linux-hardware.org/?probe=4f4352de45) | Oct 04, 2022 |
| HP            | 2000                        | Notebook    | [e6f8f7196d](https://linux-hardware.org/?probe=e6f8f7196d) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [3ec3f59233](https://linux-hardware.org/?probe=3ec3f59233) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [5ed7136249](https://linux-hardware.org/?probe=5ed7136249) | Oct 03, 2022 |
| HP            | 240 G7 Notebook PC          | Notebook    | [05b4e2117b](https://linux-hardware.org/?probe=05b4e2117b) | Oct 03, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [e0408b49e7](https://linux-hardware.org/?probe=e0408b49e7) | Oct 02, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [a4c73b484e](https://linux-hardware.org/?probe=a4c73b484e) | Oct 02, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [3cc1e139dc](https://linux-hardware.org/?probe=3cc1e139dc) | Oct 02, 2022 |
| Toshiba       | Satellite L850              | Notebook    | [0e57d064b0](https://linux-hardware.org/?probe=0e57d064b0) | Oct 02, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [05e921b4aa](https://linux-hardware.org/?probe=05e921b4aa) | Oct 02, 2022 |
| EVOO          | EG-LP10                     | Notebook    | [32c1a174d1](https://linux-hardware.org/?probe=32c1a174d1) | Oct 01, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [4d2e449699](https://linux-hardware.org/?probe=4d2e449699) | Sep 30, 2022 |
| ASRock        | X470 Master SLI             | Desktop     | [47c190b6e9](https://linux-hardware.org/?probe=47c190b6e9) | Sep 30, 2022 |
| ASUSTek       | Q504UAK                     | Convertible | [062910424d](https://linux-hardware.org/?probe=062910424d) | Sep 30, 2022 |
| Acer          | Aspire VX5-591G             | Notebook    | [b321f4561b](https://linux-hardware.org/?probe=b321f4561b) | Sep 29, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [0360123f76](https://linux-hardware.org/?probe=0360123f76) | Sep 29, 2022 |
| ASUSTek       | Q504UAK                     | Convertible | [a205e0ea70](https://linux-hardware.org/?probe=a205e0ea70) | Sep 29, 2022 |
| Gigabyte      | H270-Gaming 3               | Desktop     | [9426d21070](https://linux-hardware.org/?probe=9426d21070) | Sep 29, 2022 |
| Gigabyte      | H270-Gaming 3               | Desktop     | [830af9c53e](https://linux-hardware.org/?probe=830af9c53e) | Sep 29, 2022 |
| Lenovo        | G580 20157                  | Notebook    | [2b34d591ab](https://linux-hardware.org/?probe=2b34d591ab) | Sep 29, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [a423006d4c](https://linux-hardware.org/?probe=a423006d4c) | Sep 29, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [5dba6cf7fd](https://linux-hardware.org/?probe=5dba6cf7fd) | Sep 29, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [365d74f8e4](https://linux-hardware.org/?probe=365d74f8e4) | Sep 28, 2022 |
| Intel         | B75                         | Desktop     | [af5aef869c](https://linux-hardware.org/?probe=af5aef869c) | Sep 28, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [6d35107941](https://linux-hardware.org/?probe=6d35107941) | Sep 28, 2022 |
| Apple         | MacBookPro8,3               | Notebook    | [74927fc7d2](https://linux-hardware.org/?probe=74927fc7d2) | Sep 27, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [cfd24b9e0a](https://linux-hardware.org/?probe=cfd24b9e0a) | Sep 27, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [6bfc8d43ef](https://linux-hardware.org/?probe=6bfc8d43ef) | Sep 27, 2022 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | Notebook    | [65f896ddab](https://linux-hardware.org/?probe=65f896ddab) | Sep 27, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [d51c90a7a8](https://linux-hardware.org/?probe=d51c90a7a8) | Sep 27, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [f61a736922](https://linux-hardware.org/?probe=f61a736922) | Sep 26, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [1ecfe379e7](https://linux-hardware.org/?probe=1ecfe379e7) | Sep 26, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [dafae8d45b](https://linux-hardware.org/?probe=dafae8d45b) | Sep 26, 2022 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [d31088804f](https://linux-hardware.org/?probe=d31088804f) | Sep 24, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [015cd37f26](https://linux-hardware.org/?probe=015cd37f26) | Sep 24, 2022 |
| Dell          | Latitude 7275               | Tablet      | [49ee35636b](https://linux-hardware.org/?probe=49ee35636b) | Sep 24, 2022 |
| Dell          | 0G785M A00                  | Desktop     | [c461ec42d6](https://linux-hardware.org/?probe=c461ec42d6) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d72e6b3865](https://linux-hardware.org/?probe=d72e6b3865) | Sep 23, 2022 |
| Gateway       | NE56R                       | Notebook    | [f603edd045](https://linux-hardware.org/?probe=f603edd045) | Sep 23, 2022 |
| Toshiba       | TECRA A50-A                 | Notebook    | [6ef2538a5a](https://linux-hardware.org/?probe=6ef2538a5a) | Sep 23, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [605e97df5c](https://linux-hardware.org/?probe=605e97df5c) | Sep 22, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [94e6332c62](https://linux-hardware.org/?probe=94e6332c62) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [2e36489a4b](https://linux-hardware.org/?probe=2e36489a4b) | Sep 22, 2022 |
| Gigabyte      | EP45-UD3L                   | Desktop     | [71c630ea03](https://linux-hardware.org/?probe=71c630ea03) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [8705683c6f](https://linux-hardware.org/?probe=8705683c6f) | Sep 22, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [7299d75966](https://linux-hardware.org/?probe=7299d75966) | Sep 22, 2022 |
| HP            | 8594                        | Desktop     | [281774ad4a](https://linux-hardware.org/?probe=281774ad4a) | Sep 21, 2022 |
| Gigabyte      | EP45-UD3L                   | Desktop     | [2b90168b71](https://linux-hardware.org/?probe=2b90168b71) | Sep 21, 2022 |
| ASRock        | X470 Master SLI             | Desktop     | [3c8fefe578](https://linux-hardware.org/?probe=3c8fefe578) | Sep 20, 2022 |
| ASRock        | X470 Master SLI             | Desktop     | [1975320cad](https://linux-hardware.org/?probe=1975320cad) | Sep 20, 2022 |
| Alienware     | Area-51m R2 A00             | Notebook    | [0ebdec6dd0](https://linux-hardware.org/?probe=0ebdec6dd0) | Sep 20, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [ce162c52c0](https://linux-hardware.org/?probe=ce162c52c0) | Sep 19, 2022 |
| Dell          | 0G785M A00                  | Desktop     | [8b8c41b401](https://linux-hardware.org/?probe=8b8c41b401) | Sep 19, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [1f60a4d202](https://linux-hardware.org/?probe=1f60a4d202) | Sep 19, 2022 |
| Lenovo        | IdeaPadFlex 10 20324        | Notebook    | [4e7f3b7bac](https://linux-hardware.org/?probe=4e7f3b7bac) | Sep 19, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [cabf88c8be](https://linux-hardware.org/?probe=cabf88c8be) | Sep 19, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [854a0d4410](https://linux-hardware.org/?probe=854a0d4410) | Sep 19, 2022 |
| Dell          | Precision M6400             | Notebook    | [67924c5333](https://linux-hardware.org/?probe=67924c5333) | Sep 19, 2022 |
| Dell          | Precision M6400             | Notebook    | [27a55639e4](https://linux-hardware.org/?probe=27a55639e4) | Sep 19, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [e0e49d51d0](https://linux-hardware.org/?probe=e0e49d51d0) | Sep 18, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [7b95813c96](https://linux-hardware.org/?probe=7b95813c96) | Sep 18, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [812ea842dc](https://linux-hardware.org/?probe=812ea842dc) | Sep 18, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [004d0a2b9d](https://linux-hardware.org/?probe=004d0a2b9d) | Sep 17, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [b10823b50f](https://linux-hardware.org/?probe=b10823b50f) | Sep 17, 2022 |
| Biostar       | H410MH S2                   | Desktop     | [832dd81851](https://linux-hardware.org/?probe=832dd81851) | Sep 17, 2022 |
| Lenovo        | ThinkPad P1 20MD0020US      | Notebook    | [a701fed148](https://linux-hardware.org/?probe=a701fed148) | Sep 16, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [cce010fd53](https://linux-hardware.org/?probe=cce010fd53) | Sep 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [5ffc7d13ac](https://linux-hardware.org/?probe=5ffc7d13ac) | Sep 16, 2022 |
| Dell          | G5 5505                     | Notebook    | [25755e8605](https://linux-hardware.org/?probe=25755e8605) | Sep 16, 2022 |
| HP            | 15                          | Notebook    | [79aa0d618f](https://linux-hardware.org/?probe=79aa0d618f) | Sep 14, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [820c1e2ac6](https://linux-hardware.org/?probe=820c1e2ac6) | Sep 11, 2022 |
| Dell          | Precision 3510              | Notebook    | [4337a8e018](https://linux-hardware.org/?probe=4337a8e018) | Sep 11, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [d9e9ec9afa](https://linux-hardware.org/?probe=d9e9ec9afa) | Sep 09, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [1cdd7cda15](https://linux-hardware.org/?probe=1cdd7cda15) | Sep 09, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [6eae76b5d0](https://linux-hardware.org/?probe=6eae76b5d0) | Sep 01, 2022 |
| ASRock        | FM2A55M-HD+                 | Desktop     | [2f96c73efb](https://linux-hardware.org/?probe=2f96c73efb) | Sep 01, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [0ca693e2dd](https://linux-hardware.org/?probe=0ca693e2dd) | Aug 31, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [86fc2bf58f](https://linux-hardware.org/?probe=86fc2bf58f) | Aug 31, 2022 |
| Alienware     | 01NYPT A00                  | Desktop     | [cd95b79270](https://linux-hardware.org/?probe=cd95b79270) | Aug 29, 2022 |
| AZW           | SER                         | Mini pc     | [92460ed2a6](https://linux-hardware.org/?probe=92460ed2a6) | Aug 29, 2022 |
| ASUSTek       | TP500LA                     | Notebook    | [de395dddd8](https://linux-hardware.org/?probe=de395dddd8) | Aug 28, 2022 |
| ASRock        | B560 Steel Legend           | Desktop     | [c64907de8d](https://linux-hardware.org/?probe=c64907de8d) | Aug 27, 2022 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [37ae937f4d](https://linux-hardware.org/?probe=37ae937f4d) | Aug 26, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [663509c999](https://linux-hardware.org/?probe=663509c999) | Aug 24, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [2b7d1d59a1](https://linux-hardware.org/?probe=2b7d1d59a1) | Aug 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [928ce75df1](https://linux-hardware.org/?probe=928ce75df1) | Aug 24, 2022 |
| ASRock        | H61M-VG3                    | Desktop     | [a3cd7ba2c1](https://linux-hardware.org/?probe=a3cd7ba2c1) | Aug 22, 2022 |
| Dell          | G15 5511                    | Notebook    | [44fa9bf084](https://linux-hardware.org/?probe=44fa9bf084) | Aug 21, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [0b5044dacf](https://linux-hardware.org/?probe=0b5044dacf) | Aug 19, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [a2b6c2ae17](https://linux-hardware.org/?probe=a2b6c2ae17) | Aug 19, 2022 |
| Notebook      | P7xxDM2(-G)                 | Notebook    | [f074899985](https://linux-hardware.org/?probe=f074899985) | Aug 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [315da58d24](https://linux-hardware.org/?probe=315da58d24) | Aug 16, 2022 |
| ASRock        | X470 Master SLI             | Desktop     | [ce62975b20](https://linux-hardware.org/?probe=ce62975b20) | Aug 15, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [b2bbce2845](https://linux-hardware.org/?probe=b2bbce2845) | Aug 15, 2022 |
| ASRock        | Z97 Extreme6                | Desktop     | [31d7973a9d](https://linux-hardware.org/?probe=31d7973a9d) | Aug 14, 2022 |
| ASRock        | 760GM-HDV                   | Desktop     | [beabb7dd99](https://linux-hardware.org/?probe=beabb7dd99) | Aug 14, 2022 |
| Apple         | MacBookPro14,2              | Notebook    | [c66d476513](https://linux-hardware.org/?probe=c66d476513) | Aug 13, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [df2cc1a299](https://linux-hardware.org/?probe=df2cc1a299) | Aug 12, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [27cd96982f](https://linux-hardware.org/?probe=27cd96982f) | Aug 10, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [8f30392f49](https://linux-hardware.org/?probe=8f30392f49) | Aug 10, 2022 |
| HP            | 8054                        | Desktop     | [469b765fe0](https://linux-hardware.org/?probe=469b765fe0) | Aug 10, 2022 |
| ASUSTek       | G20AJ                       | Desktop     | [613f8a0c36](https://linux-hardware.org/?probe=613f8a0c36) | Aug 08, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [f65ba77de3](https://linux-hardware.org/?probe=f65ba77de3) | Aug 07, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [6beddf67f5](https://linux-hardware.org/?probe=6beddf67f5) | Aug 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [7a60eede9a](https://linux-hardware.org/?probe=7a60eede9a) | Aug 04, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [e142cf5c91](https://linux-hardware.org/?probe=e142cf5c91) | Aug 04, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [7c4355417f](https://linux-hardware.org/?probe=7c4355417f) | Aug 03, 2022 |
| ASUSTek       | Q504UAK                     | Convertible | [5f2025770d](https://linux-hardware.org/?probe=5f2025770d) | Aug 03, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [f034a02e69](https://linux-hardware.org/?probe=f034a02e69) | Aug 01, 2022 |
| Razer         | Blade                       | Notebook    | [cc3ce45956](https://linux-hardware.org/?probe=cc3ce45956) | Jul 31, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [3aa2fda09a](https://linux-hardware.org/?probe=3aa2fda09a) | Jul 26, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [bf2a870952](https://linux-hardware.org/?probe=bf2a870952) | Jul 23, 2022 |
| Dell          | 0J8H4R A01                  | Desktop     | [3d7d06475c](https://linux-hardware.org/?probe=3d7d06475c) | Jul 23, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [7d6b6d93d3](https://linux-hardware.org/?probe=7d6b6d93d3) | Jul 21, 2022 |
| eMachines     | EL1870                      | Desktop     | [58e76fb684](https://linux-hardware.org/?probe=58e76fb684) | Jul 19, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [c9683ea265](https://linux-hardware.org/?probe=c9683ea265) | Jul 19, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Nobara/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Nobara 37 | 263       | 35.35%  |
| Nobara 36 | 255       | 34.27%  |
| Nobara 38 | 226       | 30.38%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Nobara | 727       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Computers | Percent |
|-------------------------------|-----------|---------|
| 6.4.10-202.fsync.fc38.x86_64  | 50        | 6.3%    |
| 6.0.14-201.fsync.fc36.x86_64  | 38        | 4.79%   |
| 6.0.10-201.fc36.x86_64        | 37        | 4.66%   |
| 6.2.14-300.fsync.fc37.x86_64  | 33        | 4.16%   |
| 6.3.12-204.fsync.fc38.x86_64  | 27        | 3.4%    |
| 6.1.14-201.fsync.fc37.x86_64  | 25        | 3.15%   |
| 5.19.14-201.fsync.fc36.x86_64 | 25        | 3.15%   |
| 6.1.11-201.fsync.fc37.x86_64  | 19        | 2.39%   |
| 6.2.12-200.fsync.fc37.x86_64  | 18        | 2.27%   |
| 6.5.9-201.fsync.fc38.x86_64   | 17        | 2.14%   |
| 6.5.6-200.fsync.fc38.x86_64   | 17        | 2.14%   |
| 6.2.6-201.fsync.fc37.x86_64   | 17        | 2.14%   |
| 6.1.9-200.fsync.fc37.x86_64   | 17        | 2.14%   |
| 6.1.4-203.fsync.fc37.x86_64   | 17        | 2.14%   |
| 5.19.9-201.fsync.fc36.x86_64  | 16        | 2.02%   |
| 5.19.7-204.fsync.fc36.x86_64  | 16        | 2.02%   |
| 6.3.10-200.fsync.fc38.x86_64  | 14        | 1.76%   |
| 6.3.7-200.fsync.fc37.x86_64   | 13        | 1.64%   |
| 6.2.10-200.fsync.fc37.x86_64  | 13        | 1.64%   |
| 6.0.7-201.fsync.fc36.x86_64   | 12        | 1.51%   |
| 5.19.16-201.fsync.fc36.x86_64 | 12        | 1.51%   |
| 6.3.12-205.fsync.fc38.x86_64  | 11        | 1.39%   |
| 6.2.8-200.fsync.fc37.x86_64   | 11        | 1.39%   |
| 6.0.5-201.fsync.fc36.x86_64   | 11        | 1.39%   |
| 6.0.16-301.fsync.fc37.x86_64  | 11        | 1.39%   |
| 5.18.13-201.fsync.fc36.x86_64 | 11        | 1.39%   |
| 6.3.5-201.fsync.fc37.x86_64   | 10        | 1.26%   |
| 6.1.6-203.fsync.fc37.x86_64   | 10        | 1.26%   |
| 6.6.4-202.fsync.fc38.x86_64   | 9         | 1.13%   |
| 6.2.11-201.fsync.fc37.x86_64  | 9         | 1.13%   |
| 6.1.8-202.fsync.fc37.x86_64   | 9         | 1.13%   |
| 6.0.9-201.fc36.x86_64         | 9         | 1.13%   |
| 6.6.2-201.fsync.fc38.x86_64   | 8         | 1.01%   |
| 6.5.9-200.fsync.fc38.x86_64   | 8         | 1.01%   |
| 6.3.12-203.fsync.fc38.x86_64  | 8         | 1.01%   |
| 5.19.12-201.fsync.fc36.x86_64 | 8         | 1.01%   |
| 5.19.10-201.fsync.fc36.x86_64 | 8         | 1.01%   |
| 6.5.3-200.fsync.fc37.x86_64   | 7         | 0.88%   |
| 6.2.11-202.fsync.fc37.x86_64  | 7         | 0.88%   |
| 5.19.4-201.fsync.fc36.x86_64  | 7         | 0.88%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.4.10  | 58        | 7.32%   |
| 6.3.12  | 52        | 6.57%   |
| 6.0.14  | 38        | 4.8%    |
| 6.0.10  | 37        | 4.67%   |
| 6.2.14  | 34        | 4.29%   |
| 6.1.14  | 25        | 3.16%   |
| 5.19.14 | 25        | 3.16%   |
| 6.5.9   | 24        | 3.03%   |
| 6.3.10  | 20        | 2.53%   |
| 6.1.11  | 19        | 2.4%    |
| 6.5.6   | 18        | 2.27%   |
| 6.2.12  | 18        | 2.27%   |
| 5.19.7  | 18        | 2.27%   |
| 6.2.6   | 17        | 2.15%   |
| 6.1.9   | 17        | 2.15%   |
| 6.1.4   | 17        | 2.15%   |
| 6.2.11  | 16        | 2.02%   |
| 6.1.6   | 16        | 2.02%   |
| 6.0.7   | 16        | 2.02%   |
| 5.19.9  | 16        | 2.02%   |
| 6.5.5   | 15        | 1.89%   |
| 6.3.7   | 14        | 1.77%   |
| 6.2.10  | 13        | 1.64%   |
| 6.1.8   | 13        | 1.64%   |
| 6.0.9   | 13        | 1.64%   |
| 6.6.4   | 12        | 1.52%   |
| 6.5.3   | 12        | 1.52%   |
| 5.19.16 | 12        | 1.52%   |
| 6.3.5   | 11        | 1.39%   |
| 6.2.8   | 11        | 1.39%   |
| 6.0.5   | 11        | 1.39%   |
| 6.0.16  | 11        | 1.39%   |
| 5.18.13 | 11        | 1.39%   |
| 6.6.7   | 10        | 1.26%   |
| 6.6.2   | 8         | 1.01%   |
| 5.19.12 | 8         | 1.01%   |
| 5.19.10 | 8         | 1.01%   |
| 5.19.4  | 7         | 0.88%   |
| 5.18.16 | 7         | 0.88%   |
| 6.6.3   | 6         | 0.76%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.0     | 131       | 16.88%  |
| 5.19    | 114       | 14.69%  |
| 6.1     | 107       | 13.79%  |
| 6.2     | 106       | 13.66%  |
| 6.3     | 104       | 13.4%   |
| 6.5     | 76        | 9.79%   |
| 6.4     | 64        | 8.25%   |
| 6.6     | 40        | 5.15%   |
| 5.18    | 34        | 4.38%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 727       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 513       | 69.99%  |
| KDE5          | 206       | 28.1%   |
| Unknown       | 9         | 1.23%   |
| GNOME Classic | 2         | 0.27%   |
| X-Cinnamon    | 1         | 0.14%   |
| sway          | 1         | 0.14%   |
| Hyprland      | 1         | 0.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 579       | 78.24%  |
| X11     | 153       | 20.68%  |
| Unknown | 6         | 0.81%   |
| Tty     | 2         | 0.27%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 589       | 80.25%  |
| GDM     | 97        | 13.22%  |
| SDDM    | 44        | 5.99%   |
| LightDM | 4         | 0.54%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 382       | 52.33%  |
| en_GB   | 61        | 8.36%   |
| de_DE   | 49        | 6.71%   |
| es_ES   | 24        | 3.29%   |
| es_MX   | 21        | 2.88%   |
| en_CA   | 20        | 2.74%   |
| ru_RU   | 15        | 2.05%   |
| it_IT   | 15        | 2.05%   |
| pt_BR   | 14        | 1.92%   |
| pl_PL   | 14        | 1.92%   |
| fr_FR   | 14        | 1.92%   |
| es_AR   | 12        | 1.64%   |
| en_NZ   | 9         | 1.23%   |
| en_AU   | 7         | 0.96%   |
| de_AT   | 6         | 0.82%   |
| en_IN   | 5         | 0.68%   |
| Unknown | 5         | 0.68%   |
| pt_PT   | 4         | 0.55%   |
| nl_NL   | 4         | 0.55%   |
| es_CO   | 4         | 0.55%   |
| tr_TR   | 3         | 0.41%   |
| es_CL   | 3         | 0.41%   |
| en_PH   | 3         | 0.41%   |
| zh_TW   | 2         | 0.27%   |
| sv_SE   | 2         | 0.27%   |
| nl_BE   | 2         | 0.27%   |
| hu_HU   | 2         | 0.27%   |
| fi_FI   | 2         | 0.27%   |
| es_VE   | 2         | 0.27%   |
| da_DK   | 2         | 0.27%   |
| ar_SA   | 2         | 0.27%   |
| uk_UA   | 1         | 0.14%   |
| sk_SK   | 1         | 0.14%   |
| ro_RO   | 1         | 0.14%   |
| nb_NO   | 1         | 0.14%   |
| hr_HR   | 1         | 0.14%   |
| fr_BE   | 1         | 0.14%   |
| es_UY   | 1         | 0.14%   |
| es_US   | 1         | 0.14%   |
| es_GT   | 1         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 604       | 82.29%  |
| BIOS | 130       | 17.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 580       | 79.34%  |
| Ext4  | 149       | 20.38%  |
| Xfs   | 2         | 0.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 582       | 79.08%  |
| GPT     | 146       | 19.84%  |
| MBR     | 8         | 1.09%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 685       | 93.84%  |
| Yes       | 45        | 6.16%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 650       | 89.29%  |
| Yes       | 78        | 10.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 163       | 22.42%  |
| MSI                                  | 107       | 14.72%  |
| Lenovo                               | 81        | 11.14%  |
| Hewlett-Packard                      | 69        | 9.49%   |
| Gigabyte Technology                  | 64        | 8.8%    |
| Dell                                 | 52        | 7.15%   |
| ASRock                               | 52        | 7.15%   |
| Acer                                 | 26        | 3.58%   |
| Apple                                | 20        | 2.75%   |
| Intel                                | 8         | 1.1%    |
| Samsung Electronics                  | 6         | 0.83%   |
| Toshiba                              | 5         | 0.69%   |
| Alienware                            | 5         | 0.69%   |
| Microsoft                            | 4         | 0.55%   |
| AZW                                  | 4         | 0.55%   |
| Biostar                              | 3         | 0.41%   |
| Unknown                              | 3         | 0.41%   |
| Shenzhen Meigao Electronic Equipment | 2         | 0.28%   |
| Positivo                             | 2         | 0.28%   |
| Pegatron                             | 2         | 0.28%   |
| ONE-NETBOOK                          | 2         | 0.28%   |
| Notebook                             | 2         | 0.28%   |
| Infinix                              | 2         | 0.28%   |
| GPU Company                          | 2         | 0.28%   |
| Google                               | 2         | 0.28%   |
| Fujitsu                              | 2         | 0.28%   |
| Acidanthera                          | 2         | 0.28%   |
| ZOTAC                                | 1         | 0.14%   |
| Valve                                | 1         | 0.14%   |
| TUXEDO                               | 1         | 0.14%   |
| Timi                                 | 1         | 0.14%   |
| System76                             | 1         | 0.14%   |
| Supermicro                           | 1         | 0.14%   |
| Sony                                 | 1         | 0.14%   |
| Schenker                             | 1         | 0.14%   |
| Razer                                | 1         | 0.14%   |
| Protectli                            | 1         | 0.14%   |
| Packard Bell                         | 1         | 0.14%   |
| ONE-NETBOOK TECHNOLOGY               | 1         | 0.14%   |
| OEM                                  | 1         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| MSI MS-7B86                         | 9         | 1.24%   |
| MSI MS-7C37                         | 7         | 0.96%   |
| Unknown                             | 7         | 0.96%   |
| MSI MS-7C91                         | 6         | 0.83%   |
| MSI MS-7C02                         | 6         | 0.83%   |
| MSI MS-7B79                         | 6         | 0.83%   |
| MSI MS-7D25                         | 5         | 0.69%   |
| MSI MS-7C56                         | 5         | 0.69%   |
| ASUS All Series                     | 5         | 0.69%   |
| ASUS ROG STRIX B550-F GAMING        | 4         | 0.55%   |
| Lenovo Legion 5 15ARH05 82B5        | 3         | 0.41%   |
| Lenovo IdeaPad Y700-15ISK 80NV      | 3         | 0.41%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2 | 3         | 0.41%   |
| Lenovo IdeaPad C340-14API 81N6      | 3         | 0.41%   |
| HP Pavilion Gaming Laptop 15-ec1xxx | 3         | 0.41%   |
| Gigabyte X570 AORUS ELITE           | 3         | 0.41%   |
| Gigabyte B550 AORUS ELITE V2        | 3         | 0.41%   |
| Dell XPS 8700                       | 3         | 0.41%   |
| Dell Inspiron 15 3520               | 3         | 0.41%   |
| Dell G5 5505                        | 3         | 0.41%   |
| ASUS TUF Gaming X570-PLUS           | 3         | 0.41%   |
| ASUS TUF Gaming B550M-PLUS          | 3         | 0.41%   |
| ASUS ROG STRIX B650E-I GAMING WIFI  | 3         | 0.41%   |
| ASUS PRIME A320M-K                  | 3         | 0.41%   |
| Samsung 730QED                      | 2         | 0.28%   |
| MSI MS-7C87                         | 2         | 0.28%   |
| MSI MS-7B85                         | 2         | 0.28%   |
| MSI MS-7B84                         | 2         | 0.28%   |
| MSI MS-7B17                         | 2         | 0.28%   |
| MSI MS-7A34                         | 2         | 0.28%   |
| MSI MS-7977                         | 2         | 0.28%   |
| MSI MS-7817                         | 2         | 0.28%   |
| MSI MS-7721                         | 2         | 0.28%   |
| MSI MS-7693                         | 2         | 0.28%   |
| Lenovo Legion 5 15ARH05H 82B1       | 2         | 0.28%   |
| Lenovo Legion 5 15ACH6H 82JU        | 2         | 0.28%   |
| Lenovo IdeaPad 5 15ITL05 82FG       | 2         | 0.28%   |
| Intel X79                           | 2         | 0.28%   |
| HP ZBook 15u G3                     | 2         | 0.28%   |
| HP Pavilion Gaming Laptop 15-ec2xxx | 2         | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| ASUS ROG           | 49        | 6.74%   |
| ASUS TUF           | 26        | 3.58%   |
| Lenovo IdeaPad     | 24        | 3.3%    |
| ASUS PRIME         | 24        | 3.3%    |
| Lenovo ThinkPad    | 19        | 2.61%   |
| HP Pavilion        | 18        | 2.48%   |
| Lenovo Legion      | 15        | 2.06%   |
| ASUS VivoBook      | 12        | 1.65%   |
| Acer Aspire        | 12        | 1.65%   |
| Dell Inspiron      | 10        | 1.38%   |
| MSI MS-7B86        | 9         | 1.24%   |
| HP EliteBook       | 8         | 1.1%    |
| Gigabyte X570      | 8         | 1.1%    |
| Dell Latitude      | 8         | 1.1%    |
| Acer Nitro         | 8         | 1.1%    |
| MSI MS-7C37        | 7         | 0.96%   |
| Dell Precision     | 7         | 0.96%   |
| Dell OptiPlex      | 7         | 0.96%   |
| Unknown            | 7         | 0.96%   |
| MSI MS-7C91        | 6         | 0.83%   |
| MSI MS-7C02        | 6         | 0.83%   |
| MSI MS-7B79        | 6         | 0.83%   |
| HP ENVY            | 6         | 0.83%   |
| MSI MS-7D25        | 5         | 0.69%   |
| MSI MS-7C56        | 5         | 0.69%   |
| Lenovo Yoga        | 5         | 0.69%   |
| Lenovo ThinkCentre | 5         | 0.69%   |
| HP ZBook           | 5         | 0.69%   |
| Gigabyte B550      | 5         | 0.69%   |
| ASUS All           | 5         | 0.69%   |
| Toshiba Satellite  | 4         | 0.55%   |
| Microsoft Surface  | 4         | 0.55%   |
| HP Laptop          | 4         | 0.55%   |
| HP EliteDesk       | 4         | 0.55%   |
| Gigabyte B550M     | 4         | 0.55%   |
| Dell XPS           | 4         | 0.55%   |
| Dell Vostro        | 4         | 0.55%   |
| ASUS ASUS          | 4         | 0.55%   |
| Apple MacBookPro8  | 4         | 0.55%   |
| Lenovo IdeaPadFlex | 3         | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 102       | 14.03%  |
| 2021 | 99        | 13.62%  |
| 2019 | 93        | 12.79%  |
| 2022 | 81        | 11.14%  |
| 2018 | 81        | 11.14%  |
| 2013 | 40        | 5.5%    |
| 2012 | 37        | 5.09%   |
| 2014 | 36        | 4.95%   |
| 2017 | 34        | 4.68%   |
| 2016 | 34        | 4.68%   |
| 2015 | 25        | 3.44%   |
| 2023 | 22        | 3.03%   |
| 2011 | 18        | 2.48%   |
| 2010 | 9         | 1.24%   |
| 2009 | 8         | 1.1%    |
| 2008 | 6         | 0.83%   |
| 2007 | 2         | 0.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 373       | 51.31%  |
| Notebook    | 300       | 41.27%  |
| Convertible | 23        | 3.16%   |
| Mini pc     | 12        | 1.65%   |
| All in one  | 9         | 1.24%   |
| Tablet      | 8         | 1.1%    |
| Other       | 1         | 0.14%   |
| Server      | 1         | 0.14%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 727       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 724       | 99.59%  |
| Yes  | 3         | 0.41%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 213       | 29.1%   |
| 32.01-64.0      | 161       | 21.99%  |
| 8.01-16.0       | 118       | 16.12%  |
| 4.01-8.0        | 112       | 15.3%   |
| 3.01-4.0        | 46        | 6.28%   |
| 24.01-32.0      | 44        | 6.01%   |
| 64.01-256.0     | 32        | 4.37%   |
| 1.01-2.0        | 3         | 0.41%   |
| 2.01-3.0        | 2         | 0.27%   |
| More than 256.0 | 1         | 0.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 342       | 44.42%  |
| 3.01-4.0   | 167       | 21.69%  |
| 2.01-3.0   | 142       | 18.44%  |
| 8.01-16.0  | 77        | 10%     |
| 1.01-2.0   | 29        | 3.77%   |
| 16.01-24.0 | 9         | 1.17%   |
| 24.01-32.0 | 3         | 0.39%   |
| 32.01-64.0 | 1         | 0.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 329       | 44.4%   |
| 2      | 212       | 28.61%  |
| 3      | 99        | 13.36%  |
| 4      | 48        | 6.48%   |
| 5      | 29        | 3.91%   |
| 6      | 11        | 1.48%   |
| 7      | 5         | 0.67%   |
| 8      | 4         | 0.54%   |
| 10     | 2         | 0.27%   |
| 9      | 2         | 0.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 584       | 79.89%  |
| Yes       | 147       | 20.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 640       | 87.79%  |
| No        | 89        | 12.21%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 574       | 78.52%  |
| No        | 157       | 21.48%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 516       | 70.78%  |
| No        | 213       | 29.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 219       | 30.12%  |
| Germany      | 66        | 9.08%   |
| UK           | 38        | 5.23%   |
| Canada       | 28        | 3.85%   |
| Spain        | 25        | 3.44%   |
| Italy        | 21        | 2.89%   |
| France       | 21        | 2.89%   |
| Brazil       | 21        | 2.89%   |
| Poland       | 20        | 2.75%   |
| Russia       | 19        | 2.61%   |
| Mexico       | 19        | 2.61%   |
| Argentina    | 19        | 2.61%   |
| Netherlands  | 13        | 1.79%   |
| Sweden       | 12        | 1.65%   |
| Australia    | 12        | 1.65%   |
| India        | 10        | 1.38%   |
| New Zealand  | 9         | 1.24%   |
| Austria      | 8         | 1.1%    |
| Portugal     | 7         | 0.96%   |
| Philippines  | 7         | 0.96%   |
| Indonesia    | 7         | 0.96%   |
| Chile        | 7         | 0.96%   |
| Turkey       | 6         | 0.83%   |
| Finland      | 6         | 0.83%   |
| Colombia     | 6         | 0.83%   |
| Venezuela    | 5         | 0.69%   |
| Saudi Arabia | 5         | 0.69%   |
| Romania      | 5         | 0.69%   |
| Hungary      | 5         | 0.69%   |
| Belgium      | 5         | 0.69%   |
| Estonia      | 4         | 0.55%   |
| Czechia      | 4         | 0.55%   |
| Vietnam      | 3         | 0.41%   |
| Serbia       | 3         | 0.41%   |
| Norway       | 3         | 0.41%   |
| Malaysia     | 3         | 0.41%   |
| Croatia      | 3         | 0.41%   |
| Ukraine      | 2         | 0.28%   |
| Sri Lanka    | 2         | 0.28%   |
| South Africa | 2         | 0.28%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Buenos Aires  | 6         | 0.79%   |
| Berlin        | 6         | 0.79%   |
| Stockholm     | 5         | 0.66%   |
| Melbourne     | 5         | 0.66%   |
| Guadalajara   | 5         | 0.66%   |
| Auckland      | 5         | 0.66%   |
| Atlanta       | 5         | 0.66%   |
| San Francisco | 4         | 0.53%   |
| Milano        | 4         | 0.53%   |
| Los Angeles   | 4         | 0.53%   |
| Wroclaw       | 3         | 0.4%    |
| Wellington    | 3         | 0.4%    |
| Warsaw        | 3         | 0.4%    |
| Vienna        | 3         | 0.4%    |
| Toronto       | 3         | 0.4%    |
| Sydney        | 3         | 0.4%    |
| Seattle       | 3         | 0.4%    |
| Sao Paulo     | 3         | 0.4%    |
| San José     | 3         | 0.4%    |
| Rotterdam     | 3         | 0.4%    |
| Rome          | 3         | 0.4%    |
| Poznan        | 3         | 0.4%    |
| Philadelphia  | 3         | 0.4%    |
| Perm          | 3         | 0.4%    |
| Nuremberg     | 3         | 0.4%    |
| Milan         | 3         | 0.4%    |
| Madrid        | 3         | 0.4%    |
| Kuala Lumpur  | 3         | 0.4%    |
| Denver        | 3         | 0.4%    |
| Cologne       | 3         | 0.4%    |
| Cardiff       | 3         | 0.4%    |
| Boynton Beach | 3         | 0.4%    |
| Amsterdam     | 3         | 0.4%    |
| Wasilla       | 2         | 0.26%   |
| Vilnius       | 2         | 0.26%   |
| Villa Nueva   | 2         | 0.26%   |
| Victoria      | 2         | 0.26%   |
| Valladolid    | 2         | 0.26%   |
| Tucson        | 2         | 0.26%   |
| Toulouse      | 2         | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 237       | 374    | 18.02%  |
| WDC                          | 150       | 212    | 11.41%  |
| Seagate                      | 130       | 178    | 9.89%   |
| Sandisk                      | 96        | 115    | 7.3%    |
| Kingston                     | 83        | 92     | 6.31%   |
| Toshiba                      | 71        | 85     | 5.4%    |
| Crucial                      | 70        | 95     | 5.32%   |
| Intel                        | 41        | 52     | 3.12%   |
| Micron/Crucial Technology    | 40        | 49     | 3.04%   |
| SK hynix                     | 37        | 39     | 2.81%   |
| Phison Electronics           | 36        | 42     | 2.74%   |
| Micron Technology            | 26        | 28     | 1.98%   |
| Unknown                      | 22        | 31     | 1.67%   |
| Kingston Technology Company  | 16        | 20     | 1.22%   |
| Hitachi                      | 16        | 22     | 1.22%   |
| KIOXIA                       | 15        | 17     | 1.14%   |
| PNY                          | 14        | 22     | 1.06%   |
| HGST                         | 13        | 16     | 0.99%   |
| China                        | 12        | 12     | 0.91%   |
| A-DATA Technology            | 12        | 12     | 0.91%   |
| Apple                        | 11        | 12     | 0.84%   |
| Team                         | 9         | 9      | 0.68%   |
| SPCC                         | 9         | 11     | 0.68%   |
| Silicon Motion               | 9         | 9      | 0.68%   |
| Realtek Semiconductor        | 9         | 11     | 0.68%   |
| ADATA Technology             | 9         | 10     | 0.68%   |
| Phison                       | 8         | 9      | 0.61%   |
| Intenso                      | 6         | 7      | 0.46%   |
| MAXIO Technology (Hangzhou)  | 5         | 5      | 0.38%   |
| Lexar                        | 4         | 5      | 0.3%    |
| Corsair                      | 4         | 4      | 0.3%    |
| Unknown                      | 4         | 5      | 0.3%    |
| Verbatim                     | 3         | 3      | 0.23%   |
| Shenzhen Longsys Electronics | 3         | 3      | 0.23%   |
| OCZ                          | 3         | 3      | 0.23%   |
| KIOXIA-EXCERIA               | 3         | 4      | 0.23%   |
| HS-SSD-C100                  | 3         | 3      | 0.23%   |
| Apacer                       | 3         | 3      | 0.23%   |
| Wibtek                       | 2         | 2      | 0.15%   |
| USB3.0                       | 2         | 2      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB   | 55        | 3.68%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                   | 27        | 1.81%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB    | 26        | 1.74%   |
| Kingston SA400S37240G 240GB SSD                       | 26        | 1.74%   |
| Phison E12 NVMe Controller 512GB                      | 19        | 1.27%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                  | 16        | 1.07%   |
| Samsung SSD 860 EVO 500GB                             | 14        | 0.94%   |
| Intel SSD 660P Series 512GB                           | 14        | 0.94%   |
| Samsung SSD 860 EVO 1TB                               | 13        | 0.87%   |
| Samsung SSD 850 EVO 500GB                             | 13        | 0.87%   |
| Crucial CT1000BX500SSD1 1TB                           | 13        | 0.87%   |
| Seagate ST2000DM008-2FR102 2TB                        | 12        | 0.8%    |
| Samsung SSD 980 1TB                                   | 12        | 0.8%    |
| Crucial CT1000MX500SSD1 1TB                           | 12        | 0.8%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB   | 11        | 0.74%   |
| Samsung SSD 850 EVO 250GB                             | 10        | 0.67%   |
| Phison PS5013 E13 NVMe Controller 512GB               | 9         | 0.6%    |
| Toshiba MQ04ABF100 1TB                                | 8         | 0.54%   |
| Toshiba DT01ACA100 1TB                                | 8         | 0.54%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB      | 8         | 0.54%   |
| Kingston SA400S37480G 480GB SSD                       | 8         | 0.54%   |
| Crucial CT240BX500SSD1 240GB                          | 8         | 0.54%   |
| Unknown MMC Card  64GB                                | 7         | 0.47%   |
| Toshiba DT01ACA200 2TB                                | 7         | 0.47%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 7         | 0.47%   |
| Crucial CT2000MX500SSD1 2TB                           | 7         | 0.47%   |
| WDC WD20EZRZ-00Z5HB0 2TB                              | 6         | 0.4%    |
| WDC WD10EZEX-08WN4A0 1TB                              | 6         | 0.4%    |
| WDC WD10EZEX-00BN5A0 1TB                              | 6         | 0.4%    |
| Toshiba MQ01ABD100 1TB                                | 6         | 0.4%    |
| Seagate ST2000DM001-1ER164 2TB                        | 6         | 0.4%    |
| Samsung SSD 870 EVO 1TB                               | 6         | 0.4%    |
| Samsung SSD 860 EVO 250GB                             | 6         | 0.4%    |
| Samsung NVMe SSD Controller SM951/PM951 128GB         | 6         | 0.4%    |
| Kingston SA400S37120G 120GB SSD                       | 6         | 0.4%    |
| Intel SSDPEKNU512GZ 512GB                             | 6         | 0.4%    |
| Crucial CT500MX500SSD1 500GB                          | 6         | 0.4%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 5         | 0.33%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                        | 5         | 0.33%   |
| WDC WD10JPCX-24UE4T0 1TB                              | 5         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 128       | 173    | 34.69%  |
| WDC                 | 117       | 162    | 31.71%  |
| Toshiba             | 59        | 70     | 15.99%  |
| Samsung Electronics | 16        | 27     | 4.34%   |
| Hitachi             | 16        | 22     | 4.34%   |
| HGST                | 13        | 16     | 3.52%   |
| Apple               | 7         | 7      | 1.9%    |
| Unknown             | 2         | 2      | 0.54%   |
| Maxtor              | 2         | 2      | 0.54%   |
| ASMT                | 2         | 3      | 0.54%   |
| USB3.0              | 1         | 1      | 0.27%   |
| TO Exter            | 1         | 1      | 0.27%   |
| SSK                 | 1         | 1      | 0.27%   |
| SABRENT             | 1         | 2      | 0.27%   |
| HGST HTS            | 1         | 1      | 0.27%   |
| Hewlett-Packard     | 1         | 1      | 0.27%   |
| Fujitsu             | 1         | 1      | 0.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 115       | 152    | 25.05%  |
| Crucial             | 68        | 93     | 14.81%  |
| Kingston            | 60        | 67     | 13.07%  |
| WDC                 | 35        | 41     | 7.63%   |
| SanDisk             | 27        | 31     | 5.88%   |
| PNY                 | 14        | 22     | 3.05%   |
| China               | 12        | 12     | 2.61%   |
| A-DATA Technology   | 12        | 12     | 2.61%   |
| SPCC                | 9         | 11     | 1.96%   |
| Team                | 8         | 8      | 1.74%   |
| Intel               | 8         | 9      | 1.74%   |
| Micron Technology   | 7         | 8      | 1.53%   |
| Toshiba             | 6         | 7      | 1.31%   |
| SK hynix            | 6         | 6      | 1.31%   |
| Intenso             | 5         | 5      | 1.09%   |
| OCZ                 | 3         | 3      | 0.65%   |
| Lexar               | 3         | 4      | 0.65%   |
| KIOXIA-EXCERIA      | 3         | 4      | 0.65%   |
| Corsair             | 3         | 3      | 0.65%   |
| Apacer              | 3         | 3      | 0.65%   |
| Wibtek              | 2         | 2      | 0.44%   |
| Verbatim            | 2         | 2      | 0.44%   |
| Transcend           | 2         | 2      | 0.44%   |
| Seagate             | 2         | 2      | 0.44%   |
| Plextor             | 2         | 2      | 0.44%   |
| Patriot             | 2         | 2      | 0.44%   |
| Mushkin             | 2         | 2      | 0.44%   |
| LITEON              | 2         | 2      | 0.44%   |
| KingFast            | 2         | 2      | 0.44%   |
| Fanxiang            | 2         | 2      | 0.44%   |
| Drevo               | 2         | 2      | 0.44%   |
| Apple               | 2         | 2      | 0.44%   |
| XSTAR               | 1         | 1      | 0.22%   |
| WDC WDS             | 1         | 1      | 0.22%   |
| V-GeN               | 1         | 1      | 0.22%   |
| USB3.0              | 1         | 1      | 0.22%   |
| SuperSSpeed         | 1         | 1      | 0.22%   |
| SSSTC               | 1         | 1      | 0.22%   |
| SD                  | 1         | 1      | 0.22%   |
| SCY                 | 1         | 1      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 430       | 620    | 37.65%  |
| SSD     | 372       | 554    | 32.57%  |
| HDD     | 305       | 492    | 26.71%  |
| Unknown | 21        | 25     | 1.84%   |
| MMC     | 14        | 16     | 1.23%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 491       | 1006   | 49.95%  |
| NVMe | 427       | 615    | 43.44%  |
| SAS  | 51        | 70     | 5.19%   |
| MMC  | 14        | 16     | 1.42%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 324       | 475    | 43.78%  |
| 0.51-1.0   | 248       | 335    | 33.51%  |
| 1.01-2.0   | 102       | 149    | 13.78%  |
| 3.01-4.0   | 25        | 32     | 3.38%   |
| 4.01-10.0  | 23        | 33     | 3.11%   |
| 2.01-3.0   | 14        | 17     | 1.89%   |
| 10.01-20.0 | 4         | 5      | 0.54%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 160       | 21.42%  |
| 251-500        | 137       | 18.34%  |
| 1001-2000      | 135       | 18.07%  |
| 101-250        | 112       | 14.99%  |
| More than 3000 | 94        | 12.58%  |
| 2001-3000      | 45        | 6.02%   |
| Unknown        | 23        | 3.08%   |
| 21-50          | 20        | 2.68%   |
| 51-100         | 16        | 2.14%   |
| 1-20           | 5         | 0.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 184       | 23.9%   |
| 1-20           | 132       | 17.14%  |
| 101-250        | 116       | 15.06%  |
| 251-500        | 82        | 10.65%  |
| 51-100         | 80        | 10.39%  |
| 501-1000       | 66        | 8.57%   |
| 1001-2000      | 45        | 5.84%   |
| More than 3000 | 24        | 3.12%   |
| Unknown        | 23        | 2.99%   |
| 2001-3000      | 18        | 2.34%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-75ZAT0 500GB                    | 2         | 2      | 11.11%  |
| WDC WD30EZRX-00DC0B0 3TB                       | 1         | 1      | 5.56%   |
| WDC WD20EURS-63S48Y0 2TB                       | 1         | 1      | 5.56%   |
| WDC WD10EZEX-08M2NA0 1TB                       | 1         | 1      | 5.56%   |
| WDC WD10EACS-00D6B0 1TB                        | 1         | 1      | 5.56%   |
| SK hynix HFS128G39TND-N210A 128GB SSD          | 1         | 1      | 5.56%   |
| Seagate ST500DM002-1BD142 500GB                | 1         | 1      | 5.56%   |
| Seagate ST2000DX002-2DV164 2TB                 | 1         | 1      | 5.56%   |
| Seagate ST1000DM003-9YN162 1TB                 | 1         | 1      | 5.56%   |
| Samsung Electronics SSD 980 1TB                | 1         | 1      | 5.56%   |
| Samsung Electronics SSD 970 EVO 1TB            | 1         | 1      | 5.56%   |
| Samsung Electronics HD161GJ 160GB              | 1         | 1      | 5.56%   |
| Ramsta SSD S800 240GB                          | 1         | 1      | 5.56%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD | 1         | 1      | 5.56%   |
| Hitachi HTS54323 320GB                         | 1         | 1      | 5.56%   |
| HGST HTS721010A9E630 1TB                       | 1         | 1      | 5.56%   |
| HGST HTS545050A7E380 500GB                     | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 6      | 33.33%  |
| Seagate             | 3         | 3      | 16.67%  |
| Samsung Electronics | 3         | 3      | 16.67%  |
| HGST                | 2         | 2      | 11.11%  |
| SK hynix            | 1         | 1      | 5.56%   |
| Ramsta              | 1         | 1      | 5.56%   |
| Micron Technology   | 1         | 1      | 5.56%   |
| Hitachi             | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 6      | 46.15%  |
| Seagate             | 3         | 3      | 23.08%  |
| HGST                | 2         | 2      | 15.38%  |
| Samsung Electronics | 1         | 1      | 7.69%   |
| Hitachi             | 1         | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 13     | 72.22%  |
| SSD  | 3         | 3      | 16.67%  |
| NVMe | 2         | 2      | 11.11%  |

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
| Detected | 598       | 1394   | 78.37%  |
| Works    | 148       | 294    | 19.4%   |
| Malfunc  | 16        | 18     | 2.1%    |
| Limited  | 1         | 1      | 0.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 370       | 31.9%   |
| AMD                            | 269       | 23.19%  |
| Samsung Electronics            | 145       | 12.5%   |
| SanDisk                        | 78        | 6.72%   |
| Phison Electronics             | 44        | 3.79%   |
| Micron/Crucial Technology      | 42        | 3.62%   |
| Kingston Technology Company    | 41        | 3.53%   |
| ASMedia Technology             | 32        | 2.76%   |
| SK hynix                       | 31        | 2.67%   |
| Micron Technology              | 19        | 1.64%   |
| KIOXIA                         | 15        | 1.29%   |
| Realtek Semiconductor          | 10        | 0.86%   |
| Silicon Motion                 | 9         | 0.78%   |
| ADATA Technology               | 9         | 0.78%   |
| Nvidia                         | 8         | 0.69%   |
| Toshiba America Info Systems   | 6         | 0.52%   |
| MAXIO Technology (Hangzhou)    | 5         | 0.43%   |
| Marvell Technology Group       | 5         | 0.43%   |
| Solidigm                       | 3         | 0.26%   |
| Shenzhen Longsys Electronics   | 3         | 0.26%   |
| JMicron Technology             | 3         | 0.26%   |
| Union Memory (Shenzhen)        | 2         | 0.17%   |
| Broadcom / LSI                 | 2         | 0.17%   |
| Apple                          | 2         | 0.17%   |
| Solid State Storage Technology | 1         | 0.09%   |
| Silicon Image                  | 1         | 0.09%   |
| Seagate Technology             | 1         | 0.09%   |
| Netac Technology               | 1         | 0.09%   |
| LSI Logic / Symbios Logic      | 1         | 0.09%   |
| Lenovo                         | 1         | 0.09%   |
| Biwin Storage Technology       | 1         | 0.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 186       | 14.45%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 67        | 5.21%   |
| AMD 400 Series Chipset SATA Controller                                         | 55        | 4.27%   |
| AMD 500 Series Chipset SATA Controller                                         | 45        | 3.5%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 32        | 2.49%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 32        | 2.49%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 31        | 2.41%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 31        | 2.41%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 27        | 2.1%    |
| Intel Volume Management Device NVMe RAID Controller                            | 23        | 1.79%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 21        | 1.63%   |
| Phison E12 NVMe Controller                                                     | 20        | 1.55%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 19        | 1.48%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 17        | 1.32%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 17        | 1.32%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 17        | 1.32%   |
| Intel SSD 660P Series                                                          | 16        | 1.24%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 16        | 1.24%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 16        | 1.24%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 16        | 1.24%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 15        | 1.17%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 14        | 1.09%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 13        | 1.01%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 13        | 1.01%   |
| Intel Tiger Lake-LP SATA Controller                                            | 13        | 1.01%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 13        | 1.01%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 13        | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 13        | 1.01%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 12        | 0.93%   |
| Intel SATA Controller [RAID mode]                                              | 12        | 0.93%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 12        | 0.93%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 12        | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 12        | 0.93%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 10        | 0.78%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 10        | 0.78%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 10        | 0.78%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 9         | 0.7%    |
| Kingston Company NV2 NVMe SSD SM2267XT                                         | 9         | 0.7%    |
| Intel SSD 670p Series [Keystone Harbor]                                        | 9         | 0.7%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 9         | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 572       | 52.57%  |
| NVMe | 427       | 39.25%  |
| RAID | 57        | 5.24%   |
| IDE  | 28        | 2.57%   |
| SAS  | 4         | 0.37%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 406       | 55.85%  |
| AMD    | 321       | 44.15%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 18        | 2.46%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 14        | 1.92%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 14        | 1.92%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 13        | 1.78%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 11        | 1.5%    |
| AMD Ryzen 7 5800X 8-Core Processor            | 10        | 1.37%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 9         | 1.23%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 9         | 1.23%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 8         | 1.09%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 8         | 1.09%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 8         | 1.09%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 7         | 0.96%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 7         | 0.96%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 7         | 0.96%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 6         | 0.82%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 6         | 0.82%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 6         | 0.82%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 0.82%   |
| AMD Ryzen 9 7950X 16-Core Processor           | 6         | 0.82%   |
| AMD Ryzen 7 7800X3D 8-Core Processor          | 6         | 0.82%   |
| AMD Ryzen 7 5700X 8-Core Processor            | 6         | 0.82%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 6         | 0.82%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 6         | 0.82%   |
| AMD Ryzen 5 7600X 6-Core Processor            | 6         | 0.82%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 6         | 0.82%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 6         | 0.82%   |
| AMD FX-8350 Eight-Core Processor              | 6         | 0.82%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 5         | 0.68%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 5         | 0.68%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 5         | 0.68%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 0.68%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 5         | 0.68%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 5         | 0.68%   |
| AMD Ryzen 9 6900HX with Radeon Graphics       | 5         | 0.68%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 5         | 0.68%   |
| AMD Ryzen 7 5800X3D 8-Core Processor          | 5         | 0.68%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 0.68%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 5         | 0.68%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 5         | 0.68%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 4         | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 122       | 16.71%  |
| Intel Core i7           | 119       | 16.3%   |
| AMD Ryzen 5             | 116       | 15.89%  |
| AMD Ryzen 7             | 98        | 13.42%  |
| Other                   | 81        | 11.1%   |
| AMD Ryzen 9             | 49        | 6.71%   |
| Intel Core i3           | 31        | 4.25%   |
| Intel Xeon              | 14        | 1.92%   |
| Intel Celeron           | 14        | 1.92%   |
| AMD Ryzen 3             | 13        | 1.78%   |
| AMD FX                  | 13        | 1.78%   |
| Intel Core i9           | 7         | 0.96%   |
| Intel Core 2 Duo        | 7         | 0.96%   |
| Intel Pentium           | 6         | 0.82%   |
| Intel Atom              | 4         | 0.55%   |
| AMD A6                  | 4         | 0.55%   |
| AMD A4                  | 4         | 0.55%   |
| AMD A10                 | 4         | 0.55%   |
| AMD Phenom II X6        | 3         | 0.41%   |
| Intel Pentium Dual-Core | 2         | 0.27%   |
| AMD Ryzen Threadripper  | 2         | 0.27%   |
| Intel Core m7           | 1         | 0.14%   |
| Intel Core 2 Quad       | 1         | 0.14%   |
| Intel Core 2 Extreme    | 1         | 0.14%   |
| AMD Turion 64 X2 Mobile | 1         | 0.14%   |
| AMD Ryzen 7 PRO         | 1         | 0.14%   |
| AMD Ryzen 5 PRO         | 1         | 0.14%   |
| AMD Ryzen 3 PRO         | 1         | 0.14%   |
| AMD PRO A10             | 1         | 0.14%   |
| AMD Phenom II X4        | 1         | 0.14%   |
| AMD Phenom II           | 1         | 0.14%   |
| AMD Phenom              | 1         | 0.14%   |
| AMD G                   | 1         | 0.14%   |
| AMD E                   | 1         | 0.14%   |
| AMD Athlon X4           | 1         | 0.14%   |
| AMD Athlon II X2        | 1         | 0.14%   |
| AMD Athlon Dual Core    | 1         | 0.14%   |
| AMD A8                  | 1         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 217       | 29.81%  |
| 6      | 165       | 22.66%  |
| 8      | 130       | 17.86%  |
| 2      | 129       | 17.72%  |
| 12     | 31        | 4.26%   |
| 16     | 22        | 3.02%   |
| 14     | 12        | 1.65%   |
| 10     | 12        | 1.65%   |
| 3      | 4         | 0.55%   |
| 1      | 4         | 0.55%   |
| 24     | 2         | 0.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 725       | 99.72%  |
| 2      | 2         | 0.28%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 610       | 83.56%  |
| 1      | 120       | 16.44%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 727       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 216       | 29.11%  |
| 0x08701021 | 35        | 4.72%   |
| 0x0a50000c | 27        | 3.64%   |
| 0x0a601203 | 23        | 3.1%    |
| 0x08108109 | 21        | 2.83%   |
| 0x306c3    | 20        | 2.7%    |
| 0x306a9    | 20        | 2.7%    |
| 0x0a50000d | 19        | 2.56%   |
| 0x0800820d | 19        | 2.56%   |
| 0x0a201016 | 17        | 2.29%   |
| 0x206a7    | 16        | 2.16%   |
| 0x906ea    | 15        | 2.02%   |
| 0x906e9    | 13        | 1.75%   |
| 0x40651    | 13        | 1.75%   |
| 0x0a20120a | 13        | 1.75%   |
| 0xa0652    | 12        | 1.62%   |
| 0x08600106 | 10        | 1.35%   |
| 0x506e3    | 9         | 1.21%   |
| 0x0a404102 | 9         | 1.21%   |
| 0x08608103 | 9         | 1.21%   |
| 0x906a3    | 8         | 1.08%   |
| 0x806c1    | 8         | 1.08%   |
| 0x06000822 | 8         | 1.08%   |
| 0x806e9    | 7         | 0.94%   |
| 0x08701030 | 7         | 0.94%   |
| 0x08600104 | 7         | 0.94%   |
| 0xa0655    | 6         | 0.81%   |
| 0x90672    | 6         | 0.81%   |
| 0x0a201205 | 6         | 0.81%   |
| 0x0a201204 | 6         | 0.81%   |
| 0x906ed    | 5         | 0.67%   |
| 0x806d1    | 5         | 0.67%   |
| 0x406e3    | 5         | 0.67%   |
| 0x08001138 | 5         | 0.67%   |
| 0xa0653    | 4         | 0.54%   |
| 0x906ec    | 4         | 0.54%   |
| 0x206d7    | 4         | 0.54%   |
| 0x1067a    | 4         | 0.54%   |
| 0x0a201025 | 4         | 0.54%   |
| 0x08701013 | 4         | 0.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Zen 3            | 102       | 14.01%  |
| KabyLake         | 95        | 13.05%  |
| Zen 2            | 66        | 9.07%   |
| Haswell          | 61        | 8.38%   |
| Unknown          | 58        | 7.97%   |
| Zen+             | 48        | 6.59%   |
| Alderlake Hybrid | 39        | 5.36%   |
| Skylake          | 34        | 4.67%   |
| CometLake        | 32        | 4.4%    |
| IvyBridge        | 31        | 4.26%   |
| SandyBridge      | 28        | 3.85%   |
| TigerLake        | 22        | 3.02%   |
| Icelake          | 19        | 2.61%   |
| Piledriver       | 15        | 2.06%   |
| Zen              | 14        | 1.92%   |
| Penryn           | 10        | 1.37%   |
| Silvermont       | 9         | 1.24%   |
| Broadwell        | 8         | 1.1%    |
| K10              | 7         | 0.96%   |
| Goldmont plus    | 5         | 0.69%   |
| Excavator        | 5         | 0.69%   |
| Steamroller      | 4         | 0.55%   |
| Westmere         | 3         | 0.41%   |
| Puma             | 2         | 0.27%   |
| K8 Hammer        | 2         | 0.27%   |
| Core             | 2         | 0.27%   |
| Bobcat           | 2         | 0.27%   |
| Nehalem          | 1         | 0.14%   |
| Jaguar           | 1         | 0.14%   |
| Goldmont         | 1         | 0.14%   |
| Bulldozer        | 1         | 0.14%   |
| Bonnell          | 1         | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| AMD    | 324       | 35.29%  |
| Nvidia | 321       | 34.97%  |
| Intel  | 273       | 29.74%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 40        | 4.18%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 33        | 3.45%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 29        | 3.03%   |
| AMD Raphael                                                                 | 24        | 2.51%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 23        | 2.4%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 22        | 2.3%    |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 21        | 2.19%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 20        | 2.09%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 17        | 1.78%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 17        | 1.78%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 15        | 1.57%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 15        | 1.57%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 15        | 1.57%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 15        | 1.57%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 15        | 1.57%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 14        | 1.46%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 13        | 1.36%   |
| AMD Rembrandt [Radeon 680M]                                                 | 12        | 1.25%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX]                                    | 12        | 1.25%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 11        | 1.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 11        | 1.15%   |
| Intel HD Graphics 620                                                       | 11        | 1.15%   |
| Intel HD Graphics 530                                                       | 11        | 1.15%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 10        | 1.04%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 9         | 0.94%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 9         | 0.94%   |
| Intel UHD Graphics 620                                                      | 9         | 0.94%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 9         | 0.94%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 9         | 0.94%   |
| AMD Lucienne                                                                | 9         | 0.94%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 8         | 0.84%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 8         | 0.84%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 8         | 0.84%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 8         | 0.84%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 7         | 0.73%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7         | 0.73%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 7         | 0.73%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                      | 7         | 0.73%   |
| Intel HD Graphics 630                                                       | 7         | 0.73%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 6         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x AMD            | 228       | 31.23%  |
| 1 x Nvidia         | 169       | 23.15%  |
| 1 x Intel          | 133       | 18.22%  |
| Intel + Nvidia     | 102       | 13.97%  |
| AMD + Nvidia       | 45        | 6.16%   |
| 2 x AMD            | 30        | 4.11%   |
| Intel + AMD        | 18        | 2.47%   |
| 2 x Nvidia         | 3         | 0.41%   |
| Other              | 1         | 0.14%   |
| Intel + 2 x Nvidia | 1         | 0.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 463       | 63.25%  |
| Proprietary | 256       | 34.97%  |
| Unknown     | 13        | 1.78%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 321       | 43.32%  |
| 7.01-8.0   | 106       | 14.3%   |
| 0.01-0.5   | 80        | 10.8%   |
| 8.01-16.0  | 63        | 8.5%    |
| 1.01-2.0   | 58        | 7.83%   |
| 3.01-4.0   | 42        | 5.67%   |
| 0.51-1.0   | 32        | 4.32%   |
| 5.01-6.0   | 19        | 2.56%   |
| 16.01-24.0 | 15        | 2.02%   |
| 2.01-3.0   | 5         | 0.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 122       | 13.9%   |
| AU Optronics            | 72        | 8.2%    |
| BOE                     | 60        | 6.83%   |
| Goldstar                | 59        | 6.72%   |
| LG Display              | 51        | 5.81%   |
| Chimei Innolux          | 51        | 5.81%   |
| Acer                    | 47        | 5.35%   |
| Dell                    | 45        | 5.13%   |
| Hewlett-Packard         | 30        | 3.42%   |
| BenQ                    | 29        | 3.3%    |
| Ancor Communications    | 29        | 3.3%    |
| ASUSTek Computer        | 25        | 2.85%   |
| AOC                     | 25        | 2.85%   |
| MSI                     | 18        | 2.05%   |
| PANDA                   | 16        | 1.82%   |
| Apple                   | 16        | 1.82%   |
| ViewSonic               | 13        | 1.48%   |
| Lenovo                  | 13        | 1.48%   |
| Sharp                   | 12        | 1.37%   |
| Vizio                   | 11        | 1.25%   |
| Sony                    | 11        | 1.25%   |
| Philips                 | 9         | 1.03%   |
| Gigabyte Technology     | 8         | 0.91%   |
| InfoVision              | 7         | 0.8%    |
| Sceptre Tech            | 6         | 0.68%   |
| Iiyama                  | 6         | 0.68%   |
| Toshiba                 | 5         | 0.57%   |
| Unknown                 | 4         | 0.46%   |
| Panasonic               | 4         | 0.46%   |
| HKC                     | 4         | 0.46%   |
| Eizo                    | 4         | 0.46%   |
| Chi Mei Optoelectronics | 4         | 0.46%   |
| Pixio                   | 3         | 0.34%   |
| NEC Computers           | 3         | 0.34%   |
| Valve                   | 2         | 0.23%   |
| TMX                     | 2         | 0.23%   |
| SNC                     | 2         | 0.23%   |
| Insignia                | 2         | 0.23%   |
| HUAWEI                  | 2         | 0.23%   |
| CSO                     | 2         | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch   | 7         | 0.77%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                 | 5         | 0.55%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 5         | 0.55%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 4         | 0.44%   |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch            | 4         | 0.44%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch          | 4         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 4         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch        | 4         | 0.44%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                     | 4         | 0.44%   |
| Acer GN246HL ACR02F9 1920x1080 531x299mm 24.0-inch                      | 4         | 0.44%   |
| Vizio V505-H1 VIZ1039 3840x2160 941x529mm 42.5-inch                     | 3         | 0.33%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch               | 3         | 0.33%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch   | 3         | 0.33%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 3         | 0.33%   |
| MSI Optix MAG27CQ MSI1462 2560x1440 597x336mm 27.0-inch                 | 3         | 0.33%   |
| MSI G32C4 MSI3DA6 1920x1080 698x393mm 31.5-inch                         | 3         | 0.33%   |
| MSI G27C4 MSI3CA9 1920x1080 598x336mm 27.0-inch                         | 3         | 0.33%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch            | 3         | 0.33%   |
| Goldstar LG ULTRAGEAR GSM7766 2560x1440 700x390mm 31.5-inch             | 3         | 0.33%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 3         | 0.33%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                       | 3         | 0.33%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch           | 3         | 0.33%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch          | 3         | 0.33%   |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch            | 3         | 0.33%   |
| ASUSTek Computer PA278QV AUS2700 2560x1440 597x336mm 27.0-inch          | 3         | 0.33%   |
| AOC 27V2G5 AOC2702 1920x1080 598x336mm 27.0-inch                        | 3         | 0.33%   |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 597x336mm 27.0-inch   | 3         | 0.33%   |
| Acer GN246HL ACR02FA 1920x1080 531x299mm 24.0-inch                      | 3         | 0.33%   |
| Vizio E480i-C2 VIZ1004 1920x1080 477x268mm 21.5-inch                    | 2         | 0.22%   |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch           | 2         | 0.22%   |
| Toshiba TV TSB0108 1280x1024 708x398mm 32.0-inch                        | 2         | 0.22%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch                 | 2         | 0.22%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch          | 2         | 0.22%   |
| Samsung Electronics T24C300 SAM0A9B 1920x1080 531x299mm 24.0-inch       | 2         | 0.22%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch    | 2         | 0.22%   |
| Samsung Electronics SMB2230H SAM0648 1920x1080                          | 2         | 0.22%   |
| Samsung Electronics LCD Monitor SDC4156 1920x1080 294x165mm 13.3-inch   | 2         | 0.22%   |
| Samsung Electronics LCD Monitor SDC4152 2880x1800 302x189mm 14.0-inch   | 2         | 0.22%   |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 1872x1053mm 84.6-inch | 2         | 0.22%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch  | 2         | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 382       | 46.7%   |
| 2560x1440 (QHD)    | 103       | 12.59%  |
| 3840x2160 (4K)     | 84        | 10.27%  |
| 1366x768 (WXGA)    | 69        | 8.44%   |
| 1680x1050 (WSXGA+) | 21        | 2.57%   |
| 3440x1440          | 20        | 2.44%   |
| 1920x1200 (WUXGA)  | 18        | 2.2%    |
| 2560x1600          | 14        | 1.71%   |
| 1440x900 (WXGA+)   | 14        | 1.71%   |
| 2560x1080          | 12        | 1.47%   |
| 1600x900 (HD+)     | 10        | 1.22%   |
| 1280x1024 (SXGA)   | 10        | 1.22%   |
| 1360x768           | 9         | 1.1%    |
| 2880x1800          | 7         | 0.86%   |
| 1920x540           | 7         | 0.86%   |
| 2288x1287          | 4         | 0.49%   |
| 1280x800 (WXGA)    | 4         | 0.49%   |
| 3840x1080          | 3         | 0.37%   |
| 2736x1824          | 3         | 0.37%   |
| 2240x1400          | 3         | 0.37%   |
| 3840x2400          | 2         | 0.24%   |
| 3840x1600          | 2         | 0.24%   |
| 1600x1200          | 2         | 0.24%   |
| Unknown            | 2         | 0.24%   |
| 800x1280           | 1         | 0.12%   |
| 5760x1080          | 1         | 0.12%   |
| 3840x2560          | 1         | 0.12%   |
| 3456x2160          | 1         | 0.12%   |
| 3200x2000          | 1         | 0.12%   |
| 3200x1800 (QHD+)   | 1         | 0.12%   |
| 2520x1680          | 1         | 0.12%   |
| 2160x1440          | 1         | 0.12%   |
| 2048x1152          | 1         | 0.12%   |
| 1600x2560          | 1         | 0.12%   |
| 1280x960           | 1         | 0.12%   |
| 1280x720 (HD)      | 1         | 0.12%   |
| 1080x1920          | 1         | 0.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 172       | 19.75%  |
| 27      | 122       | 14.01%  |
| 24      | 66        | 7.58%   |
| 23      | 58        | 6.66%   |
| 31      | 51        | 5.86%   |
| 13      | 50        | 5.74%   |
| 17      | 43        | 4.94%   |
| 21      | 42        | 4.82%   |
| 14      | 35        | 4.02%   |
| 34      | 24        | 2.76%   |
| 84      | 16        | 1.84%   |
| Unknown | 15        | 1.72%   |
| 16      | 14        | 1.61%   |
| 22      | 13        | 1.49%   |
| 19      | 13        | 1.49%   |
| 18      | 12        | 1.38%   |
| 40      | 11        | 1.26%   |
| 20      | 11        | 1.26%   |
| 72      | 10        | 1.15%   |
| 32      | 10        | 1.15%   |
| 48      | 8         | 0.92%   |
| 29      | 7         | 0.8%    |
| 26      | 6         | 0.69%   |
| 42      | 5         | 0.57%   |
| 12      | 5         | 0.57%   |
| 33      | 4         | 0.46%   |
| 142     | 3         | 0.34%   |
| 69      | 3         | 0.34%   |
| 54      | 3         | 0.34%   |
| 52      | 3         | 0.34%   |
| 35      | 3         | 0.34%   |
| 28      | 3         | 0.34%   |
| 25      | 3         | 0.34%   |
| 60      | 2         | 0.23%   |
| 55      | 2         | 0.23%   |
| 43      | 2         | 0.23%   |
| 38      | 2         | 0.23%   |
| 37      | 2         | 0.23%   |
| 11      | 2         | 0.23%   |
| 8       | 2         | 0.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 248       | 29.07%  |
| 501-600        | 225       | 26.38%  |
| 401-500        | 87        | 10.2%   |
| 601-700        | 73        | 8.56%   |
| 351-400        | 45        | 5.28%   |
| 701-800        | 37        | 4.34%   |
| 201-300        | 35        | 4.1%    |
| 1501-2000      | 31        | 3.63%   |
| 1001-1500      | 23        | 2.7%    |
| 801-900        | 19        | 2.23%   |
| Unknown        | 15        | 1.76%   |
| 901-1000       | 8         | 0.94%   |
| More than 2000 | 4         | 0.47%   |
| 101-200        | 2         | 0.23%   |
| 1-100          | 1         | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 578       | 78.53%  |
| 16/10   | 83        | 11.28%  |
| 21/9    | 33        | 4.48%   |
| 5/4     | 12        | 1.63%   |
| 3/2     | 8         | 1.09%   |
| 4/3     | 6         | 0.82%   |
| 32/9    | 5         | 0.68%   |
| 1.00    | 3         | 0.41%   |
| Unknown | 3         | 0.41%   |
| 0.62    | 2         | 0.27%   |
| 1.96    | 1         | 0.14%   |
| 0.67    | 1         | 0.14%   |
| 0.56    | 1         | 0.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 175       | 20.47%  |
| 201-250        | 140       | 16.37%  |
| 301-350        | 129       | 15.09%  |
| 351-500        | 93        | 10.88%  |
| 81-90          | 65        | 7.6%    |
| More than 1000 | 51        | 5.96%   |
| 151-200        | 39        | 4.56%   |
| 121-130        | 32        | 3.74%   |
| 501-1000       | 30        | 3.51%   |
| 251-300        | 25        | 2.92%   |
| 71-80          | 21        | 2.46%   |
| 141-150        | 15        | 1.75%   |
| Unknown        | 15        | 1.75%   |
| 111-120        | 11        | 1.29%   |
| 131-140        | 4         | 0.47%   |
| 61-70          | 3         | 0.35%   |
| 1-40           | 3         | 0.35%   |
| 51-60          | 2         | 0.23%   |
| 41-50          | 1         | 0.12%   |
| 91-100         | 1         | 0.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 311       | 37.7%   |
| 121-160       | 205       | 24.85%  |
| 101-120       | 177       | 21.45%  |
| 161-240       | 57        | 6.91%   |
| 1-50          | 40        | 4.85%   |
| More than 240 | 20        | 2.42%   |
| Unknown       | 15        | 1.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 525       | 70.95%  |
| 2     | 165       | 22.3%   |
| 3     | 27        | 3.65%   |
| 0     | 21        | 2.84%   |
| 4     | 2         | 0.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 438       | 38.12%  |
| Intel                           | 378       | 32.9%   |
| Qualcomm Atheros                | 68        | 5.92%   |
| MediaTek                        | 55        | 4.79%   |
| Broadcom                        | 53        | 4.61%   |
| TP-Link                         | 24        | 2.09%   |
| Microsoft                       | 19        | 1.65%   |
| Ralink Technology               | 12        | 1.04%   |
| ASIX Electronics                | 10        | 0.87%   |
| Broadcom Limited                | 9         | 0.78%   |
| Xiaomi                          | 7         | 0.61%   |
| Samsung Electronics             | 6         | 0.52%   |
| Qualcomm                        | 5         | 0.44%   |
| Nvidia                          | 5         | 0.44%   |
| Marvell Technology Group        | 5         | 0.44%   |
| Aquantia                        | 5         | 0.44%   |
| Ralink                          | 4         | 0.35%   |
| Qualcomm Atheros Communications | 4         | 0.35%   |
| Motorola PCS                    | 4         | 0.35%   |
| ASUSTek Computer                | 4         | 0.35%   |
| Lenovo                          | 3         | 0.26%   |
| Sierra Wireless                 | 2         | 0.17%   |
| OPPO Electronics                | 2         | 0.17%   |
| Oculus VR                       | 2         | 0.17%   |
| NetGear                         | 2         | 0.17%   |
| Hewlett-Packard                 | 2         | 0.17%   |
| D-Link System                   | 2         | 0.17%   |
| ZTE WCDMA Technologies MSM      | 1         | 0.09%   |
| Wacom                           | 1         | 0.09%   |
| T & A Mobile Phones             | 1         | 0.09%   |
| ROCCAT                          | 1         | 0.09%   |
| Panasonic (Matsushita)          | 1         | 0.09%   |
| Padix (Rockfire)                | 1         | 0.09%   |
| Microchip Technology            | 1         | 0.09%   |
| Mellanox Technologies           | 1         | 0.09%   |
| Loupedeck                       | 1         | 0.09%   |
| Linksys                         | 1         | 0.09%   |
| JMicron Technology              | 1         | 0.09%   |
| ICS Advent                      | 1         | 0.09%   |
| Holtek Semiconductor            | 1         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 306       | 23.06%  |
| Realtek RTL8125 2.5GbE Controller                                 | 70        | 5.28%   |
| Intel Wi-Fi 6 AX200                                               | 64        | 4.82%   |
| Intel I211 Gigabit Network Connection                             | 39        | 2.94%   |
| Intel Ethernet Controller I225-V                                  | 36        | 2.71%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 26        | 1.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 20        | 1.51%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 19        | 1.43%   |
| Intel Wireless 8265 / 8275                                        | 19        | 1.43%   |
| Intel Wi-Fi 6 AX201                                               | 18        | 1.36%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 17        | 1.28%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 17        | 1.28%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 17        | 1.28%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 1.13%   |
| Intel Ethernet Connection (7) I219-V                              | 15        | 1.13%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 15        | 1.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 13        | 0.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 13        | 0.98%   |
| Intel Wireless 8260                                               | 13        | 0.98%   |
| Intel Wireless 7265                                               | 13        | 0.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 13        | 0.98%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter      | 13        | 0.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 12        | 0.9%    |
| Intel Wireless-AC 9260                                            | 11        | 0.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 0.83%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 10        | 0.75%   |
| Intel Wireless 7260                                               | 10        | 0.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 0.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 0.68%   |
| Microsoft Wireless XBox Controller Dongle                         | 9         | 0.68%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 9         | 0.68%   |
| ASIX AX88179 Gigabit Ethernet                                     | 9         | 0.68%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 8         | 0.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 0.6%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 8         | 0.6%    |
| Intel Ethernet Connection (2) I219-V                              | 8         | 0.6%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 7         | 0.53%   |
| Realtek 802.11ac NIC                                              | 7         | 0.53%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 7         | 0.53%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 290       | 47.46%  |
| Realtek Semiconductor           | 91        | 14.89%  |
| MediaTek                        | 55        | 9%      |
| Broadcom                        | 45        | 7.36%   |
| Qualcomm Atheros                | 43        | 7.04%   |
| TP-Link                         | 23        | 3.76%   |
| Microsoft                       | 19        | 3.11%   |
| Ralink Technology               | 12        | 1.96%   |
| Broadcom Limited                | 7         | 1.15%   |
| Ralink                          | 4         | 0.65%   |
| Qualcomm Atheros Communications | 4         | 0.65%   |
| ASUSTek Computer                | 4         | 0.65%   |
| Marvell Technology Group        | 3         | 0.49%   |
| Sierra Wireless                 | 2         | 0.33%   |
| NetGear                         | 2         | 0.33%   |
| D-Link System                   | 2         | 0.33%   |
| Wacom                           | 1         | 0.16%   |
| Panasonic (Matsushita)          | 1         | 0.16%   |
| Linksys                         | 1         | 0.16%   |
| D-Link                          | 1         | 0.16%   |
| Belkin Components               | 1         | 0.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 64        | 10.42%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 26        | 4.23%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 20        | 3.26%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 19        | 3.09%   |
| Intel Wireless 8265 / 8275                                    | 19        | 3.09%   |
| Intel Wi-Fi 6 AX201                                           | 18        | 2.93%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 17        | 2.77%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 17        | 2.77%   |
| Intel Comet Lake PCH CNVi WiFi                                | 17        | 2.77%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 15        | 2.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 13        | 2.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 13        | 2.12%   |
| Intel Wireless 8260                                           | 13        | 2.12%   |
| Intel Wireless 7265                                           | 13        | 2.12%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 13        | 2.12%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter  | 13        | 2.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 12        | 1.95%   |
| Intel Wireless-AC 9260                                        | 11        | 1.79%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 10        | 1.63%   |
| Intel Wireless 7260                                           | 10        | 1.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 9         | 1.47%   |
| Microsoft Wireless XBox Controller Dongle                     | 9         | 1.47%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 9         | 1.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 8         | 1.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 8         | 1.3%    |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 7         | 1.14%   |
| Realtek 802.11ac NIC                                          | 7         | 1.14%   |
| Broadcom BCM43142 802.11b/g/n                                 | 7         | 1.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 6         | 0.98%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 6         | 0.98%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 6         | 0.98%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter      | 5         | 0.81%   |
| Microsoft XBOX ACC                                            | 5         | 0.81%   |
| Microsoft Xbox 360 Wireless Adapter                           | 5         | 0.81%   |
| Intel Raptor Lake PCH CNVi WiFi                               | 5         | 0.81%   |
| Broadcom BCM4331 802.11a/b/g/n                                | 5         | 0.81%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                           | 4         | 0.65%   |
| TP-Link 802.11ac NIC                                          | 4         | 0.65%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 4         | 0.65%   |
| Qualcomm Atheros AR9271 802.11n                               | 4         | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 401       | 58.28%  |
| Intel                      | 178       | 25.87%  |
| Qualcomm Atheros           | 30        | 4.36%   |
| Broadcom                   | 18        | 2.62%   |
| ASIX Electronics           | 10        | 1.45%   |
| Xiaomi                     | 7         | 1.02%   |
| Qualcomm                   | 5         | 0.73%   |
| Nvidia                     | 5         | 0.73%   |
| Aquantia                   | 5         | 0.73%   |
| Samsung Electronics        | 4         | 0.58%   |
| Motorola PCS               | 4         | 0.58%   |
| Lenovo                     | 3         | 0.44%   |
| OPPO Electronics           | 2         | 0.29%   |
| Marvell Technology Group   | 2         | 0.29%   |
| Hewlett-Packard            | 2         | 0.29%   |
| Broadcom Limited           | 2         | 0.29%   |
| ZTE WCDMA Technologies MSM | 1         | 0.15%   |
| TP-Link                    | 1         | 0.15%   |
| T & A Mobile Phones        | 1         | 0.15%   |
| Mellanox Technologies      | 1         | 0.15%   |
| MediaTek                   | 1         | 0.15%   |
| JMicron Technology         | 1         | 0.15%   |
| ICS Advent                 | 1         | 0.15%   |
| Google                     | 1         | 0.15%   |
| DisplayLink                | 1         | 0.15%   |
| American Megatrends        | 1         | 0.15%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 306       | 43.53%  |
| Realtek RTL8125 2.5GbE Controller                                 | 70        | 9.96%   |
| Intel I211 Gigabit Network Connection                             | 39        | 5.55%   |
| Intel Ethernet Controller I225-V                                  | 36        | 5.12%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 2.13%   |
| Intel Ethernet Connection (7) I219-V                              | 15        | 2.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 1.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 1.28%   |
| ASIX AX88179 Gigabit Ethernet                                     | 9         | 1.28%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 8         | 1.14%   |
| Intel Ethernet Connection (2) I219-V                              | 8         | 1.14%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 7         | 1%      |
| Intel Ethernet Connection I217-LM                                 | 7         | 1%      |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 7         | 1%      |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 6         | 0.85%   |
| Intel Ethernet Connection I217-V                                  | 6         | 0.85%   |
| Intel Ethernet Connection (7) I219-LM                             | 6         | 0.85%   |
| Intel Ethernet Connection (2) I218-V                              | 6         | 0.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 0.71%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 0.71%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 0.71%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4         | 0.57%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 0.57%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 4         | 0.57%   |
| Motorola PCS moto g62 5G                                          | 4         | 0.57%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 0.57%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 0.57%   |
| Intel Ethernet Connection (17) I219-V                             | 4         | 0.57%   |
| Intel Ethernet Connection (12) I219-V                             | 4         | 0.57%   |
| Nvidia MCP79 Ethernet                                             | 3         | 0.43%   |
| Intel I210 Gigabit Network Connection                             | 3         | 0.43%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.43%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.43%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.43%   |
| Intel Ethernet Connection (14) I219-V                             | 3         | 0.43%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.28%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 0.28%   |
| Qualcomm Redmi 9T                                                 | 2         | 0.28%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.28%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 641       | 52.5%   |
| WiFi     | 570       | 46.68%  |
| Modem    | 6         | 0.49%   |
| Unknown  | 4         | 0.33%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 391       | 51.25%  |
| WiFi     | 372       | 48.75%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 388       | 53.22%  |
| 1     | 308       | 42.25%  |
| 3     | 23        | 3.16%   |
| 0     | 8         | 1.1%    |
| 6     | 1         | 0.14%   |
| 4     | 1         | 0.14%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 499       | 68.17%  |
| Yes  | 233       | 31.83%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 277       | 52.56%  |
| Realtek Semiconductor           | 45        | 8.54%   |
| Cambridge Silicon Radio         | 39        | 7.4%    |
| MediaTek                        | 25        | 4.74%   |
| Foxconn / Hon Hai               | 21        | 3.98%   |
| Qualcomm Atheros Communications | 20        | 3.8%    |
| Broadcom                        | 18        | 3.42%   |
| Apple                           | 18        | 3.42%   |
| IMC Networks                    | 17        | 3.23%   |
| Lite-On Technology              | 14        | 2.66%   |
| ASUSTek Computer                | 9         | 1.71%   |
| TP-Link                         | 6         | 1.14%   |
| Marvell Semiconductor           | 3         | 0.57%   |
| Edimax Technology               | 3         | 0.57%   |
| Toshiba                         | 2         | 0.38%   |
| Ralink                          | 2         | 0.38%   |
| Actions                         | 2         | 0.38%   |
| Realtek                         | 1         | 0.19%   |
| Integrated System Solution      | 1         | 0.19%   |
| Foxconn International           | 1         | 0.19%   |
| Dynex                           | 1         | 0.19%   |
| Dell                            | 1         | 0.19%   |
| Unknown                         | 1         | 0.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                      | 66        | 12.5%   |
| Intel AX200 Bluetooth                                   | 63        | 11.93%  |
| Intel AX201 Bluetooth                                   | 46        | 8.71%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 39        | 7.39%   |
| Realtek Bluetooth Radio                                 | 30        | 5.68%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 28        | 5.3%    |
| MediaTek Wireless_Device                                | 25        | 4.73%   |
| Intel AX210 Bluetooth                                   | 25        | 4.73%   |
| Intel Bluetooth Device                                  | 23        | 4.36%   |
| Intel Wireless-AC 3168 Bluetooth                        | 13        | 2.46%   |
| Apple Bluetooth Host Controller                         | 11        | 2.08%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 9         | 1.7%    |
| IMC Networks Wireless_Device                            | 9         | 1.7%    |
| Qualcomm Atheros  Bluetooth Device                      | 7         | 1.33%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter            | 7         | 1.33%   |
| TP-Link TP-Cdj+ UB5A Adapter                            | 6         | 1.14%   |
| Realtek  Bluetooth 4.2 Adapter                          | 6         | 1.14%   |
| Foxconn / Hon Hai Wireless_Device                       | 6         | 1.14%   |
| Realtek 802.11ac WLAN Adapter                           | 5         | 0.95%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                   | 5         | 0.95%   |
| IMC Networks Bluetooth Radio                            | 5         | 0.95%   |
| Broadcom BCM20702A0 Bluetooth 4.0                       | 5         | 0.95%   |
| ASUS ASUS USB-BT500                                     | 5         | 0.95%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth              | 4         | 0.76%   |
| Intel Centrino Bluetooth Wireless Transceiver           | 4         | 0.76%   |
| Apple Bluetooth USB Host Controller                     | 4         | 0.76%   |
| Qualcomm Atheros Bluetooth USB Host Controller          | 3         | 0.57%   |
| Marvell Bluetooth and Wireless LAN Composite            | 3         | 0.57%   |
| Lite-On Bluetooth Device                                | 3         | 0.57%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter | 3         | 0.57%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                 | 2         | 0.38%   |
| Ralink RT3290 Bluetooth                                 | 2         | 0.38%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                  | 2         | 0.38%   |
| Lite-On Wireless_Device                                 | 2         | 0.38%   |
| Lite-On Bluetooth Radio                                 | 2         | 0.38%   |
| Lite-On Atheros AR3012 Bluetooth                        | 2         | 0.38%   |
| IMC Networks Bluetooth Device                           | 2         | 0.38%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth           | 2         | 0.38%   |
| Foxconn / Hon Hai Bluetooth Device                      | 2         | 0.38%   |
| Broadcom HP Portable Bumble Bee                         | 2         | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 398       | 30.64%  |
| AMD                        | 385       | 29.64%  |
| Nvidia                     | 267       | 20.55%  |
| C-Media Electronics        | 35        | 2.69%   |
| Logitech                   | 30        | 2.31%   |
| Razer USA                  | 13        | 1%      |
| Kingston Technology        | 13        | 1%      |
| ASUSTek Computer           | 13        | 1%      |
| Creative Labs              | 10        | 0.77%   |
| SteelSeries ApS            | 9         | 0.69%   |
| Creative Technology        | 8         | 0.62%   |
| Texas Instruments          | 6         | 0.46%   |
| Sony                       | 6         | 0.46%   |
| Plantronics                | 6         | 0.46%   |
| JMTek                      | 6         | 0.46%   |
| Samson Technologies        | 5         | 0.38%   |
| Realtek Semiconductor      | 5         | 0.38%   |
| Micro Star International   | 5         | 0.38%   |
| Focusrite-Novation         | 5         | 0.38%   |
| Corsair                    | 5         | 0.38%   |
| Lenovo                     | 4         | 0.31%   |
| GN Netcom                  | 4         | 0.31%   |
| Blue Microphones           | 4         | 0.31%   |
| ROCCAT                     | 3         | 0.23%   |
| PreSonus Audio Electronics | 3         | 0.23%   |
| Hewlett-Packard            | 3         | 0.23%   |
| Audio-Technica             | 3         | 0.23%   |
| TTGK Technology            | 2         | 0.15%   |
| Tenx Technology            | 2         | 0.15%   |
| SAVITECH                   | 2         | 0.15%   |
| Native Instruments         | 2         | 0.15%   |
| Generalplus Technology     | 2         | 0.15%   |
| Astro Gaming               | 2         | 0.15%   |
| Asahi Kasei Microsystems   | 2         | 0.15%   |
| Apple                      | 2         | 0.15%   |
| Unknown                    | 2         | 0.15%   |
| VIA Technologies           | 1         | 0.08%   |
| Turtle Beach               | 1         | 0.08%   |
| Trust                      | 1         | 0.08%   |
| Solid State System         | 1         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 141       | 8.86%   |
| AMD Starship/Matisse HD Audio Controller                                   | 94        | 5.91%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 78        | 4.9%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 59        | 3.71%   |
| Intel Cannon Lake PCH cAVS                                                 | 43        | 2.7%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 43        | 2.7%    |
| Intel Sunrise Point-LP HD Audio                                            | 35        | 2.2%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 34        | 2.14%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 34        | 2.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 30        | 1.89%   |
| Nvidia TU106 High Definition Audio Controller                              | 28        | 1.76%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 28        | 1.76%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 28        | 1.76%   |
| Nvidia GA104 High Definition Audio Controller                              | 27        | 1.7%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 26        | 1.63%   |
| Nvidia GA106 High Definition Audio Controller                              | 25        | 1.57%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 23        | 1.45%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 22        | 1.38%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 21        | 1.32%   |
| Intel Comet Lake PCH cAVS                                                  | 21        | 1.32%   |
| Nvidia GP104 High Definition Audio Controller                              | 20        | 1.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 20        | 1.26%   |
| Intel 8 Series HD Audio Controller                                         | 18        | 1.13%   |
| Nvidia GP107GL High Definition Audio Controller                            | 17        | 1.07%   |
| Nvidia GA102 High Definition Audio Controller                              | 17        | 1.07%   |
| Intel Haswell-ULT HD Audio Controller                                      | 17        | 1.07%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 17        | 1.07%   |
| AMD Navi 10 HDMI Audio                                                     | 17        | 1.07%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 16        | 1.01%   |
| Intel Alder Lake-S HD Audio Controller                                     | 15        | 0.94%   |
| Intel 200 Series PCH HD Audio                                              | 15        | 0.94%   |
| Nvidia TU116 High Definition Audio Controller                              | 14        | 0.88%   |
| Nvidia TU104 HD Audio Controller                                           | 14        | 0.88%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 14        | 0.88%   |
| Nvidia Audio device                                                        | 13        | 0.82%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 13        | 0.82%   |
| AMD FCH Azalia Controller                                                  | 13        | 0.82%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 13        | 0.82%   |
| ASUSTek Computer USB Audio                                                 | 12        | 0.75%   |
| C-Media Electronics USB Audio Device                                       | 11        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 44        | 22.22%  |
| SK hynix            | 27        | 13.64%  |
| Micron Technology   | 25        | 12.63%  |
| Corsair             | 21        | 10.61%  |
| Kingston            | 20        | 10.1%   |
| G.Skill             | 19        | 9.6%    |
| Crucial             | 10        | 5.05%   |
| Unknown             | 7         | 3.54%   |
| Team                | 7         | 3.54%   |
| A-DATA Technology   | 5         | 2.53%   |
| Ramaxel Technology  | 3         | 1.52%   |
| Unknown (ABCD)      | 2         | 1.01%   |
| Transcend           | 1         | 0.51%   |
| Nanya Technology    | 1         | 0.51%   |
| Hewlett-Packard     | 1         | 0.51%   |
| GOODRAM             | 1         | 0.51%   |
| Elpida              | 1         | 0.51%   |
| Asgard              | 1         | 0.51%   |
| AMD                 | 1         | 0.51%   |
| Unknown             | 1         | 0.51%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 2.39%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 1.91%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 4         | 1.91%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 4         | 1.91%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.44%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.44%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 3         | 1.44%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                        | 2         | 0.96%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 0.96%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.96%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.96%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.96%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 0.96%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.96%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 0.96%   |
| Samsung RAM M425R2GA3BB0-CWMOD 16GB SODIMM 5600MT/s              | 2         | 0.96%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 2         | 0.96%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM DDR5 4800MT/s          | 2         | 0.96%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s             | 2         | 0.96%   |
| Micron RAM 53E2G32D4NQ-046 4096MB Row Of Chips LPDDR4 4267MT/s   | 2         | 0.96%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.96%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s             | 2         | 0.96%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 2         | 0.96%   |
| G.Skill RAM F4-3600C18-8GTRS 8GB DIMM DDR4 3600MT/s              | 2         | 0.96%   |
| G.Skill RAM F4-3600C16-8GTZNC 8GB DIMM DDR4 3800MT/s             | 2         | 0.96%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 2         | 0.96%   |
| Corsair RAM CMY16GX3M2A1866C9 8GB DIMM DDR3 2400MT/s             | 2         | 0.96%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3733MT/s            | 2         | 0.96%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s           | 2         | 0.96%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                      | 1         | 0.48%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 0.48%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                             | 1         | 0.48%   |
| Unknown RAM Module 4GB SODIMM DDR4 2133MT/s                      | 1         | 0.48%   |
| Unknown RAM 2400 C15 Series 16384MB DIMM DDR4 2133MT/s           | 1         | 0.48%   |
| Transcend RAM JM2666HSH-4G 4GB SODIMM DDR4 2667MT/s              | 1         | 0.48%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3733MT/s               | 1         | 0.48%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s               | 1         | 0.48%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s               | 1         | 0.48%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s              | 1         | 0.48%   |
| Team RAM TEAMGROUP-UD3 8GB DIMM DDR3 1600MT/s                    | 1         | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 105       | 62.5%   |
| DDR3    | 28        | 16.67%  |
| DDR5    | 18        | 10.71%  |
| LPDDR4  | 9         | 5.36%   |
| LPDDR5  | 3         | 1.79%   |
| Unknown | 2         | 1.19%   |
| SDRAM   | 1         | 0.6%    |
| LPDDR3  | 1         | 0.6%    |
| DDR2    | 1         | 0.6%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 79        | 46.75%  |
| DIMM         | 76        | 44.97%  |
| Row Of Chips | 14        | 8.28%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 85        | 46.7%   |
| 16384 | 39        | 21.43%  |
| 4096  | 29        | 15.93%  |
| 32768 | 17        | 9.34%   |
| 2048  | 11        | 6.04%   |
| 1024  | 1         | 0.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 42        | 23.33%  |
| 2667  | 21        | 11.67%  |
| 1600  | 19        | 10.56%  |
| 3600  | 13        | 7.22%   |
| 2400  | 13        | 7.22%   |
| 4800  | 7         | 3.89%   |
| 1333  | 7         | 3.89%   |
| 3733  | 6         | 3.33%   |
| 5600  | 5         | 2.78%   |
| 6400  | 4         | 2.22%   |
| 6000  | 4         | 2.22%   |
| 4267  | 4         | 2.22%   |
| 3866  | 3         | 1.67%   |
| 3800  | 3         | 1.67%   |
| 3266  | 3         | 1.67%   |
| 2133  | 3         | 1.67%   |
| 3534  | 2         | 1.11%   |
| 3466  | 2         | 1.11%   |
| 2933  | 2         | 1.11%   |
| 1066  | 2         | 1.11%   |
| 5800  | 1         | 0.56%   |
| 5200  | 1         | 0.56%   |
| 4266  | 1         | 0.56%   |
| 3933  | 1         | 0.56%   |
| 3533  | 1         | 0.56%   |
| 3400  | 1         | 0.56%   |
| 3334  | 1         | 0.56%   |
| 3333  | 1         | 0.56%   |
| 3100  | 1         | 0.56%   |
| 3000  | 1         | 0.56%   |
| 2800  | 1         | 0.56%   |
| 1867  | 1         | 0.56%   |
| 1334  | 1         | 0.56%   |
| 975   | 1         | 0.56%   |
| 800   | 1         | 0.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 5         | 33.33%  |
| Canon               | 4         | 26.67%  |
| Hewlett-Packard     | 2         | 13.33%  |
| STMicroelectronics  | 1         | 6.67%   |
| Seiko Epson         | 1         | 6.67%   |
| Samsung Electronics | 1         | 6.67%   |
| Dell                | 1         | 6.67%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 6.67%   |
| Seiko Epson XP-2100 Series                                | 1         | 6.67%   |
| Samsung Composite Device                                  | 1         | 6.67%   |
| HP DeskJet Plus 4100 series                               | 1         | 6.67%   |
| HP Color LaserJet CP1215                                  | 1         | 6.67%   |
| Dell 1130 Laser Printer                                   | 1         | 6.67%   |
| Canon TS700 series                                        | 1         | 6.67%   |
| Canon TR4500 series                                       | 1         | 6.67%   |
| Canon PIXMA MX370 Series                                  | 1         | 6.67%   |
| Canon G2000 series                                        | 1         | 6.67%   |
| Brother MFC-L2710DN series                                | 1         | 6.67%   |
| Brother MFC-J460DW                                        | 1         | 6.67%   |
| Brother HL-L2370DW series                                 | 1         | 6.67%   |
| Brother HL-L2320D series                                  | 1         | 6.67%   |
| Brother DCP-1510                                          | 1         | 6.67%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 50%     |
| Canon           | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| HP ScanJet 2400c              | 1         | 50%     |
| Canon CanoScan N1240U/LiDE 30 | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 66        | 17.93%  |
| IMC Networks                           | 38        | 10.33%  |
| Logitech                               | 32        | 8.7%    |
| Apple                                  | 25        | 6.79%   |
| Realtek Semiconductor                  | 22        | 5.98%   |
| Microdia                               | 21        | 5.71%   |
| Bison Electronics                      | 19        | 5.16%   |
| Sunplus Innovation Technology          | 18        | 4.89%   |
| Quanta                                 | 15        | 4.08%   |
| Cheng Uei Precision Industry (Foxlink) | 13        | 3.53%   |
| Syntek                                 | 12        | 3.26%   |
| Luxvisions Innotech Limited            | 9         | 2.45%   |
| Lite-On Technology                     | 8         | 2.17%   |
| Sonix Technology                       | 7         | 1.9%    |
| Microsoft                              | 7         | 1.9%    |
| Suyin                                  | 6         | 1.63%   |
| SunplusIT                              | 5         | 1.36%   |
| Samsung Electronics                    | 4         | 1.09%   |
| Silicon Motion                         | 3         | 0.82%   |
| ARC International                      | 3         | 0.82%   |
| Acer                                   | 3         | 0.82%   |
| Razer USA                              | 2         | 0.54%   |
| MacroSilicon                           | 2         | 0.54%   |
| Intel                                  | 2         | 0.54%   |
| HRY                                    | 2         | 0.54%   |
| Hewlett-Packard                        | 2         | 0.54%   |
| HDR webcam                             | 2         | 0.54%   |
| Z-Star Microelectronics                | 1         | 0.27%   |
| YGTek                                  | 1         | 0.27%   |
| WCM_USB                                | 1         | 0.27%   |
| Tobii Technology AB                    | 1         | 0.27%   |
| Shine-optics                           | 1         | 0.27%   |
| Ruision                                | 1         | 0.27%   |
| Owon                                   | 1         | 0.27%   |
| lihappe8                               | 1         | 0.27%   |
| Lenovo                                 | 1         | 0.27%   |
| KYE Systems (Mouse Systems)            | 1         | 0.27%   |
| Importek                               | 1         | 0.27%   |
| Google                                 | 1         | 0.27%   |
| Goodong Industry                       | 1         | 0.27%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 19        | 5.12%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 17        | 4.58%   |
| Realtek Integrated_Webcam_HD                        | 12        | 3.23%   |
| IMC Networks Integrated Camera                      | 10        | 2.7%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 10        | 2.7%    |
| Syntek Integrated Camera                            | 9         | 2.43%   |
| Logitech C922 Pro Stream Webcam                     | 9         | 2.43%   |
| Chicony HD WebCam                                   | 8         | 2.16%   |
| Sunplus Integrated_Webcam_HD                        | 7         | 1.89%   |
| Logitech HD Pro Webcam C920                         | 7         | 1.89%   |
| Bison Integrated Camera                             | 7         | 1.89%   |
| Microdia Integrated_Webcam_HD                       | 6         | 1.62%   |
| Bison HD Webcam                                     | 6         | 1.62%   |
| Apple FaceTime HD Camera (Built-in)                 | 6         | 1.62%   |
| Microdia USB Camera                                 | 5         | 1.35%   |
| Logitech Webcam C270                                | 5         | 1.35%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 5         | 1.35%   |
| Sonix USB2.0 HD UVC WebCam                          | 4         | 1.08%   |
| Samsung Galaxy series, misc. (MTP mode)             | 4         | 1.08%   |
| Quanta HD User Facing                               | 4         | 1.08%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 4         | 1.08%   |
| Chicony HP TrueVision HD                            | 4         | 1.08%   |
| Apple FaceTime HD Camera                            | 4         | 1.08%   |
| Apple Built-in iSight                               | 4         | 1.08%   |
| Sunplus HD WebCam                                   | 3         | 0.81%   |
| Sonix USB2.0 FHD UVC WebCam                         | 3         | 0.81%   |
| Realtek USB Camera                                  | 3         | 0.81%   |
| Quanta VGA WebCam                                   | 3         | 0.81%   |
| Logitech StreamCam                                  | 3         | 0.81%   |
| Lite-On HP HD Webcam                                | 3         | 0.81%   |
| Chicony USB2.0 HD UVC WebCam                        | 3         | 0.81%   |
| Chicony Integrated Camera (1280x720@30)             | 3         | 0.81%   |
| Chicony HD User Facing                              | 3         | 0.81%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 3         | 0.81%   |
| Bison Lenovo Integrated Webcam                      | 3         | 0.81%   |
| ARC International Camera                            | 3         | 0.81%   |
| Syntek EasyCamera                                   | 2         | 0.54%   |
| SunplusIT MTD camera                                | 2         | 0.54%   |
| SunplusIT 720p HD Camera                            | 2         | 0.54%   |
| Sunplus NexiGo N930AF FHD Webcam                    | 2         | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 17        | 33.33%  |
| Synaptics                          | 12        | 23.53%  |
| Shenzhen Goodix Technology         | 9         | 17.65%  |
| Elan Microelectronics              | 7         | 13.73%  |
| Realtek USB2.0 Finger Print Bridge | 3         | 5.88%   |
| Focal-systems.Corp                 | 2         | 3.92%   |
| LighTuning Technology              | 1         | 1.96%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 8         | 15.69%  |
| Shenzhen Goodix  FingerPrint Device                             | 5         | 9.8%    |
| Validity Sensors Synaptics WBDI                                 | 4         | 7.84%   |
| Shenzhen Goodix Fingerprint Reader                              | 4         | 7.84%   |
| Elan ELAN:Fingerprint                                           | 4         | 7.84%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 3         | 5.88%   |
| Elan ELAN:ARM-M4                                                | 3         | 5.88%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 2         | 3.92%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor     | 2         | 3.92%   |
| Synaptics UWP WBDI                                              | 2         | 3.92%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 2         | 3.92%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 2         | 3.92%   |
| Focal-systems.Corp FT9201Fingerprint.                           | 2         | 3.92%   |
| Validity Sensors Swipe Fingerprint Sensor                       | 1         | 1.96%   |
| Synaptics WBDI Device                                           | 1         | 1.96%   |
| Synaptics WBDI                                                  | 1         | 1.96%   |
| Synaptics UWP WBDI Device                                       | 1         | 1.96%   |
| Synaptics  WBDI                                                 | 1         | 1.96%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 1         | 1.96%   |
| Synaptics Fingerprint reader [HP G6]                            | 1         | 1.96%   |
| LighTuning Fingerprint Sensor                                   | 1         | 1.96%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 6         | 46.15%  |
| Alcor Micro           | 5         | 38.46%  |
| Realtek Semiconductor | 1         | 7.69%   |
| Cherry                | 1         | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 38.46%  |
| Broadcom 5880                                                                | 3         | 23.08%  |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 7.69%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 7.69%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 7.69%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 7.69%   |
| Broadcom 58200                                                               | 1         | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 551       | 74.76%  |
| 1     | 159       | 21.57%  |
| 2     | 24        | 3.26%   |
| 3     | 3         | 0.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 54        | 25.35%  |
| Net/wireless             | 52        | 24.41%  |
| Fingerprint reader       | 50        | 23.47%  |
| Multimedia controller    | 35        | 16.43%  |
| Unassigned class         | 5         | 2.35%   |
| Sound                    | 3         | 1.41%   |
| Bluetooth                | 3         | 1.41%   |
| Net/ethernet             | 2         | 0.94%   |
| Communication controller | 2         | 0.94%   |
| Card reader              | 2         | 0.94%   |
| Camera                   | 2         | 0.94%   |
| Storage/nvme             | 1         | 0.47%   |
| Modem                    | 1         | 0.47%   |
| Chipcard                 | 1         | 0.47%   |


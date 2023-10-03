Linux in Croatia - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Croatia.

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

Total: 492

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 5570               | [7975260826](https://linux-hardware.org/?probe=7975260826) | Sep 29, 2023 |
| Dell          | Latitude 5431               | [d9ea685862](https://linux-hardware.org/?probe=d9ea685862) | Sep 27, 2023 |
| Dell          | Vostro 3500                 | [fac9ee2e6e](https://linux-hardware.org/?probe=fac9ee2e6e) | Sep 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [0e32901b18](https://linux-hardware.org/?probe=0e32901b18) | Sep 27, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [c8ee0a00a5](https://linux-hardware.org/?probe=c8ee0a00a5) | Sep 06, 2023 |
| Apple         | MacBookPro11,4              | [c833e40c97](https://linux-hardware.org/?probe=c833e40c97) | Sep 01, 2023 |
| Acer          | Predator PH517-51           | [294343383a](https://linux-hardware.org/?probe=294343383a) | Aug 30, 2023 |
| Acer          | Predator PH517-51           | [adba295596](https://linux-hardware.org/?probe=adba295596) | Aug 30, 2023 |
| Acer          | Nitro AN515-44              | [caaf599d6a](https://linux-hardware.org/?probe=caaf599d6a) | Aug 29, 2023 |
| Acer          | Nitro AN515-44              | [f91274084a](https://linux-hardware.org/?probe=f91274084a) | Aug 29, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [4bc3ed94ce](https://linux-hardware.org/?probe=4bc3ed94ce) | Aug 28, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [8acc158836](https://linux-hardware.org/?probe=8acc158836) | Aug 27, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [1f6e4f9676](https://linux-hardware.org/?probe=1f6e4f9676) | Aug 21, 2023 |
| Lenovo        | ThinkPad T495s 20QJ001MG... | [3ac30cf2d0](https://linux-hardware.org/?probe=3ac30cf2d0) | Aug 16, 2023 |
| HP            | EliteBook 840 14 inch G1... | [73b7fc1fc9](https://linux-hardware.org/?probe=73b7fc1fc9) | Aug 11, 2023 |
| Acer          | Aspire 5736Z                | [de1addc70b](https://linux-hardware.org/?probe=de1addc70b) | Aug 03, 2023 |
| ASUSTek       | X540NA                      | [c7724d9c7c](https://linux-hardware.org/?probe=c7724d9c7c) | Aug 02, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | [8b7ca3c460](https://linux-hardware.org/?probe=8b7ca3c460) | Jul 21, 2023 |
| Dell          | Latitude 5520               | [070380568b](https://linux-hardware.org/?probe=070380568b) | Jul 21, 2023 |
| Dell          | Inspiron 3542               | [043258de54](https://linux-hardware.org/?probe=043258de54) | Jul 17, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [567736ec02](https://linux-hardware.org/?probe=567736ec02) | Jul 14, 2023 |
| Acer          | Swift SF314-58G             | [795625662c](https://linux-hardware.org/?probe=795625662c) | Jul 12, 2023 |
| Acer          | Swift SF314-58G             | [c01b74af46](https://linux-hardware.org/?probe=c01b74af46) | Jul 12, 2023 |
| Dell          | OptiPlex 9020               | [3384a64b67](https://linux-hardware.org/?probe=3384a64b67) | Jul 10, 2023 |
| Timi          | TM1701                      | [5dee3c6b81](https://linux-hardware.org/?probe=5dee3c6b81) | Jul 01, 2023 |
| Apple         | MacBookAir5,2               | [8f6d75c75e](https://linux-hardware.org/?probe=8f6d75c75e) | Jun 22, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [c1472b1c25](https://linux-hardware.org/?probe=c1472b1c25) | Jun 18, 2023 |
| Apple         | MacBookAir5,2               | [18e80281cc](https://linux-hardware.org/?probe=18e80281cc) | Jun 10, 2023 |
| Apple         | MacBookAir5,2               | [f7bd03dbb9](https://linux-hardware.org/?probe=f7bd03dbb9) | Jun 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [bf403bb6d8](https://linux-hardware.org/?probe=bf403bb6d8) | Jun 06, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [2667cb67a3](https://linux-hardware.org/?probe=2667cb67a3) | May 30, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [0568aa067a](https://linux-hardware.org/?probe=0568aa067a) | May 30, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [c8e0efc288](https://linux-hardware.org/?probe=c8e0efc288) | May 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [da399dc7cc](https://linux-hardware.org/?probe=da399dc7cc) | May 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [72f5c85f7f](https://linux-hardware.org/?probe=72f5c85f7f) | May 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [913f21a49c](https://linux-hardware.org/?probe=913f21a49c) | May 25, 2023 |
| Acer          | Aspire A515-57              | [3272ba5e49](https://linux-hardware.org/?probe=3272ba5e49) | May 19, 2023 |
| Tactus        | GeoBook 140                 | [534c32884a](https://linux-hardware.org/?probe=534c32884a) | May 19, 2023 |
| Schenker      | VISION (E22)                | [582ac3cbf5](https://linux-hardware.org/?probe=582ac3cbf5) | May 13, 2023 |
| Acer          | Aspire E5-553G              | [cd65f81693](https://linux-hardware.org/?probe=cd65f81693) | May 11, 2023 |
| Acer          | Aspire A315-23              | [2c96614c16](https://linux-hardware.org/?probe=2c96614c16) | May 11, 2023 |
| Acer          | Aspire E5-553G              | [5312325c90](https://linux-hardware.org/?probe=5312325c90) | May 10, 2023 |
| Lenovo        | ThinkPad T530 2394CE2       | [d232fefed2](https://linux-hardware.org/?probe=d232fefed2) | May 09, 2023 |
| Acer          | Predator PH315-53           | [efb597952f](https://linux-hardware.org/?probe=efb597952f) | May 07, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [1c98821416](https://linux-hardware.org/?probe=1c98821416) | May 03, 2023 |
| Acer          | TravelMate 5730             | [e74d115d0d](https://linux-hardware.org/?probe=e74d115d0d) | Apr 29, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [5cb9fe1ae9](https://linux-hardware.org/?probe=5cb9fe1ae9) | Apr 28, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [3669ef1de9](https://linux-hardware.org/?probe=3669ef1de9) | Apr 28, 2023 |
| Lenovo        | 3000 N200 0769A97           | [a293f4f1f7](https://linux-hardware.org/?probe=a293f4f1f7) | Apr 26, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [0db2c54b2a](https://linux-hardware.org/?probe=0db2c54b2a) | Apr 24, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [b3c9b78fec](https://linux-hardware.org/?probe=b3c9b78fec) | Apr 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [bba5f185af](https://linux-hardware.org/?probe=bba5f185af) | Apr 13, 2023 |
| Lenovo        | ThinkPad T530 2394BF7       | [5161d2f521](https://linux-hardware.org/?probe=5161d2f521) | Apr 11, 2023 |
| Acer          | Nitro AN515-55              | [64f96c6fde](https://linux-hardware.org/?probe=64f96c6fde) | Apr 07, 2023 |
| Lenovo        | V15-ADA 82C7                | [917714b1be](https://linux-hardware.org/?probe=917714b1be) | Apr 06, 2023 |
| Lenovo        | V15-ADA 82C7                | [ad148ede52](https://linux-hardware.org/?probe=ad148ede52) | Apr 06, 2023 |
| Dell          | Latitude 5530               | [802248e232](https://linux-hardware.org/?probe=802248e232) | Apr 03, 2023 |
| Dell          | Latitude 5530               | [e4688e2ef8](https://linux-hardware.org/?probe=e4688e2ef8) | Apr 01, 2023 |
| ASUSTek       | N551JM                      | [b8e3d627b5](https://linux-hardware.org/?probe=b8e3d627b5) | Mar 27, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505     | [2b0f3e8867](https://linux-hardware.org/?probe=2b0f3e8867) | Mar 25, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505     | [8bb2484825](https://linux-hardware.org/?probe=8bb2484825) | Mar 25, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [4c7add7cd1](https://linux-hardware.org/?probe=4c7add7cd1) | Mar 21, 2023 |
| Tactus        | GeoBook 140                 | [5efd6f0674](https://linux-hardware.org/?probe=5efd6f0674) | Mar 20, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [55dc5e3ef4](https://linux-hardware.org/?probe=55dc5e3ef4) | Mar 19, 2023 |
| HP            | EliteBook 8730w             | [a012fe4bd2](https://linux-hardware.org/?probe=a012fe4bd2) | Mar 10, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b349a8eedd](https://linux-hardware.org/?probe=b349a8eedd) | Mar 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [314cad4a2f](https://linux-hardware.org/?probe=314cad4a2f) | Mar 07, 2023 |
| Dell          | OptiPlex 9020               | [dda13d9c8e](https://linux-hardware.org/?probe=dda13d9c8e) | Mar 05, 2023 |
| HP            | EliteBook 840 G5            | [8e02418ca7](https://linux-hardware.org/?probe=8e02418ca7) | Mar 05, 2023 |
| HP            | EliteBook 840 G5            | [5510fed545](https://linux-hardware.org/?probe=5510fed545) | Mar 04, 2023 |
| Acer          | Swift SF314-43              | [4f2c05c854](https://linux-hardware.org/?probe=4f2c05c854) | Feb 28, 2023 |
| Valve         | Jupiter                     | [e2f06dcb4a](https://linux-hardware.org/?probe=e2f06dcb4a) | Feb 24, 2023 |
| Dell          | System XPS L702X            | [81f9738975](https://linux-hardware.org/?probe=81f9738975) | Feb 16, 2023 |
| Unknown       | Apple MacBook Pro (13-in... | [1d5a0bc43f](https://linux-hardware.org/?probe=1d5a0bc43f) | Feb 14, 2023 |
| Lenovo        | ThinkPad T540p 20BFA183A... | [2705e3d0c5](https://linux-hardware.org/?probe=2705e3d0c5) | Feb 12, 2023 |
| Acer          | Nitro AN515-55              | [b4b0bee06c](https://linux-hardware.org/?probe=b4b0bee06c) | Feb 08, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [9f76193ccc](https://linux-hardware.org/?probe=9f76193ccc) | Jan 29, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | [34882391f3](https://linux-hardware.org/?probe=34882391f3) | Jan 25, 2023 |
| HP            | Laptop 15-bs1xx             | [76689345ef](https://linux-hardware.org/?probe=76689345ef) | Jan 19, 2023 |
| Toshiba       | Satellite P200              | [478f5dc5cb](https://linux-hardware.org/?probe=478f5dc5cb) | Jan 18, 2023 |
| HP            | Laptop 15s-eq2xxx           | [29ff669f2c](https://linux-hardware.org/?probe=29ff669f2c) | Jan 14, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ef10fbe492](https://linux-hardware.org/?probe=ef10fbe492) | Jan 09, 2023 |
| Dell          | Inspiron 15-3567            | [5aaaf24b85](https://linux-hardware.org/?probe=5aaaf24b85) | Jan 09, 2023 |
| Samsung       | SBB-DA                      | [a4c6b4f454](https://linux-hardware.org/?probe=a4c6b4f454) | Jan 07, 2023 |
| Acer          | Nitro AN515-55              | [800f20e309](https://linux-hardware.org/?probe=800f20e309) | Jan 07, 2023 |
| ASUSTek       | N551JM                      | [f6de50a76b](https://linux-hardware.org/?probe=f6de50a76b) | Jan 04, 2023 |
| HP            | OMEN by Laptop              | [e703dd0215](https://linux-hardware.org/?probe=e703dd0215) | Jan 04, 2023 |
| ASUSTek       | N551JM                      | [3ba1d0e689](https://linux-hardware.org/?probe=3ba1d0e689) | Jan 03, 2023 |
| Acer          | Aspire A715-41G             | [92f3c92191](https://linux-hardware.org/?probe=92f3c92191) | Dec 29, 2022 |
| Acer          | Swift SF314-41              | [2923c4c0fc](https://linux-hardware.org/?probe=2923c4c0fc) | Dec 28, 2022 |
| Dell          | Inspiron N5110              | [9b8756cdd0](https://linux-hardware.org/?probe=9b8756cdd0) | Dec 17, 2022 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | [b2b93008c3](https://linux-hardware.org/?probe=b2b93008c3) | Dec 17, 2022 |
| HP            | Laptop 15-db1xxx            | [3dcbd61f9e](https://linux-hardware.org/?probe=3dcbd61f9e) | Dec 12, 2022 |
| Dell          | Inspiron N5110              | [9815b67f0b](https://linux-hardware.org/?probe=9815b67f0b) | Dec 06, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [d632edc927](https://linux-hardware.org/?probe=d632edc927) | Dec 05, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [412bffea3b](https://linux-hardware.org/?probe=412bffea3b) | Dec 05, 2022 |
| ASUSTek       | X550LB                      | [466592b744](https://linux-hardware.org/?probe=466592b744) | Nov 20, 2022 |
| ASUSTek       | X550LB                      | [3ca5ee2f7a](https://linux-hardware.org/?probe=3ca5ee2f7a) | Nov 20, 2022 |
| Apple         | MacBookPro12,1              | [9e16721568](https://linux-hardware.org/?probe=9e16721568) | Nov 17, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [311c90573c](https://linux-hardware.org/?probe=311c90573c) | Nov 12, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [1198a061e1](https://linux-hardware.org/?probe=1198a061e1) | Nov 12, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [de85ac10f6](https://linux-hardware.org/?probe=de85ac10f6) | Nov 09, 2022 |
| ASUSTek       | Zenbook UX5401EA_UX5401E... | [84bf8d9578](https://linux-hardware.org/?probe=84bf8d9578) | Nov 05, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [9b61195a2a](https://linux-hardware.org/?probe=9b61195a2a) | Nov 01, 2022 |
| Dell          | Studio 1735                 | [8f070a2831](https://linux-hardware.org/?probe=8f070a2831) | Oct 30, 2022 |
| Pretech       | EVE 1801 3G ES1049EG        | [24b035a7a4](https://linux-hardware.org/?probe=24b035a7a4) | Oct 25, 2022 |
| Dell          | Studio 1735                 | [21959a7db7](https://linux-hardware.org/?probe=21959a7db7) | Oct 24, 2022 |
| ASUSTek       | K53U                        | [d178c463df](https://linux-hardware.org/?probe=d178c463df) | Oct 24, 2022 |
| Dell          | Studio 1735                 | [4385640990](https://linux-hardware.org/?probe=4385640990) | Oct 23, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [eaecfdf473](https://linux-hardware.org/?probe=eaecfdf473) | Oct 21, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [c044987599](https://linux-hardware.org/?probe=c044987599) | Oct 20, 2022 |
| Acer          | Swift SF314-54              | [04fed978ae](https://linux-hardware.org/?probe=04fed978ae) | Oct 18, 2022 |
| Lenovo        | ThinkPad T470s 20HGS1R90... | [e3eba59f05](https://linux-hardware.org/?probe=e3eba59f05) | Oct 17, 2022 |
| Acer          | Aspire A317-53              | [dadf436fd1](https://linux-hardware.org/?probe=dadf436fd1) | Oct 10, 2022 |
| HP            | EliteBook 8730w             | [e7545a94b2](https://linux-hardware.org/?probe=e7545a94b2) | Oct 09, 2022 |
| HP            | EliteBook 8730w             | [b938a96086](https://linux-hardware.org/?probe=b938a96086) | Oct 09, 2022 |
| Pretech       | EVE 1801 3G ES1049EG        | [3f2cdff8d4](https://linux-hardware.org/?probe=3f2cdff8d4) | Oct 05, 2022 |
| Toshiba       | Encore                      | [a11bf538ec](https://linux-hardware.org/?probe=a11bf538ec) | Oct 05, 2022 |
| ASUSTek       | N56VZ                       | [ce162c52c0](https://linux-hardware.org/?probe=ce162c52c0) | Sep 19, 2022 |
| HP            | EliteBook 8560p             | [4a9e29fab2](https://linux-hardware.org/?probe=4a9e29fab2) | Sep 18, 2022 |
| Lenovo        | Unknown                     | [64dc493d4d](https://linux-hardware.org/?probe=64dc493d4d) | Sep 17, 2022 |
| Lenovo        | Unknown                     | [581356206a](https://linux-hardware.org/?probe=581356206a) | Sep 17, 2022 |
| Dell          | Latitude 5420               | [511ef8a105](https://linux-hardware.org/?probe=511ef8a105) | Sep 08, 2022 |
| Dell          | Latitude 5420               | [48db2c3954](https://linux-hardware.org/?probe=48db2c3954) | Sep 08, 2022 |
| Toshiba       | Satellite P200              | [583489891f](https://linux-hardware.org/?probe=583489891f) | Sep 06, 2022 |
| HP            | Pavilion dv9700             | [9543920c45](https://linux-hardware.org/?probe=9543920c45) | Sep 04, 2022 |
| HP            | Pavilion dv9700             | [b6d4d6bca2](https://linux-hardware.org/?probe=b6d4d6bca2) | Sep 04, 2022 |
| Acer          | Swift SF314-41              | [1394aca8b2](https://linux-hardware.org/?probe=1394aca8b2) | Sep 03, 2022 |
| HP            | Pavilion Notebook           | [0e4eab04c0](https://linux-hardware.org/?probe=0e4eab04c0) | Aug 27, 2022 |
| HP            | Pavilion Notebook           | [65e832cb2f](https://linux-hardware.org/?probe=65e832cb2f) | Aug 27, 2022 |
| Dell          | Latitude 5290 2-in-1        | [bafc4d3392](https://linux-hardware.org/?probe=bafc4d3392) | Aug 20, 2022 |
| Dell          | Latitude E7240              | [1f20b0f54b](https://linux-hardware.org/?probe=1f20b0f54b) | Aug 08, 2022 |
| Acer          | Aspire A515-56G             | [3df2b6b19b](https://linux-hardware.org/?probe=3df2b6b19b) | Aug 05, 2022 |
| ASUSTek       | S551LB                      | [8660a06086](https://linux-hardware.org/?probe=8660a06086) | Jul 27, 2022 |
| Lenovo        | ThinkPad T580 20LAS27000    | [a78a8e806f](https://linux-hardware.org/?probe=a78a8e806f) | Jul 21, 2022 |
| Dell          | XPS 15 9500                 | [6886cd26f5](https://linux-hardware.org/?probe=6886cd26f5) | Jul 20, 2022 |
| HP            | 250 G8 Notebook PC          | [17cdd0291e](https://linux-hardware.org/?probe=17cdd0291e) | Jul 12, 2022 |
| Lenovo        | G50-30 80G0                 | [4de601fe45](https://linux-hardware.org/?probe=4de601fe45) | Jul 12, 2022 |
| ASUSTek       | X75A1                       | [4bd18943fb](https://linux-hardware.org/?probe=4bd18943fb) | Jul 09, 2022 |
| ASUSTek       | X75A1                       | [3da162d001](https://linux-hardware.org/?probe=3da162d001) | Jul 09, 2022 |
| Dell          | Inspiron 3537               | [36305f7936](https://linux-hardware.org/?probe=36305f7936) | Jul 09, 2022 |
| Lenovo        | ThinkPad T480s 20L8S2330... | [4718003bb5](https://linux-hardware.org/?probe=4718003bb5) | Jul 09, 2022 |
| Lenovo        | Z50-70 20354                | [6d9101e2d2](https://linux-hardware.org/?probe=6d9101e2d2) | Jul 08, 2022 |
| Dell          | XPS 15 9500                 | [36c7cff92d](https://linux-hardware.org/?probe=36c7cff92d) | Jul 07, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [445bedc2c9](https://linux-hardware.org/?probe=445bedc2c9) | Jul 06, 2022 |
| Dell          | Inspiron 3537               | [bfe2aed3aa](https://linux-hardware.org/?probe=bfe2aed3aa) | Jul 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [4d4cd5bae0](https://linux-hardware.org/?probe=4d4cd5bae0) | Jul 05, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [82ca4386ae](https://linux-hardware.org/?probe=82ca4386ae) | Jun 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [42462e221b](https://linux-hardware.org/?probe=42462e221b) | Jun 29, 2022 |
| Chuwi         | GemiBook Pro                | [160062e69a](https://linux-hardware.org/?probe=160062e69a) | Jun 25, 2022 |
| Gigabyte      | G5 KC                       | [5ef620811f](https://linux-hardware.org/?probe=5ef620811f) | Jun 25, 2022 |
| Acer          | Aspire A315-23              | [45c9b081c5](https://linux-hardware.org/?probe=45c9b081c5) | Jun 24, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [96c4f21509](https://linux-hardware.org/?probe=96c4f21509) | Jun 21, 2022 |
| Acer          | Aspire E5-771G              | [dac3ae2eba](https://linux-hardware.org/?probe=dac3ae2eba) | Jun 21, 2022 |
| Chuwi         | GemiBook Pro                | [ba5ab976e2](https://linux-hardware.org/?probe=ba5ab976e2) | Jun 16, 2022 |
| Chuwi         | GemiBook Pro                | [d2b608c230](https://linux-hardware.org/?probe=d2b608c230) | Jun 16, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [1f92039342](https://linux-hardware.org/?probe=1f92039342) | Jun 02, 2022 |
| Dell          | Vostro 3500                 | [9dff398fa9](https://linux-hardware.org/?probe=9dff398fa9) | May 24, 2022 |
| Lenovo        | G40-30 80FY                 | [4280810a31](https://linux-hardware.org/?probe=4280810a31) | May 20, 2022 |
| eMachines     | E525                        | [2c397d4229](https://linux-hardware.org/?probe=2c397d4229) | May 19, 2022 |
| eMachines     | E525                        | [7a1e439150](https://linux-hardware.org/?probe=7a1e439150) | May 19, 2022 |
| HP            | ProBook 470 G1              | [cb4ef48c3d](https://linux-hardware.org/?probe=cb4ef48c3d) | May 10, 2022 |
| HP            | ProBook 470 G1              | [a20a5df1ad](https://linux-hardware.org/?probe=a20a5df1ad) | May 06, 2022 |
| Lenovo        | G50-30 80G0                 | [3d1c0ef2f0](https://linux-hardware.org/?probe=3d1c0ef2f0) | May 05, 2022 |
| HP            | Laptop 15-dw0xxx            | [8d561055ba](https://linux-hardware.org/?probe=8d561055ba) | May 04, 2022 |
| HP            | Pavilion 17                 | [3958b61eff](https://linux-hardware.org/?probe=3958b61eff) | May 02, 2022 |
| ASUSTek       | X540UA                      | [af0ed39935](https://linux-hardware.org/?probe=af0ed39935) | May 01, 2022 |
| Lenovo        | G50-30 80G0                 | [bc333fe437](https://linux-hardware.org/?probe=bc333fe437) | Apr 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [67d1865b69](https://linux-hardware.org/?probe=67d1865b69) | Apr 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [57a8a5bfcd](https://linux-hardware.org/?probe=57a8a5bfcd) | Apr 30, 2022 |
| HP            | Pavilion 17                 | [6de5e5677f](https://linux-hardware.org/?probe=6de5e5677f) | Apr 29, 2022 |
| Razer         | Blade                       | [c5ef4943c4](https://linux-hardware.org/?probe=c5ef4943c4) | Apr 27, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2US0... | [1a7a85a6ca](https://linux-hardware.org/?probe=1a7a85a6ca) | Apr 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [84978cfba3](https://linux-hardware.org/?probe=84978cfba3) | Apr 17, 2022 |
| Acer          | Swift SF114-32              | [e970f67c93](https://linux-hardware.org/?probe=e970f67c93) | Apr 13, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [bae30f6939](https://linux-hardware.org/?probe=bae30f6939) | Apr 11, 2022 |
| Dell          | OptiPlex 9020               | [6d0445b848](https://linux-hardware.org/?probe=6d0445b848) | Apr 09, 2022 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | [d7d4ac2b9a](https://linux-hardware.org/?probe=d7d4ac2b9a) | Apr 04, 2022 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | [f9ab989993](https://linux-hardware.org/?probe=f9ab989993) | Apr 02, 2022 |
| Acer          | Swift SF314-43              | [752a6415ff](https://linux-hardware.org/?probe=752a6415ff) | Apr 02, 2022 |
| ASUSTek       | X71Sr                       | [0e6ffbc190](https://linux-hardware.org/?probe=0e6ffbc190) | Apr 01, 2022 |
| eMachines     | E725 V1.03                  | [12ea923e2b](https://linux-hardware.org/?probe=12ea923e2b) | Mar 18, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [8a6bb86ea0](https://linux-hardware.org/?probe=8a6bb86ea0) | Mar 17, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [271852ad10](https://linux-hardware.org/?probe=271852ad10) | Mar 17, 2022 |
| Acer          | Swift SF314-43              | [6415b33b34](https://linux-hardware.org/?probe=6415b33b34) | Mar 17, 2022 |
| ASUSTek       | G75VX                       | [2b94fd73ea](https://linux-hardware.org/?probe=2b94fd73ea) | Mar 14, 2022 |
| Lenovo        | ThinkPad T410 2522DK2       | [9990e887c2](https://linux-hardware.org/?probe=9990e887c2) | Mar 13, 2022 |
| HP            | ProBook 4530s               | [061de41ec5](https://linux-hardware.org/?probe=061de41ec5) | Mar 13, 2022 |
| Toshiba       | Satellite C850-1GD          | [79b2741217](https://linux-hardware.org/?probe=79b2741217) | Mar 12, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [6ba21bc191](https://linux-hardware.org/?probe=6ba21bc191) | Mar 05, 2022 |
| Apple         | MacBookAir7,2               | [34da56b567](https://linux-hardware.org/?probe=34da56b567) | Mar 01, 2022 |
| Acer          | Aspire A515-51G             | [28a9d8d6a4](https://linux-hardware.org/?probe=28a9d8d6a4) | Feb 25, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [a93fdb0cc8](https://linux-hardware.org/?probe=a93fdb0cc8) | Feb 25, 2022 |
| Chuwi         | GemiBook Pro                | [37c0889ae6](https://linux-hardware.org/?probe=37c0889ae6) | Feb 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [57a0f33a96](https://linux-hardware.org/?probe=57a0f33a96) | Feb 23, 2022 |
| HP            | 2140                        | [ad18e8d0b3](https://linux-hardware.org/?probe=ad18e8d0b3) | Feb 22, 2022 |
| HP            | 2140                        | [e0757f087f](https://linux-hardware.org/?probe=e0757f087f) | Feb 22, 2022 |
| eMachines     | E725 V1.03                  | [0f12be73fa](https://linux-hardware.org/?probe=0f12be73fa) | Feb 21, 2022 |
| Apple         | MacBookAir5,2               | [dc8f1e8a38](https://linux-hardware.org/?probe=dc8f1e8a38) | Feb 20, 2022 |
| Acer          | Aspire E1-532G              | [2ec2b8bf53](https://linux-hardware.org/?probe=2ec2b8bf53) | Feb 20, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [7f55b1fa12](https://linux-hardware.org/?probe=7f55b1fa12) | Feb 17, 2022 |
| Dell          | XPS 13 9310                 | [64cfd66662](https://linux-hardware.org/?probe=64cfd66662) | Feb 11, 2022 |
| Acer          | Aspire 7739G                | [f8150dd53e](https://linux-hardware.org/?probe=f8150dd53e) | Feb 10, 2022 |
| Apple         | MacBookPro11,4              | [c843bc46b3](https://linux-hardware.org/?probe=c843bc46b3) | Feb 07, 2022 |
| HP            | ZBook 17 G2                 | [4210faf0d2](https://linux-hardware.org/?probe=4210faf0d2) | Jan 29, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [5310be8910](https://linux-hardware.org/?probe=5310be8910) | Jan 23, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [4c77e8f334](https://linux-hardware.org/?probe=4c77e8f334) | Jan 23, 2022 |
| Acer          | Aspire F5-573G              | [cb60b63849](https://linux-hardware.org/?probe=cb60b63849) | Jan 23, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [4b3b067330](https://linux-hardware.org/?probe=4b3b067330) | Jan 21, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | [45b3c5b85a](https://linux-hardware.org/?probe=45b3c5b85a) | Jan 16, 2022 |
| Acer          | Aspire A315-21              | [91548d30f5](https://linux-hardware.org/?probe=91548d30f5) | Jan 06, 2022 |
| HP            | EliteBook 2170p             | [4598e643d1](https://linux-hardware.org/?probe=4598e643d1) | Jan 05, 2022 |
| Lenovo        | ThinkPad E580 20KS005ASC    | [0a37cdb124](https://linux-hardware.org/?probe=0a37cdb124) | Jan 02, 2022 |
| Lenovo        | B590 20208                  | [967a9b3a38](https://linux-hardware.org/?probe=967a9b3a38) | Dec 27, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [d9c0087822](https://linux-hardware.org/?probe=d9c0087822) | Dec 26, 2021 |
| Apple         | MacBookAir3,2               | [9f3a7c27d9](https://linux-hardware.org/?probe=9f3a7c27d9) | Dec 24, 2021 |
| Acer          | Aspire 5250                 | [b4a48e5350](https://linux-hardware.org/?probe=b4a48e5350) | Dec 15, 2021 |
| Dell          | XPS 13 9310                 | [86eb1ce765](https://linux-hardware.org/?probe=86eb1ce765) | Dec 15, 2021 |
| Acer          | Aspire A515-55              | [f258cd6bb3](https://linux-hardware.org/?probe=f258cd6bb3) | Dec 12, 2021 |
| Acer          | Aspire A314-22              | [655c34690e](https://linux-hardware.org/?probe=655c34690e) | Dec 12, 2021 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [eb77365d4e](https://linux-hardware.org/?probe=eb77365d4e) | Dec 11, 2021 |
| Lenovo        | IdeaPad 510S-13IKB 80V0     | [fe88e1083a](https://linux-hardware.org/?probe=fe88e1083a) | Dec 11, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [dac924cd16](https://linux-hardware.org/?probe=dac924cd16) | Dec 04, 2021 |
| Acer          | Aspire E1-522               | [3111a073e8](https://linux-hardware.org/?probe=3111a073e8) | Dec 03, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [422733b9df](https://linux-hardware.org/?probe=422733b9df) | Dec 02, 2021 |
| Lenovo        | B50-70 20384                | [d75361564f](https://linux-hardware.org/?probe=d75361564f) | Dec 02, 2021 |
| Lenovo        | ThinkPad T450s 20BWS2US0... | [0e099c0bdd](https://linux-hardware.org/?probe=0e099c0bdd) | Dec 02, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1HK0... | [416712d76f](https://linux-hardware.org/?probe=416712d76f) | Nov 30, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1HK0... | [c4e34dbb1c](https://linux-hardware.org/?probe=c4e34dbb1c) | Nov 30, 2021 |
| Dell          | XPS 13 9310                 | [ec7596ddfa](https://linux-hardware.org/?probe=ec7596ddfa) | Nov 26, 2021 |
| Acer          | Aspire 6930G                | [323825e995](https://linux-hardware.org/?probe=323825e995) | Nov 24, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [659ed4999d](https://linux-hardware.org/?probe=659ed4999d) | Nov 24, 2021 |
| Dell          | Vostro 3500                 | [b0b04002be](https://linux-hardware.org/?probe=b0b04002be) | Nov 24, 2021 |
| HP            | EliteBook 2530p             | [08f1548a45](https://linux-hardware.org/?probe=08f1548a45) | Nov 23, 2021 |
| Dell          | Vostro 5568                 | [515899572d](https://linux-hardware.org/?probe=515899572d) | Nov 22, 2021 |
| Dell          | Vostro 5568                 | [9ae3647f81](https://linux-hardware.org/?probe=9ae3647f81) | Nov 22, 2021 |
| Dell          | Inspiron 5570               | [bde1fd1da2](https://linux-hardware.org/?probe=bde1fd1da2) | Nov 20, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [8a1a3f0661](https://linux-hardware.org/?probe=8a1a3f0661) | Nov 20, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [eace5e1302](https://linux-hardware.org/?probe=eace5e1302) | Nov 19, 2021 |
| Dell          | Inspiron 5570               | [9c7eba9b77](https://linux-hardware.org/?probe=9c7eba9b77) | Nov 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [3a3f503917](https://linux-hardware.org/?probe=3a3f503917) | Nov 14, 2021 |
| HP            | Pavilion Laptop 14-bf1xx    | [93e710085b](https://linux-hardware.org/?probe=93e710085b) | Nov 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [aa49529b6c](https://linux-hardware.org/?probe=aa49529b6c) | Nov 09, 2021 |
| Lenovo        | Legion 5 17ACH6 82K0        | [3af4c85553](https://linux-hardware.org/?probe=3af4c85553) | Nov 04, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [df4871ce19](https://linux-hardware.org/?probe=df4871ce19) | Nov 04, 2021 |
| ASUSTek       | X751NV                      | [ecf08805fe](https://linux-hardware.org/?probe=ecf08805fe) | Nov 03, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [c7f7df5e24](https://linux-hardware.org/?probe=c7f7df5e24) | Nov 01, 2021 |
| Dell          | Inspiron N5110              | [532a1d3d01](https://linux-hardware.org/?probe=532a1d3d01) | Oct 29, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [2d80988ddc](https://linux-hardware.org/?probe=2d80988ddc) | Oct 22, 2021 |
| SHENZHEN X... | ST106                       | [afbb6f50c8](https://linux-hardware.org/?probe=afbb6f50c8) | Oct 11, 2021 |
| SHENZHEN X... | ST106                       | [5ca1710273](https://linux-hardware.org/?probe=5ca1710273) | Oct 11, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [e570cc15cd](https://linux-hardware.org/?probe=e570cc15cd) | Oct 06, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [d5199453f5](https://linux-hardware.org/?probe=d5199453f5) | Oct 04, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [068d8ff3b0](https://linux-hardware.org/?probe=068d8ff3b0) | Oct 04, 2021 |
| Toshiba       | Satellite P200              | [df46118ac3](https://linux-hardware.org/?probe=df46118ac3) | Oct 02, 2021 |
| Acer          | Aspire A315-21              | [1b6bb85e6b](https://linux-hardware.org/?probe=1b6bb85e6b) | Sep 30, 2021 |
| Acer          | Aspire A315-21              | [aa5e0ddd18](https://linux-hardware.org/?probe=aa5e0ddd18) | Sep 30, 2021 |
| HP            | ProBook 4740s               | [77b2eed991](https://linux-hardware.org/?probe=77b2eed991) | Sep 22, 2021 |
| Acer          | Aspire 5250                 | [be1b633020](https://linux-hardware.org/?probe=be1b633020) | Sep 14, 2021 |
| HUAWEI        | WRTB-WXX9                   | [1570fd5033](https://linux-hardware.org/?probe=1570fd5033) | Sep 09, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [104bd9a2a0](https://linux-hardware.org/?probe=104bd9a2a0) | Sep 09, 2021 |
| Lenovo        | ThinkPad E590 20NB006MSC    | [73c87242b9](https://linux-hardware.org/?probe=73c87242b9) | Sep 09, 2021 |
| HP            | OMEN by Laptop              | [aa6b5ca915](https://linux-hardware.org/?probe=aa6b5ca915) | Sep 08, 2021 |
| HP            | OMEN by Laptop              | [8b503ffd8a](https://linux-hardware.org/?probe=8b503ffd8a) | Sep 07, 2021 |
| Dell          | Latitude 5580               | [944d9e820d](https://linux-hardware.org/?probe=944d9e820d) | Sep 01, 2021 |
| Acer          | Aspire F5-571G              | [d3d0e83199](https://linux-hardware.org/?probe=d3d0e83199) | Aug 30, 2021 |
| Lenovo        | IdeaPad 110-17IKB 80VK      | [44e5a5c02e](https://linux-hardware.org/?probe=44e5a5c02e) | Aug 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [06981db89b](https://linux-hardware.org/?probe=06981db89b) | Aug 20, 2021 |
| Acer          | Aspire A315-34              | [a33d74d8e4](https://linux-hardware.org/?probe=a33d74d8e4) | Aug 19, 2021 |
| Acer          | Aspire A315-34              | [19982a455b](https://linux-hardware.org/?probe=19982a455b) | Aug 18, 2021 |
| Acer          | Aspire E5-575G              | [3c4fba3670](https://linux-hardware.org/?probe=3c4fba3670) | Aug 15, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [f9bd04ed57](https://linux-hardware.org/?probe=f9bd04ed57) | Aug 14, 2021 |
| HP            | 2000                        | [73e2b73533](https://linux-hardware.org/?probe=73e2b73533) | Aug 09, 2021 |
| HP            | EliteBook 850 G8 Noteboo... | [a319e4cbd9](https://linux-hardware.org/?probe=a319e4cbd9) | Aug 06, 2021 |
| Acer          | Nitro AN515-52              | [7d693f5628](https://linux-hardware.org/?probe=7d693f5628) | Aug 04, 2021 |
| Acer          | Nitro AN515-52              | [75944f340e](https://linux-hardware.org/?probe=75944f340e) | Aug 04, 2021 |
| Lenovo        | ThinkPad T430 2349AK2       | [c51aebd74f](https://linux-hardware.org/?probe=c51aebd74f) | Aug 04, 2021 |
| Dell          | Inspiron N5110              | [0283581712](https://linux-hardware.org/?probe=0283581712) | Jul 31, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [8297a49138](https://linux-hardware.org/?probe=8297a49138) | Jul 28, 2021 |
| Acer          | Aspire E5-774G              | [f60a7a3f63](https://linux-hardware.org/?probe=f60a7a3f63) | Jul 28, 2021 |
| HP            | Laptop 15s-eq2xxx           | [4759f3249f](https://linux-hardware.org/?probe=4759f3249f) | Jul 28, 2021 |
| Lenovo        | ThinkPad X260 20F5S0JF00    | [98cbf345d9](https://linux-hardware.org/?probe=98cbf345d9) | Jul 25, 2021 |
| HP            | 2000                        | [0187fe7c8a](https://linux-hardware.org/?probe=0187fe7c8a) | Jul 25, 2021 |
| ASUSTek       | X540SAA                     | [34bb1d000b](https://linux-hardware.org/?probe=34bb1d000b) | Jul 24, 2021 |
| Lenovo        | Z50-70 20354                | [66ea173cb5](https://linux-hardware.org/?probe=66ea173cb5) | Jul 21, 2021 |
| Acer          | Aspire 6930G                | [45694711ff](https://linux-hardware.org/?probe=45694711ff) | Jul 20, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [1cd948b8e0](https://linux-hardware.org/?probe=1cd948b8e0) | Jul 19, 2021 |
| Acer          | Aspire 6930G                | [0e4d09c44c](https://linux-hardware.org/?probe=0e4d09c44c) | Jul 15, 2021 |
| Acer          | Aspire E5-571G              | [6c3da4947f](https://linux-hardware.org/?probe=6c3da4947f) | Jul 02, 2021 |
| Acer          | Aspire E5-571G              | [5497b79433](https://linux-hardware.org/?probe=5497b79433) | Jul 02, 2021 |
| HP            | EliteBook 830 G5            | [e43bc569f4](https://linux-hardware.org/?probe=e43bc569f4) | Jul 01, 2021 |
| Acer          | Aspire A315-34              | [2e6400b3fb](https://linux-hardware.org/?probe=2e6400b3fb) | Jun 30, 2021 |
| System76      | Oryx Pro                    | [fd3cc0ad52](https://linux-hardware.org/?probe=fd3cc0ad52) | Jun 30, 2021 |
| HP            | EliteBook 850 G6            | [e38bee4588](https://linux-hardware.org/?probe=e38bee4588) | Jun 24, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [b6ea706618](https://linux-hardware.org/?probe=b6ea706618) | Jun 22, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [0c5f910d8b](https://linux-hardware.org/?probe=0c5f910d8b) | Jun 21, 2021 |
| HP            | 255 G7 Notebook PC          | [79627ead32](https://linux-hardware.org/?probe=79627ead32) | Jun 14, 2021 |
| Lenovo        | ThinkPad E580 20KS005ASC    | [5b707f47c0](https://linux-hardware.org/?probe=5b707f47c0) | Jun 11, 2021 |
| Lenovo        | G40-30 80FY                 | [b2fe748178](https://linux-hardware.org/?probe=b2fe748178) | Jun 08, 2021 |
| Toshiba       | Satellite L750              | [e0c6618369](https://linux-hardware.org/?probe=e0c6618369) | Jun 07, 2021 |
| Lenovo        | ThinkPad P53 20QNZ4RBUS     | [3f5925d0f5](https://linux-hardware.org/?probe=3f5925d0f5) | Jun 07, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [7d816dafe7](https://linux-hardware.org/?probe=7d816dafe7) | Jun 01, 2021 |
| Lenovo        | ThinkPad P1 20MES1T700      | [be5bc5605b](https://linux-hardware.org/?probe=be5bc5605b) | Jun 01, 2021 |
| Lenovo        | G40-30 80FY                 | [eb9aaa55ea](https://linux-hardware.org/?probe=eb9aaa55ea) | May 30, 2021 |
| Lenovo        | V340-17IWL 81RG             | [2ec41d1cf8](https://linux-hardware.org/?probe=2ec41d1cf8) | May 26, 2021 |
| Lenovo        | G40-30 80FY                 | [0c3e0e8293](https://linux-hardware.org/?probe=0c3e0e8293) | May 26, 2021 |
| HP            | 255 G7 Notebook PC          | [bfb71f53ec](https://linux-hardware.org/?probe=bfb71f53ec) | May 03, 2021 |
| Acer          | Aspire F5-571G              | [5bb52c52af](https://linux-hardware.org/?probe=5bb52c52af) | Apr 30, 2021 |
| Acer          | Aspire A315-34              | [6ab7b315e3](https://linux-hardware.org/?probe=6ab7b315e3) | Apr 24, 2021 |
| Acer          | Aspire A315-34              | [7e0d6ec835](https://linux-hardware.org/?probe=7e0d6ec835) | Apr 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [470c00d1c5](https://linux-hardware.org/?probe=470c00d1c5) | Apr 23, 2021 |
| Lenovo        | Z50-70 20354                | [fbc2a66e2b](https://linux-hardware.org/?probe=fbc2a66e2b) | Apr 22, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [eabbb41fea](https://linux-hardware.org/?probe=eabbb41fea) | Apr 20, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [86927ce44d](https://linux-hardware.org/?probe=86927ce44d) | Apr 20, 2021 |
| Lenovo        | ThinkPad T490s 20NXCTO1W... | [92fe8bf812](https://linux-hardware.org/?probe=92fe8bf812) | Apr 20, 2021 |
| HP            | Compaq 6710b (KL509AV)      | [735870e390](https://linux-hardware.org/?probe=735870e390) | Apr 16, 2021 |
| HP            | EliteBook 850 G6            | [7dbeb6844a](https://linux-hardware.org/?probe=7dbeb6844a) | Apr 16, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [24cd2670f3](https://linux-hardware.org/?probe=24cd2670f3) | Apr 15, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [60ef5cf4f2](https://linux-hardware.org/?probe=60ef5cf4f2) | Apr 15, 2021 |
| HP            | Compaq 6710b (KL509AV)      | [565cd80547](https://linux-hardware.org/?probe=565cd80547) | Apr 15, 2021 |
| Acer          | Aspire A315-21              | [78550034b4](https://linux-hardware.org/?probe=78550034b4) | Apr 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [43b989fae1](https://linux-hardware.org/?probe=43b989fae1) | Apr 06, 2021 |
| Lenovo        | ThinkPad T460 20FMS0X022    | [02ce254082](https://linux-hardware.org/?probe=02ce254082) | Apr 06, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2d68f9ad7f](https://linux-hardware.org/?probe=2d68f9ad7f) | Mar 31, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [be7b667e75](https://linux-hardware.org/?probe=be7b667e75) | Mar 27, 2021 |
| HP            | ZBook 17 G2                 | [45e4f9d242](https://linux-hardware.org/?probe=45e4f9d242) | Mar 24, 2021 |
| HP            | 250 G7 Notebook PC          | [ba238dbe29](https://linux-hardware.org/?probe=ba238dbe29) | Mar 21, 2021 |
| Dell          | Inspiron 5551               | [3b91b6e49f](https://linux-hardware.org/?probe=3b91b6e49f) | Mar 20, 2021 |
| Acer          | Aspire F5-573G              | [8f0d10afce](https://linux-hardware.org/?probe=8f0d10afce) | Feb 24, 2021 |
| HP            | ProBook 455 G7              | [ffdabc425b](https://linux-hardware.org/?probe=ffdabc425b) | Feb 16, 2021 |
| Dell          | XPS 13 9380                 | [69f9ebe58b](https://linux-hardware.org/?probe=69f9ebe58b) | Feb 11, 2021 |
| Acer          | Aspire ES1-532G             | [f01b666f99](https://linux-hardware.org/?probe=f01b666f99) | Feb 09, 2021 |
| Acer          | Aspire A315-41              | [d0648fe1f7](https://linux-hardware.org/?probe=d0648fe1f7) | Feb 07, 2021 |
| HP            | 250 G5 Notebook PC          | [a541bcd390](https://linux-hardware.org/?probe=a541bcd390) | Feb 02, 2021 |
| ASUSTek       | F5N                         | [5a1b1f9f7a](https://linux-hardware.org/?probe=5a1b1f9f7a) | Jan 26, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [17f2fe84cb](https://linux-hardware.org/?probe=17f2fe84cb) | Jan 14, 2021 |
| Dell          | Latitude E6430              | [939c4dbad4](https://linux-hardware.org/?probe=939c4dbad4) | Jan 10, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [1f95699c20](https://linux-hardware.org/?probe=1f95699c20) | Jan 09, 2021 |
| Lenovo        | ThinkPad T61 6458AU9        | [5350b0523f](https://linux-hardware.org/?probe=5350b0523f) | Jan 08, 2021 |
| Lenovo        | G710 20252                  | [9b176fb8e5](https://linux-hardware.org/?probe=9b176fb8e5) | Jan 04, 2021 |
| Lenovo        | G710 20252                  | [db68ccb5de](https://linux-hardware.org/?probe=db68ccb5de) | Jan 04, 2021 |
| Dell          | Vostro 3578                 | [a2e6574ba4](https://linux-hardware.org/?probe=a2e6574ba4) | Dec 30, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [bb46f7172f](https://linux-hardware.org/?probe=bb46f7172f) | Dec 27, 2020 |
| TUXEDO        | Pulse 15 Gen1               | [f6ef9c50ed](https://linux-hardware.org/?probe=f6ef9c50ed) | Dec 23, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [d886327463](https://linux-hardware.org/?probe=d886327463) | Dec 22, 2020 |
| Acer          | Aspire A315-21              | [4c807db430](https://linux-hardware.org/?probe=4c807db430) | Dec 19, 2020 |
| Dell          | Inspiron N5110              | [fb469bd0dc](https://linux-hardware.org/?probe=fb469bd0dc) | Dec 17, 2020 |
| Acer          | Aspire 7739G                | [9d81c58373](https://linux-hardware.org/?probe=9d81c58373) | Dec 12, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [9b07c5b4a5](https://linux-hardware.org/?probe=9b07c5b4a5) | Dec 06, 2020 |
| HP            | EliteBook 8560p             | [3cc104d803](https://linux-hardware.org/?probe=3cc104d803) | Dec 05, 2020 |
| Lenovo        | ThinkPad W540 20BHS04K00    | [c429b95a44](https://linux-hardware.org/?probe=c429b95a44) | Dec 03, 2020 |
| HP            | 2000                        | [27fed77b24](https://linux-hardware.org/?probe=27fed77b24) | Dec 02, 2020 |
| HP            | 255 G7 Notebook PC          | [82adf2d707](https://linux-hardware.org/?probe=82adf2d707) | Dec 01, 2020 |
| Acer          | Aspire ES1-732              | [243f8b5015](https://linux-hardware.org/?probe=243f8b5015) | Nov 29, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [24fe3f5f2f](https://linux-hardware.org/?probe=24fe3f5f2f) | Nov 25, 2020 |
| HP            | ProBook 450 G7              | [49c3ecb298](https://linux-hardware.org/?probe=49c3ecb298) | Nov 24, 2020 |
| Acer          | Aspire ES1-732              | [9a62fb8fe7](https://linux-hardware.org/?probe=9a62fb8fe7) | Nov 21, 2020 |
| HP            | ProBook 640 G1              | [eed4ff0229](https://linux-hardware.org/?probe=eed4ff0229) | Nov 19, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [9c165b5f59](https://linux-hardware.org/?probe=9c165b5f59) | Nov 11, 2020 |
| HUAWEI        | KLVL-WXX9                   | [50ddfd361b](https://linux-hardware.org/?probe=50ddfd361b) | Nov 11, 2020 |
| HUAWEI        | KLVL-WXX9                   | [7e3892e9b1](https://linux-hardware.org/?probe=7e3892e9b1) | Nov 09, 2020 |
| Acer          | Aspire E5-771G              | [9d967e969d](https://linux-hardware.org/?probe=9d967e969d) | Nov 01, 2020 |
| Acer          | Aspire V5-531               | [8eb2cc2336](https://linux-hardware.org/?probe=8eb2cc2336) | Nov 01, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [e6cd5153b1](https://linux-hardware.org/?probe=e6cd5153b1) | Oct 31, 2020 |
| HP            | ProBook 450 G7              | [c3c04c52ab](https://linux-hardware.org/?probe=c3c04c52ab) | Oct 26, 2020 |
| HP            | Laptop 15-bs0xx             | [57db732909](https://linux-hardware.org/?probe=57db732909) | Oct 25, 2020 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [8d0c1b4422](https://linux-hardware.org/?probe=8d0c1b4422) | Oct 22, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [38c87efbca](https://linux-hardware.org/?probe=38c87efbca) | Oct 16, 2020 |
| Dell          | XPS 15 7590                 | [65c065a968](https://linux-hardware.org/?probe=65c065a968) | Oct 09, 2020 |
| HP            | EliteBook 850 G5            | [0d11552658](https://linux-hardware.org/?probe=0d11552658) | Oct 07, 2020 |
| Toshiba       | Satellite C55-A-1M7         | [174d6c4c6d](https://linux-hardware.org/?probe=174d6c4c6d) | Oct 06, 2020 |
| Dell          | Vostro 3578                 | [7904981ea3](https://linux-hardware.org/?probe=7904981ea3) | Oct 05, 2020 |
| Dell          | XPS 15 9570                 | [dacb39a2ba](https://linux-hardware.org/?probe=dacb39a2ba) | Sep 30, 2020 |
| HP            | ProBook 450 G7              | [b4807eff1e](https://linux-hardware.org/?probe=b4807eff1e) | Sep 28, 2020 |
| HP            | ProBook 450 G7              | [9cc971b2e7](https://linux-hardware.org/?probe=9cc971b2e7) | Sep 28, 2020 |
| HP            | 255 G7 Notebook PC          | [062f436dfa](https://linux-hardware.org/?probe=062f436dfa) | Sep 27, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [181e06ec2e](https://linux-hardware.org/?probe=181e06ec2e) | Sep 26, 2020 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [d7391de736](https://linux-hardware.org/?probe=d7391de736) | Sep 21, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [ea8e216968](https://linux-hardware.org/?probe=ea8e216968) | Sep 20, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [d93882e0b2](https://linux-hardware.org/?probe=d93882e0b2) | Sep 20, 2020 |
| HP            | EliteBook 850 G6            | [fa0ec4aeae](https://linux-hardware.org/?probe=fa0ec4aeae) | Sep 17, 2020 |
| HP            | Compaq nc6220 (PY732ES#A... | [eeb54854f8](https://linux-hardware.org/?probe=eeb54854f8) | Sep 12, 2020 |
| HP            | Compaq nc6220 (PY732ES#A... | [a8d6bb1865](https://linux-hardware.org/?probe=a8d6bb1865) | Sep 12, 2020 |
| Dell          | Latitude 7390               | [b8019896d0](https://linux-hardware.org/?probe=b8019896d0) | Sep 10, 2020 |
| HP            | ProBook 430 G3              | [b80f12df10](https://linux-hardware.org/?probe=b80f12df10) | Sep 07, 2020 |
| HP            | EliteBook 850 G6            | [4458c2267f](https://linux-hardware.org/?probe=4458c2267f) | Aug 17, 2020 |
| HP            | ProBook 430 G3              | [e28ccfa01e](https://linux-hardware.org/?probe=e28ccfa01e) | Aug 11, 2020 |
| HP            | 255 G7 Notebook PC          | [9bf9387073](https://linux-hardware.org/?probe=9bf9387073) | Aug 05, 2020 |
| ASUSTek       | GL752VW                     | [26fc584896](https://linux-hardware.org/?probe=26fc584896) | Aug 02, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | [c670b35249](https://linux-hardware.org/?probe=c670b35249) | Jul 29, 2020 |
| Lenovo        | Y50-70 20378                | [842efe3170](https://linux-hardware.org/?probe=842efe3170) | Jul 28, 2020 |
| Dell          | XPS 13 9360                 | [743f8b4f98](https://linux-hardware.org/?probe=743f8b4f98) | Jul 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [34213d655c](https://linux-hardware.org/?probe=34213d655c) | Jul 24, 2020 |
| Dell          | Precision 5530              | [30c2f2561e](https://linux-hardware.org/?probe=30c2f2561e) | Jul 20, 2020 |
| ASUSTek       | X751NV                      | [f94768a5e6](https://linux-hardware.org/?probe=f94768a5e6) | Jul 15, 2020 |
| HP            | Compaq 6820s                | [f5b6aa7190](https://linux-hardware.org/?probe=f5b6aa7190) | Jul 15, 2020 |
| HP            | EliteBook 8470p             | [ce78055795](https://linux-hardware.org/?probe=ce78055795) | Jul 14, 2020 |
| Notebook      | MAM2080                     | [7464ed3c9d](https://linux-hardware.org/?probe=7464ed3c9d) | Jun 23, 2020 |
| ASUSTek       | X751NV                      | [08c5775f88](https://linux-hardware.org/?probe=08c5775f88) | Jun 22, 2020 |
| Notebook      | MAM2080                     | [7321ecab2d](https://linux-hardware.org/?probe=7321ecab2d) | Jun 21, 2020 |
| Lenovo        | ThinkPad T440 20B7S14N0U    | [c0c727bcb0](https://linux-hardware.org/?probe=c0c727bcb0) | Jun 18, 2020 |
| ASUSTek       | X540UA                      | [7f0afeb60e](https://linux-hardware.org/?probe=7f0afeb60e) | Jun 16, 2020 |
| HP            | 255 G7 Notebook PC          | [639b8bd2bc](https://linux-hardware.org/?probe=639b8bd2bc) | Jun 14, 2020 |
| Acer          | Aspire 7720                 | [77e3ae41d8](https://linux-hardware.org/?probe=77e3ae41d8) | Jun 10, 2020 |
| Acer          | Swift SF314-52              | [fa00080df2](https://linux-hardware.org/?probe=fa00080df2) | Jun 06, 2020 |
| Lenovo        | G710 20252                  | [eff12f397f](https://linux-hardware.org/?probe=eff12f397f) | Jun 06, 2020 |
| Lenovo        | G500 20236                  | [689825038f](https://linux-hardware.org/?probe=689825038f) | May 25, 2020 |
| Toshiba       | Satellite L50-B             | [3ae92d178c](https://linux-hardware.org/?probe=3ae92d178c) | May 21, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [9e3950795e](https://linux-hardware.org/?probe=9e3950795e) | May 17, 2020 |
| Toshiba       | Satellite L50-B             | [0a7ccd88d0](https://linux-hardware.org/?probe=0a7ccd88d0) | May 15, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [951378d6d8](https://linux-hardware.org/?probe=951378d6d8) | May 15, 2020 |
| ASUSTek       | N56VZ                       | [69ee412460](https://linux-hardware.org/?probe=69ee412460) | May 14, 2020 |
| Acer          | Aspire ES1-571              | [77ee42e92e](https://linux-hardware.org/?probe=77ee42e92e) | May 12, 2020 |
| eMachines     | G725                        | [7edfa3ee85](https://linux-hardware.org/?probe=7edfa3ee85) | May 04, 2020 |
| Acer          | Aspire A315-51              | [c5c02e1984](https://linux-hardware.org/?probe=c5c02e1984) | May 03, 2020 |
| Acer          | Aspire A315-51              | [5f8f6e1f17](https://linux-hardware.org/?probe=5f8f6e1f17) | May 02, 2020 |
| Acer          | Swift SF314-52              | [72ece5cb6b](https://linux-hardware.org/?probe=72ece5cb6b) | Apr 23, 2020 |
| Lenovo        | B590 627439G                | [59e71f4410](https://linux-hardware.org/?probe=59e71f4410) | Apr 16, 2020 |
| Dell          | Vostro 3584                 | [37bd21052a](https://linux-hardware.org/?probe=37bd21052a) | Apr 15, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ca750eb568](https://linux-hardware.org/?probe=ca750eb568) | Apr 14, 2020 |
| ASUSTek       | N56VZ                       | [249176d47f](https://linux-hardware.org/?probe=249176d47f) | Apr 01, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [72c0b81b89](https://linux-hardware.org/?probe=72c0b81b89) | Mar 27, 2020 |
| Lenovo        | G710 20252                  | [1a2c3269a9](https://linux-hardware.org/?probe=1a2c3269a9) | Mar 25, 2020 |
| Medion        | P6618                       | [cd6a2e684b](https://linux-hardware.org/?probe=cd6a2e684b) | Mar 20, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [958514b01d](https://linux-hardware.org/?probe=958514b01d) | Mar 06, 2020 |
| HP            | Presario CQ57               | [09b5945399](https://linux-hardware.org/?probe=09b5945399) | Mar 02, 2020 |
| HP            | Pavilion g6                 | [5965dbf803](https://linux-hardware.org/?probe=5965dbf803) | Feb 08, 2020 |
| HP            | EliteBook 850 G6            | [ed2e18e22a](https://linux-hardware.org/?probe=ed2e18e22a) | Jan 31, 2020 |
| Acer          | Aspire A315-21              | [fc460d19de](https://linux-hardware.org/?probe=fc460d19de) | Jan 29, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [ad283e347b](https://linux-hardware.org/?probe=ad283e347b) | Jan 28, 2020 |
| Acer          | Aspire A315-21              | [fe5311a7e7](https://linux-hardware.org/?probe=fe5311a7e7) | Jan 28, 2020 |
| HP            | Laptop 17-ca0xxx            | [0af8fff870](https://linux-hardware.org/?probe=0af8fff870) | Jan 06, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [cd7fe65e36](https://linux-hardware.org/?probe=cd7fe65e36) | Jan 02, 2020 |
| Acer          | Aspire A715-72G             | [d8301b28b6](https://linux-hardware.org/?probe=d8301b28b6) | Dec 31, 2019 |
| HP            | ProBook 4730s               | [a56d8d1c28](https://linux-hardware.org/?probe=a56d8d1c28) | Dec 26, 2019 |
| HP            | ProBook 4730s               | [fc266328ed](https://linux-hardware.org/?probe=fc266328ed) | Dec 26, 2019 |
| HP            | ProBook 4730s               | [581fd252a9](https://linux-hardware.org/?probe=581fd252a9) | Dec 26, 2019 |
| Lenovo        | ThinkPad T440 20B7S14N0U    | [059788b6b9](https://linux-hardware.org/?probe=059788b6b9) | Dec 04, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [1bb0047e0e](https://linux-hardware.org/?probe=1bb0047e0e) | Dec 03, 2019 |
| HP            | OMEN by Laptop 17-cb0xxx    | [c3973966c4](https://linux-hardware.org/?probe=c3973966c4) | Nov 21, 2019 |
| Lenovo        | Y520-15IKBN 80WK            | [518b6e5e9c](https://linux-hardware.org/?probe=518b6e5e9c) | Nov 21, 2019 |
| HP            | Laptop 17-ca0xxx            | [dfc4334b0c](https://linux-hardware.org/?probe=dfc4334b0c) | Nov 15, 2019 |
| HP            | Laptop 17-ca0xxx            | [6334709a9e](https://linux-hardware.org/?probe=6334709a9e) | Nov 15, 2019 |
| HP            | EliteBook 850 G6            | [d1a89b5c7b](https://linux-hardware.org/?probe=d1a89b5c7b) | Nov 13, 2019 |
| Toshiba       | Satellite A300              | [9bd874bab4](https://linux-hardware.org/?probe=9bd874bab4) | Nov 05, 2019 |
| Acer          | Aspire A715-72G             | [ae95cd5f3d](https://linux-hardware.org/?probe=ae95cd5f3d) | Oct 12, 2019 |
| Acer          | Aspire A715-72G             | [38c98d0bfa](https://linux-hardware.org/?probe=38c98d0bfa) | Oct 12, 2019 |
| ASUSTek       | G750JZ                      | [f6f8595b70](https://linux-hardware.org/?probe=f6f8595b70) | Sep 14, 2019 |
| Acer          | Aspire A315-21              | [b29e405bdc](https://linux-hardware.org/?probe=b29e405bdc) | Sep 13, 2019 |
| Acer          | Aspire A515-51G             | [458c9ffc20](https://linux-hardware.org/?probe=458c9ffc20) | Sep 02, 2019 |
| Dell          | G3 3779                     | [46c53c54c1](https://linux-hardware.org/?probe=46c53c54c1) | Aug 28, 2019 |
| Lenovo        | ThinkPad X240 20AMS30A01    | [a808bddfca](https://linux-hardware.org/?probe=a808bddfca) | Aug 22, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [57c89febd9](https://linux-hardware.org/?probe=57c89febd9) | Jul 22, 2019 |
| Dell          | Vostro 3480                 | [142a1d632e](https://linux-hardware.org/?probe=142a1d632e) | Jul 12, 2019 |
| Dell          | Vostro 3480                 | [5c7cd324e3](https://linux-hardware.org/?probe=5c7cd324e3) | Jul 12, 2019 |
| HP            | Laptop 17-ca0xxx            | [542c9cbc52](https://linux-hardware.org/?probe=542c9cbc52) | Jun 23, 2019 |
| Acer          | Aspire A515-51G             | [43a15b2717](https://linux-hardware.org/?probe=43a15b2717) | Jun 22, 2019 |
| Acer          | Extensa 5630                | [ac0c824624](https://linux-hardware.org/?probe=ac0c824624) | Jun 16, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [edcc2f0a4e](https://linux-hardware.org/?probe=edcc2f0a4e) | Jun 06, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [8195d1d516](https://linux-hardware.org/?probe=8195d1d516) | Jun 06, 2019 |
| Dell          | Latitude E6440              | [6c61ba4580](https://linux-hardware.org/?probe=6c61ba4580) | Jun 04, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [6ce5e7dbb1](https://linux-hardware.org/?probe=6ce5e7dbb1) | May 24, 2019 |
| HP            | 250 G6 Notebook PC          | [da7e75ebe8](https://linux-hardware.org/?probe=da7e75ebe8) | May 19, 2019 |
| Lenovo        | G50-45 80E3                 | [d78a5346f7](https://linux-hardware.org/?probe=d78a5346f7) | May 13, 2019 |
| HP            | Laptop 17-ca0xxx            | [6465c1b176](https://linux-hardware.org/?probe=6465c1b176) | May 11, 2019 |
| HP            | Laptop 17-ca0xxx            | [93859ddac7](https://linux-hardware.org/?probe=93859ddac7) | May 05, 2019 |
| HP            | Notebook                    | [75f8121579](https://linux-hardware.org/?probe=75f8121579) | May 03, 2019 |
| HP            | Notebook                    | [55d7e86f13](https://linux-hardware.org/?probe=55d7e86f13) | May 03, 2019 |
| HP            | Notebook                    | [17fa8aef52](https://linux-hardware.org/?probe=17fa8aef52) | May 03, 2019 |
| HP            | Laptop 17-ca0xxx            | [09c192ce30](https://linux-hardware.org/?probe=09c192ce30) | May 03, 2019 |
| HP            | Laptop 17-ca0xxx            | [f4deeacc7c](https://linux-hardware.org/?probe=f4deeacc7c) | May 03, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5d410980c0](https://linux-hardware.org/?probe=5d410980c0) | May 01, 2019 |
| Toshiba       | Satellite A300              | [89f0da0254](https://linux-hardware.org/?probe=89f0da0254) | Apr 30, 2019 |
| ASUSTek       | X550JX                      | [341ce6f2fb](https://linux-hardware.org/?probe=341ce6f2fb) | Apr 14, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [3b3d563f34](https://linux-hardware.org/?probe=3b3d563f34) | Apr 12, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [8046c09d71](https://linux-hardware.org/?probe=8046c09d71) | Apr 03, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [54f04aad99](https://linux-hardware.org/?probe=54f04aad99) | Mar 22, 2019 |
| HP            | Unknown                     | [37702d4223](https://linux-hardware.org/?probe=37702d4223) | Feb 22, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [01e34dc2d8](https://linux-hardware.org/?probe=01e34dc2d8) | Feb 19, 2019 |
| ASUSTek       | X540UA                      | [42572b9771](https://linux-hardware.org/?probe=42572b9771) | Jan 05, 2019 |
| ASUSTek       | X540UA                      | [867a1fdda8](https://linux-hardware.org/?probe=867a1fdda8) | Dec 14, 2018 |
| ASUSTek       | X540UA                      | [ae2b9d2b8f](https://linux-hardware.org/?probe=ae2b9d2b8f) | Dec 14, 2018 |
| ASUSTek       | X540UA                      | [567e365e34](https://linux-hardware.org/?probe=567e365e34) | Dec 14, 2018 |
| Acer          | Aspire 5715Z                | [abecd9bff0](https://linux-hardware.org/?probe=abecd9bff0) | Nov 30, 2018 |
| Acer          | Aspire 5715Z                | [fd1d18122b](https://linux-hardware.org/?probe=fd1d18122b) | Nov 30, 2018 |
| HP            | 2000                        | [b24b2b9082](https://linux-hardware.org/?probe=b24b2b9082) | Nov 26, 2018 |
| HP            | ProBook 450 G4              | [415307639f](https://linux-hardware.org/?probe=415307639f) | Nov 21, 2018 |
| HP            | EliteBook 2540p             | [88e983ac45](https://linux-hardware.org/?probe=88e983ac45) | Oct 28, 2018 |
| ASUSTek       | X705UDR                     | [0a1cf851c7](https://linux-hardware.org/?probe=0a1cf851c7) | Jun 20, 2018 |
| Samsung       | N150/N210/N220              | [bab6da27ab](https://linux-hardware.org/?probe=bab6da27ab) | Apr 30, 2017 |
| Dell          | Vostro 1700                 | [6167c4bd5d](https://linux-hardware.org/?probe=6167c4bd5d) | Mar 17, 2017 |
| Dell          | Inspiron 3737               | [fba4632269](https://linux-hardware.org/?probe=fba4632269) | Dec 22, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 49        | 13.46%  |
| Ubuntu 22.04                 | 22        | 6.04%   |
| Ubuntu 18.04                 | 18        | 4.95%   |
| Debian 11                    | 12        | 3.3%    |
| Arch Rolling                 | 9         | 2.47%   |
| Zorin 16                     | 7         | 1.92%   |
| Pop!_OS 22.04                | 7         | 1.92%   |
| Pop!_OS 21.04                | 7         | 1.92%   |
| OpenMandriva 4.3             | 7         | 1.92%   |
| Fedora 36                    | 7         | 1.92%   |
| Pop!_OS 20.04                | 6         | 1.65%   |
| Ubuntu 19.04                 | 5         | 1.37%   |
| Fedora 38                    | 5         | 1.37%   |
| Fedora 35                    | 5         | 1.37%   |
| Ubuntu 21.04                 | 4         | 1.1%    |
| Pop!_OS 20.10                | 4         | 1.1%    |
| Linux Mint 21.1              | 4         | 1.1%    |
| Linux Mint 20.3              | 4         | 1.1%    |
| Linux Mint 20.2              | 4         | 1.1%    |
| KDE neon 22.04               | 4         | 1.1%    |
| KDE neon 20.04               | 4         | 1.1%    |
| Endless 3.7.8                | 4         | 1.1%    |
| Arch                         | 4         | 1.1%    |
| Zorin 15                     | 3         | 0.82%   |
| Ubuntu 20.10                 | 3         | 0.82%   |
| Ubuntu 19.10                 | 3         | 0.82%   |
| Ubuntu 18.10                 | 3         | 0.82%   |
| ROSA R10                     | 3         | 0.82%   |
| Pop!_OS 21.10                | 3         | 0.82%   |
| OpenMandriva 4.2             | 3         | 0.82%   |
| OpenMandriva 23.01           | 3         | 0.82%   |
| Linux Mint 20.1              | 3         | 0.82%   |
| Endless 3.9.5                | 3         | 0.82%   |
| Endless 3.9.4                | 3         | 0.82%   |
| EndeavourOS Rolling          | 3         | 0.82%   |
| Ubuntu 23.04                 | 2         | 0.55%   |
| Ubuntu 21.10                 | 2         | 0.55%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.55%   |
| OpenMandriva 4.50            | 2         | 0.55%   |
| Nobara 36                    | 2         | 0.55%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 100       | 30.4%   |
| Pop!_OS       | 26        | 7.9%    |
| Fedora        | 23        | 6.99%   |
| Linux Mint    | 22        | 6.69%   |
| Endless       | 22        | 6.69%   |
| Manjaro       | 17        | 5.17%   |
| Debian        | 17        | 5.17%   |
| OpenMandriva  | 16        | 4.86%   |
| Kubuntu       | 12        | 3.65%   |
| Arch          | 12        | 3.65%   |
| Zorin         | 10        | 3.04%   |
| ROSA          | 8         | 2.43%   |
| KDE neon      | 7         | 2.13%   |
| Kali          | 4         | 1.22%   |
| openSUSE      | 3         | 0.91%   |
| EndeavourOS   | 3         | 0.91%   |
| Elementary    | 3         | 0.91%   |
| ArcoLinux     | 3         | 0.91%   |
| Xubuntu       | 2         | 0.61%   |
| Ubuntu MATE   | 2         | 0.61%   |
| Nobara        | 2         | 0.61%   |
| Ubuntu Unity  | 1         | 0.3%    |
| Ubuntu Budgie | 1         | 0.3%    |
| SteamOS       | 1         | 0.3%    |
| Rocky Linux   | 1         | 0.3%    |
| Q4OS          | 1         | 0.3%    |
| Parrot        | 1         | 0.3%    |
| MX            | 1         | 0.3%    |
| Lubuntu       | 1         | 0.3%    |
| LMDE          | 1         | 0.3%    |
| LinuxFX       | 1         | 0.3%    |
| Gentoo        | 1         | 0.3%    |
| Garuda Linux  | 1         | 0.3%    |
| CentOS        | 1         | 0.3%    |
| Artix         | 1         | 0.3%    |
| Arch ARM      | 1         | 0.3%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 7         | 1.78%   |
| 5.8.0-14-generic         | 6         | 1.53%   |
| 5.11.0-38-generic        | 6         | 1.53%   |
| 5.4.0-42-generic         | 5         | 1.27%   |
| 5.11.0-7620-generic      | 5         | 1.27%   |
| 5.3.0-28-generic         | 4         | 1.02%   |
| 5.13.0-30-generic        | 4         | 1.02%   |
| 6.2.6-76060206-generic   | 3         | 0.76%   |
| 6.2.0-26-generic         | 3         | 0.76%   |
| 6.1.1-desktop-1omv2290   | 3         | 0.76%   |
| 5.8.16-2-MANJARO         | 3         | 0.76%   |
| 5.8.0-7630-generic       | 3         | 0.76%   |
| 5.8.0-59-generic         | 3         | 0.76%   |
| 5.8.0-43-generic         | 3         | 0.76%   |
| 5.4.0-52-generic         | 3         | 0.76%   |
| 5.4.0-48-generic         | 3         | 0.76%   |
| 5.4.0-47-generic         | 3         | 0.76%   |
| 5.4.0-37-generic         | 3         | 0.76%   |
| 5.4.0-29-generic         | 3         | 0.76%   |
| 5.4.0-19-generic         | 3         | 0.76%   |
| 5.19.0-38-generic        | 3         | 0.76%   |
| 5.15.0-71-generic        | 3         | 0.76%   |
| 5.15.0-58-generic        | 3         | 0.76%   |
| 5.15.0-56-generic        | 3         | 0.76%   |
| 5.15.0-47-generic        | 3         | 0.76%   |
| 5.15.0-40-generic        | 3         | 0.76%   |
| 5.13.0-7620-generic      | 3         | 0.76%   |
| 5.13.0-52-generic        | 3         | 0.76%   |
| 5.11.0-41-generic        | 3         | 0.76%   |
| 5.11.0-40-generic        | 3         | 0.76%   |
| 5.11.0-35-generic        | 3         | 0.76%   |
| 5.10.14-desktop-1omv4002 | 3         | 0.76%   |
| 4.18.0-18-generic        | 3         | 0.76%   |
| 6.2.15-300.fc38.x86_64   | 2         | 0.51%   |
| 6.0.5-200.fc36.x86_64    | 2         | 0.51%   |
| 5.9.16-1-MANJARO         | 2         | 0.51%   |
| 5.8.0-49-generic         | 2         | 0.51%   |
| 5.8.0-48-generic         | 2         | 0.51%   |
| 5.4.0-91-generic         | 2         | 0.51%   |
| 5.4.0-84-generic         | 2         | 0.51%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 53        | 14.13%  |
| 5.11.0  | 32        | 8.53%   |
| 5.15.0  | 30        | 8%      |
| 5.8.0   | 20        | 5.33%   |
| 5.13.0  | 18        | 4.8%    |
| 4.15.0  | 16        | 4.27%   |
| 5.19.0  | 14        | 3.73%   |
| 5.10.0  | 12        | 3.2%    |
| 5.3.0   | 11        | 2.93%   |
| 5.0.0   | 10        | 2.67%   |
| 4.18.0  | 10        | 2.67%   |
| 5.16.7  | 8         | 2.13%   |
| 6.2.0   | 6         | 1.6%    |
| 6.1.1   | 5         | 1.33%   |
| 6.2.6   | 4         | 1.07%   |
| 5.9.16  | 4         | 1.07%   |
| 5.14.0  | 4         | 1.07%   |
| 6.1.0   | 3         | 0.8%    |
| 6.0.0   | 3         | 0.8%    |
| 5.8.16  | 3         | 0.8%    |
| 5.10.14 | 3         | 0.8%    |
| 4.9.60  | 3         | 0.8%    |
| 4.19.0  | 3         | 0.8%    |
| 6.4.11  | 2         | 0.53%   |
| 6.2.15  | 2         | 0.53%   |
| 6.2.1   | 2         | 0.53%   |
| 6.0.5   | 2         | 0.53%   |
| 5.9.11  | 2         | 0.53%   |
| 5.5.0   | 2         | 0.53%   |
| 5.16.11 | 2         | 0.53%   |
| 5.15.8  | 2         | 0.53%   |
| 5.11.22 | 2         | 0.53%   |
| 6.5.5   | 1         | 0.27%   |
| 6.4.4   | 1         | 0.27%   |
| 6.4.13  | 1         | 0.27%   |
| 6.4.12  | 1         | 0.27%   |
| 6.3.7   | 1         | 0.27%   |
| 6.3.6   | 1         | 0.27%   |
| 6.2.7   | 1         | 0.27%   |
| 6.2.12  | 1         | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 56        | 15.22%  |
| 5.15    | 38        | 10.33%  |
| 5.11    | 38        | 10.33%  |
| 5.8     | 24        | 6.52%   |
| 5.13    | 21        | 5.71%   |
| 5.10    | 20        | 5.43%   |
| 5.19    | 19        | 5.16%   |
| 6.2     | 17        | 4.62%   |
| 4.15    | 16        | 4.35%   |
| 6.1     | 13        | 3.53%   |
| 5.16    | 13        | 3.53%   |
| 5.3     | 12        | 3.26%   |
| 5.0     | 11        | 2.99%   |
| 4.18    | 10        | 2.72%   |
| 5.9     | 8         | 2.17%   |
| 6.0     | 6         | 1.63%   |
| 5.18    | 5         | 1.36%   |
| 5.17    | 5         | 1.36%   |
| 5.14    | 5         | 1.36%   |
| 4.9     | 5         | 1.36%   |
| 6.4     | 4         | 1.09%   |
| 5.6     | 4         | 1.09%   |
| 4.19    | 3         | 0.82%   |
| 6.3     | 2         | 0.54%   |
| 5.5     | 2         | 0.54%   |
| 5.12    | 2         | 0.54%   |
| 6.5     | 1         | 0.27%   |
| 5.7     | 1         | 0.27%   |
| 5.2     | 1         | 0.27%   |
| 5.1     | 1         | 0.27%   |
| 4.17    | 1         | 0.27%   |
| 4.16    | 1         | 0.27%   |
| 4.12    | 1         | 0.27%   |
| 4.1     | 1         | 0.27%   |
| 3.10    | 1         | 0.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 310       | 97.48%  |
| i686    | 7         | 2.2%    |
| aarch64 | 1         | 0.31%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 161       | 48.06%  |
| KDE5            | 62        | 18.51%  |
| Unknown         | 39        | 11.64%  |
| X-Cinnamon      | 16        | 4.78%   |
| XFCE            | 15        | 4.48%   |
| Cinnamon        | 7         | 2.09%   |
| KDE             | 6         | 1.79%   |
| MATE            | 5         | 1.49%   |
| KDE4            | 4         | 1.19%   |
| GNOME Flashback | 4         | 1.19%   |
| Pantheon        | 3         | 0.9%    |
| DWM             | 3         | 0.9%    |
| LXQt            | 2         | 0.6%    |
| Budgie          | 2         | 0.6%    |
| Unity           | 1         | 0.3%    |
| Trinity         | 1         | 0.3%    |
| LXDE            | 1         | 0.3%    |
| i3              | 1         | 0.3%    |
| GNUstep         | 1         | 0.3%    |
| bspwm           | 1         | 0.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 248       | 72.73%  |
| Wayland | 61        | 17.89%  |
| Unknown | 27        | 7.92%   |
| Tty     | 5         | 1.47%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 146       | 44.51%  |
| GDM     | 57        | 17.38%  |
| SDDM    | 50        | 15.24%  |
| GDM3    | 35        | 10.67%  |
| LightDM | 25        | 7.62%   |
| TDM     | 11        | 3.35%   |
| KDM     | 3         | 0.91%   |
| Ly      | 1         | 0.3%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 187       | 57.19%  |
| hr_HR   | 71        | 21.71%  |
| Unknown | 39        | 11.93%  |
| en_GB   | 15        | 4.59%   |
| de_DE   | 6         | 1.83%   |
| C       | 4         | 1.22%   |
| pl_PL   | 1         | 0.31%   |
| hr_BA   | 1         | 0.31%   |
| fr_FR   | 1         | 0.31%   |
| en_DE   | 1         | 0.31%   |
| en_150  | 1         | 0.31%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 196       | 59.94%  |
| BIOS | 131       | 40.06%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 253       | 76.9%   |
| Btrfs   | 25        | 7.6%    |
| Overlay | 16        | 4.86%   |
| Unknown | 16        | 4.86%   |
| Zfs     | 6         | 1.82%   |
| Xfs     | 6         | 1.82%   |
| Tmpfs   | 5         | 1.52%   |
| Jfs     | 1         | 0.3%    |
| Ext2    | 1         | 0.3%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 154       | 47.53%  |
| GPT     | 136       | 41.98%  |
| MBR     | 34        | 10.49%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 295       | 91.61%  |
| Yes       | 27        | 8.39%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 247       | 76.47%  |
| Yes       | 76        | 23.53%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 80        | 25.16%  |
| Hewlett-Packard         | 61        | 19.18%  |
| Acer                    | 56        | 17.61%  |
| ASUSTek Computer        | 41        | 12.89%  |
| Dell                    | 38        | 11.95%  |
| Toshiba                 | 7         | 2.2%    |
| Apple                   | 6         | 1.89%   |
| Samsung Electronics     | 4         | 1.26%   |
| HUAWEI                  | 3         | 0.94%   |
| Fujitsu Siemens         | 3         | 0.94%   |
| eMachines               | 3         | 0.94%   |
| TUXEDO                  | 2         | 0.63%   |
| Tactus                  | 2         | 0.63%   |
| Valve                   | 1         | 0.31%   |
| Timi                    | 1         | 0.31%   |
| System76                | 1         | 0.31%   |
| SHENZHEN X&F TECHNOLOGY | 1         | 0.31%   |
| Schenker                | 1         | 0.31%   |
| Razer                   | 1         | 0.31%   |
| Pretech                 | 1         | 0.31%   |
| Notebook                | 1         | 0.31%   |
| Medion                  | 1         | 0.31%   |
| Gigabyte Technology     | 1         | 0.31%   |
| Chuwi                   | 1         | 0.31%   |
| Unknown                 | 1         | 0.31%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Acer Aspire A315-21                       | 4         | 1.26%   |
| Lenovo G710 20252                         | 3         | 0.94%   |
| Acer Aspire A515-51G                      | 3         | 0.94%   |
| Unknown                                   | 3         | 0.94%   |
| TUXEDO Pulse 15 Gen1                      | 2         | 0.63%   |
| Tactus GeoBook 140                        | 2         | 0.63%   |
| Lenovo Z50-70 20354                       | 2         | 0.63%   |
| Lenovo ThinkBook 16p Gen 2 20YM           | 2         | 0.63%   |
| Lenovo ThinkBook 15 G2 ITL 20VE           | 2         | 0.63%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ          | 2         | 0.63%   |
| Lenovo Legion 5 15ARH05 82B5              | 2         | 0.63%   |
| Lenovo G40-30 80FY                        | 2         | 0.63%   |
| HP ProBook 450 G7                         | 2         | 0.63%   |
| HP OMEN by Laptop                         | 2         | 0.63%   |
| HP Laptop 15s-eq2xxx                      | 2         | 0.63%   |
| HP EliteBook 8560p                        | 2         | 0.63%   |
| HP EliteBook 850 G6                       | 2         | 0.63%   |
| HP EliteBook 845 G8 Notebook PC           | 2         | 0.63%   |
| HP 2000                                   | 2         | 0.63%   |
| Fujitsu Siemens ESPRIMO Mobile V5535      | 2         | 0.63%   |
| Dell XPS 13 9310                          | 2         | 0.63%   |
| Dell Vostro 3500                          | 2         | 0.63%   |
| Dell Inspiron N5110                       | 2         | 0.63%   |
| Dell Inspiron 5570                        | 2         | 0.63%   |
| ASUS X751NV                               | 2         | 0.63%   |
| ASUS VivoBook_ASUSLaptop M3500QA_M3500QA  | 2         | 0.63%   |
| ASUS VivoBook 15_ASUS Laptop X560UD       | 2         | 0.63%   |
| ASUS VivoBook 15_ASUS Laptop X540BP       | 2         | 0.63%   |
| ASUS N56VZ                                | 2         | 0.63%   |
| ASUS ASUS EXPERTBOOK B1400CEAEY_B1400CEAE | 2         | 0.63%   |
| Apple MacBookAir5,2                       | 2         | 0.63%   |
| Acer Swift SF314-43                       | 2         | 0.63%   |
| Acer Nitro AN515-55                       | 2         | 0.63%   |
| Acer Aspire E5-771G                       | 2         | 0.63%   |
| Acer Aspire A715-72G                      | 2         | 0.63%   |
| Acer Aspire A315-23                       | 2         | 0.63%   |
| Acer Aspire 7739G                         | 2         | 0.63%   |
| Valve Jupiter                             | 1         | 0.31%   |
| Toshiba Satellite P200                    | 1         | 0.31%   |
| Toshiba Satellite L750                    | 1         | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Acer Aspire             | 41        | 12.89%  |
| Lenovo ThinkPad         | 36        | 11.32%  |
| HP EliteBook            | 17        | 5.35%   |
| HP ProBook              | 10        | 3.14%   |
| Dell Latitude           | 10        | 3.14%   |
| ASUS VivoBook           | 10        | 3.14%   |
| Lenovo IdeaPad          | 9         | 2.83%   |
| HP Pavilion             | 9         | 2.83%   |
| Dell Inspiron           | 9         | 2.83%   |
| Lenovo Legion           | 8         | 2.52%   |
| Lenovo ThinkBook        | 7         | 2.2%    |
| HP Laptop               | 7         | 2.2%    |
| Dell XPS                | 7         | 2.2%    |
| Dell Vostro             | 7         | 2.2%    |
| Acer Swift              | 7         | 2.2%    |
| Toshiba Satellite       | 6         | 1.89%   |
| ASUS Zenbook            | 5         | 1.57%   |
| HP 250                  | 4         | 1.26%   |
| Acer Nitro              | 4         | 1.26%   |
| Lenovo G710             | 3         | 0.94%   |
| HP OMEN                 | 3         | 0.94%   |
| HP Compaq               | 3         | 0.94%   |
| ASUS ROG                | 3         | 0.94%   |
| ASUS ASUS               | 3         | 0.94%   |
| Unknown                 | 3         | 0.94%   |
| TUXEDO Pulse            | 2         | 0.63%   |
| Tactus GeoBook          | 2         | 0.63%   |
| Lenovo Z50-70           | 2         | 0.63%   |
| Lenovo G40-30           | 2         | 0.63%   |
| Lenovo B590             | 2         | 0.63%   |
| HP 2000                 | 2         | 0.63%   |
| Fujitsu Siemens ESPRIMO | 2         | 0.63%   |
| ASUS X751NV             | 2         | 0.63%   |
| ASUS N56VZ              | 2         | 0.63%   |
| Apple MacBookAir5       | 2         | 0.63%   |
| Acer Predator           | 2         | 0.63%   |
| Valve Jupiter           | 1         | 0.31%   |
| Toshiba Encore          | 1         | 0.31%   |
| Timi TM1701             | 1         | 0.31%   |
| System76 Oryx           | 1         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2018    | 39        | 12.26%  |
| 2020    | 36        | 11.32%  |
| 2021    | 34        | 10.69%  |
| 2019    | 29        | 9.12%   |
| 2017    | 28        | 8.81%   |
| 2016    | 21        | 6.6%    |
| 2014    | 21        | 6.6%    |
| 2013    | 21        | 6.6%    |
| 2011    | 19        | 5.97%   |
| 2012    | 16        | 5.03%   |
| 2008    | 10        | 3.14%   |
| 2007    | 10        | 3.14%   |
| 2022    | 9         | 2.83%   |
| 2015    | 7         | 2.2%    |
| 2010    | 6         | 1.89%   |
| 2009    | 6         | 1.89%   |
| 2006    | 3         | 0.94%   |
| 2023    | 2         | 0.63%   |
| Unknown | 1         | 0.31%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 318       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 280       | 87.23%  |
| Enabled  | 41        | 12.77%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 318       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 92        | 28.48%  |
| 8.01-16.0   | 66        | 20.43%  |
| 3.01-4.0    | 57        | 17.65%  |
| 16.01-24.0  | 53        | 16.41%  |
| 32.01-64.0  | 25        | 7.74%   |
| 24.01-32.0  | 11        | 3.41%   |
| 1.01-2.0    | 11        | 3.41%   |
| 2.01-3.0    | 5         | 1.55%   |
| 64.01-256.0 | 3         | 0.93%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 114       | 31.23%  |
| 2.01-3.0   | 87        | 23.84%  |
| 4.01-8.0   | 69        | 18.9%   |
| 3.01-4.0   | 53        | 14.52%  |
| 8.01-16.0  | 20        | 5.48%   |
| 0.51-1.0   | 18        | 4.93%   |
| 16.01-24.0 | 2         | 0.55%   |
| 0.01-0.5   | 2         | 0.55%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 238       | 72.78%  |
| 2      | 70        | 21.41%  |
| 3      | 10        | 3.06%   |
| 4      | 4         | 1.22%   |
| 0      | 3         | 0.92%   |
| 6      | 1         | 0.31%   |
| 5      | 1         | 0.31%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 228       | 71.25%  |
| Yes       | 92        | 28.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 261       | 81.82%  |
| No        | 58        | 18.18%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 312       | 98.11%  |
| No        | 6         | 1.89%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 264       | 81.48%  |
| No        | 60        | 18.52%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Croatia | 318       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Zagreb              | 202       | 55.19%  |
| Split               | 18        | 4.92%   |
| Rijeka              | 13        | 3.55%   |
| Varaždin           | 10        | 2.73%   |
| Velika Gorica       | 6         | 1.64%   |
| Pula                | 6         | 1.64%   |
| Zadar               | 5         | 1.37%   |
| Osijek              | 5         | 1.37%   |
| Zaprešić          | 4         | 1.09%   |
| Čakovec            | 4         | 1.09%   |
| Bjelovar            | 4         | 1.09%   |
| Petrinja            | 3         | 0.82%   |
| Koprivnica          | 3         | 0.82%   |
| Jesenice            | 3         | 0.82%   |
| Đakovo             | 2         | 0.55%   |
| Virovitica          | 2         | 0.55%   |
| Vinkovci            | 2         | 0.55%   |
| Rovinj              | 2         | 0.55%   |
| Omiš               | 2         | 0.55%   |
| Novska              | 2         | 0.55%   |
| Krizevci            | 2         | 0.55%   |
| Komiža             | 2         | 0.55%   |
| Kastav              | 2         | 0.55%   |
| Karlovac            | 2         | 0.55%   |
| Cres                | 2         | 0.55%   |
| Buzin               | 2         | 0.55%   |
| Zminj               | 1         | 0.27%   |
| Zabok               | 1         | 0.27%   |
| Visoko              | 1         | 0.27%   |
| Velika Mlaka        | 1         | 0.27%   |
| Varazdinske Toplice | 1         | 0.27%   |
| Umag                | 1         | 0.27%   |
| Udbinja             | 1         | 0.27%   |
| Trenkovo            | 1         | 0.27%   |
| Sveti Ivan Zelina   | 1         | 0.27%   |
| Sveta Marija        | 1         | 0.27%   |
| Supetar             | 1         | 0.27%   |
| Strmec              | 1         | 0.27%   |
| Sracinec            | 1         | 0.27%   |
| Slavonski Brod      | 1         | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Samsung Electronics   | 65        | 82     | 16.25%  |
| WDC                   | 48        | 60     | 12%     |
| Kingston              | 39        | 51     | 9.75%   |
| Seagate               | 34        | 58     | 8.5%    |
| SK hynix              | 29        | 44     | 7.25%   |
| SanDisk               | 28        | 33     | 7%      |
| Toshiba               | 27        | 31     | 6.75%   |
| Micron Technology     | 19        | 22     | 4.75%   |
| Unknown               | 13        | 13     | 3.25%   |
| Intel                 | 12        | 18     | 3%      |
| Crucial               | 11        | 16     | 2.75%   |
| Hitachi               | 10        | 10     | 2.5%    |
| HGST                  | 8         | 8      | 2%      |
| Apple                 | 7         | 11     | 1.75%   |
| Fujitsu               | 5         | 7      | 1.25%   |
| A-DATA Technology     | 5         | 5      | 1.25%   |
| Patriot               | 4         | 5      | 1%      |
| LITEON                | 4         | 5      | 1%      |
| Silicon Motion        | 3         | 4      | 0.75%   |
| Netac                 | 3         | 3      | 0.75%   |
| UMIS                  | 2         | 2      | 0.5%    |
| Transcend             | 2         | 3      | 0.5%    |
| Lenovo                | 2         | 3      | 0.5%    |
| KIOXIA                | 2         | 2      | 0.5%    |
| KingFast              | 2         | 4      | 0.5%    |
| Intenso               | 2         | 3      | 0.5%    |
| Verbatim              | 1         | 1      | 0.25%   |
| StoreJet              | 1         | 1      | 0.25%   |
| SSK                   | 1         | 1      | 0.25%   |
| Realtek Semiconductor | 1         | 3      | 0.25%   |
| Phison Electronics    | 1         | 1      | 0.25%   |
| Phison                | 1         | 1      | 0.25%   |
| Mass                  | 1         | 1      | 0.25%   |
| Lite-On               | 1         | 1      | 0.25%   |
| LaCie                 | 1         | 1      | 0.25%   |
| JMicron Technology    | 1         | 1      | 0.25%   |
| Gigabyte Technology   | 1         | 1      | 0.25%   |
| Emtec                 | 1         | 1      | 0.25%   |
| Corsair               | 1         | 1      | 0.25%   |
| AMD                   | 1         | 3      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB                       | 8         | 1.96%   |
| Kingston SA400S37240G 240GB SSD                    | 7         | 1.71%   |
| SanDisk NVMe SSD Drive 512GB                       | 6         | 1.47%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD                | 6         | 1.47%   |
| Toshiba MQ01ABD100 1TB                             | 5         | 1.22%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 4         | 0.98%   |
| Kingston SA400S37120G 120GB SSD                    | 4         | 0.98%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB                 | 3         | 0.73%   |
| Unknown MMC Card  32GB                             | 3         | 0.73%   |
| Toshiba MQ04ABF100 1TB                             | 3         | 0.73%   |
| Toshiba MQ01ABF050 500GB                           | 3         | 0.73%   |
| SK hynix NVMe SSD Drive 256GB                      | 3         | 0.73%   |
| Seagate ST9500325AS 500GB                          | 3         | 0.73%   |
| Seagate ST500LT012-1DG142 500GB                    | 3         | 0.73%   |
| Seagate ST2000LM007-1R8174 2TB                     | 3         | 0.73%   |
| Seagate ST1000LM048-2E7172 1TB                     | 3         | 0.73%   |
| Seagate ST1000LM035-1RK172 1TB                     | 3         | 0.73%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB               | 3         | 0.73%   |
| Samsung SSD 850 EVO 250GB                          | 3         | 0.73%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 3         | 0.73%   |
| Samsung MZALQ512HALU-000L2 512GB                   | 3         | 0.73%   |
| Netac SSD 128GB                                    | 3         | 0.73%   |
| Kingston SA400S37480G 480GB SSD                    | 3         | 0.73%   |
| Intel NVMe SSD Drive 256GB                         | 3         | 0.73%   |
| HGST HTS721010A9E630 1TB                           | 3         | 0.73%   |
| Crucial CT240BX500SSD1 240GB                       | 3         | 0.73%   |
| WDC WD5000LPCX-60VHAT0 500GB                       | 2         | 0.49%   |
| WDC WD5000LPCX-24C6HT0 500GB                       | 2         | 0.49%   |
| WDC WD1600BEVT-22ZCT0 160GB                        | 2         | 0.49%   |
| WDC WD10SPZX-21Z10T0 1TB                           | 2         | 0.49%   |
| WDC WD10JPVX-22JC3T0 1TB                           | 2         | 0.49%   |
| Unknown SD/MMC/MS PRO 128GB                        | 2         | 0.49%   |
| Unknown MMC Card  128GB                            | 2         | 0.49%   |
| Toshiba KBG30ZMS256G NVMe 256GB                    | 2         | 0.49%   |
| SK hynix SH920 2.5 7MM 256GB SSD                   | 2         | 0.49%   |
| SK hynix NVMe SSD Drive 512GB                      | 2         | 0.49%   |
| SK hynix HFS256G39TND-N210A 256GB SSD              | 2         | 0.49%   |
| SK hynix HFS128G39TND-N210A 128GB SSD              | 2         | 0.49%   |
| SK hynix HFM512GDJTNI-82A0A 512GB                  | 2         | 0.49%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB            | 2         | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 33        | 46     | 30.56%  |
| WDC                 | 28        | 33     | 25.93%  |
| Toshiba             | 18        | 20     | 16.67%  |
| Hitachi             | 10        | 10     | 9.26%   |
| HGST                | 8         | 8      | 7.41%   |
| Fujitsu             | 5         | 7      | 4.63%   |
| Unknown             | 2         | 2      | 1.85%   |
| SSK                 | 1         | 1      | 0.93%   |
| Samsung Electronics | 1         | 2      | 0.93%   |
| JMicron Technology  | 1         | 1      | 0.93%   |
| Intenso             | 1         | 2      | 0.93%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 30        | 38     | 23.08%  |
| Samsung Electronics | 19        | 27     | 14.62%  |
| SanDisk             | 14        | 18     | 10.77%  |
| Micron Technology   | 10        | 11     | 7.69%   |
| Crucial             | 10        | 15     | 7.69%   |
| SK hynix            | 8         | 14     | 6.15%   |
| WDC                 | 7         | 9      | 5.38%   |
| Apple               | 6         | 8      | 4.62%   |
| A-DATA Technology   | 5         | 5      | 3.85%   |
| Patriot             | 4         | 5      | 3.08%   |
| Netac               | 3         | 3      | 2.31%   |
| LITEON              | 3         | 4      | 2.31%   |
| Intel               | 3         | 4      | 2.31%   |
| Toshiba             | 2         | 4      | 1.54%   |
| Transcend           | 1         | 2      | 0.77%   |
| StoreJet            | 1         | 1      | 0.77%   |
| Intenso             | 1         | 1      | 0.77%   |
| Gigabyte Technology | 1         | 1      | 0.77%   |
| Emtec               | 1         | 1      | 0.77%   |
| AMD                 | 1         | 3      | 0.77%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 140       | 187    | 36.84%  |
| SSD     | 118       | 174    | 31.05%  |
| HDD     | 106       | 132    | 27.89%  |
| MMC     | 10        | 10     | 2.63%   |
| Unknown | 6         | 18     | 1.58%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 195       | 295    | 54.47%  |
| NVMe | 140       | 187    | 39.11%  |
| SAS  | 13        | 29     | 3.63%   |
| MMC  | 10        | 10     | 2.79%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 152       | 210    | 68.16%  |
| 0.51-1.0   | 64        | 87     | 28.7%   |
| 1.01-2.0   | 6         | 7      | 2.69%   |
| 2.01-3.0   | 1         | 2      | 0.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 103       | 30.84%  |
| 251-500        | 89        | 26.65%  |
| 501-1000       | 52        | 15.57%  |
| 1001-2000      | 31        | 9.28%   |
| 51-100         | 18        | 5.39%   |
| 1-20           | 17        | 5.09%   |
| 21-50          | 9         | 2.69%   |
| Unknown        | 8         | 2.4%    |
| 2001-3000      | 4         | 1.2%    |
| More than 3000 | 3         | 0.9%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 117       | 32.68%  |
| 21-50          | 77        | 21.51%  |
| 101-250        | 51        | 14.25%  |
| 51-100         | 43        | 12.01%  |
| 251-500        | 31        | 8.66%   |
| 501-1000       | 25        | 6.98%   |
| Unknown        | 8         | 2.23%   |
| 1001-2000      | 5         | 1.4%    |
| More than 3000 | 1         | 0.28%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1         | 1      | 4.17%   |
| WDC WD600VE-75HDT0 64GB              | 1         | 1      | 4.17%   |
| WDC WD10JPCX-24UE4T0 1TB             | 1         | 1      | 4.17%   |
| Toshiba MK6459GSXP 640GB             | 1         | 1      | 4.17%   |
| SK hynix SH920 2.5 7MM 256GB SSD     | 1         | 2      | 4.17%   |
| SK hynix SC210 2.5 7MM 256GB SSD     | 1         | 1      | 4.17%   |
| Seagate ST9500420AS 500GB            | 1         | 1      | 4.17%   |
| Seagate ST9500325AS 500GB            | 1         | 1      | 4.17%   |
| Seagate ST9250827AS 250GB            | 1         | 1      | 4.17%   |
| Seagate ST500DM002-1BD142 500GB      | 1         | 2      | 4.17%   |
| Seagate ST2000LM007-1R8174 2TB       | 1         | 1      | 4.17%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 1      | 4.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 1         | 1      | 4.17%   |
| SanDisk SDSSDXPS960G 960GB           | 1         | 1      | 4.17%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD  | 1         | 1      | 4.17%   |
| LITEON LMH-256V2M-11 MSATA 256GB SSD | 1         | 1      | 4.17%   |
| Intel SSDSC2KW512G8 512GB            | 1         | 1      | 4.17%   |
| Hitachi HTS723232A7A364 320GB        | 1         | 1      | 4.17%   |
| Hitachi HTS542512K9SA00 120GB        | 1         | 1      | 4.17%   |
| HGST HTS721010A9E630 1TB             | 1         | 1      | 4.17%   |
| HGST HTS545050A7E380 500GB           | 1         | 1      | 4.17%   |
| HGST HTS541010A9E680 1TB             | 1         | 1      | 4.17%   |
| Crucial CT1024M550SSD1 1024GB        | 1         | 1      | 4.17%   |
| A-DATA Technology SU630 240GB SSD    | 1         | 1      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 7         | 8      | 30.43%  |
| WDC               | 3         | 3      | 13.04%  |
| HGST              | 3         | 3      | 13.04%  |
| SK hynix          | 2         | 3      | 8.7%    |
| Hitachi           | 2         | 2      | 8.7%    |
| Toshiba           | 1         | 1      | 4.35%   |
| SanDisk           | 1         | 2      | 4.35%   |
| LITEON            | 1         | 1      | 4.35%   |
| Intel             | 1         | 1      | 4.35%   |
| Crucial           | 1         | 1      | 4.35%   |
| A-DATA Technology | 1         | 1      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 8      | 46.67%  |
| HGST    | 3         | 3      | 20%     |
| WDC     | 2         | 2      | 13.33%  |
| Hitachi | 2         | 2      | 13.33%  |
| Toshiba | 1         | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 16     | 68.18%  |
| SSD  | 7         | 10     | 31.82%  |

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
| Detected | 184       | 289    | 53.8%   |
| Works    | 137       | 206    | 40.06%  |
| Malfunc  | 21        | 26     | 6.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 217       | 52.93%  |
| Samsung Electronics              | 48        | 11.71%  |
| AMD                              | 45        | 10.98%  |
| SanDisk                          | 28        | 6.83%   |
| SK hynix                         | 21        | 5.12%   |
| Toshiba America Info Systems     | 9         | 2.2%    |
| Micron Technology                | 9         | 2.2%    |
| Kingston Technology Company      | 9         | 2.2%    |
| Silicon Motion                   | 3         | 0.73%   |
| Phison Electronics               | 3         | 0.73%   |
| Union Memory (Shenzhen)          | 2         | 0.49%   |
| Silicon Integrated Systems [SiS] | 2         | 0.49%   |
| Nvidia                           | 2         | 0.49%   |
| Lite-On Technology               | 2         | 0.49%   |
| Lenovo                           | 2         | 0.49%   |
| KIOXIA                           | 2         | 0.49%   |
| VIA Technologies                 | 1         | 0.24%   |
| Seagate Technology               | 1         | 0.24%   |
| Realtek Semiconductor            | 1         | 0.24%   |
| Micron/Crucial Technology        | 1         | 0.24%   |
| Marvell Technology Group         | 1         | 0.24%   |
| JMicron Technology               | 1         | 0.24%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 42        | 9.59%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 33        | 7.53%   |
| Samsung NVMe SSD Controller 980                                                  | 19        | 4.34%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 19        | 4.34%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 17        | 3.88%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 16        | 3.65%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 16        | 3.65%   |
| Intel Volume Management Device NVMe RAID Controller                              | 14        | 3.2%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 13        | 2.97%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 10        | 2.28%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 10        | 2.28%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 9         | 2.05%   |
| Intel Tiger Lake-LP SATA Controller                                              | 9         | 2.05%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 9         | 2.05%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 9         | 2.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 9         | 2.05%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 8         | 1.83%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 7         | 1.6%    |
| SK hynix BC501 NVMe Solid State Drive                                            | 6         | 1.37%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 6         | 1.37%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 1.37%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 5         | 1.14%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 1.14%   |
| Intel Comet Lake SATA AHCI Controller                                            | 5         | 1.14%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 5         | 1.14%   |
| SK hynix BC511 NVMe SSD                                                          | 4         | 0.91%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                 | 4         | 0.91%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 4         | 0.91%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4         | 0.91%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 0.91%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 3         | 0.68%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 3         | 0.68%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                       | 3         | 0.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 0.68%   |
| Intel SSD 660P Series                                                            | 3         | 0.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 0.68%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 0.68%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 2         | 0.46%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 2         | 0.46%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 2         | 0.46%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 233       | 55.34%  |
| NVMe | 140       | 33.25%  |
| IDE  | 25        | 5.94%   |
| RAID | 23        | 5.46%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 247       | 77.67%  |
| AMD     | 70        | 22.01%  |
| Unknown | 1         | 0.31%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 12        | 3.77%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 11        | 3.46%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 11        | 3.46%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 7         | 2.2%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 6         | 1.89%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 1.89%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 6         | 1.89%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 6         | 1.89%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 1.57%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 1.57%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 1.57%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 1.26%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 1.26%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.26%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 4         | 1.26%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 4         | 1.26%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 3         | 0.94%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 3         | 0.94%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 3         | 0.94%   |
| Intel Pentium 3556U @ 1.70GHz                 | 3         | 0.94%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 0.94%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 0.94%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 0.94%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 0.94%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 0.94%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 3         | 0.94%   |
| AMD Ryzen 5 PRO 5650U with Radeon Graphics    | 3         | 0.94%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 0.94%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 0.94%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 3         | 0.94%   |
| Intel Pentium M processor 1.86GHz             | 2         | 0.63%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 2         | 0.63%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 2         | 0.63%   |
| Intel Core i9-9880H CPU @ 2.30GHz             | 2         | 0.63%   |
| Intel Core i9-8950HK CPU @ 2.90GHz            | 2         | 0.63%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.63%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.63%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.63%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 0.63%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 87        | 27.36%  |
| Intel Core i7           | 50        | 15.72%  |
| Other                   | 29        | 9.12%   |
| AMD Ryzen 5             | 20        | 6.29%   |
| Intel Core i3           | 19        | 5.97%   |
| AMD Ryzen 7             | 19        | 5.97%   |
| Intel Core 2 Duo        | 18        | 5.66%   |
| Intel Pentium           | 16        | 5.03%   |
| Intel Celeron           | 10        | 3.14%   |
| AMD Ryzen 3             | 6         | 1.89%   |
| Intel Pentium Dual-Core | 4         | 1.26%   |
| Intel Pentium Dual      | 4         | 1.26%   |
| Intel Core i9           | 4         | 1.26%   |
| Intel Atom              | 4         | 1.26%   |
| AMD Ryzen 5 PRO         | 4         | 1.26%   |
| AMD A6                  | 4         | 1.26%   |
| Intel Pentium Silver    | 3         | 0.94%   |
| AMD Ryzen 9             | 3         | 0.94%   |
| AMD E                   | 3         | 0.94%   |
| Intel Pentium M         | 2         | 0.63%   |
| AMD E1                  | 2         | 0.63%   |
| Intel Genuine           | 1         | 0.31%   |
| Intel Celeron M         | 1         | 0.31%   |
| AMD Turion 64 X2 Mobile | 1         | 0.31%   |
| AMD Ryzen 7 PRO         | 1         | 0.31%   |
| AMD Athlon              | 1         | 0.31%   |
| AMD A4                  | 1         | 0.31%   |
| AMD A10                 | 1         | 0.31%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 145       | 45.6%   |
| 4       | 109       | 34.28%  |
| 6       | 26        | 8.18%   |
| 8       | 25        | 7.86%   |
| 10      | 4         | 1.26%   |
| 1       | 4         | 1.26%   |
| 14      | 2         | 0.63%   |
| 16      | 1         | 0.31%   |
| 12      | 1         | 0.31%   |
| Unknown | 1         | 0.31%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 317       | 99.69%  |
| Unknown | 1         | 0.31%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 235       | 73.9%   |
| 1       | 82        | 25.79%  |
| Unknown | 1         | 0.31%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 305       | 95.31%  |
| Unknown        | 9         | 2.81%   |
| 32-bit         | 5         | 1.56%   |
| 64-bit         | 1         | 0.31%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 81        | 24.04%  |
| 0x806ea    | 17        | 5.04%   |
| 0x306c3    | 16        | 4.75%   |
| 0x306a9    | 16        | 4.75%   |
| 0x806e9    | 15        | 4.45%   |
| 0x40651    | 13        | 3.86%   |
| 0x906ea    | 12        | 3.56%   |
| 0x806ec    | 11        | 3.26%   |
| 0x806c1    | 10        | 2.97%   |
| 0x0a50000c | 9         | 2.67%   |
| 0x6fd      | 8         | 2.37%   |
| 0x206a7    | 8         | 2.37%   |
| 0x08108109 | 8         | 2.37%   |
| 0x1067a    | 7         | 2.08%   |
| 0xa0652    | 6         | 1.78%   |
| 0x08608103 | 6         | 1.78%   |
| 0x306d4    | 5         | 1.48%   |
| 0x08600103 | 5         | 1.48%   |
| 0x06006705 | 5         | 1.48%   |
| 0x406e3    | 4         | 1.19%   |
| 0x30678    | 4         | 1.19%   |
| 0x10676    | 4         | 1.19%   |
| 0x08600106 | 4         | 1.19%   |
| 0x0810100b | 4         | 1.19%   |
| 0x906a3    | 3         | 0.89%   |
| 0x706e5    | 3         | 0.89%   |
| 0x706a1    | 3         | 0.89%   |
| 0x506c9    | 3         | 0.89%   |
| 0x20655    | 3         | 0.89%   |
| 0x08108102 | 3         | 0.89%   |
| 0x05000119 | 3         | 0.89%   |
| 0x906ed    | 2         | 0.59%   |
| 0x906e9    | 2         | 0.59%   |
| 0x906a4    | 2         | 0.59%   |
| 0x806eb    | 2         | 0.59%   |
| 0x6fb      | 2         | 0.59%   |
| 0x6e8      | 2         | 0.59%   |
| 0x6d8      | 2         | 0.59%   |
| 0x406c4    | 2         | 0.59%   |
| 0x0a50000d | 2         | 0.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 78        | 24.53%  |
| Haswell          | 33        | 10.38%  |
| IvyBridge        | 20        | 6.29%   |
| TigerLake        | 16        | 5.03%   |
| Penryn           | 15        | 4.72%   |
| Unknown          | 15        | 4.72%   |
| Zen 2            | 14        | 4.4%    |
| Zen+             | 12        | 3.77%   |
| Zen 3            | 12        | 3.77%   |
| Core             | 11        | 3.46%   |
| Silvermont       | 10        | 3.14%   |
| SandyBridge      | 10        | 3.14%   |
| Skylake          | 8         | 2.52%   |
| Excavator        | 7         | 2.2%    |
| Broadwell        | 7         | 2.2%    |
| Alderlake Hybrid | 7         | 2.2%    |
| Goldmont plus    | 6         | 1.89%   |
| CometLake        | 6         | 1.89%   |
| IceLake          | 5         | 1.57%   |
| Zen              | 4         | 1.26%   |
| Westmere         | 4         | 1.26%   |
| P6               | 4         | 1.26%   |
| Goldmont         | 4         | 1.26%   |
| Bobcat           | 4         | 1.26%   |
| Tremont          | 1         | 0.31%   |
| Steamroller      | 1         | 0.31%   |
| Puma             | 1         | 0.31%   |
| K8 Hammer        | 1         | 0.31%   |
| Jaguar           | 1         | 0.31%   |
| Bonnell          | 1         | 0.31%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 220       | 51.89%  |
| Nvidia                           | 106       | 25%     |
| AMD                              | 95        | 22.41%  |
| Silicon Integrated Systems [SiS] | 2         | 0.47%   |
| VIA Technologies                 | 1         | 0.24%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 25        | 5.77%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 18        | 4.16%   |
| Intel HD Graphics 620                                                                    | 17        | 3.93%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 16        | 3.7%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 16        | 3.7%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 13        | 3%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 13        | 3%      |
| AMD Renoir                                                                               | 13        | 3%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 12        | 2.77%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 10        | 2.31%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 2.08%   |
| AMD Lucienne                                                                             | 9         | 2.08%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 8         | 1.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 1.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 1.85%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 7         | 1.62%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 7         | 1.62%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 1.39%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 1.39%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 1.39%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 6         | 1.39%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 5         | 1.15%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 5         | 1.15%   |
| Nvidia GM108M [GeForce 840M]                                                             | 5         | 1.15%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 1.15%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.15%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 1.15%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.92%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 4         | 0.92%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 0.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 0.92%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 4         | 0.92%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 0.92%   |
| Nvidia TU117M                                                                            | 3         | 0.69%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 0.69%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 0.69%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 0.69%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 3         | 0.69%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 0.69%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 3         | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 126       | 39.62%  |
| Intel + Nvidia | 72        | 22.64%  |
| 1 x AMD        | 55        | 17.3%   |
| Intel + AMD    | 21        | 6.6%    |
| 1 x Nvidia     | 20        | 6.29%   |
| AMD + Nvidia   | 14        | 4.4%    |
| 2 x AMD        | 5         | 1.57%   |
| 1 x SiS        | 2         | 0.63%   |
| Other          | 1         | 0.31%   |
| 2 x Intel      | 1         | 0.31%   |
| 1 x VIA        | 1         | 0.31%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 254       | 79.62%  |
| Proprietary | 55        | 17.24%  |
| Unknown     | 10        | 3.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 185       | 56.06%  |
| 1.01-2.0   | 49        | 14.85%  |
| 0.01-0.5   | 42        | 12.73%  |
| 3.01-4.0   | 32        | 9.7%    |
| 0.51-1.0   | 14        | 4.24%   |
| 7.01-8.0   | 5         | 1.52%   |
| 5.01-6.0   | 2         | 0.61%   |
| 2.01-3.0   | 1         | 0.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 64        | 17.02%  |
| BOE                     | 55        | 14.63%  |
| LG Display              | 51        | 13.56%  |
| Chimei Innolux          | 45        | 11.97%  |
| Samsung Electronics     | 40        | 10.64%  |
| Dell                    | 30        | 7.98%   |
| Sharp                   | 10        | 2.66%   |
| Lenovo                  | 8         | 2.13%   |
| Goldstar                | 7         | 1.86%   |
| PANDA                   | 6         | 1.6%    |
| CSO                     | 6         | 1.6%    |
| Apple                   | 6         | 1.6%    |
| AOC                     | 6         | 1.6%    |
| Chi Mei Optoelectronics | 5         | 1.33%   |
| LG Philips              | 4         | 1.06%   |
| Philips                 | 3         | 0.8%    |
| InfoVision              | 3         | 0.8%    |
| Quanta Display          | 2         | 0.53%   |
| Hewlett-Packard         | 2         | 0.53%   |
| Grundig                 | 2         | 0.53%   |
| BenQ                    | 2         | 0.53%   |
| Valve                   | 1         | 0.27%   |
| TMX                     | 1         | 0.27%   |
| Sony                    | 1         | 0.27%   |
| Panasonic               | 1         | 0.27%   |
| NCS                     | 1         | 0.27%   |
| MStar                   | 1         | 0.27%   |
| MSI                     | 1         | 0.27%   |
| InnoLux Display         | 1         | 0.27%   |
| Iiyama                  | 1         | 0.27%   |
| IBM                     | 1         | 0.27%   |
| HJW                     | 1         | 0.27%   |
| Fujitsu Siemens         | 1         | 0.27%   |
| Daewoo                  | 1         | 0.27%   |
| CPT                     | 1         | 0.27%   |
| BOE Technology Group    | 1         | 0.27%   |
| ASUSTek Computer        | 1         | 0.27%   |
| Ancor Communications    | 1         | 0.27%   |
| Achieva Shimian         | 1         | 0.27%   |
| Acer                    | 1         | 0.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 6         | 1.55%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 6         | 1.55%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch          | 4         | 1.04%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 4         | 1.04%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 4         | 1.04%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 4         | 1.04%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                 | 4         | 1.04%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 4         | 1.04%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 3         | 0.78%   |
| LG Display LCD Monitor LGD069A 1920x1080 344x194mm 15.5-inch          | 3         | 0.78%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch           | 3         | 0.78%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 3         | 0.78%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 3         | 0.78%   |
| Dell SE2717H/HX DELD0A1 1920x1080 598x336mm 27.0-inch                 | 3         | 0.78%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 3         | 0.78%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch        | 3         | 0.78%   |
| AOC 27B2 AOC2702 1920x1080 598x336mm 27.0-inch                        | 3         | 0.78%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 2         | 0.52%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 2         | 0.52%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 2         | 0.52%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 0.52%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 2         | 0.52%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 309x174mm 14.0-inch  | 2         | 0.52%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 2         | 0.52%   |
| Quanta Display LCD Monitor QDS002D 1400x1050 285x214mm 14.0-inch      | 2         | 0.52%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch           | 2         | 0.52%   |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch          | 2         | 0.52%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 2         | 0.52%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch          | 2         | 0.52%   |
| LG Display LCD Monitor LGD0289 1600x900 382x215mm 17.3-inch           | 2         | 0.52%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch           | 2         | 0.52%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 2         | 0.52%   |
| Grundig WXGA GRU4448 1600x1200                                        | 2         | 0.52%   |
| Goldstar 22EN43 GSM59D8 1920x1080 477x268mm 21.5-inch                 | 2         | 0.52%   |
| Dell U3219Q DELA124 3840x2160 697x392mm 31.5-inch                     | 2         | 0.52%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2         | 0.52%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                    | 2         | 0.52%   |
| Dell S2421HN DEL41F1 1920x1080 527x296mm 23.8-inch                    | 2         | 0.52%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 2         | 0.52%   |
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                     | 2         | 0.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 174       | 49.71%  |
| 1366x768 (WXGA)    | 58        | 16.57%  |
| 1600x900 (HD+)     | 25        | 7.14%   |
| 3840x2160 (4K)     | 20        | 5.71%   |
| 2560x1440 (QHD)    | 14        | 4%      |
| 1440x900 (WXGA+)   | 10        | 2.86%   |
| 1280x800 (WXGA)    | 9         | 2.57%   |
| 1680x1050 (WSXGA+) | 6         | 1.71%   |
| 2560x1600          | 5         | 1.43%   |
| 1920x1200 (WUXGA)  | 5         | 1.43%   |
| 2880x1800          | 4         | 1.14%   |
| 2160x1440          | 3         | 0.86%   |
| 1280x1024 (SXGA)   | 3         | 0.86%   |
| 3840x2400          | 2         | 0.57%   |
| 3440x1440          | 2         | 0.57%   |
| 1400x1050          | 2         | 0.57%   |
| 800x1280           | 1         | 0.29%   |
| 3200x2000          | 1         | 0.29%   |
| 2560x1080          | 1         | 0.29%   |
| 1920x1280          | 1         | 0.29%   |
| 1280x960           | 1         | 0.29%   |
| 1280x720 (HD)      | 1         | 0.29%   |
| 1024x600           | 1         | 0.29%   |
| 1024x576           | 1         | 0.29%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 169       | 44.47%  |
| 17      | 46        | 12.11%  |
| 14      | 34        | 8.95%   |
| 13      | 33        | 8.68%   |
| 27      | 23        | 6.05%   |
| 24      | 16        | 4.21%   |
| 23      | 9         | 2.37%   |
| 21      | 7         | 1.84%   |
| 12      | 7         | 1.84%   |
| 54      | 6         | 1.58%   |
| 31      | 5         | 1.32%   |
| 16      | 5         | 1.32%   |
| 34      | 3         | 0.79%   |
| Unknown | 3         | 0.79%   |
| 20      | 2         | 0.53%   |
| 10      | 2         | 0.53%   |
| 72      | 1         | 0.26%   |
| 52      | 1         | 0.26%   |
| 49      | 1         | 0.26%   |
| 38      | 1         | 0.26%   |
| 26      | 1         | 0.26%   |
| 25      | 1         | 0.26%   |
| 22      | 1         | 0.26%   |
| 18      | 1         | 0.26%   |
| 11      | 1         | 0.26%   |
| 7       | 1         | 0.26%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 217       | 58.02%  |
| 351-400     | 49        | 13.1%   |
| 501-600     | 41        | 10.96%  |
| 201-300     | 29        | 7.75%   |
| 401-500     | 12        | 3.21%   |
| 601-700     | 9         | 2.41%   |
| 1001-1500   | 8         | 2.14%   |
| 701-800     | 3         | 0.8%    |
| Unknown     | 3         | 0.8%    |
| 801-900     | 1         | 0.27%   |
| 1501-2000   | 1         | 0.27%   |
| 1-100       | 1         | 0.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 261       | 81.82%  |
| 16/10   | 43        | 13.48%  |
| 3/2     | 5         | 1.57%   |
| 4/3     | 3         | 0.94%   |
| 21/9    | 3         | 0.94%   |
| 5/4     | 2         | 0.63%   |
| 0.67    | 1         | 0.31%   |
| Unknown | 1         | 0.31%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 167       | 44.06%  |
| 81-90          | 55        | 14.51%  |
| 121-130        | 37        | 9.76%   |
| 301-350        | 24        | 6.33%   |
| 201-250        | 24        | 6.33%   |
| 71-80          | 11        | 2.9%    |
| More than 1000 | 9         | 2.37%   |
| 351-500        | 8         | 2.11%   |
| 131-140        | 7         | 1.85%   |
| 61-70          | 6         | 1.58%   |
| 151-200        | 6         | 1.58%   |
| 111-120        | 6         | 1.58%   |
| 251-300        | 5         | 1.32%   |
| 141-150        | 3         | 0.79%   |
| 91-100         | 3         | 0.79%   |
| Unknown        | 3         | 0.79%   |
| 41-50          | 2         | 0.53%   |
| 51-60          | 1         | 0.26%   |
| 1-40           | 1         | 0.26%   |
| 501-1000       | 1         | 0.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 174       | 47.15%  |
| 101-120       | 89        | 24.12%  |
| 51-100        | 62        | 16.8%   |
| 161-240       | 23        | 6.23%   |
| More than 240 | 9         | 2.44%   |
| 1-50          | 9         | 2.44%   |
| Unknown       | 3         | 0.81%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 247       | 74.62%  |
| 2     | 64        | 19.34%  |
| 0     | 10        | 3.02%   |
| 3     | 9         | 2.72%   |
| 4     | 1         | 0.3%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 185       | 35.85%  |
| Intel                             | 163       | 31.59%  |
| Qualcomm Atheros                  | 75        | 14.53%  |
| Broadcom                          | 26        | 5.04%   |
| MediaTek                          | 15        | 2.91%   |
| Broadcom Limited                  | 8         | 1.55%   |
| TP-Link                           | 5         | 0.97%   |
| Samsung Electronics               | 4         | 0.78%   |
| Marvell Technology Group          | 4         | 0.78%   |
| Xiaomi                            | 3         | 0.58%   |
| Lenovo                            | 3         | 0.58%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.39%   |
| Ralink Technology                 | 2         | 0.39%   |
| Ralink                            | 2         | 0.39%   |
| Qualcomm Atheros Communications   | 2         | 0.39%   |
| Qualcomm                          | 2         | 0.39%   |
| Ericsson Business Mobile Networks | 2         | 0.39%   |
| Dell                              | 2         | 0.39%   |
| D-Link                            | 2         | 0.39%   |
| ASIX Electronics                  | 2         | 0.39%   |
| VIA Technologies                  | 1         | 0.19%   |
| Nvidia                            | 1         | 0.19%   |
| Huawei Technologies               | 1         | 0.19%   |
| HTC (High Tech Computer)          | 1         | 0.19%   |
| Hewlett-Packard                   | 1         | 0.19%   |
| Fibocom                           | 1         | 0.19%   |
| DisplayLink                       | 1         | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 131       | 21.69%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 22        | 3.64%   |
| Intel Wireless 8265 / 8275                                              | 22        | 3.64%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 19        | 3.15%   |
| Intel Wi-Fi 6 AX200                                                     | 18        | 2.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 15        | 2.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 15        | 2.48%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 11        | 1.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 10        | 1.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 10        | 1.66%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 1.66%   |
| Intel Ethernet Connection (4) I219-V                                    | 9         | 1.49%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 9         | 1.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 1.32%   |
| Intel Wireless 7260                                                     | 8         | 1.32%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 1.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 8         | 1.32%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 1.16%   |
| Intel Wireless 7265                                                     | 7         | 1.16%   |
| Intel Wireless 3165                                                     | 7         | 1.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 1.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 0.99%   |
| Intel Wireless 3160                                                     | 6         | 0.99%   |
| Intel Ethernet Connection I217-LM                                       | 6         | 0.99%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 0.99%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 6         | 0.99%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 0.99%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 5         | 0.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 0.83%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 0.83%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 0.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 0.66%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 4         | 0.66%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 4         | 0.66%   |
| Intel Wireless-AC 9260                                                  | 4         | 0.66%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.66%   |
| Intel Centrino Advanced-N 6235                                          | 4         | 0.66%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 3         | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                           | 3         | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 3         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 161       | 49.85%  |
| Qualcomm Atheros                | 65        | 20.12%  |
| Realtek Semiconductor           | 42        | 13%     |
| Broadcom                        | 18        | 5.57%   |
| MediaTek                        | 15        | 4.64%   |
| TP-Link                         | 5         | 1.55%   |
| Broadcom Limited                | 4         | 1.24%   |
| Ralink Technology               | 2         | 0.62%   |
| Ralink                          | 2         | 0.62%   |
| Qualcomm Atheros Communications | 2         | 0.62%   |
| Qualcomm                        | 2         | 0.62%   |
| Dell                            | 2         | 0.62%   |
| D-Link                          | 2         | 0.62%   |
| Fibocom                         | 1         | 0.31%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 22        | 6.79%   |
| Intel Wireless 8265 / 8275                                              | 22        | 6.79%   |
| Intel Wi-Fi 6 AX200                                                     | 18        | 5.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 15        | 4.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 15        | 4.63%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 11        | 3.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 10        | 3.09%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 3.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 9         | 2.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 2.47%   |
| Intel Wireless 7260                                                     | 8         | 2.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 2.47%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 2.16%   |
| Intel Wireless 7265                                                     | 7         | 2.16%   |
| Intel Wireless 3165                                                     | 7         | 2.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 2.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 1.85%   |
| Intel Wireless 3160                                                     | 6         | 1.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 1.85%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 6         | 1.85%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 1.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 1.54%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 1.54%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 1.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.23%   |
| Intel Wireless-AC 9260                                                  | 4         | 1.23%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 1.23%   |
| Intel Centrino Advanced-N 6235                                          | 4         | 1.23%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 3         | 0.93%   |
| Intel WiFi Link 5100                                                    | 3         | 0.93%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 0.93%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.93%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 3         | 0.93%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 0.93%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 0.62%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.62%   |
| Qualcomm QCA6390 Wireless Network Adapter                               | 2         | 0.62%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.62%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.62%   |
| Intel Wireless 8260                                                     | 2         | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 165       | 60.22%  |
| Intel                            | 54        | 19.71%  |
| Qualcomm Atheros                 | 20        | 7.3%    |
| Broadcom                         | 8         | 2.92%   |
| Samsung Electronics              | 4         | 1.46%   |
| Marvell Technology Group         | 4         | 1.46%   |
| Broadcom Limited                 | 4         | 1.46%   |
| Xiaomi                           | 3         | 1.09%   |
| Lenovo                           | 3         | 1.09%   |
| Silicon Integrated Systems [SiS] | 2         | 0.73%   |
| ASIX Electronics                 | 2         | 0.73%   |
| VIA Technologies                 | 1         | 0.36%   |
| Nvidia                           | 1         | 0.36%   |
| Huawei Technologies              | 1         | 0.36%   |
| HTC (High Tech Computer)         | 1         | 0.36%   |
| DisplayLink                      | 1         | 0.36%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 131       | 47.64%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 19        | 6.91%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 3.64%   |
| Intel Ethernet Connection (4) I219-V                              | 9         | 3.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 2.91%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 2.18%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 5         | 1.82%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 1.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4         | 1.45%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 1.09%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 1.09%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 3         | 1.09%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.09%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.09%   |
| Intel Ethernet Connection (13) I219-V                             | 3         | 1.09%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 1.09%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.73%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 0.73%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.73%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 0.73%   |
| Lenovo USB-C Dock Ethernet                                        | 2         | 0.73%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.73%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.73%   |
| Intel Ethernet Connection (16) I219-V                             | 2         | 0.73%   |
| Intel Ethernet Connection (13) I219-LM                            | 2         | 0.73%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.73%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 0.73%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 2         | 0.73%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 0.73%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.36%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.36%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.36%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.36%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.36%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.36%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.36%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.36%   |
| Nvidia MCP67 Ethernet                                             | 1         | 0.36%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.36%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 312       | 53.98%  |
| Ethernet | 261       | 45.16%  |
| Modem    | 4         | 0.69%   |
| Unknown  | 1         | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 270       | 78.72%  |
| Ethernet | 73        | 21.28%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 239       | 75.16%  |
| 1     | 75        | 23.58%  |
| 0     | 3         | 0.94%   |
| 3     | 1         | 0.31%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 305       | 95.61%  |
| Yes  | 14        | 4.39%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 126       | 47.55%  |
| Realtek Semiconductor           | 27        | 10.19%  |
| Lite-On Technology              | 26        | 9.81%   |
| Qualcomm Atheros Communications | 23        | 8.68%   |
| IMC Networks                    | 19        | 7.17%   |
| Foxconn / Hon Hai               | 10        | 3.77%   |
| Broadcom                        | 9         | 3.4%    |
| Hewlett-Packard                 | 6         | 2.26%   |
| Apple                           | 6         | 2.26%   |
| Cambridge Silicon Radio         | 5         | 1.89%   |
| Toshiba                         | 3         | 1.13%   |
| Foxconn International           | 3         | 1.13%   |
| Realtek                         | 1         | 0.38%   |
| Dell                            | 1         | 0.38%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 51        | 19.25%  |
| Intel AX201 Bluetooth                               | 25        | 9.43%   |
| Realtek Bluetooth Radio                             | 23        | 8.68%   |
| Intel AX200 Bluetooth                               | 18        | 6.79%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 15        | 5.66%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 13        | 4.91%   |
| IMC Networks Bluetooth Radio                        | 9         | 3.4%    |
| Qualcomm Atheros  Bluetooth Device                  | 8         | 3.02%   |
| Intel Wireless-AC 3168 Bluetooth                    | 8         | 3.02%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 2.26%   |
| IMC Networks Wireless_Device                        | 6         | 2.26%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 1.89%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5         | 1.89%   |
| Lite-On Wireless_Device                             | 4         | 1.51%   |
| Lite-On Bluetooth Device                            | 4         | 1.51%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 1.51%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 1.13%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 1.13%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 1.13%   |
| Intel Bluetooth Device                              | 3         | 1.13%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 1.13%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 1.13%   |
| Broadcom BCM2045 Bluetooth                          | 3         | 1.13%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.75%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.75%   |
| IMC Networks Bluetooth Device                       | 2         | 0.75%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 0.75%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 2         | 0.75%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 0.75%   |
| Apple Bluetooth USB Host Controller                 | 2         | 0.75%   |
| Apple Bluetooth Host Controller                     | 2         | 0.75%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.38%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)          | 1         | 0.38%   |
| Toshiba Bluetooth Device                            | 1         | 0.38%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.38%   |
| Realtek Bluetooth Radio                             | 1         | 0.38%   |
| Qualcomm Atheros Bluetooth                          | 1         | 0.38%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.38%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.38%   |
| Lite-On Atheros Bluetooth                           | 1         | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 241       | 60.55%  |
| AMD                              | 77        | 19.35%  |
| Nvidia                           | 45        | 11.31%  |
| Logitech                         | 5         | 1.26%   |
| Lenovo                           | 5         | 1.26%   |
| C-Media Electronics              | 5         | 1.26%   |
| JMTek                            | 4         | 1.01%   |
| Silicon Integrated Systems [SiS] | 2         | 0.5%    |
| ZOOM                             | 1         | 0.25%   |
| YZ Technology                    | 1         | 0.25%   |
| VIA Technologies                 | 1         | 0.25%   |
| Trust                            | 1         | 0.25%   |
| Texas Instruments                | 1         | 0.25%   |
| SteelSeries ApS                  | 1         | 0.25%   |
| Samsung Electronics              | 1         | 0.25%   |
| Samson Technologies              | 1         | 0.25%   |
| Realtek Semiconductor            | 1         | 0.25%   |
| Plantronics                      | 1         | 0.25%   |
| Pioneer DJ                       | 1         | 0.25%   |
| M-Audio                          | 1         | 0.25%   |
| GN Netcom                        | 1         | 0.25%   |
| BEHRINGER International          | 1         | 0.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 54        | 11%     |
| Intel Sunrise Point-LP HD Audio                                                                   | 47        | 9.57%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 25        | 5.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 21        | 4.28%   |
| Intel Cannon Lake PCH cAVS                                                                        | 17        | 3.46%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 17        | 3.46%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 16        | 3.26%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 16        | 3.26%   |
| Intel 8 Series HD Audio Controller                                                                | 16        | 3.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 15        | 3.05%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 15        | 3.05%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 12        | 2.44%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 11        | 2.24%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 10        | 2.04%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 9         | 1.83%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 1.83%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 8         | 1.63%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 7         | 1.43%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 1.43%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 1.43%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 7         | 1.43%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 1.22%   |
| Intel Comet Lake PCH cAVS                                                                         | 6         | 1.22%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 1.22%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 6         | 1.22%   |
| AMD High Definition Audio Controller                                                              | 6         | 1.22%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 1.02%   |
| Nvidia Audio device                                                                               | 4         | 0.81%   |
| JMTek USB PnP Audio Device                                                                        | 4         | 0.81%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 0.81%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 0.81%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 0.81%   |
| AMD FCH Azalia Controller                                                                         | 4         | 0.81%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.61%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 0.61%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.61%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 0.61%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 3         | 0.61%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 64        | 28.96%  |
| SK hynix            | 52        | 23.53%  |
| Kingston            | 34        | 15.38%  |
| Micron Technology   | 30        | 13.57%  |
| Crucial             | 13        | 5.88%   |
| Unknown             | 9         | 4.07%   |
| Ramaxel Technology  | 5         | 2.26%   |
| Elpida              | 3         | 1.36%   |
| Patriot             | 2         | 0.9%    |
| A-DATA Technology   | 2         | 0.9%    |
| Unknown (ABCD)      | 1         | 0.45%   |
| Transcend           | 1         | 0.45%   |
| Qimonda             | 1         | 0.45%   |
| G.Skill             | 1         | 0.45%   |
| Corsair             | 1         | 0.45%   |
| Avant               | 1         | 0.45%   |
| 48spaces            | 1         | 0.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s         | 8         | 3.35%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s         | 5         | 2.09%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 4         | 1.67%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 4         | 1.67%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s          | 4         | 1.67%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s       | 4         | 1.67%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 3         | 1.26%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s       | 3         | 1.26%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 3         | 1.26%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s         | 3         | 1.26%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s         | 3         | 1.26%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s           | 2         | 0.84%   |
| SK hynix RAM HMT125S6TFR8C-H9 2GB SODIMM DDR3 1334MT/s        | 2         | 0.84%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s        | 2         | 0.84%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s        | 2         | 0.84%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 2         | 0.84%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s    | 2         | 0.84%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                | 2         | 0.84%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s         | 2         | 0.84%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s         | 2         | 0.84%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 2         | 0.84%   |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s  | 2         | 0.84%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s        | 2         | 0.84%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s         | 2         | 0.84%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s         | 2         | 0.84%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s  | 2         | 0.84%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.84%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s          | 2         | 0.84%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s         | 2         | 0.84%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4GB SODIMM DDR4 2133MT/s         | 2         | 0.84%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s         | 2         | 0.84%   |
| Kingston RAM 9905712-034.A00G 16GB SODIMM DDR4 2400MT/s       | 2         | 0.84%   |
| Kingston RAM 9905700-047.A00G 16GB SODIMM DDR4 2667MT/s       | 2         | 0.84%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                    | 2         | 0.84%   |
| Unknown RAM Module 512MB SODIMM DDR2                          | 1         | 0.42%   |
| Unknown RAM Module 4GB SODIMM 800MT/s                         | 1         | 0.42%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR3 1867MT/s           | 1         | 0.42%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2400MT/s                | 1         | 0.42%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                    | 1         | 0.42%   |
| Unknown RAM Module 2GB SODIMM DDR2                            | 1         | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 94        | 52.51%  |
| DDR3    | 52        | 29.05%  |
| LPDDR3  | 9         | 5.03%   |
| DDR2    | 9         | 5.03%   |
| LPDDR4  | 8         | 4.47%   |
| DDR5    | 3         | 1.68%   |
| LPDDR5  | 2         | 1.12%   |
| SDRAM   | 1         | 0.56%   |
| Unknown | 1         | 0.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 158       | 86.81%  |
| Row Of Chips | 21        | 11.54%  |
| DIMM         | 2         | 1.1%    |
| Chip         | 1         | 0.55%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 83        | 42.13%  |
| 4096  | 55        | 27.92%  |
| 16384 | 31        | 15.74%  |
| 2048  | 13        | 6.6%    |
| 32768 | 8         | 4.06%   |
| 1024  | 6         | 3.05%   |
| 512   | 1         | 0.51%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 46        | 23.59%  |
| 2667    | 44        | 22.56%  |
| 1600    | 41        | 21.03%  |
| 2133    | 10        | 5.13%   |
| 2400    | 9         | 4.62%   |
| 1334    | 7         | 3.59%   |
| 667     | 6         | 3.08%   |
| 4267    | 3         | 1.54%   |
| 3266    | 3         | 1.54%   |
| 1333    | 3         | 1.54%   |
| 1066    | 3         | 1.54%   |
| 6400    | 2         | 1.03%   |
| 4800    | 2         | 1.03%   |
| 4266    | 2         | 1.03%   |
| 1867    | 2         | 1.03%   |
| 800     | 2         | 1.03%   |
| 8400    | 1         | 0.51%   |
| 5600    | 1         | 0.51%   |
| 3000    | 1         | 0.51%   |
| 2933    | 1         | 0.51%   |
| 2048    | 1         | 0.51%   |
| 1800    | 1         | 0.51%   |
| 1067    | 1         | 0.51%   |
| 975     | 1         | 0.51%   |
| 533     | 1         | 0.51%   |
| Unknown | 1         | 0.51%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 50%     |
| Canon               | 2         | 33.33%  |
| Samsung Electronics | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Samsung Composite Device        | 1         | 16.67%  |
| HP LaserJet P1005               | 1         | 16.67%  |
| HP LaserJet 400 colorMFP M475dw | 1         | 16.67%  |
| HP Deskjet 1050 J410            | 1         | 16.67%  |
| Canon PIXMA iP4300 Printer      | 1         | 16.67%  |
| Canon LBP6670 UFR II            | 1         | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Ultima Electronics | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| Ultima Artec Ultima 2000 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 82        | 27.99%  |
| IMC Networks                           | 36        | 12.29%  |
| Quanta                                 | 34        | 11.6%   |
| Realtek Semiconductor                  | 24        | 8.19%   |
| Microdia                               | 16        | 5.46%   |
| Bison Electronics                      | 13        | 4.44%   |
| Suyin                                  | 12        | 4.1%    |
| Sunplus Innovation Technology          | 12        | 4.1%    |
| Lite-On Technology                     | 9         | 3.07%   |
| Syntek                                 | 8         | 2.73%   |
| Acer                                   | 7         | 2.39%   |
| Luxvisions Innotech Limited            | 6         | 2.05%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 2.05%   |
| Logitech                               | 5         | 1.71%   |
| Apple                                  | 4         | 1.37%   |
| SunplusIT                              | 2         | 0.68%   |
| Sonix Technology                       | 2         | 0.68%   |
| Silicon Motion                         | 2         | 0.68%   |
| Jieli Technology                       | 2         | 0.68%   |
| Anker                                  | 2         | 0.68%   |
| Z-Star Microelectronics                | 1         | 0.34%   |
| Xiaomi                                 | 1         | 0.34%   |
| Ricoh                                  | 1         | 0.34%   |
| Primax Electronics                     | 1         | 0.34%   |
| Goertek Electronics                    | 1         | 0.34%   |
| Genesys Logic                          | 1         | 0.34%   |
| Cubeternet                             | 1         | 0.34%   |
| Colorado                               | 1         | 0.34%   |
| AVerMedia Technologies                 | 1         | 0.34%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 15        | 5.12%   |
| Chicony HD WebCam                             | 15        | 5.12%   |
| IMC Networks Integrated Camera                | 13        | 4.44%   |
| Quanta VGA WebCam                             | 9         | 3.07%   |
| Microdia Integrated_Webcam_HD                 | 9         | 3.07%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 9         | 3.07%   |
| IMC Networks USB2.0 HD UVC WebCam             | 8         | 2.73%   |
| Quanta HD User Facing                         | 7         | 2.39%   |
| Realtek Integrated_Webcam_HD                  | 6         | 2.05%   |
| Quanta HD Webcam                              | 5         | 1.71%   |
| Lite-On HP HD Camera                          | 5         | 1.71%   |
| Bison Integrated Camera                       | 5         | 1.71%   |
| Syntek Integrated Camera                      | 4         | 1.37%   |
| Suyin Acer/HP Integrated Webcam [CN0314]      | 4         | 1.37%   |
| Quanta HP TrueVision HD Camera                | 4         | 1.37%   |
| Quanta HP HD Camera                           | 4         | 1.37%   |
| Chicony HP Webcam                             | 4         | 1.37%   |
| Sunplus Integrated_Webcam_HD                  | 3         | 1.02%   |
| Sunplus Asus Webcam                           | 3         | 1.02%   |
| Realtek Lenovo EasyCamera                     | 3         | 1.02%   |
| Realtek Integrated Webcam                     | 3         | 1.02%   |
| Lite-On Integrated Camera                     | 3         | 1.02%   |
| Chicony USB2.0 VGA UVC WebCam                 | 3         | 1.02%   |
| Chicony USB2.0 HD UVC WebCam                  | 3         | 1.02%   |
| Chicony Integrated HP HD Webcam               | 3         | 1.02%   |
| Chicony HP Wide Vision HD Camera              | 3         | 1.02%   |
| Chicony HP Wide Vision HD                     | 3         | 1.02%   |
| Chicony HP HD Camera                          | 3         | 1.02%   |
| Chicony HD User Facing                        | 3         | 1.02%   |
| Acer Lenovo EasyCamera                        | 3         | 1.02%   |
| Suyin WebCam                                  | 2         | 0.68%   |
| Suyin HP TrueVision HD Integrated Webcam      | 2         | 0.68%   |
| SunplusIT MTD camera                          | 2         | 0.68%   |
| Sunplus HD WebCam                             | 2         | 0.68%   |
| Realtek HD WebCam                             | 2         | 0.68%   |
| Realtek EasyCamera                            | 2         | 0.68%   |
| Realtek Acer 640 x 480 laptop camera          | 2         | 0.68%   |
| Microdia Laptop_Integrated_Webcam_HD          | 2         | 0.68%   |
| Microdia Integrated Webcam                    | 2         | 0.68%   |
| Luxvisions Innotech Limited Integrated Camera | 2         | 0.68%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 25        | 35.21%  |
| Validity Sensors           | 15        | 21.13%  |
| Shenzhen Goodix Technology | 11        | 15.49%  |
| AuthenTec                  | 6         | 8.45%   |
| LighTuning Technology      | 5         | 7.04%   |
| Upek                       | 4         | 5.63%   |
| Elan Microelectronics      | 4         | 5.63%   |
| STMicroelectronics         | 1         | 1.41%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 8         | 11.27%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 9.86%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 7.04%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 7.04%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 5.63%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 5.63%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 5.63%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 4.23%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 4.23%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 4.23%   |
| AuthenTec AES2810                                                          | 3         | 4.23%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 4.23%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 2.82%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 2.82%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 2.82%   |
| Elan WBF Fingerprint Sensor                                                | 2         | 2.82%   |
| Elan ELAN:Fingerprint                                                      | 2         | 2.82%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.41%   |
| Validity Sensors VFS491                                                    | 1         | 1.41%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 1.41%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 1.41%   |
| Synaptics WBDI                                                             | 1         | 1.41%   |
| Synaptics UWP WBDI                                                         | 1         | 1.41%   |
| Synaptics  WBDI                                                            | 1         | 1.41%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 1.41%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.41%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 8         | 44.44%  |
| Broadcom              | 5         | 27.78%  |
| Lenovo                | 3         | 16.67%  |
| Upek                  | 1         | 5.56%   |
| Realtek Semiconductor | 1         | 5.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 8         | 44.44%  |
| Lenovo Integrated Smart Card Reader                        | 3         | 16.67%  |
| Broadcom 58200                                             | 3         | 16.67%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 5.56%   |
| Realtek Semiconductor Smart Card Reader Interface          | 1         | 5.56%   |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 5.56%   |
| Broadcom 5880                                              | 1         | 5.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 198       | 60.18%  |
| 1     | 104       | 31.61%  |
| 2     | 23        | 6.99%   |
| 3     | 4         | 1.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 70        | 43.75%  |
| Graphics card            | 30        | 18.75%  |
| Net/wireless             | 16        | 10%     |
| Chipcard                 | 16        | 10%     |
| Multimedia controller    | 12        | 7.5%    |
| Camera                   | 5         | 3.13%   |
| Card reader              | 3         | 1.88%   |
| Storage                  | 2         | 1.25%   |
| Communication controller | 2         | 1.25%   |
| Storage/ide              | 1         | 0.63%   |
| Sound                    | 1         | 0.63%   |
| Modem                    | 1         | 0.63%   |
| Flash memory             | 1         | 0.63%   |


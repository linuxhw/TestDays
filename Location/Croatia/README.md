Linux in Croatia - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Croatia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Croatia/Desktop/README.md) and [notebooks](/Location/Croatia/Notebook/README.md).

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

Total: 788

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [58bbd67a73](https://linux-hardware.org/?probe=58bbd67a73) | Dec 23, 2023 |
| Acer          | Aspire A3SP14-31PT          | Convertible | [d9850a7566](https://linux-hardware.org/?probe=d9850a7566) | Dec 23, 2023 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [155e0f1c37](https://linux-hardware.org/?probe=155e0f1c37) | Dec 22, 2023 |
| Dell          | 0R790T A00                  | Desktop     | [8a72b2a4ce](https://linux-hardware.org/?probe=8a72b2a4ce) | Dec 13, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [656732b40e](https://linux-hardware.org/?probe=656732b40e) | Dec 12, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [367489ed4f](https://linux-hardware.org/?probe=367489ed4f) | Dec 10, 2023 |
| eMachines     | ET1850                      | Desktop     | [b433ca3cfa](https://linux-hardware.org/?probe=b433ca3cfa) | Dec 02, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [0137a4a556](https://linux-hardware.org/?probe=0137a4a556) | Nov 23, 2023 |
| eMachines     | E725 V1.03                  | Notebook    | [bd5b32a320](https://linux-hardware.org/?probe=bd5b32a320) | Nov 20, 2023 |
| eMachines     | E725 V1.03                  | Notebook    | [bd29f2ff41](https://linux-hardware.org/?probe=bd29f2ff41) | Nov 19, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [2a9ba6fc77](https://linux-hardware.org/?probe=2a9ba6fc77) | Nov 17, 2023 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [9b2d42ff24](https://linux-hardware.org/?probe=9b2d42ff24) | Nov 15, 2023 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [f5413c3dd5](https://linux-hardware.org/?probe=f5413c3dd5) | Nov 15, 2023 |
| HP            | 18E4                        | Desktop     | [fb73ea4228](https://linux-hardware.org/?probe=fb73ea4228) | Nov 12, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [982139b13a](https://linux-hardware.org/?probe=982139b13a) | Nov 11, 2023 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [4fd542edf2](https://linux-hardware.org/?probe=4fd542edf2) | Nov 11, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [c019f410aa](https://linux-hardware.org/?probe=c019f410aa) | Nov 08, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [4bfe797838](https://linux-hardware.org/?probe=4bfe797838) | Nov 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [4b04b9ef25](https://linux-hardware.org/?probe=4b04b9ef25) | Nov 02, 2023 |
| Acer          | AOD270                      | Notebook    | [83c4a5920f](https://linux-hardware.org/?probe=83c4a5920f) | Oct 29, 2023 |
| Lenovo        | ThinkPad T450s 20BWS58K0... | Notebook    | [11b2f76301](https://linux-hardware.org/?probe=11b2f76301) | Oct 29, 2023 |
| HP            | Presario CQ57               | Notebook    | [f35a975672](https://linux-hardware.org/?probe=f35a975672) | Oct 29, 2023 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [bd82dd57be](https://linux-hardware.org/?probe=bd82dd57be) | Oct 27, 2023 |
| Intel         | NUC7i7BNB J31145-303        | Mini pc     | [8b6a0fb21d](https://linux-hardware.org/?probe=8b6a0fb21d) | Oct 25, 2023 |
| ASRock        | B650E PG Riptide WiFi       | Desktop     | [24304767eb](https://linux-hardware.org/?probe=24304767eb) | Oct 21, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [deeaf6af5b](https://linux-hardware.org/?probe=deeaf6af5b) | Oct 19, 2023 |
| Intel         | DG965RY AAD41691-301        | Desktop     | [0bdf442d3d](https://linux-hardware.org/?probe=0bdf442d3d) | Oct 19, 2023 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [c8f55c449a](https://linux-hardware.org/?probe=c8f55c449a) | Oct 19, 2023 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [0e6cc9fc48](https://linux-hardware.org/?probe=0e6cc9fc48) | Oct 16, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [6c49286a6c](https://linux-hardware.org/?probe=6c49286a6c) | Oct 14, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [bf88efbfff](https://linux-hardware.org/?probe=bf88efbfff) | Oct 05, 2023 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [e0158c541c](https://linux-hardware.org/?probe=e0158c541c) | Sep 29, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [7975260826](https://linux-hardware.org/?probe=7975260826) | Sep 29, 2023 |
| Dell          | Latitude 5431               | Notebook    | [d9ea685862](https://linux-hardware.org/?probe=d9ea685862) | Sep 27, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [fac9ee2e6e](https://linux-hardware.org/?probe=fac9ee2e6e) | Sep 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [0e32901b18](https://linux-hardware.org/?probe=0e32901b18) | Sep 27, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [88653e2f06](https://linux-hardware.org/?probe=88653e2f06) | Sep 24, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [5a6ff779bd](https://linux-hardware.org/?probe=5a6ff779bd) | Sep 19, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [bd389fb2a0](https://linux-hardware.org/?probe=bd389fb2a0) | Sep 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [c8ee0a00a5](https://linux-hardware.org/?probe=c8ee0a00a5) | Sep 06, 2023 |
| Lenovo        | ThinkCentre A58 77057FG     | Desktop     | [b96c23b77b](https://linux-hardware.org/?probe=b96c23b77b) | Sep 04, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [c833e40c97](https://linux-hardware.org/?probe=c833e40c97) | Sep 01, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [ba837274bd](https://linux-hardware.org/?probe=ba837274bd) | Sep 01, 2023 |
| Acer          | Predator PH517-51           | Notebook    | [294343383a](https://linux-hardware.org/?probe=294343383a) | Aug 30, 2023 |
| Acer          | Predator PH517-51           | Notebook    | [adba295596](https://linux-hardware.org/?probe=adba295596) | Aug 30, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [caaf599d6a](https://linux-hardware.org/?probe=caaf599d6a) | Aug 29, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [f91274084a](https://linux-hardware.org/?probe=f91274084a) | Aug 29, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [4bc3ed94ce](https://linux-hardware.org/?probe=4bc3ed94ce) | Aug 28, 2023 |
| Intel         | DH61CR AAG14064-204         | Desktop     | [2fa0bbc7ec](https://linux-hardware.org/?probe=2fa0bbc7ec) | Aug 28, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [8acc158836](https://linux-hardware.org/?probe=8acc158836) | Aug 27, 2023 |
| ASRock        | B560 Steel Legend           | Desktop     | [b2e8cd4ed2](https://linux-hardware.org/?probe=b2e8cd4ed2) | Aug 26, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [1f6e4f9676](https://linux-hardware.org/?probe=1f6e4f9676) | Aug 21, 2023 |
| Lenovo        | ThinkPad T495s 20QJ001MG... | Notebook    | [3ac30cf2d0](https://linux-hardware.org/?probe=3ac30cf2d0) | Aug 16, 2023 |
| HP            | EliteBook 840 14 inch G1... | Notebook    | [73b7fc1fc9](https://linux-hardware.org/?probe=73b7fc1fc9) | Aug 11, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [ee8f18e185](https://linux-hardware.org/?probe=ee8f18e185) | Aug 07, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [de1addc70b](https://linux-hardware.org/?probe=de1addc70b) | Aug 03, 2023 |
| ASUSTek       | X540NA                      | Notebook    | [c7724d9c7c](https://linux-hardware.org/?probe=c7724d9c7c) | Aug 02, 2023 |
| HP            | 2B47                        | Desktop     | [06373794be](https://linux-hardware.org/?probe=06373794be) | Aug 01, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | Notebook    | [8b7ca3c460](https://linux-hardware.org/?probe=8b7ca3c460) | Jul 21, 2023 |
| Dell          | Latitude 5520               | Notebook    | [070380568b](https://linux-hardware.org/?probe=070380568b) | Jul 21, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [043258de54](https://linux-hardware.org/?probe=043258de54) | Jul 17, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [567736ec02](https://linux-hardware.org/?probe=567736ec02) | Jul 14, 2023 |
| Acer          | Swift SF314-58G             | Notebook    | [795625662c](https://linux-hardware.org/?probe=795625662c) | Jul 12, 2023 |
| Acer          | Swift SF314-58G             | Notebook    | [c01b74af46](https://linux-hardware.org/?probe=c01b74af46) | Jul 12, 2023 |
| Dell          | OptiPlex 9020               | Notebook    | [3384a64b67](https://linux-hardware.org/?probe=3384a64b67) | Jul 10, 2023 |
| Timi          | TM1701                      | Notebook    | [5dee3c6b81](https://linux-hardware.org/?probe=5dee3c6b81) | Jul 01, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [8f6d75c75e](https://linux-hardware.org/?probe=8f6d75c75e) | Jun 22, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [c1472b1c25](https://linux-hardware.org/?probe=c1472b1c25) | Jun 18, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [289d9fe165](https://linux-hardware.org/?probe=289d9fe165) | Jun 14, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [18e80281cc](https://linux-hardware.org/?probe=18e80281cc) | Jun 10, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [f7bd03dbb9](https://linux-hardware.org/?probe=f7bd03dbb9) | Jun 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [bf403bb6d8](https://linux-hardware.org/?probe=bf403bb6d8) | Jun 06, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [2667cb67a3](https://linux-hardware.org/?probe=2667cb67a3) | May 30, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [0568aa067a](https://linux-hardware.org/?probe=0568aa067a) | May 30, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [c8e0efc288](https://linux-hardware.org/?probe=c8e0efc288) | May 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [da399dc7cc](https://linux-hardware.org/?probe=da399dc7cc) | May 29, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [2a36e1c1d5](https://linux-hardware.org/?probe=2a36e1c1d5) | May 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [72f5c85f7f](https://linux-hardware.org/?probe=72f5c85f7f) | May 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [913f21a49c](https://linux-hardware.org/?probe=913f21a49c) | May 25, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [3272ba5e49](https://linux-hardware.org/?probe=3272ba5e49) | May 19, 2023 |
| Tactus        | GeoBook 140                 | Notebook    | [534c32884a](https://linux-hardware.org/?probe=534c32884a) | May 19, 2023 |
| Schenker      | VISION (E22)                | Notebook    | [582ac3cbf5](https://linux-hardware.org/?probe=582ac3cbf5) | May 13, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [cd65f81693](https://linux-hardware.org/?probe=cd65f81693) | May 11, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [45c02c8b1b](https://linux-hardware.org/?probe=45c02c8b1b) | May 11, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [2c96614c16](https://linux-hardware.org/?probe=2c96614c16) | May 11, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [5312325c90](https://linux-hardware.org/?probe=5312325c90) | May 10, 2023 |
| Lenovo        | ThinkPad T530 2394CE2       | Notebook    | [d232fefed2](https://linux-hardware.org/?probe=d232fefed2) | May 09, 2023 |
| HPE           | ProLiant ML30 Gen10 Plus    | Desktop     | [3a75fa5c03](https://linux-hardware.org/?probe=3a75fa5c03) | May 07, 2023 |
| Acer          | Predator PH315-53           | Notebook    | [efb597952f](https://linux-hardware.org/?probe=efb597952f) | May 07, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [1c98821416](https://linux-hardware.org/?probe=1c98821416) | May 03, 2023 |
| Acer          | TravelMate 5730             | Notebook    | [e74d115d0d](https://linux-hardware.org/?probe=e74d115d0d) | Apr 29, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | Notebook    | [5cb9fe1ae9](https://linux-hardware.org/?probe=5cb9fe1ae9) | Apr 28, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | Notebook    | [3669ef1de9](https://linux-hardware.org/?probe=3669ef1de9) | Apr 28, 2023 |
| Lenovo        | 3000 N200 0769A97           | Notebook    | [a293f4f1f7](https://linux-hardware.org/?probe=a293f4f1f7) | Apr 26, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [0db2c54b2a](https://linux-hardware.org/?probe=0db2c54b2a) | Apr 24, 2023 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [045a79a6e4](https://linux-hardware.org/?probe=045a79a6e4) | Apr 18, 2023 |
| Lenovo        | 30C0 SDK0J40705 WIN 3425... | Desktop     | [490a059818](https://linux-hardware.org/?probe=490a059818) | Apr 13, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [b3c9b78fec](https://linux-hardware.org/?probe=b3c9b78fec) | Apr 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [bba5f185af](https://linux-hardware.org/?probe=bba5f185af) | Apr 13, 2023 |
| Lenovo        | ThinkPad T530 2394BF7       | Notebook    | [5161d2f521](https://linux-hardware.org/?probe=5161d2f521) | Apr 11, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [64f96c6fde](https://linux-hardware.org/?probe=64f96c6fde) | Apr 07, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [917714b1be](https://linux-hardware.org/?probe=917714b1be) | Apr 06, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [ad148ede52](https://linux-hardware.org/?probe=ad148ede52) | Apr 06, 2023 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [171e39cdb6](https://linux-hardware.org/?probe=171e39cdb6) | Apr 05, 2023 |
| Dell          | Latitude 5530               | Notebook    | [802248e232](https://linux-hardware.org/?probe=802248e232) | Apr 03, 2023 |
| Intel         | NUC11PABi3 M68269-400       | Mini pc     | [7c7fdc5950](https://linux-hardware.org/?probe=7c7fdc5950) | Apr 02, 2023 |
| Dell          | Latitude 5530               | Notebook    | [e4688e2ef8](https://linux-hardware.org/?probe=e4688e2ef8) | Apr 01, 2023 |
| HP            | 82DC 1100                   | All in one  | [4c1c2f908b](https://linux-hardware.org/?probe=4c1c2f908b) | Mar 30, 2023 |
| ASUSTek       | N551JM                      | Notebook    | [b8e3d627b5](https://linux-hardware.org/?probe=b8e3d627b5) | Mar 27, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505     | Notebook    | [2b0f3e8867](https://linux-hardware.org/?probe=2b0f3e8867) | Mar 25, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505     | Notebook    | [8bb2484825](https://linux-hardware.org/?probe=8bb2484825) | Mar 25, 2023 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [bdfe7a3498](https://linux-hardware.org/?probe=bdfe7a3498) | Mar 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [4c7add7cd1](https://linux-hardware.org/?probe=4c7add7cd1) | Mar 21, 2023 |
| Tactus        | GeoBook 140                 | Notebook    | [5efd6f0674](https://linux-hardware.org/?probe=5efd6f0674) | Mar 20, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [55dc5e3ef4](https://linux-hardware.org/?probe=55dc5e3ef4) | Mar 19, 2023 |
| Supermicro    | X8DTU                       | Server      | [6012de6351](https://linux-hardware.org/?probe=6012de6351) | Mar 10, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [2409dc15b4](https://linux-hardware.org/?probe=2409dc15b4) | Mar 10, 2023 |
| HP            | EliteBook 8730w             | Notebook    | [a012fe4bd2](https://linux-hardware.org/?probe=a012fe4bd2) | Mar 10, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b349a8eedd](https://linux-hardware.org/?probe=b349a8eedd) | Mar 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [314cad4a2f](https://linux-hardware.org/?probe=314cad4a2f) | Mar 07, 2023 |
| ASRock        | H97 Pro4                    | Desktop     | [9ef8ff0b68](https://linux-hardware.org/?probe=9ef8ff0b68) | Mar 06, 2023 |
| Dell          | OptiPlex 9020               | Notebook    | [dda13d9c8e](https://linux-hardware.org/?probe=dda13d9c8e) | Mar 05, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [8e02418ca7](https://linux-hardware.org/?probe=8e02418ca7) | Mar 05, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [5510fed545](https://linux-hardware.org/?probe=5510fed545) | Mar 04, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [4f2c05c854](https://linux-hardware.org/?probe=4f2c05c854) | Feb 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [e2f06dcb4a](https://linux-hardware.org/?probe=e2f06dcb4a) | Feb 24, 2023 |
| Dell          | System XPS L702X            | Notebook    | [81f9738975](https://linux-hardware.org/?probe=81f9738975) | Feb 16, 2023 |
| Unknown       | Apple MacBook Pro (13-in... | Notebook    | [1d5a0bc43f](https://linux-hardware.org/?probe=1d5a0bc43f) | Feb 14, 2023 |
| Lenovo        | ThinkPad T540p 20BFA183A... | Notebook    | [2705e3d0c5](https://linux-hardware.org/?probe=2705e3d0c5) | Feb 12, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [caca2e6be1](https://linux-hardware.org/?probe=caca2e6be1) | Feb 11, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [b4b0bee06c](https://linux-hardware.org/?probe=b4b0bee06c) | Feb 08, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e574477cb6](https://linux-hardware.org/?probe=e574477cb6) | Feb 07, 2023 |
| MSI           | 0A90                        | Desktop     | [9210981559](https://linux-hardware.org/?probe=9210981559) | Feb 06, 2023 |
| MSI           | 0A90                        | Desktop     | [aedd414dbf](https://linux-hardware.org/?probe=aedd414dbf) | Feb 06, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [5a7a0cf485](https://linux-hardware.org/?probe=5a7a0cf485) | Feb 03, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [9f76193ccc](https://linux-hardware.org/?probe=9f76193ccc) | Jan 29, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [34882391f3](https://linux-hardware.org/?probe=34882391f3) | Jan 25, 2023 |
| HP            | Laptop 15-bs1xx             | Notebook    | [76689345ef](https://linux-hardware.org/?probe=76689345ef) | Jan 19, 2023 |
| Toshiba       | Satellite P200              | Notebook    | [478f5dc5cb](https://linux-hardware.org/?probe=478f5dc5cb) | Jan 18, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [29ff669f2c](https://linux-hardware.org/?probe=29ff669f2c) | Jan 14, 2023 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [2b04043ef0](https://linux-hardware.org/?probe=2b04043ef0) | Jan 10, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [ef10fbe492](https://linux-hardware.org/?probe=ef10fbe492) | Jan 09, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [5aaaf24b85](https://linux-hardware.org/?probe=5aaaf24b85) | Jan 09, 2023 |
| Samsung       | SBB-DA                      | Notebook    | [a4c6b4f454](https://linux-hardware.org/?probe=a4c6b4f454) | Jan 07, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [800f20e309](https://linux-hardware.org/?probe=800f20e309) | Jan 07, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [066ab1d6a3](https://linux-hardware.org/?probe=066ab1d6a3) | Jan 04, 2023 |
| ASUSTek       | N551JM                      | Notebook    | [f6de50a76b](https://linux-hardware.org/?probe=f6de50a76b) | Jan 04, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [e703dd0215](https://linux-hardware.org/?probe=e703dd0215) | Jan 04, 2023 |
| ASUSTek       | N551JM                      | Notebook    | [3ba1d0e689](https://linux-hardware.org/?probe=3ba1d0e689) | Jan 03, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [d88df3fcee](https://linux-hardware.org/?probe=d88df3fcee) | Jan 01, 2023 |
| Acer          | Aspire A715-41G             | Notebook    | [92f3c92191](https://linux-hardware.org/?probe=92f3c92191) | Dec 29, 2022 |
| Acer          | Swift SF314-41              | Notebook    | [2923c4c0fc](https://linux-hardware.org/?probe=2923c4c0fc) | Dec 28, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [9b8756cdd0](https://linux-hardware.org/?probe=9b8756cdd0) | Dec 17, 2022 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | Notebook    | [b2b93008c3](https://linux-hardware.org/?probe=b2b93008c3) | Dec 17, 2022 |
| ASRock        | B550M Steel Legend          | Desktop     | [516d6f7f12](https://linux-hardware.org/?probe=516d6f7f12) | Dec 14, 2022 |
| HP            | Laptop 15-db1xxx            | Notebook    | [3dcbd61f9e](https://linux-hardware.org/?probe=3dcbd61f9e) | Dec 12, 2022 |
| Lenovo        | HASWELLREFRESHDT 3190005... | All in one  | [b73060ce38](https://linux-hardware.org/?probe=b73060ce38) | Dec 10, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [15d7102174](https://linux-hardware.org/?probe=15d7102174) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [52525a1058](https://linux-hardware.org/?probe=52525a1058) | Dec 08, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [9815b67f0b](https://linux-hardware.org/?probe=9815b67f0b) | Dec 06, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [d632edc927](https://linux-hardware.org/?probe=d632edc927) | Dec 05, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [412bffea3b](https://linux-hardware.org/?probe=412bffea3b) | Dec 05, 2022 |
| ASRock        | K10N78D                     | Desktop     | [b5e2e7a024](https://linux-hardware.org/?probe=b5e2e7a024) | Dec 02, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [31f70fbb3e](https://linux-hardware.org/?probe=31f70fbb3e) | Nov 27, 2022 |
| Intel         | NUC5i5MYBE H47797-202       | Mini pc     | [e904ef7a24](https://linux-hardware.org/?probe=e904ef7a24) | Nov 26, 2022 |
| ASUSTek       | X550LB                      | Notebook    | [466592b744](https://linux-hardware.org/?probe=466592b744) | Nov 20, 2022 |
| ASUSTek       | X550LB                      | Notebook    | [3ca5ee2f7a](https://linux-hardware.org/?probe=3ca5ee2f7a) | Nov 20, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [9e16721568](https://linux-hardware.org/?probe=9e16721568) | Nov 17, 2022 |
| HP            | 1998                        | Desktop     | [f9746a4ae0](https://linux-hardware.org/?probe=f9746a4ae0) | Nov 15, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [311c90573c](https://linux-hardware.org/?probe=311c90573c) | Nov 12, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [1198a061e1](https://linux-hardware.org/?probe=1198a061e1) | Nov 12, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [de85ac10f6](https://linux-hardware.org/?probe=de85ac10f6) | Nov 09, 2022 |
| ASUSTek       | Zenbook UX5401EA_UX5401E... | Notebook    | [84bf8d9578](https://linux-hardware.org/?probe=84bf8d9578) | Nov 05, 2022 |
| Intel         | NUC5i5MYBE H47797-202       | Mini pc     | [01381d41de](https://linux-hardware.org/?probe=01381d41de) | Nov 03, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [b3cac9f8b8](https://linux-hardware.org/?probe=b3cac9f8b8) | Nov 02, 2022 |
| Intel         | NUC5i5MYBE H47797-202       | Mini pc     | [41a93c4dfa](https://linux-hardware.org/?probe=41a93c4dfa) | Nov 02, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [9b61195a2a](https://linux-hardware.org/?probe=9b61195a2a) | Nov 01, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [499932f589](https://linux-hardware.org/?probe=499932f589) | Nov 01, 2022 |
| Dell          | Studio 1735                 | Notebook    | [8f070a2831](https://linux-hardware.org/?probe=8f070a2831) | Oct 30, 2022 |
| Pretech       | EVE 1801 3G ES1049EG        | Notebook    | [24b035a7a4](https://linux-hardware.org/?probe=24b035a7a4) | Oct 25, 2022 |
| Dell          | Studio 1735                 | Notebook    | [21959a7db7](https://linux-hardware.org/?probe=21959a7db7) | Oct 24, 2022 |
| ASUSTek       | K53U                        | Notebook    | [d178c463df](https://linux-hardware.org/?probe=d178c463df) | Oct 24, 2022 |
| Dell          | Studio 1735                 | Notebook    | [4385640990](https://linux-hardware.org/?probe=4385640990) | Oct 23, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [eaecfdf473](https://linux-hardware.org/?probe=eaecfdf473) | Oct 21, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [c044987599](https://linux-hardware.org/?probe=c044987599) | Oct 20, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [04fed978ae](https://linux-hardware.org/?probe=04fed978ae) | Oct 18, 2022 |
| Lenovo        | ThinkPad T470s 20HGS1R90... | Notebook    | [e3eba59f05](https://linux-hardware.org/?probe=e3eba59f05) | Oct 17, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [c6f57791dc](https://linux-hardware.org/?probe=c6f57791dc) | Oct 12, 2022 |
| Acer          | Aspire A317-53              | Notebook    | [dadf436fd1](https://linux-hardware.org/?probe=dadf436fd1) | Oct 10, 2022 |
| HP            | EliteBook 8730w             | Notebook    | [e7545a94b2](https://linux-hardware.org/?probe=e7545a94b2) | Oct 09, 2022 |
| HP            | EliteBook 8730w             | Notebook    | [b938a96086](https://linux-hardware.org/?probe=b938a96086) | Oct 09, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [69023fe30e](https://linux-hardware.org/?probe=69023fe30e) | Oct 09, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [2a1088b211](https://linux-hardware.org/?probe=2a1088b211) | Oct 08, 2022 |
| Pretech       | EVE 1801 3G ES1049EG        | Notebook    | [3f2cdff8d4](https://linux-hardware.org/?probe=3f2cdff8d4) | Oct 05, 2022 |
| Toshiba       | Encore                      | Notebook    | [a11bf538ec](https://linux-hardware.org/?probe=a11bf538ec) | Oct 05, 2022 |
| Lenovo        | 0x30F617AA NOK              | Desktop     | [bb13b87bd5](https://linux-hardware.org/?probe=bb13b87bd5) | Oct 01, 2022 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [0dca3e500c](https://linux-hardware.org/?probe=0dca3e500c) | Sep 22, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [ce162c52c0](https://linux-hardware.org/?probe=ce162c52c0) | Sep 19, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [4a9e29fab2](https://linux-hardware.org/?probe=4a9e29fab2) | Sep 18, 2022 |
| Lenovo        | Unknown                     | Notebook    | [64dc493d4d](https://linux-hardware.org/?probe=64dc493d4d) | Sep 17, 2022 |
| Lenovo        | Unknown                     | Notebook    | [581356206a](https://linux-hardware.org/?probe=581356206a) | Sep 17, 2022 |
| Dell          | Latitude 5420               | Notebook    | [511ef8a105](https://linux-hardware.org/?probe=511ef8a105) | Sep 08, 2022 |
| Dell          | Latitude 5420               | Notebook    | [48db2c3954](https://linux-hardware.org/?probe=48db2c3954) | Sep 08, 2022 |
| Toshiba       | Satellite P200              | Notebook    | [583489891f](https://linux-hardware.org/?probe=583489891f) | Sep 06, 2022 |
| HP            | Pavilion dv9700             | Notebook    | [9543920c45](https://linux-hardware.org/?probe=9543920c45) | Sep 04, 2022 |
| HP            | Pavilion dv9700             | Notebook    | [b6d4d6bca2](https://linux-hardware.org/?probe=b6d4d6bca2) | Sep 04, 2022 |
| Acer          | Swift SF314-41              | Notebook    | [1394aca8b2](https://linux-hardware.org/?probe=1394aca8b2) | Sep 03, 2022 |
| ASUSTek       | Z97-PRO                     | Desktop     | [60865c8ded](https://linux-hardware.org/?probe=60865c8ded) | Sep 02, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [0e4eab04c0](https://linux-hardware.org/?probe=0e4eab04c0) | Aug 27, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [65e832cb2f](https://linux-hardware.org/?probe=65e832cb2f) | Aug 27, 2022 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [bafc4d3392](https://linux-hardware.org/?probe=bafc4d3392) | Aug 20, 2022 |
| Dell          | Latitude E7240              | Notebook    | [1f20b0f54b](https://linux-hardware.org/?probe=1f20b0f54b) | Aug 08, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [5ddb15f201](https://linux-hardware.org/?probe=5ddb15f201) | Aug 07, 2022 |
| Acer          | Aspire A515-56G             | Notebook    | [3df2b6b19b](https://linux-hardware.org/?probe=3df2b6b19b) | Aug 05, 2022 |
| HP            | 1825                        | Desktop     | [4a21a02ae4](https://linux-hardware.org/?probe=4a21a02ae4) | Jul 29, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [3c665fb25f](https://linux-hardware.org/?probe=3c665fb25f) | Jul 28, 2022 |
| ASUSTek       | S551LB                      | Notebook    | [8660a06086](https://linux-hardware.org/?probe=8660a06086) | Jul 27, 2022 |
| Lenovo        | ThinkPad T580 20LAS27000    | Notebook    | [a78a8e806f](https://linux-hardware.org/?probe=a78a8e806f) | Jul 21, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [6886cd26f5](https://linux-hardware.org/?probe=6886cd26f5) | Jul 20, 2022 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [55f956b817](https://linux-hardware.org/?probe=55f956b817) | Jul 14, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [17cdd0291e](https://linux-hardware.org/?probe=17cdd0291e) | Jul 12, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [4de601fe45](https://linux-hardware.org/?probe=4de601fe45) | Jul 12, 2022 |
| ASUSTek       | X75A1                       | Notebook    | [4bd18943fb](https://linux-hardware.org/?probe=4bd18943fb) | Jul 09, 2022 |
| ASUSTek       | X75A1                       | Notebook    | [3da162d001](https://linux-hardware.org/?probe=3da162d001) | Jul 09, 2022 |
| Dell          | Inspiron 3537               | Notebook    | [36305f7936](https://linux-hardware.org/?probe=36305f7936) | Jul 09, 2022 |
| Lenovo        | ThinkPad T480s 20L8S2330... | Notebook    | [4718003bb5](https://linux-hardware.org/?probe=4718003bb5) | Jul 09, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [6d9101e2d2](https://linux-hardware.org/?probe=6d9101e2d2) | Jul 08, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [36c7cff92d](https://linux-hardware.org/?probe=36c7cff92d) | Jul 07, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [445bedc2c9](https://linux-hardware.org/?probe=445bedc2c9) | Jul 06, 2022 |
| ASRock        | K10N78D                     | Desktop     | [650465a972](https://linux-hardware.org/?probe=650465a972) | Jul 06, 2022 |
| Dell          | Inspiron 3537               | Notebook    | [bfe2aed3aa](https://linux-hardware.org/?probe=bfe2aed3aa) | Jul 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [4d4cd5bae0](https://linux-hardware.org/?probe=4d4cd5bae0) | Jul 05, 2022 |
| WinFast       | NF-MCP55 FAB1.0             | Desktop     | [bb066cc2da](https://linux-hardware.org/?probe=bb066cc2da) | Jul 03, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [82ca4386ae](https://linux-hardware.org/?probe=82ca4386ae) | Jun 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [42462e221b](https://linux-hardware.org/?probe=42462e221b) | Jun 29, 2022 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [c73501602b](https://linux-hardware.org/?probe=c73501602b) | Jun 26, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [160062e69a](https://linux-hardware.org/?probe=160062e69a) | Jun 25, 2022 |
| Gigabyte      | G5 KC                       | Notebook    | [5ef620811f](https://linux-hardware.org/?probe=5ef620811f) | Jun 25, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [45c9b081c5](https://linux-hardware.org/?probe=45c9b081c5) | Jun 24, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [96c4f21509](https://linux-hardware.org/?probe=96c4f21509) | Jun 21, 2022 |
| Acer          | Aspire E5-771G              | Notebook    | [dac3ae2eba](https://linux-hardware.org/?probe=dac3ae2eba) | Jun 21, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [ba5ab976e2](https://linux-hardware.org/?probe=ba5ab976e2) | Jun 16, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [d2b608c230](https://linux-hardware.org/?probe=d2b608c230) | Jun 16, 2022 |
| ASUSTek       | B250 MINING EXPERT          | Desktop     | [0d4266a0f3](https://linux-hardware.org/?probe=0d4266a0f3) | Jun 15, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [1f92039342](https://linux-hardware.org/?probe=1f92039342) | Jun 02, 2022 |
| Supermicro    | C7Z270-CG-M                 | Server      | [dbbe7457ff](https://linux-hardware.org/?probe=dbbe7457ff) | May 31, 2022 |
| Supermicro    | C7Z270-CG-M                 | Server      | [a9c593dd0b](https://linux-hardware.org/?probe=a9c593dd0b) | May 31, 2022 |
| ASUSTek       | B250 MINING EXPERT          | Desktop     | [987ef7b2e7](https://linux-hardware.org/?probe=987ef7b2e7) | May 26, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [9dff398fa9](https://linux-hardware.org/?probe=9dff398fa9) | May 24, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [7b393b3933](https://linux-hardware.org/?probe=7b393b3933) | May 24, 2022 |
| Lenovo        | G40-30 80FY                 | Notebook    | [4280810a31](https://linux-hardware.org/?probe=4280810a31) | May 20, 2022 |
| eMachines     | E525                        | Notebook    | [2c397d4229](https://linux-hardware.org/?probe=2c397d4229) | May 19, 2022 |
| eMachines     | E525                        | Notebook    | [7a1e439150](https://linux-hardware.org/?probe=7a1e439150) | May 19, 2022 |
| Gigabyte      | X48T-DQ6                    | Desktop     | [2953148fae](https://linux-hardware.org/?probe=2953148fae) | May 16, 2022 |
| HP            | ProBook 470 G1              | Notebook    | [cb4ef48c3d](https://linux-hardware.org/?probe=cb4ef48c3d) | May 10, 2022 |
| Dell          | 0J37VM A01                  | Desktop     | [a5363ae511](https://linux-hardware.org/?probe=a5363ae511) | May 09, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [1e2ee4a2fb](https://linux-hardware.org/?probe=1e2ee4a2fb) | May 09, 2022 |
| ASRock        | Z87 Extreme4                | Desktop     | [db3a8bef92](https://linux-hardware.org/?probe=db3a8bef92) | May 09, 2022 |
| Lenovo        | 3746 No DPK                 | All in one  | [910612b856](https://linux-hardware.org/?probe=910612b856) | May 07, 2022 |
| ASRock        | H470M-HDV                   | Desktop     | [14d8e1d537](https://linux-hardware.org/?probe=14d8e1d537) | May 06, 2022 |
| HP            | ProBook 470 G1              | Notebook    | [a20a5df1ad](https://linux-hardware.org/?probe=a20a5df1ad) | May 06, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [3d1c0ef2f0](https://linux-hardware.org/?probe=3d1c0ef2f0) | May 05, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [220979cd04](https://linux-hardware.org/?probe=220979cd04) | May 05, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [8d561055ba](https://linux-hardware.org/?probe=8d561055ba) | May 04, 2022 |
| HP            | Pavilion 17                 | Notebook    | [3958b61eff](https://linux-hardware.org/?probe=3958b61eff) | May 02, 2022 |
| ASUSTek       | X540UA                      | Notebook    | [af0ed39935](https://linux-hardware.org/?probe=af0ed39935) | May 01, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [bc333fe437](https://linux-hardware.org/?probe=bc333fe437) | Apr 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [67d1865b69](https://linux-hardware.org/?probe=67d1865b69) | Apr 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [57a8a5bfcd](https://linux-hardware.org/?probe=57a8a5bfcd) | Apr 30, 2022 |
| Gigabyte      | P31-ES3G                    | Desktop     | [dc8419dcb3](https://linux-hardware.org/?probe=dc8419dcb3) | Apr 29, 2022 |
| HP            | Pavilion 17                 | Notebook    | [6de5e5677f](https://linux-hardware.org/?probe=6de5e5677f) | Apr 29, 2022 |
| Intel         | H61M-S2PV                   | Desktop     | [caa602b556](https://linux-hardware.org/?probe=caa602b556) | Apr 28, 2022 |
| Gigabyte      | P31-ES3G                    | Desktop     | [c3df637d15](https://linux-hardware.org/?probe=c3df637d15) | Apr 27, 2022 |
| Razer         | Blade                       | Notebook    | [c5ef4943c4](https://linux-hardware.org/?probe=c5ef4943c4) | Apr 27, 2022 |
| Fujitsu Si... | D2151-A1 S26361-D2151-A1    | Desktop     | [4db68ede02](https://linux-hardware.org/?probe=4db68ede02) | Apr 27, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [c8019d43f7](https://linux-hardware.org/?probe=c8019d43f7) | Apr 25, 2022 |
| ASRock        | H97 Pro4                    | Desktop     | [e937f129bf](https://linux-hardware.org/?probe=e937f129bf) | Apr 25, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2US0... | Notebook    | [1a7a85a6ca](https://linux-hardware.org/?probe=1a7a85a6ca) | Apr 21, 2022 |
| Pegatron      | 2AC3                        | Desktop     | [771e8a4439](https://linux-hardware.org/?probe=771e8a4439) | Apr 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [84978cfba3](https://linux-hardware.org/?probe=84978cfba3) | Apr 17, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [e970f67c93](https://linux-hardware.org/?probe=e970f67c93) | Apr 13, 2022 |
| ASUSTek       | P8H61 PRO                   | Desktop     | [82d8b5968f](https://linux-hardware.org/?probe=82d8b5968f) | Apr 12, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [bae30f6939](https://linux-hardware.org/?probe=bae30f6939) | Apr 11, 2022 |
| Dell          | OptiPlex 9020               | Notebook    | [6d0445b848](https://linux-hardware.org/?probe=6d0445b848) | Apr 09, 2022 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | Notebook    | [d7d4ac2b9a](https://linux-hardware.org/?probe=d7d4ac2b9a) | Apr 04, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [73cf5373cf](https://linux-hardware.org/?probe=73cf5373cf) | Apr 03, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [f76380fdae](https://linux-hardware.org/?probe=f76380fdae) | Apr 03, 2022 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | Notebook    | [f9ab989993](https://linux-hardware.org/?probe=f9ab989993) | Apr 02, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [752a6415ff](https://linux-hardware.org/?probe=752a6415ff) | Apr 02, 2022 |
| ASUSTek       | X71Sr                       | Notebook    | [0e6ffbc190](https://linux-hardware.org/?probe=0e6ffbc190) | Apr 01, 2022 |
| Gigabyte      | X48T-DQ6                    | Desktop     | [f63c898bc3](https://linux-hardware.org/?probe=f63c898bc3) | Mar 18, 2022 |
| eMachines     | E725 V1.03                  | Notebook    | [12ea923e2b](https://linux-hardware.org/?probe=12ea923e2b) | Mar 18, 2022 |
| ASUSTek       | P8H61 PRO                   | Desktop     | [60dc2b7bd7](https://linux-hardware.org/?probe=60dc2b7bd7) | Mar 18, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [9352c21f95](https://linux-hardware.org/?probe=9352c21f95) | Mar 17, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [8a6bb86ea0](https://linux-hardware.org/?probe=8a6bb86ea0) | Mar 17, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [271852ad10](https://linux-hardware.org/?probe=271852ad10) | Mar 17, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [6415b33b34](https://linux-hardware.org/?probe=6415b33b34) | Mar 17, 2022 |
| ASUSTek       | G75VX                       | Notebook    | [2b94fd73ea](https://linux-hardware.org/?probe=2b94fd73ea) | Mar 14, 2022 |
| Lenovo        | ThinkPad T410 2522DK2       | Notebook    | [9990e887c2](https://linux-hardware.org/?probe=9990e887c2) | Mar 13, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [561a945c5a](https://linux-hardware.org/?probe=561a945c5a) | Mar 13, 2022 |
| HP            | ProBook 4530s               | Notebook    | [061de41ec5](https://linux-hardware.org/?probe=061de41ec5) | Mar 13, 2022 |
| Toshiba       | Satellite C850-1GD          | Notebook    | [79b2741217](https://linux-hardware.org/?probe=79b2741217) | Mar 12, 2022 |
| ASRock        | B360 Gaming K4              | Desktop     | [ae6cb3bea9](https://linux-hardware.org/?probe=ae6cb3bea9) | Mar 11, 2022 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [ed3d7239af](https://linux-hardware.org/?probe=ed3d7239af) | Mar 09, 2022 |
| ASUSTek       | Z170-P                      | Desktop     | [fac84edcf2](https://linux-hardware.org/?probe=fac84edcf2) | Mar 08, 2022 |
| ASRock        | H97 Pro4                    | Desktop     | [83df7fb05a](https://linux-hardware.org/?probe=83df7fb05a) | Mar 07, 2022 |
| Gigabyte      | X48T-DQ6                    | Desktop     | [593cb60512](https://linux-hardware.org/?probe=593cb60512) | Mar 06, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [6ba21bc191](https://linux-hardware.org/?probe=6ba21bc191) | Mar 05, 2022 |
| Foxconn       | 2A8Ch                       | Desktop     | [49093d0be0](https://linux-hardware.org/?probe=49093d0be0) | Mar 05, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [34da56b567](https://linux-hardware.org/?probe=34da56b567) | Mar 01, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [d0ee45a4b1](https://linux-hardware.org/?probe=d0ee45a4b1) | Feb 26, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [28a9d8d6a4](https://linux-hardware.org/?probe=28a9d8d6a4) | Feb 25, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [a93fdb0cc8](https://linux-hardware.org/?probe=a93fdb0cc8) | Feb 25, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [37c0889ae6](https://linux-hardware.org/?probe=37c0889ae6) | Feb 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [57a0f33a96](https://linux-hardware.org/?probe=57a0f33a96) | Feb 23, 2022 |
| HP            | 2140                        | Notebook    | [ad18e8d0b3](https://linux-hardware.org/?probe=ad18e8d0b3) | Feb 22, 2022 |
| HP            | 2140                        | Notebook    | [e0757f087f](https://linux-hardware.org/?probe=e0757f087f) | Feb 22, 2022 |
| eMachines     | E725 V1.03                  | Notebook    | [0f12be73fa](https://linux-hardware.org/?probe=0f12be73fa) | Feb 21, 2022 |
| Apple         | MacBookAir5,2               | Notebook    | [dc8f1e8a38](https://linux-hardware.org/?probe=dc8f1e8a38) | Feb 20, 2022 |
| Acer          | Aspire E1-532G              | Notebook    | [2ec2b8bf53](https://linux-hardware.org/?probe=2ec2b8bf53) | Feb 20, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [7f55b1fa12](https://linux-hardware.org/?probe=7f55b1fa12) | Feb 17, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [731457f46c](https://linux-hardware.org/?probe=731457f46c) | Feb 13, 2022 |
| ECS           | A75F2-M2                    | Desktop     | [0c4ea60fd5](https://linux-hardware.org/?probe=0c4ea60fd5) | Feb 12, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [64cfd66662](https://linux-hardware.org/?probe=64cfd66662) | Feb 11, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [980b14c09a](https://linux-hardware.org/?probe=980b14c09a) | Feb 11, 2022 |
| Acer          | Aspire 7739G                | Notebook    | [f8150dd53e](https://linux-hardware.org/?probe=f8150dd53e) | Feb 10, 2022 |
| HP            | 82DC 1100                   | All in one  | [e3a85b9aaf](https://linux-hardware.org/?probe=e3a85b9aaf) | Feb 09, 2022 |
| Gigabyte      | B85M-DS3H                   | Desktop     | [98d6451ac1](https://linux-hardware.org/?probe=98d6451ac1) | Feb 07, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [c843bc46b3](https://linux-hardware.org/?probe=c843bc46b3) | Feb 07, 2022 |
| ASRock        | Z97M Pro4                   | Desktop     | [a496090845](https://linux-hardware.org/?probe=a496090845) | Feb 01, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [4210faf0d2](https://linux-hardware.org/?probe=4210faf0d2) | Jan 29, 2022 |
| Foxconn       | 2A8Ch                       | Desktop     | [276caa5169](https://linux-hardware.org/?probe=276caa5169) | Jan 23, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [5310be8910](https://linux-hardware.org/?probe=5310be8910) | Jan 23, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [4c77e8f334](https://linux-hardware.org/?probe=4c77e8f334) | Jan 23, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [cb60b63849](https://linux-hardware.org/?probe=cb60b63849) | Jan 23, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | Notebook    | [4b3b067330](https://linux-hardware.org/?probe=4b3b067330) | Jan 21, 2022 |
| ASRock        | Z590 Pro4                   | Desktop     | [a89877d9de](https://linux-hardware.org/?probe=a89877d9de) | Jan 16, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | Notebook    | [45b3c5b85a](https://linux-hardware.org/?probe=45b3c5b85a) | Jan 16, 2022 |
| ASRock        | Z590 Pro4                   | Desktop     | [7a2453280a](https://linux-hardware.org/?probe=7a2453280a) | Jan 14, 2022 |
| ECS           | H61H2-M2                    | Desktop     | [21704ab656](https://linux-hardware.org/?probe=21704ab656) | Jan 10, 2022 |
| ASUSTek       | X750LB                      | Desktop     | [47b4da86e2](https://linux-hardware.org/?probe=47b4da86e2) | Jan 10, 2022 |
| ASUSTek       | X750LB                      | Desktop     | [f1f247b586](https://linux-hardware.org/?probe=f1f247b586) | Jan 09, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [91548d30f5](https://linux-hardware.org/?probe=91548d30f5) | Jan 06, 2022 |
| HP            | EliteBook 2170p             | Notebook    | [4598e643d1](https://linux-hardware.org/?probe=4598e643d1) | Jan 05, 2022 |
| Lenovo        | 371C No DPK                 | All in one  | [6c4714d241](https://linux-hardware.org/?probe=6c4714d241) | Jan 04, 2022 |
| Lenovo        | ThinkPad E580 20KS005ASC    | Notebook    | [0a37cdb124](https://linux-hardware.org/?probe=0a37cdb124) | Jan 02, 2022 |
| MSI           | H81M-P33                    | Desktop     | [0fb1d25a7d](https://linux-hardware.org/?probe=0fb1d25a7d) | Dec 30, 2021 |
| Gigabyte      | 965P-DS3                    | Desktop     | [467762be06](https://linux-hardware.org/?probe=467762be06) | Dec 29, 2021 |
| ECS           | H61H2-M2                    | Desktop     | [6f3d8856df](https://linux-hardware.org/?probe=6f3d8856df) | Dec 29, 2021 |
| Lenovo        | B590 20208                  | Notebook    | [967a9b3a38](https://linux-hardware.org/?probe=967a9b3a38) | Dec 27, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [d9c0087822](https://linux-hardware.org/?probe=d9c0087822) | Dec 26, 2021 |
| Apple         | MacBookAir3,2               | Notebook    | [9f3a7c27d9](https://linux-hardware.org/?probe=9f3a7c27d9) | Dec 24, 2021 |
| ASRock        | 870 Extreme3                | Desktop     | [d202f241ee](https://linux-hardware.org/?probe=d202f241ee) | Dec 23, 2021 |
| Intel         | DH61CR AAG14064-204         | Desktop     | [13c79f41a6](https://linux-hardware.org/?probe=13c79f41a6) | Dec 18, 2021 |
| Intel         | DH61CR AAG14064-204         | Desktop     | [dbc555c5ad](https://linux-hardware.org/?probe=dbc555c5ad) | Dec 16, 2021 |
| Acer          | Aspire 5250                 | Notebook    | [b4a48e5350](https://linux-hardware.org/?probe=b4a48e5350) | Dec 15, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [86eb1ce765](https://linux-hardware.org/?probe=86eb1ce765) | Dec 15, 2021 |
| Acer          | Aspire A515-55              | Notebook    | [f258cd6bb3](https://linux-hardware.org/?probe=f258cd6bb3) | Dec 12, 2021 |
| Acer          | Aspire A314-22              | Notebook    | [655c34690e](https://linux-hardware.org/?probe=655c34690e) | Dec 12, 2021 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [eb77365d4e](https://linux-hardware.org/?probe=eb77365d4e) | Dec 11, 2021 |
| Lenovo        | IdeaPad 510S-13IKB 80V0     | Notebook    | [fe88e1083a](https://linux-hardware.org/?probe=fe88e1083a) | Dec 11, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [594becb8c9](https://linux-hardware.org/?probe=594becb8c9) | Dec 06, 2021 |
| ASRock        | M3A770DE                    | Desktop     | [1a03b6e5c7](https://linux-hardware.org/?probe=1a03b6e5c7) | Dec 05, 2021 |
| ASRock        | M3A770DE                    | Desktop     | [bdf4260678](https://linux-hardware.org/?probe=bdf4260678) | Dec 05, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d9019c420c](https://linux-hardware.org/?probe=d9019c420c) | Dec 04, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [dac924cd16](https://linux-hardware.org/?probe=dac924cd16) | Dec 04, 2021 |
| Acer          | Aspire E1-522               | Notebook    | [3111a073e8](https://linux-hardware.org/?probe=3111a073e8) | Dec 03, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [422733b9df](https://linux-hardware.org/?probe=422733b9df) | Dec 02, 2021 |
| Lenovo        | B50-70 20384                | Notebook    | [d75361564f](https://linux-hardware.org/?probe=d75361564f) | Dec 02, 2021 |
| Lenovo        | ThinkPad T450s 20BWS2US0... | Notebook    | [0e099c0bdd](https://linux-hardware.org/?probe=0e099c0bdd) | Dec 02, 2021 |
| Dell          | 0GDG8Y A00                  | Desktop     | [d0cf0cc443](https://linux-hardware.org/?probe=d0cf0cc443) | Dec 01, 2021 |
| Foxconn       | 2A8Ch                       | Desktop     | [1eff06a331](https://linux-hardware.org/?probe=1eff06a331) | Nov 30, 2021 |
| Foxconn       | 2A8Ch                       | Desktop     | [1f650ebd72](https://linux-hardware.org/?probe=1f650ebd72) | Nov 30, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1HK0... | Notebook    | [416712d76f](https://linux-hardware.org/?probe=416712d76f) | Nov 30, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1HK0... | Notebook    | [c4e34dbb1c](https://linux-hardware.org/?probe=c4e34dbb1c) | Nov 30, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [b153db375f](https://linux-hardware.org/?probe=b153db375f) | Nov 29, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [ec7596ddfa](https://linux-hardware.org/?probe=ec7596ddfa) | Nov 26, 2021 |
| Acer          | Aspire 6930G                | Notebook    | [323825e995](https://linux-hardware.org/?probe=323825e995) | Nov 24, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [659ed4999d](https://linux-hardware.org/?probe=659ed4999d) | Nov 24, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [b0b04002be](https://linux-hardware.org/?probe=b0b04002be) | Nov 24, 2021 |
| HP            | EliteBook 2530p             | Notebook    | [08f1548a45](https://linux-hardware.org/?probe=08f1548a45) | Nov 23, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [515899572d](https://linux-hardware.org/?probe=515899572d) | Nov 22, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [9ae3647f81](https://linux-hardware.org/?probe=9ae3647f81) | Nov 22, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [bde1fd1da2](https://linux-hardware.org/?probe=bde1fd1da2) | Nov 20, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [8a1a3f0661](https://linux-hardware.org/?probe=8a1a3f0661) | Nov 20, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [eace5e1302](https://linux-hardware.org/?probe=eace5e1302) | Nov 19, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [9c7eba9b77](https://linux-hardware.org/?probe=9c7eba9b77) | Nov 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [3a3f503917](https://linux-hardware.org/?probe=3a3f503917) | Nov 14, 2021 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [c77e499435](https://linux-hardware.org/?probe=c77e499435) | Nov 13, 2021 |
| HP            | Pavilion Laptop 14-bf1xx    | Notebook    | [93e710085b](https://linux-hardware.org/?probe=93e710085b) | Nov 12, 2021 |
| ASUSTek       | M4A78T-E                    | Desktop     | [10991ab539](https://linux-hardware.org/?probe=10991ab539) | Nov 10, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [aa49529b6c](https://linux-hardware.org/?probe=aa49529b6c) | Nov 09, 2021 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [3af4c85553](https://linux-hardware.org/?probe=3af4c85553) | Nov 04, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [df4871ce19](https://linux-hardware.org/?probe=df4871ce19) | Nov 04, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [d59cc9fead](https://linux-hardware.org/?probe=d59cc9fead) | Nov 04, 2021 |
| ASUSTek       | X751NV                      | Notebook    | [ecf08805fe](https://linux-hardware.org/?probe=ecf08805fe) | Nov 03, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [903ec63ceb](https://linux-hardware.org/?probe=903ec63ceb) | Nov 02, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [c7f7df5e24](https://linux-hardware.org/?probe=c7f7df5e24) | Nov 01, 2021 |
| MSI           | P55-CD53                    | Desktop     | [860bde5935](https://linux-hardware.org/?probe=860bde5935) | Oct 31, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [532a1d3d01](https://linux-hardware.org/?probe=532a1d3d01) | Oct 29, 2021 |
| MSI           | P55-CD53                    | Desktop     | [12bf811a5c](https://linux-hardware.org/?probe=12bf811a5c) | Oct 24, 2021 |
| MSI           | P55-CD53                    | Desktop     | [c1c364dbc1](https://linux-hardware.org/?probe=c1c364dbc1) | Oct 24, 2021 |
| ASUSTek       | M5A78L LE                   | Desktop     | [adf114d66e](https://linux-hardware.org/?probe=adf114d66e) | Oct 23, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [2d80988ddc](https://linux-hardware.org/?probe=2d80988ddc) | Oct 22, 2021 |
| Pegatron      | 2A73h                       | Desktop     | [dc24d5d19f](https://linux-hardware.org/?probe=dc24d5d19f) | Oct 16, 2021 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [d891006b52](https://linux-hardware.org/?probe=d891006b52) | Oct 14, 2021 |
| ASUSTek       | B85M-E                      | Desktop     | [d98b27a03c](https://linux-hardware.org/?probe=d98b27a03c) | Oct 11, 2021 |
| SHENZHEN X... | ST106                       | Notebook    | [afbb6f50c8](https://linux-hardware.org/?probe=afbb6f50c8) | Oct 11, 2021 |
| SHENZHEN X... | ST106                       | Notebook    | [5ca1710273](https://linux-hardware.org/?probe=5ca1710273) | Oct 11, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [e570cc15cd](https://linux-hardware.org/?probe=e570cc15cd) | Oct 06, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [d5199453f5](https://linux-hardware.org/?probe=d5199453f5) | Oct 04, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [068d8ff3b0](https://linux-hardware.org/?probe=068d8ff3b0) | Oct 04, 2021 |
| ASUSTek       | A58M-K                      | Desktop     | [2ca6ce79db](https://linux-hardware.org/?probe=2ca6ce79db) | Oct 03, 2021 |
| Toshiba       | Satellite P200              | Notebook    | [df46118ac3](https://linux-hardware.org/?probe=df46118ac3) | Oct 02, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [1b6bb85e6b](https://linux-hardware.org/?probe=1b6bb85e6b) | Sep 30, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [aa5e0ddd18](https://linux-hardware.org/?probe=aa5e0ddd18) | Sep 30, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [e5508ac7ab](https://linux-hardware.org/?probe=e5508ac7ab) | Sep 27, 2021 |
| ASUSTek       | M4A78T-E                    | Desktop     | [01ec64f498](https://linux-hardware.org/?probe=01ec64f498) | Sep 24, 2021 |
| HP            | ProBook 4740s               | Notebook    | [77b2eed991](https://linux-hardware.org/?probe=77b2eed991) | Sep 22, 2021 |
| Acer          | Aspire 5250                 | Notebook    | [be1b633020](https://linux-hardware.org/?probe=be1b633020) | Sep 14, 2021 |
| Lenovo        | 371C No DPK                 | All in one  | [cd0d01d653](https://linux-hardware.org/?probe=cd0d01d653) | Sep 11, 2021 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [8803020fce](https://linux-hardware.org/?probe=8803020fce) | Sep 11, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [1172b42b6b](https://linux-hardware.org/?probe=1172b42b6b) | Sep 10, 2021 |
| HUAWEI        | WRTB-WXX9                   | Notebook    | [1570fd5033](https://linux-hardware.org/?probe=1570fd5033) | Sep 09, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [104bd9a2a0](https://linux-hardware.org/?probe=104bd9a2a0) | Sep 09, 2021 |
| Lenovo        | ThinkPad E590 20NB006MSC    | Notebook    | [73c87242b9](https://linux-hardware.org/?probe=73c87242b9) | Sep 09, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [aa6b5ca915](https://linux-hardware.org/?probe=aa6b5ca915) | Sep 08, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [8b503ffd8a](https://linux-hardware.org/?probe=8b503ffd8a) | Sep 07, 2021 |
| Dell          | Latitude 5580               | Notebook    | [944d9e820d](https://linux-hardware.org/?probe=944d9e820d) | Sep 01, 2021 |
| Acer          | Aspire F5-571G              | Notebook    | [d3d0e83199](https://linux-hardware.org/?probe=d3d0e83199) | Aug 30, 2021 |
| Lenovo        | IdeaPad 110-17IKB 80VK      | Notebook    | [44e5a5c02e](https://linux-hardware.org/?probe=44e5a5c02e) | Aug 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [06981db89b](https://linux-hardware.org/?probe=06981db89b) | Aug 20, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [a33d74d8e4](https://linux-hardware.org/?probe=a33d74d8e4) | Aug 19, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [19982a455b](https://linux-hardware.org/?probe=19982a455b) | Aug 18, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [3c4fba3670](https://linux-hardware.org/?probe=3c4fba3670) | Aug 15, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [f9bd04ed57](https://linux-hardware.org/?probe=f9bd04ed57) | Aug 14, 2021 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [149504315f](https://linux-hardware.org/?probe=149504315f) | Aug 10, 2021 |
| HP            | 2000                        | Notebook    | [73e2b73533](https://linux-hardware.org/?probe=73e2b73533) | Aug 09, 2021 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [a319e4cbd9](https://linux-hardware.org/?probe=a319e4cbd9) | Aug 06, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [7d693f5628](https://linux-hardware.org/?probe=7d693f5628) | Aug 04, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [75944f340e](https://linux-hardware.org/?probe=75944f340e) | Aug 04, 2021 |
| Lenovo        | ThinkPad T430 2349AK2       | Notebook    | [c51aebd74f](https://linux-hardware.org/?probe=c51aebd74f) | Aug 04, 2021 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [3a2fd430f6](https://linux-hardware.org/?probe=3a2fd430f6) | Aug 03, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [0283581712](https://linux-hardware.org/?probe=0283581712) | Jul 31, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [f15116c26a](https://linux-hardware.org/?probe=f15116c26a) | Jul 30, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [8297a49138](https://linux-hardware.org/?probe=8297a49138) | Jul 28, 2021 |
| Acer          | Aspire E5-774G              | Notebook    | [f60a7a3f63](https://linux-hardware.org/?probe=f60a7a3f63) | Jul 28, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [4759f3249f](https://linux-hardware.org/?probe=4759f3249f) | Jul 28, 2021 |
| Lenovo        | ThinkPad X260 20F5S0JF00    | Notebook    | [98cbf345d9](https://linux-hardware.org/?probe=98cbf345d9) | Jul 25, 2021 |
| HP            | 2000                        | Notebook    | [0187fe7c8a](https://linux-hardware.org/?probe=0187fe7c8a) | Jul 25, 2021 |
| ASUSTek       | X540SAA                     | Notebook    | [34bb1d000b](https://linux-hardware.org/?probe=34bb1d000b) | Jul 24, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [66ea173cb5](https://linux-hardware.org/?probe=66ea173cb5) | Jul 21, 2021 |
| ASRock        | Z370 Pro4                   | Desktop     | [9a9f7c5e69](https://linux-hardware.org/?probe=9a9f7c5e69) | Jul 20, 2021 |
| Acer          | Aspire 6930G                | Notebook    | [45694711ff](https://linux-hardware.org/?probe=45694711ff) | Jul 20, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [1cd948b8e0](https://linux-hardware.org/?probe=1cd948b8e0) | Jul 19, 2021 |
| Acer          | Aspire 6930G                | Notebook    | [0e4d09c44c](https://linux-hardware.org/?probe=0e4d09c44c) | Jul 15, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [6c3da4947f](https://linux-hardware.org/?probe=6c3da4947f) | Jul 02, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [5497b79433](https://linux-hardware.org/?probe=5497b79433) | Jul 02, 2021 |
| HP            | EliteBook 830 G5            | Notebook    | [e43bc569f4](https://linux-hardware.org/?probe=e43bc569f4) | Jul 01, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [2e6400b3fb](https://linux-hardware.org/?probe=2e6400b3fb) | Jun 30, 2021 |
| System76      | Oryx Pro                    | Notebook    | [fd3cc0ad52](https://linux-hardware.org/?probe=fd3cc0ad52) | Jun 30, 2021 |
| HP            | EliteBook 850 G6            | Notebook    | [e38bee4588](https://linux-hardware.org/?probe=e38bee4588) | Jun 24, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [b6ea706618](https://linux-hardware.org/?probe=b6ea706618) | Jun 22, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [0c5f910d8b](https://linux-hardware.org/?probe=0c5f910d8b) | Jun 21, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [79627ead32](https://linux-hardware.org/?probe=79627ead32) | Jun 14, 2021 |
| Lenovo        | ThinkPad E580 20KS005ASC    | Notebook    | [5b707f47c0](https://linux-hardware.org/?probe=5b707f47c0) | Jun 11, 2021 |
| Gigabyte      | GA-990XA-UD3                | Desktop     | [af31bae015](https://linux-hardware.org/?probe=af31bae015) | Jun 10, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [b2fe748178](https://linux-hardware.org/?probe=b2fe748178) | Jun 08, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [e0c6618369](https://linux-hardware.org/?probe=e0c6618369) | Jun 07, 2021 |
| Lenovo        | ThinkPad P53 20QNZ4RBUS     | Notebook    | [3f5925d0f5](https://linux-hardware.org/?probe=3f5925d0f5) | Jun 07, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [83b3cc659a](https://linux-hardware.org/?probe=83b3cc659a) | Jun 07, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [7d816dafe7](https://linux-hardware.org/?probe=7d816dafe7) | Jun 01, 2021 |
| Lenovo        | ThinkPad P1 20MES1T700      | Notebook    | [be5bc5605b](https://linux-hardware.org/?probe=be5bc5605b) | Jun 01, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [eb9aaa55ea](https://linux-hardware.org/?probe=eb9aaa55ea) | May 30, 2021 |
| Lenovo        | V340-17IWL 81RG             | Notebook    | [2ec41d1cf8](https://linux-hardware.org/?probe=2ec41d1cf8) | May 26, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [0c3e0e8293](https://linux-hardware.org/?probe=0c3e0e8293) | May 26, 2021 |
| Dell          | 06CV2N A01                  | Desktop     | [35a0afd617](https://linux-hardware.org/?probe=35a0afd617) | May 25, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [eb4e8e4cc2](https://linux-hardware.org/?probe=eb4e8e4cc2) | May 25, 2021 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [657fe689d6](https://linux-hardware.org/?probe=657fe689d6) | May 19, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [bfb71f53ec](https://linux-hardware.org/?probe=bfb71f53ec) | May 03, 2021 |
| Lenovo        | CRESCENTBAY 31900058 WIN... | All in one  | [84248bb07c](https://linux-hardware.org/?probe=84248bb07c) | May 03, 2021 |
| Acer          | Aspire F5-571G              | Notebook    | [5bb52c52af](https://linux-hardware.org/?probe=5bb52c52af) | Apr 30, 2021 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [2cd9e43be0](https://linux-hardware.org/?probe=2cd9e43be0) | Apr 27, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [6ab7b315e3](https://linux-hardware.org/?probe=6ab7b315e3) | Apr 24, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [7e0d6ec835](https://linux-hardware.org/?probe=7e0d6ec835) | Apr 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [470c00d1c5](https://linux-hardware.org/?probe=470c00d1c5) | Apr 23, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [fbc2a66e2b](https://linux-hardware.org/?probe=fbc2a66e2b) | Apr 22, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [eabbb41fea](https://linux-hardware.org/?probe=eabbb41fea) | Apr 20, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [86927ce44d](https://linux-hardware.org/?probe=86927ce44d) | Apr 20, 2021 |
| Lenovo        | ThinkPad T490s 20NXCTO1W... | Notebook    | [92fe8bf812](https://linux-hardware.org/?probe=92fe8bf812) | Apr 20, 2021 |
| ASRock        | P45DE                       | Desktop     | [2f6b602e36](https://linux-hardware.org/?probe=2f6b602e36) | Apr 18, 2021 |
| HP            | Compaq 6710b (KL509AV)      | Notebook    | [735870e390](https://linux-hardware.org/?probe=735870e390) | Apr 16, 2021 |
| HP            | EliteBook 850 G6            | Notebook    | [7dbeb6844a](https://linux-hardware.org/?probe=7dbeb6844a) | Apr 16, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [24cd2670f3](https://linux-hardware.org/?probe=24cd2670f3) | Apr 15, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [60ef5cf4f2](https://linux-hardware.org/?probe=60ef5cf4f2) | Apr 15, 2021 |
| HP            | Compaq 6710b (KL509AV)      | Notebook    | [565cd80547](https://linux-hardware.org/?probe=565cd80547) | Apr 15, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [78550034b4](https://linux-hardware.org/?probe=78550034b4) | Apr 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [43b989fae1](https://linux-hardware.org/?probe=43b989fae1) | Apr 06, 2021 |
| Lenovo        | ThinkPad T460 20FMS0X022    | Notebook    | [02ce254082](https://linux-hardware.org/?probe=02ce254082) | Apr 06, 2021 |
| ASRock        | Z370 Pro4                   | Desktop     | [7ad77d82ba](https://linux-hardware.org/?probe=7ad77d82ba) | Apr 03, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [b776bc7947](https://linux-hardware.org/?probe=b776bc7947) | Mar 31, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [2d68f9ad7f](https://linux-hardware.org/?probe=2d68f9ad7f) | Mar 31, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [be7b667e75](https://linux-hardware.org/?probe=be7b667e75) | Mar 27, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [45e4f9d242](https://linux-hardware.org/?probe=45e4f9d242) | Mar 24, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ba238dbe29](https://linux-hardware.org/?probe=ba238dbe29) | Mar 21, 2021 |
| Dell          | Inspiron 5551               | Notebook    | [3b91b6e49f](https://linux-hardware.org/?probe=3b91b6e49f) | Mar 20, 2021 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [6e5e0c9ef4](https://linux-hardware.org/?probe=6e5e0c9ef4) | Mar 19, 2021 |
| MSI           | Z390-A PRO                  | Desktop     | [12566ee726](https://linux-hardware.org/?probe=12566ee726) | Mar 10, 2021 |
| Gigabyte      | G1.Sniper Z87               | Desktop     | [c9a3501b03](https://linux-hardware.org/?probe=c9a3501b03) | Mar 02, 2021 |
| ASRock        | FM2A75M-DGS                 | Desktop     | [72c1ab0b9b](https://linux-hardware.org/?probe=72c1ab0b9b) | Mar 01, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [24a672b8ac](https://linux-hardware.org/?probe=24a672b8ac) | Feb 25, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [8f0d10afce](https://linux-hardware.org/?probe=8f0d10afce) | Feb 24, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [ffdabc425b](https://linux-hardware.org/?probe=ffdabc425b) | Feb 16, 2021 |
| ASRock        | Z87 Extreme4                | Desktop     | [081e14044d](https://linux-hardware.org/?probe=081e14044d) | Feb 13, 2021 |
| Dell          | XPS 13 9380                 | Notebook    | [69f9ebe58b](https://linux-hardware.org/?probe=69f9ebe58b) | Feb 11, 2021 |
| Acer          | Aspire ES1-532G             | Notebook    | [f01b666f99](https://linux-hardware.org/?probe=f01b666f99) | Feb 09, 2021 |
| Dell          | 0NNGP2 A00                  | Desktop     | [9be58392b6](https://linux-hardware.org/?probe=9be58392b6) | Feb 08, 2021 |
| Acer          | Aspire A315-41              | Notebook    | [d0648fe1f7](https://linux-hardware.org/?probe=d0648fe1f7) | Feb 07, 2021 |
| Dell          | 0J37VM A01                  | Desktop     | [3062914f46](https://linux-hardware.org/?probe=3062914f46) | Feb 07, 2021 |
| Dell          | 0J37VM A01                  | Desktop     | [34e1267a80](https://linux-hardware.org/?probe=34e1267a80) | Feb 07, 2021 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [eee7c1f592](https://linux-hardware.org/?probe=eee7c1f592) | Feb 03, 2021 |
| HP            | 250 G5 Notebook PC          | Notebook    | [a541bcd390](https://linux-hardware.org/?probe=a541bcd390) | Feb 02, 2021 |
| ASRock        | ConRoe1333-D667             | Desktop     | [54121172b8](https://linux-hardware.org/?probe=54121172b8) | Jan 31, 2021 |
| Gigabyte      | B450 GAMING X               | Desktop     | [28cb4726bb](https://linux-hardware.org/?probe=28cb4726bb) | Jan 31, 2021 |
| Gigabyte      | B450 GAMING X               | Desktop     | [0b4b751863](https://linux-hardware.org/?probe=0b4b751863) | Jan 31, 2021 |
| ASUSTek       | F5N                         | Notebook    | [5a1b1f9f7a](https://linux-hardware.org/?probe=5a1b1f9f7a) | Jan 26, 2021 |
| ASRock        | X570M Pro4                  | Desktop     | [9cd91004ab](https://linux-hardware.org/?probe=9cd91004ab) | Jan 24, 2021 |
| Gigabyte      | F2A78M-DS2                  | Desktop     | [9afb5c207a](https://linux-hardware.org/?probe=9afb5c207a) | Jan 23, 2021 |
| Dell          | 0DFRFW A01                  | Desktop     | [482bc5334f](https://linux-hardware.org/?probe=482bc5334f) | Jan 22, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [943284255a](https://linux-hardware.org/?probe=943284255a) | Jan 20, 2021 |
| Gigabyte      | F2A78M-DS2                  | Desktop     | [df34a7d718](https://linux-hardware.org/?probe=df34a7d718) | Jan 20, 2021 |
| Gigabyte      | F2A78M-DS2                  | Desktop     | [0d8e905a30](https://linux-hardware.org/?probe=0d8e905a30) | Jan 16, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [17f2fe84cb](https://linux-hardware.org/?probe=17f2fe84cb) | Jan 14, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [9b72f3a82b](https://linux-hardware.org/?probe=9b72f3a82b) | Jan 11, 2021 |
| Dell          | Latitude E6430              | Notebook    | [939c4dbad4](https://linux-hardware.org/?probe=939c4dbad4) | Jan 10, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [1f95699c20](https://linux-hardware.org/?probe=1f95699c20) | Jan 09, 2021 |
| Lenovo        | ThinkPad T61 6458AU9        | Notebook    | [5350b0523f](https://linux-hardware.org/?probe=5350b0523f) | Jan 08, 2021 |
| Lenovo        | G710 20252                  | Notebook    | [9b176fb8e5](https://linux-hardware.org/?probe=9b176fb8e5) | Jan 04, 2021 |
| Lenovo        | G710 20252                  | Notebook    | [db68ccb5de](https://linux-hardware.org/?probe=db68ccb5de) | Jan 04, 2021 |
| ASUSTek       | M4A78T-E                    | Desktop     | [e2fa1223c4](https://linux-hardware.org/?probe=e2fa1223c4) | Jan 03, 2021 |
| ASUSTek       | M4A78T-E                    | Desktop     | [db7dfe41a5](https://linux-hardware.org/?probe=db7dfe41a5) | Jan 03, 2021 |
| MSI           | P67A-GD53/2.0               | Desktop     | [2ca3b4e129](https://linux-hardware.org/?probe=2ca3b4e129) | Jan 03, 2021 |
| MSI           | P67A-GD53/2.0               | Desktop     | [638a245f5f](https://linux-hardware.org/?probe=638a245f5f) | Jan 03, 2021 |
| Gigabyte      | GA-MA785GMT-UD2H            | Desktop     | [15160d8a87](https://linux-hardware.org/?probe=15160d8a87) | Jan 02, 2021 |
| Dell          | Vostro 3578                 | Notebook    | [a2e6574ba4](https://linux-hardware.org/?probe=a2e6574ba4) | Dec 30, 2020 |
| HP            | 18EA                        | Desktop     | [67e2e927b6](https://linux-hardware.org/?probe=67e2e927b6) | Dec 27, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [bb46f7172f](https://linux-hardware.org/?probe=bb46f7172f) | Dec 27, 2020 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [120e788567](https://linux-hardware.org/?probe=120e788567) | Dec 24, 2020 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [f6ef9c50ed](https://linux-hardware.org/?probe=f6ef9c50ed) | Dec 23, 2020 |
| ASUSTek       | H81M-K                      | Desktop     | [03b737b966](https://linux-hardware.org/?probe=03b737b966) | Dec 23, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [d886327463](https://linux-hardware.org/?probe=d886327463) | Dec 22, 2020 |
| ASRock        | Z370 Pro4                   | Desktop     | [e6df8b78b5](https://linux-hardware.org/?probe=e6df8b78b5) | Dec 21, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [4c807db430](https://linux-hardware.org/?probe=4c807db430) | Dec 19, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [fb469bd0dc](https://linux-hardware.org/?probe=fb469bd0dc) | Dec 17, 2020 |
| ASUSTek       | M5A78L LE                   | Desktop     | [4e7620198d](https://linux-hardware.org/?probe=4e7620198d) | Dec 15, 2020 |
| ASUSTek       | M5A78L LE                   | Desktop     | [0a6542f4b3](https://linux-hardware.org/?probe=0a6542f4b3) | Dec 12, 2020 |
| Acer          | Aspire 7739G                | Notebook    | [9d81c58373](https://linux-hardware.org/?probe=9d81c58373) | Dec 12, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [9b07c5b4a5](https://linux-hardware.org/?probe=9b07c5b4a5) | Dec 06, 2020 |
| HP            | EliteBook 8560p             | Notebook    | [3cc104d803](https://linux-hardware.org/?probe=3cc104d803) | Dec 05, 2020 |
| Lenovo        | ThinkPad W540 20BHS04K00    | Notebook    | [c429b95a44](https://linux-hardware.org/?probe=c429b95a44) | Dec 03, 2020 |
| HP            | 2000                        | Notebook    | [27fed77b24](https://linux-hardware.org/?probe=27fed77b24) | Dec 02, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [82adf2d707](https://linux-hardware.org/?probe=82adf2d707) | Dec 01, 2020 |
| Acer          | Aspire ES1-732              | Notebook    | [243f8b5015](https://linux-hardware.org/?probe=243f8b5015) | Nov 29, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [24fe3f5f2f](https://linux-hardware.org/?probe=24fe3f5f2f) | Nov 25, 2020 |
| HP            | ProBook 450 G7              | Notebook    | [49c3ecb298](https://linux-hardware.org/?probe=49c3ecb298) | Nov 24, 2020 |
| Acer          | Aspire ES1-732              | Notebook    | [9a62fb8fe7](https://linux-hardware.org/?probe=9a62fb8fe7) | Nov 21, 2020 |
| HP            | ProBook 640 G1              | Notebook    | [eed4ff0229](https://linux-hardware.org/?probe=eed4ff0229) | Nov 19, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [9c165b5f59](https://linux-hardware.org/?probe=9c165b5f59) | Nov 11, 2020 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [50ddfd361b](https://linux-hardware.org/?probe=50ddfd361b) | Nov 11, 2020 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [7e3892e9b1](https://linux-hardware.org/?probe=7e3892e9b1) | Nov 09, 2020 |
| Acer          | Aspire E5-771G              | Notebook    | [9d967e969d](https://linux-hardware.org/?probe=9d967e969d) | Nov 01, 2020 |
| ASRock        | N68-S3 UCC                  | Desktop     | [b75cfae4a3](https://linux-hardware.org/?probe=b75cfae4a3) | Nov 01, 2020 |
| Acer          | Aspire V5-531               | Notebook    | [8eb2cc2336](https://linux-hardware.org/?probe=8eb2cc2336) | Nov 01, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [e6cd5153b1](https://linux-hardware.org/?probe=e6cd5153b1) | Oct 31, 2020 |
| HP            | ProBook 450 G7              | Notebook    | [c3c04c52ab](https://linux-hardware.org/?probe=c3c04c52ab) | Oct 26, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [57db732909](https://linux-hardware.org/?probe=57db732909) | Oct 25, 2020 |
| Nvidia        | Tegra                       | Soc         | [ef24e8c128](https://linux-hardware.org/?probe=ef24e8c128) | Oct 23, 2020 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [8d0c1b4422](https://linux-hardware.org/?probe=8d0c1b4422) | Oct 22, 2020 |
| Nvidia        | Tegra                       | Soc         | [d3a4ce2fd2](https://linux-hardware.org/?probe=d3a4ce2fd2) | Oct 22, 2020 |
| Nvidia        | Tegra                       | Soc         | [d3bdc7437e](https://linux-hardware.org/?probe=d3bdc7437e) | Oct 22, 2020 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [36db0ea3d4](https://linux-hardware.org/?probe=36db0ea3d4) | Oct 21, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [38c87efbca](https://linux-hardware.org/?probe=38c87efbca) | Oct 16, 2020 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [ff7ecd0641](https://linux-hardware.org/?probe=ff7ecd0641) | Oct 15, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [65c065a968](https://linux-hardware.org/?probe=65c065a968) | Oct 09, 2020 |
| HP            | EliteBook 850 G5            | Notebook    | [0d11552658](https://linux-hardware.org/?probe=0d11552658) | Oct 07, 2020 |
| Pegatron      | 2A94h                       | Desktop     | [668c4bbb8b](https://linux-hardware.org/?probe=668c4bbb8b) | Oct 06, 2020 |
| Toshiba       | Satellite C55-A-1M7         | Notebook    | [174d6c4c6d](https://linux-hardware.org/?probe=174d6c4c6d) | Oct 06, 2020 |
| Dell          | Vostro 3578                 | Notebook    | [7904981ea3](https://linux-hardware.org/?probe=7904981ea3) | Oct 05, 2020 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [b098cfc85e](https://linux-hardware.org/?probe=b098cfc85e) | Sep 30, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [dacb39a2ba](https://linux-hardware.org/?probe=dacb39a2ba) | Sep 30, 2020 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [df11954c4f](https://linux-hardware.org/?probe=df11954c4f) | Sep 28, 2020 |
| HP            | ProBook 450 G7              | Notebook    | [b4807eff1e](https://linux-hardware.org/?probe=b4807eff1e) | Sep 28, 2020 |
| HP            | ProBook 450 G7              | Notebook    | [9cc971b2e7](https://linux-hardware.org/?probe=9cc971b2e7) | Sep 28, 2020 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [8220732bda](https://linux-hardware.org/?probe=8220732bda) | Sep 28, 2020 |
| ASUSTek       | M5A78L LE                   | Desktop     | [7f4940b41c](https://linux-hardware.org/?probe=7f4940b41c) | Sep 28, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [062f436dfa](https://linux-hardware.org/?probe=062f436dfa) | Sep 27, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [181e06ec2e](https://linux-hardware.org/?probe=181e06ec2e) | Sep 26, 2020 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [d7391de736](https://linux-hardware.org/?probe=d7391de736) | Sep 21, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [ea8e216968](https://linux-hardware.org/?probe=ea8e216968) | Sep 20, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [d93882e0b2](https://linux-hardware.org/?probe=d93882e0b2) | Sep 20, 2020 |
| ASRock        | N68-S3 UCC                  | Desktop     | [42ed26b195](https://linux-hardware.org/?probe=42ed26b195) | Sep 19, 2020 |
| HP            | EliteBook 850 G6            | Notebook    | [fa0ec4aeae](https://linux-hardware.org/?probe=fa0ec4aeae) | Sep 17, 2020 |
| HP            | Compaq nc6220 (PY732ES#A... | Notebook    | [eeb54854f8](https://linux-hardware.org/?probe=eeb54854f8) | Sep 12, 2020 |
| HP            | Compaq nc6220 (PY732ES#A... | Notebook    | [a8d6bb1865](https://linux-hardware.org/?probe=a8d6bb1865) | Sep 12, 2020 |
| Dell          | Latitude 7390               | Notebook    | [b8019896d0](https://linux-hardware.org/?probe=b8019896d0) | Sep 10, 2020 |
| ASUSTek       | M4A77                       | Desktop     | [d076f8fe03](https://linux-hardware.org/?probe=d076f8fe03) | Sep 08, 2020 |
| HP            | ProBook 430 G3              | Notebook    | [b80f12df10](https://linux-hardware.org/?probe=b80f12df10) | Sep 07, 2020 |
| ASRock        | Z87E-ITX                    | Desktop     | [d1095a7a24](https://linux-hardware.org/?probe=d1095a7a24) | Sep 05, 2020 |
| ASRock        | N68-S3 UCC                  | Desktop     | [a2d99d11fc](https://linux-hardware.org/?probe=a2d99d11fc) | Aug 30, 2020 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [1c2eaa2346](https://linux-hardware.org/?probe=1c2eaa2346) | Aug 23, 2020 |
| HP            | 2129                        | Desktop     | [d1eda00971](https://linux-hardware.org/?probe=d1eda00971) | Aug 20, 2020 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [1b2d8402af](https://linux-hardware.org/?probe=1b2d8402af) | Aug 17, 2020 |
| HP            | EliteBook 850 G6            | Notebook    | [4458c2267f](https://linux-hardware.org/?probe=4458c2267f) | Aug 17, 2020 |
| AMI           | Cherry Trail CR             | Mini pc     | [3a826b3414](https://linux-hardware.org/?probe=3a826b3414) | Aug 13, 2020 |
| HP            | ProBook 430 G3              | Notebook    | [e28ccfa01e](https://linux-hardware.org/?probe=e28ccfa01e) | Aug 11, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [9bf9387073](https://linux-hardware.org/?probe=9bf9387073) | Aug 05, 2020 |
| ASUSTek       | GL752VW                     | Notebook    | [26fc584896](https://linux-hardware.org/?probe=26fc584896) | Aug 02, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [c670b35249](https://linux-hardware.org/?probe=c670b35249) | Jul 29, 2020 |
| Lenovo        | Y50-70 20378                | Notebook    | [842efe3170](https://linux-hardware.org/?probe=842efe3170) | Jul 28, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [743f8b4f98](https://linux-hardware.org/?probe=743f8b4f98) | Jul 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [34213d655c](https://linux-hardware.org/?probe=34213d655c) | Jul 24, 2020 |
| Lenovo        | IdeaCentre Stick 300-01I... | Stick pc    | [28b902c9b7](https://linux-hardware.org/?probe=28b902c9b7) | Jul 21, 2020 |
| Dell          | Precision 5530              | Notebook    | [30c2f2561e](https://linux-hardware.org/?probe=30c2f2561e) | Jul 20, 2020 |
| ASUSTek       | X751NV                      | Notebook    | [f94768a5e6](https://linux-hardware.org/?probe=f94768a5e6) | Jul 15, 2020 |
| HP            | Compaq 6820s                | Notebook    | [f5b6aa7190](https://linux-hardware.org/?probe=f5b6aa7190) | Jul 15, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [ce78055795](https://linux-hardware.org/?probe=ce78055795) | Jul 14, 2020 |
| Gigabyte      | G41M-Combo                  | Desktop     | [2f3657530f](https://linux-hardware.org/?probe=2f3657530f) | Jun 29, 2020 |
| ASUSTek       | B85M-E                      | Desktop     | [e46352dec8](https://linux-hardware.org/?probe=e46352dec8) | Jun 28, 2020 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [ac52acb928](https://linux-hardware.org/?probe=ac52acb928) | Jun 24, 2020 |
| Notebook      | MAM2080                     | Notebook    | [7464ed3c9d](https://linux-hardware.org/?probe=7464ed3c9d) | Jun 23, 2020 |
| ASUSTek       | X751NV                      | Notebook    | [08c5775f88](https://linux-hardware.org/?probe=08c5775f88) | Jun 22, 2020 |
| Notebook      | MAM2080                     | Notebook    | [7321ecab2d](https://linux-hardware.org/?probe=7321ecab2d) | Jun 21, 2020 |
| ASRock        | H97M Pro4                   | Desktop     | [31f3732dc9](https://linux-hardware.org/?probe=31f3732dc9) | Jun 19, 2020 |
| Lenovo        | ThinkPad T440 20B7S14N0U    | Notebook    | [c0c727bcb0](https://linux-hardware.org/?probe=c0c727bcb0) | Jun 18, 2020 |
| ASUSTek       | X540UA                      | Notebook    | [7f0afeb60e](https://linux-hardware.org/?probe=7f0afeb60e) | Jun 16, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [639b8bd2bc](https://linux-hardware.org/?probe=639b8bd2bc) | Jun 14, 2020 |
| Acer          | Aspire 7720                 | Notebook    | [77e3ae41d8](https://linux-hardware.org/?probe=77e3ae41d8) | Jun 10, 2020 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [2c0b3072ac](https://linux-hardware.org/?probe=2c0b3072ac) | Jun 09, 2020 |
| Acer          | Swift SF314-52              | Notebook    | [fa00080df2](https://linux-hardware.org/?probe=fa00080df2) | Jun 06, 2020 |
| Lenovo        | G710 20252                  | Notebook    | [eff12f397f](https://linux-hardware.org/?probe=eff12f397f) | Jun 06, 2020 |
| Gigabyte      | G31MX-S2                    | Desktop     | [7da6752573](https://linux-hardware.org/?probe=7da6752573) | May 31, 2020 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [d77566be76](https://linux-hardware.org/?probe=d77566be76) | May 31, 2020 |
| Gigabyte      | G31MX-S2                    | Desktop     | [5472c53dca](https://linux-hardware.org/?probe=5472c53dca) | May 31, 2020 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [06f88752e5](https://linux-hardware.org/?probe=06f88752e5) | May 31, 2020 |
| AMI           | Cherry Trail CR             | Mini pc     | [15cf043276](https://linux-hardware.org/?probe=15cf043276) | May 31, 2020 |
| AMI           | Cherry Trail CR             | Mini pc     | [89935abc60](https://linux-hardware.org/?probe=89935abc60) | May 31, 2020 |
| AMI           | Cherry Trail CR             | Mini pc     | [bbb1f5819f](https://linux-hardware.org/?probe=bbb1f5819f) | May 31, 2020 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [26a9c7f62c](https://linux-hardware.org/?probe=26a9c7f62c) | May 30, 2020 |
| Lenovo        | G500 20236                  | Notebook    | [689825038f](https://linux-hardware.org/?probe=689825038f) | May 25, 2020 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [e3042f4583](https://linux-hardware.org/?probe=e3042f4583) | May 24, 2020 |
| Toshiba       | Satellite L50-B             | Notebook    | [3ae92d178c](https://linux-hardware.org/?probe=3ae92d178c) | May 21, 2020 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [e6f20d976d](https://linux-hardware.org/?probe=e6f20d976d) | May 17, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9e3950795e](https://linux-hardware.org/?probe=9e3950795e) | May 17, 2020 |
| Toshiba       | Satellite L50-B             | Notebook    | [0a7ccd88d0](https://linux-hardware.org/?probe=0a7ccd88d0) | May 15, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [951378d6d8](https://linux-hardware.org/?probe=951378d6d8) | May 15, 2020 |
| ASUSTek       | N56VZ                       | Notebook    | [69ee412460](https://linux-hardware.org/?probe=69ee412460) | May 14, 2020 |
| Acer          | Aspire ES1-571              | Notebook    | [77ee42e92e](https://linux-hardware.org/?probe=77ee42e92e) | May 12, 2020 |
| Gigabyte      | 965P-DS3                    | Desktop     | [abfb95a938](https://linux-hardware.org/?probe=abfb95a938) | May 11, 2020 |
| Gigabyte      | 965P-DS3                    | Desktop     | [e59e1593d5](https://linux-hardware.org/?probe=e59e1593d5) | May 11, 2020 |
| MSI           | MS-7360                     | Desktop     | [ab94189bcf](https://linux-hardware.org/?probe=ab94189bcf) | May 07, 2020 |
| eMachines     | G725                        | Notebook    | [7edfa3ee85](https://linux-hardware.org/?probe=7edfa3ee85) | May 04, 2020 |
| Acer          | Aspire A315-51              | Notebook    | [c5c02e1984](https://linux-hardware.org/?probe=c5c02e1984) | May 03, 2020 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [c17fa3f327](https://linux-hardware.org/?probe=c17fa3f327) | May 02, 2020 |
| Acer          | Aspire A315-51              | Notebook    | [5f8f6e1f17](https://linux-hardware.org/?probe=5f8f6e1f17) | May 02, 2020 |
| Acer          | Swift SF314-52              | Notebook    | [72ece5cb6b](https://linux-hardware.org/?probe=72ece5cb6b) | Apr 23, 2020 |
| Lenovo        | B590 627439G                | Notebook    | [59e71f4410](https://linux-hardware.org/?probe=59e71f4410) | Apr 16, 2020 |
| Dell          | Vostro 3584                 | Notebook    | [37bd21052a](https://linux-hardware.org/?probe=37bd21052a) | Apr 15, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [ca750eb568](https://linux-hardware.org/?probe=ca750eb568) | Apr 14, 2020 |
| HP            | 3031h                       | Desktop     | [b4638888cb](https://linux-hardware.org/?probe=b4638888cb) | Apr 14, 2020 |
| ASUSTek       | M5A78L LE                   | Desktop     | [1562c544a6](https://linux-hardware.org/?probe=1562c544a6) | Apr 14, 2020 |
| ASRock        | H61M-DGS                    | Desktop     | [0a090881ae](https://linux-hardware.org/?probe=0a090881ae) | Apr 12, 2020 |
| ASUSTek       | N56VZ                       | Notebook    | [249176d47f](https://linux-hardware.org/?probe=249176d47f) | Apr 01, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [72c0b81b89](https://linux-hardware.org/?probe=72c0b81b89) | Mar 27, 2020 |
| Lenovo        | G710 20252                  | Notebook    | [1a2c3269a9](https://linux-hardware.org/?probe=1a2c3269a9) | Mar 25, 2020 |
| ASUSTek       | A8V-MQ                      | Desktop     | [54a0034c0a](https://linux-hardware.org/?probe=54a0034c0a) | Mar 24, 2020 |
| Medion        | P6618                       | Notebook    | [cd6a2e684b](https://linux-hardware.org/?probe=cd6a2e684b) | Mar 20, 2020 |
| ASRock        | H61M-VS                     | Desktop     | [799e1670fd](https://linux-hardware.org/?probe=799e1670fd) | Mar 18, 2020 |
| HP            | 212B                        | Desktop     | [6058dd53b1](https://linux-hardware.org/?probe=6058dd53b1) | Mar 16, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [958514b01d](https://linux-hardware.org/?probe=958514b01d) | Mar 06, 2020 |
| HP            | Presario CQ57               | Notebook    | [09b5945399](https://linux-hardware.org/?probe=09b5945399) | Mar 02, 2020 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [26545c7add](https://linux-hardware.org/?probe=26545c7add) | Feb 24, 2020 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [1693523c61](https://linux-hardware.org/?probe=1693523c61) | Feb 21, 2020 |
| AMI           | Cherry Trail CR             | Mini pc     | [bdebb9000c](https://linux-hardware.org/?probe=bdebb9000c) | Feb 21, 2020 |
| AMI           | Cherry Trail CR             | Mini pc     | [65c38da632](https://linux-hardware.org/?probe=65c38da632) | Feb 20, 2020 |
| Intel         | DH67BL AAG10189-213         | Desktop     | [b0e9895bef](https://linux-hardware.org/?probe=b0e9895bef) | Feb 16, 2020 |
| HP            | Pavilion g6                 | Notebook    | [5965dbf803](https://linux-hardware.org/?probe=5965dbf803) | Feb 08, 2020 |
| ASRock        | B150M-HDV                   | Desktop     | [c08c6d0574](https://linux-hardware.org/?probe=c08c6d0574) | Feb 08, 2020 |
| HP            | EliteBook 850 G6            | Notebook    | [ed2e18e22a](https://linux-hardware.org/?probe=ed2e18e22a) | Jan 31, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [fc460d19de](https://linux-hardware.org/?probe=fc460d19de) | Jan 29, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [ad283e347b](https://linux-hardware.org/?probe=ad283e347b) | Jan 28, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [fe5311a7e7](https://linux-hardware.org/?probe=fe5311a7e7) | Jan 28, 2020 |
| HP            | 18E7                        | Desktop     | [de846e5f4f](https://linux-hardware.org/?probe=de846e5f4f) | Jan 22, 2020 |
| Intel         | DH67BL AAG10189-213         | Desktop     | [9ed2076b0d](https://linux-hardware.org/?probe=9ed2076b0d) | Jan 18, 2020 |
| Intel         | DH67BL AAG10189-213         | Desktop     | [dc121e5512](https://linux-hardware.org/?probe=dc121e5512) | Jan 18, 2020 |
| Acer          | Veriton S680G               | Desktop     | [277889b2ff](https://linux-hardware.org/?probe=277889b2ff) | Jan 15, 2020 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [3317c231ea](https://linux-hardware.org/?probe=3317c231ea) | Jan 08, 2020 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [0af8fff870](https://linux-hardware.org/?probe=0af8fff870) | Jan 06, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [cd7fe65e36](https://linux-hardware.org/?probe=cd7fe65e36) | Jan 02, 2020 |
| Acer          | Aspire A715-72G             | Notebook    | [d8301b28b6](https://linux-hardware.org/?probe=d8301b28b6) | Dec 31, 2019 |
| HP            | ProBook 4730s               | Notebook    | [a56d8d1c28](https://linux-hardware.org/?probe=a56d8d1c28) | Dec 26, 2019 |
| HP            | ProBook 4730s               | Notebook    | [fc266328ed](https://linux-hardware.org/?probe=fc266328ed) | Dec 26, 2019 |
| HP            | ProBook 4730s               | Notebook    | [581fd252a9](https://linux-hardware.org/?probe=581fd252a9) | Dec 26, 2019 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [e097415087](https://linux-hardware.org/?probe=e097415087) | Dec 26, 2019 |
| ASRock        | N68-S3 UCC                  | Desktop     | [9cbd6c2e0e](https://linux-hardware.org/?probe=9cbd6c2e0e) | Dec 25, 2019 |
| ASRock        | 990FX Extreme3              | Desktop     | [107280e5a9](https://linux-hardware.org/?probe=107280e5a9) | Dec 23, 2019 |
| ASRock        | 990FX Extreme3              | Desktop     | [66a084d547](https://linux-hardware.org/?probe=66a084d547) | Dec 11, 2019 |
| Lenovo        | ThinkPad T440 20B7S14N0U    | Notebook    | [059788b6b9](https://linux-hardware.org/?probe=059788b6b9) | Dec 04, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [1bb0047e0e](https://linux-hardware.org/?probe=1bb0047e0e) | Dec 03, 2019 |
| ASRock        | H97 Killer                  | Desktop     | [8538b88e3d](https://linux-hardware.org/?probe=8538b88e3d) | Nov 27, 2019 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [73c6829ffb](https://linux-hardware.org/?probe=73c6829ffb) | Nov 27, 2019 |
| HP            | OMEN by Laptop 17-cb0xxx    | Notebook    | [c3973966c4](https://linux-hardware.org/?probe=c3973966c4) | Nov 21, 2019 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [518b6e5e9c](https://linux-hardware.org/?probe=518b6e5e9c) | Nov 21, 2019 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [dfc4334b0c](https://linux-hardware.org/?probe=dfc4334b0c) | Nov 15, 2019 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [6334709a9e](https://linux-hardware.org/?probe=6334709a9e) | Nov 15, 2019 |
| HP            | EliteBook 850 G6            | Notebook    | [d1a89b5c7b](https://linux-hardware.org/?probe=d1a89b5c7b) | Nov 13, 2019 |
| HP            | 18EA                        | Desktop     | [101b838d0e](https://linux-hardware.org/?probe=101b838d0e) | Nov 10, 2019 |
| Toshiba       | Satellite A300              | Notebook    | [9bd874bab4](https://linux-hardware.org/?probe=9bd874bab4) | Nov 05, 2019 |
| Acer          | Aspire A715-72G             | Notebook    | [ae95cd5f3d](https://linux-hardware.org/?probe=ae95cd5f3d) | Oct 12, 2019 |
| Acer          | Aspire A715-72G             | Notebook    | [38c98d0bfa](https://linux-hardware.org/?probe=38c98d0bfa) | Oct 12, 2019 |
| ASRock        | A320M-HDV R3.0              | Desktop     | [d3d79c2a8d](https://linux-hardware.org/?probe=d3d79c2a8d) | Sep 16, 2019 |
| ASUSTek       | G750JZ                      | Notebook    | [f6f8595b70](https://linux-hardware.org/?probe=f6f8595b70) | Sep 14, 2019 |
| Acer          | Aspire A315-21              | Notebook    | [b29e405bdc](https://linux-hardware.org/?probe=b29e405bdc) | Sep 13, 2019 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [a35aea421b](https://linux-hardware.org/?probe=a35aea421b) | Sep 09, 2019 |
| Intel         | DX58SO AAE29331-501         | Desktop     | [349ef8982a](https://linux-hardware.org/?probe=349ef8982a) | Sep 09, 2019 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [59782a89ea](https://linux-hardware.org/?probe=59782a89ea) | Sep 06, 2019 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [b4ef0f5499](https://linux-hardware.org/?probe=b4ef0f5499) | Sep 05, 2019 |
| Acer          | Aspire A515-51G             | Notebook    | [458c9ffc20](https://linux-hardware.org/?probe=458c9ffc20) | Sep 02, 2019 |
| Dell          | G3 3779                     | Notebook    | [46c53c54c1](https://linux-hardware.org/?probe=46c53c54c1) | Aug 28, 2019 |
| Lenovo        | ThinkPad X240 20AMS30A01    | Notebook    | [a808bddfca](https://linux-hardware.org/?probe=a808bddfca) | Aug 22, 2019 |
| ASRock        | FM2A55M-DGS R2.0            | Desktop     | [be3a07802c](https://linux-hardware.org/?probe=be3a07802c) | Aug 13, 2019 |
| ASRock        | FM2A55M-DGS R2.0            | Desktop     | [9cdd546881](https://linux-hardware.org/?probe=9cdd546881) | Jul 29, 2019 |
| ASRock        | A300M-STX                   | Desktop     | [edf300f175](https://linux-hardware.org/?probe=edf300f175) | Jul 29, 2019 |
| Gigabyte      | X299 UD4 Pro-CF             | Desktop     | [aad0551e27](https://linux-hardware.org/?probe=aad0551e27) | Jul 25, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [57c89febd9](https://linux-hardware.org/?probe=57c89febd9) | Jul 22, 2019 |
| Dell          | Vostro 3480                 | Notebook    | [142a1d632e](https://linux-hardware.org/?probe=142a1d632e) | Jul 12, 2019 |
| Dell          | Vostro 3480                 | Notebook    | [5c7cd324e3](https://linux-hardware.org/?probe=5c7cd324e3) | Jul 12, 2019 |
| ASUSTek       | E35M1-M                     | Desktop     | [1b78cc518f](https://linux-hardware.org/?probe=1b78cc518f) | Jul 08, 2019 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [542c9cbc52](https://linux-hardware.org/?probe=542c9cbc52) | Jun 23, 2019 |
| ASUSTek       | E35M1-M                     | Desktop     | [1f5e6b026b](https://linux-hardware.org/?probe=1f5e6b026b) | Jun 23, 2019 |
| Acer          | Aspire A515-51G             | Notebook    | [43a15b2717](https://linux-hardware.org/?probe=43a15b2717) | Jun 22, 2019 |
| Acer          | Extensa 5630                | Notebook    | [ac0c824624](https://linux-hardware.org/?probe=ac0c824624) | Jun 16, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f8c4365b6c](https://linux-hardware.org/?probe=f8c4365b6c) | Jun 07, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3968b06d9c](https://linux-hardware.org/?probe=3968b06d9c) | Jun 07, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [edcc2f0a4e](https://linux-hardware.org/?probe=edcc2f0a4e) | Jun 06, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [8195d1d516](https://linux-hardware.org/?probe=8195d1d516) | Jun 06, 2019 |
| Dell          | Latitude E6440              | Notebook    | [6c61ba4580](https://linux-hardware.org/?probe=6c61ba4580) | Jun 04, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [6ce5e7dbb1](https://linux-hardware.org/?probe=6ce5e7dbb1) | May 24, 2019 |
| HP            | 250 G6 Notebook PC          | Notebook    | [da7e75ebe8](https://linux-hardware.org/?probe=da7e75ebe8) | May 19, 2019 |
| Lenovo        | G50-45 80E3                 | Notebook    | [d78a5346f7](https://linux-hardware.org/?probe=d78a5346f7) | May 13, 2019 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [6465c1b176](https://linux-hardware.org/?probe=6465c1b176) | May 11, 2019 |
| HP            | 83ED                        | Desktop     | [532b72754e](https://linux-hardware.org/?probe=532b72754e) | May 06, 2019 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [93859ddac7](https://linux-hardware.org/?probe=93859ddac7) | May 05, 2019 |
| HP            | Notebook                    | Notebook    | [75f8121579](https://linux-hardware.org/?probe=75f8121579) | May 03, 2019 |
| HP            | Notebook                    | Notebook    | [55d7e86f13](https://linux-hardware.org/?probe=55d7e86f13) | May 03, 2019 |
| HP            | Notebook                    | Notebook    | [17fa8aef52](https://linux-hardware.org/?probe=17fa8aef52) | May 03, 2019 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [09c192ce30](https://linux-hardware.org/?probe=09c192ce30) | May 03, 2019 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [f4deeacc7c](https://linux-hardware.org/?probe=f4deeacc7c) | May 03, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [5d410980c0](https://linux-hardware.org/?probe=5d410980c0) | May 01, 2019 |
| Toshiba       | Satellite A300              | Notebook    | [89f0da0254](https://linux-hardware.org/?probe=89f0da0254) | Apr 30, 2019 |
| ASUSTek       | X550JX                      | Notebook    | [341ce6f2fb](https://linux-hardware.org/?probe=341ce6f2fb) | Apr 14, 2019 |
| Gigabyte      | Z77P-D3                     | Desktop     | [e7259783d1](https://linux-hardware.org/?probe=e7259783d1) | Apr 13, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [3b3d563f34](https://linux-hardware.org/?probe=3b3d563f34) | Apr 12, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [8046c09d71](https://linux-hardware.org/?probe=8046c09d71) | Apr 03, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [54f04aad99](https://linux-hardware.org/?probe=54f04aad99) | Mar 22, 2019 |
| Dell          | 00X7CK A02                  | Server      | [5b9ec879fc](https://linux-hardware.org/?probe=5b9ec879fc) | Mar 11, 2019 |
| Pegatron      | 2A99                        | Desktop     | [196712630c](https://linux-hardware.org/?probe=196712630c) | Feb 26, 2019 |
| HP            | Unknown                     | Notebook    | [37702d4223](https://linux-hardware.org/?probe=37702d4223) | Feb 22, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [01e34dc2d8](https://linux-hardware.org/?probe=01e34dc2d8) | Feb 19, 2019 |
| ASUSTek       | B150M-C                     | Desktop     | [88898f6797](https://linux-hardware.org/?probe=88898f6797) | Feb 10, 2019 |
| ECS           | A770M-A                     | Desktop     | [feacfccf11](https://linux-hardware.org/?probe=feacfccf11) | Feb 05, 2019 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [bf1298d356](https://linux-hardware.org/?probe=bf1298d356) | Jan 29, 2019 |
| ABIT          | IP35-E                      | Desktop     | [87b22d6a66](https://linux-hardware.org/?probe=87b22d6a66) | Jan 26, 2019 |
| ASUSTek       | X540UA                      | Notebook    | [42572b9771](https://linux-hardware.org/?probe=42572b9771) | Jan 05, 2019 |
| ASUSTek       | X540UA                      | Notebook    | [867a1fdda8](https://linux-hardware.org/?probe=867a1fdda8) | Dec 14, 2018 |
| ASUSTek       | X540UA                      | Notebook    | [ae2b9d2b8f](https://linux-hardware.org/?probe=ae2b9d2b8f) | Dec 14, 2018 |
| ASUSTek       | X540UA                      | Notebook    | [567e365e34](https://linux-hardware.org/?probe=567e365e34) | Dec 14, 2018 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [bc26ed35a0](https://linux-hardware.org/?probe=bc26ed35a0) | Dec 08, 2018 |
| Acer          | Aspire 5715Z                | Notebook    | [abecd9bff0](https://linux-hardware.org/?probe=abecd9bff0) | Nov 30, 2018 |
| Acer          | Aspire 5715Z                | Notebook    | [fd1d18122b](https://linux-hardware.org/?probe=fd1d18122b) | Nov 30, 2018 |
| HP            | 2000                        | Notebook    | [b24b2b9082](https://linux-hardware.org/?probe=b24b2b9082) | Nov 26, 2018 |
| Unknown       | Grantsdale                  | Desktop     | [65da6a461b](https://linux-hardware.org/?probe=65da6a461b) | Nov 21, 2018 |
| HP            | ProBook 450 G4              | Notebook    | [415307639f](https://linux-hardware.org/?probe=415307639f) | Nov 21, 2018 |
| Pegatron      | 2AB6                        | Desktop     | [00a8407210](https://linux-hardware.org/?probe=00a8407210) | Oct 31, 2018 |
| HP            | EliteBook 2540p             | Notebook    | [88e983ac45](https://linux-hardware.org/?probe=88e983ac45) | Oct 28, 2018 |
| ASUSTek       | X705UDR                     | Notebook    | [0a1cf851c7](https://linux-hardware.org/?probe=0a1cf851c7) | Jun 20, 2018 |
| Samsung       | N150/N210/N220              | Notebook    | [bab6da27ab](https://linux-hardware.org/?probe=bab6da27ab) | Apr 30, 2017 |
| Dell          | Vostro 1700                 | Notebook    | [6167c4bd5d](https://linux-hardware.org/?probe=6167c4bd5d) | Mar 17, 2017 |
| Dell          | Inspiron 3737               | Notebook    | [fba4632269](https://linux-hardware.org/?probe=fba4632269) | Dec 22, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Croatia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 72        | 12.31%  |
| Ubuntu 18.04                 | 33        | 5.64%   |
| Ubuntu 22.04                 | 30        | 5.13%   |
| Debian 11                    | 21        | 3.59%   |
| OpenMandriva 4.3             | 14        | 2.39%   |
| Zorin 16                     | 12        | 2.05%   |
| Linux Mint 20.2              | 11        | 1.88%   |
| Arch Rolling                 | 11        | 1.88%   |
| Linux Mint 20.3              | 10        | 1.71%   |
| Fedora 38                    | 10        | 1.71%   |
| Ubuntu 18.10                 | 9         | 1.54%   |
| Pop!_OS 22.04                | 9         | 1.54%   |
| Pop!_OS 21.04                | 9         | 1.54%   |
| Ubuntu 21.04                 | 7         | 1.2%    |
| Pop!_OS 20.04                | 7         | 1.2%    |
| Fedora 36                    | 7         | 1.2%    |
| ArcoLinux Rolling            | 7         | 1.2%    |
| Ubuntu 19.10                 | 6         | 1.03%   |
| Pop!_OS 21.10                | 6         | 1.03%   |
| Pop!_OS 20.10                | 6         | 1.03%   |
| openSUSE Tumbleweed-XXXXXXXX | 6         | 1.03%   |
| OpenMandriva 4.2             | 6         | 1.03%   |
| Manjaro                      | 6         | 1.03%   |
| Linux Mint 21.1              | 6         | 1.03%   |
| KDE neon 20.04               | 6         | 1.03%   |
| Debian 12                    | 6         | 1.03%   |
| Debian 10                    | 6         | 1.03%   |
| Ubuntu 19.04                 | 5         | 0.85%   |
| KDE neon 22.04               | 5         | 0.85%   |
| Fedora 35                    | 5         | 0.85%   |
| Endless 3.7.8                | 5         | 0.85%   |
| EndeavourOS Rolling          | 5         | 0.85%   |
| Arch                         | 5         | 0.85%   |
| Zorin 15                     | 4         | 0.68%   |
| Ubuntu 20.10                 | 4         | 0.68%   |
| OpenMandriva 4.50            | 4         | 0.68%   |
| Linux Mint 20                | 4         | 0.68%   |
| Fedora 39                    | 4         | 0.68%   |
| Fedora 31                    | 4         | 0.68%   |
| Ubuntu Unity 18.04           | 3         | 0.51%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 165       | 30.84%  |
| Linux Mint    | 42        | 7.85%   |
| Pop!_OS       | 37        | 6.92%   |
| OpenMandriva  | 35        | 6.54%   |
| Fedora        | 35        | 6.54%   |
| Debian        | 32        | 5.98%   |
| Manjaro       | 26        | 4.86%   |
| Endless       | 24        | 4.49%   |
| Zorin         | 17        | 3.18%   |
| Arch          | 15        | 2.8%    |
| Kubuntu       | 13        | 2.43%   |
| KDE neon      | 10        | 1.87%   |
| ROSA          | 9         | 1.68%   |
| openSUSE      | 9         | 1.68%   |
| ArcoLinux     | 8         | 1.5%    |
| Ubuntu MATE   | 6         | 1.12%   |
| Elementary    | 6         | 1.12%   |
| EndeavourOS   | 5         | 0.93%   |
| Xubuntu       | 4         | 0.75%   |
| Ubuntu Budgie | 4         | 0.75%   |
| Kali          | 4         | 0.75%   |
| Ubuntu Unity  | 3         | 0.56%   |
| Nobara        | 3         | 0.56%   |
| Gentoo        | 3         | 0.56%   |
| Raspbian      | 2         | 0.37%   |
| MX            | 2         | 0.37%   |
| Lubuntu       | 2         | 0.37%   |
| LMDE          | 2         | 0.37%   |
| LinuxFX       | 2         | 0.37%   |
| Xero          | 1         | 0.19%   |
| SteamOS       | 1         | 0.19%   |
| Rocky Linux   | 1         | 0.19%   |
| Q4OS          | 1         | 0.19%   |
| Parrot        | 1         | 0.19%   |
| Garuda Linux  | 1         | 0.19%   |
| Clear Linux   | 1         | 0.19%   |
| CentOS        | 1         | 0.19%   |
| Artix         | 1         | 0.19%   |
| Arch ARM      | 1         | 0.19%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 14        | 2.2%    |
| 5.4.0-42-generic         | 8         | 1.26%   |
| 5.11.0-38-generic        | 8         | 1.26%   |
| 5.8.0-14-generic         | 6         | 0.94%   |
| 5.4.0-58-generic         | 6         | 0.94%   |
| 5.3.0-28-generic         | 6         | 0.94%   |
| 5.11.0-7620-generic      | 6         | 0.94%   |
| 5.10.14-desktop-1omv4002 | 6         | 0.94%   |
| 5.4.0-91-generic         | 5         | 0.79%   |
| 5.4.0-48-generic         | 5         | 0.79%   |
| 5.4.0-37-generic         | 5         | 0.79%   |
| 5.11.0-41-generic        | 5         | 0.79%   |
| 5.8.0-59-generic         | 4         | 0.63%   |
| 5.8.0-48-generic         | 4         | 0.63%   |
| 5.4.0-52-generic         | 4         | 0.63%   |
| 5.3.0-26-generic         | 4         | 0.63%   |
| 5.15.0-58-generic        | 4         | 0.63%   |
| 5.15.0-56-generic        | 4         | 0.63%   |
| 5.13.0-30-generic        | 4         | 0.63%   |
| 5.11.0-40-generic        | 4         | 0.63%   |
| 4.18.0-10-generic        | 4         | 0.63%   |
| 6.4.11-desktop-1omv2390  | 3         | 0.47%   |
| 6.2.9-300.fc38.x86_64    | 3         | 0.47%   |
| 6.2.6-desktop-1omv2390   | 3         | 0.47%   |
| 6.2.6-76060206-generic   | 3         | 0.47%   |
| 6.2.0-26-generic         | 3         | 0.47%   |
| 6.1.1-desktop-1omv2290   | 3         | 0.47%   |
| 6.1.0-13-amd64           | 3         | 0.47%   |
| 5.8.16-2-MANJARO         | 3         | 0.47%   |
| 5.8.0-7630-generic       | 3         | 0.47%   |
| 5.8.0-43-generic         | 3         | 0.47%   |
| 5.4.0-47-generic         | 3         | 0.47%   |
| 5.4.0-40-generic         | 3         | 0.47%   |
| 5.4.0-29-generic         | 3         | 0.47%   |
| 5.4.0-26-generic         | 3         | 0.47%   |
| 5.4.0-19-generic         | 3         | 0.47%   |
| 5.4.0-100-generic        | 3         | 0.47%   |
| 5.3.0-40-generic         | 3         | 0.47%   |
| 5.3.0-23-generic         | 3         | 0.47%   |
| 5.19.0-38-generic        | 3         | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 90        | 14.93%  |
| 5.11.0  | 48        | 7.96%   |
| 5.15.0  | 41        | 6.8%    |
| 5.8.0   | 26        | 4.31%   |
| 4.15.0  | 26        | 4.31%   |
| 5.3.0   | 24        | 3.98%   |
| 5.13.0  | 24        | 3.98%   |
| 5.10.0  | 20        | 3.32%   |
| 4.18.0  | 19        | 3.15%   |
| 5.19.0  | 17        | 2.82%   |
| 5.16.7  | 15        | 2.49%   |
| 5.0.0   | 14        | 2.32%   |
| 6.2.0   | 12        | 1.99%   |
| 6.2.6   | 7         | 1.16%   |
| 6.1.0   | 7         | 1.16%   |
| 5.10.14 | 6         | 1%      |
| 4.19.0  | 6         | 1%      |
| 6.1.1   | 5         | 0.83%   |
| 6.4.11  | 4         | 0.66%   |
| 5.9.16  | 4         | 0.66%   |
| 5.16.11 | 4         | 0.66%   |
| 5.14.0  | 4         | 0.66%   |
| 5.12.4  | 4         | 0.66%   |
| 6.5.9   | 3         | 0.5%    |
| 6.2.9   | 3         | 0.5%    |
| 6.0.5   | 3         | 0.5%    |
| 6.0.0   | 3         | 0.5%    |
| 5.8.16  | 3         | 0.5%    |
| 5.3.18  | 3         | 0.5%    |
| 5.15.8  | 3         | 0.5%    |
| 4.9.60  | 3         | 0.5%    |
| 6.6.2   | 2         | 0.33%   |
| 6.5.4   | 2         | 0.33%   |
| 6.2.15  | 2         | 0.33%   |
| 6.2.1   | 2         | 0.33%   |
| 6.1.38  | 2         | 0.33%   |
| 5.9.11  | 2         | 0.33%   |
| 5.7.11  | 2         | 0.33%   |
| 5.5.0   | 2         | 0.33%   |
| 5.19.13 | 2         | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 97        | 16.36%  |
| 5.15    | 56        | 9.44%   |
| 5.11    | 55        | 9.27%   |
| 5.10    | 36        | 6.07%   |
| 6.2     | 30        | 5.06%   |
| 5.8     | 30        | 5.06%   |
| 5.3     | 28        | 4.72%   |
| 5.13    | 27        | 4.55%   |
| 4.15    | 26        | 4.38%   |
| 5.19    | 25        | 4.22%   |
| 5.16    | 23        | 3.88%   |
| 6.1     | 20        | 3.37%   |
| 4.18    | 19        | 3.2%    |
| 5.0     | 15        | 2.53%   |
| 6.5     | 11        | 1.85%   |
| 6.0     | 10        | 1.69%   |
| 5.9     | 9         | 1.52%   |
| 5.18    | 8         | 1.35%   |
| 5.17    | 8         | 1.35%   |
| 6.4     | 7         | 1.18%   |
| 5.14    | 7         | 1.18%   |
| 4.9     | 6         | 1.01%   |
| 4.19    | 6         | 1.01%   |
| 6.6     | 5         | 0.84%   |
| 5.6     | 5         | 0.84%   |
| 5.12    | 5         | 0.84%   |
| 6.3     | 4         | 0.67%   |
| 5.7     | 3         | 0.51%   |
| 5.5     | 2         | 0.34%   |
| 4.16    | 2         | 0.34%   |
| 5.2     | 1         | 0.17%   |
| 5.1     | 1         | 0.17%   |
| 4.17    | 1         | 0.17%   |
| 4.14    | 1         | 0.17%   |
| 4.13    | 1         | 0.17%   |
| 4.12    | 1         | 0.17%   |
| 4.1     | 1         | 0.17%   |
| 3.10    | 1         | 0.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 502       | 97.1%   |
| i686    | 9         | 1.74%   |
| aarch64 | 4         | 0.77%   |
| armv7l  | 2         | 0.39%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 246       | 45.47%  |
| KDE5            | 104       | 19.22%  |
| Unknown         | 63        | 11.65%  |
| X-Cinnamon      | 29        | 5.36%   |
| XFCE            | 23        | 4.25%   |
| Cinnamon        | 12        | 2.22%   |
| MATE            | 11        | 2.03%   |
| KDE             | 10        | 1.85%   |
| Pantheon        | 5         | 0.92%   |
| GNOME Flashback | 5         | 0.92%   |
| Budgie          | 5         | 0.92%   |
| LXQt            | 4         | 0.74%   |
| LXDE            | 4         | 0.74%   |
| KDE4            | 4         | 0.74%   |
| DWM             | 4         | 0.74%   |
| Unity           | 3         | 0.55%   |
| Openbox         | 2         | 0.37%   |
| i3              | 2         | 0.37%   |
| ubuntu          | 1         | 0.18%   |
| Trinity         | 1         | 0.18%   |
| GNUstep         | 1         | 0.18%   |
| Deepin          | 1         | 0.18%   |
| bspwm           | 1         | 0.18%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 402       | 73.63%  |
| Wayland | 94        | 17.22%  |
| Unknown | 38        | 6.96%   |
| Tty     | 12        | 2.2%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 247       | 46.08%  |
| SDDM    | 88        | 16.42%  |
| GDM     | 75        | 13.99%  |
| GDM3    | 55        | 10.26%  |
| LightDM | 52        | 9.7%    |
| TDM     | 15        | 2.8%    |
| KDM     | 3         | 0.56%   |
| Ly      | 1         | 0.19%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 302       | 56.87%  |
| hr_HR   | 119       | 22.41%  |
| Unknown | 65        | 12.24%  |
| en_GB   | 26        | 4.9%    |
| C       | 7         | 1.32%   |
| de_DE   | 6         | 1.13%   |
| ru_RU   | 1         | 0.19%   |
| pl_PL   | 1         | 0.19%   |
| hr_BA   | 1         | 0.19%   |
| fr_FR   | 1         | 0.19%   |
| en_DE   | 1         | 0.19%   |
| en_150  | 1         | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 295       | 55.77%  |
| BIOS | 234       | 44.23%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 410       | 76.92%  |
| Btrfs   | 45        | 8.44%   |
| Overlay | 33        | 6.19%   |
| Unknown | 21        | 3.94%   |
| Zfs     | 9         | 1.69%   |
| Xfs     | 7         | 1.31%   |
| Tmpfs   | 6         | 1.13%   |
| Jfs     | 1         | 0.19%   |
| Ext2    | 1         | 0.19%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 258       | 49.05%  |
| GPT     | 212       | 40.3%   |
| MBR     | 56        | 10.65%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 461       | 87.31%  |
| Yes       | 67        | 12.69%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 384       | 72.87%  |
| Yes       | 143       | 27.13%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 95        | 18.38%  |
| ASUSTek Computer        | 82        | 15.86%  |
| Hewlett-Packard         | 77        | 14.89%  |
| Acer                    | 59        | 11.41%  |
| Dell                    | 44        | 8.51%   |
| ASRock                  | 40        | 7.74%   |
| Gigabyte Technology     | 30        | 5.8%    |
| MSI                     | 14        | 2.71%   |
| Intel                   | 10        | 1.93%   |
| Apple                   | 8         | 1.55%   |
| Toshiba                 | 7         | 1.35%   |
| Pegatron                | 5         | 0.97%   |
| Samsung Electronics     | 4         | 0.77%   |
| Raspberry Pi Foundation | 4         | 0.77%   |
| Fujitsu Siemens         | 4         | 0.77%   |
| eMachines               | 4         | 0.77%   |
| HUAWEI                  | 3         | 0.58%   |
| ECS                     | 3         | 0.58%   |
| TUXEDO                  | 2         | 0.39%   |
| Tactus                  | 2         | 0.39%   |
| Supermicro              | 2         | 0.39%   |
| Unknown                 | 2         | 0.39%   |
| WinFast                 | 1         | 0.19%   |
| Valve                   | 1         | 0.19%   |
| Timi                    | 1         | 0.19%   |
| System76                | 1         | 0.19%   |
| SHENZHEN X&F TECHNOLOGY | 1         | 0.19%   |
| Schenker                | 1         | 0.19%   |
| Razer                   | 1         | 0.19%   |
| Pretech                 | 1         | 0.19%   |
| Nvidia                  | 1         | 0.19%   |
| Notebook                | 1         | 0.19%   |
| Medion                  | 1         | 0.19%   |
| HPE                     | 1         | 0.19%   |
| Foxconn                 | 1         | 0.19%   |
| Chuwi                   | 1         | 0.19%   |
| AMI                     | 1         | 0.19%   |
| ABIT                    | 1         | 0.19%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| ASUS All Series                           | 6         | 1.16%   |
| ASRock B450M-HDV R4.0                     | 4         | 0.77%   |
| Acer Aspire A315-21                       | 4         | 0.77%   |
| Unknown                                   | 4         | 0.77%   |
| Lenovo Legion 5 15ARH05 82B5              | 3         | 0.58%   |
| Lenovo G710 20252                         | 3         | 0.58%   |
| ASUS PRIME A320M-K                        | 3         | 0.58%   |
| Acer Aspire A515-51G                      | 3         | 0.58%   |
| TUXEDO Pulse 15 Gen1                      | 2         | 0.39%   |
| Tactus GeoBook 140                        | 2         | 0.39%   |
| RPi Raspberry Pi 4 Model B Rev 1.1        | 2         | 0.39%   |
| MSI MS-7850                               | 2         | 0.39%   |
| Lenovo Z50-70 20354                       | 2         | 0.39%   |
| Lenovo ThinkBook 16p Gen 2 20YM           | 2         | 0.39%   |
| Lenovo ThinkBook 15 G2 ITL 20VE           | 2         | 0.39%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ          | 2         | 0.39%   |
| Lenovo G40-30 80FY                        | 2         | 0.39%   |
| Intel DH61CR AAG14064-204                 | 2         | 0.39%   |
| HP ProBook 450 G7                         | 2         | 0.39%   |
| HP Presario CQ57                          | 2         | 0.39%   |
| HP OMEN by Laptop                         | 2         | 0.39%   |
| HP Laptop 15s-eq2xxx                      | 2         | 0.39%   |
| HP EliteBook 8560p                        | 2         | 0.39%   |
| HP EliteBook 850 G6                       | 2         | 0.39%   |
| HP EliteBook 845 G8 Notebook PC           | 2         | 0.39%   |
| HP 2000                                   | 2         | 0.39%   |
| Gigabyte A320M-S2H                        | 2         | 0.39%   |
| Fujitsu Siemens ESPRIMO Mobile V5535      | 2         | 0.39%   |
| Dell XPS 13 9310                          | 2         | 0.39%   |
| Dell Vostro 3500                          | 2         | 0.39%   |
| Dell Inspiron N5110                       | 2         | 0.39%   |
| Dell Inspiron 5570                        | 2         | 0.39%   |
| ASUS X751NV                               | 2         | 0.39%   |
| ASUS VivoBook_ASUSLaptop M3500QA_M3500QA  | 2         | 0.39%   |
| ASUS VivoBook 15_ASUS Laptop X560UD       | 2         | 0.39%   |
| ASUS VivoBook 15_ASUS Laptop X540BP       | 2         | 0.39%   |
| ASUS P8H77-V LE                           | 2         | 0.39%   |
| ASUS N56VZ                                | 2         | 0.39%   |
| ASUS M5A78L LE                            | 2         | 0.39%   |
| ASUS ASUS EXPERTBOOK B1400CEAEY_B1400CEAE | 2         | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Acer Aspire       | 42        | 8.12%   |
| Lenovo ThinkPad   | 37        | 7.16%   |
| HP EliteBook      | 17        | 3.29%   |
| ASUS VivoBook     | 11        | 2.13%   |
| Lenovo IdeaPad    | 10        | 1.93%   |
| HP ProBook        | 10        | 1.93%   |
| Dell Vostro       | 10        | 1.93%   |
| Dell Latitude     | 10        | 1.93%   |
| Lenovo Legion     | 9         | 1.74%   |
| HP Pavilion       | 9         | 1.74%   |
| Dell Inspiron     | 9         | 1.74%   |
| HP Laptop         | 8         | 1.55%   |
| ASUS PRIME        | 8         | 1.55%   |
| Lenovo ThinkBook  | 7         | 1.35%   |
| Dell XPS          | 7         | 1.35%   |
| Acer Swift        | 7         | 1.35%   |
| Toshiba Satellite | 6         | 1.16%   |
| ASUS ZenBook      | 6         | 1.16%   |
| ASUS TUF          | 6         | 1.16%   |
| ASUS ROG          | 6         | 1.16%   |
| ASUS All          | 6         | 1.16%   |
| RPi Raspberry     | 4         | 0.77%   |
| HP Compaq         | 4         | 0.77%   |
| HP 250            | 4         | 0.77%   |
| ASRock B450M-HDV  | 4         | 0.77%   |
| Acer Nitro        | 4         | 0.77%   |
| Unknown           | 4         | 0.77%   |
| Lenovo IdeaCentre | 3         | 0.58%   |
| Lenovo G710       | 3         | 0.58%   |
| HP ZBook          | 3         | 0.58%   |
| HP OMEN           | 3         | 0.58%   |
| HP EliteDesk      | 3         | 0.58%   |
| Dell OptiPlex     | 3         | 0.58%   |
| ASUS ASUS         | 3         | 0.58%   |
| TUXEDO Pulse      | 2         | 0.39%   |
| Tactus GeoBook    | 2         | 0.39%   |
| MSI MS-7850       | 2         | 0.39%   |
| Lenovo Z50-70     | 2         | 0.39%   |
| Lenovo Yoga       | 2         | 0.39%   |
| Lenovo G40-30     | 2         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 59        | 11.41%  |
| 2020    | 53        | 10.25%  |
| 2021    | 48        | 9.28%   |
| 2017    | 46        | 8.9%    |
| 2013    | 40        | 7.74%   |
| 2019    | 38        | 7.35%   |
| 2011    | 34        | 6.58%   |
| 2014    | 31        | 6%      |
| 2012    | 30        | 5.8%    |
| 2016    | 23        | 4.45%   |
| 2022    | 20        | 3.87%   |
| 2008    | 17        | 3.29%   |
| 2007    | 17        | 3.29%   |
| 2009    | 16        | 3.09%   |
| 2015    | 15        | 2.9%    |
| 2010    | 14        | 2.71%   |
| 2006    | 5         | 0.97%   |
| Unknown | 5         | 0.97%   |
| 2023    | 4         | 0.77%   |
| 2005    | 2         | 0.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 329       | 63.64%  |
| Desktop        | 161       | 31.14%  |
| All in one     | 7         | 1.35%   |
| System on chip | 5         | 0.97%   |
| Convertible    | 5         | 0.97%   |
| Mini pc        | 5         | 0.97%   |
| Server         | 3         | 0.58%   |
| Stick pc       | 1         | 0.19%   |
| Tablet         | 1         | 0.19%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 470       | 90.04%  |
| Enabled  | 52        | 9.96%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 517       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 120       | 22.81%  |
| 8.01-16.0   | 120       | 22.81%  |
| 16.01-24.0  | 101       | 19.2%   |
| 3.01-4.0    | 85        | 16.16%  |
| 32.01-64.0  | 47        | 8.94%   |
| 1.01-2.0    | 22        | 4.18%   |
| 24.01-32.0  | 16        | 3.04%   |
| 64.01-256.0 | 9         | 1.71%   |
| 2.01-3.0    | 6         | 1.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 193       | 32.99%  |
| 2.01-3.0   | 148       | 25.3%   |
| 4.01-8.0   | 101       | 17.26%  |
| 3.01-4.0   | 77        | 13.16%  |
| 0.51-1.0   | 29        | 4.96%   |
| 8.01-16.0  | 27        | 4.62%   |
| 16.01-24.0 | 6         | 1.03%   |
| 0.01-0.5   | 3         | 0.51%   |
| 24.01-32.0 | 1         | 0.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 327       | 61.01%  |
| 2       | 128       | 23.88%  |
| 3       | 41        | 7.65%   |
| 4       | 17        | 3.17%   |
| 5       | 11        | 2.05%   |
| 0       | 5         | 0.93%   |
| 6       | 3         | 0.56%   |
| 14      | 1         | 0.19%   |
| 8       | 1         | 0.19%   |
| 7       | 1         | 0.19%   |
| Unknown | 1         | 0.19%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 339       | 64.94%  |
| Yes       | 183       | 35.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 444       | 85.71%  |
| No        | 74        | 14.29%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 402       | 77.46%  |
| No        | 117       | 22.54%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 325       | 61.9%   |
| No        | 200       | 38.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Croatia | 517       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Zagreb           | 308       | 52.38%  |
| Split            | 33        | 5.61%   |
| Rijeka           | 27        | 4.59%   |
| Varaždin        | 13        | 2.21%   |
| Velika Gorica    | 10        | 1.7%    |
| Pula             | 10        | 1.7%    |
| Osijek           | 10        | 1.7%    |
| Koprivnica       | 10        | 1.7%    |
| Bjelovar         | 8         | 1.36%   |
| Zaprešić       | 7         | 1.19%   |
| Zadar            | 6         | 1.02%   |
| Čakovec         | 6         | 1.02%   |
| Virovitica       | 5         | 0.85%   |
| Samobor          | 5         | 0.85%   |
| Jesenice         | 4         | 0.68%   |
| Đakovo          | 3         | 0.51%   |
| Pitomaca         | 3         | 0.51%   |
| Petrinja         | 3         | 0.51%   |
| Krizevci         | 3         | 0.51%   |
| Karlovac         | 3         | 0.51%   |
| GJurgevac        | 3         | 0.51%   |
| Vinkovci         | 2         | 0.34%   |
| Supetar          | 2         | 0.34%   |
| Slatina          | 2         | 0.34%   |
| Sisak            | 2         | 0.34%   |
| Sesvete          | 2         | 0.34%   |
| Rovinj           | 2         | 0.34%   |
| Omiš            | 2         | 0.34%   |
| Novska           | 2         | 0.34%   |
| Matulji          | 2         | 0.34%   |
| Labin            | 2         | 0.34%   |
| Komiža          | 2         | 0.34%   |
| Kastav           | 2         | 0.34%   |
| Ivanja Reka      | 2         | 0.34%   |
| Hvar             | 2         | 0.34%   |
| Drakulica Rijeka | 2         | 0.34%   |
| Cres             | 2         | 0.34%   |
| Buzin            | 2         | 0.34%   |
| Zminj            | 1         | 0.17%   |
| Zabok            | 1         | 0.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 125       | 198    | 16.76%  |
| Samsung Electronics       | 106       | 151    | 14.21%  |
| Kingston                  | 77        | 108    | 10.32%  |
| Seagate                   | 69        | 110    | 9.25%   |
| Toshiba                   | 52        | 74     | 6.97%   |
| SanDisk                   | 36        | 45     | 4.83%   |
| SK hynix                  | 31        | 46     | 4.16%   |
| Crucial                   | 31        | 45     | 4.16%   |
| Intel                     | 26        | 35     | 3.49%   |
| Micron Technology         | 23        | 26     | 3.08%   |
| Unknown                   | 22        | 25     | 2.95%   |
| Hitachi                   | 16        | 20     | 2.14%   |
| A-DATA Technology         | 16        | 20     | 2.14%   |
| Patriot                   | 10        | 14     | 1.34%   |
| HGST                      | 9         | 9      | 1.21%   |
| Apple                     | 9         | 15     | 1.21%   |
| Silicon Motion            | 6         | 8      | 0.8%    |
| Transcend                 | 5         | 10     | 0.67%   |
| Netac                     | 5         | 5      | 0.67%   |
| Fujitsu                   | 5         | 7      | 0.67%   |
| Phison                    | 4         | 4      | 0.54%   |
| LITEON                    | 4         | 5      | 0.54%   |
| KIOXIA                    | 3         | 3      | 0.4%    |
| Gigabyte Technology       | 3         | 3      | 0.4%    |
| Corsair                   | 3         | 3      | 0.4%    |
| UMIS                      | 2         | 2      | 0.27%   |
| StoreJet                  | 2         | 2      | 0.27%   |
| Realtek Semiconductor     | 2         | 4      | 0.27%   |
| Phison Electronics        | 2         | 2      | 0.27%   |
| OCZ                       | 2         | 3      | 0.27%   |
| Micron/Crucial Technology | 2         | 2      | 0.27%   |
| Maxtor                    | 2         | 2      | 0.27%   |
| Lenovo                    | 2         | 3      | 0.27%   |
| KingFast                  | 2         | 4      | 0.27%   |
| JMicron Technology        | 2         | 2      | 0.27%   |
| Intenso                   | 2         | 3      | 0.27%   |
| HPE                       | 2         | 4      | 0.27%   |
| AMD                       | 2         | 5      | 0.27%   |
| ADATA Technology          | 2         | 2      | 0.27%   |
| XPG                       | 1         | 3      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 13        | 1.61%   |
| Kingston SA400S37120G 120GB SSD                     | 11        | 1.36%   |
| Samsung NVMe SSD Drive 512GB                        | 9         | 1.12%   |
| Kingston SA400S37480G 480GB SSD                     | 9         | 1.12%   |
| Toshiba MQ01ABD100 1TB                              | 7         | 0.87%   |
| Samsung SSD 850 EVO 250GB                           | 7         | 0.87%   |
| SanDisk NVMe SSD Drive 512GB                        | 6         | 0.74%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD                 | 6         | 0.74%   |
| Crucial CT240BX500SSD1 240GB                        | 6         | 0.74%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB                  | 5         | 0.62%   |
| Toshiba HDWD130 3TB                                 | 5         | 0.62%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 5         | 0.62%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 5         | 0.62%   |
| Kingston SV300S37A120G 120GB SSD                    | 5         | 0.62%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 4         | 0.5%    |
| Unknown MMC Card  32GB                              | 4         | 0.5%    |
| Toshiba HDWD110 1TB                                 | 4         | 0.5%    |
| Seagate ST500LT012-1DG142 500GB                     | 4         | 0.5%    |
| Seagate ST1000LM035-1RK172 1TB                      | 4         | 0.5%    |
| Samsung SSD 970 EVO Plus 1TB                        | 4         | 0.5%    |
| Samsung SSD 860 QVO 1TB                             | 4         | 0.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 4         | 0.5%    |
| Patriot Burst 240GB SSD                             | 4         | 0.5%    |
| HGST HTS721010A9E630 1TB                            | 4         | 0.5%    |
| A-DATA SU650 240GB SSD                              | 4         | 0.5%    |
| WDC WD5000AAKX-001CA0 500GB                         | 3         | 0.37%   |
| WDC WD10EZEX-08M2NA0 1TB                            | 3         | 0.37%   |
| Unknown SD/MMC/MS PRO 128GB                         | 3         | 0.37%   |
| Unknown MMC Card  128GB                             | 3         | 0.37%   |
| Toshiba MQ04ABF100 1TB                              | 3         | 0.37%   |
| Toshiba MQ01ABF050 500GB                            | 3         | 0.37%   |
| Toshiba DT01ACA100 1TB                              | 3         | 0.37%   |
| SK hynix NVMe SSD Drive 512GB                       | 3         | 0.37%   |
| SK hynix NVMe SSD Drive 256GB                       | 3         | 0.37%   |
| Seagate ST9500325AS 500GB                           | 3         | 0.37%   |
| Seagate ST2000LM007-1R8174 2TB                      | 3         | 0.37%   |
| Seagate ST1000LM048-2E7172 1TB                      | 3         | 0.37%   |
| Seagate ST1000DM010-2EP102 1TB                      | 3         | 0.37%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                | 3         | 0.37%   |
| SanDisk SDSSDA240G 240GB                            | 3         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 101       | 160    | 38.11%  |
| Seagate             | 67        | 97     | 25.28%  |
| Toshiba             | 42        | 61     | 15.85%  |
| Hitachi             | 16        | 20     | 6.04%   |
| Samsung Electronics | 9         | 12     | 3.4%    |
| HGST                | 9         | 9      | 3.4%    |
| Fujitsu             | 5         | 7      | 1.89%   |
| Unknown             | 3         | 3      | 1.13%   |
| StoreJet            | 2         | 2      | 0.75%   |
| Maxtor              | 2         | 2      | 0.75%   |
| TO Exter            | 1         | 1      | 0.38%   |
| SSK                 | 1         | 1      | 0.38%   |
| Min Yi U            | 1         | 1      | 0.38%   |
| JMicron Technology  | 1         | 1      | 0.38%   |
| Intenso             | 1         | 2      | 0.38%   |
| HPE                 | 1         | 2      | 0.38%   |
| HGST HTS            | 1         | 1      | 0.38%   |
| External            | 1         | 1      | 0.38%   |
| ASMedia             | 1         | 1      | 0.38%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 65        | 86     | 26.21%  |
| Samsung Electronics | 38        | 57     | 15.32%  |
| Crucial             | 26        | 37     | 10.48%  |
| SanDisk             | 18        | 25     | 7.26%   |
| A-DATA Technology   | 14        | 17     | 5.65%   |
| Intel               | 13        | 17     | 5.24%   |
| Micron Technology   | 10        | 11     | 4.03%   |
| WDC                 | 9         | 11     | 3.63%   |
| Patriot             | 9         | 13     | 3.63%   |
| SK hynix            | 8         | 14     | 3.23%   |
| Apple               | 7         | 11     | 2.82%   |
| Netac               | 4         | 4      | 1.61%   |
| Transcend           | 3         | 4      | 1.21%   |
| LITEON              | 3         | 4      | 1.21%   |
| Gigabyte Technology | 3         | 3      | 1.21%   |
| Toshiba             | 2         | 4      | 0.81%   |
| OCZ                 | 2         | 3      | 0.81%   |
| AMD                 | 2         | 5      | 0.81%   |
| SPCC                | 1         | 1      | 0.4%    |
| Seagate             | 1         | 1      | 0.4%    |
| PNY                 | 1         | 1      | 0.4%    |
| Mushkin             | 1         | 2      | 0.4%    |
| KingSpec            | 1         | 1      | 0.4%    |
| Kingmax             | 1         | 1      | 0.4%    |
| Intenso             | 1         | 1      | 0.4%    |
| INNOVATION IT       | 1         | 1      | 0.4%    |
| GOODRAM             | 1         | 1      | 0.4%    |
| Emtec               | 1         | 1      | 0.4%    |
| Corsair             | 1         | 1      | 0.4%    |
| China               | 1         | 1      | 0.4%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 228       | 384    | 33.93%  |
| SSD     | 214       | 339    | 31.85%  |
| NVMe    | 201       | 286    | 29.91%  |
| MMC     | 19        | 22     | 2.83%   |
| Unknown | 10        | 23     | 1.49%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 351       | 703    | 58.99%  |
| NVMe | 201       | 286    | 33.78%  |
| SAS  | 24        | 43     | 4.03%   |
| MMC  | 19        | 22     | 3.19%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 275       | 441    | 60.31%  |
| 0.51-1.0   | 125       | 183    | 27.41%  |
| 1.01-2.0   | 29        | 50     | 6.36%   |
| 2.01-3.0   | 14        | 29     | 3.07%   |
| 3.01-4.0   | 10        | 16     | 2.19%   |
| 4.01-10.0  | 3         | 4      | 0.66%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 160       | 29.04%  |
| 251-500        | 129       | 23.41%  |
| 501-1000       | 84        | 15.25%  |
| 1001-2000      | 52        | 9.44%   |
| 1-20           | 32        | 5.81%   |
| 51-100         | 30        | 5.44%   |
| More than 3000 | 23        | 4.17%   |
| Unknown        | 16        | 2.9%    |
| 21-50          | 15        | 2.72%   |
| 2001-3000      | 10        | 1.81%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 211       | 36.19%  |
| 21-50          | 107       | 18.35%  |
| 101-250        | 66        | 11.32%  |
| 51-100         | 62        | 10.63%  |
| 251-500        | 51        | 8.75%   |
| 501-1000       | 41        | 7.03%   |
| Unknown        | 16        | 2.74%   |
| 1001-2000      | 15        | 2.57%   |
| More than 3000 | 7         | 1.2%    |
| 2001-3000      | 7         | 1.2%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 4      | 4.08%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1         | 1      | 2.04%   |
| WDC WD6400AAKS-07A7B0 640GB          | 1         | 1      | 2.04%   |
| WDC WD600VE-75HDT0 64GB              | 1         | 1      | 2.04%   |
| WDC WD5003ABYX-88 LEN 500GB          | 1         | 1      | 2.04%   |
| WDC WD5000AAKX-221CA1 500GB          | 1         | 1      | 2.04%   |
| WDC WD3200AAKS-00L9A0 320GB          | 1         | 1      | 2.04%   |
| WDC WD2500AAKX-75U6AA0 250GB         | 1         | 1      | 2.04%   |
| WDC WD10JPCX-24UE4T0 1TB             | 1         | 1      | 2.04%   |
| WDC WD10EZRZ-00HTKB0 1TB             | 1         | 1      | 2.04%   |
| WDC WD10EZEX-08M2NA0 1TB             | 1         | 1      | 2.04%   |
| WDC WD10EZEX-00MFCA0 1TB             | 1         | 1      | 2.04%   |
| Transcend TS480GSSD220S 480GB        | 1         | 1      | 2.04%   |
| Toshiba MK6459GSXP 640GB             | 1         | 1      | 2.04%   |
| Toshiba MK2555GSX 250GB              | 1         | 1      | 2.04%   |
| Toshiba DT01ACA100 1TB               | 1         | 1      | 2.04%   |
| SPCC Solid State Disk 128GB          | 1         | 1      | 2.04%   |
| SK hynix SH920 2.5 7MM 256GB SSD     | 1         | 2      | 2.04%   |
| SK hynix SC210 2.5 7MM 256GB SSD     | 1         | 1      | 2.04%   |
| Seagate ST9500420AS 500GB            | 1         | 1      | 2.04%   |
| Seagate ST9500325AS 500GB            | 1         | 1      | 2.04%   |
| Seagate ST9250827AS 250GB            | 1         | 1      | 2.04%   |
| Seagate ST500DM002-1BD142 500GB      | 1         | 2      | 2.04%   |
| Seagate ST3250410AS 250GB            | 1         | 1      | 2.04%   |
| Seagate ST31500341AS 1TB             | 1         | 1      | 2.04%   |
| Seagate ST2000LM007-1R8174 2TB       | 1         | 1      | 2.04%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 1      | 2.04%   |
| Seagate ST1000DX002-2DV162 1TB       | 1         | 1      | 2.04%   |
| SanDisk SDSSDXPS960G 960GB           | 1         | 1      | 2.04%   |
| SanDisk SDSSDA240G 240GB             | 1         | 1      | 2.04%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD  | 1         | 1      | 2.04%   |
| LITEON LMH-256V2M-11 MSATA 256GB SSD | 1         | 1      | 2.04%   |
| Kingston SHFS37A120G 120GB SSD       | 1         | 1      | 2.04%   |
| Intel SSDSC2KW512G8 512GB            | 1         | 1      | 2.04%   |
| Intel SSDSC2KF256H6 SATA 256GB       | 1         | 2      | 2.04%   |
| Intel SSDSC2BW180A4 180GB            | 1         | 1      | 2.04%   |
| Intel SSDSC2BW120A4 120GB            | 1         | 1      | 2.04%   |
| Hitachi HTS723232A7A364 320GB        | 1         | 1      | 2.04%   |
| Hitachi HTS542512K9SA00 120GB        | 1         | 1      | 2.04%   |
| Hitachi HDS723020BLA642 2TB          | 1         | 1      | 2.04%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 11        | 11     | 23.4%   |
| Seagate           | 10        | 14     | 21.28%  |
| Intel             | 4         | 5      | 8.51%   |
| Toshiba           | 3         | 3      | 6.38%   |
| Hitachi           | 3         | 3      | 6.38%   |
| HGST              | 3         | 3      | 6.38%   |
| Crucial           | 3         | 4      | 6.38%   |
| SK hynix          | 2         | 3      | 4.26%   |
| SanDisk           | 2         | 3      | 4.26%   |
| A-DATA Technology | 2         | 2      | 4.26%   |
| Transcend         | 1         | 1      | 2.13%   |
| SPCC              | 1         | 1      | 2.13%   |
| LITEON            | 1         | 1      | 2.13%   |
| Kingston          | 1         | 1      | 2.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 10        | 10     | 34.48%  |
| Seagate | 10        | 14     | 34.48%  |
| Toshiba | 3         | 3      | 10.34%  |
| Hitachi | 3         | 3      | 10.34%  |
| HGST    | 3         | 3      | 10.34%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 29        | 33     | 63.04%  |
| SSD  | 17        | 22     | 36.96%  |

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
| Detected | 301       | 585    | 53.65%  |
| Works    | 217       | 414    | 38.68%  |
| Malfunc  | 43        | 55     | 7.66%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 337       | 50%     |
| AMD                              | 103       | 15.28%  |
| Samsung Electronics              | 67        | 9.94%   |
| SanDisk                          | 34        | 5.04%   |
| SK hynix                         | 23        | 3.41%   |
| Kingston Technology Company      | 17        | 2.52%   |
| Micron Technology                | 13        | 1.93%   |
| Toshiba America Info Systems     | 10        | 1.48%   |
| Phison Electronics               | 9         | 1.34%   |
| Silicon Motion                   | 6         | 0.89%   |
| Nvidia                           | 6         | 0.89%   |
| Micron/Crucial Technology        | 6         | 0.89%   |
| JMicron Technology               | 6         | 0.89%   |
| Marvell Technology Group         | 5         | 0.74%   |
| ASMedia Technology               | 5         | 0.74%   |
| ADATA Technology                 | 5         | 0.74%   |
| KIOXIA                           | 3         | 0.45%   |
| VIA Technologies                 | 2         | 0.3%    |
| Union Memory (Shenzhen)          | 2         | 0.3%    |
| Silicon Integrated Systems [SiS] | 2         | 0.3%    |
| Realtek Semiconductor            | 2         | 0.3%    |
| Lite-On Technology               | 2         | 0.3%    |
| Lenovo                           | 2         | 0.3%    |
| Broadcom / LSI                   | 2         | 0.3%    |
| Transcend                        | 1         | 0.15%   |
| Silicon Image                    | 1         | 0.15%   |
| Seagate Technology               | 1         | 0.15%   |
| LSI Logic / Symbios Logic        | 1         | 0.15%   |
| Adaptec                          | 1         | 0.15%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 76        | 9.83%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 34        | 4.4%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 34        | 4.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 26        | 3.36%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 21        | 2.72%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 19        | 2.46%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 18        | 2.33%   |
| Intel Volume Management Device NVMe RAID Controller                            | 17        | 2.2%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 14        | 1.81%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 12        | 1.55%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 10        | 1.29%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 10        | 1.29%   |
| Intel Tiger Lake-LP SATA Controller                                            | 10        | 1.29%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 10        | 1.29%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 10        | 1.29%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 10        | 1.29%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 10        | 1.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 10        | 1.29%   |
| AMD FCH SATA Controller D                                                      | 10        | 1.29%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 9         | 1.16%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 9         | 1.16%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 9         | 1.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 9         | 1.16%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 9         | 1.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 9         | 1.16%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 8         | 1.03%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 8         | 1.03%   |
| AMD 400 Series Chipset SATA Controller                                         | 8         | 1.03%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 7         | 0.91%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 7         | 0.91%   |
| Intel Comet Lake SATA AHCI Controller                                          | 7         | 0.91%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 7         | 0.91%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 6         | 0.78%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 6         | 0.78%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 6         | 0.78%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 6         | 0.78%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 6         | 0.78%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 5         | 0.65%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 5         | 0.65%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 5         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 376       | 54.57%  |
| NVMe | 202       | 29.32%  |
| IDE  | 75        | 10.89%  |
| RAID | 35        | 5.08%   |
| SAS  | 1         | 0.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 372       | 71.95%  |
| AMD     | 139       | 26.89%  |
| ARM     | 5         | 0.97%   |
| Unknown | 1         | 0.19%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 12        | 2.31%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 11        | 2.12%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 11        | 2.12%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 7         | 1.35%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 7         | 1.35%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 6         | 1.15%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 1.15%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 6         | 1.15%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 5         | 0.96%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 5         | 0.96%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 0.96%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 0.96%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 0.96%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 5         | 0.96%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 0.77%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 0.77%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 0.77%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 4         | 0.77%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 4         | 0.77%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 4         | 0.77%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 4         | 0.77%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 3         | 0.58%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 3         | 0.58%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 3         | 0.58%   |
| Intel Pentium 3556U @ 1.70GHz                 | 3         | 0.58%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 3         | 0.58%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 3         | 0.58%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 0.58%   |
| Intel Core i5-9400F CPU @ 2.90GHz             | 3         | 0.58%   |
| Intel Core i5-6400 CPU @ 2.70GHz              | 3         | 0.58%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 0.58%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 0.58%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 3         | 0.58%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 0.58%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 3         | 0.58%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 3         | 0.58%   |
| Intel Core i3-10100F CPU @ 3.60GHz            | 3         | 0.58%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 3         | 0.58%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 0.58%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 3         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 124       | 23.85%  |
| Intel Core i7           | 69        | 13.27%  |
| Other                   | 44        | 8.46%   |
| Intel Core i3           | 38        | 7.31%   |
| AMD Ryzen 5             | 35        | 6.73%   |
| AMD Ryzen 7             | 31        | 5.96%   |
| Intel Core 2 Duo        | 27        | 5.19%   |
| Intel Pentium           | 21        | 4.04%   |
| Intel Celeron           | 12        | 2.31%   |
| AMD Ryzen 3             | 11        | 2.12%   |
| AMD Ryzen 9             | 9         | 1.73%   |
| Intel Atom              | 8         | 1.54%   |
| Intel Core i9           | 7         | 1.35%   |
| Intel Pentium Dual-Core | 6         | 1.15%   |
| Intel Pentium Dual      | 6         | 1.15%   |
| Intel Xeon              | 5         | 0.96%   |
| AMD Ryzen 5 PRO         | 5         | 0.96%   |
| AMD FX                  | 5         | 0.96%   |
| AMD E                   | 5         | 0.96%   |
| AMD A6                  | 5         | 0.96%   |
| AMD Athlon II X4        | 4         | 0.77%   |
| Intel Pentium Silver    | 3         | 0.58%   |
| Intel Core 2            | 3         | 0.58%   |
| AMD Phenom II X4        | 3         | 0.58%   |
| AMD Athlon X4           | 3         | 0.58%   |
| AMD Athlon 64 X2        | 3         | 0.58%   |
| Intel Pentium M         | 2         | 0.38%   |
| Intel Pentium 4         | 2         | 0.38%   |
| Intel Core 2 Quad       | 2         | 0.38%   |
| ARM BCM                 | 2         | 0.38%   |
| AMD Ryzen 7 PRO         | 2         | 0.38%   |
| AMD E1                  | 2         | 0.38%   |
| AMD Athlon              | 2         | 0.38%   |
| AMD A8                  | 2         | 0.38%   |
| Intel Xeon Bronze       | 1         | 0.19%   |
| Intel Genuine           | 1         | 0.19%   |
| Intel Celeron M         | 1         | 0.19%   |
| AMD Turion 64 X2 Mobile | 1         | 0.19%   |
| AMD Ryzen Threadripper  | 1         | 0.19%   |
| AMD Ryzen 3 PRO         | 1         | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 196       | 37.69%  |
| 4       | 193       | 37.12%  |
| 6       | 50        | 9.62%   |
| 8       | 46        | 8.85%   |
| 1       | 9         | 1.73%   |
| 12      | 7         | 1.35%   |
| 10      | 7         | 1.35%   |
| 16      | 3         | 0.58%   |
| 14      | 3         | 0.58%   |
| 3       | 3         | 0.58%   |
| 24      | 2         | 0.38%   |
| Unknown | 1         | 0.19%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 514       | 99.42%  |
| 2       | 2         | 0.39%   |
| Unknown | 1         | 0.19%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 341       | 65.83%  |
| 1       | 176       | 33.98%  |
| Unknown | 1         | 0.19%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 499       | 96.15%  |
| Unknown        | 14        | 2.7%    |
| 32-bit         | 5         | 0.96%   |
| 64-bit         | 1         | 0.19%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 139       | 25.36%  |
| 0x306c3    | 38        | 6.93%   |
| 0x206a7    | 20        | 3.65%   |
| 0x306a9    | 19        | 3.47%   |
| 0x906ea    | 18        | 3.28%   |
| 0x806ea    | 17        | 3.1%    |
| 0x806e9    | 17        | 3.1%    |
| 0x40651    | 14        | 2.55%   |
| 0x1067a    | 14        | 2.55%   |
| 0x806ec    | 11        | 2.01%   |
| 0x6fd      | 11        | 2.01%   |
| 0x806c1    | 10        | 1.82%   |
| 0x0a50000c | 10        | 1.82%   |
| 0x08600106 | 9         | 1.64%   |
| 0x08108109 | 9         | 1.64%   |
| 0x906e9    | 7         | 1.28%   |
| 0xa0652    | 6         | 1.09%   |
| 0x306d4    | 6         | 1.09%   |
| 0x08608103 | 6         | 1.09%   |
| 0x08600103 | 6         | 1.09%   |
| 0x0810100b | 6         | 1.09%   |
| 0xa0653    | 5         | 0.91%   |
| 0x906ed    | 5         | 0.91%   |
| 0x506e3    | 5         | 0.91%   |
| 0x30678    | 5         | 0.91%   |
| 0x0a50000d | 5         | 0.91%   |
| 0x0800820d | 5         | 0.91%   |
| 0x06006705 | 5         | 0.91%   |
| 0x6fb      | 4         | 0.73%   |
| 0x506c9    | 4         | 0.73%   |
| 0x406e3    | 4         | 0.73%   |
| 0x406c4    | 4         | 0.73%   |
| 0x20655    | 4         | 0.73%   |
| 0x10676    | 4         | 0.73%   |
| 0x0a601203 | 4         | 0.73%   |
| 0x08108102 | 4         | 0.73%   |
| 0x010000db | 4         | 0.73%   |
| 0x010000c8 | 4         | 0.73%   |
| 0xa0671    | 3         | 0.55%   |
| 0x906a3    | 3         | 0.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 95        | 18.34%  |
| Haswell          | 62        | 11.97%  |
| Unknown          | 30        | 5.79%   |
| Zen 2            | 27        | 5.21%   |
| SandyBridge      | 24        | 4.63%   |
| Penryn           | 24        | 4.63%   |
| IvyBridge        | 24        | 4.63%   |
| Zen+             | 21        | 4.05%   |
| Core             | 20        | 3.86%   |
| Zen 3            | 19        | 3.67%   |
| TigerLake        | 18        | 3.47%   |
| Skylake          | 16        | 3.09%   |
| CometLake        | 14        | 2.7%    |
| Zen              | 13        | 2.51%   |
| Silvermont       | 13        | 2.51%   |
| Alderlake Hybrid | 11        | 2.12%   |
| K10              | 9         | 1.74%   |
| Icelake          | 9         | 1.74%   |
| Broadwell        | 9         | 1.74%   |
| Piledriver       | 8         | 1.54%   |
| Excavator        | 8         | 1.54%   |
| Westmere         | 7         | 1.35%   |
| Goldmont plus    | 6         | 1.16%   |
| Bobcat           | 6         | 1.16%   |
| K8 Hammer        | 5         | 0.97%   |
| Goldmont         | 5         | 0.97%   |
| P6               | 4         | 0.77%   |
| NetBurst         | 2         | 0.39%   |
| Bulldozer        | 2         | 0.39%   |
| Bonnell          | 2         | 0.39%   |
| Tremont          | 1         | 0.19%   |
| Steamroller      | 1         | 0.19%   |
| Puma             | 1         | 0.19%   |
| Nehalem          | 1         | 0.19%   |
| Jaguar           | 1         | 0.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 286       | 44.34%  |
| Nvidia                           | 180       | 27.91%  |
| AMD                              | 172       | 26.67%  |
| Matrox Electronics Systems       | 3         | 0.47%   |
| Silicon Integrated Systems [SiS] | 2         | 0.31%   |
| VIA Technologies                 | 1         | 0.16%   |
| ATI Technologies                 | 1         | 0.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 25        | 3.81%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 19        | 2.9%    |
| Intel HD Graphics 620                                                                    | 18        | 2.74%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 18        | 2.74%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 18        | 2.74%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 17        | 2.59%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 14        | 2.13%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 14        | 2.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 13        | 1.98%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 13        | 1.98%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12        | 1.83%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 12        | 1.83%   |
| AMD Lucienne                                                                             | 10        | 1.52%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 10        | 1.52%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 1.37%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 8         | 1.22%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 8         | 1.22%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 1.22%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 7         | 1.07%   |
| Intel HD Graphics 5500                                                                   | 7         | 1.07%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 1.07%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 7         | 1.07%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 6         | 0.91%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 6         | 0.91%   |
| Intel HD Graphics 530                                                                    | 6         | 0.91%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 0.91%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 0.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 0.91%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 6         | 0.91%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 6         | 0.91%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 5         | 0.76%   |
| Nvidia GM108M [GeForce 840M]                                                             | 5         | 0.76%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 0.76%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 5         | 0.76%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 0.76%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 4         | 0.61%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 4         | 0.61%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 0.61%   |
| Intel HD Graphics 630                                                                    | 4         | 0.61%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 174       | 33.33%  |
| 1 x AMD         | 124       | 23.75%  |
| Intel + Nvidia  | 82        | 15.71%  |
| 1 x Nvidia      | 80        | 15.33%  |
| Intel + AMD     | 24        | 4.6%    |
| AMD + Nvidia    | 17        | 3.26%   |
| 2 x AMD         | 7         | 1.34%   |
| Other           | 6         | 1.15%   |
| 2 x Intel       | 2         | 0.38%   |
| 1 x SiS         | 2         | 0.38%   |
| 1 x Matrox      | 2         | 0.38%   |
| 1 x VIA         | 1         | 0.19%   |
| Nvidia + Matrox | 1         | 0.19%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 398       | 75.95%  |
| Proprietary | 106       | 20.23%  |
| Unknown     | 20        | 3.82%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 268       | 50.09%  |
| 1.01-2.0   | 82        | 15.33%  |
| 0.01-0.5   | 59        | 11.03%  |
| 3.01-4.0   | 47        | 8.79%   |
| 0.51-1.0   | 46        | 8.6%    |
| 7.01-8.0   | 18        | 3.36%   |
| 5.01-6.0   | 7         | 1.31%   |
| 2.01-3.0   | 4         | 0.75%   |
| 8.01-16.0  | 4         | 0.75%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 87        | 14.6%   |
| AU Optronics            | 70        | 11.74%  |
| Dell                    | 59        | 9.9%    |
| BOE                     | 58        | 9.73%   |
| LG Display              | 54        | 9.06%   |
| Chimei Innolux          | 49        | 8.22%   |
| AOC                     | 29        | 4.87%   |
| Goldstar                | 23        | 3.86%   |
| Philips                 | 20        | 3.36%   |
| Acer                    | 18        | 3.02%   |
| Lenovo                  | 13        | 2.18%   |
| Sharp                   | 10        | 1.68%   |
| Hewlett-Packard         | 10        | 1.68%   |
| Ancor Communications    | 10        | 1.68%   |
| Apple                   | 8         | 1.34%   |
| PANDA                   | 6         | 1.01%   |
| CSO                     | 6         | 1.01%   |
| BenQ                    | 6         | 1.01%   |
| Chi Mei Optoelectronics | 5         | 0.84%   |
| LG Philips              | 4         | 0.67%   |
| Grundig                 | 4         | 0.67%   |
| ASUSTek Computer        | 4         | 0.67%   |
| Sony                    | 3         | 0.5%    |
| LG Electronics          | 3         | 0.5%    |
| InfoVision              | 3         | 0.5%    |
| Fujitsu Siemens         | 3         | 0.5%    |
| Unknown                 | 2         | 0.34%   |
| Quanta Display          | 2         | 0.34%   |
| Panasonic               | 2         | 0.34%   |
| InnoLux Display         | 2         | 0.34%   |
| Huion                   | 2         | 0.34%   |
| Vestel Elektronik       | 1         | 0.17%   |
| Valve                   | 1         | 0.17%   |
| TSL                     | 1         | 0.17%   |
| TMX                     | 1         | 0.17%   |
| RTK                     | 1         | 0.17%   |
| NOA VISION              | 1         | 0.17%   |
| NEC Computers           | 1         | 0.17%   |
| NCS                     | 1         | 0.17%   |
| MStar                   | 1         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 7         | 1.13%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 6         | 0.97%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch          | 4         | 0.64%   |
| Grundig WXGA GRU4448 1600x1200                                        | 4         | 0.64%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 4         | 0.64%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 4         | 0.64%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 4         | 0.64%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 4         | 0.64%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                 | 4         | 0.64%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 4         | 0.64%   |
| AOC 27V2G5 AOC2702 1920x1080 598x336mm 27.0-inch                      | 4         | 0.64%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 3         | 0.48%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 3         | 0.48%   |
| LG Display LCD Monitor LGD069A 1920x1080 344x194mm 15.5-inch          | 3         | 0.48%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch           | 3         | 0.48%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 3         | 0.48%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 3         | 0.48%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                    | 3         | 0.48%   |
| Dell SE2717H/HX DELD0A1 1920x1080 598x336mm 27.0-inch                 | 3         | 0.48%   |
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                     | 3         | 0.48%   |
| Dell P2414H DELA09B 1920x1080 527x297mm 23.8-inch                     | 3         | 0.48%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 3         | 0.48%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch        | 3         | 0.48%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 2         | 0.32%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 2         | 0.32%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 2         | 0.32%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 2         | 0.32%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 2         | 0.32%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 2         | 0.32%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch  | 2         | 0.32%   |
| Samsung Electronics LCD Monitor SAM0509 1920x1080                     | 2         | 0.32%   |
| Quanta Display LCD Monitor QDS002D 1400x1050 285x214mm 14.0-inch      | 2         | 0.32%   |
| Philips 190C PHLC017 1280x1024 338x270mm 17.0-inch                    | 2         | 0.32%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch           | 2         | 0.32%   |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch          | 2         | 0.32%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 2         | 0.32%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch          | 2         | 0.32%   |
| LG Display LCD Monitor LGD0390 1600x900 382x215mm 17.3-inch           | 2         | 0.32%   |
| LG Display LCD Monitor LGD0289 1600x900 382x215mm 17.3-inch           | 2         | 0.32%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch           | 2         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 275       | 48.59%  |
| 1366x768 (WXGA)    | 62        | 10.95%  |
| 3840x2160 (4K)     | 35        | 6.18%   |
| 2560x1440 (QHD)    | 32        | 5.65%   |
| 1600x900 (HD+)     | 30        | 5.3%    |
| 1680x1050 (WSXGA+) | 19        | 3.36%   |
| 1280x1024 (SXGA)   | 17        | 3%      |
| 1920x1200 (WUXGA)  | 14        | 2.47%   |
| 1440x900 (WXGA+)   | 14        | 2.47%   |
| Unknown            | 10        | 1.77%   |
| 1280x800 (WXGA)    | 9         | 1.59%   |
| 3840x1080          | 6         | 1.06%   |
| 2880x1800          | 6         | 1.06%   |
| 2560x1600          | 6         | 1.06%   |
| 2560x1080          | 4         | 0.71%   |
| 1360x768           | 4         | 0.71%   |
| 3440x1440          | 3         | 0.53%   |
| 2160x1440          | 3         | 0.53%   |
| 5760x1080          | 2         | 0.35%   |
| 3840x2400          | 2         | 0.35%   |
| 2048x1152          | 2         | 0.35%   |
| 1400x1050          | 2         | 0.35%   |
| 1024x600           | 2         | 0.35%   |
| 800x1280           | 1         | 0.18%   |
| 4480x1440          | 1         | 0.18%   |
| 3200x2000          | 1         | 0.18%   |
| 1920x1280          | 1         | 0.18%   |
| 1280x960           | 1         | 0.18%   |
| 1280x720 (HD)      | 1         | 0.18%   |
| 1024x576           | 1         | 0.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 174       | 29.1%   |
| 17      | 55        | 9.2%    |
| 27      | 52        | 8.7%    |
| 24      | 44        | 7.36%   |
| 23      | 42        | 7.02%   |
| 14      | 39        | 6.52%   |
| 13      | 37        | 6.19%   |
| 21      | 30        | 5.02%   |
| Unknown | 24        | 4.01%   |
| 22      | 11        | 1.84%   |
| 19      | 10        | 1.67%   |
| 54      | 9         | 1.51%   |
| 31      | 9         | 1.51%   |
| 20      | 9         | 1.51%   |
| 12      | 7         | 1.17%   |
| 34      | 6         | 1%      |
| 16      | 5         | 0.84%   |
| 26      | 4         | 0.67%   |
| 18      | 4         | 0.67%   |
| 84      | 3         | 0.5%    |
| 72      | 3         | 0.5%    |
| 25      | 3         | 0.5%    |
| 10      | 3         | 0.5%    |
| 49      | 2         | 0.33%   |
| 33      | 2         | 0.33%   |
| 60      | 1         | 0.17%   |
| 58      | 1         | 0.17%   |
| 52      | 1         | 0.17%   |
| 46      | 1         | 0.17%   |
| 40      | 1         | 0.17%   |
| 39      | 1         | 0.17%   |
| 38      | 1         | 0.17%   |
| 32      | 1         | 0.17%   |
| 11      | 1         | 0.17%   |
| 8       | 1         | 0.17%   |
| 7       | 1         | 0.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 237       | 40.51%  |
| 501-600     | 125       | 21.37%  |
| 401-500     | 57        | 9.74%   |
| 351-400     | 57        | 9.74%   |
| 201-300     | 31        | 5.3%    |
| Unknown     | 24        | 4.1%    |
| 601-700     | 19        | 3.25%   |
| 1001-1500   | 15        | 2.56%   |
| 701-800     | 9         | 1.54%   |
| 1501-2000   | 6         | 1.03%   |
| 801-900     | 2         | 0.34%   |
| 101-200     | 1         | 0.17%   |
| 901-1000    | 1         | 0.17%   |
| 1-100       | 1         | 0.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 391       | 75.34%  |
| 16/10   | 74        | 14.26%  |
| Unknown | 20        | 3.85%   |
| 5/4     | 15        | 2.89%   |
| 21/9    | 7         | 1.35%   |
| 3/2     | 6         | 1.16%   |
| 4/3     | 4         | 0.77%   |
| 32/9    | 1         | 0.19%   |
| 0.67    | 1         | 0.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 172       | 28.91%  |
| 201-250        | 94        | 15.8%   |
| 81-90          | 63        | 10.59%  |
| 301-350        | 56        | 9.41%   |
| 121-130        | 39        | 6.55%   |
| 151-200        | 32        | 5.38%   |
| Unknown        | 24        | 4.03%   |
| More than 1000 | 19        | 3.19%   |
| 251-300        | 19        | 3.19%   |
| 351-500        | 18        | 3.03%   |
| 141-150        | 13        | 2.18%   |
| 71-80          | 12        | 2.02%   |
| 131-140        | 7         | 1.18%   |
| 61-70          | 6         | 1.01%   |
| 111-120        | 6         | 1.01%   |
| 501-1000       | 5         | 0.84%   |
| 91-100         | 4         | 0.67%   |
| 41-50          | 3         | 0.5%    |
| 1-40           | 2         | 0.34%   |
| 51-60          | 1         | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 188       | 32.7%   |
| 51-100        | 178       | 30.96%  |
| 101-120       | 127       | 22.09%  |
| 161-240       | 28        | 4.87%   |
| Unknown       | 24        | 4.17%   |
| 1-50          | 17        | 2.96%   |
| More than 240 | 13        | 2.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 405       | 75.42%  |
| 2     | 100       | 18.62%  |
| 0     | 17        | 3.17%   |
| 3     | 13        | 2.42%   |
| 4     | 2         | 0.37%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 308       | 38.4%   |
| Intel                             | 231       | 28.8%   |
| Qualcomm Atheros                  | 87        | 10.85%  |
| Broadcom                          | 38        | 4.74%   |
| MediaTek                          | 23        | 2.87%   |
| TP-Link                           | 13        | 1.62%   |
| Broadcom Limited                  | 9         | 1.12%   |
| Ralink Technology                 | 8         | 1%      |
| Samsung Electronics               | 7         | 0.87%   |
| Ralink                            | 7         | 0.87%   |
| Qualcomm Atheros Communications   | 7         | 0.87%   |
| Marvell Technology Group          | 7         | 0.87%   |
| D-Link                            | 6         | 0.75%   |
| ASIX Electronics                  | 6         | 0.75%   |
| Xiaomi                            | 5         | 0.62%   |
| Nvidia                            | 5         | 0.62%   |
| Lenovo                            | 4         | 0.5%    |
| VIA Technologies                  | 2         | 0.25%   |
| Sundance Technology Inc / IC Plus | 2         | 0.25%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.25%   |
| Qualcomm                          | 2         | 0.25%   |
| NetGear                           | 2         | 0.25%   |
| Huawei Technologies               | 2         | 0.25%   |
| Fibocom                           | 2         | 0.25%   |
| Ericsson Business Mobile Networks | 2         | 0.25%   |
| Dell                              | 2         | 0.25%   |
| ASUSTek Computer                  | 2         | 0.25%   |
| T & A Mobile Phones               | 1         | 0.12%   |
| Nokia Mobile Phones               | 1         | 0.12%   |
| Microsoft                         | 1         | 0.12%   |
| Linksys                           | 1         | 0.12%   |
| ICS Advent                        | 1         | 0.12%   |
| HTC (High Tech Computer)          | 1         | 0.12%   |
| Hewlett-Packard                   | 1         | 0.12%   |
| Edimax Technology                 | 1         | 0.12%   |
| DisplayLink                       | 1         | 0.12%   |
| D-Link System                     | 1         | 0.12%   |
| Aquantia                          | 1         | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 225       | 24.67%  |
| Intel Wireless 8265 / 8275                                              | 25        | 2.74%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 24        | 2.63%   |
| Intel Wi-Fi 6 AX200                                                     | 24        | 2.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 22        | 2.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 18        | 1.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 16        | 1.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 12        | 1.32%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 12        | 1.32%   |
| Intel Wi-Fi 6 AX201                                                     | 12        | 1.32%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 12        | 1.32%   |
| Intel Wireless 3165                                                     | 11        | 1.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 10        | 1.1%    |
| Realtek RTL8125 2.5GbE Controller                                       | 10        | 1.1%    |
| Intel Ethernet Connection I217-LM                                       | 10        | 1.1%    |
| Intel Ethernet Connection (4) I219-V                                    | 10        | 1.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 0.99%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 9         | 0.99%   |
| Intel Wireless 7260                                                     | 8         | 0.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 8         | 0.88%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 7         | 0.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 0.77%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 0.77%   |
| Intel Wireless 7265                                                     | 7         | 0.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 0.77%   |
| Qualcomm Atheros AR9271 802.11n                                         | 6         | 0.66%   |
| Intel Wireless 3160                                                     | 6         | 0.66%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 0.66%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 6         | 0.66%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 0.66%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 5         | 0.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 0.55%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 5         | 0.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 0.55%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 5         | 0.55%   |
| Intel Ethernet Controller I225-V                                        | 5         | 0.55%   |
| Intel Ethernet Connection I217-V                                        | 5         | 0.55%   |
| Intel Ethernet Connection (7) I219-V                                    | 5         | 0.55%   |
| Intel Ethernet Connection (2) I218-V                                    | 5         | 0.55%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 185       | 43.74%  |
| Qualcomm Atheros                  | 71        | 16.78%  |
| Realtek Semiconductor             | 59        | 13.95%  |
| Broadcom                          | 26        | 6.15%   |
| MediaTek                          | 22        | 5.2%    |
| TP-Link                           | 13        | 3.07%   |
| Ralink Technology                 | 8         | 1.89%   |
| Ralink                            | 7         | 1.65%   |
| Qualcomm Atheros Communications   | 7         | 1.65%   |
| D-Link                            | 6         | 1.42%   |
| Broadcom Limited                  | 4         | 0.95%   |
| Qualcomm                          | 2         | 0.47%   |
| NetGear                           | 2         | 0.47%   |
| Fibocom                           | 2         | 0.47%   |
| Ericsson Business Mobile Networks | 2         | 0.47%   |
| Dell                              | 2         | 0.47%   |
| ASUSTek Computer                  | 2         | 0.47%   |
| Microsoft                         | 1         | 0.24%   |
| Linksys                           | 1         | 0.24%   |
| Edimax Technology                 | 1         | 0.24%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 25        | 5.88%   |
| Intel Wi-Fi 6 AX200                                                     | 24        | 5.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 22        | 5.18%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 18        | 4.24%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 16        | 3.76%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 12        | 2.82%   |
| Intel Wi-Fi 6 AX201                                                     | 12        | 2.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 12        | 2.82%   |
| Intel Wireless 3165                                                     | 11        | 2.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 10        | 2.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 2.12%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 9         | 2.12%   |
| Intel Wireless 7260                                                     | 8         | 1.88%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 7         | 1.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 1.65%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 1.65%   |
| Intel Wireless 7265                                                     | 7         | 1.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 1.65%   |
| Qualcomm Atheros AR9271 802.11n                                         | 6         | 1.41%   |
| Intel Wireless 3160                                                     | 6         | 1.41%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 1.41%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 6         | 1.41%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 1.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 1.18%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 1.18%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 5         | 1.18%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 1.18%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 4         | 0.94%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 0.94%   |
| Ralink MT7601U Wireless Adapter                                         | 4         | 0.94%   |
| Intel Wireless-AC 9260                                                  | 4         | 0.94%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.94%   |
| Intel Centrino Advanced-N 6235                                          | 4         | 0.94%   |
| TP-Link 802.11ac NIC                                                    | 3         | 0.71%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.71%   |
| Ralink RT2561/RT61 802.11g PCI                                          | 3         | 0.71%   |
| Intel WiFi Link 5100                                                    | 3         | 0.71%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 0.71%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.71%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 3         | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 278       | 58.4%   |
| Intel                             | 107       | 22.48%  |
| Qualcomm Atheros                  | 26        | 5.46%   |
| Broadcom                          | 13        | 2.73%   |
| Marvell Technology Group          | 7         | 1.47%   |
| ASIX Electronics                  | 6         | 1.26%   |
| Xiaomi                            | 5         | 1.05%   |
| Samsung Electronics               | 5         | 1.05%   |
| Nvidia                            | 5         | 1.05%   |
| Broadcom Limited                  | 5         | 1.05%   |
| Lenovo                            | 4         | 0.84%   |
| VIA Technologies                  | 2         | 0.42%   |
| Sundance Technology Inc / IC Plus | 2         | 0.42%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.42%   |
| Huawei Technologies               | 2         | 0.42%   |
| T & A Mobile Phones               | 1         | 0.21%   |
| MediaTek                          | 1         | 0.21%   |
| ICS Advent                        | 1         | 0.21%   |
| HTC (High Tech Computer)          | 1         | 0.21%   |
| DisplayLink                       | 1         | 0.21%   |
| D-Link System                     | 1         | 0.21%   |
| Aquantia                          | 1         | 0.21%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 225       | 46.78%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 24        | 4.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12        | 2.49%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10        | 2.08%   |
| Intel Ethernet Connection I217-LM                                 | 10        | 2.08%   |
| Intel Ethernet Connection (4) I219-V                              | 10        | 2.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 1.66%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 1.04%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 5         | 1.04%   |
| Intel Ethernet Controller I225-V                                  | 5         | 1.04%   |
| Intel Ethernet Connection I217-V                                  | 5         | 1.04%   |
| Intel Ethernet Connection (7) I219-V                              | 5         | 1.04%   |
| Intel Ethernet Connection (2) I218-V                              | 5         | 1.04%   |
| ASIX AX88179 Gigabit Ethernet                                     | 5         | 1.04%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4         | 0.83%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 0.83%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4         | 0.83%   |
| Intel I211 Gigabit Network Connection                             | 4         | 0.83%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 0.83%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.62%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 3         | 0.62%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.62%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.62%   |
| Intel Ethernet Connection (14) I219-V                             | 3         | 0.62%   |
| Intel Ethernet Connection (13) I219-V                             | 3         | 0.62%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 0.62%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 0.62%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2         | 0.42%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.42%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.42%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.42%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.42%   |
| Nvidia MCP61 Ethernet                                             | 2         | 0.42%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2         | 0.42%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 0.42%   |
| Lenovo USB-C Dock Ethernet                                        | 2         | 0.42%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 444       | 52.11%  |
| WiFi     | 402       | 47.18%  |
| Modem    | 5         | 0.59%   |
| Unknown  | 1         | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 331       | 61.41%  |
| Ethernet | 208       | 38.59%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 298       | 57.53%  |
| 1     | 204       | 39.38%  |
| 0     | 11        | 2.12%   |
| 4     | 3         | 0.58%   |
| 3     | 2         | 0.39%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 493       | 94.99%  |
| Yes  | 26        | 5.01%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 150       | 45.87%  |
| Realtek Semiconductor           | 37        | 11.31%  |
| Lite-On Technology              | 26        | 7.95%   |
| Qualcomm Atheros Communications | 25        | 7.65%   |
| IMC Networks                    | 21        | 6.42%   |
| Broadcom                        | 14        | 4.28%   |
| Foxconn / Hon Hai               | 13        | 3.98%   |
| Cambridge Silicon Radio         | 12        | 3.67%   |
| Apple                           | 8         | 2.45%   |
| Hewlett-Packard                 | 6         | 1.83%   |
| Toshiba                         | 3         | 0.92%   |
| Foxconn International           | 3         | 0.92%   |
| MediaTek                        | 2         | 0.61%   |
| Integrated System Solution      | 2         | 0.61%   |
| ASUSTek Computer                | 2         | 0.61%   |
| TP-Link                         | 1         | 0.31%   |
| Realtek                         | 1         | 0.31%   |
| Dell                            | 1         | 0.31%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 58        | 17.74%  |
| Intel AX201 Bluetooth                               | 30        | 9.17%   |
| Realtek Bluetooth Radio                             | 25        | 7.65%   |
| Intel AX200 Bluetooth                               | 24        | 7.34%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 15        | 4.59%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 14        | 4.28%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 12        | 3.67%   |
| Intel Wireless-AC 3168 Bluetooth                    | 11        | 3.36%   |
| Qualcomm Atheros  Bluetooth Device                  | 9         | 2.75%   |
| IMC Networks Bluetooth Radio                        | 9         | 2.75%   |
| Realtek 802.11ac WLAN Adapter                       | 8         | 2.45%   |
| IMC Networks Wireless_Device                        | 7         | 2.14%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 1.83%   |
| Intel Bluetooth Device                              | 5         | 1.53%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 1.53%   |
| Lite-On Wireless_Device                             | 4         | 1.22%   |
| Lite-On Bluetooth Device                            | 4         | 1.22%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 1.22%   |
| Broadcom BCM2045 Bluetooth                          | 4         | 1.22%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 0.92%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 0.92%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 0.92%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 0.92%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 0.92%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 0.92%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 0.92%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 3         | 0.92%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 3         | 0.92%   |
| Apple Bluetooth Host Controller                     | 3         | 0.92%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.61%   |
| MediaTek Wireless_Device                            | 2         | 0.61%   |
| IMC Networks Bluetooth Device                       | 2         | 0.61%   |
| Broadcom HP Portable Bumble Bee                     | 2         | 0.61%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 0.61%   |
| Apple Bluetooth USB Host Controller                 | 2         | 0.61%   |
| TP-Link TP-Cdj+ UB5A Adapter                        | 1         | 0.31%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.31%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)          | 1         | 0.31%   |
| Toshiba Bluetooth Device                            | 1         | 0.31%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.31%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 359       | 49.79%  |
| AMD                              | 176       | 24.41%  |
| Nvidia                           | 113       | 15.67%  |
| C-Media Electronics              | 15        | 2.08%   |
| Logitech                         | 10        | 1.39%   |
| Lenovo                           | 6         | 0.83%   |
| JMTek                            | 5         | 0.69%   |
| Creative Labs                    | 3         | 0.42%   |
| VIA Technologies                 | 2         | 0.28%   |
| Trust                            | 2         | 0.28%   |
| Silicon Integrated Systems [SiS] | 2         | 0.28%   |
| Microsoft                        | 2         | 0.28%   |
| ZOOM                             | 1         | 0.14%   |
| YZ Technology                    | 1         | 0.14%   |
| Yamaha                           | 1         | 0.14%   |
| XMOS                             | 1         | 0.14%   |
| Texas Instruments                | 1         | 0.14%   |
| Tenx Technology                  | 1         | 0.14%   |
| SteelSeries ApS                  | 1         | 0.14%   |
| Samsung Electronics              | 1         | 0.14%   |
| Samson Technologies              | 1         | 0.14%   |
| Realtek Semiconductor            | 1         | 0.14%   |
| Razer USA                        | 1         | 0.14%   |
| Plantronics                      | 1         | 0.14%   |
| Pioneer DJ                       | 1         | 0.14%   |
| Nordic Semiconductor ASA         | 1         | 0.14%   |
| Native Instruments               | 1         | 0.14%   |
| MCS                              | 1         | 0.14%   |
| M-Audio                          | 1         | 0.14%   |
| Kingston Technology              | 1         | 0.14%   |
| GN Netcom                        | 1         | 0.14%   |
| Focusrite-Novation               | 1         | 0.14%   |
| Ensoniq                          | 1         | 0.14%   |
| Cirrus Logic                     | 1         | 0.14%   |
| BEHRINGER International          | 1         | 0.14%   |
| ATI Technologies                 | 1         | 0.14%   |
| ASUSTek Computer                 | 1         | 0.14%   |
| Astro Gaming                     | 1         | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 76        | 8.74%   |
| Intel Sunrise Point-LP HD Audio                                            | 49        | 5.63%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 36        | 4.14%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 35        | 4.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 29        | 3.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 25        | 2.87%   |
| Intel Cannon Lake PCH cAVS                                                 | 24        | 2.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 23        | 2.64%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 19        | 2.18%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 18        | 2.07%   |
| Intel Haswell-ULT HD Audio Controller                                      | 18        | 2.07%   |
| Intel 8 Series HD Audio Controller                                         | 18        | 2.07%   |
| Nvidia GP107GL High Definition Audio Controller                            | 17        | 1.95%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 16        | 1.84%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 16        | 1.84%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 13        | 1.49%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 13        | 1.49%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 13        | 1.49%   |
| Nvidia GP106 High Definition Audio Controller                              | 11        | 1.26%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 11        | 1.26%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 10        | 1.15%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10        | 1.15%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 10        | 1.15%   |
| Nvidia GA106 High Definition Audio Controller                              | 9         | 1.03%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 9         | 1.03%   |
| Intel Comet Lake PCH cAVS                                                  | 9         | 1.03%   |
| Intel Broadwell-U Audio Controller                                         | 9         | 1.03%   |
| AMD Starship/Matisse HD Audio Controller                                   | 9         | 1.03%   |
| AMD FCH Azalia Controller                                                  | 9         | 1.03%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 8         | 0.92%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 8         | 0.92%   |
| Nvidia TU116 High Definition Audio Controller                              | 7         | 0.8%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 7         | 0.8%    |
| Intel 200 Series PCH HD Audio                                              | 7         | 0.8%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 7         | 0.8%    |
| Nvidia GM206 High Definition Audio Controller                              | 6         | 0.69%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 6         | 0.69%   |
| Intel Comet Lake PCH-LP cAVS                                               | 6         | 0.69%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 6         | 0.69%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 6         | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 78        | 22.67%  |
| SK hynix            | 68        | 19.77%  |
| Kingston            | 64        | 18.6%   |
| Micron Technology   | 33        | 9.59%   |
| Unknown             | 21        | 6.1%    |
| Crucial             | 21        | 6.1%    |
| Corsair             | 15        | 4.36%   |
| G.Skill             | 11        | 3.2%    |
| Ramaxel Technology  | 6         | 1.74%   |
| Patriot             | 5         | 1.45%   |
| Elpida              | 5         | 1.45%   |
| Transcend           | 4         | 1.16%   |
| A-DATA Technology   | 4         | 1.16%   |
| Kingmax             | 2         | 0.58%   |
| Unknown (ABCD)      | 1         | 0.29%   |
| Silicon Power       | 1         | 0.29%   |
| Qimonda             | 1         | 0.29%   |
| Mushkin             | 1         | 0.29%   |
| Avant               | 1         | 0.29%   |
| Apacer              | 1         | 0.29%   |
| 48spaces            | 1         | 0.29%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s         | 8         | 2.16%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 5         | 1.35%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s         | 5         | 1.35%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 4         | 1.08%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s         | 4         | 1.08%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s          | 4         | 1.08%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s       | 4         | 1.08%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 3         | 0.81%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s       | 3         | 0.81%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 3         | 0.81%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 3         | 0.81%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s         | 3         | 0.81%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s         | 3         | 0.81%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s         | 3         | 0.81%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s           | 3         | 0.81%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s         | 3         | 0.81%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s           | 2         | 0.54%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                        | 2         | 0.54%   |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s                    | 2         | 0.54%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s          | 2         | 0.54%   |
| SK hynix RAM HMT125S6TFR8C-H9 2GB SODIMM DDR3 1334MT/s        | 2         | 0.54%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s        | 2         | 0.54%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s        | 2         | 0.54%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s        | 2         | 0.54%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s    | 2         | 0.54%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                | 2         | 0.54%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s         | 2         | 0.54%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s         | 2         | 0.54%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s         | 2         | 0.54%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 2         | 0.54%   |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s  | 2         | 0.54%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s        | 2         | 0.54%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s         | 2         | 0.54%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s           | 2         | 0.54%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s  | 2         | 0.54%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.54%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s          | 2         | 0.54%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s         | 2         | 0.54%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4GB SODIMM DDR4 2133MT/s         | 2         | 0.54%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s          | 2         | 0.54%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 144       | 50.7%   |
| DDR3    | 89        | 31.34%  |
| DDR2    | 12        | 4.23%   |
| LPDDR4  | 10        | 3.52%   |
| LPDDR3  | 9         | 3.17%   |
| DDR5    | 6         | 2.11%   |
| Unknown | 6         | 2.11%   |
| SDRAM   | 5         | 1.76%   |
| LPDDR5  | 2         | 0.7%    |
| DDR     | 1         | 0.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 177       | 62.11%  |
| DIMM         | 83        | 29.12%  |
| Row Of Chips | 24        | 8.42%   |
| Chip         | 1         | 0.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 128       | 41.42%  |
| 4096  | 83        | 26.86%  |
| 16384 | 48        | 15.53%  |
| 2048  | 29        | 9.39%   |
| 32768 | 10        | 3.24%   |
| 1024  | 9         | 2.91%   |
| 512   | 2         | 0.65%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 61        | 20.13%  |
| 1600    | 61        | 20.13%  |
| 2667    | 55        | 18.15%  |
| 2400    | 16        | 5.28%   |
| 2133    | 14        | 4.62%   |
| 1333    | 14        | 4.62%   |
| 667     | 8         | 2.64%   |
| 1334    | 7         | 2.31%   |
| 3400    | 6         | 1.98%   |
| 1066    | 5         | 1.65%   |
| 800     | 5         | 1.65%   |
| 4800    | 4         | 1.32%   |
| 4267    | 4         | 1.32%   |
| 1800    | 4         | 1.32%   |
| 4266    | 3         | 0.99%   |
| 3600    | 3         | 0.99%   |
| 3266    | 3         | 0.99%   |
| 1867    | 3         | 0.99%   |
| 1067    | 3         | 0.99%   |
| 6400    | 2         | 0.66%   |
| 3866    | 2         | 0.66%   |
| 2933    | 2         | 0.66%   |
| 2800    | 2         | 0.66%   |
| 533     | 2         | 0.66%   |
| 8400    | 1         | 0.33%   |
| 5600    | 1         | 0.33%   |
| 5200    | 1         | 0.33%   |
| 4000    | 1         | 0.33%   |
| 3733    | 1         | 0.33%   |
| 3533    | 1         | 0.33%   |
| 3466    | 1         | 0.33%   |
| 3334    | 1         | 0.33%   |
| 3333    | 1         | 0.33%   |
| 3000    | 1         | 0.33%   |
| 2048    | 1         | 0.33%   |
| 975     | 1         | 0.33%   |
| 400     | 1         | 0.33%   |
| Unknown | 1         | 0.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 9         | 52.94%  |
| Canon               | 4         | 23.53%  |
| Prolific Technology | 2         | 11.76%  |
| Seiko Epson         | 1         | 5.88%   |
| Samsung Electronics | 1         | 5.88%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port   | 2         | 11.76%  |
| HP DeskJet 3630 series          | 2         | 11.76%  |
| Seiko Epson ET-2600 Series      | 1         | 5.88%   |
| Samsung Composite Device        | 1         | 5.88%   |
| HP LaserJet P1005               | 1         | 5.88%   |
| HP LaserJet M14-M17             | 1         | 5.88%   |
| HP LaserJet M101-M106           | 1         | 5.88%   |
| HP LaserJet 400 colorMFP M475dw | 1         | 5.88%   |
| HP Ink Tank Wireless 410 series | 1         | 5.88%   |
| HP DeskJet 2130 series          | 1         | 5.88%   |
| HP Deskjet 1050 J410            | 1         | 5.88%   |
| Canon PIXMA iP4300 Printer      | 1         | 5.88%   |
| Canon PIXMA iP1800 Printer      | 1         | 5.88%   |
| Canon LiDE 400                  | 1         | 5.88%   |
| Canon LBP6670 UFR II            | 1         | 5.88%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 2         | 66.67%  |
| Ultima Electronics | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Ultima Artec Ultima 2000      | 1         | 33.33%  |
| Canon CanoScan N1240U/LiDE 30 | 1         | 33.33%  |
| Canon CanoScan LiDE 220       | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 89        | 25.57%  |
| IMC Networks                           | 38        | 10.92%  |
| Quanta                                 | 36        | 10.34%  |
| Realtek Semiconductor                  | 28        | 8.05%   |
| Microdia                               | 20        | 5.75%   |
| Bison Electronics                      | 20        | 5.75%   |
| Logitech                               | 19        | 5.46%   |
| Sunplus Innovation Technology          | 16        | 4.6%    |
| Suyin                                  | 13        | 3.74%   |
| Syntek                                 | 12        | 3.45%   |
| Lite-On Technology                     | 9         | 2.59%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 2.01%   |
| Apple                                  | 6         | 1.72%   |
| Luxvisions Innotech Limited            | 5         | 1.44%   |
| Sonix Technology                       | 3         | 0.86%   |
| Anker                                  | 3         | 0.86%   |
| Acer                                   | 3         | 0.86%   |
| SunplusIT                              | 2         | 0.57%   |
| Silicon Motion                         | 2         | 0.57%   |
| Primax Electronics                     | 2         | 0.57%   |
| Jieli Technology                       | 2         | 0.57%   |
| Genesys Logic                          | 2         | 0.57%   |
| Z-Star Microelectronics                | 1         | 0.29%   |
| Xiaomi                                 | 1         | 0.29%   |
| Trust                                  | 1         | 0.29%   |
| Samsung Electronics                    | 1         | 0.29%   |
| Ricoh                                  | 1         | 0.29%   |
| Goertek Electronics                    | 1         | 0.29%   |
| GenesysLogic Technology                | 1         | 0.29%   |
| DQYGF0A9IHU4ID                         | 1         | 0.29%   |
| Cubeternet                             | 1         | 0.29%   |
| AVerMedia Technologies                 | 1         | 0.29%   |
| Alcor Micro                            | 1         | 0.29%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 16        | 4.58%   |
| Chicony HD WebCam                        | 15        | 4.3%    |
| IMC Networks Integrated Camera           | 13        | 3.72%   |
| IMC Networks USB2.0 HD UVC WebCam        | 10        | 2.87%   |
| Quanta VGA WebCam                        | 9         | 2.58%   |
| Microdia Integrated_Webcam_HD            | 9         | 2.58%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 9         | 2.58%   |
| Syntek Integrated Camera                 | 8         | 2.29%   |
| Quanta HD User Facing                    | 7         | 2.01%   |
| Realtek Integrated_Webcam_HD             | 6         | 1.72%   |
| Logitech Webcam C270                     | 6         | 1.72%   |
| Bison Integrated Camera                  | 6         | 1.72%   |
| Quanta HP HD Camera                      | 5         | 1.43%   |
| Quanta HD Webcam                         | 5         | 1.43%   |
| Lite-On HP HD Camera                     | 5         | 1.43%   |
| Bison Lenovo EasyCamera                  | 5         | 1.43%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 4         | 1.15%   |
| Quanta HP TrueVision HD Camera           | 4         | 1.15%   |
| Chicony HP Webcam                        | 4         | 1.15%   |
| Chicony HP HD Camera                     | 4         | 1.15%   |
| Apple FaceTime HD Camera (Built-in)      | 4         | 1.15%   |
| Suyin WebCam                             | 3         | 0.86%   |
| Sunplus HD 720P webcam                   | 3         | 0.86%   |
| Sunplus Asus Webcam                      | 3         | 0.86%   |
| Realtek Lenovo EasyCamera                | 3         | 0.86%   |
| Realtek Integrated Webcam                | 3         | 0.86%   |
| Lite-On Integrated Camera                | 3         | 0.86%   |
| Chicony USB2.0 VGA UVC WebCam            | 3         | 0.86%   |
| Chicony USB2.0 HD UVC WebCam             | 3         | 0.86%   |
| Chicony Integrated HP HD Webcam          | 3         | 0.86%   |
| Chicony HP Wide Vision HD Camera         | 3         | 0.86%   |
| Chicony HP Wide Vision HD                | 3         | 0.86%   |
| Chicony HD User Facing                   | 3         | 0.86%   |
| Anker PowerConf C300                     | 3         | 0.86%   |
| Suyin HP TrueVision HD Integrated Webcam | 2         | 0.57%   |
| SunplusIT MTD camera                     | 2         | 0.57%   |
| Sunplus Integrated_Webcam_HD             | 2         | 0.57%   |
| Sunplus HD WebCam                        | 2         | 0.57%   |
| Sonix USB2.0 FHD UVC WebCam              | 2         | 0.57%   |
| Realtek USB Camera                       | 2         | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 29        | 37.18%  |
| Validity Sensors           | 16        | 20.51%  |
| Shenzhen Goodix Technology | 12        | 15.38%  |
| AuthenTec                  | 6         | 7.69%   |
| LighTuning Technology      | 5         | 6.41%   |
| Elan Microelectronics      | 5         | 6.41%   |
| Upek                       | 4         | 5.13%   |
| STMicroelectronics         | 1         | 1.28%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 8         | 10.26%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 8.97%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 6.41%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 5         | 6.41%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 6.41%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 5.13%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 5.13%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 5.13%   |
| Elan ELAN:Fingerprint                                                      | 4         | 5.13%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 3.85%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 3.85%   |
| AuthenTec AES2810                                                          | 3         | 3.85%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 3.85%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 2.56%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 2.56%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 2.56%   |
| Synaptics WBDI                                                             | 2         | 2.56%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 2.56%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.28%   |
| Validity Sensors VFS491                                                    | 1         | 1.28%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 1.28%   |
| Synaptics UWP WBDI                                                         | 1         | 1.28%   |
| Synaptics TouchPad                                                         | 1         | 1.28%   |
| Synaptics  WBDI                                                            | 1         | 1.28%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 1.28%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.28%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.28%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 1         | 1.28%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Alcor Micro                | 8         | 40%     |
| Broadcom                   | 5         | 25%     |
| Lenovo                     | 3         | 15%     |
| Upek                       | 1         | 5%      |
| Realtek Semiconductor      | 1         | 5%      |
| Gemalto (was Gemplus)      | 1         | 5%      |
| Athena Smartcard Solutions | 1         | 5%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 8         | 40%     |
| Lenovo Integrated Smart Card Reader                        | 3         | 15%     |
| Broadcom 58200                                             | 3         | 15%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 5%      |
| Realtek Semiconductor Smart Card Reader Interface          | 1         | 5%      |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader          | 1         | 5%      |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 5%      |
| Broadcom 5880                                              | 1         | 5%      |
| Athena Smartcard Solutions ASEDrive CCID                   | 1         | 5%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 366       | 68.54%  |
| 1     | 131       | 24.53%  |
| 2     | 33        | 6.18%   |
| 3     | 4         | 0.75%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 77        | 38.12%  |
| Graphics card            | 43        | 21.29%  |
| Net/wireless             | 22        | 10.89%  |
| Chipcard                 | 18        | 8.91%   |
| Multimedia controller    | 14        | 6.93%   |
| Camera                   | 6         | 2.97%   |
| Communication controller | 5         | 2.48%   |
| Unassigned class         | 3         | 1.49%   |
| Card reader              | 3         | 1.49%   |
| Bluetooth                | 3         | 1.49%   |
| Storage                  | 2         | 0.99%   |
| Storage/raid             | 1         | 0.5%    |
| Storage/ide              | 1         | 0.5%    |
| Sound                    | 1         | 0.5%    |
| Net/ethernet             | 1         | 0.5%    |
| Modem                    | 1         | 0.5%    |
| Flash memory             | 1         | 0.5%    |


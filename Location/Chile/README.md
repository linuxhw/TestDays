Linux in Chile - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Linux in Chile.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Chile/Desktop/README.md) and [notebooks](/Location/Chile/Notebook/README.md).

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

Total: 1229

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [4191279e7e](https://linux-hardware.org/?probe=4191279e7e) | Apr 01, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [27fbf62ba0](https://linux-hardware.org/?probe=27fbf62ba0) | Apr 01, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [5b087b11f5](https://linux-hardware.org/?probe=5b087b11f5) | Mar 30, 2023 |
| HP            | 8433 11                     | Desktop     | [55f7473ba8](https://linux-hardware.org/?probe=55f7473ba8) | Mar 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [e9600e8bfe](https://linux-hardware.org/?probe=e9600e8bfe) | Mar 29, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [f7222bf293](https://linux-hardware.org/?probe=f7222bf293) | Mar 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [a438a0c994](https://linux-hardware.org/?probe=a438a0c994) | Mar 27, 2023 |
| Acer          | Swift SF113-31              | Notebook    | [698b73783e](https://linux-hardware.org/?probe=698b73783e) | Mar 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E203... | Notebook    | [036c2c771c](https://linux-hardware.org/?probe=036c2c771c) | Mar 23, 2023 |
| MSI           | Z270 GAMING M3              | Desktop     | [2c25601c7c](https://linux-hardware.org/?probe=2c25601c7c) | Mar 22, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [4cbcbc3025](https://linux-hardware.org/?probe=4cbcbc3025) | Mar 22, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [d08f174747](https://linux-hardware.org/?probe=d08f174747) | Mar 20, 2023 |
| Dell          | G3 3590                     | Notebook    | [cba689e7f5](https://linux-hardware.org/?probe=cba689e7f5) | Mar 20, 2023 |
| HP            | 18E7                        | Desktop     | [9e4b5010d8](https://linux-hardware.org/?probe=9e4b5010d8) | Mar 20, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [23c1be0005](https://linux-hardware.org/?probe=23c1be0005) | Mar 19, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [9439371137](https://linux-hardware.org/?probe=9439371137) | Mar 18, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [c968526666](https://linux-hardware.org/?probe=c968526666) | Mar 18, 2023 |
| MSI           | MS-7360                     | Desktop     | [6c8cb5d98f](https://linux-hardware.org/?probe=6c8cb5d98f) | Mar 18, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [8a802fa8fe](https://linux-hardware.org/?probe=8a802fa8fe) | Mar 16, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [679da48c41](https://linux-hardware.org/?probe=679da48c41) | Mar 16, 2023 |
| Lenovo        | IdeaPad S540-15IWL 81NE     | Notebook    | [11b2e17886](https://linux-hardware.org/?probe=11b2e17886) | Mar 13, 2023 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [088b681bdd](https://linux-hardware.org/?probe=088b681bdd) | Mar 13, 2023 |
| Toshiba       | Satellite L515              | Notebook    | [11116a9517](https://linux-hardware.org/?probe=11116a9517) | Mar 13, 2023 |
| Gear          | Geranium                    | Notebook    | [8567411d91](https://linux-hardware.org/?probe=8567411d91) | Mar 13, 2023 |
| Gear          | Geranium                    | Notebook    | [1303244018](https://linux-hardware.org/?probe=1303244018) | Mar 13, 2023 |
| Toshiba       | Satellite L515              | Notebook    | [f2ffca7459](https://linux-hardware.org/?probe=f2ffca7459) | Mar 12, 2023 |
| ASUSTek       | K501UW                      | Notebook    | [322b5bf476](https://linux-hardware.org/?probe=322b5bf476) | Mar 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [87779bfdea](https://linux-hardware.org/?probe=87779bfdea) | Mar 11, 2023 |
| MSI           | X58 PLATINUM SLI            | Desktop     | [c8875fb17f](https://linux-hardware.org/?probe=c8875fb17f) | Mar 08, 2023 |
| ASUSTek       | K501UW                      | Notebook    | [9a61fd62b3](https://linux-hardware.org/?probe=9a61fd62b3) | Mar 05, 2023 |
| HP            | 339A                        | Desktop     | [a2af229dad](https://linux-hardware.org/?probe=a2af229dad) | Mar 05, 2023 |
| Dell          | Latitude 5410               | Notebook    | [6f55e8bbfe](https://linux-hardware.org/?probe=6f55e8bbfe) | Mar 05, 2023 |
| Toshiba       | Satellite L515              | Notebook    | [daf95cc1e5](https://linux-hardware.org/?probe=daf95cc1e5) | Mar 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [76645fa513](https://linux-hardware.org/?probe=76645fa513) | Feb 28, 2023 |
| HP            | 240 G4 Notebook PC          | Notebook    | [02744836e7](https://linux-hardware.org/?probe=02744836e7) | Feb 28, 2023 |
| Dell          | G3 3590                     | Notebook    | [eb9009fad9](https://linux-hardware.org/?probe=eb9009fad9) | Feb 27, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [b4485b65b3](https://linux-hardware.org/?probe=b4485b65b3) | Feb 27, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [a52e16df32](https://linux-hardware.org/?probe=a52e16df32) | Feb 27, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [6b712e555f](https://linux-hardware.org/?probe=6b712e555f) | Feb 26, 2023 |
| Dell          | System XPS L321X            | Notebook    | [4de5ba1c80](https://linux-hardware.org/?probe=4de5ba1c80) | Feb 25, 2023 |
| HP            | ProBook 4730s               | Notebook    | [6d563800a1](https://linux-hardware.org/?probe=6d563800a1) | Feb 24, 2023 |
| Toshiba       | Satellite L515              | Notebook    | [969c2042b9](https://linux-hardware.org/?probe=969c2042b9) | Feb 24, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [f0cb288b9f](https://linux-hardware.org/?probe=f0cb288b9f) | Feb 23, 2023 |
| HP            | 15                          | Notebook    | [470b07302a](https://linux-hardware.org/?probe=470b07302a) | Feb 22, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [63636ce164](https://linux-hardware.org/?probe=63636ce164) | Feb 22, 2023 |
| Samsung       | R430/P430                   | Notebook    | [3bbea19ca4](https://linux-hardware.org/?probe=3bbea19ca4) | Feb 21, 2023 |
| HP            | Pavilion x360 14 G1         | Convertible | [77d9445484](https://linux-hardware.org/?probe=77d9445484) | Feb 20, 2023 |
| ASUSTek       | Zenbook UM5401QA_UM5401Q... | Notebook    | [51a7f0e66d](https://linux-hardware.org/?probe=51a7f0e66d) | Feb 19, 2023 |
| HP            | 15                          | Notebook    | [60ecad0be7](https://linux-hardware.org/?probe=60ecad0be7) | Feb 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [764c7eaffe](https://linux-hardware.org/?probe=764c7eaffe) | Feb 17, 2023 |
| ASUSTek       | K501UW                      | Notebook    | [6d64083839](https://linux-hardware.org/?probe=6d64083839) | Feb 17, 2023 |
| ASUSTek       | K501UW                      | Notebook    | [7857666504](https://linux-hardware.org/?probe=7857666504) | Feb 16, 2023 |
| Dell          | Precision 7560              | Notebook    | [7ed10eebe9](https://linux-hardware.org/?probe=7ed10eebe9) | Feb 16, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [e78a97227a](https://linux-hardware.org/?probe=e78a97227a) | Feb 15, 2023 |
| ASUSTek       | K501UW                      | Notebook    | [45e719d7c0](https://linux-hardware.org/?probe=45e719d7c0) | Feb 15, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [247ab26b54](https://linux-hardware.org/?probe=247ab26b54) | Feb 14, 2023 |
| HP            | 14                          | Notebook    | [38554cf215](https://linux-hardware.org/?probe=38554cf215) | Feb 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [c3f554a4bf](https://linux-hardware.org/?probe=c3f554a4bf) | Feb 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [4ba93ea14d](https://linux-hardware.org/?probe=4ba93ea14d) | Feb 14, 2023 |
| MSI           | B85-G43 GAMING              | Desktop     | [b2b66e40e1](https://linux-hardware.org/?probe=b2b66e40e1) | Feb 14, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [89f1272cd8](https://linux-hardware.org/?probe=89f1272cd8) | Feb 13, 2023 |
| HP            | 14                          | Notebook    | [610e26434d](https://linux-hardware.org/?probe=610e26434d) | Feb 12, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [a326374047](https://linux-hardware.org/?probe=a326374047) | Feb 12, 2023 |
| HP            | 1850                        | Desktop     | [54f5b16151](https://linux-hardware.org/?probe=54f5b16151) | Feb 11, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [552d730c6d](https://linux-hardware.org/?probe=552d730c6d) | Feb 09, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [3fce6d5f05](https://linux-hardware.org/?probe=3fce6d5f05) | Feb 07, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [209a38d937](https://linux-hardware.org/?probe=209a38d937) | Feb 07, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [1867884ede](https://linux-hardware.org/?probe=1867884ede) | Feb 06, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [104a086d29](https://linux-hardware.org/?probe=104a086d29) | Feb 05, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [578b166faa](https://linux-hardware.org/?probe=578b166faa) | Feb 05, 2023 |
| HP            | Presario CQ43               | Notebook    | [76bfeffd5f](https://linux-hardware.org/?probe=76bfeffd5f) | Feb 02, 2023 |
| Dell          | 06D7TR A02                  | Desktop     | [b3bb51473f](https://linux-hardware.org/?probe=b3bb51473f) | Feb 01, 2023 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | Desktop     | [2c021665e1](https://linux-hardware.org/?probe=2c021665e1) | Jan 31, 2023 |
| MACHINIST     | X99Z V102 IENGINEER         | Desktop     | [d2cfaf56df](https://linux-hardware.org/?probe=d2cfaf56df) | Jan 31, 2023 |
| ViewSonic     | VOT132                      | Desktop     | [a8ecfadd53](https://linux-hardware.org/?probe=a8ecfadd53) | Jan 30, 2023 |
| HP            | Convertible x360 11-ab0X... | Convertible | [c56cc33809](https://linux-hardware.org/?probe=c56cc33809) | Jan 29, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [8a5423443a](https://linux-hardware.org/?probe=8a5423443a) | Jan 28, 2023 |
| Lenovo        | V14 G1 IML 82NA             | Notebook    | [c346600bdc](https://linux-hardware.org/?probe=c346600bdc) | Jan 25, 2023 |
| Dell          | 06D7TR A02                  | Desktop     | [cd487a22cd](https://linux-hardware.org/?probe=cd487a22cd) | Jan 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [30b373aafe](https://linux-hardware.org/?probe=30b373aafe) | Jan 25, 2023 |
| HP            | 2ADE                        | Desktop     | [b927cb3f98](https://linux-hardware.org/?probe=b927cb3f98) | Jan 24, 2023 |
| Google        | Treeya                      | Notebook    | [27a381272a](https://linux-hardware.org/?probe=27a381272a) | Jan 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a715541f02](https://linux-hardware.org/?probe=a715541f02) | Jan 24, 2023 |
| ASUSTek       | F2A55-M LK2                 | Desktop     | [93db1bee75](https://linux-hardware.org/?probe=93db1bee75) | Jan 23, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [f872a64ba1](https://linux-hardware.org/?probe=f872a64ba1) | Jan 20, 2023 |
| MSI           | H81M-E33                    | Desktop     | [ddb1be1cc6](https://linux-hardware.org/?probe=ddb1be1cc6) | Jan 18, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [a9cad4d873](https://linux-hardware.org/?probe=a9cad4d873) | Jan 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c2c13271fd](https://linux-hardware.org/?probe=c2c13271fd) | Jan 17, 2023 |
| HP            | ProBook 655 G1              | Notebook    | [e5f3b2835d](https://linux-hardware.org/?probe=e5f3b2835d) | Jan 16, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | Notebook    | [47d090108d](https://linux-hardware.org/?probe=47d090108d) | Jan 16, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | Notebook    | [219091b4e0](https://linux-hardware.org/?probe=219091b4e0) | Jan 15, 2023 |
| HC            | HCAR357-MI V1.0             | Desktop     | [b5f80f8eac](https://linux-hardware.org/?probe=b5f80f8eac) | Jan 14, 2023 |
| ASUSTek       | Q325UA                      | Convertible | [1862534df3](https://linux-hardware.org/?probe=1862534df3) | Jan 13, 2023 |
| Acer          | Aspire 2920                 | Notebook    | [0766ea34c6](https://linux-hardware.org/?probe=0766ea34c6) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [1a68bed616](https://linux-hardware.org/?probe=1a68bed616) | Jan 12, 2023 |
| HP            | 83F2                        | Desktop     | [7482186165](https://linux-hardware.org/?probe=7482186165) | Jan 11, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2455d11a72](https://linux-hardware.org/?probe=2455d11a72) | Jan 11, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [247bb9fe04](https://linux-hardware.org/?probe=247bb9fe04) | Jan 10, 2023 |
| HP            | ProBook 655 G1              | Notebook    | [f61b79535e](https://linux-hardware.org/?probe=f61b79535e) | Jan 10, 2023 |
| Acer          | Aspire A315-41              | Notebook    | [6c7f37297d](https://linux-hardware.org/?probe=6c7f37297d) | Jan 09, 2023 |
| HP            | ProBook 655 G1              | Notebook    | [91948448b6](https://linux-hardware.org/?probe=91948448b6) | Jan 09, 2023 |
| Acer          | Aspire A314-22              | Notebook    | [5729420a54](https://linux-hardware.org/?probe=5729420a54) | Jan 09, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [2923dcfe6f](https://linux-hardware.org/?probe=2923dcfe6f) | Jan 09, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [b345c4d626](https://linux-hardware.org/?probe=b345c4d626) | Jan 06, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [3a3164f63f](https://linux-hardware.org/?probe=3a3164f63f) | Jan 04, 2023 |
| HP            | EliteBook 8740w (WH274UT... | Notebook    | [e42d4e66a0](https://linux-hardware.org/?probe=e42d4e66a0) | Dec 31, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [68b3b51892](https://linux-hardware.org/?probe=68b3b51892) | Dec 30, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [fdb827eff9](https://linux-hardware.org/?probe=fdb827eff9) | Dec 29, 2022 |
| HP            | 240 G6 Notebook PC          | Notebook    | [b593030fef](https://linux-hardware.org/?probe=b593030fef) | Dec 28, 2022 |
| HP            | 240 G6 Notebook PC          | Notebook    | [27e4ff648f](https://linux-hardware.org/?probe=27e4ff648f) | Dec 28, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [321cc72064](https://linux-hardware.org/?probe=321cc72064) | Dec 27, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [06d788f40a](https://linux-hardware.org/?probe=06d788f40a) | Dec 27, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [6de981f1fc](https://linux-hardware.org/?probe=6de981f1fc) | Dec 24, 2022 |
| HP            | Pavilion dv7                | Notebook    | [5e5eb2c983](https://linux-hardware.org/?probe=5e5eb2c983) | Dec 22, 2022 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [1397ed80b3](https://linux-hardware.org/?probe=1397ed80b3) | Dec 21, 2022 |
| HP            | 2B54 100                    | All in one  | [b47807a201](https://linux-hardware.org/?probe=b47807a201) | Dec 16, 2022 |
| HP            | 14                          | Notebook    | [4794938b36](https://linux-hardware.org/?probe=4794938b36) | Dec 14, 2022 |
| Dell          | Inspiron 7380               | Notebook    | [29d4feb456](https://linux-hardware.org/?probe=29d4feb456) | Dec 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [d41bef1f84](https://linux-hardware.org/?probe=d41bef1f84) | Dec 09, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [4fd43d5aff](https://linux-hardware.org/?probe=4fd43d5aff) | Dec 09, 2022 |
| Acer          | Aspire A515-52              | Notebook    | [99e671f55f](https://linux-hardware.org/?probe=99e671f55f) | Dec 09, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [13e9fa6c58](https://linux-hardware.org/?probe=13e9fa6c58) | Dec 09, 2022 |
| Dell          | Inspiron 5459               | Notebook    | [9b714617c8](https://linux-hardware.org/?probe=9b714617c8) | Dec 04, 2022 |
| HP            | 14                          | Notebook    | [868daee488](https://linux-hardware.org/?probe=868daee488) | Dec 03, 2022 |
| ASUSTek       | K501UW                      | Notebook    | [1571941805](https://linux-hardware.org/?probe=1571941805) | Dec 03, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | Notebook    | [aa9ad07031](https://linux-hardware.org/?probe=aa9ad07031) | Dec 01, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [703ef1c899](https://linux-hardware.org/?probe=703ef1c899) | Nov 30, 2022 |
| Chuwi         | CoreBook X                  | Notebook    | [f6745ce587](https://linux-hardware.org/?probe=f6745ce587) | Nov 29, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [1e52ea39e4](https://linux-hardware.org/?probe=1e52ea39e4) | Nov 28, 2022 |
| Chuwi         | CoreBook X                  | Notebook    | [810ed5914a](https://linux-hardware.org/?probe=810ed5914a) | Nov 28, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [e479f87a66](https://linux-hardware.org/?probe=e479f87a66) | Nov 28, 2022 |
| Toshiba       | TECRA M11                   | Notebook    | [509dfbf1a4](https://linux-hardware.org/?probe=509dfbf1a4) | Nov 27, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [3413fb7947](https://linux-hardware.org/?probe=3413fb7947) | Nov 26, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [68e1087fde](https://linux-hardware.org/?probe=68e1087fde) | Nov 25, 2022 |
| Alienware     | M17xR3                      | Notebook    | [438f3639aa](https://linux-hardware.org/?probe=438f3639aa) | Nov 24, 2022 |
| HP            | 8309                        | Desktop     | [8329dc7b8d](https://linux-hardware.org/?probe=8329dc7b8d) | Nov 23, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [0627894c6b](https://linux-hardware.org/?probe=0627894c6b) | Nov 18, 2022 |
| Lenovo        | IdeaPad 1 14IAU7 82QC       | Notebook    | [12073cb314](https://linux-hardware.org/?probe=12073cb314) | Nov 16, 2022 |
| Sony          | SVE1411EGXB                 | Notebook    | [dafea482eb](https://linux-hardware.org/?probe=dafea482eb) | Nov 14, 2022 |
| HP            | Pavilion g4                 | Notebook    | [44162d8878](https://linux-hardware.org/?probe=44162d8878) | Nov 11, 2022 |
| HP            | ENVY 17 Leap Motion SE N... | Notebook    | [ae40e6e5b3](https://linux-hardware.org/?probe=ae40e6e5b3) | Nov 10, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [c3aaf6eed2](https://linux-hardware.org/?probe=c3aaf6eed2) | Nov 09, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [7f498c5723](https://linux-hardware.org/?probe=7f498c5723) | Nov 08, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [3d53644c05](https://linux-hardware.org/?probe=3d53644c05) | Nov 08, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [5030ff83c2](https://linux-hardware.org/?probe=5030ff83c2) | Nov 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [44e88f2879](https://linux-hardware.org/?probe=44e88f2879) | Nov 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [61756efe8c](https://linux-hardware.org/?probe=61756efe8c) | Nov 07, 2022 |
| ASRock        | H310CM-HDV                  | Desktop     | [cb1cecc5e1](https://linux-hardware.org/?probe=cb1cecc5e1) | Nov 05, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [ece385acfe](https://linux-hardware.org/?probe=ece385acfe) | Nov 05, 2022 |
| HP            | ProBook 440 G7              | Notebook    | [7a183bdeb7](https://linux-hardware.org/?probe=7a183bdeb7) | Nov 05, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [f078009dc8](https://linux-hardware.org/?probe=f078009dc8) | Nov 05, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [af85812864](https://linux-hardware.org/?probe=af85812864) | Nov 04, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [3bd662e577](https://linux-hardware.org/?probe=3bd662e577) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [4a158afdfd](https://linux-hardware.org/?probe=4a158afdfd) | Nov 02, 2022 |
| Sony          | VAIO                        | All in one  | [cefad415d0](https://linux-hardware.org/?probe=cefad415d0) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [325516bbce](https://linux-hardware.org/?probe=325516bbce) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [740d19ba42](https://linux-hardware.org/?probe=740d19ba42) | Oct 31, 2022 |
| Pegatron      | IPPCR-SS                    | Desktop     | [9427da0212](https://linux-hardware.org/?probe=9427da0212) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [424aaaf5bd](https://linux-hardware.org/?probe=424aaaf5bd) | Oct 30, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [c6a7aeb8ad](https://linux-hardware.org/?probe=c6a7aeb8ad) | Oct 30, 2022 |
| Toshiba       | TECRA M11                   | Notebook    | [15690a2198](https://linux-hardware.org/?probe=15690a2198) | Oct 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [293877c614](https://linux-hardware.org/?probe=293877c614) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d7491bf8e7](https://linux-hardware.org/?probe=d7491bf8e7) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [6bdf703faf](https://linux-hardware.org/?probe=6bdf703faf) | Oct 29, 2022 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [2e4c04ada0](https://linux-hardware.org/?probe=2e4c04ada0) | Oct 27, 2022 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [cb31f9ab8b](https://linux-hardware.org/?probe=cb31f9ab8b) | Oct 26, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [3d3ac2530c](https://linux-hardware.org/?probe=3d3ac2530c) | Oct 25, 2022 |
| Acer          | Aspire ES1-111M             | Notebook    | [ebff9e2fa5](https://linux-hardware.org/?probe=ebff9e2fa5) | Oct 25, 2022 |
| HP            | 225E                        | Desktop     | [7e246d254b](https://linux-hardware.org/?probe=7e246d254b) | Oct 24, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [b6b5c1468c](https://linux-hardware.org/?probe=b6b5c1468c) | Oct 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [7cafd024ea](https://linux-hardware.org/?probe=7cafd024ea) | Oct 22, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [9f16b5a7e2](https://linux-hardware.org/?probe=9f16b5a7e2) | Oct 22, 2022 |
| Google        | Treeya                      | Notebook    | [1a93d190b0](https://linux-hardware.org/?probe=1a93d190b0) | Oct 21, 2022 |
| Lenovo        | ThinkPad T470 20JNS01R01    | Notebook    | [abb8194196](https://linux-hardware.org/?probe=abb8194196) | Oct 21, 2022 |
| Samsung       | R430/P430/R480              | Notebook    | [a2db8aeade](https://linux-hardware.org/?probe=a2db8aeade) | Oct 19, 2022 |
| Samsung       | R430/P430/R480              | Notebook    | [92957e0afc](https://linux-hardware.org/?probe=92957e0afc) | Oct 19, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [cb63aa5619](https://linux-hardware.org/?probe=cb63aa5619) | Oct 17, 2022 |
| Samsung       | R430/P430/R480              | Notebook    | [c2f91318fe](https://linux-hardware.org/?probe=c2f91318fe) | Oct 17, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [e515cd0e66](https://linux-hardware.org/?probe=e515cd0e66) | Oct 15, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [3028d439cf](https://linux-hardware.org/?probe=3028d439cf) | Oct 14, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [2b3c91d2b0](https://linux-hardware.org/?probe=2b3c91d2b0) | Oct 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [318b3ef82b](https://linux-hardware.org/?probe=318b3ef82b) | Oct 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [17feafd680](https://linux-hardware.org/?probe=17feafd680) | Oct 12, 2022 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [e3dcca8113](https://linux-hardware.org/?probe=e3dcca8113) | Oct 11, 2022 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [593d28a4cf](https://linux-hardware.org/?probe=593d28a4cf) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [04e29685a6](https://linux-hardware.org/?probe=04e29685a6) | Oct 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [2a8fd02f04](https://linux-hardware.org/?probe=2a8fd02f04) | Oct 07, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [5e60e8faae](https://linux-hardware.org/?probe=5e60e8faae) | Oct 04, 2022 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [a7764ad0f6](https://linux-hardware.org/?probe=a7764ad0f6) | Oct 03, 2022 |
| Toshiba       | TECRA M11                   | Notebook    | [6680cedc5e](https://linux-hardware.org/?probe=6680cedc5e) | Oct 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [55f843ecf6](https://linux-hardware.org/?probe=55f843ecf6) | Oct 02, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3bbd57ceea](https://linux-hardware.org/?probe=3bbd57ceea) | Oct 02, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [5283dee456](https://linux-hardware.org/?probe=5283dee456) | Oct 02, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [9a2de7b77f](https://linux-hardware.org/?probe=9a2de7b77f) | Oct 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [32dba0444e](https://linux-hardware.org/?probe=32dba0444e) | Oct 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [46d6046fce](https://linux-hardware.org/?probe=46d6046fce) | Oct 02, 2022 |
| Toshiba       | Satellite L45               | Notebook    | [79ff097329](https://linux-hardware.org/?probe=79ff097329) | Oct 02, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [4684b672f6](https://linux-hardware.org/?probe=4684b672f6) | Sep 30, 2022 |
| SK hynix      | HyBook                      | Notebook    | [38b5f704a1](https://linux-hardware.org/?probe=38b5f704a1) | Sep 30, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [ce2d41ee99](https://linux-hardware.org/?probe=ce2d41ee99) | Sep 30, 2022 |
| Samsung       | R430/P430/R480              | Notebook    | [09795617ab](https://linux-hardware.org/?probe=09795617ab) | Sep 30, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [1570daf698](https://linux-hardware.org/?probe=1570daf698) | Sep 29, 2022 |
| AMI           | Cherry Trail CR             | Notebook    | [58caf99a77](https://linux-hardware.org/?probe=58caf99a77) | Sep 29, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [bd2dea6653](https://linux-hardware.org/?probe=bd2dea6653) | Sep 29, 2022 |
| AMI           | Cherry Trail CR             | Notebook    | [2d55b9b35e](https://linux-hardware.org/?probe=2d55b9b35e) | Sep 28, 2022 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [cf179c716e](https://linux-hardware.org/?probe=cf179c716e) | Sep 27, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [01cf3c6f99](https://linux-hardware.org/?probe=01cf3c6f99) | Sep 26, 2022 |
| HP            | Pavilion 15                 | Notebook    | [32670a0451](https://linux-hardware.org/?probe=32670a0451) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d72e6b3865](https://linux-hardware.org/?probe=d72e6b3865) | Sep 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [7dc3fbcf76](https://linux-hardware.org/?probe=7dc3fbcf76) | Sep 21, 2022 |
| Dell          | Latitude 7490               | Notebook    | [b8c3a5519a](https://linux-hardware.org/?probe=b8c3a5519a) | Sep 21, 2022 |
| Sony          | VAIO                        | All in one  | [0e3271f88f](https://linux-hardware.org/?probe=0e3271f88f) | Sep 19, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [f6ccaeed5e](https://linux-hardware.org/?probe=f6ccaeed5e) | Sep 16, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [277daa8d6d](https://linux-hardware.org/?probe=277daa8d6d) | Sep 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [2ac6776181](https://linux-hardware.org/?probe=2ac6776181) | Sep 13, 2022 |
| Intel         | NUC8BEB J72693-309          | Mini pc     | [7ec64e9e08](https://linux-hardware.org/?probe=7ec64e9e08) | Sep 13, 2022 |
| Dell          | 060K5C A00                  | Desktop     | [a64a44387b](https://linux-hardware.org/?probe=a64a44387b) | Sep 13, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [6847632df3](https://linux-hardware.org/?probe=6847632df3) | Sep 12, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [6f309073f2](https://linux-hardware.org/?probe=6f309073f2) | Sep 11, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [820c1e2ac6](https://linux-hardware.org/?probe=820c1e2ac6) | Sep 11, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [f19e04efc1](https://linux-hardware.org/?probe=f19e04efc1) | Sep 10, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [b11b5bcba5](https://linux-hardware.org/?probe=b11b5bcba5) | Sep 09, 2022 |
| Lenovo        | 14w 81MQ00AVCL              | Notebook    | [c1a16c7963](https://linux-hardware.org/?probe=c1a16c7963) | Sep 06, 2022 |
| Lenovo        | 14w 81MQ00AVCL              | Notebook    | [2ae4968612](https://linux-hardware.org/?probe=2ae4968612) | Sep 06, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2176e4d70f](https://linux-hardware.org/?probe=2176e4d70f) | Sep 05, 2022 |
| ECS           | H61H-G11/7.0                | Desktop     | [790b93cbee](https://linux-hardware.org/?probe=790b93cbee) | Sep 03, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [f1198508de](https://linux-hardware.org/?probe=f1198508de) | Sep 03, 2022 |
| Lenovo        | ThinkPad T480 20L6S80G00    | Notebook    | [bd599c876c](https://linux-hardware.org/?probe=bd599c876c) | Sep 02, 2022 |
| MSI           | H81M-E33                    | Desktop     | [ec88b5b492](https://linux-hardware.org/?probe=ec88b5b492) | Sep 02, 2022 |
| ASRock        | X99 Taichi                  | Desktop     | [4cd4bf6c89](https://linux-hardware.org/?probe=4cd4bf6c89) | Sep 01, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [8e1734f31a](https://linux-hardware.org/?probe=8e1734f31a) | Sep 01, 2022 |
| SZMZ          | X99M-G2                     | Desktop     | [eff1231310](https://linux-hardware.org/?probe=eff1231310) | Aug 31, 2022 |
| JGINYUE       | B85M VH PLUS V1.0           | Desktop     | [8712171422](https://linux-hardware.org/?probe=8712171422) | Aug 30, 2022 |
| JGINYUE       | B85M VH PLUS V1.0           | Desktop     | [f065870080](https://linux-hardware.org/?probe=f065870080) | Aug 30, 2022 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [bc4f5f8811](https://linux-hardware.org/?probe=bc4f5f8811) | Aug 24, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [93f28535f8](https://linux-hardware.org/?probe=93f28535f8) | Aug 23, 2022 |
| MSI           | H81M-E33                    | Desktop     | [56808775ee](https://linux-hardware.org/?probe=56808775ee) | Aug 23, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [7169cd34ab](https://linux-hardware.org/?probe=7169cd34ab) | Aug 22, 2022 |
| HP            | Pavilion g4                 | Notebook    | [f8c2fc628e](https://linux-hardware.org/?probe=f8c2fc628e) | Aug 21, 2022 |
| Intel         | X79M-S                      | Desktop     | [b6746f7b8d](https://linux-hardware.org/?probe=b6746f7b8d) | Aug 18, 2022 |
| Intel         | X79M-S                      | Desktop     | [49a7d62fe8](https://linux-hardware.org/?probe=49a7d62fe8) | Aug 18, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [59080cc039](https://linux-hardware.org/?probe=59080cc039) | Aug 17, 2022 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [9cefc23bb3](https://linux-hardware.org/?probe=9cefc23bb3) | Aug 17, 2022 |
| Lenovo        | IdeaPad S540-13IML 81XA     | Notebook    | [9ee2e85959](https://linux-hardware.org/?probe=9ee2e85959) | Aug 14, 2022 |
| A-DATA Tec... | XENIA 14                    | Notebook    | [51cc14cc1f](https://linux-hardware.org/?probe=51cc14cc1f) | Aug 14, 2022 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [eeed6b3d08](https://linux-hardware.org/?probe=eeed6b3d08) | Aug 14, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [81a59240ea](https://linux-hardware.org/?probe=81a59240ea) | Aug 13, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [3db0355713](https://linux-hardware.org/?probe=3db0355713) | Aug 12, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [818d0c73e8](https://linux-hardware.org/?probe=818d0c73e8) | Aug 12, 2022 |
| HP            | ENVY 17 Leap Motion SE N... | Notebook    | [efd4ec3ee7](https://linux-hardware.org/?probe=efd4ec3ee7) | Aug 11, 2022 |
| HP            | TouchSmart tm2              | Notebook    | [541d75d7ee](https://linux-hardware.org/?probe=541d75d7ee) | Aug 11, 2022 |
| HP            | TouchSmart tm2              | Notebook    | [77b260c9f1](https://linux-hardware.org/?probe=77b260c9f1) | Aug 11, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f9efd8697b](https://linux-hardware.org/?probe=f9efd8697b) | Aug 11, 2022 |
| HP            | 240 G3                      | Notebook    | [77225815d2](https://linux-hardware.org/?probe=77225815d2) | Aug 10, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [832967e639](https://linux-hardware.org/?probe=832967e639) | Aug 09, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [18b6026d87](https://linux-hardware.org/?probe=18b6026d87) | Aug 09, 2022 |
| Google        | Treeya                      | Notebook    | [11f77c6171](https://linux-hardware.org/?probe=11f77c6171) | Aug 08, 2022 |
| Render        | NOTEBOOK Revision A         | Notebook    | [90a540652f](https://linux-hardware.org/?probe=90a540652f) | Aug 06, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | Notebook    | [53c997fe1f](https://linux-hardware.org/?probe=53c997fe1f) | Aug 05, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581LV_... | Notebook    | [764d4ebd1b](https://linux-hardware.org/?probe=764d4ebd1b) | Aug 04, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581LV_... | Notebook    | [5dab148c3e](https://linux-hardware.org/?probe=5dab148c3e) | Aug 04, 2022 |
| MOTILE        | M141                        | Notebook    | [7cdc678c70](https://linux-hardware.org/?probe=7cdc678c70) | Aug 03, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [745f6815cb](https://linux-hardware.org/?probe=745f6815cb) | Jul 30, 2022 |
| Sony          | VPCEA45FL                   | Notebook    | [8079ec1351](https://linux-hardware.org/?probe=8079ec1351) | Jul 29, 2022 |
| MACHINIST     | X79 V2.82H                  | Desktop     | [29694e2098](https://linux-hardware.org/?probe=29694e2098) | Jul 29, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [71b03b93a2](https://linux-hardware.org/?probe=71b03b93a2) | Jul 27, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [a58ae4eb60](https://linux-hardware.org/?probe=a58ae4eb60) | Jul 24, 2022 |
| ASUSTek       | X541NA                      | Notebook    | [51aefa0464](https://linux-hardware.org/?probe=51aefa0464) | Jul 21, 2022 |
| Samsung       | 750XED                      | Notebook    | [546562ffbb](https://linux-hardware.org/?probe=546562ffbb) | Jul 21, 2022 |
| Olidata       | Unknown                     | Desktop     | [ac7a530d9d](https://linux-hardware.org/?probe=ac7a530d9d) | Jul 19, 2022 |
| HP            | 245 G2                      | Notebook    | [03a8791b0c](https://linux-hardware.org/?probe=03a8791b0c) | Jul 18, 2022 |
| Dell          | MXG061                      | Notebook    | [9301162b93](https://linux-hardware.org/?probe=9301162b93) | Jul 18, 2022 |
| Lenovo        | ThinkPad Edge E430 32543... | Notebook    | [75cfb6ffa8](https://linux-hardware.org/?probe=75cfb6ffa8) | Jul 17, 2022 |
| HP            | 245 G2                      | Notebook    | [f37ddc5aed](https://linux-hardware.org/?probe=f37ddc5aed) | Jul 17, 2022 |
| Gigabyte      | H410M H                     | Desktop     | [8a0a0ed167](https://linux-hardware.org/?probe=8a0a0ed167) | Jul 16, 2022 |
| Gigabyte      | H410M H                     | Desktop     | [e94723280f](https://linux-hardware.org/?probe=e94723280f) | Jul 16, 2022 |
| Samsung       | 750XED                      | Notebook    | [eb7c27f7ff](https://linux-hardware.org/?probe=eb7c27f7ff) | Jul 15, 2022 |
| HP            | Pavilion g4                 | Notebook    | [40067cace0](https://linux-hardware.org/?probe=40067cace0) | Jul 14, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [31127e76f8](https://linux-hardware.org/?probe=31127e76f8) | Jul 14, 2022 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [c21113bf90](https://linux-hardware.org/?probe=c21113bf90) | Jul 14, 2022 |
| Lenovo        | ThinkPad P50 20EQA05JCL     | Notebook    | [43f5b3c05d](https://linux-hardware.org/?probe=43f5b3c05d) | Jul 13, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [ed83060c1a](https://linux-hardware.org/?probe=ed83060c1a) | Jul 13, 2022 |
| HP            | Notebook                    | Notebook    | [1358a12fdf](https://linux-hardware.org/?probe=1358a12fdf) | Jul 13, 2022 |
| HP            | Pavilion g4                 | Notebook    | [96ba266748](https://linux-hardware.org/?probe=96ba266748) | Jul 11, 2022 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | Notebook    | [269ebd1a4d](https://linux-hardware.org/?probe=269ebd1a4d) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0c96551a28](https://linux-hardware.org/?probe=0c96551a28) | Jul 09, 2022 |
| Intel         | NUC8BEB J72693-309          | Mini pc     | [f69a70c4b4](https://linux-hardware.org/?probe=f69a70c4b4) | Jul 08, 2022 |
| Lenovo        | ThinkPad T61 6457B5S        | Notebook    | [34e97dae1e](https://linux-hardware.org/?probe=34e97dae1e) | Jul 08, 2022 |
| Samsung       | 305V4A/305V5A/3415VA        | Notebook    | [bcb40b4a21](https://linux-hardware.org/?probe=bcb40b4a21) | Jul 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [c8b9e41a50](https://linux-hardware.org/?probe=c8b9e41a50) | Jul 06, 2022 |
| MSI           | B350 GAMING PLUS            | Desktop     | [de014d917d](https://linux-hardware.org/?probe=de014d917d) | Jul 05, 2022 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [03dd055ce5](https://linux-hardware.org/?probe=03dd055ce5) | Jun 30, 2022 |
| HP            | Compaq 15                   | Notebook    | [fb14abab4d](https://linux-hardware.org/?probe=fb14abab4d) | Jun 30, 2022 |
| Lenovo        | ThinkPad X230 2325U5P       | Notebook    | [5b8770aaf7](https://linux-hardware.org/?probe=5b8770aaf7) | Jun 27, 2022 |
| Lenovo        | ThinkPad X230 2325U5P       | Notebook    | [d80f5059d2](https://linux-hardware.org/?probe=d80f5059d2) | Jun 27, 2022 |
| Lenovo        | ThinkPad X230 2325U5P       | Notebook    | [89b9650228](https://linux-hardware.org/?probe=89b9650228) | Jun 27, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [b56f69ff9c](https://linux-hardware.org/?probe=b56f69ff9c) | Jun 26, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [1eaa95f069](https://linux-hardware.org/?probe=1eaa95f069) | Jun 24, 2022 |
| Samsung       | 750XED                      | Notebook    | [49322b3456](https://linux-hardware.org/?probe=49322b3456) | Jun 21, 2022 |
| Dell          | XPS 12 9Q23                 | Notebook    | [463461920a](https://linux-hardware.org/?probe=463461920a) | Jun 21, 2022 |
| Packard Be... | EasyNote MH36               | Notebook    | [ecd7a50e8e](https://linux-hardware.org/?probe=ecd7a50e8e) | Jun 20, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | Notebook    | [bbb3795dc2](https://linux-hardware.org/?probe=bbb3795dc2) | Jun 20, 2022 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [234a9c1523](https://linux-hardware.org/?probe=234a9c1523) | Jun 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [cb268bf1ab](https://linux-hardware.org/?probe=cb268bf1ab) | Jun 18, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [f5d7a0bba4](https://linux-hardware.org/?probe=f5d7a0bba4) | Jun 17, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [d0c247db91](https://linux-hardware.org/?probe=d0c247db91) | Jun 17, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | Notebook    | [7d8683dfac](https://linux-hardware.org/?probe=7d8683dfac) | Jun 16, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [7adac78ac0](https://linux-hardware.org/?probe=7adac78ac0) | Jun 15, 2022 |
| Dell          | XPS 12 9Q23                 | Notebook    | [77c4dc4a62](https://linux-hardware.org/?probe=77c4dc4a62) | Jun 14, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [cf08ff4333](https://linux-hardware.org/?probe=cf08ff4333) | Jun 14, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [4b4bd76de7](https://linux-hardware.org/?probe=4b4bd76de7) | Jun 14, 2022 |
| Sony          | VPCM120AL                   | Notebook    | [9eb0e19bd0](https://linux-hardware.org/?probe=9eb0e19bd0) | Jun 13, 2022 |
| HP            | 240 G7                      | Notebook    | [2af5911cf8](https://linux-hardware.org/?probe=2af5911cf8) | Jun 12, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [baf792ad50](https://linux-hardware.org/?probe=baf792ad50) | Jun 12, 2022 |
| HP            | 240 G7                      | Notebook    | [bf52288eb2](https://linux-hardware.org/?probe=bf52288eb2) | Jun 10, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [576c9acdaa](https://linux-hardware.org/?probe=576c9acdaa) | Jun 08, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [73ba6fe3c0](https://linux-hardware.org/?probe=73ba6fe3c0) | Jun 06, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [83b786e73a](https://linux-hardware.org/?probe=83b786e73a) | Jun 04, 2022 |
| MSI           | Bravo 15 B5DD               | Notebook    | [d561d8dbdb](https://linux-hardware.org/?probe=d561d8dbdb) | Jun 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [abaa4456ea](https://linux-hardware.org/?probe=abaa4456ea) | Jun 01, 2022 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [b1fe95fd93](https://linux-hardware.org/?probe=b1fe95fd93) | May 31, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [4ad762abcb](https://linux-hardware.org/?probe=4ad762abcb) | May 31, 2022 |
| ECS           | MCP61M-M3                   | Desktop     | [b785b68657](https://linux-hardware.org/?probe=b785b68657) | May 29, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b7b419d941](https://linux-hardware.org/?probe=b7b419d941) | May 28, 2022 |
| HP            | 240 G7                      | Notebook    | [687546391a](https://linux-hardware.org/?probe=687546391a) | May 23, 2022 |
| Dell          | Inspiron 5459               | Notebook    | [ea99252046](https://linux-hardware.org/?probe=ea99252046) | May 20, 2022 |
| Intel         | NUC8BEB J72693-309          | Mini pc     | [73bd0df4ae](https://linux-hardware.org/?probe=73bd0df4ae) | May 19, 2022 |
| Unknown       | Unknown                     | Notebook    | [834d86e9da](https://linux-hardware.org/?probe=834d86e9da) | May 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [713dcb3d05](https://linux-hardware.org/?probe=713dcb3d05) | May 17, 2022 |
| HP            | 2ADE                        | Desktop     | [77c2ea750b](https://linux-hardware.org/?probe=77c2ea750b) | May 17, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [be93982cf0](https://linux-hardware.org/?probe=be93982cf0) | May 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [84ae0966e6](https://linux-hardware.org/?probe=84ae0966e6) | May 15, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [a7fb96d9aa](https://linux-hardware.org/?probe=a7fb96d9aa) | May 13, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f2f965ba56](https://linux-hardware.org/?probe=f2f965ba56) | May 13, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | Notebook    | [74d92cc46f](https://linux-hardware.org/?probe=74d92cc46f) | May 11, 2022 |
| LG Electro... | 15Z995-U.ARS5U1             | Notebook    | [4efbc907db](https://linux-hardware.org/?probe=4efbc907db) | May 11, 2022 |
| Acer          | Aspire R7-371T              | Notebook    | [207110a3d4](https://linux-hardware.org/?probe=207110a3d4) | May 07, 2022 |
| ASUSTek       | Maximus VI EXTREME          | Desktop     | [21e4e874a2](https://linux-hardware.org/?probe=21e4e874a2) | May 06, 2022 |
| ASUSTek       | Maximus VI EXTREME          | Desktop     | [37e77cbfe5](https://linux-hardware.org/?probe=37e77cbfe5) | May 06, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [c275c52e93](https://linux-hardware.org/?probe=c275c52e93) | May 04, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [799038a9eb](https://linux-hardware.org/?probe=799038a9eb) | May 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [61e54407f3](https://linux-hardware.org/?probe=61e54407f3) | May 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [7d0cabeccf](https://linux-hardware.org/?probe=7d0cabeccf) | May 04, 2022 |
| HP            | Pavilion g4                 | Notebook    | [afad13fa01](https://linux-hardware.org/?probe=afad13fa01) | May 04, 2022 |
| MSI           | B250M GAMING PRO            | Desktop     | [cd1e81afae](https://linux-hardware.org/?probe=cd1e81afae) | May 03, 2022 |
| MSI           | B250M GAMING PRO            | Desktop     | [bf6d6784ab](https://linux-hardware.org/?probe=bf6d6784ab) | May 03, 2022 |
| MSI           | B450M BAZOOKA               | Desktop     | [a913401ce9](https://linux-hardware.org/?probe=a913401ce9) | May 02, 2022 |
| MSI           | B450M BAZOOKA               | Desktop     | [726be8a4f1](https://linux-hardware.org/?probe=726be8a4f1) | May 02, 2022 |
| ASUSTek       | H110M-R                     | Desktop     | [0fa0b3d5f4](https://linux-hardware.org/?probe=0fa0b3d5f4) | May 01, 2022 |
| Lenovo        | ThinkPad T61 7659A39        | Notebook    | [e5c32846e2](https://linux-hardware.org/?probe=e5c32846e2) | Apr 30, 2022 |
| Acer          | Aspire E5-411G              | Notebook    | [0629e76746](https://linux-hardware.org/?probe=0629e76746) | Apr 30, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [876baf36d7](https://linux-hardware.org/?probe=876baf36d7) | Apr 29, 2022 |
| HP            | Pavilion 14                 | Notebook    | [84bde5e223](https://linux-hardware.org/?probe=84bde5e223) | Apr 29, 2022 |
| HP            | Pavilion g4                 | Notebook    | [a10918283d](https://linux-hardware.org/?probe=a10918283d) | Apr 28, 2022 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [f40f12b9be](https://linux-hardware.org/?probe=f40f12b9be) | Apr 27, 2022 |
| Intel         | Unknown                     | Notebook    | [41b673dda8](https://linux-hardware.org/?probe=41b673dda8) | Apr 26, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [6fbbf00053](https://linux-hardware.org/?probe=6fbbf00053) | Apr 23, 2022 |
| Lenovo        | IdeaPadFlex 15 20309        | Notebook    | [6dac014a49](https://linux-hardware.org/?probe=6dac014a49) | Apr 22, 2022 |
| Intel         | NUC8BEB J72693-309          | Mini pc     | [d103edc70e](https://linux-hardware.org/?probe=d103edc70e) | Apr 21, 2022 |
| Intel         | NUC8BEB J72693-309          | Mini pc     | [e5d8c4e246](https://linux-hardware.org/?probe=e5d8c4e246) | Apr 21, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [cb4bc274b3](https://linux-hardware.org/?probe=cb4bc274b3) | Apr 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4e2119abc8](https://linux-hardware.org/?probe=4e2119abc8) | Apr 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d43a69ef63](https://linux-hardware.org/?probe=d43a69ef63) | Apr 21, 2022 |
| Chuwi         | Hi10 X                      | Tablet      | [c83cb969dc](https://linux-hardware.org/?probe=c83cb969dc) | Apr 19, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [79eb10a5ef](https://linux-hardware.org/?probe=79eb10a5ef) | Apr 19, 2022 |
| MSI           | H81M-E33                    | Desktop     | [ff9197cd63](https://linux-hardware.org/?probe=ff9197cd63) | Apr 17, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7d0cde0bcd](https://linux-hardware.org/?probe=7d0cde0bcd) | Apr 13, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [28897f0c7b](https://linux-hardware.org/?probe=28897f0c7b) | Apr 13, 2022 |
| ASUSTek       | X405UQ                      | Notebook    | [4b63447e77](https://linux-hardware.org/?probe=4b63447e77) | Apr 10, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [4c367d8a9c](https://linux-hardware.org/?probe=4c367d8a9c) | Apr 08, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [f531f62c1b](https://linux-hardware.org/?probe=f531f62c1b) | Apr 03, 2022 |
| Dell          | Vostro A860                 | Notebook    | [15ce9e1f63](https://linux-hardware.org/?probe=15ce9e1f63) | Apr 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [4ad9fe021c](https://linux-hardware.org/?probe=4ad9fe021c) | Mar 31, 2022 |
| HP            | 1998                        | Desktop     | [13b901f36a](https://linux-hardware.org/?probe=13b901f36a) | Mar 29, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [4a8c48df20](https://linux-hardware.org/?probe=4a8c48df20) | Mar 28, 2022 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [e02f2032f1](https://linux-hardware.org/?probe=e02f2032f1) | Mar 28, 2022 |
| Dell          | Latitude E5450              | Notebook    | [776f0672a0](https://linux-hardware.org/?probe=776f0672a0) | Mar 23, 2022 |
| Dell          | Latitude E5450              | Notebook    | [fb7f18d5a2](https://linux-hardware.org/?probe=fb7f18d5a2) | Mar 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9183654349](https://linux-hardware.org/?probe=9183654349) | Mar 22, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [95acb8d0af](https://linux-hardware.org/?probe=95acb8d0af) | Mar 21, 2022 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [baae82b163](https://linux-hardware.org/?probe=baae82b163) | Mar 19, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [539ebb7dd9](https://linux-hardware.org/?probe=539ebb7dd9) | Mar 15, 2022 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [95c6b15672](https://linux-hardware.org/?probe=95c6b15672) | Mar 14, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [82cfb46909](https://linux-hardware.org/?probe=82cfb46909) | Mar 13, 2022 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [671a3fc70b](https://linux-hardware.org/?probe=671a3fc70b) | Mar 12, 2022 |
| Packard Be... | EasyNote MH35               | Notebook    | [66bff1bcfd](https://linux-hardware.org/?probe=66bff1bcfd) | Mar 08, 2022 |
| ASUSTek       | G752VY                      | Notebook    | [379733b3e7](https://linux-hardware.org/?probe=379733b3e7) | Mar 07, 2022 |
| Elife         | series                      | Notebook    | [dddf04aa69](https://linux-hardware.org/?probe=dddf04aa69) | Mar 05, 2022 |
| Elife         | series                      | Notebook    | [979e43c05a](https://linux-hardware.org/?probe=979e43c05a) | Mar 05, 2022 |
| HP            | 2140                        | Notebook    | [6956607bfd](https://linux-hardware.org/?probe=6956607bfd) | Mar 02, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [332a3f936b](https://linux-hardware.org/?probe=332a3f936b) | Feb 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [2f1bb56767](https://linux-hardware.org/?probe=2f1bb56767) | Feb 28, 2022 |
| Lenovo        | ThinkPad T490 20RXS0VX00    | Notebook    | [8f42f6fd5f](https://linux-hardware.org/?probe=8f42f6fd5f) | Feb 28, 2022 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [3f97cefeb4](https://linux-hardware.org/?probe=3f97cefeb4) | Feb 26, 2022 |
| Sony          | VAIO                        | All in one  | [4d477a343a](https://linux-hardware.org/?probe=4d477a343a) | Feb 26, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [8dfdb07f98](https://linux-hardware.org/?probe=8dfdb07f98) | Feb 24, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [7a8aaaa5a6](https://linux-hardware.org/?probe=7a8aaaa5a6) | Feb 23, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [849ceb3653](https://linux-hardware.org/?probe=849ceb3653) | Feb 23, 2022 |
| Lenovo        | ThinkPad T495 20NJ0004US    | Notebook    | [d8002e9eae](https://linux-hardware.org/?probe=d8002e9eae) | Feb 23, 2022 |
| Google        | Barla                       | Notebook    | [12180ab1ff](https://linux-hardware.org/?probe=12180ab1ff) | Feb 22, 2022 |
| Toshiba       | Satellite L505              | Notebook    | [16e608fb6b](https://linux-hardware.org/?probe=16e608fb6b) | Feb 22, 2022 |
| HP            | ENVY 15                     | Notebook    | [9758bb9b66](https://linux-hardware.org/?probe=9758bb9b66) | Feb 20, 2022 |
| Dell          | 0CT017                      | Desktop     | [27a31fcb1b](https://linux-hardware.org/?probe=27a31fcb1b) | Feb 17, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [46021e669f](https://linux-hardware.org/?probe=46021e669f) | Feb 17, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [4de3659979](https://linux-hardware.org/?probe=4de3659979) | Feb 16, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [c81bbf6c93](https://linux-hardware.org/?probe=c81bbf6c93) | Feb 16, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [309f440466](https://linux-hardware.org/?probe=309f440466) | Feb 15, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [81f2a365be](https://linux-hardware.org/?probe=81f2a365be) | Feb 13, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [18fa19a4f0](https://linux-hardware.org/?probe=18fa19a4f0) | Feb 10, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [824518037a](https://linux-hardware.org/?probe=824518037a) | Feb 10, 2022 |
| Pegatron      | 2ACB                        | Desktop     | [b7987fdaa7](https://linux-hardware.org/?probe=b7987fdaa7) | Feb 10, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [dae40dba1f](https://linux-hardware.org/?probe=dae40dba1f) | Feb 09, 2022 |
| Gigabyte      | B560M DS3H                  | Desktop     | [3c0ad9ce1b](https://linux-hardware.org/?probe=3c0ad9ce1b) | Feb 08, 2022 |
| MSI           | H310M GAMING ARCTIC         | Desktop     | [842ee88335](https://linux-hardware.org/?probe=842ee88335) | Jan 26, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [3060acc083](https://linux-hardware.org/?probe=3060acc083) | Jan 22, 2022 |
| Acer          | Aspire ES1-111M             | Notebook    | [02368f5bb1](https://linux-hardware.org/?probe=02368f5bb1) | Jan 22, 2022 |
| Lenovo        | G400 20235                  | Notebook    | [cba5cda239](https://linux-hardware.org/?probe=cba5cda239) | Jan 21, 2022 |
| HP            | Laptop 15-da1xxx            | Notebook    | [d6706833ff](https://linux-hardware.org/?probe=d6706833ff) | Jan 21, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [c00dd7c570](https://linux-hardware.org/?probe=c00dd7c570) | Jan 18, 2022 |
| Dell          | Inspiron 3480               | Notebook    | [ca729da91f](https://linux-hardware.org/?probe=ca729da91f) | Jan 16, 2022 |
| Lenovo        | ThinkPad T480 20L6A0UGCL    | Notebook    | [e9dbb29c83](https://linux-hardware.org/?probe=e9dbb29c83) | Jan 16, 2022 |
| Acer          | AOD255E                     | Notebook    | [cf1f3ab0e0](https://linux-hardware.org/?probe=cf1f3ab0e0) | Jan 13, 2022 |
| HP            | Pavilion 15                 | Notebook    | [95f3d87b66](https://linux-hardware.org/?probe=95f3d87b66) | Jan 09, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [edc40344ef](https://linux-hardware.org/?probe=edc40344ef) | Jan 08, 2022 |
| HONOR         | NBR-WAX9                    | Notebook    | [979f80197d](https://linux-hardware.org/?probe=979f80197d) | Jan 07, 2022 |
| MSI           | B85M-E33 V2                 | Desktop     | [ef65c0c144](https://linux-hardware.org/?probe=ef65c0c144) | Jan 05, 2022 |
| ASRock        | B550 Steel Legend           | Desktop     | [8107f2613f](https://linux-hardware.org/?probe=8107f2613f) | Jan 05, 2022 |
| ASRock        | B550 Steel Legend           | Desktop     | [704e9c09ad](https://linux-hardware.org/?probe=704e9c09ad) | Jan 05, 2022 |
| Sony          | SVE14A390X                  | Notebook    | [3b11d123cf](https://linux-hardware.org/?probe=3b11d123cf) | Jan 04, 2022 |
| HP            | EliteBook 6930p             | Notebook    | [0346ff374d](https://linux-hardware.org/?probe=0346ff374d) | Dec 26, 2021 |
| Acer          | Aspire E1-531               | Notebook    | [d1d6054fc3](https://linux-hardware.org/?probe=d1d6054fc3) | Dec 22, 2021 |
| Google        | Barla                       | Notebook    | [cfdb4935cd](https://linux-hardware.org/?probe=cfdb4935cd) | Dec 21, 2021 |
| Google        | Barla                       | Notebook    | [0629410759](https://linux-hardware.org/?probe=0629410759) | Dec 21, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [46dab8c74a](https://linux-hardware.org/?probe=46dab8c74a) | Dec 16, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [2e00250378](https://linux-hardware.org/?probe=2e00250378) | Dec 16, 2021 |
| ASUSTek       | AM1M-A                      | Desktop     | [5113655631](https://linux-hardware.org/?probe=5113655631) | Dec 14, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [fc49eed81d](https://linux-hardware.org/?probe=fc49eed81d) | Dec 09, 2021 |
| Samsung       | R510/P510                   | Notebook    | [37a9793570](https://linux-hardware.org/?probe=37a9793570) | Dec 08, 2021 |
| Dell          | Inspiron 14-3467            | Notebook    | [c53e56384e](https://linux-hardware.org/?probe=c53e56384e) | Dec 07, 2021 |
| Samsung       | R510/P510                   | Notebook    | [f55c0c88cc](https://linux-hardware.org/?probe=f55c0c88cc) | Dec 07, 2021 |
| Lenovo        | ThinkPad T460 20FMA03MCL    | Notebook    | [aecb392c83](https://linux-hardware.org/?probe=aecb392c83) | Dec 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [18da52385a](https://linux-hardware.org/?probe=18da52385a) | Dec 04, 2021 |
| MSI           | 3664h                       | Desktop     | [c4bc6c8049](https://linux-hardware.org/?probe=c4bc6c8049) | Nov 29, 2021 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [6490a6beba](https://linux-hardware.org/?probe=6490a6beba) | Nov 29, 2021 |
| Acer          | Swift SF113-31              | Notebook    | [f1e3d8c722](https://linux-hardware.org/?probe=f1e3d8c722) | Nov 29, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [baa3bf4a04](https://linux-hardware.org/?probe=baa3bf4a04) | Nov 27, 2021 |
| Dell          | Inspiron M5010              | Notebook    | [489679b294](https://linux-hardware.org/?probe=489679b294) | Nov 27, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [e9b3a62560](https://linux-hardware.org/?probe=e9b3a62560) | Nov 26, 2021 |
| ASUSTek       | TUF Gaming FX506LI_FX506... | Notebook    | [93b6cabcb6](https://linux-hardware.org/?probe=93b6cabcb6) | Nov 25, 2021 |
| HP            | 245 G6                      | Notebook    | [103da5dd76](https://linux-hardware.org/?probe=103da5dd76) | Nov 25, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [93e8bc8935](https://linux-hardware.org/?probe=93e8bc8935) | Nov 24, 2021 |
| Acer          | Aspire V5-471P              | Notebook    | [bf3b81cbb6](https://linux-hardware.org/?probe=bf3b81cbb6) | Nov 20, 2021 |
| HP            | 250 G5 Notebook PC          | Notebook    | [befb5b9afe](https://linux-hardware.org/?probe=befb5b9afe) | Nov 18, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | Notebook    | [787fc2d581](https://linux-hardware.org/?probe=787fc2d581) | Nov 18, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [d26e2fac89](https://linux-hardware.org/?probe=d26e2fac89) | Nov 17, 2021 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [10a3cb9d12](https://linux-hardware.org/?probe=10a3cb9d12) | Nov 15, 2021 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [2bca77430e](https://linux-hardware.org/?probe=2bca77430e) | Nov 14, 2021 |
| Lenovo        | IdeaPad 720S-14IKB 80XC     | Notebook    | [d0f383a016](https://linux-hardware.org/?probe=d0f383a016) | Nov 13, 2021 |
| Unknown       | Unknown                     | Notebook    | [a61385548e](https://linux-hardware.org/?probe=a61385548e) | Nov 13, 2021 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | Notebook    | [8b26cea464](https://linux-hardware.org/?probe=8b26cea464) | Nov 13, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | Notebook    | [835c948f68](https://linux-hardware.org/?probe=835c948f68) | Nov 13, 2021 |
| Samsung       | 550P5C/550P7C               | Notebook    | [31bc59dcb9](https://linux-hardware.org/?probe=31bc59dcb9) | Nov 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [ab746b7399](https://linux-hardware.org/?probe=ab746b7399) | Nov 12, 2021 |
| HP            | 2215                        | Desktop     | [4e65fa6078](https://linux-hardware.org/?probe=4e65fa6078) | Nov 09, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [c0671f26c9](https://linux-hardware.org/?probe=c0671f26c9) | Nov 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [258e2f1594](https://linux-hardware.org/?probe=258e2f1594) | Nov 08, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1dd0c3ba0a](https://linux-hardware.org/?probe=1dd0c3ba0a) | Nov 05, 2021 |
| HP            | 250 G5 Notebook PC          | Notebook    | [d6eff141a3](https://linux-hardware.org/?probe=d6eff141a3) | Nov 04, 2021 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [e53f2b7fd5](https://linux-hardware.org/?probe=e53f2b7fd5) | Nov 03, 2021 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [922c058537](https://linux-hardware.org/?probe=922c058537) | Nov 03, 2021 |
| MSI           | B365M PRO-VH                | Desktop     | [c2976ad59c](https://linux-hardware.org/?probe=c2976ad59c) | Nov 03, 2021 |
| Acer          | Aspire ES1-311              | Notebook    | [594175a2ac](https://linux-hardware.org/?probe=594175a2ac) | Nov 01, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [befb41472e](https://linux-hardware.org/?probe=befb41472e) | Oct 23, 2021 |
| Samsung       | 550P5C/550P7C               | Notebook    | [2713972f14](https://linux-hardware.org/?probe=2713972f14) | Oct 22, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [3f67c7622c](https://linux-hardware.org/?probe=3f67c7622c) | Oct 22, 2021 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [76071ec77b](https://linux-hardware.org/?probe=76071ec77b) | Oct 19, 2021 |
| Nvidia        | NF-MCP61                    | Desktop     | [666f204c08](https://linux-hardware.org/?probe=666f204c08) | Oct 18, 2021 |
| HP            | 250 G6 Notebook PC          | Notebook    | [7076268ecc](https://linux-hardware.org/?probe=7076268ecc) | Oct 17, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f7524634b9](https://linux-hardware.org/?probe=f7524634b9) | Oct 16, 2021 |
| HP            | Compaq CQ45                 | Notebook    | [e51cebc629](https://linux-hardware.org/?probe=e51cebc629) | Oct 16, 2021 |
| HP            | Compaq CQ45                 | Notebook    | [18a1e9d294](https://linux-hardware.org/?probe=18a1e9d294) | Oct 16, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [8f7c7a493b](https://linux-hardware.org/?probe=8f7c7a493b) | Oct 16, 2021 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [36e45017ff](https://linux-hardware.org/?probe=36e45017ff) | Oct 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [06b7518f72](https://linux-hardware.org/?probe=06b7518f72) | Oct 14, 2021 |
| Acer          | Aspire ES1-311              | Notebook    | [8f1dd3ce3a](https://linux-hardware.org/?probe=8f1dd3ce3a) | Oct 12, 2021 |
| ASUSTek       | X302LJ                      | Notebook    | [a0e3e93f48](https://linux-hardware.org/?probe=a0e3e93f48) | Oct 12, 2021 |
| Acer          | Aspire ES1-311              | Notebook    | [df266accf1](https://linux-hardware.org/?probe=df266accf1) | Oct 12, 2021 |
| ASUSTek       | X302LJ                      | Notebook    | [ad35db71c7](https://linux-hardware.org/?probe=ad35db71c7) | Oct 12, 2021 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [36d8e83f29](https://linux-hardware.org/?probe=36d8e83f29) | Oct 11, 2021 |
| Lenovo        | Y520-15IKBM 80YY            | Notebook    | [fc28e4f7f8](https://linux-hardware.org/?probe=fc28e4f7f8) | Oct 10, 2021 |
| HP            | x2 210                      | Notebook    | [ccf01919ab](https://linux-hardware.org/?probe=ccf01919ab) | Oct 09, 2021 |
| HP            | x2 210                      | Notebook    | [a35274c0a7](https://linux-hardware.org/?probe=a35274c0a7) | Oct 09, 2021 |
| HP            | Notebook                    | Notebook    | [d332712e6f](https://linux-hardware.org/?probe=d332712e6f) | Oct 08, 2021 |
| HP            | Notebook                    | Notebook    | [04313f623e](https://linux-hardware.org/?probe=04313f623e) | Oct 07, 2021 |
| HP            | Notebook                    | Notebook    | [282f030bc4](https://linux-hardware.org/?probe=282f030bc4) | Oct 07, 2021 |
| Alienware     | M17xR3                      | Notebook    | [740de1796c](https://linux-hardware.org/?probe=740de1796c) | Oct 05, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [8ea6adfced](https://linux-hardware.org/?probe=8ea6adfced) | Oct 03, 2021 |
| ASUSTek       | X555LB                      | Notebook    | [3af223c792](https://linux-hardware.org/?probe=3af223c792) | Sep 30, 2021 |
| Intel         | DG41WV AAE90316-103         | Desktop     | [0055a963ef](https://linux-hardware.org/?probe=0055a963ef) | Sep 30, 2021 |
| Gigabyte      | A520M DS3H                  | Desktop     | [228b36fb26](https://linux-hardware.org/?probe=228b36fb26) | Sep 28, 2021 |
| Dell          | G3 3590                     | Notebook    | [519cea3f38](https://linux-hardware.org/?probe=519cea3f38) | Sep 25, 2021 |
| Dell          | G3 3590                     | Notebook    | [bb25c895cf](https://linux-hardware.org/?probe=bb25c895cf) | Sep 25, 2021 |
| ASUSTek       | X302LJ                      | Notebook    | [281beb5fe7](https://linux-hardware.org/?probe=281beb5fe7) | Sep 23, 2021 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [7360f8d859](https://linux-hardware.org/?probe=7360f8d859) | Sep 23, 2021 |
| Acer          | Aspire ES1-572              | Notebook    | [36c622eabc](https://linux-hardware.org/?probe=36c622eabc) | Sep 21, 2021 |
| Acer          | Aspire ES1-572              | Notebook    | [0ce8da0fe0](https://linux-hardware.org/?probe=0ce8da0fe0) | Sep 21, 2021 |
| Huanan        | X79 249PC V2.3              | Desktop     | [feb9cf5a3f](https://linux-hardware.org/?probe=feb9cf5a3f) | Sep 20, 2021 |
| Huanan        | X79 249PC V2.3              | Desktop     | [0025ab8888](https://linux-hardware.org/?probe=0025ab8888) | Sep 20, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [99773cf00e](https://linux-hardware.org/?probe=99773cf00e) | Sep 19, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [079bf76915](https://linux-hardware.org/?probe=079bf76915) | Sep 18, 2021 |
| ASRock        | Z490 Phantom Gaming 4G      | Desktop     | [7857ce2ffa](https://linux-hardware.org/?probe=7857ce2ffa) | Sep 16, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [68305a2ede](https://linux-hardware.org/?probe=68305a2ede) | Sep 15, 2021 |
| Dell          | Inspiron 5459               | Notebook    | [ef87caa5ba](https://linux-hardware.org/?probe=ef87caa5ba) | Sep 12, 2021 |
| ASUSTek       | B85M-E                      | Desktop     | [27a6448b5e](https://linux-hardware.org/?probe=27a6448b5e) | Sep 12, 2021 |
| HC            | HCAR357-MI V1.0             | Desktop     | [e2df45f5f6](https://linux-hardware.org/?probe=e2df45f5f6) | Sep 12, 2021 |
| Intel         | X79M-S                      | Desktop     | [95d22f6e90](https://linux-hardware.org/?probe=95d22f6e90) | Sep 11, 2021 |
| Dell          | Inspiron 5459               | Notebook    | [feea6f3fec](https://linux-hardware.org/?probe=feea6f3fec) | Sep 11, 2021 |
| ASUSTek       | B85M-E                      | Desktop     | [36685ad5ea](https://linux-hardware.org/?probe=36685ad5ea) | Sep 11, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [15ed5db330](https://linux-hardware.org/?probe=15ed5db330) | Sep 09, 2021 |
| ASUSTek       | TUF Gaming FX506LI_FX506... | Notebook    | [890790d388](https://linux-hardware.org/?probe=890790d388) | Sep 07, 2021 |
| ASUSTek       | TUF Gaming FX506LI_FX506... | Notebook    | [341d88eae9](https://linux-hardware.org/?probe=341d88eae9) | Sep 07, 2021 |
| HP            | 339A                        | Desktop     | [ae80063e20](https://linux-hardware.org/?probe=ae80063e20) | Sep 07, 2021 |
| HC            | HCAR357-MI V1.0             | Desktop     | [14536c9a37](https://linux-hardware.org/?probe=14536c9a37) | Sep 06, 2021 |
| Intel         | X79M-S                      | Desktop     | [e45160873d](https://linux-hardware.org/?probe=e45160873d) | Sep 06, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [a8f9c859be](https://linux-hardware.org/?probe=a8f9c859be) | Sep 05, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [3c5b6aa997](https://linux-hardware.org/?probe=3c5b6aa997) | Sep 05, 2021 |
| HP            | 339A                        | Desktop     | [ceb91782c2](https://linux-hardware.org/?probe=ceb91782c2) | Sep 05, 2021 |
| HC            | HCAR357-MI V1.0             | Desktop     | [3697a37403](https://linux-hardware.org/?probe=3697a37403) | Sep 04, 2021 |
| HC            | HCAR357-MI V1.0             | Desktop     | [e4d2306204](https://linux-hardware.org/?probe=e4d2306204) | Sep 04, 2021 |
| HP            | 339A                        | Desktop     | [2c96fd74fb](https://linux-hardware.org/?probe=2c96fd74fb) | Sep 04, 2021 |
| Acer          | Swift SF314-59              | Notebook    | [f6df33267b](https://linux-hardware.org/?probe=f6df33267b) | Sep 02, 2021 |
| Lenovo        | G480 20156                  | Notebook    | [436287e7dc](https://linux-hardware.org/?probe=436287e7dc) | Sep 02, 2021 |
| Lenovo        | G480 20156                  | Notebook    | [a89f3e4acf](https://linux-hardware.org/?probe=a89f3e4acf) | Sep 02, 2021 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [6bf33dd2cb](https://linux-hardware.org/?probe=6bf33dd2cb) | Sep 01, 2021 |
| ASUSTek       | UX410UQK                    | Notebook    | [d2804fad00](https://linux-hardware.org/?probe=d2804fad00) | Sep 01, 2021 |
| ASUSTek       | UX410UQK                    | Notebook    | [819b70e8cb](https://linux-hardware.org/?probe=819b70e8cb) | Sep 01, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [93a7aa0485](https://linux-hardware.org/?probe=93a7aa0485) | Aug 31, 2021 |
| HP            | 339A                        | Desktop     | [5a5ab8d1c2](https://linux-hardware.org/?probe=5a5ab8d1c2) | Aug 31, 2021 |
| HP            | 339A                        | Desktop     | [c0043e4c4c](https://linux-hardware.org/?probe=c0043e4c4c) | Aug 31, 2021 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [190ef257e8](https://linux-hardware.org/?probe=190ef257e8) | Aug 30, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [1dbc26a990](https://linux-hardware.org/?probe=1dbc26a990) | Aug 29, 2021 |
| Toshiba       | Satellite C845D             | Notebook    | [ac992ef3e5](https://linux-hardware.org/?probe=ac992ef3e5) | Aug 29, 2021 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [f6049274c5](https://linux-hardware.org/?probe=f6049274c5) | Aug 27, 2021 |
| Gigabyte      | H97M-D3H                    | Desktop     | [a2afd00e64](https://linux-hardware.org/?probe=a2afd00e64) | Aug 26, 2021 |
| Lenovo        | ThinkPad X260 20F5S3J00D    | Notebook    | [eeb6586c28](https://linux-hardware.org/?probe=eeb6586c28) | Aug 26, 2021 |
| Sony          | VGN-NW215T                  | Notebook    | [3b59710f01](https://linux-hardware.org/?probe=3b59710f01) | Aug 25, 2021 |
| Supermicro    | H8DG6/H8DGi                 | Server      | [1fe97b31a1](https://linux-hardware.org/?probe=1fe97b31a1) | Aug 24, 2021 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | Notebook    | [207f0c8966](https://linux-hardware.org/?probe=207f0c8966) | Aug 24, 2021 |
| Acer          | Aspire 7741                 | Notebook    | [849c1fe7e3](https://linux-hardware.org/?probe=849c1fe7e3) | Aug 22, 2021 |
| HP            | ProBook 440 G3              | Notebook    | [80aa412668](https://linux-hardware.org/?probe=80aa412668) | Aug 22, 2021 |
| Dell          | 0GDG8Y A00                  | Desktop     | [2a0bf4d1a9](https://linux-hardware.org/?probe=2a0bf4d1a9) | Aug 21, 2021 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [28d8feb60d](https://linux-hardware.org/?probe=28d8feb60d) | Aug 20, 2021 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [f207dc8e9a](https://linux-hardware.org/?probe=f207dc8e9a) | Aug 20, 2021 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | Notebook    | [ab27a12603](https://linux-hardware.org/?probe=ab27a12603) | Aug 18, 2021 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [0eb2abca1d](https://linux-hardware.org/?probe=0eb2abca1d) | Aug 18, 2021 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [9c25f25e8f](https://linux-hardware.org/?probe=9c25f25e8f) | Aug 16, 2021 |
| Pegatron      | 2ADC                        | Desktop     | [48cc7f548e](https://linux-hardware.org/?probe=48cc7f548e) | Aug 13, 2021 |
| MSI           | B75MA-E33                   | Desktop     | [8a1743cb75](https://linux-hardware.org/?probe=8a1743cb75) | Aug 10, 2021 |
| Dell          | Inspiron 5459               | Notebook    | [b99b48660a](https://linux-hardware.org/?probe=b99b48660a) | Aug 08, 2021 |
| Sony          | SVE14A27CLS                 | Notebook    | [53a5965063](https://linux-hardware.org/?probe=53a5965063) | Aug 07, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [4d0bb591af](https://linux-hardware.org/?probe=4d0bb591af) | Aug 06, 2021 |
| Dell          | G3 3590                     | Notebook    | [16bdb588e1](https://linux-hardware.org/?probe=16bdb588e1) | Aug 05, 2021 |
| Dell          | G3 3590                     | Notebook    | [01a9560f9c](https://linux-hardware.org/?probe=01a9560f9c) | Aug 05, 2021 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [482c64a9c9](https://linux-hardware.org/?probe=482c64a9c9) | Aug 03, 2021 |
| Packard Be... | EasyNote MH35               | Notebook    | [e053c132dc](https://linux-hardware.org/?probe=e053c132dc) | Aug 02, 2021 |
| Dell          | Inspiron 5459               | Notebook    | [acc597c748](https://linux-hardware.org/?probe=acc597c748) | Aug 02, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [7b213037a5](https://linux-hardware.org/?probe=7b213037a5) | Jul 31, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [60b58b4557](https://linux-hardware.org/?probe=60b58b4557) | Jul 28, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [2e753f12ce](https://linux-hardware.org/?probe=2e753f12ce) | Jul 28, 2021 |
| Medion        | Unknown                     | Notebook    | [021ba4d5b5](https://linux-hardware.org/?probe=021ba4d5b5) | Jul 25, 2021 |
| Medion        | Unknown                     | Notebook    | [e9c5e99e0b](https://linux-hardware.org/?probe=e9c5e99e0b) | Jul 25, 2021 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [cae2419e98](https://linux-hardware.org/?probe=cae2419e98) | Jul 25, 2021 |
| MSI           | 3664h                       | Desktop     | [491117f46c](https://linux-hardware.org/?probe=491117f46c) | Jul 25, 2021 |
| MSI           | 3664h                       | Desktop     | [c9f3c48709](https://linux-hardware.org/?probe=c9f3c48709) | Jul 24, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [1d0f458592](https://linux-hardware.org/?probe=1d0f458592) | Jul 23, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [f8812e14cb](https://linux-hardware.org/?probe=f8812e14cb) | Jul 23, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [abea66177f](https://linux-hardware.org/?probe=abea66177f) | Jul 20, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [0d3be70373](https://linux-hardware.org/?probe=0d3be70373) | Jul 20, 2021 |
| MSI           | H81M-E33                    | Desktop     | [f56f54e2fa](https://linux-hardware.org/?probe=f56f54e2fa) | Jul 18, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [783a5cafc2](https://linux-hardware.org/?probe=783a5cafc2) | Jul 18, 2021 |
| HP            | ENVY 15                     | Notebook    | [d2a3149a9a](https://linux-hardware.org/?probe=d2a3149a9a) | Jul 17, 2021 |
| eMachines     | EL1352                      | Desktop     | [83c494c15a](https://linux-hardware.org/?probe=83c494c15a) | Jul 17, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [2db57969aa](https://linux-hardware.org/?probe=2db57969aa) | Jul 17, 2021 |
| R-StyleCom... | ALICON AI2S-A21 00.69       | Desktop     | [85a8017eaf](https://linux-hardware.org/?probe=85a8017eaf) | Jul 15, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f024f2512e](https://linux-hardware.org/?probe=f024f2512e) | Jul 14, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [5320824c78](https://linux-hardware.org/?probe=5320824c78) | Jul 11, 2021 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [efc4c63ac7](https://linux-hardware.org/?probe=efc4c63ac7) | Jul 09, 2021 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [9f7d75d241](https://linux-hardware.org/?probe=9f7d75d241) | Jul 09, 2021 |
| HP            | Spectre Laptop 13-af0xx     | Notebook    | [bfef4cded0](https://linux-hardware.org/?probe=bfef4cded0) | Jul 09, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [ef9a6d3444](https://linux-hardware.org/?probe=ef9a6d3444) | Jul 08, 2021 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [e3ea65a467](https://linux-hardware.org/?probe=e3ea65a467) | Jul 07, 2021 |
| Dell          | 0Y5DDC A00                  | Desktop     | [1888baa539](https://linux-hardware.org/?probe=1888baa539) | Jul 06, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a87404851f](https://linux-hardware.org/?probe=a87404851f) | Jul 01, 2021 |
| MSI           | A75MA-G55                   | Desktop     | [3611191f22](https://linux-hardware.org/?probe=3611191f22) | Jun 30, 2021 |
| HP            | Notebook                    | Notebook    | [3087e92283](https://linux-hardware.org/?probe=3087e92283) | Jun 29, 2021 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [771f0fed2a](https://linux-hardware.org/?probe=771f0fed2a) | Jun 27, 2021 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [48a1dddc38](https://linux-hardware.org/?probe=48a1dddc38) | Jun 27, 2021 |
| Intel         | X79 V2.72B                  | Desktop     | [c78b66e96e](https://linux-hardware.org/?probe=c78b66e96e) | Jun 25, 2021 |
| ASUSTek       | N551JX                      | Notebook    | [3ef394cafb](https://linux-hardware.org/?probe=3ef394cafb) | Jun 24, 2021 |
| Toshiba       | PORTEGE R705                | Notebook    | [fe7063735e](https://linux-hardware.org/?probe=fe7063735e) | Jun 24, 2021 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [9d80703f35](https://linux-hardware.org/?probe=9d80703f35) | Jun 23, 2021 |
| Dell          | Inspiron 5459               | Notebook    | [22f31e0de1](https://linux-hardware.org/?probe=22f31e0de1) | Jun 19, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [aa0efa1872](https://linux-hardware.org/?probe=aa0efa1872) | Jun 19, 2021 |
| Toshiba       | PORTEGE R705                | Notebook    | [a53fb9eb09](https://linux-hardware.org/?probe=a53fb9eb09) | Jun 19, 2021 |
| Unknown       | Intel X79                   | Desktop     | [5be1e4c74c](https://linux-hardware.org/?probe=5be1e4c74c) | Jun 18, 2021 |
| Apple         | Mac-F22C86C8                | Mini pc     | [82a162c683](https://linux-hardware.org/?probe=82a162c683) | Jun 18, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [033cd8c9eb](https://linux-hardware.org/?probe=033cd8c9eb) | Jun 17, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [8bb06ce851](https://linux-hardware.org/?probe=8bb06ce851) | Jun 16, 2021 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [d37cfc0abc](https://linux-hardware.org/?probe=d37cfc0abc) | Jun 13, 2021 |
| HP            | Notebook                    | Notebook    | [f1263ec1fc](https://linux-hardware.org/?probe=f1263ec1fc) | Jun 13, 2021 |
| MSI           | 970A-G46                    | Desktop     | [f7b1001ef1](https://linux-hardware.org/?probe=f7b1001ef1) | Jun 13, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [6529cc537c](https://linux-hardware.org/?probe=6529cc537c) | Jun 13, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [2aa173f32b](https://linux-hardware.org/?probe=2aa173f32b) | Jun 12, 2021 |
| Unknown       | Unknown                     | Notebook    | [16d75c0003](https://linux-hardware.org/?probe=16d75c0003) | Jun 11, 2021 |
| Samsung       | 670Z5E                      | Notebook    | [252e20c152](https://linux-hardware.org/?probe=252e20c152) | Jun 11, 2021 |
| Intel         | DZ77GA-70K AAG39009-401     | Desktop     | [a88c5c7685](https://linux-hardware.org/?probe=a88c5c7685) | Jun 09, 2021 |
| Dell          | Inspiron 5567               | Notebook    | [0ffe39ef8d](https://linux-hardware.org/?probe=0ffe39ef8d) | Jun 09, 2021 |
| Sony          | SVE14113ELW                 | Notebook    | [738c72c21c](https://linux-hardware.org/?probe=738c72c21c) | Jun 09, 2021 |
| HP            | ENVY 15                     | Notebook    | [8d7a772e05](https://linux-hardware.org/?probe=8d7a772e05) | Jun 07, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [587e4453b3](https://linux-hardware.org/?probe=587e4453b3) | Jun 04, 2021 |
| Dell          | Precision 5520              | Notebook    | [199dec46c7](https://linux-hardware.org/?probe=199dec46c7) | Jun 01, 2021 |
| HP            | 1000                        | Notebook    | [21fb6389e7](https://linux-hardware.org/?probe=21fb6389e7) | Jun 01, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [4688dc5b46](https://linux-hardware.org/?probe=4688dc5b46) | May 29, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [b1500a1319](https://linux-hardware.org/?probe=b1500a1319) | May 28, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [abc55fc46d](https://linux-hardware.org/?probe=abc55fc46d) | May 28, 2021 |
| Intel         | NUC7i5BNB J31144-309        | Mini pc     | [1761317692](https://linux-hardware.org/?probe=1761317692) | May 28, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [9654da138c](https://linux-hardware.org/?probe=9654da138c) | May 28, 2021 |
| Personal C... | Iris                        | Notebook    | [835df5c61e](https://linux-hardware.org/?probe=835df5c61e) | May 27, 2021 |
| Toshiba       | PORTEGE R705                | Notebook    | [afd83c5750](https://linux-hardware.org/?probe=afd83c5750) | May 25, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [86060380c8](https://linux-hardware.org/?probe=86060380c8) | May 23, 2021 |
| Acer          | Swift SF313-53              | Notebook    | [66e4f1aeff](https://linux-hardware.org/?probe=66e4f1aeff) | May 23, 2021 |
| ASUSTek       | P5K3 Deluxe                 | Desktop     | [458525ba70](https://linux-hardware.org/?probe=458525ba70) | May 22, 2021 |
| Unknown       | Unknown                     | Notebook    | [e9dc8181d8](https://linux-hardware.org/?probe=e9dc8181d8) | May 20, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [5287ceef8d](https://linux-hardware.org/?probe=5287ceef8d) | May 17, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [0be7d156c5](https://linux-hardware.org/?probe=0be7d156c5) | May 17, 2021 |
| Toshiba       | Satellite L45-B             | Notebook    | [544d468137](https://linux-hardware.org/?probe=544d468137) | May 16, 2021 |
| HP            | 435                         | Notebook    | [65bbde1e13](https://linux-hardware.org/?probe=65bbde1e13) | May 16, 2021 |
| HP            | 435                         | Notebook    | [fe5a82cf02](https://linux-hardware.org/?probe=fe5a82cf02) | May 16, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [493edc40c4](https://linux-hardware.org/?probe=493edc40c4) | May 15, 2021 |
| Dell          | 0CN7X8 A04                  | Server      | [e4dee6faf7](https://linux-hardware.org/?probe=e4dee6faf7) | May 15, 2021 |
| Dell          | 0CN7X8 A04                  | Server      | [aa08de711d](https://linux-hardware.org/?probe=aa08de711d) | May 15, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [a98d93888d](https://linux-hardware.org/?probe=a98d93888d) | May 14, 2021 |
| Intel         | YL-3160L2                   | Desktop     | [c282d94246](https://linux-hardware.org/?probe=c282d94246) | May 13, 2021 |
| Dell          | Latitude 7490               | Notebook    | [c533165389](https://linux-hardware.org/?probe=c533165389) | May 13, 2021 |
| Lenovo        | ThinkCentre M55 8808E19     | Desktop     | [a53c13a5c9](https://linux-hardware.org/?probe=a53c13a5c9) | May 12, 2021 |
| MSI           | X58 PLATINUM SLI            | Desktop     | [1fba25dbcf](https://linux-hardware.org/?probe=1fba25dbcf) | May 12, 2021 |
| MSI           | X58 PLATINUM SLI            | Desktop     | [c71715672c](https://linux-hardware.org/?probe=c71715672c) | May 12, 2021 |
| Samsung       | RF712                       | Notebook    | [a3624b29fa](https://linux-hardware.org/?probe=a3624b29fa) | May 11, 2021 |
| Samsung       | RF712                       | Notebook    | [652fb28adb](https://linux-hardware.org/?probe=652fb28adb) | May 11, 2021 |
| Acer          | Swift SF313-53              | Notebook    | [2e4262cb53](https://linux-hardware.org/?probe=2e4262cb53) | May 11, 2021 |
| Dell          | Inspiron 5567               | Notebook    | [aacf9438d2](https://linux-hardware.org/?probe=aacf9438d2) | May 11, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [2196430972](https://linux-hardware.org/?probe=2196430972) | May 09, 2021 |
| Olidata       | Unknown                     | Desktop     | [1dc7094a4d](https://linux-hardware.org/?probe=1dc7094a4d) | May 09, 2021 |
| HP            | 339A                        | Desktop     | [c103096e94](https://linux-hardware.org/?probe=c103096e94) | May 09, 2021 |
| HP            | 339A                        | Desktop     | [1b94801e8b](https://linux-hardware.org/?probe=1b94801e8b) | May 09, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [08d59f23ab](https://linux-hardware.org/?probe=08d59f23ab) | May 09, 2021 |
| Olidata       | Unknown                     | Desktop     | [0c2f6b27a9](https://linux-hardware.org/?probe=0c2f6b27a9) | May 08, 2021 |
| HP            | 1000                        | Notebook    | [4205750e24](https://linux-hardware.org/?probe=4205750e24) | May 08, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [ce41256b96](https://linux-hardware.org/?probe=ce41256b96) | May 07, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [566133628f](https://linux-hardware.org/?probe=566133628f) | May 07, 2021 |
| Toshiba       | Satellite U505              | Notebook    | [50baa8508f](https://linux-hardware.org/?probe=50baa8508f) | May 05, 2021 |
| Toshiba       | Satellite U505              | Notebook    | [c5785176bd](https://linux-hardware.org/?probe=c5785176bd) | May 05, 2021 |
| MSI           | H81M-E33                    | Desktop     | [47447aaec1](https://linux-hardware.org/?probe=47447aaec1) | May 05, 2021 |
| Packard Be... | EasyNote TM98               | Notebook    | [2bb98626e9](https://linux-hardware.org/?probe=2bb98626e9) | May 03, 2021 |
| HUAWEI        | WRTB-WXX9                   | Notebook    | [f9ceb7c523](https://linux-hardware.org/?probe=f9ceb7c523) | May 02, 2021 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [009abcd381](https://linux-hardware.org/?probe=009abcd381) | May 02, 2021 |
| Dell          | Latitude D630               | Notebook    | [40a03f054f](https://linux-hardware.org/?probe=40a03f054f) | May 02, 2021 |
| Acer          | Aspire ES1-431              | Notebook    | [cc8dd98cc6](https://linux-hardware.org/?probe=cc8dd98cc6) | May 01, 2021 |
| HP            | 14                          | Notebook    | [f2874ea965](https://linux-hardware.org/?probe=f2874ea965) | May 01, 2021 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [ef811a6184](https://linux-hardware.org/?probe=ef811a6184) | May 01, 2021 |
| HP            | ENVY 17 Leap Motion SE N... | Notebook    | [18b8d3d480](https://linux-hardware.org/?probe=18b8d3d480) | Apr 30, 2021 |
| HP            | Pavilion dm4                | Notebook    | [dd8938cac1](https://linux-hardware.org/?probe=dd8938cac1) | Apr 29, 2021 |
| Dell          | System Inspiron N4110       | Notebook    | [17b9bc8eb3](https://linux-hardware.org/?probe=17b9bc8eb3) | Apr 27, 2021 |
| HP            | ProBook 430 G3              | Notebook    | [c3acaeb030](https://linux-hardware.org/?probe=c3acaeb030) | Apr 26, 2021 |
| HP            | ProBook 430 G3              | Notebook    | [de3298645e](https://linux-hardware.org/?probe=de3298645e) | Apr 26, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [8ff356e9be](https://linux-hardware.org/?probe=8ff356e9be) | Apr 25, 2021 |
| Chuwi         | Hi10 plus tablet            | Tablet      | [03f22f7870](https://linux-hardware.org/?probe=03f22f7870) | Apr 25, 2021 |
| Gigabyte      | B450M GAMING                | Desktop     | [8ed2b2284e](https://linux-hardware.org/?probe=8ed2b2284e) | Apr 24, 2021 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [9a9bc27310](https://linux-hardware.org/?probe=9a9bc27310) | Apr 23, 2021 |
| Packard Be... | EasyNote_BU45               | Notebook    | [83204d550c](https://linux-hardware.org/?probe=83204d550c) | Apr 19, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0DU0... | Notebook    | [998919a455](https://linux-hardware.org/?probe=998919a455) | Apr 18, 2021 |
| ASUSTek       | P5K SE                      | Desktop     | [73a2ad1fd9](https://linux-hardware.org/?probe=73a2ad1fd9) | Apr 18, 2021 |
| ECS           | MCP61M-M3                   | Desktop     | [2e5b21af19](https://linux-hardware.org/?probe=2e5b21af19) | Apr 17, 2021 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [0761ed6181](https://linux-hardware.org/?probe=0761ed6181) | Apr 16, 2021 |
| Dell          | Latitude 7410               | Notebook    | [7792c66c17](https://linux-hardware.org/?probe=7792c66c17) | Apr 15, 2021 |
| MSI           | H81M-E33                    | Desktop     | [a5ebd5e702](https://linux-hardware.org/?probe=a5ebd5e702) | Apr 13, 2021 |
| ASUSTek       | ROG Zephyrus GX550LXS_GX... | Notebook    | [8eeff8c77c](https://linux-hardware.org/?probe=8eeff8c77c) | Apr 13, 2021 |
| Unknown       | Unknown                     | Desktop     | [a13b6fcbcd](https://linux-hardware.org/?probe=a13b6fcbcd) | Apr 12, 2021 |
| Dell          | Latitude 7400               | Notebook    | [41a2361010](https://linux-hardware.org/?probe=41a2361010) | Apr 11, 2021 |
| Acer          | Aspire ES1-431              | Notebook    | [9109f31570](https://linux-hardware.org/?probe=9109f31570) | Apr 10, 2021 |
| Acer          | Aspire ES1-431              | Notebook    | [df53cbed23](https://linux-hardware.org/?probe=df53cbed23) | Apr 10, 2021 |
| ASUSTek       | PRIME J4005I-C              | Desktop     | [5a1bc2f8fe](https://linux-hardware.org/?probe=5a1bc2f8fe) | Apr 10, 2021 |
| Toshiba       | PORTEGE R705                | Notebook    | [dd16cda442](https://linux-hardware.org/?probe=dd16cda442) | Apr 10, 2021 |
| ASUSTek       | PRIME J4005I-C              | Desktop     | [79f36c06be](https://linux-hardware.org/?probe=79f36c06be) | Apr 09, 2021 |
| ASUSTek       | N46VB                       | Notebook    | [a425e290d7](https://linux-hardware.org/?probe=a425e290d7) | Apr 09, 2021 |
| Personal C... | Iris                        | Notebook    | [add36a3a7c](https://linux-hardware.org/?probe=add36a3a7c) | Apr 09, 2021 |
| Personal C... | Iris                        | Notebook    | [4ec2ee9e6d](https://linux-hardware.org/?probe=4ec2ee9e6d) | Apr 09, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [adb7fbfc0d](https://linux-hardware.org/?probe=adb7fbfc0d) | Apr 08, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [9b9172e5a7](https://linux-hardware.org/?probe=9b9172e5a7) | Apr 08, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U2S... | Notebook    | [3c44770d1a](https://linux-hardware.org/?probe=3c44770d1a) | Apr 07, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U2S... | Notebook    | [3a85124409](https://linux-hardware.org/?probe=3a85124409) | Apr 07, 2021 |
| HP            | ENVY Notebook               | Notebook    | [83a0078309](https://linux-hardware.org/?probe=83a0078309) | Apr 06, 2021 |
| Dell          | Inspiron 5459               | Notebook    | [f3b9205a6c](https://linux-hardware.org/?probe=f3b9205a6c) | Apr 06, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [8e2a8be8ce](https://linux-hardware.org/?probe=8e2a8be8ce) | Apr 06, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [ace9676e8c](https://linux-hardware.org/?probe=ace9676e8c) | Apr 05, 2021 |
| HP            | 15                          | Notebook    | [69d2aa2538](https://linux-hardware.org/?probe=69d2aa2538) | Apr 05, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0DU0... | Notebook    | [8d5f33367e](https://linux-hardware.org/?probe=8d5f33367e) | Apr 04, 2021 |
| Lenovo        | IdeaPad Y480                | Notebook    | [d0aeb8aafc](https://linux-hardware.org/?probe=d0aeb8aafc) | Apr 03, 2021 |
| Foxconn       | G31MV/G31MV-K FAB           | Desktop     | [18047eb612](https://linux-hardware.org/?probe=18047eb612) | Apr 01, 2021 |
| Dell          | Inspiron 3420               | Notebook    | [4d76b6366d](https://linux-hardware.org/?probe=4d76b6366d) | Apr 01, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [742b7afcc8](https://linux-hardware.org/?probe=742b7afcc8) | Apr 01, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [8856c82ed6](https://linux-hardware.org/?probe=8856c82ed6) | Mar 31, 2021 |
| HP            | ENVY 15                     | Notebook    | [31c601923e](https://linux-hardware.org/?probe=31c601923e) | Mar 31, 2021 |
| HP            | ENVY 15                     | Notebook    | [3628d88bc1](https://linux-hardware.org/?probe=3628d88bc1) | Mar 31, 2021 |
| ASUSTek       | P5K SE                      | Desktop     | [fb06c3aee0](https://linux-hardware.org/?probe=fb06c3aee0) | Mar 31, 2021 |
| ASUSTek       | P5K SE                      | Desktop     | [22e69da73a](https://linux-hardware.org/?probe=22e69da73a) | Mar 30, 2021 |
| HP            | 250 G4 Notebook PC          | Notebook    | [e3119c3a18](https://linux-hardware.org/?probe=e3119c3a18) | Mar 30, 2021 |
| HP            | 245 G7 Notebook PC          | Notebook    | [3a4703f85d](https://linux-hardware.org/?probe=3a4703f85d) | Mar 27, 2021 |
| MSI           | 970A-G46                    | Desktop     | [09083497aa](https://linux-hardware.org/?probe=09083497aa) | Mar 26, 2021 |
| MSI           | 970A-G46                    | Desktop     | [dfb535cf31](https://linux-hardware.org/?probe=dfb535cf31) | Mar 26, 2021 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [22e5f1f5df](https://linux-hardware.org/?probe=22e5f1f5df) | Mar 25, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [867936010e](https://linux-hardware.org/?probe=867936010e) | Mar 25, 2021 |
| HP            | 18E9                        | Desktop     | [db74abc8b8](https://linux-hardware.org/?probe=db74abc8b8) | Mar 23, 2021 |
| HP            | 18E9                        | Desktop     | [13bfb17279](https://linux-hardware.org/?probe=13bfb17279) | Mar 23, 2021 |
| HP            | ProLiant ML10               | Desktop     | [1b448e4a71](https://linux-hardware.org/?probe=1b448e4a71) | Mar 23, 2021 |
| HP            | ProLiant ML10               | Desktop     | [cd6b0c3826](https://linux-hardware.org/?probe=cd6b0c3826) | Mar 22, 2021 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [398c74f08f](https://linux-hardware.org/?probe=398c74f08f) | Mar 21, 2021 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [c99084051b](https://linux-hardware.org/?probe=c99084051b) | Mar 21, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [d1bd246775](https://linux-hardware.org/?probe=d1bd246775) | Mar 19, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [1892b65b62](https://linux-hardware.org/?probe=1892b65b62) | Mar 18, 2021 |
| Dell          | Inspiron 14-3467            | Notebook    | [6079a062b3](https://linux-hardware.org/?probe=6079a062b3) | Mar 18, 2021 |
| HP            | 240 G7 Notebook PC          | Notebook    | [669e53f097](https://linux-hardware.org/?probe=669e53f097) | Mar 16, 2021 |
| Dell          | Inspiron 5721               | Notebook    | [0f95174924](https://linux-hardware.org/?probe=0f95174924) | Mar 15, 2021 |
| ASUSTek       | H110M-D                     | Desktop     | [da2dd5ad1a](https://linux-hardware.org/?probe=da2dd5ad1a) | Mar 15, 2021 |
| HP            | Notebook                    | Notebook    | [9c176242dd](https://linux-hardware.org/?probe=9c176242dd) | Mar 14, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [e2e99630ca](https://linux-hardware.org/?probe=e2e99630ca) | Mar 14, 2021 |
| HP            | 15                          | Notebook    | [08b381f369](https://linux-hardware.org/?probe=08b381f369) | Mar 12, 2021 |
| Dell          | Inspiron 14-3467            | Notebook    | [0611d13dff](https://linux-hardware.org/?probe=0611d13dff) | Mar 11, 2021 |
| HP            | ProBook 440 G3              | Notebook    | [fc6181a7c1](https://linux-hardware.org/?probe=fc6181a7c1) | Mar 11, 2021 |
| HP            | ProBook 440 G3              | Notebook    | [38042c5772](https://linux-hardware.org/?probe=38042c5772) | Mar 11, 2021 |
| Toshiba       | PORTEGE R705                | Notebook    | [f537f51a95](https://linux-hardware.org/?probe=f537f51a95) | Mar 09, 2021 |
| ECS           | A740GM-M                    | Desktop     | [442aa41981](https://linux-hardware.org/?probe=442aa41981) | Mar 08, 2021 |
| Intel         | X79 V1.x                    | Desktop     | [2b98f9b956](https://linux-hardware.org/?probe=2b98f9b956) | Mar 08, 2021 |
| Acer          | Aspire 5738                 | Notebook    | [a1a9e12988](https://linux-hardware.org/?probe=a1a9e12988) | Mar 07, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [1f2c6bc8af](https://linux-hardware.org/?probe=1f2c6bc8af) | Mar 05, 2021 |
| MSI           | Stealth 15M A11SEK          | Notebook    | [1187156178](https://linux-hardware.org/?probe=1187156178) | Mar 05, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [76006e9ba5](https://linux-hardware.org/?probe=76006e9ba5) | Mar 01, 2021 |
| Dell          | Inspiron 14-3467            | Notebook    | [7991d50dfd](https://linux-hardware.org/?probe=7991d50dfd) | Mar 01, 2021 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [78e3ef84ba](https://linux-hardware.org/?probe=78e3ef84ba) | Feb 28, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [000cba3fb5](https://linux-hardware.org/?probe=000cba3fb5) | Feb 28, 2021 |
| Unknown       | Unknown                     | Notebook    | [e8359056f7](https://linux-hardware.org/?probe=e8359056f7) | Feb 26, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [485a4f1e98](https://linux-hardware.org/?probe=485a4f1e98) | Feb 25, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [45dfe3c2b1](https://linux-hardware.org/?probe=45dfe3c2b1) | Feb 24, 2021 |
| Unknown       | AD12-B                      | Desktop     | [8167d089b9](https://linux-hardware.org/?probe=8167d089b9) | Feb 20, 2021 |
| Dell          | Vostro V13                  | Notebook    | [f9b40741e7](https://linux-hardware.org/?probe=f9b40741e7) | Feb 19, 2021 |
| Toshiba       | Satellite C845D             | Notebook    | [6a73d1fd72](https://linux-hardware.org/?probe=6a73d1fd72) | Feb 19, 2021 |
| Packard Be... | EasyNote TM85               | Notebook    | [972a7d0f8c](https://linux-hardware.org/?probe=972a7d0f8c) | Feb 17, 2021 |
| MSI           | MS-7267                     | Desktop     | [79cfa785c3](https://linux-hardware.org/?probe=79cfa785c3) | Feb 16, 2021 |
| MSI           | MS-7267                     | Desktop     | [9677e2392c](https://linux-hardware.org/?probe=9677e2392c) | Feb 16, 2021 |
| ASUSTek       | GL502VMK                    | Notebook    | [54b49d2dc7](https://linux-hardware.org/?probe=54b49d2dc7) | Feb 15, 2021 |
| ASUSTek       | GL502VMK                    | Notebook    | [514a434029](https://linux-hardware.org/?probe=514a434029) | Feb 15, 2021 |
| Dell          | Latitude 3440               | Notebook    | [d2806294ef](https://linux-hardware.org/?probe=d2806294ef) | Feb 13, 2021 |
| Unknown       | Unknown                     | Notebook    | [acd23bb798](https://linux-hardware.org/?probe=acd23bb798) | Feb 13, 2021 |
| Sony          | VPCEG15FL                   | Notebook    | [48a16e8a4a](https://linux-hardware.org/?probe=48a16e8a4a) | Feb 10, 2021 |
| Dell          | System Inspiron N411Z       | Notebook    | [eed8ecb624](https://linux-hardware.org/?probe=eed8ecb624) | Feb 08, 2021 |
| Dell          | 0CRH6C A01                  | Desktop     | [31da132ae8](https://linux-hardware.org/?probe=31da132ae8) | Feb 08, 2021 |
| Dell          | 0CRH6C A01                  | Desktop     | [8e9e7ffea0](https://linux-hardware.org/?probe=8e9e7ffea0) | Feb 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd F... | Notebook    | [799c301ad6](https://linux-hardware.org/?probe=799c301ad6) | Feb 08, 2021 |
| Dell          | System Inspiron N411Z       | Notebook    | [f6ea43033f](https://linux-hardware.org/?probe=f6ea43033f) | Feb 07, 2021 |
| Unknown       | AD12-B                      | Desktop     | [6635cbda4d](https://linux-hardware.org/?probe=6635cbda4d) | Feb 06, 2021 |
| Unknown       | AD12-B                      | Desktop     | [05ad299f0e](https://linux-hardware.org/?probe=05ad299f0e) | Feb 06, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [121e3e7d2d](https://linux-hardware.org/?probe=121e3e7d2d) | Feb 02, 2021 |
| Toshiba       | Satellite L745              | Notebook    | [01a4eafbb6](https://linux-hardware.org/?probe=01a4eafbb6) | Feb 02, 2021 |
| Toshiba       | Satellite L745              | Notebook    | [9cc5c245d0](https://linux-hardware.org/?probe=9cc5c245d0) | Feb 02, 2021 |
| HP            | 2ADE                        | Desktop     | [2ee5093250](https://linux-hardware.org/?probe=2ee5093250) | Feb 02, 2021 |
| HP            | 240 G6 Notebook PC          | Notebook    | [2ba1c141b8](https://linux-hardware.org/?probe=2ba1c141b8) | Feb 01, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [3f400fbc08](https://linux-hardware.org/?probe=3f400fbc08) | Jan 31, 2021 |
| ECS           | MCP61M-M3                   | Desktop     | [445f06dbde](https://linux-hardware.org/?probe=445f06dbde) | Jan 29, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [1a8312f66a](https://linux-hardware.org/?probe=1a8312f66a) | Jan 29, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [b024bfc145](https://linux-hardware.org/?probe=b024bfc145) | Jan 29, 2021 |
| ASUSTek       | UX430UNR                    | Notebook    | [e32eec7802](https://linux-hardware.org/?probe=e32eec7802) | Jan 27, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [bf3c21f60b](https://linux-hardware.org/?probe=bf3c21f60b) | Jan 25, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [8289f3c10b](https://linux-hardware.org/?probe=8289f3c10b) | Jan 24, 2021 |
| HP            | Pavilion 15                 | Notebook    | [b83dc673fd](https://linux-hardware.org/?probe=b83dc673fd) | Jan 23, 2021 |
| HP            | 14                          | Notebook    | [7c1ff6f4a8](https://linux-hardware.org/?probe=7c1ff6f4a8) | Jan 22, 2021 |
| Dell          | Vostro 1520                 | Notebook    | [36392e13b5](https://linux-hardware.org/?probe=36392e13b5) | Jan 22, 2021 |
| Intel         | SHARKBAY                    | Desktop     | [c1df3dc860](https://linux-hardware.org/?probe=c1df3dc860) | Jan 21, 2021 |
| IBM           | 813311S                     | Desktop     | [c65634928d](https://linux-hardware.org/?probe=c65634928d) | Jan 20, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [5f648131f5](https://linux-hardware.org/?probe=5f648131f5) | Jan 19, 2021 |
| IBM           | 813311S                     | Desktop     | [9dc5e1fd39](https://linux-hardware.org/?probe=9dc5e1fd39) | Jan 19, 2021 |
| Huanan        | X79 VAA1                    | Desktop     | [d88d20e6fc](https://linux-hardware.org/?probe=d88d20e6fc) | Jan 15, 2021 |
| ASUSTek       | UX310UQK                    | Notebook    | [7006cf4aa0](https://linux-hardware.org/?probe=7006cf4aa0) | Jan 13, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [4b69e8576c](https://linux-hardware.org/?probe=4b69e8576c) | Jan 11, 2021 |
| MSI           | B360M PRO-VH                | Desktop     | [f666aa301e](https://linux-hardware.org/?probe=f666aa301e) | Jan 08, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [7ae430600b](https://linux-hardware.org/?probe=7ae430600b) | Jan 07, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [5d26e74a5d](https://linux-hardware.org/?probe=5d26e74a5d) | Jan 07, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [1ce6d33d5b](https://linux-hardware.org/?probe=1ce6d33d5b) | Jan 07, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [fb8fa788e3](https://linux-hardware.org/?probe=fb8fa788e3) | Jan 07, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [fb56fb77b9](https://linux-hardware.org/?probe=fb56fb77b9) | Jan 07, 2021 |
| HP            | Notebook                    | Notebook    | [38341a3370](https://linux-hardware.org/?probe=38341a3370) | Jan 06, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [724662dec7](https://linux-hardware.org/?probe=724662dec7) | Jan 05, 2021 |
| Sony          | SVE14113ELW                 | Notebook    | [695f68585f](https://linux-hardware.org/?probe=695f68585f) | Jan 05, 2021 |
| Sony          | SVE14113ELW                 | Notebook    | [88ef270eb5](https://linux-hardware.org/?probe=88ef270eb5) | Jan 03, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [019f053a89](https://linux-hardware.org/?probe=019f053a89) | Jan 02, 2021 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [997d30ab91](https://linux-hardware.org/?probe=997d30ab91) | Jan 01, 2021 |
| HP            | Notebook                    | Notebook    | [cf3a2917d1](https://linux-hardware.org/?probe=cf3a2917d1) | Dec 28, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [0a8ed33e62](https://linux-hardware.org/?probe=0a8ed33e62) | Dec 26, 2020 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [74ccd1687d](https://linux-hardware.org/?probe=74ccd1687d) | Dec 24, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [9a02f6b2cf](https://linux-hardware.org/?probe=9a02f6b2cf) | Dec 22, 2020 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [98c8e4f3a6](https://linux-hardware.org/?probe=98c8e4f3a6) | Dec 20, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [680d4771b2](https://linux-hardware.org/?probe=680d4771b2) | Dec 15, 2020 |
| Acer          | Aspire 5738                 | Notebook    | [ad2cafcbe8](https://linux-hardware.org/?probe=ad2cafcbe8) | Dec 13, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [43e55c9de6](https://linux-hardware.org/?probe=43e55c9de6) | Dec 13, 2020 |
| HP            | EliteBook 840r G4           | Notebook    | [ebc64db4ca](https://linux-hardware.org/?probe=ebc64db4ca) | Dec 12, 2020 |
| Acer          | Aspire 5738                 | Notebook    | [f29c073cfb](https://linux-hardware.org/?probe=f29c073cfb) | Dec 11, 2020 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [5783b64146](https://linux-hardware.org/?probe=5783b64146) | Dec 11, 2020 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | Notebook    | [5bae11079c](https://linux-hardware.org/?probe=5bae11079c) | Dec 09, 2020 |
| Toshiba       | Satellite C645              | Notebook    | [0e17d5e680](https://linux-hardware.org/?probe=0e17d5e680) | Dec 09, 2020 |
| Toshiba       | Satellite C645              | Notebook    | [0fcca906f6](https://linux-hardware.org/?probe=0fcca906f6) | Dec 09, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [d9258de65c](https://linux-hardware.org/?probe=d9258de65c) | Dec 09, 2020 |
| Apple         | MacBookPro9,2               | Notebook    | [7469e3af08](https://linux-hardware.org/?probe=7469e3af08) | Dec 08, 2020 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [fd5f6edfb2](https://linux-hardware.org/?probe=fd5f6edfb2) | Dec 08, 2020 |
| Acer          | One S1003                   | Tablet      | [99ca8fdec1](https://linux-hardware.org/?probe=99ca8fdec1) | Dec 04, 2020 |
| HP            | ProBook 440 G7              | Notebook    | [01b2a334c8](https://linux-hardware.org/?probe=01b2a334c8) | Dec 04, 2020 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [38fa279b2b](https://linux-hardware.org/?probe=38fa279b2b) | Dec 04, 2020 |
| Lenovo        | IdeaPad Z400 20201          | Notebook    | [9f4318e1fa](https://linux-hardware.org/?probe=9f4318e1fa) | Dec 03, 2020 |
| Lenovo        | K2450 20243                 | Notebook    | [33409ba105](https://linux-hardware.org/?probe=33409ba105) | Dec 03, 2020 |
| Dell          | Latitude E7470              | Notebook    | [ff5ee269cb](https://linux-hardware.org/?probe=ff5ee269cb) | Dec 01, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [9be5961a82](https://linux-hardware.org/?probe=9be5961a82) | Nov 25, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [2ce0bde22b](https://linux-hardware.org/?probe=2ce0bde22b) | Nov 21, 2020 |
| ASUSTek       | X405UA                      | Notebook    | [e27b62e8d8](https://linux-hardware.org/?probe=e27b62e8d8) | Nov 19, 2020 |
| Lenovo        | K2450 20243                 | Notebook    | [4d44042257](https://linux-hardware.org/?probe=4d44042257) | Nov 19, 2020 |
| HP            | EliteBook 840r G4           | Notebook    | [4782db92e6](https://linux-hardware.org/?probe=4782db92e6) | Nov 19, 2020 |
| Lenovo        | IdeaPad S206 20154          | Notebook    | [393f27acf7](https://linux-hardware.org/?probe=393f27acf7) | Nov 18, 2020 |
| Lenovo        | SDK0F82990 WIN              | All in one  | [824c055b5b](https://linux-hardware.org/?probe=824c055b5b) | Nov 18, 2020 |
| Lenovo        | G400 20235                  | Notebook    | [7cdfc8df41](https://linux-hardware.org/?probe=7cdfc8df41) | Nov 17, 2020 |
| Lenovo        | G400 20235                  | Notebook    | [9d19c00f4e](https://linux-hardware.org/?probe=9d19c00f4e) | Nov 17, 2020 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [df5beb221f](https://linux-hardware.org/?probe=df5beb221f) | Nov 15, 2020 |
| Positivo      | Mobile                      | Notebook    | [87704474ae](https://linux-hardware.org/?probe=87704474ae) | Nov 12, 2020 |
| HP            | 1000                        | Notebook    | [a79972678b](https://linux-hardware.org/?probe=a79972678b) | Nov 10, 2020 |
| Lenovo        | ThinkPad T400 6474AU5       | Notebook    | [1b3d0a7938](https://linux-hardware.org/?probe=1b3d0a7938) | Nov 09, 2020 |
| HP            | 420                         | Notebook    | [8b2ce5df27](https://linux-hardware.org/?probe=8b2ce5df27) | Nov 09, 2020 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [60a084dcdf](https://linux-hardware.org/?probe=60a084dcdf) | Nov 06, 2020 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [2c19015153](https://linux-hardware.org/?probe=2c19015153) | Nov 05, 2020 |
| Unknown       | Unknown                     | Notebook    | [8651ede6c2](https://linux-hardware.org/?probe=8651ede6c2) | Nov 04, 2020 |
| Dell          | XPS 13 9300                 | Notebook    | [764cabc447](https://linux-hardware.org/?probe=764cabc447) | Nov 03, 2020 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [323e8e18f8](https://linux-hardware.org/?probe=323e8e18f8) | Nov 02, 2020 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [237294dbc3](https://linux-hardware.org/?probe=237294dbc3) | Nov 01, 2020 |
| ECS           | A785GM-M                    | Desktop     | [fa61acdd56](https://linux-hardware.org/?probe=fa61acdd56) | Oct 30, 2020 |
| HP            | Pavilion dv4                | Notebook    | [80f9a1311e](https://linux-hardware.org/?probe=80f9a1311e) | Oct 30, 2020 |
| Toshiba       | Satellite C45-A             | Notebook    | [bbfec71882](https://linux-hardware.org/?probe=bbfec71882) | Oct 30, 2020 |
| Lenovo        | SDK0F82990 WIN              | All in one  | [012b6a56ef](https://linux-hardware.org/?probe=012b6a56ef) | Oct 26, 2020 |
| HP            | Laptop 14-cf0xxx            | Notebook    | [5ae192d7e1](https://linux-hardware.org/?probe=5ae192d7e1) | Oct 26, 2020 |
| HP            | Laptop 14-cf0xxx            | Notebook    | [8999670eb2](https://linux-hardware.org/?probe=8999670eb2) | Oct 25, 2020 |
| Acer          | Swift SF314-42              | Notebook    | [628265bca0](https://linux-hardware.org/?probe=628265bca0) | Oct 25, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [e31a805419](https://linux-hardware.org/?probe=e31a805419) | Oct 24, 2020 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [e2a0899961](https://linux-hardware.org/?probe=e2a0899961) | Oct 23, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [e1ac94acb7](https://linux-hardware.org/?probe=e1ac94acb7) | Oct 23, 2020 |
| Lenovo        | IdeaPad S300 20197          | Notebook    | [d03e3dc110](https://linux-hardware.org/?probe=d03e3dc110) | Oct 23, 2020 |
| Intel         | X99                         | Desktop     | [53e51e0b25](https://linux-hardware.org/?probe=53e51e0b25) | Oct 22, 2020 |
| Intel         | X99                         | Desktop     | [194038048f](https://linux-hardware.org/?probe=194038048f) | Oct 22, 2020 |
| Dell          | Latitude E6440              | Notebook    | [46a2699a96](https://linux-hardware.org/?probe=46a2699a96) | Oct 21, 2020 |
| Acer          | Swift SF314-42              | Notebook    | [01143e194b](https://linux-hardware.org/?probe=01143e194b) | Oct 20, 2020 |
| ASUSTek       | X555LB                      | Notebook    | [75ba1f9ee4](https://linux-hardware.org/?probe=75ba1f9ee4) | Oct 19, 2020 |
| Acer          | Aspire E1-531               | Notebook    | [78a57e6fb8](https://linux-hardware.org/?probe=78a57e6fb8) | Oct 13, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [63831d979c](https://linux-hardware.org/?probe=63831d979c) | Oct 06, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [887dc701b4](https://linux-hardware.org/?probe=887dc701b4) | Oct 05, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [eed07ba536](https://linux-hardware.org/?probe=eed07ba536) | Oct 05, 2020 |
| MSI           | B75MA-E33                   | Desktop     | [1616dff15a](https://linux-hardware.org/?probe=1616dff15a) | Oct 04, 2020 |
| Unknown       | Unknown                     | Notebook    | [afc109116d](https://linux-hardware.org/?probe=afc109116d) | Oct 01, 2020 |
| HP            | 530                         | Notebook    | [c330f06c15](https://linux-hardware.org/?probe=c330f06c15) | Sep 30, 2020 |
| Intel         | DH55PJ AAE93812-301         | Desktop     | [f6a0fd4389](https://linux-hardware.org/?probe=f6a0fd4389) | Sep 30, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [ad0d202176](https://linux-hardware.org/?probe=ad0d202176) | Sep 29, 2020 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [6f97a1bc53](https://linux-hardware.org/?probe=6f97a1bc53) | Sep 28, 2020 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [5e196929f0](https://linux-hardware.org/?probe=5e196929f0) | Sep 28, 2020 |
| Lenovo        | ThinkPad T460 20FMS05G4L    | Notebook    | [2934114047](https://linux-hardware.org/?probe=2934114047) | Sep 28, 2020 |
| Dell          | XPS 13 9370                 | Notebook    | [bd632f89ef](https://linux-hardware.org/?probe=bd632f89ef) | Sep 26, 2020 |
| HP            | EliteBook 840r G4           | Notebook    | [2ed34e371e](https://linux-hardware.org/?probe=2ed34e371e) | Sep 26, 2020 |
| Unknown       | Unknown                     | Notebook    | [be59c4d6c4](https://linux-hardware.org/?probe=be59c4d6c4) | Sep 23, 2020 |
| ASUSTek       | F2A55-M LK2                 | Desktop     | [0ad4bcad78](https://linux-hardware.org/?probe=0ad4bcad78) | Sep 23, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [42e3c550cb](https://linux-hardware.org/?probe=42e3c550cb) | Sep 22, 2020 |
| ASUSTek       | X556URK                     | Notebook    | [1c0033b367](https://linux-hardware.org/?probe=1c0033b367) | Sep 20, 2020 |
| ASUSTek       | G55VW                       | Notebook    | [8bfec34af2](https://linux-hardware.org/?probe=8bfec34af2) | Sep 20, 2020 |
| HP            | 245 G5 Notebook PC          | Notebook    | [d2e8cd8f97](https://linux-hardware.org/?probe=d2e8cd8f97) | Sep 15, 2020 |
| HP            | 245 G5 Notebook PC          | Notebook    | [da0f03edfc](https://linux-hardware.org/?probe=da0f03edfc) | Sep 14, 2020 |
| Acer          | Aspire 5542                 | Notebook    | [da115e748b](https://linux-hardware.org/?probe=da115e748b) | Sep 14, 2020 |
| HP            | 2ADE                        | Desktop     | [0ac3191171](https://linux-hardware.org/?probe=0ac3191171) | Sep 10, 2020 |
| HP            | 2ADE                        | Desktop     | [1cf059d943](https://linux-hardware.org/?probe=1cf059d943) | Sep 10, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [1f5bd64812](https://linux-hardware.org/?probe=1f5bd64812) | Sep 09, 2020 |
| HP            | Pavilion 15                 | Notebook    | [df560484b4](https://linux-hardware.org/?probe=df560484b4) | Sep 09, 2020 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [8222d70ff5](https://linux-hardware.org/?probe=8222d70ff5) | Sep 09, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [44782a039e](https://linux-hardware.org/?probe=44782a039e) | Sep 07, 2020 |
| Lenovo        | ThinkPad A485 20MVS0N300    | Notebook    | [6ad17e6cf7](https://linux-hardware.org/?probe=6ad17e6cf7) | Sep 05, 2020 |
| HP            | Notebook                    | Notebook    | [c5d0ec5edb](https://linux-hardware.org/?probe=c5d0ec5edb) | Aug 30, 2020 |
| Acer          | Aspire E1-422               | Notebook    | [a239e53a11](https://linux-hardware.org/?probe=a239e53a11) | Aug 29, 2020 |
| MSI           | H61M-P20                    | Desktop     | [9eafb382df](https://linux-hardware.org/?probe=9eafb382df) | Aug 28, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [02f9010c71](https://linux-hardware.org/?probe=02f9010c71) | Aug 26, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [341b0f6231](https://linux-hardware.org/?probe=341b0f6231) | Aug 24, 2020 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [be74487ec4](https://linux-hardware.org/?probe=be74487ec4) | Aug 23, 2020 |
| HP            | 81C3                        | Desktop     | [d558ddad9e](https://linux-hardware.org/?probe=d558ddad9e) | Aug 22, 2020 |
| Acer          | Aspire ES1-111M             | Notebook    | [fcee1a2241](https://linux-hardware.org/?probe=fcee1a2241) | Aug 21, 2020 |
| Acer          | Aspire ES1-111M             | Notebook    | [43f35553ae](https://linux-hardware.org/?probe=43f35553ae) | Aug 21, 2020 |
| HP            | Pavilion 15                 | Notebook    | [d9c1a66672](https://linux-hardware.org/?probe=d9c1a66672) | Aug 20, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [f6678c3632](https://linux-hardware.org/?probe=f6678c3632) | Aug 17, 2020 |
| Lenovo        | ThinkPad E420 1141DAS       | Notebook    | [ab579f2102](https://linux-hardware.org/?probe=ab579f2102) | Aug 17, 2020 |
| Lenovo        | ThinkPad E420 1141DAS       | Notebook    | [d4beb495bd](https://linux-hardware.org/?probe=d4beb495bd) | Aug 17, 2020 |
| PCPartner     | G43-F71862                  | Desktop     | [6f7db25de0](https://linux-hardware.org/?probe=6f7db25de0) | Aug 12, 2020 |
| Colorful T... | C.Q1900M PRO V20            | Desktop     | [55195790be](https://linux-hardware.org/?probe=55195790be) | Aug 10, 2020 |
| HP            | 82A5                        | Mini pc     | [1840b7c2d6](https://linux-hardware.org/?probe=1840b7c2d6) | Aug 10, 2020 |
| Acer          | Aspire Z1-601               | All in one  | [b3e778a640](https://linux-hardware.org/?probe=b3e778a640) | Aug 08, 2020 |
| AMI           | Cherry Trail CR             | Desktop     | [69e0a22aed](https://linux-hardware.org/?probe=69e0a22aed) | Aug 07, 2020 |
| Gigabyte      | H310M H x.x                 | Desktop     | [8067b679a3](https://linux-hardware.org/?probe=8067b679a3) | Aug 06, 2020 |
| ZOTAC         | ZBOXNANO-AD10               | Mini pc     | [80da000793](https://linux-hardware.org/?probe=80da000793) | Aug 06, 2020 |
| ASUSTek       | FX503VD                     | Notebook    | [26ce95f067](https://linux-hardware.org/?probe=26ce95f067) | Aug 03, 2020 |
| MSI           | H61M-P20                    | Desktop     | [594f095da2](https://linux-hardware.org/?probe=594f095da2) | Aug 02, 2020 |
| HP            | 82DC 1100                   | All in one  | [34270155d0](https://linux-hardware.org/?probe=34270155d0) | Aug 01, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [467112cf04](https://linux-hardware.org/?probe=467112cf04) | Jul 31, 2020 |
| Acer          | One S1003                   | Tablet      | [9a705bc331](https://linux-hardware.org/?probe=9a705bc331) | Jul 30, 2020 |
| HP            | ProBook 440 G3              | Notebook    | [9a34cb7ec7](https://linux-hardware.org/?probe=9a34cb7ec7) | Jul 28, 2020 |
| Acer          | Aspire ES1-572              | Notebook    | [1db75aee39](https://linux-hardware.org/?probe=1db75aee39) | Jul 27, 2020 |
| Acer          | Aspire R3-431T              | Notebook    | [b3bc6f8d90](https://linux-hardware.org/?probe=b3bc6f8d90) | Jul 24, 2020 |
| HP            | Pavilion 15                 | Notebook    | [7410d46ef8](https://linux-hardware.org/?probe=7410d46ef8) | Jul 24, 2020 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [dbb48c14f0](https://linux-hardware.org/?probe=dbb48c14f0) | Jul 22, 2020 |
| HP            | Notebook                    | Notebook    | [431d1d1482](https://linux-hardware.org/?probe=431d1d1482) | Jul 22, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [3216dbc594](https://linux-hardware.org/?probe=3216dbc594) | Jul 18, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [f8c9b50bc3](https://linux-hardware.org/?probe=f8c9b50bc3) | Jul 18, 2020 |
| Sony          | VGN-FW360TJ                 | Notebook    | [8b037cac91](https://linux-hardware.org/?probe=8b037cac91) | Jul 18, 2020 |
| Acer          | One S1003                   | Tablet      | [7cdd981945](https://linux-hardware.org/?probe=7cdd981945) | Jul 16, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [f77f8a2639](https://linux-hardware.org/?probe=f77f8a2639) | Jul 15, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [4afe4f5961](https://linux-hardware.org/?probe=4afe4f5961) | Jul 15, 2020 |
| Dell          | 0GDG8Y A00                  | Desktop     | [a1fb518075](https://linux-hardware.org/?probe=a1fb518075) | Jul 12, 2020 |
| Apple         | MacBookAir7,2               | Notebook    | [f53c9923c4](https://linux-hardware.org/?probe=f53c9923c4) | Jul 11, 2020 |
| Dell          | 0GDG8Y A00                  | Desktop     | [8bb25da515](https://linux-hardware.org/?probe=8bb25da515) | Jul 09, 2020 |
| HP            | Presario CQ43               | Notebook    | [48fe8649ca](https://linux-hardware.org/?probe=48fe8649ca) | Jul 08, 2020 |
| HP            | Presario CQ43               | Notebook    | [db6a9d6546](https://linux-hardware.org/?probe=db6a9d6546) | Jul 06, 2020 |
| HP            | ProBook 4440s               | Notebook    | [48a7e1a88c](https://linux-hardware.org/?probe=48a7e1a88c) | Jul 05, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [bd30f237dd](https://linux-hardware.org/?probe=bd30f237dd) | Jul 05, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [06da0a5ed7](https://linux-hardware.org/?probe=06da0a5ed7) | Jul 05, 2020 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [07a40e042c](https://linux-hardware.org/?probe=07a40e042c) | Jul 02, 2020 |
| Acer          | Aspire ES1-331              | Notebook    | [b154bdb93b](https://linux-hardware.org/?probe=b154bdb93b) | Jul 02, 2020 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [4788e05f08](https://linux-hardware.org/?probe=4788e05f08) | Jul 01, 2020 |
| HP            | ProBook 640 G1              | Notebook    | [1a2462dee7](https://linux-hardware.org/?probe=1a2462dee7) | Jul 01, 2020 |
| Toshiba       | PORTEGE R30-A               | Notebook    | [d33d8295b1](https://linux-hardware.org/?probe=d33d8295b1) | Jun 29, 2020 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [8b9bb2543f](https://linux-hardware.org/?probe=8b9bb2543f) | Jun 28, 2020 |
| Corporativ... | LX4SI                       | Notebook    | [3a15f8865d](https://linux-hardware.org/?probe=3a15f8865d) | Jun 26, 2020 |
| ASUSTek       | X450LN                      | Notebook    | [347ebd88a5](https://linux-hardware.org/?probe=347ebd88a5) | Jun 25, 2020 |
| ASUSTek       | X450LN                      | Notebook    | [10dd68f147](https://linux-hardware.org/?probe=10dd68f147) | Jun 25, 2020 |
| Corporativ... | LX4SI                       | Notebook    | [f9e67e8a5f](https://linux-hardware.org/?probe=f9e67e8a5f) | Jun 25, 2020 |
| HP            | 240 G6 Notebook PC          | Notebook    | [c43e5357b0](https://linux-hardware.org/?probe=c43e5357b0) | Jun 24, 2020 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [ee35b699fa](https://linux-hardware.org/?probe=ee35b699fa) | Jun 24, 2020 |
| Packard Be... | DOT S                       | Notebook    | [d2cd9b2728](https://linux-hardware.org/?probe=d2cd9b2728) | Jun 24, 2020 |
| Lenovo        | IdeaPad 500-14ISK 80NS      | Notebook    | [1af5a3043b](https://linux-hardware.org/?probe=1af5a3043b) | Jun 23, 2020 |
| HP            | ProBook 430 G2              | Notebook    | [d988a74820](https://linux-hardware.org/?probe=d988a74820) | Jun 23, 2020 |
| Lenovo        | IdeaPad 720S-14IKB 80XC     | Notebook    | [0fbefbc62c](https://linux-hardware.org/?probe=0fbefbc62c) | Jun 21, 2020 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [646f93ec3a](https://linux-hardware.org/?probe=646f93ec3a) | Jun 20, 2020 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [08ce018dd0](https://linux-hardware.org/?probe=08ce018dd0) | Jun 20, 2020 |
| Lenovo        | IdeaPad 720S-14IKB 80XC     | Notebook    | [a281f8c305](https://linux-hardware.org/?probe=a281f8c305) | Jun 19, 2020 |
| MSI           | MS-7379                     | Desktop     | [b7f52ad261](https://linux-hardware.org/?probe=b7f52ad261) | Jun 18, 2020 |
| TPV-INVENT... | 2AC6 A01                    | Desktop     | [90725b3c8a](https://linux-hardware.org/?probe=90725b3c8a) | Jun 18, 2020 |
| HP            | 245 G4 Notebook PC          | Notebook    | [4f96cc852f](https://linux-hardware.org/?probe=4f96cc852f) | Jun 18, 2020 |
| HP            | 245 G4 Notebook PC          | Notebook    | [2c0356727d](https://linux-hardware.org/?probe=2c0356727d) | Jun 18, 2020 |
| Dell          | Inspiron 3420               | Notebook    | [5101d0c83c](https://linux-hardware.org/?probe=5101d0c83c) | Jun 17, 2020 |
| Dell          | Inspiron 14-3452            | Notebook    | [c83e4c2dd8](https://linux-hardware.org/?probe=c83e4c2dd8) | Jun 15, 2020 |
| Lenovo        | IdeaPad Z470                | Notebook    | [7167c9a1eb](https://linux-hardware.org/?probe=7167c9a1eb) | Jun 10, 2020 |
| Elo TouchS... | ESY1XDX                     | Desktop     | [64aded4262](https://linux-hardware.org/?probe=64aded4262) | Jun 09, 2020 |
| Packard Be... | ENNS11HR                    | Notebook    | [952d5d4772](https://linux-hardware.org/?probe=952d5d4772) | Jun 05, 2020 |
| HP            | ProBook 4440s               | Notebook    | [730e093bc4](https://linux-hardware.org/?probe=730e093bc4) | Jun 05, 2020 |
| HP            | 0AA8h                       | Desktop     | [2f692488e5](https://linux-hardware.org/?probe=2f692488e5) | Jun 05, 2020 |
| HP            | 0AA8h                       | Desktop     | [1ee6fa5fb7](https://linux-hardware.org/?probe=1ee6fa5fb7) | Jun 03, 2020 |
| HP            | 0AA8h                       | Desktop     | [3226f7a8da](https://linux-hardware.org/?probe=3226f7a8da) | Jun 03, 2020 |
| Acer          | Aspire V5-132               | Notebook    | [44a89c002a](https://linux-hardware.org/?probe=44a89c002a) | Jun 02, 2020 |
| Acer          | Aspire V5-132               | Notebook    | [5b82f8d7d3](https://linux-hardware.org/?probe=5b82f8d7d3) | Jun 02, 2020 |
| Elo TouchS... | ESY1XDX                     | Desktop     | [467adf2413](https://linux-hardware.org/?probe=467adf2413) | Jun 01, 2020 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [fbccea1bb2](https://linux-hardware.org/?probe=fbccea1bb2) | May 29, 2020 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [6661e20292](https://linux-hardware.org/?probe=6661e20292) | May 28, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X420... | Notebook    | [9a867c7a5b](https://linux-hardware.org/?probe=9a867c7a5b) | May 28, 2020 |
| Dell          | Latitude E7450              | Notebook    | [c3eab25bca](https://linux-hardware.org/?probe=c3eab25bca) | May 28, 2020 |
| Gigabyte      | GA-MA790FX-DS5              | Desktop     | [bc3ed232f3](https://linux-hardware.org/?probe=bc3ed232f3) | May 28, 2020 |
| Clevo         | W240HU/W250HUQ              | Notebook    | [9fac55b56b](https://linux-hardware.org/?probe=9fac55b56b) | May 28, 2020 |
| Clevo         | W240HU/W250HUQ              | Notebook    | [9403cfc9c4](https://linux-hardware.org/?probe=9403cfc9c4) | May 27, 2020 |
| Clevo         | W240HU/W250HUQ              | Notebook    | [216a9db389](https://linux-hardware.org/?probe=216a9db389) | May 27, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [38e63a05e2](https://linux-hardware.org/?probe=38e63a05e2) | May 26, 2020 |
| Dell          | Inspiron 14-3452            | Notebook    | [f894499ac3](https://linux-hardware.org/?probe=f894499ac3) | May 26, 2020 |
| HP            | OMEN by Laptop              | Notebook    | [6cea5aa3fd](https://linux-hardware.org/?probe=6cea5aa3fd) | May 26, 2020 |
| HP            | OMEN by Laptop              | Notebook    | [a621749c2d](https://linux-hardware.org/?probe=a621749c2d) | May 26, 2020 |
| Acer          | ES1-111M                    | Notebook    | [53e45e403c](https://linux-hardware.org/?probe=53e45e403c) | May 23, 2020 |
| Olidata       | Unknown                     | Desktop     | [4d13b52bae](https://linux-hardware.org/?probe=4d13b52bae) | May 23, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [9216a7cd89](https://linux-hardware.org/?probe=9216a7cd89) | May 21, 2020 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [fae71925c5](https://linux-hardware.org/?probe=fae71925c5) | May 21, 2020 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [aa6df4c02b](https://linux-hardware.org/?probe=aa6df4c02b) | May 21, 2020 |
| Acer          | Aspire 4739Z                | Notebook    | [f51ee0fe5a](https://linux-hardware.org/?probe=f51ee0fe5a) | May 20, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [910d27523a](https://linux-hardware.org/?probe=910d27523a) | May 20, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [ffe1142072](https://linux-hardware.org/?probe=ffe1142072) | May 19, 2020 |
| Acer          | Aspire A114-32              | Notebook    | [35ddb37c29](https://linux-hardware.org/?probe=35ddb37c29) | May 17, 2020 |
| Acer          | Aspire E5-551G              | Notebook    | [cda77789ec](https://linux-hardware.org/?probe=cda77789ec) | May 17, 2020 |
| Acer          | Aspire E5-551G              | Notebook    | [ee3ddbe726](https://linux-hardware.org/?probe=ee3ddbe726) | May 17, 2020 |
| Dell          | Latitude E6420              | Notebook    | [46a7b9904a](https://linux-hardware.org/?probe=46a7b9904a) | May 17, 2020 |
| Dell          | Latitude E6420              | Notebook    | [15d9716666](https://linux-hardware.org/?probe=15d9716666) | May 17, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [55850d2bd2](https://linux-hardware.org/?probe=55850d2bd2) | May 17, 2020 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [f170547556](https://linux-hardware.org/?probe=f170547556) | May 16, 2020 |
| Dell          | Inspiron 14-3452            | Notebook    | [65292593ee](https://linux-hardware.org/?probe=65292593ee) | May 15, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Chile/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 102       | 11.67%  |
| Ubuntu 18.04                 | 74        | 8.47%   |
| Ubuntu 22.04                 | 30        | 3.43%   |
| Arch                         | 23        | 2.63%   |
| Ubuntu 19.04                 | 22        | 2.52%   |
| OpenMandriva 4.3             | 22        | 2.52%   |
| OpenMandriva 4.2             | 21        | 2.4%    |
| Manjaro                      | 19        | 2.17%   |
| Zorin 16                     | 18        | 2.06%   |
| Pop!_OS 22.04                | 18        | 2.06%   |
| Debian 11                    | 18        | 2.06%   |
| Debian 10                    | 17        | 1.95%   |
| Fedora 34                    | 16        | 1.83%   |
| Linux Mint 20.1              | 15        | 1.72%   |
| KDE neon 20.04               | 15        | 1.72%   |
| Fedora 35                    | 15        | 1.72%   |
| Zorin 15                     | 14        | 1.6%    |
| Arch Rolling                 | 14        | 1.6%    |
| Pop!_OS 20.04                | 13        | 1.49%   |
| OpenMandriva 23.01           | 13        | 1.49%   |
| Ubuntu 19.10                 | 12        | 1.37%   |
| Ubuntu 21.10                 | 11        | 1.26%   |
| Ubuntu 20.10                 | 11        | 1.26%   |
| Fedora 37                    | 11        | 1.26%   |
| Fedora 32                    | 11        | 1.26%   |
| Fedora 36                    | 10        | 1.14%   |
| Fedora 33                    | 10        | 1.14%   |
| Debian Testing               | 10        | 1.14%   |
| Ubuntu 21.04                 | 9         | 1.03%   |
| Pop!_OS 20.10                | 8         | 0.92%   |
| openSUSE Tumbleweed-XXXXXXXX | 8         | 0.92%   |
| Linux Mint 19.3              | 8         | 0.92%   |
| Ubuntu 22.10                 | 7         | 0.8%    |
| ROSA R10                     | 7         | 0.8%    |
| Linux Mint 21                | 7         | 0.8%    |
| Linux Mint 20                | 7         | 0.8%    |
| Elementary 6.1               | 7         | 0.8%    |
| ArcoLinux Rolling            | 7         | 0.8%    |
| Ubuntu 18.10                 | 6         | 0.69%   |
| Linux Mint 21.1              | 6         | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu            | 282       | 33.85%  |
| Fedora            | 66        | 7.92%   |
| Linux Mint        | 61        | 7.32%   |
| OpenMandriva      | 59        | 7.08%   |
| Debian            | 46        | 5.52%   |
| Pop!_OS           | 44        | 5.28%   |
| Arch              | 34        | 4.08%   |
| Zorin             | 33        | 3.96%   |
| Manjaro           | 28        | 3.36%   |
| KDE neon          | 25        | 3%      |
| ROSA              | 14        | 1.68%   |
| Kubuntu           | 13        | 1.56%   |
| Elementary        | 12        | 1.44%   |
| Xubuntu           | 10        | 1.2%    |
| openSUSE          | 8         | 0.96%   |
| Ubuntu MATE       | 7         | 0.84%   |
| Endless           | 7         | 0.84%   |
| ArcoLinux         | 7         | 0.84%   |
| Lubuntu           | 6         | 0.72%   |
| Ubuntu Budgie     | 5         | 0.6%    |
| Nobara            | 5         | 0.6%    |
| Kali              | 5         | 0.6%    |
| Clear Linux       | 5         | 0.6%    |
| LMDE              | 4         | 0.48%   |
| Deepin            | 4         | 0.48%   |
| Ubuntu Unity      | 3         | 0.36%   |
| RHEL              | 3         | 0.36%   |
| Parrot            | 3         | 0.36%   |
| Gentoo            | 3         | 0.36%   |
| Ultramarine Linux | 2         | 0.24%   |
| SteamOS           | 2         | 0.24%   |
| Solus             | 2         | 0.24%   |
| Slackware         | 2         | 0.24%   |
| MX                | 2         | 0.24%   |
| LinuxFX           | 2         | 0.24%   |
| Linux Lite        | 2         | 0.24%   |
| GNOME OS          | 2         | 0.24%   |
| EndeavourOS       | 2         | 0.24%   |
| CentOS            | 2         | 0.24%   |
| Xero              | 1         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003         | 22        | 2.31%   |
| 5.10.14-desktop-1omv4002        | 19        | 2%      |
| 5.4.0-42-generic                | 13        | 1.37%   |
| 6.1.1-desktop-1omv2290          | 12        | 1.26%   |
| 5.4.0-26-generic                | 9         | 0.95%   |
| 5.15.0-56-generic               | 9         | 0.95%   |
| 5.0.0-13-generic                | 9         | 0.95%   |
| 5.8.0-50-generic                | 8         | 0.84%   |
| 5.8.0-48-generic                | 8         | 0.84%   |
| 5.4.0-58-generic                | 8         | 0.84%   |
| 5.15.0-58-generic               | 8         | 0.84%   |
| 5.4.0-48-generic                | 7         | 0.74%   |
| 5.4.0-47-generic                | 7         | 0.74%   |
| 5.15.0-48-generic               | 7         | 0.74%   |
| 5.11.0-27-generic               | 7         | 0.74%   |
| 5.0.0-23-generic                | 7         | 0.74%   |
| 4.18.0-15-generic               | 7         | 0.74%   |
| 5.4.0-56-generic                | 6         | 0.63%   |
| 5.4.0-52-generic                | 6         | 0.63%   |
| 5.4.0-29-generic                | 6         | 0.63%   |
| 5.15.0-52-generic               | 6         | 0.63%   |
| 5.15.0-41-generic               | 6         | 0.63%   |
| 5.11.0-37-generic               | 6         | 0.63%   |
| 5.4.0-77-generic                | 5         | 0.53%   |
| 5.4.0-72-generic                | 5         | 0.53%   |
| 5.4.0-37-generic                | 5         | 0.53%   |
| 5.4.0-33-generic                | 5         | 0.53%   |
| 5.3.0-53-generic                | 5         | 0.53%   |
| 5.3.0-46-generic                | 5         | 0.53%   |
| 5.3.0-42-generic                | 5         | 0.53%   |
| 5.19.0-35-generic               | 5         | 0.53%   |
| 5.15.0-60-generic               | 5         | 0.53%   |
| 5.15.0-46-generic               | 5         | 0.53%   |
| 5.15.0-43-generic               | 5         | 0.53%   |
| 5.13.0-30-generic               | 5         | 0.53%   |
| 5.11.0-7614-generic             | 5         | 0.53%   |
| 5.0.0-32-generic                | 5         | 0.53%   |
| 5.0.0-27-generic                | 5         | 0.53%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 5         | 0.53%   |
| 4.18.0-18-generic               | 5         | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 151       | 16.76%  |
| 5.15.0  | 68        | 7.55%   |
| 5.8.0   | 49        | 5.44%   |
| 5.11.0  | 49        | 5.44%   |
| 5.0.0   | 45        | 4.99%   |
| 4.15.0  | 41        | 4.55%   |
| 5.3.0   | 38        | 4.22%   |
| 5.13.0  | 30        | 3.33%   |
| 4.18.0  | 27        | 3%      |
| 5.16.7  | 22        | 2.44%   |
| 5.19.0  | 21        | 2.33%   |
| 5.10.0  | 20        | 2.22%   |
| 5.10.14 | 19        | 2.11%   |
| 6.1.1   | 15        | 1.66%   |
| 4.19.0  | 13        | 1.44%   |
| 5.14.0  | 12        | 1.33%   |
| 6.0.0   | 8         | 0.89%   |
| 5.9.16  | 6         | 0.67%   |
| 4.9.60  | 6         | 0.67%   |
| 5.17.5  | 5         | 0.55%   |
| 5.8.12  | 4         | 0.44%   |
| 5.18.10 | 4         | 0.44%   |
| 5.16.11 | 4         | 0.44%   |
| 5.13.13 | 4         | 0.44%   |
| 5.12.0  | 4         | 0.44%   |
| 6.1.11  | 3         | 0.33%   |
| 6.0.12  | 3         | 0.33%   |
| 5.9.1   | 3         | 0.33%   |
| 5.5.0   | 3         | 0.33%   |
| 5.19.12 | 3         | 0.33%   |
| 5.18.0  | 3         | 0.33%   |
| 5.17.4  | 3         | 0.33%   |
| 5.17.3  | 3         | 0.33%   |
| 5.17.13 | 3         | 0.33%   |
| 5.13.19 | 3         | 0.33%   |
| 5.13.12 | 3         | 0.33%   |
| 5.11.6  | 3         | 0.33%   |
| 5.11.12 | 3         | 0.33%   |
| 5.11.10 | 3         | 0.33%   |
| 4.4.0   | 3         | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 157       | 17.62%  |
| 5.15    | 79        | 8.87%   |
| 5.11    | 66        | 7.41%   |
| 5.10    | 61        | 6.85%   |
| 5.8     | 54        | 6.06%   |
| 5.0     | 48        | 5.39%   |
| 5.13    | 46        | 5.16%   |
| 5.19    | 41        | 4.6%    |
| 4.15    | 41        | 4.6%    |
| 5.3     | 40        | 4.49%   |
| 5.16    | 36        | 4.04%   |
| 6.1     | 32        | 3.59%   |
| 4.18    | 28        | 3.14%   |
| 5.17    | 21        | 2.36%   |
| 6.0     | 20        | 2.24%   |
| 5.14    | 20        | 2.24%   |
| 5.9     | 16        | 1.8%    |
| 5.12    | 16        | 1.8%    |
| 4.19    | 14        | 1.57%   |
| 5.18    | 13        | 1.46%   |
| 4.9     | 10        | 1.12%   |
| 5.6     | 7         | 0.79%   |
| 5.5     | 6         | 0.67%   |
| 6.2     | 5         | 0.56%   |
| 5.7     | 4         | 0.45%   |
| 4.4     | 4         | 0.45%   |
| 5.1     | 3         | 0.34%   |
| 4.13    | 1         | 0.11%   |
| 3.10    | 1         | 0.11%   |
| Unknown | 1         | 0.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 787       | 97.28%  |
| i686    | 20        | 2.47%   |
| aarch64 | 1         | 0.12%   |
| Unknown | 1         | 0.12%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 370       | 44.21%  |
| KDE5            | 136       | 16.25%  |
| Unknown         | 109       | 13.02%  |
| XFCE            | 51        | 6.09%   |
| X-Cinnamon      | 51        | 6.09%   |
| KDE             | 29        | 3.46%   |
| MATE            | 15        | 1.79%   |
| Pantheon        | 12        | 1.43%   |
| KDE4            | 10        | 1.19%   |
| Budgie          | 10        | 1.19%   |
| i3              | 8         | 0.96%   |
| Cinnamon        | 7         | 0.84%   |
| LXQt            | 5         | 0.6%    |
| Deepin          | 5         | 0.6%    |
| Unity           | 3         | 0.36%   |
| LXDE            | 3         | 0.36%   |
| GNOME Flashback | 3         | 0.36%   |
| awesome         | 3         | 0.36%   |
| xmonad          | 2         | 0.24%   |
| qtile           | 2         | 0.24%   |
| Trinity         | 1         | 0.12%   |
| icewm           | 1         | 0.12%   |
| bspwm           | 1         | 0.12%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 630       | 75.81%  |
| Wayland | 130       | 15.64%  |
| Unknown | 66        | 7.94%   |
| Tty     | 5         | 0.6%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 483       | 57.84%  |
| SDDM    | 111       | 13.29%  |
| GDM     | 95        | 11.38%  |
| LightDM | 52        | 6.23%   |
| GDM3    | 52        | 6.23%   |
| TDM     | 26        | 3.11%   |
| KDM     | 10        | 1.2%    |
| XDM     | 4         | 0.48%   |
| SLIMSKI | 1         | 0.12%   |
| LXDM    | 1         | 0.12%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| es_CL      | 427       | 51.57%  |
| en_US      | 182       | 21.98%  |
| Unknown    | 112       | 13.53%  |
| es_ES      | 48        | 5.8%    |
| en_GB      | 15        | 1.81%   |
| es_MX      | 14        | 1.69%   |
| C          | 9         | 1.09%   |
| fr_FR      | 2         | 0.24%   |
| es_VE      | 2         | 0.24%   |
| es_UY      | 2         | 0.24%   |
| es_BO      | 2         | 0.24%   |
| es_AR      | 2         | 0.24%   |
| en_CA      | 2         | 0.24%   |
| de_DE      | 2         | 0.24%   |
| ru_RU      | 1         | 0.12%   |
| pt_BR      | 1         | 0.12%   |
| nl_NL      | 1         | 0.12%   |
| es_CO      | 1         | 0.12%   |
| es_CL.UTF8 | 1         | 0.12%   |
| en_AG      | 1         | 0.12%   |
| arn_CL     | 1         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 428       | 52.13%  |
| BIOS | 393       | 47.87%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 644       | 77.97%  |
| Btrfs   | 73        | 8.84%   |
| Overlay | 52        | 6.3%    |
| Unknown | 40        | 4.84%   |
| Xfs     | 9         | 1.09%   |
| Ext2    | 4         | 0.48%   |
| Zfs     | 3         | 0.36%   |
| Ext3    | 1         | 0.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 509       | 60.96%  |
| GPT     | 255       | 30.54%  |
| MBR     | 71        | 8.5%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 738       | 89.67%  |
| Yes       | 85        | 10.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 580       | 70.05%  |
| Yes       | 248       | 29.95%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| Hewlett-Packard           | 192       | 23.76%  |
| ASUSTek Computer          | 130       | 16.09%  |
| Lenovo                    | 106       | 13.12%  |
| Dell                      | 67        | 8.29%   |
| Acer                      | 54        | 6.68%   |
| MSI                       | 44        | 5.45%   |
| Samsung Electronics       | 25        | 3.09%   |
| Gigabyte Technology       | 22        | 2.72%   |
| Toshiba                   | 19        | 2.35%   |
| Intel                     | 18        | 2.23%   |
| Apple                     | 17        | 2.1%    |
| Sony                      | 14        | 1.73%   |
| ECS                       | 10        | 1.24%   |
| Unknown                   | 9         | 1.11%   |
| Packard Bell              | 8         | 0.99%   |
| HUAWEI                    | 6         | 0.74%   |
| ASRock                    | 6         | 0.74%   |
| Pegatron                  | 4         | 0.5%    |
| Huanan                    | 4         | 0.5%    |
| Google                    | 4         | 0.5%    |
| Chuwi                     | 3         | 0.37%   |
| AMI                       | 3         | 0.37%   |
| Valve                     | 2         | 0.25%   |
| TPV-INVENTA               | 2         | 0.25%   |
| MACHINIST                 | 2         | 0.25%   |
| HC                        | 2         | 0.25%   |
| ZOTAC                     | 1         | 0.12%   |
| ViewSonic                 | 1         | 0.12%   |
| SZMZ                      | 1         | 0.12%   |
| Supermicro                | 1         | 0.12%   |
| SK hynix                  | 1         | 0.12%   |
| Render                    | 1         | 0.12%   |
| Raspberry Pi Foundation   | 1         | 0.12%   |
| R-StyleComputers          | 1         | 0.12%   |
| Quanta                    | 1         | 0.12%   |
| Positivo                  | 1         | 0.12%   |
| Personal Computer Factory | 1         | 0.12%   |
| PCPartner                 | 1         | 0.12%   |
| OX                        | 1         | 0.12%   |
| Olidata                   | 1         | 0.12%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Unknown                                 | 14        | 1.73%   |
| HP Notebook                             | 10        | 1.24%   |
| HP Pavilion Notebook                    | 7         | 0.87%   |
| HP 240 G6 Notebook PC                   | 6         | 0.74%   |
| ASUS All Series                         | 6         | 0.74%   |
| MSI MS-7817                             | 5         | 0.62%   |
| HP Pavilion Laptop 15-cw1xxx            | 5         | 0.62%   |
| HP Pavilion 15                          | 5         | 0.62%   |
| ASUS ZenBook UX325EA_UX325EA            | 5         | 0.62%   |
| HP Pavilion Laptop 15-eh0xxx            | 4         | 0.5%    |
| HP ENVY 15                              | 4         | 0.5%    |
| HP 14                                   | 4         | 0.5%    |
| ASUS PRIME B450M-A                      | 4         | 0.5%    |
| ASUS PRIME A320M-K                      | 4         | 0.5%    |
| Acer Aspire ES1-111M                    | 4         | 0.5%    |
| MSI MS-7A34                             | 3         | 0.37%   |
| MSI MS-7788                             | 3         | 0.37%   |
| Lenovo Legion Y530-15ICH 81FV           | 3         | 0.37%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK   | 3         | 0.37%   |
| HUAWEI BOHK-WAX9X                       | 3         | 0.37%   |
| HP ProBook 440 G3                       | 3         | 0.37%   |
| HP Pavilion Laptop 15-cw0xxx            | 3         | 0.37%   |
| HP Pavilion g4                          | 3         | 0.37%   |
| HP ENVY x360 Convertible 13-ag0xxx      | 3         | 0.37%   |
| HP EliteBook 840 G6                     | 3         | 0.37%   |
| HP EliteBook 2560p                      | 3         | 0.37%   |
| HP 15                                   | 3         | 0.37%   |
| HP 1000                                 | 3         | 0.37%   |
| Google Treeya                           | 3         | 0.37%   |
| Dell Latitude E6420                     | 3         | 0.37%   |
| Dell Inspiron 14-3467                   | 3         | 0.37%   |
| ASUS ZenBook UX433FN_UX433FN            | 3         | 0.37%   |
| ASUS TUF Gaming FX505DT_FX505DT         | 3         | 0.37%   |
| ASUS TUF Gaming B450M-PLUS II           | 3         | 0.37%   |
| ASUS ASUS BR1100CKA BR1100CKA_BR1100CKA | 3         | 0.37%   |
| Apple MacBookPro9,2                     | 3         | 0.37%   |
| Apple MacBookAir7,2                     | 3         | 0.37%   |
| Valve Jupiter                           | 2         | 0.25%   |
| Toshiba Satellite L745                  | 2         | 0.25%   |
| Toshiba Satellite L515                  | 2         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| HP Pavilion           | 50        | 6.19%   |
| Acer Aspire           | 41        | 5.07%   |
| Lenovo ThinkPad       | 40        | 4.95%   |
| Lenovo IdeaPad        | 37        | 4.58%   |
| Dell Inspiron         | 26        | 3.22%   |
| HP EliteBook          | 17        | 2.1%    |
| ASUS VivoBook         | 17        | 2.1%    |
| Dell Latitude         | 16        | 1.98%   |
| HP ENVY               | 15        | 1.86%   |
| ASUS TUF              | 15        | 1.86%   |
| ASUS PRIME            | 15        | 1.86%   |
| Toshiba Satellite     | 14        | 1.73%   |
| HP ProBook            | 14        | 1.73%   |
| Unknown               | 14        | 1.73%   |
| ASUS ZenBook          | 12        | 1.49%   |
| HP Laptop             | 11        | 1.36%   |
| HP Notebook           | 10        | 1.24%   |
| HP 240                | 10        | 1.24%   |
| HP Compaq             | 9         | 1.11%   |
| ASUS ASUS             | 8         | 0.99%   |
| Acer Swift            | 8         | 0.99%   |
| Packard Bell EasyNote | 6         | 0.74%   |
| Lenovo Legion         | 6         | 0.74%   |
| HP 245                | 6         | 0.74%   |
| Dell Precision        | 6         | 0.74%   |
| ASUS All              | 6         | 0.74%   |
| MSI MS-7817           | 5         | 0.62%   |
| Lenovo ThinkCentre    | 5         | 0.62%   |
| HP 250                | 5         | 0.62%   |
| Dell Vostro           | 5         | 0.62%   |
| HP ProDesk            | 4         | 0.5%    |
| HP Presario           | 4         | 0.5%    |
| HP OMEN               | 4         | 0.5%    |
| HP 14                 | 4         | 0.5%    |
| Dell OptiPlex         | 4         | 0.5%    |
| ASUS ROG              | 4         | 0.5%    |
| ASUS M5A78L-M         | 4         | 0.5%    |
| Toshiba PORTEGE       | 3         | 0.37%   |
| Samsung R430          | 3         | 0.37%   |
| Samsung 300E5EV       | 3         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 86        | 10.64%  |
| 2017    | 79        | 9.78%   |
| 2018    | 75        | 9.28%   |
| 2019    | 73        | 9.03%   |
| 2013    | 63        | 7.8%    |
| 2012    | 63        | 7.8%    |
| 2011    | 61        | 7.55%   |
| 2014    | 50        | 6.19%   |
| 2016    | 49        | 6.06%   |
| 2015    | 42        | 5.2%    |
| 2021    | 37        | 4.58%   |
| 2010    | 34        | 4.21%   |
| 2008    | 27        | 3.34%   |
| 2007    | 25        | 3.09%   |
| 2009    | 23        | 2.85%   |
| 2022    | 16        | 1.98%   |
| 2006    | 3         | 0.37%   |
| 2005    | 1         | 0.12%   |
| Unknown | 1         | 0.12%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 549       | 67.95%  |
| Desktop        | 215       | 26.61%  |
| Convertible    | 16        | 1.98%   |
| Mini pc        | 9         | 1.11%   |
| All in one     | 9         | 1.11%   |
| Tablet         | 6         | 0.74%   |
| Server         | 3         | 0.37%   |
| System on chip | 1         | 0.12%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 740       | 90.8%   |
| Enabled  | 75        | 9.2%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 804       | 99.5%   |
| Yes  | 4         | 0.5%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 219       | 26.74%  |
| 3.01-4.0    | 181       | 22.1%   |
| 8.01-16.0   | 162       | 19.78%  |
| 16.01-24.0  | 125       | 15.26%  |
| 32.01-64.0  | 49        | 5.98%   |
| 1.01-2.0    | 44        | 5.37%   |
| 24.01-32.0  | 15        | 1.83%   |
| 2.01-3.0    | 15        | 1.83%   |
| 64.01-256.0 | 6         | 0.73%   |
| 0.51-1.0    | 2         | 0.24%   |
| Unknown     | 1         | 0.12%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 326       | 36.59%  |
| 2.01-3.0   | 224       | 25.14%  |
| 3.01-4.0   | 137       | 15.38%  |
| 4.01-8.0   | 122       | 13.69%  |
| 0.51-1.0   | 44        | 4.94%   |
| 8.01-16.0  | 29        | 3.25%   |
| 0.01-0.5   | 5         | 0.56%   |
| 16.01-24.0 | 2         | 0.22%   |
| 24.01-32.0 | 1         | 0.11%   |
| Unknown    | 1         | 0.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 546       | 66.1%   |
| 2      | 198       | 23.97%  |
| 3      | 44        | 5.33%   |
| 4      | 22        | 2.66%   |
| 0      | 7         | 0.85%   |
| 5      | 6         | 0.73%   |
| 7      | 2         | 0.24%   |
| 6      | 1         | 0.12%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 548       | 67.24%  |
| Yes       | 267       | 32.76%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 694       | 85.78%  |
| No        | 115       | 14.22%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 681       | 84.07%  |
| No        | 129       | 15.93%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 530       | 64.79%  |
| No        | 288       | 35.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Chile   | 808       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Santiago            | 257       | 30.16%  |
| Viña del Mar       | 37        | 4.34%   |
| Las Condes          | 35        | 4.11%   |
| Maipu               | 32        | 3.76%   |
| Concepción         | 31        | 3.64%   |
| Puente Alto         | 29        | 3.4%    |
| Nunoa               | 21        | 2.46%   |
| La Florida          | 21        | 2.46%   |
| Temuco              | 20        | 2.35%   |
| Providencia         | 19        | 2.23%   |
| Valdivia            | 15        | 1.76%   |
| San Miguel          | 15        | 1.76%   |
| Antofagasta         | 14        | 1.64%   |
| La Serena           | 13        | 1.53%   |
| Port Montt          | 11        | 1.29%   |
| Valparaíso         | 10        | 1.17%   |
| Quilpué            | 9         | 1.06%   |
| Iquique             | 9         | 1.06%   |
| Coronel             | 9         | 1.06%   |
| Talcahuano          | 8         | 0.94%   |
| Rancagua            | 8         | 0.94%   |
| Osorno              | 8         | 0.94%   |
| Coquimbo            | 8         | 0.94%   |
| Los Ángeles        | 7         | 0.82%   |
| Colina              | 7         | 0.82%   |
| San Pedro de la Paz | 6         | 0.7%    |
| Penalolen           | 6         | 0.7%    |
| Curicó             | 6         | 0.7%    |
| Chillan             | 6         | 0.7%    |
| Central             | 6         | 0.7%    |
| Vitacura            | 5         | 0.59%   |
| San Bernardo        | 5         | 0.59%   |
| Quilicura           | 5         | 0.59%   |
| La Reina            | 5         | 0.59%   |
| El Bosque           | 5         | 0.59%   |
| Copiapó            | 5         | 0.59%   |
| Arica               | 5         | 0.59%   |
| Villa Alemana       | 4         | 0.47%   |
| Recoleta            | 4         | 0.47%   |
| Punta Arenas        | 4         | 0.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 208       | 303    | 19.07%  |
| Seagate                     | 154       | 210    | 14.12%  |
| Toshiba                     | 104       | 120    | 9.53%   |
| Kingston                    | 93        | 132    | 8.52%   |
| Samsung Electronics         | 88        | 120    | 8.07%   |
| Crucial                     | 68        | 84     | 6.23%   |
| Unknown                     | 53        | 75     | 4.86%   |
| SanDisk                     | 42        | 48     | 3.85%   |
| Hitachi                     | 42        | 50     | 3.85%   |
| HGST                        | 28        | 29     | 2.57%   |
| SK hynix                    | 27        | 32     | 2.47%   |
| Intel                       | 23        | 37     | 2.11%   |
| Micron Technology           | 15        | 21     | 1.37%   |
| Apple                       | 14        | 14     | 1.28%   |
| China                       | 12        | 16     | 1.1%    |
| KingSpec                    | 10        | 18     | 0.92%   |
| Silicon Motion              | 9         | 9      | 0.82%   |
| KIOXIA                      | 8         | 12     | 0.73%   |
| JMicron Technology          | 6         | 6      | 0.55%   |
| Corsair                     | 6         | 11     | 0.55%   |
| XPG                         | 5         | 11     | 0.46%   |
| Micron/Crucial Technology   | 5         | 9      | 0.46%   |
| Lexar                       | 5         | 10     | 0.46%   |
| A-DATA Technology           | 5         | 7      | 0.46%   |
| XrayDisk                    | 4         | 4      | 0.37%   |
| Kingston Technology Company | 4         | 4      | 0.37%   |
| SSSTC                       | 3         | 3      | 0.27%   |
| Realtek Semiconductor       | 3         | 3      | 0.27%   |
| LITEON                      | 3         | 3      | 0.27%   |
| Gigabyte Technology         | 3         | 3      | 0.27%   |
| WALRAM                      | 2         | 3      | 0.18%   |
| UMIS                        | 2         | 2      | 0.18%   |
| Netac                       | 2         | 2      | 0.18%   |
| Maxtor                      | 2         | 2      | 0.18%   |
| Mass                        | 2         | 2      | 0.18%   |
| Unknown                     | 2         | 2      | 0.18%   |
| ZOTAC                       | 1         | 1      | 0.09%   |
| Wdxsky                      | 1         | 1      | 0.09%   |
| Vaseky                      | 1         | 1      | 0.09%   |
| Transcend                   | 1         | 1      | 0.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD    | 20        | 1.69%   |
| Kingston SA400S37240G 240GB SSD     | 19        | 1.61%   |
| Seagate ST1000LM035-1RK172 1TB      | 17        | 1.44%   |
| Seagate ST500DM002-1BD142 500GB     | 15        | 1.27%   |
| Toshiba MQ01ABF050 500GB            | 14        | 1.18%   |
| Toshiba DT01ACA100 1TB              | 14        | 1.18%   |
| Kingston SA400S37480G 480GB SSD     | 14        | 1.18%   |
| Crucial CT240BX500SSD1 240GB        | 13        | 1.1%    |
| Unknown MMC Card  64GB              | 12        | 1.02%   |
| Unknown MMC Card  32GB              | 11        | 0.93%   |
| Toshiba MQ04ABF100 1TB              | 10        | 0.85%   |
| Toshiba MQ01ABD100 1TB              | 10        | 0.85%   |
| Toshiba HDWD110 1TB                 | 10        | 0.85%   |
| Seagate ST500LT012-1DG142 500GB     | 10        | 0.85%   |
| Crucial CT480BX500SSD1 480GB        | 10        | 0.85%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 9         | 0.76%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 9         | 0.76%   |
| Samsung NVMe SSD Drive 512GB        | 9         | 0.76%   |
| Kingston SA400S37120G 120GB SSD     | 9         | 0.76%   |
| HGST HTS545050A7E680 500GB          | 8         | 0.68%   |
| Crucial CT120BX500SSD1 120GB        | 8         | 0.68%   |
| WDC WD10EZEX-08WN4A0 1TB            | 7         | 0.59%   |
| Unknown MMC Card  128GB             | 7         | 0.59%   |
| Seagate ST500LT012-9WS142 500GB     | 7         | 0.59%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 7         | 0.59%   |
| SanDisk NVMe SSD Drive 500GB        | 7         | 0.59%   |
| Crucial CT500MX500SSD1 500GB        | 7         | 0.59%   |
| Crucial CT1000MX500SSD1 1TB         | 7         | 0.59%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 6         | 0.51%   |
| WDC WD5000AAKX-001CA0 500GB         | 6         | 0.51%   |
| Seagate ST9500325AS 500GB           | 6         | 0.51%   |
| Kingston SNVS500G 500GB             | 6         | 0.51%   |
| Intel NVMe SSD Drive 512GB          | 6         | 0.51%   |
| HGST HTS541010A9E680 1TB            | 6         | 0.51%   |
| Crucial CT120BX300SSD1 120GB        | 6         | 0.51%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 5         | 0.42%   |
| WDC WD5000LPCX-21VHAT0 500GB        | 5         | 0.42%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 5         | 0.42%   |
| WDC WD10SPZX-60Z10T0 1TB            | 5         | 0.42%   |
| WDC WD10SPZX-24Z10 1TB              | 5         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 152       | 207    | 30.71%  |
| WDC                 | 148       | 200    | 29.9%   |
| Toshiba             | 97        | 110    | 19.6%   |
| Hitachi             | 42        | 50     | 8.48%   |
| HGST                | 28        | 29     | 5.66%   |
| Samsung Electronics | 12        | 16     | 2.42%   |
| Apple               | 8         | 8      | 1.62%   |
| Unknown             | 3         | 3      | 0.61%   |
| Maxtor              | 2         | 2      | 0.4%    |
| Fujitsu             | 1         | 1      | 0.2%    |
| ASMT                | 1         | 1      | 0.2%    |
| ASMedia             | 1         | 2      | 0.2%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 75        | 100    | 21.87%  |
| Crucial             | 67        | 82     | 19.53%  |
| WDC                 | 64        | 86     | 18.66%  |
| Samsung Electronics | 33        | 38     | 9.62%   |
| SanDisk             | 16        | 19     | 4.66%   |
| China               | 12        | 16     | 3.5%    |
| KingSpec            | 10        | 18     | 2.92%   |
| Corsair             | 6         | 11     | 1.75%   |
| Apple               | 6         | 6      | 1.75%   |
| Micron Technology   | 5         | 5      | 1.46%   |
| Lexar               | 5         | 10     | 1.46%   |
| SK hynix            | 4         | 6      | 1.17%   |
| XrayDisk            | 3         | 3      | 0.87%   |
| JMicron Technology  | 3         | 3      | 0.87%   |
| Intel               | 3         | 5      | 0.87%   |
| Gigabyte Technology | 3         | 3      | 0.87%   |
| A-DATA Technology   | 3         | 5      | 0.87%   |
| Toshiba             | 2         | 5      | 0.58%   |
| LITEON              | 2         | 2      | 0.58%   |
| Unknown             | 2         | 2      | 0.58%   |
| ZOTAC               | 1         | 1      | 0.29%   |
| Wdxsky              | 1         | 1      | 0.29%   |
| WALRAM              | 1         | 1      | 0.29%   |
| Vaseky              | 1         | 1      | 0.29%   |
| StoreJet            | 1         | 1      | 0.29%   |
| PNY                 | 1         | 1      | 0.29%   |
| Patriot             | 1         | 1      | 0.29%   |
| OCZ                 | 1         | 2      | 0.29%   |
| NGFF                | 1         | 1      | 0.29%   |
| Netac               | 1         | 1      | 0.29%   |
| Maxell              | 1         | 1      | 0.29%   |
| LITEONIT            | 1         | 1      | 0.29%   |
| KingDian            | 1         | 2      | 0.29%   |
| Intenso             | 1         | 1      | 0.29%   |
| HS-SSD-C100         | 1         | 1      | 0.29%   |
| Hewlett-Packard     | 1         | 1      | 0.29%   |
| FORESEE             | 1         | 2      | 0.29%   |
| Faspeed             | 1         | 1      | 0.29%   |
| BIWIN               | 1         | 1      | 0.29%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 437       | 629    | 43.22%  |
| SSD     | 309       | 447    | 30.56%  |
| NVMe    | 199       | 286    | 19.68%  |
| MMC     | 49        | 70     | 4.85%   |
| Unknown | 17        | 19     | 1.68%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 645       | 1062   | 70.26%  |
| NVMe | 199       | 286    | 21.68%  |
| MMC  | 49        | 70     | 5.34%   |
| SAS  | 25        | 33     | 2.72%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 481       | 718    | 65%     |
| 0.51-1.0   | 214       | 290    | 28.92%  |
| 1.01-2.0   | 30        | 42     | 4.05%   |
| 2.01-3.0   | 6         | 14     | 0.81%   |
| 3.01-4.0   | 5         | 6      | 0.68%   |
| 4.01-10.0  | 4         | 6      | 0.54%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 253       | 29.59%  |
| 101-250        | 221       | 25.85%  |
| 501-1000       | 127       | 14.85%  |
| 1-20           | 58        | 6.78%   |
| 1001-2000      | 51        | 5.96%   |
| 51-100         | 49        | 5.73%   |
| 21-50          | 35        | 4.09%   |
| More than 3000 | 21        | 2.46%   |
| 2001-3000      | 20        | 2.34%   |
| Unknown        | 20        | 2.34%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 350       | 39.82%  |
| 21-50          | 164       | 18.66%  |
| 101-250        | 105       | 11.95%  |
| 51-100         | 100       | 11.38%  |
| 251-500        | 65        | 7.39%   |
| 501-1000       | 43        | 4.89%   |
| 1001-2000      | 21        | 2.39%   |
| Unknown        | 20        | 2.28%   |
| More than 3000 | 8         | 0.91%   |
| 2001-3000      | 3         | 0.34%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB       | 4         | 4      | 5.48%   |
| HGST HTS545050A7E680 500GB            | 4         | 4      | 5.48%   |
| Toshiba MQ01ABD075 752GB              | 2         | 3      | 2.74%   |
| Seagate ST500DM002-1BD142 500GB       | 2         | 2      | 2.74%   |
| Kingston SA400S37240G 240GB SSD       | 2         | 2      | 2.74%   |
| Hitachi HTS545050B9A300 500GB         | 2         | 3      | 2.74%   |
| Hitachi HTS545050A7E380 500GB         | 2         | 2      | 2.74%   |
| XrayDisk SSD 256GB                    | 1         | 1      | 1.37%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 1.37%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD      | 1         | 1      | 1.37%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 1      | 1.37%   |
| WDC WD5000LPLX-60ZNTT1 500GB          | 1         | 1      | 1.37%   |
| WDC WD5000LPCX-60VHAT0 500GB          | 1         | 1      | 1.37%   |
| WDC WD5000AAKX-083CA1 500GB           | 1         | 1      | 1.37%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 1         | 1      | 1.37%   |
| WDC WD5000AAKX-001CA0 500GB           | 1         | 2      | 1.37%   |
| WDC WD20EARX-00PASB0 2TB              | 1         | 1      | 1.37%   |
| WDC WD1600BB-00GUC0 160GB             | 1         | 1      | 1.37%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 1      | 1.37%   |
| WDC WD10EARS-003BB1 1TB               | 1         | 1      | 1.37%   |
| Vaseky V820/1TB 1024GB                | 1         | 1      | 1.37%   |
| Toshiba MQ01ABD050 500GB              | 1         | 1      | 1.37%   |
| Toshiba MK3265GSXN 320GB              | 1         | 1      | 1.37%   |
| Toshiba MK3265GSX 320GB               | 1         | 1      | 1.37%   |
| Toshiba MK1652GSX 160GB               | 1         | 1      | 1.37%   |
| Toshiba DT01ACA100 1TB                | 1         | 1      | 1.37%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 1.37%   |
| Seagate ST9750420AS 752GB             | 1         | 1      | 1.37%   |
| Seagate ST9500325AS 500GB             | 1         | 1      | 1.37%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 1      | 1.37%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1      | 1.37%   |
| Seagate ST500LM000-1EJ162-SSHD 500GB  | 1         | 1      | 1.37%   |
| Seagate ST3500418AS 500GB             | 1         | 1      | 1.37%   |
| Seagate ST31000528AS 1TB              | 1         | 1      | 1.37%   |
| Seagate ST1000LM048-2E7172 1TB        | 1         | 1      | 1.37%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 1.37%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 6      | 1.37%   |
| Samsung Electronics SSD 870 EVO 1TB   | 1         | 1      | 1.37%   |
| Samsung Electronics HD250HJ 250GB     | 1         | 2      | 1.37%   |
| Samsung Electronics HD081GJ 80GB      | 1         | 1      | 1.37%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 21     | 22.54%  |
| WDC                 | 12        | 13     | 16.9%   |
| Hitachi             | 10        | 14     | 14.08%  |
| HGST                | 10        | 10     | 14.08%  |
| Toshiba             | 7         | 8      | 9.86%   |
| Kingston            | 6         | 9      | 8.45%   |
| Samsung Electronics | 2         | 4      | 2.82%   |
| XrayDisk            | 1         | 1      | 1.41%   |
| Vaseky              | 1         | 1      | 1.41%   |
| SK hynix            | 1         | 1      | 1.41%   |
| LITEON              | 1         | 1      | 1.41%   |
| Intel               | 1         | 2      | 1.41%   |
| Faspeed             | 1         | 1      | 1.41%   |
| Crucial             | 1         | 1      | 1.41%   |
| A-DATA Technology   | 1         | 1      | 1.41%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 21     | 29.63%  |
| WDC                 | 10        | 11     | 18.52%  |
| Hitachi             | 10        | 14     | 18.52%  |
| HGST                | 10        | 10     | 18.52%  |
| Toshiba             | 7         | 8      | 12.96%  |
| Samsung Electronics | 1         | 3      | 1.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 51        | 67     | 75%     |
| SSD  | 16        | 20     | 23.53%  |
| NVMe | 1         | 1      | 1.47%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                    | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Toshiba MQ01ABF050 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 540       | 936    | 62.43%  |
| Works    | 257       | 426    | 29.71%  |
| Malfunc  | 67        | 88     | 7.75%   |
| Failed   | 1         | 1      | 0.12%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 516       | 55.07%  |
| AMD                              | 188       | 20.06%  |
| Samsung Electronics              | 52        | 5.55%   |
| SanDisk                          | 38        | 4.06%   |
| SK hynix                         | 23        | 2.45%   |
| Kingston Technology Company      | 23        | 2.45%   |
| Silicon Motion                   | 11        | 1.17%   |
| Micron Technology                | 10        | 1.07%   |
| Realtek Semiconductor            | 8         | 0.85%   |
| Nvidia                           | 8         | 0.85%   |
| KIOXIA                           | 8         | 0.85%   |
| JMicron Technology               | 8         | 0.85%   |
| Micron/Crucial Technology        | 7         | 0.75%   |
| Marvell Technology Group         | 7         | 0.75%   |
| Toshiba America Info Systems     | 5         | 0.53%   |
| ASMedia Technology               | 5         | 0.53%   |
| ADATA Technology                 | 5         | 0.53%   |
| Silicon Integrated Systems [SiS] | 4         | 0.43%   |
| Solid State Storage Technology   | 3         | 0.32%   |
| Union Memory (Shenzhen)          | 2         | 0.21%   |
| VIA Technologies                 | 1         | 0.11%   |
| Shenzhen Longsys Electronics     | 1         | 0.11%   |
| Phison Electronics               | 1         | 0.11%   |
| O2 Micro                         | 1         | 0.11%   |
| Lite-On Technology               | 1         | 0.11%   |
| Broadcom / LSI                   | 1         | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 138       | 12.85%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 68        | 6.33%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 40        | 3.72%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 34        | 3.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 29        | 2.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 24        | 2.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 23        | 2.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 23        | 2.14%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 22        | 2.05%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 21        | 1.96%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 19        | 1.77%   |
| Intel Volume Management Device NVMe RAID Controller                              | 18        | 1.68%   |
| AMD 400 Series Chipset SATA Controller                                           | 18        | 1.68%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 16        | 1.49%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 14        | 1.3%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 13        | 1.21%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 13        | 1.21%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 12        | 1.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 12        | 1.12%   |
| Samsung NVMe SSD Controller 980                                                  | 11        | 1.02%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 11        | 1.02%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 11        | 1.02%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 10        | 0.93%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 10        | 0.93%   |
| Micron NVMe Storage Controller                                                   | 10        | 0.93%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 10        | 0.93%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 10        | 0.93%   |
| Intel SSD 660P Series                                                            | 9         | 0.84%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 9         | 0.84%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 9         | 0.84%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 8         | 0.74%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 8         | 0.74%   |
| Intel Comet Lake SATA AHCI Controller                                            | 8         | 0.74%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 8         | 0.74%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 8         | 0.74%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 7         | 0.65%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 7         | 0.65%   |
| Realtek RTS5763DL NVMe SSD Controller                                            | 7         | 0.65%   |
| Intel NVMe Controller                                                            | 7         | 0.65%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 7         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 594       | 62.13%  |
| NVMe | 200       | 20.92%  |
| IDE  | 100       | 10.46%  |
| RAID | 62        | 6.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 579       | 71.66%  |
| AMD    | 228       | 28.22%  |
| ARM    | 1         | 0.12%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 13        | 1.6%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 11        | 1.35%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 11        | 1.35%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 10        | 1.23%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 10        | 1.23%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 1.11%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 9         | 1.11%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 9         | 1.11%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 7         | 0.86%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 7         | 0.86%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 7         | 0.86%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 0.86%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 7         | 0.86%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 7         | 0.86%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 6         | 0.74%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 6         | 0.74%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 6         | 0.74%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 6         | 0.74%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 0.74%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 6         | 0.74%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 5         | 0.62%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 5         | 0.62%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 5         | 0.62%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 5         | 0.62%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 5         | 0.62%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 5         | 0.62%   |
| AMD Ryzen 3 4300U with Radeon Graphics        | 5         | 0.62%   |
| AMD FX-6300 Six-Core Processor                | 5         | 0.62%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 4         | 0.49%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 4         | 0.49%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 4         | 0.49%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 0.49%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 4         | 0.49%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 4         | 0.49%   |
| Intel Core i5-10400F CPU @ 2.90GHz            | 4         | 0.49%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 4         | 0.49%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 4         | 0.49%   |
| Intel Celeron N4500 @ 1.10GHz                 | 4         | 0.49%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 4         | 0.49%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 4         | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 161       | 19.83%  |
| Intel Core i7           | 121       | 14.9%   |
| Intel Core i3           | 67        | 8.25%   |
| Intel Celeron           | 55        | 6.77%   |
| AMD Ryzen 5             | 49        | 6.03%   |
| Intel Pentium           | 34        | 4.19%   |
| AMD Ryzen 7             | 29        | 3.57%   |
| Other                   | 27        | 3.33%   |
| Intel Core 2 Duo        | 26        | 3.2%    |
| Intel Xeon              | 24        | 2.96%   |
| Intel Atom              | 23        | 2.83%   |
| AMD Ryzen 3             | 17        | 2.09%   |
| AMD A6                  | 14        | 1.72%   |
| AMD A10                 | 14        | 1.72%   |
| Intel Pentium Dual-Core | 12        | 1.48%   |
| AMD FX                  | 12        | 1.48%   |
| AMD A8                  | 12        | 1.48%   |
| AMD E                   | 9         | 1.11%   |
| Intel Pentium Dual      | 8         | 0.99%   |
| AMD E1                  | 8         | 0.99%   |
| AMD A4                  | 8         | 0.99%   |
| AMD E2                  | 6         | 0.74%   |
| AMD Athlon              | 6         | 0.74%   |
| AMD Ryzen 9             | 5         | 0.62%   |
| Intel Core 2            | 4         | 0.49%   |
| AMD A12                 | 4         | 0.49%   |
| Intel Pentium Silver    | 3         | 0.37%   |
| Intel Genuine           | 3         | 0.37%   |
| Intel Core i9           | 3         | 0.37%   |
| Intel Celeron Dual-Core | 3         | 0.37%   |
| AMD Turion II Dual-Core | 3         | 0.37%   |
| AMD Ryzen 5 PRO         | 3         | 0.37%   |
| AMD Phenom              | 3         | 0.37%   |
| AMD Athlon II X2        | 3         | 0.37%   |
| AMD Athlon II           | 3         | 0.37%   |
| Intel Pentium Gold      | 2         | 0.25%   |
| Intel Pentium 4         | 2         | 0.25%   |
| Intel Core 2 Quad       | 2         | 0.25%   |
| AMD Ryzen 7 PRO         | 2         | 0.25%   |
| AMD Phenom II X6        | 2         | 0.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 388       | 47.67%  |
| 4       | 293       | 36%     |
| 6       | 46        | 5.65%   |
| 8       | 41        | 5.04%   |
| 1       | 17        | 2.09%   |
| 3       | 8         | 0.98%   |
| 12      | 6         | 0.74%   |
| Unknown | 6         | 0.74%   |
| 10      | 5         | 0.61%   |
| 16      | 3         | 0.37%   |
| 20      | 1         | 0.12%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 802       | 99.26%  |
| 2       | 4         | 0.5%    |
| 4       | 1         | 0.12%   |
| Unknown | 1         | 0.12%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 502       | 61.9%   |
| 1       | 303       | 37.36%  |
| Unknown | 6         | 0.74%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 782       | 96.54%  |
| Unknown        | 15        | 1.85%   |
| 32-bit         | 7         | 0.86%   |
| 64-bit         | 6         | 0.74%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 170       | 20.38%  |
| 0x206a7    | 43        | 5.16%   |
| 0x306a9    | 35        | 4.2%    |
| 0x406e3    | 30        | 3.6%    |
| 0x806e9    | 24        | 2.88%   |
| 0x1067a    | 24        | 2.88%   |
| 0x306c3    | 23        | 2.76%   |
| 0x806ec    | 21        | 2.52%   |
| 0x40651    | 21        | 2.52%   |
| 0x30678    | 20        | 2.4%    |
| 0x08108109 | 19        | 2.28%   |
| 0x906ea    | 17        | 2.04%   |
| 0x906e9    | 15        | 1.8%    |
| 0x806ea    | 15        | 1.8%    |
| 0x806c1    | 14        | 1.68%   |
| 0x6fd      | 13        | 1.56%   |
| 0x406c4    | 13        | 1.56%   |
| 0x08108102 | 13        | 1.56%   |
| 0x20655    | 12        | 1.44%   |
| 0x0810100b | 12        | 1.44%   |
| 0x05000119 | 11        | 1.32%   |
| 0xa0652    | 10        | 1.2%    |
| 0x306d4    | 10        | 1.2%    |
| 0x08701021 | 10        | 1.2%    |
| 0x10676    | 9         | 1.08%   |
| 0x506c9    | 8         | 0.96%   |
| 0x0a50000c | 8         | 0.96%   |
| 0x08600106 | 8         | 0.96%   |
| 0x406c3    | 7         | 0.84%   |
| 0x07030105 | 7         | 0.84%   |
| 0x0700010f | 7         | 0.84%   |
| 0x06001119 | 7         | 0.84%   |
| 0x06000852 | 7         | 0.84%   |
| 0x806eb    | 6         | 0.72%   |
| 0x706a8    | 6         | 0.72%   |
| 0x706a1    | 6         | 0.72%   |
| 0x506e3    | 6         | 0.72%   |
| 0x06006705 | 6         | 0.72%   |
| 0x03000027 | 6         | 0.72%   |
| 0xa0653    | 5         | 0.6%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 132       | 16.28%  |
| Haswell          | 64        | 7.89%   |
| SandyBridge      | 55        | 6.78%   |
| IvyBridge        | 48        | 5.92%   |
| Skylake          | 45        | 5.55%   |
| Silvermont       | 45        | 5.55%   |
| Penryn           | 43        | 5.3%    |
| Zen+             | 39        | 4.81%   |
| Zen 2            | 30        | 3.7%    |
| Zen              | 23        | 2.84%   |
| Piledriver       | 22        | 2.71%   |
| Westmere         | 21        | 2.59%   |
| Core             | 21        | 2.59%   |
| CometLake        | 20        | 2.47%   |
| TigerLake        | 19        | 2.34%   |
| Excavator        | 19        | 2.34%   |
| K10              | 17        | 2.1%    |
| Bobcat           | 17        | 2.1%    |
| Zen 3            | 15        | 1.85%   |
| Broadwell        | 15        | 1.85%   |
| Puma             | 12        | 1.48%   |
| Goldmont plus    | 12        | 1.48%   |
| Unknown          | 11        | 1.36%   |
| Jaguar           | 10        | 1.23%   |
| Bonnell          | 10        | 1.23%   |
| Goldmont         | 8         | 0.99%   |
| K10 Llano        | 7         | 0.86%   |
| IceLake          | 5         | 0.62%   |
| Steamroller      | 4         | 0.49%   |
| K8 Hammer        | 4         | 0.49%   |
| Bulldozer        | 4         | 0.49%   |
| Tremont          | 3         | 0.37%   |
| P6               | 3         | 0.37%   |
| Nehalem          | 3         | 0.37%   |
| NetBurst         | 2         | 0.25%   |
| Alderlake Hybrid | 2         | 0.25%   |
| K8 & K10 hybrid  | 1         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 482       | 50.74%  |
| AMD                              | 254       | 26.74%  |
| Nvidia                           | 204       | 21.47%  |
| Silicon Integrated Systems [SiS] | 4         | 0.42%   |
| Matrox Electronics Systems       | 3         | 0.32%   |
| ATI Technologies                 | 2         | 0.21%   |
| VIA Technologies                 | 1         | 0.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 47        | 4.71%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 32        | 3.21%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 30        | 3.01%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 28        | 2.81%   |
| Intel HD Graphics 620                                                                    | 27        | 2.71%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 24        | 2.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 23        | 2.31%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 22        | 2.21%   |
| Intel UHD Graphics 620                                                                   | 20        | 2.01%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 19        | 1.91%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 18        | 1.81%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 17        | 1.71%   |
| AMD Renoir                                                                               | 16        | 1.6%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 16        | 1.6%    |
| Intel Core Processor Integrated Graphics Controller                                      | 15        | 1.5%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 15        | 1.5%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 14        | 1.4%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 14        | 1.4%    |
| Intel HD Graphics 630                                                                    | 13        | 1.3%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 13        | 1.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 12        | 1.2%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 12        | 1.2%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 11        | 1.1%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 9         | 0.9%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 0.9%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 9         | 0.9%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 9         | 0.9%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 9         | 0.9%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 9         | 0.9%    |
| Intel HD Graphics 5500                                                                   | 8         | 0.8%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 8         | 0.8%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 8         | 0.8%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 7         | 0.7%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 6         | 0.6%    |
| Nvidia TU117M                                                                            | 6         | 0.6%    |
| Nvidia GP108M [GeForce MX150]                                                            | 6         | 0.6%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 6         | 0.6%    |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 6         | 0.6%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 6         | 0.6%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 6         | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 361       | 44.51%  |
| 1 x AMD        | 181       | 22.32%  |
| 1 x Nvidia     | 94        | 11.59%  |
| Intel + Nvidia | 93        | 11.47%  |
| 2 x AMD        | 31        | 3.82%   |
| Intel + AMD    | 23        | 2.84%   |
| AMD + Nvidia   | 18        | 2.22%   |
| 1 x SiS        | 4         | 0.49%   |
| 1 x Matrox     | 2         | 0.25%   |
| Other          | 1         | 0.12%   |
| 2 x Intel      | 1         | 0.12%   |
| 1 x VIA        | 1         | 0.12%   |
| AMD + Matrox   | 1         | 0.12%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 676       | 82.84%  |
| Proprietary | 111       | 13.6%   |
| Unknown     | 29        | 3.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 467       | 56.54%  |
| 1.01-2.0   | 110       | 13.32%  |
| 0.01-0.5   | 108       | 13.08%  |
| 0.51-1.0   | 63        | 7.63%   |
| 3.01-4.0   | 44        | 5.33%   |
| 5.01-6.0   | 11        | 1.33%   |
| 7.01-8.0   | 10        | 1.21%   |
| 8.01-16.0  | 7         | 0.85%   |
| 2.01-3.0   | 6         | 0.73%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 139       | 15.94%  |
| AU Optronics            | 122       | 13.99%  |
| BOE                     | 104       | 11.93%  |
| Chimei Innolux          | 94        | 10.78%  |
| LG Display              | 76        | 8.72%   |
| Goldstar                | 63        | 7.22%   |
| Hewlett-Packard         | 27        | 3.1%    |
| Lenovo                  | 20        | 2.29%   |
| Dell                    | 19        | 2.18%   |
| AOC                     | 19        | 2.18%   |
| ViewSonic               | 13        | 1.49%   |
| PANDA                   | 12        | 1.38%   |
| LG Electronics          | 12        | 1.38%   |
| Sony                    | 11        | 1.26%   |
| Apple                   | 11        | 1.26%   |
| Unknown                 | 9         | 1.03%   |
| Chi Mei Optoelectronics | 9         | 1.03%   |
| Sharp                   | 8         | 0.92%   |
| InfoVision              | 8         | 0.92%   |
| SAC                     | 7         | 0.8%    |
| Envision                | 7         | 0.8%    |
| Acer                    | 6         | 0.69%   |
| ___                     | 5         | 0.57%   |
| ASUSTek Computer        | 5         | 0.57%   |
| Packard Bell            | 4         | 0.46%   |
| MSI                     | 4         | 0.46%   |
| LG Philips              | 4         | 0.46%   |
| KTC                     | 4         | 0.46%   |
| Hitachi                 | 4         | 0.46%   |
| Ancor Communications    | 4         | 0.46%   |
| Plain Tree Systems      | 3         | 0.34%   |
| CSO                     | 3         | 0.34%   |
| STA                     | 2         | 0.23%   |
| SKY                     | 2         | 0.23%   |
| Philips                 | 2         | 0.23%   |
| Panasonic               | 2         | 0.23%   |
| NCS                     | 2         | 0.23%   |
| LGD                     | 2         | 0.23%   |
| InnoLux Display         | 2         | 0.23%   |
| HKC                     | 2         | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 10        | 1.12%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 10        | 1.12%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                  | 9         | 1.01%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 7         | 0.78%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 6         | 0.67%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 6         | 0.67%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 6         | 0.67%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 6         | 0.67%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 6         | 0.67%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch | 5         | 0.56%   |
| SAC LED MONITOR SAC952D 1920x1080 443x249mm 20.0-inch                 | 5         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 5         | 0.56%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 5         | 0.56%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 5         | 0.56%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 5         | 0.56%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 5         | 0.56%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 5         | 0.56%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 5         | 0.56%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 5         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch  | 4         | 0.45%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 4         | 0.45%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 4         | 0.45%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                | 4         | 0.45%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 4         | 0.45%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 4         | 0.45%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 4         | 0.45%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 4         | 0.45%   |
| BOE LCD Monitor BOE0628 1366x768 309x173mm 13.9-inch                  | 4         | 0.45%   |
| BOE LCD Monitor BOE0602 1366x768 344x193mm 15.5-inch                  | 4         | 0.45%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 4         | 0.45%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch         | 4         | 0.45%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 4         | 0.45%   |
| ___ LCD TV ___9000 1360x768                                           | 3         | 0.34%   |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                  | 3         | 0.34%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                    | 3         | 0.34%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 3         | 0.34%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 3         | 0.34%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch     | 3         | 0.34%   |
| MSI Optix G241VC MSI1462 1920x1080 521x294mm 23.6-inch                | 3         | 0.34%   |
| LG Electronics LCD Monitor LG IPS FULLHD 1920x1080                    | 3         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 299       | 35.89%  |
| 1920x1080 (FHD)    | 285       | 34.21%  |
| 1600x900 (HD+)     | 35        | 4.2%    |
| 3840x2160 (4K)     | 33        | 3.96%   |
| 1360x768           | 32        | 3.84%   |
| 1440x900 (WXGA+)   | 23        | 2.76%   |
| 1280x800 (WXGA)    | 19        | 2.28%   |
| 1280x1024 (SXGA)   | 15        | 1.8%    |
| 2560x1080          | 14        | 1.68%   |
| 1680x1050 (WSXGA+) | 10        | 1.2%    |
| 2560x1440 (QHD)    | 8         | 0.96%   |
| Unknown            | 7         | 0.84%   |
| 1920x1200 (WUXGA)  | 6         | 0.72%   |
| 3440x1440          | 5         | 0.6%    |
| 2560x1600          | 5         | 0.6%    |
| 1024x600           | 4         | 0.48%   |
| 3840x1080          | 3         | 0.36%   |
| 2160x1440          | 3         | 0.36%   |
| 1920x540           | 3         | 0.36%   |
| 1024x768 (XGA)     | 3         | 0.36%   |
| 800x1280           | 2         | 0.24%   |
| 3840x1100          | 2         | 0.24%   |
| 3286x1080          | 2         | 0.24%   |
| 1024x576           | 2         | 0.24%   |
| 5760x1080          | 1         | 0.12%   |
| 5440x1800          | 1         | 0.12%   |
| 3840x2400          | 1         | 0.12%   |
| 3840x1600          | 1         | 0.12%   |
| 3000x2000          | 1         | 0.12%   |
| 2880x1800          | 1         | 0.12%   |
| 2288x1287          | 1         | 0.12%   |
| 1920x515           | 1         | 0.12%   |
| 1680x945           | 1         | 0.12%   |
| 1600x1200          | 1         | 0.12%   |
| 1280x960           | 1         | 0.12%   |
| 1280x768           | 1         | 0.12%   |
| 1280x720 (HD)      | 1         | 0.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 199       | 22.82%  |
| 13      | 146       | 16.74%  |
| 14      | 129       | 14.79%  |
| 21      | 57        | 6.54%   |
| 23      | 53        | 6.08%   |
| Unknown | 36        | 4.13%   |
| 17      | 27        | 3.1%    |
| 19      | 24        | 2.75%   |
| 18      | 24        | 2.75%   |
| 24      | 23        | 2.64%   |
| 34      | 18        | 2.06%   |
| 27      | 18        | 2.06%   |
| 11      | 16        | 1.83%   |
| 31      | 14        | 1.61%   |
| 20      | 12        | 1.38%   |
| 12      | 11        | 1.26%   |
| 72      | 10        | 1.15%   |
| 32      | 9         | 1.03%   |
| 10      | 8         | 0.92%   |
| 84      | 7         | 0.8%    |
| 54      | 5         | 0.57%   |
| 22      | 5         | 0.57%   |
| 48      | 4         | 0.46%   |
| 40      | 4         | 0.46%   |
| 16      | 4         | 0.46%   |
| 37      | 2         | 0.23%   |
| 142     | 1         | 0.11%   |
| 65      | 1         | 0.11%   |
| 52      | 1         | 0.11%   |
| 43      | 1         | 0.11%   |
| 28      | 1         | 0.11%   |
| 26      | 1         | 0.11%   |
| 7       | 1         | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 427       | 49.82%  |
| 401-500        | 106       | 12.37%  |
| 501-600        | 87        | 10.15%  |
| 201-300        | 84        | 9.8%    |
| Unknown        | 36        | 4.2%    |
| 351-400        | 34        | 3.97%   |
| 701-800        | 27        | 3.15%   |
| 601-700        | 19        | 2.22%   |
| 1501-2000      | 17        | 1.98%   |
| 1001-1500      | 11        | 1.28%   |
| 801-900        | 6         | 0.7%    |
| More than 2000 | 1         | 0.12%   |
| 901-1000       | 1         | 0.12%   |
| 1-100          | 1         | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 622       | 80.57%  |
| 16/10   | 71        | 9.2%    |
| Unknown | 25        | 3.24%   |
| 21/9    | 18        | 2.33%   |
| 5/4     | 16        | 2.07%   |
| 4/3     | 7         | 0.91%   |
| 3/2     | 4         | 0.52%   |
| 3.40    | 2         | 0.26%   |
| 1.96    | 2         | 0.26%   |
| 32/9    | 1         | 0.13%   |
| 3.73    | 1         | 0.13%   |
| 1.00    | 1         | 0.13%   |
| 0.67    | 1         | 0.13%   |
| 0.62    | 1         | 0.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 230       | 26.59%  |
| 101-110        | 200       | 23.12%  |
| 201-250        | 116       | 13.41%  |
| 151-200        | 48        | 5.55%   |
| 351-500        | 42        | 4.86%   |
| 71-80          | 41        | 4.74%   |
| Unknown        | 36        | 4.16%   |
| 141-150        | 29        | 3.35%   |
| More than 1000 | 27        | 3.12%   |
| 301-350        | 19        | 2.2%    |
| 51-60          | 18        | 2.08%   |
| 121-130        | 12        | 1.39%   |
| 61-70          | 10        | 1.16%   |
| 501-1000       | 9         | 1.04%   |
| 41-50          | 8         | 0.92%   |
| 131-140        | 7         | 0.81%   |
| 251-300        | 6         | 0.69%   |
| 111-120        | 3         | 0.35%   |
| 91-100         | 3         | 0.35%   |
| 1-40           | 1         | 0.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 338       | 39.67%  |
| 51-100        | 205       | 24.06%  |
| 121-160       | 183       | 21.48%  |
| 1-50          | 41        | 4.81%   |
| 161-240       | 40        | 4.69%   |
| Unknown       | 36        | 4.23%   |
| More than 240 | 9         | 1.06%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 642       | 77.63%  |
| 2     | 136       | 16.44%  |
| 0     | 35        | 4.23%   |
| 3     | 14        | 1.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 525       | 42.1%   |
| Intel                            | 288       | 23.1%   |
| Qualcomm Atheros                 | 159       | 12.75%  |
| Broadcom                         | 71        | 5.69%   |
| Ralink                           | 30        | 2.41%   |
| Ralink Technology                | 21        | 1.68%   |
| Broadcom Limited                 | 19        | 1.52%   |
| TP-Link                          | 18        | 1.44%   |
| Marvell Technology Group         | 14        | 1.12%   |
| Huawei Technologies              | 14        | 1.12%   |
| Xiaomi                           | 12        | 0.96%   |
| Samsung Electronics              | 8         | 0.64%   |
| Qualcomm Atheros Communications  | 7         | 0.56%   |
| Nvidia                           | 7         | 0.56%   |
| MediaTek                         | 6         | 0.48%   |
| D-Link System                    | 5         | 0.4%    |
| D-Link                           | 5         | 0.4%    |
| Silicon Integrated Systems [SiS] | 4         | 0.32%   |
| JMicron Technology               | 4         | 0.32%   |
| ICS Advent                       | 4         | 0.32%   |
| Motorola PCS                     | 3         | 0.24%   |
| Microsoft                        | 3         | 0.24%   |
| VIA Technologies                 | 2         | 0.16%   |
| DisplayLink                      | 2         | 0.16%   |
| ASIX Electronics                 | 2         | 0.16%   |
| Spreadtrum Communications        | 1         | 0.08%   |
| Qcom                             | 1         | 0.08%   |
| Padix (Rockfire)                 | 1         | 0.08%   |
| Oculus VR                        | 1         | 0.08%   |
| Netchip Technology               | 1         | 0.08%   |
| Microchip Technology             | 1         | 0.08%   |
| Mercucys                         | 1         | 0.08%   |
| Manta                            | 1         | 0.08%   |
| Lenovo                           | 1         | 0.08%   |
| HMD Global                       | 1         | 0.08%   |
| Hewlett-Packard                  | 1         | 0.08%   |
| ASUSTek Computer                 | 1         | 0.08%   |
| Arduino SA                       | 1         | 0.08%   |
| Apple                            | 1         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 338       | 22.85%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 108       | 7.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 30        | 2.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 30        | 2.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 29        | 1.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 29        | 1.96%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 26        | 1.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 23        | 1.56%   |
| Intel Wi-Fi 6 AX200                                                     | 21        | 1.42%   |
| Intel Wireless 8260                                                     | 20        | 1.35%   |
| Intel Wireless 8265 / 8275                                              | 18        | 1.22%   |
| Intel Wireless 7260                                                     | 18        | 1.22%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 17        | 1.15%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 16        | 1.08%   |
| Intel Wireless 7265                                                     | 16        | 1.08%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 15        | 1.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 15        | 1.01%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 14        | 0.95%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 13        | 0.88%   |
| Intel Wi-Fi 6 AX201                                                     | 13        | 0.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 13        | 0.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 12        | 0.81%   |
| Huawei ANA-NX9                                                          | 12        | 0.81%   |
| Broadcom BCM43142 802.11b/g/n                                           | 12        | 0.81%   |
| Ralink MT7601U Wireless Adapter                                         | 11        | 0.74%   |
| Intel Ethernet Connection I219-LM                                       | 11        | 0.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 11        | 0.74%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 10        | 0.68%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 10        | 0.68%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 10        | 0.68%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 10        | 0.68%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 9         | 0.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 9         | 0.61%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 8         | 0.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 0.54%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 7         | 0.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 7         | 0.47%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 7         | 0.47%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 0.47%   |
| Intel I211 Gigabit Network Connection                                   | 7         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 250       | 34.58%  |
| Realtek Semiconductor           | 173       | 23.93%  |
| Qualcomm Atheros                | 137       | 18.95%  |
| Broadcom                        | 54        | 7.47%   |
| Ralink                          | 30        | 4.15%   |
| Ralink Technology               | 21        | 2.9%    |
| TP-Link                         | 17        | 2.35%   |
| Broadcom Limited                | 14        | 1.94%   |
| Qualcomm Atheros Communications | 7         | 0.97%   |
| MediaTek                        | 6         | 0.83%   |
| D-Link                          | 4         | 0.55%   |
| Microsoft                       | 3         | 0.41%   |
| D-Link System                   | 3         | 0.41%   |
| Qcom                            | 1         | 0.14%   |
| Mercucys                        | 1         | 0.14%   |
| Hewlett-Packard                 | 1         | 0.14%   |
| ASUSTek Computer                | 1         | 0.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 30        | 4.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 30        | 4.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 29        | 4%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 29        | 4%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 26        | 3.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 23        | 3.17%   |
| Intel Wi-Fi 6 AX200                                                     | 21        | 2.9%    |
| Intel Wireless 8260                                                     | 20        | 2.76%   |
| Intel Wireless 8265 / 8275                                              | 18        | 2.48%   |
| Intel Wireless 7260                                                     | 18        | 2.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 17        | 2.34%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 16        | 2.21%   |
| Intel Wireless 7265                                                     | 16        | 2.21%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 15        | 2.07%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 14        | 1.93%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 13        | 1.79%   |
| Intel Wi-Fi 6 AX201                                                     | 13        | 1.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 12        | 1.66%   |
| Broadcom BCM43142 802.11b/g/n                                           | 12        | 1.66%   |
| Ralink MT7601U Wireless Adapter                                         | 11        | 1.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 11        | 1.52%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 10        | 1.38%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 10        | 1.38%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 10        | 1.38%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 9         | 1.24%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 9         | 1.24%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 8         | 1.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 1.1%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 7         | 0.97%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 7         | 0.97%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 7         | 0.97%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 0.97%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 0.97%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 6         | 0.83%   |
| Qualcomm Atheros AR9271 802.11n                                         | 6         | 0.83%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 6         | 0.83%   |
| Intel Wireless 3165                                                     | 6         | 0.83%   |
| Intel Centrino Advanced-N 6235                                          | 6         | 0.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 0.83%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 6         | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 471       | 63.91%  |
| Intel                            | 114       | 15.47%  |
| Qualcomm Atheros                 | 34        | 4.61%   |
| Broadcom                         | 30        | 4.07%   |
| Marvell Technology Group         | 14        | 1.9%    |
| Huawei Technologies              | 13        | 1.76%   |
| Xiaomi                           | 12        | 1.63%   |
| Samsung Electronics              | 7         | 0.95%   |
| Nvidia                           | 7         | 0.95%   |
| Broadcom Limited                 | 5         | 0.68%   |
| Silicon Integrated Systems [SiS] | 4         | 0.54%   |
| JMicron Technology               | 4         | 0.54%   |
| ICS Advent                       | 4         | 0.54%   |
| VIA Technologies                 | 2         | 0.27%   |
| Motorola PCS                     | 2         | 0.27%   |
| DisplayLink                      | 2         | 0.27%   |
| D-Link System                    | 2         | 0.27%   |
| ASIX Electronics                 | 2         | 0.27%   |
| TP-Link                          | 1         | 0.14%   |
| Spreadtrum Communications        | 1         | 0.14%   |
| Netchip Technology               | 1         | 0.14%   |
| Microchip Technology             | 1         | 0.14%   |
| Lenovo                           | 1         | 0.14%   |
| HMD Global                       | 1         | 0.14%   |
| D-Link                           | 1         | 0.14%   |
| Apple                            | 1         | 0.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 338       | 45.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 108       | 14.46%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 15        | 2.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13        | 1.74%   |
| Huawei ANA-NX9                                                    | 12        | 1.61%   |
| Intel Ethernet Connection I219-LM                                 | 11        | 1.47%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 10        | 1.34%   |
| Intel I211 Gigabit Network Connection                             | 7         | 0.94%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 0.94%   |
| Intel Ethernet Connection (4) I219-V                              | 7         | 0.94%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 0.8%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 6         | 0.8%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 0.8%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 6         | 0.8%    |
| Intel Ethernet Connection I217-V                                  | 6         | 0.8%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 0.67%   |
| Intel Ethernet Connection (6) I219-V                              | 5         | 0.67%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 0.67%   |
| Intel 82567LM Gigabit Network Connection                          | 5         | 0.67%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 5         | 0.67%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 4         | 0.54%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 4         | 0.54%   |
| Nvidia MCP61 Ethernet                                             | 4         | 0.54%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 0.54%   |
| Intel Ethernet Connection (10) I219-V                             | 4         | 0.54%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 0.54%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.4%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 3         | 0.4%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 0.4%    |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.4%    |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.4%    |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.4%    |
| Intel 82579V Gigabit Network Connection                           | 3         | 0.4%    |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.4%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 0.4%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 0.4%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2         | 0.27%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.27%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.27%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 693       | 50.18%  |
| WiFi     | 681       | 49.31%  |
| Modem    | 4         | 0.29%   |
| Unknown  | 3         | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 534       | 64.26%  |
| Ethernet | 297       | 35.74%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 498       | 61.41%  |
| 1     | 281       | 34.65%  |
| 3     | 16        | 1.97%   |
| 0     | 14        | 1.73%   |
| 4     | 2         | 0.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 745       | 91.41%  |
| Yes  | 70        | 8.59%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 203       | 37.8%   |
| Realtek Semiconductor           | 102       | 18.99%  |
| Qualcomm Atheros Communications | 44        | 8.19%   |
| Broadcom                        | 36        | 6.7%    |
| Lite-On Technology              | 27        | 5.03%   |
| IMC Networks                    | 27        | 5.03%   |
| Cambridge Silicon Radio         | 25        | 4.66%   |
| Apple                           | 17        | 3.17%   |
| Foxconn / Hon Hai               | 14        | 2.61%   |
| Ralink                          | 10        | 1.86%   |
| Dell                            | 8         | 1.49%   |
| Realtek                         | 6         | 1.12%   |
| Hewlett-Packard                 | 5         | 0.93%   |
| Toshiba                         | 3         | 0.56%   |
| Ralink Technology               | 3         | 0.56%   |
| ASUSTek Computer                | 3         | 0.56%   |
| Foxconn International           | 2         | 0.37%   |
| MediaTek                        | 1         | 0.19%   |
| Alps Electric                   | 1         | 0.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 82        | 15.27%  |
| Realtek Bluetooth Radio                             | 52        | 9.68%   |
| Realtek  Bluetooth 4.2 Adapter                      | 41        | 7.64%   |
| Intel AX201 Bluetooth                               | 35        | 6.52%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 26        | 4.84%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 25        | 4.66%   |
| Qualcomm Atheros  Bluetooth Device                  | 21        | 3.91%   |
| Intel AX200 Bluetooth                               | 21        | 3.91%   |
| IMC Networks Bluetooth Radio                        | 11        | 2.05%   |
| Ralink RT3290 Bluetooth                             | 10        | 1.86%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 10        | 1.86%   |
| Apple Bluetooth USB Host Controller                 | 10        | 1.86%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 9         | 1.68%   |
| Lite-On Atheros AR3012 Bluetooth                    | 9         | 1.68%   |
| Intel Wireless-AC 3168 Bluetooth                    | 9         | 1.68%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 9         | 1.68%   |
| Intel AX210 Bluetooth                               | 9         | 1.68%   |
| IMC Networks Bluetooth Device                       | 9         | 1.68%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 8         | 1.49%   |
| Realtek RTL8821A Bluetooth                          | 7         | 1.3%    |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 7         | 1.3%    |
| Realtek Bluetooth Radio                             | 6         | 1.12%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 6         | 1.12%   |
| Apple Bluetooth Host Controller                     | 6         | 1.12%   |
| Lite-On Bluetooth Device                            | 5         | 0.93%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 5         | 0.93%   |
| Broadcom Bluetooth 3.0 Dongle                       | 5         | 0.93%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 0.74%   |
| IMC Networks Wireless_Device                        | 4         | 0.74%   |
| Broadcom HP Portable Bumble Bee                     | 4         | 0.74%   |
| Broadcom BCM2070 Bluetooth Device                   | 4         | 0.74%   |
| Toshiba Bluetooth Device                            | 3         | 0.56%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 3         | 0.56%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 0.56%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 0.56%   |
| Dell Wireless 365 Bluetooth                         | 3         | 0.56%   |
| Qualcomm Atheros Bluetooth                          | 2         | 0.37%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.37%   |
| Lite-On Qualcomm Atheros Bluetooth                  | 2         | 0.37%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 552       | 54.12%  |
| AMD                              | 254       | 24.9%   |
| Nvidia                           | 129       | 12.65%  |
| C-Media Electronics              | 13        | 1.27%   |
| Creative Labs                    | 7         | 0.69%   |
| Logitech                         | 6         | 0.59%   |
| Generalplus Technology           | 5         | 0.49%   |
| Texas Instruments                | 4         | 0.39%   |
| Silicon Integrated Systems [SiS] | 4         | 0.39%   |
| Razer USA                        | 4         | 0.39%   |
| Creative Technology              | 4         | 0.39%   |
| Kingston Technology              | 3         | 0.29%   |
| JMTek                            | 3         | 0.29%   |
| VIA Technologies                 | 2         | 0.2%    |
| Focusrite-Novation               | 2         | 0.2%    |
| Corsair                          | 2         | 0.2%    |
| Arturia                          | 2         | 0.2%    |
| Apple                            | 2         | 0.2%    |
| Unknown                          | 1         | 0.1%    |
| Trust                            | 1         | 0.1%    |
| Synaptics                        | 1         | 0.1%    |
| Shenzhen Riitek Technology       | 1         | 0.1%    |
| Realtek Semiconductor            | 1         | 0.1%    |
| PreSonus Audio Electronics       | 1         | 0.1%    |
| Plantronics                      | 1         | 0.1%    |
| Pixart Imaging                   | 1         | 0.1%    |
| Native Instruments               | 1         | 0.1%    |
| Microsoft                        | 1         | 0.1%    |
| Micro Star International         | 1         | 0.1%    |
| Medeli Electronics               | 1         | 0.1%    |
| Lenovo                           | 1         | 0.1%    |
| Hewlett-Packard                  | 1         | 0.1%    |
| GYROCOM C&C                      | 1         | 0.1%    |
| ESS Technology                   | 1         | 0.1%    |
| eMPIA Technology                 | 1         | 0.1%    |
| DigiTech                         | 1         | 0.1%    |
| Blue Microphones                 | 1         | 0.1%    |
| ATI Technologies                 | 1         | 0.1%    |
| Afatech                          | 1         | 0.1%    |
| Unknown                          | 1         | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 87        | 6.91%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 82        | 6.51%   |
| AMD FCH Azalia Controller                                                                         | 53        | 4.21%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 52        | 4.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 45        | 3.57%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 44        | 3.49%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 36        | 2.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 34        | 2.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 31        | 2.46%   |
| AMD Kabini HDMI/DP Audio                                                                          | 31        | 2.46%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 25        | 1.99%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 23        | 1.83%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 23        | 1.83%   |
| Intel 8 Series HD Audio Controller                                                                | 23        | 1.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 22        | 1.75%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 22        | 1.75%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 20        | 1.59%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 20        | 1.59%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 20        | 1.59%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 19        | 1.51%   |
| Intel Cannon Lake PCH cAVS                                                                        | 19        | 1.51%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 19        | 1.51%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 15        | 1.19%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 15        | 1.19%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 14        | 1.11%   |
| Intel Broadwell-U Audio Controller                                                                | 14        | 1.11%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 13        | 1.03%   |
| Intel Comet Lake PCH cAVS                                                                         | 13        | 1.03%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 12        | 0.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 12        | 0.95%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 11        | 0.87%   |
| Intel CM238 HD Audio Controller                                                                   | 10        | 0.79%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 10        | 0.79%   |
| AMD Wrestler HDMI Audio                                                                           | 10        | 0.79%   |
| AMD Trinity HDMI Audio Controller                                                                 | 10        | 0.79%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 9         | 0.71%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 9         | 0.71%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 9         | 0.71%   |
| AMD High Definition Audio Controller                                                              | 9         | 0.71%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 9         | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 126       | 26.53%  |
| SK hynix            | 79        | 16.63%  |
| Micron Technology   | 57        | 12%     |
| Kingston            | 57        | 12%     |
| Crucial             | 51        | 10.74%  |
| Unknown             | 26        | 5.47%   |
| Ramaxel Technology  | 16        | 3.37%   |
| Corsair             | 15        | 3.16%   |
| A-DATA Technology   | 9         | 1.89%   |
| G.Skill             | 6         | 1.26%   |
| Avant               | 5         | 1.05%   |
| Patriot             | 3         | 0.63%   |
| Nanya Technology    | 3         | 0.63%   |
| Elpida              | 3         | 0.63%   |
| Unknown (ABCD)      | 2         | 0.42%   |
| Unknown             | 2         | 0.42%   |
| Unknown (090E)      | 1         | 0.21%   |
| Unknown (08C8)      | 1         | 0.21%   |
| Team                | 1         | 0.21%   |
| Smart               | 1         | 0.21%   |
| PNY                 | 1         | 0.21%   |
| Lexar               | 1         | 0.21%   |
| Kreton              | 1         | 0.21%   |
| Kllisre             | 1         | 0.21%   |
| Hikvision           | 1         | 0.21%   |
| Goldenmars          | 1         | 0.21%   |
| GLOWAY              | 1         | 0.21%   |
| Atermiter           | 1         | 0.21%   |
| ASint Technology    | 1         | 0.21%   |
| Ankowall            | 1         | 0.21%   |
| 48spaces            | 1         | 0.21%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 11        | 2.19%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 6         | 1.2%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 1.2%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 1%      |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 1%      |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 1%      |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 1%      |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 5         | 1%      |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 4         | 0.8%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.8%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.8%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.8%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 0.8%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.8%    |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 4         | 0.8%    |
| Micron RAM 8KTF51264HZ-1G6N1 4096MB SODIMM DDR3 1600MT/s         | 4         | 0.8%    |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 4         | 0.8%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 4         | 0.8%    |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 4         | 0.8%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.6%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.6%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 3         | 0.6%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.6%    |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.6%    |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 3         | 0.6%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 3         | 0.6%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.6%    |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3266MT/s              | 3         | 0.6%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 3         | 0.6%    |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s              | 3         | 0.6%    |
| Crucial RAM CT8G4SFRA32A.M8FRS 8GB SODIMM DDR4 3200MT/s          | 3         | 0.6%    |
| Unknown RAM Module 8192MB DIMM 1600MT/s                          | 2         | 0.4%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 2         | 0.4%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 0.4%    |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 2         | 0.4%    |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 2         | 0.4%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.4%    |
| SK hynix RAM HMT41GS6DFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.4%    |
| SK hynix RAM HMAB2GS6AMR6N-XN 16384MB SODIMM DDR4 3200MT/s       | 2         | 0.4%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 2         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 188       | 49.09%  |
| DDR3    | 134       | 34.99%  |
| LPDDR4  | 17        | 4.44%   |
| DDR2    | 14        | 3.66%   |
| LPDDR3  | 13        | 3.39%   |
| SDRAM   | 10        | 2.61%   |
| Unknown | 3         | 0.78%   |
| DDR     | 2         | 0.52%   |
| RAM     | 1         | 0.26%   |
| LPDDR5  | 1         | 0.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 257       | 68.17%  |
| DIMM         | 90        | 23.87%  |
| Row Of Chips | 29        | 7.69%   |
| Unknown      | 1         | 0.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 166       | 39.06%  |
| 4096  | 156       | 36.71%  |
| 2048  | 46        | 10.82%  |
| 16384 | 45        | 10.59%  |
| 32768 | 6         | 1.41%   |
| 1024  | 5         | 1.18%   |
| 64    | 1         | 0.24%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 94        | 21.61%  |
| 2667    | 74        | 17.01%  |
| 3200    | 51        | 11.72%  |
| 2400    | 41        | 9.43%   |
| 2133    | 31        | 7.13%   |
| 1333    | 24        | 5.52%   |
| 3266    | 14        | 3.22%   |
| 1334    | 14        | 3.22%   |
| 667     | 11        | 2.53%   |
| 4267    | 9         | 2.07%   |
| 3600    | 8         | 1.84%   |
| Unknown | 8         | 1.84%   |
| 800     | 6         | 1.38%   |
| 3466    | 5         | 1.15%   |
| 1067    | 4         | 0.92%   |
| 4199    | 3         | 0.69%   |
| 2933    | 3         | 0.69%   |
| 2666    | 3         | 0.69%   |
| 2048    | 3         | 0.69%   |
| 1867    | 3         | 0.69%   |
| 1866    | 3         | 0.69%   |
| 1066    | 3         | 0.69%   |
| 933     | 3         | 0.69%   |
| 4266    | 2         | 0.46%   |
| 3733    | 2         | 0.46%   |
| 3400    | 2         | 0.46%   |
| 975     | 2         | 0.46%   |
| 8400    | 1         | 0.23%   |
| 6400    | 1         | 0.23%   |
| 4000    | 1         | 0.23%   |
| 3800    | 1         | 0.23%   |
| 3666    | 1         | 0.23%   |
| 3134    | 1         | 0.23%   |
| 3000    | 1         | 0.23%   |
| 2800    | 1         | 0.23%   |
| 533     | 1         | 0.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 6         | 30%     |
| Brother Industries  | 5         | 25%     |
| Seiko Epson         | 4         | 20%     |
| Canon               | 4         | 20%     |
| QinHeng Electronics | 1         | 5%      |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                      | Computers | Percent |
|----------------------------|-----------|---------|
| Brother HL-1200 series     | 3         | 15%     |
| Brother DCP-1600           | 2         | 10%     |
| Seiko Epson XP-2100 Series | 1         | 5%      |
| Seiko Epson Printer        | 1         | 5%      |
| Seiko Epson L355 Series    | 1         | 5%      |
| Seiko Epson ET-2710 Series | 1         | 5%      |
| QinHeng CH340S             | 1         | 5%      |
| HP Officejet 4500 G510a-f  | 1         | 5%      |
| HP LaserJet P1005          | 1         | 5%      |
| HP DeskJet 5820 series     | 1         | 5%      |
| HP Deskjet 4640 series     | 1         | 5%      |
| HP Deskjet 4620 series     | 1         | 5%      |
| HP DeskJet 2130 series     | 1         | 5%      |
| Canon PIXMA MP250          | 1         | 5%      |
| Canon MF110/910 Series     | 1         | 5%      |
| Canon G2000 series         | 1         | 5%      |
| Canon G1000 series         | 1         | 5%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 50%     |
| Canon       | 2         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo]   | 1         | 25%     |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1         | 25%     |
| Canon CanoScan LiDE 110                       | 1         | 25%     |
| Canon CanoScan D1250U2                        | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 134       | 22.41%  |
| IMC Networks                           | 72        | 12.04%  |
| Realtek Semiconductor                  | 43        | 7.19%   |
| Cheng Uei Precision Industry (Foxlink) | 41        | 6.86%   |
| Microdia                               | 39        | 6.52%   |
| Sunplus Innovation Technology          | 31        | 5.18%   |
| Acer                                   | 25        | 4.18%   |
| Quanta                                 | 24        | 4.01%   |
| Suyin                                  | 22        | 3.68%   |
| Lite-On Technology                     | 22        | 3.68%   |
| Silicon Motion                         | 16        | 2.68%   |
| Apple                                  | 15        | 2.51%   |
| Logitech                               | 14        | 2.34%   |
| Syntek                                 | 10        | 1.67%   |
| Luxvisions Innotech Limited            | 9         | 1.51%   |
| Generalplus Technology                 | 7         | 1.17%   |
| Z-Star Microelectronics                | 6         | 1%      |
| Alcor Micro                            | 5         | 0.84%   |
| Ricoh                                  | 4         | 0.67%   |
| Lenovo                                 | 4         | 0.67%   |
| Importek                               | 4         | 0.67%   |
| Bison Electronics                      | 4         | 0.67%   |
| Samsung Electronics                    | 3         | 0.5%    |
| Microsoft                              | 3         | 0.5%    |
| KYE Systems (Mouse Systems)            | 3         | 0.5%    |
| Jieli Technology                       | 3         | 0.5%    |
| YGTek                                  | 2         | 0.33%   |
| Unknown                                | 2         | 0.33%   |
| SunplusIT                              | 2         | 0.33%   |
| Sonix Technology                       | 2         | 0.33%   |
| OmniVision Technologies                | 2         | 0.33%   |
| Leap Motion                            | 2         | 0.33%   |
| Huawei Technologies                    | 2         | 0.33%   |
| Foxconn / Hon Hai                      | 2         | 0.33%   |
| DigiTech                               | 2         | 0.33%   |
| ALi                                    | 2         | 0.33%   |
| webcam                                 | 1         | 0.17%   |
| USB Camera CS                          | 1         | 0.17%   |
| Sunplus Technology                     | 1         | 0.17%   |
| SN0002                                 | 1         | 0.17%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                               | 30        | 4.98%   |
| IMC Networks Integrated Camera                                  | 14        | 2.32%   |
| Chicony Integrated Camera                                       | 14        | 2.32%   |
| Chicony HD WebCam                                               | 13        | 2.16%   |
| Realtek Integrated_Webcam_HD                                    | 10        | 1.66%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 9         | 1.49%   |
| Chicony HP Wide Vision HD Camera                                | 9         | 1.49%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 9         | 1.49%   |
| Microdia Integrated_Webcam_HD                                   | 8         | 1.33%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 8         | 1.33%   |
| Chicony EasyCamera                                              | 8         | 1.33%   |
| Realtek HP Truevision HD                                        | 7         | 1.16%   |
| Lite-On Integrated Camera                                       | 7         | 1.16%   |
| Lite-On HP Wide Vision HD Camera                                | 7         | 1.16%   |
| Generalplus GENERAL WEBCAM                                      | 7         | 1.16%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                 | 7         | 1.16%   |
| Acer Integrated Camera                                          | 7         | 1.16%   |
| Suyin HP TrueVision HD                                          | 6         | 1%      |
| Chicony VGA WebCam                                              | 6         | 1%      |
| Chicony HP Webcam                                               | 6         | 1%      |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 6         | 1%      |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                | 6         | 1%      |
| Syntek Integrated Camera                                        | 5         | 0.83%   |
| Sunplus HP TrueVision HD Camera                                 | 5         | 0.83%   |
| Microdia Webcam Vitade AF                                       | 5         | 0.83%   |
| Microdia HP Webcam                                              | 5         | 0.83%   |
| Chicony HP Truevision HD camera                                 | 5         | 0.83%   |
| Chicony HP Truevision HD                                        | 5         | 0.83%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 5         | 0.83%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD         | 5         | 0.83%   |
| Acer EasyCamera                                                 | 5         | 0.83%   |
| Sunplus Laptop Integrated WebCam HD                             | 4         | 0.66%   |
| Silicon Motion WebCam SCB-1100N                                 | 4         | 0.66%   |
| Realtek HP "Truevision HD" laptop camera                        | 4         | 0.66%   |
| Quanta VGA WebCam                                               | 4         | 0.66%   |
| Quanta HP TrueVision HD Camera                                  | 4         | 0.66%   |
| Quanta HD User Facing                                           | 4         | 0.66%   |
| Logitech Webcam C270                                            | 4         | 0.66%   |
| Logitech C922 Pro Stream Webcam                                 | 4         | 0.66%   |
| Lite-On HP HD Camera                                            | 4         | 0.66%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 35        | 42.17%  |
| Synaptics                  | 19        | 22.89%  |
| Shenzhen Goodix Technology | 9         | 10.84%  |
| AuthenTec                  | 6         | 7.23%   |
| Elan Microelectronics      | 5         | 6.02%   |
| Upek                       | 3         | 3.61%   |
| LighTuning Technology      | 3         | 3.61%   |
| STMicroelectronics         | 2         | 2.41%   |
| Focal-systems.Corp         | 1         | 1.2%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 8.43%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 7         | 8.43%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 7.23%   |
| Shenzhen Goodix  FingerPrint Device                                        | 6         | 7.23%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 5         | 6.02%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 6.02%   |
| AuthenTec AES2810                                                          | 4         | 4.82%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 3.61%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 3.61%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 3.61%   |
| Synaptics  WBDI                                                            | 3         | 3.61%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 3.61%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 3.61%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 3.61%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 3.61%   |
| Elan ELAN:ARM-M4                                                           | 3         | 3.61%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 2.41%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 2.41%   |
| Elan ELAN:Fingerprint                                                      | 2         | 2.41%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.2%    |
| Validity Sensors VFS491                                                    | 1         | 1.2%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 1.2%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 1.2%    |
| Synaptics WBDI                                                             | 1         | 1.2%    |
| Synaptics UWP WBDI                                                         | 1         | 1.2%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.2%    |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 1.2%    |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.2%    |
| AuthenTec AES1600                                                          | 1         | 1.2%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 14        | 82.35%  |
| O2 Micro | 2         | 11.76%  |
| Upek     | 1         | 5.88%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 29.41%  |
| Broadcom 5880                                                                | 5         | 29.41%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 17.65%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 5.88%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 5.88%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 5.88%   |
| Broadcom 58200                                                               | 1         | 5.88%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 587       | 71.5%   |
| 1     | 194       | 23.63%  |
| 2     | 34        | 4.14%   |
| 3     | 4         | 0.49%   |
| 5     | 1         | 0.12%   |
| 4     | 1         | 0.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 83        | 30.97%  |
| Graphics card            | 60        | 22.39%  |
| Net/wireless             | 42        | 15.67%  |
| Multimedia controller    | 16        | 5.97%   |
| Chipcard                 | 16        | 5.97%   |
| Bluetooth                | 14        | 5.22%   |
| Communication controller | 9         | 3.36%   |
| Unassigned class         | 7         | 2.61%   |
| Camera                   | 5         | 1.87%   |
| Storage                  | 4         | 1.49%   |
| Sound                    | 4         | 1.49%   |
| Net/ethernet             | 3         | 1.12%   |
| Network                  | 2         | 0.75%   |
| Card reader              | 2         | 0.75%   |
| Firewire controller      | 1         | 0.37%   |


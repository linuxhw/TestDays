Debian 11 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Debian 11 (Beta test).

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Debian_11/Desktop/README.md) and [notebooks](/Dist/Debian_11/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=debian-11

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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
  - [ Dual Boot with Linux/BSD ](#dual-boot-with-linux-bsd)
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

* [ Printers & scanners ](#printers-scanners)
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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Google        | Stout                       | Notebook    | [e4463bb3d4](https://linux-hardware.org/?probe=e4463bb3d4) | Aug 02, 2021 |
| Fujitsu       | LIFEBOOK T5010              | Notebook    | [75a544682e](https://linux-hardware.org/?probe=75a544682e) | Aug 02, 2021 |
| Google        | Enguarde                    | Notebook    | [09406c6908](https://linux-hardware.org/?probe=09406c6908) | Aug 02, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [01315f2df2](https://linux-hardware.org/?probe=01315f2df2) | Aug 02, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [e6ca37026c](https://linux-hardware.org/?probe=e6ca37026c) | Aug 02, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [70647a7f66](https://linux-hardware.org/?probe=70647a7f66) | Aug 02, 2021 |
| ASRock        | H310CM-DVS                  | Desktop     | [f84e5eba5a](https://linux-hardware.org/?probe=f84e5eba5a) | Aug 02, 2021 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [e90a873ad0](https://linux-hardware.org/?probe=e90a873ad0) | Aug 02, 2021 |
| ASUSTek       | P5QL-E                      | Desktop     | [2894e88095](https://linux-hardware.org/?probe=2894e88095) | Aug 02, 2021 |
| Dell          | Inspiron 7391               | Notebook    | [c4ac48e264](https://linux-hardware.org/?probe=c4ac48e264) | Aug 02, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [ace43d8e9f](https://linux-hardware.org/?probe=ace43d8e9f) | Aug 02, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [384ffe1123](https://linux-hardware.org/?probe=384ffe1123) | Aug 02, 2021 |
| ASUSTek       | A88X-PRO                    | Desktop     | [ed95430eec](https://linux-hardware.org/?probe=ed95430eec) | Aug 02, 2021 |
| HP            | 2187 A01                    | Desktop     | [16bfdd86e3](https://linux-hardware.org/?probe=16bfdd86e3) | Aug 02, 2021 |
| Lenovo        | ThinkPad L520 5016NU7       | Notebook    | [101a0ca1b3](https://linux-hardware.org/?probe=101a0ca1b3) | Aug 01, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [61886d812f](https://linux-hardware.org/?probe=61886d812f) | Aug 01, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [9c7fb8e911](https://linux-hardware.org/?probe=9c7fb8e911) | Aug 01, 2021 |
| Lenovo        | ThinkPad L520 5016NU7       | Notebook    | [08fe25ec71](https://linux-hardware.org/?probe=08fe25ec71) | Aug 01, 2021 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [8f40021fde](https://linux-hardware.org/?probe=8f40021fde) | Aug 01, 2021 |
| ASRock        | J1900D2Y                    | Desktop     | [0dc4afc8c4](https://linux-hardware.org/?probe=0dc4afc8c4) | Aug 01, 2021 |
| Lenovo        | ThinkPad Edge E330 3354D... | Notebook    | [9c317f536b](https://linux-hardware.org/?probe=9c317f536b) | Aug 01, 2021 |
| ASUSTek       | ROG Strix G731GT_G731GT     | Notebook    | [f851abbdf5](https://linux-hardware.org/?probe=f851abbdf5) | Aug 01, 2021 |
| ASRock        | N68C-S UCC                  | Desktop     | [3da0d57fd5](https://linux-hardware.org/?probe=3da0d57fd5) | Aug 01, 2021 |
| Dell          | 0WVYMC A00                  | Desktop     | [4d2aa42e3c](https://linux-hardware.org/?probe=4d2aa42e3c) | Jul 31, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [5b89a99ad8](https://linux-hardware.org/?probe=5b89a99ad8) | Jul 31, 2021 |
| Dell          | Vostro 5502                 | Notebook    | [f1e6f11078](https://linux-hardware.org/?probe=f1e6f11078) | Jul 31, 2021 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [159ff0ba7f](https://linux-hardware.org/?probe=159ff0ba7f) | Jul 31, 2021 |
| HP            | OMEN by HP Laptop 15-dc0... | Notebook    | [60f065b770](https://linux-hardware.org/?probe=60f065b770) | Jul 31, 2021 |
| ASRock        | Z370M-ITX/ac                | Desktop     | [30511d93c4](https://linux-hardware.org/?probe=30511d93c4) | Jul 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [b62fb400bf](https://linux-hardware.org/?probe=b62fb400bf) | Jul 31, 2021 |
| Acer          | Aspire 7720                 | Notebook    | [6472272bf7](https://linux-hardware.org/?probe=6472272bf7) | Jul 30, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | Notebook    | [b16533813f](https://linux-hardware.org/?probe=b16533813f) | Jul 30, 2021 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [3f0c3901f6](https://linux-hardware.org/?probe=3f0c3901f6) | Jul 30, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0A60... | Notebook    | [8a3c585de4](https://linux-hardware.org/?probe=8a3c585de4) | Jul 30, 2021 |
| Lenovo        | ThinkPad T450s 20BX004QG... | Notebook    | [a46cb950a4](https://linux-hardware.org/?probe=a46cb950a4) | Jul 29, 2021 |
| MSI           | Z490-A PRO                  | Desktop     | [b882a9cf0d](https://linux-hardware.org/?probe=b882a9cf0d) | Jul 29, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [370cea169d](https://linux-hardware.org/?probe=370cea169d) | Jul 29, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [a5a9ca4678](https://linux-hardware.org/?probe=a5a9ca4678) | Jul 29, 2021 |
| MSI           | Q45MDO                      | Desktop     | [ab547f0047](https://linux-hardware.org/?probe=ab547f0047) | Jul 29, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [55c54d17ad](https://linux-hardware.org/?probe=55c54d17ad) | Jul 29, 2021 |
| MSI           | Q45MDO                      | Desktop     | [6b5aaa6969](https://linux-hardware.org/?probe=6b5aaa6969) | Jul 29, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [1bb07ffc9f](https://linux-hardware.org/?probe=1bb07ffc9f) | Jul 29, 2021 |
| Dell          | 0TY915                      | Desktop     | [9cb5aed659](https://linux-hardware.org/?probe=9cb5aed659) | Jul 29, 2021 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [ed7394c65a](https://linux-hardware.org/?probe=ed7394c65a) | Jul 29, 2021 |
| ASUSTek       | LEONITE                     | Desktop     | [3bf9048839](https://linux-hardware.org/?probe=3bf9048839) | Jul 29, 2021 |
| Foxconn       | 2AA9                        | Desktop     | [920a813aaf](https://linux-hardware.org/?probe=920a813aaf) | Jul 29, 2021 |
| SLIMBOOK      | PROX14-AMD                  | Notebook    | [16aeb37a86](https://linux-hardware.org/?probe=16aeb37a86) | Jul 29, 2021 |
| ASRock        | B85M Pro4                   | Desktop     | [32e615b538](https://linux-hardware.org/?probe=32e615b538) | Jul 29, 2021 |
| Acer          | Nitro AN517-41              | Notebook    | [ccc850c1da](https://linux-hardware.org/?probe=ccc850c1da) | Jul 29, 2021 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [f449b8ce85](https://linux-hardware.org/?probe=f449b8ce85) | Jul 29, 2021 |
| Lenovo        | ThinkPad T420s 4174PEG      | Notebook    | [e448710e41](https://linux-hardware.org/?probe=e448710e41) | Jul 28, 2021 |
| ECS           | H61H2-M12                   | Desktop     | [42050ab984](https://linux-hardware.org/?probe=42050ab984) | Jul 28, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [89d3c0f09d](https://linux-hardware.org/?probe=89d3c0f09d) | Jul 28, 2021 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [cccaebb483](https://linux-hardware.org/?probe=cccaebb483) | Jul 28, 2021 |
| HP            | OMEN by HP Laptop 17-cb1... | Notebook    | [bee4fd945a](https://linux-hardware.org/?probe=bee4fd945a) | Jul 28, 2021 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [4206886abb](https://linux-hardware.org/?probe=4206886abb) | Jul 28, 2021 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [d244dc6763](https://linux-hardware.org/?probe=d244dc6763) | Jul 28, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [f96bcc3ab2](https://linux-hardware.org/?probe=f96bcc3ab2) | Jul 28, 2021 |
| ZOTAC         | ZBOX-EN1070/1060,EN1070K... | Mini pc     | [cc099348c2](https://linux-hardware.org/?probe=cc099348c2) | Jul 28, 2021 |
| Lenovo        | ThinkPad T470 20HES1UD00    | Notebook    | [6034f6a417](https://linux-hardware.org/?probe=6034f6a417) | Jul 28, 2021 |
| Lenovo        | ThinkPad X230 2325BQ3       | Notebook    | [79a19ade20](https://linux-hardware.org/?probe=79a19ade20) | Jul 28, 2021 |
| Dell          | Inspiron 8600               | Notebook    | [2f49d18738](https://linux-hardware.org/?probe=2f49d18738) | Jul 28, 2021 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [abdeaec5ce](https://linux-hardware.org/?probe=abdeaec5ce) | Jul 28, 2021 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [5258847421](https://linux-hardware.org/?probe=5258847421) | Jul 28, 2021 |
| Lenovo        | ThinkPad T490 20RYCTO1WW    | Notebook    | [60c16ed267](https://linux-hardware.org/?probe=60c16ed267) | Jul 28, 2021 |
| Shuttle       | FX79R                       | Desktop     | [6ceba6fc67](https://linux-hardware.org/?probe=6ceba6fc67) | Jul 28, 2021 |
| Acer          | Swift SF313-52G             | Notebook    | [87add43827](https://linux-hardware.org/?probe=87add43827) | Jul 28, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [df0a4b1a0f](https://linux-hardware.org/?probe=df0a4b1a0f) | Jul 27, 2021 |
| Casper        | C17B                        | Notebook    | [6f56921ba5](https://linux-hardware.org/?probe=6f56921ba5) | Jul 27, 2021 |
| ASRockRack    | X570D4U-2L2T                | Desktop     | [7bb34c9dec](https://linux-hardware.org/?probe=7bb34c9dec) | Jul 27, 2021 |
| Lenovo        | ThinkPad X240 20AL008EUK    | Notebook    | [367150f04f](https://linux-hardware.org/?probe=367150f04f) | Jul 27, 2021 |
| HP            | Laptop 17-by0xxx            | Notebook    | [0cb6fde0ef](https://linux-hardware.org/?probe=0cb6fde0ef) | Jul 27, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [bc4f8acaf2](https://linux-hardware.org/?probe=bc4f8acaf2) | Jul 27, 2021 |
| ASUSTek       | A88X-PLUS/USB               | Desktop     | [57b54cc925](https://linux-hardware.org/?probe=57b54cc925) | Jul 27, 2021 |
| ASRock        | N68C-GS FX                  | Desktop     | [660f13d25d](https://linux-hardware.org/?probe=660f13d25d) | Jul 27, 2021 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [2e0f5417fc](https://linux-hardware.org/?probe=2e0f5417fc) | Jul 27, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [7821dfc370](https://linux-hardware.org/?probe=7821dfc370) | Jul 27, 2021 |
| ASUSTek       | M4A785D-M PRO               | Desktop     | [467d107518](https://linux-hardware.org/?probe=467d107518) | Jul 27, 2021 |
| Foxconn       | 915MH Series                | Desktop     | [6a3ae85dfc](https://linux-hardware.org/?probe=6a3ae85dfc) | Jul 27, 2021 |
| HP            | ProBook 635 Aero G7 Note... | Notebook    | [e6ee486690](https://linux-hardware.org/?probe=e6ee486690) | Jul 27, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [dc4a709a3b](https://linux-hardware.org/?probe=dc4a709a3b) | Jul 27, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [b24fc8e5f2](https://linux-hardware.org/?probe=b24fc8e5f2) | Jul 27, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [2a645d9cba](https://linux-hardware.org/?probe=2a645d9cba) | Jul 27, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [1e69873301](https://linux-hardware.org/?probe=1e69873301) | Jul 27, 2021 |
| Lenovo        | IdeaPad S540-13ITL 82H1     | Notebook    | [730c33a1b0](https://linux-hardware.org/?probe=730c33a1b0) | Jul 27, 2021 |
| Lenovo        | ThinkPad E14 20RAS13M00     | Notebook    | [b46ca83c19](https://linux-hardware.org/?probe=b46ca83c19) | Jul 27, 2021 |
| Dell          | Latitude 7480               | Notebook    | [0c79ad3dd4](https://linux-hardware.org/?probe=0c79ad3dd4) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | Notebook    | [5b2e06697e](https://linux-hardware.org/?probe=5b2e06697e) | Jul 27, 2021 |
| Dell          | 0M863N A00                  | Desktop     | [e94bee6137](https://linux-hardware.org/?probe=e94bee6137) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | Notebook    | [567612e805](https://linux-hardware.org/?probe=567612e805) | Jul 27, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [0172934285](https://linux-hardware.org/?probe=0172934285) | Jul 27, 2021 |
| Gigabyte      | P35C-DS3R                   | Desktop     | [e8ffe8991b](https://linux-hardware.org/?probe=e8ffe8991b) | Jul 27, 2021 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [3c6898fcd8](https://linux-hardware.org/?probe=3c6898fcd8) | Jul 27, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [f3878ff548](https://linux-hardware.org/?probe=f3878ff548) | Jul 27, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [9d0528280a](https://linux-hardware.org/?probe=9d0528280a) | Jul 26, 2021 |
| Apple         | MacBookPro11,4              | Notebook    | [d58bb90557](https://linux-hardware.org/?probe=d58bb90557) | Jul 26, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [1bbe185e86](https://linux-hardware.org/?probe=1bbe185e86) | Jul 26, 2021 |
| Lenovo        | ThinkPad E14 20RA001HRT     | Notebook    | [f7175e6651](https://linux-hardware.org/?probe=f7175e6651) | Jul 26, 2021 |
| Quanta        | TWC                         | Notebook    | [1ecec0372f](https://linux-hardware.org/?probe=1ecec0372f) | Jul 26, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [2f259b4ae2](https://linux-hardware.org/?probe=2f259b4ae2) | Jul 26, 2021 |
| ASRock        | Z97 Pro3                    | Desktop     | [8cd14c1874](https://linux-hardware.org/?probe=8cd14c1874) | Jul 26, 2021 |
| Dell          | Vostro 5471                 | Notebook    | [73c1da1908](https://linux-hardware.org/?probe=73c1da1908) | Jul 26, 2021 |
| ASUSTek       | ZenBook Q536FD_Q536FD       | Convertible | [52e5d3e16d](https://linux-hardware.org/?probe=52e5d3e16d) | Jul 26, 2021 |
| MSI           | Z370 SLI PLUS               | Desktop     | [04d84e38b8](https://linux-hardware.org/?probe=04d84e38b8) | Jul 26, 2021 |
| Intel         | NUC6i7KYB H90766-402        | Mini pc     | [e7aeecff98](https://linux-hardware.org/?probe=e7aeecff98) | Jul 26, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [eaedf12907](https://linux-hardware.org/?probe=eaedf12907) | Jul 26, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [8bfc663f48](https://linux-hardware.org/?probe=8bfc663f48) | Jul 26, 2021 |
| HP            | ProBook 470 G3              | Notebook    | [cb1b02b979](https://linux-hardware.org/?probe=cb1b02b979) | Jul 26, 2021 |
| ASUSTek       | 701                         | Notebook    | [db72d4004a](https://linux-hardware.org/?probe=db72d4004a) | Jul 26, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [eb6369aac9](https://linux-hardware.org/?probe=eb6369aac9) | Jul 26, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [0de4a63af4](https://linux-hardware.org/?probe=0de4a63af4) | Jul 26, 2021 |
| HP            | 2B38                        | Desktop     | [be24f3f652](https://linux-hardware.org/?probe=be24f3f652) | Jul 26, 2021 |
| HP            | 2B38                        | Desktop     | [c1198b90f6](https://linux-hardware.org/?probe=c1198b90f6) | Jul 26, 2021 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [9fd8d25e24](https://linux-hardware.org/?probe=9fd8d25e24) | Jul 26, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [8b0f398a93](https://linux-hardware.org/?probe=8b0f398a93) | Jul 26, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [cd62d88495](https://linux-hardware.org/?probe=cd62d88495) | Jul 26, 2021 |
| ASUSTek       | 1215B                       | Notebook    | [ce53b40511](https://linux-hardware.org/?probe=ce53b40511) | Jul 26, 2021 |
| Dell          | Latitude E6420              | Notebook    | [01000461fc](https://linux-hardware.org/?probe=01000461fc) | Jul 26, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [b040663b7c](https://linux-hardware.org/?probe=b040663b7c) | Jul 26, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [36caa67715](https://linux-hardware.org/?probe=36caa67715) | Jul 26, 2021 |
| Dell          | Studio 1555                 | Notebook    | [30b17f2421](https://linux-hardware.org/?probe=30b17f2421) | Jul 26, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [e9ddc17233](https://linux-hardware.org/?probe=e9ddc17233) | Jul 26, 2021 |
| Lenovo        | ThinkPad E14 20RA0036RT     | Notebook    | [e4f29039a8](https://linux-hardware.org/?probe=e4f29039a8) | Jul 26, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [6623f96b90](https://linux-hardware.org/?probe=6623f96b90) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [2c05790c36](https://linux-hardware.org/?probe=2c05790c36) | Jul 26, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [c676ac21ee](https://linux-hardware.org/?probe=c676ac21ee) | Jul 26, 2021 |
| ASUSTek       | 701SD                       | Notebook    | [b7c888a9a7](https://linux-hardware.org/?probe=b7c888a9a7) | Jul 26, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [64b4d84778](https://linux-hardware.org/?probe=64b4d84778) | Jul 26, 2021 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [fffec5c87f](https://linux-hardware.org/?probe=fffec5c87f) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [0b35b55294](https://linux-hardware.org/?probe=0b35b55294) | Jul 26, 2021 |
| Dell          | 0D28YY A02                  | Desktop     | [71b0f194a3](https://linux-hardware.org/?probe=71b0f194a3) | Jul 26, 2021 |
| ASRock        | H470M-ITX/ac                | Desktop     | [8a3b6cb663](https://linux-hardware.org/?probe=8a3b6cb663) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | Notebook    | [a145aa9a69](https://linux-hardware.org/?probe=a145aa9a69) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [fcd103f100](https://linux-hardware.org/?probe=fcd103f100) | Jul 26, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [00d53058e7](https://linux-hardware.org/?probe=00d53058e7) | Jul 26, 2021 |
| ASUSTek       | X541NC                      | Notebook    | [500a26f588](https://linux-hardware.org/?probe=500a26f588) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | Notebook    | [08eec2f3a7](https://linux-hardware.org/?probe=08eec2f3a7) | Jul 25, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [ec1cea0d9d](https://linux-hardware.org/?probe=ec1cea0d9d) | Jul 25, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [92cd785445](https://linux-hardware.org/?probe=92cd785445) | Jul 25, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [d09fdc110f](https://linux-hardware.org/?probe=d09fdc110f) | Jul 25, 2021 |
| Lenovo        | ThinkPad T460 20FMS03600    | Notebook    | [84f380e2a2](https://linux-hardware.org/?probe=84f380e2a2) | Jul 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [4454739a42](https://linux-hardware.org/?probe=4454739a42) | Jul 25, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3UX0... | Notebook    | [abced1dd83](https://linux-hardware.org/?probe=abced1dd83) | Jul 25, 2021 |
| Lenovo        | ThinkPad E480 20KN001NGE    | Notebook    | [e3b2914d19](https://linux-hardware.org/?probe=e3b2914d19) | Jul 25, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [1e2b68b7d8](https://linux-hardware.org/?probe=1e2b68b7d8) | Jul 25, 2021 |
| Toshiba       | Satellite C45-A             | Notebook    | [0497ab613d](https://linux-hardware.org/?probe=0497ab613d) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236WNU       | Notebook    | [d817abc511](https://linux-hardware.org/?probe=d817abc511) | Jul 25, 2021 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [11c5d6c6d0](https://linux-hardware.org/?probe=11c5d6c6d0) | Jul 25, 2021 |
| Dell          | 0PTTT9 A00                  | Desktop     | [113235448d](https://linux-hardware.org/?probe=113235448d) | Jul 25, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [54b46bdd5d](https://linux-hardware.org/?probe=54b46bdd5d) | Jul 25, 2021 |
| HP            | ProBook x360 11 G1 EE       | Notebook    | [90aeea53cc](https://linux-hardware.org/?probe=90aeea53cc) | Jul 25, 2021 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [21b43b8718](https://linux-hardware.org/?probe=21b43b8718) | Jul 25, 2021 |
| Gigabyte      | Z170M-D3H-CF                | Desktop     | [9301420a7b](https://linux-hardware.org/?probe=9301420a7b) | Jul 25, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [5c61fdfb49](https://linux-hardware.org/?probe=5c61fdfb49) | Jul 25, 2021 |
| ASRock        | P67 Pro3                    | Desktop     | [ce711e5011](https://linux-hardware.org/?probe=ce711e5011) | Jul 25, 2021 |
| Supermicro    | A1SA2-2750FA                | Desktop     | [de408d6408](https://linux-hardware.org/?probe=de408d6408) | Jul 25, 2021 |
| Gigabyte      | H87-HD3                     | Desktop     | [a102014ef0](https://linux-hardware.org/?probe=a102014ef0) | Jul 25, 2021 |
| Dell          | Latitude E5520              | Notebook    | [0d74f57317](https://linux-hardware.org/?probe=0d74f57317) | Jul 25, 2021 |
| Dell          | Latitude E5520              | Notebook    | [5866765bab](https://linux-hardware.org/?probe=5866765bab) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [dcff1a4a95](https://linux-hardware.org/?probe=dcff1a4a95) | Jul 25, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [8b1c4f962a](https://linux-hardware.org/?probe=8b1c4f962a) | Jul 25, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ab8a90e145](https://linux-hardware.org/?probe=ab8a90e145) | Jul 25, 2021 |
| IBM           | I/O Port                    | Server      | [8538814cd6](https://linux-hardware.org/?probe=8538814cd6) | Jul 25, 2021 |
| Dell          | 0Y1057                      | Desktop     | [ac342b01e2](https://linux-hardware.org/?probe=ac342b01e2) | Jul 25, 2021 |
| HP            | OMEN by HP Laptop 15-dc0... | Notebook    | [b8a2299d30](https://linux-hardware.org/?probe=b8a2299d30) | Jul 25, 2021 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [2bcfda70b5](https://linux-hardware.org/?probe=2bcfda70b5) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [514f64cef0](https://linux-hardware.org/?probe=514f64cef0) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [0d45d49199](https://linux-hardware.org/?probe=0d45d49199) | Jul 25, 2021 |
| PC Special... | NV4XMB,ME,MZ                | Notebook    | [eb789efe18](https://linux-hardware.org/?probe=eb789efe18) | Jul 25, 2021 |
| ASRock        | Z97 Extreme6                | Desktop     | [84730f7819](https://linux-hardware.org/?probe=84730f7819) | Jul 25, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [a172262124](https://linux-hardware.org/?probe=a172262124) | Jul 25, 2021 |
| Lenovo        | ThinkPad T410 2522WUZ       | Notebook    | [62cddaceb1](https://linux-hardware.org/?probe=62cddaceb1) | Jul 25, 2021 |
| Lenovo        | 3098 0B98401 PRO            | Desktop     | [a5bb2fb53c](https://linux-hardware.org/?probe=a5bb2fb53c) | Jul 25, 2021 |
| HP            | 1495                        | Desktop     | [5d01240605](https://linux-hardware.org/?probe=5d01240605) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480 20L5S1S000    | Notebook    | [1217d711fb](https://linux-hardware.org/?probe=1217d711fb) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480 20L50063EU    | Notebook    | [c59c2aa27d](https://linux-hardware.org/?probe=c59c2aa27d) | Jul 25, 2021 |
| Lenovo        | ThinkPad X201 3626ES3       | Notebook    | [c18f4c4102](https://linux-hardware.org/?probe=c18f4c4102) | Jul 25, 2021 |
| HP            | 158A                        | Desktop     | [219b010ebb](https://linux-hardware.org/?probe=219b010ebb) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2349BW1       | Notebook    | [75c4d5c7a9](https://linux-hardware.org/?probe=75c4d5c7a9) | Jul 25, 2021 |
| HP            | 158A                        | Desktop     | [da4016cb27](https://linux-hardware.org/?probe=da4016cb27) | Jul 25, 2021 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | Notebook    | [59533bd2bf](https://linux-hardware.org/?probe=59533bd2bf) | Jul 25, 2021 |
| Acer          | Aspire 5735                 | Notebook    | [60451d6f55](https://linux-hardware.org/?probe=60451d6f55) | Jul 25, 2021 |
| Fujitsu       | LIFEBOOK AH532/G52          | Notebook    | [4e8d8d9253](https://linux-hardware.org/?probe=4e8d8d9253) | Jul 25, 2021 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [a98eb4deab](https://linux-hardware.org/?probe=a98eb4deab) | Jul 25, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [a778d78c98](https://linux-hardware.org/?probe=a778d78c98) | Jul 25, 2021 |
| Gigabyte      | H110N-CF                    | Desktop     | [2a85c9961c](https://linux-hardware.org/?probe=2a85c9961c) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236EV9       | Notebook    | [62cc86b330](https://linux-hardware.org/?probe=62cc86b330) | Jul 25, 2021 |
| MSI           | MAG B550M MORTAR            | Desktop     | [b5e7cb3f3d](https://linux-hardware.org/?probe=b5e7cb3f3d) | Jul 25, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [dd60e87813](https://linux-hardware.org/?probe=dd60e87813) | Jul 25, 2021 |
| HP            | 2129                        | Desktop     | [8de5bae655](https://linux-hardware.org/?probe=8de5bae655) | Jul 25, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [b3dca0cfaa](https://linux-hardware.org/?probe=b3dca0cfaa) | Jul 25, 2021 |
| Raspberry ... | Raspberry Pi 2 Model B R... | Soc         | [f8ad21d44a](https://linux-hardware.org/?probe=f8ad21d44a) | Jul 25, 2021 |
| HP            | 250 G5 Notebook PC          | Notebook    | [53d3003d94](https://linux-hardware.org/?probe=53d3003d94) | Jul 25, 2021 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | Notebook    | [043c5815ee](https://linux-hardware.org/?probe=043c5815ee) | Jul 25, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [a30a8b568e](https://linux-hardware.org/?probe=a30a8b568e) | Jul 25, 2021 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | Notebook    | [686f21af90](https://linux-hardware.org/?probe=686f21af90) | Jul 25, 2021 |
| Dell          | XPS L322X                   | Notebook    | [6b0ab2e22d](https://linux-hardware.org/?probe=6b0ab2e22d) | Jul 25, 2021 |
| Intel         | DP55WG AAE57269-407         | Desktop     | [fa1be73a3f](https://linux-hardware.org/?probe=fa1be73a3f) | Jul 25, 2021 |
| ASRock        | B85 Anniversary             | Desktop     | [b9bdc402ce](https://linux-hardware.org/?probe=b9bdc402ce) | Jul 25, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [db0c50510b](https://linux-hardware.org/?probe=db0c50510b) | Jul 25, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [c873d77069](https://linux-hardware.org/?probe=c873d77069) | Jul 25, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [722792ec34](https://linux-hardware.org/?probe=722792ec34) | Jul 25, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [6630c7ef27](https://linux-hardware.org/?probe=6630c7ef27) | Jul 25, 2021 |
| Lenovo        | 3110 SDK0J40697 WIN 3305... | All in one  | [84b6274afe](https://linux-hardware.org/?probe=84b6274afe) | Jul 25, 2021 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [e1db015807](https://linux-hardware.org/?probe=e1db015807) | Jul 25, 2021 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [b0f56654dc](https://linux-hardware.org/?probe=b0f56654dc) | Jul 25, 2021 |
| Dell          | Inspiron 3505               | Notebook    | [be67f17212](https://linux-hardware.org/?probe=be67f17212) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [cd13d1596f](https://linux-hardware.org/?probe=cd13d1596f) | Jul 25, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [15012d7630](https://linux-hardware.org/?probe=15012d7630) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [beec8a1c7d](https://linux-hardware.org/?probe=beec8a1c7d) | Jul 25, 2021 |
| Panasonic     | CF-AX2LDCZMF                | Notebook    | [31feab61fe](https://linux-hardware.org/?probe=31feab61fe) | Jul 25, 2021 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [3dae264c17](https://linux-hardware.org/?probe=3dae264c17) | Jul 25, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [814f91322d](https://linux-hardware.org/?probe=814f91322d) | Jul 25, 2021 |
| Dell          | Inspiron 5423               | Notebook    | [f15c87c33c](https://linux-hardware.org/?probe=f15c87c33c) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480s 20L8S7HF0... | Notebook    | [5417d20b5b](https://linux-hardware.org/?probe=5417d20b5b) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2349GCG       | Notebook    | [7275a5dc90](https://linux-hardware.org/?probe=7275a5dc90) | Jul 25, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [8e2d810033](https://linux-hardware.org/?probe=8e2d810033) | Jul 25, 2021 |
| Lenovo        | ThinkPad T450s 20BX004QG... | Notebook    | [079f1c9006](https://linux-hardware.org/?probe=079f1c9006) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [6f137bd0e5](https://linux-hardware.org/?probe=6f137bd0e5) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [94307be3d8](https://linux-hardware.org/?probe=94307be3d8) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [9e0045da76](https://linux-hardware.org/?probe=9e0045da76) | Jul 25, 2021 |
| MSI           | Modern 15 A11M              | Notebook    | [acfcaa9077](https://linux-hardware.org/?probe=acfcaa9077) | Jul 25, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [fb8dc2feb1](https://linux-hardware.org/?probe=fb8dc2feb1) | Jul 25, 2021 |
| HP            | Stream Notebook             | Notebook    | [078c5d40f8](https://linux-hardware.org/?probe=078c5d40f8) | Jul 25, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [49198ead06](https://linux-hardware.org/?probe=49198ead06) | Jul 25, 2021 |
| Compulab      | fitlet2                     | Mini pc     | [9d1571afa4](https://linux-hardware.org/?probe=9d1571afa4) | Jul 25, 2021 |
| Gigabyte      | H61MS                       | Desktop     | [742ede3c3e](https://linux-hardware.org/?probe=742ede3c3e) | Jul 25, 2021 |
| Lenovo        | ThinkPad X260 20F5S0JF00    | Notebook    | [98cbf345d9](https://linux-hardware.org/?probe=98cbf345d9) | Jul 25, 2021 |
| Gigabyte      | H81M-S2H GSM                | Desktop     | [f49c35b208](https://linux-hardware.org/?probe=f49c35b208) | Jul 25, 2021 |
| Dell          | 09KPNV A01                  | Desktop     | [fb6ec7188c](https://linux-hardware.org/?probe=fb6ec7188c) | Jul 25, 2021 |
| Dell          | Inspiron 5402               | Notebook    | [f54ac49b39](https://linux-hardware.org/?probe=f54ac49b39) | Jul 25, 2021 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [fca7acc5ee](https://linux-hardware.org/?probe=fca7acc5ee) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [10fb3b6e94](https://linux-hardware.org/?probe=10fb3b6e94) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [96fd57ba79](https://linux-hardware.org/?probe=96fd57ba79) | Jul 25, 2021 |
| Lenovo        | ThinkPad X260 20F5S46R00    | Notebook    | [c72e326772](https://linux-hardware.org/?probe=c72e326772) | Jul 25, 2021 |
| ASUSTek       | H61M-K                      | Desktop     | [1cf0bdeec4](https://linux-hardware.org/?probe=1cf0bdeec4) | Jul 25, 2021 |
| Dell          | 0NK5PH A00                  | Desktop     | [d6444ebf26](https://linux-hardware.org/?probe=d6444ebf26) | Jul 25, 2021 |
| Gigabyte      | AERO 15 KB                  | Notebook    | [d66f45fc2e](https://linux-hardware.org/?probe=d66f45fc2e) | Jul 25, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [522d784ace](https://linux-hardware.org/?probe=522d784ace) | Jul 25, 2021 |
| HP            | ProBook 640 G2              | Notebook    | [558f739aab](https://linux-hardware.org/?probe=558f739aab) | Jul 25, 2021 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [9c9e82f80f](https://linux-hardware.org/?probe=9c9e82f80f) | Jul 25, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [2c9c978361](https://linux-hardware.org/?probe=2c9c978361) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236WC3       | Notebook    | [2dbdc931e7](https://linux-hardware.org/?probe=2dbdc931e7) | Jul 25, 2021 |
| Lenovo        | ThinkPad E14 20RB000UBR     | Notebook    | [c25d549bd7](https://linux-hardware.org/?probe=c25d549bd7) | Jul 25, 2021 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [9f0fbc1613](https://linux-hardware.org/?probe=9f0fbc1613) | Jul 25, 2021 |
| Protectli     | FW6                         | Desktop     | [0efef10e76](https://linux-hardware.org/?probe=0efef10e76) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [dd3347639f](https://linux-hardware.org/?probe=dd3347639f) | Jul 25, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [f7c4474b4d](https://linux-hardware.org/?probe=f7c4474b4d) | Jul 25, 2021 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [df5c29f984](https://linux-hardware.org/?probe=df5c29f984) | Jul 25, 2021 |
| Gigabyte      | 970A-D3P                    | Desktop     | [c564faffdb](https://linux-hardware.org/?probe=c564faffdb) | Jul 25, 2021 |
| Lenovo        | Yoga 710-11ISK 80TX         | Convertible | [c34bcc095c](https://linux-hardware.org/?probe=c34bcc095c) | Jul 25, 2021 |
| Dell          | 0D441T A03                  | Desktop     | [41283af596](https://linux-hardware.org/?probe=41283af596) | Jul 25, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [4c5e0baffe](https://linux-hardware.org/?probe=4c5e0baffe) | Jul 25, 2021 |
| HP            | EliteBook 820 G2            | Notebook    | [17b5a12640](https://linux-hardware.org/?probe=17b5a12640) | Jul 25, 2021 |
| MSI           | H110I PRO AC                | Desktop     | [08094a9121](https://linux-hardware.org/?probe=08094a9121) | Jul 25, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [c7cf1f5978](https://linux-hardware.org/?probe=c7cf1f5978) | Jul 25, 2021 |
| ASUSTek       | H87-PRO                     | Desktop     | [293b556234](https://linux-hardware.org/?probe=293b556234) | Jul 25, 2021 |
| MSI           | Z77MA-G45                   | Desktop     | [bbc6d96681](https://linux-hardware.org/?probe=bbc6d96681) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2347FF9       | Notebook    | [cdc7a6e9c8](https://linux-hardware.org/?probe=cdc7a6e9c8) | Jul 25, 2021 |
| HP            | 2000                        | Notebook    | [0187fe7c8a](https://linux-hardware.org/?probe=0187fe7c8a) | Jul 25, 2021 |
| Acer          | Aspire A515-41G             | Notebook    | [a34056020d](https://linux-hardware.org/?probe=a34056020d) | Jul 25, 2021 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [884f8f2850](https://linux-hardware.org/?probe=884f8f2850) | Jul 25, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [02e6821b40](https://linux-hardware.org/?probe=02e6821b40) | Jul 24, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1e8f9a7189](https://linux-hardware.org/?probe=1e8f9a7189) | Jul 24, 2021 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [4cf2681a8c](https://linux-hardware.org/?probe=4cf2681a8c) | Jul 24, 2021 |
| HP            | EliteBook x360 1030 G3      | Convertible | [0c49a20e7c](https://linux-hardware.org/?probe=0c49a20e7c) | Jul 24, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [b0e58bf8de](https://linux-hardware.org/?probe=b0e58bf8de) | Jul 24, 2021 |
| Gigabyte      | B560M D3H                   | Desktop     | [1456f9bf8e](https://linux-hardware.org/?probe=1456f9bf8e) | Jul 23, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [3491bd4228](https://linux-hardware.org/?probe=3491bd4228) | Jul 23, 2021 |
| Lenovo        | ThinkPad E595 20NF0005IX    | Notebook    | [dd220c0bdb](https://linux-hardware.org/?probe=dd220c0bdb) | Jul 23, 2021 |
| Gigabyte      | AERO 17-SA                  | Notebook    | [eaff86e276](https://linux-hardware.org/?probe=eaff86e276) | Jul 23, 2021 |
| Acer          | Aspire A715-72G             | Notebook    | [b436023dda](https://linux-hardware.org/?probe=b436023dda) | Jul 23, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [ecd10ec3a7](https://linux-hardware.org/?probe=ecd10ec3a7) | Jul 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1abb08da83](https://linux-hardware.org/?probe=1abb08da83) | Jul 21, 2021 |
| Supermicro    | X11DDW-L                    | Server      | [6fab4e3135](https://linux-hardware.org/?probe=6fab4e3135) | Jul 20, 2021 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [4ed280d4c8](https://linux-hardware.org/?probe=4ed280d4c8) | Jul 19, 2021 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [8af9716200](https://linux-hardware.org/?probe=8af9716200) | Jul 19, 2021 |
| ASUSTek       | P8Z68-V                     | Desktop     | [1a60e02aa9](https://linux-hardware.org/?probe=1a60e02aa9) | Jul 19, 2021 |
| Dell          | 0H5J4J A01                  | Server      | [fbdf83f7ff](https://linux-hardware.org/?probe=fbdf83f7ff) | Jul 17, 2021 |
| HP            | ProLiant MicroServer        | Desktop     | [ca7c4b4967](https://linux-hardware.org/?probe=ca7c4b4967) | Jul 16, 2021 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [acca72e9c1](https://linux-hardware.org/?probe=acca72e9c1) | Jul 15, 2021 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [a5daecad1d](https://linux-hardware.org/?probe=a5daecad1d) | Jul 15, 2021 |
| Dell          | Precision 3540              | Notebook    | [383ebf30aa](https://linux-hardware.org/?probe=383ebf30aa) | Jul 14, 2021 |
| Itautec       | Infoway                     | Notebook    | [06dc7b0fd1](https://linux-hardware.org/?probe=06dc7b0fd1) | Jul 14, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [71d234aaef](https://linux-hardware.org/?probe=71d234aaef) | Jul 14, 2021 |
| MSI           | A68HM-E33 V2                | Desktop     | [983bc90bc7](https://linux-hardware.org/?probe=983bc90bc7) | Jul 14, 2021 |
| Acer          | Aspire 7741                 | Notebook    | [6ed4934b61](https://linux-hardware.org/?probe=6ed4934b61) | Jul 13, 2021 |
| Acer          | Aspire 7741                 | Notebook    | [ee5a2b2029](https://linux-hardware.org/?probe=ee5a2b2029) | Jul 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [54bfb26e0f](https://linux-hardware.org/?probe=54bfb26e0f) | Jul 12, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [98271924ba](https://linux-hardware.org/?probe=98271924ba) | Jul 11, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | Notebook    | [d39fe8e9d4](https://linux-hardware.org/?probe=d39fe8e9d4) | Jul 11, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [1cb0058b88](https://linux-hardware.org/?probe=1cb0058b88) | Jul 10, 2021 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [776f848ccd](https://linux-hardware.org/?probe=776f848ccd) | Jul 09, 2021 |
| Dell          | 0M863N A00                  | Desktop     | [574671bbb9](https://linux-hardware.org/?probe=574671bbb9) | Jul 09, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [e6aa891005](https://linux-hardware.org/?probe=e6aa891005) | Jul 08, 2021 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [c79b71d033](https://linux-hardware.org/?probe=c79b71d033) | Jul 08, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [02c3ce63e7](https://linux-hardware.org/?probe=02c3ce63e7) | Jul 08, 2021 |
| HP            | 2215                        | Desktop     | [b0b56138b2](https://linux-hardware.org/?probe=b0b56138b2) | Jul 08, 2021 |
| Dell          | XPS 13 9380                 | Notebook    | [b31688ecfa](https://linux-hardware.org/?probe=b31688ecfa) | Jul 08, 2021 |
| HP            | 2215                        | Desktop     | [cdf48de6b2](https://linux-hardware.org/?probe=cdf48de6b2) | Jul 07, 2021 |
| Dell          | Latitude E6330              | Notebook    | [321bec10eb](https://linux-hardware.org/?probe=321bec10eb) | Jul 05, 2021 |
| HP            | Compaq 6830s                | Notebook    | [9c47e76afe](https://linux-hardware.org/?probe=9c47e76afe) | Jul 04, 2021 |
| MSI           | MS-6712                     | Desktop     | [ced0409e55](https://linux-hardware.org/?probe=ced0409e55) | Jul 04, 2021 |
| HP            | Compaq 6830s                | Notebook    | [b524035304](https://linux-hardware.org/?probe=b524035304) | Jul 04, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [b760b0d9cc](https://linux-hardware.org/?probe=b760b0d9cc) | Jul 03, 2021 |
| Acer          | Aspire A515-51              | Notebook    | [f94bb31c5a](https://linux-hardware.org/?probe=f94bb31c5a) | Jul 03, 2021 |
| HP            | ZBook Fury 17 G7 Mobile ... | Notebook    | [c24fcd1454](https://linux-hardware.org/?probe=c24fcd1454) | Jul 02, 2021 |
| Dell          | Latitude 7410               | Convertible | [457f309f39](https://linux-hardware.org/?probe=457f309f39) | Jul 02, 2021 |
| Dell          | Latitude 7410               | Convertible | [945a4600c4](https://linux-hardware.org/?probe=945a4600c4) | Jul 02, 2021 |
| ASRock        | H77 Pro4-M                  | Desktop     | [8ba58cff9a](https://linux-hardware.org/?probe=8ba58cff9a) | Jul 02, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [cb62272a68](https://linux-hardware.org/?probe=cb62272a68) | Jul 02, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [44b96068f2](https://linux-hardware.org/?probe=44b96068f2) | Jul 02, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [5729444e9b](https://linux-hardware.org/?probe=5729444e9b) | Jul 02, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [bd3211a03b](https://linux-hardware.org/?probe=bd3211a03b) | Jun 30, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [c8cb82f74d](https://linux-hardware.org/?probe=c8cb82f74d) | Jun 30, 2021 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [e325df530d](https://linux-hardware.org/?probe=e325df530d) | Jun 30, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [24a52836b4](https://linux-hardware.org/?probe=24a52836b4) | Jun 30, 2021 |
| HP            | ProBook 640 G3              | Notebook    | [c56b8f3ff1](https://linux-hardware.org/?probe=c56b8f3ff1) | Jun 29, 2021 |
| MSI           | B85M-G43                    | Desktop     | [4598afdf7e](https://linux-hardware.org/?probe=4598afdf7e) | Jun 29, 2021 |
| HP            | ZBook 17 G5                 | Notebook    | [5557a5c23c](https://linux-hardware.org/?probe=5557a5c23c) | Jun 29, 2021 |
| Lenovo        | IdeaPad Z580                | Notebook    | [6a9d31c8ef](https://linux-hardware.org/?probe=6a9d31c8ef) | Jun 29, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [5335641d04](https://linux-hardware.org/?probe=5335641d04) | Jun 28, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [0632a7bf28](https://linux-hardware.org/?probe=0632a7bf28) | Jun 28, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [834b68e61a](https://linux-hardware.org/?probe=834b68e61a) | Jun 28, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [65c54db09e](https://linux-hardware.org/?probe=65c54db09e) | Jun 27, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [fda3d18cf7](https://linux-hardware.org/?probe=fda3d18cf7) | Jun 27, 2021 |
| Huanan        | X99-8M-F V1.1               | Desktop     | [8ecfcffbaf](https://linux-hardware.org/?probe=8ecfcffbaf) | Jun 27, 2021 |
| HP            | ZBook Fury 17 G7 Mobile ... | Notebook    | [c3d5fd07c1](https://linux-hardware.org/?probe=c3d5fd07c1) | Jun 27, 2021 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [f435417b41](https://linux-hardware.org/?probe=f435417b41) | Jun 26, 2021 |
| Acer          | Nitro AN515-51              | Notebook    | [6c4a46b4ec](https://linux-hardware.org/?probe=6c4a46b4ec) | Jun 26, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2) (... | Phone       | [6805b89f3d](https://linux-hardware.org/?probe=6805b89f3d) | Jun 25, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [807a4ba37d](https://linux-hardware.org/?probe=807a4ba37d) | Jun 23, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [bc7246038e](https://linux-hardware.org/?probe=bc7246038e) | Jun 23, 2021 |
| ASRock        | B550 Pro4                   | Desktop     | [ef1b7bfb77](https://linux-hardware.org/?probe=ef1b7bfb77) | Jun 23, 2021 |
| ASRock        | X399 Taichi                 | Desktop     | [a664e4cf99](https://linux-hardware.org/?probe=a664e4cf99) | Jun 23, 2021 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [c9fed56a36](https://linux-hardware.org/?probe=c9fed56a36) | Jun 23, 2021 |
| Dell          | Inspiron 3501               | Notebook    | [d6f07cb592](https://linux-hardware.org/?probe=d6f07cb592) | Jun 23, 2021 |
| Dell          | 04WYPY A04                  | Server      | [20fa770830](https://linux-hardware.org/?probe=20fa770830) | Jun 22, 2021 |
| MSI           | GF65 Thin 10UE              | Notebook    | [d1e0b6ee58](https://linux-hardware.org/?probe=d1e0b6ee58) | Jun 22, 2021 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | Notebook    | [9e646a384e](https://linux-hardware.org/?probe=9e646a384e) | Jun 22, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [b3a5333d2a](https://linux-hardware.org/?probe=b3a5333d2a) | Jun 21, 2021 |
| Dell          | Precision 3560              | Notebook    | [81efcf647c](https://linux-hardware.org/?probe=81efcf647c) | Jun 21, 2021 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [75c4ec9e5a](https://linux-hardware.org/?probe=75c4ec9e5a) | Jun 21, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [08fc06c75e](https://linux-hardware.org/?probe=08fc06c75e) | Jun 20, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [c62a9a5058](https://linux-hardware.org/?probe=c62a9a5058) | Jun 20, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [5a39dabe8a](https://linux-hardware.org/?probe=5a39dabe8a) | Jun 20, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [b37bec27b3](https://linux-hardware.org/?probe=b37bec27b3) | Jun 20, 2021 |
| Dell          | Latitude E7470              | Notebook    | [49cb9ff0b0](https://linux-hardware.org/?probe=49cb9ff0b0) | Jun 20, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [73d6b46b6b](https://linux-hardware.org/?probe=73d6b46b6b) | Jun 19, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [a894e25838](https://linux-hardware.org/?probe=a894e25838) | Jun 19, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [dde7123487](https://linux-hardware.org/?probe=dde7123487) | Jun 19, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [33ffb80782](https://linux-hardware.org/?probe=33ffb80782) | Jun 19, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [842c53b8e2](https://linux-hardware.org/?probe=842c53b8e2) | Jun 18, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [1a8a3efde5](https://linux-hardware.org/?probe=1a8a3efde5) | Jun 18, 2021 |
| Lenovo        | ThinkPad X230 2325AZ8       | Notebook    | [b5ea5009bf](https://linux-hardware.org/?probe=b5ea5009bf) | Jun 18, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [259fc86278](https://linux-hardware.org/?probe=259fc86278) | Jun 18, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [9e3e72ec72](https://linux-hardware.org/?probe=9e3e72ec72) | Jun 17, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [c26c0f6e33](https://linux-hardware.org/?probe=c26c0f6e33) | Jun 15, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [0ccc446224](https://linux-hardware.org/?probe=0ccc446224) | Jun 14, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [eb77944ea2](https://linux-hardware.org/?probe=eb77944ea2) | Jun 14, 2021 |
| Gigabyte      | MCMLUAB-00                  | Desktop     | [99780e8ba8](https://linux-hardware.org/?probe=99780e8ba8) | Jun 13, 2021 |
| Acer          | Aspire V3-331               | Notebook    | [91f4f7aab6](https://linux-hardware.org/?probe=91f4f7aab6) | Jun 13, 2021 |
| UNOWHY        | Y13G002S4EI                 | Notebook    | [3d25dc9f69](https://linux-hardware.org/?probe=3d25dc9f69) | Jun 13, 2021 |
| ASUSTek       | X550LD                      | Notebook    | [2d1f6364aa](https://linux-hardware.org/?probe=2d1f6364aa) | Jun 13, 2021 |
| Acer          | Aspire V3-331               | Notebook    | [02e288caf9](https://linux-hardware.org/?probe=02e288caf9) | Jun 13, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [1b2cda6c08](https://linux-hardware.org/?probe=1b2cda6c08) | Jun 12, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f2770a810e](https://linux-hardware.org/?probe=f2770a810e) | Jun 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [f6ba765876](https://linux-hardware.org/?probe=f6ba765876) | Jun 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [57684125de](https://linux-hardware.org/?probe=57684125de) | Jun 12, 2021 |
| Unknown       | Helios64                    | Soc         | [33c6248333](https://linux-hardware.org/?probe=33c6248333) | Jun 11, 2021 |
| Dell          | 0Y7WYT A00                  | Desktop     | [8e424773e5](https://linux-hardware.org/?probe=8e424773e5) | Jun 10, 2021 |
| Dell          | Latitude E7470              | Notebook    | [51c1f3f1f5](https://linux-hardware.org/?probe=51c1f3f1f5) | Jun 10, 2021 |
| ASUSTek       | Z97-AR                      | Desktop     | [709a74c713](https://linux-hardware.org/?probe=709a74c713) | Jun 09, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [377f2e9ec6](https://linux-hardware.org/?probe=377f2e9ec6) | Jun 09, 2021 |
| Dell          | Latitude E6330              | Notebook    | [ba88cd6328](https://linux-hardware.org/?probe=ba88cd6328) | Jun 08, 2021 |
| Lenovo        | ThinkPad T430s 2356A89      | Notebook    | [0195b8564e](https://linux-hardware.org/?probe=0195b8564e) | Jun 08, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [ee4dfdfde3](https://linux-hardware.org/?probe=ee4dfdfde3) | Jun 08, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [2db77f0d01](https://linux-hardware.org/?probe=2db77f0d01) | Jun 07, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [69dd9fbe20](https://linux-hardware.org/?probe=69dd9fbe20) | Jun 07, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [548356ed30](https://linux-hardware.org/?probe=548356ed30) | Jun 06, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [f65812f774](https://linux-hardware.org/?probe=f65812f774) | Jun 06, 2021 |
| ASUSTek       | M3N                         | Notebook    | [ec5f914161](https://linux-hardware.org/?probe=ec5f914161) | Jun 06, 2021 |
| ASUSTek       | M3N                         | Notebook    | [bd89f26d7e](https://linux-hardware.org/?probe=bd89f26d7e) | Jun 05, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [0fd993c4dd](https://linux-hardware.org/?probe=0fd993c4dd) | Jun 05, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [5c16d903d3](https://linux-hardware.org/?probe=5c16d903d3) | Jun 05, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [47e9dfd146](https://linux-hardware.org/?probe=47e9dfd146) | Jun 05, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [90dbe22a68](https://linux-hardware.org/?probe=90dbe22a68) | Jun 05, 2021 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [e20b51102d](https://linux-hardware.org/?probe=e20b51102d) | Jun 03, 2021 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | Notebook    | [b513f2fc77](https://linux-hardware.org/?probe=b513f2fc77) | Jun 03, 2021 |
| ASUSTek       | M4A88T-M/USB3               | Desktop     | [7483847993](https://linux-hardware.org/?probe=7483847993) | Jun 03, 2021 |
| Monster       | ABRA A5 V15.2               | Notebook    | [012bfa586d](https://linux-hardware.org/?probe=012bfa586d) | Jun 02, 2021 |
| Pegatron      | A15                         | Notebook    | [dec1b6b43a](https://linux-hardware.org/?probe=dec1b6b43a) | Jun 02, 2021 |
| Dell          | 0YXT71 A02                  | Desktop     | [a45729e01a](https://linux-hardware.org/?probe=a45729e01a) | Jun 01, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [ac80feea4f](https://linux-hardware.org/?probe=ac80feea4f) | Jun 01, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [21574f62a5](https://linux-hardware.org/?probe=21574f62a5) | Jun 01, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [80cf3dc8e7](https://linux-hardware.org/?probe=80cf3dc8e7) | Jun 01, 2021 |
| HP            | Compaq tc4400 (GE179UP#A... | Notebook    | [eeaee9f1ad](https://linux-hardware.org/?probe=eeaee9f1ad) | Jun 01, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f77e2ebb10](https://linux-hardware.org/?probe=f77e2ebb10) | May 31, 2021 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [926229be87](https://linux-hardware.org/?probe=926229be87) | May 31, 2021 |
| Toshiba       | Satellite U800W             | Notebook    | [ac79b35dfd](https://linux-hardware.org/?probe=ac79b35dfd) | May 30, 2021 |
| MSI           | U90/U100                    | Notebook    | [477251f62e](https://linux-hardware.org/?probe=477251f62e) | May 30, 2021 |
| MSI           | U90/U100                    | Notebook    | [1a0476551b](https://linux-hardware.org/?probe=1a0476551b) | May 30, 2021 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [eb3d04e089](https://linux-hardware.org/?probe=eb3d04e089) | May 29, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [92aa2017b9](https://linux-hardware.org/?probe=92aa2017b9) | May 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [c33e7ced42](https://linux-hardware.org/?probe=c33e7ced42) | May 29, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [24d2e85009](https://linux-hardware.org/?probe=24d2e85009) | May 29, 2021 |
| MSI           | CX700                       | Notebook    | [ef40976753](https://linux-hardware.org/?probe=ef40976753) | May 29, 2021 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [7ca350189c](https://linux-hardware.org/?probe=7ca350189c) | May 29, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [5de2c933c1](https://linux-hardware.org/?probe=5de2c933c1) | May 28, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [88cee1e822](https://linux-hardware.org/?probe=88cee1e822) | May 28, 2021 |
| Samsung       | 370E4K                      | Notebook    | [125fbb3d15](https://linux-hardware.org/?probe=125fbb3d15) | May 28, 2021 |
| MSI           | CX700                       | Notebook    | [535d0016e2](https://linux-hardware.org/?probe=535d0016e2) | May 27, 2021 |
| MSI           | B250M BAZOOKA               | Desktop     | [fb2eef67f2](https://linux-hardware.org/?probe=fb2eef67f2) | May 26, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [c091670daa](https://linux-hardware.org/?probe=c091670daa) | May 25, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [ad6cd7847f](https://linux-hardware.org/?probe=ad6cd7847f) | May 24, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [2c698534c6](https://linux-hardware.org/?probe=2c698534c6) | May 23, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [f03341d873](https://linux-hardware.org/?probe=f03341d873) | May 23, 2021 |
| Gigabyte      | AB350M-D3H-CF               | Desktop     | [1ad175fddc](https://linux-hardware.org/?probe=1ad175fddc) | May 23, 2021 |
| Dell          | Latitude 7410               | Convertible | [bc7c58f248](https://linux-hardware.org/?probe=bc7c58f248) | May 21, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [6573923d55](https://linux-hardware.org/?probe=6573923d55) | May 21, 2021 |
| Lenovo        | ThinkPad X1 Tablet 20GGS... | Tablet      | [1c271464f4](https://linux-hardware.org/?probe=1c271464f4) | May 21, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [8b7b153998](https://linux-hardware.org/?probe=8b7b153998) | May 20, 2021 |
| Dell          | Latitude 7410               | Convertible | [cbd8832f44](https://linux-hardware.org/?probe=cbd8832f44) | May 19, 2021 |
| Dell          | Latitude 7480               | Notebook    | [0f2477786d](https://linux-hardware.org/?probe=0f2477786d) | May 19, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4PN0... | Notebook    | [f8b2c84bc1](https://linux-hardware.org/?probe=f8b2c84bc1) | May 19, 2021 |
| sunxi         | Unknown                     | Soc         | [d54c3a2a33](https://linux-hardware.org/?probe=d54c3a2a33) | May 19, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [b9d0acf0a6](https://linux-hardware.org/?probe=b9d0acf0a6) | May 19, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [97a658e572](https://linux-hardware.org/?probe=97a658e572) | May 19, 2021 |
| Gigabyte      | Z170X-GamingG1              | Desktop     | [361469c7d5](https://linux-hardware.org/?probe=361469c7d5) | May 18, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [28bb88d60c](https://linux-hardware.org/?probe=28bb88d60c) | May 17, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FEA0... | Convertible | [2a0eca4670](https://linux-hardware.org/?probe=2a0eca4670) | May 17, 2021 |
| HP            | Compaq Presario C700        | Notebook    | [91a939ce16](https://linux-hardware.org/?probe=91a939ce16) | May 16, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [646b64ccb3](https://linux-hardware.org/?probe=646b64ccb3) | May 15, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [71f4ed3e35](https://linux-hardware.org/?probe=71f4ed3e35) | May 11, 2021 |
| Lenovo        | MAHOBAY                     | Desktop     | [c0b8e99e35](https://linux-hardware.org/?probe=c0b8e99e35) | May 06, 2021 |
| HP            | Split 13 x2 PC              | Notebook    | [5834b6321d](https://linux-hardware.org/?probe=5834b6321d) | May 05, 2021 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [bf3e99374e](https://linux-hardware.org/?probe=bf3e99374e) | Apr 29, 2021 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [a06f2bc29e](https://linux-hardware.org/?probe=a06f2bc29e) | Apr 27, 2021 |
| Biostar       | B450MH                      | Desktop     | [f0a1151d81](https://linux-hardware.org/?probe=f0a1151d81) | Apr 27, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [a042fd63c6](https://linux-hardware.org/?probe=a042fd63c6) | Apr 27, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [a4c79ea8c3](https://linux-hardware.org/?probe=a4c79ea8c3) | Apr 26, 2021 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [446238dd0c](https://linux-hardware.org/?probe=446238dd0c) | Apr 25, 2021 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [bb76391a12](https://linux-hardware.org/?probe=bb76391a12) | Apr 25, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [bcea790fba](https://linux-hardware.org/?probe=bcea790fba) | Apr 24, 2021 |
| Lenovo        | ThinkPad T430s 23533KJ      | Notebook    | [39aa120e47](https://linux-hardware.org/?probe=39aa120e47) | Apr 21, 2021 |
| Dell          | Inspiron 5468               | Notebook    | [cfc77b26b5](https://linux-hardware.org/?probe=cfc77b26b5) | Apr 17, 2021 |
| Gigabyte      | EG41MF-US2H                 | Desktop     | [a2aa6eaec8](https://linux-hardware.org/?probe=a2aa6eaec8) | Apr 16, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [4967255e37](https://linux-hardware.org/?probe=4967255e37) | Apr 14, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [e1a5725060](https://linux-hardware.org/?probe=e1a5725060) | Apr 14, 2021 |
| sunxi         | Banana Pi BPI-M2-Ultra      | Soc         | [c0536c5433](https://linux-hardware.org/?probe=c0536c5433) | Apr 13, 2021 |
| sunxi         | Banana Pi BPI-M2-Ultra      | Soc         | [935ccffcd5](https://linux-hardware.org/?probe=935ccffcd5) | Feb 01, 2021 |
| Unknown       | Shenzhen Amediatech Tech... | Soc         | [2fed627592](https://linux-hardware.org/?probe=2fed627592) | Jan 18, 2021 |
| sunxi         | Unknown                     | Soc         | [604dd9d393](https://linux-hardware.org/?probe=604dd9d393) | Feb 25, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                        | Computers | Percent |
|--------------------------------|-----------|---------|
| 5.10.0-8-amd64                 | 177       | 46.21%  |
| 5.10.0-7-amd64                 | 106       | 27.68%  |
| 5.10.0-6-amd64                 | 37        | 9.66%   |
| 5.11.22-1-pve                  | 5         | 1.31%   |
| 5.10.0-8-686                   | 3         | 0.78%   |
| 5.12.0-19.3-liquorix-amd64     | 2         | 0.52%   |
| 5.11.22-2-pve                  | 2         | 0.52%   |
| 5.10.0-8-rt-amd64              | 2         | 0.52%   |
| 5.10.0-8-686-pae               | 2         | 0.52%   |
| 5.10-sunxi64                   | 2         | 0.52%   |
| 4.19.0-14-amd64                | 2         | 0.52%   |
| 5.9.0-arm-64                   | 1         | 0.26%   |
| 5.8.0-3-amd64                  | 1         | 0.26%   |
| 5.4.18-sunxi64                 | 1         | 0.26%   |
| 5.4.0-73-generic               | 1         | 0.26%   |
| 5.14.0-rc3-prygun              | 1         | 0.26%   |
| 5.13.5-xanmod1                 | 1         | 0.26%   |
| 5.13.4-e5520                   | 1         | 0.26%   |
| 5.13.4                         | 1         | 0.26%   |
| 5.13.1a                        | 1         | 0.26%   |
| 5.13.0-rc7-00024-g0418ae8de752 | 1         | 0.26%   |
| 5.12.4                         | 1         | 0.26%   |
| 5.12.10                        | 1         | 0.26%   |
| 5.12.1                         | 1         | 0.26%   |
| 5.12.0-9.2-liquorix-amd64      | 1         | 0.26%   |
| 5.12.0-14.2-liquorix-amd64     | 1         | 0.26%   |
| 5.11.9+                        | 1         | 0.26%   |
| 5.11.22-3-pve                  | 1         | 0.26%   |
| 5.11.15-terranz                | 1         | 0.26%   |
| 5.11.15-051115-generic         | 1         | 0.26%   |
| 5.11.14                        | 1         | 0.26%   |
| 5.11.0-rc6                     | 1         | 0.26%   |
| 5.11.0-21.1-liquorix-amd64     | 1         | 0.26%   |
| 5.11.0-16.1-liquorix-amd64     | 1         | 0.26%   |
| 5.10.46custom                  | 1         | 0.26%   |
| 5.10.42+truenas                | 1         | 0.26%   |
| 5.10.40-ismynik                | 1         | 0.26%   |
| 5.10.38-falcot                 | 1         | 0.26%   |
| 5.10.35-rockchip64             | 1         | 0.26%   |
| 5.10.21-sunxi                  | 1         | 0.26%   |
| 5.10.12-sunxi                  | 1         | 0.26%   |
| 5.10.10-64                     | 1         | 0.26%   |
| 5.10.0-io7-amd64               | 1         | 0.26%   |
| 5.10.0-8-armmp                 | 1         | 0.26%   |
| 5.10.0-7-686-pae               | 1         | 0.26%   |
| 5.10.0-6-rt-amd64              | 1         | 0.26%   |
| 5.10.0-6-686                   | 1         | 0.26%   |
| 5.10.0-5-amd64                 | 1         | 0.26%   |
| 5.10.0-4-amd64                 | 1         | 0.26%   |
| 5.10.0-3-amd64                 | 1         | 0.26%   |
| 5.10.0-2-amd64                 | 1         | 0.26%   |
| 4.19.181-z580322               | 1         | 0.26%   |
| 4.19.0-16-amd64                | 1         | 0.26%   |
| 4.19.0-16-686-pae              | 1         | 0.26%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 328       | 87.7%   |
| 5.11.22  | 8         | 2.14%   |
| 4.19.0   | 4         | 1.07%   |
| 5.12.0   | 3         | 0.8%    |
| 5.11.0   | 3         | 0.8%    |
| 5.13.4   | 2         | 0.53%   |
| 5.11.15  | 2         | 0.53%   |
| 5.10     | 2         | 0.53%   |
| 5.9.0    | 1         | 0.27%   |
| 5.8.0    | 1         | 0.27%   |
| 5.4.18   | 1         | 0.27%   |
| 5.4.0    | 1         | 0.27%   |
| 5.14.0   | 1         | 0.27%   |
| 5.13.5   | 1         | 0.27%   |
| 5.13.1   | 1         | 0.27%   |
| 5.13.0   | 1         | 0.27%   |
| 5.12.4   | 1         | 0.27%   |
| 5.12.10  | 1         | 0.27%   |
| 5.12.1   | 1         | 0.27%   |
| 5.11.9   | 1         | 0.27%   |
| 5.11.14  | 1         | 0.27%   |
| 5.10.46  | 1         | 0.27%   |
| 5.10.42  | 1         | 0.27%   |
| 5.10.40  | 1         | 0.27%   |
| 5.10.38  | 1         | 0.27%   |
| 5.10.35  | 1         | 0.27%   |
| 5.10.21  | 1         | 0.27%   |
| 5.10.12  | 1         | 0.27%   |
| 5.10.10  | 1         | 0.27%   |
| 4.19.181 | 1         | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 335       | 89.81%  |
| 5.11    | 15        | 4.02%   |
| 5.12    | 6         | 1.61%   |
| 5.13    | 5         | 1.34%   |
| 4.19    | 5         | 1.34%   |
| 5.4     | 2         | 0.54%   |
| 5       | 2         | 0.54%   |
| 5.9     | 1         | 0.27%   |
| 5.8     | 1         | 0.27%   |
| 5.14    | 1         | 0.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 358       | 95.98%  |
| i686    | 8         | 2.14%   |
| aarch64 | 5         | 1.34%   |
| armv7l  | 2         | 0.54%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 107       | 28.46%  |
| KDE5             | 76        | 20.21%  |
| Unknown          | 40        | 10.64%  |
| XFCE             | 39        | 10.37%  |
| MATE             | 28        | 7.45%   |
| Cinnamon         | 14        | 3.72%   |
| LXQt             | 13        | 3.46%   |
| i3               | 11        | 2.93%   |
| LXDE             | 10        | 2.66%   |
| KDE              | 10        | 2.66%   |
| X-Cinnamon       | 7         | 1.86%   |
| Trinity          | 5         | 1.33%   |
| lightdm-xsession | 4         | 1.06%   |
| GNOME Flashback  | 4         | 1.06%   |
| sway             | 2         | 0.53%   |
| openbox          | 2         | 0.53%   |
| GNUstep          | 1         | 0.27%   |
| default          | 1         | 0.27%   |
| Budgie           | 1         | 0.27%   |
| awesome          | 1         | 0.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 238       | 63.47%  |
| Wayland | 85        | 22.67%  |
| Tty     | 34        | 9.07%   |
| Unknown | 18        | 4.8%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| TDM     | 110       | 29.33%  |
| GDM     | 102       | 27.2%   |
| SDDM    | 78        | 20.8%   |
| Unknown | 72        | 19.2%   |
| LightDM | 8         | 2.13%   |
| XDM     | 2         | 0.53%   |
| SLiM    | 2         | 0.53%   |
| KDM     | 1         | 0.27%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 158       | 42.25%  |
| ru_RU   | 29        | 7.75%   |
| en_GB   | 28        | 7.49%   |
| de_DE   | 23        | 6.15%   |
| fr_FR   | 21        | 5.61%   |
| Unknown | 13        | 3.48%   |
| es_ES   | 11        | 2.94%   |
| pt_BR   | 9         | 2.41%   |
| pl_PL   | 8         | 2.14%   |
| en_IN   | 8         | 2.14%   |
| C       | 7         | 1.87%   |
| en_AU   | 5         | 1.34%   |
| it_IT   | 4         | 1.07%   |
| en_CA   | 4         | 1.07%   |
| tr_TR   | 3         | 0.8%    |
| nl_BE   | 3         | 0.8%    |
| ja_JP   | 3         | 0.8%    |
| hu_HU   | 3         | 0.8%    |
| de_CH   | 3         | 0.8%    |
| cs_CZ   | 3         | 0.8%    |
| uk_UA   | 2         | 0.53%   |
| ru_UA   | 2         | 0.53%   |
| ro_RO   | 2         | 0.53%   |
| pt_PT   | 2         | 0.53%   |
| en_SG   | 2         | 0.53%   |
| en_HK   | 2         | 0.53%   |
| sv_SE   | 1         | 0.27%   |
| sr_RS   | 1         | 0.27%   |
| sk_SK   | 1         | 0.27%   |
| hr_HR   | 1         | 0.27%   |
| gl_ES   | 1         | 0.27%   |
| fi_FI   | 1         | 0.27%   |
| es_VE   | 1         | 0.27%   |
| es_US   | 1         | 0.27%   |
| es_MX   | 1         | 0.27%   |
| es_EC   | 1         | 0.27%   |
| es_CO   | 1         | 0.27%   |
| es_AR   | 1         | 0.27%   |
| en_SI   | 1         | 0.27%   |
| en_PH   | 1         | 0.27%   |
| en_IE   | 1         | 0.27%   |
| ca_ES   | 1         | 0.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 236       | 62.93%  |
| BIOS | 139       | 37.07%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 297       | 79.62%  |
| Btrfs   | 27        | 7.24%   |
| Overlay | 25        | 6.7%    |
| Zfs     | 9         | 2.41%   |
| Xfs     | 5         | 1.34%   |
| Ext3    | 5         | 1.34%   |
| Unknown | 4         | 1.07%   |
| Rootfs  | 1         | 0.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 254       | 67.73%  |
| MBR     | 85        | 22.67%  |
| Unknown | 36        | 9.6%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 296       | 79.14%  |
| Yes       | 78        | 20.86%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 268       | 71.66%  |
| Yes       | 106       | 28.34%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 78        | 20.91%  |
| ASUSTek Computer        | 56        | 15.01%  |
| Dell                    | 50        | 13.4%   |
| Hewlett-Packard         | 45        | 12.06%  |
| Gigabyte Technology     | 33        | 8.85%   |
| ASRock                  | 23        | 6.17%   |
| MSI                     | 21        | 5.63%   |
| Acer                    | 13        | 3.49%   |
| Intel                   | 5         | 1.34%   |
| Apple                   | 5         | 1.34%   |
| Toshiba                 | 3         | 0.8%    |
| sunxi                   | 3         | 0.8%    |
| HUAWEI                  | 3         | 0.8%    |
| Fujitsu                 | 3         | 0.8%    |
| Supermicro              | 2         | 0.54%   |
| Huanan                  | 2         | 0.54%   |
| Google                  | 2         | 0.54%   |
| Foxconn                 | 2         | 0.54%   |
| Unknown                 | 2         | 0.54%   |
| ZOTAC                   | 1         | 0.27%   |
| UNOWHY                  | 1         | 0.27%   |
| SLIMBOOK                | 1         | 0.27%   |
| Shuttle                 | 1         | 0.27%   |
| Samsung Electronics     | 1         | 0.27%   |
| Raspberry Pi Foundation | 1         | 0.27%   |
| Quanta                  | 1         | 0.27%   |
| Protectli               | 1         | 0.27%   |
| Pine Microsystems       | 1         | 0.27%   |
| Pegatron                | 1         | 0.27%   |
| PC Specialist           | 1         | 0.27%   |
| Panasonic               | 1         | 0.27%   |
| Monster                 | 1         | 0.27%   |
| Itautec                 | 1         | 0.27%   |
| IBM                     | 1         | 0.27%   |
| HARDKERNEL              | 1         | 0.27%   |
| ECS                     | 1         | 0.27%   |
| Compulab                | 1         | 0.27%   |
| Chuwi                   | 1         | 0.27%   |
| Casper                  | 1         | 0.27%   |
| Biostar                 | 1         | 0.27%   |
| ASRockRack              | 1         | 0.27%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                          | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| ASUS All Series                               | 4         | 1.07%   |
| Unknown                                       | 4         | 1.07%   |
| Gigabyte B550I AORUS PRO AX                   | 3         | 0.8%    |
| ASRock B450M Pro4                             | 3         | 0.8%    |
| Lenovo G50-80 80E5                            | 2         | 0.54%   |
| HUAWEI NBLK-WAX9X                             | 2         | 0.54%   |
| HP Z620 Workstation                           | 2         | 0.54%   |
| Gigabyte Z77-D3H                              | 2         | 0.54%   |
| Gigabyte Z370 AORUS Gaming 5                  | 2         | 0.54%   |
| Dell XPS 13 9310                              | 2         | 0.54%   |
| Dell XPS 13 7390                              | 2         | 0.54%   |
| Dell OptiPlex 760                             | 2         | 0.54%   |
| Dell Latitude 7480                            | 2         | 0.54%   |
| Dell Inspiron 5570                            | 2         | 0.54%   |
| Dell Inspiron 3793                            | 2         | 0.54%   |
| ASUS VivoBook_ASUS Laptop E210MA_L210MA       | 2         | 0.54%   |
| ASUS PRIME B550-PLUS                          | 2         | 0.54%   |
| ASUS PRIME B450M-A                            | 2         | 0.54%   |
| ZOTAC ZBOX-EN1070/1060,EN1070K/1060K          | 1         | 0.27%   |
| UNOWHY Y13G002S4EI                            | 1         | 0.27%   |
| Toshiba Satellite U800W                       | 1         | 0.27%   |
| Toshiba Satellite S55-A                       | 1         | 0.27%   |
| Toshiba Satellite C45-A                       | 1         | 0.27%   |
| Supermicro SYS-6019P-WT                       | 1         | 0.27%   |
| Supermicro SYS-5038MA-H24TRF                  | 1         | 0.27%   |
| sunxi Banana Pi BPI-M2-Ultra                  | 1         | 0.27%   |
| SLIMBOOK PROX14-AMD                           | 1         | 0.27%   |
| Shuttle SX79R                                 | 1         | 0.27%   |
| Samsung 370E4K                                | 1         | 0.27%   |
| RPi Raspberry Pi 2 Model B Rev 1.1            | 1         | 0.27%   |
| Quanta TWC                                    | 1         | 0.27%   |
| Protectli FW6                                 | 1         | 0.27%   |
| Pine Microsystems Pine64 PinePhone (1.2) (DT) | 1         | 0.27%   |
| Pegatron A15                                  | 1         | 0.27%   |
| PC Specialist NV4XMB,ME,MZ                    | 1         | 0.27%   |
| Panasonic CF-AX2LDCZMF                        | 1         | 0.27%   |
| MSI U90/U100                                  | 1         | 0.27%   |
| MSI MS-7C94                                   | 1         | 0.27%   |
| MSI MS-7C84                                   | 1         | 0.27%   |
| MSI MS-7C75                                   | 1         | 0.27%   |
| MSI MS-7C56                                   | 1         | 0.27%   |
| MSI MS-7C35                                   | 1         | 0.27%   |
| MSI MS-7B89                                   | 1         | 0.27%   |
| MSI MS-7B46                                   | 1         | 0.27%   |
| MSI MS-7B09                                   | 1         | 0.27%   |
| MSI MS-7A70                                   | 1         | 0.27%   |
| MSI MS-7A40                                   | 1         | 0.27%   |
| MSI MS-7A38                                   | 1         | 0.27%   |
| MSI MS-7995                                   | 1         | 0.27%   |
| MSI MS-7823                                   | 1         | 0.27%   |
| MSI MS-7759                                   | 1         | 0.27%   |
| MSI MS-7721                                   | 1         | 0.27%   |
| MSI MS-7562                                   | 1         | 0.27%   |
| MSI MS-6712                                   | 1         | 0.27%   |
| MSI Modern 15 A11M                            | 1         | 0.27%   |
| MSI GF65 Thin 10UE                            | 1         | 0.27%   |
| MSI CX700                                     | 1         | 0.27%   |
| Monster ABRA A5 V15.2                         | 1         | 0.27%   |
| Lenovo Yoga 910-13IKB 80VF                    | 1         | 0.27%   |
| Lenovo Yoga 710-11ISK 80TX                    | 1         | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Lenovo ThinkPad              | 55        | 14.75%  |
| Lenovo IdeaPad               | 14        | 3.75%   |
| Dell Inspiron                | 14        | 3.75%   |
| ASUS PRIME                   | 14        | 3.75%   |
| Acer Aspire                  | 10        | 2.68%   |
| HP ProBook                   | 9         | 2.41%   |
| Dell XPS                     | 9         | 2.41%   |
| Dell OptiPlex                | 9         | 2.41%   |
| HP EliteBook                 | 8         | 2.14%   |
| Dell Latitude                | 7         | 1.88%   |
| ASUS ROG                     | 7         | 1.88%   |
| Dell Precision               | 6         | 1.61%   |
| HP Laptop                    | 5         | 1.34%   |
| ASUS ZenBook                 | 5         | 1.34%   |
| ASUS VivoBook                | 5         | 1.34%   |
| Lenovo Yoga                  | 4         | 1.07%   |
| HP Compaq                    | 4         | 1.07%   |
| ASUS All                     | 4         | 1.07%   |
| Unknown                      | 4         | 1.07%   |
| Toshiba Satellite            | 3         | 0.8%    |
| Lenovo ThinkCentre           | 3         | 0.8%    |
| Gigabyte B550I               | 3         | 0.8%    |
| Fujitsu LIFEBOOK             | 3         | 0.8%    |
| ASRock B450M                 | 3         | 0.8%    |
| Lenovo G50-80                | 2         | 0.54%   |
| HUAWEI NBLK-WAX9X            | 2         | 0.54%   |
| HP ZBook                     | 2         | 0.54%   |
| HP Z620                      | 2         | 0.54%   |
| HP ProLiant                  | 2         | 0.54%   |
| HP OMEN                      | 2         | 0.54%   |
| HP 250                       | 2         | 0.54%   |
| Gigabyte Z77-D3H             | 2         | 0.54%   |
| Gigabyte Z370                | 2         | 0.54%   |
| Gigabyte AERO                | 2         | 0.54%   |
| Dell Vostro                  | 2         | 0.54%   |
| Dell PowerEdge               | 2         | 0.54%   |
| ASRock Z97                   | 2         | 0.54%   |
| Acer Nitro                   | 2         | 0.54%   |
| ZOTAC ZBOX-EN1070            | 1         | 0.27%   |
| UNOWHY Y13G002S4EI           | 1         | 0.27%   |
| Supermicro SYS-6019P-WT      | 1         | 0.27%   |
| Supermicro SYS-5038MA-H24TRF | 1         | 0.27%   |
| sunxi Banana                 | 1         | 0.27%   |
| SLIMBOOK PROX14-AMD          | 1         | 0.27%   |
| Shuttle SX79R                | 1         | 0.27%   |
| Samsung 370E4K               | 1         | 0.27%   |
| RPi Raspberry                | 1         | 0.27%   |
| Quanta TWC                   | 1         | 0.27%   |
| Protectli FW6                | 1         | 0.27%   |
| Pine Microsystems Pine64     | 1         | 0.27%   |
| Pegatron A15                 | 1         | 0.27%   |
| PC Specialist NV4XMB         | 1         | 0.27%   |
| Panasonic CF-AX2LDCZMF       | 1         | 0.27%   |
| MSI U90                      | 1         | 0.27%   |
| MSI MS-7C94                  | 1         | 0.27%   |
| MSI MS-7C84                  | 1         | 0.27%   |
| MSI MS-7C75                  | 1         | 0.27%   |
| MSI MS-7C56                  | 1         | 0.27%   |
| MSI MS-7C35                  | 1         | 0.27%   |
| MSI MS-7B89                  | 1         | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 86        | 23.06%  |
| 2021    | 65        | 17.43%  |
| 2019    | 50        | 13.4%   |
| 2018    | 36        | 9.65%   |
| 2016    | 20        | 5.36%   |
| 2012    | 19        | 5.09%   |
| 2014    | 16        | 4.29%   |
| 2013    | 16        | 4.29%   |
| 2015    | 10        | 2.68%   |
| 2011    | 10        | 2.68%   |
| 2009    | 9         | 2.41%   |
| 2017    | 8         | 2.14%   |
| 2010    | 8         | 2.14%   |
| Unknown | 7         | 1.88%   |
| 2008    | 4         | 1.07%   |
| 2007    | 4         | 1.07%   |
| 2006    | 2         | 0.54%   |
| 2004    | 2         | 0.54%   |
| 2001    | 1         | 0.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 198       | 53.08%  |
| Desktop        | 146       | 39.14%  |
| Convertible    | 9         | 2.41%   |
| System on chip | 6         | 1.61%   |
| Mini pc        | 5         | 1.34%   |
| Server         | 4         | 1.07%   |
| Tablet         | 2         | 0.54%   |
| All in one     | 2         | 0.54%   |
| Phone          | 1         | 0.27%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 337       | 89.87%  |
| Enabled  | 38        | 10.13%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 370       | 99.2%   |
| Yes  | 3         | 0.8%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 110       | 29.49%  |
| 4.01-8.0        | 73        | 19.57%  |
| 8.01-16.0       | 61        | 16.35%  |
| 32.01-64.0      | 41        | 10.99%  |
| 3.01-4.0        | 39        | 10.46%  |
| 64.01-256.0     | 22        | 5.9%    |
| 1.01-2.0        | 11        | 2.95%   |
| 2.01-3.0        | 8         | 2.14%   |
| 24.01-32.0      | 3         | 0.8%    |
| 0.01-0.5        | 3         | 0.8%    |
| More than 256.0 | 1         | 0.27%   |
| 0.51-1.0        | 1         | 0.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 83        | 21.96%  |
| 1.01-2.0    | 78        | 20.63%  |
| 4.01-8.0    | 67        | 17.72%  |
| 3.01-4.0    | 54        | 14.29%  |
| 8.01-16.0   | 33        | 8.73%   |
| 0.51-1.0    | 33        | 8.73%   |
| 0.01-0.5    | 18        | 4.76%   |
| 24.01-32.0  | 4         | 1.06%   |
| 16.01-24.0  | 4         | 1.06%   |
| 32.01-64.0  | 3         | 0.79%   |
| 64.01-256.0 | 1         | 0.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 192       | 51.47%  |
| 2      | 109       | 29.22%  |
| 3      | 30        | 8.04%   |
| 4      | 18        | 4.83%   |
| 5      | 10        | 2.68%   |
| 8      | 5         | 1.34%   |
| 9      | 3         | 0.8%    |
| 6      | 3         | 0.8%    |
| 0      | 2         | 0.54%   |
| 10     | 1         | 0.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 259       | 69.44%  |
| Yes       | 114       | 30.56%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 317       | 84.99%  |
| No        | 56        | 15.01%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 256       | 68.63%  |
| No        | 117       | 31.37%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 210       | 56.3%   |
| No        | 163       | 43.7%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 67        | 17.96%  |
| Russia                 | 35        | 9.38%   |
| Germany                | 35        | 9.38%   |
| France                 | 31        | 8.31%   |
| UK                     | 17        | 4.56%   |
| Spain                  | 16        | 4.29%   |
| Poland                 | 15        | 4.02%   |
| Ukraine                | 13        | 3.49%   |
| Brazil                 | 11        | 2.95%   |
| Netherlands            | 9         | 2.41%   |
| India                  | 8         | 2.14%   |
| Canada                 | 7         | 1.88%   |
| Greece                 | 6         | 1.61%   |
| Czechia                | 6         | 1.61%   |
| Australia              | 6         | 1.61%   |
| Switzerland            | 5         | 1.34%   |
| Mexico                 | 5         | 1.34%   |
| Italy                  | 5         | 1.34%   |
| Hungary                | 5         | 1.34%   |
| Turkey                 | 4         | 1.07%   |
| Thailand               | 4         | 1.07%   |
| Portugal               | 4         | 1.07%   |
| Norway                 | 4         | 1.07%   |
| Kazakhstan             | 4         | 1.07%   |
| Bulgaria               | 4         | 1.07%   |
| Belarus                | 4         | 1.07%   |
| Japan                  | 3         | 0.8%    |
| Finland                | 3         | 0.8%    |
| Ecuador                | 3         | 0.8%    |
| Belgium                | 3         | 0.8%    |
| Austria                | 3         | 0.8%    |
| Argentina              | 3         | 0.8%    |
| Venezuela              | 2         | 0.54%   |
| Sweden                 | 2         | 0.54%   |
| Slovenia               | 2         | 0.54%   |
| Croatia                | 2         | 0.54%   |
| Vietnam                | 1         | 0.27%   |
| Syria                  | 1         | 0.27%   |
| Singapore              | 1         | 0.27%   |
| Serbia                 | 1         | 0.27%   |
| Romania                | 1         | 0.27%   |
| Philippines            | 1         | 0.27%   |
| New Caledonia          | 1         | 0.27%   |
| Mongolia               | 1         | 0.27%   |
| Malaysia               | 1         | 0.27%   |
| Madagascar             | 1         | 0.27%   |
| Indonesia              | 1         | 0.27%   |
| Hong Kong              | 1         | 0.27%   |
| Denmark                | 1         | 0.27%   |
| Colombia               | 1         | 0.27%   |
| China                  | 1         | 0.27%   |
| Bosnia and Herzegovina | 1         | 0.27%   |
| Bangladesh             | 1         | 0.27%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| St Petersburg  | 8         | 2.14%   |
| Paris          | 8         | 2.14%   |
| Lyon           | 6         | 1.6%    |
| Portland       | 5         | 1.34%   |
| Ocala          | 5         | 1.34%   |
| Kalamazoo      | 5         | 1.34%   |
| Athens         | 5         | 1.34%   |
| Warsaw         | 4         | 1.07%   |
| Sofia          | 4         | 1.07%   |
| Moscow         | 4         | 1.07%   |
| London         | 4         | 1.07%   |
| Kyiv           | 4         | 1.07%   |
| Ensenada       | 4         | 1.07%   |
| Berlin         | 4         | 1.07%   |
| Bengaluru      | 4         | 1.07%   |
| Bangkok        | 4         | 1.07%   |
| Vienna         | 3         | 0.8%    |
| Sunnyvale      | 3         | 0.8%    |
| Perm           | 3         | 0.8%    |
| Mesa           | 3         | 0.8%    |
| Madrid         | 3         | 0.8%    |
| Gloucester     | 3         | 0.8%    |
| Waregem        | 2         | 0.53%   |
| Sydney         | 2         | 0.53%   |
| Shizuoka       | 2         | 0.53%   |
| Saint-Denis    | 2         | 0.53%   |
| Rio de Janeiro | 2         | 0.53%   |
| Prague         | 2         | 0.53%   |
| Oleksandrivka  | 2         | 0.53%   |
| Noblesville    | 2         | 0.53%   |
| New York       | 2         | 0.53%   |
| Munich         | 2         | 0.53%   |
| Mainz          | 2         | 0.53%   |
| Lublin         | 2         | 0.53%   |
| Las Vegas      | 2         | 0.53%   |
| Kharkiv        | 2         | 0.53%   |
| Istanbul       | 2         | 0.53%   |
| Hanover        | 2         | 0.53%   |
| Hakadal        | 2         | 0.53%   |
| Gorinchem      | 2         | 0.53%   |
| Fryazino       | 2         | 0.53%   |
| Donetsk        | 2         | 0.53%   |
| Cuenca         | 2         | 0.53%   |
| Burnaby        | 2         | 0.53%   |
| Ankara         | 2         | 0.53%   |
| Amsterdam      | 2         | 0.53%   |
| Ajdov????ina   | 2         | 0.53%   |
| Érd           | 1         | 0.27%   |
| Zurich         | 1         | 0.27%   |
| Zaragoza       | 1         | 0.27%   |
| Zagreb         | 1         | 0.27%   |
| Yekaterinburg  | 1         | 0.27%   |
| Wroclaw        | 1         | 0.27%   |
| Woolloongabba  | 1         | 0.27%   |
| Woodstock      | 1         | 0.27%   |
| Wenatchee      | 1         | 0.27%   |
| Waterloo       | 1         | 0.27%   |
| Voerde         | 1         | 0.27%   |
| Vladivostok    | 1         | 0.27%   |
| Vladimir       | 1         | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 100       | 136    | 17.89%  |
| WDC                 | 92        | 137    | 16.46%  |
| Seagate             | 82        | 118    | 14.67%  |
| Toshiba             | 38        | 52     | 6.8%    |
| Kingston            | 33        | 37     | 5.9%    |
| Crucial             | 28        | 30     | 5.01%   |
| Unknown             | 25        | 35     | 4.47%   |
| Intel               | 19        | 26     | 3.4%    |
| SanDisk             | 16        | 20     | 2.86%   |
| SK Hynix            | 13        | 15     | 2.33%   |
| Hitachi             | 13        | 14     | 2.33%   |
| A-DATA Technology   | 10        | 14     | 1.79%   |
| HGST                | 8         | 10     | 1.43%   |
| PNY                 | 5         | 5      | 0.89%   |
| Micron Technology   | 5         | 5      | 0.89%   |
| KIOXIA              | 5         | 5      | 0.89%   |
| China               | 5         | 5      | 0.89%   |
| Transcend           | 4         | 5      | 0.72%   |
| SPCC                | 4         | 4      | 0.72%   |
| Apple               | 4         | 4      | 0.72%   |
| Union Memory        | 3         | 3      | 0.54%   |
| Phison              | 3         | 6      | 0.54%   |
| Patriot             | 3         | 3      | 0.54%   |
| LITEONIT            | 3         | 3      | 0.54%   |
| Intenso             | 3         | 3      | 0.54%   |
| Gigabyte Technology | 3         | 3      | 0.54%   |
| SABRENT             | 2         | 2      | 0.36%   |
| Phison Electronics  | 2         | 2      | 0.36%   |
| LITEON              | 2         | 2      | 0.36%   |
| Lenovo              | 2         | 2      | 0.36%   |
| JMicron             | 2         | 2      | 0.36%   |
| Corsair             | 2         | 2      | 0.36%   |
| ZTC                 | 1         | 1      | 0.18%   |
| XPG                 | 1         | 1      | 0.18%   |
| TrueNAS             | 1         | 1      | 0.18%   |
| Team                | 1         | 1      | 0.18%   |
| T-FORCE             | 1         | 1      | 0.18%   |
| SILICONMOTION       | 1         | 1      | 0.18%   |
| Silicon Motion      | 1         | 2      | 0.18%   |
| OCZ                 | 1         | 1      | 0.18%   |
| Maxtor              | 1         | 2      | 0.18%   |
| Maximus             | 1         | 1      | 0.18%   |
| MaxDigital          | 1         | 2      | 0.18%   |
| Lexar               | 1         | 1      | 0.18%   |
| LDLC                | 1         | 1      | 0.18%   |
| KingDian            | 1         | 1      | 0.18%   |
| IBM-ESXS            | 1         | 2      | 0.18%   |
| Fujitsu             | 1         | 1      | 0.18%   |
| DOGFISH             | 1         | 1      | 0.18%   |
| ASUS-PHISON         | 1         | 1      | 0.18%   |
| Apacer              | 1         | 1      | 0.18%   |
| AMD                 | 1         | 1      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 1TB                 | 11        | 1.7%    |
| Samsung SSD 970 EVO Plus 1TB            | 10        | 1.55%   |
| Samsung SSD 850 EVO 250GB               | 7         | 1.08%   |
| Samsung SSD 970 EVO Plus 500GB          | 6         | 0.93%   |
| Samsung SSD 860 EVO 500GB               | 6         | 0.93%   |
| Samsung SSD 850 EVO 500GB               | 6         | 0.93%   |
| Seagate ST1000LM035-1RK172 1TB          | 5         | 0.77%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 5         | 0.77%   |
| Crucial CT500MX500SSD1 500GB            | 5         | 0.77%   |
| Toshiba HDWD110 1TB                     | 4         | 0.62%   |
| Toshiba DT01ACA200 2TB                  | 4         | 0.62%   |
| Seagate ST500DM002-1BD142 500GB         | 4         | 0.62%   |
| Seagate ST4000DM004-2CV104 4TB          | 4         | 0.62%   |
| Seagate ST1000DM010-2EP102 1TB          | 4         | 0.62%   |
| Samsung SSD 860 EVO 250GB               | 4         | 0.62%   |
| Kingston SV300S37A240G 240GB SSD        | 4         | 0.62%   |
| Kingston SA400S37240G 240GB SSD         | 4         | 0.62%   |
| Kingston SA400S37120G 120GB SSD         | 4         | 0.62%   |
| Crucial CT1000MX500SSD1 1TB             | 4         | 0.62%   |
| WDC WDS500G3X0C-00SJG0 500GB            | 3         | 0.46%   |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 3         | 0.46%   |
| WDC WDS120G2G0A-00JH30 120GB SSD        | 3         | 0.46%   |
| WDC WD10SPZX-21Z10T0 1TB                | 3         | 0.46%   |
| Unknown DA4064  64GB                    | 3         | 0.46%   |
| Toshiba MQ04ABF100 1TB                  | 3         | 0.46%   |
| Toshiba DT01ACA300 3TB                  | 3         | 0.46%   |
| Seagate ST2000LX001-1RG174 2TB          | 3         | 0.46%   |
| Seagate ST2000DM001-1ER164 2TB          | 3         | 0.46%   |
| Seagate Backup+ Hub BK 4TB              | 3         | 0.46%   |
| SanDisk SSD PLUS 240GB                  | 3         | 0.46%   |
| Samsung SSD 860 EVO M.2 1TB             | 3         | 0.46%   |
| Samsung SSD 840 PRO Series 256GB        | 3         | 0.46%   |
| Kingston SV300S37A120G 120GB SSD        | 3         | 0.46%   |
| Hitachi HUS724040ALE641 4TB             | 3         | 0.46%   |
| HGST HTS721010A9E630 1TB                | 3         | 0.46%   |
| Crucial CT500P1SSD8 500GB               | 3         | 0.46%   |
| Crucial CT1000P1SSD8 1TB                | 3         | 0.46%   |
| WDC WDS500G2B0C-00PXH0 500GB            | 2         | 0.31%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD        | 2         | 0.31%   |
| WDC WD20EZAZ-00GGJB0 2TB                | 2         | 0.31%   |
| WDC WD20EFRX-68EUZN0 2TB                | 2         | 0.31%   |
| WDC WD20EARX-00PASB0 2TB                | 2         | 0.31%   |
| WDC WD10JPVX-22JC3T0 1TB                | 2         | 0.31%   |
| WDC WD10EZEX-08WN4A0 1TB                | 2         | 0.31%   |
| WDC WD10EZEX-00BN5A0 1TB                | 2         | 0.31%   |
| WDC WD10EFRX-68FYTN0 1TB                | 2         | 0.31%   |
| WDC WD1003FZEX-00MK2A0 1TB              | 2         | 0.31%   |
| WDC PC SN730 SDBPNTY-1T00-1006 1TB      | 2         | 0.31%   |
| Unknown SL16G  16GB                     | 2         | 0.31%   |
| Unknown SD/MMC/MS PRO 128GB             | 2         | 0.31%   |
| Unknown MMC Card  64GB                  | 2         | 0.31%   |
| Unknown MMC Card  32GB                  | 2         | 0.31%   |
| Toshiba MQ01ACF032 320GB                | 2         | 0.31%   |
| Toshiba MQ01ABF050 500GB                | 2         | 0.31%   |
| Toshiba KXG60PNV2T04 NVMe KIOXIA 2048GB | 2         | 0.31%   |
| Seagate ST3160815AS 160GB               | 2         | 0.31%   |
| Seagate ST3000DM001-1CH166 3TB          | 2         | 0.31%   |
| Seagate ST2000DM008-2FR102 2TB          | 2         | 0.31%   |
| Seagate ST2000DM006-2DM164 2TB          | 2         | 0.31%   |
| Seagate ST1000LX015-1U7172 1TB          | 2         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 76        | 102    | 38.78%  |
| WDC                 | 63        | 95     | 32.14%  |
| Toshiba             | 25        | 38     | 12.76%  |
| Hitachi             | 13        | 14     | 6.63%   |
| HGST                | 8         | 10     | 4.08%   |
| Samsung Electronics | 7         | 8      | 3.57%   |
| SILICONMOTION       | 1         | 1      | 0.51%   |
| MaxDigital          | 1         | 2      | 0.51%   |
| IBM-ESXS            | 1         | 2      | 0.51%   |
| Fujitsu             | 1         | 1      | 0.51%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 57        | 77     | 29.38%  |
| Kingston            | 25        | 29     | 12.89%  |
| Crucial             | 20        | 21     | 10.31%  |
| WDC                 | 12        | 15     | 6.19%   |
| SanDisk             | 11        | 14     | 5.67%   |
| Intel               | 6         | 6      | 3.09%   |
| A-DATA Technology   | 6         | 7      | 3.09%   |
| China               | 5         | 5      | 2.58%   |
| Transcend           | 4         | 5      | 2.06%   |
| Toshiba             | 4         | 5      | 2.06%   |
| PNY                 | 4         | 4      | 2.06%   |
| SPCC                | 3         | 3      | 1.55%   |
| SK Hynix            | 3         | 3      | 1.55%   |
| Seagate             | 3         | 3      | 1.55%   |
| Patriot             | 3         | 3      | 1.55%   |
| LITEONIT            | 3         | 3      | 1.55%   |
| Micron Technology   | 2         | 2      | 1.03%   |
| Intenso             | 2         | 2      | 1.03%   |
| Apple               | 2         | 2      | 1.03%   |
| ZTC                 | 1         | 1      | 0.52%   |
| Unknown             | 1         | 1      | 0.52%   |
| Union Memory        | 1         | 1      | 0.52%   |
| TrueNAS             | 1         | 1      | 0.52%   |
| Team                | 1         | 1      | 0.52%   |
| T-FORCE             | 1         | 1      | 0.52%   |
| OCZ                 | 1         | 1      | 0.52%   |
| Maxtor              | 1         | 2      | 0.52%   |
| Maximus             | 1         | 1      | 0.52%   |
| LITEON              | 1         | 1      | 0.52%   |
| Lexar               | 1         | 1      | 0.52%   |
| LDLC                | 1         | 1      | 0.52%   |
| KingDian            | 1         | 1      | 0.52%   |
| JMicron             | 1         | 1      | 0.52%   |
| Gigabyte Technology | 1         | 1      | 0.52%   |
| DOGFISH             | 1         | 1      | 0.52%   |
| ASUS-PHISON         | 1         | 1      | 0.52%   |
| Apacer              | 1         | 1      | 0.52%   |
| AMD                 | 1         | 1      | 0.52%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 179       | 229    | 34.03%  |
| HDD     | 167       | 273    | 31.75%  |
| NVMe    | 148       | 182    | 28.14%  |
| MMC     | 22        | 33     | 4.18%   |
| Unknown | 10        | 17     | 1.9%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 265       | 487    | 57.99%  |
| NVMe | 147       | 180    | 32.17%  |
| SAS  | 23        | 34     | 5.03%   |
| MMC  | 22        | 33     | 4.81%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 184       | 250    | 50.69%  |
| 0.51-1.0   | 106       | 131    | 29.2%   |
| 1.01-2.0   | 41        | 49     | 11.29%  |
| 3.01-4.0   | 13        | 32     | 3.58%   |
| 2.01-3.0   | 10        | 15     | 2.75%   |
| 4.01-10.0  | 6         | 17     | 1.65%   |
| 10.01-20.0 | 3         | 8      | 0.83%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 76        | 20.27%  |
| 101-250        | 74        | 19.73%  |
| 501-1000       | 51        | 13.6%   |
| 1001-2000      | 43        | 11.47%  |
| More than 3000 | 34        | 9.07%   |
| 1-20           | 32        | 8.53%   |
| 51-100         | 25        | 6.67%   |
| Unknown        | 16        | 4.27%   |
| 21-50          | 14        | 3.73%   |
| 2001-3000      | 10        | 2.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 110       | 29.02%  |
| 101-250        | 51        | 13.46%  |
| 21-50          | 50        | 13.19%  |
| 51-100         | 40        | 10.55%  |
| 251-500        | 36        | 9.5%    |
| 501-1000       | 33        | 8.71%   |
| 1001-2000      | 20        | 5.28%   |
| Unknown        | 16        | 4.22%   |
| More than 3000 | 12        | 3.17%   |
| 2001-3000      | 8         | 2.11%   |
| 0              | 3         | 0.79%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB              | 2         | 2      | 3.13%   |
| WDC WD5003ABYX-18WERA0 500GB                 | 1         | 2      | 1.56%   |
| WDC WD5000AAKX-00U6AA0 500GB                 | 1         | 1      | 1.56%   |
| WDC WD5000AAKX-00ERMA0 500GB                 | 1         | 1      | 1.56%   |
| WDC WD5000AAKS-22V1A0 500GB                  | 1         | 1      | 1.56%   |
| WDC WD5000AAJS-22A8B0 500GB                  | 1         | 1      | 1.56%   |
| WDC WD40EFZX-68AWUN0 4TB                     | 1         | 6      | 1.56%   |
| WDC WD400BB-00DEA0 40GB                      | 1         | 1      | 1.56%   |
| WDC WD20EFRX-68EUZN0 2TB                     | 1         | 2      | 1.56%   |
| WDC WD20EARX-00PASB0 2TB                     | 1         | 1      | 1.56%   |
| WDC WD20EARS-00MVWB0 2TB                     | 1         | 1      | 1.56%   |
| WDC WD1600AAJS-00L7A0 160GB                  | 1         | 1      | 1.56%   |
| WDC WD10JPVX-60JC3T0 1TB                     | 1         | 1      | 1.56%   |
| WDC WD10JPVX-22JC3T0 1TB                     | 1         | 1      | 1.56%   |
| WDC WD10JPVT-75A1YT0 1TB                     | 1         | 1      | 1.56%   |
| WDC WD10EZEX-08WN4A0 1TB                     | 1         | 1      | 1.56%   |
| WDC WD10EZEX-00BN5A0 1TB                     | 1         | 1      | 1.56%   |
| WDC WD1001FALS-75J7B0 1TB                    | 1         | 1      | 1.56%   |
| Toshiba MQ04ABF100 1TB                       | 1         | 1      | 1.56%   |
| Toshiba MQ01ABF050 500GB                     | 1         | 1      | 1.56%   |
| Toshiba MQ01ABD100 1TB                       | 1         | 1      | 1.56%   |
| Toshiba MK2565GSX 250GB                      | 1         | 1      | 1.56%   |
| Toshiba DT01ACA050 500GB                     | 1         | 1      | 1.56%   |
| SK Hynix PC401 NVMe 512GB                    | 1         | 2      | 1.56%   |
| Seagate ST9320325AS 320GB                    | 1         | 1      | 1.56%   |
| Seagate ST9160310AS 160GB                    | 1         | 1      | 1.56%   |
| Seagate ST500LT012-9WS142 500GB              | 1         | 1      | 1.56%   |
| Seagate ST3320620A 320GB                     | 1         | 1      | 1.56%   |
| Seagate ST3200827AS 200GB                    | 1         | 1      | 1.56%   |
| Seagate ST32000542AS 2TB                     | 1         | 1      | 1.56%   |
| Seagate ST3160813AS 160GB                    | 1         | 1      | 1.56%   |
| Seagate ST31500341AS 1TB                     | 1         | 1      | 1.56%   |
| Seagate ST3120827AS 120GB                    | 1         | 1      | 1.56%   |
| Seagate ST31000333AS 1TB                     | 1         | 1      | 1.56%   |
| Seagate ST3000DM001-9YN166 3TB               | 1         | 1      | 1.56%   |
| Seagate ST250DM000-1BD141 250GB              | 1         | 1      | 1.56%   |
| Seagate ST2000LX001-1RG174 2TB               | 1         | 1      | 1.56%   |
| Seagate ST2000DM001-1ER164 2TB               | 1         | 1      | 1.56%   |
| Seagate ST1000LX015-1U7172 1TB               | 1         | 1      | 1.56%   |
| Seagate ST1000LM035-1RK172 1TB               | 1         | 1      | 1.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1      | 1.56%   |
| Seagate ST1000DM003-9YN162 1TB               | 1         | 1      | 1.56%   |
| Seagate ST1000DM003-1CH162 1TB               | 1         | 1      | 1.56%   |
| SanDisk SSD PLUS 120 GB                      | 1         | 1      | 1.56%   |
| Samsung Electronics SSD 970 EVO 250GB        | 1         | 1      | 1.56%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 2      | 1.56%   |
| Samsung Electronics HD161GJ 160GB            | 1         | 1      | 1.56%   |
| PNY SSD2SC240G3LC709B121-460P 240GB          | 1         | 1      | 1.56%   |
| LITEONIT LMT-64M6M-HP 64GB SSD               | 1         | 1      | 1.56%   |
| Kingston SV300S37A120G 120GB SSD             | 1         | 1      | 1.56%   |
| Kingston SE100S3100G 100GB SSD               | 1         | 1      | 1.56%   |
| KingDian S280 240GB                          | 1         | 1      | 1.56%   |
| Intel SSDSC2KW120H6 120GB                    | 1         | 1      | 1.56%   |
| Intel SSDSC2BF180A4H 180GB                   | 1         | 1      | 1.56%   |
| Intel SSDPEKKW010T7 1TB                      | 1         | 2      | 1.56%   |
| Hitachi HUA722020ALA331 2TB                  | 1         | 1      | 1.56%   |
| Hitachi HTS545050A7E380 500GB                | 1         | 1      | 1.56%   |
| Hitachi HTS543212L9A300 120GB                | 1         | 1      | 1.56%   |
| Hitachi HDS722525VLAT80 250GB                | 1         | 1      | 1.56%   |
| HGST HTS725050A7E630 500GB                   | 1         | 1      | 1.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 21     | 30.65%  |
| WDC                 | 17        | 24     | 27.42%  |
| Toshiba             | 5         | 5      | 8.06%   |
| Hitachi             | 4         | 4      | 6.45%   |
| Samsung Electronics | 3         | 4      | 4.84%   |
| Intel               | 3         | 4      | 4.84%   |
| A-DATA Technology   | 3         | 4      | 4.84%   |
| Kingston            | 2         | 2      | 3.23%   |
| SK Hynix            | 1         | 2      | 1.61%   |
| SanDisk             | 1         | 1      | 1.61%   |
| PNY                 | 1         | 1      | 1.61%   |
| LITEONIT            | 1         | 1      | 1.61%   |
| KingDian            | 1         | 1      | 1.61%   |
| HGST                | 1         | 1      | 1.61%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 21     | 40.43%  |
| WDC                 | 17        | 24     | 36.17%  |
| Toshiba             | 5         | 5      | 10.64%  |
| Hitachi             | 4         | 4      | 8.51%   |
| Samsung Electronics | 1         | 1      | 2.13%   |
| HGST                | 1         | 1      | 2.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 46        | 56     | 75.41%  |
| SSD  | 12        | 14     | 19.67%  |
| NVMe | 3         | 5      | 4.92%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Seagate ST500DM005 HD502HJ 500GB | 1         | 1      | 50%     |
| Seagate ST3500830AS 500GB        | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 308       | 534    | 70.97%  |
| Detected | 66        | 123    | 15.21%  |
| Malfunc  | 58        | 75     | 13.36%  |
| Failed   | 2         | 2      | 0.46%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 230       | 48.63%  |
| AMD                          | 75        | 15.86%  |
| Samsung Electronics          | 51        | 10.78%  |
| Sandisk                      | 26        | 5.5%    |
| SK Hynix                     | 10        | 2.11%   |
| Phison Electronics           | 10        | 2.11%   |
| Micron/Crucial Technology    | 9         | 1.9%    |
| Kingston Technology Company  | 8         | 1.69%   |
| Toshiba America Info Systems | 7         | 1.48%   |
| ASMedia Technology           | 7         | 1.48%   |
| KIOXIA                       | 6         | 1.27%   |
| ADATA Technology             | 5         | 1.06%   |
| Marvell Technology Group     | 4         | 0.85%   |
| JMicron Technology           | 4         | 0.85%   |
| Broadcom / LSI               | 4         | 0.85%   |
| Micron Technology            | 3         | 0.63%   |
| Union Memory (Shenzhen)      | 2         | 0.42%   |
| Nvidia                       | 2         | 0.42%   |
| Lenovo                       | 2         | 0.42%   |
| VIA Technologies             | 1         | 0.21%   |
| Silicon Motion               | 1         | 0.21%   |
| Silicon Image                | 1         | 0.21%   |
| Seagate Technology           | 1         | 0.21%   |
| OCZ Technology Group         | 1         | 0.21%   |
| Lite-On Technology           | 1         | 0.21%   |
| Apple                        | 1         | 0.21%   |
| Adaptec                      | 1         | 0.21%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 53        | 9.71%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 33        | 6.04%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 23        | 4.21%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 21        | 3.85%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 16        | 2.93%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 16        | 2.93%   |
| AMD 400 Series Chipset SATA Controller                                                  | 15        | 2.75%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 13        | 2.38%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 10        | 1.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 10        | 1.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 9         | 1.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9         | 1.65%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 9         | 1.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 9         | 1.65%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 8         | 1.47%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 8         | 1.47%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 8         | 1.47%   |
| Phison E12 NVMe Controller                                                              | 7         | 1.28%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 7         | 1.28%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 6         | 1.1%    |
| Samsung NVMe Controller                                                                 | 6         | 1.1%    |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 6         | 1.1%    |
| KIOXIA Non-Volatile memory controller                                                   | 6         | 1.1%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 6         | 1.1%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6         | 1.1%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 5         | 0.92%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 5         | 0.92%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5         | 0.92%   |
| AMD 300 Series Chipset SATA Controller                                                  | 5         | 0.92%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 4         | 0.73%   |
| Intel SSD 660P Series                                                                   | 4         | 0.73%   |
| Intel SATA Controller [RAID mode]                                                       | 4         | 0.73%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 4         | 0.73%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 4         | 0.73%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4         | 0.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4         | 0.73%   |
| SK Hynix NVMe SSD Controller                                                            | 3         | 0.55%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 3         | 0.55%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 3         | 0.55%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 3         | 0.55%   |
| Micron Non-Volatile memory controller                                                   | 3         | 0.55%   |
| Kingston Company Company Non-Volatile memory controller                                 | 3         | 0.55%   |
| Intel SSD 600P Series                                                                   | 3         | 0.55%   |
| Intel NVMe Optane Memory Series                                                         | 3         | 0.55%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 3         | 0.55%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3         | 0.55%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 3         | 0.55%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3         | 0.55%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3         | 0.55%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 0.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 3         | 0.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 3         | 0.55%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3         | 0.55%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3         | 0.55%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3         | 0.55%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3         | 0.55%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 3         | 0.55%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                  | 2         | 0.37%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                             | 2         | 0.37%   |
| SK Hynix BC511                                                                          | 2         | 0.37%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 259       | 53.62%  |
| NVMe | 147       | 30.43%  |
| IDE  | 37        | 7.66%   |
| RAID | 34        | 7.04%   |
| SAS  | 6         | 1.24%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 275       | 73.73%  |
| AMD    | 91        | 24.4%   |
| ARM    | 7         | 1.88%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor               | 9         | 2.41%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 8         | 2.14%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 8         | 2.14%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 8         | 2.14%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 7         | 1.88%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 6         | 1.61%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 6         | 1.61%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 5         | 1.34%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 5         | 1.34%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 5         | 1.34%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics      | 5         | 1.34%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 5         | 1.34%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz              | 4         | 1.07%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 4         | 1.07%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 4         | 1.07%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 4         | 1.07%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 4         | 1.07%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 4         | 1.07%   |
| ARM Processor                                   | 4         | 1.07%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 4         | 1.07%   |
| Intel Pentium CPU N4200 @ 1.10GHz               | 3         | 0.8%    |
| Intel Core i7-9750H CPU @ 2.60GHz               | 3         | 0.8%    |
| Intel Core i7-8750H CPU @ 2.20GHz               | 3         | 0.8%    |
| Intel Core i7-7700 CPU @ 3.60GHz                | 3         | 0.8%    |
| Intel Core i7-7500U CPU @ 2.70GHz               | 3         | 0.8%    |
| Intel Core i7-10750H CPU @ 2.60GHz              | 3         | 0.8%    |
| Intel Core i5-4570 CPU @ 3.20GHz                | 3         | 0.8%    |
| Intel Core i5-4300U CPU @ 1.90GHz               | 3         | 0.8%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 3         | 0.8%    |
| AMD Ryzen 9 3900X 12-Core Processor             | 3         | 0.8%    |
| AMD Ryzen 7 5800X 8-Core Processor              | 3         | 0.8%    |
| AMD Ryzen 5 5600X 6-Core Processor              | 3         | 0.8%    |
| Intel Pentium Gold G5420 CPU @ 3.80GHz          | 2         | 0.54%   |
| Intel Core i7-8700K CPU @ 3.70GHz               | 2         | 0.54%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 2         | 0.54%   |
| Intel Core i7-5600U CPU @ 2.60GHz               | 2         | 0.54%   |
| Intel Core i7-3612QM CPU @ 2.10GHz              | 2         | 0.54%   |
| Intel Core i7-3537U CPU @ 2.00GHz               | 2         | 0.54%   |
| Intel Core i7-2640M CPU @ 2.80GHz               | 2         | 0.54%   |
| Intel Core i7-10710U CPU @ 1.10GHz              | 2         | 0.54%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 2         | 0.54%   |
| Intel Core i5-7500 CPU @ 3.40GHz                | 2         | 0.54%   |
| Intel Core i5-6600 CPU @ 3.30GHz                | 2         | 0.54%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 2         | 0.54%   |
| Intel Core i5-4460 CPU @ 3.20GHz                | 2         | 0.54%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 2         | 0.54%   |
| Intel Core i5-2500K CPU @ 3.30GHz               | 2         | 0.54%   |
| Intel Core i5-2450M CPU @ 2.50GHz               | 2         | 0.54%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 2         | 0.54%   |
| Intel Core i5-10300H CPU @ 2.50GHz              | 2         | 0.54%   |
| Intel Core i5 CPU 650 @ 3.20GHz                 | 2         | 0.54%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz              | 2         | 0.54%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz           | 2         | 0.54%   |
| Intel Core 2 Duo CPU T6400 @ 2.00GHz            | 2         | 0.54%   |
| Intel Celeron N4020 CPU @ 1.10GHz               | 2         | 0.54%   |
| Intel Celeron M processor 900MHz                | 2         | 0.54%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 2         | 0.54%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 2         | 0.54%   |
| AMD Ryzen 5 3600X 6-Core Processor              | 2         | 0.54%   |
| AMD Phenom II X4 965 Processor                  | 2         | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 98        | 26.27%  |
| Intel Core i7          | 79        | 21.18%  |
| AMD Ryzen 5            | 29        | 7.77%   |
| Other                  | 21        | 5.63%   |
| AMD Ryzen 7            | 19        | 5.09%   |
| Intel Celeron          | 17        | 4.56%   |
| Intel Core i3          | 15        | 4.02%   |
| Intel Xeon             | 12        | 3.22%   |
| Intel Core 2 Duo       | 11        | 2.95%   |
| Intel Pentium          | 9         | 2.41%   |
| AMD Ryzen 7 PRO        | 7         | 1.88%   |
| AMD Ryzen 9            | 5         | 1.34%   |
| AMD Ryzen 3            | 4         | 1.07%   |
| AMD Phenom II X4       | 4         | 1.07%   |
| AMD FX                 | 4         | 1.07%   |
| Intel Core 2 Quad      | 3         | 0.8%    |
| Intel Atom             | 3         | 0.8%    |
| AMD Ryzen Threadripper | 3         | 0.8%    |
| Intel Pentium M        | 2         | 0.54%   |
| Intel Pentium Gold     | 2         | 0.54%   |
| Intel Core 2           | 2         | 0.54%   |
| Intel Celeron M        | 2         | 0.54%   |
| AMD Athlon X4          | 2         | 0.54%   |
| AMD A10                | 2         | 0.54%   |
| Intel Xeon Silver      | 1         | 0.27%   |
| Intel Pentium 4        | 1         | 0.27%   |
| Intel Core m7          | 1         | 0.27%   |
| Intel Core i9          | 1         | 0.27%   |
| ARM BCM                | 1         | 0.27%   |
| ARM Allwinner          | 1         | 0.27%   |
| ARM AArch64            | 1         | 0.27%   |
| AMD Sempron            | 1         | 0.27%   |
| AMD PRO A8             | 1         | 0.27%   |
| AMD GX                 | 1         | 0.27%   |
| AMD C-30               | 1         | 0.27%   |
| AMD Athlon XP          | 1         | 0.27%   |
| AMD Athlon II X2       | 1         | 0.27%   |
| AMD Athlon II Neo      | 1         | 0.27%   |
| AMD Athlon Dual Core   | 1         | 0.27%   |
| AMD A8                 | 1         | 0.27%   |
| AMD A6                 | 1         | 0.27%   |
| AMD A12                | 1         | 0.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 148       | 39.68%  |
| 2      | 123       | 32.98%  |
| 6      | 45        | 12.06%  |
| 8      | 32        | 8.58%   |
| 1      | 12        | 3.22%   |
| 12     | 6         | 1.61%   |
| 16     | 4         | 1.07%   |
| 44     | 1         | 0.27%   |
| 32     | 1         | 0.27%   |
| 28     | 1         | 0.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 367       | 98.39%  |
| 2      | 6         | 1.61%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 265       | 71.05%  |
| 1      | 108       | 28.95%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 362       | 97.05%  |
| 32-bit         | 7         | 1.88%   |
| 64-bit         | 2         | 0.54%   |
| Unknown        | 2         | 0.54%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 70        | 18.62%  |
| 0x306a9    | 28        | 7.45%   |
| 0x206a7    | 18        | 4.79%   |
| 0x306c3    | 15        | 3.99%   |
| 0x08701021 | 14        | 3.72%   |
| 0x806c1    | 13        | 3.46%   |
| 0x906ea    | 12        | 3.19%   |
| 0x806ec    | 11        | 2.93%   |
| 0x806e9    | 11        | 2.93%   |
| 0x806ea    | 10        | 2.66%   |
| 0x406e3    | 9         | 2.39%   |
| 0x306d4    | 9         | 2.39%   |
| 0x706e5    | 8         | 2.13%   |
| 0x08600106 | 8         | 2.13%   |
| 0x906e9    | 7         | 1.86%   |
| 0xa0652    | 6         | 1.6%    |
| 0x506e3    | 6         | 1.6%    |
| 0x1067a    | 6         | 1.6%    |
| 0x08108109 | 6         | 1.6%    |
| 0x06003106 | 6         | 1.6%    |
| 0x806eb    | 5         | 1.33%   |
| 0x506c9    | 5         | 1.33%   |
| 0x40651    | 5         | 1.33%   |
| 0x206d7    | 5         | 1.33%   |
| 0x0a201009 | 4         | 1.06%   |
| 0x306f2    | 3         | 0.8%    |
| 0x20655    | 3         | 0.8%    |
| 0x0800820d | 3         | 0.8%    |
| 0x08001138 | 3         | 0.8%    |
| 0x010000c8 | 3         | 0.8%    |
| 0xa0660    | 2         | 0.53%   |
| 0xa0655    | 2         | 0.53%   |
| 0x706a8    | 2         | 0.53%   |
| 0x6fb      | 2         | 0.53%   |
| 0x6f6      | 2         | 0.53%   |
| 0x6d8      | 2         | 0.53%   |
| 0x695      | 2         | 0.53%   |
| 0x406c4    | 2         | 0.53%   |
| 0x406c3    | 2         | 0.53%   |
| 0x30678    | 2         | 0.53%   |
| 0x0a201016 | 2         | 0.53%   |
| 0x08701013 | 2         | 0.53%   |
| 0x08108102 | 2         | 0.53%   |
| 0x010000b6 | 2         | 0.53%   |
| 0xf41      | 1         | 0.27%   |
| 0xf29      | 1         | 0.27%   |
| 0xa0671    | 1         | 0.27%   |
| 0xa0653    | 1         | 0.27%   |
| 0x906ed    | 1         | 0.27%   |
| 0x906ec    | 1         | 0.27%   |
| 0x906eb    | 1         | 0.27%   |
| 0x706a1    | 1         | 0.27%   |
| 0x6fd      | 1         | 0.27%   |
| 0x6fa      | 1         | 0.27%   |
| 0x50657    | 1         | 0.27%   |
| 0x50654    | 1         | 0.27%   |
| 0x406f1    | 1         | 0.27%   |
| 0x406d8    | 1         | 0.27%   |
| 0x40661    | 1         | 0.27%   |
| 0x306e4    | 1         | 0.27%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 73        | 19.57%  |
| Zen 2         | 34        | 9.12%   |
| IvyBridge     | 34        | 9.12%   |
| Haswell       | 30        | 8.04%   |
| Skylake       | 23        | 6.17%   |
| SandyBridge   | 23        | 6.17%   |
| Zen+          | 17        | 4.56%   |
| TigerLake     | 15        | 4.02%   |
| CometLake     | 12        | 3.22%   |
| Broadwell     | 10        | 2.68%   |
| Zen 3         | 9         | 2.41%   |
| Core          | 9         | 2.41%   |
| Unknown       | 9         | 2.41%   |
| Penryn        | 8         | 2.14%   |
| IceLake       | 8         | 2.14%   |
| Steamroller   | 7         | 1.88%   |
| Silvermont    | 7         | 1.88%   |
| K10           | 7         | 1.88%   |
| Zen           | 6         | 1.61%   |
| Westmere      | 5         | 1.34%   |
| Goldmont      | 5         | 1.34%   |
| P6            | 4         | 1.07%   |
| Goldmont plus | 3         | 0.8%    |
| Piledriver    | 2         | 0.54%   |
| NetBurst      | 2         | 0.54%   |
| Nehalem       | 2         | 0.54%   |
| Excavator     | 2         | 0.54%   |
| Bulldozer     | 2         | 0.54%   |
| K8 Hammer     | 1         | 0.27%   |
| K6            | 1         | 0.27%   |
| Jaguar        | 1         | 0.27%   |
| Bonnell       | 1         | 0.27%   |
| Bobcat        | 1         | 0.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 216       | 50.7%   |
| Nvidia                     | 109       | 25.59%  |
| AMD                        | 93        | 21.83%  |
| ASPEED Technology          | 5         | 1.17%   |
| Matrox Electronics Systems | 3         | 0.7%    |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 23        | 5.31%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 16        | 3.7%    |
| Intel UHD Graphics 620                                                                   | 15        | 3.46%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 15        | 3.46%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 14        | 3.23%   |
| AMD Renoir                                                                               | 12        | 2.77%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 11        | 2.54%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 2.31%   |
| Intel HD Graphics 620                                                                    | 10        | 2.31%   |
| AMD Picasso                                                                              | 10        | 2.31%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 8         | 1.85%   |
| Intel HD Graphics 5500                                                                   | 8         | 1.85%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 6         | 1.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 1.39%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 1.39%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 1.39%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 1.39%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 1.39%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 6         | 1.39%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 5         | 1.15%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 5         | 1.15%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 5         | 1.15%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 0.92%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 4         | 0.92%   |
| Nvidia GK107M [GeForce GT 640M]                                                          | 4         | 0.92%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 0.92%   |
| Intel Iris Plus Graphics G7                                                              | 4         | 0.92%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 0.92%   |
| Intel HD Graphics 630                                                                    | 4         | 0.92%   |
| Intel HD Graphics 530                                                                    | 4         | 0.92%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 4         | 0.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 0.92%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 0.92%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 4         | 0.92%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.69%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.69%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 0.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 3         | 0.69%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.46%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2         | 0.46%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 2         | 0.46%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2         | 0.46%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2         | 0.46%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 2         | 0.46%   |
| Nvidia GK104 [GeForce GTX 670]                                                           | 2         | 0.46%   |
| Nvidia GF119M [NVS 4200M]                                                                | 2         | 0.46%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.46%   |
| Nvidia GF104 [GeForce GTX 460]                                                           | 2         | 0.46%   |
| Nvidia G98 [Quadro NVS 295]                                                              | 2         | 0.46%   |
| Matrox Electronics Systems G200eR2                                                       | 2         | 0.46%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.46%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.46%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.46%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 2         | 0.46%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.46%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 2         | 0.46%   |
| Intel HD Graphics 515                                                                    | 2         | 0.46%   |
| Intel HD Graphics 500                                                                    | 2         | 0.46%   |
| Intel Comet Lake UHD Graphics                                                            | 2         | 0.46%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 2         | 0.46%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 161       | 42.93%  |
| 1 x AMD         | 75        | 20%     |
| 1 x Nvidia      | 64        | 17.07%  |
| Intel + Nvidia  | 42        | 11.2%   |
| Intel + AMD     | 11        | 2.93%   |
| Other           | 8         | 2.13%   |
| 1 x ASPEED      | 4         | 1.07%   |
| 2 x AMD         | 3         | 0.8%    |
| AMD + Nvidia    | 3         | 0.8%    |
| 1 x Matrox      | 2         | 0.53%   |
| Nvidia + Matrox | 1         | 0.27%   |
| AMD + ASPEED    | 1         | 0.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 319       | 85.29%  |
| Proprietary | 41        | 10.96%  |
| Unknown     | 14        | 3.74%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 237       | 62.86%  |
| 1.01-2.0   | 31        | 8.22%   |
| 0.01-0.5   | 28        | 7.43%   |
| 0.51-1.0   | 24        | 6.37%   |
| 7.01-8.0   | 22        | 5.84%   |
| 3.01-4.0   | 22        | 5.84%   |
| 5.01-6.0   | 7         | 1.86%   |
| 2.01-3.0   | 2         | 0.53%   |
| 8.01-16.0  | 2         | 0.53%   |
| 24.01-32.0 | 1         | 0.27%   |
| 16.01-24.0 | 1         | 0.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 49        | 11.81%  |
| Samsung Electronics     | 42        | 10.12%  |
| Chimei Innolux          | 38        | 9.16%   |
| LG Display              | 36        | 8.67%   |
| BOE                     | 36        | 8.67%   |
| Dell                    | 31        | 7.47%   |
| Goldstar                | 25        | 6.02%   |
| Ancor Communications    | 17        | 4.1%    |
| Acer                    | 17        | 4.1%    |
| BenQ                    | 14        | 3.37%   |
| Hewlett-Packard         | 13        | 3.13%   |
| Sharp                   | 10        | 2.41%   |
| Philips                 | 10        | 2.41%   |
| AOC                     | 9         | 2.17%   |
| Lenovo                  | 7         | 1.69%   |
| ASUSTek Computer        | 5         | 1.2%    |
| Apple                   | 5         | 1.2%    |
| ViewSonic               | 4         | 0.96%   |
| InfoVision              | 4         | 0.96%   |
| Unknown                 | 3         | 0.72%   |
| Iiyama                  | 3         | 0.72%   |
| Vestel Elektronik       | 2         | 0.48%   |
| Sony                    | 2         | 0.48%   |
| NEC Computers           | 2         | 0.48%   |
| LG Electronics          | 2         | 0.48%   |
| Eizo                    | 2         | 0.48%   |
| CPT                     | 2         | 0.48%   |
| ___                     | 1         | 0.24%   |
| Vizio                   | 1         | 0.24%   |
| TEO                     | 1         | 0.24%   |
| Prestigio               | 1         | 0.24%   |
| PANDA                   | 1         | 0.24%   |
| ODH                     | 1         | 0.24%   |
| NCS                     | 1         | 0.24%   |
| MSI                     | 1         | 0.24%   |
| MIT                     | 1         | 0.24%   |
| Mi                      | 1         | 0.24%   |
| Medion                  | 1         | 0.24%   |
| LPL                     | 1         | 0.24%   |
| JXG                     | 1         | 0.24%   |
| JVC                     | 1         | 0.24%   |
| JRY                     | 1         | 0.24%   |
| IOD                     | 1         | 0.24%   |
| INFOTRONIC              | 1         | 0.24%   |
| Idek Iiyama             | 1         | 0.24%   |
| Hitachi                 | 1         | 0.24%   |
| HannStar                | 1         | 0.24%   |
| CSO                     | 1         | 0.24%   |
| COBY                    | 1         | 0.24%   |
| CMN                     | 1         | 0.24%   |
| Chi Mei Optoelectronics | 1         | 0.24%   |
| Belinea                 | 1         | 0.24%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Dell E176FP DELA014 1280x1024 340x270mm 17.1-inch                      | 4         | 0.94%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch          | 4         | 0.94%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch            | 3         | 0.7%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch       | 3         | 0.7%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch         | 3         | 0.7%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch         | 3         | 0.7%    |
| AU Optronics LCD Monitor AUO235C 1366x768 260x140mm 11.6-inch          | 3         | 0.7%    |
| ASUSTek Computer MZ279 AUS27CA 1920x1080 598x336mm 27.0-inch           | 3         | 0.7%    |
| ViewSonic VX3211-2K VSCF634 2560x1440 698x392mm 31.5-inch              | 2         | 0.47%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 2         | 0.47%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 2         | 0.47%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                | 2         | 0.47%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch                | 2         | 0.47%   |
| Samsung Electronics SyncMaster SAM0656 1920x1080 510x287mm 23.0-inch   | 2         | 0.47%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 1050x590mm 47.4-inch | 2         | 0.47%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 2         | 0.47%   |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch           | 2         | 0.47%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch           | 2         | 0.47%   |
| Lenovo L2251x Wide LEN0A12 1680x1050 474x296mm 22.0-inch               | 2         | 0.47%   |
| Hewlett-Packard ZR30w HWP286C 2560x1600 641x400mm 29.7-inch            | 2         | 0.47%   |
| Hewlett-Packard Z23i HWP308F 1920x1080 509x286mm 23.0-inch             | 2         | 0.47%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch           | 2         | 0.47%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 2         | 0.47%   |
| Goldstar LG ULTRAWIDE GSM59F1 1920x1080 580x240mm 24.7-inch            | 2         | 0.47%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 2         | 0.47%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2         | 0.47%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                 | 2         | 0.47%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 2         | 0.47%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                      | 2         | 0.47%   |
| Dell LCD Monitor U2312HM 1920x1080                                     | 2         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 2         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch       | 2         | 0.47%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch       | 2         | 0.47%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch       | 2         | 0.47%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 2         | 0.47%   |
| BOE LCD Monitor BOE097D 1920x1080 344x194mm 15.5-inch                  | 2         | 0.47%   |
| BOE LCD Monitor BOE0903 1920x1080 344x194mm 15.5-inch                  | 2         | 0.47%   |
| BOE LCD Monitor BOE0868 1920x1080 309x174mm 14.0-inch                  | 2         | 0.47%   |
| BOE LCD Monitor BOE06CE 1366x768 277x156mm 12.5-inch                   | 2         | 0.47%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                  | 2         | 0.47%   |
| BenQ LCD BNQ801B 2560x1440 527x296mm 23.8-inch                         | 2         | 0.47%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch          | 2         | 0.47%   |
| AU Optronics LCD Monitor AUO5C2D 1920x1080 293x165mm 13.2-inch         | 2         | 0.47%   |
| AU Optronics LCD Monitor AUO223E 1600x900 309x174mm 14.0-inch          | 2         | 0.47%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch         | 2         | 0.47%   |
| AU Optronics LCD Monitor AUO139D 1920x1080 381x214mm 17.2-inch         | 2         | 0.47%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch         | 2         | 0.47%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch         | 2         | 0.47%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch         | 2         | 0.47%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch          | 2         | 0.47%   |
| Ancor Communications ASUS VH236H ACI23F2 1920x1080 520x290mm 23.4-inch | 2         | 0.47%   |
| Ancor Communications ASUS PA238 ACI23B1 1920x1080 509x286mm 23.0-inch  | 2         | 0.47%   |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                      | 2         | 0.47%   |
| ___ LCDTV16 ___0101 1600x1200 1600x900mm 72.3-inch                     | 1         | 0.23%   |
| Vizio D32h-D1 VIZ1002 1360x768 697x392mm 31.5-inch                     | 1         | 0.23%   |
| ViewSonic VA926 Series VSC7D20 1280x1024 376x301mm 19.0-inch           | 1         | 0.23%   |
| ViewSonic LCD Monitor XG2401 SERIES                                    | 1         | 0.23%   |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                    | 1         | 0.23%   |
| TEO TL565 TEO5550 1024x768 304x228mm 15.0-inch                         | 1         | 0.23%   |
| Sony TV SNY4D04 1920x1080 1600x900mm 72.3-inch                         | 1         | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 178       | 44.17%  |
| 1366x768 (WXGA)    | 60        | 14.89%  |
| 3840x2160 (4K)     | 31        | 7.69%   |
| 2560x1440 (QHD)    | 26        | 6.45%   |
| 1600x900 (HD+)     | 20        | 4.96%   |
| 1920x1200 (WUXGA)  | 15        | 3.72%   |
| 1280x1024 (SXGA)   | 15        | 3.72%   |
| 1680x1050 (WSXGA+) | 11        | 2.73%   |
| 1440x900 (WXGA+)   | 7         | 1.74%   |
| 1280x800 (WXGA)    | 5         | 1.24%   |
| Unknown            | 5         | 1.24%   |
| 2560x1080          | 4         | 0.99%   |
| 1024x768 (XGA)     | 4         | 0.99%   |
| 2560x1600          | 3         | 0.74%   |
| 1600x1200          | 3         | 0.74%   |
| 3440x1440          | 2         | 0.5%    |
| 2288x1287          | 2         | 0.5%    |
| 7680x4320          | 1         | 0.25%   |
| 5760x1080          | 1         | 0.25%   |
| 4480x1440          | 1         | 0.25%   |
| 3840x2400          | 1         | 0.25%   |
| 3840x1080          | 1         | 0.25%   |
| 3360x1080          | 1         | 0.25%   |
| 2880x1800          | 1         | 0.25%   |
| 2256x1504          | 1         | 0.25%   |
| 2160x1440          | 1         | 0.25%   |
| 1920x540           | 1         | 0.25%   |
| 1792x768           | 1         | 0.25%   |
| 1024x600           | 1         | 0.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 71        | 17.19%  |
| 13      | 52        | 12.59%  |
| 24      | 41        | 9.93%   |
| 14      | 39        | 9.44%   |
| 27      | 33        | 7.99%   |
| 23      | 31        | 7.51%   |
| 17      | 23        | 5.57%   |
| 21      | 18        | 4.36%   |
| 12      | 14        | 3.39%   |
| Unknown | 13        | 3.15%   |
| 31      | 10        | 2.42%   |
| 11      | 10        | 2.42%   |
| 19      | 9         | 2.18%   |
| 18      | 8         | 1.94%   |
| 20      | 6         | 1.45%   |
| 34      | 5         | 1.21%   |
| 22      | 5         | 1.21%   |
| 84      | 3         | 0.73%   |
| 28      | 3         | 0.73%   |
| 25      | 3         | 0.73%   |
| 142     | 2         | 0.48%   |
| 72      | 2         | 0.48%   |
| 47      | 2         | 0.48%   |
| 29      | 2         | 0.48%   |
| 55      | 1         | 0.24%   |
| 48      | 1         | 0.24%   |
| 40      | 1         | 0.24%   |
| 38      | 1         | 0.24%   |
| 33      | 1         | 0.24%   |
| 32      | 1         | 0.24%   |
| 16      | 1         | 0.24%   |
| 10      | 1         | 0.24%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 146       | 36.05%  |
| 501-600        | 93        | 22.96%  |
| 201-300        | 49        | 12.1%   |
| 401-500        | 43        | 10.62%  |
| 601-700        | 21        | 5.19%   |
| 351-400        | 20        | 4.94%   |
| Unknown        | 13        | 3.21%   |
| 701-800        | 7         | 1.73%   |
| 1501-2000      | 5         | 1.23%   |
| 1001-1500      | 4         | 0.99%   |
| More than 2000 | 2         | 0.49%   |
| 801-900        | 2         | 0.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 285       | 75.8%   |
| 16/10   | 38        | 10.11%  |
| 5/4     | 13        | 3.46%   |
| Unknown | 12        | 3.19%   |
| 4/3     | 10        | 2.66%   |
| 3/2     | 7         | 1.86%   |
| 21/9    | 7         | 1.86%   |
| 1.00    | 2         | 0.53%   |
| 6/5     | 1         | 0.27%   |
| 1.96    | 1         | 0.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 71        | 17.44%  |
| 101-110        | 71        | 17.44%  |
| 81-90          | 69        | 16.95%  |
| 301-350        | 33        | 8.11%   |
| 71-80          | 23        | 5.65%   |
| 351-500        | 21        | 5.16%   |
| 151-200        | 21        | 5.16%   |
| 251-300        | 18        | 4.42%   |
| 141-150        | 14        | 3.44%   |
| 61-70          | 13        | 3.19%   |
| 121-130        | 13        | 3.19%   |
| Unknown        | 13        | 3.19%   |
| 51-60          | 10        | 2.46%   |
| More than 1000 | 8         | 1.97%   |
| 501-1000       | 5         | 1.23%   |
| 131-140        | 3         | 0.74%   |
| 41-50          | 1         | 0.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 135       | 34.26%  |
| 51-100        | 131       | 33.25%  |
| 101-120       | 70        | 17.77%  |
| 161-240       | 29        | 7.36%   |
| Unknown       | 13        | 3.3%    |
| More than 240 | 8         | 2.03%   |
| 1-50          | 8         | 2.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 278       | 74.13%  |
| 2     | 65        | 17.33%  |
| 0     | 22        | 5.87%   |
| 3     | 9         | 2.4%    |
| 4     | 1         | 0.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 213       | 41.44%  |
| Realtek Semiconductor             | 181       | 35.21%  |
| Qualcomm Atheros                  | 52        | 10.12%  |
| Broadcom                          | 19        | 3.7%    |
| Broadcom Limited                  | 5         | 0.97%   |
| Marvell Technology Group          | 4         | 0.78%   |
| Ralink Technology                 | 3         | 0.58%   |
| Ralink                            | 3         | 0.58%   |
| Ericsson Business Mobile Networks | 3         | 0.58%   |
| Xiaomi                            | 2         | 0.39%   |
| Sierra Wireless                   | 2         | 0.39%   |
| Nvidia                            | 2         | 0.39%   |
| Microsoft                         | 2         | 0.39%   |
| Microchip Technology              | 2         | 0.39%   |
| Edimax Technology                 | 2         | 0.39%   |
| DisplayLink                       | 2         | 0.39%   |
| Dell                              | 2         | 0.39%   |
| D-Link                            | 2         | 0.39%   |
| Cypress Semiconductor             | 2         | 0.39%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.19%   |
| TP-Link                           | 1         | 0.19%   |
| Qualcomm                          | 1         | 0.19%   |
| Mellanox Technologies             | 1         | 0.19%   |
| MEDIATEK                          | 1         | 0.19%   |
| IBM                               | 1         | 0.19%   |
| Huawei Technologies               | 1         | 0.19%   |
| Hewlett-Packard                   | 1         | 0.19%   |
| Fibocom                           | 1         | 0.19%   |
| Attansic Technology               | 1         | 0.19%   |
| American Megatrends               | 1         | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 125       | 20.1%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 25        | 4.02%   |
| Intel Wi-Fi 6 AX200                                                     | 24        | 3.86%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 13        | 2.09%   |
| Intel Wireless 8265 / 8275                                              | 13        | 2.09%   |
| Intel Wireless 8260                                                     | 13        | 2.09%   |
| Intel I211 Gigabit Network Connection                                   | 13        | 2.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 12        | 1.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 11        | 1.77%   |
| Realtek RTL8125 2.5GbE Controller                                       | 10        | 1.61%   |
| Intel Ethernet Connection (2) I219-V                                    | 10        | 1.61%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 10        | 1.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 9         | 1.45%   |
| Intel Wi-Fi 6 AX201                                                     | 9         | 1.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 7         | 1.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 1.13%   |
| Intel Wireless 7260                                                     | 7         | 1.13%   |
| Intel Ethernet Connection (4) I219-V                                    | 7         | 1.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 7         | 1.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 0.96%   |
| Intel Wireless 3165                                                     | 6         | 0.96%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 6         | 0.96%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 0.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 0.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 0.8%    |
| Intel Wireless 7265                                                     | 5         | 0.8%    |
| Intel Ethernet Connection I219-LM                                       | 5         | 0.8%    |
| Intel Ethernet Connection (6) I219-V                                    | 5         | 0.8%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 5         | 0.8%    |
| Intel Centrino Ultimate-N 6300                                          | 5         | 0.8%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 4         | 0.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 0.64%   |
| Intel Wireless 3160                                                     | 4         | 0.64%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 0.64%   |
| Intel I210 Gigabit Network Connection                                   | 4         | 0.64%   |
| Intel Ethernet Connection (4) I219-LM                                   | 4         | 0.64%   |
| Intel Centrino Wireless-N 2230                                          | 4         | 0.64%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 0.48%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 3         | 0.48%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.48%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 3         | 0.48%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 3         | 0.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 3         | 0.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3         | 0.48%   |
| Intel Wireless-AC 9260                                                  | 3         | 0.48%   |
| Intel Ethernet Connection I219-V                                        | 3         | 0.48%   |
| Intel Ethernet Connection I218-LM                                       | 3         | 0.48%   |
| Intel Ethernet Connection I217-V                                        | 3         | 0.48%   |
| Intel Ethernet Connection (2) I218-V                                    | 3         | 0.48%   |
| Intel 82574L Gigabit Network Connection                                 | 3         | 0.48%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 3         | 0.48%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 2         | 0.32%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A                     | 2         | 0.32%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.32%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 2         | 0.32%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.32%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 2         | 0.32%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 2         | 0.32%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.32%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 160       | 60.84%  |
| Qualcomm Atheros      | 39        | 14.83%  |
| Realtek Semiconductor | 35        | 13.31%  |
| Broadcom              | 9         | 3.42%   |
| Ralink Technology     | 3         | 1.14%   |
| Ralink                | 3         | 1.14%   |
| Broadcom Limited      | 3         | 1.14%   |
| Sierra Wireless       | 2         | 0.76%   |
| Microsoft             | 2         | 0.76%   |
| Edimax Technology     | 2         | 0.76%   |
| TP-Link               | 1         | 0.38%   |
| Qualcomm              | 1         | 0.38%   |
| MEDIATEK              | 1         | 0.38%   |
| Fibocom               | 1         | 0.38%   |
| D-Link                | 1         | 0.38%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 24        | 9.09%   |
| Intel Wireless 8265 / 8275                                              | 13        | 4.92%   |
| Intel Wireless 8260                                                     | 13        | 4.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 12        | 4.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 11        | 4.17%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 10        | 3.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 9         | 3.41%   |
| Intel Wi-Fi 6 AX201                                                     | 9         | 3.41%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 2.65%   |
| Intel Wireless 7260                                                     | 7         | 2.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 7         | 2.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 2.27%   |
| Intel Wireless 3165                                                     | 6         | 2.27%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 6         | 2.27%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 2.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 2.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 1.89%   |
| Intel Wireless 7265                                                     | 5         | 1.89%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 5         | 1.89%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 1.89%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 1.52%   |
| Intel Wireless 3160                                                     | 4         | 1.52%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 1.52%   |
| Intel Centrino Wireless-N 2230                                          | 4         | 1.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 1.14%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 3         | 1.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 1.14%   |
| Intel Wireless-AC 9260                                                  | 3         | 1.14%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A                     | 2         | 0.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.76%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.76%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 2         | 0.76%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 0.76%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 0.76%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 2         | 0.76%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 0.76%   |
| TP-Link Archer T4U ver.3                                                | 1         | 0.38%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.38%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.38%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.38%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.38%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 1         | 0.38%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 0.38%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.38%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 0.38%   |
| Realtek 802.11ac NIC                                                    | 1         | 0.38%   |
| Ralink RT5372 Wireless Adapter                                          | 1         | 0.38%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.38%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.38%   |
| Ralink RT5392 PCIe Wireless Network Adapter                             | 1         | 0.38%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.38%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 1         | 0.38%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]             | 1         | 0.38%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.38%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.38%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1         | 0.38%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]     | 1         | 0.38%   |
| MEDIATEK Network controller                                             | 1         | 0.38%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 163       | 48.22%  |
| Intel                    | 120       | 35.5%   |
| Qualcomm Atheros         | 18        | 5.33%   |
| Broadcom                 | 14        | 4.14%   |
| Marvell Technology Group | 4         | 1.18%   |
| Broadcom Limited         | 3         | 0.89%   |
| Xiaomi                   | 2         | 0.59%   |
| Nvidia                   | 2         | 0.59%   |
| Microchip Technology     | 2         | 0.59%   |
| DisplayLink              | 2         | 0.59%   |
| Cypress Semiconductor    | 2         | 0.59%   |
| Mellanox Technologies    | 1         | 0.3%    |
| IBM                      | 1         | 0.3%    |
| Huawei Technologies      | 1         | 0.3%    |
| D-Link                   | 1         | 0.3%    |
| Attansic Technology      | 1         | 0.3%    |
| American Megatrends      | 1         | 0.3%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 125       | 35.82%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 25        | 7.16%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 3.72%   |
| Intel I211 Gigabit Network Connection                             | 13        | 3.72%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10        | 2.87%   |
| Intel Ethernet Connection (2) I219-V                              | 10        | 2.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 2.01%   |
| Intel Ethernet Connection (4) I219-V                              | 7         | 2.01%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.43%   |
| Intel Ethernet Connection (6) I219-V                              | 5         | 1.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4         | 1.15%   |
| Intel I210 Gigabit Network Connection                             | 4         | 1.15%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.15%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.86%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.86%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.86%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.86%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.86%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.86%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.86%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 0.86%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 0.86%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3         | 0.86%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.57%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.57%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.57%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.57%   |
| Nvidia MCP61 Ethernet                                             | 2         | 0.57%   |
| Intel Ethernet Controller 10G X550T                               | 2         | 0.57%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.57%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.57%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.57%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.57%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.57%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 0.57%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.57%   |
| Cypress K38231_03                                                 | 2         | 0.57%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.57%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 0.57%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 2         | 0.57%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.29%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.29%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.29%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 0.29%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.29%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 1         | 0.29%   |
| Microchip LAN9512/LAN9514 Ethernet 10/100 Adapter (SAL10)         | 1         | 0.29%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 1         | 0.29%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.29%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.29%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.29%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.29%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 0.29%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1         | 0.29%   |
| Intel I350 Gigabit Network Connection                             | 1         | 0.29%   |
| Intel Ethernet Virtual Function 700 Series                        | 1         | 0.29%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                  | 1         | 0.29%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1         | 0.29%   |
| Intel Ethernet Connection X722 for 1GbE                           | 1         | 0.29%   |
| Intel Ethernet Connection I354                                    | 1         | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 317       | 54.56%  |
| WiFi     | 255       | 43.89%  |
| Modem    | 9         | 1.55%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 254       | 52.81%  |
| WiFi     | 226       | 46.99%  |
| Modem    | 1         | 0.21%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 195       | 52.28%  |
| 1     | 151       | 40.48%  |
| 3     | 13        | 3.49%   |
| 0     | 9         | 2.41%   |
| 4     | 2         | 0.54%   |
| 13    | 1         | 0.27%   |
| 6     | 1         | 0.27%   |
| 5     | 1         | 0.27%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 292       | 78.07%  |
| Yes  | 82        | 21.93%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 123       | 58.02%  |
| Realtek Semiconductor           | 17        | 8.02%   |
| Qualcomm Atheros Communications | 17        | 8.02%   |
| Broadcom                        | 12        | 5.66%   |
| Cambridge Silicon Radio         | 11        | 5.19%   |
| Lite-On Technology              | 7         | 3.3%    |
| IMC Networks                    | 4         | 1.89%   |
| ASUSTek Computer                | 4         | 1.89%   |
| Apple                           | 4         | 1.89%   |
| Realtek                         | 3         | 1.42%   |
| Foxconn / Hon Hai               | 3         | 1.42%   |
| Toshiba                         | 2         | 0.94%   |
| Dell                            | 2         | 0.94%   |
| Taiyo Yuden                     | 1         | 0.47%   |
| Ralink                          | 1         | 0.47%   |
| Hewlett-Packard                 | 1         | 0.47%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 44        | 20.75%  |
| Intel AX201 Bluetooth                               | 25        | 11.79%  |
| Intel AX200 Bluetooth                               | 24        | 11.32%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 15        | 7.08%   |
| Realtek Bluetooth Radio                             | 13        | 6.13%   |
| Qualcomm Atheros  Bluetooth Device                  | 11        | 5.19%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 11        | 5.19%   |
| Intel Wireless-AC 3168 Bluetooth                    | 6         | 2.83%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 5         | 2.36%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 1.89%   |
| Realtek Bluetooth Radio                             | 3         | 1.42%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.42%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.42%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.42%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 1.42%   |
| Toshiba Bluetooth Device                            | 2         | 0.94%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 0.94%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.94%   |
| Lite-On Bluetooth Device                            | 2         | 0.94%   |
| IMC Networks Bluetooth Radio                        | 2         | 0.94%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.94%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 0.94%   |
| Apple Bluetooth USB Host Controller                 | 2         | 0.94%   |
| Apple Bluetooth Host Controller                     | 2         | 0.94%   |
| Taiyo Yuden Bluetooth Device                        | 1         | 0.47%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.47%   |
| Realtek CSR BS8510                                  | 1         | 0.47%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.47%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.47%   |
| Lite-On Wireless_Device                             | 1         | 0.47%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.47%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.47%   |
| Intel Bluetooth Device                              | 1         | 0.47%   |
| IMC Networks Bluetooth Device                       | 1         | 0.47%   |
| IMC Networks Bluetooth                              | 1         | 0.47%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.47%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 0.47%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.47%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 0.47%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.47%   |
| Broadcom Bluetooth 3.0 Device                       | 1         | 0.47%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 0.47%   |
| Broadcom BCM2035 Bluetooth dongle                   | 1         | 0.47%   |
| ASUS Bluetooth Radio                                | 1         | 0.47%   |
| ASUS Bluetooth Adapter                              | 1         | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 263       | 51.57%  |
| AMD                        | 103       | 20.2%   |
| Nvidia                     | 81        | 15.88%  |
| C-Media Electronics        | 14        | 2.75%   |
| Generalplus Technology     | 6         | 1.18%   |
| Logitech                   | 5         | 0.98%   |
| GYROCOM C&C                | 4         | 0.78%   |
| Creative Labs              | 4         | 0.78%   |
| Texas Instruments          | 3         | 0.59%   |
| GN Netcom                  | 3         | 0.59%   |
| Samson Technologies        | 2         | 0.39%   |
| Plantronics                | 2         | 0.39%   |
| BEHRINGER International    | 2         | 0.39%   |
| XMOS                       | 1         | 0.2%    |
| VIA Technologies           | 1         | 0.2%    |
| TEAC                       | 1         | 0.2%    |
| SteelSeries ApS            | 1         | 0.2%    |
| RODE Microphones           | 1         | 0.2%    |
| ROCCAT                     | 1         | 0.2%    |
| Razer USA                  | 1         | 0.2%    |
| PreSonus Audio Electronics | 1         | 0.2%    |
| Hewlett-Packard            | 1         | 0.2%    |
| Hangzhou Worlde            | 1         | 0.2%    |
| Dell                       | 1         | 0.2%    |
| Creative Technology        | 1         | 0.2%    |
| Blue Microphones           | 1         | 0.2%    |
| AXELVOX                    | 1         | 0.2%    |
| AVID Technology            | 1         | 0.2%    |
| Audioengine                | 1         | 0.2%    |
| ASUSTek Computer           | 1         | 0.2%    |
| Alesis                     | 1         | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 38        | 6.39%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 32        | 5.38%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 27        | 4.54%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 27        | 4.54%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 18        | 3.03%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 15        | 2.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 15        | 2.52%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 15        | 2.52%   |
| Intel 200 Series PCH HD Audio                                                                     | 14        | 2.35%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 14        | 2.35%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 13        | 2.18%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 12        | 2.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12        | 2.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 11        | 1.85%   |
| Intel Comet Lake PCH cAVS                                                                         | 10        | 1.68%   |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 1.68%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 10        | 1.68%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10        | 1.68%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 10        | 1.68%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 1.51%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 9         | 1.51%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 1.51%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 8         | 1.34%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 8         | 1.34%   |
| AMD FCH Azalia Controller                                                                         | 8         | 1.34%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 1.18%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 1.18%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 1.18%   |
| AMD Navi 10 HDMI Audio                                                                            | 7         | 1.18%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 6         | 1.01%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 1.01%   |
| Generalplus Technology USB Audio Device                                                           | 6         | 1.01%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 5         | 0.84%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 5         | 0.84%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 0.84%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 5         | 0.84%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 0.67%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 4         | 0.67%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 4         | 0.67%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 0.67%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 4         | 0.67%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.5%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 3         | 0.5%    |
| Nvidia TU104 HD Audio Controller                                                                  | 3         | 0.5%    |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.5%    |
| Nvidia GK104 HDMI Audio Controller                                                                | 3         | 0.5%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 0.5%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.5%    |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 3         | 0.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.5%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 3         | 0.5%    |
| GYROCOM C&C Fiio E10                                                                              | 3         | 0.5%    |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 3         | 0.5%    |
| Texas Instruments PCM2912A Audio Codec                                                            | 2         | 0.34%   |
| Nvidia MCP61 High Definition Audio                                                                | 2         | 0.34%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.34%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 2         | 0.34%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 0.34%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.34%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 2         | 0.34%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 75        | 18.99%  |
| Samsung Electronics | 72        | 18.23%  |
| Kingston            | 55        | 13.92%  |
| Unknown             | 39        | 9.87%   |
| Crucial             | 33        | 8.35%   |
| Micron Technology   | 31        | 7.85%   |
| Corsair             | 27        | 6.84%   |
| G.Skill             | 14        | 3.54%   |
| A-DATA Technology   | 12        | 3.04%   |
| Ramaxel Technology  | 8         | 2.03%   |
| Elpida              | 5         | 1.27%   |
| Team                | 4         | 1.01%   |
| Patriot             | 3         | 0.76%   |
| Nanya Technology    | 3         | 0.76%   |
| Kllisre             | 3         | 0.76%   |
| Unknown (ABCD)      | 2         | 0.51%   |
| GOODRAM             | 2         | 0.51%   |
| V-Color             | 1         | 0.25%   |
| Unifosa             | 1         | 0.25%   |
| SMART Brazil        | 1         | 0.25%   |
| Smart               | 1         | 0.25%   |
| PNY                 | 1         | 0.25%   |
| Kingmax             | 1         | 0.25%   |
| GeIL                | 1         | 0.25%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 4         | 0.93%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 4         | 0.93%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s           | 4         | 0.93%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16384MB SODIMM DDR4 2667MT/s       | 3         | 0.7%    |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 0.7%    |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 3         | 0.7%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.7%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.7%    |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 3         | 0.7%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 0.7%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.7%    |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 3         | 0.7%    |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 3         | 0.7%    |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s            | 3         | 0.7%    |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3466MT/s            | 3         | 0.7%    |
| Unknown RAM Module 512MB SODIMM DDR2 400MT/s                     | 2         | 0.46%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 2         | 0.46%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 2         | 0.46%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 2         | 0.46%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                         | 2         | 0.46%   |
| Unknown RAM 99[2/7/4]164(F/R) 4GB DIMM DDR3 1600MT/s             | 2         | 0.46%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.46%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.46%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.46%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.46%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.46%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 0.46%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 0.46%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.46%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 2         | 0.46%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2133MT/s        | 2         | 0.46%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.46%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.46%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.46%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 2         | 0.46%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 0.46%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.46%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.46%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4096MB SODIMM DDR4 2667MT/s     | 2         | 0.46%   |
| Micron RAM MT52L512M32D2PF-09 4GB Row Of Chips LPDDR3 2133MT/s   | 2         | 0.46%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.46%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 2         | 0.46%   |
| Kllisre RAM KRE-D3U1600M/8G 8GB DIMM DDR3 1600MT/s               | 2         | 0.46%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3200MT/s                | 2         | 0.46%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s                | 2         | 0.46%   |
| Kingston RAM KHX2400C14S4/16G 16GB SODIMM DDR4 2667MT/s          | 2         | 0.46%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s              | 2         | 0.46%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1867MT/s              | 2         | 0.46%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s              | 2         | 0.46%   |
| Kingston RAM 99U5469-046.A00LF 4GB SODIMM DDR3 1333MT/s          | 2         | 0.46%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s           | 2         | 0.46%   |
| G.Skill RAM F4-3200C16-16GTZSK 16GB DIMM DDR4 3200MT/s           | 2         | 0.46%   |
| Crucial RAM CT8G4SFRA32A.C8FE 8GB SODIMM DDR4 3200MT/s           | 2         | 0.46%   |
| Crucial RAM CT102464BD160B.C16 8GB DIMM DDR3 1600MT/s            | 2         | 0.46%   |
| Corsair RAM CMSO8GX3M1C1600C11 8192MB SODIMM DDR3 1600MT/s       | 2         | 0.46%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s            | 2         | 0.46%   |
| V-Color RAM TD4G16C11-H11 4GB DIMM DDR3 1333MT/s                 | 1         | 0.23%   |
| Unknown SODIMM 2GB SODIMM DDR2 667MT/s                           | 1         | 0.23%   |
| Unknown SODIMM 2GB SODIMM DDR2 533MT/s                           | 1         | 0.23%   |
| Unknown SODIMM 1GB SODIMM DDR2 533MT/s                           | 1         | 0.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 175       | 51.78%  |
| DDR3    | 115       | 34.02%  |
| DDR2    | 14        | 4.14%   |
| LPDDR3  | 11        | 3.25%   |
| LPDDR4  | 8         | 2.37%   |
| SDRAM   | 7         | 2.07%   |
| Unknown | 7         | 2.07%   |
| DDR     | 1         | 0.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 180       | 53.41%  |
| DIMM         | 132       | 39.17%  |
| Row Of Chips | 21        | 6.23%   |
| Chip         | 2         | 0.59%   |
| RIMM         | 1         | 0.3%    |
| Unknown      | 1         | 0.3%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 139       | 37.77%  |
| 4096  | 96        | 26.09%  |
| 16384 | 59        | 16.03%  |
| 2048  | 36        | 9.78%   |
| 32768 | 16        | 4.35%   |
| 1024  | 15        | 4.08%   |
| 512   | 4         | 1.09%   |
| 256   | 2         | 0.54%   |
| 65536 | 1         | 0.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 83        | 22.13%  |
| 2667    | 65        | 17.33%  |
| 3200    | 54        | 14.4%   |
| 1333    | 33        | 8.8%    |
| 2400    | 32        | 8.53%   |
| 2133    | 22        | 5.87%   |
| 1334    | 11        | 2.93%   |
| 3600    | 10        | 2.67%   |
| 1867    | 7         | 1.87%   |
| 800     | 6         | 1.6%    |
| 2933    | 5         | 1.33%   |
| 667     | 5         | 1.33%   |
| 400     | 5         | 1.33%   |
| Unknown | 4         | 1.07%   |
| 4267    | 3         | 0.8%    |
| 3466    | 3         | 0.8%    |
| 2666    | 3         | 0.8%    |
| 1866    | 3         | 0.8%    |
| 1067    | 3         | 0.8%    |
| 3400    | 2         | 0.53%   |
| 3000    | 2         | 0.53%   |
| 533     | 2         | 0.53%   |
| 4266    | 1         | 0.27%   |
| 4199    | 1         | 0.27%   |
| 3533    | 1         | 0.27%   |
| 3500    | 1         | 0.27%   |
| 3100    | 1         | 0.27%   |
| 3066    | 1         | 0.27%   |
| 2465    | 1         | 0.27%   |
| 2000    | 1         | 0.27%   |
| 1800    | 1         | 0.27%   |
| 1066    | 1         | 0.27%   |
| 975     | 1         | 0.27%   |
| 333     | 1         | 0.27%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 57.14%  |
| Canon               | 2         | 28.57%  |
| Samsung Electronics | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Samsung ML-1660 Series | 1         | 14.29%  |
| HP LaserJet P1006      | 1         | 14.29%  |
| HP LaserJet M101-M106  | 1         | 14.29%  |
| HP LaserJet 1200       | 1         | 14.29%  |
| HP ENVY 4520 series    | 1         | 14.29%  |
| Canon LiDE 400         | 1         | 14.29%  |
| Canon iP2700 series    | 1         | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Canon       | 2         | 66.67%  |
| Seiko Epson | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20            | 2         | 66.67%  |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 39        | 17.89%  |
| IMC Networks                           | 31        | 14.22%  |
| Acer                                   | 24        | 11.01%  |
| Microdia                               | 21        | 9.63%   |
| Logitech                               | 16        | 7.34%   |
| Realtek Semiconductor                  | 15        | 6.88%   |
| Lite-On Technology                     | 11        | 5.05%   |
| Quanta                                 | 9         | 4.13%   |
| Sunplus Innovation Technology          | 8         | 3.67%   |
| Suyin                                  | 5         | 2.29%   |
| Syntek                                 | 4         | 1.83%   |
| Luxvisions Innotech Limited            | 4         | 1.83%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 1.83%   |
| Apple                                  | 4         | 1.83%   |
| Samsung Electronics                    | 3         | 1.38%   |
| Z-Star Microelectronics                | 2         | 0.92%   |
| Genesys Logic                          | 2         | 0.92%   |
| Generalplus Technology                 | 2         | 0.92%   |
| eMPIA Technology                       | 2         | 0.92%   |
| Xiongmai                               | 1         | 0.46%   |
| SiGma Micro                            | 1         | 0.46%   |
| Razer USA                              | 1         | 0.46%   |
| Pixart Imaging                         | 1         | 0.46%   |
| Lenovo                                 | 1         | 0.46%   |
| Huawei Technologies                    | 1         | 0.46%   |
| Hewlett-Packard                        | 1         | 0.46%   |
| AVerMedia Technologies                 | 1         | 0.46%   |
| ARC International                      | 1         | 0.46%   |
| ALi                                    | 1         | 0.46%   |
| Alcor Micro                            | 1         | 0.46%   |
| A4Tech                                 | 1         | 0.46%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 15        | 6.85%   |
| IMC Networks Integrated Camera           | 12        | 5.48%   |
| Microdia Integrated_Webcam_HD            | 10        | 4.57%   |
| Acer Integrated Camera                   | 9         | 4.11%   |
| Realtek Integrated_Webcam_HD             | 7         | 3.2%    |
| IMC Networks USB2.0 HD UVC WebCam        | 7         | 3.2%    |
| Chicony HP HD Camera                     | 5         | 2.28%   |
| Chicony HD Webcam                        | 5         | 2.28%   |
| Acer SunplusIT Integrated Camera         | 5         | 2.28%   |
| Lite-On Integrated Camera                | 4         | 1.83%   |
| Samsung Galaxy A5 (MTP)                  | 3         | 1.37%   |
| Microdia Webcam Vitade AF                | 3         | 1.37%   |
| Logitech Webcam C270                     | 3         | 1.37%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 3         | 1.37%   |
| IMC Networks USB2.0 HD IR UVC WebCam     | 3         | 1.37%   |
| Syntek Integrated Camera                 | 2         | 0.91%   |
| Sunplus Integrated_Webcam_HD             | 2         | 0.91%   |
| Realtek Integrated Webcam                | 2         | 0.91%   |
| Realtek EasyCamera                       | 2         | 0.91%   |
| Quanta HD Webcam                         | 2         | 0.91%   |
| Microdia USB Live camera                 | 2         | 0.91%   |
| Microdia Integrated Webcam HD            | 2         | 0.91%   |
| Luxvisions Innotech Limited HP HD Camera | 2         | 0.91%   |
| Logitech HD Webcam C910                  | 2         | 0.91%   |
| Logitech HD Webcam C615                  | 2         | 0.91%   |
| Logitech HD Pro Webcam C920              | 2         | 0.91%   |
| Logitech C505 HD Webcam                  | 2         | 0.91%   |
| Lite-On HP Webcam                        | 2         | 0.91%   |
| Lite-On HP HD Camera                     | 2         | 0.91%   |
| IMC Networks ov9734_azurewave_camera     | 2         | 0.91%   |
| IMC Networks Lenovo EasyCamera           | 2         | 0.91%   |
| Chicony Lenovo EasyCamera                | 2         | 0.91%   |
| Chicony HP HD Webcam                     | 2         | 0.91%   |
| Apple FaceTime HD Camera                 | 2         | 0.91%   |
| Acer ThinkPad Integrated Camera          | 2         | 0.91%   |
| Acer Lenovo Integrated Webcam            | 2         | 0.91%   |
| Acer EasyCamera                          | 2         | 0.91%   |
| Z-Star Venus USB2.0 Camera               | 1         | 0.46%   |
| Z-Star Sirius USB2.0 Camera              | 1         | 0.46%   |
| Xiongmai web camera                      | 1         | 0.46%   |
| Syntek USB 2.0 UVC PC Camera             | 1         | 0.46%   |
| Syntek Lenovo EasyCamera                 | 1         | 0.46%   |
| Suyin Laptop_Integrated_Webcam_HD        | 1         | 0.46%   |
| Suyin HP TrueVision HD Integrated Webcam | 1         | 0.46%   |
| Suyin HP TrueVision Full HD              | 1         | 0.46%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 1         | 0.46%   |
| Suyin Acer CrystalEye Webcam             | 1         | 0.46%   |
| Sunplus Laptop_Integrated_Webcam_HD      | 1         | 0.46%   |
| Sunplus Laptop_Integrated_Webcam_FHD     | 1         | 0.46%   |
| Sunplus Laptop Integrated Webcam FHD     | 1         | 0.46%   |
| Sunplus HD USB Camaer 4K                 | 1         | 0.46%   |
| Sunplus Dell E5570 integrated webcam     | 1         | 0.46%   |
| Sunplus 1.3M HD WebCam                   | 1         | 0.46%   |
| SiGma Micro WebCam SiGma Micro           | 1         | 0.46%   |
| Realtek USB Camera                       | 1         | 0.46%   |
| Realtek Lenovo EasyCamera                | 1         | 0.46%   |
| Realtek HD WebCam                        | 1         | 0.46%   |
| Realtek Acer 640 x 480 laptop camera     | 1         | 0.46%   |
| Razer USA Razer Kiyo                     | 1         | 0.46%   |
| Quanta VGA WebCam                        | 1         | 0.46%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 18        | 39.13%  |
| Validity Sensors           | 10        | 21.74%  |
| Shenzhen Goodix Technology | 9         | 19.57%  |
| Upek                       | 3         | 6.52%   |
| Elan Microelectronics      | 3         | 6.52%   |
| AuthenTec                  | 2         | 4.35%   |
| LighTuning Technology      | 1         | 2.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 7         | 15.22%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 10.87%  |
| Shenzhen Goodix  Fingerprint Device                                        | 5         | 10.87%  |
| Shenzhen Goodix FingerPrint                                                | 4         | 8.7%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 6.52%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 6.52%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 6.52%   |
| Elan ELAN:Fingerprint                                                      | 3         | 6.52%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 4.35%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 4.35%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 4.35%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.17%   |
| Synaptics  WBDI                                                            | 1         | 2.17%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 2.17%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 2.17%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 2.17%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 2.17%   |
| Unknown                                                                    | 1         | 2.17%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 8         | 32%     |
| Broadcom              | 7         | 28%     |
| Lenovo                | 4         | 16%     |
| Upek                  | 3         | 12%     |
| Yubico.com            | 1         | 4%      |
| O2 Micro              | 1         | 4%      |
| Gemalto (was Gemplus) | 1         | 4%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 8         | 32%     |
| Lenovo Integrated Smart Card Reader                                          | 4         | 16%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 12%     |
| Broadcom 58200                                                               | 3         | 12%     |
| Broadcom 5880                                                                | 2         | 8%      |
| Yubico.com Yubikey 4 CCID                                                    | 1         | 4%      |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 4%      |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 4%      |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 4%      |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 4%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 283       | 75.27%  |
| 1     | 65        | 17.29%  |
| 2     | 24        | 6.38%   |
| 5     | 2         | 0.53%   |
| 4     | 1         | 0.27%   |
| 3     | 1         | 0.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 46        | 38.66%  |
| Graphics card            | 20        | 16.81%  |
| Chipcard                 | 19        | 15.97%  |
| Multimedia controller    | 8         | 6.72%   |
| Net/wireless             | 7         | 5.88%   |
| Communication controller | 6         | 5.04%   |
| Unassigned class         | 4         | 3.36%   |
| Storage                  | 3         | 2.52%   |
| Sound                    | 1         | 0.84%   |
| Network                  | 1         | 0.84%   |
| Modem                    | 1         | 0.84%   |
| Firewire controller      | 1         | 0.84%   |
| Card reader              | 1         | 0.84%   |
| Bluetooth                | 1         | 0.84%   |

